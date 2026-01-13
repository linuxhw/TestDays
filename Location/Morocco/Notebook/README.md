Linux in Morocco - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Morocco.

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

Total: 508

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad L13 Gen 1 20R3S... | [453805a2c2](https://linux-hardware.org/?probe=453805a2c2) | Dec 17, 2025 |
| HP            | EliteBook 840 G5            | [f2cf9843ce](https://linux-hardware.org/?probe=f2cf9843ce) | Dec 16, 2025 |
| Dell          | Vostro 5620                 | [19a68d6339](https://linux-hardware.org/?probe=19a68d6339) | Dec 15, 2025 |
| Dell          | Latitude 5410               | [1780df9b4f](https://linux-hardware.org/?probe=1780df9b4f) | Dec 15, 2025 |
| Dell          | Precision M4800             | [b0ccbd6f89](https://linux-hardware.org/?probe=b0ccbd6f89) | Dec 13, 2025 |
| Acer          | Nitro AN515-51              | [d8cae4c49b](https://linux-hardware.org/?probe=d8cae4c49b) | Dec 12, 2025 |
| Apple         | MacBookPro12,1              | [a9d8f51c71](https://linux-hardware.org/?probe=a9d8f51c71) | Dec 08, 2025 |
| MSI           | Cyborg 15 A13VFK            | [5902ddb8c1](https://linux-hardware.org/?probe=5902ddb8c1) | Dec 07, 2025 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [d7e95ddd34](https://linux-hardware.org/?probe=d7e95ddd34) | Dec 06, 2025 |
| HP            | 250 G4                      | [f015980d3c](https://linux-hardware.org/?probe=f015980d3c) | Dec 02, 2025 |
| Lenovo        | Yoga Pro 7 14APH8 82Y8      | [f5b8800286](https://linux-hardware.org/?probe=f5b8800286) | Nov 30, 2025 |
| ASUSTek       | K52Jc                       | [56b3a4c466](https://linux-hardware.org/?probe=56b3a4c466) | Nov 30, 2025 |
| ASUSTek       | K52Jc                       | [c098c92aab](https://linux-hardware.org/?probe=c098c92aab) | Nov 29, 2025 |
| Lenovo        | ThinkPad L13 Gen 1 20R3S... | [d3a8af3d73](https://linux-hardware.org/?probe=d3a8af3d73) | Nov 28, 2025 |
| Acer          | Nitro ANV15-51              | [92988cd7a1](https://linux-hardware.org/?probe=92988cd7a1) | Nov 27, 2025 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [c3f71f07fa](https://linux-hardware.org/?probe=c3f71f07fa) | Nov 23, 2025 |
| Lenovo        | ThinkPad L13 Gen 1 20R3S... | [ce4c3a852c](https://linux-hardware.org/?probe=ce4c3a852c) | Nov 18, 2025 |
| HP            | EliteBook 830 G6            | [2756765643](https://linux-hardware.org/?probe=2756765643) | Nov 16, 2025 |
| HP            | Laptop 15-dw2xxx            | [b27a742abd](https://linux-hardware.org/?probe=b27a742abd) | Nov 13, 2025 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [f1ca8ef6bc](https://linux-hardware.org/?probe=f1ca8ef6bc) | Nov 10, 2025 |
| HP            | EliteBook 830 G7 Noteboo... | [61f2929dd9](https://linux-hardware.org/?probe=61f2929dd9) | Nov 09, 2025 |
| Apple         | MacBookPro9,1               | [543b1b6b44](https://linux-hardware.org/?probe=543b1b6b44) | Nov 07, 2025 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | [667441173b](https://linux-hardware.org/?probe=667441173b) | Nov 03, 2025 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | [bc5ebebe56](https://linux-hardware.org/?probe=bc5ebebe56) | Nov 03, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop K550... | [2a060689fb](https://linux-hardware.org/?probe=2a060689fb) | Oct 30, 2025 |
| Packard Be... | EasyNote TJ65               | [1b426a6f41](https://linux-hardware.org/?probe=1b426a6f41) | Oct 29, 2025 |
| HP            | 15                          | [fcd5131120](https://linux-hardware.org/?probe=fcd5131120) | Oct 26, 2025 |
| HP            | 15                          | [e37f4e9f3b](https://linux-hardware.org/?probe=e37f4e9f3b) | Oct 26, 2025 |
| ASUSTek       | X751LJ                      | [f0348e2454](https://linux-hardware.org/?probe=f0348e2454) | Oct 25, 2025 |
| Dell          | Latitude E7270              | [47a17048ad](https://linux-hardware.org/?probe=47a17048ad) | Oct 23, 2025 |
| HP            | ProBook 4530s               | [5be57cd4ab](https://linux-hardware.org/?probe=5be57cd4ab) | Oct 18, 2025 |
| Lenovo        | ThinkPad T14 Gen 4 21K4S... | [035d8be55f](https://linux-hardware.org/?probe=035d8be55f) | Oct 14, 2025 |
| Acer          | Aspire E5-571               | [91f7345324](https://linux-hardware.org/?probe=91f7345324) | Oct 10, 2025 |
| Acer          | TravelMate 3040             | [89302c24f3](https://linux-hardware.org/?probe=89302c24f3) | Oct 09, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [005026698e](https://linux-hardware.org/?probe=005026698e) | Oct 09, 2025 |
| Lenovo        | ThinkPad T480s 20L8S1QX0... | [f15b88c78d](https://linux-hardware.org/?probe=f15b88c78d) | Oct 08, 2025 |
| HP            | EliteBook 830 G5            | [73bd4bc6e3](https://linux-hardware.org/?probe=73bd4bc6e3) | Sep 29, 2025 |
| HP            | EliteBook 840 G5            | [2961f20b6e](https://linux-hardware.org/?probe=2961f20b6e) | Sep 28, 2025 |
| HP            | EliteBook 840 G5            | [755bd2060a](https://linux-hardware.org/?probe=755bd2060a) | Sep 23, 2025 |
| Dell          | Latitude 3520               | [0d41b49c2d](https://linux-hardware.org/?probe=0d41b49c2d) | Sep 21, 2025 |
| Fujitsu       | LIFEBOOK S710               | [226b5ddf14](https://linux-hardware.org/?probe=226b5ddf14) | Aug 25, 2025 |
| Fujitsu       | LIFEBOOK S710               | [c4b4548f63](https://linux-hardware.org/?probe=c4b4548f63) | Aug 25, 2025 |
| InnJoo Tec... | LeapBook A100               | [8689175ea7](https://linux-hardware.org/?probe=8689175ea7) | Aug 25, 2025 |
| Dell          | Latitude 3420               | [03c8355499](https://linux-hardware.org/?probe=03c8355499) | Aug 23, 2025 |
| HP            | 250 G3                      | [1353b8cc05](https://linux-hardware.org/?probe=1353b8cc05) | Aug 22, 2025 |
| Acer          | Aspire 7750G                | [b92992269d](https://linux-hardware.org/?probe=b92992269d) | Aug 16, 2025 |
| Samsung       | R520/R522/R620              | [4dd0921343](https://linux-hardware.org/?probe=4dd0921343) | Aug 11, 2025 |
| HONOR         | NMH-WDX9                    | [3aecbd42e4](https://linux-hardware.org/?probe=3aecbd42e4) | Aug 11, 2025 |
| TUXEDO        | InfinityBook S 14 v5        | [aec801fbb2](https://linux-hardware.org/?probe=aec801fbb2) | Aug 11, 2025 |
| Dell          | Latitude E6540              | [0ebaf61703](https://linux-hardware.org/?probe=0ebaf61703) | Jul 28, 2025 |
| Packard Be... | EasyNote TS44HR             | [75d8a5514e](https://linux-hardware.org/?probe=75d8a5514e) | Jul 27, 2025 |
| Dell          | Latitude E7450              | [029f64453f](https://linux-hardware.org/?probe=029f64453f) | Jul 14, 2025 |
| ASUSTek       | ROG Strix G731GT_G731GT     | [af279e0b13](https://linux-hardware.org/?probe=af279e0b13) | Jul 04, 2025 |
| Lenovo        | ThinkPad P16 Gen 1 21D7S... | [ff6d865b08](https://linux-hardware.org/?probe=ff6d865b08) | Jun 27, 2025 |
| HP            | ProBook 450 G5              | [5f70582ba0](https://linux-hardware.org/?probe=5f70582ba0) | Jun 26, 2025 |
| HP            | ProBook 450 G5              | [6e23047148](https://linux-hardware.org/?probe=6e23047148) | Jun 25, 2025 |
| Dell          | G15 5530                    | [9d909179f6](https://linux-hardware.org/?probe=9d909179f6) | Jun 21, 2025 |
| Dell          | G15 5530                    | [d2aedbfe4b](https://linux-hardware.org/?probe=d2aedbfe4b) | Jun 21, 2025 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [d602e008c4](https://linux-hardware.org/?probe=d602e008c4) | Jun 09, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop K550... | [6608283a6f](https://linux-hardware.org/?probe=6608283a6f) | Jun 05, 2025 |
| HP            | ZBook 17 G5                 | [d1da183e06](https://linux-hardware.org/?probe=d1da183e06) | Jun 03, 2025 |
| Dell          | Latitude E5550              | [b65aa76fdd](https://linux-hardware.org/?probe=b65aa76fdd) | May 30, 2025 |
| Lenovo        | ThinkPad X9-15 Gen 1 21Q... | [d599bc9225](https://linux-hardware.org/?probe=d599bc9225) | May 30, 2025 |
| Medion        | Deputy P60                  | [de230fe1d6](https://linux-hardware.org/?probe=de230fe1d6) | May 26, 2025 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | [d6e4d0040a](https://linux-hardware.org/?probe=d6e4d0040a) | May 23, 2025 |
| Lenovo        | LOQ 15ARP9 83JC             | [86e55ec780](https://linux-hardware.org/?probe=86e55ec780) | May 17, 2025 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | [c2f9a990f4](https://linux-hardware.org/?probe=c2f9a990f4) | May 13, 2025 |
| Lenovo        | ThinkPad T480s 20L8002AM... | [3fea75bfb6](https://linux-hardware.org/?probe=3fea75bfb6) | May 10, 2025 |
| Acer          | Nitro ANV15-51              | [5a61054a4e](https://linux-hardware.org/?probe=5a61054a4e) | May 08, 2025 |
| Acer          | Nitro ANV15-51              | [83659b1ed2](https://linux-hardware.org/?probe=83659b1ed2) | May 08, 2025 |
| Lenovo        | Legion 5 15ARP8 83EF        | [11da9879dd](https://linux-hardware.org/?probe=11da9879dd) | May 07, 2025 |
| Acer          | Aspire VN7-592G             | [7119eb8ee2](https://linux-hardware.org/?probe=7119eb8ee2) | May 07, 2025 |
| Dell          | Precision M4800             | [a10a92bd94](https://linux-hardware.org/?probe=a10a92bd94) | May 04, 2025 |
| Lenovo        | V15-ADA 82C7                | [45a2563f6d](https://linux-hardware.org/?probe=45a2563f6d) | Apr 30, 2025 |
| Dell          | Vostro 3400                 | [556772bb8b](https://linux-hardware.org/?probe=556772bb8b) | Apr 27, 2025 |
| Dell          | Precision M4800             | [396676851e](https://linux-hardware.org/?probe=396676851e) | Apr 27, 2025 |
| Dell          | Vostro 3400                 | [cc26bf4f4c](https://linux-hardware.org/?probe=cc26bf4f4c) | Apr 23, 2025 |
| HP            | ZBook 15 G3                 | [a35f480c86](https://linux-hardware.org/?probe=a35f480c86) | Apr 10, 2025 |
| Lenovo        | ThinkPad T470 20JNS00U0D    | [1614b9e507](https://linux-hardware.org/?probe=1614b9e507) | Mar 29, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [5d39519f05](https://linux-hardware.org/?probe=5d39519f05) | Mar 25, 2025 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [9b4356118a](https://linux-hardware.org/?probe=9b4356118a) | Mar 23, 2025 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [00586776cb](https://linux-hardware.org/?probe=00586776cb) | Mar 13, 2025 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [561990fd99](https://linux-hardware.org/?probe=561990fd99) | Mar 10, 2025 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [7dc9a8e543](https://linux-hardware.org/?probe=7dc9a8e543) | Mar 07, 2025 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [178350bae4](https://linux-hardware.org/?probe=178350bae4) | Mar 07, 2025 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [df31951584](https://linux-hardware.org/?probe=df31951584) | Feb 28, 2025 |
| Fujitsu       | LIFEBOOK U7511              | [9c9f33279a](https://linux-hardware.org/?probe=9c9f33279a) | Feb 21, 2025 |
| Lenovo        | ThinkPad T460 20FMS2B900    | [4727c8c9b6](https://linux-hardware.org/?probe=4727c8c9b6) | Feb 20, 2025 |
| HP            | EliteBook 840 G2            | [a95bcf56f4](https://linux-hardware.org/?probe=a95bcf56f4) | Feb 12, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [8d4ffcee41](https://linux-hardware.org/?probe=8d4ffcee41) | Feb 09, 2025 |
| Dell          | Latitude 7410               | [626618a422](https://linux-hardware.org/?probe=626618a422) | Feb 09, 2025 |
| Dell          | Latitude 5420               | [6c020c51d8](https://linux-hardware.org/?probe=6c020c51d8) | Feb 05, 2025 |
| Dell          | Precision M4600             | [62888308aa](https://linux-hardware.org/?probe=62888308aa) | Feb 02, 2025 |
| Lenovo        | G510 20238                  | [00db8ad84b](https://linux-hardware.org/?probe=00db8ad84b) | Jan 15, 2025 |
| HP            | ProBook 640 G5              | [aea76733f3](https://linux-hardware.org/?probe=aea76733f3) | Jan 15, 2025 |
| Lenovo        | IdeaPad S145-15API 81UT     | [78a05e3b0e](https://linux-hardware.org/?probe=78a05e3b0e) | Jan 07, 2025 |
| HP            | ProBook 650 G2              | [b2fc855e3e](https://linux-hardware.org/?probe=b2fc855e3e) | Jan 03, 2025 |
| Dell          | Vostro 1500                 | [b5ecc28563](https://linux-hardware.org/?probe=b5ecc28563) | Dec 31, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [b007439528](https://linux-hardware.org/?probe=b007439528) | Dec 26, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JN0... | [dae98f533a](https://linux-hardware.org/?probe=dae98f533a) | Dec 19, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JN0... | [5655debff7](https://linux-hardware.org/?probe=5655debff7) | Dec 19, 2024 |
| Toshiba       | Satellite C55-B             | [524c33e748](https://linux-hardware.org/?probe=524c33e748) | Dec 16, 2024 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [3c936aa4e5](https://linux-hardware.org/?probe=3c936aa4e5) | Dec 16, 2024 |
| HP            | ProBook 6570b               | [70dbe6620b](https://linux-hardware.org/?probe=70dbe6620b) | Dec 14, 2024 |
| HP            | G62                         | [70f9d38537](https://linux-hardware.org/?probe=70f9d38537) | Dec 11, 2024 |
| HP            | Pavilion dv6                | [92fe6246ab](https://linux-hardware.org/?probe=92fe6246ab) | Dec 09, 2024 |
| HP            | Pavilion g6                 | [36c4171d06](https://linux-hardware.org/?probe=36c4171d06) | Nov 21, 2024 |
| HP            | ProBook 6560b               | [72ddcb1cf2](https://linux-hardware.org/?probe=72ddcb1cf2) | Nov 20, 2024 |
| Google        | Drawman                     | [46c461a6e2](https://linux-hardware.org/?probe=46c461a6e2) | Nov 18, 2024 |
| HP            | Notebook                    | [19d1189e7b](https://linux-hardware.org/?probe=19d1189e7b) | Nov 08, 2024 |
| Dell          | Latitude 7490               | [92bf691a6c](https://linux-hardware.org/?probe=92bf691a6c) | Nov 04, 2024 |
| HP            | Notebook                    | [abea0efa1e](https://linux-hardware.org/?probe=abea0efa1e) | Nov 01, 2024 |
| Dell          | Latitude 7490               | [ce28c4199d](https://linux-hardware.org/?probe=ce28c4199d) | Oct 29, 2024 |
| Samsung       | N150/N210/N220              | [eef263185a](https://linux-hardware.org/?probe=eef263185a) | Oct 22, 2024 |
| Lenovo        | IdeaPad Slim 5 14IRL8 82... | [62c3d2eddd](https://linux-hardware.org/?probe=62c3d2eddd) | Oct 17, 2024 |
| Dell          | Latitude 5420               | [622540975d](https://linux-hardware.org/?probe=622540975d) | Oct 10, 2024 |
| HP            | EliteBook 840 G5            | [533e95fac4](https://linux-hardware.org/?probe=533e95fac4) | Oct 09, 2024 |
| HP            | EliteBook 840 G5            | [c40e4f6c66](https://linux-hardware.org/?probe=c40e4f6c66) | Oct 09, 2024 |
| HP            | EliteBook 8470p             | [f71728ea0e](https://linux-hardware.org/?probe=f71728ea0e) | Sep 20, 2024 |
| Packard Be... | ENNS44HR                    | [b47db91782](https://linux-hardware.org/?probe=b47db91782) | Sep 20, 2024 |
| Dell          | Latitude 7490               | [2e22221506](https://linux-hardware.org/?probe=2e22221506) | Sep 19, 2024 |
| Dell          | Latitude 7490               | [b8cce215a5](https://linux-hardware.org/?probe=b8cce215a5) | Sep 18, 2024 |
| Dell          | XPS 15 9550                 | [266c779453](https://linux-hardware.org/?probe=266c779453) | Sep 12, 2024 |
| Dell          | Inspiron 7548               | [150c9ec14f](https://linux-hardware.org/?probe=150c9ec14f) | Sep 09, 2024 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [4c19a63fee](https://linux-hardware.org/?probe=4c19a63fee) | Sep 02, 2024 |
| HP            | EliteBook Folio 9480m       | [206392c090](https://linux-hardware.org/?probe=206392c090) | Aug 23, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [e0af5cb80e](https://linux-hardware.org/?probe=e0af5cb80e) | Aug 19, 2024 |
| HP            | OMEN Laptop 15-en1xxx       | [c349c2ef99](https://linux-hardware.org/?probe=c349c2ef99) | Aug 17, 2024 |
| Dell          | Precision M4600             | [fee987030c](https://linux-hardware.org/?probe=fee987030c) | Aug 12, 2024 |
| Dell          | Precision M4600             | [7decf1dba0](https://linux-hardware.org/?probe=7decf1dba0) | Aug 11, 2024 |
| Dell          | Latitude 5420               | [4017046879](https://linux-hardware.org/?probe=4017046879) | Aug 08, 2024 |
| HP            | 15                          | [89bd9fcc15](https://linux-hardware.org/?probe=89bd9fcc15) | Aug 05, 2024 |
| HP            | 15                          | [97a7e86ff2](https://linux-hardware.org/?probe=97a7e86ff2) | Aug 05, 2024 |
| HP            | ProBook 450 G8 Notebook ... | [9eed9965d0](https://linux-hardware.org/?probe=9eed9965d0) | Jul 25, 2024 |
| Toshiba       | Satellite C660              | [682ee2b1d0](https://linux-hardware.org/?probe=682ee2b1d0) | Jul 21, 2024 |
| Dell          | Vostro 3500                 | [8cafc4b7db](https://linux-hardware.org/?probe=8cafc4b7db) | Jul 19, 2024 |
| Lenovo        | Yoga Pro 9 16IMH9 83DN      | [add07540e5](https://linux-hardware.org/?probe=add07540e5) | Jul 09, 2024 |
| Lenovo        | Yoga Pro 9 16IMH9 83DN      | [efdb6c4558](https://linux-hardware.org/?probe=efdb6c4558) | Jul 06, 2024 |
| Acer          | Aspire E5-575G              | [b8bf8326fd](https://linux-hardware.org/?probe=b8bf8326fd) | Jul 06, 2024 |
| Lenovo        | Legion Pro 7 16IRX9H 83D... | [43fb16f634](https://linux-hardware.org/?probe=43fb16f634) | Jul 03, 2024 |
| Fujitsu       | LIFEBOOK U7511              | [e3ecabe043](https://linux-hardware.org/?probe=e3ecabe043) | Jun 19, 2024 |
| HP            | EliteBook 8740w             | [158dce1091](https://linux-hardware.org/?probe=158dce1091) | Jun 17, 2024 |
| HP            | Laptop 15-bs0xx             | [d7bb8a4ea8](https://linux-hardware.org/?probe=d7bb8a4ea8) | May 17, 2024 |
| Apple         | MacBookPro9,2               | [5b949515c2](https://linux-hardware.org/?probe=5b949515c2) | May 11, 2024 |
| ASUSTek       | X550LD                      | [1c55e1acf7](https://linux-hardware.org/?probe=1c55e1acf7) | May 08, 2024 |
| HP            | Laptop 15-ra0xx             | [4d00a746ff](https://linux-hardware.org/?probe=4d00a746ff) | May 02, 2024 |
| MSI           | GS66 Stealth 10SE           | [e436c09a5c](https://linux-hardware.org/?probe=e436c09a5c) | Apr 30, 2024 |
| ACCENT        | SMART 140                   | [49fb07fe3f](https://linux-hardware.org/?probe=49fb07fe3f) | Apr 27, 2024 |
| Acer          | Aspire 7750G                | [961d70c1de](https://linux-hardware.org/?probe=961d70c1de) | Apr 27, 2024 |
| Acer          | Nitro AN515-46              | [0a90ca1966](https://linux-hardware.org/?probe=0a90ca1966) | Apr 23, 2024 |
| Dell          | Latitude E7240              | [71103e976e](https://linux-hardware.org/?probe=71103e976e) | Apr 21, 2024 |
| HP            | ProBook 450 G0              | [686202a739](https://linux-hardware.org/?probe=686202a739) | Apr 13, 2024 |
| ASUSTek       | ZenBook UX482EG_UX482EG     | [c4c0c27585](https://linux-hardware.org/?probe=c4c0c27585) | Apr 13, 2024 |
| HP            | ProBook 450 G0              | [becdc6cf99](https://linux-hardware.org/?probe=becdc6cf99) | Apr 12, 2024 |
| HP            | Split 13 x2 Detachable P... | [17c8956856](https://linux-hardware.org/?probe=17c8956856) | Apr 12, 2024 |
| ASUSTek       | ZenBook UX482EG_UX482EG     | [4d6466d304](https://linux-hardware.org/?probe=4d6466d304) | Apr 10, 2024 |
| HP            | ZBook 17 G5                 | [2b22c5c485](https://linux-hardware.org/?probe=2b22c5c485) | Apr 07, 2024 |
| Fujitsu       | LIFEBOOK S761               | [e73c5851aa](https://linux-hardware.org/?probe=e73c5851aa) | Mar 30, 2024 |
| Dell          | Inspiron 3421               | [a5606e10ad](https://linux-hardware.org/?probe=a5606e10ad) | Mar 27, 2024 |
| ASUSTek       | X550LD                      | [91112364b8](https://linux-hardware.org/?probe=91112364b8) | Mar 26, 2024 |
| ASUSTek       | X550LD                      | [1c72f8459c](https://linux-hardware.org/?probe=1c72f8459c) | Mar 26, 2024 |
| Dell          | Latitude 5480               | [ff785a4ce1](https://linux-hardware.org/?probe=ff785a4ce1) | Mar 22, 2024 |
| Acer          | Aspire E5-771G              | [3b5d0f6921](https://linux-hardware.org/?probe=3b5d0f6921) | Mar 19, 2024 |
| HP            | ProBook 440 G8 Notebook ... | [0339864371](https://linux-hardware.org/?probe=0339864371) | Mar 09, 2024 |
| Dell          | Latitude 5289               | [fe338e3231](https://linux-hardware.org/?probe=fe338e3231) | Mar 09, 2024 |
| Dell          | Latitude E5550              | [4832591086](https://linux-hardware.org/?probe=4832591086) | Mar 08, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [e545b12914](https://linux-hardware.org/?probe=e545b12914) | Mar 07, 2024 |
| ASUSTek       | Zenbook UX3404VA_Q420VA     | [f44261baba](https://linux-hardware.org/?probe=f44261baba) | Feb 24, 2024 |
| Lenovo        | ThinkPad T410 2537VTC       | [a393686fff](https://linux-hardware.org/?probe=a393686fff) | Feb 18, 2024 |
| Acer          | Swift SFX14-51G             | [038f3ddc2e](https://linux-hardware.org/?probe=038f3ddc2e) | Feb 14, 2024 |
| HP            | EliteBook 850 G3            | [a3d2bf6949](https://linux-hardware.org/?probe=a3d2bf6949) | Feb 10, 2024 |
| Dell          | Latitude 5510               | [e0d5fe1c62](https://linux-hardware.org/?probe=e0d5fe1c62) | Feb 07, 2024 |
| HP            | 620                         | [523cfc94c0](https://linux-hardware.org/?probe=523cfc94c0) | Feb 03, 2024 |
| HP            | ProBook 5320m               | [3be604f862](https://linux-hardware.org/?probe=3be604f862) | Feb 03, 2024 |
| HP            | 15                          | [b99530abd5](https://linux-hardware.org/?probe=b99530abd5) | Feb 01, 2024 |
| HP            | 15                          | [874ae10280](https://linux-hardware.org/?probe=874ae10280) | Feb 01, 2024 |
| HP            | 620                         | [adcf9577e4](https://linux-hardware.org/?probe=adcf9577e4) | Feb 01, 2024 |
| ASUSTek       | X555LD                      | [e65c871d95](https://linux-hardware.org/?probe=e65c871d95) | Jan 31, 2024 |
| ASUSTek       | X555LD                      | [1433f11bba](https://linux-hardware.org/?probe=1433f11bba) | Jan 31, 2024 |
| Sony          | VPCF12A4E                   | [66fb5f96a0](https://linux-hardware.org/?probe=66fb5f96a0) | Jan 30, 2024 |
| HP            | ProBook 6560b               | [7b9f78e8df](https://linux-hardware.org/?probe=7b9f78e8df) | Jan 23, 2024 |
| HP            | EliteBook 840 G3            | [ea1922427f](https://linux-hardware.org/?probe=ea1922427f) | Jan 19, 2024 |
| Dell          | Latitude 7390               | [837b633afe](https://linux-hardware.org/?probe=837b633afe) | Jan 14, 2024 |
| HP            | EliteBook 830 G5            | [106a150b97](https://linux-hardware.org/?probe=106a150b97) | Jan 13, 2024 |
| HP            | EliteBook 840 G5            | [f6b222e444](https://linux-hardware.org/?probe=f6b222e444) | Jan 06, 2024 |
| HP            | EliteBook 840 G5            | [0af2ce345e](https://linux-hardware.org/?probe=0af2ce345e) | Jan 06, 2024 |
| HP            | ZBook Studio G3             | [21b560e443](https://linux-hardware.org/?probe=21b560e443) | Jan 04, 2024 |
| HP            | ProBook 640 G1              | [a6ba47a6e6](https://linux-hardware.org/?probe=a6ba47a6e6) | Jan 01, 2024 |
| Dell          | Latitude E5470              | [71121b89c8](https://linux-hardware.org/?probe=71121b89c8) | Dec 25, 2023 |
| Acer          | Aspire 7750G                | [cdbe6b267f](https://linux-hardware.org/?probe=cdbe6b267f) | Dec 19, 2023 |
| Acer          | Aspire 7750G                | [6fc9570e4f](https://linux-hardware.org/?probe=6fc9570e4f) | Dec 19, 2023 |
| Lenovo        | ThinkPad T480 20L6SH3L2D    | [73c69f2b50](https://linux-hardware.org/?probe=73c69f2b50) | Dec 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [04ed98dd4a](https://linux-hardware.org/?probe=04ed98dd4a) | Dec 09, 2023 |
| Dell          | Inspiron 3421               | [2ceba60d03](https://linux-hardware.org/?probe=2ceba60d03) | Dec 09, 2023 |
| Dell          | Inspiron 3421               | [912e908ba0](https://linux-hardware.org/?probe=912e908ba0) | Dec 09, 2023 |
| HP            | Pavilion 15                 | [e62aa2185a](https://linux-hardware.org/?probe=e62aa2185a) | Dec 02, 2023 |
| HP            | Pavilion 15                 | [4282694224](https://linux-hardware.org/?probe=4282694224) | Dec 01, 2023 |
| Toshiba       | Satellite Pro L300          | [8cc0e1c14d](https://linux-hardware.org/?probe=8cc0e1c14d) | Nov 09, 2023 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | [68dd4f08d9](https://linux-hardware.org/?probe=68dd4f08d9) | Nov 02, 2023 |
| Lenovo        | ThinkPad T480 20L6SH3L2D    | [db3f0ac717](https://linux-hardware.org/?probe=db3f0ac717) | Oct 31, 2023 |
| Thomson       | N14C4WH64                   | [8dd9b1dbde](https://linux-hardware.org/?probe=8dd9b1dbde) | Oct 28, 2023 |
| LG Electro... | R310-K.AP31B                | [ac3922c573](https://linux-hardware.org/?probe=ac3922c573) | Oct 24, 2023 |
| HP            | EliteBook 840 G3            | [a5a8709f77](https://linux-hardware.org/?probe=a5a8709f77) | Oct 19, 2023 |
| Lenovo        | ThinkPad T480s 20L8002AM... | [b8d09ca2f5](https://linux-hardware.org/?probe=b8d09ca2f5) | Oct 18, 2023 |
| Lenovo        | ThinkPad T480 20L6SH3L2D    | [e66ff52b09](https://linux-hardware.org/?probe=e66ff52b09) | Oct 13, 2023 |
| Apple         | MacBookAir7,2               | [0a667d66b7](https://linux-hardware.org/?probe=0a667d66b7) | Sep 26, 2023 |
| Apple         | MacBookAir7,2               | [15f8d0107f](https://linux-hardware.org/?probe=15f8d0107f) | Sep 26, 2023 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [dbe3003db5](https://linux-hardware.org/?probe=dbe3003db5) | Sep 25, 2023 |
| HP            | ProBook 640 G1              | [a941b27d32](https://linux-hardware.org/?probe=a941b27d32) | Sep 25, 2023 |
| HP            | 250 G4                      | [5290896e7d](https://linux-hardware.org/?probe=5290896e7d) | Sep 23, 2023 |
| Lenovo        | IdeaPadFlex 15D 20334       | [82b9c0d614](https://linux-hardware.org/?probe=82b9c0d614) | Sep 21, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | [fe68084259](https://linux-hardware.org/?probe=fe68084259) | Sep 18, 2023 |
| Acer          | Aspire 5742                 | [603e2a55fb](https://linux-hardware.org/?probe=603e2a55fb) | Sep 15, 2023 |
| Lenovo        | ThinkPad X260 20F5S2WX0R    | [cb338af601](https://linux-hardware.org/?probe=cb338af601) | Sep 04, 2023 |
| Acer          | Aspire 5742                 | [ff917b0920](https://linux-hardware.org/?probe=ff917b0920) | Sep 02, 2023 |
| Valve         | Jupiter                     | [6df7fe9dca](https://linux-hardware.org/?probe=6df7fe9dca) | Sep 02, 2023 |
| HP            | Bloog                       | [17077dd340](https://linux-hardware.org/?probe=17077dd340) | Aug 26, 2023 |
| Acer          | Nitro AN515-53              | [368352c126](https://linux-hardware.org/?probe=368352c126) | Jul 12, 2023 |
| Dell          | Latitude 5540               | [bdf022bb03](https://linux-hardware.org/?probe=bdf022bb03) | Jul 02, 2023 |
| Dell          | Latitude 5289               | [cb492423ed](https://linux-hardware.org/?probe=cb492423ed) | Jun 20, 2023 |
| Dell          | Latitude E7450              | [addda016c8](https://linux-hardware.org/?probe=addda016c8) | Jun 18, 2023 |
| ASUSTek       | X540LA                      | [55316783a4](https://linux-hardware.org/?probe=55316783a4) | Jun 16, 2023 |
| ASUSTek       | X540LA                      | [2c1b5651ed](https://linux-hardware.org/?probe=2c1b5651ed) | Jun 15, 2023 |
| ASUSTek       | UX32LN                      | [97ff235920](https://linux-hardware.org/?probe=97ff235920) | Jun 08, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [e92f94ecb3](https://linux-hardware.org/?probe=e92f94ecb3) | May 27, 2023 |
| HUAWEI        | CREM-WXX9                   | [73dfd22efc](https://linux-hardware.org/?probe=73dfd22efc) | May 21, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [7d4516eff2](https://linux-hardware.org/?probe=7d4516eff2) | May 20, 2023 |
| Dell          | Latitude E7450              | [14227e270f](https://linux-hardware.org/?probe=14227e270f) | May 19, 2023 |
| HP            | Pavilion g6                 | [21bf9f3d3f](https://linux-hardware.org/?probe=21bf9f3d3f) | May 12, 2023 |
| Dell          | Latitude 5510               | [2c279a470e](https://linux-hardware.org/?probe=2c279a470e) | May 10, 2023 |
| Lenovo        | ThinkPad T450 20BUS3E800    | [c419e60853](https://linux-hardware.org/?probe=c419e60853) | May 09, 2023 |
| Lenovo        | ThinkPad X201 3680HTG       | [9cb4890df2](https://linux-hardware.org/?probe=9cb4890df2) | May 06, 2023 |
| HP            | Pavilion g6                 | [3c4ec29c8a](https://linux-hardware.org/?probe=3c4ec29c8a) | May 05, 2023 |
| American M... | XA133PR110                  | [4c02a6f8da](https://linux-hardware.org/?probe=4c02a6f8da) | May 03, 2023 |
| HP            | EliteBook 830 G5            | [1979bde291](https://linux-hardware.org/?probe=1979bde291) | May 01, 2023 |
| HP            | 15                          | [17b9906d58](https://linux-hardware.org/?probe=17b9906d58) | May 01, 2023 |
| HP            | 15                          | [8fb1f3c8f8](https://linux-hardware.org/?probe=8fb1f3c8f8) | May 01, 2023 |
| Lenovo        | ThinkPad T430 2349BS7       | [8d832f0261](https://linux-hardware.org/?probe=8d832f0261) | Apr 26, 2023 |
| HP            | ProBook 5320m               | [7597710994](https://linux-hardware.org/?probe=7597710994) | Apr 24, 2023 |
| American M... | XA133PR110                  | [5c634b7029](https://linux-hardware.org/?probe=5c634b7029) | Apr 19, 2023 |
| American M... | XA133PR110                  | [08b47e43a7](https://linux-hardware.org/?probe=08b47e43a7) | Apr 17, 2023 |
| HP            | Laptop 15-dw2xxx            | [e9e05a1bb3](https://linux-hardware.org/?probe=e9e05a1bb3) | Apr 15, 2023 |
| HP            | Laptop 15-dw2xxx            | [0b4fdfd30e](https://linux-hardware.org/?probe=0b4fdfd30e) | Apr 15, 2023 |
| Lenovo        | ThinkPad X201 3680HTG       | [f7029b5f3b](https://linux-hardware.org/?probe=f7029b5f3b) | Apr 14, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [9fbd9476b2](https://linux-hardware.org/?probe=9fbd9476b2) | Mar 28, 2023 |
| Dell          | Latitude 5400               | [4e17f4827d](https://linux-hardware.org/?probe=4e17f4827d) | Mar 23, 2023 |
| Dell          | Latitude 5400               | [c85d243d8a](https://linux-hardware.org/?probe=c85d243d8a) | Mar 23, 2023 |
| Dell          | Vostro 3500                 | [2a85ee4871](https://linux-hardware.org/?probe=2a85ee4871) | Mar 15, 2023 |
| Dell          | Latitude E5450              | [2f16482775](https://linux-hardware.org/?probe=2f16482775) | Mar 04, 2023 |
| HP            | EliteBook 8440p             | [9ce5a599cd](https://linux-hardware.org/?probe=9ce5a599cd) | Mar 03, 2023 |
| Dell          | Latitude E6520              | [2774f2cb16](https://linux-hardware.org/?probe=2774f2cb16) | Mar 01, 2023 |
| ASUSTek       | X751LK                      | [f312f303e0](https://linux-hardware.org/?probe=f312f303e0) | Feb 26, 2023 |
| HP            | Pavilion g6                 | [39b27e9850](https://linux-hardware.org/?probe=39b27e9850) | Feb 19, 2023 |
| Dell          | Latitude E7450              | [16f40c9f6a](https://linux-hardware.org/?probe=16f40c9f6a) | Feb 17, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | [b82ad16853](https://linux-hardware.org/?probe=b82ad16853) | Feb 08, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | [76dd43711a](https://linux-hardware.org/?probe=76dd43711a) | Feb 08, 2023 |
| Toshiba       | Satellite C855-1LG          | [26ce54002a](https://linux-hardware.org/?probe=26ce54002a) | Feb 05, 2023 |
| Dell          | Latitude 3500               | [79cdb991bf](https://linux-hardware.org/?probe=79cdb991bf) | Feb 03, 2023 |
| Lenovo        | V310-15IKB 80T3             | [a39fb673c7](https://linux-hardware.org/?probe=a39fb673c7) | Feb 03, 2023 |
| Dell          | Latitude D630               | [aa435d7701](https://linux-hardware.org/?probe=aa435d7701) | Feb 03, 2023 |
| Dell          | Latitude D630               | [b191402036](https://linux-hardware.org/?probe=b191402036) | Feb 03, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [b33f2d5606](https://linux-hardware.org/?probe=b33f2d5606) | Jan 28, 2023 |
| Dell          | Latitude E6410              | [854634fb32](https://linux-hardware.org/?probe=854634fb32) | Jan 24, 2023 |
| Dell          | Latitude E6410              | [a5edbef8d2](https://linux-hardware.org/?probe=a5edbef8d2) | Jan 24, 2023 |
| Fujitsu Si... | AMILO Xi 3650               | [1f238129d8](https://linux-hardware.org/?probe=1f238129d8) | Jan 12, 2023 |
| Lenovo        | IdeaPadFlex 15D 20334       | [c5379f6dc1](https://linux-hardware.org/?probe=c5379f6dc1) | Jan 12, 2023 |
| Lenovo        | IdeaPadFlex 15D 20334       | [2c092397ea](https://linux-hardware.org/?probe=2c092397ea) | Jan 05, 2023 |
| Dell          | Latitude 5510               | [68e4810231](https://linux-hardware.org/?probe=68e4810231) | Dec 24, 2022 |
| SINTRONES     | AMB-5000G1                  | [3f9a3badb0](https://linux-hardware.org/?probe=3f9a3badb0) | Dec 17, 2022 |
| SINTRONES     | AMB-5000G1                  | [b1738a6528](https://linux-hardware.org/?probe=b1738a6528) | Dec 17, 2022 |
| Dell          | Latitude D820               | [29df917188](https://linux-hardware.org/?probe=29df917188) | Dec 16, 2022 |
| Dell          | Latitude D820               | [27f19eafce](https://linux-hardware.org/?probe=27f19eafce) | Dec 16, 2022 |
| Dell          | Latitude E7250              | [3e40466ae4](https://linux-hardware.org/?probe=3e40466ae4) | Dec 13, 2022 |
| HP            | Pavilion 15                 | [5d88eed564](https://linux-hardware.org/?probe=5d88eed564) | Dec 13, 2022 |
| Toshiba       | Satellite L50-B             | [5bbe558b2f](https://linux-hardware.org/?probe=5bbe558b2f) | Dec 05, 2022 |
| Lenovo        | ThinkPad T560 20FJS3YN00    | [636921b46c](https://linux-hardware.org/?probe=636921b46c) | Nov 24, 2022 |
| HP            | 15                          | [51711b792f](https://linux-hardware.org/?probe=51711b792f) | Nov 20, 2022 |
| HP            | EliteBook 8540w             | [4da059da1b](https://linux-hardware.org/?probe=4da059da1b) | Nov 14, 2022 |
| Lenovo        | B50-30 20382                | [c4e67c5f10](https://linux-hardware.org/?probe=c4e67c5f10) | Nov 13, 2022 |
| HP            | 250 G5 Notebook PC          | [d710968897](https://linux-hardware.org/?probe=d710968897) | Nov 11, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [451acdb910](https://linux-hardware.org/?probe=451acdb910) | Oct 31, 2022 |
| HP            | 15                          | [c356a2b0cd](https://linux-hardware.org/?probe=c356a2b0cd) | Oct 30, 2022 |
| HP            | 15                          | [34e1ac4cbe](https://linux-hardware.org/?probe=34e1ac4cbe) | Oct 30, 2022 |
| HP            | EliteBook Folio 1040 G1     | [81df2d786a](https://linux-hardware.org/?probe=81df2d786a) | Oct 15, 2022 |
| Dell          | Latitude E4310              | [318726cca9](https://linux-hardware.org/?probe=318726cca9) | Oct 14, 2022 |
| Casper        | EXCALIBUR G770              | [7961a3ca3e](https://linux-hardware.org/?probe=7961a3ca3e) | Oct 14, 2022 |
| eMachines     | eME528                      | [502802d50d](https://linux-hardware.org/?probe=502802d50d) | Oct 13, 2022 |
| Apple         | MacBookPro10,2              | [379590d053](https://linux-hardware.org/?probe=379590d053) | Oct 09, 2022 |
| HP            | ProBook 650 G1              | [e31d2052e5](https://linux-hardware.org/?probe=e31d2052e5) | Oct 06, 2022 |
| HP            | ProBook 650 G1              | [1bcfb0642f](https://linux-hardware.org/?probe=1bcfb0642f) | Oct 06, 2022 |
| Unknown       | 1.0                         | [f5b0e6a742](https://linux-hardware.org/?probe=f5b0e6a742) | Sep 24, 2022 |
| ASUSTek       | X555LD                      | [08793f9065](https://linux-hardware.org/?probe=08793f9065) | Sep 24, 2022 |
| HP            | EliteBook 840 G5            | [eb488dae73](https://linux-hardware.org/?probe=eb488dae73) | Sep 17, 2022 |
| HP            | EliteBook 840 G5            | [eb406c0e81](https://linux-hardware.org/?probe=eb406c0e81) | Sep 15, 2022 |
| HP            | EliteBook 840 G5            | [6b6e4efdfc](https://linux-hardware.org/?probe=6b6e4efdfc) | Sep 13, 2022 |
| HP            | EliteBook 840 G5            | [4083f9d2c9](https://linux-hardware.org/?probe=4083f9d2c9) | Sep 11, 2022 |
| HP            | EliteBook 840 G5            | [bd15d55792](https://linux-hardware.org/?probe=bd15d55792) | Sep 07, 2022 |
| Dell          | Latitude 5490               | [a3f76e546f](https://linux-hardware.org/?probe=a3f76e546f) | Sep 01, 2022 |
| ASUSTek       | K72Jk                       | [d456f7083c](https://linux-hardware.org/?probe=d456f7083c) | Aug 26, 2022 |
| HP            | Compaq 15                   | [c2bdac6148](https://linux-hardware.org/?probe=c2bdac6148) | Aug 21, 2022 |
| HP            | ProBook 450 G7              | [c636c0401e](https://linux-hardware.org/?probe=c636c0401e) | Aug 18, 2022 |
| Dell          | Latitude E5500              | [5d04270674](https://linux-hardware.org/?probe=5d04270674) | Aug 08, 2022 |
| Acer          | Aspire ES1-523              | [d14f053671](https://linux-hardware.org/?probe=d14f053671) | Aug 01, 2022 |
| Lenovo        | S21e-20 80M4                | [bec71c2353](https://linux-hardware.org/?probe=bec71c2353) | Jul 27, 2022 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | [02dd3c2357](https://linux-hardware.org/?probe=02dd3c2357) | Jul 21, 2022 |
| Dell          | Latitude D620               | [70be0d553e](https://linux-hardware.org/?probe=70be0d553e) | Jul 08, 2022 |
| HP            | Laptop 15-dw3xxx            | [44b541373b](https://linux-hardware.org/?probe=44b541373b) | Jul 08, 2022 |
| Dell          | Latitude E6420              | [ede3298bf4](https://linux-hardware.org/?probe=ede3298bf4) | Jul 02, 2022 |
| HP            | ZBook 15 G3                 | [8c6f371222](https://linux-hardware.org/?probe=8c6f371222) | Jun 19, 2022 |
| HP            | Laptop 15-ra0xx             | [947ca74beb](https://linux-hardware.org/?probe=947ca74beb) | Jun 16, 2022 |
| HP            | Laptop 15-ra0xx             | [70ed4ebad8](https://linux-hardware.org/?probe=70ed4ebad8) | Jun 16, 2022 |
| Lenovo        | ThinkPad T430 2349BS7       | [2369e183ec](https://linux-hardware.org/?probe=2369e183ec) | May 30, 2022 |
| eMachines     | eM350                       | [2573854a09](https://linux-hardware.org/?probe=2573854a09) | May 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [ae7670331c](https://linux-hardware.org/?probe=ae7670331c) | May 22, 2022 |
| Gigabyte      | AERO 15 KC                  | [5ebc19bd4c](https://linux-hardware.org/?probe=5ebc19bd4c) | May 18, 2022 |
| HP            | Laptop 17-cn0xxx            | [39bb2b41e5](https://linux-hardware.org/?probe=39bb2b41e5) | May 18, 2022 |
| HP            | Laptop 15s-eq2xxx           | [427af3e3a0](https://linux-hardware.org/?probe=427af3e3a0) | May 09, 2022 |
| HP            | Laptop 15-dw3xxx            | [7d4d1cb642](https://linux-hardware.org/?probe=7d4d1cb642) | May 06, 2022 |
| Dell          | Latitude E5440              | [556fccb6d3](https://linux-hardware.org/?probe=556fccb6d3) | May 06, 2022 |
| Packard Be... | EasyNote TS44HR             | [2eff4001dc](https://linux-hardware.org/?probe=2eff4001dc) | May 06, 2022 |
| HP            | Laptop 15-dw3xxx            | [889f1cba36](https://linux-hardware.org/?probe=889f1cba36) | Apr 30, 2022 |
| Toshiba       | Satellite C660              | [f4403056c8](https://linux-hardware.org/?probe=f4403056c8) | Apr 30, 2022 |
| HP            | Pavilion g6                 | [b79730a7af](https://linux-hardware.org/?probe=b79730a7af) | Apr 27, 2022 |
| Lenovo        | ThinkPad T460 20FN002SUS    | [0fad5f6cd2](https://linux-hardware.org/?probe=0fad5f6cd2) | Apr 21, 2022 |
| HP            | Presario C500 (GF852EA#A... | [b14e9c5694](https://linux-hardware.org/?probe=b14e9c5694) | Apr 08, 2022 |
| TrekStor      | Surfbook W2                 | [52eb1e4ce9](https://linux-hardware.org/?probe=52eb1e4ce9) | Apr 06, 2022 |
| HP            | Notebook                    | [313ca81d16](https://linux-hardware.org/?probe=313ca81d16) | Mar 27, 2022 |
| HP            | 250 G5 Notebook PC          | [24664b0486](https://linux-hardware.org/?probe=24664b0486) | Mar 25, 2022 |
| HP            | 250 G5 Notebook PC          | [1cb13706a4](https://linux-hardware.org/?probe=1cb13706a4) | Mar 25, 2022 |
| Dell          | Vostro 1015                 | [5eac01f806](https://linux-hardware.org/?probe=5eac01f806) | Mar 25, 2022 |
| Dell          | Vostro 1015                 | [ce0fa4ee36](https://linux-hardware.org/?probe=ce0fa4ee36) | Mar 25, 2022 |
| Dell          | Latitude E5440              | [6b871a160e](https://linux-hardware.org/?probe=6b871a160e) | Mar 22, 2022 |
| Dell          | Latitude E5440              | [bd5621d6e2](https://linux-hardware.org/?probe=bd5621d6e2) | Mar 21, 2022 |
| HP            | ProBook 440 G5              | [39d48e6d79](https://linux-hardware.org/?probe=39d48e6d79) | Feb 28, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [fc6097a447](https://linux-hardware.org/?probe=fc6097a447) | Feb 23, 2022 |
| Dell          | Inspiron 5558               | [6888384b59](https://linux-hardware.org/?probe=6888384b59) | Feb 21, 2022 |
| ASUSTek       | X751LD                      | [074c993361](https://linux-hardware.org/?probe=074c993361) | Feb 19, 2022 |
| Dell          | Latitude E6520              | [f921803f50](https://linux-hardware.org/?probe=f921803f50) | Feb 16, 2022 |
| HP            | EliteBook 8440p             | [ae8afcd09f](https://linux-hardware.org/?probe=ae8afcd09f) | Feb 13, 2022 |
| HP            | ProBook 440 G5              | [4769ae7351](https://linux-hardware.org/?probe=4769ae7351) | Feb 12, 2022 |
| Dell          | Precision M4800             | [8f91ff2d57](https://linux-hardware.org/?probe=8f91ff2d57) | Jan 29, 2022 |
| Dell          | Latitude E6520              | [ee96960cec](https://linux-hardware.org/?probe=ee96960cec) | Jan 25, 2022 |
| ASUSTek       | X540LA                      | [a24d99bf3b](https://linux-hardware.org/?probe=a24d99bf3b) | Jan 24, 2022 |
| Clevo         | W24/250CU                   | [64c6f06849](https://linux-hardware.org/?probe=64c6f06849) | Jan 22, 2022 |
| Google        | Banon                       | [3e792337e2](https://linux-hardware.org/?probe=3e792337e2) | Jan 21, 2022 |
| Google        | Banon                       | [c4cfb244b1](https://linux-hardware.org/?probe=c4cfb244b1) | Jan 21, 2022 |
| HP            | Pavilion g6                 | [099231b0b3](https://linux-hardware.org/?probe=099231b0b3) | Jan 19, 2022 |
| HP            | EliteBook 840 G1            | [8e4f80059d](https://linux-hardware.org/?probe=8e4f80059d) | Jan 14, 2022 |
| Lenovo        | ThinkPad P50 20EQS6J100     | [f366de3acf](https://linux-hardware.org/?probe=f366de3acf) | Jan 03, 2022 |
| Dell          | Precision 5560              | [04cb5954e9](https://linux-hardware.org/?probe=04cb5954e9) | Dec 31, 2021 |
| Timi          | TM1701                      | [ce3374e321](https://linux-hardware.org/?probe=ce3374e321) | Dec 23, 2021 |
| Acer          | Aspire One 522              | [7f495fc85b](https://linux-hardware.org/?probe=7f495fc85b) | Dec 21, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [331d419175](https://linux-hardware.org/?probe=331d419175) | Dec 06, 2021 |
| HP            | EliteBook 8460p             | [97aec623b3](https://linux-hardware.org/?probe=97aec623b3) | Dec 04, 2021 |
| ASUSTek       | K72Jr                       | [518ee0b884](https://linux-hardware.org/?probe=518ee0b884) | Nov 30, 2021 |
| ASUSTek       | K72Jr                       | [405b87f8bf](https://linux-hardware.org/?probe=405b87f8bf) | Nov 29, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3DD1... | [816aaebc79](https://linux-hardware.org/?probe=816aaebc79) | Nov 27, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3DD1... | [162c76040f](https://linux-hardware.org/?probe=162c76040f) | Nov 27, 2021 |
| Lenovo        | ThinkPad X13 Gen 2i 20WK... | [7b9f86430d](https://linux-hardware.org/?probe=7b9f86430d) | Nov 25, 2021 |
| Lenovo        | ThinkPad X13 Gen 2i 20WK... | [c5aa70cf8a](https://linux-hardware.org/?probe=c5aa70cf8a) | Nov 25, 2021 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [73b27d5257](https://linux-hardware.org/?probe=73b27d5257) | Nov 25, 2021 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [915ddf82b5](https://linux-hardware.org/?probe=915ddf82b5) | Nov 23, 2021 |
| HP            | EliteBook 8530w             | [e3a38e431e](https://linux-hardware.org/?probe=e3a38e431e) | Nov 23, 2021 |
| HP            | ZBook 15                    | [6aca3076ac](https://linux-hardware.org/?probe=6aca3076ac) | Nov 22, 2021 |
| HP            | 15                          | [e82411639f](https://linux-hardware.org/?probe=e82411639f) | Nov 20, 2021 |
| Toshiba       | Satellite L50-A-1EL         | [40fff0be70](https://linux-hardware.org/?probe=40fff0be70) | Nov 19, 2021 |
| Apple         | MacBookPro13,3              | [e80b600640](https://linux-hardware.org/?probe=e80b600640) | Nov 12, 2021 |
| HP            | Laptop 15-dw3xxx            | [966b61331a](https://linux-hardware.org/?probe=966b61331a) | Nov 05, 2021 |
| HP            | Laptop 15-dw3xxx            | [e1c9be9f1d](https://linux-hardware.org/?probe=e1c9be9f1d) | Nov 05, 2021 |
| HP            | Pavilion Power Laptop 15... | [c1f75f6249](https://linux-hardware.org/?probe=c1f75f6249) | Oct 27, 2021 |
| ASUSTek       | X540LA                      | [c947e5b1ea](https://linux-hardware.org/?probe=c947e5b1ea) | Oct 26, 2021 |
| HP            | Laptop 15-da0xxx            | [2de5c74bc0](https://linux-hardware.org/?probe=2de5c74bc0) | Oct 23, 2021 |
| HP            | 250 I3-5005U 15.6           | [94c7602d80](https://linux-hardware.org/?probe=94c7602d80) | Oct 20, 2021 |
| Sony          | VPCEH1L8E                   | [11ef4d4baf](https://linux-hardware.org/?probe=11ef4d4baf) | Oct 19, 2021 |
| Sony          | SVE14122CAW                 | [7e20d79b1d](https://linux-hardware.org/?probe=7e20d79b1d) | Oct 16, 2021 |
| Razer         | Blade Pro 17 (2019)         | [c0fc32d290](https://linux-hardware.org/?probe=c0fc32d290) | Oct 09, 2021 |
| Dell          | Latitude E5570              | [bfc3702626](https://linux-hardware.org/?probe=bfc3702626) | Oct 04, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | [c5f4555ed5](https://linux-hardware.org/?probe=c5f4555ed5) | Sep 29, 2021 |
| Dell          | Latitude E5570              | [b4f22d5062](https://linux-hardware.org/?probe=b4f22d5062) | Sep 27, 2021 |
| Dell          | Latitude E5570              | [42c88d1bb8](https://linux-hardware.org/?probe=42c88d1bb8) | Sep 27, 2021 |
| HP            | EliteBook 8530w             | [37a7444281](https://linux-hardware.org/?probe=37a7444281) | Sep 25, 2021 |
| HP            | EliteBook 8530w             | [326645a221](https://linux-hardware.org/?probe=326645a221) | Sep 25, 2021 |
| Dell          | XPS 13 9350                 | [b01438543e](https://linux-hardware.org/?probe=b01438543e) | Sep 20, 2021 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [554c02e687](https://linux-hardware.org/?probe=554c02e687) | Sep 14, 2021 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [e2202296c9](https://linux-hardware.org/?probe=e2202296c9) | Sep 13, 2021 |
| HP            | Pavilion Power Laptop 15... | [d63a5c07e1](https://linux-hardware.org/?probe=d63a5c07e1) | Aug 28, 2021 |
| HP            | Pavilion Power Laptop 15... | [78316d40ea](https://linux-hardware.org/?probe=78316d40ea) | Aug 28, 2021 |
| Lenovo        | ThinkPad X250 20CLS4WV08    | [2c09cdd5bd](https://linux-hardware.org/?probe=2c09cdd5bd) | Aug 12, 2021 |
| HP            | 15                          | [80ce139934](https://linux-hardware.org/?probe=80ce139934) | Aug 06, 2021 |
| HP            | 15                          | [24c674140c](https://linux-hardware.org/?probe=24c674140c) | Aug 05, 2021 |
| HP            | Laptop 15-dw3xxx            | [ea05f5d624](https://linux-hardware.org/?probe=ea05f5d624) | Jul 21, 2021 |
| Unknown       | 1.0                         | [d049c76d58](https://linux-hardware.org/?probe=d049c76d58) | Jul 08, 2021 |
| Unknown       | 1.0                         | [deb4346da8](https://linux-hardware.org/?probe=deb4346da8) | Jul 08, 2021 |
| Unknown       | 1.0                         | [967654bdb6](https://linux-hardware.org/?probe=967654bdb6) | Jul 04, 2021 |
| Unknown       | 1.0                         | [36977bacbe](https://linux-hardware.org/?probe=36977bacbe) | Jul 03, 2021 |
| HP            | Pavilion Power Laptop 15... | [19666df61f](https://linux-hardware.org/?probe=19666df61f) | Jun 26, 2021 |
| HP            | Pavilion Power Laptop 15... | [df836c85c5](https://linux-hardware.org/?probe=df836c85c5) | Jun 26, 2021 |
| HP            | EliteBook 840 G3            | [dd3d9ede87](https://linux-hardware.org/?probe=dd3d9ede87) | Jun 20, 2021 |
| Unknown       | Unknown                     | [80c0612f78](https://linux-hardware.org/?probe=80c0612f78) | Jun 04, 2021 |
| Unknown       | Unknown                     | [9bac89aecf](https://linux-hardware.org/?probe=9bac89aecf) | Jun 04, 2021 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | [3890d7877d](https://linux-hardware.org/?probe=3890d7877d) | May 06, 2021 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | [44810c2cc1](https://linux-hardware.org/?probe=44810c2cc1) | May 06, 2021 |
| Lenovo        | ThinkPad X220 4291V5K       | [c0b9d7bd52](https://linux-hardware.org/?probe=c0b9d7bd52) | Apr 26, 2021 |
| Lenovo        | ThinkPad X220 4291V5K       | [4ec1325f12](https://linux-hardware.org/?probe=4ec1325f12) | Apr 26, 2021 |
| HP            | EliteBook 8460p             | [cf8b627aa4](https://linux-hardware.org/?probe=cf8b627aa4) | Apr 11, 2021 |
| HP            | EliteBook 8460p             | [bd04b1367f](https://linux-hardware.org/?probe=bd04b1367f) | Apr 11, 2021 |
| HP            | EliteBook 840 G2            | [522eb62b1a](https://linux-hardware.org/?probe=522eb62b1a) | Apr 03, 2021 |
| HP            | EliteBook 840 G2            | [e9df8836cf](https://linux-hardware.org/?probe=e9df8836cf) | Apr 03, 2021 |
| HP            | EliteBook 2540p             | [46c15e3b14](https://linux-hardware.org/?probe=46c15e3b14) | Apr 01, 2021 |
| HP            | EliteBook 840 G2            | [e1023ad432](https://linux-hardware.org/?probe=e1023ad432) | Mar 31, 2021 |
| HP            | EliteBook 840 G2            | [5c9803ca79](https://linux-hardware.org/?probe=5c9803ca79) | Mar 31, 2021 |
| HP            | Pavilion Laptop 15-ck0xx    | [f973f0f31c](https://linux-hardware.org/?probe=f973f0f31c) | Mar 23, 2021 |
| Dell          | Latitude 5580               | [9fd0e8f6b5](https://linux-hardware.org/?probe=9fd0e8f6b5) | Mar 22, 2021 |
| Lenovo        | ThinkPad X220 4291B66       | [411fb65be7](https://linux-hardware.org/?probe=411fb65be7) | Mar 21, 2021 |
| HP            | Notebook                    | [fbc522f5e7](https://linux-hardware.org/?probe=fbc522f5e7) | Feb 24, 2021 |
| HP            | Pavilion Sleekbook 15       | [aeb3111a93](https://linux-hardware.org/?probe=aeb3111a93) | Feb 20, 2021 |
| HP            | EliteBook 840 G2            | [1ffab0446e](https://linux-hardware.org/?probe=1ffab0446e) | Feb 17, 2021 |
| Lenovo        | ThinkPad T460 20FN002SUS    | [2ba0a379e8](https://linux-hardware.org/?probe=2ba0a379e8) | Feb 16, 2021 |
| Dell          | Latitude 3480               | [533356cb56](https://linux-hardware.org/?probe=533356cb56) | Feb 15, 2021 |
| HP            | Pavilion dv7                | [17dcac4931](https://linux-hardware.org/?probe=17dcac4931) | Feb 10, 2021 |
| GPD           | MicroPC                     | [ed2233e6ce](https://linux-hardware.org/?probe=ed2233e6ce) | Feb 08, 2021 |
| Acer          | AO722                       | [24cb20b715](https://linux-hardware.org/?probe=24cb20b715) | Feb 04, 2021 |
| HP            | EliteBook 840 G2            | [8da09ed292](https://linux-hardware.org/?probe=8da09ed292) | Feb 04, 2021 |
| Lenovo        | ThinkPad E590 20NB002AMB    | [e45b210ee6](https://linux-hardware.org/?probe=e45b210ee6) | Feb 01, 2021 |
| Lenovo        | ThinkPad T460 20FN002SUS    | [6c9654a854](https://linux-hardware.org/?probe=6c9654a854) | Jan 25, 2021 |
| Apple         | MacBook5,2                  | [512f5b5bdc](https://linux-hardware.org/?probe=512f5b5bdc) | Jan 18, 2021 |
| HP            | Pavilion dv7                | [bc33dda5d6](https://linux-hardware.org/?probe=bc33dda5d6) | Jan 09, 2021 |
| HP            | 650                         | [65c5445c17](https://linux-hardware.org/?probe=65c5445c17) | Jan 08, 2021 |
| Sony          | VGN-FW11L                   | [e99fe042af](https://linux-hardware.org/?probe=e99fe042af) | Jan 06, 2021 |
| HP            | 255 G7 Notebook PC          | [493c807f09](https://linux-hardware.org/?probe=493c807f09) | Jan 06, 2021 |
| Lenovo        | ThinkPad E570 20H50078IX    | [9162d07863](https://linux-hardware.org/?probe=9162d07863) | Dec 31, 2020 |
| Lenovo        | ThinkPad E570 20H50078IX    | [f1f07aecd0](https://linux-hardware.org/?probe=f1f07aecd0) | Dec 31, 2020 |
| Dell          | Latitude E6440              | [cec6c1fd51](https://linux-hardware.org/?probe=cec6c1fd51) | Dec 25, 2020 |
| HP            | 650                         | [ff87d07205](https://linux-hardware.org/?probe=ff87d07205) | Dec 21, 2020 |
| Packard Be... | EasyNote TS11HR             | [9c31cf187f](https://linux-hardware.org/?probe=9c31cf187f) | Dec 17, 2020 |
| Timi          | TM1701                      | [bc63393a91](https://linux-hardware.org/?probe=bc63393a91) | Dec 13, 2020 |
| Lenovo        | ThinkPad T480s 20L8S3P30... | [1a37278a5b](https://linux-hardware.org/?probe=1a37278a5b) | Dec 13, 2020 |
| HP            | EliteBook 8560w             | [d546d8c598](https://linux-hardware.org/?probe=d546d8c598) | Nov 25, 2020 |
| HP            | EliteBook 8560w             | [9bb315e3ac](https://linux-hardware.org/?probe=9bb315e3ac) | Nov 25, 2020 |
| Dell          | Latitude E6440              | [6739c087eb](https://linux-hardware.org/?probe=6739c087eb) | Nov 20, 2020 |
| TUXEDO        | N13xWU                      | [b72558f93c](https://linux-hardware.org/?probe=b72558f93c) | Nov 19, 2020 |
| TUXEDO        | N13xWU                      | [e6a667e32c](https://linux-hardware.org/?probe=e6a667e32c) | Nov 08, 2020 |
| TUXEDO        | N13xWU                      | [b4cd820410](https://linux-hardware.org/?probe=b4cd820410) | Nov 08, 2020 |
| Lenovo        | ThinkPad X280 20KF001KFR    | [bb66d36c3e](https://linux-hardware.org/?probe=bb66d36c3e) | Oct 23, 2020 |
| ASUSTek       | X555LAB                     | [d4755cc80a](https://linux-hardware.org/?probe=d4755cc80a) | Oct 18, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [ef4b4ee1be](https://linux-hardware.org/?probe=ef4b4ee1be) | Oct 10, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [c1d3bd539a](https://linux-hardware.org/?probe=c1d3bd539a) | Oct 09, 2020 |
| HP            | ProBook 450 G0              | [a12e9900c0](https://linux-hardware.org/?probe=a12e9900c0) | Oct 07, 2020 |
| HP            | ProBook 450 G0              | [822c9a0ece](https://linux-hardware.org/?probe=822c9a0ece) | Oct 07, 2020 |
| HP            | Compaq nc6220 (PL814AV)     | [7f042faa64](https://linux-hardware.org/?probe=7f042faa64) | Oct 04, 2020 |
| HP            | EliteBook 8440p             | [a5438c06dc](https://linux-hardware.org/?probe=a5438c06dc) | Oct 02, 2020 |
| HP            | ProBook 6470b               | [0c6e7c5d06](https://linux-hardware.org/?probe=0c6e7c5d06) | Sep 30, 2020 |
| HP            | ProBook 6470b               | [3ab44ecc2c](https://linux-hardware.org/?probe=3ab44ecc2c) | Sep 20, 2020 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | [e36d2e46a2](https://linux-hardware.org/?probe=e36d2e46a2) | Sep 16, 2020 |
| Lenovo        | ThinkPad X280 20KF001KFR    | [09ba7a078c](https://linux-hardware.org/?probe=09ba7a078c) | Sep 06, 2020 |
| Toshiba       | Satellite L750              | [1c9467e7ff](https://linux-hardware.org/?probe=1c9467e7ff) | Aug 31, 2020 |
| Dell          | Latitude E5270              | [b9e93e40f1](https://linux-hardware.org/?probe=b9e93e40f1) | Aug 26, 2020 |
| Toshiba       | Satellite C855-2CF          | [00048c3fd7](https://linux-hardware.org/?probe=00048c3fd7) | Aug 26, 2020 |
| HP            | ProBook 650 G1              | [134ae0f98f](https://linux-hardware.org/?probe=134ae0f98f) | Aug 24, 2020 |
| Lenovo        | ThinkPad X280 20KF001KFR    | [47a6af7e14](https://linux-hardware.org/?probe=47a6af7e14) | Aug 23, 2020 |
| HP            | Laptop 15-da0xxx            | [b51e82eb8b](https://linux-hardware.org/?probe=b51e82eb8b) | Aug 08, 2020 |
| HP            | ProBook 440 G7              | [b2d1e5272e](https://linux-hardware.org/?probe=b2d1e5272e) | Aug 07, 2020 |
| Lenovo        | Z70-80 80FG                 | [8f0c5d78da](https://linux-hardware.org/?probe=8f0c5d78da) | Jul 29, 2020 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | [c4b91061bd](https://linux-hardware.org/?probe=c4b91061bd) | Jun 24, 2020 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | [1d9441c4cb](https://linux-hardware.org/?probe=1d9441c4cb) | Jun 24, 2020 |
| HP            | EliteBook 840 G2            | [8f31cacb03](https://linux-hardware.org/?probe=8f31cacb03) | Jun 15, 2020 |
| Dell          | Latitude E6410              | [63006c892d](https://linux-hardware.org/?probe=63006c892d) | Jun 12, 2020 |
| Dell          | Latitude E6540              | [0820a41e4a](https://linux-hardware.org/?probe=0820a41e4a) | Jun 03, 2020 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [d4a0f7593f](https://linux-hardware.org/?probe=d4a0f7593f) | May 30, 2020 |
| Packard Be... | EasyNote TK85               | [1ef7f1dccf](https://linux-hardware.org/?probe=1ef7f1dccf) | May 24, 2020 |
| HP            | Unknown                     | [83216ab6f8](https://linux-hardware.org/?probe=83216ab6f8) | May 23, 2020 |
| Dell          | Latitude E5270              | [79c2208ee5](https://linux-hardware.org/?probe=79c2208ee5) | May 16, 2020 |
| HP            | Laptop 15-da0xxx            | [4d933966bb](https://linux-hardware.org/?probe=4d933966bb) | May 16, 2020 |
| HP            | ZBook 15                    | [7fdf5ffeb8](https://linux-hardware.org/?probe=7fdf5ffeb8) | May 10, 2020 |
| Lenovo        | G50-70 20351                | [fea9f24d5a](https://linux-hardware.org/?probe=fea9f24d5a) | Apr 27, 2020 |
| Lenovo        | G50-70 20351                | [f6609c3613](https://linux-hardware.org/?probe=f6609c3613) | Apr 27, 2020 |
| ASUSTek       | UX31A                       | [2ce7c49619](https://linux-hardware.org/?probe=2ce7c49619) | Apr 16, 2020 |
| ASUSTek       | X542UAR                     | [1597291755](https://linux-hardware.org/?probe=1597291755) | Apr 03, 2020 |
| HP            | 250 G3                      | [e92714c5e6](https://linux-hardware.org/?probe=e92714c5e6) | Mar 18, 2020 |
| Dell          | Latitude E6510              | [bc7b29779f](https://linux-hardware.org/?probe=bc7b29779f) | Mar 08, 2020 |
| Packard Be... | EasyNote TK85               | [bf3776568a](https://linux-hardware.org/?probe=bf3776568a) | Feb 23, 2020 |
| HP            | EliteBook 8440p             | [2bc65b9511](https://linux-hardware.org/?probe=2bc65b9511) | Feb 22, 2020 |
| HP            | EliteBook 8440p             | [4ef298fd63](https://linux-hardware.org/?probe=4ef298fd63) | Feb 22, 2020 |
| HP            | Pavilion Laptop 15-cs2xx... | [98c2d41201](https://linux-hardware.org/?probe=98c2d41201) | Feb 21, 2020 |
| HP            | Pavilion Laptop 15-cs2xx... | [6b512c0e61](https://linux-hardware.org/?probe=6b512c0e61) | Feb 21, 2020 |
| Dell          | Latitude E5520              | [2994cbb1d2](https://linux-hardware.org/?probe=2994cbb1d2) | Feb 21, 2020 |
| Dell          | Inspiron 3521               | [35973fcba8](https://linux-hardware.org/?probe=35973fcba8) | Jan 01, 2020 |
| Medion        | P7615                       | [1402e4bf25](https://linux-hardware.org/?probe=1402e4bf25) | Dec 29, 2019 |
| Toshiba       | Satellite Pro C650          | [984a530b85](https://linux-hardware.org/?probe=984a530b85) | Dec 19, 2019 |
| Medion        | P7615                       | [56fdcbb995](https://linux-hardware.org/?probe=56fdcbb995) | Nov 25, 2019 |
| Medion        | P7615                       | [150034113d](https://linux-hardware.org/?probe=150034113d) | Nov 25, 2019 |
| Acer          | Aspire 7736                 | [64727a44db](https://linux-hardware.org/?probe=64727a44db) | Nov 24, 2019 |
| Acer          | Aspire 7736                 | [3415167cef](https://linux-hardware.org/?probe=3415167cef) | Nov 23, 2019 |
| Acer          | Aspire ES1-523              | [74c8472d6f](https://linux-hardware.org/?probe=74c8472d6f) | Nov 12, 2019 |
| ASUSTek       | X200MA                      | [860c71f889](https://linux-hardware.org/?probe=860c71f889) | Nov 10, 2019 |
| Acer          | Calpella                    | [6ff918b898](https://linux-hardware.org/?probe=6ff918b898) | Oct 29, 2019 |
| Dell          | Latitude 3590               | [8e1927b00a](https://linux-hardware.org/?probe=8e1927b00a) | Sep 22, 2019 |
| Lenovo        | ThinkPad T440 20B7S2MF01    | [4dc662ddb5](https://linux-hardware.org/?probe=4dc662ddb5) | Sep 04, 2019 |
| HP            | Laptop 15-bs0xx             | [73e92501d3](https://linux-hardware.org/?probe=73e92501d3) | Aug 29, 2019 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [d9903b4749](https://linux-hardware.org/?probe=d9903b4749) | May 14, 2019 |
| Toshiba       | Satellite L50-A-1DG         | [b0e44b3093](https://linux-hardware.org/?probe=b0e44b3093) | Apr 13, 2019 |
| Toshiba       | Satellite L50-A-1DG         | [1103235a87](https://linux-hardware.org/?probe=1103235a87) | Apr 13, 2019 |
| Acer          | Aspire E5-575               | [e7e29b676f](https://linux-hardware.org/?probe=e7e29b676f) | Mar 16, 2019 |
| Acer          | Aspire E5-575               | [4d2d0aa109](https://linux-hardware.org/?probe=4d2d0aa109) | Feb 20, 2019 |
| ASUSTek       | F5VL                        | [8c665a5eb1](https://linux-hardware.org/?probe=8c665a5eb1) | Feb 07, 2019 |
| ASUSTek       | F5VL                        | [d54a4a5d26](https://linux-hardware.org/?probe=d54a4a5d26) | Dec 12, 2018 |
| Lenovo        | ThinkPad X240 20AMA09VFR    | [8e1e3b46c5](https://linux-hardware.org/?probe=8e1e3b46c5) | Nov 26, 2018 |
| Lenovo        | ThinkPad X240 20AMA09VFR    | [b14f27a474](https://linux-hardware.org/?probe=b14f27a474) | Nov 26, 2018 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Morocco/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 35        | 9.14%   |
| Ubuntu 22.04        | 29        | 7.57%   |
| Arch Rolling        | 16        | 4.18%   |
| Ubuntu 18.04        | 13        | 3.39%   |
| KDE neon 20.04      | 10        | 2.61%   |
| Fedora 39           | 10        | 2.61%   |
| Ubuntu 24.04        | 9         | 2.35%   |
| OpenMandriva 4.3    | 9         | 2.35%   |
| Fedora 42           | 9         | 2.35%   |
| Debian 11           | 9         | 2.35%   |
| Zorin 17            | 8         | 2.09%   |
| Pop!_OS 22.04       | 8         | 2.09%   |
| ArcoLinux Rolling   | 8         | 2.09%   |
| Zorin 16            | 7         | 1.83%   |
| OpenMandriva 4.2    | 6         | 1.57%   |
| Linux Mint 22.2     | 6         | 1.57%   |
| Linux Mint 20.2     | 6         | 1.57%   |
| Fedora 41           | 6         | 1.57%   |
| OpenMandriva 23.01  | 5         | 1.31%   |
| Fedora 43           | 5         | 1.31%   |
| Fedora 40           | 5         | 1.31%   |
| Fedora 38           | 5         | 1.31%   |
| Xero Rolling        | 4         | 1.04%   |
| Ubuntu Unity 16.04  | 4         | 1.04%   |
| Ubuntu 20.10        | 4         | 1.04%   |
| Ubuntu 19.10        | 4         | 1.04%   |
| OpenMandriva 24.12  | 4         | 1.04%   |
| Linux Mint 21.3     | 4         | 1.04%   |
| Linux Mint 20.3     | 4         | 1.04%   |
| EndeavourOS Rolling | 4         | 1.04%   |
| Elementary 7.1      | 4         | 1.04%   |
| Arch                | 4         | 1.04%   |
| OpenMandriva 25.90  | 3         | 0.78%   |
| Manjaro             | 3         | 0.78%   |
| Linux Mint 22.1     | 3         | 0.78%   |
| Linux Mint 21.1     | 3         | 0.78%   |
| Debian 12           | 3         | 0.78%   |
| Xubuntu 20.04       | 2         | 0.52%   |
| Void Linux          | 2         | 0.52%   |
| Ubuntu 23.10        | 2         | 0.52%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 102       | 28.25%  |
| Fedora       | 42        | 11.63%  |
| OpenMandriva | 31        | 8.59%   |
| Linux Mint   | 28        | 7.76%   |
| Arch         | 19        | 5.26%   |
| Zorin        | 17        | 4.71%   |
| Debian       | 16        | 4.43%   |
| Kali         | 13        | 3.6%    |
| Pop!_OS      | 12        | 3.32%   |
| KDE neon     | 11        | 3.05%   |
| Manjaro      | 10        | 2.77%   |
| ArcoLinux    | 8         | 2.22%   |
| Elementary   | 6         | 1.66%   |
| Ubuntu Unity | 5         | 1.39%   |
| EndeavourOS  | 5         | 1.39%   |
| Xero         | 4         | 1.11%   |
| Xubuntu      | 3         | 0.83%   |
| Endless      | 3         | 0.83%   |
| Void Linux   | 2         | 0.55%   |
| Ubuntu MATE  | 2         | 0.55%   |
| SteamOS      | 2         | 0.55%   |
| openSUSE     | 2         | 0.55%   |
| Nobara       | 2         | 0.55%   |
| NixOS        | 2         | 0.55%   |
| MX           | 2         | 0.55%   |
| Garuda Linux | 2         | 0.55%   |
| RHEL         | 1         | 0.28%   |
| Parrot       | 1         | 0.28%   |
| Lubuntu      | 1         | 0.28%   |
| LMDE         | 1         | 0.28%   |
| Linux Lite   | 1         | 0.28%   |
| Kubuntu      | 1         | 0.28%   |
| CentOS       | 1         | 0.28%   |
| BunsenLabs   | 1         | 0.28%   |
| blendOS      | 1         | 0.28%   |
| Athenaos     | 1         | 0.28%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 9         | 2.21%   |
| 5.10.14-desktop-1omv4002 | 6         | 1.47%   |
| 6.2.0-33-generic         | 5         | 1.23%   |
| 6.14.2-desktop-3omv2590  | 5         | 1.23%   |
| 6.1.1-desktop-1omv2290   | 5         | 1.23%   |
| 5.8.0-43-generic         | 5         | 1.23%   |
| 5.13.0-40-generic        | 5         | 1.23%   |
| 6.12.1-desktop-1omv2490  | 4         | 0.98%   |
| 5.4.0-58-generic         | 4         | 0.98%   |
| 5.4.0-48-generic         | 4         | 0.98%   |
| 6.8.4-200.fc39.x86_64    | 3         | 0.74%   |
| 6.5.0-26-generic         | 3         | 0.74%   |
| 6.5.0-14-generic         | 3         | 0.74%   |
| 6.2.0-37-generic         | 3         | 0.74%   |
| 6.14.0-63.fc42.x86_64    | 3         | 0.74%   |
| 6.14.0-37-generic        | 3         | 0.74%   |
| 6.14.0-29-generic        | 3         | 0.74%   |
| 5.4.0-42-generic         | 3         | 0.74%   |
| 5.3.0-40-generic         | 3         | 0.74%   |
| 5.17.5-76051705-generic  | 3         | 0.74%   |
| 5.15.0-46-generic        | 3         | 0.74%   |
| 5.13.0-27-generic        | 3         | 0.74%   |
| 5.11.0-37-generic        | 3         | 0.74%   |
| 6.8.0-60-generic         | 2         | 0.49%   |
| 6.8.0-58-generic         | 2         | 0.49%   |
| 6.8.0-50-generic         | 2         | 0.49%   |
| 6.8.0-45-generic         | 2         | 0.49%   |
| 6.7.9-200.fc39.x86_64    | 2         | 0.49%   |
| 6.6.2-desktop-1omv2390   | 2         | 0.49%   |
| 6.5.0-28-generic         | 2         | 0.49%   |
| 6.5.0-21-generic         | 2         | 0.49%   |
| 6.4.11-desktop-1omv2390  | 2         | 0.49%   |
| 6.2.6-76060206-generic   | 2         | 0.49%   |
| 6.2.14-300.fc38.x86_64   | 2         | 0.49%   |
| 6.2.0-39-generic         | 2         | 0.49%   |
| 6.17.11-300.fc43.x86_64  | 2         | 0.49%   |
| 6.16.8+kali-amd64        | 2         | 0.49%   |
| 6.12.57+deb13-amd64      | 2         | 0.49%   |
| 6.12.48+deb13-amd64      | 2         | 0.49%   |
| 6.10.4-zen2-1-zen        | 2         | 0.49%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 34        | 8.81%   |
| 5.15.0  | 23        | 5.96%   |
| 6.8.0   | 17        | 4.4%    |
| 6.5.0   | 15        | 3.89%   |
| 5.8.0   | 14        | 3.63%   |
| 6.2.0   | 13        | 3.37%   |
| 5.13.0  | 13        | 3.37%   |
| 5.11.0  | 12        | 3.11%   |
| 4.15.0  | 12        | 3.11%   |
| 6.14.0  | 11        | 2.85%   |
| 5.3.0   | 10        | 2.59%   |
| 5.10.0  | 10        | 2.59%   |
| 5.16.7  | 9         | 2.33%   |
| 5.19.0  | 8         | 2.07%   |
| 6.11.0  | 6         | 1.55%   |
| 5.10.14 | 6         | 1.55%   |
| 5.0.0   | 6         | 1.55%   |
| 6.14.2  | 5         | 1.3%    |
| 6.1.1   | 5         | 1.3%    |
| 6.1.0   | 5         | 1.3%    |
| 6.12.1  | 4         | 1.04%   |
| 6.8.4   | 3         | 0.78%   |
| 6.7.9   | 3         | 0.78%   |
| 6.2.6   | 3         | 0.78%   |
| 6.17.7  | 3         | 0.78%   |
| 6.16.8  | 3         | 0.78%   |
| 6.10.3  | 3         | 0.78%   |
| 5.17.5  | 3         | 0.78%   |
| 4.18.0  | 3         | 0.78%   |
| 6.9.5   | 2         | 0.52%   |
| 6.8.7   | 2         | 0.52%   |
| 6.6.2   | 2         | 0.52%   |
| 6.5.3   | 2         | 0.52%   |
| 6.4.11  | 2         | 0.52%   |
| 6.2.9   | 2         | 0.52%   |
| 6.2.14  | 2         | 0.52%   |
| 6.17.8  | 2         | 0.52%   |
| 6.17.11 | 2         | 0.52%   |
| 6.14.5  | 2         | 0.52%   |
| 6.12.57 | 2         | 0.52%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 34        | 8.83%   |
| 5.15    | 29        | 7.53%   |
| 6.8     | 24        | 6.23%   |
| 6.14    | 22        | 5.71%   |
| 6.5     | 21        | 5.45%   |
| 6.2     | 21        | 5.45%   |
| 5.10    | 17        | 4.42%   |
| 5.8     | 16        | 4.16%   |
| 6.12    | 15        | 3.9%    |
| 5.13    | 14        | 3.64%   |
| 5.11    | 14        | 3.64%   |
| 6.1     | 12        | 3.12%   |
| 5.16    | 12        | 3.12%   |
| 4.15    | 12        | 3.12%   |
| 6.11    | 11        | 2.86%   |
| 5.19    | 11        | 2.86%   |
| 6.6     | 10        | 2.6%    |
| 6.17    | 10        | 2.6%    |
| 5.3     | 10        | 2.6%    |
| 6.10    | 8         | 2.08%   |
| 6.16    | 6         | 1.56%   |
| 5.17    | 6         | 1.56%   |
| 5.0     | 6         | 1.56%   |
| 6.9     | 5         | 1.3%    |
| 6.4     | 5         | 1.3%    |
| 6.3     | 5         | 1.3%    |
| 6.7     | 4         | 1.04%   |
| 6.13    | 4         | 1.04%   |
| 5.18    | 4         | 1.04%   |
| 6.0     | 3         | 0.78%   |
| 5.14    | 3         | 0.78%   |
| 4.18    | 3         | 0.78%   |
| 6.15    | 2         | 0.52%   |
| 4.19    | 2         | 0.52%   |
| 5.7     | 1         | 0.26%   |
| 4.4     | 1         | 0.26%   |
| 4.14    | 1         | 0.26%   |
| 4.13    | 1         | 0.26%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 344       | 98.01%  |
| i686   | 7         | 1.99%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 185       | 50.96%  |
| KDE5            | 48        | 13.22%  |
| XFCE            | 27        | 7.44%   |
| X-Cinnamon      | 21        | 5.79%   |
| Unknown         | 20        | 5.51%   |
| KDE6            | 19        | 5.23%   |
| KDE             | 7         | 1.93%   |
| Pantheon        | 6         | 1.65%   |
| Unity           | 5         | 1.38%   |
| MATE            | 4         | 1.1%    |
| i3              | 4         | 1.1%    |
| GNOME Classic   | 3         | 0.83%   |
| LXQt            | 2         | 0.55%   |
| Hyprland        | 2         | 0.55%   |
| GNOME Flashback | 2         | 0.55%   |
| Cinnamon        | 2         | 0.55%   |
| xmonad          | 1         | 0.28%   |
| sway            | 1         | 0.28%   |
| niri            | 1         | 0.28%   |
| KDE4            | 1         | 0.28%   |
| Budgie          | 1         | 0.28%   |
| bspwm           | 1         | 0.28%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 222       | 60.82%  |
| Wayland | 129       | 35.34%  |
| Unknown | 10        | 2.74%   |
| Tty     | 4         | 1.1%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 169       | 45.68%  |
| SDDM    | 64        | 17.3%   |
| GDM3    | 48        | 12.97%  |
| GDM     | 47        | 12.7%   |
| LightDM | 38        | 10.27%  |
| TDM     | 3         | 0.81%   |
| LY-DM   | 1         | 0.27%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Notebooks | Percent |
|------------|-----------|---------|
| en_US      | 208       | 58.76%  |
| fr_FR      | 94        | 26.55%  |
| Unknown    | 15        | 4.24%   |
| en_GB      | 13        | 3.67%   |
| C          | 6         | 1.69%   |
| es_ES      | 3         | 0.85%   |
| de_DE      | 3         | 0.85%   |
| ru_RU      | 2         | 0.56%   |
| ar_MA      | 2         | 0.56%   |
| ar_EG      | 2         | 0.56%   |
| it_IT      | 1         | 0.28%   |
| fr_MA      | 1         | 0.28%   |
| fr_BE      | 1         | 0.28%   |
| en_US.UTF8 | 1         | 0.28%   |
| en_NG      | 1         | 0.28%   |
| en_AG      | 1         | 0.28%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 212       | 59.38%  |
| EFI  | 145       | 40.62%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 249       | 69.55%  |
| Btrfs   | 53        | 14.8%   |
| Overlay | 30        | 8.38%   |
| Tmpfs   | 22        | 6.15%   |
| Xfs     | 2         | 0.56%   |
| Unknown | 2         | 0.56%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 165       | 45.96%  |
| GPT     | 138       | 38.44%  |
| MBR     | 56        | 15.6%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 316       | 88.52%  |
| Yes       | 41        | 11.48%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 250       | 69.83%  |
| Yes       | 108       | 30.17%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 106       | 30.2%   |
| Lenovo              | 68        | 19.37%  |
| Dell                | 60        | 17.09%  |
| ASUSTek Computer    | 30        | 8.55%   |
| Acer                | 20        | 5.7%    |
| Toshiba             | 11        | 3.13%   |
| Apple               | 7         | 1.99%   |
| Packard Bell        | 6         | 1.71%   |
| Sony                | 4         | 1.14%   |
| Samsung Electronics | 4         | 1.14%   |
| Fujitsu             | 3         | 0.85%   |
| TUXEDO              | 2         | 0.57%   |
| Timi                | 2         | 0.57%   |
| MSI                 | 2         | 0.57%   |
| Medion              | 2         | 0.57%   |
| HUAWEI              | 2         | 0.57%   |
| Google              | 2         | 0.57%   |
| eMachines           | 2         | 0.57%   |
| Unknown             | 2         | 0.57%   |
| Valve               | 1         | 0.28%   |
| TrekStor            | 1         | 0.28%   |
| Thomson             | 1         | 0.28%   |
| SINTRONES           | 1         | 0.28%   |
| Razer               | 1         | 0.28%   |
| Mediacom            | 1         | 0.28%   |
| LG Electronics      | 1         | 0.28%   |
| InnJoo Technology   | 1         | 0.28%   |
| HONOR               | 1         | 0.28%   |
| GPD                 | 1         | 0.28%   |
| Gigabyte Technology | 1         | 0.28%   |
| Fujitsu Siemens     | 1         | 0.28%   |
| Clevo               | 1         | 0.28%   |
| Casper              | 1         | 0.28%   |
| American Megatrends | 1         | 0.28%   |
| ACCENT              | 1         | 0.28%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| HP EliteBook 8440p                    | 4         | 1.14%   |
| HP EliteBook 840 G5                   | 4         | 1.14%   |
| HP EliteBook 840 G2                   | 4         | 1.14%   |
| HP Pavilion g6                        | 3         | 0.85%   |
| HP Notebook                           | 3         | 0.85%   |
| HP Laptop 15-dw3xxx                   | 3         | 0.85%   |
| HP EliteBook 840 G3                   | 3         | 0.85%   |
| HP EliteBook 830 G5                   | 3         | 0.85%   |
| ASUS X540LA                           | 3         | 0.85%   |
| Unknown                               | 3         | 0.85%   |
| Toshiba Satellite C660                | 2         | 0.57%   |
| Timi TM1701                           | 2         | 0.57%   |
| Packard Bell EasyNote TS44HR          | 2         | 0.57%   |
| Lenovo ThinkBook 15 G2 ITL 20VE       | 2         | 0.57%   |
| Lenovo IdeaPad S145-15IIL 81W8        | 2         | 0.57%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK | 2         | 0.57%   |
| Lenovo IdeaPad L3 15IML05 81Y3        | 2         | 0.57%   |
| HP ZBook 15 G3                        | 2         | 0.57%   |
| HP ZBook 15                           | 2         | 0.57%   |
| HP ProBook 6560b                      | 2         | 0.57%   |
| HP ProBook 650 G1                     | 2         | 0.57%   |
| HP ProBook 6470b                      | 2         | 0.57%   |
| HP ProBook 640 G1                     | 2         | 0.57%   |
| HP ProBook 450 G0                     | 2         | 0.57%   |
| HP Pavilion 15                        | 2         | 0.57%   |
| HP Laptop 15-ra0xx                    | 2         | 0.57%   |
| HP Laptop 15-dw2xxx                   | 2         | 0.57%   |
| HP Laptop 15-bs0xx                    | 2         | 0.57%   |
| HP EliteBook 8460p                    | 2         | 0.57%   |
| HP 250 G5 Notebook PC                 | 2         | 0.57%   |
| HP 250 G4                             | 2         | 0.57%   |
| HP 250 G3                             | 2         | 0.57%   |
| Dell Vostro 3500                      | 2         | 0.57%   |
| Dell Precision M4800                  | 2         | 0.57%   |
| Dell Latitude E7450                   | 2         | 0.57%   |
| Dell Latitude E6540                   | 2         | 0.57%   |
| Dell Latitude E6520                   | 2         | 0.57%   |
| Dell Latitude E6410                   | 2         | 0.57%   |
| Dell Latitude 5420                    | 2         | 0.57%   |
| ASUS X555LD                           | 2         | 0.57%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Dell Latitude         | 43        | 12.25%  |
| Lenovo ThinkPad       | 38        | 10.83%  |
| HP EliteBook          | 32        | 9.12%   |
| HP ProBook            | 21        | 5.98%   |
| Lenovo IdeaPad        | 14        | 3.99%   |
| HP Pavilion           | 12        | 3.42%   |
| HP Laptop             | 12        | 3.42%   |
| Acer Aspire           | 12        | 3.42%   |
| Toshiba Satellite     | 11        | 3.13%   |
| HP 250                | 7         | 1.99%   |
| HP ZBook              | 6         | 1.71%   |
| Dell Vostro           | 6         | 1.71%   |
| Packard Bell EasyNote | 5         | 1.42%   |
| ASUS VivoBook         | 5         | 1.42%   |
| Dell Precision        | 4         | 1.14%   |
| Dell Inspiron         | 4         | 1.14%   |
| Acer Nitro            | 4         | 1.14%   |
| Lenovo ThinkBook      | 3         | 0.85%   |
| HP Notebook           | 3         | 0.85%   |
| Fujitsu LIFEBOOK      | 3         | 0.85%   |
| ASUS Zenbook          | 3         | 0.85%   |
| ASUS X540LA           | 3         | 0.85%   |
| Unknown               | 3         | 0.85%   |
| Timi TM1701           | 2         | 0.57%   |
| Lenovo Yoga           | 2         | 0.57%   |
| Lenovo Legion         | 2         | 0.57%   |
| HP OMEN               | 2         | 0.57%   |
| HP Compaq             | 2         | 0.57%   |
| Dell XPS              | 2         | 0.57%   |
| ASUS X555LD           | 2         | 0.57%   |
| ASUS ROG              | 2         | 0.57%   |
| ASUS ASUS             | 2         | 0.57%   |
| Apple MacBookPro9     | 2         | 0.57%   |
| Valve Jupiter         | 1         | 0.28%   |
| TUXEDO N13xWU         | 1         | 0.28%   |
| TUXEDO InfinityBook   | 1         | 0.28%   |
| TrekStor Surfbook     | 1         | 0.28%   |
| Thomson N14C4WH64     | 1         | 0.28%   |
| Sony VPCF12A4E        | 1         | 0.28%   |
| Sony VPCEH1L8E        | 1         | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 32        | 9.12%   |
| 2011 | 30        | 8.55%   |
| 2013 | 29        | 8.26%   |
| 2016 | 28        | 7.98%   |
| 2020 | 27        | 7.69%   |
| 2014 | 27        | 7.69%   |
| 2010 | 27        | 7.69%   |
| 2015 | 23        | 6.55%   |
| 2017 | 21        | 5.98%   |
| 2019 | 20        | 5.7%    |
| 2021 | 17        | 4.84%   |
| 2012 | 15        | 4.27%   |
| 2009 | 12        | 3.42%   |
| 2023 | 9         | 2.56%   |
| 2022 | 9         | 2.56%   |
| 2024 | 8         | 2.28%   |
| 2008 | 7         | 1.99%   |
| 2007 | 4         | 1.14%   |
| 2006 | 4         | 1.14%   |
| 2025 | 1         | 0.28%   |
| 2005 | 1         | 0.28%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 351       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 334       | 94.35%  |
| Enabled  | 20        | 5.65%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 348       | 99.15%  |
| Yes  | 3         | 0.85%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 125       | 35.01%  |
| 3.01-4.0    | 77        | 21.57%  |
| 8.01-16.0   | 52        | 14.57%  |
| 16.01-24.0  | 49        | 13.73%  |
| 32.01-64.0  | 19        | 5.32%   |
| 1.01-2.0    | 17        | 4.76%   |
| 24.01-32.0  | 8         | 2.24%   |
| 2.01-3.0    | 6         | 1.68%   |
| 64.01-256.0 | 2         | 0.56%   |
| 0.51-1.0    | 2         | 0.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 122       | 31.69%  |
| 1.01-2.0  | 118       | 30.65%  |
| 4.01-8.0  | 68        | 17.66%  |
| 3.01-4.0  | 50        | 12.99%  |
| 0.51-1.0  | 15        | 3.9%    |
| 8.01-16.0 | 11        | 2.86%   |
| 0.01-0.5  | 1         | 0.26%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 285       | 80.28%  |
| 2      | 62        | 17.46%  |
| 3      | 7         | 1.97%   |
| 4      | 1         | 0.28%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 222       | 63.25%  |
| Yes       | 129       | 36.75%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 300       | 85.47%  |
| No        | 51        | 14.53%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 345       | 98.01%  |
| No        | 7         | 1.99%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 265       | 74.44%  |
| No        | 91        | 25.56%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Morocco | 351       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Casablanca              | 94        | 24.42%  |
| Marrakesh               | 42        | 10.91%  |
| Rabat                   | 33        | 8.57%   |
| Agadir                  | 26        | 6.75%   |
| Fes                     | 20        | 5.19%   |
| Tangier                 | 19        | 4.94%   |
| Kenitra                 | 19        | 4.94%   |
| Salé                   | 18        | 4.68%   |
| Oujda                   | 15        | 3.9%    |
| Meknes                  | 10        | 2.6%    |
| Khouribga               | 7         | 1.82%   |
| Nador                   | 5         | 1.3%    |
| El Jadida               | 5         | 1.3%    |
| Tiznit                  | 4         | 1.04%   |
| Safi                    | 4         | 1.04%   |
| Mohammedia              | 4         | 1.04%   |
| Beni Mellal             | 4         | 1.04%   |
| Tétouan                | 3         | 0.78%   |
| Temara                  | 3         | 0.78%   |
| Taza                    | 3         | 0.78%   |
| Méchouar de Casablanca | 3         | 0.78%   |
| Martil                  | 3         | 0.78%   |
| Khemisset               | 3         | 0.78%   |
| Guelmim                 | 3         | 0.78%   |
| Settat                  | 2         | 0.52%   |
| Imouzzer Kandar         | 2         | 0.52%   |
| Berkane                 | 2         | 0.52%   |
| Azamor                  | 2         | 0.52%   |
| Youssoufia              | 1         | 0.26%   |
| Tit Mellil              | 1         | 0.26%   |
| Targuist                | 1         | 0.26%   |
| Taourirt                | 1         | 0.26%   |
| Skhirate                | 1         | 0.26%   |
| Sidi Slimane            | 1         | 0.26%   |
| Sidi Kacem              | 1         | 0.26%   |
| Sidi Ifni               | 1         | 0.26%   |
| Sidi Allal El Bahraoui  | 1         | 0.26%   |
| Sefrou                  | 1         | 0.26%   |
| Oued Zem                | 1         | 0.26%   |
| Midelt                  | 1         | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 61        | 73     | 14.88%  |
| Seagate                     | 49        | 61     | 11.95%  |
| WDC                         | 44        | 58     | 10.73%  |
| Toshiba                     | 43        | 53     | 10.49%  |
| SanDisk                     | 25        | 29     | 6.1%    |
| Unknown                     | 23        | 31     | 5.61%   |
| SK hynix                    | 19        | 22     | 4.63%   |
| Hitachi                     | 14        | 15     | 3.41%   |
| Micron Technology           | 13        | 18     | 3.17%   |
| Intel                       | 13        | 17     | 3.17%   |
| HGST                        | 12        | 13     | 2.93%   |
| Kingston                    | 10        | 13     | 2.44%   |
| KIOXIA                      | 8         | 8      | 1.95%   |
| Apple                       | 8         | 8      | 1.95%   |
| PNY                         | 6         | 9      | 1.46%   |
| LITEON                      | 4         | 4      | 0.98%   |
| Crucial                     | 4         | 4      | 0.98%   |
| China                       | 4         | 5      | 0.98%   |
| Phison Electronics          | 3         | 4      | 0.73%   |
| Kingston Technology Company | 3         | 3      | 0.73%   |
| Unknown                     | 3         | 3      | 0.73%   |
| LITEONIT                    | 2         | 2      | 0.49%   |
| Lexar                       | 2         | 2      | 0.49%   |
| KingSpec                    | 2         | 4      | 0.49%   |
| KingFast                    | 2         | 3      | 0.49%   |
| KingDian                    | 2         | 9      | 0.49%   |
| GOODRAM                     | 2         | 2      | 0.49%   |
| Fujitsu                     | 2         | 2      | 0.49%   |
| A-DATA Technology           | 2         | 2      | 0.49%   |
| XUM                         | 1         | 1      | 0.24%   |
| Union Memory (Shenzhen)     | 1         | 1      | 0.24%   |
| TwinMOS                     | 1         | 1      | 0.24%   |
| Transcend                   | 1         | 1      | 0.24%   |
| Team                        | 1         | 1      | 0.24%   |
| Supersonic                  | 1         | 1      | 0.24%   |
| ShiJi                       | 1         | 2      | 0.24%   |
| SG                          | 1         | 1      | 0.24%   |
| Realtek                     | 1         | 1      | 0.24%   |
| RCESSD                      | 1         | 1      | 0.24%   |
| Phison                      | 1         | 1      | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                       | 7         | 1.65%   |
| Toshiba MQ04ABF100 1TB                               | 6         | 1.42%   |
| Seagate ST500LT012-1DG142 500GB                      | 6         | 1.42%   |
| Unknown MMC Card  64GB                               | 5         | 1.18%   |
| Toshiba MQ01ABF050 500GB                             | 5         | 1.18%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 5         | 1.18%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1024GB | 5         | 1.18%   |
| HGST HTS545050A7E680 500GB                           | 5         | 1.18%   |
| Unknown MMC Card  32GB                               | 4         | 0.95%   |
| Toshiba MQ01ABD050 500GB                             | 4         | 0.95%   |
| Seagate ST9500325AS 500GB                            | 4         | 0.95%   |
| Samsung NVMe SSD Drive 512GB                         | 4         | 0.95%   |
| WDC WD10SPZX-60Z10T0 1TB                             | 3         | 0.71%   |
| Toshiba MQ01ACF050 500GB                             | 3         | 0.71%   |
| Toshiba MQ01ABD100 1TB                               | 3         | 0.71%   |
| Toshiba KXG50ZNV256G 256GB                           | 3         | 0.71%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB     | 3         | 0.71%   |
| Samsung NVMe SSD Drive 256GB                         | 3         | 0.71%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB    | 3         | 0.71%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB   | 3         | 0.71%   |
| Unknown                                              | 3         | 0.71%   |
| WDC WD5000LPCX-80VHAT1 500GB                         | 2         | 0.47%   |
| WDC WD5000LPCX-60VHAT0 500GB                         | 2         | 0.47%   |
| WDC WD1600BEVT-22ZCT0 160GB                          | 2         | 0.47%   |
| WDC WD10JUCT-63CYNY0 1TB                             | 2         | 0.47%   |
| WDC WD10JPVX-60JC3T0 1TB                             | 2         | 0.47%   |
| WDC WD10JPVX-22JC3T0 1TB                             | 2         | 0.47%   |
| Unknown SB32G  32GB                                  | 2         | 0.47%   |
| Unknown MMC Card  16GB                               | 2         | 0.47%   |
| Toshiba XG6 NVMe SSD Controller 1024GB               | 2         | 0.47%   |
| SK hynix SKHynix_HFS512GDE9X081N 512GB               | 2         | 0.47%   |
| SK hynix SKHynix_HFS001TEJ9X115N 1024GB              | 2         | 0.47%   |
| SK hynix SC311 SATA 512GB SSD                        | 2         | 0.47%   |
| SK hynix BC501 NVMe Solid State Drive 512GB          | 2         | 0.47%   |
| Seagate ST980811AS 80GB                              | 2         | 0.47%   |
| Seagate ST9500423AS 500GB                            | 2         | 0.47%   |
| Seagate ST9250315AS 250GB                            | 2         | 0.47%   |
| Seagate ST500VT000-1DK142 500GB                      | 2         | 0.47%   |
| Seagate ST500LM012 HN-M500MBB 500GB                  | 2         | 0.47%   |
| Seagate ST500LM000-1EJ162 500GB                      | 2         | 0.47%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 49        | 61     | 31.41%  |
| WDC                 | 38        | 52     | 24.36%  |
| Toshiba             | 33        | 38     | 21.15%  |
| Hitachi             | 14        | 15     | 8.97%   |
| HGST                | 12        | 13     | 7.69%   |
| Samsung Electronics | 3         | 3      | 1.92%   |
| Apple               | 3         | 3      | 1.92%   |
| Fujitsu             | 2         | 2      | 1.28%   |
| Intenso             | 1         | 2      | 0.64%   |
| IBM/Hitachi         | 1         | 1      | 0.64%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 21        | 25     | 18.58%  |
| SanDisk             | 12        | 13     | 10.62%  |
| Kingston            | 9         | 12     | 7.96%   |
| Micron Technology   | 7         | 12     | 6.19%   |
| PNY                 | 6         | 9      | 5.31%   |
| SK hynix            | 4         | 6      | 3.54%   |
| LITEON              | 4         | 4      | 3.54%   |
| Intel               | 4         | 5      | 3.54%   |
| Crucial             | 4         | 4      | 3.54%   |
| China               | 4         | 5      | 3.54%   |
| Apple               | 4         | 4      | 3.54%   |
| Toshiba             | 3         | 3      | 2.65%   |
| LITEONIT            | 2         | 2      | 1.77%   |
| Lexar               | 2         | 2      | 1.77%   |
| KingSpec            | 2         | 4      | 1.77%   |
| KingDian            | 2         | 9      | 1.77%   |
| GOODRAM             | 2         | 2      | 1.77%   |
| Unknown             | 2         | 2      | 1.77%   |
| XUM                 | 1         | 1      | 0.88%   |
| WDC                 | 1         | 1      | 0.88%   |
| TwinMOS             | 1         | 1      | 0.88%   |
| Transcend           | 1         | 1      | 0.88%   |
| Team                | 1         | 1      | 0.88%   |
| Supersonic          | 1         | 1      | 0.88%   |
| RCESSD              | 1         | 1      | 0.88%   |
| MSI                 | 1         | 1      | 0.88%   |
| KODAK               | 1         | 1      | 0.88%   |
| KingFast            | 1         | 1      | 0.88%   |
| Indilinx            | 1         | 1      | 0.88%   |
| Hewlett-Packard     | 1         | 1      | 0.88%   |
| Geonix              | 1         | 1      | 0.88%   |
| BIWIN               | 1         | 1      | 0.88%   |
| Bestoss             | 1         | 1      | 0.88%   |
| Apacer              | 1         | 1      | 0.88%   |
| AFOX                | 1         | 1      | 0.88%   |
| A-DATA Technology   | 1         | 1      | 0.88%   |
| 2.5"                | 1         | 1      | 0.88%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 154       | 190    | 38.99%  |
| SSD     | 109       | 142    | 27.59%  |
| NVMe    | 105       | 135    | 26.58%  |
| MMC     | 23        | 31     | 5.82%   |
| Unknown | 4         | 6      | 1.01%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 247       | 335    | 65.34%  |
| NVMe | 104       | 133    | 27.51%  |
| MMC  | 23        | 31     | 6.08%   |
| SAS  | 4         | 5      | 1.06%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 190       | 239    | 73.64%  |
| 0.51-1.0   | 60        | 82     | 23.26%  |
| 1.01-2.0   | 8         | 11     | 3.1%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 112       | 30.68%  |
| 251-500        | 93        | 25.48%  |
| 501-1000       | 44        | 12.05%  |
| 51-100         | 41        | 11.23%  |
| 1-20           | 28        | 7.67%   |
| 21-50          | 20        | 5.48%   |
| 1001-2000      | 16        | 4.38%   |
| Unknown        | 8         | 2.19%   |
| More than 3000 | 2         | 0.55%   |
| 2001-3000      | 1         | 0.27%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 148       | 38.24%  |
| 21-50          | 95        | 24.55%  |
| 101-250        | 60        | 15.5%   |
| 51-100         | 49        | 12.66%  |
| 251-500        | 18        | 4.65%   |
| Unknown        | 8         | 2.07%   |
| 501-1000       | 6         | 1.55%   |
| More than 3000 | 2         | 0.52%   |
| 1001-2000      | 1         | 0.26%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                  | Notebooks | Drives | Percent |
|--------------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD050 500GB                               | 3         | 3      | 6.98%   |
| Seagate ST9500325AS 500GB                              | 3         | 4      | 6.98%   |
| HGST HTS545050A7E680 500GB                             | 3         | 4      | 6.98%   |
| Hitachi HTS542525K9A300 250GB                          | 2         | 2      | 4.65%   |
| WDC WD5000BPVT-22HXZT1 500GB                           | 1         | 1      | 2.33%   |
| WDC WD2500BEVT-60ZCT1 250GB                            | 1         | 1      | 2.33%   |
| WDC WD2500BEVS-22UST0 250GB                            | 1         | 1      | 2.33%   |
| WDC WD2500BEKT-60A25T1 250GB                           | 1         | 1      | 2.33%   |
| WDC WD10SPZX-60Z10T0 1TB                               | 1         | 1      | 2.33%   |
| WDC WD10JPVX-60JC3T0 1TB                               | 1         | 8      | 2.33%   |
| WDC WD10JPVT-00A1YT0 1TB                               | 1         | 1      | 2.33%   |
| Toshiba MQ04ABF100 1TB                                 | 1         | 1      | 2.33%   |
| Toshiba MQ01ACF050 500GB                               | 1         | 1      | 2.33%   |
| Toshiba MQ01ABD032 320GB                               | 1         | 1      | 2.33%   |
| Toshiba MK3265GSX H 320GB                              | 1         | 1      | 2.33%   |
| Toshiba MK2565GSXN 250GB                               | 1         | 1      | 2.33%   |
| Toshiba MK1237GSX 120GB                                | 1         | 1      | 2.33%   |
| Seagate ST9500423AS 500GB                              | 1         | 1      | 2.33%   |
| Seagate ST9320423AS 320GB                              | 1         | 1      | 2.33%   |
| Seagate ST9100824AS 100GB                              | 1         | 1      | 2.33%   |
| Seagate ST500LT012-1DG142 500GB                        | 1         | 1      | 2.33%   |
| Seagate ST500LM021-1KJ152 500GB                        | 1         | 1      | 2.33%   |
| Seagate ST500LM012 HN-M500MBB 500GB                    | 1         | 1      | 2.33%   |
| Seagate ST500LM000-1EJ162 500GB                        | 1         | 1      | 2.33%   |
| SanDisk SD7UB3Q256G1001 256GB SSD                      | 1         | 1      | 2.33%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD       | 1         | 1      | 2.33%   |
| Samsung Electronics MZ7PD128HAFV-000H7 128GB SSD       | 1         | 1      | 2.33%   |
| Micron Technology 1100 SATA 256GB SSD                  | 1         | 1      | 2.33%   |
| Intel SSDSCKKF256G8H 256GB                             | 1         | 1      | 2.33%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series 512GB | 1         | 2      | 2.33%   |
| Hitachi HTS723232A7A364 320GB                          | 1         | 1      | 2.33%   |
| Hitachi HTS545050A7E380 500GB                          | 1         | 2      | 2.33%   |
| HGST HTS725032A7E630 320GB                             | 1         | 1      | 2.33%   |
| HGST HTS721010A9E630 1TB                               | 1         | 1      | 2.33%   |
| Fujitsu MHW2120BH 120GB                                | 1         | 1      | 2.33%   |
| Apple HDD HTS541010A9E662 1TB                          | 1         | 1      | 2.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 11     | 23.26%  |
| Toshiba             | 9         | 9      | 20.93%  |
| WDC                 | 7         | 14     | 16.28%  |
| HGST                | 5         | 6      | 11.63%  |
| Hitachi             | 4         | 5      | 9.3%    |
| Samsung Electronics | 2         | 2      | 4.65%   |
| Intel               | 2         | 3      | 4.65%   |
| SanDisk             | 1         | 1      | 2.33%   |
| Micron Technology   | 1         | 1      | 2.33%   |
| Fujitsu             | 1         | 1      | 2.33%   |
| Apple               | 1         | 1      | 2.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 10        | 11     | 27.03%  |
| Toshiba | 9         | 9      | 24.32%  |
| WDC     | 7         | 14     | 18.92%  |
| HGST    | 5         | 6      | 13.51%  |
| Hitachi | 4         | 5      | 10.81%  |
| Fujitsu | 1         | 1      | 2.7%    |
| Apple   | 1         | 1      | 2.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 37        | 47     | 86.05%  |
| SSD  | 5         | 5      | 11.63%  |
| NVMe | 1         | 2      | 2.33%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                      | Notebooks | Drives | Percent |
|--------------------------------------------|-----------|--------|---------|
| WDC WD2500BEVT-22A23T0 250GB               | 1         | 2      | 50%     |
| Samsung Electronics MZVLB1T0HALR-00000 1TB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 2      | 50%     |
| Samsung Electronics | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 212       | 294    | 56.23%  |
| Works    | 120       | 153    | 31.83%  |
| Malfunc  | 43        | 54     | 11.41%  |
| Failed   | 2         | 3      | 0.53%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 271       | 68.96%  |
| Samsung Electronics              | 40        | 10.18%  |
| SanDisk                          | 16        | 4.07%   |
| AMD                              | 16        | 4.07%   |
| SK hynix                         | 15        | 3.82%   |
| KIOXIA                           | 8         | 2.04%   |
| Toshiba America Info Systems     | 7         | 1.78%   |
| Micron Technology                | 6         | 1.53%   |
| Phison Electronics               | 4         | 1.02%   |
| Kingston Technology Company      | 4         | 1.02%   |
| Union Memory (Shenzhen)          | 1         | 0.25%   |
| Silicon Integrated Systems [SiS] | 1         | 0.25%   |
| O2 Micro                         | 1         | 0.25%   |
| Nvidia                           | 1         | 0.25%   |
| Micron/Crucial Technology        | 1         | 0.25%   |
| ADATA Technology                 | 1         | 0.25%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 32        | 7.66%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 30        | 7.18%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 26        | 6.22%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 20        | 4.78%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 19        | 4.55%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 18        | 4.31%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 16        | 3.83%   |
| Intel Volume Management Device NVMe RAID Controller                              | 15        | 3.59%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 13        | 3.11%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 13        | 3.11%   |
| Intel Tiger Lake-LP SATA Controller                                              | 12        | 2.87%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 12        | 2.87%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 11        | 2.63%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 10        | 2.39%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 9         | 2.15%   |
| Intel Comet Lake SATA AHCI Controller                                            | 8         | 1.91%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 8         | 1.91%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 5         | 1.2%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 5         | 1.2%    |
| Intel RST Volume Management Device Controller                                    | 5         | 1.2%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 5         | 1.2%    |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 4         | 0.96%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 4         | 0.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4         | 0.96%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 3         | 0.72%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                             | 3         | 0.72%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 3         | 0.72%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 3         | 0.72%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 0.72%   |
| Micron 2400 NVMe SSD (DRAM-less)                                                 | 3         | 0.72%   |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                       | 3         | 0.72%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 3         | 0.72%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 3         | 0.72%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 3         | 0.72%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 3         | 0.72%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 3         | 0.72%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                               | 2         | 0.48%   |
| SK hynix PC601 NVMe Solid State Drive                                            | 2         | 0.48%   |
| SanDisk WD SN560/SN740/SN770/SN5000 NVMe SSD                                     | 2         | 0.48%   |
| Sandisk WD PC SN740 NVMe SSD 512GB (DRAM-less)                                   | 2         | 0.48%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 233       | 57.53%  |
| NVMe | 104       | 25.68%  |
| RAID | 54        | 13.33%  |
| IDE  | 14        | 3.46%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 322       | 91.74%  |
| AMD    | 29        | 8.26%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz             | 12        | 3.42%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 11        | 3.13%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 9         | 2.56%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 7         | 1.99%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 7         | 1.99%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 7         | 1.99%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 7         | 1.99%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 7         | 1.99%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 6         | 1.71%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 6         | 1.71%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 6         | 1.71%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 1.42%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 5         | 1.42%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 5         | 1.42%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 5         | 1.42%   |
| Intel Core i5-10310U CPU @ 1.70GHz            | 5         | 1.42%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 5         | 1.42%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 1.14%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 4         | 1.14%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 1.14%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 4         | 1.14%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 3         | 0.85%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 3         | 0.85%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 3         | 0.85%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 0.85%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 0.85%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 3         | 0.85%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 3         | 0.85%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 0.85%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 3         | 0.85%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 3         | 0.85%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 3         | 0.85%   |
| Intel Core i3 CPU M 350 @ 2.27GHz             | 3         | 0.85%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 3         | 0.85%   |
| Intel 13th Gen Core i7-13700H                 | 3         | 0.85%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 0.85%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 2         | 0.57%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.57%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 2         | 0.57%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 136       | 38.75%  |
| Intel Core i7           | 60        | 17.09%  |
| Other                   | 39        | 11.11%  |
| Intel Core i3           | 37        | 10.54%  |
| Intel Core 2 Duo        | 15        | 4.27%   |
| Intel Celeron           | 14        | 3.99%   |
| Intel Atom              | 8         | 2.28%   |
| AMD Ryzen 7             | 8         | 2.28%   |
| AMD Ryzen 5             | 5         | 1.42%   |
| AMD E1                  | 3         | 0.85%   |
| Intel Pentium Dual-Core | 2         | 0.57%   |
| Intel Pentium           | 2         | 0.57%   |
| Intel Core 2            | 2         | 0.57%   |
| Intel Core              | 2         | 0.57%   |
| AMD C-60                | 2         | 0.57%   |
| AMD A8                  | 2         | 0.57%   |
| AMD A6                  | 2         | 0.57%   |
| Intel Pentium Silver    | 1         | 0.28%   |
| Intel Pentium M         | 1         | 0.28%   |
| Intel Pentium Gold      | 1         | 0.28%   |
| Intel Pentium Dual      | 1         | 0.28%   |
| Intel Genuine           | 1         | 0.28%   |
| Intel Core i9           | 1         | 0.28%   |
| Intel Celeron M         | 1         | 0.28%   |
| AMD Ryzen 9             | 1         | 0.28%   |
| AMD Ryzen 7 PRO         | 1         | 0.28%   |
| AMD Ryzen 5 PRO         | 1         | 0.28%   |
| AMD A4                  | 1         | 0.28%   |
| AMD A10                 | 1         | 0.28%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 198       | 56.41%  |
| 4      | 107       | 30.48%  |
| 8      | 14        | 3.99%   |
| 6      | 11        | 3.13%   |
| 1      | 6         | 1.71%   |
| 14     | 5         | 1.42%   |
| 10     | 5         | 1.42%   |
| 16     | 2         | 0.57%   |
| 12     | 2         | 0.57%   |
| 24     | 1         | 0.28%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 351       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 285       | 81.2%   |
| 1      | 66        | 18.8%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 346       | 98.58%  |
| 32-bit         | 3         | 0.85%   |
| Unknown        | 2         | 0.57%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 191       | 52.91%  |
| 0x206a7    | 20        | 5.54%   |
| 0x306d4    | 14        | 3.88%   |
| 0x806ea    | 12        | 3.32%   |
| 0x40651    | 12        | 3.32%   |
| 0x806ec    | 9         | 2.49%   |
| 0x306c3    | 9         | 2.49%   |
| 0x306a9    | 9         | 2.49%   |
| 0x20655    | 9         | 2.49%   |
| 0x806c1    | 7         | 1.94%   |
| 0x406e3    | 7         | 1.94%   |
| 0x1067a    | 6         | 1.66%   |
| 0x806e9    | 5         | 1.39%   |
| 0x6fd      | 5         | 1.39%   |
| 0x20652    | 5         | 1.39%   |
| 0x506e3    | 4         | 1.11%   |
| 0x30678    | 4         | 1.11%   |
| 0x0a50000c | 3         | 0.83%   |
| 0x906ea    | 2         | 0.55%   |
| 0x406c4    | 2         | 0.55%   |
| 0x406c3    | 2         | 0.55%   |
| 0x10676    | 2         | 0.55%   |
| 0x07030105 | 2         | 0.55%   |
| 0x0700010f | 2         | 0.55%   |
| 0xb06a3    | 1         | 0.28%   |
| 0x906e9    | 1         | 0.28%   |
| 0x806eb    | 1         | 0.28%   |
| 0x806d1    | 1         | 0.28%   |
| 0x706e5    | 1         | 0.28%   |
| 0x706a1    | 1         | 0.28%   |
| 0x6ec      | 1         | 0.28%   |
| 0x6e8      | 1         | 0.28%   |
| 0x6d8      | 1         | 0.28%   |
| 0x30673    | 1         | 0.28%   |
| 0x30661    | 1         | 0.28%   |
| 0x08108109 | 1         | 0.28%   |
| 0x08108102 | 1         | 0.28%   |
| 0x06006705 | 1         | 0.28%   |
| 0x06001119 | 1         | 0.28%   |
| 0x05000119 | 1         | 0.28%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 63        | 17.95%  |
| Haswell          | 43        | 12.25%  |
| Skylake          | 30        | 8.55%   |
| SandyBridge      | 29        | 8.26%   |
| Westmere         | 25        | 7.12%   |
| Broadwell        | 23        | 6.55%   |
| TigerLake        | 21        | 5.98%   |
| Unknown          | 21        | 5.98%   |
| IvyBridge        | 16        | 4.56%   |
| Silvermont       | 14        | 3.99%   |
| Penryn           | 12        | 3.42%   |
| Core             | 9         | 2.56%   |
| Alderlake Hybrid | 7         | 1.99%   |
| IceLake          | 6         | 1.71%   |
| Zen+             | 4         | 1.14%   |
| Zen 3            | 4         | 1.14%   |
| P6               | 3         | 0.85%   |
| Bonnell          | 3         | 0.85%   |
| Bobcat           | 3         | 0.85%   |
| Puma             | 2         | 0.57%   |
| Jaguar           | 2         | 0.57%   |
| Goldmont plus    | 2         | 0.57%   |
| Excavator        | 2         | 0.57%   |
| CometLake        | 2         | 0.57%   |
| Zen              | 1         | 0.28%   |
| Piledriver       | 1         | 0.28%   |
| Lunarlake Hybrid | 1         | 0.28%   |
| K10 Llano        | 1         | 0.28%   |
| Goldmont         | 1         | 0.28%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 299       | 67.49%  |
| Nvidia | 92        | 20.77%  |
| AMD    | 52        | 11.74%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 27        | 6.01%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 26        | 5.79%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 24        | 5.35%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 21        | 4.68%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 20        | 4.45%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 19        | 4.23%   |
| Intel Core Processor Integrated Graphics Controller                                      | 19        | 4.23%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 16        | 3.56%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 12        | 2.67%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 11        | 2.45%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 10        | 2.23%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 9         | 2%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 9         | 2%      |
| Intel Skylake-H GT2 [HD Graphics 530]                                                    | 8         | 1.78%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 8         | 1.78%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 6         | 1.34%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 6         | 1.34%   |
| Nvidia GM108M [GeForce 840M]                                                             | 5         | 1.11%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 5         | 1.11%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 1.11%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 1.11%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 0.89%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 4         | 0.89%   |
| Intel Raptor Lake-P [UHD Graphics]                                                       | 4         | 0.89%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 4         | 0.89%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4         | 0.89%   |
| Nvidia TU117M [GeForce MX450]                                                            | 3         | 0.67%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 0.67%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 3         | 0.67%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 3         | 0.67%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                                          | 3         | 0.67%   |
| Nvidia AD106M [GeForce RTX 4070 Max-Q / Mobile]                                          | 3         | 0.67%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 0.67%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 0.67%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 0.67%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 3         | 0.67%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 0.67%   |
| AMD Lucienne                                                                             | 3         | 0.67%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 2         | 0.45%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 0.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 209       | 59.38%  |
| Intel + Nvidia | 74        | 21.02%  |
| 1 x AMD        | 35        | 9.94%   |
| 1 x Nvidia     | 14        | 3.98%   |
| Intel + AMD    | 13        | 3.69%   |
| AMD + Nvidia   | 4         | 1.14%   |
| 2 x Intel      | 3         | 0.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 294       | 81.89%  |
| Proprietary | 40        | 11.14%  |
| Unknown     | 25        | 6.96%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 279       | 77.5%   |
| 1.01-2.0   | 32        | 8.89%   |
| 0.01-0.5   | 26        | 7.22%   |
| 3.01-4.0   | 11        | 3.06%   |
| 0.51-1.0   | 10        | 2.78%   |
| 7.01-8.0   | 1         | 0.28%   |
| 2.01-3.0   | 1         | 0.28%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 66        | 18.38%  |
| LG Display              | 62        | 17.27%  |
| Chimei Innolux          | 61        | 16.99%  |
| BOE                     | 58        | 16.16%  |
| Samsung Electronics     | 43        | 11.98%  |
| InfoVision              | 10        | 2.79%   |
| Lenovo                  | 8         | 2.23%   |
| Hewlett-Packard         | 7         | 1.95%   |
| Apple                   | 7         | 1.95%   |
| Sharp                   | 6         | 1.67%   |
| Chi Mei Optoelectronics | 6         | 1.67%   |
| LG Philips              | 5         | 1.39%   |
| Dell                    | 4         | 1.11%   |
| HannStar                | 3         | 0.84%   |
| PANDA                   | 2         | 0.56%   |
| MSI                     | 2         | 0.56%   |
| Valve                   | 1         | 0.28%   |
| TMX                     | 1         | 0.28%   |
| TCL                     | 1         | 0.28%   |
| Sony                    | 1         | 0.28%   |
| NCS                     | 1         | 0.28%   |
| LGD                     | 1         | 0.28%   |
| IBM                     | 1         | 0.28%   |
| Goldstar                | 1         | 0.28%   |
| CNC                     | 1         | 0.28%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 5         | 1.39%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 4         | 1.11%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 4         | 1.11%   |
| Samsung Electronics LCD Monitor SEC3642 1366x768 344x194mm 15.5-inch     | 3         | 0.83%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 3         | 0.83%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x193mm 15.5-inch          | 3         | 0.83%   |
| Chimei Innolux LCD Monitor CMN14E7 1920x1080 309x173mm 13.9-inch         | 3         | 0.83%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 3         | 0.83%   |
| Chimei Innolux LCD Monitor CMN14A3 1600x900 309x174mm 14.0-inch          | 3         | 0.83%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                    | 3         | 0.83%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                     | 3         | 0.83%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 3         | 0.83%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 3         | 0.83%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 2         | 0.55%   |
| Samsung Electronics LCD Monitor SDC4D42 1366x768 309x174mm 14.0-inch     | 2         | 0.55%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 2         | 0.55%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch             | 2         | 0.55%   |
| LG Display LCD Monitor LGD0504 1366x768 340x190mm 15.3-inch              | 2         | 0.55%   |
| LG Display LCD Monitor LGD03D9 1366x768 345x194mm 15.6-inch              | 2         | 0.55%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 2         | 0.55%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 2         | 0.55%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1080 518x324mm 24.1-inch               | 2         | 0.55%   |
| InfoVision LCD Monitor IVO057F 1920x1080 309x174mm 14.0-inch             | 2         | 0.55%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch             | 2         | 0.55%   |
| Dell 2208WFP DEL403B 1680x1050 473x296mm 22.0-inch                       | 2         | 0.55%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 2         | 0.55%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 0.55%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch         | 2         | 0.55%   |
| Chimei Innolux LCD Monitor CMN15B7 1366x768 344x193mm 15.5-inch          | 2         | 0.55%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 2         | 0.55%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 2         | 0.55%   |
| Chimei Innolux LCD Monitor CMN1343 1920x1080 282x165mm 12.9-inch         | 2         | 0.55%   |
| Chi Mei Optoelectronics LCD Monitor CMO1599 1366x768 344x193mm 15.5-inch | 2         | 0.55%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                    | 2         | 0.55%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                    | 2         | 0.55%   |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                     | 2         | 0.55%   |
| BOE LCD Monitor BOE0714 1920x1080 344x193mm 15.5-inch                    | 2         | 0.55%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch            | 2         | 0.55%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 2         | 0.55%   |
| AU Optronics LCD Monitor AUO42EC 1366x768 344x193mm 15.5-inch            | 2         | 0.55%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 144       | 40.91%  |
| 1920x1080 (FHD)    | 119       | 33.81%  |
| 1600x900 (HD+)     | 24        | 6.82%   |
| 1280x800 (WXGA)    | 11        | 3.13%   |
| 1920x1200 (WUXGA)  | 7         | 1.99%   |
| 1440x900 (WXGA+)   | 6         | 1.7%    |
| 3840x2160 (4K)     | 5         | 1.42%   |
| 2560x1440 (QHD)    | 5         | 1.42%   |
| 2560x1600          | 4         | 1.14%   |
| 1680x1050 (WSXGA+) | 4         | 1.14%   |
| 1024x600           | 4         | 1.14%   |
| 1280x1024 (SXGA)   | 3         | 0.85%   |
| 2880x1800          | 2         | 0.57%   |
| 2240x1400          | 2         | 0.57%   |
| 1360x768           | 2         | 0.57%   |
| 800x1280           | 1         | 0.28%   |
| 3840x2400          | 1         | 0.28%   |
| 3440x1440          | 1         | 0.28%   |
| 2880x1620          | 1         | 0.28%   |
| 2520x1680          | 1         | 0.28%   |
| 1920x515           | 1         | 0.28%   |
| 1680x945           | 1         | 0.28%   |
| 1400x1050          | 1         | 0.28%   |
| 1024x768 (XGA)     | 1         | 0.28%   |
| Unknown            | 1         | 0.28%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 177       | 49.17%  |
| 14      | 51        | 14.17%  |
| 13      | 51        | 14.17%  |
| 17      | 20        | 5.56%   |
| 12      | 16        | 4.44%   |
| 18      | 6         | 1.67%   |
| 16      | 5         | 1.39%   |
| 23      | 4         | 1.11%   |
| 11      | 4         | 1.11%   |
| 24      | 3         | 0.83%   |
| 22      | 3         | 0.83%   |
| 10      | 3         | 0.83%   |
| Unknown | 3         | 0.83%   |
| 34      | 2         | 0.56%   |
| 31      | 2         | 0.56%   |
| 21      | 2         | 0.56%   |
| 19      | 2         | 0.56%   |
| 84      | 1         | 0.28%   |
| 54      | 1         | 0.28%   |
| 32      | 1         | 0.28%   |
| 27      | 1         | 0.28%   |
| 20      | 1         | 0.28%   |
| 7       | 1         | 0.28%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 259       | 72.55%  |
| 201-300     | 44        | 12.32%  |
| 351-400     | 24        | 6.72%   |
| 401-500     | 11        | 3.08%   |
| 501-600     | 8         | 2.24%   |
| 701-800     | 3         | 0.84%   |
| Unknown     | 3         | 0.84%   |
| 601-700     | 2         | 0.56%   |
| 1501-2000   | 1         | 0.28%   |
| 1001-1500   | 1         | 0.28%   |
| 1-100       | 1         | 0.28%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 296       | 85.06%  |
| 16/10   | 39        | 11.21%  |
| 5/4     | 3         | 0.86%   |
| 4/3     | 3         | 0.86%   |
| 3/2     | 2         | 0.57%   |
| Unknown | 2         | 0.57%   |
| 3.73    | 1         | 0.29%   |
| 21/9    | 1         | 0.29%   |
| 0.67    | 1         | 0.29%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 176       | 49.03%  |
| 81-90          | 85        | 23.68%  |
| 71-80          | 15        | 4.18%   |
| 61-70          | 15        | 4.18%   |
| 121-130        | 15        | 4.18%   |
| 201-250        | 9         | 2.51%   |
| 141-150        | 7         | 1.95%   |
| 111-120        | 6         | 1.67%   |
| 51-60          | 4         | 1.11%   |
| 351-500        | 4         | 1.11%   |
| 151-200        | 4         | 1.11%   |
| 41-50          | 3         | 0.84%   |
| 131-140        | 3         | 0.84%   |
| 91-100         | 3         | 0.84%   |
| Unknown        | 3         | 0.84%   |
| More than 1000 | 2         | 0.56%   |
| 251-300        | 2         | 0.56%   |
| 1-40           | 1         | 0.28%   |
| 301-350        | 1         | 0.28%   |
| 501-1000       | 1         | 0.28%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 144       | 40.45%  |
| 121-160       | 132       | 37.08%  |
| 51-100        | 40        | 11.24%  |
| 161-240       | 32        | 8.99%   |
| More than 240 | 4         | 1.12%   |
| Unknown       | 3         | 0.84%   |
| 1-50          | 1         | 0.28%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 320       | 90.14%  |
| 2     | 25        | 7.04%   |
| 0     | 9         | 2.54%   |
| 3     | 1         | 0.28%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 196       | 36.23%  |
| Realtek Semiconductor    | 150       | 27.73%  |
| Qualcomm Atheros         | 69        | 12.75%  |
| Broadcom                 | 52        | 9.61%   |
| Ralink Technology        | 15        | 2.77%   |
| Ralink                   | 9         | 1.66%   |
| MediaTek                 | 8         | 1.48%   |
| Sierra Wireless          | 7         | 1.29%   |
| Broadcom Limited         | 6         | 1.11%   |
| Dell                     | 5         | 0.92%   |
| Samsung Electronics      | 4         | 0.74%   |
| Marvell Technology Group | 4         | 0.74%   |
| Xiaomi                   | 3         | 0.55%   |
| Qualcomm                 | 3         | 0.55%   |
| TP-Link                  | 2         | 0.37%   |
| Lenovo                   | 2         | 0.37%   |
| JMicron Technology       | 2         | 0.37%   |
| Nvidia                   | 1         | 0.18%   |
| Huawei Technologies      | 1         | 0.18%   |
| D-Link                   | 1         | 0.18%   |
| Arduino SA               | 1         | 0.18%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 97        | 13.98%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 30        | 4.32%   |
| Intel Wireless 8265 / 8275                                             | 26        | 3.75%   |
| Intel Wireless 8260                                                    | 21        | 3.03%   |
| Intel Ethernet Connection (4) I219-LM                                  | 16        | 2.31%   |
| Intel Wireless 7265                                                    | 14        | 2.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 14        | 2.02%   |
| Intel 82577LM Gigabit Network Connection                               | 14        | 2.02%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 13        | 1.87%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 13        | 1.87%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 12        | 1.73%   |
| Ralink MT7601U Wireless Adapter                                        | 12        | 1.73%   |
| Intel Wi-Fi 6 AX201                                                    | 12        | 1.73%   |
| Intel Ethernet Connection I219-LM                                      | 12        | 1.73%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 11        | 1.59%   |
| Intel Centrino Advanced-N 6200                                         | 11        | 1.59%   |
| Broadcom BCM43142 802.11b/g/n                                          | 11        | 1.59%   |
| Intel Ethernet Connection (3) I218-LM                                  | 10        | 1.44%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 10        | 1.44%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 9         | 1.3%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 9         | 1.3%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 9         | 1.3%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 8         | 1.15%   |
| Intel Wireless 7260                                                    | 8         | 1.15%   |
| Intel Ethernet Connection I218-LM                                      | 8         | 1.15%   |
| Intel Ethernet Connection I217-LM                                      | 8         | 1.15%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 7         | 1.01%   |
| Intel Ethernet Connection (2) I219-LM                                  | 7         | 1.01%   |
| Broadcom BCM43228 802.11a/b/g/n                                        | 7         | 1.01%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 6         | 0.86%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 6         | 0.86%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 6         | 0.86%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 6         | 0.86%   |
| Intel Wi-Fi 6 AX200                                                    | 6         | 0.86%   |
| Intel Centrino Advanced-N 6235                                         | 6         | 0.86%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 6         | 0.86%   |
| Intel Centrino Ultimate-N 6300                                         | 5         | 0.72%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 5         | 0.72%   |
| Sierra Wireless EM7455                                                 | 4         | 0.58%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 4         | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 179       | 47.99%  |
| Qualcomm Atheros      | 63        | 16.89%  |
| Realtek Semiconductor | 39        | 10.46%  |
| Broadcom              | 39        | 10.46%  |
| Ralink Technology     | 15        | 4.02%   |
| Ralink                | 9         | 2.41%   |
| Sierra Wireless       | 7         | 1.88%   |
| MediaTek              | 7         | 1.88%   |
| Broadcom Limited      | 6         | 1.61%   |
| Dell                  | 4         | 1.07%   |
| TP-Link               | 2         | 0.54%   |
| Qualcomm              | 2         | 0.54%   |
| D-Link                | 1         | 0.27%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                           | 26        | 6.93%   |
| Intel Wireless 8260                                                  | 21        | 5.6%    |
| Intel Wireless 7265                                                  | 14        | 3.73%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 13        | 3.47%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 13        | 3.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 12        | 3.2%    |
| Ralink MT7601U Wireless Adapter                                      | 12        | 3.2%    |
| Intel Wi-Fi 6 AX201                                                  | 12        | 3.2%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 11        | 2.93%   |
| Intel Centrino Advanced-N 6200                                       | 11        | 2.93%   |
| Broadcom BCM43142 802.11b/g/n                                        | 11        | 2.93%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 10        | 2.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 9         | 2.4%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 9         | 2.4%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 9         | 2.4%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 8         | 2.13%   |
| Intel Wireless 7260                                                  | 8         | 2.13%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 7         | 1.87%   |
| Broadcom BCM43228 802.11a/b/g/n                                      | 7         | 1.87%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 6         | 1.6%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 6         | 1.6%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                            | 6         | 1.6%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 6         | 1.6%    |
| Intel Wi-Fi 6 AX200                                                  | 6         | 1.6%    |
| Intel Centrino Advanced-N 6235                                       | 6         | 1.6%    |
| Intel Cannon Lake PCH CNVi WiFi                                      | 6         | 1.6%    |
| Intel Centrino Ultimate-N 6300                                       | 5         | 1.33%   |
| Sierra Wireless EM7455                                               | 4         | 1.07%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330] | 4         | 1.07%   |
| Intel WiFi Link 5100                                                 | 4         | 1.07%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 4         | 1.07%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 3         | 0.8%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                | 3         | 0.8%    |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 3         | 0.8%    |
| Dell DW5811e Snapdragon X7 LTE                                       | 3         | 0.8%    |
| Broadcom BCM4331 802.11a/b/g/n                                       | 3         | 0.8%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 2         | 0.53%   |
| Realtek RTL8723DE Wireless Network Adapter                           | 2         | 0.53%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                           | 2         | 0.53%   |
| Ralink RT5370 Wireless Adapter                                       | 2         | 0.53%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 136       | 43.73%  |
| Intel                    | 122       | 39.23%  |
| Broadcom                 | 19        | 6.11%   |
| Qualcomm Atheros         | 14        | 4.5%    |
| Samsung Electronics      | 4         | 1.29%   |
| Marvell Technology Group | 4         | 1.29%   |
| Xiaomi                   | 3         | 0.96%   |
| Lenovo                   | 2         | 0.64%   |
| JMicron Technology       | 2         | 0.64%   |
| Qualcomm                 | 1         | 0.32%   |
| Nvidia                   | 1         | 0.32%   |
| MediaTek                 | 1         | 0.32%   |
| Huawei Technologies      | 1         | 0.32%   |
| Broadcom Limited         | 1         | 0.32%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 97        | 30.7%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 30        | 9.49%   |
| Intel Ethernet Connection (4) I219-LM                                  | 16        | 5.06%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 14        | 4.43%   |
| Intel 82577LM Gigabit Network Connection                               | 14        | 4.43%   |
| Intel Ethernet Connection I219-LM                                      | 12        | 3.8%    |
| Intel Ethernet Connection (3) I218-LM                                  | 10        | 3.16%   |
| Intel Ethernet Connection I218-LM                                      | 8         | 2.53%   |
| Intel Ethernet Connection I217-LM                                      | 8         | 2.53%   |
| Intel Ethernet Connection (2) I219-LM                                  | 7         | 2.22%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 4         | 1.27%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 4         | 1.27%   |
| Intel Ethernet Connection I217-V                                       | 4         | 1.27%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 4         | 1.27%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 3         | 0.95%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 3         | 0.95%   |
| Intel Ethernet Connection (6) I219-LM                                  | 3         | 0.95%   |
| Intel Ethernet Connection (4) I219-V                                   | 3         | 0.95%   |
| Intel Ethernet Connection (13) I219-LM                                 | 3         | 0.95%   |
| Intel Ethernet Connection (10) I219-LM                                 | 3         | 0.95%   |
| Intel 82579V Gigabit Network Connection                                | 3         | 0.95%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 3         | 0.95%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 2         | 0.63%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2         | 0.63%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 2         | 0.63%   |
| Realtek RTL8125 2.5GbE Controller                                      | 2         | 0.63%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 2         | 0.63%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 2         | 0.63%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2         | 0.63%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                | 2         | 0.63%   |
| Lenovo ThinkPad TBT 3 Dock                                             | 2         | 0.63%   |
| Intel Ethernet Connection (7) I219-LM                                  | 2         | 0.63%   |
| Intel Ethernet Connection (16) I219-LM                                 | 2         | 0.63%   |
| Intel Ethernet Connection (13) I219-V                                  | 2         | 0.63%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 2         | 0.63%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 2         | 0.63%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                | 2         | 0.63%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                        | 2         | 0.63%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 0.32%   |
| Qualcomm Nokia X30 5G                                                  | 1         | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 345       | 53.32%  |
| Ethernet | 299       | 46.21%  |
| Modem    | 3         | 0.46%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 301       | 84.79%  |
| Ethernet | 54        | 15.21%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 289       | 82.1%   |
| 1     | 55        | 15.63%  |
| 0     | 6         | 1.7%    |
| 7     | 1         | 0.28%   |
| 3     | 1         | 0.28%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 350       | 99.72%  |
| Yes  | 1         | 0.28%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 131       | 49.43%  |
| Realtek Semiconductor           | 28        | 10.57%  |
| Qualcomm Atheros Communications | 23        | 8.68%   |
| Broadcom                        | 16        | 6.04%   |
| Lite-On Technology              | 10        | 3.77%   |
| IMC Networks                    | 9         | 3.4%    |
| Foxconn / Hon Hai               | 9         | 3.4%    |
| Dell                            | 8         | 3.02%   |
| Hewlett-Packard                 | 7         | 2.64%   |
| Ralink                          | 6         | 2.26%   |
| Apple                           | 6         | 2.26%   |
| Toshiba                         | 3         | 1.13%   |
| Cambridge Silicon Radio         | 2         | 0.75%   |
| USI                             | 1         | 0.38%   |
| Ralink Technology               | 1         | 0.38%   |
| Foxconn International           | 1         | 0.38%   |
| ASUSTek Computer                | 1         | 0.38%   |
| Askey Computer                  | 1         | 0.38%   |
| Alps Electric                   | 1         | 0.38%   |
| Actions                         | 1         | 0.38%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 62        | 23.4%   |
| Intel AX201 Bluetooth                               | 25        | 9.43%   |
| Realtek Bluetooth Radio                             | 16        | 6.04%   |
| Intel Bluetooth Device                              | 12        | 4.53%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 12        | 4.53%   |
| Qualcomm Atheros  Bluetooth Device                  | 11        | 4.15%   |
| Realtek  Bluetooth 4.2 Adapter                      | 7         | 2.64%   |
| IMC Networks Bluetooth Device                       | 7         | 2.64%   |
| Ralink RT3290 Bluetooth                             | 6         | 2.26%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 6         | 2.26%   |
| Intel AX200 Bluetooth                               | 6         | 2.26%   |
| HP Broadcom 2070 Bluetooth Combo                    | 6         | 2.26%   |
| Dell DW375 Bluetooth Module                         | 5         | 1.89%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 5         | 1.89%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 4         | 1.51%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 4         | 1.51%   |
| Intel Wireless-AC 3168 Bluetooth                    | 4         | 1.51%   |
| Broadcom HP Portable Bumble Bee                     | 4         | 1.51%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 3         | 1.13%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 1.13%   |
| Apple Bluetooth USB Host Controller                 | 3         | 1.13%   |
| Toshiba Bluetooth Device                            | 2         | 0.75%   |
| Realtek RTL8821A Bluetooth                          | 2         | 0.75%   |
| Realtek RTL8723B Bluetooth                          | 2         | 0.75%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 2         | 0.75%   |
| Lite-On Bluetooth Device                            | 2         | 0.75%   |
| Intel AX210 Bluetooth                               | 2         | 0.75%   |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 0.75%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 2         | 0.75%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 0.75%   |
| Dell Wireless 360 Bluetooth                         | 2         | 0.75%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 0.75%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 0.75%   |
| Apple Bluetooth Host Controller                     | 2         | 0.75%   |
| USI Bluetooth Device                                | 1         | 0.38%   |
| Toshiba Askey Bluetooth Module                      | 1         | 0.38%   |
| Realtek CSR BS8510                                  | 1         | 0.38%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.38%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 0.38%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 316       | 75.6%   |
| Nvidia                           | 52        | 12.44%  |
| AMD                              | 39        | 9.33%   |
| Lenovo                           | 2         | 0.48%   |
| GN Netcom                        | 2         | 0.48%   |
| Walmart                          | 1         | 0.24%   |
| Silicon Integrated Systems [SiS] | 1         | 0.24%   |
| Nordic Semiconductor ASA         | 1         | 0.24%   |
| Logitech                         | 1         | 0.24%   |
| Generalplus Technology           | 1         | 0.24%   |
| Focusrite-Novation               | 1         | 0.24%   |
| ASUSTek Computer                 | 1         | 0.24%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 54        | 10.69%  |
| Intel Haswell-ULT HD Audio Controller                                                             | 28        | 5.54%   |
| Intel 8 Series HD Audio Controller                                                                | 28        | 5.54%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 25        | 4.95%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 25        | 4.95%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 23        | 4.55%   |
| Intel Broadwell-U Audio Controller                                                                | 23        | 4.55%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 21        | 4.16%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 20        | 3.96%   |
| AMD Ryzen HD Audio Controller                                                                     | 17        | 3.37%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 15        | 2.97%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 14        | 2.77%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 11        | 2.18%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 11        | 2.18%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 10        | 1.98%   |
| Intel Cannon Lake PCH cAVS                                                                        | 10        | 1.98%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 10        | 1.98%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 8         | 1.58%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 1.39%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 6         | 1.19%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                       | 6         | 1.19%   |
| AMD FCH Azalia Controller                                                                         | 6         | 1.19%   |
| Nvidia GA107 High Definition Audio Controller                                                     | 5         | 0.99%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 5         | 0.99%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 0.99%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 5         | 0.99%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 0.99%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 0.99%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 4         | 0.79%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 4         | 0.79%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 4         | 0.79%   |
| Nvidia AD107 High Definition Audio Controller                                                     | 4         | 0.79%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 0.79%   |
| AMD Radeon High Definition Audio Controller                                                       | 4         | 0.79%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.59%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 3         | 0.59%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 0.59%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 0.59%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 3         | 0.59%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 0.4%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 74        | 32.03%  |
| SK hynix            | 58        | 25.11%  |
| Micron Technology   | 33        | 14.29%  |
| Kingston            | 22        | 9.52%   |
| Unknown             | 9         | 3.9%    |
| Ramaxel Technology  | 6         | 2.6%    |
| A-DATA Technology   | 6         | 2.6%    |
| Elpida              | 5         | 2.16%   |
| Crucial             | 5         | 2.16%   |
| Nanya Technology    | 3         | 1.3%    |
| Transcend           | 2         | 0.87%   |
| Sesame              | 2         | 0.87%   |
| ASint Technology    | 2         | 0.87%   |
| Unknown (83DA)      | 1         | 0.43%   |
| Unknown (0B85)      | 1         | 0.43%   |
| Toshiba             | 1         | 0.43%   |
| Qimonda             | 1         | 0.43%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 5         | 2.02%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1600MT/s       | 4         | 1.62%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                | 3         | 1.21%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 3         | 1.21%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s      | 3         | 1.21%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s      | 3         | 1.21%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 3         | 1.21%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s                 | 3         | 1.21%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s       | 3         | 1.21%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s       | 3         | 1.21%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s       | 3         | 1.21%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s       | 3         | 1.21%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s       | 3         | 1.21%   |
| Kingston RAM HP16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s       | 3         | 1.21%   |
| Unknown RAM Module 2GB SODIMM DDR2                          | 2         | 0.81%   |
| Transcend RAM JM1333KSN-4G 4GB SODIMM DDR3 1334MT/s         | 2         | 0.81%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 2         | 0.81%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 2667MT/s      | 2         | 0.81%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s     | 2         | 0.81%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s      | 2         | 0.81%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s      | 2         | 0.81%   |
| Sesame RAM S939A2SGS-ITR 8GB SODIMM DDR4 2667MT/s           | 2         | 0.81%   |
| Samsung RAM M471B5773EB0-CK0 2048MB SODIMM DDR3 1600MT/s    | 2         | 0.81%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s       | 2         | 0.81%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s       | 2         | 0.81%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s    | 2         | 0.81%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s       | 2         | 0.81%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s      | 2         | 0.81%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s      | 2         | 0.81%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 3200MT/s       | 2         | 0.81%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 8400MT/s       | 2         | 0.81%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s       | 2         | 0.81%   |
| Samsung RAM M471A1K43BB0-CPB 8GiB SODIMM DDR4 2133MT/s      | 2         | 0.81%   |
| Samsung RAM M471A1G44AB0-CWE 8GiB SODIMM DDR4 3200MT/s      | 2         | 0.81%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s | 2         | 0.81%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s     | 2         | 0.81%   |
| Micron RAM 8KTF51264HZ-1G9P1 4GB SODIMM DDR3 1867MT/s       | 2         | 0.81%   |
| Micron RAM 8KTF51264HZ-1G6P1 4GB SODIMM DDR3 1600MT/s       | 2         | 0.81%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s        | 2         | 0.81%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s       | 2         | 0.81%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 80        | 42.55%  |
| DDR4    | 79        | 42.02%  |
| DDR2    | 7         | 3.72%   |
| LPDDR5  | 5         | 2.66%   |
| DDR5    | 5         | 2.66%   |
| LPDDR4  | 4         | 2.13%   |
| SDRAM   | 3         | 1.6%    |
| LPDDR3  | 3         | 1.6%    |
| Unknown | 2         | 1.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 170       | 91.4%   |
| Row Of Chips | 13        | 6.99%   |
| Unknown      | 2         | 1.08%   |
| DIMM         | 1         | 0.54%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 79        | 37.62%  |
| 4096  | 70        | 33.33%  |
| 16384 | 26        | 12.38%  |
| 2048  | 24        | 11.43%  |
| 32768 | 5         | 2.38%   |
| 1024  | 5         | 2.38%   |
| 12288 | 1         | 0.48%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 52        | 25.62%  |
| 2667    | 37        | 18.23%  |
| 3200    | 35        | 17.24%  |
| 2400    | 11        | 5.42%   |
| 1334    | 11        | 5.42%   |
| 2133    | 10        | 4.93%   |
| 1333    | 7         | 3.45%   |
| 1067    | 5         | 2.46%   |
| Unknown | 5         | 2.46%   |
| 4800    | 4         | 1.97%   |
| 8400    | 3         | 1.48%   |
| 3266    | 3         | 1.48%   |
| 6400    | 2         | 0.99%   |
| 4199    | 2         | 0.99%   |
| 1867    | 2         | 0.99%   |
| 1066    | 2         | 0.99%   |
| 975     | 2         | 0.99%   |
| 800     | 2         | 0.99%   |
| 667     | 2         | 0.99%   |
| 8533    | 1         | 0.49%   |
| 7500    | 1         | 0.49%   |
| 7467    | 1         | 0.49%   |
| 5600    | 1         | 0.49%   |
| 4267    | 1         | 0.49%   |
| 2048    | 1         | 0.49%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| HP LaserJet 1018 | 1         | 100%    |

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
| Chicony Electronics                    | 86        | 28.01%  |
| IMC Networks                           | 29        | 9.45%   |
| Realtek Semiconductor                  | 25        | 8.14%   |
| Cheng Uei Precision Industry (Foxlink) | 22        | 7.17%   |
| Sunplus Innovation Technology          | 19        | 6.19%   |
| Lite-On Technology                     | 18        | 5.86%   |
| Quanta                                 | 16        | 5.21%   |
| Microdia                               | 16        | 5.21%   |
| Suyin                                  | 14        | 4.56%   |
| Bison Electronics                      | 11        | 3.58%   |
| Syntek                                 | 7         | 2.28%   |
| Luxvisions Innotech Limited            | 7         | 2.28%   |
| Apple                                  | 6         | 1.95%   |
| Ricoh                                  | 4         | 1.3%    |
| Alcor Micro                            | 4         | 1.3%    |
| Z-Star Microelectronics                | 3         | 0.98%   |
| Sonix Technology                       | 2         | 0.65%   |
| Silicon Motion                         | 2         | 0.65%   |
| ShineTech                              | 2         | 0.65%   |
| Samsung Electronics                    | 2         | 0.65%   |
| ALi                                    | 2         | 0.65%   |
| Sunplus Technology                     | 1         | 0.33%   |
| Primax Electronics                     | 1         | 0.33%   |
| OPPO Electronics                       | 1         | 0.33%   |
| OmniVision Technologies                | 1         | 0.33%   |
| Nebraska Furniture Mart                | 1         | 0.33%   |
| Logitech                               | 1         | 0.33%   |
| LG Innotek                             | 1         | 0.33%   |
| Lenovo                                 | 1         | 0.33%   |
| icSpring                               | 1         | 0.33%   |
| Acer                                   | 1         | 0.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 16        | 5.18%   |
| IMC Networks Integrated Camera                              | 10        | 3.24%   |
| Realtek Integrated_Webcam_HD                                | 8         | 2.59%   |
| Lite-On HP HD Camera                                        | 8         | 2.59%   |
| Sunplus Integrated_Webcam_HD                                | 7         | 2.27%   |
| Chicony HP Webcam [2 MP Macro]                              | 6         | 1.94%   |
| Chicony HP Webcam                                           | 6         | 1.94%   |
| Chicony HP HD Camera                                        | 6         | 1.94%   |
| Microdia Integrated_Webcam_HD                               | 5         | 1.62%   |
| Microdia Integrated Webcam                                  | 5         | 1.62%   |
| Lite-On HP HD Webcam                                        | 5         | 1.62%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 5         | 1.62%   |
| Chicony HD WebCam                                           | 5         | 1.62%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera         | 5         | 1.62%   |
| Bison Integrated Camera                                     | 5         | 1.62%   |
| Sunplus Laptop_Integrated_Webcam_FHD                        | 4         | 1.29%   |
| Realtek USB Camera                                          | 4         | 1.29%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam         | 4         | 1.29%   |
| Syntek Lenovo EasyCamera                                    | 3         | 0.97%   |
| Quanta HP Wide Vision HD Camera                             | 3         | 0.97%   |
| Quanta HP HD Camera                                         | 3         | 0.97%   |
| Quanta HD WebCam                                            | 3         | 0.97%   |
| Luxvisions Innotech Limited Integrated Camera               | 3         | 0.97%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 3         | 0.97%   |
| IMC Networks Lenovo EasyCamera                              | 3         | 0.97%   |
| IMC Networks HP TrueVision HD Camera                        | 3         | 0.97%   |
| Chicony USB2.0 HD UVC WebCam                                | 3         | 0.97%   |
| Chicony TOSHIBA Web Camera - HD                             | 3         | 0.97%   |
| Chicony Integrated Camera (1280x720@30)                     | 3         | 0.97%   |
| Chicony HP Wide Vision HD Camera                            | 3         | 0.97%   |
| Chicony HP HD Webcam [Fixed]                                | 3         | 0.97%   |
| Chicony HP HD Webcam                                        | 3         | 0.97%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD     | 3         | 0.97%   |
| Alcor Micro USB 2.0 Camera                                  | 3         | 0.97%   |
| Syntek Integrated Camera                                    | 2         | 0.65%   |
| Syntek EasyCamera                                           | 2         | 0.65%   |
| Suyin Sony Visual Communication Camera                      | 2         | 0.65%   |
| Suyin HP TrueVision HD Integrated Webcam                    | 2         | 0.65%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 2         | 0.65%   |
| Sunplus HP Universal Camera                                 | 2         | 0.65%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 41        | 62.12%  |
| Synaptics                  | 14        | 21.21%  |
| Shenzhen Goodix Technology | 4         | 6.06%   |
| Elan Microelectronics      | 4         | 6.06%   |
| Upek                       | 2         | 3.03%   |
| Focal-systems.Corp         | 1         | 1.52%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 14        | 21.21%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 12.12%  |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 9.09%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 6         | 9.09%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 6         | 9.09%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 4.55%   |
| Validity Sensors VFS491                                                    | 2         | 3.03%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 3.03%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 3.03%   |
| Synaptics UWP WBDI Device                                                  | 2         | 3.03%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 2         | 3.03%   |
| Shenzhen Goodix  Fingerprint Device                                        | 2         | 3.03%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 3.03%   |
| Elan ELAN:Fingerprint                                                      | 2         | 3.03%   |
| Elan ELAN:ARM-M4                                                           | 2         | 3.03%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 1.52%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 1.52%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.52%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 1.52%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 1.52%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 30        | 62.5%   |
| Alcor Micro | 13        | 27.08%  |
| O2 Micro    | 4         | 8.33%   |
| Lenovo      | 1         | 2.08%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
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


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 202       | 55.34%  |
| 1     | 125       | 34.25%  |
| 2     | 33        | 9.04%   |
| 3     | 3         | 0.82%   |
| 5     | 2         | 0.55%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 66        | 32.51%  |
| Graphics card            | 45        | 22.17%  |
| Chipcard                 | 40        | 19.7%   |
| Net/wireless             | 15        | 7.39%   |
| Storage                  | 7         | 3.45%   |
| Bluetooth                | 7         | 3.45%   |
| Camera                   | 6         | 2.96%   |
| Communication controller | 5         | 2.46%   |
| Multimedia controller    | 4         | 1.97%   |
| Sound                    | 3         | 1.48%   |
| Net/ethernet             | 2         | 0.99%   |
| Unassigned class         | 1         | 0.49%   |
| Network                  | 1         | 0.49%   |
| Modem                    | 1         | 0.49%   |

