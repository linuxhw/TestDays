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

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.11.0-40-generic      | 52        | 22.61%  |
| 5.11.0-41-generic      | 39        | 16.96%  |
| 5.11.0-27-generic      | 38        | 16.52%  |
| 5.11.0-38-generic      | 25        | 10.87%  |
| 5.11.0-37-generic      | 24        | 10.43%  |
| 5.11.0-25-generic      | 16        | 6.96%   |
| 5.11.0-34-generic      | 14        | 6.09%   |
| 5.8.0-50-generic       | 5         | 2.17%   |
| 5.11.0-36-generic      | 4         | 1.74%   |
| 5.8.0-55-generic       | 3         | 1.3%    |
| 5.8.0-63-generic       | 2         | 0.87%   |
| 5.8.0-53-generic       | 1         | 0.43%   |
| 5.8.0-44-generic       | 1         | 0.43%   |
| 5.4.0-58-generic       | 1         | 0.43%   |
| 5.4.0-56-generic       | 1         | 0.43%   |
| 5.14.7-xanmod1-cacule  | 1         | 0.43%   |
| 5.14.14-051414-generic | 1         | 0.43%   |
| 5.11.0-41-lowlatency   | 1         | 0.43%   |
| 5.11.0-051100-generic  | 1         | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11.0  | 204       | 92.73%  |
| 5.8.0   | 12        | 5.45%   |
| 5.4.0   | 2         | 0.91%   |
| 5.14.7  | 1         | 0.45%   |
| 5.14.14 | 1         | 0.45%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11    | 204       | 92.73%  |
| 5.8     | 12        | 5.45%   |
| 5.4     | 2         | 0.91%   |
| 5.14    | 2         | 0.91%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 220       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Pantheon   | 201       | 90.95%  |
| Unknown    | 15        | 6.79%   |
| X-Cinnamon | 2         | 0.9%    |
| GNOME      | 2         | 0.9%    |
| MATE       | 1         | 0.45%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 220       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 175       | 79.55%  |
| LightDM | 36        | 16.36%  |
| TDM     | 7         | 3.18%   |
| GDM     | 2         | 0.91%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 111       | 50.45%  |
| de_DE | 22        | 10%     |
| es_ES | 19        | 8.64%   |
| ru_RU | 8         | 3.64%   |
| pt_BR | 8         | 3.64%   |
| fr_FR | 8         | 3.64%   |
| en_GB | 6         | 2.73%   |
| pl_PL | 4         | 1.82%   |
| it_IT | 4         | 1.82%   |
| zh_CN | 3         | 1.36%   |
| en_CA | 3         | 1.36%   |
| cs_CZ | 3         | 1.36%   |
| tr_TR | 2         | 0.91%   |
| nl_NL | 2         | 0.91%   |
| en_AU | 2         | 0.91%   |
| de_CH | 2         | 0.91%   |
| ca_ES | 2         | 0.91%   |
| vi_VN | 1         | 0.45%   |
| ro_RO | 1         | 0.45%   |
| lt_LT | 1         | 0.45%   |
| id_ID | 1         | 0.45%   |
| hu_HU | 1         | 0.45%   |
| hr_HR | 1         | 0.45%   |
| gl_ES | 1         | 0.45%   |
| fr_BE | 1         | 0.45%   |
| fi_FI | 1         | 0.45%   |
| es_MX | 1         | 0.45%   |
| da_DK | 1         | 0.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 139       | 62.9%   |
| BIOS | 82        | 37.1%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 211       | 95.91%  |
| Overlay | 5         | 2.27%   |
| Btrfs   | 4         | 1.82%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 182       | 82.73%  |
| GPT     | 27        | 12.27%  |
| MBR     | 11        | 5%      |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 210       | 95.45%  |
| Yes       | 10        | 4.55%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 194       | 88.18%  |
| Yes       | 26        | 11.82%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 48        | 21.82%  |
| Lenovo                  | 26        | 11.82%  |
| ASUSTek Computer        | 23        | 10.45%  |
| Dell                    | 22        | 10%     |
| Apple                   | 16        | 7.27%   |
| Acer                    | 15        | 6.82%   |
| Gigabyte Technology     | 14        | 6.36%   |
| MSI                     | 8         | 3.64%   |
| ASRock                  | 7         | 3.18%   |
| Toshiba                 | 4         | 1.82%   |
| Intel                   | 3         | 1.36%   |
| HUAWEI                  | 3         | 1.36%   |
| Google                  | 3         | 1.36%   |
| TUXEDO                  | 2         | 0.91%   |
| Sony                    | 2         | 0.91%   |
| Pegatron                | 2         | 0.91%   |
| Microsoft               | 2         | 0.91%   |
| Medion                  | 2         | 0.91%   |
| Biostar                 | 2         | 0.91%   |
| Star Labs               | 1         | 0.45%   |
| Shuttle                 | 1         | 0.45%   |
| Schenker                | 1         | 0.45%   |
| Samsung Electronics     | 1         | 0.45%   |
| Quanta                  | 1         | 0.45%   |
| Panasonic               | 1         | 0.45%   |
| Packard Bell            | 1         | 0.45%   |
| Notebook                | 1         | 0.45%   |
| HCL Infosystems Limited | 1         | 0.45%   |
| Gateway                 | 1         | 0.45%   |
| Fujitsu                 | 1         | 0.45%   |
| eMachines               | 1         | 0.45%   |
| Chuwi                   | 1         | 0.45%   |
| Alienware               | 1         | 0.45%   |
| Acidanthera             | 1         | 0.45%   |
| Unknown                 | 1         | 0.45%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo Yoga 300-11IBR 80M1                 | 2         | 0.91%   |
| HP Pavilion Notebook                       | 2         | 0.91%   |
| Dell XPS 13 9350                           | 2         | 0.91%   |
| Apple MacBookPro9,1                        | 2         | 0.91%   |
| Apple MacBookPro10,2                       | 2         | 0.91%   |
| Apple MacBookAir7,2                        | 2         | 0.91%   |
| TUXEDO Pulse 15 Gen1                       | 1         | 0.45%   |
| TUXEDO InfinityBook S 14 Gen6              | 1         | 0.45%   |
| Toshiba Satellite P100                     | 1         | 0.45%   |
| Toshiba Satellite L840                     | 1         | 0.45%   |
| Toshiba Satellite L750                     | 1         | 0.45%   |
| Toshiba Satellite L500                     | 1         | 0.45%   |
| Star Labs StarBook                         | 1         | 0.45%   |
| Sony SVE15115EN                            | 1         | 0.45%   |
| Sony Serie VJC14                           | 1         | 0.45%   |
| Shuttle DS61                               | 1         | 0.45%   |
| Schenker X170KM-G                          | 1         | 0.45%   |
| Samsung 550XDA                             | 1         | 0.45%   |
| Quanta TW9/SW9                             | 1         | 0.45%   |
| Pegatron KJ379AA-ABA a6400f                | 1         | 0.45%   |
| Pegatron IPMH61P1                          | 1         | 0.45%   |
| Panasonic FZ-G1ASH39E3                     | 1         | 0.45%   |
| Packard Bell EasyNote LS11HR               | 1         | 0.45%   |
| Notebook L140CU                            | 1         | 0.45%   |
| MSI MS-7C83                                | 1         | 0.45%   |
| MSI MS-7B79                                | 1         | 0.45%   |
| MSI MS-7B46                                | 1         | 0.45%   |
| MSI MS-7817                                | 1         | 0.45%   |
| MSI MS-7693                                | 1         | 0.45%   |
| MSI Modern 14 B4MW                         | 1         | 0.45%   |
| MSI GF72 7RE                               | 1         | 0.45%   |
| MSI Elite 7100 Microtower PC               | 1         | 0.45%   |
| Microsoft Surface Pro 4                    | 1         | 0.45%   |
| Microsoft Surface Pro 3                    | 1         | 0.45%   |
| Medion E7218                               | 1         | 0.45%   |
| Medion Akoya THE TOUCH 10                  | 1         | 0.45%   |
| Lenovo V330-15IKB 81AX                     | 1         | 0.45%   |
| Lenovo ThinkPad X250 20CLS32H00            | 1         | 0.45%   |
| Lenovo ThinkPad X230 23259L3               | 1         | 0.45%   |
| Lenovo ThinkPad X201 Tablet 311396G        | 1         | 0.45%   |
| Lenovo ThinkPad X201 3249CTO               | 1         | 0.45%   |
| Lenovo ThinkPad X140e 20BLS00400           | 1         | 0.45%   |
| Lenovo ThinkPad X1 Carbon 3448B86          | 1         | 0.45%   |
| Lenovo ThinkPad W700 2758MVG               | 1         | 0.45%   |
| Lenovo ThinkPad T470 20HD004AUS            | 1         | 0.45%   |
| Lenovo ThinkPad T460s 20F90042MS           | 1         | 0.45%   |
| Lenovo ThinkPad T430 2342A19               | 1         | 0.45%   |
| Lenovo ThinkPad T410s 292494G              | 1         | 0.45%   |
| Lenovo ThinkPad T14 Gen 1 20UES5SR00       | 1         | 0.45%   |
| Lenovo ThinkPad SL400 2743A37              | 1         | 0.45%   |
| Lenovo ThinkPad E470 20H10052IG            | 1         | 0.45%   |
| Lenovo ThinkPad E14 Gen 3 20Y7006XMX       | 1         | 0.45%   |
| Lenovo IdeaPad S145-15AST 81N3             | 1         | 0.45%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5           | 1         | 0.45%   |
| Lenovo IdeaPad 5 14ARE05 81YM              | 1         | 0.45%   |
| Lenovo IdeaPad 330-15IKB 81FE              | 1         | 0.45%   |
| Lenovo IdeaPad 320S-14IKB 81BN             | 1         | 0.45%   |
| Lenovo IdeaPad 120S-14IAP 81A5             | 1         | 0.45%   |
| Lenovo IdeaCentre AIO 3 24ARE05 F0EW00FLSC | 1         | 0.45%   |
| Lenovo G50-45 80E3                         | 1         | 0.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 15        | 6.82%   |
| HP Pavilion            | 13        | 5.91%   |
| Acer Aspire            | 10        | 4.55%   |
| Lenovo IdeaPad         | 6         | 2.73%   |
| HP ProBook             | 6         | 2.73%   |
| HP Laptop              | 6         | 2.73%   |
| HP EliteBook           | 6         | 2.73%   |
| HP ENVY                | 5         | 2.27%   |
| Dell XPS               | 5         | 2.27%   |
| Dell Inspiron          | 5         | 2.27%   |
| Toshiba Satellite      | 4         | 1.82%   |
| Dell Latitude          | 4         | 1.82%   |
| Dell OptiPlex          | 3         | 1.36%   |
| ASUS TUF               | 3         | 1.36%   |
| ASUS ROG               | 3         | 1.36%   |
| Microsoft Surface      | 2         | 0.91%   |
| Lenovo Yoga            | 2         | 0.91%   |
| HP Compaq              | 2         | 0.91%   |
| Gigabyte X570          | 2         | 0.91%   |
| Dell System            | 2         | 0.91%   |
| Dell Precision         | 2         | 0.91%   |
| ASUS PRIME             | 2         | 0.91%   |
| Apple MacBookPro9      | 2         | 0.91%   |
| Apple MacBookPro8      | 2         | 0.91%   |
| Apple MacBookPro10     | 2         | 0.91%   |
| Apple MacBookAir7      | 2         | 0.91%   |
| Acer Swift             | 2         | 0.91%   |
| Acer ConceptD          | 2         | 0.91%   |
| TUXEDO Pulse           | 1         | 0.45%   |
| TUXEDO InfinityBook    | 1         | 0.45%   |
| Star Labs StarBook     | 1         | 0.45%   |
| Sony SVE15115EN        | 1         | 0.45%   |
| Sony Serie             | 1         | 0.45%   |
| Shuttle DS61           | 1         | 0.45%   |
| Schenker X170KM-G      | 1         | 0.45%   |
| Samsung 550XDA         | 1         | 0.45%   |
| Quanta TW9             | 1         | 0.45%   |
| Pegatron KJ379AA-ABA   | 1         | 0.45%   |
| Pegatron IPMH61P1      | 1         | 0.45%   |
| Panasonic FZ-G1ASH39E3 | 1         | 0.45%   |
| Packard Bell EasyNote  | 1         | 0.45%   |
| Notebook L140CU        | 1         | 0.45%   |
| MSI MS-7C83            | 1         | 0.45%   |
| MSI MS-7B79            | 1         | 0.45%   |
| MSI MS-7B46            | 1         | 0.45%   |
| MSI MS-7817            | 1         | 0.45%   |
| MSI MS-7693            | 1         | 0.45%   |
| MSI Modern             | 1         | 0.45%   |
| MSI GF72               | 1         | 0.45%   |
| MSI Elite              | 1         | 0.45%   |
| Medion E7218           | 1         | 0.45%   |
| Medion Akoya           | 1         | 0.45%   |
| Lenovo V330-15IKB      | 1         | 0.45%   |
| Lenovo IdeaCentre      | 1         | 0.45%   |
| Lenovo G50-45          | 1         | 0.45%   |
| Intel X64              | 1         | 0.45%   |
| Intel NUC7i3BNH        | 1         | 0.45%   |
| Intel H61              | 1         | 0.45%   |
| HUAWEI NBLB-WAX9N      | 1         | 0.45%   |
| HUAWEI MACHD-WXX9      | 1         | 0.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 54        | 24.55%  |
| 2020    | 31        | 14.09%  |
| 2019    | 23        | 10.45%  |
| 2018    | 19        | 8.64%   |
| 2015    | 16        | 7.27%   |
| 2012    | 15        | 6.82%   |
| 2011    | 15        | 6.82%   |
| 2014    | 10        | 4.55%   |
| 2010    | 9         | 4.09%   |
| 2017    | 8         | 3.64%   |
| 2013    | 7         | 3.18%   |
| 2016    | 4         | 1.82%   |
| 2009    | 4         | 1.82%   |
| 2008    | 2         | 0.91%   |
| 2007    | 2         | 0.91%   |
| Unknown | 1         | 0.45%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 134       | 60.91%  |
| Desktop     | 64        | 29.09%  |
| All in one  | 11        | 5%      |
| Convertible | 6         | 2.73%   |
| Tablet      | 4         | 1.82%   |
| Mini pc     | 1         | 0.45%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 182       | 82.73%  |
| Enabled  | 38        | 17.27%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 216       | 98.18%  |
| Yes  | 4         | 1.82%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 66        | 30%     |
| 16.01-24.0  | 44        | 20%     |
| 3.01-4.0    | 41        | 18.64%  |
| 8.01-16.0   | 34        | 15.45%  |
| 32.01-64.0  | 23        | 10.45%  |
| 1.01-2.0    | 9         | 4.09%   |
| 24.01-32.0  | 1         | 0.45%   |
| 2.01-3.0    | 1         | 0.45%   |
| 64.01-256.0 | 1         | 0.45%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 95        | 41.3%   |
| 2.01-3.0  | 67        | 29.13%  |
| 3.01-4.0  | 33        | 14.35%  |
| 4.01-8.0  | 30        | 13.04%  |
| 0.51-1.0  | 3         | 1.3%    |
| 8.01-16.0 | 2         | 0.87%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 143       | 64.41%  |
| 2      | 56        | 25.23%  |
| 3      | 10        | 4.5%    |
| 4      | 9         | 4.05%   |
| 5      | 3         | 1.35%   |
| 6      | 1         | 0.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 152       | 69.09%  |
| Yes       | 68        | 30.91%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 179       | 81.36%  |
| No        | 41        | 18.64%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 188       | 85.45%  |
| No        | 32        | 14.55%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 163       | 73.76%  |
| No        | 58        | 26.24%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country            | Computers | Percent |
|--------------------|-----------|---------|
| USA                | 30        | 13.57%  |
| Germany            | 21        | 9.5%    |
| India              | 13        | 5.88%   |
| UK                 | 11        | 4.98%   |
| Russia             | 10        | 4.52%   |
| Canada             | 10        | 4.52%   |
| Brazil             | 10        | 4.52%   |
| Mexico             | 7         | 3.17%   |
| France             | 7         | 3.17%   |
| Argentina          | 7         | 3.17%   |
| Netherlands        | 6         | 2.71%   |
| Indonesia          | 6         | 2.71%   |
| Spain              | 5         | 2.26%   |
| Poland             | 4         | 1.81%   |
| Italy              | 4         | 1.81%   |
| Finland            | 4         | 1.81%   |
| Denmark            | 4         | 1.81%   |
| Czechia            | 4         | 1.81%   |
| Vietnam            | 3         | 1.36%   |
| Sweden             | 3         | 1.36%   |
| Belgium            | 3         | 1.36%   |
| Austria            | 3         | 1.36%   |
| Australia          | 3         | 1.36%   |
| Turkey             | 2         | 0.9%    |
| Switzerland        | 2         | 0.9%    |
| Romania            | 2         | 0.9%    |
| Paraguay           | 2         | 0.9%    |
| Kenya              | 2         | 0.9%    |
| Guatemala          | 2         | 0.9%    |
| Estonia            | 2         | 0.9%    |
| China              | 2         | 0.9%    |
| Chile              | 2         | 0.9%    |
| Uruguay            | 1         | 0.45%   |
| Ukraine            | 1         | 0.45%   |
| Thailand           | 1         | 0.45%   |
| Sri Lanka          | 1         | 0.45%   |
| South Africa       | 1         | 0.45%   |
| Slovenia           | 1         | 0.45%   |
| Serbia             | 1         | 0.45%   |
| Philippines        | 1         | 0.45%   |
| New Zealand        | 1         | 0.45%   |
| Myanmar            | 1         | 0.45%   |
| Morocco            | 1         | 0.45%   |
| Malaysia           | 1         | 0.45%   |
| Lithuania          | 1         | 0.45%   |
| Latvia             | 1         | 0.45%   |
| Kazakhstan         | 1         | 0.45%   |
| Japan              | 1         | 0.45%   |
| Ireland            | 1         | 0.45%   |
| Hungary            | 1         | 0.45%   |
| Guyana             | 1         | 0.45%   |
| Greece             | 1         | 0.45%   |
| Dominican Republic | 1         | 0.45%   |
| Croatia            | 1         | 0.45%   |
| Costa Rica         | 1         | 0.45%   |
| Colombia           | 1         | 0.45%   |
| Albania            | 1         | 0.45%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Vienna                | 3         | 1.33%   |
| Moscow                | 3         | 1.33%   |
| Mexico City           | 3         | 1.33%   |
| Warsaw                | 2         | 0.88%   |
| Tallinn               | 2         | 0.88%   |
| Santiago              | 2         | 0.88%   |
| Paris                 | 2         | 0.88%   |
| Nairobi               | 2         | 0.88%   |
| Mumbai                | 2         | 0.88%   |
| Montreal              | 2         | 0.88%   |
| Milan                 | 2         | 0.88%   |
| Medan                 | 2         | 0.88%   |
| Guatemala City        | 2         | 0.88%   |
| Calgary               | 2         | 0.88%   |
| Buenos Aires          | 2         | 0.88%   |
| Brussels              | 2         | 0.88%   |
| Zonguldak             | 1         | 0.44%   |
| Znojmo                | 1         | 0.44%   |
| Xicheng District      | 1         | 0.44%   |
| Wythenshawe           | 1         | 0.44%   |
| Wriezen               | 1         | 0.44%   |
| Woodbridge            | 1         | 0.44%   |
| Wigan                 | 1         | 0.44%   |
| Wattala               | 1         | 0.44%   |
| Wakefield             | 1         | 0.44%   |
| Vit??ria              | 1         | 0.44%   |
| Vilnius               | 1         | 0.44%   |
| Villeurbanne          | 1         | 0.44%   |
| Villahermosa          | 1         | 0.44%   |
| Victoria              | 1         | 0.44%   |
| Veyre-Monton          | 1         | 0.44%   |
| Vernon                | 1         | 0.44%   |
| Vantaa                | 1         | 0.44%   |
| Vancouver             | 1         | 0.44%   |
| Valladolid            | 1         | 0.44%   |
| Ullastrell            | 1         | 0.44%   |
| Turku                 | 1         | 0.44%   |
| Tucson                | 1         | 0.44%   |
| Tolyatti              | 1         | 0.44%   |
| Toluca                | 1         | 0.44%   |
| Toledo                | 1         | 0.44%   |
| Tirupur               | 1         | 0.44%   |
| Thousand Oaks         | 1         | 0.44%   |
| Taganrog              | 1         | 0.44%   |
| Surabaya              | 1         | 0.44%   |
| Sukabumi              | 1         | 0.44%   |
| Stockholm             | 1         | 0.44%   |
| Stevenage             | 1         | 0.44%   |
| Staropyshminsk        | 1         | 0.44%   |
| Sparti                | 1         | 0.44%   |
| Sinop                 | 1         | 0.44%   |
| Simferopol            | 1         | 0.44%   |
| Seattle               | 1         | 0.44%   |
| Schwarzenbach am Wald | 1         | 0.44%   |
| S??o Pedro            | 1         | 0.44%   |
| S??o Paulo            | 1         | 0.44%   |
| Saskatoon             | 1         | 0.44%   |
| Sao Jose do Rio Preto | 1         | 0.44%   |
| Sao Joaquim da Barra  | 1         | 0.44%   |
| Santo Andr?�          | 1         | 0.44%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 52        | 63     | 17.33%  |
| Samsung Electronics       | 47        | 61     | 15.67%  |
| Seagate                   | 35        | 43     | 11.67%  |
| Sandisk                   | 21        | 24     | 7%      |
| Toshiba                   | 17        | 17     | 5.67%   |
| Kingston                  | 15        | 20     | 5%      |
| Unknown                   | 13        | 14     | 4.33%   |
| Crucial                   | 13        | 16     | 4.33%   |
| Hitachi                   | 8         | 8      | 2.67%   |
| Apple                     | 8         | 8      | 2.67%   |
| HGST                      | 7         | 7      | 2.33%   |
| Micron Technology         | 6         | 6      | 2%      |
| Intel                     | 6         | 6      | 2%      |
| SK Hynix                  | 5         | 6      | 1.67%   |
| Phison                    | 3         | 4      | 1%      |
| Patriot                   | 3         | 3      | 1%      |
| OCZ                       | 3         | 3      | 1%      |
| LITEON                    | 3         | 3      | 1%      |
| KIOXIA                    | 3         | 3      | 1%      |
| Gigabyte Technology       | 3         | 3      | 1%      |
| A-DATA Technology         | 3         | 4      | 1%      |
| Transcend                 | 2         | 3      | 0.67%   |
| Silicon Motion            | 2         | 2      | 0.67%   |
| Micron/Crucial Technology | 2         | 3      | 0.67%   |
| LITEONIT                  | 2         | 2      | 0.67%   |
| China                     | 2         | 2      | 0.67%   |
| USB3.1                    | 1         | 1      | 0.33%   |
| Union Memory              | 1         | 1      | 0.33%   |
| Team                      | 1         | 1      | 0.33%   |
| StoreJet                  | 1         | 1      | 0.33%   |
| Star Drive                | 1         | 1      | 0.33%   |
| OCZ-VERTEX2               | 1         | 1      | 0.33%   |
| Netac                     | 1         | 1      | 0.33%   |
| Mercury                   | 1         | 1      | 0.33%   |
| LS                        | 1         | 1      | 0.33%   |
| Kingmax                   | 1         | 1      | 0.33%   |
| HUAWEI                    | 1         | 1      | 0.33%   |
| Hewlett-Packard           | 1         | 1      | 0.33%   |
| GALAX                     | 1         | 1      | 0.33%   |
| Dogfish                   | 1         | 1      | 0.33%   |
| CLOVER                    | 1         | 1      | 0.33%   |
| Apacer                    | 1         | 1      | 0.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD  | 7         | 2.17%   |
| Samsung NVMe SSD Drive 512GB     | 6         | 1.86%   |
| Samsung NVMe SSD Drive 500GB     | 6         | 1.86%   |
| Samsung NVMe SSD Drive 256GB     | 5         | 1.55%   |
| Unknown MMC Card  128GB          | 4         | 1.24%   |
| Sandisk NVMe SSD Drive 512GB     | 4         | 1.24%   |
| Samsung NVMe SSD Drive 1TB       | 4         | 1.24%   |
| Intel NVMe SSD Drive 512GB       | 4         | 1.24%   |
| Crucial CT240BX500SSD1 240GB     | 4         | 1.24%   |
| WDC WD5000LPVX-22V0TT0 500GB     | 3         | 0.93%   |
| WDC WD10JPVX-22JC3T0 1TB         | 3         | 0.93%   |
| Seagate ST1000LM035-1RK172 1TB   | 3         | 0.93%   |
| Samsung SSD 860 EVO 250GB        | 3         | 0.93%   |
| Kingston SA400S37480G 480GB SSD  | 3         | 0.93%   |
| WDC WDS500G2B0A-00SM50 500GB SSD | 2         | 0.62%   |
| WDC WD5000AAKX-003CA0 500GB      | 2         | 0.62%   |
| WDC WD10SPZX-21Z10T0 1TB         | 2         | 0.62%   |
| WDC WD10EZEX-60WN4A0 1TB         | 2         | 0.62%   |
| WDC WD10EZEX-08WN4A0 1TB         | 2         | 0.62%   |
| Unknown MMC Card  32GB           | 2         | 0.62%   |
| Unknown MMC Card  16GB           | 2         | 0.62%   |
| Toshiba NVMe SSD Drive 256GB     | 2         | 0.62%   |
| Toshiba MQ01ABD100 1TB           | 2         | 0.62%   |
| Toshiba MK6475GSX 640GB          | 2         | 0.62%   |
| SK Hynix NVMe SSD Drive 512GB    | 2         | 0.62%   |
| Seagate ST500LT012-1DG142 500GB  | 2         | 0.62%   |
| Seagate ST250DM000-1BD141 250GB  | 2         | 0.62%   |
| Seagate ST2000LX001-1RG174 2TB   | 2         | 0.62%   |
| Sandisk NVMe SSD Drive 500GB     | 2         | 0.62%   |
| Sandisk NVMe SSD Drive 256GB     | 2         | 0.62%   |
| Samsung SSD 850 EVO 250GB        | 2         | 0.62%   |
| Samsung SSD 840 EVO 120GB        | 2         | 0.62%   |
| KIOXIA NVMe SSD Drive 512GB      | 2         | 0.62%   |
| HGST HTS721010A9E630 1TB         | 2         | 0.62%   |
| HGST HTS541010A9E680 1TB         | 2         | 0.62%   |
| Crucial CT525MX300SSD1 528GB     | 2         | 0.62%   |
| Crucial CT250MX500SSD1 250GB     | 2         | 0.62%   |
| Crucial CT240BX200SSD1 240GB     | 2         | 0.62%   |
| Apple SSD SD128E 121GB           | 2         | 0.62%   |
| WDC WDS500G2B0A 500GB SSD        | 1         | 0.31%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 1         | 0.31%   |
| WDC WDS200T2B0B-00YS70 2TB SSD   | 1         | 0.31%   |
| WDC WD6401AALS-00J7B0 640GB      | 1         | 0.31%   |
| WDC WD6400BEVT-22A0RT0 640GB     | 1         | 0.31%   |
| WDC WD5000LPLX-08ZNTT0 500GB     | 1         | 0.31%   |
| WDC WD5000BPVT-75HXZT1 500GB     | 1         | 0.31%   |
| WDC WD5000BPVT-22HXZT3 500GB     | 1         | 0.31%   |
| WDC WD5000BPVT-00HXZT1 500GB     | 1         | 0.31%   |
| WDC WD5000BPKT-75PK4T0 500GB     | 1         | 0.31%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 1         | 0.31%   |
| WDC WD5000AAKX-603CA0 500GB      | 1         | 0.31%   |
| WDC WD5000AAKX-00ERMA0 500GB     | 1         | 0.31%   |
| WDC WD5000AAKX-001CA0 500GB      | 1         | 0.31%   |
| WDC WD50 00LUCT-61C26Y0 500GB    | 1         | 0.31%   |
| WDC WD40EZRZ-00GXCB0 4TB         | 1         | 0.31%   |
| WDC WD40EZAZ-00SF3B0 4TB         | 1         | 0.31%   |
| WDC WD3200BEVT-75A23T0 320GB     | 1         | 0.31%   |
| WDC WD3200AAJS-56B4A0 320GB      | 1         | 0.31%   |
| WDC WD2500BEKT-75A25T0 250GB     | 1         | 0.31%   |
| WDC WD2500AAKS-00B3A0 250GB      | 1         | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 44        | 53     | 38.26%  |
| Seagate             | 34        | 41     | 29.57%  |
| Toshiba             | 13        | 13     | 11.3%   |
| Hitachi             | 8         | 8      | 6.96%   |
| HGST                | 7         | 7      | 6.09%   |
| Samsung Electronics | 5         | 5      | 4.35%   |
| Apple               | 2         | 2      | 1.74%   |
| Unknown             | 1         | 1      | 0.87%   |
| StoreJet            | 1         | 1      | 0.87%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 19        | 24     | 18.27%  |
| Crucial             | 13        | 16     | 12.5%   |
| SanDisk             | 12        | 13     | 11.54%  |
| Kingston            | 12        | 16     | 11.54%  |
| Apple               | 6         | 6      | 5.77%   |
| WDC                 | 5         | 5      | 4.81%   |
| Patriot             | 3         | 3      | 2.88%   |
| OCZ                 | 3         | 3      | 2.88%   |
| Micron Technology   | 3         | 3      | 2.88%   |
| LITEON              | 3         | 3      | 2.88%   |
| A-DATA Technology   | 3         | 4      | 2.88%   |
| Transcend           | 2         | 3      | 1.92%   |
| SK Hynix            | 2         | 2      | 1.92%   |
| LITEONIT            | 2         | 2      | 1.92%   |
| Intel               | 2         | 2      | 1.92%   |
| China               | 2         | 2      | 1.92%   |
| Toshiba             | 1         | 1      | 0.96%   |
| Team                | 1         | 1      | 0.96%   |
| OCZ-VERTEX2         | 1         | 1      | 0.96%   |
| Netac               | 1         | 1      | 0.96%   |
| Mercury             | 1         | 1      | 0.96%   |
| LS                  | 1         | 1      | 0.96%   |
| Kingmax             | 1         | 1      | 0.96%   |
| Hewlett-Packard     | 1         | 1      | 0.96%   |
| Gigabyte Technology | 1         | 1      | 0.96%   |
| GALAX               | 1         | 1      | 0.96%   |
| Dogfish             | 1         | 1      | 0.96%   |
| Apacer              | 1         | 1      | 0.96%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 105       | 131    | 37.63%  |
| SSD     | 92        | 119    | 32.97%  |
| NVMe    | 65        | 82     | 23.3%   |
| MMC     | 11        | 12     | 3.94%   |
| Unknown | 6         | 6      | 2.15%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 171       | 247    | 67.32%  |
| NVMe | 65        | 82     | 25.59%  |
| MMC  | 11        | 12     | 4.33%   |
| SAS  | 7         | 9      | 2.76%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 127       | 167    | 63.5%   |
| 0.51-1.0   | 58        | 65     | 29%     |
| 1.01-2.0   | 11        | 13     | 5.5%    |
| 3.01-4.0   | 2         | 2      | 1%      |
| 2.01-3.0   | 2         | 3      | 1%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 83        | 37.39%  |
| 251-500        | 63        | 28.38%  |
| 501-1000       | 27        | 12.16%  |
| 51-100         | 14        | 6.31%   |
| 21-50          | 12        | 5.41%   |
| 1001-2000      | 10        | 4.5%    |
| 2001-3000      | 5         | 2.25%   |
| 1-20           | 5         | 2.25%   |
| More than 3000 | 3         | 1.35%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 117       | 52.7%   |
| 21-50     | 47        | 21.17%  |
| 51-100    | 26        | 11.71%  |
| 101-250   | 15        | 6.76%   |
| 251-500   | 6         | 2.7%    |
| 501-1000  | 6         | 2.7%    |
| 1001-2000 | 3         | 1.35%   |
| 2001-3000 | 2         | 0.9%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD5000BPKT-75PK4T0 500GB        | 1         | 1      | 8.33%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 1         | 1      | 8.33%   |
| WDC WD3200AAJS-56B4A0 320GB         | 1         | 1      | 8.33%   |
| WDC WD10EZEX-00KUWA0 1TB            | 1         | 1      | 8.33%   |
| Toshiba MK3259GSXP 320GB            | 1         | 1      | 8.33%   |
| Seagate ST320LT020-9YG142 320GB     | 1         | 1      | 8.33%   |
| Seagate ST3160813AS 160GB           | 1         | 1      | 8.33%   |
| Seagate ST1000LX015-1U7172-SSHD 1TB | 1         | 1      | 8.33%   |
| SanDisk SD7SB3Q256G1002 256GB SSD   | 1         | 1      | 8.33%   |
| Samsung Electronics HD160JJ 160GB   | 1         | 1      | 8.33%   |
| Hitachi HTS542525K9SA00 250GB       | 1         | 1      | 8.33%   |
| Apple HDD HTS541010A9E662 1TB       | 1         | 1      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 4      | 33.33%  |
| Seagate             | 3         | 3      | 25%     |
| Toshiba             | 1         | 1      | 8.33%   |
| SanDisk             | 1         | 1      | 8.33%   |
| Samsung Electronics | 1         | 1      | 8.33%   |
| Hitachi             | 1         | 1      | 8.33%   |
| Apple               | 1         | 1      | 8.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 4      | 36.36%  |
| Seagate             | 3         | 3      | 27.27%  |
| Toshiba             | 1         | 1      | 9.09%   |
| Samsung Electronics | 1         | 1      | 9.09%   |
| Hitachi             | 1         | 1      | 9.09%   |
| Apple               | 1         | 1      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 9         | 11     | 90%     |
| SSD  | 1         | 1      | 10%     |

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
| Detected | 185       | 297    | 81.5%   |
| Works    | 32        | 41     | 14.1%   |
| Malfunc  | 10        | 12     | 4.41%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 160       | 57.14%  |
| AMD                          | 36        | 12.86%  |
| Samsung Electronics          | 31        | 11.07%  |
| Sandisk                      | 16        | 5.71%   |
| Phison Electronics           | 5         | 1.79%   |
| Toshiba America Info Systems | 3         | 1.07%   |
| SK Hynix                     | 3         | 1.07%   |
| Micron Technology            | 3         | 1.07%   |
| Marvell Technology Group     | 3         | 1.07%   |
| KIOXIA                       | 3         | 1.07%   |
| Kingston Technology Company  | 3         | 1.07%   |
| Silicon Motion               | 2         | 0.71%   |
| Nvidia                       | 2         | 0.71%   |
| Micron/Crucial Technology    | 2         | 0.71%   |
| JMicron Technology           | 2         | 0.71%   |
| ASMedia Technology           | 2         | 0.71%   |
| VIA Technologies             | 1         | 0.36%   |
| Seagate Technology           | 1         | 0.36%   |
| LSI Logic / Symbios Logic    | 1         | 0.36%   |
| Broadcom / LSI               | 1         | 0.36%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 26        | 8.28%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 17        | 5.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 13        | 4.14%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 13        | 4.14%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 12        | 3.82%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 11        | 3.5%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 10        | 3.18%   |
| Samsung NVMe SSD Controller 980                                                         | 8         | 2.55%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 8         | 2.55%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 7         | 2.23%   |
| Intel SATA Controller [RAID mode]                                                       | 6         | 1.91%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5         | 1.59%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5         | 1.59%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 4         | 1.27%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 4         | 1.27%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 4         | 1.27%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 4         | 1.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4         | 1.27%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 4         | 1.27%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 4         | 1.27%   |
| SK Hynix Gold P31 SSD                                                                   | 3         | 0.96%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 3         | 0.96%   |
| Samsung Electronics SATA controller                                                     | 3         | 0.96%   |
| Micron Non-Volatile memory controller                                                   | 3         | 0.96%   |
| KIOXIA Non-Volatile memory controller                                                   | 3         | 0.96%   |
| Intel SSD 660P Series                                                                   | 3         | 0.96%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 3         | 0.96%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 3         | 0.96%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3         | 0.96%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 3         | 0.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 3         | 0.96%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 3         | 0.96%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 3         | 0.96%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 3         | 0.96%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 3         | 0.96%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3         | 0.96%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3         | 0.96%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 3         | 0.96%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 3         | 0.96%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 3         | 0.96%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3         | 0.96%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3         | 0.96%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 2         | 0.64%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2         | 0.64%   |
| Sandisk Non-Volatile memory controller                                                  | 2         | 0.64%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2         | 0.64%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2         | 0.64%   |
| Phison PS5013 E13 NVMe Controller                                                       | 2         | 0.64%   |
| Phison E12 NVMe Controller                                                              | 2         | 0.64%   |
| Kingston Company A2000 NVMe SSD                                                         | 2         | 0.64%   |
| JMicron JMB368 IDE controller                                                           | 2         | 0.64%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 2         | 0.64%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                         | 2         | 0.64%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2         | 0.64%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                    | 2         | 0.64%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 2         | 0.64%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 2         | 0.64%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3)  | 2         | 0.64%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2         | 0.64%   |
| AMD FCH SATA Controller D                                                               | 2         | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 160       | 58.18%  |
| NVMe | 65        | 23.64%  |
| RAID | 25        | 9.09%   |
| IDE  | 23        | 8.36%   |
| SAS  | 1         | 0.36%   |
| SCSI | 1         | 0.36%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 176       | 80%     |
| AMD    | 44        | 20%     |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz           | 6         | 2.73%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 4         | 1.82%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 4         | 1.82%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 4         | 1.82%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 4         | 1.82%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 3         | 1.36%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 3         | 1.36%   |
| Intel Core i3 CPU M 350 @ 2.27GHz           | 3         | 1.36%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 3         | 1.36%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 2         | 0.91%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 2         | 0.91%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 2         | 0.91%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz          | 2         | 0.91%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 2         | 0.91%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 0.91%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 2         | 0.91%   |
| Intel Core i5-5250U CPU @ 1.60GHz           | 2         | 0.91%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 2         | 0.91%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 2         | 0.91%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 2         | 0.91%   |
| Intel Core i5 CPU M 560 @ 2.67GHz           | 2         | 0.91%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2         | 0.91%   |
| Intel Core i3 CPU 530 @ 2.93GHz             | 2         | 0.91%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 2         | 0.91%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 2         | 0.91%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz     | 2         | 0.91%   |
| AMD Ryzen 5 4500U with Radeon Graphics      | 2         | 0.91%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2         | 0.91%   |
| Intel Xeon W-11855M CPU @ 3.20GHz           | 1         | 0.45%   |
| Intel Xeon CPU X5660 @ 2.80GHz              | 1         | 0.45%   |
| Intel Xeon CPU E5520 @ 2.27GHz              | 1         | 0.45%   |
| Intel Xeon CPU E5-2689 0 @ 2.60GHz          | 1         | 0.45%   |
| Intel Xeon CPU E5-2640 0 @ 2.50GHz          | 1         | 0.45%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1         | 0.45%   |
| Intel Pentium CPU P6200 @ 2.13GHz           | 1         | 0.45%   |
| Intel Pentium CPU N4200 @ 1.10GHz           | 1         | 0.45%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 1         | 0.45%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 1         | 0.45%   |
| Intel Pentium CPU N3530 @ 2.16GHz           | 1         | 0.45%   |
| Intel Pentium CPU G620 @ 2.60GHz            | 1         | 0.45%   |
| Intel Pentium CPU G3260 @ 3.30GHz           | 1         | 0.45%   |
| Intel Pentium CPU B960 @ 2.20GHz            | 1         | 0.45%   |
| Intel Pentium CPU B950 @ 2.10GHz            | 1         | 0.45%   |
| Intel Pentium CPU 6405U @ 2.40GHz           | 1         | 0.45%   |
| Intel Pentium 3556U @ 1.70GHz               | 1         | 0.45%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 0.45%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1         | 0.45%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 1         | 0.45%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1         | 0.45%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1         | 0.45%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 0.45%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1         | 0.45%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 0.45%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 0.45%   |
| Intel Core i7-5557U CPU @ 3.10GHz           | 1         | 0.45%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 1         | 0.45%   |
| Intel Core i7-4930K CPU @ 3.40GHz           | 1         | 0.45%   |
| Intel Core i7-4850HQ CPU @ 2.30GHz          | 1         | 0.45%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1         | 0.45%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1         | 0.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 58        | 26.36%  |
| Intel Core i7           | 39        | 17.73%  |
| Intel Core i3           | 19        | 8.64%   |
| Other                   | 15        | 6.82%   |
| Intel Celeron           | 14        | 6.36%   |
| Intel Pentium           | 11        | 5%      |
| AMD Ryzen 7             | 11        | 5%      |
| AMD Ryzen 5             | 11        | 5%      |
| Intel Core 2 Duo        | 7         | 3.18%   |
| Intel Xeon              | 5         | 2.27%   |
| AMD FX                  | 3         | 1.36%   |
| Intel Pentium Silver    | 2         | 0.91%   |
| Intel Pentium Dual-Core | 2         | 0.91%   |
| AMD Ryzen 9             | 2         | 0.91%   |
| AMD A8                  | 2         | 0.91%   |
| AMD A6                  | 2         | 0.91%   |
| AMD A4                  | 2         | 0.91%   |
| Intel Pentium Dual      | 1         | 0.45%   |
| Intel Core 2 Quad       | 1         | 0.45%   |
| Intel Core 2            | 1         | 0.45%   |
| Intel Celeron M         | 1         | 0.45%   |
| AMD Ryzen 7 PRO         | 1         | 0.45%   |
| AMD Ryzen 5 PRO         | 1         | 0.45%   |
| AMD Ryzen 3             | 1         | 0.45%   |
| AMD Phenom II X4        | 1         | 0.45%   |
| AMD Phenom II           | 1         | 0.45%   |
| AMD Phenom              | 1         | 0.45%   |
| AMD E1                  | 1         | 0.45%   |
| AMD C-60                | 1         | 0.45%   |
| AMD C-50                | 1         | 0.45%   |
| AMD Athlon II X4        | 1         | 0.45%   |
| AMD A10                 | 1         | 0.45%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 100       | 45.45%  |
| 4      | 72        | 32.73%  |
| 6      | 23        | 10.45%  |
| 8      | 17        | 7.73%   |
| 12     | 4         | 1.82%   |
| 1      | 3         | 1.36%   |
| 3      | 1         | 0.45%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 217       | 98.64%  |
| 2      | 3         | 1.36%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 150       | 68.18%  |
| 1      | 70        | 31.82%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 220       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x206a7    | 21        | 9.42%   |
| Unknown    | 17        | 7.62%   |
| 0x306c3    | 12        | 5.38%   |
| 0x306a9    | 12        | 5.38%   |
| 0x806c1    | 11        | 4.93%   |
| 0x406e3    | 10        | 4.48%   |
| 0x20655    | 7         | 3.14%   |
| 0x806ea    | 6         | 2.69%   |
| 0x40651    | 6         | 2.69%   |
| 0x20652    | 6         | 2.69%   |
| 0x1067a    | 6         | 2.69%   |
| 0x906e9    | 5         | 2.24%   |
| 0x806e9    | 5         | 2.24%   |
| 0x306d4    | 5         | 2.24%   |
| 0x08701021 | 5         | 2.24%   |
| 0x906ea    | 4         | 1.79%   |
| 0x30678    | 4         | 1.79%   |
| 0xa0671    | 3         | 1.35%   |
| 0x806ec    | 3         | 1.35%   |
| 0x706a8    | 3         | 1.35%   |
| 0x6fb      | 3         | 1.35%   |
| 0x406c4    | 3         | 1.35%   |
| 0x08600104 | 3         | 1.35%   |
| 0x0800820d | 3         | 1.35%   |
| 0xa0655    | 2         | 0.9%    |
| 0xa0653    | 2         | 0.9%    |
| 0x806eb    | 2         | 0.9%    |
| 0x706a1    | 2         | 0.9%    |
| 0x6fd      | 2         | 0.9%    |
| 0x406c3    | 2         | 0.9%    |
| 0x40661    | 2         | 0.9%    |
| 0x206d7    | 2         | 0.9%    |
| 0x106a5    | 2         | 0.9%    |
| 0x08701013 | 2         | 0.9%    |
| 0x08101007 | 2         | 0.9%    |
| 0x07030105 | 2         | 0.9%    |
| 0x0600611a | 2         | 0.9%    |
| 0x06000852 | 2         | 0.9%    |
| 0xa0652    | 1         | 0.45%   |
| 0x906ed    | 1         | 0.45%   |
| 0x906eb    | 1         | 0.45%   |
| 0x806d1    | 1         | 0.45%   |
| 0x706e5    | 1         | 0.45%   |
| 0x6fa      | 1         | 0.45%   |
| 0x506e3    | 1         | 0.45%   |
| 0x506c9    | 1         | 0.45%   |
| 0x40671    | 1         | 0.45%   |
| 0x306e4    | 1         | 0.45%   |
| 0x206c2    | 1         | 0.45%   |
| 0x106e5    | 1         | 0.45%   |
| 0x10676    | 1         | 0.45%   |
| 0x0a50000c | 1         | 0.45%   |
| 0x0a201016 | 1         | 0.45%   |
| 0x08608103 | 1         | 0.45%   |
| 0x08600106 | 1         | 0.45%   |
| 0x08600103 | 1         | 0.45%   |
| 0x08108109 | 1         | 0.45%   |
| 0x08101016 | 1         | 0.45%   |
| 0x0810100b | 1         | 0.45%   |
| 0x0800111c | 1         | 0.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 31        | 14.09%  |
| SandyBridge   | 26        | 11.82%  |
| Haswell       | 20        | 9.09%   |
| Westmere      | 14        | 6.36%   |
| Zen 2         | 13        | 5.91%   |
| IvyBridge     | 13        | 5.91%   |
| Skylake       | 12        | 5.45%   |
| TigerLake     | 11        | 5%      |
| Silvermont    | 10        | 4.55%   |
| Penryn        | 7         | 3.18%   |
| Core          | 6         | 2.73%   |
| Broadwell     | 6         | 2.73%   |
| Zen+          | 5         | 2.27%   |
| Zen           | 5         | 2.27%   |
| Icelake       | 5         | 2.27%   |
| Goldmont plus | 5         | 2.27%   |
| CometLake     | 5         | 2.27%   |
| K10           | 4         | 1.82%   |
| Zen 3         | 3         | 1.36%   |
| Piledriver    | 3         | 1.36%   |
| Nehalem       | 3         | 1.36%   |
| Excavator     | 3         | 1.36%   |
| Puma          | 2         | 0.91%   |
| Jaguar        | 2         | 0.91%   |
| Bobcat        | 2         | 0.91%   |
| Unknown       | 2         | 0.91%   |
| Goldmont      | 1         | 0.45%   |
| Bulldozer     | 1         | 0.45%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Intel            | 142       | 55.25%  |
| AMD              | 57        | 22.18%  |
| Nvidia           | 56        | 21.79%  |
| Conexant Systems | 1         | 0.39%   |
| ATI Technologies | 1         | 0.39%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 19        | 7.25%   |
| Intel Core Processor Integrated Graphics Controller                                      | 12        | 4.58%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 11        | 4.2%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 10        | 3.82%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 9         | 3.44%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 8         | 3.05%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 6         | 2.29%   |
| Intel UHD Graphics 620                                                                   | 6         | 2.29%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 2.29%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 2.29%   |
| AMD Renoir                                                                               | 6         | 2.29%   |
| Intel HD Graphics 620                                                                    | 5         | 1.91%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1.53%   |
| Intel HD Graphics 630                                                                    | 4         | 1.53%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 1.53%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 4         | 1.53%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 4         | 1.53%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 1.15%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.15%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.15%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 2         | 0.76%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 0.76%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.76%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 2         | 0.76%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 2         | 0.76%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 2         | 0.76%   |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                                              | 2         | 0.76%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 2         | 0.76%   |
| Nvidia GA102 [GeForce RTX 3080]                                                          | 2         | 0.76%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 0.76%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 0.76%   |
| Intel Tiger Lake UHD Graphics                                                            | 2         | 0.76%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.76%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 0.76%   |
| Intel HD Graphics 6000                                                                   | 2         | 0.76%   |
| Intel HD Graphics 5500                                                                   | 2         | 0.76%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 0.76%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 0.76%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 0.76%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 0.76%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 2         | 0.76%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 2         | 0.76%   |
| AMD RS780D [Radeon HD 3300]                                                              | 2         | 0.76%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 0.76%   |
| AMD Oland PRO [Radeon R7 240/340]                                                        | 2         | 0.76%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 0.76%   |
| AMD Cezanne                                                                              | 2         | 0.76%   |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                                     | 2         | 0.76%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.38%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.38%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 1         | 0.38%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 0.38%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 1         | 0.38%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 1         | 0.38%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.38%   |
| Nvidia GP108BM [GeForce MX250]                                                           | 1         | 0.38%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 0.38%   |
| Nvidia GP107M [GeForce MX350]                                                            | 1         | 0.38%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                    | 1         | 0.38%   |
| Nvidia GP107GL [Quadro P1000]                                                            | 1         | 0.38%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| 1 x Intel                      | 109       | 49.55%  |
| 1 x AMD                        | 45        | 20.45%  |
| 1 x Nvidia                     | 28        | 12.73%  |
| Intel + Nvidia                 | 26        | 11.82%  |
| Intel + AMD                    | 6         | 2.73%   |
| 2 x AMD                        | 3         | 1.36%   |
| AMD + Nvidia                   | 2         | 0.91%   |
| 2 x AMD + 1 x Conexant Systems | 1         | 0.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 193       | 86.55%  |
| Proprietary | 27        | 12.11%  |
| Unknown     | 3         | 1.35%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 128       | 57.66%  |
| 1.01-2.0   | 23        | 10.36%  |
| 0.01-0.5   | 19        | 8.56%   |
| 0.51-1.0   | 18        | 8.11%   |
| 3.01-4.0   | 15        | 6.76%   |
| 7.01-8.0   | 13        | 5.86%   |
| 5.01-6.0   | 2         | 0.9%    |
| 2.01-3.0   | 2         | 0.9%    |
| 8.01-16.0  | 2         | 0.9%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 30        | 12.55%  |
| Samsung Electronics     | 26        | 10.88%  |
| Chimei Innolux          | 24        | 10.04%  |
| LG Display              | 21        | 8.79%   |
| BOE                     | 20        | 8.37%   |
| Apple                   | 15        | 6.28%   |
| Hewlett-Packard         | 13        | 5.44%   |
| Goldstar                | 10        | 4.18%   |
| Lenovo                  | 8         | 3.35%   |
| Dell                    | 8         | 3.35%   |
| BenQ                    | 7         | 2.93%   |
| Acer                    | 7         | 2.93%   |
| AOC                     | 6         | 2.51%   |
| Ancor Communications    | 5         | 2.09%   |
| Sharp                   | 4         | 1.67%   |
| Chi Mei Optoelectronics | 4         | 1.67%   |
| Vizio                   | 3         | 1.26%   |
| ViewSonic               | 3         | 1.26%   |
| CPT                     | 3         | 1.26%   |
| MSI                     | 2         | 0.84%   |
| LG Electronics          | 2         | 0.84%   |
| CSO                     | 2         | 0.84%   |
| Toshiba                 | 1         | 0.42%   |
| TBD                     | 1         | 0.42%   |
| SKY                     | 1         | 0.42%   |
| Seiko/Epson             | 1         | 0.42%   |
| Philips                 | 1         | 0.42%   |
| PANDA                   | 1         | 0.42%   |
| NEC Computers           | 1         | 0.42%   |
| LGD                     | 1         | 0.42%   |
| LG Philips              | 1         | 0.42%   |
| Lenovo Group Limited    | 1         | 0.42%   |
| HOP                     | 1         | 0.42%   |
| HannStar                | 1         | 0.42%   |
| Grundig                 | 1         | 0.42%   |
| Denver                  | 1         | 0.42%   |
| AUS                     | 1         | 0.42%   |
| Unknown                 | 1         | 0.42%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch           | 5         | 2.03%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 2         | 0.81%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 2         | 0.81%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 340x190mm 15.3-inch         | 2         | 0.81%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 2         | 0.81%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 2         | 0.81%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch | 2         | 0.81%   |
| AU Optronics LCD Monitor AUO413D 1920x1080 309x173mm 13.9-inch           | 2         | 0.81%   |
| AU Optronics LCD Monitor AUO235C 1366x768 260x140mm 11.6-inch            | 2         | 0.81%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 2         | 0.81%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 2         | 0.81%   |
| Apple Color LCD APPA014 2560x1600 286x179mm 13.3-inch                    | 2         | 0.81%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                     | 2         | 0.81%   |
| Apple Color LCD APP9CC7 1280x800 290x180mm 13.4-inch                     | 2         | 0.81%   |
| Apple Color LCD APP9CA4 1440x900 331x207mm 15.4-inch                     | 2         | 0.81%   |
| AOC 2369M AOC2369 1920x1080 509x286mm 23.0-inch                          | 2         | 0.81%   |
| AOC 22V2WG5 AOC2202 1920x1080 476x268mm 21.5-inch                        | 2         | 0.81%   |
| Vizio L37 HD VIZ1300 1366x768 820x460mm 37.0-inch                        | 1         | 0.41%   |
| Vizio E321VL VIZ0083 1366x768 700x400mm 31.7-inch                        | 1         | 0.41%   |
| Vizio E190VA VIZ0067 1360x768 410x230mm 18.5-inch                        | 1         | 0.41%   |
| ViewSonic VA2445 SERIES VSC712E 1920x1080 521x293mm 23.5-inch            | 1         | 0.41%   |
| ViewSonic VA2055 Series VSC3C31 1920x1080 435x239mm 19.5-inch            | 1         | 0.41%   |
| ViewSonic LCD Monitor VSC732E 1920x1080 520x290mm 23.4-inch              | 1         | 0.41%   |
| Toshiba TV TSB0206 1920x1080 886x498mm 40.0-inch                         | 1         | 0.41%   |
| TBD HDMI TBD3148 1600x900 344x193mm 15.5-inch                            | 1         | 0.41%   |
| SKY TV-monitor SKY0001 1920x1080 697x392mm 31.5-inch                     | 1         | 0.41%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch                  | 1         | 0.41%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                  | 1         | 0.41%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                  | 1         | 0.41%   |
| Sharp LCD Monitor SHP1420 1920x1080 290x170mm 13.2-inch                  | 1         | 0.41%   |
| Seiko/Epson LCD Monitor 1920x1080                                        | 1         | 0.41%   |
| Samsung Electronics U32J59x SAM0F33 3840x2160 697x392mm 31.5-inch        | 1         | 0.41%   |
| Samsung Electronics U28H75x SAM0E00 3840x2160 607x345mm 27.5-inch        | 1         | 0.41%   |
| Samsung Electronics U28H75x SAM0DFF 3840x2160 608x345mm 27.5-inch        | 1         | 0.41%   |
| Samsung Electronics SyncMaster SAM0428 1680x1050 459x296mm 21.5-inch     | 1         | 0.41%   |
| Samsung Electronics S27D850 SAM0BC8 2560x1440 598x336mm 27.0-inch        | 1         | 0.41%   |
| Samsung Electronics S24D332 SAM0F5E 1920x1080 531x299mm 24.0-inch        | 1         | 0.41%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch        | 1         | 0.41%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 480x270mm 21.7-inch        | 1         | 0.41%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch        | 1         | 0.41%   |
| Samsung Electronics S22C200 SAM09B6 1920x1080 477x268mm 21.5-inch        | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC5842 1366x768 309x174mm 14.0-inch     | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC364D 1600x900 382x214mm 17.2-inch     | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC3542 2160x1440 250x170mm 11.9-inch    | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 344x194mm 15.5-inch     | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch     | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch     | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 340x190mm 15.3-inch     | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SDC4E42 1366x768 309x174mm 14.0-inch     | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SDC3853 2736x1824 260x173mm 12.3-inch    | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SAM705B 1920x1080 1210x680mm 54.6-inch   | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SAM0B30 1920x1080 890x500mm 40.2-inch    | 1         | 0.41%   |
| Samsung Electronics LCD Monitor S24F350 5760x1080                        | 1         | 0.41%   |
| Samsung Electronics LCD Monitor S24F350                                  | 1         | 0.41%   |
| Samsung Electronics LCD Monitor C24F390 1920x1080                        | 1         | 0.41%   |
| Samsung Electronics C49J89x SAM0F21 3840x1080 1196x336mm 48.9-inch       | 1         | 0.41%   |
| Samsung Electronics C49HG9x SAM0E5D 3840x1080 1200x340mm 49.1-inch       | 1         | 0.41%   |
| Samsung Electronics C27F591 SAM0D36 1920x1080 598x336mm 27.0-inch        | 1         | 0.41%   |
| Philips PHL 223V7 PHLC154 1920x1080 476x268mm 21.5-inch                  | 1         | 0.41%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 91        | 39.91%  |
| 1366x768 (WXGA)    | 51        | 22.37%  |
| 1600x900 (HD+)     | 14        | 6.14%   |
| 3840x2160 (4K)     | 12        | 5.26%   |
| 2560x1440 (QHD)    | 9         | 3.95%   |
| 1280x800 (WXGA)    | 9         | 3.95%   |
| 1440x900 (WXGA+)   | 8         | 3.51%   |
| 2560x1600          | 5         | 2.19%   |
| 1680x1050 (WSXGA+) | 5         | 2.19%   |
| 1920x1200 (WUXGA)  | 4         | 1.75%   |
| Unknown            | 4         | 1.75%   |
| 3840x1080          | 3         | 1.32%   |
| 2560x1080          | 3         | 1.32%   |
| 5760x1080          | 1         | 0.44%   |
| 5120x1440          | 1         | 0.44%   |
| 4480x1440          | 1         | 0.44%   |
| 3840x2400          | 1         | 0.44%   |
| 3440x1440          | 1         | 0.44%   |
| 3000x2000          | 1         | 0.44%   |
| 2880x1800          | 1         | 0.44%   |
| 2736x1824          | 1         | 0.44%   |
| 2160x1440          | 1         | 0.44%   |
| 1280x1024 (SXGA)   | 1         | 0.44%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 63        | 26.69%  |
| 13      | 31        | 13.14%  |
| 14      | 19        | 8.05%   |
| 27      | 18        | 7.63%   |
| 21      | 16        | 6.78%   |
| 23      | 12        | 5.08%   |
| Unknown | 12        | 5.08%   |
| 17      | 11        | 4.66%   |
| 12      | 8         | 3.39%   |
| 24      | 7         | 2.97%   |
| 11      | 6         | 2.54%   |
| 20      | 4         | 1.69%   |
| 19      | 4         | 1.69%   |
| 31      | 3         | 1.27%   |
| 72      | 2         | 0.85%   |
| 49      | 2         | 0.85%   |
| 40      | 2         | 0.85%   |
| 34      | 2         | 0.85%   |
| 10      | 2         | 0.85%   |
| 74      | 1         | 0.42%   |
| 54      | 1         | 0.42%   |
| 37      | 1         | 0.42%   |
| 33      | 1         | 0.42%   |
| 32      | 1         | 0.42%   |
| 29      | 1         | 0.42%   |
| 28      | 1         | 0.42%   |
| 26      | 1         | 0.42%   |
| 25      | 1         | 0.42%   |
| 22      | 1         | 0.42%   |
| 18      | 1         | 0.42%   |
| 16      | 1         | 0.42%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 96        | 41.38%  |
| 201-300     | 33        | 14.22%  |
| 501-600     | 32        | 13.79%  |
| 401-500     | 25        | 10.78%  |
| 351-400     | 12        | 5.17%   |
| Unknown     | 12        | 5.17%   |
| 601-700     | 9         | 3.88%   |
| 701-800     | 4         | 1.72%   |
| 801-900     | 3         | 1.29%   |
| 1501-2000   | 3         | 1.29%   |
| 1001-1500   | 3         | 1.29%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 162       | 75%     |
| 16/10   | 30        | 13.89%  |
| Unknown | 12        | 5.56%   |
| 3/2     | 5         | 2.31%   |
| 21/9    | 4         | 1.85%   |
| 32/9    | 2         | 0.93%   |
| 5/4     | 1         | 0.46%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 63        | 26.81%  |
| 81-90          | 37        | 15.74%  |
| 201-250        | 27        | 11.49%  |
| 301-350        | 20        | 8.51%   |
| 151-200        | 14        | 5.96%   |
| 71-80          | 13        | 5.53%   |
| Unknown        | 12        | 5.11%   |
| 61-70          | 8         | 3.4%    |
| 351-500        | 7         | 2.98%   |
| 121-130        | 7         | 2.98%   |
| 51-60          | 6         | 2.55%   |
| 501-1000       | 5         | 2.13%   |
| More than 1000 | 4         | 1.7%    |
| 251-300        | 4         | 1.7%    |
| 131-140        | 3         | 1.28%   |
| 41-50          | 2         | 0.85%   |
| 141-150        | 2         | 0.85%   |
| 111-120        | 1         | 0.43%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 71        | 31.42%  |
| 101-120       | 68        | 30.09%  |
| 51-100        | 52        | 23.01%  |
| 161-240       | 13        | 5.75%   |
| Unknown       | 12        | 5.31%   |
| 1-50          | 6         | 2.65%   |
| More than 240 | 4         | 1.77%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 190       | 85.97%  |
| 2     | 20        | 9.05%   |
| 3     | 7         | 3.17%   |
| 0     | 4         | 1.81%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 124       | 36.26%  |
| Intel                             | 92        | 26.9%   |
| Qualcomm Atheros                  | 34        | 9.94%   |
| Broadcom                          | 32        | 9.36%   |
| TP-Link                           | 8         | 2.34%   |
| Broadcom Limited                  | 8         | 2.34%   |
| Ralink Technology                 | 6         | 1.75%   |
| Xiaomi                            | 4         | 1.17%   |
| Ralink                            | 4         | 1.17%   |
| Marvell Technology Group          | 4         | 1.17%   |
| Sierra Wireless                   | 3         | 0.88%   |
| MediaTek                          | 3         | 0.88%   |
| Samsung Electronics               | 2         | 0.58%   |
| Hewlett-Packard                   | 2         | 0.58%   |
| Qualcomm                          | 1         | 0.29%   |
| OPPO Electronics                  | 1         | 0.29%   |
| Nvidia                            | 1         | 0.29%   |
| NetGear                           | 1         | 0.29%   |
| NEC Computers                     | 1         | 0.29%   |
| Mercucys                          | 1         | 0.29%   |
| Linksys                           | 1         | 0.29%   |
| Huawei Technologies               | 1         | 0.29%   |
| Google                            | 1         | 0.29%   |
| Ericsson Business Mobile Networks | 1         | 0.29%   |
| Edimax Technology                 | 1         | 0.29%   |
| DisplayLink                       | 1         | 0.29%   |
| D-Link                            | 1         | 0.29%   |
| Attansic Technology               | 1         | 0.29%   |
| ASUSTek Computer                  | 1         | 0.29%   |
| ASIX Electronics                  | 1         | 0.29%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 79        | 19.6%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 15        | 3.72%   |
| Intel Wi-Fi 6 AX200                                               | 12        | 2.98%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 2.48%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 8         | 1.99%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 7         | 1.74%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 7         | 1.74%   |
| Intel Wi-Fi 6 AX201                                               | 7         | 1.74%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 6         | 1.49%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 6         | 1.49%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 6         | 1.49%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 1.24%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 1.24%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 1.24%   |
| Intel Wireless 7265                                               | 5         | 1.24%   |
| Intel I211 Gigabit Network Connection                             | 5         | 1.24%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 1.24%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 5         | 1.24%   |
| Ralink MT7601U Wireless Adapter                                   | 4         | 0.99%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 0.99%   |
| Intel Wireless 8265 / 8275                                        | 4         | 0.99%   |
| Intel Wireless 8260                                               | 4         | 0.99%   |
| Intel Wireless 7260                                               | 4         | 0.99%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 0.99%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 0.99%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 4         | 0.99%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.74%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 3         | 0.74%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 3         | 0.74%   |
| Intel Wireless 3160                                               | 3         | 0.74%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 3         | 0.74%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.74%   |
| Intel 82574L Gigabit Network Connection                           | 3         | 0.74%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 3         | 0.74%   |
| Broadcom BCM43142 802.11b/g/n                                     | 3         | 0.74%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 2         | 0.5%    |
| TP-Link 802.11ac NIC                                              | 2         | 0.5%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 0.5%    |
| Realtek RTL8723DE Wireless Network Adapter                        | 2         | 0.5%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 2         | 0.5%    |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.5%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 2         | 0.5%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.5%    |
| MediaTek WP5 Pro                                                  | 2         | 0.5%    |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                 | 2         | 0.5%    |
| Intel Wireless 3165                                               | 2         | 0.5%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 2         | 0.5%    |
| Intel Ethernet Connection I219-V                                  | 2         | 0.5%    |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.5%    |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.5%    |
| Intel Ethernet Connection (2) I219-V                              | 2         | 0.5%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 0.5%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 2         | 0.5%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 0.5%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 0.5%    |
| Intel Centrino Advanced-N 6235                                    | 2         | 0.5%    |
| Intel Centrino Advanced-N 6200                                    | 2         | 0.5%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 0.5%    |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 0.5%    |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 2         | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 74        | 36.27%  |
| Realtek Semiconductor    | 39        | 19.12%  |
| Qualcomm Atheros         | 28        | 13.73%  |
| Broadcom                 | 28        | 13.73%  |
| TP-Link                  | 8         | 3.92%   |
| Ralink Technology        | 6         | 2.94%   |
| Broadcom Limited         | 6         | 2.94%   |
| Ralink                   | 4         | 1.96%   |
| Sierra Wireless          | 3         | 1.47%   |
| Marvell Technology Group | 2         | 0.98%   |
| NetGear                  | 1         | 0.49%   |
| Mercucys                 | 1         | 0.49%   |
| MEDIATEK                 | 1         | 0.49%   |
| Edimax Technology        | 1         | 0.49%   |
| D-Link                   | 1         | 0.49%   |
| ASUSTek Computer         | 1         | 0.49%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 12        | 5.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 8         | 3.92%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 7         | 3.43%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 7         | 3.43%   |
| Intel Wi-Fi 6 AX201                                            | 7         | 3.43%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 6         | 2.94%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 6         | 2.94%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 6         | 2.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 2.45%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 5         | 2.45%   |
| Intel Wireless 7265                                            | 5         | 2.45%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 5         | 2.45%   |
| Ralink MT7601U Wireless Adapter                                | 4         | 1.96%   |
| Intel Wireless 8265 / 8275                                     | 4         | 1.96%   |
| Intel Wireless 8260                                            | 4         | 1.96%   |
| Intel Wireless 7260                                            | 4         | 1.96%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 1.96%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 4         | 1.96%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 3         | 1.47%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 3         | 1.47%   |
| Intel Wireless 3160                                            | 3         | 1.47%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 3         | 1.47%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 3         | 1.47%   |
| Broadcom BCM43142 802.11b/g/n                                  | 3         | 1.47%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 2         | 0.98%   |
| TP-Link 802.11ac NIC                                           | 2         | 0.98%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 2         | 0.98%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 2         | 0.98%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 2         | 0.98%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 2         | 0.98%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 0.98%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless              | 2         | 0.98%   |
| Intel Wireless 3165                                            | 2         | 0.98%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 2         | 0.98%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 0.98%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 2         | 0.98%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 0.98%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 0.98%   |
| Intel Centrino Advanced-N 6235                                 | 2         | 0.98%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 0.98%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 2         | 0.98%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 2         | 0.98%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 2         | 0.98%   |
| TP-Link 802.11ac WLAN Adapter                                  | 1         | 0.49%   |
| Sierra Wireless MC8305 Modem                                   | 1         | 0.49%   |
| Sierra Wireless EM7455                                         | 1         | 0.49%   |
| Sierra Wireless EM7305 Modem                                   | 1         | 0.49%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 0.49%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 1         | 0.49%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 1         | 0.49%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1         | 0.49%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 0.49%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 0.49%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.49%   |
| Realtek RTL8187 Wireless Adapter                               | 1         | 0.49%   |
| Realtek 802.11ac+Bluetooth 5.0 Adapter                         | 1         | 0.49%   |
| Ralink RT5370 Wireless Adapter                                 | 1         | 0.49%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1         | 0.49%   |
| Ralink RT5592 PCIe Wireless Network Adapter                    | 1         | 0.49%   |
| Ralink RT2800 802.11n PCI                                      | 1         | 0.49%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 103       | 53.93%  |
| Intel                    | 43        | 22.51%  |
| Broadcom                 | 14        | 7.33%   |
| Qualcomm Atheros         | 11        | 5.76%   |
| Xiaomi                   | 4         | 2.09%   |
| Samsung Electronics      | 2         | 1.05%   |
| MediaTek                 | 2         | 1.05%   |
| Marvell Technology Group | 2         | 1.05%   |
| Broadcom Limited         | 2         | 1.05%   |
| Qualcomm                 | 1         | 0.52%   |
| OPPO Electronics         | 1         | 0.52%   |
| Nvidia                   | 1         | 0.52%   |
| Linksys                  | 1         | 0.52%   |
| Google                   | 1         | 0.52%   |
| DisplayLink              | 1         | 0.52%   |
| Attansic Technology      | 1         | 0.52%   |
| ASIX Electronics         | 1         | 0.52%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 79        | 40.72%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 15        | 7.73%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 5.15%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 2.58%   |
| Intel I211 Gigabit Network Connection                             | 5         | 2.58%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 2.58%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 2.06%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 2.06%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 1.55%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.55%   |
| Intel 82574L Gigabit Network Connection                           | 3         | 1.55%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 1.03%   |
| MediaTek WP5 Pro                                                  | 2         | 1.03%   |
| Intel Ethernet Connection I219-V                                  | 2         | 1.03%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.03%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.03%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 1.03%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 1.03%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 2         | 1.03%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 2         | 1.03%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 1.03%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.52%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.52%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.52%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.52%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.52%   |
| Qualcomm Mobile Router                                            | 1         | 0.52%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.52%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.52%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.52%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.52%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.52%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.52%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.52%   |
| OPPO realme X50 Pro 5G                                            | 1         | 0.52%   |
| Nvidia MCP77 Ethernet                                             | 1         | 0.52%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.52%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 0.52%   |
| Linksys Gigabit Ethernet Adapter                                  | 1         | 0.52%   |
| Intel PRO/100 VE Network Connection                               | 1         | 0.52%   |
| Intel Ethernet Controller I225-V                                  | 1         | 0.52%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.52%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.52%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.52%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.52%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.52%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 0.52%   |
| Intel Ethernet Connection (14) I219-V                             | 1         | 0.52%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.52%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.52%   |
| Google Nexus/Pixel Device (tether)                                | 1         | 0.52%   |
| DisplayLink USB-C Triple-4K Dock                                  | 1         | 0.52%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 0.52%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 0.52%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.52%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1         | 0.52%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 1         | 0.52%   |
| Attansic AR8152 v2.0 Fast Ethernet                                | 1         | 0.52%   |
| ASIX AX88772B                                                     | 1         | 0.52%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 188       | 50.4%   |
| Ethernet | 180       | 48.26%  |
| Modem    | 4         | 1.07%   |
| Unknown  | 1         | 0.27%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 170       | 51.05%  |
| Ethernet | 163       | 48.95%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 126       | 57.27%  |
| 1     | 90        | 40.91%  |
| 3     | 3         | 1.36%   |
| 0     | 1         | 0.45%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 164       | 74.21%  |
| Yes  | 57        | 25.79%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 62        | 38.04%  |
| Realtek Semiconductor           | 23        | 14.11%  |
| Apple                           | 17        | 10.43%  |
| Qualcomm Atheros Communications | 15        | 9.2%    |
| Broadcom                        | 13        | 7.98%   |
| Cambridge Silicon Radio         | 9         | 5.52%   |
| Lite-On Technology              | 5         | 3.07%   |
| Foxconn / Hon Hai               | 4         | 2.45%   |
| IMC Networks                    | 3         | 1.84%   |
| Ralink                          | 2         | 1.23%   |
| Marvell Semiconductor           | 2         | 1.23%   |
| Dell                            | 2         | 1.23%   |
| Toshiba                         | 1         | 0.61%   |
| Realtek                         | 1         | 0.61%   |
| Qcom                            | 1         | 0.61%   |
| Hewlett-Packard                 | 1         | 0.61%   |
| Belkin Components               | 1         | 0.61%   |
| ASUSTek Computer                | 1         | 0.61%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                              | 27        | 16.56%  |
| Intel Bluetooth wireless interface                  | 16        | 9.82%   |
| Realtek Bluetooth Radio                             | 13        | 7.98%   |
| Intel AX200 Bluetooth                               | 12        | 7.36%   |
| Realtek  Bluetooth 4.2 Adapter                      | 9         | 5.52%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 9         | 5.52%   |
| Apple Bluetooth USB Host Controller                 | 8         | 4.91%   |
| Apple Bluetooth Host Controller                     | 7         | 4.29%   |
| Qualcomm Atheros  Bluetooth Device                  | 6         | 3.68%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 6         | 3.68%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 3         | 1.84%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 3         | 1.84%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 1.84%   |
| Ralink RT3290 Bluetooth                             | 2         | 1.23%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 1.23%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 1.23%   |
| IMC Networks Bluetooth Radio                        | 2         | 1.23%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 1.23%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 2         | 1.23%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 1.23%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.61%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.61%   |
| Realtek Bluetooth Radio                             | 1         | 0.61%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.61%   |
| Qcom Broadcom Bluetooth USB                         | 1         | 0.61%   |
| Marvell Bluetooth and Wireless LAN Composite Device | 1         | 0.61%   |
| Marvell Bluetooth and Wireless LAN Composite        | 1         | 0.61%   |
| Lite-On Wireless_Device                             | 1         | 0.61%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 0.61%   |
| Lite-On Qualcomm Atheros Bluetooth                  | 1         | 0.61%   |
| Lite-On Bluetooth Device                            | 1         | 0.61%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.61%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.61%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.61%   |
| IMC Networks BCM20702A0                             | 1         | 0.61%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 0.61%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 0.61%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 0.61%   |
| Dell DW375 Bluetooth Module                         | 1         | 0.61%   |
| Dell Broadcom BCM20702A0 Bluetooth                  | 1         | 0.61%   |
| Broadcom HP Portable Valentine                      | 1         | 0.61%   |
| Broadcom Bluetooth 3.0 Dongle                       | 1         | 0.61%   |
| Broadcom BCM20702A0                                 | 1         | 0.61%   |
| Belkin Components Bluetooth Mini Dongle             | 1         | 0.61%   |
| ASUS Bluetooth Radio                                | 1         | 0.61%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 0.61%   |
| Apple Bluetooth HCI                                 | 1         | 0.61%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 173       | 58.05%  |
| AMD                                  | 58        | 19.46%  |
| Nvidia                               | 40        | 13.42%  |
| C-Media Electronics                  | 6         | 2.01%   |
| Logitech                             | 3         | 1.01%   |
| Generalplus Technology               | 3         | 1.01%   |
| Creative Labs                        | 3         | 1.01%   |
| JMTek                                | 2         | 0.67%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.34%   |
| TEAC                                 | 1         | 0.34%   |
| Razer USA                            | 1         | 0.34%   |
| HECATE G2 GAMING HEADSET             | 1         | 0.34%   |
| GN Netcom                            | 1         | 0.34%   |
| Focusrite-Novation                   | 1         | 0.34%   |
| Creative Technology                  | 1         | 0.34%   |
| Corsair                              | 1         | 0.34%   |
| ATI Technologies                     | 1         | 0.34%   |
| ASUSTek Computer                     | 1         | 0.34%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 22        | 6.16%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 22        | 6.16%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 15        | 4.2%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 14        | 3.92%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 14        | 3.92%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 13        | 3.64%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 11        | 3.08%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 9         | 2.52%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 8         | 2.24%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 8         | 2.24%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 8         | 2.24%   |
| Intel Cannon Lake PCH cAVS                                                                        | 7         | 1.96%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6         | 1.68%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 1.68%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 1.68%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 6         | 1.68%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 1.68%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 1.68%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 5         | 1.4%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 5         | 1.4%    |
| Intel Tiger Lake-H HD Audio Controller                                                            | 5         | 1.4%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 1.4%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 1.4%    |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 1.4%    |
| AMD FCH Azalia Controller                                                                         | 5         | 1.4%    |
| Nvidia GA104 High Definition Audio Controller                                                     | 4         | 1.12%   |
| Intel CM238 HD Audio Controller                                                                   | 4         | 1.12%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 1.12%   |
| Intel 200 Series PCH HD Audio                                                                     | 4         | 1.12%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 4         | 1.12%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 0.84%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.84%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 0.84%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 0.84%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 0.84%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 3         | 0.84%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3         | 0.84%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 0.84%   |
| Generalplus Technology USB Audio Device                                                           | 3         | 0.84%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 3         | 0.84%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 0.84%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3         | 0.84%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 3         | 0.84%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 2         | 0.56%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 2         | 0.56%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 2         | 0.56%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.56%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 2         | 0.56%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 0.56%   |
| Intel Crystal Well HD Audio Controller                                                            | 2         | 0.56%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 0.56%   |
| Creative Labs CA0108/CA10300 [Sound Blaster Audigy Series]                                        | 2         | 0.56%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 0.56%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                                        | 2         | 0.56%   |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                                            | 2         | 0.56%   |
| Thesycon Systemsoftware & Consulting DX3 Pro                                                      | 1         | 0.28%   |
| TEAC TASCAM iXR                                                                                   | 1         | 0.28%   |
| Razer USA Razer USB Audio Controller                                                              | 1         | 0.28%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.28%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.28%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 19        | 25.68%  |
| SK Hynix            | 13        | 17.57%  |
| Kingston            | 11        | 14.86%  |
| Micron Technology   | 10        | 13.51%  |
| Unknown             | 3         | 4.05%   |
| G.Skill             | 3         | 4.05%   |
| Crucial             | 3         | 4.05%   |
| Ramaxel Technology  | 2         | 2.7%    |
| Corsair             | 2         | 2.7%    |
| A-DATA Technology   | 2         | 2.7%    |
| Toshiba             | 1         | 1.35%   |
| Qimonda             | 1         | 1.35%   |
| Neo Forza           | 1         | 1.35%   |
| Nanya Technology    | 1         | 1.35%   |
| Kllisre             | 1         | 1.35%   |
| GSkill              | 1         | 1.35%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s    | 3         | 3.9%    |
| SK Hynix RAM HMA851S6CJR6N-VK 4096MB SODIMM DDR4 2667MT/s   | 2         | 2.6%    |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s    | 2         | 2.6%    |
| Unknown RAM Module 4096MB Chip DDR4 2133MT/s                | 1         | 1.3%    |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                 | 1         | 1.3%    |
| Unknown RAM Module 1024MB SODIMM LPDDR4 2400MT/s            | 1         | 1.3%    |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s          | 1         | 1.3%    |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM 1066MT/s           | 1         | 1.3%    |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                | 1         | 1.3%    |
| SK Hynix RAM Module 4096MB SODIMM DDR3 1867MT/s             | 1         | 1.3%    |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 1.3%    |
| SK Hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s   | 1         | 1.3%    |
| SK Hynix RAM HMT325S6CFR8C-PB 2048MB SODIMM DDR3 1600MT/s   | 1         | 1.3%    |
| SK Hynix RAM HMT31GR7BFR4C-H9 8GB DIMM DDR3 1333MT/s        | 1         | 1.3%    |
| SK Hynix RAM HMAA2GS6CJR8N-XN 16384MB SODIMM DDR4 3200MT/s  | 1         | 1.3%    |
| SK Hynix RAM HMA851S6DJR6N-XN 4096MB SODIMM DDR4 3200MT/s   | 1         | 1.3%    |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s      | 1         | 1.3%    |
| SK Hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s   | 1         | 1.3%    |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 1         | 1.3%    |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s              | 1         | 1.3%    |
| Samsung RAM Module 8192MB DIMM DDR4 2666MT/s                | 1         | 1.3%    |
| Samsung RAM M471B5773DH0-CK0 2048MB SODIMM DDR3 1600MT/s    | 1         | 1.3%    |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s       | 1         | 1.3%    |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s       | 1         | 1.3%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s       | 1         | 1.3%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s       | 1         | 1.3%    |
| Samsung RAM M471B2873FHS-CF8 1GB SODIMM DDR3 1067MT/s       | 1         | 1.3%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s       | 1         | 1.3%    |
| Samsung RAM M471A2K43DB1-CWE 16384MB SODIMM DDR4 3200MT/s   | 1         | 1.3%    |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s      | 1         | 1.3%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s | 1         | 1.3%    |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2400MT/s       | 1         | 1.3%    |
| Samsung RAM M4 70T5663EH3-CF7 2GB SODIMM DDR2 800MT/s       | 1         | 1.3%    |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3200MT/s         | 1         | 1.3%    |
| Ramaxel RAM RMT3170EF68F9W1600 4GB SODIMM DDR3 1600MT/s     | 1         | 1.3%    |
| Ramaxel RAM RMSA3310NA86H9F-2666 4GB SODIMM DDR4 2667MT/s   | 1         | 1.3%    |
| Qimonda RAM 64T256020EDL2.5C2 2048MB SODIMM DDR2 2048MT/s   | 1         | 1.3%    |
| Neo Forza RAM NMUD380D81-1600D 8GB DIMM DDR3 1333MT/s       | 1         | 1.3%    |
| Nanya RAM Module 4GB DIMM DDR3 1333MT/s                     | 1         | 1.3%    |
| Micron RAM MT41K256M16LY 2GB SODIMM DDR3 1600MT/s           | 1         | 1.3%    |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s               | 1         | 1.3%    |
| Micron RAM Module 2048MB SODIMM DDR3 1600MT/s               | 1         | 1.3%    |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s       | 1         | 1.3%    |
| Micron RAM 8ATF1G64HZ-2G6H1 8192MB SODIMM DDR4 2667MT/s     | 1         | 1.3%    |
| Micron RAM 53E1G32D4NQ 2048MB Row Of Chips LPDDR4 4267MT/s  | 1         | 1.3%    |
| Micron RAM 4ATF51264HZ-2G6E3 4096MB SODIMM DDR4 2667MT/s    | 1         | 1.3%    |
| Micron RAM 4ATF1G64HZ-3G2E2 8192MB SODIMM DDR4 3200MT/s     | 1         | 1.3%    |
| Micron RAM 16JSF25664HZ-1G4F1 2GB SODIMM DDR3 1334MT/s      | 1         | 1.3%    |
| Micron RAM 16ATF2G64HZ-3G2J1 16GB SODIMM DDR4 3200MT/s      | 1         | 1.3%    |
| Kllisre RAM KRE-D3S1600M/8G 8192MB SODIMM DDR3 1600MT/s     | 1         | 1.3%    |
| Kingston RAM KHX2666C15S4/8G 8GB SODIMM DDR4 2667MT/s       | 1         | 1.3%    |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s         | 1         | 1.3%    |
| Kingston RAM HP687515-H66-MCN 4096MB SODIMM DDR3 1600MT/s   | 1         | 1.3%    |
| Kingston RAM HP16D3LS1KBG/8G 8192MB SODIMM DDR3 1600MT/s    | 1         | 1.3%    |
| Kingston RAM ACR16D3LS1KFG/8G 8GB SODIMM DDR3 1600MT/s      | 1         | 1.3%    |
| Kingston RAM 99U5471-052.A 8GB DIMM DDR3 1333MT/s           | 1         | 1.3%    |
| Kingston RAM 99U5458-001.A00LF 2GB DIMM DDR3 1600MT/s       | 1         | 1.3%    |
| Kingston RAM 99U5403-159.A01LF 8192MB DIMM DDR3 1333MT/s    | 1         | 1.3%    |
| Kingston RAM 9965516-069.A00LF 8GB DIMM DDR3 1333MT/s       | 1         | 1.3%    |
| Kingston RAM 9965516-003.A00LF 8GB DIMM DDR3 1333MT/s       | 1         | 1.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 27        | 46.55%  |
| DDR3   | 25        | 43.1%   |
| SDRAM  | 2         | 3.45%   |
| LPDDR4 | 2         | 3.45%   |
| DDR2   | 2         | 3.45%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 44        | 74.58%  |
| DIMM         | 12        | 20.34%  |
| Row Of Chips | 2         | 3.39%   |
| Chip         | 1         | 1.69%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 24        | 36.36%  |
| 4096  | 21        | 31.82%  |
| 2048  | 11        | 16.67%  |
| 16384 | 8         | 12.12%  |
| 1024  | 2         | 3.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 19        | 28.79%  |
| 3200  | 11        | 16.67%  |
| 2667  | 11        | 16.67%  |
| 2400  | 4         | 6.06%   |
| 2133  | 4         | 6.06%   |
| 1333  | 4         | 6.06%   |
| 1867  | 2         | 3.03%   |
| 4267  | 1         | 1.52%   |
| 4199  | 1         | 1.52%   |
| 3600  | 1         | 1.52%   |
| 3007  | 1         | 1.52%   |
| 3000  | 1         | 1.52%   |
| 2666  | 1         | 1.52%   |
| 2048  | 1         | 1.52%   |
| 1334  | 1         | 1.52%   |
| 1067  | 1         | 1.52%   |
| 1066  | 1         | 1.52%   |
| 800   | 1         | 1.52%   |

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
| Chicony Electronics                    | 38        | 25.5%   |
| Microdia                               | 12        | 8.05%   |
| Apple                                  | 12        | 8.05%   |
| Realtek Semiconductor                  | 11        | 7.38%   |
| Acer                                   | 10        | 6.71%   |
| Quanta                                 | 9         | 6.04%   |
| Logitech                               | 9         | 6.04%   |
| Sunplus Innovation Technology          | 8         | 5.37%   |
| Suyin                                  | 7         | 4.7%    |
| Cheng Uei Precision Industry (Foxlink) | 7         | 4.7%    |
| Syntek                                 | 4         | 2.68%   |
| Lenovo                                 | 4         | 2.68%   |
| Microsoft                              | 3         | 2.01%   |
| IMC Networks                           | 3         | 2.01%   |
| Luxvisions Innotech Limited            | 2         | 1.34%   |
| Lite-On Technology                     | 2         | 1.34%   |
| Z-Star Microelectronics                | 1         | 0.67%   |
| USB Camera                             | 1         | 0.67%   |
| Primax Electronics                     | 1         | 0.67%   |
| Importek                               | 1         | 0.67%   |
| HD WEBCAM                              | 1         | 0.67%   |
| Generalplus Technology                 | 1         | 0.67%   |
| DJJHNA29IE9J88                         | 1         | 0.67%   |
| Creative Technology                    | 1         | 0.67%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                      | 8         | 5.3%    |
| Chicony HD WebCam                              | 4         | 2.65%   |
| Apple FaceTime HD Camera (Built-in)            | 4         | 2.65%   |
| Apple FaceTime HD Camera                       | 4         | 2.65%   |
| Suyin 1.3M HD WebCam                           | 3         | 1.99%   |
| Realtek Integrated_Webcam_HD                   | 3         | 1.99%   |
| Realtek HD WebCam                              | 3         | 1.99%   |
| Quanta HP TrueVision HD Camera                 | 3         | 1.99%   |
| Chicony HP Wide Vision HD Camera               | 3         | 1.99%   |
| Chicony HP Truevision HD                       | 3         | 1.99%   |
| Chicony HP HD Webcam [Fixed]                   | 3         | 1.99%   |
| Acer Lenovo EasyCamera                         | 3         | 1.99%   |
| Syntek Integrated Camera                       | 2         | 1.32%   |
| Suyin Acer/HP Integrated Webcam [CN0314]       | 2         | 1.32%   |
| Sunplus Laptop_Integrated_Webcam_HD            | 2         | 1.32%   |
| Realtek USB Camera                             | 2         | 1.32%   |
| Microdia Webcam Vitade AF                      | 2         | 1.32%   |
| Microdia Integrated Webcam HD                  | 2         | 1.32%   |
| Logitech Webcam C270                           | 2         | 1.32%   |
| Logitech HD Pro Webcam C920                    | 2         | 1.32%   |
| Lenovo Integrated Webcam                       | 2         | 1.32%   |
| IMC Networks USB2.0 HD UVC WebCam              | 2         | 1.32%   |
| Chicony USB2.0 Camera                          | 2         | 1.32%   |
| Chicony HP TrueVision HD Camera                | 2         | 1.32%   |
| Chicony HP High Definition 1MP Webcam          | 2         | 1.32%   |
| Apple iPhone 5/5C/5S/6/SE                      | 2         | 1.32%   |
| Apple Built-in iSight                          | 2         | 1.32%   |
| Acer Integrated Camera                         | 2         | 1.32%   |
| Z-Star Sirius USB2.0 Camera                    | 1         | 0.66%   |
| USB Camera USB Camera                          | 1         | 0.66%   |
| Syntek USB2.0 Camera                           | 1         | 0.66%   |
| Syntek EasyCamera                              | 1         | 0.66%   |
| Suyin HP TrueVision HD Integrated Webcam       | 1         | 0.66%   |
| Suyin Asus Integrated Webcam                   | 1         | 0.66%   |
| Sunplus Laptop_Integrated_Webcam_1.3M          | 1         | 0.66%   |
| Sunplus Laptop Integrated WebCam HD            | 1         | 0.66%   |
| Sunplus Integrated_Webcam_HD                   | 1         | 0.66%   |
| Sunplus Depstech webcam MIC                    | 1         | 0.66%   |
| Sunplus Aukey-PC-LM1E Camera                   | 1         | 0.66%   |
| Sunplus 1.3M HD WebCam                         | 1         | 0.66%   |
| Realtek Integrated Webcam                      | 1         | 0.66%   |
| Realtek Integrated Camera                      | 1         | 0.66%   |
| Realtek HP Truevision HD                       | 1         | 0.66%   |
| Quanta ov9734_techfront_camera                 | 1         | 0.66%   |
| Quanta HP Webcam                               | 1         | 0.66%   |
| Quanta HP TrueVision HD Webcam                 | 1         | 0.66%   |
| Quanta HP 5M Camera                            | 1         | 0.66%   |
| Quanta HD User Facing                          | 1         | 0.66%   |
| Quanta HD Camera                               | 1         | 0.66%   |
| Primax Villem                                  | 1         | 0.66%   |
| Microsoft Xbox NUI Camera                      | 1         | 0.66%   |
| Microsoft LifeCam Rear                         | 1         | 0.66%   |
| Microsoft LifeCam HD-3000                      | 1         | 0.66%   |
| Microsoft LifeCam Front                        | 1         | 0.66%   |
| Microdia USB 2.0 Camera                        | 1         | 0.66%   |
| Microdia Sonix 1.3 MP Laptop Integrated Webcam | 1         | 0.66%   |
| Microdia Laptop_Integrated_Webcam_FHD          | 1         | 0.66%   |
| Microdia Laptop_Integrated_Webcam_2M           | 1         | 0.66%   |
| Microdia Integrated_Webcam_FHD                 | 1         | 0.66%   |
| Microdia Integrated Webcam                     | 1         | 0.66%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 13        | 44.83%  |
| Synaptics                  | 4         | 13.79%  |
| Upek                       | 3         | 10.34%  |
| LighTuning Technology      | 3         | 10.34%  |
| Shenzhen Goodix Technology | 2         | 6.9%    |
| AuthenTec                  | 2         | 6.9%    |
| STMicroelectronics         | 1         | 3.45%   |
| Focal-systems.Corp         | 1         | 3.45%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 10.34%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 10.34%  |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 10.34%  |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 6.9%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 6.9%    |
| Shenzhen Goodix  FingerPrint Device                                        | 2         | 6.9%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 3.45%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 3.45%   |
| Validity Sensors VFS491                                                    | 1         | 3.45%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 3.45%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 3.45%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 3.45%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 3.45%   |
| Synaptics  WBDI                                                            | 1         | 3.45%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 3.45%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 3.45%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 3.45%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 3.45%   |
| AuthenTec AES2810                                                          | 1         | 3.45%   |
| Unknown                                                                    | 1         | 3.45%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 2         | 50%     |
| Upek        | 1         | 25%     |
| Alcor Micro | 1         | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 25%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 25%     |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 25%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 158       | 71.49%  |
| 1     | 54        | 24.43%  |
| 2     | 9         | 4.07%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 29        | 39.19%  |
| Net/wireless             | 15        | 20.27%  |
| Graphics card            | 9         | 12.16%  |
| Multimedia controller    | 8         | 10.81%  |
| Chipcard                 | 4         | 5.41%   |
| Sound                    | 2         | 2.7%    |
| Net/ethernet             | 2         | 2.7%    |
| Bluetooth                | 2         | 2.7%    |
| Storage                  | 1         | 1.35%   |
| Communication controller | 1         | 1.35%   |
| Camera                   | 1         | 1.35%   |

