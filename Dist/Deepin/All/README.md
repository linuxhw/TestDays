Deepin - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Deepin.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Deepin/Desktop/README.md) and [notebooks](/Dist/Deepin/Notebook/README.md).

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

Total: 305

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | EliteBook 845 14 inch G1... | Notebook    | [6459a498c5](https://linux-hardware.org/?probe=6459a498c5) | Sep 07, 2023 |
| HP            | EliteBook 845 14 inch G1... | Notebook    | [c57f9232a2](https://linux-hardware.org/?probe=c57f9232a2) | Sep 05, 2023 |
| HP            | EliteBook 845 14 inch G1... | Notebook    | [8b11ecfd36](https://linux-hardware.org/?probe=8b11ecfd36) | Sep 04, 2023 |
| TSINGHUA T... | B460M-HDV                   | Desktop     | [f82a030bce](https://linux-hardware.org/?probe=f82a030bce) | Aug 30, 2023 |
| Chuwi         | UBook X                     | Tablet      | [e2281326e3](https://linux-hardware.org/?probe=e2281326e3) | Aug 27, 2023 |
| HP            | EliteBook 845 14 inch G1... | Notebook    | [ac607e5597](https://linux-hardware.org/?probe=ac607e5597) | Aug 25, 2023 |
| TSINGHUA T... | B460M-HDV                   | Desktop     | [815cb59889](https://linux-hardware.org/?probe=815cb59889) | Aug 16, 2023 |
| TSINGHUA T... | B460-N2                     | Desktop     | [f7f87f7a07](https://linux-hardware.org/?probe=f7f87f7a07) | Aug 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [4d875892d6](https://linux-hardware.org/?probe=4d875892d6) | Jul 30, 2023 |
| GreatWall     | GW-XXXXXX-XXX               | Soc         | [8709162441](https://linux-hardware.org/?probe=8709162441) | Jul 27, 2023 |
| HONOR         | NBLK-WAX9X                  | Notebook    | [1081b2e480](https://linux-hardware.org/?probe=1081b2e480) | Jul 26, 2023 |
| HONOR         | NBLK-WAX9X                  | Notebook    | [9919413d6e](https://linux-hardware.org/?probe=9919413d6e) | Jul 25, 2023 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [bddace9995](https://linux-hardware.org/?probe=bddace9995) | Jul 25, 2023 |
| THTF          | ChaoXiangQ620-T1            | Soc         | [45e36895f0](https://linux-hardware.org/?probe=45e36895f0) | Jul 23, 2023 |
| itel Mobil... | SPIRIT 1                    | Notebook    | [36c3d3f6a8](https://linux-hardware.org/?probe=36c3d3f6a8) | Jul 16, 2023 |
| MSI           | GL72M 7REX                  | Notebook    | [6d50ff945d](https://linux-hardware.org/?probe=6d50ff945d) | Jun 19, 2023 |
| MSI           | GL72M 7REX                  | Notebook    | [1f1699301f](https://linux-hardware.org/?probe=1f1699301f) | Jun 15, 2023 |
| HP            | 18EA                        | Desktop     | [d6e48a99e7](https://linux-hardware.org/?probe=d6e48a99e7) | Jun 08, 2023 |
| MSI           | A55M-E35                    | Desktop     | [fa4eba3787](https://linux-hardware.org/?probe=fa4eba3787) | Jun 08, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [320e5bee32](https://linux-hardware.org/?probe=320e5bee32) | Jun 04, 2023 |
| Hometech      | Alfa 470C                   | Notebook    | [ee3bd9eb81](https://linux-hardware.org/?probe=ee3bd9eb81) | Jun 02, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [a5785cf3c3](https://linux-hardware.org/?probe=a5785cf3c3) | May 29, 2023 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [8310aaaa78](https://linux-hardware.org/?probe=8310aaaa78) | May 27, 2023 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [86545c89c0](https://linux-hardware.org/?probe=86545c89c0) | May 27, 2023 |
| Dell          | Inspiron 13-7359            | Notebook    | [35c9cf7244](https://linux-hardware.org/?probe=35c9cf7244) | May 12, 2023 |
| Koloe         | X58                         | Desktop     | [7c1acc3b84](https://linux-hardware.org/?probe=7c1acc3b84) | May 08, 2023 |
| ASUSTek       | ROG Maximus Z790 HERO       | Desktop     | [a22f7f4309](https://linux-hardware.org/?probe=a22f7f4309) | Mar 13, 2023 |
| ASUSTek       | ROG Maximus Z790 HERO       | Desktop     | [d4f6b075c4](https://linux-hardware.org/?probe=d4f6b075c4) | Mar 13, 2023 |
| Dell          | G15 5520                    | Notebook    | [0322e7d38c](https://linux-hardware.org/?probe=0322e7d38c) | Mar 06, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [42a0b7428f](https://linux-hardware.org/?probe=42a0b7428f) | Mar 05, 2023 |
| Dell          | G15 5520                    | Notebook    | [1e3dcc41d3](https://linux-hardware.org/?probe=1e3dcc41d3) | Mar 04, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [f492107b66](https://linux-hardware.org/?probe=f492107b66) | Feb 19, 2023 |
| Intel         | NUC8BEB J72692-304          | Mini pc     | [16b8333671](https://linux-hardware.org/?probe=16b8333671) | Feb 17, 2023 |
| Intel         | NUC8BEB J72692-304          | Mini pc     | [546d700cde](https://linux-hardware.org/?probe=546d700cde) | Feb 17, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [44a3952ccf](https://linux-hardware.org/?probe=44a3952ccf) | Feb 15, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [1746b40d04](https://linux-hardware.org/?probe=1746b40d04) | Feb 09, 2023 |
| Acer          | Aspire A515-54G             | Notebook    | [a57a68e42f](https://linux-hardware.org/?probe=a57a68e42f) | Jan 31, 2023 |
| OEM           | KX-01 V1.0                  | Desktop     | [75d9dc396c](https://linux-hardware.org/?probe=75d9dc396c) | Jan 28, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [510b879339](https://linux-hardware.org/?probe=510b879339) | Jan 26, 2023 |
| Rockchip E... | RK3588                      | Soc         | [87b2165adf](https://linux-hardware.org/?probe=87b2165adf) | Jan 23, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [9cdfb3119e](https://linux-hardware.org/?probe=9cdfb3119e) | Jan 15, 2023 |
| Infinix       | INBOOK X2 GEN11             | Notebook    | [a899026279](https://linux-hardware.org/?probe=a899026279) | Jan 08, 2023 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | Notebook    | [c4170b9ea3](https://linux-hardware.org/?probe=c4170b9ea3) | Dec 20, 2022 |
| Dell          | Inspiron 5488               | Notebook    | [32b350c3f6](https://linux-hardware.org/?probe=32b350c3f6) | Nov 25, 2022 |
| Lenovo        | ThinkPad 10 20C1CTO1WW      | Tablet      | [f5e2cc92e2](https://linux-hardware.org/?probe=f5e2cc92e2) | Nov 19, 2022 |
| Timi          | Redmi G 2022                | Notebook    | [86f8128511](https://linux-hardware.org/?probe=86f8128511) | Nov 12, 2022 |
| HP            | Laptop                      | Notebook    | [e1cd3de91a](https://linux-hardware.org/?probe=e1cd3de91a) | Nov 02, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [ba1f911067](https://linux-hardware.org/?probe=ba1f911067) | Sep 10, 2022 |
| Phytium       | D2000                       | Server      | [7e0be651b1](https://linux-hardware.org/?probe=7e0be651b1) | Jul 27, 2022 |
| Unknown       | Unknown                     | Desktop     | [98e2d17193](https://linux-hardware.org/?probe=98e2d17193) | Jul 21, 2022 |
| HP            | 620                         | Notebook    | [4476f5f677](https://linux-hardware.org/?probe=4476f5f677) | Jun 23, 2022 |
| ASUSTek       | ROG Maximus XII HERO        | Desktop     | [843d2132ad](https://linux-hardware.org/?probe=843d2132ad) | Jun 09, 2022 |
| Lenovo        | ZHAOYANG K4e-ITL 82F8       | Notebook    | [6103e540b9](https://linux-hardware.org/?probe=6103e540b9) | May 04, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [7795fe989b](https://linux-hardware.org/?probe=7795fe989b) | Apr 29, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [a771d771b2](https://linux-hardware.org/?probe=a771d771b2) | Apr 24, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [1a195527a4](https://linux-hardware.org/?probe=1a195527a4) | Apr 24, 2022 |
| Lenovo        | Legion Y7000 81FW           | Notebook    | [c56c469d4f](https://linux-hardware.org/?probe=c56c469d4f) | Apr 21, 2022 |
| Acer          | Swift SF314-512             | Notebook    | [d7e77fd856](https://linux-hardware.org/?probe=d7e77fd856) | Apr 21, 2022 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [8794debb03](https://linux-hardware.org/?probe=8794debb03) | Apr 20, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [486b6a5d64](https://linux-hardware.org/?probe=486b6a5d64) | Apr 10, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [ec3689ffdc](https://linux-hardware.org/?probe=ec3689ffdc) | Apr 10, 2022 |
| ASUSTek       | P552LA                      | Notebook    | [94ef2678d5](https://linux-hardware.org/?probe=94ef2678d5) | Apr 03, 2022 |
| ASUSTek       | P552LA                      | Notebook    | [9166f15878](https://linux-hardware.org/?probe=9166f15878) | Apr 03, 2022 |
| Phytium       | FT-2000/4 V0001             | Server      | [6385010257](https://linux-hardware.org/?probe=6385010257) | Mar 28, 2022 |
| Cube          | SurfTab twin 11.6           | Convertible | [d8659d7018](https://linux-hardware.org/?probe=d8659d7018) | Mar 03, 2022 |
| Cube          | SurfTab twin 11.6           | Convertible | [fde2a4b713](https://linux-hardware.org/?probe=fde2a4b713) | Mar 03, 2022 |
| HANWEI        | FT-208-COME-B               | Soc         | [93aca5cd19](https://linux-hardware.org/?probe=93aca5cd19) | Feb 25, 2022 |
| HANWEI        | FT-208-COME-B               | Soc         | [e578c5f173](https://linux-hardware.org/?probe=e578c5f173) | Jan 28, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [131c9a7dc2](https://linux-hardware.org/?probe=131c9a7dc2) | Jan 27, 2022 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [f891c69576](https://linux-hardware.org/?probe=f891c69576) | Jan 08, 2022 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [3e37ded7e2](https://linux-hardware.org/?probe=3e37ded7e2) | Jan 04, 2022 |
| Google        | Akemi                       | Notebook    | [295fd594af](https://linux-hardware.org/?probe=295fd594af) | Dec 27, 2021 |
| TSINGHUA T... | B460M-HDV                   | Desktop     | [8447bd4156](https://linux-hardware.org/?probe=8447bd4156) | Dec 22, 2021 |
| Acer          | Aspire VN7-572G             | Notebook    | [895dca26b0](https://linux-hardware.org/?probe=895dca26b0) | Dec 21, 2021 |
| TSINGHUA T... | B460M-HDV                   | Desktop     | [1146dc777c](https://linux-hardware.org/?probe=1146dc777c) | Dec 15, 2021 |
| HUAWEI        | HN-WX9X                     | Notebook    | [f228b60d0c](https://linux-hardware.org/?probe=f228b60d0c) | Dec 07, 2021 |
| Dell          | 07N90W A02                  | Desktop     | [43a5aec999](https://linux-hardware.org/?probe=43a5aec999) | Dec 07, 2021 |
| ECS           | H81H3-M4                    | Desktop     | [cdaf4b1031](https://linux-hardware.org/?probe=cdaf4b1031) | Dec 07, 2021 |
| HP            | EliteBook 8570w             | Notebook    | [7752a79879](https://linux-hardware.org/?probe=7752a79879) | Dec 06, 2021 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [4b03ed047c](https://linux-hardware.org/?probe=4b03ed047c) | Dec 06, 2021 |
| Samsung       | 550P5C/550P7C               | Notebook    | [31bc59dcb9](https://linux-hardware.org/?probe=31bc59dcb9) | Nov 12, 2021 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | Notebook    | [88d791ff87](https://linux-hardware.org/?probe=88d791ff87) | Nov 09, 2021 |
| Dell          | Latitude 3400               | Notebook    | [7f519c2721](https://linux-hardware.org/?probe=7f519c2721) | Oct 23, 2021 |
| Samsung       | 550P5C/550P7C               | Notebook    | [2713972f14](https://linux-hardware.org/?probe=2713972f14) | Oct 22, 2021 |
| HP            | ZHAN 66 Pro G1              | Notebook    | [a1a1c41c6a](https://linux-hardware.org/?probe=a1a1c41c6a) | Oct 09, 2021 |
| HP            | ZHAN 66 Pro G1              | Notebook    | [fcc291e2f1](https://linux-hardware.org/?probe=fcc291e2f1) | Oct 08, 2021 |
| Lenovo        | Legion Y7000 2020 82AV      | Notebook    | [64d71e1177](https://linux-hardware.org/?probe=64d71e1177) | Sep 29, 2021 |
| Soyo          | SY-Thin Mini H110           | Mini pc     | [ca900f89d0](https://linux-hardware.org/?probe=ca900f89d0) | Sep 28, 2021 |
| TSINGHUA T... | B460M-HDV                   | Desktop     | [bc175433f9](https://linux-hardware.org/?probe=bc175433f9) | Sep 18, 2021 |
| TSINGHUA T... | B460M-HDV                   | Desktop     | [80017bc79b](https://linux-hardware.org/?probe=80017bc79b) | Sep 18, 2021 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [a428f57f6a](https://linux-hardware.org/?probe=a428f57f6a) | Sep 17, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [fc0f8f406b](https://linux-hardware.org/?probe=fc0f8f406b) | Aug 31, 2021 |
| Lenovo        | ThinkPad L412 0585AC3       | Notebook    | [f31b3187c3](https://linux-hardware.org/?probe=f31b3187c3) | Aug 23, 2021 |
| Lenovo        | Legion R9000K2021H 82N6     | Notebook    | [048b8332cc](https://linux-hardware.org/?probe=048b8332cc) | Aug 13, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [5e1cc5b229](https://linux-hardware.org/?probe=5e1cc5b229) | Aug 11, 2021 |
| TSINGHUA T... | B460-N2                     | Desktop     | [59d9384348](https://linux-hardware.org/?probe=59d9384348) | Aug 09, 2021 |
| Gigabyte      | B550M DS3H                  | Desktop     | [418d6ee68f](https://linux-hardware.org/?probe=418d6ee68f) | Jul 23, 2021 |
| Toshiba       | STI 005492G                 | Desktop     | [d7fe511a9e](https://linux-hardware.org/?probe=d7fe511a9e) | Jul 19, 2021 |
| Lenovo        | XiaoXinAir-14ARE 2020 81... | Notebook    | [d563d62b5f](https://linux-hardware.org/?probe=d563d62b5f) | Jul 14, 2021 |
| AMD           | BL2 V2.3                    | Desktop     | [1053adf355](https://linux-hardware.org/?probe=1053adf355) | Jul 12, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [61b9408d9e](https://linux-hardware.org/?probe=61b9408d9e) | Jul 11, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [59728d9bef](https://linux-hardware.org/?probe=59728d9bef) | Jul 11, 2021 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [efc4c63ac7](https://linux-hardware.org/?probe=efc4c63ac7) | Jul 09, 2021 |
| HP            | Spectre x2 Detachable 12... | Tablet      | [9f7d75d241](https://linux-hardware.org/?probe=9f7d75d241) | Jul 09, 2021 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [26b5b9e3d3](https://linux-hardware.org/?probe=26b5b9e3d3) | Jul 06, 2021 |
| Lenovo        | ZHAOYANG CF4620Z-A123 59... | Notebook    | [6f716961de](https://linux-hardware.org/?probe=6f716961de) | Jun 29, 2021 |
| Lenovo        | XiaoXin-15ARE 2020 81YR     | Notebook    | [279dea011e](https://linux-hardware.org/?probe=279dea011e) | Jun 28, 2021 |
| ECS           | H81H3-M4                    | Desktop     | [838f10c576](https://linux-hardware.org/?probe=838f10c576) | Jun 25, 2021 |
| ECS           | H81H3-M4                    | Desktop     | [bfc9a4d537](https://linux-hardware.org/?probe=bfc9a4d537) | Jun 25, 2021 |
| Lenovo        | Yoga DuetITL 2021 82MA      | Tablet      | [48335e0b08](https://linux-hardware.org/?probe=48335e0b08) | Jun 24, 2021 |
| TSINGHUA T... | B460-N2 V1.1                | Desktop     | [70d8ede642](https://linux-hardware.org/?probe=70d8ede642) | Jun 23, 2021 |
| TSINGHUA T... | B460-N2 V1.1                | Desktop     | [8431bcbed8](https://linux-hardware.org/?probe=8431bcbed8) | Jun 22, 2021 |
| Loongson      | LS3A3000-7A1000-1w-V1.2-... | Desktop     | [014bdabb68](https://linux-hardware.org/?probe=014bdabb68) | Jun 16, 2021 |
| Lenovo        | ThinkBook 14 G2 ARE R7 8... | Notebook    | [b2c24061a6](https://linux-hardware.org/?probe=b2c24061a6) | Jun 13, 2021 |
| Toshiba       | STI 005492G                 | Desktop     | [e28291b9ed](https://linux-hardware.org/?probe=e28291b9ed) | Jun 13, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [0540d35606](https://linux-hardware.org/?probe=0540d35606) | May 31, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [30ffaaaad4](https://linux-hardware.org/?probe=30ffaaaad4) | May 22, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [91b9340ed6](https://linux-hardware.org/?probe=91b9340ed6) | May 20, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [68740fff81](https://linux-hardware.org/?probe=68740fff81) | May 16, 2021 |
| MSI           | H81I                        | Desktop     | [a0f0f9e7e8](https://linux-hardware.org/?probe=a0f0f9e7e8) | May 06, 2021 |
| Unknown       | Unknown                     | Notebook    | [4d3ffa307c](https://linux-hardware.org/?probe=4d3ffa307c) | Apr 26, 2021 |
| Unknown       | Unknown                     | Notebook    | [8d019adbf9](https://linux-hardware.org/?probe=8d019adbf9) | Apr 26, 2021 |
| Lenovo        | ThinkPad T420 4180M8P       | Notebook    | [1fe655cf93](https://linux-hardware.org/?probe=1fe655cf93) | Apr 25, 2021 |
| Huanan        | X99-8M-F V1.1               | Desktop     | [13daa2d4a6](https://linux-hardware.org/?probe=13daa2d4a6) | Apr 23, 2021 |
| ASUSTek       | P8H61-MX                    | Desktop     | [9212747e6a](https://linux-hardware.org/?probe=9212747e6a) | Apr 08, 2021 |
| Toshiba       | Satellite E55t-A            | Notebook    | [e1a3602d7b](https://linux-hardware.org/?probe=e1a3602d7b) | Mar 28, 2021 |
| Unknown       | Unknown                     | Notebook    | [94f00d3697](https://linux-hardware.org/?probe=94f00d3697) | Mar 27, 2021 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [e6db1c79cc](https://linux-hardware.org/?probe=e6db1c79cc) | Mar 25, 2021 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [edb786e43a](https://linux-hardware.org/?probe=edb786e43a) | Mar 25, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [1db414e1cd](https://linux-hardware.org/?probe=1db414e1cd) | Mar 21, 2021 |
| Gigabyte      | H81M-D2V                    | Desktop     | [d62d3a2dad](https://linux-hardware.org/?probe=d62d3a2dad) | Mar 19, 2021 |
| MSI           | B460M PRO-VDH WIFI          | Desktop     | [b165cd04ce](https://linux-hardware.org/?probe=b165cd04ce) | Feb 25, 2021 |
| Sony          | VGN-AW11Z_B                 | Notebook    | [9ddedfd3c9](https://linux-hardware.org/?probe=9ddedfd3c9) | Feb 13, 2021 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [309266e981](https://linux-hardware.org/?probe=309266e981) | Feb 13, 2021 |
| Dell          | Inspiron 7720               | Notebook    | [8c8689a8ba](https://linux-hardware.org/?probe=8c8689a8ba) | Feb 08, 2021 |
| Acer          | Aspire V5-571P              | Notebook    | [e03d4bc850](https://linux-hardware.org/?probe=e03d4bc850) | Feb 07, 2021 |
| Dell          | Inspiron 5547               | Notebook    | [e2cee5283f](https://linux-hardware.org/?probe=e2cee5283f) | Feb 04, 2021 |
| Dell          | 0KWVT8 A00                  | Desktop     | [56f1d17280](https://linux-hardware.org/?probe=56f1d17280) | Feb 04, 2021 |
| HUAWEI        | HN-WX9X                     | Notebook    | [b0ca634dee](https://linux-hardware.org/?probe=b0ca634dee) | Jan 28, 2021 |
| Dell          | 00V62H A00                  | Desktop     | [863c1d64fe](https://linux-hardware.org/?probe=863c1d64fe) | Jan 23, 2021 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [842703dc6b](https://linux-hardware.org/?probe=842703dc6b) | Jan 20, 2021 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [5b9e365258](https://linux-hardware.org/?probe=5b9e365258) | Jan 19, 2021 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [0bfbe639fc](https://linux-hardware.org/?probe=0bfbe639fc) | Jan 18, 2021 |
| Lenovo        | ThinkPad E14 20RA0058VA     | Notebook    | [3c08ce49f5](https://linux-hardware.org/?probe=3c08ce49f5) | Jan 08, 2021 |
| Acer          | Aspire 4736Z                | Notebook    | [dd3b50729f](https://linux-hardware.org/?probe=dd3b50729f) | Jan 07, 2021 |
| ASUSTek       | X406UAR                     | Notebook    | [42e509209a](https://linux-hardware.org/?probe=42e509209a) | Dec 20, 2020 |
| ASUSTek       | X406UAR                     | Notebook    | [23b1fae05b](https://linux-hardware.org/?probe=23b1fae05b) | Dec 20, 2020 |
| Lenovo        | IdeaPad 3 14ARE05 81W3      | Notebook    | [667577cb5f](https://linux-hardware.org/?probe=667577cb5f) | Dec 15, 2020 |
| Lenovo        | G50-80 80L0                 | Notebook    | [951a5a280f](https://linux-hardware.org/?probe=951a5a280f) | Dec 11, 2020 |
| Gigabyte      | H81M-D2V                    | Desktop     | [49bd67196b](https://linux-hardware.org/?probe=49bd67196b) | Nov 20, 2020 |
| Acer          | Nitro AN515-54              | Notebook    | [d46eb4b9c9](https://linux-hardware.org/?probe=d46eb4b9c9) | Nov 19, 2020 |
| Acer          | Nitro AN515-54              | Notebook    | [877187c708](https://linux-hardware.org/?probe=877187c708) | Nov 19, 2020 |
| Lenovo        | ThinkPad E585 20KV0010US    | Notebook    | [033f6f0920](https://linux-hardware.org/?probe=033f6f0920) | Nov 18, 2020 |
| Lenovo        | ThinkPad E585 20KV0010US    | Notebook    | [d2bedcab13](https://linux-hardware.org/?probe=d2bedcab13) | Nov 18, 2020 |
| Foxconn       | 2ADA                        | Desktop     | [2c76ab07eb](https://linux-hardware.org/?probe=2c76ab07eb) | Nov 12, 2020 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [0b46341e31](https://linux-hardware.org/?probe=0b46341e31) | Nov 07, 2020 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [b687de4d3c](https://linux-hardware.org/?probe=b687de4d3c) | Nov 05, 2020 |
| Toshiba       | Satellite C850D-11K         | Notebook    | [53f5d002c9](https://linux-hardware.org/?probe=53f5d002c9) | Oct 31, 2020 |
| HP            | ENVY 15                     | Notebook    | [c23287b06d](https://linux-hardware.org/?probe=c23287b06d) | Oct 31, 2020 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | Desktop     | [a4fa363ca9](https://linux-hardware.org/?probe=a4fa363ca9) | Oct 29, 2020 |
| Acer          | Swift SF314-42              | Notebook    | [628265bca0](https://linux-hardware.org/?probe=628265bca0) | Oct 25, 2020 |
| Acer          | Swift SF314-42              | Notebook    | [01143e194b](https://linux-hardware.org/?probe=01143e194b) | Oct 20, 2020 |
| Lenovo        | IdeaPad 110-14IBR 80UJ      | Notebook    | [8d149c1a39](https://linux-hardware.org/?probe=8d149c1a39) | Oct 17, 2020 |
| Acer          | Nitro AN515-52              | Notebook    | [ca3d5b9444](https://linux-hardware.org/?probe=ca3d5b9444) | Oct 13, 2020 |
| Microtech     | ebookPro                    | Notebook    | [2f1ff6265a](https://linux-hardware.org/?probe=2f1ff6265a) | Oct 10, 2020 |
| ASRock        | Z68 Extreme7 Gen3           | Desktop     | [181ccd5686](https://linux-hardware.org/?probe=181ccd5686) | Oct 10, 2020 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [88e5775f0f](https://linux-hardware.org/?probe=88e5775f0f) | Oct 02, 2020 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [2972557e3e](https://linux-hardware.org/?probe=2972557e3e) | Oct 02, 2020 |
| Toshiba       | STI 013442                  | Desktop     | [25aa1737df](https://linux-hardware.org/?probe=25aa1737df) | Oct 02, 2020 |
| Toshiba       | STI 013442                  | Desktop     | [325dccb021](https://linux-hardware.org/?probe=325dccb021) | Oct 01, 2020 |
| Toshiba       | STI 013442                  | Desktop     | [d878c17ac5](https://linux-hardware.org/?probe=d878c17ac5) | Oct 01, 2020 |
| Lenovo        | G50-70 20351                | Notebook    | [c5ea28ed29](https://linux-hardware.org/?probe=c5ea28ed29) | Sep 28, 2020 |
| ASRock        | Z68 Extreme7 Gen3           | Desktop     | [d5c18b2ad2](https://linux-hardware.org/?probe=d5c18b2ad2) | Sep 27, 2020 |
| ASRock        | Z68 Extreme7 Gen3           | Desktop     | [27f0cbcbfa](https://linux-hardware.org/?probe=27f0cbcbfa) | Sep 27, 2020 |
| HP            | ENVY 15                     | Notebook    | [e7bfa62e4c](https://linux-hardware.org/?probe=e7bfa62e4c) | Sep 23, 2020 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [7318b0893d](https://linux-hardware.org/?probe=7318b0893d) | Sep 22, 2020 |
| Samsung       | 270E5J/2570EJ               | Notebook    | [d00667e263](https://linux-hardware.org/?probe=d00667e263) | Sep 21, 2020 |
| HP            | Pavilion 15                 | Notebook    | [f824ed9d26](https://linux-hardware.org/?probe=f824ed9d26) | Sep 18, 2020 |
| Gigabyte      | H81M-D2V                    | Desktop     | [c46dd29f7a](https://linux-hardware.org/?probe=c46dd29f7a) | Sep 17, 2020 |
| HP            | Pavilion 15                 | Notebook    | [d95e413136](https://linux-hardware.org/?probe=d95e413136) | Sep 16, 2020 |
| Dell          | Inspiron 3583               | Notebook    | [860b906339](https://linux-hardware.org/?probe=860b906339) | Sep 14, 2020 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [d7f43611eb](https://linux-hardware.org/?probe=d7f43611eb) | Sep 13, 2020 |
| Lenovo        | V310-15ISK 80SY             | Notebook    | [043d555fa5](https://linux-hardware.org/?probe=043d555fa5) | Sep 05, 2020 |
| Acer          | Aspire E5-571               | Notebook    | [84a6667f77](https://linux-hardware.org/?probe=84a6667f77) | Sep 05, 2020 |
| Acer          | Aspire 5735                 | Notebook    | [0e4c64618a](https://linux-hardware.org/?probe=0e4c64618a) | Sep 03, 2020 |
| Dell          | Inspiron 3583               | Notebook    | [885667a4cd](https://linux-hardware.org/?probe=885667a4cd) | Sep 02, 2020 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [e4b74d9442](https://linux-hardware.org/?probe=e4b74d9442) | Sep 02, 2020 |
| Dell          | Inspiron 5447               | Notebook    | [bc69598c5f](https://linux-hardware.org/?probe=bc69598c5f) | Aug 28, 2020 |
| HP            | 81B4                        | Desktop     | [9e3aa00a36](https://linux-hardware.org/?probe=9e3aa00a36) | Aug 21, 2020 |
| Samsung       | DP500A2D-A01UB SEC_SW_RE... | All in one  | [0a65089c68](https://linux-hardware.org/?probe=0a65089c68) | Aug 18, 2020 |
| Samsung       | DP500A2D-A01UB SEC_SW_RE... | All in one  | [922ccd2bc5](https://linux-hardware.org/?probe=922ccd2bc5) | Aug 18, 2020 |
| HP            | 81B4                        | Desktop     | [03c849fcd2](https://linux-hardware.org/?probe=03c849fcd2) | Jul 26, 2020 |
| Dell          | Inspiron 5447               | Notebook    | [b9bf539788](https://linux-hardware.org/?probe=b9bf539788) | Jul 26, 2020 |
| Foxconn       | 2ADA                        | Desktop     | [035b1fd159](https://linux-hardware.org/?probe=035b1fd159) | Jul 24, 2020 |
| Samsung       | 500R4K/500R5H/5400RK/501... | Notebook    | [b73122dcbf](https://linux-hardware.org/?probe=b73122dcbf) | Jul 24, 2020 |
| ASUSTek       | AM1M-A/BR                   | Desktop     | [dafd042867](https://linux-hardware.org/?probe=dafd042867) | Jul 22, 2020 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [a3dc30f185](https://linux-hardware.org/?probe=a3dc30f185) | Jul 21, 2020 |
| Dell          | Inspiron 7520               | Notebook    | [0e4bbcdaca](https://linux-hardware.org/?probe=0e4bbcdaca) | Jul 19, 2020 |
| Positivo      | POS-PQ45AU                  | Desktop     | [056dd1ec51](https://linux-hardware.org/?probe=056dd1ec51) | Jul 15, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [116754d157](https://linux-hardware.org/?probe=116754d157) | Jul 11, 2020 |
| Lenovo        | ThinkPad L512 44444NG       | Notebook    | [bfda7d01d5](https://linux-hardware.org/?probe=bfda7d01d5) | Jun 30, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [4a0dcf77f1](https://linux-hardware.org/?probe=4a0dcf77f1) | Jun 24, 2020 |
| MSI           | P67A-GD65                   | Desktop     | [c0df14bdee](https://linux-hardware.org/?probe=c0df14bdee) | Jun 22, 2020 |
| HP            | EliteBook 820 G3            | Notebook    | [1ad623b060](https://linux-hardware.org/?probe=1ad623b060) | Jun 20, 2020 |
| HP            | EliteBook 820 G3            | Notebook    | [5517a703d4](https://linux-hardware.org/?probe=5517a703d4) | Jun 15, 2020 |
| Apple         | Mac-F2268CC8                | All in one  | [2212090ff2](https://linux-hardware.org/?probe=2212090ff2) | Jun 10, 2020 |
| Chuwi         | AeroBook                    | Notebook    | [12312a6c5b](https://linux-hardware.org/?probe=12312a6c5b) | Jun 03, 2020 |
| Chuwi         | AeroBook                    | Notebook    | [fdcf37b34d](https://linux-hardware.org/?probe=fdcf37b34d) | Jun 01, 2020 |
| Chuwi         | AeroBook                    | Notebook    | [6a57e4427b](https://linux-hardware.org/?probe=6a57e4427b) | Jun 01, 2020 |
| ASRock        | Z77 Extreme4                | Desktop     | [2e074b7913](https://linux-hardware.org/?probe=2e074b7913) | May 30, 2020 |
| Google        | Edgar                       | Notebook    | [ed3bf69957](https://linux-hardware.org/?probe=ed3bf69957) | May 28, 2020 |
| ASUSTek       | T100TAF                     | Notebook    | [6d2999ebb1](https://linux-hardware.org/?probe=6d2999ebb1) | May 26, 2020 |
| Gigabyte      | 990XA-UD3                   | Desktop     | [cc7c6da435](https://linux-hardware.org/?probe=cc7c6da435) | May 19, 2020 |
| ASUSTek       | T101HA                      | Tablet      | [eedf2f3d04](https://linux-hardware.org/?probe=eedf2f3d04) | May 16, 2020 |
| ASUSTek       | T101HA                      | Tablet      | [cc59b3f980](https://linux-hardware.org/?probe=cc59b3f980) | May 16, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [825d07d907](https://linux-hardware.org/?probe=825d07d907) | May 14, 2020 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | Notebook    | [49661d90bd](https://linux-hardware.org/?probe=49661d90bd) | Apr 19, 2020 |
| Microsoft     | Surface Pro 4               | Tablet      | [13b3bd980f](https://linux-hardware.org/?probe=13b3bd980f) | Apr 08, 2020 |
| HP            | EliteBook 8570p             | Notebook    | [6928abb72d](https://linux-hardware.org/?probe=6928abb72d) | Apr 07, 2020 |
| HP            | EliteBook 8570p             | Notebook    | [020c71d11e](https://linux-hardware.org/?probe=020c71d11e) | Apr 07, 2020 |
| HP            | EliteBook 8570p             | Notebook    | [163b885549](https://linux-hardware.org/?probe=163b885549) | Apr 07, 2020 |
| Sony          | VGN-NS140D                  | Notebook    | [dbae86d335](https://linux-hardware.org/?probe=dbae86d335) | Apr 06, 2020 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [b8f32a998c](https://linux-hardware.org/?probe=b8f32a998c) | Mar 31, 2020 |
| Dell          | 0M863N A00                  | Desktop     | [39201e0067](https://linux-hardware.org/?probe=39201e0067) | Mar 30, 2020 |
| HP            | Pavilion Laptop 14-ce0xx... | Notebook    | [76c9608867](https://linux-hardware.org/?probe=76c9608867) | Mar 24, 2020 |
| HP            | Pavilion Laptop 14-ce0xx... | Notebook    | [81e20268cd](https://linux-hardware.org/?probe=81e20268cd) | Mar 24, 2020 |
| Fujitsu       | FARQ06012Z                  | Notebook    | [6d19311f7e](https://linux-hardware.org/?probe=6d19311f7e) | Mar 23, 2020 |
| Dell          | 07C0H8 A00                  | Desktop     | [6863933279](https://linux-hardware.org/?probe=6863933279) | Mar 18, 2020 |
| ASRock        | J5005-ITX                   | Desktop     | [94c7463689](https://linux-hardware.org/?probe=94c7463689) | Mar 16, 2020 |
| ASRock        | J5005-ITX                   | Desktop     | [12e2c41514](https://linux-hardware.org/?probe=12e2c41514) | Mar 08, 2020 |
| ASRock        | J5005-ITX                   | Desktop     | [77ca797332](https://linux-hardware.org/?probe=77ca797332) | Mar 04, 2020 |
| ASRock        | J5005-ITX                   | Desktop     | [455989807e](https://linux-hardware.org/?probe=455989807e) | Mar 04, 2020 |
| HP            | EliteBook 820 G4            | Notebook    | [b525dfeb66](https://linux-hardware.org/?probe=b525dfeb66) | Mar 01, 2020 |
| HP            | EliteBook 820 G4            | Notebook    | [e28f1711fd](https://linux-hardware.org/?probe=e28f1711fd) | Mar 01, 2020 |
| CCE           | Capella & IbexPeak-M Chi... | Notebook    | [b6b6b3d6d5](https://linux-hardware.org/?probe=b6b6b3d6d5) | Mar 01, 2020 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [c8e114bee8](https://linux-hardware.org/?probe=c8e114bee8) | Feb 14, 2020 |
| Medion        | MS-7728                     | Desktop     | [645a7667ce](https://linux-hardware.org/?probe=645a7667ce) | Feb 07, 2020 |
| Medion        | MS-7728                     | Desktop     | [c55f5705f3](https://linux-hardware.org/?probe=c55f5705f3) | Feb 07, 2020 |
| ASUSTek       | Z170-AR                     | Desktop     | [cd4ef749f3](https://linux-hardware.org/?probe=cd4ef749f3) | Feb 03, 2020 |
| ASUSTek       | Z170-AR                     | Desktop     | [74934afe78](https://linux-hardware.org/?probe=74934afe78) | Feb 03, 2020 |
| HP            | ENVY 15                     | Notebook    | [a8fb8c36bf](https://linux-hardware.org/?probe=a8fb8c36bf) | Jan 22, 2020 |
| Acer          | P5WE0                       | Notebook    | [a3377994d6](https://linux-hardware.org/?probe=a3377994d6) | Jan 18, 2020 |
| HP            | 250 G5 Notebook PC          | Notebook    | [6882e04fe6](https://linux-hardware.org/?probe=6882e04fe6) | Jan 16, 2020 |
| Acer          | Nitro AN515-54              | Notebook    | [af36fc8a7c](https://linux-hardware.org/?probe=af36fc8a7c) | Jan 15, 2020 |
| Acer          | Nitro AN515-54              | Notebook    | [d96a34fd91](https://linux-hardware.org/?probe=d96a34fd91) | Jan 15, 2020 |
| Acer          | Nitro AN515-54              | Notebook    | [dbd7e76364](https://linux-hardware.org/?probe=dbd7e76364) | Jan 15, 2020 |
| HUAWEI        | HLY-WX9XX                   | Notebook    | [9f6e79326e](https://linux-hardware.org/?probe=9f6e79326e) | Jan 14, 2020 |
| Dell          | XPS 13 9360                 | Notebook    | [60888ae202](https://linux-hardware.org/?probe=60888ae202) | Jan 14, 2020 |
| Lenovo        | ThinkPad T420 4236CU8       | Notebook    | [0222255c98](https://linux-hardware.org/?probe=0222255c98) | Jan 12, 2020 |
| Toshiba       | Satellite L75-C             | Notebook    | [649fb9a60a](https://linux-hardware.org/?probe=649fb9a60a) | Jan 03, 2020 |
| Toshiba       | Satellite L75-C             | Notebook    | [2b66fb3c5e](https://linux-hardware.org/?probe=2b66fb3c5e) | Jan 03, 2020 |
| ASRock        | N68-S3 FX                   | Desktop     | [ddf39244d2](https://linux-hardware.org/?probe=ddf39244d2) | Dec 24, 2019 |
| ASRock        | N68-S3 FX                   | Desktop     | [5f2a15fa54](https://linux-hardware.org/?probe=5f2a15fa54) | Dec 24, 2019 |
| Toshiba       | Satellite C850-1H6          | Notebook    | [a0ffb29c6c](https://linux-hardware.org/?probe=a0ffb29c6c) | Dec 18, 2019 |
| Lenovo        | Unknown                     | Notebook    | [10ab399874](https://linux-hardware.org/?probe=10ab399874) | Dec 14, 2019 |
| Lenovo        | IdeaPad 2in1 14 81CW        | Convertible | [33d7d63c6d](https://linux-hardware.org/?probe=33d7d63c6d) | Dec 13, 2019 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [d1b18250b9](https://linux-hardware.org/?probe=d1b18250b9) | Dec 04, 2019 |
| BQ            | Tesla2 W10                  | Notebook    | [27f3692e24](https://linux-hardware.org/?probe=27f3692e24) | Dec 04, 2019 |
| BQ            | Tesla2 W10                  | Notebook    | [4c37070709](https://linux-hardware.org/?probe=4c37070709) | Dec 04, 2019 |
| HP            | Pavilion 15                 | Notebook    | [03188ddfb3](https://linux-hardware.org/?probe=03188ddfb3) | Dec 03, 2019 |
| HP            | Pavilion 15                 | Notebook    | [ae59f09d06](https://linux-hardware.org/?probe=ae59f09d06) | Nov 19, 2019 |
| Acer          | Aspire E5-571G              | Notebook    | [afc9fdb4b3](https://linux-hardware.org/?probe=afc9fdb4b3) | Nov 14, 2019 |
| Acer          | Aspire E5-571G              | Notebook    | [7914862967](https://linux-hardware.org/?probe=7914862967) | Nov 14, 2019 |
| ASUSTek       | K501LX                      | Notebook    | [e90c15e3c9](https://linux-hardware.org/?probe=e90c15e3c9) | Nov 10, 2019 |
| Dell          | 0Y4DXR A00                  | All in one  | [8740133e10](https://linux-hardware.org/?probe=8740133e10) | Nov 02, 2019 |
| Lenovo        | 3107 NOK                    | Desktop     | [8545691fd8](https://linux-hardware.org/?probe=8545691fd8) | Oct 24, 2019 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [997462e90b](https://linux-hardware.org/?probe=997462e90b) | Oct 19, 2019 |
| Sony          | SVF14A190X                  | Notebook    | [0b9bdec363](https://linux-hardware.org/?probe=0b9bdec363) | Oct 08, 2019 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | Notebook    | [c4f25ea846](https://linux-hardware.org/?probe=c4f25ea846) | Oct 07, 2019 |
| Gateway       | NE56R                       | Notebook    | [d0978555c2](https://linux-hardware.org/?probe=d0978555c2) | Sep 11, 2019 |
| Sony          | SVE14135CXP                 | Notebook    | [1b1819d6c0](https://linux-hardware.org/?probe=1b1819d6c0) | Aug 13, 2019 |
| ASUSTek       | Z97-A                       | Desktop     | [1c2f2dd0b9](https://linux-hardware.org/?probe=1c2f2dd0b9) | Aug 06, 2019 |
| Dell          | Inspiron 1428               | Notebook    | [d12daa7b97](https://linux-hardware.org/?probe=d12daa7b97) | Aug 01, 2019 |
| Dell          | Inspiron 1428               | Notebook    | [44b9085f50](https://linux-hardware.org/?probe=44b9085f50) | Aug 01, 2019 |
| Dell          | Inspiron 17 7000 Series ... | Notebook    | [37b056e670](https://linux-hardware.org/?probe=37b056e670) | Jul 23, 2019 |
| ASUSTek       | P5G41T-M LX2/BR             | Desktop     | [834659c2b7](https://linux-hardware.org/?probe=834659c2b7) | Jun 18, 2019 |
| ASUSTek       | P8H61-M LX2 R2.0            | Desktop     | [883fb20fad](https://linux-hardware.org/?probe=883fb20fad) | Jun 18, 2019 |
| Timi          | TM1701                      | Notebook    | [cde89e0f6e](https://linux-hardware.org/?probe=cde89e0f6e) | Jun 13, 2019 |
| Dell          | Latitude E6420              | Notebook    | [c5063bb936](https://linux-hardware.org/?probe=c5063bb936) | May 12, 2019 |
| Dell          | Latitude E6420              | Notebook    | [9563d07d0a](https://linux-hardware.org/?probe=9563d07d0a) | May 12, 2019 |
| Acer          | Aspire 7741                 | Notebook    | [38acfde0bd](https://linux-hardware.org/?probe=38acfde0bd) | Apr 25, 2019 |
| ASUSTek       | N46VM                       | Notebook    | [c22250e143](https://linux-hardware.org/?probe=c22250e143) | Apr 25, 2019 |
| ASUSTek       | N46VM                       | Notebook    | [def5c1c07c](https://linux-hardware.org/?probe=def5c1c07c) | Apr 25, 2019 |
| Positivo      | C14CU51                     | Notebook    | [87fe4181bd](https://linux-hardware.org/?probe=87fe4181bd) | Apr 08, 2019 |
| HP            | Unknown                     | Notebook    | [53f0f72dd6](https://linux-hardware.org/?probe=53f0f72dd6) | Apr 02, 2019 |
| Sony          | VPCYB25AB                   | Notebook    | [035925b406](https://linux-hardware.org/?probe=035925b406) | Apr 01, 2019 |
| ASUSTek       | P5Q-E                       | Desktop     | [f16456d590](https://linux-hardware.org/?probe=f16456d590) | Mar 28, 2019 |
| ASUSTek       | P5G41T-M LX2/BR             | Desktop     | [dacef5f8e5](https://linux-hardware.org/?probe=dacef5f8e5) | Mar 28, 2019 |
| HP            | G42                         | Notebook    | [c0b7643d96](https://linux-hardware.org/?probe=c0b7643d96) | Mar 28, 2019 |
| HP            | Pavilion Notebook           | Notebook    | [53fb4de336](https://linux-hardware.org/?probe=53fb4de336) | Mar 27, 2019 |
| HP            | Pavilion Notebook           | Notebook    | [9a4cbb7444](https://linux-hardware.org/?probe=9a4cbb7444) | Mar 27, 2019 |
| Samsung       | 800G5M/800G5W               | Notebook    | [efdc2e3d09](https://linux-hardware.org/?probe=efdc2e3d09) | Mar 27, 2019 |
| HP            | EliteBook 840 G2            | Notebook    | [86742db945](https://linux-hardware.org/?probe=86742db945) | Mar 27, 2019 |
| Standard      | MB45II/MB45IN               | Notebook    | [5a6f9cc354](https://linux-hardware.org/?probe=5a6f9cc354) | Mar 27, 2019 |
| Positivo      | POS-EINM70CS POSITIVO       | Desktop     | [296a0cde2c](https://linux-hardware.org/?probe=296a0cde2c) | Mar 27, 2019 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [619a0d9d90](https://linux-hardware.org/?probe=619a0d9d90) | Mar 27, 2019 |
| Lenovo        | G400s VILG1                 | Notebook    | [a18da046c8](https://linux-hardware.org/?probe=a18da046c8) | Mar 27, 2019 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [175525d48c](https://linux-hardware.org/?probe=175525d48c) | Mar 25, 2019 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [dccca67c2e](https://linux-hardware.org/?probe=dccca67c2e) | Mar 25, 2019 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [d0787d5045](https://linux-hardware.org/?probe=d0787d5045) | Mar 25, 2019 |
| Lenovo        | ThinkPad E450c 20EHA00NC... | Notebook    | [deac2364d1](https://linux-hardware.org/?probe=deac2364d1) | Jan 30, 2019 |
| Lenovo        | ThinkPad E450c 20EHA00NC... | Notebook    | [1629601591](https://linux-hardware.org/?probe=1629601591) | Jan 30, 2019 |
| Lenovo        | ThinkPad E450c 20EHA00NC... | Notebook    | [b314214e24](https://linux-hardware.org/?probe=b314214e24) | Dec 25, 2018 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [730a46747b](https://linux-hardware.org/?probe=730a46747b) | Nov 07, 2018 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [0e7a915eb4](https://linux-hardware.org/?probe=0e7a915eb4) | Oct 30, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Deepin         | 47        | 21.17%  |
| Deepin 20      | 31        | 13.96%  |
| UOS 20         | 28        | 12.61%  |
| Deepin 15.11   | 27        | 12.16%  |
| Deepin 23      | 13        | 5.86%   |
| Deepin 15.9.2  | 12        | 5.41%   |
| Deepin 20.8    | 8         | 3.6%    |
| Deepin 20.3    | 7         | 3.15%   |
| Deepin 20.1    | 7         | 3.15%   |
| Deepin 20 beta | 7         | 3.15%   |
| Deepin 20.9    | 4         | 1.8%    |
| Deepin 20.5    | 4         | 1.8%    |
| Deepin 20.2.4  | 3         | 1.35%   |
| Deepin 20.2.3  | 3         | 1.35%   |
| Deepin 20.2.2  | 3         | 1.35%   |
| Deepin 15.10.1 | 3         | 1.35%   |
| Deepin 20.7.1  | 2         | 0.9%    |
| Deepin 20.6    | 2         | 0.9%    |
| Deepin 15.9.3  | 2         | 0.9%    |
| Deepin 2014.3  | 1         | 0.45%   |
| Deepin 20.7    | 1         | 0.45%   |
| Deepin 20.4    | 1         | 0.45%   |
| Deepin 20.2.1  | 1         | 0.45%   |
| Deepin 20.2    | 1         | 0.45%   |
| Deepin 15.9    | 1         | 0.45%   |
| Deepin 15.8    | 1         | 0.45%   |
| Deepin 15.7    | 1         | 0.45%   |
| Deepin 15.10   | 1         | 0.45%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Deepin | 213       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Computers | Percent |
|-------------------------------------|-----------|---------|
| 4.15.0-30deepin-generic             | 41        | 18.47%  |
| 5.4.50-amd64-desktop                | 22        | 9.91%   |
| 4.15.0-29deepin-generic             | 19        | 8.56%   |
| 5.4.70-amd64-desktop                | 16        | 7.21%   |
| 5.10.60-amd64-desktop               | 12        | 5.41%   |
| 5.3.0-3-amd64                       | 10        | 4.5%    |
| 5.10.0-amd64-desktop                | 7         | 3.15%   |
| 5.7.7-amd64-desktop                 | 6         | 2.7%    |
| 5.18.17-amd64-desktop-community-hwe | 6         | 2.7%    |
| 5.10.29-amd64-desktop               | 6         | 2.7%    |
| 5.18.17-amd64-desktop-hwe           | 5         | 2.25%   |
| 5.15.77-amd64-desktop               | 5         | 2.25%   |
| 5.10.41-amd64-desktop               | 5         | 2.25%   |
| 5.10.36-amd64-desktop               | 5         | 2.25%   |
| 4.19.0-amd64-desktop                | 5         | 2.25%   |
| 6.1.11-amd64-desktop-hwe            | 4         | 1.8%    |
| 5.10.18-amd64-desktop               | 4         | 1.8%    |
| 5.15.45-amd64-desktop               | 3         | 1.35%   |
| 5.15.24-amd64-desktop               | 3         | 1.35%   |
| 5.15.1-amd64-desktop                | 3         | 1.35%   |
| 5.10.50-amd64-desktop               | 3         | 1.35%   |
| 5.10.5-amd64-desktop+               | 3         | 1.35%   |
| 5.10.101-amd64-desktop              | 3         | 1.35%   |
| 5.8.14-amd64-desktop                | 2         | 0.9%    |
| 5.5.4-xanmod3                       | 2         | 0.9%    |
| 5.10.83-amd64-desktop               | 2         | 0.9%    |
| 4.19.0-arm64-desktop                | 2         | 0.9%    |
| 6.5.0                               | 1         | 0.45%   |
| 6.1.32-amd64-desktop-hwe            | 1         | 0.45%   |
| 6.1.12-1-liquorix-amd64             | 1         | 0.45%   |
| 5.6.14-050614-generic               | 1         | 0.45%   |
| 5.6.12-xanmod1                      | 1         | 0.45%   |
| 5.4.2-xanmod2                       | 1         | 0.45%   |
| 5.3.8-xanmod6                       | 1         | 0.45%   |
| 5.2.14-050214-lowlatency            | 1         | 0.45%   |
| 5.14.0-rc3-amd64-desktop            | 1         | 0.45%   |
| 5.12.18-amd64-desktop               | 1         | 0.45%   |
| 5.10.0-11-arm64                     | 1         | 0.45%   |
| 5.10.0                              | 1         | 0.45%   |
| 5.1.15-surface-linux-surface        | 1         | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 4.15.0   | 61        | 27.48%  |
| 5.4.50   | 22        | 9.91%   |
| 5.4.70   | 16        | 7.21%   |
| 5.10.60  | 12        | 5.41%   |
| 5.18.17  | 11        | 4.95%   |
| 5.3.0    | 10        | 4.5%    |
| 5.10.0   | 9         | 4.05%   |
| 4.19.0   | 8         | 3.6%    |
| 5.7.7    | 6         | 2.7%    |
| 5.10.29  | 6         | 2.7%    |
| 5.15.77  | 5         | 2.25%   |
| 5.10.41  | 5         | 2.25%   |
| 5.10.36  | 5         | 2.25%   |
| 6.1.11   | 4         | 1.8%    |
| 5.10.18  | 4         | 1.8%    |
| 5.15.45  | 3         | 1.35%   |
| 5.15.24  | 3         | 1.35%   |
| 5.15.1   | 3         | 1.35%   |
| 5.10.50  | 3         | 1.35%   |
| 5.10.5   | 3         | 1.35%   |
| 5.10.101 | 3         | 1.35%   |
| 5.8.14   | 2         | 0.9%    |
| 5.5.4    | 2         | 0.9%    |
| 5.10.83  | 2         | 0.9%    |
| 6.5.0    | 1         | 0.45%   |
| 6.1.32   | 1         | 0.45%   |
| 6.1.12   | 1         | 0.45%   |
| 5.6.14   | 1         | 0.45%   |
| 5.6.12   | 1         | 0.45%   |
| 5.4.2    | 1         | 0.45%   |
| 5.3.8    | 1         | 0.45%   |
| 5.2.14   | 1         | 0.45%   |
| 5.14.0   | 1         | 0.45%   |
| 5.12.18  | 1         | 0.45%   |
| 5.1.15   | 1         | 0.45%   |
| 5.1.0    | 1         | 0.45%   |
| 4.19.90  | 1         | 0.45%   |
| 4.19.71  | 1         | 0.45%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.15    | 61        | 27.98%  |
| 5.10    | 50        | 22.94%  |
| 5.4     | 38        | 17.43%  |
| 5.15    | 13        | 5.96%   |
| 5.3     | 11        | 5.05%   |
| 5.18    | 11        | 5.05%   |
| 4.19    | 10        | 4.59%   |
| 6.1     | 6         | 2.75%   |
| 5.7     | 6         | 2.75%   |
| 5.8     | 2         | 0.92%   |
| 5.6     | 2         | 0.92%   |
| 5.5     | 2         | 0.92%   |
| 5.1     | 2         | 0.92%   |
| 6.5     | 1         | 0.46%   |
| 5.2     | 1         | 0.46%   |
| 5.14    | 1         | 0.46%   |
| 5.12    | 1         | 0.46%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 207       | 97.18%  |
| aarch64 | 5         | 2.35%   |
| mips64  | 1         | 0.47%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Deepin  | 180       | 84.11%  |
| Unknown | 29        | 13.55%  |
| DDE     | 2         | 0.93%   |
| MATE    | 1         | 0.47%   |
| KDE5    | 1         | 0.47%   |
| KDE     | 1         | 0.47%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 205       | 96.24%  |
| Wayland | 5         | 2.35%   |
| Tty     | 3         | 1.41%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 92        | 42.79%  |
| LightDM | 70        | 32.56%  |
| TDM     | 53        | 24.65%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 44        | 20.47%  |
| zh_CN   | 39        | 18.14%  |
| Unknown | 39        | 18.14%  |
| pt_BR   | 26        | 12.09%  |
| es_ES   | 22        | 10.23%  |
| de_DE   | 16        | 7.44%   |
| ru_RU   | 9         | 4.19%   |
| it_IT   | 4         | 1.86%   |
| tr_TR   | 3         | 1.4%    |
| pl_PL   | 3         | 1.4%    |
| en_GB   | 3         | 1.4%    |
| fr_FR   | 2         | 0.93%   |
| sv_SE   | 1         | 0.47%   |
| nl_NL   | 1         | 0.47%   |
| lt_LT   | 1         | 0.47%   |
| ja_JP   | 1         | 0.47%   |
| id_ID   | 1         | 0.47%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 132       | 61.68%  |
| BIOS | 82        | 38.32%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 194       | 91.08%  |
| Unknown | 18        | 8.45%   |
| Overlay | 1         | 0.47%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 107       | 49.54%  |
| Unknown | 87        | 40.28%  |
| MBR     | 22        | 10.19%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 161       | 74.54%  |
| Yes       | 55        | 25.46%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 158       | 73.49%  |
| Yes       | 57        | 26.51%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Lenovo                     | 39        | 18.31%  |
| Hewlett-Packard            | 26        | 12.21%  |
| ASUSTek Computer           | 24        | 11.27%  |
| Dell                       | 18        | 8.45%   |
| Acer                       | 14        | 6.57%   |
| Gigabyte Technology        | 9         | 4.23%   |
| Samsung Electronics        | 8         | 3.76%   |
| TSINGHUA TONGFANG COMPUTER | 7         | 3.29%   |
| HUAWEI                     | 6         | 2.82%   |
| Sony                       | 5         | 2.35%   |
| Toshiba                    | 4         | 1.88%   |
| MSI                        | 4         | 1.88%   |
| ASRock                     | 4         | 1.88%   |
| Positivo                   | 3         | 1.41%   |
| Unknown                    | 3         | 1.41%   |
| Timi                       | 2         | 0.94%   |
| Semp Toshiba               | 2         | 0.94%   |
| Intel                      | 2         | 0.94%   |
| Google                     | 2         | 0.94%   |
| ECS                        | 2         | 0.94%   |
| Chuwi                      | 2         | 0.94%   |
| Apple                      | 2         | 0.94%   |
| THTF                       | 1         | 0.47%   |
| Standard                   | 1         | 0.47%   |
| Soyo                       | 1         | 0.47%   |
| Rockchip Electronics       | 1         | 0.47%   |
| Phytium                    | 1         | 0.47%   |
| OEM                        | 1         | 0.47%   |
| Microtech                  | 1         | 0.47%   |
| Microsoft                  | 1         | 0.47%   |
| Medion                     | 1         | 0.47%   |
| Loongson                   | 1         | 0.47%   |
| Koloe                      | 1         | 0.47%   |
| itel Mobile Limited        | 1         | 0.47%   |
| Infinix                    | 1         | 0.47%   |
| Huanan                     | 1         | 0.47%   |
| HONOR                      | 1         | 0.47%   |
| Hometech                   | 1         | 0.47%   |
| HANWEI                     | 1         | 0.47%   |
| GreatWall                  | 1         | 0.47%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| TSINGHUA TONGFANG COMPUTER E500                   | 7         | 3.29%   |
| Unknown                                           | 5         | 2.35%   |
| Semp Toshiba STI                                  | 2         | 0.94%   |
| Samsung 340XAA/350XAA/550XAA                      | 2         | 0.94%   |
| Lenovo IdeaPad 120S-11IAP 81A4                    | 2         | 0.94%   |
| HP Pavilion Notebook                              | 2         | 0.94%   |
| HP Pavilion 15                                    | 2         | 0.94%   |
| HP ENVY 15                                        | 2         | 0.94%   |
| ECS H81H3-M4                                      | 2         | 0.94%   |
| ASUS All Series                                   | 2         | 0.94%   |
| Acer Nitro AN515-54                               | 2         | 0.94%   |
| Toshiba Satellite L75-C                           | 1         | 0.47%   |
| Toshiba Satellite E55t-A                          | 1         | 0.47%   |
| Toshiba Satellite C850D-11K                       | 1         | 0.47%   |
| Toshiba Satellite C850-1H6                        | 1         | 0.47%   |
| Timi TM1701                                       | 1         | 0.47%   |
| Timi Redmi G 2022                                 | 1         | 0.47%   |
| THTF ChaoXiangQ620-T1                             | 1         | 0.47%   |
| Standard MB45II/MB45IN                            | 1         | 0.47%   |
| Soyo SY-Thin Mini H110                            | 1         | 0.47%   |
| Sony VPCYB25AB                                    | 1         | 0.47%   |
| Sony VGN-NS140D                                   | 1         | 0.47%   |
| Sony VGN-AW11Z_B                                  | 1         | 0.47%   |
| Sony SVF14A190X                                   | 1         | 0.47%   |
| Sony SVE14135CXP                                  | 1         | 0.47%   |
| Samsung P500A2D                                   | 1         | 0.47%   |
| Samsung 800G5M/800G5W                             | 1         | 0.47%   |
| Samsung 550P5C/550P7C                             | 1         | 0.47%   |
| Samsung 500R4K/500R5H/5400RK/501R5H/5500RH/500R5S | 1         | 0.47%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA        | 1         | 0.47%   |
| Samsung 270E5J/2570EJ                             | 1         | 0.47%   |
| Rockchip RK3588                                   | 1         | 0.47%   |
| Positivo POS-PQ45AU                               | 1         | 0.47%   |
| Positivo POS-EINM70CS                             | 1         | 0.47%   |
| Positivo C14CU51                                  | 1         | 0.47%   |
| Phytium D2000                                     | 1         | 0.47%   |
| OEM ZXE CRB                                       | 1         | 0.47%   |
| MSI MS-7C83                                       | 1         | 0.47%   |
| MSI MS-7851                                       | 1         | 0.47%   |
| MSI MS-7681                                       | 1         | 0.47%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                            | Computers | Percent |
|---------------------------------|-----------|---------|
| Dell Inspiron                   | 11        | 5.16%   |
| Lenovo ThinkPad                 | 10        | 4.69%   |
| Lenovo IdeaPad                  | 9         | 4.23%   |
| Acer Aspire                     | 8         | 3.76%   |
| TSINGHUA TONGFANG COMPUTER E500 | 7         | 3.29%   |
| HP EliteBook                    | 6         | 2.82%   |
| HP Pavilion                     | 5         | 2.35%   |
| Unknown                         | 5         | 2.35%   |
| Toshiba Satellite               | 4         | 1.88%   |
| Lenovo Legion                   | 4         | 1.88%   |
| HP Laptop                       | 4         | 1.88%   |
| Lenovo ThinkBook                | 3         | 1.41%   |
| HP ENVY                         | 3         | 1.41%   |
| ASUS PRIME                      | 3         | 1.41%   |
| Acer Nitro                      | 3         | 1.41%   |
| Semp Toshiba STI                | 2         | 0.94%   |
| Samsung 340XAA                  | 2         | 0.94%   |
| Lenovo ZHAOYANG                 | 2         | 0.94%   |
| Lenovo Yoga                     | 2         | 0.94%   |
| Lenovo ThinkCentre              | 2         | 0.94%   |
| ECS H81H3-M4                    | 2         | 0.94%   |
| Dell OptiPlex                   | 2         | 0.94%   |
| Dell Latitude                   | 2         | 0.94%   |
| ASUS ROG                        | 2         | 0.94%   |
| ASUS All                        | 2         | 0.94%   |
| Acer Swift                      | 2         | 0.94%   |
| Timi TM1701                     | 1         | 0.47%   |
| Timi Redmi                      | 1         | 0.47%   |
| THTF ChaoXiangQ620-T1           | 1         | 0.47%   |
| Standard MB45II                 | 1         | 0.47%   |
| Soyo SY-Thin                    | 1         | 0.47%   |
| Sony VPCYB25AB                  | 1         | 0.47%   |
| Sony VGN-NS140D                 | 1         | 0.47%   |
| Sony VGN-AW11Z                  | 1         | 0.47%   |
| Sony SVF14A190X                 | 1         | 0.47%   |
| Sony SVE14135CXP                | 1         | 0.47%   |
| Samsung P500A2D                 | 1         | 0.47%   |
| Samsung 800G5M                  | 1         | 0.47%   |
| Samsung 550P5C                  | 1         | 0.47%   |
| Samsung 500R4K                  | 1         | 0.47%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 22        | 10.33%  |
| 2018    | 20        | 9.39%   |
| 2017    | 20        | 9.39%   |
| 2019    | 18        | 8.45%   |
| 2013    | 18        | 8.45%   |
| 2020    | 17        | 7.98%   |
| 2012    | 17        | 7.98%   |
| 2014    | 14        | 6.57%   |
| 2011    | 13        | 6.1%    |
| 2016    | 11        | 5.16%   |
| 2015    | 11        | 5.16%   |
| 2022    | 9         | 4.23%   |
| 2010    | 9         | 4.23%   |
| 2009    | 8         | 3.76%   |
| 2023    | 2         | 0.94%   |
| 2008    | 2         | 0.94%   |
| Unknown | 2         | 0.94%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 132       | 61.97%  |
| Desktop        | 62        | 29.11%  |
| Tablet         | 6         | 2.82%   |
| System on chip | 4         | 1.88%   |
| Convertible    | 3         | 1.41%   |
| All in one     | 3         | 1.41%   |
| Mini pc        | 2         | 0.94%   |
| Server         | 1         | 0.47%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 202       | 94.84%  |
| Enabled  | 11        | 5.16%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 211       | 99.06%  |
| Yes  | 2         | 0.94%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 64        | 30.05%  |
| 8.01-16.0   | 51        | 23.94%  |
| 16.01-24.0  | 44        | 20.66%  |
| 3.01-4.0    | 37        | 17.37%  |
| 32.01-64.0  | 8         | 3.76%   |
| 1.01-2.0    | 5         | 2.35%   |
| 64.01-256.0 | 2         | 0.94%   |
| 24.01-32.0  | 1         | 0.47%   |
| 2.01-3.0    | 1         | 0.47%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 68        | 30.36%  |
| 2.01-3.0  | 62        | 27.68%  |
| 3.01-4.0  | 37        | 16.52%  |
| 4.01-8.0  | 35        | 15.63%  |
| 0.51-1.0  | 15        | 6.7%    |
| 8.01-16.0 | 6         | 2.68%   |
| 0.01-0.5  | 1         | 0.45%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 138       | 63.89%  |
| 2      | 62        | 28.7%   |
| 4      | 8         | 3.7%    |
| 3      | 7         | 3.24%   |
| 5      | 1         | 0.46%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 145       | 67.44%  |
| Yes       | 70        | 32.56%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 166       | 77.93%  |
| No        | 47        | 22.07%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 165       | 77.46%  |
| No        | 48        | 22.54%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 139       | 65.26%  |
| No        | 74        | 34.74%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country               | Computers | Percent |
|-----------------------|-----------|---------|
| Brazil                | 47        | 21.96%  |
| China                 | 42        | 19.63%  |
| Germany               | 16        | 7.48%   |
| USA                   | 14        | 6.54%   |
| Spain                 | 7         | 3.27%   |
| Russia                | 7         | 3.27%   |
| Turkey                | 5         | 2.34%   |
| Indonesia             | 5         | 2.34%   |
| Poland                | 4         | 1.87%   |
| Panama                | 4         | 1.87%   |
| Italy                 | 4         | 1.87%   |
| Colombia              | 4         | 1.87%   |
| Chile                 | 4         | 1.87%   |
| Mexico                | 3         | 1.4%    |
| Japan                 | 3         | 1.4%    |
| India                 | 3         | 1.4%    |
| Austria               | 3         | 1.4%    |
| Argentina             | 3         | 1.4%    |
| UK                    | 2         | 0.93%   |
| Canada                | 2         | 0.93%   |
| Bulgaria              | 2         | 0.93%   |
| Bangladesh            | 2         | 0.93%   |
| Vietnam               | 1         | 0.47%   |
| Venezuela             | 1         | 0.47%   |
| Ukraine               | 1         | 0.47%   |
| Tunisia               | 1         | 0.47%   |
| Sweden                | 1         | 0.47%   |
| South Africa          | 1         | 0.47%   |
| Singapore             | 1         | 0.47%   |
| Serbia                | 1         | 0.47%   |
| Sao Tome and Principe | 1         | 0.47%   |
| Romania               | 1         | 0.47%   |
| Portugal              | 1         | 0.47%   |
| Pakistan              | 1         | 0.47%   |
| New Zealand           | 1         | 0.47%   |
| Netherlands           | 1         | 0.47%   |
| Namibia               | 1         | 0.47%   |
| Lithuania             | 1         | 0.47%   |
| Lebanon               | 1         | 0.47%   |
| Kenya                 | 1         | 0.47%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Computers | Percent |
|-----------------|-----------|---------|
| Wuhan           | 8         | 3.7%    |
| Beijing         | 8         | 3.7%    |
| Sao Paulo       | 5         | 2.31%   |
| Shanghai        | 4         | 1.85%   |
| Guangzhou       | 4         | 1.85%   |
| David           | 4         | 1.85%   |
| Nanjing         | 3         | 1.39%   |
| Curitiba        | 3         | 1.39%   |
| Uberlândia     | 2         | 0.93%   |
| Surabaya        | 2         | 0.93%   |
| San Francisco   | 2         | 0.93%   |
| Petrópolis     | 2         | 0.93%   |
| Moscow          | 2         | 0.93%   |
| Londrina        | 2         | 0.93%   |
| Innsbruck       | 2         | 0.93%   |
| Getxo           | 2         | 0.93%   |
| Dhaka           | 2         | 0.93%   |
| Contagem        | 2         | 0.93%   |
| Brasília       | 2         | 0.93%   |
| Bogotá         | 2         | 0.93%   |
| Atlanta         | 2         | 0.93%   |
| Zaragoza        | 1         | 0.46%   |
| Yozgat          | 1         | 0.46%   |
| Yogyakarta      | 1         | 0.46%   |
| Xuhui           | 1         | 0.46%   |
| Windhoek        | 1         | 0.46%   |
| West Jordan     | 1         | 0.46%   |
| Waynesville     | 1         | 0.46%   |
| Wanchai         | 1         | 0.46%   |
| Voronezh        | 1         | 0.46%   |
| Voluntari       | 1         | 0.46%   |
| Villa Ballester | 1         | 0.46%   |
| Vigo            | 1         | 0.46%   |
| Ufa             | 1         | 0.46%   |
| Tychy           | 1         | 0.46%   |
| Tomsk           | 1         | 0.46%   |
| Toluca          | 1         | 0.46%   |
| Tokyo           | 1         | 0.46%   |
| Tianjin         | 1         | 0.46%   |
| TehrДЃn       | 1         | 0.46%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 50        | 63     | 16.56%  |
| Seagate                        | 41        | 47     | 13.58%  |
| Samsung Electronics            | 28        | 31     | 9.27%   |
| Toshiba                        | 21        | 23     | 6.95%   |
| SanDisk                        | 18        | 22     | 5.96%   |
| Unknown                        | 17        | 18     | 5.63%   |
| Kingston                       | 17        | 23     | 5.63%   |
| SK hynix                       | 10        | 11     | 3.31%   |
| Hitachi                        | 8         | 8      | 2.65%   |
| Crucial                        | 7         | 8      | 2.32%   |
| China                          | 7         | 7      | 2.32%   |
| Micron Technology              | 6         | 8      | 1.99%   |
| HGST                           | 6         | 6      | 1.99%   |
| Intel                          | 5         | 6      | 1.66%   |
| A-DATA Technology              | 5         | 6      | 1.66%   |
| SPCC                           | 4         | 5      | 1.32%   |
| Silicon Motion                 | 4         | 4      | 1.32%   |
| Phison                         | 4         | 4      | 1.32%   |
| FORESEE                        | 4         | 4      | 1.32%   |
| LITEON                         | 3         | 3      | 0.99%   |
| Vaseky                         | 2         | 2      | 0.66%   |
| Maxtor                         | 2         | 4      | 0.66%   |
| JMicron Technology             | 2         | 2      | 0.66%   |
| Intenso                        | 2         | 3      | 0.66%   |
| Hewlett-Packard                | 2         | 3      | 0.66%   |
| V-GeN                          | 1         | 1      | 0.33%   |
| Transcend                      | 1         | 1      | 0.33%   |
| Solid State Storage Technology | 1         | 1      | 0.33%   |
| Realtek Semiconductor          | 1         | 1      | 0.33%   |
| Phytium                        | 1         | 1      | 0.33%   |
| Patriot                        | 1         | 1      | 0.33%   |
| OEM                            | 1         | 1      | 0.33%   |
| OCZ                            | 1         | 1      | 0.33%   |
| Netac                          | 1         | 1      | 0.33%   |
| Mushkin                        | 1         | 1      | 0.33%   |
| Microtech                      | 1         | 1      | 0.33%   |
| Maxtor 6                       | 1         | 1      | 0.33%   |
| LaCie                          | 1         | 2      | 0.33%   |
| KIOXIA                         | 1         | 1      | 0.33%   |
| Kingston Technology Company    | 1         | 1      | 0.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 6         | 1.9%    |
| Kingston SA400S37240G 240GB SSD      | 6         | 1.9%    |
| Toshiba MQ01ABF050 500GB             | 5         | 1.58%   |
| Seagate ST1000DM010-2EP102 1TB       | 4         | 1.27%   |
| WDC WD5000LPCX-24VHAT0 500GB         | 3         | 0.95%   |
| Unknown MMC Card                     | 3         | 0.95%   |
| Toshiba MQ01ABD100 1TB               | 3         | 0.95%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 3         | 0.95%   |
| Samsung SSD 850 EVO 500GB            | 3         | 0.95%   |
| Phison ESO256GMFCH-E3C-2 256GB       | 3         | 0.95%   |
| Crucial CT240BX500SSD1 240GB         | 3         | 0.95%   |
| WDC WD5000AAKX-003CA0 500GB          | 2         | 0.63%   |
| WDC WD10EZEX-22MFCA0 1TB             | 2         | 0.63%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB | 2         | 0.63%   |
| Toshiba DT01ACA200 2TB               | 2         | 0.63%   |
| SPCC Solid State Disk 512GB          | 2         | 0.63%   |
| Seagate ST9320325AS 320GB            | 2         | 0.63%   |
| Seagate ST2000LM007-1R8174 2TB       | 2         | 0.63%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 0.63%   |
| Seagate ST1000DM003-1SB102 1TB       | 2         | 0.63%   |
| SanDisk SSD PLUS 240GB               | 2         | 0.63%   |
| SanDisk SDSSDH3512G 512GB            | 2         | 0.63%   |
| SanDisk SDSSDA240G 240GB             | 2         | 0.63%   |
| SanDisk SDSSDA120G 120GB             | 2         | 0.63%   |
| SanDisk DF4064  64GB                 | 2         | 0.63%   |
| Samsung MZVLW256HEHP-000H1 256GB     | 2         | 0.63%   |
| Kingston SV300S37A120G 120GB SSD     | 2         | 0.63%   |
| Kingston SA400S37480G 480GB SSD      | 2         | 0.63%   |
| JMicron Generic 1TB                  | 2         | 0.63%   |
| HGST HTS545050A7E680 500GB           | 2         | 0.63%   |
| FORESEE P900F256GBH                  | 2         | 0.63%   |
| WDC WDS500G2B0C-00PXH0 500GB         | 1         | 0.32%   |
| WDC WDS500G2B0B-00YS70 500GB SSD     | 1         | 0.32%   |
| WDC WDS480G2G0B-00EPW0 480GB SSD     | 1         | 0.32%   |
| WDC WDS250G1B0C-00S6U0 250GB         | 1         | 0.32%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 0.32%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 1         | 0.32%   |
| WDC WDS120G1G0A-00SS50 120GB SSD     | 1         | 0.32%   |
| WDC WDS100T2G0A-00JH30 1TB SSD       | 1         | 0.32%   |
| WDC WD80 0BEVE-11UYT0 80GB           | 1         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 40        | 46     | 32.79%  |
| WDC                 | 39        | 45     | 31.97%  |
| Toshiba             | 19        | 21     | 15.57%  |
| Hitachi             | 8         | 8      | 6.56%   |
| HGST                | 6         | 6      | 4.92%   |
| Samsung Electronics | 3         | 3      | 2.46%   |
| Maxtor              | 2         | 4      | 1.64%   |
| Unknown             | 1         | 2      | 0.82%   |
| OEM                 | 1         | 1      | 0.82%   |
| Maxtor 6            | 1         | 1      | 0.82%   |
| Hewlett-Packard     | 1         | 2      | 0.82%   |
| Fujitsu             | 1         | 2      | 0.82%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 16        | 20     | 17.02%  |
| Kingston            | 15        | 21     | 15.96%  |
| Samsung Electronics | 12        | 14     | 12.77%  |
| WDC                 | 7         | 10     | 7.45%   |
| China               | 7         | 7      | 7.45%   |
| Crucial             | 5         | 6      | 5.32%   |
| SPCC                | 4         | 5      | 4.26%   |
| A-DATA Technology   | 3         | 4      | 3.19%   |
| Vaseky              | 2         | 2      | 2.13%   |
| SK hynix            | 2         | 2      | 2.13%   |
| Micron Technology   | 2         | 3      | 2.13%   |
| LITEON              | 2         | 2      | 2.13%   |
| JMicron Technology  | 2         | 2      | 2.13%   |
| Intenso             | 2         | 3      | 2.13%   |
| V-GeN               | 1         | 1      | 1.06%   |
| Unknown             | 1         | 1      | 1.06%   |
| Transcend           | 1         | 1      | 1.06%   |
| OCZ                 | 1         | 1      | 1.06%   |
| Netac               | 1         | 1      | 1.06%   |
| Microtech           | 1         | 1      | 1.06%   |
| KingSpec            | 1         | 1      | 1.06%   |
| KingDian            | 1         | 1      | 1.06%   |
| KINGBANK            | 1         | 1      | 1.06%   |
| Intel               | 1         | 2      | 1.06%   |
| Hewlett-Packard     | 1         | 1      | 1.06%   |
| G521N               | 1         | 1      | 1.06%   |
| Apacer              | 1         | 3      | 1.06%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 109       | 141    | 39.35%  |
| SSD     | 82        | 117    | 29.6%   |
| NVMe    | 68        | 75     | 24.55%  |
| MMC     | 16        | 17     | 5.78%   |
| Unknown | 2         | 3      | 0.72%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 158       | 247    | 62.7%   |
| NVMe | 68        | 75     | 26.98%  |
| MMC  | 16        | 17     | 6.35%   |
| SAS  | 10        | 14     | 3.97%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 112       | 164    | 59.26%  |
| 0.51-1.0   | 65        | 77     | 34.39%  |
| 1.01-2.0   | 10        | 15     | 5.29%   |
| 3.01-4.0   | 1         | 1      | 0.53%   |
| 4.01-10.0  | 1         | 1      | 0.53%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 61        | 27.98%  |
| 101-250        | 53        | 24.31%  |
| 501-1000       | 40        | 18.35%  |
| 1001-2000      | 29        | 13.3%   |
| 51-100         | 11        | 5.05%   |
| More than 3000 | 8         | 3.67%   |
| 21-50          | 5         | 2.29%   |
| 2001-3000      | 5         | 2.29%   |
| Unknown        | 4         | 1.83%   |
| 1-20           | 2         | 0.92%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 48        | 21.72%  |
| 21-50          | 47        | 21.27%  |
| 101-250        | 42        | 19%     |
| 51-100         | 25        | 11.31%  |
| 251-500        | 22        | 9.95%   |
| 501-1000       | 21        | 9.5%    |
| 1001-2000      | 8         | 3.62%   |
| Unknown        | 4         | 1.81%   |
| 2001-3000      | 3         | 1.36%   |
| More than 3000 | 1         | 0.45%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                         | Computers | Drives | Percent |
|-----------------------------------------------|-----------|--------|---------|
| Seagate ST9320325AS 320GB                     | 2         | 2      | 9.09%   |
| WDC WD5000LPLX-66ZNTT1 500GB                  | 1         | 1      | 4.55%   |
| WDC WD10JPVX-22JC3T0 1TB                      | 1         | 1      | 4.55%   |
| WDC WD10EARS-00Y5B1 1TB                       | 1         | 1      | 4.55%   |
| Toshiba MQ01ABD100 1TB                        | 1         | 1      | 4.55%   |
| Toshiba MQ01ABD032 320GB                      | 1         | 1      | 4.55%   |
| Toshiba MK8052GSX 80GB                        | 1         | 1      | 4.55%   |
| SK hynix PC711 HFS001TDE9X073N 1TB            | 1         | 1      | 4.55%   |
| SK hynix BC511 HFM256GDJTNI-82A0A 256GB       | 1         | 1      | 4.55%   |
| Seagate ST3750528AS 752GB                     | 1         | 1      | 4.55%   |
| Seagate ST2000LM003 HN-M201RAD 2TB            | 1         | 1      | 4.55%   |
| Seagate ST1000LM049-2GH172 1TB                | 1         | 1      | 4.55%   |
| Seagate ST1000DL002-9TT153 1TB                | 1         | 1      | 4.55%   |
| Samsung Electronics HM250HI 250GB             | 1         | 1      | 4.55%   |
| Samsung Electronics HD502HJ 500GB             | 1         | 1      | 4.55%   |
| Samsung Electronics HD250HJ 250GB             | 1         | 1      | 4.55%   |
| OCZ VERTEX4 256GB SSD                         | 1         | 1      | 4.55%   |
| Micron Technology MTFDDAT128MAM-1J2 128GB SSD | 1         | 2      | 4.55%   |
| Intenso lntenso SSD Sata III 128GB            | 1         | 1      | 4.55%   |
| Hitachi HTS543225L9A300 250GB                 | 1         | 1      | 4.55%   |
| G521N SSD 256GB                               | 1         | 1      | 4.55%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 6      | 23.81%  |
| WDC                 | 3         | 3      | 14.29%  |
| Toshiba             | 3         | 3      | 14.29%  |
| Samsung Electronics | 3         | 3      | 14.29%  |
| SK hynix            | 2         | 2      | 9.52%   |
| OCZ                 | 1         | 1      | 4.76%   |
| Micron Technology   | 1         | 2      | 4.76%   |
| Intenso             | 1         | 1      | 4.76%   |
| Hitachi             | 1         | 1      | 4.76%   |
| G521N               | 1         | 1      | 4.76%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 6      | 33.33%  |
| WDC                 | 3         | 3      | 20%     |
| Toshiba             | 3         | 3      | 20%     |
| Samsung Electronics | 3         | 3      | 20%     |
| Hitachi             | 1         | 1      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 15        | 16     | 71.43%  |
| SSD  | 4         | 5      | 19.05%  |
| NVMe | 2         | 2      | 9.52%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                       | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Toshiba MK5065GSXN 500GB    | 1         | 1      | 50%     |
| Hitachi HUA722010CLA330 1TB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 50%     |
| Hitachi | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 108       | 179    | 45.76%  |
| Works    | 105       | 149    | 44.49%  |
| Malfunc  | 21        | 23     | 8.9%    |
| Failed   | 2         | 2      | 0.85%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 147       | 57.65%  |
| AMD                            | 22        | 8.63%   |
| Samsung Electronics            | 14        | 5.49%   |
| SK hynix                       | 8         | 3.14%   |
| SanDisk                        | 8         | 3.14%   |
| ASMedia Technology             | 7         | 2.75%   |
| Silicon Motion                 | 6         | 2.35%   |
| Phison Electronics             | 5         | 1.96%   |
| Marvell Technology Group       | 5         | 1.96%   |
| Micron Technology              | 4         | 1.57%   |
| Shenzhen Longsys Electronics   | 3         | 1.18%   |
| Kingston Technology Company    | 3         | 1.18%   |
| Zhaoxin                        | 2         | 0.78%   |
| Realtek Semiconductor          | 2         | 0.78%   |
| Nvidia                         | 2         | 0.78%   |
| Micron/Crucial Technology      | 2         | 0.78%   |
| MAXIO Technology (Hangzhou)    | 2         | 0.78%   |
| KIOXIA                         | 2         | 0.78%   |
| JMicron Technology             | 2         | 0.78%   |
| Beijing Starblaze Technology   | 2         | 0.78%   |
| Toshiba America Info Systems   | 1         | 0.39%   |
| Solid State Storage Technology | 1         | 0.39%   |
| Loongson Technology            | 1         | 0.39%   |
| Lite-On Technology             | 1         | 0.39%   |
| Apple                          | 1         | 0.39%   |
| ADATA Technology               | 1         | 0.39%   |
| Unknown                        | 1         | 0.39%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 16        | 5.84%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 15        | 5.47%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 13        | 4.74%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 11        | 4.01%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 10        | 3.65%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 9         | 3.28%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 7         | 2.55%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 7         | 2.55%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 6         | 2.19%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 6         | 2.19%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 6         | 2.19%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 6         | 2.19%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 6         | 2.19%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 6         | 2.19%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 5         | 1.82%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 5         | 1.82%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 5         | 1.82%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4         | 1.46%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 1.46%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 1.46%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 4         | 1.46%   |
| SK hynix BC511 NVMe SSD                                                        | 3         | 1.09%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 1.09%   |
| Phison PS5013 E13 NVMe Controller                                              | 3         | 1.09%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller               | 3         | 1.09%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 3         | 1.09%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 3         | 1.09%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 3         | 1.09%   |
| Zhaoxin ZX-100/ZX-200/KX-6000/KX-6000G StorX AHCI Controller                   | 2         | 0.73%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 2         | 0.73%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 2         | 0.73%   |
| Shenzhen Longsys Non-Volatile memory controller                                | 2         | 0.73%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 2         | 0.73%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 2         | 0.73%   |
| Micron 2200S NVMe SSD [Cassandra]                                              | 2         | 0.73%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                   | 2         | 0.73%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 2         | 0.73%   |
| Intel Tiger Lake-LP SATA Controller                                            | 2         | 0.73%   |
| Intel SATA Controller [RAID mode]                                              | 2         | 0.73%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 0.73%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 159       | 63.1%   |
| NVMe | 67        | 26.59%  |
| IDE  | 17        | 6.75%   |
| RAID | 9         | 3.57%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 169       | 79.34%  |
| AMD          | 36        | 16.9%   |
| Phytium      | 3         | 1.41%   |
| CentaurHauls | 2         | 0.94%   |
| ARM          | 2         | 0.94%   |
| Unknown      | 1         | 0.47%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-10700 CPU @ 2.90GHz             | 6         | 2.82%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 2.35%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 4         | 1.88%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 4         | 1.88%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 1.88%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 4         | 1.88%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 1.41%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 1.41%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 3         | 1.41%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 1.41%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 1.41%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 2         | 0.94%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 0.94%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 0.94%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.94%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 0.94%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 2         | 0.94%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 2         | 0.94%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 0.94%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 2         | 0.94%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 0.94%   |
| Intel Core i5-8259U CPU @ 2.30GHz             | 2         | 0.94%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 0.94%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 0.94%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 0.94%   |
| Intel Core i3-6100 CPU @ 3.70GHz              | 2         | 0.94%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 2         | 0.94%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 2         | 0.94%   |
| Intel Core i3-10100 CPU @ 3.60GHz             | 2         | 0.94%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 2         | 0.94%   |
| Intel Celeron CPU 1007U @ 1.50GHz             | 2         | 0.94%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 2         | 0.94%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 2         | 0.94%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 0.94%   |
| ARM Processor                                 | 2         | 0.94%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 0.94%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 0.94%   |
| AMD Ryzen 5 4600U with Radeon Graphics        | 2         | 0.94%   |
| AMD Ryzen 5 3600 6-Core Processor             | 2         | 0.94%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 0.94%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 50        | 23.47%  |
| Intel Core i5           | 46        | 21.6%   |
| Other                   | 20        | 9.39%   |
| Intel Core i3           | 20        | 9.39%   |
| Intel Celeron           | 13        | 6.1%    |
| AMD Ryzen 5             | 10        | 4.69%   |
| Intel Core 2 Duo        | 8         | 3.76%   |
| AMD Ryzen 7             | 8         | 3.76%   |
| Intel Atom              | 6         | 2.82%   |
| Intel Pentium Dual-Core | 4         | 1.88%   |
| AMD FX                  | 4         | 1.88%   |
| Intel Xeon              | 3         | 1.41%   |
| Intel Pentium           | 3         | 1.41%   |
| AMD Ryzen 3             | 3         | 1.41%   |
| Intel Pentium Silver    | 2         | 0.94%   |
| Intel Core i9           | 2         | 0.94%   |
| AMD A10                 | 2         | 0.94%   |
| Intel Core m3           | 1         | 0.47%   |
| Intel Core M            | 1         | 0.47%   |
| Intel Celeron Dual-Core | 1         | 0.47%   |
| AMD Ryzen 7 PRO         | 1         | 0.47%   |
| AMD Ryzen 5 PRO         | 1         | 0.47%   |
| AMD E1                  | 1         | 0.47%   |
| AMD E                   | 1         | 0.47%   |
| AMD C-60                | 1         | 0.47%   |
| AMD Athlon              | 1         | 0.47%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 93        | 43.66%  |
| 4      | 80        | 37.56%  |
| 8      | 17        | 7.98%   |
| 6      | 15        | 7.04%   |
| 10     | 3         | 1.41%   |
| 12     | 2         | 0.94%   |
| 24     | 1         | 0.47%   |
| 3      | 1         | 0.47%   |
| 1      | 1         | 0.47%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 211       | 99.06%  |
| 3      | 2         | 0.94%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 149       | 69.95%  |
| 1      | 64        | 30.05%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 196       | 92.02%  |
| Unknown        | 17        | 7.98%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 53        | 24.54%  |
| 0x306a9    | 19        | 8.8%    |
| 0x806ec    | 10        | 4.63%   |
| 0x806e9    | 9         | 4.17%   |
| 0x40651    | 9         | 4.17%   |
| 0x306c3    | 8         | 3.7%    |
| 0x206a7    | 8         | 3.7%    |
| 0x306d4    | 7         | 3.24%   |
| 0x1067a    | 7         | 3.24%   |
| 0x406e3    | 6         | 2.78%   |
| 0xa0655    | 5         | 2.31%   |
| 0x906ea    | 5         | 2.31%   |
| 0x906e9    | 4         | 1.85%   |
| 0x806ea    | 4         | 1.85%   |
| 0x906a3    | 3         | 1.39%   |
| 0x806c1    | 3         | 1.39%   |
| 0x706a8    | 3         | 1.39%   |
| 0x406c4    | 3         | 1.39%   |
| 0x08600106 | 3         | 1.39%   |
| 0x08108109 | 3         | 1.39%   |
| 0x506e3    | 2         | 0.93%   |
| 0x30678    | 2         | 0.93%   |
| 0x20655    | 2         | 0.93%   |
| 0x0a50000d | 2         | 0.93%   |
| 0x08600104 | 2         | 0.93%   |
| 0x08200103 | 2         | 0.93%   |
| 0x08108102 | 2         | 0.93%   |
| 0x0500010d | 2         | 0.93%   |
| 0xb06a3    | 1         | 0.46%   |
| 0xb0671    | 1         | 0.46%   |
| 0xa0653    | 1         | 0.46%   |
| 0xa0652    | 1         | 0.46%   |
| 0x906eb    | 1         | 0.46%   |
| 0x806c2    | 1         | 0.46%   |
| 0x706a1    | 1         | 0.46%   |
| 0x6fd      | 1         | 0.46%   |
| 0x406c3    | 1         | 0.46%   |
| 0x306f2    | 1         | 0.46%   |
| 0x206c2    | 1         | 0.46%   |
| 0x10676    | 1         | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 40        | 18.78%  |
| IvyBridge        | 24        | 11.27%  |
| Haswell          | 20        | 9.39%   |
| Penryn           | 13        | 6.1%    |
| Skylake          | 11        | 5.16%   |
| Unknown          | 11        | 5.16%   |
| SandyBridge      | 10        | 4.69%   |
| CometLake        | 10        | 4.69%   |
| Broadwell        | 10        | 4.69%   |
| Zen 2            | 9         | 4.23%   |
| Silvermont       | 9         | 4.23%   |
| Goldmont plus    | 6         | 2.82%   |
| Zen+             | 5         | 2.35%   |
| Zen              | 5         | 2.35%   |
| Alderlake Hybrid | 5         | 2.35%   |
| Zen 3            | 4         | 1.88%   |
| Westmere         | 4         | 1.88%   |
| TigerLake        | 4         | 1.88%   |
| Bobcat           | 3         | 1.41%   |
| Piledriver       | 2         | 0.94%   |
| Goldmont         | 2         | 0.94%   |
| Excavator        | 2         | 0.94%   |
| Bulldozer        | 2         | 0.94%   |
| Jaguar           | 1         | 0.47%   |
| Core             | 1         | 0.47%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 138       | 52.47%  |
| Nvidia              | 69        | 26.24%  |
| AMD                 | 52        | 19.77%  |
| Zhaoxin             | 2         | 0.76%   |
| Phytium Technology  | 1         | 0.38%   |
| Loongson Technology | 1         | 0.38%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 12        | 4.51%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 4.14%   |
| Intel HD Graphics 5500                                                                   | 9         | 3.38%   |
| Intel HD Graphics 620                                                                    | 8         | 3.01%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8         | 3.01%   |
| AMD Renoir                                                                               | 7         | 2.63%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 2.63%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 2.26%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 6         | 2.26%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 2.26%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 2.26%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 6         | 2.26%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 5         | 1.88%   |
| Intel UHD Graphics 620                                                                   | 5         | 1.88%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 1.88%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 5         | 1.88%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 1.5%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 1.5%    |
| Intel HD Graphics 630                                                                    | 4         | 1.5%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 1.5%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 1.13%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 3         | 1.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3         | 1.13%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.13%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 1.13%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 3         | 1.13%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 3         | 1.13%   |
| Zhaoxin ZX-E C-960 GPU                                                                   | 2         | 0.75%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 0.75%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 0.75%   |
| Nvidia GP108M [GeForce MX250]                                                            | 2         | 0.75%   |
| Nvidia GP108BM [GeForce MX250]                                                           | 2         | 0.75%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.75%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 0.75%   |
| Nvidia GM108M [GeForce MX110]                                                            | 2         | 0.75%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 2         | 0.75%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.75%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 2         | 0.75%   |
| Nvidia GK107M [GeForce GT 650M]                                                          | 2         | 0.75%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 88        | 41.31%  |
| Intel + Nvidia          | 40        | 18.78%  |
| 1 x AMD                 | 40        | 18.78%  |
| 1 x Nvidia              | 27        | 12.68%  |
| Intel + AMD             | 8         | 3.76%   |
| Other                   | 2         | 0.94%   |
| 2 x AMD                 | 2         | 0.94%   |
| 1 x Zhaoxin             | 2         | 0.94%   |
| AMD + Nvidia            | 2         | 0.94%   |
| 1 x Phytium Technology  | 1         | 0.47%   |
| 1 x Loongson Technology | 1         | 0.47%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 163       | 76.17%  |
| Proprietary | 34        | 15.89%  |
| Unknown     | 17        | 7.94%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 124       | 56.88%  |
| 1.01-2.0   | 43        | 19.72%  |
| 3.01-4.0   | 21        | 9.63%   |
| 0.01-0.5   | 15        | 6.88%   |
| 0.51-1.0   | 8         | 3.67%   |
| 7.01-8.0   | 4         | 1.83%   |
| 5.01-6.0   | 3         | 1.38%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 31        | 14.49%  |
| Samsung Electronics     | 30        | 14.02%  |
| BOE                     | 28        | 13.08%  |
| Chimei Innolux          | 19        | 8.88%   |
| LG Display              | 17        | 7.94%   |
| Goldstar                | 12        | 5.61%   |
| Hewlett-Packard         | 8         | 3.74%   |
| ViewSonic               | 6         | 2.8%    |
| Dell                    | 5         | 2.34%   |
| CSO                     | 5         | 2.34%   |
| Lenovo                  | 4         | 1.87%   |
| AOC                     | 4         | 1.87%   |
| Philips                 | 3         | 1.4%    |
| Iiyama                  | 3         | 1.4%    |
| HKC                     | 3         | 1.4%    |
| BenQ                    | 3         | 1.4%    |
| RTK                     | 2         | 0.93%   |
| InfoVision              | 2         | 0.93%   |
| Chi Mei Optoelectronics | 2         | 0.93%   |
| Apple                   | 2         | 0.93%   |
| Ancor Communications    | 2         | 0.93%   |
| Acer                    | 2         | 0.93%   |
| Xiaomi                  | 1         | 0.47%   |
| Unknown                 | 1         | 0.47%   |
| Toshiba                 | 1         | 0.47%   |
| TMX                     | 1         | 0.47%   |
| TFC                     | 1         | 0.47%   |
| SKY                     | 1         | 0.47%   |
| Sharp                   | 1         | 0.47%   |
| SAC                     | 1         | 0.47%   |
| Positivo                | 1         | 0.47%   |
| PANDA                   | 1         | 0.47%   |
| MSI                     | 1         | 0.47%   |
| JDI                     | 1         | 0.47%   |
| InnoLux Display         | 1         | 0.47%   |
| Hisense                 | 1         | 0.47%   |
| HB@                     | 1         | 0.47%   |
| HannStar                | 1         | 0.47%   |
| Gateway                 | 1         | 0.47%   |
| DTV                     | 1         | 0.47%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| ViewSonic VA2478-H-2 VSC8335 1920x1080 527x296mm 23.8-inch            | 3         | 1.36%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 3         | 1.36%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 3         | 1.36%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch           | 2         | 0.9%    |
| Goldstar 20EN33 GSM4EE1 1600x900 443x249mm 20.0-inch                  | 2         | 0.9%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 0.9%    |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch       | 2         | 0.9%    |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                 | 2         | 0.9%    |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 2         | 0.9%    |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch         | 2         | 0.9%    |
| AU Optronics LCD Monitor AUO226D 1920x1080 276x155mm 12.5-inch        | 2         | 0.9%    |
| Xiaomi Mi TV XMD0076 3840x2160 800x450mm 36.1-inch                    | 1         | 0.45%   |
| ViewSonic VX2481-mh VSC3933 1920x1080 527x296mm 23.8-inch             | 1         | 0.45%   |
| ViewSonic VA2431-H-2 VSC3A22 1920x1080 527x296mm 23.8-inch            | 1         | 0.45%   |
| ViewSonic VA2430-H-3 VSC3A3E 1920x1080 527x296mm 23.8-inch            | 1         | 0.45%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 1         | 0.45%   |
| Toshiba TV TSB0108 1360x768 698x393mm 31.5-inch                       | 1         | 0.45%   |
| TMX TL140VDXP04-0 TMX1398 1920x1080 309x174mm 14.0-inch               | 1         | 0.45%   |
| TFC TF2411 TFC0238 1920x1080 527x296mm 23.8-inch                      | 1         | 0.45%   |
| SKY 24X1Q SKY2380 2560x1440 520x290mm 23.4-inch                       | 1         | 0.45%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch               | 1         | 0.45%   |
| Samsung Electronics SyncMaster SAM060B 1920x1080 510x290mm 23.1-inch  | 1         | 0.45%   |
| Samsung Electronics SyncMaster SAM0601 1600x900                       | 1         | 0.45%   |
| Samsung Electronics SyncMaster SAM05FF 1600x900 443x249mm 20.0-inch   | 1         | 0.45%   |
| Samsung Electronics SyncMaster SAM02B6 1920x1200 518x324mm 24.1-inch  | 1         | 0.45%   |
| Samsung Electronics SyncMaster SAM0167 1280x1024 338x270mm 17.0-inch  | 1         | 0.45%   |
| Samsung Electronics SMT24A550 SAM07B5 1920x1080 531x299mm 24.0-inch   | 1         | 0.45%   |
| Samsung Electronics S32B80P SAM71F1 3840x2160 698x393mm 31.5-inch     | 1         | 0.45%   |
| Samsung Electronics S24E360 SAM0C10 1920x1080 520x290mm 23.4-inch     | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SMS23A350H 1920x1080                  | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch  | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC384A 1366x768 344x194mm 15.5-inch  | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch  | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch  | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC314B 1600x900 344x194mm 15.5-inch  | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SDC864D 1920x1080 293x165mm 13.2-inch | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SDC534B 1600x900 382x215mm 17.3-inch  | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch  | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SDC4A42 1366x768 309x174mm 14.0-inch  | 1         | 0.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 93        | 44.93%  |
| 1366x768 (WXGA)    | 54        | 26.09%  |
| 1600x900 (HD+)     | 10        | 4.83%   |
| 3840x2160 (4K)     | 8         | 3.86%   |
| 2560x1440 (QHD)    | 7         | 3.38%   |
| 2560x1600          | 4         | 1.93%   |
| 3000x2000          | 3         | 1.45%   |
| 2880x1800          | 3         | 1.45%   |
| 2160x1440          | 3         | 1.45%   |
| 3840x1080          | 2         | 0.97%   |
| 1920x540           | 2         | 0.97%   |
| 1920x1200 (WUXGA)  | 2         | 0.97%   |
| 1440x900 (WXGA+)   | 2         | 0.97%   |
| 1360x768           | 2         | 0.97%   |
| 1280x1024 (SXGA)   | 2         | 0.97%   |
| Unknown            | 2         | 0.97%   |
| 3440x1440          | 1         | 0.48%   |
| 3200x1800 (QHD+)   | 1         | 0.48%   |
| 2736x1824          | 1         | 0.48%   |
| 2288x1287          | 1         | 0.48%   |
| 2160x1350          | 1         | 0.48%   |
| 1680x945           | 1         | 0.48%   |
| 1680x1050 (WSXGA+) | 1         | 0.48%   |
| 1280x800 (WXGA)    | 1         | 0.48%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 56        | 25.93%  |
| 13      | 32        | 14.81%  |
| 23      | 24        | 11.11%  |
| 14      | 22        | 10.19%  |
| 24      | 10        | 4.63%   |
| 21      | 10        | 4.63%   |
| Unknown | 9         | 4.17%   |
| 27      | 8         | 3.7%    |
| 18      | 6         | 2.78%   |
| 12      | 6         | 2.78%   |
| 17      | 5         | 2.31%   |
| 11      | 4         | 1.85%   |
| 32      | 3         | 1.39%   |
| 31      | 3         | 1.39%   |
| 20      | 3         | 1.39%   |
| 84      | 2         | 0.93%   |
| 25      | 2         | 0.93%   |
| 19      | 2         | 0.93%   |
| 16      | 2         | 0.93%   |
| 142     | 1         | 0.46%   |
| 72      | 1         | 0.46%   |
| 65      | 1         | 0.46%   |
| 54      | 1         | 0.46%   |
| 40      | 1         | 0.46%   |
| 22      | 1         | 0.46%   |
| 10      | 1         | 0.46%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 97        | 45.75%  |
| 501-600        | 42        | 19.81%  |
| 201-300        | 24        | 11.32%  |
| 401-500        | 21        | 9.91%   |
| Unknown        | 9         | 4.25%   |
| 351-400        | 6         | 2.83%   |
| 701-800        | 3         | 1.42%   |
| 601-700        | 3         | 1.42%   |
| 1501-2000      | 3         | 1.42%   |
| 1001-1500      | 2         | 0.94%   |
| More than 2000 | 1         | 0.47%   |
| 801-900        | 1         | 0.47%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 167       | 83.92%  |
| 16/10   | 15        | 7.54%   |
| 3/2     | 8         | 4.02%   |
| Unknown | 7         | 3.52%   |
| 5/4     | 1         | 0.5%    |
| 1.00    | 1         | 0.5%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 56        | 25.93%  |
| 81-90          | 44        | 20.37%  |
| 201-250        | 37        | 17.13%  |
| 71-80          | 10        | 4.63%   |
| 151-200        | 10        | 4.63%   |
| Unknown        | 9         | 4.17%   |
| 301-350        | 8         | 3.7%    |
| 61-70          | 7         | 3.24%   |
| More than 1000 | 6         | 2.78%   |
| 351-500        | 6         | 2.78%   |
| 251-300        | 6         | 2.78%   |
| 141-150        | 6         | 2.78%   |
| 51-60          | 3         | 1.39%   |
| 121-130        | 3         | 1.39%   |
| 111-120        | 2         | 0.93%   |
| 41-50          | 1         | 0.46%   |
| 131-140        | 1         | 0.46%   |
| 501-1000       | 1         | 0.46%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 67        | 31.75%  |
| 51-100        | 56        | 26.54%  |
| 121-160       | 50        | 23.7%   |
| 161-240       | 17        | 8.06%   |
| Unknown       | 9         | 4.27%   |
| More than 240 | 8         | 3.79%   |
| 1-50          | 4         | 1.9%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 174       | 80.93%  |
| 2     | 31        | 14.42%  |
| 0     | 9         | 4.19%   |
| 3     | 1         | 0.47%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 134       | 43.93%  |
| Intel                           | 80        | 26.23%  |
| Qualcomm Atheros                | 43        | 14.1%   |
| Broadcom                        | 9         | 2.95%   |
| MediaTek                        | 6         | 1.97%   |
| Marvell Technology Group        | 5         | 1.64%   |
| Xiaomi                          | 4         | 1.31%   |
| TP-Link                         | 3         | 0.98%   |
| Broadcom Limited                | 3         | 0.98%   |
| Ralink Technology               | 2         | 0.66%   |
| Ralink                          | 2         | 0.66%   |
| Nvidia                          | 2         | 0.66%   |
| Unknown                         | 1         | 0.33%   |
| Samsung Electronics             | 1         | 0.33%   |
| Qualcomm Atheros Communications | 1         | 0.33%   |
| OPPO Electronics                | 1         | 0.33%   |
| NXP Semiconductors              | 1         | 0.33%   |
| NetGear                         | 1         | 0.33%   |
| Loongson Technology             | 1         | 0.33%   |
| IMC Networks                    | 1         | 0.33%   |
| Huawei Technologies             | 1         | 0.33%   |
| Hewlett-Packard                 | 1         | 0.33%   |
| ASIX Electronics                | 1         | 0.33%   |
| Aquantia                        | 1         | 0.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 93        | 26.5%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 20        | 5.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 14        | 3.99%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 8         | 2.28%   |
| Intel Wireless 3165                                               | 8         | 2.28%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 7         | 1.99%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 7         | 1.99%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 1.71%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 1.42%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 1.42%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 1.42%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 1.42%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 4         | 1.14%   |
| Intel Wireless 8265 / 8275                                        | 4         | 1.14%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 1.14%   |
| Intel Ethernet Connection (12) I219-V                             | 4         | 1.14%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 1.14%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 1.14%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 3         | 0.85%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 3         | 0.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 3         | 0.85%   |
| Intel Wireless 7260                                               | 3         | 0.85%   |
| Intel Wireless 3160                                               | 3         | 0.85%   |
| Intel WiFi Link 5100                                              | 3         | 0.85%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 0.85%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 3         | 0.85%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.57%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.57%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.57%   |
| Realtek RTL8191SEvA Wireless LAN Controller                       | 2         | 0.57%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)         | 2         | 0.57%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 0.57%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.57%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 2         | 0.57%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 2         | 0.57%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 0.57%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 0.57%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 0.57%   |
| Intel Wireless 7265                                               | 2         | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 64        | 37.87%  |
| Realtek Semiconductor           | 41        | 24.26%  |
| Qualcomm Atheros                | 40        | 23.67%  |
| MediaTek                        | 5         | 2.96%   |
| Broadcom                        | 4         | 2.37%   |
| TP-Link                         | 3         | 1.78%   |
| Broadcom Limited                | 3         | 1.78%   |
| Ralink Technology               | 2         | 1.18%   |
| Ralink                          | 2         | 1.18%   |
| Xiaomi                          | 1         | 0.59%   |
| Qualcomm Atheros Communications | 1         | 0.59%   |
| NetGear                         | 1         | 0.59%   |
| Marvell Technology Group        | 1         | 0.59%   |
| IMC Networks                    | 1         | 0.59%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 14        | 8.24%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 8         | 4.71%   |
| Intel Wireless 3165                                            | 8         | 4.71%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 7         | 4.12%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 7         | 4.12%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 5         | 2.94%   |
| Intel Wi-Fi 6 AX200                                            | 5         | 2.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 5         | 2.94%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 4         | 2.35%   |
| Intel Wireless 8265 / 8275                                     | 4         | 2.35%   |
| Intel Wi-Fi 6 AX201                                            | 4         | 2.35%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 2.35%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 4         | 2.35%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 3         | 1.76%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 3         | 1.76%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 3         | 1.76%   |
| Intel Wireless 7260                                            | 3         | 1.76%   |
| Intel Wireless 3160                                            | 3         | 1.76%   |
| Intel WiFi Link 5100                                           | 3         | 1.76%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 3         | 1.76%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 3         | 1.76%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 1.18%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.18%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.18%   |
| Realtek RTL8191SEvA Wireless LAN Controller                    | 2         | 1.18%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)      | 2         | 1.18%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 1.18%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 1.18%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 2         | 1.18%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 1.18%   |
| Intel Wireless 7265                                            | 2         | 1.18%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 1.18%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 1.18%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 1.18%   |
| Xiaomi MediaTek MT7601U [MI WiFi]                              | 1         | 0.59%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1         | 0.59%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                          | 1         | 0.59%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 0.59%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 0.59%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 1         | 0.59%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 121       | 68.36%  |
| Intel                    | 28        | 15.82%  |
| Qualcomm Atheros         | 6         | 3.39%   |
| Broadcom                 | 5         | 2.82%   |
| Marvell Technology Group | 4         | 2.26%   |
| Xiaomi                   | 3         | 1.69%   |
| Nvidia                   | 2         | 1.13%   |
| Samsung Electronics      | 1         | 0.56%   |
| OPPO Electronics         | 1         | 0.56%   |
| MediaTek                 | 1         | 0.56%   |
| Loongson Technology      | 1         | 0.56%   |
| Huawei Technologies      | 1         | 0.56%   |
| Hewlett-Packard          | 1         | 0.56%   |
| ASIX Electronics         | 1         | 0.56%   |
| Aquantia                 | 1         | 0.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 93        | 51.96%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 20        | 11.17%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 3.35%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 2.79%   |
| Intel Ethernet Connection (12) I219-V                             | 4         | 2.23%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 1.12%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 1.12%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 1.12%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 1.12%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.12%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 1.12%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 1.12%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 1.12%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 2         | 1.12%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.56%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.56%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.56%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.56%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.56%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.56%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.56%   |
| OPPO OnePlus Nord                                                 | 1         | 0.56%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.56%   |
| Nvidia MCP61 Ethernet                                             | 1         | 0.56%   |
| MediaTek moto g22                                                 | 1         | 0.56%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 0.56%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 0.56%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1         | 0.56%   |
| Loongson Gigabit Ethernet Controller                              | 1         | 0.56%   |
| Intel Ethernet Controller I226-V                                  | 1         | 0.56%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.56%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.56%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.56%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.56%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.56%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.56%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.56%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.56%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 0.56%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 0.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 167       | 50%     |
| WiFi     | 165       | 49.4%   |
| Modem    | 1         | 0.3%    |
| Unknown  | 1         | 0.3%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 130       | 62.5%   |
| Ethernet | 78        | 37.5%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 109       | 50.93%  |
| 1     | 90        | 42.06%  |
| 0     | 10        | 4.67%   |
| 3     | 4         | 1.87%   |
| 4     | 1         | 0.47%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 197       | 92.06%  |
| Yes  | 17        | 7.94%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 54        | 38.57%  |
| Qualcomm Atheros Communications | 23        | 16.43%  |
| Realtek Semiconductor           | 16        | 11.43%  |
| Cambridge Silicon Radio         | 11        | 7.86%   |
| Foxconn / Hon Hai               | 8         | 5.71%   |
| Broadcom                        | 7         | 5%      |
| Realtek                         | 5         | 3.57%   |
| Lite-On Technology              | 4         | 2.86%   |
| IMC Networks                    | 4         | 2.86%   |
| Toshiba                         | 1         | 0.71%   |
| Ralink Technology               | 1         | 0.71%   |
| MediaTek                        | 1         | 0.71%   |
| Marvell Semiconductor           | 1         | 0.71%   |
| Dynex                           | 1         | 0.71%   |
| Dell                            | 1         | 0.71%   |
| ASUSTek Computer                | 1         | 0.71%   |
| Apple                           | 1         | 0.71%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 24        | 17.14%  |
| Qualcomm Atheros  Bluetooth Device                                                  | 16        | 11.43%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 11        | 7.86%   |
| Realtek Bluetooth Radio                                                             | 9         | 6.43%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 9         | 6.43%   |
| Intel AX201 Bluetooth                                                               | 9         | 6.43%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 5         | 3.57%   |
| Realtek 802.11ac WLAN Adapter                                                       | 5         | 3.57%   |
| Intel Bluetooth Device                                                              | 5         | 3.57%   |
| Intel AX200 Bluetooth                                                               | 5         | 3.57%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 4         | 2.86%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 2.14%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 1.43%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 2         | 1.43%   |
| Lite-On Bluetooth Device                                                            | 2         | 1.43%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.43%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 2         | 1.43%   |
| IMC Networks Bluetooth Device                                                       | 2         | 1.43%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 1.43%   |
| Broadcom HP Portable SoftSailing                                                    | 2         | 1.43%   |
| Toshiba Bluetooth Radio                                                             | 1         | 0.71%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.71%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.71%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 1         | 0.71%   |
| MediaTek BT                                                                         | 1         | 0.71%   |
| Marvell Bluetooth and Wireless LAN Composite                                        | 1         | 0.71%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.71%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.71%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 1         | 0.71%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 1         | 0.71%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.71%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.71%   |
| Foxconn / Hon Hai BCM43142A0                                                        | 1         | 0.71%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 0.71%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]                            | 1         | 0.71%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.71%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 0.71%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 1         | 0.71%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 1         | 0.71%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 162       | 60.9%   |
| AMD                                          | 52        | 19.55%  |
| Nvidia                                       | 38        | 14.29%  |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 0.75%   |
| Zhaoxin                                      | 2         | 0.75%   |
| C-Media Electronics                          | 2         | 0.75%   |
| XMOS                                         | 1         | 0.38%   |
| Phytium Technology                           | 1         | 0.38%   |
| Microdia                                     | 1         | 0.38%   |
| Loongson Technology                          | 1         | 0.38%   |
| JMTek                                        | 1         | 0.38%   |
| Creative Technology                          | 1         | 0.38%   |
| BEHRINGER International                      | 1         | 0.38%   |
| ASUSTek Computer                             | 1         | 0.38%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 23        | 7.12%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 21        | 6.5%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 20        | 6.19%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 14        | 4.33%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 11        | 3.41%   |
| Intel 8 Series HD Audio Controller                                                                | 11        | 3.41%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 10        | 3.1%    |
| Intel Broadwell-U Audio Controller                                                                | 10        | 3.1%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 10        | 3.1%    |
| Intel Comet Lake PCH-V cAVS                                                                       | 8         | 2.48%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 8         | 2.48%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 8         | 2.48%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 7         | 2.17%   |
| Intel Cannon Lake PCH cAVS                                                                        | 7         | 2.17%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 7         | 2.17%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 7         | 2.17%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 1.86%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 1.55%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 1.55%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1.24%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 1.24%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 1.24%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 1.24%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 1.24%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 4         | 1.24%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 3         | 0.93%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.93%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 3         | 0.93%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 3         | 0.93%   |
| Nvidia Audio device                                                                               | 3         | 0.93%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 0.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.93%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 3         | 0.93%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 0.93%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 0.93%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 0.93%   |
| AMD FCH Azalia Controller                                                                         | 3         | 0.93%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                                    | 2         | 0.62%   |
| Zhaoxin ZX-E High Definition Audio Controller                                                     | 2         | 0.62%   |
| Zhaoxin ZX-100/KX-5000/KX-6000/KX-6000G High Definition Audio Controller                          | 2         | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Samsung Electronics                | 31        | 22.3%   |
| SK hynix                           | 26        | 18.71%  |
| Unknown                            | 16        | 11.51%  |
| Kingston                           | 15        | 10.79%  |
| Micron Technology                  | 12        | 8.63%   |
| Smart                              | 4         | 2.88%   |
| Ramaxel Technology                 | 4         | 2.88%   |
| Nanya Technology                   | 4         | 2.88%   |
| Crucial                            | 3         | 2.16%   |
| Corsair                            | 3         | 2.16%   |
| A-DATA Technology                  | 3         | 2.16%   |
| Unknown (ABCD)                     | 2         | 1.44%   |
| G.Skill                            | 2         | 1.44%   |
| Unknown                            | 2         | 1.44%   |
| Unknown (07FB)                     | 1         | 0.72%   |
| UniIC                              | 1         | 0.72%   |
| Team                               | 1         | 0.72%   |
| Smart Brazil                       | 1         | 0.72%   |
| MTASE                              | 1         | 0.72%   |
| Kingmax                            | 1         | 0.72%   |
| KINGBANK                           | 1         | 0.72%   |
| Kimtigo Semiconductor (HK) Limited | 1         | 0.72%   |
| JEDEC ID: 0000h                    | 1         | 0.72%   |
| CSX                                | 1         | 0.72%   |
| ChangXin Memory                    | 1         | 0.72%   |
| Apacer                             | 1         | 0.72%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB Row Of Chips DDR4 2667MT/s     | 3         | 2.01%   |
| Kingston RAM TF32D4U2S1MEH-8 8192MB DIMM DDR4 3200MT/s           | 3         | 2.01%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 2         | 1.34%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 2         | 1.34%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 2         | 1.34%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2133MT/s                  | 2         | 1.34%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.34%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.34%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 2         | 1.34%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.34%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.34%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 1.34%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1.34%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 2         | 1.34%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 1.34%   |
| Unknown                                                          | 2         | 1.34%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.67%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                        | 1         | 0.67%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                   | 1         | 0.67%   |
| Unknown RAM Module 4GB SODIMM LPDDR3 1600MT/s                    | 1         | 0.67%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2667MT/s                   | 1         | 0.67%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 0.67%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 1         | 0.67%   |
| Unknown RAM Module 4096MB DIMM DDR3 1067MT/s                     | 1         | 0.67%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                           | 1         | 0.67%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 1         | 0.67%   |
| Unknown RAM Module 2048MB SODIMM LPDDR3 1600MT/s                 | 1         | 0.67%   |
| Unknown RAM Module 2048MB SODIMM DDR3                            | 1         | 0.67%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 1         | 0.67%   |
| Unknown RAM Module 2048MB Chip DDR3 1066MT/s                     | 1         | 0.67%   |
| Unknown RAM Module 1024MB SODIMM LPDDR4 2400MT/s                 | 1         | 0.67%   |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 1         | 0.67%   |
| Unknown RAM 1866 CL10 Ser 8192MB DIMM DDR3 800MT/s               | 1         | 0.67%   |
| Unknown (07FB) RAM GST32G08SCL196P-26 32GB SODIMM DDR4 2667MT/s  | 1         | 0.67%   |
| UniIC RAM SCC08GU03H1F1C-26V 8192MB DIMM DDR4 2666MT/s           | 1         | 0.67%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s               | 1         | 0.67%   |
| Smart RAM SH564568FJ8NZRNSDR 2GB SODIMM DDR3 1600MT/s            | 1         | 0.67%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s            | 1         | 0.67%   |
| Smart RAM SG564568FG8NWKF-Z1 2GB SODIMM DDR2 800MT/s             | 1         | 0.67%   |
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s     | 1         | 0.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 64        | 51.2%   |
| DDR3    | 34        | 27.2%   |
| LPDDR4  | 8         | 6.4%    |
| LPDDR3  | 8         | 6.4%    |
| DDR5    | 3         | 2.4%    |
| SDRAM   | 2         | 1.6%    |
| LPDDR5  | 2         | 1.6%    |
| DDR2    | 2         | 1.6%    |
| Unknown | 2         | 1.6%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 78        | 61.9%   |
| DIMM         | 30        | 23.81%  |
| Row Of Chips | 15        | 11.9%   |
| Chip         | 2         | 1.59%   |
| Unknown      | 1         | 0.79%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 64        | 48.12%  |
| 4096  | 39        | 29.32%  |
| 2048  | 14        | 10.53%  |
| 16384 | 11        | 8.27%   |
| 1024  | 3         | 2.26%   |
| 32768 | 2         | 1.5%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 23        | 17.42%  |
| 1600    | 23        | 17.42%  |
| 3200    | 16        | 12.12%  |
| 2400    | 10        | 7.58%   |
| 2133    | 10        | 7.58%   |
| 2666    | 5         | 3.79%   |
| 1867    | 5         | 3.79%   |
| 1333    | 5         | 3.79%   |
| 4266    | 3         | 2.27%   |
| 1334    | 3         | 2.27%   |
| 1066    | 3         | 2.27%   |
| Unknown | 3         | 2.27%   |
| 6400    | 2         | 1.52%   |
| 4800    | 2         | 1.52%   |
| 3400    | 2         | 1.52%   |
| 3266    | 2         | 1.52%   |
| 5600    | 1         | 0.76%   |
| 4267    | 1         | 0.76%   |
| 4199    | 1         | 0.76%   |
| 3800    | 1         | 0.76%   |
| 3733    | 1         | 0.76%   |
| 3600    | 1         | 0.76%   |
| 3533    | 1         | 0.76%   |
| 3500    | 1         | 0.76%   |
| 3466    | 1         | 0.76%   |
| 3000    | 1         | 0.76%   |
| 2933    | 1         | 0.76%   |
| 2800    | 1         | 0.76%   |
| 1067    | 1         | 0.76%   |
| 800     | 1         | 0.76%   |
| 667     | 1         | 0.76%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Seiko Epson     | 1         | 50%     |
| Hewlett-Packard | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson ME 340 Series/Stylus NX130 Series | 1         | 50%     |
| HP Deskjet 3520 series                        | 1         | 50%     |

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
| Chicony Electronics                    | 34        | 25%     |
| Realtek Semiconductor                  | 13        | 9.56%   |
| Microdia                               | 12        | 8.82%   |
| IMC Networks                           | 11        | 8.09%   |
| Sunplus Innovation Technology          | 8         | 5.88%   |
| Silicon Motion                         | 7         | 5.15%   |
| Quanta                                 | 7         | 5.15%   |
| Syntek                                 | 6         | 4.41%   |
| Logitech                               | 6         | 4.41%   |
| Suyin                                  | 5         | 3.68%   |
| Lite-On Technology                     | 4         | 2.94%   |
| Bison Electronics                      | 4         | 2.94%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 2.21%   |
| Ricoh                                  | 2         | 1.47%   |
| Primax Electronics                     | 2         | 1.47%   |
| Alcor Micro                            | 2         | 1.47%   |
| LG Electronics                         | 1         | 0.74%   |
| Lenovo                                 | 1         | 0.74%   |
| kingcome                               | 1         | 0.74%   |
| icSpring                               | 1         | 0.74%   |
| Goodong Industry                       | 1         | 0.74%   |
| Generalplus Technology                 | 1         | 0.74%   |
| Arkmicro Technologies                  | 1         | 0.74%   |
| Apple                                  | 1         | 0.74%   |
| Acer                                   | 1         | 0.74%   |
| 2M UVC CAMERA                          | 1         | 0.74%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 8         | 5.84%   |
| IMC Networks Integrated Camera           | 5         | 3.65%   |
| Logitech Webcam C270                     | 4         | 2.92%   |
| IMC Networks HD Camera                   | 4         | 2.92%   |
| Chicony EasyCamera                       | 4         | 2.92%   |
| Syntek EasyCamera                        | 3         | 2.19%   |
| Silicon Motion Web Camera                | 3         | 2.19%   |
| Quanta HD User Facing                    | 3         | 2.19%   |
| Microdia Integrated_Webcam_HD            | 3         | 2.19%   |
| Chicony TOSHIBA Web Camera - HD          | 3         | 2.19%   |
| Syntek Integrated Camera                 | 2         | 1.46%   |
| Sunplus Integrated_Webcam_HD             | 2         | 1.46%   |
| Sunplus HD WebCam                        | 2         | 1.46%   |
| Realtek Integrated_Webcam_HD             | 2         | 1.46%   |
| Realtek HP "Truevision HD" laptop camera | 2         | 1.46%   |
| Quanta HP TrueVision HD Camera           | 2         | 1.46%   |
| Primax HP HD Webcam [Fixed]              | 2         | 1.46%   |
| Chicony HP Webcam                        | 2         | 1.46%   |
| Chicony HP HD Webcam                     | 2         | 1.46%   |
| Chicony HD WebCam                        | 2         | 1.46%   |
| Syntek Lenovo EasyCamera                 | 1         | 0.73%   |
| Suyin Integrated_Webcam_HD               | 1         | 0.73%   |
| Suyin HP Truevision HD                   | 1         | 0.73%   |
| Suyin HD WebCam                          | 1         | 0.73%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 1         | 0.73%   |
| Suyin 1.3M Front                         | 1         | 0.73%   |
| Sunplus XiaoMi USB 2.0 Webcam            | 1         | 0.73%   |
| Sunplus PC Camera                        | 1         | 0.73%   |
| Sunplus HP Wide Vision HD                | 1         | 0.73%   |
| Sunplus Asus Webcam                      | 1         | 0.73%   |
| Silicon Motion WebCam SC-13HDL11939N     | 1         | 0.73%   |
| Silicon Motion WebCam SC-10IRQ12340N     | 1         | 0.73%   |
| Silicon Motion WebCam SC-0311139N        | 1         | 0.73%   |
| Silicon Motion ATIV VGA Camera           | 1         | 0.73%   |
| Ricoh Sony Vaio Integrated Webcam        | 1         | 0.73%   |
| Ricoh Laptop_Integrated_Webcam_FHD       | 1         | 0.73%   |
| Realtek USB Camera                       | 1         | 0.73%   |
| Realtek Streamplify CAM                  | 1         | 0.73%   |
| Realtek Laptop_Integrated_Webcam_HD      | 1         | 0.73%   |
| Realtek Integrated_Webcam_FHD            | 1         | 0.73%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 10        | 37.04%  |
| Shenzhen Goodix Technology | 9         | 33.33%  |
| Upek                       | 5         | 18.52%  |
| Synaptics                  | 2         | 7.41%   |
| Elan Microelectronics      | 1         | 3.7%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                    | 6         | 22.22%  |
| Validity Sensors VFS495 Fingerprint Reader             | 5         | 18.52%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 3         | 11.11%  |
| Shenzhen Goodix Fingerprint Reader                     | 3         | 11.11%  |
| Validity Sensors VFS491                                | 2         | 7.41%   |
| Validity Sensors Swipe Fingerprint Sensor              | 2         | 7.41%   |
| Upek TCS5B Fingerprint sensor                          | 2         | 7.41%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 3.7%    |
| Synaptics UWP WBDI                                     | 1         | 3.7%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 3.7%    |
| Elan ELAN:Fingerprint                                  | 1         | 3.7%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Alcor Micro         | 3         | 50%     |
| Lenovo              | 1         | 16.67%  |
| Giesecke & Devrient | 1         | 16.67%  |
| Broadcom            | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader            | 3         | 50%     |
| Lenovo Integrated Smart Card Reader            | 1         | 16.67%  |
| Giesecke & Devrient StarSign CUT               | 1         | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 154       | 71.3%   |
| 1     | 50        | 23.15%  |
| 2     | 11        | 5.09%   |
| 3     | 1         | 0.46%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 27        | 36.99%  |
| Graphics card            | 22        | 30.14%  |
| Multimedia controller    | 8         | 10.96%  |
| Chipcard                 | 5         | 6.85%   |
| Net/wireless             | 4         | 5.48%   |
| Sound                    | 3         | 4.11%   |
| Unassigned class         | 1         | 1.37%   |
| Storage                  | 1         | 1.37%   |
| Communication controller | 1         | 1.37%   |
| Camera                   | 1         | 1.37%   |

