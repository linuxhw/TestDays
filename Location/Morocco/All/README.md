Linux in Morocco - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Morocco.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Morocco/Desktop/README.md) and [notebooks](/Location/Morocco/Notebook/README.md).

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

Total: 710

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | 1494                        | Desktop     | [e32d33455b](https://linux-hardware.org/?probe=e32d33455b) | Dec 22, 2025 |
| Microsoft     | Surface Laptop              | Tablet      | [a42ed283a2](https://linux-hardware.org/?probe=a42ed283a2) | Dec 18, 2025 |
| Lenovo        | ThinkPad L13 Gen 1 20R3S... | Notebook    | [453805a2c2](https://linux-hardware.org/?probe=453805a2c2) | Dec 17, 2025 |
| HP            | EliteBook 840 G5            | Notebook    | [f2cf9843ce](https://linux-hardware.org/?probe=f2cf9843ce) | Dec 16, 2025 |
| HP            | 3397                        | Desktop     | [7deb053b0b](https://linux-hardware.org/?probe=7deb053b0b) | Dec 16, 2025 |
| Dell          | Vostro 5620                 | Notebook    | [19a68d6339](https://linux-hardware.org/?probe=19a68d6339) | Dec 15, 2025 |
| Dell          | Latitude 5410               | Notebook    | [1780df9b4f](https://linux-hardware.org/?probe=1780df9b4f) | Dec 15, 2025 |
| Dell          | 0WR7PY A03                  | Desktop     | [64001fab76](https://linux-hardware.org/?probe=64001fab76) | Dec 15, 2025 |
| Dell          | Precision M4800             | Notebook    | [b0ccbd6f89](https://linux-hardware.org/?probe=b0ccbd6f89) | Dec 13, 2025 |
| Acer          | Nitro AN515-51              | Notebook    | [d8cae4c49b](https://linux-hardware.org/?probe=d8cae4c49b) | Dec 12, 2025 |
| Apple         | MacBookPro12,1              | Notebook    | [a9d8f51c71](https://linux-hardware.org/?probe=a9d8f51c71) | Dec 08, 2025 |
| MSI           | Cyborg 15 A13VFK            | Notebook    | [5902ddb8c1](https://linux-hardware.org/?probe=5902ddb8c1) | Dec 07, 2025 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [d7e95ddd34](https://linux-hardware.org/?probe=d7e95ddd34) | Dec 06, 2025 |
| HP            | 250 G4                      | Notebook    | [f015980d3c](https://linux-hardware.org/?probe=f015980d3c) | Dec 02, 2025 |
| Lenovo        | Yoga Pro 7 14APH8 82Y8      | Notebook    | [f5b8800286](https://linux-hardware.org/?probe=f5b8800286) | Nov 30, 2025 |
| ASUSTek       | K52Jc                       | Notebook    | [56b3a4c466](https://linux-hardware.org/?probe=56b3a4c466) | Nov 30, 2025 |
| ASUSTek       | K52Jc                       | Notebook    | [c098c92aab](https://linux-hardware.org/?probe=c098c92aab) | Nov 29, 2025 |
| HP            | 09F0h                       | Desktop     | [610ddb1849](https://linux-hardware.org/?probe=610ddb1849) | Nov 29, 2025 |
| Lenovo        | ThinkPad L13 Gen 1 20R3S... | Notebook    | [d3a8af3d73](https://linux-hardware.org/?probe=d3a8af3d73) | Nov 28, 2025 |
| Acer          | Nitro ANV15-51              | Notebook    | [92988cd7a1](https://linux-hardware.org/?probe=92988cd7a1) | Nov 27, 2025 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [c3f71f07fa](https://linux-hardware.org/?probe=c3f71f07fa) | Nov 23, 2025 |
| Lenovo        | ThinkPad L13 Gen 1 20R3S... | Notebook    | [ce4c3a852c](https://linux-hardware.org/?probe=ce4c3a852c) | Nov 18, 2025 |
| HP            | EliteBook 830 G6            | Notebook    | [2756765643](https://linux-hardware.org/?probe=2756765643) | Nov 16, 2025 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [b27a742abd](https://linux-hardware.org/?probe=b27a742abd) | Nov 13, 2025 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [f1ca8ef6bc](https://linux-hardware.org/?probe=f1ca8ef6bc) | Nov 10, 2025 |
| HP            | EliteBook 830 G7 Noteboo... | Notebook    | [61f2929dd9](https://linux-hardware.org/?probe=61f2929dd9) | Nov 09, 2025 |
| Apple         | MacBookPro9,1               | Notebook    | [543b1b6b44](https://linux-hardware.org/?probe=543b1b6b44) | Nov 07, 2025 |
| HP            | 1589                        | Desktop     | [5f25d9db26](https://linux-hardware.org/?probe=5f25d9db26) | Nov 06, 2025 |
| HP            | 1589                        | Desktop     | [e2cb47a304](https://linux-hardware.org/?probe=e2cb47a304) | Nov 06, 2025 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | Notebook    | [667441173b](https://linux-hardware.org/?probe=667441173b) | Nov 03, 2025 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | Notebook    | [bc5ebebe56](https://linux-hardware.org/?probe=bc5ebebe56) | Nov 03, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop K550... | Notebook    | [2a060689fb](https://linux-hardware.org/?probe=2a060689fb) | Oct 30, 2025 |
| Packard Be... | EasyNote TJ65               | Notebook    | [1b426a6f41](https://linux-hardware.org/?probe=1b426a6f41) | Oct 29, 2025 |
| HP            | 15                          | Notebook    | [fcd5131120](https://linux-hardware.org/?probe=fcd5131120) | Oct 26, 2025 |
| HP            | 15                          | Notebook    | [e37f4e9f3b](https://linux-hardware.org/?probe=e37f4e9f3b) | Oct 26, 2025 |
| ASUSTek       | X751LJ                      | Notebook    | [f0348e2454](https://linux-hardware.org/?probe=f0348e2454) | Oct 25, 2025 |
| HP            | 8299                        | Desktop     | [7d241d83ab](https://linux-hardware.org/?probe=7d241d83ab) | Oct 23, 2025 |
| Dell          | Latitude E7270              | Notebook    | [47a17048ad](https://linux-hardware.org/?probe=47a17048ad) | Oct 23, 2025 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [2f6599e33e](https://linux-hardware.org/?probe=2f6599e33e) | Oct 19, 2025 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [f32cd477b8](https://linux-hardware.org/?probe=f32cd477b8) | Oct 19, 2025 |
| HP            | ProBook 4530s               | Notebook    | [5be57cd4ab](https://linux-hardware.org/?probe=5be57cd4ab) | Oct 18, 2025 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [24adec3cdb](https://linux-hardware.org/?probe=24adec3cdb) | Oct 18, 2025 |
| Pegatron      | 2AD5                        | Desktop     | [076872dfa1](https://linux-hardware.org/?probe=076872dfa1) | Oct 16, 2025 |
| Lenovo        | ThinkPad T14 Gen 4 21K4S... | Notebook    | [035d8be55f](https://linux-hardware.org/?probe=035d8be55f) | Oct 14, 2025 |
| Acer          | Aspire E5-571               | Notebook    | [91f7345324](https://linux-hardware.org/?probe=91f7345324) | Oct 10, 2025 |
| Acer          | TravelMate 3040             | Notebook    | [89302c24f3](https://linux-hardware.org/?probe=89302c24f3) | Oct 09, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [005026698e](https://linux-hardware.org/?probe=005026698e) | Oct 09, 2025 |
| Lenovo        | ThinkPad T480s 20L8S1QX0... | Notebook    | [f15b88c78d](https://linux-hardware.org/?probe=f15b88c78d) | Oct 08, 2025 |
| Shenzhen M... | F7BSC                       | Mini pc     | [708c5bb3a2](https://linux-hardware.org/?probe=708c5bb3a2) | Oct 06, 2025 |
| HP            | 304Ah                       | Desktop     | [b0c4041aaa](https://linux-hardware.org/?probe=b0c4041aaa) | Oct 03, 2025 |
| HP            | 0AACh                       | Desktop     | [95233ca98a](https://linux-hardware.org/?probe=95233ca98a) | Sep 29, 2025 |
| HP            | EliteBook 830 G5            | Notebook    | [73bd4bc6e3](https://linux-hardware.org/?probe=73bd4bc6e3) | Sep 29, 2025 |
| HP            | EliteBook 840 G5            | Notebook    | [2961f20b6e](https://linux-hardware.org/?probe=2961f20b6e) | Sep 28, 2025 |
| HP            | EliteBook 840 G5            | Notebook    | [755bd2060a](https://linux-hardware.org/?probe=755bd2060a) | Sep 23, 2025 |
| Dell          | Latitude 3520               | Notebook    | [0d41b49c2d](https://linux-hardware.org/?probe=0d41b49c2d) | Sep 21, 2025 |
| Dell          | 04YP6J A02                  | Desktop     | [eea42cabee](https://linux-hardware.org/?probe=eea42cabee) | Sep 17, 2025 |
| MSI           | PRO A620M-E                 | Desktop     | [b3c97fa479](https://linux-hardware.org/?probe=b3c97fa479) | Sep 10, 2025 |
| MSI           | PRO A620M-E                 | Desktop     | [1a9efed61f](https://linux-hardware.org/?probe=1a9efed61f) | Sep 09, 2025 |
| Pegatron      | 2AD5                        | Desktop     | [911a5acdf2](https://linux-hardware.org/?probe=911a5acdf2) | Aug 26, 2025 |
| Fujitsu       | LIFEBOOK S710               | Notebook    | [226b5ddf14](https://linux-hardware.org/?probe=226b5ddf14) | Aug 25, 2025 |
| Fujitsu       | LIFEBOOK S710               | Notebook    | [c4b4548f63](https://linux-hardware.org/?probe=c4b4548f63) | Aug 25, 2025 |
| InnJoo Tec... | LeapBook A100               | Notebook    | [8689175ea7](https://linux-hardware.org/?probe=8689175ea7) | Aug 25, 2025 |
| Dell          | Latitude 3420               | Notebook    | [03c8355499](https://linux-hardware.org/?probe=03c8355499) | Aug 23, 2025 |
| HP            | 250 G3                      | Notebook    | [1353b8cc05](https://linux-hardware.org/?probe=1353b8cc05) | Aug 22, 2025 |
| Acer          | Aspire 7750G                | Notebook    | [b92992269d](https://linux-hardware.org/?probe=b92992269d) | Aug 16, 2025 |
| MSI           | B450M-A PRO MAX II          | Desktop     | [356282aab4](https://linux-hardware.org/?probe=356282aab4) | Aug 15, 2025 |
| Dell          | 0KC9NP A01                  | Desktop     | [480c11206c](https://linux-hardware.org/?probe=480c11206c) | Aug 14, 2025 |
| Shenzhen M... | F7BSC                       | Mini pc     | [333493ce10](https://linux-hardware.org/?probe=333493ce10) | Aug 12, 2025 |
| Samsung       | R520/R522/R620              | Notebook    | [4dd0921343](https://linux-hardware.org/?probe=4dd0921343) | Aug 11, 2025 |
| HONOR         | NMH-WDX9                    | Notebook    | [3aecbd42e4](https://linux-hardware.org/?probe=3aecbd42e4) | Aug 11, 2025 |
| TUXEDO        | InfinityBook S 14 v5        | Notebook    | [aec801fbb2](https://linux-hardware.org/?probe=aec801fbb2) | Aug 11, 2025 |
| Pegatron      | 2AD5                        | Desktop     | [1b6084fb84](https://linux-hardware.org/?probe=1b6084fb84) | Aug 01, 2025 |
| Dell          | Latitude E6540              | Notebook    | [0ebaf61703](https://linux-hardware.org/?probe=0ebaf61703) | Jul 28, 2025 |
| Packard Be... | EasyNote TS44HR             | Notebook    | [75d8a5514e](https://linux-hardware.org/?probe=75d8a5514e) | Jul 27, 2025 |
| Dell          | Latitude E7450              | Notebook    | [029f64453f](https://linux-hardware.org/?probe=029f64453f) | Jul 14, 2025 |
| Gigabyte      | B760 DS3H AX DDR4           | Desktop     | [2461a88a30](https://linux-hardware.org/?probe=2461a88a30) | Jul 13, 2025 |
| Foxconn       | 2ADA                        | Desktop     | [3c89640d98](https://linux-hardware.org/?probe=3c89640d98) | Jul 05, 2025 |
| ASUSTek       | ROG Strix G731GT_G731GT     | Notebook    | [af279e0b13](https://linux-hardware.org/?probe=af279e0b13) | Jul 04, 2025 |
| Lenovo        | ThinkPad P16 Gen 1 21D7S... | Notebook    | [ff6d865b08](https://linux-hardware.org/?probe=ff6d865b08) | Jun 27, 2025 |
| HP            | ProBook 450 G5              | Notebook    | [5f70582ba0](https://linux-hardware.org/?probe=5f70582ba0) | Jun 26, 2025 |
| HP            | ProBook 450 G5              | Notebook    | [6e23047148](https://linux-hardware.org/?probe=6e23047148) | Jun 25, 2025 |
| Pegatron      | 2A73h                       | Desktop     | [b2f513c983](https://linux-hardware.org/?probe=b2f513c983) | Jun 22, 2025 |
| Dell          | G15 5530                    | Notebook    | [9d909179f6](https://linux-hardware.org/?probe=9d909179f6) | Jun 21, 2025 |
| Dell          | G15 5530                    | Notebook    | [d2aedbfe4b](https://linux-hardware.org/?probe=d2aedbfe4b) | Jun 21, 2025 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [8ea4cf9a41](https://linux-hardware.org/?probe=8ea4cf9a41) | Jun 14, 2025 |
| HP            | EliteBook x360 1040 G7 N... | Convertible | [bbe4e62557](https://linux-hardware.org/?probe=bbe4e62557) | Jun 11, 2025 |
| Acer          | Veriton M2640G V:1.0        | Desktop     | [1afb0d8968](https://linux-hardware.org/?probe=1afb0d8968) | Jun 11, 2025 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [d602e008c4](https://linux-hardware.org/?probe=d602e008c4) | Jun 09, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop K550... | Notebook    | [6608283a6f](https://linux-hardware.org/?probe=6608283a6f) | Jun 05, 2025 |
| HP            | ZBook 17 G5                 | Notebook    | [d1da183e06](https://linux-hardware.org/?probe=d1da183e06) | Jun 03, 2025 |
| Dell          | Latitude E5550              | Notebook    | [b65aa76fdd](https://linux-hardware.org/?probe=b65aa76fdd) | May 30, 2025 |
| Lenovo        | ThinkPad X9-15 Gen 1 21Q... | Notebook    | [d599bc9225](https://linux-hardware.org/?probe=d599bc9225) | May 30, 2025 |
| Medion        | Deputy P60                  | Notebook    | [de230fe1d6](https://linux-hardware.org/?probe=de230fe1d6) | May 26, 2025 |
| HP            | EliteBook x360 1040 G7 N... | Convertible | [538b86fe96](https://linux-hardware.org/?probe=538b86fe96) | May 24, 2025 |
| HP            | 212B                        | Desktop     | [905bb62926](https://linux-hardware.org/?probe=905bb62926) | May 24, 2025 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | Notebook    | [d6e4d0040a](https://linux-hardware.org/?probe=d6e4d0040a) | May 23, 2025 |
| Lenovo        | LOQ 15ARP9 83JC             | Notebook    | [86e55ec780](https://linux-hardware.org/?probe=86e55ec780) | May 17, 2025 |
| HP            | 18E7                        | Desktop     | [81b687a9f8](https://linux-hardware.org/?probe=81b687a9f8) | May 16, 2025 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | Notebook    | [c2f9a990f4](https://linux-hardware.org/?probe=c2f9a990f4) | May 13, 2025 |
| Lenovo        | ThinkPad T480s 20L8002AM... | Notebook    | [3fea75bfb6](https://linux-hardware.org/?probe=3fea75bfb6) | May 10, 2025 |
| Dell          | 0Y5DDC A00                  | Desktop     | [023a9d827b](https://linux-hardware.org/?probe=023a9d827b) | May 10, 2025 |
| Acer          | Nitro ANV15-51              | Notebook    | [5a61054a4e](https://linux-hardware.org/?probe=5a61054a4e) | May 08, 2025 |
| Acer          | Nitro ANV15-51              | Notebook    | [83659b1ed2](https://linux-hardware.org/?probe=83659b1ed2) | May 08, 2025 |
| Lenovo        | Legion 5 15ARP8 83EF        | Notebook    | [11da9879dd](https://linux-hardware.org/?probe=11da9879dd) | May 07, 2025 |
| Acer          | Aspire VN7-592G             | Notebook    | [7119eb8ee2](https://linux-hardware.org/?probe=7119eb8ee2) | May 07, 2025 |
| Dell          | Precision M4800             | Notebook    | [a10a92bd94](https://linux-hardware.org/?probe=a10a92bd94) | May 04, 2025 |
| Dell          | 0MN1TX A01                  | Desktop     | [74ae783308](https://linux-hardware.org/?probe=74ae783308) | Apr 30, 2025 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [45a2563f6d](https://linux-hardware.org/?probe=45a2563f6d) | Apr 30, 2025 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [a4ddfd0ffb](https://linux-hardware.org/?probe=a4ddfd0ffb) | Apr 28, 2025 |
| MSI           | B450M-A PRO MAX II          | Desktop     | [6874de2afa](https://linux-hardware.org/?probe=6874de2afa) | Apr 27, 2025 |
| Dell          | Vostro 3400                 | Notebook    | [556772bb8b](https://linux-hardware.org/?probe=556772bb8b) | Apr 27, 2025 |
| Dell          | Precision M4800             | Notebook    | [396676851e](https://linux-hardware.org/?probe=396676851e) | Apr 27, 2025 |
| Dell          | Vostro 3400                 | Notebook    | [cc26bf4f4c](https://linux-hardware.org/?probe=cc26bf4f4c) | Apr 23, 2025 |
| Dell          | 05YDCW A01                  | Desktop     | [fc545c965a](https://linux-hardware.org/?probe=fc545c965a) | Apr 20, 2025 |
| Dell          | 05YDCW A01                  | Desktop     | [9dc75fa0db](https://linux-hardware.org/?probe=9dc75fa0db) | Apr 20, 2025 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [340120df0b](https://linux-hardware.org/?probe=340120df0b) | Apr 17, 2025 |
| HP            | ZBook 15 G3                 | Notebook    | [a35f480c86](https://linux-hardware.org/?probe=a35f480c86) | Apr 10, 2025 |
| Dell          | 0KC9NP A01                  | Desktop     | [397773ae54](https://linux-hardware.org/?probe=397773ae54) | Apr 06, 2025 |
| Lenovo        | ThinkPad T470 20JNS00U0D    | Notebook    | [1614b9e507](https://linux-hardware.org/?probe=1614b9e507) | Mar 29, 2025 |
| Microsoft     | Surface Pro                 | Tablet      | [7a4aa60293](https://linux-hardware.org/?probe=7a4aa60293) | Mar 26, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [5d39519f05](https://linux-hardware.org/?probe=5d39519f05) | Mar 25, 2025 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [9b4356118a](https://linux-hardware.org/?probe=9b4356118a) | Mar 23, 2025 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [00586776cb](https://linux-hardware.org/?probe=00586776cb) | Mar 13, 2025 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [561990fd99](https://linux-hardware.org/?probe=561990fd99) | Mar 10, 2025 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [7dc9a8e543](https://linux-hardware.org/?probe=7dc9a8e543) | Mar 07, 2025 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [178350bae4](https://linux-hardware.org/?probe=178350bae4) | Mar 07, 2025 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [df31951584](https://linux-hardware.org/?probe=df31951584) | Feb 28, 2025 |
| Fujitsu       | LIFEBOOK U7511              | Notebook    | [9c9f33279a](https://linux-hardware.org/?probe=9c9f33279a) | Feb 21, 2025 |
| Gateway       | DT71                        | Desktop     | [cacb1c4c18](https://linux-hardware.org/?probe=cacb1c4c18) | Feb 21, 2025 |
| Gateway       | DT71                        | Desktop     | [c1ffdc7907](https://linux-hardware.org/?probe=c1ffdc7907) | Feb 21, 2025 |
| Lenovo        | ThinkPad T460 20FMS2B900    | Notebook    | [4727c8c9b6](https://linux-hardware.org/?probe=4727c8c9b6) | Feb 20, 2025 |
| HP            | EliteBook 840 G2            | Notebook    | [a95bcf56f4](https://linux-hardware.org/?probe=a95bcf56f4) | Feb 12, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [8d4ffcee41](https://linux-hardware.org/?probe=8d4ffcee41) | Feb 09, 2025 |
| Dell          | Latitude 7410               | Notebook    | [626618a422](https://linux-hardware.org/?probe=626618a422) | Feb 09, 2025 |
| Dell          | Latitude 5420               | Notebook    | [6c020c51d8](https://linux-hardware.org/?probe=6c020c51d8) | Feb 05, 2025 |
| Lenovo        | Yoga 520-14IKB 81C8         | Convertible | [ae97ea9ec1](https://linux-hardware.org/?probe=ae97ea9ec1) | Feb 03, 2025 |
| Dell          | Precision M4600             | Notebook    | [62888308aa](https://linux-hardware.org/?probe=62888308aa) | Feb 02, 2025 |
| Lenovo        | G510 20238                  | Notebook    | [00db8ad84b](https://linux-hardware.org/?probe=00db8ad84b) | Jan 15, 2025 |
| HP            | ProBook 640 G5              | Notebook    | [aea76733f3](https://linux-hardware.org/?probe=aea76733f3) | Jan 15, 2025 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [78a05e3b0e](https://linux-hardware.org/?probe=78a05e3b0e) | Jan 07, 2025 |
| Dell          | OptiPlex 745                | Desktop     | [578cc6d8f1](https://linux-hardware.org/?probe=578cc6d8f1) | Jan 06, 2025 |
| HP            | ProBook 650 G2              | Notebook    | [b2fc855e3e](https://linux-hardware.org/?probe=b2fc855e3e) | Jan 03, 2025 |
| Dell          | Vostro 1500                 | Notebook    | [b5ecc28563](https://linux-hardware.org/?probe=b5ecc28563) | Dec 31, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [b007439528](https://linux-hardware.org/?probe=b007439528) | Dec 26, 2024 |
| HP            | 8B4D 100                    | All in one  | [24eb20636b](https://linux-hardware.org/?probe=24eb20636b) | Dec 25, 2024 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [91cdbe5df9](https://linux-hardware.org/?probe=91cdbe5df9) | Dec 25, 2024 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [32e2211a4c](https://linux-hardware.org/?probe=32e2211a4c) | Dec 25, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JN0... | Notebook    | [dae98f533a](https://linux-hardware.org/?probe=dae98f533a) | Dec 19, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JN0... | Notebook    | [5655debff7](https://linux-hardware.org/?probe=5655debff7) | Dec 19, 2024 |
| Toshiba       | Satellite C55-B             | Notebook    | [524c33e748](https://linux-hardware.org/?probe=524c33e748) | Dec 16, 2024 |
| HP            | 8054                        | Desktop     | [3196c09967](https://linux-hardware.org/?probe=3196c09967) | Dec 16, 2024 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [3c936aa4e5](https://linux-hardware.org/?probe=3c936aa4e5) | Dec 16, 2024 |
| HP            | ProBook 6570b               | Notebook    | [70dbe6620b](https://linux-hardware.org/?probe=70dbe6620b) | Dec 14, 2024 |
| HP            | G62                         | Notebook    | [70f9d38537](https://linux-hardware.org/?probe=70f9d38537) | Dec 11, 2024 |
| HP            | Pavilion dv6                | Notebook    | [92fe6246ab](https://linux-hardware.org/?probe=92fe6246ab) | Dec 09, 2024 |
| Lenovo        | ThinkPad X1 Tablet 20GHS... | Tablet      | [18960c0bf8](https://linux-hardware.org/?probe=18960c0bf8) | Dec 08, 2024 |
| HP            | Pavilion g6                 | Notebook    | [36c4171d06](https://linux-hardware.org/?probe=36c4171d06) | Nov 21, 2024 |
| HP            | ProBook 6560b               | Notebook    | [72ddcb1cf2](https://linux-hardware.org/?probe=72ddcb1cf2) | Nov 20, 2024 |
| Lenovo        | ThinkPad Yoga 370 20JJS1... | Convertible | [79d938cc3f](https://linux-hardware.org/?probe=79d938cc3f) | Nov 20, 2024 |
| HP            | 8055                        | Desktop     | [25559cfc60](https://linux-hardware.org/?probe=25559cfc60) | Nov 20, 2024 |
| Lenovo        | ThinkPad Yoga 370 20JJS1... | Convertible | [d5389c9065](https://linux-hardware.org/?probe=d5389c9065) | Nov 19, 2024 |
| Google        | Drawman                     | Notebook    | [46c461a6e2](https://linux-hardware.org/?probe=46c461a6e2) | Nov 18, 2024 |
| HP            | Notebook                    | Notebook    | [19d1189e7b](https://linux-hardware.org/?probe=19d1189e7b) | Nov 08, 2024 |
| Dell          | Latitude 7490               | Notebook    | [92bf691a6c](https://linux-hardware.org/?probe=92bf691a6c) | Nov 04, 2024 |
| Gigabyte      | H310M H x.x                 | Desktop     | [7e072971d7](https://linux-hardware.org/?probe=7e072971d7) | Nov 04, 2024 |
| HP            | Notebook                    | Notebook    | [abea0efa1e](https://linux-hardware.org/?probe=abea0efa1e) | Nov 01, 2024 |
| Dell          | Latitude 7490               | Notebook    | [ce28c4199d](https://linux-hardware.org/?probe=ce28c4199d) | Oct 29, 2024 |
| Samsung       | N150/N210/N220              | Notebook    | [eef263185a](https://linux-hardware.org/?probe=eef263185a) | Oct 22, 2024 |
| Lenovo        | IdeaPad Slim 5 14IRL8 82... | Notebook    | [62c3d2eddd](https://linux-hardware.org/?probe=62c3d2eddd) | Oct 17, 2024 |
| Dell          | Latitude 5420               | Notebook    | [622540975d](https://linux-hardware.org/?probe=622540975d) | Oct 10, 2024 |
| HP            | EliteBook 840 G5            | Notebook    | [533e95fac4](https://linux-hardware.org/?probe=533e95fac4) | Oct 09, 2024 |
| HP            | EliteBook 840 G5            | Notebook    | [c40e4f6c66](https://linux-hardware.org/?probe=c40e4f6c66) | Oct 09, 2024 |
| HP            | 8057                        | All in one  | [83a63f311a](https://linux-hardware.org/?probe=83a63f311a) | Oct 08, 2024 |
| HP            | 18E4                        | Desktop     | [9b22068827](https://linux-hardware.org/?probe=9b22068827) | Oct 04, 2024 |
| HP            | EliteBook 8470p             | Notebook    | [f71728ea0e](https://linux-hardware.org/?probe=f71728ea0e) | Sep 20, 2024 |
| Packard Be... | ENNS44HR                    | Notebook    | [b47db91782](https://linux-hardware.org/?probe=b47db91782) | Sep 20, 2024 |
| Dell          | Latitude 7490               | Notebook    | [2e22221506](https://linux-hardware.org/?probe=2e22221506) | Sep 19, 2024 |
| Dell          | Latitude 7490               | Notebook    | [b8cce215a5](https://linux-hardware.org/?probe=b8cce215a5) | Sep 18, 2024 |
| Dell          | XPS 15 9550                 | Notebook    | [266c779453](https://linux-hardware.org/?probe=266c779453) | Sep 12, 2024 |
| Dell          | 02YYK5 A00                  | Desktop     | [d75576c2f8](https://linux-hardware.org/?probe=d75576c2f8) | Sep 09, 2024 |
| Dell          | Inspiron 7548               | Notebook    | [150c9ec14f](https://linux-hardware.org/?probe=150c9ec14f) | Sep 09, 2024 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [4c19a63fee](https://linux-hardware.org/?probe=4c19a63fee) | Sep 02, 2024 |
| Unknown       | Unknown                     | Desktop     | [0f53ca6134](https://linux-hardware.org/?probe=0f53ca6134) | Aug 26, 2024 |
| HP            | EliteBook Folio 9480m       | Notebook    | [206392c090](https://linux-hardware.org/?probe=206392c090) | Aug 23, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | Notebook    | [e0af5cb80e](https://linux-hardware.org/?probe=e0af5cb80e) | Aug 19, 2024 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [c349c2ef99](https://linux-hardware.org/?probe=c349c2ef99) | Aug 17, 2024 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | Desktop     | [073d286abd](https://linux-hardware.org/?probe=073d286abd) | Aug 14, 2024 |
| Dell          | Precision M4600             | Notebook    | [fee987030c](https://linux-hardware.org/?probe=fee987030c) | Aug 12, 2024 |
| Dell          | Precision M4600             | Notebook    | [7decf1dba0](https://linux-hardware.org/?probe=7decf1dba0) | Aug 11, 2024 |
| Dell          | Latitude 5420               | Notebook    | [4017046879](https://linux-hardware.org/?probe=4017046879) | Aug 08, 2024 |
| HP            | 15                          | Notebook    | [89bd9fcc15](https://linux-hardware.org/?probe=89bd9fcc15) | Aug 05, 2024 |
| HP            | 15                          | Notebook    | [97a7e86ff2](https://linux-hardware.org/?probe=97a7e86ff2) | Aug 05, 2024 |
| HP            | 0B40h                       | Desktop     | [4e504e2f3a](https://linux-hardware.org/?probe=4e504e2f3a) | Aug 05, 2024 |
| HP            | 18E7                        | Desktop     | [a91cb43a38](https://linux-hardware.org/?probe=a91cb43a38) | Jul 30, 2024 |
| HP            | 18E7                        | Desktop     | [b426107c33](https://linux-hardware.org/?probe=b426107c33) | Jul 29, 2024 |
| HP            | 18E7                        | Desktop     | [5d7f84157a](https://linux-hardware.org/?probe=5d7f84157a) | Jul 27, 2024 |
| HP            | 18E7                        | Desktop     | [f1679be146](https://linux-hardware.org/?probe=f1679be146) | Jul 27, 2024 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [9eed9965d0](https://linux-hardware.org/?probe=9eed9965d0) | Jul 25, 2024 |
| HP            | 872C                        | Mini pc     | [89a2238ddd](https://linux-hardware.org/?probe=89a2238ddd) | Jul 25, 2024 |
| HP            | 872C                        | Mini pc     | [1357e6cd79](https://linux-hardware.org/?probe=1357e6cd79) | Jul 25, 2024 |
| Dell          | 0MN1TX A01                  | Desktop     | [99e899cbb0](https://linux-hardware.org/?probe=99e899cbb0) | Jul 22, 2024 |
| Toshiba       | Satellite C660              | Notebook    | [682ee2b1d0](https://linux-hardware.org/?probe=682ee2b1d0) | Jul 21, 2024 |
| Dell          | Vostro 3500                 | Notebook    | [8cafc4b7db](https://linux-hardware.org/?probe=8cafc4b7db) | Jul 19, 2024 |
| Lenovo        | Yoga Pro 9 16IMH9 83DN      | Notebook    | [add07540e5](https://linux-hardware.org/?probe=add07540e5) | Jul 09, 2024 |
| Lenovo        | Yoga Pro 9 16IMH9 83DN      | Notebook    | [efdb6c4558](https://linux-hardware.org/?probe=efdb6c4558) | Jul 06, 2024 |
| Acer          | Aspire E5-575G              | Notebook    | [b8bf8326fd](https://linux-hardware.org/?probe=b8bf8326fd) | Jul 06, 2024 |
| Lenovo        | Legion Pro 7 16IRX9H 83D... | Notebook    | [43fb16f634](https://linux-hardware.org/?probe=43fb16f634) | Jul 03, 2024 |
| Fujitsu       | LIFEBOOK U7511              | Notebook    | [e3ecabe043](https://linux-hardware.org/?probe=e3ecabe043) | Jun 19, 2024 |
| HP            | 0AA8h                       | Desktop     | [bb1f36cf41](https://linux-hardware.org/?probe=bb1f36cf41) | Jun 17, 2024 |
| HP            | EliteBook 8740w             | Notebook    | [158dce1091](https://linux-hardware.org/?probe=158dce1091) | Jun 17, 2024 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [8bf9046adc](https://linux-hardware.org/?probe=8bf9046adc) | Jun 02, 2024 |
| HP            | Laptop 15-bs0xx             | Notebook    | [d7bb8a4ea8](https://linux-hardware.org/?probe=d7bb8a4ea8) | May 17, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [5b949515c2](https://linux-hardware.org/?probe=5b949515c2) | May 11, 2024 |
| ASUSTek       | X550LD                      | Notebook    | [1c55e1acf7](https://linux-hardware.org/?probe=1c55e1acf7) | May 08, 2024 |
| HP            | Laptop 15-ra0xx             | Notebook    | [4d00a746ff](https://linux-hardware.org/?probe=4d00a746ff) | May 02, 2024 |
| MSI           | GS66 Stealth 10SE           | Notebook    | [e436c09a5c](https://linux-hardware.org/?probe=e436c09a5c) | Apr 30, 2024 |
| ACCENT        | SMART 140                   | Notebook    | [49fb07fe3f](https://linux-hardware.org/?probe=49fb07fe3f) | Apr 27, 2024 |
| Acer          | Aspire 7750G                | Notebook    | [961d70c1de](https://linux-hardware.org/?probe=961d70c1de) | Apr 27, 2024 |
| Acer          | Nitro AN515-46              | Notebook    | [0a90ca1966](https://linux-hardware.org/?probe=0a90ca1966) | Apr 23, 2024 |
| Dell          | Latitude E7240              | Notebook    | [71103e976e](https://linux-hardware.org/?probe=71103e976e) | Apr 21, 2024 |
| Dell          | 0V8F20 A01                  | Desktop     | [5b99cd208d](https://linux-hardware.org/?probe=5b99cd208d) | Apr 17, 2024 |
| HP            | ProBook 450 G0              | Notebook    | [686202a739](https://linux-hardware.org/?probe=686202a739) | Apr 13, 2024 |
| ASUSTek       | ZenBook UX482EG_UX482EG     | Notebook    | [c4c0c27585](https://linux-hardware.org/?probe=c4c0c27585) | Apr 13, 2024 |
| HP            | ProBook 450 G0              | Notebook    | [becdc6cf99](https://linux-hardware.org/?probe=becdc6cf99) | Apr 12, 2024 |
| HP            | Split 13 x2 Detachable P... | Notebook    | [17c8956856](https://linux-hardware.org/?probe=17c8956856) | Apr 12, 2024 |
| ASUSTek       | ZenBook UX482EG_UX482EG     | Notebook    | [4d6466d304](https://linux-hardware.org/?probe=4d6466d304) | Apr 10, 2024 |
| Lenovo        | 32E6 NOK                    | Desktop     | [b560c0d5fe](https://linux-hardware.org/?probe=b560c0d5fe) | Apr 09, 2024 |
| Lenovo        | 3740 NOK                    | Desktop     | [355c32d663](https://linux-hardware.org/?probe=355c32d663) | Apr 09, 2024 |
| HP            | ZBook 17 G5                 | Notebook    | [2b22c5c485](https://linux-hardware.org/?probe=2b22c5c485) | Apr 07, 2024 |
| Fujitsu       | LIFEBOOK S761               | Notebook    | [e73c5851aa](https://linux-hardware.org/?probe=e73c5851aa) | Mar 30, 2024 |
| Dell          | Inspiron 3421               | Notebook    | [a5606e10ad](https://linux-hardware.org/?probe=a5606e10ad) | Mar 27, 2024 |
| ASUSTek       | X550LD                      | Notebook    | [91112364b8](https://linux-hardware.org/?probe=91112364b8) | Mar 26, 2024 |
| ASUSTek       | X550LD                      | Notebook    | [1c72f8459c](https://linux-hardware.org/?probe=1c72f8459c) | Mar 26, 2024 |
| Dell          | Latitude 5480               | Notebook    | [ff785a4ce1](https://linux-hardware.org/?probe=ff785a4ce1) | Mar 22, 2024 |
| Acer          | Aspire E5-771G              | Notebook    | [3b5d0f6921](https://linux-hardware.org/?probe=3b5d0f6921) | Mar 19, 2024 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [0339864371](https://linux-hardware.org/?probe=0339864371) | Mar 09, 2024 |
| Dell          | Latitude 5289               | Notebook    | [fe338e3231](https://linux-hardware.org/?probe=fe338e3231) | Mar 09, 2024 |
| Gigabyte      | B450M S2H                   | Desktop     | [979a30bf92](https://linux-hardware.org/?probe=979a30bf92) | Mar 09, 2024 |
| Gigabyte      | B450M S2H                   | Desktop     | [66558a86e4](https://linux-hardware.org/?probe=66558a86e4) | Mar 09, 2024 |
| Dell          | Latitude E5550              | Notebook    | [4832591086](https://linux-hardware.org/?probe=4832591086) | Mar 08, 2024 |
| HP            | 212B                        | Desktop     | [781ec8e8f8](https://linux-hardware.org/?probe=781ec8e8f8) | Mar 07, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [e545b12914](https://linux-hardware.org/?probe=e545b12914) | Mar 07, 2024 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | Desktop     | [87afd5cfa6](https://linux-hardware.org/?probe=87afd5cfa6) | Mar 02, 2024 |
| ASUSTek       | Zenbook UX3404VA_Q420VA     | Notebook    | [f44261baba](https://linux-hardware.org/?probe=f44261baba) | Feb 24, 2024 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | Desktop     | [949f1cd85d](https://linux-hardware.org/?probe=949f1cd85d) | Feb 23, 2024 |
| Lenovo        | 32CB SDK0T76530 WIN 3556... | Desktop     | [c71cf6708c](https://linux-hardware.org/?probe=c71cf6708c) | Feb 19, 2024 |
| Lenovo        | ThinkPad T410 2537VTC       | Notebook    | [a393686fff](https://linux-hardware.org/?probe=a393686fff) | Feb 18, 2024 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | Desktop     | [2df79d1eff](https://linux-hardware.org/?probe=2df79d1eff) | Feb 17, 2024 |
| Acer          | Swift SFX14-51G             | Notebook    | [038f3ddc2e](https://linux-hardware.org/?probe=038f3ddc2e) | Feb 14, 2024 |
| HP            | EliteBook 850 G3            | Notebook    | [a3d2bf6949](https://linux-hardware.org/?probe=a3d2bf6949) | Feb 10, 2024 |
| Dell          | Latitude 5510               | Notebook    | [e0d5fe1c62](https://linux-hardware.org/?probe=e0d5fe1c62) | Feb 07, 2024 |
| HP            | 620                         | Notebook    | [523cfc94c0](https://linux-hardware.org/?probe=523cfc94c0) | Feb 03, 2024 |
| HP            | ProBook 5320m               | Notebook    | [3be604f862](https://linux-hardware.org/?probe=3be604f862) | Feb 03, 2024 |
| Lenovo        | 312A NOK                    | Desktop     | [366174cd75](https://linux-hardware.org/?probe=366174cd75) | Feb 02, 2024 |
| HP            | 15                          | Notebook    | [b99530abd5](https://linux-hardware.org/?probe=b99530abd5) | Feb 01, 2024 |
| HP            | 15                          | Notebook    | [874ae10280](https://linux-hardware.org/?probe=874ae10280) | Feb 01, 2024 |
| HP            | 620                         | Notebook    | [adcf9577e4](https://linux-hardware.org/?probe=adcf9577e4) | Feb 01, 2024 |
| ASUSTek       | X555LD                      | Notebook    | [e65c871d95](https://linux-hardware.org/?probe=e65c871d95) | Jan 31, 2024 |
| ASUSTek       | X555LD                      | Notebook    | [1433f11bba](https://linux-hardware.org/?probe=1433f11bba) | Jan 31, 2024 |
| Dell          | 02K9CR A01                  | Desktop     | [72df486f35](https://linux-hardware.org/?probe=72df486f35) | Jan 31, 2024 |
| Lenovo        | 312A NOK                    | Desktop     | [4cb29324fc](https://linux-hardware.org/?probe=4cb29324fc) | Jan 30, 2024 |
| Lenovo        | 312A NOK                    | Desktop     | [dea06ca305](https://linux-hardware.org/?probe=dea06ca305) | Jan 30, 2024 |
| Lenovo        | 312A NOK                    | Desktop     | [83eec08588](https://linux-hardware.org/?probe=83eec08588) | Jan 30, 2024 |
| Sony          | VPCF12A4E                   | Notebook    | [66fb5f96a0](https://linux-hardware.org/?probe=66fb5f96a0) | Jan 30, 2024 |
| HP            | ProBook 6560b               | Notebook    | [7b9f78e8df](https://linux-hardware.org/?probe=7b9f78e8df) | Jan 23, 2024 |
| HP            | EliteBook 840 G3            | Notebook    | [ea1922427f](https://linux-hardware.org/?probe=ea1922427f) | Jan 19, 2024 |
| Dell          | Latitude 7390               | Notebook    | [837b633afe](https://linux-hardware.org/?probe=837b633afe) | Jan 14, 2024 |
| HP            | EliteBook 830 G5            | Notebook    | [106a150b97](https://linux-hardware.org/?probe=106a150b97) | Jan 13, 2024 |
| HP            | EliteBook 840 G5            | Notebook    | [f6b222e444](https://linux-hardware.org/?probe=f6b222e444) | Jan 06, 2024 |
| HP            | EliteBook 840 G5            | Notebook    | [0af2ce345e](https://linux-hardware.org/?probe=0af2ce345e) | Jan 06, 2024 |
| HP            | ZBook Studio G3             | Notebook    | [21b560e443](https://linux-hardware.org/?probe=21b560e443) | Jan 04, 2024 |
| HP            | ProBook 640 G1              | Notebook    | [a6ba47a6e6](https://linux-hardware.org/?probe=a6ba47a6e6) | Jan 01, 2024 |
| HP            | 18E7                        | Desktop     | [f5115e035f](https://linux-hardware.org/?probe=f5115e035f) | Dec 30, 2023 |
| Dell          | Latitude E5470              | Notebook    | [71121b89c8](https://linux-hardware.org/?probe=71121b89c8) | Dec 25, 2023 |
| HP            | 090Ch                       | Desktop     | [06e9f893bc](https://linux-hardware.org/?probe=06e9f893bc) | Dec 25, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [3441aa81e6](https://linux-hardware.org/?probe=3441aa81e6) | Dec 23, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [cdbe6b267f](https://linux-hardware.org/?probe=cdbe6b267f) | Dec 19, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [6fc9570e4f](https://linux-hardware.org/?probe=6fc9570e4f) | Dec 19, 2023 |
| Lenovo        | ThinkPad T480 20L6SH3L2D    | Notebook    | [73c69f2b50](https://linux-hardware.org/?probe=73c69f2b50) | Dec 13, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 5 2... | Convertible | [4053f6be95](https://linux-hardware.org/?probe=4053f6be95) | Dec 12, 2023 |
| HP            | 18E7                        | Desktop     | [dad5884f78](https://linux-hardware.org/?probe=dad5884f78) | Dec 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [04ed98dd4a](https://linux-hardware.org/?probe=04ed98dd4a) | Dec 09, 2023 |
| Dell          | Inspiron 3421               | Notebook    | [2ceba60d03](https://linux-hardware.org/?probe=2ceba60d03) | Dec 09, 2023 |
| Dell          | Inspiron 3421               | Notebook    | [912e908ba0](https://linux-hardware.org/?probe=912e908ba0) | Dec 09, 2023 |
| HP            | 3031h                       | Desktop     | [06a9e0c346](https://linux-hardware.org/?probe=06a9e0c346) | Dec 04, 2023 |
| HP            | Pavilion 15                 | Notebook    | [e62aa2185a](https://linux-hardware.org/?probe=e62aa2185a) | Dec 02, 2023 |
| HP            | Pavilion 15                 | Notebook    | [4282694224](https://linux-hardware.org/?probe=4282694224) | Dec 01, 2023 |
| Dell          | OptiPlex 745                | Desktop     | [1abbad3f94](https://linux-hardware.org/?probe=1abbad3f94) | Nov 23, 2023 |
| Dell          | 0XPDFK A01                  | Desktop     | [8b3abafe9b](https://linux-hardware.org/?probe=8b3abafe9b) | Nov 19, 2023 |
| Toshiba       | Satellite Pro L300          | Notebook    | [8cc0e1c14d](https://linux-hardware.org/?probe=8cc0e1c14d) | Nov 09, 2023 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | Notebook    | [68dd4f08d9](https://linux-hardware.org/?probe=68dd4f08d9) | Nov 02, 2023 |
| Lenovo        | ThinkPad T480 20L6SH3L2D    | Notebook    | [db3f0ac717](https://linux-hardware.org/?probe=db3f0ac717) | Oct 31, 2023 |
| Thomson       | N14C4WH64                   | Notebook    | [8dd9b1dbde](https://linux-hardware.org/?probe=8dd9b1dbde) | Oct 28, 2023 |
| LG Electro... | R310-K.AP31B                | Notebook    | [ac3922c573](https://linux-hardware.org/?probe=ac3922c573) | Oct 24, 2023 |
| HP            | 1998                        | Desktop     | [d37c482ca8](https://linux-hardware.org/?probe=d37c482ca8) | Oct 19, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [a5a8709f77](https://linux-hardware.org/?probe=a5a8709f77) | Oct 19, 2023 |
| Lenovo        | ThinkPad T480s 20L8002AM... | Notebook    | [b8d09ca2f5](https://linux-hardware.org/?probe=b8d09ca2f5) | Oct 18, 2023 |
| Lenovo        | ThinkPad T480 20L6SH3L2D    | Notebook    | [e66ff52b09](https://linux-hardware.org/?probe=e66ff52b09) | Oct 13, 2023 |
| HP            | 18E4                        | Desktop     | [6707337e0c](https://linux-hardware.org/?probe=6707337e0c) | Oct 03, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [0a667d66b7](https://linux-hardware.org/?probe=0a667d66b7) | Sep 26, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [15f8d0107f](https://linux-hardware.org/?probe=15f8d0107f) | Sep 26, 2023 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [dbe3003db5](https://linux-hardware.org/?probe=dbe3003db5) | Sep 25, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [a941b27d32](https://linux-hardware.org/?probe=a941b27d32) | Sep 25, 2023 |
| HP            | 250 G4                      | Notebook    | [5290896e7d](https://linux-hardware.org/?probe=5290896e7d) | Sep 23, 2023 |
| Lenovo        | IdeaPadFlex 15D 20334       | Notebook    | [82b9c0d614](https://linux-hardware.org/?probe=82b9c0d614) | Sep 21, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [fe68084259](https://linux-hardware.org/?probe=fe68084259) | Sep 18, 2023 |
| Acer          | Aspire 5742                 | Notebook    | [603e2a55fb](https://linux-hardware.org/?probe=603e2a55fb) | Sep 15, 2023 |
| Dell          | 077RRV A00                  | Desktop     | [5ebc4171ff](https://linux-hardware.org/?probe=5ebc4171ff) | Sep 08, 2023 |
| Lenovo        | ThinkPad X260 20F5S2WX0R    | Notebook    | [cb338af601](https://linux-hardware.org/?probe=cb338af601) | Sep 04, 2023 |
| Acer          | Aspire 5742                 | Notebook    | [ff917b0920](https://linux-hardware.org/?probe=ff917b0920) | Sep 02, 2023 |
| Valve         | Jupiter                     | Notebook    | [6df7fe9dca](https://linux-hardware.org/?probe=6df7fe9dca) | Sep 02, 2023 |
| Lenovo        | 1030 SDK0J40697 WIN 3305... | Desktop     | [e180d8d91b](https://linux-hardware.org/?probe=e180d8d91b) | Aug 31, 2023 |
| HP            | Bloog                       | Notebook    | [17077dd340](https://linux-hardware.org/?probe=17077dd340) | Aug 26, 2023 |
| HP            | 3031h                       | Desktop     | [4ce70764b2](https://linux-hardware.org/?probe=4ce70764b2) | Aug 16, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [74a73b0208](https://linux-hardware.org/?probe=74a73b0208) | Aug 13, 2023 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | Desktop     | [5dc4c594ea](https://linux-hardware.org/?probe=5dc4c594ea) | Aug 05, 2023 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | Desktop     | [e8249dc6d6](https://linux-hardware.org/?probe=e8249dc6d6) | Jul 21, 2023 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | Desktop     | [37132be6bd](https://linux-hardware.org/?probe=37132be6bd) | Jul 21, 2023 |
| Acer          | Nitro AN515-53              | Notebook    | [368352c126](https://linux-hardware.org/?probe=368352c126) | Jul 12, 2023 |
| HP            | 158A                        | Desktop     | [4d915b56e7](https://linux-hardware.org/?probe=4d915b56e7) | Jul 08, 2023 |
| HP            | 0AECh D                     | Desktop     | [bd8035963a](https://linux-hardware.org/?probe=bd8035963a) | Jul 03, 2023 |
| Dell          | Latitude 5540               | Notebook    | [bdf022bb03](https://linux-hardware.org/?probe=bdf022bb03) | Jul 02, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [6c1829f43d](https://linux-hardware.org/?probe=6c1829f43d) | Jul 01, 2023 |
| HP            | 21F5 0A                     | Desktop     | [dd990a6e99](https://linux-hardware.org/?probe=dd990a6e99) | Jun 26, 2023 |
| Dell          | Latitude 5289               | Notebook    | [cb492423ed](https://linux-hardware.org/?probe=cb492423ed) | Jun 20, 2023 |
| Dell          | Latitude E7450              | Notebook    | [addda016c8](https://linux-hardware.org/?probe=addda016c8) | Jun 18, 2023 |
| ASUSTek       | X540LA                      | Notebook    | [55316783a4](https://linux-hardware.org/?probe=55316783a4) | Jun 16, 2023 |
| ASUSTek       | X540LA                      | Notebook    | [2c1b5651ed](https://linux-hardware.org/?probe=2c1b5651ed) | Jun 15, 2023 |
| ASUSTek       | UX32LN                      | Notebook    | [97ff235920](https://linux-hardware.org/?probe=97ff235920) | Jun 08, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [e92f94ecb3](https://linux-hardware.org/?probe=e92f94ecb3) | May 27, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [73dfd22efc](https://linux-hardware.org/?probe=73dfd22efc) | May 21, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [7d4516eff2](https://linux-hardware.org/?probe=7d4516eff2) | May 20, 2023 |
| Dell          | Latitude E7450              | Notebook    | [14227e270f](https://linux-hardware.org/?probe=14227e270f) | May 19, 2023 |
| HP            | Pavilion g6                 | Notebook    | [21bf9f3d3f](https://linux-hardware.org/?probe=21bf9f3d3f) | May 12, 2023 |
| Dell          | Latitude 5510               | Notebook    | [2c279a470e](https://linux-hardware.org/?probe=2c279a470e) | May 10, 2023 |
| Lenovo        | ThinkPad T450 20BUS3E800    | Notebook    | [c419e60853](https://linux-hardware.org/?probe=c419e60853) | May 09, 2023 |
| HP            | 1589                        | Desktop     | [be15d33d32](https://linux-hardware.org/?probe=be15d33d32) | May 07, 2023 |
| Lenovo        | ThinkPad X201 3680HTG       | Notebook    | [9cb4890df2](https://linux-hardware.org/?probe=9cb4890df2) | May 06, 2023 |
| HP            | Pavilion g6                 | Notebook    | [3c4ec29c8a](https://linux-hardware.org/?probe=3c4ec29c8a) | May 05, 2023 |
| American M... | XA133PR110                  | Notebook    | [4c02a6f8da](https://linux-hardware.org/?probe=4c02a6f8da) | May 03, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [1979bde291](https://linux-hardware.org/?probe=1979bde291) | May 01, 2023 |
| HP            | 15                          | Notebook    | [17b9906d58](https://linux-hardware.org/?probe=17b9906d58) | May 01, 2023 |
| HP            | 15                          | Notebook    | [8fb1f3c8f8](https://linux-hardware.org/?probe=8fb1f3c8f8) | May 01, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [3592ce514a](https://linux-hardware.org/?probe=3592ce514a) | Apr 29, 2023 |
| Lenovo        | ThinkPad T430 2349BS7       | Notebook    | [8d832f0261](https://linux-hardware.org/?probe=8d832f0261) | Apr 26, 2023 |
| HP            | ProBook 5320m               | Notebook    | [7597710994](https://linux-hardware.org/?probe=7597710994) | Apr 24, 2023 |
| American M... | XA133PR110                  | Notebook    | [5c634b7029](https://linux-hardware.org/?probe=5c634b7029) | Apr 19, 2023 |
| American M... | XA133PR110                  | Notebook    | [08b47e43a7](https://linux-hardware.org/?probe=08b47e43a7) | Apr 17, 2023 |
| HP            | 0AECh D                     | Desktop     | [f6c67d337e](https://linux-hardware.org/?probe=f6c67d337e) | Apr 17, 2023 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [e9e05a1bb3](https://linux-hardware.org/?probe=e9e05a1bb3) | Apr 15, 2023 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [0b4fdfd30e](https://linux-hardware.org/?probe=0b4fdfd30e) | Apr 15, 2023 |
| Lenovo        | ThinkPad X201 3680HTG       | Notebook    | [f7029b5f3b](https://linux-hardware.org/?probe=f7029b5f3b) | Apr 14, 2023 |
| HP            | 1494                        | Desktop     | [9c5dc1a221](https://linux-hardware.org/?probe=9c5dc1a221) | Apr 13, 2023 |
| HP            | 89B4 A                      | Desktop     | [cb8136a176](https://linux-hardware.org/?probe=cb8136a176) | Mar 28, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [9fbd9476b2](https://linux-hardware.org/?probe=9fbd9476b2) | Mar 28, 2023 |
| Dell          | Latitude 5400               | Notebook    | [4e17f4827d](https://linux-hardware.org/?probe=4e17f4827d) | Mar 23, 2023 |
| Dell          | Latitude 5400               | Notebook    | [c85d243d8a](https://linux-hardware.org/?probe=c85d243d8a) | Mar 23, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [2a85ee4871](https://linux-hardware.org/?probe=2a85ee4871) | Mar 15, 2023 |
| Dell          | Latitude E5450              | Notebook    | [2f16482775](https://linux-hardware.org/?probe=2f16482775) | Mar 04, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [9ce5a599cd](https://linux-hardware.org/?probe=9ce5a599cd) | Mar 03, 2023 |
| Dell          | Latitude E6520              | Notebook    | [2774f2cb16](https://linux-hardware.org/?probe=2774f2cb16) | Mar 01, 2023 |
| ASUSTek       | X751LK                      | Notebook    | [f312f303e0](https://linux-hardware.org/?probe=f312f303e0) | Feb 26, 2023 |
| HP            | Pavilion g6                 | Notebook    | [39b27e9850](https://linux-hardware.org/?probe=39b27e9850) | Feb 19, 2023 |
| Dell          | Latitude E7450              | Notebook    | [16f40c9f6a](https://linux-hardware.org/?probe=16f40c9f6a) | Feb 17, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [41f9974254](https://linux-hardware.org/?probe=41f9974254) | Feb 16, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | Notebook    | [b82ad16853](https://linux-hardware.org/?probe=b82ad16853) | Feb 08, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | Notebook    | [76dd43711a](https://linux-hardware.org/?probe=76dd43711a) | Feb 08, 2023 |
| Toshiba       | Satellite C855-1LG          | Notebook    | [26ce54002a](https://linux-hardware.org/?probe=26ce54002a) | Feb 05, 2023 |
| Dell          | Latitude 3500               | Notebook    | [79cdb991bf](https://linux-hardware.org/?probe=79cdb991bf) | Feb 03, 2023 |
| Lenovo        | V310-15IKB 80T3             | Notebook    | [a39fb673c7](https://linux-hardware.org/?probe=a39fb673c7) | Feb 03, 2023 |
| Dell          | Latitude D630               | Notebook    | [aa435d7701](https://linux-hardware.org/?probe=aa435d7701) | Feb 03, 2023 |
| Dell          | Latitude D630               | Notebook    | [b191402036](https://linux-hardware.org/?probe=b191402036) | Feb 03, 2023 |
| HP            | 18E7                        | Desktop     | [db4ef3e5f4](https://linux-hardware.org/?probe=db4ef3e5f4) | Jan 30, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [b33f2d5606](https://linux-hardware.org/?probe=b33f2d5606) | Jan 28, 2023 |
| Dell          | Latitude E6410              | Notebook    | [854634fb32](https://linux-hardware.org/?probe=854634fb32) | Jan 24, 2023 |
| Dell          | Latitude E6410              | Notebook    | [a5edbef8d2](https://linux-hardware.org/?probe=a5edbef8d2) | Jan 24, 2023 |
| Fujitsu Si... | AMILO Xi 3650               | Notebook    | [1f238129d8](https://linux-hardware.org/?probe=1f238129d8) | Jan 12, 2023 |
| Lenovo        | IdeaPadFlex 15D 20334       | Notebook    | [c5379f6dc1](https://linux-hardware.org/?probe=c5379f6dc1) | Jan 12, 2023 |
| Dell          | 0MN1TX A02                  | Desktop     | [e0099da561](https://linux-hardware.org/?probe=e0099da561) | Jan 11, 2023 |
| Lenovo        | IdeaPadFlex 15D 20334       | Notebook    | [2c092397ea](https://linux-hardware.org/?probe=2c092397ea) | Jan 05, 2023 |
| Dell          | Latitude 5510               | Notebook    | [68e4810231](https://linux-hardware.org/?probe=68e4810231) | Dec 24, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [15582a281d](https://linux-hardware.org/?probe=15582a281d) | Dec 17, 2022 |
| SINTRONES     | AMB-5000G1                  | Notebook    | [3f9a3badb0](https://linux-hardware.org/?probe=3f9a3badb0) | Dec 17, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [57fa4478d0](https://linux-hardware.org/?probe=57fa4478d0) | Dec 17, 2022 |
| SINTRONES     | AMB-5000G1                  | Notebook    | [b1738a6528](https://linux-hardware.org/?probe=b1738a6528) | Dec 17, 2022 |
| Dell          | Latitude D820               | Notebook    | [29df917188](https://linux-hardware.org/?probe=29df917188) | Dec 16, 2022 |
| Dell          | Latitude D820               | Notebook    | [27f19eafce](https://linux-hardware.org/?probe=27f19eafce) | Dec 16, 2022 |
| Dell          | Latitude E7250              | Notebook    | [3e40466ae4](https://linux-hardware.org/?probe=3e40466ae4) | Dec 13, 2022 |
| HP            | Pavilion 15                 | Notebook    | [5d88eed564](https://linux-hardware.org/?probe=5d88eed564) | Dec 13, 2022 |
| Toshiba       | Satellite L50-B             | Notebook    | [5bbe558b2f](https://linux-hardware.org/?probe=5bbe558b2f) | Dec 05, 2022 |
| Lenovo        | ThinkPad T560 20FJS3YN00    | Notebook    | [636921b46c](https://linux-hardware.org/?probe=636921b46c) | Nov 24, 2022 |
| HP            | 15                          | Notebook    | [51711b792f](https://linux-hardware.org/?probe=51711b792f) | Nov 20, 2022 |
| HP            | EliteBook 8540w             | Notebook    | [4da059da1b](https://linux-hardware.org/?probe=4da059da1b) | Nov 14, 2022 |
| Lenovo        | B50-30 20382                | Notebook    | [c4e67c5f10](https://linux-hardware.org/?probe=c4e67c5f10) | Nov 13, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [d710968897](https://linux-hardware.org/?probe=d710968897) | Nov 11, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [451acdb910](https://linux-hardware.org/?probe=451acdb910) | Oct 31, 2022 |
| HP            | 15                          | Notebook    | [c356a2b0cd](https://linux-hardware.org/?probe=c356a2b0cd) | Oct 30, 2022 |
| HP            | 15                          | Notebook    | [34e1ac4cbe](https://linux-hardware.org/?probe=34e1ac4cbe) | Oct 30, 2022 |
| HP            | 2AA2                        | Desktop     | [36f40353c8](https://linux-hardware.org/?probe=36f40353c8) | Oct 25, 2022 |
| Linx          | LINX12X64                   | Tablet      | [132f0a1803](https://linux-hardware.org/?probe=132f0a1803) | Oct 24, 2022 |
| Linx          | LINX12X64                   | Tablet      | [5f78d7109f](https://linux-hardware.org/?probe=5f78d7109f) | Oct 24, 2022 |
| HP            | EliteBook Folio 1040 G1     | Notebook    | [81df2d786a](https://linux-hardware.org/?probe=81df2d786a) | Oct 15, 2022 |
| Dell          | Latitude E4310              | Notebook    | [318726cca9](https://linux-hardware.org/?probe=318726cca9) | Oct 14, 2022 |
| Casper        | EXCALIBUR G770              | Notebook    | [7961a3ca3e](https://linux-hardware.org/?probe=7961a3ca3e) | Oct 14, 2022 |
| eMachines     | eME528                      | Notebook    | [502802d50d](https://linux-hardware.org/?probe=502802d50d) | Oct 13, 2022 |
| Apple         | MacBookPro10,2              | Notebook    | [379590d053](https://linux-hardware.org/?probe=379590d053) | Oct 09, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [e31d2052e5](https://linux-hardware.org/?probe=e31d2052e5) | Oct 06, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [1bcfb0642f](https://linux-hardware.org/?probe=1bcfb0642f) | Oct 06, 2022 |
| HP            | 1497                        | Desktop     | [17a2f79f3f](https://linux-hardware.org/?probe=17a2f79f3f) | Oct 04, 2022 |
| HP            | 1497                        | Desktop     | [fab365512a](https://linux-hardware.org/?probe=fab365512a) | Oct 04, 2022 |
| HP            | 1497                        | Desktop     | [86ab60b437](https://linux-hardware.org/?probe=86ab60b437) | Sep 30, 2022 |
| Unknown       | 1.0                         | Notebook    | [f5b0e6a742](https://linux-hardware.org/?probe=f5b0e6a742) | Sep 24, 2022 |
| ASUSTek       | X555LD                      | Notebook    | [08793f9065](https://linux-hardware.org/?probe=08793f9065) | Sep 24, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [eb488dae73](https://linux-hardware.org/?probe=eb488dae73) | Sep 17, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [eb406c0e81](https://linux-hardware.org/?probe=eb406c0e81) | Sep 15, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | Desktop     | [805d4161a8](https://linux-hardware.org/?probe=805d4161a8) | Sep 15, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [6b6e4efdfc](https://linux-hardware.org/?probe=6b6e4efdfc) | Sep 13, 2022 |
| Lenovo        | SHARKBAY 0C48431 WIN        | Desktop     | [4598920e84](https://linux-hardware.org/?probe=4598920e84) | Sep 13, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [4083f9d2c9](https://linux-hardware.org/?probe=4083f9d2c9) | Sep 11, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [bd15d55792](https://linux-hardware.org/?probe=bd15d55792) | Sep 07, 2022 |
| HP            | 18E4                        | Desktop     | [2c113164fd](https://linux-hardware.org/?probe=2c113164fd) | Sep 05, 2022 |
| Dell          | Latitude 5490               | Notebook    | [a3f76e546f](https://linux-hardware.org/?probe=a3f76e546f) | Sep 01, 2022 |
| ASUSTek       | K72Jk                       | Notebook    | [d456f7083c](https://linux-hardware.org/?probe=d456f7083c) | Aug 26, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [3cca56dc74](https://linux-hardware.org/?probe=3cca56dc74) | Aug 22, 2022 |
| HP            | Compaq 15                   | Notebook    | [c2bdac6148](https://linux-hardware.org/?probe=c2bdac6148) | Aug 21, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [c636c0401e](https://linux-hardware.org/?probe=c636c0401e) | Aug 18, 2022 |
| Dell          | Latitude E5500              | Notebook    | [5d04270674](https://linux-hardware.org/?probe=5d04270674) | Aug 08, 2022 |
| Raspberry ... | Raspberry Pi Model B Rev... | Soc         | [90197434fc](https://linux-hardware.org/?probe=90197434fc) | Aug 08, 2022 |
| HP            | 198E                        | Desktop     | [4327be921d](https://linux-hardware.org/?probe=4327be921d) | Aug 06, 2022 |
| HP            | 198E                        | Desktop     | [284e29b3ea](https://linux-hardware.org/?probe=284e29b3ea) | Aug 06, 2022 |
| Acer          | Aspire ES1-523              | Notebook    | [d14f053671](https://linux-hardware.org/?probe=d14f053671) | Aug 01, 2022 |
| Lenovo        | S21e-20 80M4                | Notebook    | [bec71c2353](https://linux-hardware.org/?probe=bec71c2353) | Jul 27, 2022 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | Notebook    | [02dd3c2357](https://linux-hardware.org/?probe=02dd3c2357) | Jul 21, 2022 |
| ASUSTek       | WS X299 SAGE                | Desktop     | [acb31e0818](https://linux-hardware.org/?probe=acb31e0818) | Jul 18, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [789f614370](https://linux-hardware.org/?probe=789f614370) | Jul 14, 2022 |
| Dell          | Latitude D620               | Notebook    | [70be0d553e](https://linux-hardware.org/?probe=70be0d553e) | Jul 08, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [44b541373b](https://linux-hardware.org/?probe=44b541373b) | Jul 08, 2022 |
| Dell          | Latitude E6420              | Notebook    | [ede3298bf4](https://linux-hardware.org/?probe=ede3298bf4) | Jul 02, 2022 |
| HP            | ZBook 15 G3                 | Notebook    | [8c6f371222](https://linux-hardware.org/?probe=8c6f371222) | Jun 19, 2022 |
| HP            | Laptop 15-ra0xx             | Notebook    | [947ca74beb](https://linux-hardware.org/?probe=947ca74beb) | Jun 16, 2022 |
| HP            | Laptop 15-ra0xx             | Notebook    | [70ed4ebad8](https://linux-hardware.org/?probe=70ed4ebad8) | Jun 16, 2022 |
| Dell          | 0KJCC5 A00                  | Desktop     | [334e57a8b2](https://linux-hardware.org/?probe=334e57a8b2) | Jun 14, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [ed68bc8e1d](https://linux-hardware.org/?probe=ed68bc8e1d) | May 31, 2022 |
| Lenovo        | ThinkPad T430 2349BS7       | Notebook    | [2369e183ec](https://linux-hardware.org/?probe=2369e183ec) | May 30, 2022 |
| eMachines     | eM350                       | Notebook    | [2573854a09](https://linux-hardware.org/?probe=2573854a09) | May 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [ae7670331c](https://linux-hardware.org/?probe=ae7670331c) | May 22, 2022 |
| Gigabyte      | AERO 15 KC                  | Notebook    | [5ebc19bd4c](https://linux-hardware.org/?probe=5ebc19bd4c) | May 18, 2022 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [39bb2b41e5](https://linux-hardware.org/?probe=39bb2b41e5) | May 18, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [427af3e3a0](https://linux-hardware.org/?probe=427af3e3a0) | May 09, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [7d4d1cb642](https://linux-hardware.org/?probe=7d4d1cb642) | May 06, 2022 |
| Dell          | Latitude E5440              | Notebook    | [556fccb6d3](https://linux-hardware.org/?probe=556fccb6d3) | May 06, 2022 |
| Packard Be... | EasyNote TS44HR             | Notebook    | [2eff4001dc](https://linux-hardware.org/?probe=2eff4001dc) | May 06, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [889f1cba36](https://linux-hardware.org/?probe=889f1cba36) | Apr 30, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [f4403056c8](https://linux-hardware.org/?probe=f4403056c8) | Apr 30, 2022 |
| HP            | Pavilion g6                 | Notebook    | [b79730a7af](https://linux-hardware.org/?probe=b79730a7af) | Apr 27, 2022 |
| Lenovo        | ThinkPad T460 20FN002SUS    | Notebook    | [0fad5f6cd2](https://linux-hardware.org/?probe=0fad5f6cd2) | Apr 21, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [45ad38e728](https://linux-hardware.org/?probe=45ad38e728) | Apr 14, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d809b304eb](https://linux-hardware.org/?probe=d809b304eb) | Apr 14, 2022 |
| HP            | Presario C500 (GF852EA#A... | Notebook    | [b14e9c5694](https://linux-hardware.org/?probe=b14e9c5694) | Apr 08, 2022 |
| TrekStor      | Surfbook W2                 | Notebook    | [52eb1e4ce9](https://linux-hardware.org/?probe=52eb1e4ce9) | Apr 06, 2022 |
| Medion        | S4401 MD61533               | Convertible | [0017875c99](https://linux-hardware.org/?probe=0017875c99) | Mar 30, 2022 |
| HP            | Notebook                    | Notebook    | [313ca81d16](https://linux-hardware.org/?probe=313ca81d16) | Mar 27, 2022 |
| ECS           | Nettle2                     | Desktop     | [4939d60e6d](https://linux-hardware.org/?probe=4939d60e6d) | Mar 27, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [24664b0486](https://linux-hardware.org/?probe=24664b0486) | Mar 25, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [1cb13706a4](https://linux-hardware.org/?probe=1cb13706a4) | Mar 25, 2022 |
| Dell          | Vostro 1015                 | Notebook    | [5eac01f806](https://linux-hardware.org/?probe=5eac01f806) | Mar 25, 2022 |
| Dell          | Vostro 1015                 | Notebook    | [ce0fa4ee36](https://linux-hardware.org/?probe=ce0fa4ee36) | Mar 25, 2022 |
| Dell          | Latitude E5440              | Notebook    | [6b871a160e](https://linux-hardware.org/?probe=6b871a160e) | Mar 22, 2022 |
| Dell          | Latitude E5440              | Notebook    | [bd5621d6e2](https://linux-hardware.org/?probe=bd5621d6e2) | Mar 21, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [39d48e6d79](https://linux-hardware.org/?probe=39d48e6d79) | Feb 28, 2022 |
| HP            | 18E4                        | Desktop     | [e7d597600e](https://linux-hardware.org/?probe=e7d597600e) | Feb 25, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [fc6097a447](https://linux-hardware.org/?probe=fc6097a447) | Feb 23, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [6888384b59](https://linux-hardware.org/?probe=6888384b59) | Feb 21, 2022 |
| ASUSTek       | X751LD                      | Notebook    | [074c993361](https://linux-hardware.org/?probe=074c993361) | Feb 19, 2022 |
| Dell          | Latitude E6520              | Notebook    | [f921803f50](https://linux-hardware.org/?probe=f921803f50) | Feb 16, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [ae8afcd09f](https://linux-hardware.org/?probe=ae8afcd09f) | Feb 13, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [4769ae7351](https://linux-hardware.org/?probe=4769ae7351) | Feb 12, 2022 |
| Dell          | Precision M4800             | Notebook    | [8f91ff2d57](https://linux-hardware.org/?probe=8f91ff2d57) | Jan 29, 2022 |
| Dell          | Latitude E6520              | Notebook    | [ee96960cec](https://linux-hardware.org/?probe=ee96960cec) | Jan 25, 2022 |
| ASUSTek       | X540LA                      | Notebook    | [a24d99bf3b](https://linux-hardware.org/?probe=a24d99bf3b) | Jan 24, 2022 |
| Clevo         | W24/250CU                   | Notebook    | [64c6f06849](https://linux-hardware.org/?probe=64c6f06849) | Jan 22, 2022 |
| Google        | Banon                       | Notebook    | [3e792337e2](https://linux-hardware.org/?probe=3e792337e2) | Jan 21, 2022 |
| Google        | Banon                       | Notebook    | [c4cfb244b1](https://linux-hardware.org/?probe=c4cfb244b1) | Jan 21, 2022 |
| HP            | 3396                        | Desktop     | [e9486b13b8](https://linux-hardware.org/?probe=e9486b13b8) | Jan 20, 2022 |
| HP            | Pavilion g6                 | Notebook    | [099231b0b3](https://linux-hardware.org/?probe=099231b0b3) | Jan 19, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [8e4f80059d](https://linux-hardware.org/?probe=8e4f80059d) | Jan 14, 2022 |
| HP            | 1589                        | Desktop     | [402f1722ab](https://linux-hardware.org/?probe=402f1722ab) | Jan 09, 2022 |
| Lenovo        | ThinkPad P50 20EQS6J100     | Notebook    | [f366de3acf](https://linux-hardware.org/?probe=f366de3acf) | Jan 03, 2022 |
| Dell          | Precision 5560              | Notebook    | [04cb5954e9](https://linux-hardware.org/?probe=04cb5954e9) | Dec 31, 2021 |
| HP            | 8054                        | Desktop     | [13d18f87fe](https://linux-hardware.org/?probe=13d18f87fe) | Dec 30, 2021 |
| HP            | 8054                        | Desktop     | [fcf6deb221](https://linux-hardware.org/?probe=fcf6deb221) | Dec 30, 2021 |
| Timi          | TM1701                      | Notebook    | [ce3374e321](https://linux-hardware.org/?probe=ce3374e321) | Dec 23, 2021 |
| HP            | 1998                        | Desktop     | [f8e644ed15](https://linux-hardware.org/?probe=f8e644ed15) | Dec 23, 2021 |
| HP            | 090Ch                       | Desktop     | [bf92e3c728](https://linux-hardware.org/?probe=bf92e3c728) | Dec 22, 2021 |
| Acer          | Aspire One 522              | Notebook    | [7f495fc85b](https://linux-hardware.org/?probe=7f495fc85b) | Dec 21, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [331d419175](https://linux-hardware.org/?probe=331d419175) | Dec 06, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [97aec623b3](https://linux-hardware.org/?probe=97aec623b3) | Dec 04, 2021 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [8a415c9db8](https://linux-hardware.org/?probe=8a415c9db8) | Dec 04, 2021 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [3027f5288e](https://linux-hardware.org/?probe=3027f5288e) | Dec 04, 2021 |
| HP            | 1998                        | Desktop     | [ffa6c0b239](https://linux-hardware.org/?probe=ffa6c0b239) | Dec 01, 2021 |
| ASUSTek       | K72Jr                       | Notebook    | [518ee0b884](https://linux-hardware.org/?probe=518ee0b884) | Nov 30, 2021 |
| ASUSTek       | K72Jr                       | Notebook    | [405b87f8bf](https://linux-hardware.org/?probe=405b87f8bf) | Nov 29, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3DD1... | Notebook    | [816aaebc79](https://linux-hardware.org/?probe=816aaebc79) | Nov 27, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3DD1... | Notebook    | [162c76040f](https://linux-hardware.org/?probe=162c76040f) | Nov 27, 2021 |
| Lenovo        | ThinkPad X13 Gen 2i 20WK... | Notebook    | [7b9f86430d](https://linux-hardware.org/?probe=7b9f86430d) | Nov 25, 2021 |
| Lenovo        | ThinkPad X13 Gen 2i 20WK... | Notebook    | [c5aa70cf8a](https://linux-hardware.org/?probe=c5aa70cf8a) | Nov 25, 2021 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [73b27d5257](https://linux-hardware.org/?probe=73b27d5257) | Nov 25, 2021 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [915ddf82b5](https://linux-hardware.org/?probe=915ddf82b5) | Nov 23, 2021 |
| HP            | EliteBook 8530w             | Notebook    | [e3a38e431e](https://linux-hardware.org/?probe=e3a38e431e) | Nov 23, 2021 |
| HP            | ZBook 15                    | Notebook    | [6aca3076ac](https://linux-hardware.org/?probe=6aca3076ac) | Nov 22, 2021 |
| HP            | 15                          | Notebook    | [e82411639f](https://linux-hardware.org/?probe=e82411639f) | Nov 20, 2021 |
| Toshiba       | Satellite L50-A-1EL         | Notebook    | [40fff0be70](https://linux-hardware.org/?probe=40fff0be70) | Nov 19, 2021 |
| Dell          | 0MWYPT A01                  | Desktop     | [63385716b2](https://linux-hardware.org/?probe=63385716b2) | Nov 19, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [f8670ddd99](https://linux-hardware.org/?probe=f8670ddd99) | Nov 18, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [b4fb9ffc24](https://linux-hardware.org/?probe=b4fb9ffc24) | Nov 18, 2021 |
| ASUSTek       | Acacia                      | Desktop     | [acb0ed7655](https://linux-hardware.org/?probe=acb0ed7655) | Nov 16, 2021 |
| HP            | EliteBook x360 1030 G2      | Convertible | [b4ebd974c1](https://linux-hardware.org/?probe=b4ebd974c1) | Nov 15, 2021 |
| Apple         | MacBookPro13,3              | Notebook    | [e80b600640](https://linux-hardware.org/?probe=e80b600640) | Nov 12, 2021 |
| HP            | 1589                        | Desktop     | [789cbfc3fa](https://linux-hardware.org/?probe=789cbfc3fa) | Nov 10, 2021 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [966b61331a](https://linux-hardware.org/?probe=966b61331a) | Nov 05, 2021 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [e1c9be9f1d](https://linux-hardware.org/?probe=e1c9be9f1d) | Nov 05, 2021 |
| Pegatron      | 2AD5                        | Desktop     | [70ae8e4cdf](https://linux-hardware.org/?probe=70ae8e4cdf) | Oct 30, 2021 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [c1f75f6249](https://linux-hardware.org/?probe=c1f75f6249) | Oct 27, 2021 |
| ASUSTek       | X540LA                      | Notebook    | [c947e5b1ea](https://linux-hardware.org/?probe=c947e5b1ea) | Oct 26, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [2de5c74bc0](https://linux-hardware.org/?probe=2de5c74bc0) | Oct 23, 2021 |
| HP            | 18E7                        | Desktop     | [94c750ba4b](https://linux-hardware.org/?probe=94c750ba4b) | Oct 23, 2021 |
| HP            | 250 I3-5005U 15.6           | Notebook    | [94c7602d80](https://linux-hardware.org/?probe=94c7602d80) | Oct 20, 2021 |
| American M... | K7S41GX                     | Desktop     | [b5f8d33cc4](https://linux-hardware.org/?probe=b5f8d33cc4) | Oct 20, 2021 |
| American M... | K7S41GX                     | Desktop     | [920a47f107](https://linux-hardware.org/?probe=920a47f107) | Oct 20, 2021 |
| Sony          | VPCEH1L8E                   | Notebook    | [11ef4d4baf](https://linux-hardware.org/?probe=11ef4d4baf) | Oct 19, 2021 |
| HP            | 3032h                       | Desktop     | [6914386d3d](https://linux-hardware.org/?probe=6914386d3d) | Oct 19, 2021 |
| Sony          | SVE14122CAW                 | Notebook    | [7e20d79b1d](https://linux-hardware.org/?probe=7e20d79b1d) | Oct 16, 2021 |
| HP            | 1589                        | Desktop     | [bb8d8d60cf](https://linux-hardware.org/?probe=bb8d8d60cf) | Oct 10, 2021 |
| Dell          | 0J3C2F A00                  | Desktop     | [565fbea977](https://linux-hardware.org/?probe=565fbea977) | Oct 10, 2021 |
| Razer         | Blade Pro 17 (2019)         | Notebook    | [c0fc32d290](https://linux-hardware.org/?probe=c0fc32d290) | Oct 09, 2021 |
| Foxconn       | 2ABF                        | Desktop     | [92bc4bf86c](https://linux-hardware.org/?probe=92bc4bf86c) | Oct 04, 2021 |
| Dell          | Latitude E5570              | Notebook    | [bfc3702626](https://linux-hardware.org/?probe=bfc3702626) | Oct 04, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [c5f4555ed5](https://linux-hardware.org/?probe=c5f4555ed5) | Sep 29, 2021 |
| Dell          | Latitude E5570              | Notebook    | [b4f22d5062](https://linux-hardware.org/?probe=b4f22d5062) | Sep 27, 2021 |
| Dell          | Latitude E5570              | Notebook    | [42c88d1bb8](https://linux-hardware.org/?probe=42c88d1bb8) | Sep 27, 2021 |
| HP            | EliteBook 8530w             | Notebook    | [37a7444281](https://linux-hardware.org/?probe=37a7444281) | Sep 25, 2021 |
| HP            | EliteBook 8530w             | Notebook    | [326645a221](https://linux-hardware.org/?probe=326645a221) | Sep 25, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [b01438543e](https://linux-hardware.org/?probe=b01438543e) | Sep 20, 2021 |
| HP            | 18E7                        | Desktop     | [e1aa6d3e49](https://linux-hardware.org/?probe=e1aa6d3e49) | Sep 19, 2021 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [554c02e687](https://linux-hardware.org/?probe=554c02e687) | Sep 14, 2021 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [e2202296c9](https://linux-hardware.org/?probe=e2202296c9) | Sep 13, 2021 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [99c878cd5e](https://linux-hardware.org/?probe=99c878cd5e) | Sep 04, 2021 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [d63a5c07e1](https://linux-hardware.org/?probe=d63a5c07e1) | Aug 28, 2021 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [78316d40ea](https://linux-hardware.org/?probe=78316d40ea) | Aug 28, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [cece1a32de](https://linux-hardware.org/?probe=cece1a32de) | Aug 21, 2021 |
| HP            | 0AACh                       | Desktop     | [588b35da24](https://linux-hardware.org/?probe=588b35da24) | Aug 21, 2021 |
| HP            | EliteBook x360 1030 G2      | Convertible | [49eb3e8236](https://linux-hardware.org/?probe=49eb3e8236) | Aug 18, 2021 |
| HP            | EliteBook x360 1030 G2      | Convertible | [3e73238fc6](https://linux-hardware.org/?probe=3e73238fc6) | Aug 13, 2021 |
| Lenovo        | ThinkPad X250 20CLS4WV08    | Notebook    | [2c09cdd5bd](https://linux-hardware.org/?probe=2c09cdd5bd) | Aug 12, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [f0faf00d2f](https://linux-hardware.org/?probe=f0faf00d2f) | Aug 09, 2021 |
| Dell          | 0NX0PH A01                  | Desktop     | [8416267437](https://linux-hardware.org/?probe=8416267437) | Aug 09, 2021 |
| HP            | 15                          | Notebook    | [80ce139934](https://linux-hardware.org/?probe=80ce139934) | Aug 06, 2021 |
| HP            | 15                          | Notebook    | [24c674140c](https://linux-hardware.org/?probe=24c674140c) | Aug 05, 2021 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [ea05f5d624](https://linux-hardware.org/?probe=ea05f5d624) | Jul 21, 2021 |
| HP            | 339A                        | Desktop     | [7ea04a15cb](https://linux-hardware.org/?probe=7ea04a15cb) | Jul 18, 2021 |
| HP            | 339A                        | Desktop     | [31018180f8](https://linux-hardware.org/?probe=31018180f8) | Jul 16, 2021 |
| Unknown       | 1.0                         | Notebook    | [d049c76d58](https://linux-hardware.org/?probe=d049c76d58) | Jul 08, 2021 |
| Unknown       | 1.0                         | Notebook    | [deb4346da8](https://linux-hardware.org/?probe=deb4346da8) | Jul 08, 2021 |
| Foxconn       | 2ABF                        | Desktop     | [77e63e8902](https://linux-hardware.org/?probe=77e63e8902) | Jul 06, 2021 |
| HP            | 3396                        | Desktop     | [28e2f6399c](https://linux-hardware.org/?probe=28e2f6399c) | Jul 05, 2021 |
| Unknown       | 1.0                         | Notebook    | [967654bdb6](https://linux-hardware.org/?probe=967654bdb6) | Jul 04, 2021 |
| Unknown       | 1.0                         | Notebook    | [36977bacbe](https://linux-hardware.org/?probe=36977bacbe) | Jul 03, 2021 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [19666df61f](https://linux-hardware.org/?probe=19666df61f) | Jun 26, 2021 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [df836c85c5](https://linux-hardware.org/?probe=df836c85c5) | Jun 26, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [dd3d9ede87](https://linux-hardware.org/?probe=dd3d9ede87) | Jun 20, 2021 |
| Unknown       | Unknown                     | Notebook    | [80c0612f78](https://linux-hardware.org/?probe=80c0612f78) | Jun 04, 2021 |
| Unknown       | Unknown                     | Notebook    | [9bac89aecf](https://linux-hardware.org/?probe=9bac89aecf) | Jun 04, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [513f79e441](https://linux-hardware.org/?probe=513f79e441) | May 26, 2021 |
| HP            | 0AACh                       | Desktop     | [92920ff59a](https://linux-hardware.org/?probe=92920ff59a) | May 26, 2021 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | Notebook    | [3890d7877d](https://linux-hardware.org/?probe=3890d7877d) | May 06, 2021 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | Notebook    | [44810c2cc1](https://linux-hardware.org/?probe=44810c2cc1) | May 06, 2021 |
| MSI           | 2A9C                        | Desktop     | [db1be00449](https://linux-hardware.org/?probe=db1be00449) | May 02, 2021 |
| Lenovo        | ThinkPad X220 4291V5K       | Notebook    | [c0b9d7bd52](https://linux-hardware.org/?probe=c0b9d7bd52) | Apr 26, 2021 |
| Lenovo        | ThinkPad X220 4291V5K       | Notebook    | [4ec1325f12](https://linux-hardware.org/?probe=4ec1325f12) | Apr 26, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [cf8b627aa4](https://linux-hardware.org/?probe=cf8b627aa4) | Apr 11, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [bd04b1367f](https://linux-hardware.org/?probe=bd04b1367f) | Apr 11, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [522eb62b1a](https://linux-hardware.org/?probe=522eb62b1a) | Apr 03, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [e9df8836cf](https://linux-hardware.org/?probe=e9df8836cf) | Apr 03, 2021 |
| HP            | EliteBook 2540p             | Notebook    | [46c15e3b14](https://linux-hardware.org/?probe=46c15e3b14) | Apr 01, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [e1023ad432](https://linux-hardware.org/?probe=e1023ad432) | Mar 31, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [5c9803ca79](https://linux-hardware.org/?probe=5c9803ca79) | Mar 31, 2021 |
| Foxconn       | 2ACA                        | Desktop     | [04556ec49b](https://linux-hardware.org/?probe=04556ec49b) | Mar 26, 2021 |
| HP            | Pavilion Laptop 15-ck0xx    | Notebook    | [f973f0f31c](https://linux-hardware.org/?probe=f973f0f31c) | Mar 23, 2021 |
| Dell          | Latitude 5580               | Notebook    | [9fd0e8f6b5](https://linux-hardware.org/?probe=9fd0e8f6b5) | Mar 22, 2021 |
| Lenovo        | ThinkPad X220 4291B66       | Notebook    | [411fb65be7](https://linux-hardware.org/?probe=411fb65be7) | Mar 21, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [7a6947637a](https://linux-hardware.org/?probe=7a6947637a) | Mar 16, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [635fc4a0a2](https://linux-hardware.org/?probe=635fc4a0a2) | Mar 16, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [6bccb5f740](https://linux-hardware.org/?probe=6bccb5f740) | Mar 15, 2021 |
| Dell          | 0MWYPT A01                  | Desktop     | [1c76380527](https://linux-hardware.org/?probe=1c76380527) | Mar 06, 2021 |
| HP            | 1495                        | Desktop     | [ca9664aff0](https://linux-hardware.org/?probe=ca9664aff0) | Mar 05, 2021 |
| HP            | Notebook                    | Notebook    | [fbc522f5e7](https://linux-hardware.org/?probe=fbc522f5e7) | Feb 24, 2021 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | Desktop     | [ab67b7aab9](https://linux-hardware.org/?probe=ab67b7aab9) | Feb 22, 2021 |
| HP            | Pavilion Sleekbook 15       | Notebook    | [aeb3111a93](https://linux-hardware.org/?probe=aeb3111a93) | Feb 20, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [1ffab0446e](https://linux-hardware.org/?probe=1ffab0446e) | Feb 17, 2021 |
| Lenovo        | ThinkPad T460 20FN002SUS    | Notebook    | [2ba0a379e8](https://linux-hardware.org/?probe=2ba0a379e8) | Feb 16, 2021 |
| Dell          | Latitude 3480               | Notebook    | [533356cb56](https://linux-hardware.org/?probe=533356cb56) | Feb 15, 2021 |
| HP            | Pavilion dv7                | Notebook    | [17dcac4931](https://linux-hardware.org/?probe=17dcac4931) | Feb 10, 2021 |
| GPD           | MicroPC                     | Notebook    | [ed2233e6ce](https://linux-hardware.org/?probe=ed2233e6ce) | Feb 08, 2021 |
| Dell          | 0M863N A01                  | Desktop     | [c10de13cf0](https://linux-hardware.org/?probe=c10de13cf0) | Feb 05, 2021 |
| Acer          | AO722                       | Notebook    | [24cb20b715](https://linux-hardware.org/?probe=24cb20b715) | Feb 04, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [8da09ed292](https://linux-hardware.org/?probe=8da09ed292) | Feb 04, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [7861f8622e](https://linux-hardware.org/?probe=7861f8622e) | Feb 01, 2021 |
| Lenovo        | ThinkPad E590 20NB002AMB    | Notebook    | [e45b210ee6](https://linux-hardware.org/?probe=e45b210ee6) | Feb 01, 2021 |
| Lenovo        | ThinkPad T460 20FN002SUS    | Notebook    | [6c9654a854](https://linux-hardware.org/?probe=6c9654a854) | Jan 25, 2021 |
| Apple         | MacBook5,2                  | Notebook    | [512f5b5bdc](https://linux-hardware.org/?probe=512f5b5bdc) | Jan 18, 2021 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [3475dcd9b6](https://linux-hardware.org/?probe=3475dcd9b6) | Jan 17, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [8d7a3472b3](https://linux-hardware.org/?probe=8d7a3472b3) | Jan 16, 2021 |
| HP            | Pavilion dv7                | Notebook    | [bc33dda5d6](https://linux-hardware.org/?probe=bc33dda5d6) | Jan 09, 2021 |
| HP            | 650                         | Notebook    | [65c5445c17](https://linux-hardware.org/?probe=65c5445c17) | Jan 08, 2021 |
| Sony          | VGN-FW11L                   | Notebook    | [e99fe042af](https://linux-hardware.org/?probe=e99fe042af) | Jan 06, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [493c807f09](https://linux-hardware.org/?probe=493c807f09) | Jan 06, 2021 |
| Lenovo        | ThinkPad E570 20H50078IX    | Notebook    | [9162d07863](https://linux-hardware.org/?probe=9162d07863) | Dec 31, 2020 |
| Lenovo        | ThinkPad E570 20H50078IX    | Notebook    | [f1f07aecd0](https://linux-hardware.org/?probe=f1f07aecd0) | Dec 31, 2020 |
| HP            | 158A                        | Desktop     | [afd1e7439b](https://linux-hardware.org/?probe=afd1e7439b) | Dec 28, 2020 |
| Dell          | Latitude E6440              | Notebook    | [cec6c1fd51](https://linux-hardware.org/?probe=cec6c1fd51) | Dec 25, 2020 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [4a4ce9f5d2](https://linux-hardware.org/?probe=4a4ce9f5d2) | Dec 25, 2020 |
| HP            | 650                         | Notebook    | [ff87d07205](https://linux-hardware.org/?probe=ff87d07205) | Dec 21, 2020 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [9c31cf187f](https://linux-hardware.org/?probe=9c31cf187f) | Dec 17, 2020 |
| Timi          | TM1701                      | Notebook    | [bc63393a91](https://linux-hardware.org/?probe=bc63393a91) | Dec 13, 2020 |
| Lenovo        | ThinkPad T480s 20L8S3P30... | Notebook    | [1a37278a5b](https://linux-hardware.org/?probe=1a37278a5b) | Dec 13, 2020 |
| HP            | EliteBook 8560w             | Notebook    | [d546d8c598](https://linux-hardware.org/?probe=d546d8c598) | Nov 25, 2020 |
| HP            | EliteBook 8560w             | Notebook    | [9bb315e3ac](https://linux-hardware.org/?probe=9bb315e3ac) | Nov 25, 2020 |
| HP            | 304Ah                       | Desktop     | [d5f7af2482](https://linux-hardware.org/?probe=d5f7af2482) | Nov 23, 2020 |
| Dell          | Latitude E6440              | Notebook    | [6739c087eb](https://linux-hardware.org/?probe=6739c087eb) | Nov 20, 2020 |
| TUXEDO        | N13xWU                      | Notebook    | [b72558f93c](https://linux-hardware.org/?probe=b72558f93c) | Nov 19, 2020 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [193c57b056](https://linux-hardware.org/?probe=193c57b056) | Nov 10, 2020 |
| TUXEDO        | N13xWU                      | Notebook    | [e6a667e32c](https://linux-hardware.org/?probe=e6a667e32c) | Nov 08, 2020 |
| TUXEDO        | N13xWU                      | Notebook    | [b4cd820410](https://linux-hardware.org/?probe=b4cd820410) | Nov 08, 2020 |
| Lenovo        | ThinkPad X280 20KF001KFR    | Notebook    | [bb66d36c3e](https://linux-hardware.org/?probe=bb66d36c3e) | Oct 23, 2020 |
| ASUSTek       | X555LAB                     | Notebook    | [d4755cc80a](https://linux-hardware.org/?probe=d4755cc80a) | Oct 18, 2020 |
| Dell          | 0MWYPT A01                  | Desktop     | [3134def56f](https://linux-hardware.org/?probe=3134def56f) | Oct 11, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [ef4b4ee1be](https://linux-hardware.org/?probe=ef4b4ee1be) | Oct 10, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [c1d3bd539a](https://linux-hardware.org/?probe=c1d3bd539a) | Oct 09, 2020 |
| HP            | ProBook 450 G0              | Notebook    | [a12e9900c0](https://linux-hardware.org/?probe=a12e9900c0) | Oct 07, 2020 |
| HP            | ProBook 450 G0              | Notebook    | [822c9a0ece](https://linux-hardware.org/?probe=822c9a0ece) | Oct 07, 2020 |
| HP            | Compaq nc6220 (PL814AV)     | Notebook    | [7f042faa64](https://linux-hardware.org/?probe=7f042faa64) | Oct 04, 2020 |
| HP            | EliteBook 8440p             | Notebook    | [a5438c06dc](https://linux-hardware.org/?probe=a5438c06dc) | Oct 02, 2020 |
| HP            | ProBook 6470b               | Notebook    | [0c6e7c5d06](https://linux-hardware.org/?probe=0c6e7c5d06) | Sep 30, 2020 |
| HP            | ProBook 6470b               | Notebook    | [3ab44ecc2c](https://linux-hardware.org/?probe=3ab44ecc2c) | Sep 20, 2020 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | Notebook    | [e36d2e46a2](https://linux-hardware.org/?probe=e36d2e46a2) | Sep 16, 2020 |
| Lenovo        | ThinkPad X280 20KF001KFR    | Notebook    | [09ba7a078c](https://linux-hardware.org/?probe=09ba7a078c) | Sep 06, 2020 |
| Toshiba       | Satellite L750              | Notebook    | [1c9467e7ff](https://linux-hardware.org/?probe=1c9467e7ff) | Aug 31, 2020 |
| HP            | 3398                        | Desktop     | [6b7ea8d306](https://linux-hardware.org/?probe=6b7ea8d306) | Aug 27, 2020 |
| Dell          | Latitude E5270              | Notebook    | [b9e93e40f1](https://linux-hardware.org/?probe=b9e93e40f1) | Aug 26, 2020 |
| Toshiba       | Satellite C855-2CF          | Notebook    | [00048c3fd7](https://linux-hardware.org/?probe=00048c3fd7) | Aug 26, 2020 |
| HP            | ProBook 650 G1              | Notebook    | [134ae0f98f](https://linux-hardware.org/?probe=134ae0f98f) | Aug 24, 2020 |
| Lenovo        | ThinkPad X280 20KF001KFR    | Notebook    | [47a6af7e14](https://linux-hardware.org/?probe=47a6af7e14) | Aug 23, 2020 |
| HP            | Laptop 15-da0xxx            | Notebook    | [b51e82eb8b](https://linux-hardware.org/?probe=b51e82eb8b) | Aug 08, 2020 |
| HP            | ProBook 440 G7              | Notebook    | [b2d1e5272e](https://linux-hardware.org/?probe=b2d1e5272e) | Aug 07, 2020 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [8f0c5d78da](https://linux-hardware.org/?probe=8f0c5d78da) | Jul 29, 2020 |
| HP            | 3397                        | Desktop     | [de9945e027](https://linux-hardware.org/?probe=de9945e027) | Jun 30, 2020 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | Notebook    | [c4b91061bd](https://linux-hardware.org/?probe=c4b91061bd) | Jun 24, 2020 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | Notebook    | [1d9441c4cb](https://linux-hardware.org/?probe=1d9441c4cb) | Jun 24, 2020 |
| HP            | EliteBook 840 G2            | Notebook    | [8f31cacb03](https://linux-hardware.org/?probe=8f31cacb03) | Jun 15, 2020 |
| Dell          | Latitude E6410              | Notebook    | [63006c892d](https://linux-hardware.org/?probe=63006c892d) | Jun 12, 2020 |
| Dell          | Latitude E6540              | Notebook    | [0820a41e4a](https://linux-hardware.org/?probe=0820a41e4a) | Jun 03, 2020 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [d4a0f7593f](https://linux-hardware.org/?probe=d4a0f7593f) | May 30, 2020 |
| Packard Be... | EasyNote TK85               | Notebook    | [1ef7f1dccf](https://linux-hardware.org/?probe=1ef7f1dccf) | May 24, 2020 |
| HP            | Unknown                     | Notebook    | [83216ab6f8](https://linux-hardware.org/?probe=83216ab6f8) | May 23, 2020 |
| Dell          | Latitude E5270              | Notebook    | [79c2208ee5](https://linux-hardware.org/?probe=79c2208ee5) | May 16, 2020 |
| HP            | Laptop 15-da0xxx            | Notebook    | [4d933966bb](https://linux-hardware.org/?probe=4d933966bb) | May 16, 2020 |
| HP            | ZBook 15                    | Notebook    | [7fdf5ffeb8](https://linux-hardware.org/?probe=7fdf5ffeb8) | May 10, 2020 |
| HP            | 0A04h                       | Desktop     | [c0b180275b](https://linux-hardware.org/?probe=c0b180275b) | May 05, 2020 |
| HP            | 0A04h                       | Desktop     | [bb34c7e807](https://linux-hardware.org/?probe=bb34c7e807) | May 05, 2020 |
| Lenovo        | G50-70 20351                | Notebook    | [fea9f24d5a](https://linux-hardware.org/?probe=fea9f24d5a) | Apr 27, 2020 |
| Lenovo        | G50-70 20351                | Notebook    | [f6609c3613](https://linux-hardware.org/?probe=f6609c3613) | Apr 27, 2020 |
| ASUSTek       | UX31A                       | Notebook    | [2ce7c49619](https://linux-hardware.org/?probe=2ce7c49619) | Apr 16, 2020 |
| ASUSTek       | X542UAR                     | Notebook    | [1597291755](https://linux-hardware.org/?probe=1597291755) | Apr 03, 2020 |
| HP            | 3397                        | Desktop     | [37ddb2349c](https://linux-hardware.org/?probe=37ddb2349c) | Mar 20, 2020 |
| HP            | 250 G3                      | Notebook    | [e92714c5e6](https://linux-hardware.org/?probe=e92714c5e6) | Mar 18, 2020 |
| Dell          | Latitude E6510              | Notebook    | [bc7b29779f](https://linux-hardware.org/?probe=bc7b29779f) | Mar 08, 2020 |
| Packard Be... | EasyNote TK85               | Notebook    | [bf3776568a](https://linux-hardware.org/?probe=bf3776568a) | Feb 23, 2020 |
| HP            | EliteBook 8440p             | Notebook    | [2bc65b9511](https://linux-hardware.org/?probe=2bc65b9511) | Feb 22, 2020 |
| HP            | EliteBook 8440p             | Notebook    | [4ef298fd63](https://linux-hardware.org/?probe=4ef298fd63) | Feb 22, 2020 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [98c2d41201](https://linux-hardware.org/?probe=98c2d41201) | Feb 21, 2020 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [6b512c0e61](https://linux-hardware.org/?probe=6b512c0e61) | Feb 21, 2020 |
| Dell          | Latitude E5520              | Notebook    | [2994cbb1d2](https://linux-hardware.org/?probe=2994cbb1d2) | Feb 21, 2020 |
| Unknown       | Unknown                     | Phone       | [4ff689998e](https://linux-hardware.org/?probe=4ff689998e) | Feb 11, 2020 |
| Dell          | Inspiron 3521               | Notebook    | [35973fcba8](https://linux-hardware.org/?probe=35973fcba8) | Jan 01, 2020 |
| Medion        | P7615                       | Notebook    | [1402e4bf25](https://linux-hardware.org/?probe=1402e4bf25) | Dec 29, 2019 |
| Toshiba       | Satellite Pro C650          | Notebook    | [984a530b85](https://linux-hardware.org/?probe=984a530b85) | Dec 19, 2019 |
| Medion        | P7615                       | Notebook    | [56fdcbb995](https://linux-hardware.org/?probe=56fdcbb995) | Nov 25, 2019 |
| Medion        | P7615                       | Notebook    | [150034113d](https://linux-hardware.org/?probe=150034113d) | Nov 25, 2019 |
| Acer          | Aspire 7736                 | Notebook    | [64727a44db](https://linux-hardware.org/?probe=64727a44db) | Nov 24, 2019 |
| Acer          | Aspire 7736                 | Notebook    | [3415167cef](https://linux-hardware.org/?probe=3415167cef) | Nov 23, 2019 |
| HP            | 1494                        | Desktop     | [af749848e8](https://linux-hardware.org/?probe=af749848e8) | Nov 23, 2019 |
| Acer          | Aspire ES1-523              | Notebook    | [74c8472d6f](https://linux-hardware.org/?probe=74c8472d6f) | Nov 12, 2019 |
| ASUSTek       | X200MA                      | Notebook    | [860c71f889](https://linux-hardware.org/?probe=860c71f889) | Nov 10, 2019 |
| Acer          | Calpella                    | Notebook    | [6ff918b898](https://linux-hardware.org/?probe=6ff918b898) | Oct 29, 2019 |
| Dell          | Latitude 3590               | Notebook    | [8e1927b00a](https://linux-hardware.org/?probe=8e1927b00a) | Sep 22, 2019 |
| Lenovo        | ThinkPad T440 20B7S2MF01    | Notebook    | [4dc662ddb5](https://linux-hardware.org/?probe=4dc662ddb5) | Sep 04, 2019 |
| HP            | Laptop 15-bs0xx             | Notebook    | [73e92501d3](https://linux-hardware.org/?probe=73e92501d3) | Aug 29, 2019 |
| Dell          | 0D28YY A03                  | Desktop     | [0be7a39100](https://linux-hardware.org/?probe=0be7a39100) | Jul 14, 2019 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [d9903b4749](https://linux-hardware.org/?probe=d9903b4749) | May 14, 2019 |
| Toshiba       | Satellite L50-A-1DG         | Notebook    | [b0e44b3093](https://linux-hardware.org/?probe=b0e44b3093) | Apr 13, 2019 |
| Toshiba       | Satellite L50-A-1DG         | Notebook    | [1103235a87](https://linux-hardware.org/?probe=1103235a87) | Apr 13, 2019 |
| Acer          | Aspire E5-575               | Notebook    | [e7e29b676f](https://linux-hardware.org/?probe=e7e29b676f) | Mar 16, 2019 |
| Acer          | Aspire E5-575               | Notebook    | [4d2d0aa109](https://linux-hardware.org/?probe=4d2d0aa109) | Feb 20, 2019 |
| ASUSTek       | F5VL                        | Notebook    | [8c665a5eb1](https://linux-hardware.org/?probe=8c665a5eb1) | Feb 07, 2019 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [730a048dd9](https://linux-hardware.org/?probe=730a048dd9) | Dec 20, 2018 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [36a6a5ce8c](https://linux-hardware.org/?probe=36a6a5ce8c) | Dec 20, 2018 |
| ASUSTek       | F5VL                        | Notebook    | [d54a4a5d26](https://linux-hardware.org/?probe=d54a4a5d26) | Dec 12, 2018 |
| Lenovo        | ThinkPad X240 20AMA09VFR    | Notebook    | [8e1e3b46c5](https://linux-hardware.org/?probe=8e1e3b46c5) | Nov 26, 2018 |
| Lenovo        | ThinkPad X240 20AMA09VFR    | Notebook    | [b14f27a474](https://linux-hardware.org/?probe=b14f27a474) | Nov 26, 2018 |
| Dell          | 0DR845                      | Desktop     | [3e45e16507](https://linux-hardware.org/?probe=3e45e16507) | Sep 23, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Morocco/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 44        | 8.15%   |
| Ubuntu 22.04        | 41        | 7.59%   |
| Arch Rolling        | 22        | 4.07%   |
| Ubuntu 24.04        | 18        | 3.33%   |
| Ubuntu 18.04        | 17        | 3.15%   |
| Debian 11           | 16        | 2.96%   |
| OpenMandriva 4.2    | 12        | 2.22%   |
| Fedora 42           | 12        | 2.22%   |
| Fedora 39           | 12        | 2.22%   |
| ArcoLinux Rolling   | 12        | 2.22%   |
| KDE neon 20.04      | 11        | 2.04%   |
| Zorin 17            | 10        | 1.85%   |
| OpenMandriva 4.3    | 10        | 1.85%   |
| Zorin 16            | 9         | 1.67%   |
| Pop!_OS 22.04       | 8         | 1.48%   |
| OpenMandriva 24.12  | 7         | 1.3%    |
| Linux Mint 20.2     | 7         | 1.3%    |
| Fedora 41           | 7         | 1.3%    |
| Fedora 40           | 7         | 1.3%    |
| Fedora 38           | 7         | 1.3%    |
| Debian 12           | 7         | 1.3%    |
| OpenMandriva 23.01  | 6         | 1.11%   |
| Linux Mint 22.2     | 6         | 1.11%   |
| Linux Mint 22.1     | 6         | 1.11%   |
| Ubuntu Unity 16.04  | 5         | 0.93%   |
| Ubuntu 20.10        | 5         | 0.93%   |
| OpenMandriva 4.50   | 5         | 0.93%   |
| Linux Mint 20.3     | 5         | 0.93%   |
| Fedora 43           | 5         | 0.93%   |
| Fedora 33           | 5         | 0.93%   |
| EndeavourOS Rolling | 5         | 0.93%   |
| Elementary 7.1      | 5         | 0.93%   |
| Xero Rolling        | 4         | 0.74%   |
| Ubuntu 19.10        | 4         | 0.74%   |
| OpenMandriva 5.0    | 4         | 0.74%   |
| OpenMandriva 25.90  | 4         | 0.74%   |
| Linux Mint 21.3     | 4         | 0.74%   |
| Linux Mint 21       | 4         | 0.74%   |
| Arch                | 4         | 0.74%   |
| Ubuntu 23.10        | 3         | 0.56%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 140       | 27.67%  |
| OpenMandriva | 57        | 11.26%  |
| Fedora       | 56        | 11.07%  |
| Linux Mint   | 35        | 6.92%   |
| Debian       | 27        | 5.34%   |
| Arch         | 25        | 4.94%   |
| Zorin        | 22        | 4.35%   |
| Kali         | 18        | 3.56%   |
| Pop!_OS      | 14        | 2.77%   |
| Manjaro      | 13        | 2.57%   |
| KDE neon     | 13        | 2.57%   |
| ArcoLinux    | 12        | 2.37%   |
| Elementary   | 7         | 1.38%   |
| Ubuntu Unity | 6         | 1.19%   |
| EndeavourOS  | 6         | 1.19%   |
| Xubuntu      | 4         | 0.79%   |
| Xero         | 4         | 0.79%   |
| Ubuntu MATE  | 3         | 0.59%   |
| Lubuntu      | 3         | 0.59%   |
| Endless      | 3         | 0.59%   |
| Void Linux   | 2         | 0.4%    |
| SteamOS      | 2         | 0.4%    |
| Raspbian     | 2         | 0.4%    |
| Parrot       | 2         | 0.4%    |
| openSUSE     | 2         | 0.4%    |
| Nobara       | 2         | 0.4%    |
| NixOS        | 2         | 0.4%    |
| MX           | 2         | 0.4%    |
| LMDE         | 2         | 0.4%    |
| Kubuntu      | 2         | 0.4%    |
| Garuda Linux | 2         | 0.4%    |
| CentOS       | 2         | 0.4%    |
| BlackPanther | 2         | 0.4%    |
| Bazzite      | 2         | 0.4%    |
| ROSA         | 1         | 0.2%    |
| RHEL         | 1         | 0.2%    |
| Pear OS      | 1         | 0.2%    |
| Linux Lite   | 1         | 0.2%    |
| Deepin       | 1         | 0.2%    |
| BunsenLabs   | 1         | 0.2%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 12        | 2.09%   |
| 6.14.2-desktop-3omv2590  | 11        | 1.92%   |
| 5.16.7-desktop-1omv4003  | 11        | 1.92%   |
| 6.12.1-desktop-1omv2490  | 7         | 1.22%   |
| 6.2.0-33-generic         | 6         | 1.05%   |
| 6.1.1-desktop-1omv2290   | 6         | 1.05%   |
| 5.8.0-43-generic         | 5         | 0.87%   |
| 5.4.0-58-generic         | 5         | 0.87%   |
| 5.4.0-48-generic         | 5         | 0.87%   |
| 5.13.0-40-generic        | 5         | 0.87%   |
| 6.8.0-45-generic         | 4         | 0.7%    |
| 6.4.11-desktop-1omv2390  | 4         | 0.7%    |
| 5.4.0-42-generic         | 4         | 0.7%    |
| 5.15.0-46-generic        | 4         | 0.7%    |
| 5.12.4-desktop-1omv4050  | 4         | 0.7%    |
| 5.11.0-37-generic        | 4         | 0.7%    |
| 6.8.4-200.fc39.x86_64    | 3         | 0.52%   |
| 6.8.0-58-generic         | 3         | 0.52%   |
| 6.6.2-desktop-1omv2390   | 3         | 0.52%   |
| 6.5.0-26-generic         | 3         | 0.52%   |
| 6.5.0-21-generic         | 3         | 0.52%   |
| 6.5.0-14-generic         | 3         | 0.52%   |
| 6.2.0-37-generic         | 3         | 0.52%   |
| 6.14.0-63.fc42.x86_64    | 3         | 0.52%   |
| 6.14.0-37-generic        | 3         | 0.52%   |
| 6.14.0-29-generic        | 3         | 0.52%   |
| 6.10.0-desktop-1omv2490  | 3         | 0.52%   |
| 5.3.0-40-generic         | 3         | 0.52%   |
| 5.19.0-41-generic        | 3         | 0.52%   |
| 5.19.0-38-generic        | 3         | 0.52%   |
| 5.17.5-76051705-generic  | 3         | 0.52%   |
| 5.15.0-58-generic        | 3         | 0.52%   |
| 5.15.0-52-generic        | 3         | 0.52%   |
| 5.15.0-41-generic        | 3         | 0.52%   |
| 5.13.0-27-generic        | 3         | 0.52%   |
| 5.10.0-21-amd64          | 3         | 0.52%   |
| 6.8.0-60-generic         | 2         | 0.35%   |
| 6.8.0-50-generic         | 2         | 0.35%   |
| 6.8.0-39-generic         | 2         | 0.35%   |
| 6.7.9-arch1-1            | 2         | 0.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 41        | 7.47%   |
| 5.15.0  | 41        | 7.47%   |
| 6.8.0   | 22        | 4.01%   |
| 6.5.0   | 22        | 4.01%   |
| 5.8.0   | 18        | 3.28%   |
| 5.11.0  | 17        | 3.1%    |
| 5.10.0  | 17        | 3.1%    |
| 4.15.0  | 17        | 3.1%    |
| 6.2.0   | 15        | 2.73%   |
| 6.14.0  | 15        | 2.73%   |
| 5.13.0  | 14        | 2.55%   |
| 6.14.2  | 12        | 2.19%   |
| 5.3.0   | 12        | 2.19%   |
| 5.10.14 | 12        | 2.19%   |
| 6.1.0   | 11        | 2%      |
| 5.16.7  | 11        | 2%      |
| 6.11.0  | 10        | 1.82%   |
| 5.19.0  | 10        | 1.82%   |
| 6.12.1  | 7         | 1.28%   |
| 6.1.1   | 6         | 1.09%   |
| 5.0.0   | 6         | 1.09%   |
| 4.18.0  | 5         | 0.91%   |
| 6.7.9   | 4         | 0.73%   |
| 6.4.11  | 4         | 0.73%   |
| 6.10.3  | 4         | 0.73%   |
| 5.12.4  | 4         | 0.73%   |
| 6.8.4   | 3         | 0.55%   |
| 6.6.2   | 3         | 0.55%   |
| 6.2.9   | 3         | 0.55%   |
| 6.2.6   | 3         | 0.55%   |
| 6.17.7  | 3         | 0.55%   |
| 6.16.8  | 3         | 0.55%   |
| 6.12.48 | 3         | 0.55%   |
| 6.11.2  | 3         | 0.55%   |
| 6.10.0  | 3         | 0.55%   |
| 5.17.5  | 3         | 0.55%   |
| 5.14.0  | 3         | 0.55%   |
| 4.19.0  | 3         | 0.55%   |
| 6.9.6   | 2         | 0.36%   |
| 6.9.5   | 2         | 0.36%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 48        | 8.79%   |
| 5.4     | 41        | 7.51%   |
| 6.14    | 36        | 6.59%   |
| 5.10    | 35        | 6.41%   |
| 6.8     | 30        | 5.49%   |
| 6.5     | 29        | 5.31%   |
| 6.2     | 24        | 4.4%    |
| 5.8     | 21        | 3.85%   |
| 6.12    | 20        | 3.66%   |
| 5.11    | 20        | 3.66%   |
| 6.1     | 19        | 3.48%   |
| 6.11    | 18        | 3.3%    |
| 4.15    | 17        | 3.11%   |
| 6.6     | 16        | 2.93%   |
| 5.13    | 16        | 2.93%   |
| 5.19    | 14        | 2.56%   |
| 5.16    | 14        | 2.56%   |
| 6.17    | 12        | 2.2%    |
| 6.10    | 12        | 2.2%    |
| 5.3     | 12        | 2.2%    |
| 6.4     | 9         | 1.65%   |
| 6.16    | 8         | 1.47%   |
| 6.9     | 7         | 1.28%   |
| 6.3     | 6         | 1.1%    |
| 5.17    | 6         | 1.1%    |
| 5.14    | 6         | 1.1%    |
| 5.0     | 6         | 1.1%    |
| 4.18    | 6         | 1.1%    |
| 6.7     | 5         | 0.92%   |
| 6.15    | 5         | 0.92%   |
| 6.13    | 5         | 0.92%   |
| 5.18    | 5         | 0.92%   |
| 6.0     | 4         | 0.73%   |
| 5.12    | 4         | 0.73%   |
| 4.19    | 3         | 0.55%   |
| 5.7     | 1         | 0.18%   |
| 5.6     | 1         | 0.18%   |
| 4.9     | 1         | 0.18%   |
| 4.4     | 1         | 0.18%   |
| 4.14    | 1         | 0.18%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 479       | 97.16%  |
| i686   | 11        | 2.23%   |
| armv8l | 1         | 0.2%    |
| armv7l | 1         | 0.2%    |
| armv6l | 1         | 0.2%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 253       | 49.13%  |
| KDE5            | 71        | 13.79%  |
| XFCE            | 35        | 6.8%    |
| KDE6            | 35        | 6.8%    |
| Unknown         | 30        | 5.83%   |
| X-Cinnamon      | 27        | 5.24%   |
| KDE             | 9         | 1.75%   |
| MATE            | 8         | 1.55%   |
| Pantheon        | 7         | 1.36%   |
| Unity           | 6         | 1.17%   |
| LXQt            | 4         | 0.78%   |
| LXDE            | 4         | 0.78%   |
| i3              | 4         | 0.78%   |
| Hyprland        | 3         | 0.58%   |
| GNOME Classic   | 3         | 0.58%   |
| Cinnamon        | 3         | 0.58%   |
| KDE4            | 2         | 0.39%   |
| GNOME Flashback | 2         | 0.39%   |
| bspwm           | 2         | 0.39%   |
| xmonad          | 1         | 0.19%   |
| sway            | 1         | 0.19%   |
| qtile           | 1         | 0.19%   |
| niri            | 1         | 0.19%   |
| KDE:KDE-X11     | 1         | 0.19%   |
| DDE             | 1         | 0.19%   |
| Budgie          | 1         | 0.19%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 310       | 60.43%  |
| Wayland | 179       | 34.89%  |
| Unknown | 16        | 3.12%   |
| Tty     | 8         | 1.56%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 217       | 41.65%  |
| SDDM    | 102       | 19.58%  |
| GDM3    | 79        | 15.16%  |
| GDM     | 60        | 11.52%  |
| LightDM | 57        | 10.94%  |
| TDM     | 4         | 0.77%   |
| LY-DM   | 1         | 0.19%   |
| KDM     | 1         | 0.19%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 285       | 57%     |
| fr_FR      | 138       | 27.6%   |
| en_GB      | 22        | 4.4%    |
| Unknown    | 22        | 4.4%    |
| C          | 9         | 1.8%    |
| ru_RU      | 3         | 0.6%    |
| es_ES      | 3         | 0.6%    |
| de_DE      | 3         | 0.6%    |
| ar_MA      | 3         | 0.6%    |
| it_IT      | 2         | 0.4%    |
| en_AG      | 2         | 0.4%    |
| ar_EG      | 2         | 0.4%    |
| fr_MA      | 1         | 0.2%    |
| fr_CH      | 1         | 0.2%    |
| fr_BE      | 1         | 0.2%    |
| en_US.UTF8 | 1         | 0.2%    |
| en_NG      | 1         | 0.2%    |
| ar_DZ      | 1         | 0.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 294       | 58.33%  |
| EFI  | 210       | 41.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 340       | 67.46%  |
| Btrfs   | 72        | 14.29%  |
| Overlay | 50        | 9.92%   |
| Tmpfs   | 32        | 6.35%   |
| Xfs     | 5         | 0.99%   |
| Unknown | 5         | 0.99%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 216       | 42.86%  |
| GPT     | 211       | 41.87%  |
| MBR     | 77        | 15.28%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 429       | 85.46%  |
| Yes       | 73        | 14.54%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 334       | 66.27%  |
| Yes       | 170       | 33.73%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Hewlett-Packard                      | 165       | 33.54%  |
| Lenovo                               | 85        | 17.28%  |
| Dell                                 | 82        | 16.67%  |
| ASUSTek Computer                     | 40        | 8.13%   |
| Acer                                 | 21        | 4.27%   |
| Toshiba                              | 11        | 2.24%   |
| Apple                                | 10        | 2.03%   |
| Packard Bell                         | 6         | 1.22%   |
| MSI                                  | 5         | 1.02%   |
| Gigabyte Technology                  | 5         | 1.02%   |
| Foxconn                              | 5         | 1.02%   |
| Sony                                 | 4         | 0.81%   |
| Samsung Electronics                  | 4         | 0.81%   |
| Fujitsu                              | 4         | 0.81%   |
| Unknown                              | 4         | 0.81%   |
| Pegatron                             | 3         | 0.61%   |
| Medion                               | 3         | 0.61%   |
| TUXEDO                               | 2         | 0.41%   |
| Timi                                 | 2         | 0.41%   |
| Raspberry Pi Foundation              | 2         | 0.41%   |
| Microsoft                            | 2         | 0.41%   |
| HUAWEI                               | 2         | 0.41%   |
| Google                               | 2         | 0.41%   |
| eMachines                            | 2         | 0.41%   |
| American Megatrends                  | 2         | 0.41%   |
| Valve                                | 1         | 0.2%    |
| TrekStor                             | 1         | 0.2%    |
| Thomson                              | 1         | 0.2%    |
| SINTRONES                            | 1         | 0.2%    |
| Shenzhen Meigao Electronic Equipment | 1         | 0.2%    |
| Razer                                | 1         | 0.2%    |
| Mediacom                             | 1         | 0.2%    |
| Linx                                 | 1         | 0.2%    |
| LG Electronics                       | 1         | 0.2%    |
| InnJoo Technology                    | 1         | 0.2%    |
| HONOR                                | 1         | 0.2%    |
| GPD                                  | 1         | 0.2%    |
| Gateway                              | 1         | 0.2%    |
| Fujitsu Siemens                      | 1         | 0.2%    |
| ECS                                  | 1         | 0.2%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| HP ProDesk 600 G1 TWR                  | 5         | 1.02%   |
| Unknown                                | 5         | 1.02%   |
| HP EliteBook 8440p                     | 4         | 0.81%   |
| HP EliteBook 840 G5                    | 4         | 0.81%   |
| HP EliteBook 840 G2                    | 4         | 0.81%   |
| HP Pavilion g6                         | 3         | 0.61%   |
| HP Notebook                            | 3         | 0.61%   |
| HP Laptop 15-dw3xxx                    | 3         | 0.61%   |
| HP EliteDesk 800 G1 TWR                | 3         | 0.61%   |
| HP EliteDesk 800 G1 SFF                | 3         | 0.61%   |
| HP EliteBook 840 G3                    | 3         | 0.61%   |
| HP EliteBook 830 G5                    | 3         | 0.61%   |
| HP Compaq dc7800 Convertible Minitower | 3         | 0.61%   |
| Dell OptiPlex 7010                     | 3         | 0.61%   |
| ASUS X540LA                            | 3         | 0.61%   |
| Toshiba Satellite C660                 | 2         | 0.41%   |
| Timi TM1701                            | 2         | 0.41%   |
| Packard Bell EasyNote TS44HR           | 2         | 0.41%   |
| Lenovo ThinkBook 15 G2 ITL 20VE        | 2         | 0.41%   |
| Lenovo IdeaPad S145-15IIL 81W8         | 2         | 0.41%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK  | 2         | 0.41%   |
| Lenovo IdeaPad L3 15IML05 81Y3         | 2         | 0.41%   |
| HP ZBook 15 G3                         | 2         | 0.41%   |
| HP ZBook 15                            | 2         | 0.41%   |
| HP Z620 Workstation                    | 2         | 0.41%   |
| HP Z420 Workstation                    | 2         | 0.41%   |
| HP ProDesk 600 G1 SFF                  | 2         | 0.41%   |
| HP ProBook 6560b                       | 2         | 0.41%   |
| HP ProBook 650 G1                      | 2         | 0.41%   |
| HP ProBook 6470b                       | 2         | 0.41%   |
| HP ProBook 640 G1                      | 2         | 0.41%   |
| HP ProBook 450 G0                      | 2         | 0.41%   |
| HP Pavilion 15                         | 2         | 0.41%   |
| HP Laptop 15-ra0xx                     | 2         | 0.41%   |
| HP Laptop 15-dw2xxx                    | 2         | 0.41%   |
| HP Laptop 15-bs0xx                     | 2         | 0.41%   |
| HP EliteDesk 800 G2 SFF                | 2         | 0.41%   |
| HP EliteBook x360 1040 G7 Notebook PC  | 2         | 0.41%   |
| HP EliteBook 8460p                     | 2         | 0.41%   |
| HP Compaq Elite 8300 SFF               | 2         | 0.41%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Dell Latitude         | 43        | 8.74%   |
| Lenovo ThinkPad       | 42        | 8.54%   |
| HP EliteBook          | 35        | 7.11%   |
| HP Compaq             | 22        | 4.47%   |
| HP ProBook            | 21        | 4.27%   |
| Dell OptiPlex         | 15        | 3.05%   |
| Lenovo IdeaPad        | 14        | 2.85%   |
| HP Pavilion           | 12        | 2.44%   |
| HP Laptop             | 12        | 2.44%   |
| Acer Aspire           | 12        | 2.44%   |
| Toshiba Satellite     | 11        | 2.24%   |
| HP EliteDesk          | 11        | 2.24%   |
| HP ProDesk            | 9         | 1.83%   |
| Lenovo ThinkCentre    | 8         | 1.63%   |
| Dell Vostro           | 8         | 1.63%   |
| Dell Precision        | 8         | 1.63%   |
| HP 250                | 7         | 1.42%   |
| HP ZBook              | 6         | 1.22%   |
| ASUS ROG              | 6         | 1.22%   |
| Packard Bell EasyNote | 5         | 1.02%   |
| ASUS VivoBook         | 5         | 1.02%   |
| Unknown               | 5         | 1.02%   |
| Dell Inspiron         | 4         | 0.81%   |
| Acer Nitro            | 4         | 0.81%   |
| Lenovo Yoga           | 3         | 0.61%   |
| Lenovo ThinkBook      | 3         | 0.61%   |
| HP Notebook           | 3         | 0.61%   |
| Fujitsu LIFEBOOK      | 3         | 0.61%   |
| Dell XPS              | 3         | 0.61%   |
| ASUS ZenBook          | 3         | 0.61%   |
| ASUS X540LA           | 3         | 0.61%   |
| Timi TM1701           | 2         | 0.41%   |
| RPi Raspberry         | 2         | 0.41%   |
| Microsoft Surface     | 2         | 0.41%   |
| Lenovo ThinkStation   | 2         | 0.41%   |
| Lenovo Legion         | 2         | 0.41%   |
| HP Z620               | 2         | 0.41%   |
| HP Z420               | 2         | 0.41%   |
| HP OMEN               | 2         | 0.41%   |
| HP dc5000             | 2         | 0.41%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2013    | 50        | 10.16%  |
| 2018    | 44        | 8.94%   |
| 2011    | 40        | 8.13%   |
| 2014    | 36        | 7.32%   |
| 2020    | 34        | 6.91%   |
| 2016    | 31        | 6.3%    |
| 2010    | 31        | 6.3%    |
| 2015    | 30        | 6.1%    |
| 2017    | 29        | 5.89%   |
| 2012    | 28        | 5.69%   |
| 2021    | 25        | 5.08%   |
| 2019    | 24        | 4.88%   |
| 2009    | 17        | 3.46%   |
| 2023    | 14        | 2.85%   |
| 2022    | 13        | 2.64%   |
| 2007    | 12        | 2.44%   |
| 2008    | 11        | 2.24%   |
| 2024    | 10        | 2.03%   |
| 2006    | 5         | 1.02%   |
| 2004    | 3         | 0.61%   |
| 2005    | 2         | 0.41%   |
| Unknown | 2         | 0.41%   |
| 2025    | 1         | 0.2%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 351       | 71.34%  |
| Desktop        | 116       | 23.58%  |
| Convertible    | 10        | 2.03%   |
| All in one     | 5         | 1.02%   |
| Tablet         | 4         | 0.81%   |
| Mini pc        | 3         | 0.61%   |
| System on chip | 2         | 0.41%   |
| Phone          | 1         | 0.2%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 469       | 94.37%  |
| Enabled  | 28        | 5.63%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 489       | 99.39%  |
| Yes  | 3         | 0.61%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 166       | 33.13%  |
| 3.01-4.0    | 101       | 20.16%  |
| 8.01-16.0   | 77        | 15.37%  |
| 16.01-24.0  | 73        | 14.57%  |
| 1.01-2.0    | 26        | 5.19%   |
| 32.01-64.0  | 25        | 4.99%   |
| 24.01-32.0  | 13        | 2.59%   |
| 2.01-3.0    | 9         | 1.8%    |
| 64.01-256.0 | 8         | 1.6%    |
| 0.51-1.0    | 2         | 0.4%    |
| 0.01-0.5    | 1         | 0.2%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 167       | 30.81%  |
| 2.01-3.0  | 166       | 30.63%  |
| 4.01-8.0  | 94        | 17.34%  |
| 3.01-4.0  | 71        | 13.1%   |
| 0.51-1.0  | 26        | 4.8%    |
| 8.01-16.0 | 14        | 2.58%   |
| 0.01-0.5  | 4         | 0.74%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 361       | 72.2%   |
| 2      | 108       | 21.6%   |
| 3      | 25        | 5%      |
| 4      | 5         | 1%      |
| 0      | 1         | 0.2%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 300       | 60.73%  |
| Yes       | 194       | 39.27%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 430       | 87.4%   |
| No        | 62        | 12.6%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 437       | 88.1%   |
| No        | 59        | 11.9%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 316       | 63.45%  |
| No        | 182       | 36.55%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Morocco | 492       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Computers | Percent |
|-------------------------|-----------|---------|
| Casablanca              | 148       | 27.41%  |
| Marrakesh               | 56        | 10.37%  |
| Agadir                  | 40        | 7.41%   |
| Rabat                   | 39        | 7.22%   |
| Fes                     | 31        | 5.74%   |
| Tangier                 | 29        | 5.37%   |
| Salé                   | 25        | 4.63%   |
| Kenitra                 | 21        | 3.89%   |
| Oujda                   | 16        | 2.96%   |
| Meknes                  | 15        | 2.78%   |
| Khouribga               | 7         | 1.3%    |
| El Jadida               | 7         | 1.3%    |
| Tétouan                | 6         | 1.11%   |
| Tiznit                  | 5         | 0.93%   |
| Taza                    | 5         | 0.93%   |
| Safi                    | 5         | 0.93%   |
| Nador                   | 5         | 0.93%   |
| Mohammedia              | 5         | 0.93%   |
| Beni Mellal             | 5         | 0.93%   |
| Temara                  | 4         | 0.74%   |
| Méchouar de Casablanca | 4         | 0.74%   |
| Berkane                 | 4         | 0.74%   |
| Sidi Ifni               | 3         | 0.56%   |
| Settat                  | 3         | 0.56%   |
| Martil                  | 3         | 0.56%   |
| Khemisset               | 3         | 0.56%   |
| Guelmim                 | 3         | 0.56%   |
| Azamor                  | 3         | 0.56%   |
| Youssoufia              | 2         | 0.37%   |
| Targuist                | 2         | 0.37%   |
| Skhirate                | 2         | 0.37%   |
| Imouzzer Kandar         | 2         | 0.37%   |
| Berrechid               | 2         | 0.37%   |
| Tit Mellil              | 1         | 0.19%   |
| Taourirt                | 1         | 0.19%   |
| Taounate                | 1         | 0.19%   |
| Tan-Tan                 | 1         | 0.19%   |
| Sidi Slimane            | 1         | 0.19%   |
| Sidi Lmokhtar           | 1         | 0.19%   |
| Sidi Kacem              | 1         | 0.19%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 93        | 112    | 14.86%  |
| WDC                         | 83        | 111    | 13.26%  |
| Seagate                     | 82        | 105    | 13.1%   |
| Toshiba                     | 57        | 76     | 9.11%   |
| Hitachi                     | 32        | 39     | 5.11%   |
| Sandisk                     | 30        | 34     | 4.79%   |
| Unknown                     | 28        | 36     | 4.47%   |
| SK hynix                    | 23        | 26     | 3.67%   |
| Intel                       | 19        | 24     | 3.04%   |
| HGST                        | 18        | 20     | 2.88%   |
| Micron Technology           | 16        | 22     | 2.56%   |
| Kingston                    | 16        | 25     | 2.56%   |
| Apple                       | 10        | 11     | 1.6%    |
| KIOXIA                      | 9         | 9      | 1.44%   |
| PNY                         | 8         | 11     | 1.28%   |
| China                       | 7         | 8      | 1.12%   |
| LITEON                      | 6         | 6      | 0.96%   |
| Crucial                     | 6         | 7      | 0.96%   |
| Unknown                     | 6         | 6      | 0.96%   |
| Lexar                       | 4         | 4      | 0.64%   |
| KingFast                    | 4         | 5      | 0.64%   |
| Fujitsu                     | 4         | 4      | 0.64%   |
| Phison Electronics          | 3         | 4      | 0.48%   |
| Phison                      | 3         | 4      | 0.48%   |
| Kingston Technology Company | 3         | 3      | 0.48%   |
| TwinMOS                     | 2         | 2      | 0.32%   |
| Supersonic                  | 2         | 6      | 0.32%   |
| SPCC                        | 2         | 4      | 0.32%   |
| MSI                         | 2         | 2      | 0.32%   |
| LITEONIT                    | 2         | 2      | 0.32%   |
| KODAK                       | 2         | 2      | 0.32%   |
| KingSpec                    | 2         | 4      | 0.32%   |
| KingDian                    | 2         | 9      | 0.32%   |
| GOODRAM                     | 2         | 2      | 0.32%   |
| AFOX                        | 2         | 2      | 0.32%   |
| A-DATA Technology           | 2         | 2      | 0.32%   |
| XUM                         | 1         | 1      | 0.16%   |
| X12                         | 1         | 1      | 0.16%   |
| Union Memory (Shenzhen)     | 1         | 1      | 0.16%   |
| Transcend                   | 1         | 1      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Seagate ST500LT012-1DG142 500GB                      | 7         | 1.07%   |
| Seagate ST500DM002-1BD142 500GB                      | 7         | 1.07%   |
| Seagate ST1000LM035-1RK172 1TB                       | 7         | 1.07%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB    | 7         | 1.07%   |
| Unknown MMC Card  64GB                               | 6         | 0.92%   |
| Toshiba MQ04ABF100 1TB                               | 6         | 0.92%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1024GB | 6         | 0.92%   |
| Unknown                                              | 6         | 0.92%   |
| Unknown MMC Card  32GB                               | 5         | 0.76%   |
| Toshiba MQ01ABF050 500GB                             | 5         | 0.76%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 5         | 0.76%   |
| Kingston SA400S37480G 480GB SSD                      | 5         | 0.76%   |
| HGST HTS545050A7E680 500GB                           | 5         | 0.76%   |
| WDC WD5000AAKX-60U6AA0 500GB                         | 4         | 0.61%   |
| Toshiba MQ01ABD050 500GB                             | 4         | 0.61%   |
| Seagate ST9500325AS 500GB                            | 4         | 0.61%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB     | 4         | 0.61%   |
| Samsung NVMe SSD Drive 512GB                         | 4         | 0.61%   |
| Samsung MZVLW256HEHP-000L7 256GB                     | 4         | 0.61%   |
| Intel SSDSC2BF180A4H 180GB                           | 4         | 0.61%   |
| Hitachi HUA723020ALA641 2TB                          | 4         | 0.61%   |
| HGST HTS725050A7E630 500GB                           | 4         | 0.61%   |
| WDC WD10SPZX-60Z10T0 1TB                             | 3         | 0.46%   |
| Toshiba MQ01ACF050 500GB                             | 3         | 0.46%   |
| Toshiba MQ01ABD100 1TB                               | 3         | 0.46%   |
| Toshiba KXG50ZNV256G 256GB                           | 3         | 0.46%   |
| Toshiba BG3 NVMe SSD Controller 256GB                | 3         | 0.46%   |
| SK hynix BC501 NVMe Solid State Drive 512GB          | 3         | 0.46%   |
| Seagate ST500LM000-1EJ162 500GB                      | 3         | 0.46%   |
| Seagate ST3250312AS 250GB                            | 3         | 0.46%   |
| Samsung NVMe SSD Drive 256GB                         | 3         | 0.46%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB   | 3         | 0.46%   |
| PNY CS900 120GB SSD                                  | 3         | 0.46%   |
| LITEON IT LCS-128L9S-HP 128GB SSD                    | 3         | 0.46%   |
| Kingston SA400S37120G 120GB SSD                      | 3         | 0.46%   |
| Hitachi HTS541616J9SA00 160GB                        | 3         | 0.46%   |
| WDC WD800JD-00LSA0 80GB                              | 2         | 0.31%   |
| WDC WD5000LPCX-80VHAT1 500GB                         | 2         | 0.31%   |
| WDC WD5000LPCX-60VHAT0 500GB                         | 2         | 0.31%   |
| WDC WD5000AZLX-60K2TA0 500GB                         | 2         | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 82        | 105    | 30.15%  |
| WDC                 | 76        | 104    | 27.94%  |
| Toshiba             | 43        | 54     | 15.81%  |
| Hitachi             | 32        | 39     | 11.76%  |
| HGST                | 18        | 20     | 6.62%   |
| Samsung Electronics | 8         | 11     | 2.94%   |
| Fujitsu             | 4         | 4      | 1.47%   |
| Apple               | 4         | 4      | 1.47%   |
| Maxtor              | 1         | 1      | 0.37%   |
| Magnetic Data       | 1         | 1      | 0.37%   |
| Intenso             | 1         | 2      | 0.37%   |
| IBM/Hitachi         | 1         | 1      | 0.37%   |
| HPE                 | 1         | 2      | 0.37%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 35        | 42     | 20.71%  |
| Kingston            | 14        | 22     | 8.28%   |
| SanDisk             | 12        | 13     | 7.1%    |
| Micron Technology   | 10        | 16     | 5.92%   |
| PNY                 | 8         | 11     | 4.73%   |
| Intel               | 7         | 8      | 4.14%   |
| China               | 7         | 8      | 4.14%   |
| LITEON              | 6         | 6      | 3.55%   |
| Crucial             | 6         | 7      | 3.55%   |
| SK hynix            | 5         | 7      | 2.96%   |
| Lexar               | 4         | 4      | 2.37%   |
| Apple               | 4         | 4      | 2.37%   |
| Unknown             | 4         | 4      | 2.37%   |
| Toshiba             | 3         | 3      | 1.78%   |
| KingFast            | 3         | 3      | 1.78%   |
| WDC                 | 2         | 2      | 1.18%   |
| TwinMOS             | 2         | 2      | 1.18%   |
| Supersonic          | 2         | 3      | 1.18%   |
| SPCC                | 2         | 4      | 1.18%   |
| MSI                 | 2         | 2      | 1.18%   |
| LITEONIT            | 2         | 2      | 1.18%   |
| KODAK               | 2         | 2      | 1.18%   |
| KingSpec            | 2         | 4      | 1.18%   |
| KingDian            | 2         | 9      | 1.18%   |
| GOODRAM             | 2         | 2      | 1.18%   |
| AFOX                | 2         | 2      | 1.18%   |
| XUM                 | 1         | 1      | 0.59%   |
| X12                 | 1         | 1      | 0.59%   |
| Transcend           | 1         | 1      | 0.59%   |
| Team                | 1         | 1      | 0.59%   |
| RCESSD              | 1         | 1      | 0.59%   |
| Mushkin             | 1         | 1      | 0.59%   |
| Min Yi U            | 1         | 1      | 0.59%   |
| Indilinx            | 1         | 1      | 0.59%   |
| HS-SSD-E100         | 1         | 1      | 0.59%   |
| Hewlett-Packard     | 1         | 1      | 0.59%   |
| Gigabyte Technology | 1         | 1      | 0.59%   |
| Geonix              | 1         | 1      | 0.59%   |
| ESSENCORE           | 1         | 1      | 0.59%   |
| Corsair             | 1         | 1      | 0.59%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 246       | 348    | 42.71%  |
| SSD     | 156       | 211    | 27.08%  |
| NVMe    | 141       | 183    | 24.48%  |
| MMC     | 27        | 35     | 4.69%   |
| Unknown | 6         | 10     | 1.04%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 362       | 563    | 67.66%  |
| NVMe | 140       | 181    | 26.17%  |
| MMC  | 27        | 35     | 5.05%   |
| SAS  | 6         | 8      | 1.12%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 279       | 387    | 70.45%  |
| 0.51-1.0   | 93        | 136    | 23.48%  |
| 1.01-2.0   | 18        | 27     | 4.55%   |
| 3.01-4.0   | 2         | 3      | 0.51%   |
| 2.01-3.0   | 2         | 3      | 0.51%   |
| 4.01-10.0  | 2         | 3      | 0.51%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 158       | 30.62%  |
| 251-500        | 124       | 24.03%  |
| 501-1000       | 60        | 11.63%  |
| 51-100         | 52        | 10.08%  |
| 1-20           | 46        | 8.91%   |
| 21-50          | 28        | 5.43%   |
| 1001-2000      | 25        | 4.84%   |
| Unknown        | 13        | 2.52%   |
| More than 3000 | 7         | 1.36%   |
| 2001-3000      | 3         | 0.58%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 215       | 39.52%  |
| 21-50          | 124       | 22.79%  |
| 101-250        | 74        | 13.6%   |
| 51-100         | 67        | 12.32%  |
| 251-500        | 29        | 5.33%   |
| Unknown        | 13        | 2.39%   |
| 501-1000       | 11        | 2.02%   |
| 1001-2000      | 6         | 1.1%    |
| More than 3000 | 4         | 0.74%   |
| 2001-3000      | 1         | 0.18%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 4         | 4      | 5.48%   |
| Toshiba MQ01ABD050 500GB            | 3         | 3      | 4.11%   |
| Seagate ST9500325AS 500GB           | 3         | 4      | 4.11%   |
| HGST HTS545050A7E680 500GB          | 3         | 4      | 4.11%   |
| Seagate ST500LM021-1KJ152 500GB     | 2         | 2      | 2.74%   |
| Hitachi HTS542525K9A300 250GB       | 2         | 2      | 2.74%   |
| Hitachi HDS721680PLA380 80GB        | 2         | 3      | 2.74%   |
| X12 SSD 512GB                       | 1         | 1      | 1.37%   |
| WDC WD800AAJS-60WAA0 80GB           | 1         | 1      | 1.37%   |
| WDC WD7500BPKX-80HPJT0 752GB        | 1         | 1      | 1.37%   |
| WDC WD5000BPVT-22HXZT1 500GB        | 1         | 1      | 1.37%   |
| WDC WD2500BPVT-00JJ5T0 250GB        | 1         | 1      | 1.37%   |
| WDC WD2500BEVT-60ZCT1 250GB         | 1         | 1      | 1.37%   |
| WDC WD2500BEVS-22UST0 250GB         | 1         | 1      | 1.37%   |
| WDC WD2500BEKT-60A25T1 250GB        | 1         | 1      | 1.37%   |
| WDC WD2500AAJS-60Z0A0 250GB         | 1         | 1      | 1.37%   |
| WDC WD1602ABJS-43P5A0 160GB         | 1         | 1      | 1.37%   |
| WDC WD1200BEVS-60UST0 120GB         | 1         | 2      | 1.37%   |
| WDC WD10SPZX-60Z10T0 1TB            | 1         | 1      | 1.37%   |
| WDC WD10JPVX-60JC3T0 1TB            | 1         | 8      | 1.37%   |
| WDC WD10JPVT-00A1YT0 1TB            | 1         | 1      | 1.37%   |
| Toshiba MQ04ABF100 1TB              | 1         | 1      | 1.37%   |
| Toshiba MQ01ACF050 500GB            | 1         | 1      | 1.37%   |
| Toshiba MQ01ABD032 320GB            | 1         | 1      | 1.37%   |
| Toshiba MK3265GSX H 320GB           | 1         | 1      | 1.37%   |
| Toshiba MK2565GSXN 250GB            | 1         | 1      | 1.37%   |
| Toshiba MK1237GSX 120GB             | 1         | 1      | 1.37%   |
| Seagate ST9500423AS 500GB           | 1         | 1      | 1.37%   |
| Seagate ST9320423AS 320GB           | 1         | 1      | 1.37%   |
| Seagate ST9100824AS 100GB           | 1         | 1      | 1.37%   |
| Seagate ST500LT012-1DG142 500GB     | 1         | 1      | 1.37%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1         | 1      | 1.37%   |
| Seagate ST500LM000-1EJ162 500GB     | 1         | 1      | 1.37%   |
| Seagate ST340016A 40GB              | 1         | 1      | 1.37%   |
| Seagate ST340014AS 40GB             | 1         | 1      | 1.37%   |
| Seagate ST3250318AS 250GB           | 1         | 1      | 1.37%   |
| Seagate ST3250312AS 250GB           | 1         | 1      | 1.37%   |
| Seagate ST3160318AS 160GB           | 1         | 1      | 1.37%   |
| Seagate ST1000DM010-2EP102 1TB      | 1         | 1      | 1.37%   |
| SanDisk SD7UB3Q256G1001 256GB SSD   | 1         | 1      | 1.37%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 20        | 22     | 27.78%  |
| WDC                 | 13        | 21     | 18.06%  |
| Toshiba             | 9         | 9      | 12.5%   |
| Hitachi             | 9         | 11     | 12.5%   |
| HGST                | 6         | 7      | 8.33%   |
| Samsung Electronics | 3         | 3      | 4.17%   |
| Intel               | 2         | 3      | 2.78%   |
| Fujitsu             | 2         | 2      | 2.78%   |
| X12                 | 1         | 1      | 1.39%   |
| SanDisk             | 1         | 1      | 1.39%   |
| Micron Technology   | 1         | 1      | 1.39%   |
| Maxtor              | 1         | 1      | 1.39%   |
| Kingston            | 1         | 2      | 1.39%   |
| HPE                 | 1         | 2      | 1.39%   |
| Corsair             | 1         | 1      | 1.39%   |
| Apple               | 1         | 1      | 1.39%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 20        | 22     | 31.75%  |
| WDC                 | 13        | 21     | 20.63%  |
| Toshiba             | 9         | 9      | 14.29%  |
| Hitachi             | 9         | 11     | 14.29%  |
| HGST                | 6         | 7      | 9.52%   |
| Fujitsu             | 2         | 2      | 3.17%   |
| Samsung Electronics | 1         | 1      | 1.59%   |
| Maxtor              | 1         | 1      | 1.59%   |
| HPE                 | 1         | 2      | 1.59%   |
| Apple               | 1         | 1      | 1.59%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 60        | 77     | 86.96%  |
| SSD  | 8         | 9      | 11.59%  |
| NVMe | 1         | 2      | 1.45%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                      | Computers | Drives | Percent |
|--------------------------------------------|-----------|--------|---------|
| WDC WD800JD-00LSA0 80GB                    | 2         | 3      | 40%     |
| WDC WD2500BEVT-22A23T0 250GB               | 1         | 2      | 20%     |
| SK hynix BC501 NVMe 256GB                  | 1         | 1      | 20%     |
| Samsung Electronics MZVLB1T0HALR-00000 1TB | 1         | 1      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 3         | 5      | 60%     |
| SK hynix            | 1         | 1      | 20%     |
| Samsung Electronics | 1         | 1      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 280       | 429    | 51.85%  |
| Works    | 187       | 263    | 34.63%  |
| Malfunc  | 68        | 88     | 12.59%  |
| Failed   | 5         | 7      | 0.93%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 383       | 68.39%  |
| Samsung Electronics              | 53        | 9.46%   |
| AMD                              | 29        | 5.18%   |
| SanDisk                          | 21        | 3.75%   |
| SK hynix                         | 18        | 3.21%   |
| Toshiba America Info Systems     | 11        | 1.96%   |
| KIOXIA                           | 9         | 1.61%   |
| Phison Electronics               | 6         | 1.07%   |
| Micron Technology                | 6         | 1.07%   |
| Kingston Technology Company      | 5         | 0.89%   |
| Nvidia                           | 3         | 0.54%   |
| Silicon Integrated Systems [SiS] | 2         | 0.36%   |
| ADATA Technology                 | 2         | 0.36%   |
| Union Memory (Shenzhen)          | 1         | 0.18%   |
| Solidigm                         | 1         | 0.18%   |
| Silicon Motion                   | 1         | 0.18%   |
| Shenzhen Longsys Electronics     | 1         | 0.18%   |
| Realtek Semiconductor            | 1         | 0.18%   |
| O2 Micro                         | 1         | 0.18%   |
| Micron/Crucial Technology        | 1         | 0.18%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.18%   |
| LSI Logic / Symbios Logic        | 1         | 0.18%   |
| JMicron Technology               | 1         | 0.18%   |
| Broadcom / LSI                   | 1         | 0.18%   |
| Apple                            | 1         | 0.18%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 33        | 5.21%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 32        | 5.06%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 32        | 5.06%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 26        | 4.11%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 24        | 3.79%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 20        | 3.16%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 19        | 3%      |
| AMD FCH SATA Controller [AHCI mode]                                              | 19        | 3%      |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 18        | 2.84%   |
| Intel SATA Controller [RAID mode]                                                | 16        | 2.53%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 15        | 2.37%   |
| Intel Volume Management Device NVMe RAID Controller                              | 15        | 2.37%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 13        | 2.05%   |
| Intel Tiger Lake-LP SATA Controller                                              | 12        | 1.9%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 12        | 1.9%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 12        | 1.9%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 10        | 1.58%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 9         | 1.42%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 9         | 1.42%   |
| Intel Comet Lake SATA AHCI Controller                                            | 8         | 1.26%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 8         | 1.26%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 6         | 0.95%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 5         | 0.79%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 5         | 0.79%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 5         | 0.79%   |
| Intel RST Volume Management Device Controller                                    | 5         | 0.79%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 5         | 0.79%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 4         | 0.63%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                             | 4         | 0.63%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 4         | 0.63%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 4         | 0.63%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                              | 4         | 0.63%   |
| Intel C600/X79 series chipset IDE-r Controller                                   | 4         | 0.63%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4         | 0.63%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                               | 4         | 0.63%   |
| Intel 82Q35 Express PT IDER Controller                                           | 4         | 0.63%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]              | 4         | 0.63%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                     | 4         | 0.63%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 4         | 0.63%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                       | 4         | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 323       | 55.03%  |
| NVMe | 140       | 23.85%  |
| RAID | 70        | 11.93%  |
| IDE  | 49        | 8.35%   |
| SAS  | 4         | 0.68%   |
| SCSI | 1         | 0.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 442       | 89.84%  |
| AMD    | 47        | 9.55%   |
| ARM    | 3         | 0.61%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz       | 12        | 2.44%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 11        | 2.24%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 9         | 1.83%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 7         | 1.42%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 7         | 1.42%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 7         | 1.42%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 7         | 1.42%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 7         | 1.42%   |
| Intel Core i3-4005U CPU @ 1.70GHz       | 7         | 1.42%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 6         | 1.22%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 6         | 1.22%   |
| Intel Core i3-5005U CPU @ 2.00GHz       | 6         | 1.22%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 6         | 1.22%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 5         | 1.02%   |
| Intel Core i5-4590 CPU @ 3.30GHz        | 5         | 1.02%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 5         | 1.02%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 5         | 1.02%   |
| Intel Core i5-2410M CPU @ 2.30GHz       | 5         | 1.02%   |
| Intel Core i5-10310U CPU @ 1.70GHz      | 5         | 1.02%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 5         | 1.02%   |
| Intel Core i5 CPU M 560 @ 2.67GHz       | 5         | 1.02%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 4         | 0.81%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 4         | 0.81%   |
| Intel Core i5-4570 CPU @ 3.20GHz        | 4         | 0.81%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 4         | 0.81%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 4         | 0.81%   |
| Intel Celeron CPU N3060 @ 1.60GHz       | 4         | 0.81%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 3         | 0.61%   |
| Intel Core i5-8365U CPU @ 1.60GHz       | 3         | 0.61%   |
| Intel Core i5-6500 CPU @ 3.20GHz        | 3         | 0.61%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 3         | 0.61%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 3         | 0.61%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 3         | 0.61%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 3         | 0.61%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 3         | 0.61%   |
| Intel Core i3-6006U CPU @ 2.00GHz       | 3         | 0.61%   |
| Intel Core i3-2310M CPU @ 2.10GHz       | 3         | 0.61%   |
| Intel Core i3 CPU M 350 @ 2.27GHz       | 3         | 0.61%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 3         | 0.61%   |
| Intel Celeron CPU N2840 @ 2.16GHz       | 3         | 0.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 180       | 36.59%  |
| Intel Core i7           | 78        | 15.85%  |
| Intel Core i3           | 54        | 10.98%  |
| Other                   | 46        | 9.35%   |
| Intel Core 2 Duo        | 22        | 4.47%   |
| Intel Celeron           | 14        | 2.85%   |
| Intel Xeon              | 12        | 2.44%   |
| AMD Ryzen 5             | 12        | 2.44%   |
| Intel Atom              | 9         | 1.83%   |
| AMD Ryzen 7             | 9         | 1.83%   |
| Intel Pentium Dual-Core | 4         | 0.81%   |
| Intel Pentium           | 4         | 0.81%   |
| AMD Ryzen 9             | 4         | 0.81%   |
| Intel Pentium 4         | 3         | 0.61%   |
| Intel Core 2            | 3         | 0.61%   |
| AMD E1                  | 3         | 0.61%   |
| Intel Pentium Dual      | 2         | 0.41%   |
| Intel Core i9           | 2         | 0.41%   |
| Intel Core 2 Quad       | 2         | 0.41%   |
| Intel Core              | 2         | 0.41%   |
| ARM BCM                 | 2         | 0.41%   |
| AMD C-60                | 2         | 0.41%   |
| AMD Athlon 64 X2        | 2         | 0.41%   |
| AMD A8                  | 2         | 0.41%   |
| AMD A6                  | 2         | 0.41%   |
| Intel Pentium Silver    | 1         | 0.2%    |
| Intel Pentium M         | 1         | 0.2%    |
| Intel Pentium Gold      | 1         | 0.2%    |
| Intel Genuine           | 1         | 0.2%    |
| Intel Core m5           | 1         | 0.2%    |
| Intel Core m3           | 1         | 0.2%    |
| Intel Celeron M         | 1         | 0.2%    |
| ARM AArch64             | 1         | 0.2%    |
| AMD Ryzen 7 PRO         | 1         | 0.2%    |
| AMD Ryzen 5 PRO         | 1         | 0.2%    |
| AMD Ryzen 3 PRO         | 1         | 0.2%    |
| AMD Ryzen 3             | 1         | 0.2%    |
| AMD Phenom II X6        | 1         | 0.2%    |
| AMD E                   | 1         | 0.2%    |
| AMD Athlon XP           | 1         | 0.2%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 238       | 48.37%  |
| 4      | 176       | 35.77%  |
| 6      | 25        | 5.08%   |
| 8      | 18        | 3.66%   |
| 1      | 11        | 2.24%   |
| 10     | 7         | 1.42%   |
| 12     | 6         | 1.22%   |
| 16     | 5         | 1.02%   |
| 14     | 5         | 1.02%   |
| 24     | 1         | 0.2%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 487       | 98.98%  |
| 2      | 5         | 1.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 355       | 72.15%  |
| 1      | 137       | 27.85%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 482       | 97.97%  |
| 32-bit         | 6         | 1.22%   |
| Unknown        | 4         | 0.81%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 266       | 52.88%  |
| 0x206a7    | 28        | 5.57%   |
| 0x306c3    | 19        | 3.78%   |
| 0x306a9    | 17        | 3.38%   |
| 0x806ea    | 15        | 2.98%   |
| 0x306d4    | 14        | 2.78%   |
| 0x40651    | 12        | 2.39%   |
| 0x806ec    | 10        | 1.99%   |
| 0x20655    | 9         | 1.79%   |
| 0x1067a    | 9         | 1.79%   |
| 0x806c1    | 7         | 1.39%   |
| 0x506e3    | 7         | 1.39%   |
| 0x406e3    | 7         | 1.39%   |
| 0x806e9    | 6         | 1.19%   |
| 0x6fd      | 6         | 1.19%   |
| 0x20652    | 5         | 0.99%   |
| 0x30678    | 4         | 0.8%    |
| 0x10676    | 4         | 0.8%    |
| 0x906e9    | 3         | 0.6%    |
| 0x90675    | 3         | 0.6%    |
| 0x6fb      | 3         | 0.6%    |
| 0x206d7    | 3         | 0.6%    |
| 0x0a50000c | 3         | 0.6%    |
| 0x08701021 | 3         | 0.6%    |
| 0x906ea    | 2         | 0.4%    |
| 0x706e5    | 2         | 0.4%    |
| 0x406c4    | 2         | 0.4%    |
| 0x406c3    | 2         | 0.4%    |
| 0x08108102 | 2         | 0.4%    |
| 0x07030105 | 2         | 0.4%    |
| 0x0700010f | 2         | 0.4%    |
| 0x05000119 | 2         | 0.4%    |
| 0xf41      | 1         | 0.2%    |
| 0xf29      | 1         | 0.2%    |
| 0xb06a3    | 1         | 0.2%    |
| 0x806eb    | 1         | 0.2%    |
| 0x806d1    | 1         | 0.2%    |
| 0x706a1    | 1         | 0.2%    |
| 0x6ec      | 1         | 0.2%    |
| 0x6e8      | 1         | 0.2%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 81        | 16.46%  |
| Haswell          | 69        | 14.02%  |
| Skylake          | 42        | 8.54%   |
| SandyBridge      | 42        | 8.54%   |
| IvyBridge        | 31        | 6.3%    |
| Westmere         | 29        | 5.89%   |
| Unknown          | 29        | 5.89%   |
| Broadwell        | 24        | 4.88%   |
| TigerLake        | 21        | 4.27%   |
| Penryn           | 20        | 4.07%   |
| Silvermont       | 15        | 3.05%   |
| Core             | 15        | 3.05%   |
| Alderlake Hybrid | 11        | 2.24%   |
| Zen 3            | 8         | 1.63%   |
| IceLake          | 7         | 1.42%   |
| Zen+             | 5         | 1.02%   |
| Zen 2            | 5         | 1.02%   |
| CometLake        | 5         | 1.02%   |
| Bobcat           | 4         | 0.81%   |
| P6               | 3         | 0.61%   |
| NetBurst         | 3         | 0.61%   |
| Bonnell          | 3         | 0.61%   |
| Puma             | 2         | 0.41%   |
| Nehalem          | 2         | 0.41%   |
| K8 Hammer        | 2         | 0.41%   |
| Jaguar           | 2         | 0.41%   |
| Goldmont plus    | 2         | 0.41%   |
| Excavator        | 2         | 0.41%   |
| Zen              | 1         | 0.2%    |
| Piledriver       | 1         | 0.2%    |
| Lunarlake Hybrid | 1         | 0.2%    |
| K6               | 1         | 0.2%    |
| K10 Llano        | 1         | 0.2%    |
| K10              | 1         | 0.2%    |
| Gracemont        | 1         | 0.2%    |
| Goldmont         | 1         | 0.2%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 386       | 65.42%  |
| Nvidia                           | 130       | 22.03%  |
| AMD                              | 73        | 12.37%  |
| Silicon Integrated Systems [SiS] | 1         | 0.17%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 33        | 5.5%    |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 27        | 4.5%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 27        | 4.5%    |
| Intel Core Processor Integrated Graphics Controller                                      | 21        | 3.5%    |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 21        | 3.5%    |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 20        | 3.33%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 19        | 3.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 18        | 3%      |
| Intel 3rd Gen Core processor Graphics Controller                                         | 16        | 2.67%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 13        | 2.17%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 12        | 2%      |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 12        | 2%      |
| Intel Skylake-S GT2 [HD Graphics 530]                                                    | 10        | 1.67%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 10        | 1.67%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 9         | 1.5%    |
| Intel Skylake-H GT2 [HD Graphics 530]                                                    | 8         | 1.33%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 8         | 1.33%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 6         | 1%      |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 6         | 1%      |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 1%      |
| Nvidia GM108M [GeForce 840M]                                                             | 5         | 0.83%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 5         | 0.83%   |
| Intel Raptor Lake-P [UHD Graphics]                                                       | 5         | 0.83%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 5         | 0.83%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 0.83%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 5         | 0.83%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 5         | 0.83%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 0.67%   |
| Nvidia GM107GL [Quadro K2200]                                                            | 4         | 0.67%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 4         | 0.67%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 4         | 0.67%   |
| Intel Kaby Lake-S GT2 [HD Graphics 630]                                                  | 4         | 0.67%   |
| AMD Lucienne                                                                             | 4         | 0.67%   |
| Nvidia TU117M [GeForce MX450]                                                            | 3         | 0.5%    |
| Nvidia GT218 [GeForce 210]                                                               | 3         | 0.5%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 0.5%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 3         | 0.5%    |
| Nvidia GM204GL [Quadro M4000]                                                            | 3         | 0.5%    |
| Nvidia GM108M [GeForce 940MX]                                                            | 3         | 0.5%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 3         | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 288       | 58.18%  |
| Intel + Nvidia | 76        | 15.35%  |
| 1 x AMD        | 53        | 10.71%  |
| 1 x Nvidia     | 48        | 9.7%    |
| Intel + AMD    | 14        | 2.83%   |
| 2 x Intel      | 4         | 0.81%   |
| AMD + Nvidia   | 4         | 0.81%   |
| Other          | 3         | 0.61%   |
| 2 x AMD        | 3         | 0.61%   |
| 2 x Nvidia     | 1         | 0.2%    |
| 1 x SiS        | 1         | 0.2%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 410       | 82%     |
| Proprietary | 56        | 11.2%   |
| Unknown     | 34        | 6.8%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 380       | 74.8%   |
| 1.01-2.0   | 45        | 8.86%   |
| 0.01-0.5   | 37        | 7.28%   |
| 3.01-4.0   | 19        | 3.74%   |
| 0.51-1.0   | 18        | 3.54%   |
| 7.01-8.0   | 6         | 1.18%   |
| 5.01-6.0   | 1         | 0.2%    |
| 2.01-3.0   | 1         | 0.2%    |
| 8.01-16.0  | 1         | 0.2%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 70        | 14.43%  |
| Samsung Electronics     | 63        | 12.99%  |
| LG Display              | 63        | 12.99%  |
| Chimei Innolux          | 62        | 12.78%  |
| BOE                     | 59        | 12.16%  |
| Hewlett-Packard         | 28        | 5.77%   |
| Dell                    | 24        | 4.95%   |
| InfoVision              | 14        | 2.89%   |
| Lenovo                  | 12        | 2.47%   |
| Apple                   | 10        | 2.06%   |
| Sharp                   | 8         | 1.65%   |
| Goldstar                | 8         | 1.65%   |
| Chi Mei Optoelectronics | 6         | 1.24%   |
| LG Philips              | 5         | 1.03%   |
| Iiyama                  | 5         | 1.03%   |
| Acer                    | 5         | 1.03%   |
| MSI                     | 4         | 0.82%   |
| HannStar                | 3         | 0.62%   |
| Fujitsu Siemens         | 3         | 0.62%   |
| BenQ                    | 3         | 0.62%   |
| Sony                    | 2         | 0.41%   |
| Philips                 | 2         | 0.41%   |
| PANDA                   | 2         | 0.41%   |
| ASUSTek Computer        | 2         | 0.41%   |
| AOC                     | 2         | 0.41%   |
| Ancor Communications    | 2         | 0.41%   |
| Valve                   | 1         | 0.21%   |
| ULP                     | 1         | 0.21%   |
| TMX                     | 1         | 0.21%   |
| TCL                     | 1         | 0.21%   |
| SAC                     | 1         | 0.21%   |
| RTK                     | 1         | 0.21%   |
| Panasonic               | 1         | 0.21%   |
| NEC Computers           | 1         | 0.21%   |
| NCS                     | 1         | 0.21%   |
| MiTAC                   | 1         | 0.21%   |
| Mi                      | 1         | 0.21%   |
| Medion                  | 1         | 0.21%   |
| LGD                     | 1         | 0.21%   |
| IBM                     | 1         | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 5         | 1.02%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch | 4         | 0.82%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch         | 4         | 0.82%   |
| Samsung Electronics LCD Monitor SEC3642 1366x768 344x194mm 15.5-inch | 3         | 0.61%   |
| Dell E2414H DEL4090 1920x1080 531x299mm 24.0-inch                    | 3         | 0.61%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch      | 3         | 0.61%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x193mm 15.5-inch      | 3         | 0.61%   |
| Chimei Innolux LCD Monitor CMN14E7 1920x1080 309x173mm 13.9-inch     | 3         | 0.61%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 3         | 0.61%   |
| Chimei Innolux LCD Monitor CMN14A3 1600x900 309x174mm 14.0-inch      | 3         | 0.61%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                | 3         | 0.61%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                 | 3         | 0.61%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                 | 3         | 0.61%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 3         | 0.61%   |
| Samsung Electronics SyncMaster SAM027E 1680x1050 474x296mm 22.0-inch | 2         | 0.41%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch | 2         | 0.41%   |
| Samsung Electronics LCD Monitor SDC4D42 1366x768 309x174mm 14.0-inch | 2         | 0.41%   |
| MSI G24C6 MSI3BA0 1920x1080 521x293mm 23.5-inch                      | 2         | 0.41%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch         | 2         | 0.41%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch         | 2         | 0.41%   |
| LG Display LCD Monitor LGD0504 1366x768 340x190mm 15.3-inch          | 2         | 0.41%   |
| LG Display LCD Monitor LGD03D9 1366x768 345x194mm 15.6-inch          | 2         | 0.41%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch          | 2         | 0.41%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch          | 2         | 0.41%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1080 518x324mm 24.1-inch           | 2         | 0.41%   |
| InfoVision LCD Monitor IVO8C78 1920x1080 309x174mm 14.0-inch         | 2         | 0.41%   |
| InfoVision LCD Monitor IVO057F 1920x1080 309x174mm 14.0-inch         | 2         | 0.41%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch         | 2         | 0.41%   |
| InfoVision LCD Monitor IVO0535 1920x1080 290x170mm 13.2-inch         | 2         | 0.41%   |
| Hewlett-Packard L1750 HWP26E9 1280x1024 340x270mm 17.1-inch          | 2         | 0.41%   |
| Hewlett-Packard 25x HPN357E 1920x1080 544x303mm 24.5-inch            | 2         | 0.41%   |
| Dell S2719H DELD0CE 1920x1080 600x340mm 27.2-inch                    | 2         | 0.41%   |
| Dell E2014H DELD03B 1600x900 432x240mm 19.5-inch                     | 2         | 0.41%   |
| Dell E198FP DELA028 1280x1024 380x305mm 19.2-inch                    | 2         | 0.41%   |
| Dell 2208WFP DEL403B 1680x1050 473x296mm 22.0-inch                   | 2         | 0.41%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 2         | 0.41%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 2         | 0.41%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch     | 2         | 0.41%   |
| Chimei Innolux LCD Monitor CMN15B7 1366x768 344x193mm 15.5-inch      | 2         | 0.41%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 2         | 0.41%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 176       | 36.97%  |
| 1366x768 (WXGA)    | 149       | 31.3%   |
| 1600x900 (HD+)     | 30        | 6.3%    |
| 1680x1050 (WSXGA+) | 17        | 3.57%   |
| 3840x2160 (4K)     | 15        | 3.15%   |
| 1440x900 (WXGA+)   | 15        | 3.15%   |
| 1280x1024 (SXGA)   | 14        | 2.94%   |
| 1280x800 (WXGA)    | 11        | 2.31%   |
| 1920x1200 (WUXGA)  | 9         | 1.89%   |
| 2560x1440 (QHD)    | 8         | 1.68%   |
| 2560x1600          | 4         | 0.84%   |
| 1024x600           | 4         | 0.84%   |
| 1360x768           | 3         | 0.63%   |
| 3840x2400          | 2         | 0.42%   |
| 2880x1920          | 2         | 0.42%   |
| 2880x1800          | 2         | 0.42%   |
| 2240x1400          | 2         | 0.42%   |
| 1024x768 (XGA)     | 2         | 0.42%   |
| 800x1280           | 1         | 0.21%   |
| 3440x1440          | 1         | 0.21%   |
| 2880x1620          | 1         | 0.21%   |
| 2520x1680          | 1         | 0.21%   |
| 2160x1440          | 1         | 0.21%   |
| 1920x515           | 1         | 0.21%   |
| 1680x945           | 1         | 0.21%   |
| 1400x1050          | 1         | 0.21%   |
| 1280x720 (HD)      | 1         | 0.21%   |
| 1152x864           | 1         | 0.21%   |
| Unknown            | 1         | 0.21%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 179       | 36.68%  |
| 13      | 60        | 12.3%   |
| 14      | 55        | 11.27%  |
| 17      | 26        | 5.33%   |
| 24      | 22        | 4.51%   |
| 23      | 18        | 3.69%   |
| 12      | 18        | 3.69%   |
| 19      | 17        | 3.48%   |
| 27      | 16        | 3.28%   |
| 22      | 15        | 3.07%   |
| 21      | 10        | 2.05%   |
| 18      | 9         | 1.84%   |
| Unknown | 7         | 1.43%   |
| 20      | 6         | 1.23%   |
| 16      | 5         | 1.02%   |
| 31      | 4         | 0.82%   |
| 11      | 4         | 0.82%   |
| 10      | 3         | 0.61%   |
| 84      | 2         | 0.41%   |
| 72      | 2         | 0.41%   |
| 54      | 2         | 0.41%   |
| 34      | 2         | 0.41%   |
| 74      | 1         | 0.2%    |
| 58      | 1         | 0.2%    |
| 52      | 1         | 0.2%    |
| 43      | 1         | 0.2%    |
| 32      | 1         | 0.2%    |
| 7       | 1         | 0.2%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 273       | 56.76%  |
| 201-300     | 53        | 11.02%  |
| 501-600     | 51        | 10.6%   |
| 401-500     | 48        | 9.98%   |
| 351-400     | 29        | 6.03%   |
| Unknown     | 7         | 1.46%   |
| 601-700     | 6         | 1.25%   |
| 1501-2000   | 5         | 1.04%   |
| 1001-1500   | 4         | 0.83%   |
| 701-800     | 3         | 0.62%   |
| 901-1000    | 1         | 0.21%   |
| 1-100       | 1         | 0.21%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 371       | 78.94%  |
| 16/10   | 67        | 14.26%  |
| 5/4     | 14        | 2.98%   |
| Unknown | 6         | 1.28%   |
| 4/3     | 5         | 1.06%   |
| 3/2     | 4         | 0.85%   |
| 3.73    | 1         | 0.21%   |
| 21/9    | 1         | 0.21%   |
| 0.67    | 1         | 0.21%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 179       | 36.98%  |
| 81-90          | 92        | 19.01%  |
| 201-250        | 53        | 10.95%  |
| 151-200        | 27        | 5.58%   |
| 71-80          | 20        | 4.13%   |
| 61-70          | 17        | 3.51%   |
| 301-350        | 16        | 3.31%   |
| 121-130        | 15        | 3.1%    |
| 141-150        | 13        | 2.69%   |
| More than 1000 | 9         | 1.86%   |
| 251-300        | 8         | 1.65%   |
| Unknown        | 7         | 1.45%   |
| 351-500        | 6         | 1.24%   |
| 111-120        | 6         | 1.24%   |
| 51-60          | 4         | 0.83%   |
| 41-50          | 3         | 0.62%   |
| 131-140        | 3         | 0.62%   |
| 91-100         | 3         | 0.62%   |
| 501-1000       | 2         | 0.41%   |
| 1-40           | 1         | 0.21%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 158       | 32.99%  |
| 121-160       | 138       | 28.81%  |
| 51-100        | 122       | 25.47%  |
| 161-240       | 40        | 8.35%   |
| 1-50          | 8         | 1.67%   |
| Unknown       | 7         | 1.46%   |
| More than 240 | 6         | 1.25%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 445       | 89.18%  |
| 2     | 33        | 6.61%   |
| 0     | 20        | 4.01%   |
| 3     | 1         | 0.2%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 288       | 37.84%  |
| Realtek Semiconductor            | 196       | 25.76%  |
| Qualcomm Atheros                 | 76        | 9.99%   |
| Broadcom                         | 60        | 7.88%   |
| Ralink Technology                | 37        | 4.86%   |
| Ralink                           | 16        | 2.1%    |
| TP-Link                          | 14        | 1.84%   |
| Broadcom Limited                 | 10        | 1.31%   |
| Sierra Wireless                  | 8         | 1.05%   |
| Samsung Electronics              | 8         | 1.05%   |
| MediaTek                         | 8         | 1.05%   |
| Marvell Technology Group         | 8         | 1.05%   |
| Dell                             | 5         | 0.66%   |
| Xiaomi                           | 3         | 0.39%   |
| Qualcomm                         | 3         | 0.39%   |
| Nvidia                           | 3         | 0.39%   |
| Lenovo                           | 2         | 0.26%   |
| JMicron Technology               | 2         | 0.26%   |
| Huawei Technologies              | 2         | 0.26%   |
| D-Link System                    | 2         | 0.26%   |
| D-Link                           | 2         | 0.26%   |
| Silicon Integrated Systems [SiS] | 1         | 0.13%   |
| Qualcomm Atheros Communications  | 1         | 0.13%   |
| NetGear                          | 1         | 0.13%   |
| Microchip Technology             | 1         | 0.13%   |
| Gemtek                           | 1         | 0.13%   |
| Fibocom                          | 1         | 0.13%   |
| Arduino SA                       | 1         | 0.13%   |
| Aquantia                         | 1         | 0.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 126       | 13.39%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 35        | 3.72%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 31        | 3.29%   |
| Intel Wireless 8265 / 8275                                             | 29        | 3.08%   |
| Intel Ethernet Connection I217-LM                                      | 28        | 2.98%   |
| Intel Wireless 8260                                                    | 23        | 2.44%   |
| Ralink MT7601U Wireless Adapter                                        | 18        | 1.91%   |
| Intel Ethernet Connection (4) I219-LM                                  | 17        | 1.81%   |
| Intel Ethernet Connection (2) I219-LM                                  | 16        | 1.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 15        | 1.59%   |
| Ralink RT5370 Wireless Adapter                                         | 14        | 1.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 14        | 1.49%   |
| Intel Wireless 7265                                                    | 14        | 1.49%   |
| Intel 82577LM Gigabit Network Connection                               | 14        | 1.49%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 13        | 1.38%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 13        | 1.38%   |
| Intel Wi-Fi 6 AX201                                                    | 12        | 1.28%   |
| Intel Wi-Fi 6 AX200                                                    | 12        | 1.28%   |
| Intel Ethernet Connection I219-LM                                      | 12        | 1.28%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 11        | 1.17%   |
| Intel Centrino Advanced-N 6200                                         | 11        | 1.17%   |
| Broadcom BCM43142 802.11b/g/n                                          | 11        | 1.17%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 10        | 1.06%   |
| Intel Ethernet Connection (3) I218-LM                                  | 10        | 1.06%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 10        | 1.06%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 9         | 0.96%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 9         | 0.96%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 8         | 0.85%   |
| Intel Wireless 7260                                                    | 8         | 0.85%   |
| Intel Ethernet Connection I218-LM                                      | 8         | 0.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 7         | 0.74%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 7         | 0.74%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 7         | 0.74%   |
| Broadcom BCM43228 802.11a/b/g/n                                        | 7         | 0.74%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 6         | 0.64%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 6         | 0.64%   |
| Intel Centrino Advanced-N 6235                                         | 6         | 0.64%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 6         | 0.64%   |
| Sierra Wireless EM7455                                                 | 5         | 0.53%   |
| Realtek RTL8125 2.5GbE Controller                                      | 5         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 202       | 42.62%  |
| Qualcomm Atheros                | 68        | 14.35%  |
| Realtek Semiconductor           | 57        | 12.03%  |
| Broadcom                        | 43        | 9.07%   |
| Ralink Technology               | 37        | 7.81%   |
| Ralink                          | 16        | 3.38%   |
| TP-Link                         | 14        | 2.95%   |
| Sierra Wireless                 | 8         | 1.69%   |
| MediaTek                        | 7         | 1.48%   |
| Broadcom Limited                | 7         | 1.48%   |
| Dell                            | 4         | 0.84%   |
| Qualcomm                        | 2         | 0.42%   |
| Marvell Technology Group        | 2         | 0.42%   |
| D-Link                          | 2         | 0.42%   |
| Qualcomm Atheros Communications | 1         | 0.21%   |
| NetGear                         | 1         | 0.21%   |
| Gemtek                          | 1         | 0.21%   |
| Fibocom                         | 1         | 0.21%   |
| D-Link System                   | 1         | 0.21%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                           | 29        | 6.05%   |
| Intel Wireless 8260                                                  | 23        | 4.8%    |
| Ralink MT7601U Wireless Adapter                                      | 18        | 3.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 15        | 3.13%   |
| Ralink RT5370 Wireless Adapter                                       | 14        | 2.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 14        | 2.92%   |
| Intel Wireless 7265                                                  | 14        | 2.92%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 13        | 2.71%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 13        | 2.71%   |
| Intel Wi-Fi 6 AX201                                                  | 12        | 2.51%   |
| Intel Wi-Fi 6 AX200                                                  | 12        | 2.51%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 11        | 2.3%    |
| Intel Centrino Advanced-N 6200                                       | 11        | 2.3%    |
| Broadcom BCM43142 802.11b/g/n                                        | 11        | 2.3%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 10        | 2.09%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 10        | 2.09%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 9         | 1.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 9         | 1.88%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 8         | 1.67%   |
| Intel Wireless 7260                                                  | 8         | 1.67%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 7         | 1.46%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 7         | 1.46%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 7         | 1.46%   |
| Broadcom BCM43228 802.11a/b/g/n                                      | 7         | 1.46%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 6         | 1.25%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                            | 6         | 1.25%   |
| Intel Centrino Advanced-N 6235                                       | 6         | 1.25%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 6         | 1.25%   |
| Sierra Wireless EM7455                                               | 5         | 1.04%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 5         | 1.04%   |
| Intel Centrino Ultimate-N 6300                                       | 5         | 1.04%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                           | 4         | 0.84%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                            | 4         | 0.84%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330] | 4         | 0.84%   |
| Intel WiFi Link 5100                                                 | 4         | 0.84%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 4         | 0.84%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 4         | 0.84%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 4         | 0.84%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                          | 4         | 0.84%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 3         | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 201       | 44.77%  |
| Realtek Semiconductor            | 171       | 38.08%  |
| Broadcom                         | 25        | 5.57%   |
| Qualcomm Atheros                 | 16        | 3.56%   |
| Samsung Electronics              | 8         | 1.78%   |
| Marvell Technology Group         | 6         | 1.34%   |
| Broadcom Limited                 | 4         | 0.89%   |
| Xiaomi                           | 3         | 0.67%   |
| Nvidia                           | 3         | 0.67%   |
| Lenovo                           | 2         | 0.45%   |
| JMicron Technology               | 2         | 0.45%   |
| Huawei Technologies              | 2         | 0.45%   |
| Silicon Integrated Systems [SiS] | 1         | 0.22%   |
| Qualcomm                         | 1         | 0.22%   |
| Microchip Technology             | 1         | 0.22%   |
| MediaTek                         | 1         | 0.22%   |
| D-Link System                    | 1         | 0.22%   |
| Aquantia                         | 1         | 0.22%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 126       | 27.45%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 35        | 7.63%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 31        | 6.75%   |
| Intel Ethernet Connection I217-LM                                      | 28        | 6.1%    |
| Intel Ethernet Connection (4) I219-LM                                  | 17        | 3.7%    |
| Intel Ethernet Connection (2) I219-LM                                  | 16        | 3.49%   |
| Intel 82577LM Gigabit Network Connection                               | 14        | 3.05%   |
| Intel Ethernet Connection I219-LM                                      | 12        | 2.61%   |
| Intel Ethernet Connection (3) I218-LM                                  | 10        | 2.18%   |
| Intel Ethernet Connection I218-LM                                      | 8         | 1.74%   |
| Realtek RTL8125 2.5GbE Controller                                      | 5         | 1.09%   |
| Intel Ethernet Connection I217-V                                       | 5         | 1.09%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 5         | 1.09%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 4         | 0.87%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 4         | 0.87%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 4         | 0.87%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 4         | 0.87%   |
| Intel I211 Gigabit Network Connection                                  | 4         | 0.87%   |
| Intel Ethernet Connection (4) I219-V                                   | 4         | 0.87%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 4         | 0.87%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 4         | 0.87%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 3         | 0.65%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 3         | 0.65%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 3         | 0.65%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 3         | 0.65%   |
| Intel I210 Gigabit Network Connection                                  | 3         | 0.65%   |
| Intel Ethernet Connection (6) I219-LM                                  | 3         | 0.65%   |
| Intel Ethernet Connection (13) I219-LM                                 | 3         | 0.65%   |
| Intel Ethernet Connection (10) I219-LM                                 | 3         | 0.65%   |
| Intel 82579V Gigabit Network Connection                                | 3         | 0.65%   |
| Intel 82578DM Gigabit Network Connection                               | 3         | 0.65%   |
| Intel 82574L Gigabit Network Connection                                | 3         | 0.65%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                | 3         | 0.65%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 3         | 0.65%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 2         | 0.44%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 2         | 0.44%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2         | 0.44%   |
| Nvidia MCP61 Ethernet                                                  | 2         | 0.44%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                | 2         | 0.44%   |
| Lenovo ThinkPad TBT 3 Dock                                             | 2         | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 437       | 50.29%  |
| Ethernet | 429       | 49.37%  |
| Modem    | 3         | 0.35%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 368       | 73.9%   |
| Ethernet | 130       | 26.1%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 324       | 65.72%  |
| 1     | 150       | 30.43%  |
| 0     | 11        | 2.23%   |
| 3     | 7         | 1.42%   |
| 7     | 1         | 0.2%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 491       | 99.8%   |
| Yes  | 1         | 0.2%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 152       | 47.95%  |
| Realtek Semiconductor           | 33        | 10.41%  |
| Qualcomm Atheros Communications | 27        | 8.52%   |
| Broadcom                        | 19        | 5.99%   |
| Cambridge Silicon Radio         | 11        | 3.47%   |
| Lite-On Technology              | 10        | 3.15%   |
| Apple                           | 10        | 3.15%   |
| IMC Networks                    | 9         | 2.84%   |
| Foxconn / Hon Hai               | 9         | 2.84%   |
| Dell                            | 8         | 2.52%   |
| Hewlett-Packard                 | 7         | 2.21%   |
| Ralink                          | 6         | 1.89%   |
| Toshiba                         | 4         | 1.26%   |
| TP-Link                         | 2         | 0.63%   |
| Marvell Semiconductor           | 2         | 0.63%   |
| ASUSTek Computer                | 2         | 0.63%   |
| USI                             | 1         | 0.32%   |
| Ralink Technology               | 1         | 0.32%   |
| Foxconn International           | 1         | 0.32%   |
| Askey Computer                  | 1         | 0.32%   |
| Alps Electric                   | 1         | 0.32%   |
| Actions                         | 1         | 0.32%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 71        | 22.4%   |
| Intel AX201 Bluetooth                               | 29        | 9.15%   |
| Realtek Bluetooth Radio                             | 21        | 6.62%   |
| Qualcomm Atheros  Bluetooth Device                  | 14        | 4.42%   |
| Intel Bluetooth Device                              | 13        | 4.1%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 12        | 3.79%   |
| Intel AX200 Bluetooth                               | 12        | 3.79%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 11        | 3.47%   |
| Realtek  Bluetooth 4.2 Adapter                      | 7         | 2.21%   |
| IMC Networks Bluetooth Device                       | 7         | 2.21%   |
| Ralink RT3290 Bluetooth                             | 6         | 1.89%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 6         | 1.89%   |
| HP Broadcom 2070 Bluetooth Combo                    | 6         | 1.89%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 5         | 1.58%   |
| Dell DW375 Bluetooth Module                         | 5         | 1.58%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 5         | 1.58%   |
| Apple Bluetooth USB Host Controller                 | 5         | 1.58%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 4         | 1.26%   |
| Intel Wireless-AC 3168 Bluetooth                    | 4         | 1.26%   |
| Broadcom HP Portable Bumble Bee                     | 4         | 1.26%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 3         | 0.95%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 0.95%   |
| Intel AX210 Bluetooth                               | 3         | 0.95%   |
| Apple Bluetooth Host Controller                     | 3         | 0.95%   |
| TP-Link TP-T@- UB500 Adapter                        | 2         | 0.63%   |
| Toshiba Bluetooth Device                            | 2         | 0.63%   |
| Realtek RTL8821A Bluetooth                          | 2         | 0.63%   |
| Realtek RTL8723B Bluetooth                          | 2         | 0.63%   |
| Marvell Bluetooth and Wireless LAN Composite        | 2         | 0.63%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 2         | 0.63%   |
| Lite-On Bluetooth Device                            | 2         | 0.63%   |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 0.63%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 2         | 0.63%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 0.63%   |
| Dell Wireless 360 Bluetooth                         | 2         | 0.63%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2         | 0.63%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 0.63%   |
| USI Bluetooth Device                                | 1         | 0.32%   |
| Toshiba Atheros AR3012 Bluetooth                    | 1         | 0.32%   |
| Toshiba Askey Bluetooth Module                      | 1         | 0.32%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 434       | 71.03%  |
| Nvidia                                       | 89        | 14.57%  |
| AMD                                          | 61        | 9.98%   |
| GN Netcom                                    | 3         | 0.49%   |
| Silicon Integrated Systems [SiS]             | 2         | 0.33%   |
| Logitech                                     | 2         | 0.33%   |
| Lenovo                                       | 2         | 0.33%   |
| EDFIER                                       | 2         | 0.33%   |
| C-Media Electronics                          | 2         | 0.33%   |
| ASUSTek Computer                             | 2         | 0.33%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.16%   |
| Walmart                                      | 1         | 0.16%   |
| Trust                                        | 1         | 0.16%   |
| Nordic Semiconductor ASA                     | 1         | 0.16%   |
| Medeli Electronics                           | 1         | 0.16%   |
| Kingston Technology                          | 1         | 0.16%   |
| JMTek                                        | 1         | 0.16%   |
| Hewlett-Packard                              | 1         | 0.16%   |
| Generalplus Technology                       | 1         | 0.16%   |
| GEMBIRD                                      | 1         | 0.16%   |
| Focusrite-Novation                           | 1         | 0.16%   |
| Creative Labs                                | 1         | 0.16%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 63        | 8.58%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 38        | 5.18%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 37        | 5.04%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 31        | 4.22%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 31        | 4.22%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 29        | 3.95%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 28        | 3.81%   |
| Intel 8 Series HD Audio Controller                                                                | 28        | 3.81%   |
| AMD Ryzen HD Audio Controller                                                                     | 25        | 3.41%   |
| Intel Broadwell-U Audio Controller                                                                | 24        | 3.27%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 23        | 3.13%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 21        | 2.86%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 21        | 2.86%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 20        | 2.72%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 14        | 1.91%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 14        | 1.91%   |
| Intel Cannon Lake PCH cAVS                                                                        | 13        | 1.77%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                       | 11        | 1.5%    |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 9         | 1.23%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 8         | 1.09%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 7         | 0.95%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 7         | 0.95%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 0.95%   |
| Nvidia High Definition Audio Controller                                                           | 6         | 0.82%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 6         | 0.82%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 6         | 0.82%   |
| Intel 200 Series PCH HD Audio                                                                     | 6         | 0.82%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 0.82%   |
| AMD Radeon High Definition Audio Controller                                                       | 6         | 0.82%   |
| AMD FCH Azalia Controller                                                                         | 6         | 0.82%   |
| Nvidia GA107 High Definition Audio Controller                                                     | 5         | 0.68%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 5         | 0.68%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 0.68%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 5         | 0.68%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 5         | 0.68%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 5         | 0.68%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 5         | 0.68%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 0.68%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 4         | 0.54%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 4         | 0.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 110       | 30.9%   |
| SK hynix                                | 89        | 25%     |
| Micron Technology                       | 51        | 14.33%  |
| Kingston                                | 30        | 8.43%   |
| Unknown                                 | 12        | 3.37%   |
| Ramaxel Technology                      | 10        | 2.81%   |
| Nanya Technology                        | 7         | 1.97%   |
| Crucial                                 | 7         | 1.97%   |
| A-DATA Technology                       | 7         | 1.97%   |
| Elpida                                  | 6         | 1.69%   |
| Corsair                                 | 5         | 1.4%    |
| Sesame                                  | 3         | 0.84%   |
| Transcend                               | 2         | 0.56%   |
| Qimonda                                 | 2         | 0.56%   |
| ASint Technology                        | 2         | 0.56%   |
| Unknown                                 | 2         | 0.56%   |
| Wilk                                    | 1         | 0.28%   |
| Unknown (83DA)                          | 1         | 0.28%   |
| Unknown (0B85)                          | 1         | 0.28%   |
| Toshiba                                 | 1         | 0.28%   |
| Team                                    | 1         | 0.28%   |
| TakeMS                                  | 1         | 0.28%   |
| Silicon Power Computer & Communications | 1         | 0.28%   |
| Silicon Power                           | 1         | 0.28%   |
| G.Skill                                 | 1         | 0.28%   |
| Avant                                   | 1         | 0.28%   |
| Apacer                                  | 1         | 0.28%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s    | 5         | 1.29%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s      | 5         | 1.29%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s     | 4         | 1.03%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s   | 4         | 1.03%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1600MT/s    | 4         | 1.03%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s      | 4         | 1.03%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s    | 4         | 1.03%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s             | 3         | 0.77%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s     | 3         | 0.77%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s   | 3         | 0.77%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s   | 3         | 0.77%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s   | 3         | 0.77%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s              | 3         | 0.77%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s              | 3         | 0.77%   |
| Samsung RAM Module 4GB DIMM DDR3 1333MT/s                | 3         | 0.77%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s    | 3         | 0.77%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s    | 3         | 0.77%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s    | 3         | 0.77%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s    | 3         | 0.77%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s    | 3         | 0.77%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s    | 3         | 0.77%   |
| Kingston RAM HP16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s    | 3         | 0.77%   |
| Unknown RAM Module 2GB SODIMM DDR2                       | 2         | 0.52%   |
| Transcend RAM JM1333KSN-4G 4GB SODIMM DDR3 1334MT/s      | 2         | 0.52%   |
| SK hynix RAM HMT451U6AFR8A-PB 4GB DIMM DDR3 1600MT/s     | 2         | 0.52%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 2         | 0.52%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 2667MT/s   | 2         | 0.52%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s  | 2         | 0.52%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s   | 2         | 0.52%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s   | 2         | 0.52%   |
| Sesame RAM S939A2SGS-ITR 8GB SODIMM DDR4 2667MT/s        | 2         | 0.52%   |
| Samsung RAM M471B5773EB0-CK0 2048MB SODIMM DDR3 1600MT/s | 2         | 0.52%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s    | 2         | 0.52%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s    | 2         | 0.52%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s | 2         | 0.52%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s    | 2         | 0.52%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s   | 2         | 0.52%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s   | 2         | 0.52%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 3200MT/s    | 2         | 0.52%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 8400MT/s    | 2         | 0.52%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 117       | 41.79%  |
| DDR3    | 109       | 38.93%  |
| DDR2    | 13        | 4.64%   |
| SDRAM   | 12        | 4.29%   |
| LPDDR4  | 7         | 2.5%    |
| LPDDR5  | 6         | 2.14%   |
| LPDDR3  | 6         | 2.14%   |
| DDR5    | 6         | 2.14%   |
| Unknown | 3         | 1.07%   |
| DDR     | 1         | 0.36%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 187       | 69%     |
| DIMM         | 61        | 22.51%  |
| Row Of Chips | 19        | 7.01%   |
| Unknown      | 2         | 0.74%   |
| RIMM         | 1         | 0.37%   |
| Chip         | 1         | 0.37%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 108       | 34.5%   |
| 4096  | 107       | 34.19%  |
| 2048  | 38        | 12.14%  |
| 16384 | 36        | 11.5%   |
| 1024  | 12        | 3.83%   |
| 32768 | 7         | 2.24%   |
| 512   | 2         | 0.64%   |
| 12288 | 1         | 0.32%   |
| 256   | 1         | 0.32%   |
| 128   | 1         | 0.32%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 72        | 23.08%  |
| 2667    | 47        | 15.06%  |
| 3200    | 41        | 13.14%  |
| 2400    | 20        | 6.41%   |
| 2133    | 19        | 6.09%   |
| 1333    | 17        | 5.45%   |
| 1334    | 12        | 3.85%   |
| 1067    | 7         | 2.24%   |
| 667     | 7         | 2.24%   |
| 1867    | 6         | 1.92%   |
| Unknown | 6         | 1.92%   |
| 4800    | 4         | 1.28%   |
| 3600    | 4         | 1.28%   |
| 3266    | 4         | 1.28%   |
| 1648    | 4         | 1.28%   |
| 800     | 4         | 1.28%   |
| 8400    | 3         | 0.96%   |
| 6400    | 3         | 0.96%   |
| 4000    | 3         | 0.96%   |
| 1066    | 3         | 0.96%   |
| 5600    | 2         | 0.64%   |
| 4199    | 2         | 0.64%   |
| 2048    | 2         | 0.64%   |
| 1800    | 2         | 0.64%   |
| 1639    | 2         | 0.64%   |
| 975     | 2         | 0.64%   |
| 49926   | 1         | 0.32%   |
| 8533    | 1         | 0.32%   |
| 7500    | 1         | 0.32%   |
| 7467    | 1         | 0.32%   |
| 4267    | 1         | 0.32%   |
| 3733    | 1         | 0.32%   |
| 3467    | 1         | 0.32%   |
| 2666    | 1         | 0.32%   |
| 2000    | 1         | 0.32%   |
| 1866    | 1         | 0.32%   |
| 1331    | 1         | 0.32%   |
| 400     | 1         | 0.32%   |
| 333     | 1         | 0.32%   |
| 266     | 1         | 0.32%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 4         | 50%     |
| Canon               | 2         | 25%     |
| Samsung Electronics | 1         | 12.5%   |
| Konica Minolta      | 1         | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                     | Computers | Percent |
|---------------------------|-----------|---------|
| Samsung M2070 Series      | 1         | 12.5%   |
| Konica Minolta C364Series | 1         | 12.5%   |
| HP LaserJet P1005         | 1         | 12.5%   |
| HP LaserJet M402dn        | 1         | 12.5%   |
| HP LaserJet 1018          | 1         | 12.5%   |
| HP Deskjet 3510 series    | 1         | 12.5%   |
| Canon MB2000 series       | 1         | 12.5%   |
| Canon LBP6030/6030B/6018L | 1         | 12.5%   |

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
| Chicony Electronics                    | 92        | 28.13%  |
| IMC Networks                           | 31        | 9.48%   |
| Realtek Semiconductor                  | 25        | 7.65%   |
| Cheng Uei Precision Industry (Foxlink) | 23        | 7.03%   |
| Sunplus Innovation Technology          | 19        | 5.81%   |
| Lite-On Technology                     | 19        | 5.81%   |
| Quanta                                 | 17        | 5.2%    |
| Microdia                               | 16        | 4.89%   |
| Suyin                                  | 14        | 4.28%   |
| Bison Electronics                      | 11        | 3.36%   |
| Apple                                  | 9         | 2.75%   |
| Syntek                                 | 7         | 2.14%   |
| Luxvisions Innotech Limited            | 7         | 2.14%   |
| Alcor Micro                            | 5         | 1.53%   |
| Ricoh                                  | 4         | 1.22%   |
| Z-Star Microelectronics                | 3         | 0.92%   |
| Samsung Electronics                    | 3         | 0.92%   |
| Logitech                               | 3         | 0.92%   |
| Sonix Technology                       | 2         | 0.61%   |
| Silicon Motion                         | 2         | 0.61%   |
| ShineTech                              | 2         | 0.61%   |
| ALi                                    | 2         | 0.61%   |
| Sunplus Technology                     | 1         | 0.31%   |
| Primax Electronics                     | 1         | 0.31%   |
| OPPO Electronics                       | 1         | 0.31%   |
| OmniVision Technologies                | 1         | 0.31%   |
| Nebraska Furniture Mart                | 1         | 0.31%   |
| LG Innotek                             | 1         | 0.31%   |
| Lenovo                                 | 1         | 0.31%   |
| Jieli Technology                       | 1         | 0.31%   |
| icSpring                               | 1         | 0.31%   |
| GEMBIRD                                | 1         | 0.31%   |
| Acer                                   | 1         | 0.31%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 17        | 5.15%   |
| IMC Networks Integrated Camera                          | 11        | 3.33%   |
| Realtek Integrated_Webcam_HD                            | 8         | 2.42%   |
| Lite-On HP HD Camera                                    | 8         | 2.42%   |
| Chicony HP HD Camera                                    | 8         | 2.42%   |
| Sunplus Integrated_Webcam_HD                            | 7         | 2.12%   |
| Chicony HP Webcam                                       | 7         | 2.12%   |
| Chicony HP Webcam [2 MP Macro]                          | 6         | 1.82%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera     | 6         | 1.82%   |
| Microdia Integrated_Webcam_HD                           | 5         | 1.52%   |
| Microdia Integrated Webcam                              | 5         | 1.52%   |
| Lite-On HP HD Webcam                                    | 5         | 1.52%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 5         | 1.52%   |
| Chicony HD WebCam                                       | 5         | 1.52%   |
| Bison Integrated Camera                                 | 5         | 1.52%   |
| Sunplus Laptop_Integrated_Webcam_FHD                    | 4         | 1.21%   |
| Realtek USB Camera                                      | 4         | 1.21%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam     | 4         | 1.21%   |
| Alcor Micro USB 2.0 Camera                              | 4         | 1.21%   |
| Syntek Lenovo EasyCamera                                | 3         | 0.91%   |
| Samsung Galaxy series, misc. (MTP mode)                 | 3         | 0.91%   |
| Quanta HP Wide Vision HD Camera                         | 3         | 0.91%   |
| Quanta HP HD Camera                                     | 3         | 0.91%   |
| Quanta HD WebCam                                        | 3         | 0.91%   |
| Luxvisions Innotech Limited Integrated Camera           | 3         | 0.91%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 3         | 0.91%   |
| IMC Networks Lenovo EasyCamera                          | 3         | 0.91%   |
| IMC Networks HP TrueVision HD Camera                    | 3         | 0.91%   |
| Chicony USB2.0 HD UVC WebCam                            | 3         | 0.91%   |
| Chicony TOSHIBA Web Camera - HD                         | 3         | 0.91%   |
| Chicony Integrated Camera (1280x720@30)                 | 3         | 0.91%   |
| Chicony HP Wide Vision HD Camera                        | 3         | 0.91%   |
| Chicony HP HD Webcam [Fixed]                            | 3         | 0.91%   |
| Chicony HP HD Webcam                                    | 3         | 0.91%   |
| Chicony EasyCamera                                      | 3         | 0.91%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 3         | 0.91%   |
| Apple FaceTime HD Camera (Built-in)                     | 3         | 0.91%   |
| Syntek Integrated Camera                                | 2         | 0.61%   |
| Syntek EasyCamera                                       | 2         | 0.61%   |
| Suyin Sony Visual Communication Camera                  | 2         | 0.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 44        | 60.27%  |
| Synaptics                  | 18        | 24.66%  |
| Shenzhen Goodix Technology | 4         | 5.48%   |
| Elan Microelectronics      | 4         | 5.48%   |
| Upek                       | 2         | 2.74%   |
| Focal-systems.Corp         | 1         | 1.37%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 14        | 19.18%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 10.96%  |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 8.22%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 6         | 8.22%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 6         | 8.22%   |
| Validity Sensors Synaptics WBDI                                            | 4         | 5.48%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 4.11%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 4.11%   |
| Validity Sensors VFS491                                                    | 2         | 2.74%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 2.74%   |
| Synaptics UWP WBDI Device                                                  | 2         | 2.74%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 2.74%   |
| Shenzhen Goodix  Fingerprint Device                                        | 2         | 2.74%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 2.74%   |
| Elan ELAN:Fingerprint                                                      | 2         | 2.74%   |
| Elan ELAN:ARM-M4                                                           | 2         | 2.74%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 1.37%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 1.37%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 1.37%   |
| Synaptics  WBDI                                                            | 1         | 1.37%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.37%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 1.37%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 1.37%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 30        | 62.5%   |
| Alcor Micro | 13        | 27.08%  |
| O2 Micro    | 4         | 8.33%   |
| Lenovo      | 1         | 2.08%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 13        | 27.08%  |
| Broadcom BCM5880 Secure Applications Processor                               | 11        | 22.92%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 7         | 14.58%  |
| Broadcom 5880                                                                | 7         | 14.58%  |
| Broadcom 58200                                                               | 3         | 6.25%   |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 4.17%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 4.17%   |
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard)  | 2         | 4.17%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 2.08%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 316       | 62.2%   |
| 1     | 148       | 29.13%  |
| 2     | 38        | 7.48%   |
| 3     | 4         | 0.79%   |
| 5     | 2         | 0.39%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 73        | 30.93%  |
| Graphics card            | 53        | 22.46%  |
| Chipcard                 | 40        | 16.95%  |
| Net/wireless             | 23        | 9.75%   |
| Communication controller | 8         | 3.39%   |
| Storage                  | 7         | 2.97%   |
| Multimedia controller    | 7         | 2.97%   |
| Bluetooth                | 7         | 2.97%   |
| Camera                   | 6         | 2.54%   |
| Unassigned class         | 5         | 2.12%   |
| Sound                    | 3         | 1.27%   |
| Net/ethernet             | 2         | 0.85%   |
| Network                  | 1         | 0.42%   |
| Modem                    | 1         | 0.42%   |

