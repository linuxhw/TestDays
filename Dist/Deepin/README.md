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

Total: 317

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | 0XR1GT A00                  | Desktop     | [f01a35c9a7](https://linux-hardware.org/?probe=f01a35c9a7) | Nov 06, 2023 |
| HP            | Compaq Presario CQ40        | Notebook    | [ede0c05f18](https://linux-hardware.org/?probe=ede0c05f18) | Nov 04, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [3b669afc38](https://linux-hardware.org/?probe=3b669afc38) | Oct 26, 2023 |
| UNOWHY        | Y13G012S4EI                 | Notebook    | [eb2ef3f8d5](https://linux-hardware.org/?probe=eb2ef3f8d5) | Oct 24, 2023 |
| Intel         | DX58SO AAE29331-504         | Desktop     | [33d7713b52](https://linux-hardware.org/?probe=33d7713b52) | Oct 21, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [50698ed07c](https://linux-hardware.org/?probe=50698ed07c) | Oct 14, 2023 |
| Intel         | DX58SO AAE29331-504         | Desktop     | [afe13c52df](https://linux-hardware.org/?probe=afe13c52df) | Oct 11, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [e337e05dff](https://linux-hardware.org/?probe=e337e05dff) | Oct 08, 2023 |
| Timi          | RedmiBook Air 13            | Notebook    | [63ea7be36f](https://linux-hardware.org/?probe=63ea7be36f) | Oct 07, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [dc4ec4e72a](https://linux-hardware.org/?probe=dc4ec4e72a) | Oct 02, 2023 |
| HP            | EliteBook 845 14 inch G1... | Notebook    | [b409947c26](https://linux-hardware.org/?probe=b409947c26) | Sep 11, 2023 |
| HP            | EliteBook 845 14 inch G1... | Notebook    | [f7f7964c03](https://linux-hardware.org/?probe=f7f7964c03) | Sep 09, 2023 |
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

![OS](./All/images/pie_chart/os_name.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Deepin         | 47        | 20.43%  |
| Deepin 20      | 31        | 13.48%  |
| UOS 20         | 29        | 12.61%  |
| Deepin 15.11   | 27        | 11.74%  |
| Deepin 23      | 17        | 7.39%   |
| Deepin 15.9.2  | 12        | 5.22%   |
| Deepin 20.8    | 8         | 3.48%   |
| Deepin 20.9    | 7         | 3.04%   |
| Deepin 20.3    | 7         | 3.04%   |
| Deepin 20.1    | 7         | 3.04%   |
| Deepin 20 beta | 7         | 3.04%   |
| Deepin 20.5    | 4         | 1.74%   |
| Deepin 20.2.4  | 3         | 1.3%    |
| Deepin 20.2.3  | 3         | 1.3%    |
| Deepin 20.2.2  | 3         | 1.3%    |
| Deepin 15.10.1 | 3         | 1.3%    |
| Deepin 20.7.1  | 2         | 0.87%   |
| Deepin 20.6    | 2         | 0.87%   |
| Deepin 15.9.3  | 2         | 0.87%   |
| Deepin 2014.3  | 1         | 0.43%   |
| Deepin 20.7    | 1         | 0.43%   |
| Deepin 20.4    | 1         | 0.43%   |
| Deepin 20.2.1  | 1         | 0.43%   |
| Deepin 20.2    | 1         | 0.43%   |
| Deepin 15.9    | 1         | 0.43%   |
| Deepin 15.8    | 1         | 0.43%   |
| Deepin 15.7    | 1         | 0.43%   |
| Deepin 15.10   | 1         | 0.43%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Deepin | 221       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                             | Computers | Percent |
|-------------------------------------|-----------|---------|
| 4.15.0-30deepin-generic             | 41        | 17.83%  |
| 5.4.50-amd64-desktop                | 22        | 9.57%   |
| 4.15.0-29deepin-generic             | 19        | 8.26%   |
| 5.4.70-amd64-desktop                | 16        | 6.96%   |
| 5.10.60-amd64-desktop               | 12        | 5.22%   |
| 5.3.0-3-amd64                       | 10        | 4.35%   |
| 5.10.0-amd64-desktop                | 8         | 3.48%   |
| 5.7.7-amd64-desktop                 | 6         | 2.61%   |
| 5.18.17-amd64-desktop-hwe           | 6         | 2.61%   |
| 5.18.17-amd64-desktop-community-hwe | 6         | 2.61%   |
| 5.15.77-amd64-desktop               | 6         | 2.61%   |
| 5.10.29-amd64-desktop               | 6         | 2.61%   |
| 5.10.41-amd64-desktop               | 5         | 2.17%   |
| 5.10.36-amd64-desktop               | 5         | 2.17%   |
| 4.19.0-amd64-desktop                | 5         | 2.17%   |
| 6.1.32-amd64-desktop-hwe            | 4         | 1.74%   |
| 6.1.11-amd64-desktop-hwe            | 4         | 1.74%   |
| 5.10.18-amd64-desktop               | 4         | 1.74%   |
| 5.15.45-amd64-desktop               | 3         | 1.3%    |
| 5.15.24-amd64-desktop               | 3         | 1.3%    |
| 5.15.1-amd64-desktop                | 3         | 1.3%    |
| 5.10.50-amd64-desktop               | 3         | 1.3%    |
| 5.10.5-amd64-desktop+               | 3         | 1.3%    |
| 5.10.101-amd64-desktop              | 3         | 1.3%    |
| 5.8.14-amd64-desktop                | 2         | 0.87%   |
| 5.5.4-xanmod3                       | 2         | 0.87%   |
| 5.10.83-amd64-desktop               | 2         | 0.87%   |
| 4.19.0-arm64-desktop                | 2         | 0.87%   |
| 6.5.0                               | 1         | 0.43%   |
| 6.3.0-rc4-amd64-exton               | 1         | 0.43%   |
| 6.1.12-1-liquorix-amd64             | 1         | 0.43%   |
| 5.6.14-050614-generic               | 1         | 0.43%   |
| 5.6.12-xanmod1                      | 1         | 0.43%   |
| 5.4.2-xanmod2                       | 1         | 0.43%   |
| 5.3.8-xanmod6                       | 1         | 0.43%   |
| 5.2.14-050214-lowlatency            | 1         | 0.43%   |
| 5.15.34-amd64-desktop               | 1         | 0.43%   |
| 5.14.0-rc3-amd64-desktop            | 1         | 0.43%   |
| 5.12.18-amd64-desktop               | 1         | 0.43%   |
| 5.10.0-11-arm64                     | 1         | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 4.15.0   | 61        | 26.52%  |
| 5.4.50   | 22        | 9.57%   |
| 5.4.70   | 16        | 6.96%   |
| 5.18.17  | 12        | 5.22%   |
| 5.10.60  | 12        | 5.22%   |
| 5.3.0    | 10        | 4.35%   |
| 5.10.0   | 10        | 4.35%   |
| 4.19.0   | 8         | 3.48%   |
| 5.7.7    | 6         | 2.61%   |
| 5.15.77  | 6         | 2.61%   |
| 5.10.29  | 6         | 2.61%   |
| 5.10.41  | 5         | 2.17%   |
| 5.10.36  | 5         | 2.17%   |
| 6.1.32   | 4         | 1.74%   |
| 6.1.11   | 4         | 1.74%   |
| 5.10.18  | 4         | 1.74%   |
| 5.15.45  | 3         | 1.3%    |
| 5.15.24  | 3         | 1.3%    |
| 5.15.1   | 3         | 1.3%    |
| 5.10.50  | 3         | 1.3%    |
| 5.10.5   | 3         | 1.3%    |
| 5.10.101 | 3         | 1.3%    |
| 5.8.14   | 2         | 0.87%   |
| 5.5.4    | 2         | 0.87%   |
| 5.10.83  | 2         | 0.87%   |
| 6.5.0    | 1         | 0.43%   |
| 6.3.0    | 1         | 0.43%   |
| 6.1.12   | 1         | 0.43%   |
| 5.6.14   | 1         | 0.43%   |
| 5.6.12   | 1         | 0.43%   |
| 5.4.2    | 1         | 0.43%   |
| 5.3.8    | 1         | 0.43%   |
| 5.2.14   | 1         | 0.43%   |
| 5.15.34  | 1         | 0.43%   |
| 5.14.0   | 1         | 0.43%   |
| 5.12.18  | 1         | 0.43%   |
| 5.1.15   | 1         | 0.43%   |
| 5.1.0    | 1         | 0.43%   |
| 4.19.90  | 1         | 0.43%   |
| 4.19.71  | 1         | 0.43%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.15    | 61        | 26.99%  |
| 5.10    | 51        | 22.57%  |
| 5.4     | 38        | 16.81%  |
| 5.15    | 15        | 6.64%   |
| 5.18    | 12        | 5.31%   |
| 5.3     | 11        | 4.87%   |
| 4.19    | 10        | 4.42%   |
| 6.1     | 9         | 3.98%   |
| 5.7     | 6         | 2.65%   |
| 5.8     | 2         | 0.88%   |
| 5.6     | 2         | 0.88%   |
| 5.5     | 2         | 0.88%   |
| 5.1     | 2         | 0.88%   |
| 6.5     | 1         | 0.44%   |
| 6.3     | 1         | 0.44%   |
| 5.2     | 1         | 0.44%   |
| 5.14    | 1         | 0.44%   |
| 5.12    | 1         | 0.44%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 215       | 97.29%  |
| aarch64 | 5         | 2.26%   |
| mips64  | 1         | 0.45%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Deepin  | 184       | 82.88%  |
| Unknown | 29        | 13.06%  |
| DDE     | 6         | 2.7%    |
| MATE    | 1         | 0.45%   |
| KDE5    | 1         | 0.45%   |
| KDE     | 1         | 0.45%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 212       | 95.93%  |
| Wayland | 6         | 2.71%   |
| Tty     | 3         | 1.36%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 94        | 42.15%  |
| LightDM | 76        | 34.08%  |
| TDM     | 53        | 23.77%  |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 49        | 21.97%  |
| zh_CN   | 40        | 17.94%  |
| Unknown | 39        | 17.49%  |
| pt_BR   | 26        | 11.66%  |
| es_ES   | 22        | 9.87%   |
| de_DE   | 16        | 7.17%   |
| ru_RU   | 10        | 4.48%   |
| it_IT   | 4         | 1.79%   |
| tr_TR   | 3         | 1.35%   |
| pl_PL   | 3         | 1.35%   |
| fr_FR   | 3         | 1.35%   |
| en_GB   | 3         | 1.35%   |
| sv_SE   | 1         | 0.45%   |
| nl_NL   | 1         | 0.45%   |
| lt_LT   | 1         | 0.45%   |
| ja_JP   | 1         | 0.45%   |
| id_ID   | 1         | 0.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 138       | 62.16%  |
| BIOS | 84        | 37.84%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 202       | 91.4%   |
| Unknown | 18        | 8.14%   |
| Overlay | 1         | 0.45%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 112       | 50%     |
| Unknown | 89        | 39.73%  |
| MBR     | 23        | 10.27%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 166       | 74.11%  |
| Yes       | 58        | 25.89%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 163       | 73.09%  |
| Yes       | 60        | 26.91%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Lenovo                     | 39        | 17.65%  |
| Hewlett-Packard            | 28        | 12.67%  |
| ASUSTek Computer           | 24        | 10.86%  |
| Dell                       | 20        | 9.05%   |
| Acer                       | 15        | 6.79%   |
| Gigabyte Technology        | 9         | 4.07%   |
| Samsung Electronics        | 8         | 3.62%   |
| TSINGHUA TONGFANG COMPUTER | 7         | 3.17%   |
| HUAWEI                     | 6         | 2.71%   |
| Sony                       | 5         | 2.26%   |
| Toshiba                    | 4         | 1.81%   |
| MSI                        | 4         | 1.81%   |
| ASRock                     | 4         | 1.81%   |
| Timi                       | 3         | 1.36%   |
| Positivo                   | 3         | 1.36%   |
| Intel                      | 3         | 1.36%   |
| Unknown                    | 3         | 1.36%   |
| Semp Toshiba               | 2         | 0.9%    |
| Google                     | 2         | 0.9%    |
| ECS                        | 2         | 0.9%    |
| Chuwi                      | 2         | 0.9%    |
| Apple                      | 2         | 0.9%    |
| UNOWHY                     | 1         | 0.45%   |
| THTF                       | 1         | 0.45%   |
| Standard                   | 1         | 0.45%   |
| Soyo                       | 1         | 0.45%   |
| Rockchip Electronics       | 1         | 0.45%   |
| Phytium                    | 1         | 0.45%   |
| OEM                        | 1         | 0.45%   |
| Microtech                  | 1         | 0.45%   |
| Microsoft                  | 1         | 0.45%   |
| Medion                     | 1         | 0.45%   |
| Loongson                   | 1         | 0.45%   |
| Koloe                      | 1         | 0.45%   |
| itel Mobile Limited        | 1         | 0.45%   |
| Infinix                    | 1         | 0.45%   |
| Huanan                     | 1         | 0.45%   |
| HONOR                      | 1         | 0.45%   |
| Hometech                   | 1         | 0.45%   |
| HANWEI                     | 1         | 0.45%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                              | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| TSINGHUA TONGFANG COMPUTER E500                   | 7         | 3.17%   |
| Unknown                                           | 5         | 2.26%   |
| Semp Toshiba STI                                  | 2         | 0.9%    |
| Samsung 340XAA/350XAA/550XAA                      | 2         | 0.9%    |
| Lenovo IdeaPad 120S-11IAP 81A4                    | 2         | 0.9%    |
| HP Pavilion Notebook                              | 2         | 0.9%    |
| HP Pavilion 15                                    | 2         | 0.9%    |
| HP ENVY 15                                        | 2         | 0.9%    |
| ECS H81H3-M4                                      | 2         | 0.9%    |
| ASUS All Series                                   | 2         | 0.9%    |
| Acer Nitro AN515-54                               | 2         | 0.9%    |
| UNOWHY Y13G012S4EI                                | 1         | 0.45%   |
| Toshiba Satellite L75-C                           | 1         | 0.45%   |
| Toshiba Satellite E55t-A                          | 1         | 0.45%   |
| Toshiba Satellite C850D-11K                       | 1         | 0.45%   |
| Toshiba Satellite C850-1H6                        | 1         | 0.45%   |
| Timi TM1701                                       | 1         | 0.45%   |
| Timi RedmiBook Air 13                             | 1         | 0.45%   |
| Timi Redmi G 2022                                 | 1         | 0.45%   |
| THTF ChaoXiangQ620-T1                             | 1         | 0.45%   |
| Standard MB45II/MB45IN                            | 1         | 0.45%   |
| Soyo SY-Thin Mini H110                            | 1         | 0.45%   |
| Sony VPCYB25AB                                    | 1         | 0.45%   |
| Sony VGN-NS140D                                   | 1         | 0.45%   |
| Sony VGN-AW11Z_B                                  | 1         | 0.45%   |
| Sony SVF14A190X                                   | 1         | 0.45%   |
| Sony SVE14135CXP                                  | 1         | 0.45%   |
| Samsung P500A2D                                   | 1         | 0.45%   |
| Samsung 800G5M/800G5W                             | 1         | 0.45%   |
| Samsung 550P5C/550P7C                             | 1         | 0.45%   |
| Samsung 500R4K/500R5H/5400RK/501R5H/5500RH/500R5S | 1         | 0.45%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA        | 1         | 0.45%   |
| Samsung 270E5J/2570EJ                             | 1         | 0.45%   |
| Rockchip RK3588                                   | 1         | 0.45%   |
| Positivo POS-PQ45AU                               | 1         | 0.45%   |
| Positivo POS-EINM70CS                             | 1         | 0.45%   |
| Positivo C14CU51                                  | 1         | 0.45%   |
| Phytium D2000                                     | 1         | 0.45%   |
| OEM ZXE CRB                                       | 1         | 0.45%   |
| MSI MS-7C83                                       | 1         | 0.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                            | Computers | Percent |
|---------------------------------|-----------|---------|
| Dell Inspiron                   | 11        | 4.98%   |
| Lenovo ThinkPad                 | 10        | 4.52%   |
| Lenovo IdeaPad                  | 9         | 4.07%   |
| Acer Aspire                     | 8         | 3.62%   |
| TSINGHUA TONGFANG COMPUTER E500 | 7         | 3.17%   |
| HP EliteBook                    | 6         | 2.71%   |
| HP Pavilion                     | 5         | 2.26%   |
| HP Laptop                       | 5         | 2.26%   |
| Unknown                         | 5         | 2.26%   |
| Toshiba Satellite               | 4         | 1.81%   |
| Lenovo Legion                   | 4         | 1.81%   |
| Acer Nitro                      | 4         | 1.81%   |
| Lenovo ThinkBook                | 3         | 1.36%   |
| HP ENVY                         | 3         | 1.36%   |
| Dell OptiPlex                   | 3         | 1.36%   |
| ASUS PRIME                      | 3         | 1.36%   |
| Semp Toshiba STI                | 2         | 0.9%    |
| Samsung 340XAA                  | 2         | 0.9%    |
| Lenovo ZHAOYANG                 | 2         | 0.9%    |
| Lenovo Yoga                     | 2         | 0.9%    |
| Lenovo ThinkCentre              | 2         | 0.9%    |
| ECS H81H3-M4                    | 2         | 0.9%    |
| Dell Vostro                     | 2         | 0.9%    |
| Dell Latitude                   | 2         | 0.9%    |
| ASUS ROG                        | 2         | 0.9%    |
| ASUS All                        | 2         | 0.9%    |
| Acer Swift                      | 2         | 0.9%    |
| UNOWHY Y13G012S4EI              | 1         | 0.45%   |
| Timi TM1701                     | 1         | 0.45%   |
| Timi RedmiBook                  | 1         | 0.45%   |
| Timi Redmi                      | 1         | 0.45%   |
| THTF ChaoXiangQ620-T1           | 1         | 0.45%   |
| Standard MB45II                 | 1         | 0.45%   |
| Soyo SY-Thin                    | 1         | 0.45%   |
| Sony VPCYB25AB                  | 1         | 0.45%   |
| Sony VGN-NS140D                 | 1         | 0.45%   |
| Sony VGN-AW11Z                  | 1         | 0.45%   |
| Sony SVF14A190X                 | 1         | 0.45%   |
| Sony SVE14135CXP                | 1         | 0.45%   |
| Samsung P500A2D                 | 1         | 0.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 25        | 11.31%  |
| 2017    | 21        | 9.5%    |
| 2018    | 20        | 9.05%   |
| 2019    | 18        | 8.14%   |
| 2013    | 18        | 8.14%   |
| 2012    | 18        | 8.14%   |
| 2020    | 17        | 7.69%   |
| 2014    | 14        | 6.33%   |
| 2011    | 13        | 5.88%   |
| 2016    | 11        | 4.98%   |
| 2015    | 11        | 4.98%   |
| 2022    | 10        | 4.52%   |
| 2010    | 10        | 4.52%   |
| 2009    | 8         | 3.62%   |
| 2008    | 3         | 1.36%   |
| 2023    | 2         | 0.9%    |
| Unknown | 2         | 0.9%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 137       | 61.99%  |
| Desktop        | 65        | 29.41%  |
| Tablet         | 6         | 2.71%   |
| System on chip | 4         | 1.81%   |
| Convertible    | 3         | 1.36%   |
| All in one     | 3         | 1.36%   |
| Mini pc        | 2         | 0.9%    |
| Server         | 1         | 0.45%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 210       | 95.02%  |
| Enabled  | 11        | 4.98%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 219       | 99.1%   |
| Yes  | 2         | 0.9%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 66        | 29.86%  |
| 8.01-16.0   | 51        | 23.08%  |
| 16.01-24.0  | 47        | 21.27%  |
| 3.01-4.0    | 39        | 17.65%  |
| 32.01-64.0  | 9         | 4.07%   |
| 1.01-2.0    | 5         | 2.26%   |
| 64.01-256.0 | 2         | 0.9%    |
| 24.01-32.0  | 1         | 0.45%   |
| 2.01-3.0    | 1         | 0.45%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 69        | 29.74%  |
| 2.01-3.0  | 63        | 27.16%  |
| 4.01-8.0  | 40        | 17.24%  |
| 3.01-4.0  | 38        | 16.38%  |
| 0.51-1.0  | 15        | 6.47%   |
| 8.01-16.0 | 6         | 2.59%   |
| 0.01-0.5  | 1         | 0.43%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 144       | 64.29%  |
| 2      | 64        | 28.57%  |
| 4      | 8         | 3.57%   |
| 3      | 7         | 3.13%   |
| 5      | 1         | 0.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 153       | 68.61%  |
| Yes       | 70        | 31.39%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 171       | 77.38%  |
| No        | 50        | 22.62%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 171       | 77.38%  |
| No        | 50        | 22.62%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 145       | 65.61%  |
| No        | 76        | 34.39%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country               | Computers | Percent |
|-----------------------|-----------|---------|
| Brazil                | 47        | 21.17%  |
| China                 | 43        | 19.37%  |
| Germany               | 16        | 7.21%   |
| USA                   | 15        | 6.76%   |
| Russia                | 9         | 4.05%   |
| Spain                 | 7         | 3.15%   |
| Turkey                | 5         | 2.25%   |
| Indonesia             | 5         | 2.25%   |
| Poland                | 4         | 1.8%    |
| Panama                | 4         | 1.8%    |
| Italy                 | 4         | 1.8%    |
| India                 | 4         | 1.8%    |
| Colombia              | 4         | 1.8%    |
| Chile                 | 4         | 1.8%    |
| Mexico                | 3         | 1.35%   |
| Japan                 | 3         | 1.35%   |
| Austria               | 3         | 1.35%   |
| Argentina             | 3         | 1.35%   |
| UK                    | 2         | 0.9%    |
| Kenya                 | 2         | 0.9%    |
| Canada                | 2         | 0.9%    |
| Bulgaria              | 2         | 0.9%    |
| Bangladesh            | 2         | 0.9%    |
| Vietnam               | 1         | 0.45%   |
| Venezuela             | 1         | 0.45%   |
| Ukraine               | 1         | 0.45%   |
| Tunisia               | 1         | 0.45%   |
| Sweden                | 1         | 0.45%   |
| South Africa          | 1         | 0.45%   |
| Singapore             | 1         | 0.45%   |
| Serbia                | 1         | 0.45%   |
| Sao Tome and Principe | 1         | 0.45%   |
| Romania               | 1         | 0.45%   |
| Portugal              | 1         | 0.45%   |
| Pakistan              | 1         | 0.45%   |
| New Zealand           | 1         | 0.45%   |
| Netherlands           | 1         | 0.45%   |
| Namibia               | 1         | 0.45%   |
| Lithuania             | 1         | 0.45%   |
| Lebanon               | 1         | 0.45%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City            | Computers | Percent |
|-----------------|-----------|---------|
| Beijing         | 9         | 4.02%   |
| Wuhan           | 8         | 3.57%   |
| Sao Paulo       | 5         | 2.23%   |
| Shanghai        | 4         | 1.79%   |
| Guangzhou       | 4         | 1.79%   |
| David           | 4         | 1.79%   |
| Nanjing         | 3         | 1.34%   |
| Curitiba        | 3         | 1.34%   |
| Uberlândia     | 2         | 0.89%   |
| Surabaya        | 2         | 0.89%   |
| San Francisco   | 2         | 0.89%   |
| Petrópolis     | 2         | 0.89%   |
| Moscow          | 2         | 0.89%   |
| Londrina        | 2         | 0.89%   |
| Innsbruck       | 2         | 0.89%   |
| Getxo           | 2         | 0.89%   |
| Dhaka           | 2         | 0.89%   |
| Contagem        | 2         | 0.89%   |
| Brasília       | 2         | 0.89%   |
| Bogotá         | 2         | 0.89%   |
| Atlanta         | 2         | 0.89%   |
| Zaragoza        | 1         | 0.45%   |
| Yozgat          | 1         | 0.45%   |
| Yogyakarta      | 1         | 0.45%   |
| Yekaterinburg   | 1         | 0.45%   |
| Xuhui           | 1         | 0.45%   |
| Windhoek        | 1         | 0.45%   |
| West Jordan     | 1         | 0.45%   |
| Waynesville     | 1         | 0.45%   |
| Wanchai         | 1         | 0.45%   |
| Voronezh        | 1         | 0.45%   |
| Voluntari       | 1         | 0.45%   |
| Villa Ballester | 1         | 0.45%   |
| Vigo            | 1         | 0.45%   |
| Ufa             | 1         | 0.45%   |
| Tychy           | 1         | 0.45%   |
| Tomsk           | 1         | 0.45%   |
| Toluca          | 1         | 0.45%   |
| Tokyo           | 1         | 0.45%   |
| Tianjin         | 1         | 0.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 50        | 63     | 16.03%  |
| Seagate                        | 43        | 49     | 13.78%  |
| Samsung Electronics            | 28        | 31     | 8.97%   |
| Toshiba                        | 21        | 23     | 6.73%   |
| SanDisk                        | 19        | 23     | 6.09%   |
| Unknown                        | 18        | 19     | 5.77%   |
| Kingston                       | 18        | 24     | 5.77%   |
| SK hynix                       | 10        | 11     | 3.21%   |
| Hitachi                        | 9         | 9      | 2.88%   |
| Crucial                        | 8         | 9      | 2.56%   |
| China                          | 7         | 7      | 2.24%   |
| Micron Technology              | 6         | 8      | 1.92%   |
| Intel                          | 6         | 7      | 1.92%   |
| HGST                           | 6         | 6      | 1.92%   |
| A-DATA Technology              | 5         | 6      | 1.6%    |
| SPCC                           | 4         | 5      | 1.28%   |
| Silicon Motion                 | 4         | 4      | 1.28%   |
| Phison                         | 4         | 4      | 1.28%   |
| FORESEE                        | 4         | 4      | 1.28%   |
| LITEON                         | 3         | 3      | 0.96%   |
| Vaseky                         | 2         | 2      | 0.64%   |
| Maxtor                         | 2         | 4      | 0.64%   |
| KIOXIA                         | 2         | 2      | 0.64%   |
| JMicron Technology             | 2         | 2      | 0.64%   |
| Intenso                        | 2         | 3      | 0.64%   |
| Hewlett-Packard                | 2         | 3      | 0.64%   |
| V-GeN                          | 1         | 1      | 0.32%   |
| Transcend                      | 1         | 1      | 0.32%   |
| Solid State Storage Technology | 1         | 1      | 0.32%   |
| Realtek Semiconductor          | 1         | 1      | 0.32%   |
| Phytium                        | 1         | 1      | 0.32%   |
| Patriot                        | 1         | 1      | 0.32%   |
| OEM                            | 1         | 1      | 0.32%   |
| OCZ                            | 1         | 1      | 0.32%   |
| Netac                          | 1         | 1      | 0.32%   |
| Mushkin                        | 1         | 1      | 0.32%   |
| Microtech                      | 1         | 1      | 0.32%   |
| Maxtor 6                       | 1         | 1      | 0.32%   |
| MAXIO Technology (Hangzhou)    | 1         | 1      | 0.32%   |
| LaCie                          | 1         | 2      | 0.32%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 6         | 1.84%   |
| Kingston SA400S37240G 240GB SSD      | 6         | 1.84%   |
| Toshiba MQ01ABF050 500GB             | 5         | 1.53%   |
| Seagate ST1000DM010-2EP102 1TB       | 4         | 1.23%   |
| Crucial CT240BX500SSD1 240GB         | 4         | 1.23%   |
| WDC WD5000LPCX-24VHAT0 500GB         | 3         | 0.92%   |
| Unknown MMC Card                     | 3         | 0.92%   |
| Toshiba MQ01ABD100 1TB               | 3         | 0.92%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 3         | 0.92%   |
| Samsung SSD 850 EVO 500GB            | 3         | 0.92%   |
| Phison ESO256GMFCH-E3C-2 256GB       | 3         | 0.92%   |
| WDC WD5000AAKX-003CA0 500GB          | 2         | 0.61%   |
| WDC WD10EZEX-22MFCA0 1TB             | 2         | 0.61%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB | 2         | 0.61%   |
| Toshiba DT01ACA200 2TB               | 2         | 0.61%   |
| SPCC Solid State Disk 512GB          | 2         | 0.61%   |
| Seagate ST9320325AS 320GB            | 2         | 0.61%   |
| Seagate ST2000LM007-1R8174 2TB       | 2         | 0.61%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 0.61%   |
| Seagate ST1000DM003-1SB102 1TB       | 2         | 0.61%   |
| SanDisk SSD PLUS 240GB               | 2         | 0.61%   |
| SanDisk SDSSDH3512G 512GB            | 2         | 0.61%   |
| SanDisk SDSSDA240G 240GB             | 2         | 0.61%   |
| SanDisk SDSSDA120G 120GB             | 2         | 0.61%   |
| SanDisk DF4064  64GB                 | 2         | 0.61%   |
| Samsung MZVLW256HEHP-000H1 256GB     | 2         | 0.61%   |
| Kingston SV300S37A120G 120GB SSD     | 2         | 0.61%   |
| Kingston SA400S37480G 480GB SSD      | 2         | 0.61%   |
| JMicron Generic 256GB                | 2         | 0.61%   |
| HGST HTS545050A7E680 500GB           | 2         | 0.61%   |
| FORESEE P900F256GBH                  | 2         | 0.61%   |
| WDC WDS500G2B0C-00PXH0 500GB         | 1         | 0.31%   |
| WDC WDS500G2B0B-00YS70 500GB SSD     | 1         | 0.31%   |
| WDC WDS480G2G0B-00EPW0 480GB SSD     | 1         | 0.31%   |
| WDC WDS250G1B0C-00S6U0 250GB         | 1         | 0.31%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 0.31%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 1         | 0.31%   |
| WDC WDS120G1G0A-00SS50 120GB SSD     | 1         | 0.31%   |
| WDC WDS100T2G0A-00JH30 1TB SSD       | 1         | 0.31%   |
| WDC WD80 0BEVE-11UYT0 80GB           | 1         | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 42        | 48     | 33.6%   |
| WDC                 | 39        | 45     | 31.2%   |
| Toshiba             | 19        | 21     | 15.2%   |
| Hitachi             | 9         | 9      | 7.2%    |
| HGST                | 6         | 6      | 4.8%    |
| Samsung Electronics | 3         | 3      | 2.4%    |
| Maxtor              | 2         | 4      | 1.6%    |
| Unknown             | 1         | 2      | 0.8%    |
| OEM                 | 1         | 1      | 0.8%    |
| Maxtor 6            | 1         | 1      | 0.8%    |
| Hewlett-Packard     | 1         | 2      | 0.8%    |
| Fujitsu             | 1         | 2      | 0.8%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 17        | 21     | 17.89%  |
| Kingston            | 15        | 21     | 15.79%  |
| Samsung Electronics | 12        | 14     | 12.63%  |
| WDC                 | 7         | 10     | 7.37%   |
| China               | 7         | 7      | 7.37%   |
| Crucial             | 6         | 7      | 6.32%   |
| SPCC                | 4         | 5      | 4.21%   |
| A-DATA Technology   | 3         | 4      | 3.16%   |
| Vaseky              | 2         | 2      | 2.11%   |
| SK hynix            | 2         | 2      | 2.11%   |
| Micron Technology   | 2         | 3      | 2.11%   |
| LITEON              | 2         | 2      | 2.11%   |
| Intenso             | 2         | 3      | 2.11%   |
| Intel               | 2         | 3      | 2.11%   |
| V-GeN               | 1         | 1      | 1.05%   |
| Unknown             | 1         | 1      | 1.05%   |
| Transcend           | 1         | 1      | 1.05%   |
| OCZ                 | 1         | 1      | 1.05%   |
| Netac               | 1         | 1      | 1.05%   |
| Microtech           | 1         | 1      | 1.05%   |
| KingSpec            | 1         | 1      | 1.05%   |
| KingDian            | 1         | 1      | 1.05%   |
| KINGBANK            | 1         | 1      | 1.05%   |
| Hewlett-Packard     | 1         | 1      | 1.05%   |
| G521N               | 1         | 1      | 1.05%   |
| Apacer              | 1         | 3      | 1.05%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 111       | 144    | 38.54%  |
| SSD     | 85        | 118    | 29.51%  |
| NVMe    | 73        | 80     | 25.35%  |
| MMC     | 17        | 18     | 5.9%    |
| Unknown | 2         | 3      | 0.69%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 162       | 253    | 62.31%  |
| NVMe | 71        | 78     | 27.31%  |
| MMC  | 17        | 18     | 6.54%   |
| SAS  | 10        | 14     | 3.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 115       | 168    | 59.28%  |
| 0.51-1.0   | 68        | 80     | 35.05%  |
| 1.01-2.0   | 9         | 12     | 4.64%   |
| 3.01-4.0   | 1         | 1      | 0.52%   |
| 4.01-10.0  | 1         | 1      | 0.52%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 63        | 27.88%  |
| 101-250        | 54        | 23.89%  |
| 501-1000       | 44        | 19.47%  |
| 1001-2000      | 29        | 12.83%  |
| 51-100         | 12        | 5.31%   |
| More than 3000 | 8         | 3.54%   |
| 21-50          | 5         | 2.21%   |
| 2001-3000      | 5         | 2.21%   |
| Unknown        | 4         | 1.77%   |
| 1-20           | 2         | 0.88%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 50        | 21.83%  |
| 21-50          | 48        | 20.96%  |
| 101-250        | 43        | 18.78%  |
| 51-100         | 26        | 11.35%  |
| 251-500        | 25        | 10.92%  |
| 501-1000       | 21        | 9.17%   |
| 1001-2000      | 8         | 3.49%   |
| Unknown        | 4         | 1.75%   |
| 2001-3000      | 3         | 1.31%   |
| More than 3000 | 1         | 0.44%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                         | Computers | Drives | Percent |
|-----------------------------------------------|-----------|--------|---------|
| Seagate ST9320325AS 320GB                     | 2         | 2      | 8.7%    |
| WDC WD5000LPLX-66ZNTT1 500GB                  | 1         | 1      | 4.35%   |
| WDC WD10JPVX-22JC3T0 1TB                      | 1         | 1      | 4.35%   |
| WDC WD10EARS-00Y5B1 1TB                       | 1         | 1      | 4.35%   |
| Toshiba MQ01ABD100 1TB                        | 1         | 1      | 4.35%   |
| Toshiba MQ01ABD032 320GB                      | 1         | 1      | 4.35%   |
| Toshiba MK8052GSX 80GB                        | 1         | 1      | 4.35%   |
| SK hynix PC711 HFS001TDE9X073N 1024GB         | 1         | 1      | 4.35%   |
| SK hynix BC511 HFM256GDJTNI-82A0A 256GB       | 1         | 1      | 4.35%   |
| Seagate ST3750528AS 752GB                     | 1         | 1      | 4.35%   |
| Seagate ST2000LM003 HN-M201RAD 2TB            | 1         | 1      | 4.35%   |
| Seagate ST1000LM049-2GH172 1TB                | 1         | 1      | 4.35%   |
| Seagate ST1000DL002-9TT153 1TB                | 1         | 1      | 4.35%   |
| Samsung Electronics HM250HI 250GB             | 1         | 1      | 4.35%   |
| Samsung Electronics HD502HJ 500GB             | 1         | 1      | 4.35%   |
| Samsung Electronics HD250HJ 250GB             | 1         | 1      | 4.35%   |
| OCZ VERTEX4 256GB SSD                         | 1         | 1      | 4.35%   |
| Micron Technology MTFDDAT128MAM-1J2 128GB SSD | 1         | 2      | 4.35%   |
| Intenso lntenso SSD Sata III 480GB            | 1         | 1      | 4.35%   |
| Hitachi HTS543225L9A300 250GB                 | 1         | 1      | 4.35%   |
| Hitachi HDP725050GLA360 500GB                 | 1         | 1      | 4.35%   |
| G521N SSD 256GB                               | 1         | 1      | 4.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 6      | 22.73%  |
| WDC                 | 3         | 3      | 13.64%  |
| Toshiba             | 3         | 3      | 13.64%  |
| Samsung Electronics | 3         | 3      | 13.64%  |
| SK hynix            | 2         | 2      | 9.09%   |
| Hitachi             | 2         | 2      | 9.09%   |
| OCZ                 | 1         | 1      | 4.55%   |
| Micron Technology   | 1         | 2      | 4.55%   |
| Intenso             | 1         | 1      | 4.55%   |
| G521N               | 1         | 1      | 4.55%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 6      | 31.25%  |
| WDC                 | 3         | 3      | 18.75%  |
| Toshiba             | 3         | 3      | 18.75%  |
| Samsung Electronics | 3         | 3      | 18.75%  |
| Hitachi             | 2         | 2      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 16        | 17     | 72.73%  |
| SSD  | 4         | 5      | 18.18%  |
| NVMe | 2         | 2      | 9.09%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                       | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Toshiba MK5065GSXN 500GB    | 1         | 1      | 50%     |
| Hitachi HUA722010CLA330 1TB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 50%     |
| Hitachi | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 111       | 182    | 45.31%  |
| Works    | 110       | 155    | 44.9%   |
| Malfunc  | 22        | 24     | 8.98%   |
| Failed   | 2         | 2      | 0.82%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 153       | 57.74%  |
| AMD                            | 22        | 8.3%    |
| Samsung Electronics            | 14        | 5.28%   |
| SK hynix                       | 8         | 3.02%   |
| SanDisk                        | 8         | 3.02%   |
| ASMedia Technology             | 7         | 2.64%   |
| Silicon Motion                 | 6         | 2.26%   |
| Marvell Technology Group       | 6         | 2.26%   |
| Phison Electronics             | 5         | 1.89%   |
| Micron Technology              | 4         | 1.51%   |
| Kingston Technology Company    | 4         | 1.51%   |
| Shenzhen Longsys Electronics   | 3         | 1.13%   |
| MAXIO Technology (Hangzhou)    | 3         | 1.13%   |
| KIOXIA                         | 3         | 1.13%   |
| Zhaoxin                        | 2         | 0.75%   |
| Realtek Semiconductor          | 2         | 0.75%   |
| Nvidia                         | 2         | 0.75%   |
| Micron/Crucial Technology      | 2         | 0.75%   |
| JMicron Technology             | 2         | 0.75%   |
| Beijing Starblaze Technology   | 2         | 0.75%   |
| Toshiba America Info Systems   | 1         | 0.38%   |
| Solid State Storage Technology | 1         | 0.38%   |
| Loongson Technology            | 1         | 0.38%   |
| Lite-On Technology             | 1         | 0.38%   |
| Apple                          | 1         | 0.38%   |
| ADATA Technology               | 1         | 0.38%   |
| Unknown                        | 1         | 0.38%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 16        | 5.59%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 15        | 5.24%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 13        | 4.55%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 11        | 3.85%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 10        | 3.5%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 9         | 3.15%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 7         | 2.45%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 7         | 2.45%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 7         | 2.45%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 7         | 2.45%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 6         | 2.1%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 6         | 2.1%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 6         | 2.1%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 6         | 2.1%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 6         | 2.1%    |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 5         | 1.75%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 5         | 1.75%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4         | 1.4%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 1.4%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 1.4%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 4         | 1.4%    |
| SK hynix BC511 NVMe SSD                                                        | 3         | 1.05%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 1.05%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 3         | 1.05%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller               | 3         | 1.05%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 3         | 1.05%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 3         | 1.05%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 3         | 1.05%   |
| Zhaoxin ZX-100/ZX-200/KX-6000/KX-6000G/KH-40000 StorX AHCI Controller          | 2         | 0.7%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 2         | 0.7%    |
| SK hynix BC501 NVMe Solid State Drive                                          | 2         | 0.7%    |
| Shenzhen Longsys FORESEE P900 BGA NVMe SSD (DRAM-less)                         | 2         | 0.7%    |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 2         | 0.7%    |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 2         | 0.7%    |
| Micron 2200S NVMe SSD [Cassandra]                                              | 2         | 0.7%    |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                   | 2         | 0.7%    |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                          | 2         | 0.7%    |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 2         | 0.7%    |
| Kingston Company A1000/U-SNS8154P3 x2 NVMe SSD                                 | 2         | 0.7%    |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 165       | 62.98%  |
| NVMe | 70        | 26.72%  |
| IDE  | 18        | 6.87%   |
| RAID | 9         | 3.44%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 176       | 79.64%  |
| AMD          | 37        | 16.74%  |
| Phytium      | 3         | 1.36%   |
| CentaurHauls | 2         | 0.9%    |
| ARM          | 2         | 0.9%    |
| Unknown      | 1         | 0.45%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-10700 CPU @ 2.90GHz             | 6         | 2.71%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 2.26%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 4         | 1.81%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 4         | 1.81%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 1.81%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 4         | 1.81%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 1.36%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 1.36%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 3         | 1.36%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 1.36%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 1.36%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 2         | 0.9%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 0.9%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 0.9%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.9%    |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 0.9%    |
| Intel Core i7-4790 CPU @ 3.60GHz              | 2         | 0.9%    |
| Intel Core i7-4510U CPU @ 2.00GHz             | 2         | 0.9%    |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 0.9%    |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 2         | 0.9%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 0.9%    |
| Intel Core i5-8259U CPU @ 2.30GHz             | 2         | 0.9%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 0.9%    |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 0.9%    |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 0.9%    |
| Intel Core i3-6100 CPU @ 3.70GHz              | 2         | 0.9%    |
| Intel Core i3-4030U CPU @ 1.90GHz             | 2         | 0.9%    |
| Intel Core i3-4005U CPU @ 1.70GHz             | 2         | 0.9%    |
| Intel Core i3-3220 CPU @ 3.30GHz              | 2         | 0.9%    |
| Intel Core i3-10100 CPU @ 3.60GHz             | 2         | 0.9%    |
| Intel Celeron N4120 CPU @ 1.10GHz             | 2         | 0.9%    |
| Intel Celeron CPU N3350 @ 1.10GHz             | 2         | 0.9%    |
| Intel Celeron CPU 1007U @ 1.50GHz             | 2         | 0.9%    |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 2         | 0.9%    |
| Intel Atom CPU Z3735F @ 1.33GHz               | 2         | 0.9%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 0.9%    |
| ARM Processor                                 | 2         | 0.9%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 0.9%    |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 0.9%    |
| AMD Ryzen 5 4600U with Radeon Graphics        | 2         | 0.9%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 51        | 23.08%  |
| Intel Core i5           | 48        | 21.72%  |
| Other                   | 21        | 9.5%    |
| Intel Core i3           | 21        | 9.5%    |
| Intel Celeron           | 14        | 6.33%   |
| AMD Ryzen 5             | 10        | 4.52%   |
| Intel Core 2 Duo        | 9         | 4.07%   |
| AMD Ryzen 7             | 8         | 3.62%   |
| Intel Atom              | 6         | 2.71%   |
| Intel Pentium Dual-Core | 4         | 1.81%   |
| AMD Ryzen 3             | 4         | 1.81%   |
| AMD FX                  | 4         | 1.81%   |
| Intel Xeon              | 3         | 1.36%   |
| Intel Pentium           | 3         | 1.36%   |
| Intel Pentium Silver    | 2         | 0.9%    |
| Intel Core i9           | 2         | 0.9%    |
| AMD A10                 | 2         | 0.9%    |
| Intel Core m3           | 1         | 0.45%   |
| Intel Core M            | 1         | 0.45%   |
| Intel Celeron Dual-Core | 1         | 0.45%   |
| AMD Ryzen 7 PRO         | 1         | 0.45%   |
| AMD Ryzen 5 PRO         | 1         | 0.45%   |
| AMD E1                  | 1         | 0.45%   |
| AMD E                   | 1         | 0.45%   |
| AMD C-60                | 1         | 0.45%   |
| AMD Athlon              | 1         | 0.45%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 95        | 42.99%  |
| 4      | 85        | 38.46%  |
| 8      | 17        | 7.69%   |
| 6      | 16        | 7.24%   |
| 10     | 3         | 1.36%   |
| 12     | 2         | 0.9%    |
| 24     | 1         | 0.45%   |
| 3      | 1         | 0.45%   |
| 1      | 1         | 0.45%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 219       | 99.1%   |
| 3      | 2         | 0.9%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 154       | 69.68%  |
| 1      | 67        | 30.32%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 204       | 92.31%  |
| Unknown        | 17        | 7.69%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 54        | 24.11%  |
| 0x306a9    | 20        | 8.93%   |
| 0x806ec    | 11        | 4.91%   |
| 0x806e9    | 9         | 4.02%   |
| 0x40651    | 9         | 4.02%   |
| 0x306c3    | 8         | 3.57%   |
| 0x206a7    | 8         | 3.57%   |
| 0x1067a    | 8         | 3.57%   |
| 0x306d4    | 7         | 3.13%   |
| 0x406e3    | 6         | 2.68%   |
| 0xa0655    | 5         | 2.23%   |
| 0x906ea    | 5         | 2.23%   |
| 0x906e9    | 5         | 2.23%   |
| 0x806ea    | 4         | 1.79%   |
| 0x706a8    | 4         | 1.79%   |
| 0x906a3    | 3         | 1.34%   |
| 0x806c1    | 3         | 1.34%   |
| 0x406c4    | 3         | 1.34%   |
| 0x08600106 | 3         | 1.34%   |
| 0x08108109 | 3         | 1.34%   |
| 0x506e3    | 2         | 0.89%   |
| 0x30678    | 2         | 0.89%   |
| 0x20655    | 2         | 0.89%   |
| 0x0a50000d | 2         | 0.89%   |
| 0x08600104 | 2         | 0.89%   |
| 0x08200103 | 2         | 0.89%   |
| 0x08108102 | 2         | 0.89%   |
| 0x0500010d | 2         | 0.89%   |
| 0xb06a3    | 1         | 0.45%   |
| 0xb0671    | 1         | 0.45%   |
| 0xa0653    | 1         | 0.45%   |
| 0xa0652    | 1         | 0.45%   |
| 0x906eb    | 1         | 0.45%   |
| 0x806d1    | 1         | 0.45%   |
| 0x806c2    | 1         | 0.45%   |
| 0x706a1    | 1         | 0.45%   |
| 0x6fd      | 1         | 0.45%   |
| 0x406c3    | 1         | 0.45%   |
| 0x306f2    | 1         | 0.45%   |
| 0x206c2    | 1         | 0.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 42        | 19%     |
| IvyBridge        | 25        | 11.31%  |
| Haswell          | 20        | 9.05%   |
| Penryn           | 14        | 6.33%   |
| Unknown          | 12        | 5.43%   |
| Skylake          | 11        | 4.98%   |
| SandyBridge      | 10        | 4.52%   |
| CometLake        | 10        | 4.52%   |
| Broadwell        | 10        | 4.52%   |
| Zen 2            | 9         | 4.07%   |
| Silvermont       | 9         | 4.07%   |
| Goldmont plus    | 7         | 3.17%   |
| Zen+             | 5         | 2.26%   |
| Zen              | 5         | 2.26%   |
| Alderlake Hybrid | 5         | 2.26%   |
| Zen 3            | 4         | 1.81%   |
| Westmere         | 4         | 1.81%   |
| TigerLake        | 4         | 1.81%   |
| Bobcat           | 3         | 1.36%   |
| Piledriver       | 2         | 0.9%    |
| Goldmont         | 2         | 0.9%    |
| Excavator        | 2         | 0.9%    |
| Bulldozer        | 2         | 0.9%    |
| Nehalem          | 1         | 0.45%   |
| Jaguar           | 1         | 0.45%   |
| Icelake          | 1         | 0.45%   |
| Core             | 1         | 0.45%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 144       | 52.55%  |
| Nvidia              | 72        | 26.28%  |
| AMD                 | 54        | 19.71%  |
| Zhaoxin             | 2         | 0.73%   |
| Phytium Technology  | 1         | 0.36%   |
| Loongson Technology | 1         | 0.36%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 12        | 4.33%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 3.97%   |
| Intel HD Graphics 5500                                                                   | 9         | 3.25%   |
| Intel HD Graphics 620                                                                    | 8         | 2.89%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8         | 2.89%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 2.53%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 7         | 2.53%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 2.53%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 6         | 2.17%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 2.17%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 2.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 2.17%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 6         | 2.17%   |
| Intel UHD Graphics 620                                                                   | 5         | 1.81%   |
| Intel HD Graphics 630                                                                    | 5         | 1.81%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 1.81%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 1.81%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 5         | 1.81%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 1.44%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 1.44%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 1.44%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 1.08%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 3         | 1.08%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3         | 1.08%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.08%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 1.08%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 3         | 1.08%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 3         | 1.08%   |
| Zhaoxin ZX-E C-960 GPU                                                                   | 2         | 0.72%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 0.72%   |
| Nvidia GP108M [GeForce MX250]                                                            | 2         | 0.72%   |
| Nvidia GP108BM [GeForce MX250]                                                           | 2         | 0.72%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.72%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 0.72%   |
| Nvidia GM108M [GeForce MX110]                                                            | 2         | 0.72%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 2         | 0.72%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.72%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 2         | 0.72%   |
| Nvidia GK107M [GeForce GT 650M]                                                          | 2         | 0.72%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 92        | 41.63%  |
| Intel + Nvidia          | 41        | 18.55%  |
| 1 x AMD                 | 41        | 18.55%  |
| 1 x Nvidia              | 28        | 12.67%  |
| Intel + AMD             | 8         | 3.62%   |
| AMD + Nvidia            | 3         | 1.36%   |
| Other                   | 2         | 0.9%    |
| 2 x AMD                 | 2         | 0.9%    |
| 1 x Zhaoxin             | 2         | 0.9%    |
| 1 x Phytium Technology  | 1         | 0.45%   |
| 1 x Loongson Technology | 1         | 0.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 169       | 76.13%  |
| Proprietary | 36        | 16.22%  |
| Unknown     | 17        | 7.66%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 129       | 57.08%  |
| 1.01-2.0   | 45        | 19.91%  |
| 3.01-4.0   | 21        | 9.29%   |
| 0.01-0.5   | 16        | 7.08%   |
| 0.51-1.0   | 8         | 3.54%   |
| 7.01-8.0   | 4         | 1.77%   |
| 5.01-6.0   | 3         | 1.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 31        | 13.78%  |
| AU Optronics            | 31        | 13.78%  |
| BOE                     | 29        | 12.89%  |
| Chimei Innolux          | 21        | 9.33%   |
| LG Display              | 17        | 7.56%   |
| Goldstar                | 12        | 5.33%   |
| Hewlett-Packard         | 8         | 3.56%   |
| ViewSonic               | 6         | 2.67%   |
| Dell                    | 6         | 2.67%   |
| CSO                     | 6         | 2.67%   |
| AOC                     | 5         | 2.22%   |
| Philips                 | 4         | 1.78%   |
| Lenovo                  | 4         | 1.78%   |
| Iiyama                  | 3         | 1.33%   |
| HKC                     | 3         | 1.33%   |
| BenQ                    | 3         | 1.33%   |
| RTK                     | 2         | 0.89%   |
| InfoVision              | 2         | 0.89%   |
| HannStar                | 2         | 0.89%   |
| Chi Mei Optoelectronics | 2         | 0.89%   |
| Apple                   | 2         | 0.89%   |
| Ancor Communications    | 2         | 0.89%   |
| Acer                    | 2         | 0.89%   |
| Xiaomi                  | 1         | 0.44%   |
| Unknown                 | 1         | 0.44%   |
| Toshiba                 | 1         | 0.44%   |
| TMX                     | 1         | 0.44%   |
| TFC                     | 1         | 0.44%   |
| SKY                     | 1         | 0.44%   |
| Sharp                   | 1         | 0.44%   |
| SAC                     | 1         | 0.44%   |
| Positivo                | 1         | 0.44%   |
| PANDA                   | 1         | 0.44%   |
| Packard Bell            | 1         | 0.44%   |
| MSI                     | 1         | 0.44%   |
| LG Philips              | 1         | 0.44%   |
| JDI                     | 1         | 0.44%   |
| InnoLux Display         | 1         | 0.44%   |
| Hisense                 | 1         | 0.44%   |
| HB@                     | 1         | 0.44%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| ViewSonic VA2478-H-2 VSC8335 1920x1080 527x296mm 23.8-inch            | 3         | 1.29%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 3         | 1.29%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 3         | 1.29%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch           | 2         | 0.86%   |
| Goldstar 20EN33 GSM4EE1 1600x900 443x249mm 20.0-inch                  | 2         | 0.86%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 0.86%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch       | 2         | 0.86%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                 | 2         | 0.86%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 2         | 0.86%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch         | 2         | 0.86%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 276x155mm 12.5-inch        | 2         | 0.86%   |
| Xiaomi Mi TV XMD0076 3840x2160 800x450mm 36.1-inch                    | 1         | 0.43%   |
| ViewSonic VX2481-mh VSC3933 1920x1080 527x296mm 23.8-inch             | 1         | 0.43%   |
| ViewSonic VA2431-H-2 VSC3A22 1920x1080 527x296mm 23.8-inch            | 1         | 0.43%   |
| ViewSonic VA2430-H-3 VSC3A3E 1920x1080 527x296mm 23.8-inch            | 1         | 0.43%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 1         | 0.43%   |
| Toshiba TV TSB0108 1360x768 698x393mm 31.5-inch                       | 1         | 0.43%   |
| TMX TL140VDXP04-0 TMX1398 1920x1080 309x174mm 14.0-inch               | 1         | 0.43%   |
| TFC TF2411 TFC0238 1920x1080 527x296mm 23.8-inch                      | 1         | 0.43%   |
| SKY 24X1Q SKY2380 2560x1440 520x290mm 23.4-inch                       | 1         | 0.43%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch               | 1         | 0.43%   |
| Samsung Electronics SyncMaster SAM060B 1920x1080 510x290mm 23.1-inch  | 1         | 0.43%   |
| Samsung Electronics SyncMaster SAM0601 1600x900                       | 1         | 0.43%   |
| Samsung Electronics SyncMaster SAM05FF 1600x900 443x249mm 20.0-inch   | 1         | 0.43%   |
| Samsung Electronics SyncMaster SAM02B6 1920x1200 518x324mm 24.1-inch  | 1         | 0.43%   |
| Samsung Electronics SyncMaster SAM0167 1280x1024 338x270mm 17.0-inch  | 1         | 0.43%   |
| Samsung Electronics SMT24A550 SAM07B5 1920x1080 531x299mm 24.0-inch   | 1         | 0.43%   |
| Samsung Electronics S32B80P SAM71F1 3840x2160 698x393mm 31.5-inch     | 1         | 0.43%   |
| Samsung Electronics S24E360 SAM0C10 1920x1080 520x290mm 23.4-inch     | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SMS23A350H 1920x1080                  | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch  | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SEC384A 1366x768 344x194mm 15.5-inch  | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch  | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch  | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SEC314B 1680x945 409x230mm 18.5-inch  | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SDC864D 1920x1080 293x165mm 13.2-inch | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SDC534B 1600x900 382x215mm 17.3-inch  | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch  | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SDC4A42 1366x768 309x174mm 14.0-inch  | 1         | 0.43%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 97        | 44.7%   |
| 1366x768 (WXGA)    | 54        | 24.88%  |
| 3840x2160 (4K)     | 10        | 4.61%   |
| 1600x900 (HD+)     | 10        | 4.61%   |
| 2560x1440 (QHD)    | 7         | 3.23%   |
| 2560x1600          | 5         | 2.3%    |
| 3000x2000          | 3         | 1.38%   |
| 2880x1800          | 3         | 1.38%   |
| 2160x1440          | 3         | 1.38%   |
| 1440x900 (WXGA+)   | 3         | 1.38%   |
| 3840x1080          | 2         | 0.92%   |
| 2288x1287          | 2         | 0.92%   |
| 1920x540           | 2         | 0.92%   |
| 1920x1200 (WUXGA)  | 2         | 0.92%   |
| 1680x1050 (WSXGA+) | 2         | 0.92%   |
| 1360x768           | 2         | 0.92%   |
| 1280x1024 (SXGA)   | 2         | 0.92%   |
| Unknown            | 2         | 0.92%   |
| 3440x1440          | 1         | 0.46%   |
| 3200x1800 (QHD+)   | 1         | 0.46%   |
| 2736x1824          | 1         | 0.46%   |
| 2160x1350          | 1         | 0.46%   |
| 1680x945           | 1         | 0.46%   |
| 1280x800 (WXGA)    | 1         | 0.46%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 59        | 25.99%  |
| 13      | 33        | 14.54%  |
| 23      | 25        | 11.01%  |
| 14      | 23        | 10.13%  |
| 21      | 11        | 4.85%   |
| 24      | 10        | 4.41%   |
| 27      | 9         | 3.96%   |
| Unknown | 9         | 3.96%   |
| 18      | 6         | 2.64%   |
| 12      | 6         | 2.64%   |
| 17      | 5         | 2.2%    |
| 11      | 4         | 1.76%   |
| 84      | 3         | 1.32%   |
| 32      | 3         | 1.32%   |
| 31      | 3         | 1.32%   |
| 20      | 3         | 1.32%   |
| 19      | 3         | 1.32%   |
| 25      | 2         | 0.88%   |
| 22      | 2         | 0.88%   |
| 16      | 2         | 0.88%   |
| 142     | 1         | 0.44%   |
| 72      | 1         | 0.44%   |
| 65      | 1         | 0.44%   |
| 54      | 1         | 0.44%   |
| 40      | 1         | 0.44%   |
| 10      | 1         | 0.44%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 101       | 45.5%   |
| 501-600        | 44        | 19.82%  |
| 201-300        | 25        | 11.26%  |
| 401-500        | 23        | 10.36%  |
| Unknown        | 9         | 4.05%   |
| 351-400        | 6         | 2.7%    |
| 1501-2000      | 4         | 1.8%    |
| 701-800        | 3         | 1.35%   |
| 601-700        | 3         | 1.35%   |
| 1001-1500      | 2         | 0.9%    |
| More than 2000 | 1         | 0.45%   |
| 801-900        | 1         | 0.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 172       | 83.09%  |
| 16/10   | 18        | 8.7%    |
| 3/2     | 8         | 3.86%   |
| Unknown | 7         | 3.38%   |
| 5/4     | 1         | 0.48%   |
| 1.00    | 1         | 0.48%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 59        | 26.11%  |
| 81-90          | 45        | 19.91%  |
| 201-250        | 39        | 17.26%  |
| 71-80          | 11        | 4.87%   |
| 151-200        | 11        | 4.87%   |
| 301-350        | 9         | 3.98%   |
| Unknown        | 9         | 3.98%   |
| More than 1000 | 7         | 3.1%    |
| 61-70          | 7         | 3.1%    |
| 351-500        | 6         | 2.65%   |
| 251-300        | 6         | 2.65%   |
| 141-150        | 6         | 2.65%   |
| 51-60          | 3         | 1.33%   |
| 121-130        | 3         | 1.33%   |
| 111-120        | 2         | 0.88%   |
| 41-50          | 1         | 0.44%   |
| 131-140        | 1         | 0.44%   |
| 501-1000       | 1         | 0.44%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 69        | 31.22%  |
| 51-100        | 60        | 27.15%  |
| 121-160       | 53        | 23.98%  |
| 161-240       | 18        | 8.14%   |
| Unknown       | 9         | 4.07%   |
| More than 240 | 8         | 3.62%   |
| 1-50          | 4         | 1.81%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 179       | 80.27%  |
| 2     | 34        | 15.25%  |
| 0     | 9         | 4.04%   |
| 3     | 1         | 0.45%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 139       | 43.99%  |
| Intel                           | 85        | 26.9%   |
| Qualcomm Atheros                | 43        | 13.61%  |
| Broadcom                        | 10        | 3.16%   |
| MediaTek                        | 6         | 1.9%    |
| Marvell Technology Group        | 5         | 1.58%   |
| Xiaomi                          | 4         | 1.27%   |
| TP-Link                         | 3         | 0.95%   |
| Broadcom Limited                | 3         | 0.95%   |
| Ralink Technology               | 2         | 0.63%   |
| Ralink                          | 2         | 0.63%   |
| Nvidia                          | 2         | 0.63%   |
| Unknown                         | 1         | 0.32%   |
| Samsung Electronics             | 1         | 0.32%   |
| Qualcomm Atheros Communications | 1         | 0.32%   |
| OPPO Electronics                | 1         | 0.32%   |
| NXP Semiconductors              | 1         | 0.32%   |
| NetGear                         | 1         | 0.32%   |
| Loongson Technology             | 1         | 0.32%   |
| IMC Networks                    | 1         | 0.32%   |
| Huawei Technologies             | 1         | 0.32%   |
| Hewlett-Packard                 | 1         | 0.32%   |
| ASIX Electronics                | 1         | 0.32%   |
| Aquantia                        | 1         | 0.32%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 94        | 25.97%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 21        | 5.8%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 14        | 3.87%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 9         | 2.49%   |
| Intel Wireless 3165                                               | 8         | 2.21%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 7         | 1.93%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 7         | 1.93%   |
| Intel Wi-Fi 6 AX200                                               | 6         | 1.66%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 1.66%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 1.38%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 1.38%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 1.38%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 4         | 1.1%    |
| Intel Wireless 8265 / 8275                                        | 4         | 1.1%    |
| Intel Wi-Fi 6 AX201                                               | 4         | 1.1%    |
| Intel Ethernet Connection (12) I219-V                             | 4         | 1.1%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 1.1%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 1.1%    |
| Realtek RTL8723DE Wireless Network Adapter                        | 3         | 0.83%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 3         | 0.83%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 3         | 0.83%   |
| Intel Wireless 7260                                               | 3         | 0.83%   |
| Intel Wireless 3160                                               | 3         | 0.83%   |
| Intel WiFi Link 5100                                              | 3         | 0.83%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 0.83%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 3         | 0.83%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.55%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 2         | 0.55%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.55%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.55%   |
| Realtek RTL8191SEvA Wireless LAN Controller                       | 2         | 0.55%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)         | 2         | 0.55%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 0.55%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.55%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 2         | 0.55%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 2         | 0.55%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 0.55%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 0.55%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 67        | 38.29%  |
| Realtek Semiconductor           | 43        | 24.57%  |
| Qualcomm Atheros                | 40        | 22.86%  |
| MediaTek                        | 5         | 2.86%   |
| Broadcom                        | 5         | 2.86%   |
| TP-Link                         | 3         | 1.71%   |
| Broadcom Limited                | 3         | 1.71%   |
| Ralink Technology               | 2         | 1.14%   |
| Ralink                          | 2         | 1.14%   |
| Xiaomi                          | 1         | 0.57%   |
| Qualcomm Atheros Communications | 1         | 0.57%   |
| NetGear                         | 1         | 0.57%   |
| Marvell Technology Group        | 1         | 0.57%   |
| IMC Networks                    | 1         | 0.57%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 14        | 7.95%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 9         | 5.11%   |
| Intel Wireless 3165                                            | 8         | 4.55%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 7         | 3.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 7         | 3.98%   |
| Intel Wi-Fi 6 AX200                                            | 6         | 3.41%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 5         | 2.84%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 5         | 2.84%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 4         | 2.27%   |
| Intel Wireless 8265 / 8275                                     | 4         | 2.27%   |
| Intel Wi-Fi 6 AX201                                            | 4         | 2.27%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 2.27%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 4         | 2.27%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 3         | 1.7%    |
| Realtek RTL8188EE Wireless Network Adapter                     | 3         | 1.7%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 3         | 1.7%    |
| Intel Wireless 7260                                            | 3         | 1.7%    |
| Intel Wireless 3160                                            | 3         | 1.7%    |
| Intel WiFi Link 5100                                           | 3         | 1.7%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 3         | 1.7%    |
| Intel Alder Lake-P PCH CNVi WiFi                               | 3         | 1.7%    |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 2         | 1.14%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 1.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.14%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.14%   |
| Realtek RTL8191SEvA Wireless LAN Controller                    | 2         | 1.14%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)      | 2         | 1.14%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 1.14%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 1.14%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 2         | 1.14%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 1.14%   |
| Intel Wireless 7265                                            | 2         | 1.14%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 1.14%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 1.14%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 1.14%   |
| Xiaomi MediaTek MT7601U [MI WiFi]                              | 1         | 0.57%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1         | 0.57%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 1         | 0.57%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 0.57%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 1         | 0.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 124       | 68.13%  |
| Intel                    | 30        | 16.48%  |
| Qualcomm Atheros         | 6         | 3.3%    |
| Broadcom                 | 5         | 2.75%   |
| Marvell Technology Group | 4         | 2.2%    |
| Xiaomi                   | 3         | 1.65%   |
| Nvidia                   | 2         | 1.1%    |
| Samsung Electronics      | 1         | 0.55%   |
| OPPO Electronics         | 1         | 0.55%   |
| MediaTek                 | 1         | 0.55%   |
| Loongson Technology      | 1         | 0.55%   |
| Huawei Technologies      | 1         | 0.55%   |
| Hewlett-Packard          | 1         | 0.55%   |
| ASIX Electronics         | 1         | 0.55%   |
| Aquantia                 | 1         | 0.55%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 94        | 51.09%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 21        | 11.41%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 3.26%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 2.72%   |
| Intel Ethernet Connection (12) I219-V                             | 4         | 2.17%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 1.09%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 1.09%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 1.09%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 1.09%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.09%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 1.09%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 1.09%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 1.09%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 2         | 1.09%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.54%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.54%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.54%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.54%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.54%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.54%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.54%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.54%   |
| OPPO RMX2027                                                      | 1         | 0.54%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.54%   |
| Nvidia MCP61 Ethernet                                             | 1         | 0.54%   |
| MediaTek Wiko U316AT                                              | 1         | 0.54%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 0.54%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 0.54%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1         | 0.54%   |
| Loongson Gigabit Ethernet Controller                              | 1         | 0.54%   |
| Intel Ethernet Controller I226-V                                  | 1         | 0.54%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.54%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.54%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.54%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.54%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.54%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.54%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.54%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.54%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.54%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 172       | 49.86%  |
| WiFi     | 171       | 49.57%  |
| Modem    | 1         | 0.29%   |
| Unknown  | 1         | 0.29%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 135       | 62.5%   |
| Ethernet | 81        | 37.5%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 111       | 50%     |
| 1     | 96        | 43.24%  |
| 0     | 10        | 4.5%    |
| 3     | 4         | 1.8%    |
| 4     | 1         | 0.45%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 204       | 91.89%  |
| Yes  | 18        | 8.11%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 57        | 39.04%  |
| Qualcomm Atheros Communications | 23        | 15.75%  |
| Realtek Semiconductor           | 17        | 11.64%  |
| Cambridge Silicon Radio         | 13        | 8.9%    |
| Foxconn / Hon Hai               | 8         | 5.48%   |
| Broadcom                        | 7         | 4.79%   |
| Realtek                         | 5         | 3.42%   |
| Lite-On Technology              | 4         | 2.74%   |
| IMC Networks                    | 4         | 2.74%   |
| Toshiba                         | 1         | 0.68%   |
| Ralink Technology               | 1         | 0.68%   |
| MediaTek                        | 1         | 0.68%   |
| Marvell Semiconductor           | 1         | 0.68%   |
| Dynex                           | 1         | 0.68%   |
| Dell                            | 1         | 0.68%   |
| ASUSTek Computer                | 1         | 0.68%   |
| Apple                           | 1         | 0.68%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 24        | 16.44%  |
| Qualcomm Atheros  Bluetooth Device                                                  | 16        | 10.96%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 13        | 8.9%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 10        | 6.85%   |
| Intel AX201 Bluetooth                                                               | 10        | 6.85%   |
| Realtek Bluetooth Radio                                                             | 9         | 6.16%   |
| Intel AX200 Bluetooth                                                               | 6         | 4.11%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 5         | 3.42%   |
| Realtek Bluetooth Radio                                                             | 5         | 3.42%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 4         | 2.74%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 2.05%   |
| Intel Bluetooth Device                                                              | 3         | 2.05%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 1.37%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 2         | 1.37%   |
| Lite-On Bluetooth Device                                                            | 2         | 1.37%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.37%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 1.37%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 2         | 1.37%   |
| IMC Networks Bluetooth Device                                                       | 2         | 1.37%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 2         | 1.37%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 1.37%   |
| Broadcom HP Portable SoftSailing                                                    | 2         | 1.37%   |
| Toshiba Bluetooth Radio                                                             | 1         | 0.68%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.68%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.68%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.68%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 1         | 0.68%   |
| MediaTek BT                                                                         | 1         | 0.68%   |
| Marvell Bluetooth and Wireless LAN Composite                                        | 1         | 0.68%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.68%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.68%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.68%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth                                     | 1         | 0.68%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.68%   |
| Foxconn / Hon Hai BCM43142A0                                                        | 1         | 0.68%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]                            | 1         | 0.68%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.68%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 0.68%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 1         | 0.68%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 1         | 0.68%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 169       | 61.01%  |
| AMD                                          | 54        | 19.49%  |
| Nvidia                                       | 40        | 14.44%  |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 0.72%   |
| Zhaoxin                                      | 2         | 0.72%   |
| C-Media Electronics                          | 2         | 0.72%   |
| XMOS                                         | 1         | 0.36%   |
| Phytium Technology                           | 1         | 0.36%   |
| Microdia                                     | 1         | 0.36%   |
| Loongson Technology                          | 1         | 0.36%   |
| JMTek                                        | 1         | 0.36%   |
| Creative Technology                          | 1         | 0.36%   |
| BEHRINGER International                      | 1         | 0.36%   |
| ASUSTek Computer                             | 1         | 0.36%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 24        | 7.16%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 22        | 6.57%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 21        | 6.27%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 14        | 4.18%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 11        | 3.28%   |
| Intel 8 Series HD Audio Controller                                                                | 11        | 3.28%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 11        | 3.28%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 10        | 2.99%   |
| Intel Broadwell-U Audio Controller                                                                | 10        | 2.99%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 8         | 2.39%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 8         | 2.39%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 8         | 2.39%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 8         | 2.39%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 7         | 2.09%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 7         | 2.09%   |
| Intel Cannon Lake PCH cAVS                                                                        | 7         | 2.09%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 7         | 2.09%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 5         | 1.49%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 1.49%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 1.49%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 1.19%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 1.19%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 1.19%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 1.19%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 4         | 1.19%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 3         | 0.9%    |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.9%    |
| Nvidia GF119 HDMI Audio Controller                                                                | 3         | 0.9%    |
| Nvidia GF116 High Definition Audio Controller                                                     | 3         | 0.9%    |
| Nvidia Audio device                                                                               | 3         | 0.9%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 0.9%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.9%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 3         | 0.9%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3         | 0.9%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 0.9%    |
| Intel 200 Series PCH HD Audio                                                                     | 3         | 0.9%    |
| AMD Wrestler HDMI Audio                                                                           | 3         | 0.9%    |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 0.9%    |
| AMD FCH Azalia Controller                                                                         | 3         | 0.9%    |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                                    | 2         | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Samsung Electronics                | 33        | 22.45%  |
| SK hynix                           | 29        | 19.73%  |
| Unknown                            | 16        | 10.88%  |
| Kingston                           | 16        | 10.88%  |
| Micron Technology                  | 12        | 8.16%   |
| Smart                              | 4         | 2.72%   |
| Ramaxel Technology                 | 4         | 2.72%   |
| Nanya Technology                   | 4         | 2.72%   |
| Unknown (ABCD)                     | 3         | 2.04%   |
| G.Skill                            | 3         | 2.04%   |
| Crucial                            | 3         | 2.04%   |
| Corsair                            | 3         | 2.04%   |
| A-DATA Technology                  | 3         | 2.04%   |
| Unknown                            | 2         | 1.36%   |
| Unknown (07FB)                     | 1         | 0.68%   |
| UniIC                              | 1         | 0.68%   |
| Team                               | 1         | 0.68%   |
| Smart Brazil                       | 1         | 0.68%   |
| MTASE                              | 1         | 0.68%   |
| Kingmax                            | 1         | 0.68%   |
| KINGBANK                           | 1         | 0.68%   |
| Kimtigo Semiconductor (HK) Limited | 1         | 0.68%   |
| JEDEC ID: 0000h                    | 1         | 0.68%   |
| CSX                                | 1         | 0.68%   |
| ChangXin Memory                    | 1         | 0.68%   |
| Apacer                             | 1         | 0.68%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 1.91%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB Row Of Chips DDR4 2667MT/s     | 3         | 1.91%   |
| Kingston RAM TF32D4U2S1MEH-8 8192MB DIMM DDR4 3200MT/s           | 3         | 1.91%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 2         | 1.27%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 2         | 1.27%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2133MT/s                  | 2         | 1.27%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.27%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.27%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 2         | 1.27%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.27%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.27%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 1.27%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1.27%   |
| Samsung RAM K4EBE304ED-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 2         | 1.27%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 2         | 1.27%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 1.27%   |
| Unknown                                                          | 2         | 1.27%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.64%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                        | 1         | 0.64%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                   | 1         | 0.64%   |
| Unknown RAM Module 4GB SODIMM LPDDR3 1600MT/s                    | 1         | 0.64%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2667MT/s                   | 1         | 0.64%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 0.64%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 1         | 0.64%   |
| Unknown RAM Module 4096MB DIMM DDR3 1067MT/s                     | 1         | 0.64%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                           | 1         | 0.64%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 1         | 0.64%   |
| Unknown RAM Module 2048MB SODIMM LPDDR3 1600MT/s                 | 1         | 0.64%   |
| Unknown RAM Module 2048MB SODIMM DDR3                            | 1         | 0.64%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 1         | 0.64%   |
| Unknown RAM Module 2048MB Chip DDR3 1066MT/s                     | 1         | 0.64%   |
| Unknown RAM Module 1024MB SODIMM LPDDR4 2400MT/s                 | 1         | 0.64%   |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 1         | 0.64%   |
| Unknown RAM 1866 CL10 Ser 8192MB DIMM DDR3 800MT/s               | 1         | 0.64%   |
| Unknown (07FB) RAM GST32G08SCL196P-26 32GB SODIMM DDR4 2667MT/s  | 1         | 0.64%   |
| UniIC RAM SCC08GU03H1F1C-26V 8192MB DIMM DDR4 2666MT/s           | 1         | 0.64%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s              | 1         | 0.64%   |
| Smart RAM SH564568FJ8NZRNSDR 2GB SODIMM DDR3 1600MT/s            | 1         | 0.64%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s            | 1         | 0.64%   |
| Smart RAM SG564568FG8NWKF-Z1 2GB SODIMM DDR2 800MT/s             | 1         | 0.64%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 66        | 50%     |
| DDR3    | 35        | 26.52%  |
| LPDDR4  | 9         | 6.82%   |
| LPDDR3  | 9         | 6.82%   |
| SDRAM   | 3         | 2.27%   |
| DDR5    | 3         | 2.27%   |
| DDR2    | 3         | 2.27%   |
| LPDDR5  | 2         | 1.52%   |
| Unknown | 2         | 1.52%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 81        | 61.36%  |
| DIMM         | 32        | 24.24%  |
| Row Of Chips | 16        | 12.12%  |
| Chip         | 2         | 1.52%   |
| Unknown      | 1         | 0.76%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 66        | 47.14%  |
| 4096  | 42        | 30%     |
| 2048  | 15        | 10.71%  |
| 16384 | 12        | 8.57%   |
| 1024  | 3         | 2.14%   |
| 32768 | 2         | 1.43%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 23        | 16.43%  |
| 1600    | 23        | 16.43%  |
| 3200    | 17        | 12.14%  |
| 2400    | 12        | 8.57%   |
| 2133    | 11        | 7.86%   |
| 2666    | 5         | 3.57%   |
| 1867    | 5         | 3.57%   |
| 1333    | 5         | 3.57%   |
| 4266    | 3         | 2.14%   |
| 1334    | 3         | 2.14%   |
| 1066    | 3         | 2.14%   |
| Unknown | 3         | 2.14%   |
| 4800    | 2         | 1.43%   |
| 3600    | 2         | 1.43%   |
| 3400    | 2         | 1.43%   |
| 3266    | 2         | 1.43%   |
| 1067    | 2         | 1.43%   |
| 800     | 2         | 1.43%   |
| 7467    | 1         | 0.71%   |
| 6400    | 1         | 0.71%   |
| 5600    | 1         | 0.71%   |
| 4267    | 1         | 0.71%   |
| 4199    | 1         | 0.71%   |
| 3800    | 1         | 0.71%   |
| 3733    | 1         | 0.71%   |
| 3533    | 1         | 0.71%   |
| 3500    | 1         | 0.71%   |
| 3466    | 1         | 0.71%   |
| 3000    | 1         | 0.71%   |
| 2933    | 1         | 0.71%   |
| 2800    | 1         | 0.71%   |
| 2048    | 1         | 0.71%   |
| 667     | 1         | 0.71%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Seiko Epson     | 1         | 50%     |
| Hewlett-Packard | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 34        | 24.29%  |
| Realtek Semiconductor                  | 14        | 10%     |
| Microdia                               | 12        | 8.57%   |
| IMC Networks                           | 11        | 7.86%   |
| Quanta                                 | 9         | 6.43%   |
| Sunplus Innovation Technology          | 8         | 5.71%   |
| Silicon Motion                         | 7         | 5%      |
| Syntek                                 | 6         | 4.29%   |
| Suyin                                  | 6         | 4.29%   |
| Logitech                               | 6         | 4.29%   |
| Lite-On Technology                     | 4         | 2.86%   |
| Bison Electronics                      | 4         | 2.86%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 2.14%   |
| Ricoh                                  | 2         | 1.43%   |
| Primax Electronics                     | 2         | 1.43%   |
| Alcor Micro                            | 2         | 1.43%   |
| LG Electronics                         | 1         | 0.71%   |
| Lenovo                                 | 1         | 0.71%   |
| kingcome                               | 1         | 0.71%   |
| icSpring                               | 1         | 0.71%   |
| HD 2MP WEBCAM                          | 1         | 0.71%   |
| Goodong Industry                       | 1         | 0.71%   |
| Generalplus Technology                 | 1         | 0.71%   |
| Arkmicro Technologies                  | 1         | 0.71%   |
| Apple                                  | 1         | 0.71%   |
| Acer                                   | 1         | 0.71%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 8         | 5.67%   |
| IMC Networks Integrated Camera           | 5         | 3.55%   |
| Quanta HD User Facing                    | 4         | 2.84%   |
| Logitech Webcam C270                     | 4         | 2.84%   |
| Chicony EasyCamera                       | 4         | 2.84%   |
| Syntek EasyCamera                        | 3         | 2.13%   |
| Silicon Motion Web Camera                | 3         | 2.13%   |
| Quanta HP TrueVision HD Camera           | 3         | 2.13%   |
| Microdia Integrated_Webcam_HD            | 3         | 2.13%   |
| IMC Networks ov9734_azurewave_camera     | 3         | 2.13%   |
| Chicony TOSHIBA Web Camera - HD          | 3         | 2.13%   |
| Syntek Integrated Camera                 | 2         | 1.42%   |
| Sunplus Integrated_Webcam_HD             | 2         | 1.42%   |
| Sunplus HD WebCam                        | 2         | 1.42%   |
| Realtek Integrated_Webcam_HD             | 2         | 1.42%   |
| Realtek HP "Truevision HD" laptop camera | 2         | 1.42%   |
| Primax HP HD Webcam [Fixed]              | 2         | 1.42%   |
| Microdia USB 2.0 Camera                  | 2         | 1.42%   |
| Chicony HP Webcam                        | 2         | 1.42%   |
| Chicony HP HD Webcam                     | 2         | 1.42%   |
| Syntek Lenovo EasyCamera                 | 1         | 0.71%   |
| Suyin Integrated_Webcam_HD               | 1         | 0.71%   |
| Suyin HP Webcam 101                      | 1         | 0.71%   |
| Suyin HP Truevision HD                   | 1         | 0.71%   |
| Suyin HD WebCam                          | 1         | 0.71%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 1         | 0.71%   |
| Suyin 1.3M HD WebCam                     | 1         | 0.71%   |
| Sunplus XiaoMi USB 2.0 Webcam            | 1         | 0.71%   |
| Sunplus Hy-FHD(9807)-Camera              | 1         | 0.71%   |
| Sunplus HP Wide Vision HD                | 1         | 0.71%   |
| Sunplus Asus Webcam                      | 1         | 0.71%   |
| Silicon Motion WebCam SC-13HDL11939N     | 1         | 0.71%   |
| Silicon Motion WebCam SC-10IRQ12340N     | 1         | 0.71%   |
| Silicon Motion WebCam SC-0311139N        | 1         | 0.71%   |
| Silicon Motion ATIV VGA Camera           | 1         | 0.71%   |
| Ricoh Sony Vaio Integrated Webcam        | 1         | 0.71%   |
| Ricoh Laptop_Integrated_Webcam_FHD       | 1         | 0.71%   |
| Realtek USB2.0 camera                    | 1         | 0.71%   |
| Realtek USB Camera                       | 1         | 0.71%   |
| Realtek NexiGo N660P FHD Webcam          | 1         | 0.71%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


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

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


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

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Alcor Micro         | 3         | 50%     |
| Lenovo              | 1         | 16.67%  |
| Giesecke & Devrient | 1         | 16.67%  |
| Broadcom            | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


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

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 160       | 71.75%  |
| 1     | 51        | 22.87%  |
| 2     | 11        | 4.93%   |
| 3     | 1         | 0.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 27        | 36.49%  |
| Graphics card            | 23        | 31.08%  |
| Multimedia controller    | 8         | 10.81%  |
| Chipcard                 | 5         | 6.76%   |
| Net/wireless             | 4         | 5.41%   |
| Sound                    | 3         | 4.05%   |
| Unassigned class         | 1         | 1.35%   |
| Storage                  | 1         | 1.35%   |
| Communication controller | 1         | 1.35%   |
| Camera                   | 1         | 1.35%   |

