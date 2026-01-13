Linux in Estonia - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Estonia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Estonia/Desktop/README.md) and [notebooks](/Location/Estonia/Notebook/README.md).

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

Total: 705

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | EliteBook 8460p             | Notebook    | [17cd1c1733](https://linux-hardware.org/?probe=17cd1c1733) | Dec 25, 2025 |
| ORIGIMAGIC    | ADB19D                      | Mini pc     | [f9b181c89d](https://linux-hardware.org/?probe=f9b181c89d) | Dec 22, 2025 |
| HP            | 8054                        | Desktop     | [4dd9ded903](https://linux-hardware.org/?probe=4dd9ded903) | Dec 18, 2025 |
| HP            | 8054                        | Desktop     | [3a036d008d](https://linux-hardware.org/?probe=3a036d008d) | Dec 18, 2025 |
| ASUSTek       | TUF Gaming B550M-E          | Desktop     | [df3602e76a](https://linux-hardware.org/?probe=df3602e76a) | Dec 17, 2025 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [ec7b63cebb](https://linux-hardware.org/?probe=ec7b63cebb) | Dec 15, 2025 |
| ASRock        | B550M Pro4                  | Desktop     | [1d5172aa80](https://linux-hardware.org/?probe=1d5172aa80) | Dec 13, 2025 |
| Gigabyte      | H410M H V2                  | Desktop     | [e6c5d99360](https://linux-hardware.org/?probe=e6c5d99360) | Dec 12, 2025 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [1a1e65db1a](https://linux-hardware.org/?probe=1a1e65db1a) | Dec 09, 2025 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [4bc887a2f1](https://linux-hardware.org/?probe=4bc887a2f1) | Dec 08, 2025 |
| Apple         | MacBookPro11,2              | Notebook    | [6aa16084f0](https://linux-hardware.org/?probe=6aa16084f0) | Dec 07, 2025 |
| Gigabyte      | A520I AC                    | Desktop     | [d77e425355](https://linux-hardware.org/?probe=d77e425355) | Dec 04, 2025 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [4cbef30a8f](https://linux-hardware.org/?probe=4cbef30a8f) | Dec 04, 2025 |
| Lenovo        | ThinkPad X230 2325SG2       | Notebook    | [38b00653b3](https://linux-hardware.org/?probe=38b00653b3) | Dec 04, 2025 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | Notebook    | [8310635b74](https://linux-hardware.org/?probe=8310635b74) | Dec 03, 2025 |
| Gigabyte      | X670 GAMING X AX            | Desktop     | [095ff236bd](https://linux-hardware.org/?probe=095ff236bd) | Dec 01, 2025 |
| Intel         | NUC7i5BNB J31144-309        | Mini pc     | [c86e56476e](https://linux-hardware.org/?probe=c86e56476e) | Dec 01, 2025 |
| MSI           | MPG X670E CARBON WIFI       | Desktop     | [5830707879](https://linux-hardware.org/?probe=5830707879) | Nov 30, 2025 |
| HP            | EliteBook Folio 1040 G2     | Notebook    | [cec6d02e50](https://linux-hardware.org/?probe=cec6d02e50) | Nov 29, 2025 |
| HP            | ProBook 640 G1              | Notebook    | [5d214afddf](https://linux-hardware.org/?probe=5d214afddf) | Nov 29, 2025 |
| HP            | Pavilion 15                 | Notebook    | [66f29bd82a](https://linux-hardware.org/?probe=66f29bd82a) | Nov 24, 2025 |
| Apple         | MacBook8,1                  | Notebook    | [8bc9d8aa99](https://linux-hardware.org/?probe=8bc9d8aa99) | Nov 24, 2025 |
| Apple         | MacBook8,1                  | Notebook    | [a334a69680](https://linux-hardware.org/?probe=a334a69680) | Nov 24, 2025 |
| Lenovo        | ThinkPad T430 2347HM4       | Notebook    | [09150691a8](https://linux-hardware.org/?probe=09150691a8) | Nov 22, 2025 |
| Unknown       | GB01                        | Desktop     | [286b0b27d8](https://linux-hardware.org/?probe=286b0b27d8) | Nov 08, 2025 |
| AZW           | SER V1.0                    | Mini pc     | [a6d1e64c81](https://linux-hardware.org/?probe=a6d1e64c81) | Nov 08, 2025 |
| HP            | 8056                        | Desktop     | [054501371a](https://linux-hardware.org/?probe=054501371a) | Nov 03, 2025 |
| MSI           | A520M-A PRO                 | Desktop     | [b6e8caa135](https://linux-hardware.org/?probe=b6e8caa135) | Nov 03, 2025 |
| ASRock        | B450 Steel Legend           | Desktop     | [6c9f79c082](https://linux-hardware.org/?probe=6c9f79c082) | Nov 02, 2025 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [64fccee2dc](https://linux-hardware.org/?probe=64fccee2dc) | Oct 31, 2025 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [f52148a8a2](https://linux-hardware.org/?probe=f52148a8a2) | Oct 31, 2025 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [45164b6ebb](https://linux-hardware.org/?probe=45164b6ebb) | Oct 31, 2025 |
| MSI           | H81M-E33 V2                 | Desktop     | [dae3d11df3](https://linux-hardware.org/?probe=dae3d11df3) | Oct 30, 2025 |
| HP            | 8917                        | Desktop     | [5286dacfd8](https://linux-hardware.org/?probe=5286dacfd8) | Oct 26, 2025 |
| ASRock        | B550M-HDV                   | Desktop     | [17ef857adf](https://linux-hardware.org/?probe=17ef857adf) | Oct 18, 2025 |
| Lenovo        | ThinkPad T480 20L50011US    | Notebook    | [b0d8e874d7](https://linux-hardware.org/?probe=b0d8e874d7) | Oct 14, 2025 |
| Gigabyte      | B650 EAGLE AX               | Desktop     | [90cd7a83f3](https://linux-hardware.org/?probe=90cd7a83f3) | Oct 14, 2025 |
| Lenovo        | LOQ 15ARP9 83JC             | Notebook    | [92a5998356](https://linux-hardware.org/?probe=92a5998356) | Oct 13, 2025 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [15e5fecee0](https://linux-hardware.org/?probe=15e5fecee0) | Oct 03, 2025 |
| Dell          | Inspiron 7737               | Notebook    | [2e2b0ce8da](https://linux-hardware.org/?probe=2e2b0ce8da) | Oct 01, 2025 |
| Dell          | Inspiron 7737               | Notebook    | [bbc74021e1](https://linux-hardware.org/?probe=bbc74021e1) | Oct 01, 2025 |
| Intel         | NUC8BEB J72693-307          | Mini pc     | [f628e203a1](https://linux-hardware.org/?probe=f628e203a1) | Oct 01, 2025 |
| ASUSTek       | ROG STRIX B850-I GAMING ... | Desktop     | [618f2e5fdf](https://linux-hardware.org/?probe=618f2e5fdf) | Sep 28, 2025 |
| MSI           | MAG B550 TORPEDO            | Desktop     | [a55e64dcc5](https://linux-hardware.org/?probe=a55e64dcc5) | Sep 28, 2025 |
| MSI           | MAG B550 TORPEDO            | Desktop     | [43fc490ac7](https://linux-hardware.org/?probe=43fc490ac7) | Sep 28, 2025 |
| Chuwi         | CoreBook X                  | Notebook    | [c8bb120e05](https://linux-hardware.org/?probe=c8bb120e05) | Sep 24, 2025 |
| Chuwi         | CoreBook X                  | Notebook    | [084cecffb5](https://linux-hardware.org/?probe=084cecffb5) | Sep 23, 2025 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [bf5d1fe87a](https://linux-hardware.org/?probe=bf5d1fe87a) | Sep 19, 2025 |
| Lenovo        | ThinkPad T14 Gen 5 21MMS... | Notebook    | [345a58a039](https://linux-hardware.org/?probe=345a58a039) | Sep 15, 2025 |
| Notebook      | N9x0TD_TF                   | Notebook    | [7281d4fccf](https://linux-hardware.org/?probe=7281d4fccf) | Sep 15, 2025 |
| Lenovo        | ThinkPad T14 Gen 5 21MMS... | Notebook    | [8d04cd4279](https://linux-hardware.org/?probe=8d04cd4279) | Sep 15, 2025 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [5e381a1979](https://linux-hardware.org/?probe=5e381a1979) | Sep 12, 2025 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [5eeec43c14](https://linux-hardware.org/?probe=5eeec43c14) | Sep 11, 2025 |
| ASRock        | X300M-STX                   | Desktop     | [ecf5edd56b](https://linux-hardware.org/?probe=ecf5edd56b) | Sep 11, 2025 |
| Dell          | Inspiron 15-3567            | Notebook    | [03d0038733](https://linux-hardware.org/?probe=03d0038733) | Sep 09, 2025 |
| ASRock        | X300M-STX                   | Desktop     | [d73a77ca97](https://linux-hardware.org/?probe=d73a77ca97) | Sep 07, 2025 |
| Lenovo        | ThinkPad X280 20KE003KMX    | Notebook    | [cadf220563](https://linux-hardware.org/?probe=cadf220563) | Sep 06, 2025 |
| Intel         | DH61CR AAG14064-208         | Desktop     | [29807f043c](https://linux-hardware.org/?probe=29807f043c) | Sep 06, 2025 |
| Gigabyte      | B360HD3                     | Desktop     | [6d09c0c78b](https://linux-hardware.org/?probe=6d09c0c78b) | Aug 15, 2025 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [fea21bc343](https://linux-hardware.org/?probe=fea21bc343) | Aug 10, 2025 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [b15b20f5fd](https://linux-hardware.org/?probe=b15b20f5fd) | Aug 10, 2025 |
| Lenovo        | ThinkPad T14 Gen 5 21MCS... | Notebook    | [69b4399293](https://linux-hardware.org/?probe=69b4399293) | Aug 07, 2025 |
| Lenovo        | ThinkPad T420 4236W9P       | Notebook    | [6c0a7ada9d](https://linux-hardware.org/?probe=6c0a7ada9d) | Aug 03, 2025 |
| Framework     | Laptop 16 (AMD Ryzen 704... | Notebook    | [62f44f6c6b](https://linux-hardware.org/?probe=62f44f6c6b) | Jul 29, 2025 |
| Framework     | Laptop 16 (AMD Ryzen 704... | Notebook    | [3f690161be](https://linux-hardware.org/?probe=3f690161be) | Jul 27, 2025 |
| Durabook      | R11I                        | Tablet      | [531e6b1248](https://linux-hardware.org/?probe=531e6b1248) | Jul 23, 2025 |
| Dell          | Latitude 5490               | Notebook    | [188dd223da](https://linux-hardware.org/?probe=188dd223da) | Jul 22, 2025 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [e11c75dc55](https://linux-hardware.org/?probe=e11c75dc55) | Jul 18, 2025 |
| ASUSTek       | ASUS Zenbook S 16 UM5606... | Notebook    | [2ab3e26358](https://linux-hardware.org/?probe=2ab3e26358) | Jul 14, 2025 |
| Lenovo        | ThinkPad W530 2436CTO       | Notebook    | [109e3b0a4b](https://linux-hardware.org/?probe=109e3b0a4b) | Jul 14, 2025 |
| ASUSTek       | ASUS Zenbook S 16 UM5606... | Notebook    | [927261893b](https://linux-hardware.org/?probe=927261893b) | Jul 14, 2025 |
| Intel         | NUC8BEB J72693-304          | Mini pc     | [6edaa52472](https://linux-hardware.org/?probe=6edaa52472) | Jul 11, 2025 |
| Dell          | Latitude 7420               | Notebook    | [1d1f41c660](https://linux-hardware.org/?probe=1d1f41c660) | Jul 11, 2025 |
| Dell          | Latitude 7420               | Notebook    | [a45d25c768](https://linux-hardware.org/?probe=a45d25c768) | Jul 11, 2025 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [43b778a1d6](https://linux-hardware.org/?probe=43b778a1d6) | Jul 01, 2025 |
| Apple         | MacBookPro5,4               | Notebook    | [380af89a75](https://linux-hardware.org/?probe=380af89a75) | Jun 23, 2025 |
| Gigabyte      | B760M AORUS ELITE AX        | Desktop     | [5d818f8619](https://linux-hardware.org/?probe=5d818f8619) | Jun 22, 2025 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [b59e1e98fe](https://linux-hardware.org/?probe=b59e1e98fe) | Jun 20, 2025 |
| Raspberry ... | Raspberry Pi Zero 2 W Re... | Soc         | [9113e5aedd](https://linux-hardware.org/?probe=9113e5aedd) | Jun 17, 2025 |
| ASRock        | X470 Taichi                 | Desktop     | [e0f9e1a639](https://linux-hardware.org/?probe=e0f9e1a639) | Jun 10, 2025 |
| Gigabyte      | GA-A55-DS3P                 | Desktop     | [92a3ebcf80](https://linux-hardware.org/?probe=92a3ebcf80) | Jun 06, 2025 |
| HP            | EliteBook 850 G6            | Notebook    | [2f0fd20ed5](https://linux-hardware.org/?probe=2f0fd20ed5) | May 31, 2025 |
| HP            | EliteBook 850 G6            | Notebook    | [4bc436ca7a](https://linux-hardware.org/?probe=4bc436ca7a) | May 31, 2025 |
| Lenovo        | ThinkPad Edge 022138G       | Notebook    | [4a0bff5124](https://linux-hardware.org/?probe=4a0bff5124) | May 29, 2025 |
| Lenovo        | ThinkPad T14s Gen 6 21M1... | Notebook    | [134387e9b6](https://linux-hardware.org/?probe=134387e9b6) | May 26, 2025 |
| Bananapi      | BPI-R2                      | Soc         | [846e4cab6c](https://linux-hardware.org/?probe=846e4cab6c) | May 23, 2025 |
| Bananapi      | BPI-R2                      | Soc         | [68dedc3ed7](https://linux-hardware.org/?probe=68dedc3ed7) | May 23, 2025 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [b58e0e68b4](https://linux-hardware.org/?probe=b58e0e68b4) | May 16, 2025 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [f090c9b6a6](https://linux-hardware.org/?probe=f090c9b6a6) | May 16, 2025 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [8d802b57fb](https://linux-hardware.org/?probe=8d802b57fb) | May 15, 2025 |
| ASRock        | X300M-STX                   | Desktop     | [9db19f1ced](https://linux-hardware.org/?probe=9db19f1ced) | May 15, 2025 |
| Notebook      | N9x0TD_TF                   | Notebook    | [fd4e0c03f7](https://linux-hardware.org/?probe=fd4e0c03f7) | Apr 24, 2025 |
| Notebook      | N9x0TD_TF                   | Notebook    | [c10fb115aa](https://linux-hardware.org/?probe=c10fb115aa) | Apr 22, 2025 |
| HP            | Elite Dragonfly 13.5 inc... | Notebook    | [57c675dad5](https://linux-hardware.org/?probe=57c675dad5) | Apr 12, 2025 |
| Dell          | Vostro 3700                 | Notebook    | [fa66ce1fa7](https://linux-hardware.org/?probe=fa66ce1fa7) | Apr 05, 2025 |
| Lenovo        | ThinkPad T14s Gen 6 21M1... | Notebook    | [fbda73a703](https://linux-hardware.org/?probe=fbda73a703) | Apr 01, 2025 |
| Apple         | MacBookAir7,2               | Notebook    | [241c2d8a5c](https://linux-hardware.org/?probe=241c2d8a5c) | Mar 31, 2025 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [3d8294c0a4](https://linux-hardware.org/?probe=3d8294c0a4) | Mar 28, 2025 |
| HP            | ZBook 17 G3                 | Notebook    | [c90d04b1e8](https://linux-hardware.org/?probe=c90d04b1e8) | Mar 28, 2025 |
| Dell          | Latitude 7490               | Notebook    | [e3d46aa669](https://linux-hardware.org/?probe=e3d46aa669) | Mar 24, 2025 |
| GPD           | G1619-04                    | Notebook    | [c52627c2de](https://linux-hardware.org/?probe=c52627c2de) | Mar 21, 2025 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [f6485a2930](https://linux-hardware.org/?probe=f6485a2930) | Mar 17, 2025 |
| Dell          | Latitude 7280               | Notebook    | [9378675ecb](https://linux-hardware.org/?probe=9378675ecb) | Mar 17, 2025 |
| Lenovo        | V330-14IKB 81B0             | Notebook    | [a1af0b781e](https://linux-hardware.org/?probe=a1af0b781e) | Mar 13, 2025 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [4a41b757f6](https://linux-hardware.org/?probe=4a41b757f6) | Mar 13, 2025 |
| Dell          | Latitude 7640               | Notebook    | [abd6719d67](https://linux-hardware.org/?probe=abd6719d67) | Mar 06, 2025 |
| Notebook      | N9x0TD_TF                   | Notebook    | [902efa63b3](https://linux-hardware.org/?probe=902efa63b3) | Mar 04, 2025 |
| Notebook      | N9x0TD_TF                   | Notebook    | [ef4ee4970c](https://linux-hardware.org/?probe=ef4ee4970c) | Mar 03, 2025 |
| Lenovo        | ThinkPad T14s Gen 6 21M1... | Notebook    | [c9cd04c99a](https://linux-hardware.org/?probe=c9cd04c99a) | Mar 02, 2025 |
| Lenovo        | ThinkPad T14s Gen 6 21M1... | Notebook    | [a4c826ce08](https://linux-hardware.org/?probe=a4c826ce08) | Mar 02, 2025 |
| Dell          | XPS 15 9570                 | Notebook    | [f913fd0139](https://linux-hardware.org/?probe=f913fd0139) | Feb 24, 2025 |
| Dell          | Latitude 7640               | Notebook    | [ad3ce4d65c](https://linux-hardware.org/?probe=ad3ce4d65c) | Feb 23, 2025 |
| GPD           | G1619-04                    | Notebook    | [5328fd045b](https://linux-hardware.org/?probe=5328fd045b) | Feb 18, 2025 |
| ASRock        | X300M-STX                   | Desktop     | [2c7f0f1a03](https://linux-hardware.org/?probe=2c7f0f1a03) | Feb 18, 2025 |
| ASRock        | X300M-STX                   | Desktop     | [e1a56f4904](https://linux-hardware.org/?probe=e1a56f4904) | Feb 16, 2025 |
| Samsung       | 905S3G/906S3G/915S3G        | Notebook    | [cdfe8ff639](https://linux-hardware.org/?probe=cdfe8ff639) | Feb 15, 2025 |
| Dell          | Precision M6700             | Notebook    | [11f8956de8](https://linux-hardware.org/?probe=11f8956de8) | Feb 13, 2025 |
| Lenovo        | ThinkPad P70 20ER000EMS     | Notebook    | [21552aaa9a](https://linux-hardware.org/?probe=21552aaa9a) | Feb 08, 2025 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [4432213b4b](https://linux-hardware.org/?probe=4432213b4b) | Feb 08, 2025 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [8761ae5ace](https://linux-hardware.org/?probe=8761ae5ace) | Feb 04, 2025 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [11555b90a6](https://linux-hardware.org/?probe=11555b90a6) | Jan 25, 2025 |
| Acer          | Aspire 5750ZG               | Notebook    | [b55d95dc40](https://linux-hardware.org/?probe=b55d95dc40) | Jan 23, 2025 |
| Acer          | Aspire 5750ZG               | Notebook    | [fa9b739c95](https://linux-hardware.org/?probe=fa9b739c95) | Jan 23, 2025 |
| Lenovo        | ThinkPad T500 2056VPG       | Notebook    | [8ee528a59e](https://linux-hardware.org/?probe=8ee528a59e) | Jan 16, 2025 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [04d8b45864](https://linux-hardware.org/?probe=04d8b45864) | Jan 16, 2025 |
| MSI           | B760 GAMING PLUS WIFI       | Desktop     | [6f0df5310a](https://linux-hardware.org/?probe=6f0df5310a) | Jan 14, 2025 |
| Dell          | Latitude 7640               | Notebook    | [f7e928b28a](https://linux-hardware.org/?probe=f7e928b28a) | Jan 14, 2025 |
| Dell          | Latitude 3340               | Notebook    | [83ea4fad0a](https://linux-hardware.org/?probe=83ea4fad0a) | Jan 13, 2025 |
| Dell          | Latitude 7640               | Notebook    | [6d1fd722cb](https://linux-hardware.org/?probe=6d1fd722cb) | Jan 13, 2025 |
| Fujitsu       | D3171-A1 S26361-D3171-A1    | Desktop     | [9167e2df37](https://linux-hardware.org/?probe=9167e2df37) | Jan 08, 2025 |
| HP            | EliteBook 8470p             | Notebook    | [7a5df9412c](https://linux-hardware.org/?probe=7a5df9412c) | Dec 31, 2024 |
| Dell          | Latitude 7640               | Notebook    | [931523acc9](https://linux-hardware.org/?probe=931523acc9) | Dec 28, 2024 |
| Intel         | HM570                       | Desktop     | [74847a808d](https://linux-hardware.org/?probe=74847a808d) | Dec 21, 2024 |
| MSI           | MEG Z490I UNIFY             | Desktop     | [34567a9026](https://linux-hardware.org/?probe=34567a9026) | Dec 20, 2024 |
| Dell          | System XPS 15Z              | Notebook    | [9e7fc2d36e](https://linux-hardware.org/?probe=9e7fc2d36e) | Dec 20, 2024 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [c511952a11](https://linux-hardware.org/?probe=c511952a11) | Dec 19, 2024 |
| Lenovo        | ThinkPad T60 1951FDG        | Notebook    | [9c3c2fb92b](https://linux-hardware.org/?probe=9c3c2fb92b) | Dec 13, 2024 |
| ASUSTek       | ASUS Vivobook S 16 M5606... | Notebook    | [b3ea15c92e](https://linux-hardware.org/?probe=b3ea15c92e) | Dec 12, 2024 |
| Supermicro    | H13SAE-MF                   | Server      | [cab997495e](https://linux-hardware.org/?probe=cab997495e) | Dec 11, 2024 |
| MACHINIST     | E5-RS9 V1.1                 | Desktop     | [9f5f41fa91](https://linux-hardware.org/?probe=9f5f41fa91) | Dec 07, 2024 |
| Lenovo        | ThinkPad T460s 20F9003RM... | Notebook    | [5092bec86b](https://linux-hardware.org/?probe=5092bec86b) | Dec 07, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [e51903f612](https://linux-hardware.org/?probe=e51903f612) | Dec 05, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [4e0782715d](https://linux-hardware.org/?probe=4e0782715d) | Dec 02, 2024 |
| HP            | Laptop 15-db0xxx            | Notebook    | [469069638e](https://linux-hardware.org/?probe=469069638e) | Dec 01, 2024 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [458a67a9e4](https://linux-hardware.org/?probe=458a67a9e4) | Nov 30, 2024 |
| HP            | EliteBook 8470p             | Notebook    | [f03062334f](https://linux-hardware.org/?probe=f03062334f) | Nov 29, 2024 |
| Dell          | XPS 13 9310                 | Notebook    | [5a464dff99](https://linux-hardware.org/?probe=5a464dff99) | Nov 27, 2024 |
| Toshiba       | Satellite L870-120          | Notebook    | [44263921b6](https://linux-hardware.org/?probe=44263921b6) | Nov 26, 2024 |
| Lenovo        | ThinkStation D20 4158GK1    | Desktop     | [8af2b2f494](https://linux-hardware.org/?probe=8af2b2f494) | Nov 24, 2024 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [ac01b2a1d7](https://linux-hardware.org/?probe=ac01b2a1d7) | Nov 19, 2024 |
| Lenovo        | ThinkPad T14 Gen 5 21MCS... | Notebook    | [2d30a85677](https://linux-hardware.org/?probe=2d30a85677) | Nov 18, 2024 |
| Lenovo        | ThinkPad X240 20AMA0W706    | Notebook    | [ccf9df80ca](https://linux-hardware.org/?probe=ccf9df80ca) | Nov 11, 2024 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | Notebook    | [7b749bf585](https://linux-hardware.org/?probe=7b749bf585) | Nov 11, 2024 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [6dda519942](https://linux-hardware.org/?probe=6dda519942) | Nov 07, 2024 |
| Dell          | Latitude 7640               | Notebook    | [f092c8cc9f](https://linux-hardware.org/?probe=f092c8cc9f) | Oct 27, 2024 |
| Lenovo        | ThinkPad T420 4236W9P       | Notebook    | [25a5b7315a](https://linux-hardware.org/?probe=25a5b7315a) | Oct 21, 2024 |
| HP            | Compaq 6910p                | Notebook    | [2d33276514](https://linux-hardware.org/?probe=2d33276514) | Oct 17, 2024 |
| Lenovo        | ThinkPad T420 4236W9P       | Notebook    | [676dd2d194](https://linux-hardware.org/?probe=676dd2d194) | Oct 14, 2024 |
| Lenovo        | ThinkPad E14 Gen 5 21JR0... | Notebook    | [ec688a0cae](https://linux-hardware.org/?probe=ec688a0cae) | Oct 13, 2024 |
| Dell          | XPS L322X                   | Notebook    | [ebe83a8923](https://linux-hardware.org/?probe=ebe83a8923) | Oct 07, 2024 |
| Lenovo        | ThinkPad T420 4236W9P       | Notebook    | [d55aedf9d2](https://linux-hardware.org/?probe=d55aedf9d2) | Oct 06, 2024 |
| HP            | Laptop 14s-dq3xxx           | Notebook    | [e93a1db49f](https://linux-hardware.org/?probe=e93a1db49f) | Oct 06, 2024 |
| Intel         | JSL MRD                     | Desktop     | [8ccee12f0f](https://linux-hardware.org/?probe=8ccee12f0f) | Oct 02, 2024 |
| MSI           | PRO B550M-P GEN3            | Desktop     | [29d2b26873](https://linux-hardware.org/?probe=29d2b26873) | Sep 30, 2024 |
| Intel         | DH61CR AAG14064-208         | Desktop     | [10e7fcebd5](https://linux-hardware.org/?probe=10e7fcebd5) | Sep 28, 2024 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [76e2b2a322](https://linux-hardware.org/?probe=76e2b2a322) | Sep 22, 2024 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [a8bb2af7ad](https://linux-hardware.org/?probe=a8bb2af7ad) | Sep 20, 2024 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [6f566682d4](https://linux-hardware.org/?probe=6f566682d4) | Sep 19, 2024 |
| HP            | EliteBook 835 G8 Noteboo... | Notebook    | [7b97957b7a](https://linux-hardware.org/?probe=7b97957b7a) | Sep 10, 2024 |
| HP            | Laptop 14s-dq3xxx           | Notebook    | [c107b751c7](https://linux-hardware.org/?probe=c107b751c7) | Sep 03, 2024 |
| MSI           | B75MA-P45                   | Desktop     | [177c4ba401](https://linux-hardware.org/?probe=177c4ba401) | Sep 01, 2024 |
| HP            | Laptop 14s-dq3xxx           | Notebook    | [d05b98ac9f](https://linux-hardware.org/?probe=d05b98ac9f) | Sep 01, 2024 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [14e3740dda](https://linux-hardware.org/?probe=14e3740dda) | Aug 22, 2024 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [04fbf91f84](https://linux-hardware.org/?probe=04fbf91f84) | Aug 22, 2024 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [0bfe4993d8](https://linux-hardware.org/?probe=0bfe4993d8) | Aug 22, 2024 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [83343a4a26](https://linux-hardware.org/?probe=83343a4a26) | Aug 07, 2024 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [b3dd1179a9](https://linux-hardware.org/?probe=b3dd1179a9) | Aug 05, 2024 |
| Dell          | Latitude 3340               | Notebook    | [533fe2ea9d](https://linux-hardware.org/?probe=533fe2ea9d) | Aug 04, 2024 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [c3feea4b6d](https://linux-hardware.org/?probe=c3feea4b6d) | Aug 03, 2024 |
| Dell          | XPS L322X                   | Notebook    | [8b14979f7c](https://linux-hardware.org/?probe=8b14979f7c) | Jul 30, 2024 |
| Dell          | XPS L322X                   | Notebook    | [bf4c97865c](https://linux-hardware.org/?probe=bf4c97865c) | Jul 30, 2024 |
| Dell          | Latitude E7450              | Notebook    | [ba9d36e59d](https://linux-hardware.org/?probe=ba9d36e59d) | Jul 25, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [4f3c1e544b](https://linux-hardware.org/?probe=4f3c1e544b) | Jul 15, 2024 |
| Valve         | Jupiter                     | Notebook    | [c83514f0ef](https://linux-hardware.org/?probe=c83514f0ef) | Jul 13, 2024 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [8bc58488a8](https://linux-hardware.org/?probe=8bc58488a8) | Jul 09, 2024 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [0050e9851f](https://linux-hardware.org/?probe=0050e9851f) | Jul 08, 2024 |
| Acer          | Aspire 5755G                | Notebook    | [9d85820d8a](https://linux-hardware.org/?probe=9d85820d8a) | Jul 06, 2024 |
| Lenovo        | 3130 SDK0J40697 WIN 3305... | Mini pc     | [b5dfce71c0](https://linux-hardware.org/?probe=b5dfce71c0) | Jul 06, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [8046341f97](https://linux-hardware.org/?probe=8046341f97) | Jul 04, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [a4411a1a03](https://linux-hardware.org/?probe=a4411a1a03) | Jul 03, 2024 |
| Notebook      | PE60RNE_RND_RNC             | Notebook    | [82b61a10fa](https://linux-hardware.org/?probe=82b61a10fa) | Jul 03, 2024 |
| Valve         | Jupiter                     | Notebook    | [64bd09dae7](https://linux-hardware.org/?probe=64bd09dae7) | Jul 02, 2024 |
| Lenovo        | ThinkPad T470 20HES00300    | Notebook    | [a311daa558](https://linux-hardware.org/?probe=a311daa558) | Jul 01, 2024 |
| Lenovo        | ThinkPad T470 20HES00300    | Notebook    | [8df67624a1](https://linux-hardware.org/?probe=8df67624a1) | Jul 01, 2024 |
| ASRock        | B460 Steel Legend           | Desktop     | [937d1eb881](https://linux-hardware.org/?probe=937d1eb881) | Jul 01, 2024 |
| Valve         | Jupiter                     | Notebook    | [7cb4543c27](https://linux-hardware.org/?probe=7cb4543c27) | Jun 30, 2024 |
| Dell          | Latitude 5431               | Notebook    | [b945bd0e46](https://linux-hardware.org/?probe=b945bd0e46) | Jun 21, 2024 |
| Dell          | XPS L322X                   | Notebook    | [1af333c86d](https://linux-hardware.org/?probe=1af333c86d) | Jun 18, 2024 |
| Dell          | XPS L322X                   | Notebook    | [34bcf0a790](https://linux-hardware.org/?probe=34bcf0a790) | Jun 18, 2024 |
| Dell          | Latitude 5431               | Notebook    | [7469c5f44a](https://linux-hardware.org/?probe=7469c5f44a) | Jun 17, 2024 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [161e412652](https://linux-hardware.org/?probe=161e412652) | Jun 09, 2024 |
| Acer          | Aspire A315-24P             | Notebook    | [f265233665](https://linux-hardware.org/?probe=f265233665) | Jun 05, 2024 |
| Lenovo        | Yoga Pro 7 14IRH8 82Y7      | Notebook    | [8534f873cf](https://linux-hardware.org/?probe=8534f873cf) | May 24, 2024 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [548c48e57a](https://linux-hardware.org/?probe=548c48e57a) | May 21, 2024 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [fbc31b1a58](https://linux-hardware.org/?probe=fbc31b1a58) | May 19, 2024 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [8818119aed](https://linux-hardware.org/?probe=8818119aed) | May 16, 2024 |
| Dell          | XPS 13 9360                 | Notebook    | [536f8ed319](https://linux-hardware.org/?probe=536f8ed319) | May 09, 2024 |
| Lenovo        | ThinkPad X240 20AMA0W706    | Notebook    | [ed0902f81c](https://linux-hardware.org/?probe=ed0902f81c) | May 08, 2024 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [2dee9df53a](https://linux-hardware.org/?probe=2dee9df53a) | May 02, 2024 |
| Dell          | Latitude 3300               | Notebook    | [639fb8097f](https://linux-hardware.org/?probe=639fb8097f) | May 02, 2024 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | Notebook    | [eefd534cd5](https://linux-hardware.org/?probe=eefd534cd5) | May 01, 2024 |
| Acer          | Extensa 5620                | Notebook    | [4150199b68](https://linux-hardware.org/?probe=4150199b68) | Apr 29, 2024 |
| Lenovo        | LOQ 15APH8 82XT             | Notebook    | [fad4840965](https://linux-hardware.org/?probe=fad4840965) | Apr 26, 2024 |
| Lenovo        | ThinkPad P43s 20RH0021MX    | Notebook    | [01d705d92b](https://linux-hardware.org/?probe=01d705d92b) | Apr 25, 2024 |
| Apple         | MacBookPro5,3               | Notebook    | [4661f5b412](https://linux-hardware.org/?probe=4661f5b412) | Apr 08, 2024 |
| Gigabyte      | H81M-S                      | Desktop     | [d18c354852](https://linux-hardware.org/?probe=d18c354852) | Mar 31, 2024 |
| Lenovo        | ThinkPad T490s 20NX006HM... | Notebook    | [52e2e29f44](https://linux-hardware.org/?probe=52e2e29f44) | Mar 22, 2024 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [d13f0a354c](https://linux-hardware.org/?probe=d13f0a354c) | Mar 21, 2024 |
| Dell          | Inspiron 5558               | Notebook    | [2202cb6328](https://linux-hardware.org/?probe=2202cb6328) | Mar 21, 2024 |
| Intel         | DB85FL AAG89861-201         | Desktop     | [15f1dac527](https://linux-hardware.org/?probe=15f1dac527) | Mar 21, 2024 |
| HP            | 650                         | Notebook    | [d58bfc527e](https://linux-hardware.org/?probe=d58bfc527e) | Mar 17, 2024 |
| ASRock        | H310M-HDV                   | Desktop     | [4e2f714f49](https://linux-hardware.org/?probe=4e2f714f49) | Mar 16, 2024 |
| ASRock        | H310M-HDV                   | Desktop     | [8d62cae785](https://linux-hardware.org/?probe=8d62cae785) | Mar 15, 2024 |
| MSI           | B85M-G43                    | Desktop     | [c1b1061c0d](https://linux-hardware.org/?probe=c1b1061c0d) | Mar 14, 2024 |
| Lenovo        | ThinkPad P50 20EN0007MS     | Notebook    | [8c9bcaf098](https://linux-hardware.org/?probe=8c9bcaf098) | Mar 14, 2024 |
| HP            | EliteBook 840 G5            | Notebook    | [16dee4c095](https://linux-hardware.org/?probe=16dee4c095) | Mar 13, 2024 |
| Dell          | Latitude 5420 Rugged        | Notebook    | [f9c7c915c9](https://linux-hardware.org/?probe=f9c7c915c9) | Mar 08, 2024 |
| Lenovo        | ThinkPad T470 20HDS01L00    | Notebook    | [d3de9797e5](https://linux-hardware.org/?probe=d3de9797e5) | Mar 07, 2024 |
| Lenovo        | ThinkPad T470 20HDS01L00    | Notebook    | [48c9ed444c](https://linux-hardware.org/?probe=48c9ed444c) | Mar 06, 2024 |
| Lenovo        | ThinkPad T480s 20L8002UM... | Notebook    | [a8c23be08a](https://linux-hardware.org/?probe=a8c23be08a) | Mar 05, 2024 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [66295fb0e8](https://linux-hardware.org/?probe=66295fb0e8) | Mar 04, 2024 |
| Gigabyte      | X570S AORUS PRO AX          | Desktop     | [9dbfe4a6eb](https://linux-hardware.org/?probe=9dbfe4a6eb) | Mar 04, 2024 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [c2b5dc013f](https://linux-hardware.org/?probe=c2b5dc013f) | Mar 03, 2024 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [7c8e1659f2](https://linux-hardware.org/?probe=7c8e1659f2) | Feb 24, 2024 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [b1c2e786ed](https://linux-hardware.org/?probe=b1c2e786ed) | Feb 17, 2024 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [0ea90e3ee0](https://linux-hardware.org/?probe=0ea90e3ee0) | Feb 17, 2024 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [50746a2234](https://linux-hardware.org/?probe=50746a2234) | Feb 09, 2024 |
| MSI           | X570-A PRO                  | Desktop     | [779b399243](https://linux-hardware.org/?probe=779b399243) | Feb 09, 2024 |
| Lenovo        | Yoga Pro 7 14APH8 82Y8      | Notebook    | [07deb1efe3](https://linux-hardware.org/?probe=07deb1efe3) | Feb 04, 2024 |
| Valve         | Jupiter                     | Notebook    | [ff59f7877a](https://linux-hardware.org/?probe=ff59f7877a) | Feb 02, 2024 |
| Dell          | Latitude 7490               | Notebook    | [d2085f3674](https://linux-hardware.org/?probe=d2085f3674) | Jan 24, 2024 |
| Dell          | Inspiron N5010              | Notebook    | [ab07a9741b](https://linux-hardware.org/?probe=ab07a9741b) | Jan 13, 2024 |
| MSI           | Pulse GL66 11UDK            | Notebook    | [fdb748bed5](https://linux-hardware.org/?probe=fdb748bed5) | Jan 13, 2024 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [7536a68c05](https://linux-hardware.org/?probe=7536a68c05) | Jan 06, 2024 |
| Dell          | Inspiron N5010              | Notebook    | [8991ffeadc](https://linux-hardware.org/?probe=8991ffeadc) | Jan 04, 2024 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [0863d91cdc](https://linux-hardware.org/?probe=0863d91cdc) | Dec 25, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [c1069bda0b](https://linux-hardware.org/?probe=c1069bda0b) | Dec 23, 2023 |
| Acer          | Nitro AN517-55              | Notebook    | [f3e3de235b](https://linux-hardware.org/?probe=f3e3de235b) | Dec 23, 2023 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [e222a97c0b](https://linux-hardware.org/?probe=e222a97c0b) | Dec 21, 2023 |
| HP            | ProBook 6570b               | Notebook    | [7dbd0f9be1](https://linux-hardware.org/?probe=7dbd0f9be1) | Dec 21, 2023 |
| HP            | ProBook 6570b               | Notebook    | [7a4a6018b6](https://linux-hardware.org/?probe=7a4a6018b6) | Dec 21, 2023 |
| TUXEDO        | Polaris AMD Gen5            | Notebook    | [84a93dbb91](https://linux-hardware.org/?probe=84a93dbb91) | Dec 19, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [646c403e2f](https://linux-hardware.org/?probe=646c403e2f) | Dec 16, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [7fc71d8954](https://linux-hardware.org/?probe=7fc71d8954) | Dec 16, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [9c4f708056](https://linux-hardware.org/?probe=9c4f708056) | Dec 10, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [62734db5de](https://linux-hardware.org/?probe=62734db5de) | Dec 10, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [be768fb273](https://linux-hardware.org/?probe=be768fb273) | Dec 06, 2023 |
| HP            | 8619                        | Desktop     | [a33e273f33](https://linux-hardware.org/?probe=a33e273f33) | Dec 04, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [bb0ded92ef](https://linux-hardware.org/?probe=bb0ded92ef) | Dec 03, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [a1ab0858a6](https://linux-hardware.org/?probe=a1ab0858a6) | Dec 01, 2023 |
| HP            | ProBook 4530s               | Notebook    | [5743a3e441](https://linux-hardware.org/?probe=5743a3e441) | Nov 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [78e9bae926](https://linux-hardware.org/?probe=78e9bae926) | Nov 26, 2023 |
| Dell          | Precision M4600             | Notebook    | [864f0c5cfe](https://linux-hardware.org/?probe=864f0c5cfe) | Nov 22, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [2ab108f743](https://linux-hardware.org/?probe=2ab108f743) | Nov 22, 2023 |
| Dell          | Precision M4600             | Notebook    | [af124219eb](https://linux-hardware.org/?probe=af124219eb) | Nov 18, 2023 |
| Acer          | Predator PH317-53           | Notebook    | [84650e7d6f](https://linux-hardware.org/?probe=84650e7d6f) | Nov 15, 2023 |
| Intel         | DH61DL AAG14066-205         | Desktop     | [be33944c69](https://linux-hardware.org/?probe=be33944c69) | Nov 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 4 21HDC... | Notebook    | [0d9316dbcf](https://linux-hardware.org/?probe=0d9316dbcf) | Oct 31, 2023 |
| ECS           | H61H2-M12                   | Desktop     | [885cbf522c](https://linux-hardware.org/?probe=885cbf522c) | Oct 28, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [bc710e10c6](https://linux-hardware.org/?probe=bc710e10c6) | Oct 27, 2023 |
| Lenovo        | YB1-X91L                    | Convertible | [235eadfef8](https://linux-hardware.org/?probe=235eadfef8) | Oct 18, 2023 |
| Lenovo        | YB1-X91L                    | Convertible | [42b86ea4ec](https://linux-hardware.org/?probe=42b86ea4ec) | Oct 18, 2023 |
| MSI           | PRO B660-A DDR4             | Desktop     | [506accae39](https://linux-hardware.org/?probe=506accae39) | Oct 16, 2023 |
| Lenovo        | ThinkPad T440p 20AWS49Q0... | Notebook    | [65fa77246e](https://linux-hardware.org/?probe=65fa77246e) | Sep 21, 2023 |
| Dell          | Latitude E5550              | Notebook    | [9044f3b345](https://linux-hardware.org/?probe=9044f3b345) | Sep 12, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [773143cf61](https://linux-hardware.org/?probe=773143cf61) | Sep 01, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BV0... | Notebook    | [3d7ba31c2a](https://linux-hardware.org/?probe=3d7ba31c2a) | Aug 24, 2023 |
| Lenovo        | ThinkPad P50 20EQS4XN00     | Notebook    | [a517cc57b8](https://linux-hardware.org/?probe=a517cc57b8) | Aug 23, 2023 |
| Lenovo        | ThinkPad T490 20N3S79M38    | Notebook    | [cb5346a558](https://linux-hardware.org/?probe=cb5346a558) | Aug 17, 2023 |
| Lenovo        | ThinkPad T490 20N3S79M38    | Notebook    | [4bfb2c68ca](https://linux-hardware.org/?probe=4bfb2c68ca) | Aug 17, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [d78e4ab87d](https://linux-hardware.org/?probe=d78e4ab87d) | Aug 08, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [482b97d3de](https://linux-hardware.org/?probe=482b97d3de) | Aug 02, 2023 |
| Dell          | Vostro 3700                 | Notebook    | [96e4579b7b](https://linux-hardware.org/?probe=96e4579b7b) | Aug 01, 2023 |
| Intel         | powered classmate PC        | Notebook    | [ccbb0cb45a](https://linux-hardware.org/?probe=ccbb0cb45a) | Jul 24, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [00bda81c25](https://linux-hardware.org/?probe=00bda81c25) | Jul 19, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [8c2fd03132](https://linux-hardware.org/?probe=8c2fd03132) | Jul 06, 2023 |
| ASUSTek       | PRIME Z790M-PLUS            | Desktop     | [ea7090722f](https://linux-hardware.org/?probe=ea7090722f) | Jun 22, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [961a04643c](https://linux-hardware.org/?probe=961a04643c) | May 25, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [a38171543f](https://linux-hardware.org/?probe=a38171543f) | May 24, 2023 |
| Microsoft     | Surface Book                | Tablet      | [7bb9611a98](https://linux-hardware.org/?probe=7bb9611a98) | May 21, 2023 |
| Lenovo        | ThinkPad L480 20LTSAK70R    | Notebook    | [551d238ad3](https://linux-hardware.org/?probe=551d238ad3) | May 16, 2023 |
| Notebook      | N150SD/N155SD               | Notebook    | [55f219bc3f](https://linux-hardware.org/?probe=55f219bc3f) | May 11, 2023 |
| ASUSTek       | N550JK                      | Notebook    | [a799667521](https://linux-hardware.org/?probe=a799667521) | May 04, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [fdaef83d1e](https://linux-hardware.org/?probe=fdaef83d1e) | Apr 23, 2023 |
| Lenovo        | ThinkStation D20 4158GK1    | Desktop     | [44d9536051](https://linux-hardware.org/?probe=44d9536051) | Apr 14, 2023 |
| MSI           | GF63 Thin 10SCXR            | Notebook    | [33e5d369a7](https://linux-hardware.org/?probe=33e5d369a7) | Apr 04, 2023 |
| HP            | 304Ah                       | Desktop     | [14d92e85a2](https://linux-hardware.org/?probe=14d92e85a2) | Apr 01, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [6694c9279d](https://linux-hardware.org/?probe=6694c9279d) | Mar 31, 2023 |
| Apple         | MacBookPro5,1               | Notebook    | [b06257fd9c](https://linux-hardware.org/?probe=b06257fd9c) | Mar 28, 2023 |
| Apple         | MacBookPro5,1               | Notebook    | [3a0d77d195](https://linux-hardware.org/?probe=3a0d77d195) | Mar 28, 2023 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [6b088adaf9](https://linux-hardware.org/?probe=6b088adaf9) | Mar 27, 2023 |
| Gigabyte      | G5 KD                       | Notebook    | [32afc6a4cf](https://linux-hardware.org/?probe=32afc6a4cf) | Mar 23, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [4efbf8be88](https://linux-hardware.org/?probe=4efbf8be88) | Mar 23, 2023 |
| ASRock        | B660M-ITX/ac                | Desktop     | [95687a223c](https://linux-hardware.org/?probe=95687a223c) | Mar 22, 2023 |
| GPD           | G1619-04                    | Notebook    | [c69bb703ae](https://linux-hardware.org/?probe=c69bb703ae) | Mar 21, 2023 |
| HP            | 304Ah                       | Desktop     | [49adbe8acf](https://linux-hardware.org/?probe=49adbe8acf) | Mar 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M560... | Notebook    | [c87313bdd4](https://linux-hardware.org/?probe=c87313bdd4) | Mar 20, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [37bf97e9b3](https://linux-hardware.org/?probe=37bf97e9b3) | Mar 16, 2023 |
| Lenovo        | ThinkPad T540p 20BFS3BR0... | Notebook    | [6218acf76f](https://linux-hardware.org/?probe=6218acf76f) | Mar 12, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [ec707b621c](https://linux-hardware.org/?probe=ec707b621c) | Mar 05, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [36699f94c9](https://linux-hardware.org/?probe=36699f94c9) | Mar 05, 2023 |
| ASRock        | H81M-DGS R2.0               | Desktop     | [396ad2d6aa](https://linux-hardware.org/?probe=396ad2d6aa) | Mar 04, 2023 |
| ASRock        | B660M-ITX/ac                | Desktop     | [c2e600e445](https://linux-hardware.org/?probe=c2e600e445) | Feb 28, 2023 |
| ASRock        | B660M-ITX/ac                | Desktop     | [1efc15e2cc](https://linux-hardware.org/?probe=1efc15e2cc) | Feb 28, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [6f09d6cd6c](https://linux-hardware.org/?probe=6f09d6cd6c) | Feb 05, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [07d496ada9](https://linux-hardware.org/?probe=07d496ada9) | Feb 04, 2023 |
| Packard Be... | EasyNote TK87               | Notebook    | [82ce911f26](https://linux-hardware.org/?probe=82ce911f26) | Jan 25, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [2141789e3a](https://linux-hardware.org/?probe=2141789e3a) | Jan 14, 2023 |
| Packard Be... | EasyNote TK87               | Notebook    | [f1c4c8b89e](https://linux-hardware.org/?probe=f1c4c8b89e) | Jan 13, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [8674044a95](https://linux-hardware.org/?probe=8674044a95) | Jan 13, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [ff12fe840d](https://linux-hardware.org/?probe=ff12fe840d) | Jan 12, 2023 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [146f307b8e](https://linux-hardware.org/?probe=146f307b8e) | Jan 10, 2023 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [aa21c2b75f](https://linux-hardware.org/?probe=aa21c2b75f) | Jan 06, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [efa2d6986f](https://linux-hardware.org/?probe=efa2d6986f) | Dec 28, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [4a85ebbc33](https://linux-hardware.org/?probe=4a85ebbc33) | Dec 26, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [70436ae3c3](https://linux-hardware.org/?probe=70436ae3c3) | Dec 15, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [4c5bac90eb](https://linux-hardware.org/?probe=4c5bac90eb) | Dec 15, 2022 |
| ASRock        | Z490M Pro4                  | Desktop     | [2ace77f72c](https://linux-hardware.org/?probe=2ace77f72c) | Dec 14, 2022 |
| ASRock        | Z490M Pro4                  | Desktop     | [0b91c8c70f](https://linux-hardware.org/?probe=0b91c8c70f) | Dec 14, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | Notebook    | [d8b614d1ca](https://linux-hardware.org/?probe=d8b614d1ca) | Dec 12, 2022 |
| MSI           | MAG B660M BAZOOKA DDR4      | Desktop     | [280f28a486](https://linux-hardware.org/?probe=280f28a486) | Dec 11, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [1f904e68af](https://linux-hardware.org/?probe=1f904e68af) | Nov 29, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [6f3bf3fe46](https://linux-hardware.org/?probe=6f3bf3fe46) | Nov 28, 2022 |
| ASUSTek       | N53Jf                       | Notebook    | [e4dc6e5cd9](https://linux-hardware.org/?probe=e4dc6e5cd9) | Nov 27, 2022 |
| Lenovo        | ThinkPad X240 20AMA0W706    | Notebook    | [b792955af6](https://linux-hardware.org/?probe=b792955af6) | Nov 27, 2022 |
| Lenovo        | ThinkPad X240 20AMA0W706    | Notebook    | [033e206fab](https://linux-hardware.org/?probe=033e206fab) | Nov 25, 2022 |
| MSI           | Z490-A PRO                  | Desktop     | [9154fdbc9e](https://linux-hardware.org/?probe=9154fdbc9e) | Nov 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [0e77de9dba](https://linux-hardware.org/?probe=0e77de9dba) | Nov 20, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [96d82e20c4](https://linux-hardware.org/?probe=96d82e20c4) | Nov 19, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [f5fd517d69](https://linux-hardware.org/?probe=f5fd517d69) | Nov 19, 2022 |
| Lenovo        | Legion 7 16ARHA7 82UH       | Notebook    | [b8dae15ebf](https://linux-hardware.org/?probe=b8dae15ebf) | Nov 09, 2022 |
| Alienware     | 17                          | Notebook    | [91358a0bec](https://linux-hardware.org/?probe=91358a0bec) | Nov 09, 2022 |
| Fujitsu       | LIFEBOOK A512               | Notebook    | [c479fc2cea](https://linux-hardware.org/?probe=c479fc2cea) | Nov 06, 2022 |
| HP            | Unknown                     | Notebook    | [aa28b92716](https://linux-hardware.org/?probe=aa28b92716) | Nov 06, 2022 |
| Lenovo        | ThinkPad T440p 20AW000GU... | Notebook    | [b4ff1758e9](https://linux-hardware.org/?probe=b4ff1758e9) | Nov 02, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X2S... | Notebook    | [36d7199821](https://linux-hardware.org/?probe=36d7199821) | Nov 01, 2022 |
| ASUSTek       | M4A78                       | Desktop     | [8eb1316a14](https://linux-hardware.org/?probe=8eb1316a14) | Oct 31, 2022 |
| ASUSTek       | M4A78                       | Desktop     | [81374a561c](https://linux-hardware.org/?probe=81374a561c) | Oct 31, 2022 |
| ASUSTek       | M4A78                       | Desktop     | [d88d101a3c](https://linux-hardware.org/?probe=d88d101a3c) | Oct 29, 2022 |
| MSI           | GL72 6QD                    | Notebook    | [2f7c223f5a](https://linux-hardware.org/?probe=2f7c223f5a) | Oct 29, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [5405caf9dc](https://linux-hardware.org/?probe=5405caf9dc) | Oct 28, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [5548027da3](https://linux-hardware.org/?probe=5548027da3) | Oct 27, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [26d539c606](https://linux-hardware.org/?probe=26d539c606) | Oct 26, 2022 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [dbb72f4c00](https://linux-hardware.org/?probe=dbb72f4c00) | Oct 26, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [8b459ac79b](https://linux-hardware.org/?probe=8b459ac79b) | Oct 20, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [dad786ca06](https://linux-hardware.org/?probe=dad786ca06) | Oct 15, 2022 |
| ASRock        | B460 Steel Legend           | Desktop     | [ca98840e23](https://linux-hardware.org/?probe=ca98840e23) | Oct 14, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [7a1b08d912](https://linux-hardware.org/?probe=7a1b08d912) | Oct 13, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [3f808f36a0](https://linux-hardware.org/?probe=3f808f36a0) | Oct 13, 2022 |
| Unknown       | Seagate Personal Cloud (... | Desktop     | [40ea197650](https://linux-hardware.org/?probe=40ea197650) | Oct 09, 2022 |
| Dell          | Latitude 7390               | Notebook    | [268add52b3](https://linux-hardware.org/?probe=268add52b3) | Sep 19, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [9a7d178f1b](https://linux-hardware.org/?probe=9a7d178f1b) | Sep 15, 2022 |
| ASUSTek       | 1225C                       | Notebook    | [91f049c977](https://linux-hardware.org/?probe=91f049c977) | Sep 09, 2022 |
| Fujitsu       | LIFEBOOK S760               | Notebook    | [d805aa67b2](https://linux-hardware.org/?probe=d805aa67b2) | Sep 09, 2022 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [f6c6b627f7](https://linux-hardware.org/?probe=f6c6b627f7) | Aug 28, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [7332174749](https://linux-hardware.org/?probe=7332174749) | Aug 24, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [5097845796](https://linux-hardware.org/?probe=5097845796) | Aug 24, 2022 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [8c56960243](https://linux-hardware.org/?probe=8c56960243) | Aug 19, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [4d6f6d6a23](https://linux-hardware.org/?probe=4d6f6d6a23) | Aug 15, 2022 |
| Valve         | Jupiter                     | Notebook    | [ced35212a7](https://linux-hardware.org/?probe=ced35212a7) | Aug 07, 2022 |
| MSI           | MAG B460M BAZOOKA           | Desktop     | [5dae076f42](https://linux-hardware.org/?probe=5dae076f42) | Jul 27, 2022 |
| ECS           | G41T-M7                     | Desktop     | [a531a754a8](https://linux-hardware.org/?probe=a531a754a8) | Jul 23, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [e71169659f](https://linux-hardware.org/?probe=e71169659f) | Jul 22, 2022 |
| HP            | 3646h                       | Desktop     | [88b38da161](https://linux-hardware.org/?probe=88b38da161) | Jul 11, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [cdb4149eba](https://linux-hardware.org/?probe=cdb4149eba) | Jun 27, 2022 |
| MSI           | Z77A-G41                    | Desktop     | [d0f55f3c0b](https://linux-hardware.org/?probe=d0f55f3c0b) | Jun 22, 2022 |
| Dell          | 0VHWTR A02                  | Desktop     | [d8f9374e6c](https://linux-hardware.org/?probe=d8f9374e6c) | Jun 22, 2022 |
| Dell          | 0VHWTR A02                  | Desktop     | [00495646c1](https://linux-hardware.org/?probe=00495646c1) | Jun 22, 2022 |
| Dell          | 0VHWTR A02                  | Desktop     | [208e447fe1](https://linux-hardware.org/?probe=208e447fe1) | Jun 17, 2022 |
| ASUSTek       | E502NA                      | Notebook    | [d65dd8fc52](https://linux-hardware.org/?probe=d65dd8fc52) | Jun 09, 2022 |
| ASUSTek       | E502NA                      | Notebook    | [d3d64dcb5b](https://linux-hardware.org/?probe=d3d64dcb5b) | Jun 09, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [a068a18649](https://linux-hardware.org/?probe=a068a18649) | Jun 08, 2022 |
| Dell          | 088DT1 A00                  | Desktop     | [b585cb1f70](https://linux-hardware.org/?probe=b585cb1f70) | Jun 07, 2022 |
| HP            | Presario CQ57               | Notebook    | [9f87592293](https://linux-hardware.org/?probe=9f87592293) | Jun 02, 2022 |
| Intel         | DP67BG AAG10491-305         | Desktop     | [714722d24b](https://linux-hardware.org/?probe=714722d24b) | Jun 01, 2022 |
| Intel         | DP67BG AAG10491-305         | Desktop     | [966ab11802](https://linux-hardware.org/?probe=966ab11802) | May 31, 2022 |
| ASRock        | AB350 Pro4                  | Desktop     | [49223fe44b](https://linux-hardware.org/?probe=49223fe44b) | May 21, 2022 |
| ASRock        | AB350 Pro4                  | Desktop     | [40cb336486](https://linux-hardware.org/?probe=40cb336486) | May 21, 2022 |
| Gigabyte      | H55M-S2                     | Desktop     | [4d68acc78c](https://linux-hardware.org/?probe=4d68acc78c) | May 18, 2022 |
| Dell          | Latitude 5520               | Notebook    | [320ed1c4fc](https://linux-hardware.org/?probe=320ed1c4fc) | May 17, 2022 |
| Dell          | Latitude 5520               | Notebook    | [18823f33fb](https://linux-hardware.org/?probe=18823f33fb) | May 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [5107890ffd](https://linux-hardware.org/?probe=5107890ffd) | May 15, 2022 |
| Lenovo        | ThinkCentre M58 7360WQK     | Desktop     | [9002375046](https://linux-hardware.org/?probe=9002375046) | May 13, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [0773b6244e](https://linux-hardware.org/?probe=0773b6244e) | May 11, 2022 |
| Gigabyte      | B560 HD3                    | Desktop     | [34fd3f60c4](https://linux-hardware.org/?probe=34fd3f60c4) | May 11, 2022 |
| Lenovo        | ThinkPad T490s 20NX000AM... | Notebook    | [f07b38c5f9](https://linux-hardware.org/?probe=f07b38c5f9) | May 10, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [92637583b8](https://linux-hardware.org/?probe=92637583b8) | May 10, 2022 |
| mPTech        | ARC 11.6 128GB HD           | Notebook    | [aafa7cb1cb](https://linux-hardware.org/?probe=aafa7cb1cb) | May 07, 2022 |
| Dell          | Precision 7540              | Notebook    | [8b1b7dd8da](https://linux-hardware.org/?probe=8b1b7dd8da) | Apr 30, 2022 |
| Lenovo        | ThinkPad T520 4243RT9       | Notebook    | [a10fb9fe10](https://linux-hardware.org/?probe=a10fb9fe10) | Apr 23, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [b963507390](https://linux-hardware.org/?probe=b963507390) | Apr 19, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [fff8ad361e](https://linux-hardware.org/?probe=fff8ad361e) | Apr 19, 2022 |
| Lenovo        | ThinkPad T520 4243RT9       | Notebook    | [d948d987b4](https://linux-hardware.org/?probe=d948d987b4) | Apr 18, 2022 |
| Framework     | Laptop                      | Notebook    | [d4a02dfec9](https://linux-hardware.org/?probe=d4a02dfec9) | Apr 14, 2022 |
| Lenovo        | IdeaPad 320S-13IKB 81AK     | Notebook    | [8444b44333](https://linux-hardware.org/?probe=8444b44333) | Apr 04, 2022 |
| Lenovo        | ThinkPad X260 20F5S84400    | Notebook    | [69e1c25b4c](https://linux-hardware.org/?probe=69e1c25b4c) | Apr 03, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [8af8994f80](https://linux-hardware.org/?probe=8af8994f80) | Apr 02, 2022 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [ccf4457b51](https://linux-hardware.org/?probe=ccf4457b51) | Mar 28, 2022 |
| HP            | 18E9                        | Desktop     | [5a223b8722](https://linux-hardware.org/?probe=5a223b8722) | Mar 23, 2022 |
| Dell          | Latitude 5520               | Notebook    | [a8e30b61c6](https://linux-hardware.org/?probe=a8e30b61c6) | Mar 21, 2022 |
| Dell          | Latitude 5520               | Notebook    | [02b408b5f6](https://linux-hardware.org/?probe=02b408b5f6) | Mar 21, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | Notebook    | [ee3693d6a7](https://linux-hardware.org/?probe=ee3693d6a7) | Mar 09, 2022 |
| HP            | ENVY Laptop 13-ah0xxx       | Notebook    | [7fb04e6c7d](https://linux-hardware.org/?probe=7fb04e6c7d) | Mar 03, 2022 |
| HP            | ENVY Laptop 13-ah0xxx       | Notebook    | [0f27bdf5a8](https://linux-hardware.org/?probe=0f27bdf5a8) | Mar 02, 2022 |
| Lenovo        | 31900058 STD                | Desktop     | [d34e3c79a0](https://linux-hardware.org/?probe=d34e3c79a0) | Mar 01, 2022 |
| Lenovo        | ThinkPad X220 429136G       | Notebook    | [324d66c0fc](https://linux-hardware.org/?probe=324d66c0fc) | Feb 23, 2022 |
| ECS           | G41T-M7                     | Desktop     | [c4aca5bc12](https://linux-hardware.org/?probe=c4aca5bc12) | Feb 20, 2022 |
| HP            | EliteBook Folio 1040 G2     | Notebook    | [5f3cd9e8d5](https://linux-hardware.org/?probe=5f3cd9e8d5) | Feb 16, 2022 |
| MSI           | B150M PRO-VD                | Desktop     | [b46943492e](https://linux-hardware.org/?probe=b46943492e) | Feb 15, 2022 |
| HP            | 304Ah                       | Desktop     | [078b605c39](https://linux-hardware.org/?probe=078b605c39) | Feb 09, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [96f97ed2d6](https://linux-hardware.org/?probe=96f97ed2d6) | Jan 23, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [c9b246d9a8](https://linux-hardware.org/?probe=c9b246d9a8) | Jan 12, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [49234f883d](https://linux-hardware.org/?probe=49234f883d) | Jan 12, 2022 |
| Huanan        | X79 V2.47                   | Desktop     | [a27e7cdbef](https://linux-hardware.org/?probe=a27e7cdbef) | Jan 09, 2022 |
| Dell          | 0KH290                      | Desktop     | [e8c0e16dfb](https://linux-hardware.org/?probe=e8c0e16dfb) | Dec 28, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [ca26ae6ff8](https://linux-hardware.org/?probe=ca26ae6ff8) | Dec 22, 2021 |
| ASUSTek       | K52Jc                       | Notebook    | [f6789bc7ac](https://linux-hardware.org/?probe=f6789bc7ac) | Dec 18, 2021 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [5c0550c1e8](https://linux-hardware.org/?probe=5c0550c1e8) | Dec 09, 2021 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | Desktop     | [db552307a3](https://linux-hardware.org/?probe=db552307a3) | Dec 07, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [142cab14c6](https://linux-hardware.org/?probe=142cab14c6) | Dec 02, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [0b2751c5c1](https://linux-hardware.org/?probe=0b2751c5c1) | Dec 02, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [dbbe56da66](https://linux-hardware.org/?probe=dbbe56da66) | Dec 01, 2021 |
| Gigabyte      | X570 UD                     | Desktop     | [79c117738b](https://linux-hardware.org/?probe=79c117738b) | Dec 01, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [dc981a1604](https://linux-hardware.org/?probe=dc981a1604) | Nov 27, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [362a840c47](https://linux-hardware.org/?probe=362a840c47) | Nov 20, 2021 |
| Alienware     | 17                          | Notebook    | [d3460bdfd1](https://linux-hardware.org/?probe=d3460bdfd1) | Nov 20, 2021 |
| Dell          | Precision 5550              | Notebook    | [f7853ec2b6](https://linux-hardware.org/?probe=f7853ec2b6) | Nov 18, 2021 |
| Gigabyte      | GA-790XTA-UD4               | Desktop     | [6eb5a4107e](https://linux-hardware.org/?probe=6eb5a4107e) | Nov 10, 2021 |
| Intel         | D33217GKE G69901-205        | Desktop     | [a922d5f3fc](https://linux-hardware.org/?probe=a922d5f3fc) | Nov 10, 2021 |
| ZOTAC         | ZBOX-CA621NANO              | Mini pc     | [e540507afc](https://linux-hardware.org/?probe=e540507afc) | Nov 10, 2021 |
| Intel         | D33217GKE G69901-205        | Desktop     | [dd1ddaf74f](https://linux-hardware.org/?probe=dd1ddaf74f) | Nov 09, 2021 |
| MSI           | MAG Z390 TOMAHAWK           | Desktop     | [201bc8d044](https://linux-hardware.org/?probe=201bc8d044) | Oct 17, 2021 |
| Getac         | B300G4                      | Notebook    | [78b2fab1e0](https://linux-hardware.org/?probe=78b2fab1e0) | Oct 17, 2021 |
| HP            | Pavilion dv7                | Notebook    | [6c14033e55](https://linux-hardware.org/?probe=6c14033e55) | Oct 16, 2021 |
| HP            | Pavilion dv7                | Notebook    | [f93789f29a](https://linux-hardware.org/?probe=f93789f29a) | Oct 16, 2021 |
| Acer          | Extensa 5620                | Notebook    | [5cae4fe0fa](https://linux-hardware.org/?probe=5cae4fe0fa) | Oct 11, 2021 |
| HP            | EliteBook x360 1030 G2      | Convertible | [95d389bfe5](https://linux-hardware.org/?probe=95d389bfe5) | Oct 07, 2021 |
| Huanan        | X79 V2.47                   | Desktop     | [326b3f5892](https://linux-hardware.org/?probe=326b3f5892) | Oct 07, 2021 |
| Huanan        | X79 V2.47                   | Desktop     | [c2c6287186](https://linux-hardware.org/?probe=c2c6287186) | Oct 07, 2021 |
| Lenovo        | 318E SDK0J40697 WIN 3305... | Desktop     | [9cd559605c](https://linux-hardware.org/?probe=9cd559605c) | Sep 27, 2021 |
| Lenovo        | 318E SDK0J40697 WIN 3305... | Desktop     | [68f4ff7431](https://linux-hardware.org/?probe=68f4ff7431) | Sep 27, 2021 |
| Lenovo        | ThinkPad E14 20RA0036MX     | Notebook    | [b2183edddf](https://linux-hardware.org/?probe=b2183edddf) | Sep 24, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [d339553d59](https://linux-hardware.org/?probe=d339553d59) | Sep 19, 2021 |
| Prestigio     | PNT10131DEDB                | Convertible | [39dc1df1df](https://linux-hardware.org/?probe=39dc1df1df) | Sep 18, 2021 |
| Alienware     | 17                          | Notebook    | [c97b201719](https://linux-hardware.org/?probe=c97b201719) | Sep 17, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [47fb03fde8](https://linux-hardware.org/?probe=47fb03fde8) | Sep 17, 2021 |
| MSI           | MS-B901                     | All in one  | [282992f343](https://linux-hardware.org/?probe=282992f343) | Sep 14, 2021 |
| MSI           | MS-B901                     | All in one  | [3a288bcc81](https://linux-hardware.org/?probe=3a288bcc81) | Sep 14, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [4f393c5347](https://linux-hardware.org/?probe=4f393c5347) | Sep 13, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [1240138d48](https://linux-hardware.org/?probe=1240138d48) | Sep 11, 2021 |
| ASUSTek       | UX530UX                     | Notebook    | [c713dcf9e2](https://linux-hardware.org/?probe=c713dcf9e2) | Sep 08, 2021 |
| ASUSTek       | X510UA                      | Notebook    | [0a8045cc4f](https://linux-hardware.org/?probe=0a8045cc4f) | Sep 05, 2021 |
| ASUSTek       | X550ZA                      | Notebook    | [210ca88228](https://linux-hardware.org/?probe=210ca88228) | Aug 30, 2021 |
| Lenovo        | ThinkPad X201 3680CG7       | Notebook    | [9565bae9c3](https://linux-hardware.org/?probe=9565bae9c3) | Aug 30, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [75619baa6e](https://linux-hardware.org/?probe=75619baa6e) | Aug 29, 2021 |
| ASUSTek       | X550ZA                      | Notebook    | [0a21d3b326](https://linux-hardware.org/?probe=0a21d3b326) | Aug 27, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [bf81c78371](https://linux-hardware.org/?probe=bf81c78371) | Aug 26, 2021 |
| Gigabyte      | Z87X-D3H-CF                 | Desktop     | [b40ad47903](https://linux-hardware.org/?probe=b40ad47903) | Aug 25, 2021 |
| Lenovo        | ThinkPad T510 4384GFG       | Notebook    | [e5d8500e1c](https://linux-hardware.org/?probe=e5d8500e1c) | Aug 21, 2021 |
| Lenovo        | ThinkPad T510 4384GFG       | Notebook    | [67b971a2dd](https://linux-hardware.org/?probe=67b971a2dd) | Aug 21, 2021 |
| Lenovo        | ThinkPad W541 20EF001TMS    | Notebook    | [bc2879c7e5](https://linux-hardware.org/?probe=bc2879c7e5) | Aug 19, 2021 |
| Lenovo        | ThinkPad 20AY001DMH         | Notebook    | [d3f7b62a42](https://linux-hardware.org/?probe=d3f7b62a42) | Aug 19, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [559742f4d7](https://linux-hardware.org/?probe=559742f4d7) | Aug 19, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [f21459caa1](https://linux-hardware.org/?probe=f21459caa1) | Aug 19, 2021 |
| Lenovo        | ThinkPad T440 20B60061MD    | Notebook    | [5f9d1cd1a6](https://linux-hardware.org/?probe=5f9d1cd1a6) | Aug 18, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [d28cc83aed](https://linux-hardware.org/?probe=d28cc83aed) | Aug 17, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [be5db43316](https://linux-hardware.org/?probe=be5db43316) | Aug 17, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [0ce69e02fa](https://linux-hardware.org/?probe=0ce69e02fa) | Aug 17, 2021 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [286d06cd5e](https://linux-hardware.org/?probe=286d06cd5e) | Aug 15, 2021 |
| Lenovo        | ThinkPad T440 20B60061MD    | Notebook    | [fcd91a58e2](https://linux-hardware.org/?probe=fcd91a58e2) | Aug 13, 2021 |
| Gigabyte      | B250M-D2V-CF                | Desktop     | [b2db3ea0a9](https://linux-hardware.org/?probe=b2db3ea0a9) | Aug 10, 2021 |
| Gigabyte      | B250M-D2V-CF                | Desktop     | [c086b1441c](https://linux-hardware.org/?probe=c086b1441c) | Aug 09, 2021 |
| HP            | Pavilion dv7                | Notebook    | [a56935a751](https://linux-hardware.org/?probe=a56935a751) | Aug 09, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [2a9fe5f63c](https://linux-hardware.org/?probe=2a9fe5f63c) | Jul 31, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [1c5dccfd22](https://linux-hardware.org/?probe=1c5dccfd22) | Jul 31, 2021 |
| MSI           | GP62M 7RDX                  | Notebook    | [f02c96473f](https://linux-hardware.org/?probe=f02c96473f) | Jul 30, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [19a4054ab4](https://linux-hardware.org/?probe=19a4054ab4) | Jul 28, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [bc64d314a1](https://linux-hardware.org/?probe=bc64d314a1) | Jul 28, 2021 |
| ASUSTek       | M3N78                       | Desktop     | [810e386d8b](https://linux-hardware.org/?probe=810e386d8b) | Jul 26, 2021 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [4f26f93184](https://linux-hardware.org/?probe=4f26f93184) | Jul 26, 2021 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [932c4de6ce](https://linux-hardware.org/?probe=932c4de6ce) | Jul 18, 2021 |
| Lenovo        | ThinkPad T440 20B60061MD    | Notebook    | [7207e6aa0f](https://linux-hardware.org/?probe=7207e6aa0f) | Jul 08, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [a47fb764b4](https://linux-hardware.org/?probe=a47fb764b4) | Jul 01, 2021 |
| ASUSTek       | N3050I-C                    | Desktop     | [e9cd0640f7](https://linux-hardware.org/?probe=e9cd0640f7) | Jun 30, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [7a01d3d232](https://linux-hardware.org/?probe=7a01d3d232) | Jun 28, 2021 |
| ASUSTek       | N3050I-C                    | Desktop     | [c42e493962](https://linux-hardware.org/?probe=c42e493962) | Jun 26, 2021 |
| ASUSTek       | N3050I-C                    | Desktop     | [9834731c15](https://linux-hardware.org/?probe=9834731c15) | Jun 26, 2021 |
| Lenovo        | IdeaPadFlex 10 20324        | Notebook    | [d96aea9f90](https://linux-hardware.org/?probe=d96aea9f90) | Jun 26, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [cb4242a344](https://linux-hardware.org/?probe=cb4242a344) | Jun 15, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [7bf0e678ea](https://linux-hardware.org/?probe=7bf0e678ea) | Jun 13, 2021 |
| Lenovo        | ThinkPad T450s 20BWS1RG0... | Notebook    | [79d386a567](https://linux-hardware.org/?probe=79d386a567) | Jun 08, 2021 |
| Dell          | Latitude 5511               | Notebook    | [933fb253d4](https://linux-hardware.org/?probe=933fb253d4) | Jun 07, 2021 |
| Dell          | Latitude 5511               | Notebook    | [7b5e6276c0](https://linux-hardware.org/?probe=7b5e6276c0) | Jun 07, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [6a7fe6469a](https://linux-hardware.org/?probe=6a7fe6469a) | Jun 06, 2021 |
| Timi          | RedmiBook 14 II             | Notebook    | [8700a7eaed](https://linux-hardware.org/?probe=8700a7eaed) | May 31, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [1ba665b0b3](https://linux-hardware.org/?probe=1ba665b0b3) | May 24, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [3ae2f83c9f](https://linux-hardware.org/?probe=3ae2f83c9f) | May 23, 2021 |
| Dell          | G5 5587                     | Notebook    | [39be80ad79](https://linux-hardware.org/?probe=39be80ad79) | May 19, 2021 |
| Dell          | Precision 5530              | Notebook    | [aa0aa77e62](https://linux-hardware.org/?probe=aa0aa77e62) | May 16, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [6f3d7a9d3f](https://linux-hardware.org/?probe=6f3d7a9d3f) | May 15, 2021 |
| Dell          | Vostro V131                 | Notebook    | [43fe3f190f](https://linux-hardware.org/?probe=43fe3f190f) | May 14, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [426f99f758](https://linux-hardware.org/?probe=426f99f758) | May 14, 2021 |
| Lenovo        | Y50-70 20378                | Notebook    | [fe95dd9355](https://linux-hardware.org/?probe=fe95dd9355) | May 11, 2021 |
| Dell          | System Inspiron N7110       | Notebook    | [f5f418c337](https://linux-hardware.org/?probe=f5f418c337) | May 02, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [1bbe4079c5](https://linux-hardware.org/?probe=1bbe4079c5) | Apr 27, 2021 |
| HP            | Compaq nx6120 (PV170PA#U... | Notebook    | [5f105dda68](https://linux-hardware.org/?probe=5f105dda68) | Apr 21, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f84cf26650](https://linux-hardware.org/?probe=f84cf26650) | Apr 10, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [a677fe0972](https://linux-hardware.org/?probe=a677fe0972) | Apr 08, 2021 |
| MSI           | B250M PRO-VD                | Desktop     | [20ff770033](https://linux-hardware.org/?probe=20ff770033) | Apr 07, 2021 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [ed6b3b5754](https://linux-hardware.org/?probe=ed6b3b5754) | Apr 04, 2021 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [218092e59f](https://linux-hardware.org/?probe=218092e59f) | Apr 03, 2021 |
| Lenovo        | Y50-70 20378                | Notebook    | [18ec5d54a4](https://linux-hardware.org/?probe=18ec5d54a4) | Apr 02, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [6e6dc77b21](https://linux-hardware.org/?probe=6e6dc77b21) | Mar 29, 2021 |
| Samsung       | R410                        | Notebook    | [331d909654](https://linux-hardware.org/?probe=331d909654) | Mar 27, 2021 |
| ASUSTek       | P5LD2                       | Desktop     | [72b40a39d4](https://linux-hardware.org/?probe=72b40a39d4) | Mar 25, 2021 |
| Samsung       | R410                        | Notebook    | [5aa6fee818](https://linux-hardware.org/?probe=5aa6fee818) | Mar 25, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [f555918663](https://linux-hardware.org/?probe=f555918663) | Mar 24, 2021 |
| Samsung       | R410                        | Notebook    | [d3f94bcc8c](https://linux-hardware.org/?probe=d3f94bcc8c) | Mar 24, 2021 |
| OEM           | Intel H81                   | Desktop     | [385b6ee448](https://linux-hardware.org/?probe=385b6ee448) | Mar 19, 2021 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [013a785195](https://linux-hardware.org/?probe=013a785195) | Mar 18, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [fb33c2e9b9](https://linux-hardware.org/?probe=fb33c2e9b9) | Mar 17, 2021 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [9b991380f9](https://linux-hardware.org/?probe=9b991380f9) | Mar 17, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [273fba9fd2](https://linux-hardware.org/?probe=273fba9fd2) | Mar 14, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [75a661f9f8](https://linux-hardware.org/?probe=75a661f9f8) | Mar 14, 2021 |
| Notebook      | W35xSS_370SS                | Notebook    | [0e98472f08](https://linux-hardware.org/?probe=0e98472f08) | Mar 02, 2021 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [ff698cacf3](https://linux-hardware.org/?probe=ff698cacf3) | Feb 27, 2021 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [116202ee88](https://linux-hardware.org/?probe=116202ee88) | Feb 27, 2021 |
| Lenovo        | ThinkPad T61 766112G        | Notebook    | [04ec7d5efd](https://linux-hardware.org/?probe=04ec7d5efd) | Feb 25, 2021 |
| Acer          | Aspire V5-572P              | Notebook    | [61834c786c](https://linux-hardware.org/?probe=61834c786c) | Feb 24, 2021 |
| HP            | EliteBook 850 G2            | Notebook    | [4c935ce981](https://linux-hardware.org/?probe=4c935ce981) | Feb 18, 2021 |
| HP            | EliteBook 850 G2            | Notebook    | [69090d5f4c](https://linux-hardware.org/?probe=69090d5f4c) | Feb 17, 2021 |
| MSI           | MS-7267                     | Desktop     | [b987c1ad14](https://linux-hardware.org/?probe=b987c1ad14) | Feb 15, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [e1dc5a8ea7](https://linux-hardware.org/?probe=e1dc5a8ea7) | Feb 14, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [d3004980ee](https://linux-hardware.org/?probe=d3004980ee) | Feb 09, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [8652b51903](https://linux-hardware.org/?probe=8652b51903) | Jan 20, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [77be7c1164](https://linux-hardware.org/?probe=77be7c1164) | Jan 18, 2021 |
| HP            | EliteBook 840 G5            | Notebook    | [59aaeda6a9](https://linux-hardware.org/?probe=59aaeda6a9) | Dec 28, 2020 |
| Fujitsu       | LIFEBOOK E744               | Notebook    | [81daeffb49](https://linux-hardware.org/?probe=81daeffb49) | Dec 28, 2020 |
| MSI           | Z77A-G41                    | Desktop     | [171be87aa0](https://linux-hardware.org/?probe=171be87aa0) | Dec 27, 2020 |
| Timi          | RedmiBook 16                | Notebook    | [34bc3ceb48](https://linux-hardware.org/?probe=34bc3ceb48) | Dec 24, 2020 |
| MSI           | GT70 2OC/2OD                | Notebook    | [e52bbc40aa](https://linux-hardware.org/?probe=e52bbc40aa) | Dec 19, 2020 |
| Lenovo        | ThinkPad T61 64665DG        | Notebook    | [95355fcff6](https://linux-hardware.org/?probe=95355fcff6) | Dec 17, 2020 |
| Lenovo        | ThinkPad T61 64665DG        | Notebook    | [3ee030e6ac](https://linux-hardware.org/?probe=3ee030e6ac) | Dec 17, 2020 |
| Lenovo        | ThinkPad T61 765912G        | Notebook    | [9651814a46](https://linux-hardware.org/?probe=9651814a46) | Dec 08, 2020 |
| MSI           | H81I                        | Desktop     | [772ce7ff24](https://linux-hardware.org/?probe=772ce7ff24) | Dec 03, 2020 |
| MSI           | Boston                      | Desktop     | [9843e15faa](https://linux-hardware.org/?probe=9843e15faa) | Dec 01, 2020 |
| Lenovo        | Y50-70 20378                | Notebook    | [07c05e281b](https://linux-hardware.org/?probe=07c05e281b) | Nov 29, 2020 |
| HP            | ENVY Laptop 13-ah0xxx       | Notebook    | [4defcea6f8](https://linux-hardware.org/?probe=4defcea6f8) | Nov 24, 2020 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [1280ebbedf](https://linux-hardware.org/?probe=1280ebbedf) | Nov 17, 2020 |
| Intel         | D425KT AAE93083-400         | Mini pc     | [e1f6c727d9](https://linux-hardware.org/?probe=e1f6c727d9) | Oct 14, 2020 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [f61cacc391](https://linux-hardware.org/?probe=f61cacc391) | Oct 05, 2020 |
| Notebook      | W35xSS_370SS                | Notebook    | [ed0e6634d4](https://linux-hardware.org/?probe=ed0e6634d4) | Sep 29, 2020 |
| HP            | EliteBook 745 G5            | Notebook    | [e9d2889a6d](https://linux-hardware.org/?probe=e9d2889a6d) | Sep 28, 2020 |
| MSI           | X470 GAMING PRO             | Desktop     | [6b818c1352](https://linux-hardware.org/?probe=6b818c1352) | Sep 28, 2020 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [3255a17583](https://linux-hardware.org/?probe=3255a17583) | Sep 28, 2020 |
| MSI           | Z170-A PRO                  | Desktop     | [bcf22d328e](https://linux-hardware.org/?probe=bcf22d328e) | Sep 28, 2020 |
| Dell          | Latitude 7490               | Notebook    | [cfd6c8dcc4](https://linux-hardware.org/?probe=cfd6c8dcc4) | Sep 28, 2020 |
| Intel         | DX79TO AAG28805-400         | Desktop     | [d4cdc0726f](https://linux-hardware.org/?probe=d4cdc0726f) | Sep 26, 2020 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [118729faeb](https://linux-hardware.org/?probe=118729faeb) | Sep 23, 2020 |
| TUXEDO        | Book BA1510                 | Notebook    | [d89436074e](https://linux-hardware.org/?probe=d89436074e) | Sep 23, 2020 |
| Lenovo        | ThinkPad E495 20NE001GMX    | Notebook    | [3399940dd9](https://linux-hardware.org/?probe=3399940dd9) | Sep 17, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [5bd6ca5aba](https://linux-hardware.org/?probe=5bd6ca5aba) | Sep 15, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [83263681eb](https://linux-hardware.org/?probe=83263681eb) | Sep 15, 2020 |
| Notebook      | W35xSS_370SS                | Notebook    | [5b35813fca](https://linux-hardware.org/?probe=5b35813fca) | Sep 10, 2020 |
| HP            | ZBook 17                    | Notebook    | [605dfd3279](https://linux-hardware.org/?probe=605dfd3279) | Sep 08, 2020 |
| HP            | ZBook 17                    | Notebook    | [09e5bd8eb6](https://linux-hardware.org/?probe=09e5bd8eb6) | Sep 08, 2020 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [0dd7682249](https://linux-hardware.org/?probe=0dd7682249) | Sep 08, 2020 |
| ASUSTek       | X542UQR                     | Notebook    | [7782f01f3c](https://linux-hardware.org/?probe=7782f01f3c) | Sep 04, 2020 |
| ASUSTek       | E502MA                      | Notebook    | [1eb9e7db73](https://linux-hardware.org/?probe=1eb9e7db73) | Sep 01, 2020 |
| ASUSTek       | X501U                       | Notebook    | [006dc7a8d6](https://linux-hardware.org/?probe=006dc7a8d6) | Aug 15, 2020 |
| ASRock        | P45DE3                      | Desktop     | [3fce267079](https://linux-hardware.org/?probe=3fce267079) | Aug 11, 2020 |
| Lenovo        | 0x36A017AA SDK0J40700 WI... | Desktop     | [5b48876c88](https://linux-hardware.org/?probe=5b48876c88) | Aug 11, 2020 |
| Lenovo        | 0x36A017AA SDK0J40700 WI... | Desktop     | [420e531d0c](https://linux-hardware.org/?probe=420e531d0c) | Aug 11, 2020 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [fd8d68081e](https://linux-hardware.org/?probe=fd8d68081e) | Aug 08, 2020 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [30d102a39e](https://linux-hardware.org/?probe=30d102a39e) | Aug 07, 2020 |
| Lenovo        | ThinkPad X220 4291R30       | Notebook    | [bdf2c40591](https://linux-hardware.org/?probe=bdf2c40591) | Aug 06, 2020 |
| Lenovo        | ThinkPad T490 20N2000NMX    | Notebook    | [8f21de6e06](https://linux-hardware.org/?probe=8f21de6e06) | Aug 05, 2020 |
| Acer          | Extensa 5620                | Notebook    | [dba48971a3](https://linux-hardware.org/?probe=dba48971a3) | Jul 24, 2020 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [f6f1267e91](https://linux-hardware.org/?probe=f6f1267e91) | Jul 23, 2020 |
| Lenovo        | ThinkPad T480s 20L7001VU... | Notebook    | [03bcc8865c](https://linux-hardware.org/?probe=03bcc8865c) | Jul 23, 2020 |
| ASRock        | B250M Pro4                  | Desktop     | [3ad9bafdc1](https://linux-hardware.org/?probe=3ad9bafdc1) | Jul 19, 2020 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [43684f5ded](https://linux-hardware.org/?probe=43684f5ded) | Jul 15, 2020 |
| ASUSTek       | P5LD2                       | Desktop     | [caa5d2a038](https://linux-hardware.org/?probe=caa5d2a038) | Jul 13, 2020 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [751ba49889](https://linux-hardware.org/?probe=751ba49889) | Jul 09, 2020 |
| ASRock        | Z170 Pro4S                  | Desktop     | [71665893c0](https://linux-hardware.org/?probe=71665893c0) | Jul 08, 2020 |
| ASRock        | Z170 Pro4S                  | Desktop     | [2d7a70bd54](https://linux-hardware.org/?probe=2d7a70bd54) | Jul 06, 2020 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [3149f0037a](https://linux-hardware.org/?probe=3149f0037a) | Jul 03, 2020 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [9bd5a64d0d](https://linux-hardware.org/?probe=9bd5a64d0d) | Jun 25, 2020 |
| HP            | Presario CQ56               | Notebook    | [f668bc59f5](https://linux-hardware.org/?probe=f668bc59f5) | Jun 23, 2020 |
| HP            | Presario CQ56               | Notebook    | [b8db4c3694](https://linux-hardware.org/?probe=b8db4c3694) | Jun 23, 2020 |
| Dell          | XPS 15 9560                 | Notebook    | [867ca870fd](https://linux-hardware.org/?probe=867ca870fd) | Jun 14, 2020 |
| ASUSTek       | WS X299 SAGE                | Desktop     | [bfc9505d4b](https://linux-hardware.org/?probe=bfc9505d4b) | Jun 05, 2020 |
| MSI           | Boston                      | Desktop     | [48a3bf1932](https://linux-hardware.org/?probe=48a3bf1932) | Jun 02, 2020 |
| Samsung       | 535U3C                      | Notebook    | [e7bc13b354](https://linux-hardware.org/?probe=e7bc13b354) | May 30, 2020 |
| Lenovo        | ThinkPad P43s 20RH0021MX    | Notebook    | [26c8949a0a](https://linux-hardware.org/?probe=26c8949a0a) | May 29, 2020 |
| Supermicro    | X10SLH-F/X10SLM+-F          | Server      | [869444acf6](https://linux-hardware.org/?probe=869444acf6) | May 26, 2020 |
| Lenovo        | ThinkPad Yoga 370 20JJS0... | Convertible | [d4e3d725fa](https://linux-hardware.org/?probe=d4e3d725fa) | May 19, 2020 |
| ASUSTek       | Z97-A                       | Desktop     | [32fc505cab](https://linux-hardware.org/?probe=32fc505cab) | May 17, 2020 |
| MSI           | Z170A GAMING M3             | Desktop     | [369ce228c3](https://linux-hardware.org/?probe=369ce228c3) | May 16, 2020 |
| Lenovo        | ThinkPad T540p 20BFS4510... | Notebook    | [6c5bf8bfbe](https://linux-hardware.org/?probe=6c5bf8bfbe) | May 05, 2020 |
| HP            | EliteBook 840 G2            | Notebook    | [e1602a8c0e](https://linux-hardware.org/?probe=e1602a8c0e) | May 04, 2020 |
| Lenovo        | Y720-15IKB 80VR             | Notebook    | [a1a1ce6e00](https://linux-hardware.org/?probe=a1a1ce6e00) | May 02, 2020 |
| Lenovo        | Y720-15IKB 80VR             | Notebook    | [e3321de949](https://linux-hardware.org/?probe=e3321de949) | May 02, 2020 |
| Samsung       | 900X3C/900X3D/900X4C/900... | Notebook    | [35b95432ac](https://linux-hardware.org/?probe=35b95432ac) | Apr 30, 2020 |
| Dell          | XPS 15 9560                 | Notebook    | [eea0fa4941](https://linux-hardware.org/?probe=eea0fa4941) | Apr 25, 2020 |
| MSI           | B360-A PRO                  | Desktop     | [c42cb75770](https://linux-hardware.org/?probe=c42cb75770) | Apr 24, 2020 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | Notebook    | [91770bcd78](https://linux-hardware.org/?probe=91770bcd78) | Apr 22, 2020 |
| MSI           | GS75 Stealth 8SE            | Notebook    | [1c50333136](https://linux-hardware.org/?probe=1c50333136) | Apr 07, 2020 |
| HP            | EliteBook 2560p             | Notebook    | [cdca82a043](https://linux-hardware.org/?probe=cdca82a043) | Apr 05, 2020 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [61c4420d0e](https://linux-hardware.org/?probe=61c4420d0e) | Mar 22, 2020 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [76af4a7e0b](https://linux-hardware.org/?probe=76af4a7e0b) | Mar 21, 2020 |
| ASRock        | P45DE3                      | Desktop     | [fffef664cd](https://linux-hardware.org/?probe=fffef664cd) | Mar 18, 2020 |
| MSI           | B75A-G43                    | Desktop     | [9683ec9bd4](https://linux-hardware.org/?probe=9683ec9bd4) | Mar 16, 2020 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [95eb08349e](https://linux-hardware.org/?probe=95eb08349e) | Mar 15, 2020 |
| Samsung       | 275E4E/275E5E               | Notebook    | [6b624f1079](https://linux-hardware.org/?probe=6b624f1079) | Mar 12, 2020 |
| Lenovo        | ThinkPad A285 20MXS0BG00    | Notebook    | [4dabcb8d3f](https://linux-hardware.org/?probe=4dabcb8d3f) | Mar 11, 2020 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [e30b449cc4](https://linux-hardware.org/?probe=e30b449cc4) | Mar 08, 2020 |
| ASUSTek       | Z97-A                       | Desktop     | [8bc7b7979a](https://linux-hardware.org/?probe=8bc7b7979a) | Mar 01, 2020 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [63e19ed1f4](https://linux-hardware.org/?probe=63e19ed1f4) | Feb 28, 2020 |
| MSI           | 990FXA-GD65                 | Desktop     | [adc15c7147](https://linux-hardware.org/?probe=adc15c7147) | Feb 24, 2020 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [b17f2abd3e](https://linux-hardware.org/?probe=b17f2abd3e) | Feb 20, 2020 |
| Lenovo        | ThinkPad P50 20EN0006MS     | Notebook    | [c71def9148](https://linux-hardware.org/?probe=c71def9148) | Feb 18, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [ed5efcdf48](https://linux-hardware.org/?probe=ed5efcdf48) | Feb 03, 2020 |
| Gigabyte      | H81M-S1                     | Desktop     | [754bdf88c1](https://linux-hardware.org/?probe=754bdf88c1) | Jan 26, 2020 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [1eb5f177d1](https://linux-hardware.org/?probe=1eb5f177d1) | Jan 13, 2020 |
| Dell          | 0D28YY A01                  | Desktop     | [be51211fe3](https://linux-hardware.org/?probe=be51211fe3) | Dec 09, 2019 |
| Dell          | Latitude 5289               | Convertible | [dfdc8c484f](https://linux-hardware.org/?probe=dfdc8c484f) | Dec 04, 2019 |
| Gigabyte      | H81M-S1                     | Desktop     | [57524ab581](https://linux-hardware.org/?probe=57524ab581) | Dec 03, 2019 |
| Dell          | Precision 5510              | Notebook    | [68c56e0ab4](https://linux-hardware.org/?probe=68c56e0ab4) | Dec 02, 2019 |
| ASUSTek       | VM60                        | Desktop     | [4842363a0b](https://linux-hardware.org/?probe=4842363a0b) | Nov 14, 2019 |
| HP            | Pavilion Gaming Notebook    | Notebook    | [c4917de06e](https://linux-hardware.org/?probe=c4917de06e) | Oct 17, 2019 |
| HP            | Pavilion Gaming Notebook    | Notebook    | [9f867b307a](https://linux-hardware.org/?probe=9f867b307a) | Oct 12, 2019 |
| ASRock        | B250M Pro4                  | Desktop     | [8beb57338d](https://linux-hardware.org/?probe=8beb57338d) | Oct 02, 2019 |
| HP            | Pavilion Gaming Notebook    | Notebook    | [f3f1a208c1](https://linux-hardware.org/?probe=f3f1a208c1) | Sep 26, 2019 |
| HP            | Pavilion Gaming Notebook    | Notebook    | [0639ef182a](https://linux-hardware.org/?probe=0639ef182a) | Sep 20, 2019 |
| HP            | Pavilion Gaming Notebook    | Notebook    | [3b99dff2c2](https://linux-hardware.org/?probe=3b99dff2c2) | Sep 19, 2019 |
| ASUSTek       | A8N32-SLI-Deluxe            | Desktop     | [abc398724a](https://linux-hardware.org/?probe=abc398724a) | Sep 16, 2019 |
| ASUSTek       | A8N32-SLI-Deluxe            | Desktop     | [f6acac9fc8](https://linux-hardware.org/?probe=f6acac9fc8) | Sep 15, 2019 |
| ASUSTek       | A8N32-SLI-Deluxe            | Desktop     | [d2b5c32d2f](https://linux-hardware.org/?probe=d2b5c32d2f) | Sep 15, 2019 |
| Dell          | Inspiron 5748               | Notebook    | [75647e5457](https://linux-hardware.org/?probe=75647e5457) | Sep 03, 2019 |
| Acer          | Aspire V3-771               | Notebook    | [335c3fea78](https://linux-hardware.org/?probe=335c3fea78) | Aug 10, 2019 |
| Quanta        | TWH                         | Notebook    | [b6c3554305](https://linux-hardware.org/?probe=b6c3554305) | Aug 05, 2019 |
| Quanta        | TWH                         | Notebook    | [243be58298](https://linux-hardware.org/?probe=243be58298) | Aug 05, 2019 |
| HP            | OMEN by Laptop              | Notebook    | [4a247c1234](https://linux-hardware.org/?probe=4a247c1234) | Aug 03, 2019 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [15bfdc0f25](https://linux-hardware.org/?probe=15bfdc0f25) | Aug 03, 2019 |
| HP            | OMEN by Laptop              | Notebook    | [cd37f24ff8](https://linux-hardware.org/?probe=cd37f24ff8) | Aug 01, 2019 |
| HP            | 1495                        | Desktop     | [3d9e77ae8a](https://linux-hardware.org/?probe=3d9e77ae8a) | Jul 23, 2019 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [46e1a9fc55](https://linux-hardware.org/?probe=46e1a9fc55) | Jul 04, 2019 |
| Dell          | Inspiron 5558               | Notebook    | [f26b9a5e36](https://linux-hardware.org/?probe=f26b9a5e36) | Jun 29, 2019 |
| ASUSTek       | N56VZ                       | Notebook    | [02928f6b1e](https://linux-hardware.org/?probe=02928f6b1e) | Jun 25, 2019 |
| ASRock        | B250M Pro4                  | Desktop     | [3a8d19c8fc](https://linux-hardware.org/?probe=3a8d19c8fc) | Jun 22, 2019 |
| Gigabyte      | 970-GAMING                  | Desktop     | [aa1385d100](https://linux-hardware.org/?probe=aa1385d100) | Jun 03, 2019 |
| Lenovo        | IdeaPad U330p 20267         | Notebook    | [1edb7b5f96](https://linux-hardware.org/?probe=1edb7b5f96) | May 25, 2019 |
| HP            | Pavilion dv4000 (EK980EA... | Notebook    | [837230178b](https://linux-hardware.org/?probe=837230178b) | May 23, 2019 |
| Intel         | DQ35JO AAD82085-807         | Desktop     | [7f57ad053d](https://linux-hardware.org/?probe=7f57ad053d) | May 20, 2019 |
| Lenovo        | G50-70 20351                | Notebook    | [84c3544bb2](https://linux-hardware.org/?probe=84c3544bb2) | May 20, 2019 |
| Samsung       | 275E4E/275E5E               | Notebook    | [60cb87eeb6](https://linux-hardware.org/?probe=60cb87eeb6) | May 11, 2019 |
| Dell          | Latitude 5289               | Convertible | [e28d069f05](https://linux-hardware.org/?probe=e28d069f05) | May 07, 2019 |
| Lenovo        | ThinkPad T61 76641FG        | Notebook    | [cfcb3e3b82](https://linux-hardware.org/?probe=cfcb3e3b82) | May 02, 2019 |
| Lenovo        | ThinkPad T61 76641FG        | Notebook    | [c577dfbf17](https://linux-hardware.org/?probe=c577dfbf17) | May 02, 2019 |
| Samsung       | 770Z5E/780Z5E               | Notebook    | [e07529a7fc](https://linux-hardware.org/?probe=e07529a7fc) | Apr 14, 2019 |
| Dell          | 0KP561                      | Desktop     | [bba0fe2672](https://linux-hardware.org/?probe=bba0fe2672) | Apr 05, 2019 |
| Dell          | 0KP561                      | Desktop     | [f3085d1ae9](https://linux-hardware.org/?probe=f3085d1ae9) | Apr 04, 2019 |
| Fujitsu Si... | AMILO La1703                | Notebook    | [4530891733](https://linux-hardware.org/?probe=4530891733) | Apr 01, 2019 |
| ASRock        | H370M-ITX/ac                | Desktop     | [ba39531b87](https://linux-hardware.org/?probe=ba39531b87) | Mar 31, 2019 |
| Dell          | Inspiron 3543               | Notebook    | [e411551975](https://linux-hardware.org/?probe=e411551975) | Mar 21, 2019 |
| Dell          | Inspiron 3543               | Notebook    | [f85fec55bb](https://linux-hardware.org/?probe=f85fec55bb) | Mar 19, 2019 |
| Samsung       | 900X3C/900X3D/900X3E/900... | Notebook    | [bee48cd1c5](https://linux-hardware.org/?probe=bee48cd1c5) | Mar 09, 2019 |
| Lenovo        | ThinkPad T580 20L90026MX    | Notebook    | [14afd9ea12](https://linux-hardware.org/?probe=14afd9ea12) | Feb 27, 2019 |
| HP            | 18E7                        | Desktop     | [19df4fb560](https://linux-hardware.org/?probe=19df4fb560) | Feb 22, 2019 |
| HP            | ProBook 470 G1              | Notebook    | [268414d1b5](https://linux-hardware.org/?probe=268414d1b5) | Feb 07, 2019 |
| ABIT          | KN9 Series                  | Desktop     | [10015b723b](https://linux-hardware.org/?probe=10015b723b) | Feb 04, 2019 |
| Intel         | NUC8BEB J72692-303          | Mini pc     | [f1a9b27e5c](https://linux-hardware.org/?probe=f1a9b27e5c) | Feb 04, 2019 |
| ASRock        | B250M Pro4                  | Desktop     | [b702949950](https://linux-hardware.org/?probe=b702949950) | Dec 19, 2018 |
| Lenovo        | ThinkPad T480 20L5000BMX    | Notebook    | [5357d8ad3a](https://linux-hardware.org/?probe=5357d8ad3a) | Dec 04, 2018 |
| Gigabyte      | AX370M-Gaming 3-CF          | Desktop     | [158fb83dcc](https://linux-hardware.org/?probe=158fb83dcc) | Nov 13, 2018 |
| ASRock        | B250M Pro4                  | Desktop     | [a00ad66604](https://linux-hardware.org/?probe=a00ad66604) | Oct 24, 2018 |
| ASRock        | B250M Pro4                  | Desktop     | [9c47ffacd5](https://linux-hardware.org/?probe=9c47ffacd5) | Oct 24, 2018 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [a075fc73d3](https://linux-hardware.org/?probe=a075fc73d3) | Oct 09, 2018 |
| ASUSTek       | X55A                        | Notebook    | [403b1aa1d7](https://linux-hardware.org/?probe=403b1aa1d7) | May 08, 2018 |
| ASUSTek       | K40IJ                       | Notebook    | [24366329c2](https://linux-hardware.org/?probe=24366329c2) | May 07, 2018 |
| ECS           | H55H-3.8L                   | Desktop     | [7e782321c8](https://linux-hardware.org/?probe=7e782321c8) | Mar 31, 2018 |
| Dell          | Inspiron N5110              | Notebook    | [d7b2f7f719](https://linux-hardware.org/?probe=d7b2f7f719) | Oct 05, 2017 |
| ASUSTek       | M2N-MX SE                   | Desktop     | [78791d4918](https://linux-hardware.org/?probe=78791d4918) | Sep 13, 2017 |
| Acer          | Aspire 6530G                | Notebook    | [2f88dba791](https://linux-hardware.org/?probe=2f88dba791) | Aug 13, 2017 |
| ASUSTek       | P8H67                       | Desktop     | [e36d00c6f9](https://linux-hardware.org/?probe=e36d00c6f9) | Jul 21, 2017 |
| HP            | Compaq nx7400 (RH387EA#A... | Notebook    | [116c8bc9de](https://linux-hardware.org/?probe=116c8bc9de) | Jun 03, 2017 |
| Toshiba       | Satellite L855              | Notebook    | [de2e163003](https://linux-hardware.org/?probe=de2e163003) | May 17, 2017 |
| ECS           | nVidia-nForce               | Desktop     | [db8fd734f9](https://linux-hardware.org/?probe=db8fd734f9) | May 16, 2017 |
| HP            | Pavilion dv5                | Notebook    | [3191678465](https://linux-hardware.org/?probe=3191678465) | May 04, 2017 |
| HP            | Pavilion dv5                | Notebook    | [1f21f421ed](https://linux-hardware.org/?probe=1f21f421ed) | May 02, 2017 |
| Quanta        | TWH                         | Notebook    | [4807bd6702](https://linux-hardware.org/?probe=4807bd6702) | Apr 28, 2017 |
| Quanta        | TWH                         | Notebook    | [0105619fb7](https://linux-hardware.org/?probe=0105619fb7) | Apr 27, 2017 |
| Acer          | Aspire 5541                 | Notebook    | [efa45ad21c](https://linux-hardware.org/?probe=efa45ad21c) | Nov 14, 2016 |
| Acer          | Aspire 5541                 | Notebook    | [b61eb7bcb0](https://linux-hardware.org/?probe=b61eb7bcb0) | Nov 13, 2016 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Estonia/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 22.04                 | 33        | 6.19%   |
| Ubuntu 20.04                 | 32        | 6%      |
| Arch Rolling                 | 31        | 5.82%   |
| Ubuntu 18.04                 | 22        | 4.13%   |
| ArcoLinux Rolling            | 12        | 2.25%   |
| Ubuntu 24.04                 | 11        | 2.06%   |
| Debian 12                    | 11        | 2.06%   |
| ROSA R11                     | 10        | 1.88%   |
| Arch                         | 10        | 1.88%   |
| OpenMandriva 4.3             | 9         | 1.69%   |
| Fedora 42                    | 9         | 1.69%   |
| Pop!_OS 22.04                | 8         | 1.5%    |
| Fedora 34                    | 8         | 1.5%    |
| Ubuntu MATE 22.04            | 7         | 1.31%   |
| Ubuntu 19.04                 | 7         | 1.31%   |
| ROSA R8.1                    | 7         | 1.31%   |
| Manjaro                      | 7         | 1.31%   |
| Kubuntu 20.04                | 7         | 1.31%   |
| Debian 11                    | 7         | 1.31%   |
| Zorin 17                     | 6         | 1.13%   |
| Linux Mint 22.2              | 6         | 1.13%   |
| Linux Mint 20.1              | 6         | 1.13%   |
| ROSA 12.2                    | 5         | 0.94%   |
| openSUSE Tumbleweed-XXXXXXXX | 5         | 0.94%   |
| OpenMandriva 4.2             | 5         | 0.94%   |
| Fedora 36                    | 5         | 0.94%   |
| Fedora 35                    | 5         | 0.94%   |
| EndeavourOS Rolling          | 5         | 0.94%   |
| ROSA R9                      | 4         | 0.75%   |
| Linux Mint 21.3              | 4         | 0.75%   |
| Linux Mint 21.2              | 4         | 0.75%   |
| Linux Mint 20.3              | 4         | 0.75%   |
| Kubuntu 22.04                | 4         | 0.75%   |
| KDE neon 20.04               | 4         | 0.75%   |
| Fedora 41                    | 4         | 0.75%   |
| Zorin 16                     | 3         | 0.56%   |
| Ubuntu 21.10                 | 3         | 0.56%   |
| Ubuntu 19.10                 | 3         | 0.56%   |
| ROSA R10                     | 3         | 0.56%   |
| Pop!_OS 24.04                | 3         | 0.56%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 118       | 22.78%  |
| Fedora       | 45        | 8.69%   |
| Arch         | 41        | 7.92%   |
| ROSA         | 35        | 6.76%   |
| Linux Mint   | 35        | 6.76%   |
| OpenMandriva | 33        | 6.37%   |
| Debian       | 29        | 5.6%    |
| Manjaro      | 18        | 3.47%   |
| Pop!_OS      | 16        | 3.09%   |
| Kubuntu      | 16        | 3.09%   |
| Ubuntu MATE  | 12        | 2.32%   |
| ArcoLinux    | 12        | 2.32%   |
| Zorin        | 11        | 2.12%   |
| KDE neon     | 10        | 1.93%   |
| Xubuntu      | 8         | 1.54%   |
| openSUSE     | 7         | 1.35%   |
| Gentoo       | 6         | 1.16%   |
| Elementary   | 6         | 1.16%   |
| Nobara       | 5         | 0.97%   |
| EndeavourOS  | 5         | 0.97%   |
| Bazzite      | 5         | 0.97%   |
| Lubuntu      | 4         | 0.77%   |
| Kali         | 4         | 0.77%   |
| Endless      | 4         | 0.77%   |
| SteamOS      | 3         | 0.58%   |
| Reborn OS    | 3         | 0.58%   |
| NixOS        | 3         | 0.58%   |
| Methaneos    | 3         | 0.58%   |
| Clear Linux  | 3         | 0.58%   |
| MX           | 2         | 0.39%   |
| LMDE         | 2         | 0.39%   |
| Garuda Linux | 2         | 0.39%   |
| ChimeraOS    | 2         | 0.39%   |
| CachyOS      | 2         | 0.39%   |
| ALT Linux    | 2         | 0.39%   |
| Xero         | 1         | 0.19%   |
| Ubuntu Unity | 1         | 0.19%   |
| TUXEDO OS    | 1         | 0.19%   |
| Raspbian     | 1         | 0.19%   |
| Parrot       | 1         | 0.19%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                             | Computers | Percent |
|-------------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003             | 9         | 1.57%   |
| 5.4.0-42-generic                    | 8         | 1.4%    |
| 6.14.2-desktop-3omv2590             | 5         | 0.87%   |
| 6.1.0-13-amd64                      | 5         | 0.87%   |
| 5.15.0-52-generic                   | 5         | 0.87%   |
| 5.10.14-desktop-1omv4002            | 5         | 0.87%   |
| 6.8.0-49-generic                    | 4         | 0.7%    |
| 6.2.0-26-generic                    | 4         | 0.7%    |
| 6.14.0-33-generic                   | 4         | 0.7%    |
| 6.12.9-desktop-1omv2490             | 4         | 0.7%    |
| 5.15.0-53-generic                   | 4         | 0.7%    |
| 4.9.20-nrj-desktop-1rosa-x86_64     | 4         | 0.7%    |
| 6.8.0-87-generic                    | 3         | 0.52%   |
| 6.8.0-60-generic                    | 3         | 0.52%   |
| 6.8.0-52-generic                    | 3         | 0.52%   |
| 6.8.0-41-generic                    | 3         | 0.52%   |
| 6.17.7-ba19.fc43.x86_64             | 3         | 0.52%   |
| 6.14.0-29-generic                   | 3         | 0.52%   |
| 5.4.0-65-generic                    | 3         | 0.52%   |
| 5.4.0-47-generic                    | 3         | 0.52%   |
| 5.4.0-28-generic                    | 3         | 0.52%   |
| 5.15.0-56-generic                   | 3         | 0.52%   |
| 5.10.74-generic-2rosa2021.1-x86_64  | 3         | 0.52%   |
| 5.10.118-generic-2rosa2021.1-x86_64 | 3         | 0.52%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 3         | 0.52%   |
| 6.9.6-methane-jn27                  | 2         | 0.35%   |
| 6.9.3-76060903-generic              | 2         | 0.35%   |
| 6.8.0-51-generic                    | 2         | 0.35%   |
| 6.8.0-45-generic                    | 2         | 0.35%   |
| 6.8.0-31-generic                    | 2         | 0.35%   |
| 6.5.0-9-generic                     | 2         | 0.35%   |
| 6.5.0-45-generic                    | 2         | 0.35%   |
| 6.5.0-35-generic                    | 2         | 0.35%   |
| 6.5.0-14-generic                    | 2         | 0.35%   |
| 6.2.6-desktop-1omv2390              | 2         | 0.35%   |
| 6.2.0-39-generic                    | 2         | 0.35%   |
| 6.15.10-200.fc42.x86_64             | 2         | 0.35%   |
| 6.14.6-300.fc42.x86_64              | 2         | 0.35%   |
| 6.14.0-37-generic                   | 2         | 0.35%   |
| 6.14.0-34-generic                   | 2         | 0.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.4.0    | 48        | 8.62%   |
| 5.15.0   | 35        | 6.28%   |
| 4.15.0   | 27        | 4.85%   |
| 6.8.0    | 26        | 4.67%   |
| 6.5.0    | 16        | 2.87%   |
| 5.11.0   | 15        | 2.69%   |
| 6.14.0   | 14        | 2.51%   |
| 5.13.0   | 12        | 2.15%   |
| 6.1.0    | 11        | 1.97%   |
| 5.8.0    | 11        | 1.97%   |
| 6.2.0    | 10        | 1.8%    |
| 5.0.0    | 10        | 1.8%    |
| 5.16.7   | 9         | 1.62%   |
| 5.10.0   | 8         | 1.44%   |
| 6.17.9   | 6         | 1.08%   |
| 6.11.0   | 6         | 1.08%   |
| 5.3.0    | 6         | 1.08%   |
| 4.18.0   | 6         | 1.08%   |
| 6.2.6    | 5         | 0.9%    |
| 6.14.2   | 5         | 0.9%    |
| 6.12.9   | 5         | 0.9%    |
| 5.19.0   | 5         | 0.9%    |
| 5.10.14  | 5         | 0.9%    |
| 4.9.20   | 5         | 0.9%    |
| 6.9.3    | 4         | 0.72%   |
| 6.17.7   | 4         | 0.72%   |
| 6.14.6   | 3         | 0.54%   |
| 6.13.5   | 3         | 0.54%   |
| 5.15.2   | 3         | 0.54%   |
| 5.13.12  | 3         | 0.54%   |
| 5.10.74  | 3         | 0.54%   |
| 5.10.118 | 3         | 0.54%   |
| 4.9.9    | 3         | 0.54%   |
| 6.9.6    | 2         | 0.36%   |
| 6.6.65   | 2         | 0.36%   |
| 6.6.10   | 2         | 0.36%   |
| 6.5.6    | 2         | 0.36%   |
| 6.17.5   | 2         | 0.36%   |
| 6.16.4   | 2         | 0.36%   |
| 6.15.8   | 2         | 0.36%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 54        | 9.8%    |
| 5.15    | 43        | 7.8%    |
| 6.8     | 29        | 5.26%   |
| 6.1     | 27        | 4.9%    |
| 4.15    | 27        | 4.9%    |
| 5.10    | 26        | 4.72%   |
| 5.13    | 25        | 4.54%   |
| 6.14    | 24        | 4.36%   |
| 5.11    | 20        | 3.63%   |
| 6.5     | 19        | 3.45%   |
| 6.17    | 17        | 3.09%   |
| 6.12    | 17        | 3.09%   |
| 6.11    | 17        | 3.09%   |
| 6.6     | 16        | 2.9%    |
| 6.2     | 16        | 2.9%    |
| 5.8     | 14        | 2.54%   |
| 5.16    | 14        | 2.54%   |
| 4.9     | 14        | 2.54%   |
| 5.0     | 11        | 2%      |
| 6.10    | 9         | 1.63%   |
| 6.0     | 9         | 1.63%   |
| 6.9     | 8         | 1.45%   |
| 6.15    | 8         | 1.45%   |
| 5.3     | 8         | 1.45%   |
| 5.14    | 8         | 1.45%   |
| 5.19    | 7         | 1.27%   |
| 6.16    | 6         | 1.09%   |
| 6.13    | 6         | 1.09%   |
| 5.17    | 6         | 1.09%   |
| 4.18    | 6         | 1.09%   |
| 6.7     | 5         | 0.91%   |
| 4.19    | 5         | 0.91%   |
| 5.9     | 4         | 0.73%   |
| 5.5     | 4         | 0.73%   |
| 5.12    | 4         | 0.73%   |
| 6.4     | 3         | 0.54%   |
| 5.6     | 3         | 0.54%   |
| 5.18    | 3         | 0.54%   |
| 6.3     | 2         | 0.36%   |
| 4.1     | 2         | 0.36%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 485       | 96.81%  |
| i686    | 12        | 2.4%    |
| armv7l  | 3         | 0.6%    |
| aarch64 | 1         | 0.2%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 182       | 34.8%   |
| KDE5          | 77        | 14.72%  |
| Unknown       | 52        | 9.94%   |
| KDE6          | 49        | 9.37%   |
| X-Cinnamon    | 34        | 6.5%    |
| XFCE          | 31        | 5.93%   |
| MATE          | 23        | 4.4%    |
| KDE4          | 20        | 3.82%   |
| KDE           | 9         | 1.72%   |
| LXQt          | 8         | 1.53%   |
| Pantheon      | 6         | 1.15%   |
| i3            | 6         | 1.15%   |
| Hyprland      | 6         | 1.15%   |
| COSMIC        | 3         | 0.57%   |
| Budgie        | 3         | 0.57%   |
| Unity         | 2         | 0.38%   |
| sway          | 2         | 0.38%   |
| niri          | 2         | 0.38%   |
| LXDE          | 2         | 0.38%   |
| awesome       | 2         | 0.38%   |
| Yoyo          | 1         | 0.19%   |
| openbox       | 1         | 0.19%   |
| labwc:wlroots | 1         | 0.19%   |
| Cinnamon      | 1         | 0.19%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 330       | 64.33%  |
| Wayland | 154       | 30.02%  |
| Unknown | 18        | 3.51%   |
| Tty     | 10        | 1.95%   |
| Web     | 1         | 0.19%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 214       | 41.39%  |
| SDDM           | 110       | 21.28%  |
| GDM3           | 60        | 11.61%  |
| LightDM        | 52        | 10.06%  |
| GDM            | 45        | 8.7%    |
| KDM            | 20        | 3.87%   |
| TDM            | 12        | 2.32%   |
| GREETD         | 3         | 0.58%   |
| COSMIC-GREETER | 1         | 0.19%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang            | Computers | Percent |
|-----------------|-----------|---------|
| en_US           | 261       | 51.08%  |
| et_EE           | 74        | 14.48%  |
| Unknown         | 61        | 11.94%  |
| ru_RU           | 43        | 8.41%   |
| en_GB           | 33        | 6.46%   |
| C               | 11        | 2.15%   |
| de_DE           | 6         | 1.17%   |
| pl_PL           | 2         | 0.39%   |
| fr_FR           | 2         | 0.39%   |
| en_IE           | 2         | 0.39%   |
| en_DK           | 2         | 0.39%   |
| C.UTF8          | 2         | 0.39%   |
| uk_UA           | 1         | 0.2%    |
| ru_UA           | 1         | 0.2%    |
| POSIX           | 1         | 0.2%    |
| it_IT           | 1         | 0.2%    |
| es_MX           | 1         | 0.2%    |
| en_US.utf-8     | 1         | 0.2%    |
| en_US.iso885915 | 1         | 0.2%    |
| en_DE           | 1         | 0.2%    |
| en_BW           | 1         | 0.2%    |
| en_AU           | 1         | 0.2%    |
| en_001          | 1         | 0.2%    |
| be_BY@latin     | 1         | 0.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 265       | 51.56%  |
| EFI  | 249       | 48.44%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 332       | 64.72%  |
| Btrfs   | 87        | 16.96%  |
| Overlay | 29        | 5.65%   |
| Tmpfs   | 26        | 5.07%   |
| Unknown | 20        | 3.9%    |
| Zfs     | 9         | 1.75%   |
| Xfs     | 7         | 1.36%   |
| Ext3    | 3         | 0.58%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 245       | 47.85%  |
| Unknown | 209       | 40.82%  |
| MBR     | 58        | 11.33%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 427       | 83.73%  |
| Yes       | 83        | 16.27%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 357       | 69.59%  |
| Yes       | 156       | 30.41%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 111       | 22.16%  |
| ASUSTek Computer        | 70        | 13.97%  |
| Hewlett-Packard         | 64        | 12.77%  |
| Dell                    | 53        | 10.58%  |
| MSI                     | 44        | 8.78%   |
| Gigabyte Technology     | 39        | 7.78%   |
| Intel                   | 16        | 3.19%   |
| ASRock                  | 16        | 3.19%   |
| Apple                   | 12        | 2.4%    |
| Acer                    | 11        | 2.2%    |
| Samsung Electronics     | 9         | 1.8%    |
| Fujitsu                 | 6         | 1.2%    |
| Valve                   | 4         | 0.8%    |
| Notebook                | 4         | 0.8%    |
| ECS                     | 4         | 0.8%    |
| TUXEDO                  | 2         | 0.4%    |
| Toshiba                 | 2         | 0.4%    |
| Timi                    | 2         | 0.4%    |
| Supermicro              | 2         | 0.4%    |
| Raspberry Pi Foundation | 2         | 0.4%    |
| Quanta                  | 2         | 0.4%    |
| HUAWEI                  | 2         | 0.4%    |
| Framework               | 2         | 0.4%    |
| Chuwi                   | 2         | 0.4%    |
| Alienware               | 2         | 0.4%    |
| Unknown                 | 2         | 0.4%    |
| ZOTAC                   | 1         | 0.2%    |
| Prestigio               | 1         | 0.2%    |
| Packard Bell            | 1         | 0.2%    |
| ORIGIMAGIC              | 1         | 0.2%    |
| OEM                     | 1         | 0.2%    |
| mPTech                  | 1         | 0.2%    |
| Microsoft               | 1         | 0.2%    |
| MACHINIST               | 1         | 0.2%    |
| Huanan                  | 1         | 0.2%    |
| GPD                     | 1         | 0.2%    |
| Getac                   | 1         | 0.2%    |
| Fujitsu Siemens         | 1         | 0.2%    |
| Durabook                | 1         | 0.2%    |
| Bananapi                | 1         | 0.2%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Valve Jupiter                        | 4         | 0.8%    |
| MSI MS-7C91                          | 4         | 0.8%    |
| ASUS All Series                      | 4         | 0.8%    |
| HP EliteBook 8470p                   | 3         | 0.6%    |
| HP EliteBook 8460p                   | 3         | 0.6%    |
| Dell Latitude 7490                   | 3         | 0.6%    |
| Unknown                              | 3         | 0.6%    |
| Quanta TWH                           | 2         | 0.4%    |
| MSI MS-7C37                          | 2         | 0.4%    |
| MSI MS-7C02                          | 2         | 0.4%    |
| MSI MS-7758                          | 2         | 0.4%    |
| Lenovo Y50-70 20378                  | 2         | 0.4%    |
| Lenovo ThinkPad T14 Gen 5 21MCS00J00 | 2         | 0.4%    |
| Lenovo IdeaPadFlex 5 14ARE05 81X2    | 2         | 0.4%    |
| Intel NUC8i3BEK                      | 2         | 0.4%    |
| HP ProBook 640 G1                    | 2         | 0.4%    |
| HP Pavilion Gaming Laptop 15-ec1xxx  | 2         | 0.4%    |
| HP Pavilion dv7                      | 2         | 0.4%    |
| HP ENVY Laptop 13-ah0xxx             | 2         | 0.4%    |
| HP EliteBook Folio 1040 G2           | 2         | 0.4%    |
| HP EliteBook 840 G8 Notebook PC      | 2         | 0.4%    |
| HP EliteBook 840 G5                  | 2         | 0.4%    |
| HP EliteBook 840 G2                  | 2         | 0.4%    |
| HP Compaq 8100 Elite SFF PC          | 2         | 0.4%    |
| Gigabyte X570 AORUS PRO              | 2         | 0.4%    |
| Gigabyte Q87M-D2H                    | 2         | 0.4%    |
| Gigabyte 990FXA-UD3                  | 2         | 0.4%    |
| Dell Inspiron N5110                  | 2         | 0.4%    |
| Dell Inspiron 5558                   | 2         | 0.4%    |
| Dell Inspiron 15-3567                | 2         | 0.4%    |
| ASUS ZenBook UX325EA_UX325EA         | 2         | 0.4%    |
| ASUS ROG STRIX B650E-E GAMING WIFI   | 2         | 0.4%    |
| ASUS ROG STRIX B550-F GAMING         | 2         | 0.4%    |
| ASUS PRIME X570-PRO                  | 2         | 0.4%    |
| ASUS PRIME B550M-K                   | 2         | 0.4%    |
| Apple MacBookPro9,2                  | 2         | 0.4%    |
| Alienware 17                         | 2         | 0.4%    |
| ZOTAC B410                           | 1         | 0.2%    |
| TUXEDO Polaris AMD Gen5              | 1         | 0.2%    |
| TUXEDO Book BA1510                   | 1         | 0.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 73        | 14.57%  |
| HP EliteBook       | 21        | 4.19%   |
| Dell Latitude      | 18        | 3.59%   |
| Dell Inspiron      | 11        | 2.2%    |
| ASUS PRIME         | 11        | 2.2%    |
| Lenovo IdeaPad     | 9         | 1.8%    |
| HP Pavilion        | 9         | 1.8%    |
| ASUS ROG           | 9         | 1.8%    |
| Dell XPS           | 8         | 1.6%    |
| HP Compaq          | 7         | 1.4%    |
| ASUS TUF           | 7         | 1.4%    |
| Acer Aspire        | 7         | 1.4%    |
| Dell Precision     | 6         | 1.2%    |
| Lenovo ThinkCentre | 5         | 1%      |
| HP ProBook         | 5         | 1%      |
| Dell OptiPlex      | 5         | 1%      |
| Valve Jupiter      | 4         | 0.8%    |
| MSI MS-7C91        | 4         | 0.8%    |
| Lenovo Legion      | 4         | 0.8%    |
| Gigabyte X570      | 4         | 0.8%    |
| ASUS ZenBook       | 4         | 0.8%    |
| ASUS VivoBook      | 4         | 0.8%    |
| ASUS ASUS          | 4         | 0.8%    |
| ASUS All           | 4         | 0.8%    |
| Lenovo Yoga        | 3         | 0.6%    |
| Lenovo IdeaPadFlex | 3         | 0.6%    |
| HP OMEN            | 3         | 0.6%    |
| HP Laptop          | 3         | 0.6%    |
| HP ENVY            | 3         | 0.6%    |
| HP EliteDesk       | 3         | 0.6%    |
| Fujitsu LIFEBOOK   | 3         | 0.6%    |
| Fujitsu ESPRIMO    | 3         | 0.6%    |
| Apple MacBookPro5  | 3         | 0.6%    |
| Unknown            | 3         | 0.6%    |
| Toshiba Satellite  | 2         | 0.4%    |
| Timi RedmiBook     | 2         | 0.4%    |
| Samsung 900X3C     | 2         | 0.4%    |
| RPi Raspberry      | 2         | 0.4%    |
| Quanta TWH         | 2         | 0.4%    |
| MSI MS-7C37        | 2         | 0.4%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 55        | 10.98%  |
| 2018    | 52        | 10.38%  |
| 2013    | 48        | 9.58%   |
| 2019    | 41        | 8.18%   |
| 2012    | 34        | 6.79%   |
| 2011    | 32        | 6.39%   |
| 2021    | 31        | 6.19%   |
| 2022    | 28        | 5.59%   |
| 2015    | 24        | 4.79%   |
| 2014    | 23        | 4.59%   |
| 2017    | 22        | 4.39%   |
| 2016    | 21        | 4.19%   |
| 2010    | 16        | 3.19%   |
| 2023    | 13        | 2.59%   |
| 2024    | 12        | 2.4%    |
| 2009    | 12        | 2.4%    |
| 2008    | 12        | 2.4%    |
| 2007    | 10        | 2%      |
| 2006    | 6         | 1.2%    |
| Unknown | 4         | 0.8%    |
| 2025    | 2         | 0.4%    |
| 2005    | 2         | 0.4%    |
| 2004    | 1         | 0.2%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 290       | 57.88%  |
| Desktop        | 181       | 36.13%  |
| Convertible    | 12        | 2.4%    |
| Mini pc        | 9         | 1.8%    |
| System on chip | 3         | 0.6%    |
| Tablet         | 2         | 0.4%    |
| All in one     | 2         | 0.4%    |
| Server         | 2         | 0.4%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 473       | 93.66%  |
| Enabled  | 32        | 6.34%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 501       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 115       | 22.68%  |
| 4.01-8.0    | 95        | 18.74%  |
| 8.01-16.0   | 90        | 17.75%  |
| 32.01-64.0  | 75        | 14.79%  |
| 3.01-4.0    | 60        | 11.83%  |
| 24.01-32.0  | 22        | 4.34%   |
| 64.01-256.0 | 22        | 4.34%   |
| 2.01-3.0    | 13        | 2.56%   |
| 1.01-2.0    | 10        | 1.97%   |
| 0.51-1.0    | 3         | 0.59%   |
| 0.01-0.5    | 2         | 0.39%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 129       | 23.76%  |
| 4.01-8.0   | 124       | 22.84%  |
| 2.01-3.0   | 120       | 22.1%   |
| 3.01-4.0   | 73        | 13.44%  |
| 8.01-16.0  | 43        | 7.92%   |
| 0.51-1.0   | 33        | 6.08%   |
| 16.01-24.0 | 9         | 1.66%   |
| 0.01-0.5   | 7         | 1.29%   |
| 24.01-32.0 | 3         | 0.55%   |
| 32.01-64.0 | 2         | 0.37%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 306       | 59.19%  |
| 2      | 118       | 22.82%  |
| 3      | 48        | 9.28%   |
| 4      | 21        | 4.06%   |
| 6      | 10        | 1.93%   |
| 5      | 9         | 1.74%   |
| 0      | 3         | 0.58%   |
| 7      | 2         | 0.39%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 344       | 68.25%  |
| Yes       | 160       | 31.75%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 444       | 87.92%  |
| No        | 61        | 12.08%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 376       | 74.9%   |
| No        | 126       | 25.1%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 327       | 64.62%  |
| No        | 179       | 35.38%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Estonia | 501       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Tallinn       | 311       | 60.15%  |
| Tartu         | 64        | 12.38%  |
| Pärnu        | 18        | 3.48%   |
| Rapla         | 9         | 1.74%   |
| Rakvere       | 8         | 1.55%   |
| Narva         | 8         | 1.55%   |
| Tabasalu      | 6         | 1.16%   |
| Haapsalu      | 6         | 1.16%   |
| Viljandi      | 5         | 0.97%   |
| Saku          | 5         | 0.97%   |
| Maardu        | 5         | 0.97%   |
| Viimsi        | 4         | 0.77%   |
| Tapa          | 4         | 0.77%   |
| Valga         | 3         | 0.58%   |
| Peetrimoisa   | 3         | 0.58%   |
| Paldiski      | 3         | 0.58%   |
| Kuressaare    | 3         | 0.58%   |
| Keila         | 3         | 0.58%   |
| Vinni         | 2         | 0.39%   |
| Türi         | 2         | 0.39%   |
| Sindi         | 2         | 0.39%   |
| Põlva        | 2         | 0.39%   |
| Otepaeae      | 2         | 0.39%   |
| Laagri        | 2         | 0.39%   |
| Kupu          | 2         | 0.39%   |
| Kose          | 2         | 0.39%   |
| Kohtla-Järve | 2         | 0.39%   |
| Kadrina       | 2         | 0.39%   |
| Jõhvi        | 2         | 0.39%   |
| Jaerveotsa    | 2         | 0.39%   |
| Võru         | 1         | 0.19%   |
| Vatla         | 1         | 0.19%   |
| Vaskjala      | 1         | 0.19%   |
| Vaidasoo      | 1         | 0.19%   |
| Torvandi      | 1         | 0.19%   |
| Tila          | 1         | 0.19%   |
| Sillamäe     | 1         | 0.19%   |
| Sauga         | 1         | 0.19%   |
| Reiu          | 1         | 0.19%   |
| Rae Parish    | 1         | 0.19%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 168       | 240    | 22.08%  |
| Seagate                     | 77        | 100    | 10.12%  |
| WDC                         | 68        | 98     | 8.94%   |
| Kingston                    | 57        | 81     | 7.49%   |
| Toshiba                     | 47        | 50     | 6.18%   |
| SanDisk                     | 38        | 44     | 4.99%   |
| Crucial                     | 31        | 42     | 4.07%   |
| SK hynix                    | 26        | 31     | 3.42%   |
| Unknown                     | 22        | 24     | 2.89%   |
| Intel                       | 18        | 22     | 2.37%   |
| Hitachi                     | 18        | 22     | 2.37%   |
| A-DATA Technology           | 15        | 21     | 1.97%   |
| HGST                        | 14        | 18     | 1.84%   |
| Micron Technology           | 13        | 13     | 1.71%   |
| Patriot                     | 11        | 12     | 1.45%   |
| Kingston Technology Company | 11        | 15     | 1.45%   |
| KIOXIA                      | 9         | 12     | 1.18%   |
| China                       | 8         | 8      | 1.05%   |
| Apacer                      | 8         | 9      | 1.05%   |
| ADATA Technology            | 8         | 9      | 1.05%   |
| Phison Electronics          | 6         | 8      | 0.79%   |
| Apple                       | 6         | 6      | 0.79%   |
| SPCC                        | 5         | 7      | 0.66%   |
| Gigabyte Technology         | 5         | 6      | 0.66%   |
| Unknown                     | 5         | 5      | 0.66%   |
| XPG                         | 4         | 4      | 0.53%   |
| Transcend                   | 4         | 7      | 0.53%   |
| KingSpec                    | 4         | 6      | 0.53%   |
| Team                        | 3         | 4      | 0.39%   |
| Netac                       | 3         | 3      | 0.39%   |
| Micron/Crucial Technology   | 3         | 7      | 0.39%   |
| Maxtor                      | 3         | 3      | 0.39%   |
| MAXIO Technology (Hangzhou) | 3         | 3      | 0.39%   |
| Lenovo                      | 3         | 3      | 0.39%   |
| Union Memory (Shenzhen)     | 2         | 2      | 0.26%   |
| Silicon Motion              | 2         | 4      | 0.26%   |
| Plextor                     | 2         | 2      | 0.26%   |
| LITEONIT                    | 2         | 2      | 0.26%   |
| Lexar                       | 2         | 2      | 0.26%   |
| Intenso                     | 2         | 2      | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                              | Computers | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB                  | 20        | 2.37%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB                 | 10        | 1.18%   |
| Samsung SSD 850 EVO 500GB                                          | 8         | 0.95%   |
| Samsung SSD 850 EVO 250GB                                          | 8         | 0.95%   |
| Kingston SA400S37240G 240GB SSD                                    | 8         | 0.95%   |
| Samsung SSD 860 EVO 250GB                                          | 7         | 0.83%   |
| Kingston SA400S37120G 120GB SSD                                    | 7         | 0.83%   |
| Seagate ST2000DM008-2FR102 2TB                                     | 6         | 0.71%   |
| Seagate ST1000DM010-2EP102 1TB                                     | 6         | 0.71%   |
| Samsung NVMe SSD Drive 1TB                                         | 6         | 0.71%   |
| Kingston SA400S37960G 960GB SSD                                    | 5         | 0.59%   |
| Kingston SA400S37480G 480GB SSD                                    | 5         | 0.59%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive 1024GB | 5         | 0.59%   |
| Unknown                                                            | 5         | 0.59%   |
| Toshiba DT01ACA100 1TB                                             | 4         | 0.47%   |
| Seagate ST500LT012-9WS142 500GB                                    | 4         | 0.47%   |
| Samsung SSD 970 EVO Plus 500GB                                     | 4         | 0.47%   |
| Samsung SSD 870 QVO 1TB                                            | 4         | 0.47%   |
| Samsung NVMe SSD Drive 512GB                                       | 4         | 0.47%   |
| Samsung HD103SJ 1TB                                                | 4         | 0.47%   |
| Patriot Burst 480GB SSD                                            | 4         | 0.47%   |
| Kingston Company SNV2S1000G 1TB                                    | 4         | 0.47%   |
| HGST HTS721010A9E630 1TB                                           | 4         | 0.47%   |
| HGST HTS541010A9E680 1TB                                           | 4         | 0.47%   |
| Crucial CT500MX500SSD1 500GB                                       | 4         | 0.47%   |
| Crucial CT1000MX500SSD1 1TB                                        | 4         | 0.47%   |
| Apacer AS350 512GB SSD                                             | 4         | 0.47%   |
| Toshiba HDWD130 3TB                                                | 3         | 0.36%   |
| Toshiba DT01ACA200 2TB                                             | 3         | 0.36%   |
| SK hynix NVMe SSD Drive 256GB                                      | 3         | 0.36%   |
| Seagate ST500LM021-1KJ152 500GB                                    | 3         | 0.36%   |
| Seagate ST500DM002-1BD142 500GB                                    | 3         | 0.36%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                                 | 3         | 0.36%   |
| Samsung SSD 990 PRO 1TB                                            | 3         | 0.36%   |
| Samsung SSD 970 EVO Plus 1TB                                       | 3         | 0.36%   |
| Samsung SSD 960 PRO 512GB                                          | 3         | 0.36%   |
| Samsung SSD 860 EVO 500GB                                          | 3         | 0.36%   |
| Samsung SSD 860 EVO 1TB                                            | 3         | 0.36%   |
| Samsung SSD 840 EVO 250GB                                          | 3         | 0.36%   |
| Samsung SSD 840 EVO 120GB                                          | 3         | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 73        | 96     | 34.43%  |
| WDC                 | 52        | 74     | 24.53%  |
| Toshiba             | 27        | 29     | 12.74%  |
| Samsung Electronics | 18        | 24     | 8.49%   |
| Hitachi             | 18        | 22     | 8.49%   |
| HGST                | 14        | 18     | 6.6%    |
| Maxtor              | 3         | 3      | 1.42%   |
| Fujitsu             | 2         | 2      | 0.94%   |
| Unknown             | 1         | 1      | 0.47%   |
| Synology            | 1         | 1      | 0.47%   |
| JMicron Technology  | 1         | 1      | 0.47%   |
| External            | 1         | 1      | 0.47%   |
| Apple               | 1         | 1      | 0.47%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 87        | 109    | 30.31%  |
| Kingston            | 44        | 62     | 15.33%  |
| Crucial             | 29        | 40     | 10.1%   |
| SanDisk             | 16        | 18     | 5.57%   |
| A-DATA Technology   | 12        | 17     | 4.18%   |
| Patriot             | 10        | 11     | 3.48%   |
| WDC                 | 9         | 13     | 3.14%   |
| China               | 8         | 8      | 2.79%   |
| Apacer              | 8         | 9      | 2.79%   |
| Intel               | 7         | 8      | 2.44%   |
| SK hynix            | 6         | 6      | 2.09%   |
| Toshiba             | 5         | 6      | 1.74%   |
| Micron Technology   | 5         | 5      | 1.74%   |
| Transcend           | 4         | 7      | 1.39%   |
| SPCC                | 4         | 6      | 1.39%   |
| KingSpec            | 4         | 6      | 1.39%   |
| Apple               | 4         | 4      | 1.39%   |
| Team                | 3         | 4      | 1.05%   |
| Netac               | 3         | 3      | 1.05%   |
| Plextor             | 2         | 2      | 0.7%    |
| LITEONIT            | 2         | 2      | 0.7%    |
| Lexar               | 2         | 2      | 0.7%    |
| Intenso             | 2         | 2      | 0.7%    |
| Gigabyte Technology | 2         | 3      | 0.7%    |
| Corsair             | 2         | 2      | 0.7%    |
| ZADAK               | 1         | 1      | 0.35%   |
| XPG                 | 1         | 1      | 0.35%   |
| SHAREVDI            | 1         | 1      | 0.35%   |
| Integral            | 1         | 1      | 0.35%   |
| i-FlashDisk         | 1         | 1      | 0.35%   |
| ASMT                | 1         | 1      | 0.35%   |
| Unknown             | 1         | 1      | 0.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 237       | 362    | 35.85%  |
| NVMe    | 217       | 317    | 32.83%  |
| HDD     | 177       | 273    | 26.78%  |
| MMC     | 20        | 23     | 3.03%   |
| Unknown | 10        | 11     | 1.51%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 339       | 624    | 56.31%  |
| NVMe | 217       | 313    | 36.05%  |
| SAS  | 26        | 26     | 4.32%   |
| MMC  | 20        | 23     | 3.32%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 264       | 401    | 59.73%  |
| 0.51-1.0   | 118       | 157    | 26.7%   |
| 1.01-2.0   | 30        | 38     | 6.79%   |
| 2.01-3.0   | 10        | 18     | 2.26%   |
| 4.01-10.0  | 9         | 10     | 2.04%   |
| 3.01-4.0   | 8         | 8      | 1.81%   |
| 10.01-20.0 | 3         | 3      | 0.68%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 142       | 26.94%  |
| 251-500        | 99        | 18.79%  |
| 501-1000       | 67        | 12.71%  |
| 1-20           | 49        | 9.3%    |
| 1001-2000      | 48        | 9.11%   |
| More than 3000 | 41        | 7.78%   |
| 51-100         | 28        | 5.31%   |
| Unknown        | 23        | 4.36%   |
| 2001-3000      | 18        | 3.42%   |
| 21-50          | 12        | 2.28%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 187       | 34.95%  |
| 21-50          | 88        | 16.45%  |
| 101-250        | 66        | 12.34%  |
| 51-100         | 50        | 9.35%   |
| 251-500        | 39        | 7.29%   |
| 501-1000       | 35        | 6.54%   |
| 1001-2000      | 24        | 4.49%   |
| Unknown        | 23        | 4.3%    |
| More than 3000 | 16        | 2.99%   |
| 2001-3000      | 6         | 1.12%   |
| 0              | 1         | 0.19%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Maxtor STM3250310AS 250GB                    | 2         | 2      | 3.33%   |
| Crucial CT128MX100SSD1 128GB                 | 2         | 3      | 3.33%   |
| WDC WD60EFRX-68MYMN1 6TB                     | 1         | 1      | 1.67%   |
| WDC WD5002AALX-00J37A0 500GB                 | 1         | 1      | 1.67%   |
| WDC WD5000BPVT-00HXZT1 500GB                 | 1         | 1      | 1.67%   |
| WDC WD5000AAKX-00ERMA0 500GB                 | 1         | 1      | 1.67%   |
| WDC WD3200BEVT-22ZCT0 320GB                  | 1         | 1      | 1.67%   |
| WDC WD30EFRX-68EUZN0 3TB                     | 1         | 1      | 1.67%   |
| WDC WD2500BEVT-80A23T0 250GB                 | 1         | 1      | 1.67%   |
| WDC WD20EZRX-00DC0B0 2TB                     | 1         | 2      | 1.67%   |
| WDC WD20EARX-00PASB0 2TB                     | 1         | 1      | 1.67%   |
| WDC WD10PURX-64E5EY0 1TB                     | 1         | 1      | 1.67%   |
| WDC WD10EAVS-00D7B1 1TB                      | 1         | 1      | 1.67%   |
| WDC WD10EADS-00M2B0 1TB                      | 1         | 2      | 1.67%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD     | 1         | 2      | 1.67%   |
| Toshiba MK6475GSX 640GB                      | 1         | 1      | 1.67%   |
| Toshiba MK3261GSYN 320GB                     | 1         | 1      | 1.67%   |
| Toshiba KSG60ZMV512G M.2 2280 512GB SSD      | 1         | 1      | 1.67%   |
| Toshiba DT01ACA200 2TB                       | 1         | 1      | 1.67%   |
| SHAREVDI 256GB SSD                           | 1         | 1      | 1.67%   |
| Seagate ST98823AS 80GB                       | 1         | 1      | 1.67%   |
| Seagate ST9750420AS 752GB                    | 1         | 1      | 1.67%   |
| Seagate ST9320325AS 320GB                    | 1         | 1      | 1.67%   |
| Seagate ST9250315AS 250GB                    | 1         | 1      | 1.67%   |
| Seagate ST9160412AS 160GB                    | 1         | 1      | 1.67%   |
| Seagate ST750LX003-1AC154 752GB              | 1         | 1      | 1.67%   |
| Seagate ST500DM002-1BD142 500GB              | 1         | 1      | 1.67%   |
| Seagate ST340016A 40GB                       | 1         | 2      | 1.67%   |
| Seagate ST320LT012-9WS14C 320GB              | 1         | 1      | 1.67%   |
| Seagate ST31000528AS 1TB                     | 1         | 1      | 1.67%   |
| Seagate ST3000DM008-2DM166 3TB               | 1         | 1      | 1.67%   |
| Seagate ST1000LM035-1RK172 1TB               | 1         | 1      | 1.67%   |
| Seagate ST1000DM010-2EP102 1TB               | 1         | 1      | 1.67%   |
| SanDisk SDSSDX480GG25 480GB                  | 1         | 1      | 1.67%   |
| Samsung Electronics SSD 850 EVO mSATA 1TB    | 1         | 1      | 1.67%   |
| Samsung Electronics SSD 840 PRO Series 128GB | 1         | 1      | 1.67%   |
| Samsung Electronics SP0802N 80GB             | 1         | 1      | 1.67%   |
| Samsung Electronics HD642JJ 640GB            | 1         | 2      | 1.67%   |
| Samsung Electronics HD501LJ 500GB            | 1         | 1      | 1.67%   |
| Samsung Electronics HD103SJ 1TB              | 1         | 1      | 1.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 14     | 22.41%  |
| WDC                 | 11        | 14     | 18.97%  |
| Samsung Electronics | 6         | 8      | 10.34%  |
| Toshiba             | 5         | 6      | 8.62%   |
| Hitachi             | 4         | 4      | 6.9%    |
| Crucial             | 4         | 5      | 6.9%    |
| Kingston            | 3         | 3      | 5.17%   |
| Patriot             | 2         | 2      | 3.45%   |
| Micron Technology   | 2         | 2      | 3.45%   |
| Maxtor              | 2         | 2      | 3.45%   |
| SHAREVDI            | 1         | 1      | 1.72%   |
| SanDisk             | 1         | 1      | 1.72%   |
| Netac               | 1         | 1      | 1.72%   |
| HGST                | 1         | 1      | 1.72%   |
| Fujitsu             | 1         | 1      | 1.72%   |
| A-DATA Technology   | 1         | 1      | 1.72%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 14     | 33.33%  |
| WDC                 | 11        | 14     | 28.21%  |
| Samsung Electronics | 4         | 6      | 10.26%  |
| Hitachi             | 4         | 4      | 10.26%  |
| Toshiba             | 3         | 3      | 7.69%   |
| Maxtor              | 2         | 2      | 5.13%   |
| HGST                | 1         | 1      | 2.56%   |
| Fujitsu             | 1         | 1      | 2.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 36        | 45     | 67.92%  |
| SSD  | 17        | 21     | 32.08%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Samsung Electronics MZ7TY128HDHP-000L1 128GB SSD | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 260       | 506    | 47.53%  |
| Works    | 234       | 413    | 42.78%  |
| Malfunc  | 52        | 66     | 9.51%   |
| Failed   | 1         | 1      | 0.18%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 292       | 43.39%  |
| AMD                                     | 107       | 15.9%   |
| Samsung Electronics                     | 83        | 12.33%  |
| Sandisk                                 | 32        | 4.75%   |
| Kingston Technology Company             | 24        | 3.57%   |
| SK hynix                                | 20        | 2.97%   |
| Toshiba America Info Systems            | 13        | 1.93%   |
| ADATA Technology                        | 13        | 1.93%   |
| Marvell Technology Group                | 11        | 1.63%   |
| KIOXIA                                  | 11        | 1.63%   |
| ASMedia Technology                      | 11        | 1.63%   |
| Phison Electronics                      | 10        | 1.49%   |
| Micron Technology                       | 9         | 1.34%   |
| Nvidia                                  | 8         | 1.19%   |
| Micron/Crucial Technology               | 4         | 0.59%   |
| VIA Technologies                        | 3         | 0.45%   |
| Silicon Motion                          | 3         | 0.45%   |
| MAXIO Technology (Hangzhou)             | 3         | 0.45%   |
| Lenovo                                  | 3         | 0.45%   |
| JMicron Technology                      | 2         | 0.3%    |
| Union Memory (Shenzhen)                 | 1         | 0.15%   |
| Solid State Storage Technology          | 1         | 0.15%   |
| Silicon Image                           | 1         | 0.15%   |
| Shenzhen Unionmemory Information System | 1         | 0.15%   |
| Shenzhen Longsys Electronics            | 1         | 0.15%   |
| Seagate Technology                      | 1         | 0.15%   |
| Realtek Semiconductor                   | 1         | 0.15%   |
| Lite-On IT Corp. / Plextor              | 1         | 0.15%   |
| Hosin Global Electronics                | 1         | 0.15%   |
| Apple                                   | 1         | 0.15%   |
| Adaptec                                 | 1         | 0.15%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 58        | 7.73%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 43        | 5.73%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 36        | 4.8%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 26        | 3.47%   |
| AMD 500 Series Chipset SATA Controller                                         | 20        | 2.67%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 19        | 2.53%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 17        | 2.27%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 14        | 1.87%   |
| AMD 400 Series Chipset SATA Controller                                         | 13        | 1.73%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 12        | 1.6%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 11        | 1.47%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 10        | 1.33%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 10        | 1.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 10        | 1.33%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 10        | 1.33%   |
| Intel Volume Management Device NVMe RAID Controller                            | 9         | 1.2%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 9         | 1.2%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 9         | 1.2%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 9         | 1.2%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 9         | 1.2%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 9         | 1.2%    |
| AMD 600 Series Chipset SATA Controller                                         | 9         | 1.2%    |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 8         | 1.07%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 8         | 1.07%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 8         | 1.07%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 8         | 1.07%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 7         | 0.93%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 7         | 0.93%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 7         | 0.93%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 7         | 0.93%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 7         | 0.93%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 7         | 0.93%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD [E18]                           | 6         | 0.8%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 6         | 0.8%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 6         | 0.8%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 5         | 0.67%   |
| SanDisk WD SN560/SN740/SN770/SN5000 NVMe SSD                                   | 5         | 0.67%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 5         | 0.67%   |
| Intel SSD 660P Series                                                          | 5         | 0.67%   |
| Intel Comet Lake SATA AHCI Controller                                          | 5         | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 365       | 55.56%  |
| NVMe | 219       | 33.33%  |
| IDE  | 48        | 7.31%   |
| RAID | 24        | 3.65%   |
| SCSI | 1         | 0.15%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 348       | 69.46%  |
| AMD                   | 149       | 29.74%  |
| ARM                   | 3         | 0.6%    |
| Marvell Semiconductor | 1         | 0.2%    |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz          | 10        | 1.99%   |
| AMD Ryzen 5 5600X 6-Core Processor         | 8         | 1.59%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz    | 6         | 1.2%    |
| AMD Ryzen 7 3700X 8-Core Processor         | 6         | 1.2%    |
| Intel Core i7-8550U CPU @ 1.80GHz          | 5         | 1%      |
| Intel Core i7-5600U CPU @ 2.60GHz          | 5         | 1%      |
| Intel Core i5-3210M CPU @ 2.50GHz          | 5         | 1%      |
| Intel Core i5-2520M CPU @ 2.50GHz          | 5         | 1%      |
| AMD Ryzen 9 5900X 12-Core Processor        | 5         | 1%      |
| Intel Core i7-8750H CPU @ 2.20GHz          | 4         | 0.8%    |
| Intel Core i7-8565U CPU @ 1.80GHz          | 4         | 0.8%    |
| Intel Core i7-6820HQ CPU @ 2.70GHz         | 4         | 0.8%    |
| Intel Core i5-7300U CPU @ 2.60GHz          | 4         | 0.8%    |
| Intel Core i3-4130 CPU @ 3.40GHz           | 4         | 0.8%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz    | 4         | 0.8%    |
| AMD Ryzen 5 4500U with Radeon Graphics     | 4         | 0.8%    |
| AMD Ryzen 5 3600 6-Core Processor          | 4         | 0.8%    |
| AMD Custom APU 0405                        | 4         | 0.8%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz         | 3         | 0.6%    |
| Intel Core i7-7500U CPU @ 2.70GHz          | 3         | 0.6%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz         | 3         | 0.6%    |
| Intel Core i7-4790 CPU @ 3.60GHz           | 3         | 0.6%    |
| Intel Core i7-4710MQ CPU @ 2.50GHz         | 3         | 0.6%    |
| Intel Core i7-10750H CPU @ 2.60GHz         | 3         | 0.6%    |
| Intel Core i5-8350U CPU @ 1.70GHz          | 3         | 0.6%    |
| Intel Core i5-8265U CPU @ 1.60GHz          | 3         | 0.6%    |
| Intel Core i5-7200U CPU @ 2.50GHz          | 3         | 0.6%    |
| Intel Core i5-6500 CPU @ 3.20GHz           | 3         | 0.6%    |
| Intel Core i5-3320M CPU @ 2.60GHz          | 3         | 0.6%    |
| Intel Core i5-2450M CPU @ 2.50GHz          | 3         | 0.6%    |
| Intel Core i5 CPU M 460 @ 2.53GHz          | 3         | 0.6%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz       | 3         | 0.6%    |
| AMD Ryzen 9 3900X 12-Core Processor        | 3         | 0.6%    |
| AMD Ryzen 7 7840HS w/ Radeon 780M Graphics | 3         | 0.6%    |
| AMD Ryzen 7 5800X3D 8-Core Processor       | 3         | 0.6%    |
| AMD Ryzen 7 5800H with Radeon Graphics     | 3         | 0.6%    |
| AMD Ryzen 7 4800H with Radeon Graphics     | 3         | 0.6%    |
| AMD Ryzen 7 4700U with Radeon Graphics     | 3         | 0.6%    |
| AMD Ryzen 5 PRO 4650U with Radeon Graphics | 3         | 0.6%    |
| AMD Ryzen 5 4600H with Radeon Graphics     | 3         | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 117       | 23.31%  |
| Intel Core i7                  | 94        | 18.73%  |
| Other                          | 46        | 9.16%   |
| AMD Ryzen 7                    | 38        | 7.57%   |
| AMD Ryzen 5                    | 38        | 7.57%   |
| Intel Core i3                  | 28        | 5.58%   |
| Intel Core 2 Duo               | 17        | 3.39%   |
| Intel Celeron                  | 17        | 3.39%   |
| AMD Ryzen 9                    | 16        | 3.19%   |
| AMD Ryzen 7 PRO                | 9         | 1.79%   |
| Intel Xeon                     | 7         | 1.39%   |
| Intel Pentium                  | 7         | 1.39%   |
| AMD FX                         | 6         | 1.2%    |
| Intel Atom                     | 5         | 1%      |
| AMD Ryzen 5 PRO                | 5         | 1%      |
| AMD Phenom II X4               | 4         | 0.8%    |
| AMD Athlon 64 X2               | 4         | 0.8%    |
| Intel Core i9                  | 3         | 0.6%    |
| AMD Ryzen 3 PRO                | 3         | 0.6%    |
| AMD Ryzen 3                    | 3         | 0.6%    |
| AMD A10                        | 3         | 0.6%    |
| Intel Pentium Silver           | 2         | 0.4%    |
| Intel Pentium M                | 2         | 0.4%    |
| Intel Core 2                   | 2         | 0.4%    |
| Intel Celeron Dual-Core        | 2         | 0.4%    |
| AMD A6                         | 2         | 0.4%    |
| AMD A4                         | 2         | 0.4%    |
| Intel Pentium Gold             | 1         | 0.2%    |
| Intel Pentium Dual-Core        | 1         | 0.2%    |
| Intel Pentium Dual             | 1         | 0.2%    |
| Intel Pentium D                | 1         | 0.2%    |
| Intel Pentium 4                | 1         | 0.2%    |
| Intel Genuine                  | 1         | 0.2%    |
| Intel Core M                   | 1         | 0.2%    |
| Intel Core                     | 1         | 0.2%    |
| Intel Celeron M                | 1         | 0.2%    |
| ARM BCM                        | 1         | 0.2%    |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.2%    |
| AMD Turion II Neo              | 1         | 0.2%    |
| AMD Quad-Core                  | 1         | 0.2%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 167       | 33.27%  |
| 4       | 161       | 32.07%  |
| 6       | 64        | 12.75%  |
| 8       | 55        | 10.96%  |
| 12      | 17        | 3.39%   |
| 1       | 12        | 2.39%   |
| 16      | 9         | 1.79%   |
| 10      | 7         | 1.39%   |
| 14      | 5         | 1%      |
| Unknown | 4         | 0.8%    |
| 3       | 1         | 0.2%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 499       | 99.6%   |
| 2       | 1         | 0.2%    |
| Unknown | 1         | 0.2%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 365       | 72.71%  |
| 1       | 133       | 26.49%  |
| Unknown | 4         | 0.8%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 493       | 98.21%  |
| Unknown        | 6         | 1.2%    |
| 32-bit         | 3         | 0.6%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 252       | 48.65%  |
| 0x306c3    | 24        | 4.63%   |
| 0x306a9    | 22        | 4.25%   |
| 0x206a7    | 20        | 3.86%   |
| 0x806ea    | 10        | 1.93%   |
| 0x906e9    | 9         | 1.74%   |
| 0x1067a    | 9         | 1.74%   |
| 0x08600106 | 9         | 1.74%   |
| 0x40651    | 8         | 1.54%   |
| 0x906ea    | 7         | 1.35%   |
| 0x20655    | 7         | 1.35%   |
| 0x08701021 | 7         | 1.35%   |
| 0x806ec    | 6         | 1.16%   |
| 0x806e9    | 6         | 1.16%   |
| 0x806c1    | 6         | 1.16%   |
| 0x506e3    | 6         | 1.16%   |
| 0x306d4    | 6         | 1.16%   |
| 0x6fb      | 5         | 0.97%   |
| 0x08701013 | 5         | 0.97%   |
| 0xa0652    | 4         | 0.77%   |
| 0x6fd      | 4         | 0.77%   |
| 0x08108102 | 4         | 0.77%   |
| 0xa0655    | 3         | 0.58%   |
| 0x90672    | 3         | 0.58%   |
| 0x406e3    | 3         | 0.58%   |
| 0x06000852 | 3         | 0.58%   |
| 0x05000119 | 3         | 0.58%   |
| 0xa0671    | 2         | 0.39%   |
| 0x906ed    | 2         | 0.39%   |
| 0x706a1    | 2         | 0.39%   |
| 0x6d8      | 2         | 0.39%   |
| 0x406c4    | 2         | 0.39%   |
| 0x30678    | 2         | 0.39%   |
| 0x106ca    | 2         | 0.39%   |
| 0x10676    | 2         | 0.39%   |
| 0x0a601206 | 2         | 0.39%   |
| 0x0a50000d | 2         | 0.39%   |
| 0x0a50000c | 2         | 0.39%   |
| 0x08600104 | 2         | 0.39%   |
| 0x08600103 | 2         | 0.39%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 80        | 15.97%  |
| Haswell          | 52        | 10.38%  |
| Unknown          | 47        | 9.38%   |
| Zen 2            | 39        | 7.78%   |
| IvyBridge        | 38        | 7.58%   |
| Zen 3            | 33        | 6.59%   |
| SandyBridge      | 33        | 6.59%   |
| Skylake          | 21        | 4.19%   |
| Broadwell        | 15        | 2.99%   |
| Westmere         | 13        | 2.59%   |
| TigerLake        | 13        | 2.59%   |
| Penryn           | 13        | 2.59%   |
| Core             | 13        | 2.59%   |
| Alderlake Hybrid | 11        | 2.2%    |
| Zen+             | 10        | 2%      |
| CometLake        | 10        | 2%      |
| Piledriver       | 8         | 1.6%    |
| K10              | 7         | 1.4%    |
| Zen              | 6         | 1.2%    |
| Silvermont       | 5         | 1%      |
| Goldmont plus    | 5         | 1%      |
| K8 Hammer        | 4         | 0.8%    |
| IceLake          | 4         | 0.8%    |
| Steamroller      | 3         | 0.6%    |
| Bonnell          | 3         | 0.6%    |
| Bobcat           | 3         | 0.6%    |
| P6               | 2         | 0.4%    |
| NetBurst         | 2         | 0.4%    |
| Excavator        | 2         | 0.4%    |
| Tremont          | 1         | 0.2%    |
| K8 & K10 hybrid  | 1         | 0.2%    |
| K6               | 1         | 0.2%    |
| K10 Llano        | 1         | 0.2%    |
| Jaguar           | 1         | 0.2%    |
| Goldmont         | 1         | 0.2%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 282       | 45.48%  |
| Nvidia            | 193       | 31.13%  |
| AMD               | 142       | 22.9%   |
| ASPEED Technology | 2         | 0.32%   |
| VIA Technologies  | 1         | 0.16%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                            | 24        | 3.75%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 24        | 3.75%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                    | 20        | 3.13%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                 | 20        | 3.13%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 15        | 2.34%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 13        | 2.03%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 12        | 1.88%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                     | 11        | 1.72%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 11        | 1.72%   |
| Intel Core Processor Integrated Graphics Controller                         | 11        | 1.72%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                    | 10        | 1.56%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 9         | 1.41%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 9         | 1.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 8         | 1.25%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 8         | 1.25%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 7         | 1.09%   |
| Intel Skylake-H GT2 [HD Graphics 530]                                       | 7         | 1.09%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 7         | 1.09%   |
| AMD Raphael                                                                 | 7         | 1.09%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 7         | 1.09%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 6         | 0.94%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)         | 6         | 0.94%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)           | 6         | 0.94%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 5         | 0.78%   |
| Nvidia GP108M [GeForce MX150]                                               | 5         | 0.78%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 5         | 0.78%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 5         | 0.78%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                       | 5         | 0.78%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                      | 5         | 0.78%   |
| Intel Kaby Lake-H GT2 [HD Graphics 630]                                     | 5         | 0.78%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 5         | 0.78%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX/7900 GRE/7900M]                     | 5         | 0.78%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 5         | 0.78%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 4         | 0.63%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 4         | 0.63%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 4         | 0.63%   |
| Nvidia GM107GLM [Quadro M2000M]                                             | 4         | 0.63%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 4         | 0.63%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 4         | 0.63%   |
| AMD VanGogh [AMD Custom GPU 0405]                                           | 4         | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 180       | 35.79%  |
| 1 x AMD        | 105       | 20.87%  |
| 1 x Nvidia     | 91        | 18.09%  |
| Intel + Nvidia | 82        | 16.3%   |
| AMD + Nvidia   | 15        | 2.98%   |
| Intel + AMD    | 12        | 2.39%   |
| 2 x AMD        | 7         | 1.39%   |
| Other          | 4         | 0.8%    |
| 2 x Nvidia     | 2         | 0.4%    |
| 2 x Intel      | 2         | 0.4%    |
| AMD + ASPEED   | 2         | 0.4%    |
| 1 x VIA        | 1         | 0.2%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 377       | 73.78%  |
| Proprietary | 107       | 20.94%  |
| Unknown     | 27        | 5.28%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 285       | 55.56%  |
| 1.01-2.0   | 57        | 11.11%  |
| 0.01-0.5   | 48        | 9.36%   |
| 3.01-4.0   | 31        | 6.04%   |
| 0.51-1.0   | 30        | 5.85%   |
| 7.01-8.0   | 26        | 5.07%   |
| 8.01-16.0  | 15        | 2.92%   |
| 5.01-6.0   | 10        | 1.95%   |
| 16.01-24.0 | 7         | 1.36%   |
| 2.01-3.0   | 3         | 0.58%   |
| 4.01-5.0   | 1         | 0.19%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 66        | 11.44%  |
| AU Optronics            | 66        | 11.44%  |
| Samsung Electronics     | 65        | 11.27%  |
| Chimei Innolux          | 52        | 9.01%   |
| LG Display              | 41        | 7.11%   |
| BOE                     | 39        | 6.76%   |
| Goldstar                | 34        | 5.89%   |
| Hewlett-Packard         | 21        | 3.64%   |
| AOC                     | 18        | 3.12%   |
| Lenovo                  | 16        | 2.77%   |
| Philips                 | 14        | 2.43%   |
| Sharp                   | 13        | 2.25%   |
| Chi Mei Optoelectronics | 12        | 2.08%   |
| BenQ                    | 12        | 2.08%   |
| ViewSonic               | 11        | 1.91%   |
| Apple                   | 11        | 1.91%   |
| ASUSTek Computer        | 7         | 1.21%   |
| PANDA                   | 6         | 1.04%   |
| Hitachi                 | 5         | 0.87%   |
| Ancor Communications    | 5         | 0.87%   |
| Sony                    | 4         | 0.69%   |
| LG Philips              | 4         | 0.69%   |
| Gigabyte Technology     | 4         | 0.69%   |
| Acer                    | 4         | 0.69%   |
| Panasonic               | 3         | 0.52%   |
| CSO                     | 3         | 0.52%   |
| Valve                   | 2         | 0.35%   |
| Unknown                 | 2         | 0.35%   |
| RoverScan               | 2         | 0.35%   |
| MSI                     | 2         | 0.35%   |
| LG Electronics          | 2         | 0.35%   |
| Lenovo Group Limited    | 2         | 0.35%   |
| InfoVision              | 2         | 0.35%   |
| Fujitsu Siemens         | 2         | 0.35%   |
| CSOT                    | 2         | 0.35%   |
| CPT                     | 2         | 0.35%   |
| Vestel Elektronik       | 1         | 0.17%   |
| Toshiba                 | 1         | 0.17%   |
| Tech Concepts           | 1         | 0.17%   |
| TCL                     | 1         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 5         | 0.82%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 5         | 0.82%   |
| Hitachi HISENSE HEC0030 3840x2160 1872x1053mm 84.6-inch                  | 4         | 0.66%   |
| Goldstar 27GL850 GSM5B80 2560x1440 697x392mm 31.5-inch                   | 4         | 0.66%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch           | 4         | 0.66%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch           | 4         | 0.66%   |
| Panasonic VVX11F009G00 MEI96A2 1920x1080 344x193mm 15.5-inch             | 3         | 0.49%   |
| Hewlett-Packard 27er HWP3325 1920x1080 598x336mm 27.0-inch               | 3         | 0.49%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 3         | 0.49%   |
| Dell S2721DGF DEL41D9 2560x1440 597x336mm 27.0-inch                      | 3         | 0.49%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 3         | 0.49%   |
| Chi Mei Optoelectronics LCD Monitor CMO1467 1366x768 309x174mm 14.0-inch | 3         | 0.49%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                    | 3         | 0.49%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 3         | 0.49%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 3         | 0.49%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 3         | 0.49%   |
| ViewSonic VA703-4Series VSC6A1E 1280x1024 341x274mm 17.2-inch            | 2         | 0.33%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 2         | 0.33%   |
| Sony TV SNYDB01 1920x1080                                                | 2         | 0.33%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                  | 2         | 0.33%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                  | 2         | 0.33%   |
| Sharp LCD Monitor SHP143B 3840x2160 346x194mm 15.6-inch                  | 2         | 0.33%   |
| Samsung Electronics S32D850 SAM0BCB 2560x1440 710x400mm 32.1-inch        | 2         | 0.33%   |
| Samsung Electronics S24C650 SAM0B18 1920x1200 518x324mm 24.1-inch        | 2         | 0.33%   |
| Samsung Electronics LCD Monitor SEC3046 1366x768 344x193mm 15.5-inch     | 2         | 0.33%   |
| LG Philips LCD Monitor LPL0133 1280x800 304x190mm 14.1-inch              | 2         | 0.33%   |
| LG Display LCD Monitor LGD0685 1920x1080 309x174mm 14.0-inch             | 2         | 0.33%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch              | 2         | 0.33%   |
| LG Display LCD Monitor LGD02DA 1920x1080 382x215mm 17.3-inch             | 2         | 0.33%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch                  | 2         | 0.33%   |
| Lenovo B140UAN02.7 LEN403A 1920x1200 302x188mm 14.0-inch                 | 2         | 0.33%   |
| Hewlett-Packard ZR24w HWP2869 1920x1200 518x324mm 24.1-inch              | 2         | 0.33%   |
| Hewlett-Packard LE2202x HWP2967 1920x1080 480x270mm 21.7-inch            | 2         | 0.33%   |
| Goldstar W2243 GSM56FE 1920x1080 477x269mm 21.6-inch                     | 2         | 0.33%   |
| Goldstar ULTRAWIDE GSM7768 3440x1440 800x334mm 34.1-inch                 | 2         | 0.33%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                     | 2         | 0.33%   |
| Goldstar HDR 4K GSM774F 3840x2160 697x392mm 31.5-inch                    | 2         | 0.33%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 597x336mm 27.0-inch                   | 2         | 0.33%   |
| Dell U2719D DEL415A 2560x1440 597x336mm 27.0-inch                        | 2         | 0.33%   |
| Dell U2518D DEL413A 2560x1440 553x311mm 25.0-inch                        | 2         | 0.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 233       | 42.21%  |
| 1366x768 (WXGA)    | 60        | 10.87%  |
| 3840x2160 (4K)     | 54        | 9.78%   |
| 2560x1440 (QHD)    | 40        | 7.25%   |
| 1920x1200 (WUXGA)  | 37        | 6.7%    |
| 1600x900 (HD+)     | 24        | 4.35%   |
| 1280x1024 (SXGA)   | 23        | 4.17%   |
| 3440x1440          | 16        | 2.9%    |
| 1280x800 (WXGA)    | 13        | 2.36%   |
| 2560x1600          | 10        | 1.81%   |
| 1680x1050 (WSXGA+) | 10        | 1.81%   |
| 1440x900 (WXGA+)   | 9         | 1.63%   |
| 2880x1800          | 4         | 0.72%   |
| 800x1280           | 3         | 0.54%   |
| 3840x1600          | 2         | 0.36%   |
| 2560x1080          | 2         | 0.36%   |
| 1600x1200          | 2         | 0.36%   |
| 3840x2400          | 1         | 0.18%   |
| 3200x1800 (QHD+)   | 1         | 0.18%   |
| 3000x2000          | 1         | 0.18%   |
| 2304x1440          | 1         | 0.18%   |
| 2256x1504          | 1         | 0.18%   |
| 2160x1440          | 1         | 0.18%   |
| 1920x540           | 1         | 0.18%   |
| 1920x1280          | 1         | 0.18%   |
| 1360x768           | 1         | 0.18%   |
| 1024x768 (XGA)     | 1         | 0.18%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 113       | 19.22%  |
| 14      | 63        | 10.71%  |
| 13      | 60        | 10.2%   |
| 24      | 56        | 9.52%   |
| 27      | 52        | 8.84%   |
| 17      | 35        | 5.95%   |
| 21      | 28        | 4.76%   |
| 23      | 26        | 4.42%   |
| 31      | 22        | 3.74%   |
| Unknown | 19        | 3.23%   |
| 34      | 14        | 2.38%   |
| 12      | 13        | 2.21%   |
| 19      | 12        | 2.04%   |
| 16      | 9         | 1.53%   |
| 84      | 8         | 1.36%   |
| 20      | 7         | 1.19%   |
| 40      | 5         | 0.85%   |
| 32      | 5         | 0.85%   |
| 25      | 4         | 0.68%   |
| 18      | 4         | 0.68%   |
| 72      | 3         | 0.51%   |
| 65      | 3         | 0.51%   |
| 22      | 3         | 0.51%   |
| 54      | 2         | 0.34%   |
| 43      | 2         | 0.34%   |
| 37      | 2         | 0.34%   |
| 33      | 2         | 0.34%   |
| 29      | 2         | 0.34%   |
| 28      | 2         | 0.34%   |
| 11      | 2         | 0.34%   |
| 7       | 2         | 0.34%   |
| 86      | 1         | 0.17%   |
| 75      | 1         | 0.17%   |
| 48      | 1         | 0.17%   |
| 38      | 1         | 0.17%   |
| 35      | 1         | 0.17%   |
| 10      | 1         | 0.17%   |
| 9       | 1         | 0.17%   |
| 3       | 1         | 0.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 218       | 38.11%  |
| 501-600     | 121       | 21.15%  |
| 201-300     | 53        | 9.27%   |
| 401-500     | 44        | 7.69%   |
| 601-700     | 32        | 5.59%   |
| 351-400     | 31        | 5.42%   |
| 701-800     | 21        | 3.67%   |
| Unknown     | 19        | 3.32%   |
| 1501-2000   | 12        | 2.1%    |
| 801-900     | 9         | 1.57%   |
| 1001-1500   | 7         | 1.22%   |
| 1-100       | 3         | 0.52%   |
| 901-1000    | 2         | 0.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 365       | 69.79%  |
| 16/10   | 87        | 16.63%  |
| 5/4     | 20        | 3.82%   |
| 21/9    | 17        | 3.25%   |
| Unknown | 17        | 3.25%   |
| 3/2     | 6         | 1.15%   |
| 4/3     | 4         | 0.76%   |
| 6/5     | 3         | 0.57%   |
| 0.67    | 2         | 0.38%   |
| 32/9    | 1         | 0.19%   |
| 0.56    | 1         | 0.19%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 110       | 18.84%  |
| 81-90          | 91        | 15.58%  |
| 201-250        | 71        | 12.16%  |
| 301-350        | 52        | 8.9%    |
| 351-500        | 47        | 8.05%   |
| 251-300        | 40        | 6.85%   |
| 71-80          | 29        | 4.97%   |
| 151-200        | 24        | 4.11%   |
| 121-130        | 20        | 3.42%   |
| More than 1000 | 19        | 3.25%   |
| Unknown        | 19        | 3.25%   |
| 141-150        | 17        | 2.91%   |
| 61-70          | 12        | 2.05%   |
| 111-120        | 12        | 2.05%   |
| 501-1000       | 10        | 1.71%   |
| 1-40           | 3         | 0.51%   |
| 91-100         | 3         | 0.51%   |
| 51-60          | 2         | 0.34%   |
| 41-50          | 2         | 0.34%   |
| 131-140        | 1         | 0.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 176       | 31.1%   |
| 121-160       | 163       | 28.8%   |
| 101-120       | 130       | 22.97%  |
| 161-240       | 54        | 9.54%   |
| Unknown       | 19        | 3.36%   |
| More than 240 | 14        | 2.47%   |
| 1-50          | 10        | 1.77%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 379       | 74.02%  |
| 2     | 103       | 20.12%  |
| 0     | 16        | 3.13%   |
| 3     | 13        | 2.54%   |
| 4     | 1         | 0.2%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 256       | 33.95%  |
| Realtek Semiconductor             | 247       | 32.76%  |
| Qualcomm Atheros                  | 64        | 8.49%   |
| Broadcom                          | 33        | 4.38%   |
| MediaTek                          | 28        | 3.71%   |
| TP-Link                           | 13        | 1.72%   |
| ASIX Electronics                  | 12        | 1.59%   |
| Ralink                            | 8         | 1.06%   |
| Nvidia                            | 8         | 1.06%   |
| Broadcom Limited                  | 8         | 1.06%   |
| Ralink Technology                 | 6         | 0.8%    |
| Sierra Wireless                   | 5         | 0.66%   |
| Lenovo                            | 5         | 0.66%   |
| Fibocom                           | 5         | 0.66%   |
| Ericsson Business Mobile Networks | 5         | 0.66%   |
| Samsung Electronics               | 4         | 0.53%   |
| Qualcomm Technologies             | 4         | 0.53%   |
| Marvell Technology Group          | 4         | 0.53%   |
| Hewlett-Packard                   | 4         | 0.53%   |
| Shenzhen Goodix Technology        | 3         | 0.4%    |
| Microsoft                         | 3         | 0.4%    |
| Qualcomm Atheros Communications   | 2         | 0.27%   |
| Qualcomm                          | 2         | 0.27%   |
| QinHeng Electronics               | 2         | 0.27%   |
| JMicron Technology                | 2         | 0.27%   |
| Huawei Technologies               | 2         | 0.27%   |
| D-Link System                     | 2         | 0.27%   |
| Xiaomi                            | 1         | 0.13%   |
| VIA Technologies                  | 1         | 0.13%   |
| Van Ooijen Technische Informatica | 1         | 0.13%   |
| STMicroelectronics                | 1         | 0.13%   |
| Quectel Wireless Solutions        | 1         | 0.13%   |
| OPPO Electronics                  | 1         | 0.13%   |
| Microchip Technology              | 1         | 0.13%   |
| Mellanox Technologies             | 1         | 0.13%   |
| Insyde Software                   | 1         | 0.13%   |
| Google                            | 1         | 0.13%   |
| Espressif                         | 1         | 0.13%   |
| DisplayLink                       | 1         | 0.13%   |
| D-Link                            | 1         | 0.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 161       | 17.75%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 24        | 2.65%   |
| Intel Wireless 8265 / 8275                                             | 24        | 2.65%   |
| Intel Wi-Fi 6 AX200                                                    | 20        | 2.21%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 20        | 2.21%   |
| Realtek RTL8125 2.5GbE Controller                                      | 19        | 2.09%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 18        | 1.98%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 18        | 1.98%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 15        | 1.65%   |
| Intel Wireless 7260                                                    | 12        | 1.32%   |
| Intel I211 Gigabit Network Connection                                  | 12        | 1.32%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 11        | 1.21%   |
| Intel Wireless 7265                                                    | 11        | 1.21%   |
| Intel Wi-Fi 6 AX201                                                    | 11        | 1.21%   |
| ASIX AX88179 Gigabit Ethernet                                          | 11        | 1.21%   |
| Intel Ethernet Connection I217-LM                                      | 10        | 1.1%    |
| Intel Ethernet Connection (4) I219-V                                   | 10        | 1.1%    |
| Intel Ethernet Connection (4) I219-LM                                  | 10        | 1.1%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 10        | 1.1%    |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]   | 9         | 0.99%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 8         | 0.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 8         | 0.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 8         | 0.88%   |
| Intel Wireless 8260                                                    | 8         | 0.88%   |
| Intel Ethernet Connection (6) I219-V                                   | 8         | 0.88%   |
| Intel Ethernet Connection (3) I218-LM                                  | 8         | 0.88%   |
| Intel Ethernet Connection (2) I219-LM                                  | 8         | 0.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 7         | 0.77%   |
| Intel Ethernet Controller I225-V                                       | 7         | 0.77%   |
| Intel Ethernet Connection (7) I219-V                                   | 7         | 0.77%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 6         | 0.66%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 6         | 0.66%   |
| Intel Wireless 3165                                                    | 6         | 0.66%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 6         | 0.66%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 6         | 0.66%   |
| Intel Ethernet Connection I217-V                                       | 6         | 0.66%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 6         | 0.66%   |
| Intel 82579V Gigabit Network Connection                                | 6         | 0.66%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 5         | 0.55%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 5         | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 190       | 47.62%  |
| Realtek Semiconductor           | 55        | 13.78%  |
| Qualcomm Atheros                | 48        | 12.03%  |
| Broadcom                        | 26        | 6.52%   |
| MediaTek                        | 22        | 5.51%   |
| TP-Link                         | 11        | 2.76%   |
| Ralink                          | 8         | 2.01%   |
| Ralink Technology               | 6         | 1.5%    |
| Sierra Wireless                 | 5         | 1.25%   |
| Fibocom                         | 5         | 1.25%   |
| Broadcom Limited                | 5         | 1.25%   |
| Qualcomm Technologies           | 4         | 1%      |
| Microsoft                       | 3         | 0.75%   |
| Qualcomm Atheros Communications | 2         | 0.5%    |
| Qualcomm                        | 2         | 0.5%    |
| Hewlett-Packard                 | 2         | 0.5%    |
| Quectel Wireless Solutions      | 1         | 0.25%   |
| Marvell Technology Group        | 1         | 0.25%   |
| D-Link System                   | 1         | 0.25%   |
| D-Link                          | 1         | 0.25%   |
| Belkin Components               | 1         | 0.25%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                           | 24        | 5.99%   |
| Intel Wi-Fi 6 AX200                                                  | 20        | 4.99%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 18        | 4.49%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 15        | 3.74%   |
| Intel Wireless 7260                                                  | 12        | 2.99%   |
| Intel Wireless 7265                                                  | 11        | 2.74%   |
| Intel Wi-Fi 6 AX201                                                  | 11        | 2.74%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 10        | 2.49%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330] | 9         | 2.24%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 8         | 2%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 8         | 2%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 8         | 2%      |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 8         | 2%      |
| Intel Wireless 8260                                                  | 8         | 2%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 7         | 1.75%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 6         | 1.5%    |
| Intel Wireless 3165                                                  | 6         | 1.5%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 6         | 1.5%    |
| Intel Raptor Lake PCH CNVi WiFi                                      | 6         | 1.5%    |
| Intel Comet Lake PCH CNVi WiFi                                       | 6         | 1.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 5         | 1.25%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 5         | 1.25%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 5         | 1.25%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                    | 5         | 1.25%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 4         | 1%      |
| Qualcomm WCN785x Wi-Fi 7(802.11be) 320MHz 2x2 [FastConnect 7800]     | 4         | 1%      |
| Intel Wireless 3160                                                  | 4         | 1%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 4         | 1%      |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 4         | 1%      |
| Intel Cannon Lake PCH CNVi WiFi                                      | 4         | 1%      |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 4         | 1%      |
| TP-Link Archer T4U ver.3                                             | 3         | 0.75%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 3         | 0.75%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 3         | 0.75%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 3         | 0.75%   |
| Ralink RT5370 Wireless Adapter                                       | 3         | 0.75%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                            | 3         | 0.75%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 3         | 0.75%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection        | 3         | 0.75%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                | 3         | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 223       | 46.85%  |
| Intel                    | 160       | 33.61%  |
| Qualcomm Atheros         | 23        | 4.83%   |
| Broadcom                 | 13        | 2.73%   |
| ASIX Electronics         | 12        | 2.52%   |
| Nvidia                   | 8         | 1.68%   |
| MediaTek                 | 6         | 1.26%   |
| Samsung Electronics      | 4         | 0.84%   |
| Lenovo                   | 4         | 0.84%   |
| Marvell Technology Group | 3         | 0.63%   |
| Broadcom Limited         | 3         | 0.63%   |
| TP-Link                  | 2         | 0.42%   |
| JMicron Technology       | 2         | 0.42%   |
| Xiaomi                   | 1         | 0.21%   |
| VIA Technologies         | 1         | 0.21%   |
| OPPO Electronics         | 1         | 0.21%   |
| Microchip Technology     | 1         | 0.21%   |
| Mellanox Technologies    | 1         | 0.21%   |
| Insyde Software          | 1         | 0.21%   |
| Hewlett-Packard          | 1         | 0.21%   |
| Google                   | 1         | 0.21%   |
| DisplayLink              | 1         | 0.21%   |
| D-Link System            | 1         | 0.21%   |
| ASUSTek Computer         | 1         | 0.21%   |
| Aquantia                 | 1         | 0.21%   |
| Apple                    | 1         | 0.21%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 161       | 33.06%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 24        | 4.93%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 20        | 4.11%   |
| Realtek RTL8125 2.5GbE Controller                                      | 19        | 3.9%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 18        | 3.7%    |
| Intel I211 Gigabit Network Connection                                  | 12        | 2.46%   |
| ASIX AX88179 Gigabit Ethernet                                          | 11        | 2.26%   |
| Intel Ethernet Connection I217-LM                                      | 10        | 2.05%   |
| Intel Ethernet Connection (4) I219-V                                   | 10        | 2.05%   |
| Intel Ethernet Connection (4) I219-LM                                  | 10        | 2.05%   |
| Intel Ethernet Connection (6) I219-V                                   | 8         | 1.64%   |
| Intel Ethernet Connection (3) I218-LM                                  | 8         | 1.64%   |
| Intel Ethernet Connection (2) I219-LM                                  | 8         | 1.64%   |
| Intel Ethernet Controller I225-V                                       | 7         | 1.44%   |
| Intel Ethernet Connection (7) I219-V                                   | 7         | 1.44%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 6         | 1.23%   |
| Intel Ethernet Connection I217-V                                       | 6         | 1.23%   |
| Intel 82579V Gigabit Network Connection                                | 6         | 1.23%   |
| Intel 82566MM Gigabit Network Connection                               | 5         | 1.03%   |
| Intel Ethernet Connection (2) I219-V                                   | 4         | 0.82%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 4         | 0.82%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 3         | 0.62%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 3         | 0.62%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 3         | 0.62%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 3         | 0.62%   |
| Nvidia MCP79 Ethernet                                                  | 3         | 0.62%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 3         | 0.62%   |
| Intel I210 Gigabit Network Connection                                  | 3         | 0.62%   |
| Intel 82577LM Gigabit Network Connection                               | 3         | 0.62%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 2         | 0.41%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 2         | 0.41%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 2         | 0.41%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 2         | 0.41%   |
| Nvidia CK804 Ethernet Controller                                       | 2         | 0.41%   |
| MediaTek Infinix HOT 50i                                               | 2         | 0.41%   |
| Lenovo ThinkPad TBT3 LAN                                               | 2         | 0.41%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 0.41%   |
| Intel Ethernet Connection (2) I218-V                                   | 2         | 0.41%   |
| Intel Ethernet Connection (13) I219-V                                  | 2         | 0.41%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 2         | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 443       | 52.93%  |
| WiFi     | 376       | 44.92%  |
| Modem    | 18        | 2.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 281       | 54.67%  |
| Ethernet | 233       | 45.33%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 280       | 55.78%  |
| 1     | 203       | 40.44%  |
| 0     | 10        | 1.99%   |
| 3     | 7         | 1.39%   |
| 6     | 1         | 0.2%    |
| 4     | 1         | 0.2%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 401       | 78.32%  |
| Yes  | 111       | 21.68%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 153       | 46.36%  |
| Realtek Semiconductor           | 30        | 9.09%   |
| Qualcomm Atheros Communications | 24        | 7.27%   |
| Cambridge Silicon Radio         | 22        | 6.67%   |
| IMC Networks                    | 19        | 5.76%   |
| Broadcom                        | 17        | 5.15%   |
| Foxconn / Hon Hai               | 15        | 4.55%   |
| Apple                           | 11        | 3.33%   |
| Hewlett-Packard                 | 6         | 1.82%   |
| TP-Link                         | 5         | 1.52%   |
| MediaTek                        | 5         | 1.52%   |
| ASUSTek Computer                | 5         | 1.52%   |
| Realtek                         | 4         | 1.21%   |
| Dell                            | 3         | 0.91%   |
| Toshiba                         | 2         | 0.61%   |
| Lite-On Technology              | 2         | 0.61%   |
| Edimax Technology               | 2         | 0.61%   |
| USI                             | 1         | 0.3%    |
| Ralink                          | 1         | 0.3%    |
| Quectel Wireless Solutions      | 1         | 0.3%    |
| Integrated System Solution      | 1         | 0.3%    |
| Askey Computer                  | 1         | 0.3%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 61        | 18.48%  |
| Intel AX201 Bluetooth                               | 24        | 7.27%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 22        | 6.67%   |
| Realtek Bluetooth Radio                             | 20        | 6.06%   |
| Intel AX200 Bluetooth                               | 17        | 5.15%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 16        | 4.85%   |
| Intel Bluetooth Device                              | 13        | 3.94%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 9         | 2.73%   |
| IMC Networks Bluetooth Radio                        | 8         | 2.42%   |
| Qualcomm Atheros  Bluetooth Device                  | 7         | 2.12%   |
| Intel AX210 Bluetooth                               | 7         | 2.12%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 7         | 2.12%   |
| TP-Link TP-T@- UB500 Adapter                        | 5         | 1.52%   |
| MediaTek Wireless_Device                            | 5         | 1.52%   |
| IMC Networks Bluetooth Device                       | 5         | 1.52%   |
| Foxconn / Hon Hai Wireless_Device                   | 5         | 1.52%   |
| Apple Bluetooth USB Host Controller                 | 5         | 1.52%   |
| Apple Bluetooth Host Controller                     | 5         | 1.52%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 1.21%   |
| Realtek Bluetooth Radio                             | 4         | 1.21%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4         | 1.21%   |
| Intel Wireless-AC 3168 Bluetooth                    | 4         | 1.21%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 4         | 1.21%   |
| IMC Networks Wireless_Device                        | 4         | 1.21%   |
| HP Broadcom 2070 Bluetooth Combo                    | 4         | 1.21%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 4         | 1.21%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 3         | 0.91%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 0.91%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 3         | 0.91%   |
| Foxconn / Hon Hai Bluetooth Device                  | 3         | 0.91%   |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 0.91%   |
| Toshiba Bluetooth USB Host Controller               | 2         | 0.61%   |
| Realtek RTL8723B Bluetooth                          | 2         | 0.61%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 0.61%   |
| Edimax Bluetooth Device                             | 2         | 0.61%   |
| Dell BCM20702A0 Bluetooth Module                    | 2         | 0.61%   |
| Broadcom HP Portable SoftSailing                    | 2         | 0.61%   |
| Broadcom HP Portable Bumble Bee                     | 2         | 0.61%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 2         | 0.61%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 0.61%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 339       | 45.81%  |
| AMD                                  | 170       | 22.97%  |
| Nvidia                               | 138       | 18.65%  |
| C-Media Electronics                  | 10        | 1.35%   |
| Logitech                             | 9         | 1.22%   |
| Kingston Technology                  | 8         | 1.08%   |
| Lenovo                               | 7         | 0.95%   |
| SteelSeries ApS                      | 5         | 0.68%   |
| Razer USA                            | 5         | 0.68%   |
| ASUSTek Computer                     | 5         | 0.68%   |
| TerraTec Electronic                  | 3         | 0.41%   |
| Micro Star International             | 3         | 0.41%   |
| JMTek                                | 3         | 0.41%   |
| Generalplus Technology               | 3         | 0.41%   |
| Creative Labs                        | 3         | 0.41%   |
| Sony                                 | 2         | 0.27%   |
| Realtek Semiconductor                | 2         | 0.27%   |
| KTMicro                              | 2         | 0.27%   |
| Focusrite-Novation                   | 2         | 0.27%   |
| DSEA A/S                             | 2         | 0.27%   |
| VIA Technologies                     | 1         | 0.14%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.14%   |
| Texas Instruments                    | 1         | 0.14%   |
| Syntek                               | 1         | 0.14%   |
| Samson Technologies                  | 1         | 0.14%   |
| Roland                               | 1         | 0.14%   |
| Micronas                             | 1         | 0.14%   |
| Mark of the Unicorn                  | 1         | 0.14%   |
| M-Audio                              | 1         | 0.14%   |
| Hewlett-Packard                      | 1         | 0.14%   |
| GYROCOM C&C                          | 1         | 0.14%   |
| GN Netcom                            | 1         | 0.14%   |
| Giga-Byte Technology                 | 1         | 0.14%   |
| FiiO Electronics Technology          | 1         | 0.14%   |
| Elite Silicon                        | 1         | 0.14%   |
| Dell                                 | 1         | 0.14%   |
| Creative Technology                  | 1         | 0.14%   |
| BEHRINGER International              | 1         | 0.14%   |
| Unknown                              | 1         | 0.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                              | 68        | 7.67%   |
| Intel Sunrise Point-LP HD Audio                                            | 39        | 4.4%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 38        | 4.28%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 37        | 4.17%   |
| AMD Starship/Matisse HD Audio Controller                                   | 36        | 4.06%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 33        | 3.72%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 31        | 3.49%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 25        | 2.82%   |
| AMD Radeon High Definition Audio Controller                                | 22        | 2.48%   |
| Intel Cannon Lake PCH cAVS                                                 | 19        | 2.14%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 15        | 1.69%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 14        | 1.58%   |
| Intel Broadwell-U Audio Controller                                         | 14        | 1.58%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 14        | 1.58%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 13        | 1.47%   |
| Nvidia TU106 High Definition Audio Controller                              | 12        | 1.35%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 12        | 1.35%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 12        | 1.35%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 12        | 1.35%   |
| Nvidia GA104 High Definition Audio Controller                              | 11        | 1.24%   |
| Intel Haswell-ULT HD Audio Controller                                      | 11        | 1.24%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 11        | 1.24%   |
| Intel 8 Series HD Audio Controller                                         | 11        | 1.24%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 10        | 1.13%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 10        | 1.13%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 10        | 1.13%   |
| Nvidia TU116 High Definition Audio Controller                              | 9         | 1.01%   |
| Nvidia GP104 High Definition Audio Controller                              | 9         | 1.01%   |
| AMD FCH Azalia Controller                                                  | 9         | 1.01%   |
| Nvidia GP107GL High Definition Audio Controller                            | 8         | 0.9%    |
| Intel 200 Series PCH HD Audio                                              | 8         | 0.9%    |
| Nvidia GF108 High Definition Audio Controller                              | 7         | 0.79%   |
| Intel Comet Lake PCH cAVS                                                  | 7         | 0.79%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 7         | 0.79%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 6         | 0.68%   |
| Nvidia GK104 HDMI Audio Controller                                         | 6         | 0.68%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 6         | 0.68%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 6         | 0.68%   |
| Kingston Technology HyperX 7.1 Audio                                       | 5         | 0.56%   |
| Intel CM238 HD Audio Controller                                            | 5         | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 81        | 22.88%  |
| SK hynix            | 56        | 15.82%  |
| Kingston            | 49        | 13.84%  |
| Micron Technology   | 34        | 9.6%    |
| G.Skill             | 30        | 8.47%   |
| Unknown             | 27        | 7.63%   |
| Crucial             | 20        | 5.65%   |
| Corsair             | 12        | 3.39%   |
| A-DATA Technology   | 8         | 2.26%   |
| Nanya Technology    | 5         | 1.41%   |
| Elpida              | 5         | 1.41%   |
| Ramaxel Technology  | 4         | 1.13%   |
| Unknown (ABCD)      | 3         | 0.85%   |
| Patriot             | 3         | 0.85%   |
| GOODRAM             | 2         | 0.56%   |
| ASint Technology    | 2         | 0.56%   |
| Apacer              | 2         | 0.56%   |
| Wilk                | 1         | 0.28%   |
| Unifosa             | 1         | 0.28%   |
| Team                | 1         | 0.28%   |
| Silicon Power       | 1         | 0.28%   |
| Qimonda             | 1         | 0.28%   |
| Lexar               | 1         | 0.28%   |
| Kllisre             | 1         | 0.28%   |
| Gigabyte Technology | 1         | 0.28%   |
| AMD                 | 1         | 0.28%   |
| Aeneon              | 1         | 0.28%   |
| Unknown             | 1         | 0.28%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 1.84%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 2400MT/s            | 4         | 1.05%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 1.05%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 1.05%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 0.79%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 0.79%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 3         | 0.79%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 3         | 0.79%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.79%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 3200MT/s            | 3         | 0.79%   |
| G.Skill RAM F4-3200C16-16GIS 16GB DIMM DDR4 3600MT/s             | 3         | 0.79%   |
| Unknown RAM Module 512MB DIMM SDRAM                              | 2         | 0.52%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 2         | 0.52%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 0.52%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.52%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 2667MT/s           | 2         | 0.52%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.52%   |
| SK hynix RAM HMT125U6TFR8C-G7 2GB DIMM DDR3 1067MT/s             | 2         | 0.52%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 2         | 0.52%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.52%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.52%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.52%   |
| Samsung RAM M471B5673FH0-CF8 2048MB SODIMM DDR3 1067MT/s         | 2         | 0.52%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.52%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.52%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 2         | 0.52%   |
| Samsung RAM M471B1G73BH0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.52%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 8400MT/s            | 2         | 0.52%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.52%   |
| Samsung RAM M471A1G44AB0-CWE 8GiB SODIMM DDR4 3200MT/s           | 2         | 0.52%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.52%   |
| Samsung RAM M378B5173DB0-CK0 4096MB DIMM DDR3 1600MT/s           | 2         | 0.52%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s             | 2         | 0.52%   |
| Micron RAM Module 16GB SODIMM DDR4 3200MT/s                      | 2         | 0.52%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s      | 2         | 0.52%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.52%   |
| Micron RAM 16ATF2G64HZ-2G3E1 16GB SODIMM DDR4 2667MT/s           | 2         | 0.52%   |
| Kingston RAM KF560C40-16 16GB DIMM 6000MT/s                      | 2         | 0.52%   |
| Kingston RAM KF556S40-32 32GB SODIMM DDR5 5600MT/s               | 2         | 0.52%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3733MT/s            | 2         | 0.52%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 141       | 46.69%  |
| DDR3    | 93        | 30.79%  |
| DDR5    | 17        | 5.63%   |
| DDR2    | 12        | 3.97%   |
| LPDDR5  | 10        | 3.31%   |
| LPDDR4  | 10        | 3.31%   |
| SDRAM   | 8         | 2.65%   |
| Unknown | 6         | 1.99%   |
| LPDDR3  | 3         | 0.99%   |
| DDR     | 2         | 0.66%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 169       | 57.29%  |
| DIMM         | 111       | 37.63%  |
| Row Of Chips | 15        | 5.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 118       | 35.87%  |
| 4096  | 76        | 23.1%   |
| 16384 | 65        | 19.76%  |
| 2048  | 34        | 10.33%  |
| 32768 | 19        | 5.78%   |
| 1024  | 11        | 3.34%   |
| 512   | 5         | 1.52%   |
| 256   | 1         | 0.3%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 62        | 18.45%  |
| 3200    | 48        | 14.29%  |
| 2667    | 43        | 12.8%   |
| 1333    | 19        | 5.65%   |
| 3600    | 17        | 5.06%   |
| 2400    | 17        | 5.06%   |
| 1334    | 12        | 3.57%   |
| 2133    | 11        | 3.27%   |
| Unknown | 9         | 2.68%   |
| 1067    | 8         | 2.38%   |
| 5600    | 7         | 2.08%   |
| 667     | 7         | 2.08%   |
| 6400    | 6         | 1.79%   |
| 6000    | 6         | 1.79%   |
| 4267    | 6         | 1.79%   |
| 3266    | 4         | 1.19%   |
| 800     | 4         | 1.19%   |
| 8400    | 3         | 0.89%   |
| 7500    | 3         | 0.89%   |
| 4800    | 3         | 0.89%   |
| 3733    | 3         | 0.89%   |
| 3666    | 3         | 0.89%   |
| 2666    | 3         | 0.89%   |
| 1867    | 3         | 0.89%   |
| 4266    | 2         | 0.6%    |
| 4199    | 2         | 0.6%    |
| 4000    | 2         | 0.6%    |
| 3800    | 2         | 0.6%    |
| 3000    | 2         | 0.6%    |
| 1866    | 2         | 0.6%    |
| 1632    | 2         | 0.6%    |
| 533     | 2         | 0.6%    |
| 12800   | 1         | 0.3%    |
| 4133    | 1         | 0.3%    |
| 3466    | 1         | 0.3%    |
| 3334    | 1         | 0.3%    |
| 3333    | 1         | 0.3%    |
| 2933    | 1         | 0.3%    |
| 2800    | 1         | 0.3%    |
| 2733    | 1         | 0.3%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Brother Industries              | 3         | 30%     |
| Samsung Electronics             | 2         | 20%     |
| Seiko Epson                     | 1         | 10%     |
| QinHeng Electronics             | 1         | 10%     |
| Konica Minolta                  | 1         | 10%     |
| Hewlett-Packard                 | 1         | 10%     |
| cab Produkttechnik GmbH & Co KG | 1         | 10%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Seiko Epson Thermal Receipt Printer [TM-T20] | 1         | 10%     |
| Samsung SCX-3400 Series                      | 1         | 10%     |
| Samsung ML-1670 Series                       | 1         | 10%     |
| QinHeng CH340S                               | 1         | 10%     |
| Konica Minolta Printer                       | 1         | 10%     |
| HP Smart Tank 750 series                     | 1         | 10%     |
| cab Produkttechnik GmbH & Co KG EOS2/300     | 1         | 10%     |
| Brother HL-4140CN series                     | 1         | 10%     |
| Brother DCP-L2510D series                    | 1         | 10%     |
| Brother DCP-J152W                            | 1         | 10%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Seiko Epson Perfection 660                          | 1         | 50%     |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO] | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 64        | 22.3%   |
| Microdia                               | 29        | 10.1%   |
| IMC Networks                           | 27        | 9.41%   |
| Bison Electronics                      | 25        | 8.71%   |
| Realtek Semiconductor                  | 19        | 6.62%   |
| Sunplus Innovation Technology          | 18        | 6.27%   |
| Logitech                               | 13        | 4.53%   |
| Lite-On Technology                     | 10        | 3.48%   |
| Apple                                  | 10        | 3.48%   |
| Syntek                                 | 9         | 3.14%   |
| Cheng Uei Precision Industry (Foxlink) | 9         | 3.14%   |
| Luxvisions Innotech Limited            | 8         | 2.79%   |
| Suyin                                  | 7         | 2.44%   |
| Silicon Motion                         | 7         | 2.44%   |
| Quanta                                 | 5         | 1.74%   |
| Samsung Electronics                    | 3         | 1.05%   |
| Lenovo                                 | 3         | 1.05%   |
| Sonix Technology                       | 2         | 0.7%    |
| Microsoft                              | 2         | 0.7%    |
| Arkmicro Technologies                  | 2         | 0.7%    |
| Alcor Micro                            | 2         | 0.7%    |
| Acer                                   | 2         | 0.7%    |
| Z-Star Microelectronics                | 1         | 0.35%   |
| Xinfrared                              | 1         | 0.35%   |
| Xiaomi                                 | 1         | 0.35%   |
| Tripath Technology                     | 1         | 0.35%   |
| Shinetech                              | 1         | 0.35%   |
| Polycom                                | 1         | 0.35%   |
| LG Electronics                         | 1         | 0.35%   |
| Importek                               | 1         | 0.35%   |
| HYGD-XH--241023                        | 1         | 0.35%   |
| Huddly                                 | 1         | 0.35%   |
| Creative Technology                    | 1         | 0.35%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 18        | 6.19%   |
| Microdia Integrated_Webcam_HD                           | 15        | 5.15%   |
| IMC Networks Integrated Camera                          | 11        | 3.78%   |
| Bison Integrated Camera                                 | 9         | 3.09%   |
| Lite-On Integrated Camera                               | 8         | 2.75%   |
| Syntek Integrated Camera                                | 7         | 2.41%   |
| Sunplus Integrated_Webcam_HD                            | 5         | 1.72%   |
| Realtek USB Camera                                      | 5         | 1.72%   |
| Logitech HD Webcam C525                                 | 4         | 1.37%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 4         | 1.37%   |
| Chicony Integrated HP HD Webcam                         | 4         | 1.37%   |
| Chicony HP HD Webcam                                    | 4         | 1.37%   |
| Samsung Galaxy series, misc. (MTP mode)                 | 3         | 1.03%   |
| Realtek Integrated_Webcam_HD                            | 3         | 1.03%   |
| Quanta HP HD Camera                                     | 3         | 1.03%   |
| Microdia Webcam Vitade AF                               | 3         | 1.03%   |
| Luxvisions Innotech Limited Integrated RGB Camera       | 3         | 1.03%   |
| Logitech Webcam C930e                                   | 3         | 1.03%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 3         | 1.03%   |
| Chicony ThinkPad T490 Webcam                            | 3         | 1.03%   |
| Chicony Lenovo Integrated Camera (0.3MP)                | 3         | 1.03%   |
| Chicony HP HD Camera                                    | 3         | 1.03%   |
| Chicony FJ Camera                                       | 3         | 1.03%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                         | 3         | 1.03%   |
| Apple FaceTime HD Camera                                | 3         | 1.03%   |
| Apple Built-in iSight                                   | 3         | 1.03%   |
| Suyin 1.3M HD WebCam                                    | 2         | 0.69%   |
| Sunplus Asus Webcam                                     | 2         | 0.69%   |
| Sonix USB2.0 FHD UVC WebCam                             | 2         | 0.69%   |
| Silicon Motion Webcam SC-13HDL11624N [Namuga Co., Ltd.] | 2         | 0.69%   |
| Realtek USB2.0 HD UVC WebCam                            | 2         | 0.69%   |
| Realtek Lenovo EasyCamera                               | 2         | 0.69%   |
| Realtek Integrated Webcam HD                            | 2         | 0.69%   |
| Microsoft LifeCam HD-3000                               | 2         | 0.69%   |
| Microdia Laptop_Integrated_Webcam_HD                    | 2         | 0.69%   |
| Luxvisions Innotech Limited Integrated Camera           | 2         | 0.69%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 2         | 0.69%   |
| Logitech Webcam C270                                    | 2         | 0.69%   |
| Logitech HD Pro Webcam C920                             | 2         | 0.69%   |
| IMC Networks EasyCamera                                 | 2         | 0.69%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 30        | 38.46%  |
| Synaptics                          | 28        | 35.9%   |
| STMicroelectronics                 | 5         | 6.41%   |
| Shenzhen Goodix Technology         | 5         | 6.41%   |
| Upek                               | 4         | 5.13%   |
| AuthenTec                          | 3         | 3.85%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 1.28%   |
| LighTuning Technology              | 1         | 1.28%   |
| Elan Microelectronics              | 1         | 1.28%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 11        | 14.1%   |
| Validity Sensors VFS495 Fingerprint Reader                      | 8         | 10.26%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 8         | 10.26%  |
| Validity Sensors VFS 5011 fingerprint sensor                    | 5         | 6.41%   |
| STMicroelectronics Fingerprint Reader                           | 5         | 6.41%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor               | 4         | 5.13%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 4         | 5.13%   |
| Validity Sensors VFS471 Fingerprint Reader                      | 3         | 3.85%   |
| Synaptics WBDI                                                  | 3         | 3.85%   |
| Shenzhen Goodix FingerPrint                                     | 3         | 3.85%   |
| Validity Sensors VFS5011 Fingerprint Reader                     | 2         | 2.56%   |
| Validity Sensors VFS491                                         | 2         | 2.56%   |
| Validity Sensors Synaptics WBDI                                 | 2         | 2.56%   |
| Synaptics Prometheus Fingerprint Reader                         | 2         | 2.56%   |
| Shenzhen Goodix  FingerPrint Device                             | 2         | 2.56%   |
| Validity Sensors VFS300 Fingerprint Reader                      | 1         | 1.28%   |
| Validity Sensors VFS101 Fingerprint Reader                      | 1         | 1.28%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor     | 1         | 1.28%   |
| Validity Sensors Fingerprint scanner                            | 1         | 1.28%   |
| Synaptics UWP WBDI Device                                       | 1         | 1.28%   |
| Synaptics UWP WBDI                                              | 1         | 1.28%   |
| Synaptics  WBDI                                                 | 1         | 1.28%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint        | 1         | 1.28%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 1.28%   |
| LighTuning ES603 Swipe Fingerprint Sensor                       | 1         | 1.28%   |
| Elan ELAN:Fingerprint                                           | 1         | 1.28%   |
| AuthenTec AES2810                                               | 1         | 1.28%   |
| AuthenTec AES2550 Fingerprint Sensor                            | 1         | 1.28%   |
| AuthenTec AES2501 Fingerprint Sensor                            | 1         | 1.28%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 43        | 43.43%  |
| OmniKey               | 22        | 22.22%  |
| Broadcom              | 13        | 13.13%  |
| Gemalto (was Gemplus) | 8         | 8.08%   |
| Lenovo                | 6         | 6.06%   |
| Chicony Electronics   | 2         | 2.02%   |
| Upek                  | 1         | 1.01%   |
| SCM Microsystems      | 1         | 1.01%   |
| O2 Micro              | 1         | 1.01%   |
| Clay Logic            | 1         | 1.01%   |
| Aladdin R.D.          | 1         | 1.01%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 36        | 36.36%  |
| OmniKey CardMan 1021                                                         | 19        | 19.19%  |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 7         | 7.07%   |
| Alcor Micro Watchdata W 1981                                                 | 7         | 7.07%   |
| Lenovo Integrated Smart Card Reader                                          | 6         | 6.06%   |
| OmniKey CardMan 4321                                                         | 3         | 3.03%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 3.03%   |
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard)  | 3         | 3.03%   |
| Broadcom 5880                                                                | 3         | 3.03%   |
| Broadcom 58200                                                               | 3         | 3.03%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 2         | 2.02%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 1.01%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 1.01%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 1.01%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.01%   |
| Clay Logic Nitrokey Start                                                    | 1         | 1.01%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 1.01%   |
| Aladdin R.D. JaCarta                                                         | 1         | 1.01%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 323       | 62.84%  |
| 1     | 150       | 29.18%  |
| 2     | 37        | 7.2%    |
| 3     | 3         | 0.58%   |
| 4     | 1         | 0.19%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 77        | 33.33%  |
| Graphics card            | 55        | 23.81%  |
| Chipcard                 | 55        | 23.81%  |
| Multimedia controller    | 13        | 5.63%   |
| Net/wireless             | 6         | 2.6%    |
| Communication controller | 6         | 2.6%    |
| Camera                   | 6         | 2.6%    |
| Card reader              | 5         | 2.16%   |
| Net/ethernet             | 3         | 1.3%    |
| Modem                    | 2         | 0.87%   |
| Storage                  | 1         | 0.43%   |
| Sound                    | 1         | 0.43%   |
| Bluetooth                | 1         | 0.43%   |

