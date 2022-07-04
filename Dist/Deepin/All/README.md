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

Total: 255

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| Deepin         | 47        | 25.54%  |
| Deepin 20      | 31        | 16.85%  |
| Deepin 15.11   | 27        | 14.67%  |
| UOS 20         | 16        | 8.7%    |
| Deepin 15.9.2  | 12        | 6.52%   |
| Deepin 20.3    | 7         | 3.8%    |
| Deepin 20.1    | 7         | 3.8%    |
| Deepin 20 beta | 7         | 3.8%    |
| Deepin 20.5    | 4         | 2.17%   |
| Deepin 23      | 3         | 1.63%   |
| Deepin 20.2.4  | 3         | 1.63%   |
| Deepin 20.2.3  | 3         | 1.63%   |
| Deepin 20.2.2  | 3         | 1.63%   |
| Deepin 15.10.1 | 3         | 1.63%   |
| Deepin 15.9.3  | 2         | 1.09%   |
| Deepin 2014.3  | 1         | 0.54%   |
| Deepin 20.6    | 1         | 0.54%   |
| Deepin 20.4    | 1         | 0.54%   |
| Deepin 20.2.1  | 1         | 0.54%   |
| Deepin 20.2    | 1         | 0.54%   |
| Deepin 15.9    | 1         | 0.54%   |
| Deepin 15.8    | 1         | 0.54%   |
| Deepin 15.7    | 1         | 0.54%   |
| Deepin 15.10   | 1         | 0.54%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Deepin | 175       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 4.15.0-30deepin-generic      | 41        | 22.4%   |
| 5.4.50-amd64-desktop         | 22        | 12.02%  |
| 4.15.0-29deepin-generic      | 19        | 10.38%  |
| 5.4.70-amd64-desktop         | 16        | 8.74%   |
| 5.10.60-amd64-desktop        | 12        | 6.56%   |
| 5.3.0-3-amd64                | 10        | 5.46%   |
| 5.7.7-amd64-desktop          | 6         | 3.28%   |
| 5.10.29-amd64-desktop        | 6         | 3.28%   |
| 5.10.41-amd64-desktop        | 5         | 2.73%   |
| 5.10.36-amd64-desktop        | 5         | 2.73%   |
| 5.10.18-amd64-desktop        | 4         | 2.19%   |
| 5.15.24-amd64-desktop        | 3         | 1.64%   |
| 5.15.1-amd64-desktop         | 3         | 1.64%   |
| 5.10.50-amd64-desktop        | 3         | 1.64%   |
| 5.10.5-amd64-desktop+        | 3         | 1.64%   |
| 4.19.0-amd64-desktop         | 3         | 1.64%   |
| 5.8.14-amd64-desktop         | 2         | 1.09%   |
| 5.5.4-xanmod3                | 2         | 1.09%   |
| 5.10.83-amd64-desktop        | 2         | 1.09%   |
| 5.10.101-amd64-desktop       | 2         | 1.09%   |
| 5.6.14-050614-generic        | 1         | 0.55%   |
| 5.6.12-xanmod1               | 1         | 0.55%   |
| 5.4.2-xanmod2                | 1         | 0.55%   |
| 5.3.8-xanmod6                | 1         | 0.55%   |
| 5.2.14-050214-lowlatency     | 1         | 0.55%   |
| 5.14.0-rc3-amd64-desktop     | 1         | 0.55%   |
| 5.12.18-amd64-desktop        | 1         | 0.55%   |
| 5.10.0-amd64-desktop         | 1         | 0.55%   |
| 5.10.0-11-arm64              | 1         | 0.55%   |
| 5.1.15-surface-linux-surface | 1         | 0.55%   |
| 5.1.0-050100rc2-generic      | 1         | 0.55%   |
| 4.19.90-1.lns7.2.mips64el    | 1         | 0.55%   |
| 4.19.0-5-amd64               | 1         | 0.55%   |
| 4.15.0-135-generic           | 1         | 0.55%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 4.15.0   | 61        | 33.33%  |
| 5.4.50   | 22        | 12.02%  |
| 5.4.70   | 16        | 8.74%   |
| 5.10.60  | 12        | 6.56%   |
| 5.3.0    | 10        | 5.46%   |
| 5.7.7    | 6         | 3.28%   |
| 5.10.29  | 6         | 3.28%   |
| 5.10.41  | 5         | 2.73%   |
| 5.10.36  | 5         | 2.73%   |
| 5.10.18  | 4         | 2.19%   |
| 4.19.0   | 4         | 2.19%   |
| 5.15.24  | 3         | 1.64%   |
| 5.15.1   | 3         | 1.64%   |
| 5.10.50  | 3         | 1.64%   |
| 5.10.5   | 3         | 1.64%   |
| 5.8.14   | 2         | 1.09%   |
| 5.5.4    | 2         | 1.09%   |
| 5.10.83  | 2         | 1.09%   |
| 5.10.101 | 2         | 1.09%   |
| 5.10.0   | 2         | 1.09%   |
| 5.6.14   | 1         | 0.55%   |
| 5.6.12   | 1         | 0.55%   |
| 5.4.2    | 1         | 0.55%   |
| 5.3.8    | 1         | 0.55%   |
| 5.2.14   | 1         | 0.55%   |
| 5.14.0   | 1         | 0.55%   |
| 5.12.18  | 1         | 0.55%   |
| 5.1.15   | 1         | 0.55%   |
| 5.1.0    | 1         | 0.55%   |
| 4.19.90  | 1         | 0.55%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.15    | 61        | 34.08%  |
| 5.10    | 42        | 23.46%  |
| 5.4     | 38        | 21.23%  |
| 5.3     | 11        | 6.15%   |
| 5.7     | 6         | 3.35%   |
| 5.15    | 5         | 2.79%   |
| 4.19    | 5         | 2.79%   |
| 5.8     | 2         | 1.12%   |
| 5.6     | 2         | 1.12%   |
| 5.5     | 2         | 1.12%   |
| 5.1     | 2         | 1.12%   |
| 5.2     | 1         | 0.56%   |
| 5.14    | 1         | 0.56%   |
| 5.12    | 1         | 0.56%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 173       | 98.86%  |
| mips64  | 1         | 0.57%   |
| aarch64 | 1         | 0.57%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Deepin  | 146       | 82.95%  |
| Unknown | 27        | 15.34%  |
| MATE    | 1         | 0.57%   |
| KDE5    | 1         | 0.57%   |
| KDE     | 1         | 0.57%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 173       | 98.86%  |
| Tty  | 2         | 1.14%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 87        | 49.15%  |
| TDM     | 53        | 29.94%  |
| LightDM | 37        | 20.9%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 38        | 21.47%  |
| en_US   | 36        | 20.34%  |
| pt_BR   | 24        | 13.56%  |
| zh_CN   | 23        | 12.99%  |
| es_ES   | 20        | 11.3%   |
| de_DE   | 12        | 6.78%   |
| ru_RU   | 7         | 3.95%   |
| pl_PL   | 3         | 1.69%   |
| it_IT   | 3         | 1.69%   |
| en_GB   | 3         | 1.69%   |
| tr_TR   | 2         | 1.13%   |
| fr_FR   | 2         | 1.13%   |
| sv_SE   | 1         | 0.56%   |
| lt_LT   | 1         | 0.56%   |
| ja_JP   | 1         | 0.56%   |
| id_ID   | 1         | 0.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 96        | 54.55%  |
| BIOS | 80        | 45.45%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 157       | 89.71%  |
| Unknown | 18        | 10.29%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 84        | 47.19%  |
| GPT     | 74        | 41.57%  |
| MBR     | 20        | 11.24%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 143       | 80.79%  |
| Yes       | 34        | 19.21%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 132       | 74.58%  |
| Yes       | 45        | 25.42%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Lenovo                     | 34        | 19.43%  |
| Hewlett-Packard            | 22        | 12.57%  |
| ASUSTek Computer           | 21        | 12%     |
| Dell                       | 15        | 8.57%   |
| Acer                       | 13        | 7.43%   |
| Gigabyte Technology        | 9         | 5.14%   |
| Samsung Electronics        | 8         | 4.57%   |
| Sony                       | 5         | 2.86%   |
| TSINGHUA TONGFANG COMPUTER | 4         | 2.29%   |
| Toshiba                    | 4         | 2.29%   |
| HUAWEI                     | 4         | 2.29%   |
| ASRock                     | 4         | 2.29%   |
| Positivo                   | 3         | 1.71%   |
| MSI                        | 3         | 1.71%   |
| Semp Toshiba               | 2         | 1.14%   |
| Google                     | 2         | 1.14%   |
| ECS                        | 2         | 1.14%   |
| Unknown                    | 2         | 1.14%   |
| Timi                       | 1         | 0.57%   |
| Standard                   | 1         | 0.57%   |
| Soyo                       | 1         | 0.57%   |
| Microtech                  | 1         | 0.57%   |
| Microsoft                  | 1         | 0.57%   |
| Medion                     | 1         | 0.57%   |
| Loongson                   | 1         | 0.57%   |
| Huanan                     | 1         | 0.57%   |
| HANWEI                     | 1         | 0.57%   |
| Gateway                    | 1         | 0.57%   |
| Fujitsu                    | 1         | 0.57%   |
| Foxconn                    | 1         | 0.57%   |
| Cube                       | 1         | 0.57%   |
| Chuwi                      | 1         | 0.57%   |
| CCE                        | 1         | 0.57%   |
| BQ                         | 1         | 0.57%   |
| Apple                      | 1         | 0.57%   |
| AMD                        | 1         | 0.57%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| TSINGHUA TONGFANG COMPUTER E500                   | 4         | 2.29%   |
| Unknown                                           | 4         | 2.29%   |
| Semp Toshiba STI                                  | 2         | 1.14%   |
| Samsung 340XAA/350XAA/550XAA                      | 2         | 1.14%   |
| Lenovo IdeaPad 120S-11IAP 81A4                    | 2         | 1.14%   |
| HP Pavilion Notebook                              | 2         | 1.14%   |
| HP Pavilion 15                                    | 2         | 1.14%   |
| HP ENVY 15                                        | 2         | 1.14%   |
| ECS H81H3-M4                                      | 2         | 1.14%   |
| ASUS All Series                                   | 2         | 1.14%   |
| Acer Nitro AN515-54                               | 2         | 1.14%   |
| Toshiba Satellite L75-C                           | 1         | 0.57%   |
| Toshiba Satellite E55t-A                          | 1         | 0.57%   |
| Toshiba Satellite C850D-11K                       | 1         | 0.57%   |
| Toshiba Satellite C850-1H6                        | 1         | 0.57%   |
| Timi TM1701                                       | 1         | 0.57%   |
| Standard MB45II/MB45IN                            | 1         | 0.57%   |
| Soyo SY-Thin Mini H110                            | 1         | 0.57%   |
| Sony VPCYB25AB                                    | 1         | 0.57%   |
| Sony VGN-NS140D                                   | 1         | 0.57%   |
| Sony VGN-AW11Z_B                                  | 1         | 0.57%   |
| Sony SVF14A190X                                   | 1         | 0.57%   |
| Sony SVE14135CXP                                  | 1         | 0.57%   |
| Samsung P500A2D                                   | 1         | 0.57%   |
| Samsung 800G5M/800G5W                             | 1         | 0.57%   |
| Samsung 550P5C/550P7C                             | 1         | 0.57%   |
| Samsung 500R4K/500R5H/5400RK/501R5H/5500RH/500R5S | 1         | 0.57%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA        | 1         | 0.57%   |
| Samsung 270E5J/2570EJ                             | 1         | 0.57%   |
| Positivo POS-PQ45AU                               | 1         | 0.57%   |
| Positivo POS-EINM70CS                             | 1         | 0.57%   |
| Positivo C14CU51                                  | 1         | 0.57%   |
| MSI MS-7C83                                       | 1         | 0.57%   |
| MSI MS-7851                                       | 1         | 0.57%   |
| MSI MS-7681                                       | 1         | 0.57%   |
| Microtech ebookPro                                | 1         | 0.57%   |
| Microsoft Surface Pro 4                           | 1         | 0.57%   |
| Medion MS-7728                                    | 1         | 0.57%   |
| Loongson LS3A3000-7A1000-1w-V1.2-Dev              | 1         | 0.57%   |
| Lenovo ZHAOYANG K4e-ITL 82F8                      | 1         | 0.57%   |
| Lenovo ZHAOYANG CF4620Z-A123 59082537             | 1         | 0.57%   |
| Lenovo Yoga DuetITL 2021 82MA                     | 1         | 0.57%   |
| Lenovo Yoga 3 Pro-1370 80HE                       | 1         | 0.57%   |
| Lenovo XiaoXinAir-14ARE 2020 81YN                 | 1         | 0.57%   |
| Lenovo XiaoXin-15ARE 2020 81YR                    | 1         | 0.57%   |
| Lenovo V310-15ISK 80SY                            | 1         | 0.57%   |
| Lenovo ThinkPad T420 4236CU8                      | 1         | 0.57%   |
| Lenovo ThinkPad T420 4180M8P                      | 1         | 0.57%   |
| Lenovo ThinkPad L512 44444NG                      | 1         | 0.57%   |
| Lenovo ThinkPad L412 0585AC3                      | 1         | 0.57%   |
| Lenovo ThinkPad E585 20KV0010US                   | 1         | 0.57%   |
| Lenovo ThinkPad E450c 20EHA00NCD                  | 1         | 0.57%   |
| Lenovo ThinkPad E14 20RA0058VA                    | 1         | 0.57%   |
| Lenovo ThinkCentre M910t-N000 10N9CTO1WW          | 1         | 0.57%   |
| Lenovo ThinkCentre M82 2929AJ2                    | 1         | 0.57%   |
| Lenovo ThinkBook 14 G2 ARE R7 8 20VF              | 1         | 0.57%   |
| Lenovo ThinkBook 13s-IWL 20R9                     | 1         | 0.57%   |
| Lenovo Legion Y7000 81FW                          | 1         | 0.57%   |
| Lenovo Legion Y7000 2020 82AV                     | 1         | 0.57%   |
| Lenovo Legion R9000K2021H 82N6                    | 1         | 0.57%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Lenovo IdeaPad                       | 9         | 5.14%   |
| Dell Inspiron                        | 9         | 5.14%   |
| Lenovo ThinkPad                      | 7         | 4%      |
| Acer Aspire                          | 7         | 4%      |
| HP Pavilion                          | 5         | 2.86%   |
| HP EliteBook                         | 5         | 2.86%   |
| TSINGHUA TONGFANG COMPUTER E500      | 4         | 2.29%   |
| Toshiba Satellite                    | 4         | 2.29%   |
| Unknown                              | 4         | 2.29%   |
| Lenovo Legion                        | 3         | 1.71%   |
| HP Laptop                            | 3         | 1.71%   |
| ASUS PRIME                           | 3         | 1.71%   |
| Acer Nitro                           | 3         | 1.71%   |
| Semp Toshiba STI                     | 2         | 1.14%   |
| Samsung 340XAA                       | 2         | 1.14%   |
| Lenovo ZHAOYANG                      | 2         | 1.14%   |
| Lenovo Yoga                          | 2         | 1.14%   |
| Lenovo ThinkCentre                   | 2         | 1.14%   |
| Lenovo ThinkBook                     | 2         | 1.14%   |
| HP ENVY                              | 2         | 1.14%   |
| ECS H81H3-M4                         | 2         | 1.14%   |
| Dell OptiPlex                        | 2         | 1.14%   |
| Dell Latitude                        | 2         | 1.14%   |
| ASUS All                             | 2         | 1.14%   |
| Acer Swift                           | 2         | 1.14%   |
| Timi TM1701                          | 1         | 0.57%   |
| Standard MB45II                      | 1         | 0.57%   |
| Soyo SY-Thin                         | 1         | 0.57%   |
| Sony VPCYB25AB                       | 1         | 0.57%   |
| Sony VGN-NS140D                      | 1         | 0.57%   |
| Sony VGN-AW11Z                       | 1         | 0.57%   |
| Sony SVF14A190X                      | 1         | 0.57%   |
| Sony SVE14135CXP                     | 1         | 0.57%   |
| Samsung P500A2D                      | 1         | 0.57%   |
| Samsung 800G5M                       | 1         | 0.57%   |
| Samsung 550P5C                       | 1         | 0.57%   |
| Samsung 500R4K                       | 1         | 0.57%   |
| Samsung 300E4A                       | 1         | 0.57%   |
| Samsung 270E5J                       | 1         | 0.57%   |
| Positivo POS-PQ45AU                  | 1         | 0.57%   |
| Positivo POS-EINM70CS                | 1         | 0.57%   |
| Positivo C14CU51                     | 1         | 0.57%   |
| MSI MS-7C83                          | 1         | 0.57%   |
| MSI MS-7851                          | 1         | 0.57%   |
| MSI MS-7681                          | 1         | 0.57%   |
| Microtech ebookPro                   | 1         | 0.57%   |
| Microsoft Surface                    | 1         | 0.57%   |
| Medion MS-7728                       | 1         | 0.57%   |
| Loongson LS3A3000-7A1000-1w-V1.2-Dev | 1         | 0.57%   |
| Lenovo XiaoXinAir-14ARE              | 1         | 0.57%   |
| Lenovo XiaoXin-15ARE                 | 1         | 0.57%   |
| Lenovo V310-15ISK                    | 1         | 0.57%   |
| Lenovo G50-80                        | 1         | 0.57%   |
| Lenovo G50-70                        | 1         | 0.57%   |
| Lenovo G400s                         | 1         | 0.57%   |
| HUAWEI NBLK-WAX9X                    | 1         | 0.57%   |
| HUAWEI HN-WX9X                       | 1         | 0.57%   |
| HUAWEI HLYL-WXX9                     | 1         | 0.57%   |
| HUAWEI HLY-WX9XX                     | 1         | 0.57%   |
| Huanan X99-8M-F                      | 1         | 0.57%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2017    | 19        | 10.86%  |
| 2019    | 17        | 9.71%   |
| 2018    | 17        | 9.71%   |
| 2013    | 17        | 9.71%   |
| 2012    | 17        | 9.71%   |
| 2020    | 12        | 6.86%   |
| 2016    | 12        | 6.86%   |
| 2011    | 12        | 6.86%   |
| 2021    | 11        | 6.29%   |
| 2014    | 11        | 6.29%   |
| 2010    | 9         | 5.14%   |
| 2015    | 8         | 4.57%   |
| 2009    | 8         | 4.57%   |
| 2008    | 2         | 1.14%   |
| Unknown | 2         | 1.14%   |
| 2022    | 1         | 0.57%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 113       | 64.57%  |
| Desktop        | 51        | 29.14%  |
| Tablet         | 4         | 2.29%   |
| All in one     | 3         | 1.71%   |
| Convertible    | 2         | 1.14%   |
| System on chip | 1         | 0.57%   |
| Mini pc        | 1         | 0.57%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 169       | 96.57%  |
| Enabled  | 6         | 3.43%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 173       | 98.86%  |
| Yes  | 2         | 1.14%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 53        | 30.29%  |
| 8.01-16.0   | 43        | 24.57%  |
| 3.01-4.0    | 34        | 19.43%  |
| 16.01-24.0  | 32        | 18.29%  |
| 32.01-64.0  | 5         | 2.86%   |
| 1.01-2.0    | 5         | 2.86%   |
| 64.01-256.0 | 2         | 1.14%   |
| 2.01-3.0    | 1         | 0.57%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 61        | 32.97%  |
| 2.01-3.0  | 50        | 27.03%  |
| 4.01-8.0  | 29        | 15.68%  |
| 3.01-4.0  | 28        | 15.14%  |
| 0.51-1.0  | 13        | 7.03%   |
| 8.01-16.0 | 3         | 1.62%   |
| 0.01-0.5  | 1         | 0.54%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 113       | 63.48%  |
| 2      | 52        | 29.21%  |
| 4      | 7         | 3.93%   |
| 3      | 5         | 2.81%   |
| 5      | 1         | 0.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 111       | 62.71%  |
| Yes       | 66        | 37.29%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 144       | 82.29%  |
| No        | 31        | 17.71%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 135       | 77.14%  |
| No        | 40        | 22.86%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 114       | 65.14%  |
| No        | 61        | 34.86%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country               | Computers | Percent |
|-----------------------|-----------|---------|
| Brazil                | 45        | 25.57%  |
| China                 | 27        | 15.34%  |
| USA                   | 12        | 6.82%   |
| Germany               | 12        | 6.82%   |
| Spain                 | 6         | 3.41%   |
| Russia                | 5         | 2.84%   |
| Indonesia             | 5         | 2.84%   |
| Turkey                | 4         | 2.27%   |
| Poland                | 4         | 2.27%   |
| Panama                | 4         | 2.27%   |
| Chile                 | 4         | 2.27%   |
| Mexico                | 3         | 1.7%    |
| Italy                 | 3         | 1.7%    |
| Colombia              | 3         | 1.7%    |
| Argentina             | 3         | 1.7%    |
| UK                    | 2         | 1.14%   |
| Japan                 | 2         | 1.14%   |
| India                 | 2         | 1.14%   |
| Canada                | 2         | 1.14%   |
| Bangladesh            | 2         | 1.14%   |
| Austria               | 2         | 1.14%   |
| Venezuela             | 1         | 0.57%   |
| Ukraine               | 1         | 0.57%   |
| Tunisia               | 1         | 0.57%   |
| Sweden                | 1         | 0.57%   |
| South Africa          | 1         | 0.57%   |
| Singapore             | 1         | 0.57%   |
| Serbia                | 1         | 0.57%   |
| Sao Tome and Principe | 1         | 0.57%   |
| Romania               | 1         | 0.57%   |
| Portugal              | 1         | 0.57%   |
| Pakistan              | 1         | 0.57%   |
| New Zealand           | 1         | 0.57%   |
| Namibia               | 1         | 0.57%   |
| Lithuania             | 1         | 0.57%   |
| Iran                  | 1         | 0.57%   |
| Greece                | 1         | 0.57%   |
| France                | 1         | 0.57%   |
| Ecuador               | 1         | 0.57%   |
| Czechia               | 1         | 0.57%   |
| Cuba                  | 1         | 0.57%   |
| Bulgaria              | 1         | 0.57%   |
| Belgium               | 1         | 0.57%   |
| Belarus               | 1         | 0.57%   |
| Australia             | 1         | 0.57%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Sao Paulo          | 5         | 2.81%   |
| Beijing            | 5         | 2.81%   |
| Guangzhou          | 4         | 2.25%   |
| David              | 4         | 2.25%   |
| Nanjing            | 3         | 1.69%   |
| Curitiba           | 3         | 1.69%   |
| Wuhan              | 2         | 1.12%   |
| Uberlândia        | 2         | 1.12%   |
| Surabaya           | 2         | 1.12%   |
| Shanghai           | 2         | 1.12%   |
| San Francisco      | 2         | 1.12%   |
| Petrópolis        | 2         | 1.12%   |
| Londrina           | 2         | 1.12%   |
| Getxo              | 2         | 1.12%   |
| Dhaka              | 2         | 1.12%   |
| Contagem           | 2         | 1.12%   |
| Brasília          | 2         | 1.12%   |
| Bogotá            | 2         | 1.12%   |
| Atlanta            | 2         | 1.12%   |
| Yozgat             | 1         | 0.56%   |
| Yogyakarta         | 1         | 0.56%   |
| Xuhui              | 1         | 0.56%   |
| Windhoek           | 1         | 0.56%   |
| West Jordan        | 1         | 0.56%   |
| Waynesville        | 1         | 0.56%   |
| Voluntari          | 1         | 0.56%   |
| Villa Ballester    | 1         | 0.56%   |
| Vigo               | 1         | 0.56%   |
| Ufa                | 1         | 0.56%   |
| Tychy              | 1         | 0.56%   |
| Tomsk              | 1         | 0.56%   |
| Toluca             | 1         | 0.56%   |
| Tianjin            | 1         | 0.56%   |
| TehrДЃn          | 1         | 0.56%   |
| Taua               | 1         | 0.56%   |
| Taiyuan            | 1         | 0.56%   |
| SГЈo TomГ©     | 1         | 0.56%   |
| Suzhou             | 1         | 0.56%   |
| Suzano             | 1         | 0.56%   |
| Surakarta          | 1         | 0.56%   |
| St Petersburg      | 1         | 0.56%   |
| Socorro            | 1         | 0.56%   |
| Singapore          | 1         | 0.56%   |
| Shenzhen           | 1         | 0.56%   |
| Seesen             | 1         | 0.56%   |
| Sao Carlos         | 1         | 0.56%   |
| Sao Caetano do Sul | 1         | 0.56%   |
| Sao Bento do Sul   | 1         | 0.56%   |
| Santiago           | 1         | 0.56%   |
| Samara             | 1         | 0.56%   |
| Saitama            | 1         | 0.56%   |
| Rzeszów           | 1         | 0.56%   |
| Rotenburg          | 1         | 0.56%   |
| Rome               | 1         | 0.56%   |
| Rio de Janeiro     | 1         | 0.56%   |
| Ransart            | 1         | 0.56%   |
| Poznan             | 1         | 0.56%   |
| Portoviejo         | 1         | 0.56%   |
| Porto Velho        | 1         | 0.56%   |
| Plovdiv            | 1         | 0.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 40        | 49     | 16%     |
| Seagate                        | 37        | 43     | 14.8%   |
| Samsung Electronics            | 24        | 27     | 9.6%    |
| SanDisk                        | 18        | 22     | 7.2%    |
| Toshiba                        | 17        | 19     | 6.8%    |
| Unknown                        | 13        | 14     | 5.2%    |
| Kingston                       | 13        | 18     | 5.2%    |
| Hitachi                        | 8         | 8      | 3.2%    |
| SK hynix                       | 7         | 7      | 2.8%    |
| Crucial                        | 7         | 8      | 2.8%    |
| Micron Technology              | 6         | 8      | 2.4%    |
| China                          | 6         | 6      | 2.4%    |
| HGST                           | 5         | 5      | 2%      |
| A-DATA Technology              | 5         | 6      | 2%      |
| SPCC                           | 4         | 5      | 1.6%    |
| Intel                          | 4         | 5      | 1.6%    |
| LITEON                         | 3         | 3      | 1.2%    |
| Vaseky                         | 2         | 2      | 0.8%    |
| Silicon Motion                 | 2         | 2      | 0.8%    |
| Maxtor                         | 2         | 4      | 0.8%    |
| JMicron Technology             | 2         | 2      | 0.8%    |
| Intenso                        | 2         | 3      | 0.8%    |
| Hewlett-Packard                | 2         | 3      | 0.8%    |
| FORESEE                        | 2         | 2      | 0.8%    |
| V-GeN                          | 1         | 1      | 0.4%    |
| Transcend                      | 1         | 1      | 0.4%    |
| Solid State Storage Technology | 1         | 1      | 0.4%    |
| Realtek Semiconductor          | 1         | 1      | 0.4%    |
| Phison                         | 1         | 1      | 0.4%    |
| OEM                            | 1         | 1      | 0.4%    |
| OCZ                            | 1         | 1      | 0.4%    |
| Netac                          | 1         | 1      | 0.4%    |
| Mushkin                        | 1         | 1      | 0.4%    |
| Microtech                      | 1         | 1      | 0.4%    |
| Maxtor 6                       | 1         | 1      | 0.4%    |
| LaCie                          | 1         | 2      | 0.4%    |
| KingSpec                       | 1         | 1      | 0.4%    |
| KingDian                       | 1         | 1      | 0.4%    |
| KINGBANK                       | 1         | 1      | 0.4%    |
| Gigabyte Technology            | 1         | 1      | 0.4%    |
| Fujitsu                        | 1         | 2      | 0.4%    |
| Beijing Starblaze              | 1         | 1      | 0.4%    |
| Apacer                         | 1         | 3      | 0.4%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 6         | 2.29%   |
| Toshiba MQ01ABF050 500GB             | 5         | 1.91%   |
| Kingston SA400S37240G 240GB SSD      | 5         | 1.91%   |
| WDC WD5000LPCX-24VHAT0 500GB         | 3         | 1.15%   |
| Unknown MMC Card                     | 3         | 1.15%   |
| Toshiba MQ01ABD100 1TB               | 3         | 1.15%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 3         | 1.15%   |
| Seagate ST1000DM010-2EP102 1TB       | 3         | 1.15%   |
| Samsung SSD 850 EVO 500GB            | 3         | 1.15%   |
| Crucial CT240BX500SSD1 240GB         | 3         | 1.15%   |
| WDC WD5000AAKX-003CA0 500GB          | 2         | 0.76%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB | 2         | 0.76%   |
| SPCC Solid State Disk 512GB          | 2         | 0.76%   |
| Seagate ST9320325AS 320GB            | 2         | 0.76%   |
| Seagate ST2000LM007-1R8174 2TB       | 2         | 0.76%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 0.76%   |
| Seagate ST1000DM003-1SB102 1TB       | 2         | 0.76%   |
| SanDisk SSD PLUS 240GB               | 2         | 0.76%   |
| SanDisk SDSSDH3512G 512GB            | 2         | 0.76%   |
| SanDisk SDSSDA240G 240GB             | 2         | 0.76%   |
| SanDisk SDSSDA120G 120GB             | 2         | 0.76%   |
| SanDisk DF4064  64GB                 | 2         | 0.76%   |
| Samsung MZVLW256HEHP-000H1 256GB     | 2         | 0.76%   |
| Kingston SV300S37A120G 120GB SSD     | 2         | 0.76%   |
| JMicron Generic 2TB                  | 2         | 0.76%   |
| HGST HTS545050A7E680 500GB           | 2         | 0.76%   |
| FORESEE P900F256GBH                  | 2         | 0.76%   |
| WDC WDS500G2B0C-00PXH0 500GB         | 1         | 0.38%   |
| WDC WDS500G2B0B-00YS70 500GB SSD     | 1         | 0.38%   |
| WDC WDS480G2G0B-00EPW0 480GB SSD     | 1         | 0.38%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 1         | 0.38%   |
| WDC WDS120G1G0A-00SS50 120GB SSD     | 1         | 0.38%   |
| WDC WDS100T2G0A-00JH30 1TB SSD       | 1         | 0.38%   |
| WDC WD80 0BEVE-11UYT0 80GB           | 1         | 0.38%   |
| WDC WD7500BPVT-24HXZT3 752GB         | 1         | 0.38%   |
| WDC WD7500BPKX-22HPJT0 752GB         | 1         | 0.38%   |
| WDC WD6400AAKS-75A7B0 640GB          | 1         | 0.38%   |
| WDC WD5000LPZX-75Z10T0 500GB         | 1         | 0.38%   |
| WDC WD5000LPVX-80V0TT0 500GB         | 1         | 0.38%   |
| WDC WD5000LPVX-08V0TT6 500GB         | 1         | 0.38%   |
| WDC WD5000LPCX-24C6HT0 500GB         | 1         | 0.38%   |
| WDC WD5000AAKX-00ERMA0 500GB         | 1         | 0.38%   |
| WDC WD5000AAKS-00A7B2 500GB          | 1         | 0.38%   |
| WDC WD5000AAJS-57TKA0 500GB          | 1         | 0.38%   |
| WDC WD3200BEVT-60A23T0 320GB         | 1         | 0.38%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 1         | 0.38%   |
| WDC WD3200BEVT-08A23T1 320GB         | 1         | 0.38%   |
| WDC WD3200AAKS-00VYA0 320GB          | 1         | 0.38%   |
| WDC WD20PURX-64P6ZY0 2TB             | 1         | 0.38%   |
| WDC WD20EARX-00PASB0 2TB             | 1         | 0.38%   |
| WDC WD1600AAJS-00L7A0 160GB          | 1         | 0.38%   |
| WDC WD10SPZX-35Z10T0 1TB             | 1         | 0.38%   |
| WDC WD10SPZX-24Z10 1TB               | 1         | 0.38%   |
| WDC WD10SPZX-08Z10 1TB               | 1         | 0.38%   |
| WDC WD10JPVX-60JC3T1 1TB             | 1         | 0.38%   |
| WDC WD10JPVX-60JC3T0 1TB             | 1         | 0.38%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.38%   |
| WDC WD10JPCX-24UE4T0 1TB             | 1         | 0.38%   |
| WDC WD10EZEX-22MFCA0 1TB             | 1         | 0.38%   |
| WDC WD10EZEX-08M2NA0 1TB             | 1         | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 36        | 42     | 32.73%  |
| WDC                 | 33        | 39     | 30%     |
| Toshiba             | 16        | 18     | 14.55%  |
| Hitachi             | 8         | 8      | 7.27%   |
| HGST                | 5         | 5      | 4.55%   |
| Samsung Electronics | 3         | 3      | 2.73%   |
| Maxtor              | 2         | 4      | 1.82%   |
| JMicron Technology  | 2         | 2      | 1.82%   |
| Unknown             | 1         | 2      | 0.91%   |
| OEM                 | 1         | 1      | 0.91%   |
| Maxtor 6            | 1         | 1      | 0.91%   |
| Hewlett-Packard     | 1         | 2      | 0.91%   |
| Fujitsu             | 1         | 2      | 0.91%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 16        | 20     | 18.82%  |
| Kingston            | 13        | 18     | 15.29%  |
| Samsung Electronics | 11        | 13     | 12.94%  |
| China               | 6         | 6      | 7.06%   |
| WDC                 | 5         | 5      | 5.88%   |
| Crucial             | 5         | 6      | 5.88%   |
| SPCC                | 4         | 5      | 4.71%   |
| A-DATA Technology   | 3         | 4      | 3.53%   |
| Vaseky              | 2         | 2      | 2.35%   |
| SK hynix            | 2         | 2      | 2.35%   |
| Micron Technology   | 2         | 3      | 2.35%   |
| LITEON              | 2         | 2      | 2.35%   |
| Intenso             | 2         | 3      | 2.35%   |
| V-GeN               | 1         | 1      | 1.18%   |
| Unknown             | 1         | 1      | 1.18%   |
| Transcend           | 1         | 1      | 1.18%   |
| OCZ                 | 1         | 1      | 1.18%   |
| Netac               | 1         | 1      | 1.18%   |
| Microtech           | 1         | 1      | 1.18%   |
| KingSpec            | 1         | 1      | 1.18%   |
| KingDian            | 1         | 1      | 1.18%   |
| KINGBANK            | 1         | 1      | 1.18%   |
| Intel               | 1         | 2      | 1.18%   |
| Hewlett-Packard     | 1         | 1      | 1.18%   |
| Apacer              | 1         | 3      | 1.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 98        | 129    | 43.17%  |
| SSD     | 75        | 104    | 33.04%  |
| NVMe    | 40        | 45     | 17.62%  |
| MMC     | 12        | 13     | 5.29%   |
| Unknown | 2         | 3      | 0.88%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 142       | 223    | 69.95%  |
| NVMe | 40        | 45     | 19.7%   |
| MMC  | 12        | 13     | 5.91%   |
| SAS  | 9         | 13     | 4.43%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 102       | 149    | 58.96%  |
| 0.51-1.0   | 60        | 71     | 34.68%  |
| 1.01-2.0   | 10        | 12     | 5.78%   |
| 4.01-10.0  | 1         | 1      | 0.58%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 48        | 26.67%  |
| 101-250        | 43        | 23.89%  |
| 501-1000       | 37        | 20.56%  |
| 1001-2000      | 24        | 13.33%  |
| 51-100         | 8         | 4.44%   |
| More than 3000 | 7         | 3.89%   |
| 21-50          | 5         | 2.78%   |
| 2001-3000      | 4         | 2.22%   |
| Unknown        | 3         | 1.67%   |
| 1-20           | 1         | 0.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 21-50     | 37        | 20.22%  |
| 101-250   | 36        | 19.67%  |
| 1-20      | 36        | 19.67%  |
| 51-100    | 24        | 13.11%  |
| 251-500   | 19        | 10.38%  |
| 501-1000  | 19        | 10.38%  |
| 1001-2000 | 6         | 3.28%   |
| 2001-3000 | 3         | 1.64%   |
| Unknown   | 3         | 1.64%   |

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
| Intenso lntenso SSD Sata III 240GB            | 1         | 1      | 5.88%   |
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
| Detected | 98        | 162    | 50.78%  |
| Works    | 77        | 112    | 39.9%   |
| Malfunc  | 16        | 18     | 8.29%   |
| Failed   | 2         | 2      | 1.04%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 129       | 63.24%  |
| AMD                            | 20        | 9.8%    |
| Samsung Electronics            | 11        | 5.39%   |
| SK hynix                       | 5         | 2.45%   |
| SanDisk                        | 5         | 2.45%   |
| ASMedia Technology             | 5         | 2.45%   |
| Micron Technology              | 4         | 1.96%   |
| Marvell Technology Group       | 4         | 1.96%   |
| Silicon Motion                 | 3         | 1.47%   |
| Shenzhen Longsys Electronics   | 2         | 0.98%   |
| Realtek Semiconductor          | 2         | 0.98%   |
| Phison Electronics             | 2         | 0.98%   |
| Nvidia                         | 2         | 0.98%   |
| Micron/Crucial Technology      | 2         | 0.98%   |
| JMicron Technology             | 2         | 0.98%   |
| Zhaoxin                        | 1         | 0.49%   |
| Solid State Storage Technology | 1         | 0.49%   |
| Loongson Technology            | 1         | 0.49%   |
| Lite-On Technology             | 1         | 0.49%   |
| KIOXIA                         | 1         | 0.49%   |
| Beijing Starblaze Technology   | 1         | 0.49%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 15        | 6.73%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 14        | 6.28%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 13        | 5.83%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 11        | 4.93%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 10        | 4.48%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 6         | 2.69%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 6         | 2.69%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 6         | 2.69%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 6         | 2.69%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 6         | 2.69%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5         | 2.24%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5         | 2.24%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 5         | 2.24%   |
| Micron Non-Volatile memory controller                                                   | 4         | 1.79%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4         | 1.79%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 4         | 1.79%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4         | 1.79%   |
| SK hynix BC511                                                                          | 3         | 1.35%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 3         | 1.35%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3         | 1.35%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 3         | 1.35%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 3         | 1.35%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 3         | 1.35%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 3         | 1.35%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 3         | 1.35%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 3         | 1.35%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 2         | 0.9%    |
| Shenzhen Longsys Non-Volatile memory controller                                         | 2         | 0.9%    |
| SanDisk Non-Volatile memory controller                                                  | 2         | 0.9%    |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 2         | 0.9%    |
| Intel SATA Controller [RAID mode]                                                       | 2         | 0.9%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 2         | 0.9%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2         | 0.9%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 2         | 0.9%    |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2         | 0.9%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 0.9%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 0.9%    |
| Zhaoxin ZX-100/ZX-200/ZX-E StorX AHCI Controller                                        | 1         | 0.45%   |
| Solid State Storage Non-Volatile memory controller                                      | 1         | 0.45%   |
| SK hynix Gold P31 SSD                                                                   | 1         | 0.45%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 1         | 0.45%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 1         | 0.45%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1         | 0.45%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1         | 0.45%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 1         | 0.45%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1         | 0.45%   |
| Samsung NVMe SSD Controller 980                                                         | 1         | 0.45%   |
| Realtek RTS5763DL NVMe SSD Controller                                                   | 1         | 0.45%   |
| Realtek Realtek Non-Volatile memory controller                                          | 1         | 0.45%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1         | 0.45%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1         | 0.45%   |
| Nvidia MCP79 SATA Controller                                                            | 1         | 0.45%   |
| Nvidia MCP61 SATA Controller                                                            | 1         | 0.45%   |
| Nvidia MCP61 IDE                                                                        | 1         | 0.45%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1         | 0.45%   |
| Micron/Crucial Non-Volatile memory controller                                           | 1         | 0.45%   |
| Marvell Group 88SE9123 PCIe SATA 6.0 Gb/s controller                                    | 1         | 0.45%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 1         | 0.45%   |
| Loongson SATA AHCI Controller                                                           | 1         | 0.45%   |
| Lite-On Non-Volatile memory controller                                                  | 1         | 0.45%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 136       | 67.66%  |
| NVMe | 40        | 19.9%   |
| IDE  | 17        | 8.46%   |
| RAID | 8         | 3.98%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 143       | 81.71%  |
| AMD          | 29        | 16.57%  |
| PHYTIUM      | 1         | 0.57%   |
| CentaurHauls | 1         | 0.57%   |
| Unknown      | 1         | 0.57%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 2.86%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 4         | 2.29%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 4         | 2.29%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 2.29%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 4         | 2.29%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 1.71%   |
| Intel Core i7-10700 CPU @ 2.90GHz             | 3         | 1.71%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 3         | 1.71%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 1.71%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 1.71%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 2         | 1.14%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.14%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 2         | 1.14%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 2         | 1.14%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 1.14%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 2         | 1.14%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 1.14%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 1.14%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 1.14%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 1.14%   |
| Intel Core i3-6100 CPU @ 3.70GHz              | 2         | 1.14%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 2         | 1.14%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 2         | 1.14%   |
| Intel Core i3-10100 CPU @ 3.60GHz             | 2         | 1.14%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 2         | 1.14%   |
| Intel Celeron CPU 1007U @ 1.50GHz             | 2         | 1.14%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 2         | 1.14%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 2         | 1.14%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 1.14%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 1.14%   |
| AMD Ryzen 5 4600U with Radeon Graphics        | 2         | 1.14%   |
| AMD Ryzen 5 3600 6-Core Processor             | 2         | 1.14%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.14%   |
| AMD FX-8320 Eight-Core Processor              | 2         | 1.14%   |
| PHYTIUM D2000 Series CPU                      | 1         | 0.57%   |
| Intel Xeon CPU E5450 @ 3.00GHz                | 1         | 0.57%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz           | 1         | 0.57%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.57%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz      | 1         | 0.57%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 0.57%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz   | 1         | 0.57%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.57%   |
| Intel Pentium CPU 5405U @ 2.30GHz             | 1         | 0.57%   |
| Intel Pentium CPU 4415U @ 2.30GHz             | 1         | 0.57%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz              | 1         | 0.57%   |
| Intel Core M-5Y71 CPU @ 1.20GHz               | 1         | 0.57%   |
| Intel Core i9-8950HK CPU @ 2.90GHz            | 1         | 0.57%   |
| Intel Core i9-10900K CPU @ 3.70GHz            | 1         | 0.57%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 0.57%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 1         | 0.57%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.57%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 1         | 0.57%   |
| Intel Core i7-7560U CPU @ 2.40GHz             | 1         | 0.57%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 1         | 0.57%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 0.57%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 0.57%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 1         | 0.57%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 1         | 0.57%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 1         | 0.57%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 42        | 24%     |
| Intel Core i7           | 40        | 22.86%  |
| Intel Core i3           | 19        | 10.86%  |
| Intel Celeron           | 10        | 5.71%   |
| AMD Ryzen 5             | 9         | 5.14%   |
| Other                   | 8         | 4.57%   |
| Intel Core 2 Duo        | 8         | 4.57%   |
| Intel Atom              | 5         | 2.86%   |
| AMD Ryzen 7             | 5         | 2.86%   |
| Intel Pentium Dual-Core | 4         | 2.29%   |
| AMD FX                  | 4         | 2.29%   |
| Intel Pentium           | 3         | 1.71%   |
| AMD Ryzen 3             | 3         | 1.71%   |
| Intel Xeon              | 2         | 1.14%   |
| Intel Pentium Silver    | 2         | 1.14%   |
| Intel Core i9           | 2         | 1.14%   |
| AMD A10                 | 2         | 1.14%   |
| Intel Core m3           | 1         | 0.57%   |
| Intel Core M            | 1         | 0.57%   |
| Intel Celeron Dual-Core | 1         | 0.57%   |
| AMD E1                  | 1         | 0.57%   |
| AMD E                   | 1         | 0.57%   |
| AMD C-60                | 1         | 0.57%   |
| AMD Athlon              | 1         | 0.57%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 88        | 50.29%  |
| 4      | 65        | 37.14%  |
| 8      | 9         | 5.14%   |
| 6      | 9         | 5.14%   |
| 12     | 1         | 0.57%   |
| 10     | 1         | 0.57%   |
| 3      | 1         | 0.57%   |
| 1      | 1         | 0.57%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 175       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 122       | 69.71%  |
| 1      | 53        | 30.29%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 159       | 90.86%  |
| Unknown        | 16        | 9.14%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 45        | 25.42%  |
| 0x306a9    | 18        | 10.17%  |
| 0x40651    | 9         | 5.08%   |
| 0x806e9    | 8         | 4.52%   |
| 0x206a7    | 8         | 4.52%   |
| 0x806ec    | 7         | 3.95%   |
| 0x306d4    | 7         | 3.95%   |
| 0x1067a    | 7         | 3.95%   |
| 0x306c3    | 6         | 3.39%   |
| 0x406e3    | 5         | 2.82%   |
| 0x906ea    | 4         | 2.26%   |
| 0xa0655    | 3         | 1.69%   |
| 0x906e9    | 3         | 1.69%   |
| 0x806ea    | 3         | 1.69%   |
| 0x406c4    | 3         | 1.69%   |
| 0x806c1    | 2         | 1.13%   |
| 0x506e3    | 2         | 1.13%   |
| 0x20655    | 2         | 1.13%   |
| 0x08600106 | 2         | 1.13%   |
| 0x08600104 | 2         | 1.13%   |
| 0x08108109 | 2         | 1.13%   |
| 0x08108102 | 2         | 1.13%   |
| 0x0500010d | 2         | 1.13%   |
| 0xa0653    | 1         | 0.56%   |
| 0xa0652    | 1         | 0.56%   |
| 0x906eb    | 1         | 0.56%   |
| 0x906a3    | 1         | 0.56%   |
| 0x706a1    | 1         | 0.56%   |
| 0x6fd      | 1         | 0.56%   |
| 0x406c3    | 1         | 0.56%   |
| 0x306f2    | 1         | 0.56%   |
| 0x30678    | 1         | 0.56%   |
| 0x10676    | 1         | 0.56%   |
| 0x0a50000c | 1         | 0.56%   |
| 0x0a50000b | 1         | 0.56%   |
| 0x08701013 | 1         | 0.56%   |
| 0x08600103 | 1         | 0.56%   |
| 0x08600102 | 1         | 0.56%   |
| 0x08200103 | 1         | 0.56%   |
| 0x0810100b | 1         | 0.56%   |
| 0x08001138 | 1         | 0.56%   |
| 0x08001137 | 1         | 0.56%   |
| 0x07026101 | 1         | 0.56%   |
| 0x06006115 | 1         | 0.56%   |
| 0x06000822 | 1         | 0.56%   |
| 0x06000629 | 1         | 0.56%   |
| 0x06000626 | 1         | 0.56%   |
| 0x05000029 | 1         | 0.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 32        | 18.29%  |
| IvyBridge        | 23        | 13.14%  |
| Haswell          | 18        | 10.29%  |
| Penryn           | 13        | 7.43%   |
| Skylake          | 10        | 5.71%   |
| SandyBridge      | 10        | 5.71%   |
| Broadwell        | 10        | 5.71%   |
| Zen 2            | 8         | 4.57%   |
| Silvermont       | 8         | 4.57%   |
| CometLake        | 7         | 4%      |
| Zen+             | 4         | 2.29%   |
| Zen              | 4         | 2.29%   |
| Unknown          | 4         | 2.29%   |
| Westmere         | 3         | 1.71%   |
| Goldmont plus    | 3         | 1.71%   |
| Bobcat           | 3         | 1.71%   |
| Zen 3            | 2         | 1.14%   |
| TigerLake        | 2         | 1.14%   |
| Piledriver       | 2         | 1.14%   |
| Goldmont         | 2         | 1.14%   |
| Excavator        | 2         | 1.14%   |
| Bulldozer        | 2         | 1.14%   |
| Jaguar           | 1         | 0.57%   |
| Core             | 1         | 0.57%   |
| Alderlake Hybrid | 1         | 0.57%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 116       | 53.46%  |
| Nvidia              | 58        | 26.73%  |
| AMD                 | 41        | 18.89%  |
| Zhaoxin             | 1         | 0.46%   |
| Loongson Technology | 1         | 0.46%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 12        | 5.45%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 5%      |
| Intel HD Graphics 5500                                                                   | 9         | 4.09%   |
| Intel HD Graphics 620                                                                    | 8         | 3.64%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8         | 3.64%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 6         | 2.73%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 2.73%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 6         | 2.73%   |
| AMD Renoir                                                                               | 6         | 2.73%   |
| Intel UHD Graphics 620                                                                   | 5         | 2.27%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 2.27%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 2.27%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 2.27%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4         | 1.82%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 3         | 1.36%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 1.36%   |
| Intel HD Graphics 630                                                                    | 3         | 1.36%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.36%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 1.36%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 0.91%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 0.91%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.91%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 0.91%   |
| Nvidia GM108M [GeForce MX110]                                                            | 2         | 0.91%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 2         | 0.91%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.91%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 2         | 0.91%   |
| Nvidia GK107M [GeForce GT 650M]                                                          | 2         | 0.91%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.91%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 2         | 0.91%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 0.91%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 0.91%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 2         | 0.91%   |
| Intel HD Graphics 500                                                                    | 2         | 0.91%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 0.91%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 0.91%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 0.91%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 0.91%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 2         | 0.91%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 0.91%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 2         | 0.91%   |
| Zhaoxin ZX-E C-960 GPU                                                                   | 1         | 0.45%   |
| Nvidia TU117M                                                                            | 1         | 0.45%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 1         | 0.45%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                    | 1         | 0.45%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.45%   |
| Nvidia GP108BM [GeForce MX250]                                                           | 1         | 0.45%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 0.45%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.45%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.45%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 0.45%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 1         | 0.45%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 1         | 0.45%   |
| Nvidia GM206 [GeForce GTX 950]                                                           | 1         | 0.45%   |
| Nvidia GM108M [GeForce 940M]                                                             | 1         | 0.45%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 1         | 0.45%   |
| Nvidia GM108M [GeForce 845M]                                                             | 1         | 0.45%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 0.45%   |
| Nvidia GK208M [GeForce GT 735M]                                                          | 1         | 0.45%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1         | 0.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 75        | 42.86%  |
| Intel + Nvidia          | 32        | 18.29%  |
| 1 x AMD                 | 31        | 17.71%  |
| 1 x Nvidia              | 25        | 14.29%  |
| Intel + AMD             | 7         | 4%      |
| 2 x AMD                 | 2         | 1.14%   |
| 1 x Zhaoxin             | 1         | 0.57%   |
| 1 x Loongson Technology | 1         | 0.57%   |
| AMD + Nvidia            | 1         | 0.57%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 139       | 79.43%  |
| Proprietary | 26        | 14.86%  |
| Unknown     | 10        | 5.71%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 96        | 53.63%  |
| 1.01-2.0   | 40        | 22.35%  |
| 3.01-4.0   | 19        | 10.61%  |
| 0.01-0.5   | 11        | 6.15%   |
| 0.51-1.0   | 7         | 3.91%   |
| 7.01-8.0   | 3         | 1.68%   |
| 5.01-6.0   | 3         | 1.68%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 27        | 15.34%  |
| AU Optronics            | 27        | 15.34%  |
| BOE                     | 25        | 14.2%   |
| LG Display              | 16        | 9.09%   |
| Chimei Innolux          | 16        | 9.09%   |
| Goldstar                | 9         | 5.11%   |
| Hewlett-Packard         | 8         | 4.55%   |
| Lenovo                  | 4         | 2.27%   |
| Dell                    | 4         | 2.27%   |
| ViewSonic               | 3         | 1.7%    |
| Iiyama                  | 3         | 1.7%    |
| AOC                     | 3         | 1.7%    |
| Ancor Communications    | 3         | 1.7%    |
| Philips                 | 2         | 1.14%   |
| InfoVision              | 2         | 1.14%   |
| CSO                     | 2         | 1.14%   |
| Chi Mei Optoelectronics | 2         | 1.14%   |
| BenQ                    | 2         | 1.14%   |
| Acer                    | 2         | 1.14%   |
| Unknown                 | 1         | 0.57%   |
| Toshiba                 | 1         | 0.57%   |
| TFC                     | 1         | 0.57%   |
| Sharp                   | 1         | 0.57%   |
| SAC                     | 1         | 0.57%   |
| RTK                     | 1         | 0.57%   |
| Positivo                | 1         | 0.57%   |
| PANDA                   | 1         | 0.57%   |
| MSI                     | 1         | 0.57%   |
| Hisense                 | 1         | 0.57%   |
| HB@                     | 1         | 0.57%   |
| HannStar                | 1         | 0.57%   |
| Gateway                 | 1         | 0.57%   |
| DTV                     | 1         | 0.57%   |
| ASUSTek Computer        | 1         | 0.57%   |
| Apple                   | 1         | 0.57%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch           | 3         | 1.64%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch          | 3         | 1.64%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch             | 2         | 1.09%   |
| Goldstar 20EN33 GSM4EE1 1600x900 443x249mm 20.0-inch                    | 2         | 1.09%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch         | 2         | 1.09%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                    | 2         | 1.09%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch           | 2         | 1.09%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 276x155mm 12.5-inch          | 2         | 1.09%   |
| ViewSonic VX2481-mh VSC3933 1920x1080 527x296mm 23.8-inch               | 1         | 0.55%   |
| ViewSonic VA2478-H-2 VSC8335 1920x1080 527x296mm 23.8-inch              | 1         | 0.55%   |
| ViewSonic VA2430-H-3 VSC3A3E 1920x1080 527x296mm 23.8-inch              | 1         | 0.55%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch               | 1         | 0.55%   |
| Toshiba TV TSB0108 1920x540                                             | 1         | 0.55%   |
| TFC TF2411 TFC0238 1920x1080 527x296mm 23.8-inch                        | 1         | 0.55%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                 | 1         | 0.55%   |
| Samsung Electronics SyncMaster SAM060B 1920x1080 510x290mm 23.1-inch    | 1         | 0.55%   |
| Samsung Electronics SyncMaster SAM0601 1600x900                         | 1         | 0.55%   |
| Samsung Electronics SyncMaster SAM05FF 1600x900 443x249mm 20.0-inch     | 1         | 0.55%   |
| Samsung Electronics SyncMaster SAM02B6 1920x1200 518x324mm 24.1-inch    | 1         | 0.55%   |
| Samsung Electronics SyncMaster SAM0167 1280x1024 338x270mm 17.0-inch    | 1         | 0.55%   |
| Samsung Electronics SMT24A550 SAM07B5 1920x1080 531x299mm 24.0-inch     | 1         | 0.55%   |
| Samsung Electronics S24E360 SAM0C10 1920x1080 520x290mm 23.4-inch       | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SMS23A350H 1920x1080                    | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch   | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch    | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC384A 1366x768 344x194mm 15.5-inch    | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch    | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 340x190mm 15.3-inch    | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC314B 1600x900 344x194mm 15.5-inch    | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SDC534B 1600x900 382x215mm 17.3-inch    | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch    | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SDC4A42 1366x768 309x174mm 14.0-inch    | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch    | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SDC434A 3200x1800 293x165mm 13.2-inch   | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SDC4147 1366x768 344x194mm 15.5-inch    | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SDC3853 2736x1824 260x173mm 12.3-inch   | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1872x1053mm 84.6-inch | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SAM0E90 1366x768 609x347mm 27.6-inch    | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SAM0DF6 3840x2160 890x500mm 40.2-inch   | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SAM03BC 1920x1080                       | 1         | 0.55%   |
| Samsung Electronics LCD Monitor S24E390 1920x1080                       | 1         | 0.55%   |
| Samsung Electronics LCD Monitor S24E360 1920x1080                       | 1         | 0.55%   |
| Samsung Electronics LCD Monitor S24E310 3840x1080                       | 1         | 0.55%   |
| Samsung Electronics LCD Monitor S24E310                                 | 1         | 0.55%   |
| Samsung Electronics AIO DP500-A SEM0222 1920x1080 480x270mm 21.7-inch   | 1         | 0.55%   |
| SAC LED MONITOR SAC952D 1920x1080 480x270mm 21.7-inch                   | 1         | 0.55%   |
| RTK FHD HDR RTKBC32 1920x1080 597x336mm 27.0-inch                       | 1         | 0.55%   |
| Positivo FIT85X NON1801 1360x768 344x194mm 15.5-inch                    | 1         | 0.55%   |
| Philips FTV PHL04C2 1920x1080 1440x810mm 65.0-inch                      | 1         | 0.55%   |
| Philips 200V4 PHLC0BF 1600x900 432x240mm 19.5-inch                      | 1         | 0.55%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                 | 1         | 0.55%   |
| MSI MAG271CR MSI3FA6 1920x1080 598x336mm 27.0-inch                      | 1         | 0.55%   |
| LG Display LP156WH1-TLA1 LGD6301 1366x768 344x194mm 15.5-inch           | 1         | 0.55%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch            | 1         | 0.55%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch            | 1         | 0.55%   |
| LG Display LCD Monitor LGD055D 3000x2000 260x173mm 12.3-inch            | 1         | 0.55%   |
| LG Display LCD Monitor LGD0503 1366x768 344x194mm 15.5-inch             | 1         | 0.55%   |
| LG Display LCD Monitor LGD04B2 1920x1080 309x175mm 14.0-inch            | 1         | 0.55%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch             | 1         | 0.55%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch             | 1         | 0.55%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 75        | 43.86%  |
| 1366x768 (WXGA)    | 54        | 31.58%  |
| 1600x900 (HD+)     | 10        | 5.85%   |
| 2560x1440 (QHD)    | 5         | 2.92%   |
| 3840x2160 (4K)     | 3         | 1.75%   |
| 3840x1080          | 2         | 1.17%   |
| 1920x540           | 2         | 1.17%   |
| 1440x900 (WXGA+)   | 2         | 1.17%   |
| 1360x768           | 2         | 1.17%   |
| 1280x1024 (SXGA)   | 2         | 1.17%   |
| Unknown            | 2         | 1.17%   |
| 3440x1440          | 1         | 0.58%   |
| 3200x1800 (QHD+)   | 1         | 0.58%   |
| 3000x2000          | 1         | 0.58%   |
| 2736x1824          | 1         | 0.58%   |
| 2560x1600          | 1         | 0.58%   |
| 2288x1287          | 1         | 0.58%   |
| 2160x1440          | 1         | 0.58%   |
| 2160x1350          | 1         | 0.58%   |
| 1920x1200 (WUXGA)  | 1         | 0.58%   |
| 1680x945           | 1         | 0.58%   |
| 1680x1050 (WSXGA+) | 1         | 0.58%   |
| 1280x800 (WXGA)    | 1         | 0.58%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 53        | 29.44%  |
| 13      | 25        | 13.89%  |
| 23      | 18        | 10%     |
| 14      | 17        | 9.44%   |
| 24      | 8         | 4.44%   |
| 21      | 8         | 4.44%   |
| Unknown | 8         | 4.44%   |
| 27      | 7         | 3.89%   |
| 18      | 6         | 3.33%   |
| 12      | 5         | 2.78%   |
| 17      | 4         | 2.22%   |
| 20      | 3         | 1.67%   |
| 11      | 3         | 1.67%   |
| 84      | 2         | 1.11%   |
| 32      | 2         | 1.11%   |
| 25      | 2         | 1.11%   |
| 19      | 2         | 1.11%   |
| 142     | 1         | 0.56%   |
| 72      | 1         | 0.56%   |
| 65      | 1         | 0.56%   |
| 40      | 1         | 0.56%   |
| 31      | 1         | 0.56%   |
| 22      | 1         | 0.56%   |
| 16      | 1         | 0.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 86        | 49.14%  |
| 501-600        | 32        | 18.29%  |
| 401-500        | 19        | 10.86%  |
| 201-300        | 16        | 9.14%   |
| Unknown        | 8         | 4.57%   |
| 351-400        | 5         | 2.86%   |
| 1501-2000      | 3         | 1.71%   |
| 701-800        | 2         | 1.14%   |
| More than 2000 | 1         | 0.57%   |
| 801-900        | 1         | 0.57%   |
| 601-700        | 1         | 0.57%   |
| 1001-1500      | 1         | 0.57%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 145       | 87.88%  |
| 16/10   | 8         | 4.85%   |
| Unknown | 6         | 3.64%   |
| 3/2     | 4         | 2.42%   |
| 5/4     | 1         | 0.61%   |
| 1.00    | 1         | 0.61%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 53        | 29.44%  |
| 81-90          | 34        | 18.89%  |
| 201-250        | 29        | 16.11%  |
| 151-200        | 9         | 5%      |
| 71-80          | 8         | 4.44%   |
| Unknown        | 8         | 4.44%   |
| 301-350        | 7         | 3.89%   |
| 141-150        | 6         | 3.33%   |
| More than 1000 | 5         | 2.78%   |
| 61-70          | 5         | 2.78%   |
| 251-300        | 5         | 2.78%   |
| 51-60          | 3         | 1.67%   |
| 351-500        | 3         | 1.67%   |
| 121-130        | 2         | 1.11%   |
| 131-140        | 1         | 0.56%   |
| 111-120        | 1         | 0.56%   |
| 501-1000       | 1         | 0.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 64        | 36.57%  |
| 51-100        | 46        | 26.29%  |
| 121-160       | 40        | 22.86%  |
| 161-240       | 10        | 5.71%   |
| Unknown       | 8         | 4.57%   |
| 1-50          | 4         | 2.29%   |
| More than 240 | 3         | 1.71%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 145       | 82.39%  |
| 2     | 24        | 13.64%  |
| 0     | 6         | 3.41%   |
| 3     | 1         | 0.57%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 116       | 44.79%  |
| Intel                           | 61        | 23.55%  |
| Qualcomm Atheros                | 41        | 15.83%  |
| Broadcom                        | 7         | 2.7%    |
| Marvell Technology Group        | 5         | 1.93%   |
| Xiaomi                          | 4         | 1.54%   |
| TP-Link                         | 3         | 1.16%   |
| Broadcom Limited                | 3         | 1.16%   |
| Ralink                          | 2         | 0.77%   |
| Nvidia                          | 2         | 0.77%   |
| MediaTek                        | 2         | 0.77%   |
| Unknown                         | 1         | 0.39%   |
| Samsung Electronics             | 1         | 0.39%   |
| Ralink Technology               | 1         | 0.39%   |
| Qualcomm Atheros Communications | 1         | 0.39%   |
| OPPO Electronics                | 1         | 0.39%   |
| NXP Semiconductors              | 1         | 0.39%   |
| NetGear                         | 1         | 0.39%   |
| Loongson Technology             | 1         | 0.39%   |
| IMC Networks                    | 1         | 0.39%   |
| Huawei Technologies             | 1         | 0.39%   |
| Hewlett-Packard                 | 1         | 0.39%   |
| ASIX Electronics                | 1         | 0.39%   |
| Aquantia                        | 1         | 0.39%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 82        | 27.52%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 19        | 6.38%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 14        | 4.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 7         | 2.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 7         | 2.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 7         | 2.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 2.01%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 1.68%   |
| Intel Wireless 3165                                               | 5         | 1.68%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 1.68%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 1.34%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 4         | 1.34%   |
| Intel Wireless 8265 / 8275                                        | 4         | 1.34%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 1.34%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 3         | 1.01%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 3         | 1.01%   |
| Intel Wireless 7260                                               | 3         | 1.01%   |
| Intel Wireless 3160                                               | 3         | 1.01%   |
| Intel WiFi Link 5100                                              | 3         | 1.01%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 1.01%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.67%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.67%   |
| Realtek RTL8191SEvA Wireless LAN Controller                       | 2         | 0.67%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 0.67%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.67%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.67%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 2         | 0.67%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 2         | 0.67%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 0.67%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 0.67%   |
| Intel Wireless 7265                                               | 2         | 0.67%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 0.67%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 0.67%   |
| Intel Ethernet Connection (12) I219-V                             | 2         | 0.67%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 2         | 0.67%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 0.67%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 0.67%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 0.67%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 0.67%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 2         | 0.67%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 0.67%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.34%   |
| Xiaomi MediaTek MT7601U [MI WiFi]                                 | 1         | 0.34%   |
| Unknown Network controller                                        | 1         | 0.34%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1         | 0.34%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 1         | 0.34%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1         | 0.34%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.34%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 0.34%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.34%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.34%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 1         | 0.34%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1         | 0.34%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 0.34%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)         | 1         | 0.34%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1         | 0.34%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.34%   |
| Realtek 802.11ac NIC                                              | 1         | 0.34%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1         | 0.34%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter            | 1         | 0.34%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 49        | 35.25%  |
| Qualcomm Atheros                | 39        | 28.06%  |
| Realtek Semiconductor           | 34        | 24.46%  |
| TP-Link                         | 3         | 2.16%   |
| Broadcom Limited                | 3         | 2.16%   |
| Ralink                          | 2         | 1.44%   |
| Broadcom                        | 2         | 1.44%   |
| Xiaomi                          | 1         | 0.72%   |
| Ralink Technology               | 1         | 0.72%   |
| Qualcomm Atheros Communications | 1         | 0.72%   |
| NetGear                         | 1         | 0.72%   |
| MediaTek                        | 1         | 0.72%   |
| Marvell Technology Group        | 1         | 0.72%   |
| IMC Networks                    | 1         | 0.72%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 14        | 10%     |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 7         | 5%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 7         | 5%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 7         | 5%      |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 5         | 3.57%   |
| Intel Wireless 3165                                            | 5         | 3.57%   |
| Intel Wi-Fi 6 AX200                                            | 5         | 3.57%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 4         | 2.86%   |
| Intel Wireless 8265 / 8275                                     | 4         | 2.86%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 2.86%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 3         | 2.14%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 3         | 2.14%   |
| Intel Wireless 7260                                            | 3         | 2.14%   |
| Intel Wireless 3160                                            | 3         | 2.14%   |
| Intel WiFi Link 5100                                           | 3         | 2.14%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 3         | 2.14%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.43%   |
| Realtek RTL8191SEvA Wireless LAN Controller                    | 2         | 1.43%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 1.43%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 1.43%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 1.43%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 2         | 1.43%   |
| Intel Wireless 7265                                            | 2         | 1.43%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 1.43%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 2         | 1.43%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 1.43%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 1.43%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 1.43%   |
| Xiaomi MediaTek MT7601U [MI WiFi]                              | 1         | 0.71%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1         | 0.71%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 1         | 0.71%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 0.71%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 0.71%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 0.71%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.71%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 1         | 0.71%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1         | 0.71%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 0.71%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)      | 1         | 0.71%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 1         | 0.71%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 0.71%   |
| Realtek 802.11ac NIC                                           | 1         | 0.71%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1         | 0.71%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter         | 1         | 0.71%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.71%   |
| Qualcomm Atheros AR9271 802.11n                                | 1         | 0.71%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 0.71%   |
| NetGear A6210                                                  | 1         | 0.71%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 1         | 0.71%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless              | 1         | 0.71%   |
| Intel Wireless 8260                                            | 1         | 0.71%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1         | 0.71%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 0.71%   |
| Intel Centrino Wireless-N 2230                                 | 1         | 0.71%   |
| Intel Centrino Wireless-N 100                                  | 1         | 0.71%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 0.71%   |
| Intel Centrino Advanced-N 6235                                 | 1         | 0.71%   |
| Intel Centrino Advanced-N 6200                                 | 1         | 0.71%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 0.71%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 1         | 0.71%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 107       | 69.03%  |
| Intel                    | 21        | 13.55%  |
| Qualcomm Atheros         | 5         | 3.23%   |
| Broadcom                 | 5         | 3.23%   |
| Marvell Technology Group | 4         | 2.58%   |
| Xiaomi                   | 3         | 1.94%   |
| Nvidia                   | 2         | 1.29%   |
| Samsung Electronics      | 1         | 0.65%   |
| OPPO Electronics         | 1         | 0.65%   |
| MediaTek                 | 1         | 0.65%   |
| Loongson Technology      | 1         | 0.65%   |
| Huawei Technologies      | 1         | 0.65%   |
| Hewlett-Packard          | 1         | 0.65%   |
| ASIX Electronics         | 1         | 0.65%   |
| Aquantia                 | 1         | 0.65%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 82        | 52.56%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 19        | 12.18%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 3.85%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 2.56%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 1.28%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 1.28%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 1.28%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 1.28%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 1.28%   |
| Intel Ethernet Connection (12) I219-V                             | 2         | 1.28%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 1.28%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 1.28%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 2         | 1.28%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.64%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.64%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.64%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.64%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.64%   |
| OPPO Find X2 Lite                                                 | 1         | 0.64%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.64%   |
| Nvidia MCP61 Ethernet                                             | 1         | 0.64%   |
| MediaTek TECNO SPARK 3                                            | 1         | 0.64%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 0.64%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 0.64%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1         | 0.64%   |
| Loongson Gigabit Ethernet Controller                              | 1         | 0.64%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.64%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.64%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.64%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.64%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.64%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.64%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.64%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 0.64%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 0.64%   |
| Huawei COL-L29                                                    | 1         | 0.64%   |
| HP lt4120 Snapdragon X5 LTE                                       | 1         | 0.64%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                   | 1         | 0.64%   |
| ASIX AX88772A Fast Ethernet                                       | 1         | 0.64%   |
| Aquantia AQC111 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 0.64%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 145       | 51.42%  |
| WiFi     | 135       | 47.87%  |
| Modem    | 1         | 0.35%   |
| Unknown  | 1         | 0.35%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 106       | 61.27%  |
| Ethernet | 67        | 38.73%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 98        | 55.68%  |
| 1     | 73        | 41.48%  |
| 0     | 4         | 2.27%   |
| 3     | 1         | 0.57%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 168       | 95.45%  |
| Yes  | 8         | 4.55%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 39        | 33.91%  |
| Qualcomm Atheros Communications | 23        | 20%     |
| Realtek Semiconductor           | 12        | 10.43%  |
| Cambridge Silicon Radio         | 11        | 9.57%   |
| Foxconn / Hon Hai               | 6         | 5.22%   |
| Broadcom                        | 6         | 5.22%   |
| Realtek                         | 4         | 3.48%   |
| IMC Networks                    | 4         | 3.48%   |
| Lite-On Technology              | 3         | 2.61%   |
| Toshiba                         | 1         | 0.87%   |
| Ralink Technology               | 1         | 0.87%   |
| Marvell Semiconductor           | 1         | 0.87%   |
| Dynex                           | 1         | 0.87%   |
| Dell                            | 1         | 0.87%   |
| ASUSTek Computer                | 1         | 0.87%   |
| Apple                           | 1         | 0.87%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 20        | 17.39%  |
| Qualcomm Atheros  Bluetooth Device                                                  | 16        | 13.91%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 11        | 9.57%   |
| Realtek Bluetooth Radio                                                             | 6         | 5.22%   |
| Intel Bluetooth Device                                                              | 6         | 5.22%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 5         | 4.35%   |
| Intel AX200 Bluetooth                                                               | 5         | 4.35%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 4         | 3.48%   |
| Realtek Bluetooth Radio                                                             | 4         | 3.48%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 4         | 3.48%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 2.61%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 1.74%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 2         | 1.74%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.74%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 2         | 1.74%   |
| IMC Networks Bluetooth Device                                                       | 2         | 1.74%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 1.74%   |
| Broadcom HP Portable SoftSailing                                                    | 2         | 1.74%   |
| Toshiba Bluetooth Radio                                                             | 1         | 0.87%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.87%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.87%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 1         | 0.87%   |
| Marvell Bluetooth and Wireless LAN Composite                                        | 1         | 0.87%   |
| Lite-On Bluetooth Device                                                            | 1         | 0.87%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 0.87%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.87%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.87%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.87%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.87%   |
| Foxconn / Hon Hai BCM43142A0                                                        | 1         | 0.87%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 0.87%   |
| Dynex BCM20702A0                                                                    | 1         | 0.87%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.87%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 1         | 0.87%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 1         | 0.87%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 137       | 62.56%  |
| AMD                     | 41        | 18.72%  |
| Nvidia                  | 32        | 14.61%  |
| C-Media Electronics     | 2         | 0.91%   |
| Zhaoxin                 | 1         | 0.46%   |
| XMOS                    | 1         | 0.46%   |
| Microdia                | 1         | 0.46%   |
| Loongson Technology     | 1         | 0.46%   |
| JMTek                   | 1         | 0.46%   |
| Creative Technology     | 1         | 0.46%   |
| BEHRINGER International | 1         | 0.46%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 21        | 7.92%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 19        | 7.17%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 14        | 5.28%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 14        | 5.28%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 11        | 4.15%   |
| Intel 8 Series HD Audio Controller                                                                | 11        | 4.15%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 10        | 3.77%   |
| Intel Broadwell-U Audio Controller                                                                | 10        | 3.77%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 7         | 2.64%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 7         | 2.64%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 2.26%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 2.26%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 2.26%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 5         | 1.89%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 1.89%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1.51%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 1.51%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 1.51%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 4         | 1.51%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 1.13%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 3         | 1.13%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 1.13%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 3         | 1.13%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 1.13%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 1.13%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 1.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1.13%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 1.13%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 1.13%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 1.13%   |
| AMD FCH Azalia Controller                                                                         | 3         | 1.13%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3         | 1.13%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 0.75%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.75%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.75%   |
| Nvidia Audio device                                                                               | 2         | 0.75%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 0.75%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 0.75%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 0.75%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 0.75%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2         | 0.75%   |
| Intel 200 Series PCH HD Audio                                                                     | 2         | 0.75%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 0.75%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 2         | 0.75%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 0.75%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2         | 0.75%   |
| Zhaoxin ZX-E High Definition Audio Controller                                                     | 1         | 0.38%   |
| Zhaoxin ZX-100/ZX-D/ZX-E High Definition Audio Controller                                         | 1         | 0.38%   |
| XMOS iFi (by AMR) HD USB Audio                                                                    | 1         | 0.38%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.38%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.38%   |
| Nvidia MCP61 High Definition Audio                                                                | 1         | 0.38%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 1         | 0.38%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 0.38%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 0.38%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.38%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 1         | 0.38%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.38%   |
| Microdia USB Audio                                                                                | 1         | 0.38%   |
| Loongson Technology HDA (High Definition Audio) Controller                                        | 1         | 0.38%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 22        | 21.36%  |
| SK hynix            | 19        | 18.45%  |
| Unknown             | 15        | 14.56%  |
| Kingston            | 13        | 12.62%  |
| Micron Technology   | 7         | 6.8%    |
| Smart               | 4         | 3.88%   |
| Nanya Technology    | 4         | 3.88%   |
| Corsair             | 3         | 2.91%   |
| A-DATA Technology   | 3         | 2.91%   |
| Ramaxel Technology  | 2         | 1.94%   |
| G.Skill             | 2         | 1.94%   |
| Crucial             | 2         | 1.94%   |
| Unknown (07FB)      | 1         | 0.97%   |
| Team                | 1         | 0.97%   |
| Smart Brazil        | 1         | 0.97%   |
| MTASE               | 1         | 0.97%   |
| JEDEC ID: 0000h     | 1         | 0.97%   |
| CSX                 | 1         | 0.97%   |
| Apacer              | 1         | 0.97%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                      | 2         | 1.8%    |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s               | 2         | 1.8%    |
| SK hynix RAM Module 8192MB SODIMM DDR4 2133MT/s                     | 2         | 1.8%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 1.8%    |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB Row Of Chips DDR4 2667MT/s        | 2         | 1.8%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 2         | 1.8%    |
| Samsung RAM M471A1K43CB1-CRC 8192MB SODIMM DDR4 2667MT/s            | 2         | 1.8%    |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s                | 2         | 1.8%    |
| Kingston RAM TF32D4U2S1MEH-8 8GB DIMM DDR4 3200MT/s                 | 2         | 1.8%    |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                         | 1         | 0.9%    |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                           | 1         | 0.9%    |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                      | 1         | 0.9%    |
| Unknown RAM Module 4GB SODIMM LPDDR3 1600MT/s                       | 1         | 0.9%    |
| Unknown RAM Module 4096MB SODIMM DDR4 2667MT/s                      | 1         | 0.9%    |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                      | 1         | 0.9%    |
| Unknown RAM Module 4096MB SODIMM DDR3                               | 1         | 0.9%    |
| Unknown RAM Module 4096MB DIMM DDR3 1067MT/s                        | 1         | 0.9%    |
| Unknown RAM Module 4096MB DIMM 667MT/s                              | 1         | 0.9%    |
| Unknown RAM Module 2GB DIMM SDRAM                                   | 1         | 0.9%    |
| Unknown RAM Module 2048MB SODIMM LPDDR3 1600MT/s                    | 1         | 0.9%    |
| Unknown RAM Module 2048MB SODIMM DDR3                               | 1         | 0.9%    |
| Unknown RAM Module 2048MB SODIMM DDR2                               | 1         | 0.9%    |
| Unknown RAM Module 1024MB SODIMM LPDDR4 2400MT/s                    | 1         | 0.9%    |
| Unknown RAM Module 1024MB SODIMM DDR2                               | 1         | 0.9%    |
| Unknown RAM 1866 CL10 Ser 8192MB DIMM DDR3 800MT/s                  | 1         | 0.9%    |
| Unknown (07FB) RAM GST32G08SCL196P-26 32GB SODIMM DDR4 2667MT/s     | 1         | 0.9%    |
| Team RAM TEAMGROUP-UD4-3200 32GB DIMM DDR4 3200MT/s                 | 1         | 0.9%    |
| Smart RAM SH564568FJ8NZRNSDR 2GB SODIMM DDR3 1600MT/s               | 1         | 0.9%    |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s               | 1         | 0.9%    |
| Smart RAM SG564568FG8NWKF-Z1 2GB SODIMM DDR2 800MT/s                | 1         | 0.9%    |
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s        | 1         | 0.9%    |
| SK hynix RAM MPPS4GBPC1600 1.35 4096MB SODIMM DDR3 1600MT/s         | 1         | 0.9%    |
| SK hynix RAM Module 4GB SODIMM DDR3 1066MT/s                        | 1         | 0.9%    |
| SK hynix RAM HMT451S6MFR8C-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 0.9%    |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 0.9%    |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s              | 1         | 0.9%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB Row Of Chips DDR4 3200MT/s     | 1         | 0.9%    |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s        | 1         | 0.9%    |
| SK hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s             | 1         | 0.9%    |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 1         | 0.9%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2400MT/s           | 1         | 0.9%    |
| SK hynix RAM H9CCNNNBJTMLAR-NUD 4096MB SODIMM LPDDR3 1867MT/s       | 1         | 0.9%    |
| SK hynix RAM H9CCNNNBJTMLAR-NUD 4096MB Row Of Chips LPDDR3 1867MT/s | 1         | 0.9%    |
| SK hynix RAM H9CCNNN8JTBLAR-NUD 2048MB LPDDR3 1600MT/s              | 1         | 0.9%    |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                      | 1         | 0.9%    |
| Samsung RAM Module 4096MB SODIMM LPDDR3 1600MT/s                    | 1         | 0.9%    |
| Samsung RAM Module 4096MB SODIMM DDR4 2666MT/s                      | 1         | 0.9%    |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s               | 1         | 0.9%    |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.9%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.9%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.9%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.9%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 0.9%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 1         | 0.9%    |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s         | 1         | 0.9%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 1         | 0.9%    |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s               | 1         | 0.9%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 1         | 0.9%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 1         | 0.9%    |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s                 | 1         | 0.9%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 47        | 51.65%  |
| DDR3    | 30        | 32.97%  |
| LPDDR3  | 6         | 6.59%   |
| LPDDR4  | 3         | 3.3%    |
| SDRAM   | 2         | 2.2%    |
| DDR2    | 2         | 2.2%    |
| Unknown | 1         | 1.1%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 59        | 64.13%  |
| DIMM         | 23        | 25%     |
| Row Of Chips | 9         | 9.78%   |
| Unknown      | 1         | 1.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 41        | 42.27%  |
| 4096  | 33        | 34.02%  |
| 2048  | 12        | 12.37%  |
| 16384 | 6         | 6.19%   |
| 1024  | 3         | 3.09%   |
| 32768 | 2         | 2.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 20        | 20.83%  |
| 2667    | 18        | 18.75%  |
| 3200    | 12        | 12.5%   |
| 2133    | 6         | 6.25%   |
| 2400    | 5         | 5.21%   |
| 1867    | 5         | 5.21%   |
| 1333    | 5         | 5.21%   |
| 1334    | 3         | 3.13%   |
| Unknown | 3         | 3.13%   |
| 3466    | 2         | 2.08%   |
| 3266    | 2         | 2.08%   |
| 2933    | 2         | 2.08%   |
| 2666    | 2         | 2.08%   |
| 1066    | 2         | 2.08%   |
| 4267    | 1         | 1.04%   |
| 4266    | 1         | 1.04%   |
| 4199    | 1         | 1.04%   |
| 3500    | 1         | 1.04%   |
| 3400    | 1         | 1.04%   |
| 2800    | 1         | 1.04%   |
| 1067    | 1         | 1.04%   |
| 800     | 1         | 1.04%   |
| 667     | 1         | 1.04%   |

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
| Chicony Electronics                    | 30        | 26.32%  |
| IMC Networks                           | 11        | 9.65%   |
| Realtek Semiconductor                  | 10        | 8.77%   |
| Microdia                               | 9         | 7.89%   |
| Silicon Motion                         | 7         | 6.14%   |
| Syntek                                 | 6         | 5.26%   |
| Suyin                                  | 5         | 4.39%   |
| Sunplus Innovation Technology          | 5         | 4.39%   |
| Logitech                               | 5         | 4.39%   |
| Quanta                                 | 4         | 3.51%   |
| Acer                                   | 4         | 3.51%   |
| Lite-On Technology                     | 3         | 2.63%   |
| Ricoh                                  | 2         | 1.75%   |
| Primax Electronics                     | 2         | 1.75%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 1.75%   |
| Alcor Micro                            | 2         | 1.75%   |
| LG Electronics                         | 1         | 0.88%   |
| Lenovo                                 | 1         | 0.88%   |
| Goodong Industry                       | 1         | 0.88%   |
| Generalplus Technology                 | 1         | 0.88%   |
| Arkmicro Technologies                  | 1         | 0.88%   |
| Apple                                  | 1         | 0.88%   |
| 2M UVC CAMERA                          | 1         | 0.88%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                             | 7         | 6.14%   |
| IMC Networks Integrated Camera                        | 5         | 4.39%   |
| IMC Networks HD Camera                                | 4         | 3.51%   |
| Chicony EasyCamera                                    | 4         | 3.51%   |
| Syntek EasyCamera                                     | 3         | 2.63%   |
| Silicon Motion Web Camera                             | 3         | 2.63%   |
| Logitech Webcam C270                                  | 3         | 2.63%   |
| Chicony TOSHIBA Web Camera - HD                       | 3         | 2.63%   |
| Syntek Integrated Camera                              | 2         | 1.75%   |
| Sunplus HD WebCam                                     | 2         | 1.75%   |
| Realtek HP "Truevision HD" laptop camera              | 2         | 1.75%   |
| Quanta HD User Facing                                 | 2         | 1.75%   |
| Primax HP HD Webcam [Fixed]                           | 2         | 1.75%   |
| Microdia Integrated_Webcam_HD                         | 2         | 1.75%   |
| Chicony HP Webcam                                     | 2         | 1.75%   |
| Chicony HP HD Webcam                                  | 2         | 1.75%   |
| Chicony HD WebCam                                     | 2         | 1.75%   |
| Acer Integrated Camera                                | 2         | 1.75%   |
| Syntek Lenovo EasyCamera                              | 1         | 0.88%   |
| Suyin Integrated_Webcam_HD                            | 1         | 0.88%   |
| Suyin HP Truevision HD                                | 1         | 0.88%   |
| Suyin HD WebCam                                       | 1         | 0.88%   |
| Suyin Acer/HP Integrated Webcam [CN0314]              | 1         | 0.88%   |
| Suyin 1.3M HD WebCam                                  | 1         | 0.88%   |
| Sunplus Integrated_Webcam_HD                          | 1         | 0.88%   |
| Sunplus HP Wide Vision HD                             | 1         | 0.88%   |
| Sunplus Asus Webcam                                   | 1         | 0.88%   |
| Silicon Motion WebCam SC-13HDL11939N                  | 1         | 0.88%   |
| Silicon Motion WebCam SC-10IRQ12340N                  | 1         | 0.88%   |
| Silicon Motion WebCam SC-0311139N                     | 1         | 0.88%   |
| Silicon Motion ATIV VGA Camera                        | 1         | 0.88%   |
| Ricoh Sony Vaio Integrated Webcam                     | 1         | 0.88%   |
| Ricoh Laptop_Integrated_Webcam_FHD                    | 1         | 0.88%   |
| Realtek USB Camera                                    | 1         | 0.88%   |
| Realtek Lenovo easy camera                            | 1         | 0.88%   |
| Realtek Laptop_Integrated_Webcam_HD                   | 1         | 0.88%   |
| Realtek Integrated_Webcam_HD                          | 1         | 0.88%   |
| Realtek Integrated_Webcam_FHD                         | 1         | 0.88%   |
| Realtek HP Wide Vision HD Camera                      | 1         | 0.88%   |
| Realtek HP Truevision HD                              | 1         | 0.88%   |
| Realtek HD WebCam                                     | 1         | 0.88%   |
| Quanta HP TrueVision HD Camera                        | 1         | 0.88%   |
| Quanta HD Webcam                                      | 1         | 0.88%   |
| Microdia Webcam SC-10HDD12636P                        | 1         | 0.88%   |
| Microdia USB 2.0 Camera                               | 1         | 0.88%   |
| Microdia Sony Visual Communication Camera             | 1         | 0.88%   |
| Microdia Sonix USB 2.0 Camera                         | 1         | 0.88%   |
| Microdia Laptop_Integrated_Webcam_HD                  | 1         | 0.88%   |
| Microdia Integrated Webcam HD                         | 1         | 0.88%   |
| Microdia Integrated HD Webcam                         | 1         | 0.88%   |
| Logitech Webcam C200                                  | 1         | 0.88%   |
| Logitech HD Pro Webcam C920                           | 1         | 0.88%   |
| Lite-On TOSHIBA Web Camera - HD                       | 1         | 0.88%   |
| Lite-On HP Webcam                                     | 1         | 0.88%   |
| Lite-On HP HD Camera                                  | 1         | 0.88%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 1         | 0.88%   |
| Lenovo Integrated Webcam [R5U877]                     | 1         | 0.88%   |
| IMC Networks USB2.0 VGA UVC WebCam                    | 1         | 0.88%   |
| IMC Networks USB2.0 HD UVC WebCam                     | 1         | 0.88%   |
| Goodong Industry USB2.0 HD UVC WebCam                 | 1         | 0.88%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 10        | 45.45%  |
| Shenzhen Goodix Technology | 6         | 27.27%  |
| Upek                       | 5         | 22.73%  |
| Elan Microelectronics      | 1         | 4.55%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 5         | 22.73%  |
| Shenzhen Goodix  FingerPrint Device                    | 4         | 18.18%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 3         | 13.64%  |
| Validity Sensors VFS491                                | 2         | 9.09%   |
| Validity Sensors Swipe Fingerprint Sensor              | 2         | 9.09%   |
| Upek TCS5B Fingerprint sensor                          | 2         | 9.09%   |
| Shenzhen Goodix Fingerprint Reader                     | 2         | 9.09%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 4.55%   |
| Elan ELAN:Fingerprint                                  | 1         | 4.55%   |

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
| 0     | 128       | 72.32%  |
| 1     | 40        | 22.6%   |
| 2     | 8         | 4.52%   |
| 3     | 1         | 0.56%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 22        | 37.29%  |
| Graphics card            | 18        | 30.51%  |
| Multimedia controller    | 5         | 8.47%   |
| Chipcard                 | 5         | 8.47%   |
| Sound                    | 3         | 5.08%   |
| Net/wireless             | 3         | 5.08%   |
| Storage                  | 1         | 1.69%   |
| Communication controller | 1         | 1.69%   |
| Camera                   | 1         | 1.69%   |

