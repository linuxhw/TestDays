Void Linux - Tested Hardware & Statistics
-----------------------------------------

A project to collect tested hardware configurations for Void Linux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Void_Linux/Desktop/README.md) and [notebooks](/Dist/Void_Linux/Notebook/README.md).

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

Total: 288

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T420 4180D81       | Notebook    | [586b69e749](https://linux-hardware.org/?probe=586b69e749) | Apr 23, 2024 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [4113f409f3](https://linux-hardware.org/?probe=4113f409f3) | Apr 22, 2024 |
| Lenovo        | ThinkPad T520 42433ZG       | Notebook    | [d2899d8de6](https://linux-hardware.org/?probe=d2899d8de6) | Apr 19, 2024 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [02724e5adf](https://linux-hardware.org/?probe=02724e5adf) | Apr 15, 2024 |
| ASUSTek       | E402MA                      | Notebook    | [58a1e32393](https://linux-hardware.org/?probe=58a1e32393) | Apr 14, 2024 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [d6d03b4ad2](https://linux-hardware.org/?probe=d6d03b4ad2) | Apr 14, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [4e18f485f3](https://linux-hardware.org/?probe=4e18f485f3) | Apr 11, 2024 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [27c9e47ccc](https://linux-hardware.org/?probe=27c9e47ccc) | Apr 11, 2024 |
| Acer          | E1-510                      | Notebook    | [c53095abd3](https://linux-hardware.org/?probe=c53095abd3) | Apr 10, 2024 |
| Dell          | Latitude 5400               | Notebook    | [20fa0e002d](https://linux-hardware.org/?probe=20fa0e002d) | Mar 23, 2024 |
| ASUSTek       | PRIME Z370-P II             | Desktop     | [09665b9825](https://linux-hardware.org/?probe=09665b9825) | Mar 21, 2024 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [d5c50b0264](https://linux-hardware.org/?probe=d5c50b0264) | Mar 20, 2024 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [14b3cedbef](https://linux-hardware.org/?probe=14b3cedbef) | Mar 18, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [d2152999e9](https://linux-hardware.org/?probe=d2152999e9) | Mar 13, 2024 |
| Gigabyte      | Z97X-UD7 TH-CF              | Desktop     | [3f20fe5386](https://linux-hardware.org/?probe=3f20fe5386) | Mar 13, 2024 |
| ASUSTek       | ROG Maximus Z790 APEX EN... | Desktop     | [b0c33ebfd2](https://linux-hardware.org/?probe=b0c33ebfd2) | Mar 07, 2024 |
| OrangePi      | Zero3                       | Soc         | [a92d36b760](https://linux-hardware.org/?probe=a92d36b760) | Mar 06, 2024 |
| ASUSTek       | ROG Maximus Z790 APEX EN... | Desktop     | [15c45d681f](https://linux-hardware.org/?probe=15c45d681f) | Mar 06, 2024 |
| Lenovo        | ThinkPad T480 20L6S37W04    | Notebook    | [1278612ad9](https://linux-hardware.org/?probe=1278612ad9) | Mar 05, 2024 |
| Raspberry ... | Raspberry Pi Zero 2 W Re... | Soc         | [bf1cfeb779](https://linux-hardware.org/?probe=bf1cfeb779) | Mar 05, 2024 |
| Lenovo        | ThinkPad E590 20NB001AUK    | Notebook    | [45eadbd174](https://linux-hardware.org/?probe=45eadbd174) | Mar 03, 2024 |
| Lenovo        | ThinkBook 14 G5+ ARP 21H... | Notebook    | [b68f17fbdf](https://linux-hardware.org/?probe=b68f17fbdf) | Mar 02, 2024 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [4dd27fbd4e](https://linux-hardware.org/?probe=4dd27fbd4e) | Feb 23, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [7fe3789b7f](https://linux-hardware.org/?probe=7fe3789b7f) | Feb 23, 2024 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | Notebook    | [99f1228781](https://linux-hardware.org/?probe=99f1228781) | Feb 20, 2024 |
| Dell          | Latitude 7420               | Notebook    | [29ce5896a7](https://linux-hardware.org/?probe=29ce5896a7) | Feb 05, 2024 |
| Dell          | Latitude 7420               | Notebook    | [cdd5031988](https://linux-hardware.org/?probe=cdd5031988) | Feb 04, 2024 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [bda104dc07](https://linux-hardware.org/?probe=bda104dc07) | Feb 04, 2024 |
| Gigabyte      | Z790 AORUS MASTER X         | Desktop     | [c35fdb0865](https://linux-hardware.org/?probe=c35fdb0865) | Feb 04, 2024 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | Notebook    | [3cec123511](https://linux-hardware.org/?probe=3cec123511) | Feb 04, 2024 |
| HP            | 2ADE                        | Desktop     | [c98c83ddde](https://linux-hardware.org/?probe=c98c83ddde) | Jan 29, 2024 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | Notebook    | [971c919cef](https://linux-hardware.org/?probe=971c919cef) | Jan 20, 2024 |
| Gigabyte      | Z790 AORUS MASTER X         | Desktop     | [89387d46ef](https://linux-hardware.org/?probe=89387d46ef) | Jan 18, 2024 |
| Gigabyte      | Z790 AORUS MASTER X         | Desktop     | [c1e2f276ba](https://linux-hardware.org/?probe=c1e2f276ba) | Jan 18, 2024 |
| Lenovo        | ThinkBook 14 G5+ ARP 21H... | Notebook    | [78a77e24d1](https://linux-hardware.org/?probe=78a77e24d1) | Jan 14, 2024 |
| Toshiba       | Satellite A200              | Notebook    | [4b6c5e1edb](https://linux-hardware.org/?probe=4b6c5e1edb) | Jan 08, 2024 |
| Dell          | Inspiron N5010              | Notebook    | [cc169dad66](https://linux-hardware.org/?probe=cc169dad66) | Jan 08, 2024 |
| Dell          | 0G919G A00                  | Desktop     | [265aa7e914](https://linux-hardware.org/?probe=265aa7e914) | Jan 04, 2024 |
| ASRock        | B550M Pro4                  | Desktop     | [9eb47b934a](https://linux-hardware.org/?probe=9eb47b934a) | Jan 02, 2024 |
| ASUSTek       | PRIME B660M-A WIFI D4       | Desktop     | [7caa5da564](https://linux-hardware.org/?probe=7caa5da564) | Dec 31, 2023 |
| Acer          | Aspire A515-44              | Notebook    | [b063fdc8bf](https://linux-hardware.org/?probe=b063fdc8bf) | Dec 29, 2023 |
| MSI           | PRO B550M-P GEN3            | Desktop     | [9662ee22d6](https://linux-hardware.org/?probe=9662ee22d6) | Dec 26, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | Notebook    | [4f6ecdc95a](https://linux-hardware.org/?probe=4f6ecdc95a) | Dec 19, 2023 |
| MSI           | GE60 2OC\2OD\2OE            | Notebook    | [cd261e1bc3](https://linux-hardware.org/?probe=cd261e1bc3) | Dec 14, 2023 |
| MSI           | GE60 2OC\2OD\2OE            | Notebook    | [5f97c0d536](https://linux-hardware.org/?probe=5f97c0d536) | Dec 13, 2023 |
| Apple         | Mac-F42787C8 PVT            | All in one  | [e553ac24bf](https://linux-hardware.org/?probe=e553ac24bf) | Dec 10, 2023 |
| ASUSTek       | G750JX                      | Notebook    | [acb5d61dd5](https://linux-hardware.org/?probe=acb5d61dd5) | Dec 08, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [980caec27f](https://linux-hardware.org/?probe=980caec27f) | Dec 03, 2023 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [c6f9c552b6](https://linux-hardware.org/?probe=c6f9c552b6) | Nov 29, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f6d20427d3](https://linux-hardware.org/?probe=f6d20427d3) | Nov 26, 2023 |
| Lenovo        | Ducati 5 82ES               | Notebook    | [04fce2b1b1](https://linux-hardware.org/?probe=04fce2b1b1) | Nov 19, 2023 |
| Lenovo        | Ducati 5 82ES               | Notebook    | [70a8dad823](https://linux-hardware.org/?probe=70a8dad823) | Nov 19, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [7ed36f1817](https://linux-hardware.org/?probe=7ed36f1817) | Nov 18, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f2070cd827](https://linux-hardware.org/?probe=f2070cd827) | Nov 18, 2023 |
| Unknown       | T100                        | Desktop     | [298b8f8764](https://linux-hardware.org/?probe=298b8f8764) | Nov 16, 2023 |
| Razer         | Blade 14 (2022) - RZ09-0... | Notebook    | [426fd54105](https://linux-hardware.org/?probe=426fd54105) | Nov 15, 2023 |
| MSI           | Prestige 15 A10SC           | Notebook    | [a9ff569501](https://linux-hardware.org/?probe=a9ff569501) | Nov 14, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [5e3d94c299](https://linux-hardware.org/?probe=5e3d94c299) | Nov 07, 2023 |
| ASUSTek       | PRIME B550-PLUS AC-HES      | Desktop     | [6a8536f5df](https://linux-hardware.org/?probe=6a8536f5df) | Nov 04, 2023 |
| Supermicro    | X11SCA-F                    | Server      | [e63931ed4f](https://linux-hardware.org/?probe=e63931ed4f) | Nov 04, 2023 |
| Google        | Phaser360                   | Notebook    | [9915a1a3be](https://linux-hardware.org/?probe=9915a1a3be) | Nov 03, 2023 |
| Dell          | 0C27VV A03                  | Desktop     | [3e65f94217](https://linux-hardware.org/?probe=3e65f94217) | Oct 28, 2023 |
| Dell          | Latitude D610               | Notebook    | [270c26c018](https://linux-hardware.org/?probe=270c26c018) | Oct 27, 2023 |
| EVGA          | Z790 DARK KINGPIN.0         | Desktop     | [9faa5f07eb](https://linux-hardware.org/?probe=9faa5f07eb) | Oct 20, 2023 |
| EVGA          | Z790 DARK KINGPIN.0         | Desktop     | [4bec650d3e](https://linux-hardware.org/?probe=4bec650d3e) | Oct 20, 2023 |
| Unknown       | Unknown                     | Notebook    | [93113727fa](https://linux-hardware.org/?probe=93113727fa) | Oct 18, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [b000ad74e9](https://linux-hardware.org/?probe=b000ad74e9) | Oct 14, 2023 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [d96bdeca74](https://linux-hardware.org/?probe=d96bdeca74) | Oct 10, 2023 |
| MSI           | GF63 Thin 10SCXR            | Notebook    | [c63ad78eb4](https://linux-hardware.org/?probe=c63ad78eb4) | Oct 06, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [c074bb832e](https://linux-hardware.org/?probe=c074bb832e) | Oct 06, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [3fcfddc8e9](https://linux-hardware.org/?probe=3fcfddc8e9) | Sep 27, 2023 |
| Acer          | One S1003                   | Tablet      | [dd8e16ad67](https://linux-hardware.org/?probe=dd8e16ad67) | Sep 25, 2023 |
| Acer          | One S1003                   | Tablet      | [02c8574cb0](https://linux-hardware.org/?probe=02c8574cb0) | Sep 25, 2023 |
| HP            | 15                          | Notebook    | [d0ddd6fbc9](https://linux-hardware.org/?probe=d0ddd6fbc9) | Sep 21, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [1e60d905c5](https://linux-hardware.org/?probe=1e60d905c5) | Sep 10, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [1e01a32799](https://linux-hardware.org/?probe=1e01a32799) | Sep 01, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [2322edb05f](https://linux-hardware.org/?probe=2322edb05f) | Aug 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | Notebook    | [417f4d6d5b](https://linux-hardware.org/?probe=417f4d6d5b) | Aug 17, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [179381f376](https://linux-hardware.org/?probe=179381f376) | Aug 12, 2023 |
| Notebook      | NH50_70RA                   | Notebook    | [4f4304a557](https://linux-hardware.org/?probe=4f4304a557) | Aug 06, 2023 |
| Notebook      | NH50_70RA                   | Notebook    | [f86b014869](https://linux-hardware.org/?probe=f86b014869) | Aug 06, 2023 |
| Gigabyte      | X570S UD                    | Desktop     | [dd0cfabd4b](https://linux-hardware.org/?probe=dd0cfabd4b) | Jul 29, 2023 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [14dbf1a55b](https://linux-hardware.org/?probe=14dbf1a55b) | Jul 26, 2023 |
| ASUSTek       | X751LD                      | Notebook    | [de2e3a3ebb](https://linux-hardware.org/?probe=de2e3a3ebb) | Jul 23, 2023 |
| Gigabyte      | Z370 AORUS Gaming 3         | Desktop     | [08d9fe81da](https://linux-hardware.org/?probe=08d9fe81da) | Jul 10, 2023 |
| HP            | 1998                        | Desktop     | [15e8251d36](https://linux-hardware.org/?probe=15e8251d36) | Jul 10, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [798efb2213](https://linux-hardware.org/?probe=798efb2213) | Jun 24, 2023 |
| ASUSTek       | Maximus VIII FORMULA        | Desktop     | [00a862ae7c](https://linux-hardware.org/?probe=00a862ae7c) | Jun 14, 2023 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | Notebook    | [42eab3e3af](https://linux-hardware.org/?probe=42eab3e3af) | Jun 08, 2023 |
| ASUSTek       | PRIME H610M-E D4            | Desktop     | [827f6ecac2](https://linux-hardware.org/?probe=827f6ecac2) | Jun 07, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [45c21cb512](https://linux-hardware.org/?probe=45c21cb512) | May 24, 2023 |
| Acer          | Aspire 4315                 | Notebook    | [8a25a16dfa](https://linux-hardware.org/?probe=8a25a16dfa) | May 22, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [889301578c](https://linux-hardware.org/?probe=889301578c) | Apr 18, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [f06fd87a32](https://linux-hardware.org/?probe=f06fd87a32) | Apr 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [4964eb99e9](https://linux-hardware.org/?probe=4964eb99e9) | Apr 18, 2023 |
| Dell          | Latitude 7490               | Notebook    | [b9a5dadc44](https://linux-hardware.org/?probe=b9a5dadc44) | Apr 05, 2023 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [cba22e109f](https://linux-hardware.org/?probe=cba22e109f) | Mar 23, 2023 |
| Acer          | E1-510                      | Notebook    | [86abc88022](https://linux-hardware.org/?probe=86abc88022) | Mar 06, 2023 |
| HP            | ENVY m7 Notebook            | Notebook    | [88d1b48b0c](https://linux-hardware.org/?probe=88d1b48b0c) | Feb 26, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [d94b8cf0e0](https://linux-hardware.org/?probe=d94b8cf0e0) | Feb 18, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [d77029e5a0](https://linux-hardware.org/?probe=d77029e5a0) | Feb 13, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | Notebook    | [095fa7a182](https://linux-hardware.org/?probe=095fa7a182) | Feb 12, 2023 |
| ASUSTek       | Q325UAR                     | Convertible | [b95d2d4e30](https://linux-hardware.org/?probe=b95d2d4e30) | Feb 02, 2023 |
| Microsoft     | Surface Go 2                | Tablet      | [43ba50f36c](https://linux-hardware.org/?probe=43ba50f36c) | Jan 25, 2023 |
| Lenovo        | B50-80 80EW                 | Notebook    | [61932dd31a](https://linux-hardware.org/?probe=61932dd31a) | Jan 24, 2023 |
| HP            | Stream Notebook PC 11       | Notebook    | [be652213f6](https://linux-hardware.org/?probe=be652213f6) | Jan 19, 2023 |
| HP            | Stream Notebook PC 11       | Notebook    | [f92fcd0382](https://linux-hardware.org/?probe=f92fcd0382) | Jan 19, 2023 |
| MSI           | Summit E13FlipEvo A12MT     | Notebook    | [35024faf2b](https://linux-hardware.org/?probe=35024faf2b) | Jan 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | Notebook    | [3c9f8b612c](https://linux-hardware.org/?probe=3c9f8b612c) | Jan 16, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [a551d228f4](https://linux-hardware.org/?probe=a551d228f4) | Jan 14, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [b9ca7fb340](https://linux-hardware.org/?probe=b9ca7fb340) | Jan 12, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [511306775e](https://linux-hardware.org/?probe=511306775e) | Jan 11, 2023 |
| Lenovo        | B50-80 80EW                 | Notebook    | [7bf9c1c7f4](https://linux-hardware.org/?probe=7bf9c1c7f4) | Jan 10, 2023 |
| MSI           | B550M PRO                   | Desktop     | [61b36bfa2e](https://linux-hardware.org/?probe=61b36bfa2e) | Dec 29, 2022 |
| HP            | Pavilion 15                 | Notebook    | [264e3738ec](https://linux-hardware.org/?probe=264e3738ec) | Dec 29, 2022 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [b30f8a638b](https://linux-hardware.org/?probe=b30f8a638b) | Dec 26, 2022 |
| MSI           | B550M PRO                   | Desktop     | [57f4a4985a](https://linux-hardware.org/?probe=57f4a4985a) | Dec 23, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [64f6471e58](https://linux-hardware.org/?probe=64f6471e58) | Dec 21, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [b01c41faa0](https://linux-hardware.org/?probe=b01c41faa0) | Dec 21, 2022 |
| MSI           | GV72 7RE                    | Notebook    | [74b317d501](https://linux-hardware.org/?probe=74b317d501) | Dec 01, 2022 |
| Lenovo        | ThinkPad T490 20N20046US    | Notebook    | [34882fc8cb](https://linux-hardware.org/?probe=34882fc8cb) | Nov 16, 2022 |
| Toshiba       | Satellite A300D             | Notebook    | [21952b8d66](https://linux-hardware.org/?probe=21952b8d66) | Nov 15, 2022 |
| Lenovo        | Y520-15IKB 80YY             | Notebook    | [626a442179](https://linux-hardware.org/?probe=626a442179) | Nov 06, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [b487c53dfd](https://linux-hardware.org/?probe=b487c53dfd) | Nov 04, 2022 |
| Lenovo        | ThinkPad X201 3680BR4       | Notebook    | [eeeeb33766](https://linux-hardware.org/?probe=eeeeb33766) | Nov 01, 2022 |
| Lenovo        | ThinkPad T420 4236PG6       | Notebook    | [49d423bc50](https://linux-hardware.org/?probe=49d423bc50) | Nov 01, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [001bcba320](https://linux-hardware.org/?probe=001bcba320) | Oct 02, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [a3485b332a](https://linux-hardware.org/?probe=a3485b332a) | Sep 27, 2022 |
| Unknown       | 1.0                         | Notebook    | [f5b0e6a742](https://linux-hardware.org/?probe=f5b0e6a742) | Sep 24, 2022 |
| ASUSTek       | X555LD                      | Notebook    | [08793f9065](https://linux-hardware.org/?probe=08793f9065) | Sep 24, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [68406339d5](https://linux-hardware.org/?probe=68406339d5) | Sep 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [49c235aa0d](https://linux-hardware.org/?probe=49c235aa0d) | Aug 30, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [dcb33e35ae](https://linux-hardware.org/?probe=dcb33e35ae) | Aug 18, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [2f9e03051e](https://linux-hardware.org/?probe=2f9e03051e) | Aug 13, 2022 |
| Exo           | Exomate X352                | Notebook    | [3be8045452](https://linux-hardware.org/?probe=3be8045452) | Aug 02, 2022 |
| ASUSTek       | X455LF                      | Notebook    | [8e83c4492a](https://linux-hardware.org/?probe=8e83c4492a) | Jul 27, 2022 |
| Microsoft     | Surface with Windows RT     | Tablet      | [7e7f71a3c0](https://linux-hardware.org/?probe=7e7f71a3c0) | Jul 23, 2022 |
| Microsoft     | Surface with Windows RT     | Tablet      | [761dd08497](https://linux-hardware.org/?probe=761dd08497) | Jul 23, 2022 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [53fd2c87d2](https://linux-hardware.org/?probe=53fd2c87d2) | Jul 16, 2022 |
| HP            | 3397                        | Desktop     | [7d3b738672](https://linux-hardware.org/?probe=7d3b738672) | Jul 14, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [fa17eccd81](https://linux-hardware.org/?probe=fa17eccd81) | Jul 04, 2022 |
| ASUSTek       | PRIME Z690-P                | Desktop     | [6302e38583](https://linux-hardware.org/?probe=6302e38583) | Jun 22, 2022 |
| Nokia         | Booklet 3G                  | Notebook    | [2f0e1a5bcd](https://linux-hardware.org/?probe=2f0e1a5bcd) | Jun 14, 2022 |
| ASUSTek       | PRIME Z690-P                | Desktop     | [ce610351c3](https://linux-hardware.org/?probe=ce610351c3) | Jun 03, 2022 |
| ASUSTek       | PRIME Z690-P                | Desktop     | [1e0c1bed2a](https://linux-hardware.org/?probe=1e0c1bed2a) | Jun 02, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [758bdaefe9](https://linux-hardware.org/?probe=758bdaefe9) | May 21, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [607d5b3c79](https://linux-hardware.org/?probe=607d5b3c79) | May 14, 2022 |
| Dell          | 0WR7PY A01                  | Desktop     | [9a18a890d4](https://linux-hardware.org/?probe=9a18a890d4) | May 03, 2022 |
| MSI           | Z87-G43                     | Desktop     | [d5612db7ca](https://linux-hardware.org/?probe=d5612db7ca) | May 02, 2022 |
| Lenovo        | ThinkPad T420 4180A21       | Notebook    | [6b5a6e89a2](https://linux-hardware.org/?probe=6b5a6e89a2) | Apr 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [ffdfb3a578](https://linux-hardware.org/?probe=ffdfb3a578) | Apr 29, 2022 |
| Cisco Syst... | 0T38HV A02                  | Server      | [abc0c5402d](https://linux-hardware.org/?probe=abc0c5402d) | Apr 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [55c0ec3653](https://linux-hardware.org/?probe=55c0ec3653) | Apr 29, 2022 |
| Cisco Syst... | 0T38HV A02                  | Server      | [9389a4bd1e](https://linux-hardware.org/?probe=9389a4bd1e) | Apr 29, 2022 |
| ASRock        | X570 Pro4                   | Desktop     | [678366aef2](https://linux-hardware.org/?probe=678366aef2) | Apr 25, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6be9414efd](https://linux-hardware.org/?probe=6be9414efd) | Apr 22, 2022 |
| ASRock        | TRX40 Taichi                | Desktop     | [4a90b659fc](https://linux-hardware.org/?probe=4a90b659fc) | Apr 14, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | Notebook    | [59b9a2cbcb](https://linux-hardware.org/?probe=59b9a2cbcb) | Apr 11, 2022 |
| MSI           | B550M PRO                   | Desktop     | [70e55581b6](https://linux-hardware.org/?probe=70e55581b6) | Mar 24, 2022 |
| HUAWEI        | HN-WX9X                     | Notebook    | [ee3842bc8f](https://linux-hardware.org/?probe=ee3842bc8f) | Mar 20, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [e7d10ddac0](https://linux-hardware.org/?probe=e7d10ddac0) | Mar 04, 2022 |
| HP            | ENVY 6                      | Notebook    | [988417aaa7](https://linux-hardware.org/?probe=988417aaa7) | Feb 25, 2022 |
| ASUSTek       | Q325UAR                     | Convertible | [fc83e5d0b3](https://linux-hardware.org/?probe=fc83e5d0b3) | Feb 21, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [613a6d2320](https://linux-hardware.org/?probe=613a6d2320) | Feb 16, 2022 |
| Lenovo        | ThinkPad T460 20FMS0WN00    | Notebook    | [28be6b9f17](https://linux-hardware.org/?probe=28be6b9f17) | Feb 14, 2022 |
| Lenovo        | ThinkPad T460 20FMS0WN00    | Notebook    | [5819fc1b20](https://linux-hardware.org/?probe=5819fc1b20) | Feb 14, 2022 |
| Framework     | Laptop                      | Notebook    | [24c119ef46](https://linux-hardware.org/?probe=24c119ef46) | Feb 01, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [61374a4048](https://linux-hardware.org/?probe=61374a4048) | Jan 25, 2022 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [298ddd1139](https://linux-hardware.org/?probe=298ddd1139) | Jan 24, 2022 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | Notebook    | [80906dc02b](https://linux-hardware.org/?probe=80906dc02b) | Jan 19, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [3afcc4b1c0](https://linux-hardware.org/?probe=3afcc4b1c0) | Jan 18, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [24fedcca0a](https://linux-hardware.org/?probe=24fedcca0a) | Jan 18, 2022 |
| Lenovo        | ThinkPad X240 20AMA34HMN    | Notebook    | [a4dfbb6e38](https://linux-hardware.org/?probe=a4dfbb6e38) | Jan 10, 2022 |
| HP            | Notebook                    | Notebook    | [3b26596e87](https://linux-hardware.org/?probe=3b26596e87) | Jan 10, 2022 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [8ff352de01](https://linux-hardware.org/?probe=8ff352de01) | Dec 31, 2021 |
| ASUSTek       | X751LD                      | Notebook    | [ce95acc16d](https://linux-hardware.org/?probe=ce95acc16d) | Nov 24, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [efd1c194ac](https://linux-hardware.org/?probe=efd1c194ac) | Nov 11, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [0802656d19](https://linux-hardware.org/?probe=0802656d19) | Nov 11, 2021 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [ae9fd68c7d](https://linux-hardware.org/?probe=ae9fd68c7d) | Nov 04, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [b1dec2f3df](https://linux-hardware.org/?probe=b1dec2f3df) | Oct 28, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [093a7d451a](https://linux-hardware.org/?probe=093a7d451a) | Oct 16, 2021 |
| Lenovo        | ThinkPad X260 20F5S08Q00    | Notebook    | [2929e779ad](https://linux-hardware.org/?probe=2929e779ad) | Oct 15, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [7917f7d57f](https://linux-hardware.org/?probe=7917f7d57f) | Oct 12, 2021 |
| Acer          | Aspire E1-531               | Notebook    | [30d85d7ea1](https://linux-hardware.org/?probe=30d85d7ea1) | Oct 03, 2021 |
| Gigabyte      | H310M M.2 x.x               | Desktop     | [6ad302377d](https://linux-hardware.org/?probe=6ad302377d) | Sep 30, 2021 |
| Acer          | Aspire E1-531               | Notebook    | [9c0d90d6ab](https://linux-hardware.org/?probe=9c0d90d6ab) | Sep 24, 2021 |
| Acer          | Aspire E1-531               | Notebook    | [4cff8ab563](https://linux-hardware.org/?probe=4cff8ab563) | Sep 24, 2021 |
| ASUSTek       | X751LD                      | Notebook    | [efc517d282](https://linux-hardware.org/?probe=efc517d282) | Sep 22, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [b4749d300a](https://linux-hardware.org/?probe=b4749d300a) | Sep 17, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [b9d873983c](https://linux-hardware.org/?probe=b9d873983c) | Sep 17, 2021 |
| Dell          | G3 3579                     | Notebook    | [95182b0267](https://linux-hardware.org/?probe=95182b0267) | Sep 16, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [a0d3015e21](https://linux-hardware.org/?probe=a0d3015e21) | Sep 15, 2021 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [d3c1b5c10c](https://linux-hardware.org/?probe=d3c1b5c10c) | Sep 11, 2021 |
| HP            | Laptop 15-bw0xx             | Notebook    | [11722e3cd0](https://linux-hardware.org/?probe=11722e3cd0) | Sep 04, 2021 |
| MSI           | Bravo 15 A4DDR              | Notebook    | [feddf87464](https://linux-hardware.org/?probe=feddf87464) | Sep 01, 2021 |
| Acer          | Swift SF314-42              | Notebook    | [98c2c3d5ac](https://linux-hardware.org/?probe=98c2c3d5ac) | Aug 24, 2021 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [bc2b986f06](https://linux-hardware.org/?probe=bc2b986f06) | Aug 19, 2021 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [85d1c86c68](https://linux-hardware.org/?probe=85d1c86c68) | Aug 19, 2021 |
| Samsung       | 275E4E/275E5E               | Notebook    | [26f7b81074](https://linux-hardware.org/?probe=26f7b81074) | Aug 17, 2021 |
| Lenovo        | ThinkPad T480 20L6SA5Q00    | Notebook    | [5459bf7337](https://linux-hardware.org/?probe=5459bf7337) | Aug 08, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [e30dac258e](https://linux-hardware.org/?probe=e30dac258e) | Jul 26, 2021 |
| Dell          | 03NVJ6 A02                  | Desktop     | [5dec53ee3f](https://linux-hardware.org/?probe=5dec53ee3f) | Jul 26, 2021 |
| Unknown       | 1.0                         | Notebook    | [d049c76d58](https://linux-hardware.org/?probe=d049c76d58) | Jul 08, 2021 |
| Acer          | Aspire A515-54G             | Notebook    | [4a19b59c46](https://linux-hardware.org/?probe=4a19b59c46) | Jul 06, 2021 |
| Unknown       | Unknown                     | Notebook    | [17aab9510b](https://linux-hardware.org/?probe=17aab9510b) | Jul 05, 2021 |
| Unknown       | 1.0                         | Notebook    | [967654bdb6](https://linux-hardware.org/?probe=967654bdb6) | Jul 04, 2021 |
| Unknown       | 1.0                         | Notebook    | [36977bacbe](https://linux-hardware.org/?probe=36977bacbe) | Jul 03, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [7684808016](https://linux-hardware.org/?probe=7684808016) | Jun 24, 2021 |
| Acer          | Aspire E5-521               | Notebook    | [e1f4843546](https://linux-hardware.org/?probe=e1f4843546) | Jun 16, 2021 |
| ASRock        | J4005B-ITX                  | Desktop     | [053a28a1b7](https://linux-hardware.org/?probe=053a28a1b7) | Jun 13, 2021 |
| Lenovo        | G50-45 80E3                 | Notebook    | [8e075758bf](https://linux-hardware.org/?probe=8e075758bf) | May 29, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [59e32967c4](https://linux-hardware.org/?probe=59e32967c4) | May 26, 2021 |
| HP            | Stream 7 Tablet             | Tablet      | [32c0e61ea7](https://linux-hardware.org/?probe=32c0e61ea7) | May 24, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [bf2d71e7f2](https://linux-hardware.org/?probe=bf2d71e7f2) | May 14, 2021 |
| ASRock        | H61M-VG4                    | Desktop     | [f99a68e64b](https://linux-hardware.org/?probe=f99a68e64b) | May 14, 2021 |
| ASRock        | H61M-VG4                    | Desktop     | [d2a90378bc](https://linux-hardware.org/?probe=d2a90378bc) | May 12, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [0ebae8c8ec](https://linux-hardware.org/?probe=0ebae8c8ec) | Apr 28, 2021 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [c96223f666](https://linux-hardware.org/?probe=c96223f666) | Apr 06, 2021 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [63df5a92c1](https://linux-hardware.org/?probe=63df5a92c1) | Apr 01, 2021 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [9312919fed](https://linux-hardware.org/?probe=9312919fed) | Apr 01, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [42d648695d](https://linux-hardware.org/?probe=42d648695d) | Mar 26, 2021 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [b0e56964ae](https://linux-hardware.org/?probe=b0e56964ae) | Mar 15, 2021 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [adf7976842](https://linux-hardware.org/?probe=adf7976842) | Mar 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [bdedf5a7c7](https://linux-hardware.org/?probe=bdedf5a7c7) | Feb 22, 2021 |
| Unknown       | Unknown                     | Desktop     | [35af7cfd3d](https://linux-hardware.org/?probe=35af7cfd3d) | Feb 22, 2021 |
| ASUSTek       | X510UAR                     | Notebook    | [1888d46194](https://linux-hardware.org/?probe=1888d46194) | Feb 21, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [09b0e87eec](https://linux-hardware.org/?probe=09b0e87eec) | Feb 12, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [5d02f20d1d](https://linux-hardware.org/?probe=5d02f20d1d) | Feb 10, 2021 |
| Lenovo        | ThinkPad T430 2349PS3       | Notebook    | [b7eecfebd0](https://linux-hardware.org/?probe=b7eecfebd0) | Jan 29, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [66e8ed8402](https://linux-hardware.org/?probe=66e8ed8402) | Jan 22, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [d4fcffbd93](https://linux-hardware.org/?probe=d4fcffbd93) | Jan 22, 2021 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [624f71f228](https://linux-hardware.org/?probe=624f71f228) | Jan 21, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [73c3fdc605](https://linux-hardware.org/?probe=73c3fdc605) | Jan 16, 2021 |
| ASUSTek       | PRIME Z270-AR               | Desktop     | [35d08fe710](https://linux-hardware.org/?probe=35d08fe710) | Dec 30, 2020 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [1f66d0eb72](https://linux-hardware.org/?probe=1f66d0eb72) | Dec 22, 2020 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [61887011a6](https://linux-hardware.org/?probe=61887011a6) | Dec 22, 2020 |
| Acer          | Aspire SW5-015              | Notebook    | [e84677b145](https://linux-hardware.org/?probe=e84677b145) | Dec 20, 2020 |
| ASUSTek       | B150M PRO GAMING            | Desktop     | [4d4ec823bb](https://linux-hardware.org/?probe=4d4ec823bb) | Dec 06, 2020 |
| ASUSTek       | B150M PRO GAMING            | Desktop     | [7d1a0b6924](https://linux-hardware.org/?probe=7d1a0b6924) | Dec 02, 2020 |
| Dell          | Inspiron 11 - 3148          | Notebook    | [f9ec6964bb](https://linux-hardware.org/?probe=f9ec6964bb) | Nov 29, 2020 |
| Acer          | Aspire E1-570G              | Notebook    | [d8adc8e3f8](https://linux-hardware.org/?probe=d8adc8e3f8) | Nov 20, 2020 |
| ASUSTek       | H110M-PLUS                  | Desktop     | [09df23b136](https://linux-hardware.org/?probe=09df23b136) | Nov 20, 2020 |
| Acer          | AO722                       | Notebook    | [cee0cf9a99](https://linux-hardware.org/?probe=cee0cf9a99) | Nov 17, 2020 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [438477ec85](https://linux-hardware.org/?probe=438477ec85) | Nov 14, 2020 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [ac5adde915](https://linux-hardware.org/?probe=ac5adde915) | Nov 13, 2020 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [d889341667](https://linux-hardware.org/?probe=d889341667) | Oct 28, 2020 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [e769e1f93a](https://linux-hardware.org/?probe=e769e1f93a) | Oct 24, 2020 |
| HP            | 82C0                        | Mini pc     | [44430304d3](https://linux-hardware.org/?probe=44430304d3) | Oct 19, 2020 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [b50f7a3624](https://linux-hardware.org/?probe=b50f7a3624) | Oct 07, 2020 |
| Acer          | Aspire E5-575G              | Notebook    | [204ef3a0f3](https://linux-hardware.org/?probe=204ef3a0f3) | Oct 02, 2020 |
| Acer          | Aspire A315-55G             | Notebook    | [d24561be9e](https://linux-hardware.org/?probe=d24561be9e) | Oct 01, 2020 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [90d57d39e2](https://linux-hardware.org/?probe=90d57d39e2) | Sep 29, 2020 |
| Dell          | Inspiron 5555               | Notebook    | [a7be8edb39](https://linux-hardware.org/?probe=a7be8edb39) | Sep 28, 2020 |
| MSI           | Z270 TOMAHAWK               | Desktop     | [66f15fef73](https://linux-hardware.org/?probe=66f15fef73) | Sep 28, 2020 |
| Dell          | Inspiron 5555               | Notebook    | [079a8b39a7](https://linux-hardware.org/?probe=079a8b39a7) | Sep 27, 2020 |
| ASUSTek       | P8Z77-V LX2                 | Desktop     | [ee56035e75](https://linux-hardware.org/?probe=ee56035e75) | Sep 24, 2020 |
| Acer          | Nitro AN715-51              | Notebook    | [d375c469b7](https://linux-hardware.org/?probe=d375c469b7) | Sep 16, 2020 |
| Getac         | V110                        | Notebook    | [f0d3292b48](https://linux-hardware.org/?probe=f0d3292b48) | Sep 15, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [1f9434f4c9](https://linux-hardware.org/?probe=1f9434f4c9) | Sep 06, 2020 |
| Acer          | AOA150                      | Notebook    | [f88d38a138](https://linux-hardware.org/?probe=f88d38a138) | Sep 04, 2020 |
| ASUSTek       | P8H67-V                     | Desktop     | [9bc61b31d4](https://linux-hardware.org/?probe=9bc61b31d4) | Sep 02, 2020 |
| Acer          | AO722                       | Notebook    | [816e97376d](https://linux-hardware.org/?probe=816e97376d) | Aug 21, 2020 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [efac4b3e2b](https://linux-hardware.org/?probe=efac4b3e2b) | May 25, 2020 |
| Lenovo        | IdeaPad Z570 10246ZG        | Notebook    | [0a0f078e76](https://linux-hardware.org/?probe=0a0f078e76) | Apr 25, 2020 |
| HP            | 15                          | Notebook    | [66422a127b](https://linux-hardware.org/?probe=66422a127b) | Mar 14, 2020 |
| Dell          | Precision 3530              | Notebook    | [dd006a4ce0](https://linux-hardware.org/?probe=dd006a4ce0) | Mar 07, 2020 |
| Dell          | Latitude E4300              | Notebook    | [c94ae7cddb](https://linux-hardware.org/?probe=c94ae7cddb) | Feb 24, 2020 |
| Dell          | 0H8052                      | Desktop     | [18169ce984](https://linux-hardware.org/?probe=18169ce984) | Jan 29, 2020 |
| Unknown       | Unknown                     | Desktop     | [b9eb4a5652](https://linux-hardware.org/?probe=b9eb4a5652) | Jan 24, 2020 |
| Unknown       | Unknown                     | Desktop     | [ac87dc43f3](https://linux-hardware.org/?probe=ac87dc43f3) | Jan 24, 2020 |
| ASUSTek       | X555UJ                      | Notebook    | [261f8ada0a](https://linux-hardware.org/?probe=261f8ada0a) | Jan 24, 2020 |
| Lenovo        | IdeaPad 710S-13IKB 80VQ     | Notebook    | [faeec47313](https://linux-hardware.org/?probe=faeec47313) | Jan 21, 2020 |
| Lenovo        | IdeaPad 710S-13IKB 80VQ     | Notebook    | [ec79f8e0c6](https://linux-hardware.org/?probe=ec79f8e0c6) | Jan 21, 2020 |
| ASUSTek       | H110M-PLUS                  | Desktop     | [b8c562a7e5](https://linux-hardware.org/?probe=b8c562a7e5) | Dec 23, 2019 |
| Dell          | Inspiron 1501               | Notebook    | [17f0e8e41b](https://linux-hardware.org/?probe=17f0e8e41b) | Dec 03, 2019 |
| HP            | Laptop 14-bs0xx             | Notebook    | [bd6b795d81](https://linux-hardware.org/?probe=bd6b795d81) | Nov 09, 2019 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [3bae5ecb46](https://linux-hardware.org/?probe=3bae5ecb46) | Oct 10, 2019 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [230c0c9bc6](https://linux-hardware.org/?probe=230c0c9bc6) | Oct 01, 2019 |
| Dell          | Latitude 3379               | Notebook    | [e80a21e349](https://linux-hardware.org/?probe=e80a21e349) | Sep 13, 2019 |
| ASRock        | AB350M                      | Desktop     | [1ec4015426](https://linux-hardware.org/?probe=1ec4015426) | Sep 01, 2019 |
| ASRock        | N68-S3 FX                   | Desktop     | [69e86c050b](https://linux-hardware.org/?probe=69e86c050b) | Aug 18, 2019 |
| ASRock        | N68-S3 FX                   | Desktop     | [ef4f02af88](https://linux-hardware.org/?probe=ef4f02af88) | Aug 16, 2019 |
| ASUSTek       | Z97-A                       | Desktop     | [c2458d18f6](https://linux-hardware.org/?probe=c2458d18f6) | Aug 03, 2019 |
| Digibras      | NH4CU03                     | Notebook    | [51273f53df](https://linux-hardware.org/?probe=51273f53df) | Jul 15, 2019 |
| Digibras      | NH4CU03                     | Notebook    | [5ac8c5ff7b](https://linux-hardware.org/?probe=5ac8c5ff7b) | Jun 25, 2019 |
| MSI           | B350M GAMING PRO            | Desktop     | [20e1f5d7a1](https://linux-hardware.org/?probe=20e1f5d7a1) | Apr 17, 2019 |
| Positivo      | Mobile                      | Notebook    | [0267cf3435](https://linux-hardware.org/?probe=0267cf3435) | Mar 27, 2019 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [1b0a4407c7](https://linux-hardware.org/?probe=1b0a4407c7) | Mar 27, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Void Linux Rolling | 171       | 76.68%  |
| Void Linux         | 52        | 23.32%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Void Linux | 220       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version   | Computers | Percent |
|-----------|-----------|---------|
| 6.3.13_1  | 11        | 4.64%   |
| 6.3.12_1  | 9         | 3.8%    |
| 5.13.19_1 | 7         | 2.95%   |
| 6.6.11_1  | 5         | 2.11%   |
| 5.8.18_1  | 5         | 2.11%   |
| 6.6.22_1  | 4         | 1.69%   |
| 6.1.4_1   | 4         | 1.69%   |
| 6.1.31_1  | 4         | 1.69%   |
| 5.3.9_1   | 4         | 1.69%   |
| 5.18.19_1 | 4         | 1.69%   |
| 5.16.20_1 | 4         | 1.69%   |
| 5.10.17_1 | 4         | 1.69%   |
| 6.6.8_1   | 3         | 1.27%   |
| 6.5.13_1  | 3         | 1.27%   |
| 6.5.11_1  | 3         | 1.27%   |
| 5.8.12_1  | 3         | 1.27%   |
| 5.19.17_1 | 3         | 1.27%   |
| 5.18.14_1 | 3         | 1.27%   |
| 5.15.32_1 | 3         | 1.27%   |
| 5.13.13_1 | 3         | 1.27%   |
| 5.12.10_1 | 3         | 1.27%   |
| 6.7.6_1   | 2         | 0.84%   |
| 6.6.9_1   | 2         | 0.84%   |
| 6.6.25_1  | 2         | 0.84%   |
| 6.6.21_1  | 2         | 0.84%   |
| 6.6.1_1   | 2         | 0.84%   |
| 6.6.17_1  | 2         | 0.84%   |
| 6.6.16_1  | 2         | 0.84%   |
| 6.5.9_1   | 2         | 0.84%   |
| 6.5.5_2   | 2         | 0.84%   |
| 6.5.10_1  | 2         | 0.84%   |
| 6.1.21_1  | 2         | 0.84%   |
| 6.1.10_1  | 2         | 0.84%   |
| 6.0.15_1  | 2         | 0.84%   |
| 6.0.13_1  | 2         | 0.84%   |
| 5.9.14_1  | 2         | 0.84%   |
| 5.4.24_1  | 2         | 0.84%   |
| 5.4.13_2  | 2         | 0.84%   |
| 5.19.16_1 | 2         | 0.84%   |
| 5.18.9_1  | 2         | 0.84%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.3.13  | 11        | 4.64%   |
| 6.3.12  | 9         | 3.8%    |
| 5.13.19 | 7         | 2.95%   |
| 6.6.11  | 5         | 2.11%   |
| 5.8.18  | 5         | 2.11%   |
| 6.6.22  | 4         | 1.69%   |
| 6.1.4   | 4         | 1.69%   |
| 6.1.31  | 4         | 1.69%   |
| 5.8.12  | 4         | 1.69%   |
| 5.3.9   | 4         | 1.69%   |
| 5.18.19 | 4         | 1.69%   |
| 5.16.20 | 4         | 1.69%   |
| 5.10.17 | 4         | 1.69%   |
| 6.6.8   | 3         | 1.27%   |
| 6.5.13  | 3         | 1.27%   |
| 6.5.11  | 3         | 1.27%   |
| 5.19.17 | 3         | 1.27%   |
| 5.18.14 | 3         | 1.27%   |
| 5.15.32 | 3         | 1.27%   |
| 5.13.13 | 3         | 1.27%   |
| 5.12.10 | 3         | 1.27%   |
| 6.8.0   | 2         | 0.84%   |
| 6.7.6   | 2         | 0.84%   |
| 6.6.9   | 2         | 0.84%   |
| 6.6.25  | 2         | 0.84%   |
| 6.6.21  | 2         | 0.84%   |
| 6.6.17  | 2         | 0.84%   |
| 6.6.16  | 2         | 0.84%   |
| 6.6.1   | 2         | 0.84%   |
| 6.5.9   | 2         | 0.84%   |
| 6.5.5   | 2         | 0.84%   |
| 6.5.10  | 2         | 0.84%   |
| 6.1.21  | 2         | 0.84%   |
| 6.1.10  | 2         | 0.84%   |
| 6.0.15  | 2         | 0.84%   |
| 6.0.13  | 2         | 0.84%   |
| 5.9.14  | 2         | 0.84%   |
| 5.4.24  | 2         | 0.84%   |
| 5.4.13  | 2         | 0.84%   |
| 5.19.16 | 2         | 0.84%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.6     | 25        | 10.68%  |
| 5.15    | 24        | 10.26%  |
| 6.3     | 20        | 8.55%   |
| 6.1     | 20        | 8.55%   |
| 5.8     | 18        | 7.69%   |
| 5.13    | 16        | 6.84%   |
| 6.5     | 15        | 6.41%   |
| 5.10    | 15        | 6.41%   |
| 5.18    | 12        | 5.13%   |
| 5.12    | 9         | 3.85%   |
| 5.4     | 7         | 2.99%   |
| 6.0     | 6         | 2.56%   |
| 6.8     | 5         | 2.14%   |
| 5.3     | 5         | 2.14%   |
| 5.19    | 5         | 2.14%   |
| 5.11    | 5         | 2.14%   |
| 5.9     | 4         | 1.71%   |
| 5.16    | 4         | 1.71%   |
| 4.19    | 4         | 1.71%   |
| 6.7     | 3         | 1.28%   |
| 6.2     | 2         | 0.85%   |
| 6.9     | 1         | 0.43%   |
| 6.4     | 1         | 0.43%   |
| 5.7     | 1         | 0.43%   |
| 5.6     | 1         | 0.43%   |
| 5.2     | 1         | 0.43%   |
| 5.17    | 1         | 0.43%   |
| 5.14    | 1         | 0.43%   |
| 5.1     | 1         | 0.43%   |
| 4.4     | 1         | 0.43%   |
| 4.14    | 1         | 0.43%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 205       | 93.18%  |
| i686    | 7         | 3.18%   |
| aarch64 | 5         | 2.27%   |
| ppc64le | 1         | 0.45%   |
| ppc64   | 1         | 0.45%   |
| armv7l  | 1         | 0.45%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Unknown           | 92        | 40.35%  |
| XFCE              | 36        | 15.79%  |
| KDE5              | 20        | 8.77%   |
| KDE               | 14        | 6.14%   |
| GNOME             | 13        | 5.7%    |
| sway              | 10        | 4.39%   |
| MATE              | 9         | 3.95%   |
| i3                | 7         | 3.07%   |
| X-Cinnamon        | 5         | 2.19%   |
| bspwm             | 4         | 1.75%   |
| awesome           | 4         | 1.75%   |
| openbox           | 3         | 1.32%   |
| X-Generic         | 2         | 0.88%   |
| Lumina            | 2         | 0.88%   |
| river             | 1         | 0.44%   |
| LXQt              | 1         | 0.44%   |
| LXDE              | 1         | 0.44%   |
| Hyprland          | 1         | 0.44%   |
| dwm               | 1         | 0.44%   |
| dot-xsession      | 1         | 0.44%   |
| awesome-with-dbus | 1         | 0.44%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 147       | 65.33%  |
| Wayland | 36        | 16%     |
| Tty     | 26        | 11.56%  |
| Unknown | 16        | 7.11%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 167       | 74.22%  |
| LightDM | 24        | 10.67%  |
| SDDM    | 18        | 8%      |
| LXDM    | 8         | 3.56%   |
| GDM     | 6         | 2.67%   |
| SLiM    | 1         | 0.44%   |
| LDM     | 1         | 0.44%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 120       | 52.86%  |
| Unknown | 24        | 10.57%  |
| en_GB   | 14        | 6.17%   |
| fr_FR   | 7         | 3.08%   |
| en_DK   | 7         | 3.08%   |
| C       | 7         | 3.08%   |
| de_DE   | 6         | 2.64%   |
| ru_RU   | 5         | 2.2%    |
| it_IT   | 5         | 2.2%    |
| en_CA   | 5         | 2.2%    |
| es_ES   | 4         | 1.76%   |
| cs_CZ   | 3         | 1.32%   |
| pt_BR   | 2         | 0.88%   |
| pl_PL   | 2         | 0.88%   |
| en_AU   | 2         | 0.88%   |
| el_GR   | 2         | 0.88%   |
| tr_TR   | 1         | 0.44%   |
| ru_UA   | 1         | 0.44%   |
| nb_NO   | 1         | 0.44%   |
| hu_HU   | 1         | 0.44%   |
| es_HN   | 1         | 0.44%   |
| es_DO   | 1         | 0.44%   |
| es_CL   | 1         | 0.44%   |
| es_AR   | 1         | 0.44%   |
| en_NZ   | 1         | 0.44%   |
| en_IE   | 1         | 0.44%   |
| ca_ES   | 1         | 0.44%   |
| bg_BG   | 1         | 0.44%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 124       | 55.36%  |
| BIOS | 100       | 44.64%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 134       | 59.56%  |
| Btrfs   | 53        | 23.56%  |
| Xfs     | 14        | 6.22%   |
| Zfs     | 9         | 4%      |
| Unknown | 7         | 3.11%   |
| F2fs    | 4         | 1.78%   |
| Overlay | 3         | 1.33%   |
| Ext3    | 1         | 0.44%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 134       | 59.82%  |
| Unknown | 64        | 28.57%  |
| MBR     | 26        | 11.61%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 194       | 87.78%  |
| Yes       | 27        | 12.22%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 174       | 77.68%  |
| Yes       | 50        | 22.32%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 43        | 19.55%  |
| ASUSTek Computer        | 43        | 19.55%  |
| Hewlett-Packard         | 24        | 10.91%  |
| Dell                    | 18        | 8.18%   |
| MSI                     | 17        | 7.73%   |
| Acer                    | 17        | 7.73%   |
| Gigabyte Technology     | 11        | 5%      |
| ASRock                  | 9         | 4.09%   |
| Unknown                 | 7         | 3.18%   |
| Apple                   | 4         | 1.82%   |
| HUAWEI                  | 3         | 1.36%   |
| Raspberry Pi Foundation | 2         | 0.91%   |
| Notebook                | 2         | 0.91%   |
| Microsoft               | 2         | 0.91%   |
| Framework               | 2         | 0.91%   |
| Toshiba                 | 1         | 0.45%   |
| Timi                    | 1         | 0.45%   |
| Supermicro              | 1         | 0.45%   |
| Samsung Electronics     | 1         | 0.45%   |
| Razer                   | 1         | 0.45%   |
| Positivo                | 1         | 0.45%   |
| Pine Microsystems       | 1         | 0.45%   |
| OrangePi                | 1         | 0.45%   |
| Nokia                   | 1         | 0.45%   |
| Google                  | 1         | 0.45%   |
| Getac                   | 1         | 0.45%   |
| Exo                     | 1         | 0.45%   |
| EVGA                    | 1         | 0.45%   |
| Digibras                | 1         | 0.45%   |
| Cisco Systems           | 1         | 0.45%   |
| Chuwi                   | 1         | 0.45%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| Unknown                               | 7         | 3.18%   |
| MSI MS-7C02                           | 2         | 0.91%   |
| Lenovo ThinkPad P16s Gen 1 21CKCTO1WW | 2         | 0.91%   |
| HP Pavilion Notebook                  | 2         | 0.91%   |
| HP Laptop 15-bw0xx                    | 2         | 0.91%   |
| HP 15                                 | 2         | 0.91%   |
| Dell OptiPlex 780                     | 2         | 0.91%   |
| Dell OptiPlex 7010                    | 2         | 0.91%   |
| ASUS X751LD                           | 2         | 0.91%   |
| ASUS PRIME Z390-P                     | 2         | 0.91%   |
| Apple MacBookPro11,1                  | 2         | 0.91%   |
| Acer Swift SF314-42                   | 2         | 0.91%   |
| Toshiba Satellite A200                | 1         | 0.45%   |
| Timi Redmi Book Pro 15 2022           | 1         | 0.45%   |
| Supermicro Super Server               | 1         | 0.45%   |
| Samsung 275E4E/275E5E                 | 1         | 0.45%   |
| Razer Blade 14 (2022) - RZ09-0427     | 1         | 0.45%   |
| RPi Raspberry Pi Zero 2 W Rev 1.0     | 1         | 0.45%   |
| RPi Raspberry Pi                      | 1         | 0.45%   |
| Positivo Mobile                       | 1         | 0.45%   |
| Pine Microsystems Pine64 Pinebook Pro | 1         | 0.45%   |
| OrangePi Zero3                        | 1         | 0.45%   |
| Notebook NV4XMB,ME,MZ                 | 1         | 0.45%   |
| Notebook NH50_70RA                    | 1         | 0.45%   |
| Nokia Booklet 3G                      | 1         | 0.45%   |
| MSI Summit E13FlipEvo A12MT           | 1         | 0.45%   |
| MSI Prestige 15 A10SC                 | 1         | 0.45%   |
| MSI MS-7D95                           | 1         | 0.45%   |
| MSI MS-7D14                           | 1         | 0.45%   |
| MSI MS-7C92                           | 1         | 0.45%   |
| MSI MS-7C52                           | 1         | 0.45%   |
| MSI MS-7C35                           | 1         | 0.45%   |
| MSI MS-7B86                           | 1         | 0.45%   |
| MSI MS-7A68                           | 1         | 0.45%   |
| MSI MS-7A39                           | 1         | 0.45%   |
| MSI MS-7816                           | 1         | 0.45%   |
| MSI GV72 7RE                          | 1         | 0.45%   |
| MSI GF63 Thin 10SCXR                  | 1         | 0.45%   |
| MSI GE60 2OC\2OD\2OE                  | 1         | 0.45%   |
| MSI Bravo 15 A4DDR                    | 1         | 0.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 24        | 10.91%  |
| Lenovo IdeaPad           | 10        | 4.55%   |
| ASUS PRIME               | 10        | 4.55%   |
| Acer Aspire              | 10        | 4.55%   |
| ASUS VivoBook            | 8         | 3.64%   |
| Unknown                  | 7         | 3.18%   |
| Dell Latitude            | 6         | 2.73%   |
| HP Pavilion              | 5         | 2.27%   |
| HP Laptop                | 5         | 2.27%   |
| Dell OptiPlex            | 5         | 2.27%   |
| Dell Inspiron            | 4         | 1.82%   |
| Lenovo ThinkBook         | 3         | 1.36%   |
| HP Stream                | 3         | 1.36%   |
| ASUS TUF                 | 3         | 1.36%   |
| ASUS ROG                 | 3         | 1.36%   |
| RPi Raspberry            | 2         | 0.91%   |
| MSI MS-7C02              | 2         | 0.91%   |
| Microsoft Surface        | 2         | 0.91%   |
| HP ENVY                  | 2         | 0.91%   |
| HP Compaq                | 2         | 0.91%   |
| HP 255                   | 2         | 0.91%   |
| HP 15                    | 2         | 0.91%   |
| Framework Laptop         | 2         | 0.91%   |
| ASUS X751LD              | 2         | 0.91%   |
| Apple MacBookPro11       | 2         | 0.91%   |
| Acer Swift               | 2         | 0.91%   |
| Toshiba Satellite        | 1         | 0.45%   |
| Timi Redmi               | 1         | 0.45%   |
| Supermicro Super         | 1         | 0.45%   |
| Samsung 275E4E           | 1         | 0.45%   |
| Razer Blade              | 1         | 0.45%   |
| Positivo Mobile          | 1         | 0.45%   |
| Pine Microsystems Pine64 | 1         | 0.45%   |
| OrangePi Zero3           | 1         | 0.45%   |
| Notebook NV4XMB          | 1         | 0.45%   |
| Notebook NH50            | 1         | 0.45%   |
| Nokia Booklet            | 1         | 0.45%   |
| MSI Summit               | 1         | 0.45%   |
| MSI Prestige             | 1         | 0.45%   |
| MSI MS-7D95              | 1         | 0.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 32        | 14.55%  |
| 2020    | 26        | 11.82%  |
| 2018    | 23        | 10.45%  |
| 2021    | 16        | 7.27%   |
| 2013    | 15        | 6.82%   |
| 2017    | 14        | 6.36%   |
| 2022    | 13        | 5.91%   |
| 2014    | 13        | 5.91%   |
| 2016    | 10        | 4.55%   |
| 2012    | 10        | 4.55%   |
| 2011    | 10        | 4.55%   |
| 2015    | 9         | 4.09%   |
| Unknown | 7         | 3.18%   |
| 2023    | 6         | 2.73%   |
| 2010    | 5         | 2.27%   |
| 2009    | 2         | 0.91%   |
| 2008    | 2         | 0.91%   |
| 2007    | 2         | 0.91%   |
| 2006    | 2         | 0.91%   |
| 2005    | 2         | 0.91%   |
| 2024    | 1         | 0.45%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 135       | 61.36%  |
| Desktop        | 69        | 31.36%  |
| Tablet         | 4         | 1.82%   |
| Convertible    | 4         | 1.82%   |
| System on chip | 3         | 1.36%   |
| All in one     | 2         | 0.91%   |
| Server         | 2         | 0.91%   |
| Mini pc        | 1         | 0.45%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 220       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 219       | 99.55%  |
| Yes  | 1         | 0.45%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 48        | 21.52%  |
| 16.01-24.0      | 47        | 21.08%  |
| 8.01-16.0       | 37        | 16.59%  |
| 3.01-4.0        | 33        | 14.8%   |
| 32.01-64.0      | 28        | 12.56%  |
| 1.01-2.0        | 10        | 4.48%   |
| 24.01-32.0      | 8         | 3.59%   |
| 64.01-256.0     | 4         | 1.79%   |
| 0.51-1.0        | 4         | 1.79%   |
| 0.01-0.5        | 2         | 0.9%    |
| More than 256.0 | 1         | 0.45%   |
| 2.01-3.0        | 1         | 0.45%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 67        | 28.63%  |
| 2.01-3.0    | 48        | 20.51%  |
| 3.01-4.0    | 32        | 13.68%  |
| 4.01-8.0    | 31        | 13.25%  |
| 0.51-1.0    | 26        | 11.11%  |
| 8.01-16.0   | 16        | 6.84%   |
| 0.01-0.5    | 10        | 4.27%   |
| 16.01-24.0  | 3         | 1.28%   |
| 64.01-256.0 | 1         | 0.43%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 137       | 61.71%  |
| 2      | 49        | 22.07%  |
| 3      | 24        | 10.81%  |
| 4      | 6         | 2.7%    |
| 5      | 3         | 1.35%   |
| 9      | 1         | 0.45%   |
| 7      | 1         | 0.45%   |
| 0      | 1         | 0.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 175       | 79.55%  |
| Yes       | 45        | 20.45%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 174       | 78.73%  |
| No        | 47        | 21.27%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 166       | 75.11%  |
| No        | 55        | 24.89%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 145       | 65.61%  |
| No        | 76        | 34.39%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 45        | 20.45%  |
| Russia      | 20        | 9.09%   |
| Germany     | 19        | 8.64%   |
| India       | 10        | 4.55%   |
| UK          | 9         | 4.09%   |
| Czechia     | 9         | 4.09%   |
| Poland      | 8         | 3.64%   |
| France      | 8         | 3.64%   |
| Brazil      | 8         | 3.64%   |
| Canada      | 7         | 3.18%   |
| Italy       | 6         | 2.73%   |
| Netherlands | 5         | 2.27%   |
| Greece      | 5         | 2.27%   |
| Denmark     | 5         | 2.27%   |
| Ukraine     | 4         | 1.82%   |
| Switzerland | 4         | 1.82%   |
| Turkey      | 3         | 1.36%   |
| Spain       | 3         | 1.36%   |
| Bulgaria    | 3         | 1.36%   |
| Australia   | 3         | 1.36%   |
| Argentina   | 3         | 1.36%   |
| Vietnam     | 2         | 0.91%   |
| Serbia      | 2         | 0.91%   |
| Norway      | 2         | 0.91%   |
| Morocco     | 2         | 0.91%   |
| Indonesia   | 2         | 0.91%   |
| Finland     | 2         | 0.91%   |
| Uruguay     | 1         | 0.45%   |
| Thailand    | 1         | 0.45%   |
| Sweden      | 1         | 0.45%   |
| Portugal    | 1         | 0.45%   |
| Peru        | 1         | 0.45%   |
| Nigeria     | 1         | 0.45%   |
| New Zealand | 1         | 0.45%   |
| Mexico      | 1         | 0.45%   |
| Latvia      | 1         | 0.45%   |
| Jordan      | 1         | 0.45%   |
| Hungary     | 1         | 0.45%   |
| Honduras    | 1         | 0.45%   |
| Guatemala   | 1         | 0.45%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Prague             | 6         | 2.64%   |
| Moscow             | 6         | 2.64%   |
| Vancouver          | 3         | 1.32%   |
| St Petersburg      | 3         | 1.32%   |
| Munich             | 3         | 1.32%   |
| Lublin             | 3         | 1.32%   |
| Denver             | 3         | 1.32%   |
| Amsterdam          | 3         | 1.32%   |
| Warsaw             | 2         | 0.88%   |
| Toulouse           | 2         | 0.88%   |
| Spring Hill        | 2         | 0.88%   |
| Sofia              | 2         | 0.88%   |
| Sao Paulo          | 2         | 0.88%   |
| Rome               | 2         | 0.88%   |
| Orlando            | 2         | 0.88%   |
| Meknes             | 2         | 0.88%   |
| Kenmore            | 2         | 0.88%   |
| Ioannina           | 2         | 0.88%   |
| Hyderabad          | 2         | 0.88%   |
| Harrisonburg       | 2         | 0.88%   |
| Geneva             | 2         | 0.88%   |
| Zarqa              | 1         | 0.44%   |
| Zagnansk           | 1         | 0.44%   |
| Yekaterinburg      | 1         | 0.44%   |
| Yambol             | 1         | 0.44%   |
| Worthing           | 1         | 0.44%   |
| Winnipeg           | 1         | 0.44%   |
| Wilen bei Wollerau | 1         | 0.44%   |
| Weatherford        | 1         | 0.44%   |
| Volgograd          | 1         | 0.44%   |
| Vlaardingen        | 1         | 0.44%   |
| Vienna             | 1         | 0.44%   |
| Viby J             | 1         | 0.44%   |
| Verkhnyaya Pyshma  | 1         | 0.44%   |
| Varna              | 1         | 0.44%   |
| Trujillo           | 1         | 0.44%   |
| Touget             | 1         | 0.44%   |
| Toms River         | 1         | 0.44%   |
| Tegucigalpa        | 1         | 0.44%   |
| Taranto            | 1         | 0.44%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 63        | 88     | 19.94%  |
| Seagate                     | 42        | 54     | 13.29%  |
| WDC                         | 41        | 54     | 12.97%  |
| SanDisk                     | 21        | 24     | 6.65%   |
| Unknown                     | 19        | 26     | 6.01%   |
| Kingston                    | 18        | 19     | 5.7%    |
| SK hynix                    | 13        | 16     | 4.11%   |
| Intel                       | 11        | 13     | 3.48%   |
| Toshiba                     | 10        | 11     | 3.16%   |
| HGST                        | 9         | 10     | 2.85%   |
| Crucial                     | 9         | 11     | 2.85%   |
| Hitachi                     | 8         | 8      | 2.53%   |
| Micron Technology           | 4         | 5      | 1.27%   |
| Phison Electronics          | 3         | 3      | 0.95%   |
| Phison                      | 3         | 3      | 0.95%   |
| Patriot                     | 3         | 3      | 0.95%   |
| Micron/Crucial Technology   | 3         | 3      | 0.95%   |
| Kingston Technology Company | 3         | 4      | 0.95%   |
| Apple                       | 3         | 3      | 0.95%   |
| A-DATA Technology           | 3         | 4      | 0.95%   |
| Lenovo                      | 2         | 2      | 0.63%   |
| KIOXIA                      | 2         | 2      | 0.63%   |
| Corsair                     | 2         | 2      | 0.63%   |
| XrayDisk                    | 1         | 1      | 0.32%   |
| XPG                         | 1         | 4      | 0.32%   |
| Union Memory (Shenzhen)     | 1         | 1      | 0.32%   |
| Transcend                   | 1         | 1      | 0.32%   |
| SPCC                        | 1         | 1      | 0.32%   |
| Realtek Semiconductor       | 1         | 1      | 0.32%   |
| PNY                         | 1         | 1      | 0.32%   |
| ORIGIN                      | 1         | 1      | 0.32%   |
| OCZ                         | 1         | 1      | 0.32%   |
| Maxtor                      | 1         | 1      | 0.32%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.32%   |
| LITEONIT                    | 1         | 1      | 0.32%   |
| JMicron Technology          | 1         | 1      | 0.32%   |
| Intenso                     | 1         | 1      | 0.32%   |
| INNOVATION IT               | 1         | 1      | 0.32%   |
| IBM/Hitachi                 | 1         | 1      | 0.32%   |
| Gigabyte Technology         | 1         | 2      | 0.32%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 9         | 2.58%   |
| Unknown MMC Card  32GB                             | 8         | 2.29%   |
| Seagate ST1000LM035-1RK172 1TB                     | 6         | 1.72%   |
| Kingston SA400S37240G 240GB SSD                    | 6         | 1.72%   |
| Unknown MMC Card  64GB                             | 5         | 1.43%   |
| Seagate ST2000DM008-2FR102 2TB                     | 5         | 1.43%   |
| Seagate ST500LM012 HN-M500MBB 500GB                | 4         | 1.15%   |
| Seagate ST1000DM010-2EP102 1TB                     | 4         | 1.15%   |
| Sandisk WD Blue SN550 NVMe SSD 2TB                 | 4         | 1.15%   |
| Samsung SSD 870 EVO 500GB                          | 4         | 1.15%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 4         | 1.15%   |
| WDC WD10EZEX-08WN4A0 1TB                           | 3         | 0.86%   |
| Toshiba MQ01ABF050 500GB                           | 3         | 0.86%   |
| Samsung SSD 870 QVO 1TB                            | 3         | 0.86%   |
| Samsung SSD 850 EVO 500GB                          | 3         | 0.86%   |
| Samsung NVMe SSD Drive 1TB                         | 3         | 0.86%   |
| Kingston SHFS37A120G 120GB SSD                     | 3         | 0.86%   |
| HGST HTS545050A7E680 500GB                         | 3         | 0.86%   |
| Crucial CT500MX500SSD1 500GB                       | 3         | 0.86%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                   | 2         | 0.57%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                   | 2         | 0.57%   |
| WDC WD10JPCX-24UE4T0 1TB                           | 2         | 0.57%   |
| Unknown MMC Card  128GB                            | 2         | 0.57%   |
| Toshiba MQ04ABF100 1TB                             | 2         | 0.57%   |
| Toshiba DT01ACA050 500GB                           | 2         | 0.57%   |
| SK hynix SKHynix_HFS001TD9TNI-L2B0B 1024GB         | 2         | 0.57%   |
| SK hynix SHPP41-2000GM 2TB                         | 2         | 0.57%   |
| Seagate ST500DM002-1BD142 500GB                    | 2         | 0.57%   |
| Seagate ST1000LM049-2GH172 1TB                     | 2         | 0.57%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 2         | 0.57%   |
| Seagate ST1000DM003-1CH162 1TB                     | 2         | 0.57%   |
| Sandisk WD Blue SN570 1TB                          | 2         | 0.57%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB   | 2         | 0.57%   |
| Samsung SSD 980 PRO 500GB                          | 2         | 0.57%   |
| Samsung SSD 970 EVO Plus 1TB                       | 2         | 0.57%   |
| Samsung SSD 870 EVO 1TB                            | 2         | 0.57%   |
| Samsung SSD 860 EVO 500GB                          | 2         | 0.57%   |
| Samsung SSD 860 EVO 4TB                            | 2         | 0.57%   |
| Samsung NVMe SSD Drive 500GB                       | 2         | 0.57%   |
| Patriot Burst 120GB SSD                            | 2         | 0.57%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 42        | 54     | 36.52%  |
| WDC                 | 34        | 43     | 29.57%  |
| Toshiba             | 9         | 10     | 7.83%   |
| HGST                | 9         | 10     | 7.83%   |
| Hitachi             | 8         | 8      | 6.96%   |
| Samsung Electronics | 7         | 8      | 6.09%   |
| XrayDisk            | 1         | 1      | 0.87%   |
| Unknown             | 1         | 1      | 0.87%   |
| Maxtor              | 1         | 1      | 0.87%   |
| JMicron Technology  | 1         | 1      | 0.87%   |
| IBM/Hitachi         | 1         | 1      | 0.87%   |
| Apple               | 1         | 1      | 0.87%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 25        | 29     | 27.78%  |
| Kingston            | 17        | 18     | 18.89%  |
| SanDisk             | 8         | 9      | 8.89%   |
| Crucial             | 7         | 9      | 7.78%   |
| WDC                 | 6         | 7      | 6.67%   |
| Intel               | 4         | 4      | 4.44%   |
| Patriot             | 3         | 3      | 3.33%   |
| Apple               | 2         | 2      | 2.22%   |
| A-DATA Technology   | 2         | 3      | 2.22%   |
| Transcend           | 1         | 1      | 1.11%   |
| SPCC                | 1         | 1      | 1.11%   |
| SK hynix            | 1         | 1      | 1.11%   |
| PNY                 | 1         | 1      | 1.11%   |
| ORIGIN              | 1         | 1      | 1.11%   |
| OCZ                 | 1         | 1      | 1.11%   |
| LITEONIT            | 1         | 1      | 1.11%   |
| Lenovo              | 1         | 1      | 1.11%   |
| Intenso             | 1         | 1      | 1.11%   |
| INNOVATION IT       | 1         | 1      | 1.11%   |
| Gigabyte Technology | 1         | 2      | 1.11%   |
| Corsair             | 1         | 1      | 1.11%   |
| China               | 1         | 1      | 1.11%   |
| BIWIN               | 1         | 1      | 1.11%   |
| BHT                 | 1         | 1      | 1.11%   |
| AGI                 | 1         | 1      | 1.11%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 97        | 139    | 33.8%   |
| NVMe    | 92        | 127    | 32.06%  |
| SSD     | 78        | 101    | 27.18%  |
| MMC     | 18        | 23     | 6.27%   |
| Unknown | 2         | 3      | 0.7%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 142       | 234    | 54.62%  |
| NVMe | 92        | 127    | 35.38%  |
| MMC  | 18        | 23     | 6.92%   |
| SAS  | 8         | 9      | 3.08%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 95        | 126    | 51.91%  |
| 0.51-1.0   | 65        | 80     | 35.52%  |
| 1.01-2.0   | 17        | 24     | 9.29%   |
| 3.01-4.0   | 4         | 8      | 2.19%   |
| 4.01-10.0  | 2         | 2      | 1.09%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 55        | 24.44%  |
| 501-1000       | 47        | 20.89%  |
| 101-250        | 42        | 18.67%  |
| 1001-2000      | 20        | 8.89%   |
| More than 3000 | 13        | 5.78%   |
| Unknown        | 13        | 5.78%   |
| 1-20           | 12        | 5.33%   |
| 51-100         | 11        | 4.89%   |
| 21-50          | 7         | 3.11%   |
| 2001-3000      | 5         | 2.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 68        | 29.31%  |
| 101-250        | 44        | 18.97%  |
| 21-50          | 32        | 13.79%  |
| 251-500        | 21        | 9.05%   |
| 51-100         | 21        | 9.05%   |
| 501-1000       | 15        | 6.47%   |
| Unknown        | 13        | 5.6%    |
| 1001-2000      | 11        | 4.74%   |
| More than 3000 | 5         | 2.16%   |
| 2001-3000      | 2         | 0.86%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500LM012 HN-M500MBB 500GB   | 2         | 2      | 5.26%   |
| Seagate ST500DM002-1BD142 500GB       | 2         | 2      | 5.26%   |
| HGST HTS541010A9E680 1TB              | 2         | 2      | 5.26%   |
| WDC WD5000AADS-00S9B0 500GB           | 1         | 2      | 2.63%   |
| WDC WD2003FZEX-00Z4SA0 2TB            | 1         | 1      | 2.63%   |
| WDC WD1600BEVS-60VAT0 160GB           | 1         | 1      | 2.63%   |
| WDC WD10EZEX-08WN4A0 1TB              | 1         | 1      | 2.63%   |
| Toshiba MQ04ABF100 1TB                | 1         | 2      | 2.63%   |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 2.63%   |
| Seagate ST980811AS 80GB               | 1         | 1      | 2.63%   |
| Seagate ST9750420AS 752GB             | 1         | 1      | 2.63%   |
| Seagate ST9500325AS 500GB             | 1         | 1      | 2.63%   |
| Seagate ST500LT012-9WS142 500GB       | 1         | 1      | 2.63%   |
| Seagate ST4000VN008-2DR166 4TB        | 1         | 1      | 2.63%   |
| Seagate ST4000VN000-1H4168 4TB        | 1         | 2      | 2.63%   |
| Seagate ST3750330AS 752GB             | 1         | 1      | 2.63%   |
| Seagate ST3160318AS 160GB             | 1         | 1      | 2.63%   |
| Seagate ST2000VX000-1CU164 2TB        | 1         | 2      | 2.63%   |
| Seagate ST2000DM001-1CH164 2TB        | 1         | 1      | 2.63%   |
| Seagate ST1000LM035-1RK172 1TB        | 1         | 1      | 2.63%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1         | 1      | 2.63%   |
| SanDisk SSD U100 256GB                | 1         | 1      | 2.63%   |
| Samsung Electronics SSD 870 EVO 500GB | 1         | 1      | 2.63%   |
| Samsung Electronics HM160HI 160GB     | 1         | 1      | 2.63%   |
| Samsung Electronics HD502HJ 500GB     | 1         | 1      | 2.63%   |
| Samsung Electronics HD322HJ 320GB     | 1         | 1      | 2.63%   |
| IBM/Hitachi IC25N040ATMR04-0 40GB     | 1         | 1      | 2.63%   |
| Hitachi HUA722010CLA330 1TB           | 1         | 1      | 2.63%   |
| Hitachi HTS727575A9E364 752GB         | 1         | 1      | 2.63%   |
| Hitachi HTS545050B9A300 500GB         | 1         | 1      | 2.63%   |
| Hitachi HTS545050A7E380 500GB         | 1         | 1      | 2.63%   |
| Hitachi HTS543216L9A300 160GB         | 1         | 1      | 2.63%   |
| HGST HTS545050A7E680 500GB            | 1         | 1      | 2.63%   |
| Crucial CT256MX100SSD1 256GB          | 1         | 1      | 2.63%   |
| A-DATA Technology SU700 120GB SSD     | 1         | 1      | 2.63%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 18     | 38.89%  |
| Hitachi             | 5         | 5      | 13.89%  |
| WDC                 | 4         | 5      | 11.11%  |
| Samsung Electronics | 4         | 4      | 11.11%  |
| HGST                | 3         | 3      | 8.33%   |
| Toshiba             | 2         | 3      | 5.56%   |
| SanDisk             | 1         | 1      | 2.78%   |
| IBM/Hitachi         | 1         | 1      | 2.78%   |
| Crucial             | 1         | 1      | 2.78%   |
| A-DATA Technology   | 1         | 1      | 2.78%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 18     | 43.75%  |
| Hitachi             | 5         | 5      | 15.63%  |
| WDC                 | 4         | 5      | 12.5%   |
| Samsung Electronics | 3         | 3      | 9.38%   |
| HGST                | 3         | 3      | 9.38%   |
| Toshiba             | 2         | 3      | 6.25%   |
| IBM/Hitachi         | 1         | 1      | 3.13%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 31        | 38     | 88.57%  |
| SSD  | 4         | 4      | 11.43%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Intel SSDSC2BW240H6 240GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| Intel  | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 125       | 191    | 50%     |
| Detected | 91        | 159    | 36.4%   |
| Malfunc  | 33        | 42     | 13.2%   |
| Failed   | 1         | 1      | 0.4%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 113       | 40.65%  |
| AMD                                     | 58        | 20.86%  |
| Samsung Electronics                     | 39        | 14.03%  |
| SanDisk                                 | 15        | 5.4%    |
| SK hynix                                | 12        | 4.32%   |
| Phison Electronics                      | 7         | 2.52%   |
| Micron/Crucial Technology               | 4         | 1.44%   |
| Micron Technology                       | 4         | 1.44%   |
| Marvell Technology Group                | 4         | 1.44%   |
| Kingston Technology Company             | 4         | 1.44%   |
| ASMedia Technology                      | 4         | 1.44%   |
| KIOXIA                                  | 2         | 0.72%   |
| ADATA Technology                        | 2         | 0.72%   |
| Toshiba America Info Systems            | 1         | 0.36%   |
| Silicon Integrated Systems [SiS]        | 1         | 0.36%   |
| Shenzhen Unionmemory Information System | 1         | 0.36%   |
| Realtek Semiconductor                   | 1         | 0.36%   |
| Nvidia                                  | 1         | 0.36%   |
| MAXIO Technology (Hangzhou)             | 1         | 0.36%   |
| LSI Logic / Symbios Logic               | 1         | 0.36%   |
| Lenovo                                  | 1         | 0.36%   |
| JMicron Technology                      | 1         | 0.36%   |
| Broadcom                                | 1         | 0.36%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 40        | 12.94%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 22        | 7.12%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 12        | 3.88%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 10        | 3.24%   |
| AMD 400 Series Chipset SATA Controller                                         | 10        | 3.24%   |
| AMD 500 Series Chipset SATA Controller                                         | 8         | 2.59%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 7         | 2.27%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 7         | 2.27%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 5         | 1.62%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 5         | 1.62%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 5         | 1.62%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 5         | 1.62%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 4         | 1.29%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 4         | 1.29%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 4         | 1.29%   |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 1.29%   |
| Intel SATA Controller [RAID Mode]                                              | 4         | 1.29%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 1.29%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 1.29%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 4         | 1.29%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 3         | 0.97%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 0.97%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                  | 3         | 0.97%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 0.97%   |
| Intel SSD 660P Series                                                          | 3         | 0.97%   |
| Intel Raptor Lake SATA AHCI Controller                                         | 3         | 0.97%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 3         | 0.97%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 3         | 0.97%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 3         | 0.97%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 3         | 0.97%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 0.97%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3         | 0.97%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 3         | 0.97%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 3         | 0.97%   |
| SK hynix PC611 NVMe Solid State Drive                                          | 2         | 0.65%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 2         | 0.65%   |
| Sandisk WD Black SN850X NVMe SSD                                               | 2         | 0.65%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 2         | 0.65%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 2         | 0.65%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2         | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 152       | 54.48%  |
| NVMe | 93        | 33.33%  |
| IDE  | 18        | 6.45%   |
| RAID | 16        | 5.73%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 136       | 61.82%  |
| AMD                      | 76        | 34.55%  |
| ARM                      | 6         | 2.73%   |
| PowerNV C1P9S01 REV 1.01 | 1         | 0.45%   |
| PowerMac11,2             | 1         | 0.45%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| AMD Ryzen 5 5600X 6-Core Processor                 | 6         | 2.73%   |
| ARM Processor                                      | 5         | 2.27%   |
| Intel Core i5-8265U CPU @ 1.60GHz                  | 4         | 1.82%   |
| Intel Core i9-14900K                               | 3         | 1.36%   |
| Intel Core i7-9750H CPU @ 2.60GHz                  | 3         | 1.36%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz                 | 3         | 1.36%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz                 | 3         | 1.36%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx      | 3         | 1.36%   |
| Intel Core i7-8650U CPU @ 1.90GHz                  | 2         | 0.91%   |
| Intel Core i7-3770 CPU @ 3.40GHz                   | 2         | 0.91%   |
| Intel Core i7-10510U CPU @ 1.80GHz                 | 2         | 0.91%   |
| Intel Core i5-9300H CPU @ 2.40GHz                  | 2         | 0.91%   |
| Intel Core i5-8350U CPU @ 1.70GHz                  | 2         | 0.91%   |
| Intel Core i5-7600K CPU @ 3.80GHz                  | 2         | 0.91%   |
| Intel Core i5-6300U CPU @ 2.40GHz                  | 2         | 0.91%   |
| Intel Core i5-6200U CPU @ 2.30GHz                  | 2         | 0.91%   |
| Intel Core i5-4278U CPU @ 2.60GHz                  | 2         | 0.91%   |
| Intel Core i5-4210U CPU @ 1.70GHz                  | 2         | 0.91%   |
| Intel Core i5-2520M CPU @ 2.50GHz                  | 2         | 0.91%   |
| Intel Core i3-5005U CPU @ 2.00GHz                  | 2         | 0.91%   |
| Intel Core i3-4030U CPU @ 1.90GHz                  | 2         | 0.91%   |
| Intel Core i3-4010U CPU @ 1.70GHz                  | 2         | 0.91%   |
| Intel Celeron N4020 CPU @ 1.10GHz                  | 2         | 0.91%   |
| Intel Atom CPU Z3735F @ 1.33GHz                    | 2         | 0.91%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz            | 2         | 0.91%   |
| AMD Ryzen 7 PRO 6850U with Radeon Graphics         | 2         | 0.91%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics         | 2         | 0.91%   |
| AMD Ryzen 7 5800X 8-Core Processor                 | 2         | 0.91%   |
| AMD Ryzen 7 4800H with Radeon Graphics             | 2         | 0.91%   |
| AMD Ryzen 7 2700X Eight-Core Processor             | 2         | 0.91%   |
| AMD Ryzen 5 5600H with Radeon Graphics             | 2         | 0.91%   |
| AMD Ryzen 5 5500U with Radeon Graphics             | 2         | 0.91%   |
| AMD Ryzen 5 4500U with Radeon Graphics             | 2         | 0.91%   |
| AMD Ryzen 5 3600X 6-Core Processor                 | 2         | 0.91%   |
| AMD Ryzen 5 2600 Six-Core Processor                | 2         | 0.91%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx      | 2         | 0.91%   |
| AMD Ryzen 3 5300U with Radeon Graphics             | 2         | 0.91%   |
| AMD FX-4300 Quad-Core Processor                    | 2         | 0.91%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G       | 2         | 0.91%   |
| PowerNV C1P9S01 REV 1.01 POWER9, altivec supported | 1         | 0.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 38        | 17.27%  |
| Intel Core i7           | 29        | 13.18%  |
| Other                   | 25        | 11.36%  |
| AMD Ryzen 5             | 24        | 10.91%  |
| AMD Ryzen 7             | 20        | 9.09%   |
| Intel Core i3           | 18        | 8.18%   |
| Intel Celeron           | 10        | 4.55%   |
| Intel Atom              | 7         | 3.18%   |
| AMD Ryzen 7 PRO         | 6         | 2.73%   |
| Intel Pentium           | 5         | 2.27%   |
| Intel Core i9           | 4         | 1.82%   |
| Intel Xeon              | 3         | 1.36%   |
| Intel Core 2 Duo        | 3         | 1.36%   |
| AMD Ryzen 9             | 3         | 1.36%   |
| AMD Ryzen 3             | 3         | 1.36%   |
| AMD FX                  | 3         | 1.36%   |
| Intel Genuine           | 2         | 0.91%   |
| AMD A8                  | 2         | 0.91%   |
| Intel Pentium M         | 1         | 0.45%   |
| Intel Pentium Gold      | 1         | 0.45%   |
| Intel Pentium 4         | 1         | 0.45%   |
| Intel Core 2 Quad       | 1         | 0.45%   |
| AMD Turion 64 X2 Mobile | 1         | 0.45%   |
| AMD Ryzen Threadripper  | 1         | 0.45%   |
| AMD Ryzen 5 PRO         | 1         | 0.45%   |
| AMD Phenom II X4        | 1         | 0.45%   |
| AMD E2                  | 1         | 0.45%   |
| AMD E1                  | 1         | 0.45%   |
| AMD C-60                | 1         | 0.45%   |
| AMD Athlon II X3        | 1         | 0.45%   |
| AMD Athlon II X2        | 1         | 0.45%   |
| AMD A6                  | 1         | 0.45%   |
| AMD A4                  | 1         | 0.45%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 73        | 33.18%  |
| 2       | 64        | 29.09%  |
| 6       | 33        | 15%     |
| 8       | 27        | 12.27%  |
| 1       | 7         | 3.18%   |
| 12      | 4         | 1.82%   |
| 24      | 3         | 1.36%   |
| Unknown | 3         | 1.36%   |
| 14      | 2         | 0.91%   |
| 64      | 1         | 0.45%   |
| 16      | 1         | 0.45%   |
| 10      | 1         | 0.45%   |
| 3       | 1         | 0.45%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 215       | 97.73%  |
| Unknown | 3         | 1.36%   |
| 2       | 2         | 0.91%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 153       | 69.55%  |
| 1       | 63        | 28.64%  |
| Unknown | 3         | 1.36%   |
| 4       | 1         | 0.45%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 204       | 92.73%  |
| Unknown        | 8         | 3.64%   |
| 32-bit         | 5         | 2.27%   |
| 64-bit         | 3         | 1.36%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 104       | 46.02%  |
| 0x40651    | 8         | 3.54%   |
| 0x306a9    | 7         | 3.1%    |
| 0x906e9    | 5         | 2.21%   |
| 0x0a404102 | 5         | 2.21%   |
| 0x906ea    | 4         | 1.77%   |
| 0x806ec    | 4         | 1.77%   |
| 0x806e9    | 4         | 1.77%   |
| 0x406e3    | 4         | 1.77%   |
| 0x08108102 | 4         | 1.77%   |
| 0x806ea    | 3         | 1.33%   |
| 0x30678    | 3         | 1.33%   |
| 0x206a7    | 3         | 1.33%   |
| 0x0a50000c | 3         | 1.33%   |
| 0x08600104 | 3         | 1.33%   |
| 0x06006705 | 3         | 1.33%   |
| 0x906a3    | 2         | 0.88%   |
| 0x506e3    | 2         | 0.88%   |
| 0x106c2    | 2         | 0.88%   |
| 0x0a201009 | 2         | 0.88%   |
| 0x08701030 | 2         | 0.88%   |
| 0x08701021 | 2         | 0.88%   |
| 0x08608103 | 2         | 0.88%   |
| 0x0800820d | 2         | 0.88%   |
| 0x07030105 | 2         | 0.88%   |
| 0x06000852 | 2         | 0.88%   |
| 0x05000119 | 2         | 0.88%   |
| 0x010000c8 | 2         | 0.88%   |
| 0xa0671    | 1         | 0.44%   |
| 0xa0652    | 1         | 0.44%   |
| 0x906ed    | 1         | 0.44%   |
| 0x90675    | 1         | 0.44%   |
| 0x90672    | 1         | 0.44%   |
| 0x806eb    | 1         | 0.44%   |
| 0x806c1    | 1         | 0.44%   |
| 0x706e5    | 1         | 0.44%   |
| 0x706a1    | 1         | 0.44%   |
| 0x406c4    | 1         | 0.44%   |
| 0x306d4    | 1         | 0.44%   |
| 0x306c3    | 1         | 0.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 39        | 17.73%  |
| Unknown          | 23        | 10.45%  |
| Zen 3            | 17        | 7.73%   |
| Haswell          | 16        | 7.27%   |
| Zen 2            | 14        | 6.36%   |
| IvyBridge        | 11        | 5%      |
| Zen+             | 9         | 4.09%   |
| Silvermont       | 9         | 4.09%   |
| Skylake          | 8         | 3.64%   |
| Alderlake Hybrid | 8         | 3.64%   |
| SandyBridge      | 7         | 3.18%   |
| Zen              | 5         | 2.27%   |
| IceLake          | 5         | 2.27%   |
| Excavator        | 5         | 2.27%   |
| TigerLake        | 4         | 1.82%   |
| Goldmont plus    | 4         | 1.82%   |
| Broadwell        | 4         | 1.82%   |
| Puma             | 3         | 1.36%   |
| Piledriver       | 3         | 1.36%   |
| Penryn           | 3         | 1.36%   |
| K10              | 3         | 1.36%   |
| Core             | 3         | 1.36%   |
| CometLake        | 3         | 1.36%   |
| Bonnell          | 3         | 1.36%   |
| P6               | 2         | 0.91%   |
| Bobcat           | 2         | 0.91%   |
| Westmere         | 1         | 0.45%   |
| NetBurst         | 1         | 0.45%   |
| Nehalem          | 1         | 0.45%   |
| K8 Hammer        | 1         | 0.45%   |
| Jaguar           | 1         | 0.45%   |
| Gracemont        | 1         | 0.45%   |
| Goldmont         | 1         | 0.45%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 107       | 41.63%  |
| AMD                              | 76        | 29.57%  |
| Nvidia                           | 70        | 27.24%  |
| ASPEED Technology                | 2         | 0.78%   |
| Silicon Integrated Systems [SiS] | 1         | 0.39%   |
| Matrox Electronics Systems       | 1         | 0.39%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 12        | 4.55%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 7         | 2.65%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 2.65%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7         | 2.65%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 7         | 2.65%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 6         | 2.27%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 6         | 2.27%   |
| Intel UHD Graphics 620                                                                   | 6         | 2.27%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 2.27%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 2.27%   |
| AMD Rembrandt [Radeon 680M]                                                              | 6         | 2.27%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 5         | 1.89%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 5         | 1.89%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 1.89%   |
| AMD Lucienne                                                                             | 5         | 1.89%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 1.52%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 1.52%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 1.52%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 1.52%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 4         | 1.52%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4         | 1.52%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4         | 1.52%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 3         | 1.14%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 1.14%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 3         | 1.14%   |
| Intel HD Graphics 630                                                                    | 3         | 1.14%   |
| Intel HD Graphics 620                                                                    | 3         | 1.14%   |
| Intel HD Graphics 5500                                                                   | 3         | 1.14%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 3         | 1.14%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                                       | 3         | 1.14%   |
| Nvidia TU106 [GeForce RTX 2070]                                                          | 2         | 0.76%   |
| Nvidia GP108M [GeForce MX250]                                                            | 2         | 0.76%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 2         | 0.76%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.76%   |
| Nvidia AD102 [GeForce RTX 4090]                                                          | 2         | 0.76%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 0.76%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 0.76%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 0.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 0.76%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 2         | 0.76%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 71        | 31.7%   |
| 1 x AMD        | 64        | 28.57%  |
| 1 x Nvidia     | 35        | 15.63%  |
| Intel + Nvidia | 29        | 12.95%  |
| Other          | 8         | 3.57%   |
| AMD + Nvidia   | 5         | 2.23%   |
| Intel + AMD    | 3         | 1.34%   |
| 2 x Nvidia     | 2         | 0.89%   |
| 2 x AMD        | 2         | 0.89%   |
| AMD + ASPEED   | 2         | 0.89%   |
| 2 x Intel      | 1         | 0.45%   |
| 1 x SiS        | 1         | 0.45%   |
| 1 x Matrox     | 1         | 0.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 159       | 71.3%   |
| Proprietary | 55        | 24.66%  |
| Unknown     | 9         | 4.04%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 128       | 55.9%   |
| 3.01-4.0   | 21        | 9.17%   |
| 1.01-2.0   | 21        | 9.17%   |
| 0.01-0.5   | 19        | 8.3%    |
| 7.01-8.0   | 14        | 6.11%   |
| 0.51-1.0   | 11        | 4.8%    |
| 5.01-6.0   | 5         | 2.18%   |
| 8.01-16.0  | 5         | 2.18%   |
| 16.01-24.0 | 3         | 1.31%   |
| 2.01-3.0   | 2         | 0.87%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Chimei Innolux       | 33        | 13.98%  |
| AU Optronics         | 29        | 12.29%  |
| BOE                  | 25        | 10.59%  |
| Samsung Electronics  | 21        | 8.9%    |
| LG Display           | 19        | 8.05%   |
| Dell                 | 12        | 5.08%   |
| Hewlett-Packard      | 10        | 4.24%   |
| Goldstar             | 7         | 2.97%   |
| Philips              | 6         | 2.54%   |
| Acer                 | 6         | 2.54%   |
| Lenovo               | 5         | 2.12%   |
| Iiyama               | 5         | 2.12%   |
| Apple                | 5         | 2.12%   |
| PANDA                | 4         | 1.69%   |
| BenQ                 | 4         | 1.69%   |
| AOC                  | 4         | 1.69%   |
| LG Philips           | 3         | 1.27%   |
| ASUSTek Computer     | 3         | 1.27%   |
| Ancor Communications | 3         | 1.27%   |
| Unknown              | 3         | 1.27%   |
| TMX                  | 2         | 0.85%   |
| Sharp                | 2         | 0.85%   |
| Fujitsu Siemens      | 2         | 0.85%   |
| Vizio                | 1         | 0.42%   |
| ViewSonic            | 1         | 0.42%   |
| Unknown              | 1         | 0.42%   |
| STD                  | 1         | 0.42%   |
| Sceptre Tech         | 1         | 0.42%   |
| Sceptre              | 1         | 0.42%   |
| Quanta Display       | 1         | 0.42%   |
| Panasonic            | 1         | 0.42%   |
| ONN                  | 1         | 0.42%   |
| MSI                  | 1         | 0.42%   |
| LG Electronics       | 1         | 0.42%   |
| KK@                  | 1         | 0.42%   |
| InnoLux Display      | 1         | 0.42%   |
| InfoVision           | 1         | 0.42%   |
| Idek Iiyama          | 1         | 0.42%   |
| Huion                | 1         | 0.42%   |
| Gigabyte Technology  | 1         | 0.42%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 1.23%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 3         | 1.23%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 3         | 1.23%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 3         | 1.23%   |
| Unknown                                                               | 3         | 1.23%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 2         | 0.82%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 2         | 0.82%   |
| Iiyama PL3461WQ IVM7615 3440x1440 800x330mm 34.1-inch                 | 2         | 0.82%   |
| Iiyama PL2473HD IVM6107 1920x1080 521x293mm 23.5-inch                 | 2         | 0.82%   |
| Hewlett-Packard LA2405 HWP284C 1920x1200 518x324mm 24.1-inch          | 2         | 0.82%   |
| Hewlett-Packard 22w HPN342E 1920x1080 476x268mm 21.5-inch             | 2         | 0.82%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 2         | 0.82%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch       | 2         | 0.82%   |
| Chimei Innolux LCD Monitor CMN15B7 1366x768 344x193mm 15.5-inch       | 2         | 0.82%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch        | 2         | 0.82%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch         | 2         | 0.82%   |
| Apple Color LCD APPA020 2560x1600 286x179mm 13.3-inch                 | 2         | 0.82%   |
| Vizio E320-A1 VIZ0095 1360x768 697x392mm 31.5-inch                    | 1         | 0.41%   |
| ViewSonic LCD Monitor VX2457 1920x1080                                | 1         | 0.41%   |
| Unknown LCD Monitor ENV LCD2460 1920x1080                             | 1         | 0.41%   |
| TMX TL156VDXP01 TMX1560 1920x1080 344x194mm 15.5-inch                 | 1         | 0.41%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch               | 1         | 0.41%   |
| STD Monitor STD0001 1920x1080                                         | 1         | 0.41%   |
| Sharp LQ134N1JW53 SHP1521 1920x1200 288x180mm 13.4-inch               | 1         | 0.41%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 1         | 0.41%   |
| Sceptre Tech E24 SPT099D 1920x1080 530x300mm 24.0-inch                | 1         | 0.41%   |
| Sceptre LCD Monitor E24 1920x1080                                     | 1         | 0.41%   |
| Samsung Electronics SyncMaster SAM04D4 1920x1080 531x298mm 24.0-inch  | 1         | 0.41%   |
| Samsung Electronics SA300/SA350 SAM07D2 1920x1080 477x268mm 21.5-inch | 1         | 0.41%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 0.41%   |
| Samsung Electronics S23C350 SAM0A36 1920x1080 510x287mm 23.0-inch     | 1         | 0.41%   |
| Samsung Electronics LU28R55 SAM1017 3840x2160 632x360mm 28.6-inch     | 1         | 0.41%   |
| Samsung Electronics LU28R55 SAM1015 3840x2160 630x360mm 28.6-inch     | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                  | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SyncMaster                            | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch  | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch  | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SDC4193 2880x1800 302x189mm 14.0-inch | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SDC416D 2880x1800 312x195mm 14.5-inch | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SAM050C 1920x1080 886x498mm 40.0-inch | 1         | 0.41%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 97        | 42.54%  |
| 1366x768 (WXGA)    | 41        | 17.98%  |
| 2560x1440 (QHD)    | 12        | 5.26%   |
| 1920x1200 (WUXGA)  | 12        | 5.26%   |
| 3840x2160 (4K)     | 10        | 4.39%   |
| 1600x900 (HD+)     | 8         | 3.51%   |
| Unknown            | 5         | 2.19%   |
| 3440x1440          | 4         | 1.75%   |
| 2560x1600          | 4         | 1.75%   |
| 1680x1050 (WSXGA+) | 4         | 1.75%   |
| 1280x800 (WXGA)    | 4         | 1.75%   |
| 2880x1800          | 3         | 1.32%   |
| 2560x1080          | 3         | 1.32%   |
| 2160x1440          | 3         | 1.32%   |
| 3840x1080          | 2         | 0.88%   |
| 2256x1504          | 2         | 0.88%   |
| 1280x1024 (SXGA)   | 2         | 0.88%   |
| 1024x600           | 2         | 0.88%   |
| 7680x1080          | 1         | 0.44%   |
| 7040x1440          | 1         | 0.44%   |
| 3840x1600          | 1         | 0.44%   |
| 3200x2000          | 1         | 0.44%   |
| 2288x1287          | 1         | 0.44%   |
| 1920x1280          | 1         | 0.44%   |
| 1600x1200          | 1         | 0.44%   |
| 1360x768           | 1         | 0.44%   |
| 1280x720 (HD)      | 1         | 0.44%   |
| 1024x768 (XGA)     | 1         | 0.44%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 57        | 24.36%  |
| 14      | 28        | 11.97%  |
| 13      | 23        | 9.83%   |
| 24      | 21        | 8.97%   |
| Unknown | 19        | 8.12%   |
| 21      | 13        | 5.56%   |
| 27      | 9         | 3.85%   |
| 23      | 9         | 3.85%   |
| 17      | 6         | 2.56%   |
| 11      | 6         | 2.56%   |
| 34      | 5         | 2.14%   |
| 22      | 5         | 2.14%   |
| 16      | 4         | 1.71%   |
| 12      | 4         | 1.71%   |
| 31      | 3         | 1.28%   |
| 28      | 3         | 1.28%   |
| 10      | 3         | 1.28%   |
| 25      | 2         | 0.85%   |
| 20      | 2         | 0.85%   |
| 19      | 2         | 0.85%   |
| 84      | 1         | 0.43%   |
| 48      | 1         | 0.43%   |
| 40      | 1         | 0.43%   |
| 39      | 1         | 0.43%   |
| 37      | 1         | 0.43%   |
| 33      | 1         | 0.43%   |
| 32      | 1         | 0.43%   |
| 26      | 1         | 0.43%   |
| 18      | 1         | 0.43%   |
| 8       | 1         | 0.43%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 100       | 43.1%   |
| 501-600     | 39        | 16.81%  |
| 201-300     | 26        | 11.21%  |
| 401-500     | 21        | 9.05%   |
| Unknown     | 19        | 8.19%   |
| 601-700     | 8         | 3.45%   |
| 701-800     | 7         | 3.02%   |
| 351-400     | 6         | 2.59%   |
| 801-900     | 3         | 1.29%   |
| 1501-2000   | 1         | 0.43%   |
| 101-200     | 1         | 0.43%   |
| 1001-1500   | 1         | 0.43%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 151       | 69.27%  |
| 16/10   | 29        | 13.3%   |
| Unknown | 18        | 8.26%   |
| 3/2     | 8         | 3.67%   |
| 21/9    | 8         | 3.67%   |
| 5/4     | 2         | 0.92%   |
| 4/3     | 1         | 0.46%   |
| 32/9    | 1         | 0.46%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 56        | 24.14%  |
| 81-90          | 41        | 17.67%  |
| 201-250        | 35        | 15.09%  |
| Unknown        | 19        | 8.19%   |
| 251-300        | 13        | 5.6%    |
| 351-500        | 12        | 5.17%   |
| 301-350        | 10        | 4.31%   |
| 71-80          | 8         | 3.45%   |
| 51-60          | 7         | 3.02%   |
| 151-200        | 5         | 2.16%   |
| 111-120        | 5         | 2.16%   |
| 61-70          | 4         | 1.72%   |
| 501-1000       | 4         | 1.72%   |
| 121-130        | 3         | 1.29%   |
| 41-50          | 2         | 0.86%   |
| 141-150        | 2         | 0.86%   |
| 131-140        | 2         | 0.86%   |
| 91-100         | 2         | 0.86%   |
| More than 1000 | 1         | 0.43%   |
| 1-40           | 1         | 0.43%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 69        | 29.74%  |
| 51-100        | 60        | 25.86%  |
| 101-120       | 56        | 24.14%  |
| 161-240       | 22        | 9.48%   |
| Unknown       | 19        | 8.19%   |
| More than 240 | 5         | 2.16%   |
| 1-50          | 1         | 0.43%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 177       | 79.37%  |
| 2     | 39        | 17.49%  |
| 0     | 7         | 3.14%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 122       | 38.36%  |
| Intel                            | 92        | 28.93%  |
| Qualcomm Atheros                 | 26        | 8.18%   |
| Broadcom                         | 17        | 5.35%   |
| MediaTek                         | 8         | 2.52%   |
| Broadcom Limited                 | 6         | 1.89%   |
| TP-Link                          | 5         | 1.57%   |
| Ralink Technology                | 5         | 1.57%   |
| Qualcomm                         | 5         | 1.57%   |
| Xiaomi                           | 3         | 0.94%   |
| Sierra Wireless                  | 3         | 0.94%   |
| Aquantia                         | 3         | 0.94%   |
| Ralink                           | 2         | 0.63%   |
| Qualcomm Atheros Communications  | 2         | 0.63%   |
| Marvell Technology Group         | 2         | 0.63%   |
| Cypress Semiconductor            | 2         | 0.63%   |
| Tenda                            | 1         | 0.31%   |
| STMicroelectronics               | 1         | 0.31%   |
| Standard Microsystems            | 1         | 0.31%   |
| Silicon Integrated Systems [SiS] | 1         | 0.31%   |
| Qualcomm Technologies            | 1         | 0.31%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.31%   |
| Nvidia                           | 1         | 0.31%   |
| Microsoft                        | 1         | 0.31%   |
| Mellanox Technologies            | 1         | 0.31%   |
| Huawei Technologies              | 1         | 0.31%   |
| DisplayLink                      | 1         | 0.31%   |
| ASUSTek Computer                 | 1         | 0.31%   |
| ASIX Electronics                 | 1         | 0.31%   |
| Arduino SA                       | 1         | 0.31%   |
| Apple                            | 1         | 0.31%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 75        | 20.27%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 17        | 4.59%   |
| Intel Wi-Fi 6 AX200                                                    | 16        | 4.32%   |
| Realtek RTL8125 2.5GbE Controller                                      | 10        | 2.7%    |
| Intel Wireless 8265 / 8275                                             | 9         | 2.43%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 8         | 2.16%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 7         | 1.89%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 7         | 1.89%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 7         | 1.89%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 6         | 1.62%   |
| Intel I211 Gigabit Network Connection                                  | 6         | 1.62%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 5         | 1.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 5         | 1.35%   |
| Broadcom BCM43142 802.11b/g/n                                          | 5         | 1.35%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 4         | 1.08%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 4         | 1.08%   |
| Qualcomm QCNFA765 Wireless Network Adapter                             | 4         | 1.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 4         | 1.08%   |
| Intel Ethernet Connection (4) I219-LM                                  | 4         | 1.08%   |
| Intel Ethernet Connection (2) I219-V                                   | 4         | 1.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 4         | 1.08%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 3         | 0.81%   |
| Ralink MT7601U Wireless Adapter                                        | 3         | 0.81%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 3         | 0.81%   |
| Intel Wireless 8260                                                    | 3         | 0.81%   |
| Intel Wireless 7265                                                    | 3         | 0.81%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 3         | 0.81%   |
| Intel Wi-Fi 6 AX201                                                    | 3         | 0.81%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 3         | 0.81%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 3         | 0.81%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 3         | 0.81%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 3         | 0.81%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 2         | 0.54%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                 | 2         | 0.54%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 2         | 0.54%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 2         | 0.54%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 2         | 0.54%   |
| Qualcomm Atheros AR9271 802.11n                                        | 2         | 0.54%   |
| Intel Wireless 7260                                                    | 2         | 0.54%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 2         | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 74        | 42.29%  |
| Realtek Semiconductor           | 34        | 19.43%  |
| Qualcomm Atheros                | 21        | 12%     |
| Broadcom                        | 11        | 6.29%   |
| MediaTek                        | 7         | 4%      |
| Ralink Technology               | 5         | 2.86%   |
| TP-Link                         | 4         | 2.29%   |
| Qualcomm                        | 4         | 2.29%   |
| Broadcom Limited                | 4         | 2.29%   |
| Sierra Wireless                 | 3         | 1.71%   |
| Ralink                          | 2         | 1.14%   |
| Qualcomm Atheros Communications | 2         | 1.14%   |
| Tenda                           | 1         | 0.57%   |
| Qualcomm Technologies           | 1         | 0.57%   |
| Microsoft                       | 1         | 0.57%   |
| ASUSTek Computer                | 1         | 0.57%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 16        | 9.04%   |
| Intel Wireless 8265 / 8275                                           | 9         | 5.08%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 7         | 3.95%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 7         | 3.95%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 7         | 3.95%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 6         | 3.39%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 5         | 2.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 5         | 2.82%   |
| Broadcom BCM43142 802.11b/g/n                                        | 5         | 2.82%   |
| Realtek RTL8723DE Wireless Network Adapter                           | 4         | 2.26%   |
| Qualcomm QCNFA765 Wireless Network Adapter                           | 4         | 2.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 4         | 2.26%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 4         | 2.26%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 3         | 1.69%   |
| Ralink MT7601U Wireless Adapter                                      | 3         | 1.69%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 3         | 1.69%   |
| Intel Wireless 8260                                                  | 3         | 1.69%   |
| Intel Wireless 7265                                                  | 3         | 1.69%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 3         | 1.69%   |
| Intel Wi-Fi 6 AX201                                                  | 3         | 1.69%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 3         | 1.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 3         | 1.69%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 3         | 1.69%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 3         | 1.69%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                               | 2         | 1.13%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 2         | 1.13%   |
| Qualcomm Atheros AR9271 802.11n                                      | 2         | 1.13%   |
| Intel Wireless 7260                                                  | 2         | 1.13%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 2         | 1.13%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 2         | 1.13%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 2         | 1.13%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 2         | 1.13%   |
| Intel Centrino Ultimate-N 6300                                       | 2         | 1.13%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 2         | 1.13%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 2         | 1.13%   |
| Broadcom BCM4311 802.11b/g WLAN                                      | 2         | 1.13%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 1         | 0.56%   |
| TP-Link 802.11n NIC                                                  | 1         | 0.56%   |
| Tenda U12                                                            | 1         | 0.56%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                        | 1         | 0.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 108       | 57.45%  |
| Intel                            | 43        | 22.87%  |
| Broadcom                         | 8         | 4.26%   |
| Qualcomm Atheros                 | 6         | 3.19%   |
| Xiaomi                           | 3         | 1.6%    |
| Aquantia                         | 3         | 1.6%    |
| Marvell Technology Group         | 2         | 1.06%   |
| Cypress Semiconductor            | 2         | 1.06%   |
| Broadcom Limited                 | 2         | 1.06%   |
| TP-Link                          | 1         | 0.53%   |
| Standard Microsystems            | 1         | 0.53%   |
| Silicon Integrated Systems [SiS] | 1         | 0.53%   |
| Qualcomm                         | 1         | 0.53%   |
| Nvidia                           | 1         | 0.53%   |
| Mellanox Technologies            | 1         | 0.53%   |
| MediaTek                         | 1         | 0.53%   |
| Huawei Technologies              | 1         | 0.53%   |
| DisplayLink                      | 1         | 0.53%   |
| ASIX Electronics                 | 1         | 0.53%   |
| Apple                            | 1         | 0.53%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 75        | 39.68%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 17        | 8.99%   |
| Realtek RTL8125 2.5GbE Controller                                      | 10        | 5.29%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 8         | 4.23%   |
| Intel I211 Gigabit Network Connection                                  | 6         | 3.17%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 4         | 2.12%   |
| Intel Ethernet Connection (4) I219-LM                                  | 4         | 2.12%   |
| Intel Ethernet Connection (2) I219-V                                   | 4         | 2.12%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 2         | 1.06%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 2         | 1.06%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 2         | 1.06%   |
| Intel Ethernet Controller I226-V                                       | 2         | 1.06%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 1.06%   |
| Intel Ethernet Connection (7) I219-LM                                  | 2         | 1.06%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 2         | 1.06%   |
| Cypress K38231_03                                                      | 2         | 1.06%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 0.53%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 1         | 0.53%   |
| Standard Microsystems Ethernet controller                              | 1         | 0.53%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 1         | 0.53%   |
| Qualcomm SAMSUNG_Android                                               | 1         | 0.53%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 0.53%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1         | 0.53%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1         | 0.53%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 0.53%   |
| Nvidia MCP61 Ethernet                                                  | 1         | 0.53%   |
| Mellanox MT27710 Family [ConnectX-4 Lx]                                | 1         | 0.53%   |
| MediaTek RMX3085                                                       | 1         | 0.53%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 1         | 0.53%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                   | 1         | 0.53%   |
| Intel I210 Gigabit Network Connection                                  | 1         | 0.53%   |
| Intel Ethernet Connection I219-V                                       | 1         | 0.53%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 0.53%   |
| Intel Ethernet Connection I218-V                                       | 1         | 0.53%   |
| Intel Ethernet Connection I217-V                                       | 1         | 0.53%   |
| Intel Ethernet Connection I217-LM                                      | 1         | 0.53%   |
| Intel Ethernet Connection (6) I219-V                                   | 1         | 0.53%   |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 0.53%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 0.53%   |
| Intel Ethernet Connection (17) I219-V                                  | 1         | 0.53%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 174       | 50.58%  |
| WiFi     | 166       | 48.26%  |
| Modem    | 3         | 0.87%   |
| Unknown  | 1         | 0.29%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 135       | 61.64%  |
| Ethernet | 84        | 38.36%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 100       | 45.45%  |
| 1     | 97        | 44.09%  |
| 0     | 11        | 5%      |
| 3     | 10        | 4.55%   |
| 4     | 2         | 0.91%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 178       | 79.82%  |
| Yes  | 45        | 20.18%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 62        | 41.61%  |
| Realtek Semiconductor           | 20        | 13.42%  |
| Broadcom                        | 11        | 7.38%   |
| Lite-On Technology              | 9         | 6.04%   |
| IMC Networks                    | 8         | 5.37%   |
| Cambridge Silicon Radio         | 8         | 5.37%   |
| Foxconn / Hon Hai               | 7         | 4.7%    |
| USI                             | 4         | 2.68%   |
| Qualcomm Atheros Communications | 4         | 2.68%   |
| Apple                           | 4         | 2.68%   |
| Realtek                         | 3         | 2.01%   |
| Toshiba                         | 1         | 0.67%   |
| SINO WEALTH                     | 1         | 0.67%   |
| Ralink                          | 1         | 0.67%   |
| Opticis                         | 1         | 0.67%   |
| MediaTek                        | 1         | 0.67%   |
| Foxconn International           | 1         | 0.67%   |
| Dell                            | 1         | 0.67%   |
| ASUSTek Computer                | 1         | 0.67%   |
| Actions                         | 1         | 0.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                               | 16        | 10.67%  |
| Intel Bluetooth Device                              | 12        | 8%      |
| Realtek Bluetooth Radio                             | 11        | 7.33%   |
| Intel AX201 Bluetooth                               | 10        | 6.67%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 9         | 6%      |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 8         | 5.33%   |
| Realtek  Bluetooth 4.2 Adapter                      | 5         | 3.33%   |
| Intel Bluetooth wireless interface                  | 5         | 3.33%   |
| USI Bluetooth Device                                | 4         | 2.67%   |
| IMC Networks Bluetooth Radio                        | 4         | 2.67%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 4         | 2.67%   |
| Realtek Bluetooth Radio                             | 3         | 2%      |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 2%      |
| Lite-On Atheros AR3012 Bluetooth                    | 3         | 2%      |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 2%      |
| Intel AX211 Bluetooth                               | 3         | 2%      |
| Intel AX210 Bluetooth                               | 3         | 2%      |
| Broadcom BCM43142A0 Bluetooth Device                | 3         | 2%      |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 2%      |
| Realtek 802.11ac WLAN Adapter                       | 2         | 1.33%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 1.33%   |
| Lite-On Bluetooth Device                            | 2         | 1.33%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 1.33%   |
| IMC Networks Bluetooth Device                       | 2         | 1.33%   |
| Apple Bluetooth Host Controller                     | 2         | 1.33%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 0.67%   |
| SINO WEALTH Bluetooth Keyboard                      | 1         | 0.67%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.67%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.67%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.67%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.67%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.67%   |
| Opticis Bluetooth Radio                             | 1         | 0.67%   |
| MediaTek Wireless_Device                            | 1         | 0.67%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.67%   |
| IMC Networks Wireless_Device                        | 1         | 0.67%   |
| IMC Networks Bluetooth                              | 1         | 0.67%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.67%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth     | 1         | 0.67%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 0.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 129       | 41.88%  |
| AMD                                  | 86        | 27.92%  |
| Nvidia                               | 47        | 15.26%  |
| Logitech                             | 6         | 1.95%   |
| C-Media Electronics                  | 6         | 1.95%   |
| JMTek                                | 5         | 1.62%   |
| Texas Instruments                    | 2         | 0.65%   |
| Creative Technology                  | 2         | 0.65%   |
| Corsair                              | 2         | 0.65%   |
| Astro Gaming                         | 2         | 0.65%   |
| VIA Technologies                     | 1         | 0.32%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.32%   |
| SteelSeries ApS                      | 1         | 0.32%   |
| Silicon Integrated Systems [SiS]     | 1         | 0.32%   |
| SAVITECH                             | 1         | 0.32%   |
| Samson Technologies                  | 1         | 0.32%   |
| Razer USA                            | 1         | 0.32%   |
| Mark of the Unicorn                  | 1         | 0.32%   |
| Fry's Electronics                    | 1         | 0.32%   |
| Focusrite                            | 1         | 0.32%   |
| FiiO Electronics Technology          | 1         | 0.32%   |
| Elgato Systems                       | 1         | 0.32%   |
| EDFIER                               | 1         | 0.32%   |
| DCMT Technology                      | 1         | 0.32%   |
| Cambridge Silicon Radio              | 1         | 0.32%   |
| Cambridge Audio                      | 1         | 0.32%   |
| Blue Microphones                     | 1         | 0.32%   |
| BEHRINGER International              | 1         | 0.32%   |
| ASUSTek Computer                     | 1         | 0.32%   |
| ASRock                               | 1         | 0.32%   |
| Apple                                | 1         | 0.32%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 31        | 8.01%   |
| AMD Starship/Matisse HD Audio Controller                                   | 18        | 4.65%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 17        | 4.39%   |
| Intel Sunrise Point-LP HD Audio                                            | 16        | 4.13%   |
| Intel Haswell-ULT HD Audio Controller                                      | 12        | 3.1%    |
| Intel 8 Series HD Audio Controller                                         | 12        | 3.1%    |
| Intel Cannon Lake PCH cAVS                                                 | 10        | 2.58%   |
| Nvidia GP107GL High Definition Audio Controller                            | 9         | 2.33%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 9         | 2.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8         | 2.07%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 8         | 2.07%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 7         | 1.81%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 7         | 1.81%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 7         | 1.81%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 7         | 1.81%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6         | 1.55%   |
| JMTek USB PnP Audio Device                                                 | 5         | 1.29%   |
| Intel 200 Series PCH HD Audio                                              | 5         | 1.29%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 5         | 1.29%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 5         | 1.29%   |
| AMD Navi 10 HDMI Audio                                                     | 5         | 1.29%   |
| AMD High Definition Audio Controller                                       | 5         | 1.29%   |
| AMD FCH Azalia Controller                                                  | 5         | 1.29%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 5         | 1.29%   |
| Nvidia TU106 High Definition Audio Controller                              | 4         | 1.03%   |
| Nvidia GP106 High Definition Audio Controller                              | 4         | 1.03%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 4         | 1.03%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 4         | 1.03%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 1.03%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 1.03%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 4         | 1.03%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 4         | 1.03%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 1.03%   |
| AMD Kabini HDMI/DP Audio                                                   | 4         | 1.03%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 4         | 1.03%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 0.78%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 0.78%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3         | 0.78%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 0.78%   |
| Intel CM238 HD Audio Controller                                            | 3         | 0.78%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 40        | 22.86%  |
| Samsung Electronics | 39        | 22.29%  |
| Micron Technology   | 23        | 13.14%  |
| Kingston            | 15        | 8.57%   |
| Unknown             | 11        | 6.29%   |
| G.Skill             | 11        | 6.29%   |
| Corsair             | 9         | 5.14%   |
| Crucial             | 7         | 4%      |
| A-DATA Technology   | 7         | 4%      |
| Ramaxel Technology  | 3         | 1.71%   |
| Nanya Technology    | 2         | 1.14%   |
| Unknown (ABCD)      | 1         | 0.57%   |
| Transcend           | 1         | 0.57%   |
| Team                | 1         | 0.57%   |
| Patriot             | 1         | 0.57%   |
| Elpida              | 1         | 0.57%   |
| Avant               | 1         | 0.57%   |
| 4ea5                | 1         | 0.57%   |
| 48spaces            | 1         | 0.57%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 1.58%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 2         | 1.05%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 1.05%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 1.05%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 1.05%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.05%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.05%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.05%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 1.05%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1.05%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 1.05%   |
| Ramaxel RAM RMSA3260MH78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 2         | 1.05%   |
| Micron RAM MT62F2G32D8DR-031 WT 8GB SODIMM LPDDR5 6400MT/s       | 2         | 1.05%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 2         | 1.05%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 2         | 1.05%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s            | 2         | 1.05%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s           | 2         | 1.05%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 2         | 1.05%   |
| Unknown RAM Module 8GB DIMM DDR4 3200MT/s                        | 1         | 0.53%   |
| Unknown RAM Module 8192MB SODIMM LPDDR4 4266MT/s                 | 1         | 0.53%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s                     | 1         | 0.53%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 1         | 0.53%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 1         | 0.53%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                        | 1         | 0.53%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 1         | 0.53%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 1         | 0.53%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                         | 1         | 0.53%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 0.53%   |
| Transcend RAM TS512MSK64W6H 4GB SODIMM DDR3 1600MT/s             | 1         | 0.53%   |
| Team RAM TEAMGROUP-SD4-3200 16384MB SODIMM DDR4 3200MT/s         | 1         | 0.53%   |
| SK hynix RAM Module 512MB SODIMM DDR2 533MT/s                    | 1         | 0.53%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.53%   |
| SK hynix RAM Module 1GB SODIMM DDR 667MT/s                       | 1         | 0.53%   |
| SK hynix RAM HMT451U6MFR8C-C9 8GB SODIMM DDR4 2133MT/s           | 1         | 0.53%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1         | 0.53%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.53%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.53%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.53%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.53%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 1         | 0.53%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 73        | 48.03%  |
| DDR3    | 49        | 32.24%  |
| LPDDR5  | 7         | 4.61%   |
| LPDDR4  | 6         | 3.95%   |
| DDR5    | 5         | 3.29%   |
| LPDDR3  | 4         | 2.63%   |
| DDR2    | 4         | 2.63%   |
| Unknown | 3         | 1.97%   |
| DDR     | 1         | 0.66%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 92        | 60.13%  |
| DIMM         | 44        | 28.76%  |
| Row Of Chips | 16        | 10.46%  |
| Unknown      | 1         | 0.65%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 73        | 43.45%  |
| 4096  | 49        | 29.17%  |
| 16384 | 22        | 13.1%   |
| 2048  | 13        | 7.74%   |
| 1024  | 5         | 2.98%   |
| 512   | 3         | 1.79%   |
| 32768 | 2         | 1.19%   |
| 24576 | 1         | 0.6%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 34        | 20.24%  |
| 2667    | 27        | 16.07%  |
| 3200    | 24        | 14.29%  |
| 2400    | 12        | 7.14%   |
| 1333    | 12        | 7.14%   |
| 6400    | 7         | 4.17%   |
| 3600    | 6         | 3.57%   |
| 1334    | 6         | 3.57%   |
| 2133    | 5         | 2.98%   |
| 4800    | 3         | 1.79%   |
| 3866    | 3         | 1.79%   |
| 1867    | 3         | 1.79%   |
| 667     | 3         | 1.79%   |
| 533     | 3         | 1.79%   |
| 3733    | 2         | 1.19%   |
| 3534    | 2         | 1.19%   |
| 8400    | 1         | 0.6%    |
| 8200    | 1         | 0.6%    |
| 5600    | 1         | 0.6%    |
| 4267    | 1         | 0.6%    |
| 4266    | 1         | 0.6%    |
| 3333    | 1         | 0.6%    |
| 3266    | 1         | 0.6%    |
| 3066    | 1         | 0.6%    |
| 3000    | 1         | 0.6%    |
| 2933    | 1         | 0.6%    |
| 2800    | 1         | 0.6%    |
| 2666    | 1         | 0.6%    |
| 1866    | 1         | 0.6%    |
| 1800    | 1         | 0.6%    |
| 1067    | 1         | 0.6%    |
| Unknown | 1         | 0.6%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 42        | 28.77%  |
| IMC Networks                           | 18        | 12.33%  |
| Microdia                               | 13        | 8.9%    |
| Quanta                                 | 10        | 6.85%   |
| Realtek Semiconductor                  | 8         | 5.48%   |
| Acer                                   | 8         | 5.48%   |
| Logitech                               | 7         | 4.79%   |
| Sunplus Innovation Technology          | 6         | 4.11%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 3.42%   |
| Bison Electronics                      | 5         | 3.42%   |
| Syntek                                 | 4         | 2.74%   |
| Suyin                                  | 3         | 2.05%   |
| Luxvisions Innotech Limited            | 3         | 2.05%   |
| MacroSilicon                           | 2         | 1.37%   |
| Apple                                  | 2         | 1.37%   |
| WaveRider Communications               | 1         | 0.68%   |
| SunplusIT                              | 1         | 0.68%   |
| Sonix Technology                       | 1         | 0.68%   |
| Silicon Motion                         | 1         | 0.68%   |
| Samsung Electronics                    | 1         | 0.68%   |
| Microsoft                              | 1         | 0.68%   |
| Intel                                  | 1         | 0.68%   |
| GEMBIRD                                | 1         | 0.68%   |
| Asuscom Network                        | 1         | 0.68%   |
| Alcor Micro                            | 1         | 0.68%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 12        | 8.11%   |
| IMC Networks USB2.0 HD UVC WebCam             | 7         | 4.73%   |
| Chicony HP Truevision HD camera               | 4         | 2.7%    |
| Syntek Integrated Camera                      | 3         | 2.03%   |
| Suyin HP Truevision HD                        | 3         | 2.03%   |
| Realtek USB Camera                            | 3         | 2.03%   |
| Quanta HD User Facing                         | 3         | 2.03%   |
| Microdia Integrated_Webcam_HD                 | 3         | 2.03%   |
| Logitech Webcam C270                          | 3         | 2.03%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 3         | 2.03%   |
| Chicony USB 2.0 Camera                        | 3         | 2.03%   |
| Chicony HD Webcam                             | 3         | 2.03%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 3         | 2.03%   |
| Sunplus Integrated_Webcam_HD                  | 2         | 1.35%   |
| Quanta HP Webcam                              | 2         | 1.35%   |
| Microdia Webcam Vitade AF                     | 2         | 1.35%   |
| Microdia USB 2.0 Camera                       | 2         | 1.35%   |
| Microdia HP Integrated Webcam                 | 2         | 1.35%   |
| IMC Networks Integrated Camera                | 2         | 1.35%   |
| IMC Networks HD Camera                        | 2         | 1.35%   |
| Chicony USB2.0 VGA UVC WebCam                 | 2         | 1.35%   |
| Chicony USB2.0 Camera                         | 2         | 1.35%   |
| Chicony Lenovo EasyCamera                     | 2         | 1.35%   |
| Chicony Integrated Camera (1280x720@30)       | 2         | 1.35%   |
| Chicony HD WebCam (Acer)                      | 2         | 1.35%   |
| Chicony HD User Facing                        | 2         | 1.35%   |
| Chicony EasyCamera                            | 2         | 1.35%   |
| Bison SunplusIT Integrated Camera             | 2         | 1.35%   |
| Acer Integrated RGB Camera                    | 2         | 1.35%   |
| Acer Integrated Camera                        | 2         | 1.35%   |
| WaveRider USB Live camera                     | 1         | 0.68%   |
| Syntek EasyCamera                             | 1         | 0.68%   |
| SunplusIT XiaoMi USB 2.0 Webcam               | 1         | 0.68%   |
| Sunplus USB 2.0 Camera                        | 1         | 0.68%   |
| Sunplus PC Camera                             | 1         | 0.68%   |
| Sunplus Integrated_Webcam_FHD                 | 1         | 0.68%   |
| Sunplus HP Wide Vision HD                     | 1         | 0.68%   |
| Sonix NexiGo HD Webcam                        | 1         | 0.68%   |
| Silicon Motion WebCam SC-10HDD12636N          | 1         | 0.68%   |
| Samsung Galaxy series, misc. (MTP mode)       | 1         | 0.68%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 11        | 45.83%  |
| Shenzhen Goodix Technology | 5         | 20.83%  |
| Validity Sensors           | 3         | 12.5%   |
| Upek                       | 3         | 12.5%   |
| Elan Microelectronics      | 2         | 8.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 5         | 20.83%  |
| Shenzhen Goodix  Fingerprint Device                    | 4         | 16.67%  |
| Validity Sensors VFS 5011 fingerprint sensor           | 3         | 12.5%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 3         | 12.5%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 2         | 8.33%   |
| Synaptics WBDI Fingerprint Reader USB 086              | 1         | 4.17%   |
| Synaptics UWP WBDI Device                              | 1         | 4.17%   |
| Synaptics  WBDI                                        | 1         | 4.17%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 4.17%   |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 4.17%   |
| Elan ELAN:Fingerprint                                  | 1         | 4.17%   |
| Elan ELAN:ARM-M4                                       | 1         | 4.17%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 4         | 50%     |
| Lenovo      | 2         | 25%     |
| Broadcom    | 2         | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader            | 4         | 50%     |
| Lenovo Integrated Smart Card Reader            | 2         | 25%     |
| Broadcom BCM5880 Secure Applications Processor | 1         | 12.5%   |
| Broadcom 58200                                 | 1         | 12.5%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 162       | 73.3%   |
| 1     | 45        | 20.36%  |
| 2     | 12        | 5.43%   |
| 3     | 2         | 0.9%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 24        | 32.88%  |
| Graphics card            | 16        | 21.92%  |
| Net/wireless             | 8         | 10.96%  |
| Chipcard                 | 8         | 10.96%  |
| Sound                    | 4         | 5.48%   |
| Multimedia controller    | 4         | 5.48%   |
| Camera                   | 4         | 5.48%   |
| Communication controller | 2         | 2.74%   |
| Net/ethernet             | 1         | 1.37%   |
| Card reader              | 1         | 1.37%   |
| Bluetooth                | 1         | 1.37%   |

