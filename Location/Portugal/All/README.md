Linux in Portugal - Tested Hardware & Statistics
------------------------------------------------

A project to collect tested hardware configurations for Linux in Portugal.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Portugal/Desktop/README.md) and [notebooks](/Location/Portugal/Notebook/README.md).

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

Total: 2128

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | ENVY x360 Convertible 13... | Convertible | [5cfdd30fa7](https://linux-hardware.org/?probe=5cfdd30fa7) | May 01, 2023 |
| HUAWEI        | RLEF-XX                     | Notebook    | [b7ca4beb49](https://linux-hardware.org/?probe=b7ca4beb49) | Apr 30, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [c1fe7a5f87](https://linux-hardware.org/?probe=c1fe7a5f87) | Apr 30, 2023 |
| Acer          | E661GXM                     | Desktop     | [d5433b46bd](https://linux-hardware.org/?probe=d5433b46bd) | Apr 30, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [d4cfc1e964](https://linux-hardware.org/?probe=d4cfc1e964) | Apr 30, 2023 |
| ASUSTek       | X542URR                     | Notebook    | [910cdd940c](https://linux-hardware.org/?probe=910cdd940c) | Apr 28, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [a808e47839](https://linux-hardware.org/?probe=a808e47839) | Apr 28, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [67ae1efc54](https://linux-hardware.org/?probe=67ae1efc54) | Apr 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | Notebook    | [3a6e27c6ce](https://linux-hardware.org/?probe=3a6e27c6ce) | Apr 26, 2023 |
| Intel         | X99H                        | Desktop     | [d0f8c22128](https://linux-hardware.org/?probe=d0f8c22128) | Apr 26, 2023 |
| ASUSTek       | M4A78LT-M                   | Desktop     | [11f1e291a7](https://linux-hardware.org/?probe=11f1e291a7) | Apr 25, 2023 |
| Dell          | Inspiron 5521               | Notebook    | [8de2e801a3](https://linux-hardware.org/?probe=8de2e801a3) | Apr 23, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [67f15c6f4a](https://linux-hardware.org/?probe=67f15c6f4a) | Apr 22, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [1fc445ac89](https://linux-hardware.org/?probe=1fc445ac89) | Apr 22, 2023 |
| HP            | EliteBook 850 G5            | Notebook    | [ba9bbe1e70](https://linux-hardware.org/?probe=ba9bbe1e70) | Apr 21, 2023 |
| Dell          | Precision 5540              | Notebook    | [66b58fad6c](https://linux-hardware.org/?probe=66b58fad6c) | Apr 19, 2023 |
| Dell          | Precision 5540              | Notebook    | [e114fb911c](https://linux-hardware.org/?probe=e114fb911c) | Apr 19, 2023 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [b4c6c1198f](https://linux-hardware.org/?probe=b4c6c1198f) | Apr 19, 2023 |
| ASUSTek       | X541UJ                      | Notebook    | [1aa63436a5](https://linux-hardware.org/?probe=1aa63436a5) | Apr 19, 2023 |
| AAEON         | UPS-EHL01 V1.0              | Desktop     | [14471b218c](https://linux-hardware.org/?probe=14471b218c) | Apr 18, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [4174faae23](https://linux-hardware.org/?probe=4174faae23) | Apr 17, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [a2b27dd2d6](https://linux-hardware.org/?probe=a2b27dd2d6) | Apr 17, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [14517ef743](https://linux-hardware.org/?probe=14517ef743) | Apr 17, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [4ee307bb03](https://linux-hardware.org/?probe=4ee307bb03) | Apr 14, 2023 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | Notebook    | [1280936eba](https://linux-hardware.org/?probe=1280936eba) | Apr 13, 2023 |
| MSI           | Z370 PC PRO                 | Desktop     | [fb3078d5c3](https://linux-hardware.org/?probe=fb3078d5c3) | Apr 12, 2023 |
| Fujitsu       | LIFEBOOK U7411              | Notebook    | [b054f2bcd1](https://linux-hardware.org/?probe=b054f2bcd1) | Apr 12, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [238037e4b8](https://linux-hardware.org/?probe=238037e4b8) | Apr 11, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | Notebook    | [69f8d7dfdf](https://linux-hardware.org/?probe=69f8d7dfdf) | Apr 11, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [e0f6223c25](https://linux-hardware.org/?probe=e0f6223c25) | Apr 10, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [cb009d5401](https://linux-hardware.org/?probe=cb009d5401) | Apr 10, 2023 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [69ee985017](https://linux-hardware.org/?probe=69ee985017) | Apr 09, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [617f2a18bb](https://linux-hardware.org/?probe=617f2a18bb) | Apr 09, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [c2132caa73](https://linux-hardware.org/?probe=c2132caa73) | Apr 08, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [2f4fb987b8](https://linux-hardware.org/?probe=2f4fb987b8) | Apr 07, 2023 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [0258b5925f](https://linux-hardware.org/?probe=0258b5925f) | Apr 07, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [5ff7c0183d](https://linux-hardware.org/?probe=5ff7c0183d) | Apr 07, 2023 |
| Fujitsu       | LIFEBOOK E751               | Notebook    | [0bdc444de8](https://linux-hardware.org/?probe=0bdc444de8) | Apr 05, 2023 |
| Acer          | Aspire XC-330               | Desktop     | [a0e2b31c08](https://linux-hardware.org/?probe=a0e2b31c08) | Apr 05, 2023 |
| Dell          | Latitude 5430               | Notebook    | [6494113c9b](https://linux-hardware.org/?probe=6494113c9b) | Apr 04, 2023 |
| ASUSTek       | TUF Gaming FX705DY_TUF70... | Notebook    | [85e0077c83](https://linux-hardware.org/?probe=85e0077c83) | Apr 03, 2023 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [aead33a5e6](https://linux-hardware.org/?probe=aead33a5e6) | Apr 01, 2023 |
| MSI           | MAG A520M VECTOR WIFI       | Desktop     | [3c08cf9aba](https://linux-hardware.org/?probe=3c08cf9aba) | Apr 01, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [1da5570114](https://linux-hardware.org/?probe=1da5570114) | Apr 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [a1fa08efc6](https://linux-hardware.org/?probe=a1fa08efc6) | Mar 30, 2023 |
| HUAWEI        | RLEF-XX                     | Notebook    | [e9988edacd](https://linux-hardware.org/?probe=e9988edacd) | Mar 30, 2023 |
| Dell          | Latitude 7430               | Notebook    | [fdef205301](https://linux-hardware.org/?probe=fdef205301) | Mar 29, 2023 |
| ASUSTek       | P7P55D-E                    | Desktop     | [3db646f782](https://linux-hardware.org/?probe=3db646f782) | Mar 29, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [3b7fe31c07](https://linux-hardware.org/?probe=3b7fe31c07) | Mar 29, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [e6b01be2f1](https://linux-hardware.org/?probe=e6b01be2f1) | Mar 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [ebf2728d28](https://linux-hardware.org/?probe=ebf2728d28) | Mar 29, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [0aabfe954d](https://linux-hardware.org/?probe=0aabfe954d) | Mar 28, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [b7a0579d38](https://linux-hardware.org/?probe=b7a0579d38) | Mar 28, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [88d5c3bb9f](https://linux-hardware.org/?probe=88d5c3bb9f) | Mar 28, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [d7b0ec58d5](https://linux-hardware.org/?probe=d7b0ec58d5) | Mar 27, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | Notebook    | [701b74ce3e](https://linux-hardware.org/?probe=701b74ce3e) | Mar 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [537fc6af0e](https://linux-hardware.org/?probe=537fc6af0e) | Mar 26, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [e973d0294d](https://linux-hardware.org/?probe=e973d0294d) | Mar 22, 2023 |
| Lenovo        | IP 5-14ALC05 82LM           | Notebook    | [5bacaa401a](https://linux-hardware.org/?probe=5bacaa401a) | Mar 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [7fb78c1c79](https://linux-hardware.org/?probe=7fb78c1c79) | Mar 20, 2023 |
| ASUSTek       | M5A78L LE                   | Desktop     | [e18778e282](https://linux-hardware.org/?probe=e18778e282) | Mar 20, 2023 |
| Dell          | 0MY171 A00                  | Desktop     | [47fd974afd](https://linux-hardware.org/?probe=47fd974afd) | Mar 20, 2023 |
| HP            | 3646h                       | Desktop     | [812e12695b](https://linux-hardware.org/?probe=812e12695b) | Mar 19, 2023 |
| Intel         | NUC11PHBi7 M26151-404       | Mini pc     | [22290c7abf](https://linux-hardware.org/?probe=22290c7abf) | Mar 19, 2023 |
| Gigabyte      | A520M H                     | Desktop     | [a3cee7c278](https://linux-hardware.org/?probe=a3cee7c278) | Mar 19, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [7c770db7fd](https://linux-hardware.org/?probe=7c770db7fd) | Mar 18, 2023 |
| Unknown       | Unknown                     | Desktop     | [2389fcea33](https://linux-hardware.org/?probe=2389fcea33) | Mar 17, 2023 |
| ASUSTek       | PRIME H610M-A D4            | Desktop     | [9765f2823e](https://linux-hardware.org/?probe=9765f2823e) | Mar 16, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [f13da06079](https://linux-hardware.org/?probe=f13da06079) | Mar 15, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [e7dd32b931](https://linux-hardware.org/?probe=e7dd32b931) | Mar 15, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [557a08d242](https://linux-hardware.org/?probe=557a08d242) | Mar 15, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [48370f2817](https://linux-hardware.org/?probe=48370f2817) | Mar 14, 2023 |
| HP            | 3033h                       | Desktop     | [ab5e388ea9](https://linux-hardware.org/?probe=ab5e388ea9) | Mar 14, 2023 |
| Toshiba       | Satellite P300              | Notebook    | [1872bc8b57](https://linux-hardware.org/?probe=1872bc8b57) | Mar 14, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [59d2c50a02](https://linux-hardware.org/?probe=59d2c50a02) | Mar 14, 2023 |
| HP            | 3033h                       | Desktop     | [38ac77726b](https://linux-hardware.org/?probe=38ac77726b) | Mar 13, 2023 |
| ASUSTek       | X202EV                      | Notebook    | [db21e9ac28](https://linux-hardware.org/?probe=db21e9ac28) | Mar 13, 2023 |
| ASUSTek       | PRIME H610M-A D4            | Desktop     | [7a20b4f81a](https://linux-hardware.org/?probe=7a20b4f81a) | Mar 12, 2023 |
| HP            | ENVY Notebook               | Notebook    | [8a063efa19](https://linux-hardware.org/?probe=8a063efa19) | Mar 09, 2023 |
| MSI           | GF65 Thin 9SD               | Notebook    | [ea69b96e55](https://linux-hardware.org/?probe=ea69b96e55) | Mar 09, 2023 |
| Dell          | Latitude E4310              | Notebook    | [8dbe3e01fa](https://linux-hardware.org/?probe=8dbe3e01fa) | Mar 08, 2023 |
| Lenovo        | ThinkPad T470 20HD0001PG    | Notebook    | [be61e16d11](https://linux-hardware.org/?probe=be61e16d11) | Mar 08, 2023 |
| Dell          | Latitude E5570              | Notebook    | [5a5d668611](https://linux-hardware.org/?probe=5a5d668611) | Mar 07, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [2728efea53](https://linux-hardware.org/?probe=2728efea53) | Mar 05, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [7235211822](https://linux-hardware.org/?probe=7235211822) | Mar 05, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [e61f05b7f6](https://linux-hardware.org/?probe=e61f05b7f6) | Mar 05, 2023 |
| MSI           | GF72 8RD                    | Notebook    | [54eb266d2a](https://linux-hardware.org/?probe=54eb266d2a) | Mar 04, 2023 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [240adbe154](https://linux-hardware.org/?probe=240adbe154) | Mar 04, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C30... | Notebook    | [1fb81359e0](https://linux-hardware.org/?probe=1fb81359e0) | Mar 03, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [5715b4e8af](https://linux-hardware.org/?probe=5715b4e8af) | Mar 03, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [26b308e28a](https://linux-hardware.org/?probe=26b308e28a) | Mar 02, 2023 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [73776ef4dd](https://linux-hardware.org/?probe=73776ef4dd) | Mar 02, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [73c765dbe2](https://linux-hardware.org/?probe=73c765dbe2) | Mar 01, 2023 |
| ASUSTek       | Z87-PRO                     | Desktop     | [7997191f44](https://linux-hardware.org/?probe=7997191f44) | Feb 28, 2023 |
| ASUSTek       | Z87-PRO                     | Desktop     | [9a6bc5f3af](https://linux-hardware.org/?probe=9a6bc5f3af) | Feb 28, 2023 |
| Lenovo        | ThinkPad T480 20L6SEH700    | Notebook    | [4a187e016b](https://linux-hardware.org/?probe=4a187e016b) | Feb 27, 2023 |
| HP            | Compaq 6730b (FU594ES#AB... | Notebook    | [810cdb1ad1](https://linux-hardware.org/?probe=810cdb1ad1) | Feb 26, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [8fb68b4ad6](https://linux-hardware.org/?probe=8fb68b4ad6) | Feb 26, 2023 |
| Dell          | 0MY171 A00                  | Desktop     | [795f707b1a](https://linux-hardware.org/?probe=795f707b1a) | Feb 25, 2023 |
| Lenovo        | ThinkPad T480 20L5S03600    | Notebook    | [5c9736ab0c](https://linux-hardware.org/?probe=5c9736ab0c) | Feb 25, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [7b59cbd067](https://linux-hardware.org/?probe=7b59cbd067) | Feb 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [d99e163be6](https://linux-hardware.org/?probe=d99e163be6) | Feb 24, 2023 |
| HP            | mt40                        | Notebook    | [16e5f8eb5d](https://linux-hardware.org/?probe=16e5f8eb5d) | Feb 23, 2023 |
| MSI           | GF72 8RD                    | Notebook    | [cf6dad63da](https://linux-hardware.org/?probe=cf6dad63da) | Feb 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [022527aa4c](https://linux-hardware.org/?probe=022527aa4c) | Feb 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [3b1afb00a2](https://linux-hardware.org/?probe=3b1afb00a2) | Feb 21, 2023 |
| ASUSTek       | BM6630_BM6330_BP6230        | Desktop     | [e062475561](https://linux-hardware.org/?probe=e062475561) | Feb 20, 2023 |
| ASUSTek       | BM6630_BM6330_BP6230        | Desktop     | [5d6240bcc6](https://linux-hardware.org/?probe=5d6240bcc6) | Feb 19, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [fe75bac6ce](https://linux-hardware.org/?probe=fe75bac6ce) | Feb 19, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [605089c66c](https://linux-hardware.org/?probe=605089c66c) | Feb 19, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [387aa81d4c](https://linux-hardware.org/?probe=387aa81d4c) | Feb 18, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [ebaa8145e1](https://linux-hardware.org/?probe=ebaa8145e1) | Feb 18, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [a56a788adf](https://linux-hardware.org/?probe=a56a788adf) | Feb 17, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [bb1c4209c7](https://linux-hardware.org/?probe=bb1c4209c7) | Feb 17, 2023 |
| HP            | Laptop 15-bs1xx             | Notebook    | [88d9514231](https://linux-hardware.org/?probe=88d9514231) | Feb 17, 2023 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [42b7f88059](https://linux-hardware.org/?probe=42b7f88059) | Feb 16, 2023 |
| ASUSTek       | P5G41T-M LE                 | Desktop     | [3ebf4858b8](https://linux-hardware.org/?probe=3ebf4858b8) | Feb 16, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [ef69c22820](https://linux-hardware.org/?probe=ef69c22820) | Feb 16, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [4e6c625797](https://linux-hardware.org/?probe=4e6c625797) | Feb 15, 2023 |
| MSI           | Z68MA-ED55                  | Desktop     | [e2bd6f0fb4](https://linux-hardware.org/?probe=e2bd6f0fb4) | Feb 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [c2d957f650](https://linux-hardware.org/?probe=c2d957f650) | Feb 15, 2023 |
| Toshiba       | Satellite L500              | Notebook    | [da3617cc40](https://linux-hardware.org/?probe=da3617cc40) | Feb 14, 2023 |
| Gigabyte      | P65                         | Notebook    | [b3d7faba21](https://linux-hardware.org/?probe=b3d7faba21) | Feb 12, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [4344acac5e](https://linux-hardware.org/?probe=4344acac5e) | Feb 11, 2023 |
| Gigabyte      | P65                         | Notebook    | [25d871afca](https://linux-hardware.org/?probe=25d871afca) | Feb 11, 2023 |
| IBM           | 819046G                     | Desktop     | [a43370bbbd](https://linux-hardware.org/?probe=a43370bbbd) | Feb 11, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [b6b590fcdf](https://linux-hardware.org/?probe=b6b590fcdf) | Feb 11, 2023 |
| Dell          | Latitude 7370               | Notebook    | [30c62c9e44](https://linux-hardware.org/?probe=30c62c9e44) | Feb 10, 2023 |
| Dell          | Latitude 7370               | Notebook    | [b4e7a5cb63](https://linux-hardware.org/?probe=b4e7a5cb63) | Feb 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [25e4994344](https://linux-hardware.org/?probe=25e4994344) | Feb 09, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [d0319bdf17](https://linux-hardware.org/?probe=d0319bdf17) | Feb 09, 2023 |
| Acer          | Aspire S7-391               | Notebook    | [3777a7d1e9](https://linux-hardware.org/?probe=3777a7d1e9) | Feb 08, 2023 |
| MSI           | A78M-E35                    | Desktop     | [ba4515e5ea](https://linux-hardware.org/?probe=ba4515e5ea) | Feb 08, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [f268d3da5e](https://linux-hardware.org/?probe=f268d3da5e) | Feb 08, 2023 |
| Acer          | Aspire V3-572G              | Notebook    | [7b48d97053](https://linux-hardware.org/?probe=7b48d97053) | Feb 07, 2023 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [3bba794976](https://linux-hardware.org/?probe=3bba794976) | Feb 05, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [b2247eafed](https://linux-hardware.org/?probe=b2247eafed) | Feb 05, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [9299261af6](https://linux-hardware.org/?probe=9299261af6) | Feb 05, 2023 |
| Dell          | Precision 7550              | Notebook    | [9608ff008d](https://linux-hardware.org/?probe=9608ff008d) | Feb 04, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [e3ab731c3c](https://linux-hardware.org/?probe=e3ab731c3c) | Feb 02, 2023 |
| ASUSTek       | Z170-DELUXE                 | Desktop     | [d0cf3a9d76](https://linux-hardware.org/?probe=d0cf3a9d76) | Feb 02, 2023 |
| ASUSTek       | ZenBook UX425JA_UX425JA     | Notebook    | [367646ee16](https://linux-hardware.org/?probe=367646ee16) | Feb 02, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [a8f54f681a](https://linux-hardware.org/?probe=a8f54f681a) | Feb 01, 2023 |
| ASUSTek       | X555LD                      | Notebook    | [b70d834fe5](https://linux-hardware.org/?probe=b70d834fe5) | Jan 29, 2023 |
| INSYS         | GW1-W149                    | Notebook    | [5a4337006d](https://linux-hardware.org/?probe=5a4337006d) | Jan 28, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [1a9e67408e](https://linux-hardware.org/?probe=1a9e67408e) | Jan 28, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [0b05244a15](https://linux-hardware.org/?probe=0b05244a15) | Jan 27, 2023 |
| ASUSTek       | X541UJ                      | Notebook    | [d9ceb3c732](https://linux-hardware.org/?probe=d9ceb3c732) | Jan 27, 2023 |
| HP            | ProBook 640 G2              | Notebook    | [4e8cd1aa46](https://linux-hardware.org/?probe=4e8cd1aa46) | Jan 26, 2023 |
| Acer          | RS740DVF                    | Desktop     | [6aaeb06f9a](https://linux-hardware.org/?probe=6aaeb06f9a) | Jan 26, 2023 |
| Lenovo        | ThinkPad L490 20Q5002GPG    | Notebook    | [a9567dc72b](https://linux-hardware.org/?probe=a9567dc72b) | Jan 26, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [a8ee7729d5](https://linux-hardware.org/?probe=a8ee7729d5) | Jan 23, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [3a542dd368](https://linux-hardware.org/?probe=3a542dd368) | Jan 22, 2023 |
| ASUSTek       | UX360CA                     | Notebook    | [98fa78d117](https://linux-hardware.org/?probe=98fa78d117) | Jan 22, 2023 |
| Acer          | Aspire E1-522               | Notebook    | [ad5202642a](https://linux-hardware.org/?probe=ad5202642a) | Jan 22, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [f52614c5aa](https://linux-hardware.org/?probe=f52614c5aa) | Jan 21, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [27e484698b](https://linux-hardware.org/?probe=27e484698b) | Jan 20, 2023 |
| Pegatron      | Narra6                      | Desktop     | [ac9462ee8e](https://linux-hardware.org/?probe=ac9462ee8e) | Jan 20, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [09dbcb3ae4](https://linux-hardware.org/?probe=09dbcb3ae4) | Jan 20, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [a929c23a1b](https://linux-hardware.org/?probe=a929c23a1b) | Jan 20, 2023 |
| Lenovo        | ThinkPad T470p 20J60018M... | Notebook    | [9324b897c3](https://linux-hardware.org/?probe=9324b897c3) | Jan 19, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [11ce0ed5ad](https://linux-hardware.org/?probe=11ce0ed5ad) | Jan 18, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [95074766b9](https://linux-hardware.org/?probe=95074766b9) | Jan 18, 2023 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [cd6cedc906](https://linux-hardware.org/?probe=cd6cedc906) | Jan 17, 2023 |
| ASUSTek       | Benicia                     | Desktop     | [c0441ff1e5](https://linux-hardware.org/?probe=c0441ff1e5) | Jan 17, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [60a0157a51](https://linux-hardware.org/?probe=60a0157a51) | Jan 16, 2023 |
| Acer          | Predator PH315-51           | Notebook    | [0b2ae38776](https://linux-hardware.org/?probe=0b2ae38776) | Jan 16, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | Notebook    | [bbf1dabe59](https://linux-hardware.org/?probe=bbf1dabe59) | Jan 14, 2023 |
| ASUSTek       | X541UV                      | Notebook    | [d45c8ef0ac](https://linux-hardware.org/?probe=d45c8ef0ac) | Jan 13, 2023 |
| Acer          | Aspire V5-122               | Notebook    | [a25a7c3fb1](https://linux-hardware.org/?probe=a25a7c3fb1) | Jan 12, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [7c62282370](https://linux-hardware.org/?probe=7c62282370) | Jan 12, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | Notebook    | [e9783891d1](https://linux-hardware.org/?probe=e9783891d1) | Jan 12, 2023 |
| Acer          | Aspire 5742G                | Notebook    | [07f15478a7](https://linux-hardware.org/?probe=07f15478a7) | Jan 11, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [71c61d98b9](https://linux-hardware.org/?probe=71c61d98b9) | Jan 10, 2023 |
| MSI           | B350 KRAIT GAMING           | Desktop     | [d27b435baf](https://linux-hardware.org/?probe=d27b435baf) | Jan 10, 2023 |
| ASRock        | A320M-HDV R3.0              | Desktop     | [cb970f09e6](https://linux-hardware.org/?probe=cb970f09e6) | Jan 09, 2023 |
| HP            | 0AA4h                       | Desktop     | [8d177b0b8d](https://linux-hardware.org/?probe=8d177b0b8d) | Jan 09, 2023 |
| MSI           | H97 GAMING 3                | Desktop     | [39ec0d3441](https://linux-hardware.org/?probe=39ec0d3441) | Jan 09, 2023 |
| Unknown       | Unknown                     | Notebook    | [ce97b4a08f](https://linux-hardware.org/?probe=ce97b4a08f) | Jan 08, 2023 |
| ASUSTek       | GL753VE                     | Notebook    | [7e0d372f98](https://linux-hardware.org/?probe=7e0d372f98) | Jan 08, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [bdc427771d](https://linux-hardware.org/?probe=bdc427771d) | Jan 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [50d2637c41](https://linux-hardware.org/?probe=50d2637c41) | Jan 07, 2023 |
| HP            | 83EE                        | Desktop     | [cb43945233](https://linux-hardware.org/?probe=cb43945233) | Jan 07, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [aff5a2ce85](https://linux-hardware.org/?probe=aff5a2ce85) | Jan 07, 2023 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | Notebook    | [b69c9f59d5](https://linux-hardware.org/?probe=b69c9f59d5) | Jan 06, 2023 |
| Gigabyte      | H81M-S1                     | Desktop     | [db0e909d27](https://linux-hardware.org/?probe=db0e909d27) | Jan 06, 2023 |
| HP            | Pavilion dv6                | Notebook    | [9f0fb0adf5](https://linux-hardware.org/?probe=9f0fb0adf5) | Jan 04, 2023 |
| Toshiba       | Satellite C50D-B            | Notebook    | [e4bc0d4130](https://linux-hardware.org/?probe=e4bc0d4130) | Jan 04, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [e24802533e](https://linux-hardware.org/?probe=e24802533e) | Jan 03, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [eefb2d0334](https://linux-hardware.org/?probe=eefb2d0334) | Jan 03, 2023 |
| Gigabyte      | Z77P-D3                     | Desktop     | [76d75de6ac](https://linux-hardware.org/?probe=76d75de6ac) | Jan 02, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [dfb32a8abb](https://linux-hardware.org/?probe=dfb32a8abb) | Jan 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [bbd09c7b2c](https://linux-hardware.org/?probe=bbd09c7b2c) | Jan 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [013b1e7816](https://linux-hardware.org/?probe=013b1e7816) | Jan 02, 2023 |
| Acer          | Aspire 4310                 | Notebook    | [e179184ea3](https://linux-hardware.org/?probe=e179184ea3) | Jan 02, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [113a2a45b2](https://linux-hardware.org/?probe=113a2a45b2) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [34528f04fe](https://linux-hardware.org/?probe=34528f04fe) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [7295ec02b5](https://linux-hardware.org/?probe=7295ec02b5) | Dec 31, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [2161cbc9a0](https://linux-hardware.org/?probe=2161cbc9a0) | Dec 31, 2022 |
| ASUSTek       | Benicia                     | Desktop     | [9d307c5f2f](https://linux-hardware.org/?probe=9d307c5f2f) | Dec 31, 2022 |
| ASUSTek       | Benicia                     | Desktop     | [bc835cbca9](https://linux-hardware.org/?probe=bc835cbca9) | Dec 31, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [76e9829e66](https://linux-hardware.org/?probe=76e9829e66) | Dec 30, 2022 |
| Toshiba       | Satellite L775-12V          | Notebook    | [2c601f6366](https://linux-hardware.org/?probe=2c601f6366) | Dec 29, 2022 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [042fb842d2](https://linux-hardware.org/?probe=042fb842d2) | Dec 27, 2022 |
| ASUSTek       | B85M-GAMER                  | Desktop     | [ded2e7e4e6](https://linux-hardware.org/?probe=ded2e7e4e6) | Dec 26, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [b181e9e5a3](https://linux-hardware.org/?probe=b181e9e5a3) | Dec 26, 2022 |
| MSI           | B350 KRAIT GAMING           | Desktop     | [896aebf101](https://linux-hardware.org/?probe=896aebf101) | Dec 25, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [82f8802857](https://linux-hardware.org/?probe=82f8802857) | Dec 24, 2022 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | Notebook    | [f980d6ed2e](https://linux-hardware.org/?probe=f980d6ed2e) | Dec 23, 2022 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | Notebook    | [a5dcdfece2](https://linux-hardware.org/?probe=a5dcdfece2) | Dec 23, 2022 |
| Dell          | Latitude E4310              | Notebook    | [6386845196](https://linux-hardware.org/?probe=6386845196) | Dec 23, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [982f470134](https://linux-hardware.org/?probe=982f470134) | Dec 21, 2022 |
| HP            | 0980h                       | Desktop     | [d54665c87c](https://linux-hardware.org/?probe=d54665c87c) | Dec 21, 2022 |
| Dell          | Latitude E4310              | Notebook    | [7b184a032b](https://linux-hardware.org/?probe=7b184a032b) | Dec 21, 2022 |
| MSI           | H81M-P33                    | Desktop     | [5d91d96949](https://linux-hardware.org/?probe=5d91d96949) | Dec 20, 2022 |
| HP            | 0980h                       | Desktop     | [3faf0c7996](https://linux-hardware.org/?probe=3faf0c7996) | Dec 20, 2022 |
| Dell          | Inspiron N5050              | Notebook    | [41fb3c537a](https://linux-hardware.org/?probe=41fb3c537a) | Dec 19, 2022 |
| Thomson       | PT-NEO14A.2WH32             | Notebook    | [d028ff11a9](https://linux-hardware.org/?probe=d028ff11a9) | Dec 18, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [10e579b77e](https://linux-hardware.org/?probe=10e579b77e) | Dec 18, 2022 |
| Dell          | 03V7GF A01                  | Desktop     | [3847c61b81](https://linux-hardware.org/?probe=3847c61b81) | Dec 17, 2022 |
| Dell          | 03V7GF A01                  | Desktop     | [e491b54a3c](https://linux-hardware.org/?probe=e491b54a3c) | Dec 17, 2022 |
| Unknown       | Unknown                     | Desktop     | [988a2e80c0](https://linux-hardware.org/?probe=988a2e80c0) | Dec 17, 2022 |
| Gigabyte      | H57M-USB3                   | Desktop     | [d4812cfdb6](https://linux-hardware.org/?probe=d4812cfdb6) | Dec 13, 2022 |
| Dell          | 0MY171 A00                  | Desktop     | [055bc4ea78](https://linux-hardware.org/?probe=055bc4ea78) | Dec 13, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [49fad98b7b](https://linux-hardware.org/?probe=49fad98b7b) | Dec 12, 2022 |
| Gigabyte      | H57M-USB3                   | Desktop     | [c48aaf8b29](https://linux-hardware.org/?probe=c48aaf8b29) | Dec 12, 2022 |
| Dell          | Precision 5510              | Notebook    | [77b7f6dd95](https://linux-hardware.org/?probe=77b7f6dd95) | Dec 12, 2022 |
| ASRock        | G31M-GS                     | Desktop     | [2e1fc34b39](https://linux-hardware.org/?probe=2e1fc34b39) | Dec 11, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [d83227cce9](https://linux-hardware.org/?probe=d83227cce9) | Dec 10, 2022 |
| Sony          | VGN-FZ31Z                   | Notebook    | [4f392d3575](https://linux-hardware.org/?probe=4f392d3575) | Dec 10, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [8008043900](https://linux-hardware.org/?probe=8008043900) | Dec 10, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [de42f36422](https://linux-hardware.org/?probe=de42f36422) | Dec 10, 2022 |
| Acer          | Aspire A315-55G             | Notebook    | [0c6e399e4f](https://linux-hardware.org/?probe=0c6e399e4f) | Dec 09, 2022 |
| Acer          | Aspire A315-55G             | Notebook    | [9c083ab22c](https://linux-hardware.org/?probe=9c083ab22c) | Dec 09, 2022 |
| MSI           | GF72 8RD                    | Notebook    | [f943786d2c](https://linux-hardware.org/?probe=f943786d2c) | Dec 09, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [29c71a771b](https://linux-hardware.org/?probe=29c71a771b) | Dec 08, 2022 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [1519fb3a87](https://linux-hardware.org/?probe=1519fb3a87) | Dec 06, 2022 |
| MSI           | Z490-A PRO                  | Desktop     | [34157244aa](https://linux-hardware.org/?probe=34157244aa) | Dec 05, 2022 |
| Packard Be... | FIH57                       | Desktop     | [a98f4adbab](https://linux-hardware.org/?probe=a98f4adbab) | Dec 05, 2022 |
| HP            | Pavilion dv6                | Notebook    | [8a940a493b](https://linux-hardware.org/?probe=8a940a493b) | Dec 03, 2022 |
| Gigabyte      | GA-MA785GT-UD3H             | Desktop     | [5ab13c42b3](https://linux-hardware.org/?probe=5ab13c42b3) | Dec 03, 2022 |
| Gigabyte      | GA-MA785GT-UD3H             | Desktop     | [b3ab0684c5](https://linux-hardware.org/?probe=b3ab0684c5) | Dec 03, 2022 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [e28a13071a](https://linux-hardware.org/?probe=e28a13071a) | Dec 02, 2022 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [44a7c01e06](https://linux-hardware.org/?probe=44a7c01e06) | Dec 02, 2022 |
| MSI           | GF72 8RD                    | Notebook    | [c03f783ea5](https://linux-hardware.org/?probe=c03f783ea5) | Dec 01, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [a6a71120f2](https://linux-hardware.org/?probe=a6a71120f2) | Nov 30, 2022 |
| ASUSTek       | Benicia                     | Desktop     | [e5468e4258](https://linux-hardware.org/?probe=e5468e4258) | Nov 30, 2022 |
| Acer          | Nitro AN515-58              | Notebook    | [6bb64e8108](https://linux-hardware.org/?probe=6bb64e8108) | Nov 29, 2022 |
| Acer          | Aspire E1-570G              | Notebook    | [bbb8e289a9](https://linux-hardware.org/?probe=bbb8e289a9) | Nov 29, 2022 |
| Acer          | Aspire E1-570G              | Notebook    | [def1faf044](https://linux-hardware.org/?probe=def1faf044) | Nov 28, 2022 |
| ASUSTek       | N61Vg                       | Notebook    | [b5cc07b253](https://linux-hardware.org/?probe=b5cc07b253) | Nov 27, 2022 |
| MSI           | GF72 8RD                    | Notebook    | [fb92041c1b](https://linux-hardware.org/?probe=fb92041c1b) | Nov 26, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [59a39475dd](https://linux-hardware.org/?probe=59a39475dd) | Nov 26, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | Notebook    | [fa21163ace](https://linux-hardware.org/?probe=fa21163ace) | Nov 26, 2022 |
| HP            | 18E7                        | Desktop     | [5a5c2667a5](https://linux-hardware.org/?probe=5a5c2667a5) | Nov 26, 2022 |
| ASUSTek       | F7SR                        | Notebook    | [ecdba533ea](https://linux-hardware.org/?probe=ecdba533ea) | Nov 25, 2022 |
| ASUSTek       | F7SR                        | Notebook    | [8102d8b361](https://linux-hardware.org/?probe=8102d8b361) | Nov 25, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [ccf106edce](https://linux-hardware.org/?probe=ccf106edce) | Nov 24, 2022 |
| Gigabyte      | EG41MF-US2H                 | Desktop     | [07ac3ace2c](https://linux-hardware.org/?probe=07ac3ace2c) | Nov 24, 2022 |
| MSI           | Summit E16Flip A12UCT       | Notebook    | [95f653bddb](https://linux-hardware.org/?probe=95f653bddb) | Nov 24, 2022 |
| MSI           | Summit E16Flip A12UCT       | Notebook    | [a4a2b60b09](https://linux-hardware.org/?probe=a4a2b60b09) | Nov 24, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [2de63dfd54](https://linux-hardware.org/?probe=2de63dfd54) | Nov 23, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [99fc338b3e](https://linux-hardware.org/?probe=99fc338b3e) | Nov 23, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [814f45a510](https://linux-hardware.org/?probe=814f45a510) | Nov 23, 2022 |
| Apple         | MacBookAir5,1               | Notebook    | [2ded48104d](https://linux-hardware.org/?probe=2ded48104d) | Nov 22, 2022 |
| MSI           | 990FXA-GD65                 | Desktop     | [8e134485ce](https://linux-hardware.org/?probe=8e134485ce) | Nov 22, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [0584338e31](https://linux-hardware.org/?probe=0584338e31) | Nov 22, 2022 |
| Acer          | Popcorn                     | Notebook    | [6f446a097a](https://linux-hardware.org/?probe=6f446a097a) | Nov 20, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [dfb9f9524e](https://linux-hardware.org/?probe=dfb9f9524e) | Nov 20, 2022 |
| MSI           | 990FXA-GD65                 | Desktop     | [d41acd5075](https://linux-hardware.org/?probe=d41acd5075) | Nov 20, 2022 |
| ASRock        | B550 Extreme4               | Desktop     | [7fba8e38dc](https://linux-hardware.org/?probe=7fba8e38dc) | Nov 20, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [250885e79f](https://linux-hardware.org/?probe=250885e79f) | Nov 19, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | Notebook    | [02c6e2e360](https://linux-hardware.org/?probe=02c6e2e360) | Nov 18, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | Notebook    | [d4c27f1388](https://linux-hardware.org/?probe=d4c27f1388) | Nov 18, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [3b33d1989a](https://linux-hardware.org/?probe=3b33d1989a) | Nov 18, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [0401b9e939](https://linux-hardware.org/?probe=0401b9e939) | Nov 17, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [68db7ff193](https://linux-hardware.org/?probe=68db7ff193) | Nov 16, 2022 |
| Acer          | Aspire V3-575G              | Notebook    | [9044e30d53](https://linux-hardware.org/?probe=9044e30d53) | Nov 16, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [2455b541f5](https://linux-hardware.org/?probe=2455b541f5) | Nov 16, 2022 |
| ASUSTek       | G752VS                      | Notebook    | [364d6d09ab](https://linux-hardware.org/?probe=364d6d09ab) | Nov 14, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [c54708e797](https://linux-hardware.org/?probe=c54708e797) | Nov 14, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [c332019d7e](https://linux-hardware.org/?probe=c332019d7e) | Nov 14, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [e54df5cb0d](https://linux-hardware.org/?probe=e54df5cb0d) | Nov 13, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [2c896d28a8](https://linux-hardware.org/?probe=2c896d28a8) | Nov 13, 2022 |
| ASUSTek       | B85M-GAMER                  | Desktop     | [112508759b](https://linux-hardware.org/?probe=112508759b) | Nov 13, 2022 |
| ASUSTek       | A6JC                        | Notebook    | [dce6c2a8f4](https://linux-hardware.org/?probe=dce6c2a8f4) | Nov 13, 2022 |
| Packard Be... | EasyNote LV11HC             | Notebook    | [244d508935](https://linux-hardware.org/?probe=244d508935) | Nov 12, 2022 |
| ASUSTek       | P5KPL-AM EPU                | Desktop     | [dc1c83bed5](https://linux-hardware.org/?probe=dc1c83bed5) | Nov 11, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [c1f18206f4](https://linux-hardware.org/?probe=c1f18206f4) | Nov 11, 2022 |
| eMachines     | G525                        | Notebook    | [38b8684942](https://linux-hardware.org/?probe=38b8684942) | Nov 10, 2022 |
| ASUSTek       | N61Vg                       | Notebook    | [5205b24cb0](https://linux-hardware.org/?probe=5205b24cb0) | Nov 08, 2022 |
| Dell          | Latitude E6510              | Notebook    | [befb811cfe](https://linux-hardware.org/?probe=befb811cfe) | Nov 05, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [a1cef4e43d](https://linux-hardware.org/?probe=a1cef4e43d) | Nov 04, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [b58a40d876](https://linux-hardware.org/?probe=b58a40d876) | Nov 04, 2022 |
| Microsoft     | Surface Book 2              | Tablet      | [fe997bad04](https://linux-hardware.org/?probe=fe997bad04) | Nov 03, 2022 |
| IP3 Tech      | GB3                         | Mini pc     | [1bbd4f8bd9](https://linux-hardware.org/?probe=1bbd4f8bd9) | Nov 03, 2022 |
| ASUSTek       | N61Vg                       | Notebook    | [27f288e5f1](https://linux-hardware.org/?probe=27f288e5f1) | Nov 01, 2022 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [c46dd8d9b6](https://linux-hardware.org/?probe=c46dd8d9b6) | Nov 01, 2022 |
| Dell          | Latitude E6510              | Notebook    | [b346d71347](https://linux-hardware.org/?probe=b346d71347) | Oct 29, 2022 |
| Acer          | Aspire SW5-012              | Notebook    | [90dd31edc8](https://linux-hardware.org/?probe=90dd31edc8) | Oct 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [50a8c356f0](https://linux-hardware.org/?probe=50a8c356f0) | Oct 28, 2022 |
| Pegatron      | TRUCKEE                     | Desktop     | [2a6fe2bcd1](https://linux-hardware.org/?probe=2a6fe2bcd1) | Oct 28, 2022 |
| Acer          | Aspire ES1-131              | Notebook    | [f0edf4897a](https://linux-hardware.org/?probe=f0edf4897a) | Oct 26, 2022 |
| Dell          | Latitude 7320               | Notebook    | [f249267def](https://linux-hardware.org/?probe=f249267def) | Oct 26, 2022 |
| Samsung       | 870Z5E/880Z5E/680Z5E        | Notebook    | [8ebb941ac6](https://linux-hardware.org/?probe=8ebb941ac6) | Oct 26, 2022 |
| ASUSTek       | X542URR                     | Notebook    | [fe6fb20830](https://linux-hardware.org/?probe=fe6fb20830) | Oct 25, 2022 |
| Toshiba       | NB300                       | Notebook    | [c5aa7d3c5f](https://linux-hardware.org/?probe=c5aa7d3c5f) | Oct 25, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [ede3bcd3f3](https://linux-hardware.org/?probe=ede3bcd3f3) | Oct 24, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [fe9ec739e2](https://linux-hardware.org/?probe=fe9ec739e2) | Oct 24, 2022 |
| ASUSTek       | S550CB                      | Notebook    | [a81f0ecac8](https://linux-hardware.org/?probe=a81f0ecac8) | Oct 24, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [6354f13944](https://linux-hardware.org/?probe=6354f13944) | Oct 21, 2022 |
| HP            | G62                         | Notebook    | [721c09b331](https://linux-hardware.org/?probe=721c09b331) | Oct 19, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [e5f7b07e9c](https://linux-hardware.org/?probe=e5f7b07e9c) | Oct 19, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [25bb674789](https://linux-hardware.org/?probe=25bb674789) | Oct 19, 2022 |
| HP            | 8158 A01                    | Mini pc     | [d7021dfe8a](https://linux-hardware.org/?probe=d7021dfe8a) | Oct 17, 2022 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | Notebook    | [40771441a2](https://linux-hardware.org/?probe=40771441a2) | Oct 17, 2022 |
| ASUSTek       | X541UV                      | Notebook    | [ba7c1c3d83](https://linux-hardware.org/?probe=ba7c1c3d83) | Oct 14, 2022 |
| HP            | 805D                        | Desktop     | [ece9f05ea6](https://linux-hardware.org/?probe=ece9f05ea6) | Oct 14, 2022 |
| HP            | 805D                        | Desktop     | [f10271c447](https://linux-hardware.org/?probe=f10271c447) | Oct 14, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [ca8ac557b3](https://linux-hardware.org/?probe=ca8ac557b3) | Oct 14, 2022 |
| Toshiba       | Satellite L650              | Notebook    | [89f43e5484](https://linux-hardware.org/?probe=89f43e5484) | Oct 12, 2022 |
| Toshiba       | Satellite L650              | Notebook    | [43f57daebb](https://linux-hardware.org/?probe=43f57daebb) | Oct 12, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [d83c027361](https://linux-hardware.org/?probe=d83c027361) | Oct 12, 2022 |
| ASUSTek       | N53SV                       | Notebook    | [2460d79ba8](https://linux-hardware.org/?probe=2460d79ba8) | Oct 10, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [9eaf0bffca](https://linux-hardware.org/?probe=9eaf0bffca) | Oct 09, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [184ecb5e76](https://linux-hardware.org/?probe=184ecb5e76) | Oct 08, 2022 |
| ASUSTek       | G752VS                      | Notebook    | [df98c91ed6](https://linux-hardware.org/?probe=df98c91ed6) | Oct 08, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [be6a0fda35](https://linux-hardware.org/?probe=be6a0fda35) | Oct 08, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [76d2eeb1d0](https://linux-hardware.org/?probe=76d2eeb1d0) | Oct 07, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [8061516838](https://linux-hardware.org/?probe=8061516838) | Oct 06, 2022 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [abe6a3fde2](https://linux-hardware.org/?probe=abe6a3fde2) | Oct 06, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [a3d3100ffa](https://linux-hardware.org/?probe=a3d3100ffa) | Oct 05, 2022 |
| Acer          | Aspire ES1-520              | Notebook    | [b50cfdccab](https://linux-hardware.org/?probe=b50cfdccab) | Oct 05, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [8d863ae2d8](https://linux-hardware.org/?probe=8d863ae2d8) | Oct 04, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [a055ed4d2c](https://linux-hardware.org/?probe=a055ed4d2c) | Oct 03, 2022 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [1e0190a274](https://linux-hardware.org/?probe=1e0190a274) | Oct 03, 2022 |
| HP            | ENVY 15                     | Notebook    | [950623d8b2](https://linux-hardware.org/?probe=950623d8b2) | Oct 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [d9a196cd8e](https://linux-hardware.org/?probe=d9a196cd8e) | Oct 02, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [516795a4a8](https://linux-hardware.org/?probe=516795a4a8) | Oct 02, 2022 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [5bdf95fbdc](https://linux-hardware.org/?probe=5bdf95fbdc) | Oct 02, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [7ff2c5ad1c](https://linux-hardware.org/?probe=7ff2c5ad1c) | Oct 01, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [a64cec6a4d](https://linux-hardware.org/?probe=a64cec6a4d) | Oct 01, 2022 |
| MSI           | Modern 14 A10M              | Notebook    | [5c5666fa97](https://linux-hardware.org/?probe=5c5666fa97) | Sep 29, 2022 |
| GIADA         | ChiefRiver Platform         | Notebook    | [d0f71cdc7f](https://linux-hardware.org/?probe=d0f71cdc7f) | Sep 26, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [9fff405744](https://linux-hardware.org/?probe=9fff405744) | Sep 26, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [34035b63b6](https://linux-hardware.org/?probe=34035b63b6) | Sep 25, 2022 |
| HP            | ProBook 440 14 inch G9 N... | Notebook    | [84d47822bf](https://linux-hardware.org/?probe=84d47822bf) | Sep 24, 2022 |
| HP            | ProBook 440 14 inch G9 N... | Notebook    | [3afd2e892b](https://linux-hardware.org/?probe=3afd2e892b) | Sep 24, 2022 |
| Acer          | Predator PH315-51           | Notebook    | [24ae1f3fb8](https://linux-hardware.org/?probe=24ae1f3fb8) | Sep 23, 2022 |
| ASUSTek       | X556UF                      | Notebook    | [47f145c034](https://linux-hardware.org/?probe=47f145c034) | Sep 23, 2022 |
| ASUSTek       | X556UF                      | Notebook    | [2f1fe986d8](https://linux-hardware.org/?probe=2f1fe986d8) | Sep 23, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [7910fab01e](https://linux-hardware.org/?probe=7910fab01e) | Sep 22, 2022 |
| ASRock        | B550 Pro4                   | Desktop     | [a1009d700e](https://linux-hardware.org/?probe=a1009d700e) | Sep 21, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [910b604abc](https://linux-hardware.org/?probe=910b604abc) | Sep 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [b72e23e590](https://linux-hardware.org/?probe=b72e23e590) | Sep 20, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [70a7e5cad3](https://linux-hardware.org/?probe=70a7e5cad3) | Sep 20, 2022 |
| MSI           | Z77A-G45                    | Desktop     | [b5a8d40602](https://linux-hardware.org/?probe=b5a8d40602) | Sep 18, 2022 |
| Toshiba       | Satellite P845T             | Notebook    | [0d5f5ac925](https://linux-hardware.org/?probe=0d5f5ac925) | Sep 17, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [dd6d053ae2](https://linux-hardware.org/?probe=dd6d053ae2) | Sep 17, 2022 |
| ASUSTek       | N550LF                      | Notebook    | [73f2edfe65](https://linux-hardware.org/?probe=73f2edfe65) | Sep 16, 2022 |
| ASUSTek       | X555LJ                      | Notebook    | [5d27ea49aa](https://linux-hardware.org/?probe=5d27ea49aa) | Sep 13, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [d4fb6aa0ae](https://linux-hardware.org/?probe=d4fb6aa0ae) | Sep 13, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [e558fd5212](https://linux-hardware.org/?probe=e558fd5212) | Sep 13, 2022 |
| Lenovo        | ThinkPad W540 20BG0016US    | Notebook    | [9f0543edc4](https://linux-hardware.org/?probe=9f0543edc4) | Sep 11, 2022 |
| Chuwi         | CoreBook X                  | Notebook    | [4f29128588](https://linux-hardware.org/?probe=4f29128588) | Sep 11, 2022 |
| ASUSTek       | P5L-VM 1394                 | Desktop     | [a7931f2026](https://linux-hardware.org/?probe=a7931f2026) | Sep 10, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [eb81d635df](https://linux-hardware.org/?probe=eb81d635df) | Sep 10, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [71717109c3](https://linux-hardware.org/?probe=71717109c3) | Sep 10, 2022 |
| System76      | Oryx Pro                    | Notebook    | [d84de42ab6](https://linux-hardware.org/?probe=d84de42ab6) | Sep 10, 2022 |
| Apple         | Mac-F2218FA9                | All in one  | [4a791df589](https://linux-hardware.org/?probe=4a791df589) | Sep 10, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [ab939db2c0](https://linux-hardware.org/?probe=ab939db2c0) | Sep 10, 2022 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | Notebook    | [f9604390e8](https://linux-hardware.org/?probe=f9604390e8) | Sep 10, 2022 |
| Rockchip      | RK3318 BOX                  | Soc         | [bf1aba4ebe](https://linux-hardware.org/?probe=bf1aba4ebe) | Sep 10, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [132a8e025a](https://linux-hardware.org/?probe=132a8e025a) | Sep 07, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [038f57c2d8](https://linux-hardware.org/?probe=038f57c2d8) | Sep 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [5d61bcd114](https://linux-hardware.org/?probe=5d61bcd114) | Sep 06, 2022 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | Notebook    | [bcd73bee62](https://linux-hardware.org/?probe=bcd73bee62) | Sep 06, 2022 |
| HP            | Pavilion g6                 | Notebook    | [770b1a8154](https://linux-hardware.org/?probe=770b1a8154) | Sep 05, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [c2cd1091cd](https://linux-hardware.org/?probe=c2cd1091cd) | Sep 04, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [66724351c4](https://linux-hardware.org/?probe=66724351c4) | Sep 04, 2022 |
| Sony          | VGN-FZ31Z                   | Notebook    | [b99831e9f4](https://linux-hardware.org/?probe=b99831e9f4) | Sep 03, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [a74d79fc0b](https://linux-hardware.org/?probe=a74d79fc0b) | Sep 02, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [8a7e7ce8ea](https://linux-hardware.org/?probe=8a7e7ce8ea) | Sep 01, 2022 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [6fa51d2c4e](https://linux-hardware.org/?probe=6fa51d2c4e) | Aug 31, 2022 |
| OEM           | Intel H81                   | Desktop     | [4b45e6dc61](https://linux-hardware.org/?probe=4b45e6dc61) | Aug 31, 2022 |
| ASUSTek       | X541UJ                      | Notebook    | [0cd33aa36a](https://linux-hardware.org/?probe=0cd33aa36a) | Aug 31, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [11efd3dbe0](https://linux-hardware.org/?probe=11efd3dbe0) | Aug 30, 2022 |
| Toshiba       | Satellite A300              | Notebook    | [f90886ae85](https://linux-hardware.org/?probe=f90886ae85) | Aug 30, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [3b26a2ffe2](https://linux-hardware.org/?probe=3b26a2ffe2) | Aug 29, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [98ac365e3c](https://linux-hardware.org/?probe=98ac365e3c) | Aug 28, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [73db272ecb](https://linux-hardware.org/?probe=73db272ecb) | Aug 28, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [ee07c7a93a](https://linux-hardware.org/?probe=ee07c7a93a) | Aug 27, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [8ffebf0c43](https://linux-hardware.org/?probe=8ffebf0c43) | Aug 26, 2022 |
| ASUSTek       | Benicia                     | Desktop     | [08f930384d](https://linux-hardware.org/?probe=08f930384d) | Aug 25, 2022 |
| ASUSTek       | N61Vg                       | Notebook    | [30be913709](https://linux-hardware.org/?probe=30be913709) | Aug 25, 2022 |
| HP            | ProBook 640 G2              | Notebook    | [fc50d4e200](https://linux-hardware.org/?probe=fc50d4e200) | Aug 25, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [cb533d9c12](https://linux-hardware.org/?probe=cb533d9c12) | Aug 22, 2022 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [ba3fb2513f](https://linux-hardware.org/?probe=ba3fb2513f) | Aug 21, 2022 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [7ee8720a43](https://linux-hardware.org/?probe=7ee8720a43) | Aug 21, 2022 |
| MSI           | Z370 PC PRO                 | Desktop     | [9131aa23c4](https://linux-hardware.org/?probe=9131aa23c4) | Aug 20, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [ed1f055157](https://linux-hardware.org/?probe=ed1f055157) | Aug 19, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [764eaea2ba](https://linux-hardware.org/?probe=764eaea2ba) | Aug 19, 2022 |
| Lenovo        | ThinkPad P50 20EN0005PG     | Notebook    | [69c8e5eedc](https://linux-hardware.org/?probe=69c8e5eedc) | Aug 19, 2022 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [2bf774fae7](https://linux-hardware.org/?probe=2bf774fae7) | Aug 18, 2022 |
| MSI           | B85M-E45                    | Desktop     | [cb991c0789](https://linux-hardware.org/?probe=cb991c0789) | Aug 17, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [57732104cd](https://linux-hardware.org/?probe=57732104cd) | Aug 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [315da58d24](https://linux-hardware.org/?probe=315da58d24) | Aug 16, 2022 |
| Lenovo        | ThinkPad T430 2349V4B       | Notebook    | [0f919e20c7](https://linux-hardware.org/?probe=0f919e20c7) | Aug 14, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [76483c9f78](https://linux-hardware.org/?probe=76483c9f78) | Aug 14, 2022 |
| ASUSTek       | Basswood                    | Desktop     | [26e4efad3f](https://linux-hardware.org/?probe=26e4efad3f) | Aug 14, 2022 |
| ASUSTek       | N53SN                       | Notebook    | [6cb4ac4247](https://linux-hardware.org/?probe=6cb4ac4247) | Aug 14, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [73a3d7c1cf](https://linux-hardware.org/?probe=73a3d7c1cf) | Aug 12, 2022 |
| ASRock        | H410M-HVS                   | Desktop     | [4d1acc8488](https://linux-hardware.org/?probe=4d1acc8488) | Aug 11, 2022 |
| MSI           | Modern 14 A10RB             | Notebook    | [9979c66e3e](https://linux-hardware.org/?probe=9979c66e3e) | Aug 11, 2022 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | Desktop     | [48b0dfdee0](https://linux-hardware.org/?probe=48b0dfdee0) | Aug 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [9d6be5eb68](https://linux-hardware.org/?probe=9d6be5eb68) | Aug 08, 2022 |
| ASUSTek       | P8Z77-V                     | Desktop     | [18935d4aff](https://linux-hardware.org/?probe=18935d4aff) | Aug 07, 2022 |
| Apple         | MacBookAir6,1               | Notebook    | [154468415c](https://linux-hardware.org/?probe=154468415c) | Aug 05, 2022 |
| Apple         | MacBookAir6,1               | Notebook    | [6f355de994](https://linux-hardware.org/?probe=6f355de994) | Aug 04, 2022 |
| Toshiba       | Satellite U840              | Notebook    | [5ebf9417bf](https://linux-hardware.org/?probe=5ebf9417bf) | Aug 04, 2022 |
| MSI           | Modern 14 A10RB             | Notebook    | [abf1fcf08b](https://linux-hardware.org/?probe=abf1fcf08b) | Aug 02, 2022 |
| ASUSTek       | P8H67                       | Desktop     | [508b0275e3](https://linux-hardware.org/?probe=508b0275e3) | Aug 02, 2022 |
| Gigabyte      | H110M-Gaming3-CF            | Desktop     | [99a140d79b](https://linux-hardware.org/?probe=99a140d79b) | Aug 01, 2022 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [d1ae6a188c](https://linux-hardware.org/?probe=d1ae6a188c) | Jul 31, 2022 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [bce4496b78](https://linux-hardware.org/?probe=bce4496b78) | Jul 31, 2022 |
| HP            | Pavilion dv2000 (RQ116PA... | Notebook    | [c6ce2d4317](https://linux-hardware.org/?probe=c6ce2d4317) | Jul 31, 2022 |
| HP            | Pavilion dv2000 (RQ116PA... | Notebook    | [eca5fa0c39](https://linux-hardware.org/?probe=eca5fa0c39) | Jul 31, 2022 |
| ASUSTek       | P5G41C-M LX                 | Desktop     | [4e30dc6361](https://linux-hardware.org/?probe=4e30dc6361) | Jul 31, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [ea83758651](https://linux-hardware.org/?probe=ea83758651) | Jul 30, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [bc5b132a8d](https://linux-hardware.org/?probe=bc5b132a8d) | Jul 29, 2022 |
| Toshiba       | Satellite U840              | Notebook    | [c3f00f5b90](https://linux-hardware.org/?probe=c3f00f5b90) | Jul 29, 2022 |
| ASUSTek       | N53SN                       | Notebook    | [2e35ef4a8a](https://linux-hardware.org/?probe=2e35ef4a8a) | Jul 28, 2022 |
| Apple         | Mac-F2238AC8                | All in one  | [5eb6c551b0](https://linux-hardware.org/?probe=5eb6c551b0) | Jul 26, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [0c310749f1](https://linux-hardware.org/?probe=0c310749f1) | Jul 26, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e95cafce19](https://linux-hardware.org/?probe=e95cafce19) | Jul 26, 2022 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [ae71cae955](https://linux-hardware.org/?probe=ae71cae955) | Jul 25, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [ae16c8863a](https://linux-hardware.org/?probe=ae16c8863a) | Jul 25, 2022 |
| ASUSTek       | X540LJ                      | Notebook    | [264bb2f2a1](https://linux-hardware.org/?probe=264bb2f2a1) | Jul 23, 2022 |
| ASUSTek       | X540LJ                      | Notebook    | [fc5c252e6e](https://linux-hardware.org/?probe=fc5c252e6e) | Jul 23, 2022 |
| ASUSTek       | PRIME H570M-PLUS            | Desktop     | [b3dbd37276](https://linux-hardware.org/?probe=b3dbd37276) | Jul 22, 2022 |
| MSI           | A78M-E45 V2                 | Desktop     | [c5007c5729](https://linux-hardware.org/?probe=c5007c5729) | Jul 22, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [323aa03c61](https://linux-hardware.org/?probe=323aa03c61) | Jul 18, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [528f562110](https://linux-hardware.org/?probe=528f562110) | Jul 18, 2022 |
| Packard Be... | EasyNote LV11HC             | Notebook    | [c0693d5f9a](https://linux-hardware.org/?probe=c0693d5f9a) | Jul 18, 2022 |
| ASUSTek       | P8Z77-V                     | Desktop     | [bb9f40d075](https://linux-hardware.org/?probe=bb9f40d075) | Jul 18, 2022 |
| Sony          | SVF1521F6EW                 | Notebook    | [3f359d9763](https://linux-hardware.org/?probe=3f359d9763) | Jul 17, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [e1313016ee](https://linux-hardware.org/?probe=e1313016ee) | Jul 17, 2022 |
| ASUSTek       | EX-A320M-GAMING             | Desktop     | [68884b1723](https://linux-hardware.org/?probe=68884b1723) | Jul 17, 2022 |
| Sony          | VPCEB3L1E                   | Notebook    | [310a2ada05](https://linux-hardware.org/?probe=310a2ada05) | Jul 13, 2022 |
| Sony          | VPCEB3L1E                   | Notebook    | [247411abde](https://linux-hardware.org/?probe=247411abde) | Jul 13, 2022 |
| Acer          | FMCP7AM                     | Desktop     | [f2fc2e98c3](https://linux-hardware.org/?probe=f2fc2e98c3) | Jul 10, 2022 |
| IP3 Tech      | AH215                       | All in one  | [10fb10ae7f](https://linux-hardware.org/?probe=10fb10ae7f) | Jul 08, 2022 |
| Sony          | VPCEB3L1E                   | Notebook    | [9af59fca26](https://linux-hardware.org/?probe=9af59fca26) | Jul 08, 2022 |
| ASUSTek       | X540LJ                      | Notebook    | [5994a314d0](https://linux-hardware.org/?probe=5994a314d0) | Jul 05, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [4f31f807cb](https://linux-hardware.org/?probe=4f31f807cb) | Jul 05, 2022 |
| Sony          | VGN-FZ31Z                   | Notebook    | [62d8b20ff8](https://linux-hardware.org/?probe=62d8b20ff8) | Jul 04, 2022 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [03bede7266](https://linux-hardware.org/?probe=03bede7266) | Jul 03, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [15088a414c](https://linux-hardware.org/?probe=15088a414c) | Jul 03, 2022 |
| MSI           | B450M BAZOOKA V2            | Desktop     | [bded0a2071](https://linux-hardware.org/?probe=bded0a2071) | Jul 03, 2022 |
| Acer          | Aspire A515-54G             | Notebook    | [c0975c6877](https://linux-hardware.org/?probe=c0975c6877) | Jul 02, 2022 |
| ASUSTek       | N61Jq                       | Notebook    | [19b3d15d92](https://linux-hardware.org/?probe=19b3d15d92) | Jul 02, 2022 |
| Acer          | Aspire A515-54G             | Notebook    | [92d695d6be](https://linux-hardware.org/?probe=92d695d6be) | Jul 02, 2022 |
| HP            | 8169                        | Desktop     | [18c6ea7678](https://linux-hardware.org/?probe=18c6ea7678) | Jul 01, 2022 |
| HP            | 8169                        | Desktop     | [c479baadc1](https://linux-hardware.org/?probe=c479baadc1) | Jul 01, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [b691598870](https://linux-hardware.org/?probe=b691598870) | Jul 01, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [91c5f849c5](https://linux-hardware.org/?probe=91c5f849c5) | Jun 29, 2022 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | Notebook    | [17cb04c5f5](https://linux-hardware.org/?probe=17cb04c5f5) | Jun 29, 2022 |
| HP            | x2 210 G2                   | Tablet      | [812530aed8](https://linux-hardware.org/?probe=812530aed8) | Jun 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1c4ace32a2](https://linux-hardware.org/?probe=1c4ace32a2) | Jun 27, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [3c116356e3](https://linux-hardware.org/?probe=3c116356e3) | Jun 26, 2022 |
| MSI           | A78M-E45 V2                 | Desktop     | [e4cd6586b4](https://linux-hardware.org/?probe=e4cd6586b4) | Jun 26, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d4b96de9b6](https://linux-hardware.org/?probe=d4b96de9b6) | Jun 24, 2022 |
| Sony          | VPCEH2J1E                   | Notebook    | [7dde3ae196](https://linux-hardware.org/?probe=7dde3ae196) | Jun 23, 2022 |
| HP            | EliteBook 820 G1            | Notebook    | [ff4b7698ed](https://linux-hardware.org/?probe=ff4b7698ed) | Jun 23, 2022 |
| Gigabyte      | H310M H                     | Desktop     | [90038bfa8e](https://linux-hardware.org/?probe=90038bfa8e) | Jun 22, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [fd65aaa4b3](https://linux-hardware.org/?probe=fd65aaa4b3) | Jun 21, 2022 |
| MSI           | A78M-E45 V2                 | Desktop     | [97b9d51036](https://linux-hardware.org/?probe=97b9d51036) | Jun 20, 2022 |
| HP            | ProLiant DL385 G7           | Server      | [89a03359cd](https://linux-hardware.org/?probe=89a03359cd) | Jun 20, 2022 |
| Toshiba       | NB305                       | Notebook    | [1280ac15ba](https://linux-hardware.org/?probe=1280ac15ba) | Jun 17, 2022 |
| MSI           | B85M-E45                    | Desktop     | [58c2ff96e3](https://linux-hardware.org/?probe=58c2ff96e3) | Jun 17, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [d9b85c0e15](https://linux-hardware.org/?probe=d9b85c0e15) | Jun 16, 2022 |
| MSI           | A78M-E45 V2                 | Desktop     | [86394fa5df](https://linux-hardware.org/?probe=86394fa5df) | Jun 16, 2022 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [4b1946451e](https://linux-hardware.org/?probe=4b1946451e) | Jun 15, 2022 |
| MSI           | A78M-E45 V2                 | Desktop     | [a2d26ab800](https://linux-hardware.org/?probe=a2d26ab800) | Jun 14, 2022 |
| ASUSTek       | AT5IONT-I                   | Desktop     | [70438d549d](https://linux-hardware.org/?probe=70438d549d) | Jun 14, 2022 |
| ASUSTek       | AT5IONT-I                   | Desktop     | [56abd525d8](https://linux-hardware.org/?probe=56abd525d8) | Jun 14, 2022 |
| ASUSTek       | E403SA                      | Notebook    | [9ca6a865ff](https://linux-hardware.org/?probe=9ca6a865ff) | Jun 11, 2022 |
| Apple         | MacBookAir6,1               | Notebook    | [f0883ab59b](https://linux-hardware.org/?probe=f0883ab59b) | Jun 10, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [35dc89f7ff](https://linux-hardware.org/?probe=35dc89f7ff) | Jun 09, 2022 |
| Toshiba       | QOSMIO X770                 | Notebook    | [d11736c26f](https://linux-hardware.org/?probe=d11736c26f) | Jun 09, 2022 |
| HP            | ProLiant DL385 G7           | Server      | [a232d0abd8](https://linux-hardware.org/?probe=a232d0abd8) | Jun 08, 2022 |
| Toshiba       | Satellite T130              | Notebook    | [b5ba2dac2a](https://linux-hardware.org/?probe=b5ba2dac2a) | Jun 06, 2022 |
| Toshiba       | Satellite T130              | Notebook    | [3fe154a2ce](https://linux-hardware.org/?probe=3fe154a2ce) | Jun 06, 2022 |
| MSI           | B460M-A PRO                 | Desktop     | [c858bede94](https://linux-hardware.org/?probe=c858bede94) | Jun 05, 2022 |
| Dell          | 05XGC8 A01                  | Desktop     | [2a1316250b](https://linux-hardware.org/?probe=2a1316250b) | Jun 05, 2022 |
| Sony          | VGN-FZ31Z                   | Notebook    | [f9b7b79d5a](https://linux-hardware.org/?probe=f9b7b79d5a) | Jun 04, 2022 |
| Dell          | Latitude E6400              | Notebook    | [67a5bdc1aa](https://linux-hardware.org/?probe=67a5bdc1aa) | Jun 04, 2022 |
| HP            | Compaq nx7300 (RU464EA#A... | Notebook    | [a44ec57985](https://linux-hardware.org/?probe=a44ec57985) | Jun 02, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [8aff04335d](https://linux-hardware.org/?probe=8aff04335d) | Jun 01, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [029a55ffb4](https://linux-hardware.org/?probe=029a55ffb4) | Jun 01, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [24fb23a450](https://linux-hardware.org/?probe=24fb23a450) | May 31, 2022 |
| Lenovo        | ThinkPad T530 2394C98       | Notebook    | [b5aebb2490](https://linux-hardware.org/?probe=b5aebb2490) | May 30, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [f47dbc0616](https://linux-hardware.org/?probe=f47dbc0616) | May 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [e72ac27af1](https://linux-hardware.org/?probe=e72ac27af1) | May 30, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [eb522816a1](https://linux-hardware.org/?probe=eb522816a1) | May 29, 2022 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [9399a639c8](https://linux-hardware.org/?probe=9399a639c8) | May 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [de7ed0046e](https://linux-hardware.org/?probe=de7ed0046e) | May 29, 2022 |
| Lenovo        | ThinkPad X230 2325N66       | Notebook    | [2061351dbc](https://linux-hardware.org/?probe=2061351dbc) | May 28, 2022 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [42b16ce834](https://linux-hardware.org/?probe=42b16ce834) | May 28, 2022 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [4620e51e7b](https://linux-hardware.org/?probe=4620e51e7b) | May 28, 2022 |
| Lenovo        | ThinkPad L490 20Q5002GPG    | Notebook    | [9e1d2f7e8a](https://linux-hardware.org/?probe=9e1d2f7e8a) | May 26, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | Notebook    | [533beb13eb](https://linux-hardware.org/?probe=533beb13eb) | May 26, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [f2e5a856f4](https://linux-hardware.org/?probe=f2e5a856f4) | May 25, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [d98649058e](https://linux-hardware.org/?probe=d98649058e) | May 24, 2022 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [37f92aa173](https://linux-hardware.org/?probe=37f92aa173) | May 21, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [00a44d4f7e](https://linux-hardware.org/?probe=00a44d4f7e) | May 21, 2022 |
| Fujitsu       | D3403-A1 S26361-D3403-A1    | Desktop     | [ccf347729e](https://linux-hardware.org/?probe=ccf347729e) | May 19, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [93b08c2d75](https://linux-hardware.org/?probe=93b08c2d75) | May 19, 2022 |
| HP            | EliteBook 8540w             | Notebook    | [2f973c22ec](https://linux-hardware.org/?probe=2f973c22ec) | May 19, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [1ef52e97fa](https://linux-hardware.org/?probe=1ef52e97fa) | May 18, 2022 |
| ASUSTek       | Maximus IV Extreme          | Desktop     | [08dedbb3cb](https://linux-hardware.org/?probe=08dedbb3cb) | May 18, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [a46fea4edb](https://linux-hardware.org/?probe=a46fea4edb) | May 18, 2022 |
| Dell          | 0HN7XN A00                  | Desktop     | [6fba9a10da](https://linux-hardware.org/?probe=6fba9a10da) | May 18, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [a83bed6668](https://linux-hardware.org/?probe=a83bed6668) | May 16, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [a2ae5d95dd](https://linux-hardware.org/?probe=a2ae5d95dd) | May 15, 2022 |
| Notebook      | NB50TJ1_TK1                 | Notebook    | [8789da25ba](https://linux-hardware.org/?probe=8789da25ba) | May 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [58f371c0d7](https://linux-hardware.org/?probe=58f371c0d7) | May 13, 2022 |
| Lenovo        | ThinkPad X61 7673AQ5        | Notebook    | [42a17c86f4](https://linux-hardware.org/?probe=42a17c86f4) | May 13, 2022 |
| ASRockRack    | X399D8A-2T                  | Desktop     | [f1d2fbc435](https://linux-hardware.org/?probe=f1d2fbc435) | May 12, 2022 |
| MSI           | GT72VR 6RD                  | Notebook    | [c4cf6c9cd0](https://linux-hardware.org/?probe=c4cf6c9cd0) | May 12, 2022 |
| Gigabyte      | Z77P-D3                     | Desktop     | [40de59e6f7](https://linux-hardware.org/?probe=40de59e6f7) | May 10, 2022 |
| MSI           | Modern 15 A10RAS            | Notebook    | [3e844bb07a](https://linux-hardware.org/?probe=3e844bb07a) | May 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [f837aaeb12](https://linux-hardware.org/?probe=f837aaeb12) | May 08, 2022 |
| HP            | Pavilion g6                 | Notebook    | [69406bff46](https://linux-hardware.org/?probe=69406bff46) | May 08, 2022 |
| HP            | Pavilion g6                 | Notebook    | [56ca785331](https://linux-hardware.org/?probe=56ca785331) | May 08, 2022 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [c589ad9143](https://linux-hardware.org/?probe=c589ad9143) | May 07, 2022 |
| ASUSTek       | M4A78LT-M                   | Desktop     | [2a10a13430](https://linux-hardware.org/?probe=2a10a13430) | May 06, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [d24187e845](https://linux-hardware.org/?probe=d24187e845) | May 05, 2022 |
| HP            | ProBook 640 G2              | Notebook    | [50ccff3e1a](https://linux-hardware.org/?probe=50ccff3e1a) | May 04, 2022 |
| ASUSTek       | X540SAA                     | Notebook    | [9943699a6b](https://linux-hardware.org/?probe=9943699a6b) | May 04, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [47aaf6f556](https://linux-hardware.org/?probe=47aaf6f556) | May 04, 2022 |
| ASRock        | Z77 Pro3                    | Desktop     | [050aee0a5f](https://linux-hardware.org/?probe=050aee0a5f) | May 03, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [0a6358dc13](https://linux-hardware.org/?probe=0a6358dc13) | May 03, 2022 |
| MSI           | MS-7053                     | Desktop     | [6de132b805](https://linux-hardware.org/?probe=6de132b805) | May 02, 2022 |
| Sony          | VGN-FZ31Z                   | Notebook    | [ebe91972ba](https://linux-hardware.org/?probe=ebe91972ba) | May 01, 2022 |
| HP            | ENVY Laptop 15-ep0xxx       | Notebook    | [96dbfb494e](https://linux-hardware.org/?probe=96dbfb494e) | Apr 29, 2022 |
| ASUSTek       | X540SAA                     | Notebook    | [6c8e397ca3](https://linux-hardware.org/?probe=6c8e397ca3) | Apr 29, 2022 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [519ed87066](https://linux-hardware.org/?probe=519ed87066) | Apr 29, 2022 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [c46a1d595b](https://linux-hardware.org/?probe=c46a1d595b) | Apr 29, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [910267bbd5](https://linux-hardware.org/?probe=910267bbd5) | Apr 28, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [22dd67107b](https://linux-hardware.org/?probe=22dd67107b) | Apr 28, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [91c7a6b5a0](https://linux-hardware.org/?probe=91c7a6b5a0) | Apr 27, 2022 |
| Lenovo        | ThinkPad L490 20Q5002GPG    | Notebook    | [9e591226b7](https://linux-hardware.org/?probe=9e591226b7) | Apr 26, 2022 |
| Lenovo        | ThinkPad X201 Tablet 083... | Notebook    | [e3ece9d899](https://linux-hardware.org/?probe=e3ece9d899) | Apr 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [5c309ec35d](https://linux-hardware.org/?probe=5c309ec35d) | Apr 26, 2022 |
| Lenovo        | ThinkPad X201 Tablet 083... | Notebook    | [8e7b2c79a0](https://linux-hardware.org/?probe=8e7b2c79a0) | Apr 25, 2022 |
| ASUSTek       | X540LJ                      | Notebook    | [8e0c841b78](https://linux-hardware.org/?probe=8e0c841b78) | Apr 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [710ddc650e](https://linux-hardware.org/?probe=710ddc650e) | Apr 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [7fc8d31b49](https://linux-hardware.org/?probe=7fc8d31b49) | Apr 24, 2022 |
| ASUSTek       | 1215N                       | Notebook    | [93ad513620](https://linux-hardware.org/?probe=93ad513620) | Apr 24, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [6162231453](https://linux-hardware.org/?probe=6162231453) | Apr 23, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [9146df4426](https://linux-hardware.org/?probe=9146df4426) | Apr 23, 2022 |
| HP            | 8719                        | Desktop     | [7e0ae3d91f](https://linux-hardware.org/?probe=7e0ae3d91f) | Apr 22, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [2641eee3f1](https://linux-hardware.org/?probe=2641eee3f1) | Apr 21, 2022 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [a21dad9ee4](https://linux-hardware.org/?probe=a21dad9ee4) | Apr 20, 2022 |
| ASUSTek       | X102BA                      | Notebook    | [00fbb5cbff](https://linux-hardware.org/?probe=00fbb5cbff) | Apr 20, 2022 |
| Lenovo        | ThinkPad L390 20NR001EPG    | Notebook    | [d83b89a414](https://linux-hardware.org/?probe=d83b89a414) | Apr 20, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [278c76b54f](https://linux-hardware.org/?probe=278c76b54f) | Apr 18, 2022 |
| HP            | Pavilion g6                 | Notebook    | [0c4c081e71](https://linux-hardware.org/?probe=0c4c081e71) | Apr 17, 2022 |
| Toshiba       | Satellite L775-151          | Notebook    | [957020b872](https://linux-hardware.org/?probe=957020b872) | Apr 16, 2022 |
| Toshiba       | Satellite L775-151          | Notebook    | [706f14a3e6](https://linux-hardware.org/?probe=706f14a3e6) | Apr 16, 2022 |
| Teclast       | F6 Plus                     | Notebook    | [a9407bd227](https://linux-hardware.org/?probe=a9407bd227) | Apr 16, 2022 |
| Teclast       | F6 Plus                     | Notebook    | [7403ce7189](https://linux-hardware.org/?probe=7403ce7189) | Apr 16, 2022 |
| Toshiba       | Satellite L300              | Notebook    | [242592fee5](https://linux-hardware.org/?probe=242592fee5) | Apr 15, 2022 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | Notebook    | [7436528d4f](https://linux-hardware.org/?probe=7436528d4f) | Apr 14, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [5f49d4d7d8](https://linux-hardware.org/?probe=5f49d4d7d8) | Apr 14, 2022 |
| Toshiba       | Satellite P70-B             | Notebook    | [6c01bb2cc3](https://linux-hardware.org/?probe=6c01bb2cc3) | Apr 13, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [bc22c713a7](https://linux-hardware.org/?probe=bc22c713a7) | Apr 13, 2022 |
| HP            | ZBook Power G7 Mobile Wo... | Notebook    | [fba984b898](https://linux-hardware.org/?probe=fba984b898) | Apr 11, 2022 |
| Positivo      | H14BU08                     | Notebook    | [11014257c0](https://linux-hardware.org/?probe=11014257c0) | Apr 11, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [4ca643452e](https://linux-hardware.org/?probe=4ca643452e) | Apr 10, 2022 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [db8350499d](https://linux-hardware.org/?probe=db8350499d) | Apr 09, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [8adf631258](https://linux-hardware.org/?probe=8adf631258) | Apr 08, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [00c3a80eb1](https://linux-hardware.org/?probe=00c3a80eb1) | Apr 07, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [ec5daa2c06](https://linux-hardware.org/?probe=ec5daa2c06) | Apr 06, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [191c569aa7](https://linux-hardware.org/?probe=191c569aa7) | Apr 05, 2022 |
| ASUSTek       | T100TA                      | Notebook    | [dbfc15621f](https://linux-hardware.org/?probe=dbfc15621f) | Apr 04, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [9493efcabe](https://linux-hardware.org/?probe=9493efcabe) | Apr 03, 2022 |
| ASUSTek       | X555LJ                      | Notebook    | [f9bbaea819](https://linux-hardware.org/?probe=f9bbaea819) | Apr 01, 2022 |
| ASUSTek       | X555LJ                      | Notebook    | [944f40aa28](https://linux-hardware.org/?probe=944f40aa28) | Apr 01, 2022 |
| TUXEDO        | InfinityBook S 14 Gen6      | Notebook    | [847b8f0788](https://linux-hardware.org/?probe=847b8f0788) | Apr 01, 2022 |
| HP            | Pavilion g6                 | Notebook    | [5dce001675](https://linux-hardware.org/?probe=5dce001675) | Mar 31, 2022 |
| Intel         | NUC7i3BNB J22859-309        | Mini pc     | [740b44dda7](https://linux-hardware.org/?probe=740b44dda7) | Mar 30, 2022 |
| MSI           | Modern 14 B11M              | Notebook    | [3cdc036c09](https://linux-hardware.org/?probe=3cdc036c09) | Mar 30, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [60a6bafd86](https://linux-hardware.org/?probe=60a6bafd86) | Mar 30, 2022 |
| Fujitsu       | LIFEBOOK S752               | Notebook    | [73c18f75a9](https://linux-hardware.org/?probe=73c18f75a9) | Mar 29, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [41870b3fdb](https://linux-hardware.org/?probe=41870b3fdb) | Mar 28, 2022 |
| ASUSTek       | T100TA                      | Notebook    | [fa6858ef16](https://linux-hardware.org/?probe=fa6858ef16) | Mar 28, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [fc92c7a9d2](https://linux-hardware.org/?probe=fc92c7a9d2) | Mar 28, 2022 |
| ASUSTek       | GL552VW                     | Notebook    | [7e8bfac4b7](https://linux-hardware.org/?probe=7e8bfac4b7) | Mar 27, 2022 |
| MSI           | GL65 Leopard 10SFK          | Notebook    | [96afe8ccf1](https://linux-hardware.org/?probe=96afe8ccf1) | Mar 25, 2022 |
| MSI           | Modern 14 B11M              | Notebook    | [a2921a6b4c](https://linux-hardware.org/?probe=a2921a6b4c) | Mar 25, 2022 |
| MSI           | Modern 14 B11M              | Notebook    | [ca5720c46b](https://linux-hardware.org/?probe=ca5720c46b) | Mar 25, 2022 |
| Toshiba       | Satellite P50-B-10V         | Notebook    | [1f6acfd782](https://linux-hardware.org/?probe=1f6acfd782) | Mar 24, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [f146cb600a](https://linux-hardware.org/?probe=f146cb600a) | Mar 24, 2022 |
| ASUSTek       | X510UNR                     | Notebook    | [ab3b8653a6](https://linux-hardware.org/?probe=ab3b8653a6) | Mar 23, 2022 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [90a8431fc2](https://linux-hardware.org/?probe=90a8431fc2) | Mar 22, 2022 |
| Apple         | MacBookAir3,1               | Notebook    | [482fbd3456](https://linux-hardware.org/?probe=482fbd3456) | Mar 21, 2022 |
| HP            | ProBook 640 G2              | Notebook    | [17ceb0fd9f](https://linux-hardware.org/?probe=17ceb0fd9f) | Mar 19, 2022 |
| ASUSTek       | X541UV                      | Notebook    | [a23f80c36b](https://linux-hardware.org/?probe=a23f80c36b) | Mar 19, 2022 |
| MSI           | Stealth GS66 12UGS          | Notebook    | [882be4cd35](https://linux-hardware.org/?probe=882be4cd35) | Mar 19, 2022 |
| HP            | ProBook 640 G2              | Notebook    | [9024337e9f](https://linux-hardware.org/?probe=9024337e9f) | Mar 19, 2022 |
| Gigabyte      | A520M H                     | Desktop     | [46b8c80485](https://linux-hardware.org/?probe=46b8c80485) | Mar 17, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [36c1044633](https://linux-hardware.org/?probe=36c1044633) | Mar 16, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [5b345c55f7](https://linux-hardware.org/?probe=5b345c55f7) | Mar 16, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [90bbda2f8c](https://linux-hardware.org/?probe=90bbda2f8c) | Mar 16, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [1fea8c1b2b](https://linux-hardware.org/?probe=1fea8c1b2b) | Mar 16, 2022 |
| Lenovo        | ThinkPad L490 20Q5002GPG    | Notebook    | [fabbaeb1bb](https://linux-hardware.org/?probe=fabbaeb1bb) | Mar 16, 2022 |
| Gigabyte      | A520M H                     | Desktop     | [483e47645c](https://linux-hardware.org/?probe=483e47645c) | Mar 16, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [3aded823d8](https://linux-hardware.org/?probe=3aded823d8) | Mar 13, 2022 |
| ASUSTek       | ZenBook UX431FA             | Notebook    | [b3cbed05f5](https://linux-hardware.org/?probe=b3cbed05f5) | Mar 10, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [8469a31d58](https://linux-hardware.org/?probe=8469a31d58) | Mar 10, 2022 |
| Sony          | VGN-FZ31Z                   | Notebook    | [17e3cb9771](https://linux-hardware.org/?probe=17e3cb9771) | Mar 10, 2022 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [8a97b4f2d3](https://linux-hardware.org/?probe=8a97b4f2d3) | Mar 09, 2022 |
| ASUSTek       | X541UV                      | Notebook    | [aef8901d13](https://linux-hardware.org/?probe=aef8901d13) | Mar 08, 2022 |
| ASUSTek       | X541UV                      | Notebook    | [6bed69bcdb](https://linux-hardware.org/?probe=6bed69bcdb) | Mar 08, 2022 |
| HP            | 0A54h                       | Desktop     | [2dfc948414](https://linux-hardware.org/?probe=2dfc948414) | Mar 08, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [8a4f961472](https://linux-hardware.org/?probe=8a4f961472) | Mar 08, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [4d33fc28da](https://linux-hardware.org/?probe=4d33fc28da) | Mar 08, 2022 |
| Acer          | Aspire E5-551G              | Notebook    | [18bc15734f](https://linux-hardware.org/?probe=18bc15734f) | Mar 07, 2022 |
| ASUSTek       | X541UV                      | Notebook    | [a90d26bc2d](https://linux-hardware.org/?probe=a90d26bc2d) | Mar 06, 2022 |
| Lenovo        | ThinkPad W541 20EGS03100    | Notebook    | [f7b51cf262](https://linux-hardware.org/?probe=f7b51cf262) | Mar 05, 2022 |
| ASUSTek       | X541UV                      | Notebook    | [b5678eb9d3](https://linux-hardware.org/?probe=b5678eb9d3) | Mar 05, 2022 |
| Apple         | MacBookPro8,3               | Notebook    | [87a5df55b8](https://linux-hardware.org/?probe=87a5df55b8) | Mar 04, 2022 |
| ASUSTek       | T100TA                      | Notebook    | [485c2b3aa7](https://linux-hardware.org/?probe=485c2b3aa7) | Mar 04, 2022 |
| Gigabyte      | G31M-S2L                    | Desktop     | [dd40993d97](https://linux-hardware.org/?probe=dd40993d97) | Mar 03, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [c1b8c2903d](https://linux-hardware.org/?probe=c1b8c2903d) | Mar 02, 2022 |
| Acer          | Aspire A515-54G             | Notebook    | [67241eca45](https://linux-hardware.org/?probe=67241eca45) | Mar 02, 2022 |
| Acer          | Aspire A515-54G             | Notebook    | [06455796f9](https://linux-hardware.org/?probe=06455796f9) | Mar 01, 2022 |
| Sony          | VGN-FZ31Z                   | Notebook    | [01b50ec980](https://linux-hardware.org/?probe=01b50ec980) | Mar 01, 2022 |
| HP            | 3396                        | Desktop     | [f952a8f044](https://linux-hardware.org/?probe=f952a8f044) | Mar 01, 2022 |
| MSI           | B85M-E45                    | Desktop     | [42fba9424e](https://linux-hardware.org/?probe=42fba9424e) | Feb 27, 2022 |
| Minix         | NEO Z83-4 V1.1              | Desktop     | [8aa7469422](https://linux-hardware.org/?probe=8aa7469422) | Feb 27, 2022 |
| Sony          | VGN-FZ31Z                   | Notebook    | [1d156021e3](https://linux-hardware.org/?probe=1d156021e3) | Feb 26, 2022 |
| Sony          | VGN-FZ31Z                   | Notebook    | [b223305dc1](https://linux-hardware.org/?probe=b223305dc1) | Feb 26, 2022 |
| OBSIDIAN-P... | N13_N140ZU                  | Notebook    | [9f2fdbfce5](https://linux-hardware.org/?probe=9f2fdbfce5) | Feb 25, 2022 |
| Biostar       | H81MHV3                     | Desktop     | [3fd07aef04](https://linux-hardware.org/?probe=3fd07aef04) | Feb 25, 2022 |
| Positivo      | H14BU08                     | Notebook    | [b3cb8e0d72](https://linux-hardware.org/?probe=b3cb8e0d72) | Feb 25, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [e72b93aadf](https://linux-hardware.org/?probe=e72b93aadf) | Feb 24, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [e9d9cfb3e9](https://linux-hardware.org/?probe=e9d9cfb3e9) | Feb 24, 2022 |
| Samsung       | QX310/QX410/QX510/SF310/... | Notebook    | [20b0cf0db9](https://linux-hardware.org/?probe=20b0cf0db9) | Feb 24, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [48d36e9bae](https://linux-hardware.org/?probe=48d36e9bae) | Feb 24, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [60adc82fb8](https://linux-hardware.org/?probe=60adc82fb8) | Feb 23, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [cf3e28fb31](https://linux-hardware.org/?probe=cf3e28fb31) | Feb 23, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [677ffe54b5](https://linux-hardware.org/?probe=677ffe54b5) | Feb 23, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [eacd6c646c](https://linux-hardware.org/?probe=eacd6c646c) | Feb 22, 2022 |
| IBM           | 819046G                     | Desktop     | [54b0798b76](https://linux-hardware.org/?probe=54b0798b76) | Feb 22, 2022 |
| ASUSTek       | P5VDC-X                     | Desktop     | [40943e3ee0](https://linux-hardware.org/?probe=40943e3ee0) | Feb 22, 2022 |
| SLIMBOOK      | TITAN                       | Notebook    | [2a35f863c2](https://linux-hardware.org/?probe=2a35f863c2) | Feb 21, 2022 |
| Lenovo        | ThinkPad T540p 20BFS23T0... | Notebook    | [c49acb0edf](https://linux-hardware.org/?probe=c49acb0edf) | Feb 21, 2022 |
| Lenovo        | ThinkPad T540p 20BFS23T0... | Notebook    | [6f13abc9eb](https://linux-hardware.org/?probe=6f13abc9eb) | Feb 21, 2022 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [013349e12a](https://linux-hardware.org/?probe=013349e12a) | Feb 19, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [f114f6ea54](https://linux-hardware.org/?probe=f114f6ea54) | Feb 18, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [b6f947ed63](https://linux-hardware.org/?probe=b6f947ed63) | Feb 18, 2022 |
| HP            | 83F3                        | Desktop     | [9421f4385a](https://linux-hardware.org/?probe=9421f4385a) | Feb 18, 2022 |
| Dell          | Latitude E6440              | Notebook    | [1d4bac917c](https://linux-hardware.org/?probe=1d4bac917c) | Feb 18, 2022 |
| ASUSTek       | T100TA                      | Notebook    | [9f0a454d8b](https://linux-hardware.org/?probe=9f0a454d8b) | Feb 18, 2022 |
| ASUSTek       | ROG STRIX B560-F GAMING ... | Desktop     | [f7ee45924c](https://linux-hardware.org/?probe=f7ee45924c) | Feb 17, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [b39fbbaec6](https://linux-hardware.org/?probe=b39fbbaec6) | Feb 16, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [8f1ce82db7](https://linux-hardware.org/?probe=8f1ce82db7) | Feb 15, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [8441ab9eb2](https://linux-hardware.org/?probe=8441ab9eb2) | Feb 15, 2022 |
| ASUSTek       | X555LJ                      | Notebook    | [c2f63ae6d7](https://linux-hardware.org/?probe=c2f63ae6d7) | Feb 14, 2022 |
| Acer          | Aspire 5715Z                | Notebook    | [cdd4414bbd](https://linux-hardware.org/?probe=cdd4414bbd) | Feb 13, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [aeec085062](https://linux-hardware.org/?probe=aeec085062) | Feb 13, 2022 |
| ASUSTek       | X541UV                      | Notebook    | [fb81da9fa5](https://linux-hardware.org/?probe=fb81da9fa5) | Feb 13, 2022 |
| MSI           | MS-7053                     | Desktop     | [2ee97bf0a8](https://linux-hardware.org/?probe=2ee97bf0a8) | Feb 13, 2022 |
| Dell          | Precision 3561              | Notebook    | [23c3392c57](https://linux-hardware.org/?probe=23c3392c57) | Feb 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [6c64279dbc](https://linux-hardware.org/?probe=6c64279dbc) | Feb 12, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [0dd30d1e7e](https://linux-hardware.org/?probe=0dd30d1e7e) | Feb 11, 2022 |
| Lenovo        | ThinkPad W510 4389BB4       | Notebook    | [ecaa14289f](https://linux-hardware.org/?probe=ecaa14289f) | Feb 09, 2022 |
| MSI           | H61M-P20                    | Desktop     | [81b315b229](https://linux-hardware.org/?probe=81b315b229) | Feb 09, 2022 |
| HP            | Compaq Presario CQ60        | Notebook    | [f5d9f92aad](https://linux-hardware.org/?probe=f5d9f92aad) | Feb 09, 2022 |
| HP            | 8103 A01                    | Mini pc     | [60924b9fd9](https://linux-hardware.org/?probe=60924b9fd9) | Feb 08, 2022 |
| Lenovo        | ThinkPad P50 20EN0005PG     | Notebook    | [0043180375](https://linux-hardware.org/?probe=0043180375) | Feb 07, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [70122a3cd0](https://linux-hardware.org/?probe=70122a3cd0) | Feb 07, 2022 |
| MSI           | B85M-E45                    | Desktop     | [3653d29a0a](https://linux-hardware.org/?probe=3653d29a0a) | Feb 07, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [6bee100b0a](https://linux-hardware.org/?probe=6bee100b0a) | Feb 06, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [a554a842f7](https://linux-hardware.org/?probe=a554a842f7) | Feb 05, 2022 |
| Dell          | Latitude D630               | Notebook    | [66fe60e209](https://linux-hardware.org/?probe=66fe60e209) | Feb 04, 2022 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [722271e199](https://linux-hardware.org/?probe=722271e199) | Feb 04, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [62cf8cdd3c](https://linux-hardware.org/?probe=62cf8cdd3c) | Feb 02, 2022 |
| Foxconn       | H67M-S/H67M-V/H67           | Desktop     | [a3f3367577](https://linux-hardware.org/?probe=a3f3367577) | Feb 02, 2022 |
| Dell          | Latitude D630               | Notebook    | [c4b7202805](https://linux-hardware.org/?probe=c4b7202805) | Feb 01, 2022 |
| Sony          | VGN-FZ31Z                   | Notebook    | [c3e03d2551](https://linux-hardware.org/?probe=c3e03d2551) | Feb 01, 2022 |
| ASUSTek       | P5K3L-ASUS-S1-P5G35         | Desktop     | [f9e7838b90](https://linux-hardware.org/?probe=f9e7838b90) | Jan 31, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [e0c36731ca](https://linux-hardware.org/?probe=e0c36731ca) | Jan 31, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [b4f3d4f1ee](https://linux-hardware.org/?probe=b4f3d4f1ee) | Jan 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [77d230b476](https://linux-hardware.org/?probe=77d230b476) | Jan 29, 2022 |
| Acer          | Aspire E5-551G              | Notebook    | [435c894ed4](https://linux-hardware.org/?probe=435c894ed4) | Jan 29, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [8609aaadb3](https://linux-hardware.org/?probe=8609aaadb3) | Jan 27, 2022 |
| ASUSTek       | N56VZ                       | Notebook    | [6f1b0cf9e0](https://linux-hardware.org/?probe=6f1b0cf9e0) | Jan 26, 2022 |
| Foxconn       | nT-i1000 Series PCB         | Desktop     | [72374dc22c](https://linux-hardware.org/?probe=72374dc22c) | Jan 26, 2022 |
| Foxconn       | nT-i1000 Series PCB         | Desktop     | [78cdf0490a](https://linux-hardware.org/?probe=78cdf0490a) | Jan 26, 2022 |
| Apple         | MacBookAir1,1               | Notebook    | [dfbdc8f20b](https://linux-hardware.org/?probe=dfbdc8f20b) | Jan 25, 2022 |
| ASUSTek       | ZenBook UX431FA             | Notebook    | [519a7a72ab](https://linux-hardware.org/?probe=519a7a72ab) | Jan 24, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [b3aec22953](https://linux-hardware.org/?probe=b3aec22953) | Jan 24, 2022 |
| Gigabyte      | H110M-Gaming3-CF            | Desktop     | [5b23faaf76](https://linux-hardware.org/?probe=5b23faaf76) | Jan 22, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [90249388ff](https://linux-hardware.org/?probe=90249388ff) | Jan 22, 2022 |
| Gigabyte      | H110M-Gaming3-CF            | Desktop     | [3791490565](https://linux-hardware.org/?probe=3791490565) | Jan 22, 2022 |
| Toshiba       | Satellite A200              | Notebook    | [9086ec49b6](https://linux-hardware.org/?probe=9086ec49b6) | Jan 21, 2022 |
| Lenovo        | 313C SDK0J40697 WIN 3305... | Desktop     | [6cad862612](https://linux-hardware.org/?probe=6cad862612) | Jan 21, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [6fd36db1e0](https://linux-hardware.org/?probe=6fd36db1e0) | Jan 18, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [6f87d7372b](https://linux-hardware.org/?probe=6f87d7372b) | Jan 18, 2022 |
| Sony          | VGN-FZ31Z                   | Notebook    | [c7f9080e23](https://linux-hardware.org/?probe=c7f9080e23) | Jan 18, 2022 |
| Acer          | Aspire ES1-512              | Notebook    | [ca83027c67](https://linux-hardware.org/?probe=ca83027c67) | Jan 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [b27ed63a97](https://linux-hardware.org/?probe=b27ed63a97) | Jan 16, 2022 |
| MSI           | MS-7053                     | Desktop     | [8844db2984](https://linux-hardware.org/?probe=8844db2984) | Jan 13, 2022 |
| ASUSTek       | P5K PRO                     | Desktop     | [9338817523](https://linux-hardware.org/?probe=9338817523) | Jan 13, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [a4b1346944](https://linux-hardware.org/?probe=a4b1346944) | Jan 13, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [a8ff8d111b](https://linux-hardware.org/?probe=a8ff8d111b) | Jan 11, 2022 |
| Lenovo        | ThinkPad E15 20RD0015PG     | Notebook    | [008fd40914](https://linux-hardware.org/?probe=008fd40914) | Jan 11, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [5ba5bfc822](https://linux-hardware.org/?probe=5ba5bfc822) | Jan 11, 2022 |
| ASUSTek       | V-P7H55E                    | Desktop     | [7fc2d44a4a](https://linux-hardware.org/?probe=7fc2d44a4a) | Jan 11, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [409de37ae4](https://linux-hardware.org/?probe=409de37ae4) | Jan 09, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [468890e10d](https://linux-hardware.org/?probe=468890e10d) | Jan 08, 2022 |
| Sony          | VGN-FZ31Z                   | Notebook    | [7587e6c439](https://linux-hardware.org/?probe=7587e6c439) | Jan 08, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [a3194a0ed3](https://linux-hardware.org/?probe=a3194a0ed3) | Jan 06, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [a140e77bfe](https://linux-hardware.org/?probe=a140e77bfe) | Jan 05, 2022 |
| Toshiba       | Satellite L50D-B            | Notebook    | [e253741d9f](https://linux-hardware.org/?probe=e253741d9f) | Jan 05, 2022 |
| HP            | ProBook 4530s               | Notebook    | [c68e298c14](https://linux-hardware.org/?probe=c68e298c14) | Jan 04, 2022 |
| Lenovo        | ThinkPad L530 24791S8       | Notebook    | [030611ecba](https://linux-hardware.org/?probe=030611ecba) | Jan 04, 2022 |
| MSI           | Modern 14 A10RB             | Notebook    | [83285ade95](https://linux-hardware.org/?probe=83285ade95) | Jan 02, 2022 |
| MSI           | Modern 14 A10RB             | Notebook    | [602fe88681](https://linux-hardware.org/?probe=602fe88681) | Jan 02, 2022 |
| Timi          | TM1701                      | Notebook    | [594f40016d](https://linux-hardware.org/?probe=594f40016d) | Jan 02, 2022 |
| ASUSTek       | X542URR                     | Notebook    | [8af11eb0f1](https://linux-hardware.org/?probe=8af11eb0f1) | Jan 02, 2022 |
| Gigabyte      | P41T-D3P                    | Desktop     | [1c94714d99](https://linux-hardware.org/?probe=1c94714d99) | Jan 01, 2022 |
| Google        | Sion                        | Desktop     | [08215c86b6](https://linux-hardware.org/?probe=08215c86b6) | Dec 31, 2021 |
| Dell          | Latitude D420               | Notebook    | [3caac63d5f](https://linux-hardware.org/?probe=3caac63d5f) | Dec 31, 2021 |
| Sony          | VGN-FZ31Z                   | Notebook    | [38b3f4d971](https://linux-hardware.org/?probe=38b3f4d971) | Dec 30, 2021 |
| Sony          | VGN-FZ31Z                   | Notebook    | [d1a2146c05](https://linux-hardware.org/?probe=d1a2146c05) | Dec 29, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [4dfe6a5b8c](https://linux-hardware.org/?probe=4dfe6a5b8c) | Dec 29, 2021 |
| ASUSTek       | A_F_K31AN                   | Desktop     | [4bd56c7243](https://linux-hardware.org/?probe=4bd56c7243) | Dec 29, 2021 |
| RKM           | Cherry Trail CR             | Desktop     | [907cacf8cc](https://linux-hardware.org/?probe=907cacf8cc) | Dec 29, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [6f891ac715](https://linux-hardware.org/?probe=6f891ac715) | Dec 29, 2021 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [d988f944f8](https://linux-hardware.org/?probe=d988f944f8) | Dec 28, 2021 |
| Huanan        | X79-8D VAA31                | Desktop     | [79be6da608](https://linux-hardware.org/?probe=79be6da608) | Dec 26, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [1daccedded](https://linux-hardware.org/?probe=1daccedded) | Dec 26, 2021 |
| HP            | 1998                        | Desktop     | [fffadbe1cf](https://linux-hardware.org/?probe=fffadbe1cf) | Dec 25, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [99bea5df6c](https://linux-hardware.org/?probe=99bea5df6c) | Dec 25, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [fe1f7f03e2](https://linux-hardware.org/?probe=fe1f7f03e2) | Dec 21, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X3C... | Notebook    | [40282bb1fd](https://linux-hardware.org/?probe=40282bb1fd) | Dec 21, 2021 |
| Acer          | Aspire ES1-520              | Notebook    | [7a43d12de6](https://linux-hardware.org/?probe=7a43d12de6) | Dec 20, 2021 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | Desktop     | [855061aa1a](https://linux-hardware.org/?probe=855061aa1a) | Dec 18, 2021 |
| MSI           | MS-7053                     | Desktop     | [3e9330e811](https://linux-hardware.org/?probe=3e9330e811) | Dec 18, 2021 |
| MSI           | MS-7053                     | Desktop     | [b32db3cd18](https://linux-hardware.org/?probe=b32db3cd18) | Dec 18, 2021 |
| ASUSTek       | T100HAN                     | Notebook    | [ad0dc6b737](https://linux-hardware.org/?probe=ad0dc6b737) | Dec 17, 2021 |
| ASUSTek       | T100HAN                     | Notebook    | [67b8998643](https://linux-hardware.org/?probe=67b8998643) | Dec 17, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [f9a4ac885d](https://linux-hardware.org/?probe=f9a4ac885d) | Dec 17, 2021 |
| MSI           | Alpha 15 A4DEK              | Notebook    | [0ecac9e450](https://linux-hardware.org/?probe=0ecac9e450) | Dec 16, 2021 |
| Toshiba       | QOSMIO X770                 | Notebook    | [c8c9ab4cf8](https://linux-hardware.org/?probe=c8c9ab4cf8) | Dec 16, 2021 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [830b8475ac](https://linux-hardware.org/?probe=830b8475ac) | Dec 15, 2021 |
| MSI           | Alpha 15 A4DEK              | Notebook    | [4b7a0b485e](https://linux-hardware.org/?probe=4b7a0b485e) | Dec 15, 2021 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [6248556dd7](https://linux-hardware.org/?probe=6248556dd7) | Dec 14, 2021 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [93957ddac1](https://linux-hardware.org/?probe=93957ddac1) | Dec 13, 2021 |
| Sony          | VGN-SZ2HP_B                 | Notebook    | [a5d51adfab](https://linux-hardware.org/?probe=a5d51adfab) | Dec 13, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [1812d44a36](https://linux-hardware.org/?probe=1812d44a36) | Dec 12, 2021 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [d1e767dfde](https://linux-hardware.org/?probe=d1e767dfde) | Dec 11, 2021 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [3faa0a2aad](https://linux-hardware.org/?probe=3faa0a2aad) | Dec 11, 2021 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [8b03acc524](https://linux-hardware.org/?probe=8b03acc524) | Dec 11, 2021 |
| Fujitsu       | LIFEBOOK U7411              | Notebook    | [65bc5c1c5b](https://linux-hardware.org/?probe=65bc5c1c5b) | Dec 11, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [11fb7ea1d7](https://linux-hardware.org/?probe=11fb7ea1d7) | Dec 08, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [23579d8b3a](https://linux-hardware.org/?probe=23579d8b3a) | Dec 08, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [66796a4303](https://linux-hardware.org/?probe=66796a4303) | Dec 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [1d9d5bfe12](https://linux-hardware.org/?probe=1d9d5bfe12) | Dec 05, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [aa4d4e3b08](https://linux-hardware.org/?probe=aa4d4e3b08) | Dec 04, 2021 |
| Lenovo        | ThinkPad R61 89337HG        | Notebook    | [670c02b990](https://linux-hardware.org/?probe=670c02b990) | Dec 02, 2021 |
| Fujitsu       | D3521-A1 S26361-D3521-A1... | Server      | [cded98e996](https://linux-hardware.org/?probe=cded98e996) | Dec 02, 2021 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [c68a7d50dc](https://linux-hardware.org/?probe=c68a7d50dc) | Dec 02, 2021 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [49055ba417](https://linux-hardware.org/?probe=49055ba417) | Dec 01, 2021 |
| Sony          | VGN-FZ31Z                   | Notebook    | [8e4401834b](https://linux-hardware.org/?probe=8e4401834b) | Dec 01, 2021 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [40a204e5f1](https://linux-hardware.org/?probe=40a204e5f1) | Nov 30, 2021 |
| Packard Be... | EasyNote_MX37-V-101PT       | Notebook    | [6f8e7042c4](https://linux-hardware.org/?probe=6f8e7042c4) | Nov 30, 2021 |
| Acer          | Aspire A315-57G             | Notebook    | [cfc036a421](https://linux-hardware.org/?probe=cfc036a421) | Nov 29, 2021 |
| HP            | OMEN by Laptop              | Notebook    | [4dec490a3f](https://linux-hardware.org/?probe=4dec490a3f) | Nov 29, 2021 |
| Acer          | Aspire E5-521               | Notebook    | [48d70742bb](https://linux-hardware.org/?probe=48d70742bb) | Nov 28, 2021 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | Notebook    | [1a717e5780](https://linux-hardware.org/?probe=1a717e5780) | Nov 28, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [19fc23d020](https://linux-hardware.org/?probe=19fc23d020) | Nov 27, 2021 |
| Pegatron      | Benicia                     | Desktop     | [d50daedc5d](https://linux-hardware.org/?probe=d50daedc5d) | Nov 26, 2021 |
| Microsoft     | Surface Pro 3               | Tablet      | [6b926197c9](https://linux-hardware.org/?probe=6b926197c9) | Nov 24, 2021 |
| HP            | Pavilion 15                 | Notebook    | [0f1442bb2c](https://linux-hardware.org/?probe=0f1442bb2c) | Nov 22, 2021 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [22f1f5326e](https://linux-hardware.org/?probe=22f1f5326e) | Nov 21, 2021 |
| HP            | 15 TS                       | Notebook    | [50a260e4dc](https://linux-hardware.org/?probe=50a260e4dc) | Nov 21, 2021 |
| Clevo         | M7X0SU                      | Notebook    | [a9638079c6](https://linux-hardware.org/?probe=a9638079c6) | Nov 20, 2021 |
| Microsoft     | Surface Pro 3               | Tablet      | [517d6787c9](https://linux-hardware.org/?probe=517d6787c9) | Nov 20, 2021 |
| Biostar       | FX9830M                     | Desktop     | [f845fe2694](https://linux-hardware.org/?probe=f845fe2694) | Nov 19, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [32a54aa260](https://linux-hardware.org/?probe=32a54aa260) | Nov 19, 2021 |
| ASUSTek       | UX303LAB                    | Notebook    | [21a3bdf255](https://linux-hardware.org/?probe=21a3bdf255) | Nov 19, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [8fc5db0cd9](https://linux-hardware.org/?probe=8fc5db0cd9) | Nov 17, 2021 |
| Sony          | VGN-FZ31Z                   | Notebook    | [2c4fd499c5](https://linux-hardware.org/?probe=2c4fd499c5) | Nov 17, 2021 |
| HP            | Pavilion dv6                | Notebook    | [3f54f48e23](https://linux-hardware.org/?probe=3f54f48e23) | Nov 17, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [5f28060674](https://linux-hardware.org/?probe=5f28060674) | Nov 16, 2021 |
| ASUSTek       | X540YA                      | Notebook    | [72e7bebf84](https://linux-hardware.org/?probe=72e7bebf84) | Nov 16, 2021 |
| ASUSTek       | X540YA                      | Notebook    | [39d8ea222a](https://linux-hardware.org/?probe=39d8ea222a) | Nov 16, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [f30f49d634](https://linux-hardware.org/?probe=f30f49d634) | Nov 16, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [fccd73da9d](https://linux-hardware.org/?probe=fccd73da9d) | Nov 12, 2021 |
| HUAWEI        | WRT-WX9                     | Notebook    | [6c0ee3ae74](https://linux-hardware.org/?probe=6c0ee3ae74) | Nov 12, 2021 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [be61c60b41](https://linux-hardware.org/?probe=be61c60b41) | Nov 12, 2021 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [9fa65491aa](https://linux-hardware.org/?probe=9fa65491aa) | Nov 12, 2021 |
| ASUSTek       | X202EV                      | Notebook    | [ff0732f245](https://linux-hardware.org/?probe=ff0732f245) | Nov 11, 2021 |
| Sony          | VGN-FZ31Z                   | Notebook    | [fe8ba3f801](https://linux-hardware.org/?probe=fe8ba3f801) | Nov 11, 2021 |
| ASUSTek       | T102HA                      | Notebook    | [d648620b1a](https://linux-hardware.org/?probe=d648620b1a) | Nov 10, 2021 |
| Lenovo        | ThinkPad T420 4177Q5U       | Notebook    | [02ce053478](https://linux-hardware.org/?probe=02ce053478) | Nov 10, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [c13d42cb63](https://linux-hardware.org/?probe=c13d42cb63) | Nov 10, 2021 |
| HP            | ProLiant DL380 Gen9         | Server      | [7d9fdf4b73](https://linux-hardware.org/?probe=7d9fdf4b73) | Nov 10, 2021 |
| HP            | ProLiant DL380 Gen9         | Server      | [fd25e09529](https://linux-hardware.org/?probe=fd25e09529) | Nov 10, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [8403f5c97f](https://linux-hardware.org/?probe=8403f5c97f) | Nov 09, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [5dbef9a6a7](https://linux-hardware.org/?probe=5dbef9a6a7) | Nov 09, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [a2d1a17ff1](https://linux-hardware.org/?probe=a2d1a17ff1) | Nov 09, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d4a2a86c38](https://linux-hardware.org/?probe=d4a2a86c38) | Nov 09, 2021 |
| Dell          | 0HD5W2 A00                  | Desktop     | [d4c15ae33a](https://linux-hardware.org/?probe=d4c15ae33a) | Nov 08, 2021 |
| Minix         | NEO Z83-4 V1.1              | Desktop     | [c7b52e35cf](https://linux-hardware.org/?probe=c7b52e35cf) | Nov 08, 2021 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [a0d13572a5](https://linux-hardware.org/?probe=a0d13572a5) | Nov 06, 2021 |
| HP            | G62                         | Notebook    | [a4a0360f3a](https://linux-hardware.org/?probe=a4a0360f3a) | Nov 06, 2021 |
| HP            | G62                         | Notebook    | [cd87bfa19b](https://linux-hardware.org/?probe=cd87bfa19b) | Nov 06, 2021 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [87daccdc88](https://linux-hardware.org/?probe=87daccdc88) | Nov 05, 2021 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [72e74c86fb](https://linux-hardware.org/?probe=72e74c86fb) | Nov 04, 2021 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [bbb4e58192](https://linux-hardware.org/?probe=bbb4e58192) | Nov 04, 2021 |
| ASUSTek       | P5LD2-SE                    | Desktop     | [4f817c0167](https://linux-hardware.org/?probe=4f817c0167) | Nov 03, 2021 |
| HP            | OMEN by Laptop              | Notebook    | [0b933dd493](https://linux-hardware.org/?probe=0b933dd493) | Nov 03, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [c22b81abd4](https://linux-hardware.org/?probe=c22b81abd4) | Nov 02, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [b643635a41](https://linux-hardware.org/?probe=b643635a41) | Nov 02, 2021 |
| Sony          | VPCYB1S1E                   | Notebook    | [bbe04676c1](https://linux-hardware.org/?probe=bbe04676c1) | Nov 02, 2021 |
| Sony          | VPCYB1S1E                   | Notebook    | [09eba8bb5f](https://linux-hardware.org/?probe=09eba8bb5f) | Nov 02, 2021 |
| Standard      | Unknown                     | Notebook    | [3cccd4bf9f](https://linux-hardware.org/?probe=3cccd4bf9f) | Nov 02, 2021 |
| HP            | ProBook 445 G7              | Notebook    | [ca8418c85b](https://linux-hardware.org/?probe=ca8418c85b) | Nov 02, 2021 |
| Acer          | Aspire E1-570G              | Notebook    | [9c6c7691c9](https://linux-hardware.org/?probe=9c6c7691c9) | Nov 02, 2021 |
| ASUSTek       | P5LD2-SE                    | Desktop     | [8ba60d9634](https://linux-hardware.org/?probe=8ba60d9634) | Nov 01, 2021 |
| Dell          | 0CRWCR A01                  | All in one  | [f92fa1f111](https://linux-hardware.org/?probe=f92fa1f111) | Oct 31, 2021 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [d1fc84613e](https://linux-hardware.org/?probe=d1fc84613e) | Oct 31, 2021 |
| Acer          | Aspire 4732Z                | Notebook    | [7095848f26](https://linux-hardware.org/?probe=7095848f26) | Oct 31, 2021 |
| Acer          | Aspire 4732Z                | Notebook    | [ce23f8d9f9](https://linux-hardware.org/?probe=ce23f8d9f9) | Oct 30, 2021 |
| MSI           | P55-CD53                    | Desktop     | [d342f4e0a4](https://linux-hardware.org/?probe=d342f4e0a4) | Oct 29, 2021 |
| Standard      | Unknown                     | Notebook    | [1bf7e2da2f](https://linux-hardware.org/?probe=1bf7e2da2f) | Oct 28, 2021 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [9276790a36](https://linux-hardware.org/?probe=9276790a36) | Oct 28, 2021 |
| Acer          | Aspire 5732Z                | Notebook    | [9d4f7a1a4b](https://linux-hardware.org/?probe=9d4f7a1a4b) | Oct 27, 2021 |
| ASUSTek       | X453MA                      | Notebook    | [4a70424b2f](https://linux-hardware.org/?probe=4a70424b2f) | Oct 27, 2021 |
| ASUSTek       | X540YA                      | Notebook    | [9b382500c5](https://linux-hardware.org/?probe=9b382500c5) | Oct 27, 2021 |
| ASUSTek       | A_F_K31AN                   | Desktop     | [ebd51400e3](https://linux-hardware.org/?probe=ebd51400e3) | Oct 25, 2021 |
| Dell          | Latitude E5400              | Notebook    | [7049bbe182](https://linux-hardware.org/?probe=7049bbe182) | Oct 24, 2021 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [4826046b43](https://linux-hardware.org/?probe=4826046b43) | Oct 24, 2021 |
| Toshiba       | Satellite T130              | Notebook    | [b3e2853259](https://linux-hardware.org/?probe=b3e2853259) | Oct 24, 2021 |
| Toshiba       | Satellite T130              | Notebook    | [5af2c96114](https://linux-hardware.org/?probe=5af2c96114) | Oct 24, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [7aac95cd60](https://linux-hardware.org/?probe=7aac95cd60) | Oct 23, 2021 |
| ASUSTek       | B85M-E                      | Desktop     | [7a6479dc2d](https://linux-hardware.org/?probe=7a6479dc2d) | Oct 23, 2021 |
| HP            | Notebook                    | Notebook    | [fb90bf9dc7](https://linux-hardware.org/?probe=fb90bf9dc7) | Oct 21, 2021 |
| ASUSTek       | X555LD                      | Notebook    | [eef17ea12f](https://linux-hardware.org/?probe=eef17ea12f) | Oct 20, 2021 |
| Lenovo        | ThinkPad T480 20L6S7PE06    | Notebook    | [28857899a2](https://linux-hardware.org/?probe=28857899a2) | Oct 20, 2021 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | Desktop     | [7313df4bd9](https://linux-hardware.org/?probe=7313df4bd9) | Oct 17, 2021 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [005e2591e8](https://linux-hardware.org/?probe=005e2591e8) | Oct 17, 2021 |
| HP            | Compaq Presario CQ60        | Notebook    | [0b02aa22d4](https://linux-hardware.org/?probe=0b02aa22d4) | Oct 17, 2021 |
| HP            | Pavilion x2 Detachable      | Notebook    | [c17c589af5](https://linux-hardware.org/?probe=c17c589af5) | Oct 17, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [c70057c643](https://linux-hardware.org/?probe=c70057c643) | Oct 16, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [6360789a1c](https://linux-hardware.org/?probe=6360789a1c) | Oct 14, 2021 |
| eMachines     | E520 V1.06                  | Notebook    | [97c667e3c0](https://linux-hardware.org/?probe=97c667e3c0) | Oct 14, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [b3f6912fdd](https://linux-hardware.org/?probe=b3f6912fdd) | Oct 11, 2021 |
| HP            | Pavilion g6                 | Notebook    | [5eba384acd](https://linux-hardware.org/?probe=5eba384acd) | Oct 11, 2021 |
| HP            | Notebook                    | Notebook    | [732cc33a53](https://linux-hardware.org/?probe=732cc33a53) | Oct 11, 2021 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [2ee0e02dca](https://linux-hardware.org/?probe=2ee0e02dca) | Oct 08, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [77a6cb9eba](https://linux-hardware.org/?probe=77a6cb9eba) | Oct 07, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [99c08de77b](https://linux-hardware.org/?probe=99c08de77b) | Oct 07, 2021 |
| ASUSTek       | H81M-A                      | Desktop     | [b73e4dc969](https://linux-hardware.org/?probe=b73e4dc969) | Oct 07, 2021 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [cc60b4cc30](https://linux-hardware.org/?probe=cc60b4cc30) | Oct 07, 2021 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [dae39c15c9](https://linux-hardware.org/?probe=dae39c15c9) | Oct 06, 2021 |
| HP            | G62                         | Notebook    | [6cbed79ca9](https://linux-hardware.org/?probe=6cbed79ca9) | Oct 05, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [426eac3a94](https://linux-hardware.org/?probe=426eac3a94) | Oct 05, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [843d9a14d4](https://linux-hardware.org/?probe=843d9a14d4) | Oct 05, 2021 |
| Toshiba       | Satellite A100              | Notebook    | [b1996e39c6](https://linux-hardware.org/?probe=b1996e39c6) | Oct 05, 2021 |
| Toshiba       | Satellite A100              | Notebook    | [47def5d058](https://linux-hardware.org/?probe=47def5d058) | Oct 05, 2021 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [eeae519a3e](https://linux-hardware.org/?probe=eeae519a3e) | Oct 04, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [a198e8517a](https://linux-hardware.org/?probe=a198e8517a) | Oct 01, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [96cf9ba56a](https://linux-hardware.org/?probe=96cf9ba56a) | Sep 30, 2021 |
| ASUSTek       | X453MA                      | Notebook    | [782dfc1a5f](https://linux-hardware.org/?probe=782dfc1a5f) | Sep 30, 2021 |
| Toshiba       | Satellite L500              | Notebook    | [07116867d0](https://linux-hardware.org/?probe=07116867d0) | Sep 30, 2021 |
| ASUSTek       | P5KC                        | Desktop     | [c6c9f72f10](https://linux-hardware.org/?probe=c6c9f72f10) | Sep 29, 2021 |
| Unknown       | Unknown                     | Notebook    | [1466ee93ee](https://linux-hardware.org/?probe=1466ee93ee) | Sep 29, 2021 |
| SLIMBOOK      | TITAN                       | Notebook    | [985d394a66](https://linux-hardware.org/?probe=985d394a66) | Sep 29, 2021 |
| ASUSTek       | M4N68T-M                    | Desktop     | [adaee7ea4e](https://linux-hardware.org/?probe=adaee7ea4e) | Sep 28, 2021 |
| Intel         | NUC7i3BNB J22859-309        | Mini pc     | [053ea52cd6](https://linux-hardware.org/?probe=053ea52cd6) | Sep 28, 2021 |
| HP            | Pavilion dv6                | Notebook    | [0a3653d139](https://linux-hardware.org/?probe=0a3653d139) | Sep 27, 2021 |
| Acer          | Aspire ES1-512              | Notebook    | [d573d0691e](https://linux-hardware.org/?probe=d573d0691e) | Sep 27, 2021 |
| Acer          | Aspire ES1-512              | Notebook    | [6aa9666f2c](https://linux-hardware.org/?probe=6aa9666f2c) | Sep 27, 2021 |
| HP            | Pavilion dv6                | Notebook    | [a5de874a12](https://linux-hardware.org/?probe=a5de874a12) | Sep 26, 2021 |
| Dell          | Latitude 5400               | Notebook    | [c94a87ddcd](https://linux-hardware.org/?probe=c94a87ddcd) | Sep 26, 2021 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [c11c48b5d6](https://linux-hardware.org/?probe=c11c48b5d6) | Sep 24, 2021 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [66900d1009](https://linux-hardware.org/?probe=66900d1009) | Sep 24, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [d8d6573dea](https://linux-hardware.org/?probe=d8d6573dea) | Sep 23, 2021 |
| Shuttle       | NC03U                       | Desktop     | [c5f76c4400](https://linux-hardware.org/?probe=c5f76c4400) | Sep 22, 2021 |
| Fujitsu       | LIFEBOOK AH552/SL           | Notebook    | [adefc47ea8](https://linux-hardware.org/?probe=adefc47ea8) | Sep 22, 2021 |
| Toshiba       | PORTEGE Z30-A               | Notebook    | [13b9ce0773](https://linux-hardware.org/?probe=13b9ce0773) | Sep 22, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [6a1f29d17c](https://linux-hardware.org/?probe=6a1f29d17c) | Sep 22, 2021 |
| Dynabook      | PORTEGE X50-G               | Notebook    | [da8279a7a9](https://linux-hardware.org/?probe=da8279a7a9) | Sep 22, 2021 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [8a14f4f8ce](https://linux-hardware.org/?probe=8a14f4f8ce) | Sep 20, 2021 |
| Foxconn       | A74ML-K                     | Desktop     | [b7a9a59c77](https://linux-hardware.org/?probe=b7a9a59c77) | Sep 19, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [61fd64b037](https://linux-hardware.org/?probe=61fd64b037) | Sep 19, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [a7a8c2cead](https://linux-hardware.org/?probe=a7a8c2cead) | Sep 18, 2021 |
| Biostar       | A68MHE                      | Desktop     | [8a2cdafa86](https://linux-hardware.org/?probe=8a2cdafa86) | Sep 18, 2021 |
| Sony          | VGN-FZ31Z                   | Notebook    | [134fab4631](https://linux-hardware.org/?probe=134fab4631) | Sep 17, 2021 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | Desktop     | [82058974d9](https://linux-hardware.org/?probe=82058974d9) | Sep 17, 2021 |
| Libretrend    | LT1000                      | Desktop     | [781fa86fea](https://linux-hardware.org/?probe=781fa86fea) | Sep 17, 2021 |
| Sony          | VGN-FZ31Z                   | Notebook    | [78a5f6cc5b](https://linux-hardware.org/?probe=78a5f6cc5b) | Sep 16, 2021 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [e8ac4691b0](https://linux-hardware.org/?probe=e8ac4691b0) | Sep 16, 2021 |
| Sony          | VGN-FZ31Z                   | Notebook    | [fd9704ad22](https://linux-hardware.org/?probe=fd9704ad22) | Sep 16, 2021 |
| ASUSTek       | F5SL                        | Notebook    | [e6e93168a6](https://linux-hardware.org/?probe=e6e93168a6) | Sep 15, 2021 |
| Sony          | VGN-FZ21M                   | Notebook    | [f68a8cedaa](https://linux-hardware.org/?probe=f68a8cedaa) | Sep 15, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [c9286413a5](https://linux-hardware.org/?probe=c9286413a5) | Sep 15, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [6488a302af](https://linux-hardware.org/?probe=6488a302af) | Sep 15, 2021 |
| ASRock        | X570M Pro4                  | Desktop     | [297bbaf6a4](https://linux-hardware.org/?probe=297bbaf6a4) | Sep 14, 2021 |
| Acer          | Elena                       | Desktop     | [c05122b62f](https://linux-hardware.org/?probe=c05122b62f) | Sep 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [232a307a5b](https://linux-hardware.org/?probe=232a307a5b) | Sep 14, 2021 |
| Acer          | Aspire ES1-520              | Notebook    | [4b4f263238](https://linux-hardware.org/?probe=4b4f263238) | Sep 14, 2021 |
| Intel         | powered classmate PC        | Notebook    | [15cb9c7764](https://linux-hardware.org/?probe=15cb9c7764) | Sep 12, 2021 |
| ASUSTek       | B85M-E                      | Desktop     | [1ef0a151b1](https://linux-hardware.org/?probe=1ef0a151b1) | Sep 12, 2021 |
| ASUSTek       | ROG CROSSHAIR VI EXTREME    | Desktop     | [4404093ccf](https://linux-hardware.org/?probe=4404093ccf) | Sep 12, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [bfe6584c68](https://linux-hardware.org/?probe=bfe6584c68) | Sep 12, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [e82ca3db5b](https://linux-hardware.org/?probe=e82ca3db5b) | Sep 12, 2021 |
| MSI           | GE75 Raider 8RF             | Notebook    | [350527f093](https://linux-hardware.org/?probe=350527f093) | Sep 10, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [13d65a1a4e](https://linux-hardware.org/?probe=13d65a1a4e) | Sep 09, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c50b07bfbc](https://linux-hardware.org/?probe=c50b07bfbc) | Sep 08, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [24053a2921](https://linux-hardware.org/?probe=24053a2921) | Sep 07, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [b34fb7492d](https://linux-hardware.org/?probe=b34fb7492d) | Sep 07, 2021 |
| MSI           | B350 TOMAHAWK ARCTIC        | Desktop     | [b92b2f815b](https://linux-hardware.org/?probe=b92b2f815b) | Sep 07, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e65bcd50d4](https://linux-hardware.org/?probe=e65bcd50d4) | Sep 05, 2021 |
| ASUSTek       | K53SV                       | Notebook    | [f617f97f20](https://linux-hardware.org/?probe=f617f97f20) | Sep 03, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [be1de37337](https://linux-hardware.org/?probe=be1de37337) | Sep 03, 2021 |
| Dell          | 0X947H A01                  | Server      | [e36bfcd946](https://linux-hardware.org/?probe=e36bfcd946) | Sep 02, 2021 |
| Dell          | 0X947H A01                  | Server      | [faee3aa1d7](https://linux-hardware.org/?probe=faee3aa1d7) | Sep 02, 2021 |
| ASUSTek       | P5L8L-SE                    | Desktop     | [32e39bbd4f](https://linux-hardware.org/?probe=32e39bbd4f) | Sep 02, 2021 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [243dba3b27](https://linux-hardware.org/?probe=243dba3b27) | Sep 02, 2021 |
| Intel         | NUC7i3BNB J22859-309        | Mini pc     | [54825c8496](https://linux-hardware.org/?probe=54825c8496) | Sep 02, 2021 |
| Intel         | NUC7i3BNB J22859-309        | Mini pc     | [3a4c36db86](https://linux-hardware.org/?probe=3a4c36db86) | Sep 02, 2021 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [ca0e00bc0f](https://linux-hardware.org/?probe=ca0e00bc0f) | Sep 01, 2021 |
| ASRock        | N68-VS3 FX                  | Desktop     | [450ffd830c](https://linux-hardware.org/?probe=450ffd830c) | Sep 01, 2021 |
| ASUSTek       | P8H67                       | Desktop     | [73edbfaf52](https://linux-hardware.org/?probe=73edbfaf52) | Sep 01, 2021 |
| ASUSTek       | P8H67                       | Desktop     | [cefaaa7f19](https://linux-hardware.org/?probe=cefaaa7f19) | Sep 01, 2021 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | Notebook    | [62e286b6bc](https://linux-hardware.org/?probe=62e286b6bc) | Aug 31, 2021 |
| Lenovo        | ThinkPad T430 2349V4B       | Notebook    | [33a45018fc](https://linux-hardware.org/?probe=33a45018fc) | Aug 31, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | Notebook    | [84ed2a684d](https://linux-hardware.org/?probe=84ed2a684d) | Aug 30, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [6d630f76dc](https://linux-hardware.org/?probe=6d630f76dc) | Aug 30, 2021 |
| ASRock        | 760GM-HDV                   | Desktop     | [7b2322353d](https://linux-hardware.org/?probe=7b2322353d) | Aug 29, 2021 |
| Apple         | MacBookAir3,1               | Notebook    | [c431035e14](https://linux-hardware.org/?probe=c431035e14) | Aug 28, 2021 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [26e4c99970](https://linux-hardware.org/?probe=26e4c99970) | Aug 27, 2021 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [25c5f20a00](https://linux-hardware.org/?probe=25c5f20a00) | Aug 27, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [fcfdefc5ce](https://linux-hardware.org/?probe=fcfdefc5ce) | Aug 24, 2021 |
| Unknown       | 1.0                         | Desktop     | [5e638360a8](https://linux-hardware.org/?probe=5e638360a8) | Aug 24, 2021 |
| Acer          | Aspire one 1-431            | Notebook    | [1d73bf7163](https://linux-hardware.org/?probe=1d73bf7163) | Aug 23, 2021 |
| HP            | Compaq Presario CQ50        | Notebook    | [afde6653db](https://linux-hardware.org/?probe=afde6653db) | Aug 20, 2021 |
| ECS           | Livermore8                  | Desktop     | [a86f5a7745](https://linux-hardware.org/?probe=a86f5a7745) | Aug 18, 2021 |
| ASUSTek       | K52Je                       | Notebook    | [d35de28c56](https://linux-hardware.org/?probe=d35de28c56) | Aug 17, 2021 |
| Unknown       | Unknown                     | Desktop     | [65ebd0006e](https://linux-hardware.org/?probe=65ebd0006e) | Aug 16, 2021 |
| Samsung       | 905S3G/906S3G/915S3G/930... | Notebook    | [c2dee4fe1c](https://linux-hardware.org/?probe=c2dee4fe1c) | Aug 14, 2021 |
| HP            | Compaq Presario CQ71        | Notebook    | [c1e4d1748b](https://linux-hardware.org/?probe=c1e4d1748b) | Aug 14, 2021 |
| ASUSTek       | K52Je                       | Notebook    | [ae9629c543](https://linux-hardware.org/?probe=ae9629c543) | Aug 13, 2021 |
| Teclast       | TbooK 11                    | Notebook    | [d045383640](https://linux-hardware.org/?probe=d045383640) | Aug 12, 2021 |
| Teclast       | TbooK 11                    | Notebook    | [f3e17cb791](https://linux-hardware.org/?probe=f3e17cb791) | Aug 12, 2021 |
| ASUSTek       | X541UV                      | Notebook    | [3f45acb762](https://linux-hardware.org/?probe=3f45acb762) | Aug 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [3fb07ec1ab](https://linux-hardware.org/?probe=3fb07ec1ab) | Aug 11, 2021 |
| MSI           | Alpha 15 A4DEK              | Notebook    | [f8bd1ccc54](https://linux-hardware.org/?probe=f8bd1ccc54) | Aug 09, 2021 |
| ASUSTek       | P5P43TD PRO                 | Desktop     | [0576757382](https://linux-hardware.org/?probe=0576757382) | Aug 08, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [f8727e28db](https://linux-hardware.org/?probe=f8727e28db) | Aug 05, 2021 |
| MSI           | Alpha 15 A4DEK              | Notebook    | [77c994366c](https://linux-hardware.org/?probe=77c994366c) | Aug 04, 2021 |
| Biostar       | A68MHE                      | Desktop     | [160e00a244](https://linux-hardware.org/?probe=160e00a244) | Aug 04, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [ea96dd2fc0](https://linux-hardware.org/?probe=ea96dd2fc0) | Aug 03, 2021 |
| Acer          | Extensa 5635ZG              | Notebook    | [7b18fd92ec](https://linux-hardware.org/?probe=7b18fd92ec) | Aug 01, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [dde43dfc5f](https://linux-hardware.org/?probe=dde43dfc5f) | Jul 31, 2021 |
| Acer          | Extensa 5635ZG              | Notebook    | [920920b284](https://linux-hardware.org/?probe=920920b284) | Jul 30, 2021 |
| Foxconn       | G41MXE/G41MXE-K             | Desktop     | [a6df82ec75](https://linux-hardware.org/?probe=a6df82ec75) | Jul 30, 2021 |
| Foxconn       | G41MXE/G41MXE-K             | Desktop     | [b33ddef912](https://linux-hardware.org/?probe=b33ddef912) | Jul 30, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [a4d0bd11cf](https://linux-hardware.org/?probe=a4d0bd11cf) | Jul 30, 2021 |
| Packard Be... | EasyNote MB65               | Notebook    | [f659f0645c](https://linux-hardware.org/?probe=f659f0645c) | Jul 28, 2021 |
| Intel         | NUC7i3BNB J22859-309        | Mini pc     | [bd1b8e13fe](https://linux-hardware.org/?probe=bd1b8e13fe) | Jul 28, 2021 |
| Toshiba       | Satellite L50-B             | Notebook    | [0e3d86e5fc](https://linux-hardware.org/?probe=0e3d86e5fc) | Jul 28, 2021 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [e877303c3f](https://linux-hardware.org/?probe=e877303c3f) | Jul 28, 2021 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | Notebook    | [abdeaec5ce](https://linux-hardware.org/?probe=abdeaec5ce) | Jul 28, 2021 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | Notebook    | [5258847421](https://linux-hardware.org/?probe=5258847421) | Jul 28, 2021 |
| ASUSTek       | X550DP                      | Notebook    | [fab8695920](https://linux-hardware.org/?probe=fab8695920) | Jul 27, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [ec1cea0d9d](https://linux-hardware.org/?probe=ec1cea0d9d) | Jul 25, 2021 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [a2ba4d937e](https://linux-hardware.org/?probe=a2ba4d937e) | Jul 25, 2021 |
| Lenovo        | ThinkPad T490 20N3S27C00    | Notebook    | [f4f26a9357](https://linux-hardware.org/?probe=f4f26a9357) | Jul 24, 2021 |
| Sony          | VGN-AW21Z_B                 | Notebook    | [16afdefee9](https://linux-hardware.org/?probe=16afdefee9) | Jul 23, 2021 |
| Fujitsu       | LIFEBOOK U7411              | Notebook    | [ad8fb39682](https://linux-hardware.org/?probe=ad8fb39682) | Jul 23, 2021 |
| Lenovo        | ThinkPad T480 20L5S03600    | Notebook    | [996bc7336f](https://linux-hardware.org/?probe=996bc7336f) | Jul 23, 2021 |
| Lenovo        | ThinkPad T480 20L5S03600    | Notebook    | [84d70d9bde](https://linux-hardware.org/?probe=84d70d9bde) | Jul 23, 2021 |
| HP            | ProLiant ML350 G5           | Desktop     | [189789f8d5](https://linux-hardware.org/?probe=189789f8d5) | Jul 23, 2021 |
| Toshiba       | Satellite M70               | Notebook    | [ffe4b92da3](https://linux-hardware.org/?probe=ffe4b92da3) | Jul 21, 2021 |
| Intel         | DH61WW AAG23116-206         | Desktop     | [bdd8ae093d](https://linux-hardware.org/?probe=bdd8ae093d) | Jul 21, 2021 |
| Dell          | 04MFRM A02                  | Desktop     | [9d92f05e1c](https://linux-hardware.org/?probe=9d92f05e1c) | Jul 17, 2021 |
| Dell          | 04MFRM A02                  | Desktop     | [2b2a31a2f9](https://linux-hardware.org/?probe=2b2a31a2f9) | Jul 17, 2021 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [1056457127](https://linux-hardware.org/?probe=1056457127) | Jul 17, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [6e299e2f37](https://linux-hardware.org/?probe=6e299e2f37) | Jul 16, 2021 |
| Toshiba       | Satellite C50-B             | Notebook    | [288b6b0769](https://linux-hardware.org/?probe=288b6b0769) | Jul 16, 2021 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [4004b6bcb6](https://linux-hardware.org/?probe=4004b6bcb6) | Jul 16, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Portugal/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 199       | 12.88%  |
| Ubuntu 18.04                 | 139       | 9%      |
| Ubuntu 22.04                 | 64        | 4.14%   |
| OpenMandriva 4.3             | 48        | 3.11%   |
| Debian 11                    | 38        | 2.46%   |
| OpenMandriva 4.2             | 36        | 2.33%   |
| Zorin 16                     | 32        | 2.07%   |
| Zorin 15                     | 29        | 1.88%   |
| Pop!_OS 20.04                | 28        | 1.81%   |
| Pop!_OS 22.04                | 27        | 1.75%   |
| KDE neon 20.04               | 23        | 1.49%   |
| Ubuntu 19.10                 | 22        | 1.42%   |
| Linux Mint 20.3              | 22        | 1.42%   |
| Linux Mint 19.3              | 22        | 1.42%   |
| Arch Rolling                 | 22        | 1.42%   |
| Linux Mint 20                | 21        | 1.36%   |
| Debian 10                    | 21        | 1.36%   |
| Manjaro                      | 20        | 1.29%   |
| Fedora 34                    | 20        | 1.29%   |
| Pop!_OS 21.04                | 19        | 1.23%   |
| Linux Mint 20.1              | 19        | 1.23%   |
| Ubuntu 19.04                 | 17        | 1.1%    |
| OpenMandriva 23.01           | 17        | 1.1%    |
| Xubuntu 20.04                | 16        | 1.04%   |
| Ubuntu 20.10                 | 16        | 1.04%   |
| OpenMandriva 4.50            | 16        | 1.04%   |
| Fedora 36                    | 16        | 1.04%   |
| Arch                         | 16        | 1.04%   |
| Ubuntu 21.10                 | 15        | 0.97%   |
| Ubuntu 21.04                 | 15        | 0.97%   |
| Pop!_OS 20.10                | 15        | 0.97%   |
| Xubuntu 18.04                | 14        | 0.91%   |
| Pop!_OS 21.10                | 14        | 0.91%   |
| Fedora 37                    | 14        | 0.91%   |
| Fedora 33                    | 14        | 0.91%   |
| ArcoLinux Rolling            | 14        | 0.91%   |
| Linux Mint 21.1              | 13        | 0.84%   |
| Linux Mint 19.1              | 13        | 0.84%   |
| openSUSE Tumbleweed-XXXXXXXX | 12        | 0.78%   |
| Linux Mint 21                | 12        | 0.78%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 487       | 33.22%  |
| Linux Mint    | 137       | 9.35%   |
| OpenMandriva  | 123       | 8.39%   |
| Pop!_OS       | 100       | 6.82%   |
| Fedora        | 85        | 5.8%    |
| Debian        | 69        | 4.71%   |
| Zorin         | 62        | 4.23%   |
| Manjaro       | 51        | 3.48%   |
| Endless       | 41        | 2.8%    |
| Arch          | 39        | 2.66%   |
| Xubuntu       | 34        | 2.32%   |
| KDE neon      | 34        | 2.32%   |
| ROSA          | 19        | 1.3%    |
| Kubuntu       | 19        | 1.3%    |
| openSUSE      | 16        | 1.09%   |
| Elementary    | 16        | 1.09%   |
| ArcoLinux     | 15        | 1.02%   |
| Ubuntu Unity  | 10        | 0.68%   |
| Ubuntu MATE   | 9         | 0.61%   |
| Slackware     | 7         | 0.48%   |
| LMDE          | 7         | 0.48%   |
| Clear Linux   | 7         | 0.48%   |
| Ubuntu Budgie | 6         | 0.41%   |
| Lubuntu       | 6         | 0.41%   |
| EndeavourOS   | 6         | 0.41%   |
| Nobara        | 5         | 0.34%   |
| Gentoo        | 5         | 0.34%   |
| Kali          | 4         | 0.27%   |
| UbuntuDDE     | 3         | 0.2%    |
| Peppermint    | 3         | 0.2%    |
| CentOS        | 3         | 0.2%    |
| XCP-ng        | 2         | 0.14%   |
| SteamOS       | 2         | 0.14%   |
| Reborn OS     | 2         | 0.14%   |
| Raspbian      | 2         | 0.14%   |
| Parrot        | 2         | 0.14%   |
| MX            | 2         | 0.14%   |
| Manjaro-ARM   | 2         | 0.14%   |
| Devuan        | 2         | 0.14%   |
| BlackPanther  | 2         | 0.14%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 40        | 2.34%   |
| 5.4.0-42-generic         | 38        | 2.22%   |
| 5.10.14-desktop-1omv4002 | 35        | 2.05%   |
| 5.15.0-56-generic        | 19        | 1.11%   |
| 5.3.0-46-generic         | 16        | 0.94%   |
| 6.1.1-desktop-1omv2290   | 15        | 0.88%   |
| 5.4.0-58-generic         | 15        | 0.88%   |
| 5.4.0-52-generic         | 15        | 0.88%   |
| 5.4.0-29-generic         | 14        | 0.82%   |
| 5.15.0-58-generic        | 13        | 0.76%   |
| 5.15.0-52-generic        | 13        | 0.76%   |
| 5.15.0-48-generic        | 13        | 0.76%   |
| 5.15.0-46-generic        | 13        | 0.76%   |
| 5.11.0-38-generic        | 13        | 0.76%   |
| 5.4.0-26-generic         | 12        | 0.7%    |
| 5.3.0-28-generic         | 12        | 0.7%    |
| 5.0.0-37-generic         | 12        | 0.7%    |
| 6.2.6-desktop-1omv2390   | 11        | 0.64%   |
| 5.4.0-7634-generic       | 11        | 0.64%   |
| 5.19.0-76051900-generic  | 11        | 0.64%   |
| 5.14.14-desktop-1omv4050 | 11        | 0.64%   |
| 5.10.0-8-amd64           | 11        | 0.64%   |
| 5.8.0-43-generic         | 10        | 0.59%   |
| 5.4.0-48-generic         | 10        | 0.59%   |
| 5.15.0-41-generic        | 10        | 0.59%   |
| 5.0.0-25-generic         | 10        | 0.59%   |
| 4.18.0-15-generic        | 10        | 0.59%   |
| 5.8.0-48-generic         | 9         | 0.53%   |
| 5.3.0-40-generic         | 9         | 0.53%   |
| 5.11.0-43-generic        | 9         | 0.53%   |
| 4.15.0-46-generic        | 9         | 0.53%   |
| 5.8.0-44-generic         | 8         | 0.47%   |
| 5.4.0-37-generic         | 8         | 0.47%   |
| 5.19.0-35-generic        | 8         | 0.47%   |
| 5.13.0-39-generic        | 8         | 0.47%   |
| 4.18.0-25-generic        | 8         | 0.47%   |
| 5.4.0-65-generic         | 7         | 0.41%   |
| 5.4.0-40-generic         | 7         | 0.41%   |
| 5.4.0-31-generic         | 7         | 0.41%   |
| 5.4.0-28-generic         | 7         | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 270       | 16.86%  |
| 5.15.0  | 119       | 7.43%   |
| 4.15.0  | 109       | 6.81%   |
| 5.8.0   | 93        | 5.81%   |
| 5.11.0  | 85        | 5.31%   |
| 5.3.0   | 83        | 5.18%   |
| 5.13.0  | 70        | 4.37%   |
| 5.0.0   | 58        | 3.62%   |
| 4.18.0  | 47        | 2.94%   |
| 5.19.0  | 42        | 2.62%   |
| 5.10.0  | 41        | 2.56%   |
| 5.16.7  | 40        | 2.5%    |
| 5.10.14 | 37        | 2.31%   |
| 4.19.0  | 24        | 1.5%    |
| 6.1.1   | 18        | 1.12%   |
| 6.2.6   | 15        | 0.94%   |
| 5.14.14 | 11        | 0.69%   |
| 5.11.12 | 9         | 0.56%   |
| 6.2.0   | 6         | 0.37%   |
| 6.0.9   | 6         | 0.37%   |
| 5.14.0  | 6         | 0.37%   |
| 4.9.155 | 6         | 0.37%   |
| 4.4.0   | 6         | 0.37%   |
| 6.0.6   | 5         | 0.31%   |
| 6.0.12  | 5         | 0.31%   |
| 5.15.7  | 5         | 0.31%   |
| 5.13.19 | 5         | 0.31%   |
| 5.12.4  | 5         | 0.31%   |
| 6.0.0   | 4         | 0.25%   |
| 5.8.16  | 4         | 0.25%   |
| 5.7.10  | 4         | 0.25%   |
| 5.7.0   | 4         | 0.25%   |
| 5.6.0   | 4         | 0.25%   |
| 5.16.11 | 4         | 0.25%   |
| 5.15.11 | 4         | 0.25%   |
| 5.14.16 | 4         | 0.25%   |
| 4.9.60  | 4         | 0.25%   |
| 4.9.0   | 4         | 0.25%   |
| 6.2.10  | 3         | 0.19%   |
| 6.1.4   | 3         | 0.19%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 286       | 18.07%  |
| 5.15    | 162       | 10.23%  |
| 5.8     | 116       | 7.33%   |
| 4.15    | 110       | 6.95%   |
| 5.11    | 99        | 6.25%   |
| 5.10    | 97        | 6.13%   |
| 5.3     | 86        | 5.43%   |
| 5.13    | 84        | 5.31%   |
| 5.16    | 63        | 3.98%   |
| 5.19    | 61        | 3.85%   |
| 5.0     | 59        | 3.73%   |
| 4.18    | 51        | 3.22%   |
| 6.1     | 40        | 2.53%   |
| 6.2     | 33        | 2.08%   |
| 6.0     | 32        | 2.02%   |
| 5.14    | 31        | 1.96%   |
| 4.19    | 28        | 1.77%   |
| 5.12    | 22        | 1.39%   |
| 4.9     | 20        | 1.26%   |
| 5.7     | 16        | 1.01%   |
| 5.9     | 15        | 0.95%   |
| 5.17    | 15        | 0.95%   |
| 5.6     | 14        | 0.88%   |
| 5.18    | 13        | 0.82%   |
| 5.5     | 10        | 0.63%   |
| 4.4     | 6         | 0.38%   |
| 5.2     | 4         | 0.25%   |
| 4.12    | 2         | 0.13%   |
| 4.10    | 2         | 0.13%   |
| 6.3     | 1         | 0.06%   |
| 5.1     | 1         | 0.06%   |
| 4.1     | 1         | 0.06%   |
| 3.10    | 1         | 0.06%   |
| 2.6     | 1         | 0.06%   |
| Unknown | 1         | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1339      | 94.9%   |
| i686    | 63        | 4.46%   |
| aarch64 | 7         | 0.5%    |
| armv7l  | 2         | 0.14%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 655       | 44.11%  |
| KDE5            | 231       | 15.56%  |
| Unknown         | 217       | 14.61%  |
| XFCE            | 111       | 7.47%   |
| X-Cinnamon      | 106       | 7.14%   |
| KDE             | 32        | 2.15%   |
| MATE            | 28        | 1.89%   |
| Pantheon        | 15        | 1.01%   |
| Cinnamon        | 14        | 0.94%   |
| Budgie          | 13        | 0.88%   |
| KDE4            | 12        | 0.81%   |
| Unity           | 11        | 0.74%   |
| i3              | 10        | 0.67%   |
| LXQt            | 6         | 0.4%    |
| awesome         | 6         | 0.4%    |
| LXDE            | 5         | 0.34%   |
| Deepin          | 4         | 0.27%   |
| GNOME Flashback | 3         | 0.2%    |
| Openbox         | 2         | 0.13%   |
| qtile           | 1         | 0.07%   |
| LeftWM          | 1         | 0.07%   |
| Hyprland        | 1         | 0.07%   |
| fluxbox         | 1         | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1123      | 77.66%  |
| Wayland | 198       | 13.69%  |
| Unknown | 116       | 8.02%   |
| Tty     | 9         | 0.62%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 821       | 56.12%  |
| SDDM    | 200       | 13.67%  |
| GDM     | 141       | 9.64%   |
| GDM3    | 137       | 9.36%   |
| LightDM | 104       | 7.11%   |
| TDM     | 43        | 2.94%   |
| KDM     | 12        | 0.82%   |
| XDM     | 4         | 0.27%   |
| SLiM    | 1         | 0.07%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| pt_PT   | 589       | 40.48%  |
| en_US   | 504       | 34.64%  |
| Unknown | 199       | 13.68%  |
| en_GB   | 74        | 5.09%   |
| C       | 28        | 1.92%   |
| pt_BR   | 23        | 1.58%   |
| fr_FR   | 8         | 0.55%   |
| ru_RU   | 5         | 0.34%   |
| en_IE   | 5         | 0.34%   |
| de_DE   | 5         | 0.34%   |
| es_ES   | 4         | 0.27%   |
| sv_SE   | 3         | 0.21%   |
| POSIX   | 2         | 0.14%   |
| en_CA   | 2         | 0.14%   |
| sk_SK   | 1         | 0.07%   |
| it_IT   | 1         | 0.07%   |
| en_IN   | 1         | 0.07%   |
| Default | 1         | 0.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 812       | 56.08%  |
| EFI  | 636       | 43.92%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 1123      | 78.15%  |
| Overlay  | 108       | 7.52%   |
| Btrfs    | 104       | 7.24%   |
| Unknown  | 67        | 4.66%   |
| Xfs      | 14        | 0.97%   |
| Zfs      | 8         | 0.56%   |
| Ext2     | 5         | 0.35%   |
| Ext3     | 4         | 0.28%   |
| Tmpfs    | 1         | 0.07%   |
| Reiserfs | 1         | 0.07%   |
| F2fs     | 1         | 0.07%   |
| Aufs     | 1         | 0.07%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 874       | 60.32%  |
| GPT     | 437       | 30.16%  |
| MBR     | 138       | 9.52%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1249      | 87.4%   |
| Yes       | 180       | 12.6%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1023      | 71.19%  |
| Yes       | 414       | 28.81%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 321       | 22.77%  |
| Hewlett-Packard         | 216       | 15.32%  |
| Lenovo                  | 187       | 13.26%  |
| Acer                    | 107       | 7.59%   |
| MSI                     | 81        | 5.74%   |
| Toshiba                 | 77        | 5.46%   |
| Dell                    | 69        | 4.89%   |
| Gigabyte Technology     | 57        | 4.04%   |
| Sony                    | 41        | 2.91%   |
| Apple                   | 35        | 2.48%   |
| ASRock                  | 26        | 1.84%   |
| HUAWEI                  | 20        | 1.42%   |
| Samsung Electronics     | 14        | 0.99%   |
| Intel                   | 14        | 0.99%   |
| Fujitsu                 | 13        | 0.92%   |
| Notebook                | 9         | 0.64%   |
| Foxconn                 | 8         | 0.57%   |
| Raspberry Pi Foundation | 7         | 0.5%    |
| Packard Bell            | 7         | 0.5%    |
| Unknown                 | 7         | 0.5%    |
| TUXEDO                  | 6         | 0.43%   |
| eMachines               | 6         | 0.43%   |
| Pegatron                | 4         | 0.28%   |
| Chuwi                   | 4         | 0.28%   |
| Phoenix/SiS             | 3         | 0.21%   |
| Microsoft               | 3         | 0.21%   |
| LG Electronics          | 3         | 0.21%   |
| Clevo                   | 3         | 0.21%   |
| Biostar                 | 3         | 0.21%   |
| AMI                     | 3         | 0.21%   |
| Teclast                 | 2         | 0.14%   |
| SLIMBOOK                | 2         | 0.14%   |
| Positivo                | 2         | 0.14%   |
| OEM                     | 2         | 0.14%   |
| OBSIDIAN-PC             | 2         | 0.14%   |
| Minix                   | 2         | 0.14%   |
| Medion                  | 2         | 0.14%   |
| IP3 Tech                | 2         | 0.14%   |
| INSYS                   | 2         | 0.14%   |
| Huanan                  | 2         | 0.14%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Sony VGN-FZ31Z                         | 20        | 1.42%   |
| ASUS All Series                        | 15        | 1.06%   |
| Lenovo IdeaPad 1 14ADA05 82GW          | 14        | 0.99%   |
| Unknown                                | 9         | 0.64%   |
| Toshiba Satellite C660                 | 8         | 0.57%   |
| HP Pavilion g6                         | 8         | 0.57%   |
| HP Pavilion dv6                        | 8         | 0.57%   |
| HP G62                                 | 7         | 0.5%    |
| HP Notebook                            | 6         | 0.43%   |
| Toshiba Satellite L650                 | 5         | 0.35%   |
| MSI MS-7817                            | 5         | 0.35%   |
| Lenovo Legion 5 15ACH6H 82JU           | 5         | 0.35%   |
| ASUS X555LJ                            | 5         | 0.35%   |
| ASUS X555LD                            | 5         | 0.35%   |
| ASUS X541UV                            | 5         | 0.35%   |
| Acer Extensa 5620                      | 5         | 0.35%   |
| Toshiba Satellite L500                 | 4         | 0.28%   |
| Toshiba Satellite L40                  | 4         | 0.28%   |
| Toshiba Satellite A200                 | 4         | 0.28%   |
| Lenovo Y520-15IKBN 80WK                | 4         | 0.28%   |
| HUAWEI NBLK-WAX9X                      | 4         | 0.28%   |
| HP Pavilion Notebook                   | 4         | 0.28%   |
| HP OMEN by Laptop 15-dc0xxx            | 4         | 0.28%   |
| HP Compaq Presario CQ60                | 4         | 0.28%   |
| ASUS X541UJ                            | 4         | 0.28%   |
| ASUS VivoBook_ASUSLaptop X512DA_F512DA | 4         | 0.28%   |
| ASUS VivoBook 15_ASUS Laptop X507LA    | 4         | 0.28%   |
| ASUS P5G41T-M LX                       | 4         | 0.28%   |
| ASUS H110M-K                           | 4         | 0.28%   |
| Acer Aspire E5-551G                    | 4         | 0.28%   |
| Toshiba Satellite L50D-B               | 3         | 0.21%   |
| MSI Modern 14 A10RB                    | 3         | 0.21%   |
| Lenovo Legion 5 15ARH05 82B5           | 3         | 0.21%   |
| Lenovo IdeaPad 320-15AST 80XV          | 3         | 0.21%   |
| Lenovo G50-45 80E3                     | 3         | 0.21%   |
| Intel powered classmate PC             | 3         | 0.21%   |
| HUAWEI WRT-WX9                         | 3         | 0.21%   |
| HP Pavilion Gaming Laptop 15-ec2xxx    | 3         | 0.21%   |
| HP Pavilion 15                         | 3         | 0.21%   |
| HP OMEN by Laptop                      | 3         | 0.21%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 88        | 6.24%   |
| Acer Aspire           | 87        | 6.17%   |
| Toshiba Satellite     | 67        | 4.75%   |
| HP Pavilion           | 58        | 4.11%   |
| Lenovo IdeaPad        | 52        | 3.69%   |
| HP Compaq             | 33        | 2.34%   |
| ASUS VivoBook         | 33        | 2.34%   |
| ASUS PRIME            | 24        | 1.7%    |
| HP EliteBook          | 23        | 1.63%   |
| Dell Latitude         | 23        | 1.63%   |
| Sony VGN-FZ31Z        | 20        | 1.42%   |
| ASUS ROG              | 17        | 1.21%   |
| HP ProBook            | 15        | 1.06%   |
| ASUS All              | 15        | 1.06%   |
| Lenovo Legion         | 13        | 0.92%   |
| Dell XPS              | 13        | 0.92%   |
| HP Laptop             | 12        | 0.85%   |
| Dell OptiPlex         | 11        | 0.78%   |
| ASUS TUF              | 11        | 0.78%   |
| HP OMEN               | 10        | 0.71%   |
| HP ENVY               | 10        | 0.71%   |
| Dell Inspiron         | 10        | 0.71%   |
| ASUS ZenBook          | 10        | 0.71%   |
| Dell Precision        | 9         | 0.64%   |
| ASUS P5G41T-M         | 9         | 0.64%   |
| Unknown               | 9         | 0.64%   |
| Acer Extensa          | 8         | 0.57%   |
| RPi Raspberry         | 7         | 0.5%    |
| HP G62                | 7         | 0.5%    |
| Packard Bell EasyNote | 6         | 0.43%   |
| MSI Modern            | 6         | 0.43%   |
| HP ProLiant           | 6         | 0.43%   |
| HP ProDesk            | 6         | 0.43%   |
| HP Notebook           | 6         | 0.43%   |
| Gigabyte B550         | 6         | 0.43%   |
| MSI MS-7817           | 5         | 0.35%   |
| Fujitsu LIFEBOOK      | 5         | 0.35%   |
| ASUS X555LJ           | 5         | 0.35%   |
| ASUS X555LD           | 5         | 0.35%   |
| ASUS X541UV           | 5         | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 130       | 9.22%   |
| 2018    | 122       | 8.65%   |
| 2019    | 118       | 8.37%   |
| 2010    | 112       | 7.94%   |
| 2015    | 84        | 5.96%   |
| 2013    | 82        | 5.82%   |
| 2014    | 81        | 5.74%   |
| 2012    | 81        | 5.74%   |
| 2008    | 76        | 5.39%   |
| 2016    | 75        | 5.32%   |
| 2017    | 74        | 5.25%   |
| 2007    | 74        | 5.25%   |
| 2011    | 73        | 5.18%   |
| 2009    | 73        | 5.18%   |
| 2021    | 71        | 5.04%   |
| 2006    | 30        | 2.13%   |
| 2022    | 25        | 1.77%   |
| 2005    | 14        | 0.99%   |
| Unknown | 10        | 0.71%   |
| 2004    | 3         | 0.21%   |
| 2023    | 1         | 0.07%   |
| 2003    | 1         | 0.07%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 935       | 66.31%  |
| Desktop        | 411       | 29.15%  |
| Convertible    | 14        | 0.99%   |
| Mini pc        | 14        | 0.99%   |
| Tablet         | 10        | 0.71%   |
| All in one     | 9         | 0.64%   |
| System on chip | 8         | 0.57%   |
| Server         | 8         | 0.57%   |
| Phone          | 1         | 0.07%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1322      | 92.32%  |
| Enabled  | 110       | 7.68%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1406      | 99.72%  |
| Yes  | 4         | 0.28%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 377       | 26.22%  |
| 4.01-8.0        | 311       | 21.63%  |
| 16.01-24.0      | 233       | 16.2%   |
| 8.01-16.0       | 231       | 16.06%  |
| 32.01-64.0      | 111       | 7.72%   |
| 1.01-2.0        | 94        | 6.54%   |
| 2.01-3.0        | 32        | 2.23%   |
| 64.01-256.0     | 20        | 1.39%   |
| 24.01-32.0      | 14        | 0.97%   |
| 0.51-1.0        | 14        | 0.97%   |
| More than 256.0 | 1         | 0.07%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 602       | 38.64%  |
| 2.01-3.0    | 330       | 21.18%  |
| 4.01-8.0    | 235       | 15.08%  |
| 3.01-4.0    | 176       | 11.3%   |
| 0.51-1.0    | 119       | 7.64%   |
| 8.01-16.0   | 64        | 4.11%   |
| 0.01-0.5    | 15        | 0.96%   |
| 16.01-24.0  | 10        | 0.64%   |
| 24.01-32.0  | 4         | 0.26%   |
| 32.01-64.0  | 1         | 0.06%   |
| 64.01-256.0 | 1         | 0.06%   |
| Unknown     | 1         | 0.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 916       | 63.26%  |
| 2      | 354       | 24.45%  |
| 3      | 93        | 6.42%   |
| 4      | 42        | 2.9%    |
| 0      | 18        | 1.24%   |
| 5      | 10        | 0.69%   |
| 6      | 7         | 0.48%   |
| 11     | 2         | 0.14%   |
| 10     | 2         | 0.14%   |
| 7      | 2         | 0.14%   |
| 87     | 1         | 0.07%   |
| 8      | 1         | 0.07%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 871       | 61.55%  |
| Yes       | 544       | 38.45%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1224      | 86.44%  |
| No        | 192       | 13.56%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1103      | 77.68%  |
| No        | 317       | 22.32%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 803       | 56.04%  |
| No        | 630       | 43.96%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Computers | Percent |
|----------|-----------|---------|
| Portugal | 1410      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                         | Computers | Percent |
|------------------------------|-----------|---------|
| Lisbon                       | 339       | 22.52%  |
| Porto                        | 126       | 8.37%   |
| Amadora                      | 37        | 2.46%   |
| Vila Nova de Gaia            | 35        | 2.33%   |
| Funchal                      | 33        | 2.19%   |
| Braga                        | 31        | 2.06%   |
| Coimbra                      | 27        | 1.79%   |
| Setúbal                     | 24        | 1.59%   |
| Leiria                       | 23        | 1.53%   |
| Aveiro                       | 23        | 1.53%   |
| Faro                         | 22        | 1.46%   |
| Cascais                      | 18        | 1.2%    |
| Loures                       | 17        | 1.13%   |
| Sintra                       | 13        | 0.86%   |
| Mem Martins                  | 12        | 0.8%    |
| Evora                        | 12        | 0.8%    |
| Bragança                    | 12        | 0.8%    |
| Almada                       | 12        | 0.8%    |
| Póvoa de Varzim             | 11        | 0.73%   |
| Odivelas                     | 11        | 0.73%   |
| Guimaraes                    | 11        | 0.73%   |
| Viana do Castelo             | 10        | 0.66%   |
| Torres Vedras                | 10        | 0.66%   |
| Portimao                     | 10        | 0.66%   |
| Barreiro                     | 10        | 0.66%   |
| Amora                        | 10        | 0.66%   |
| Viseu                        | 9         | 0.6%    |
| Santarém                    | 9         | 0.6%    |
| Povoa de Santa Iria          | 9         | 0.6%    |
| Matosinhos Municipality      | 9         | 0.6%    |
| Alverca do Ribatejo          | 9         | 0.6%    |
| Vila do Conde                | 8         | 0.53%   |
| Trofa                        | 8         | 0.53%   |
| Maia                         | 8         | 0.53%   |
| Figueira da Foz Municipality | 8         | 0.53%   |
| Feira                        | 8         | 0.53%   |
| Cacem                        | 8         | 0.53%   |
| Vila Nova de Famalicao       | 7         | 0.47%   |
| Sao Joao da Madeira          | 7         | 0.47%   |
| Sao Domingos de Rana         | 7         | 0.47%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 290       | 404    | 14.78%  |
| WDC                         | 267       | 428    | 13.61%  |
| Seagate                     | 239       | 382    | 12.18%  |
| Toshiba                     | 180       | 269    | 9.17%   |
| Kingston                    | 180       | 235    | 9.17%   |
| SanDisk                     | 91        | 109    | 4.64%   |
| Unknown                     | 89        | 128    | 4.54%   |
| Crucial                     | 78        | 102    | 3.98%   |
| Hitachi                     | 74        | 85     | 3.77%   |
| HGST                        | 42        | 57     | 2.14%   |
| Intel                       | 39        | 61     | 1.99%   |
| SK hynix                    | 34        | 39     | 1.73%   |
| Micron Technology           | 25        | 29     | 1.27%   |
| KIOXIA                      | 23        | 39     | 1.17%   |
| Maxtor                      | 21        | 35     | 1.07%   |
| Fujitsu                     | 21        | 22     | 1.07%   |
| GOODRAM                     | 18        | 21     | 0.92%   |
| Apple                       | 14        | 14     | 0.71%   |
| PNY                         | 13        | 18     | 0.66%   |
| BlueRay                     | 12        | 14     | 0.61%   |
| S3+                         | 10        | 19     | 0.51%   |
| Phison                      | 10        | 16     | 0.51%   |
| China                       | 10        | 11     | 0.51%   |
| A-DATA Technology           | 10        | 10     | 0.51%   |
| KIOXIA-EXCERIA              | 9         | 10     | 0.46%   |
| JMicron Technology          | 8         | 8      | 0.41%   |
| Micron/Crucial Technology   | 7         | 12     | 0.36%   |
| LITEON                      | 7         | 8      | 0.36%   |
| Hewlett-Packard             | 7         | 8      | 0.36%   |
| Emtec                       | 7         | 8      | 0.36%   |
| Unknown                     | 7         | 8      | 0.36%   |
| Transcend                   | 6         | 7      | 0.31%   |
| Silicon Motion              | 6         | 6      | 0.31%   |
| Team                        | 5         | 6      | 0.25%   |
| Phison Electronics          | 5         | 6      | 0.25%   |
| OCZ                         | 5         | 5      | 0.25%   |
| Gigabyte Technology         | 5         | 6      | 0.25%   |
| Kingston Technology Company | 4         | 4      | 0.2%    |
| KingDian                    | 4         | 7      | 0.2%    |
| ExcelStor                   | 4         | 4      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                   | 33        | 1.57%   |
| Kingston SA400S37120G 120GB SSD                   | 26        | 1.24%   |
| Unknown MMC Card  32GB                            | 24        | 1.14%   |
| Toshiba MQ01ABD100 1TB                            | 19        | 0.91%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 19        | 0.91%   |
| Kingston SV300S37A120G 120GB SSD                  | 19        | 0.91%   |
| HGST HTS721010A9E630 1TB                          | 19        | 0.91%   |
| Seagate ST1000DM010-2EP102 1TB                    | 15        | 0.71%   |
| Unknown MMC64G  64GB                              | 14        | 0.67%   |
| Unknown MMC Card  64GB                            | 14        | 0.67%   |
| Seagate ST500LT012-1DG142 500GB                   | 14        | 0.67%   |
| Samsung SSD 850 EVO 250GB                         | 14        | 0.67%   |
| Kingston SA400S37480G 480GB SSD                   | 14        | 0.67%   |
| Crucial CT240M500SSD1 240GB                       | 14        | 0.67%   |
| Toshiba MQ01ABF050 500GB                          | 13        | 0.62%   |
| Seagate ST1000LM035-1RK172 970GB                  | 13        | 0.62%   |
| Samsung SSD 860 EVO 500GB                         | 13        | 0.62%   |
| Kingston SV300S37A240G 240GB SSD                  | 13        | 0.62%   |
| Seagate ST9500325AS 500GB                         | 12        | 0.57%   |
| Samsung SSD 850 EVO 500GB                         | 11        | 0.52%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                  | 10        | 0.48%   |
| Seagate ST3500418AS 500GB                         | 10        | 0.48%   |
| SanDisk NVMe SSD Drive 512GB                      | 10        | 0.48%   |
| Samsung NVMe SSD Drive 512GB                      | 10        | 0.48%   |
| Crucial CT240BX500SSD1 240GB                      | 10        | 0.48%   |
| Samsung SSD 840 EVO 250GB                         | 9         | 0.43%   |
| Samsung NVMe SSD Drive 500GB                      | 9         | 0.43%   |
| Crucial CT500MX500SSD1 500GB                      | 9         | 0.43%   |
| Toshiba HDWD110 1TB                               | 8         | 0.38%   |
| Seagate Expansion 4TB                             | 8         | 0.38%   |
| SanDisk NVMe SSD Drive 256GB                      | 8         | 0.38%   |
| Samsung NVMe SSD Drive 256GB                      | 8         | 0.38%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 8         | 0.38%   |
| Kingston SUV400S37240G 240GB SSD                  | 8         | 0.38%   |
| WDC WD3200BEVT-22ZCT0 320GB                       | 7         | 0.33%   |
| Toshiba TR200 240GB SSD                           | 7         | 0.33%   |
| Toshiba MQ04ABF100 1TB                            | 7         | 0.33%   |
| SK hynix NVMe SSD Drive 256GB                     | 7         | 0.33%   |
| Seagate ST2000DM008-2FR102 2TB                    | 7         | 0.33%   |
| Samsung SSD 860 QVO 1TB                           | 7         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 233       | 372    | 29.05%  |
| WDC                 | 204       | 316    | 25.44%  |
| Toshiba             | 132       | 209    | 16.46%  |
| Hitachi             | 74        | 85     | 9.23%   |
| Samsung Electronics | 57        | 79     | 7.11%   |
| HGST                | 42        | 57     | 5.24%   |
| Fujitsu             | 20        | 21     | 2.49%   |
| Maxtor              | 17        | 24     | 2.12%   |
| JMicron Technology  | 5         | 5      | 0.62%   |
| ExcelStor           | 4         | 4      | 0.5%    |
| Apple               | 3         | 3      | 0.37%   |
| MSFT                | 2         | 12     | 0.25%   |
| Dell                | 2         | 4      | 0.25%   |
| ASMedia             | 2         | 3      | 0.25%   |
| USB3.0              | 1         | 1      | 0.12%   |
| Unknown             | 1         | 1      | 0.12%   |
| Quantum             | 1         | 1      | 0.12%   |
| HPE                 | 1         | 4      | 0.12%   |
| Hewlett-Packard     | 1         | 2      | 0.12%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 157       | 200    | 23.57%  |
| Samsung Electronics | 128       | 175    | 19.22%  |
| Crucial             | 74        | 97     | 11.11%  |
| SanDisk             | 46        | 55     | 6.91%   |
| WDC                 | 34        | 52     | 5.11%   |
| Toshiba             | 28        | 37     | 4.2%    |
| GOODRAM             | 16        | 19     | 2.4%    |
| Intel               | 12        | 15     | 1.8%    |
| S3+                 | 10        | 19     | 1.5%    |
| China               | 10        | 11     | 1.5%    |
| BlueRay             | 10        | 11     | 1.5%    |
| Apple               | 10        | 10     | 1.5%    |
| A-DATA Technology   | 10        | 10     | 1.5%    |
| PNY                 | 9         | 13     | 1.35%   |
| SK hynix            | 8         | 8      | 1.2%    |
| Micron Technology   | 7         | 10     | 1.05%   |
| Emtec               | 7         | 8      | 1.05%   |
| Transcend           | 6         | 7      | 0.9%    |
| Hewlett-Packard     | 6         | 6      | 0.9%    |
| Team                | 5         | 6      | 0.75%   |
| OCZ                 | 5         | 5      | 0.75%   |
| LITEON              | 5         | 6      | 0.75%   |
| KIOXIA-EXCERIA      | 5         | 5      | 0.75%   |
| Unknown             | 4         | 4      | 0.6%    |
| Seagate             | 4         | 6      | 0.6%    |
| Maxtor              | 4         | 11     | 0.6%    |
| KingDian            | 4         | 7      | 0.6%    |
| Vaseky              | 3         | 3      | 0.45%   |
| Netac               | 3         | 3      | 0.45%   |
| Gigabyte Technology | 3         | 3      | 0.45%   |
| 2-Power             | 3         | 4      | 0.45%   |
| USB                 | 2         | 2      | 0.3%    |
| TCSUNBOW            | 2         | 2      | 0.3%    |
| Unknown             | 2         | 2      | 0.3%    |
| Zheino              | 1         | 2      | 0.15%   |
| XrayDisk            | 1         | 2      | 0.15%   |
| Verbatim            | 1         | 1      | 0.15%   |
| TO Exter            | 1         | 1      | 0.15%   |
| Teclast             | 1         | 1      | 0.15%   |
| TEAM T25            | 1         | 1      | 0.15%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 689       | 1203   | 39.01%  |
| SSD     | 594       | 858    | 33.64%  |
| NVMe    | 376       | 552    | 21.29%  |
| MMC     | 86        | 125    | 4.87%   |
| Unknown | 21        | 24     | 1.19%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1056      | 2019   | 67.18%  |
| NVMe | 376       | 549    | 23.92%  |
| MMC  | 86        | 125    | 5.47%   |
| SAS  | 54        | 69     | 3.44%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 857       | 1349   | 67.53%  |
| 0.51-1.0   | 306       | 459    | 24.11%  |
| 1.01-2.0   | 55        | 84     | 4.33%   |
| 3.01-4.0   | 17        | 35     | 1.34%   |
| 4.01-10.0  | 16        | 24     | 1.26%   |
| 2.01-3.0   | 15        | 21     | 1.18%   |
| 10.01-20.0 | 2         | 88     | 0.16%   |
| 0          | 1         | 1      | 0.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 426       | 28.63%  |
| 251-500        | 341       | 22.92%  |
| 501-1000       | 190       | 12.77%  |
| 51-100         | 127       | 8.53%   |
| 1-20           | 115       | 7.73%   |
| 1001-2000      | 93        | 6.25%   |
| 21-50          | 70        | 4.7%    |
| More than 3000 | 51        | 3.43%   |
| Unknown        | 38        | 2.55%   |
| 2001-3000      | 37        | 2.49%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 635       | 41.31%  |
| 21-50          | 286       | 18.61%  |
| 101-250        | 175       | 11.39%  |
| 51-100         | 161       | 10.47%  |
| 251-500        | 100       | 6.51%   |
| 501-1000       | 63        | 4.1%    |
| 1001-2000      | 49        | 3.19%   |
| Unknown        | 38        | 2.47%   |
| More than 3000 | 17        | 1.11%   |
| 2001-3000      | 13        | 0.85%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Crucial CT240M500SSD1 240GB        | 13        | 13     | 9.85%   |
| Kingston SV300S37A120G 120GB SSD   | 6         | 6      | 4.55%   |
| Seagate ST9500325AS 500GB          | 3         | 3      | 2.27%   |
| Seagate ST3500418AS 500GB          | 3         | 3      | 2.27%   |
| WDC WD800JD-60LSA0 80GB            | 2         | 2      | 1.52%   |
| WDC WD3200AAJS-00L7A0 320GB        | 2         | 2      | 1.52%   |
| Toshiba MK2552GSX 250GB            | 2         | 2      | 1.52%   |
| Seagate ST500LT012-1DG142 500GB    | 2         | 2      | 1.52%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2         | 2      | 1.52%   |
| Samsung Electronics HD252HJ 250GB  | 2         | 2      | 1.52%   |
| Kingston SV300S37A240G 240GB SSD   | 2         | 2      | 1.52%   |
| Kingston SUV400S37240G 240GB SSD   | 2         | 2      | 1.52%   |
| Hitachi HTS545050A7E380 500GB      | 2         | 2      | 1.52%   |
| HGST HTS721010A9E630 1TB           | 2         | 2      | 1.52%   |
| WDC WD6400AADS-00M2B0 640GB        | 1         | 1      | 0.76%   |
| WDC WD5000LPCX-60VHAT0 500GB       | 1         | 1      | 0.76%   |
| WDC WD5000BPVT-80HXZT1 500GB       | 1         | 1      | 0.76%   |
| WDC WD5000BPVT-22HXZT1 500GB       | 1         | 1      | 0.76%   |
| WDC WD5000AZRX-00A3KB0 500GB       | 1         | 1      | 0.76%   |
| WDC WD5000AAKS-00V1A0 500GB        | 1         | 1      | 0.76%   |
| WDC WD5000AAKS-00A7B0 500GB        | 1         | 4      | 0.76%   |
| WDC WD40EFRX-68WT0N0 4TB           | 1         | 2      | 0.76%   |
| WDC WD3200BEVT-22A23T0 320GB       | 1         | 1      | 0.76%   |
| WDC WD3200AAJS-00B4A0 320GB        | 1         | 1      | 0.76%   |
| WDC WD30EZRS-11J99B1 3TB           | 1         | 1      | 0.76%   |
| WDC WD2500JS-40TGB0 250GB          | 1         | 1      | 0.76%   |
| WDC WD20EARS-00MVWB0 2TB           | 1         | 1      | 0.76%   |
| WDC WD10JPVT-22A1YT0 1TB           | 1         | 1      | 0.76%   |
| WDC WD10EZRZ-00Z5HB0 1TB           | 1         | 1      | 0.76%   |
| WDC WD10EZEX-00BN5A0 1TB           | 1         | 1      | 0.76%   |
| WDC WD10EAVS-00D7B1 1TB            | 1         | 1      | 0.76%   |
| WDC WD10EARS-00Y5B1 1TB            | 1         | 1      | 0.76%   |
| WDC WD10EALX-009BA0 1TB            | 1         | 1      | 0.76%   |
| WDC WD10EADS-11M2B1 1TB            | 1         | 1      | 0.76%   |
| WDC WD1002FBYS-02A6B0 1TB          | 1         | 1      | 0.76%   |
| WDC WD1001FALS-00J7B0 1TB          | 1         | 4      | 0.76%   |
| USB 3.1 480GB SSD                  | 1         | 1      | 0.76%   |
| Unknown FM-25S2S-60GBP2 64GB SSD   | 1         | 1      | 0.76%   |
| Toshiba Q300. 240GB SSD            | 1         | 1      | 0.76%   |
| Toshiba MQ01ABF050 500GB           | 1         | 1      | 0.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 26        | 33     | 20.16%  |
| Seagate             | 22        | 25     | 17.05%  |
| Hitachi             | 15        | 15     | 11.63%  |
| Crucial             | 15        | 15     | 11.63%  |
| Kingston            | 11        | 11     | 8.53%   |
| Toshiba             | 10        | 11     | 7.75%   |
| Samsung Electronics | 9         | 11     | 6.98%   |
| Maxtor              | 4         | 7      | 3.1%    |
| SK hynix            | 3         | 3      | 2.33%   |
| HGST                | 2         | 2      | 1.55%   |
| China               | 2         | 2      | 1.55%   |
| USB                 | 1         | 1      | 0.78%   |
| Unknown             | 1         | 1      | 0.78%   |
| SanDisk             | 1         | 1      | 0.78%   |
| Patriot             | 1         | 1      | 0.78%   |
| KingDian            | 1         | 2      | 0.78%   |
| Intel               | 1         | 1      | 0.78%   |
| HP Phison           | 1         | 1      | 0.78%   |
| Fujitsu             | 1         | 1      | 0.78%   |
| Apple               | 1         | 1      | 0.78%   |
| A-DATA Technology   | 1         | 1      | 0.78%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 26        | 33     | 30.23%  |
| Seagate             | 22        | 25     | 25.58%  |
| Hitachi             | 15        | 15     | 17.44%  |
| Toshiba             | 9         | 10     | 10.47%  |
| Samsung Electronics | 6         | 7      | 6.98%   |
| Maxtor              | 4         | 7      | 4.65%   |
| HGST                | 2         | 2      | 2.33%   |
| Fujitsu             | 1         | 1      | 1.16%   |
| Apple               | 1         | 1      | 1.16%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 82        | 101    | 65.6%   |
| SSD  | 41        | 43     | 32.8%   |
| NVMe | 2         | 2      | 1.6%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST3750640NS 752GB | 1         | 1      | 50%     |
| HGST HTS541010B7E610 1TB  | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| HGST    | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 950       | 1897   | 63.12%  |
| Works    | 431       | 717    | 28.64%  |
| Malfunc  | 122       | 146    | 8.11%   |
| Failed   | 2         | 2      | 0.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 927       | 55.51%  |
| AMD                              | 239       | 14.31%  |
| Samsung Electronics              | 125       | 7.49%   |
| SanDisk                          | 74        | 4.43%   |
| Kingston Technology Company      | 29        | 1.74%   |
| Nvidia                           | 25        | 1.5%    |
| KIOXIA                           | 25        | 1.5%    |
| JMicron Technology               | 25        | 1.5%    |
| SK hynix                         | 24        | 1.44%   |
| Toshiba America Info Systems     | 23        | 1.38%   |
| Phison Electronics               | 21        | 1.26%   |
| Micron Technology                | 19        | 1.14%   |
| ASMedia Technology               | 17        | 1.02%   |
| Silicon Integrated Systems [SiS] | 16        | 0.96%   |
| VIA Technologies                 | 13        | 0.78%   |
| Marvell Technology Group         | 13        | 0.78%   |
| Micron/Crucial Technology        | 11        | 0.66%   |
| Union Memory (Shenzhen)          | 6         | 0.36%   |
| Silicon Motion                   | 6         | 0.36%   |
| LSI Logic / Symbios Logic        | 6         | 0.36%   |
| Lite-On Technology               | 5         | 0.3%    |
| Shenzhen Longsys Electronics     | 3         | 0.18%   |
| Hewlett-Packard                  | 3         | 0.18%   |
| ADATA Technology                 | 3         | 0.18%   |
| Solid State Storage Technology   | 2         | 0.12%   |
| Realtek Semiconductor            | 2         | 0.12%   |
| Lenovo                           | 2         | 0.12%   |
| Adaptec                          | 2         | 0.12%   |
| ULi Electronics                  | 1         | 0.06%   |
| Silicon Image                    | 1         | 0.06%   |
| Enmotus                          | 1         | 0.06%   |
| Apple                            | 1         | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 165       | 8.32%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 67        | 3.38%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 66        | 3.33%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 61        | 3.07%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 58        | 2.92%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 54        | 2.72%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 51        | 2.57%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 48        | 2.42%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 47        | 2.37%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 43        | 2.17%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 43        | 2.17%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 42        | 2.12%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 41        | 2.07%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 36        | 1.81%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 28        | 1.41%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 26        | 1.31%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 24        | 1.21%   |
| Samsung NVMe SSD Controller 980                                                         | 23        | 1.16%   |
| AMD 500 Series Chipset SATA Controller                                                  | 23        | 1.16%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 22        | 1.11%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 22        | 1.11%   |
| AMD 400 Series Chipset SATA Controller                                                  | 22        | 1.11%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 21        | 1.06%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 21        | 1.06%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 20        | 1.01%   |
| Micron NVMe Storage Controller                                                          | 19        | 0.96%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 19        | 0.96%   |
| Intel SSD 660P Series                                                                   | 18        | 0.91%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 18        | 0.91%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 17        | 0.86%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 17        | 0.86%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                    | 16        | 0.81%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 16        | 0.81%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 15        | 0.76%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 15        | 0.76%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 15        | 0.76%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 14        | 0.71%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 14        | 0.71%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                             | 13        | 0.66%   |
| Phison E12 NVMe Controller                                                              | 13        | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 966       | 55.84%  |
| NVMe | 378       | 21.85%  |
| IDE  | 287       | 16.59%  |
| RAID | 94        | 5.43%   |
| SCSI | 3         | 0.17%   |
| SAS  | 2         | 0.12%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 1096      | 77.73%  |
| AMD    | 305       | 21.63%  |
| ARM    | 9         | 0.64%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 24        | 1.7%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 21        | 1.49%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 19        | 1.35%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 19        | 1.35%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 16        | 1.13%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 14        | 0.99%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 14        | 0.99%   |
| AMD 3020e with Radeon Graphics                | 14        | 0.99%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 13        | 0.92%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 13        | 0.92%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 12        | 0.85%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 12        | 0.85%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 12        | 0.85%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 11        | 0.78%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 11        | 0.78%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 10        | 0.71%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 10        | 0.71%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 10        | 0.71%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 10        | 0.71%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 9         | 0.64%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 9         | 0.64%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 9         | 0.64%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 9         | 0.64%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 9         | 0.64%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 9         | 0.64%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 9         | 0.64%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 8         | 0.57%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 8         | 0.57%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 8         | 0.57%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 8         | 0.57%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 8         | 0.57%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 8         | 0.57%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 8         | 0.57%   |
| AMD Ryzen 5 3600 6-Core Processor             | 8         | 0.57%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz        | 7         | 0.5%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 7         | 0.5%    |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 7         | 0.5%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 7         | 0.5%    |
| Intel Core i3 CPU M 330 @ 2.13GHz             | 7         | 0.5%    |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 7         | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 275       | 19.48%  |
| Intel Core i5           | 258       | 18.27%  |
| Intel Core i3           | 94        | 6.66%   |
| Intel Core 2 Duo        | 92        | 6.52%   |
| Other                   | 91        | 6.44%   |
| AMD Ryzen 5             | 78        | 5.52%   |
| AMD Ryzen 7             | 64        | 4.53%   |
| Intel Celeron           | 57        | 4.04%   |
| Intel Atom              | 46        | 3.26%   |
| Intel Pentium Dual-Core | 39        | 2.76%   |
| Intel Pentium Dual      | 28        | 1.98%   |
| AMD FX                  | 27        | 1.91%   |
| Intel Xeon              | 26        | 1.84%   |
| Intel Pentium           | 26        | 1.84%   |
| Intel Core 2 Quad       | 22        | 1.56%   |
| Intel Core 2            | 21        | 1.49%   |
| Intel Pentium 4         | 14        | 0.99%   |
| Intel Genuine           | 14        | 0.99%   |
| AMD A4                  | 13        | 0.92%   |
| AMD A6                  | 12        | 0.85%   |
| AMD Ryzen 3             | 11        | 0.78%   |
| AMD A8                  | 10        | 0.71%   |
| AMD Ryzen 9             | 9         | 0.64%   |
| AMD A10                 | 8         | 0.57%   |
| AMD E2                  | 7         | 0.5%    |
| Intel Pentium D         | 6         | 0.42%   |
| Intel Pentium M         | 5         | 0.35%   |
| AMD E                   | 5         | 0.35%   |
| AMD Athlon              | 5         | 0.35%   |
| Intel Core i9           | 3         | 0.21%   |
| AMD Ryzen 7 PRO         | 3         | 0.21%   |
| AMD Athlon II X3        | 3         | 0.21%   |
| AMD Athlon II X2        | 3         | 0.21%   |
| AMD Athlon 64           | 3         | 0.21%   |
| Intel Pentium Gold      | 2         | 0.14%   |
| Intel Core m3           | 2         | 0.14%   |
| Intel Celeron M         | 2         | 0.14%   |
| ARM BCM                 | 2         | 0.14%   |
| AMD Ryzen Threadripper  | 2         | 0.14%   |
| AMD Mobile Sempron      | 2         | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 631       | 44.66%  |
| 4       | 485       | 34.32%  |
| 6       | 116       | 8.21%   |
| 8       | 83        | 5.87%   |
| 1       | 52        | 3.68%   |
| 3       | 14        | 0.99%   |
| 10      | 8         | 0.57%   |
| 12      | 7         | 0.5%    |
| 16      | 6         | 0.42%   |
| Unknown | 5         | 0.35%   |
| 14      | 4         | 0.28%   |
| 36      | 1         | 0.07%   |
| 24      | 1         | 0.07%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1399      | 99.22%  |
| 2       | 7         | 0.5%    |
| Unknown | 4         | 0.28%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 859       | 60.84%  |
| 1       | 548       | 38.81%  |
| Unknown | 5         | 0.35%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1342      | 94.44%  |
| Unknown        | 49        | 3.45%   |
| 32-bit         | 23        | 1.62%   |
| 64-bit         | 7         | 0.49%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 353       | 24.06%  |
| 0x1067a    | 72        | 4.91%   |
| 0x306a9    | 70        | 4.77%   |
| 0x206a7    | 70        | 4.77%   |
| 0x906ea    | 41        | 2.79%   |
| 0x10676    | 40        | 2.73%   |
| 0x806ec    | 38        | 2.59%   |
| 0x306c3    | 36        | 2.45%   |
| 0x806ea    | 34        | 2.32%   |
| 0x6fd      | 34        | 2.32%   |
| 0x506e3    | 29        | 1.98%   |
| 0x806c1    | 27        | 1.84%   |
| 0x40651    | 26        | 1.77%   |
| 0x20655    | 23        | 1.57%   |
| 0x306d4    | 21        | 1.43%   |
| 0x406e3    | 20        | 1.36%   |
| 0x20652    | 19        | 1.3%    |
| 0x30678    | 18        | 1.23%   |
| 0x806eb    | 17        | 1.16%   |
| 0x906e9    | 16        | 1.09%   |
| 0x806e9    | 16        | 1.09%   |
| 0x406c4    | 15        | 1.02%   |
| 0x06000852 | 15        | 1.02%   |
| 0x6fb      | 14        | 0.95%   |
| 0x08200103 | 14        | 0.95%   |
| 0x6f6      | 13        | 0.89%   |
| 0x106e5    | 13        | 0.89%   |
| 0x08701021 | 13        | 0.89%   |
| 0x08108109 | 13        | 0.89%   |
| 0x406c3    | 11        | 0.75%   |
| 0x0a50000c | 11        | 0.75%   |
| 0x0800820d | 11        | 0.75%   |
| 0xa0652    | 10        | 0.68%   |
| 0x08600106 | 9         | 0.61%   |
| 0x08108102 | 9         | 0.61%   |
| 0x106ca    | 8         | 0.55%   |
| 0x08600104 | 8         | 0.55%   |
| 0x07030105 | 8         | 0.55%   |
| 0x906a3    | 7         | 0.48%   |
| 0x706e5    | 6         | 0.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 203       | 14.38%  |
| Penryn           | 139       | 9.84%   |
| Haswell          | 95        | 6.73%   |
| IvyBridge        | 89        | 6.3%    |
| Core             | 87        | 6.16%   |
| SandyBridge      | 85        | 6.02%   |
| Skylake          | 72        | 5.1%    |
| Silvermont       | 60        | 4.25%   |
| Westmere         | 56        | 3.97%   |
| Zen 2            | 49        | 3.47%   |
| Zen+             | 45        | 3.19%   |
| Zen 3            | 40        | 2.83%   |
| Zen              | 38        | 2.69%   |
| TigerLake        | 38        | 2.69%   |
| Unknown          | 31        | 2.2%    |
| Broadwell        | 30        | 2.12%   |
| Piledriver       | 28        | 1.98%   |
| CometLake        | 24        | 1.7%    |
| NetBurst         | 22        | 1.56%   |
| Excavator        | 19        | 1.35%   |
| Bonnell          | 18        | 1.27%   |
| Puma             | 17        | 1.2%    |
| Nehalem          | 16        | 1.13%   |
| K10              | 14        | 0.99%   |
| P6               | 13        | 0.92%   |
| IceLake          | 12        | 0.85%   |
| Jaguar           | 10        | 0.71%   |
| Alderlake Hybrid | 10        | 0.71%   |
| Steamroller      | 9         | 0.64%   |
| K8 Hammer        | 9         | 0.64%   |
| Goldmont plus    | 9         | 0.64%   |
| Bobcat           | 7         | 0.5%    |
| Goldmont         | 6         | 0.42%   |
| K8 & K10 hybrid  | 4         | 0.28%   |
| Tremont          | 3         | 0.21%   |
| Bulldozer        | 3         | 0.21%   |
| K10 Llano        | 2         | 0.14%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 780       | 45.03%  |
| Nvidia                           | 518       | 29.91%  |
| AMD                              | 417       | 24.08%  |
| Silicon Integrated Systems [SiS] | 11        | 0.64%   |
| Matrox Electronics Systems       | 3         | 0.17%   |
| ASPEED Technology                | 3         | 0.17%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 65        | 3.61%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 55        | 3.05%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 42        | 2.33%   |
| Intel UHD Graphics 620                                                                   | 38        | 2.11%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 38        | 2.11%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 35        | 1.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 35        | 1.94%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 34        | 1.89%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 30        | 1.67%   |
| Intel Core Processor Integrated Graphics Controller                                      | 30        | 1.67%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 30        | 1.67%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 30        | 1.67%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 28        | 1.55%   |
| AMD Renoir                                                                               | 27        | 1.5%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 26        | 1.44%   |
| Intel HD Graphics 5500                                                                   | 24        | 1.33%   |
| Intel HD Graphics 530                                                                    | 24        | 1.33%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 24        | 1.33%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 23        | 1.28%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 23        | 1.28%   |
| Intel HD Graphics 620                                                                    | 22        | 1.22%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 21        | 1.17%   |
| Nvidia G86M [GeForce 8600M GS]                                                           | 20        | 1.11%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 19        | 1.05%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 19        | 1.05%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 17        | 0.94%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 16        | 0.89%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 15        | 0.83%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 15        | 0.83%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 14        | 0.78%   |
| Nvidia GP108M [GeForce MX150]                                                            | 13        | 0.72%   |
| Intel HD Graphics 630                                                                    | 13        | 0.72%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 13        | 0.72%   |
| Nvidia GP108M [GeForce MX250]                                                            | 12        | 0.67%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 12        | 0.67%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 12        | 0.67%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 11        | 0.61%   |
| Nvidia GT218 [GeForce 210]                                                               | 11        | 0.61%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 11        | 0.61%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 11        | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 493       | 34.72%  |
| 1 x AMD         | 312       | 21.97%  |
| 1 x Nvidia      | 253       | 17.82%  |
| Intel + Nvidia  | 227       | 15.99%  |
| Intel + AMD     | 47        | 3.31%   |
| AMD + Nvidia    | 32        | 2.25%   |
| 2 x AMD         | 27        | 1.9%    |
| 1 x SiS         | 11        | 0.77%   |
| Other           | 9         | 0.63%   |
| 2 x Nvidia      | 2         | 0.14%   |
| Nvidia + ASPEED | 2         | 0.14%   |
| 1 x Matrox      | 2         | 0.14%   |
| 2 x Intel       | 1         | 0.07%   |
| Nvidia + Matrox | 1         | 0.07%   |
| 1 x ASPEED      | 1         | 0.07%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1117      | 78.06%  |
| Proprietary | 248       | 17.33%  |
| Unknown     | 66        | 4.61%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 753       | 51.9%   |
| 0.01-0.5   | 233       | 16.06%  |
| 1.01-2.0   | 186       | 12.82%  |
| 0.51-1.0   | 125       | 8.61%   |
| 3.01-4.0   | 80        | 5.51%   |
| 7.01-8.0   | 34        | 2.34%   |
| 5.01-6.0   | 27        | 1.86%   |
| 8.01-16.0  | 8         | 0.55%   |
| 2.01-3.0   | 5         | 0.34%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 214       | 14.46%  |
| Samsung Electronics     | 183       | 12.36%  |
| Chimei Innolux          | 146       | 9.86%   |
| LG Display              | 126       | 8.51%   |
| BOE                     | 115       | 7.77%   |
| Goldstar                | 105       | 7.09%   |
| Hewlett-Packard         | 70        | 4.73%   |
| Ancor Communications    | 70        | 4.73%   |
| Dell                    | 40        | 2.7%    |
| Apple                   | 33        | 2.23%   |
| AOC                     | 32        | 2.16%   |
| Chi Mei Optoelectronics | 30        | 2.03%   |
| BenQ                    | 27        | 1.82%   |
| Philips                 | 26        | 1.76%   |
| Lenovo                  | 25        | 1.69%   |
| LG Philips              | 21        | 1.42%   |
| PANDA                   | 18        | 1.22%   |
| Acer                    | 16        | 1.08%   |
| Sharp                   | 15        | 1.01%   |
| Sony                    | 14        | 0.95%   |
| ASUSTek Computer        | 14        | 0.95%   |
| LG Electronics          | 12        | 0.81%   |
| Unknown                 | 11        | 0.74%   |
| MSI                     | 7         | 0.47%   |
| CPT                     | 7         | 0.47%   |
| ViewSonic               | 6         | 0.41%   |
| Seiko/Epson             | 6         | 0.41%   |
| InfoVision              | 6         | 0.41%   |
| Toshiba                 | 4         | 0.27%   |
| HUAWEI                  | 4         | 0.27%   |
| HPN                     | 4         | 0.27%   |
| HannStar                | 4         | 0.27%   |
| Fujitsu Siemens         | 4         | 0.27%   |
| Mi                      | 3         | 0.2%    |
| LGD                     | 3         | 0.2%    |
| Lenovo Group Limited    | 3         | 0.2%    |
| CSO                     | 3         | 0.2%    |
| AVX                     | 3         | 0.2%    |
| ___                     | 2         | 0.14%   |
| Vestel Elektronik       | 2         | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO723C 1366x768 309x173mm 13.9-inch            | 14        | 0.92%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 12        | 0.79%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 9         | 0.59%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 9         | 0.59%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 8         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 8         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 8         | 0.53%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 8         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 6         | 0.39%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 6         | 0.39%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch          | 6         | 0.39%   |
| BOE LCD Monitor BOE0704 1366x768 344x194mm 15.5-inch                     | 6         | 0.39%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                        | 6         | 0.39%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 6         | 0.39%   |
| Ancor Communications VX238 ACI23C1 1920x1080 510x290mm 23.1-inch         | 6         | 0.39%   |
| Ancor Communications ASUS VW193D ACI19D5 1440x900 408x255mm 18.9-inch    | 6         | 0.39%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 5         | 0.33%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 5         | 0.33%   |
| LG Philips LCD Monitor LPLDD00 1280x800 331x207mm 15.4-inch              | 5         | 0.33%   |
| LG Display LCD Monitor LGD045D 1366x768 345x194mm 15.6-inch              | 5         | 0.33%   |
| Goldstar FULL HD GSM5AB9 1920x1080 480x270mm 21.7-inch                   | 5         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 5         | 0.33%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 5         | 0.33%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 5         | 0.33%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 5         | 0.33%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 5         | 0.33%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 5         | 0.33%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch           | 5         | 0.33%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 5         | 0.33%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 5         | 0.33%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch        | 4         | 0.26%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 4         | 0.26%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 4         | 0.26%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 4         | 0.26%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 4         | 0.26%   |
| HUAWEI AD80HW HWV2402 1920x1080 527x296mm 23.8-inch                      | 4         | 0.26%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 4         | 0.26%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                   | 4         | 0.26%   |
| Chimei Innolux LCD Monitor CMN15B7 1366x768 344x194mm 15.5-inch          | 4         | 0.26%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 4         | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 558       | 39.8%   |
| 1366x768 (WXGA)    | 354       | 25.25%  |
| 1280x1024 (SXGA)   | 75        | 5.35%   |
| 3840x2160 (4K)     | 70        | 4.99%   |
| 1280x800 (WXGA)    | 60        | 4.28%   |
| 1600x900 (HD+)     | 41        | 2.92%   |
| 1440x900 (WXGA+)   | 39        | 2.78%   |
| 1680x1050 (WSXGA+) | 37        | 2.64%   |
| 2560x1440 (QHD)    | 34        | 2.43%   |
| 1920x1200 (WUXGA)  | 20        | 1.43%   |
| 2560x1080          | 12        | 0.86%   |
| 1360x768           | 12        | 0.86%   |
| Unknown            | 12        | 0.86%   |
| 1024x768 (XGA)     | 9         | 0.64%   |
| 3440x1440          | 8         | 0.57%   |
| 2160x1440          | 7         | 0.5%    |
| 2560x1600          | 6         | 0.43%   |
| 1024x600           | 6         | 0.43%   |
| 3840x2400          | 4         | 0.29%   |
| 3840x1080          | 4         | 0.29%   |
| 2880x1800          | 4         | 0.29%   |
| 3200x1800 (QHD+)   | 3         | 0.21%   |
| 2288x1287          | 3         | 0.21%   |
| 1400x1050          | 3         | 0.21%   |
| 1152x864           | 3         | 0.21%   |
| 640x480            | 1         | 0.07%   |
| 4560x1080          | 1         | 0.07%   |
| 4480x1600          | 1         | 0.07%   |
| 3840x1100          | 1         | 0.07%   |
| 3520x1080          | 1         | 0.07%   |
| 3360x1080          | 1         | 0.07%   |
| 3360x1050          | 1         | 0.07%   |
| 3280x1080          | 1         | 0.07%   |
| 3240x2160          | 1         | 0.07%   |
| 3000x2000          | 1         | 0.07%   |
| 2944x1080          | 1         | 0.07%   |
| 2880x1620          | 1         | 0.07%   |
| 2736x1824          | 1         | 0.07%   |
| 2726x768           | 1         | 0.07%   |
| 2560x2520          | 1         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 486       | 32.77%  |
| 14      | 126       | 8.5%    |
| 13      | 124       | 8.36%   |
| 21      | 97        | 6.54%   |
| 24      | 94        | 6.34%   |
| 17      | 84        | 5.66%   |
| Unknown | 72        | 4.86%   |
| 23      | 71        | 4.79%   |
| 27      | 69        | 4.65%   |
| 19      | 46        | 3.1%    |
| 18      | 27        | 1.82%   |
| 20      | 22        | 1.48%   |
| 34      | 19        | 1.28%   |
| 12      | 19        | 1.28%   |
| 31      | 17        | 1.15%   |
| 11      | 17        | 1.15%   |
| 22      | 16        | 1.08%   |
| 10      | 13        | 0.88%   |
| 16      | 12        | 0.81%   |
| 84      | 9         | 0.61%   |
| 54      | 6         | 0.4%    |
| 40      | 6         | 0.4%    |
| 25      | 6         | 0.4%    |
| 72      | 5         | 0.34%   |
| 33      | 3         | 0.2%    |
| 32      | 3         | 0.2%    |
| 26      | 3         | 0.2%    |
| 46      | 2         | 0.13%   |
| 28      | 2         | 0.13%   |
| 142     | 1         | 0.07%   |
| 58      | 1         | 0.07%   |
| 48      | 1         | 0.07%   |
| 42      | 1         | 0.07%   |
| 39      | 1         | 0.07%   |
| 36      | 1         | 0.07%   |
| 8       | 1         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 707       | 48.62%  |
| 501-600        | 216       | 14.86%  |
| 401-500        | 179       | 12.31%  |
| 201-300        | 110       | 7.57%   |
| 351-400        | 82        | 5.64%   |
| Unknown        | 72        | 4.95%   |
| 601-700        | 28        | 1.93%   |
| 701-800        | 26        | 1.79%   |
| 1501-2000      | 14        | 0.96%   |
| 1001-1500      | 10        | 0.69%   |
| 801-900        | 7         | 0.48%   |
| More than 2000 | 1         | 0.07%   |
| 101-200        | 1         | 0.07%   |
| 901-1000       | 1         | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 979       | 73.11%  |
| 16/10   | 167       | 12.47%  |
| 5/4     | 65        | 4.85%   |
| Unknown | 64        | 4.78%   |
| 4/3     | 24        | 1.79%   |
| 21/9    | 19        | 1.42%   |
| 3/2     | 15        | 1.12%   |
| 6/5     | 3         | 0.22%   |
| 32/9    | 1         | 0.07%   |
| 3.40    | 1         | 0.07%   |
| 1.00    | 1         | 0.07%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 479       | 32.52%  |
| 201-250        | 234       | 15.89%  |
| 81-90          | 199       | 13.51%  |
| 151-200        | 90        | 6.11%   |
| Unknown        | 72        | 4.89%   |
| 301-350        | 71        | 4.82%   |
| 141-150        | 64        | 4.34%   |
| 71-80          | 50        | 3.39%   |
| 351-500        | 41        | 2.78%   |
| 121-130        | 33        | 2.24%   |
| 251-300        | 27        | 1.83%   |
| More than 1000 | 23        | 1.56%   |
| 61-70          | 18        | 1.22%   |
| 51-60          | 18        | 1.22%   |
| 111-120        | 15        | 1.02%   |
| 41-50          | 13        | 0.88%   |
| 501-1000       | 12        | 0.81%   |
| 131-140        | 9         | 0.61%   |
| 91-100         | 4         | 0.27%   |
| 1-40           | 1         | 0.07%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 460       | 32.15%  |
| 101-120       | 439       | 30.68%  |
| 121-160       | 361       | 25.23%  |
| Unknown       | 72        | 5.03%   |
| 161-240       | 62        | 4.33%   |
| More than 240 | 21        | 1.47%   |
| 1-50          | 16        | 1.12%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1131      | 78.27%  |
| 2     | 201       | 13.91%  |
| 0     | 84        | 5.81%   |
| 3     | 25        | 1.73%   |
| 4     | 4         | 0.28%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 760       | 35.75%  |
| Intel                             | 567       | 26.67%  |
| Qualcomm Atheros                  | 317       | 14.91%  |
| Broadcom                          | 139       | 6.54%   |
| Marvell Technology Group          | 55        | 2.59%   |
| TP-Link                           | 48        | 2.26%   |
| Broadcom Limited                  | 25        | 1.18%   |
| Nvidia                            | 22        | 1.03%   |
| MediaTek                          | 20        | 0.94%   |
| Qualcomm Atheros Communications   | 18        | 0.85%   |
| Silicon Integrated Systems [SiS]  | 16        | 0.75%   |
| Ralink                            | 16        | 0.75%   |
| Ralink Technology                 | 13        | 0.61%   |
| D-Link                            | 9         | 0.42%   |
| ASUSTek Computer                  | 7         | 0.33%   |
| ASIX Electronics                  | 7         | 0.33%   |
| VIA Technologies                  | 5         | 0.24%   |
| Sierra Wireless                   | 5         | 0.24%   |
| Samsung Electronics               | 5         | 0.24%   |
| Lenovo                            | 4         | 0.19%   |
| JMicron Technology                | 4         | 0.19%   |
| Ericsson Business Mobile Networks | 4         | 0.19%   |
| Attansic Technology               | 4         | 0.19%   |
| ICS Advent                        | 3         | 0.14%   |
| Huawei Technologies               | 3         | 0.14%   |
| Hewlett-Packard                   | 3         | 0.14%   |
| Edimax Technology                 | 3         | 0.14%   |
| DisplayLink                       | 3         | 0.14%   |
| D-Link System                     | 3         | 0.14%   |
| TRENDnet                          | 2         | 0.09%   |
| Mellanox Technologies             | 2         | 0.09%   |
| Fibocom                           | 2         | 0.09%   |
| Dresden Elektronik                | 2         | 0.09%   |
| Dell                              | 2         | 0.09%   |
| Belkin Components                 | 2         | 0.09%   |
| ADMtek                            | 2         | 0.09%   |
| Accton Technology                 | 2         | 0.09%   |
| Xiaomi                            | 1         | 0.05%   |
| Toshiba                           | 1         | 0.05%   |
| T & A Mobile Phones               | 1         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 517       | 21.02%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 117       | 4.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 52        | 2.11%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 47        | 1.91%   |
| Intel Wi-Fi 6 AX200                                                     | 41        | 1.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 39        | 1.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 34        | 1.38%   |
| Intel Wireless 8265 / 8275                                              | 33        | 1.34%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 32        | 1.3%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 28        | 1.14%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 28        | 1.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 27        | 1.1%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 26        | 1.06%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 26        | 1.06%   |
| Intel Wi-Fi 6 AX201                                                     | 26        | 1.06%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                    | 25        | 1.02%   |
| Intel Wireless 7265                                                     | 25        | 1.02%   |
| Broadcom BCM43142 802.11b/g/n                                           | 25        | 1.02%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 24        | 0.98%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]         | 23        | 0.93%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 23        | 0.93%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 23        | 0.93%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 22        | 0.89%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 21        | 0.85%   |
| Intel Wireless 7260                                                     | 21        | 0.85%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 21        | 0.85%   |
| Intel Wireless 8260                                                     | 20        | 0.81%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 19        | 0.77%   |
| Realtek RTL8125 2.5GbE Controller                                       | 18        | 0.73%   |
| Intel Wireless 3165                                                     | 18        | 0.73%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 18        | 0.73%   |
| Intel 82579V Gigabit Network Connection                                 | 18        | 0.73%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 16        | 0.65%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 16        | 0.65%   |
| Intel I211 Gigabit Network Connection                                   | 16        | 0.65%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 15        | 0.61%   |
| Qualcomm Atheros AR9271 802.11n                                         | 15        | 0.61%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 15        | 0.61%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 15        | 0.61%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 14        | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 458       | 40%     |
| Qualcomm Atheros                      | 260       | 22.71%  |
| Realtek Semiconductor                 | 184       | 16.07%  |
| Broadcom                              | 96        | 8.38%   |
| TP-Link                               | 26        | 2.27%   |
| MediaTek                              | 19        | 1.66%   |
| Qualcomm Atheros Communications       | 18        | 1.57%   |
| Ralink                                | 16        | 1.4%    |
| Broadcom Limited                      | 15        | 1.31%   |
| Ralink Technology                     | 13        | 1.14%   |
| D-Link                                | 9         | 0.79%   |
| ASUSTek Computer                      | 7         | 0.61%   |
| Sierra Wireless                       | 4         | 0.35%   |
| Marvell Technology Group              | 3         | 0.26%   |
| Edimax Technology                     | 3         | 0.26%   |
| TRENDnet                              | 2         | 0.17%   |
| Fibocom                               | 2         | 0.17%   |
| Dell                                  | 2         | 0.17%   |
| Belkin Components                     | 2         | 0.17%   |
| Sitecom Europe                        | 1         | 0.09%   |
| Microsoft                             | 1         | 0.09%   |
| Micro Star International              | 1         | 0.09%   |
| D-Link System                         | 1         | 0.09%   |
| Accton Technology                     | 1         | 0.09%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 52        | 4.54%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 47        | 4.1%    |
| Intel Wi-Fi 6 AX200                                                     | 41        | 3.58%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 39        | 3.4%    |
| Intel Wireless 8265 / 8275                                              | 33        | 2.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 32        | 2.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 28        | 2.44%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 28        | 2.44%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 26        | 2.27%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 26        | 2.27%   |
| Intel Wi-Fi 6 AX201                                                     | 26        | 2.27%   |
| Intel Wireless 7265                                                     | 25        | 2.18%   |
| Broadcom BCM43142 802.11b/g/n                                           | 25        | 2.18%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 24        | 2.09%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 23        | 2.01%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 23        | 2.01%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 22        | 1.92%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 21        | 1.83%   |
| Intel Wireless 7260                                                     | 21        | 1.83%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 21        | 1.83%   |
| Intel Wireless 8260                                                     | 20        | 1.75%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 19        | 1.66%   |
| Intel Wireless 3165                                                     | 18        | 1.57%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 18        | 1.57%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 16        | 1.4%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 16        | 1.4%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 15        | 1.31%   |
| Qualcomm Atheros AR9271 802.11n                                         | 15        | 1.31%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 14        | 1.22%   |
| Intel Wireless 3160                                                     | 13        | 1.13%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 13        | 1.13%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 11        | 0.96%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 11        | 0.96%   |
| Intel Wireless-AC 9260                                                  | 10        | 0.87%   |
| Intel WiFi Link 5100                                                    | 10        | 0.87%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 10        | 0.87%   |
| Intel Centrino Advanced-N 6235                                          | 9         | 0.79%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 8         | 0.7%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 8         | 0.7%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 8         | 0.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 702       | 55.15%  |
| Intel                            | 240       | 18.85%  |
| Qualcomm Atheros                 | 91        | 7.15%   |
| Broadcom                         | 61        | 4.79%   |
| Marvell Technology Group         | 52        | 4.08%   |
| TP-Link                          | 23        | 1.81%   |
| Nvidia                           | 22        | 1.73%   |
| Silicon Integrated Systems [SiS] | 16        | 1.26%   |
| Broadcom Limited                 | 10        | 0.79%   |
| ASIX Electronics                 | 7         | 0.55%   |
| VIA Technologies                 | 5         | 0.39%   |
| Lenovo                           | 4         | 0.31%   |
| JMicron Technology               | 4         | 0.31%   |
| Attansic Technology              | 4         | 0.31%   |
| Samsung Electronics              | 3         | 0.24%   |
| ICS Advent                       | 3         | 0.24%   |
| DisplayLink                      | 3         | 0.24%   |
| Mellanox Technologies            | 2         | 0.16%   |
| Huawei Technologies              | 2         | 0.16%   |
| Hewlett-Packard                  | 2         | 0.16%   |
| D-Link System                    | 2         | 0.16%   |
| ADMtek                           | 2         | 0.16%   |
| Xiaomi                           | 1         | 0.08%   |
| T & A Mobile Phones              | 1         | 0.08%   |
| Standard Microsystems            | 1         | 0.08%   |
| Silicom                          | 1         | 0.08%   |
| Sierra Wireless                  | 1         | 0.08%   |
| Qualcomm                         | 1         | 0.08%   |
| Microchip Technology             | 1         | 0.08%   |
| MediaTek                         | 1         | 0.08%   |
| LSI                              | 1         | 0.08%   |
| Archos                           | 1         | 0.08%   |
| Apple                            | 1         | 0.08%   |
| Allwinner Technology             | 1         | 0.08%   |
| Accton Technology                | 1         | 0.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 517       | 40.08%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 117       | 9.07%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 34        | 2.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 27        | 2.09%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                           | 25        | 1.94%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 23        | 1.78%   |
| Realtek RTL8125 2.5GbE Controller                                              | 18        | 1.4%    |
| Intel 82579V Gigabit Network Connection                                        | 18        | 1.4%    |
| Intel I211 Gigabit Network Connection                                          | 16        | 1.24%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 15        | 1.16%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 15        | 1.16%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 14        | 1.09%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 13        | 1.01%   |
| Intel Ethernet Connection (2) I219-V                                           | 12        | 0.93%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 11        | 0.85%   |
| Intel Ethernet Connection I218-LM                                              | 10        | 0.78%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 9         | 0.7%    |
| Intel Ethernet Connection I217-LM                                              | 9         | 0.7%    |
| Intel 82577LM Gigabit Network Connection                                       | 9         | 0.7%    |
| Intel Ethernet Connection (4) I219-LM                                          | 8         | 0.62%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 8         | 0.62%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 7         | 0.54%   |
| Intel Ethernet Connection (6) I219-V                                           | 7         | 0.54%   |
| Intel Ethernet Connection (4) I219-V                                           | 7         | 0.54%   |
| Intel Ethernet Connection (2) I218-V                                           | 7         | 0.54%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 7         | 0.54%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 6         | 0.47%   |
| Nvidia MCP79 Ethernet                                                          | 6         | 0.47%   |
| Nvidia MCP61 Ethernet                                                          | 6         | 0.47%   |
| Intel Ethernet Connection I219-LM                                              | 6         | 0.47%   |
| Intel Ethernet Connection (7) I219-V                                           | 6         | 0.47%   |
| Intel 82567LM Gigabit Network Connection                                       | 6         | 0.47%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 6         | 0.47%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 5         | 0.39%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 5         | 0.39%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 5         | 0.39%   |
| Intel Ethernet Connection (2) I219-LM                                          | 5         | 0.39%   |
| Intel Ethernet Connection (14) I219-V                                          | 5         | 0.39%   |
| Intel Ethernet Connection (10) I219-V                                          | 5         | 0.39%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 5         | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1223      | 52.11%  |
| WiFi     | 1100      | 46.87%  |
| Modem    | 22        | 0.94%   |
| Unknown  | 2         | 0.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 858       | 58.25%  |
| Ethernet | 614       | 41.68%  |
| Modem    | 1         | 0.07%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 808       | 57.14%  |
| 1     | 556       | 39.32%  |
| 0     | 30        | 2.12%   |
| 3     | 12        | 0.85%   |
| 6     | 3         | 0.21%   |
| 10    | 2         | 0.14%   |
| 5     | 2         | 0.14%   |
| 4     | 1         | 0.07%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1084      | 75.12%  |
| Yes  | 359       | 24.88%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 327       | 40.47%  |
| Realtek Semiconductor           | 87        | 10.77%  |
| Qualcomm Atheros Communications | 58        | 7.18%   |
| IMC Networks                    | 54        | 6.68%   |
| Lite-On Technology              | 42        | 5.2%    |
| Foxconn / Hon Hai               | 40        | 4.95%   |
| Cambridge Silicon Radio         | 36        | 4.46%   |
| Broadcom                        | 34        | 4.21%   |
| Apple                           | 32        | 3.96%   |
| ASUSTek Computer                | 28        | 3.47%   |
| Toshiba                         | 18        | 2.23%   |
| Hewlett-Packard                 | 14        | 1.73%   |
| Realtek                         | 9         | 1.11%   |
| Dell                            | 9         | 1.11%   |
| Ralink                          | 5         | 0.62%   |
| Alps Electric                   | 4         | 0.5%    |
| TP-Link                         | 2         | 0.25%   |
| Ralink Technology               | 2         | 0.25%   |
| Marvell Semiconductor           | 2         | 0.25%   |
| Belkin Components               | 2         | 0.25%   |
| MediaTek                        | 1         | 0.12%   |
| Foxconn International           | 1         | 0.12%   |
| Chicony Electronics             | 1         | 0.12%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 128       | 15.84%  |
| Realtek Bluetooth Radio                                                             | 61        | 7.55%   |
| Intel AX201 Bluetooth                                                               | 57        | 7.05%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 56        | 6.93%   |
| Intel AX200 Bluetooth                                                               | 42        | 5.2%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 36        | 4.46%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 33        | 4.08%   |
| IMC Networks Bluetooth Device                                                       | 29        | 3.59%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 16        | 1.98%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 16        | 1.98%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 14        | 1.73%   |
| Apple Bluetooth Host Controller                                                     | 13        | 1.61%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 12        | 1.49%   |
| IMC Networks Bluetooth Radio                                                        | 12        | 1.49%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 11        | 1.36%   |
| Lite-On Bluetooth Device                                                            | 10        | 1.24%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 10        | 1.24%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 10        | 1.24%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 10        | 1.24%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 10        | 1.24%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 10        | 1.24%   |
| Apple Bluetooth USB Host Controller                                                 | 10        | 1.24%   |
| Realtek 802.11ac WLAN Adapter                                                       | 9         | 1.11%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 8         | 0.99%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 7         | 0.87%   |
| Intel Bluetooth Device                                                              | 7         | 0.87%   |
| IMC Networks Wireless_Device                                                        | 7         | 0.87%   |
| Realtek RTL8821A Bluetooth                                                          | 5         | 0.62%   |
| Ralink RT3290 Bluetooth                                                             | 5         | 0.62%   |
| Lite-On BCM43142A0                                                                  | 5         | 0.62%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 5         | 0.62%   |
| Dell DW375 Bluetooth Module                                                         | 5         | 0.62%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 5         | 0.62%   |
| Toshiba Integrated Bluetooth HCI                                                    | 4         | 0.5%    |
| Toshiba Askey Bluetooth Module                                                      | 4         | 0.5%    |
| Foxconn / Hon Hai BCM43142A0 broadcom bluetooth                                     | 4         | 0.5%    |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 4         | 0.5%    |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                                               | 4         | 0.5%    |
| ASUS ASUS USB-BT500                                                                 | 4         | 0.5%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 4         | 0.5%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1015      | 53.68%  |
| AMD                                  | 401       | 21.21%  |
| Nvidia                               | 290       | 15.34%  |
| C-Media Electronics                  | 23        | 1.22%   |
| Creative Labs                        | 20        | 1.06%   |
| Silicon Integrated Systems [SiS]     | 16        | 0.85%   |
| Logitech                             | 11        | 0.58%   |
| Kingston Technology                  | 10        | 0.53%   |
| JMTek                                | 10        | 0.53%   |
| Razer USA                            | 8         | 0.42%   |
| Realtek Semiconductor                | 7         | 0.37%   |
| Texas Instruments                    | 6         | 0.32%   |
| Plantronics                          | 6         | 0.32%   |
| Hewlett-Packard                      | 5         | 0.26%   |
| GN Netcom                            | 5         | 0.26%   |
| Creative Technology                  | 4         | 0.21%   |
| ASUSTek Computer                     | 4         | 0.21%   |
| Lenovo                               | 3         | 0.16%   |
| Generalplus Technology               | 3         | 0.16%   |
| Focusrite-Novation                   | 3         | 0.16%   |
| VIA Technologies                     | 2         | 0.11%   |
| SteelSeries ApS                      | 2         | 0.11%   |
| Micro Star International             | 2         | 0.11%   |
| EGO SYStems                          | 2         | 0.11%   |
| DSEA A/S                             | 2         | 0.11%   |
| Corsair                              | 2         | 0.11%   |
| Apple                                | 2         | 0.11%   |
| XMOS                                 | 1         | 0.05%   |
| WinChipHead                          | 1         | 0.05%   |
| ULi Electronics                      | 1         | 0.05%   |
| Turtle Beach                         | 1         | 0.05%   |
| Trust                                | 1         | 0.05%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.05%   |
| Sony                                 | 1         | 0.05%   |
| Silicon Motion                       | 1         | 0.05%   |
| Sennheiser Communications            | 1         | 0.05%   |
| Samsung Electronics                  | 1         | 0.05%   |
| Samson Technologies                  | 1         | 0.05%   |
| Philips (or NXP)                     | 1         | 0.05%   |
| Microchip Technology                 | 1         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 119       | 5.38%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 93        | 4.2%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 89        | 4.02%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 78        | 3.52%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 73        | 3.3%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 69        | 3.12%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 68        | 3.07%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 62        | 2.8%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 53        | 2.39%   |
| Intel Cannon Lake PCH cAVS                                                                        | 52        | 2.35%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 47        | 2.12%   |
| AMD FCH Azalia Controller                                                                         | 45        | 2.03%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 44        | 1.99%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 42        | 1.9%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 38        | 1.72%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 38        | 1.72%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 38        | 1.72%   |
| Intel 8 Series HD Audio Controller                                                                | 37        | 1.67%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 35        | 1.58%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 34        | 1.54%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 34        | 1.54%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 34        | 1.54%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 34        | 1.54%   |
| AMD Kabini HDMI/DP Audio                                                                          | 33        | 1.49%   |
| Intel Broadwell-U Audio Controller                                                                | 29        | 1.31%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 28        | 1.27%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 28        | 1.27%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 28        | 1.27%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 27        | 1.22%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 24        | 1.08%   |
| Nvidia High Definition Audio Controller                                                           | 22        | 0.99%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 20        | 0.9%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 19        | 0.86%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 19        | 0.86%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 17        | 0.77%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 17        | 0.77%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 15        | 0.68%   |
| Intel Comet Lake PCH cAVS                                                                         | 15        | 0.68%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 15        | 0.68%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 15        | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 183       | 24.4%   |
| SK hynix            | 141       | 18.8%   |
| Unknown             | 111       | 14.8%   |
| Kingston            | 95        | 12.67%  |
| Micron Technology   | 58        | 7.73%   |
| G.Skill             | 40        | 5.33%   |
| Crucial             | 25        | 3.33%   |
| Corsair             | 23        | 3.07%   |
| Ramaxel Technology  | 14        | 1.87%   |
| A-DATA Technology   | 9         | 1.2%    |
| Team                | 8         | 1.07%   |
| Elpida              | 8         | 1.07%   |
| Nanya Technology    | 6         | 0.8%    |
| Transcend           | 4         | 0.53%   |
| Unknown (ABCD)      | 3         | 0.4%    |
| Unknown             | 3         | 0.4%    |
| Apacer              | 2         | 0.27%   |
| Unigen              | 1         | 0.13%   |
| Unifosa             | 1         | 0.13%   |
| Toshiba             | 1         | 0.13%   |
| Teikon              | 1         | 0.13%   |
| Silicon Power       | 1         | 0.13%   |
| PUSKILL             | 1         | 0.13%   |
| Patriot             | 1         | 0.13%   |
| Netlist             | 1         | 0.13%   |
| Lexar               | 1         | 0.13%   |
| Kimtigo             | 1         | 0.13%   |
| Infineon            | 1         | 0.13%   |
| Hewlett-Packard     | 1         | 0.13%   |
| GOODRAM             | 1         | 0.13%   |
| Goldkey             | 1         | 0.13%   |
| Essencore Limited   | 1         | 0.13%   |
| CSX                 | 1         | 0.13%   |
| 48spaces            | 1         | 0.13%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2                               | 23        | 2.85%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 16        | 1.98%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 14        | 1.73%   |
| Samsung RAM M471A2K43CB1-CTD 16384MB SODIMM DDR4 8400MT/s        | 9         | 1.12%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 9         | 1.12%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 7         | 0.87%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 0.74%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 6         | 0.74%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 0.62%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 5         | 0.62%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 5         | 0.62%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 0.62%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 0.62%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 5         | 0.62%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 5         | 0.62%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.5%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 4         | 0.5%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 0.5%    |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.5%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 0.5%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.5%    |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 4         | 0.5%    |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 4         | 0.5%    |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s             | 4         | 0.5%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 4         | 0.5%    |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 3         | 0.37%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 3         | 0.37%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s                      | 3         | 0.37%   |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 3         | 0.37%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.37%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.37%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.37%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 3         | 0.37%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 3         | 0.37%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 3         | 0.37%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.37%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 3         | 0.37%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.37%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 0.37%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.37%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 295       | 44.97%  |
| DDR3    | 197       | 30.03%  |
| DDR2    | 66        | 10.06%  |
| Unknown | 23        | 3.51%   |
| SDRAM   | 21        | 3.2%    |
| LPDDR4  | 21        | 3.2%    |
| LPDDR3  | 18        | 2.74%   |
| DDR     | 8         | 1.22%   |
| DDR5    | 4         | 0.61%   |
| LPDDR5  | 3         | 0.46%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 398       | 61.04%  |
| DIMM         | 185       | 28.37%  |
| Row Of Chips | 65        | 9.97%   |
| FB-DIMM      | 2         | 0.31%   |
| Chip         | 2         | 0.31%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 8192    | 233       | 32.63%  |
| 4096    | 205       | 28.71%  |
| 2048    | 120       | 16.81%  |
| 16384   | 100       | 14.01%  |
| 1024    | 30        | 4.2%    |
| 32768   | 18        | 2.52%   |
| 512     | 6         | 0.84%   |
| 256     | 1         | 0.14%   |
| Unknown | 1         | 0.14%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 129       | 18.27%  |
| 2667    | 115       | 16.29%  |
| 3200    | 91        | 12.89%  |
| Unknown | 52        | 7.37%   |
| 2400    | 50        | 7.08%   |
| 1333    | 43        | 6.09%   |
| 2133    | 33        | 4.67%   |
| 667     | 25        | 3.54%   |
| 1334    | 20        | 2.83%   |
| 1867    | 13        | 1.84%   |
| 800     | 12        | 1.7%    |
| 8400    | 10        | 1.42%   |
| 4267    | 10        | 1.42%   |
| 3600    | 9         | 1.27%   |
| 1067    | 9         | 1.27%   |
| 3266    | 8         | 1.13%   |
| 3000    | 7         | 0.99%   |
| 533     | 7         | 0.99%   |
| 4199    | 6         | 0.85%   |
| 1866    | 5         | 0.71%   |
| 4800    | 4         | 0.57%   |
| 2666    | 4         | 0.57%   |
| 1066    | 4         | 0.57%   |
| 400     | 4         | 0.57%   |
| 6400    | 3         | 0.42%   |
| 3800    | 3         | 0.42%   |
| 3733    | 3         | 0.42%   |
| 3400    | 3         | 0.42%   |
| 2048    | 3         | 0.42%   |
| 4000    | 2         | 0.28%   |
| 2933    | 2         | 0.28%   |
| 2000    | 2         | 0.28%   |
| 1800    | 2         | 0.28%   |
| 43889   | 1         | 0.14%   |
| 4266    | 1         | 0.14%   |
| 3866    | 1         | 0.14%   |
| 3534    | 1         | 0.14%   |
| 3466    | 1         | 0.14%   |
| 3334    | 1         | 0.14%   |
| 3066    | 1         | 0.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 21        | 63.64%  |
| Seiko Epson            | 3         | 9.09%   |
| Canon                  | 3         | 9.09%   |
| Brother Industries     | 2         | 6.06%   |
| Xerox                  | 1         | 3.03%   |
| Samsung Electronics    | 1         | 3.03%   |
| Panasonic (Matsushita) | 1         | 3.03%   |
| Lexmark International  | 1         | 3.03%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| HP Deskjet 1050 J410                         | 5         | 14.29%  |
| Xerox Phaser 6000B                           | 1         | 2.86%   |
| Seiko Epson XP-225 Series                    | 1         | 2.86%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1         | 2.86%   |
| Seiko Epson AcuLaser C1700                   | 1         | 2.86%   |
| Samsung ML-1640 Series Laser Printer         | 1         | 2.86%   |
| Panasonic (Matsushita) KX-FLB851SP           | 1         | 2.86%   |
| Lexmark International E120(n)                | 1         | 2.86%   |
| HP OfficeJet 5200 series                     | 1         | 2.86%   |
| HP Officejet 4620 series                     | 1         | 2.86%   |
| HP Officejet 4500 G510g-m                    | 1         | 2.86%   |
| HP OfficeJet 3830 series                     | 1         | 2.86%   |
| HP LaserJet Professional P1102w              | 1         | 2.86%   |
| HP LaserJet M14-M17                          | 1         | 2.86%   |
| HP ENVY 6000 series                          | 1         | 2.86%   |
| HP ENVY 4520 series                          | 1         | 2.86%   |
| HP DeskJet F4100 Printer series              | 1         | 2.86%   |
| HP DeskJet F300 series                       | 1         | 2.86%   |
| HP DeskJet F2492 All-in-One                  | 1         | 2.86%   |
| HP DeskJet 930c                              | 1         | 2.86%   |
| HP DeskJet 3630 series                       | 1         | 2.86%   |
| HP Deskjet 3050A                             | 1         | 2.86%   |
| HP Deskjet 3050 J610 series                  | 1         | 2.86%   |
| HP DeskJet 2700 series                       | 1         | 2.86%   |
| HP DeskJet 2130 series                       | 1         | 2.86%   |
| Canon TS6300 series                          | 1         | 2.86%   |
| Canon PIXMA TS6250                           | 1         | 2.86%   |
| Canon PIXMA MG2900 Series                    | 1         | 2.86%   |
| Canon LBP6200                                | 1         | 2.86%   |
| Brother DCP-L3550CDW series                  | 1         | 2.86%   |
| Brother DCP-1610W                            | 1         | 2.86%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Mustek Systems  | 4         | 44.44%  |
| Canon           | 3         | 33.33%  |
| Seiko Epson     | 1         | 11.11%  |
| Hewlett-Packard | 1         | 11.11%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Mustek Systems ScanExpress 1200 UB    | 3         | 33.33%  |
| Seiko Epson GT-X770 [Perfection V500] | 1         | 11.11%  |
| Mustek Systems BearPaw 2448 CU Pro    | 1         | 11.11%  |
| HP ScanJet 5300c/5370c                | 1         | 11.11%  |
| Canon CanoScan N670U/N676U/LiDE 20    | 1         | 11.11%  |
| Canon CanoScan LiDE 110               | 1         | 11.11%  |
| Canon CanoScan 4400F                  | 1         | 11.11%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 236       | 24.92%  |
| IMC Networks                           | 115       | 12.14%  |
| Realtek Semiconductor                  | 72        | 7.6%    |
| Suyin                                  | 46        | 4.86%   |
| Microdia                               | 42        | 4.44%   |
| Quanta                                 | 41        | 4.33%   |
| Bison Electronics                      | 33        | 3.48%   |
| Ricoh                                  | 31        | 3.27%   |
| Acer                                   | 31        | 3.27%   |
| Logitech                               | 30        | 3.17%   |
| Cheng Uei Precision Industry (Foxlink) | 29        | 3.06%   |
| Sunplus Innovation Technology          | 28        | 2.96%   |
| Syntek                                 | 24        | 2.53%   |
| Lite-On Technology                     | 24        | 2.53%   |
| Apple                                  | 24        | 2.53%   |
| Microsoft                              | 16        | 1.69%   |
| Luxvisions Innotech Limited            | 12        | 1.27%   |
| Creative Technology                    | 12        | 1.27%   |
| Silicon Motion                         | 10        | 1.06%   |
| Hewlett-Packard                        | 9         | 0.95%   |
| Alcor Micro                            | 8         | 0.84%   |
| Z-Star Microelectronics                | 7         | 0.74%   |
| Lenovo                                 | 7         | 0.74%   |
| Importek                               | 7         | 0.74%   |
| Generalplus Technology                 | 7         | 0.74%   |
| Samsung Electronics                    | 6         | 0.63%   |
| Cubeternet                             | 4         | 0.42%   |
| WaveRider Communications               | 3         | 0.32%   |
| Sonix Technology                       | 3         | 0.32%   |
| Aveo Technology                        | 3         | 0.32%   |
| ALi                                    | 3         | 0.32%   |
| Primax Electronics                     | 2         | 0.21%   |
| Philips (or NXP)                       | 2         | 0.21%   |
| Jieli Technology                       | 2         | 0.21%   |
| DigiTech                               | 2         | 0.21%   |
| Y Media                                | 1         | 0.11%   |
| Xiaomi                                 | 1         | 0.11%   |
| Trust                                  | 1         | 0.11%   |
| Razer USA                              | 1         | 0.11%   |
| OmniVision Technologies                | 1         | 0.11%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                   | 33        | 3.47%   |
| Chicony Integrated Camera                           | 31        | 3.26%   |
| Chicony HD Webcam                                   | 24        | 2.52%   |
| Ricoh Visual Communication Camera VGP-VCC8 [R5U870] | 21        | 2.21%   |
| IMC Networks Integrated Camera                      | 21        | 2.21%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 18        | 1.89%   |
| Chicony USB2.0 VGA UVC WebCam                       | 16        | 1.68%   |
| Realtek EasyCamera                                  | 14        | 1.47%   |
| Chicony USB 2.0 Camera                              | 13        | 1.37%   |
| Chicony CNF9055 Toshiba Webcam                      | 13        | 1.37%   |
| Realtek USB Camera                                  | 12        | 1.26%   |
| Microdia Integrated_Webcam_HD                       | 12        | 1.26%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 11        | 1.16%   |
| Chicony TOSHIBA Web Camera - HD                     | 11        | 1.16%   |
| Quanta HP Wide Vision HD Camera                     | 9         | 0.95%   |
| Microsoft LifeCam HD-3000                           | 9         | 0.95%   |
| IMC Networks HD Camera                              | 9         | 0.95%   |
| Acer Integrated Camera                              | 9         | 0.95%   |
| Syntek Integrated Camera                            | 8         | 0.84%   |
| Realtek Integrated_Webcam_HD                        | 8         | 0.84%   |
| Realtek HD WebCam                                   | 8         | 0.84%   |
| Chicony HP Truevision HD                            | 8         | 0.84%   |
| Bison Integrated Camera                             | 8         | 0.84%   |
| Apple Built-in iSight                               | 8         | 0.84%   |
| Suyin USB 2.0 Camera                                | 7         | 0.74%   |
| Sunplus HD WebCam                                   | 7         | 0.74%   |
| Quanta HP TrueVision HD Camera                      | 7         | 0.74%   |
| Microdia Sonix USB 2.0 Camera                       | 7         | 0.74%   |
| Logitech Webcam C270                                | 7         | 0.74%   |
| Lite-On Integrated Camera                           | 7         | 0.74%   |
| IMC Networks ov9734_azurewave_camera                | 7         | 0.74%   |
| HP Webcam HD 2300                                   | 7         | 0.74%   |
| Chicony HP HD Camera                                | 7         | 0.74%   |
| Bison HD Webcam                                     | 7         | 0.74%   |
| Syntek EasyCamera                                   | 6         | 0.63%   |
| Samsung Galaxy series, misc. (MTP mode)             | 6         | 0.63%   |
| Realtek USB2.0 VGA UVC WebCam                       | 6         | 0.63%   |
| Realtek 2SF022                                      | 6         | 0.63%   |
| Generalplus 808 Camera                              | 6         | 0.63%   |
| Chicony VGA Webcam                                  | 6         | 0.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 49        | 34.75%  |
| Validity Sensors                   | 41        | 29.08%  |
| Shenzhen Goodix Technology         | 20        | 14.18%  |
| AuthenTec                          | 11        | 7.8%    |
| Elan Microelectronics              | 7         | 4.96%   |
| Upek                               | 6         | 4.26%   |
| LighTuning Technology              | 4         | 2.84%   |
| STMicroelectronics                 | 2         | 1.42%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.71%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 15        | 10.64%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 10        | 7.09%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 5.67%   |
| Validity Sensors Synaptics WBDI                                            | 5         | 3.55%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 5         | 3.55%   |
| Synaptics UWP WBDI Device                                                  | 5         | 3.55%   |
| AuthenTec AES1600                                                          | 5         | 3.55%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 2.84%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 2.84%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 4         | 2.84%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 2.84%   |
| Synaptics UWP WBDI                                                         | 4         | 2.84%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 4         | 2.84%   |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 2.84%   |
| Elan ELAN:ARM-M4                                                           | 4         | 2.84%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 2.13%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 2.13%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 2.13%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 2.13%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 3         | 2.13%   |
| Synaptics WBDI                                                             | 3         | 2.13%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 2.13%   |
| Elan ELAN:Fingerprint                                                      | 3         | 2.13%   |
| AuthenTec AES2810                                                          | 3         | 2.13%   |
| Validity Sensors VFS491                                                    | 2         | 1.42%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 1.42%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 1.42%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 2         | 1.42%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 1.42%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 2         | 1.42%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 1.42%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 1.42%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 1.42%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 0.71%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.71%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.71%   |
| Synaptics WBDI Device                                                      | 1         | 0.71%   |
| Synaptics  WBDI                                                            | 1         | 0.71%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.71%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 0.71%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 25        | 34.25%  |
| Broadcom              | 18        | 24.66%  |
| Gemalto (was Gemplus) | 7         | 9.59%   |
| O2 Micro              | 6         | 8.22%   |
| Lenovo                | 3         | 4.11%   |
| Bit4id                | 3         | 4.11%   |
| SCM Microsystems      | 2         | 2.74%   |
| Realtek Semiconductor | 2         | 2.74%   |
| Advanced Card Systems | 2         | 2.74%   |
| Yubico.com            | 1         | 1.37%   |
| Upek                  | 1         | 1.37%   |
| Hewlett-Packard       | 1         | 1.37%   |
| Chicony Electronics   | 1         | 1.37%   |
| Cherry                | 1         | 1.37%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 24        | 32.88%  |
| Broadcom BCM5880 Secure Applications Processor                               | 7         | 9.59%   |
| Broadcom 58200                                                               | 7         | 9.59%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 6         | 8.22%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 5         | 6.85%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 4.11%   |
| Broadcom 5880                                                                | 3         | 4.11%   |
| Bit4id miniLector EVO                                                        | 3         | 4.11%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 2.74%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 2.74%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 2         | 2.74%   |
| Yubico.com Yubikey 4 U2F+CCID                                                | 1         | 1.37%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 1.37%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.37%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 1.37%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.37%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 1.37%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 1.37%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 1.37%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 1.37%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1021      | 70.32%  |
| 1     | 335       | 23.07%  |
| 2     | 74        | 5.1%    |
| 3     | 16        | 1.1%    |
| 4     | 5         | 0.34%   |
| 5     | 1         | 0.07%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 145       | 27.67%  |
| Fingerprint reader       | 140       | 26.72%  |
| Net/wireless             | 64        | 12.21%  |
| Chipcard                 | 56        | 10.69%  |
| Multimedia controller    | 43        | 8.21%   |
| Camera                   | 17        | 3.24%   |
| Bluetooth                | 12        | 2.29%   |
| Card reader              | 11        | 2.1%    |
| Storage                  | 7         | 1.34%   |
| Communication controller | 7         | 1.34%   |
| Modem                    | 5         | 0.95%   |
| Network                  | 4         | 0.76%   |
| Net/ethernet             | 4         | 0.76%   |
| Flash memory             | 4         | 0.76%   |
| Unassigned class         | 2         | 0.38%   |
| Sound                    | 2         | 0.38%   |
| Dvb card                 | 1         | 0.19%   |

