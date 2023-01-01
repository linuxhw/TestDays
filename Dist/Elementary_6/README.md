Elementary 6 - Tested Hardware & Statistics
-------------------------------------------

A project to collect tested hardware configurations for Elementary 6.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Elementary_6/Desktop/README.md) and [notebooks](/Dist/Elementary_6/Notebook/README.md).

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

Total: 284

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Sony          | VPCEB16FG                   | Notebook    | [6baf989163](https://linux-hardware.org/?probe=6baf989163) | Aug 06, 2022 |
| HP            | ProBook 430 G2              | Notebook    | [0be149d703](https://linux-hardware.org/?probe=0be149d703) | Jul 16, 2022 |
| Inventec      | D CLASS A02                 | Desktop     | [d00d37285b](https://linux-hardware.org/?probe=d00d37285b) | Apr 19, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [0bc837ffef](https://linux-hardware.org/?probe=0bc837ffef) | Apr 06, 2022 |
| LG Electro... | P1-JSUVT                    | Notebook    | [b0e2f9e53c](https://linux-hardware.org/?probe=b0e2f9e53c) | Mar 27, 2022 |
| ASUSTek       | PRIME B250-PRO              | Desktop     | [be377c733e](https://linux-hardware.org/?probe=be377c733e) | Feb 14, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [ac78806c22](https://linux-hardware.org/?probe=ac78806c22) | Jan 30, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [657fbc0f6d](https://linux-hardware.org/?probe=657fbc0f6d) | Jan 30, 2022 |
| ASUSTek       | GL502VS                     | Notebook    | [feb64c0933](https://linux-hardware.org/?probe=feb64c0933) | Jan 12, 2022 |
| Lenovo        | ThinkPad T460s 20F9CTO1W... | Notebook    | [7ba01d7327](https://linux-hardware.org/?probe=7ba01d7327) | Jan 07, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [172b005a76](https://linux-hardware.org/?probe=172b005a76) | Jan 07, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [a0a13869ab](https://linux-hardware.org/?probe=a0a13869ab) | Jan 05, 2022 |
| Acer          | Aspire XXXX                 | Notebook    | [d52d9dc2bd](https://linux-hardware.org/?probe=d52d9dc2bd) | Jan 04, 2022 |
| Acer          | Aspire XXXX                 | Notebook    | [b5d8962bbc](https://linux-hardware.org/?probe=b5d8962bbc) | Jan 04, 2022 |
| ASRock        | AB350M Pro4                 | Desktop     | [2886b84cc0](https://linux-hardware.org/?probe=2886b84cc0) | Jan 04, 2022 |
| ASRock        | Z590 Phantom Gaming 4/ac    | Desktop     | [b52ca671f7](https://linux-hardware.org/?probe=b52ca671f7) | Dec 24, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [5627f53d66](https://linux-hardware.org/?probe=5627f53d66) | Dec 17, 2021 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [7b3efc8cd8](https://linux-hardware.org/?probe=7b3efc8cd8) | Dec 14, 2021 |
| Pegatron      | IPMH61P1                    | Desktop     | [1ba6ea2ee9](https://linux-hardware.org/?probe=1ba6ea2ee9) | Dec 14, 2021 |
| Acer          | ConceptD CM100-51A V:1.1    | Desktop     | [0b3e5753fc](https://linux-hardware.org/?probe=0b3e5753fc) | Dec 13, 2021 |
| Dell          | Inspiron 1764               | Notebook    | [a8abf45979](https://linux-hardware.org/?probe=a8abf45979) | Dec 13, 2021 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [8280287583](https://linux-hardware.org/?probe=8280287583) | Dec 12, 2021 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [6f114c2528](https://linux-hardware.org/?probe=6f114c2528) | Dec 12, 2021 |
| Dell          | XPS 15 9510                 | Notebook    | [da1818e0c5](https://linux-hardware.org/?probe=da1818e0c5) | Dec 12, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [40b1d83a44](https://linux-hardware.org/?probe=40b1d83a44) | Dec 11, 2021 |
| Star Labs     | StarBook                    | Notebook    | [e9414e6bc4](https://linux-hardware.org/?probe=e9414e6bc4) | Dec 09, 2021 |
| Lenovo        | ThinkPad X201 Tablet 311... | Notebook    | [31e281d91b](https://linux-hardware.org/?probe=31e281d91b) | Dec 09, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [d6be9fac19](https://linux-hardware.org/?probe=d6be9fac19) | Dec 09, 2021 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [5c0550c1e8](https://linux-hardware.org/?probe=5c0550c1e8) | Dec 09, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [fc49eed81d](https://linux-hardware.org/?probe=fc49eed81d) | Dec 09, 2021 |
| Lenovo        | ThinkPad SL400 2743A37      | Notebook    | [d32c954439](https://linux-hardware.org/?probe=d32c954439) | Dec 09, 2021 |
| ASUSTek       | H81M-C                      | Desktop     | [0b0241baf7](https://linux-hardware.org/?probe=0b0241baf7) | Dec 08, 2021 |
| Dell          | 0MGK50 A02                  | Desktop     | [df4bb96e67](https://linux-hardware.org/?probe=df4bb96e67) | Dec 08, 2021 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [cd20a94e3e](https://linux-hardware.org/?probe=cd20a94e3e) | Dec 08, 2021 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [fa1e8b87a6](https://linux-hardware.org/?probe=fa1e8b87a6) | Dec 08, 2021 |
| Google        | Cyan                        | Notebook    | [f49c895086](https://linux-hardware.org/?probe=f49c895086) | Dec 08, 2021 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [5c46f5e832](https://linux-hardware.org/?probe=5c46f5e832) | Dec 07, 2021 |
| Dell          | Latitude E5420              | Notebook    | [e9fdf365b6](https://linux-hardware.org/?probe=e9fdf365b6) | Dec 07, 2021 |
| Gigabyte      | AX370-Gaming-CF se1         | Desktop     | [7cb1ebd6c9](https://linux-hardware.org/?probe=7cb1ebd6c9) | Dec 07, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [a8e4016566](https://linux-hardware.org/?probe=a8e4016566) | Dec 06, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [ebfed157e7](https://linux-hardware.org/?probe=ebfed157e7) | Dec 06, 2021 |
| Microsoft     | Surface Pro 3               | Tablet      | [73f375d3ac](https://linux-hardware.org/?probe=73f375d3ac) | Dec 06, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [ed493cd76f](https://linux-hardware.org/?probe=ed493cd76f) | Dec 05, 2021 |
| Acer          | Aspire X3990                | Desktop     | [e291d06394](https://linux-hardware.org/?probe=e291d06394) | Dec 05, 2021 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [970669192e](https://linux-hardware.org/?probe=970669192e) | Dec 05, 2021 |
| HP            | G62                         | Notebook    | [6e055d5b6b](https://linux-hardware.org/?probe=6e055d5b6b) | Dec 05, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [9143857ca7](https://linux-hardware.org/?probe=9143857ca7) | Dec 05, 2021 |
| ASUSTek       | FX503VD                     | Notebook    | [6b5bd7a6d3](https://linux-hardware.org/?probe=6b5bd7a6d3) | Dec 05, 2021 |
| MSI           | Z370 KRAIT GAMING           | Desktop     | [b213dc07b8](https://linux-hardware.org/?probe=b213dc07b8) | Dec 04, 2021 |
| HP            | ENVY x360 Convertible       | Convertible | [bc5923cefe](https://linux-hardware.org/?probe=bc5923cefe) | Dec 04, 2021 |
| HP            | ENVY x360 Convertible       | Convertible | [f8ed9dbcf4](https://linux-hardware.org/?probe=f8ed9dbcf4) | Dec 04, 2021 |
| MSI           | Z370 KRAIT GAMING           | Desktop     | [b562e90f75](https://linux-hardware.org/?probe=b562e90f75) | Dec 04, 2021 |
| Packard Be... | EasyNote LS11HR             | Notebook    | [d58c199fda](https://linux-hardware.org/?probe=d58c199fda) | Dec 04, 2021 |
| Intel         | NUC7i3BNB J22859-313        | Mini pc     | [c9fe8f5431](https://linux-hardware.org/?probe=c9fe8f5431) | Dec 03, 2021 |
| HP            | ZBook 15 G5                 | Notebook    | [b42c2359f4](https://linux-hardware.org/?probe=b42c2359f4) | Dec 03, 2021 |
| HP            | 2B07                        | All in one  | [b6cf0a1651](https://linux-hardware.org/?probe=b6cf0a1651) | Dec 03, 2021 |
| Lenovo        | ThinkPad T410s 292494G      | Notebook    | [f43363fde0](https://linux-hardware.org/?probe=f43363fde0) | Dec 03, 2021 |
| Pegatron      | Benicia                     | Desktop     | [51dae15bcd](https://linux-hardware.org/?probe=51dae15bcd) | Dec 03, 2021 |
| Gigabyte      | AX370-Gaming-CF se1         | Desktop     | [313d4d0bd8](https://linux-hardware.org/?probe=313d4d0bd8) | Dec 03, 2021 |
| HP            | EliteBook 820 G2            | Notebook    | [03bb5ecc6a](https://linux-hardware.org/?probe=03bb5ecc6a) | Dec 03, 2021 |
| HP            | 8653 A                      | Desktop     | [85d1730019](https://linux-hardware.org/?probe=85d1730019) | Dec 01, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [68fffd46cf](https://linux-hardware.org/?probe=68fffd46cf) | Dec 01, 2021 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [fbe4820444](https://linux-hardware.org/?probe=fbe4820444) | Dec 01, 2021 |
| ASUSTek       | ROG STRIX Z490-F GAMING     | Desktop     | [500f9c8851](https://linux-hardware.org/?probe=500f9c8851) | Dec 01, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [0131556200](https://linux-hardware.org/?probe=0131556200) | Dec 01, 2021 |
| Samsung       | 550XDA                      | Notebook    | [30c24b17f4](https://linux-hardware.org/?probe=30c24b17f4) | Dec 01, 2021 |
| HP            | EliteBook 2760p             | Notebook    | [d13f27ae75](https://linux-hardware.org/?probe=d13f27ae75) | Nov 30, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [5052f33272](https://linux-hardware.org/?probe=5052f33272) | Nov 30, 2021 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [c7cbb50843](https://linux-hardware.org/?probe=c7cbb50843) | Nov 30, 2021 |
| Google        | Kip                         | Notebook    | [958c198a17](https://linux-hardware.org/?probe=958c198a17) | Nov 29, 2021 |
| Lenovo        | ThinkPad SL400 2743A37      | Notebook    | [26cba9b931](https://linux-hardware.org/?probe=26cba9b931) | Nov 29, 2021 |
| Chuwi         | LarkBox Pro                 | Mini pc     | [4af62a6057](https://linux-hardware.org/?probe=4af62a6057) | Nov 29, 2021 |
| Biostar       | TH55XE                      | Desktop     | [9e420cc495](https://linux-hardware.org/?probe=9e420cc495) | Nov 28, 2021 |
| Toshiba       | Satellite L750              | Notebook    | [0a4f8ff5f1](https://linux-hardware.org/?probe=0a4f8ff5f1) | Nov 28, 2021 |
| HP            | Laptop 15s-fq0xxx           | Notebook    | [8b1d090289](https://linux-hardware.org/?probe=8b1d090289) | Nov 28, 2021 |
| MSI           | H81M-P33                    | Desktop     | [8812103632](https://linux-hardware.org/?probe=8812103632) | Nov 28, 2021 |
| HP            | 1497                        | Desktop     | [6f042fb99c](https://linux-hardware.org/?probe=6f042fb99c) | Nov 28, 2021 |
| HP            | Pavilion dm4                | Notebook    | [e2c582f687](https://linux-hardware.org/?probe=e2c582f687) | Nov 28, 2021 |
| HP            | ProBook 4540s               | Notebook    | [b6762448da](https://linux-hardware.org/?probe=b6762448da) | Nov 28, 2021 |
| Acer          | Aspire X3990                | Desktop     | [5559b2d988](https://linux-hardware.org/?probe=5559b2d988) | Nov 27, 2021 |
| Notebook      | L140CU                      | Notebook    | [59021b2a31](https://linux-hardware.org/?probe=59021b2a31) | Nov 27, 2021 |
| Toshiba       | Satellite L840              | Notebook    | [6c29b0fc8d](https://linux-hardware.org/?probe=6c29b0fc8d) | Nov 27, 2021 |
| Acer          | Iconia Tab W500             | Tablet      | [5984a91751](https://linux-hardware.org/?probe=5984a91751) | Nov 27, 2021 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [c8a72fc7e2](https://linux-hardware.org/?probe=c8a72fc7e2) | Nov 26, 2021 |
| HP            | 1825                        | Desktop     | [3648c360a9](https://linux-hardware.org/?probe=3648c360a9) | Nov 26, 2021 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [0004bab911](https://linux-hardware.org/?probe=0004bab911) | Nov 26, 2021 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [2ef4f4f273](https://linux-hardware.org/?probe=2ef4f4f273) | Nov 26, 2021 |
| Dell          | Inspiron 15-3573            | Notebook    | [04dc1956ff](https://linux-hardware.org/?probe=04dc1956ff) | Nov 26, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [ee1387e206](https://linux-hardware.org/?probe=ee1387e206) | Nov 26, 2021 |
| Lenovo        | ThinkPad SL400 2743A37      | Notebook    | [cd408c48d0](https://linux-hardware.org/?probe=cd408c48d0) | Nov 25, 2021 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [34e71f1e27](https://linux-hardware.org/?probe=34e71f1e27) | Nov 25, 2021 |
| Lenovo        | ThinkPad X140e 20BLS0040... | Notebook    | [94b3c73b50](https://linux-hardware.org/?probe=94b3c73b50) | Nov 25, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [0fccfea38c](https://linux-hardware.org/?probe=0fccfea38c) | Nov 25, 2021 |
| Apple         | MacBookPro11,2              | Notebook    | [07931c8e7b](https://linux-hardware.org/?probe=07931c8e7b) | Nov 24, 2021 |
| Dell          | System Inspiron N7110       | Notebook    | [fe6a145b19](https://linux-hardware.org/?probe=fe6a145b19) | Nov 24, 2021 |
| Medion        | E7218                       | Notebook    | [e4a790a38d](https://linux-hardware.org/?probe=e4a790a38d) | Nov 23, 2021 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [1bfd5fb612](https://linux-hardware.org/?probe=1bfd5fb612) | Nov 23, 2021 |
| HP            | Laptop 15s-du1xxx           | Notebook    | [d4cf81aaa5](https://linux-hardware.org/?probe=d4cf81aaa5) | Nov 23, 2021 |
| HP            | Laptop 15s-du1xxx           | Notebook    | [0368cfb8e2](https://linux-hardware.org/?probe=0368cfb8e2) | Nov 23, 2021 |
| Apple         | MacBookPro12,1              | Notebook    | [4f694a8ba3](https://linux-hardware.org/?probe=4f694a8ba3) | Nov 23, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [945f4c9b1d](https://linux-hardware.org/?probe=945f4c9b1d) | Nov 22, 2021 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [1e15277ce2](https://linux-hardware.org/?probe=1e15277ce2) | Nov 22, 2021 |
| Biostar       | TA790GXE 128M               | Desktop     | [93ff10a9c2](https://linux-hardware.org/?probe=93ff10a9c2) | Nov 21, 2021 |
| MSI           | GF72 7RE                    | Notebook    | [8e48a382b9](https://linux-hardware.org/?probe=8e48a382b9) | Nov 21, 2021 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [12bcc06e6e](https://linux-hardware.org/?probe=12bcc06e6e) | Nov 21, 2021 |
| Alienware     | 17                          | Notebook    | [d3460bdfd1](https://linux-hardware.org/?probe=d3460bdfd1) | Nov 20, 2021 |
| Intel         | NUC7i3BNB J22859-313        | Mini pc     | [e7e27b16de](https://linux-hardware.org/?probe=e7e27b16de) | Nov 20, 2021 |
| Dell          | Vostro 3300                 | Notebook    | [04fc886be3](https://linux-hardware.org/?probe=04fc886be3) | Nov 20, 2021 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [9e7d926319](https://linux-hardware.org/?probe=9e7d926319) | Nov 19, 2021 |
| HP            | ProBook 4730s               | Notebook    | [ffaa64e329](https://linux-hardware.org/?probe=ffaa64e329) | Nov 19, 2021 |
| HP            | 0AECh D                     | Desktop     | [c81bcc92ca](https://linux-hardware.org/?probe=c81bcc92ca) | Nov 19, 2021 |
| Schenker      | X170KM-G                    | Notebook    | [79bb8af2a1](https://linux-hardware.org/?probe=79bb8af2a1) | Nov 19, 2021 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [e49d63158f](https://linux-hardware.org/?probe=e49d63158f) | Nov 19, 2021 |
| HP            | ENVY x360 Convertible       | Convertible | [d998144d2e](https://linux-hardware.org/?probe=d998144d2e) | Nov 18, 2021 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [38d8d7827f](https://linux-hardware.org/?probe=38d8d7827f) | Nov 18, 2021 |
| Dell          | Inspiron 7506 2n1           | Convertible | [078e3be7c3](https://linux-hardware.org/?probe=078e3be7c3) | Nov 17, 2021 |
| HP            | Compaq 6710b (GB893EA#AB... | Notebook    | [47a6a7a44f](https://linux-hardware.org/?probe=47a6a7a44f) | Nov 17, 2021 |
| Unknown       | Unknown                     | Notebook    | [7027abd4e6](https://linux-hardware.org/?probe=7027abd4e6) | Nov 17, 2021 |
| Acer          | Aspire 5733Z                | Notebook    | [324f0d898e](https://linux-hardware.org/?probe=324f0d898e) | Nov 16, 2021 |
| Acer          | Aspire ES1-571              | Notebook    | [60fef7922d](https://linux-hardware.org/?probe=60fef7922d) | Nov 16, 2021 |
| Dell          | 0F2A20 A00                  | All in one  | [e98616633d](https://linux-hardware.org/?probe=e98616633d) | Nov 16, 2021 |
| Gigabyte      | EP43T-USB3                  | Desktop     | [a24bb09910](https://linux-hardware.org/?probe=a24bb09910) | Nov 15, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [74e99a032e](https://linux-hardware.org/?probe=74e99a032e) | Nov 15, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [58edd5c8e6](https://linux-hardware.org/?probe=58edd5c8e6) | Nov 14, 2021 |
| Gigabyte      | H81M-H                      | Desktop     | [a895ed29e0](https://linux-hardware.org/?probe=a895ed29e0) | Nov 14, 2021 |
| ASRock        | X570 Extreme4               | Desktop     | [e49fdf2db4](https://linux-hardware.org/?probe=e49fdf2db4) | Nov 13, 2021 |
| Lenovo        | ThinkPad T460s 20F90042M... | Notebook    | [76ba8c7144](https://linux-hardware.org/?probe=76ba8c7144) | Nov 13, 2021 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [197f5e1565](https://linux-hardware.org/?probe=197f5e1565) | Nov 12, 2021 |
| Sony          | SVE15115EN                  | Notebook    | [03cbf5ac5a](https://linux-hardware.org/?probe=03cbf5ac5a) | Nov 11, 2021 |
| MSI           | 970A-G43                    | Desktop     | [19714dd1a0](https://linux-hardware.org/?probe=19714dd1a0) | Nov 08, 2021 |
| Gigabyte      | Z270X-Gaming 5              | Desktop     | [5244244701](https://linux-hardware.org/?probe=5244244701) | Nov 08, 2021 |
| Dell          | 05R2TK A01                  | All in one  | [0b728f2263](https://linux-hardware.org/?probe=0b728f2263) | Nov 07, 2021 |
| ASUSTek       | ROG Strix G512LI_G512LI     | Notebook    | [e43a236a2c](https://linux-hardware.org/?probe=e43a236a2c) | Nov 06, 2021 |
| Quanta        | TW9/SW9                     | Notebook    | [86643edf2a](https://linux-hardware.org/?probe=86643edf2a) | Nov 06, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [66109af766](https://linux-hardware.org/?probe=66109af766) | Nov 05, 2021 |
| ASUSTek       | E502SA                      | Notebook    | [28d4f5e427](https://linux-hardware.org/?probe=28d4f5e427) | Nov 04, 2021 |
| HCL Infosy... | HCL ME LAPTOP               | Notebook    | [0db069b4f1](https://linux-hardware.org/?probe=0db069b4f1) | Nov 01, 2021 |
| Fujitsu       | LIFEBOOK U747               | Notebook    | [2b68c16c68](https://linux-hardware.org/?probe=2b68c16c68) | Nov 01, 2021 |
| Dell          | Latitude E6410              | Notebook    | [ba51fc9216](https://linux-hardware.org/?probe=ba51fc9216) | Oct 30, 2021 |
| ASRock        | P67 Extreme4                | Desktop     | [a70eb2d3f8](https://linux-hardware.org/?probe=a70eb2d3f8) | Oct 29, 2021 |
| ASRock        | P67 Extreme4                | Desktop     | [0a07f4c735](https://linux-hardware.org/?probe=0a07f4c735) | Oct 29, 2021 |
| MSI           | 2A9Ch                       | Desktop     | [2f752a1a3e](https://linux-hardware.org/?probe=2f752a1a3e) | Oct 28, 2021 |
| Lenovo        | ThinkPad X230 23259L3       | Notebook    | [801c1d8af3](https://linux-hardware.org/?probe=801c1d8af3) | Oct 27, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [6461bfc243](https://linux-hardware.org/?probe=6461bfc243) | Oct 26, 2021 |
| MSI           | Modern 14 B4MW              | Notebook    | [a904daf48d](https://linux-hardware.org/?probe=a904daf48d) | Oct 26, 2021 |
| HP            | 84EE 1100                   | All in one  | [225f3ee57b](https://linux-hardware.org/?probe=225f3ee57b) | Oct 26, 2021 |
| HP            | ProBook 6460b               | Notebook    | [18f27d1f5c](https://linux-hardware.org/?probe=18f27d1f5c) | Oct 25, 2021 |
| Lenovo        | ThinkPad T470 20HD004AUS    | Notebook    | [80fb4514c5](https://linux-hardware.org/?probe=80fb4514c5) | Oct 23, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [5c95c74b6c](https://linux-hardware.org/?probe=5c95c74b6c) | Oct 21, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [f48a449c7a](https://linux-hardware.org/?probe=f48a449c7a) | Oct 21, 2021 |
| HP            | 158B                        | Desktop     | [24399f4e69](https://linux-hardware.org/?probe=24399f4e69) | Oct 20, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [4ce4f8ba78](https://linux-hardware.org/?probe=4ce4f8ba78) | Oct 20, 2021 |
| Google        | Setzer                      | Notebook    | [e9536ccbfb](https://linux-hardware.org/?probe=e9536ccbfb) | Oct 19, 2021 |
| Google        | Setzer                      | Notebook    | [3ba49636ef](https://linux-hardware.org/?probe=3ba49636ef) | Oct 19, 2021 |
| HP            | 339A                        | Desktop     | [d9c6208191](https://linux-hardware.org/?probe=d9c6208191) | Oct 16, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [370b129f3f](https://linux-hardware.org/?probe=370b129f3f) | Oct 16, 2021 |
| Lenovo        | ThinkPad E470 20H10052IG    | Notebook    | [1342d4ce00](https://linux-hardware.org/?probe=1342d4ce00) | Oct 15, 2021 |
| HP            | Pavilion dv6500             | Notebook    | [dd3c7ef3e7](https://linux-hardware.org/?probe=dd3c7ef3e7) | Oct 14, 2021 |
| HP            | Pavilion dv6500             | Notebook    | [c1c77cf91a](https://linux-hardware.org/?probe=c1c77cf91a) | Oct 14, 2021 |
| HP            | 2B42                        | All in one  | [42d66aed80](https://linux-hardware.org/?probe=42d66aed80) | Oct 14, 2021 |
| Dell          | 0M9KCM A02                  | Desktop     | [a925b0f3d1](https://linux-hardware.org/?probe=a925b0f3d1) | Oct 12, 2021 |
| Acer          | Aspire ES1-311              | Notebook    | [8f1dd3ce3a](https://linux-hardware.org/?probe=8f1dd3ce3a) | Oct 12, 2021 |
| Acer          | Aspire ES1-311              | Notebook    | [df266accf1](https://linux-hardware.org/?probe=df266accf1) | Oct 12, 2021 |
| Apple         | MacBookAir6,1               | Notebook    | [66f91918dc](https://linux-hardware.org/?probe=66f91918dc) | Oct 12, 2021 |
| Apple         | MacBookAir6,1               | Notebook    | [87403edfc9](https://linux-hardware.org/?probe=87403edfc9) | Oct 11, 2021 |
| HP            | 2B42                        | All in one  | [c1224ad1ab](https://linux-hardware.org/?probe=c1224ad1ab) | Oct 11, 2021 |
| ASUSTek       | 1215B                       | Notebook    | [7b3bf2ca14](https://linux-hardware.org/?probe=7b3bf2ca14) | Oct 11, 2021 |
| HP            | EliteBook 8440p             | Notebook    | [e5071e6c43](https://linux-hardware.org/?probe=e5071e6c43) | Oct 10, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [f6e75d0258](https://linux-hardware.org/?probe=f6e75d0258) | Oct 09, 2021 |
| HP            | ProBook 4530s               | Notebook    | [0a725a0b81](https://linux-hardware.org/?probe=0a725a0b81) | Oct 07, 2021 |
| Apple         | MacBookPro7,1               | Notebook    | [644b3b5b60](https://linux-hardware.org/?probe=644b3b5b60) | Oct 04, 2021 |
| MSI           | B460M PRO-VDH WIFI          | Desktop     | [05711b548f](https://linux-hardware.org/?probe=05711b548f) | Oct 03, 2021 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [de0f051658](https://linux-hardware.org/?probe=de0f051658) | Oct 02, 2021 |
| Shuttle       | FS61                        | Desktop     | [b25047a516](https://linux-hardware.org/?probe=b25047a516) | Oct 01, 2021 |
| Panasonic     | FZ-G1ASH39E3                | Tablet      | [06f11c0449](https://linux-hardware.org/?probe=06f11c0449) | Sep 30, 2021 |
| Panasonic     | FZ-G1ASH39E3                | Tablet      | [961d53afb6](https://linux-hardware.org/?probe=961d53afb6) | Sep 30, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | Notebook    | [32c58fa2f6](https://linux-hardware.org/?probe=32c58fa2f6) | Sep 30, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [c1dc59d33f](https://linux-hardware.org/?probe=c1dc59d33f) | Sep 29, 2021 |
| Apple         | Mac-F221BEC8                | Desktop     | [1754c64091](https://linux-hardware.org/?probe=1754c64091) | Sep 27, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [c28700cfda](https://linux-hardware.org/?probe=c28700cfda) | Sep 26, 2021 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [fbcf277174](https://linux-hardware.org/?probe=fbcf277174) | Sep 26, 2021 |
| Lenovo        | G50-45 80E3                 | Notebook    | [59224ec754](https://linux-hardware.org/?probe=59224ec754) | Sep 26, 2021 |
| ASUSTek       | P7H55-M                     | Desktop     | [3367bc011a](https://linux-hardware.org/?probe=3367bc011a) | Sep 25, 2021 |
| Dell          | 0Y5DDC A00                  | Desktop     | [df95ea94b8](https://linux-hardware.org/?probe=df95ea94b8) | Sep 25, 2021 |
| Dell          | 0Y5DDC A00                  | Desktop     | [10ee1abc07](https://linux-hardware.org/?probe=10ee1abc07) | Sep 25, 2021 |
| Apple         | MacBookPro10,2              | Notebook    | [25c8a26c00](https://linux-hardware.org/?probe=25c8a26c00) | Sep 24, 2021 |
| ASRock        | M3A790GXH/128M              | Desktop     | [818ec10ec8](https://linux-hardware.org/?probe=818ec10ec8) | Sep 24, 2021 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [c1b8f22fa6](https://linux-hardware.org/?probe=c1b8f22fa6) | Sep 22, 2021 |
| Intel         | X79 V1.x                    | Desktop     | [19223e911c](https://linux-hardware.org/?probe=19223e911c) | Sep 22, 2021 |
| Dell          | Precision M4800             | Notebook    | [736b482dc3](https://linux-hardware.org/?probe=736b482dc3) | Sep 22, 2021 |
| eMachines     | G525                        | Notebook    | [8e8d037369](https://linux-hardware.org/?probe=8e8d037369) | Sep 21, 2021 |
| ASUSTek       | M4N78-AM                    | Desktop     | [3d8e0efc00](https://linux-hardware.org/?probe=3d8e0efc00) | Sep 21, 2021 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [9d25d0c5c7](https://linux-hardware.org/?probe=9d25d0c5c7) | Sep 21, 2021 |
| Lenovo        | ThinkPad W700 2758MVG       | Notebook    | [66c8ecbaa1](https://linux-hardware.org/?probe=66c8ecbaa1) | Sep 20, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [b01438543e](https://linux-hardware.org/?probe=b01438543e) | Sep 20, 2021 |
| Apple         | MacBookPro10,2              | Notebook    | [0e44f5011a](https://linux-hardware.org/?probe=0e44f5011a) | Sep 20, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3448B... | Notebook    | [2bec640695](https://linux-hardware.org/?probe=2bec640695) | Sep 20, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [d2511347b4](https://linux-hardware.org/?probe=d2511347b4) | Sep 19, 2021 |
| HP            | ENVY 15                     | Notebook    | [ba9a8e1d7a](https://linux-hardware.org/?probe=ba9a8e1d7a) | Sep 19, 2021 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [9d10bffde2](https://linux-hardware.org/?probe=9d10bffde2) | Sep 18, 2021 |
| Lenovo        | ThinkPad X250 20CLS32H00    | Notebook    | [15981e12f3](https://linux-hardware.org/?probe=15981e12f3) | Sep 18, 2021 |
| Lenovo        | ThinkPad X250 20CLS32H00    | Notebook    | [bcdb4d552d](https://linux-hardware.org/?probe=bcdb4d552d) | Sep 18, 2021 |
| HP            | ENVY 15                     | Notebook    | [d2d607895f](https://linux-hardware.org/?probe=d2d607895f) | Sep 18, 2021 |
| ASRock        | A320M-HDV                   | Desktop     | [24bb7c7d18](https://linux-hardware.org/?probe=24bb7c7d18) | Sep 17, 2021 |
| Alienware     | 17                          | Notebook    | [c97b201719](https://linux-hardware.org/?probe=c97b201719) | Sep 17, 2021 |
| Acer          | Aspire V3-572G              | Notebook    | [addf12cb05](https://linux-hardware.org/?probe=addf12cb05) | Sep 16, 2021 |
| TUXEDO        | InfinityBook S 14 Gen6      | Notebook    | [0c206818b9](https://linux-hardware.org/?probe=0c206818b9) | Sep 15, 2021 |
| Acer          | Aspire VX5-591G             | Notebook    | [c7d5407b29](https://linux-hardware.org/?probe=c7d5407b29) | Sep 15, 2021 |
| Dell          | Latitude E7440              | Notebook    | [fc9f25eecb](https://linux-hardware.org/?probe=fc9f25eecb) | Sep 14, 2021 |
| Toshiba       | Satellite P100              | Notebook    | [bc5b605920](https://linux-hardware.org/?probe=bc5b605920) | Sep 13, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [591ba7a77c](https://linux-hardware.org/?probe=591ba7a77c) | Sep 12, 2021 |
| Dell          | Inspiron 3583               | Notebook    | [49b4db94c6](https://linux-hardware.org/?probe=49b4db94c6) | Sep 12, 2021 |
| Lenovo        | 371C No DPK                 | All in one  | [cd0d01d653](https://linux-hardware.org/?probe=cd0d01d653) | Sep 11, 2021 |
| ASUSTek       | UX303LA                     | Notebook    | [1a67d956de](https://linux-hardware.org/?probe=1a67d956de) | Sep 11, 2021 |
| Intel         | H61                         | Desktop     | [0010dbcb5e](https://linux-hardware.org/?probe=0010dbcb5e) | Sep 10, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [f373a049e2](https://linux-hardware.org/?probe=f373a049e2) | Sep 10, 2021 |
| HP            | 8767 A                      | Desktop     | [7f022c67ac](https://linux-hardware.org/?probe=7f022c67ac) | Sep 09, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [6e97abfd44](https://linux-hardware.org/?probe=6e97abfd44) | Sep 09, 2021 |
| Lenovo        | ThinkPad X201 3249CTO       | Notebook    | [7b3432fcf6](https://linux-hardware.org/?probe=7b3432fcf6) | Sep 08, 2021 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [0614925ee7](https://linux-hardware.org/?probe=0614925ee7) | Sep 08, 2021 |
| Gateway       | NV54 Series                 | Notebook    | [fcf57528ed](https://linux-hardware.org/?probe=fcf57528ed) | Sep 08, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [dfb9789af2](https://linux-hardware.org/?probe=dfb9789af2) | Sep 07, 2021 |
| Sony          | Serie VJC14                 | Notebook    | [27828e1dfb](https://linux-hardware.org/?probe=27828e1dfb) | Sep 07, 2021 |
| Sony          | Serie VJC14                 | Notebook    | [4c1200e7cf](https://linux-hardware.org/?probe=4c1200e7cf) | Sep 07, 2021 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [797db05baf](https://linux-hardware.org/?probe=797db05baf) | Sep 06, 2021 |
| Microsoft     | Surface Laptop Go           | Tablet      | [ebd997cb1a](https://linux-hardware.org/?probe=ebd997cb1a) | Sep 05, 2021 |
| Microsoft     | Surface Laptop Go           | Tablet      | [a5d7b5a10e](https://linux-hardware.org/?probe=a5d7b5a10e) | Sep 05, 2021 |
| HP            | Laptop 15-bs1xx             | Notebook    | [91ecd39f66](https://linux-hardware.org/?probe=91ecd39f66) | Sep 05, 2021 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [633441bc2b](https://linux-hardware.org/?probe=633441bc2b) | Sep 05, 2021 |
| Medion        | Akoya THE TOUCH 10          | Notebook    | [d49d62a2f5](https://linux-hardware.org/?probe=d49d62a2f5) | Sep 04, 2021 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [c9476d5d06](https://linux-hardware.org/?probe=c9476d5d06) | Sep 02, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [da332ba09e](https://linux-hardware.org/?probe=da332ba09e) | Sep 01, 2021 |
| HP            | 86ED A01                    | All in one  | [78778f22a2](https://linux-hardware.org/?probe=78778f22a2) | Sep 01, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [adbb6a690a](https://linux-hardware.org/?probe=adbb6a690a) | Sep 01, 2021 |
| Dell          | Latitude 3580               | Notebook    | [2befbbba9e](https://linux-hardware.org/?probe=2befbbba9e) | Aug 31, 2021 |
| HP            | Pavilion g6                 | Notebook    | [7dba3c201c](https://linux-hardware.org/?probe=7dba3c201c) | Aug 31, 2021 |
| Gigabyte      | F2A55M-HD2                  | Desktop     | [0c05ab5b21](https://linux-hardware.org/?probe=0c05ab5b21) | Aug 30, 2021 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [48c720456a](https://linux-hardware.org/?probe=48c720456a) | Aug 30, 2021 |
| ASRock        | H81TM-ITX R2.0              | Desktop     | [4f04e7309e](https://linux-hardware.org/?probe=4f04e7309e) | Aug 30, 2021 |
| HP            | ProBook 4320s               | Notebook    | [94f189cea1](https://linux-hardware.org/?probe=94f189cea1) | Aug 29, 2021 |
| eMachines     | G525                        | Notebook    | [d64e29475f](https://linux-hardware.org/?probe=d64e29475f) | Aug 29, 2021 |
| Microsoft     | Surface Pro 4               | Tablet      | [aeec497ed8](https://linux-hardware.org/?probe=aeec497ed8) | Aug 28, 2021 |
| Lenovo        | ThinkPad X201 3249CTO       | Notebook    | [0a9bdb4827](https://linux-hardware.org/?probe=0a9bdb4827) | Aug 27, 2021 |
| Acer          | Aspire A515-51G             | Notebook    | [df0d3e8ac4](https://linux-hardware.org/?probe=df0d3e8ac4) | Aug 26, 2021 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [d0ff1c6977](https://linux-hardware.org/?probe=d0ff1c6977) | Aug 25, 2021 |
| HP            | 86ED A01                    | All in one  | [402a8e492c](https://linux-hardware.org/?probe=402a8e492c) | Aug 24, 2021 |
| ASUSTek       | P6X58D-E                    | Desktop     | [db1ef28e92](https://linux-hardware.org/?probe=db1ef28e92) | Aug 20, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [fae546f5cb](https://linux-hardware.org/?probe=fae546f5cb) | Aug 20, 2021 |
| Apple         | MacBookPro9,1               | Notebook    | [e9bec90506](https://linux-hardware.org/?probe=e9bec90506) | Aug 19, 2021 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [1176a287c7](https://linux-hardware.org/?probe=1176a287c7) | Aug 19, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [9d7628068c](https://linux-hardware.org/?probe=9d7628068c) | Aug 19, 2021 |
| Dell          | System XPS L321X            | Notebook    | [34d7fb6cbb](https://linux-hardware.org/?probe=34d7fb6cbb) | Aug 18, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [f30480d463](https://linux-hardware.org/?probe=f30480d463) | Aug 17, 2021 |
| HP            | Notebook                    | Notebook    | [a3058005e3](https://linux-hardware.org/?probe=a3058005e3) | Aug 16, 2021 |
| HP            | Notebook                    | Notebook    | [7800ef9623](https://linux-hardware.org/?probe=7800ef9623) | Aug 16, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [fa6c69671f](https://linux-hardware.org/?probe=fa6c69671f) | Aug 16, 2021 |
| ASUSTek       | TUF Gaming B450M-PRO II     | Desktop     | [73beb900ea](https://linux-hardware.org/?probe=73beb900ea) | Aug 15, 2021 |
| Acidanther... | Mac-7BA5B2D9E42DDD94 iMa... | All in one  | [a8d4959fde](https://linux-hardware.org/?probe=a8d4959fde) | Aug 14, 2021 |
| Apple         | MacBookPro9,1               | Notebook    | [a6b2c12401](https://linux-hardware.org/?probe=a6b2c12401) | Aug 14, 2021 |
| Dell          | Precision 5760              | Notebook    | [824e5e7dad](https://linux-hardware.org/?probe=824e5e7dad) | Aug 14, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [e302074e5e](https://linux-hardware.org/?probe=e302074e5e) | Aug 14, 2021 |
| Acer          | Aspire A514-54              | Notebook    | [dcfc87a32f](https://linux-hardware.org/?probe=dcfc87a32f) | Aug 14, 2021 |
| Acer          | Aspire A514-54              | Notebook    | [e354646c04](https://linux-hardware.org/?probe=e354646c04) | Aug 13, 2021 |
| Gigabyte      | H310M M.2 x.x               | Desktop     | [69e2e83b95](https://linux-hardware.org/?probe=69e2e83b95) | Aug 10, 2021 |
| Gigabyte      | H310M M.2 x.x               | Desktop     | [86d69a15b9](https://linux-hardware.org/?probe=86d69a15b9) | Aug 10, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [4e6f050b43](https://linux-hardware.org/?probe=4e6f050b43) | Aug 10, 2021 |
| Toshiba       | Satellite L500              | Notebook    | [76a8d2c20a](https://linux-hardware.org/?probe=76a8d2c20a) | Jul 29, 2021 |
| Google        | Cave                        | Notebook    | [e2617f0c2d](https://linux-hardware.org/?probe=e2617f0c2d) | Jul 25, 2021 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [a97fc63d3d](https://linux-hardware.org/?probe=a97fc63d3d) | Jul 23, 2021 |
| Toshiba       | Satellite L500              | Notebook    | [7124417642](https://linux-hardware.org/?probe=7124417642) | Jul 22, 2021 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [0447155931](https://linux-hardware.org/?probe=0447155931) | Jul 02, 2021 |
| Acer          | Swift SF314-55G             | Notebook    | [c371b46cbe](https://linux-hardware.org/?probe=c371b46cbe) | Jun 30, 2021 |
| Acer          | Swift SF315-41              | Notebook    | [8df5e13fc0](https://linux-hardware.org/?probe=8df5e13fc0) | Jun 18, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [c5d0611f79](https://linux-hardware.org/?probe=c5d0611f79) | Jun 13, 2021 |
| Acer          | Swift SF314-55G             | Notebook    | [4e5cf8aa1e](https://linux-hardware.org/?probe=4e5cf8aa1e) | Jun 13, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [63da02a979](https://linux-hardware.org/?probe=63da02a979) | May 19, 2021 |
| Acer          | ConceptD CN315-71P          | Notebook    | [5ecea84320](https://linux-hardware.org/?probe=5ecea84320) | May 15, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [223234378e](https://linux-hardware.org/?probe=223234378e) | May 04, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [e177523d81](https://linux-hardware.org/?probe=e177523d81) | May 03, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [a208e8a358](https://linux-hardware.org/?probe=a208e8a358) | May 01, 2021 |
| Apple         | MacBookPro8,2               | Notebook    | [e87a073ae8](https://linux-hardware.org/?probe=e87a073ae8) | Mar 18, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [1e31858e51](https://linux-hardware.org/?probe=1e31858e51) | Mar 09, 2021 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [f7d949f5a7](https://linux-hardware.org/?probe=f7d949f5a7) | Dec 23, 2020 |
| HP            | 8433 11                     | Desktop     | [691ef58a05](https://linux-hardware.org/?probe=691ef58a05) | Dec 09, 2020 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.11.0-40-generic      | 54        | 22.22%  |
| 5.11.0-41-generic      | 42        | 17.28%  |
| 5.11.0-27-generic      | 40        | 16.46%  |
| 5.11.0-38-generic      | 27        | 11.11%  |
| 5.11.0-37-generic      | 24        | 9.88%   |
| 5.11.0-25-generic      | 18        | 7.41%   |
| 5.11.0-34-generic      | 14        | 5.76%   |
| 5.8.0-50-generic       | 5         | 2.06%   |
| 5.11.0-36-generic      | 4         | 1.65%   |
| 5.8.0-55-generic       | 3         | 1.23%   |
| 5.8.0-63-generic       | 2         | 0.82%   |
| 5.8.0-53-generic       | 1         | 0.41%   |
| 5.8.0-44-generic       | 1         | 0.41%   |
| 5.4.0-91-generic       | 1         | 0.41%   |
| 5.4.0-58-generic       | 1         | 0.41%   |
| 5.4.0-56-generic       | 1         | 0.41%   |
| 5.15.1-xanmod1         | 1         | 0.41%   |
| 5.14.7-xanmod1-cacule  | 1         | 0.41%   |
| 5.14.14-051414-generic | 1         | 0.41%   |
| 5.11.0-41-lowlatency   | 1         | 0.41%   |
| 5.11.0-051100-generic  | 1         | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11.0  | 215       | 92.27%  |
| 5.8.0   | 12        | 5.15%   |
| 5.4.0   | 3         | 1.29%   |
| 5.15.1  | 1         | 0.43%   |
| 5.14.7  | 1         | 0.43%   |
| 5.14.14 | 1         | 0.43%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11    | 215       | 92.27%  |
| 5.8     | 12        | 5.15%   |
| 5.4     | 3         | 1.29%   |
| 5.14    | 2         | 0.86%   |
| 5.15    | 1         | 0.43%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 233       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Pantheon   | 213       | 91.03%  |
| Unknown    | 15        | 6.41%   |
| GNOME      | 3         | 1.28%   |
| X-Cinnamon | 2         | 0.85%   |
| MATE       | 1         | 0.43%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 233       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 182       | 78.11%  |
| LightDM | 41        | 17.6%   |
| TDM     | 7         | 3%      |
| GDM     | 3         | 1.29%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 118       | 50.64%  |
| de_DE | 24        | 10.3%   |
| es_ES | 19        | 8.15%   |
| ru_RU | 8         | 3.43%   |
| pt_BR | 8         | 3.43%   |
| fr_FR | 8         | 3.43%   |
| en_GB | 6         | 2.58%   |
| en_CA | 5         | 2.15%   |
| pl_PL | 4         | 1.72%   |
| it_IT | 4         | 1.72%   |
| zh_CN | 3         | 1.29%   |
| tr_TR | 3         | 1.29%   |
| en_AU | 3         | 1.29%   |
| cs_CZ | 3         | 1.29%   |
| nl_NL | 2         | 0.86%   |
| de_CH | 2         | 0.86%   |
| ca_ES | 2         | 0.86%   |
| vi_VN | 1         | 0.43%   |
| ro_RO | 1         | 0.43%   |
| lt_LT | 1         | 0.43%   |
| id_ID | 1         | 0.43%   |
| hu_HU | 1         | 0.43%   |
| hr_HR | 1         | 0.43%   |
| gl_ES | 1         | 0.43%   |
| fr_BE | 1         | 0.43%   |
| fi_FI | 1         | 0.43%   |
| es_MX | 1         | 0.43%   |
| da_DK | 1         | 0.43%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 145       | 61.97%  |
| BIOS | 89        | 38.03%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 224       | 96.14%  |
| Overlay | 5         | 2.15%   |
| Btrfs   | 4         | 1.72%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 193       | 82.83%  |
| GPT     | 29        | 12.45%  |
| MBR     | 11        | 4.72%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 222       | 95.28%  |
| Yes       | 11        | 4.72%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 205       | 87.98%  |
| Yes       | 28        | 12.02%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 49        | 21.03%  |
| Lenovo                  | 27        | 11.59%  |
| Dell                    | 25        | 10.73%  |
| ASUSTek Computer        | 25        | 10.73%  |
| Apple                   | 16        | 6.87%   |
| Acer                    | 16        | 6.87%   |
| Gigabyte Technology     | 15        | 6.44%   |
| MSI                     | 8         | 3.43%   |
| ASRock                  | 8         | 3.43%   |
| Toshiba                 | 4         | 1.72%   |
| Sony                    | 3         | 1.29%   |
| Intel                   | 3         | 1.29%   |
| HUAWEI                  | 3         | 1.29%   |
| Google                  | 3         | 1.29%   |
| TUXEDO                  | 2         | 0.86%   |
| Pegatron                | 2         | 0.86%   |
| Microsoft               | 2         | 0.86%   |
| Medion                  | 2         | 0.86%   |
| Biostar                 | 2         | 0.86%   |
| Star Labs               | 1         | 0.43%   |
| Shuttle                 | 1         | 0.43%   |
| Schenker                | 1         | 0.43%   |
| Samsung Electronics     | 1         | 0.43%   |
| Quanta                  | 1         | 0.43%   |
| Panasonic               | 1         | 0.43%   |
| Packard Bell            | 1         | 0.43%   |
| Notebook                | 1         | 0.43%   |
| LG Electronics          | 1         | 0.43%   |
| Inventec                | 1         | 0.43%   |
| HCL Infosystems Limited | 1         | 0.43%   |
| Gateway                 | 1         | 0.43%   |
| Fujitsu                 | 1         | 0.43%   |
| eMachines               | 1         | 0.43%   |
| Chuwi                   | 1         | 0.43%   |
| Alienware               | 1         | 0.43%   |
| Acidanthera             | 1         | 0.43%   |
| Unknown                 | 1         | 0.43%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                          | Computers | Percent |
|-------------------------------|-----------|---------|
| Lenovo Yoga 300-11IBR 80M1    | 2         | 0.86%   |
| HP Pavilion Notebook          | 2         | 0.86%   |
| Dell XPS 13 9350              | 2         | 0.86%   |
| Dell Inspiron N5110           | 2         | 0.86%   |
| Apple MacBookPro9,1           | 2         | 0.86%   |
| Apple MacBookPro10,2          | 2         | 0.86%   |
| Apple MacBookAir7,2           | 2         | 0.86%   |
| TUXEDO Pulse 15 Gen1          | 1         | 0.43%   |
| TUXEDO InfinityBook S 14 Gen6 | 1         | 0.43%   |
| Toshiba Satellite P100        | 1         | 0.43%   |
| Toshiba Satellite L840        | 1         | 0.43%   |
| Toshiba Satellite L750        | 1         | 0.43%   |
| Toshiba Satellite L500        | 1         | 0.43%   |
| Star Labs StarBook            | 1         | 0.43%   |
| Sony VPCEB16FG                | 1         | 0.43%   |
| Sony SVE15115EN               | 1         | 0.43%   |
| Sony Serie VJC14              | 1         | 0.43%   |
| Shuttle DS61                  | 1         | 0.43%   |
| Schenker X170KM-G             | 1         | 0.43%   |
| Samsung 550XDA                | 1         | 0.43%   |
| Quanta TW9/SW9                | 1         | 0.43%   |
| Pegatron KJ379AA-ABA a6400f   | 1         | 0.43%   |
| Pegatron IPMH61P1             | 1         | 0.43%   |
| Panasonic FZ-G1ASH39E3        | 1         | 0.43%   |
| Packard Bell EasyNote LS11HR  | 1         | 0.43%   |
| Notebook L140CU               | 1         | 0.43%   |
| MSI MS-7C83                   | 1         | 0.43%   |
| MSI MS-7B79                   | 1         | 0.43%   |
| MSI MS-7B46                   | 1         | 0.43%   |
| MSI MS-7817                   | 1         | 0.43%   |
| MSI MS-7693                   | 1         | 0.43%   |
| MSI Modern 14 B4MW            | 1         | 0.43%   |
| MSI GF72 7RE                  | 1         | 0.43%   |
| MSI Elite 7100 Microtower PC  | 1         | 0.43%   |
| Microsoft Surface Pro 4       | 1         | 0.43%   |
| Microsoft Surface Pro 3       | 1         | 0.43%   |
| Medion E7218                  | 1         | 0.43%   |
| Medion Akoya THE TOUCH 10     | 1         | 0.43%   |
| LG P1-JSUVT                   | 1         | 0.43%   |
| Lenovo V330-15IKB 81AX        | 1         | 0.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 16        | 6.87%   |
| HP Pavilion          | 13        | 5.58%   |
| Acer Aspire          | 11        | 4.72%   |
| HP ProBook           | 7         | 3%      |
| Dell Inspiron        | 7         | 3%      |
| Lenovo IdeaPad       | 6         | 2.58%   |
| HP Laptop            | 6         | 2.58%   |
| HP EliteBook         | 6         | 2.58%   |
| Dell XPS             | 6         | 2.58%   |
| HP ENVY              | 5         | 2.15%   |
| Toshiba Satellite    | 4         | 1.72%   |
| Dell Latitude        | 4         | 1.72%   |
| Dell OptiPlex        | 3         | 1.29%   |
| ASUS TUF             | 3         | 1.29%   |
| ASUS ROG             | 3         | 1.29%   |
| ASUS PRIME           | 3         | 1.29%   |
| Microsoft Surface    | 2         | 0.86%   |
| Lenovo Yoga          | 2         | 0.86%   |
| HP Compaq            | 2         | 0.86%   |
| Gigabyte X570        | 2         | 0.86%   |
| Gigabyte B450M       | 2         | 0.86%   |
| Dell System          | 2         | 0.86%   |
| Dell Precision       | 2         | 0.86%   |
| Apple MacBookPro9    | 2         | 0.86%   |
| Apple MacBookPro8    | 2         | 0.86%   |
| Apple MacBookPro10   | 2         | 0.86%   |
| Apple MacBookAir7    | 2         | 0.86%   |
| Acer Swift           | 2         | 0.86%   |
| Acer ConceptD        | 2         | 0.86%   |
| TUXEDO Pulse         | 1         | 0.43%   |
| TUXEDO InfinityBook  | 1         | 0.43%   |
| Star Labs StarBook   | 1         | 0.43%   |
| Sony VPCEB16FG       | 1         | 0.43%   |
| Sony SVE15115EN      | 1         | 0.43%   |
| Sony Serie           | 1         | 0.43%   |
| Shuttle DS61         | 1         | 0.43%   |
| Schenker X170KM-G    | 1         | 0.43%   |
| Samsung 550XDA       | 1         | 0.43%   |
| Quanta TW9           | 1         | 0.43%   |
| Pegatron KJ379AA-ABA | 1         | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 27        | 11.59%  |
| 2018    | 22        | 9.44%   |
| 2015    | 22        | 9.44%   |
| 2011    | 22        | 9.44%   |
| 2010    | 21        | 9.01%   |
| 2017    | 19        | 8.15%   |
| 2019    | 18        | 7.73%   |
| 2021    | 17        | 7.3%    |
| 2012    | 17        | 7.3%    |
| 2016    | 13        | 5.58%   |
| 2014    | 11        | 4.72%   |
| 2013    | 9         | 3.86%   |
| 2009    | 7         | 3%      |
| 2008    | 4         | 1.72%   |
| 2007    | 2         | 0.86%   |
| 2006    | 1         | 0.43%   |
| Unknown | 1         | 0.43%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 143       | 61.37%  |
| Desktop     | 67        | 28.76%  |
| All in one  | 11        | 4.72%   |
| Convertible | 6         | 2.58%   |
| Tablet      | 4         | 1.72%   |
| Mini pc     | 2         | 0.86%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 195       | 83.69%  |
| Enabled  | 38        | 16.31%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 229       | 98.28%  |
| Yes  | 4         | 1.72%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 67        | 28.76%  |
| 16.01-24.0  | 46        | 19.74%  |
| 3.01-4.0    | 43        | 18.45%  |
| 8.01-16.0   | 37        | 15.88%  |
| 32.01-64.0  | 24        | 10.3%   |
| 1.01-2.0    | 10        | 4.29%   |
| 24.01-32.0  | 3         | 1.29%   |
| 64.01-256.0 | 2         | 0.86%   |
| 2.01-3.0    | 1         | 0.43%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 102       | 41.98%  |
| 2.01-3.0   | 68        | 27.98%  |
| 3.01-4.0   | 34        | 13.99%  |
| 4.01-8.0   | 33        | 13.58%  |
| 0.51-1.0   | 3         | 1.23%   |
| 8.01-16.0  | 2         | 0.82%   |
| 32.01-64.0 | 1         | 0.41%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 150       | 63.83%  |
| 2      | 60        | 25.53%  |
| 3      | 12        | 5.11%   |
| 4      | 9         | 3.83%   |
| 5      | 3         | 1.28%   |
| 6      | 1         | 0.43%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 159       | 68.24%  |
| Yes       | 74        | 31.76%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 192       | 82.4%   |
| No        | 41        | 17.6%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 198       | 84.98%  |
| No        | 35        | 15.02%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 172       | 73.5%   |
| No        | 62        | 26.5%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 31        | 13.25%  |
| Germany      | 23        | 9.83%   |
| India        | 15        | 6.41%   |
| Canada       | 12        | 5.13%   |
| UK           | 11        | 4.7%    |
| Russia       | 10        | 4.27%   |
| Brazil       | 10        | 4.27%   |
| France       | 8         | 3.42%   |
| Mexico       | 7         | 2.99%   |
| Argentina    | 7         | 2.99%   |
| Netherlands  | 6         | 2.56%   |
| Indonesia    | 6         | 2.56%   |
| Spain        | 5         | 2.14%   |
| Turkey       | 4         | 1.71%   |
| Poland       | 4         | 1.71%   |
| Italy        | 4         | 1.71%   |
| Finland      | 4         | 1.71%   |
| Denmark      | 4         | 1.71%   |
| Czechia      | 4         | 1.71%   |
| Australia    | 4         | 1.71%   |
| Vietnam      | 3         | 1.28%   |
| Sweden       | 3         | 1.28%   |
| Belgium      | 3         | 1.28%   |
| Austria      | 3         | 1.28%   |
| Switzerland  | 2         | 0.85%   |
| Romania      | 2         | 0.85%   |
| Paraguay     | 2         | 0.85%   |
| Kenya        | 2         | 0.85%   |
| Guatemala    | 2         | 0.85%   |
| Estonia      | 2         | 0.85%   |
| China        | 2         | 0.85%   |
| Chile        | 2         | 0.85%   |
| Uruguay      | 1         | 0.43%   |
| Ukraine      | 1         | 0.43%   |
| Thailand     | 1         | 0.43%   |
| Sri Lanka    | 1         | 0.43%   |
| South Africa | 1         | 0.43%   |
| Slovenia     | 1         | 0.43%   |
| Serbia       | 1         | 0.43%   |
| Philippines  | 1         | 0.43%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Vienna           | 3         | 1.26%   |
| Vernon           | 3         | 1.26%   |
| Paris            | 3         | 1.26%   |
| Moscow           | 3         | 1.26%   |
| Mexico City      | 3         | 1.26%   |
| Warsaw           | 2         | 0.84%   |
| Valladolid       | 2         | 0.84%   |
| Tallinn          | 2         | 0.84%   |
| Sassnitz         | 2         | 0.84%   |
| Sao Paulo        | 2         | 0.84%   |
| Santiago         | 2         | 0.84%   |
| San Jose         | 2         | 0.84%   |
| Perth            | 2         | 0.84%   |
| Nairobi          | 2         | 0.84%   |
| Mumbai           | 2         | 0.84%   |
| Montreal         | 2         | 0.84%   |
| Milan            | 2         | 0.84%   |
| Kolkata          | 2         | 0.84%   |
| Istanbul         | 2         | 0.84%   |
| Ho Chi Minh City | 2         | 0.84%   |
| Guatemala City   | 2         | 0.84%   |
| Copenhagen       | 2         | 0.84%   |
| Coimbatore       | 2         | 0.84%   |
| Calgary          | 2         | 0.84%   |
| Buenos Aires     | 2         | 0.84%   |
| Berlin           | 2         | 0.84%   |
| Zurich           | 1         | 0.42%   |
| Zonguldak        | 1         | 0.42%   |
| Xicheng District | 1         | 0.42%   |
| Woodbridge       | 1         | 0.42%   |
| Wigan            | 1         | 0.42%   |
| Walsrode         | 1         | 0.42%   |
| Wakefield        | 1         | 0.42%   |
| Vitória         | 1         | 0.42%   |
| Vilnius          | 1         | 0.42%   |
| Villeurbanne     | 1         | 0.42%   |
| Villahermosa     | 1         | 0.42%   |
| Victoria         | 1         | 0.42%   |
| Vertaizon        | 1         | 0.42%   |
| Vancouver        | 1         | 0.42%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 55        | 67     | 17.24%  |
| Samsung Electronics       | 52        | 67     | 16.3%   |
| Seagate                   | 37        | 45     | 11.6%   |
| SanDisk                   | 23        | 26     | 7.21%   |
| Toshiba                   | 19        | 19     | 5.96%   |
| Kingston                  | 15        | 20     | 4.7%    |
| Crucial                   | 14        | 17     | 4.39%   |
| Unknown                   | 13        | 14     | 4.08%   |
| Hitachi                   | 8         | 8      | 2.51%   |
| HGST                      | 8         | 8      | 2.51%   |
| Apple                     | 8         | 8      | 2.51%   |
| Micron Technology         | 7         | 7      | 2.19%   |
| Intel                     | 6         | 6      | 1.88%   |
| SK hynix                  | 5         | 6      | 1.57%   |
| Phison                    | 3         | 4      | 0.94%   |
| Patriot                   | 3         | 3      | 0.94%   |
| OCZ                       | 3         | 3      | 0.94%   |
| LITEON                    | 3         | 3      | 0.94%   |
| KIOXIA                    | 3         | 3      | 0.94%   |
| Gigabyte Technology       | 3         | 3      | 0.94%   |
| A-DATA Technology         | 3         | 4      | 0.94%   |
| Transcend                 | 2         | 3      | 0.63%   |
| Silicon Motion            | 2         | 2      | 0.63%   |
| Micron/Crucial Technology | 2         | 3      | 0.63%   |
| LITEONIT                  | 2         | 2      | 0.63%   |
| China                     | 2         | 2      | 0.63%   |
| USB3.1                    | 1         | 1      | 0.31%   |
| Union Memory              | 1         | 1      | 0.31%   |
| Team                      | 1         | 1      | 0.31%   |
| StoreJet                  | 1         | 1      | 0.31%   |
| Star Drive                | 1         | 1      | 0.31%   |
| OCZ-VERTEX2               | 1         | 1      | 0.31%   |
| Netac                     | 1         | 1      | 0.31%   |
| Mercury                   | 1         | 1      | 0.31%   |
| LS                        | 1         | 1      | 0.31%   |
| Kingmax                   | 1         | 1      | 0.31%   |
| Intenso                   | 1         | 1      | 0.31%   |
| HUAWEI                    | 1         | 1      | 0.31%   |
| Hewlett-Packard           | 1         | 1      | 0.31%   |
| GALAX                     | 1         | 1      | 0.31%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD        | 7         | 2.04%   |
| Samsung NVMe SSD Drive 512GB           | 6         | 1.75%   |
| Samsung NVMe SSD Drive 500GB           | 6         | 1.75%   |
| SanDisk NVMe SSD Drive 512GB           | 5         | 1.46%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 5         | 1.46%   |
| Unknown MMC Card  128GB                | 4         | 1.17%   |
| Samsung NVMe SSD Drive 1TB             | 4         | 1.17%   |
| Intel NVMe SSD Drive 512GB             | 4         | 1.17%   |
| Crucial CT240BX500SSD1 240GB           | 4         | 1.17%   |
| WDC WD5000LPVX-22V0TT0 500GB           | 3         | 0.87%   |
| WDC WD10JPVX-22JC3T0 1TB               | 3         | 0.87%   |
| Toshiba MQ01ABD100V -63 1TB            | 3         | 0.87%   |
| Seagate ST1000LM035-1RK172 1TB         | 3         | 0.87%   |
| SanDisk NVMe SSD Drive 500GB           | 3         | 0.87%   |
| Samsung SSD 860 EVO 250GB              | 3         | 0.87%   |
| Kingston SA400S37480G 480GB SSD        | 3         | 0.87%   |
| HGST HTS721010A9E630 1TB               | 3         | 0.87%   |
| WDC WDS500G2B0A-00SM50 500GB SSD       | 2         | 0.58%   |
| WDC WD5000AAKX-003CA0 500GB            | 2         | 0.58%   |
| WDC WD10SPZX-21Z10T0 1TB               | 2         | 0.58%   |
| WDC WD10EZEX-60WN4A0 1TB               | 2         | 0.58%   |
| WDC WD10EZEX-08WN4A0 1TB               | 2         | 0.58%   |
| Unknown MMC Card  32GB                 | 2         | 0.58%   |
| Unknown MMC Card  16GB                 | 2         | 0.58%   |
| Toshiba NVMe SSD Drive 256GB           | 2         | 0.58%   |
| Toshiba MQ01ABD100 1TB                 | 2         | 0.58%   |
| Toshiba MK6475GSX 640GB                | 2         | 0.58%   |
| SK hynix NVMe SSD Drive 512GB          | 2         | 0.58%   |
| Seagate ST500LT012-1DG142 500GB        | 2         | 0.58%   |
| Seagate ST250DM000-1BD141 250GB        | 2         | 0.58%   |
| Seagate ST2000LX001-1RG174 2TB         | 2         | 0.58%   |
| SanDisk NVMe SSD Drive 256GB           | 2         | 0.58%   |
| Samsung SSD 850 EVO 250GB              | 2         | 0.58%   |
| Samsung SSD 840 EVO 120GB              | 2         | 0.58%   |
| KIOXIA NVMe SSD Drive 512GB            | 2         | 0.58%   |
| HGST HTS541010A9E680 1TB               | 2         | 0.58%   |
| Crucial CT525MX300SSD1 528GB           | 2         | 0.58%   |
| Crucial CT250MX500SSD1 250GB           | 2         | 0.58%   |
| Crucial CT240BX200SSD1 240GB           | 2         | 0.58%   |
| Apple SSD SD128E 121GB                 | 2         | 0.58%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 47        | 56     | 37.9%   |
| Seagate             | 36        | 43     | 29.03%  |
| Toshiba             | 15        | 15     | 12.1%   |
| Hitachi             | 8         | 8      | 6.45%   |
| HGST                | 8         | 8      | 6.45%   |
| Samsung Electronics | 6         | 6      | 4.84%   |
| Apple               | 2         | 2      | 1.61%   |
| Unknown             | 1         | 1      | 0.81%   |
| Fujitsu             | 1         | 1      | 0.81%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 21        | 27     | 19.09%  |
| Crucial             | 14        | 17     | 12.73%  |
| SanDisk             | 12        | 13     | 10.91%  |
| Kingston            | 12        | 16     | 10.91%  |
| WDC                 | 6         | 6      | 5.45%   |
| Apple               | 6         | 6      | 5.45%   |
| Patriot             | 3         | 3      | 2.73%   |
| OCZ                 | 3         | 3      | 2.73%   |
| Micron Technology   | 3         | 3      | 2.73%   |
| LITEON              | 3         | 3      | 2.73%   |
| A-DATA Technology   | 3         | 4      | 2.73%   |
| Transcend           | 2         | 3      | 1.82%   |
| SK hynix            | 2         | 2      | 1.82%   |
| LITEONIT            | 2         | 2      | 1.82%   |
| Intel               | 2         | 2      | 1.82%   |
| China               | 2         | 2      | 1.82%   |
| Toshiba             | 1         | 1      | 0.91%   |
| Team                | 1         | 1      | 0.91%   |
| StoreJet            | 1         | 1      | 0.91%   |
| OCZ-VERTEX2         | 1         | 1      | 0.91%   |
| Netac               | 1         | 1      | 0.91%   |
| Mercury             | 1         | 1      | 0.91%   |
| LS                  | 1         | 1      | 0.91%   |
| Kingmax             | 1         | 1      | 0.91%   |
| Intenso             | 1         | 1      | 0.91%   |
| Hewlett-Packard     | 1         | 1      | 0.91%   |
| Gigabyte Technology | 1         | 1      | 0.91%   |
| GALAX               | 1         | 1      | 0.91%   |
| Dogfish             | 1         | 1      | 0.91%   |
| Apacer              | 1         | 1      | 0.91%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 114       | 140    | 38.26%  |
| SSD     | 97        | 126    | 32.55%  |
| NVMe    | 70        | 87     | 23.49%  |
| MMC     | 11        | 12     | 3.69%   |
| Unknown | 6         | 6      | 2.01%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 182       | 263    | 67.41%  |
| NVMe | 70        | 87     | 25.93%  |
| MMC  | 11        | 12     | 4.07%   |
| SAS  | 7         | 9      | 2.59%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 135       | 176    | 63.08%  |
| 0.51-1.0   | 63        | 71     | 29.44%  |
| 1.01-2.0   | 11        | 13     | 5.14%   |
| 2.01-3.0   | 3         | 4      | 1.4%    |
| 3.01-4.0   | 2         | 2      | 0.93%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 86        | 36.6%   |
| 251-500        | 66        | 28.09%  |
| 501-1000       | 30        | 12.77%  |
| 51-100         | 15        | 6.38%   |
| 21-50          | 12        | 5.11%   |
| 1001-2000      | 10        | 4.26%   |
| 2001-3000      | 6         | 2.55%   |
| 1-20           | 6         | 2.55%   |
| More than 3000 | 4         | 1.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 122       | 51.91%  |
| 21-50     | 49        | 20.85%  |
| 51-100    | 28        | 11.91%  |
| 101-250   | 16        | 6.81%   |
| 251-500   | 7         | 2.98%   |
| 501-1000  | 7         | 2.98%   |
| 1001-2000 | 4         | 1.7%    |
| 2001-3000 | 2         | 0.85%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD5000BPKT-75PK4T0 500GB        | 1         | 1      | 7.14%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 1         | 1      | 7.14%   |
| WDC WD3200AAJS-56B4A0 320GB         | 1         | 1      | 7.14%   |
| WDC WD10EZEX-00KUWA0 1TB            | 1         | 1      | 7.14%   |
| WDC WD1003FZEX-00MK2A0 1TB          | 1         | 1      | 7.14%   |
| Toshiba MK3259GSXP 320GB            | 1         | 1      | 7.14%   |
| Seagate ST320LT020-9YG142 320GB     | 1         | 1      | 7.14%   |
| Seagate ST3160813AS 160GB           | 1         | 1      | 7.14%   |
| Seagate ST1000LX015-1U7172-SSHD 1TB | 1         | 1      | 7.14%   |
| SanDisk SD7SB3Q256G1002 256GB SSD   | 1         | 1      | 7.14%   |
| Samsung Electronics HD160JJ/ 160GB  | 1         | 1      | 7.14%   |
| Hitachi HTS542525K9SA00 250GB       | 1         | 1      | 7.14%   |
| Crucial CT256M550SSD1 256GB         | 1         | 1      | 7.14%   |
| Apple HDD HTS541010A9E662 1TB       | 1         | 1      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 35.71%  |
| Seagate             | 3         | 3      | 21.43%  |
| Toshiba             | 1         | 1      | 7.14%   |
| SanDisk             | 1         | 1      | 7.14%   |
| Samsung Electronics | 1         | 1      | 7.14%   |
| Hitachi             | 1         | 1      | 7.14%   |
| Crucial             | 1         | 1      | 7.14%   |
| Apple               | 1         | 1      | 7.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 41.67%  |
| Seagate             | 3         | 3      | 25%     |
| Toshiba             | 1         | 1      | 8.33%   |
| Samsung Electronics | 1         | 1      | 8.33%   |
| Hitachi             | 1         | 1      | 8.33%   |
| Apple               | 1         | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 12     | 83.33%  |
| SSD  | 2         | 2      | 16.67%  |

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
| Detected | 196       | 313    | 81.33%  |
| Works    | 34        | 44     | 14.11%  |
| Malfunc  | 11        | 14     | 4.56%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 168       | 56.76%  |
| AMD                          | 39        | 13.18%  |
| Samsung Electronics          | 33        | 11.15%  |
| SanDisk                      | 18        | 6.08%   |
| Phison Electronics           | 5         | 1.69%   |
| Micron Technology            | 4         | 1.35%   |
| Toshiba America Info Systems | 3         | 1.01%   |
| SK hynix                     | 3         | 1.01%   |
| Marvell Technology Group     | 3         | 1.01%   |
| KIOXIA                       | 3         | 1.01%   |
| Kingston Technology Company  | 3         | 1.01%   |
| Silicon Motion               | 2         | 0.68%   |
| Nvidia                       | 2         | 0.68%   |
| Micron/Crucial Technology    | 2         | 0.68%   |
| JMicron Technology           | 2         | 0.68%   |
| ASMedia Technology           | 2         | 0.68%   |
| VIA Technologies             | 1         | 0.34%   |
| Seagate Technology           | 1         | 0.34%   |
| LSI Logic / Symbios Logic    | 1         | 0.34%   |
| Broadcom / LSI               | 1         | 0.34%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 27        | 8.13%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 17        | 5.12%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 14        | 4.22%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 13        | 3.92%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 13        | 3.92%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 11        | 3.31%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 10        | 3.01%   |
| Samsung NVMe SSD Controller 980                                                         | 8         | 2.41%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 8         | 2.41%   |
| Intel SATA Controller [RAID mode]                                                       | 7         | 2.11%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 7         | 2.11%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 6         | 1.81%   |
| AMD 400 Series Chipset SATA Controller                                                  | 6         | 1.81%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 5         | 1.51%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 5         | 1.51%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 4         | 1.2%    |
| Micron Non-Volatile memory controller                                                   | 4         | 1.2%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 4         | 1.2%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 4         | 1.2%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 4         | 1.2%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 4         | 1.2%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4         | 1.2%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 4         | 1.2%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 4         | 1.2%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 4         | 1.2%    |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                          | 3         | 0.9%    |
| SanDisk Non-Volatile memory controller                                                  | 3         | 0.9%    |
| Samsung Electronics SATA controller                                                     | 3         | 0.9%    |
| KIOXIA NVMe SSD Controller BG4                                                          | 3         | 0.9%    |
| Intel SSD 660P Series                                                                   | 3         | 0.9%    |
| Intel Comet Lake SATA AHCI Controller                                                   | 3         | 0.9%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3         | 0.9%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 3         | 0.9%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 3         | 0.9%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 3         | 0.9%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 3         | 0.9%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 3         | 0.9%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 3         | 0.9%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3         | 0.9%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3         | 0.9%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 170       | 58.22%  |
| NVMe | 70        | 23.97%  |
| RAID | 26        | 8.9%    |
| IDE  | 24        | 8.22%   |
| SAS  | 1         | 0.34%   |
| SCSI | 1         | 0.34%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 186       | 79.83%  |
| AMD    | 47        | 20.17%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz           | 6         | 2.58%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 5         | 2.15%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 4         | 1.72%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 4         | 1.72%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 4         | 1.72%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 4         | 1.72%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 3         | 1.29%   |
| Intel Core i3 CPU M 350 @ 2.27GHz           | 3         | 1.29%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 3         | 1.29%   |
| AMD Ryzen 5 3600 6-Core Processor           | 3         | 1.29%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 2         | 0.86%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 2         | 0.86%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 2         | 0.86%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz          | 2         | 0.86%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 2         | 0.86%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 2         | 0.86%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 0.86%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 2         | 0.86%   |
| Intel Core i5-5250U CPU @ 1.60GHz           | 2         | 0.86%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 2         | 0.86%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 2         | 0.86%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 2         | 0.86%   |
| Intel Core i5 CPU M 560 @ 2.67GHz           | 2         | 0.86%   |
| Intel Core i3-5010U CPU @ 2.10GHz           | 2         | 0.86%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2         | 0.86%   |
| Intel Core i3 CPU 530 @ 2.93GHz             | 2         | 0.86%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 2         | 0.86%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 2         | 0.86%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz     | 2         | 0.86%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 2         | 0.86%   |
| AMD Ryzen 5 4500U with Radeon Graphics      | 2         | 0.86%   |
| Intel Xeon W-11855M CPU @ 3.20GHz           | 1         | 0.43%   |
| Intel Xeon CPU X5660 @ 2.80GHz              | 1         | 0.43%   |
| Intel Xeon CPU E5520 @ 2.27GHz              | 1         | 0.43%   |
| Intel Xeon CPU E5-2689 0 @ 2.60GHz          | 1         | 0.43%   |
| Intel Xeon CPU E5-2640 0 @ 2.50GHz          | 1         | 0.43%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1         | 0.43%   |
| Intel Pentium CPU P6200 @ 2.13GHz           | 1         | 0.43%   |
| Intel Pentium CPU N4200 @ 1.10GHz           | 1         | 0.43%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 1         | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 59        | 25.32%  |
| Intel Core i7           | 42        | 18.03%  |
| Intel Core i3           | 24        | 10.3%   |
| Other                   | 15        | 6.44%   |
| Intel Celeron           | 14        | 6.01%   |
| AMD Ryzen 7             | 12        | 5.15%   |
| AMD Ryzen 5             | 12        | 5.15%   |
| Intel Pentium           | 11        | 4.72%   |
| Intel Core 2 Duo        | 7         | 3%      |
| Intel Xeon              | 5         | 2.15%   |
| AMD FX                  | 3         | 1.29%   |
| Intel Pentium Silver    | 2         | 0.86%   |
| Intel Pentium Dual-Core | 2         | 0.86%   |
| Intel Core 2            | 2         | 0.86%   |
| AMD Ryzen 9             | 2         | 0.86%   |
| AMD A8                  | 2         | 0.86%   |
| AMD A6                  | 2         | 0.86%   |
| AMD A4                  | 2         | 0.86%   |
| Intel Pentium Dual      | 1         | 0.43%   |
| Intel Core 2 Quad       | 1         | 0.43%   |
| Intel Celeron M         | 1         | 0.43%   |
| AMD Ryzen 7 PRO         | 1         | 0.43%   |
| AMD Ryzen 5 PRO         | 1         | 0.43%   |
| AMD Ryzen 3             | 1         | 0.43%   |
| AMD Phenom II X4        | 1         | 0.43%   |
| AMD Phenom II           | 1         | 0.43%   |
| AMD Phenom              | 1         | 0.43%   |
| AMD G                   | 1         | 0.43%   |
| AMD E1                  | 1         | 0.43%   |
| AMD C-60                | 1         | 0.43%   |
| AMD C-50                | 1         | 0.43%   |
| AMD Athlon II X4        | 1         | 0.43%   |
| AMD A10                 | 1         | 0.43%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 108       | 46.35%  |
| 4      | 74        | 31.76%  |
| 6      | 25        | 10.73%  |
| 8      | 18        | 7.73%   |
| 12     | 4         | 1.72%   |
| 1      | 3         | 1.29%   |
| 3      | 1         | 0.43%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 230       | 98.71%  |
| 2      | 3         | 1.29%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 160       | 68.67%  |
| 1      | 73        | 31.33%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 233       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x206a7    | 23        | 9.75%   |
| Unknown    | 18        | 7.63%   |
| 0x306c3    | 12        | 5.08%   |
| 0x306a9    | 12        | 5.08%   |
| 0x806c1    | 11        | 4.66%   |
| 0x406e3    | 10        | 4.24%   |
| 0x306d4    | 7         | 2.97%   |
| 0x20655    | 7         | 2.97%   |
| 0x20652    | 7         | 2.97%   |
| 0x906e9    | 6         | 2.54%   |
| 0x806ea    | 6         | 2.54%   |
| 0x40651    | 6         | 2.54%   |
| 0x1067a    | 6         | 2.54%   |
| 0x08701021 | 6         | 2.54%   |
| 0x806e9    | 5         | 2.12%   |
| 0x906ea    | 4         | 1.69%   |
| 0x30678    | 4         | 1.69%   |
| 0x0800820d | 4         | 1.69%   |
| 0xa0671    | 3         | 1.27%   |
| 0x806ec    | 3         | 1.27%   |
| 0x706a8    | 3         | 1.27%   |
| 0x6fb      | 3         | 1.27%   |
| 0x406c4    | 3         | 1.27%   |
| 0x08600104 | 3         | 1.27%   |
| 0xa0655    | 2         | 0.85%   |
| 0xa0653    | 2         | 0.85%   |
| 0xa0652    | 2         | 0.85%   |
| 0x806eb    | 2         | 0.85%   |
| 0x706a1    | 2         | 0.85%   |
| 0x6fd      | 2         | 0.85%   |
| 0x506e3    | 2         | 0.85%   |
| 0x406c3    | 2         | 0.85%   |
| 0x40661    | 2         | 0.85%   |
| 0x206d7    | 2         | 0.85%   |
| 0x106a5    | 2         | 0.85%   |
| 0x08701013 | 2         | 0.85%   |
| 0x08101007 | 2         | 0.85%   |
| 0x07030105 | 2         | 0.85%   |
| 0x0600611a | 2         | 0.85%   |
| 0x06000852 | 2         | 0.85%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 32        | 13.73%  |
| SandyBridge   | 28        | 12.02%  |
| Haswell       | 20        | 8.58%   |
| Westmere      | 15        | 6.44%   |
| Zen 2         | 14        | 6.01%   |
| Skylake       | 14        | 6.01%   |
| IvyBridge     | 13        | 5.58%   |
| TigerLake     | 11        | 4.72%   |
| Silvermont    | 10        | 4.29%   |
| Broadwell     | 8         | 3.43%   |
| Penryn        | 7         | 3%      |
| Core          | 7         | 3%      |
| Zen+          | 6         | 2.58%   |
| CometLake     | 6         | 2.58%   |
| Zen           | 5         | 2.15%   |
| IceLake       | 5         | 2.15%   |
| Goldmont plus | 5         | 2.15%   |
| K10           | 4         | 1.72%   |
| Zen 3         | 3         | 1.29%   |
| Piledriver    | 3         | 1.29%   |
| Nehalem       | 3         | 1.29%   |
| Excavator     | 3         | 1.29%   |
| Bobcat        | 3         | 1.29%   |
| Puma          | 2         | 0.86%   |
| Jaguar        | 2         | 0.86%   |
| Unknown       | 2         | 0.86%   |
| Goldmont      | 1         | 0.43%   |
| Bulldozer     | 1         | 0.43%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Intel            | 149       | 54.78%  |
| AMD              | 61        | 22.43%  |
| Nvidia           | 60        | 22.06%  |
| Conexant Systems | 1         | 0.37%   |
| ATI Technologies | 1         | 0.37%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 21        | 7.58%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 12        | 4.33%   |
| Intel Core Processor Integrated Graphics Controller                                      | 12        | 4.33%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 10        | 3.61%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 9         | 3.25%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 8         | 2.89%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 6         | 2.17%   |
| Intel UHD Graphics 620                                                                   | 6         | 2.17%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 2.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 2.17%   |
| AMD Renoir                                                                               | 6         | 2.17%   |
| Intel HD Graphics 630                                                                    | 5         | 1.81%   |
| Intel HD Graphics 620                                                                    | 5         | 1.81%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1.44%   |
| Intel HD Graphics 5500                                                                   | 4         | 1.44%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 1.44%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 4         | 1.44%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 4         | 1.44%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 1.08%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.08%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.08%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.72%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 2         | 0.72%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 0.72%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.72%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 2         | 0.72%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 2         | 0.72%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 2         | 0.72%   |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                                              | 2         | 0.72%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 2         | 0.72%   |
| Nvidia GA102 [GeForce RTX 3080]                                                          | 2         | 0.72%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 0.72%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 0.72%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 2         | 0.72%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.72%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 0.72%   |
| Intel HD Graphics 6000                                                                   | 2         | 0.72%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 0.72%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 0.72%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 0.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| 1 x Intel                      | 114       | 48.93%  |
| 1 x AMD                        | 49        | 21.03%  |
| 1 x Nvidia                     | 30        | 12.88%  |
| Intel + Nvidia                 | 28        | 12.02%  |
| Intel + AMD                    | 6         | 2.58%   |
| 2 x AMD                        | 3         | 1.29%   |
| AMD + Nvidia                   | 2         | 0.86%   |
| 2 x AMD + 1 x Conexant Systems | 1         | 0.43%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 205       | 86.86%  |
| Proprietary | 27        | 11.44%  |
| Unknown     | 4         | 1.69%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 135       | 57.45%  |
| 1.01-2.0   | 25        | 10.64%  |
| 0.01-0.5   | 21        | 8.94%   |
| 0.51-1.0   | 19        | 8.09%   |
| 3.01-4.0   | 15        | 6.38%   |
| 7.01-8.0   | 13        | 5.53%   |
| 5.01-6.0   | 3         | 1.28%   |
| 2.01-3.0   | 2         | 0.85%   |
| 8.01-16.0  | 2         | 0.85%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 30        | 11.9%   |
| Samsung Electronics     | 28        | 11.11%  |
| LG Display              | 24        | 9.52%   |
| Chimei Innolux          | 24        | 9.52%   |
| BOE                     | 20        | 7.94%   |
| Hewlett-Packard         | 15        | 5.95%   |
| Apple                   | 15        | 5.95%   |
| Goldstar                | 10        | 3.97%   |
| Lenovo                  | 9         | 3.57%   |
| Dell                    | 9         | 3.57%   |
| BenQ                    | 7         | 2.78%   |
| Acer                    | 7         | 2.78%   |
| AOC                     | 6         | 2.38%   |
| Sharp                   | 5         | 1.98%   |
| Ancor Communications    | 5         | 1.98%   |
| Chi Mei Optoelectronics | 4         | 1.59%   |
| Vizio                   | 3         | 1.19%   |
| ViewSonic               | 3         | 1.19%   |
| CPT                     | 3         | 1.19%   |
| MSI                     | 2         | 0.79%   |
| LG Electronics          | 2         | 0.79%   |
| CSO                     | 2         | 0.79%   |
| Toshiba                 | 1         | 0.4%    |
| TBD                     | 1         | 0.4%    |
| Sony                    | 1         | 0.4%    |
| SKY                     | 1         | 0.4%    |
| Seiko/Epson             | 1         | 0.4%    |
| Philips                 | 1         | 0.4%    |
| PANDA                   | 1         | 0.4%    |
| Panasonic               | 1         | 0.4%    |
| NEC Computers           | 1         | 0.4%    |
| LGD                     | 1         | 0.4%    |
| LG Philips              | 1         | 0.4%    |
| Lenovo Group Limited    | 1         | 0.4%    |
| HOP                     | 1         | 0.4%    |
| HannStar                | 1         | 0.4%    |
| Grundig                 | 1         | 0.4%    |
| Denver                  | 1         | 0.4%    |
| AUS                     | 1         | 0.4%    |
| ASUSTek Computer        | 1         | 0.4%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 5         | 1.93%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 4         | 1.54%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 2         | 0.77%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 2         | 0.77%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 2         | 0.77%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 2         | 0.77%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 2         | 0.77%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch | 2         | 0.77%   |
| AU Optronics LCD Monitor AUO413D 1920x1080 309x173mm 13.9-inch           | 2         | 0.77%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 2         | 0.77%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 2         | 0.77%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 2         | 0.77%   |
| Apple Color LCD APPA014 2560x1600 286x179mm 13.3-inch                    | 2         | 0.77%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                     | 2         | 0.77%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                     | 2         | 0.77%   |
| Apple Color LCD APP9CA4 1440x900 331x207mm 15.4-inch                     | 2         | 0.77%   |
| AOC 2369M AOC2369 1920x1080 509x286mm 23.0-inch                          | 2         | 0.77%   |
| AOC 22B2W AOC2202 1920x1080 476x268mm 21.5-inch                          | 2         | 0.77%   |
| Vizio L37 HD VIZ1300 1366x768 820x460mm 37.0-inch                        | 1         | 0.39%   |
| Vizio E321VL VIZ0083 1366x768 700x390mm 31.5-inch                        | 1         | 0.39%   |
| Vizio E320VT VIZ0067 1920x1080 698x392mm 31.5-inch                       | 1         | 0.39%   |
| ViewSonic VA2446 Series VSC732E 1920x1080 521x293mm 23.5-inch            | 1         | 0.39%   |
| ViewSonic VA2445 SERIES VSC712E 1920x1080 521x293mm 23.5-inch            | 1         | 0.39%   |
| ViewSonic VA2055 Series VSC3C31 1920x1080 435x239mm 19.5-inch            | 1         | 0.39%   |
| Toshiba TV TSB0206 1920x1080 886x498mm 40.0-inch                         | 1         | 0.39%   |
| TBD HDMI TBD3148 1600x900 344x193mm 15.5-inch                            | 1         | 0.39%   |
| Sony Nvidia Defaul t Flat Panel MS_0025 1920x1080 531x299mm 24.0-inch    | 1         | 0.39%   |
| SKY SKYWORTH SKY0001 1920x1080 885x498mm 40.0-inch                       | 1         | 0.39%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch                  | 1         | 0.39%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                  | 1         | 0.39%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                  | 1         | 0.39%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                  | 1         | 0.39%   |
| Sharp LCD Monitor SHP1420 1920x1080 294x165mm 13.3-inch                  | 1         | 0.39%   |
| Seiko/Epson LCD Monitor 1920x1080                                        | 1         | 0.39%   |
| Samsung Electronics U32J59x SAM0F33 3840x2160 697x392mm 31.5-inch        | 1         | 0.39%   |
| Samsung Electronics U28H75x SAM0E00 3840x2160 607x345mm 27.5-inch        | 1         | 0.39%   |
| Samsung Electronics U28H75x SAM0DFF 3840x2160 608x345mm 27.5-inch        | 1         | 0.39%   |
| Samsung Electronics SyncMaster SAM0428 1680x1050 459x296mm 21.5-inch     | 1         | 0.39%   |
| Samsung Electronics S27H85x SAM0E0E 2560x1440 597x336mm 27.0-inch        | 1         | 0.39%   |
| Samsung Electronics S27D850 SAM0BC8 2560x1440 598x336mm 27.0-inch        | 1         | 0.39%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 96        | 40%     |
| 1366x768 (WXGA)    | 55        | 22.92%  |
| 1600x900 (HD+)     | 14        | 5.83%   |
| 3840x2160 (4K)     | 13        | 5.42%   |
| 2560x1440 (QHD)    | 10        | 4.17%   |
| 1280x800 (WXGA)    | 9         | 3.75%   |
| 1440x900 (WXGA+)   | 8         | 3.33%   |
| 2560x1600          | 5         | 2.08%   |
| 1920x1200 (WUXGA)  | 5         | 2.08%   |
| 1680x1050 (WSXGA+) | 5         | 2.08%   |
| Unknown            | 4         | 1.67%   |
| 3840x1080          | 3         | 1.25%   |
| 2560x1080          | 3         | 1.25%   |
| 5760x1080          | 1         | 0.42%   |
| 5120x1440          | 1         | 0.42%   |
| 4480x1440          | 1         | 0.42%   |
| 3840x2400          | 1         | 0.42%   |
| 3440x1440          | 1         | 0.42%   |
| 3000x2000          | 1         | 0.42%   |
| 2880x1800          | 1         | 0.42%   |
| 2736x1824          | 1         | 0.42%   |
| 2160x1440          | 1         | 0.42%   |
| 1280x1024 (SXGA)   | 1         | 0.42%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 67        | 26.91%  |
| 13      | 30        | 12.05%  |
| 27      | 21        | 8.43%   |
| 14      | 21        | 8.43%   |
| 21      | 16        | 6.43%   |
| 23      | 14        | 5.62%   |
| 17      | 12        | 4.82%   |
| Unknown | 12        | 4.82%   |
| 24      | 9         | 3.61%   |
| 12      | 8         | 3.21%   |
| 11      | 6         | 2.41%   |
| 20      | 4         | 1.61%   |
| 19      | 4         | 1.61%   |
| 54      | 3         | 1.2%    |
| 31      | 3         | 1.2%    |
| 49      | 2         | 0.8%    |
| 34      | 2         | 0.8%    |
| 10      | 2         | 0.8%    |
| 74      | 1         | 0.4%    |
| 72      | 1         | 0.4%    |
| 40      | 1         | 0.4%    |
| 37      | 1         | 0.4%    |
| 33      | 1         | 0.4%    |
| 32      | 1         | 0.4%    |
| 29      | 1         | 0.4%    |
| 28      | 1         | 0.4%    |
| 26      | 1         | 0.4%    |
| 25      | 1         | 0.4%    |
| 22      | 1         | 0.4%    |
| 18      | 1         | 0.4%    |
| 16      | 1         | 0.4%    |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 100       | 40.98%  |
| 501-600     | 37        | 15.16%  |
| 201-300     | 34        | 13.93%  |
| 401-500     | 25        | 10.25%  |
| 351-400     | 13        | 5.33%   |
| Unknown     | 12        | 4.92%   |
| 601-700     | 10        | 4.1%    |
| 1001-1500   | 5         | 2.05%   |
| 701-800     | 4         | 1.64%   |
| 801-900     | 2         | 0.82%   |
| 1501-2000   | 2         | 0.82%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 172       | 75.77%  |
| 16/10   | 31        | 13.66%  |
| Unknown | 12        | 5.29%   |
| 3/2     | 5         | 2.2%    |
| 21/9    | 4         | 1.76%   |
| 32/9    | 2         | 0.88%   |
| 5/4     | 1         | 0.44%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 67        | 27.02%  |
| 81-90          | 37        | 14.92%  |
| 201-250        | 33        | 13.31%  |
| 301-350        | 23        | 9.27%   |
| 71-80          | 14        | 5.65%   |
| 151-200        | 12        | 4.84%   |
| Unknown        | 12        | 4.84%   |
| 61-70          | 8         | 3.23%   |
| 121-130        | 8         | 3.23%   |
| 351-500        | 7         | 2.82%   |
| 51-60          | 6         | 2.42%   |
| More than 1000 | 5         | 2.02%   |
| 251-300        | 4         | 1.61%   |
| 501-1000       | 4         | 1.61%   |
| 131-140        | 3         | 1.21%   |
| 41-50          | 2         | 0.81%   |
| 141-150        | 2         | 0.81%   |
| 111-120        | 1         | 0.4%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 73        | 30.42%  |
| 101-120       | 73        | 30.42%  |
| 51-100        | 58        | 24.17%  |
| 161-240       | 13        | 5.42%   |
| Unknown       | 12        | 5%      |
| 1-50          | 6         | 2.5%    |
| More than 240 | 5         | 2.08%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 199       | 85.04%  |
| 2     | 23        | 9.83%   |
| 3     | 7         | 2.99%   |
| 0     | 5         | 2.14%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 133       | 36.64%  |
| Intel                             | 98        | 27%     |
| Qualcomm Atheros                  | 35        | 9.64%   |
| Broadcom                          | 33        | 9.09%   |
| TP-Link                           | 10        | 2.75%   |
| Broadcom Limited                  | 8         | 2.2%    |
| Ralink Technology                 | 6         | 1.65%   |
| Marvell Technology Group          | 5         | 1.38%   |
| Xiaomi                            | 4         | 1.1%    |
| Ralink                            | 4         | 1.1%    |
| Sierra Wireless                   | 3         | 0.83%   |
| MediaTek                          | 3         | 0.83%   |
| Samsung Electronics               | 2         | 0.55%   |
| Hewlett-Packard                   | 2         | 0.55%   |
| Qualcomm                          | 1         | 0.28%   |
| OPPO Electronics                  | 1         | 0.28%   |
| Nvidia                            | 1         | 0.28%   |
| NetGear                           | 1         | 0.28%   |
| NEC Computers                     | 1         | 0.28%   |
| Mercucys                          | 1         | 0.28%   |
| LSI                               | 1         | 0.28%   |
| Linksys                           | 1         | 0.28%   |
| Huawei Technologies               | 1         | 0.28%   |
| Google                            | 1         | 0.28%   |
| Ericsson Business Mobile Networks | 1         | 0.28%   |
| Edimax Technology                 | 1         | 0.28%   |
| DisplayLink                       | 1         | 0.28%   |
| D-Link                            | 1         | 0.28%   |
| Attansic Technology               | 1         | 0.28%   |
| ASUSTek Computer                  | 1         | 0.28%   |
| ASIX Electronics                  | 1         | 0.28%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 86        | 20.19%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 17        | 3.99%   |
| Intel Wi-Fi 6 AX200                                               | 12        | 2.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 2.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 8         | 1.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 7         | 1.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 7         | 1.64%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 7         | 1.64%   |
| Intel Wi-Fi 6 AX201                                               | 7         | 1.64%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 6         | 1.41%   |
| Intel Wireless 8260                                               | 6         | 1.41%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 6         | 1.41%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 1.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 1.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 1.17%   |
| Intel Wireless 7265                                               | 5         | 1.17%   |
| Intel I211 Gigabit Network Connection                             | 5         | 1.17%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 1.17%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 5         | 1.17%   |
| Ralink MT7601U Wireless Adapter                                   | 4         | 0.94%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 0.94%   |
| Intel Wireless 8265 / 8275                                        | 4         | 0.94%   |
| Intel Wireless 7260                                               | 4         | 0.94%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 0.94%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 0.94%   |
| Broadcom BCM43142 802.11b/g/n                                     | 4         | 0.94%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 4         | 0.94%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.7%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 3         | 0.7%    |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 3         | 0.7%    |
| Intel Wireless 3160                                               | 3         | 0.7%    |
| Intel Tiger Lake PCH CNVi WiFi                                    | 3         | 0.7%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 3         | 0.7%    |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.7%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 3         | 0.7%    |
| Intel Centrino Wireless-N 2230                                    | 3         | 0.7%    |
| Intel 82574L Gigabit Network Connection                           | 3         | 0.7%    |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 3         | 0.7%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 2         | 0.47%   |
| TP-Link 802.11ac WLAN Adapter                                     | 2         | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 80        | 37.21%  |
| Realtek Semiconductor    | 40        | 18.6%   |
| Qualcomm Atheros         | 29        | 13.49%  |
| Broadcom                 | 29        | 13.49%  |
| TP-Link                  | 10        | 4.65%   |
| Ralink Technology        | 6         | 2.79%   |
| Broadcom Limited         | 6         | 2.79%   |
| Ralink                   | 4         | 1.86%   |
| Sierra Wireless          | 3         | 1.4%    |
| Marvell Technology Group | 2         | 0.93%   |
| NetGear                  | 1         | 0.47%   |
| Mercucys                 | 1         | 0.47%   |
| MediaTek                 | 1         | 0.47%   |
| Edimax Technology        | 1         | 0.47%   |
| D-Link                   | 1         | 0.47%   |
| ASUSTek Computer         | 1         | 0.47%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 12        | 5.58%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 8         | 3.72%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 7         | 3.26%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 7         | 3.26%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 7         | 3.26%   |
| Intel Wi-Fi 6 AX201                                            | 7         | 3.26%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 6         | 2.79%   |
| Intel Wireless 8260                                            | 6         | 2.79%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 6         | 2.79%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 2.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 5         | 2.33%   |
| Intel Wireless 7265                                            | 5         | 2.33%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 5         | 2.33%   |
| Ralink MT7601U Wireless Adapter                                | 4         | 1.86%   |
| Intel Wireless 8265 / 8275                                     | 4         | 1.86%   |
| Intel Wireless 7260                                            | 4         | 1.86%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 1.86%   |
| Broadcom BCM43142 802.11b/g/n                                  | 4         | 1.86%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 4         | 1.86%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 3         | 1.4%    |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 3         | 1.4%    |
| Intel Wireless 3160                                            | 3         | 1.4%    |
| Intel Tiger Lake PCH CNVi WiFi                                 | 3         | 1.4%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 3         | 1.4%    |
| Intel Comet Lake PCH CNVi WiFi                                 | 3         | 1.4%    |
| Intel Centrino Wireless-N 2230                                 | 3         | 1.4%    |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 3         | 1.4%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 2         | 0.93%   |
| TP-Link 802.11ac WLAN Adapter                                  | 2         | 0.93%   |
| TP-Link 802.11ac NIC                                           | 2         | 0.93%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 2         | 0.93%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 2         | 0.93%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2         | 0.93%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 2         | 0.93%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 2         | 0.93%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 0.93%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless              | 2         | 0.93%   |
| Intel Wireless 3165                                            | 2         | 0.93%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 0.93%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 2         | 0.93%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 112       | 55.17%  |
| Intel                    | 44        | 21.67%  |
| Broadcom                 | 14        | 6.9%    |
| Qualcomm Atheros         | 11        | 5.42%   |
| Xiaomi                   | 4         | 1.97%   |
| Marvell Technology Group | 3         | 1.48%   |
| Samsung Electronics      | 2         | 0.99%   |
| MediaTek                 | 2         | 0.99%   |
| Broadcom Limited         | 2         | 0.99%   |
| Qualcomm                 | 1         | 0.49%   |
| OPPO Electronics         | 1         | 0.49%   |
| Nvidia                   | 1         | 0.49%   |
| LSI                      | 1         | 0.49%   |
| Linksys                  | 1         | 0.49%   |
| Google                   | 1         | 0.49%   |
| DisplayLink              | 1         | 0.49%   |
| Attansic Technology      | 1         | 0.49%   |
| ASIX Electronics         | 1         | 0.49%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 86        | 41.75%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 17        | 8.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 10        | 4.85%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 5         | 2.43%   |
| Intel I211 Gigabit Network Connection                                          | 5         | 2.43%   |
| Intel 82577LM Gigabit Network Connection                                       | 5         | 2.43%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 4         | 1.94%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 4         | 1.94%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 3         | 1.46%   |
| Intel Ethernet Connection I217-LM                                              | 3         | 1.46%   |
| Intel 82574L Gigabit Network Connection                                        | 3         | 1.46%   |
| Realtek RTL8125 2.5GbE Controller                                              | 2         | 0.97%   |
| MediaTek Infinix NOTE 11                                                       | 2         | 0.97%   |
| Intel Ethernet Connection I219-V                                               | 2         | 0.97%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 0.97%   |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 0.97%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 0.97%   |
| Intel Ethernet Connection (2) I219-V                                           | 2         | 0.97%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 2         | 0.97%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                              | 2         | 0.97%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                              | 2         | 0.97%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 2         | 0.97%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.49%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.49%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.49%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.49%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1         | 0.49%   |
| Qualcomm MegaFon M150-4                                                        | 1         | 0.49%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.49%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.49%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 0.49%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.49%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.49%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.49%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.49%   |
| OPPO RMX3263                                                                   | 1         | 0.49%   |
| Nvidia MCP77 Ethernet                                                          | 1         | 0.49%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.49%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 0.49%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 1         | 0.49%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 198       | 50.13%  |
| Ethernet | 192       | 48.61%  |
| Modem    | 4         | 1.01%   |
| Unknown  | 1         | 0.25%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 160       | 68.09%  |
| Ethernet | 75        | 31.91%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 134       | 57.51%  |
| 1     | 95        | 40.77%  |
| 3     | 3         | 1.29%   |
| 0     | 1         | 0.43%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 171       | 73.08%  |
| Yes  | 63        | 26.92%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 66        | 38.37%  |
| Realtek Semiconductor           | 24        | 13.95%  |
| Apple                           | 17        | 9.88%   |
| Qualcomm Atheros Communications | 15        | 8.72%   |
| Broadcom                        | 13        | 7.56%   |
| Cambridge Silicon Radio         | 12        | 6.98%   |
| Lite-On Technology              | 5         | 2.91%   |
| Foxconn / Hon Hai               | 5         | 2.91%   |
| IMC Networks                    | 3         | 1.74%   |
| Ralink                          | 2         | 1.16%   |
| Marvell Semiconductor           | 2         | 1.16%   |
| Dell                            | 2         | 1.16%   |
| Toshiba                         | 1         | 0.58%   |
| Realtek                         | 1         | 0.58%   |
| Qcom                            | 1         | 0.58%   |
| Hewlett-Packard                 | 1         | 0.58%   |
| Belkin Components               | 1         | 0.58%   |
| ASUSTek Computer                | 1         | 0.58%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 25        | 14.53%  |
| Realtek Bluetooth Radio                                                             | 15        | 8.72%   |
| Intel AX201 Bluetooth                                                               | 12        | 6.98%   |
| Intel AX200 Bluetooth                                                               | 12        | 6.98%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 12        | 6.98%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 9         | 5.23%   |
| Apple Bluetooth USB Host Controller                                                 | 8         | 4.65%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 7         | 4.07%   |
| Apple Bluetooth Host Controller                                                     | 7         | 4.07%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 6         | 3.49%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 5         | 2.91%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 5         | 2.91%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 3         | 1.74%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 3         | 1.74%   |
| Ralink RT3290 Bluetooth                                                             | 2         | 1.16%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1.16%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 1.16%   |
| IMC Networks Bluetooth Radio                                                        | 2         | 1.16%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 1.16%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 2         | 1.16%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 2         | 1.16%   |
| Toshiba Bluetooth USB Host Controller                                               | 1         | 0.58%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.58%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.58%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.58%   |
| Qcom Broadcom Bluetooth USB                                                         | 1         | 0.58%   |
| Marvell Bluetooth and Wireless LAN Composite Device                                 | 1         | 0.58%   |
| Marvell Bluetooth and Wireless LAN Composite                                        | 1         | 0.58%   |
| Lite-On Wireless_Device                                                             | 1         | 0.58%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 0.58%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 1         | 0.58%   |
| Lite-On Bluetooth Device                                                            | 1         | 0.58%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 0.58%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 0.58%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.58%   |
| Intel AX210 Bluetooth                                                               | 1         | 0.58%   |
| IMC Networks BCM20702A0                                                             | 1         | 0.58%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.58%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.58%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.58%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 183       | 58.1%   |
| AMD                                  | 62        | 19.68%  |
| Nvidia                               | 42        | 13.33%  |
| C-Media Electronics                  | 7         | 2.22%   |
| Logitech                             | 3         | 0.95%   |
| Generalplus Technology               | 3         | 0.95%   |
| Creative Labs                        | 3         | 0.95%   |
| JMTek                                | 2         | 0.63%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.32%   |
| TEAC                                 | 1         | 0.32%   |
| Razer USA                            | 1         | 0.32%   |
| GN Netcom                            | 1         | 0.32%   |
| Focusrite-Novation                   | 1         | 0.32%   |
| Creative Technology                  | 1         | 0.32%   |
| Corsair                              | 1         | 0.32%   |
| BY EDIFIER                           | 1         | 0.32%   |
| ATI Technologies                     | 1         | 0.32%   |
| ASUSTek Computer                     | 1         | 0.32%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 24        | 6.37%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 23        | 6.1%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 15        | 3.98%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 15        | 3.98%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 14        | 3.71%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 13        | 3.45%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 11        | 2.92%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 9         | 2.39%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 9         | 2.39%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 9         | 2.39%   |
| Intel Broadwell-U Audio Controller                                                                | 8         | 2.12%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 8         | 2.12%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 7         | 1.86%   |
| Intel Cannon Lake PCH cAVS                                                                        | 7         | 1.86%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6         | 1.59%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 1.59%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 6         | 1.59%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 1.59%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 1.59%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 5         | 1.33%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 5         | 1.33%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 1.33%   |
| Intel 200 Series PCH HD Audio                                                                     | 5         | 1.33%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 1.33%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 1.33%   |
| AMD FCH Azalia Controller                                                                         | 5         | 1.33%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 4         | 1.06%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 1.06%   |
| Intel CM238 HD Audio Controller                                                                   | 4         | 1.06%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 1.06%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 4         | 1.06%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 4         | 1.06%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 0.8%    |
| Nvidia GP104 High Definition Audio Controller                                                     | 3         | 0.8%    |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.8%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 0.8%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 0.8%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 0.8%    |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 3         | 0.8%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3         | 0.8%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 19        | 24.68%  |
| SK hynix            | 14        | 18.18%  |
| Kingston            | 12        | 15.58%  |
| Micron Technology   | 10        | 12.99%  |
| Unknown             | 3         | 3.9%    |
| G.Skill             | 3         | 3.9%    |
| Crucial             | 3         | 3.9%    |
| Ramaxel Technology  | 2         | 2.6%    |
| Corsair             | 2         | 2.6%    |
| A-DATA Technology   | 2         | 2.6%    |
| Toshiba             | 1         | 1.3%    |
| Qimonda             | 1         | 1.3%    |
| Neo Forza           | 1         | 1.3%    |
| Nanya Technology    | 1         | 1.3%    |
| Kllisre             | 1         | 1.3%    |
| GSkill              | 1         | 1.3%    |
| Unknown             | 1         | 1.3%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 3         | 3.75%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s      | 2         | 2.5%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s       | 2         | 2.5%    |
| Unknown RAM Module 4096MB Chip DDR4 2133MT/s                | 1         | 1.25%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                 | 1         | 1.25%   |
| Unknown RAM Module 1024MB SODIMM LPDDR4 2400MT/s            | 1         | 1.25%   |
| Toshiba RAM 8HTF12864HDY-800G1 4GB SODIMM 1066MT/s          | 1         | 1.25%   |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM DDR2 1066MT/s      | 1         | 1.25%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                | 1         | 1.25%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1867MT/s             | 1         | 1.25%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 1.25%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 1         | 1.25%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s      | 1         | 1.25%   |
| SK hynix RAM HMT31GR7BFR4C-H9 8GB DIMM DDR3 1333MT/s        | 1         | 1.25%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s     | 1         | 1.25%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s      | 1         | 1.25%   |
| SK hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s     | 1         | 1.25%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s      | 1         | 1.25%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s      | 1         | 1.25%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 1         | 1.25%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s              | 1         | 1.25%   |
| Samsung RAM Module 8192MB DIMM DDR4 2666MT/s                | 1         | 1.25%   |
| Samsung RAM M471B5773DH0-CK0 2048MB SODIMM DDR3 1600MT/s    | 1         | 1.25%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s       | 1         | 1.25%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s       | 1         | 1.25%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s       | 1         | 1.25%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s       | 1         | 1.25%   |
| Samsung RAM M471B2873FHS-CF8 1GB SODIMM DDR3 1067MT/s       | 1         | 1.25%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s       | 1         | 1.25%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s      | 1         | 1.25%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s      | 1         | 1.25%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s | 1         | 1.25%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2400MT/s       | 1         | 1.25%   |
| Samsung RAM M4 70T5663EH3-CF7 2GB SODIMM DDR2 975MT/s       | 1         | 1.25%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3200MT/s         | 1         | 1.25%   |
| Ramaxel RAM RMT3170EF68F9W1600 4GB SODIMM DDR3 1600MT/s     | 1         | 1.25%   |
| Ramaxel RAM RMSA3310NA86H9F-2666 4GB SODIMM DDR4 2667MT/s   | 1         | 1.25%   |
| Qimonda RAM 64T256020EDL2.5C2 2GB SODIMM DDR2 2048MT/s      | 1         | 1.25%   |
| Neo Forza RAM NMUD380D81-1600D 8GB DIMM DDR3 1333MT/s       | 1         | 1.25%   |
| Nanya RAM Module 4GB DIMM DDR3 1333MT/s                     | 1         | 1.25%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 29        | 48.33%  |
| DDR3   | 25        | 41.67%  |
| SDRAM  | 2         | 3.33%   |
| LPDDR4 | 2         | 3.33%   |
| DDR2   | 2         | 3.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 45        | 72.58%  |
| DIMM         | 13        | 20.97%  |
| Row Of Chips | 2         | 3.23%   |
| Chip         | 2         | 3.23%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 25        | 36.23%  |
| 4096  | 21        | 30.43%  |
| 2048  | 11        | 15.94%  |
| 16384 | 10        | 14.49%  |
| 1024  | 2         | 2.9%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 18        | 26.47%  |
| 3200  | 12        | 17.65%  |
| 2667  | 11        | 16.18%  |
| 2400  | 4         | 5.88%   |
| 2133  | 4         | 5.88%   |
| 1333  | 4         | 5.88%   |
| 1867  | 3         | 4.41%   |
| 3600  | 2         | 2.94%   |
| 4267  | 1         | 1.47%   |
| 4199  | 1         | 1.47%   |
| 3007  | 1         | 1.47%   |
| 3000  | 1         | 1.47%   |
| 2666  | 1         | 1.47%   |
| 2048  | 1         | 1.47%   |
| 1334  | 1         | 1.47%   |
| 1067  | 1         | 1.47%   |
| 1066  | 1         | 1.47%   |
| 800   | 1         | 1.47%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 2         | 50%     |
| Brother Industries | 2         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                    | Computers | Percent |
|--------------------------|-----------|---------|
| HP LaserJet M101-M106    | 1         | 25%     |
| HP Deskjet F4500 series  | 1         | 25%     |
| Brother MFC-T800W        | 1         | 25%     |
| Brother HL-4140CN series | 1         | 25%     |

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
| Chicony Electronics                    | 40        | 25.32%  |
| Microdia                               | 15        | 9.49%   |
| Realtek Semiconductor                  | 13        | 8.23%   |
| Apple                                  | 13        | 8.23%   |
| Acer                                   | 10        | 6.33%   |
| Quanta                                 | 9         | 5.7%    |
| Logitech                               | 9         | 5.7%    |
| Sunplus Innovation Technology          | 8         | 5.06%   |
| Suyin                                  | 7         | 4.43%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 4.43%   |
| Syntek                                 | 4         | 2.53%   |
| Lenovo                                 | 4         | 2.53%   |
| Microsoft                              | 3         | 1.9%    |
| Luxvisions Innotech Limited            | 3         | 1.9%    |
| Lite-On Technology                     | 3         | 1.9%    |
| IMC Networks                           | 3         | 1.9%    |
| Z-Star Microelectronics                | 1         | 0.63%   |
| USB Camera                             | 1         | 0.63%   |
| Primax Electronics                     | 1         | 0.63%   |
| Importek                               | 1         | 0.63%   |
| HD 2MP WEBCAM                          | 1         | 0.63%   |
| Generalplus Technology                 | 1         | 0.63%   |
| Creative Technology                    | 1         | 0.63%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 8         | 5%      |
| Realtek Integrated_Webcam_HD             | 4         | 2.5%    |
| Chicony HD WebCam                        | 4         | 2.5%    |
| Apple FaceTime HD Camera (Built-in)      | 4         | 2.5%    |
| Apple FaceTime HD Camera                 | 4         | 2.5%    |
| Realtek HD WebCam                        | 3         | 1.88%   |
| Quanta HP TrueVision HD Camera           | 3         | 1.88%   |
| Chicony HP Wide Vision HD Camera         | 3         | 1.88%   |
| Chicony HP Truevision HD                 | 3         | 1.88%   |
| Chicony HP HD Webcam [Fixed]             | 3         | 1.88%   |
| Apple iPhone5/5C/5S/6                    | 3         | 1.88%   |
| Acer Lenovo EasyCamera                   | 3         | 1.88%   |
| Syntek Integrated Camera                 | 2         | 1.25%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 2         | 1.25%   |
| Suyin 1.3M Front                         | 2         | 1.25%   |
| Sunplus Laptop_Integrated_Webcam_HD      | 2         | 1.25%   |
| Realtek USB Camera                       | 2         | 1.25%   |
| Microdia Webcam Vitade AF                | 2         | 1.25%   |
| Microdia Laptop_Integrated_Webcam_HD     | 2         | 1.25%   |
| Microdia Integrated_Webcam_HD            | 2         | 1.25%   |
| Logitech Webcam C270                     | 2         | 1.25%   |
| Logitech HD Pro Webcam C920              | 2         | 1.25%   |
| Lite-On Integrated Camera                | 2         | 1.25%   |
| Lenovo Integrated Webcam                 | 2         | 1.25%   |
| IMC Networks USB2.0 HD UVC WebCam        | 2         | 1.25%   |
| Chicony USB2.0 Camera                    | 2         | 1.25%   |
| Chicony HP TrueVision HD Camera          | 2         | 1.25%   |
| Chicony HP High Definition 1MP Webcam    | 2         | 1.25%   |
| Chicony HP HD Webcam                     | 2         | 1.25%   |
| Apple Built-in iSight                    | 2         | 1.25%   |
| Z-Star Sirius USB2.0 Camera              | 1         | 0.63%   |
| USB Camera USB Camera                    | 1         | 0.63%   |
| Syntek USB2.0 Camera                     | 1         | 0.63%   |
| Syntek EasyCamera                        | 1         | 0.63%   |
| Suyin HP TrueVision HD Integrated Webcam | 1         | 0.63%   |
| Suyin Asus Integrated Webcam             | 1         | 0.63%   |
| Suyin 1.3M HD WebCam                     | 1         | 0.63%   |
| Sunplus SPCA2650 AV Camera               | 1         | 0.63%   |
| Sunplus Laptop_Integrated_Webcam_1.3M    | 1         | 0.63%   |
| Sunplus Laptop Integrated WebCam HD      | 1         | 0.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 14        | 42.42%  |
| Synaptics                  | 4         | 12.12%  |
| Upek                       | 3         | 9.09%   |
| Shenzhen Goodix Technology | 3         | 9.09%   |
| LighTuning Technology      | 3         | 9.09%   |
| AuthenTec                  | 3         | 9.09%   |
| STMicroelectronics         | 1         | 3.03%   |
| Focal-systems.Corp         | 1         | 3.03%   |
| Elan Microelectronics      | 1         | 3.03%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 9.09%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 9.09%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 9.09%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 6.06%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 6.06%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 6.06%   |
| Shenzhen Goodix  FingerPrint Device                                        | 2         | 6.06%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 3.03%   |
| Validity Sensors VFS491                                                    | 1         | 3.03%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 3.03%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 3.03%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 3.03%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 3.03%   |
| Synaptics  WBDI                                                            | 1         | 3.03%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 3.03%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 3.03%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 3.03%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 3.03%   |
| Elan ELAN:ARM-M4                                                           | 1         | 3.03%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 3.03%   |
| AuthenTec AES2810                                                          | 1         | 3.03%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 3.03%   |
| Unknown                                                                    | 1         | 3.03%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 2         | 40%     |
| Alcor Micro | 2         | 40%     |
| Upek        | 1         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 40%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 20%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 20%     |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 166       | 70.94%  |
| 1     | 55        | 23.5%   |
| 2     | 12        | 5.13%   |
| 3     | 1         | 0.43%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 33        | 39.29%  |
| Net/wireless             | 16        | 19.05%  |
| Graphics card            | 13        | 15.48%  |
| Multimedia controller    | 8         | 9.52%   |
| Chipcard                 | 5         | 5.95%   |
| Sound                    | 2         | 2.38%   |
| Net/ethernet             | 2         | 2.38%   |
| Bluetooth                | 2         | 2.38%   |
| Storage                  | 1         | 1.19%   |
| Communication controller | 1         | 1.19%   |
| Camera                   | 1         | 1.19%   |

