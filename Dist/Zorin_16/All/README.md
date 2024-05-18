Zorin 16 - Tested Hardware & Statistics
---------------------------------------

A project to collect tested hardware configurations for Zorin 16.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Zorin_16/Desktop/README.md) and [notebooks](/Dist/Zorin_16/Notebook/README.md).

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

Total: 6287

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad Edge E530c 3366... | Notebook    | [d4d583a573](https://linux-hardware.org/?probe=d4d583a573) | May 07, 2024 |
| Intel         | H55                         | Desktop     | [83c1ac4239](https://linux-hardware.org/?probe=83c1ac4239) | May 07, 2024 |
| Fujitsu       | LIFEBOOK U7510              | Notebook    | [a52ed98e85](https://linux-hardware.org/?probe=a52ed98e85) | May 07, 2024 |
| SCHNEIDER     | SCL141CTP                   | Notebook    | [ce0a785c29](https://linux-hardware.org/?probe=ce0a785c29) | May 07, 2024 |
| Dell          | 0M5DCD A00                  | Desktop     | [f390e47ea1](https://linux-hardware.org/?probe=f390e47ea1) | May 03, 2024 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [257f9cdad4](https://linux-hardware.org/?probe=257f9cdad4) | May 03, 2024 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [1a3ebd462f](https://linux-hardware.org/?probe=1a3ebd462f) | May 02, 2024 |
| HP            | Pavilion Notebook           | Notebook    | [2fc15c8d5c](https://linux-hardware.org/?probe=2fc15c8d5c) | May 02, 2024 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [fcd6ae5579](https://linux-hardware.org/?probe=fcd6ae5579) | May 02, 2024 |
| Lenovo        | ThinkPad X200s 7469W92      | Notebook    | [687cc00e33](https://linux-hardware.org/?probe=687cc00e33) | May 01, 2024 |
| Dell          | System Vostro 3450          | Notebook    | [eede1fda8a](https://linux-hardware.org/?probe=eede1fda8a) | Apr 30, 2024 |
| Lenovo        | B50-80 80EW                 | Notebook    | [5f20d3fde3](https://linux-hardware.org/?probe=5f20d3fde3) | Apr 29, 2024 |
| HP            | ProBook 450 G1              | Notebook    | [9c5d161110](https://linux-hardware.org/?probe=9c5d161110) | Apr 28, 2024 |
| AOpen         | D1009 A1A4                  | Desktop     | [f5399e68ef](https://linux-hardware.org/?probe=f5399e68ef) | Apr 27, 2024 |
| ASUSTek       | M4A78 PRO                   | Desktop     | [4a79911a5b](https://linux-hardware.org/?probe=4a79911a5b) | Apr 24, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [12f44c7a5a](https://linux-hardware.org/?probe=12f44c7a5a) | Apr 23, 2024 |
| Lenovo        | 3098 SDK0E50510 WIN         | Desktop     | [6f1ba910cd](https://linux-hardware.org/?probe=6f1ba910cd) | Apr 23, 2024 |
| Acer          | Aspire E5-575T              | Notebook    | [d91600e2a3](https://linux-hardware.org/?probe=d91600e2a3) | Apr 22, 2024 |
| Dell          | XPS MXC062                  | Notebook    | [3d7326b94d](https://linux-hardware.org/?probe=3d7326b94d) | Apr 22, 2024 |
| Dell          | XPS MXC062                  | Notebook    | [d217b8e5ee](https://linux-hardware.org/?probe=d217b8e5ee) | Apr 22, 2024 |
| ASUSTek       | K75VM                       | Notebook    | [c863c3ba6b](https://linux-hardware.org/?probe=c863c3ba6b) | Apr 21, 2024 |
| Mediacom      | SmartBook Pro i5            | Notebook    | [fdc40cdd18](https://linux-hardware.org/?probe=fdc40cdd18) | Apr 19, 2024 |
| AXDIA Inte... | MAVEN WIN 12 PRO            | Tablet      | [963dab8edc](https://linux-hardware.org/?probe=963dab8edc) | Apr 19, 2024 |
| Dell          | Latitude E5420              | Notebook    | [f937473451](https://linux-hardware.org/?probe=f937473451) | Apr 19, 2024 |
| Acer          | Aspire A515-43              | Notebook    | [fcd5e8e59d](https://linux-hardware.org/?probe=fcd5e8e59d) | Apr 16, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [b3fc204759](https://linux-hardware.org/?probe=b3fc204759) | Apr 14, 2024 |
| Dell          | XPS 15 9550                 | Notebook    | [22d857c49c](https://linux-hardware.org/?probe=22d857c49c) | Apr 14, 2024 |
| Dell          | Latitude 3440               | Notebook    | [e334ba82e5](https://linux-hardware.org/?probe=e334ba82e5) | Apr 14, 2024 |
| Dell          | Latitude 3440               | Notebook    | [77e2af784e](https://linux-hardware.org/?probe=77e2af784e) | Apr 14, 2024 |
| HP            | Pavilion dv6000 (GM695LA... | Notebook    | [21796df3a5](https://linux-hardware.org/?probe=21796df3a5) | Apr 14, 2024 |
| ASUSTek       | E402SA                      | Notebook    | [5266b4e65d](https://linux-hardware.org/?probe=5266b4e65d) | Apr 13, 2024 |
| ASUSTek       | N552VW                      | Notebook    | [02c36db055](https://linux-hardware.org/?probe=02c36db055) | Apr 12, 2024 |
| ASUSTek       | P8Z68-V GEN3                | Desktop     | [39d3eeda79](https://linux-hardware.org/?probe=39d3eeda79) | Apr 12, 2024 |
| Lenovo        | G550 2958                   | Notebook    | [2cebfc34df](https://linux-hardware.org/?probe=2cebfc34df) | Apr 12, 2024 |
| Lenovo        | ThinkPad T520 4243F53       | Notebook    | [9996ba8710](https://linux-hardware.org/?probe=9996ba8710) | Apr 12, 2024 |
| ASUSTek       | N552VW                      | Notebook    | [981a9ddf63](https://linux-hardware.org/?probe=981a9ddf63) | Apr 11, 2024 |
| ASUSTek       | CM6870                      | Desktop     | [0c29f72def](https://linux-hardware.org/?probe=0c29f72def) | Apr 10, 2024 |
| Dell          | 0XCR8D A01                  | Desktop     | [9d38e92df0](https://linux-hardware.org/?probe=9d38e92df0) | Apr 09, 2024 |
| Dell          | 0XCR8D A01                  | Desktop     | [a0b8193ba4](https://linux-hardware.org/?probe=a0b8193ba4) | Apr 09, 2024 |
| Dell          | 0VYXHD A00                  | Desktop     | [c0cfa74664](https://linux-hardware.org/?probe=c0cfa74664) | Apr 09, 2024 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | Notebook    | [b87b1a20b9](https://linux-hardware.org/?probe=b87b1a20b9) | Apr 06, 2024 |
| MSI           | GT70 2PE                    | Notebook    | [13f21446e0](https://linux-hardware.org/?probe=13f21446e0) | Apr 06, 2024 |
| Acer          | Aspire 5750                 | Notebook    | [ee4bb4963a](https://linux-hardware.org/?probe=ee4bb4963a) | Apr 04, 2024 |
| Dell          | Latitude E7470              | Notebook    | [ea70b2caa0](https://linux-hardware.org/?probe=ea70b2caa0) | Apr 04, 2024 |
| MSI           | H81M-E34                    | Desktop     | [62882b5228](https://linux-hardware.org/?probe=62882b5228) | Apr 02, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [cccef069f7](https://linux-hardware.org/?probe=cccef069f7) | Apr 01, 2024 |
| Dell          | Latitude 7480               | Notebook    | [0ab21a354e](https://linux-hardware.org/?probe=0ab21a354e) | Mar 31, 2024 |
| HP            | 15                          | Notebook    | [e1c7ccf97a](https://linux-hardware.org/?probe=e1c7ccf97a) | Mar 31, 2024 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [740eb90402](https://linux-hardware.org/?probe=740eb90402) | Mar 30, 2024 |
| Lenovo        | ThinkPad Yoga 370 20JJS0... | Convertible | [2436c8e791](https://linux-hardware.org/?probe=2436c8e791) | Mar 29, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [00e4cbdc6e](https://linux-hardware.org/?probe=00e4cbdc6e) | Mar 29, 2024 |
| Lenovo        | ThinkPad E470 20H1006KGE    | Notebook    | [494ac5439c](https://linux-hardware.org/?probe=494ac5439c) | Mar 28, 2024 |
| Dell          | Inspiron 5537               | Notebook    | [f081fc7478](https://linux-hardware.org/?probe=f081fc7478) | Mar 26, 2024 |
| Dell          | Inspiron 5537               | Notebook    | [bbe46521b3](https://linux-hardware.org/?probe=bbe46521b3) | Mar 26, 2024 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [a549e35cf7](https://linux-hardware.org/?probe=a549e35cf7) | Mar 26, 2024 |
| Toshiba       | Satellite L355D             | Notebook    | [fd8ddd8b99](https://linux-hardware.org/?probe=fd8ddd8b99) | Mar 25, 2024 |
| HP            | 3029h                       | Desktop     | [1913f87768](https://linux-hardware.org/?probe=1913f87768) | Mar 25, 2024 |
| HP            | 8767 A                      | Desktop     | [167796eedc](https://linux-hardware.org/?probe=167796eedc) | Mar 25, 2024 |
| Fujitsu       | LIFEBOOK S760               | Notebook    | [9ef9218d97](https://linux-hardware.org/?probe=9ef9218d97) | Mar 24, 2024 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [f8ca0e66e2](https://linux-hardware.org/?probe=f8ca0e66e2) | Mar 24, 2024 |
| Lenovo        | ThinkPad X230 2325PB3       | Notebook    | [399c0cd75c](https://linux-hardware.org/?probe=399c0cd75c) | Mar 23, 2024 |
| HP            | 15                          | Notebook    | [139e556699](https://linux-hardware.org/?probe=139e556699) | Mar 23, 2024 |
| Positivo      | Q232A                       | Notebook    | [46c3ff72eb](https://linux-hardware.org/?probe=46c3ff72eb) | Mar 23, 2024 |
| Positivo      | Q232A                       | Notebook    | [924bb4b4ee](https://linux-hardware.org/?probe=924bb4b4ee) | Mar 23, 2024 |
| MSI           | H81M-E34                    | Desktop     | [5ab741f203](https://linux-hardware.org/?probe=5ab741f203) | Mar 21, 2024 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [f7f667d127](https://linux-hardware.org/?probe=f7f667d127) | Mar 21, 2024 |
| Google        | Magma                       | Notebook    | [8fe3986816](https://linux-hardware.org/?probe=8fe3986816) | Mar 20, 2024 |
| Intel         | DQ45CB AAE30148-207         | Desktop     | [779eb3b38f](https://linux-hardware.org/?probe=779eb3b38f) | Mar 20, 2024 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [9ce06e146a](https://linux-hardware.org/?probe=9ce06e146a) | Mar 19, 2024 |
| Apple         | Mac-F2218EA9                | All in one  | [04aea2f042](https://linux-hardware.org/?probe=04aea2f042) | Mar 19, 2024 |
| HP            | Compaq 6715s (KE068ET#AB... | Notebook    | [93f757d8b3](https://linux-hardware.org/?probe=93f757d8b3) | Mar 18, 2024 |
| Dell          | 0T656F A01                  | Desktop     | [325c5efb6e](https://linux-hardware.org/?probe=325c5efb6e) | Mar 18, 2024 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [6477033da6](https://linux-hardware.org/?probe=6477033da6) | Mar 18, 2024 |
| eMachines     | MCP61PM-GM                  | Desktop     | [c92849e391](https://linux-hardware.org/?probe=c92849e391) | Mar 18, 2024 |
| ASUSTek       | K42F                        | Notebook    | [f36df8e399](https://linux-hardware.org/?probe=f36df8e399) | Mar 18, 2024 |
| Chuwi         | Hi10 X                      | Tablet      | [e746a7b752](https://linux-hardware.org/?probe=e746a7b752) | Mar 17, 2024 |
| HP            | Pavilion dv6000 (GF677EA... | Notebook    | [ecbe5ffb1f](https://linux-hardware.org/?probe=ecbe5ffb1f) | Mar 16, 2024 |
| Dell          | 0M9KCM A02                  | Desktop     | [7823cafa72](https://linux-hardware.org/?probe=7823cafa72) | Mar 15, 2024 |
| Dell          | 0M9KCM A02                  | Desktop     | [6dd5b76d21](https://linux-hardware.org/?probe=6dd5b76d21) | Mar 15, 2024 |
| Apple         | MacBook5,2                  | Notebook    | [e482eea403](https://linux-hardware.org/?probe=e482eea403) | Mar 13, 2024 |
| Apple         | MacBook5,2                  | Notebook    | [7e0aa86d1c](https://linux-hardware.org/?probe=7e0aa86d1c) | Mar 13, 2024 |
| Supermicro    | C7Q67 V1.01                 | Desktop     | [4fe003a84f](https://linux-hardware.org/?probe=4fe003a84f) | Mar 13, 2024 |
| Chuwi         | UBook X                     | Tablet      | [bab0a4bcb7](https://linux-hardware.org/?probe=bab0a4bcb7) | Mar 12, 2024 |
| Chuwi         | UBook X                     | Tablet      | [5bc5d0dcde](https://linux-hardware.org/?probe=5bc5d0dcde) | Mar 12, 2024 |
| Fujitsu       | LIFEBOOK U7510              | Notebook    | [b78e24d0f3](https://linux-hardware.org/?probe=b78e24d0f3) | Mar 11, 2024 |
| HP            | ProBook 650 G2              | Notebook    | [532a823ad7](https://linux-hardware.org/?probe=532a823ad7) | Mar 11, 2024 |
| HP            | ProBook 450 G6              | Notebook    | [6fb4193bc2](https://linux-hardware.org/?probe=6fb4193bc2) | Mar 10, 2024 |
| Acer          | Aspire 9410                 | Notebook    | [3307f5eede](https://linux-hardware.org/?probe=3307f5eede) | Mar 09, 2024 |
| HP            | 1000                        | Notebook    | [12df954c4d](https://linux-hardware.org/?probe=12df954c4d) | Mar 09, 2024 |
| Foxconn       | 946 7MA Series              | Desktop     | [7453cdde18](https://linux-hardware.org/?probe=7453cdde18) | Mar 09, 2024 |
| HP            | Compaq 6715s (KE068ET#AB... | Notebook    | [bd5a3177a0](https://linux-hardware.org/?probe=bd5a3177a0) | Mar 09, 2024 |
| Biostar       | G41-M7                      | Desktop     | [54836e3fbe](https://linux-hardware.org/?probe=54836e3fbe) | Mar 08, 2024 |
| HP            | Laptop 15s-du3xxx           | Notebook    | [d3e9bec32e](https://linux-hardware.org/?probe=d3e9bec32e) | Mar 08, 2024 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [b18d2c6cab](https://linux-hardware.org/?probe=b18d2c6cab) | Mar 08, 2024 |
| ASUSTek       | X205TAW                     | Notebook    | [6ed323ca5c](https://linux-hardware.org/?probe=6ed323ca5c) | Mar 07, 2024 |
| ASUSTek       | X205TAW                     | Notebook    | [2dd874e62c](https://linux-hardware.org/?probe=2dd874e62c) | Mar 07, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [e545b12914](https://linux-hardware.org/?probe=e545b12914) | Mar 07, 2024 |
| HP            | ZBook Fury 17.3 inch G8 ... | Notebook    | [0111e861f4](https://linux-hardware.org/?probe=0111e861f4) | Mar 07, 2024 |
| Apple         | Mac-F22C86C8                | Mini pc     | [523b960a7e](https://linux-hardware.org/?probe=523b960a7e) | Mar 06, 2024 |
| Acer          | Aspire M3-581G              | Notebook    | [7ab92d79ee](https://linux-hardware.org/?probe=7ab92d79ee) | Mar 06, 2024 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [06c5a79ab1](https://linux-hardware.org/?probe=06c5a79ab1) | Mar 06, 2024 |
| TongFang      | GM7PX0N                     | Notebook    | [632d2a6962](https://linux-hardware.org/?probe=632d2a6962) | Mar 06, 2024 |
| Fujitsu       | STYLISTIC Q665              | Tablet      | [9bc073f366](https://linux-hardware.org/?probe=9bc073f366) | Mar 05, 2024 |
| TongFang      | GM7PX0N                     | Notebook    | [4282677961](https://linux-hardware.org/?probe=4282677961) | Mar 05, 2024 |
| Acer          | Extensa 5635ZG              | Notebook    | [736943715c](https://linux-hardware.org/?probe=736943715c) | Mar 04, 2024 |
| Acer          | Extensa 5635ZG              | Notebook    | [e32263435e](https://linux-hardware.org/?probe=e32263435e) | Mar 04, 2024 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [f9efc24735](https://linux-hardware.org/?probe=f9efc24735) | Mar 03, 2024 |
| Apple         | MacBookPro5,3               | Notebook    | [20e198611e](https://linux-hardware.org/?probe=20e198611e) | Mar 02, 2024 |
| ASUSTek       | E201NA                      | Notebook    | [39326f3b72](https://linux-hardware.org/?probe=39326f3b72) | Mar 01, 2024 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [aae4ff4009](https://linux-hardware.org/?probe=aae4ff4009) | Feb 29, 2024 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [445ff9dc64](https://linux-hardware.org/?probe=445ff9dc64) | Feb 28, 2024 |
| HP            | Pavilion Sleekbook 14       | Notebook    | [9727db31ca](https://linux-hardware.org/?probe=9727db31ca) | Feb 28, 2024 |
| Dell          | Latitude E7470              | Notebook    | [d4890f7ed2](https://linux-hardware.org/?probe=d4890f7ed2) | Feb 27, 2024 |
| Lenovo        | ThinkPad T480 20L5000UUS    | Notebook    | [79b3e2b85f](https://linux-hardware.org/?probe=79b3e2b85f) | Feb 26, 2024 |
| Toshiba       | Satellite Pro C50-A-1EM     | Notebook    | [a0d0bf0a80](https://linux-hardware.org/?probe=a0d0bf0a80) | Feb 25, 2024 |
| Apple         | Mac-F4218EC8 DVT            | All in one  | [9498f74025](https://linux-hardware.org/?probe=9498f74025) | Feb 24, 2024 |
| Toshiba       | Satellite Pro C50-A-1EM     | Notebook    | [c398b93c14](https://linux-hardware.org/?probe=c398b93c14) | Feb 24, 2024 |
| HP            | Pavilion 17                 | Notebook    | [274b953249](https://linux-hardware.org/?probe=274b953249) | Feb 23, 2024 |
| HP            | 240 14 inch G9              | Notebook    | [54ea49a49a](https://linux-hardware.org/?probe=54ea49a49a) | Feb 23, 2024 |
| ASUSTek       | X501U                       | Notebook    | [1ebbe09ae2](https://linux-hardware.org/?probe=1ebbe09ae2) | Feb 21, 2024 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [d7f17aa5fd](https://linux-hardware.org/?probe=d7f17aa5fd) | Feb 21, 2024 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [4d913de0c0](https://linux-hardware.org/?probe=4d913de0c0) | Feb 21, 2024 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [bddbc049f7](https://linux-hardware.org/?probe=bddbc049f7) | Feb 21, 2024 |
| Lenovo        | ThinkPad X230 2325CY4       | Notebook    | [6491a02f07](https://linux-hardware.org/?probe=6491a02f07) | Feb 20, 2024 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [9d5c5dfeb7](https://linux-hardware.org/?probe=9d5c5dfeb7) | Feb 20, 2024 |
| Gigabyte      | H61M-DS2                    | Desktop     | [581dd97a4d](https://linux-hardware.org/?probe=581dd97a4d) | Feb 20, 2024 |
| ASUSTek       | B85M-E                      | Desktop     | [d1bbdc0a03](https://linux-hardware.org/?probe=d1bbdc0a03) | Feb 19, 2024 |
| ALLDOCUBE     | KnoteGo                     | Tablet      | [ce5ed12e45](https://linux-hardware.org/?probe=ce5ed12e45) | Feb 19, 2024 |
| AZW           | Gemini T45                  | Desktop     | [9a81383d10](https://linux-hardware.org/?probe=9a81383d10) | Feb 19, 2024 |
| Medion        | Akoya THE TOUCH 10          | Notebook    | [55af4d803a](https://linux-hardware.org/?probe=55af4d803a) | Feb 19, 2024 |
| Acer          | Swift SF314-54              | Notebook    | [a08666a01c](https://linux-hardware.org/?probe=a08666a01c) | Feb 18, 2024 |
| Dell          | Latitude E6410              | Notebook    | [a074f7ca62](https://linux-hardware.org/?probe=a074f7ca62) | Feb 17, 2024 |
| Gigabyte      | M720-US3                    | Desktop     | [79c1cffeae](https://linux-hardware.org/?probe=79c1cffeae) | Feb 17, 2024 |
| Gigabyte      | M720-US3                    | Desktop     | [340b590f33](https://linux-hardware.org/?probe=340b590f33) | Feb 17, 2024 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [2d74906a7d](https://linux-hardware.org/?probe=2d74906a7d) | Feb 16, 2024 |
| Notebook      | P95_96_97Ex,Rx              | Notebook    | [b3549ef96d](https://linux-hardware.org/?probe=b3549ef96d) | Feb 16, 2024 |
| ASUSTek       | Rampage II Extreme          | Desktop     | [42f4db38c2](https://linux-hardware.org/?probe=42f4db38c2) | Feb 16, 2024 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [78b9324e29](https://linux-hardware.org/?probe=78b9324e29) | Feb 16, 2024 |
| Dell          | 0C522T A00                  | Desktop     | [fc865abc9f](https://linux-hardware.org/?probe=fc865abc9f) | Feb 16, 2024 |
| Dell          | Studio XPS 1640             | Notebook    | [79baf0c0bf](https://linux-hardware.org/?probe=79baf0c0bf) | Feb 15, 2024 |
| MSI           | CR61 3M                     | Notebook    | [6a7b9ef9b5](https://linux-hardware.org/?probe=6a7b9ef9b5) | Feb 15, 2024 |
| ASRock        | AB350 Pro4                  | Desktop     | [5b8e7f1992](https://linux-hardware.org/?probe=5b8e7f1992) | Feb 14, 2024 |
| Acer          | Aspire VX5-591G             | Notebook    | [ab712b6e6c](https://linux-hardware.org/?probe=ab712b6e6c) | Feb 14, 2024 |
| Acer          | Acadia V1.34                | Desktop     | [6807342689](https://linux-hardware.org/?probe=6807342689) | Feb 13, 2024 |
| Lenovo        | ThinkPad T460 20FMS22Q00    | Notebook    | [85e7855e2c](https://linux-hardware.org/?probe=85e7855e2c) | Feb 13, 2024 |
| Unknown       | W1415A                      | Notebook    | [a0c020f290](https://linux-hardware.org/?probe=a0c020f290) | Feb 13, 2024 |
| Lenovo        | G40-45 80E1                 | Notebook    | [23bd060420](https://linux-hardware.org/?probe=23bd060420) | Feb 12, 2024 |
| HP            | Notebook                    | Notebook    | [bdd85f3367](https://linux-hardware.org/?probe=bdd85f3367) | Feb 12, 2024 |
| Dell          | 0VYXHD A00                  | Desktop     | [134cac2a6d](https://linux-hardware.org/?probe=134cac2a6d) | Feb 11, 2024 |
| Dell          | 0VYXHD A00                  | Desktop     | [8178dd22d5](https://linux-hardware.org/?probe=8178dd22d5) | Feb 11, 2024 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [eb7f318e9b](https://linux-hardware.org/?probe=eb7f318e9b) | Feb 11, 2024 |
| Lenovo        | ThinkPad T410 2537CF3       | Notebook    | [7be1e6e033](https://linux-hardware.org/?probe=7be1e6e033) | Feb 10, 2024 |
| HP            | 250 G7 Notebook PC          | Notebook    | [284bdb6d3c](https://linux-hardware.org/?probe=284bdb6d3c) | Feb 10, 2024 |
| HP            | ProBook 430 G1              | Notebook    | [191e61f6f6](https://linux-hardware.org/?probe=191e61f6f6) | Feb 09, 2024 |
| Dell          | 0VRWRC A00                  | Desktop     | [1dfe3721a8](https://linux-hardware.org/?probe=1dfe3721a8) | Feb 09, 2024 |
| Dell          | Latitude D630               | Notebook    | [3de4290e6a](https://linux-hardware.org/?probe=3de4290e6a) | Feb 09, 2024 |
| Dell          | Latitude D630               | Notebook    | [bb2c9bba3c](https://linux-hardware.org/?probe=bb2c9bba3c) | Feb 09, 2024 |
| MSI           | GF63 Thin 11UC              | Notebook    | [1c9674a221](https://linux-hardware.org/?probe=1c9674a221) | Feb 08, 2024 |
| ASRock        | B250M-HDV PS                | Desktop     | [b18ea679bb](https://linux-hardware.org/?probe=b18ea679bb) | Feb 08, 2024 |
| HP            | ProBook 450 G2              | Notebook    | [7a2fbcd83a](https://linux-hardware.org/?probe=7a2fbcd83a) | Feb 08, 2024 |
| HP            | ProBook 450 G2              | Notebook    | [77995292b4](https://linux-hardware.org/?probe=77995292b4) | Feb 08, 2024 |
| Positivo      | C14CR21                     | Notebook    | [0c5f4aa87b](https://linux-hardware.org/?probe=0c5f4aa87b) | Feb 07, 2024 |
| ASUSTek       | UL50VT                      | Notebook    | [b25f172725](https://linux-hardware.org/?probe=b25f172725) | Feb 07, 2024 |
| MSI           | B450M GAMING PLUS           | Desktop     | [62af32fc16](https://linux-hardware.org/?probe=62af32fc16) | Feb 07, 2024 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [8800fba01e](https://linux-hardware.org/?probe=8800fba01e) | Feb 06, 2024 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [1b1a2efc3f](https://linux-hardware.org/?probe=1b1a2efc3f) | Feb 05, 2024 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [a16ea9a89e](https://linux-hardware.org/?probe=a16ea9a89e) | Feb 05, 2024 |
| HP            | 650                         | Notebook    | [1787878b4c](https://linux-hardware.org/?probe=1787878b4c) | Feb 05, 2024 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [facc68443a](https://linux-hardware.org/?probe=facc68443a) | Feb 05, 2024 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [927466a797](https://linux-hardware.org/?probe=927466a797) | Feb 05, 2024 |
| Dell          | Latitude E7470              | Notebook    | [cb6d054e87](https://linux-hardware.org/?probe=cb6d054e87) | Feb 04, 2024 |
| Acer          | Extensa 5635ZG              | Notebook    | [8b36e2aaa6](https://linux-hardware.org/?probe=8b36e2aaa6) | Feb 04, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [c4e7517d41](https://linux-hardware.org/?probe=c4e7517d41) | Feb 04, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [db0469bd8f](https://linux-hardware.org/?probe=db0469bd8f) | Feb 04, 2024 |
| Positivo      | Schoolmate 17 SF20PA2       | Notebook    | [d779dcc224](https://linux-hardware.org/?probe=d779dcc224) | Feb 04, 2024 |
| Positivo      | Schoolmate 17 SF20PA2       | Notebook    | [4be4aaae01](https://linux-hardware.org/?probe=4be4aaae01) | Feb 04, 2024 |
| Dell          | 0G214D A00                  | Desktop     | [1a1b425da2](https://linux-hardware.org/?probe=1a1b425da2) | Feb 04, 2024 |
| ASRock        | 4Core1600-D800              | Desktop     | [70cc10cb2c](https://linux-hardware.org/?probe=70cc10cb2c) | Feb 04, 2024 |
| Dell          | Venue 11 Pro 7140           | Notebook    | [35aa24fc01](https://linux-hardware.org/?probe=35aa24fc01) | Feb 04, 2024 |
| Gigabyte      | GA-990FXA-UD7               | Desktop     | [50c2a07f8a](https://linux-hardware.org/?probe=50c2a07f8a) | Feb 04, 2024 |
| ASRock        | 4Core1600-D800              | Desktop     | [c34e1b1365](https://linux-hardware.org/?probe=c34e1b1365) | Feb 04, 2024 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [39712fdfe2](https://linux-hardware.org/?probe=39712fdfe2) | Feb 03, 2024 |
| Lenovo        | ThinkPad T430 2349HNU       | Notebook    | [f73b7b76a2](https://linux-hardware.org/?probe=f73b7b76a2) | Feb 03, 2024 |
| Toshiba       | Satellite L55-C             | Notebook    | [747bf6b034](https://linux-hardware.org/?probe=747bf6b034) | Feb 03, 2024 |
| ASRock        | G31M-S                      | Desktop     | [a596a04111](https://linux-hardware.org/?probe=a596a04111) | Feb 03, 2024 |
| Apple         | Mac-F4218FC8 DVT            | All in one  | [7e9ecedb98](https://linux-hardware.org/?probe=7e9ecedb98) | Feb 02, 2024 |
| Gigabyte      | GA-990FXA-UD7               | Desktop     | [66768ccdf7](https://linux-hardware.org/?probe=66768ccdf7) | Feb 02, 2024 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [3074b7c2a6](https://linux-hardware.org/?probe=3074b7c2a6) | Feb 02, 2024 |
| Gigabyte      | GA-990FXA-UD7               | Desktop     | [4726161c35](https://linux-hardware.org/?probe=4726161c35) | Feb 02, 2024 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [62dc25b8b6](https://linux-hardware.org/?probe=62dc25b8b6) | Feb 02, 2024 |
| Apple         | Mac-F4218FC8 DVT            | All in one  | [9b97e0a028](https://linux-hardware.org/?probe=9b97e0a028) | Feb 01, 2024 |
| Unknown       | Unknown                     | Desktop     | [4fa0768f2b](https://linux-hardware.org/?probe=4fa0768f2b) | Feb 01, 2024 |
| Unknown       | Unknown                     | Desktop     | [69b18742b6](https://linux-hardware.org/?probe=69b18742b6) | Feb 01, 2024 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [3cedb3c573](https://linux-hardware.org/?probe=3cedb3c573) | Feb 01, 2024 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [45207cf034](https://linux-hardware.org/?probe=45207cf034) | Jan 31, 2024 |
| HP            | EliteBook 8460p             | Notebook    | [8ddfa07beb](https://linux-hardware.org/?probe=8ddfa07beb) | Jan 31, 2024 |
| HP            | ProBook 6570b               | Notebook    | [20537302e6](https://linux-hardware.org/?probe=20537302e6) | Jan 31, 2024 |
| Huanan        | X99-8M-F V1.4               | Desktop     | [7625188b91](https://linux-hardware.org/?probe=7625188b91) | Jan 31, 2024 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [d1065a1aca](https://linux-hardware.org/?probe=d1065a1aca) | Jan 30, 2024 |
| Acer          | Aspire 9420                 | Notebook    | [d0c7154097](https://linux-hardware.org/?probe=d0c7154097) | Jan 30, 2024 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [073f673b78](https://linux-hardware.org/?probe=073f673b78) | Jan 29, 2024 |
| Dell          | 0RY007                      | Desktop     | [151f303198](https://linux-hardware.org/?probe=151f303198) | Jan 29, 2024 |
| Dell          | Inspiron 1545               | Notebook    | [3cffc989aa](https://linux-hardware.org/?probe=3cffc989aa) | Jan 29, 2024 |
| Dell          | Inspiron 1545               | Notebook    | [31ce3ae751](https://linux-hardware.org/?probe=31ce3ae751) | Jan 29, 2024 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [292b1b06ca](https://linux-hardware.org/?probe=292b1b06ca) | Jan 28, 2024 |
| ASRock        | G31M-S                      | Desktop     | [3030db55a6](https://linux-hardware.org/?probe=3030db55a6) | Jan 28, 2024 |
| Acer          | Aspire M3-581G              | Notebook    | [b91416ad7c](https://linux-hardware.org/?probe=b91416ad7c) | Jan 28, 2024 |
| MSI           | Z490-A PRO                  | Desktop     | [a851d2d2fe](https://linux-hardware.org/?probe=a851d2d2fe) | Jan 28, 2024 |
| Gigabyte      | Z97X-UD5H                   | Desktop     | [fd0ab9a9ac](https://linux-hardware.org/?probe=fd0ab9a9ac) | Jan 28, 2024 |
| Dell          | 0GDG8Y A00                  | Desktop     | [47f8ef1ba6](https://linux-hardware.org/?probe=47f8ef1ba6) | Jan 27, 2024 |
| Dell          | Latitude E6430              | Notebook    | [237d6e4d3e](https://linux-hardware.org/?probe=237d6e4d3e) | Jan 27, 2024 |
| Dell          | 0Y5DDC A00                  | Desktop     | [1912506274](https://linux-hardware.org/?probe=1912506274) | Jan 26, 2024 |
| Quanta        | XV1                         | All in one  | [b39049cedd](https://linux-hardware.org/?probe=b39049cedd) | Jan 26, 2024 |
| ASUSTek       | CM6870                      | Desktop     | [1abc8128a3](https://linux-hardware.org/?probe=1abc8128a3) | Jan 26, 2024 |
| HP            | 3647h                       | Desktop     | [14bc5e74bc](https://linux-hardware.org/?probe=14bc5e74bc) | Jan 26, 2024 |
| Dell          | 048DY8 A01                  | Desktop     | [d5e6914489](https://linux-hardware.org/?probe=d5e6914489) | Jan 26, 2024 |
| Toshiba       | Satellite R630              | Notebook    | [c888a8f4d5](https://linux-hardware.org/?probe=c888a8f4d5) | Jan 24, 2024 |
| Dell          | 0GDG8Y A00                  | Desktop     | [18de9933d4](https://linux-hardware.org/?probe=18de9933d4) | Jan 24, 2024 |
| Alienware     | 07W25T A01                  | Desktop     | [538d2e2b5f](https://linux-hardware.org/?probe=538d2e2b5f) | Jan 24, 2024 |
| Apple         | MacBookPro5,5               | Notebook    | [214ebad454](https://linux-hardware.org/?probe=214ebad454) | Jan 24, 2024 |
| Apple         | MacBookPro5,5               | Notebook    | [f2a415adc9](https://linux-hardware.org/?probe=f2a415adc9) | Jan 24, 2024 |
| Dell          | 0D28YY A00                  | Desktop     | [8d8d8005b1](https://linux-hardware.org/?probe=8d8d8005b1) | Jan 23, 2024 |
| HP            | ZBook Studio G5             | Notebook    | [114d79aa75](https://linux-hardware.org/?probe=114d79aa75) | Jan 23, 2024 |
| Dell          | Latitude E5420              | Notebook    | [8347319849](https://linux-hardware.org/?probe=8347319849) | Jan 23, 2024 |
| HP            | Pavilion g4                 | Notebook    | [f0cc56ebca](https://linux-hardware.org/?probe=f0cc56ebca) | Jan 23, 2024 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [eed9a3591f](https://linux-hardware.org/?probe=eed9a3591f) | Jan 23, 2024 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [8479b771e4](https://linux-hardware.org/?probe=8479b771e4) | Jan 23, 2024 |
| HP            | 8523 A01                    | Mini pc     | [cfec865f42](https://linux-hardware.org/?probe=cfec865f42) | Jan 23, 2024 |
| HP            | 8523 A01                    | Mini pc     | [ad950a4d7d](https://linux-hardware.org/?probe=ad950a4d7d) | Jan 23, 2024 |
| Google        | Kefka                       | Notebook    | [6cb0b95d02](https://linux-hardware.org/?probe=6cb0b95d02) | Jan 22, 2024 |
| HP            | Notebook                    | Notebook    | [8359e2a5dd](https://linux-hardware.org/?probe=8359e2a5dd) | Jan 22, 2024 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [8dacf655a4](https://linux-hardware.org/?probe=8dacf655a4) | Jan 22, 2024 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [c3f3bb78c6](https://linux-hardware.org/?probe=c3f3bb78c6) | Jan 22, 2024 |
| HP            | ProBook 430 G4              | Notebook    | [046036e7e3](https://linux-hardware.org/?probe=046036e7e3) | Jan 22, 2024 |
| HP            | ProBook 430 G4              | Notebook    | [262a8552de](https://linux-hardware.org/?probe=262a8552de) | Jan 22, 2024 |
| Dell          | Inspiron 5559               | Notebook    | [a0c06abcbd](https://linux-hardware.org/?probe=a0c06abcbd) | Jan 22, 2024 |
| Dell          | Latitude 5490               | Notebook    | [ebc5bed33f](https://linux-hardware.org/?probe=ebc5bed33f) | Jan 22, 2024 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [41a378391c](https://linux-hardware.org/?probe=41a378391c) | Jan 22, 2024 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [a8893e7742](https://linux-hardware.org/?probe=a8893e7742) | Jan 22, 2024 |
| Alienware     | 07W25T A01                  | Desktop     | [2a7a6fd405](https://linux-hardware.org/?probe=2a7a6fd405) | Jan 22, 2024 |
| Apple         | MacBookPro14,1              | Notebook    | [af0244605f](https://linux-hardware.org/?probe=af0244605f) | Jan 21, 2024 |
| Apple         | MacBookPro14,1              | Notebook    | [024b0a26f9](https://linux-hardware.org/?probe=024b0a26f9) | Jan 21, 2024 |
| MSI           | 760GM-P34                   | Desktop     | [3eb4ebb737](https://linux-hardware.org/?probe=3eb4ebb737) | Jan 21, 2024 |
| Toshiba       | Satellite L640              | Notebook    | [7478e6971b](https://linux-hardware.org/?probe=7478e6971b) | Jan 21, 2024 |
| HP            | Notebook                    | Notebook    | [2dcfaac5fd](https://linux-hardware.org/?probe=2dcfaac5fd) | Jan 21, 2024 |
| Foxconn       | 946 7MA Series              | Desktop     | [40261803d6](https://linux-hardware.org/?probe=40261803d6) | Jan 21, 2024 |
| Acer          | TravelMate Spin P614RN-5    | Convertible | [875bdb70a2](https://linux-hardware.org/?probe=875bdb70a2) | Jan 20, 2024 |
| Sony          | VGN-NS11Z_S                 | Notebook    | [64fa921691](https://linux-hardware.org/?probe=64fa921691) | Jan 20, 2024 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [4257aab3ea](https://linux-hardware.org/?probe=4257aab3ea) | Jan 20, 2024 |
| Dell          | Inspiron 3531               | Notebook    | [afc0f1a968](https://linux-hardware.org/?probe=afc0f1a968) | Jan 20, 2024 |
| AZW           | SER                         | Mini pc     | [c91aa206d4](https://linux-hardware.org/?probe=c91aa206d4) | Jan 20, 2024 |
| HP            | EliteBook 840 G1            | Notebook    | [becbec6f26](https://linux-hardware.org/?probe=becbec6f26) | Jan 20, 2024 |
| Acer          | Aspire E5-551G              | Notebook    | [c4bd469e8d](https://linux-hardware.org/?probe=c4bd469e8d) | Jan 19, 2024 |
| Acer          | Aspire E5-523               | Notebook    | [02378722b6](https://linux-hardware.org/?probe=02378722b6) | Jan 19, 2024 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [c3733ef1e3](https://linux-hardware.org/?probe=c3733ef1e3) | Jan 18, 2024 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [518ca600f6](https://linux-hardware.org/?probe=518ca600f6) | Jan 18, 2024 |
| Dell          | 0GTK4K A02                  | Desktop     | [a4aef81553](https://linux-hardware.org/?probe=a4aef81553) | Jan 18, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [ae841d1af4](https://linux-hardware.org/?probe=ae841d1af4) | Jan 17, 2024 |
| HP            | ZBook 14u G6                | Notebook    | [668a33bda1](https://linux-hardware.org/?probe=668a33bda1) | Jan 17, 2024 |
| Toshiba       | Satellite A665              | Notebook    | [66c11ee330](https://linux-hardware.org/?probe=66c11ee330) | Jan 17, 2024 |
| Toshiba       | Satellite C850-B820         | Notebook    | [321a8ae666](https://linux-hardware.org/?probe=321a8ae666) | Jan 17, 2024 |
| Toshiba       | Satellite A665              | Notebook    | [640deb41af](https://linux-hardware.org/?probe=640deb41af) | Jan 17, 2024 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | Notebook    | [0e05a50329](https://linux-hardware.org/?probe=0e05a50329) | Jan 16, 2024 |
| HP            | Pavilion 17                 | Notebook    | [3594afe0d4](https://linux-hardware.org/?probe=3594afe0d4) | Jan 16, 2024 |
| Intel         | Unknown                     | Notebook    | [dfd975eff3](https://linux-hardware.org/?probe=dfd975eff3) | Jan 15, 2024 |
| Intel         | DQ67SW AAG12527-310         | Desktop     | [4c5f54d07e](https://linux-hardware.org/?probe=4c5f54d07e) | Jan 15, 2024 |
| Dell          | OptiPlex 7050               | Desktop     | [f0c2b782ff](https://linux-hardware.org/?probe=f0c2b782ff) | Jan 15, 2024 |
| Intel         | X99-P4 V5.0                 | Desktop     | [574a971f93](https://linux-hardware.org/?probe=574a971f93) | Jan 14, 2024 |
| ASUSTek       | Z170-P                      | Desktop     | [b3d8c3265d](https://linux-hardware.org/?probe=b3d8c3265d) | Jan 14, 2024 |
| Lenovo        | ThinkCentre M70E 0830W36    | Desktop     | [f28fd8d379](https://linux-hardware.org/?probe=f28fd8d379) | Jan 14, 2024 |
| Sony          | VGN-NS11Z_S                 | Notebook    | [863785eef9](https://linux-hardware.org/?probe=863785eef9) | Jan 13, 2024 |
| Quanta        | XV1                         | All in one  | [112581cd19](https://linux-hardware.org/?probe=112581cd19) | Jan 13, 2024 |
| Dell          | Inspiron 3501               | Notebook    | [75a54dcccf](https://linux-hardware.org/?probe=75a54dcccf) | Jan 13, 2024 |
| Toshiba       | Satellite R630              | Notebook    | [0e83a06873](https://linux-hardware.org/?probe=0e83a06873) | Jan 13, 2024 |
| Acer          | Aspire V5-573G              | Notebook    | [09ddfeab43](https://linux-hardware.org/?probe=09ddfeab43) | Jan 12, 2024 |
| HP            | 3647h                       | Desktop     | [e9767a4e96](https://linux-hardware.org/?probe=e9767a4e96) | Jan 12, 2024 |
| HP            | 3647h                       | Desktop     | [39414040e7](https://linux-hardware.org/?probe=39414040e7) | Jan 12, 2024 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | Mini pc     | [de5d52bcd5](https://linux-hardware.org/?probe=de5d52bcd5) | Jan 12, 2024 |
| Gateway       | SX2851                      | Desktop     | [0cbcae7c27](https://linux-hardware.org/?probe=0cbcae7c27) | Jan 11, 2024 |
| Acer          | Veriton X490G               | Desktop     | [1110362d9a](https://linux-hardware.org/?probe=1110362d9a) | Jan 11, 2024 |
| ASUSTek       | N56JR                       | Notebook    | [513c456753](https://linux-hardware.org/?probe=513c456753) | Jan 11, 2024 |
| Dell          | 0T1D10 A01                  | Desktop     | [0c1256487e](https://linux-hardware.org/?probe=0c1256487e) | Jan 11, 2024 |
| Medion        | E4251 MD61435               | Notebook    | [6a9251fa94](https://linux-hardware.org/?probe=6a9251fa94) | Jan 11, 2024 |
| HP            | Pavilion Sleekbook 14       | Notebook    | [9f54d91b95](https://linux-hardware.org/?probe=9f54d91b95) | Jan 10, 2024 |
| Toshiba       | Satellite L845              | Notebook    | [e45e9517b3](https://linux-hardware.org/?probe=e45e9517b3) | Jan 10, 2024 |
| Dell          | Inspiron 7737               | Notebook    | [ae41cf1d2f](https://linux-hardware.org/?probe=ae41cf1d2f) | Jan 10, 2024 |
| Acer          | Aspire E1-570G              | Notebook    | [2bb5dcf476](https://linux-hardware.org/?probe=2bb5dcf476) | Jan 10, 2024 |
| ASUSTek       | X200CA                      | Notebook    | [c27c1b9fc2](https://linux-hardware.org/?probe=c27c1b9fc2) | Jan 10, 2024 |
| Toshiba       | Satellite C850              | Notebook    | [38fb6d3619](https://linux-hardware.org/?probe=38fb6d3619) | Jan 09, 2024 |
| Toshiba       | Satellite C850              | Notebook    | [c6faf796f4](https://linux-hardware.org/?probe=c6faf796f4) | Jan 09, 2024 |
| Unknown       | Unknown                     | Desktop     | [ca7b5632f4](https://linux-hardware.org/?probe=ca7b5632f4) | Jan 09, 2024 |
| Lenovo        | SKYBAY SDK0J40697 WIN 33... | Desktop     | [d5486716d1](https://linux-hardware.org/?probe=d5486716d1) | Jan 09, 2024 |
| HONOR         | BBR-WAX9                    | Notebook    | [b9d1ee2b4c](https://linux-hardware.org/?probe=b9d1ee2b4c) | Jan 08, 2024 |
| HP            | EliteBook 8440p             | Notebook    | [6a5afb5dec](https://linux-hardware.org/?probe=6a5afb5dec) | Jan 08, 2024 |
| HP            | EliteBook Revolve 810 G1    | Notebook    | [c428c1eb3e](https://linux-hardware.org/?probe=c428c1eb3e) | Jan 08, 2024 |
| ASUSTek       | ROG Maximus Z790 HERO       | Desktop     | [50877161c2](https://linux-hardware.org/?probe=50877161c2) | Jan 08, 2024 |
| ASUSTek       | ROG Maximus Z790 HERO       | Desktop     | [cb7c295dc6](https://linux-hardware.org/?probe=cb7c295dc6) | Jan 08, 2024 |
| ASUSTek       | UL50VT                      | Notebook    | [428d20a1eb](https://linux-hardware.org/?probe=428d20a1eb) | Jan 07, 2024 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [ac3aa9697a](https://linux-hardware.org/?probe=ac3aa9697a) | Jan 07, 2024 |
| Acer          | Swift SF314-511             | Notebook    | [14eac9efff](https://linux-hardware.org/?probe=14eac9efff) | Jan 07, 2024 |
| Acer          | Aspire E1-570G              | Notebook    | [3c08b1958e](https://linux-hardware.org/?probe=3c08b1958e) | Jan 07, 2024 |
| Intel         | H61                         | Desktop     | [a0d05acffb](https://linux-hardware.org/?probe=a0d05acffb) | Jan 07, 2024 |
| Dell          | Latitude E5420              | Notebook    | [40835d5737](https://linux-hardware.org/?probe=40835d5737) | Jan 07, 2024 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [b02f06751f](https://linux-hardware.org/?probe=b02f06751f) | Jan 07, 2024 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [8f181c2fb8](https://linux-hardware.org/?probe=8f181c2fb8) | Jan 07, 2024 |
| Biostar       | A320MH                      | Desktop     | [9bec9420ab](https://linux-hardware.org/?probe=9bec9420ab) | Jan 06, 2024 |
| ASUSTek       | B85M-E                      | Desktop     | [1f5304b336](https://linux-hardware.org/?probe=1f5304b336) | Jan 06, 2024 |
| ASUSTek       | B85M-E                      | Desktop     | [7c7fb3af69](https://linux-hardware.org/?probe=7c7fb3af69) | Jan 06, 2024 |
| Lenovo        | ThinkPad T520 4243F53       | Notebook    | [900bfdd9a8](https://linux-hardware.org/?probe=900bfdd9a8) | Jan 06, 2024 |
| ASRock        | G31M-S                      | Desktop     | [1b44835106](https://linux-hardware.org/?probe=1b44835106) | Jan 06, 2024 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [f9b4427f39](https://linux-hardware.org/?probe=f9b4427f39) | Jan 06, 2024 |
| Dell          | 0HN7XN A01                  | Desktop     | [f154d2ee51](https://linux-hardware.org/?probe=f154d2ee51) | Jan 06, 2024 |
| HP            | ENVY dv6                    | Notebook    | [12f54bd4e0](https://linux-hardware.org/?probe=12f54bd4e0) | Jan 06, 2024 |
| ASUSTek       | PRIME X399-A                | Desktop     | [5f016cc67b](https://linux-hardware.org/?probe=5f016cc67b) | Jan 05, 2024 |
| Dell          | 0T1D10 A01                  | Desktop     | [36fd42ae37](https://linux-hardware.org/?probe=36fd42ae37) | Jan 05, 2024 |
| Dell          | 0HN7XN A01                  | Desktop     | [91b070152e](https://linux-hardware.org/?probe=91b070152e) | Jan 05, 2024 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [37ea5af9b1](https://linux-hardware.org/?probe=37ea5af9b1) | Jan 04, 2024 |
| Dell          | Inspiron 1525               | Notebook    | [debaccaee2](https://linux-hardware.org/?probe=debaccaee2) | Jan 04, 2024 |
| ASUSTek       | E201NA                      | Notebook    | [91cac0307a](https://linux-hardware.org/?probe=91cac0307a) | Jan 04, 2024 |
| Lenovo        | ThinkCentre M71e 3156PT5    | Desktop     | [53089d138d](https://linux-hardware.org/?probe=53089d138d) | Jan 03, 2024 |
| Intel         | DQ67SW AAG12527-310         | Desktop     | [64811dfb22](https://linux-hardware.org/?probe=64811dfb22) | Jan 03, 2024 |
| Lenovo        | ThinkPad P16s Gen 1 21BT... | Notebook    | [e15430e53e](https://linux-hardware.org/?probe=e15430e53e) | Jan 02, 2024 |
| Dell          | 0D28YY A01                  | Desktop     | [f67d5d22eb](https://linux-hardware.org/?probe=f67d5d22eb) | Jan 02, 2024 |
| Lenovo        | ThinkPad T460s 20FAS1V60... | Notebook    | [ca5f55438f](https://linux-hardware.org/?probe=ca5f55438f) | Jan 02, 2024 |
| Gigabyte      | Z590 UD AC                  | Desktop     | [0db9ec67ac](https://linux-hardware.org/?probe=0db9ec67ac) | Jan 02, 2024 |
| Apple         | Mac-F22C86C8                | Mini pc     | [b1e1f0314c](https://linux-hardware.org/?probe=b1e1f0314c) | Jan 01, 2024 |
| Samsung       | DT1234567890 SEC_SW_REVI... | Desktop     | [d2112b91c1](https://linux-hardware.org/?probe=d2112b91c1) | Jan 01, 2024 |
| Samsung       | DT1234567890 SEC_SW_REVI... | Desktop     | [252e78398a](https://linux-hardware.org/?probe=252e78398a) | Jan 01, 2024 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [a37bbce8de](https://linux-hardware.org/?probe=a37bbce8de) | Dec 31, 2023 |
| ASUSTek       | CM6870                      | Desktop     | [bdc19328ef](https://linux-hardware.org/?probe=bdc19328ef) | Dec 31, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [d975ab384e](https://linux-hardware.org/?probe=d975ab384e) | Dec 31, 2023 |
| Dell          | 0RW199                      | Desktop     | [62dc9ffa33](https://linux-hardware.org/?probe=62dc9ffa33) | Dec 31, 2023 |
| Gigabyte      | Z790 GAMING X AX            | Desktop     | [e330d0191e](https://linux-hardware.org/?probe=e330d0191e) | Dec 31, 2023 |
| Acer          | Aspire 8943G                | Notebook    | [a75a2524f2](https://linux-hardware.org/?probe=a75a2524f2) | Dec 31, 2023 |
| ASUSTek       | PRIME X399-A                | Desktop     | [ac506b01e6](https://linux-hardware.org/?probe=ac506b01e6) | Dec 30, 2023 |
| HP            | 82F1                        | Desktop     | [9fc9cb3de0](https://linux-hardware.org/?probe=9fc9cb3de0) | Dec 30, 2023 |
| Dell          | 0VRWRC A00                  | Desktop     | [c58ff5350b](https://linux-hardware.org/?probe=c58ff5350b) | Dec 30, 2023 |
| Pegatron      | 2A9A                        | Desktop     | [92def1bf4a](https://linux-hardware.org/?probe=92def1bf4a) | Dec 30, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [7dca6779be](https://linux-hardware.org/?probe=7dca6779be) | Dec 29, 2023 |
| Sony          | VGN-CR21S_W                 | Notebook    | [732175d0f6](https://linux-hardware.org/?probe=732175d0f6) | Dec 29, 2023 |
| ASRock        | B550M-C                     | Desktop     | [ba3fa09385](https://linux-hardware.org/?probe=ba3fa09385) | Dec 29, 2023 |
| Lenovo        | 36EB SDK0J40700 WIN 3258... | Desktop     | [7a34810f0e](https://linux-hardware.org/?probe=7a34810f0e) | Dec 29, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [9189ed311a](https://linux-hardware.org/?probe=9189ed311a) | Dec 29, 2023 |
| ASUSTek       | PRIME X399-A                | Desktop     | [4d46811257](https://linux-hardware.org/?probe=4d46811257) | Dec 29, 2023 |
| HP            | ZBook 14u G6                | Notebook    | [409e402108](https://linux-hardware.org/?probe=409e402108) | Dec 28, 2023 |
| Lenovo        | No DPK                      | All in one  | [e47b692f60](https://linux-hardware.org/?probe=e47b692f60) | Dec 28, 2023 |
| Dell          | Vostro 2420                 | Notebook    | [52ae549c99](https://linux-hardware.org/?probe=52ae549c99) | Dec 28, 2023 |
| Dell          | 0GDG8Y A00                  | Desktop     | [59c76d34e1](https://linux-hardware.org/?probe=59c76d34e1) | Dec 27, 2023 |
| Acer          | Aspire E1-570               | Notebook    | [403dd9f171](https://linux-hardware.org/?probe=403dd9f171) | Dec 27, 2023 |
| HP            | Compaq 2510p                | Notebook    | [b7b88f9c1c](https://linux-hardware.org/?probe=b7b88f9c1c) | Dec 27, 2023 |
| UNOWHY        | Y13G012S4EI                 | Notebook    | [a3bb952104](https://linux-hardware.org/?probe=a3bb952104) | Dec 27, 2023 |
| ASUSTek       | M4A79T Deluxe               | Desktop     | [167d330ef0](https://linux-hardware.org/?probe=167d330ef0) | Dec 27, 2023 |
| HP            | EliteBook Revolve 810 G1    | Notebook    | [30d2bb71e5](https://linux-hardware.org/?probe=30d2bb71e5) | Dec 27, 2023 |
| Lenovo        | No DPK                      | All in one  | [961bd36b3d](https://linux-hardware.org/?probe=961bd36b3d) | Dec 27, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [bc9feace53](https://linux-hardware.org/?probe=bc9feace53) | Dec 27, 2023 |
| Pegatron      | 2A9A                        | Desktop     | [e67022179a](https://linux-hardware.org/?probe=e67022179a) | Dec 26, 2023 |
| Lenovo        | ThinkPad T440p 20AWS08S0... | Notebook    | [ae928b9cc1](https://linux-hardware.org/?probe=ae928b9cc1) | Dec 25, 2023 |
| Dell          | 0GDG8Y A00                  | Desktop     | [52a5621ef8](https://linux-hardware.org/?probe=52a5621ef8) | Dec 25, 2023 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [0cee3977a0](https://linux-hardware.org/?probe=0cee3977a0) | Dec 25, 2023 |
| Dell          | 0MN1TX A04                  | Desktop     | [ba94c75ba0](https://linux-hardware.org/?probe=ba94c75ba0) | Dec 25, 2023 |
| HP            | ENVY dv6                    | Notebook    | [e7d00bdca8](https://linux-hardware.org/?probe=e7d00bdca8) | Dec 25, 2023 |
| HP            | ENVY dv6                    | Notebook    | [7feb95b534](https://linux-hardware.org/?probe=7feb95b534) | Dec 25, 2023 |
| HP            | 2AF7                        | Desktop     | [2fc4d5dd6b](https://linux-hardware.org/?probe=2fc4d5dd6b) | Dec 24, 2023 |
| HP            | 2AF7                        | Desktop     | [baa5012432](https://linux-hardware.org/?probe=baa5012432) | Dec 24, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [2f8f606e9f](https://linux-hardware.org/?probe=2f8f606e9f) | Dec 24, 2023 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [dd911fd507](https://linux-hardware.org/?probe=dd911fd507) | Dec 24, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [6ee70cb266](https://linux-hardware.org/?probe=6ee70cb266) | Dec 24, 2023 |
| Dell          | Latitude E6430              | Notebook    | [d949738171](https://linux-hardware.org/?probe=d949738171) | Dec 24, 2023 |
| Dell          | Latitude E6430              | Notebook    | [c821d379ec](https://linux-hardware.org/?probe=c821d379ec) | Dec 24, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | Notebook    | [a69b3fa1ca](https://linux-hardware.org/?probe=a69b3fa1ca) | Dec 24, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | Notebook    | [9ac48a1719](https://linux-hardware.org/?probe=9ac48a1719) | Dec 24, 2023 |
| HP            | Notebook                    | Notebook    | [69bef099c0](https://linux-hardware.org/?probe=69bef099c0) | Dec 24, 2023 |
| ASUSTek       | M2V                         | Desktop     | [67c7bc43ed](https://linux-hardware.org/?probe=67c7bc43ed) | Dec 23, 2023 |
| ASUSTek       | M2V                         | Desktop     | [1d6970f290](https://linux-hardware.org/?probe=1d6970f290) | Dec 23, 2023 |
| HP            | 1998                        | Desktop     | [8eb25518c4](https://linux-hardware.org/?probe=8eb25518c4) | Dec 23, 2023 |
| HP            | Victus by 15.6 inch Gami... | Notebook    | [b74170ede4](https://linux-hardware.org/?probe=b74170ede4) | Dec 23, 2023 |
| Toshiba       | Satellite Pro R50-C         | Notebook    | [b4d280ac6a](https://linux-hardware.org/?probe=b4d280ac6a) | Dec 23, 2023 |
| Toshiba       | Satellite Pro R50-C         | Notebook    | [421d62894b](https://linux-hardware.org/?probe=421d62894b) | Dec 23, 2023 |
| Toshiba       | QOSMIO X770                 | Notebook    | [dceb1203ed](https://linux-hardware.org/?probe=dceb1203ed) | Dec 23, 2023 |
| Toshiba       | QOSMIO X770                 | Notebook    | [b9557b6218](https://linux-hardware.org/?probe=b9557b6218) | Dec 23, 2023 |
| Gigabyte      | B650 GAMING X AX            | Desktop     | [9c0210d1ed](https://linux-hardware.org/?probe=9c0210d1ed) | Dec 22, 2023 |
| Fujitsu       | LIFEBOOK E736               | Notebook    | [49cdf35ca4](https://linux-hardware.org/?probe=49cdf35ca4) | Dec 22, 2023 |
| VTEX          | NOTEBOOK                    | Notebook    | [972b407abc](https://linux-hardware.org/?probe=972b407abc) | Dec 22, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [084e48827c](https://linux-hardware.org/?probe=084e48827c) | Dec 21, 2023 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [83183dbb01](https://linux-hardware.org/?probe=83183dbb01) | Dec 21, 2023 |
| Lenovo        | ThinkPad X131e 33691K7      | Notebook    | [360dc0f244](https://linux-hardware.org/?probe=360dc0f244) | Dec 21, 2023 |
| Dell          | Latitude E7270              | Notebook    | [4574a46c78](https://linux-hardware.org/?probe=4574a46c78) | Dec 21, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [f9d9539e00](https://linux-hardware.org/?probe=f9d9539e00) | Dec 21, 2023 |
| ASUSTek       | E201NA                      | Notebook    | [ee5e05ce6d](https://linux-hardware.org/?probe=ee5e05ce6d) | Dec 21, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [6311def15e](https://linux-hardware.org/?probe=6311def15e) | Dec 21, 2023 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [8b094a74c9](https://linux-hardware.org/?probe=8b094a74c9) | Dec 21, 2023 |
| HP            | 1000                        | Notebook    | [2279f68ba4](https://linux-hardware.org/?probe=2279f68ba4) | Dec 21, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [5266cee35b](https://linux-hardware.org/?probe=5266cee35b) | Dec 21, 2023 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [c0c637bbba](https://linux-hardware.org/?probe=c0c637bbba) | Dec 21, 2023 |
| HP            | ProBook 430 G7              | Notebook    | [50a3c349a0](https://linux-hardware.org/?probe=50a3c349a0) | Dec 21, 2023 |
| HP            | ProBook 430 G7              | Notebook    | [f79ed192ac](https://linux-hardware.org/?probe=f79ed192ac) | Dec 21, 2023 |
| Dell          | 0FM586                      | Desktop     | [eadcdb629b](https://linux-hardware.org/?probe=eadcdb629b) | Dec 20, 2023 |
| Toshiba       | Satellite C850              | Notebook    | [caa584d966](https://linux-hardware.org/?probe=caa584d966) | Dec 20, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [af51ef8978](https://linux-hardware.org/?probe=af51ef8978) | Dec 20, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [7cda066ff6](https://linux-hardware.org/?probe=7cda066ff6) | Dec 20, 2023 |
| Lenovo        | Yoga 7 16IRL8 82YN          | Convertible | [6a601de5d5](https://linux-hardware.org/?probe=6a601de5d5) | Dec 20, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [f7cd6db92f](https://linux-hardware.org/?probe=f7cd6db92f) | Dec 20, 2023 |
| HP            | 1998                        | Desktop     | [bc41363911](https://linux-hardware.org/?probe=bc41363911) | Dec 20, 2023 |
| Framework     | Laptop                      | Notebook    | [2aab7ea892](https://linux-hardware.org/?probe=2aab7ea892) | Dec 19, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [bcae8d434f](https://linux-hardware.org/?probe=bcae8d434f) | Dec 19, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [95ab984d32](https://linux-hardware.org/?probe=95ab984d32) | Dec 19, 2023 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [582c2df7b1](https://linux-hardware.org/?probe=582c2df7b1) | Dec 19, 2023 |
| Toshiba       | Satellite Pro C50-A-1E2     | Notebook    | [91b5e05490](https://linux-hardware.org/?probe=91b5e05490) | Dec 19, 2023 |
| Toshiba       | Satellite Pro C50-A-1E2     | Notebook    | [fde7aeea9c](https://linux-hardware.org/?probe=fde7aeea9c) | Dec 19, 2023 |
| Google        | Phaser360                   | Notebook    | [c739678794](https://linux-hardware.org/?probe=c739678794) | Dec 18, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [780a4cf454](https://linux-hardware.org/?probe=780a4cf454) | Dec 18, 2023 |
| Lenovo        | ThinkPad X240 20AMS0VU00    | Notebook    | [ecca798714](https://linux-hardware.org/?probe=ecca798714) | Dec 18, 2023 |
| HP            | ProBook 430 G4              | Notebook    | [c2b96a9e0f](https://linux-hardware.org/?probe=c2b96a9e0f) | Dec 18, 2023 |
| Dell          | Venue 11 Pro 5130           | Notebook    | [74cdfd92c0](https://linux-hardware.org/?probe=74cdfd92c0) | Dec 18, 2023 |
| HP            | ZBook 14u G6                | Notebook    | [125dbde28d](https://linux-hardware.org/?probe=125dbde28d) | Dec 17, 2023 |
| Lenovo        | Yoga 7 16IRL8 82YN          | Convertible | [2b9510004d](https://linux-hardware.org/?probe=2b9510004d) | Dec 17, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [a411802ac6](https://linux-hardware.org/?probe=a411802ac6) | Dec 17, 2023 |
| Sony          | VGN-FW455J                  | Notebook    | [f16255f9d1](https://linux-hardware.org/?probe=f16255f9d1) | Dec 17, 2023 |
| ASUSTek       | K53SD                       | Notebook    | [7962dd075b](https://linux-hardware.org/?probe=7962dd075b) | Dec 17, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [304fbf1e83](https://linux-hardware.org/?probe=304fbf1e83) | Dec 17, 2023 |
| Lenovo        | Yoga 7 16IRL8 82YN          | Convertible | [4e3b49ab8e](https://linux-hardware.org/?probe=4e3b49ab8e) | Dec 17, 2023 |
| Irbis         | NB12                        | Notebook    | [f6eb11e455](https://linux-hardware.org/?probe=f6eb11e455) | Dec 17, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [ad9eaf3ae6](https://linux-hardware.org/?probe=ad9eaf3ae6) | Dec 16, 2023 |
| Google        | Phaser360                   | Notebook    | [784ed40440](https://linux-hardware.org/?probe=784ed40440) | Dec 16, 2023 |
| HP            | ProBook 455 15.6 inch G1... | Notebook    | [56e1b0ed26](https://linux-hardware.org/?probe=56e1b0ed26) | Dec 16, 2023 |
| HP            | ProBook 430 G4              | Notebook    | [30f8fe050c](https://linux-hardware.org/?probe=30f8fe050c) | Dec 16, 2023 |
| HP            | Notebook                    | Notebook    | [4973d42380](https://linux-hardware.org/?probe=4973d42380) | Dec 16, 2023 |
| MSI           | MPG Z490 GAMING PLUS        | Desktop     | [faf62fd1be](https://linux-hardware.org/?probe=faf62fd1be) | Dec 16, 2023 |
| HP            | Notebook                    | Notebook    | [a960b17c37](https://linux-hardware.org/?probe=a960b17c37) | Dec 16, 2023 |
| ASUSTek       | X553MA                      | Notebook    | [1bd6eab773](https://linux-hardware.org/?probe=1bd6eab773) | Dec 15, 2023 |
| Dell          | 0FM586                      | Desktop     | [c895a8d51f](https://linux-hardware.org/?probe=c895a8d51f) | Dec 15, 2023 |
| Medion        | P7624                       | Notebook    | [4828985ec0](https://linux-hardware.org/?probe=4828985ec0) | Dec 15, 2023 |
| Medion        | P7624                       | Notebook    | [050fbbd613](https://linux-hardware.org/?probe=050fbbd613) | Dec 15, 2023 |
| Dell          | XPS 15 9550                 | Notebook    | [de4b8201ef](https://linux-hardware.org/?probe=de4b8201ef) | Dec 15, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [646c709529](https://linux-hardware.org/?probe=646c709529) | Dec 15, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [b5fefd59fe](https://linux-hardware.org/?probe=b5fefd59fe) | Dec 15, 2023 |
| Medion        | E4251 MD61435               | Notebook    | [7d20d738b1](https://linux-hardware.org/?probe=7d20d738b1) | Dec 14, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [734375c1cc](https://linux-hardware.org/?probe=734375c1cc) | Dec 14, 2023 |
| TUXEDO        | InfinityBook Pro Gen8 (M... | Notebook    | [5ae09c04d4](https://linux-hardware.org/?probe=5ae09c04d4) | Dec 14, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [3eb792873c](https://linux-hardware.org/?probe=3eb792873c) | Dec 14, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [048f7ace00](https://linux-hardware.org/?probe=048f7ace00) | Dec 14, 2023 |
| Dell          | 0GDG8Y A00                  | Desktop     | [85f532c1c5](https://linux-hardware.org/?probe=85f532c1c5) | Dec 13, 2023 |
| Positivo      | POS-PIQ57BQ POSITIVO        | Desktop     | [1a2fe7c9ef](https://linux-hardware.org/?probe=1a2fe7c9ef) | Dec 13, 2023 |
| Dell          | Inspiron 15 5510            | Notebook    | [41dbdcf594](https://linux-hardware.org/?probe=41dbdcf594) | Dec 13, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [f9933769ef](https://linux-hardware.org/?probe=f9933769ef) | Dec 13, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [27b99be924](https://linux-hardware.org/?probe=27b99be924) | Dec 12, 2023 |
| HP            | Notebook                    | Notebook    | [972e86b7cf](https://linux-hardware.org/?probe=972e86b7cf) | Dec 12, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [bdfc16eb98](https://linux-hardware.org/?probe=bdfc16eb98) | Dec 11, 2023 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [f779186ae7](https://linux-hardware.org/?probe=f779186ae7) | Dec 11, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [311c3a6954](https://linux-hardware.org/?probe=311c3a6954) | Dec 11, 2023 |
| ASUSTek       | ZenBook UX482EG_UX482EG     | Notebook    | [a644fcc63e](https://linux-hardware.org/?probe=a644fcc63e) | Dec 11, 2023 |
| Lenovo        | ThinkPad T440s 20ARS06C0... | Notebook    | [332492b0c4](https://linux-hardware.org/?probe=332492b0c4) | Dec 11, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [d0ff744f50](https://linux-hardware.org/?probe=d0ff744f50) | Dec 10, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [e7dbed1e89](https://linux-hardware.org/?probe=e7dbed1e89) | Dec 10, 2023 |
| Dell          | 0FM586                      | Desktop     | [2bf8665376](https://linux-hardware.org/?probe=2bf8665376) | Dec 10, 2023 |
| MSI           | 2AE0                        | Desktop     | [29c5d75dcf](https://linux-hardware.org/?probe=29c5d75dcf) | Dec 10, 2023 |
| MSI           | 2AE0                        | Desktop     | [63543021ec](https://linux-hardware.org/?probe=63543021ec) | Dec 10, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [5522722e53](https://linux-hardware.org/?probe=5522722e53) | Dec 10, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [52e1cb6958](https://linux-hardware.org/?probe=52e1cb6958) | Dec 10, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [949de6a6a9](https://linux-hardware.org/?probe=949de6a6a9) | Dec 10, 2023 |
| Dell          | Inspiron 7559               | Notebook    | [3f4af9bbdd](https://linux-hardware.org/?probe=3f4af9bbdd) | Dec 10, 2023 |
| Packard Be... | EasyNote TE11BZ             | Notebook    | [514899b0b9](https://linux-hardware.org/?probe=514899b0b9) | Dec 10, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [bc892e5d3b](https://linux-hardware.org/?probe=bc892e5d3b) | Dec 09, 2023 |
| ASUSTek       | X550VC                      | Notebook    | [e2c932c285](https://linux-hardware.org/?probe=e2c932c285) | Dec 09, 2023 |
| Acer          | AOD257                      | Notebook    | [79c121ca0e](https://linux-hardware.org/?probe=79c121ca0e) | Dec 09, 2023 |
| Dell          | Vostro 3560                 | Notebook    | [d2abe7128b](https://linux-hardware.org/?probe=d2abe7128b) | Dec 09, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [955f530c70](https://linux-hardware.org/?probe=955f530c70) | Dec 08, 2023 |
| Acer          | AOD257                      | Notebook    | [c817dc5cca](https://linux-hardware.org/?probe=c817dc5cca) | Dec 08, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [045ab5efca](https://linux-hardware.org/?probe=045ab5efca) | Dec 08, 2023 |
| HP            | Compaq 6730b (NB034ET#UU... | Notebook    | [88c39cda86](https://linux-hardware.org/?probe=88c39cda86) | Dec 08, 2023 |
| HP            | Stream Laptop 14-cb1XX      | Notebook    | [fc2efc3edb](https://linux-hardware.org/?probe=fc2efc3edb) | Dec 07, 2023 |
| Lenovo        | ThinkPad P52 20MAS25B1X     | Notebook    | [767b4efa54](https://linux-hardware.org/?probe=767b4efa54) | Dec 06, 2023 |
| MSI           | MS-7309                     | Desktop     | [bfc6167f25](https://linux-hardware.org/?probe=bfc6167f25) | Dec 06, 2023 |
| MSI           | MS-7309                     | Desktop     | [556b1ebd9a](https://linux-hardware.org/?probe=556b1ebd9a) | Dec 06, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [bfd0ab0fc0](https://linux-hardware.org/?probe=bfd0ab0fc0) | Dec 06, 2023 |
| Dell          | Latitude 7490               | Notebook    | [364b5c38d4](https://linux-hardware.org/?probe=364b5c38d4) | Dec 06, 2023 |
| Gateway       | SX2851                      | Desktop     | [2ec497373d](https://linux-hardware.org/?probe=2ec497373d) | Dec 05, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [1748ab2263](https://linux-hardware.org/?probe=1748ab2263) | Dec 05, 2023 |
| ASUSTek       | P8Z68-V GEN3                | Desktop     | [3792e939db](https://linux-hardware.org/?probe=3792e939db) | Dec 05, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [549c56d2f8](https://linux-hardware.org/?probe=549c56d2f8) | Dec 04, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [9714fadd61](https://linux-hardware.org/?probe=9714fadd61) | Dec 04, 2023 |
| HP            | 255 G6 Notebook PC          | Notebook    | [ee58e73f03](https://linux-hardware.org/?probe=ee58e73f03) | Dec 04, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [23937a8b80](https://linux-hardware.org/?probe=23937a8b80) | Dec 04, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [0d13c9a0b6](https://linux-hardware.org/?probe=0d13c9a0b6) | Dec 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [dcb521e9aa](https://linux-hardware.org/?probe=dcb521e9aa) | Dec 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [4800fa6c99](https://linux-hardware.org/?probe=4800fa6c99) | Dec 04, 2023 |
| Dell          | 042P49 A00                  | Desktop     | [6bc5e84b91](https://linux-hardware.org/?probe=6bc5e84b91) | Dec 04, 2023 |
| Dell          | 042P49 A00                  | Desktop     | [813edffc94](https://linux-hardware.org/?probe=813edffc94) | Dec 04, 2023 |
| HP            | 3031h                       | Desktop     | [06a9e0c346](https://linux-hardware.org/?probe=06a9e0c346) | Dec 04, 2023 |
| SONIQ Digi... | Soniq 11.6inch Convertib... | Convertible | [4e67d597e1](https://linux-hardware.org/?probe=4e67d597e1) | Dec 04, 2023 |
| Dell          | Latitude 6430U              | Notebook    | [45d1723559](https://linux-hardware.org/?probe=45d1723559) | Dec 03, 2023 |
| Dell          | Latitude 6430U              | Notebook    | [1e4dda911f](https://linux-hardware.org/?probe=1e4dda911f) | Dec 03, 2023 |
| Lenovo        | YB1-X91L                    | Convertible | [e4f6d008cc](https://linux-hardware.org/?probe=e4f6d008cc) | Dec 03, 2023 |
| MSI           | 870A-G54                    | Desktop     | [46f9552be9](https://linux-hardware.org/?probe=46f9552be9) | Dec 03, 2023 |
| HP            | Pavilion dv7                | Notebook    | [42ddf2c00c](https://linux-hardware.org/?probe=42ddf2c00c) | Dec 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [dca543f661](https://linux-hardware.org/?probe=dca543f661) | Dec 03, 2023 |
| HP            | Pavilion dv5                | Notebook    | [40e03f76cf](https://linux-hardware.org/?probe=40e03f76cf) | Dec 03, 2023 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [7a932c5570](https://linux-hardware.org/?probe=7a932c5570) | Dec 02, 2023 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [9b46bc6583](https://linux-hardware.org/?probe=9b46bc6583) | Dec 02, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [f2a9f68180](https://linux-hardware.org/?probe=f2a9f68180) | Dec 02, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [e6d3755007](https://linux-hardware.org/?probe=e6d3755007) | Dec 02, 2023 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | Notebook    | [5d98fa1470](https://linux-hardware.org/?probe=5d98fa1470) | Dec 02, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [9dea837056](https://linux-hardware.org/?probe=9dea837056) | Dec 02, 2023 |
| Fujitsu       | LIFEBOOK E780               | Notebook    | [f1e82db736](https://linux-hardware.org/?probe=f1e82db736) | Dec 01, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [aab717794b](https://linux-hardware.org/?probe=aab717794b) | Dec 01, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [ca692e6dcb](https://linux-hardware.org/?probe=ca692e6dcb) | Dec 01, 2023 |
| MSI           | MPG Z590M GAMING EDGE WI... | Desktop     | [a8495b2209](https://linux-hardware.org/?probe=a8495b2209) | Dec 01, 2023 |
| Acer          | Aspire A517-52G             | Notebook    | [72702ceb3f](https://linux-hardware.org/?probe=72702ceb3f) | Dec 01, 2023 |
| HP            | 15                          | Notebook    | [7bd98a81f6](https://linux-hardware.org/?probe=7bd98a81f6) | Dec 01, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [02f2ca658e](https://linux-hardware.org/?probe=02f2ca658e) | Dec 01, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [e812beed5d](https://linux-hardware.org/?probe=e812beed5d) | Dec 01, 2023 |
| Acer          | Extensa M2610 V:1.0         | Desktop     | [e4c1bd6f51](https://linux-hardware.org/?probe=e4c1bd6f51) | Nov 30, 2023 |
| Acer          | Aspire A517-52G             | Notebook    | [33126bb441](https://linux-hardware.org/?probe=33126bb441) | Nov 30, 2023 |
| Toshiba       | Satellite L850D-131         | Notebook    | [483c7cfdf6](https://linux-hardware.org/?probe=483c7cfdf6) | Nov 30, 2023 |
| AMI           | AMD                         | Notebook    | [9f3f9ba617](https://linux-hardware.org/?probe=9f3f9ba617) | Nov 29, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B5602CBA... | Notebook    | [0c08316018](https://linux-hardware.org/?probe=0c08316018) | Nov 29, 2023 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [062cd64553](https://linux-hardware.org/?probe=062cd64553) | Nov 29, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [423e8001ab](https://linux-hardware.org/?probe=423e8001ab) | Nov 29, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [c934dcacd6](https://linux-hardware.org/?probe=c934dcacd6) | Nov 29, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [9af25bdb99](https://linux-hardware.org/?probe=9af25bdb99) | Nov 28, 2023 |
| Medion        | Erazer P7643 MD60133        | Notebook    | [65f090fe28](https://linux-hardware.org/?probe=65f090fe28) | Nov 28, 2023 |
| HP            | 15                          | Notebook    | [c1ca96368f](https://linux-hardware.org/?probe=c1ca96368f) | Nov 28, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 Ub 82KU    | Notebook    | [f99e3c8556](https://linux-hardware.org/?probe=f99e3c8556) | Nov 28, 2023 |
| ASUSTek       | K93SV                       | Notebook    | [f85fb01be1](https://linux-hardware.org/?probe=f85fb01be1) | Nov 28, 2023 |
| HP            | 15                          | Notebook    | [aba1e87e5c](https://linux-hardware.org/?probe=aba1e87e5c) | Nov 28, 2023 |
| Gigabyte      | Z87X-D3H-CF                 | Desktop     | [7d6885561f](https://linux-hardware.org/?probe=7d6885561f) | Nov 28, 2023 |
| Gigabyte      | Z87X-D3H-CF                 | Desktop     | [e106315577](https://linux-hardware.org/?probe=e106315577) | Nov 28, 2023 |
| Dell          | XPS 15 9550                 | Notebook    | [6d2e371a5f](https://linux-hardware.org/?probe=6d2e371a5f) | Nov 27, 2023 |
| Acer          | Aspire TC-280               | Desktop     | [bfd90230bc](https://linux-hardware.org/?probe=bfd90230bc) | Nov 27, 2023 |
| Lenovo        | Yoga 730-13IWL 81JR         | Convertible | [38dd158d3e](https://linux-hardware.org/?probe=38dd158d3e) | Nov 27, 2023 |
| Acer          | Aspire TC-280               | Desktop     | [4b2fec8699](https://linux-hardware.org/?probe=4b2fec8699) | Nov 27, 2023 |
| Dell          | Latitude D830               | Notebook    | [2e017edf81](https://linux-hardware.org/?probe=2e017edf81) | Nov 27, 2023 |
| HP            | ENVY m6                     | Notebook    | [41cff88708](https://linux-hardware.org/?probe=41cff88708) | Nov 26, 2023 |
| Apple         | MacBookPro5,4               | Notebook    | [fb45c81af9](https://linux-hardware.org/?probe=fb45c81af9) | Nov 26, 2023 |
| AZW           | Green G3                    | Desktop     | [c08be7a4cf](https://linux-hardware.org/?probe=c08be7a4cf) | Nov 26, 2023 |
| Toshiba       | TECRA W50-A                 | Notebook    | [91a2348496](https://linux-hardware.org/?probe=91a2348496) | Nov 25, 2023 |
| ASUSTek       | ROG Maximus Z790 HERO       | Desktop     | [e4062fc1e4](https://linux-hardware.org/?probe=e4062fc1e4) | Nov 25, 2023 |
| HP            | 82F1                        | Desktop     | [09c7b87413](https://linux-hardware.org/?probe=09c7b87413) | Nov 24, 2023 |
| Lenovo        | Z710 20250                  | Notebook    | [c9522c065e](https://linux-hardware.org/?probe=c9522c065e) | Nov 24, 2023 |
| HP            | 82F1                        | Desktop     | [9ed00910d4](https://linux-hardware.org/?probe=9ed00910d4) | Nov 24, 2023 |
| Lenovo        | ThinkPad T570 20HAS0K501    | Notebook    | [4fe6d8f889](https://linux-hardware.org/?probe=4fe6d8f889) | Nov 24, 2023 |
| Lenovo        | MAHOBAY Win8 STD EM DPK ... | All in one  | [a86dba284f](https://linux-hardware.org/?probe=a86dba284f) | Nov 24, 2023 |
| Toshiba       | TECRA R850                  | Notebook    | [6930db743c](https://linux-hardware.org/?probe=6930db743c) | Nov 24, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [eb779ea004](https://linux-hardware.org/?probe=eb779ea004) | Nov 24, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [0d60447eea](https://linux-hardware.org/?probe=0d60447eea) | Nov 24, 2023 |
| HP            | G5000 (GF767EA#B1A)         | Notebook    | [5239511cca](https://linux-hardware.org/?probe=5239511cca) | Nov 24, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [9d5752b2d8](https://linux-hardware.org/?probe=9d5752b2d8) | Nov 24, 2023 |
| Unknown       | M17                         | Notebook    | [d3d7d176b4](https://linux-hardware.org/?probe=d3d7d176b4) | Nov 23, 2023 |
| Medion        | E5214                       | Notebook    | [f3ab89b2d3](https://linux-hardware.org/?probe=f3ab89b2d3) | Nov 23, 2023 |
| Acer          | Aspire E5-511               | Notebook    | [87ccf00042](https://linux-hardware.org/?probe=87ccf00042) | Nov 23, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [c883420b97](https://linux-hardware.org/?probe=c883420b97) | Nov 23, 2023 |
| Gigabyte      | GA-MA74GMT-S2               | Desktop     | [440e7b6c7c](https://linux-hardware.org/?probe=440e7b6c7c) | Nov 23, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | Notebook    | [3b995f6b47](https://linux-hardware.org/?probe=3b995f6b47) | Nov 23, 2023 |
| Toshiba       | Satellite L850D-131         | Notebook    | [8810505a5a](https://linux-hardware.org/?probe=8810505a5a) | Nov 23, 2023 |
| Lenovo        | ThinkPad T440 20B7S0VA05    | Notebook    | [37a1e3b979](https://linux-hardware.org/?probe=37a1e3b979) | Nov 23, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [0137a4a556](https://linux-hardware.org/?probe=0137a4a556) | Nov 23, 2023 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [c5a84018e9](https://linux-hardware.org/?probe=c5a84018e9) | Nov 23, 2023 |
| HP            | 3029h                       | Desktop     | [2dd2ec759b](https://linux-hardware.org/?probe=2dd2ec759b) | Nov 23, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [fca11dfd70](https://linux-hardware.org/?probe=fca11dfd70) | Nov 23, 2023 |
| Acer          | Aspire ES1-731              | Notebook    | [649e8a4e24](https://linux-hardware.org/?probe=649e8a4e24) | Nov 22, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | Notebook    | [8d492b21b0](https://linux-hardware.org/?probe=8d492b21b0) | Nov 22, 2023 |
| HUAWEI        | BoDE-WXX9                   | Notebook    | [343ba69496](https://linux-hardware.org/?probe=343ba69496) | Nov 22, 2023 |
| HP            | 3561                        | All in one  | [aef249e21a](https://linux-hardware.org/?probe=aef249e21a) | Nov 22, 2023 |
| HUAWEI        | BoDE-WXX9                   | Notebook    | [b365872b3f](https://linux-hardware.org/?probe=b365872b3f) | Nov 22, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [1f07a66db1](https://linux-hardware.org/?probe=1f07a66db1) | Nov 22, 2023 |
| Samsung       | 530XBB                      | Notebook    | [c31efedbdf](https://linux-hardware.org/?probe=c31efedbdf) | Nov 22, 2023 |
| ASUSTek       | E201NA                      | Notebook    | [11f7e8f675](https://linux-hardware.org/?probe=11f7e8f675) | Nov 22, 2023 |
| HP            | EliteBook Folio 1020 G1     | Notebook    | [022f885fe9](https://linux-hardware.org/?probe=022f885fe9) | Nov 22, 2023 |
| Notebook      | NL40_50CU                   | Notebook    | [94885b9878](https://linux-hardware.org/?probe=94885b9878) | Nov 21, 2023 |
| AZW           | MINI S 10                   | Desktop     | [47bd270ae8](https://linux-hardware.org/?probe=47bd270ae8) | Nov 21, 2023 |
| HP            | Stream Notebook PC 11       | Notebook    | [c363e01e5f](https://linux-hardware.org/?probe=c363e01e5f) | Nov 21, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [f9136272f9](https://linux-hardware.org/?probe=f9136272f9) | Nov 21, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [6e0d000498](https://linux-hardware.org/?probe=6e0d000498) | Nov 20, 2023 |
| Apple         | MacBookPro14,3              | Notebook    | [3664fc3164](https://linux-hardware.org/?probe=3664fc3164) | Nov 20, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [6c2755ced9](https://linux-hardware.org/?probe=6c2755ced9) | Nov 20, 2023 |
| Lenovo        | ThinkPad Edge E530 32599... | Notebook    | [f472f3fd2e](https://linux-hardware.org/?probe=f472f3fd2e) | Nov 20, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [8fbd1e56eb](https://linux-hardware.org/?probe=8fbd1e56eb) | Nov 20, 2023 |
| Lenovo        | ThinkPad T460 20FMS22Q00    | Notebook    | [84df1d0476](https://linux-hardware.org/?probe=84df1d0476) | Nov 20, 2023 |
| HUAWEI        | CREFG-XX                    | Notebook    | [97b8871652](https://linux-hardware.org/?probe=97b8871652) | Nov 20, 2023 |
| Medion        | E5214                       | Notebook    | [8e3148e284](https://linux-hardware.org/?probe=8e3148e284) | Nov 20, 2023 |
| HP            | ProBook 430 G2              | Notebook    | [e0a3622122](https://linux-hardware.org/?probe=e0a3622122) | Nov 20, 2023 |
| Gigabyte      | GA-MA78G-DS3H               | Desktop     | [8047aac511](https://linux-hardware.org/?probe=8047aac511) | Nov 20, 2023 |
| MSI           | Z97-G55 SLI                 | Desktop     | [9137a70965](https://linux-hardware.org/?probe=9137a70965) | Nov 20, 2023 |
| AZW           | MINI S 10                   | Desktop     | [a1358be402](https://linux-hardware.org/?probe=a1358be402) | Nov 20, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [468cc043b8](https://linux-hardware.org/?probe=468cc043b8) | Nov 19, 2023 |
| HUAWEI        | CREFG-XX                    | Notebook    | [be15ab8952](https://linux-hardware.org/?probe=be15ab8952) | Nov 19, 2023 |
| Lenovo        | ThinkPad T460 20FMS22Q00    | Notebook    | [626d8d9409](https://linux-hardware.org/?probe=626d8d9409) | Nov 19, 2023 |
| Intel         | H61                         | Desktop     | [bdab1dc80a](https://linux-hardware.org/?probe=bdab1dc80a) | Nov 19, 2023 |
| HUAWEI        | CREFG-XX                    | Notebook    | [747979b60f](https://linux-hardware.org/?probe=747979b60f) | Nov 19, 2023 |
| Intel         | H61                         | Desktop     | [4b5806ba4c](https://linux-hardware.org/?probe=4b5806ba4c) | Nov 19, 2023 |
| Acer          | Spin SP513-52N              | Convertible | [339c8003a9](https://linux-hardware.org/?probe=339c8003a9) | Nov 19, 2023 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [6876ff8fc6](https://linux-hardware.org/?probe=6876ff8fc6) | Nov 19, 2023 |
| Acer          | Extensa M2610 V:1.0         | Desktop     | [7b70ac1965](https://linux-hardware.org/?probe=7b70ac1965) | Nov 19, 2023 |
| Medion        | E5214                       | Notebook    | [4513f3394d](https://linux-hardware.org/?probe=4513f3394d) | Nov 18, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [b62a8b07f4](https://linux-hardware.org/?probe=b62a8b07f4) | Nov 18, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS AC    | Desktop     | [cb10d99771](https://linux-hardware.org/?probe=cb10d99771) | Nov 18, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [ec19f0fa52](https://linux-hardware.org/?probe=ec19f0fa52) | Nov 18, 2023 |
| Lenovo        | ThinkCentre M90p 5536Y1K    | Desktop     | [6bdc4cb524](https://linux-hardware.org/?probe=6bdc4cb524) | Nov 18, 2023 |
| Lenovo        | ThinkPad Yoga 11e 3rd Ge... | Convertible | [75cd18198b](https://linux-hardware.org/?probe=75cd18198b) | Nov 18, 2023 |
| Dell          | Latitude 5490               | Notebook    | [b3da1a92d0](https://linux-hardware.org/?probe=b3da1a92d0) | Nov 17, 2023 |
| Compaq        | Presario CQ-17              | Notebook    | [7b53a480e4](https://linux-hardware.org/?probe=7b53a480e4) | Nov 17, 2023 |
| ASUSTek       | ROG Strix G814JI_G814JI     | Notebook    | [54bad5da51](https://linux-hardware.org/?probe=54bad5da51) | Nov 17, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [d087235304](https://linux-hardware.org/?probe=d087235304) | Nov 17, 2023 |
| Toshiba       | TECRA R850                  | Notebook    | [9974b99f5a](https://linux-hardware.org/?probe=9974b99f5a) | Nov 16, 2023 |
| HP            | Pavilion g7                 | Notebook    | [9f8b6f3432](https://linux-hardware.org/?probe=9f8b6f3432) | Nov 16, 2023 |
| HP            | Pavilion g7                 | Notebook    | [0c4816a4f2](https://linux-hardware.org/?probe=0c4816a4f2) | Nov 16, 2023 |
| ECS           | H61H2-M2                    | Desktop     | [df572cd989](https://linux-hardware.org/?probe=df572cd989) | Nov 15, 2023 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [7edaa0f1be](https://linux-hardware.org/?probe=7edaa0f1be) | Nov 15, 2023 |
| HP            | InsydeH2O EFI BIOS          | Notebook    | [559ef6212b](https://linux-hardware.org/?probe=559ef6212b) | Nov 15, 2023 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [d79f8e5ed5](https://linux-hardware.org/?probe=d79f8e5ed5) | Nov 14, 2023 |
| HP            | ZBook 14u G6                | Notebook    | [c6471dbbfd](https://linux-hardware.org/?probe=c6471dbbfd) | Nov 14, 2023 |
| Adreamer      | PN1308P                     | Notebook    | [8c4d2fca5a](https://linux-hardware.org/?probe=8c4d2fca5a) | Nov 14, 2023 |
| Adreamer      | PN1308P                     | Notebook    | [5efc66eebc](https://linux-hardware.org/?probe=5efc66eebc) | Nov 14, 2023 |
| HP            | Compaq 6910p                | Notebook    | [019a154d30](https://linux-hardware.org/?probe=019a154d30) | Nov 14, 2023 |
| Dell          | System Vostro 3750          | Notebook    | [513485cc8f](https://linux-hardware.org/?probe=513485cc8f) | Nov 14, 2023 |
| Tactus        | GeoBook 110                 | Notebook    | [077bbdc325](https://linux-hardware.org/?probe=077bbdc325) | Nov 14, 2023 |
| Tactus        | GeoBook 110                 | Notebook    | [5e50f31cbb](https://linux-hardware.org/?probe=5e50f31cbb) | Nov 14, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [d00bbdf844](https://linux-hardware.org/?probe=d00bbdf844) | Nov 14, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [493702778b](https://linux-hardware.org/?probe=493702778b) | Nov 14, 2023 |
| Fujitsu       | D2619 S26361-D2619-N15 W... | Server      | [d9f5b1502c](https://linux-hardware.org/?probe=d9f5b1502c) | Nov 14, 2023 |
| Fujitsu       | D2619 S26361-D2619-N15 W... | Server      | [56925134d7](https://linux-hardware.org/?probe=56925134d7) | Nov 14, 2023 |
| JHZD          | BQM5                        | Desktop     | [cab813ae6e](https://linux-hardware.org/?probe=cab813ae6e) | Nov 14, 2023 |
| Gigabyte      | Z390 UD                     | Desktop     | [f961fee784](https://linux-hardware.org/?probe=f961fee784) | Nov 14, 2023 |
| Dell          | System Vostro 3750          | Notebook    | [3c336ad6e1](https://linux-hardware.org/?probe=3c336ad6e1) | Nov 14, 2023 |
| Lenovo        | ThinkPad E550 20DF00CNGE    | Notebook    | [35e0f85cf3](https://linux-hardware.org/?probe=35e0f85cf3) | Nov 13, 2023 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [73a53ca5a4](https://linux-hardware.org/?probe=73a53ca5a4) | Nov 13, 2023 |
| Dell          | 0RW199                      | Desktop     | [e3b364ccd6](https://linux-hardware.org/?probe=e3b364ccd6) | Nov 13, 2023 |
| Intel         | H61                         | Desktop     | [cbefae3544](https://linux-hardware.org/?probe=cbefae3544) | Nov 13, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [a0105ee2c8](https://linux-hardware.org/?probe=a0105ee2c8) | Nov 13, 2023 |
| HP            | 15                          | Notebook    | [20b22b2eeb](https://linux-hardware.org/?probe=20b22b2eeb) | Nov 13, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [83d6eddd15](https://linux-hardware.org/?probe=83d6eddd15) | Nov 12, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [8bcc86ef17](https://linux-hardware.org/?probe=8bcc86ef17) | Nov 12, 2023 |
| HP            | ProLiant ML350e Gen8 v2     | Desktop     | [f5de128dd1](https://linux-hardware.org/?probe=f5de128dd1) | Nov 12, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [d46548a5e6](https://linux-hardware.org/?probe=d46548a5e6) | Nov 12, 2023 |
| Dell          | 0HN7XN A01                  | Desktop     | [cd4230cf5b](https://linux-hardware.org/?probe=cd4230cf5b) | Nov 12, 2023 |
| HUAWEI        | RLEFG-XX                    | Notebook    | [5f413be4fc](https://linux-hardware.org/?probe=5f413be4fc) | Nov 12, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [1d2a92df29](https://linux-hardware.org/?probe=1d2a92df29) | Nov 12, 2023 |
| Lenovo        | ThinkPad E580 20KS001RGE    | Notebook    | [55b706c3ec](https://linux-hardware.org/?probe=55b706c3ec) | Nov 12, 2023 |
| Lenovo        | ThinkPad T460 20FMS22Q00    | Notebook    | [4c40c1d213](https://linux-hardware.org/?probe=4c40c1d213) | Nov 11, 2023 |
| Unknown       | Unknown                     | Notebook    | [16acb0dabc](https://linux-hardware.org/?probe=16acb0dabc) | Nov 11, 2023 |
| Toshiba       | Satellite L655              | Notebook    | [b3c59942a1](https://linux-hardware.org/?probe=b3c59942a1) | Nov 11, 2023 |
| Intel         | H61                         | Desktop     | [c65f2e03f6](https://linux-hardware.org/?probe=c65f2e03f6) | Nov 11, 2023 |
| HP            | Presario CQ62               | Notebook    | [584d709751](https://linux-hardware.org/?probe=584d709751) | Nov 11, 2023 |
| Toshiba       | PORTEGE Z30-A               | Notebook    | [1b3661590f](https://linux-hardware.org/?probe=1b3661590f) | Nov 11, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [13798a5389](https://linux-hardware.org/?probe=13798a5389) | Nov 11, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [b962155541](https://linux-hardware.org/?probe=b962155541) | Nov 11, 2023 |
| Dell          | Precision M6800             | Notebook    | [4ad69afe3a](https://linux-hardware.org/?probe=4ad69afe3a) | Nov 11, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [e4fd0fa1f0](https://linux-hardware.org/?probe=e4fd0fa1f0) | Nov 10, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [fda2670cc5](https://linux-hardware.org/?probe=fda2670cc5) | Nov 10, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [08c8ac6e4d](https://linux-hardware.org/?probe=08c8ac6e4d) | Nov 09, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [c0e0567705](https://linux-hardware.org/?probe=c0e0567705) | Nov 09, 2023 |
| Lenovo        | Z40-70 20366                | Notebook    | [f1968605c1](https://linux-hardware.org/?probe=f1968605c1) | Nov 09, 2023 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [97e4b3093b](https://linux-hardware.org/?probe=97e4b3093b) | Nov 09, 2023 |
| Dell          | 0RW199                      | Desktop     | [11e414d343](https://linux-hardware.org/?probe=11e414d343) | Nov 08, 2023 |
| Acer          | Aspire E1-531               | Notebook    | [6a30b05dcb](https://linux-hardware.org/?probe=6a30b05dcb) | Nov 08, 2023 |
| PEAQ          | PNB C1014-I1B1 MD99447      | Notebook    | [33d5a0aa8c](https://linux-hardware.org/?probe=33d5a0aa8c) | Nov 08, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [b48cc5df9c](https://linux-hardware.org/?probe=b48cc5df9c) | Nov 08, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [cc75144dea](https://linux-hardware.org/?probe=cc75144dea) | Nov 08, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [38b21b9f64](https://linux-hardware.org/?probe=38b21b9f64) | Nov 08, 2023 |
| Acer          | Aspire E5-553G              | Notebook    | [f77e4d524d](https://linux-hardware.org/?probe=f77e4d524d) | Nov 08, 2023 |
| HP            | Compaq 6830s                | Notebook    | [069a45be37](https://linux-hardware.org/?probe=069a45be37) | Nov 08, 2023 |
| Gigabyte      | GA-890FXA-UD5               | Desktop     | [abb549b943](https://linux-hardware.org/?probe=abb549b943) | Nov 07, 2023 |
| Lenovo        | ThinkPad T440p 20AWS08S0... | Notebook    | [b7e993f677](https://linux-hardware.org/?probe=b7e993f677) | Nov 07, 2023 |
| Dell          | 0KWVT8 A03                  | Desktop     | [864f50cabf](https://linux-hardware.org/?probe=864f50cabf) | Nov 07, 2023 |
| Fujitsu Si... | AMILO Li 1818               | Notebook    | [ab74cc1cc6](https://linux-hardware.org/?probe=ab74cc1cc6) | Nov 07, 2023 |
| Dell          | Venue 11 Pro 5130           | Notebook    | [c2434cadfc](https://linux-hardware.org/?probe=c2434cadfc) | Nov 07, 2023 |
| Dell          | Venue 11 Pro 5130           | Notebook    | [a5628b0f9d](https://linux-hardware.org/?probe=a5628b0f9d) | Nov 07, 2023 |
| Lenovo        | Gardenia CRB SDK0J40709 ... | All in one  | [ef772812b1](https://linux-hardware.org/?probe=ef772812b1) | Nov 07, 2023 |
| Acer          | Aspire ES1-572              | Notebook    | [eea33256f6](https://linux-hardware.org/?probe=eea33256f6) | Nov 07, 2023 |
| Lenovo        | IdeaPad S400u 20213         | Notebook    | [5ddd610c2d](https://linux-hardware.org/?probe=5ddd610c2d) | Nov 06, 2023 |
| Dell          | Venue 11 Pro 5130           | Notebook    | [5d63a1487d](https://linux-hardware.org/?probe=5d63a1487d) | Nov 06, 2023 |
| Samsung       | DT1234567890 SEC_SW_REVI... | Desktop     | [4ef314d383](https://linux-hardware.org/?probe=4ef314d383) | Nov 06, 2023 |
| Acer          | Aspire ES1-521              | Notebook    | [8447756322](https://linux-hardware.org/?probe=8447756322) | Nov 06, 2023 |
| Acer          | Aspire ES1-521              | Notebook    | [af12dd22ba](https://linux-hardware.org/?probe=af12dd22ba) | Nov 06, 2023 |
| ASUSTek       | ROG Maximus XII FORMULA     | Desktop     | [6c8bb1840e](https://linux-hardware.org/?probe=6c8bb1840e) | Nov 05, 2023 |
| Dell          | Venue 11 Pro 5130           | Notebook    | [0facd311dc](https://linux-hardware.org/?probe=0facd311dc) | Nov 05, 2023 |
| Dell          | Venue 11 Pro 5130           | Notebook    | [27740d5118](https://linux-hardware.org/?probe=27740d5118) | Nov 05, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [38b95c0462](https://linux-hardware.org/?probe=38b95c0462) | Nov 05, 2023 |
| Dell          | Latitude E7450              | Notebook    | [71fe592aa3](https://linux-hardware.org/?probe=71fe592aa3) | Nov 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [4bf4b470a0](https://linux-hardware.org/?probe=4bf4b470a0) | Nov 05, 2023 |
| HP            | 1497                        | Desktop     | [734abf0595](https://linux-hardware.org/?probe=734abf0595) | Nov 05, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [8b3f431a00](https://linux-hardware.org/?probe=8b3f431a00) | Nov 05, 2023 |
| Toshiba       | IS 1412                     | Notebook    | [486d28dfeb](https://linux-hardware.org/?probe=486d28dfeb) | Nov 05, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [9d8a12d929](https://linux-hardware.org/?probe=9d8a12d929) | Nov 05, 2023 |
| Gigabyte      | M5NM1AI-GB                  | Desktop     | [99e2275a93](https://linux-hardware.org/?probe=99e2275a93) | Nov 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [dbd2e07499](https://linux-hardware.org/?probe=dbd2e07499) | Nov 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [e98e6bb977](https://linux-hardware.org/?probe=e98e6bb977) | Nov 05, 2023 |
| Toshiba       | IS 1412                     | Notebook    | [d423a5c34a](https://linux-hardware.org/?probe=d423a5c34a) | Nov 04, 2023 |
| Toshiba       | STI 001359                  | Desktop     | [ebf464dbb3](https://linux-hardware.org/?probe=ebf464dbb3) | Nov 04, 2023 |
| Apple         | Mac-F2268DC8                | All in one  | [1173519349](https://linux-hardware.org/?probe=1173519349) | Nov 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [38df9f5382](https://linux-hardware.org/?probe=38df9f5382) | Nov 04, 2023 |
| TrekStor      | Surfbook W2                 | Notebook    | [cfee0c0363](https://linux-hardware.org/?probe=cfee0c0363) | Nov 04, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [7a24e5115a](https://linux-hardware.org/?probe=7a24e5115a) | Nov 04, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [c07d28d9bc](https://linux-hardware.org/?probe=c07d28d9bc) | Nov 04, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [00cab2c4d1](https://linux-hardware.org/?probe=00cab2c4d1) | Nov 04, 2023 |
| Timi          | A35                         | Notebook    | [1baa5932cc](https://linux-hardware.org/?probe=1baa5932cc) | Nov 03, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [239e99c725](https://linux-hardware.org/?probe=239e99c725) | Nov 03, 2023 |
| Dell          | Latitude E6520              | Notebook    | [a0e05f5040](https://linux-hardware.org/?probe=a0e05f5040) | Nov 02, 2023 |
| ASUSTek       | T100TAF                     | Notebook    | [ea9f809740](https://linux-hardware.org/?probe=ea9f809740) | Nov 02, 2023 |
| Gigabyte      | Z790 GAMING X AX            | Desktop     | [c5e282cbad](https://linux-hardware.org/?probe=c5e282cbad) | Nov 02, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [4372a2d9eb](https://linux-hardware.org/?probe=4372a2d9eb) | Nov 02, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [fb7f16d298](https://linux-hardware.org/?probe=fb7f16d298) | Nov 02, 2023 |
| ASUSTek       | U36SD                       | Notebook    | [e2045d61a5](https://linux-hardware.org/?probe=e2045d61a5) | Nov 02, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [ef9bc3cc1e](https://linux-hardware.org/?probe=ef9bc3cc1e) | Nov 02, 2023 |
| ONDA          | Tablet                      | Tablet      | [1f8b5d6c72](https://linux-hardware.org/?probe=1f8b5d6c72) | Nov 01, 2023 |
| Dell          | 0XCR8D A01                  | Desktop     | [bc8414b164](https://linux-hardware.org/?probe=bc8414b164) | Nov 01, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [6db0212093](https://linux-hardware.org/?probe=6db0212093) | Nov 01, 2023 |
| Acer          | Aspire 5736Z                | Notebook    | [9fff8956bb](https://linux-hardware.org/?probe=9fff8956bb) | Nov 01, 2023 |
| Apple         | MacBookPro3,1               | Notebook    | [73a395f017](https://linux-hardware.org/?probe=73a395f017) | Nov 01, 2023 |
| Lenovo        | MAHOBAY                     | Desktop     | [319e545ba5](https://linux-hardware.org/?probe=319e545ba5) | Oct 31, 2023 |
| MSI           | A320M PRO-M2 V2             | Desktop     | [3b667e2123](https://linux-hardware.org/?probe=3b667e2123) | Oct 31, 2023 |
| Pegatron      | EVANS                       | Desktop     | [3ea2a80843](https://linux-hardware.org/?probe=3ea2a80843) | Oct 31, 2023 |
| Pegatron      | EVANS                       | Desktop     | [52c3eeea68](https://linux-hardware.org/?probe=52c3eeea68) | Oct 31, 2023 |
| RCA           | W122SC24T2                  | Tablet      | [1313389b98](https://linux-hardware.org/?probe=1313389b98) | Oct 31, 2023 |
| RCA           | W122SC24T2                  | Tablet      | [f46f159a0c](https://linux-hardware.org/?probe=f46f159a0c) | Oct 31, 2023 |
| Sony          | SVS15116GAB                 | Notebook    | [03634a7731](https://linux-hardware.org/?probe=03634a7731) | Oct 30, 2023 |
| MSI           | Delta 15 A5EFK              | Notebook    | [185b65ebc1](https://linux-hardware.org/?probe=185b65ebc1) | Oct 30, 2023 |
| HP            | 21F5 0A                     | Desktop     | [097ce56daf](https://linux-hardware.org/?probe=097ce56daf) | Oct 30, 2023 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | Desktop     | [c447277c0b](https://linux-hardware.org/?probe=c447277c0b) | Oct 30, 2023 |
| Notebook      | PA70Hx                      | Notebook    | [627ed781b5](https://linux-hardware.org/?probe=627ed781b5) | Oct 30, 2023 |
| HP            | 15                          | Notebook    | [1480b12f56](https://linux-hardware.org/?probe=1480b12f56) | Oct 30, 2023 |
| HP            | Notebook                    | Notebook    | [5538a0e3b2](https://linux-hardware.org/?probe=5538a0e3b2) | Oct 30, 2023 |
| HP            | Pavilion dv4                | Notebook    | [854806c6f4](https://linux-hardware.org/?probe=854806c6f4) | Oct 29, 2023 |
| HP            | 1998                        | Desktop     | [2182b05a45](https://linux-hardware.org/?probe=2182b05a45) | Oct 29, 2023 |
| HP            | ENVY 17                     | Notebook    | [8852bab8c1](https://linux-hardware.org/?probe=8852bab8c1) | Oct 29, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [28f261fb9a](https://linux-hardware.org/?probe=28f261fb9a) | Oct 29, 2023 |
| Lenovo        | ThinkPad X270 20HMS1T600    | Notebook    | [97fbe59dd7](https://linux-hardware.org/?probe=97fbe59dd7) | Oct 29, 2023 |
| Notebook      | PA70Hx                      | Notebook    | [e13de47400](https://linux-hardware.org/?probe=e13de47400) | Oct 29, 2023 |
| Lenovo        | ThinkPad E420 1141BTU       | Notebook    | [867e950bca](https://linux-hardware.org/?probe=867e950bca) | Oct 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [a123ac023f](https://linux-hardware.org/?probe=a123ac023f) | Oct 29, 2023 |
| MSI           | Z370M MORTAR                | Desktop     | [0af3708cd3](https://linux-hardware.org/?probe=0af3708cd3) | Oct 29, 2023 |
| HP            | 18E4                        | Desktop     | [b192ce4f35](https://linux-hardware.org/?probe=b192ce4f35) | Oct 28, 2023 |
| ASUSTek       | ZenBook UX434IQ_Q407IQ      | Notebook    | [97eabba1a8](https://linux-hardware.org/?probe=97eabba1a8) | Oct 28, 2023 |
| Dell          | 06X1TJ A00                  | Desktop     | [c2bc73c67b](https://linux-hardware.org/?probe=c2bc73c67b) | Oct 28, 2023 |
| Acer          | Aspire V3-772G              | Notebook    | [d48a91cce4](https://linux-hardware.org/?probe=d48a91cce4) | Oct 28, 2023 |
| ASUSTek       | P8B75-M                     | Desktop     | [b9830b7f02](https://linux-hardware.org/?probe=b9830b7f02) | Oct 28, 2023 |
| Lenovo        | 0x36C4 SDK0M26027 WIN 32... | All in one  | [98c2ece6fd](https://linux-hardware.org/?probe=98c2ece6fd) | Oct 28, 2023 |
| HP            | ENVY 17                     | Notebook    | [aaa99aaa53](https://linux-hardware.org/?probe=aaa99aaa53) | Oct 27, 2023 |
| Acer          | TravelMate Spin P614RN-5    | Convertible | [e337a1e208](https://linux-hardware.org/?probe=e337a1e208) | Oct 27, 2023 |
| HCL Infosy... | HCL ME Laptop               | Notebook    | [a23dc90a3b](https://linux-hardware.org/?probe=a23dc90a3b) | Oct 27, 2023 |
| MSI           | Boston                      | Desktop     | [66f7505c8b](https://linux-hardware.org/?probe=66f7505c8b) | Oct 27, 2023 |
| Thomson       | WWNEO14C-4BK32F             | Notebook    | [516a5ee33b](https://linux-hardware.org/?probe=516a5ee33b) | Oct 27, 2023 |
| HP            | 2215                        | Desktop     | [01fd79c4fe](https://linux-hardware.org/?probe=01fd79c4fe) | Oct 26, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [463b5f73b5](https://linux-hardware.org/?probe=463b5f73b5) | Oct 26, 2023 |
| ASUSTek       | ZenBook UX434IQ_Q407IQ      | Notebook    | [763e54c87b](https://linux-hardware.org/?probe=763e54c87b) | Oct 26, 2023 |
| HP            | G61                         | Notebook    | [d184a33522](https://linux-hardware.org/?probe=d184a33522) | Oct 26, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [67021475e9](https://linux-hardware.org/?probe=67021475e9) | Oct 26, 2023 |
| ASUSTek       | PRIME X370-A                | Desktop     | [ec0dcdaa76](https://linux-hardware.org/?probe=ec0dcdaa76) | Oct 26, 2023 |
| ASUSTek       | PRIME X370-A                | Desktop     | [4f4d354524](https://linux-hardware.org/?probe=4f4d354524) | Oct 26, 2023 |
| Lenovo        | 36EB SDK0J40700 WIN 3258... | Desktop     | [ca4ce5575c](https://linux-hardware.org/?probe=ca4ce5575c) | Oct 26, 2023 |
| HP            | Pavilion g7                 | Notebook    | [4699d107df](https://linux-hardware.org/?probe=4699d107df) | Oct 26, 2023 |
| LORD ELECT... | Guso G4x + ICH7 Series M... | Desktop     | [c6f81cf996](https://linux-hardware.org/?probe=c6f81cf996) | Oct 25, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [3c8f87fe9e](https://linux-hardware.org/?probe=3c8f87fe9e) | Oct 25, 2023 |
| Lenovo        | 0x36C4 SDK0M26027 WIN 32... | All in one  | [e0534a1c2a](https://linux-hardware.org/?probe=e0534a1c2a) | Oct 25, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [cd1abadd3a](https://linux-hardware.org/?probe=cd1abadd3a) | Oct 25, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [6f9c14dc54](https://linux-hardware.org/?probe=6f9c14dc54) | Oct 24, 2023 |
| Acer          | Aspire 5738                 | Notebook    | [039878b1b2](https://linux-hardware.org/?probe=039878b1b2) | Oct 24, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [706967e8e6](https://linux-hardware.org/?probe=706967e8e6) | Oct 24, 2023 |
| Gigabyte      | B85M-D3V Plus               | Desktop     | [845b1f10ef](https://linux-hardware.org/?probe=845b1f10ef) | Oct 24, 2023 |
| Dell          | 0RCPW3 A03                  | Desktop     | [a461b9f3e7](https://linux-hardware.org/?probe=a461b9f3e7) | Oct 23, 2023 |
| Dell          | 0R790T A00                  | Desktop     | [905555c7d5](https://linux-hardware.org/?probe=905555c7d5) | Oct 23, 2023 |
| Dell          | 0R790T A00                  | Desktop     | [5f6d67d67e](https://linux-hardware.org/?probe=5f6d67d67e) | Oct 23, 2023 |
| Fanless Mi... | Rev GMLR1                   | Mini pc     | [cd4e6f4d07](https://linux-hardware.org/?probe=cd4e6f4d07) | Oct 23, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [961b658ac5](https://linux-hardware.org/?probe=961b658ac5) | Oct 23, 2023 |
| Lenovo        | ThinkPad A485 20MVS0X62X    | Notebook    | [52661c1969](https://linux-hardware.org/?probe=52661c1969) | Oct 22, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [6f89b3f8ad](https://linux-hardware.org/?probe=6f89b3f8ad) | Oct 22, 2023 |
| ONDA          | Tablet                      | Tablet      | [2ef7c07bdf](https://linux-hardware.org/?probe=2ef7c07bdf) | Oct 22, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [ff9e1d6c16](https://linux-hardware.org/?probe=ff9e1d6c16) | Oct 22, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [9999b4b89a](https://linux-hardware.org/?probe=9999b4b89a) | Oct 22, 2023 |
| Dell          | Precision 7530              | Notebook    | [92f2a2c99e](https://linux-hardware.org/?probe=92f2a2c99e) | Oct 22, 2023 |
| ASUSTek       | X453MA                      | Notebook    | [ef8715c7a7](https://linux-hardware.org/?probe=ef8715c7a7) | Oct 21, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [081a658255](https://linux-hardware.org/?probe=081a658255) | Oct 21, 2023 |
| TrekStor      | Surfbook W2                 | Notebook    | [001d67067b](https://linux-hardware.org/?probe=001d67067b) | Oct 21, 2023 |
| ONDA          | Tablet                      | Tablet      | [835a5e9d6d](https://linux-hardware.org/?probe=835a5e9d6d) | Oct 21, 2023 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [5536078e9f](https://linux-hardware.org/?probe=5536078e9f) | Oct 21, 2023 |
| HP            | Laptop 14-cf2xxx            | Notebook    | [ef8c0bb04c](https://linux-hardware.org/?probe=ef8c0bb04c) | Oct 21, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [330cbe85c6](https://linux-hardware.org/?probe=330cbe85c6) | Oct 21, 2023 |
| HP            | Pavilion dv6                | Notebook    | [a7ee33da8f](https://linux-hardware.org/?probe=a7ee33da8f) | Oct 21, 2023 |
| Dell          | Inspiron 7560               | Notebook    | [6b9df8da7d](https://linux-hardware.org/?probe=6b9df8da7d) | Oct 21, 2023 |
| ASUSTek       | X453MA                      | Notebook    | [11d8517f7e](https://linux-hardware.org/?probe=11d8517f7e) | Oct 20, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [9ce038aa93](https://linux-hardware.org/?probe=9ce038aa93) | Oct 20, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [d8b8f7bafe](https://linux-hardware.org/?probe=d8b8f7bafe) | Oct 20, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [cb8d8311e7](https://linux-hardware.org/?probe=cb8d8311e7) | Oct 20, 2023 |
| HP            | Laptop 14-cf2xxx            | Notebook    | [3dd8426b8f](https://linux-hardware.org/?probe=3dd8426b8f) | Oct 20, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [af96c09a64](https://linux-hardware.org/?probe=af96c09a64) | Oct 19, 2023 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | Desktop     | [77079711d3](https://linux-hardware.org/?probe=77079711d3) | Oct 19, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [7fed113f9b](https://linux-hardware.org/?probe=7fed113f9b) | Oct 19, 2023 |
| ALLDOCUBE     | KnoteGo                     | Tablet      | [17833d30dc](https://linux-hardware.org/?probe=17833d30dc) | Oct 19, 2023 |
| HP            | 829A                        | Mini pc     | [8a3f72e9ef](https://linux-hardware.org/?probe=8a3f72e9ef) | Oct 19, 2023 |
| Dell          | Latitude 5490               | Notebook    | [cdf021cc62](https://linux-hardware.org/?probe=cdf021cc62) | Oct 19, 2023 |
| Microsoft     | Surface Pro 6               | Tablet      | [060a642de4](https://linux-hardware.org/?probe=060a642de4) | Oct 19, 2023 |
| Microsoft     | Surface Pro 6               | Tablet      | [051cd3c21e](https://linux-hardware.org/?probe=051cd3c21e) | Oct 19, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [d37e5bc4f2](https://linux-hardware.org/?probe=d37e5bc4f2) | Oct 19, 2023 |
| ASUSTek       | X751SA                      | Notebook    | [21a2a5b900](https://linux-hardware.org/?probe=21a2a5b900) | Oct 18, 2023 |
| ONDA          | Tablet                      | Tablet      | [6a43a8d57d](https://linux-hardware.org/?probe=6a43a8d57d) | Oct 18, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [cde2726f48](https://linux-hardware.org/?probe=cde2726f48) | Oct 18, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [2985805059](https://linux-hardware.org/?probe=2985805059) | Oct 18, 2023 |
| EPSON DIRE... | AT992E                      | Desktop     | [bdc9d825d8](https://linux-hardware.org/?probe=bdc9d825d8) | Oct 18, 2023 |
| EPSON DIRE... | AT992E                      | Desktop     | [ec5284109e](https://linux-hardware.org/?probe=ec5284109e) | Oct 18, 2023 |
| ASUSTek       | X200MA                      | Notebook    | [c1ea75561b](https://linux-hardware.org/?probe=c1ea75561b) | Oct 18, 2023 |
| Sony          | VGN-FZ31Z                   | Notebook    | [9a6fd46a7d](https://linux-hardware.org/?probe=9a6fd46a7d) | Oct 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [03cf657f5a](https://linux-hardware.org/?probe=03cf657f5a) | Oct 17, 2023 |
| Lenovo        | ThinkPad T420 4236KU9       | Notebook    | [f1e77b51bc](https://linux-hardware.org/?probe=f1e77b51bc) | Oct 17, 2023 |
| Acer          | Aspire A515-57G             | Notebook    | [7116f7edd9](https://linux-hardware.org/?probe=7116f7edd9) | Oct 17, 2023 |
| Acer          | Aspire SW5-012              | Notebook    | [848b8d7c20](https://linux-hardware.org/?probe=848b8d7c20) | Oct 17, 2023 |
| Lenovo        | ThinkPad T440 20B7S1D200    | Notebook    | [43185c1e5b](https://linux-hardware.org/?probe=43185c1e5b) | Oct 16, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [fd91b9ece9](https://linux-hardware.org/?probe=fd91b9ece9) | Oct 16, 2023 |
| Lenovo        | Yoga 7 16IAH7 82UF          | Convertible | [76e5cf1323](https://linux-hardware.org/?probe=76e5cf1323) | Oct 16, 2023 |
| Multilaser    | MLSH1H LINUX                | Notebook    | [e87c9aab74](https://linux-hardware.org/?probe=e87c9aab74) | Oct 16, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [a0f3ae3d1a](https://linux-hardware.org/?probe=a0f3ae3d1a) | Oct 16, 2023 |
| Multilaser    | MLSH1H LINUX                | Notebook    | [0ca88d127f](https://linux-hardware.org/?probe=0ca88d127f) | Oct 16, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [cfc61d2f3c](https://linux-hardware.org/?probe=cfc61d2f3c) | Oct 15, 2023 |
| Lenovo        | IdeaPad Y580 20132          | Notebook    | [77c1531b00](https://linux-hardware.org/?probe=77c1531b00) | Oct 15, 2023 |
| Lenovo        | IdeaPad Y580 20132          | Notebook    | [2960de2715](https://linux-hardware.org/?probe=2960de2715) | Oct 15, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [d22b6fa2e4](https://linux-hardware.org/?probe=d22b6fa2e4) | Oct 15, 2023 |
| ASUSTek       | P5Q PRO TURBO               | Desktop     | [16a117accb](https://linux-hardware.org/?probe=16a117accb) | Oct 15, 2023 |
| HP            | Pavilion g7                 | Notebook    | [309ca4d5c7](https://linux-hardware.org/?probe=309ca4d5c7) | Oct 15, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [d43a466e59](https://linux-hardware.org/?probe=d43a466e59) | Oct 14, 2023 |
| Lenovo        | Yoga 7 16IAH7 82UF          | Convertible | [39e9986b39](https://linux-hardware.org/?probe=39e9986b39) | Oct 14, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [c6321b8063](https://linux-hardware.org/?probe=c6321b8063) | Oct 14, 2023 |
| Dell          | Vostro 1015                 | Notebook    | [35a5d0ac7c](https://linux-hardware.org/?probe=35a5d0ac7c) | Oct 14, 2023 |
| Dell          | Vostro 1015                 | Notebook    | [081856b4e9](https://linux-hardware.org/?probe=081856b4e9) | Oct 14, 2023 |
| Apple         | MacBookPro3,1               | Notebook    | [0db9d6a5cf](https://linux-hardware.org/?probe=0db9d6a5cf) | Oct 14, 2023 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | Desktop     | [f4e7334b7e](https://linux-hardware.org/?probe=f4e7334b7e) | Oct 14, 2023 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [c2cbb1c407](https://linux-hardware.org/?probe=c2cbb1c407) | Oct 13, 2023 |
| HP            | 470 17 inch G9              | Notebook    | [d138f8f9f3](https://linux-hardware.org/?probe=d138f8f9f3) | Oct 13, 2023 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [17d1931208](https://linux-hardware.org/?probe=17d1931208) | Oct 13, 2023 |
| MSI           | B85M-E45                    | Desktop     | [6ad9d3ff3c](https://linux-hardware.org/?probe=6ad9d3ff3c) | Oct 13, 2023 |
| ASRock        | X570 Phantom Gaming X       | Desktop     | [ffd832c09d](https://linux-hardware.org/?probe=ffd832c09d) | Oct 13, 2023 |
| ASRock        | X570 Phantom Gaming X       | Desktop     | [c70591ee60](https://linux-hardware.org/?probe=c70591ee60) | Oct 12, 2023 |
| HP            | ProBook 455 15.6 inch G1... | Notebook    | [cc3dbe7ccd](https://linux-hardware.org/?probe=cc3dbe7ccd) | Oct 12, 2023 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [314d81343b](https://linux-hardware.org/?probe=314d81343b) | Oct 12, 2023 |
| Schenker      | XMG CORE (REN/M20)          | Notebook    | [48ee28954d](https://linux-hardware.org/?probe=48ee28954d) | Oct 12, 2023 |
| HP            | ProBook 455 15.6 inch G1... | Notebook    | [8c1ef64452](https://linux-hardware.org/?probe=8c1ef64452) | Oct 12, 2023 |
| HP            | Pavilion g7                 | Notebook    | [e276347e0a](https://linux-hardware.org/?probe=e276347e0a) | Oct 12, 2023 |
| Acer          | Aspire A317-55P             | Notebook    | [a4e8b9c99a](https://linux-hardware.org/?probe=a4e8b9c99a) | Oct 12, 2023 |
| Dell          | 0NDYHG A01                  | Desktop     | [02414ff1af](https://linux-hardware.org/?probe=02414ff1af) | Oct 11, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [916bfc1646](https://linux-hardware.org/?probe=916bfc1646) | Oct 11, 2023 |
| Acer          | Aspire A317-55P             | Notebook    | [3805200b55](https://linux-hardware.org/?probe=3805200b55) | Oct 11, 2023 |
| MSI           | Z97-G55 SLI                 | Desktop     | [cc50dc0894](https://linux-hardware.org/?probe=cc50dc0894) | Oct 11, 2023 |
| MSI           | Z97-G55 SLI                 | Desktop     | [754748eac6](https://linux-hardware.org/?probe=754748eac6) | Oct 11, 2023 |
| Dell          | 0XHGV1 A00                  | Desktop     | [adda7a23c2](https://linux-hardware.org/?probe=adda7a23c2) | Oct 11, 2023 |
| Acer          | Aspire 5750                 | Notebook    | [44a7bac1b9](https://linux-hardware.org/?probe=44a7bac1b9) | Oct 10, 2023 |
| AMI           | Intel                       | Desktop     | [1615dc16ba](https://linux-hardware.org/?probe=1615dc16ba) | Oct 10, 2023 |
| Acer          | Aspire A315-55G             | Notebook    | [df54ad11e5](https://linux-hardware.org/?probe=df54ad11e5) | Oct 10, 2023 |
| ASUSTek       | K42F                        | Notebook    | [0d099eb4f7](https://linux-hardware.org/?probe=0d099eb4f7) | Oct 10, 2023 |
| Lenovo        | Tiger Hill                  | Desktop     | [cdd9f65bf5](https://linux-hardware.org/?probe=cdd9f65bf5) | Oct 10, 2023 |
| Gigabyte      | H55M-USB3                   | Desktop     | [c4ae24b408](https://linux-hardware.org/?probe=c4ae24b408) | Oct 10, 2023 |
| Toshiba       | Satellite Pro R50-B         | Notebook    | [9b41869902](https://linux-hardware.org/?probe=9b41869902) | Oct 09, 2023 |
| Apple         | MacBookPro4,1               | Notebook    | [407c6f0e29](https://linux-hardware.org/?probe=407c6f0e29) | Oct 09, 2023 |
| Acer          | Aspire A315-55G             | Notebook    | [53e4e70567](https://linux-hardware.org/?probe=53e4e70567) | Oct 09, 2023 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [332ce6061d](https://linux-hardware.org/?probe=332ce6061d) | Oct 09, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | Notebook    | [8984311ce7](https://linux-hardware.org/?probe=8984311ce7) | Oct 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [1eeecb8823](https://linux-hardware.org/?probe=1eeecb8823) | Oct 08, 2023 |
| HP            | Pavilion 15                 | Notebook    | [ae1e07dd63](https://linux-hardware.org/?probe=ae1e07dd63) | Oct 08, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [067260a51f](https://linux-hardware.org/?probe=067260a51f) | Oct 08, 2023 |
| Shuttle       | FS110                       | Desktop     | [cd7c40ed57](https://linux-hardware.org/?probe=cd7c40ed57) | Oct 08, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [bd6094c5cd](https://linux-hardware.org/?probe=bd6094c5cd) | Oct 08, 2023 |
| Lenovo        | ThinkPad T460s 20FAS08W0... | Notebook    | [24dee8bc07](https://linux-hardware.org/?probe=24dee8bc07) | Oct 07, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [b82e5d0718](https://linux-hardware.org/?probe=b82e5d0718) | Oct 07, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [f347154767](https://linux-hardware.org/?probe=f347154767) | Oct 07, 2023 |
| UMAX          | N14R                        | Notebook    | [4ac10723f5](https://linux-hardware.org/?probe=4ac10723f5) | Oct 07, 2023 |
| UMAX          | N14R                        | Notebook    | [9852750745](https://linux-hardware.org/?probe=9852750745) | Oct 07, 2023 |
| Pegatron      | EVANS                       | Desktop     | [f798f24c90](https://linux-hardware.org/?probe=f798f24c90) | Oct 07, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [299eee42c7](https://linux-hardware.org/?probe=299eee42c7) | Oct 07, 2023 |
| Alienware     | M14xR2                      | Notebook    | [3b7dd3717c](https://linux-hardware.org/?probe=3b7dd3717c) | Oct 07, 2023 |
| Dynabook      | PORTEGE X30W-J              | Convertible | [aa212009a2](https://linux-hardware.org/?probe=aa212009a2) | Oct 06, 2023 |
| Dell          | Precision 5530              | Notebook    | [38fdcea75f](https://linux-hardware.org/?probe=38fdcea75f) | Oct 06, 2023 |
| Thomson       | GEN360-4C128BK              | Notebook    | [ec04ddb0ba](https://linux-hardware.org/?probe=ec04ddb0ba) | Oct 06, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [d68de2a20e](https://linux-hardware.org/?probe=d68de2a20e) | Oct 06, 2023 |
| Intel         | X99                         | Desktop     | [9bc14ff597](https://linux-hardware.org/?probe=9bc14ff597) | Oct 06, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [7add8932c3](https://linux-hardware.org/?probe=7add8932c3) | Oct 06, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [9be367f445](https://linux-hardware.org/?probe=9be367f445) | Oct 06, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [d343f99b47](https://linux-hardware.org/?probe=d343f99b47) | Oct 06, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [ff815f228b](https://linux-hardware.org/?probe=ff815f228b) | Oct 05, 2023 |
| Medion        | E4251 MD61435               | Notebook    | [b8f2dc6919](https://linux-hardware.org/?probe=b8f2dc6919) | Oct 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | Notebook    | [8313e4fb72](https://linux-hardware.org/?probe=8313e4fb72) | Oct 05, 2023 |
| Dell          | Latitude 7480               | Notebook    | [7eec2f8e4e](https://linux-hardware.org/?probe=7eec2f8e4e) | Oct 05, 2023 |
| Dell          | Latitude 7480               | Notebook    | [a80bc8f591](https://linux-hardware.org/?probe=a80bc8f591) | Oct 05, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [a6668a2378](https://linux-hardware.org/?probe=a6668a2378) | Oct 04, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [de22cbed3e](https://linux-hardware.org/?probe=de22cbed3e) | Oct 04, 2023 |
| Acer          | Aspire M3-581G              | Notebook    | [040dc9b84b](https://linux-hardware.org/?probe=040dc9b84b) | Oct 04, 2023 |
| Apple         | Mac-F22C86C8                | Mini pc     | [c3e7936a83](https://linux-hardware.org/?probe=c3e7936a83) | Oct 04, 2023 |
| Dell          | 0RW199                      | Desktop     | [f829184aa0](https://linux-hardware.org/?probe=f829184aa0) | Oct 04, 2023 |
| Dell          | G3 3579                     | Notebook    | [7730315a91](https://linux-hardware.org/?probe=7730315a91) | Oct 04, 2023 |
| Lenovo        | Tiger Hill                  | Desktop     | [4a3ef3e12f](https://linux-hardware.org/?probe=4a3ef3e12f) | Oct 03, 2023 |
| Acer          | Aspire ES1-521              | Notebook    | [1e6ec4d559](https://linux-hardware.org/?probe=1e6ec4d559) | Oct 03, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [c474599b04](https://linux-hardware.org/?probe=c474599b04) | Oct 03, 2023 |
| MSI           | Bravo 15 A4DDR              | Notebook    | [0ebc5c48b5](https://linux-hardware.org/?probe=0ebc5c48b5) | Oct 03, 2023 |
| MSI           | Bravo 15 A4DDR              | Notebook    | [00afde76db](https://linux-hardware.org/?probe=00afde76db) | Oct 03, 2023 |
| Pegatron      | EVANS                       | Desktop     | [3f2a4fe53e](https://linux-hardware.org/?probe=3f2a4fe53e) | Oct 03, 2023 |
| Gigabyte      | Z270-HD3-CF                 | Desktop     | [c23994e74a](https://linux-hardware.org/?probe=c23994e74a) | Oct 02, 2023 |
| HP            | Pavilion dv6                | Notebook    | [b210c95b8e](https://linux-hardware.org/?probe=b210c95b8e) | Oct 02, 2023 |
| HP            | Pavilion dv6                | Notebook    | [2519f8a695](https://linux-hardware.org/?probe=2519f8a695) | Oct 02, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [320836ef04](https://linux-hardware.org/?probe=320836ef04) | Oct 02, 2023 |
| Lenovo        | ThinkPad T14 Gen 4 21HDC... | Notebook    | [aa2d376e85](https://linux-hardware.org/?probe=aa2d376e85) | Oct 02, 2023 |
| MSI           | B85M-E45                    | Desktop     | [12fa4b4da3](https://linux-hardware.org/?probe=12fa4b4da3) | Oct 02, 2023 |
| Acer          | Aspire M3450                | Desktop     | [2c6f35e1d3](https://linux-hardware.org/?probe=2c6f35e1d3) | Oct 02, 2023 |
| Acer          | Aspire M3450                | Desktop     | [ded620f59b](https://linux-hardware.org/?probe=ded620f59b) | Oct 02, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [5698c85faa](https://linux-hardware.org/?probe=5698c85faa) | Oct 02, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [056bfb8474](https://linux-hardware.org/?probe=056bfb8474) | Oct 01, 2023 |
| HP            | 470 17 inch G9              | Notebook    | [c6043cc6cc](https://linux-hardware.org/?probe=c6043cc6cc) | Oct 01, 2023 |
| Intel         | X79M-S                      | Desktop     | [dfa1322112](https://linux-hardware.org/?probe=dfa1322112) | Oct 01, 2023 |
| MSI           | B75MA-E33                   | Desktop     | [8d558a64e8](https://linux-hardware.org/?probe=8d558a64e8) | Oct 01, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [127980fc54](https://linux-hardware.org/?probe=127980fc54) | Oct 01, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [e0cdb74f25](https://linux-hardware.org/?probe=e0cdb74f25) | Oct 01, 2023 |
| Toshiba       | Satellite C870-1C2          | Notebook    | [d9750c9040](https://linux-hardware.org/?probe=d9750c9040) | Sep 30, 2023 |
| Apple         | MacBookPro5,3               | Notebook    | [0669d0020d](https://linux-hardware.org/?probe=0669d0020d) | Sep 30, 2023 |
| Acer          | Predator G3610              | Desktop     | [cddfa514ba](https://linux-hardware.org/?probe=cddfa514ba) | Sep 30, 2023 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | Desktop     | [c93af00811](https://linux-hardware.org/?probe=c93af00811) | Sep 30, 2023 |
| MP            | MS-7848                     | Desktop     | [63d5662351](https://linux-hardware.org/?probe=63d5662351) | Sep 30, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [237492c356](https://linux-hardware.org/?probe=237492c356) | Sep 30, 2023 |
| Apple         | MacBookPro5,3               | Notebook    | [d249d5e114](https://linux-hardware.org/?probe=d249d5e114) | Sep 30, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [186991da49](https://linux-hardware.org/?probe=186991da49) | Sep 29, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [145f7eccd3](https://linux-hardware.org/?probe=145f7eccd3) | Sep 29, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [a318f83948](https://linux-hardware.org/?probe=a318f83948) | Sep 29, 2023 |
| Lenovo        | IdeaPad Slim 3 15IRU8 82... | Notebook    | [e9dd0291e0](https://linux-hardware.org/?probe=e9dd0291e0) | Sep 29, 2023 |
| ASUSTek       | X551MA                      | Notebook    | [8ba160ee59](https://linux-hardware.org/?probe=8ba160ee59) | Sep 29, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [4aa521a31f](https://linux-hardware.org/?probe=4aa521a31f) | Sep 29, 2023 |
| Lenovo        | ThinkPad R60 9461DXG        | Notebook    | [4f74530d68](https://linux-hardware.org/?probe=4f74530d68) | Sep 28, 2023 |
| Lenovo        | ThinkPad R60 9461DXG        | Notebook    | [5fb1e549ea](https://linux-hardware.org/?probe=5fb1e549ea) | Sep 28, 2023 |
| HP            | 2B35                        | Desktop     | [2f63f14724](https://linux-hardware.org/?probe=2f63f14724) | Sep 28, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [ce3a9f8960](https://linux-hardware.org/?probe=ce3a9f8960) | Sep 28, 2023 |
| Acer          | Aspire 5736Z                | Notebook    | [cfd174dbe0](https://linux-hardware.org/?probe=cfd174dbe0) | Sep 28, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | Notebook    | [c717c1ab13](https://linux-hardware.org/?probe=c717c1ab13) | Sep 28, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [f6c6bfc3fe](https://linux-hardware.org/?probe=f6c6bfc3fe) | Sep 27, 2023 |
| Lenovo        | ThinkPad E14 20RA0050US     | Notebook    | [097539dde8](https://linux-hardware.org/?probe=097539dde8) | Sep 27, 2023 |
| Medion        | E6431 MD60112               | Notebook    | [f1fee9da62](https://linux-hardware.org/?probe=f1fee9da62) | Sep 27, 2023 |
| Intel         | X79G V2.x                   | Desktop     | [3d001a09ab](https://linux-hardware.org/?probe=3d001a09ab) | Sep 27, 2023 |
| HP            | Notebook                    | Notebook    | [4690fda15e](https://linux-hardware.org/?probe=4690fda15e) | Sep 27, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [7463d4f447](https://linux-hardware.org/?probe=7463d4f447) | Sep 26, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [f87aee7d8f](https://linux-hardware.org/?probe=f87aee7d8f) | Sep 26, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [811818acb8](https://linux-hardware.org/?probe=811818acb8) | Sep 26, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [7214093885](https://linux-hardware.org/?probe=7214093885) | Sep 26, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [e7e87a1269](https://linux-hardware.org/?probe=e7e87a1269) | Sep 26, 2023 |
| Dell          | Inspiron 5459               | Notebook    | [1095c770f0](https://linux-hardware.org/?probe=1095c770f0) | Sep 26, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | Notebook    | [0c8a57738d](https://linux-hardware.org/?probe=0c8a57738d) | Sep 25, 2023 |
| AZW           | SER                         | Mini pc     | [8e73904b3c](https://linux-hardware.org/?probe=8e73904b3c) | Sep 25, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | Notebook    | [a778013e21](https://linux-hardware.org/?probe=a778013e21) | Sep 25, 2023 |
| Intel         | W7645                       | Notebook    | [8a83c23785](https://linux-hardware.org/?probe=8a83c23785) | Sep 25, 2023 |
| Dell          | 0Y5DDC A00                  | Desktop     | [29feb62e32](https://linux-hardware.org/?probe=29feb62e32) | Sep 25, 2023 |
| Dell          | Inspiron 14 5410            | Notebook    | [863dfa9b96](https://linux-hardware.org/?probe=863dfa9b96) | Sep 25, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [1bee981c70](https://linux-hardware.org/?probe=1bee981c70) | Sep 25, 2023 |
| Dell          | Inspiron 3581               | Notebook    | [11796876dd](https://linux-hardware.org/?probe=11796876dd) | Sep 25, 2023 |
| Dell          | 0D28YY A01                  | Desktop     | [7c901ae7fd](https://linux-hardware.org/?probe=7c901ae7fd) | Sep 25, 2023 |
| Sony          | SVF14A15CXB                 | Notebook    | [cbce21a887](https://linux-hardware.org/?probe=cbce21a887) | Sep 25, 2023 |
| Alienware     | M17x                        | Notebook    | [5c6b700486](https://linux-hardware.org/?probe=5c6b700486) | Sep 25, 2023 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [6d75f2f29b](https://linux-hardware.org/?probe=6d75f2f29b) | Sep 24, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [f2a543d0dd](https://linux-hardware.org/?probe=f2a543d0dd) | Sep 24, 2023 |
| Sary          | Tab2                        | Tablet      | [7078e2b899](https://linux-hardware.org/?probe=7078e2b899) | Sep 23, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [fdfd7f2e50](https://linux-hardware.org/?probe=fdfd7f2e50) | Sep 23, 2023 |
| Sary          | Tab2                        | Tablet      | [913ec00764](https://linux-hardware.org/?probe=913ec00764) | Sep 23, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [6897fc6f5a](https://linux-hardware.org/?probe=6897fc6f5a) | Sep 23, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [02a39de387](https://linux-hardware.org/?probe=02a39de387) | Sep 23, 2023 |
| Dell          | 0HN7XN A01                  | Desktop     | [fd3ce44501](https://linux-hardware.org/?probe=fd3ce44501) | Sep 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [e2c17f3a64](https://linux-hardware.org/?probe=e2c17f3a64) | Sep 23, 2023 |
| Intel         | DB85FL AAG89861-201         | Desktop     | [58b289a69d](https://linux-hardware.org/?probe=58b289a69d) | Sep 23, 2023 |
| Lenovo        | ThinkPad E575 20H8000HUS    | Notebook    | [8b5a2354c5](https://linux-hardware.org/?probe=8b5a2354c5) | Sep 23, 2023 |
| Acer          | Aspire A514-54              | Notebook    | [c74511d498](https://linux-hardware.org/?probe=c74511d498) | Sep 22, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [e513362f71](https://linux-hardware.org/?probe=e513362f71) | Sep 22, 2023 |
| Toshiba       | Satellite Pro R40-D         | Notebook    | [d33d1b7b77](https://linux-hardware.org/?probe=d33d1b7b77) | Sep 22, 2023 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [81bf9d5194](https://linux-hardware.org/?probe=81bf9d5194) | Sep 22, 2023 |
| Primux Tec... | Primux_1406F_W10            | Notebook    | [a1911e4e9a](https://linux-hardware.org/?probe=a1911e4e9a) | Sep 22, 2023 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [7ecfb9c56f](https://linux-hardware.org/?probe=7ecfb9c56f) | Sep 22, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [47e5429752](https://linux-hardware.org/?probe=47e5429752) | Sep 22, 2023 |
| Primux Tec... | Primux_1406F_W10            | Notebook    | [c267e8d9a3](https://linux-hardware.org/?probe=c267e8d9a3) | Sep 22, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [a35f78cead](https://linux-hardware.org/?probe=a35f78cead) | Sep 21, 2023 |
| AZW           | MINI S 10                   | Desktop     | [e393d95960](https://linux-hardware.org/?probe=e393d95960) | Sep 21, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [cc25c24fa5](https://linux-hardware.org/?probe=cc25c24fa5) | Sep 21, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [d92a4fb2af](https://linux-hardware.org/?probe=d92a4fb2af) | Sep 21, 2023 |
| Dell          | Inspiron 3576               | Notebook    | [a76faead17](https://linux-hardware.org/?probe=a76faead17) | Sep 21, 2023 |
| Acer          | TravelMate P246-MG          | Notebook    | [197b2c18c7](https://linux-hardware.org/?probe=197b2c18c7) | Sep 21, 2023 |
| Acer          | Aspire VN7-572G             | Notebook    | [8936ef0637](https://linux-hardware.org/?probe=8936ef0637) | Sep 21, 2023 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [e57a830f9c](https://linux-hardware.org/?probe=e57a830f9c) | Sep 21, 2023 |
| Lenovo        | ThinkPad T570 20HAS1PC00    | Notebook    | [218325e9e3](https://linux-hardware.org/?probe=218325e9e3) | Sep 21, 2023 |
| Lenovo        | ThinkPad T560 20FJS2BX00    | Notebook    | [85a0203a02](https://linux-hardware.org/?probe=85a0203a02) | Sep 20, 2023 |
| Dell          | 0F3KHR A00                  | Desktop     | [dd7f2cf2b2](https://linux-hardware.org/?probe=dd7f2cf2b2) | Sep 20, 2023 |
| Lenovo        | ThinkPad T560 20FJS2BX00    | Notebook    | [c96d3bf498](https://linux-hardware.org/?probe=c96d3bf498) | Sep 20, 2023 |
| Lenovo        | H320 10044                  | Desktop     | [bf4ffce3e9](https://linux-hardware.org/?probe=bf4ffce3e9) | Sep 20, 2023 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | Desktop     | [776633dd59](https://linux-hardware.org/?probe=776633dd59) | Sep 20, 2023 |
| Dell          | 0F3KHR A00                  | Desktop     | [fcdaf47870](https://linux-hardware.org/?probe=fcdaf47870) | Sep 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [e4dc880c6f](https://linux-hardware.org/?probe=e4dc880c6f) | Sep 20, 2023 |
| Dell          | 0RW199                      | Desktop     | [2857c6ada1](https://linux-hardware.org/?probe=2857c6ada1) | Sep 20, 2023 |
| Gigabyte      | Z790 UD AC                  | Desktop     | [83af285806](https://linux-hardware.org/?probe=83af285806) | Sep 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [162a680d7d](https://linux-hardware.org/?probe=162a680d7d) | Sep 19, 2023 |
| Lenovo        | MIIX 2 11 20327             | Tablet      | [3d4f35cc26](https://linux-hardware.org/?probe=3d4f35cc26) | Sep 19, 2023 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [fcd8ef31df](https://linux-hardware.org/?probe=fcd8ef31df) | Sep 19, 2023 |
| Acer          | Aspire 5750                 | Notebook    | [9fb8b99e70](https://linux-hardware.org/?probe=9fb8b99e70) | Sep 19, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [ca70cb035f](https://linux-hardware.org/?probe=ca70cb035f) | Sep 19, 2023 |
| Biostar       | H61MLC                      | Desktop     | [154ead8447](https://linux-hardware.org/?probe=154ead8447) | Sep 19, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [f45c7732e3](https://linux-hardware.org/?probe=f45c7732e3) | Sep 19, 2023 |
| AZW           | GTR V21                     | Desktop     | [5066e153f8](https://linux-hardware.org/?probe=5066e153f8) | Sep 19, 2023 |
| HP            | Pavilion dv7                | Notebook    | [2bbc187582](https://linux-hardware.org/?probe=2bbc187582) | Sep 19, 2023 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [5ec304bdb6](https://linux-hardware.org/?probe=5ec304bdb6) | Sep 19, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [bb3c1bf2b9](https://linux-hardware.org/?probe=bb3c1bf2b9) | Sep 18, 2023 |
| HP            | EliteBook 745 G5            | Notebook    | [d03b8c1860](https://linux-hardware.org/?probe=d03b8c1860) | Sep 18, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [4e845095f4](https://linux-hardware.org/?probe=4e845095f4) | Sep 18, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [002401cab6](https://linux-hardware.org/?probe=002401cab6) | Sep 18, 2023 |
| ASUSTek       | M4N68T-M-LE-V2              | Desktop     | [202375fbb7](https://linux-hardware.org/?probe=202375fbb7) | Sep 18, 2023 |
| HP            | 3047h                       | Desktop     | [a955e9b6c6](https://linux-hardware.org/?probe=a955e9b6c6) | Sep 17, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [9e7069cdc3](https://linux-hardware.org/?probe=9e7069cdc3) | Sep 17, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Zorin_16/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.15.0-56-generic | 235       | 4.99%   |
| 5.11.0-38-generic | 181       | 3.84%   |
| 5.11.0-27-generic | 156       | 3.31%   |
| 5.15.0-46-generic | 152       | 3.23%   |
| 5.15.0-58-generic | 151       | 3.2%    |
| 5.15.0-52-generic | 151       | 3.2%    |
| 5.15.0-91-generic | 146       | 3.1%    |
| 5.15.0-67-generic | 144       | 3.06%   |
| 5.15.0-69-generic | 136       | 2.89%   |
| 5.15.0-78-generic | 134       | 2.84%   |
| 5.13.0-30-generic | 126       | 2.67%   |
| 5.11.0-40-generic | 123       | 2.61%   |
| 5.13.0-39-generic | 122       | 2.59%   |
| 5.15.0-60-generic | 112       | 2.38%   |
| 5.11.0-41-generic | 109       | 2.31%   |
| 5.15.0-71-generic | 108       | 2.29%   |
| 5.15.0-76-generic | 107       | 2.27%   |
| 5.11.0-37-generic | 106       | 2.25%   |
| 5.11.0-43-generic | 100       | 2.12%   |
| 5.15.0-48-generic | 95        | 2.02%   |
| 5.11.0-34-generic | 95        | 2.02%   |
| 5.15.0-88-generic | 94        | 1.99%   |
| 5.13.0-40-generic | 90        | 1.91%   |
| 5.15.0-84-generic | 81        | 1.72%   |
| 5.15.0-53-generic | 81        | 1.72%   |
| 5.15.0-41-generic | 77        | 1.63%   |
| 5.13.0-44-generic | 76        | 1.61%   |
| 5.13.0-35-generic | 74        | 1.57%   |
| 5.13.0-28-generic | 73        | 1.55%   |
| 5.15.0-89-generic | 71        | 1.51%   |
| 5.15.0-73-generic | 70        | 1.49%   |
| 5.15.0-86-generic | 69        | 1.46%   |
| 5.15.0-83-generic | 60        | 1.27%   |
| 5.15.0-72-generic | 60        | 1.27%   |
| 5.13.0-27-generic | 60        | 1.27%   |
| 5.13.0-52-generic | 59        | 1.25%   |
| 5.15.0-79-generic | 55        | 1.17%   |
| 5.13.0-41-generic | 54        | 1.15%   |
| 5.15.0-87-generic | 45        | 0.96%   |
| 5.13.0-51-generic | 42        | 0.89%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 2349      | 55.98%  |
| 5.11.0  | 947       | 22.57%  |
| 5.13.0  | 770       | 18.35%  |
| 5.8.0   | 54        | 1.29%   |
| 5.14.0  | 10        | 0.24%   |
| 6.3.13  | 6         | 0.14%   |
| 5.4.0   | 5         | 0.12%   |
| 6.5.7   | 4         | 0.1%    |
| 6.2.16  | 3         | 0.07%   |
| 6.3.2   | 2         | 0.05%   |
| 5.19.12 | 2         | 0.05%   |
| 5.19.0  | 2         | 0.05%   |
| 5.18.15 | 2         | 0.05%   |
| 5.17.5  | 2         | 0.05%   |
| 5.17.1  | 2         | 0.05%   |
| 5.16.0  | 2         | 0.05%   |
| 5.10.0  | 2         | 0.05%   |
| 6.6.7   | 1         | 0.02%   |
| 6.6.1   | 1         | 0.02%   |
| 6.3.1   | 1         | 0.02%   |
| 6.3.0   | 1         | 0.02%   |
| 6.2.7   | 1         | 0.02%   |
| 6.2.14  | 1         | 0.02%   |
| 6.1.8   | 1         | 0.02%   |
| 6.1.7   | 1         | 0.02%   |
| 6.1.22  | 1         | 0.02%   |
| 6.0.9   | 1         | 0.02%   |
| 6.0.8   | 1         | 0.02%   |
| 6.0.19  | 1         | 0.02%   |
| 6.0.0   | 1         | 0.02%   |
| 5.4.180 | 1         | 0.02%   |
| 5.19.9  | 1         | 0.02%   |
| 5.19.6  | 1         | 0.02%   |
| 5.19.2  | 1         | 0.02%   |
| 5.19.14 | 1         | 0.02%   |
| 5.19.1  | 1         | 0.02%   |
| 5.18.6  | 1         | 0.02%   |
| 5.18.19 | 1         | 0.02%   |
| 5.17.9  | 1         | 0.02%   |
| 5.16.5  | 1         | 0.02%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 2353      | 56.1%   |
| 5.11    | 947       | 22.58%  |
| 5.13    | 772       | 18.41%  |
| 5.8     | 54        | 1.29%   |
| 6.3     | 10        | 0.24%   |
| 5.14    | 10        | 0.24%   |
| 5.19    | 9         | 0.21%   |
| 5.4     | 6         | 0.14%   |
| 6.2     | 5         | 0.12%   |
| 5.17    | 5         | 0.12%   |
| 5.16    | 5         | 0.12%   |
| 6.5     | 4         | 0.1%    |
| 6.0     | 4         | 0.1%    |
| 5.18    | 4         | 0.1%    |
| 6.6     | 2         | 0.05%   |
| 6.1     | 2         | 0.05%   |
| 5.10    | 2         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 4033      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 3396      | 83.52%  |
| XFCE            | 615       | 15.13%  |
| Unknown         | 25        | 0.61%   |
| KDE5            | 9         | 0.22%   |
| X-Cinnamon      | 5         | 0.12%   |
| Budgie          | 4         | 0.1%    |
| Cinnamon        | 3         | 0.07%   |
| Unity           | 2         | 0.05%   |
| i3              | 2         | 0.05%   |
| MATE            | 1         | 0.02%   |
| LXQt            | 1         | 0.02%   |
| LXDE            | 1         | 0.02%   |
| KDE             | 1         | 0.02%   |
| GNOME Flashback | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 3969      | 97.73%  |
| Wayland | 77        | 1.9%    |
| Unknown | 12        | 0.3%    |
| Tty     | 3         | 0.07%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3129      | 76.37%  |
| GDM     | 439       | 10.72%  |
| GDM3    | 373       | 9.1%    |
| LightDM | 152       | 3.71%   |
| SDDM    | 2         | 0.05%   |
| TDM     | 1         | 0.02%   |
| LXDM    | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 1591      | 39.25%  |
| de_DE | 393       | 9.7%    |
| en_GB | 271       | 6.69%   |
| pt_BR | 221       | 5.45%   |
| fr_FR | 159       | 3.92%   |
| it_IT | 130       | 3.21%   |
| es_ES | 128       | 3.16%   |
| en_CA | 111       | 2.74%   |
| en_IN | 100       | 2.47%   |
| pl_PL | 97        | 2.39%   |
| en_AU | 76        | 1.88%   |
| nl_NL | 74        | 1.83%   |
| es_MX | 58        | 1.43%   |
| ru_RU | 48        | 1.18%   |
| en_ZA | 38        | 0.94%   |
| pt_PT | 33        | 0.81%   |
| cs_CZ | 32        | 0.79%   |
| es_AR | 31        | 0.76%   |
| hu_HU | 30        | 0.74%   |
| sv_SE | 25        | 0.62%   |
| tr_TR | 24        | 0.59%   |
| en_NZ | 23        | 0.57%   |
| nl_BE | 20        | 0.49%   |
| es_CL | 20        | 0.49%   |
| fr_BE | 19        | 0.47%   |
| de_CH | 19        | 0.47%   |
| de_AT | 17        | 0.42%   |
| fr_CA | 14        | 0.35%   |
| es_CO | 13        | 0.32%   |
| ja_JP | 12        | 0.3%    |
| fi_FI | 12        | 0.3%    |
| el_GR | 12        | 0.3%    |
| sk_SK | 11        | 0.27%   |
| da_DK | 11        | 0.27%   |
| nb_NO | 10        | 0.25%   |
| es_VE | 10        | 0.25%   |
| en_PH | 10        | 0.25%   |
| ar_EG | 10        | 0.25%   |
| es_CR | 8         | 0.2%    |
| en_IE | 8         | 0.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 2360      | 57.73%  |
| BIOS | 1728      | 42.27%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 3721      | 91.49%  |
| Tmpfs    | 137       | 3.37%   |
| Zfs      | 75        | 1.84%   |
| Overlay  | 66        | 1.62%   |
| Btrfs    | 41        | 1.01%   |
| Xfs      | 9         | 0.22%   |
| Ext2     | 9         | 0.22%   |
| Ext3     | 7         | 0.17%   |
| Reiserfs | 1         | 0.02%   |
| Jfs      | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3304      | 80.72%  |
| GPT     | 606       | 14.81%  |
| MBR     | 183       | 4.47%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3925      | 97.08%  |
| Yes       | 118       | 2.92%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3645      | 90.02%  |
| Yes       | 404       | 9.98%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 672       | 16.66%  |
| ASUSTek Computer    | 573       | 14.21%  |
| Dell                | 533       | 13.22%  |
| Lenovo              | 532       | 13.19%  |
| Gigabyte Technology | 225       | 5.58%   |
| Acer                | 213       | 5.28%   |
| MSI                 | 190       | 4.71%   |
| Apple               | 148       | 3.67%   |
| ASRock              | 97        | 2.41%   |
| Toshiba             | 95        | 2.36%   |
| Intel               | 70        | 1.74%   |
| Unknown             | 47        | 1.17%   |
| Samsung Electronics | 41        | 1.02%   |
| Sony                | 35        | 0.87%   |
| Google              | 35        | 0.87%   |
| Fujitsu             | 33        | 0.82%   |
| Microsoft           | 26        | 0.64%   |
| HUAWEI              | 25        | 0.62%   |
| Biostar             | 22        | 0.55%   |
| Positivo            | 21        | 0.52%   |
| Pegatron            | 21        | 0.52%   |
| Packard Bell        | 19        | 0.47%   |
| AZW                 | 18        | 0.45%   |
| Medion              | 17        | 0.42%   |
| Foxconn             | 16        | 0.4%    |
| Alienware           | 16        | 0.4%    |
| Chuwi               | 13        | 0.32%   |
| AMI                 | 11        | 0.27%   |
| Notebook            | 10        | 0.25%   |
| Fujitsu Siemens     | 8         | 0.2%    |
| Multilaser          | 7         | 0.17%   |
| GPU Company         | 7         | 0.17%   |
| Gateway             | 6         | 0.15%   |
| BESSTAR Tech        | 6         | 0.15%   |
| Thomson             | 5         | 0.12%   |
| LG Electronics      | 5         | 0.12%   |
| ECS                 | 5         | 0.12%   |
| TrekStor            | 4         | 0.1%    |
| Semp Toshiba        | 4         | 0.1%    |
| RCA                 | 4         | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Unknown                      | 60        | 1.49%   |
| ASUS All Series              | 33        | 0.82%   |
| HP Notebook                  | 26        | 0.64%   |
| HP Pavilion Notebook         | 15        | 0.37%   |
| HP 15                        | 14        | 0.35%   |
| Dell OptiPlex 7010           | 13        | 0.32%   |
| MSI MS-7817                  | 10        | 0.25%   |
| HP Pavilion dv7              | 9         | 0.22%   |
| HP Pavilion dv6              | 9         | 0.22%   |
| HP Pavilion 15               | 9         | 0.22%   |
| Dell OptiPlex 790            | 9         | 0.22%   |
| ASUS TUF Gaming X570-PLUS    | 9         | 0.22%   |
| Intel H61                    | 8         | 0.2%    |
| Apple MacBookPro8,1          | 8         | 0.2%    |
| Apple iMac12,2               | 8         | 0.2%    |
| Apple iMac12,1               | 8         | 0.2%    |
| Microsoft Surface Pro        | 7         | 0.17%   |
| Lenovo MIIX 320-10ICR 80XF   | 7         | 0.17%   |
| Dell OptiPlex 780            | 7         | 0.17%   |
| Dell OptiPlex 380            | 7         | 0.17%   |
| ASUS M5A78L-M/USB3           | 7         | 0.17%   |
| Apple MacBookPro12,1         | 7         | 0.17%   |
| Apple iMac10,1               | 7         | 0.17%   |
| MSI MS-7C37                  | 6         | 0.15%   |
| MSI MS-7C02                  | 6         | 0.15%   |
| Microsoft Surface Pro 4      | 6         | 0.15%   |
| HP Pavilion g7               | 6         | 0.15%   |
| Gigabyte B450 AORUS M        | 6         | 0.15%   |
| Gigabyte A320M-S2H           | 6         | 0.15%   |
| Dell OptiPlex 3010           | 6         | 0.15%   |
| Dell Latitude E6540          | 6         | 0.15%   |
| Dell Latitude E6520          | 6         | 0.15%   |
| Dell Latitude E6430          | 6         | 0.15%   |
| Dell Inspiron 15-3567        | 6         | 0.15%   |
| ASUS M5A97 R2.0              | 6         | 0.15%   |
| Lenovo IdeaPad 3 15ALC6 82KU | 5         | 0.12%   |
| HP ProBook 640 G1            | 5         | 0.12%   |
| HP Pavilion g6               | 5         | 0.12%   |
| HP EliteDesk 800 G1 SFF      | 5         | 0.12%   |
| HP EliteBook 8460p           | 5         | 0.12%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 175       | 4.34%   |
| Acer Aspire           | 145       | 3.6%    |
| Dell Latitude         | 139       | 3.45%   |
| Dell Inspiron         | 139       | 3.45%   |
| HP Pavilion           | 135       | 3.35%   |
| Lenovo IdeaPad        | 126       | 3.12%   |
| Dell OptiPlex         | 104       | 2.58%   |
| Toshiba Satellite     | 78        | 1.93%   |
| HP EliteBook          | 71        | 1.76%   |
| HP Compaq             | 62        | 1.54%   |
| Unknown               | 60        | 1.49%   |
| HP ProBook            | 58        | 1.44%   |
| ASUS ROG              | 58        | 1.44%   |
| ASUS PRIME            | 52        | 1.29%   |
| Lenovo ThinkCentre    | 51        | 1.26%   |
| HP Laptop             | 50        | 1.24%   |
| ASUS TUF              | 44        | 1.09%   |
| Dell Precision        | 39        | 0.97%   |
| ASUS VivoBook         | 38        | 0.94%   |
| Dell XPS              | 35        | 0.87%   |
| Lenovo Yoga           | 33        | 0.82%   |
| ASUS All              | 33        | 0.82%   |
| Dell Vostro           | 32        | 0.79%   |
| HP ENVY               | 31        | 0.77%   |
| Microsoft Surface     | 26        | 0.64%   |
| HP Notebook           | 26        | 0.64%   |
| HP EliteDesk          | 23        | 0.57%   |
| HP Stream             | 19        | 0.47%   |
| HP 15                 | 16        | 0.4%    |
| ASUS ZenBook          | 16        | 0.4%    |
| ASUS ASUS             | 16        | 0.4%    |
| Apple iMac12          | 16        | 0.4%    |
| Packard Bell EasyNote | 15        | 0.37%   |
| Lenovo Legion         | 14        | 0.35%   |
| HP OMEN               | 14        | 0.35%   |
| HP ProDesk            | 13        | 0.32%   |
| Gigabyte B450         | 13        | 0.32%   |
| Fujitsu ESPRIMO       | 13        | 0.32%   |
| Dell Studio           | 12        | 0.3%    |
| Lenovo MIIX           | 11        | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 337       | 8.36%   |
| 2021    | 332       | 8.23%   |
| 2013    | 332       | 8.23%   |
| 2011    | 328       | 8.13%   |
| 2018    | 306       | 7.59%   |
| 2020    | 297       | 7.36%   |
| 2019    | 276       | 6.84%   |
| 2014    | 268       | 6.65%   |
| 2017    | 263       | 6.52%   |
| 2010    | 225       | 5.58%   |
| 2016    | 212       | 5.26%   |
| 2015    | 204       | 5.06%   |
| 2008    | 176       | 4.36%   |
| 2009    | 155       | 3.84%   |
| 2022    | 124       | 3.07%   |
| 2007    | 102       | 2.53%   |
| 2023    | 59        | 1.46%   |
| 2006    | 27        | 0.67%   |
| 2005    | 6         | 0.15%   |
| Unknown | 3         | 0.07%   |
| 2024    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 2225      | 55.17%  |
| Desktop     | 1460      | 36.2%   |
| Convertible | 104       | 2.58%   |
| All in one  | 96        | 2.38%   |
| Tablet      | 71        | 1.76%   |
| Mini pc     | 67        | 1.66%   |
| Server      | 10        | 0.25%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 3570      | 87.71%  |
| Enabled  | 500       | 12.29%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3994      | 99.03%  |
| Yes  | 39        | 0.97%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 1125      | 27.6%   |
| 3.01-4.0        | 875       | 21.47%  |
| 16.01-24.0      | 698       | 17.12%  |
| 8.01-16.0       | 667       | 16.36%  |
| 32.01-64.0      | 313       | 7.68%   |
| 1.01-2.0        | 190       | 4.66%   |
| 64.01-256.0     | 82        | 2.01%   |
| 2.01-3.0        | 59        | 1.45%   |
| 24.01-32.0      | 57        | 1.4%    |
| 0.51-1.0        | 9         | 0.22%   |
| More than 256.0 | 1         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1629      | 36.73%  |
| 2.01-3.0   | 1454      | 32.78%  |
| 3.01-4.0   | 620       | 13.98%  |
| 4.01-8.0   | 532       | 12%     |
| 0.51-1.0   | 94        | 2.12%   |
| 8.01-16.0  | 84        | 1.89%   |
| 16.01-24.0 | 13        | 0.29%   |
| 24.01-32.0 | 6         | 0.14%   |
| 32.01-64.0 | 2         | 0.05%   |
| 0.01-0.5   | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 2638      | 63.95%  |
| 2      | 989       | 23.98%  |
| 3      | 242       | 5.87%   |
| 4      | 123       | 2.98%   |
| 5      | 59        | 1.43%   |
| 6      | 34        | 0.82%   |
| 0      | 15        | 0.36%   |
| 7      | 12        | 0.29%   |
| 8      | 9         | 0.22%   |
| 51     | 1         | 0.02%   |
| 30     | 1         | 0.02%   |
| 11     | 1         | 0.02%   |
| 9      | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2335      | 57.57%  |
| Yes       | 1721      | 42.43%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3375      | 83.5%   |
| No        | 667       | 16.5%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3226      | 79.63%  |
| No        | 825       | 20.37%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2414      | 59.25%  |
| No        | 1660      | 40.75%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 937       | 23.14%  |
| Germany      | 427       | 10.54%  |
| Brazil       | 249       | 6.15%   |
| UK           | 248       | 6.12%   |
| France       | 145       | 3.58%   |
| Italy        | 143       | 3.53%   |
| Canada       | 141       | 3.48%   |
| Spain        | 136       | 3.36%   |
| Netherlands  | 119       | 2.94%   |
| India        | 104       | 2.57%   |
| Poland       | 94        | 2.32%   |
| Mexico       | 78        | 1.93%   |
| Australia    | 78        | 1.93%   |
| Belgium      | 60        | 1.48%   |
| Russia       | 48        | 1.19%   |
| Sweden       | 46        | 1.14%   |
| Portugal     | 43        | 1.06%   |
| Austria      | 43        | 1.06%   |
| South Africa | 42        | 1.04%   |
| Switzerland  | 41        | 1.01%   |
| Argentina    | 40        | 0.99%   |
| Turkey       | 38        | 0.94%   |
| Czechia      | 36        | 0.89%   |
| Hungary      | 34        | 0.84%   |
| Romania      | 32        | 0.79%   |
| Norway       | 31        | 0.77%   |
| Greece       | 31        | 0.77%   |
| New Zealand  | 25        | 0.62%   |
| Egypt        | 24        | 0.59%   |
| Denmark      | 24        | 0.59%   |
| Chile        | 24        | 0.59%   |
| Japan        | 23        | 0.57%   |
| Finland      | 22        | 0.54%   |
| Colombia     | 21        | 0.52%   |
| Indonesia    | 19        | 0.47%   |
| Serbia       | 18        | 0.44%   |
| Bulgaria     | 16        | 0.4%    |
| Slovakia     | 15        | 0.37%   |
| Malaysia     | 14        | 0.35%   |
| Ireland      | 14        | 0.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Berlin            | 38        | 0.89%   |
| Munich            | 26        | 0.61%   |
| Madrid            | 24        | 0.56%   |
| Vienna            | 23        | 0.54%   |
| Sydney            | 22        | 0.52%   |
| Rome              | 21        | 0.49%   |
| Rio de Janeiro    | 21        | 0.49%   |
| Athens            | 21        | 0.49%   |
| New York          | 20        | 0.47%   |
| Hamburg           | 20        | 0.47%   |
| Sao Paulo         | 18        | 0.42%   |
| Milan             | 18        | 0.42%   |
| Montreal          | 17        | 0.4%    |
| Amsterdam         | 17        | 0.4%    |
| Paris             | 16        | 0.38%   |
| Denver            | 15        | 0.35%   |
| Dallas            | 15        | 0.35%   |
| Melbourne         | 14        | 0.33%   |
| London            | 14        | 0.33%   |
| Cape Town         | 13        | 0.31%   |
| Phoenix           | 12        | 0.28%   |
| Mexico City       | 12        | 0.28%   |
| Johannesburg      | 12        | 0.28%   |
| Houston           | 12        | 0.28%   |
| Delhi             | 12        | 0.28%   |
| Bucharest         | 12        | 0.28%   |
| Toronto           | 11        | 0.26%   |
| Stockholm         | 11        | 0.26%   |
| Salt Lake City    | 11        | 0.26%   |
| Istanbul          | 11        | 0.26%   |
| Frankfurt am Main | 11        | 0.26%   |
| Calgary           | 11        | 0.26%   |
| Bogotá           | 11        | 0.26%   |
| Bengaluru         | 11        | 0.26%   |
| Auckland          | 11        | 0.26%   |
| Valencia          | 10        | 0.24%   |
| Seattle           | 10        | 0.24%   |
| San Jose          | 10        | 0.24%   |
| Perth             | 10        | 0.24%   |
| Moscow            | 10        | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 822       | 1192   | 14.39%  |
| Samsung Electronics         | 755       | 1102   | 13.22%  |
| WDC                         | 738       | 1030   | 12.92%  |
| Toshiba                     | 399       | 509    | 6.99%   |
| Sandisk                     | 348       | 442    | 6.09%   |
| Unknown                     | 343       | 483    | 6%      |
| Kingston                    | 306       | 433    | 5.36%   |
| Crucial                     | 203       | 247    | 3.55%   |
| Hitachi                     | 172       | 225    | 3.01%   |
| SK hynix                    | 121       | 141    | 2.12%   |
| Intel                       | 116       | 148    | 2.03%   |
| HGST                        | 99        | 122    | 1.73%   |
| China                       | 84        | 104    | 1.47%   |
| Micron Technology           | 82        | 101    | 1.44%   |
| A-DATA Technology           | 73        | 96     | 1.28%   |
| Apple                       | 66        | 76     | 1.16%   |
| Intenso                     | 50        | 55     | 0.88%   |
| Silicon Motion              | 41        | 54     | 0.72%   |
| KIOXIA                      | 40        | 46     | 0.7%    |
| Unknown                     | 38        | 42     | 0.67%   |
| PNY                         | 37        | 50     | 0.65%   |
| Phison                      | 36        | 43     | 0.63%   |
| SPCC                        | 32        | 46     | 0.56%   |
| Netac                       | 30        | 35     | 0.53%   |
| Patriot                     | 29        | 38     | 0.51%   |
| Micron/Crucial Technology   | 27        | 34     | 0.47%   |
| GOODRAM                     | 25        | 30     | 0.44%   |
| JMicron Technology          | 24        | 29     | 0.42%   |
| Phison Electronics          | 22        | 25     | 0.39%   |
| OCZ                         | 19        | 22     | 0.33%   |
| LITEON                      | 18        | 20     | 0.32%   |
| Lexar                       | 18        | 19     | 0.32%   |
| Team                        | 17        | 20     | 0.3%    |
| LITEONIT                    | 17        | 21     | 0.3%    |
| Kingston Technology Company | 16        | 20     | 0.28%   |
| KingSpec                    | 16        | 19     | 0.28%   |
| Transcend                   | 15        | 34     | 0.26%   |
| MAXIO Technology (Hangzhou) | 15        | 15     | 0.26%   |
| Hewlett-Packard             | 15        | 21     | 0.26%   |
| Fujitsu                     | 15        | 17     | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Unknown MMC Card  64GB                             | 101       | 1.61%   |
| Unknown MMC Card  32GB                             | 101       | 1.61%   |
| Kingston SA400S37240G 240GB SSD                    | 76        | 1.21%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 53        | 0.85%   |
| Seagate ST1000LM035-1RK172 1TB                     | 50        | 0.8%    |
| Seagate ST500DM002-1BD142 500GB                    | 49        | 0.78%   |
| Toshiba MQ01ABD100 1TB                             | 45        | 0.72%   |
| Unknown MMC Card  128GB                            | 42        | 0.67%   |
| Kingston SA400S37480G 480GB SSD                    | 42        | 0.67%   |
| Crucial CT240BX500SSD1 240GB                       | 42        | 0.67%   |
| Samsung SSD 860 EVO 500GB                          | 40        | 0.64%   |
| Kingston SA400S37120G 120GB SSD                    | 39        | 0.62%   |
| Unknown                                            | 38        | 0.61%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 37        | 0.59%   |
| Toshiba MQ01ABF050 500GB                           | 32        | 0.51%   |
| Seagate ST500LT012-1DG142 500GB                    | 32        | 0.51%   |
| Seagate ST1000DM010-2EP102 1TB                     | 32        | 0.51%   |
| Unknown SD/MMC/MS PRO 128GB                        | 31        | 0.5%    |
| Samsung SSD 850 EVO 250GB                          | 31        | 0.5%    |
| Toshiba MQ04ABF100 1TB                             | 29        | 0.46%   |
| Crucial CT500MX500SSD1 500GB                       | 27        | 0.43%   |
| Samsung SSD 850 EVO 500GB                          | 26        | 0.42%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB             | 26        | 0.42%   |
| Samsung NVMe SSD Drive 512GB                       | 25        | 0.4%    |
| Samsung NVMe SSD Drive 1TB                         | 25        | 0.4%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1TB  | 25        | 0.4%    |
| Seagate ST9500325AS 500GB                          | 24        | 0.38%   |
| Seagate ST1000DM003-1CH162 1TB                     | 24        | 0.38%   |
| WDC WD10EZEX-08WN4A0 1TB                           | 23        | 0.37%   |
| Seagate Expansion 2TB                              | 21        | 0.34%   |
| SanDisk NVMe SSD Drive 256GB                       | 21        | 0.34%   |
| Samsung SSD 870 EVO 1TB                            | 21        | 0.34%   |
| Samsung NVMe SSD Drive 500GB                       | 21        | 0.34%   |
| Crucial CT1000MX500SSD1 1TB                        | 21        | 0.34%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 20        | 0.32%   |
| Kingston SV300S37A120G 120GB SSD                   | 20        | 0.32%   |
| HGST HTS721010A9E630 1TB                           | 20        | 0.32%   |
| Unknown MMC Card  16GB                             | 19        | 0.3%    |
| Toshiba HDWD110 1TB                                | 19        | 0.3%    |
| Crucial CT480BX500SSD1 480GB                       | 19        | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 809       | 1161   | 35.91%  |
| WDC                 | 631       | 871    | 28.01%  |
| Toshiba             | 313       | 406    | 13.89%  |
| Hitachi             | 172       | 225    | 7.63%   |
| HGST                | 99        | 122    | 4.39%   |
| Samsung Electronics | 92        | 113    | 4.08%   |
| Unknown             | 32        | 40     | 1.42%   |
| Apple               | 29        | 33     | 1.29%   |
| JMicron Technology  | 16        | 18     | 0.71%   |
| Fujitsu             | 15        | 17     | 0.67%   |
| Maxtor              | 14        | 18     | 0.62%   |
| SABRENT             | 10        | 12     | 0.44%   |
| Hewlett-Packard     | 4         | 7      | 0.18%   |
| Intenso             | 3         | 3      | 0.13%   |
| USB3.0              | 2         | 3      | 0.09%   |
| XrayDisk            | 1         | 1      | 0.04%   |
| WD MediaMax         | 1         | 1      | 0.04%   |
| Unknown (CF)        | 1         | 1      | 0.04%   |
| TO Exter            | 1         | 1      | 0.04%   |
| TDAS                | 1         | 3      | 0.04%   |
| QUANTUM             | 1         | 1      | 0.04%   |
| LaCie               | 1         | 1      | 0.04%   |
| KESU                | 1         | 1      | 0.04%   |
| IBM/Hitachi         | 1         | 1      | 0.04%   |
| HGST HTS            | 1         | 1      | 0.04%   |
| ASMT                | 1         | 2      | 0.04%   |
| ACASIS              | 1         | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 380       | 542    | 19.44%  |
| Kingston            | 256       | 347    | 13.09%  |
| Crucial             | 193       | 235    | 9.87%   |
| SanDisk             | 184       | 234    | 9.41%   |
| WDC                 | 88        | 114    | 4.5%    |
| China               | 83        | 103    | 4.25%   |
| A-DATA Technology   | 64        | 87     | 3.27%   |
| Intel               | 44        | 51     | 2.25%   |
| Toshiba             | 40        | 47     | 2.05%   |
| PNY                 | 37        | 50     | 1.89%   |
| Micron Technology   | 34        | 41     | 1.74%   |
| Intenso             | 34        | 37     | 1.74%   |
| SK hynix            | 33        | 33     | 1.69%   |
| SPCC                | 31        | 45     | 1.59%   |
| Apple               | 31        | 35     | 1.59%   |
| Netac               | 30        | 34     | 1.53%   |
| Patriot             | 28        | 37     | 1.43%   |
| GOODRAM             | 23        | 28     | 1.18%   |
| OCZ                 | 18        | 21     | 0.92%   |
| LITEON              | 18        | 20     | 0.92%   |
| Team                | 17        | 20     | 0.87%   |
| LITEONIT            | 17        | 21     | 0.87%   |
| Lexar               | 16        | 17     | 0.82%   |
| Transcend           | 15        | 34     | 0.77%   |
| KingSpec            | 15        | 18     | 0.77%   |
| Unknown             | 13        | 17     | 0.66%   |
| Apacer              | 12        | 15     | 0.61%   |
| Hewlett-Packard     | 10        | 13     | 0.51%   |
| Gigabyte Technology | 9         | 10     | 0.46%   |
| Fanxiang            | 7         | 8      | 0.36%   |
| Leven               | 6         | 7      | 0.31%   |
| ASMT                | 6         | 6      | 0.31%   |
| Verbatim            | 5         | 5      | 0.26%   |
| Teclast             | 5         | 5      | 0.26%   |
| Plextor             | 5         | 6      | 0.26%   |
| Phison              | 5         | 8      | 0.26%   |
| Mushkin             | 5         | 5      | 0.26%   |
| KIOXIA-EXCERIA      | 5         | 9      | 0.26%   |
| FORESEE             | 5         | 6      | 0.26%   |
| Super Talent        | 4         | 5      | 0.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1930      | 3064   | 37.28%  |
| SSD     | 1757      | 2541   | 33.94%  |
| NVMe    | 1045      | 1455   | 20.19%  |
| MMC     | 321       | 437    | 6.2%    |
| Unknown | 124       | 159    | 2.4%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3127      | 5421   | 66.22%  |
| NVMe | 1043      | 1449   | 22.09%  |
| MMC  | 321       | 437    | 6.8%    |
| SAS  | 231       | 349    | 4.89%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2320      | 3435   | 60.94%  |
| 0.51-1.0   | 1045      | 1470   | 27.45%  |
| 1.01-2.0   | 278       | 395    | 7.3%    |
| 3.01-4.0   | 76        | 151    | 2%      |
| 4.01-10.0  | 40        | 59     | 1.05%   |
| 2.01-3.0   | 39        | 66     | 1.02%   |
| 10.01-20.0 | 8         | 27     | 0.21%   |
| 20.01-50.0 | 1         | 2      | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1366      | 32.63%  |
| 251-500        | 1015      | 24.25%  |
| 501-1000       | 641       | 15.31%  |
| 51-100         | 345       | 8.24%   |
| 1001-2000      | 246       | 5.88%   |
| 21-50          | 199       | 4.75%   |
| More than 3000 | 148       | 3.54%   |
| 1-20           | 98        | 2.34%   |
| 2001-3000      | 76        | 1.82%   |
| Unknown        | 52        | 1.24%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1592      | 36.2%   |
| 21-50          | 1259      | 28.63%  |
| 51-100         | 544       | 12.37%  |
| 101-250        | 432       | 9.82%   |
| 251-500        | 237       | 5.39%   |
| 501-1000       | 138       | 3.14%   |
| More than 3000 | 65        | 1.48%   |
| 1001-2000      | 55        | 1.25%   |
| Unknown        | 52        | 1.18%   |
| 2001-3000      | 24        | 0.55%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                   | 4         | 4      | 3.45%   |
| HGST HTS545050A7E680 500GB               | 3         | 3      | 2.59%   |
| HGST HTS541010A9E680 1TB                 | 3         | 3      | 2.59%   |
| WDC WD30EFRX-68EUZN0 3TB                 | 2         | 2      | 1.72%   |
| Toshiba MQ02ABD100H 1TB                  | 2         | 2      | 1.72%   |
| SK hynix BC711 HFM512GD3JX013N 512GB     | 2         | 2      | 1.72%   |
| Seagate ST9500420AS 500GB                | 2         | 2      | 1.72%   |
| Seagate ST9500325AS 500GB                | 2         | 2      | 1.72%   |
| Seagate ST500LT012-1DG142 500GB          | 2         | 2      | 1.72%   |
| Seagate ST500DM002-1BD142 500GB          | 2         | 2      | 1.72%   |
| Seagate ST1000LM048-2E7172 1TB           | 2         | 2      | 1.72%   |
| Seagate ST1000LM035-1RK172 1TB           | 2         | 2      | 1.72%   |
| Kingston SUV400S37240G 240GB SSD         | 2         | 2      | 1.72%   |
| HGST HTS545050A7E380 500GB               | 2         | 3      | 1.72%   |
| WDC WDS500G2B0A-00SM50 500GB SSD         | 1         | 1      | 0.86%   |
| WDC WD6400BEVT-22A0RT0 640GB             | 1         | 1      | 0.86%   |
| WDC WD5000LPVX-75V0TT0 500GB             | 1         | 1      | 0.86%   |
| WDC WD5000LPCX-60VHAT0 500GB             | 1         | 1      | 0.86%   |
| WDC WD5000BEVT-24A0RT0 500GB             | 1         | 1      | 0.86%   |
| WDC WD3200AAKS-22B3A0 320GB              | 1         | 1      | 0.86%   |
| WDC WD3200AAJS-00L7A0 320GB              | 1         | 1      | 0.86%   |
| WDC WD2500AAJS-00B4A0 250GB              | 1         | 1      | 0.86%   |
| WDC WD20EZRX-22D8PB0 2TB                 | 1         | 1      | 0.86%   |
| WDC WD20EZRX-00D8PB0 2TB                 | 1         | 1      | 0.86%   |
| WDC WD1200BEVS-60UST0 120GB              | 1         | 1      | 0.86%   |
| WDC WD10SPZX-75Z10T2 1TB                 | 1         | 1      | 0.86%   |
| WDC WD10JPVX-22JC3T0 1TB                 | 1         | 1      | 0.86%   |
| WDC WD10JPVT-55A1YT0 1TB                 | 1         | 1      | 0.86%   |
| WDC WD10EZEX-21M2NA0 1TB                 | 1         | 2      | 0.86%   |
| WDC WD10EURX-63FH1Y0 1TB                 | 1         | 1      | 0.86%   |
| WDC WD Green 2.5 1000GB                  | 1         | 1      | 0.86%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD | 1         | 1      | 0.86%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD     | 1         | 1      | 0.86%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD | 1         | 1      | 0.86%   |
| Toshiba MQ01ABF050 500GB                 | 1         | 1      | 0.86%   |
| Toshiba MQ01ABD075 752GB                 | 1         | 1      | 0.86%   |
| Toshiba MK8046GSX 80GB                   | 1         | 1      | 0.86%   |
| Toshiba MK3265GSX 320GB                  | 1         | 1      | 0.86%   |
| Toshiba MG03ACA200 2TB                   | 1         | 1      | 0.86%   |
| Toshiba DT01ACA100 1TB                   | 1         | 1      | 0.86%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 38        | 39     | 33.04%  |
| WDC                 | 19        | 20     | 16.52%  |
| Toshiba             | 15        | 15     | 13.04%  |
| HGST                | 11        | 12     | 9.57%   |
| Samsung Electronics | 6         | 6      | 5.22%   |
| Kingston            | 6         | 6      | 5.22%   |
| Hitachi             | 3         | 3      | 2.61%   |
| SK hynix            | 2         | 2      | 1.74%   |
| Intel               | 2         | 2      | 1.74%   |
| A-DATA Technology   | 2         | 2      | 1.74%   |
| Teclast             | 1         | 1      | 0.87%   |
| Silicon Motion      | 1         | 1      | 0.87%   |
| POLION              | 1         | 1      | 0.87%   |
| OCZ                 | 1         | 1      | 0.87%   |
| Netac               | 1         | 1      | 0.87%   |
| Maxtor              | 1         | 1      | 0.87%   |
| LITEONIT            | 1         | 1      | 0.87%   |
| Hewlett-Packard     | 1         | 1      | 0.87%   |
| Drevo               | 1         | 1      | 0.87%   |
| China               | 1         | 1      | 0.87%   |
| Unknown             | 1         | 1      | 0.87%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 38        | 39     | 44.19%  |
| WDC                 | 17        | 18     | 19.77%  |
| Toshiba             | 12        | 12     | 13.95%  |
| HGST                | 11        | 12     | 12.79%  |
| Samsung Electronics | 4         | 4      | 4.65%   |
| Hitachi             | 3         | 3      | 3.49%   |
| Maxtor              | 1         | 1      | 1.16%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 82        | 89     | 73.87%  |
| SSD  | 25        | 25     | 22.52%  |
| NVMe | 4         | 4      | 3.6%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                          | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate ST2000LX001-1RG174 2TB | 1         | 1      | 50%     |
| SanDisk SSD i100 24GB          | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| SanDisk | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 3580      | 6776   | 85.85%  |
| Works    | 478       | 759    | 11.46%  |
| Malfunc  | 109       | 118    | 2.61%   |
| Failed   | 2         | 2      | 0.05%   |
| Fixed    | 1         | 1      | 0.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2744      | 56.88%  |
| AMD                              | 743       | 15.4%   |
| Samsung Electronics              | 356       | 7.38%   |
| SanDisk                          | 184       | 3.81%   |
| SK hynix                         | 83        | 1.72%   |
| Nvidia                           | 75        | 1.55%   |
| Kingston Technology Company      | 73        | 1.51%   |
| ASMedia Technology               | 64        | 1.33%   |
| Phison Electronics               | 59        | 1.22%   |
| Micron Technology                | 49        | 1.02%   |
| Toshiba America Info Systems     | 46        | 0.95%   |
| Silicon Motion                   | 46        | 0.95%   |
| KIOXIA                           | 42        | 0.87%   |
| JMicron Technology               | 41        | 0.85%   |
| Micron/Crucial Technology        | 37        | 0.77%   |
| Marvell Technology Group         | 37        | 0.77%   |
| ADATA Technology                 | 22        | 0.46%   |
| MAXIO Technology (Hangzhou)      | 17        | 0.35%   |
| Realtek Semiconductor            | 15        | 0.31%   |
| VIA Technologies                 | 11        | 0.23%   |
| Seagate Technology               | 10        | 0.21%   |
| Silicon Image                    | 9         | 0.19%   |
| Union Memory (Shenzhen)          | 7         | 0.15%   |
| Solid State Storage Technology   | 6         | 0.12%   |
| Shenzhen Longsys Electronics     | 6         | 0.12%   |
| Lite-On Technology               | 6         | 0.12%   |
| Apple                            | 5         | 0.1%    |
| LSI Logic / Symbios Logic        | 4         | 0.08%   |
| INNOGRIT                         | 4         | 0.08%   |
| Broadcom / LSI                   | 4         | 0.08%   |
| Silicon Integrated Systems [SiS] | 3         | 0.06%   |
| Yangtze Memory Technologies      | 2         | 0.04%   |
| OCZ Technology Group             | 2         | 0.04%   |
| Netac Technology                 | 2         | 0.04%   |
| Lenovo                           | 2         | 0.04%   |
| TenaFe                           | 1         | 0.02%   |
| Nextorage                        | 1         | 0.02%   |
| Integrated Technology Express    | 1         | 0.02%   |
| HighPoint Technologies           | 1         | 0.02%   |
| Dell                             | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 489       | 8.78%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 204       | 3.66%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 204       | 3.66%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 197       | 3.54%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 147       | 2.64%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 138       | 2.48%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 136       | 2.44%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 113       | 2.03%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 105       | 1.89%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 93        | 1.67%   |
| Intel Volume Management Device NVMe RAID Controller                            | 92        | 1.65%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 88        | 1.58%   |
| AMD 400 Series Chipset SATA Controller                                         | 88        | 1.58%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 86        | 1.54%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 85        | 1.53%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 83        | 1.49%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 79        | 1.42%   |
| Intel SATA Controller [RAID mode]                                              | 77        | 1.38%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 76        | 1.36%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 74        | 1.33%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 73        | 1.31%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 73        | 1.31%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 72        | 1.29%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 65        | 1.17%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 61        | 1.1%    |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 58        | 1.04%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 57        | 1.02%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 55        | 0.99%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 54        | 0.97%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 52        | 0.93%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 49        | 0.88%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 48        | 0.86%   |
| AMD 500 Series Chipset SATA Controller                                         | 47        | 0.84%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 45        | 0.81%   |
| Intel Tiger Lake-LP SATA Controller                                            | 44        | 0.79%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 42        | 0.75%   |
| Intel Comet Lake SATA AHCI Controller                                          | 40        | 0.72%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 36        | 0.65%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 36        | 0.65%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 36        | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2987      | 60.2%   |
| NVMe | 1043      | 21.02%  |
| IDE  | 560       | 11.29%  |
| RAID | 361       | 7.28%   |
| SAS  | 8         | 0.16%   |
| SCSI | 3         | 0.06%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 3160      | 78.35%  |
| AMD    | 873       | 21.65%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 54        | 1.34%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 44        | 1.09%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 40        | 0.99%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 35        | 0.87%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 34        | 0.84%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 30        | 0.74%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 29        | 0.72%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 28        | 0.69%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 28        | 0.69%   |
| AMD Ryzen 5 3600 6-Core Processor             | 28        | 0.69%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 27        | 0.67%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 26        | 0.64%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 24        | 0.59%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 24        | 0.59%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 23        | 0.57%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 23        | 0.57%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 23        | 0.57%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 22        | 0.54%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 22        | 0.54%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 21        | 0.52%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 21        | 0.52%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 20        | 0.5%    |
| Intel Core i5-3230M CPU @ 2.60GHz             | 20        | 0.5%    |
| Intel Core i5-4200U CPU @ 1.60GHz             | 18        | 0.45%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 18        | 0.45%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 18        | 0.45%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 17        | 0.42%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 17        | 0.42%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 17        | 0.42%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 17        | 0.42%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 16        | 0.4%    |
| Intel Core i7-3770 CPU @ 3.40GHz              | 16        | 0.4%    |
| Intel Core i5-4460 CPU @ 3.20GHz              | 16        | 0.4%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 16        | 0.4%    |
| Intel Core i3-3110M CPU @ 2.40GHz             | 16        | 0.4%    |
| Intel Core i3-2120 CPU @ 3.30GHz              | 16        | 0.4%    |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 16        | 0.4%    |
| AMD Ryzen 9 5900X 12-Core Processor           | 16        | 0.4%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 15        | 0.37%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 15        | 0.37%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 928       | 22.99%  |
| Intel Core i7           | 578       | 14.32%  |
| Intel Core i3           | 373       | 9.24%   |
| Intel Celeron           | 278       | 6.89%   |
| Other                   | 247       | 6.12%   |
| AMD Ryzen 5             | 207       | 5.13%   |
| Intel Core 2 Duo        | 202       | 5%      |
| Intel Atom              | 128       | 3.17%   |
| AMD Ryzen 7             | 125       | 3.1%    |
| Intel Pentium           | 116       | 2.87%   |
| Intel Xeon              | 87        | 2.16%   |
| AMD Ryzen 9             | 60        | 1.49%   |
| AMD FX                  | 59        | 1.46%   |
| Intel Pentium Dual-Core | 57        | 1.41%   |
| AMD A6                  | 48        | 1.19%   |
| AMD Ryzen 3             | 40        | 0.99%   |
| Intel Pentium Dual      | 37        | 0.92%   |
| Intel Core 2 Quad       | 37        | 0.92%   |
| AMD A8                  | 37        | 0.92%   |
| AMD A10                 | 35        | 0.87%   |
| AMD A4                  | 33        | 0.82%   |
| Intel Core 2            | 27        | 0.67%   |
| AMD Athlon II X2        | 26        | 0.64%   |
| AMD Phenom II X4        | 19        | 0.47%   |
| AMD E1                  | 19        | 0.47%   |
| Intel Pentium Silver    | 16        | 0.4%    |
| Intel Core i9           | 15        | 0.37%   |
| AMD Athlon 64 X2        | 14        | 0.35%   |
| Intel Core M            | 13        | 0.32%   |
| AMD Athlon              | 12        | 0.3%    |
| Intel Pentium Gold      | 11        | 0.27%   |
| AMD Phenom II X6        | 11        | 0.27%   |
| AMD E                   | 11        | 0.27%   |
| AMD Turion 64 X2 Mobile | 10        | 0.25%   |
| Intel Pentium 4         | 7         | 0.17%   |
| AMD E2                  | 7         | 0.17%   |
| AMD Athlon II X4        | 7         | 0.17%   |
| AMD Athlon II           | 6         | 0.15%   |
| Intel Core m5           | 5         | 0.12%   |
| AMD Sempron             | 5         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 1889      | 46.79%  |
| 4      | 1439      | 35.65%  |
| 6      | 300       | 7.43%   |
| 8      | 208       | 5.15%   |
| 1      | 56        | 1.39%   |
| 12     | 49        | 1.21%   |
| 10     | 29        | 0.72%   |
| 16     | 26        | 0.64%   |
| 3      | 22        | 0.54%   |
| 14     | 12        | 0.3%    |
| 24     | 4         | 0.1%    |
| 28     | 2         | 0.05%   |
| 40     | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 4017      | 99.6%   |
| 2      | 16        | 0.4%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 2429      | 60.2%   |
| 1      | 1606      | 39.8%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4033      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306a9    | 302       | 7.36%   |
| 0x206a7    | 301       | 7.34%   |
| Unknown    | 298       | 7.26%   |
| 0x306c3    | 236       | 5.75%   |
| 0x1067a    | 198       | 4.83%   |
| 0x40651    | 117       | 2.85%   |
| 0x806c1    | 110       | 2.68%   |
| 0x406e3    | 107       | 2.61%   |
| 0x20655    | 101       | 2.46%   |
| 0x806e9    | 99        | 2.41%   |
| 0x306d4    | 93        | 2.27%   |
| 0x506e3    | 87        | 2.12%   |
| 0x30678    | 85        | 2.07%   |
| 0x406c4    | 84        | 2.05%   |
| 0x806ea    | 74        | 1.8%    |
| 0x906ea    | 73        | 1.78%   |
| 0x806ec    | 72        | 1.76%   |
| 0x906e9    | 69        | 1.68%   |
| 0x6fd      | 66        | 1.61%   |
| 0x706a8    | 65        | 1.58%   |
| 0x08701021 | 51        | 1.24%   |
| 0x08108109 | 50        | 1.22%   |
| 0x506c9    | 48        | 1.17%   |
| 0x706e5    | 44        | 1.07%   |
| 0x10676    | 43        | 1.05%   |
| 0x20652    | 41        | 1%      |
| 0x06000852 | 39        | 0.95%   |
| 0x010000c8 | 39        | 0.95%   |
| 0x406c3    | 35        | 0.85%   |
| 0x6fb      | 31        | 0.76%   |
| 0x0a50000c | 31        | 0.76%   |
| 0x0800820d | 29        | 0.71%   |
| 0x06001119 | 29        | 0.71%   |
| 0x07030105 | 28        | 0.68%   |
| 0x08600106 | 26        | 0.63%   |
| 0x06006705 | 26        | 0.63%   |
| 0xa0655    | 25        | 0.61%   |
| 0xa0653    | 25        | 0.61%   |
| 0x6f6      | 24        | 0.59%   |
| 0x0a50000d | 23        | 0.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 473       | 11.72%  |
| Haswell          | 388       | 9.62%   |
| SandyBridge      | 325       | 8.05%   |
| IvyBridge        | 325       | 8.05%   |
| Penryn           | 248       | 6.15%   |
| Silvermont       | 220       | 5.45%   |
| Skylake          | 203       | 5.03%   |
| Westmere         | 155       | 3.84%   |
| Core             | 143       | 3.54%   |
| Zen 2            | 124       | 3.07%   |
| TigerLake        | 124       | 3.07%   |
| Zen 3            | 114       | 2.83%   |
| Zen+             | 106       | 2.63%   |
| Unknown          | 102       | 2.53%   |
| Broadwell        | 100       | 2.48%   |
| Goldmont plus    | 91        | 2.26%   |
| K10              | 89        | 2.21%   |
| CometLake        | 79        | 1.96%   |
| Piledriver       | 75        | 1.86%   |
| IceLake          | 75        | 1.86%   |
| Excavator        | 68        | 1.69%   |
| Zen              | 56        | 1.39%   |
| Goldmont         | 51        | 1.26%   |
| Puma             | 44        | 1.09%   |
| Alderlake Hybrid | 40        | 0.99%   |
| Nehalem          | 38        | 0.94%   |
| K8 Hammer        | 31        | 0.77%   |
| Jaguar           | 27        | 0.67%   |
| Bobcat           | 22        | 0.55%   |
| K10 Llano        | 18        | 0.45%   |
| Steamroller      | 17        | 0.42%   |
| Tremont          | 16        | 0.4%    |
| Bulldozer        | 16        | 0.4%    |
| Bonnell          | 16        | 0.4%    |
| NetBurst         | 10        | 0.25%   |
| K8 & K10 hybrid  | 6         | 0.15%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2466      | 53.37%  |
| Nvidia                           | 1096      | 23.72%  |
| AMD                              | 1043      | 22.57%  |
| Matrox Electronics Systems       | 6         | 0.13%   |
| VIA Technologies                 | 4         | 0.09%   |
| Silicon Integrated Systems [SiS] | 3         | 0.06%   |
| ASPEED Technology                | 2         | 0.04%   |
| ATI Technologies                 | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 248       | 5.22%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 191       | 4.02%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 121       | 2.55%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 119       | 2.5%    |
| Intel Core Processor Integrated Graphics Controller                                      | 102       | 2.15%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 98        | 2.06%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 97        | 2.04%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 95        | 2%      |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 93        | 1.96%   |
| Intel HD Graphics 620                                                                    | 84        | 1.77%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 80        | 1.68%   |
| Intel UHD Graphics 620                                                                   | 74        | 1.56%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 74        | 1.56%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 73        | 1.54%   |
| Intel HD Graphics 5500                                                                   | 58        | 1.22%   |
| Intel HD Graphics 630                                                                    | 56        | 1.18%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 55        | 1.16%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 52        | 1.09%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 51        | 1.07%   |
| Intel HD Graphics 530                                                                    | 51        | 1.07%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 48        | 1.01%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 45        | 0.95%   |
| Intel HD Graphics 500                                                                    | 43        | 0.91%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 43        | 0.91%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 41        | 0.86%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 41        | 0.86%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 40        | 0.84%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 40        | 0.84%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 39        | 0.82%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 39        | 0.82%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 37        | 0.78%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 33        | 0.69%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 33        | 0.69%   |
| AMD Lucienne                                                                             | 33        | 0.69%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 32        | 0.67%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 28        | 0.59%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 28        | 0.59%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 26        | 0.55%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 24        | 0.51%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 24        | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| 1 x Intel            | 1957      | 48.27%  |
| 1 x AMD              | 839       | 20.7%   |
| 1 x Nvidia           | 671       | 16.55%  |
| Intel + Nvidia       | 352       | 8.68%   |
| Intel + AMD          | 96        | 2.37%   |
| 2 x AMD              | 54        | 1.33%   |
| AMD + Nvidia         | 53        | 1.31%   |
| 2 x Nvidia           | 9         | 0.22%   |
| Other                | 6         | 0.15%   |
| 1 x VIA              | 4         | 0.1%    |
| 1 x Matrox           | 4         | 0.1%    |
| 1 x SiS              | 3         | 0.07%   |
| 1 x ASPEED           | 2         | 0.05%   |
| 2 x Intel            | 1         | 0.02%   |
| 2 x AMD + 1 x Nvidia | 1         | 0.02%   |
| Nvidia + Matrox      | 1         | 0.02%   |
| AMD + Matrox         | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 3280      | 80.81%  |
| Proprietary | 632       | 15.57%  |
| Unknown     | 147       | 3.62%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2449      | 59.69%  |
| 0.01-0.5   | 494       | 12.04%  |
| 1.01-2.0   | 378       | 9.21%   |
| 0.51-1.0   | 332       | 8.09%   |
| 3.01-4.0   | 184       | 4.48%   |
| 7.01-8.0   | 130       | 3.17%   |
| 5.01-6.0   | 57        | 1.39%   |
| 8.01-16.0  | 43        | 1.05%   |
| 2.01-3.0   | 32        | 0.78%   |
| 16.01-24.0 | 4         | 0.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 523       | 12.77%  |
| AU Optronics            | 489       | 11.94%  |
| BOE                     | 361       | 8.81%   |
| Chimei Innolux          | 357       | 8.71%   |
| LG Display              | 352       | 8.59%   |
| Dell                    | 196       | 4.78%   |
| Goldstar                | 184       | 4.49%   |
| Hewlett-Packard         | 148       | 3.61%   |
| Apple                   | 127       | 3.1%    |
| Acer                    | 117       | 2.86%   |
| Philips                 | 90        | 2.2%    |
| AOC                     | 89        | 2.17%   |
| Lenovo                  | 77        | 1.88%   |
| Chi Mei Optoelectronics | 69        | 1.68%   |
| Ancor Communications    | 68        | 1.66%   |
| BenQ                    | 64        | 1.56%   |
| Sharp                   | 56        | 1.37%   |
| ViewSonic               | 34        | 0.83%   |
| Sony                    | 33        | 0.81%   |
| LG Philips              | 33        | 0.81%   |
| PANDA                   | 31        | 0.76%   |
| LG Electronics          | 31        | 0.76%   |
| InfoVision              | 31        | 0.76%   |
| Unknown                 | 30        | 0.73%   |
| Unknown                 | 25        | 0.61%   |
| ASUSTek Computer        | 24        | 0.59%   |
| Vizio                   | 23        | 0.56%   |
| Iiyama                  | 21        | 0.51%   |
| Fujitsu Siemens         | 16        | 0.39%   |
| Sceptre Tech            | 15        | 0.37%   |
| Toshiba                 | 13        | 0.32%   |
| Panasonic               | 13        | 0.32%   |
| NEC Computers           | 13        | 0.32%   |
| Eizo                    | 13        | 0.32%   |
| CPT                     | 13        | 0.32%   |
| MSI                     | 11        | 0.27%   |
| HPN                     | 10        | 0.24%   |
| HannStar                | 10        | 0.24%   |
| FUS                     | 8         | 0.2%    |
| SLD                     | 6         | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                  | 30        | 0.71%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 23        | 0.55%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 20        | 0.47%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 19        | 0.45%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 18        | 0.43%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 17        | 0.4%    |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 16        | 0.38%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 15        | 0.36%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 15        | 0.36%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 14        | 0.33%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 14        | 0.33%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 12        | 0.28%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 12        | 0.28%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 12        | 0.28%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x170mm 12.2-inch             | 11        | 0.26%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 11        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 11        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 11        | 0.26%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 11        | 0.26%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 10        | 0.24%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch    | 9         | 0.21%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 9         | 0.21%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 9         | 0.21%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                    | 9         | 0.21%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 9         | 0.21%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 9         | 0.21%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 9         | 0.21%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 8         | 0.19%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 8         | 0.19%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 8         | 0.19%   |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch            | 8         | 0.19%   |
| Apple iMac APPA00C 1920x1080 475x267mm 21.5-inch                         | 8         | 0.19%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 7         | 0.17%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch                  | 7         | 0.17%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 7         | 0.17%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 7         | 0.17%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 7         | 0.17%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 7         | 0.17%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 7         | 0.17%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch            | 7         | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1522      | 38.12%  |
| 1366x768 (WXGA)    | 988       | 24.74%  |
| 3840x2160 (4K)     | 212       | 5.31%   |
| 1600x900 (HD+)     | 205       | 5.13%   |
| 2560x1440 (QHD)    | 116       | 2.91%   |
| 1280x800 (WXGA)    | 116       | 2.91%   |
| 1440x900 (WXGA+)   | 114       | 2.85%   |
| 1680x1050 (WSXGA+) | 108       | 2.7%    |
| 1280x1024 (SXGA)   | 100       | 2.5%    |
| Unknown            | 71        | 1.78%   |
| 1920x1200 (WUXGA)  | 62        | 1.55%   |
| 1360x768           | 42        | 1.05%   |
| 3440x1440          | 39        | 0.98%   |
| 3840x1080          | 36        | 0.9%    |
| 2560x1080          | 32        | 0.8%    |
| 2560x1600          | 31        | 0.78%   |
| 2736x1824          | 18        | 0.45%   |
| 1920x540           | 18        | 0.45%   |
| 2160x1440          | 13        | 0.33%   |
| 2880x1800          | 12        | 0.3%    |
| 3200x1800 (QHD+)   | 10        | 0.25%   |
| 2256x1504          | 10        | 0.25%   |
| 1024x768 (XGA)     | 10        | 0.25%   |
| 1600x1200          | 8         | 0.2%    |
| 3840x2400          | 7         | 0.18%   |
| 1280x720 (HD)      | 7         | 0.18%   |
| 1024x600           | 5         | 0.13%   |
| 5760x1080          | 4         | 0.1%    |
| 3840x1600          | 4         | 0.1%    |
| 1920x1280          | 4         | 0.1%    |
| 4480x1440          | 3         | 0.08%   |
| 3600x1080          | 3         | 0.08%   |
| 2880x1920          | 3         | 0.08%   |
| 1920x515           | 3         | 0.08%   |
| 7680x2160          | 2         | 0.05%   |
| 5760x2160          | 2         | 0.05%   |
| 5120x1440          | 2         | 0.05%   |
| 4480x1600          | 2         | 0.05%   |
| 4480x1080          | 2         | 0.05%   |
| 3360x1080          | 2         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1043      | 25.7%   |
| 13      | 393       | 9.68%   |
| Unknown | 317       | 7.81%   |
| 14      | 309       | 7.61%   |
| 17      | 237       | 5.84%   |
| 27      | 226       | 5.57%   |
| 24      | 200       | 4.93%   |
| 21      | 192       | 4.73%   |
| 23      | 176       | 4.34%   |
| 19      | 108       | 2.66%   |
| 11      | 100       | 2.46%   |
| 31      | 92        | 2.27%   |
| 12      | 92        | 2.27%   |
| 20      | 85        | 2.09%   |
| 18      | 83        | 2.05%   |
| 22      | 69        | 1.7%    |
| 34      | 53        | 1.31%   |
| 16      | 31        | 0.76%   |
| 40      | 29        | 0.71%   |
| 84      | 23        | 0.57%   |
| 54      | 23        | 0.57%   |
| 72      | 19        | 0.47%   |
| 32      | 17        | 0.42%   |
| 26      | 16        | 0.39%   |
| 10      | 16        | 0.39%   |
| 25      | 12        | 0.3%    |
| 52      | 8         | 0.2%    |
| 49      | 8         | 0.2%    |
| 65      | 7         | 0.17%   |
| 36      | 7         | 0.17%   |
| 48      | 6         | 0.15%   |
| 28      | 5         | 0.12%   |
| 64      | 4         | 0.1%    |
| 46      | 4         | 0.1%    |
| 37      | 4         | 0.1%    |
| 29      | 4         | 0.1%    |
| 74      | 3         | 0.07%   |
| 58      | 3         | 0.07%   |
| 42      | 3         | 0.07%   |
| 39      | 3         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1587      | 39.68%  |
| 501-600        | 567       | 14.18%  |
| 401-500        | 476       | 11.9%   |
| 201-300        | 397       | 9.93%   |
| Unknown        | 317       | 7.93%   |
| 351-400        | 278       | 6.95%   |
| 601-700        | 127       | 3.18%   |
| 701-800        | 80        | 2%      |
| 1001-1500      | 74        | 1.85%   |
| 1501-2000      | 48        | 1.2%    |
| 801-900        | 39        | 0.98%   |
| 901-1000       | 6         | 0.15%   |
| 101-200        | 2         | 0.05%   |
| More than 2000 | 1         | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2777      | 73.84%  |
| 16/10   | 446       | 11.86%  |
| Unknown | 281       | 7.47%   |
| 5/4     | 91        | 2.42%   |
| 21/9    | 61        | 1.62%   |
| 3/2     | 55        | 1.46%   |
| 4/3     | 26        | 0.69%   |
| 32/9    | 12        | 0.32%   |
| 6/5     | 5         | 0.13%   |
| 3.73    | 3         | 0.08%   |
| 0.62    | 2         | 0.05%   |
| 1.00    | 1         | 0.03%   |
| 0.56    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1037      | 25.73%  |
| 81-90          | 566       | 14.04%  |
| 201-250        | 510       | 12.65%  |
| Unknown        | 317       | 7.86%   |
| 151-200        | 262       | 6.5%    |
| 301-350        | 235       | 5.83%   |
| 351-500        | 172       | 4.27%   |
| 121-130        | 161       | 3.99%   |
| 71-80          | 148       | 3.67%   |
| 141-150        | 116       | 2.88%   |
| More than 1000 | 112       | 2.78%   |
| 51-60          | 102       | 2.53%   |
| 61-70          | 78        | 1.94%   |
| 251-300        | 73        | 1.81%   |
| 501-1000       | 61        | 1.51%   |
| 131-140        | 28        | 0.69%   |
| 111-120        | 27        | 0.67%   |
| 41-50          | 14        | 0.35%   |
| 91-100         | 10        | 0.25%   |
| 1-40           | 2         | 0.05%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 1183      | 30.01%  |
| 51-100        | 1149      | 29.15%  |
| 121-160       | 911       | 23.11%  |
| Unknown       | 318       | 8.07%   |
| 161-240       | 208       | 5.28%   |
| 1-50          | 109       | 2.77%   |
| More than 240 | 64        | 1.62%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3433      | 83.59%  |
| 2     | 484       | 11.78%  |
| 0     | 147       | 3.58%   |
| 3     | 38        | 0.93%   |
| 4     | 4         | 0.1%    |
| 5     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2168      | 35.28%  |
| Intel                             | 1766      | 28.74%  |
| Qualcomm Atheros                  | 733       | 11.93%  |
| Broadcom                          | 433       | 7.05%   |
| Broadcom Limited                  | 124       | 2.02%   |
| Ralink Technology                 | 92        | 1.5%    |
| TP-Link                           | 89        | 1.45%   |
| Marvell Technology Group          | 86        | 1.4%    |
| Ralink                            | 72        | 1.17%   |
| MediaTek                          | 72        | 1.17%   |
| Nvidia                            | 66        | 1.07%   |
| Samsung Electronics               | 41        | 0.67%   |
| ASIX Electronics                  | 33        | 0.54%   |
| NetGear                           | 25        | 0.41%   |
| Dell                              | 25        | 0.41%   |
| DisplayLink                       | 21        | 0.34%   |
| Xiaomi                            | 20        | 0.33%   |
| Qualcomm Atheros Communications   | 17        | 0.28%   |
| Sierra Wireless                   | 16        | 0.26%   |
| Microsoft                         | 16        | 0.26%   |
| Huawei Technologies               | 16        | 0.26%   |
| JMicron Technology                | 14        | 0.23%   |
| D-Link                            | 14        | 0.23%   |
| D-Link System                     | 13        | 0.21%   |
| Hewlett-Packard                   | 12        | 0.2%    |
| OPPO Electronics                  | 10        | 0.16%   |
| Edimax Technology                 | 10        | 0.16%   |
| ASUSTek Computer                  | 10        | 0.16%   |
| Qualcomm                          | 8         | 0.13%   |
| Motorola PCS                      | 8         | 0.13%   |
| Linksys                           | 7         | 0.11%   |
| Ericsson Business Mobile Networks | 7         | 0.11%   |
| Aquantia                          | 7         | 0.11%   |
| Belkin Components                 | 6         | 0.1%    |
| T & A Mobile Phones               | 5         | 0.08%   |
| Google                            | 5         | 0.08%   |
| VIA Technologies                  | 4         | 0.07%   |
| OnePlus Technology (Shenzhen)     | 4         | 0.07%   |
| ZyDAS                             | 3         | 0.05%   |
| Silicon Integrated Systems [SiS]  | 3         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 1357      | 18.94%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 322       | 4.49%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 178       | 2.48%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 120       | 1.68%   |
| Intel Wi-Fi 6 AX200                                                    | 120       | 1.68%   |
| Intel Wireless 7265                                                    | 117       | 1.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 104       | 1.45%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 100       | 1.4%    |
| Intel Wireless 8265 / 8275                                             | 96        | 1.34%   |
| Intel Wireless 7260                                                    | 96        | 1.34%   |
| Intel Wi-Fi 6 AX201                                                    | 86        | 1.2%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 85        | 1.19%   |
| Realtek RTL8125 2.5GbE Controller                                      | 84        | 1.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 83        | 1.16%   |
| Intel Ethernet Connection I217-LM                                      | 82        | 1.14%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 67        | 0.94%   |
| Intel Wireless 3165                                                    | 66        | 0.92%   |
| Intel Wireless 8260                                                    | 65        | 0.91%   |
| Broadcom BCM43142 802.11b/g/n                                          | 62        | 0.87%   |
| Intel I211 Gigabit Network Connection                                  | 61        | 0.85%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 61        | 0.85%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 57        | 0.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 56        | 0.78%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 51        | 0.71%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 50        | 0.7%    |
| Realtek 802.11ac NIC                                                   | 50        | 0.7%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 49        | 0.68%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 44        | 0.61%   |
| Intel Ethernet Connection (2) I219-V                                   | 44        | 0.61%   |
| Intel Ethernet Controller I225-V                                       | 43        | 0.6%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 42        | 0.59%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 41        | 0.57%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 40        | 0.56%   |
| Ralink MT7601U Wireless Adapter                                        | 39        | 0.54%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 39        | 0.54%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 37        | 0.52%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 37        | 0.52%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 36        | 0.5%    |
| Realtek RTL8188EE Wireless Network Adapter                             | 35        | 0.49%   |
| Intel WiFi Link 5100                                                   | 31        | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1347      | 38.91%  |
| Realtek Semiconductor                 | 658       | 19.01%  |
| Qualcomm Atheros                      | 582       | 16.81%  |
| Broadcom                              | 302       | 8.72%   |
| Ralink Technology                     | 92        | 2.66%   |
| Broadcom Limited                      | 82        | 2.37%   |
| TP-Link                               | 78        | 2.25%   |
| Ralink                                | 72        | 2.08%   |
| MediaTek                              | 62        | 1.79%   |
| NetGear                               | 25        | 0.72%   |
| Marvell Technology Group              | 22        | 0.64%   |
| Qualcomm Atheros Communications       | 17        | 0.49%   |
| Sierra Wireless                       | 16        | 0.46%   |
| Dell                                  | 14        | 0.4%    |
| D-Link                                | 14        | 0.4%    |
| Microsoft                             | 13        | 0.38%   |
| D-Link System                         | 11        | 0.32%   |
| Edimax Technology                     | 10        | 0.29%   |
| ASUSTek Computer                      | 8         | 0.23%   |
| Linksys                               | 6         | 0.17%   |
| Belkin Components                     | 6         | 0.17%   |
| ZyDAS                                 | 3         | 0.09%   |
| AVM                                   | 3         | 0.09%   |
| ZyXEL Communications                  | 2         | 0.06%   |
| TRENDnet                              | 2         | 0.06%   |
| Hewlett-Packard                       | 2         | 0.06%   |
| Gemtek                                | 2         | 0.06%   |
| FIBOCOM                               | 2         | 0.06%   |
| Xiaomi                                | 1         | 0.03%   |
| Tenda                                 | 1         | 0.03%   |
| Qualcomm                              | 1         | 0.03%   |
| Panasonic (Matsushita)                | 1         | 0.03%   |
| Ovislink                              | 1         | 0.03%   |
| Mercucys                              | 1         | 0.03%   |
| Askey Computer                        | 1         | 0.03%   |
| ADMtek                                | 1         | 0.03%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 120       | 3.43%   |
| Intel Wi-Fi 6 AX200                                            | 120       | 3.43%   |
| Intel Wireless 7265                                            | 117       | 3.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 104       | 2.97%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 100       | 2.86%   |
| Intel Wireless 8265 / 8275                                     | 96        | 2.75%   |
| Intel Wireless 7260                                            | 96        | 2.75%   |
| Intel Wi-Fi 6 AX201                                            | 86        | 2.46%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 85        | 2.43%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 83        | 2.37%   |
| Intel Wireless 3165                                            | 66        | 1.89%   |
| Intel Wireless 8260                                            | 65        | 1.86%   |
| Broadcom BCM43142 802.11b/g/n                                  | 62        | 1.77%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 61        | 1.74%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 57        | 1.63%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 56        | 1.6%    |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 51        | 1.46%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 50        | 1.43%   |
| Realtek 802.11ac NIC                                           | 50        | 1.43%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 49        | 1.4%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 44        | 1.26%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 42        | 1.2%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 41        | 1.17%   |
| Ralink MT7601U Wireless Adapter                                | 39        | 1.12%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 39        | 1.12%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 37        | 1.06%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 37        | 1.06%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 35        | 1%      |
| Intel WiFi Link 5100                                           | 31        | 0.89%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 30        | 0.86%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 29        | 0.83%   |
| Intel Centrino Ultimate-N 6300                                 | 29        | 0.83%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 27        | 0.77%   |
| Intel Wireless 3160                                            | 27        | 0.77%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 25        | 0.71%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 24        | 0.69%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 24        | 0.69%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 24        | 0.69%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 23        | 0.66%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 22        | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1875      | 52.74%  |
| Intel                             | 872       | 24.53%  |
| Qualcomm Atheros                  | 209       | 5.88%   |
| Broadcom                          | 189       | 5.32%   |
| Nvidia                            | 66        | 1.86%   |
| Marvell Technology Group          | 64        | 1.8%    |
| Broadcom Limited                  | 45        | 1.27%   |
| Samsung Electronics               | 40        | 1.13%   |
| ASIX Electronics                  | 33        | 0.93%   |
| DisplayLink                       | 21        | 0.59%   |
| Xiaomi                            | 19        | 0.53%   |
| JMicron Technology                | 14        | 0.39%   |
| Huawei Technologies               | 13        | 0.37%   |
| TP-Link                           | 11        | 0.31%   |
| OPPO Electronics                  | 10        | 0.28%   |
| MediaTek                          | 9         | 0.25%   |
| Qualcomm                          | 7         | 0.2%    |
| Aquantia                          | 7         | 0.2%    |
| Motorola PCS                      | 5         | 0.14%   |
| Google                            | 5         | 0.14%   |
| VIA Technologies                  | 4         | 0.11%   |
| Silicon Integrated Systems [SiS]  | 3         | 0.08%   |
| Hewlett-Packard                   | 3         | 0.08%   |
| Sundance Technology Inc / IC Plus | 2         | 0.06%   |
| OnePlus Technology (Shenzhen)     | 2         | 0.06%   |
| Microsoft                         | 2         | 0.06%   |
| Lenovo                            | 2         | 0.06%   |
| ICS Advent                        | 2         | 0.06%   |
| HMD Global                        | 2         | 0.06%   |
| D-Link System                     | 2         | 0.06%   |
| ASUSTek Computer                  | 2         | 0.06%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.03%   |
| vivo                              | 1         | 0.03%   |
| T & A Mobile Phones               | 1         | 0.03%   |
| Sun Microsystems                  | 1         | 0.03%   |
| Spreadtrum Communications         | 1         | 0.03%   |
| Research In Motion                | 1         | 0.03%   |
| Novatel Wireless                  | 1         | 0.03%   |
| Motorola BCS                      | 1         | 0.03%   |
| Linksys                           | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 1357      | 37.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 322       | 8.94%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 178       | 4.94%   |
| Realtek RTL8125 2.5GbE Controller                                      | 84        | 2.33%   |
| Intel Ethernet Connection I217-LM                                      | 82        | 2.28%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 67        | 1.86%   |
| Intel I211 Gigabit Network Connection                                  | 61        | 1.69%   |
| Intel Ethernet Connection (2) I219-V                                   | 44        | 1.22%   |
| Intel Ethernet Controller I225-V                                       | 43        | 1.19%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 40        | 1.11%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 36        | 1%      |
| Nvidia MCP79 Ethernet                                                  | 30        | 0.83%   |
| Intel Ethernet Connection I219-LM                                      | 30        | 0.83%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 28        | 0.78%   |
| Intel Ethernet Connection I217-V                                       | 28        | 0.78%   |
| ASIX AX88179 Gigabit Ethernet                                          | 28        | 0.78%   |
| Intel Ethernet Connection I218-LM                                      | 27        | 0.75%   |
| Intel Ethernet Connection (4) I219-LM                                  | 25        | 0.69%   |
| Intel 82577LM Gigabit Network Connection                               | 25        | 0.69%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 25        | 0.69%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 24        | 0.67%   |
| Intel Ethernet Connection (2) I219-LM                                  | 23        | 0.64%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 21        | 0.58%   |
| Nvidia MCP61 Ethernet                                                  | 20        | 0.56%   |
| Intel 82579V Gigabit Network Connection                                | 20        | 0.56%   |
| Intel 82567LM Gigabit Network Connection                               | 19        | 0.53%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 18        | 0.5%    |
| Intel Ethernet Connection I219-V                                       | 18        | 0.5%    |
| Intel 82567LM-3 Gigabit Network Connection                             | 18        | 0.5%    |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 17        | 0.47%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 17        | 0.47%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 17        | 0.47%   |
| Intel Ethernet Connection (7) I219-V                                   | 17        | 0.47%   |
| Intel Ethernet Connection (4) I219-V                                   | 17        | 0.47%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 17        | 0.47%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 16        | 0.44%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 15        | 0.42%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 15        | 0.42%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 14        | 0.39%   |
| Intel Ethernet Connection (5) I219-LM                                  | 14        | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 3366      | 50.56%  |
| WiFi     | 3229      | 48.5%   |
| Modem    | 51        | 0.77%   |
| Unknown  | 12        | 0.18%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2531      | 60.39%  |
| Ethernet | 1655      | 39.49%  |
| Unknown  | 3         | 0.07%   |
| Modem    | 2         | 0.05%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2190      | 54.1%   |
| 1     | 1647      | 40.69%  |
| 0     | 135       | 3.33%   |
| 3     | 69        | 1.7%    |
| 5     | 3         | 0.07%   |
| 4     | 3         | 0.07%   |
| 7     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2776      | 67.67%  |
| Yes  | 1326      | 32.33%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1034      | 42.24%  |
| Realtek Semiconductor           | 299       | 12.21%  |
| Qualcomm Atheros Communications | 213       | 8.7%    |
| Broadcom                        | 136       | 5.56%   |
| Apple                           | 135       | 5.51%   |
| Cambridge Silicon Radio         | 127       | 5.19%   |
| IMC Networks                    | 104       | 4.25%   |
| Foxconn / Hon Hai               | 65        | 2.66%   |
| Lite-On Technology              | 61        | 2.49%   |
| Dell                            | 44        | 1.8%    |
| Hewlett-Packard                 | 35        | 1.43%   |
| ASUSTek Computer                | 35        | 1.43%   |
| Toshiba                         | 32        | 1.31%   |
| Marvell Semiconductor           | 21        | 0.86%   |
| Ralink                          | 19        | 0.78%   |
| MediaTek                        | 16        | 0.65%   |
| Realtek                         | 12        | 0.49%   |
| TP-Link                         | 8         | 0.33%   |
| Foxconn International           | 7         | 0.29%   |
| Alps Electric                   | 7         | 0.29%   |
| Integrated System Solution      | 6         | 0.25%   |
| Dynex                           | 5         | 0.2%    |
| Unknown                         | 5         | 0.2%    |
| Belkin Components               | 4         | 0.16%   |
| Ralink Technology               | 3         | 0.12%   |
| Askey Computer                  | 3         | 0.12%   |
| Actions                         | 3         | 0.12%   |
| Sitecom Europe                  | 1         | 0.04%   |
| Qcom                            | 1         | 0.04%   |
| National Semiconductor          | 1         | 0.04%   |
| Micro Star International        | 1         | 0.04%   |
| Logitech                        | 1         | 0.04%   |
| Edimax Technology               | 1         | 0.04%   |
| D-Link System                   | 1         | 0.04%   |
| Conwise Technology              | 1         | 0.04%   |
| Chicony Electronics             | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 298       | 12.16%  |
| Realtek Bluetooth Radio                             | 208       | 8.49%   |
| Intel AX201 Bluetooth                               | 157       | 6.41%   |
| Intel Bluetooth Device                              | 144       | 5.88%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 129       | 5.26%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 127       | 5.18%   |
| Intel AX200 Bluetooth                               | 104       | 4.24%   |
| Qualcomm Atheros  Bluetooth Device                  | 91        | 3.71%   |
| Apple Bluetooth Host Controller                     | 60        | 2.45%   |
| Intel AX210 Bluetooth                               | 53        | 2.16%   |
| Realtek  Bluetooth 4.2 Adapter                      | 42        | 1.71%   |
| Intel Wireless-AC 3168 Bluetooth                    | 39        | 1.59%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 39        | 1.59%   |
| IMC Networks Bluetooth Device                       | 35        | 1.43%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 35        | 1.43%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 31        | 1.26%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 30        | 1.22%   |
| IMC Networks Bluetooth Radio                        | 29        | 1.18%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 28        | 1.14%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 26        | 1.06%   |
| Apple Bluetooth USB Host Controller                 | 25        | 1.02%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 24        | 0.98%   |
| Intel AX211 Bluetooth                               | 23        | 0.94%   |
| IMC Networks Wireless_Device                        | 22        | 0.9%    |
| Realtek 802.11ac WLAN Adapter                       | 21        | 0.86%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 21        | 0.86%   |
| Marvell Bluetooth and Wireless LAN Composite        | 20        | 0.82%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 20        | 0.82%   |
| Lite-On Atheros AR3012 Bluetooth                    | 20        | 0.82%   |
| Foxconn / Hon Hai Bluetooth Device                  | 20        | 0.82%   |
| Ralink RT3290 Bluetooth                             | 19        | 0.78%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 19        | 0.78%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 19        | 0.78%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 19        | 0.78%   |
| MediaTek Wireless_Device                            | 15        | 0.61%   |
| Dell DW375 Bluetooth Module                         | 15        | 0.61%   |
| Apple Bluetooth HCI                                 | 15        | 0.61%   |
| HP Broadcom 2070 Bluetooth Combo                    | 14        | 0.57%   |
| Broadcom BCM2045B (BDC-2.1)                         | 14        | 0.57%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 13        | 0.53%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 2981      | 55.36%  |
| AMD                                          | 1109      | 20.59%  |
| Nvidia                                       | 859       | 15.95%  |
| C-Media Electronics                          | 65        | 1.21%   |
| Creative Labs                                | 26        | 0.48%   |
| Logitech                                     | 22        | 0.41%   |
| JMTek                                        | 22        | 0.41%   |
| Generalplus Technology                       | 18        | 0.33%   |
| Texas Instruments                            | 17        | 0.32%   |
| Kingston Technology                          | 17        | 0.32%   |
| ASUSTek Computer                             | 17        | 0.32%   |
| Realtek Semiconductor                        | 13        | 0.24%   |
| Plantronics                                  | 11        | 0.2%    |
| VIA Technologies                             | 10        | 0.19%   |
| Razer USA                                    | 10        | 0.19%   |
| GN Netcom                                    | 10        | 0.19%   |
| Creative Technology                          | 10        | 0.19%   |
| Lenovo                                       | 8         | 0.15%   |
| Tenx Technology                              | 7         | 0.13%   |
| SteelSeries ApS                              | 7         | 0.13%   |
| Micro Star International                     | 6         | 0.11%   |
| Focusrite-Novation                           | 6         | 0.11%   |
| Zoran Co. Personal Media Division (Nogatech) | 5         | 0.09%   |
| DCMT Technology                              | 5         | 0.09%   |
| Corsair                                      | 5         | 0.09%   |
| Sony                                         | 4         | 0.07%   |
| PreSonus Audio Electronics                   | 4         | 0.07%   |
| KTMicro                                      | 4         | 0.07%   |
| DSEA A/S                                     | 4         | 0.07%   |
| BR25                                         | 4         | 0.07%   |
| Silicon Integrated Systems [SiS]             | 3         | 0.06%   |
| Samsung Electronics                          | 3         | 0.06%   |
| RODE Microphones                             | 3         | 0.06%   |
| BEHRINGER International                      | 3         | 0.06%   |
| Astro Gaming                                 | 3         | 0.06%   |
| Asahi Kasei Microsystems                     | 3         | 0.06%   |
| Apple                                        | 3         | 0.06%   |
| AKAI Professional M.I.                       | 3         | 0.06%   |
| Yamaha                                       | 2         | 0.04%   |
| XMOS                                         | 2         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 321       | 5.01%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 308       | 4.81%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 297       | 4.64%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 269       | 4.2%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 233       | 3.64%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 167       | 2.61%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 161       | 2.51%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 152       | 2.37%   |
| AMD FCH Azalia Controller                                                                         | 151       | 2.36%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 130       | 2.03%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 128       | 2%      |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 124       | 1.94%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 121       | 1.89%   |
| Intel 8 Series HD Audio Controller                                                                | 121       | 1.89%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 121       | 1.89%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 117       | 1.83%   |
| Intel Cannon Lake PCH cAVS                                                                        | 95        | 1.48%   |
| Intel Broadwell-U Audio Controller                                                                | 95        | 1.48%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 94        | 1.47%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 91        | 1.42%   |
| AMD Kabini HDMI/DP Audio                                                                          | 91        | 1.42%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 89        | 1.39%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 87        | 1.36%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 71        | 1.11%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 71        | 1.11%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 69        | 1.08%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 65        | 1.02%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 64        | 1%      |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 64        | 1%      |
| Intel 200 Series PCH HD Audio                                                                     | 59        | 0.92%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 58        | 0.91%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 56        | 0.87%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 51        | 0.8%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 48        | 0.75%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 48        | 0.75%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 47        | 0.73%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 45        | 0.7%    |
| Nvidia High Definition Audio Controller                                                           | 44        | 0.69%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 44        | 0.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 44        | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Samsung Electronics    | 218       | 24.17%  |
| SK hynix               | 165       | 18.29%  |
| Micron Technology      | 98        | 10.86%  |
| Unknown                | 81        | 8.98%   |
| Kingston               | 74        | 8.2%    |
| Crucial                | 47        | 5.21%   |
| Unknown (ABCD)         | 27        | 2.99%   |
| Corsair                | 27        | 2.99%   |
| G.Skill                | 25        | 2.77%   |
| A-DATA Technology      | 17        | 1.88%   |
| Team                   | 15        | 1.66%   |
| Elpida                 | 14        | 1.55%   |
| Ramaxel Technology     | 12        | 1.33%   |
| Unknown                | 9         | 1%      |
| Nanya Technology       | 8         | 0.89%   |
| Smart                  | 7         | 0.78%   |
| Patriot                | 6         | 0.67%   |
| Transcend              | 4         | 0.44%   |
| Timetec                | 4         | 0.44%   |
| Avant                  | 3         | 0.33%   |
| Wilk                   | 2         | 0.22%   |
| Unifosa                | 2         | 0.22%   |
| Teikon                 | 2         | 0.22%   |
| Qimonda                | 2         | 0.22%   |
| ff                     | 2         | 0.22%   |
| fef5                   | 2         | 0.22%   |
| Apacer                 | 2         | 0.22%   |
| 4ea5                   | 2         | 0.22%   |
| Unknown (08B5)         | 1         | 0.11%   |
| Unknown (07F7)         | 1         | 0.11%   |
| Unknown (000080B30080) | 1         | 0.11%   |
| SUPER KINGSTEK         | 1         | 0.11%   |
| Strontium              | 1         | 0.11%   |
| Smart Brazil           | 1         | 0.11%   |
| Silicon Power          | 1         | 0.11%   |
| SHARETRONIC            | 1         | 0.11%   |
| PUSKILL                | 1         | 0.11%   |
| ProMos/Mosel Vitelic   | 1         | 0.11%   |
| pqi                    | 1         | 0.11%   |
| PNY                    | 1         | 0.11%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 23        | 2.41%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 11        | 1.15%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 10        | 1.05%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 10        | 1.05%   |
| Unknown                                                          | 9         | 0.94%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 0.84%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 0.84%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 8         | 0.84%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 7         | 0.73%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 0.73%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 0.73%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 7         | 0.73%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 7         | 0.73%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                     | 6         | 0.63%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 0.63%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 6         | 0.63%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 6         | 0.63%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 5         | 0.52%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 5         | 0.52%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.52%   |
| SK hynix RAM HMA851S6CJR6N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 0.52%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 5         | 0.52%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 5         | 0.52%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 4         | 0.42%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 4         | 0.42%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 4         | 0.42%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 0.42%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.42%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 4         | 0.42%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 4         | 0.42%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 4         | 0.42%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.42%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.42%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 4         | 0.42%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 4         | 0.42%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.42%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.42%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 4         | 0.42%   |
| Samsung RAM M471A1G44BB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 4         | 0.42%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 4         | 0.42%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 329       | 42.45%  |
| DDR3    | 276       | 35.61%  |
| LPDDR4  | 58        | 7.48%   |
| LPDDR3  | 30        | 3.87%   |
| DDR2    | 30        | 3.87%   |
| SDRAM   | 19        | 2.45%   |
| Unknown | 16        | 2.06%   |
| DDR5    | 8         | 1.03%   |
| LPDDR5  | 4         | 0.52%   |
| DDR     | 4         | 0.52%   |
| DRAM    | 1         | 0.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 486       | 62.71%  |
| DIMM         | 194       | 25.03%  |
| Row Of Chips | 77        | 9.94%   |
| Chip         | 9         | 1.16%   |
| Unknown      | 8         | 1.03%   |
| FB-DIMM      | 1         | 0.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 329       | 38.34%  |
| 4096  | 258       | 30.07%  |
| 2048  | 121       | 14.1%   |
| 16384 | 96        | 11.19%  |
| 32768 | 26        | 3.03%   |
| 1024  | 26        | 3.03%   |
| 512   | 2         | 0.23%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 176       | 21%     |
| 3200    | 138       | 16.47%  |
| 2667    | 111       | 13.25%  |
| 2400    | 74        | 8.83%   |
| 1333    | 54        | 6.44%   |
| 2133    | 33        | 3.94%   |
| 1334    | 26        | 3.1%    |
| 1867    | 19        | 2.27%   |
| 4267    | 17        | 2.03%   |
| Unknown | 16        | 1.91%   |
| 3600    | 15        | 1.79%   |
| 800     | 14        | 1.67%   |
| 667     | 14        | 1.67%   |
| 1066    | 12        | 1.43%   |
| 3266    | 10        | 1.19%   |
| 4800    | 7         | 0.84%   |
| 3733    | 7         | 0.84%   |
| 2048    | 7         | 0.84%   |
| 1866    | 7         | 0.84%   |
| 1067    | 7         | 0.84%   |
| 3000    | 6         | 0.72%   |
| 1800    | 6         | 0.72%   |
| 6400    | 5         | 0.6%    |
| 8400    | 4         | 0.48%   |
| 3800    | 4         | 0.48%   |
| 975     | 4         | 0.48%   |
| 4266    | 3         | 0.36%   |
| 4199    | 3         | 0.36%   |
| 3866    | 3         | 0.36%   |
| 3400    | 3         | 0.36%   |
| 2933    | 3         | 0.36%   |
| 2666    | 3         | 0.36%   |
| 3666    | 2         | 0.24%   |
| 3500    | 2         | 0.24%   |
| 3466    | 2         | 0.24%   |
| 400     | 2         | 0.24%   |
| 6000    | 1         | 0.12%   |
| 5600    | 1         | 0.12%   |
| 5354    | 1         | 0.12%   |
| 5200    | 1         | 0.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 35        | 32.71%  |
| Canon                 | 19        | 17.76%  |
| Brother Industries    | 18        | 16.82%  |
| Seiko Epson           | 15        | 14.02%  |
| Samsung Electronics   | 12        | 11.21%  |
| Lexmark International | 3         | 2.8%    |
| Zebra                 | 1         | 0.93%   |
| Ricoh                 | 1         | 0.93%   |
| QinHeng Electronics   | 1         | 0.93%   |
| Konica Minolta        | 1         | 0.93%   |
| GG IMAGE              | 1         | 0.93%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Seiko Epson L3110 Series                     | 3         | 2.8%    |
| HP DeskJet 2700 series                       | 3         | 2.8%    |
| Samsung M2070 Series                         | 2         | 1.87%   |
| Samsung M2020 Series                         | 2         | 1.87%   |
| Samsung C460 Series                          | 2         | 1.87%   |
| HP OfficeJet 6950                            | 2         | 1.87%   |
| HP LaserJet Professional P1102w              | 2         | 1.87%   |
| HP ENVY Photo 6200 series                    | 2         | 1.87%   |
| HP ENVY 4520 series                          | 2         | 1.87%   |
| HP DeskJet 2130 series                       | 2         | 1.87%   |
| Canon TS3100 series                          | 2         | 1.87%   |
| Canon PIXMA MG3600 Series                    | 2         | 1.87%   |
| Canon LiDE 400                               | 2         | 1.87%   |
| Brother HL-2140 series                       | 2         | 1.87%   |
| Zebra ZP 450 Printer                         | 1         | 0.93%   |
| Seiko Epson XP-7100 Series                   | 1         | 0.93%   |
| Seiko Epson XP-235 Series                    | 1         | 0.93%   |
| Seiko Epson XP-205 207 Series                | 1         | 0.93%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1         | 0.93%   |
| Seiko Epson L805 Series                      | 1         | 0.93%   |
| Seiko Epson L355 Series                      | 1         | 0.93%   |
| Seiko Epson L3250 Series                     | 1         | 0.93%   |
| Seiko Epson ET-3850 Series                   | 1         | 0.93%   |
| Seiko Epson ET-2820 Series                   | 1         | 0.93%   |
| Seiko Epson ET-2800 Series                   | 1         | 0.93%   |
| Seiko Epson ET-2710 Series                   | 1         | 0.93%   |
| Seiko Epson AcuLaser C1700                   | 1         | 0.93%   |
| Samsung SCX-483x 5x3x Series                 | 1         | 0.93%   |
| Samsung SCX-4623 Series                      | 1         | 0.93%   |
| Samsung SCX-4200 series                      | 1         | 0.93%   |
| Samsung SCX-3400 Series                      | 1         | 0.93%   |
| Samsung ML-2950 Series                       | 1         | 0.93%   |
| Samsung ML-216x Series Laser Printer         | 1         | 0.93%   |
| Ricoh SP 112SU                               | 1         | 0.93%   |
| QinHeng CH340S                               | 1         | 0.93%   |
| Lexmark International MX310dn                | 1         | 0.93%   |
| Lexmark International Laser Printer E232     | 1         | 0.93%   |
| Lexmark International 2400 series            | 1         | 0.93%   |
| Konica Minolta PagePro 1380MF                | 1         | 0.93%   |
| HP Smart Tank 510 series                     | 1         | 0.93%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 14        | 66.67%  |
| Seiko Epson     | 4         | 19.05%  |
| Hewlett-Packard | 3         | 14.29%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X750 [Perfection 4490 Photo] | 3         | 13.64%  |
| Canon CanoScan LiDE 90                      | 2         | 9.09%   |
| Canon CanoScan LiDE 220                     | 2         | 9.09%   |
| Canon CanoScan LiDE 110                     | 2         | 9.09%   |
| Seiko Epson Scanner                         | 1         | 4.55%   |
| HP ScanJet 2400c                            | 1         | 4.55%   |
| HP Scanjet 200                              | 1         | 4.55%   |
| HP PSC 1200                                 | 1         | 4.55%   |
| Canon CanoScan N670U/N676U/LiDE 20          | 1         | 4.55%   |
| Canon CanoScan LiDE 700F                    | 1         | 4.55%   |
| Canon CanoScan LiDE 60                      | 1         | 4.55%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40      | 1         | 4.55%   |
| Canon CanoScan LIDE 25                      | 1         | 4.55%   |
| Canon CanoScan LiDE 100                     | 1         | 4.55%   |
| Canon CanoScan D660U                        | 1         | 4.55%   |
| Canon CanoScan 8800F                        | 1         | 4.55%   |
| Canon CanoScan 5600F                        | 1         | 4.55%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 489       | 20.65%  |
| Microdia                               | 214       | 9.04%   |
| Realtek Semiconductor                  | 198       | 8.36%   |
| IMC Networks                           | 168       | 7.09%   |
| Sunplus Innovation Technology          | 134       | 5.66%   |
| Apple                                  | 117       | 4.94%   |
| Bison Electronics                      | 105       | 4.43%   |
| Cheng Uei Precision Industry (Foxlink) | 103       | 4.35%   |
| Quanta                                 | 99        | 4.18%   |
| Logitech                               | 90        | 3.8%    |
| Suyin                                  | 82        | 3.46%   |
| Syntek                                 | 65        | 2.74%   |
| Acer                                   | 52        | 2.2%    |
| Lite-On Technology                     | 49        | 2.07%   |
| Alcor Micro                            | 40        | 1.69%   |
| Silicon Motion                         | 36        | 1.52%   |
| Luxvisions Innotech Limited            | 29        | 1.22%   |
| Ricoh                                  | 22        | 0.93%   |
| Microsoft                              | 22        | 0.93%   |
| Samsung Electronics                    | 21        | 0.89%   |
| Sonix Technology                       | 18        | 0.76%   |
| Z-Star Microelectronics                | 15        | 0.63%   |
| icSpring                               | 14        | 0.59%   |
| Primax Electronics                     | 12        | 0.51%   |
| Generalplus Technology                 | 12        | 0.51%   |
| Lenovo                                 | 10        | 0.42%   |
| ARC International                      | 10        | 0.42%   |
| SunplusIT                              | 9         | 0.38%   |
| GEMBIRD                                | 9         | 0.38%   |
| ALi                                    | 8         | 0.34%   |
| Importek                               | 7         | 0.3%    |
| Y Media                                | 5         | 0.21%   |
| Shenzhen Kingcome Optoelectronic       | 5         | 0.21%   |
| Jieli Technology                       | 5         | 0.21%   |
| Genesys Logic                          | 5         | 0.21%   |
| Sunplus Technology                     | 4         | 0.17%   |
| Razer USA                              | 4         | 0.17%   |
| OmniVision Technologies                | 4         | 0.17%   |
| Intel                                  | 4         | 0.17%   |
| Creative Technology                    | 4         | 0.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 84        | 3.52%   |
| Microdia Integrated_Webcam_HD                       | 49        | 2.06%   |
| Syntek Integrated Camera                            | 42        | 1.76%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 42        | 1.76%   |
| Realtek Integrated_Webcam_HD                        | 41        | 1.72%   |
| Apple FaceTime HD Camera (Built-in)                 | 41        | 1.72%   |
| Chicony HD WebCam                                   | 40        | 1.68%   |
| IMC Networks Integrated Camera                      | 34        | 1.43%   |
| Bison Integrated Camera                             | 34        | 1.43%   |
| Realtek USB Camera                                  | 32        | 1.34%   |
| Apple Built-in iSight                               | 31        | 1.3%    |
| Chicony HP Truevision HD                            | 29        | 1.22%   |
| Microdia Integrated Webcam                          | 26        | 1.09%   |
| Sunplus Integrated_Webcam_HD                        | 25        | 1.05%   |
| Chicony TOSHIBA Web Camera - HD                     | 25        | 1.05%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 24        | 1.01%   |
| Samsung Galaxy series, misc. (MTP mode)             | 21        | 0.88%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 21        | 0.88%   |
| Logitech Webcam C270                                | 20        | 0.84%   |
| Alcor Micro USB 2.0 PC cam                          | 20        | 0.84%   |
| Acer Integrated Camera                              | 20        | 0.84%   |
| Microdia Webcam Vitade AF                           | 18        | 0.76%   |
| Lite-On HP HD Camera                                | 18        | 0.76%   |
| Microdia USB 2.0 Camera                             | 17        | 0.71%   |
| Chicony EasyCamera                                  | 17        | 0.71%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 17        | 0.71%   |
| Sunplus HD WebCam                                   | 16        | 0.67%   |
| Realtek Integrated Webcam HD                        | 15        | 0.63%   |
| Realtek Integrated Webcam                           | 15        | 0.63%   |
| Quanta HD User Facing                               | 15        | 0.63%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 15        | 0.63%   |
| Chicony USB2.0 VGA UVC WebCam                       | 15        | 0.63%   |
| Chicony HP TrueVision HD Camera                     | 15        | 0.63%   |
| Apple FaceTime HD Camera                            | 15        | 0.63%   |
| Quanta HP Wide Vision HD Camera                     | 14        | 0.59%   |
| Logitech HD Pro Webcam C920                         | 14        | 0.59%   |
| icSpring camera                                     | 14        | 0.59%   |
| Chicony VGA WebCam                                  | 14        | 0.59%   |
| Chicony Lenovo EasyCamera                           | 14        | 0.59%   |
| Chicony HP HD Camera                                | 14        | 0.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 158       | 40.72%  |
| Synaptics                          | 67        | 17.27%  |
| Shenzhen Goodix Technology         | 50        | 12.89%  |
| AuthenTec                          | 37        | 9.54%   |
| Upek                               | 24        | 6.19%   |
| Elan Microelectronics              | 22        | 5.67%   |
| LighTuning Technology              | 14        | 3.61%   |
| STMicroelectronics                 | 7         | 1.8%    |
| Samsung Electronics                | 3         | 0.77%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 0.77%   |
| Next Biometrics                    | 1         | 0.26%   |
| HOLTEK                             | 1         | 0.26%   |
| Focal-systems.Corp                 | 1         | 0.26%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 32        | 8.25%   |
| Shenzhen Goodix  Fingerprint Device                                        | 29        | 7.47%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 22        | 5.67%   |
| Shenzhen Goodix Fingerprint Reader                                         | 18        | 4.64%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 16        | 4.12%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 16        | 4.12%   |
| Validity Sensors VFS491                                                    | 15        | 3.87%   |
| Elan ELAN:ARM-M4                                                           | 15        | 3.87%   |
| Validity Sensors Fingerprint scanner                                       | 12        | 3.09%   |
| AuthenTec AES2810                                                          | 12        | 3.09%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 12        | 3.09%   |
| Validity Sensors Synaptics WBDI                                            | 11        | 2.84%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 10        | 2.58%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 10        | 2.58%   |
| Synaptics WBDI                                                             | 9         | 2.32%   |
| Synaptics UWP WBDI                                                         | 9         | 2.32%   |
| Synaptics  WBDI                                                            | 9         | 2.32%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 9         | 2.32%   |
| Synaptics Fingerprint reader [HP G6]                                       | 9         | 2.32%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 2.06%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 7         | 1.8%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 7         | 1.8%    |
| STMicroelectronics Fingerprint Reader                                      | 7         | 1.8%    |
| Elan ELAN:Fingerprint                                                      | 7         | 1.8%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 1.55%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 6         | 1.55%   |
| LighTuning Fingerprint Sensor                                              | 5         | 1.29%   |
| AuthenTec Fingerprint Sensor                                               | 5         | 1.29%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 1.03%   |
| Validity Sensors VFS Fingerprint sensor                                    | 4         | 1.03%   |
| AuthenTec AES1600                                                          | 4         | 1.03%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 0.77%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 0.77%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 0.77%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 3         | 0.77%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 0.52%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 0.52%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 0.52%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 0.52%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 0.52%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 82        | 50.93%  |
| Alcor Micro                       | 27        | 16.77%  |
| O2 Micro                          | 17        | 10.56%  |
| Upek                              | 7         | 4.35%   |
| Lenovo                            | 7         | 4.35%   |
| VASCO Data Security International | 3         | 1.86%   |
| SCM Microsystems                  | 3         | 1.86%   |
| Realtek Semiconductor             | 3         | 1.86%   |
| Yubico.com                        | 2         | 1.24%   |
| Gemalto (was Gemplus)             | 2         | 1.24%   |
| Fujitsu Siemens Computers         | 2         | 1.24%   |
| Advanced Card Systems             | 2         | 1.24%   |
| Reiner SCT Kartensysteme          | 1         | 0.62%   |
| OmniKey                           | 1         | 0.62%   |
| Jing-Mold Enterprise              | 1         | 0.62%   |
| Chicony Electronics               | 1         | 0.62%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 30        | 18.63%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 27        | 16.77%  |
| Broadcom 5880                                                                | 24        | 14.91%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 20        | 12.42%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 16        | 9.94%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 7         | 4.35%   |
| Lenovo Integrated Smart Card Reader                                          | 7         | 4.35%   |
| Broadcom 58200                                                               | 6         | 3.73%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 3         | 1.86%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 1.24%   |
| VASCO Data Security International DIGIPASS 870                               | 2         | 1.24%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 1.24%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 1.24%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 2         | 1.24%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 1.24%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.62%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.62%   |
| Reiner SCT Kartensysteme cyberJack e-com/pinpad                              | 1         | 0.62%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.62%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.62%   |
| Jing-Mold Enterprise HP USB Business Slim Smartcard CCID Keyboard            | 1         | 0.62%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.62%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.62%   |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 1         | 0.62%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2897      | 70.54%  |
| 1     | 975       | 23.74%  |
| 2     | 208       | 5.06%   |
| 3     | 24        | 0.58%   |
| 4     | 2         | 0.05%   |
| 8     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 382       | 26.86%  |
| Graphics card            | 301       | 21.17%  |
| Net/wireless             | 257       | 18.07%  |
| Multimedia controller    | 163       | 11.46%  |
| Chipcard                 | 149       | 10.48%  |
| Communication controller | 29        | 2.04%   |
| Bluetooth                | 29        | 2.04%   |
| Storage                  | 28        | 1.97%   |
| Sound                    | 14        | 0.98%   |
| Unassigned class         | 11        | 0.77%   |
| Camera                   | 10        | 0.7%    |
| Net/ethernet             | 8         | 0.56%   |
| Storage/raid             | 7         | 0.49%   |
| Modem                    | 7         | 0.49%   |
| Card reader              | 7         | 0.49%   |
| Network                  | 6         | 0.42%   |
| Dvb card                 | 5         | 0.35%   |
| Storage/ide              | 4         | 0.28%   |
| Storage/nvme             | 2         | 0.14%   |
| Flash memory             | 2         | 0.14%   |
| Unclassified device      | 1         | 0.07%   |

