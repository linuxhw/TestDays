Elementary 6 - Tested Hardware & Statistics
-------------------------------------------

A project to collect tested hardware configurations for Elementary 6.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Elementary_6/Desktop/README.md) and [notebooks](/Dist/Elementary_6/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| ASUSTek       | TUF GAMING B560M-PLUS       | Desktop     | [5c0550c1e8](https://linux-hardware.org/?probe=5c0550c1e8) | Dec 09, 2021 |
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
| Chuwi         | LarkBox Pro                 | Desktop     | [4af62a6057](https://linux-hardware.org/?probe=4af62a6057) | Nov 29, 2021 |
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
| Lenovo        | ThinkPad SL400 2743A37      | Notebook    | [8c0a3a65ba](https://linux-hardware.org/?probe=8c0a3a65ba) | Nov 26, 2021 |
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
| HP            | 2B42                        | All in one  | [794d39b312](https://linux-hardware.org/?probe=794d39b312) | Oct 11, 2021 |
| HP            | 2B42                        | All in one  | [936b3a489d](https://linux-hardware.org/?probe=936b3a489d) | Oct 11, 2021 |
| HP            | 2B42                        | All in one  | [c1224ad1ab](https://linux-hardware.org/?probe=c1224ad1ab) | Oct 11, 2021 |
| ASUSTek       | 1215B                       | Notebook    | [7b3bf2ca14](https://linux-hardware.org/?probe=7b3bf2ca14) | Oct 11, 2021 |
| HP            | EliteBook 8440p             | Notebook    | [e5071e6c43](https://linux-hardware.org/?probe=e5071e6c43) | Oct 10, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [f6e75d0258](https://linux-hardware.org/?probe=f6e75d0258) | Oct 09, 2021 |
| HP            | ProBook 4530s               | Notebook    | [0a725a0b81](https://linux-hardware.org/?probe=0a725a0b81) | Oct 07, 2021 |
| Apple         | MacBookPro7,1               | Notebook    | [644b3b5b60](https://linux-hardware.org/?probe=644b3b5b60) | Oct 04, 2021 |
| MSI           | B460M PRO-VDH WIFI          | Desktop     | [05711b548f](https://linux-hardware.org/?probe=05711b548f) | Oct 03, 2021 |
| ASUSTek       | TUF GAMING B560M-PLUS       | Desktop     | [de0f051658](https://linux-hardware.org/?probe=de0f051658) | Oct 02, 2021 |
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
| ASUSTek       | TUF GAMING B450M-PRO II     | Desktop     | [73beb900ea](https://linux-hardware.org/?probe=73beb900ea) | Aug 15, 2021 |
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
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [63da02a979](https://linux-hardware.org/?probe=63da02a979) | May 19, 2021 |
| Acer          | ConceptD CN315-71P          | Notebook    | [5ecea84320](https://linux-hardware.org/?probe=5ecea84320) | May 15, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [223234378e](https://linux-hardware.org/?probe=223234378e) | May 04, 2021 |
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

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.11.0-40-generic      | 52        | 21.94%  |
| 5.11.0-41-generic      | 40        | 16.88%  |
| 5.11.0-27-generic      | 40        | 16.88%  |
| 5.11.0-38-generic      | 27        | 11.39%  |
| 5.11.0-37-generic      | 24        | 10.13%  |
| 5.11.0-25-generic      | 16        | 6.75%   |
| 5.11.0-34-generic      | 14        | 5.91%   |
| 5.8.0-50-generic       | 5         | 2.11%   |
| 5.11.0-36-generic      | 4         | 1.69%   |
| 5.8.0-55-generic       | 3         | 1.27%   |
| 5.8.0-63-generic       | 2         | 0.84%   |
| 5.8.0-53-generic       | 1         | 0.42%   |
| 5.8.0-44-generic       | 1         | 0.42%   |
| 5.4.0-91-generic       | 1         | 0.42%   |
| 5.4.0-58-generic       | 1         | 0.42%   |
| 5.4.0-56-generic       | 1         | 0.42%   |
| 5.15.1-xanmod1         | 1         | 0.42%   |
| 5.14.7-xanmod1-cacule  | 1         | 0.42%   |
| 5.14.14-051414-generic | 1         | 0.42%   |
| 5.11.0-41-lowlatency   | 1         | 0.42%   |
| 5.11.0-051100-generic  | 1         | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11.0  | 209       | 92.07%  |
| 5.8.0   | 12        | 5.29%   |
| 5.4.0   | 3         | 1.32%   |
| 5.15.1  | 1         | 0.44%   |
| 5.14.7  | 1         | 0.44%   |
| 5.14.14 | 1         | 0.44%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11    | 209       | 92.07%  |
| 5.8     | 12        | 5.29%   |
| 5.4     | 3         | 1.32%   |
| 5.14    | 2         | 0.88%   |
| 5.15    | 1         | 0.44%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 227       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Pantheon   | 207       | 90.79%  |
| Unknown    | 15        | 6.58%   |
| GNOME      | 3         | 1.32%   |
| X-Cinnamon | 2         | 0.88%   |
| MATE       | 1         | 0.44%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 227       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 178       | 78.41%  |
| LightDM | 39        | 17.18%  |
| TDM     | 7         | 3.08%   |
| GDM     | 3         | 1.32%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 115       | 50.66%  |
| de_DE | 22        | 9.69%   |
| es_ES | 19        | 8.37%   |
| ru_RU | 8         | 3.52%   |
| pt_BR | 8         | 3.52%   |
| fr_FR | 8         | 3.52%   |
| en_GB | 6         | 2.64%   |
| en_CA | 5         | 2.2%    |
| pl_PL | 4         | 1.76%   |
| it_IT | 4         | 1.76%   |
| zh_CN | 3         | 1.32%   |
| en_AU | 3         | 1.32%   |
| cs_CZ | 3         | 1.32%   |
| tr_TR | 2         | 0.88%   |
| nl_NL | 2         | 0.88%   |
| de_CH | 2         | 0.88%   |
| ca_ES | 2         | 0.88%   |
| vi_VN | 1         | 0.44%   |
| ro_RO | 1         | 0.44%   |
| lt_LT | 1         | 0.44%   |
| id_ID | 1         | 0.44%   |
| hu_HU | 1         | 0.44%   |
| hr_HR | 1         | 0.44%   |
| gl_ES | 1         | 0.44%   |
| fr_BE | 1         | 0.44%   |
| fi_FI | 1         | 0.44%   |
| es_MX | 1         | 0.44%   |
| da_DK | 1         | 0.44%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 143       | 62.72%  |
| BIOS | 85        | 37.28%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 218       | 96.04%  |
| Overlay | 5         | 2.2%    |
| Btrfs   | 4         | 1.76%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 187       | 82.38%  |
| GPT     | 29        | 12.78%  |
| MBR     | 11        | 4.85%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 217       | 95.59%  |
| Yes       | 10        | 4.41%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 200       | 88.11%  |
| Yes       | 27        | 11.89%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 48        | 21.15%  |
| Lenovo                  | 27        | 11.89%  |
| Dell                    | 25        | 11.01%  |
| ASUSTek Computer        | 24        | 10.57%  |
| Apple                   | 16        | 7.05%   |
| Acer                    | 16        | 7.05%   |
| Gigabyte Technology     | 14        | 6.17%   |
| MSI                     | 8         | 3.52%   |
| ASRock                  | 8         | 3.52%   |
| Toshiba                 | 4         | 1.76%   |
| Intel                   | 3         | 1.32%   |
| HUAWEI                  | 3         | 1.32%   |
| Google                  | 3         | 1.32%   |
| TUXEDO                  | 2         | 0.88%   |
| Sony                    | 2         | 0.88%   |
| Pegatron                | 2         | 0.88%   |
| Microsoft               | 2         | 0.88%   |
| Medion                  | 2         | 0.88%   |
| Biostar                 | 2         | 0.88%   |
| Star Labs               | 1         | 0.44%   |
| Shuttle                 | 1         | 0.44%   |
| Schenker                | 1         | 0.44%   |
| Samsung Electronics     | 1         | 0.44%   |
| Quanta                  | 1         | 0.44%   |
| Panasonic               | 1         | 0.44%   |
| Packard Bell            | 1         | 0.44%   |
| Notebook                | 1         | 0.44%   |
| HCL Infosystems Limited | 1         | 0.44%   |
| Gateway                 | 1         | 0.44%   |
| Fujitsu                 | 1         | 0.44%   |
| eMachines               | 1         | 0.44%   |
| Chuwi                   | 1         | 0.44%   |
| Alienware               | 1         | 0.44%   |
| Acidanthera             | 1         | 0.44%   |
| Unknown                 | 1         | 0.44%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Lenovo Yoga 300-11IBR 80M1           | 2         | 0.88%   |
| HP Pavilion Notebook                 | 2         | 0.88%   |
| Dell XPS 13 9350                     | 2         | 0.88%   |
| Dell Inspiron N5110                  | 2         | 0.88%   |
| Apple MacBookPro9,1                  | 2         | 0.88%   |
| Apple MacBookPro10,2                 | 2         | 0.88%   |
| Apple MacBookAir7,2                  | 2         | 0.88%   |
| TUXEDO Pulse 15 Gen1                 | 1         | 0.44%   |
| TUXEDO InfinityBook S 14 Gen6        | 1         | 0.44%   |
| Toshiba Satellite P100               | 1         | 0.44%   |
| Toshiba Satellite L840               | 1         | 0.44%   |
| Toshiba Satellite L750               | 1         | 0.44%   |
| Toshiba Satellite L500               | 1         | 0.44%   |
| Star Labs StarBook                   | 1         | 0.44%   |
| Sony SVE15115EN                      | 1         | 0.44%   |
| Sony Serie VJC14                     | 1         | 0.44%   |
| Shuttle DS61                         | 1         | 0.44%   |
| Schenker X170KM-G                    | 1         | 0.44%   |
| Samsung 550XDA                       | 1         | 0.44%   |
| Quanta TW9/SW9                       | 1         | 0.44%   |
| Pegatron KJ379AA-ABA a6400f          | 1         | 0.44%   |
| Pegatron IPMH61P1                    | 1         | 0.44%   |
| Panasonic FZ-G1ASH39E3               | 1         | 0.44%   |
| Packard Bell EasyNote LS11HR         | 1         | 0.44%   |
| Notebook L140CU                      | 1         | 0.44%   |
| MSI MS-7C83                          | 1         | 0.44%   |
| MSI MS-7B79                          | 1         | 0.44%   |
| MSI MS-7B46                          | 1         | 0.44%   |
| MSI MS-7817                          | 1         | 0.44%   |
| MSI MS-7693                          | 1         | 0.44%   |
| MSI Modern 14 B4MW                   | 1         | 0.44%   |
| MSI GF72 7RE                         | 1         | 0.44%   |
| MSI Elite 7100 Microtower PC         | 1         | 0.44%   |
| Microsoft Surface Pro 4              | 1         | 0.44%   |
| Microsoft Surface Pro 3              | 1         | 0.44%   |
| Medion E7218                         | 1         | 0.44%   |
| Medion Akoya THE TOUCH 10            | 1         | 0.44%   |
| Lenovo V330-15IKB 81AX               | 1         | 0.44%   |
| Lenovo ThinkPad X250 20CLS32H00      | 1         | 0.44%   |
| Lenovo ThinkPad X230 23259L3         | 1         | 0.44%   |
| Lenovo ThinkPad X201 Tablet 311396G  | 1         | 0.44%   |
| Lenovo ThinkPad X201 3249CTO         | 1         | 0.44%   |
| Lenovo ThinkPad X140e 20BLS00400     | 1         | 0.44%   |
| Lenovo ThinkPad X1 Carbon 3448B86    | 1         | 0.44%   |
| Lenovo ThinkPad W700 2758MVG         | 1         | 0.44%   |
| Lenovo ThinkPad T470 20HD004AUS      | 1         | 0.44%   |
| Lenovo ThinkPad T460s 20F9CTO1WW     | 1         | 0.44%   |
| Lenovo ThinkPad T460s 20F90042MS     | 1         | 0.44%   |
| Lenovo ThinkPad T430 2342A19         | 1         | 0.44%   |
| Lenovo ThinkPad T410s 292494G        | 1         | 0.44%   |
| Lenovo ThinkPad T14 Gen 1 20UES5SR00 | 1         | 0.44%   |
| Lenovo ThinkPad SL400 2743A37        | 1         | 0.44%   |
| Lenovo ThinkPad E470 20H10052IG      | 1         | 0.44%   |
| Lenovo ThinkPad E14 Gen 3 20Y7006XMX | 1         | 0.44%   |
| Lenovo IdeaPad S145-15AST 81N3       | 1         | 0.44%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5     | 1         | 0.44%   |
| Lenovo IdeaPad 5 14ARE05 81YM        | 1         | 0.44%   |
| Lenovo IdeaPad 330-15IKB 81FE        | 1         | 0.44%   |
| Lenovo IdeaPad 320S-14IKB 81BN       | 1         | 0.44%   |
| Lenovo IdeaPad 120S-14IAP 81A5       | 1         | 0.44%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 16        | 7.05%   |
| HP Pavilion            | 13        | 5.73%   |
| Acer Aspire            | 11        | 4.85%   |
| Dell Inspiron          | 7         | 3.08%   |
| Lenovo IdeaPad         | 6         | 2.64%   |
| HP ProBook             | 6         | 2.64%   |
| HP Laptop              | 6         | 2.64%   |
| HP EliteBook           | 6         | 2.64%   |
| Dell XPS               | 6         | 2.64%   |
| HP ENVY                | 5         | 2.2%    |
| Toshiba Satellite      | 4         | 1.76%   |
| Dell Latitude          | 4         | 1.76%   |
| Dell OptiPlex          | 3         | 1.32%   |
| ASUS TUF               | 3         | 1.32%   |
| ASUS ROG               | 3         | 1.32%   |
| Microsoft Surface      | 2         | 0.88%   |
| Lenovo Yoga            | 2         | 0.88%   |
| HP Compaq              | 2         | 0.88%   |
| Gigabyte X570          | 2         | 0.88%   |
| Dell System            | 2         | 0.88%   |
| Dell Precision         | 2         | 0.88%   |
| ASUS PRIME             | 2         | 0.88%   |
| Apple MacBookPro9      | 2         | 0.88%   |
| Apple MacBookPro8      | 2         | 0.88%   |
| Apple MacBookPro10     | 2         | 0.88%   |
| Apple MacBookAir7      | 2         | 0.88%   |
| Acer Swift             | 2         | 0.88%   |
| Acer ConceptD          | 2         | 0.88%   |
| TUXEDO Pulse           | 1         | 0.44%   |
| TUXEDO InfinityBook    | 1         | 0.44%   |
| Star Labs StarBook     | 1         | 0.44%   |
| Sony SVE15115EN        | 1         | 0.44%   |
| Sony Serie             | 1         | 0.44%   |
| Shuttle DS61           | 1         | 0.44%   |
| Schenker X170KM-G      | 1         | 0.44%   |
| Samsung 550XDA         | 1         | 0.44%   |
| Quanta TW9             | 1         | 0.44%   |
| Pegatron KJ379AA-ABA   | 1         | 0.44%   |
| Pegatron IPMH61P1      | 1         | 0.44%   |
| Panasonic FZ-G1ASH39E3 | 1         | 0.44%   |
| Packard Bell EasyNote  | 1         | 0.44%   |
| Notebook L140CU        | 1         | 0.44%   |
| MSI MS-7C83            | 1         | 0.44%   |
| MSI MS-7B79            | 1         | 0.44%   |
| MSI MS-7B46            | 1         | 0.44%   |
| MSI MS-7817            | 1         | 0.44%   |
| MSI MS-7693            | 1         | 0.44%   |
| MSI Modern             | 1         | 0.44%   |
| MSI GF72               | 1         | 0.44%   |
| MSI Elite              | 1         | 0.44%   |
| Medion E7218           | 1         | 0.44%   |
| Medion Akoya           | 1         | 0.44%   |
| Lenovo V330-15IKB      | 1         | 0.44%   |
| Lenovo IdeaCentre      | 1         | 0.44%   |
| Lenovo G50-45          | 1         | 0.44%   |
| Intel X64              | 1         | 0.44%   |
| Intel NUC7i3BNH        | 1         | 0.44%   |
| Intel H61              | 1         | 0.44%   |
| HUAWEI NBLB-WAX9N      | 1         | 0.44%   |
| HUAWEI MACHD-WXX9      | 1         | 0.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 28        | 12.33%  |
| 2011    | 22        | 9.69%   |
| 2018    | 21        | 9.25%   |
| 2019    | 20        | 8.81%   |
| 2017    | 20        | 8.81%   |
| 2010    | 20        | 8.81%   |
| 2021    | 17        | 7.49%   |
| 2016    | 17        | 7.49%   |
| 2015    | 15        | 6.61%   |
| 2012    | 15        | 6.61%   |
| 2014    | 11        | 4.85%   |
| 2009    | 8         | 3.52%   |
| 2013    | 7         | 3.08%   |
| 2008    | 3         | 1.32%   |
| 2007    | 2         | 0.88%   |
| Unknown | 1         | 0.44%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 140       | 61.67%  |
| Desktop     | 65        | 28.63%  |
| All in one  | 11        | 4.85%   |
| Convertible | 6         | 2.64%   |
| Tablet      | 4         | 1.76%   |
| Mini pc     | 1         | 0.44%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 189       | 83.26%  |
| Enabled  | 38        | 16.74%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 223       | 98.24%  |
| Yes  | 4         | 1.76%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 66        | 29.07%  |
| 16.01-24.0  | 44        | 19.38%  |
| 3.01-4.0    | 41        | 18.06%  |
| 8.01-16.0   | 37        | 16.3%   |
| 32.01-64.0  | 24        | 10.57%  |
| 1.01-2.0    | 9         | 3.96%   |
| 24.01-32.0  | 3         | 1.32%   |
| 64.01-256.0 | 2         | 0.88%   |
| 2.01-3.0    | 1         | 0.44%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 98        | 41.35%  |
| 2.01-3.0   | 68        | 28.69%  |
| 3.01-4.0   | 33        | 13.92%  |
| 4.01-8.0   | 32        | 13.5%   |
| 0.51-1.0   | 3         | 1.27%   |
| 8.01-16.0  | 2         | 0.84%   |
| 32.01-64.0 | 1         | 0.42%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 146       | 63.76%  |
| 2      | 59        | 25.76%  |
| 4      | 10        | 4.37%   |
| 3      | 10        | 4.37%   |
| 5      | 3         | 1.31%   |
| 6      | 1         | 0.44%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 157       | 69.16%  |
| Yes       | 70        | 30.84%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 186       | 81.94%  |
| No        | 41        | 18.06%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 195       | 85.9%   |
| No        | 32        | 14.1%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 167       | 73.25%  |
| No        | 61        | 26.75%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Computers | Percent |
|--------------------|-----------|---------|
| USA                | 31        | 13.6%   |
| Germany            | 21        | 9.21%   |
| India              | 14        | 6.14%   |
| Canada             | 12        | 5.26%   |
| UK                 | 11        | 4.82%   |
| Russia             | 10        | 4.39%   |
| Brazil             | 10        | 4.39%   |
| France             | 8         | 3.51%   |
| Mexico             | 7         | 3.07%   |
| Argentina          | 7         | 3.07%   |
| Netherlands        | 6         | 2.63%   |
| Indonesia          | 6         | 2.63%   |
| Spain              | 5         | 2.19%   |
| Poland             | 4         | 1.75%   |
| Italy              | 4         | 1.75%   |
| Finland            | 4         | 1.75%   |
| Denmark            | 4         | 1.75%   |
| Czechia            | 4         | 1.75%   |
| Australia          | 4         | 1.75%   |
| Vietnam            | 3         | 1.32%   |
| Sweden             | 3         | 1.32%   |
| Belgium            | 3         | 1.32%   |
| Austria            | 3         | 1.32%   |
| Turkey             | 2         | 0.88%   |
| Switzerland        | 2         | 0.88%   |
| Romania            | 2         | 0.88%   |
| Paraguay           | 2         | 0.88%   |
| Kenya              | 2         | 0.88%   |
| Guatemala          | 2         | 0.88%   |
| Estonia            | 2         | 0.88%   |
| China              | 2         | 0.88%   |
| Chile              | 2         | 0.88%   |
| Uruguay            | 1         | 0.44%   |
| Ukraine            | 1         | 0.44%   |
| Thailand           | 1         | 0.44%   |
| Sri Lanka          | 1         | 0.44%   |
| South Africa       | 1         | 0.44%   |
| Slovenia           | 1         | 0.44%   |
| Serbia             | 1         | 0.44%   |
| Philippines        | 1         | 0.44%   |
| New Zealand        | 1         | 0.44%   |
| Myanmar            | 1         | 0.44%   |
| Morocco            | 1         | 0.44%   |
| Malaysia           | 1         | 0.44%   |
| Lithuania          | 1         | 0.44%   |
| Latvia             | 1         | 0.44%   |
| Kazakhstan         | 1         | 0.44%   |
| Japan              | 1         | 0.44%   |
| Ireland            | 1         | 0.44%   |
| Hungary            | 1         | 0.44%   |
| Guyana             | 1         | 0.44%   |
| Greece             | 1         | 0.44%   |
| Dominican Republic | 1         | 0.44%   |
| Croatia            | 1         | 0.44%   |
| Costa Rica         | 1         | 0.44%   |
| Colombia           | 1         | 0.44%   |
| Belarus            | 1         | 0.44%   |
| Albania            | 1         | 0.44%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Vienna                | 3         | 1.29%   |
| Vernon                | 3         | 1.29%   |
| Paris                 | 3         | 1.29%   |
| Moscow                | 3         | 1.29%   |
| Mexico City           | 3         | 1.29%   |
| Warsaw                | 2         | 0.86%   |
| Tallinn               | 2         | 0.86%   |
| Santiago              | 2         | 0.86%   |
| Perth                 | 2         | 0.86%   |
| New Delhi             | 2         | 0.86%   |
| Nairobi               | 2         | 0.86%   |
| Mumbai                | 2         | 0.86%   |
| Montreal              | 2         | 0.86%   |
| Milan                 | 2         | 0.86%   |
| Medan                 | 2         | 0.86%   |
| Guatemala City        | 2         | 0.86%   |
| Calgary               | 2         | 0.86%   |
| Buenos Aires          | 2         | 0.86%   |
| Brussels              | 2         | 0.86%   |
| Zonguldak             | 1         | 0.43%   |
| Znojmo                | 1         | 0.43%   |
| Xicheng District      | 1         | 0.43%   |
| Wythenshawe           | 1         | 0.43%   |
| Wriezen               | 1         | 0.43%   |
| Woodbridge            | 1         | 0.43%   |
| Wigan                 | 1         | 0.43%   |
| Wattala               | 1         | 0.43%   |
| Wakefield             | 1         | 0.43%   |
| Vit??ria              | 1         | 0.43%   |
| Vilnius               | 1         | 0.43%   |
| Villeurbanne          | 1         | 0.43%   |
| Villahermosa          | 1         | 0.43%   |
| Victoria              | 1         | 0.43%   |
| Veyre-Monton          | 1         | 0.43%   |
| Vantaa                | 1         | 0.43%   |
| Vancouver             | 1         | 0.43%   |
| Valladolid            | 1         | 0.43%   |
| Ullastrell            | 1         | 0.43%   |
| Turku                 | 1         | 0.43%   |
| Tucson                | 1         | 0.43%   |
| Tolyatti              | 1         | 0.43%   |
| Toluca                | 1         | 0.43%   |
| Toledo                | 1         | 0.43%   |
| Tirupur               | 1         | 0.43%   |
| Thousand Oaks         | 1         | 0.43%   |
| Taganrog              | 1         | 0.43%   |
| Surabaya              | 1         | 0.43%   |
| Sukabumi              | 1         | 0.43%   |
| Stockholm             | 1         | 0.43%   |
| Stevenage             | 1         | 0.43%   |
| Staropyshminsk        | 1         | 0.43%   |
| Sparti                | 1         | 0.43%   |
| Sinop                 | 1         | 0.43%   |
| Simferopol            | 1         | 0.43%   |
| Seattle               | 1         | 0.43%   |
| Schwarzenbach am Wald | 1         | 0.43%   |
| S??o Pedro            | 1         | 0.43%   |
| S??o Paulo            | 1         | 0.43%   |
| Saskatoon             | 1         | 0.43%   |
| Sao Jose do Rio Preto | 1         | 0.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 54        | 66     | 17.36%  |
| Samsung Electronics       | 49        | 63     | 15.76%  |
| Seagate                   | 37        | 45     | 11.9%   |
| SanDisk                   | 22        | 25     | 7.07%   |
| Toshiba                   | 19        | 19     | 6.11%   |
| Kingston                  | 15        | 20     | 4.82%   |
| Crucial                   | 14        | 17     | 4.5%    |
| Unknown                   | 13        | 14     | 4.18%   |
| Hitachi                   | 8         | 8      | 2.57%   |
| Apple                     | 8         | 8      | 2.57%   |
| Micron Technology         | 7         | 7      | 2.25%   |
| HGST                      | 7         | 7      | 2.25%   |
| Intel                     | 6         | 6      | 1.93%   |
| SK Hynix                  | 5         | 6      | 1.61%   |
| Phison                    | 3         | 4      | 0.96%   |
| Patriot                   | 3         | 3      | 0.96%   |
| OCZ                       | 3         | 3      | 0.96%   |
| LITEON                    | 3         | 3      | 0.96%   |
| KIOXIA                    | 3         | 3      | 0.96%   |
| Gigabyte Technology       | 3         | 3      | 0.96%   |
| A-DATA Technology         | 3         | 4      | 0.96%   |
| Transcend                 | 2         | 3      | 0.64%   |
| Silicon Motion            | 2         | 2      | 0.64%   |
| Micron/Crucial Technology | 2         | 3      | 0.64%   |
| LITEONIT                  | 2         | 2      | 0.64%   |
| China                     | 2         | 2      | 0.64%   |
| USB3.1                    | 1         | 1      | 0.32%   |
| Union Memory              | 1         | 1      | 0.32%   |
| Team                      | 1         | 1      | 0.32%   |
| StoreJet                  | 1         | 1      | 0.32%   |
| Star Drive                | 1         | 1      | 0.32%   |
| OCZ-VERTEX2               | 1         | 1      | 0.32%   |
| Netac                     | 1         | 1      | 0.32%   |
| Mercury                   | 1         | 1      | 0.32%   |
| LS                        | 1         | 1      | 0.32%   |
| Kingmax                   | 1         | 1      | 0.32%   |
| HUAWEI                    | 1         | 1      | 0.32%   |
| Hewlett-Packard           | 1         | 1      | 0.32%   |
| GALAX                     | 1         | 1      | 0.32%   |
| Dogfish                   | 1         | 1      | 0.32%   |
| CLOVER                    | 1         | 1      | 0.32%   |
| Apacer                    | 1         | 1      | 0.32%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD     | 7         | 2.1%    |
| Samsung NVMe SSD Drive 512GB        | 6         | 1.8%    |
| Samsung NVMe SSD Drive 500GB        | 6         | 1.8%    |
| Sandisk NVMe SSD Drive 512GB        | 5         | 1.5%    |
| Samsung NVMe SSD Drive 256GB        | 5         | 1.5%    |
| Unknown MMC Card  128GB             | 4         | 1.2%    |
| Samsung NVMe SSD Drive 1TB          | 4         | 1.2%    |
| Intel NVMe SSD Drive 512GB          | 4         | 1.2%    |
| Crucial CT240BX500SSD1 240GB        | 4         | 1.2%    |
| WDC WD5000LPVX-22V0TT0 500GB        | 3         | 0.9%    |
| WDC WD10JPVX-22JC3T0 1TB            | 3         | 0.9%    |
| Toshiba MQ01ABD100V -63 1TB         | 3         | 0.9%    |
| Toshiba KBG30ZMS128G 128GB NVMe SSD | 3         | 0.9%    |
| Seagate ST1000LM035-1RK172 1TB      | 3         | 0.9%    |
| Samsung SSD 860 EVO 250GB           | 3         | 0.9%    |
| Kingston SA400S37480G 480GB SSD     | 3         | 0.9%    |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 2         | 0.6%    |
| WDC WD5000AAKX-003CA0 500GB         | 2         | 0.6%    |
| WDC WD10SPZX-21Z10T0 1TB            | 2         | 0.6%    |
| WDC WD10EZEX-60WN4A0 1TB            | 2         | 0.6%    |
| WDC WD10EZEX-08WN4A0 1TB            | 2         | 0.6%    |
| Unknown MMC Card  32GB              | 2         | 0.6%    |
| Unknown MMC Card  16GB              | 2         | 0.6%    |
| Toshiba MQ01ABD100 1TB              | 2         | 0.6%    |
| Toshiba MK6475GSX 640GB             | 2         | 0.6%    |
| SK Hynix NVMe SSD Drive 512GB       | 2         | 0.6%    |
| Seagate ST500LT012-1DG142 500GB     | 2         | 0.6%    |
| Seagate ST250DM000-1BD141 250GB     | 2         | 0.6%    |
| Seagate ST2000LX001-1RG174 2TB      | 2         | 0.6%    |
| Sandisk NVMe SSD Drive 500GB        | 2         | 0.6%    |
| Sandisk NVMe SSD Drive 256GB        | 2         | 0.6%    |
| Samsung SSD 850 EVO 250GB           | 2         | 0.6%    |
| Samsung SSD 840 EVO 120GB           | 2         | 0.6%    |
| KIOXIA NVMe SSD Drive 512GB         | 2         | 0.6%    |
| HGST HTS721010A9E630 1TB            | 2         | 0.6%    |
| HGST HTS541010A9E680 1TB            | 2         | 0.6%    |
| Crucial CT525MX300SSD1 528GB        | 2         | 0.6%    |
| Crucial CT250MX500SSD1 250GB        | 2         | 0.6%    |
| Crucial CT240BX200SSD1 240GB        | 2         | 0.6%    |
| Apple SSD SD128E 121GB              | 2         | 0.6%    |
| WDC WDS500G2B0A 500GB SSD           | 1         | 0.3%    |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 1         | 0.3%    |
| WDC WDS200T2B0B-00YS70 2TB SSD      | 1         | 0.3%    |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 1         | 0.3%    |
| WDC WD6401AALS-00J7B0 640GB         | 1         | 0.3%    |
| WDC WD6400BEVT-22A0RT0 640GB        | 1         | 0.3%    |
| WDC WD5000LPLX-08ZNTT0 500GB        | 1         | 0.3%    |
| WDC WD5000BPVT-75HXZT1 500GB        | 1         | 0.3%    |
| WDC WD5000BPVT-22HXZT3 500GB        | 1         | 0.3%    |
| WDC WD5000BPVT-22HXZT1 500GB        | 1         | 0.3%    |
| WDC WD5000BPVT-00HXZT1 500GB        | 1         | 0.3%    |
| WDC WD5000BPKT-75PK4T0 500GB        | 1         | 0.3%    |
| WDC WD5000AAKX-60U6AA0 500GB        | 1         | 0.3%    |
| WDC WD5000AAKX-603CA0 500GB         | 1         | 0.3%    |
| WDC WD5000AAKX-00ERMA0 500GB        | 1         | 0.3%    |
| WDC WD5000AAKX-001CA0 500GB         | 1         | 0.3%    |
| WDC WD50 00LUCT-61C26Y0 500GB       | 1         | 0.3%    |
| WDC WD40EZRZ-00GXCB0 4TB            | 1         | 0.3%    |
| WDC WD40EZAZ-00SF3B0 4TB            | 1         | 0.3%    |
| WDC WD3200BEVT-75A23T0 320GB        | 1         | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 46        | 55     | 38.02%  |
| Seagate             | 36        | 43     | 29.75%  |
| Toshiba             | 15        | 15     | 12.4%   |
| Hitachi             | 8         | 8      | 6.61%   |
| HGST                | 7         | 7      | 5.79%   |
| Samsung Electronics | 5         | 5      | 4.13%   |
| Apple               | 2         | 2      | 1.65%   |
| Unknown             | 1         | 1      | 0.83%   |
| StoreJet            | 1         | 1      | 0.83%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 19        | 24     | 17.92%  |
| Crucial             | 14        | 17     | 13.21%  |
| SanDisk             | 12        | 13     | 11.32%  |
| Kingston            | 12        | 16     | 11.32%  |
| WDC                 | 6         | 6      | 5.66%   |
| Apple               | 6         | 6      | 5.66%   |
| Patriot             | 3         | 3      | 2.83%   |
| OCZ                 | 3         | 3      | 2.83%   |
| Micron Technology   | 3         | 3      | 2.83%   |
| LITEON              | 3         | 3      | 2.83%   |
| A-DATA Technology   | 3         | 4      | 2.83%   |
| Transcend           | 2         | 3      | 1.89%   |
| SK Hynix            | 2         | 2      | 1.89%   |
| LITEONIT            | 2         | 2      | 1.89%   |
| Intel               | 2         | 2      | 1.89%   |
| China               | 2         | 2      | 1.89%   |
| Toshiba             | 1         | 1      | 0.94%   |
| Team                | 1         | 1      | 0.94%   |
| OCZ-VERTEX2         | 1         | 1      | 0.94%   |
| Netac               | 1         | 1      | 0.94%   |
| Mercury             | 1         | 1      | 0.94%   |
| LS                  | 1         | 1      | 0.94%   |
| Kingmax             | 1         | 1      | 0.94%   |
| Hewlett-Packard     | 1         | 1      | 0.94%   |
| Gigabyte Technology | 1         | 1      | 0.94%   |
| GALAX               | 1         | 1      | 0.94%   |
| Dogfish             | 1         | 1      | 0.94%   |
| Apacer              | 1         | 1      | 0.94%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 110       | 137    | 37.93%  |
| SSD     | 94        | 121    | 32.41%  |
| NVMe    | 69        | 86     | 23.79%  |
| MMC     | 11        | 12     | 3.79%   |
| Unknown | 6         | 6      | 2.07%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 176       | 255    | 66.92%  |
| NVMe | 69        | 86     | 26.24%  |
| MMC  | 11        | 12     | 4.18%   |
| SAS  | 7         | 9      | 2.66%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 130       | 171    | 63.11%  |
| 0.51-1.0   | 61        | 69     | 29.61%  |
| 1.01-2.0   | 11        | 13     | 5.34%   |
| 3.01-4.0   | 2         | 2      | 0.97%   |
| 2.01-3.0   | 2         | 3      | 0.97%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 84        | 36.68%  |
| 251-500        | 65        | 28.38%  |
| 501-1000       | 30        | 13.1%   |
| 51-100         | 14        | 6.11%   |
| 21-50          | 12        | 5.24%   |
| 1001-2000      | 10        | 4.37%   |
| 2001-3000      | 6         | 2.62%   |
| 1-20           | 5         | 2.18%   |
| More than 3000 | 3         | 1.31%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 119       | 51.97%  |
| 21-50     | 49        | 21.4%   |
| 51-100    | 27        | 11.79%  |
| 101-250   | 16        | 6.99%   |
| 251-500   | 6         | 2.62%   |
| 501-1000  | 6         | 2.62%   |
| 1001-2000 | 4         | 1.75%   |
| 2001-3000 | 2         | 0.87%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


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
| Samsung Electronics HD160JJ 160GB   | 1         | 1      | 7.14%   |
| Hitachi HTS542525K9SA00 250GB       | 1         | 1      | 7.14%   |
| Crucial CT256M550SSD1 256GB         | 1         | 1      | 7.14%   |
| Apple HDD HTS541010A9E662 1TB       | 1         | 1      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


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

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


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

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


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

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 190       | 304    | 80.85%  |
| Works    | 34        | 44     | 14.47%  |
| Malfunc  | 11        | 14     | 4.68%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 164       | 56.75%  |
| AMD                          | 37        | 12.8%   |
| Samsung Electronics          | 33        | 11.42%  |
| Sandisk                      | 17        | 5.88%   |
| Phison Electronics           | 5         | 1.73%   |
| Micron Technology            | 4         | 1.38%   |
| Toshiba America Info Systems | 3         | 1.04%   |
| SK Hynix                     | 3         | 1.04%   |
| Marvell Technology Group     | 3         | 1.04%   |
| KIOXIA                       | 3         | 1.04%   |
| Kingston Technology Company  | 3         | 1.04%   |
| Silicon Motion               | 2         | 0.69%   |
| Nvidia                       | 2         | 0.69%   |
| Micron/Crucial Technology    | 2         | 0.69%   |
| JMicron Technology           | 2         | 0.69%   |
| ASMedia Technology           | 2         | 0.69%   |
| VIA Technologies             | 1         | 0.35%   |
| Seagate Technology           | 1         | 0.35%   |
| LSI Logic / Symbios Logic    | 1         | 0.35%   |
| Broadcom / LSI               | 1         | 0.35%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 27        | 8.33%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 17        | 5.25%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 14        | 4.32%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 13        | 4.01%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 13        | 4.01%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 11        | 3.4%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 10        | 3.09%   |
| Samsung NVMe SSD Controller 980                                                         | 8         | 2.47%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 8         | 2.47%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 7         | 2.16%   |
| Intel SATA Controller [RAID mode]                                                       | 6         | 1.85%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 5         | 1.54%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5         | 1.54%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5         | 1.54%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 4         | 1.23%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 4         | 1.23%   |
| Micron Non-Volatile memory controller                                                   | 4         | 1.23%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 4         | 1.23%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 4         | 1.23%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 4         | 1.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4         | 1.23%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 4         | 1.23%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 4         | 1.23%   |
| SK Hynix Gold P31 SSD                                                                   | 3         | 0.93%   |
| Sandisk Non-Volatile memory controller                                                  | 3         | 0.93%   |
| Samsung Electronics SATA controller                                                     | 3         | 0.93%   |
| KIOXIA Non-Volatile memory controller                                                   | 3         | 0.93%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 3         | 0.93%   |
| Intel SSD 660P Series                                                                   | 3         | 0.93%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 3         | 0.93%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3         | 0.93%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 3         | 0.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 3         | 0.93%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 3         | 0.93%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 3         | 0.93%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 3         | 0.93%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 3         | 0.93%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3         | 0.93%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3         | 0.93%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 3         | 0.93%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 3         | 0.93%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 3         | 0.93%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3         | 0.93%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3         | 0.93%   |
| AMD 300 Series Chipset SATA Controller                                                  | 3         | 0.93%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 2         | 0.62%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2         | 0.62%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2         | 0.62%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2         | 0.62%   |
| Phison PS5013 E13 NVMe Controller                                                       | 2         | 0.62%   |
| Phison E12 NVMe Controller                                                              | 2         | 0.62%   |
| Kingston Company A2000 NVMe SSD                                                         | 2         | 0.62%   |
| JMicron JMB368 IDE controller                                                           | 2         | 0.62%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                         | 2         | 0.62%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2         | 0.62%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                    | 2         | 0.62%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 2         | 0.62%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 2         | 0.62%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3)  | 2         | 0.62%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2         | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 165       | 58.1%   |
| NVMe | 69        | 24.3%   |
| RAID | 25        | 8.8%    |
| IDE  | 23        | 8.1%    |
| SAS  | 1         | 0.35%   |
| SCSI | 1         | 0.35%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 182       | 80.18%  |
| AMD    | 45        | 19.82%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz           | 6         | 2.64%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 5         | 2.2%    |
| Intel Core i5-8250U CPU @ 1.60GHz           | 4         | 1.76%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 4         | 1.76%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 4         | 1.76%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 4         | 1.76%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 3         | 1.32%   |
| Intel Core i3 CPU M 350 @ 2.27GHz           | 3         | 1.32%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 3         | 1.32%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 2         | 0.88%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 2         | 0.88%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 2         | 0.88%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz          | 2         | 0.88%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 2         | 0.88%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 2         | 0.88%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 0.88%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 2         | 0.88%   |
| Intel Core i5-5250U CPU @ 1.60GHz           | 2         | 0.88%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 2         | 0.88%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 2         | 0.88%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 2         | 0.88%   |
| Intel Core i5 CPU M 560 @ 2.67GHz           | 2         | 0.88%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2         | 0.88%   |
| Intel Core i3 CPU 530 @ 2.93GHz             | 2         | 0.88%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 2         | 0.88%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 2         | 0.88%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz     | 2         | 0.88%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 2         | 0.88%   |
| AMD Ryzen 5 4500U with Radeon Graphics      | 2         | 0.88%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2         | 0.88%   |
| Intel Xeon W-11855M CPU @ 3.20GHz           | 1         | 0.44%   |
| Intel Xeon CPU X5660 @ 2.80GHz              | 1         | 0.44%   |
| Intel Xeon CPU E5520 @ 2.27GHz              | 1         | 0.44%   |
| Intel Xeon CPU E5-2689 0 @ 2.60GHz          | 1         | 0.44%   |
| Intel Xeon CPU E5-2640 0 @ 2.50GHz          | 1         | 0.44%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1         | 0.44%   |
| Intel Pentium CPU P6200 @ 2.13GHz           | 1         | 0.44%   |
| Intel Pentium CPU N4200 @ 1.10GHz           | 1         | 0.44%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 1         | 0.44%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 1         | 0.44%   |
| Intel Pentium CPU N3530 @ 2.16GHz           | 1         | 0.44%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 1         | 0.44%   |
| Intel Pentium CPU G3260 @ 3.30GHz           | 1         | 0.44%   |
| Intel Pentium CPU B960 @ 2.20GHz            | 1         | 0.44%   |
| Intel Pentium CPU B950 @ 2.10GHz            | 1         | 0.44%   |
| Intel Pentium CPU 6405U @ 2.40GHz           | 1         | 0.44%   |
| Intel Pentium 3556U @ 1.70GHz               | 1         | 0.44%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 0.44%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1         | 0.44%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 1         | 0.44%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1         | 0.44%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1         | 0.44%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 0.44%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1         | 0.44%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 0.44%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 0.44%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 1         | 0.44%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 0.44%   |
| Intel Core i7-5557U CPU @ 3.10GHz           | 1         | 0.44%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 1         | 0.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 58        | 25.55%  |
| Intel Core i7           | 42        | 18.5%   |
| Intel Core i3           | 22        | 9.69%   |
| Other                   | 15        | 6.61%   |
| Intel Celeron           | 14        | 6.17%   |
| AMD Ryzen 7             | 12        | 5.29%   |
| Intel Pentium           | 11        | 4.85%   |
| AMD Ryzen 5             | 11        | 4.85%   |
| Intel Core 2 Duo        | 7         | 3.08%   |
| Intel Xeon              | 5         | 2.2%    |
| AMD FX                  | 3         | 1.32%   |
| Intel Pentium Silver    | 2         | 0.88%   |
| Intel Pentium Dual-Core | 2         | 0.88%   |
| AMD Ryzen 9             | 2         | 0.88%   |
| AMD A8                  | 2         | 0.88%   |
| AMD A6                  | 2         | 0.88%   |
| AMD A4                  | 2         | 0.88%   |
| Intel Pentium Dual      | 1         | 0.44%   |
| Intel Core 2 Quad       | 1         | 0.44%   |
| Intel Core 2            | 1         | 0.44%   |
| Intel Celeron M         | 1         | 0.44%   |
| AMD Ryzen 7 PRO         | 1         | 0.44%   |
| AMD Ryzen 5 PRO         | 1         | 0.44%   |
| AMD Ryzen 3             | 1         | 0.44%   |
| AMD Phenom II X4        | 1         | 0.44%   |
| AMD Phenom II           | 1         | 0.44%   |
| AMD Phenom              | 1         | 0.44%   |
| AMD E1                  | 1         | 0.44%   |
| AMD C-60                | 1         | 0.44%   |
| AMD C-50                | 1         | 0.44%   |
| AMD Athlon II X4        | 1         | 0.44%   |
| AMD A10                 | 1         | 0.44%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 104       | 45.81%  |
| 4      | 73        | 32.16%  |
| 6      | 24        | 10.57%  |
| 8      | 18        | 7.93%   |
| 12     | 4         | 1.76%   |
| 1      | 3         | 1.32%   |
| 3      | 1         | 0.44%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 224       | 98.68%  |
| 2      | 3         | 1.32%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 157       | 69.16%  |
| 1      | 70        | 30.84%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 227       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x206a7    | 23        | 10%     |
| Unknown    | 18        | 7.83%   |
| 0x306c3    | 12        | 5.22%   |
| 0x306a9    | 12        | 5.22%   |
| 0x806c1    | 11        | 4.78%   |
| 0x406e3    | 10        | 4.35%   |
| 0x20655    | 7         | 3.04%   |
| 0x806ea    | 6         | 2.61%   |
| 0x40651    | 6         | 2.61%   |
| 0x306d4    | 6         | 2.61%   |
| 0x20652    | 6         | 2.61%   |
| 0x1067a    | 6         | 2.61%   |
| 0x906e9    | 5         | 2.17%   |
| 0x806e9    | 5         | 2.17%   |
| 0x08701021 | 5         | 2.17%   |
| 0x906ea    | 4         | 1.74%   |
| 0x30678    | 4         | 1.74%   |
| 0x0800820d | 4         | 1.74%   |
| 0xa0671    | 3         | 1.3%    |
| 0x806ec    | 3         | 1.3%    |
| 0x706a8    | 3         | 1.3%    |
| 0x6fb      | 3         | 1.3%    |
| 0x406c4    | 3         | 1.3%    |
| 0x08600104 | 3         | 1.3%    |
| 0xa0655    | 2         | 0.87%   |
| 0xa0653    | 2         | 0.87%   |
| 0xa0652    | 2         | 0.87%   |
| 0x806eb    | 2         | 0.87%   |
| 0x706a1    | 2         | 0.87%   |
| 0x6fd      | 2         | 0.87%   |
| 0x506e3    | 2         | 0.87%   |
| 0x406c3    | 2         | 0.87%   |
| 0x40661    | 2         | 0.87%   |
| 0x206d7    | 2         | 0.87%   |
| 0x106a5    | 2         | 0.87%   |
| 0x08701013 | 2         | 0.87%   |
| 0x08101007 | 2         | 0.87%   |
| 0x07030105 | 2         | 0.87%   |
| 0x0600611a | 2         | 0.87%   |
| 0x06000852 | 2         | 0.87%   |
| 0x906ed    | 1         | 0.43%   |
| 0x906eb    | 1         | 0.43%   |
| 0x806d1    | 1         | 0.43%   |
| 0x706e5    | 1         | 0.43%   |
| 0x6fa      | 1         | 0.43%   |
| 0x506c9    | 1         | 0.43%   |
| 0x40671    | 1         | 0.43%   |
| 0x306e4    | 1         | 0.43%   |
| 0x206c2    | 1         | 0.43%   |
| 0x106e5    | 1         | 0.43%   |
| 0x10676    | 1         | 0.43%   |
| 0x0a50000c | 1         | 0.43%   |
| 0x0a201016 | 1         | 0.43%   |
| 0x08608103 | 1         | 0.43%   |
| 0x08600106 | 1         | 0.43%   |
| 0x08600103 | 1         | 0.43%   |
| 0x08108109 | 1         | 0.43%   |
| 0x08101016 | 1         | 0.43%   |
| 0x0810100b | 1         | 0.43%   |
| 0x0800111c | 1         | 0.43%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 31        | 13.66%  |
| SandyBridge   | 28        | 12.33%  |
| Haswell       | 20        | 8.81%   |
| Westmere      | 14        | 6.17%   |
| Skylake       | 14        | 6.17%   |
| Zen 2         | 13        | 5.73%   |
| IvyBridge     | 13        | 5.73%   |
| TigerLake     | 11        | 4.85%   |
| Silvermont    | 10        | 4.41%   |
| Penryn        | 7         | 3.08%   |
| Broadwell     | 7         | 3.08%   |
| Zen+          | 6         | 2.64%   |
| Core          | 6         | 2.64%   |
| CometLake     | 6         | 2.64%   |
| Zen           | 5         | 2.2%    |
| Icelake       | 5         | 2.2%    |
| Goldmont plus | 5         | 2.2%    |
| K10           | 4         | 1.76%   |
| Zen 3         | 3         | 1.32%   |
| Piledriver    | 3         | 1.32%   |
| Nehalem       | 3         | 1.32%   |
| Excavator     | 3         | 1.32%   |
| Puma          | 2         | 0.88%   |
| Jaguar        | 2         | 0.88%   |
| Bobcat        | 2         | 0.88%   |
| Unknown       | 2         | 0.88%   |
| Goldmont      | 1         | 0.44%   |
| Bulldozer     | 1         | 0.44%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Intel            | 147       | 55.26%  |
| Nvidia           | 59        | 22.18%  |
| AMD              | 58        | 21.8%   |
| Conexant Systems | 1         | 0.38%   |
| ATI Technologies | 1         | 0.38%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 21        | 7.75%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 12        | 4.43%   |
| Intel Core Processor Integrated Graphics Controller                                      | 12        | 4.43%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 10        | 3.69%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 9         | 3.32%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 8         | 2.95%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 6         | 2.21%   |
| Intel UHD Graphics 620                                                                   | 6         | 2.21%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 2.21%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 2.21%   |
| AMD Renoir                                                                               | 6         | 2.21%   |
| Intel HD Graphics 620                                                                    | 5         | 1.85%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1.48%   |
| Intel HD Graphics 630                                                                    | 4         | 1.48%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 1.48%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 4         | 1.48%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 4         | 1.48%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 1.11%   |
| Intel HD Graphics 5500                                                                   | 3         | 1.11%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.11%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.11%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.74%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 2         | 0.74%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 0.74%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.74%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 2         | 0.74%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 2         | 0.74%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 2         | 0.74%   |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                                              | 2         | 0.74%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 2         | 0.74%   |
| Nvidia GA102 [GeForce RTX 3080]                                                          | 2         | 0.74%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 0.74%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 0.74%   |
| Intel Tiger Lake UHD Graphics                                                            | 2         | 0.74%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.74%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 0.74%   |
| Intel HD Graphics 6000                                                                   | 2         | 0.74%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 0.74%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 0.74%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 0.74%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 0.74%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 0.74%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 2         | 0.74%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 2         | 0.74%   |
| AMD RS780D [Radeon HD 3300]                                                              | 2         | 0.74%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 0.74%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                                           | 2         | 0.74%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 0.74%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 2         | 0.74%   |
| AMD Cezanne                                                                              | 2         | 0.74%   |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                                     | 2         | 0.74%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.37%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 1         | 0.37%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 0.37%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 1         | 0.37%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 1         | 0.37%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.37%   |
| Nvidia GP108BM [GeForce MX250]                                                           | 1         | 0.37%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 0.37%   |
| Nvidia GP107M [GeForce MX350]                                                            | 1         | 0.37%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| 1 x Intel                      | 112       | 49.34%  |
| 1 x AMD                        | 46        | 20.26%  |
| 1 x Nvidia                     | 29        | 12.78%  |
| Intel + Nvidia                 | 28        | 12.33%  |
| Intel + AMD                    | 6         | 2.64%   |
| 2 x AMD                        | 3         | 1.32%   |
| AMD + Nvidia                   | 2         | 0.88%   |
| 2 x AMD + 1 x Conexant Systems | 1         | 0.44%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 199       | 86.52%  |
| Proprietary | 27        | 11.74%  |
| Unknown     | 4         | 1.74%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 133       | 58.08%  |
| 1.01-2.0   | 25        | 10.92%  |
| 0.01-0.5   | 19        | 8.3%    |
| 0.51-1.0   | 18        | 7.86%   |
| 3.01-4.0   | 15        | 6.55%   |
| 7.01-8.0   | 13        | 5.68%   |
| 5.01-6.0   | 2         | 0.87%   |
| 2.01-3.0   | 2         | 0.87%   |
| 8.01-16.0  | 2         | 0.87%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 30        | 12.15%  |
| Samsung Electronics     | 27        | 10.93%  |
| LG Display              | 24        | 9.72%   |
| Chimei Innolux          | 24        | 9.72%   |
| BOE                     | 20        | 8.1%    |
| Apple                   | 15        | 6.07%   |
| Hewlett-Packard         | 13        | 5.26%   |
| Goldstar                | 10        | 4.05%   |
| Lenovo                  | 9         | 3.64%   |
| Dell                    | 9         | 3.64%   |
| BenQ                    | 7         | 2.83%   |
| Acer                    | 7         | 2.83%   |
| AOC                     | 6         | 2.43%   |
| Sharp                   | 5         | 2.02%   |
| Ancor Communications    | 5         | 2.02%   |
| Chi Mei Optoelectronics | 4         | 1.62%   |
| Vizio                   | 3         | 1.21%   |
| ViewSonic               | 3         | 1.21%   |
| CPT                     | 3         | 1.21%   |
| MSI                     | 2         | 0.81%   |
| LG Electronics          | 2         | 0.81%   |
| CSO                     | 2         | 0.81%   |
| Toshiba                 | 1         | 0.4%    |
| TBD                     | 1         | 0.4%    |
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
| Unknown                 | 1         | 0.4%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 5         | 1.97%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 4         | 1.57%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 2         | 0.79%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 2         | 0.79%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 2         | 0.79%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 2         | 0.79%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 2         | 0.79%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch | 2         | 0.79%   |
| AU Optronics LCD Monitor AUO413D 1920x1080 309x173mm 13.9-inch           | 2         | 0.79%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 2         | 0.79%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 2         | 0.79%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 2         | 0.79%   |
| Apple Color LCD APPA014 2560x1600 286x179mm 13.3-inch                    | 2         | 0.79%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                     | 2         | 0.79%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                     | 2         | 0.79%   |
| Apple Color LCD APP9CA4 1440x900 331x207mm 15.4-inch                     | 2         | 0.79%   |
| AOC 2369M AOC2369 1920x1080 509x286mm 23.0-inch                          | 2         | 0.79%   |
| AOC 22V2WG5 AOC2202 1920x1080 476x268mm 21.5-inch                        | 2         | 0.79%   |
| Vizio L37 HD VIZ1300 1366x768 820x460mm 37.0-inch                        | 1         | 0.39%   |
| Vizio E321VL VIZ0083 1366x768 700x400mm 31.7-inch                        | 1         | 0.39%   |
| Vizio E190VA VIZ0067 1360x768 410x230mm 18.5-inch                        | 1         | 0.39%   |
| ViewSonic VA2445 SERIES VSC712E 1920x1080 521x293mm 23.5-inch            | 1         | 0.39%   |
| ViewSonic VA2055 Series VSC3C31 1920x1080 435x239mm 19.5-inch            | 1         | 0.39%   |
| ViewSonic LCD Monitor VSC732E 1920x1080 520x290mm 23.4-inch              | 1         | 0.39%   |
| Toshiba TV TSB0206 1920x1080 886x498mm 40.0-inch                         | 1         | 0.39%   |
| TBD HDMI TBD3148 1600x900 344x193mm 15.5-inch                            | 1         | 0.39%   |
| SKY TV-monitor SKY0001 1920x1080 697x392mm 31.5-inch                     | 1         | 0.39%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch                  | 1         | 0.39%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                  | 1         | 0.39%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                  | 1         | 0.39%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                  | 1         | 0.39%   |
| Sharp LCD Monitor SHP1420 1920x1080 290x170mm 13.2-inch                  | 1         | 0.39%   |
| Seiko/Epson LCD Monitor 1920x1080                                        | 1         | 0.39%   |
| Samsung Electronics U32J59x SAM0F33 1920x2160 700x390mm 31.5-inch        | 1         | 0.39%   |
| Samsung Electronics U28H75x SAM0E00 3840x2160 607x345mm 27.5-inch        | 1         | 0.39%   |
| Samsung Electronics U28H75x SAM0DFF 3840x2160 608x345mm 27.5-inch        | 1         | 0.39%   |
| Samsung Electronics SyncMaster SAM0428 1680x1050 459x296mm 21.5-inch     | 1         | 0.39%   |
| Samsung Electronics S27H85x SAM0E0E 2560x1440 597x336mm 27.0-inch        | 1         | 0.39%   |
| Samsung Electronics S27D850 SAM0BC8 2560x1440 598x336mm 27.0-inch        | 1         | 0.39%   |
| Samsung Electronics S24D332 SAM0F5E 1920x1080 531x299mm 24.0-inch        | 1         | 0.39%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch        | 1         | 0.39%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch        | 1         | 0.39%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch        | 1         | 0.39%   |
| Samsung Electronics S22C200 SAM09B6 1920x1080 477x268mm 21.5-inch        | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC5842 1366x768 309x174mm 14.0-inch     | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC364D 1600x900 382x214mm 17.2-inch     | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC3542 2160x1440 254x169mm 12.0-inch    | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 344x194mm 15.5-inch     | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch     | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch     | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 344x194mm 15.5-inch     | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SDC4E42 1366x768 309x174mm 14.0-inch     | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SDC3853 2736x1824 260x173mm 12.3-inch    | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SAM705B 1920x1080 1210x680mm 54.6-inch   | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SAM0B30 1920x1080 885x498mm 40.0-inch    | 1         | 0.39%   |
| Samsung Electronics LCD Monitor S24F350 5760x1080                        | 1         | 0.39%   |
| Samsung Electronics LCD Monitor S24F350                                  | 1         | 0.39%   |
| Samsung Electronics LCD Monitor C24F390 1920x1080                        | 1         | 0.39%   |
| Samsung Electronics C49J89x SAM0F21 3840x1080 1196x336mm 48.9-inch       | 1         | 0.39%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 92        | 39.15%  |
| 1366x768 (WXGA)    | 54        | 22.98%  |
| 1600x900 (HD+)     | 14        | 5.96%   |
| 3840x2160 (4K)     | 13        | 5.53%   |
| 2560x1440 (QHD)    | 10        | 4.26%   |
| 1280x800 (WXGA)    | 9         | 3.83%   |
| 1440x900 (WXGA+)   | 8         | 3.4%    |
| 2560x1600          | 5         | 2.13%   |
| 1920x1200 (WUXGA)  | 5         | 2.13%   |
| 1680x1050 (WSXGA+) | 5         | 2.13%   |
| Unknown            | 4         | 1.7%    |
| 3840x1080          | 3         | 1.28%   |
| 2560x1080          | 3         | 1.28%   |
| 5760x1080          | 1         | 0.43%   |
| 5120x1440          | 1         | 0.43%   |
| 4480x1440          | 1         | 0.43%   |
| 3840x2400          | 1         | 0.43%   |
| 3440x1440          | 1         | 0.43%   |
| 3000x2000          | 1         | 0.43%   |
| 2880x1800          | 1         | 0.43%   |
| 2736x1824          | 1         | 0.43%   |
| 2160x1440          | 1         | 0.43%   |
| 1280x1024 (SXGA)   | 1         | 0.43%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 67        | 27.46%  |
| 13      | 31        | 12.7%   |
| 27      | 20        | 8.2%    |
| 14      | 19        | 7.79%   |
| 21      | 16        | 6.56%   |
| 23      | 13        | 5.33%   |
| 17      | 12        | 4.92%   |
| Unknown | 12        | 4.92%   |
| 12      | 8         | 3.28%   |
| 24      | 7         | 2.87%   |
| 11      | 6         | 2.46%   |
| 20      | 4         | 1.64%   |
| 19      | 4         | 1.64%   |
| 31      | 3         | 1.23%   |
| 54      | 2         | 0.82%   |
| 49      | 2         | 0.82%   |
| 40      | 2         | 0.82%   |
| 34      | 2         | 0.82%   |
| 10      | 2         | 0.82%   |
| 74      | 1         | 0.41%   |
| 72      | 1         | 0.41%   |
| 37      | 1         | 0.41%   |
| 33      | 1         | 0.41%   |
| 32      | 1         | 0.41%   |
| 29      | 1         | 0.41%   |
| 28      | 1         | 0.41%   |
| 26      | 1         | 0.41%   |
| 25      | 1         | 0.41%   |
| 22      | 1         | 0.41%   |
| 18      | 1         | 0.41%   |
| 16      | 1         | 0.41%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 100       | 41.84%  |
| 501-600     | 33        | 13.81%  |
| 201-300     | 33        | 13.81%  |
| 401-500     | 25        | 10.46%  |
| 351-400     | 13        | 5.44%   |
| Unknown     | 12        | 5.02%   |
| 601-700     | 10        | 4.18%   |
| 701-800     | 4         | 1.67%   |
| 1001-1500   | 4         | 1.67%   |
| 801-900     | 3         | 1.26%   |
| 1501-2000   | 2         | 0.84%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 167       | 75.23%  |
| 16/10   | 31        | 13.96%  |
| Unknown | 12        | 5.41%   |
| 3/2     | 5         | 2.25%   |
| 21/9    | 4         | 1.8%    |
| 32/9    | 2         | 0.9%    |
| 5/4     | 1         | 0.45%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 67        | 27.57%  |
| 81-90          | 37        | 15.23%  |
| 201-250        | 28        | 11.52%  |
| 301-350        | 22        | 9.05%   |
| 151-200        | 14        | 5.76%   |
| 71-80          | 13        | 5.35%   |
| Unknown        | 12        | 4.94%   |
| 61-70          | 8         | 3.29%   |
| 121-130        | 8         | 3.29%   |
| 351-500        | 7         | 2.88%   |
| 51-60          | 6         | 2.47%   |
| 501-1000       | 5         | 2.06%   |
| More than 1000 | 4         | 1.65%   |
| 251-300        | 4         | 1.65%   |
| 131-140        | 3         | 1.23%   |
| 41-50          | 2         | 0.82%   |
| 141-150        | 2         | 0.82%   |
| 111-120        | 1         | 0.41%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 73        | 31.2%   |
| 101-120       | 72        | 30.77%  |
| 51-100        | 54        | 23.08%  |
| 161-240       | 13        | 5.56%   |
| Unknown       | 12        | 5.13%   |
| More than 240 | 5         | 2.14%   |
| 1-50          | 5         | 2.14%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 193       | 84.65%  |
| 2     | 23        | 10.09%  |
| 3     | 7         | 3.07%   |
| 0     | 5         | 2.19%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 129       | 36.34%  |
| Intel                             | 97        | 27.32%  |
| Qualcomm Atheros                  | 34        | 9.58%   |
| Broadcom                          | 33        | 9.3%    |
| TP-Link                           | 10        | 2.82%   |
| Broadcom Limited                  | 8         | 2.25%   |
| Ralink Technology                 | 6         | 1.69%   |
| Xiaomi                            | 4         | 1.13%   |
| Ralink                            | 4         | 1.13%   |
| Marvell Technology Group          | 4         | 1.13%   |
| Sierra Wireless                   | 3         | 0.85%   |
| MediaTek                          | 3         | 0.85%   |
| Samsung Electronics               | 2         | 0.56%   |
| Hewlett-Packard                   | 2         | 0.56%   |
| Qualcomm                          | 1         | 0.28%   |
| OPPO Electronics                  | 1         | 0.28%   |
| Nvidia                            | 1         | 0.28%   |
| NetGear                           | 1         | 0.28%   |
| NEC Computers                     | 1         | 0.28%   |
| Mercucys                          | 1         | 0.28%   |
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

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 82        | 19.66%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 17        | 4.08%   |
| Intel Wi-Fi 6 AX200                                               | 12        | 2.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 2.4%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 8         | 1.92%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 7         | 1.68%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 7         | 1.68%   |
| Intel Wi-Fi 6 AX201                                               | 7         | 1.68%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 6         | 1.44%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 6         | 1.44%   |
| Intel Wireless 8260                                               | 6         | 1.44%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 6         | 1.44%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 1.2%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 1.2%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 1.2%    |
| Intel Wireless 7265                                               | 5         | 1.2%    |
| Intel I211 Gigabit Network Connection                             | 5         | 1.2%    |
| Intel 82577LM Gigabit Network Connection                          | 5         | 1.2%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 5         | 1.2%    |
| TP-Link 802.11ac WLAN Adapter                                     | 4         | 0.96%   |
| Ralink MT7601U Wireless Adapter                                   | 4         | 0.96%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 0.96%   |
| Intel Wireless 8265 / 8275                                        | 4         | 0.96%   |
| Intel Wireless 7260                                               | 4         | 0.96%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 0.96%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 0.96%   |
| Broadcom BCM43142 802.11b/g/n                                     | 4         | 0.96%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 4         | 0.96%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.72%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 3         | 0.72%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 3         | 0.72%   |
| Intel Wireless 3160                                               | 3         | 0.72%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 3         | 0.72%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.72%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 3         | 0.72%   |
| Intel Centrino Wireless-N 2230                                    | 3         | 0.72%   |
| Intel 82574L Gigabit Network Connection                           | 3         | 0.72%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 3         | 0.72%   |
| TP-Link 802.11ac NIC                                              | 2         | 0.48%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 0.48%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 2         | 0.48%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 2         | 0.48%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.48%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 2         | 0.48%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.48%   |
| MediaTek Infinix HOT 10T                                          | 2         | 0.48%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                 | 2         | 0.48%   |
| Intel Wireless 3165                                               | 2         | 0.48%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 2         | 0.48%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.48%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.48%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.48%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.48%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 0.48%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 0.48%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 2         | 0.48%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 0.48%   |
| Intel Centrino Advanced-N 6235                                    | 2         | 0.48%   |
| Intel Centrino Advanced-N 6200                                    | 2         | 0.48%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 79        | 37.26%  |
| Realtek Semiconductor    | 39        | 18.4%   |
| Broadcom                 | 29        | 13.68%  |
| Qualcomm Atheros         | 28        | 13.21%  |
| TP-Link                  | 10        | 4.72%   |
| Ralink Technology        | 6         | 2.83%   |
| Broadcom Limited         | 6         | 2.83%   |
| Ralink                   | 4         | 1.89%   |
| Sierra Wireless          | 3         | 1.42%   |
| Marvell Technology Group | 2         | 0.94%   |
| NetGear                  | 1         | 0.47%   |
| Mercucys                 | 1         | 0.47%   |
| MEDIATEK                 | 1         | 0.47%   |
| Edimax Technology        | 1         | 0.47%   |
| D-Link                   | 1         | 0.47%   |
| ASUSTek Computer         | 1         | 0.47%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 12        | 5.66%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 8         | 3.77%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 7         | 3.3%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 7         | 3.3%    |
| Intel Wi-Fi 6 AX201                                            | 7         | 3.3%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 6         | 2.83%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 6         | 2.83%   |
| Intel Wireless 8260                                            | 6         | 2.83%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 6         | 2.83%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 2.36%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 5         | 2.36%   |
| Intel Wireless 7265                                            | 5         | 2.36%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 5         | 2.36%   |
| TP-Link 802.11ac WLAN Adapter                                  | 4         | 1.89%   |
| Ralink MT7601U Wireless Adapter                                | 4         | 1.89%   |
| Intel Wireless 8265 / 8275                                     | 4         | 1.89%   |
| Intel Wireless 7260                                            | 4         | 1.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 1.89%   |
| Broadcom BCM43142 802.11b/g/n                                  | 4         | 1.89%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 4         | 1.89%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 3         | 1.42%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 3         | 1.42%   |
| Intel Wireless 3160                                            | 3         | 1.42%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 3         | 1.42%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 3         | 1.42%   |
| Intel Centrino Wireless-N 2230                                 | 3         | 1.42%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 3         | 1.42%   |
| TP-Link 802.11ac NIC                                           | 2         | 0.94%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 2         | 0.94%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 2         | 0.94%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 2         | 0.94%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 2         | 0.94%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 0.94%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless              | 2         | 0.94%   |
| Intel Wireless 3165                                            | 2         | 0.94%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 2         | 0.94%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 0.94%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 2         | 0.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 0.94%   |
| Intel Centrino Advanced-N 6235                                 | 2         | 0.94%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 0.94%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 2         | 0.94%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 2         | 0.94%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 2         | 0.94%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                          | 1         | 0.47%   |
| Sierra Wireless MC8305 Modem                                   | 1         | 0.47%   |
| Sierra Wireless EM7455                                         | 1         | 0.47%   |
| Sierra Wireless EM7305 Modem                                   | 1         | 0.47%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 0.47%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 1         | 0.47%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 1         | 0.47%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1         | 0.47%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 0.47%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 0.47%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.47%   |
| Realtek RTL8187 Wireless Adapter                               | 1         | 0.47%   |
| Realtek 802.11ac NIC                                           | 1         | 0.47%   |
| Ralink RT5370 Wireless Adapter                                 | 1         | 0.47%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1         | 0.47%   |
| Ralink RT5592 PCIe Wireless Network Adapter                    | 1         | 0.47%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 108       | 54.82%  |
| Intel                    | 44        | 22.34%  |
| Broadcom                 | 14        | 7.11%   |
| Qualcomm Atheros         | 11        | 5.58%   |
| Xiaomi                   | 4         | 2.03%   |
| Samsung Electronics      | 2         | 1.02%   |
| MediaTek                 | 2         | 1.02%   |
| Marvell Technology Group | 2         | 1.02%   |
| Broadcom Limited         | 2         | 1.02%   |
| Qualcomm                 | 1         | 0.51%   |
| OPPO Electronics         | 1         | 0.51%   |
| Nvidia                   | 1         | 0.51%   |
| Linksys                  | 1         | 0.51%   |
| Google                   | 1         | 0.51%   |
| DisplayLink              | 1         | 0.51%   |
| Attansic Technology      | 1         | 0.51%   |
| ASIX Electronics         | 1         | 0.51%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 82        | 41%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 17        | 8.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 5%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 2.5%    |
| Intel I211 Gigabit Network Connection                             | 5         | 2.5%    |
| Intel 82577LM Gigabit Network Connection                          | 5         | 2.5%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 2%      |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 2%      |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 1.5%    |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.5%    |
| Intel 82574L Gigabit Network Connection                           | 3         | 1.5%    |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 1%      |
| MediaTek Infinix HOT 10T                                          | 2         | 1%      |
| Intel Ethernet Connection I219-V                                  | 2         | 1%      |
| Intel Ethernet Connection I219-LM                                 | 2         | 1%      |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1%      |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1%      |
| Intel Ethernet Connection (2) I219-V                              | 2         | 1%      |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 1%      |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 2         | 1%      |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 2         | 1%      |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 1%      |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.5%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.5%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.5%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.5%    |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.5%    |
| Qualcomm U673C                                                    | 1         | 0.5%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.5%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.5%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.5%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.5%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.5%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.5%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.5%    |
| OPPO RMX3381                                                      | 1         | 0.5%    |
| Nvidia MCP77 Ethernet                                             | 1         | 0.5%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.5%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 0.5%    |
| Linksys Gigabit Ethernet Adapter                                  | 1         | 0.5%    |
| Intel PRO/100 VE Network Connection                               | 1         | 0.5%    |
| Intel Ethernet Controller I225-V                                  | 1         | 0.5%    |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.5%    |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.5%    |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.5%    |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.5%    |
| Intel Ethernet Connection (2) I218-V                              | 1         | 0.5%    |
| Intel Ethernet Connection (14) I219-V                             | 1         | 0.5%    |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.5%    |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.5%    |
| Google Nexus/Pixel Device (tether)                                | 1         | 0.5%    |
| DisplayLink USB3.0 5K Graphic Docking                             | 1         | 0.5%    |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 0.5%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 0.5%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.5%    |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1         | 0.5%    |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 1         | 0.5%    |
| Attansic AR8152 v2.0 Fast Ethernet                                | 1         | 0.5%    |
| ASIX AX88772B                                                     | 1         | 0.5%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 195       | 50.52%  |
| Ethernet | 186       | 48.19%  |
| Modem    | 4         | 1.04%   |
| Unknown  | 1         | 0.26%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 176       | 51.16%  |
| Ethernet | 168       | 48.84%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 131       | 57.71%  |
| 1     | 92        | 40.53%  |
| 3     | 3         | 1.32%   |
| 0     | 1         | 0.44%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 168       | 73.68%  |
| Yes  | 60        | 26.32%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 66        | 39.52%  |
| Realtek Semiconductor           | 23        | 13.77%  |
| Apple                           | 17        | 10.18%  |
| Qualcomm Atheros Communications | 15        | 8.98%   |
| Broadcom                        | 13        | 7.78%   |
| Cambridge Silicon Radio         | 9         | 5.39%   |
| Lite-On Technology              | 5         | 2.99%   |
| Foxconn / Hon Hai               | 4         | 2.4%    |
| IMC Networks                    | 3         | 1.8%    |
| Ralink                          | 2         | 1.2%    |
| Marvell Semiconductor           | 2         | 1.2%    |
| Dell                            | 2         | 1.2%    |
| Toshiba                         | 1         | 0.6%    |
| Realtek                         | 1         | 0.6%    |
| Qcom                            | 1         | 0.6%    |
| Hewlett-Packard                 | 1         | 0.6%    |
| Belkin Components               | 1         | 0.6%    |
| ASUSTek Computer                | 1         | 0.6%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                              | 40        | 23.95%  |
| Realtek Bluetooth Radio                             | 13        | 7.78%   |
| Realtek  Bluetooth 4.2 Adapter                      | 9         | 5.39%   |
| Intel Bluetooth wireless interface                  | 9         | 5.39%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 9         | 5.39%   |
| Apple Bluetooth USB Host Controller                 | 8         | 4.79%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 7         | 4.19%   |
| Apple Bluetooth Host Controller                     | 7         | 4.19%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 6         | 3.59%   |
| Qualcomm Atheros  Bluetooth Device                  | 5         | 2.99%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 5         | 2.99%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 3         | 1.8%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 1.8%    |
| Ralink RT3290 Bluetooth                             | 2         | 1.2%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 1.2%    |
| Marvell Bluetooth and Wireless LAN Composite Device | 2         | 1.2%    |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 1.2%    |
| IMC Networks Bluetooth Radio                        | 2         | 1.2%    |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 1.2%    |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 2         | 1.2%    |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 1.2%    |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.6%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.6%    |
| Realtek Bluetooth Radio                             | 1         | 0.6%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.6%    |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.6%    |
| Qcom Broadcom Bluetooth USB                         | 1         | 0.6%    |
| Lite-On Wireless_Device                             | 1         | 0.6%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 0.6%    |
| Lite-On Qualcomm Atheros Bluetooth                  | 1         | 0.6%    |
| Lite-On Bluetooth Device                            | 1         | 0.6%    |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.6%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.6%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.6%    |
| Intel AX210 Bluetooth                               | 1         | 0.6%    |
| IMC Networks BCM20702A0                             | 1         | 0.6%    |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 0.6%    |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 0.6%    |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 0.6%    |
| Dell DW375 Bluetooth Module                         | 1         | 0.6%    |
| Dell Broadcom BCM20702A0 Bluetooth                  | 1         | 0.6%    |
| Broadcom HP Portable Valentine                      | 1         | 0.6%    |
| Broadcom Bluetooth 3.0 Dongle                       | 1         | 0.6%    |
| Broadcom BCM20702A0                                 | 1         | 0.6%    |
| Belkin Components Bluetooth Mini Dongle             | 1         | 0.6%    |
| ASUS Bluetooth Radio                                | 1         | 0.6%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 0.6%    |
| Apple Bluetooth HCI                                 | 1         | 0.6%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 179       | 58.31%  |
| AMD                                  | 59        | 19.22%  |
| Nvidia                               | 41        | 13.36%  |
| C-Media Electronics                  | 7         | 2.28%   |
| Logitech                             | 3         | 0.98%   |
| Generalplus Technology               | 3         | 0.98%   |
| Creative Labs                        | 3         | 0.98%   |
| JMTek                                | 2         | 0.65%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.33%   |
| TEAC                                 | 1         | 0.33%   |
| Razer USA                            | 1         | 0.33%   |
| HECATE G2 GAMING HEADSET             | 1         | 0.33%   |
| GN Netcom                            | 1         | 0.33%   |
| Focusrite-Novation                   | 1         | 0.33%   |
| Creative Technology                  | 1         | 0.33%   |
| Corsair                              | 1         | 0.33%   |
| ATI Technologies                     | 1         | 0.33%   |
| ASUSTek Computer                     | 1         | 0.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 24        | 6.54%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 23        | 6.27%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 15        | 4.09%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 14        | 3.81%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 14        | 3.81%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 13        | 3.54%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 11        | 3%      |
| AMD Renoir Radeon High Definition Audio Controller                                                | 9         | 2.45%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 8         | 2.18%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 8         | 2.18%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 8         | 2.18%   |
| Intel Cannon Lake PCH cAVS                                                                        | 7         | 1.91%   |
| Intel Broadwell-U Audio Controller                                                                | 7         | 1.91%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6         | 1.63%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 1.63%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 1.63%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 6         | 1.63%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 1.63%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 1.63%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 5         | 1.36%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 5         | 1.36%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 1.36%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 1.36%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 1.36%   |
| AMD FCH Azalia Controller                                                                         | 5         | 1.36%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 4         | 1.09%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 1.09%   |
| Intel CM238 HD Audio Controller                                                                   | 4         | 1.09%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 1.09%   |
| Intel 200 Series PCH HD Audio                                                                     | 4         | 1.09%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 4         | 1.09%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 4         | 1.09%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 0.82%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 3         | 0.82%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.82%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 0.82%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 0.82%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 3         | 0.82%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3         | 0.82%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 0.82%   |
| Generalplus Technology Usb Audio Device                                                           | 3         | 0.82%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 3         | 0.82%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 0.82%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3         | 0.82%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 2         | 0.54%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 2         | 0.54%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.54%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 2         | 0.54%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 0.54%   |
| Intel Crystal Well HD Audio Controller                                                            | 2         | 0.54%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 0.54%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 0.54%   |
| Creative Labs CA0108/CA10300 [Sound Blaster Audigy Series]                                        | 2         | 0.54%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 0.54%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                                        | 2         | 0.54%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                                            | 2         | 0.54%   |
| Thesycon Systemsoftware & Consulting E30                                                          | 1         | 0.27%   |
| TEAC TASCAM iXR                                                                                   | 1         | 0.27%   |
| Razer USA Razer USB Audio Controller                                                              | 1         | 0.27%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.27%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 19        | 24.68%  |
| SK Hynix            | 14        | 18.18%  |
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

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 3         | 3.75%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s      | 2         | 2.5%    |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s    | 2         | 2.5%    |
| Unknown RAM Module 4096MB Chip DDR4 2133MT/s                | 1         | 1.25%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                 | 1         | 1.25%   |
| Unknown RAM Module 1024MB SODIMM LPDDR4 2400MT/s            | 1         | 1.25%   |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s          | 1         | 1.25%   |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM 1066MT/s           | 1         | 1.25%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                | 1         | 1.25%   |
| SK Hynix RAM Module 4096MB SODIMM DDR3 1867MT/s             | 1         | 1.25%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 1.25%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s   | 1         | 1.25%   |
| SK Hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s      | 1         | 1.25%   |
| SK Hynix RAM HMT31GR7BFR4C-H9 8GB DIMM DDR3 1333MT/s        | 1         | 1.25%   |
| SK Hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s     | 1         | 1.25%   |
| SK Hynix RAM HMA851S6DJR6N-XN 4096MB SODIMM DDR4 3200MT/s   | 1         | 1.25%   |
| SK Hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s     | 1         | 1.25%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s      | 1         | 1.25%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s      | 1         | 1.25%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s   | 1         | 1.25%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s              | 1         | 1.25%   |
| Samsung RAM Module 8192MB DIMM DDR4 2666MT/s                | 1         | 1.25%   |
| Samsung RAM M471B5773DH0-CK0 2048MB SODIMM DDR3 1600MT/s    | 1         | 1.25%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s       | 1         | 1.25%   |
| Samsung RAM M471B5673FH0-CF8 2048MB SODIMM 1067MT/s         | 1         | 1.25%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s       | 1         | 1.25%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s       | 1         | 1.25%   |
| Samsung RAM M471B2873FHS-CF8 1GB SODIMM DDR3 1067MT/s       | 1         | 1.25%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s    | 1         | 1.25%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s      | 1         | 1.25%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s      | 1         | 1.25%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s | 1         | 1.25%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2400MT/s       | 1         | 1.25%   |
| Samsung RAM M4 70T5663EH3-CF7 2GB SODIMM DDR2 800MT/s       | 1         | 1.25%   |
| Samsung RAM M378A1K43CB2-CTD 8192MB DIMM DDR4 3200MT/s      | 1         | 1.25%   |
| Ramaxel RAM RMT3170EF68F9W1600 4GB SODIMM DDR3 1600MT/s     | 1         | 1.25%   |
| Ramaxel RAM RMSA3310NA86H9F-2666 4GB SODIMM DDR4 2667MT/s   | 1         | 1.25%   |
| Qimonda RAM 64T256020EDL2.5C2 2048MB SODIMM DDR2 2048MT/s   | 1         | 1.25%   |
| Neo Forza RAM NMUD380D81-1600D 8GB DIMM DDR3 1333MT/s       | 1         | 1.25%   |
| Nanya RAM Module 4GB DIMM DDR3 1333MT/s                     | 1         | 1.25%   |
| Micron RAM MT41K256M16LY 2GB SODIMM DDR3 1600MT/s           | 1         | 1.25%   |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s               | 1         | 1.25%   |
| Micron RAM Module 2048MB SODIMM DDR3 1600MT/s               | 1         | 1.25%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s    | 1         | 1.25%   |
| Micron RAM 8ATF1G64HZ-2G6H1 8192MB SODIMM DDR4 2667MT/s     | 1         | 1.25%   |
| Micron RAM 53E1G32D4NQ 2048MB Row Of Chips LPDDR4 4267MT/s  | 1         | 1.25%   |
| Micron RAM 4ATF51264HZ-2G6E3 4096MB SODIMM DDR4 2667MT/s    | 1         | 1.25%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s        | 1         | 1.25%   |
| Micron RAM 16JSF25664HZ-1G4F1 2GB SODIMM DDR3 1334MT/s      | 1         | 1.25%   |
| Micron RAM 16ATF2G64HZ-3G2J1 16GB SODIMM DDR4 3200MT/s      | 1         | 1.25%   |
| Kllisre RAM KRE-D3S1600M/8G 8192MB SODIMM DDR3 1600MT/s     | 1         | 1.25%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s         | 1         | 1.25%   |
| Kingston RAM KHX2666C15S4/8G 8192MB SODIMM DDR4 2667MT/s    | 1         | 1.25%   |
| Kingston RAM KHX1866C10D3/4G 4096MB DIMM DDR3 1867MT/s      | 1         | 1.25%   |
| Kingston RAM HP687515-H66-MCN 4096MB SODIMM DDR3 1600MT/s   | 1         | 1.25%   |
| Kingston RAM HP16D3LS1KBG/8G 8192MB SODIMM DDR3 1600MT/s    | 1         | 1.25%   |
| Kingston RAM ACR16D3LS1KFG/8G 8GB SODIMM DDR3 1600MT/s      | 1         | 1.25%   |
| Kingston RAM 99U5471-052.A 8GB DIMM DDR3 1333MT/s           | 1         | 1.25%   |
| Kingston RAM 99U5458-001.A00LF 2048MB DIMM DDR3 1600MT/s    | 1         | 1.25%   |
| Kingston RAM 99U5403-159.A01LF 8192MB DIMM DDR3 1333MT/s    | 1         | 1.25%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


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

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 45        | 72.58%  |
| DIMM         | 13        | 20.97%  |
| Row Of Chips | 2         | 3.23%   |
| Chip         | 2         | 3.23%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


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

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 18        | 26.47%  |
| 3200  | 12        | 17.65%  |
| 2667  | 11        | 16.18%  |
| 2400  | 4         | 5.88%   |
| 2133  | 4         | 5.88%   |
| 1333  | 4         | 5.88%   |
| 3600  | 2         | 2.94%   |
| 1867  | 2         | 2.94%   |
| 4267  | 1         | 1.47%   |
| 4199  | 1         | 1.47%   |
| 3007  | 1         | 1.47%   |
| 3000  | 1         | 1.47%   |
| 2666  | 1         | 1.47%   |
| 2048  | 1         | 1.47%   |
| 1800  | 1         | 1.47%   |
| 1334  | 1         | 1.47%   |
| 1067  | 1         | 1.47%   |
| 1066  | 1         | 1.47%   |
| 800   | 1         | 1.47%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 2         | 50%     |
| Brother Industries | 2         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


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

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 39        | 25%     |
| Microdia                               | 14        | 8.97%   |
| Realtek Semiconductor                  | 13        | 8.33%   |
| Apple                                  | 13        | 8.33%   |
| Acer                                   | 10        | 6.41%   |
| Quanta                                 | 9         | 5.77%   |
| Logitech                               | 9         | 5.77%   |
| Sunplus Innovation Technology          | 8         | 5.13%   |
| Suyin                                  | 7         | 4.49%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 4.49%   |
| Syntek                                 | 4         | 2.56%   |
| Lenovo                                 | 4         | 2.56%   |
| Microsoft                              | 3         | 1.92%   |
| Luxvisions Innotech Limited            | 3         | 1.92%   |
| Lite-On Technology                     | 3         | 1.92%   |
| IMC Networks                           | 3         | 1.92%   |
| Z-Star Microelectronics                | 1         | 0.64%   |
| USB2.0 Webcamera                       | 1         | 0.64%   |
| Primax Electronics                     | 1         | 0.64%   |
| PC-LM1E                                | 1         | 0.64%   |
| Importek                               | 1         | 0.64%   |
| Generalplus Technology                 | 1         | 0.64%   |
| Creative Technology                    | 1         | 0.64%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 8         | 5.06%   |
| Realtek Integrated_Webcam_HD                        | 4         | 2.53%   |
| Chicony HD WebCam                                   | 4         | 2.53%   |
| Apple FaceTime HD Camera (Built-in)                 | 4         | 2.53%   |
| Apple FaceTime HD Camera                            | 4         | 2.53%   |
| Suyin 1.3M HD WebCam                                | 3         | 1.9%    |
| Realtek HD WebCam                                   | 3         | 1.9%    |
| Quanta HP TrueVision HD Camera                      | 3         | 1.9%    |
| Chicony HP Wide Vision HD Camera                    | 3         | 1.9%    |
| Chicony HP Truevision HD                            | 3         | 1.9%    |
| Chicony HP HD Webcam [Fixed]                        | 3         | 1.9%    |
| Apple iPhone 5/5C/5S/6/SE                           | 3         | 1.9%    |
| Acer Lenovo EasyCamera                              | 3         | 1.9%    |
| Syntek Integrated Camera                            | 2         | 1.27%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 2         | 1.27%   |
| Sunplus Laptop_Integrated_Webcam_HD                 | 2         | 1.27%   |
| Realtek USB Camera                                  | 2         | 1.27%   |
| Microdia Webcam Vitade AF                           | 2         | 1.27%   |
| Microdia Laptop_Integrated_Webcam_HD                | 2         | 1.27%   |
| Microdia Integrated_Webcam_HD                       | 2         | 1.27%   |
| Logitech Webcam C270                                | 2         | 1.27%   |
| Logitech HD Pro Webcam C920                         | 2         | 1.27%   |
| Lite-On Integrated Camera                           | 2         | 1.27%   |
| Lenovo Integrated Webcam                            | 2         | 1.27%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 2         | 1.27%   |
| Chicony USB2.0 Camera                               | 2         | 1.27%   |
| Chicony HP TrueVision HD Camera                     | 2         | 1.27%   |
| Chicony HP High Definition 1MP Webcam               | 2         | 1.27%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 2         | 1.27%   |
| Apple Built-in iSight                               | 2         | 1.27%   |
| Z-Star Sirius USB2.0 Camera                         | 1         | 0.63%   |
| USB2.0 Webcamera USB2.0 Webcamera                   | 1         | 0.63%   |
| Syntek USB2.0 Camera                                | 1         | 0.63%   |
| Syntek EasyCamera                                   | 1         | 0.63%   |
| Suyin HP TrueVision HD Integrated Webcam            | 1         | 0.63%   |
| Suyin Asus Integrated Webcam                        | 1         | 0.63%   |
| Sunplus Laptop_Integrated_Webcam_1.3M               | 1         | 0.63%   |
| Sunplus Laptop Integrated WebCam HD                 | 1         | 0.63%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 0.63%   |
| Sunplus FHD Camera Microphone                       | 1         | 0.63%   |
| Sunplus Aukey-PC-LM1E Camera                        | 1         | 0.63%   |
| Sunplus 1.3M HD WebCam                              | 1         | 0.63%   |
| Realtek USB2.0 HD UVC WebCam                        | 1         | 0.63%   |
| Realtek Integrated Webcam                           | 1         | 0.63%   |
| Realtek Integrated Camera                           | 1         | 0.63%   |
| Realtek HP Truevision HD                            | 1         | 0.63%   |
| Quanta ov9734_techfront_camera                      | 1         | 0.63%   |
| Quanta HP Webcam                                    | 1         | 0.63%   |
| Quanta HP TrueVision HD Webcam                      | 1         | 0.63%   |
| Quanta HP 5M Camera                                 | 1         | 0.63%   |
| Quanta HD User Facing                               | 1         | 0.63%   |
| Quanta HD Camera                                    | 1         | 0.63%   |
| Primax Villem                                       | 1         | 0.63%   |
| PC-LM1E PC-LM1E                                     | 1         | 0.63%   |
| Microsoft Xbox NUI Camera                           | 1         | 0.63%   |
| Microsoft LifeCam Rear                              | 1         | 0.63%   |
| Microsoft LifeCam HD-3000                           | 1         | 0.63%   |
| Microsoft LifeCam Front                             | 1         | 0.63%   |
| Microdia USB Live camera                            | 1         | 0.63%   |
| Microdia Sonix 1.3 MP Laptop Integrated Webcam      | 1         | 0.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 14        | 45.16%  |
| Synaptics                  | 4         | 12.9%   |
| Upek                       | 3         | 9.68%   |
| Shenzhen Goodix Technology | 3         | 9.68%   |
| LighTuning Technology      | 3         | 9.68%   |
| AuthenTec                  | 2         | 6.45%   |
| STMicroelectronics         | 1         | 3.23%   |
| Focal-systems.Corp         | 1         | 3.23%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 9.68%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 9.68%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 9.68%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 6.45%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 6.45%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 6.45%   |
| Shenzhen Goodix  FingerPrint Device                                        | 2         | 6.45%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 3.23%   |
| Validity Sensors VFS491                                                    | 1         | 3.23%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 3.23%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 3.23%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 3.23%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 3.23%   |
| Synaptics  WBDI                                                            | 1         | 3.23%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 3.23%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 3.23%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 3.23%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 3.23%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 3.23%   |
| AuthenTec AES2810                                                          | 1         | 3.23%   |
| Unknown                                                                    | 1         | 3.23%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 2         | 40%     |
| Alcor Micro | 2         | 40%     |
| Upek        | 1         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


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

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 161       | 70.61%  |
| 1     | 56        | 24.56%  |
| 2     | 10        | 4.39%   |
| 3     | 1         | 0.44%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 31        | 38.27%  |
| Net/wireless             | 16        | 19.75%  |
| Graphics card            | 12        | 14.81%  |
| Multimedia controller    | 8         | 9.88%   |
| Chipcard                 | 5         | 6.17%   |
| Sound                    | 2         | 2.47%   |
| Net/ethernet             | 2         | 2.47%   |
| Bluetooth                | 2         | 2.47%   |
| Storage                  | 1         | 1.23%   |
| Communication controller | 1         | 1.23%   |
| Camera                   | 1         | 1.23%   |

