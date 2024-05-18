Kubuntu 22.04 - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Kubuntu 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Kubuntu_22.04/Desktop/README.md) and [notebooks](/Dist/Kubuntu_22.04/Notebook/README.md).

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

Total: 1983

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | Dev One Notebook PC         | Notebook    | [095bc08ae2](https://linux-hardware.org/?probe=095bc08ae2) | May 09, 2024 |
| ASUSTek       | N61Vn                       | Notebook    | [07f83fc6c0](https://linux-hardware.org/?probe=07f83fc6c0) | May 08, 2024 |
| Gigabyte      | Z270-HD3P-CF                | Desktop     | [b67da2effc](https://linux-hardware.org/?probe=b67da2effc) | May 08, 2024 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [54f40400ed](https://linux-hardware.org/?probe=54f40400ed) | May 08, 2024 |
| HP            | Laptop 15-bs0xx             | Notebook    | [f0bc418296](https://linux-hardware.org/?probe=f0bc418296) | May 08, 2024 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [9b4c39c111](https://linux-hardware.org/?probe=9b4c39c111) | May 07, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [d7c1c96567](https://linux-hardware.org/?probe=d7c1c96567) | May 07, 2024 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [60ef8abb02](https://linux-hardware.org/?probe=60ef8abb02) | May 07, 2024 |
| Dell          | Latitude E6540              | Notebook    | [634735e1da](https://linux-hardware.org/?probe=634735e1da) | May 06, 2024 |
| Dell          | Vostro 15 3510              | Notebook    | [cd07d15de0](https://linux-hardware.org/?probe=cd07d15de0) | May 06, 2024 |
| ASUSTek       | P5Q                         | Desktop     | [5af3396f04](https://linux-hardware.org/?probe=5af3396f04) | May 05, 2024 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [9c6cf56bbb](https://linux-hardware.org/?probe=9c6cf56bbb) | May 05, 2024 |
| ASUSTek       | N61Vn                       | Notebook    | [5aaf9f4609](https://linux-hardware.org/?probe=5aaf9f4609) | May 05, 2024 |
| ASUSTek       | PN50                        | Mini pc     | [bab451ff6f](https://linux-hardware.org/?probe=bab451ff6f) | May 05, 2024 |
| HP            | 8054                        | Desktop     | [bc7d8e8b56](https://linux-hardware.org/?probe=bc7d8e8b56) | May 04, 2024 |
| Lenovo        | ThinkPad X1 Yoga Gen 8 2... | Convertible | [7dfe52f49a](https://linux-hardware.org/?probe=7dfe52f49a) | May 03, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [40f4c2e910](https://linux-hardware.org/?probe=40f4c2e910) | May 03, 2024 |
| Dell          | 0D881F A05                  | Desktop     | [9dfc8fb5b7](https://linux-hardware.org/?probe=9dfc8fb5b7) | May 03, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [750eaa16c3](https://linux-hardware.org/?probe=750eaa16c3) | May 02, 2024 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [e759e41a51](https://linux-hardware.org/?probe=e759e41a51) | May 01, 2024 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [6486b4f435](https://linux-hardware.org/?probe=6486b4f435) | May 01, 2024 |
| Dell          | Inspiron 3543               | Notebook    | [13549c3c7b](https://linux-hardware.org/?probe=13549c3c7b) | May 01, 2024 |
| Lenovo        | ThinkPad T570 20H9CTO1WW    | Notebook    | [433a701205](https://linux-hardware.org/?probe=433a701205) | Apr 30, 2024 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [4a07e72bf5](https://linux-hardware.org/?probe=4a07e72bf5) | Apr 30, 2024 |
| ASUSTek       | KGPE-D16                    | Desktop     | [f199ccf950](https://linux-hardware.org/?probe=f199ccf950) | Apr 30, 2024 |
| MSI           | MS-7D46                     | Notebook    | [135fa9337a](https://linux-hardware.org/?probe=135fa9337a) | Apr 28, 2024 |
| Dell          | 04GJJT A00                  | Desktop     | [b336911f53](https://linux-hardware.org/?probe=b336911f53) | Apr 28, 2024 |
| Timi          | RedmiBook Pro 14S           | Notebook    | [a330c6b15e](https://linux-hardware.org/?probe=a330c6b15e) | Apr 28, 2024 |
| Acer          | Nitro AN715-51              | Notebook    | [0056e3f773](https://linux-hardware.org/?probe=0056e3f773) | Apr 27, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [86089f64dc](https://linux-hardware.org/?probe=86089f64dc) | Apr 26, 2024 |
| Dell          | Inspiron 1525               | Notebook    | [c609a3560c](https://linux-hardware.org/?probe=c609a3560c) | Apr 26, 2024 |
| HP            | EliteBook 8730w             | Notebook    | [da4db94e97](https://linux-hardware.org/?probe=da4db94e97) | Apr 26, 2024 |
| MSI           | Z790 GAMING PLUS WIFI       | Desktop     | [c1242570d2](https://linux-hardware.org/?probe=c1242570d2) | Apr 25, 2024 |
| Gigabyte      | B75M-D2V                    | Desktop     | [21c055a907](https://linux-hardware.org/?probe=21c055a907) | Apr 25, 2024 |
| Gigabyte      | B365 M AORUS ELITE-CF       | Desktop     | [e89543357b](https://linux-hardware.org/?probe=e89543357b) | Apr 25, 2024 |
| Gigabyte      | G5 MD                       | Notebook    | [09c723ce43](https://linux-hardware.org/?probe=09c723ce43) | Apr 25, 2024 |
| Gigabyte      | G5 MD                       | Notebook    | [4529b157ae](https://linux-hardware.org/?probe=4529b157ae) | Apr 25, 2024 |
| HP            | 829A                        | Mini pc     | [b8f9282a11](https://linux-hardware.org/?probe=b8f9282a11) | Apr 25, 2024 |
| Gigabyte      | B365 M AORUS ELITE-CF       | Desktop     | [91dc4d43de](https://linux-hardware.org/?probe=91dc4d43de) | Apr 25, 2024 |
| ASUSTek       | P5K Premium                 | Desktop     | [9b09b4d8bd](https://linux-hardware.org/?probe=9b09b4d8bd) | Apr 24, 2024 |
| Carbon Sys... | Iridium 16 Pro              | Notebook    | [b35260710f](https://linux-hardware.org/?probe=b35260710f) | Apr 24, 2024 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [1cc02514fd](https://linux-hardware.org/?probe=1cc02514fd) | Apr 23, 2024 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [11d418a07c](https://linux-hardware.org/?probe=11d418a07c) | Apr 22, 2024 |
| Gigabyte      | H310M S2P                   | Desktop     | [80fc55e632](https://linux-hardware.org/?probe=80fc55e632) | Apr 22, 2024 |
| Dell          | 00V62H A01                  | Desktop     | [89c9b39716](https://linux-hardware.org/?probe=89c9b39716) | Apr 22, 2024 |
| HP            | Pavilion g7                 | Notebook    | [b700499e3c](https://linux-hardware.org/?probe=b700499e3c) | Apr 21, 2024 |
| Gigabyte      | Z77-D3H                     | Desktop     | [6808539c26](https://linux-hardware.org/?probe=6808539c26) | Apr 21, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [96c7946b39](https://linux-hardware.org/?probe=96c7946b39) | Apr 20, 2024 |
| Lenovo        | ThinkBook 16 G4+ IAP 21C... | Notebook    | [06f11dee2c](https://linux-hardware.org/?probe=06f11dee2c) | Apr 19, 2024 |
| Dell          | 0HD5W2 A01                  | Desktop     | [47d879fa41](https://linux-hardware.org/?probe=47d879fa41) | Apr 19, 2024 |
| Gigabyte      | H61MA-D3V                   | Desktop     | [ebc9dd41f4](https://linux-hardware.org/?probe=ebc9dd41f4) | Apr 19, 2024 |
| ASUSTek       | X756UXK                     | Notebook    | [c529e5199d](https://linux-hardware.org/?probe=c529e5199d) | Apr 18, 2024 |
| Dell          | 0HD5W2 A01                  | Desktop     | [6074f97307](https://linux-hardware.org/?probe=6074f97307) | Apr 18, 2024 |
| Apple         | MacBookPro11,5              | Notebook    | [52efce758f](https://linux-hardware.org/?probe=52efce758f) | Apr 18, 2024 |
| ASUSTek       | PRIME X299-DELUXE           | Desktop     | [6b14b793c5](https://linux-hardware.org/?probe=6b14b793c5) | Apr 17, 2024 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [78cd7a86b3](https://linux-hardware.org/?probe=78cd7a86b3) | Apr 17, 2024 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | Desktop     | [2dc0b12567](https://linux-hardware.org/?probe=2dc0b12567) | Apr 16, 2024 |
| ASUSTek       | P6T SE                      | Desktop     | [31a598cb35](https://linux-hardware.org/?probe=31a598cb35) | Apr 16, 2024 |
| Maibenben     | MaiBook M                   | Notebook    | [9bf28eb5b5](https://linux-hardware.org/?probe=9bf28eb5b5) | Apr 15, 2024 |
| Lenovo        | ThinkPad W540 20BHS0KY08    | Notebook    | [2628bdee23](https://linux-hardware.org/?probe=2628bdee23) | Apr 15, 2024 |
| HP            | Laptop 15-bs1xx             | Notebook    | [f51e425901](https://linux-hardware.org/?probe=f51e425901) | Apr 15, 2024 |
| HP            | Laptop 15-fd0xxx            | Notebook    | [7674249513](https://linux-hardware.org/?probe=7674249513) | Apr 15, 2024 |
| ASUSTek       | PRIME B650-PLUS             | Desktop     | [bca932a740](https://linux-hardware.org/?probe=bca932a740) | Apr 15, 2024 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [d2060f0dcd](https://linux-hardware.org/?probe=d2060f0dcd) | Apr 14, 2024 |
| AMI           | Intel                       | Desktop     | [d8aa9b61b5](https://linux-hardware.org/?probe=d8aa9b61b5) | Apr 14, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [2b471c5586](https://linux-hardware.org/?probe=2b471c5586) | Apr 14, 2024 |
| Intel         | B250                        | Desktop     | [197e339bcf](https://linux-hardware.org/?probe=197e339bcf) | Apr 14, 2024 |
| Samsung       | 550XDA                      | Notebook    | [2679015030](https://linux-hardware.org/?probe=2679015030) | Apr 12, 2024 |
| HP            | Pavilion x360 Convertibl... | Convertible | [a678b9a33b](https://linux-hardware.org/?probe=a678b9a33b) | Apr 12, 2024 |
| Samsung       | 550XDA                      | Notebook    | [ac02b37e1d](https://linux-hardware.org/?probe=ac02b37e1d) | Apr 12, 2024 |
| HP            | Pavilion x360 Convertibl... | Convertible | [44a31677ab](https://linux-hardware.org/?probe=44a31677ab) | Apr 12, 2024 |
| Acer          | Nitro AN515-43              | Notebook    | [36bf325205](https://linux-hardware.org/?probe=36bf325205) | Apr 12, 2024 |
| AZW           | SER V1.0                    | Mini pc     | [3173fd0ebe](https://linux-hardware.org/?probe=3173fd0ebe) | Apr 12, 2024 |
| Dell          | Inspiron 14 5425            | Notebook    | [65702761a8](https://linux-hardware.org/?probe=65702761a8) | Apr 10, 2024 |
| Acer          | Aspire A515-45              | Notebook    | [d62d670bd4](https://linux-hardware.org/?probe=d62d670bd4) | Apr 09, 2024 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [37733a1209](https://linux-hardware.org/?probe=37733a1209) | Apr 09, 2024 |
| Gigabyte      | A320M-DS2-CF                | Desktop     | [14aae5a31c](https://linux-hardware.org/?probe=14aae5a31c) | Apr 08, 2024 |
| Lenovo        | ThinkPad Yoga 260 20FES1... | Convertible | [fa773129c2](https://linux-hardware.org/?probe=fa773129c2) | Apr 08, 2024 |
| MSI           | Katana GF76 11SC            | Notebook    | [937a23fec5](https://linux-hardware.org/?probe=937a23fec5) | Apr 08, 2024 |
| HP            | 15                          | Notebook    | [8e4dc27da3](https://linux-hardware.org/?probe=8e4dc27da3) | Apr 08, 2024 |
| Lenovo        | ThinkPad T530 2359CTO       | Notebook    | [3fb9602631](https://linux-hardware.org/?probe=3fb9602631) | Apr 08, 2024 |
| Dell          | Inspiron N5110              | Notebook    | [e6d6bf8f56](https://linux-hardware.org/?probe=e6d6bf8f56) | Apr 06, 2024 |
| ASUSTek       | N551JX                      | Notebook    | [e7f0a7b86d](https://linux-hardware.org/?probe=e7f0a7b86d) | Apr 06, 2024 |
| Acer          | Aspire A315-59              | Notebook    | [f436469297](https://linux-hardware.org/?probe=f436469297) | Apr 06, 2024 |
| Unknown       | Unknown                     | Desktop     | [edbaa46cbe](https://linux-hardware.org/?probe=edbaa46cbe) | Apr 05, 2024 |
| MSI           | MS-B9241                    | Desktop     | [f0b74d9e54](https://linux-hardware.org/?probe=f0b74d9e54) | Apr 05, 2024 |
| Avell High... | B.ON                        | Notebook    | [9070104d8b](https://linux-hardware.org/?probe=9070104d8b) | Apr 05, 2024 |
| MSI           | Prestige 14Evo A11M         | Notebook    | [62fb7b6781](https://linux-hardware.org/?probe=62fb7b6781) | Apr 05, 2024 |
| Acer          | Nitro AN715-51              | Notebook    | [8f37d9426f](https://linux-hardware.org/?probe=8f37d9426f) | Apr 05, 2024 |
| HP            | Laptop 15q-ds0xxx           | Notebook    | [64e20f99d6](https://linux-hardware.org/?probe=64e20f99d6) | Apr 05, 2024 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [bba7520a79](https://linux-hardware.org/?probe=bba7520a79) | Apr 01, 2024 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [d82daf5b14](https://linux-hardware.org/?probe=d82daf5b14) | Apr 01, 2024 |
| Lenovo        | ThinkPad E520 1143R77       | Notebook    | [5aa9f4eb4b](https://linux-hardware.org/?probe=5aa9f4eb4b) | Apr 01, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [8b7a171522](https://linux-hardware.org/?probe=8b7a171522) | Mar 31, 2024 |
| Lenovo        | IdeaCentre K430             | Desktop     | [b72fcce004](https://linux-hardware.org/?probe=b72fcce004) | Mar 31, 2024 |
| Lenovo        | IdeaCentre K430             | Desktop     | [a2c9b21fb9](https://linux-hardware.org/?probe=a2c9b21fb9) | Mar 31, 2024 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [84b0e3e2af](https://linux-hardware.org/?probe=84b0e3e2af) | Mar 31, 2024 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [175015e349](https://linux-hardware.org/?probe=175015e349) | Mar 30, 2024 |
| Wortmann      | 1220571_1470066             | Notebook    | [702441f1cb](https://linux-hardware.org/?probe=702441f1cb) | Mar 30, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [ec84be5fad](https://linux-hardware.org/?probe=ec84be5fad) | Mar 30, 2024 |
| Avell High... | B.ON                        | Notebook    | [577f3c12bf](https://linux-hardware.org/?probe=577f3c12bf) | Mar 30, 2024 |
| Dell          | G3 3590                     | Notebook    | [5d1da882a1](https://linux-hardware.org/?probe=5d1da882a1) | Mar 30, 2024 |
| Dell          | Latitude 5580               | Notebook    | [db427c180d](https://linux-hardware.org/?probe=db427c180d) | Mar 28, 2024 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [75c0051304](https://linux-hardware.org/?probe=75c0051304) | Mar 28, 2024 |
| HUAWEI        | YTF-XXX                     | Notebook    | [fe3bb27b46](https://linux-hardware.org/?probe=fe3bb27b46) | Mar 28, 2024 |
| HP            | Laptop 15-fd0xxx            | Notebook    | [ff78c23f0b](https://linux-hardware.org/?probe=ff78c23f0b) | Mar 28, 2024 |
| HP            | 1998                        | Desktop     | [4c2971ed76](https://linux-hardware.org/?probe=4c2971ed76) | Mar 27, 2024 |
| Dell          | Inspiron 3543               | Notebook    | [d73ccce6fc](https://linux-hardware.org/?probe=d73ccce6fc) | Mar 27, 2024 |
| Dell          | XPS 15 7590                 | Notebook    | [44a28c885e](https://linux-hardware.org/?probe=44a28c885e) | Mar 27, 2024 |
| HP            | Notebook                    | Notebook    | [1b9763e964](https://linux-hardware.org/?probe=1b9763e964) | Mar 26, 2024 |
| AZW           | SER V1.0                    | Mini pc     | [8f85bd11a7](https://linux-hardware.org/?probe=8f85bd11a7) | Mar 26, 2024 |
| Dell          | Inspiron 3543               | Notebook    | [f4df9e06b2](https://linux-hardware.org/?probe=f4df9e06b2) | Mar 26, 2024 |
| Gigabyte      | A520I AC                    | Desktop     | [baff8cb9b8](https://linux-hardware.org/?probe=baff8cb9b8) | Mar 25, 2024 |
| Lenovo        | ThinkPad T430 2342A19       | Notebook    | [d71f48c168](https://linux-hardware.org/?probe=d71f48c168) | Mar 25, 2024 |
| ASRock        | B450M Pro4                  | Desktop     | [2e8543e629](https://linux-hardware.org/?probe=2e8543e629) | Mar 25, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [97a323caf9](https://linux-hardware.org/?probe=97a323caf9) | Mar 25, 2024 |
| HP            | 1998                        | Desktop     | [d8865ee940](https://linux-hardware.org/?probe=d8865ee940) | Mar 24, 2024 |
| Unknown       | Cherry Trail CR             | Notebook    | [efb2513f33](https://linux-hardware.org/?probe=efb2513f33) | Mar 22, 2024 |
| Acer          | Aspire E5-575G              | Notebook    | [cfac3d0451](https://linux-hardware.org/?probe=cfac3d0451) | Mar 21, 2024 |
| HP            | Pavilion 15                 | Notebook    | [6901a5764b](https://linux-hardware.org/?probe=6901a5764b) | Mar 20, 2024 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [891d67a053](https://linux-hardware.org/?probe=891d67a053) | Mar 19, 2024 |
| Lenovo        | 102F                        | Desktop     | [e4e070f4df](https://linux-hardware.org/?probe=e4e070f4df) | Mar 19, 2024 |
| HP            | EliteBook 8570p             | Notebook    | [04c8384abd](https://linux-hardware.org/?probe=04c8384abd) | Mar 19, 2024 |
| HP            | EliteBook 8570p             | Notebook    | [3dd98d315b](https://linux-hardware.org/?probe=3dd98d315b) | Mar 19, 2024 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [d24e51a631](https://linux-hardware.org/?probe=d24e51a631) | Mar 17, 2024 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [a98bd8065a](https://linux-hardware.org/?probe=a98bd8065a) | Mar 16, 2024 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [dff6166e47](https://linux-hardware.org/?probe=dff6166e47) | Mar 16, 2024 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | Notebook    | [c63d09f5fa](https://linux-hardware.org/?probe=c63d09f5fa) | Mar 15, 2024 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | Notebook    | [3f7ac15be0](https://linux-hardware.org/?probe=3f7ac15be0) | Mar 15, 2024 |
| ASRock        | B550M-ITX/ac                | Desktop     | [cdcb2eddcf](https://linux-hardware.org/?probe=cdcb2eddcf) | Mar 15, 2024 |
| ASUSTek       | TUF Z270 MARK 1             | Desktop     | [bd35285f2c](https://linux-hardware.org/?probe=bd35285f2c) | Mar 14, 2024 |
| Dell          | Unidentified System         | Notebook    | [bab85b187d](https://linux-hardware.org/?probe=bab85b187d) | Mar 14, 2024 |
| MSI           | MAG X670E TOMAHAWK WIFI     | Desktop     | [56218fcc37](https://linux-hardware.org/?probe=56218fcc37) | Mar 13, 2024 |
| MSI           | MAG X670E TOMAHAWK WIFI     | Desktop     | [9fd3e4a19d](https://linux-hardware.org/?probe=9fd3e4a19d) | Mar 13, 2024 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [c4fe7430eb](https://linux-hardware.org/?probe=c4fe7430eb) | Mar 13, 2024 |
| Dell          | Inspiron 3505               | Notebook    | [f3a4539b51](https://linux-hardware.org/?probe=f3a4539b51) | Mar 12, 2024 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [ea8dd3c585](https://linux-hardware.org/?probe=ea8dd3c585) | Mar 11, 2024 |
| Lenovo        | ThinkPad L390 Yoga 20NT0... | Convertible | [4c224edb1a](https://linux-hardware.org/?probe=4c224edb1a) | Mar 11, 2024 |
| Lenovo        | ThinkPad L390 Yoga 20NT0... | Convertible | [f18cdf7cd0](https://linux-hardware.org/?probe=f18cdf7cd0) | Mar 11, 2024 |
| Lenovo        | ThinkPad E480 20KN007XAD    | Notebook    | [44866c275d](https://linux-hardware.org/?probe=44866c275d) | Mar 10, 2024 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [78ab08dee5](https://linux-hardware.org/?probe=78ab08dee5) | Mar 09, 2024 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [4832f2d4f3](https://linux-hardware.org/?probe=4832f2d4f3) | Mar 09, 2024 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [afa0de9aa3](https://linux-hardware.org/?probe=afa0de9aa3) | Mar 09, 2024 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [3908a94356](https://linux-hardware.org/?probe=3908a94356) | Mar 08, 2024 |
| HP            | ProBook 450 G5              | Notebook    | [7e89a95523](https://linux-hardware.org/?probe=7e89a95523) | Mar 06, 2024 |
| HP            | 8704                        | Desktop     | [a9a02c9d98](https://linux-hardware.org/?probe=a9a02c9d98) | Mar 06, 2024 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [e3503e808b](https://linux-hardware.org/?probe=e3503e808b) | Mar 05, 2024 |
| MSI           | 970 GAMING                  | Desktop     | [7ec06861ba](https://linux-hardware.org/?probe=7ec06861ba) | Mar 05, 2024 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [f46cf35368](https://linux-hardware.org/?probe=f46cf35368) | Mar 05, 2024 |
| Lenovo        | ThinkPad T470 20HD000EHV    | Notebook    | [b2d96be2dd](https://linux-hardware.org/?probe=b2d96be2dd) | Mar 04, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [1d8f8e4d0f](https://linux-hardware.org/?probe=1d8f8e4d0f) | Mar 04, 2024 |
| MSI           | MPG Z690 EDGE WIFI DDR4     | Desktop     | [65080da98c](https://linux-hardware.org/?probe=65080da98c) | Mar 04, 2024 |
| Dell          | Inspiron 5567               | Notebook    | [0304104a60](https://linux-hardware.org/?probe=0304104a60) | Mar 03, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [336cabac77](https://linux-hardware.org/?probe=336cabac77) | Mar 02, 2024 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [59d562ccb2](https://linux-hardware.org/?probe=59d562ccb2) | Mar 02, 2024 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [b58bb65fff](https://linux-hardware.org/?probe=b58bb65fff) | Mar 01, 2024 |
| Acer          | Aspire Z3-615               | All in one  | [fd9c0e6b48](https://linux-hardware.org/?probe=fd9c0e6b48) | Feb 29, 2024 |
| Fujitsu       | LIFEBOOK T725               | Notebook    | [4f3102fa7d](https://linux-hardware.org/?probe=4f3102fa7d) | Feb 29, 2024 |
| ASUSTek       | K53SV                       | Notebook    | [1043b72dee](https://linux-hardware.org/?probe=1043b72dee) | Feb 29, 2024 |
| Acer          | Swift SF114-34              | Notebook    | [75d2193098](https://linux-hardware.org/?probe=75d2193098) | Feb 28, 2024 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [3022d85c07](https://linux-hardware.org/?probe=3022d85c07) | Feb 28, 2024 |
| MSI           | Pulse GL66 12UEK            | Notebook    | [49640f04ca](https://linux-hardware.org/?probe=49640f04ca) | Feb 28, 2024 |
| Lenovo        | ThinkBook 16p Gen 4 21J8    | Notebook    | [e947cc88f8](https://linux-hardware.org/?probe=e947cc88f8) | Feb 28, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [d549a1c39d](https://linux-hardware.org/?probe=d549a1c39d) | Feb 27, 2024 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [8f3bba3e55](https://linux-hardware.org/?probe=8f3bba3e55) | Feb 27, 2024 |
| Acer          | Veriton M4660G V:1.0        | Desktop     | [f4d17adcc4](https://linux-hardware.org/?probe=f4d17adcc4) | Feb 26, 2024 |
| HP            | EliteBook 840 G5            | Notebook    | [2c00c513d3](https://linux-hardware.org/?probe=2c00c513d3) | Feb 26, 2024 |
| HP            | EliteBook 840 G5            | Notebook    | [60b6b91372](https://linux-hardware.org/?probe=60b6b91372) | Feb 26, 2024 |
| MSI           | GF63 8RD                    | Notebook    | [b933a88005](https://linux-hardware.org/?probe=b933a88005) | Feb 26, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [e4c07576f6](https://linux-hardware.org/?probe=e4c07576f6) | Feb 26, 2024 |
| ASUSTek       | P7P55-M                     | Desktop     | [3ea869d864](https://linux-hardware.org/?probe=3ea869d864) | Feb 24, 2024 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [84300cc9c1](https://linux-hardware.org/?probe=84300cc9c1) | Feb 24, 2024 |
| Apple         | Mac-B809C3757DA9BB8D iMa... | All in one  | [ec1d2f8b0d](https://linux-hardware.org/?probe=ec1d2f8b0d) | Feb 24, 2024 |
| Apple         | MacBookPro16,3              | Notebook    | [4921eebd7d](https://linux-hardware.org/?probe=4921eebd7d) | Feb 23, 2024 |
| HP            | 1496                        | Desktop     | [1cc3bd19db](https://linux-hardware.org/?probe=1cc3bd19db) | Feb 23, 2024 |
| Gigabyte      | B760M DS3H                  | Desktop     | [7e6352f1af](https://linux-hardware.org/?probe=7e6352f1af) | Feb 23, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [682708c8fc](https://linux-hardware.org/?probe=682708c8fc) | Feb 22, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [7b6aebf503](https://linux-hardware.org/?probe=7b6aebf503) | Feb 22, 2024 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [6511d32b6d](https://linux-hardware.org/?probe=6511d32b6d) | Feb 22, 2024 |
| Fujitsu       | D3602-A1 S26361-D3602-A1    | Desktop     | [daeb6385eb](https://linux-hardware.org/?probe=daeb6385eb) | Feb 22, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [dbfe2d4d52](https://linux-hardware.org/?probe=dbfe2d4d52) | Feb 22, 2024 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [af9bba507c](https://linux-hardware.org/?probe=af9bba507c) | Feb 22, 2024 |
| ASRock        | B450M Pro4                  | Desktop     | [6ca9a09551](https://linux-hardware.org/?probe=6ca9a09551) | Feb 21, 2024 |
| Lenovo        | Legion Pro 7 16IRX8H 82W... | Notebook    | [1e64feccdb](https://linux-hardware.org/?probe=1e64feccdb) | Feb 21, 2024 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | Notebook    | [034c817132](https://linux-hardware.org/?probe=034c817132) | Feb 20, 2024 |
| Dell          | Latitude E6530              | Notebook    | [cd8cb1807f](https://linux-hardware.org/?probe=cd8cb1807f) | Feb 19, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [129f9eb367](https://linux-hardware.org/?probe=129f9eb367) | Feb 17, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [81acc04317](https://linux-hardware.org/?probe=81acc04317) | Feb 17, 2024 |
| Dell          | XPS 13 9315 2-in-1          | Tablet      | [c220d545b2](https://linux-hardware.org/?probe=c220d545b2) | Feb 17, 2024 |
| Dell          | XPS 13 9315 2-in-1          | Tablet      | [4886dcfde6](https://linux-hardware.org/?probe=4886dcfde6) | Feb 17, 2024 |
| Acer          | Nitro AN515-52              | Notebook    | [ecfbf20c60](https://linux-hardware.org/?probe=ecfbf20c60) | Feb 16, 2024 |
| AZW           | SER V1.0                    | Mini pc     | [106c5b5cdb](https://linux-hardware.org/?probe=106c5b5cdb) | Feb 15, 2024 |
| HP            | Spectre x360 Convertible... | Convertible | [3ea0c302a4](https://linux-hardware.org/?probe=3ea0c302a4) | Feb 15, 2024 |
| Gigabyte      | B650M DS3H                  | Desktop     | [91f2211c0c](https://linux-hardware.org/?probe=91f2211c0c) | Feb 14, 2024 |
| ASUSTek       | P5LD2-TVM-SE-SI             | Desktop     | [d0a9f3664e](https://linux-hardware.org/?probe=d0a9f3664e) | Feb 13, 2024 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [c5a7934836](https://linux-hardware.org/?probe=c5a7934836) | Feb 13, 2024 |
| ASUSTek       | H61M-A/BR                   | Desktop     | [6a09917f6f](https://linux-hardware.org/?probe=6a09917f6f) | Feb 13, 2024 |
| HP            | EliteBook 650 15.6 inch ... | Notebook    | [c82778e496](https://linux-hardware.org/?probe=c82778e496) | Feb 13, 2024 |
| AZW           | SER V1.0                    | Mini pc     | [0b68327f4f](https://linux-hardware.org/?probe=0b68327f4f) | Feb 13, 2024 |
| HP            | 843B                        | Desktop     | [aa6fd9964e](https://linux-hardware.org/?probe=aa6fd9964e) | Feb 13, 2024 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [f8f33cacdf](https://linux-hardware.org/?probe=f8f33cacdf) | Feb 13, 2024 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [25f4ea22cd](https://linux-hardware.org/?probe=25f4ea22cd) | Feb 12, 2024 |
| HP            | G62                         | Notebook    | [b6daa4e6b1](https://linux-hardware.org/?probe=b6daa4e6b1) | Feb 12, 2024 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [6f6d39cf77](https://linux-hardware.org/?probe=6f6d39cf77) | Feb 12, 2024 |
| Gigabyte      | B460 AORUS PRO AC           | Desktop     | [00a2a68eef](https://linux-hardware.org/?probe=00a2a68eef) | Feb 12, 2024 |
| AMD           | 990FXA-UD3                  | Desktop     | [a8866aee9c](https://linux-hardware.org/?probe=a8866aee9c) | Feb 12, 2024 |
| Lenovo        | ThinkPad P51 20HJS3Q700     | Notebook    | [2de6ff345e](https://linux-hardware.org/?probe=2de6ff345e) | Feb 12, 2024 |
| MSI           | Z270 GAMING PLUS            | Desktop     | [d232086b57](https://linux-hardware.org/?probe=d232086b57) | Feb 11, 2024 |
| Intel         | DQ57TM AAE70931-402         | Desktop     | [1c8831a84d](https://linux-hardware.org/?probe=1c8831a84d) | Feb 11, 2024 |
| Unknown       | Unknown                     | Desktop     | [0a197d31ec](https://linux-hardware.org/?probe=0a197d31ec) | Feb 10, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [bc1e6e90c1](https://linux-hardware.org/?probe=bc1e6e90c1) | Feb 10, 2024 |
| HP            | 1998                        | Desktop     | [de3c15346c](https://linux-hardware.org/?probe=de3c15346c) | Feb 10, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [0c1b63b275](https://linux-hardware.org/?probe=0c1b63b275) | Feb 10, 2024 |
| AAEON         | S500 V1.0                   | Desktop     | [e4d8723e6f](https://linux-hardware.org/?probe=e4d8723e6f) | Feb 09, 2024 |
| Acer          | Aspire A515-57              | Notebook    | [5e72988c18](https://linux-hardware.org/?probe=5e72988c18) | Feb 08, 2024 |
| ASUSTek       | P5LD2-TVM-SE-SI             | Desktop     | [df029c3635](https://linux-hardware.org/?probe=df029c3635) | Feb 07, 2024 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [85c4dfa0f4](https://linux-hardware.org/?probe=85c4dfa0f4) | Feb 07, 2024 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [790b3a7124](https://linux-hardware.org/?probe=790b3a7124) | Feb 07, 2024 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [429b3c3517](https://linux-hardware.org/?probe=429b3c3517) | Feb 05, 2024 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [4b6f872d8b](https://linux-hardware.org/?probe=4b6f872d8b) | Feb 05, 2024 |
| HP            | 1998                        | Desktop     | [5e85b19897](https://linux-hardware.org/?probe=5e85b19897) | Feb 05, 2024 |
| Toshiba       | QOSMIO X505                 | Notebook    | [109be22d5f](https://linux-hardware.org/?probe=109be22d5f) | Feb 05, 2024 |
| HP            | Pavilion 15                 | Notebook    | [066b0cf774](https://linux-hardware.org/?probe=066b0cf774) | Feb 05, 2024 |
| HP            | 89D8 SMVB                   | Desktop     | [732db9f3b4](https://linux-hardware.org/?probe=732db9f3b4) | Feb 04, 2024 |
| Lenovo        | IdeaPad Y560                | Notebook    | [24bf3674dc](https://linux-hardware.org/?probe=24bf3674dc) | Feb 04, 2024 |
| Lenovo        | IdeaPad Y560                | Notebook    | [7d98e0f393](https://linux-hardware.org/?probe=7d98e0f393) | Feb 04, 2024 |
| Lenovo        | ThinkPad E520 1143R77       | Notebook    | [b36ea31ed6](https://linux-hardware.org/?probe=b36ea31ed6) | Feb 04, 2024 |
| Shenzhen M... | F6BFC                       | Desktop     | [489a0859f2](https://linux-hardware.org/?probe=489a0859f2) | Feb 03, 2024 |
| Dell          | Inspiron 5593               | Notebook    | [99994880b0](https://linux-hardware.org/?probe=99994880b0) | Feb 03, 2024 |
| Biostar       | G41-M7                      | Desktop     | [eea33a47ac](https://linux-hardware.org/?probe=eea33a47ac) | Feb 03, 2024 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [58d150eef2](https://linux-hardware.org/?probe=58d150eef2) | Feb 02, 2024 |
| Unknown       | Unknown                     | Notebook    | [8c03bd946c](https://linux-hardware.org/?probe=8c03bd946c) | Feb 02, 2024 |
| Notebook      | V15x_V17xRNx                | Notebook    | [901e71289e](https://linux-hardware.org/?probe=901e71289e) | Feb 02, 2024 |
| ASUSTek       | P5Q                         | Desktop     | [63522c9a09](https://linux-hardware.org/?probe=63522c9a09) | Feb 02, 2024 |
| GX55          | Unknown                     | Tablet      | [99db62ac14](https://linux-hardware.org/?probe=99db62ac14) | Feb 02, 2024 |
| Dell          | Inspiron 5547               | Notebook    | [507fad3c00](https://linux-hardware.org/?probe=507fad3c00) | Feb 02, 2024 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [c2514048e9](https://linux-hardware.org/?probe=c2514048e9) | Feb 02, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [8e3680cd5d](https://linux-hardware.org/?probe=8e3680cd5d) | Feb 01, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [f1b0b8716f](https://linux-hardware.org/?probe=f1b0b8716f) | Feb 01, 2024 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [9d2088ace3](https://linux-hardware.org/?probe=9d2088ace3) | Feb 01, 2024 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | Notebook    | [8f630da527](https://linux-hardware.org/?probe=8f630da527) | Jan 31, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [02d7b129fc](https://linux-hardware.org/?probe=02d7b129fc) | Jan 31, 2024 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [a477ec4fe1](https://linux-hardware.org/?probe=a477ec4fe1) | Jan 31, 2024 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [aabd02c85c](https://linux-hardware.org/?probe=aabd02c85c) | Jan 30, 2024 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [c823432a5a](https://linux-hardware.org/?probe=c823432a5a) | Jan 30, 2024 |
| ASUSTek       | G75VX                       | Notebook    | [5c270f1082](https://linux-hardware.org/?probe=5c270f1082) | Jan 30, 2024 |
| Toshiba       | Satellite P300              | Notebook    | [14da91750f](https://linux-hardware.org/?probe=14da91750f) | Jan 29, 2024 |
| Acer          | Veriton X6630G              | Desktop     | [66d62ae7ed](https://linux-hardware.org/?probe=66d62ae7ed) | Jan 29, 2024 |
| Acer          | Veriton X6630G              | Desktop     | [9684aca764](https://linux-hardware.org/?probe=9684aca764) | Jan 29, 2024 |
| Acer          | TravelMate P215-41-G2       | Notebook    | [0500733b2d](https://linux-hardware.org/?probe=0500733b2d) | Jan 28, 2024 |
| HP            | EliteBook 8470w             | Notebook    | [a92904a970](https://linux-hardware.org/?probe=a92904a970) | Jan 28, 2024 |
| Acer          | Aspire A715-42G             | Notebook    | [6e3e887615](https://linux-hardware.org/?probe=6e3e887615) | Jan 27, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21AHA... | Notebook    | [f2ed690a39](https://linux-hardware.org/?probe=f2ed690a39) | Jan 27, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21AHA... | Notebook    | [4644130b45](https://linux-hardware.org/?probe=4644130b45) | Jan 27, 2024 |
| ASRock        | B450M Pro4                  | Desktop     | [23faf0c03e](https://linux-hardware.org/?probe=23faf0c03e) | Jan 25, 2024 |
| Lenovo        | ThinkPad Twist 334729G      | Notebook    | [0a17051b66](https://linux-hardware.org/?probe=0a17051b66) | Jan 25, 2024 |
| Medion        | S14409                      | Notebook    | [8e8339905a](https://linux-hardware.org/?probe=8e8339905a) | Jan 25, 2024 |
| AZW           | Gemini T45                  | Desktop     | [5a3dba74d6](https://linux-hardware.org/?probe=5a3dba74d6) | Jan 24, 2024 |
| AZW           | Gemini T45                  | Desktop     | [a0e1db7908](https://linux-hardware.org/?probe=a0e1db7908) | Jan 24, 2024 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [7c94952653](https://linux-hardware.org/?probe=7c94952653) | Jan 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | Notebook    | [f9da9c2d2e](https://linux-hardware.org/?probe=f9da9c2d2e) | Jan 23, 2024 |
| HP            | ProBook 4540s               | Notebook    | [84367073dd](https://linux-hardware.org/?probe=84367073dd) | Jan 22, 2024 |
| HP            | ProBook 4540s               | Notebook    | [f72cd2d1a0](https://linux-hardware.org/?probe=f72cd2d1a0) | Jan 22, 2024 |
| Lenovo        | 1037 SDK0Q40104 WIN 3305... | Server      | [e8d7aba4fe](https://linux-hardware.org/?probe=e8d7aba4fe) | Jan 22, 2024 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [31a4f6e57f](https://linux-hardware.org/?probe=31a4f6e57f) | Jan 22, 2024 |
| ASUSTek       | UX410UAK                    | Notebook    | [1155ca8c5c](https://linux-hardware.org/?probe=1155ca8c5c) | Jan 22, 2024 |
| Gigabyte      | Z97-HD3                     | Desktop     | [e568089bad](https://linux-hardware.org/?probe=e568089bad) | Jan 21, 2024 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [aaf1d1d0de](https://linux-hardware.org/?probe=aaf1d1d0de) | Jan 21, 2024 |
| HP            | Notebook                    | Notebook    | [71136f647b](https://linux-hardware.org/?probe=71136f647b) | Jan 20, 2024 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [494d0af2e5](https://linux-hardware.org/?probe=494d0af2e5) | Jan 19, 2024 |
| Dell          | Latitude 7330               | Notebook    | [d8b532bbee](https://linux-hardware.org/?probe=d8b532bbee) | Jan 19, 2024 |
| HP            | OMEN Laptop 15-ek1xxx       | Notebook    | [5c18e1a4bc](https://linux-hardware.org/?probe=5c18e1a4bc) | Jan 18, 2024 |
| Great Wall    | MBX-Z60AR110 TBD            | Desktop     | [fdfa81d344](https://linux-hardware.org/?probe=fdfa81d344) | Jan 18, 2024 |
| Dell          | Latitude 5530               | Notebook    | [df5d5becd7](https://linux-hardware.org/?probe=df5d5becd7) | Jan 17, 2024 |
| Medion        | H110H4-EM                   | Desktop     | [ea736cf314](https://linux-hardware.org/?probe=ea736cf314) | Jan 17, 2024 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [0d81012aa0](https://linux-hardware.org/?probe=0d81012aa0) | Jan 16, 2024 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [c69281db28](https://linux-hardware.org/?probe=c69281db28) | Jan 15, 2024 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [ca627d3c3e](https://linux-hardware.org/?probe=ca627d3c3e) | Jan 15, 2024 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [cdfc29ad66](https://linux-hardware.org/?probe=cdfc29ad66) | Jan 15, 2024 |
| MSI           | Summit E16Flip A12UCT       | Notebook    | [efb852e7fb](https://linux-hardware.org/?probe=efb852e7fb) | Jan 15, 2024 |
| Google        | Fleex                       | Notebook    | [46f5b6af86](https://linux-hardware.org/?probe=46f5b6af86) | Jan 14, 2024 |
| VALE          | Notebook Slim S132          | Notebook    | [32021c35d3](https://linux-hardware.org/?probe=32021c35d3) | Jan 14, 2024 |
| VALE          | Notebook Slim S132          | Notebook    | [0d2db2e184](https://linux-hardware.org/?probe=0d2db2e184) | Jan 14, 2024 |
| HP            | x2 210 G2                   | Tablet      | [e1baf3e443](https://linux-hardware.org/?probe=e1baf3e443) | Jan 14, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [bda32c8468](https://linux-hardware.org/?probe=bda32c8468) | Jan 14, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [398927cd45](https://linux-hardware.org/?probe=398927cd45) | Jan 13, 2024 |
| Unknown       | Unknown                     | Desktop     | [25341b5586](https://linux-hardware.org/?probe=25341b5586) | Jan 13, 2024 |
| Lenovo        | ThinkPad T495 20NJ000XIX    | Notebook    | [700470a7f6](https://linux-hardware.org/?probe=700470a7f6) | Jan 12, 2024 |
| MSI           | H410M PRO                   | Desktop     | [76a24b5fa3](https://linux-hardware.org/?probe=76a24b5fa3) | Jan 12, 2024 |
| Lenovo        | ThinkPad E450 20DC003WUS    | Notebook    | [817c17d60e](https://linux-hardware.org/?probe=817c17d60e) | Jan 12, 2024 |
| HP            | ProBook 6450b               | Notebook    | [ddae4148a2](https://linux-hardware.org/?probe=ddae4148a2) | Jan 12, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [bddc683db5](https://linux-hardware.org/?probe=bddc683db5) | Jan 12, 2024 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [a188d14c50](https://linux-hardware.org/?probe=a188d14c50) | Jan 11, 2024 |
| Dell          | Inspiron 3793               | Notebook    | [60ded5e8e7](https://linux-hardware.org/?probe=60ded5e8e7) | Jan 11, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f1814dff2e](https://linux-hardware.org/?probe=f1814dff2e) | Jan 11, 2024 |
| HP            | 8767 A                      | Desktop     | [88f6719b01](https://linux-hardware.org/?probe=88f6719b01) | Jan 10, 2024 |
| ASUSTek       | H81T R2.0                   | Desktop     | [23cc8eb053](https://linux-hardware.org/?probe=23cc8eb053) | Jan 10, 2024 |
| Sony          | VGN-CS190N                  | Notebook    | [2ac26516a6](https://linux-hardware.org/?probe=2ac26516a6) | Jan 09, 2024 |
| ASUSTek       | Zephyrus S GX502GW_GX502... | Notebook    | [8101d22b4a](https://linux-hardware.org/?probe=8101d22b4a) | Jan 09, 2024 |
| Dell          | 0HD5W2 A01                  | Desktop     | [7194fe43ed](https://linux-hardware.org/?probe=7194fe43ed) | Jan 09, 2024 |
| Dell          | 0F96C8 A00                  | All in one  | [f7d20028f6](https://linux-hardware.org/?probe=f7d20028f6) | Jan 08, 2024 |
| Gigabyte      | H67A-UD3H-B3                | Desktop     | [f43717fa8e](https://linux-hardware.org/?probe=f43717fa8e) | Jan 08, 2024 |
| Dell          | Latitude E7450              | Notebook    | [a60667c993](https://linux-hardware.org/?probe=a60667c993) | Jan 08, 2024 |
| Apple         | MacBookAir9,1               | Notebook    | [6af0a29be6](https://linux-hardware.org/?probe=6af0a29be6) | Jan 07, 2024 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [ee9fb5898f](https://linux-hardware.org/?probe=ee9fb5898f) | Jan 07, 2024 |
| HP            | 3397                        | Desktop     | [0ba7322ded](https://linux-hardware.org/?probe=0ba7322ded) | Jan 05, 2024 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [5feecec8b2](https://linux-hardware.org/?probe=5feecec8b2) | Jan 05, 2024 |
| Biostar       | B365MHC                     | Desktop     | [0936a451ce](https://linux-hardware.org/?probe=0936a451ce) | Jan 04, 2024 |
| HP            | ENVY m6                     | Notebook    | [d63a06fb89](https://linux-hardware.org/?probe=d63a06fb89) | Jan 04, 2024 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [cf1f935e69](https://linux-hardware.org/?probe=cf1f935e69) | Jan 03, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [cf07066830](https://linux-hardware.org/?probe=cf07066830) | Jan 03, 2024 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [4c7efd21fe](https://linux-hardware.org/?probe=4c7efd21fe) | Jan 02, 2024 |
| Rockchip      | RK3588 OPi 5 Plus           | Soc         | [a948fd2006](https://linux-hardware.org/?probe=a948fd2006) | Jan 02, 2024 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [fb59929b28](https://linux-hardware.org/?probe=fb59929b28) | Jan 02, 2024 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [435dc251c1](https://linux-hardware.org/?probe=435dc251c1) | Jan 02, 2024 |
| Rockchip      | RK3588 OPi 5 Plus           | Soc         | [e8e24c9091](https://linux-hardware.org/?probe=e8e24c9091) | Jan 01, 2024 |
| MSI           | 2AE0                        | Desktop     | [00b5d15112](https://linux-hardware.org/?probe=00b5d15112) | Jan 01, 2024 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [8a1771af4b](https://linux-hardware.org/?probe=8a1771af4b) | Jan 01, 2024 |
| Rockchip      | RK3588 OPi 5 Plus           | Soc         | [c6a3df522b](https://linux-hardware.org/?probe=c6a3df522b) | Dec 31, 2023 |
| Toshiba       | STI 013442                  | Desktop     | [c8488906f2](https://linux-hardware.org/?probe=c8488906f2) | Dec 31, 2023 |
| Notebook      | NL5xNU                      | Notebook    | [915031852a](https://linux-hardware.org/?probe=915031852a) | Dec 31, 2023 |
| Toshiba       | STI 013442                  | Desktop     | [ed56d2dcb5](https://linux-hardware.org/?probe=ed56d2dcb5) | Dec 31, 2023 |
| Apple         | MacBookAir9,1               | Notebook    | [71c755966f](https://linux-hardware.org/?probe=71c755966f) | Dec 31, 2023 |
| Apple         | MacBookAir9,1               | Notebook    | [b13ec8c4fe](https://linux-hardware.org/?probe=b13ec8c4fe) | Dec 31, 2023 |
| ASUSTek       | PRIME B360M-A               | Notebook    | [42b25d8ac5](https://linux-hardware.org/?probe=42b25d8ac5) | Dec 30, 2023 |
| HP            | ENVY m4                     | Notebook    | [6416f24210](https://linux-hardware.org/?probe=6416f24210) | Dec 30, 2023 |
| HP            | ENVY m4                     | Notebook    | [f0cd285399](https://linux-hardware.org/?probe=f0cd285399) | Dec 30, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [3700165122](https://linux-hardware.org/?probe=3700165122) | Dec 28, 2023 |
| Rockchip      | RK3588 OPi 5 Plus           | Soc         | [4f74bf57df](https://linux-hardware.org/?probe=4f74bf57df) | Dec 28, 2023 |
| Rockchip      | RK3588 OPi 5 Plus           | Soc         | [59ae3d3d52](https://linux-hardware.org/?probe=59ae3d3d52) | Dec 28, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [c68ea76b65](https://linux-hardware.org/?probe=c68ea76b65) | Dec 28, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [48d04b219b](https://linux-hardware.org/?probe=48d04b219b) | Dec 28, 2023 |
| Foxconn       | 2AB7                        | Desktop     | [2d0962bbfa](https://linux-hardware.org/?probe=2d0962bbfa) | Dec 27, 2023 |
| Foxconn       | 2AB7                        | Desktop     | [b1b00dd0b5](https://linux-hardware.org/?probe=b1b00dd0b5) | Dec 27, 2023 |
| Notebook      | NL5xNU                      | Notebook    | [ad5a093909](https://linux-hardware.org/?probe=ad5a093909) | Dec 26, 2023 |
| Lenovo        | ThinkPad T520 4243ED3       | Notebook    | [6fd4832f12](https://linux-hardware.org/?probe=6fd4832f12) | Dec 26, 2023 |
| Apple         | MacBookAir9,1               | Notebook    | [22b65c12f2](https://linux-hardware.org/?probe=22b65c12f2) | Dec 26, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [0714d5920a](https://linux-hardware.org/?probe=0714d5920a) | Dec 26, 2023 |
| PC Special... | 14 Fusion Pro               | Notebook    | [76bf311c34](https://linux-hardware.org/?probe=76bf311c34) | Dec 25, 2023 |
| Dell          | 0F6X5P A00                  | Desktop     | [8b6cbdd646](https://linux-hardware.org/?probe=8b6cbdd646) | Dec 24, 2023 |
| HP            | 340S G7 Notebook PC         | Notebook    | [097603b65a](https://linux-hardware.org/?probe=097603b65a) | Dec 23, 2023 |
| Lenovo        | ThinkPad T500 20564RG       | Notebook    | [e17f4b51d6](https://linux-hardware.org/?probe=e17f4b51d6) | Dec 22, 2023 |
| Lenovo        | M30-70 80H8                 | Notebook    | [8ec7db7a8a](https://linux-hardware.org/?probe=8ec7db7a8a) | Dec 22, 2023 |
| Eluktronic... | MECH-17                     | Notebook    | [0a69b2e084](https://linux-hardware.org/?probe=0a69b2e084) | Dec 22, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | Notebook    | [db6db43604](https://linux-hardware.org/?probe=db6db43604) | Dec 22, 2023 |
| HUAWEI        | RLEF-XX                     | Notebook    | [cdcc0b8368](https://linux-hardware.org/?probe=cdcc0b8368) | Dec 22, 2023 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [1b860f6465](https://linux-hardware.org/?probe=1b860f6465) | Dec 21, 2023 |
| Dell          | 0F6X5P A00                  | Desktop     | [fb2877e727](https://linux-hardware.org/?probe=fb2877e727) | Dec 21, 2023 |
| Apple         | Mac-F2218FC8                | All in one  | [81855c7ee8](https://linux-hardware.org/?probe=81855c7ee8) | Dec 21, 2023 |
| Google        | Cave                        | Notebook    | [ec9d49335f](https://linux-hardware.org/?probe=ec9d49335f) | Dec 20, 2023 |
| HP            | Pavilion 17                 | Notebook    | [449c36ff1c](https://linux-hardware.org/?probe=449c36ff1c) | Dec 19, 2023 |
| TUXEDO        | Pulse 14 Gen1               | Notebook    | [031f8b45bd](https://linux-hardware.org/?probe=031f8b45bd) | Dec 19, 2023 |
| MSI           | H97M-P35                    | Desktop     | [759943cd15](https://linux-hardware.org/?probe=759943cd15) | Dec 19, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [42706222be](https://linux-hardware.org/?probe=42706222be) | Dec 19, 2023 |
| HP            | 81B3                        | Desktop     | [86d9fc12a5](https://linux-hardware.org/?probe=86d9fc12a5) | Dec 19, 2023 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [d56dcc35b9](https://linux-hardware.org/?probe=d56dcc35b9) | Dec 18, 2023 |
| Gateway       | NV54 Series                 | Notebook    | [1bd87c77d2](https://linux-hardware.org/?probe=1bd87c77d2) | Dec 18, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [6115b25184](https://linux-hardware.org/?probe=6115b25184) | Dec 18, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [8507460974](https://linux-hardware.org/?probe=8507460974) | Dec 18, 2023 |
| MSI           | GF63 Thin 9RCX              | Notebook    | [fe9179b1fb](https://linux-hardware.org/?probe=fe9179b1fb) | Dec 16, 2023 |
| Gigabyte      | 970-GAMING                  | Desktop     | [f1f6a55f9c](https://linux-hardware.org/?probe=f1f6a55f9c) | Dec 16, 2023 |
| Gigabyte      | 970-GAMING                  | Desktop     | [8b6e7627f9](https://linux-hardware.org/?probe=8b6e7627f9) | Dec 16, 2023 |
| HP            | G62                         | Notebook    | [fd110d99fd](https://linux-hardware.org/?probe=fd110d99fd) | Dec 15, 2023 |
| Lenovo        | IdeaPad Pro 5 16APH8 83A... | Notebook    | [d438fe20ff](https://linux-hardware.org/?probe=d438fe20ff) | Dec 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | Notebook    | [42b02a9d8e](https://linux-hardware.org/?probe=42b02a9d8e) | Dec 14, 2023 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [57cc6cbccf](https://linux-hardware.org/?probe=57cc6cbccf) | Dec 14, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [27c22f0c94](https://linux-hardware.org/?probe=27c22f0c94) | Dec 14, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [22dfb202b4](https://linux-hardware.org/?probe=22dfb202b4) | Dec 12, 2023 |
| Lenovo        | IdeaPad D330-10IGL 82H0     | Tablet      | [a73b0c39f2](https://linux-hardware.org/?probe=a73b0c39f2) | Dec 12, 2023 |
| Lenovo        | IdeaPad D330-10IGL 82H0     | Tablet      | [b569f37962](https://linux-hardware.org/?probe=b569f37962) | Dec 11, 2023 |
| HP            | Laptop                      | Notebook    | [8bdb6d048e](https://linux-hardware.org/?probe=8bdb6d048e) | Dec 11, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [281cfa9ff7](https://linux-hardware.org/?probe=281cfa9ff7) | Dec 11, 2023 |
| HP            | Laptop                      | Notebook    | [b5d2cf7074](https://linux-hardware.org/?probe=b5d2cf7074) | Dec 10, 2023 |
| Acer          | Nitro AN517-41              | Notebook    | [6e5abc0ea5](https://linux-hardware.org/?probe=6e5abc0ea5) | Dec 10, 2023 |
| Gigabyte      | P55-UD3                     | Desktop     | [4c20f6a826](https://linux-hardware.org/?probe=4c20f6a826) | Dec 10, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [3a6b7f5ae4](https://linux-hardware.org/?probe=3a6b7f5ae4) | Dec 09, 2023 |
| Notebook      | N24_25JU                    | Notebook    | [170b205714](https://linux-hardware.org/?probe=170b205714) | Dec 09, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [6f35ce12bd](https://linux-hardware.org/?probe=6f35ce12bd) | Dec 07, 2023 |
| ASUSTek       | K52JB                       | Notebook    | [2edc689735](https://linux-hardware.org/?probe=2edc689735) | Dec 06, 2023 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | Notebook    | [1f68b6b7c7](https://linux-hardware.org/?probe=1f68b6b7c7) | Dec 06, 2023 |
| eMachines     | eME732G                     | Notebook    | [d94dd62bf1](https://linux-hardware.org/?probe=d94dd62bf1) | Dec 05, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [e90c011500](https://linux-hardware.org/?probe=e90c011500) | Dec 05, 2023 |
| Acer          | Aspire A314-22              | Notebook    | [daa41db960](https://linux-hardware.org/?probe=daa41db960) | Dec 05, 2023 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [57a63775b2](https://linux-hardware.org/?probe=57a63775b2) | Dec 05, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [e6e58d5148](https://linux-hardware.org/?probe=e6e58d5148) | Dec 05, 2023 |
| Samsung       | 730QED                      | Convertible | [e7b8057036](https://linux-hardware.org/?probe=e7b8057036) | Dec 04, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [8fd5e3b166](https://linux-hardware.org/?probe=8fd5e3b166) | Dec 04, 2023 |
| eMachines     | eME732G                     | Notebook    | [931569e396](https://linux-hardware.org/?probe=931569e396) | Dec 03, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [abb3c226ed](https://linux-hardware.org/?probe=abb3c226ed) | Dec 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [ff37eb859a](https://linux-hardware.org/?probe=ff37eb859a) | Dec 02, 2023 |
| ASUSTek       | M4A88TD-M EVO               | Desktop     | [7f6b5fd810](https://linux-hardware.org/?probe=7f6b5fd810) | Dec 01, 2023 |
| Lenovo        | K14 G2 IRU 21G1             | Notebook    | [b52ce46b0d](https://linux-hardware.org/?probe=b52ce46b0d) | Dec 01, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [88bd7270db](https://linux-hardware.org/?probe=88bd7270db) | Dec 01, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [be4ecb6dfa](https://linux-hardware.org/?probe=be4ecb6dfa) | Nov 29, 2023 |
| ASUSTek       | P7P55D-E PRO                | Desktop     | [6fe23dd80e](https://linux-hardware.org/?probe=6fe23dd80e) | Nov 28, 2023 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [1f830eb37e](https://linux-hardware.org/?probe=1f830eb37e) | Nov 27, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [e38428746a](https://linux-hardware.org/?probe=e38428746a) | Nov 27, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [12e26441e1](https://linux-hardware.org/?probe=12e26441e1) | Nov 27, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [4b4737d484](https://linux-hardware.org/?probe=4b4737d484) | Nov 27, 2023 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [8474959120](https://linux-hardware.org/?probe=8474959120) | Nov 26, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [c166853e23](https://linux-hardware.org/?probe=c166853e23) | Nov 26, 2023 |
| ASUSTek       | ROG STRIX B460-I GAMING     | Desktop     | [7a0adaf9f3](https://linux-hardware.org/?probe=7a0adaf9f3) | Nov 25, 2023 |
| ASUSTek       | ROG STRIX B460-I GAMING     | Desktop     | [b96e460a4f](https://linux-hardware.org/?probe=b96e460a4f) | Nov 25, 2023 |
| Dell          | Inspiron 5537               | Notebook    | [7c92224aed](https://linux-hardware.org/?probe=7c92224aed) | Nov 25, 2023 |
| Dell          | Inspiron 5537               | Notebook    | [57a3d9064a](https://linux-hardware.org/?probe=57a3d9064a) | Nov 25, 2023 |
| Dell          | Inspiron 5537               | Notebook    | [a4c63ff9b4](https://linux-hardware.org/?probe=a4c63ff9b4) | Nov 25, 2023 |
| Lenovo        | IdeaPad Pro 5 16APH8 83A... | Notebook    | [2b5e71ca1e](https://linux-hardware.org/?probe=2b5e71ca1e) | Nov 24, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [48112cbfe0](https://linux-hardware.org/?probe=48112cbfe0) | Nov 24, 2023 |
| Acer          | Aspire E5-575               | Notebook    | [1ad50e2862](https://linux-hardware.org/?probe=1ad50e2862) | Nov 23, 2023 |
| Lenovo        | 1037 SDK0Q40104 WIN 3305... | Server      | [7b466d7f56](https://linux-hardware.org/?probe=7b466d7f56) | Nov 22, 2023 |
| BESSTAR Te... | TH50                        | Desktop     | [39c4acf035](https://linux-hardware.org/?probe=39c4acf035) | Nov 22, 2023 |
| Acer          | Aspire E1-570               | Notebook    | [8c6fd80245](https://linux-hardware.org/?probe=8c6fd80245) | Nov 22, 2023 |
| Lenovo        | ThinkCentre M91p 4518A31    | Desktop     | [9031421465](https://linux-hardware.org/?probe=9031421465) | Nov 22, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [195e3a2ce6](https://linux-hardware.org/?probe=195e3a2ce6) | Nov 22, 2023 |
| ASUSTek       | PRIME X299-DELUXE           | Desktop     | [cd86a8c45b](https://linux-hardware.org/?probe=cd86a8c45b) | Nov 22, 2023 |
| HP            | 2AA7 H                      | Desktop     | [c98041f477](https://linux-hardware.org/?probe=c98041f477) | Nov 21, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [6066ce2199](https://linux-hardware.org/?probe=6066ce2199) | Nov 20, 2023 |
| PC Special... | Lafite Pro II 15            | Notebook    | [b7b85ab8ce](https://linux-hardware.org/?probe=b7b85ab8ce) | Nov 20, 2023 |
| Dell          | 0YJPT1 A00                  | Desktop     | [7728c1ff4c](https://linux-hardware.org/?probe=7728c1ff4c) | Nov 20, 2023 |
| HP            | ProBook 430 G6              | Notebook    | [6175f06df9](https://linux-hardware.org/?probe=6175f06df9) | Nov 20, 2023 |
| Dell          | 02M8NY A00                  | Desktop     | [dd2bdfb403](https://linux-hardware.org/?probe=dd2bdfb403) | Nov 20, 2023 |
| HP            | Pavilion 17                 | Notebook    | [00c2d45d1d](https://linux-hardware.org/?probe=00c2d45d1d) | Nov 19, 2023 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [883da32584](https://linux-hardware.org/?probe=883da32584) | Nov 18, 2023 |
| Gigabyte      | X570 UD                     | Desktop     | [2902bc3e9f](https://linux-hardware.org/?probe=2902bc3e9f) | Nov 15, 2023 |
| Dell          | Latitude 5521               | Notebook    | [2cd2e72764](https://linux-hardware.org/?probe=2cd2e72764) | Nov 15, 2023 |
| Dell          | Latitude E7450              | Notebook    | [500f23ef78](https://linux-hardware.org/?probe=500f23ef78) | Nov 14, 2023 |
| HP            | ProBook 6570b               | Notebook    | [edf0d74b51](https://linux-hardware.org/?probe=edf0d74b51) | Nov 14, 2023 |
| Lenovo        | G550 2958                   | Notebook    | [b158de590e](https://linux-hardware.org/?probe=b158de590e) | Nov 14, 2023 |
| Lenovo        | G550 2958                   | Notebook    | [25455f055b](https://linux-hardware.org/?probe=25455f055b) | Nov 14, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [0874caf8a9](https://linux-hardware.org/?probe=0874caf8a9) | Nov 13, 2023 |
| ASRock        | B760M Steel Legend WiFi     | Desktop     | [8fd2ed0ba7](https://linux-hardware.org/?probe=8fd2ed0ba7) | Nov 13, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [2166a882d2](https://linux-hardware.org/?probe=2166a882d2) | Nov 13, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [872e6f2ca5](https://linux-hardware.org/?probe=872e6f2ca5) | Nov 12, 2023 |
| HP            | Pavilion g6                 | Notebook    | [1215d8475b](https://linux-hardware.org/?probe=1215d8475b) | Nov 11, 2023 |
| Lenovo        | ThinkPad T480s 20L7001MH... | Notebook    | [f5c3846dce](https://linux-hardware.org/?probe=f5c3846dce) | Nov 10, 2023 |
| Dell          | 0WN7Y6 A01                  | Desktop     | [85e2b37a15](https://linux-hardware.org/?probe=85e2b37a15) | Nov 10, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [ecb49b0454](https://linux-hardware.org/?probe=ecb49b0454) | Nov 09, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [5b67ed0642](https://linux-hardware.org/?probe=5b67ed0642) | Nov 09, 2023 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | Notebook    | [34c0a2ec4c](https://linux-hardware.org/?probe=34c0a2ec4c) | Nov 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [8ef23bbac8](https://linux-hardware.org/?probe=8ef23bbac8) | Nov 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [003be2f197](https://linux-hardware.org/?probe=003be2f197) | Nov 07, 2023 |
| Dell          | 0D881F A05                  | Desktop     | [9b3ffcb3d5](https://linux-hardware.org/?probe=9b3ffcb3d5) | Nov 07, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [01884ea8de](https://linux-hardware.org/?probe=01884ea8de) | Nov 07, 2023 |
| Dell          | Precision 3561              | Notebook    | [8fd1f7d515](https://linux-hardware.org/?probe=8fd1f7d515) | Nov 06, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [b5e4afb8e9](https://linux-hardware.org/?probe=b5e4afb8e9) | Nov 06, 2023 |
| Lenovo        | ThinkPad T480 20L6S5VP3U    | Notebook    | [ea70f0e597](https://linux-hardware.org/?probe=ea70f0e597) | Nov 05, 2023 |
| Dell          | 08WKV3 A00                  | Desktop     | [e16dbbaf8b](https://linux-hardware.org/?probe=e16dbbaf8b) | Nov 05, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [4f690a4297](https://linux-hardware.org/?probe=4f690a4297) | Nov 05, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [f154c5979f](https://linux-hardware.org/?probe=f154c5979f) | Nov 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [85733c0ec0](https://linux-hardware.org/?probe=85733c0ec0) | Nov 05, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [8a4147b40a](https://linux-hardware.org/?probe=8a4147b40a) | Nov 05, 2023 |
| Tactus        | GeoFlex 140                 | Convertible | [a386eceffe](https://linux-hardware.org/?probe=a386eceffe) | Nov 05, 2023 |
| Tactus        | GeoFlex 140                 | Convertible | [1e6407d9d5](https://linux-hardware.org/?probe=1e6407d9d5) | Nov 04, 2023 |
| Gigabyte      | H81M-DS2                    | Desktop     | [5ac9818b1f](https://linux-hardware.org/?probe=5ac9818b1f) | Nov 03, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [c9e7b12e63](https://linux-hardware.org/?probe=c9e7b12e63) | Nov 03, 2023 |
| Dell          | Latitude E7470              | Notebook    | [343fdc858a](https://linux-hardware.org/?probe=343fdc858a) | Nov 03, 2023 |
| Gigabyte      | P35-DS3L                    | Desktop     | [c2df6f267b](https://linux-hardware.org/?probe=c2df6f267b) | Nov 03, 2023 |
| Acer          | Aspire A515-43              | Notebook    | [6aa1f3a294](https://linux-hardware.org/?probe=6aa1f3a294) | Nov 02, 2023 |
| Acer          | Aspire A515-43              | Notebook    | [3e65346dfd](https://linux-hardware.org/?probe=3e65346dfd) | Nov 02, 2023 |
| ASRock        | H61M-VS                     | Desktop     | [677490b7c2](https://linux-hardware.org/?probe=677490b7c2) | Nov 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [0f4435d620](https://linux-hardware.org/?probe=0f4435d620) | Nov 02, 2023 |
| Lenovo        | ThinkBook 14p Gen 3 21EJ    | Notebook    | [cde7923bf2](https://linux-hardware.org/?probe=cde7923bf2) | Nov 01, 2023 |
| MSI           | B450-A PRO                  | Desktop     | [f0b1ef4bc8](https://linux-hardware.org/?probe=f0b1ef4bc8) | Nov 01, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [50a30d4ebd](https://linux-hardware.org/?probe=50a30d4ebd) | Nov 01, 2023 |
| Acer          | Aspire A517-52G             | Notebook    | [f65225d50a](https://linux-hardware.org/?probe=f65225d50a) | Nov 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [5acc8f68a0](https://linux-hardware.org/?probe=5acc8f68a0) | Nov 01, 2023 |
| Acer          | Aspire A517-52G             | Notebook    | [69f7a5ebed](https://linux-hardware.org/?probe=69f7a5ebed) | Nov 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [8a2a3561ab](https://linux-hardware.org/?probe=8a2a3561ab) | Nov 01, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [7271f0fc8c](https://linux-hardware.org/?probe=7271f0fc8c) | Nov 01, 2023 |
| HP            | 2AF7                        | Desktop     | [0a2c239b75](https://linux-hardware.org/?probe=0a2c239b75) | Nov 01, 2023 |
| Dell          | Latitude 7290               | Notebook    | [b7170343fb](https://linux-hardware.org/?probe=b7170343fb) | Oct 31, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [98d01105c7](https://linux-hardware.org/?probe=98d01105c7) | Oct 31, 2023 |
| ASRock        | H110 Pro BTC+               | Desktop     | [c889a29b7f](https://linux-hardware.org/?probe=c889a29b7f) | Oct 31, 2023 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [77d9982cf2](https://linux-hardware.org/?probe=77d9982cf2) | Oct 31, 2023 |
| Acer          | Aspire AV15-51              | Notebook    | [84064baf19](https://linux-hardware.org/?probe=84064baf19) | Oct 31, 2023 |
| Lenovo        | Yoga 9 14IAP7 82LU          | Convertible | [babfdba8f2](https://linux-hardware.org/?probe=babfdba8f2) | Oct 30, 2023 |
| Dell          | Latitude 5530               | Notebook    | [1731342e23](https://linux-hardware.org/?probe=1731342e23) | Oct 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [986edacf9a](https://linux-hardware.org/?probe=986edacf9a) | Oct 30, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [9b3c09e73a](https://linux-hardware.org/?probe=9b3c09e73a) | Oct 27, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [40769bf0a3](https://linux-hardware.org/?probe=40769bf0a3) | Oct 27, 2023 |
| MSI           | B250M PRO-VDH               | Desktop     | [c3d5a72f41](https://linux-hardware.org/?probe=c3d5a72f41) | Oct 27, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [3831a70240](https://linux-hardware.org/?probe=3831a70240) | Oct 27, 2023 |
| EXTRA Comp... | MS-1758                     | Notebook    | [eced546e79](https://linux-hardware.org/?probe=eced546e79) | Oct 26, 2023 |
| HP            | Pavilion 17                 | Notebook    | [9eb519ce8c](https://linux-hardware.org/?probe=9eb519ce8c) | Oct 26, 2023 |
| HP            | Pavilion 17                 | Notebook    | [9b004ab742](https://linux-hardware.org/?probe=9b004ab742) | Oct 26, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [f956ab0313](https://linux-hardware.org/?probe=f956ab0313) | Oct 26, 2023 |
| SYWZ          | S210H Series                | Desktop     | [9239922f80](https://linux-hardware.org/?probe=9239922f80) | Oct 26, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [e25ec0e229](https://linux-hardware.org/?probe=e25ec0e229) | Oct 25, 2023 |
| HP            | Pavilion g7                 | Notebook    | [3bd963fd9e](https://linux-hardware.org/?probe=3bd963fd9e) | Oct 24, 2023 |
| ASUSTek       | K56CM                       | Notebook    | [a5437fcab8](https://linux-hardware.org/?probe=a5437fcab8) | Oct 24, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [c74b24edc0](https://linux-hardware.org/?probe=c74b24edc0) | Oct 23, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [4f269eeaa7](https://linux-hardware.org/?probe=4f269eeaa7) | Oct 23, 2023 |
| ASRockRack    | ROMED8-2T                   | Desktop     | [d71e04d478](https://linux-hardware.org/?probe=d71e04d478) | Oct 23, 2023 |
| Lenovo        | IdeaPad 3 14ARE05 81W3      | Notebook    | [55c5bbce9f](https://linux-hardware.org/?probe=55c5bbce9f) | Oct 23, 2023 |
| Gigabyte      | Z77X-UP7                    | Desktop     | [806cdb2bef](https://linux-hardware.org/?probe=806cdb2bef) | Oct 23, 2023 |
| AZW           | SEi                         | Notebook    | [94602bd41b](https://linux-hardware.org/?probe=94602bd41b) | Oct 22, 2023 |
| Gigabyte      | GA-890FXA-UD5               | Desktop     | [bd8cdfe190](https://linux-hardware.org/?probe=bd8cdfe190) | Oct 22, 2023 |
| HP            | ProBook 4340s               | Notebook    | [8746af78f7](https://linux-hardware.org/?probe=8746af78f7) | Oct 22, 2023 |
| ECS           | CHICAGO2                    | Desktop     | [e33ec52f5a](https://linux-hardware.org/?probe=e33ec52f5a) | Oct 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [130d199934](https://linux-hardware.org/?probe=130d199934) | Oct 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [f23d0ff7da](https://linux-hardware.org/?probe=f23d0ff7da) | Oct 20, 2023 |
| Dell          | Latitude E7470              | Notebook    | [4870f90403](https://linux-hardware.org/?probe=4870f90403) | Oct 20, 2023 |
| MACHENIKE     | MACHCREATOR-16              | Notebook    | [91f29a5a63](https://linux-hardware.org/?probe=91f29a5a63) | Oct 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [09b04f5fd5](https://linux-hardware.org/?probe=09b04f5fd5) | Oct 20, 2023 |
| Lenovo        | ThinkBook 14p Gen 3 21EJ    | Notebook    | [4bfe18fe76](https://linux-hardware.org/?probe=4bfe18fe76) | Oct 20, 2023 |
| Lenovo        | ThinkBook 14p Gen 3 21EJ    | Notebook    | [e83ad29e5e](https://linux-hardware.org/?probe=e83ad29e5e) | Oct 20, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [a0cdc0c3e1](https://linux-hardware.org/?probe=a0cdc0c3e1) | Oct 19, 2023 |
| Fujitsu       | D2990-A3 S26361-D2990-A3    | Desktop     | [c2215ccabb](https://linux-hardware.org/?probe=c2215ccabb) | Oct 19, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [aad7482915](https://linux-hardware.org/?probe=aad7482915) | Oct 19, 2023 |
| HP            | G60                         | Notebook    | [3c3f75c072](https://linux-hardware.org/?probe=3c3f75c072) | Oct 19, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [495a705c9e](https://linux-hardware.org/?probe=495a705c9e) | Oct 18, 2023 |
| Dell          | Precision 7520              | Notebook    | [bd78f68578](https://linux-hardware.org/?probe=bd78f68578) | Oct 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [6fe57753a4](https://linux-hardware.org/?probe=6fe57753a4) | Oct 17, 2023 |
| Lenovo        | 01KN179                     | Server      | [9f36a4143d](https://linux-hardware.org/?probe=9f36a4143d) | Oct 16, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [02bc0ccf6d](https://linux-hardware.org/?probe=02bc0ccf6d) | Oct 16, 2023 |
| AMI           | Intel                       | Convertible | [38a3df30fe](https://linux-hardware.org/?probe=38a3df30fe) | Oct 15, 2023 |
| Dell          | Latitude E7470              | Notebook    | [59258fc186](https://linux-hardware.org/?probe=59258fc186) | Oct 15, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | Notebook    | [88c47cfb66](https://linux-hardware.org/?probe=88c47cfb66) | Oct 15, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [92049beb26](https://linux-hardware.org/?probe=92049beb26) | Oct 15, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [3eff97b04d](https://linux-hardware.org/?probe=3eff97b04d) | Oct 15, 2023 |
| HP            | 829A                        | Mini pc     | [f9af7b48fe](https://linux-hardware.org/?probe=f9af7b48fe) | Oct 14, 2023 |
| MSI           | B560M PRO                   | Desktop     | [1dba250310](https://linux-hardware.org/?probe=1dba250310) | Oct 14, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [a03109d57a](https://linux-hardware.org/?probe=a03109d57a) | Oct 14, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [007ce9ca02](https://linux-hardware.org/?probe=007ce9ca02) | Oct 14, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [09a90189ec](https://linux-hardware.org/?probe=09a90189ec) | Oct 14, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [f18ac93db8](https://linux-hardware.org/?probe=f18ac93db8) | Oct 13, 2023 |
| MSI           | B85-G43                     | Desktop     | [8684995c92](https://linux-hardware.org/?probe=8684995c92) | Oct 13, 2023 |
| Dell          | Latitude 7490               | Notebook    | [b5e38fe27e](https://linux-hardware.org/?probe=b5e38fe27e) | Oct 13, 2023 |
| Acer          | Aspire 5250                 | Notebook    | [bef1086dfe](https://linux-hardware.org/?probe=bef1086dfe) | Oct 12, 2023 |
| HP            | EliteBook 8770w             | Notebook    | [bf26581f5d](https://linux-hardware.org/?probe=bf26581f5d) | Oct 12, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | Notebook    | [f48331f12b](https://linux-hardware.org/?probe=f48331f12b) | Oct 12, 2023 |
| Dell          | Vostro 5490                 | Notebook    | [616aecbfbd](https://linux-hardware.org/?probe=616aecbfbd) | Oct 11, 2023 |
| Alienware     | m16 R1                      | Notebook    | [6ea5ba513f](https://linux-hardware.org/?probe=6ea5ba513f) | Oct 11, 2023 |
| Alienware     | m16 R1                      | Notebook    | [f9c4374e7c](https://linux-hardware.org/?probe=f9c4374e7c) | Oct 11, 2023 |
| Dell          | Latitude 5511               | Notebook    | [164cc57420](https://linux-hardware.org/?probe=164cc57420) | Oct 10, 2023 |
| Dell          | Latitude 5511               | Notebook    | [9827df8ea8](https://linux-hardware.org/?probe=9827df8ea8) | Oct 10, 2023 |
| Dell          | Latitude 5530               | Notebook    | [95ec4384f9](https://linux-hardware.org/?probe=95ec4384f9) | Oct 10, 2023 |
| Dell          | Latitude 5530               | Notebook    | [4d218edfa4](https://linux-hardware.org/?probe=4d218edfa4) | Oct 10, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [3ba4207fd0](https://linux-hardware.org/?probe=3ba4207fd0) | Oct 09, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [f6dac1e5f6](https://linux-hardware.org/?probe=f6dac1e5f6) | Oct 09, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | Notebook    | [1996d5a1ff](https://linux-hardware.org/?probe=1996d5a1ff) | Oct 08, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [84ff0a9a08](https://linux-hardware.org/?probe=84ff0a9a08) | Oct 07, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [1505f63948](https://linux-hardware.org/?probe=1505f63948) | Oct 07, 2023 |
| Medion        | E15302                      | Notebook    | [d26c76cedf](https://linux-hardware.org/?probe=d26c76cedf) | Oct 07, 2023 |
| TUXEDO        | Book XP15 / XP17 Gen12      | Notebook    | [5ff0e17804](https://linux-hardware.org/?probe=5ff0e17804) | Oct 07, 2023 |
| ATOPNUC       | MA90                        | Mini pc     | [5ac03d658c](https://linux-hardware.org/?probe=5ac03d658c) | Oct 07, 2023 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [7e01bc1824](https://linux-hardware.org/?probe=7e01bc1824) | Oct 06, 2023 |
| ASUSTek       | Z87-PRO                     | Desktop     | [31248aa2bf](https://linux-hardware.org/?probe=31248aa2bf) | Oct 06, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [5b84610e15](https://linux-hardware.org/?probe=5b84610e15) | Oct 06, 2023 |
| Lenovo        | Yoga Creator 7 15IMH05 8... | Notebook    | [e796c2f9ba](https://linux-hardware.org/?probe=e796c2f9ba) | Oct 05, 2023 |
| Dell          | Latitude 7490               | Notebook    | [ff1fcbaff6](https://linux-hardware.org/?probe=ff1fcbaff6) | Oct 04, 2023 |
| Dell          | Latitude 7490               | Notebook    | [7eca4901d4](https://linux-hardware.org/?probe=7eca4901d4) | Oct 04, 2023 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [57b1771805](https://linux-hardware.org/?probe=57b1771805) | Oct 04, 2023 |
| Lenovo        | IdeaPad S540-13IML 81XA     | Notebook    | [2fdd309c6a](https://linux-hardware.org/?probe=2fdd309c6a) | Oct 04, 2023 |
| ASUSTek       | E2KM1I-DELUXE               | Desktop     | [bb9493309a](https://linux-hardware.org/?probe=bb9493309a) | Oct 04, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [3f7231bda4](https://linux-hardware.org/?probe=3f7231bda4) | Oct 03, 2023 |
| ASUSTek       | ROG Strix G513IM_G513IM     | Notebook    | [f349819e0a](https://linux-hardware.org/?probe=f349819e0a) | Oct 02, 2023 |
| Google        | Blorb                       | Notebook    | [04e37bafe3](https://linux-hardware.org/?probe=04e37bafe3) | Oct 02, 2023 |
| ASUSTek       | ROG Strix G513IM_G513IM     | Notebook    | [122f1d4ca8](https://linux-hardware.org/?probe=122f1d4ca8) | Oct 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [f8ee109cbd](https://linux-hardware.org/?probe=f8ee109cbd) | Oct 01, 2023 |
| Schenker      | VIA 15 Pro (M22)            | Notebook    | [1919690674](https://linux-hardware.org/?probe=1919690674) | Oct 01, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | Notebook    | [ffd2e0d99d](https://linux-hardware.org/?probe=ffd2e0d99d) | Oct 01, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [1448f32279](https://linux-hardware.org/?probe=1448f32279) | Oct 01, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [48ff113276](https://linux-hardware.org/?probe=48ff113276) | Sep 30, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [3421ba07f9](https://linux-hardware.org/?probe=3421ba07f9) | Sep 30, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [480316a0da](https://linux-hardware.org/?probe=480316a0da) | Sep 30, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [cd9628c344](https://linux-hardware.org/?probe=cd9628c344) | Sep 29, 2023 |
| Alienware     | x15 R1                      | Notebook    | [a34b343fce](https://linux-hardware.org/?probe=a34b343fce) | Sep 29, 2023 |
| ASUSTek       | EB1501P                     | Desktop     | [df48fa7e96](https://linux-hardware.org/?probe=df48fa7e96) | Sep 29, 2023 |
| ASUSTek       | K72Jr                       | Notebook    | [9167494336](https://linux-hardware.org/?probe=9167494336) | Sep 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [a329c5630e](https://linux-hardware.org/?probe=a329c5630e) | Sep 28, 2023 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [e54490e96a](https://linux-hardware.org/?probe=e54490e96a) | Sep 27, 2023 |
| HP            | EliteBook 8770w             | Notebook    | [3286090099](https://linux-hardware.org/?probe=3286090099) | Sep 27, 2023 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [2f574aa287](https://linux-hardware.org/?probe=2f574aa287) | Sep 27, 2023 |
| Acer          | FX58M                       | Desktop     | [e24f36e0bd](https://linux-hardware.org/?probe=e24f36e0bd) | Sep 26, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [37840dad1c](https://linux-hardware.org/?probe=37840dad1c) | Sep 26, 2023 |
| Lenovo        | B480 20140                  | Notebook    | [960fe0be2b](https://linux-hardware.org/?probe=960fe0be2b) | Sep 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [56cd5e0bfd](https://linux-hardware.org/?probe=56cd5e0bfd) | Sep 25, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [2691aa5f87](https://linux-hardware.org/?probe=2691aa5f87) | Sep 24, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [a834cee874](https://linux-hardware.org/?probe=a834cee874) | Sep 24, 2023 |
| ASRock        | ALiveXFire-eSATA2           | Desktop     | [7e69c8e2e1](https://linux-hardware.org/?probe=7e69c8e2e1) | Sep 23, 2023 |
| Lenovo        | ThinkPad P17 Gen 1 20SQS... | Notebook    | [05bf70d208](https://linux-hardware.org/?probe=05bf70d208) | Sep 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [ad1f9f63c0](https://linux-hardware.org/?probe=ad1f9f63c0) | Sep 22, 2023 |
| Dell          | 0D881F A05                  | Desktop     | [583c577b02](https://linux-hardware.org/?probe=583c577b02) | Sep 22, 2023 |
| ASUSTek       | TUF Z390-PRO GAMING         | Desktop     | [16fe0e3ba6](https://linux-hardware.org/?probe=16fe0e3ba6) | Sep 22, 2023 |
| ASUSTek       | TUF Z390-PRO GAMING         | Desktop     | [aab34fa582](https://linux-hardware.org/?probe=aab34fa582) | Sep 22, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [28c84c64c1](https://linux-hardware.org/?probe=28c84c64c1) | Sep 21, 2023 |
| HP            | 18E7                        | Desktop     | [ba0cb8996d](https://linux-hardware.org/?probe=ba0cb8996d) | Sep 21, 2023 |
| Gigabyte      | H310M H                     | Desktop     | [389282109e](https://linux-hardware.org/?probe=389282109e) | Sep 21, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [c7142a0d96](https://linux-hardware.org/?probe=c7142a0d96) | Sep 20, 2023 |
| Toshiba       | Satellite Pro C70-B         | Notebook    | [a24c6808ba](https://linux-hardware.org/?probe=a24c6808ba) | Sep 20, 2023 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [e753271d63](https://linux-hardware.org/?probe=e753271d63) | Sep 19, 2023 |
| Dell          | Precision 7520              | Notebook    | [99e70bdd81](https://linux-hardware.org/?probe=99e70bdd81) | Sep 19, 2023 |
| ASRock        | Z68 Pro3                    | Desktop     | [4ffee8598b](https://linux-hardware.org/?probe=4ffee8598b) | Sep 19, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [c8a7f18e5d](https://linux-hardware.org/?probe=c8a7f18e5d) | Sep 19, 2023 |
| Dell          | Precision 7520              | Notebook    | [89f1a6a0a5](https://linux-hardware.org/?probe=89f1a6a0a5) | Sep 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [cbfe8b032d](https://linux-hardware.org/?probe=cbfe8b032d) | Sep 18, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [144dcee0ae](https://linux-hardware.org/?probe=144dcee0ae) | Sep 18, 2023 |
| Dell          | Inspiron 5520               | Notebook    | [91404ec81d](https://linux-hardware.org/?probe=91404ec81d) | Sep 17, 2023 |
| Gigabyte      | H310M H                     | Desktop     | [5a9f4e8791](https://linux-hardware.org/?probe=5a9f4e8791) | Sep 17, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [e6db76aa66](https://linux-hardware.org/?probe=e6db76aa66) | Sep 17, 2023 |
| HP            | Compaq 6820s                | Notebook    | [99a625283d](https://linux-hardware.org/?probe=99a625283d) | Sep 16, 2023 |
| HP            | Compaq 6820s                | Notebook    | [2ae8b9ac9d](https://linux-hardware.org/?probe=2ae8b9ac9d) | Sep 16, 2023 |
| ASUSTek       | Z97-PRO                     | Desktop     | [37d6d12772](https://linux-hardware.org/?probe=37d6d12772) | Sep 15, 2023 |
| Lenovo        | 1037 SDK0Q40104 WIN 3305... | Server      | [fabf2bef4c](https://linux-hardware.org/?probe=fabf2bef4c) | Sep 15, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [a32457e14d](https://linux-hardware.org/?probe=a32457e14d) | Sep 15, 2023 |
| HP            | 0A9Ch                       | Desktop     | [4894ac01b8](https://linux-hardware.org/?probe=4894ac01b8) | Sep 14, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [15256fdeb2](https://linux-hardware.org/?probe=15256fdeb2) | Sep 14, 2023 |
| Notebook      | P65_P67SA                   | Notebook    | [4d11ae0ff7](https://linux-hardware.org/?probe=4d11ae0ff7) | Sep 13, 2023 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [8f3c4bff98](https://linux-hardware.org/?probe=8f3c4bff98) | Sep 13, 2023 |
| HP            | 1998                        | Desktop     | [c3451afea8](https://linux-hardware.org/?probe=c3451afea8) | Sep 11, 2023 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [53139247c9](https://linux-hardware.org/?probe=53139247c9) | Sep 10, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [938cec3228](https://linux-hardware.org/?probe=938cec3228) | Sep 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [4e30077177](https://linux-hardware.org/?probe=4e30077177) | Sep 08, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [7ce5ebe4bc](https://linux-hardware.org/?probe=7ce5ebe4bc) | Sep 07, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [eb92b04384](https://linux-hardware.org/?probe=eb92b04384) | Sep 06, 2023 |
| ASUSTek       | X580VD                      | Notebook    | [989134a7c5](https://linux-hardware.org/?probe=989134a7c5) | Sep 06, 2023 |
| Alienware     | 0H869M A00                  | Desktop     | [64132daa63](https://linux-hardware.org/?probe=64132daa63) | Sep 06, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [cf9c65c6f4](https://linux-hardware.org/?probe=cf9c65c6f4) | Sep 06, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [d2ae9b900d](https://linux-hardware.org/?probe=d2ae9b900d) | Sep 06, 2023 |
| Dell          | Latitude 7490               | Notebook    | [2a945e76de](https://linux-hardware.org/?probe=2a945e76de) | Sep 05, 2023 |
| Dell          | Inspiron 3480               | Notebook    | [3d639d27ba](https://linux-hardware.org/?probe=3d639d27ba) | Sep 05, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [1cd7fc15b1](https://linux-hardware.org/?probe=1cd7fc15b1) | Sep 05, 2023 |
| ASUSTek       | S400CA                      | Notebook    | [453335f199](https://linux-hardware.org/?probe=453335f199) | Sep 04, 2023 |
| ASUSTek       | K52JB                       | Notebook    | [7944dc4ca2](https://linux-hardware.org/?probe=7944dc4ca2) | Sep 04, 2023 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | Notebook    | [2dff249b45](https://linux-hardware.org/?probe=2dff249b45) | Sep 04, 2023 |
| Dell          | Latitude E6500              | Notebook    | [6199709334](https://linux-hardware.org/?probe=6199709334) | Sep 04, 2023 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | Notebook    | [515a81a0d1](https://linux-hardware.org/?probe=515a81a0d1) | Sep 03, 2023 |
| Dell          | Latitude E6500              | Notebook    | [308d8d0f19](https://linux-hardware.org/?probe=308d8d0f19) | Sep 03, 2023 |
| Fujitsu Si... | LIFEBOOK E8410              | Notebook    | [31618d06c6](https://linux-hardware.org/?probe=31618d06c6) | Sep 02, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [85cc9860f3](https://linux-hardware.org/?probe=85cc9860f3) | Sep 02, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F6... | Notebook    | [2fc5b41456](https://linux-hardware.org/?probe=2fc5b41456) | Sep 02, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [1aeb1ffd17](https://linux-hardware.org/?probe=1aeb1ffd17) | Sep 02, 2023 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [9028ba6c0f](https://linux-hardware.org/?probe=9028ba6c0f) | Sep 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [7dabe0d117](https://linux-hardware.org/?probe=7dabe0d117) | Sep 01, 2023 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [b132ff749e](https://linux-hardware.org/?probe=b132ff749e) | Sep 01, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [d80ee341d8](https://linux-hardware.org/?probe=d80ee341d8) | Sep 01, 2023 |
| Dell          | XPS 9315                    | Notebook    | [5676f0c210](https://linux-hardware.org/?probe=5676f0c210) | Aug 31, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F6... | Notebook    | [3384884acc](https://linux-hardware.org/?probe=3384884acc) | Aug 31, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [17e971c3fb](https://linux-hardware.org/?probe=17e971c3fb) | Aug 31, 2023 |
| Sony          | VPCEC390X                   | Notebook    | [ddad567e2a](https://linux-hardware.org/?probe=ddad567e2a) | Aug 31, 2023 |
| ASUSTek       | PRIME X299-DELUXE           | Desktop     | [d9a8673516](https://linux-hardware.org/?probe=d9a8673516) | Aug 31, 2023 |
| AZW           | MINI S                      | Desktop     | [fb828c24eb](https://linux-hardware.org/?probe=fb828c24eb) | Aug 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [2906fc34f6](https://linux-hardware.org/?probe=2906fc34f6) | Aug 30, 2023 |
| Gigabyte      | H310M H                     | Desktop     | [ca4ddb2663](https://linux-hardware.org/?probe=ca4ddb2663) | Aug 29, 2023 |
| HP            | 212B                        | Desktop     | [80b2496334](https://linux-hardware.org/?probe=80b2496334) | Aug 29, 2023 |
| Fujitsu       | LIFEBOOK U9312              | Notebook    | [891b276812](https://linux-hardware.org/?probe=891b276812) | Aug 28, 2023 |
| ASUSTek       | Pro WS 565-ACE              | Desktop     | [ae73127da5](https://linux-hardware.org/?probe=ae73127da5) | Aug 28, 2023 |
| Dell          | Vostro 3501                 | Notebook    | [0211379a67](https://linux-hardware.org/?probe=0211379a67) | Aug 27, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | Notebook    | [69a4a078cd](https://linux-hardware.org/?probe=69a4a078cd) | Aug 27, 2023 |
| HP            | 18E7                        | Desktop     | [0b94065a0f](https://linux-hardware.org/?probe=0b94065a0f) | Aug 27, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [cf2cba5c59](https://linux-hardware.org/?probe=cf2cba5c59) | Aug 26, 2023 |
| mPTech        | ARC 11.6 128GB HD           | Notebook    | [4167149587](https://linux-hardware.org/?probe=4167149587) | Aug 26, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [efa1e38911](https://linux-hardware.org/?probe=efa1e38911) | Aug 26, 2023 |
| MSI           | 990FXA GAMING               | Desktop     | [813d9c9c10](https://linux-hardware.org/?probe=813d9c9c10) | Aug 26, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [5004de7897](https://linux-hardware.org/?probe=5004de7897) | Aug 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [d0de544ecd](https://linux-hardware.org/?probe=d0de544ecd) | Aug 25, 2023 |
| Lenovo        | IdeaPad Z580                | Notebook    | [b84eb0a6fa](https://linux-hardware.org/?probe=b84eb0a6fa) | Aug 24, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [0161911081](https://linux-hardware.org/?probe=0161911081) | Aug 24, 2023 |
| MSI           | GL65 9SE                    | Notebook    | [aa162e5634](https://linux-hardware.org/?probe=aa162e5634) | Aug 22, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [aee37b4a93](https://linux-hardware.org/?probe=aee37b4a93) | Aug 21, 2023 |
| Dell          | 0D881F A05                  | Desktop     | [8c6f4a2e1c](https://linux-hardware.org/?probe=8c6f4a2e1c) | Aug 21, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [4d631eed0e](https://linux-hardware.org/?probe=4d631eed0e) | Aug 21, 2023 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [bb5a7dc0d8](https://linux-hardware.org/?probe=bb5a7dc0d8) | Aug 21, 2023 |
| HP            | ElitePad 1000 G2            | Notebook    | [bb21bd2dbc](https://linux-hardware.org/?probe=bb21bd2dbc) | Aug 21, 2023 |
| Fujitsu       | D3602-A1 S26361-D3602-A1    | Desktop     | [8144c6d466](https://linux-hardware.org/?probe=8144c6d466) | Aug 21, 2023 |
| Dell          | Latitude E6520              | Notebook    | [923d01a34f](https://linux-hardware.org/?probe=923d01a34f) | Aug 21, 2023 |
| Schenker      | XMG PRO (E23)               | Notebook    | [9b1639077c](https://linux-hardware.org/?probe=9b1639077c) | Aug 20, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [df48f3ca66](https://linux-hardware.org/?probe=df48f3ca66) | Aug 19, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [ed75b0702f](https://linux-hardware.org/?probe=ed75b0702f) | Aug 19, 2023 |
| MSI           | B250M MORTAR                | Desktop     | [fc97ccab18](https://linux-hardware.org/?probe=fc97ccab18) | Aug 17, 2023 |
| ASUSTek       | TUF Gaming A520M-PLUS WI... | Desktop     | [1962f7a581](https://linux-hardware.org/?probe=1962f7a581) | Aug 17, 2023 |
| Intel         | D53427RKE G87971-402        | Desktop     | [433dcaffa6](https://linux-hardware.org/?probe=433dcaffa6) | Aug 17, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [ace741b68a](https://linux-hardware.org/?probe=ace741b68a) | Aug 17, 2023 |
| ASRock        | Z77 Extreme4                | Desktop     | [e9f564475b](https://linux-hardware.org/?probe=e9f564475b) | Aug 16, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [41b9b0bfc9](https://linux-hardware.org/?probe=41b9b0bfc9) | Aug 14, 2023 |
| ASUSTek       | N53SV                       | Notebook    | [8643d609f2](https://linux-hardware.org/?probe=8643d609f2) | Aug 14, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [29aa72820d](https://linux-hardware.org/?probe=29aa72820d) | Aug 14, 2023 |
| Dell          | 0D881F A05                  | Desktop     | [83dd0f7fe7](https://linux-hardware.org/?probe=83dd0f7fe7) | Aug 14, 2023 |
| LG Electro... | 17Z90N-V.AA72A8             | Notebook    | [28e815418c](https://linux-hardware.org/?probe=28e815418c) | Aug 13, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [7ad086cf8b](https://linux-hardware.org/?probe=7ad086cf8b) | Aug 13, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [e2fe66aca4](https://linux-hardware.org/?probe=e2fe66aca4) | Aug 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [307eb30c27](https://linux-hardware.org/?probe=307eb30c27) | Aug 13, 2023 |
| Gigabyte      | Z690 AORUS MASTER           | Desktop     | [760a5d6077](https://linux-hardware.org/?probe=760a5d6077) | Aug 13, 2023 |
| Dell          | 0GNVHC A00                  | Desktop     | [27e3be4942](https://linux-hardware.org/?probe=27e3be4942) | Aug 12, 2023 |
| ASUSTek       | CM1630                      | Desktop     | [dfd52e2852](https://linux-hardware.org/?probe=dfd52e2852) | Aug 12, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [b4b9fa2d17](https://linux-hardware.org/?probe=b4b9fa2d17) | Aug 12, 2023 |
| ASUSTek       | CM1630                      | Desktop     | [d8f56bcdaf](https://linux-hardware.org/?probe=d8f56bcdaf) | Aug 12, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [181db8cf87](https://linux-hardware.org/?probe=181db8cf87) | Aug 11, 2023 |
| Medion        | P651x series                | Notebook    | [46505da47d](https://linux-hardware.org/?probe=46505da47d) | Aug 11, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [ba03034ac5](https://linux-hardware.org/?probe=ba03034ac5) | Aug 10, 2023 |
| Gigabyte      | Z690 AORUS MASTER           | Desktop     | [be6c815f39](https://linux-hardware.org/?probe=be6c815f39) | Aug 10, 2023 |
| ASUSTek       | Q87M-E                      | Desktop     | [0dee84c129](https://linux-hardware.org/?probe=0dee84c129) | Aug 10, 2023 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | Notebook    | [d97ae334a3](https://linux-hardware.org/?probe=d97ae334a3) | Aug 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [f28e4b71d6](https://linux-hardware.org/?probe=f28e4b71d6) | Aug 09, 2023 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [58d7c4be4c](https://linux-hardware.org/?probe=58d7c4be4c) | Aug 08, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [068b8c5a6f](https://linux-hardware.org/?probe=068b8c5a6f) | Aug 07, 2023 |
| ASRock        | N68C-S UCC                  | Desktop     | [ebe7ed3f69](https://linux-hardware.org/?probe=ebe7ed3f69) | Aug 07, 2023 |
| Timi          | RedmiBook 14-APCS           | Notebook    | [a0a289f4ee](https://linux-hardware.org/?probe=a0a289f4ee) | Aug 06, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [ec1bd43523](https://linux-hardware.org/?probe=ec1bd43523) | Aug 05, 2023 |
| Dell          | Inspiron 3520               | Notebook    | [00b2c0458a](https://linux-hardware.org/?probe=00b2c0458a) | Aug 05, 2023 |
| HP            | 2AF7                        | Desktop     | [655c896815](https://linux-hardware.org/?probe=655c896815) | Aug 04, 2023 |
| Lenovo        | ThinkPad T480 20L50000MC    | Notebook    | [341698801e](https://linux-hardware.org/?probe=341698801e) | Aug 04, 2023 |
| Dell          | Inspiron 3520               | Notebook    | [6bef2ead01](https://linux-hardware.org/?probe=6bef2ead01) | Aug 04, 2023 |
| Dell          | Latitude 5530               | Notebook    | [dd85033508](https://linux-hardware.org/?probe=dd85033508) | Aug 03, 2023 |
| System76      | Galago Pro                  | Notebook    | [2677fc9a99](https://linux-hardware.org/?probe=2677fc9a99) | Aug 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [3bb1942723](https://linux-hardware.org/?probe=3bb1942723) | Aug 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [7748df9ae9](https://linux-hardware.org/?probe=7748df9ae9) | Aug 01, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [48c7912f46](https://linux-hardware.org/?probe=48c7912f46) | Aug 01, 2023 |
| MSI           | PRO Z690-A                  | Desktop     | [19f4cb0c69](https://linux-hardware.org/?probe=19f4cb0c69) | Jul 31, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [be7baf7741](https://linux-hardware.org/?probe=be7baf7741) | Jul 31, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [3b0862f434](https://linux-hardware.org/?probe=3b0862f434) | Jul 31, 2023 |
| Dell          | Precision 3571              | Notebook    | [83a85ddae5](https://linux-hardware.org/?probe=83a85ddae5) | Jul 31, 2023 |
| Dell          | Inspiron 16 7610            | Notebook    | [e7befe5a64](https://linux-hardware.org/?probe=e7befe5a64) | Jul 29, 2023 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [0ed7dfdf32](https://linux-hardware.org/?probe=0ed7dfdf32) | Jul 29, 2023 |
| MSI           | X99S SLI PLUS               | Desktop     | [edf7fd3a91](https://linux-hardware.org/?probe=edf7fd3a91) | Jul 28, 2023 |
| Gigabyte      | EP45T-UD3LR                 | Desktop     | [c2928283bd](https://linux-hardware.org/?probe=c2928283bd) | Jul 28, 2023 |
| MSI           | PRO Z690-A                  | Desktop     | [f1a5d69727](https://linux-hardware.org/?probe=f1a5d69727) | Jul 28, 2023 |
| Supermicro    | C7H61                       | Desktop     | [57c9a4eeff](https://linux-hardware.org/?probe=57c9a4eeff) | Jul 27, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [810ff8bbd6](https://linux-hardware.org/?probe=810ff8bbd6) | Jul 26, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [3548050f99](https://linux-hardware.org/?probe=3548050f99) | Jul 26, 2023 |
| Lenovo        | ThinkPad E580 20KS003LLM    | Notebook    | [9bc92a8ef2](https://linux-hardware.org/?probe=9bc92a8ef2) | Jul 26, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [7b7287762f](https://linux-hardware.org/?probe=7b7287762f) | Jul 26, 2023 |
| HP            | G60                         | Notebook    | [4d64158286](https://linux-hardware.org/?probe=4d64158286) | Jul 26, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [914560761d](https://linux-hardware.org/?probe=914560761d) | Jul 25, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [4a1a31cb65](https://linux-hardware.org/?probe=4a1a31cb65) | Jul 25, 2023 |
| Gigabyte      | P67A-UD3-B3                 | Desktop     | [26e7657871](https://linux-hardware.org/?probe=26e7657871) | Jul 23, 2023 |
| MSI           | Z87 MPOWER                  | Desktop     | [dcbda0f556](https://linux-hardware.org/?probe=dcbda0f556) | Jul 23, 2023 |
| HP            | Presario CQ62               | Notebook    | [b736890f88](https://linux-hardware.org/?probe=b736890f88) | Jul 23, 2023 |
| Acer          | Aspire A517-52              | Notebook    | [25fd4c6993](https://linux-hardware.org/?probe=25fd4c6993) | Jul 22, 2023 |
| Acer          | Aspire A517-52              | Notebook    | [e07c3205da](https://linux-hardware.org/?probe=e07c3205da) | Jul 22, 2023 |
| Medion        | H110H4-EM2                  | Desktop     | [443b61cb44](https://linux-hardware.org/?probe=443b61cb44) | Jul 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [e948334857](https://linux-hardware.org/?probe=e948334857) | Jul 22, 2023 |
| ASUSTek       | PRIME B550M-A AC            | Desktop     | [1a39665e1c](https://linux-hardware.org/?probe=1a39665e1c) | Jul 22, 2023 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [38a01d299e](https://linux-hardware.org/?probe=38a01d299e) | Jul 21, 2023 |
| Intel         | DQ57TM AAE70931-402         | Desktop     | [01621f8578](https://linux-hardware.org/?probe=01621f8578) | Jul 21, 2023 |
| Dell          | Latitude 5289               | Convertible | [eeb009e8f5](https://linux-hardware.org/?probe=eeb009e8f5) | Jul 21, 2023 |
| Lenovo        | 3151 SDK0J40697 WIN 3305... | Mini pc     | [3e6dc436dd](https://linux-hardware.org/?probe=3e6dc436dd) | Jul 21, 2023 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [620c7f4aec](https://linux-hardware.org/?probe=620c7f4aec) | Jul 21, 2023 |
| Acer          | ConceptD CN715-71           | Notebook    | [ae4de8c5b2](https://linux-hardware.org/?probe=ae4de8c5b2) | Jul 21, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [df9e2bd667](https://linux-hardware.org/?probe=df9e2bd667) | Jul 20, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [4f438fcc8b](https://linux-hardware.org/?probe=4f438fcc8b) | Jul 20, 2023 |
| Dell          | 0D881F A05                  | Desktop     | [26695664a7](https://linux-hardware.org/?probe=26695664a7) | Jul 18, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [d4a4fec7c0](https://linux-hardware.org/?probe=d4a4fec7c0) | Jul 17, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [164e93a53b](https://linux-hardware.org/?probe=164e93a53b) | Jul 16, 2023 |
| Lenovo        | MAHOBAY                     | Desktop     | [ded2ed05d8](https://linux-hardware.org/?probe=ded2ed05d8) | Jul 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [3caf271d7c](https://linux-hardware.org/?probe=3caf271d7c) | Jul 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [689d391a1d](https://linux-hardware.org/?probe=689d391a1d) | Jul 15, 2023 |
| ASRock        | B85M Pro4                   | Desktop     | [8e53be597f](https://linux-hardware.org/?probe=8e53be597f) | Jul 13, 2023 |
| ASRock        | B85M Pro4                   | Desktop     | [dcb1a242c5](https://linux-hardware.org/?probe=dcb1a242c5) | Jul 13, 2023 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [b5374c8055](https://linux-hardware.org/?probe=b5374c8055) | Jul 12, 2023 |
| ASUSTek       | Q87M-E                      | Desktop     | [0d59e226ae](https://linux-hardware.org/?probe=0d59e226ae) | Jul 10, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [975668f4f1](https://linux-hardware.org/?probe=975668f4f1) | Jul 10, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [7bc8c956fd](https://linux-hardware.org/?probe=7bc8c956fd) | Jul 10, 2023 |
| Dell          | Latitude E5420              | Notebook    | [6dba8e523b](https://linux-hardware.org/?probe=6dba8e523b) | Jul 09, 2023 |
| Lenovo        | B560 43308UG                | Notebook    | [20ea6219d4](https://linux-hardware.org/?probe=20ea6219d4) | Jul 09, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [41ede144c1](https://linux-hardware.org/?probe=41ede144c1) | Jul 09, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [17c907528f](https://linux-hardware.org/?probe=17c907528f) | Jul 09, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [978a7ef06f](https://linux-hardware.org/?probe=978a7ef06f) | Jul 08, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [7c39787112](https://linux-hardware.org/?probe=7c39787112) | Jul 08, 2023 |
| AWOW          | AR40S                       | Stick pc    | [35b286ba6b](https://linux-hardware.org/?probe=35b286ba6b) | Jul 08, 2023 |
| AWOW          | AR40S                       | Stick pc    | [44eaa3f5c1](https://linux-hardware.org/?probe=44eaa3f5c1) | Jul 08, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [46132f9b9c](https://linux-hardware.org/?probe=46132f9b9c) | Jul 07, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B2502CBA... | Notebook    | [397adc6b70](https://linux-hardware.org/?probe=397adc6b70) | Jul 06, 2023 |
| Dell          | Latitude E6530              | Notebook    | [16581ade55](https://linux-hardware.org/?probe=16581ade55) | Jul 06, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | Desktop     | [b1f7c9aea2](https://linux-hardware.org/?probe=b1f7c9aea2) | Jul 06, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [6b250aabab](https://linux-hardware.org/?probe=6b250aabab) | Jul 05, 2023 |
| Lenovo        | ThinkCentre A70 7844H9G     | Desktop     | [46bfb7c0ff](https://linux-hardware.org/?probe=46bfb7c0ff) | Jul 05, 2023 |
| Gigabyte      | Z87-D3HP-CF                 | Desktop     | [7502eb638e](https://linux-hardware.org/?probe=7502eb638e) | Jul 04, 2023 |
| Dell          | Latitude 7530               | Notebook    | [0d03a052d8](https://linux-hardware.org/?probe=0d03a052d8) | Jul 03, 2023 |
| Dell          | 0D881F A05                  | Desktop     | [947d2ff164](https://linux-hardware.org/?probe=947d2ff164) | Jul 03, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [b5a7ef8997](https://linux-hardware.org/?probe=b5a7ef8997) | Jul 02, 2023 |
| Dell          | G3 3779                     | Notebook    | [bcae1c7195](https://linux-hardware.org/?probe=bcae1c7195) | Jul 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [1c976fee39](https://linux-hardware.org/?probe=1c976fee39) | Jul 01, 2023 |
| Fujitsu       | LIFEBOOK U757               | Notebook    | [f7bac40ab1](https://linux-hardware.org/?probe=f7bac40ab1) | Jul 01, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [9beb3b7196](https://linux-hardware.org/?probe=9beb3b7196) | Jul 01, 2023 |
| Lenovo        | Yoga 9 14IAP7 82LU          | Convertible | [cb6f37ea2b](https://linux-hardware.org/?probe=cb6f37ea2b) | Jul 01, 2023 |
| Dell          | Latitude E5450              | Notebook    | [e0826ab83a](https://linux-hardware.org/?probe=e0826ab83a) | Jun 30, 2023 |
| Schenker      | XMG PRO (E23)               | Notebook    | [c70da63bd9](https://linux-hardware.org/?probe=c70da63bd9) | Jun 30, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [b52c0ac96a](https://linux-hardware.org/?probe=b52c0ac96a) | Jun 29, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [bbd13c14eb](https://linux-hardware.org/?probe=bbd13c14eb) | Jun 29, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [802b3686d4](https://linux-hardware.org/?probe=802b3686d4) | Jun 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [abf9b9909f](https://linux-hardware.org/?probe=abf9b9909f) | Jun 27, 2023 |
| MSI           | H81M-P33                    | Desktop     | [1726bb80ec](https://linux-hardware.org/?probe=1726bb80ec) | Jun 27, 2023 |
| Positivo      | POS-PIH81DI                 | Desktop     | [42e304c777](https://linux-hardware.org/?probe=42e304c777) | Jun 26, 2023 |
| Positivo      | POS-PIH81DI                 | Desktop     | [77d2d3d01b](https://linux-hardware.org/?probe=77d2d3d01b) | Jun 26, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [589dd91af9](https://linux-hardware.org/?probe=589dd91af9) | Jun 25, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [aa50925a16](https://linux-hardware.org/?probe=aa50925a16) | Jun 23, 2023 |
| Dell          | G3 3590                     | Notebook    | [14ab83043b](https://linux-hardware.org/?probe=14ab83043b) | Jun 21, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [014c851c43](https://linux-hardware.org/?probe=014c851c43) | Jun 21, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [3dffeb35fa](https://linux-hardware.org/?probe=3dffeb35fa) | Jun 20, 2023 |
| HP            | ENVY Laptop 14-eb0xxx       | Notebook    | [233b6c3412](https://linux-hardware.org/?probe=233b6c3412) | Jun 20, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U30... | Notebook    | [7d00ddf4fc](https://linux-hardware.org/?probe=7d00ddf4fc) | Jun 20, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | Notebook    | [5daecd88f5](https://linux-hardware.org/?probe=5daecd88f5) | Jun 19, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [260297ab72](https://linux-hardware.org/?probe=260297ab72) | Jun 19, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | Notebook    | [83d17fd3bd](https://linux-hardware.org/?probe=83d17fd3bd) | Jun 17, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | Notebook    | [739c466bf0](https://linux-hardware.org/?probe=739c466bf0) | Jun 17, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [587c48c954](https://linux-hardware.org/?probe=587c48c954) | Jun 17, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [75eeeb7917](https://linux-hardware.org/?probe=75eeeb7917) | Jun 16, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [b8d24f1cc8](https://linux-hardware.org/?probe=b8d24f1cc8) | Jun 15, 2023 |
| HP            | Notebook                    | Notebook    | [e0a00a71de](https://linux-hardware.org/?probe=e0a00a71de) | Jun 15, 2023 |
| HP            | Notebook                    | Notebook    | [76433ab03f](https://linux-hardware.org/?probe=76433ab03f) | Jun 15, 2023 |
| HP            | 86F0 11000                  | All in one  | [45026f50ef](https://linux-hardware.org/?probe=45026f50ef) | Jun 15, 2023 |
| HP            | 86F0 11000                  | All in one  | [f074cca59a](https://linux-hardware.org/?probe=f074cca59a) | Jun 15, 2023 |
| Dell          | Latitude 3310               | Notebook    | [40aa328d98](https://linux-hardware.org/?probe=40aa328d98) | Jun 15, 2023 |
| Proline       | V1165C4                     | Notebook    | [89f6135da3](https://linux-hardware.org/?probe=89f6135da3) | Jun 14, 2023 |
| Lenovo        | ThinkPad T440p 20AN009CU... | Notebook    | [54fd87b596](https://linux-hardware.org/?probe=54fd87b596) | Jun 14, 2023 |
| Intel         | NUC10i3FNB M38070-307       | Mini pc     | [a0cdda9a4d](https://linux-hardware.org/?probe=a0cdda9a4d) | Jun 14, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [f616cb77b5](https://linux-hardware.org/?probe=f616cb77b5) | Jun 13, 2023 |
| Gigabyte      | C246-WU4-CF                 | Desktop     | [8babb9b5f1](https://linux-hardware.org/?probe=8babb9b5f1) | Jun 13, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [7f974cd282](https://linux-hardware.org/?probe=7f974cd282) | Jun 12, 2023 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [679fb4f6ab](https://linux-hardware.org/?probe=679fb4f6ab) | Jun 11, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [36f0bbcb6d](https://linux-hardware.org/?probe=36f0bbcb6d) | Jun 11, 2023 |
| Lenovo        | 312A SDK0R32862 WIN 3258... | Desktop     | [1e8ab337a5](https://linux-hardware.org/?probe=1e8ab337a5) | Jun 11, 2023 |
| Microsoft     | Surface Laptop 3            | Tablet      | [b599a55609](https://linux-hardware.org/?probe=b599a55609) | Jun 10, 2023 |
| Lenovo        | ThinkPad T570 20H9000UUS    | Notebook    | [606989ab70](https://linux-hardware.org/?probe=606989ab70) | Jun 10, 2023 |
| Supermicro    | C7H61                       | Desktop     | [7eef5b7873](https://linux-hardware.org/?probe=7eef5b7873) | Jun 08, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [610c9c318f](https://linux-hardware.org/?probe=610c9c318f) | Jun 08, 2023 |
| PC Special... | Initia Ii 15                | Notebook    | [36a16c2890](https://linux-hardware.org/?probe=36a16c2890) | Jun 08, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [62418abec4](https://linux-hardware.org/?probe=62418abec4) | Jun 08, 2023 |
| Acer          | Nitro AN515-56              | Notebook    | [f02195de51](https://linux-hardware.org/?probe=f02195de51) | Jun 07, 2023 |
| Microsoft     | Surface Laptop 3            | Tablet      | [646e1db08d](https://linux-hardware.org/?probe=646e1db08d) | Jun 07, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [f4e4a4b982](https://linux-hardware.org/?probe=f4e4a4b982) | Jun 07, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [7948f267c2](https://linux-hardware.org/?probe=7948f267c2) | Jun 07, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [1139c69312](https://linux-hardware.org/?probe=1139c69312) | Jun 06, 2023 |
| MSI           | 2AE0                        | Desktop     | [15b3c478d3](https://linux-hardware.org/?probe=15b3c478d3) | Jun 06, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [5e9fd3f392](https://linux-hardware.org/?probe=5e9fd3f392) | Jun 05, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [693fdb51d3](https://linux-hardware.org/?probe=693fdb51d3) | Jun 05, 2023 |
| Biostar       | B350GT3                     | Desktop     | [b425f8d45a](https://linux-hardware.org/?probe=b425f8d45a) | Jun 05, 2023 |
| Lenovo        | Yoga Creator 7 15IMH05 8... | Notebook    | [3bcc239452](https://linux-hardware.org/?probe=3bcc239452) | Jun 04, 2023 |
| Dell          | Latitude E6500              | Notebook    | [4053ff5676](https://linux-hardware.org/?probe=4053ff5676) | Jun 03, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | Notebook    | [767241151a](https://linux-hardware.org/?probe=767241151a) | Jun 03, 2023 |
| Lenovo        | ThinkPad T460 20FN004BMN    | Notebook    | [dafbbaeb0f](https://linux-hardware.org/?probe=dafbbaeb0f) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [6ae18b11ab](https://linux-hardware.org/?probe=6ae18b11ab) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [963b30ca7f](https://linux-hardware.org/?probe=963b30ca7f) | Jun 02, 2023 |
| Biostar       | A10N-8800E                  | Desktop     | [906dbab25c](https://linux-hardware.org/?probe=906dbab25c) | Jun 01, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [7baed02e0e](https://linux-hardware.org/?probe=7baed02e0e) | Jun 01, 2023 |
| ASRock        | H170M Pro4                  | Desktop     | [d936c663d3](https://linux-hardware.org/?probe=d936c663d3) | Jun 01, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [8720e6163e](https://linux-hardware.org/?probe=8720e6163e) | Jun 01, 2023 |
| MSI           | GF63 Thin 11SC              | Notebook    | [8f8afcc010](https://linux-hardware.org/?probe=8f8afcc010) | Jun 01, 2023 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | Desktop     | [0586d2c0e2](https://linux-hardware.org/?probe=0586d2c0e2) | Jun 01, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [ebd7782079](https://linux-hardware.org/?probe=ebd7782079) | May 31, 2023 |
| ASUSTek       | P5Q                         | Desktop     | [e936e44332](https://linux-hardware.org/?probe=e936e44332) | May 31, 2023 |
| ASUSTek       | Z97-DELUXE                  | Desktop     | [2723d218b7](https://linux-hardware.org/?probe=2723d218b7) | May 31, 2023 |
| ASUSTek       | P9X79                       | Desktop     | [c677ff5b2d](https://linux-hardware.org/?probe=c677ff5b2d) | May 31, 2023 |
| AZW           | GTR V02                     | Desktop     | [bd1740c7b2](https://linux-hardware.org/?probe=bd1740c7b2) | May 31, 2023 |
| AZW           | GTR V02                     | Desktop     | [cab90f1838](https://linux-hardware.org/?probe=cab90f1838) | May 31, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [2667cb67a3](https://linux-hardware.org/?probe=2667cb67a3) | May 30, 2023 |
| Dell          | G15 5525                    | Notebook    | [f7e5d0ae57](https://linux-hardware.org/?probe=f7e5d0ae57) | May 30, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [0568aa067a](https://linux-hardware.org/?probe=0568aa067a) | May 30, 2023 |
| ASRock        | AB350M Pro4                 | Desktop     | [4f23de2827](https://linux-hardware.org/?probe=4f23de2827) | May 30, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [bca463af6d](https://linux-hardware.org/?probe=bca463af6d) | May 28, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [e429db5b0b](https://linux-hardware.org/?probe=e429db5b0b) | May 27, 2023 |
| Dell          | Precision 5530              | Notebook    | [cb116bdfd2](https://linux-hardware.org/?probe=cb116bdfd2) | May 26, 2023 |
| ASUSTek       | P7P55-M                     | Desktop     | [a8fd95ce79](https://linux-hardware.org/?probe=a8fd95ce79) | May 25, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [1c62418caf](https://linux-hardware.org/?probe=1c62418caf) | May 25, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [3e1fb6f93b](https://linux-hardware.org/?probe=3e1fb6f93b) | May 25, 2023 |
| Acer          | Aspire M3920                | Desktop     | [5e61c22a26](https://linux-hardware.org/?probe=5e61c22a26) | May 24, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [2ef3c0b337](https://linux-hardware.org/?probe=2ef3c0b337) | May 24, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [174a3139c4](https://linux-hardware.org/?probe=174a3139c4) | May 24, 2023 |
| Dell          | Inspiron 14 5401            | Notebook    | [16d8b1c945](https://linux-hardware.org/?probe=16d8b1c945) | May 24, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [9568d26302](https://linux-hardware.org/?probe=9568d26302) | May 24, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [3eb016e8c7](https://linux-hardware.org/?probe=3eb016e8c7) | May 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3d4cdd163c](https://linux-hardware.org/?probe=3d4cdd163c) | May 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c3251b8c63](https://linux-hardware.org/?probe=c3251b8c63) | May 23, 2023 |
| ASUSTek       | Z170-PRO                    | Desktop     | [27819563b9](https://linux-hardware.org/?probe=27819563b9) | May 23, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [7f3dae82d3](https://linux-hardware.org/?probe=7f3dae82d3) | May 23, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [185b65bf34](https://linux-hardware.org/?probe=185b65bf34) | May 22, 2023 |
| COM1          | NBINF-X5-9G5                | Notebook    | [8d8c13c10c](https://linux-hardware.org/?probe=8d8c13c10c) | May 22, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [434372d228](https://linux-hardware.org/?probe=434372d228) | May 21, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [1c178d1658](https://linux-hardware.org/?probe=1c178d1658) | May 21, 2023 |
| Fujitsu       | LIFEBOOK U748               | Notebook    | [a8d8e219a2](https://linux-hardware.org/?probe=a8d8e219a2) | May 21, 2023 |
| MSI           | X370 GAMING PLUS            | Desktop     | [610c8c1a42](https://linux-hardware.org/?probe=610c8c1a42) | May 19, 2023 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | Desktop     | [1e7af790ed](https://linux-hardware.org/?probe=1e7af790ed) | May 19, 2023 |
| Notebook      | NLx0MU                      | Notebook    | [e0300907f0](https://linux-hardware.org/?probe=e0300907f0) | May 18, 2023 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [7da21ce089](https://linux-hardware.org/?probe=7da21ce089) | May 18, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [28b96d7d6a](https://linux-hardware.org/?probe=28b96d7d6a) | May 17, 2023 |
| Samsung       | 730QFG                      | Convertible | [134377c283](https://linux-hardware.org/?probe=134377c283) | May 17, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [7c05862259](https://linux-hardware.org/?probe=7c05862259) | May 16, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [8cb1f28963](https://linux-hardware.org/?probe=8cb1f28963) | May 16, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [c8250719d9](https://linux-hardware.org/?probe=c8250719d9) | May 16, 2023 |
| ASUSTek       | F1A75-V PRO                 | Desktop     | [9ee8a0ca50](https://linux-hardware.org/?probe=9ee8a0ca50) | May 14, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [e81d6a8a69](https://linux-hardware.org/?probe=e81d6a8a69) | May 14, 2023 |
| Dell          | Latitude E6500              | Notebook    | [b223b17c87](https://linux-hardware.org/?probe=b223b17c87) | May 14, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [0701f94970](https://linux-hardware.org/?probe=0701f94970) | May 13, 2023 |
| Dell          | G3 3590                     | Notebook    | [696d2d38df](https://linux-hardware.org/?probe=696d2d38df) | May 13, 2023 |
| Samsung       | R425/R525                   | Notebook    | [a7719ea5d3](https://linux-hardware.org/?probe=a7719ea5d3) | May 13, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [9ca71ebd01](https://linux-hardware.org/?probe=9ca71ebd01) | May 12, 2023 |
| Dell          | Latitude 7490               | Notebook    | [a187ae7b7e](https://linux-hardware.org/?probe=a187ae7b7e) | May 12, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [9448d89bb6](https://linux-hardware.org/?probe=9448d89bb6) | May 12, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [e360693145](https://linux-hardware.org/?probe=e360693145) | May 11, 2023 |
| Dell          | Latitude 5420               | Notebook    | [a3c2a7c9bf](https://linux-hardware.org/?probe=a3c2a7c9bf) | May 11, 2023 |
| HP            | ProBook x360 440 G1         | Convertible | [63e082c879](https://linux-hardware.org/?probe=63e082c879) | May 10, 2023 |
| HP            | ProBook x360 440 G1         | Convertible | [c85cc0e79c](https://linux-hardware.org/?probe=c85cc0e79c) | May 10, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [d567c1f954](https://linux-hardware.org/?probe=d567c1f954) | May 10, 2023 |
| IBM           | 00AM544                     | Server      | [4c011ef794](https://linux-hardware.org/?probe=4c011ef794) | May 09, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [c941da38cd](https://linux-hardware.org/?probe=c941da38cd) | May 08, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [cbafd29abc](https://linux-hardware.org/?probe=cbafd29abc) | May 08, 2023 |
| Dell          | Latitude 3570               | Notebook    | [8209fc06f4](https://linux-hardware.org/?probe=8209fc06f4) | May 08, 2023 |
| TerraQue      | W65_W67RB                   | Notebook    | [842f203ec5](https://linux-hardware.org/?probe=842f203ec5) | May 07, 2023 |
| Acer          | Aspire M3920                | Desktop     | [aed14c1e20](https://linux-hardware.org/?probe=aed14c1e20) | May 07, 2023 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [a062cb2ab6](https://linux-hardware.org/?probe=a062cb2ab6) | May 07, 2023 |
| Lenovo        | ThinkPad T460s 20F9CTO1W... | Notebook    | [4229be0afa](https://linux-hardware.org/?probe=4229be0afa) | May 07, 2023 |
| Dell          | XPS 13 9300                 | Notebook    | [7bbdc5e568](https://linux-hardware.org/?probe=7bbdc5e568) | May 07, 2023 |
| Samsung       | Galaxy TabPro S             | Tablet      | [167229560a](https://linux-hardware.org/?probe=167229560a) | May 05, 2023 |
| Razer         | Blade Pro 17 (2019)         | Notebook    | [4b2265c354](https://linux-hardware.org/?probe=4b2265c354) | May 05, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [00a1158a86](https://linux-hardware.org/?probe=00a1158a86) | May 04, 2023 |
| ASUSTek       | X750JB                      | Notebook    | [02a5481254](https://linux-hardware.org/?probe=02a5481254) | May 03, 2023 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [ae1618c708](https://linux-hardware.org/?probe=ae1618c708) | May 03, 2023 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [63015eecb0](https://linux-hardware.org/?probe=63015eecb0) | May 03, 2023 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [36574d4502](https://linux-hardware.org/?probe=36574d4502) | May 03, 2023 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [2da8ff7129](https://linux-hardware.org/?probe=2da8ff7129) | May 03, 2023 |
| Dell          | Inspiron 3593               | Notebook    | [263099c212](https://linux-hardware.org/?probe=263099c212) | May 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [ee8e81add2](https://linux-hardware.org/?probe=ee8e81add2) | May 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [e8ce8c11c0](https://linux-hardware.org/?probe=e8ce8c11c0) | May 01, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [45a7e28db1](https://linux-hardware.org/?probe=45a7e28db1) | Apr 30, 2023 |
| Intel         | H81                         | Desktop     | [c70b10516b](https://linux-hardware.org/?probe=c70b10516b) | Apr 30, 2023 |
| Acer          | Aspire M5-481T              | Notebook    | [d215d36b64](https://linux-hardware.org/?probe=d215d36b64) | Apr 30, 2023 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [a31fa8f985](https://linux-hardware.org/?probe=a31fa8f985) | Apr 28, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [dd76e10243](https://linux-hardware.org/?probe=dd76e10243) | Apr 28, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [7feb43607e](https://linux-hardware.org/?probe=7feb43607e) | Apr 27, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [44c5943019](https://linux-hardware.org/?probe=44c5943019) | Apr 27, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [812906148b](https://linux-hardware.org/?probe=812906148b) | Apr 27, 2023 |
| Dell          | Inspiron 3793               | Notebook    | [f9d337a0a1](https://linux-hardware.org/?probe=f9d337a0a1) | Apr 26, 2023 |
| Lenovo        | ThinkPad T430s 23539MU      | Notebook    | [83a1144be6](https://linux-hardware.org/?probe=83a1144be6) | Apr 26, 2023 |
| Alienware     | Aurora R15 AMD              | Desktop     | [f2e22848d1](https://linux-hardware.org/?probe=f2e22848d1) | Apr 25, 2023 |
| MSI           | FM2-A75MA-E35               | Desktop     | [011f691ce1](https://linux-hardware.org/?probe=011f691ce1) | Apr 25, 2023 |
| Acer          | Spin SP313-51N              | Convertible | [76646ac40d](https://linux-hardware.org/?probe=76646ac40d) | Apr 24, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [6d49fc2276](https://linux-hardware.org/?probe=6d49fc2276) | Apr 24, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [3d8d7c49f8](https://linux-hardware.org/?probe=3d8d7c49f8) | Apr 24, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [e9a3b8f1d1](https://linux-hardware.org/?probe=e9a3b8f1d1) | Apr 24, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [2a8a92135b](https://linux-hardware.org/?probe=2a8a92135b) | Apr 24, 2023 |
| Carbon Sys... | Iridium 14                  | Notebook    | [10cd21aba6](https://linux-hardware.org/?probe=10cd21aba6) | Apr 23, 2023 |
| Dell          | 00V16R A00                  | All in one  | [cb94924faa](https://linux-hardware.org/?probe=cb94924faa) | Apr 23, 2023 |
| Dell          | Precision 7550              | Notebook    | [31830a82c6](https://linux-hardware.org/?probe=31830a82c6) | Apr 22, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [c4a5aad8a1](https://linux-hardware.org/?probe=c4a5aad8a1) | Apr 22, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [0dcc2eaa50](https://linux-hardware.org/?probe=0dcc2eaa50) | Apr 22, 2023 |
| HP            | 82F2 A01                    | Desktop     | [fbcf679bae](https://linux-hardware.org/?probe=fbcf679bae) | Apr 21, 2023 |
| Supermicro    | C7H61                       | Desktop     | [f5e17f37d4](https://linux-hardware.org/?probe=f5e17f37d4) | Apr 21, 2023 |
| Carbon Sys... | Iridium 14                  | Notebook    | [af5e3d750a](https://linux-hardware.org/?probe=af5e3d750a) | Apr 20, 2023 |
| ASUSTek       | Z170-PRO                    | Desktop     | [970c4dfa6f](https://linux-hardware.org/?probe=970c4dfa6f) | Apr 20, 2023 |
| Supermicro    | C7H61                       | Desktop     | [d975325f4b](https://linux-hardware.org/?probe=d975325f4b) | Apr 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [cd58803d5c](https://linux-hardware.org/?probe=cd58803d5c) | Apr 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [7adb4b2000](https://linux-hardware.org/?probe=7adb4b2000) | Apr 19, 2023 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | Notebook    | [cccb2ff44c](https://linux-hardware.org/?probe=cccb2ff44c) | Apr 18, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [cc18450a32](https://linux-hardware.org/?probe=cc18450a32) | Apr 17, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [7ed9078ed9](https://linux-hardware.org/?probe=7ed9078ed9) | Apr 17, 2023 |
| MSI           | Modern 14 B11MOU            | Notebook    | [d76555e7e6](https://linux-hardware.org/?probe=d76555e7e6) | Apr 16, 2023 |
| Dell          | 0D881F A05                  | Desktop     | [7aef52516b](https://linux-hardware.org/?probe=7aef52516b) | Apr 16, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [073b59d558](https://linux-hardware.org/?probe=073b59d558) | Apr 16, 2023 |
| AXIOO         | SlimBook 11                 | Notebook    | [b0c639ab77](https://linux-hardware.org/?probe=b0c639ab77) | Apr 15, 2023 |
| HP            | ProBook 650 G3              | Notebook    | [00526690c9](https://linux-hardware.org/?probe=00526690c9) | Apr 15, 2023 |
| ASRock        | Z170 Extreme4               | Desktop     | [d21971f30f](https://linux-hardware.org/?probe=d21971f30f) | Apr 13, 2023 |
| Casper        | NIRVANA NOTEBOOK            | Notebook    | [624fa75f43](https://linux-hardware.org/?probe=624fa75f43) | Apr 12, 2023 |
| ASUSTek       | Z97-A                       | Desktop     | [139f5f3aca](https://linux-hardware.org/?probe=139f5f3aca) | Apr 12, 2023 |
| Dell          | Latitude E5450              | Notebook    | [f98cdf4da0](https://linux-hardware.org/?probe=f98cdf4da0) | Apr 11, 2023 |
| Dell          | Latitude E5450              | Notebook    | [7bf04cdb7d](https://linux-hardware.org/?probe=7bf04cdb7d) | Apr 11, 2023 |
| HP            | 829C                        | All in one  | [91f5a10ba1](https://linux-hardware.org/?probe=91f5a10ba1) | Apr 11, 2023 |
| Dell          | 0RW199                      | Desktop     | [8c41f4ff91](https://linux-hardware.org/?probe=8c41f4ff91) | Apr 11, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [5875837a8d](https://linux-hardware.org/?probe=5875837a8d) | Apr 10, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [6b6b2a8633](https://linux-hardware.org/?probe=6b6b2a8633) | Apr 09, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [00489240d2](https://linux-hardware.org/?probe=00489240d2) | Apr 09, 2023 |
| Dell          | 0F373D A00                  | Desktop     | [e42bdc9769](https://linux-hardware.org/?probe=e42bdc9769) | Apr 09, 2023 |
| MSI           | MPG Z690 CARBON WIFI        | Desktop     | [8187fc54a3](https://linux-hardware.org/?probe=8187fc54a3) | Apr 07, 2023 |
| Unknown       | Unknown                     | Notebook    | [0bf91f3219](https://linux-hardware.org/?probe=0bf91f3219) | Apr 06, 2023 |
| Lenovo        | ThinkPad T420 4177RVU       | Notebook    | [994fccf5d0](https://linux-hardware.org/?probe=994fccf5d0) | Apr 06, 2023 |
| Unknown       | Unknown                     | Notebook    | [ec673ad1c1](https://linux-hardware.org/?probe=ec673ad1c1) | Apr 06, 2023 |
| Gigabyte      | M61SME-S2                   | Desktop     | [25d436d2cb](https://linux-hardware.org/?probe=25d436d2cb) | Apr 06, 2023 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [edd397551c](https://linux-hardware.org/?probe=edd397551c) | Apr 05, 2023 |
| HP            | 0A9Ch                       | Desktop     | [178046626f](https://linux-hardware.org/?probe=178046626f) | Apr 05, 2023 |
| Gigabyte      | 970-GAMING                  | Desktop     | [6ec3c125d5](https://linux-hardware.org/?probe=6ec3c125d5) | Apr 05, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [32f708c916](https://linux-hardware.org/?probe=32f708c916) | Apr 05, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [0779903086](https://linux-hardware.org/?probe=0779903086) | Apr 05, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [7cce222ce2](https://linux-hardware.org/?probe=7cce222ce2) | Apr 04, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [7eeea6ba29](https://linux-hardware.org/?probe=7eeea6ba29) | Apr 04, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [6e750dfaa5](https://linux-hardware.org/?probe=6e750dfaa5) | Apr 04, 2023 |
| Notebook      | PD5x_7xSNC_SND_SNE          | Notebook    | [1c9d684eba](https://linux-hardware.org/?probe=1c9d684eba) | Apr 04, 2023 |
| Alienware     | 0VDT73 A00                  | Desktop     | [ed92305da6](https://linux-hardware.org/?probe=ed92305da6) | Apr 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CFS... | Notebook    | [0cff652e48](https://linux-hardware.org/?probe=0cff652e48) | Apr 03, 2023 |
| Gigabyte      | B460M AORUS PRO             | Desktop     | [72dc18dacb](https://linux-hardware.org/?probe=72dc18dacb) | Apr 03, 2023 |
| Lenovo        | Yoga 7 14ACN6 82N7          | Convertible | [8ba82ca424](https://linux-hardware.org/?probe=8ba82ca424) | Apr 03, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [f8e61fd850](https://linux-hardware.org/?probe=f8e61fd850) | Apr 03, 2023 |
| ASUSTek       | ASUS ExpertBook P2451FA_... | Notebook    | [05261a9b98](https://linux-hardware.org/?probe=05261a9b98) | Apr 03, 2023 |
| Gigabyte      | X570 AORUS XTREME           | Desktop     | [35c3ae13c5](https://linux-hardware.org/?probe=35c3ae13c5) | Apr 02, 2023 |
| Thomson       | SPNEOX13-4RD64              | Notebook    | [bf3eb39804](https://linux-hardware.org/?probe=bf3eb39804) | Apr 02, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [e800b0ff2e](https://linux-hardware.org/?probe=e800b0ff2e) | Apr 02, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [a0dddcbb95](https://linux-hardware.org/?probe=a0dddcbb95) | Apr 02, 2023 |
| Gigabyte      | B460M AORUS PRO             | Desktop     | [12647b9601](https://linux-hardware.org/?probe=12647b9601) | Apr 02, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [46e8dbcdc8](https://linux-hardware.org/?probe=46e8dbcdc8) | Apr 02, 2023 |
| Notebook      | PD5x_7xSNC_SND_SNE          | Notebook    | [4809c76aba](https://linux-hardware.org/?probe=4809c76aba) | Apr 02, 2023 |
| Lenovo        | ThinkPad X280 20KF001UUS    | Notebook    | [49e740bc77](https://linux-hardware.org/?probe=49e740bc77) | Apr 02, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [0fbed59931](https://linux-hardware.org/?probe=0fbed59931) | Apr 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [bc77efa103](https://linux-hardware.org/?probe=bc77efa103) | Apr 01, 2023 |
| MSI           | MAG A520M VECTOR WIFI       | Desktop     | [3c08cf9aba](https://linux-hardware.org/?probe=3c08cf9aba) | Apr 01, 2023 |
| ASUSTek       | EB1036                      | Desktop     | [955d389e06](https://linux-hardware.org/?probe=955d389e06) | Mar 30, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [278ed0e013](https://linux-hardware.org/?probe=278ed0e013) | Mar 30, 2023 |
| Dell          | 0200DY A01                  | Desktop     | [722b28547b](https://linux-hardware.org/?probe=722b28547b) | Mar 28, 2023 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [548224967e](https://linux-hardware.org/?probe=548224967e) | Mar 28, 2023 |
| MSI           | B85-G43                     | Desktop     | [3dac8c76c2](https://linux-hardware.org/?probe=3dac8c76c2) | Mar 28, 2023 |
| Lenovo        | SHARKBAY SDK0J40709 WIN ... | Desktop     | [22e3e1831c](https://linux-hardware.org/?probe=22e3e1831c) | Mar 28, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [84092aca44](https://linux-hardware.org/?probe=84092aca44) | Mar 27, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Kubuntu_22.04/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.15.0-56-generic | 67        | 4.22%   |
| 5.15.0-52-generic | 66        | 4.15%   |
| 5.15.0-48-generic | 41        | 2.58%   |
| 5.15.0-58-generic | 40        | 2.52%   |
| 5.15.0-43-generic | 39        | 2.45%   |
| 5.15.0-91-generic | 38        | 2.39%   |
| 6.2.0-26-generic  | 36        | 2.27%   |
| 5.15.0-47-generic | 36        | 2.27%   |
| 5.15.0-53-generic | 33        | 2.08%   |
| 5.15.0-46-generic | 33        | 2.08%   |
| 5.15.0-60-generic | 32        | 2.01%   |
| 5.15.0-41-generic | 29        | 1.83%   |
| 5.15.0-25-generic | 29        | 1.83%   |
| 5.19.0-35-generic | 28        | 1.76%   |
| 6.5.0-28-generic  | 26        | 1.64%   |
| 5.15.0-40-generic | 26        | 1.64%   |
| 5.15.0-67-generic | 25        | 1.57%   |
| 6.5.0-15-generic  | 24        | 1.51%   |
| 6.2.0-34-generic  | 24        | 1.51%   |
| 5.19.0-46-generic | 24        | 1.51%   |
| 5.15.0-27-generic | 24        | 1.51%   |
| 6.2.0-39-generic  | 23        | 1.45%   |
| 5.15.0-50-generic | 23        | 1.45%   |
| 5.19.0-38-generic | 22        | 1.38%   |
| 6.5.0-26-generic  | 20        | 1.26%   |
| 5.19.0-32-generic | 20        | 1.26%   |
| 5.15.0-75-generic | 20        | 1.26%   |
| 6.2.0-37-generic  | 19        | 1.2%    |
| 5.19.0-41-generic | 19        | 1.2%    |
| 6.2.0-36-generic  | 18        | 1.13%   |
| 5.15.0-33-generic | 18        | 1.13%   |
| 6.5.0-21-generic  | 16        | 1.01%   |
| 6.2.0-33-generic  | 16        | 1.01%   |
| 6.5.0-14-generic  | 15        | 0.94%   |
| 5.15.0-78-generic | 15        | 0.94%   |
| 5.15.0-71-generic | 15        | 0.94%   |
| 5.15.0-69-generic | 15        | 0.94%   |
| 6.5.0-27-generic  | 14        | 0.88%   |
| 6.2.0-32-generic  | 14        | 0.88%   |
| 5.15.0-57-generic | 14        | 0.88%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 878       | 59.61%  |
| 6.2.0   | 170       | 11.54%  |
| 5.19.0  | 170       | 11.54%  |
| 6.5.0   | 149       | 10.12%  |
| 5.17.0  | 16        | 1.09%   |
| 6.0.0   | 6         | 0.41%   |
| 5.13.0  | 6         | 0.41%   |
| 6.1.0   | 5         | 0.34%   |
| 6.4.8   | 2         | 0.14%   |
| 6.4.10  | 2         | 0.14%   |
| 6.3.8   | 2         | 0.14%   |
| 6.3.6   | 2         | 0.14%   |
| 6.2.2   | 2         | 0.14%   |
| 6.2.16  | 2         | 0.14%   |
| 6.1.5   | 2         | 0.14%   |
| 6.0.7   | 2         | 0.14%   |
| 6.0.1   | 2         | 0.14%   |
| 5.19.5  | 2         | 0.14%   |
| 5.18.4  | 2         | 0.14%   |
| 5.18.10 | 2         | 0.14%   |
| 6.8.6   | 1         | 0.07%   |
| 6.7.11  | 1         | 0.07%   |
| 6.7.1   | 1         | 0.07%   |
| 6.6.2   | 1         | 0.07%   |
| 6.5.7   | 1         | 0.07%   |
| 6.5.5   | 1         | 0.07%   |
| 6.5.3   | 1         | 0.07%   |
| 6.5.10  | 1         | 0.07%   |
| 6.4.3   | 1         | 0.07%   |
| 6.4.0   | 1         | 0.07%   |
| 6.3.9   | 1         | 0.07%   |
| 6.3.4   | 1         | 0.07%   |
| 6.3.1   | 1         | 0.07%   |
| 6.3.0   | 1         | 0.07%   |
| 6.2.8   | 1         | 0.07%   |
| 6.2.10  | 1         | 0.07%   |
| 6.1.9   | 1         | 0.07%   |
| 6.1.69  | 1         | 0.07%   |
| 6.1.58  | 1         | 0.07%   |
| 6.1.55  | 1         | 0.07%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 880       | 59.82%  |
| 6.2     | 176       | 11.96%  |
| 5.19    | 176       | 11.96%  |
| 6.5     | 153       | 10.4%   |
| 5.17    | 21        | 1.43%   |
| 6.1     | 13        | 0.88%   |
| 6.0     | 12        | 0.82%   |
| 6.3     | 8         | 0.54%   |
| 5.18    | 8         | 0.54%   |
| 6.4     | 6         | 0.41%   |
| 5.13    | 6         | 0.41%   |
| 5.16    | 3         | 0.2%    |
| 6.7     | 2         | 0.14%   |
| 5.10    | 2         | 0.14%   |
| 6.8     | 1         | 0.07%   |
| 6.6     | 1         | 0.07%   |
| 5.4     | 1         | 0.07%   |
| 5.14    | 1         | 0.07%   |
| 5.11    | 1         | 0.07%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1418      | 99.79%  |
| aarch64 | 2         | 0.14%   |
| riscv64 | 1         | 0.07%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| KDE5       | 1395      | 97.96%  |
| KDE        | 10        | 0.7%    |
| GNOME      | 9         | 0.63%   |
| XFCE       | 2         | 0.14%   |
| X-Cinnamon | 1         | 0.07%   |
| Unity      | 1         | 0.07%   |
| MATE       | 1         | 0.07%   |
| KDE6       | 1         | 0.07%   |
| i3         | 1         | 0.07%   |
| GNUstep    | 1         | 0.07%   |
| Cinnamon   | 1         | 0.07%   |
| Budgie     | 1         | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1357      | 95.03%  |
| Wayland | 45        | 3.15%   |
| Tty     | 25        | 1.75%   |
| Web     | 1         | 0.07%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 1035      | 72.23%  |
| Unknown | 297       | 20.73%  |
| GDM3    | 65        | 4.54%   |
| LightDM | 33        | 2.3%    |
| SLiM    | 1         | 0.07%   |
| LXDM    | 1         | 0.07%   |
| GDM     | 1         | 0.07%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 681       | 47.79%  |
| de_DE   | 121       | 8.49%   |
| fr_FR   | 68        | 4.77%   |
| it_IT   | 67        | 4.7%    |
| ru_RU   | 64        | 4.49%   |
| en_GB   | 62        | 4.35%   |
| pt_BR   | 38        | 2.67%   |
| es_ES   | 35        | 2.46%   |
| en_AU   | 32        | 2.25%   |
| en_CA   | 26        | 1.82%   |
| en_IN   | 25        | 1.75%   |
| pl_PL   | 24        | 1.68%   |
| es_AR   | 12        | 0.84%   |
| cs_CZ   | 12        | 0.84%   |
| C       | 11        | 0.77%   |
| hu_HU   | 8         | 0.56%   |
| en_ZA   | 8         | 0.56%   |
| nl_NL   | 7         | 0.49%   |
| en_PH   | 7         | 0.49%   |
| en_NZ   | 7         | 0.49%   |
| zh_CN   | 6         | 0.42%   |
| en_SG   | 6         | 0.42%   |
| tr_TR   | 5         | 0.35%   |
| es_MX   | 5         | 0.35%   |
| es_CO   | 5         | 0.35%   |
| el_GR   | 5         | 0.35%   |
| de_CH   | 5         | 0.35%   |
| de_AT   | 5         | 0.35%   |
| Default | 5         | 0.35%   |
| nl_BE   | 4         | 0.28%   |
| fi_FI   | 4         | 0.28%   |
| en_AG   | 4         | 0.28%   |
| pt_PT   | 3         | 0.21%   |
| lt_LT   | 3         | 0.21%   |
| fr_CH   | 3         | 0.21%   |
| fr_BE   | 3         | 0.21%   |
| es_VE   | 3         | 0.21%   |
| sl_SI   | 2         | 0.14%   |
| es_CL   | 2         | 0.14%   |
| en_IL   | 2         | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 748       | 52.16%  |
| BIOS | 686       | 47.84%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1167      | 81.1%   |
| Tmpfs   | 164       | 11.4%   |
| Btrfs   | 48        | 3.34%   |
| Overlay | 43        | 2.99%   |
| Xfs     | 10        | 0.69%   |
| Zfs     | 4         | 0.28%   |
| Ext2    | 2         | 0.14%   |
| Ext3    | 1         | 0.07%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 968       | 67.41%  |
| Unknown | 368       | 25.63%  |
| MBR     | 100       | 6.96%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1277      | 89.3%   |
| Yes       | 153       | 10.7%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 898       | 62.84%  |
| Yes       | 531       | 37.16%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| ASUSTek Computer                     | 240       | 16.89%  |
| Lenovo                               | 236       | 16.61%  |
| Hewlett-Packard                      | 195       | 13.72%  |
| Dell                                 | 165       | 11.61%  |
| Gigabyte Technology                  | 102       | 7.18%   |
| MSI                                  | 101       | 7.11%   |
| Acer                                 | 71        | 5%      |
| ASRock                               | 42        | 2.96%   |
| Apple                                | 34        | 2.39%   |
| HUAWEI                               | 19        | 1.34%   |
| Samsung Electronics                  | 14        | 0.99%   |
| Fujitsu                              | 10        | 0.7%    |
| AZW                                  | 10        | 0.7%    |
| Toshiba                              | 9         | 0.63%   |
| Intel                                | 9         | 0.63%   |
| Google                               | 9         | 0.63%   |
| Unknown                              | 9         | 0.63%   |
| Notebook                             | 8         | 0.56%   |
| Alienware                            | 8         | 0.56%   |
| TUXEDO                               | 6         | 0.42%   |
| Supermicro                           | 6         | 0.42%   |
| Biostar                              | 6         | 0.42%   |
| Timi                                 | 5         | 0.35%   |
| Sony                                 | 5         | 0.35%   |
| Medion                               | 5         | 0.35%   |
| Microsoft                            | 4         | 0.28%   |
| System76                             | 3         | 0.21%   |
| Schenker                             | 3         | 0.21%   |
| PC Specialist                        | 3         | 0.21%   |
| Framework                            | 3         | 0.21%   |
| Carbon Systems                       | 3         | 0.21%   |
| AMI                                  | 3         | 0.21%   |
| VALE                                 | 2         | 0.14%   |
| Shuttle                              | 2         | 0.14%   |
| Shenzhen Meigao Electronic Equipment | 2         | 0.14%   |
| Razer                                | 2         | 0.14%   |
| Positivo                             | 2         | 0.14%   |
| Panasonic                            | 2         | 0.14%   |
| LG Electronics                       | 2         | 0.14%   |
| HONOR                                | 2         | 0.14%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| ASUS All Series                        | 19        | 1.34%   |
| Unknown                                | 14        | 0.99%   |
| ASUS ROG STRIX B550-F GAMING           | 6         | 0.42%   |
| MSI MS-7B79                            | 5         | 0.35%   |
| HUAWEI HVY-WXX9                        | 5         | 0.35%   |
| AZW SER                                | 5         | 0.35%   |
| Lenovo IdeaPad 5 15ARE05 81YQ          | 4         | 0.28%   |
| HP Pavilion g6                         | 4         | 0.28%   |
| HP OMEN Laptop 15-en0xxx               | 4         | 0.28%   |
| HP Notebook                            | 4         | 0.28%   |
| HP 255 G8 Notebook PC                  | 4         | 0.28%   |
| ASUS PRIME X370-PRO                    | 4         | 0.28%   |
| ASRock B450M Pro4                      | 4         | 0.28%   |
| Acer Aspire A515-45                    | 4         | 0.28%   |
| MSI MS-7C95                            | 3         | 0.21%   |
| MSI MS-7B86                            | 3         | 0.21%   |
| MSI MS-7B51                            | 3         | 0.21%   |
| Lenovo IdeaPad 5 Pro 14ACN6 82L7       | 3         | 0.21%   |
| Lenovo IdeaPad 3 15ALC6 82KU           | 3         | 0.21%   |
| HP ProBook 6570b                       | 3         | 0.21%   |
| HP ProBook 6470b                       | 3         | 0.21%   |
| HP ProBook 440 G8 Notebook PC          | 3         | 0.21%   |
| HP Pavilion Gaming Laptop 15-ec0xxx    | 3         | 0.21%   |
| HP Laptop 15-ef2xxx                    | 3         | 0.21%   |
| HP G62                                 | 3         | 0.21%   |
| HP EliteDesk 800 G1 SFF                | 3         | 0.21%   |
| HP EliteBook 845 G7 Notebook PC        | 3         | 0.21%   |
| HP Compaq Elite 8300 SFF               | 3         | 0.21%   |
| Gigabyte B450M DS3H                    | 3         | 0.21%   |
| Framework Laptop (12th Gen Intel Core) | 3         | 0.21%   |
| Dell XPS 15 9560                       | 3         | 0.21%   |
| Dell OptiPlex 7040                     | 3         | 0.21%   |
| Dell OptiPlex 7010                     | 3         | 0.21%   |
| Dell Latitude 7490                     | 3         | 0.21%   |
| Dell Latitude 5420                     | 3         | 0.21%   |
| Dell Latitude 3420                     | 3         | 0.21%   |
| Dell G3 3590                           | 3         | 0.21%   |
| ASUS ROG STRIX X570-E GAMING           | 3         | 0.21%   |
| ASUS ROG CROSSHAIR VII HERO            | 3         | 0.21%   |
| ASUS P5Q                               | 3         | 0.21%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 97        | 6.83%   |
| Lenovo IdeaPad     | 50        | 3.52%   |
| Dell Latitude      | 48        | 3.38%   |
| Acer Aspire        | 41        | 2.89%   |
| ASUS ROG           | 38        | 2.67%   |
| Dell Inspiron      | 37        | 2.6%    |
| HP Pavilion        | 32        | 2.25%   |
| ASUS PRIME         | 30        | 2.11%   |
| HP ProBook         | 26        | 1.83%   |
| ASUS VivoBook      | 26        | 1.83%   |
| HP EliteBook       | 25        | 1.76%   |
| Dell XPS           | 22        | 1.55%   |
| HP Laptop          | 21        | 1.48%   |
| Dell Precision     | 19        | 1.34%   |
| ASUS TUF           | 19        | 1.34%   |
| ASUS All           | 19        | 1.34%   |
| Dell OptiPlex      | 18        | 1.27%   |
| Lenovo ThinkCentre | 17        | 1.2%    |
| Lenovo ThinkBook   | 14        | 0.99%   |
| Lenovo Legion      | 14        | 0.99%   |
| Unknown            | 14        | 0.99%   |
| Acer Nitro         | 13        | 0.91%   |
| Lenovo Yoga        | 12        | 0.84%   |
| HP ENVY            | 10        | 0.7%    |
| Gigabyte X570      | 9         | 0.63%   |
| Dell Vostro        | 9         | 0.63%   |
| HP OMEN            | 8         | 0.56%   |
| HP EliteDesk       | 8         | 0.56%   |
| ASUS ASUS          | 8         | 0.56%   |
| Toshiba Satellite  | 7         | 0.49%   |
| HP ZBook           | 7         | 0.49%   |
| HP Compaq          | 6         | 0.42%   |
| Apple MacBookPro11 | 6         | 0.42%   |
| MSI MS-7B79        | 5         | 0.35%   |
| Lenovo IdeaCentre  | 5         | 0.35%   |
| HUAWEI HVY-WXX9    | 5         | 0.35%   |
| HP Spectre         | 5         | 0.35%   |
| HP ProDesk         | 5         | 0.35%   |
| HP 255             | 5         | 0.35%   |
| Fujitsu LIFEBOOK   | 5         | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 215       | 15.13%  |
| 2020    | 184       | 12.95%  |
| 2022    | 125       | 8.8%    |
| 2019    | 123       | 8.66%   |
| 2018    | 111       | 7.81%   |
| 2012    | 108       | 7.6%    |
| 2017    | 84        | 5.91%   |
| 2014    | 80        | 5.63%   |
| 2013    | 71        | 5%      |
| 2016    | 65        | 4.57%   |
| 2011    | 61        | 4.29%   |
| 2015    | 55        | 3.87%   |
| 2023    | 40        | 2.81%   |
| 2010    | 37        | 2.6%    |
| 2009    | 21        | 1.48%   |
| 2008    | 21        | 1.48%   |
| 2007    | 15        | 1.06%   |
| Unknown | 3         | 0.21%   |
| 2024    | 2         | 0.14%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 795       | 55.95%  |
| Desktop        | 515       | 36.24%  |
| Convertible    | 46        | 3.24%   |
| Mini pc        | 25        | 1.76%   |
| All in one     | 18        | 1.27%   |
| Tablet         | 12        | 0.84%   |
| Server         | 7         | 0.49%   |
| System on chip | 2         | 0.14%   |
| Stick pc       | 1         | 0.07%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1288      | 90.2%   |
| Enabled  | 140       | 9.8%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1409      | 99.16%  |
| Yes  | 12        | 0.84%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 384       | 26.82%  |
| 4.01-8.0        | 290       | 20.25%  |
| 8.01-16.0       | 252       | 17.6%   |
| 32.01-64.0      | 246       | 17.18%  |
| 3.01-4.0        | 123       | 8.59%   |
| 64.01-256.0     | 71        | 4.96%   |
| 24.01-32.0      | 47        | 3.28%   |
| 1.01-2.0        | 8         | 0.56%   |
| 2.01-3.0        | 6         | 0.42%   |
| More than 256.0 | 4         | 0.28%   |
| 0.51-1.0        | 1         | 0.07%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 393       | 25.87%  |
| 2.01-3.0   | 390       | 25.67%  |
| 3.01-4.0   | 304       | 20.01%  |
| 1.01-2.0   | 290       | 19.09%  |
| 8.01-16.0  | 99        | 6.52%   |
| 16.01-24.0 | 23        | 1.51%   |
| 0.51-1.0   | 8         | 0.53%   |
| 24.01-32.0 | 6         | 0.39%   |
| 32.01-64.0 | 4         | 0.26%   |
| 0.01-0.5   | 2         | 0.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 746       | 51.77%  |
| 2      | 409       | 28.38%  |
| 3      | 136       | 9.44%   |
| 4      | 70        | 4.86%   |
| 5      | 33        | 2.29%   |
| 6      | 19        | 1.32%   |
| 7      | 16        | 1.11%   |
| 9      | 3         | 0.21%   |
| 8      | 3         | 0.21%   |
| 0      | 3         | 0.21%   |
| 11     | 2         | 0.14%   |
| 12     | 1         | 0.07%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1037      | 72.67%  |
| Yes       | 390       | 27.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1171      | 82.29%  |
| No        | 252       | 17.71%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1164      | 81.74%  |
| No        | 260       | 18.26%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1018      | 70.99%  |
| No        | 416       | 29.01%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 309       | 21.7%   |
| Germany      | 160       | 11.24%  |
| Italy        | 93        | 6.53%   |
| France       | 84        | 5.9%    |
| Russia       | 79        | 5.55%   |
| UK           | 58        | 4.07%   |
| Brazil       | 55        | 3.86%   |
| Spain        | 44        | 3.09%   |
| Poland       | 42        | 2.95%   |
| Canada       | 33        | 2.32%   |
| Australia    | 31        | 2.18%   |
| India        | 28        | 1.97%   |
| Netherlands  | 25        | 1.76%   |
| Switzerland  | 22        | 1.54%   |
| Czechia      | 19        | 1.33%   |
| Argentina    | 19        | 1.33%   |
| Hungary      | 17        | 1.19%   |
| Belgium      | 14        | 0.98%   |
| Finland      | 13        | 0.91%   |
| Indonesia    | 12        | 0.84%   |
| Turkey       | 11        | 0.77%   |
| Austria      | 11        | 0.77%   |
| Portugal     | 10        | 0.7%    |
| Mexico       | 10        | 0.7%    |
| Bulgaria     | 10        | 0.7%    |
| Sweden       | 9         | 0.63%   |
| South Africa | 9         | 0.63%   |
| Slovenia     | 9         | 0.63%   |
| Serbia       | 9         | 0.63%   |
| Greece       | 9         | 0.63%   |
| Romania      | 8         | 0.56%   |
| Philippines  | 8         | 0.56%   |
| Norway       | 8         | 0.56%   |
| New Zealand  | 8         | 0.56%   |
| China        | 8         | 0.56%   |
| Thailand     | 7         | 0.49%   |
| Denmark      | 7         | 0.49%   |
| Singapore    | 6         | 0.42%   |
| Lithuania    | 6         | 0.42%   |
| Colombia     | 6         | 0.42%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 21        | 1.42%   |
| Milan             | 19        | 1.29%   |
| Berlin            | 19        | 1.29%   |
| Paris             | 12        | 0.81%   |
| Munich            | 10        | 0.68%   |
| Hamburg           | 10        | 0.68%   |
| Warsaw            | 9         | 0.61%   |
| St Petersburg     | 9         | 0.61%   |
| Madrid            | 9         | 0.61%   |
| Budapest          | 9         | 0.61%   |
| Sydney            | 8         | 0.54%   |
| Sao Paulo         | 8         | 0.54%   |
| Prague            | 8         | 0.54%   |
| Montreal          | 8         | 0.54%   |
| Frankfurt am Main | 8         | 0.54%   |
| Dallas            | 8         | 0.54%   |
| London            | 7         | 0.47%   |
| Castro Valley     | 7         | 0.47%   |
| Belgrade          | 7         | 0.47%   |
| Zurich            | 6         | 0.41%   |
| Vladivostok       | 6         | 0.41%   |
| Vienna            | 6         | 0.41%   |
| Singapore         | 6         | 0.41%   |
| Rome              | 6         | 0.41%   |
| New York          | 6         | 0.41%   |
| Houston           | 6         | 0.41%   |
| Cologne           | 6         | 0.41%   |
| Bengaluru         | 6         | 0.41%   |
| Amsterdam         | 6         | 0.41%   |
| Wroclaw           | 5         | 0.34%   |
| Rio de Janeiro    | 5         | 0.34%   |
| Melbourne         | 5         | 0.34%   |
| Krakow            | 5         | 0.34%   |
| Johannesburg      | 5         | 0.34%   |
| Istanbul          | 5         | 0.34%   |
| Auckland          | 5         | 0.34%   |
| Washington        | 4         | 0.27%   |
| Vilnius           | 4         | 0.27%   |
| Varna             | 4         | 0.27%   |
| Turin             | 4         | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 393       | 626    | 17.38%  |
| WDC                         | 290       | 424    | 12.83%  |
| Seagate                     | 252       | 424    | 11.15%  |
| Kingston                    | 144       | 173    | 6.37%   |
| SanDisk                     | 137       | 188    | 6.06%   |
| Toshiba                     | 116       | 162    | 5.13%   |
| Crucial                     | 91        | 111    | 4.02%   |
| SK hynix                    | 72        | 84     | 3.18%   |
| Unknown                     | 68        | 92     | 3.01%   |
| Intel                       | 65        | 79     | 2.87%   |
| Hitachi                     | 52        | 61     | 2.3%    |
| Micron Technology           | 51        | 55     | 2.26%   |
| KIOXIA                      | 34        | 37     | 1.5%    |
| HGST                        | 34        | 41     | 1.5%    |
| A-DATA Technology           | 34        | 41     | 1.5%    |
| China                       | 28        | 33     | 1.24%   |
| Apple                       | 21        | 25     | 0.93%   |
| Phison                      | 18        | 18     | 0.8%    |
| SPCC                        | 17        | 21     | 0.75%   |
| Phison Electronics          | 17        | 17     | 0.75%   |
| Patriot                     | 17        | 20     | 0.75%   |
| Silicon Motion              | 16        | 21     | 0.71%   |
| PNY                         | 15        | 31     | 0.66%   |
| Micron/Crucial Technology   | 13        | 17     | 0.57%   |
| Corsair                     | 12        | 14     | 0.53%   |
| Unknown                     | 12        | 12     | 0.53%   |
| Kingston Technology Company | 10        | 15     | 0.44%   |
| JMicron Technology          | 10        | 10     | 0.44%   |
| SSSTC                       | 8         | 8      | 0.35%   |
| Maxtor                      | 8         | 11     | 0.35%   |
| Lexar                       | 8         | 8      | 0.35%   |
| SABRENT                     | 7         | 9      | 0.31%   |
| OCZ                         | 7         | 7      | 0.31%   |
| Transcend                   | 6         | 7      | 0.27%   |
| Team                        | 6         | 6      | 0.27%   |
| Realtek Semiconductor       | 6         | 6      | 0.27%   |
| LITEON                      | 6         | 6      | 0.27%   |
| Intenso                     | 6         | 9      | 0.27%   |
| GOODRAM                     | 6         | 7      | 0.27%   |
| Hewlett-Packard             | 5         | 5      | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 32        | 1.26%   |
| Kingston SA400S37240G 240GB SSD                    | 24        | 0.94%   |
| Kingston SA400S37480G 480GB SSD                    | 23        | 0.9%    |
| Samsung SSD 860 EVO 500GB                          | 19        | 0.75%   |
| Samsung SSD 850 EVO 500GB                          | 17        | 0.67%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 17        | 0.67%   |
| Samsung SSD 860 EVO 1TB                            | 14        | 0.55%   |
| Toshiba DT01ACA100 1TB                             | 13        | 0.51%   |
| Samsung SSD 850 EVO 250GB                          | 13        | 0.51%   |
| Samsung SSD 980 1TB                                | 12        | 0.47%   |
| Samsung SSD 870 EVO 1TB                            | 12        | 0.47%   |
| Crucial CT1000MX500SSD1 1TB                        | 12        | 0.47%   |
| Unknown                                            | 12        | 0.47%   |
| Toshiba MQ01ABD100 1TB                             | 11        | 0.43%   |
| Seagate ST2000DM008-2FR102 2TB                     | 11        | 0.43%   |
| Sandisk WD Blue SN550 NVMe SSD 2TB                 | 11        | 0.43%   |
| Samsung SSD 980 PRO 1TB                            | 11        | 0.43%   |
| Samsung SSD 870 QVO 1TB                            | 11        | 0.43%   |
| Unknown MMC Card  64GB                             | 10        | 0.39%   |
| Unknown MMC Card  32GB                             | 10        | 0.39%   |
| Seagate ST4000DM004-2CV104 4TB                     | 10        | 0.39%   |
| SanDisk NVMe SSD Drive 1TB                         | 10        | 0.39%   |
| Samsung SSD 970 EVO Plus 500GB                     | 10        | 0.39%   |
| Samsung SSD 970 EVO Plus 1TB                       | 10        | 0.39%   |
| Crucial CT500MX500SSD1 500GB                       | 10        | 0.39%   |
| Seagate ST1000LM035-1RK172 1TB                     | 9         | 0.35%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB   | 9         | 0.35%   |
| Samsung SSD 870 EVO 500GB                          | 9         | 0.35%   |
| Crucial CT240BX500SSD1 240GB                       | 9         | 0.35%   |
| WDC WD10EZEX-08WN4A0 1TB                           | 8         | 0.31%   |
| Unknown MMC Card  128GB                            | 8         | 0.31%   |
| Toshiba MQ04ABF100 1TB                             | 8         | 0.31%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 8         | 0.31%   |
| Seagate Expansion 2TB                              | 8         | 0.31%   |
| Phison PS5013 E13 NVMe Controller 512GB            | 8         | 0.31%   |
| Kingston SA400S37960G 960GB SSD                    | 8         | 0.31%   |
| Crucial CT1000BX500SSD1 1TB                        | 8         | 0.31%   |
| Toshiba HDWD110 1TB                                | 7         | 0.28%   |
| Seagate ST3500418AS 500GB                          | 7         | 0.28%   |
| Seagate ST2000LM007-1R8174 2TB                     | 7         | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 238       | 401    | 35.26%  |
| WDC                 | 208       | 294    | 30.81%  |
| Toshiba             | 78        | 113    | 11.56%  |
| Hitachi             | 52        | 61     | 7.7%    |
| HGST                | 34        | 41     | 5.04%   |
| Samsung Electronics | 26        | 44     | 3.85%   |
| SABRENT             | 7         | 9      | 1.04%   |
| Maxtor              | 7         | 10     | 1.04%   |
| JMicron Technology  | 6         | 6      | 0.89%   |
| Apple               | 6         | 6      | 0.89%   |
| Unknown             | 5         | 5      | 0.74%   |
| SAGE                | 2         | 2      | 0.3%    |
| KESU                | 1         | 1      | 0.15%   |
| IET                 | 1         | 1      | 0.15%   |
| HPE                 | 1         | 6      | 0.15%   |
| HGST HTS            | 1         | 1      | 0.15%   |
| Hewlett-Packard     | 1         | 1      | 0.15%   |
| Fujitsu             | 1         | 1      | 0.15%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 189       | 285    | 25.23%  |
| Kingston            | 97        | 110    | 12.95%  |
| Crucial             | 71        | 87     | 9.48%   |
| SanDisk             | 63        | 82     | 8.41%   |
| WDC                 | 45        | 74     | 6.01%   |
| China               | 27        | 32     | 3.6%    |
| A-DATA Technology   | 27        | 32     | 3.6%    |
| Patriot             | 17        | 20     | 2.27%   |
| Intel               | 16        | 23     | 2.14%   |
| SPCC                | 14        | 15     | 1.87%   |
| PNY                 | 13        | 29     | 1.74%   |
| Micron Technology   | 13        | 13     | 1.74%   |
| SK hynix            | 10        | 10     | 1.34%   |
| Apple               | 9         | 9      | 1.2%    |
| Toshiba             | 8         | 11     | 1.07%   |
| OCZ                 | 7         | 7      | 0.93%   |
| Lexar               | 7         | 7      | 0.93%   |
| LITEON              | 6         | 6      | 0.8%    |
| GOODRAM             | 6         | 7      | 0.8%    |
| Transcend           | 5         | 5      | 0.67%   |
| Team                | 5         | 5      | 0.67%   |
| Verbatim            | 4         | 4      | 0.53%   |
| LITEONIT            | 4         | 4      | 0.53%   |
| Intenso             | 4         | 5      | 0.53%   |
| Hewlett-Packard     | 4         | 4      | 0.53%   |
| Corsair             | 4         | 4      | 0.53%   |
| Unknown             | 4         | 4      | 0.53%   |
| Plextor             | 3         | 3      | 0.4%    |
| Mushkin             | 3         | 4      | 0.4%    |
| KIOXIA-EXCERIA      | 3         | 5      | 0.4%    |
| Emtec               | 3         | 3      | 0.4%    |
| USB3.0              | 2         | 2      | 0.27%   |
| Smart               | 2         | 2      | 0.27%   |
| Seagate             | 2         | 3      | 0.27%   |
| Netac               | 2         | 2      | 0.27%   |
| LT                  | 2         | 4      | 0.27%   |
| KODAK               | 2         | 2      | 0.27%   |
| KingSpec            | 2         | 2      | 0.27%   |
| INNOVATION IT       | 2         | 2      | 0.27%   |
| Apacer              | 2         | 2      | 0.27%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 724       | 981    | 35.67%  |
| SSD     | 640       | 974    | 31.53%  |
| HDD     | 556       | 1003   | 27.39%  |
| MMC     | 61        | 73     | 3%      |
| Unknown | 49        | 71     | 2.41%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 893       | 1882   | 50.06%  |
| NVMe | 719       | 971    | 40.3%   |
| SAS  | 111       | 176    | 6.22%   |
| MMC  | 61        | 73     | 3.42%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 621       | 979    | 48.36%  |
| 0.51-1.0   | 381       | 538    | 29.67%  |
| 1.01-2.0   | 144       | 222    | 11.21%  |
| 3.01-4.0   | 68        | 141    | 5.3%    |
| 4.01-10.0  | 33        | 49     | 2.57%   |
| 2.01-3.0   | 26        | 31     | 2.02%   |
| 10.01-20.0 | 11        | 17     | 0.86%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 341       | 23.52%  |
| 101-250        | 291       | 20.07%  |
| 501-1000       | 279       | 19.24%  |
| 1001-2000      | 205       | 14.14%  |
| More than 3000 | 134       | 9.24%   |
| 2001-3000      | 83        | 5.72%   |
| 1-20           | 51        | 3.52%   |
| 51-100         | 48        | 3.31%   |
| 21-50          | 15        | 1.03%   |
| Unknown        | 3         | 0.21%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 284       | 19.19%  |
| 101-250        | 279       | 18.85%  |
| 21-50          | 201       | 13.58%  |
| 251-500        | 184       | 12.43%  |
| 51-100         | 183       | 12.36%  |
| 501-1000       | 157       | 10.61%  |
| 1001-2000      | 102       | 6.89%   |
| More than 3000 | 59        | 3.99%   |
| 2001-3000      | 28        | 1.89%   |
| Unknown        | 3         | 0.2%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 3         | 3      | 2.14%   |
| Samsung Electronics SSD 870 EVO 500GB | 3         | 3      | 2.14%   |
| Samsung Electronics SSD 870 EVO 1TB   | 3         | 3      | 2.14%   |
| HGST HTS545050A7E680 500GB            | 3         | 3      | 2.14%   |
| WDC WD10JPVX-60JC3T0 1TB              | 2         | 2      | 1.43%   |
| Toshiba MQ04ABF100 1TB                | 2         | 2      | 1.43%   |
| SK hynix BC711 HFM512GD3JX013N 512GB  | 2         | 2      | 1.43%   |
| SK hynix BC711 HFM256GD3JX013N 256GB  | 2         | 2      | 1.43%   |
| Seagate ST3500418AS 500GB             | 2         | 2      | 1.43%   |
| Seagate ST2000LM007-1R8174 2TB        | 2         | 2      | 1.43%   |
| SanDisk SSD PLUS 240GB                | 2         | 2      | 1.43%   |
| Samsung Electronics HM321HI 320GB     | 2         | 2      | 1.43%   |
| Samsung Electronics HD103SI 1TB       | 2         | 2      | 1.43%   |
| Maxtor STM3250310AS 250GB             | 2         | 3      | 1.43%   |
| Kingston SUV400S37240G 240GB SSD      | 2         | 2      | 1.43%   |
| Kingston SA400S37480G 480GB SSD       | 2         | 2      | 1.43%   |
| Hitachi HTS547550A9E384 500GB         | 2         | 2      | 1.43%   |
| Hitachi HDS721010CLA630 1TB           | 2         | 2      | 1.43%   |
| HGST HTS721010A9E630 1TB              | 2         | 2      | 1.43%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD      | 1         | 1      | 0.71%   |
| WDC WD7502ABYS-02A6B0 752GB           | 1         | 1      | 0.71%   |
| WDC WD5000AZRX-00A3KB0 500GB          | 1         | 1      | 0.71%   |
| WDC WD5000AVVS-63M8B0 500GB           | 1         | 1      | 0.71%   |
| WDC WD5000AAKS-00V1A0 500GB           | 1         | 1      | 0.71%   |
| WDC WD40EURX-63BMCY0 4TB              | 1         | 1      | 0.71%   |
| WDC WD40EFAX-68JH4N1 4TB              | 1         | 4      | 0.71%   |
| WDC WD3200JD-22KLB0 320GB             | 1         | 1      | 0.71%   |
| WDC WD30EZRX-00MMMB0 3TB              | 1         | 1      | 0.71%   |
| WDC WD30EFRX-68EUZN0 3TB              | 1         | 1      | 0.71%   |
| WDC WD20EFRX-68EUZN0 2TB              | 1         | 2      | 0.71%   |
| WDC WD20EADS-14R6B0 2TB               | 1         | 1      | 0.71%   |
| WDC WD10EZRX-00L4HB0 1TB              | 1         | 1      | 0.71%   |
| WDC WD10EZEX-22MFCA0 1TB              | 1         | 1      | 0.71%   |
| WDC WD10EZEX-08M2NA0 1TB              | 1         | 1      | 0.71%   |
| WDC WD10EURX-73C57Y0 1TB              | 1         | 1      | 0.71%   |
| WDC WD10EARS-00MVWB0 1TB              | 1         | 1      | 0.71%   |
| WDC WD10EADS-00L5B1 1TB               | 1         | 1      | 0.71%   |
| WDC WD10EACS-65D6B0 1TB               | 1         | 1      | 0.71%   |
| WDC WD1001FALS-40U9B0 1TB             | 1         | 1      | 0.71%   |
| VISIPRO SSD 256GB                     | 1         | 2      | 0.71%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 25        | 30     | 18.38%  |
| WDC                 | 20        | 26     | 14.71%  |
| Samsung Electronics | 17        | 30     | 12.5%   |
| Hitachi             | 11        | 11     | 8.09%   |
| Toshiba             | 9         | 10     | 6.62%   |
| Crucial             | 7         | 7      | 5.15%   |
| SK hynix            | 6         | 6      | 4.41%   |
| HGST                | 6         | 6      | 4.41%   |
| SanDisk             | 5         | 5      | 3.68%   |
| Kingston            | 5         | 5      | 3.68%   |
| Maxtor              | 3         | 4      | 2.21%   |
| A-DATA Technology   | 3         | 3      | 2.21%   |
| SSSTC               | 2         | 2      | 1.47%   |
| Micron Technology   | 2         | 2      | 1.47%   |
| Intel               | 2         | 5      | 1.47%   |
| VISIPRO             | 1         | 2      | 0.74%   |
| tecmiyo             | 1         | 3      | 0.74%   |
| T-FORCE             | 1         | 1      | 0.74%   |
| R580                | 1         | 1      | 0.74%   |
| Phison Electronics  | 1         | 1      | 0.74%   |
| OCZ                 | 1         | 1      | 0.74%   |
| LITEONIT            | 1         | 1      | 0.74%   |
| LITEON              | 1         | 1      | 0.74%   |
| Intenso             | 1         | 1      | 0.74%   |
| Corsair             | 1         | 1      | 0.74%   |
| China               | 1         | 1      | 0.74%   |
| BAITITON            | 1         | 1      | 0.74%   |
| Apple               | 1         | 1      | 0.74%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 25        | 30     | 32.05%  |
| WDC                 | 19        | 25     | 24.36%  |
| Hitachi             | 11        | 11     | 14.1%   |
| Toshiba             | 8         | 9      | 10.26%  |
| HGST                | 6         | 6      | 7.69%   |
| Samsung Electronics | 5         | 18     | 6.41%   |
| Maxtor              | 3         | 4      | 3.85%   |
| Apple               | 1         | 1      | 1.28%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 74        | 104    | 56.92%  |
| SSD  | 46        | 54     | 35.38%  |
| NVMe | 10        | 10     | 7.69%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Samsung Electronics HD502IJ 500GB | 1         | 1      | 50%     |
| Hitachi HTS547550A9E384 500GB     | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 50%     |
| Hitachi             | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 756       | 1404   | 47.1%   |
| Detected | 722       | 1528   | 44.98%  |
| Malfunc  | 126       | 168    | 7.85%   |
| Failed   | 1         | 2      | 0.06%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 850       | 42.74%  |
| AMD                                     | 314       | 15.79%  |
| Samsung Electronics                     | 217       | 10.91%  |
| SanDisk                                 | 125       | 6.28%   |
| SK hynix                                | 62        | 3.12%   |
| Kingston Technology Company             | 61        | 3.07%   |
| Phison Electronics                      | 47        | 2.36%   |
| Micron Technology                       | 38        | 1.91%   |
| Toshiba America Info Systems            | 33        | 1.66%   |
| Micron/Crucial Technology               | 33        | 1.66%   |
| KIOXIA                                  | 32        | 1.61%   |
| ASMedia Technology                      | 31        | 1.56%   |
| Silicon Motion                          | 19        | 0.96%   |
| JMicron Technology                      | 19        | 0.96%   |
| Marvell Technology Group                | 16        | 0.8%    |
| Realtek Semiconductor                   | 12        | 0.6%    |
| ADATA Technology                        | 12        | 0.6%    |
| Solid State Storage Technology          | 9         | 0.45%   |
| LSI Logic / Symbios Logic               | 7         | 0.35%   |
| Apple                                   | 7         | 0.35%   |
| Union Memory (Shenzhen)                 | 6         | 0.3%    |
| Seagate Technology                      | 5         | 0.25%   |
| Nvidia                                  | 5         | 0.25%   |
| Broadcom / LSI                          | 4         | 0.2%    |
| Shenzhen Longsys Electronics            | 3         | 0.15%   |
| MAXIO Technology (Hangzhou)             | 3         | 0.15%   |
| Zhaoxin                                 | 2         | 0.1%    |
| Solidigm                                | 2         | 0.1%    |
| Silicon Image                           | 2         | 0.1%    |
| Netac Technology                        | 2         | 0.1%    |
| Yangtze Memory Technologies             | 1         | 0.05%   |
| VIA Technologies                        | 1         | 0.05%   |
| Promise Technology                      | 1         | 0.05%   |
| OCZ Technology Group                    | 1         | 0.05%   |
| O2 Micro                                | 1         | 0.05%   |
| Lite-On Technology                      | 1         | 0.05%   |
| Lenovo                                  | 1         | 0.05%   |
| Jiangsu Xinsheng Intelligent Technology | 1         | 0.05%   |
| INNOGRIT                                | 1         | 0.05%   |
| Hewlett-Packard                         | 1         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 215       | 9.57%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 88        | 3.92%   |
| Intel Volume Management Device NVMe RAID Controller                            | 74        | 3.29%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 65        | 2.89%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 64        | 2.85%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 63        | 2.8%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 59        | 2.63%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 51        | 2.27%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 44        | 1.96%   |
| AMD 400 Series Chipset SATA Controller                                         | 43        | 1.91%   |
| AMD 500 Series Chipset SATA Controller                                         | 34        | 1.51%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 32        | 1.42%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 31        | 1.38%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 30        | 1.34%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 29        | 1.29%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 29        | 1.29%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 29        | 1.29%   |
| Intel Tiger Lake-LP SATA Controller                                            | 27        | 1.2%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 26        | 1.16%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 25        | 1.11%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 25        | 1.11%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 24        | 1.07%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 23        | 1.02%   |
| Intel SATA Controller [RAID mode]                                              | 23        | 1.02%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 22        | 0.98%   |
| Intel SSD 660P Series                                                          | 21        | 0.93%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 21        | 0.93%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 20        | 0.89%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 19        | 0.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 18        | 0.8%    |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 17        | 0.76%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 17        | 0.76%   |
| Intel Comet Lake SATA AHCI Controller                                          | 17        | 0.76%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 17        | 0.76%   |
| Phison E12 NVMe Controller                                                     | 15        | 0.67%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 15        | 0.67%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 15        | 0.67%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 14        | 0.62%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 14        | 0.62%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 14        | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1010      | 51.04%  |
| NVMe | 715       | 36.13%  |
| RAID | 156       | 7.88%   |
| IDE  | 90        | 4.55%   |
| SAS  | 6         | 0.3%    |
| SCSI | 2         | 0.1%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor        | Computers | Percent |
|---------------|-----------|---------|
| Intel         | 1011      | 71.15%  |
| AMD           | 405       | 28.5%   |
| CentaurHauls  | 2         | 0.14%   |
| ARM           | 2         | 0.14%   |
| sifive,u74-mc | 1         | 0.07%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 29        | 2.04%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 24        | 1.69%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 22        | 1.55%   |
| AMD Ryzen 7 5800H with Radeon Graphics  | 21        | 1.48%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 19        | 1.34%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 18        | 1.27%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 16        | 1.13%   |
| Intel 12th Gen Core i7-12700H           | 16        | 1.13%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 14        | 0.99%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 13        | 0.91%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 13        | 0.91%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 12        | 0.84%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 11        | 0.77%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 11        | 0.77%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 10        | 0.7%    |
| Intel Core i5-6200U CPU @ 2.30GHz       | 10        | 0.7%    |
| Intel Core i5-4590 CPU @ 3.30GHz        | 10        | 0.7%    |
| Intel 12th Gen Core i7-1255U            | 10        | 0.7%    |
| AMD Ryzen 5 5600X 6-Core Processor      | 10        | 0.7%    |
| Intel Core i7-7500U CPU @ 2.70GHz       | 9         | 0.63%   |
| Intel 12th Gen Core i7-1260P            | 9         | 0.63%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz | 9         | 0.63%   |
| AMD Ryzen 7 4800H with Radeon Graphics  | 9         | 0.63%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 8         | 0.56%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 8         | 0.56%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 8         | 0.56%   |
| AMD Ryzen 9 5900X 12-Core Processor     | 8         | 0.56%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 7         | 0.49%   |
| Intel Core i7-6700 CPU @ 3.40GHz        | 7         | 0.49%   |
| Intel Core i7-4790K CPU @ 4.00GHz       | 7         | 0.49%   |
| Intel Core i5-9600K CPU @ 3.70GHz       | 7         | 0.49%   |
| Intel Core i5-7300U CPU @ 2.60GHz       | 7         | 0.49%   |
| Intel Core i5-10400F CPU @ 2.90GHz      | 7         | 0.49%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 7         | 0.49%   |
| AMD Ryzen 5 5600G with Radeon Graphics  | 7         | 0.49%   |
| AMD Ryzen 5 4600H with Radeon Graphics  | 7         | 0.49%   |
| AMD Ryzen 5 3600 6-Core Processor       | 7         | 0.49%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 6         | 0.42%   |
| Intel Core i7-7700K CPU @ 4.20GHz       | 6         | 0.42%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz      | 6         | 0.42%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 294       | 20.69%  |
| Intel Core i5           | 270       | 19%     |
| Other                   | 219       | 15.41%  |
| AMD Ryzen 7             | 117       | 8.23%   |
| AMD Ryzen 5             | 107       | 7.53%   |
| Intel Core i3           | 65        | 4.57%   |
| Intel Celeron           | 45        | 3.17%   |
| AMD Ryzen 9             | 43        | 3.03%   |
| Intel Xeon              | 27        | 1.9%    |
| Intel Core 2 Duo        | 25        | 1.76%   |
| Intel Pentium           | 23        | 1.62%   |
| AMD Ryzen 3             | 23        | 1.62%   |
| AMD FX                  | 20        | 1.41%   |
| AMD Ryzen 7 PRO         | 15        | 1.06%   |
| Intel Core i9           | 14        | 0.99%   |
| AMD A6                  | 12        | 0.84%   |
| AMD A8                  | 9         | 0.63%   |
| Intel Pentium Silver    | 8         | 0.56%   |
| Intel Atom              | 7         | 0.49%   |
| AMD Ryzen 5 PRO         | 7         | 0.49%   |
| Intel Core 2 Quad       | 6         | 0.42%   |
| AMD Phenom II X4        | 6         | 0.42%   |
| AMD A10                 | 6         | 0.42%   |
| AMD Athlon              | 5         | 0.35%   |
| Intel Pentium Gold      | 4         | 0.28%   |
| Intel Pentium Dual-Core | 3         | 0.21%   |
| Intel Core m3           | 3         | 0.21%   |
| AMD Ryzen Threadripper  | 3         | 0.21%   |
| AMD Opteron             | 3         | 0.21%   |
| AMD E                   | 3         | 0.21%   |
| AMD Athlon II X2        | 3         | 0.21%   |
| AMD Athlon 64 X2        | 3         | 0.21%   |
| Intel Xeon Gold         | 2         | 0.14%   |
| AMD PRO A10             | 2         | 0.14%   |
| AMD Phenom II X6        | 2         | 0.14%   |
| AMD Phenom II X2        | 2         | 0.14%   |
| AMD Athlon II           | 2         | 0.14%   |
| AMD A4                  | 2         | 0.14%   |
| Intel Pentium D         | 1         | 0.07%   |
| Intel Core M            | 1         | 0.07%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 514       | 36.17%  |
| 2       | 367       | 25.83%  |
| 6       | 198       | 13.93%  |
| 8       | 182       | 12.81%  |
| 12      | 47        | 3.31%   |
| 14      | 33        | 2.32%   |
| 10      | 32        | 2.25%   |
| 16      | 24        | 1.69%   |
| 24      | 8         | 0.56%   |
| 1       | 7         | 0.49%   |
| 3       | 3         | 0.21%   |
| Unknown | 2         | 0.14%   |
| 44      | 1         | 0.07%   |
| 36      | 1         | 0.07%   |
| 20      | 1         | 0.07%   |
| 5       | 1         | 0.07%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1408      | 99.09%  |
| 2       | 11        | 0.77%   |
| Unknown | 2         | 0.14%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1105      | 77.49%  |
| 1       | 319       | 22.37%  |
| Unknown | 2         | 0.14%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1418      | 99.79%  |
| Unknown        | 2         | 0.14%   |
| 64-bit         | 1         | 0.07%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 734       | 50.76%  |
| 0x306a9    | 40        | 2.77%   |
| 0x0a50000c | 38        | 2.63%   |
| 0x806c1    | 37        | 2.56%   |
| 0x306c3    | 34        | 2.35%   |
| 0x906a3    | 33        | 2.28%   |
| 0x806ea    | 29        | 2.01%   |
| 0x906ea    | 26        | 1.8%    |
| 0x08608103 | 21        | 1.45%   |
| 0x206a7    | 20        | 1.38%   |
| 0x806ec    | 18        | 1.24%   |
| 0x08600106 | 18        | 1.24%   |
| 0x906e9    | 17        | 1.18%   |
| 0x08701021 | 17        | 1.18%   |
| 0x506e3    | 15        | 1.04%   |
| 0x806e9    | 13        | 0.9%    |
| 0x0a50000d | 13        | 0.9%    |
| 0x906ed    | 11        | 0.76%   |
| 0x406e3    | 11        | 0.76%   |
| 0x906a4    | 10        | 0.69%   |
| 0x08108109 | 10        | 0.69%   |
| 0x1067a    | 9         | 0.62%   |
| 0x0800820d | 9         | 0.62%   |
| 0xa0653    | 8         | 0.55%   |
| 0xa0652    | 8         | 0.55%   |
| 0x806c2    | 8         | 0.55%   |
| 0x706a8    | 8         | 0.55%   |
| 0x08608102 | 8         | 0.55%   |
| 0x010000c8 | 8         | 0.55%   |
| 0x706a1    | 7         | 0.48%   |
| 0x40651    | 7         | 0.48%   |
| 0x0a201016 | 7         | 0.48%   |
| 0xa0655    | 6         | 0.41%   |
| 0x90672    | 6         | 0.41%   |
| 0x806d1    | 6         | 0.41%   |
| 0x706e5    | 6         | 0.41%   |
| 0x0a404102 | 6         | 0.41%   |
| 0x06000852 | 6         | 0.41%   |
| 0x406f1    | 5         | 0.35%   |
| 0x40661    | 5         | 0.35%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 227       | 15.93%  |
| Unknown          | 121       | 8.49%   |
| Haswell          | 119       | 8.35%   |
| IvyBridge        | 110       | 7.72%   |
| Zen 3            | 107       | 7.51%   |
| TigerLake        | 81        | 5.68%   |
| Alderlake Hybrid | 75        | 5.26%   |
| Zen 2            | 69        | 4.84%   |
| Skylake          | 61        | 4.28%   |
| SandyBridge      | 57        | 4%      |
| Zen+             | 51        | 3.58%   |
| CometLake        | 43        | 3.02%   |
| Icelake          | 35        | 2.46%   |
| Goldmont plus    | 32        | 2.25%   |
| Zen              | 28        | 1.96%   |
| Piledriver       | 27        | 1.89%   |
| Penryn           | 27        | 1.89%   |
| Broadwell        | 25        | 1.75%   |
| Westmere         | 22        | 1.54%   |
| K10              | 18        | 1.26%   |
| Silvermont       | 14        | 0.98%   |
| Excavator        | 14        | 0.98%   |
| Nehalem          | 13        | 0.91%   |
| Core             | 12        | 0.84%   |
| Goldmont         | 8         | 0.56%   |
| Puma             | 5         | 0.35%   |
| Bobcat           | 5         | 0.35%   |
| Steamroller      | 4         | 0.28%   |
| K10 Llano        | 4         | 0.28%   |
| K8 Hammer        | 3         | 0.21%   |
| Bulldozer        | 2         | 0.14%   |
| Bonnell          | 2         | 0.14%   |
| Tremont          | 1         | 0.07%   |
| NetBurst         | 1         | 0.07%   |
| K8 & K10 hybrid  | 1         | 0.07%   |
| Jaguar           | 1         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 786       | 45.25%  |
| Nvidia                     | 518       | 29.82%  |
| AMD                        | 422       | 24.29%  |
| Matrox Electronics Systems | 6         | 0.35%   |
| ASPEED Technology          | 3         | 0.17%   |
| Zhaoxin                    | 2         | 0.12%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 71        | 4.01%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 62        | 3.5%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 53        | 2.99%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 43        | 2.43%   |
| AMD Lucienne                                                                          | 42        | 2.37%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                         | 39        | 2.2%    |
| Intel HD Graphics 620                                                                 | 38        | 2.14%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                             | 38        | 2.14%   |
| Intel UHD Graphics 620                                                                | 37        | 2.09%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 37        | 2.09%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 33        | 1.86%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller           | 29        | 1.64%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 26        | 1.47%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                    | 25        | 1.41%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 25        | 1.41%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                               | 23        | 1.3%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 22        | 1.24%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 22        | 1.24%   |
| Intel HD Graphics 630                                                                 | 22        | 1.24%   |
| Intel HD Graphics 530                                                                 | 22        | 1.24%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 19        | 1.07%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                           | 18        | 1.02%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 17        | 0.96%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 17        | 0.96%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 16        | 0.9%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 14        | 0.79%   |
| Intel HD Graphics 5500                                                                | 14        | 0.79%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 13        | 0.73%   |
| Nvidia GK208B [GeForce GT 710]                                                        | 13        | 0.73%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                | 13        | 0.73%   |
| AMD Rembrandt [Radeon 680M]                                                           | 13        | 0.73%   |
| Nvidia GP104 [GeForce GTX 1070]                                                       | 12        | 0.68%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                | 12        | 0.68%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                             | 12        | 0.68%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 11        | 0.62%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 11        | 0.62%   |
| Intel Iris Plus Graphics G7                                                           | 11        | 0.62%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 11        | 0.62%   |
| Nvidia TU117 [GeForce GTX 1650]                                                       | 10        | 0.56%   |
| Nvidia GP108 [GeForce GT 1030]                                                        | 10        | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 515       | 36.14%  |
| 1 x AMD                  | 311       | 21.82%  |
| 1 x Nvidia               | 276       | 19.37%  |
| Intel + Nvidia           | 190       | 13.33%  |
| AMD + Nvidia             | 44        | 3.09%   |
| Intel + AMD              | 42        | 2.95%   |
| 2 x AMD                  | 22        | 1.54%   |
| Other                    | 7         | 0.49%   |
| 2 x Nvidia               | 4         | 0.28%   |
| 1 x Matrox               | 3         | 0.21%   |
| 3 x Nvidia               | 2         | 0.14%   |
| 1 x Zhaoxin              | 2         | 0.14%   |
| Nvidia + ASPEED          | 2         | 0.14%   |
| AMD + Matrox             | 2         | 0.14%   |
| Nvidia + Matrox          | 1         | 0.07%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.07%   |
| 1 x ASPEED               | 1         | 0.07%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1032      | 72.07%  |
| Proprietary | 362       | 25.28%  |
| Unknown     | 38        | 2.65%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 922       | 64.03%  |
| 0.01-0.5   | 120       | 8.33%   |
| 1.01-2.0   | 113       | 7.85%   |
| 3.01-4.0   | 84        | 5.83%   |
| 7.01-8.0   | 63        | 4.38%   |
| 0.51-1.0   | 61        | 4.24%   |
| 5.01-6.0   | 43        | 2.99%   |
| 8.01-16.0  | 24        | 1.67%   |
| 16.01-24.0 | 5         | 0.35%   |
| 2.01-3.0   | 4         | 0.28%   |
| 4.01-5.0   | 1         | 0.07%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 203       | 12.03%  |
| BOE                     | 172       | 10.19%  |
| AU Optronics            | 166       | 9.83%   |
| Chimei Innolux          | 155       | 9.18%   |
| LG Display              | 134       | 7.94%   |
| Dell                    | 116       | 6.87%   |
| Goldstar                | 102       | 6.04%   |
| Hewlett-Packard         | 71        | 4.21%   |
| Acer                    | 53        | 3.14%   |
| Philips                 | 47        | 2.78%   |
| BenQ                    | 39        | 2.31%   |
| AOC                     | 34        | 2.01%   |
| Iiyama                  | 30        | 1.78%   |
| ASUSTek Computer        | 29        | 1.72%   |
| Apple                   | 29        | 1.72%   |
| Sharp                   | 27        | 1.6%    |
| Ancor Communications    | 27        | 1.6%    |
| InfoVision              | 20        | 1.18%   |
| Lenovo                  | 19        | 1.13%   |
| CSO                     | 14        | 0.83%   |
| Sony                    | 13        | 0.77%   |
| Chi Mei Optoelectronics | 12        | 0.71%   |
| ViewSonic               | 11        | 0.65%   |
| PANDA                   | 10        | 0.59%   |
| Eizo                    | 8         | 0.47%   |
| Sceptre Tech            | 6         | 0.36%   |
| Panasonic               | 6         | 0.36%   |
| NEC Computers           | 6         | 0.36%   |
| Gigabyte Technology     | 6         | 0.36%   |
| Vizio                   | 5         | 0.3%    |
| Fujitsu Siemens         | 5         | 0.3%    |
| RTK                     | 4         | 0.24%   |
| MSI                     | 4         | 0.24%   |
| Insignia                | 4         | 0.24%   |
| Idek Iiyama             | 4         | 0.24%   |
| HKC                     | 4         | 0.24%   |
| Mi                      | 3         | 0.18%   |
| Medion                  | 3         | 0.18%   |
| LG Electronics          | 3         | 0.18%   |
| HUAWEI                  | 3         | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 12        | 0.69%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 11        | 0.63%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 10        | 0.57%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 10        | 0.57%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                    | 9         | 0.52%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch          | 9         | 0.52%   |
| BOE LCD Monitor BOE084E 1920x1080 382x215mm 17.3-inch                     | 8         | 0.46%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 7         | 0.4%    |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch              | 6         | 0.34%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                 | 6         | 0.34%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                     | 6         | 0.34%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 6         | 0.34%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch     | 5         | 0.29%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch         | 5         | 0.29%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch              | 5         | 0.29%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                  | 5         | 0.29%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch          | 5         | 0.29%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 5         | 0.29%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                     | 5         | 0.29%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch            | 5         | 0.29%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 5         | 0.29%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 5         | 0.29%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch         | 4         | 0.23%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch              | 4         | 0.23%   |
| InfoVision LCD Monitor IVO0536 1920x1080 294x165mm 13.3-inch              | 4         | 0.23%   |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                       | 4         | 0.23%   |
| Dell S2340L DELD058 1920x1080 509x286mm 23.0-inch                         | 4         | 0.23%   |
| Dell P2314H DEL4099 1920x1080 509x286mm 23.0-inch                         | 4         | 0.23%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                     | 4         | 0.23%   |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                     | 4         | 0.23%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch            | 4         | 0.23%   |
| AOC 27G2G3 AOC2702 1920x1080 598x336mm 27.0-inch                          | 4         | 0.23%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch     | 4         | 0.23%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                   | 3         | 0.17%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch         | 3         | 0.17%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch         | 3         | 0.17%   |
| RTK LCD Monitor RTK1D1A 1920x1080 1020x570mm 46.0-inch                    | 3         | 0.17%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                        | 3         | 0.17%   |
| LG Display LCD Monitor LGD068D 1920x1080 309x174mm 14.0-inch              | 3         | 0.17%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch               | 3         | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 798       | 50.6%   |
| 1366x768 (WXGA)    | 192       | 12.18%  |
| 3840x2160 (4K)     | 118       | 7.48%   |
| 2560x1440 (QHD)    | 89        | 5.64%   |
| 1920x1200 (WUXGA)  | 71        | 4.5%    |
| 1600x900 (HD+)     | 46        | 2.92%   |
| 1680x1050 (WSXGA+) | 38        | 2.41%   |
| 2560x1600          | 35        | 2.22%   |
| 3440x1440          | 27        | 1.71%   |
| 1280x1024 (SXGA)   | 25        | 1.59%   |
| 2880x1800          | 18        | 1.14%   |
| 1440x900 (WXGA+)   | 17        | 1.08%   |
| 2560x1080          | 15        | 0.95%   |
| 1280x800 (WXGA)    | 10        | 0.63%   |
| 1360x768           | 9         | 0.57%   |
| 3840x1080          | 7         | 0.44%   |
| 2240x1400          | 6         | 0.38%   |
| 1920x540           | 6         | 0.38%   |
| Unknown            | 6         | 0.38%   |
| 2160x1440          | 4         | 0.25%   |
| 3840x2400          | 3         | 0.19%   |
| 3840x1600          | 3         | 0.19%   |
| 2256x1504          | 3         | 0.19%   |
| 1280x720 (HD)      | 3         | 0.19%   |
| 1024x768 (XGA)     | 3         | 0.19%   |
| 3072x1920          | 2         | 0.13%   |
| 2736x1824          | 2         | 0.13%   |
| 2520x1680          | 2         | 0.13%   |
| 1600x1200          | 2         | 0.13%   |
| 6160x1440          | 1         | 0.06%   |
| 5760x2160          | 1         | 0.06%   |
| 5760x1080          | 1         | 0.06%   |
| 480x1920           | 1         | 0.06%   |
| 4800x1080          | 1         | 0.06%   |
| 3840x1200          | 1         | 0.06%   |
| 3600x1200          | 1         | 0.06%   |
| 3200x1800 (QHD+)   | 1         | 0.06%   |
| 3000x2000          | 1         | 0.06%   |
| 2880x1920          | 1         | 0.06%   |
| 2880x1620          | 1         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 394       | 23.38%  |
| 24      | 159       | 9.44%   |
| 27      | 145       | 8.61%   |
| 14      | 140       | 8.31%   |
| 23      | 131       | 7.77%   |
| 13      | 131       | 7.77%   |
| 21      | 96        | 5.7%    |
| 17      | 88        | 5.22%   |
| 31      | 51        | 3.03%   |
| 16      | 41        | 2.43%   |
| 34      | 39        | 2.31%   |
| Unknown | 29        | 1.72%   |
| 19      | 28        | 1.66%   |
| 22      | 23        | 1.36%   |
| 18      | 21        | 1.25%   |
| 20      | 19        | 1.13%   |
| 12      | 16        | 0.95%   |
| 32      | 15        | 0.89%   |
| 72      | 14        | 0.83%   |
| 11      | 12        | 0.71%   |
| 54      | 9         | 0.53%   |
| 40      | 9         | 0.53%   |
| 25      | 8         | 0.47%   |
| 46      | 7         | 0.42%   |
| 84      | 6         | 0.36%   |
| 28      | 6         | 0.36%   |
| 65      | 4         | 0.24%   |
| 49      | 4         | 0.24%   |
| 48      | 4         | 0.24%   |
| 10      | 4         | 0.24%   |
| 52      | 3         | 0.18%   |
| 37      | 3         | 0.18%   |
| 36      | 3         | 0.18%   |
| 26      | 3         | 0.18%   |
| 69      | 2         | 0.12%   |
| 60      | 2         | 0.12%   |
| 55      | 2         | 0.12%   |
| 42      | 2         | 0.12%   |
| 29      | 2         | 0.12%   |
| 142     | 1         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 618       | 37.68%  |
| 501-600        | 389       | 23.72%  |
| 401-500        | 170       | 10.37%  |
| 351-400        | 112       | 6.83%   |
| 201-300        | 107       | 6.52%   |
| 601-700        | 78        | 4.76%   |
| 701-800        | 57        | 3.48%   |
| 1001-1500      | 39        | 2.38%   |
| Unknown        | 29        | 1.77%   |
| 1501-2000      | 23        | 1.4%    |
| 801-900        | 14        | 0.85%   |
| 901-1000       | 3         | 0.18%   |
| More than 2000 | 1         | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1130      | 77.34%  |
| 16/10   | 209       | 14.31%  |
| 21/9    | 45        | 3.08%   |
| 5/4     | 21        | 1.44%   |
| Unknown | 21        | 1.44%   |
| 3/2     | 18        | 1.23%   |
| 4/3     | 6         | 0.41%   |
| 32/9    | 6         | 0.41%   |
| 6/5     | 2         | 0.14%   |
| 1.96    | 1         | 0.07%   |
| 1.00    | 1         | 0.07%   |
| 0.25    | 1         | 0.07%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 402       | 24.28%  |
| 201-250        | 312       | 18.84%  |
| 81-90          | 215       | 12.98%  |
| 301-350        | 148       | 8.94%   |
| 351-500        | 110       | 6.64%   |
| 121-130        | 74        | 4.47%   |
| 151-200        | 69        | 4.17%   |
| 251-300        | 59        | 3.56%   |
| 71-80          | 58        | 3.5%    |
| More than 1000 | 50        | 3.02%   |
| 111-120        | 32        | 1.93%   |
| 501-1000       | 32        | 1.93%   |
| Unknown        | 29        | 1.75%   |
| 141-150        | 27        | 1.63%   |
| 61-70          | 13        | 0.79%   |
| 51-60          | 12        | 0.72%   |
| 131-140        | 7         | 0.42%   |
| 41-50          | 4         | 0.24%   |
| 91-100         | 3         | 0.18%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 499       | 31.4%   |
| 51-100        | 495       | 31.15%  |
| 101-120       | 323       | 20.33%  |
| 161-240       | 152       | 9.57%   |
| 1-50          | 55        | 3.46%   |
| More than 240 | 36        | 2.27%   |
| Unknown       | 29        | 1.83%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1053      | 72.82%  |
| 2     | 303       | 20.95%  |
| 3     | 43        | 2.97%   |
| 0     | 36        | 2.49%   |
| 4     | 11        | 0.76%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 789       | 36.13%  |
| Intel                             | 779       | 35.67%  |
| Qualcomm Atheros                  | 175       | 8.01%   |
| Broadcom                          | 96        | 4.4%    |
| MediaTek                          | 80        | 3.66%   |
| TP-Link                           | 28        | 1.28%   |
| Ralink Technology                 | 25        | 1.14%   |
| ASIX Electronics                  | 21        | 0.96%   |
| Samsung Electronics               | 15        | 0.69%   |
| Ralink                            | 14        | 0.64%   |
| Broadcom Limited                  | 13        | 0.6%    |
| Aquantia                          | 10        | 0.46%   |
| Marvell Technology Group          | 9         | 0.41%   |
| Sierra Wireless                   | 8         | 0.37%   |
| Lenovo                            | 8         | 0.37%   |
| Huawei Technologies               | 8         | 0.37%   |
| Xiaomi                            | 7         | 0.32%   |
| Qualcomm Atheros Communications   | 6         | 0.27%   |
| NetGear                           | 6         | 0.27%   |
| DisplayLink                       | 6         | 0.27%   |
| Dell                              | 6         | 0.27%   |
| Qualcomm                          | 5         | 0.23%   |
| Nvidia                            | 5         | 0.23%   |
| Edimax Technology                 | 5         | 0.23%   |
| Belkin Components                 | 4         | 0.18%   |
| Apple                             | 4         | 0.18%   |
| Hewlett-Packard                   | 3         | 0.14%   |
| Ericsson Business Mobile Networks | 3         | 0.14%   |
| D-Link                            | 3         | 0.14%   |
| ASUSTek Computer                  | 3         | 0.14%   |
| Wilocity                          | 2         | 0.09%   |
| VIA Technologies                  | 2         | 0.09%   |
| U-Blox                            | 2         | 0.09%   |
| Solarflare Communications         | 2         | 0.09%   |
| Motorola PCS                      | 2         | 0.09%   |
| JMicron Technology                | 2         | 0.09%   |
| IBM                               | 2         | 0.09%   |
| Google                            | 2         | 0.09%   |
| D-Link System                     | 2         | 0.09%   |
| ZyXEL Communications              | 1         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 501       | 19.43%  |
| Intel Wi-Fi 6 AX200                                                    | 87        | 3.37%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 58        | 2.25%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 58        | 2.25%   |
| Intel Wi-Fi 6 AX201                                                    | 58        | 2.25%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 57        | 2.21%   |
| Realtek RTL8125 2.5GbE Controller                                      | 54        | 2.09%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 52        | 2.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 47        | 1.82%   |
| Intel Wireless 8265 / 8275                                             | 46        | 1.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 44        | 1.71%   |
| Intel I211 Gigabit Network Connection                                  | 40        | 1.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 38        | 1.47%   |
| Intel Ethernet Controller I225-V                                       | 36        | 1.4%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 28        | 1.09%   |
| Intel Wireless 7265                                                    | 28        | 1.09%   |
| Intel Wireless 7260                                                    | 27        | 1.05%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 27        | 1.05%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 26        | 1.01%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 26        | 1.01%   |
| Intel Ethernet Connection I217-LM                                      | 25        | 0.97%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 24        | 0.93%   |
| Intel Ethernet Connection (2) I219-V                                   | 22        | 0.85%   |
| Intel Wireless 8260                                                    | 21        | 0.81%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 21        | 0.81%   |
| Intel Wireless 3165                                                    | 19        | 0.74%   |
| Intel Ethernet Connection (7) I219-V                                   | 19        | 0.74%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 19        | 0.74%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 19        | 0.74%   |
| ASIX AX88179 Gigabit Ethernet                                          | 19        | 0.74%   |
| Intel Ethernet Connection (4) I219-LM                                  | 18        | 0.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 16        | 0.62%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 15        | 0.58%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 15        | 0.58%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 15        | 0.58%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 14        | 0.54%   |
| Realtek 802.11ac NIC                                                   | 14        | 0.54%   |
| Intel 82579V Gigabit Network Connection                                | 14        | 0.54%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 13        | 0.5%    |
| Samsung Galaxy series, misc. (tethering mode)                          | 12        | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 592       | 48.25%  |
| Realtek Semiconductor           | 225       | 18.34%  |
| Qualcomm Atheros                | 131       | 10.68%  |
| MediaTek                        | 79        | 6.44%   |
| Broadcom                        | 71        | 5.79%   |
| Ralink Technology               | 25        | 2.04%   |
| TP-Link                         | 23        | 1.87%   |
| Ralink                          | 14        | 1.14%   |
| Broadcom Limited                | 9         | 0.73%   |
| Sierra Wireless                 | 8         | 0.65%   |
| Qualcomm Atheros Communications | 6         | 0.49%   |
| NetGear                         | 6         | 0.49%   |
| Edimax Technology               | 5         | 0.41%   |
| Dell                            | 5         | 0.41%   |
| Qualcomm                        | 4         | 0.33%   |
| Belkin Components               | 4         | 0.33%   |
| D-Link                          | 3         | 0.24%   |
| ASUSTek Computer                | 3         | 0.24%   |
| Wilocity                        | 2         | 0.16%   |
| Marvell Technology Group        | 2         | 0.16%   |
| D-Link System                   | 2         | 0.16%   |
| ZyXEL Communications            | 1         | 0.08%   |
| Quectel Wireless Solutions      | 1         | 0.08%   |
| Microsoft                       | 1         | 0.08%   |
| Mercucys                        | 1         | 0.08%   |
| Linksys                         | 1         | 0.08%   |
| LG Electronics                  | 1         | 0.08%   |
| FIBOCOM                         | 1         | 0.08%   |
| Acer Peripherals (now BenQ)     | 1         | 0.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 87        | 6.99%   |
| Intel Wi-Fi 6 AX201                                            | 58        | 4.66%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 57        | 4.58%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 52        | 4.18%   |
| Intel Wireless 8265 / 8275                                     | 46        | 3.69%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 44        | 3.53%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 38        | 3.05%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 28        | 2.25%   |
| Intel Wireless 7265                                            | 28        | 2.25%   |
| Intel Wireless 7260                                            | 27        | 2.17%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 27        | 2.17%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 26        | 2.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 26        | 2.09%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 24        | 1.93%   |
| Intel Wireless 8260                                            | 21        | 1.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 21        | 1.69%   |
| Intel Wireless 3165                                            | 19        | 1.53%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 19        | 1.53%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 19        | 1.53%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 16        | 1.29%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 15        | 1.2%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 15        | 1.2%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 15        | 1.2%    |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 14        | 1.12%   |
| Realtek 802.11ac NIC                                           | 14        | 1.12%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 13        | 1.04%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 12        | 0.96%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 12        | 0.96%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 12        | 0.96%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 11        | 0.88%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 11        | 0.88%   |
| Ralink MT7601U Wireless Adapter                                | 10        | 0.8%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 10        | 0.8%    |
| Intel Raptor Lake PCH CNVi WiFi                                | 10        | 0.8%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 10        | 0.8%    |
| Intel Wireless 3160                                            | 9         | 0.72%   |
| Intel Raptor Lake-S PCH CNVi WiFi                              | 9         | 0.72%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 9         | 0.72%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 8         | 0.64%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 8         | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 678       | 53.22%  |
| Intel                      | 387       | 30.38%  |
| Qualcomm Atheros           | 49        | 3.85%   |
| Broadcom                   | 40        | 3.14%   |
| ASIX Electronics           | 21        | 1.65%   |
| Samsung Electronics        | 15        | 1.18%   |
| Aquantia                   | 10        | 0.78%   |
| Lenovo                     | 8         | 0.63%   |
| Huawei Technologies        | 8         | 0.63%   |
| Xiaomi                     | 7         | 0.55%   |
| Marvell Technology Group   | 7         | 0.55%   |
| DisplayLink                | 6         | 0.47%   |
| TP-Link                    | 5         | 0.39%   |
| Nvidia                     | 5         | 0.39%   |
| Broadcom Limited           | 4         | 0.31%   |
| Apple                      | 4         | 0.31%   |
| VIA Technologies           | 2         | 0.16%   |
| Solarflare Communications  | 2         | 0.16%   |
| JMicron Technology         | 2         | 0.16%   |
| IBM                        | 2         | 0.16%   |
| Google                     | 2         | 0.16%   |
| ZTE WCDMA Technologies MSM | 1         | 0.08%   |
| Spreadtrum Communications  | 1         | 0.08%   |
| Qualcomm                   | 1         | 0.08%   |
| OPPO Electronics           | 1         | 0.08%   |
| Motorola PCS               | 1         | 0.08%   |
| Mellanox Technologies      | 1         | 0.08%   |
| MediaTek                   | 1         | 0.08%   |
| ICS Advent                 | 1         | 0.08%   |
| Hewlett-Packard            | 1         | 0.08%   |
| American Megatrends        | 1         | 0.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 501       | 38.16%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 58        | 4.42%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 58        | 4.42%   |
| Realtek RTL8125 2.5GbE Controller                                              | 54        | 4.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 47        | 3.58%   |
| Intel I211 Gigabit Network Connection                                          | 40        | 3.05%   |
| Intel Ethernet Controller I225-V                                               | 36        | 2.74%   |
| Intel Ethernet Connection I217-LM                                              | 25        | 1.9%    |
| Intel Ethernet Connection (2) I219-V                                           | 22        | 1.68%   |
| Intel Ethernet Connection (7) I219-V                                           | 19        | 1.45%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 19        | 1.45%   |
| Intel Ethernet Connection (4) I219-LM                                          | 18        | 1.37%   |
| Intel 82579V Gigabit Network Connection                                        | 14        | 1.07%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 12        | 0.91%   |
| Intel Ethernet Connection (2) I218-V                                           | 12        | 0.91%   |
| Intel I210 Gigabit Network Connection                                          | 11        | 0.84%   |
| Realtek Killer E2600 GbE Controller                                            | 10        | 0.76%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 10        | 0.76%   |
| Intel Ethernet Connection I219-LM                                              | 9         | 0.69%   |
| Intel 82574L Gigabit Network Connection                                        | 9         | 0.69%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 8         | 0.61%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 8         | 0.61%   |
| Intel Ethernet Connection (7) I219-LM                                          | 8         | 0.61%   |
| Intel Ethernet Connection (5) I219-LM                                          | 8         | 0.61%   |
| Intel Ethernet Connection (2) I219-LM                                          | 8         | 0.61%   |
| Intel Ethernet Connection (16) I219-LM                                         | 8         | 0.61%   |
| Intel Ethernet Connection (10) I219-V                                          | 8         | 0.61%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 8         | 0.61%   |
| Intel Ethernet Connection (4) I219-V                                           | 7         | 0.53%   |
| Intel Ethernet Connection (13) I219-V                                          | 7         | 0.53%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 7         | 0.53%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 6         | 0.46%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 6         | 0.46%   |
| Intel Ethernet Connection I217-V                                               | 6         | 0.46%   |
| Intel Ethernet Connection (3) I218-LM                                          | 6         | 0.46%   |
| Intel Ethernet Connection (14) I219-V                                          | 6         | 0.46%   |
| Huawei VTR-L09                                                                 | 6         | 0.46%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                              | 6         | 0.46%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 5         | 0.38%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 5         | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1168      | 49.72%  |
| WiFi     | 1162      | 49.47%  |
| Modem    | 13        | 0.55%   |
| Unknown  | 6         | 0.26%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 904       | 60.55%  |
| Ethernet | 589       | 39.45%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 752       | 52.92%  |
| 1     | 596       | 41.94%  |
| 3     | 41        | 2.89%   |
| 0     | 23        | 1.62%   |
| 4     | 7         | 0.49%   |
| 6     | 2         | 0.14%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 999       | 69.67%  |
| Yes  | 435       | 30.33%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 523       | 50.58%  |
| Realtek Semiconductor           | 113       | 10.93%  |
| Cambridge Silicon Radio         | 64        | 6.19%   |
| Qualcomm Atheros Communications | 56        | 5.42%   |
| IMC Networks                    | 52        | 5.03%   |
| Broadcom                        | 44        | 4.26%   |
| Foxconn / Hon Hai               | 36        | 3.48%   |
| Lite-On Technology              | 32        | 3.09%   |
| Apple                           | 26        | 2.51%   |
| ASUSTek Computer                | 22        | 2.13%   |
| MediaTek                        | 14        | 1.35%   |
| TP-Link                         | 8         | 0.77%   |
| Realtek                         | 7         | 0.68%   |
| Dell                            | 7         | 0.68%   |
| Ralink                          | 6         | 0.58%   |
| Toshiba                         | 5         | 0.48%   |
| Edimax Technology               | 4         | 0.39%   |
| Hewlett-Packard                 | 3         | 0.29%   |
| Marvell Semiconductor           | 2         | 0.19%   |
| Alps Electric                   | 2         | 0.19%   |
| USI                             | 1         | 0.1%    |
| SiW                             | 1         | 0.1%    |
| SINO WEALTH                     | 1         | 0.1%    |
| Foxconn International           | 1         | 0.1%    |
| Dynex                           | 1         | 0.1%    |
| D-Link                          | 1         | 0.1%    |
| Conwise Technology              | 1         | 0.1%    |
| Chicony Electronics             | 1         | 0.1%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 114       | 11%     |
| Intel AX200 Bluetooth                               | 84        | 8.11%   |
| Intel Bluetooth wireless interface                  | 79        | 7.63%   |
| Realtek Bluetooth Radio                             | 71        | 6.85%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 64        | 6.18%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 64        | 6.18%   |
| Intel AX211 Bluetooth                               | 62        | 5.98%   |
| Intel Bluetooth Device                              | 60        | 5.79%   |
| Qualcomm Atheros  Bluetooth Device                  | 29        | 2.8%    |
| IMC Networks Wireless_Device                        | 23        | 2.22%   |
| Realtek 802.11ac WLAN Adapter                       | 22        | 2.12%   |
| Intel AX210 Bluetooth                               | 22        | 2.12%   |
| Lite-On Wireless_Device                             | 17        | 1.64%   |
| IMC Networks Bluetooth Radio                        | 17        | 1.64%   |
| Apple Bluetooth Host Controller                     | 17        | 1.64%   |
| Realtek  Bluetooth 4.2 Adapter                      | 15        | 1.45%   |
| Intel Wireless-AC 3168 Bluetooth                    | 15        | 1.45%   |
| MediaTek Wireless_Device                            | 14        | 1.35%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 14        | 1.35%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 13        | 1.25%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 12        | 1.16%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 10        | 0.97%   |
| Broadcom HP Portable SoftSailing                    | 10        | 0.97%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 9         | 0.87%   |
| ASUS ASUS USB-BT500                                 | 9         | 0.87%   |
| TP-Link UB500 Adapter                               | 8         | 0.77%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 8         | 0.77%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 8         | 0.77%   |
| Realtek Bluetooth Radio                             | 7         | 0.68%   |
| Foxconn / Hon Hai Bluetooth Device                  | 7         | 0.68%   |
| Ralink RT3290 Bluetooth                             | 6         | 0.58%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 5         | 0.48%   |
| IMC Networks Bluetooth Device                       | 5         | 0.48%   |
| Foxconn / Hon Hai Wireless_Device                   | 5         | 0.48%   |
| Foxconn / Hon Hai MediaTek MT7921 Bluetooth         | 5         | 0.48%   |
| Apple Bluetooth USB Host Controller                 | 5         | 0.48%   |
| Dell DW375 Bluetooth Module                         | 4         | 0.39%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 0.39%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 4         | 0.39%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 3         | 0.29%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 988       | 46.58%  |
| AMD                        | 472       | 22.25%  |
| Nvidia                     | 403       | 19%     |
| C-Media Electronics        | 34        | 1.6%    |
| GN Netcom                  | 17        | 0.8%    |
| Logitech                   | 14        | 0.66%   |
| JMTek                      | 13        | 0.61%   |
| Hewlett-Packard            | 10        | 0.47%   |
| Generalplus Technology     | 10        | 0.47%   |
| Lenovo                     | 9         | 0.42%   |
| Creative Labs              | 8         | 0.38%   |
| Texas Instruments          | 7         | 0.33%   |
| Realtek Semiconductor      | 7         | 0.33%   |
| Micro Star International   | 7         | 0.33%   |
| Focusrite-Novation         | 7         | 0.33%   |
| Razer USA                  | 6         | 0.28%   |
| Corsair                    | 6         | 0.28%   |
| Apple                      | 6         | 0.28%   |
| ASUSTek Computer           | 5         | 0.24%   |
| VIA Technologies           | 4         | 0.19%   |
| Kingston Technology        | 4         | 0.19%   |
| Blue Microphones           | 4         | 0.19%   |
| Tenx Technology            | 3         | 0.14%   |
| Samson Technologies        | 3         | 0.14%   |
| KORG                       | 3         | 0.14%   |
| Creative Technology        | 3         | 0.14%   |
| Arturia                    | 3         | 0.14%   |
| AKAI Professional M.I.     | 3         | 0.14%   |
| ZOOM                       | 2         | 0.09%   |
| Zhaoxin                    | 2         | 0.09%   |
| TerraTec Electronic        | 2         | 0.09%   |
| SteelSeries ApS            | 2         | 0.09%   |
| Sony                       | 2         | 0.09%   |
| PreSonus Audio Electronics | 2         | 0.09%   |
| Plantronics                | 2         | 0.09%   |
| Nordic Semiconductor ASA   | 2         | 0.09%   |
| Medeli Electronics         | 2         | 0.09%   |
| M-Audio                    | 2         | 0.09%   |
| DSEA A/S                   | 2         | 0.09%   |
| BY EDIFIER                 | 2         | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 211       | 8.36%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 136       | 5.39%   |
| Intel Sunrise Point-LP HD Audio                                            | 103       | 4.08%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 99        | 3.92%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 81        | 3.21%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 76        | 3.01%   |
| Intel Cannon Lake PCH cAVS                                                 | 67        | 2.65%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 67        | 2.65%   |
| AMD Starship/Matisse HD Audio Controller                                   | 63        | 2.5%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 57        | 2.26%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 56        | 2.22%   |
| Nvidia GP107GL High Definition Audio Controller                            | 42        | 1.66%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 41        | 1.62%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 37        | 1.47%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 35        | 1.39%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 33        | 1.31%   |
| Intel 200 Series PCH HD Audio                                              | 32        | 1.27%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 31        | 1.23%   |
| Nvidia TU116 High Definition Audio Controller                              | 29        | 1.15%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 29        | 1.15%   |
| Nvidia GA106 High Definition Audio Controller                              | 27        | 1.07%   |
| Intel Comet Lake PCH cAVS                                                  | 27        | 1.07%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 27        | 1.07%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 26        | 1.03%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 24        | 0.95%   |
| AMD FCH Azalia Controller                                                  | 24        | 0.95%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 23        | 0.91%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 23        | 0.91%   |
| Nvidia TU106 High Definition Audio Controller                              | 22        | 0.87%   |
| Nvidia GP104 High Definition Audio Controller                              | 22        | 0.87%   |
| Nvidia GA104 High Definition Audio Controller                              | 22        | 0.87%   |
| Nvidia Audio device                                                        | 21        | 0.83%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 21        | 0.83%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 20        | 0.79%   |
| Intel Comet Lake PCH-LP cAVS                                               | 20        | 0.79%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 18        | 0.71%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 18        | 0.71%   |
| Intel Broadwell-U Audio Controller                                         | 18        | 0.71%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 18        | 0.71%   |
| Nvidia GF108 High Definition Audio Controller                              | 17        | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Samsung Electronics        | 252       | 23.31%  |
| SK hynix                   | 160       | 14.8%   |
| Kingston                   | 131       | 12.12%  |
| Micron Technology          | 120       | 11.1%   |
| Crucial                    | 91        | 8.42%   |
| Corsair                    | 67        | 6.2%    |
| Unknown                    | 49        | 4.53%   |
| G.Skill                    | 44        | 4.07%   |
| A-DATA Technology          | 22        | 2.04%   |
| Unknown (ABCD)             | 19        | 1.76%   |
| Unknown                    | 14        | 1.3%    |
| Ramaxel Technology         | 11        | 1.02%   |
| Elpida                     | 11        | 1.02%   |
| Team                       | 9         | 0.83%   |
| Nanya Technology           | 9         | 0.83%   |
| Patriot                    | 7         | 0.65%   |
| Transcend                  | 6         | 0.56%   |
| Smart                      | 6         | 0.56%   |
| Silicon Power              | 4         | 0.37%   |
| AMD                        | 4         | 0.37%   |
| Wilk                       | 3         | 0.28%   |
| PNY                        | 3         | 0.28%   |
| Lexar                      | 3         | 0.28%   |
| ff                         | 3         | 0.28%   |
| 4ea5                       | 3         | 0.28%   |
| Teikon                     | 2         | 0.19%   |
| GOODRAM                    | 2         | 0.19%   |
| Atermiter                  | 2         | 0.19%   |
| Xi'an UniIC Semiconductors | 1         | 0.09%   |
| V-Color                    | 1         | 0.09%   |
| Unknown (8A02)             | 1         | 0.09%   |
| Unknown (08C8)             | 1         | 0.09%   |
| Unifosa                    | 1         | 0.09%   |
| Super Talent               | 1         | 0.09%   |
| Shenzhen Zhongteng         | 1         | 0.09%   |
| Shenzhen WODPOSIT          | 1         | 0.09%   |
| SHARETRONIC                | 1         | 0.09%   |
| Sesame                     | 1         | 0.09%   |
| Qumo                       | 1         | 0.09%   |
| Qimonda                    | 1         | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 15        | 1.31%   |
| Unknown                                                          | 14        | 1.22%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 13        | 1.14%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 10        | 0.87%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 10        | 0.87%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 9         | 0.79%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 9         | 0.79%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 9         | 0.79%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 0.7%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 7         | 0.61%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 7         | 0.61%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 7         | 0.61%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 7         | 0.61%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 6         | 0.52%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 6         | 0.52%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.52%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 6         | 0.52%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 6         | 0.52%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 6         | 0.52%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.44%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 5         | 0.44%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 0.44%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 5         | 0.44%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.44%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.44%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 5         | 0.44%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 5         | 0.44%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.44%   |
| Micron RAM MTC4C10163S1SC48BA1 8GB SODIMM DDR5 4800MT/s          | 5         | 0.44%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 5         | 0.44%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 4         | 0.35%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 4         | 0.35%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s                      | 4         | 0.35%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 4         | 0.35%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 0.35%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 4         | 0.35%   |
| Samsung RAM M471A2G43BB2-CWE 16GB SODIMM DDR4 3200MT/s           | 4         | 0.35%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 4         | 0.35%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s            | 4         | 0.35%   |
| Micron RAM Module 8GB SODIMM DDR4 3200MT/s                       | 4         | 0.35%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 535       | 58.6%   |
| DDR3    | 208       | 22.78%  |
| LPDDR4  | 57        | 6.24%   |
| DDR5    | 40        | 4.38%   |
| LPDDR5  | 18        | 1.97%   |
| Unknown | 15        | 1.64%   |
| DDR2    | 14        | 1.53%   |
| SDRAM   | 13        | 1.42%   |
| LPDDR3  | 10        | 1.1%    |
| DDR     | 2         | 0.22%   |
| DRAM    | 1         | 0.11%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 522       | 56.8%   |
| DIMM         | 291       | 31.66%  |
| Row Of Chips | 95        | 10.34%  |
| Chip         | 5         | 0.54%   |
| Unknown      | 5         | 0.54%   |
| RIMM         | 1         | 0.11%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 434       | 43.57%  |
| 16384 | 226       | 22.69%  |
| 4096  | 202       | 20.28%  |
| 2048  | 67        | 6.73%   |
| 32768 | 59        | 5.92%   |
| 1024  | 8         | 0.8%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 256       | 25.94%  |
| 1600    | 140       | 14.18%  |
| 2667    | 130       | 13.17%  |
| 2400    | 86        | 8.71%   |
| 1333    | 52        | 5.27%   |
| 2133    | 36        | 3.65%   |
| 3600    | 34        | 3.44%   |
| 4800    | 26        | 2.63%   |
| 4267    | 24        | 2.43%   |
| 1867    | 18        | 1.82%   |
| 6400    | 17        | 1.72%   |
| 2666    | 13        | 1.32%   |
| 1334    | 13        | 1.32%   |
| 3800    | 8         | 0.81%   |
| 3266    | 7         | 0.71%   |
| 3000    | 7         | 0.71%   |
| 1866    | 7         | 0.71%   |
| 1066    | 7         | 0.71%   |
| 5600    | 6         | 0.61%   |
| 2933    | 6         | 0.61%   |
| 800     | 6         | 0.61%   |
| 667     | 6         | 0.61%   |
| Unknown | 6         | 0.61%   |
| 4266    | 5         | 0.51%   |
| 3866    | 5         | 0.51%   |
| 3666    | 5         | 0.51%   |
| 6000    | 4         | 0.41%   |
| 3066    | 4         | 0.41%   |
| 2800    | 4         | 0.41%   |
| 1648    | 4         | 0.41%   |
| 3733    | 3         | 0.3%    |
| 3333    | 3         | 0.3%    |
| 2048    | 3         | 0.3%    |
| 400     | 3         | 0.3%    |
| 8400    | 2         | 0.2%    |
| 5808    | 2         | 0.2%    |
| 4199    | 2         | 0.2%    |
| 4000    | 2         | 0.2%    |
| 3400    | 2         | 0.2%    |
| 3100    | 2         | 0.2%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 12        | 33.33%  |
| Seiko Epson         | 6         | 16.67%  |
| Brother Industries  | 6         | 16.67%  |
| Canon               | 4         | 11.11%  |
| Samsung Electronics | 2         | 5.56%   |
| Zebra               | 1         | 2.78%   |
| Xerox               | 1         | 2.78%   |
| Prolific Technology | 1         | 2.78%   |
| Kyocera             | 1         | 2.78%   |
| Dymo-CoStar         | 1         | 2.78%   |
| Datamax-O'Neil      | 1         | 2.78%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Seiko Epson L360 Series               | 2         | 5.56%   |
| Seiko Epson L3110 Series              | 2         | 5.56%   |
| Samsung M2070 Series                  | 2         | 5.56%   |
| Brother MFC-J460DW                    | 2         | 5.56%   |
| Zebra Thrmal 2844                     | 1         | 2.78%   |
| Xerox Phaser 3140 and 3155            | 1         | 2.78%   |
| Seiko Epson XP-3100 Series            | 1         | 2.78%   |
| Seiko Epson ET-2700 Series            | 1         | 2.78%   |
| Prolific PL2305 Parallel Port         | 1         | 2.78%   |
| Kyocera Mita FS-820                   | 1         | 2.78%   |
| HP OfficeJet Pro 7730 series          | 1         | 2.78%   |
| HP OfficeJet 5500 series              | 1         | 2.78%   |
| HP LaserJet Professional P 1102w      | 1         | 2.78%   |
| HP LaserJet P2015 series              | 1         | 2.78%   |
| HP LaserJet 1022                      | 1         | 2.78%   |
| HP LaserJet 1012                      | 1         | 2.78%   |
| HP ENVY Photo 6200 series             | 1         | 2.78%   |
| HP ENVY 4500 series                   | 1         | 2.78%   |
| HP DeskJet D2300                      | 1         | 2.78%   |
| HP DeskJet 3700 series                | 1         | 2.78%   |
| HP DeskJet 3630 series                | 1         | 2.78%   |
| HP ColorLaserJet M253-M254            | 1         | 2.78%   |
| Dymo-CoStar LabelWriter 450           | 1         | 2.78%   |
| Datamax-O'Neil Datamax E-4304         | 1         | 2.78%   |
| Canon PIXMA MX470 Series              | 1         | 2.78%   |
| Canon PIXMA MG5500 Series             | 1         | 2.78%   |
| Canon LaserShot LBP-1120 Printer      | 1         | 2.78%   |
| Canon iP2600 series                   | 1         | 2.78%   |
| Brother PT-P700 P-touch Label Printer | 1         | 2.78%   |
| Brother MFC-L2750DW series            | 1         | 2.78%   |
| Brother HL-2230 series                | 1         | 2.78%   |
| Brother DCP-L2500D                    | 1         | 2.78%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Computers | Percent |
|----------------|-----------|---------|
| Canon          | 6         | 75%     |
| Seiko Epson    | 1         | 12.5%   |
| Mustek Systems | 1         | 12.5%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40      | 2         | 25%     |
| Seiko Epson GT-X820 [Perfection V600 Photo] | 1         | 12.5%   |
| Mustek Systems ScanExpress A3 USB 1200 PRO  | 1         | 12.5%   |
| Canon CanoScan N670U/N676U/LiDE 20          | 1         | 12.5%   |
| Canon CanoScan LiDE 220                     | 1         | 12.5%   |
| Canon CanoScan LiDE 210                     | 1         | 12.5%   |
| Canon CanoScan LiDE 110                     | 1         | 12.5%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 178       | 18.62%  |
| IMC Networks                           | 91        | 9.52%   |
| Microdia                               | 88        | 9.21%   |
| Logitech                               | 80        | 8.37%   |
| Quanta                                 | 64        | 6.69%   |
| Realtek Semiconductor                  | 60        | 6.28%   |
| Bison Electronics                      | 58        | 6.07%   |
| Sunplus Innovation Technology          | 49        | 5.13%   |
| Cheng Uei Precision Industry (Foxlink) | 37        | 3.87%   |
| Acer                                   | 28        | 2.93%   |
| Luxvisions Innotech Limited            | 26        | 2.72%   |
| Apple                                  | 22        | 2.3%    |
| Syntek                                 | 18        | 1.88%   |
| Lite-On Technology                     | 14        | 1.46%   |
| Suyin                                  | 12        | 1.26%   |
| Samsung Electronics                    | 9         | 0.94%   |
| Microsoft                              | 9         | 0.94%   |
| Sonix Technology                       | 8         | 0.84%   |
| Silicon Motion                         | 8         | 0.84%   |
| Generalplus Technology                 | 7         | 0.73%   |
| Alcor Micro                            | 6         | 0.63%   |
| Z-Star Microelectronics                | 5         | 0.52%   |
| Y Media                                | 5         | 0.52%   |
| SunplusIT                              | 5         | 0.52%   |
| icSpring                               | 5         | 0.52%   |
| KYE Systems (Mouse Systems)            | 4         | 0.42%   |
| ShineTech                              | 3         | 0.31%   |
| MacroSilicon                           | 3         | 0.31%   |
| GEMBIRD                                | 3         | 0.31%   |
| Cubeternet                             | 3         | 0.31%   |
| ARC International                      | 3         | 0.31%   |
| YGTek                                  | 2         | 0.21%   |
| Unknown                                | 2         | 0.21%   |
| Trust                                  | 2         | 0.21%   |
| Ricoh                                  | 2         | 0.21%   |
| Razer USA                              | 2         | 0.21%   |
| Primax Electronics                     | 2         | 0.21%   |
| LG Electronics                         | 2         | 0.21%   |
| Lenovo                                 | 2         | 0.21%   |
| Jieli Technology                       | 2         | 0.21%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 47        | 4.89%   |
| Microdia Integrated_Webcam_HD                                   | 39        | 4.06%   |
| IMC Networks Integrated Camera                                  | 33        | 3.43%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 25        | 2.6%    |
| Bison Integrated Camera                                         | 22        | 2.29%   |
| Realtek Integrated_Webcam_HD                                    | 19        | 1.98%   |
| Chicony HD User Facing                                          | 19        | 1.98%   |
| Sunplus Integrated_Webcam_HD                                    | 16        | 1.66%   |
| Logitech HD Pro Webcam C920                                     | 16        | 1.66%   |
| Logitech Webcam C270                                            | 14        | 1.46%   |
| Quanta HP TrueVision HD Camera                                  | 13        | 1.35%   |
| Chicony HD Webcam                                               | 13        | 1.35%   |
| Acer Integrated Camera                                          | 13        | 1.35%   |
| Syntek Integrated Camera                                        | 12        | 1.25%   |
| Microdia Integrated_Webcam_FHD                                  | 12        | 1.25%   |
| Quanta HD User Facing                                           | 11        | 1.14%   |
| Bison HD Webcam                                                 | 11        | 1.14%   |
| Realtek USB Camera                                              | 10        | 1.04%   |
| Chicony HP HD Camera                                            | 10        | 1.04%   |
| Apple FaceTime HD Camera (Built-in)                             | 10        | 1.04%   |
| Samsung Galaxy series, misc. (MTP mode)                         | 9         | 0.94%   |
| Microdia Webcam Vitade AF                                       | 9         | 0.94%   |
| Bison BisonCam,NB Pro                                           | 9         | 0.94%   |
| Chicony USB2.0 Camera                                           | 8         | 0.83%   |
| Chicony Integrated Camera (1280x720@30)                         | 8         | 0.83%   |
| Quanta HP HD Camera                                             | 7         | 0.73%   |
| Quanta ACER HD User Facing                                      | 7         | 0.73%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 7         | 0.73%   |
| Logitech C922 Pro Stream Webcam                                 | 7         | 0.73%   |
| IMC Networks HD Camera                                          | 7         | 0.73%   |
| Quanta HP Wide Vision HD Camera                                 | 6         | 0.62%   |
| Luxvisions Innotech Limited Integrated Camera                   | 6         | 0.62%   |
| Logitech C920 PRO HD Webcam                                     | 6         | 0.62%   |
| Chicony HP Wide Vision HD Camera                                | 6         | 0.62%   |
| Chicony HP TrueVision HD                                        | 6         | 0.62%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 6         | 0.62%   |
| Y Media USB Camera                                              | 5         | 0.52%   |
| Sonix USB2.0 HD UVC WebCam                                      | 5         | 0.52%   |
| Microdia USB 2.0 Camera                                         | 5         | 0.52%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera            | 5         | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 55        | 31.07%  |
| Validity Sensors                   | 47        | 26.55%  |
| Shenzhen Goodix Technology         | 41        | 23.16%  |
| Elan Microelectronics              | 15        | 8.47%   |
| AuthenTec                          | 6         | 3.39%   |
| Upek                               | 5         | 2.82%   |
| LighTuning Technology              | 4         | 2.26%   |
| STMicroelectronics                 | 1         | 0.56%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.56%   |
| Focal-systems.Corp                 | 1         | 0.56%   |
| Dell                               | 1         | 0.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 32        | 18.08%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 14        | 7.91%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 10        | 5.65%   |
| Elan ELAN:ARM-M4                                                           | 9         | 5.08%   |
| Validity Sensors VFS491                                                    | 7         | 3.95%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 7         | 3.95%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 3.95%   |
| Shenzhen Goodix Fingerprint Reader                                         | 7         | 3.95%   |
| Validity Sensors Synaptics WBDI                                            | 6         | 3.39%   |
| Elan ELAN:Fingerprint                                                      | 6         | 3.39%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 5         | 2.82%   |
| Synaptics WBDI                                                             | 5         | 2.82%   |
| Synaptics UWP WBDI                                                         | 5         | 2.82%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 2.26%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 4         | 2.26%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 3         | 1.69%   |
| Synaptics UWP WBDI Device                                                  | 3         | 1.69%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 1.69%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 3         | 1.69%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 1.69%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 1.13%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 1.13%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 1.13%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 1.13%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 1.13%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 2         | 1.13%   |
| Synaptics  WBDI                                                            | 2         | 1.13%   |
| Synaptics Fingerprint reader [HP G6]                                       | 2         | 1.13%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 1.13%   |
| AuthenTec AES2810                                                          | 2         | 1.13%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.56%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.56%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.56%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 1         | 0.56%   |
| Synaptics TouchPad                                                         | 1         | 0.56%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.56%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 0.56%   |
| LighTuning Fingerprint Sensor                                              | 1         | 0.56%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.56%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 32        | 39.51%  |
| Broadcom                  | 31        | 38.27%  |
| Upek                      | 4         | 4.94%   |
| OmniKey                   | 2         | 2.47%   |
| O2 Micro                  | 2         | 2.47%   |
| Lenovo                    | 2         | 2.47%   |
| Gemalto (was Gemplus)     | 2         | 2.47%   |
| Bit4id                    | 2         | 2.47%   |
| SCM Microsystems          | 1         | 1.23%   |
| Clay Logic                | 1         | 1.23%   |
| Aladdin Knowledge Systems | 1         | 1.23%   |
| Advanced Card Systems     | 1         | 1.23%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 32        | 39.51%  |
| Broadcom 58200                                                               | 12        | 14.81%  |
| Broadcom 5880                                                                | 10        | 12.35%  |
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 6.17%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 4.94%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 4         | 4.94%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 2.47%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 2.47%   |
| Bit4id miniLector EVO                                                        | 2         | 2.47%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 1.23%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 1.23%   |
| OmniKey CardMan 1021                                                         | 1         | 1.23%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 1.23%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 1.23%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 1.23%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 1.23%   |
| Advanced Card Systems ACR39U                                                 | 1         | 1.23%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 997       | 68.76%  |
| 1     | 359       | 24.76%  |
| 2     | 81        | 5.59%   |
| 3     | 9         | 0.62%   |
| 4     | 2         | 0.14%   |
| 9     | 1         | 0.07%   |
| 7     | 1         | 0.07%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 172       | 32.09%  |
| Graphics card            | 79        | 14.74%  |
| Chipcard                 | 72        | 13.43%  |
| Net/wireless             | 63        | 11.75%  |
| Multimedia controller    | 33        | 6.16%   |
| Camera                   | 32        | 5.97%   |
| Unassigned class         | 19        | 3.54%   |
| Bluetooth                | 18        | 3.36%   |
| Sound                    | 13        | 2.43%   |
| Communication controller | 11        | 2.05%   |
| Storage                  | 6         | 1.12%   |
| Storage/ide              | 4         | 0.75%   |
| Network                  | 4         | 0.75%   |
| Net/ethernet             | 3         | 0.56%   |
| Card reader              | 3         | 0.56%   |
| Modem                    | 2         | 0.37%   |
| Storage/raid             | 1         | 0.19%   |
| Dvb card                 | 1         | 0.19%   |

