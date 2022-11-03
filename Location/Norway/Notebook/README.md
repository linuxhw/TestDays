Linux in Norway - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Norway.

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

Total: 700

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Aspire A114-32              | [036ff9e51f](https://linux-hardware.org/?probe=036ff9e51f) | Nov 02, 2022 |
| Acer          | Aspire A114-32              | [d5d1583252](https://linux-hardware.org/?probe=d5d1583252) | Nov 02, 2022 |
| Dell          | Latitude E7240              | [effafc033d](https://linux-hardware.org/?probe=effafc033d) | Nov 01, 2022 |
| ASUSTek       | K55VD                       | [6e2ff87fad](https://linux-hardware.org/?probe=6e2ff87fad) | Nov 01, 2022 |
| Dell          | Latitude E7240              | [d8ae1a7195](https://linux-hardware.org/?probe=d8ae1a7195) | Nov 01, 2022 |
| MSI           | GF63 Thin 11UD              | [8f48ae7586](https://linux-hardware.org/?probe=8f48ae7586) | Oct 29, 2022 |
| MSI           | GF63 Thin 11UD              | [8f1f41f3b0](https://linux-hardware.org/?probe=8f1f41f3b0) | Oct 29, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [f845ed2866](https://linux-hardware.org/?probe=f845ed2866) | Oct 28, 2022 |
| MSI           | GF63 Thin 11UD              | [e2a6e0f610](https://linux-hardware.org/?probe=e2a6e0f610) | Oct 28, 2022 |
| MSI           | GF63 Thin 11UD              | [9f7121381b](https://linux-hardware.org/?probe=9f7121381b) | Oct 27, 2022 |
| MSI           | GF63 Thin 11UD              | [2b6b8d3854](https://linux-hardware.org/?probe=2b6b8d3854) | Oct 26, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [3375318388](https://linux-hardware.org/?probe=3375318388) | Oct 25, 2022 |
| Dell          | Latitude E7240              | [6966cfc71f](https://linux-hardware.org/?probe=6966cfc71f) | Oct 25, 2022 |
| Dell          | Latitude 5480               | [0b8576ce3b](https://linux-hardware.org/?probe=0b8576ce3b) | Oct 25, 2022 |
| Apple         | MacBookAir6,2               | [c271de3628](https://linux-hardware.org/?probe=c271de3628) | Oct 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [5eeed3a9f0](https://linux-hardware.org/?probe=5eeed3a9f0) | Oct 24, 2022 |
| MSI           | GF63 Thin 11UD              | [ca39605260](https://linux-hardware.org/?probe=ca39605260) | Oct 18, 2022 |
| Lenovo        | IdeaPad 5 Pro 16IAH7 82S... | [dfa3140411](https://linux-hardware.org/?probe=dfa3140411) | Oct 17, 2022 |
| MSI           | GF63 Thin 11UD              | [d522208941](https://linux-hardware.org/?probe=d522208941) | Oct 17, 2022 |
| Lenovo        | ThinkPad T510 43495KG       | [4668319862](https://linux-hardware.org/?probe=4668319862) | Oct 16, 2022 |
| Getac         | V110G3                      | [09cd83f0ec](https://linux-hardware.org/?probe=09cd83f0ec) | Oct 14, 2022 |
| Lenovo        | ThinkPad T510 43495KG       | [dbe29306f4](https://linux-hardware.org/?probe=dbe29306f4) | Oct 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [46b44504df](https://linux-hardware.org/?probe=46b44504df) | Oct 08, 2022 |
| MSI           | GL62 6QD                    | [d97ad417e9](https://linux-hardware.org/?probe=d97ad417e9) | Oct 07, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | [b27c3b70a7](https://linux-hardware.org/?probe=b27c3b70a7) | Oct 07, 2022 |
| Acer          | Aspire A515-57G             | [f8d3a419e6](https://linux-hardware.org/?probe=f8d3a419e6) | Oct 07, 2022 |
| Dell          | Latitude 5400               | [00789b23c6](https://linux-hardware.org/?probe=00789b23c6) | Oct 06, 2022 |
| HP            | ProBook 645 G1              | [a085d5e42c](https://linux-hardware.org/?probe=a085d5e42c) | Oct 06, 2022 |
| Dell          | Latitude 5400               | [14ed107028](https://linux-hardware.org/?probe=14ed107028) | Oct 05, 2022 |
| MSI           | GF63 Thin 11UD              | [25077cf5e8](https://linux-hardware.org/?probe=25077cf5e8) | Oct 04, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [5037913bd4](https://linux-hardware.org/?probe=5037913bd4) | Oct 04, 2022 |
| Dell          | Latitude E7240              | [0a41ea4b4c](https://linux-hardware.org/?probe=0a41ea4b4c) | Oct 04, 2022 |
| MSI           | GF63 Thin 11UD              | [b8237b1bd7](https://linux-hardware.org/?probe=b8237b1bd7) | Oct 04, 2022 |
| Intel Clie... | LAPQC71A                    | [6d7beecaf6](https://linux-hardware.org/?probe=6d7beecaf6) | Sep 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [54bc787611](https://linux-hardware.org/?probe=54bc787611) | Sep 29, 2022 |
| Dell          | XPS 13 9350                 | [23142407b0](https://linux-hardware.org/?probe=23142407b0) | Sep 28, 2022 |
| MSI           | GS66 Stealth 10SGS          | [644efb07cf](https://linux-hardware.org/?probe=644efb07cf) | Sep 27, 2022 |
| Dell          | XPS 15 9520                 | [fab5b34402](https://linux-hardware.org/?probe=fab5b34402) | Sep 25, 2022 |
| Dell          | XPS 15 9500                 | [1095e2f7f0](https://linux-hardware.org/?probe=1095e2f7f0) | Sep 25, 2022 |
| MSI           | GF63 Thin 11UD              | [fac56b0962](https://linux-hardware.org/?probe=fac56b0962) | Sep 24, 2022 |
| HP            | Presario CQ56               | [ed937514cf](https://linux-hardware.org/?probe=ed937514cf) | Sep 23, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | [4dd83a1b80](https://linux-hardware.org/?probe=4dd83a1b80) | Sep 16, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | [80638ed98f](https://linux-hardware.org/?probe=80638ed98f) | Sep 15, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [3196144640](https://linux-hardware.org/?probe=3196144640) | Sep 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [38fa0eaf03](https://linux-hardware.org/?probe=38fa0eaf03) | Sep 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [72c53fd3c8](https://linux-hardware.org/?probe=72c53fd3c8) | Sep 15, 2022 |
| HUAWEI        | KLVL-WXX9                   | [7bc7cbca76](https://linux-hardware.org/?probe=7bc7cbca76) | Sep 12, 2022 |
| Acer          | Aspire 6930G                | [cb054f2964](https://linux-hardware.org/?probe=cb054f2964) | Sep 12, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [e1d128b56a](https://linux-hardware.org/?probe=e1d128b56a) | Sep 12, 2022 |
| HP            | ZBook 15 G5                 | [fe1d0da2fc](https://linux-hardware.org/?probe=fe1d0da2fc) | Sep 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [30488e19df](https://linux-hardware.org/?probe=30488e19df) | Sep 08, 2022 |
| MSI           | Katana GF66 11UE            | [36b2cba297](https://linux-hardware.org/?probe=36b2cba297) | Sep 05, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [5472c45d04](https://linux-hardware.org/?probe=5472c45d04) | Sep 03, 2022 |
| MSI           | GF65 Thin 10SER             | [9438d3a4fe](https://linux-hardware.org/?probe=9438d3a4fe) | Sep 03, 2022 |
| MSI           | GF65 Thin 10SER             | [5344528fa4](https://linux-hardware.org/?probe=5344528fa4) | Sep 03, 2022 |
| Intel Clie... | LAPQC71A                    | [9bc39724f8](https://linux-hardware.org/?probe=9bc39724f8) | Sep 02, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [b6e6d0a261](https://linux-hardware.org/?probe=b6e6d0a261) | Sep 02, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [7277e72eb4](https://linux-hardware.org/?probe=7277e72eb4) | Aug 31, 2022 |
| Notebook      | NLx0MU                      | [90c9b01136](https://linux-hardware.org/?probe=90c9b01136) | Aug 31, 2022 |
| Notebook      | NLx0MU                      | [77d4b4ff99](https://linux-hardware.org/?probe=77d4b4ff99) | Aug 31, 2022 |
| MSI           | GL72 6QF                    | [1ffe55389e](https://linux-hardware.org/?probe=1ffe55389e) | Aug 27, 2022 |
| MSI           | GL72 6QF                    | [46b40c3c67](https://linux-hardware.org/?probe=46b40c3c67) | Aug 27, 2022 |
| HP            | ProBook 430 G8 Notebook ... | [17260bd4fb](https://linux-hardware.org/?probe=17260bd4fb) | Aug 24, 2022 |
| Acer          | Aspire 5742                 | [6692313edb](https://linux-hardware.org/?probe=6692313edb) | Aug 22, 2022 |
| HP            | EliteBook 645 14 inch G9... | [d287893b82](https://linux-hardware.org/?probe=d287893b82) | Aug 22, 2022 |
| Lenovo        | B570e 476022G               | [ad4a4c25d5](https://linux-hardware.org/?probe=ad4a4c25d5) | Aug 22, 2022 |
| Dell          | Latitude E7240              | [4adf6ab444](https://linux-hardware.org/?probe=4adf6ab444) | Aug 22, 2022 |
| Dell          | XPS 13 9350                 | [e663637449](https://linux-hardware.org/?probe=e663637449) | Aug 21, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [2b746c613f](https://linux-hardware.org/?probe=2b746c613f) | Aug 16, 2022 |
| MSI           | GF63 Thin 11UD              | [82bfe63c71](https://linux-hardware.org/?probe=82bfe63c71) | Aug 14, 2022 |
| Acer          | Aspire 6930G                | [c0ba049caf](https://linux-hardware.org/?probe=c0ba049caf) | Aug 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [3dcb75072e](https://linux-hardware.org/?probe=3dcb75072e) | Aug 12, 2022 |
| HP            | Compaq Presario CQ71        | [68c8f97537](https://linux-hardware.org/?probe=68c8f97537) | Aug 11, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | [e2a0bef6d4](https://linux-hardware.org/?probe=e2a0bef6d4) | Aug 10, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | [fc0389fd3e](https://linux-hardware.org/?probe=fc0389fd3e) | Aug 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [4312639df6](https://linux-hardware.org/?probe=4312639df6) | Aug 09, 2022 |
| HP            | EliteBook 820 G1            | [1bdfc2f218](https://linux-hardware.org/?probe=1bdfc2f218) | Aug 09, 2022 |
| Dell          | Latitude E5470              | [8cd7ffad9e](https://linux-hardware.org/?probe=8cd7ffad9e) | Aug 08, 2022 |
| MSI           | GF63 Thin 11UD              | [67e1664484](https://linux-hardware.org/?probe=67e1664484) | Aug 07, 2022 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [6b1d79046a](https://linux-hardware.org/?probe=6b1d79046a) | Aug 06, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | [06da05d12b](https://linux-hardware.org/?probe=06da05d12b) | Aug 03, 2022 |
| Notebook      | NV4XMB,ME,MZ                | [7b369e1cdf](https://linux-hardware.org/?probe=7b369e1cdf) | Aug 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [4bcdc51e89](https://linux-hardware.org/?probe=4bcdc51e89) | Jul 27, 2022 |
| MSI           | GF63 Thin 11UD              | [ce18b4e9ab](https://linux-hardware.org/?probe=ce18b4e9ab) | Jul 26, 2022 |
| Acer          | Aspire 5739G                | [aef89fc83f](https://linux-hardware.org/?probe=aef89fc83f) | Jul 26, 2022 |
| MSI           | GS40 6QE Phantom            | [137d7c8701](https://linux-hardware.org/?probe=137d7c8701) | Jul 26, 2022 |
| MSI           | GS40 6QE Phantom            | [76bd6feebe](https://linux-hardware.org/?probe=76bd6feebe) | Jul 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [37ebea2647](https://linux-hardware.org/?probe=37ebea2647) | Jul 25, 2022 |
| HP            | ProBook 450 G2              | [3e2f9e1e86](https://linux-hardware.org/?probe=3e2f9e1e86) | Jul 25, 2022 |
| Notebook      | NV4XMB,ME,MZ                | [f965008c98](https://linux-hardware.org/?probe=f965008c98) | Jul 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [ca9e042e30](https://linux-hardware.org/?probe=ca9e042e30) | Jul 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [68a78a8ed1](https://linux-hardware.org/?probe=68a78a8ed1) | Jul 18, 2022 |
| Lenovo        | ThinkPad W540 20BG001CMN    | [117f9a585b](https://linux-hardware.org/?probe=117f9a585b) | Jul 17, 2022 |
| Toshiba       | Satellite L500              | [5ac3a7aa95](https://linux-hardware.org/?probe=5ac3a7aa95) | Jul 17, 2022 |
| Lenovo        | ThinkPad W540 20BG001CMN    | [e408c1236c](https://linux-hardware.org/?probe=e408c1236c) | Jul 17, 2022 |
| HP            | ProBook 430 G2              | [0be149d703](https://linux-hardware.org/?probe=0be149d703) | Jul 16, 2022 |
| HUAWEI        | MACH-WX9                    | [76035ea427](https://linux-hardware.org/?probe=76035ea427) | Jul 15, 2022 |
| Dell          | XPS 15 9520                 | [271277c36b](https://linux-hardware.org/?probe=271277c36b) | Jul 14, 2022 |
| MSI           | GF63 Thin 11UD              | [b4cf81df26](https://linux-hardware.org/?probe=b4cf81df26) | Jul 13, 2022 |
| Acer          | Aspire A515-44              | [c0d1086ae8](https://linux-hardware.org/?probe=c0d1086ae8) | Jul 09, 2022 |
| HUAWEI        | MACH-WX9                    | [486d051b71](https://linux-hardware.org/?probe=486d051b71) | Jul 08, 2022 |
| Dell          | Latitude D531               | [008236dd11](https://linux-hardware.org/?probe=008236dd11) | Jul 07, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | [fec0786471](https://linux-hardware.org/?probe=fec0786471) | Jul 06, 2022 |
| MSI           | GF63 Thin 11UD              | [7847c0275c](https://linux-hardware.org/?probe=7847c0275c) | Jul 02, 2022 |
| MSI           | GF63 Thin 11UD              | [325fec2ac6](https://linux-hardware.org/?probe=325fec2ac6) | Jul 01, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [1967dad271](https://linux-hardware.org/?probe=1967dad271) | Jun 22, 2022 |
| Dell          | Latitude E7240              | [1c76f3cdf4](https://linux-hardware.org/?probe=1c76f3cdf4) | Jun 21, 2022 |
| Dell          | Latitude E7240              | [2974c5fa7c](https://linux-hardware.org/?probe=2974c5fa7c) | Jun 21, 2022 |
| HP            | EliteBook 840 G1            | [4a3e29a7c0](https://linux-hardware.org/?probe=4a3e29a7c0) | Jun 20, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [4a1a0294d8](https://linux-hardware.org/?probe=4a1a0294d8) | Jun 18, 2022 |
| Dell          | Latitude E7240              | [2ed64f08f3](https://linux-hardware.org/?probe=2ed64f08f3) | Jun 17, 2022 |
| Dell          | Latitude E7240              | [31340542c2](https://linux-hardware.org/?probe=31340542c2) | Jun 17, 2022 |
| Dell          | Latitude E7240              | [08efb8dcc5](https://linux-hardware.org/?probe=08efb8dcc5) | Jun 17, 2022 |
| Dell          | Latitude E7240              | [b6978a823c](https://linux-hardware.org/?probe=b6978a823c) | Jun 17, 2022 |
| Lenovo        | ThinkPad X220 4286CTO       | [fd2fb2f646](https://linux-hardware.org/?probe=fd2fb2f646) | Jun 14, 2022 |
| HP            | Mini 210-1000               | [8746b5b684](https://linux-hardware.org/?probe=8746b5b684) | Jun 10, 2022 |
| HP            | Mini 210-1000               | [65b65f1319](https://linux-hardware.org/?probe=65b65f1319) | Jun 08, 2022 |
| ASUSTek       | X55U                        | [66e1c7ed1d](https://linux-hardware.org/?probe=66e1c7ed1d) | Jun 06, 2022 |
| Toshiba       | Satellite L500              | [b4b4831c86](https://linux-hardware.org/?probe=b4b4831c86) | Jun 05, 2022 |
| Acer          | Aspire 5739G                | [6f6f16ee08](https://linux-hardware.org/?probe=6f6f16ee08) | May 31, 2022 |
| Notebook      | Multicom Xishan NL50        | [9ffa89c7a9](https://linux-hardware.org/?probe=9ffa89c7a9) | May 31, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [ed28d49715](https://linux-hardware.org/?probe=ed28d49715) | May 30, 2022 |
| Notebook      | Multicom Xishan NL50        | [0c45263f11](https://linux-hardware.org/?probe=0c45263f11) | May 30, 2022 |
| Acer          | Aspire 6930G                | [a07fb7cbcd](https://linux-hardware.org/?probe=a07fb7cbcd) | May 25, 2022 |
| Lenovo        | ThinkPad T490s 20NX0077M... | [cea81a1d63](https://linux-hardware.org/?probe=cea81a1d63) | May 24, 2022 |
| Acer          | Aspire 5739G                | [428631aa4a](https://linux-hardware.org/?probe=428631aa4a) | May 23, 2022 |
| Notebook      | N8xEJEK                     | [5c2c66e8f5](https://linux-hardware.org/?probe=5c2c66e8f5) | May 17, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [48c983a184](https://linux-hardware.org/?probe=48c983a184) | May 15, 2022 |
| Lenovo        | ThinkPad P51 20HJS02H00     | [fc7562c140](https://linux-hardware.org/?probe=fc7562c140) | May 12, 2022 |
| Lenovo        | ThinkPad P51 20HJS02H00     | [810fda94b1](https://linux-hardware.org/?probe=810fda94b1) | May 12, 2022 |
| HP            | ZBook Power 15.6 inch G8... | [c195f80f3c](https://linux-hardware.org/?probe=c195f80f3c) | May 12, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [1b52e22774](https://linux-hardware.org/?probe=1b52e22774) | May 10, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [47b730f9bd](https://linux-hardware.org/?probe=47b730f9bd) | May 10, 2022 |
| Dell          | Latitude E5430 non-vPro     | [2075bfcc02](https://linux-hardware.org/?probe=2075bfcc02) | May 05, 2022 |
| Dell          | Latitude E5430 non-vPro     | [71f8f45765](https://linux-hardware.org/?probe=71f8f45765) | May 05, 2022 |
| HP            | ProBook 4330s               | [7cad0acb2c](https://linux-hardware.org/?probe=7cad0acb2c) | May 04, 2022 |
| HP            | ProBook 4330s               | [ca6474fbfc](https://linux-hardware.org/?probe=ca6474fbfc) | May 04, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [0295d9e820](https://linux-hardware.org/?probe=0295d9e820) | May 04, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFC... | [3835b6bdb8](https://linux-hardware.org/?probe=3835b6bdb8) | May 03, 2022 |
| Apple         | MacBookPro12,1              | [5f68858e66](https://linux-hardware.org/?probe=5f68858e66) | May 01, 2022 |
| HP            | ZBook Firefly 15 inch G8... | [6cdff366fa](https://linux-hardware.org/?probe=6cdff366fa) | Apr 28, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [620718bb9e](https://linux-hardware.org/?probe=620718bb9e) | Apr 26, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [743177a467](https://linux-hardware.org/?probe=743177a467) | Apr 24, 2022 |
| Acer          | Swift SF514-51              | [d6c47a5367](https://linux-hardware.org/?probe=d6c47a5367) | Apr 23, 2022 |
| Dell          | Latitude E6430              | [91bbf4068b](https://linux-hardware.org/?probe=91bbf4068b) | Apr 20, 2022 |
| Google        | Cave                        | [c762019e08](https://linux-hardware.org/?probe=c762019e08) | Apr 18, 2022 |
| Lenovo        | V130-14IKB 81HQ             | [19299bc16d](https://linux-hardware.org/?probe=19299bc16d) | Apr 14, 2022 |
| ASUSTek       | K52Dr                       | [29124147fe](https://linux-hardware.org/?probe=29124147fe) | Apr 14, 2022 |
| Lenovo        | ThinkPad T490s 20NX003UM... | [60dca75a93](https://linux-hardware.org/?probe=60dca75a93) | Apr 14, 2022 |
| HP            | ZBook Power 15.6 inch G8... | [7f83d03bf3](https://linux-hardware.org/?probe=7f83d03bf3) | Apr 13, 2022 |
| HP            | ZBook Power 15.6 inch G8... | [bbcb05781f](https://linux-hardware.org/?probe=bbcb05781f) | Apr 13, 2022 |
| Lenovo        | ThinkPad T460s 20F90044M... | [47498ed4aa](https://linux-hardware.org/?probe=47498ed4aa) | Apr 13, 2022 |
| MSI           | GS66 Stealth 10UH           | [5589b339ed](https://linux-hardware.org/?probe=5589b339ed) | Apr 11, 2022 |
| HP            | EliteBook 840 G4            | [dd511f4bf0](https://linux-hardware.org/?probe=dd511f4bf0) | Apr 09, 2022 |
| Lenovo        | Yoga Slim 7 Carbon 14ACN... | [5328fde624](https://linux-hardware.org/?probe=5328fde624) | Apr 08, 2022 |
| Dell          | Inspiron 5370               | [abc7562fb9](https://linux-hardware.org/?probe=abc7562fb9) | Apr 07, 2022 |
| MSI           | GS66 Stealth 10UH           | [bd6f031bc8](https://linux-hardware.org/?probe=bd6f031bc8) | Apr 06, 2022 |
| Apple         | MacBookPro11,1              | [f41079b495](https://linux-hardware.org/?probe=f41079b495) | Apr 05, 2022 |
| Lenovo        | ThinkPad T520 4243W83       | [79c6231f19](https://linux-hardware.org/?probe=79c6231f19) | Apr 02, 2022 |
| Dell          | Latitude E5430 non-vPro     | [b47f5b30db](https://linux-hardware.org/?probe=b47f5b30db) | Apr 01, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | [ea012026c5](https://linux-hardware.org/?probe=ea012026c5) | Mar 30, 2022 |
| HP            | Laptop 14s-fq0xxx           | [0a68b0e55c](https://linux-hardware.org/?probe=0a68b0e55c) | Mar 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [f4e2b38106](https://linux-hardware.org/?probe=f4e2b38106) | Mar 20, 2022 |
| ASUSTek       | UL50VT                      | [6911af9ce1](https://linux-hardware.org/?probe=6911af9ce1) | Mar 20, 2022 |
| HP            | ZBook Firefly 15 inch G8... | [674a4429c2](https://linux-hardware.org/?probe=674a4429c2) | Mar 19, 2022 |
| ASUSTek       | GL502VMK                    | [f2fedaa3c3](https://linux-hardware.org/?probe=f2fedaa3c3) | Mar 18, 2022 |
| Notebook      | NV4XMB,ME,MZ                | [ce34107bae](https://linux-hardware.org/?probe=ce34107bae) | Mar 14, 2022 |
| Dell          | XPS 13 9310                 | [acef37559c](https://linux-hardware.org/?probe=acef37559c) | Mar 14, 2022 |
| Dell          | XPS 13 9310                 | [884e853e6f](https://linux-hardware.org/?probe=884e853e6f) | Mar 14, 2022 |
| Intel Clie... | LAPQC71A                    | [14108beccf](https://linux-hardware.org/?probe=14108beccf) | Mar 12, 2022 |
| Intel Clie... | LAPQC71A                    | [ee7f4f0b82](https://linux-hardware.org/?probe=ee7f4f0b82) | Mar 12, 2022 |
| Dell          | Latitude 5480               | [d7fe091593](https://linux-hardware.org/?probe=d7fe091593) | Mar 12, 2022 |
| Dell          | Latitude E5450              | [0e4fb3e1fd](https://linux-hardware.org/?probe=0e4fb3e1fd) | Mar 12, 2022 |
| Dell          | Latitude 7480               | [bb03e5e22e](https://linux-hardware.org/?probe=bb03e5e22e) | Mar 11, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [917a6b65a8](https://linux-hardware.org/?probe=917a6b65a8) | Mar 10, 2022 |
| Dell          | Precision M6800             | [239dd5797a](https://linux-hardware.org/?probe=239dd5797a) | Mar 10, 2022 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [3a9118e8bc](https://linux-hardware.org/?probe=3a9118e8bc) | Mar 07, 2022 |
| ASUSTek       | UL50VT                      | [5a711af850](https://linux-hardware.org/?probe=5a711af850) | Mar 07, 2022 |
| Lenovo        | ThinkPad T480 20L60033MX    | [fda7557aa0](https://linux-hardware.org/?probe=fda7557aa0) | Mar 07, 2022 |
| Lenovo        | ThinkPad T400s 2808D9G      | [6a5d0584bd](https://linux-hardware.org/?probe=6a5d0584bd) | Mar 02, 2022 |
| Lenovo        | ThinkPad T460 20FMS1XX00    | [78e82c6674](https://linux-hardware.org/?probe=78e82c6674) | Feb 24, 2022 |
| Dell          | XPS 15 7590                 | [69896e5117](https://linux-hardware.org/?probe=69896e5117) | Feb 23, 2022 |
| HP            | EliteBook 840 G4            | [7bb148611f](https://linux-hardware.org/?probe=7bb148611f) | Feb 23, 2022 |
| Lenovo        | ThinkPad T460s 20F9S1G20... | [6a6c0b0b39](https://linux-hardware.org/?probe=6a6c0b0b39) | Feb 21, 2022 |
| ASUSTek       | UX430UAR                    | [c7cd5ce50d](https://linux-hardware.org/?probe=c7cd5ce50d) | Feb 21, 2022 |
| Lenovo        | ThinkPad Edge E330 3354D... | [0337480978](https://linux-hardware.org/?probe=0337480978) | Feb 17, 2022 |
| HUAWEI        | KLVL-WXX9                   | [34bd2af067](https://linux-hardware.org/?probe=34bd2af067) | Feb 14, 2022 |
| HP            | ProBook 4330s               | [3781146b1f](https://linux-hardware.org/?probe=3781146b1f) | Feb 14, 2022 |
| ASUSTek       | G74Sx                       | [a3709f6df1](https://linux-hardware.org/?probe=a3709f6df1) | Feb 12, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [68d863ab48](https://linux-hardware.org/?probe=68d863ab48) | Feb 10, 2022 |
| Lenovo        | ThinkPad Edge 0301DMG       | [ab580c3edd](https://linux-hardware.org/?probe=ab580c3edd) | Feb 10, 2022 |
| Lenovo        | ThinkPad Edge 0301DMG       | [c11f9d5c6d](https://linux-hardware.org/?probe=c11f9d5c6d) | Feb 10, 2022 |
| Lenovo        | ThinkPad T470s 20HGS0FJ0... | [6dc9215373](https://linux-hardware.org/?probe=6dc9215373) | Feb 07, 2022 |
| Acer          | Swift SF314-511             | [9f7733e6ec](https://linux-hardware.org/?probe=9f7733e6ec) | Feb 03, 2022 |
| Dell          | Latitude E4200              | [35dbab3b2e](https://linux-hardware.org/?probe=35dbab3b2e) | Jan 31, 2022 |
| Toshiba       | Satellite C660D             | [d6498c16bb](https://linux-hardware.org/?probe=d6498c16bb) | Jan 27, 2022 |
| Lenovo        | ThinkPad T520 4243W83       | [698c80468a](https://linux-hardware.org/?probe=698c80468a) | Jan 25, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [29ce7637f6](https://linux-hardware.org/?probe=29ce7637f6) | Jan 23, 2022 |
| HP            | OMEN by Laptop 15-dc1xxx    | [cbf995ff80](https://linux-hardware.org/?probe=cbf995ff80) | Jan 22, 2022 |
| HUAWEI        | KLVL-WXX9                   | [ae399035f5](https://linux-hardware.org/?probe=ae399035f5) | Jan 21, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [634d45ff9e](https://linux-hardware.org/?probe=634d45ff9e) | Jan 21, 2022 |
| Dell          | Latitude 7280               | [6b9dcc88b7](https://linux-hardware.org/?probe=6b9dcc88b7) | Jan 21, 2022 |
| Dell          | Latitude 7280               | [beb9306791](https://linux-hardware.org/?probe=beb9306791) | Jan 21, 2022 |
| Lenovo        | ThinkPad X230 23252EG       | [e236263783](https://linux-hardware.org/?probe=e236263783) | Jan 19, 2022 |
| Lenovo        | G50-30 80G0                 | [5a609ef492](https://linux-hardware.org/?probe=5a609ef492) | Jan 16, 2022 |
| HP            | Laptop 17-cn0xxx            | [5cb4bc2ed8](https://linux-hardware.org/?probe=5cb4bc2ed8) | Jan 14, 2022 |
| Dell          | Precision 7560              | [a58a852902](https://linux-hardware.org/?probe=a58a852902) | Jan 13, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [9fa645342b](https://linux-hardware.org/?probe=9fa645342b) | Jan 12, 2022 |
| HP            | EliteBook 820 G1            | [37dd78dd6e](https://linux-hardware.org/?probe=37dd78dd6e) | Jan 11, 2022 |
| Apple         | MacBookPro9,2               | [831591fe79](https://linux-hardware.org/?probe=831591fe79) | Jan 11, 2022 |
| MSI           | GS66 Stealth 10UH           | [a38abf3dd0](https://linux-hardware.org/?probe=a38abf3dd0) | Jan 10, 2022 |
| Dell          | Latitude 5480               | [c572bd1eac](https://linux-hardware.org/?probe=c572bd1eac) | Jan 08, 2022 |
| Apple         | MacBookPro9,2               | [b5bd2eca7d](https://linux-hardware.org/?probe=b5bd2eca7d) | Jan 07, 2022 |
| HP            | Pavilion dv6000 (GH912EA... | [a41f8d2d74](https://linux-hardware.org/?probe=a41f8d2d74) | Jan 03, 2022 |
| Dell          | Latitude E7440              | [9df6480d3e](https://linux-hardware.org/?probe=9df6480d3e) | Jan 02, 2022 |
| Lenovo        | ThinkPad T410s 2924W79      | [43fe13f2a4](https://linux-hardware.org/?probe=43fe13f2a4) | Dec 30, 2021 |
| Dell          | Latitude 5480               | [e560c10eb8](https://linux-hardware.org/?probe=e560c10eb8) | Dec 29, 2021 |
| Acer          | Aspire E1-572               | [ab9c63e097](https://linux-hardware.org/?probe=ab9c63e097) | Dec 28, 2021 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | [04ebd359f1](https://linux-hardware.org/?probe=04ebd359f1) | Dec 28, 2021 |
| Acer          | Aspire E1-572               | [63f4428f24](https://linux-hardware.org/?probe=63f4428f24) | Dec 28, 2021 |
| Lenovo        | ThinkPad L512 44444WG       | [0f7bd5b933](https://linux-hardware.org/?probe=0f7bd5b933) | Dec 26, 2021 |
| MSI           | GS66 Stealth 10UH           | [6246228e2d](https://linux-hardware.org/?probe=6246228e2d) | Dec 26, 2021 |
| Lenovo        | ThinkPad L512 44444WG       | [113b39ddbc](https://linux-hardware.org/?probe=113b39ddbc) | Dec 25, 2021 |
| HP            | ZBook 15                    | [57cb28cc81](https://linux-hardware.org/?probe=57cb28cc81) | Dec 24, 2021 |
| Dell          | Latitude 5480               | [5c91ed91a8](https://linux-hardware.org/?probe=5c91ed91a8) | Dec 24, 2021 |
| Acer          | Aspire xxxx                 | [13b21c09d2](https://linux-hardware.org/?probe=13b21c09d2) | Dec 23, 2021 |
| Dell          | XPS 15 9500                 | [86789982ba](https://linux-hardware.org/?probe=86789982ba) | Dec 21, 2021 |
| Lenovo        | ThinkPad E580 20KS001EMX    | [366aae1cd6](https://linux-hardware.org/?probe=366aae1cd6) | Dec 18, 2021 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | [3cd4b5c111](https://linux-hardware.org/?probe=3cd4b5c111) | Dec 18, 2021 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | [03115bdd2e](https://linux-hardware.org/?probe=03115bdd2e) | Dec 18, 2021 |
| Lenovo        | ThinkPad T410s 2924W79      | [f26b8b4f98](https://linux-hardware.org/?probe=f26b8b4f98) | Dec 17, 2021 |
| Acer          | Aspire xxxx                 | [dfa568d766](https://linux-hardware.org/?probe=dfa568d766) | Dec 17, 2021 |
| Toshiba       | Satellite L750              | [30ad7918cd](https://linux-hardware.org/?probe=30ad7918cd) | Dec 13, 2021 |
| Acer          | Aspire A114-32              | [dd9fb384ea](https://linux-hardware.org/?probe=dd9fb384ea) | Dec 13, 2021 |
| Lenovo        | ThinkPad L512 44444WG       | [711aa97225](https://linux-hardware.org/?probe=711aa97225) | Dec 13, 2021 |
| HP            | ZBook 15                    | [cb2487cb67](https://linux-hardware.org/?probe=cb2487cb67) | Dec 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [204f77ca68](https://linux-hardware.org/?probe=204f77ca68) | Dec 10, 2021 |
| HP            | ZBook 15                    | [c0d2e24505](https://linux-hardware.org/?probe=c0d2e24505) | Dec 10, 2021 |
| ASUSTek       | N550JV                      | [696dd578ab](https://linux-hardware.org/?probe=696dd578ab) | Dec 08, 2021 |
| HP            | OMEN by Laptop              | [b44117a400](https://linux-hardware.org/?probe=b44117a400) | Dec 06, 2021 |
| Dell          | Inspiron M5030              | [b28a3fe6a7](https://linux-hardware.org/?probe=b28a3fe6a7) | Dec 05, 2021 |
| ASUSTek       | ZenBook UX425EA_BX425EA     | [c579de06b5](https://linux-hardware.org/?probe=c579de06b5) | Dec 03, 2021 |
| Lenovo        | ThinkPad T580 20LAS2BH00    | [e85a481d36](https://linux-hardware.org/?probe=e85a481d36) | Dec 02, 2021 |
| Acer          | Aspire A114-32              | [64005f7018](https://linux-hardware.org/?probe=64005f7018) | Nov 30, 2021 |
| Dell          | Inspiron 15-3552            | [7fbb6be9e3](https://linux-hardware.org/?probe=7fbb6be9e3) | Nov 30, 2021 |
| Acer          | Aspire A114-32              | [a380d2a0c8](https://linux-hardware.org/?probe=a380d2a0c8) | Nov 29, 2021 |
| Acer          | Aspire A315-42              | [a0483c5539](https://linux-hardware.org/?probe=a0483c5539) | Nov 27, 2021 |
| HP            | EliteBook 8460p             | [ca30b13118](https://linux-hardware.org/?probe=ca30b13118) | Nov 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [969dde57b0](https://linux-hardware.org/?probe=969dde57b0) | Nov 22, 2021 |
| Lenovo        | ThinkPad L512 44444WG       | [1d12ea147a](https://linux-hardware.org/?probe=1d12ea147a) | Nov 20, 2021 |
| Dell          | Latitude E7440              | [89fdff42c1](https://linux-hardware.org/?probe=89fdff42c1) | Nov 20, 2021 |
| Acer          | Aspire 5810T                | [c6e0003dcb](https://linux-hardware.org/?probe=c6e0003dcb) | Nov 20, 2021 |
| Acer          | Aspire 5810T                | [6b485f4c9a](https://linux-hardware.org/?probe=6b485f4c9a) | Nov 20, 2021 |
| Acer          | Swift SF514-51              | [07e73dc8ab](https://linux-hardware.org/?probe=07e73dc8ab) | Nov 19, 2021 |
| Lenovo        | ThinkPad T520 42433VG       | [529262c2e4](https://linux-hardware.org/?probe=529262c2e4) | Nov 17, 2021 |
| HP            | ZBook Fury 15 G7 Mobile ... | [6196137046](https://linux-hardware.org/?probe=6196137046) | Nov 17, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [564ef15a99](https://linux-hardware.org/?probe=564ef15a99) | Nov 16, 2021 |
| HP            | ProBook 440 G4              | [f5d53e44ae](https://linux-hardware.org/?probe=f5d53e44ae) | Nov 15, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [bb1201e75c](https://linux-hardware.org/?probe=bb1201e75c) | Nov 06, 2021 |
| Lenovo        | ThinkPad W540 20BHS0NQ00    | [69f4b3d974](https://linux-hardware.org/?probe=69f4b3d974) | Nov 03, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [0b7ae3ebf5](https://linux-hardware.org/?probe=0b7ae3ebf5) | Nov 03, 2021 |
| Dell          | XPS 13 9370                 | [458d3682a5](https://linux-hardware.org/?probe=458d3682a5) | Nov 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [070b533b05](https://linux-hardware.org/?probe=070b533b05) | Nov 02, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [3acc230d6a](https://linux-hardware.org/?probe=3acc230d6a) | Nov 02, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [c88adaac6e](https://linux-hardware.org/?probe=c88adaac6e) | Nov 02, 2021 |
| Acer          | Aspire 5739G                | [9366122bdb](https://linux-hardware.org/?probe=9366122bdb) | Nov 01, 2021 |
| Acer          | Aspire 5739G                | [aaf8f33249](https://linux-hardware.org/?probe=aaf8f33249) | Nov 01, 2021 |
| Acer          | Aspire 5739G                | [7979c29593](https://linux-hardware.org/?probe=7979c29593) | Oct 29, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [2eac1bfc4f](https://linux-hardware.org/?probe=2eac1bfc4f) | Oct 24, 2021 |
| Lenovo        | ThinkPad T450s 20BWS3EG0... | [df466b506d](https://linux-hardware.org/?probe=df466b506d) | Oct 20, 2021 |
| Lenovo        | ThinkPad T450s 20BWS3EG0... | [748d3e56a7](https://linux-hardware.org/?probe=748d3e56a7) | Oct 20, 2021 |
| HP            | EliteBook 820 G1            | [278ec34902](https://linux-hardware.org/?probe=278ec34902) | Oct 19, 2021 |
| Dell          | XPS 15 9570                 | [26d1a4225d](https://linux-hardware.org/?probe=26d1a4225d) | Oct 17, 2021 |
| Lenovo        | ThinkPad X260 20F5S08Q00    | [2929e779ad](https://linux-hardware.org/?probe=2929e779ad) | Oct 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [fe7520a392](https://linux-hardware.org/?probe=fe7520a392) | Oct 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [8fab065f3b](https://linux-hardware.org/?probe=8fab065f3b) | Oct 14, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [8502c5d5f7](https://linux-hardware.org/?probe=8502c5d5f7) | Oct 13, 2021 |
| Lenovo        | ThinkPad T460p 20FWCTO1W... | [d7f1b3f27e](https://linux-hardware.org/?probe=d7f1b3f27e) | Oct 12, 2021 |
| Acer          | Aspire A515-45              | [4b45531984](https://linux-hardware.org/?probe=4b45531984) | Oct 09, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [4206d52561](https://linux-hardware.org/?probe=4206d52561) | Oct 07, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [8e94483caf](https://linux-hardware.org/?probe=8e94483caf) | Oct 07, 2021 |
| HP            | EliteBook 840 G5            | [e64aeb5fa4](https://linux-hardware.org/?probe=e64aeb5fa4) | Oct 01, 2021 |
| HP            | EliteBook 840 G5            | [28bfae31ee](https://linux-hardware.org/?probe=28bfae31ee) | Oct 01, 2021 |
| Acer          | Aspire A114-32              | [e1dc7a64a4](https://linux-hardware.org/?probe=e1dc7a64a4) | Sep 30, 2021 |
| Dell          | Latitude E5530 non-vPro     | [7e710da685](https://linux-hardware.org/?probe=7e710da685) | Sep 27, 2021 |
| Dell          | Latitude E5530 non-vPro     | [87dd9f48a9](https://linux-hardware.org/?probe=87dd9f48a9) | Sep 26, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [bf5a5a2c74](https://linux-hardware.org/?probe=bf5a5a2c74) | Sep 26, 2021 |
| Apple         | MacBookPro12,1              | [4d798633db](https://linux-hardware.org/?probe=4d798633db) | Sep 25, 2021 |
| Dell          | XPS 15 9570                 | [a54466b990](https://linux-hardware.org/?probe=a54466b990) | Sep 24, 2021 |
| ASUSTek       | E403NA                      | [382c1a7b47](https://linux-hardware.org/?probe=382c1a7b47) | Sep 24, 2021 |
| Dell          | Latitude E5470              | [17d97e59de](https://linux-hardware.org/?probe=17d97e59de) | Sep 23, 2021 |
| ASUSTek       | E402NA                      | [8262dd102f](https://linux-hardware.org/?probe=8262dd102f) | Sep 23, 2021 |
| Lenovo        | ThinkPad E15 20RES6DF07     | [2f5045ab95](https://linux-hardware.org/?probe=2f5045ab95) | Sep 21, 2021 |
| Acer          | Aspire A114-32              | [333d881ec2](https://linux-hardware.org/?probe=333d881ec2) | Sep 20, 2021 |
| Acer          | Aspire A114-32              | [da860f1378](https://linux-hardware.org/?probe=da860f1378) | Sep 20, 2021 |
| HUAWEI        | EUL-WX9                     | [4ab59b64df](https://linux-hardware.org/?probe=4ab59b64df) | Sep 18, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [b640e5da6d](https://linux-hardware.org/?probe=b640e5da6d) | Sep 17, 2021 |
| Dell          | Latitude 5480               | [ac2c5649d3](https://linux-hardware.org/?probe=ac2c5649d3) | Sep 17, 2021 |
| Dell          | Latitude E5470              | [82aca1d7b4](https://linux-hardware.org/?probe=82aca1d7b4) | Sep 16, 2021 |
| Dell          | Latitude E5470              | [c898d2b210](https://linux-hardware.org/?probe=c898d2b210) | Sep 16, 2021 |
| HP            | ZBook 15u G5                | [a5331a4d5e](https://linux-hardware.org/?probe=a5331a4d5e) | Sep 15, 2021 |
| HP            | ZBook Fury 15 G7 Mobile ... | [a92f9c3457](https://linux-hardware.org/?probe=a92f9c3457) | Sep 15, 2021 |
| HP            | EliteBook 820 G1            | [cf1e0581f3](https://linux-hardware.org/?probe=cf1e0581f3) | Sep 15, 2021 |
| MSI           | Alpha 17 A4DE               | [0be8b0b607](https://linux-hardware.org/?probe=0be8b0b607) | Sep 14, 2021 |
| Lenovo        | ThinkPad E590 20NBCTO1WW    | [2b5735f34c](https://linux-hardware.org/?probe=2b5735f34c) | Sep 13, 2021 |
| Samsung       | RF511/RF411/RF711           | [0918a27e6a](https://linux-hardware.org/?probe=0918a27e6a) | Sep 08, 2021 |
| Acer          | Aspire 5745G                | [680d788d4b](https://linux-hardware.org/?probe=680d788d4b) | Sep 07, 2021 |
| MSI           | Alpha 17 A4DE               | [3f0de31253](https://linux-hardware.org/?probe=3f0de31253) | Sep 06, 2021 |
| Dell          | Precision 5510              | [1339721ac0](https://linux-hardware.org/?probe=1339721ac0) | Sep 06, 2021 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [7bc3201683](https://linux-hardware.org/?probe=7bc3201683) | Sep 06, 2021 |
| Samsung       | RF511/RF411/RF711           | [332124aa7f](https://linux-hardware.org/?probe=332124aa7f) | Sep 04, 2021 |
| Acer          | Aspire A515-45              | [16a250faf6](https://linux-hardware.org/?probe=16a250faf6) | Sep 01, 2021 |
| Acer          | Aspire E1-772               | [2b6d07434a](https://linux-hardware.org/?probe=2b6d07434a) | Sep 01, 2021 |
| Dell          | Latitude E7270              | [1bd5f17116](https://linux-hardware.org/?probe=1bd5f17116) | Sep 01, 2021 |
| Acer          | Aspire E1-772               | [4c1d560351](https://linux-hardware.org/?probe=4c1d560351) | Sep 01, 2021 |
| ASUSTek       | UX430UQ                     | [2bd5adb706](https://linux-hardware.org/?probe=2bd5adb706) | Aug 31, 2021 |
| Lenovo        | G710 20252                  | [bcb68ab6d0](https://linux-hardware.org/?probe=bcb68ab6d0) | Aug 21, 2021 |
| Dell          | Studio 1747                 | [ba0f2b7d03](https://linux-hardware.org/?probe=ba0f2b7d03) | Aug 15, 2021 |
| Teclast       | F6 Plus                     | [a1df449dea](https://linux-hardware.org/?probe=a1df449dea) | Aug 13, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [5742cb7dd7](https://linux-hardware.org/?probe=5742cb7dd7) | Aug 12, 2021 |
| Alienware     | x17 R1                      | [447d4de752](https://linux-hardware.org/?probe=447d4de752) | Aug 12, 2021 |
| Clevo         | W55xEU                      | [ee96e1ca32](https://linux-hardware.org/?probe=ee96e1ca32) | Aug 08, 2021 |
| Lenovo        | ThinkPad X240 20AMS0BU0T    | [f22b591a0a](https://linux-hardware.org/?probe=f22b591a0a) | Aug 07, 2021 |
| Lenovo        | ThinkPad T440s 20ARA1DJM... | [3d02d8b67f](https://linux-hardware.org/?probe=3d02d8b67f) | Aug 07, 2021 |
| Apple         | MacBookPro11,5              | [938ff270ef](https://linux-hardware.org/?probe=938ff270ef) | Jul 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [b62fb400bf](https://linux-hardware.org/?probe=b62fb400bf) | Jul 31, 2021 |
| HP            | ProBook 4740s               | [624b649eb0](https://linux-hardware.org/?probe=624b649eb0) | Jul 28, 2021 |
| HP            | EliteBook 1040 G4           | [693137b6b8](https://linux-hardware.org/?probe=693137b6b8) | Jul 26, 2021 |
| Dell          | Latitude 5480               | [64665ed287](https://linux-hardware.org/?probe=64665ed287) | Jul 25, 2021 |
| Dell          | Latitude 5480               | [1b32299688](https://linux-hardware.org/?probe=1b32299688) | Jul 24, 2021 |
| HP            | Presario CQ56               | [7148aa989e](https://linux-hardware.org/?probe=7148aa989e) | Jul 21, 2021 |
| Apple         | MacBook8,1                  | [1220a734d7](https://linux-hardware.org/?probe=1220a734d7) | Jul 20, 2021 |
| Packard Be... | EasyNote ENTG71BM           | [788b497894](https://linux-hardware.org/?probe=788b497894) | Jul 19, 2021 |
| Dell          | XPS 15 9500                 | [610bb918de](https://linux-hardware.org/?probe=610bb918de) | Jul 14, 2021 |
| Notebook      | NV4XMB,ME,MZ                | [eba2e6ade8](https://linux-hardware.org/?probe=eba2e6ade8) | Jul 13, 2021 |
| HP            | Presario CQ56               | [7a202a99e9](https://linux-hardware.org/?probe=7a202a99e9) | Jul 11, 2021 |
| Acer          | Aspire E5-575G              | [27fd4c16ae](https://linux-hardware.org/?probe=27fd4c16ae) | Jul 08, 2021 |
| Lenovo        | IdeaPad 320-17AST 80XW      | [b8a40b6dbd](https://linux-hardware.org/?probe=b8a40b6dbd) | Jul 02, 2021 |
| Lenovo        | G50-80 80L0                 | [ca1d482329](https://linux-hardware.org/?probe=ca1d482329) | Jun 27, 2021 |
| Lenovo        | ThinkPad X230 23252EG       | [77c68fb077](https://linux-hardware.org/?probe=77c68fb077) | Jun 23, 2021 |
| Lenovo        | ThinkPad T460s 20FA0047M... | [eeb383631b](https://linux-hardware.org/?probe=eeb383631b) | Jun 20, 2021 |
| Lenovo        | ThinkPad T520 4243W83       | [b17a1f2c15](https://linux-hardware.org/?probe=b17a1f2c15) | Jun 19, 2021 |
| HP            | EliteBook 820 G1            | [09ff787c3f](https://linux-hardware.org/?probe=09ff787c3f) | Jun 17, 2021 |
| HP            | EliteBook 820 G1            | [b64bd1afcd](https://linux-hardware.org/?probe=b64bd1afcd) | Jun 17, 2021 |
| Lenovo        | ThinkPad T580 20LAS2BH00    | [bbedefdee0](https://linux-hardware.org/?probe=bbedefdee0) | Jun 16, 2021 |
| Dell          | XPS 13 9380                 | [41972327e1](https://linux-hardware.org/?probe=41972327e1) | Jun 15, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [4ecc3eec8f](https://linux-hardware.org/?probe=4ecc3eec8f) | Jun 14, 2021 |
| Lenovo        | ThinkPad T440p 20AW0048G... | [8b1ba139f9](https://linux-hardware.org/?probe=8b1ba139f9) | Jun 13, 2021 |
| Lenovo        | ThinkPad T580 20LAS2BH00    | [9674952e07](https://linux-hardware.org/?probe=9674952e07) | Jun 11, 2021 |
| Lenovo        | ThinkPad T580 20LAS2BH00    | [b39699b009](https://linux-hardware.org/?probe=b39699b009) | Jun 11, 2021 |
| Lenovo        | ThinkPad T410s 291236G      | [ebbdc74a27](https://linux-hardware.org/?probe=ebbdc74a27) | Jun 06, 2021 |
| Acer          | Nitro AN515-42              | [28aadacd07](https://linux-hardware.org/?probe=28aadacd07) | Jun 02, 2021 |
| Lenovo        | ThinkPad T430s 2356GBG      | [aef8c27b50](https://linux-hardware.org/?probe=aef8c27b50) | May 31, 2021 |
| Lenovo        | ThinkPad T430s 2356GBG      | [e67f4b0fd4](https://linux-hardware.org/?probe=e67f4b0fd4) | May 31, 2021 |
| HUAWEI        | MACH-WX9                    | [7fd687d091](https://linux-hardware.org/?probe=7fd687d091) | May 29, 2021 |
| Lenovo        | ThinkPad T450 20BUS0WK03    | [6131e3c22a](https://linux-hardware.org/?probe=6131e3c22a) | May 27, 2021 |
| ASUSTek       | N53TK                       | [cee81adbaf](https://linux-hardware.org/?probe=cee81adbaf) | May 25, 2021 |
| Dell          | XPS 15 9500                 | [8c072ea1c4](https://linux-hardware.org/?probe=8c072ea1c4) | May 24, 2021 |
| Acer          | Aspire 5745G                | [30f455f132](https://linux-hardware.org/?probe=30f455f132) | May 22, 2021 |
| HP            | Spectre Pro x360 G2         | [236efc033e](https://linux-hardware.org/?probe=236efc033e) | May 21, 2021 |
| Razer         | Blade 15 Base Model (Ear... | [2b97441fb1](https://linux-hardware.org/?probe=2b97441fb1) | May 17, 2021 |
| Razer         | Blade 15 Base Model (Ear... | [f9420a7960](https://linux-hardware.org/?probe=f9420a7960) | May 16, 2021 |
| Acer          | Aspire 5745G                | [cb987a733a](https://linux-hardware.org/?probe=cb987a733a) | May 15, 2021 |
| Lenovo        | ThinkPad X230 2325AJG       | [c4b7c3340c](https://linux-hardware.org/?probe=c4b7c3340c) | May 11, 2021 |
| Toshiba       | Satellite L510              | [01753d1f93](https://linux-hardware.org/?probe=01753d1f93) | May 02, 2021 |
| Acer          | TravelMate 8472             | [bdf53780fb](https://linux-hardware.org/?probe=bdf53780fb) | May 01, 2021 |
| Lenovo        | ThinkPad T490s 20NX0054M... | [4cc25622a5](https://linux-hardware.org/?probe=4cc25622a5) | Apr 28, 2021 |
| Acer          | TravelMate 8472             | [84fea7d029](https://linux-hardware.org/?probe=84fea7d029) | Apr 25, 2021 |
| Acer          | TravelMate 8472             | [a4aafc8541](https://linux-hardware.org/?probe=a4aafc8541) | Apr 25, 2021 |
| MSI           | MS-175A                     | [3e3f73559d](https://linux-hardware.org/?probe=3e3f73559d) | Apr 23, 2021 |
| MSI           | MS-175A                     | [22e9e676d9](https://linux-hardware.org/?probe=22e9e676d9) | Apr 23, 2021 |
| Samsung       | 900X3C/900X3D/900X4C/900... | [58df3a61b0](https://linux-hardware.org/?probe=58df3a61b0) | Apr 21, 2021 |
| Dell          | Precision M4500             | [8c35250407](https://linux-hardware.org/?probe=8c35250407) | Apr 17, 2021 |
| ASUSTek       | Zephyrus M GU502GU_GU502... | [67c2373bdf](https://linux-hardware.org/?probe=67c2373bdf) | Apr 15, 2021 |
| ASUSTek       | Zephyrus M GU502GU_GU502... | [db960abcdb](https://linux-hardware.org/?probe=db960abcdb) | Apr 15, 2021 |
| Dell          | XPS 13 9380                 | [cf23d87096](https://linux-hardware.org/?probe=cf23d87096) | Apr 08, 2021 |
| Acer          | NU-A515-44-R68D             | [7e8724905f](https://linux-hardware.org/?probe=7e8724905f) | Apr 06, 2021 |
| Dell          | XPS 13 9380                 | [1631f6bb81](https://linux-hardware.org/?probe=1631f6bb81) | Apr 06, 2021 |
| HP            | ProBook 430 G1              | [6d2b17825a](https://linux-hardware.org/?probe=6d2b17825a) | Apr 05, 2021 |
| Dell          | Latitude E6530              | [0078b55697](https://linux-hardware.org/?probe=0078b55697) | Apr 05, 2021 |
| Acer          | Aspire V3-571G              | [a5268098b2](https://linux-hardware.org/?probe=a5268098b2) | Apr 02, 2021 |
| Dell          | Studio 1747                 | [31c1b6a828](https://linux-hardware.org/?probe=31c1b6a828) | Apr 01, 2021 |
| HP            | Pavilion Notebook           | [6189b0e033](https://linux-hardware.org/?probe=6189b0e033) | Mar 27, 2021 |
| HP            | Pavilion Notebook           | [df09bd2c58](https://linux-hardware.org/?probe=df09bd2c58) | Mar 25, 2021 |
| Dell          | Latitude E6530              | [7cce6316f6](https://linux-hardware.org/?probe=7cce6316f6) | Mar 24, 2021 |
| Lenovo        | ThinkPad X201 4492A23       | [0cace83a52](https://linux-hardware.org/?probe=0cace83a52) | Mar 23, 2021 |
| ASUSTek       | GL553VW                     | [7d8aed9645](https://linux-hardware.org/?probe=7d8aed9645) | Mar 21, 2021 |
| Acer          | Nitro AN515-51              | [79b5d4aed8](https://linux-hardware.org/?probe=79b5d4aed8) | Mar 16, 2021 |
| Acer          | Nitro AN515-51              | [ac92ab9404](https://linux-hardware.org/?probe=ac92ab9404) | Mar 15, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [1725699a96](https://linux-hardware.org/?probe=1725699a96) | Mar 12, 2021 |
| Lenovo        | ThinkPad X230 2325AJG       | [f55532e284](https://linux-hardware.org/?probe=f55532e284) | Mar 12, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [e74933164b](https://linux-hardware.org/?probe=e74933164b) | Mar 10, 2021 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [406b41e802](https://linux-hardware.org/?probe=406b41e802) | Mar 10, 2021 |
| HP            | EliteBook 830 G6            | [45f8bdabb0](https://linux-hardware.org/?probe=45f8bdabb0) | Mar 09, 2021 |
| HP            | EliteBook 830 G6            | [de6b1ee9fe](https://linux-hardware.org/?probe=de6b1ee9fe) | Mar 09, 2021 |
| HP            | EliteBook 8470p             | [d97eb7724a](https://linux-hardware.org/?probe=d97eb7724a) | Mar 04, 2021 |
| Acer          | Aspire E5-575G              | [9f523080d5](https://linux-hardware.org/?probe=9f523080d5) | Mar 03, 2021 |
| Dell          | Precision 5550              | [98abf3a7d0](https://linux-hardware.org/?probe=98abf3a7d0) | Mar 02, 2021 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [8235a48b49](https://linux-hardware.org/?probe=8235a48b49) | Feb 26, 2021 |
| HP            | EliteBook 820 G3            | [22a4daed00](https://linux-hardware.org/?probe=22a4daed00) | Feb 25, 2021 |
| HP            | ZBook 15 G3                 | [7c24c07795](https://linux-hardware.org/?probe=7c24c07795) | Feb 25, 2021 |
| HP            | OMEN by Laptop 17-cb0xxx    | [a2fdf109b0](https://linux-hardware.org/?probe=a2fdf109b0) | Feb 20, 2021 |
| HP            | Pavilion Notebook           | [db4bc9fa7a](https://linux-hardware.org/?probe=db4bc9fa7a) | Feb 20, 2021 |
| Lenovo        | ThinkPad T460s 20F90057M... | [2bf00440b7](https://linux-hardware.org/?probe=2bf00440b7) | Feb 18, 2021 |
| Apple         | MacBookAir7,2               | [01c84ea037](https://linux-hardware.org/?probe=01c84ea037) | Feb 18, 2021 |
| Lenovo        | Z50-70 20354                | [84b15e21ec](https://linux-hardware.org/?probe=84b15e21ec) | Feb 17, 2021 |
| Lenovo        | ThinkPad T420s 4176A11      | [626009a335](https://linux-hardware.org/?probe=626009a335) | Feb 16, 2021 |
| Packard Be... | EasyNote ENTG71BM           | [d11dd1d1a0](https://linux-hardware.org/?probe=d11dd1d1a0) | Feb 14, 2021 |
| Packard Be... | SJV50MV                     | [aba113ee3f](https://linux-hardware.org/?probe=aba113ee3f) | Feb 14, 2021 |
| ASUSTek       | X556URK                     | [6af569fcf4](https://linux-hardware.org/?probe=6af569fcf4) | Feb 13, 2021 |
| Lenovo        | ThinkPad L450 20DT001NMN    | [9a71946a9e](https://linux-hardware.org/?probe=9a71946a9e) | Feb 13, 2021 |
| Lenovo        | ThinkPad L450 20DT001NMN    | [f43d50a826](https://linux-hardware.org/?probe=f43d50a826) | Feb 13, 2021 |
| ASUSTek       | X55U                        | [aea7a001db](https://linux-hardware.org/?probe=aea7a001db) | Feb 13, 2021 |
| Unknown       | T3 MRD                      | [a71b7acc18](https://linux-hardware.org/?probe=a71b7acc18) | Feb 10, 2021 |
| Lenovo        | ThinkPad T420s 4176A11      | [f26de119c9](https://linux-hardware.org/?probe=f26de119c9) | Feb 08, 2021 |
| Lenovo        | ThinkPad T420s 4176A11      | [670ce5270a](https://linux-hardware.org/?probe=670ce5270a) | Feb 07, 2021 |
| Acer          | NG-AN515-52-74W6            | [70574e752f](https://linux-hardware.org/?probe=70574e752f) | Feb 05, 2021 |
| Clevo         | P170EM                      | [eff7a04dad](https://linux-hardware.org/?probe=eff7a04dad) | Feb 02, 2021 |
| ASUSTek       | N501VW                      | [a5a63c6343](https://linux-hardware.org/?probe=a5a63c6343) | Feb 01, 2021 |
| Acer          | Aspire M3-581TG             | [f87979122a](https://linux-hardware.org/?probe=f87979122a) | Jan 31, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | [c71286b553](https://linux-hardware.org/?probe=c71286b553) | Jan 31, 2021 |
| Apple         | MacBookAir4,2               | [590fdfe6bb](https://linux-hardware.org/?probe=590fdfe6bb) | Jan 30, 2021 |
| Lenovo        | ThinkPad X240 20AM006KMN    | [7c40d08353](https://linux-hardware.org/?probe=7c40d08353) | Jan 28, 2021 |
| Lenovo        | ThinkPad T500 22439AG       | [fe8ffb1fc3](https://linux-hardware.org/?probe=fe8ffb1fc3) | Jan 27, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [a2b88b8f9d](https://linux-hardware.org/?probe=a2b88b8f9d) | Jan 27, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [29f9f04453](https://linux-hardware.org/?probe=29f9f04453) | Jan 27, 2021 |
| Lenovo        | ThinkPad T480 20L6002DMX    | [5dd69602d6](https://linux-hardware.org/?probe=5dd69602d6) | Jan 27, 2021 |
| ASUSTek       | GL753VE                     | [af8e0933c0](https://linux-hardware.org/?probe=af8e0933c0) | Jan 24, 2021 |
| Acer          | Swift SF314-42              | [daeea162bf](https://linux-hardware.org/?probe=daeea162bf) | Jan 18, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [aca39bcba0](https://linux-hardware.org/?probe=aca39bcba0) | Jan 18, 2021 |
| MSI           | GE72VR 7RF                  | [1dfd19668d](https://linux-hardware.org/?probe=1dfd19668d) | Jan 14, 2021 |
| Acer          | NU-A515-44-R68D             | [f45afd1e14](https://linux-hardware.org/?probe=f45afd1e14) | Jan 12, 2021 |
| HP            | Stream Laptop 14-cb1XX      | [69a7ec5b7c](https://linux-hardware.org/?probe=69a7ec5b7c) | Jan 07, 2021 |
| Acer          | Swift SF314-42              | [5761cc2a05](https://linux-hardware.org/?probe=5761cc2a05) | Jan 06, 2021 |
| Dell          | XPS 15 7590                 | [69a5abe225](https://linux-hardware.org/?probe=69a5abe225) | Jan 05, 2021 |
| ASUSTek       | GL552JX                     | [5dd9cde584](https://linux-hardware.org/?probe=5dd9cde584) | Jan 03, 2021 |
| ASUSTek       | GL552JX                     | [4dfc0f1909](https://linux-hardware.org/?probe=4dfc0f1909) | Jan 03, 2021 |
| Lenovo        | ThinkPad S1 Yoga 20CD003... | [70d4988c38](https://linux-hardware.org/?probe=70d4988c38) | Dec 30, 2020 |
| Lenovo        | ThinkPad X220 4286CTO       | [bef81325c0](https://linux-hardware.org/?probe=bef81325c0) | Dec 27, 2020 |
| ASUSTek       | G75VW                       | [d04692210c](https://linux-hardware.org/?probe=d04692210c) | Dec 23, 2020 |
| ASUSTek       | G75VW                       | [cc1a212c60](https://linux-hardware.org/?probe=cc1a212c60) | Dec 23, 2020 |
| ASUSTek       | N61Ja                       | [324c64905b](https://linux-hardware.org/?probe=324c64905b) | Dec 20, 2020 |
| Dell          | Latitude E6420              | [d4e4d15cf4](https://linux-hardware.org/?probe=d4e4d15cf4) | Dec 20, 2020 |
| Acer          | Swift SF514-51              | [f04b672d42](https://linux-hardware.org/?probe=f04b672d42) | Dec 15, 2020 |
| Acer          | Swift SF514-51              | [31b51cc2b0](https://linux-hardware.org/?probe=31b51cc2b0) | Dec 13, 2020 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | [7a59304f76](https://linux-hardware.org/?probe=7a59304f76) | Dec 08, 2020 |
| Dell          | XPS 15 9570                 | [d164834ae1](https://linux-hardware.org/?probe=d164834ae1) | Dec 03, 2020 |
| Dell          | XPS 15 9570                 | [5031a2060f](https://linux-hardware.org/?probe=5031a2060f) | Dec 03, 2020 |
| Dell          | XPS 15 9570                 | [b30cae7041](https://linux-hardware.org/?probe=b30cae7041) | Dec 03, 2020 |
| Lenovo        | Yoga S740-14IIL 81RS        | [80b2a9b7a0](https://linux-hardware.org/?probe=80b2a9b7a0) | Dec 01, 2020 |
| Dell          | Precision 5530              | [2d3e299290](https://linux-hardware.org/?probe=2d3e299290) | Nov 29, 2020 |
| Dell          | XPS 13 9380                 | [c27456cd80](https://linux-hardware.org/?probe=c27456cd80) | Nov 28, 2020 |
| Lenovo        | ThinkPad T460s 20F9005CM... | [0b39212390](https://linux-hardware.org/?probe=0b39212390) | Nov 26, 2020 |
| Lenovo        | Legion 5 17IMH05H 81Y8      | [cb0b2991f5](https://linux-hardware.org/?probe=cb0b2991f5) | Nov 26, 2020 |
| Apple         | MacBookPro11,1              | [29f9bd8133](https://linux-hardware.org/?probe=29f9bd8133) | Nov 26, 2020 |
| Apple         | MacBookPro11,1              | [c7a03e79d1](https://linux-hardware.org/?probe=c7a03e79d1) | Nov 26, 2020 |
| HP            | EliteBook 840 G1            | [44f18b2c9c](https://linux-hardware.org/?probe=44f18b2c9c) | Nov 25, 2020 |
| Dell          | XPS 15 9530                 | [498a6352ca](https://linux-hardware.org/?probe=498a6352ca) | Nov 17, 2020 |
| HP            | Presario CQ56               | [dc13808697](https://linux-hardware.org/?probe=dc13808697) | Nov 15, 2020 |
| HP            | EliteBook 840 G4            | [5476e88101](https://linux-hardware.org/?probe=5476e88101) | Nov 13, 2020 |
| Lenovo        | Legion 5 17IMH05H 81Y8      | [94c7b24f6f](https://linux-hardware.org/?probe=94c7b24f6f) | Nov 12, 2020 |
| HP            | EliteBook 840 G4            | [365d184384](https://linux-hardware.org/?probe=365d184384) | Nov 12, 2020 |
| Acer          | Swift SF314-42              | [b1d5b6d202](https://linux-hardware.org/?probe=b1d5b6d202) | Nov 11, 2020 |
| Razer         | Blade 15 Base Model (Ear... | [8aaa52acfe](https://linux-hardware.org/?probe=8aaa52acfe) | Nov 11, 2020 |
| Samsung       | 870Z5G/880Z5F               | [1edba5531d](https://linux-hardware.org/?probe=1edba5531d) | Nov 11, 2020 |
| Samsung       | 870Z5G/880Z5F               | [c8f54522bc](https://linux-hardware.org/?probe=c8f54522bc) | Nov 11, 2020 |
| Lenovo        | ThinkPad L450 20DT001NMN    | [2c04018d8b](https://linux-hardware.org/?probe=2c04018d8b) | Nov 10, 2020 |
| Lenovo        | ThinkPad L450 20DT001NMN    | [e1bfa030b6](https://linux-hardware.org/?probe=e1bfa030b6) | Nov 10, 2020 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [d80b3d6e1b](https://linux-hardware.org/?probe=d80b3d6e1b) | Nov 10, 2020 |
| Apple         | MacBookPro10,1              | [de48058cc4](https://linux-hardware.org/?probe=de48058cc4) | Nov 07, 2020 |
| Lenovo        | ThinkPad T470s 20HGS33N0... | [46e54eb12c](https://linux-hardware.org/?probe=46e54eb12c) | Nov 05, 2020 |
| ASUSTek       | E203NA                      | [83f3bbfada](https://linux-hardware.org/?probe=83f3bbfada) | Nov 05, 2020 |
| Acer          | Aspire V3-571G              | [43a7cef240](https://linux-hardware.org/?probe=43a7cef240) | Nov 01, 2020 |
| Razer         | Blade 15 Base Model (Ear... | [5ec26083ab](https://linux-hardware.org/?probe=5ec26083ab) | Oct 31, 2020 |
| Acer          | Swift SF314-42              | [2b56b5b407](https://linux-hardware.org/?probe=2b56b5b407) | Oct 30, 2020 |
| Acer          | Aspire V3-571G              | [4b0d12f5b0](https://linux-hardware.org/?probe=4b0d12f5b0) | Oct 29, 2020 |
| Acer          | Aspire V3-571G              | [aed3a57697](https://linux-hardware.org/?probe=aed3a57697) | Oct 28, 2020 |
| HP            | EliteBook 8540w             | [22041bab6b](https://linux-hardware.org/?probe=22041bab6b) | Oct 28, 2020 |
| HP            | Pavilion g6                 | [de072f8297](https://linux-hardware.org/?probe=de072f8297) | Oct 26, 2020 |
| HP            | EliteBook 8540w             | [d7a8999c8f](https://linux-hardware.org/?probe=d7a8999c8f) | Oct 22, 2020 |
| HP            | EliteBook 840 G6            | [47c1ff9096](https://linux-hardware.org/?probe=47c1ff9096) | Oct 19, 2020 |
| HP            | EliteBook 725 G2            | [fbdc47c84f](https://linux-hardware.org/?probe=fbdc47c84f) | Oct 15, 2020 |
| LAMINA        | T-1012B NORD                | [633e33d892](https://linux-hardware.org/?probe=633e33d892) | Oct 12, 2020 |
| HP            | ProBook 6475b               | [c547b7b23e](https://linux-hardware.org/?probe=c547b7b23e) | Oct 11, 2020 |
| Clevo         | W150HRM                     | [8859e15cb5](https://linux-hardware.org/?probe=8859e15cb5) | Oct 10, 2020 |
| Nokia         | N900                        | [7960cb48cc](https://linux-hardware.org/?probe=7960cb48cc) | Oct 05, 2020 |
| Toshiba       | Satellite A100              | [93f3a15a9e](https://linux-hardware.org/?probe=93f3a15a9e) | Oct 04, 2020 |
| Toshiba       | Satellite C55-A-1MW         | [a0a0d949d6](https://linux-hardware.org/?probe=a0a0d949d6) | Oct 03, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [06cc9298b0](https://linux-hardware.org/?probe=06cc9298b0) | Oct 02, 2020 |
| HP            | EliteBook 830 G6            | [f3313ab891](https://linux-hardware.org/?probe=f3313ab891) | Sep 28, 2020 |
| Apple         | MacBook2,1                  | [a11af3313e](https://linux-hardware.org/?probe=a11af3313e) | Sep 28, 2020 |
| ASUSTek       | UX430UQ                     | [c201929d1a](https://linux-hardware.org/?probe=c201929d1a) | Sep 27, 2020 |
| HP            | ProBook 6550b               | [b5e0d7059d](https://linux-hardware.org/?probe=b5e0d7059d) | Sep 25, 2020 |
| ASUSTek       | K75DE                       | [f58f907928](https://linux-hardware.org/?probe=f58f907928) | Sep 20, 2020 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | [88f6a44ae4](https://linux-hardware.org/?probe=88f6a44ae4) | Sep 17, 2020 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [c9adcfd59a](https://linux-hardware.org/?probe=c9adcfd59a) | Sep 13, 2020 |
| HP            | EliteBook Revolve 810 G2    | [5aaf924422](https://linux-hardware.org/?probe=5aaf924422) | Sep 13, 2020 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | [956bfaaad9](https://linux-hardware.org/?probe=956bfaaad9) | Sep 11, 2020 |
| Lenovo        | ThinkPad S2 20GKS03C00      | [3db4820f00](https://linux-hardware.org/?probe=3db4820f00) | Sep 05, 2020 |
| Acer          | Swift SF314-42              | [fcce649648](https://linux-hardware.org/?probe=fcce649648) | Sep 04, 2020 |
| Dell          | XPS 13 9380                 | [d97dc026d9](https://linux-hardware.org/?probe=d97dc026d9) | Sep 03, 2020 |
| Clevo         | P15xEMx                     | [6aa236976d](https://linux-hardware.org/?probe=6aa236976d) | Sep 03, 2020 |
| HP            | EliteBook Revolve 810 G2    | [62bf637d91](https://linux-hardware.org/?probe=62bf637d91) | Sep 02, 2020 |
| Lenovo        | ThinkPad X201 3323BSG       | [16840940a8](https://linux-hardware.org/?probe=16840940a8) | Sep 02, 2020 |
| Apple         | MacBookPro12,1              | [08ca1bc0c6](https://linux-hardware.org/?probe=08ca1bc0c6) | Aug 31, 2020 |
| HP            | EliteBook 840 G3            | [e87474d550](https://linux-hardware.org/?probe=e87474d550) | Aug 31, 2020 |
| Dell          | Latitude E7450              | [96a90e1ad3](https://linux-hardware.org/?probe=96a90e1ad3) | Aug 30, 2020 |
| HP            | EliteBook Revolve 810 G2    | [a0f29a4ba9](https://linux-hardware.org/?probe=a0f29a4ba9) | Aug 30, 2020 |
| Lenovo        | Legion Y540-15IRH 81SX      | [d045f2314f](https://linux-hardware.org/?probe=d045f2314f) | Aug 24, 2020 |
| Lenovo        | ThinkPad X250 20CLS8MD00    | [cdc5a7009e](https://linux-hardware.org/?probe=cdc5a7009e) | Aug 18, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [2a83273e54](https://linux-hardware.org/?probe=2a83273e54) | Aug 16, 2020 |
| HP            | G62                         | [79f5cf8c86](https://linux-hardware.org/?probe=79f5cf8c86) | Aug 08, 2020 |
| HP            | EliteBook 8540w             | [d89e8704d1](https://linux-hardware.org/?probe=d89e8704d1) | Aug 03, 2020 |
| Lenovo        | IdeaPad 710S Plus-13IKB ... | [58887ecbe5](https://linux-hardware.org/?probe=58887ecbe5) | Jul 28, 2020 |
| Notebook      | W230SD                      | [17334fe86e](https://linux-hardware.org/?probe=17334fe86e) | Jul 24, 2020 |
| Lenovo        | ThinkPad X230 23252EG       | [2617c14fa9](https://linux-hardware.org/?probe=2617c14fa9) | Jul 24, 2020 |
| Lenovo        | ThinkPad X230 23252EG       | [16ae7ff56d](https://linux-hardware.org/?probe=16ae7ff56d) | Jul 23, 2020 |
| Packard Be... | EasyNote_BU45               | [8e4b6e270b](https://linux-hardware.org/?probe=8e4b6e270b) | Jul 21, 2020 |
| Dell          | Latitude 7400               | [69e41d5126](https://linux-hardware.org/?probe=69e41d5126) | Jul 20, 2020 |
| Dell          | Latitude 7400               | [42561b6e01](https://linux-hardware.org/?probe=42561b6e01) | Jul 20, 2020 |
| HP            | EliteBook 850 G3            | [6bdfab8f44](https://linux-hardware.org/?probe=6bdfab8f44) | Jul 19, 2020 |
| HP            | Notebook                    | [47c49601e5](https://linux-hardware.org/?probe=47c49601e5) | Jul 17, 2020 |
| Dell          | Latitude 7400               | [606ef1afa8](https://linux-hardware.org/?probe=606ef1afa8) | Jul 17, 2020 |
| ASUSTek       | GL552VX                     | [b1e86e0658](https://linux-hardware.org/?probe=b1e86e0658) | Jul 13, 2020 |
| HP            | Notebook                    | [0193bf657a](https://linux-hardware.org/?probe=0193bf657a) | Jul 10, 2020 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [323451d34a](https://linux-hardware.org/?probe=323451d34a) | Jul 07, 2020 |
| Lenovo        | ThinkPad X220 429137G       | [81eaa774db](https://linux-hardware.org/?probe=81eaa774db) | Jun 27, 2020 |
| HP            | EliteBook 840 G2            | [4030e9a77b](https://linux-hardware.org/?probe=4030e9a77b) | Jun 26, 2020 |
| HP            | ProBook 430 G2              | [5a207f8ecb](https://linux-hardware.org/?probe=5a207f8ecb) | Jun 22, 2020 |
| Lenovo        | ThinkPad L480 20LS001AMX    | [ac9b1fcfc1](https://linux-hardware.org/?probe=ac9b1fcfc1) | Jun 19, 2020 |
| Lenovo        | ThinkPad L480 20LS001AMX    | [aae11be071](https://linux-hardware.org/?probe=aae11be071) | Jun 19, 2020 |
| Lenovo        | ThinkPad X220 5114707       | [b7b5a2d3c4](https://linux-hardware.org/?probe=b7b5a2d3c4) | Jun 17, 2020 |
| Acer          | Nitro AN517-51              | [e97d053d44](https://linux-hardware.org/?probe=e97d053d44) | Jun 14, 2020 |
| HP            | ZBook Studio G3             | [fa56c43e8b](https://linux-hardware.org/?probe=fa56c43e8b) | Jun 08, 2020 |
| ASUSTek       | K53SK                       | [70a8febf11](https://linux-hardware.org/?probe=70a8febf11) | Jun 06, 2020 |
| HP            | ProBook 450 G4              | [0fb21e7f95](https://linux-hardware.org/?probe=0fb21e7f95) | Jun 06, 2020 |
| HP            | ProBook 450 G4              | [59b277ce7e](https://linux-hardware.org/?probe=59b277ce7e) | Jun 06, 2020 |
| Apple         | MacBookPro12,1              | [a173aacb52](https://linux-hardware.org/?probe=a173aacb52) | Jun 03, 2020 |
| Apple         | MacBookPro12,1              | [3b583f9685](https://linux-hardware.org/?probe=3b583f9685) | Jun 03, 2020 |
| MSI           | GS65 Stealth Thin 8RE       | [272d2636c4](https://linux-hardware.org/?probe=272d2636c4) | Jun 02, 2020 |
| Apple         | MacBookPro8,2               | [0916b13ab9](https://linux-hardware.org/?probe=0916b13ab9) | May 30, 2020 |
| Lenovo        | ThinkPad X200 74598Y7       | [4552172a72](https://linux-hardware.org/?probe=4552172a72) | May 28, 2020 |
| HP            | ProBook 6550b               | [be0095e38a](https://linux-hardware.org/?probe=be0095e38a) | May 27, 2020 |
| HP            | ProBook 6560b               | [db77e16126](https://linux-hardware.org/?probe=db77e16126) | May 26, 2020 |
| Lenovo        | ThinkPad T480s 20L7001HM... | [8c6c9a5faa](https://linux-hardware.org/?probe=8c6c9a5faa) | May 25, 2020 |
| Packard Be... | EasyNote TS11HR             | [6983e57f22](https://linux-hardware.org/?probe=6983e57f22) | May 24, 2020 |
| Packard Be... | EasyNote TS11HR             | [6191587002](https://linux-hardware.org/?probe=6191587002) | May 24, 2020 |
| HP            | EliteBook 8560p             | [4e386aed8d](https://linux-hardware.org/?probe=4e386aed8d) | May 22, 2020 |
| HP            | EliteBook 8560p             | [97625a0aa5](https://linux-hardware.org/?probe=97625a0aa5) | May 21, 2020 |
| HP            | ZBook 15 G6                 | [4826fc8a4e](https://linux-hardware.org/?probe=4826fc8a4e) | May 15, 2020 |
| Lenovo        | ThinkPad X220 42915CG       | [57fd312a24](https://linux-hardware.org/?probe=57fd312a24) | May 10, 2020 |
| Lenovo        | ThinkPad X220 42915CG       | [2f5ff0ecb0](https://linux-hardware.org/?probe=2f5ff0ecb0) | May 10, 2020 |
| Dell          | Latitude E5450              | [1267f8327e](https://linux-hardware.org/?probe=1267f8327e) | May 05, 2020 |
| Dell          | Latitude E5450              | [869437538e](https://linux-hardware.org/?probe=869437538e) | May 05, 2020 |
| Dell          | Precision M4600             | [f08cd698ff](https://linux-hardware.org/?probe=f08cd698ff) | May 05, 2020 |
| Dell          | Latitude E6330              | [e4ed5b9a57](https://linux-hardware.org/?probe=e4ed5b9a57) | May 05, 2020 |
| HP            | ProBook 6360b               | [877e10ccd2](https://linux-hardware.org/?probe=877e10ccd2) | May 03, 2020 |
| HP            | Presario V6500              | [f4363eb821](https://linux-hardware.org/?probe=f4363eb821) | May 03, 2020 |
| Packard Be... | EasyNote MB65               | [afdaaf53ba](https://linux-hardware.org/?probe=afdaaf53ba) | Apr 30, 2020 |
| Packard Be... | EasyNote MB65               | [18bc60d2a7](https://linux-hardware.org/?probe=18bc60d2a7) | Apr 30, 2020 |
| Dell          | Precision 5540              | [6cf02adf6c](https://linux-hardware.org/?probe=6cf02adf6c) | Apr 29, 2020 |
| HP            | Notebook                    | [edd7cc080c](https://linux-hardware.org/?probe=edd7cc080c) | Apr 29, 2020 |
| HP            | OMEN by Laptop              | [afa4e06e15](https://linux-hardware.org/?probe=afa4e06e15) | Apr 27, 2020 |
| Dell          | Precision 5540              | [520210c4e8](https://linux-hardware.org/?probe=520210c4e8) | Apr 26, 2020 |
| Dell          | Precision 5540              | [0c96c9ee27](https://linux-hardware.org/?probe=0c96c9ee27) | Apr 26, 2020 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [48c077167c](https://linux-hardware.org/?probe=48c077167c) | Apr 24, 2020 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [2f07d3f214](https://linux-hardware.org/?probe=2f07d3f214) | Apr 23, 2020 |
| Lenovo        | ThinkPad T430s 2356GCG      | [9204f9b549](https://linux-hardware.org/?probe=9204f9b549) | Apr 21, 2020 |
| Lenovo        | ThinkPad T430s 2356GCG      | [8adfba26f0](https://linux-hardware.org/?probe=8adfba26f0) | Apr 21, 2020 |
| HP            | EliteBook 840 G6            | [b177ca5c0c](https://linux-hardware.org/?probe=b177ca5c0c) | Apr 19, 2020 |
| HP            | EliteBook 840 G6            | [ace8e5ae82](https://linux-hardware.org/?probe=ace8e5ae82) | Apr 19, 2020 |
| HP            | EliteBook 840 G6            | [d0dd5b9cfe](https://linux-hardware.org/?probe=d0dd5b9cfe) | Apr 19, 2020 |
| Apple         | MacBookPro12,1              | [4cf3de7438](https://linux-hardware.org/?probe=4cf3de7438) | Apr 19, 2020 |
| Lenovo        | ThinkPad T460s 20F9003WM... | [1b1c89732c](https://linux-hardware.org/?probe=1b1c89732c) | Apr 19, 2020 |
| Lenovo        | IdeaPad S510p 20298         | [41e6690bfd](https://linux-hardware.org/?probe=41e6690bfd) | Apr 17, 2020 |
| ASUSTek       | K53E                        | [006182b224](https://linux-hardware.org/?probe=006182b224) | Apr 17, 2020 |
| ASUSTek       | K53E                        | [07c8dde574](https://linux-hardware.org/?probe=07c8dde574) | Apr 17, 2020 |
| Apple         | MacBookPro12,1              | [bf90b17b91](https://linux-hardware.org/?probe=bf90b17b91) | Apr 15, 2020 |
| Apple         | MacBookPro12,1              | [e3673127d2](https://linux-hardware.org/?probe=e3673127d2) | Apr 14, 2020 |
| Acer          | Aspire ES1-520              | [1ebbc3ef40](https://linux-hardware.org/?probe=1ebbc3ef40) | Apr 13, 2020 |
| Acer          | Aspire ES1-520              | [27ba93c17e](https://linux-hardware.org/?probe=27ba93c17e) | Apr 13, 2020 |
| HP            | EliteBook 8470p             | [8607854607](https://linux-hardware.org/?probe=8607854607) | Apr 13, 2020 |
| HP            | EliteBook 8470p             | [4ea04e46a0](https://linux-hardware.org/?probe=4ea04e46a0) | Apr 13, 2020 |
| HP            | EliteBook 840 G5            | [b0d990b779](https://linux-hardware.org/?probe=b0d990b779) | Apr 12, 2020 |
| Lenovo        | Flex 3-1480                 | [4327baf273](https://linux-hardware.org/?probe=4327baf273) | Apr 11, 2020 |
| HP            | G62                         | [65f362927c](https://linux-hardware.org/?probe=65f362927c) | Apr 04, 2020 |
| HP            | Compaq 8710w (GC125EA#AB... | [a06e142488](https://linux-hardware.org/?probe=a06e142488) | Mar 28, 2020 |
| Lenovo        | ThinkPad T450 20BV003SMN    | [15d72b17e9](https://linux-hardware.org/?probe=15d72b17e9) | Mar 27, 2020 |
| Dell          | Inspiron 910                | [5a445b86f5](https://linux-hardware.org/?probe=5a445b86f5) | Mar 26, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [c8544c05c8](https://linux-hardware.org/?probe=c8544c05c8) | Mar 23, 2020 |
| HP            | G62                         | [6f4776017d](https://linux-hardware.org/?probe=6f4776017d) | Mar 21, 2020 |
| Lenovo        | ThinkPad P53 20QQS1JE00     | [6692834531](https://linux-hardware.org/?probe=6692834531) | Mar 18, 2020 |
| Dell          | Inspiron 910                | [40deae1721](https://linux-hardware.org/?probe=40deae1721) | Mar 18, 2020 |
| Lenovo        | ThinkPad W500 40613EG       | [07fbc1a98c](https://linux-hardware.org/?probe=07fbc1a98c) | Mar 16, 2020 |
| Lenovo        | ThinkPad T560 20FH0036MN    | [443d40d6e8](https://linux-hardware.org/?probe=443d40d6e8) | Mar 15, 2020 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [9e6de9df80](https://linux-hardware.org/?probe=9e6de9df80) | Mar 15, 2020 |
| Acer          | Aspire E1-572G              | [cc8b5532c5](https://linux-hardware.org/?probe=cc8b5532c5) | Mar 12, 2020 |
| Dell          | Inspiron 910                | [b8ec7ce084](https://linux-hardware.org/?probe=b8ec7ce084) | Mar 10, 2020 |
| HP            | ProBook 6360b               | [b3c23a39d0](https://linux-hardware.org/?probe=b3c23a39d0) | Mar 06, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [a7d5b5cbba](https://linux-hardware.org/?probe=a7d5b5cbba) | Mar 05, 2020 |
| HP            | ProBook 6360b               | [0a33c7ca36](https://linux-hardware.org/?probe=0a33c7ca36) | Mar 05, 2020 |
| Acer          | Aspire 5552                 | [b10fce36b2](https://linux-hardware.org/?probe=b10fce36b2) | Feb 28, 2020 |
| Acer          | Aspire A517-51              | [2e94416a6c](https://linux-hardware.org/?probe=2e94416a6c) | Feb 28, 2020 |
| Lenovo        | ThinkPad P53 20QQS1JE00     | [41b2c57c35](https://linux-hardware.org/?probe=41b2c57c35) | Feb 26, 2020 |
| Lenovo        | B575e 36852EG               | [af105c3035](https://linux-hardware.org/?probe=af105c3035) | Feb 23, 2020 |
| HP            | EliteBook 2570p             | [ee7aa6d846](https://linux-hardware.org/?probe=ee7aa6d846) | Feb 23, 2020 |
| HP            | EliteBook 2570p             | [910fb6d461](https://linux-hardware.org/?probe=910fb6d461) | Feb 23, 2020 |
| Samsung       | N150/N210/N220              | [ee94964d7c](https://linux-hardware.org/?probe=ee94964d7c) | Feb 23, 2020 |
| HP            | Pavilion dv8                | [58ccc99c12](https://linux-hardware.org/?probe=58ccc99c12) | Feb 22, 2020 |
| Notebook      | N8xEJEK                     | [8fc5a6eb72](https://linux-hardware.org/?probe=8fc5a6eb72) | Feb 22, 2020 |
| Dell          | Inspiron 1545               | [174a4904a7](https://linux-hardware.org/?probe=174a4904a7) | Feb 18, 2020 |
| HP            | ProBook 440 G5              | [eee6e3a9af](https://linux-hardware.org/?probe=eee6e3a9af) | Feb 16, 2020 |
| Dell          | Precision 5530              | [354c8ce45c](https://linux-hardware.org/?probe=354c8ce45c) | Feb 10, 2020 |
| MSI           | GL62M 7REX                  | [c80fad9158](https://linux-hardware.org/?probe=c80fad9158) | Feb 09, 2020 |
| MSI           | GL62M 7REX                  | [a40633b816](https://linux-hardware.org/?probe=a40633b816) | Feb 09, 2020 |
| Dell          | Precision 5530              | [520e69cfef](https://linux-hardware.org/?probe=520e69cfef) | Feb 03, 2020 |
| Toshiba       | NB520                       | [a6b76ee94c](https://linux-hardware.org/?probe=a6b76ee94c) | Feb 02, 2020 |
| Toshiba       | NB520                       | [7fcee73990](https://linux-hardware.org/?probe=7fcee73990) | Feb 02, 2020 |
| Dell          | Precision 5530              | [b28c9b7db5](https://linux-hardware.org/?probe=b28c9b7db5) | Feb 01, 2020 |
| Dell          | Precision 5530              | [767587099c](https://linux-hardware.org/?probe=767587099c) | Feb 01, 2020 |
| Lenovo        | ThinkPad X230 2325WBG       | [bd6ea83361](https://linux-hardware.org/?probe=bd6ea83361) | Jan 25, 2020 |
| HP            | EliteBook 830 G6            | [c4078ad25e](https://linux-hardware.org/?probe=c4078ad25e) | Jan 25, 2020 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [a343aeccf1](https://linux-hardware.org/?probe=a343aeccf1) | Jan 15, 2020 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [d1ef555bfb](https://linux-hardware.org/?probe=d1ef555bfb) | Jan 15, 2020 |
| Lenovo        | Z50-70 20354                | [37002c2466](https://linux-hardware.org/?probe=37002c2466) | Jan 12, 2020 |
| HUAWEI        | WRT-WX9                     | [30f6145d8c](https://linux-hardware.org/?probe=30f6145d8c) | Jan 10, 2020 |
| HUAWEI        | WRT-WX9                     | [c0a2dbc240](https://linux-hardware.org/?probe=c0a2dbc240) | Jan 10, 2020 |
| HUAWEI        | WRT-WX9                     | [e809c2c313](https://linux-hardware.org/?probe=e809c2c313) | Jan 10, 2020 |
| HUAWEI        | WRT-WX9                     | [b639ae9260](https://linux-hardware.org/?probe=b639ae9260) | Jan 10, 2020 |
| HUAWEI        | WRT-WX9                     | [2d2afb9984](https://linux-hardware.org/?probe=2d2afb9984) | Jan 08, 2020 |
| HP            | Pavilion Notebook           | [3aa5a0e012](https://linux-hardware.org/?probe=3aa5a0e012) | Dec 31, 2019 |
| HP            | ENVY Laptop 13-ad1xx        | [e44d4d3221](https://linux-hardware.org/?probe=e44d4d3221) | Dec 21, 2019 |
| Packard Be... | EasyNote TE11HC             | [7857e6a77b](https://linux-hardware.org/?probe=7857e6a77b) | Dec 18, 2019 |
| HP            | Compaq 8710w (GC125EA#AB... | [d201d96afe](https://linux-hardware.org/?probe=d201d96afe) | Dec 12, 2019 |
| ASUSTek       | TP500LA                     | [5e1d50070f](https://linux-hardware.org/?probe=5e1d50070f) | Nov 25, 2019 |
| HP            | EliteBook 840 G6            | [a64d688094](https://linux-hardware.org/?probe=a64d688094) | Nov 23, 2019 |
| Lenovo        | ThinkPad T480 20L60033MX    | [6bc4be7b85](https://linux-hardware.org/?probe=6bc4be7b85) | Nov 23, 2019 |
| Lenovo        | ThinkPad T450s 20BWS1U60... | [ce78a45975](https://linux-hardware.org/?probe=ce78a45975) | Nov 16, 2019 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [3200b20576](https://linux-hardware.org/?probe=3200b20576) | Nov 16, 2019 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [b7089462b3](https://linux-hardware.org/?probe=b7089462b3) | Nov 16, 2019 |
| Apple         | MacBookPro6,1               | [4f5f07bc6e](https://linux-hardware.org/?probe=4f5f07bc6e) | Nov 10, 2019 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [71a554266d](https://linux-hardware.org/?probe=71a554266d) | Nov 08, 2019 |
| HP            | Pavilion dv6                | [bf5a8c1756](https://linux-hardware.org/?probe=bf5a8c1756) | Nov 01, 2019 |
| HP            | Pavilion dv6                | [5d194be097](https://linux-hardware.org/?probe=5d194be097) | Nov 01, 2019 |
| Apple         | MacBookPro6,1               | [2029685373](https://linux-hardware.org/?probe=2029685373) | Oct 19, 2019 |
| Dell          | Latitude D531               | [e5d515dd75](https://linux-hardware.org/?probe=e5d515dd75) | Oct 19, 2019 |
| Acer          | Aspire xxxx                 | [d4d6a3752e](https://linux-hardware.org/?probe=d4d6a3752e) | Oct 18, 2019 |
| Toshiba       | Unknown                     | [64c90921de](https://linux-hardware.org/?probe=64c90921de) | Oct 18, 2019 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [aced6cd1bd](https://linux-hardware.org/?probe=aced6cd1bd) | Oct 17, 2019 |
| Acer          | Aspire V3-574G              | [632726f3fc](https://linux-hardware.org/?probe=632726f3fc) | Oct 16, 2019 |
| Acer          | Aspire V3-574G              | [933dfaebec](https://linux-hardware.org/?probe=933dfaebec) | Oct 16, 2019 |
| HUAWEI        | MACH-WX9                    | [aaa6c2a79e](https://linux-hardware.org/?probe=aaa6c2a79e) | Oct 10, 2019 |
| HP            | ProBook 6550b               | [f359c727c3](https://linux-hardware.org/?probe=f359c727c3) | Oct 07, 2019 |
| HP            | ProBook 430 G2              | [845cc60615](https://linux-hardware.org/?probe=845cc60615) | Oct 02, 2019 |
| Lenovo        | ThinkPad T530 2392APU       | [1236a173c5](https://linux-hardware.org/?probe=1236a173c5) | Sep 02, 2019 |
| Lenovo        | ThinkPad T430 23472M1       | [0327550660](https://linux-hardware.org/?probe=0327550660) | Sep 01, 2019 |
| HP            | OMEN by Laptop              | [60a6a7a4f4](https://linux-hardware.org/?probe=60a6a7a4f4) | Aug 13, 2019 |
| HUAWEI        | MACH-WX9                    | [5f7a70586e](https://linux-hardware.org/?probe=5f7a70586e) | Jul 27, 2019 |
| Lenovo        | ThinkPad T420 4180EA3       | [fbf8462f41](https://linux-hardware.org/?probe=fbf8462f41) | Jul 22, 2019 |
| Lenovo        | G550 20023                  | [370dcd58cc](https://linux-hardware.org/?probe=370dcd58cc) | Jul 22, 2019 |
| Acer          | Aspire A515-52G             | [517cad6069](https://linux-hardware.org/?probe=517cad6069) | Jul 18, 2019 |
| HP            | ProBook 430 G2              | [3e165ac0a4](https://linux-hardware.org/?probe=3e165ac0a4) | Jul 17, 2019 |
| HP            | Laptop 14-bp0xx             | [6fdcfe86c2](https://linux-hardware.org/?probe=6fdcfe86c2) | Jul 14, 2019 |
| Acer          | Aspire xxxx                 | [a67af78289](https://linux-hardware.org/?probe=a67af78289) | Jul 13, 2019 |
| Acer          | Aspire xxxx                 | [7bc2ed3297](https://linux-hardware.org/?probe=7bc2ed3297) | Jul 11, 2019 |
| HP            | ProBook 430 G2              | [c935897214](https://linux-hardware.org/?probe=c935897214) | Jul 10, 2019 |
| Lenovo        | ThinkPad T420s 4174PEG      | [270133c428](https://linux-hardware.org/?probe=270133c428) | Jul 07, 2019 |
| HP            | ProBook 430 G2              | [45ad728ed9](https://linux-hardware.org/?probe=45ad728ed9) | Jul 03, 2019 |
| HP            | ProBook 430 G2              | [7ca78fa791](https://linux-hardware.org/?probe=7ca78fa791) | Jul 02, 2019 |
| HP            | ProBook 430 G2              | [909a60cd55](https://linux-hardware.org/?probe=909a60cd55) | Jul 02, 2019 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [3c2262b65c](https://linux-hardware.org/?probe=3c2262b65c) | Jun 19, 2019 |
| Lenovo        | ThinkPad T420s 4174PEG      | [eedc970aa6](https://linux-hardware.org/?probe=eedc970aa6) | Jun 17, 2019 |
| HP            | EliteBook 8470p             | [707703a569](https://linux-hardware.org/?probe=707703a569) | Jun 09, 2019 |
| Dell          | Precision 7520              | [edeb5aff4c](https://linux-hardware.org/?probe=edeb5aff4c) | Jun 08, 2019 |
| ASUSTek       | K53TK                       | [6a47875df8](https://linux-hardware.org/?probe=6a47875df8) | Jun 08, 2019 |
| Dell          | Latitude E6510              | [a9143beecd](https://linux-hardware.org/?probe=a9143beecd) | Jun 05, 2019 |
| Dell          | G3 3579                     | [59eaf9f30e](https://linux-hardware.org/?probe=59eaf9f30e) | May 17, 2019 |
| Dell          | G3 3579                     | [47fb6be810](https://linux-hardware.org/?probe=47fb6be810) | May 17, 2019 |
| Acer          | Swift SF315-51              | [1bb011abd5](https://linux-hardware.org/?probe=1bb011abd5) | May 12, 2019 |
| Acer          | Nitro AN515-52              | [4b221958a2](https://linux-hardware.org/?probe=4b221958a2) | Apr 28, 2019 |
| Lenovo        | ThinkPad X201 3626GWG       | [18496881cc](https://linux-hardware.org/?probe=18496881cc) | Apr 23, 2019 |
| Samsung       | R19/R20/R21                 | [5d5c459e44](https://linux-hardware.org/?probe=5d5c459e44) | Apr 19, 2019 |
| Dell          | Inspiron MP061              | [d671256209](https://linux-hardware.org/?probe=d671256209) | Apr 18, 2019 |
| Dell          | Inspiron MP061              | [0fd2ab6ca2](https://linux-hardware.org/?probe=0fd2ab6ca2) | Apr 18, 2019 |
| HUAWEI        | MACH-WX9                    | [9c7220422a](https://linux-hardware.org/?probe=9c7220422a) | Apr 07, 2019 |
| ASUSTek       | Zephyrus M GM501GM          | [db4f84abe8](https://linux-hardware.org/?probe=db4f84abe8) | Mar 28, 2019 |
| ASUSTek       | K56CA                       | [8b6978a8bf](https://linux-hardware.org/?probe=8b6978a8bf) | Mar 24, 2019 |
| ASUSTek       | K56CA                       | [0aa8c51eca](https://linux-hardware.org/?probe=0aa8c51eca) | Mar 20, 2019 |
| Lenovo        | ThinkPad T450s 20BX000VM... | [f15c77aa62](https://linux-hardware.org/?probe=f15c77aa62) | Mar 20, 2019 |
| Dell          | Precision 5530              | [0590fe5aab](https://linux-hardware.org/?probe=0590fe5aab) | Mar 01, 2019 |
| HUAWEI        | MACH-WX9                    | [910d0e78a5](https://linux-hardware.org/?probe=910d0e78a5) | Jan 14, 2019 |
| HP            | EliteBook 8560p             | [c94827d5d2](https://linux-hardware.org/?probe=c94827d5d2) | Jan 07, 2019 |
| ASUSTek       | N53SV                       | [ba26650150](https://linux-hardware.org/?probe=ba26650150) | Dec 10, 2018 |
| HP            | EliteBook 850 G2            | [9bc872a1df](https://linux-hardware.org/?probe=9bc872a1df) | Nov 16, 2018 |
| HP            | ProBook 4340s               | [f37c4eb7b0](https://linux-hardware.org/?probe=f37c4eb7b0) | Nov 06, 2018 |
| HP            | ProBook 4340s               | [f8a6517e9f](https://linux-hardware.org/?probe=f8a6517e9f) | Nov 06, 2018 |
| Lenovo        | ThinkPad X220 42914CG       | [218f1cab0a](https://linux-hardware.org/?probe=218f1cab0a) | Oct 21, 2018 |
| Unknown       | Unknown                     | [59c80c3cb7](https://linux-hardware.org/?probe=59c80c3cb7) | Oct 17, 2018 |
| Unknown       | Unknown                     | [ced1bff049](https://linux-hardware.org/?probe=ced1bff049) | Oct 17, 2018 |
| Apple         | MacBook6,1                  | [546260009b](https://linux-hardware.org/?probe=546260009b) | Aug 14, 2018 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Norway/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 75        | 15.24%  |
| Ubuntu 18.04                 | 35        | 7.11%   |
| Pop!_OS 22.04                | 15        | 3.05%   |
| Debian 11                    | 14        | 2.85%   |
| Ubuntu 22.04                 | 13        | 2.64%   |
| Fedora 35                    | 13        | 2.64%   |
| OpenMandriva 4.2             | 11        | 2.24%   |
| Fedora 31                    | 11        | 2.24%   |
| Ubuntu 20.10                 | 10        | 2.03%   |
| KDE neon 20.04               | 10        | 2.03%   |
| Zorin 16                     | 9         | 1.83%   |
| Pop!_OS 21.10                | 9         | 1.83%   |
| Fedora 36                    | 9         | 1.83%   |
| Fedora 34                    | 9         | 1.83%   |
| Arch Rolling                 | 9         | 1.83%   |
| Ubuntu 19.04                 | 8         | 1.63%   |
| Pop!_OS 21.04                | 8         | 1.63%   |
| Pop!_OS 20.10                | 8         | 1.63%   |
| Linux Mint 20.2              | 8         | 1.63%   |
| Xubuntu 20.04                | 7         | 1.42%   |
| Manjaro                      | 7         | 1.42%   |
| Linux Mint 20.3              | 7         | 1.42%   |
| ArcoLinux Rolling            | 7         | 1.42%   |
| Ubuntu 19.10                 | 6         | 1.22%   |
| Pop!_OS 20.04                | 6         | 1.22%   |
| openSUSE Tumbleweed-XXXXXXXX | 6         | 1.22%   |
| OpenMandriva 4.3             | 6         | 1.22%   |
| Linux Mint 20.1              | 5         | 1.02%   |
| Linux Mint 19.3              | 5         | 1.02%   |
| Debian 10                    | 5         | 1.02%   |
| Arch                         | 5         | 1.02%   |
| Zorin 15                     | 4         | 0.81%   |
| Ubuntu 21.10                 | 4         | 0.81%   |
| Manjaro 20.2.1               | 4         | 0.81%   |
| Linux Mint 19.1              | 4         | 0.81%   |
| Fedora 33                    | 4         | 0.81%   |
| Xubuntu 18.04                | 3         | 0.61%   |
| Ubuntu MATE 20.04            | 3         | 0.61%   |
| Ubuntu 18.10                 | 3         | 0.61%   |
| Linux Mint 21                | 3         | 0.61%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 155       | 33.19%  |
| Fedora        | 47        | 10.06%  |
| Pop!_OS       | 42        | 8.99%   |
| Linux Mint    | 33        | 7.07%   |
| Manjaro       | 23        | 4.93%   |
| Debian        | 23        | 4.93%   |
| OpenMandriva  | 19        | 4.07%   |
| Zorin         | 14        | 3%      |
| Arch          | 14        | 3%      |
| KDE neon      | 12        | 2.57%   |
| Xubuntu       | 11        | 2.36%   |
| openSUSE      | 9         | 1.93%   |
| ArcoLinux     | 7         | 1.5%    |
| Kali          | 6         | 1.28%   |
| Elementary    | 6         | 1.28%   |
| Gentoo        | 5         | 1.07%   |
| Ubuntu MATE   | 4         | 0.86%   |
| ROSA          | 4         | 0.86%   |
| Ubuntu Budgie | 3         | 0.64%   |
| Kubuntu       | 3         | 0.64%   |
| EndeavourOS   | 3         | 0.64%   |
| Clear Linux   | 3         | 0.64%   |
| Xero          | 2         | 0.43%   |
| Ubuntu Unity  | 2         | 0.43%   |
| Solus         | 2         | 0.43%   |
| MX            | 2         | 0.43%   |
| Lubuntu       | 2         | 0.43%   |
| CentOS        | 2         | 0.43%   |
| Void Linux    | 1         | 0.21%   |
| Ubuntu Studio | 1         | 0.21%   |
| RHEL          | 1         | 0.21%   |
| Peppermint    | 1         | 0.21%   |
| LMDE          | 1         | 0.21%   |
| Devuan        | 1         | 0.21%   |
| Cleanjaro     | 1         | 0.21%   |
| Chrome OS     | 1         | 0.21%   |
| antergos      | 1         | 0.21%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 10        | 1.86%   |
| 5.4.0-42-generic         | 9         | 1.67%   |
| 5.3.0-46-generic         | 7         | 1.3%    |
| 5.15.0-46-generic        | 7         | 1.3%    |
| 5.4.0-58-generic         | 6         | 1.12%   |
| 5.19.0-76051900-generic  | 6         | 1.12%   |
| 5.11.0-40-generic        | 6         | 1.12%   |
| 5.8.0-44-generic         | 5         | 0.93%   |
| 5.4.0-91-generic         | 5         | 0.93%   |
| 5.4.0-74-generic         | 5         | 0.93%   |
| 5.4.0-48-generic         | 5         | 0.93%   |
| 5.4.0-26-generic         | 5         | 0.93%   |
| 5.16.7-desktop-1omv4003  | 5         | 0.93%   |
| 5.15.0-48-generic        | 5         | 0.93%   |
| 5.8.0-7630-generic       | 4         | 0.74%   |
| 5.8.0-43-generic         | 4         | 0.74%   |
| 5.4.0-45-generic         | 4         | 0.74%   |
| 5.4.0-33-generic         | 4         | 0.74%   |
| 5.3.0-40-generic         | 4         | 0.74%   |
| 5.17.5-76051705-generic  | 4         | 0.74%   |
| 5.17.15-76051715-generic | 4         | 0.74%   |
| 5.13.0-7620-generic      | 4         | 0.74%   |
| 5.13.0-39-generic        | 4         | 0.74%   |
| 5.13.0-28-generic        | 4         | 0.74%   |
| 5.11.0-7620-generic      | 4         | 0.74%   |
| 5.10.0-8-amd64           | 4         | 0.74%   |
| 5.0.0-31-generic         | 4         | 0.74%   |
| 5.8.0-7642-generic       | 3         | 0.56%   |
| 5.8.0-50-generic         | 3         | 0.56%   |
| 5.8.0-48-generic         | 3         | 0.56%   |
| 5.4.0-81-generic         | 3         | 0.56%   |
| 5.4.0-56-generic         | 3         | 0.56%   |
| 5.4.0-53-generic         | 3         | 0.56%   |
| 5.4.0-40-generic         | 3         | 0.56%   |
| 5.4.0-31-generic         | 3         | 0.56%   |
| 5.4.0-29-generic         | 3         | 0.56%   |
| 5.4.0-28-generic         | 3         | 0.56%   |
| 5.4.0-107-generic        | 3         | 0.56%   |
| 5.3.0-42-generic         | 3         | 0.56%   |
| 5.3.0-28-generic         | 3         | 0.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 99        | 19.45%  |
| 5.8.0   | 32        | 6.29%   |
| 5.11.0  | 29        | 5.7%    |
| 4.15.0  | 25        | 4.91%   |
| 5.3.0   | 23        | 4.52%   |
| 5.13.0  | 21        | 4.13%   |
| 5.15.0  | 20        | 3.93%   |
| 5.10.0  | 16        | 3.14%   |
| 5.0.0   | 15        | 2.95%   |
| 4.18.0  | 12        | 2.36%   |
| 5.10.14 | 10        | 1.96%   |
| 5.19.0  | 8         | 1.57%   |
| 5.17.5  | 5         | 0.98%   |
| 5.16.7  | 5         | 0.98%   |
| 5.16.11 | 5         | 0.98%   |
| 5.18.0  | 4         | 0.79%   |
| 5.17.15 | 4         | 0.79%   |
| 4.19.0  | 4         | 0.79%   |
| 5.9.0   | 3         | 0.59%   |
| 5.5.5   | 3         | 0.59%   |
| 5.4.14  | 3         | 0.59%   |
| 5.18.10 | 3         | 0.59%   |
| 5.17.0  | 3         | 0.59%   |
| 5.16.15 | 3         | 0.59%   |
| 5.16.10 | 3         | 0.59%   |
| 5.15.5  | 3         | 0.59%   |
| 5.14.16 | 3         | 0.59%   |
| 5.13.19 | 3         | 0.59%   |
| 5.12.4  | 3         | 0.59%   |
| 5.10.7  | 3         | 0.59%   |
| 6.0.2   | 2         | 0.39%   |
| 5.9.8   | 2         | 0.39%   |
| 5.9.16  | 2         | 0.39%   |
| 5.4.8   | 2         | 0.39%   |
| 5.4.6   | 2         | 0.39%   |
| 5.3.7   | 2         | 0.39%   |
| 5.3.11  | 2         | 0.39%   |
| 5.19.13 | 2         | 0.39%   |
| 5.19.11 | 2         | 0.39%   |
| 5.17.3  | 2         | 0.39%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 111       | 22.11%  |
| 5.8     | 38        | 7.57%   |
| 5.13    | 36        | 7.17%   |
| 5.15    | 35        | 6.97%   |
| 5.11    | 35        | 6.97%   |
| 5.10    | 34        | 6.77%   |
| 5.3     | 31        | 6.18%   |
| 4.15    | 25        | 4.98%   |
| 5.16    | 24        | 4.78%   |
| 5.17    | 19        | 3.78%   |
| 5.19    | 15        | 2.99%   |
| 5.0     | 15        | 2.99%   |
| 4.18    | 15        | 2.99%   |
| 5.14    | 14        | 2.79%   |
| 5.9     | 11        | 2.19%   |
| 5.18    | 10        | 1.99%   |
| 5.12    | 7         | 1.39%   |
| 4.19    | 6         | 1.2%    |
| 5.5     | 5         | 1%      |
| 6.0     | 3         | 0.6%    |
| 5.7     | 3         | 0.6%    |
| 4.9     | 3         | 0.6%    |
| 5.6     | 2         | 0.4%    |
| 5.2     | 2         | 0.4%    |
| 5.1     | 2         | 0.4%    |
| 4.4     | 1         | 0.2%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 439       | 97.12%  |
| i686   | 12        | 2.65%   |
| armv7l | 1         | 0.22%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| GNOME             | 231       | 49.15%  |
| KDE5              | 63        | 13.4%   |
| Unknown           | 56        | 11.91%  |
| XFCE              | 44        | 9.36%   |
| X-Cinnamon        | 21        | 4.47%   |
| KDE               | 12        | 2.55%   |
| MATE              | 9         | 1.91%   |
| Cinnamon          | 6         | 1.28%   |
| Pantheon          | 5         | 1.06%   |
| GNOME Flashback   | 4         | 0.85%   |
| Budgie            | 4         | 0.85%   |
| Unity             | 2         | 0.43%   |
| LXQt              | 2         | 0.43%   |
| LXDE              | 2         | 0.43%   |
| KDE4              | 2         | 0.43%   |
| i3                | 2         | 0.43%   |
| Yaru:ubuntu:GNOME | 1         | 0.21%   |
| xinit-compat      | 1         | 0.21%   |
| i3-with-shmlog    | 1         | 0.21%   |
| Deepin            | 1         | 0.21%   |
| bspwm             | 1         | 0.21%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 360       | 77.25%  |
| Wayland | 70        | 15.02%  |
| Unknown | 30        | 6.44%   |
| Tty     | 6         | 1.29%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 236       | 49.89%  |
| GDM     | 76        | 16.07%  |
| SDDM    | 54        | 11.42%  |
| LightDM | 46        | 9.73%   |
| GDM3    | 40        | 8.46%   |
| TDM     | 17        | 3.59%   |
| KDM     | 3         | 0.63%   |
| XDM     | 1         | 0.21%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| en_US       | 235       | 50.76%  |
| nb_NO       | 117       | 25.27%  |
| Unknown     | 55        | 11.88%  |
| en_GB       | 21        | 4.54%   |
| nn_NO       | 8         | 1.73%   |
| C           | 8         | 1.73%   |
| pl_PL       | 5         | 1.08%   |
| en_DK       | 3         | 0.65%   |
| de_DE       | 3         | 0.65%   |
| ru_RU       | 1         | 0.22%   |
| pt_PT       | 1         | 0.22%   |
| fi_FI       | 1         | 0.22%   |
| en_US.utf-8 | 1         | 0.22%   |
| en_IE       | 1         | 0.22%   |
| en_150      | 1         | 0.22%   |
| en_001      | 1         | 0.22%   |
| el_GR       | 1         | 0.22%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 244       | 53.28%  |
| BIOS | 214       | 46.72%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 365       | 79.52%  |
| Btrfs   | 43        | 9.37%   |
| Overlay | 25        | 5.45%   |
| Unknown | 12        | 2.61%   |
| Xfs     | 10        | 2.18%   |
| Zfs     | 2         | 0.44%   |
| Ext3    | 1         | 0.22%   |
| Ext2    | 1         | 0.22%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 258       | 56.21%  |
| GPT     | 163       | 35.51%  |
| MBR     | 38        | 8.28%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 411       | 89.74%  |
| Yes       | 47        | 10.26%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 355       | 77.51%  |
| Yes       | 103       | 22.49%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo               | 134       | 29.65%  |
| Hewlett-Packard      | 86        | 19.03%  |
| Dell                 | 67        | 14.82%  |
| ASUSTek Computer     | 47        | 10.4%   |
| Acer                 | 35        | 7.74%   |
| Apple                | 16        | 3.54%   |
| MSI                  | 14        | 3.1%    |
| HUAWEI               | 13        | 2.88%   |
| Toshiba              | 8         | 1.77%   |
| Samsung Electronics  | 6         | 1.33%   |
| Packard Bell         | 6         | 1.33%   |
| Notebook             | 5         | 1.11%   |
| Clevo                | 4         | 0.88%   |
| Unknown              | 3         | 0.66%   |
| Teclast              | 1         | 0.22%   |
| Razer                | 1         | 0.22%   |
| Nokia                | 1         | 0.22%   |
| LAMINA               | 1         | 0.22%   |
| Intel Client Systems | 1         | 0.22%   |
| Google               | 1         | 0.22%   |
| Getac                | 1         | 0.22%   |
| Alienware            | 1         | 0.22%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| HUAWEI MACH-WX9                          | 6         | 1.33%   |
| Dell Precision 5530                      | 5         | 1.11%   |
| HP ProBook 430 G2                        | 4         | 0.88%   |
| Unknown                                  | 4         | 0.88%   |
| HUAWEI WRT-WX9                           | 3         | 0.66%   |
| HP OMEN by Laptop                        | 3         | 0.66%   |
| HP EliteBook 8470p                       | 3         | 0.66%   |
| HP EliteBook 840 G6                      | 3         | 0.66%   |
| Dell XPS 15 9570                         | 3         | 0.66%   |
| Dell XPS 15 9500                         | 3         | 0.66%   |
| Dell XPS 13 9380                         | 3         | 0.66%   |
| Dell Latitude E7240                      | 3         | 0.66%   |
| Dell Latitude E5470                      | 3         | 0.66%   |
| Dell Latitude 5480                       | 3         | 0.66%   |
| Apple MacBookPro12,1                     | 3         | 0.66%   |
| MSI GF63 Thin 11UD                       | 2         | 0.44%   |
| Lenovo Z50-70 20354                      | 2         | 0.44%   |
| Lenovo Yoga Slim 7 Pro 14IAH7 82UT       | 2         | 0.44%   |
| Lenovo Yoga Slim 7 14ARE05 82A2          | 2         | 0.44%   |
| Lenovo Y520-15IKBN 80WK                  | 2         | 0.44%   |
| Lenovo ThinkPad X230 23252EG             | 2         | 0.44%   |
| Lenovo ThinkPad X1 Carbon 7th 20QD00L1MX | 2         | 0.44%   |
| Lenovo ThinkPad L450 20DT001NMN          | 2         | 0.44%   |
| HP ProBook 6550b                         | 2         | 0.44%   |
| HP ProBook 4330s                         | 2         | 0.44%   |
| HP Pavilion Notebook                     | 2         | 0.44%   |
| HP EliteBook 8560p                       | 2         | 0.44%   |
| HP EliteBook 840 G8 Notebook PC          | 2         | 0.44%   |
| HP EliteBook 840 G5                      | 2         | 0.44%   |
| HP EliteBook 840 G4                      | 2         | 0.44%   |
| HP EliteBook 840 G1                      | 2         | 0.44%   |
| HP EliteBook 830 G6                      | 2         | 0.44%   |
| HP EliteBook 820 G1                      | 2         | 0.44%   |
| Dell XPS 15 9520                         | 2         | 0.44%   |
| Dell XPS 15 7590                         | 2         | 0.44%   |
| Dell Latitude E6530                      | 2         | 0.44%   |
| Dell Latitude E5450                      | 2         | 0.44%   |
| Dell Latitude D531                       | 2         | 0.44%   |
| ASUS X55U                                | 2         | 0.44%   |
| ASUS VivoBook_ASUSLaptop E410MAB_E410MA  | 2         | 0.44%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 100       | 22.12%  |
| HP EliteBook          | 33        | 7.3%    |
| Dell Latitude         | 29        | 6.42%   |
| Acer Aspire           | 24        | 5.31%   |
| HP ProBook            | 20        | 4.42%   |
| Dell XPS              | 17        | 3.76%   |
| Dell Precision        | 13        | 2.88%   |
| Lenovo IdeaPad        | 10        | 2.21%   |
| HP ZBook              | 9         | 1.99%   |
| ASUS VivoBook         | 8         | 1.77%   |
| Lenovo Yoga           | 7         | 1.55%   |
| Toshiba Satellite     | 6         | 1.33%   |
| HUAWEI MACH-WX9       | 6         | 1.33%   |
| HP Pavilion           | 6         | 1.33%   |
| Dell Inspiron         | 6         | 1.33%   |
| Packard Bell EasyNote | 5         | 1.11%   |
| HP OMEN               | 5         | 1.11%   |
| Acer Swift            | 5         | 1.11%   |
| Unknown               | 4         | 0.88%   |
| Lenovo Legion         | 3         | 0.66%   |
| HUAWEI WRT-WX9        | 3         | 0.66%   |
| HP Laptop             | 3         | 0.66%   |
| ASUS ZenBook          | 3         | 0.66%   |
| ASUS TUF              | 3         | 0.66%   |
| Apple MacBookPro12    | 3         | 0.66%   |
| Apple MacBookPro11    | 3         | 0.66%   |
| Acer Nitro            | 3         | 0.66%   |
| MSI GS66              | 2         | 0.44%   |
| MSI GF63              | 2         | 0.44%   |
| Lenovo Z50-70         | 2         | 0.44%   |
| Lenovo Y520-15IKBN    | 2         | 0.44%   |
| HP Presario           | 2         | 0.44%   |
| HP Compaq             | 2         | 0.44%   |
| ASUS Zephyrus         | 2         | 0.44%   |
| ASUS X55U             | 2         | 0.44%   |
| ASUS UX430UQ          | 2         | 0.44%   |
| Toshiba NB520         | 1         | 0.22%   |
| Teclast F6            | 1         | 0.22%   |
| Samsung RF511         | 1         | 0.22%   |
| Samsung R19           | 1         | 0.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2018    | 49        | 10.84%  |
| 2019    | 48        | 10.62%  |
| 2016    | 41        | 9.07%   |
| 2020    | 40        | 8.85%   |
| 2012    | 39        | 8.63%   |
| 2011    | 34        | 7.52%   |
| 2017    | 31        | 6.86%   |
| 2015    | 31        | 6.86%   |
| 2010    | 26        | 5.75%   |
| 2021    | 25        | 5.53%   |
| 2014    | 25        | 5.53%   |
| 2013    | 22        | 4.87%   |
| 2009    | 15        | 3.32%   |
| 2007    | 9         | 1.99%   |
| 2022    | 8         | 1.77%   |
| 2008    | 6         | 1.33%   |
| 2006    | 1         | 0.22%   |
| 2005    | 1         | 0.22%   |
| Unknown | 1         | 0.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 452       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 397       | 87.64%  |
| Enabled  | 56        | 12.36%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 450       | 99.56%  |
| Yes  | 2         | 0.44%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 136       | 29.76%  |
| 16.01-24.0  | 108       | 23.63%  |
| 8.01-16.0   | 76        | 16.63%  |
| 3.01-4.0    | 67        | 14.66%  |
| 32.01-64.0  | 42        | 9.19%   |
| 1.01-2.0    | 12        | 2.63%   |
| 64.01-256.0 | 5         | 1.09%   |
| 24.01-32.0  | 4         | 0.88%   |
| 2.01-3.0    | 3         | 0.66%   |
| 0.51-1.0    | 3         | 0.66%   |
| 0.01-0.5    | 1         | 0.22%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 153       | 30.6%   |
| 2.01-3.0   | 126       | 25.2%   |
| 4.01-8.0   | 96        | 19.2%   |
| 3.01-4.0   | 82        | 16.4%   |
| 0.51-1.0   | 19        | 3.8%    |
| 8.01-16.0  | 18        | 3.6%    |
| 0.01-0.5   | 4         | 0.8%    |
| 16.01-24.0 | 2         | 0.4%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 364       | 79.13%  |
| 2      | 82        | 17.83%  |
| 3      | 9         | 1.96%   |
| 0      | 3         | 0.65%   |
| 6      | 1         | 0.22%   |
| 4      | 1         | 0.22%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 340       | 74.73%  |
| Yes       | 115       | 25.27%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 368       | 81.24%  |
| No        | 85        | 18.76%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 448       | 99.12%  |
| No        | 4         | 0.88%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 365       | 79.35%  |
| No        | 95        | 20.65%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Norway  | 452       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Oslo                 | 152       | 31.87%  |
| Trondheim            | 22        | 4.61%   |
| Bergen               | 21        | 4.4%    |
| Kristiansand         | 15        | 3.14%   |
| Stavanger            | 11        | 2.31%   |
| Tromsø              | 10        | 2.1%    |
| Røyken Municipality | 8         | 1.68%   |
| Fredrikstad          | 7         | 1.47%   |
| Skien                | 6         | 1.26%   |
| Drammen              | 6         | 1.26%   |
| Sandnes              | 5         | 1.05%   |
| Drobak               | 5         | 1.05%   |
| Bodø                | 5         | 1.05%   |
| Nesttun              | 4         | 0.84%   |
| Moss                 | 4         | 0.84%   |
| Vear                 | 3         | 0.63%   |
| Tønsberg            | 3         | 0.63%   |
| Sarpsborg            | 3         | 0.63%   |
| Honefoss             | 3         | 0.63%   |
| Haugesund            | 3         | 0.63%   |
| Hamar                | 3         | 0.63%   |
| Fornebu              | 3         | 0.63%   |
| Ålesund             | 3         | 0.63%   |
| Stjordal             | 2         | 0.42%   |
| Stabekk              | 2         | 0.42%   |
| Skoppum              | 2         | 0.42%   |
| Skollenborg          | 2         | 0.42%   |
| Skiptvet             | 2         | 0.42%   |
| Ski                  | 2         | 0.42%   |
| Sistranda            | 2         | 0.42%   |
| Sandefjord           | 2         | 0.42%   |
| Saetre               | 2         | 0.42%   |
| Rong                 | 2         | 0.42%   |
| Notteroy             | 2         | 0.42%   |
| Nesodden             | 2         | 0.42%   |
| Nesbru               | 2         | 0.42%   |
| Mjondalen            | 2         | 0.42%   |
| Melhus               | 2         | 0.42%   |
| Lysaker              | 2         | 0.42%   |
| Lunner               | 2         | 0.42%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 126       | 168    | 23.16%  |
| Toshiba                        | 47        | 52     | 8.64%   |
| SanDisk                        | 43        | 55     | 7.9%    |
| WDC                            | 42        | 53     | 7.72%   |
| Seagate                        | 36        | 41     | 6.62%   |
| SK hynix                       | 32        | 34     | 5.88%   |
| Unknown                        | 30        | 36     | 5.51%   |
| Intel                          | 23        | 26     | 4.23%   |
| Micron Technology              | 21        | 30     | 3.86%   |
| Kingston                       | 21        | 29     | 3.86%   |
| Hitachi                        | 16        | 24     | 2.94%   |
| Crucial                        | 14        | 16     | 2.57%   |
| HGST                           | 12        | 12     | 2.21%   |
| LITEON                         | 11        | 15     | 2.02%   |
| Apple                          | 11        | 13     | 2.02%   |
| KIOXIA                         | 6         | 13     | 1.1%    |
| PNY                            | 5         | 7      | 0.92%   |
| A-DATA Technology              | 5         | 7      | 0.92%   |
| Lenovo                         | 4         | 4      | 0.74%   |
| Phison                         | 3         | 4      | 0.55%   |
| OCZ                            | 3         | 3      | 0.55%   |
| LITEONIT                       | 3         | 4      | 0.55%   |
| Fujitsu                        | 3         | 3      | 0.55%   |
| Corsair                        | 3         | 3      | 0.55%   |
| XPG                            | 2         | 2      | 0.37%   |
| Transcend                      | 2         | 2      | 0.37%   |
| Lexar                          | 2         | 2      | 0.37%   |
| China                          | 2         | 2      | 0.37%   |
| ASMT                           | 2         | 2      | 0.37%   |
| Ugreen                         | 1         | 1      | 0.18%   |
| Teclast                        | 1         | 1      | 0.18%   |
| STEC                           | 1         | 1      | 0.18%   |
| Solid State Storage Technology | 1         | 1      | 0.18%   |
| Phison Electronics             | 1         | 1      | 0.18%   |
| Patriot                        | 1         | 1      | 0.18%   |
| Lite-On                        | 1         | 1      | 0.18%   |
| Linux                          | 1         | 1      | 0.18%   |
| LaCie                          | 1         | 1      | 0.18%   |
| Intenso                        | 1         | 1      | 0.18%   |
| GOODRAM                        | 1         | 1      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 13        | 2.29%   |
| HGST HTS721010A9E630 1TB               | 7         | 1.23%   |
| Toshiba NVMe SSD Drive 256GB           | 6         | 1.06%   |
| Unknown MMC Card  64GB                 | 5         | 0.88%   |
| SanDisk NVMe SSD Drive 512GB           | 5         | 0.88%   |
| Samsung NVMe SSD Drive 1024GB          | 5         | 0.88%   |
| PNY ELITE PSSD 240GB                   | 5         | 0.88%   |
| Toshiba NVMe SSD Drive 512GB           | 4         | 0.71%   |
| SK hynix NVMe SSD Drive 512GB          | 4         | 0.71%   |
| SanDisk NVMe SSD Drive 500GB           | 4         | 0.71%   |
| SanDisk NVMe SSD Drive 256GB           | 4         | 0.71%   |
| Samsung NVMe SSD Drive 500GB           | 4         | 0.71%   |
| Kingston SV300S37A120G 120GB SSD       | 4         | 0.71%   |
| Intel NVMe SSD Drive 512GB             | 4         | 0.71%   |
| WDC WDS500G2B0A-00SM50 500GB SSD       | 3         | 0.53%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB   | 3         | 0.53%   |
| Unknown MMC Card  16GB                 | 3         | 0.53%   |
| SK hynix PC401 NVMe 512GB              | 3         | 0.53%   |
| SK hynix PC401 NVMe 1TB                | 3         | 0.53%   |
| SK hynix HFS128G39TND-N210A 128GB SSD  | 3         | 0.53%   |
| Seagate ST9500325AS 500GB              | 3         | 0.53%   |
| Seagate Expansion 2TB                  | 3         | 0.53%   |
| SanDisk SD8SN8U-128G-1006 128GB SSD    | 3         | 0.53%   |
| SanDisk SD6SB1M-128G-1006 128GB SSD    | 3         | 0.53%   |
| SanDisk NVMe SSD Drive 1TB             | 3         | 0.53%   |
| Samsung SSD 850 EVO 250GB              | 3         | 0.53%   |
| Samsung NVMe SSD Drive 512GB           | 3         | 0.53%   |
| Samsung MZ7LN256HCHP-000L7 256GB SSD   | 3         | 0.53%   |
| OCZ AGILITY3 120GB SSD                 | 3         | 0.53%   |
| Micron NVMe SSD Drive 512GB            | 3         | 0.53%   |
| Micron MTFDKBA512TFH 512GB             | 3         | 0.53%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD    | 3         | 0.53%   |
| Kingston OM8PCP3512F-AI1 512GB         | 3         | 0.53%   |
| Kingston NVMe SSD Drive 512GB          | 3         | 0.53%   |
| Hitachi HTS545050B9A300 500GB          | 3         | 0.53%   |
| HGST HTS725050A7E630 500GB             | 3         | 0.53%   |
| Crucial CT120BX500SSD1 120GB           | 3         | 0.53%   |
| WDC WD5000BEVT-22ZAT0 500GB            | 2         | 0.35%   |
| WDC WD10JPVX-22JC3T0 1TB               | 2         | 0.35%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB   | 2         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 35        | 40     | 32.71%  |
| WDC                 | 20        | 29     | 18.69%  |
| Toshiba             | 17        | 20     | 15.89%  |
| Hitachi             | 16        | 24     | 14.95%  |
| HGST                | 12        | 12     | 11.21%  |
| Fujitsu             | 3         | 3      | 2.8%    |
| Unknown             | 1         | 1      | 0.93%   |
| Samsung Electronics | 1         | 3      | 0.93%   |
| LaCie               | 1         | 1      | 0.93%   |
| Intenso             | 1         | 1      | 0.93%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 63        | 79     | 30.29%  |
| SanDisk             | 23        | 28     | 11.06%  |
| Kingston            | 16        | 18     | 7.69%   |
| Intel               | 14        | 16     | 6.73%   |
| Crucial             | 14        | 16     | 6.73%   |
| Apple               | 10        | 12     | 4.81%   |
| Micron Technology   | 9         | 13     | 4.33%   |
| LITEON              | 9         | 13     | 4.33%   |
| SK hynix            | 8         | 9      | 3.85%   |
| Toshiba             | 7         | 7      | 3.37%   |
| WDC                 | 6         | 8      | 2.88%   |
| PNY                 | 5         | 7      | 2.4%    |
| A-DATA Technology   | 4         | 6      | 1.92%   |
| OCZ                 | 3         | 3      | 1.44%   |
| LITEONIT            | 3         | 4      | 1.44%   |
| Corsair             | 3         | 3      | 1.44%   |
| Transcend           | 2         | 2      | 0.96%   |
| China               | 2         | 2      | 0.96%   |
| ASMT                | 2         | 2      | 0.96%   |
| Teclast             | 1         | 1      | 0.48%   |
| Seagate             | 1         | 1      | 0.48%   |
| Patriot             | 1         | 1      | 0.48%   |
| GOODRAM             | 1         | 1      | 0.48%   |
| BIWIN               | 1         | 1      | 0.48%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 195       | 253    | 37.72%  |
| NVMe    | 180       | 246    | 34.82%  |
| HDD     | 105       | 134    | 20.31%  |
| MMC     | 30        | 36     | 5.8%    |
| Unknown | 7         | 7      | 1.35%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 271       | 363    | 53.77%  |
| NVMe | 180       | 246    | 35.71%  |
| MMC  | 30        | 36     | 5.95%   |
| SAS  | 23        | 31     | 4.56%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 232       | 312    | 77.08%  |
| 0.51-1.0   | 55        | 58     | 18.27%  |
| 1.01-2.0   | 11        | 13     | 3.65%   |
| 3.01-4.0   | 2         | 3      | 0.66%   |
| 4.01-10.0  | 1         | 1      | 0.33%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 172       | 36.36%  |
| 251-500        | 122       | 25.79%  |
| 501-1000       | 52        | 10.99%  |
| 1-20           | 35        | 7.4%    |
| 1001-2000      | 30        | 6.34%   |
| 51-100         | 20        | 4.23%   |
| 21-50          | 13        | 2.75%   |
| More than 3000 | 11        | 2.33%   |
| 2001-3000      | 11        | 2.33%   |
| Unknown        | 7         | 1.48%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 194       | 39.11%  |
| 21-50          | 82        | 16.53%  |
| 101-250        | 74        | 14.92%  |
| 51-100         | 64        | 12.9%   |
| 251-500        | 43        | 8.67%   |
| 1001-2000      | 15        | 3.02%   |
| 501-1000       | 12        | 2.42%   |
| Unknown        | 7         | 1.41%   |
| More than 3000 | 5         | 1.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD7500BPVX-22JC3T0 752GB                        | 1         | 1      | 4.35%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 1         | 1      | 4.35%   |
| Toshiba MK5055GSX 500GB                             | 1         | 2      | 4.35%   |
| SK hynix SH920 2.5 7MM 128GB SSD                    | 1         | 1      | 4.35%   |
| SK hynix SC210 2.5 7MM 256GB SSD                    | 1         | 1      | 4.35%   |
| SK hynix HFS128G39TND-N210A 128GB SSD               | 1         | 1      | 4.35%   |
| Seagate ST9750420AS 752GB                           | 1         | 1      | 4.35%   |
| Seagate ST500LT012-1DG142 500GB                     | 1         | 1      | 4.35%   |
| Seagate ST500LM000-SSHD-8GB                         | 1         | 1      | 4.35%   |
| Seagate ST1000LM014-SSHD-8GB                        | 1         | 1      | 4.35%   |
| SanDisk SD8TN8U-256G-1006 256GB SSD                 | 1         | 1      | 4.35%   |
| Samsung Electronics SSD SM841 2.5 7mm 256GB         | 1         | 1      | 4.35%   |
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 4      | 4.35%   |
| Micron Technology 1100_MTFDDAV512TBN 512GB SSD      | 1         | 1      | 4.35%   |
| Micron Technology 1100_MTFDDAK512TBN 512GB SSD      | 1         | 1      | 4.35%   |
| Lenovo LENSE20256GMSP34MEAT2TA 256GB                | 1         | 1      | 4.35%   |
| Intel SSDSA1M080G2LE 80GB                           | 1         | 1      | 4.35%   |
| Hitachi HTS725032A9A364 320GB                       | 1         | 1      | 4.35%   |
| Hitachi HTS725025A9A364 250GB                       | 1         | 1      | 4.35%   |
| HGST HTS725050A7E630 500GB                          | 1         | 1      | 4.35%   |
| Crucial CT256M550SSD1 256GB                         | 1         | 1      | 4.35%   |
| Corsair Performance Pro 128GB SSD                   | 1         | 1      | 4.35%   |
| Corsair Force GS 240GB SSD                          | 1         | 1      | 4.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 4      | 17.39%  |
| SK hynix            | 3         | 3      | 13.04%  |
| Micron Technology   | 3         | 6      | 13.04%  |
| WDC                 | 2         | 2      | 8.7%    |
| Hitachi             | 2         | 2      | 8.7%    |
| Corsair             | 2         | 2      | 8.7%    |
| Toshiba             | 1         | 2      | 4.35%   |
| SanDisk             | 1         | 1      | 4.35%   |
| Samsung Electronics | 1         | 1      | 4.35%   |
| Lenovo              | 1         | 1      | 4.35%   |
| Intel               | 1         | 1      | 4.35%   |
| HGST                | 1         | 1      | 4.35%   |
| Crucial             | 1         | 1      | 4.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 40%     |
| WDC     | 2         | 2      | 20%     |
| Hitachi | 2         | 2      | 20%     |
| Toshiba | 1         | 2      | 10%     |
| HGST    | 1         | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 12        | 15     | 52.17%  |
| HDD  | 10        | 11     | 43.48%  |
| NVMe | 1         | 1      | 4.35%   |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 284       | 417    | 58.8%   |
| Works    | 176       | 232    | 36.44%  |
| Malfunc  | 23        | 27     | 4.76%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 310       | 57.94%  |
| Samsung Electronics            | 69        | 12.9%   |
| AMD                            | 35        | 6.54%   |
| SanDisk                        | 34        | 6.36%   |
| Toshiba America Info Systems   | 24        | 4.49%   |
| SK hynix                       | 24        | 4.49%   |
| Micron Technology              | 12        | 2.24%   |
| Kingston Technology Company    | 5         | 0.93%   |
| Lenovo                         | 4         | 0.75%   |
| KIOXIA                         | 4         | 0.75%   |
| Phison Electronics             | 3         | 0.56%   |
| Lite-On Technology             | 3         | 0.56%   |
| Nvidia                         | 2         | 0.37%   |
| Marvell Technology Group       | 2         | 0.37%   |
| ADATA Technology               | 2         | 0.37%   |
| Solid State Storage Technology | 1         | 0.19%   |
| Apple                          | 1         | 0.19%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 39        | 6.9%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 37        | 6.55%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 29        | 5.13%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 28        | 4.96%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 27        | 4.78%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 25        | 4.42%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 22        | 3.89%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 21        | 3.72%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 17        | 3.01%   |
| Intel Volume Management Device NVMe RAID Controller                              | 16        | 2.83%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 15        | 2.65%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 15        | 2.65%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 14        | 2.48%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 12        | 2.12%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 12        | 2.12%   |
| Micron Non-Volatile memory controller                                            | 12        | 2.12%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 12        | 2.12%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 12        | 2.12%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 9         | 1.59%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 8         | 1.42%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                      | 8         | 1.42%   |
| SK hynix Non-Volatile memory controller                                          | 8         | 1.42%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 8         | 1.42%   |
| Samsung NVMe SSD Controller 980                                                  | 7         | 1.24%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 6         | 1.06%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 5         | 0.88%   |
| Samsung Electronics SATA controller                                              | 5         | 0.88%   |
| Kingston Company Company Non-Volatile memory controller                          | 5         | 0.88%   |
| Intel SSD 660P Series                                                            | 5         | 0.88%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 5         | 0.88%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 5         | 0.88%   |
| SK hynix Gold P31 SSD                                                            | 4         | 0.71%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 4         | 0.71%   |
| Lenovo Non-Volatile memory controller                                            | 4         | 0.71%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 4         | 0.71%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 4         | 0.71%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 4         | 0.71%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 3         | 0.53%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 3         | 0.53%   |
| Lite-On Non-Volatile memory controller                                           | 3         | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 299       | 54.96%  |
| NVMe | 179       | 32.9%   |
| RAID | 44        | 8.09%   |
| IDE  | 22        | 4.04%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 395       | 87.39%  |
| AMD    | 56        | 12.39%  |
| ARM    | 1         | 0.22%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz       | 14        | 3.1%    |
| Intel Core i5-8250U CPU @ 1.60GHz       | 12        | 2.65%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 11        | 2.43%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 10        | 2.21%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 9         | 1.99%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 9         | 1.99%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 9         | 1.99%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 7         | 1.55%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 7         | 1.55%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 7         | 1.55%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 7         | 1.55%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 7         | 1.55%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 7         | 1.55%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 6         | 1.33%   |
| Intel Core i7-3520M CPU @ 2.90GHz       | 6         | 1.33%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 6         | 1.33%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 5         | 1.11%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 5         | 1.11%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 5         | 1.11%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 5         | 1.11%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 5         | 1.11%   |
| Intel Core i3-4030U CPU @ 1.90GHz       | 5         | 1.11%   |
| Intel Core i9-8950HK CPU @ 2.90GHz      | 4         | 0.88%   |
| Intel Core i7-2630QM CPU @ 2.00GHz      | 4         | 0.88%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz      | 4         | 0.88%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 4         | 0.88%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 4         | 0.88%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 4         | 0.88%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 4         | 0.88%   |
| AMD Ryzen 7 4700U with Radeon Graphics  | 4         | 0.88%   |
| AMD Ryzen 5 4500U with Radeon Graphics  | 4         | 0.88%   |
| Intel Core i7-8850H CPU @ 2.60GHz       | 3         | 0.66%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 3         | 0.66%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 3         | 0.66%   |
| Intel Core i7-4600U CPU @ 2.10GHz       | 3         | 0.66%   |
| Intel Core i7-4500U CPU @ 1.80GHz       | 3         | 0.66%   |
| Intel Core i7-2640M CPU @ 2.80GHz       | 3         | 0.66%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz       | 3         | 0.66%   |
| Intel Core i5-5257U CPU @ 2.70GHz       | 3         | 0.66%   |
| Intel Core i5-4310U CPU @ 2.00GHz       | 3         | 0.66%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 145       | 32.08%  |
| Intel Core i5           | 138       | 30.53%  |
| Other                   | 27        | 5.97%   |
| Intel Core i3           | 23        | 5.09%   |
| Intel Celeron           | 16        | 3.54%   |
| AMD Ryzen 7             | 14        | 3.1%    |
| Intel Core 2 Duo        | 12        | 2.65%   |
| AMD Ryzen 5             | 10        | 2.21%   |
| Intel Core i9           | 7         | 1.55%   |
| Intel Pentium           | 6         | 1.33%   |
| Intel Atom              | 6         | 1.33%   |
| AMD A8                  | 5         | 1.11%   |
| Intel Genuine           | 4         | 0.88%   |
| Intel Core 2            | 4         | 0.88%   |
| AMD Ryzen 7 PRO         | 4         | 0.88%   |
| Intel Pentium Dual-Core | 3         | 0.66%   |
| AMD A6                  | 3         | 0.66%   |
| AMD Turion 64 X2 Mobile | 2         | 0.44%   |
| AMD Ryzen 3             | 2         | 0.44%   |
| AMD Phenom II           | 2         | 0.44%   |
| AMD E2                  | 2         | 0.44%   |
| AMD E                   | 2         | 0.44%   |
| Intel Xeon              | 1         | 0.22%   |
| Intel Pentium Silver    | 1         | 0.22%   |
| Intel Pentium Gold      | 1         | 0.22%   |
| Intel Core M            | 1         | 0.22%   |
| Intel Core 2 Solo       | 1         | 0.22%   |
| Intel Celeron Dual-Core | 1         | 0.22%   |
| AMD V160                | 1         | 0.22%   |
| AMD V120                | 1         | 0.22%   |
| AMD Ryzen 9             | 1         | 0.22%   |
| AMD Ryzen 5 PRO         | 1         | 0.22%   |
| AMD E1                  | 1         | 0.22%   |
| AMD Athlon II           | 1         | 0.22%   |
| AMD Athlon 64 X2        | 1         | 0.22%   |
| AMD Athlon              | 1         | 0.22%   |
| AMD A10                 | 1         | 0.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 225       | 49.78%  |
| 4      | 143       | 31.64%  |
| 6      | 46        | 10.18%  |
| 8      | 23        | 5.09%   |
| 1      | 8         | 1.77%   |
| 12     | 3         | 0.66%   |
| 14     | 2         | 0.44%   |
| 10     | 1         | 0.22%   |
| 3      | 1         | 0.22%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 452       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 361       | 79.69%  |
| 1      | 91        | 20.09%  |
| 8      | 1         | 0.22%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 439       | 96.91%  |
| Unknown        | 9         | 1.99%   |
| 32-bit         | 5         | 1.1%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 113       | 24.15%  |
| 0x206a7    | 27        | 5.77%   |
| 0x906ea    | 25        | 5.34%   |
| 0x306a9    | 24        | 5.13%   |
| 0x406e3    | 20        | 4.27%   |
| 0x40651    | 20        | 4.27%   |
| 0x806ec    | 18        | 3.85%   |
| 0x806ea    | 17        | 3.63%   |
| 0x306d4    | 15        | 3.21%   |
| 0x806e9    | 14        | 2.99%   |
| 0x20655    | 12        | 2.56%   |
| 0xa0652    | 11        | 2.35%   |
| 0x506e3    | 11        | 2.35%   |
| 0x1067a    | 11        | 2.35%   |
| 0x306c3    | 10        | 2.14%   |
| 0x806c1    | 9         | 1.92%   |
| 0x906e9    | 8         | 1.71%   |
| 0x806eb    | 7         | 1.5%    |
| 0x806d1    | 6         | 1.28%   |
| 0x20652    | 5         | 1.07%   |
| 0x08600103 | 5         | 1.07%   |
| 0x010000c8 | 5         | 1.07%   |
| 0x906ed    | 4         | 0.85%   |
| 0x906a3    | 4         | 0.85%   |
| 0x08600106 | 4         | 0.85%   |
| 0x05000119 | 4         | 0.85%   |
| 0x506c9    | 3         | 0.64%   |
| 0x08600104 | 3         | 0.64%   |
| 0x08108109 | 3         | 0.64%   |
| 0x08108102 | 3         | 0.64%   |
| 0x706a8    | 2         | 0.43%   |
| 0x706a1    | 2         | 0.43%   |
| 0x6fd      | 2         | 0.43%   |
| 0x6f6      | 2         | 0.43%   |
| 0x406c4    | 2         | 0.43%   |
| 0x406c3    | 2         | 0.43%   |
| 0x30678    | 2         | 0.43%   |
| 0x106e5    | 2         | 0.43%   |
| 0x106ca    | 2         | 0.43%   |
| 0x10676    | 2         | 0.43%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 116       | 25.49%  |
| Skylake          | 42        | 9.23%   |
| Haswell          | 42        | 9.23%   |
| SandyBridge      | 33        | 7.25%   |
| IvyBridge        | 32        | 7.03%   |
| Broadwell        | 23        | 5.05%   |
| Westmere         | 19        | 4.18%   |
| Zen 2            | 17        | 3.74%   |
| Penryn           | 16        | 3.52%   |
| TigerLake        | 14        | 3.08%   |
| CometLake        | 11        | 2.42%   |
| Unknown          | 9         | 1.98%   |
| Zen+             | 8         | 1.76%   |
| Silvermont       | 8         | 1.76%   |
| Icelake          | 7         | 1.54%   |
| Goldmont plus    | 6         | 1.32%   |
| Core             | 6         | 1.32%   |
| K10              | 5         | 1.1%    |
| Alderlake Hybrid | 5         | 1.1%    |
| Zen 3            | 4         | 0.88%   |
| Bonnell          | 4         | 0.88%   |
| Bobcat           | 4         | 0.88%   |
| Piledriver       | 3         | 0.66%   |
| P6               | 3         | 0.66%   |
| Nehalem          | 3         | 0.66%   |
| K8 Hammer        | 3         | 0.66%   |
| Goldmont         | 3         | 0.66%   |
| Excavator        | 3         | 0.66%   |
| K10 Llano        | 2         | 0.44%   |
| Zen              | 1         | 0.22%   |
| Steamroller      | 1         | 0.22%   |
| Puma             | 1         | 0.22%   |
| Jaguar           | 1         | 0.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 356       | 61.27%  |
| Nvidia | 144       | 24.78%  |
| AMD    | 81        | 13.94%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 31        | 5.21%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 28        | 4.71%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 28        | 4.71%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 27        | 4.54%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 25        | 4.2%    |
| Intel UHD Graphics 620                                                                   | 25        | 4.2%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 23        | 3.87%   |
| Intel HD Graphics 620                                                                    | 19        | 3.19%   |
| Intel HD Graphics 5500                                                                   | 18        | 3.03%   |
| AMD Renoir                                                                               | 17        | 2.86%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 14        | 2.35%   |
| Intel HD Graphics 530                                                                    | 13        | 2.18%   |
| Intel Core Processor Integrated Graphics Controller                                      | 13        | 2.18%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 12        | 2.02%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 11        | 1.85%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 10        | 1.68%   |
| Nvidia GP108M [GeForce MX150]                                                            | 8         | 1.34%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 8         | 1.34%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 8         | 1.34%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 6         | 1.01%   |
| Intel HD Graphics 630                                                                    | 6         | 1.01%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 1.01%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 5         | 0.84%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 5         | 0.84%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 5         | 0.84%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 5         | 0.84%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 5         | 0.84%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 5         | 0.84%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 5         | 0.84%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 0.84%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 0.84%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 5         | 0.84%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 4         | 0.67%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                    | 4         | 0.67%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 4         | 0.67%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 4         | 0.67%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 4         | 0.67%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 4         | 0.67%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 4         | 0.67%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 230       | 50.77%  |
| Intel + Nvidia | 112       | 24.72%  |
| 1 x AMD        | 55        | 12.14%  |
| 1 x Nvidia     | 28        | 6.18%   |
| Intel + AMD    | 14        | 3.09%   |
| 2 x AMD        | 9         | 1.99%   |
| AMD + Nvidia   | 4         | 0.88%   |
| Other          | 1         | 0.22%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 364       | 79.48%  |
| Proprietary | 81        | 17.69%  |
| Unknown     | 13        | 2.84%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 303       | 66.01%  |
| 1.01-2.0   | 49        | 10.68%  |
| 0.01-0.5   | 43        | 9.37%   |
| 3.01-4.0   | 30        | 6.54%   |
| 0.51-1.0   | 19        | 4.14%   |
| 5.01-6.0   | 8         | 1.74%   |
| 7.01-8.0   | 4         | 0.87%   |
| 2.01-3.0   | 2         | 0.44%   |
| 16.01-24.0 | 1         | 0.22%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 94        | 17.38%  |
| AU Optronics            | 89        | 16.45%  |
| Chimei Innolux          | 60        | 11.09%  |
| BOE                     | 51        | 9.43%   |
| Samsung Electronics     | 50        | 9.24%   |
| Sharp                   | 26        | 4.81%   |
| Dell                    | 21        | 3.88%   |
| Lenovo                  | 20        | 3.7%    |
| Apple                   | 16        | 2.96%   |
| Hewlett-Packard         | 13        | 2.4%    |
| AOC                     | 10        | 1.85%   |
| InfoVision              | 9         | 1.66%   |
| Chi Mei Optoelectronics | 8         | 1.48%   |
| BenQ                    | 8         | 1.48%   |
| JDI                     | 7         | 1.29%   |
| Ancor Communications    | 7         | 1.29%   |
| Philips                 | 6         | 1.11%   |
| PANDA                   | 6         | 1.11%   |
| Acer                    | 6         | 1.11%   |
| Goldstar                | 5         | 0.92%   |
| CSO                     | 5         | 0.92%   |
| Sony                    | 2         | 0.37%   |
| MiTAC                   | 2         | 0.37%   |
| HannStar                | 2         | 0.37%   |
| Grundig                 | 2         | 0.37%   |
| VOXICON                 | 1         | 0.18%   |
| Vestel Elektronik       | 1         | 0.18%   |
| Toshiba                 | 1         | 0.18%   |
| Tatung                  | 1         | 0.18%   |
| SSD                     | 1         | 0.18%   |
| Seiko/Epson             | 1         | 0.18%   |
| S2-Tek                  | 1         | 0.18%   |
| Panasonic               | 1         | 0.18%   |
| MSI                     | 1         | 0.18%   |
| LGD                     | 1         | 0.18%   |
| LG Philips              | 1         | 0.18%   |
| Fujitsu Siemens         | 1         | 0.18%   |
| CVTE                    | 1         | 0.18%   |
| CTO                     | 1         | 0.18%   |
| CMN                     | 1         | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch               | 7         | 1.28%   |
| JDI LCD Monitor JDI422A 3000x2000 293x196mm 13.9-inch                 | 6         | 1.09%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 5         | 0.91%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch        | 5         | 0.91%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 4         | 0.73%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 4         | 0.73%   |
| AU Optronics LCD Monitor AUO80ED 1920x1080 344x193mm 15.5-inch        | 4         | 0.73%   |
| AU Optronics LCD Monitor AUO313D 1920x1080 309x174mm 14.0-inch        | 4         | 0.73%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch               | 3         | 0.55%   |
| Samsung Electronics LCD Monitor SEC3859 1366x768 293x165mm 13.2-inch  | 3         | 0.55%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x174mm 14.0-inch  | 3         | 0.55%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch          | 3         | 0.55%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 3         | 0.55%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 3         | 0.55%   |
| LG Display LCD Monitor LGD0354 1366x768 293x165mm 13.2-inch           | 3         | 0.55%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch           | 3         | 0.55%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch               | 3         | 0.55%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch               | 3         | 0.55%   |
| Dell U2718Q DELA0EC 3840x2160 609x349mm 27.6-inch                     | 3         | 0.55%   |
| Dell U2717D DEL40EA 2560x1440 597x336mm 27.0-inch                     | 3         | 0.55%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch      | 3         | 0.55%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 3         | 0.55%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch      | 3         | 0.55%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 3         | 0.55%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 3         | 0.55%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 3         | 0.55%   |
| AOC Q32G1WG4 AOC3201 2560x1440 697x393mm 31.5-inch                    | 3         | 0.55%   |
| Sharp LCD Monitor SHP1516 3840x2400 336x210mm 15.6-inch               | 2         | 0.36%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 2         | 0.36%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 2         | 0.36%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch | 2         | 0.36%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch               | 2         | 0.36%   |
| LG Display LCD Monitor LGD056D 1920x1080 382x215mm 17.3-inch          | 2         | 0.36%   |
| LG Display LCD Monitor LGD0446 1920x1080 309x174mm 14.0-inch          | 2         | 0.36%   |
| LG Display LCD Monitor LGD032C 1920x1080 344x194mm 15.5-inch          | 2         | 0.36%   |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch           | 2         | 0.36%   |
| LG Display LCD Monitor LGD02D9 1920x1080 344x194mm 15.5-inch          | 2         | 0.36%   |
| LG Display LCD Monitor LGD02D3 1366x768 277x156mm 12.5-inch           | 2         | 0.36%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch              | 2         | 0.36%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch               | 2         | 0.36%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 238       | 46.58%  |
| 1366x768 (WXGA)   | 95        | 18.59%  |
| 3840x2160 (4K)    | 38        | 7.44%   |
| 1600x900 (HD+)    | 30        | 5.87%   |
| 2560x1440 (QHD)   | 20        | 3.91%   |
| 1920x1200 (WUXGA) | 16        | 3.13%   |
| 1280x800 (WXGA)   | 13        | 2.54%   |
| 3000x2000         | 7         | 1.37%   |
| 1440x900 (WXGA+)  | 7         | 1.37%   |
| 3840x2400         | 6         | 1.17%   |
| 2880x1800         | 6         | 1.17%   |
| 2560x1600         | 6         | 1.17%   |
| 2160x1440         | 4         | 0.78%   |
| 1280x1024 (SXGA)  | 4         | 0.78%   |
| 1024x600          | 4         | 0.78%   |
| 3440x1440         | 2         | 0.39%   |
| 1920x540          | 2         | 0.39%   |
| 1360x768          | 2         | 0.39%   |
| Unknown           | 2         | 0.39%   |
| 9600x2160         | 1         | 0.2%    |
| 3840x1600         | 1         | 0.2%    |
| 3840x1100         | 1         | 0.2%    |
| 3840x1080         | 1         | 0.2%    |
| 2646x1024         | 1         | 0.2%    |
| 2560x1080         | 1         | 0.2%    |
| 2304x1440         | 1         | 0.2%    |
| 2048x1152         | 1         | 0.2%    |
| 1280x720 (HD)     | 1         | 0.2%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 177       | 32.84%  |
| 13      | 91        | 16.88%  |
| 14      | 84        | 15.58%  |
| 27      | 37        | 6.86%   |
| 17      | 34        | 6.31%   |
| 12      | 31        | 5.75%   |
| 24      | 24        | 4.45%   |
| Unknown | 8         | 1.48%   |
| 31      | 6         | 1.11%   |
| 23      | 6         | 1.11%   |
| 25      | 3         | 0.56%   |
| 11      | 3         | 0.56%   |
| 10      | 3         | 0.56%   |
| 84      | 2         | 0.37%   |
| 72      | 2         | 0.37%   |
| 54      | 2         | 0.37%   |
| 48      | 2         | 0.37%   |
| 43      | 2         | 0.37%   |
| 34      | 2         | 0.37%   |
| 32      | 2         | 0.37%   |
| 26      | 2         | 0.37%   |
| 21      | 2         | 0.37%   |
| 19      | 2         | 0.37%   |
| 60      | 1         | 0.19%   |
| 55      | 1         | 0.19%   |
| 42      | 1         | 0.19%   |
| 40      | 1         | 0.19%   |
| 39      | 1         | 0.19%   |
| 37      | 1         | 0.19%   |
| 36      | 1         | 0.19%   |
| 28      | 1         | 0.19%   |
| 22      | 1         | 0.19%   |
| 18      | 1         | 0.19%   |
| 16      | 1         | 0.19%   |
| 8       | 1         | 0.19%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 298       | 55.81%  |
| 201-300     | 87        | 16.29%  |
| 501-600     | 61        | 11.42%  |
| 351-400     | 41        | 7.68%   |
| 601-700     | 13        | 2.43%   |
| Unknown     | 8         | 1.5%    |
| 1001-1500   | 6         | 1.12%   |
| 701-800     | 5         | 0.94%   |
| 401-500     | 4         | 0.75%   |
| 1501-2000   | 4         | 0.75%   |
| 801-900     | 3         | 0.56%   |
| 901-1000    | 3         | 0.56%   |
| 101-200     | 1         | 0.19%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 382       | 82.15%  |
| 16/10   | 52        | 11.18%  |
| 3/2     | 14        | 3.01%   |
| Unknown | 6         | 1.29%   |
| 5/4     | 5         | 1.08%   |
| 21/9    | 4         | 0.86%   |
| 32/9    | 1         | 0.22%   |
| 3.40    | 1         | 0.22%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 174       | 32.34%  |
| 81-90          | 137       | 25.46%  |
| 71-80          | 38        | 7.06%   |
| 301-350        | 37        | 6.88%   |
| 61-70          | 30        | 5.58%   |
| 121-130        | 30        | 5.58%   |
| 201-250        | 24        | 4.46%   |
| 251-300        | 13        | 2.42%   |
| 351-500        | 11        | 2.04%   |
| More than 1000 | 9         | 1.67%   |
| Unknown        | 8         | 1.49%   |
| 501-1000       | 7         | 1.3%    |
| 51-60          | 4         | 0.74%   |
| 41-50          | 3         | 0.56%   |
| 141-150        | 3         | 0.56%   |
| 131-140        | 3         | 0.56%   |
| 111-120        | 3         | 0.56%   |
| 151-200        | 2         | 0.37%   |
| 1-40           | 1         | 0.19%   |
| 91-100         | 1         | 0.19%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 253       | 47.56%  |
| 101-120       | 107       | 20.11%  |
| 51-100        | 80        | 15.04%  |
| 161-240       | 41        | 7.71%   |
| More than 240 | 37        | 6.95%   |
| Unknown       | 8         | 1.5%    |
| 1-50          | 6         | 1.13%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 343       | 73.92%  |
| 2     | 93        | 20.04%  |
| 3     | 15        | 3.23%   |
| 0     | 13        | 2.8%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 304       | 43.18%  |
| Realtek Semiconductor             | 172       | 24.43%  |
| Qualcomm Atheros                  | 71        | 10.09%  |
| Broadcom                          | 46        | 6.53%   |
| Broadcom Limited                  | 19        | 2.7%    |
| Ericsson Business Mobile Networks | 14        | 1.99%   |
| Dell                              | 12        | 1.7%    |
| Sierra Wireless                   | 11        | 1.56%   |
| Lenovo                            | 6         | 0.85%   |
| Ralink                            | 5         | 0.71%   |
| Hewlett-Packard                   | 5         | 0.71%   |
| ASUSTek Computer                  | 5         | 0.71%   |
| Marvell Technology Group          | 4         | 0.57%   |
| FIBOCOM                           | 4         | 0.57%   |
| DisplayLink                       | 4         | 0.57%   |
| Ralink Technology                 | 3         | 0.43%   |
| Qualcomm                          | 3         | 0.43%   |
| MediaTek                          | 3         | 0.43%   |
| Nvidia                            | 2         | 0.28%   |
| NetGear                           | 2         | 0.28%   |
| JMicron Technology                | 2         | 0.28%   |
| TP-Link                           | 1         | 0.14%   |
| T & A Mobile Phones               | 1         | 0.14%   |
| Samsung Electronics               | 1         | 0.14%   |
| Qualcomm Atheros Communications   | 1         | 0.14%   |
| Microsoft                         | 1         | 0.14%   |
| Huawei Technologies               | 1         | 0.14%   |
| D-Link                            | 1         | 0.14%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                              | Notebooks | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller  | 116       | 13.02%  |
| Intel Wireless 8265 / 8275                                         | 36        | 4.04%   |
| Intel Wi-Fi 6 AX200                                                | 32        | 3.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)              | 31        | 3.48%   |
| Intel Wireless 8260                                                | 25        | 2.81%   |
| Intel Wireless 7265                                                | 24        | 2.69%   |
| Intel Wireless 7260                                                | 24        | 2.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                       | 19        | 2.13%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                           | 18        | 2.02%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller              | 17        | 1.91%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                           | 16        | 1.8%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)     | 14        | 1.57%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter         | 13        | 1.46%   |
| Intel Centrino Ultimate-N 6300                                     | 13        | 1.46%   |
| Intel Ethernet Connection I218-LM                                  | 12        | 1.35%   |
| Intel Cannon Lake PCH CNVi WiFi                                    | 12        | 1.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter         | 11        | 1.23%   |
| Intel Ethernet Connection I219-LM                                  | 11        | 1.23%   |
| Intel Ethernet Connection (4) I219-V                               | 11        | 1.23%   |
| Intel Ethernet Connection (4) I219-LM                              | 11        | 1.23%   |
| Intel Ethernet Connection (6) I219-V                               | 10        | 1.12%   |
| Intel Ethernet Connection (3) I218-LM                              | 10        | 1.12%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter         | 9         | 1.01%   |
| Intel Wireless-AC 9260                                             | 9         | 1.01%   |
| Intel Comet Lake PCH CNVi WiFi                                     | 9         | 1.01%   |
| Intel 82577LM Gigabit Network Connection                           | 9         | 1.01%   |
| Intel WiFi Link 5100                                               | 8         | 0.9%    |
| Intel Wi-Fi 6 AX201                                                | 8         | 0.9%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                | 8         | 0.9%    |
| Ericsson Business Mobile Networks F5521gw                          | 7         | 0.79%   |
| Broadcom BCM43228 802.11a/b/g/n                                    | 7         | 0.79%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter           | 6         | 0.67%   |
| Intel Wireless 3165                                                | 6         | 0.67%   |
| Intel Ethernet Connection I219-V                                   | 6         | 0.67%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                  | 6         | 0.67%   |
| Intel Alder Lake-P PCH CNVi WiFi                                   | 6         | 0.67%   |
| Ericsson Business Mobile Networks H5321 gw Mobile Broadband Driver | 6         | 0.67%   |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A                | 5         | 0.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter           | 5         | 0.56%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                    | 5         | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 293       | 59.67%  |
| Qualcomm Atheros                | 60        | 12.22%  |
| Broadcom                        | 38        | 7.74%   |
| Realtek Semiconductor           | 36        | 7.33%   |
| Broadcom Limited                | 16        | 3.26%   |
| Sierra Wireless                 | 11        | 2.24%   |
| Dell                            | 7         | 1.43%   |
| Ralink                          | 5         | 1.02%   |
| ASUSTek Computer                | 5         | 1.02%   |
| FIBOCOM                         | 4         | 0.81%   |
| Ralink Technology               | 3         | 0.61%   |
| Qualcomm                        | 3         | 0.61%   |
| MediaTek                        | 3         | 0.61%   |
| NetGear                         | 2         | 0.41%   |
| Hewlett-Packard                 | 2         | 0.41%   |
| TP-Link                         | 1         | 0.2%    |
| Qualcomm Atheros Communications | 1         | 0.2%    |
| Microsoft                       | 1         | 0.2%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 36        | 7.33%   |
| Intel Wi-Fi 6 AX200                                            | 32        | 6.52%   |
| Intel Wireless 8260                                            | 25        | 5.09%   |
| Intel Wireless 7265                                            | 24        | 4.89%   |
| Intel Wireless 7260                                            | 24        | 4.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 19        | 3.87%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 16        | 3.26%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 14        | 2.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 13        | 2.65%   |
| Intel Centrino Ultimate-N 6300                                 | 13        | 2.65%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 12        | 2.44%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 11        | 2.24%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 9         | 1.83%   |
| Intel Wireless-AC 9260                                         | 9         | 1.83%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 9         | 1.83%   |
| Intel WiFi Link 5100                                           | 8         | 1.63%   |
| Intel Wi-Fi 6 AX201                                            | 8         | 1.63%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 8         | 1.63%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 7         | 1.43%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 6         | 1.22%   |
| Intel Wireless 3165                                            | 6         | 1.22%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 6         | 1.22%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 6         | 1.22%   |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A            | 5         | 1.02%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 5         | 1.02%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 5         | 1.02%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 5         | 1.02%   |
| Intel Centrino Advanced-N 6235                                 | 5         | 1.02%   |
| Sierra Wireless EM7345 4G LTE                                  | 4         | 0.81%   |
| Intel Wireless 3160                                            | 4         | 0.81%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 4         | 0.81%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 4         | 0.81%   |
| Intel Centrino Advanced-N 6200                                 | 4         | 0.81%   |
| FIBOCOM L830-EB                                                | 4         | 0.81%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                           | 4         | 0.81%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 4         | 0.81%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter     | 4         | 0.81%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 4         | 0.81%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 4         | 0.81%   |
| ASUS 802.11ac NIC                                              | 4         | 0.81%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 156       | 41.27%  |
| Realtek Semiconductor    | 153       | 40.48%  |
| Qualcomm Atheros         | 24        | 6.35%   |
| Broadcom                 | 18        | 4.76%   |
| Lenovo                   | 6         | 1.59%   |
| Broadcom Limited         | 5         | 1.32%   |
| Marvell Technology Group | 4         | 1.06%   |
| DisplayLink              | 4         | 1.06%   |
| Nvidia                   | 2         | 0.53%   |
| JMicron Technology       | 2         | 0.53%   |
| T & A Mobile Phones      | 1         | 0.26%   |
| Samsung Electronics      | 1         | 0.26%   |
| Huawei Technologies      | 1         | 0.26%   |
| D-Link                   | 1         | 0.26%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 116       | 30.69%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 31        | 8.2%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 18        | 4.76%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 17        | 4.5%    |
| Intel Ethernet Connection I218-LM                                 | 12        | 3.17%   |
| Intel Ethernet Connection I219-LM                                 | 11        | 2.91%   |
| Intel Ethernet Connection (4) I219-V                              | 11        | 2.91%   |
| Intel Ethernet Connection (4) I219-LM                             | 11        | 2.91%   |
| Intel Ethernet Connection (6) I219-V                              | 10        | 2.65%   |
| Intel Ethernet Connection (3) I218-LM                             | 10        | 2.65%   |
| Intel 82577LM Gigabit Network Connection                          | 9         | 2.38%   |
| Intel Ethernet Connection I219-V                                  | 6         | 1.59%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 1.32%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 4         | 1.06%   |
| Intel Ethernet Connection (3) I218-V                              | 4         | 1.06%   |
| Intel Ethernet Connection (2) I219-LM                             | 4         | 1.06%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 1.06%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 4         | 1.06%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 3         | 0.79%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 0.79%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 0.79%   |
| Intel Ethernet Connection (7) I219-LM                             | 3         | 0.79%   |
| Intel Ethernet Connection (6) I219-LM                             | 3         | 0.79%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 3         | 0.79%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.53%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.53%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.53%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 2         | 0.53%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 0.53%   |
| Lenovo ThinkPad TBT3 LAN                                          | 2         | 0.53%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 2         | 0.53%   |
| Intel PRO/100 VE Network Connection                               | 2         | 0.53%   |
| Intel Ethernet controller                                         | 2         | 0.53%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 0.53%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 0.53%   |
| Intel Ethernet Connection (10) I219-LM                            | 2         | 0.53%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 0.53%   |
| Intel 82577LC Gigabit Network Connection                          | 2         | 0.53%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.53%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2         | 0.53%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 448       | 53.59%  |
| Ethernet | 366       | 43.78%  |
| Modem    | 21        | 2.51%   |
| Unknown  | 1         | 0.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 399       | 83.3%   |
| Ethernet | 80        | 16.7%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 335       | 73.95%  |
| 1     | 112       | 24.72%  |
| 3     | 4         | 0.88%   |
| 0     | 2         | 0.44%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 414       | 89.42%  |
| Yes  | 49        | 10.58%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 211       | 57.34%  |
| Broadcom                        | 41        | 11.14%  |
| Qualcomm Atheros Communications | 16        | 4.35%   |
| Realtek Semiconductor           | 15        | 4.08%   |
| Lite-On Technology              | 14        | 3.8%    |
| Apple                           | 13        | 3.53%   |
| IMC Networks                    | 12        | 3.26%   |
| Foxconn / Hon Hai               | 12        | 3.26%   |
| Hewlett-Packard                 | 11        | 2.99%   |
| Dell                            | 10        | 2.72%   |
| ASUSTek Computer                | 6         | 1.63%   |
| Realtek                         | 2         | 0.54%   |
| Cambridge Silicon Radio         | 2         | 0.54%   |
| Ralink Technology               | 1         | 0.27%   |
| Ralink                          | 1         | 0.27%   |
| MediaTek                        | 1         | 0.27%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 101       | 27.45%  |
| Intel AX200 Bluetooth                               | 31        | 8.42%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 28        | 7.61%   |
| Intel AX201 Bluetooth                               | 27        | 7.34%   |
| Broadcom BCM2045B (BDC-2.1)                         | 12        | 3.26%   |
| Realtek Bluetooth Radio                             | 11        | 2.99%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 9         | 2.45%   |
| HP Broadcom 2070 Bluetooth Combo                    | 8         | 2.17%   |
| Apple Bluetooth Host Controller                     | 8         | 2.17%   |
| Lite-On Bluetooth Device                            | 7         | 1.9%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 7         | 1.9%    |
| Foxconn / Hon Hai Bluetooth Device                  | 6         | 1.63%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 5         | 1.36%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 5         | 1.36%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 5         | 1.36%   |
| Intel Bluetooth Device                              | 5         | 1.36%   |
| IMC Networks Bluetooth Radio                        | 5         | 1.36%   |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 1.09%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 4         | 1.09%   |
| Dell BCM20702A0 Bluetooth Module                    | 4         | 1.09%   |
| Broadcom BCM20702A0                                 | 4         | 1.09%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 4         | 1.09%   |
| Intel AX210 Bluetooth                               | 3         | 0.82%   |
| IMC Networks Bluetooth Device                       | 3         | 0.82%   |
| Dell DW375 Bluetooth Module                         | 3         | 0.82%   |
| Broadcom BCM43142A0 Bluetooth Device                | 3         | 0.82%   |
| Apple Bluetooth USB Host Controller                 | 3         | 0.82%   |
| Realtek Bluetooth Radio                             | 2         | 0.54%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 2         | 0.54%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 0.54%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 2         | 0.54%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 0.54%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 2         | 0.54%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 0.54%   |
| Broadcom HP Portable SoftSailing                    | 2         | 0.54%   |
| Broadcom HP Portable Bumble Bee                     | 2         | 0.54%   |
| Broadcom BCM20702A0 Bluetooth                       | 2         | 0.54%   |
| ASUS BT-270 Bluetooth Adapter                       | 2         | 0.54%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 2         | 0.54%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 390       | 68.3%   |
| AMD                         | 70        | 12.26%  |
| Nvidia                      | 66        | 11.56%  |
| Realtek Semiconductor       | 9         | 1.58%   |
| Lenovo                      | 9         | 1.58%   |
| Logitech                    | 5         | 0.88%   |
| Kingston Technology         | 5         | 0.88%   |
| GN Netcom                   | 2         | 0.35%   |
| C-Media Electronics         | 2         | 0.35%   |
| Sony                        | 1         | 0.18%   |
| Sonicstar                   | 1         | 0.18%   |
| Roland                      | 1         | 0.18%   |
| ROCCAT                      | 1         | 0.18%   |
| Razer USA                   | 1         | 0.18%   |
| NAD                         | 1         | 0.18%   |
| Mark of the Unicorn         | 1         | 0.18%   |
| Hewlett-Packard             | 1         | 0.18%   |
| Focusrite-Novation          | 1         | 0.18%   |
| FiiO Electronics Technology | 1         | 0.18%   |
| Drop                        | 1         | 0.18%   |
| Corsair                     | 1         | 0.18%   |
| Conexant Systems            | 1         | 0.18%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 74        | 10.85%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 35        | 5.13%   |
| AMD Family 17h/19h HD Audio Controller                                     | 32        | 4.69%   |
| Intel Cannon Lake PCH cAVS                                                 | 31        | 4.55%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 30        | 4.4%    |
| Intel Haswell-ULT HD Audio Controller                                      | 27        | 3.96%   |
| Intel 8 Series HD Audio Controller                                         | 27        | 3.96%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 25        | 3.67%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 23        | 3.37%   |
| Intel Broadwell-U Audio Controller                                         | 23        | 3.37%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 22        | 3.23%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 22        | 3.23%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 16        | 2.35%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 15        | 2.2%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 14        | 2.05%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 13        | 1.91%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 12        | 1.76%   |
| Intel Comet Lake PCH cAVS                                                  | 11        | 1.61%   |
| AMD FCH Azalia Controller                                                  | 11        | 1.61%   |
| Realtek Semiconductor USB Audio                                            | 9         | 1.32%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 9         | 1.32%   |
| Intel CM238 HD Audio Controller                                            | 9         | 1.32%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 9         | 1.32%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 8         | 1.17%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 7         | 1.03%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 7         | 1.03%   |
| Nvidia TU106 High Definition Audio Controller                              | 6         | 0.88%   |
| Nvidia GP107GL High Definition Audio Controller                            | 6         | 0.88%   |
| Nvidia GF108 High Definition Audio Controller                              | 6         | 0.88%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 6         | 0.88%   |
| Intel Comet Lake PCH-LP cAVS                                               | 6         | 0.88%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 6         | 0.88%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 6         | 0.88%   |
| Nvidia TU116 High Definition Audio Controller                              | 5         | 0.73%   |
| Nvidia GT216 HDMI Audio Controller                                         | 5         | 0.73%   |
| Kingston Technology HyperX 7.1 Audio                                       | 4         | 0.59%   |
| Nvidia GK106 HDMI Audio Controller                                         | 3         | 0.44%   |
| Nvidia GF119 HDMI Audio Controller                                         | 3         | 0.44%   |
| Nvidia GA104 High Definition Audio Controller                              | 3         | 0.44%   |
| Lenovo ThinkPad Dock USB Audio                                             | 3         | 0.44%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 104       | 37.68%  |
| SK hynix            | 72        | 26.09%  |
| Micron Technology   | 35        | 12.68%  |
| Kingston            | 20        | 7.25%   |
| Unknown             | 12        | 4.35%   |
| Elpida              | 8         | 2.9%    |
| Crucial             | 7         | 2.54%   |
| Corsair             | 4         | 1.45%   |
| A-DATA Technology   | 4         | 1.45%   |
| Ramaxel Technology  | 3         | 1.09%   |
| Unknown (ABCD)      | 1         | 0.36%   |
| Transcend           | 1         | 0.36%   |
| Toshiba             | 1         | 0.36%   |
| Team                | 1         | 0.36%   |
| Nanya Technology    | 1         | 0.36%   |
| ASint Technology    | 1         | 0.36%   |
| 48spaces            | 1         | 0.36%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s              | 6         | 2.08%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 5         | 1.74%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 5         | 1.74%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 5         | 1.74%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 5         | 1.74%   |
| Unknown RAM Module 4GB Chip DDR4 2133MT/s                           | 4         | 1.39%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 4         | 1.39%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 4         | 1.39%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s       | 4         | 1.39%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 1.04%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 3         | 1.04%   |
| SK hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 3         | 1.04%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 3         | 1.04%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8192MB SODIMM DDR4 2667MT/s           | 3         | 1.04%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 3         | 1.04%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                      | 3         | 1.04%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 3         | 1.04%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 3         | 1.04%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 3         | 1.04%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 3         | 1.04%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 3         | 1.04%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 3         | 1.04%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 0.69%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 2         | 0.69%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 0.69%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s              | 2         | 0.69%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 2         | 0.69%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s             | 2         | 0.69%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 2         | 0.69%   |
| SK hynix RAM H9CCNNNBJTALAR-NVD 4GB Row Of Chips LPDDR3 2133MT/s    | 2         | 0.69%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2667MT/s                     | 2         | 0.69%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 4199MT/s               | 2         | 0.69%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 2         | 0.69%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 0.69%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 2         | 0.69%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s              | 2         | 0.69%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s              | 2         | 0.69%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 0.69%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 2         | 0.69%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s               | 2         | 0.69%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 114       | 47.9%   |
| DDR3    | 80        | 33.61%  |
| LPDDR3  | 23        | 9.66%   |
| LPDDR4  | 9         | 3.78%   |
| DDR2    | 4         | 1.68%   |
| SDRAM   | 3         | 1.26%   |
| LPDDR5  | 3         | 1.26%   |
| DDR5    | 1         | 0.42%   |
| Unknown | 1         | 0.42%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 197       | 81.4%   |
| Row Of Chips | 34        | 14.05%  |
| Chip         | 9         | 3.72%   |
| Unknown      | 2         | 0.83%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 98        | 39.04%  |
| 4096  | 87        | 34.66%  |
| 16384 | 42        | 16.73%  |
| 2048  | 18        | 7.17%   |
| 32768 | 5         | 1.99%   |
| 1024  | 1         | 0.4%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 65        | 25.49%  |
| 1600  | 59        | 23.14%  |
| 2133  | 36        | 14.12%  |
| 3200  | 30        | 11.76%  |
| 2400  | 12        | 4.71%   |
| 1867  | 10        | 3.92%   |
| 1334  | 10        | 3.92%   |
| 1333  | 6         | 2.35%   |
| 1067  | 4         | 1.57%   |
| 6400  | 3         | 1.18%   |
| 4267  | 3         | 1.18%   |
| 4199  | 3         | 1.18%   |
| 667   | 3         | 1.18%   |
| 8400  | 2         | 0.78%   |
| 4266  | 2         | 0.78%   |
| 3266  | 2         | 0.78%   |
| 1066  | 2         | 0.78%   |
| 4800  | 1         | 0.39%   |
| 1866  | 1         | 0.39%   |
| 975   | 1         | 0.39%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 2         | 50%     |
| Brother Industries | 2         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                     | Notebooks | Percent |
|---------------------------|-----------|---------|
| HP Printing Support       | 1         | 25%     |
| HP ENVY Photo 6200 series | 1         | 25%     |
| Brother PT-2450DX         | 1         | 25%     |
| Brother HL-1210W series   | 1         | 25%     |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 105       | 24.82%  |
| Acer                                   | 52        | 12.29%  |
| IMC Networks                           | 44        | 10.4%   |
| Microdia                               | 32        | 7.57%   |
| Sunplus Innovation Technology          | 29        | 6.86%   |
| Realtek Semiconductor                  | 21        | 4.96%   |
| Cheng Uei Precision Industry (Foxlink) | 20        | 4.73%   |
| Quanta                                 | 18        | 4.26%   |
| Lite-On Technology                     | 18        | 4.26%   |
| Suyin                                  | 13        | 3.07%   |
| Apple                                  | 12        | 2.84%   |
| Lenovo                                 | 11        | 2.6%    |
| Logitech                               | 9         | 2.13%   |
| Luxvisions Innotech Limited            | 5         | 1.18%   |
| Alcor Micro                            | 5         | 1.18%   |
| Samsung Electronics                    | 4         | 0.95%   |
| Primax Electronics                     | 4         | 0.95%   |
| Silicon Motion                         | 3         | 0.71%   |
| Syntek                                 | 2         | 0.47%   |
| Sonix Technology                       | 2         | 0.47%   |
| Ricoh                                  | 2         | 0.47%   |
| Microsoft                              | 2         | 0.47%   |
| Generalplus Technology                 | 2         | 0.47%   |
| ALi                                    | 2         | 0.47%   |
| Z-Star Microelectronics                | 1         | 0.24%   |
| Unknown                                | 1         | 0.24%   |
| Sunplus Technology                     | 1         | 0.24%   |
| Mustek Systems                         | 1         | 0.24%   |
| Intel                                  | 1         | 0.24%   |
| Creative Technology                    | 1         | 0.24%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 36        | 8.45%   |
| Microdia Integrated_Webcam_HD                       | 21        | 4.93%   |
| IMC Networks Integrated Camera                      | 16        | 3.76%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 12        | 2.82%   |
| Sunplus Integrated_Webcam_HD                        | 11        | 2.58%   |
| Chicony HP HD Camera                                | 11        | 2.58%   |
| Chicony HP HD Webcam                                | 10        | 2.35%   |
| Lite-On Integrated Camera                           | 9         | 2.11%   |
| Acer Integrated Camera                              | 9         | 2.11%   |
| Realtek Integrated_Webcam_HD                        | 8         | 1.88%   |
| Chicony HD Webcam                                   | 8         | 1.88%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera    | 7         | 1.64%   |
| Acer Lenovo EasyCamera                              | 7         | 1.64%   |
| Acer BisonCam, NB Pro                               | 7         | 1.64%   |
| Lenovo Integrated Webcam [R5U877]                   | 6         | 1.41%   |
| Sunplus HD WebCam                                   | 5         | 1.17%   |
| Quanta HD User Facing                               | 5         | 1.17%   |
| Microdia Integrated Webcam                          | 5         | 1.17%   |
| Lite-On HP HD Camera                                | 5         | 1.17%   |
| Chicony Integrated HP HD Webcam                     | 5         | 1.17%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 5         | 1.17%   |
| Apple iPhone 5/5C/5S/6/SE                           | 5         | 1.17%   |
| Acer SunplusIT Integrated Camera                    | 5         | 1.17%   |
| Acer Lenovo Integrated Webcam                       | 5         | 1.17%   |
| Sunplus Asus Webcam                                 | 4         | 0.94%   |
| Samsung Galaxy series, misc. (MTP mode)             | 4         | 0.94%   |
| Primax HP HD Webcam [Fixed]                         | 4         | 0.94%   |
| Luxvisions Innotech Limited HP HD Camera            | 4         | 0.94%   |
| Lite-On HP HD Webcam                                | 4         | 0.94%   |
| Acer HD Webcam                                      | 4         | 0.94%   |
| Sunplus Laptop Integrated Webcam HD                 | 3         | 0.7%    |
| Quanta HP HD Camera                                 | 3         | 0.7%    |
| Quanta HD Webcam                                    | 3         | 0.7%    |
| Lenovo Integrated Webcam                            | 3         | 0.7%    |
| IMC Networks USB camera                             | 3         | 0.7%    |
| Chicony Lenovo Integrated Camera (0.3MP)            | 3         | 0.7%    |
| Chicony Integrated Camera (1280x720@30)             | 3         | 0.7%    |
| Chicony HP Wide Vision HD Camera                    | 3         | 0.7%    |
| Acer EasyCamera                                     | 3         | 0.7%    |
| Suyin USB 2.0 Camera                                | 2         | 0.47%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 52        | 42.28%  |
| Synaptics                  | 36        | 29.27%  |
| Upek                       | 15        | 12.2%   |
| Shenzhen Goodix Technology | 9         | 7.32%   |
| Elan Microelectronics      | 5         | 4.07%   |
| AuthenTec                  | 3         | 2.44%   |
| LighTuning Technology      | 2         | 1.63%   |
| Samsung Electronics        | 1         | 0.81%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 18        | 14.63%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 14        | 11.38%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 13        | 10.57%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 12        | 9.76%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 7         | 5.69%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 5.69%   |
| Shenzhen Goodix FingerPrint                                                | 5         | 4.07%   |
| Elan ELAN:Fingerprint                                                      | 5         | 4.07%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 3.25%   |
| Validity Sensors Synaptics WBDI                                            | 4         | 3.25%   |
| Unknown                                                                    | 4         | 3.25%   |
| Validity Sensors VFS491                                                    | 3         | 2.44%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 2.44%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 3         | 2.44%   |
| Shenzhen Goodix  Fingerprint Device                                        | 3         | 2.44%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 1.63%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 1.63%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 1.63%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 1.63%   |
| AuthenTec AES2810                                                          | 2         | 1.63%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.81%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.81%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.81%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 0.81%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 0.81%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.81%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 0.81%   |
| AuthenTec AES1600                                                          | 1         | 0.81%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 23        | 39.66%  |
| Broadcom              | 22        | 37.93%  |
| Upek                  | 7         | 12.07%  |
| Lenovo                | 5         | 8.62%   |
| Gemalto (was Gemplus) | 1         | 1.72%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 23        | 39.66%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 9         | 15.52%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 7         | 12.07%  |
| Broadcom 5880                                                                | 7         | 12.07%  |
| Lenovo Integrated Smart Card Reader                                          | 5         | 8.62%   |
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 5.17%   |
| Broadcom 58200                                                               | 3         | 5.17%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.72%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 251       | 53.86%  |
| 1     | 161       | 34.55%  |
| 2     | 45        | 9.66%   |
| 3     | 9         | 1.93%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 123       | 46.42%  |
| Chipcard              | 50        | 18.87%  |
| Graphics card         | 39        | 14.72%  |
| Net/wireless          | 21        | 7.92%   |
| Multimedia controller | 12        | 4.53%   |
| Camera                | 7         | 2.64%   |
| Card reader           | 6         | 2.26%   |
| Storage               | 3         | 1.13%   |
| Net/ethernet          | 2         | 0.75%   |
| Sound                 | 1         | 0.38%   |
| Bluetooth             | 1         | 0.38%   |

