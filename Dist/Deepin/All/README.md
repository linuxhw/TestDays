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

Total: 262

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| Deepin         | 47        | 24.61%  |
| Deepin 20      | 31        | 16.23%  |
| Deepin 15.11   | 27        | 14.14%  |
| UOS 20         | 18        | 9.42%   |
| Deepin 15.9.2  | 12        | 6.28%   |
| Deepin 20.3    | 7         | 3.66%   |
| Deepin 20.1    | 7         | 3.66%   |
| Deepin 20 beta | 7         | 3.66%   |
| Deepin 23      | 4         | 2.09%   |
| Deepin 20.5    | 4         | 2.09%   |
| Deepin 20.2.4  | 3         | 1.57%   |
| Deepin 20.2.3  | 3         | 1.57%   |
| Deepin 20.2.2  | 3         | 1.57%   |
| Deepin 15.10.1 | 3         | 1.57%   |
| Deepin 20.7.1  | 2         | 1.05%   |
| Deepin 20.6    | 2         | 1.05%   |
| Deepin 15.9.3  | 2         | 1.05%   |
| Deepin 2014.3  | 1         | 0.52%   |
| Deepin 20.7    | 1         | 0.52%   |
| Deepin 20.4    | 1         | 0.52%   |
| Deepin 20.2.1  | 1         | 0.52%   |
| Deepin 20.2    | 1         | 0.52%   |
| Deepin 15.9    | 1         | 0.52%   |
| Deepin 15.8    | 1         | 0.52%   |
| Deepin 15.7    | 1         | 0.52%   |
| Deepin 15.10   | 1         | 0.52%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Deepin | 182       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 4.15.0-30deepin-generic      | 41        | 21.58%  |
| 5.4.50-amd64-desktop         | 22        | 11.58%  |
| 4.15.0-29deepin-generic      | 19        | 10%     |
| 5.4.70-amd64-desktop         | 16        | 8.42%   |
| 5.10.60-amd64-desktop        | 12        | 6.32%   |
| 5.3.0-3-amd64                | 10        | 5.26%   |
| 5.7.7-amd64-desktop          | 6         | 3.16%   |
| 5.10.29-amd64-desktop        | 6         | 3.16%   |
| 5.10.41-amd64-desktop        | 5         | 2.63%   |
| 5.10.36-amd64-desktop        | 5         | 2.63%   |
| 5.10.18-amd64-desktop        | 4         | 2.11%   |
| 5.18.17-amd64-desktop-hwe    | 3         | 1.58%   |
| 5.15.24-amd64-desktop        | 3         | 1.58%   |
| 5.15.1-amd64-desktop         | 3         | 1.58%   |
| 5.10.50-amd64-desktop        | 3         | 1.58%   |
| 5.10.5-amd64-desktop+        | 3         | 1.58%   |
| 5.10.101-amd64-desktop       | 3         | 1.58%   |
| 4.19.0-amd64-desktop         | 3         | 1.58%   |
| 5.8.14-amd64-desktop         | 2         | 1.05%   |
| 5.5.4-xanmod3                | 2         | 1.05%   |
| 5.10.83-amd64-desktop        | 2         | 1.05%   |
| 5.10.0-amd64-desktop         | 2         | 1.05%   |
| 5.6.14-050614-generic        | 1         | 0.53%   |
| 5.6.12-xanmod1               | 1         | 0.53%   |
| 5.4.2-xanmod2                | 1         | 0.53%   |
| 5.3.8-xanmod6                | 1         | 0.53%   |
| 5.2.14-050214-lowlatency     | 1         | 0.53%   |
| 5.15.45-amd64-desktop        | 1         | 0.53%   |
| 5.14.0-rc3-amd64-desktop     | 1         | 0.53%   |
| 5.12.18-amd64-desktop        | 1         | 0.53%   |
| 5.10.0-11-arm64              | 1         | 0.53%   |
| 5.1.15-surface-linux-surface | 1         | 0.53%   |
| 5.1.0-050100rc2-generic      | 1         | 0.53%   |
| 4.19.90-1.lns7.2.mips64el    | 1         | 0.53%   |
| 4.19.0-arm64-desktop         | 1         | 0.53%   |
| 4.19.0-5-amd64               | 1         | 0.53%   |
| 4.15.0-135-generic           | 1         | 0.53%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 4.15.0   | 61        | 32.11%  |
| 5.4.50   | 22        | 11.58%  |
| 5.4.70   | 16        | 8.42%   |
| 5.10.60  | 12        | 6.32%   |
| 5.3.0    | 10        | 5.26%   |
| 5.7.7    | 6         | 3.16%   |
| 5.10.29  | 6         | 3.16%   |
| 5.10.41  | 5         | 2.63%   |
| 5.10.36  | 5         | 2.63%   |
| 4.19.0   | 5         | 2.63%   |
| 5.10.18  | 4         | 2.11%   |
| 5.18.17  | 3         | 1.58%   |
| 5.15.24  | 3         | 1.58%   |
| 5.15.1   | 3         | 1.58%   |
| 5.10.50  | 3         | 1.58%   |
| 5.10.5   | 3         | 1.58%   |
| 5.10.101 | 3         | 1.58%   |
| 5.10.0   | 3         | 1.58%   |
| 5.8.14   | 2         | 1.05%   |
| 5.5.4    | 2         | 1.05%   |
| 5.10.83  | 2         | 1.05%   |
| 5.6.14   | 1         | 0.53%   |
| 5.6.12   | 1         | 0.53%   |
| 5.4.2    | 1         | 0.53%   |
| 5.3.8    | 1         | 0.53%   |
| 5.2.14   | 1         | 0.53%   |
| 5.15.45  | 1         | 0.53%   |
| 5.14.0   | 1         | 0.53%   |
| 5.12.18  | 1         | 0.53%   |
| 5.1.15   | 1         | 0.53%   |
| 5.1.0    | 1         | 0.53%   |
| 4.19.90  | 1         | 0.53%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.15    | 61        | 32.8%   |
| 5.10    | 44        | 23.66%  |
| 5.4     | 38        | 20.43%  |
| 5.3     | 11        | 5.91%   |
| 5.7     | 6         | 3.23%   |
| 5.15    | 6         | 3.23%   |
| 4.19    | 6         | 3.23%   |
| 5.18    | 3         | 1.61%   |
| 5.8     | 2         | 1.08%   |
| 5.6     | 2         | 1.08%   |
| 5.5     | 2         | 1.08%   |
| 5.1     | 2         | 1.08%   |
| 5.2     | 1         | 0.54%   |
| 5.14    | 1         | 0.54%   |
| 5.12    | 1         | 0.54%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 179       | 98.35%  |
| aarch64 | 2         | 1.1%    |
| mips64  | 1         | 0.55%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Deepin  | 152       | 83.06%  |
| Unknown | 28        | 15.3%   |
| MATE    | 1         | 0.55%   |
| KDE5    | 1         | 0.55%   |
| KDE     | 1         | 0.55%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 180       | 98.9%   |
| Tty  | 2         | 1.1%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 88        | 47.83%  |
| TDM     | 53        | 28.8%   |
| LightDM | 43        | 23.37%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 39        | 21.2%   |
| en_US   | 36        | 19.57%  |
| zh_CN   | 28        | 15.22%  |
| pt_BR   | 24        | 13.04%  |
| es_ES   | 20        | 10.87%  |
| de_DE   | 12        | 6.52%   |
| ru_RU   | 7         | 3.8%    |
| it_IT   | 4         | 2.17%   |
| pl_PL   | 3         | 1.63%   |
| en_GB   | 3         | 1.63%   |
| tr_TR   | 2         | 1.09%   |
| fr_FR   | 2         | 1.09%   |
| sv_SE   | 1         | 0.54%   |
| lt_LT   | 1         | 0.54%   |
| ja_JP   | 1         | 0.54%   |
| id_ID   | 1         | 0.54%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 103       | 56.28%  |
| BIOS | 80        | 43.72%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 164       | 90.11%  |
| Unknown | 18        | 9.89%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 84        | 45.41%  |
| GPT     | 81        | 43.78%  |
| MBR     | 20        | 10.81%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 146       | 79.35%  |
| Yes       | 38        | 20.65%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 137       | 74.46%  |
| Yes       | 47        | 25.54%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Lenovo                     | 35        | 19.23%  |
| Hewlett-Packard            | 23        | 12.64%  |
| ASUSTek Computer           | 21        | 11.54%  |
| Dell                       | 16        | 8.79%   |
| Acer                       | 13        | 7.14%   |
| Gigabyte Technology        | 9         | 4.95%   |
| Samsung Electronics        | 8         | 4.4%    |
| Sony                       | 5         | 2.75%   |
| HUAWEI                     | 5         | 2.75%   |
| TSINGHUA TONGFANG COMPUTER | 4         | 2.2%    |
| Toshiba                    | 4         | 2.2%    |
| ASRock                     | 4         | 2.2%    |
| Positivo                   | 3         | 1.65%   |
| MSI                        | 3         | 1.65%   |
| Unknown                    | 3         | 1.65%   |
| Timi                       | 2         | 1.1%    |
| Semp Toshiba               | 2         | 1.1%    |
| Google                     | 2         | 1.1%    |
| ECS                        | 2         | 1.1%    |
| Standard                   | 1         | 0.55%   |
| Soyo                       | 1         | 0.55%   |
| Phytium                    | 1         | 0.55%   |
| Microtech                  | 1         | 0.55%   |
| Microsoft                  | 1         | 0.55%   |
| Medion                     | 1         | 0.55%   |
| Loongson                   | 1         | 0.55%   |
| Huanan                     | 1         | 0.55%   |
| HANWEI                     | 1         | 0.55%   |
| Gateway                    | 1         | 0.55%   |
| Fujitsu                    | 1         | 0.55%   |
| Foxconn                    | 1         | 0.55%   |
| Cube                       | 1         | 0.55%   |
| Chuwi                      | 1         | 0.55%   |
| CCE                        | 1         | 0.55%   |
| BQ                         | 1         | 0.55%   |
| Apple                      | 1         | 0.55%   |
| AMD                        | 1         | 0.55%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Unknown                                           | 5         | 2.75%   |
| TSINGHUA TONGFANG COMPUTER E500                   | 4         | 2.2%    |
| Semp Toshiba STI                                  | 2         | 1.1%    |
| Samsung 340XAA/350XAA/550XAA                      | 2         | 1.1%    |
| Lenovo IdeaPad 120S-11IAP 81A4                    | 2         | 1.1%    |
| HP Pavilion Notebook                              | 2         | 1.1%    |
| HP Pavilion 15                                    | 2         | 1.1%    |
| HP ENVY 15                                        | 2         | 1.1%    |
| ECS H81H3-M4                                      | 2         | 1.1%    |
| ASUS All Series                                   | 2         | 1.1%    |
| Acer Nitro AN515-54                               | 2         | 1.1%    |
| Toshiba Satellite L75-C                           | 1         | 0.55%   |
| Toshiba Satellite E55t-A                          | 1         | 0.55%   |
| Toshiba Satellite C850D-11K                       | 1         | 0.55%   |
| Toshiba Satellite C850-1H6                        | 1         | 0.55%   |
| Timi TM1701                                       | 1         | 0.55%   |
| Timi Redmi G 2022                                 | 1         | 0.55%   |
| Standard MB45II/MB45IN                            | 1         | 0.55%   |
| Soyo SY-Thin Mini H110                            | 1         | 0.55%   |
| Sony VPCYB25AB                                    | 1         | 0.55%   |
| Sony VGN-NS140D                                   | 1         | 0.55%   |
| Sony VGN-AW11Z_B                                  | 1         | 0.55%   |
| Sony SVF14A190X                                   | 1         | 0.55%   |
| Sony SVE14135CXP                                  | 1         | 0.55%   |
| Samsung P500A2D                                   | 1         | 0.55%   |
| Samsung 800G5M/800G5W                             | 1         | 0.55%   |
| Samsung 550P5C/550P7C                             | 1         | 0.55%   |
| Samsung 500R4K/500R5H/5400RK/501R5H/5500RH/500R5S | 1         | 0.55%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA        | 1         | 0.55%   |
| Samsung 270E5J/2570EJ                             | 1         | 0.55%   |
| Positivo POS-PQ45AU                               | 1         | 0.55%   |
| Positivo POS-EINM70CS                             | 1         | 0.55%   |
| Positivo C14CU51                                  | 1         | 0.55%   |
| Phytium D2000                                     | 1         | 0.55%   |
| MSI MS-7C83                                       | 1         | 0.55%   |
| MSI MS-7851                                       | 1         | 0.55%   |
| MSI MS-7681                                       | 1         | 0.55%   |
| Microtech ebookPro                                | 1         | 0.55%   |
| Microsoft Surface Pro 4                           | 1         | 0.55%   |
| Medion MS-7728                                    | 1         | 0.55%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                            | Computers | Percent |
|---------------------------------|-----------|---------|
| Dell Inspiron                   | 10        | 5.49%   |
| Lenovo IdeaPad                  | 9         | 4.95%   |
| Lenovo ThinkPad                 | 8         | 4.4%    |
| Acer Aspire                     | 7         | 3.85%   |
| HP Pavilion                     | 5         | 2.75%   |
| HP EliteBook                    | 5         | 2.75%   |
| Unknown                         | 5         | 2.75%   |
| TSINGHUA TONGFANG COMPUTER E500 | 4         | 2.2%    |
| Toshiba Satellite               | 4         | 2.2%    |
| HP Laptop                       | 4         | 2.2%    |
| Lenovo Legion                   | 3         | 1.65%   |
| ASUS PRIME                      | 3         | 1.65%   |
| Acer Nitro                      | 3         | 1.65%   |
| Semp Toshiba STI                | 2         | 1.1%    |
| Samsung 340XAA                  | 2         | 1.1%    |
| Lenovo ZHAOYANG                 | 2         | 1.1%    |
| Lenovo Yoga                     | 2         | 1.1%    |
| Lenovo ThinkCentre              | 2         | 1.1%    |
| Lenovo ThinkBook                | 2         | 1.1%    |
| HP ENVY                         | 2         | 1.1%    |
| ECS H81H3-M4                    | 2         | 1.1%    |
| Dell OptiPlex                   | 2         | 1.1%    |
| Dell Latitude                   | 2         | 1.1%    |
| ASUS All                        | 2         | 1.1%    |
| Acer Swift                      | 2         | 1.1%    |
| Timi TM1701                     | 1         | 0.55%   |
| Timi Redmi                      | 1         | 0.55%   |
| Standard MB45II                 | 1         | 0.55%   |
| Soyo SY-Thin                    | 1         | 0.55%   |
| Sony VPCYB25AB                  | 1         | 0.55%   |
| Sony VGN-NS140D                 | 1         | 0.55%   |
| Sony VGN-AW11Z                  | 1         | 0.55%   |
| Sony SVF14A190X                 | 1         | 0.55%   |
| Sony SVE14135CXP                | 1         | 0.55%   |
| Samsung P500A2D                 | 1         | 0.55%   |
| Samsung 800G5M                  | 1         | 0.55%   |
| Samsung 550P5C                  | 1         | 0.55%   |
| Samsung 500R4K                  | 1         | 0.55%   |
| Samsung 300E4A                  | 1         | 0.55%   |
| Samsung 270E5J                  | 1         | 0.55%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2017    | 19        | 10.44%  |
| 2019    | 18        | 9.89%   |
| 2018    | 17        | 9.34%   |
| 2013    | 17        | 9.34%   |
| 2012    | 17        | 9.34%   |
| 2021    | 14        | 7.69%   |
| 2014    | 13        | 7.14%   |
| 2020    | 12        | 6.59%   |
| 2016    | 12        | 6.59%   |
| 2011    | 12        | 6.59%   |
| 2010    | 9         | 4.95%   |
| 2009    | 8         | 4.4%    |
| 2015    | 7         | 3.85%   |
| 2022    | 3         | 1.65%   |
| 2008    | 2         | 1.1%    |
| Unknown | 2         | 1.1%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 117       | 64.29%  |
| Desktop        | 52        | 28.57%  |
| Tablet         | 5         | 2.75%   |
| All in one     | 3         | 1.65%   |
| Convertible    | 2         | 1.1%    |
| System on chip | 1         | 0.55%   |
| Mini pc        | 1         | 0.55%   |
| Server         | 1         | 0.55%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 174       | 95.6%   |
| Enabled  | 8         | 4.4%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 180       | 98.9%   |
| Yes  | 2         | 1.1%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 55        | 30.22%  |
| 8.01-16.0   | 43        | 23.63%  |
| 3.01-4.0    | 36        | 19.78%  |
| 16.01-24.0  | 35        | 19.23%  |
| 32.01-64.0  | 5         | 2.75%   |
| 1.01-2.0    | 5         | 2.75%   |
| 64.01-256.0 | 2         | 1.1%    |
| 2.01-3.0    | 1         | 0.55%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 62        | 32.29%  |
| 2.01-3.0  | 54        | 28.13%  |
| 4.01-8.0  | 31        | 16.15%  |
| 3.01-4.0  | 28        | 14.58%  |
| 0.51-1.0  | 13        | 6.77%   |
| 8.01-16.0 | 3         | 1.56%   |
| 0.01-0.5  | 1         | 0.52%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 120       | 64.86%  |
| 2      | 52        | 28.11%  |
| 4      | 7         | 3.78%   |
| 3      | 5         | 2.7%    |
| 5      | 1         | 0.54%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 118       | 64.13%  |
| Yes       | 66        | 35.87%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 147       | 80.77%  |
| No        | 35        | 19.23%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 141       | 77.47%  |
| No        | 41        | 22.53%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 119       | 65.38%  |
| No        | 63        | 34.62%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country               | Computers | Percent |
|-----------------------|-----------|---------|
| Brazil                | 45        | 24.59%  |
| China                 | 31        | 16.94%  |
| USA                   | 13        | 7.1%    |
| Germany               | 12        | 6.56%   |
| Spain                 | 6         | 3.28%   |
| Russia                | 5         | 2.73%   |
| Indonesia             | 5         | 2.73%   |
| Turkey                | 4         | 2.19%   |
| Poland                | 4         | 2.19%   |
| Panama                | 4         | 2.19%   |
| Italy                 | 4         | 2.19%   |
| Chile                 | 4         | 2.19%   |
| Mexico                | 3         | 1.64%   |
| Japan                 | 3         | 1.64%   |
| Colombia              | 3         | 1.64%   |
| Argentina             | 3         | 1.64%   |
| UK                    | 2         | 1.09%   |
| India                 | 2         | 1.09%   |
| Canada                | 2         | 1.09%   |
| Bangladesh            | 2         | 1.09%   |
| Austria               | 2         | 1.09%   |
| Venezuela             | 1         | 0.55%   |
| Ukraine               | 1         | 0.55%   |
| Tunisia               | 1         | 0.55%   |
| Sweden                | 1         | 0.55%   |
| South Africa          | 1         | 0.55%   |
| Singapore             | 1         | 0.55%   |
| Serbia                | 1         | 0.55%   |
| Sao Tome and Principe | 1         | 0.55%   |
| Romania               | 1         | 0.55%   |
| Portugal              | 1         | 0.55%   |
| Pakistan              | 1         | 0.55%   |
| New Zealand           | 1         | 0.55%   |
| Namibia               | 1         | 0.55%   |
| Lithuania             | 1         | 0.55%   |
| Iran                  | 1         | 0.55%   |
| Greece                | 1         | 0.55%   |
| France                | 1         | 0.55%   |
| Ecuador               | 1         | 0.55%   |
| Czechia               | 1         | 0.55%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Computers | Percent |
|-----------------|-----------|---------|
| Beijing         | 6         | 3.24%   |
| Sao Paulo       | 5         | 2.7%    |
| Guangzhou       | 4         | 2.16%   |
| David           | 4         | 2.16%   |
| Shanghai        | 3         | 1.62%   |
| Nanjing         | 3         | 1.62%   |
| Curitiba        | 3         | 1.62%   |
| Wuhan           | 2         | 1.08%   |
| Uberlândia     | 2         | 1.08%   |
| Surabaya        | 2         | 1.08%   |
| San Francisco   | 2         | 1.08%   |
| Petrópolis     | 2         | 1.08%   |
| Londrina        | 2         | 1.08%   |
| Getxo           | 2         | 1.08%   |
| Dhaka           | 2         | 1.08%   |
| Contagem        | 2         | 1.08%   |
| Brasília       | 2         | 1.08%   |
| Bogotá         | 2         | 1.08%   |
| Atlanta         | 2         | 1.08%   |
| Yozgat          | 1         | 0.54%   |
| Yogyakarta      | 1         | 0.54%   |
| Xuhui           | 1         | 0.54%   |
| Windhoek        | 1         | 0.54%   |
| West Jordan     | 1         | 0.54%   |
| Waynesville     | 1         | 0.54%   |
| Voluntari       | 1         | 0.54%   |
| Villa Ballester | 1         | 0.54%   |
| Vigo            | 1         | 0.54%   |
| Ufa             | 1         | 0.54%   |
| Tychy           | 1         | 0.54%   |
| Tomsk           | 1         | 0.54%   |
| Toluca          | 1         | 0.54%   |
| Tokyo           | 1         | 0.54%   |
| Tianjin         | 1         | 0.54%   |
| TehrДЃn       | 1         | 0.54%   |
| Taua            | 1         | 0.54%   |
| Taiyuan         | 1         | 0.54%   |
| Tai'an          | 1         | 0.54%   |
| SГЈo TomГ©  | 1         | 0.54%   |
| Suzhou          | 1         | 0.54%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 41        | 50     | 15.89%  |
| Seagate                        | 37        | 43     | 14.34%  |
| Samsung Electronics            | 24        | 27     | 9.3%    |
| Toshiba                        | 18        | 20     | 6.98%   |
| SanDisk                        | 18        | 22     | 6.98%   |
| Unknown                        | 16        | 17     | 6.2%    |
| Kingston                       | 13        | 18     | 5.04%   |
| Hitachi                        | 8         | 8      | 3.1%    |
| SK hynix                       | 7         | 7      | 2.71%   |
| Crucial                        | 7         | 8      | 2.71%   |
| Micron Technology              | 6         | 8      | 2.33%   |
| China                          | 6         | 6      | 2.33%   |
| HGST                           | 5         | 5      | 1.94%   |
| A-DATA Technology              | 5         | 6      | 1.94%   |
| SPCC                           | 4         | 5      | 1.55%   |
| Intel                          | 4         | 5      | 1.55%   |
| Silicon Motion                 | 3         | 3      | 1.16%   |
| LITEON                         | 3         | 3      | 1.16%   |
| Vaseky                         | 2         | 2      | 0.78%   |
| Phison                         | 2         | 2      | 0.78%   |
| Maxtor                         | 2         | 4      | 0.78%   |
| JMicron Technology             | 2         | 2      | 0.78%   |
| Intenso                        | 2         | 3      | 0.78%   |
| Hewlett-Packard                | 2         | 3      | 0.78%   |
| FORESEE                        | 2         | 2      | 0.78%   |
| V-GeN                          | 1         | 1      | 0.39%   |
| Transcend                      | 1         | 1      | 0.39%   |
| Solid State Storage Technology | 1         | 1      | 0.39%   |
| Realtek Semiconductor          | 1         | 1      | 0.39%   |
| OEM                            | 1         | 1      | 0.39%   |
| OCZ                            | 1         | 1      | 0.39%   |
| Netac                          | 1         | 1      | 0.39%   |
| Mushkin                        | 1         | 1      | 0.39%   |
| Microtech                      | 1         | 1      | 0.39%   |
| Maxtor 6                       | 1         | 1      | 0.39%   |
| LaCie                          | 1         | 2      | 0.39%   |
| KingSpec                       | 1         | 1      | 0.39%   |
| KingDian                       | 1         | 1      | 0.39%   |
| KINGBANK                       | 1         | 1      | 0.39%   |
| Hikvision                      | 1         | 1      | 0.39%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 6         | 2.22%   |
| Toshiba MQ01ABF050 500GB             | 5         | 1.85%   |
| Kingston SA400S37240G 240GB SSD      | 5         | 1.85%   |
| WDC WD5000LPCX-24VHAT0 500GB         | 3         | 1.11%   |
| Unknown MMC Card                     | 3         | 1.11%   |
| Toshiba MQ01ABD100 1TB               | 3         | 1.11%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 3         | 1.11%   |
| Seagate ST1000DM010-2EP102 1TB       | 3         | 1.11%   |
| Samsung SSD 850 EVO 500GB            | 3         | 1.11%   |
| Crucial CT240BX500SSD1 240GB         | 3         | 1.11%   |
| WDC WD5000AAKX-003CA0 500GB          | 2         | 0.74%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB | 2         | 0.74%   |
| SPCC Solid State Disk 512GB          | 2         | 0.74%   |
| Seagate ST9320325AS 320GB            | 2         | 0.74%   |
| Seagate ST2000LM007-1R8174 2TB       | 2         | 0.74%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 0.74%   |
| Seagate ST1000DM003-1SB102 1TB       | 2         | 0.74%   |
| SanDisk SSD PLUS 240GB               | 2         | 0.74%   |
| SanDisk SDSSDH3512G 512GB            | 2         | 0.74%   |
| SanDisk SDSSDA240G 240GB             | 2         | 0.74%   |
| SanDisk SDSSDA120G 120GB             | 2         | 0.74%   |
| SanDisk DF4064  64GB                 | 2         | 0.74%   |
| Samsung MZVLW256HEHP-000H1 256GB     | 2         | 0.74%   |
| Kingston SV300S37A120G 120GB SSD     | 2         | 0.74%   |
| JMicron Generic 1TB                  | 2         | 0.74%   |
| HGST HTS545050A7E680 500GB           | 2         | 0.74%   |
| FORESEE P900F256GBH                  | 2         | 0.74%   |
| WDC WDS500G2B0C-00PXH0 500GB         | 1         | 0.37%   |
| WDC WDS500G2B0B-00YS70 500GB SSD     | 1         | 0.37%   |
| WDC WDS480G2G0B-00EPW0 480GB SSD     | 1         | 0.37%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 1         | 0.37%   |
| WDC WDS120G1G0A-00SS50 120GB SSD     | 1         | 0.37%   |
| WDC WDS100T2G0A-00JH30 1TB SSD       | 1         | 0.37%   |
| WDC WD80 0BEVE-11UYT0 80GB           | 1         | 0.37%   |
| WDC WD7500BPVT-24HXZT3 752GB         | 1         | 0.37%   |
| WDC WD7500BPKX-22HPJT0 752GB         | 1         | 0.37%   |
| WDC WD6400AAKS-75A7B0 640GB          | 1         | 0.37%   |
| WDC WD5000LPZX-75Z10T0 500GB         | 1         | 0.37%   |
| WDC WD5000LPVX-80V0TT0 500GB         | 1         | 0.37%   |
| WDC WD5000LPVX-08V0TT6 500GB         | 1         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 36        | 42     | 33.03%  |
| WDC                 | 33        | 39     | 30.28%  |
| Toshiba             | 17        | 19     | 15.6%   |
| Hitachi             | 8         | 8      | 7.34%   |
| HGST                | 5         | 5      | 4.59%   |
| Samsung Electronics | 3         | 3      | 2.75%   |
| Maxtor              | 2         | 4      | 1.83%   |
| Unknown             | 1         | 2      | 0.92%   |
| OEM                 | 1         | 1      | 0.92%   |
| Maxtor 6            | 1         | 1      | 0.92%   |
| Hewlett-Packard     | 1         | 2      | 0.92%   |
| Fujitsu             | 1         | 2      | 0.92%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 16        | 20     | 18.39%  |
| Kingston            | 13        | 18     | 14.94%  |
| Samsung Electronics | 11        | 13     | 12.64%  |
| China               | 6         | 6      | 6.9%    |
| WDC                 | 5         | 5      | 5.75%   |
| Crucial             | 5         | 6      | 5.75%   |
| SPCC                | 4         | 5      | 4.6%    |
| A-DATA Technology   | 3         | 4      | 3.45%   |
| Vaseky              | 2         | 2      | 2.3%    |
| SK hynix            | 2         | 2      | 2.3%    |
| Micron Technology   | 2         | 3      | 2.3%    |
| LITEON              | 2         | 2      | 2.3%    |
| JMicron Technology  | 2         | 2      | 2.3%    |
| Intenso             | 2         | 3      | 2.3%    |
| V-GeN               | 1         | 1      | 1.15%   |
| Unknown             | 1         | 1      | 1.15%   |
| Transcend           | 1         | 1      | 1.15%   |
| OCZ                 | 1         | 1      | 1.15%   |
| Netac               | 1         | 1      | 1.15%   |
| Microtech           | 1         | 1      | 1.15%   |
| KingSpec            | 1         | 1      | 1.15%   |
| KingDian            | 1         | 1      | 1.15%   |
| KINGBANK            | 1         | 1      | 1.15%   |
| Intel               | 1         | 2      | 1.15%   |
| Hewlett-Packard     | 1         | 1      | 1.15%   |
| Apacer              | 1         | 3      | 1.15%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 98        | 128    | 41.88%  |
| SSD     | 75        | 106    | 32.05%  |
| NVMe    | 45        | 50     | 19.23%  |
| MMC     | 14        | 15     | 5.98%   |
| Unknown | 2         | 3      | 0.85%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 142       | 224    | 67.62%  |
| NVMe | 45        | 50     | 21.43%  |
| MMC  | 14        | 15     | 6.67%   |
| SAS  | 9         | 13     | 4.29%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 102       | 149    | 59.3%   |
| 0.51-1.0   | 61        | 74     | 35.47%  |
| 1.01-2.0   | 8         | 10     | 4.65%   |
| 4.01-10.0  | 1         | 1      | 0.58%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 50        | 26.74%  |
| 101-250        | 46        | 24.6%   |
| 501-1000       | 37        | 19.79%  |
| 1001-2000      | 24        | 12.83%  |
| 51-100         | 9         | 4.81%   |
| More than 3000 | 7         | 3.74%   |
| 21-50          | 5         | 2.67%   |
| 2001-3000      | 4         | 2.14%   |
| Unknown        | 4         | 2.14%   |
| 1-20           | 1         | 0.53%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 21-50     | 40        | 21.05%  |
| 1-20      | 39        | 20.53%  |
| 101-250   | 36        | 18.95%  |
| 51-100    | 24        | 12.63%  |
| 251-500   | 19        | 10%     |
| 501-1000  | 19        | 10%     |
| 1001-2000 | 6         | 3.16%   |
| Unknown   | 4         | 2.11%   |
| 2001-3000 | 3         | 1.58%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                         | Computers | Drives | Percent |
|-----------------------------------------------|-----------|--------|---------|
| Seagate ST9320325AS 320GB                     | 2         | 2      | 11.76%  |
| WDC WD10JPVX-22JC3T0 1TB                      | 1         | 1      | 5.88%   |
| WDC WD10EARS-00Y5B1 1TB                       | 1         | 1      | 5.88%   |
| Toshiba MQ01ABD100 1TB                        | 1         | 1      | 5.88%   |
| Toshiba MQ01ABD032 320GB                      | 1         | 1      | 5.88%   |
| SK hynix BC511 HFM256GDJTNI-82A0A 256GB       | 1         | 1      | 5.88%   |
| Seagate ST3750528AS 752GB                     | 1         | 1      | 5.88%   |
| Seagate ST2000LM003 HN-M201RAD 2TB            | 1         | 1      | 5.88%   |
| Seagate ST1000DL002-9TT153 1TB                | 1         | 1      | 5.88%   |
| Samsung Electronics HM250HI 250GB             | 1         | 1      | 5.88%   |
| Samsung Electronics HD502HJ 500GB             | 1         | 1      | 5.88%   |
| Samsung Electronics HD250HJ 250GB             | 1         | 1      | 5.88%   |
| OCZ VERTEX4 256GB SSD                         | 1         | 1      | 5.88%   |
| Micron Technology MTFDDAT128MAM-1J2 128GB SSD | 1         | 2      | 5.88%   |
| Intenso lntenso SSD Sata III 128GB            | 1         | 1      | 5.88%   |
| Hitachi HTS543225L9A300 250GB                 | 1         | 1      | 5.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 5      | 25%     |
| Samsung Electronics | 3         | 3      | 18.75%  |
| WDC                 | 2         | 2      | 12.5%   |
| Toshiba             | 2         | 2      | 12.5%   |
| SK hynix            | 1         | 1      | 6.25%   |
| OCZ                 | 1         | 1      | 6.25%   |
| Micron Technology   | 1         | 2      | 6.25%   |
| Intenso             | 1         | 1      | 6.25%   |
| Hitachi             | 1         | 1      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 5      | 33.33%  |
| Samsung Electronics | 3         | 3      | 25%     |
| WDC                 | 2         | 2      | 16.67%  |
| Toshiba             | 2         | 2      | 16.67%  |
| Hitachi             | 1         | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 12        | 13     | 75%     |
| SSD  | 3         | 4      | 18.75%  |
| NVMe | 1         | 1      | 6.25%   |

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
| Detected | 101       | 166    | 50.5%   |
| Works    | 81        | 116    | 40.5%   |
| Malfunc  | 16        | 18     | 8%      |
| Failed   | 2         | 2      | 1%      |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 131       | 62.09%  |
| AMD                            | 20        | 9.48%   |
| Samsung Electronics            | 11        | 5.21%   |
| SanDisk                        | 6         | 2.84%   |
| SK hynix                       | 5         | 2.37%   |
| ASMedia Technology             | 5         | 2.37%   |
| Silicon Motion                 | 4         | 1.9%    |
| Micron Technology              | 4         | 1.9%    |
| Marvell Technology Group       | 4         | 1.9%    |
| Phison Electronics             | 3         | 1.42%   |
| Shenzhen Longsys Electronics   | 2         | 0.95%   |
| Realtek Semiconductor          | 2         | 0.95%   |
| Nvidia                         | 2         | 0.95%   |
| Micron/Crucial Technology      | 2         | 0.95%   |
| JMicron Technology             | 2         | 0.95%   |
| Zhaoxin                        | 1         | 0.47%   |
| Solid State Storage Technology | 1         | 0.47%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.47%   |
| Loongson Technology            | 1         | 0.47%   |
| Lite-On Technology             | 1         | 0.47%   |
| KIOXIA                         | 1         | 0.47%   |
| Beijing Starblaze Technology   | 1         | 0.47%   |
| Unknown                        | 1         | 0.47%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 15        | 6.52%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 14        | 6.09%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 13        | 5.65%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 11        | 4.78%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 10        | 4.35%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 6         | 2.61%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 6         | 2.61%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 6         | 2.61%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 6         | 2.61%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 6         | 2.61%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5         | 2.17%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5         | 2.17%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 5         | 2.17%   |
| Micron Non-Volatile memory controller                                                   | 4         | 1.74%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 4         | 1.74%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 4         | 1.74%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4         | 1.74%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 4         | 1.74%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4         | 1.74%   |
| SK hynix BC511                                                                          | 3         | 1.3%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 3         | 1.3%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 3         | 1.3%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3         | 1.3%    |
| Intel Comet Lake SATA AHCI Controller                                                   | 3         | 1.3%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 3         | 1.3%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 3         | 1.3%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3         | 1.3%    |
| Shenzhen Longsys Non-Volatile memory controller                                         | 2         | 0.87%   |
| SanDisk Non-Volatile memory controller                                                  | 2         | 0.87%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 2         | 0.87%   |
| Intel SATA Controller [RAID mode]                                                       | 2         | 0.87%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 2         | 0.87%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2         | 0.87%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 2         | 0.87%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2         | 0.87%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 0.87%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 0.87%   |
| Zhaoxin ZX-100/ZX-200/ZX-E StorX AHCI Controller                                        | 1         | 0.43%   |
| Solid State Storage Non-Volatile memory controller                                      | 1         | 0.43%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                          | 1         | 0.43%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 137       | 65.87%  |
| NVMe | 45        | 21.63%  |
| IDE  | 17        | 8.17%   |
| RAID | 9         | 4.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 148       | 81.32%  |
| AMD          | 30        | 16.48%  |
| Phytium      | 2         | 1.1%    |
| CentaurHauls | 1         | 0.55%   |
| Unknown      | 1         | 0.55%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 2.75%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 4         | 2.2%    |
| Intel Core i7-3770 CPU @ 3.40GHz              | 4         | 2.2%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 2.2%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 4         | 2.2%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 1.65%   |
| Intel Core i7-10700 CPU @ 2.90GHz             | 3         | 1.65%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 3         | 1.65%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 1.65%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 1.65%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 2         | 1.1%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 1.1%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.1%    |
| Intel Core i7-4790 CPU @ 3.60GHz              | 2         | 1.1%    |
| Intel Core i7-4510U CPU @ 2.00GHz             | 2         | 1.1%    |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 1.1%    |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 2         | 1.1%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 1.1%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 1.1%    |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 1.1%    |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 1.1%    |
| Intel Core i3-6100 CPU @ 3.70GHz              | 2         | 1.1%    |
| Intel Core i3-4030U CPU @ 1.90GHz             | 2         | 1.1%    |
| Intel Core i3-4005U CPU @ 1.70GHz             | 2         | 1.1%    |
| Intel Core i3-10100 CPU @ 3.60GHz             | 2         | 1.1%    |
| Intel Celeron CPU N3350 @ 1.10GHz             | 2         | 1.1%    |
| Intel Celeron CPU 1007U @ 1.50GHz             | 2         | 1.1%    |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 2         | 1.1%    |
| Intel Atom CPU Z3735F @ 1.33GHz               | 2         | 1.1%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 1.1%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 1.1%    |
| AMD Ryzen 5 4600U with Radeon Graphics        | 2         | 1.1%    |
| AMD Ryzen 5 3600 6-Core Processor             | 2         | 1.1%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.1%    |
| AMD FX-8320 Eight-Core Processor              | 2         | 1.1%    |
| AMD 3020e with Radeon Graphics                | 2         | 1.1%    |
| Phytium D2000/8 E8C                           | 1         | 0.55%   |
| PHYTIUM D2000 Series CPU                      | 1         | 0.55%   |
| Intel Xeon CPU E5450 @ 3.00GHz                | 1         | 0.55%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz           | 1         | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 42        | 23.08%  |
| Intel Core i7           | 41        | 22.53%  |
| Intel Core i3           | 19        | 10.44%  |
| Other                   | 12        | 6.59%   |
| Intel Celeron           | 11        | 6.04%   |
| AMD Ryzen 5             | 9         | 4.95%   |
| Intel Core 2 Duo        | 8         | 4.4%    |
| Intel Atom              | 6         | 3.3%    |
| AMD Ryzen 7             | 5         | 2.75%   |
| Intel Pentium Dual-Core | 4         | 2.2%    |
| AMD FX                  | 4         | 2.2%    |
| Intel Pentium           | 3         | 1.65%   |
| AMD Ryzen 3             | 3         | 1.65%   |
| Intel Xeon              | 2         | 1.1%    |
| Intel Pentium Silver    | 2         | 1.1%    |
| Intel Core i9           | 2         | 1.1%    |
| AMD A10                 | 2         | 1.1%    |
| Intel Core m3           | 1         | 0.55%   |
| Intel Core M            | 1         | 0.55%   |
| Intel Celeron Dual-Core | 1         | 0.55%   |
| AMD E1                  | 1         | 0.55%   |
| AMD E                   | 1         | 0.55%   |
| AMD C-60                | 1         | 0.55%   |
| AMD Athlon              | 1         | 0.55%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 89        | 48.9%   |
| 4      | 69        | 37.91%  |
| 8      | 10        | 5.49%   |
| 6      | 9         | 4.95%   |
| 10     | 2         | 1.1%    |
| 12     | 1         | 0.55%   |
| 3      | 1         | 0.55%   |
| 1      | 1         | 0.55%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 182       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 125       | 68.68%  |
| 1      | 57        | 31.32%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 166       | 91.21%  |
| Unknown        | 16        | 8.79%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 46        | 25%     |
| 0x306a9    | 18        | 9.78%   |
| 0x40651    | 9         | 4.89%   |
| 0x806ec    | 8         | 4.35%   |
| 0x806e9    | 8         | 4.35%   |
| 0x206a7    | 8         | 4.35%   |
| 0x306d4    | 7         | 3.8%    |
| 0x1067a    | 7         | 3.8%    |
| 0x306c3    | 6         | 3.26%   |
| 0x406e3    | 5         | 2.72%   |
| 0x906ea    | 4         | 2.17%   |
| 0xa0655    | 3         | 1.63%   |
| 0x906e9    | 3         | 1.63%   |
| 0x806ea    | 3         | 1.63%   |
| 0x806c1    | 3         | 1.63%   |
| 0x406c4    | 3         | 1.63%   |
| 0x906a3    | 2         | 1.09%   |
| 0x506e3    | 2         | 1.09%   |
| 0x30678    | 2         | 1.09%   |
| 0x20655    | 2         | 1.09%   |
| 0x08600106 | 2         | 1.09%   |
| 0x08600104 | 2         | 1.09%   |
| 0x08200103 | 2         | 1.09%   |
| 0x08108109 | 2         | 1.09%   |
| 0x08108102 | 2         | 1.09%   |
| 0x0500010d | 2         | 1.09%   |
| 0xa0653    | 1         | 0.54%   |
| 0xa0652    | 1         | 0.54%   |
| 0x906eb    | 1         | 0.54%   |
| 0x706a8    | 1         | 0.54%   |
| 0x706a1    | 1         | 0.54%   |
| 0x6fd      | 1         | 0.54%   |
| 0x406c3    | 1         | 0.54%   |
| 0x306f2    | 1         | 0.54%   |
| 0x10676    | 1         | 0.54%   |
| 0x0a50000c | 1         | 0.54%   |
| 0x0a50000b | 1         | 0.54%   |
| 0x08701013 | 1         | 0.54%   |
| 0x08600103 | 1         | 0.54%   |
| 0x08600102 | 1         | 0.54%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 33        | 18.13%  |
| IvyBridge        | 23        | 12.64%  |
| Haswell          | 18        | 9.89%   |
| Penryn           | 13        | 7.14%   |
| Skylake          | 10        | 5.49%   |
| SandyBridge      | 10        | 5.49%   |
| Broadwell        | 10        | 5.49%   |
| Silvermont       | 9         | 4.95%   |
| Zen 2            | 8         | 4.4%    |
| CometLake        | 7         | 3.85%   |
| Zen              | 5         | 2.75%   |
| Unknown          | 5         | 2.75%   |
| Zen+             | 4         | 2.2%    |
| Goldmont plus    | 4         | 2.2%    |
| Westmere         | 3         | 1.65%   |
| TigerLake        | 3         | 1.65%   |
| Bobcat           | 3         | 1.65%   |
| Zen 3            | 2         | 1.1%    |
| Piledriver       | 2         | 1.1%    |
| Goldmont         | 2         | 1.1%    |
| Excavator        | 2         | 1.1%    |
| Bulldozer        | 2         | 1.1%    |
| Alderlake Hybrid | 2         | 1.1%    |
| Jaguar           | 1         | 0.55%   |
| Core             | 1         | 0.55%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 121       | 53.54%  |
| Nvidia              | 60        | 26.55%  |
| AMD                 | 42        | 18.58%  |
| Zhaoxin             | 1         | 0.44%   |
| Phytium Technology  | 1         | 0.44%   |
| Loongson Technology | 1         | 0.44%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 12        | 5.24%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 4.8%    |
| Intel HD Graphics 5500                                                                   | 9         | 3.93%   |
| Intel HD Graphics 620                                                                    | 8         | 3.49%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8         | 3.49%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 6         | 2.62%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 2.62%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 6         | 2.62%   |
| AMD Renoir                                                                               | 6         | 2.62%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 2.62%   |
| Intel UHD Graphics 620                                                                   | 5         | 2.18%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 2.18%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 2.18%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4         | 1.75%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 1.75%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 3         | 1.31%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 1.31%   |
| Intel HD Graphics 630                                                                    | 3         | 1.31%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.31%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 1.31%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 1.31%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 0.87%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 0.87%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.87%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 0.87%   |
| Nvidia GM108M [GeForce MX110]                                                            | 2         | 0.87%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 2         | 0.87%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.87%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 2         | 0.87%   |
| Nvidia GK107M [GeForce GT 650M]                                                          | 2         | 0.87%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.87%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 2         | 0.87%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 0.87%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 2         | 0.87%   |
| Intel HD Graphics 500                                                                    | 2         | 0.87%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 0.87%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 0.87%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 0.87%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 0.87%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 2         | 0.87%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 78        | 42.86%  |
| Intel + Nvidia          | 34        | 18.68%  |
| 1 x AMD                 | 32        | 17.58%  |
| 1 x Nvidia              | 25        | 13.74%  |
| Intel + AMD             | 7         | 3.85%   |
| 2 x AMD                 | 2         | 1.1%    |
| 1 x Zhaoxin             | 1         | 0.55%   |
| 1 x Phytium Technology  | 1         | 0.55%   |
| 1 x Loongson Technology | 1         | 0.55%   |
| AMD + Nvidia            | 1         | 0.55%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 144       | 79.12%  |
| Proprietary | 27        | 14.84%  |
| Unknown     | 11        | 6.04%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 101       | 54.3%   |
| 1.01-2.0   | 41        | 22.04%  |
| 3.01-4.0   | 20        | 10.75%  |
| 0.01-0.5   | 11        | 5.91%   |
| 0.51-1.0   | 7         | 3.76%   |
| 7.01-8.0   | 3         | 1.61%   |
| 5.01-6.0   | 3         | 1.61%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 28        | 15.22%  |
| Samsung Electronics     | 27        | 14.67%  |
| BOE                     | 26        | 14.13%  |
| Chimei Innolux          | 17        | 9.24%   |
| LG Display              | 16        | 8.7%    |
| Goldstar                | 9         | 4.89%   |
| Hewlett-Packard         | 8         | 4.35%   |
| Lenovo                  | 4         | 2.17%   |
| Dell                    | 4         | 2.17%   |
| CSO                     | 4         | 2.17%   |
| AOC                     | 4         | 2.17%   |
| ViewSonic               | 3         | 1.63%   |
| Iiyama                  | 3         | 1.63%   |
| Ancor Communications    | 3         | 1.63%   |
| Philips                 | 2         | 1.09%   |
| InfoVision              | 2         | 1.09%   |
| Chi Mei Optoelectronics | 2         | 1.09%   |
| BenQ                    | 2         | 1.09%   |
| Acer                    | 2         | 1.09%   |
| Unknown                 | 1         | 0.54%   |
| Toshiba                 | 1         | 0.54%   |
| TFC                     | 1         | 0.54%   |
| SKY                     | 1         | 0.54%   |
| Sharp                   | 1         | 0.54%   |
| SAC                     | 1         | 0.54%   |
| RTK                     | 1         | 0.54%   |
| Positivo                | 1         | 0.54%   |
| PANDA                   | 1         | 0.54%   |
| MSI                     | 1         | 0.54%   |
| Hisense                 | 1         | 0.54%   |
| HB@                     | 1         | 0.54%   |
| HannStar                | 1         | 0.54%   |
| Gateway                 | 1         | 0.54%   |
| DTV                     | 1         | 0.54%   |
| DST                     | 1         | 0.54%   |
| ASUSTek Computer        | 1         | 0.54%   |
| Apple                   | 1         | 0.54%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch           | 3         | 1.57%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch          | 3         | 1.57%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch             | 2         | 1.05%   |
| Goldstar 20EN33 GSM4EE1 1600x900 443x249mm 20.0-inch                    | 2         | 1.05%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch        | 2         | 1.05%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch         | 2         | 1.05%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                    | 2         | 1.05%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch           | 2         | 1.05%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 276x155mm 12.5-inch          | 2         | 1.05%   |
| ViewSonic VX2481-mh VSC3933 1920x1080 527x296mm 23.8-inch               | 1         | 0.52%   |
| ViewSonic VA2478-H-2 VSC8335 1920x1080 527x296mm 23.8-inch              | 1         | 0.52%   |
| ViewSonic VA2430-H-3 VSC3A3E 1920x1080 527x296mm 23.8-inch              | 1         | 0.52%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch               | 1         | 0.52%   |
| Toshiba TV TSB0108 1360x768 580x320mm 26.1-inch                         | 1         | 0.52%   |
| TFC TF2411 TFC0238 1920x1080 527x296mm 23.8-inch                        | 1         | 0.52%   |
| SKY 24X1Q SKY2380 2560x1440 520x290mm 23.4-inch                         | 1         | 0.52%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                 | 1         | 0.52%   |
| Samsung Electronics SyncMaster SAM060B 1920x1080 510x290mm 23.1-inch    | 1         | 0.52%   |
| Samsung Electronics SyncMaster SAM0601 1600x900                         | 1         | 0.52%   |
| Samsung Electronics SyncMaster SAM05FF 1600x900 443x249mm 20.0-inch     | 1         | 0.52%   |
| Samsung Electronics SyncMaster SAM02B6 1920x1200 518x324mm 24.1-inch    | 1         | 0.52%   |
| Samsung Electronics SyncMaster SAM0167 1280x1024 338x270mm 17.0-inch    | 1         | 0.52%   |
| Samsung Electronics SMT24A550 SAM07B5 1920x1080 530x300mm 24.0-inch     | 1         | 0.52%   |
| Samsung Electronics S24E360 SAM0C10 1920x1080 520x290mm 23.4-inch       | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SMS23A350H 1920x1080                    | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch   | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch    | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC384A 1366x768 344x194mm 15.5-inch    | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch    | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch    | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC314B 1600x900 344x194mm 15.5-inch    | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SDC534B 1600x900 382x215mm 17.3-inch    | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch    | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SDC4A42 1366x768 309x174mm 14.0-inch    | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch    | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SDC434A 3200x1800 293x165mm 13.2-inch   | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SDC4147 1366x768 344x194mm 15.5-inch    | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SDC3853 2736x1824 260x173mm 12.3-inch   | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1872x1053mm 84.6-inch | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SAM0E90 1366x768 700x390mm 31.5-inch    | 1         | 0.52%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 77        | 42.78%  |
| 1366x768 (WXGA)    | 55        | 30.56%  |
| 1600x900 (HD+)     | 10        | 5.56%   |
| 2560x1440 (QHD)    | 6         | 3.33%   |
| 3840x2160 (4K)     | 4         | 2.22%   |
| 2560x1600          | 3         | 1.67%   |
| 3840x1080          | 2         | 1.11%   |
| 3000x2000          | 2         | 1.11%   |
| 1920x540           | 2         | 1.11%   |
| 1920x1200 (WUXGA)  | 2         | 1.11%   |
| 1440x900 (WXGA+)   | 2         | 1.11%   |
| 1360x768           | 2         | 1.11%   |
| 1280x1024 (SXGA)   | 2         | 1.11%   |
| Unknown            | 2         | 1.11%   |
| 3440x1440          | 1         | 0.56%   |
| 3200x1800 (QHD+)   | 1         | 0.56%   |
| 2736x1824          | 1         | 0.56%   |
| 2288x1287          | 1         | 0.56%   |
| 2160x1440          | 1         | 0.56%   |
| 2160x1350          | 1         | 0.56%   |
| 1680x945           | 1         | 0.56%   |
| 1680x1050 (WSXGA+) | 1         | 0.56%   |
| 1280x800 (WXGA)    | 1         | 0.56%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 52        | 27.66%  |
| 13      | 27        | 14.36%  |
| 23      | 19        | 10.11%  |
| 14      | 18        | 9.57%   |
| 24      | 9         | 4.79%   |
| 21      | 8         | 4.26%   |
| Unknown | 8         | 4.26%   |
| 27      | 7         | 3.72%   |
| 18      | 7         | 3.72%   |
| 12      | 5         | 2.66%   |
| 17      | 4         | 2.13%   |
| 32      | 3         | 1.6%    |
| 20      | 3         | 1.6%    |
| 11      | 3         | 1.6%    |
| 84      | 2         | 1.06%   |
| 25      | 2         | 1.06%   |
| 19      | 2         | 1.06%   |
| 16      | 2         | 1.06%   |
| 142     | 1         | 0.53%   |
| 72      | 1         | 0.53%   |
| 65      | 1         | 0.53%   |
| 40      | 1         | 0.53%   |
| 31      | 1         | 0.53%   |
| 22      | 1         | 0.53%   |
| 10      | 1         | 0.53%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 88        | 48.09%  |
| 501-600        | 34        | 18.58%  |
| 401-500        | 20        | 10.93%  |
| 201-300        | 18        | 9.84%   |
| Unknown        | 8         | 4.37%   |
| 351-400        | 5         | 2.73%   |
| 701-800        | 3         | 1.64%   |
| 1501-2000      | 3         | 1.64%   |
| More than 2000 | 1         | 0.55%   |
| 801-900        | 1         | 0.55%   |
| 601-700        | 1         | 0.55%   |
| 1001-1500      | 1         | 0.55%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 150       | 86.71%  |
| 16/10   | 10        | 5.78%   |
| Unknown | 6         | 3.47%   |
| 3/2     | 5         | 2.89%   |
| 5/4     | 1         | 0.58%   |
| 1.00    | 1         | 0.58%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 52        | 27.66%  |
| 81-90          | 37        | 19.68%  |
| 201-250        | 31        | 16.49%  |
| 151-200        | 9         | 4.79%   |
| 71-80          | 8         | 4.26%   |
| Unknown        | 8         | 4.26%   |
| 301-350        | 7         | 3.72%   |
| 141-150        | 7         | 3.72%   |
| More than 1000 | 5         | 2.66%   |
| 61-70          | 5         | 2.66%   |
| 251-300        | 5         | 2.66%   |
| 351-500        | 4         | 2.13%   |
| 51-60          | 3         | 1.6%    |
| 121-130        | 2         | 1.06%   |
| 111-120        | 2         | 1.06%   |
| 41-50          | 1         | 0.53%   |
| 131-140        | 1         | 0.53%   |
| 501-1000       | 1         | 0.53%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 64        | 34.97%  |
| 51-100        | 49        | 26.78%  |
| 121-160       | 42        | 22.95%  |
| 161-240       | 12        | 6.56%   |
| Unknown       | 8         | 4.37%   |
| More than 240 | 4         | 2.19%   |
| 1-50          | 4         | 2.19%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 151       | 82.51%  |
| 2     | 25        | 13.66%  |
| 0     | 6         | 3.28%   |
| 3     | 1         | 0.55%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 120       | 44.78%  |
| Intel                           | 64        | 23.88%  |
| Qualcomm Atheros                | 41        | 15.3%   |
| Broadcom                        | 7         | 2.61%   |
| Marvell Technology Group        | 5         | 1.87%   |
| Xiaomi                          | 4         | 1.49%   |
| MediaTek                        | 4         | 1.49%   |
| TP-Link                         | 3         | 1.12%   |
| Broadcom Limited                | 3         | 1.12%   |
| Ralink                          | 2         | 0.75%   |
| Nvidia                          | 2         | 0.75%   |
| Unknown                         | 1         | 0.37%   |
| Samsung Electronics             | 1         | 0.37%   |
| Ralink Technology               | 1         | 0.37%   |
| Qualcomm Atheros Communications | 1         | 0.37%   |
| OPPO Electronics                | 1         | 0.37%   |
| NXP Semiconductors              | 1         | 0.37%   |
| NetGear                         | 1         | 0.37%   |
| Loongson Technology             | 1         | 0.37%   |
| IMC Networks                    | 1         | 0.37%   |
| Huawei Technologies             | 1         | 0.37%   |
| Hewlett-Packard                 | 1         | 0.37%   |
| ASIX Electronics                | 1         | 0.37%   |
| Aquantia                        | 1         | 0.37%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 84        | 27.36%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 20        | 6.51%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 14        | 4.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 7         | 2.28%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 7         | 2.28%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 7         | 2.28%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 1.95%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 1.63%   |
| Intel Wireless 3165                                               | 5         | 1.63%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 1.63%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 1.3%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 4         | 1.3%    |
| Intel Wireless 8265 / 8275                                        | 4         | 1.3%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 1.3%    |
| Realtek RTL8723DE Wireless Network Adapter                        | 3         | 0.98%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 3         | 0.98%   |
| Intel Wireless 7260                                               | 3         | 0.98%   |
| Intel Wireless 3160                                               | 3         | 0.98%   |
| Intel WiFi Link 5100                                              | 3         | 0.98%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 0.98%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 0.98%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 0.98%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.65%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.65%   |
| Realtek RTL8191SEvA Wireless LAN Controller                       | 2         | 0.65%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 0.65%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.65%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.65%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 2         | 0.65%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 2         | 0.65%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 0.65%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 0.65%   |
| Intel Wireless 7265                                               | 2         | 0.65%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 0.65%   |
| Intel Ethernet Connection (12) I219-V                             | 2         | 0.65%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 2         | 0.65%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 0.65%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 2         | 0.65%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 0.65%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 52        | 35.62%  |
| Qualcomm Atheros                | 39        | 26.71%  |
| Realtek Semiconductor           | 35        | 23.97%  |
| TP-Link                         | 3         | 2.05%   |
| MediaTek                        | 3         | 2.05%   |
| Broadcom Limited                | 3         | 2.05%   |
| Ralink                          | 2         | 1.37%   |
| Broadcom                        | 2         | 1.37%   |
| Xiaomi                          | 1         | 0.68%   |
| Ralink Technology               | 1         | 0.68%   |
| Qualcomm Atheros Communications | 1         | 0.68%   |
| NetGear                         | 1         | 0.68%   |
| Marvell Technology Group        | 1         | 0.68%   |
| IMC Networks                    | 1         | 0.68%   |
| Hewlett-Packard                 | 1         | 0.68%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 14        | 9.52%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 7         | 4.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 7         | 4.76%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 7         | 4.76%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 5         | 3.4%    |
| Intel Wireless 3165                                            | 5         | 3.4%    |
| Intel Wi-Fi 6 AX200                                            | 5         | 3.4%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 4         | 2.72%   |
| Intel Wireless 8265 / 8275                                     | 4         | 2.72%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 2.72%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 3         | 2.04%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 3         | 2.04%   |
| Intel Wireless 7260                                            | 3         | 2.04%   |
| Intel Wireless 3160                                            | 3         | 2.04%   |
| Intel WiFi Link 5100                                           | 3         | 2.04%   |
| Intel Wi-Fi 6 AX201                                            | 3         | 2.04%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 3         | 2.04%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 3         | 2.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.36%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.36%   |
| Realtek RTL8191SEvA Wireless LAN Controller                    | 2         | 1.36%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 1.36%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 1.36%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 1.36%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 2         | 1.36%   |
| Intel Wireless 7265                                            | 2         | 1.36%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 2         | 1.36%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 1.36%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 2         | 1.36%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 1.36%   |
| Xiaomi MediaTek MT7601U [MI WiFi]                              | 1         | 0.68%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1         | 0.68%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 1         | 0.68%   |
| TP-Link 802.11ac WLAN Adapter                                  | 1         | 0.68%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 0.68%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 0.68%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 1         | 0.68%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1         | 0.68%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 0.68%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)      | 1         | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 110       | 70.06%  |
| Intel                    | 21        | 13.38%  |
| Qualcomm Atheros         | 5         | 3.18%   |
| Broadcom                 | 5         | 3.18%   |
| Marvell Technology Group | 4         | 2.55%   |
| Xiaomi                   | 3         | 1.91%   |
| Nvidia                   | 2         | 1.27%   |
| Samsung Electronics      | 1         | 0.64%   |
| OPPO Electronics         | 1         | 0.64%   |
| MediaTek                 | 1         | 0.64%   |
| Loongson Technology      | 1         | 0.64%   |
| Huawei Technologies      | 1         | 0.64%   |
| ASIX Electronics         | 1         | 0.64%   |
| Aquantia                 | 1         | 0.64%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 84        | 53.16%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 20        | 12.66%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 3.8%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 2.53%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 1.27%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 1.27%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 1.27%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 1.27%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 1.27%   |
| Intel Ethernet Connection (12) I219-V                             | 2         | 1.27%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 1.27%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 1.27%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 2         | 1.27%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.63%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.63%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.63%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.63%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.63%   |
| OPPO SDM665-IDP _SN:18689828                                      | 1         | 0.63%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.63%   |
| Nvidia MCP61 Ethernet                                             | 1         | 0.63%   |
| MediaTek N152DL                                                   | 1         | 0.63%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 0.63%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 0.63%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1         | 0.63%   |
| Loongson Gigabit Ethernet Controller                              | 1         | 0.63%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.63%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.63%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.63%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.63%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.63%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.63%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.63%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 0.63%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 0.63%   |
| Huawei SNE-LX1                                                    | 1         | 0.63%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                   | 1         | 0.63%   |
| ASIX AX88772A Fast Ethernet                                       | 1         | 0.63%   |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 0.63%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 148       | 50.86%  |
| WiFi     | 141       | 48.45%  |
| Modem    | 1         | 0.34%   |
| Unknown  | 1         | 0.34%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 111       | 62.01%  |
| Ethernet | 68        | 37.99%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 100       | 54.64%  |
| 1     | 75        | 40.98%  |
| 0     | 6         | 3.28%   |
| 3     | 2         | 1.09%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 175       | 95.63%  |
| Yes  | 8         | 4.37%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 42        | 35%     |
| Qualcomm Atheros Communications | 23        | 19.17%  |
| Realtek Semiconductor           | 13        | 10.83%  |
| Cambridge Silicon Radio         | 11        | 9.17%   |
| Foxconn / Hon Hai               | 6         | 5%      |
| Broadcom                        | 6         | 5%      |
| Realtek                         | 4         | 3.33%   |
| IMC Networks                    | 4         | 3.33%   |
| Lite-On Technology              | 3         | 2.5%    |
| Toshiba                         | 1         | 0.83%   |
| Ralink Technology               | 1         | 0.83%   |
| MediaTek                        | 1         | 0.83%   |
| Marvell Semiconductor           | 1         | 0.83%   |
| Dynex                           | 1         | 0.83%   |
| Dell                            | 1         | 0.83%   |
| ASUSTek Computer                | 1         | 0.83%   |
| Apple                           | 1         | 0.83%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 20        | 16.67%  |
| Qualcomm Atheros  Bluetooth Device                                                  | 16        | 13.33%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 11        | 9.17%   |
| Intel AX201 Bluetooth                                                               | 7         | 5.83%   |
| Realtek Bluetooth Radio                                                             | 6         | 5%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 6         | 5%      |
| Realtek  Bluetooth 4.2 Adapter                                                      | 5         | 4.17%   |
| Intel AX200 Bluetooth                                                               | 5         | 4.17%   |
| Realtek Bluetooth Radio                                                             | 4         | 3.33%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 4         | 3.33%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 2.5%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 1.67%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 2         | 1.67%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.67%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 2         | 1.67%   |
| IMC Networks Bluetooth Device                                                       | 2         | 1.67%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 1.67%   |
| Broadcom HP Portable SoftSailing                                                    | 2         | 1.67%   |
| Toshiba Bluetooth Radio                                                             | 1         | 0.83%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.83%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.83%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 1         | 0.83%   |
| MediaTek BT                                                                         | 1         | 0.83%   |
| Marvell Bluetooth and Wireless LAN Composite                                        | 1         | 0.83%   |
| Lite-On Bluetooth Device                                                            | 1         | 0.83%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 0.83%   |
| Intel Bluetooth Device                                                              | 1         | 0.83%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.83%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.83%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.83%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.83%   |
| Foxconn / Hon Hai BCM43142A0                                                        | 1         | 0.83%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 0.83%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]                            | 1         | 0.83%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.83%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 1         | 0.83%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 1         | 0.83%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 141       | 61.84%  |
| AMD                                          | 42        | 18.42%  |
| Nvidia                                       | 33        | 14.47%  |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 0.88%   |
| C-Media Electronics                          | 2         | 0.88%   |
| Zhaoxin                                      | 1         | 0.44%   |
| XMOS                                         | 1         | 0.44%   |
| Phytium Technology                           | 1         | 0.44%   |
| Microdia                                     | 1         | 0.44%   |
| Loongson Technology                          | 1         | 0.44%   |
| JMTek                                        | 1         | 0.44%   |
| Creative Technology                          | 1         | 0.44%   |
| BEHRINGER International                      | 1         | 0.44%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 21        | 7.61%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 19        | 6.88%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 15        | 5.43%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 14        | 5.07%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 11        | 3.99%   |
| Intel 8 Series HD Audio Controller                                                                | 11        | 3.99%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 10        | 3.62%   |
| Intel Broadwell-U Audio Controller                                                                | 10        | 3.62%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 7         | 2.54%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 7         | 2.54%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 2.54%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 2.17%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 2.17%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 5         | 1.81%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 1.81%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 1.81%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1.45%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 1.45%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 1.45%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 4         | 1.45%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 1.09%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 3         | 1.09%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 1.09%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 3         | 1.09%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 1.09%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 1.09%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 1.09%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1.09%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 1.09%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 1.09%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 1.09%   |
| AMD FCH Azalia Controller                                                                         | 3         | 1.09%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3         | 1.09%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                                    | 2         | 0.72%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 0.72%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.72%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.72%   |
| Nvidia Audio device                                                                               | 2         | 0.72%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 0.72%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 25        | 22.73%  |
| SK hynix            | 20        | 18.18%  |
| Unknown             | 16        | 14.55%  |
| Kingston            | 13        | 11.82%  |
| Micron Technology   | 7         | 6.36%   |
| Smart               | 4         | 3.64%   |
| Nanya Technology    | 4         | 3.64%   |
| Ramaxel Technology  | 3         | 2.73%   |
| Corsair             | 3         | 2.73%   |
| A-DATA Technology   | 3         | 2.73%   |
| G.Skill             | 2         | 1.82%   |
| Crucial             | 2         | 1.82%   |
| Unknown (07FB)      | 1         | 0.91%   |
| Team                | 1         | 0.91%   |
| Smart Brazil        | 1         | 0.91%   |
| MTASE               | 1         | 0.91%   |
| JEDEC ID: 0000h     | 1         | 0.91%   |
| CSX                 | 1         | 0.91%   |
| ChangXin Memory     | 1         | 0.91%   |
| Apacer              | 1         | 0.91%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                  | 2         | 1.69%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s           | 2         | 1.69%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2133MT/s                 | 2         | 1.69%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s          | 2         | 1.69%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB Row Of Chips DDR4 2667MT/s    | 2         | 1.69%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s          | 2         | 1.69%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s           | 2         | 1.69%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s           | 2         | 1.69%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s            | 2         | 1.69%   |
| Kingston RAM TF32D4U2S1MEH-8 8GB DIMM DDR4 3200MT/s             | 2         | 1.69%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 0.85%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                       | 1         | 0.85%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                  | 1         | 0.85%   |
| Unknown RAM Module 4GB SODIMM LPDDR3 1600MT/s                   | 1         | 0.85%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2667MT/s                  | 1         | 0.85%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                  | 1         | 0.85%   |
| Unknown RAM Module 4096MB SODIMM DDR3                           | 1         | 0.85%   |
| Unknown RAM Module 4096MB DIMM DDR3 1067MT/s                    | 1         | 0.85%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                          | 1         | 0.85%   |
| Unknown RAM Module 2GB DIMM SDRAM                               | 1         | 0.85%   |
| Unknown RAM Module 2048MB SODIMM LPDDR3 1600MT/s                | 1         | 0.85%   |
| Unknown RAM Module 2048MB SODIMM DDR3                           | 1         | 0.85%   |
| Unknown RAM Module 2048MB SODIMM DDR2                           | 1         | 0.85%   |
| Unknown RAM Module 2048MB Chip DDR3 1066MT/s                    | 1         | 0.85%   |
| Unknown RAM Module 1024MB SODIMM LPDDR4 2400MT/s                | 1         | 0.85%   |
| Unknown RAM Module 1024MB SODIMM DDR2                           | 1         | 0.85%   |
| Unknown RAM 1866 CL10 Ser 8192MB DIMM DDR3 800MT/s              | 1         | 0.85%   |
| Unknown (07FB) RAM GST32G08SCL196P-26 32GB SODIMM DDR4 2667MT/s | 1         | 0.85%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s             | 1         | 0.85%   |
| Smart RAM SH564568FJ8NZRNSDR 2GB SODIMM DDR3 1600MT/s           | 1         | 0.85%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s           | 1         | 0.85%   |
| Smart RAM SG564568FG8NWKF-Z1 2GB SODIMM DDR2 800MT/s            | 1         | 0.85%   |
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s    | 1         | 0.85%   |
| SK hynix RAM MPPS4GBPC1600 1.35 4096MB SODIMM DDR3 1600MT/s     | 1         | 0.85%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1066MT/s                    | 1         | 0.85%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 0.85%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 0.85%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s          | 1         | 0.85%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s    | 1         | 0.85%   |
| SK hynix RAM HMA851S6DJR6N-XN 4096MB Row Of Chips DDR4 3200MT/s | 1         | 0.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 51        | 52.04%  |
| DDR3    | 31        | 31.63%  |
| LPDDR3  | 6         | 6.12%   |
| LPDDR4  | 4         | 4.08%   |
| SDRAM   | 2         | 2.04%   |
| DDR2    | 2         | 2.04%   |
| DDR5    | 1         | 1.02%   |
| Unknown | 1         | 1.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 64        | 64.65%  |
| DIMM         | 23        | 23.23%  |
| Row Of Chips | 10        | 10.1%   |
| Chip         | 1         | 1.01%   |
| Unknown      | 1         | 1.01%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 43        | 41.35%  |
| 4096  | 34        | 32.69%  |
| 2048  | 14        | 13.46%  |
| 16384 | 8         | 7.69%   |
| 1024  | 3         | 2.88%   |
| 32768 | 2         | 1.92%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 20        | 19.42%  |
| 2667    | 19        | 18.45%  |
| 3200    | 11        | 10.68%  |
| 2133    | 7         | 6.8%    |
| 2400    | 6         | 5.83%   |
| 1867    | 5         | 4.85%   |
| 1333    | 5         | 4.85%   |
| 1334    | 3         | 2.91%   |
| 1066    | 3         | 2.91%   |
| Unknown | 3         | 2.91%   |
| 3466    | 2         | 1.94%   |
| 3400    | 2         | 1.94%   |
| 3266    | 2         | 1.94%   |
| 2666    | 2         | 1.94%   |
| 4800    | 1         | 0.97%   |
| 4267    | 1         | 0.97%   |
| 4266    | 1         | 0.97%   |
| 4199    | 1         | 0.97%   |
| 3800    | 1         | 0.97%   |
| 3733    | 1         | 0.97%   |
| 3500    | 1         | 0.97%   |
| 3000    | 1         | 0.97%   |
| 2933    | 1         | 0.97%   |
| 2800    | 1         | 0.97%   |
| 1067    | 1         | 0.97%   |
| 800     | 1         | 0.97%   |
| 667     | 1         | 0.97%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson ME 340 Series/Stylus NX130 Series | 1         | 100%    |

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
| Chicony Electronics                    | 30        | 25.42%  |
| Realtek Semiconductor                  | 11        | 9.32%   |
| IMC Networks                           | 11        | 9.32%   |
| Microdia                               | 9         | 7.63%   |
| Silicon Motion                         | 7         | 5.93%   |
| Syntek                                 | 6         | 5.08%   |
| Sunplus Innovation Technology          | 6         | 5.08%   |
| Suyin                                  | 5         | 4.24%   |
| Quanta                                 | 5         | 4.24%   |
| Logitech                               | 5         | 4.24%   |
| Acer                                   | 4         | 3.39%   |
| Lite-On Technology                     | 3         | 2.54%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 2.54%   |
| Ricoh                                  | 2         | 1.69%   |
| Primax Electronics                     | 2         | 1.69%   |
| Alcor Micro                            | 2         | 1.69%   |
| LG Electronics                         | 1         | 0.85%   |
| Lenovo                                 | 1         | 0.85%   |
| Goodong Industry                       | 1         | 0.85%   |
| Generalplus Technology                 | 1         | 0.85%   |
| Arkmicro Technologies                  | 1         | 0.85%   |
| Apple                                  | 1         | 0.85%   |
| 2M UVC CAMERA                          | 1         | 0.85%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 7         | 5.93%   |
| IMC Networks Integrated Camera           | 5         | 4.24%   |
| Chicony EasyCamera                       | 4         | 3.39%   |
| Syntek EasyCamera                        | 3         | 2.54%   |
| Silicon Motion Web Camera                | 3         | 2.54%   |
| Logitech Webcam C270                     | 3         | 2.54%   |
| IMC Networks ov9734_azurewave_camera     | 3         | 2.54%   |
| Chicony TOSHIBA Web Camera - HD          | 3         | 2.54%   |
| Syntek Integrated Camera                 | 2         | 1.69%   |
| Sunplus HD WebCam                        | 2         | 1.69%   |
| Realtek Integrated_Webcam_HD             | 2         | 1.69%   |
| Realtek HP "Truevision HD" laptop camera | 2         | 1.69%   |
| Quanta HP TrueVision HD Camera           | 2         | 1.69%   |
| Quanta HD User Facing                    | 2         | 1.69%   |
| Primax HP HD Webcam [Fixed]              | 2         | 1.69%   |
| Microdia Integrated_Webcam_HD            | 2         | 1.69%   |
| Chicony HP Webcam                        | 2         | 1.69%   |
| Chicony HP HD Webcam                     | 2         | 1.69%   |
| Acer Integrated Camera                   | 2         | 1.69%   |
| Syntek Lenovo EasyCamera                 | 1         | 0.85%   |
| Suyin Integrated_Webcam_HD               | 1         | 0.85%   |
| Suyin HP Truevision HD                   | 1         | 0.85%   |
| Suyin HD WebCam                          | 1         | 0.85%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 1         | 0.85%   |
| Suyin 1.3M HD WebCam                     | 1         | 0.85%   |
| Sunplus XiaoMi USB 2.0 Webcam            | 1         | 0.85%   |
| Sunplus Integrated_Webcam_HD             | 1         | 0.85%   |
| Sunplus HP Wide Vision HD                | 1         | 0.85%   |
| Sunplus Asus Webcam                      | 1         | 0.85%   |
| Silicon Motion WebCam SC-13HDL11939N     | 1         | 0.85%   |
| Silicon Motion WebCam SC-10IRQ12340N     | 1         | 0.85%   |
| Silicon Motion WebCam SC-0311139N        | 1         | 0.85%   |
| Silicon Motion ATIV VGA Camera           | 1         | 0.85%   |
| Ricoh Sony Vaio Integrated Webcam        | 1         | 0.85%   |
| Ricoh Laptop_Integrated_Webcam_FHD       | 1         | 0.85%   |
| Realtek USB Camera                       | 1         | 0.85%   |
| Realtek Lenovo easy camera               | 1         | 0.85%   |
| Realtek Laptop_Integrated_Webcam_HD      | 1         | 0.85%   |
| Realtek Integrated_Webcam_FHD            | 1         | 0.85%   |
| Realtek HP Wide Vision HD Camera         | 1         | 0.85%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 10        | 41.67%  |
| Shenzhen Goodix Technology | 8         | 33.33%  |
| Upek                       | 5         | 20.83%  |
| Elan Microelectronics      | 1         | 4.17%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 5         | 20.83%  |
| Shenzhen Goodix  Fingerprint Device                    | 5         | 20.83%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 3         | 12.5%   |
| Shenzhen Goodix Fingerprint Reader                     | 3         | 12.5%   |
| Validity Sensors VFS491                                | 2         | 8.33%   |
| Validity Sensors Swipe Fingerprint Sensor              | 2         | 8.33%   |
| Upek TCS5B Fingerprint sensor                          | 2         | 8.33%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 4.17%   |
| Elan ELAN:Fingerprint                                  | 1         | 4.17%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Alcor Micro         | 2         | 40%     |
| Lenovo              | 1         | 20%     |
| Giesecke & Devrient | 1         | 20%     |
| Broadcom            | 1         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader            | 2         | 40%     |
| Lenovo Integrated Smart Card Reader            | 1         | 20%     |
| Giesecke & Devrient StarSign CUT               | 1         | 20%     |
| Broadcom BCM5880 Secure Applications Processor | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 131       | 71.2%   |
| 1     | 43        | 23.37%  |
| 2     | 9         | 4.89%   |
| 3     | 1         | 0.54%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 24        | 38.1%   |
| Graphics card            | 19        | 30.16%  |
| Multimedia controller    | 5         | 7.94%   |
| Chipcard                 | 5         | 7.94%   |
| Sound                    | 3         | 4.76%   |
| Net/wireless             | 3         | 4.76%   |
| Unassigned class         | 1         | 1.59%   |
| Storage                  | 1         | 1.59%   |
| Communication controller | 1         | 1.59%   |
| Camera                   | 1         | 1.59%   |

