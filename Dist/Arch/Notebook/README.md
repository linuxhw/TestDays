Arch - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------

A project to collect tested hardware configurations for Arch.

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

Total: 4297

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad S145-15IWL 81S9     | [2be076637c](https://linux-hardware.org/?probe=2be076637c) | Feb 01, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [ee219f2f82](https://linux-hardware.org/?probe=ee219f2f82) | Feb 01, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [af2f6edc6f](https://linux-hardware.org/?probe=af2f6edc6f) | Feb 01, 2023 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | [3fc59532b8](https://linux-hardware.org/?probe=3fc59532b8) | Feb 01, 2023 |
| HP            | Laptop 15s-eq3xxx           | [e9525c9a86](https://linux-hardware.org/?probe=e9525c9a86) | Jan 31, 2023 |
| HP            | Laptop 15s-eq3xxx           | [e6cb9d8296](https://linux-hardware.org/?probe=e6cb9d8296) | Jan 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [78bd5ea99c](https://linux-hardware.org/?probe=78bd5ea99c) | Jan 31, 2023 |
| Lenovo        | Legion R9000P ARH7H 82RG    | [15cda8e776](https://linux-hardware.org/?probe=15cda8e776) | Jan 30, 2023 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [0c220851f3](https://linux-hardware.org/?probe=0c220851f3) | Jan 30, 2023 |
| HP            | Laptop 15s-eq1xxx           | [9f093d7cff](https://linux-hardware.org/?probe=9f093d7cff) | Jan 30, 2023 |
| Lenovo        | Legion 7 15IMH05 81YT       | [b88f08d400](https://linux-hardware.org/?probe=b88f08d400) | Jan 29, 2023 |
| Dell          | G15 5520                    | [ae4bf1777e](https://linux-hardware.org/?probe=ae4bf1777e) | Jan 29, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [8727d22cba](https://linux-hardware.org/?probe=8727d22cba) | Jan 29, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [4603f92b18](https://linux-hardware.org/?probe=4603f92b18) | Jan 29, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [608c0b8c88](https://linux-hardware.org/?probe=608c0b8c88) | Jan 29, 2023 |
| Dell          | Latitude E6530              | [87bca9f2a4](https://linux-hardware.org/?probe=87bca9f2a4) | Jan 29, 2023 |
| Dell          | G15 5520                    | [a0c269c5b1](https://linux-hardware.org/?probe=a0c269c5b1) | Jan 28, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [85e23fef85](https://linux-hardware.org/?probe=85e23fef85) | Jan 28, 2023 |
| ASUSTek       | X555LAB                     | [343025f50f](https://linux-hardware.org/?probe=343025f50f) | Jan 28, 2023 |
| TUXEDO        | InfinityBook S 15 Gen6      | [f5ebfcecc5](https://linux-hardware.org/?probe=f5ebfcecc5) | Jan 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [56cb1ce2a6](https://linux-hardware.org/?probe=56cb1ce2a6) | Jan 27, 2023 |
| Acer          | Aspire ES1-572              | [9f745ecc18](https://linux-hardware.org/?probe=9f745ecc18) | Jan 27, 2023 |
| Acer          | Aspire E5-553G              | [e851efaf39](https://linux-hardware.org/?probe=e851efaf39) | Jan 27, 2023 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | [ff67a5eb33](https://linux-hardware.org/?probe=ff67a5eb33) | Jan 27, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [bd0b1f7e94](https://linux-hardware.org/?probe=bd0b1f7e94) | Jan 27, 2023 |
| Acer          | Aspire ES1-411              | [110767fd86](https://linux-hardware.org/?probe=110767fd86) | Jan 26, 2023 |
| Dell          | XPS 15 9500                 | [4109360c56](https://linux-hardware.org/?probe=4109360c56) | Jan 26, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [a22071f9ec](https://linux-hardware.org/?probe=a22071f9ec) | Jan 26, 2023 |
| Dell          | G3 3500                     | [ea11767144](https://linux-hardware.org/?probe=ea11767144) | Jan 26, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [4a3c63f3f0](https://linux-hardware.org/?probe=4a3c63f3f0) | Jan 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [2026175299](https://linux-hardware.org/?probe=2026175299) | Jan 26, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [702b3c77fc](https://linux-hardware.org/?probe=702b3c77fc) | Jan 25, 2023 |
| HUAWEI        | KLVL-WXX9                   | [f04915614f](https://linux-hardware.org/?probe=f04915614f) | Jan 25, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [0ef51b9eda](https://linux-hardware.org/?probe=0ef51b9eda) | Jan 25, 2023 |
| ASUSTek       | TUF Gaming FX505DY_TUF50... | [92a3e34781](https://linux-hardware.org/?probe=92a3e34781) | Jan 24, 2023 |
| MSI           | Alpha 15 B5EEK              | [d815a80782](https://linux-hardware.org/?probe=d815a80782) | Jan 24, 2023 |
| Dell          | Latitude E7470              | [5258f49771](https://linux-hardware.org/?probe=5258f49771) | Jan 24, 2023 |
| Dell          | XPS 15 9570                 | [270a9bf553](https://linux-hardware.org/?probe=270a9bf553) | Jan 24, 2023 |
| TUXEDO        | Unknown                     | [5973888b27](https://linux-hardware.org/?probe=5973888b27) | Jan 24, 2023 |
| MSI           | Alpha 15 B5EEK              | [d2c9a02f60](https://linux-hardware.org/?probe=d2c9a02f60) | Jan 24, 2023 |
| Dell          | Latitude E7470              | [647c279ad4](https://linux-hardware.org/?probe=647c279ad4) | Jan 24, 2023 |
| Dell          | XPS 13 9360                 | [fabda16ea6](https://linux-hardware.org/?probe=fabda16ea6) | Jan 23, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [4c6da4840e](https://linux-hardware.org/?probe=4c6da4840e) | Jan 23, 2023 |
| Dell          | XPS 13 9360                 | [45f94cdedc](https://linux-hardware.org/?probe=45f94cdedc) | Jan 23, 2023 |
| HP            | Laptop 15s-eq3xxx           | [b00e46e17f](https://linux-hardware.org/?probe=b00e46e17f) | Jan 23, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [85bfcb35ff](https://linux-hardware.org/?probe=85bfcb35ff) | Jan 23, 2023 |
| Fujitsu       | LIFEBOOK U9311A             | [6bdcfeae43](https://linux-hardware.org/?probe=6bdcfeae43) | Jan 23, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | [023f1e3cdc](https://linux-hardware.org/?probe=023f1e3cdc) | Jan 23, 2023 |
| HP            | Laptop 15s-eq3xxx           | [1a9aaa1cb2](https://linux-hardware.org/?probe=1a9aaa1cb2) | Jan 22, 2023 |
| HP            | Laptop 15s-eq3xxx           | [4ed27b0b56](https://linux-hardware.org/?probe=4ed27b0b56) | Jan 22, 2023 |
| Lenovo        | ThinkPad P51 20HJS16Q0K     | [00e6c3575f](https://linux-hardware.org/?probe=00e6c3575f) | Jan 22, 2023 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | [ae3846db38](https://linux-hardware.org/?probe=ae3846db38) | Jan 22, 2023 |
| Lenovo        | ThinkPad L430 2466DS2       | [8be9a889b7](https://linux-hardware.org/?probe=8be9a889b7) | Jan 22, 2023 |
| Dell          | G3 3500                     | [b3a545ee30](https://linux-hardware.org/?probe=b3a545ee30) | Jan 22, 2023 |
| HP            | Laptop 15s-eq3xxx           | [0ba680dd8f](https://linux-hardware.org/?probe=0ba680dd8f) | Jan 22, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [15b2f3fc5e](https://linux-hardware.org/?probe=15b2f3fc5e) | Jan 22, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [082d1b40bc](https://linux-hardware.org/?probe=082d1b40bc) | Jan 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [cd1f6d8306](https://linux-hardware.org/?probe=cd1f6d8306) | Jan 21, 2023 |
| Dell          | Vostro 15 3515              | [51234f64dd](https://linux-hardware.org/?probe=51234f64dd) | Jan 21, 2023 |
| Lenovo        | IdeaPad Slim 7 14ITL05 8... | [45bc9c5f3f](https://linux-hardware.org/?probe=45bc9c5f3f) | Jan 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [f33b08f626](https://linux-hardware.org/?probe=f33b08f626) | Jan 21, 2023 |
| Sony          | VPCF13Z1E                   | [3eaeffde09](https://linux-hardware.org/?probe=3eaeffde09) | Jan 21, 2023 |
| MSI           | GP66 Leopard 11UH           | [cf6837bb85](https://linux-hardware.org/?probe=cf6837bb85) | Jan 20, 2023 |
| Dell          | Vostro 5620                 | [e70af512c8](https://linux-hardware.org/?probe=e70af512c8) | Jan 20, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [169ba5d31f](https://linux-hardware.org/?probe=169ba5d31f) | Jan 20, 2023 |
| Unknown       | Unknown                     | [1de254a697](https://linux-hardware.org/?probe=1de254a697) | Jan 20, 2023 |
| Dell          | G3 3579                     | [d418b797c8](https://linux-hardware.org/?probe=d418b797c8) | Jan 20, 2023 |
| HP            | 1000                        | [62ee01ee38](https://linux-hardware.org/?probe=62ee01ee38) | Jan 20, 2023 |
| Dell          | XPS 13 7390                 | [01f3a78934](https://linux-hardware.org/?probe=01f3a78934) | Jan 19, 2023 |
| Dell          | XPS 15 9570                 | [ebd319efff](https://linux-hardware.org/?probe=ebd319efff) | Jan 19, 2023 |
| HP            | EliteBook 840 G5            | [c0667c5ea5](https://linux-hardware.org/?probe=c0667c5ea5) | Jan 18, 2023 |
| HP            | ProBook 640 G5              | [095355c9fc](https://linux-hardware.org/?probe=095355c9fc) | Jan 18, 2023 |
| Acer          | Aspire A515-51              | [1aac8c57f8](https://linux-hardware.org/?probe=1aac8c57f8) | Jan 18, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [987dcf118c](https://linux-hardware.org/?probe=987dcf118c) | Jan 17, 2023 |
| Sony          | VPCF13Z1E                   | [aa93abde02](https://linux-hardware.org/?probe=aa93abde02) | Jan 17, 2023 |
| HP            | Laptop 15s-fq2xxx           | [133972f199](https://linux-hardware.org/?probe=133972f199) | Jan 17, 2023 |
| MSI           | GP66 Leopard 11UH           | [269015d6a4](https://linux-hardware.org/?probe=269015d6a4) | Jan 17, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [8474e8ce69](https://linux-hardware.org/?probe=8474e8ce69) | Jan 17, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [a5ddfa16b9](https://linux-hardware.org/?probe=a5ddfa16b9) | Jan 17, 2023 |
| Lenovo        | ThinkPad X230 2325CW1       | [44a8ae0b56](https://linux-hardware.org/?probe=44a8ae0b56) | Jan 17, 2023 |
| BANGHO        | MOV                         | [bc4f98d4ff](https://linux-hardware.org/?probe=bc4f98d4ff) | Jan 17, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [11ca9b863c](https://linux-hardware.org/?probe=11ca9b863c) | Jan 16, 2023 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | [5b56cf615b](https://linux-hardware.org/?probe=5b56cf615b) | Jan 16, 2023 |
| MSI           | GE66 Raider 10SF            | [55f5300c59](https://linux-hardware.org/?probe=55f5300c59) | Jan 16, 2023 |
| Lenovo        | Legion R70002021 82JW       | [5e5628739f](https://linux-hardware.org/?probe=5e5628739f) | Jan 16, 2023 |
| Lenovo        | IdeaPad 5-15ARE05 81YQ      | [4c9bb70ea2](https://linux-hardware.org/?probe=4c9bb70ea2) | Jan 16, 2023 |
| Lenovo        | IdeaPad Slim 7 Carbon 14... | [620185bf98](https://linux-hardware.org/?probe=620185bf98) | Jan 15, 2023 |
| Lenovo        | ThinkPad E590 20NCS00800    | [8751d5b445](https://linux-hardware.org/?probe=8751d5b445) | Jan 15, 2023 |
| Dell          | Vostro 15 3515              | [fdf3113afb](https://linux-hardware.org/?probe=fdf3113afb) | Jan 15, 2023 |
| HP            | Pavilion Laptop 14-ce0xx... | [dd0a234ebb](https://linux-hardware.org/?probe=dd0a234ebb) | Jan 14, 2023 |
| Dell          | XPS 15 9570                 | [bff6278ed8](https://linux-hardware.org/?probe=bff6278ed8) | Jan 14, 2023 |
| HP            | Pavilion Laptop 15-cs2xx... | [e7bab74a13](https://linux-hardware.org/?probe=e7bab74a13) | Jan 13, 2023 |
| Dell          | Latitude E6430              | [5951bc10ca](https://linux-hardware.org/?probe=5951bc10ca) | Jan 13, 2023 |
| TUXEDO        | Unknown                     | [5721ffbc43](https://linux-hardware.org/?probe=5721ffbc43) | Jan 13, 2023 |
| ASUSTek       | N53SM                       | [fdf56c0639](https://linux-hardware.org/?probe=fdf56c0639) | Jan 13, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [e4912e6bfc](https://linux-hardware.org/?probe=e4912e6bfc) | Jan 12, 2023 |
| Acer          | Aspire A315-58              | [855dfb5e62](https://linux-hardware.org/?probe=855dfb5e62) | Jan 12, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [998a408a04](https://linux-hardware.org/?probe=998a408a04) | Jan 12, 2023 |
| Notebook      | NS50MU                      | [7d94a36b67](https://linux-hardware.org/?probe=7d94a36b67) | Jan 12, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [5076e36526](https://linux-hardware.org/?probe=5076e36526) | Jan 11, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [2455d11a72](https://linux-hardware.org/?probe=2455d11a72) | Jan 11, 2023 |
| Lenovo        | IdeaPad 5-15ARE05 81YQ      | [b5d071346b](https://linux-hardware.org/?probe=b5d071346b) | Jan 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [3b767cfcef](https://linux-hardware.org/?probe=3b767cfcef) | Jan 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [ac7ae437c8](https://linux-hardware.org/?probe=ac7ae437c8) | Jan 10, 2023 |
| Dell          | Latitude 3570               | [2748121a05](https://linux-hardware.org/?probe=2748121a05) | Jan 10, 2023 |
| Dell          | Inspiron 5502               | [b09655552e](https://linux-hardware.org/?probe=b09655552e) | Jan 09, 2023 |
| MSI           | Modern 14 B11MOU            | [0db2c1a27c](https://linux-hardware.org/?probe=0db2c1a27c) | Jan 09, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [b6e56e8d87](https://linux-hardware.org/?probe=b6e56e8d87) | Jan 08, 2023 |
| HP            | ZHAN 66 Pro G1              | [76e588ab0a](https://linux-hardware.org/?probe=76e588ab0a) | Jan 08, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [66ba6bf6d3](https://linux-hardware.org/?probe=66ba6bf6d3) | Jan 08, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [7a02a3b48b](https://linux-hardware.org/?probe=7a02a3b48b) | Jan 08, 2023 |
| Toshiba       | Satellite C55Dt-A           | [e7b268e7e5](https://linux-hardware.org/?probe=e7b268e7e5) | Jan 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | [14273d90fd](https://linux-hardware.org/?probe=14273d90fd) | Jan 08, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | [7ce97bb3ec](https://linux-hardware.org/?probe=7ce97bb3ec) | Jan 08, 2023 |
| Acer          | Nitro AN515-54              | [cfabe67812](https://linux-hardware.org/?probe=cfabe67812) | Jan 07, 2023 |
| HP            | Pavilion dv6                | [7e1ac76fc9](https://linux-hardware.org/?probe=7e1ac76fc9) | Jan 07, 2023 |
| HP            | ZBook 15                    | [3e2f33f6c1](https://linux-hardware.org/?probe=3e2f33f6c1) | Jan 07, 2023 |
| Dell          | Inspiron 5515               | [3b8a41b7af](https://linux-hardware.org/?probe=3b8a41b7af) | Jan 07, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [2227400f4c](https://linux-hardware.org/?probe=2227400f4c) | Jan 05, 2023 |
| Gigabyte      | AERO 16 XE4                 | [e05dd3f797](https://linux-hardware.org/?probe=e05dd3f797) | Jan 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [e4a7ff414a](https://linux-hardware.org/?probe=e4a7ff414a) | Jan 05, 2023 |
| Lenovo        | B40-70 20392                | [71c1ae09af](https://linux-hardware.org/?probe=71c1ae09af) | Jan 05, 2023 |
| MSI           | GP66 Leopard 11UH           | [63f0536a21](https://linux-hardware.org/?probe=63f0536a21) | Jan 04, 2023 |
| Valve         | Jupiter                     | [e7e5475978](https://linux-hardware.org/?probe=e7e5475978) | Jan 04, 2023 |
| MSI           | Prestige 15 A11SCX          | [86850a5925](https://linux-hardware.org/?probe=86850a5925) | Jan 04, 2023 |
| Lenovo        | ThinkPad X230 2320LFG       | [e8e510f4e6](https://linux-hardware.org/?probe=e8e510f4e6) | Jan 04, 2023 |
| Lenovo        | ThinkPad W541 20EFCTO1WW    | [a10abfb25a](https://linux-hardware.org/?probe=a10abfb25a) | Jan 03, 2023 |
| Acer          | Aspire R7-572G              | [56e5de8317](https://linux-hardware.org/?probe=56e5de8317) | Jan 03, 2023 |
| Acer          | Aspire A515-57G             | [854bee8efb](https://linux-hardware.org/?probe=854bee8efb) | Jan 02, 2023 |
| HUAWEI        | MACH-WX9                    | [525ea65bc1](https://linux-hardware.org/?probe=525ea65bc1) | Jan 02, 2023 |
| HP            | ProBook 635 Aero G8         | [f710248f3c](https://linux-hardware.org/?probe=f710248f3c) | Jan 02, 2023 |
| Toshiba       | Satellite P755              | [1296e73b50](https://linux-hardware.org/?probe=1296e73b50) | Jan 02, 2023 |
| Lenovo        | ThinkPad T480 20L5000BGE    | [acdb8c643e](https://linux-hardware.org/?probe=acdb8c643e) | Jan 02, 2023 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [0179007813](https://linux-hardware.org/?probe=0179007813) | Jan 01, 2023 |
| Acer          | Aspire A515-47              | [aaf0830ffc](https://linux-hardware.org/?probe=aaf0830ffc) | Jan 01, 2023 |
| ASUSTek       | X550VX                      | [e83ccf9576](https://linux-hardware.org/?probe=e83ccf9576) | Jan 01, 2023 |
| Dell          | Latitude E7450              | [f48717bb6f](https://linux-hardware.org/?probe=f48717bb6f) | Jan 01, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [a30f96dea4](https://linux-hardware.org/?probe=a30f96dea4) | Dec 31, 2022 |
| Dell          | Latitude E6430              | [de9b03cf29](https://linux-hardware.org/?probe=de9b03cf29) | Dec 31, 2022 |
| Dell          | Latitude 3420               | [05095533cd](https://linux-hardware.org/?probe=05095533cd) | Dec 31, 2022 |
| Dell          | G3 3579                     | [cad48f0160](https://linux-hardware.org/?probe=cad48f0160) | Dec 30, 2022 |
| HUAWEI        | BOM-WXX9                    | [4409746122](https://linux-hardware.org/?probe=4409746122) | Dec 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [d7806eec79](https://linux-hardware.org/?probe=d7806eec79) | Dec 30, 2022 |
| HP            | ProBook 430 G8 Notebook ... | [3f4178001d](https://linux-hardware.org/?probe=3f4178001d) | Dec 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [ce66958f69](https://linux-hardware.org/?probe=ce66958f69) | Dec 29, 2022 |
| Acer          | Aspire A715-41G             | [92f3c92191](https://linux-hardware.org/?probe=92f3c92191) | Dec 29, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | [587aa5f819](https://linux-hardware.org/?probe=587aa5f819) | Dec 29, 2022 |
| Lenovo        | ThinkPad E580 20KS001RIX    | [4ca01731b4](https://linux-hardware.org/?probe=4ca01731b4) | Dec 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [1cf63ef1ad](https://linux-hardware.org/?probe=1cf63ef1ad) | Dec 28, 2022 |
| Acer          | AO756                       | [d0cf64acd1](https://linux-hardware.org/?probe=d0cf64acd1) | Dec 28, 2022 |
| Acer          | Swift SF314-41              | [2923c4c0fc](https://linux-hardware.org/?probe=2923c4c0fc) | Dec 28, 2022 |
| System76      | Darter Pro                  | [a46000c111](https://linux-hardware.org/?probe=a46000c111) | Dec 28, 2022 |
| HP            | 250 G8 Notebook PC          | [7d79eadc7d](https://linux-hardware.org/?probe=7d79eadc7d) | Dec 28, 2022 |
| Lenovo        | ThinkPad P50 20EQS3BT1R     | [a86fddc0b9](https://linux-hardware.org/?probe=a86fddc0b9) | Dec 28, 2022 |
| Acer          | Aspire 5741                 | [1c41b5afb0](https://linux-hardware.org/?probe=1c41b5afb0) | Dec 27, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [d75dbe1e39](https://linux-hardware.org/?probe=d75dbe1e39) | Dec 27, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [196d570869](https://linux-hardware.org/?probe=196d570869) | Dec 26, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [c82ebf8b80](https://linux-hardware.org/?probe=c82ebf8b80) | Dec 26, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [38a87e716e](https://linux-hardware.org/?probe=38a87e716e) | Dec 26, 2022 |
| ASUSTek       | ZenBook UX425UG_Q408UG      | [9fb13764cc](https://linux-hardware.org/?probe=9fb13764cc) | Dec 26, 2022 |
| Lenovo        | ThinkPad T440p 20AW007QM... | [6e3d39b4ae](https://linux-hardware.org/?probe=6e3d39b4ae) | Dec 25, 2022 |
| ASUSTek       | GL752VW                     | [021903d3d7](https://linux-hardware.org/?probe=021903d3d7) | Dec 25, 2022 |
| WYSE          | XM CLASS                    | [948bfb388d](https://linux-hardware.org/?probe=948bfb388d) | Dec 25, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [1ae154433a](https://linux-hardware.org/?probe=1ae154433a) | Dec 24, 2022 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | [f980d6ed2e](https://linux-hardware.org/?probe=f980d6ed2e) | Dec 23, 2022 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | [a5dcdfece2](https://linux-hardware.org/?probe=a5dcdfece2) | Dec 23, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [97749ab6b4](https://linux-hardware.org/?probe=97749ab6b4) | Dec 23, 2022 |
| Google        | Babytiger                   | [352d1a547b](https://linux-hardware.org/?probe=352d1a547b) | Dec 23, 2022 |
| Google        | Babytiger                   | [4b2ae6579f](https://linux-hardware.org/?probe=4b2ae6579f) | Dec 23, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [0246231a61](https://linux-hardware.org/?probe=0246231a61) | Dec 22, 2022 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [0ee0790d0a](https://linux-hardware.org/?probe=0ee0790d0a) | Dec 22, 2022 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [c2dd6d0281](https://linux-hardware.org/?probe=c2dd6d0281) | Dec 22, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | [543b6fc9db](https://linux-hardware.org/?probe=543b6fc9db) | Dec 21, 2022 |
| Lenovo        | ThinkPad T470s 20HF003QU... | [5145350f9a](https://linux-hardware.org/?probe=5145350f9a) | Dec 21, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [95b8e650ce](https://linux-hardware.org/?probe=95b8e650ce) | Dec 21, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [5262e622da](https://linux-hardware.org/?probe=5262e622da) | Dec 21, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [d2e0ceb9a5](https://linux-hardware.org/?probe=d2e0ceb9a5) | Dec 20, 2022 |
| Lenovo        | Legion R9000P ARH7H 82RG    | [bbc48ee483](https://linux-hardware.org/?probe=bbc48ee483) | Dec 20, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [2b8c2f06eb](https://linux-hardware.org/?probe=2b8c2f06eb) | Dec 20, 2022 |
| Notebook      | PCX0DX                      | [83c28a3013](https://linux-hardware.org/?probe=83c28a3013) | Dec 20, 2022 |
| Acer          | Swift SF314-71              | [36d833d9c2](https://linux-hardware.org/?probe=36d833d9c2) | Dec 20, 2022 |
| Acer          | Swift SF314-71              | [c065eec185](https://linux-hardware.org/?probe=c065eec185) | Dec 20, 2022 |
| Lenovo        | ThinkPad P50 20EQS3BT1R     | [cd16c6fb41](https://linux-hardware.org/?probe=cd16c6fb41) | Dec 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [593cdd8cf6](https://linux-hardware.org/?probe=593cdd8cf6) | Dec 19, 2022 |
| Dell          | XPS 15 9560                 | [1f1c0123c7](https://linux-hardware.org/?probe=1f1c0123c7) | Dec 19, 2022 |
| Alienware     | x17 R1                      | [a5ff52a7ce](https://linux-hardware.org/?probe=a5ff52a7ce) | Dec 19, 2022 |
| Alienware     | x14                         | [d965b3510e](https://linux-hardware.org/?probe=d965b3510e) | Dec 19, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | [3fe5be03b1](https://linux-hardware.org/?probe=3fe5be03b1) | Dec 18, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | [b34d0f3a2c](https://linux-hardware.org/?probe=b34d0f3a2c) | Dec 18, 2022 |
| Lenovo        | Legion 7 16ARHA7 82UH       | [2a39f517ef](https://linux-hardware.org/?probe=2a39f517ef) | Dec 18, 2022 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [b0f674ae6f](https://linux-hardware.org/?probe=b0f674ae6f) | Dec 17, 2022 |
| Gigabyte      | G5 KE                       | [9ff3d65e35](https://linux-hardware.org/?probe=9ff3d65e35) | Dec 17, 2022 |
| HP            | EliteBook Folio 1040 G3     | [278cdcd567](https://linux-hardware.org/?probe=278cdcd567) | Dec 17, 2022 |
| HP            | ProBook 445 G8 Notebook ... | [87b21382ec](https://linux-hardware.org/?probe=87b21382ec) | Dec 17, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [9768b1fe82](https://linux-hardware.org/?probe=9768b1fe82) | Dec 16, 2022 |
| Dell          | Precision 5570              | [9468beba51](https://linux-hardware.org/?probe=9468beba51) | Dec 16, 2022 |
| HP            | Laptop 15-dw4xxx            | [ac9c6384ca](https://linux-hardware.org/?probe=ac9c6384ca) | Dec 16, 2022 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | [6d51ea5c76](https://linux-hardware.org/?probe=6d51ea5c76) | Dec 16, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [30fda215a5](https://linux-hardware.org/?probe=30fda215a5) | Dec 16, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [36a0b6f8d9](https://linux-hardware.org/?probe=36a0b6f8d9) | Dec 16, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [61dd034d23](https://linux-hardware.org/?probe=61dd034d23) | Dec 16, 2022 |
| HUAWEI        | KLVL-WXXW                   | [302dc680df](https://linux-hardware.org/?probe=302dc680df) | Dec 16, 2022 |
| HP            | Laptop 15-da0xxx            | [d871acfe36](https://linux-hardware.org/?probe=d871acfe36) | Dec 16, 2022 |
| HUAWEI        | KLVL-WXXW                   | [d289646ec3](https://linux-hardware.org/?probe=d289646ec3) | Dec 16, 2022 |
| Lenovo        | ThinkPad X240 20AMA40QLM    | [ec9133f05d](https://linux-hardware.org/?probe=ec9133f05d) | Dec 16, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [7ea1bad26b](https://linux-hardware.org/?probe=7ea1bad26b) | Dec 15, 2022 |
| MSI           | GL75 Leopard 10SDK          | [03dc950ee5](https://linux-hardware.org/?probe=03dc950ee5) | Dec 14, 2022 |
| Dell          | Latitude 5490               | [d05d57e241](https://linux-hardware.org/?probe=d05d57e241) | Dec 14, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21E3S... | [40cf8dd049](https://linux-hardware.org/?probe=40cf8dd049) | Dec 12, 2022 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [ed087084fb](https://linux-hardware.org/?probe=ed087084fb) | Dec 12, 2022 |
| Dell          | XPS 13 9380                 | [665b87269c](https://linux-hardware.org/?probe=665b87269c) | Dec 12, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [304bad9c19](https://linux-hardware.org/?probe=304bad9c19) | Dec 12, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [1461a09931](https://linux-hardware.org/?probe=1461a09931) | Dec 12, 2022 |
| LG Electro... | 15Z95N-G.AAC6U1             | [f8dae62b0c](https://linux-hardware.org/?probe=f8dae62b0c) | Dec 11, 2022 |
| HP            | Compaq Presario CQ71        | [57ab22c9c2](https://linux-hardware.org/?probe=57ab22c9c2) | Dec 11, 2022 |
| Sony          | VPCEB3D4R                   | [5f85b7c516](https://linux-hardware.org/?probe=5f85b7c516) | Dec 11, 2022 |
| HP            | Compaq Presario CQ71        | [b3f0bf2008](https://linux-hardware.org/?probe=b3f0bf2008) | Dec 11, 2022 |
| MSI           | Modern 14 B11MOU            | [ec8ac9bbd7](https://linux-hardware.org/?probe=ec8ac9bbd7) | Dec 11, 2022 |
| HP            | Laptop 14s-fq1xxx           | [811092647b](https://linux-hardware.org/?probe=811092647b) | Dec 11, 2022 |
| ASUSTek       | S551LN                      | [9aabc2d159](https://linux-hardware.org/?probe=9aabc2d159) | Dec 11, 2022 |
| Acer          | Swift SF314-57G             | [3ba8e00e00](https://linux-hardware.org/?probe=3ba8e00e00) | Dec 11, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [92d1403bdf](https://linux-hardware.org/?probe=92d1403bdf) | Dec 10, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [17cbc91488](https://linux-hardware.org/?probe=17cbc91488) | Dec 10, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [4b9eb9fcab](https://linux-hardware.org/?probe=4b9eb9fcab) | Dec 10, 2022 |
| Dell          | XPS 15 9500                 | [a933e298c7](https://linux-hardware.org/?probe=a933e298c7) | Dec 10, 2022 |
| Dell          | XPS 15 9500                 | [0e7dd9fbdb](https://linux-hardware.org/?probe=0e7dd9fbdb) | Dec 10, 2022 |
| Dell          | Latitude E6430              | [f28775142d](https://linux-hardware.org/?probe=f28775142d) | Dec 09, 2022 |
| Acer          | Swift SFX16-52G             | [02a7a5e487](https://linux-hardware.org/?probe=02a7a5e487) | Dec 09, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [91b65d2fa1](https://linux-hardware.org/?probe=91b65d2fa1) | Dec 09, 2022 |
| Dell          | Inspiron 3583               | [93934b74f5](https://linux-hardware.org/?probe=93934b74f5) | Dec 09, 2022 |
| Acer          | Aspire A315-55G             | [0c6e399e4f](https://linux-hardware.org/?probe=0c6e399e4f) | Dec 09, 2022 |
| Acer          | Aspire A315-55G             | [9c083ab22c](https://linux-hardware.org/?probe=9c083ab22c) | Dec 09, 2022 |
| HP            | Laptop 14s-dq1xxx           | [6af7fadd72](https://linux-hardware.org/?probe=6af7fadd72) | Dec 09, 2022 |
| HP            | Laptop 14s-dq1xxx           | [7e1510d6c6](https://linux-hardware.org/?probe=7e1510d6c6) | Dec 09, 2022 |
| HP            | EliteBook 840 G5            | [946807e266](https://linux-hardware.org/?probe=946807e266) | Dec 08, 2022 |
| Dell          | Latitude 3400               | [d01726a4d0](https://linux-hardware.org/?probe=d01726a4d0) | Dec 08, 2022 |
| MSI           | Alpha 15 A4DEK              | [d2a30990d9](https://linux-hardware.org/?probe=d2a30990d9) | Dec 08, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [8924598f09](https://linux-hardware.org/?probe=8924598f09) | Dec 08, 2022 |
| MSI           | Modern 14 B11MOU            | [426e23829e](https://linux-hardware.org/?probe=426e23829e) | Dec 08, 2022 |
| HP            | ZBook Fury 17 G7 Mobile ... | [cb45484bb6](https://linux-hardware.org/?probe=cb45484bb6) | Dec 08, 2022 |
| MSI           | Vector GP76 12UGS           | [d6c55a874f](https://linux-hardware.org/?probe=d6c55a874f) | Dec 08, 2022 |
| HP            | EliteBook 840 G5            | [bb11ec4f3f](https://linux-hardware.org/?probe=bb11ec4f3f) | Dec 08, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [ea7638c0f9](https://linux-hardware.org/?probe=ea7638c0f9) | Dec 07, 2022 |
| MSI           | Modern 14 B11MOU            | [49e70cf65f](https://linux-hardware.org/?probe=49e70cf65f) | Dec 07, 2022 |
| Positivo B... | VJFE42F11X-XXXXXX           | [8575adb47e](https://linux-hardware.org/?probe=8575adb47e) | Dec 07, 2022 |
| Dell          | Inspiron 5505               | [183c4593a7](https://linux-hardware.org/?probe=183c4593a7) | Dec 07, 2022 |
| HP            | Laptop 14s-dq2xxx           | [383bc11a0d](https://linux-hardware.org/?probe=383bc11a0d) | Dec 07, 2022 |
| Packard Be... | EasyNote LJ65               | [1ca8a161fd](https://linux-hardware.org/?probe=1ca8a161fd) | Dec 06, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | [db1a2c7a74](https://linux-hardware.org/?probe=db1a2c7a74) | Dec 06, 2022 |
| Toshiba       | Satellite R630              | [3826be6846](https://linux-hardware.org/?probe=3826be6846) | Dec 06, 2022 |
| Toshiba       | Satellite R630              | [eebafcab9e](https://linux-hardware.org/?probe=eebafcab9e) | Dec 06, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | [6ae5470891](https://linux-hardware.org/?probe=6ae5470891) | Dec 06, 2022 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [c2d30310e8](https://linux-hardware.org/?probe=c2d30310e8) | Dec 06, 2022 |
| Lenovo        | IdeaPad 1 14AMN7 82VF       | [a978cbc03b](https://linux-hardware.org/?probe=a978cbc03b) | Dec 06, 2022 |
| HP            | ProBook 6560b               | [a73750fc79](https://linux-hardware.org/?probe=a73750fc79) | Dec 06, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [dd7a026e5e](https://linux-hardware.org/?probe=dd7a026e5e) | Dec 05, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [d69f4daaa6](https://linux-hardware.org/?probe=d69f4daaa6) | Dec 05, 2022 |
| eMachines     | E520 V1.06                  | [0ef424fa9b](https://linux-hardware.org/?probe=0ef424fa9b) | Dec 05, 2022 |
| Lenovo        | ThinkPad P51 20HJS16Q0K     | [3dfd18754f](https://linux-hardware.org/?probe=3dfd18754f) | Dec 05, 2022 |
| Google        | Lick                        | [7ee6b1918e](https://linux-hardware.org/?probe=7ee6b1918e) | Dec 04, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [cf810b2e09](https://linux-hardware.org/?probe=cf810b2e09) | Dec 04, 2022 |
| Lenovo        | ThinkPad P51 20HJS1G900     | [aaf35cbcc4](https://linux-hardware.org/?probe=aaf35cbcc4) | Dec 04, 2022 |
| Acer          | Aspire A315-23              | [8c3beba1e1](https://linux-hardware.org/?probe=8c3beba1e1) | Dec 03, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [f34caf87d5](https://linux-hardware.org/?probe=f34caf87d5) | Dec 03, 2022 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | [6dbc014a04](https://linux-hardware.org/?probe=6dbc014a04) | Dec 03, 2022 |
| HONOR         | NMH-WCX9                    | [3f107d24d1](https://linux-hardware.org/?probe=3f107d24d1) | Dec 03, 2022 |
| ASUSTek       | X580VD                      | [027cd08fb1](https://linux-hardware.org/?probe=027cd08fb1) | Dec 03, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [e16c372c9c](https://linux-hardware.org/?probe=e16c372c9c) | Dec 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [c544d40ecb](https://linux-hardware.org/?probe=c544d40ecb) | Dec 02, 2022 |
| Dell          | XPS 13 9310                 | [ca1fab4db1](https://linux-hardware.org/?probe=ca1fab4db1) | Dec 02, 2022 |
| Dell          | XPS 13 9310                 | [2adab1a5b2](https://linux-hardware.org/?probe=2adab1a5b2) | Dec 02, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [ae8f8361c1](https://linux-hardware.org/?probe=ae8f8361c1) | Dec 02, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | [253135f8dc](https://linux-hardware.org/?probe=253135f8dc) | Dec 01, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [d57de89542](https://linux-hardware.org/?probe=d57de89542) | Dec 01, 2022 |
| Lenovo        | B40-70 20392                | [a527c5b6e6](https://linux-hardware.org/?probe=a527c5b6e6) | Dec 01, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFC... | [cccb2da575](https://linux-hardware.org/?probe=cccb2da575) | Dec 01, 2022 |
| ASUSTek       | E403SA                      | [d3a1f181d5](https://linux-hardware.org/?probe=d3a1f181d5) | Nov 30, 2022 |
| Positivo B... | S14SL03                     | [a42ebacec4](https://linux-hardware.org/?probe=a42ebacec4) | Nov 29, 2022 |
| MSI           | GF75 Thin 9SC               | [50a779c35d](https://linux-hardware.org/?probe=50a779c35d) | Nov 29, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [9f473cbdeb](https://linux-hardware.org/?probe=9f473cbdeb) | Nov 29, 2022 |
| Dell          | Inspiron 15-3567            | [b06377f324](https://linux-hardware.org/?probe=b06377f324) | Nov 29, 2022 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [d258962c35](https://linux-hardware.org/?probe=d258962c35) | Nov 28, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [a3c2004787](https://linux-hardware.org/?probe=a3c2004787) | Nov 28, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [ceb78dbe4e](https://linux-hardware.org/?probe=ceb78dbe4e) | Nov 28, 2022 |
| Timi          | TM1613                      | [37036a425d](https://linux-hardware.org/?probe=37036a425d) | Nov 28, 2022 |
| Dell          | G15 5520                    | [251078d1b4](https://linux-hardware.org/?probe=251078d1b4) | Nov 28, 2022 |
| HP            | Pavilion Laptop 14-ce3xx... | [ccc431ef2e](https://linux-hardware.org/?probe=ccc431ef2e) | Nov 28, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | [0d99651537](https://linux-hardware.org/?probe=0d99651537) | Nov 28, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | [3f660318ea](https://linux-hardware.org/?probe=3f660318ea) | Nov 28, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [f18a4c8031](https://linux-hardware.org/?probe=f18a4c8031) | Nov 28, 2022 |
| Acer          | Predator PH315-54           | [15909202b8](https://linux-hardware.org/?probe=15909202b8) | Nov 27, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [d8bb1b1d38](https://linux-hardware.org/?probe=d8bb1b1d38) | Nov 27, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [4825bcbe78](https://linux-hardware.org/?probe=4825bcbe78) | Nov 27, 2022 |
| Dell          | Latitude E7440              | [3709af0366](https://linux-hardware.org/?probe=3709af0366) | Nov 27, 2022 |
| Sony          | VPCEA45FG                   | [847b1cb39a](https://linux-hardware.org/?probe=847b1cb39a) | Nov 26, 2022 |
| HP            | Laptop 14s-dq1xxx           | [9b3a058fda](https://linux-hardware.org/?probe=9b3a058fda) | Nov 26, 2022 |
| ASUSTek       | K70AB                       | [8b7e3c4b9e](https://linux-hardware.org/?probe=8b7e3c4b9e) | Nov 26, 2022 |
| Dell          | Latitude 5490               | [7aedc1fbd7](https://linux-hardware.org/?probe=7aedc1fbd7) | Nov 26, 2022 |
| Lenovo        | Legion R9000P ARH7H 82RG    | [0e3f081937](https://linux-hardware.org/?probe=0e3f081937) | Nov 26, 2022 |
| MSI           | Alpha 17 B5EEK              | [0cd6df782e](https://linux-hardware.org/?probe=0cd6df782e) | Nov 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [cd9478ab62](https://linux-hardware.org/?probe=cd9478ab62) | Nov 26, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [1f2bd09174](https://linux-hardware.org/?probe=1f2bd09174) | Nov 25, 2022 |
| MSI           | Modern 14 B10MW             | [9768df6ae0](https://linux-hardware.org/?probe=9768df6ae0) | Nov 25, 2022 |
| MSI           | Modern 14 B10MW             | [1564025817](https://linux-hardware.org/?probe=1564025817) | Nov 25, 2022 |
| Acer          | Nitro AN515-52              | [c639db74cb](https://linux-hardware.org/?probe=c639db74cb) | Nov 25, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [2d1c8c7ea5](https://linux-hardware.org/?probe=2d1c8c7ea5) | Nov 24, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [ce5f08445d](https://linux-hardware.org/?probe=ce5f08445d) | Nov 24, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [4efc557c1b](https://linux-hardware.org/?probe=4efc557c1b) | Nov 24, 2022 |
| MECER         | YA13Q20-DP_PRO              | [c51a900a73](https://linux-hardware.org/?probe=c51a900a73) | Nov 23, 2022 |
| HP            | Laptop 15-dw3xxx            | [4f6911ae2c](https://linux-hardware.org/?probe=4f6911ae2c) | Nov 23, 2022 |
| MSI           | Modern 15 A5M               | [51ca9fa048](https://linux-hardware.org/?probe=51ca9fa048) | Nov 23, 2022 |
| MSI           | Modern 15 A5M               | [0ca1ce1d74](https://linux-hardware.org/?probe=0ca1ce1d74) | Nov 23, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [47d808147c](https://linux-hardware.org/?probe=47d808147c) | Nov 23, 2022 |
| Lenovo        | ThinkPad T480 20L50011US    | [2f32726e0d](https://linux-hardware.org/?probe=2f32726e0d) | Nov 23, 2022 |
| Lenovo        | ThinkPad T440p 20AWS3RJ0... | [43f6a19d9a](https://linux-hardware.org/?probe=43f6a19d9a) | Nov 22, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [65a3383e83](https://linux-hardware.org/?probe=65a3383e83) | Nov 22, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [0584338e31](https://linux-hardware.org/?probe=0584338e31) | Nov 22, 2022 |
| HP            | ProBook 6570b               | [b7bd63db1c](https://linux-hardware.org/?probe=b7bd63db1c) | Nov 22, 2022 |
| HP            | EliteBook 8460w             | [cdb72eea80](https://linux-hardware.org/?probe=cdb72eea80) | Nov 22, 2022 |
| Dell          | XPS 13 9300                 | [3f9c0d5b63](https://linux-hardware.org/?probe=3f9c0d5b63) | Nov 22, 2022 |
| ASUSTek       | GL503VS                     | [18fa411a6d](https://linux-hardware.org/?probe=18fa411a6d) | Nov 22, 2022 |
| Acer          | Nitro AN515-52              | [57b2e84560](https://linux-hardware.org/?probe=57b2e84560) | Nov 22, 2022 |
| ASUSTek       | X455YA                      | [70267d756a](https://linux-hardware.org/?probe=70267d756a) | Nov 21, 2022 |
| Acer          | Nitro AN515-52              | [308968646b](https://linux-hardware.org/?probe=308968646b) | Nov 21, 2022 |
| HP            | Pavilion Laptop 14-ce2xx... | [cd2b457ffb](https://linux-hardware.org/?probe=cd2b457ffb) | Nov 20, 2022 |
| HP            | Notebook                    | [1278403b39](https://linux-hardware.org/?probe=1278403b39) | Nov 20, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [2db5ac853d](https://linux-hardware.org/?probe=2db5ac853d) | Nov 20, 2022 |
| Dell          | XPS 9320                    | [e590d602a9](https://linux-hardware.org/?probe=e590d602a9) | Nov 19, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [7ac338ce0d](https://linux-hardware.org/?probe=7ac338ce0d) | Nov 19, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [50bd30f30d](https://linux-hardware.org/?probe=50bd30f30d) | Nov 19, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [85e0869ac9](https://linux-hardware.org/?probe=85e0869ac9) | Nov 19, 2022 |
| Dell          | Latitude E5440              | [f423bbe9b0](https://linux-hardware.org/?probe=f423bbe9b0) | Nov 19, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [865fa07274](https://linux-hardware.org/?probe=865fa07274) | Nov 19, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [68d651f36b](https://linux-hardware.org/?probe=68d651f36b) | Nov 19, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [87219ba8e3](https://linux-hardware.org/?probe=87219ba8e3) | Nov 19, 2022 |
| ASUSTek       | ZenBook UX425UG_Q408UG      | [6a39161e50](https://linux-hardware.org/?probe=6a39161e50) | Nov 19, 2022 |
| Dell          | Latitude E5440              | [0f98fe6066](https://linux-hardware.org/?probe=0f98fe6066) | Nov 18, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [0cdd3b10fc](https://linux-hardware.org/?probe=0cdd3b10fc) | Nov 18, 2022 |
| Alienware     | m17                         | [e3e14a271a](https://linux-hardware.org/?probe=e3e14a271a) | Nov 17, 2022 |
| Dell          | XPS 15 9570                 | [d62ee2298d](https://linux-hardware.org/?probe=d62ee2298d) | Nov 16, 2022 |
| Lenovo        | ThinkPad T490 20RYCTO1WW    | [69f54ed610](https://linux-hardware.org/?probe=69f54ed610) | Nov 16, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [3eaa12ef7a](https://linux-hardware.org/?probe=3eaa12ef7a) | Nov 16, 2022 |
| Apple         | MacBookPro11,4              | [91268b9919](https://linux-hardware.org/?probe=91268b9919) | Nov 16, 2022 |
| ASUSTek       | ZenBook UX425UG_Q408UG      | [e2982c0c35](https://linux-hardware.org/?probe=e2982c0c35) | Nov 16, 2022 |
| ASUSTek       | X550VX                      | [a1e3d4527c](https://linux-hardware.org/?probe=a1e3d4527c) | Nov 15, 2022 |
| Lenovo        | ThinkPad P52 20MAS70500     | [96db8793b2](https://linux-hardware.org/?probe=96db8793b2) | Nov 15, 2022 |
| Lenovo        | ThinkPad P52 20MAS70500     | [c576805c81](https://linux-hardware.org/?probe=c576805c81) | Nov 15, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [35cb137655](https://linux-hardware.org/?probe=35cb137655) | Nov 15, 2022 |
| Alienware     | m17                         | [4140c68e95](https://linux-hardware.org/?probe=4140c68e95) | Nov 15, 2022 |
| Acer          | Aspire A715-42G             | [403bc1b6b5](https://linux-hardware.org/?probe=403bc1b6b5) | Nov 14, 2022 |
| Acer          | Aspire A715-42G             | [6209796b42](https://linux-hardware.org/?probe=6209796b42) | Nov 14, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | [d28a778811](https://linux-hardware.org/?probe=d28a778811) | Nov 14, 2022 |
| Dell          | XPS 13 9380                 | [1501d641b4](https://linux-hardware.org/?probe=1501d641b4) | Nov 14, 2022 |
| Lenovo        | Legion R9000P ARH7H 82RG    | [d584008808](https://linux-hardware.org/?probe=d584008808) | Nov 14, 2022 |
| Fujitsu       | LIFEBOOK U7511              | [66656bedcf](https://linux-hardware.org/?probe=66656bedcf) | Nov 14, 2022 |
| Lenovo        | XiaoXinPro 14ACH 2021 82... | [d74b37eebb](https://linux-hardware.org/?probe=d74b37eebb) | Nov 13, 2022 |
| HP            | Laptop 14-dq2xxx            | [dcb6d439d4](https://linux-hardware.org/?probe=dcb6d439d4) | Nov 13, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CH0... | [7290725ced](https://linux-hardware.org/?probe=7290725ced) | Nov 13, 2022 |
| HONOR         | BOD-WXX9                    | [ca8b207b30](https://linux-hardware.org/?probe=ca8b207b30) | Nov 12, 2022 |
| Packard Be... | EasyNote LJ65               | [1de1737600](https://linux-hardware.org/?probe=1de1737600) | Nov 12, 2022 |
| Gigabyte      | G5 KE                       | [aefbee04fd](https://linux-hardware.org/?probe=aefbee04fd) | Nov 12, 2022 |
| Acer          | AO722                       | [5c51412f98](https://linux-hardware.org/?probe=5c51412f98) | Nov 12, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CH0... | [7fded9a538](https://linux-hardware.org/?probe=7fded9a538) | Nov 12, 2022 |
| Dell          | Inspiron 15 3511            | [361f37b08d](https://linux-hardware.org/?probe=361f37b08d) | Nov 11, 2022 |
| Google        | Blooglet                    | [bd55466988](https://linux-hardware.org/?probe=bd55466988) | Nov 11, 2022 |
| Komplett      | LAPQC71B                    | [b5ee8960c6](https://linux-hardware.org/?probe=b5ee8960c6) | Nov 11, 2022 |
| ASUSTek       | K54C                        | [e347d4a0f5](https://linux-hardware.org/?probe=e347d4a0f5) | Nov 10, 2022 |
| MSI           | GV62 8RC                    | [859227b2bb](https://linux-hardware.org/?probe=859227b2bb) | Nov 10, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [d6fd1a5ecd](https://linux-hardware.org/?probe=d6fd1a5ecd) | Nov 10, 2022 |
| Panasonic     | CF-R9KWCTDR                 | [2a414f5dc5](https://linux-hardware.org/?probe=2a414f5dc5) | Nov 10, 2022 |
| Lenovo        | ThinkPad E14 20RA004VPH     | [abbb784ea9](https://linux-hardware.org/?probe=abbb784ea9) | Nov 09, 2022 |
| MSI           | GL63 8RD                    | [e10069a2f8](https://linux-hardware.org/?probe=e10069a2f8) | Nov 09, 2022 |
| HP            | Elite x2 1012 G1            | [0847b8a5d7](https://linux-hardware.org/?probe=0847b8a5d7) | Nov 09, 2022 |
| HP            | Elite x2 1012 G1            | [a5446ab998](https://linux-hardware.org/?probe=a5446ab998) | Nov 09, 2022 |
| Dell          | XPS 15 9550                 | [6642f568d4](https://linux-hardware.org/?probe=6642f568d4) | Nov 09, 2022 |
| HP            | ProBook 430 G3              | [e69d9794fd](https://linux-hardware.org/?probe=e69d9794fd) | Nov 09, 2022 |
| DERE          | V14                         | [0431077216](https://linux-hardware.org/?probe=0431077216) | Nov 08, 2022 |
| HP            | ProBook 430 G3              | [d8bae2c402](https://linux-hardware.org/?probe=d8bae2c402) | Nov 08, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | [b4d22497e8](https://linux-hardware.org/?probe=b4d22497e8) | Nov 08, 2022 |
| Dell          | XPS 13 9310                 | [5f358af327](https://linux-hardware.org/?probe=5f358af327) | Nov 08, 2022 |
| ASUSTek       | Zenbook UM5401QA_UM5401Q... | [d19fce3e6c](https://linux-hardware.org/?probe=d19fce3e6c) | Nov 08, 2022 |
| Dell          | XPS 13 9360                 | [a35aee6ec2](https://linux-hardware.org/?probe=a35aee6ec2) | Nov 08, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [95b5d8b8ca](https://linux-hardware.org/?probe=95b5d8b8ca) | Nov 07, 2022 |
| MSI           | Modern 14 B5M               | [c2e7afc800](https://linux-hardware.org/?probe=c2e7afc800) | Nov 07, 2022 |
| Packard Be... | EasyNote LJ65               | [c75f470cf8](https://linux-hardware.org/?probe=c75f470cf8) | Nov 06, 2022 |
| Teclast       | F6 Pro                      | [bfba140f45](https://linux-hardware.org/?probe=bfba140f45) | Nov 06, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 80X4     | [0d7567fb3f](https://linux-hardware.org/?probe=0d7567fb3f) | Nov 06, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 80X4     | [c3a3d8d222](https://linux-hardware.org/?probe=c3a3d8d222) | Nov 06, 2022 |
| HP            | ProBook 6570b               | [1fec197471](https://linux-hardware.org/?probe=1fec197471) | Nov 06, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [006e91ea03](https://linux-hardware.org/?probe=006e91ea03) | Nov 06, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y3A... | [d53e6cef83](https://linux-hardware.org/?probe=d53e6cef83) | Nov 06, 2022 |
| Clevo         | Modified by dsanke          | [b0c6c10d48](https://linux-hardware.org/?probe=b0c6c10d48) | Nov 05, 2022 |
| COLORFUL      | X15 XS 22                   | [38bc70c9b2](https://linux-hardware.org/?probe=38bc70c9b2) | Nov 04, 2022 |
| COLORFUL      | X15 XS 22                   | [342a90f101](https://linux-hardware.org/?probe=342a90f101) | Nov 04, 2022 |
| Lenovo        | ThinkPad E14 20RA004VPH     | [fbe5c4578c](https://linux-hardware.org/?probe=fbe5c4578c) | Nov 04, 2022 |
| MSI           | Bravo 15 A4DDR              | [8598cf3c36](https://linux-hardware.org/?probe=8598cf3c36) | Nov 04, 2022 |
| Lenovo        | IdeaPad Creator 5 15IMH0... | [72b1a49ec9](https://linux-hardware.org/?probe=72b1a49ec9) | Nov 04, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | [eeda582315](https://linux-hardware.org/?probe=eeda582315) | Nov 04, 2022 |
| ASUSTek       | X555LJ                      | [b46456d0c2](https://linux-hardware.org/?probe=b46456d0c2) | Nov 04, 2022 |
| ASUSTek       | X555LJ                      | [e57ec28998](https://linux-hardware.org/?probe=e57ec28998) | Nov 03, 2022 |
| ASUSTek       | X550LD                      | [0847d7c7e6](https://linux-hardware.org/?probe=0847d7c7e6) | Nov 03, 2022 |
| Avell High... | B.ON                        | [f0ea745f7d](https://linux-hardware.org/?probe=f0ea745f7d) | Nov 03, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [e2f82d9c90](https://linux-hardware.org/?probe=e2f82d9c90) | Nov 03, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [ec7425c123](https://linux-hardware.org/?probe=ec7425c123) | Nov 03, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [608c7f56e6](https://linux-hardware.org/?probe=608c7f56e6) | Nov 03, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TES... | [209e99f964](https://linux-hardware.org/?probe=209e99f964) | Nov 02, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TES... | [f12fc289fa](https://linux-hardware.org/?probe=f12fc289fa) | Nov 02, 2022 |
| Lenovo        | ThinkPad L13 Gen 2 20VH0... | [de1cd69b53](https://linux-hardware.org/?probe=de1cd69b53) | Nov 02, 2022 |
| GPD           | P3 MAX                      | [8b198da775](https://linux-hardware.org/?probe=8b198da775) | Nov 02, 2022 |
| GPD           | P3 MAX                      | [aea8f8bb50](https://linux-hardware.org/?probe=aea8f8bb50) | Nov 02, 2022 |
| Notebook      | P65xHP                      | [68d40fd2c7](https://linux-hardware.org/?probe=68d40fd2c7) | Nov 02, 2022 |
| ASUSTek       | N53Jg                       | [8e4782c668](https://linux-hardware.org/?probe=8e4782c668) | Nov 01, 2022 |
| Acer          | Swift SF314-512             | [4c80b212c6](https://linux-hardware.org/?probe=4c80b212c6) | Nov 01, 2022 |
| Acer          | Swift SF314-512             | [4e92800709](https://linux-hardware.org/?probe=4e92800709) | Nov 01, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [7603f28400](https://linux-hardware.org/?probe=7603f28400) | Nov 01, 2022 |
| ASUSTek       | K54C                        | [dd4f63b1e4](https://linux-hardware.org/?probe=dd4f63b1e4) | Nov 01, 2022 |
| Avell High... | B.ON                        | [1eb1bf21ed](https://linux-hardware.org/?probe=1eb1bf21ed) | Oct 31, 2022 |
| Lenovo        | Legion Y7000 2019 1050 8... | [3821dabcb9](https://linux-hardware.org/?probe=3821dabcb9) | Oct 31, 2022 |
| HP            | ProBook 450 G6              | [224f9c8141](https://linux-hardware.org/?probe=224f9c8141) | Oct 30, 2022 |
| HP            | EliteBook 840 G5            | [f8c58b7061](https://linux-hardware.org/?probe=f8c58b7061) | Oct 30, 2022 |
| Dell          | Latitude E5430 non-vPro     | [70a0354dba](https://linux-hardware.org/?probe=70a0354dba) | Oct 30, 2022 |
| HP            | ProBook 640 G4              | [0a7776630f](https://linux-hardware.org/?probe=0a7776630f) | Oct 30, 2022 |
| Apple         | MacBookPro11,2              | [c5955c7440](https://linux-hardware.org/?probe=c5955c7440) | Oct 29, 2022 |
| MSI           | Prestige 14 A10SC           | [1504398ef8](https://linux-hardware.org/?probe=1504398ef8) | Oct 29, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [1753d78397](https://linux-hardware.org/?probe=1753d78397) | Oct 29, 2022 |
| HP            | OMEN by Laptop              | [610be75cca](https://linux-hardware.org/?probe=610be75cca) | Oct 29, 2022 |
| HP            | Pavilion dv5                | [8bd42e12c3](https://linux-hardware.org/?probe=8bd42e12c3) | Oct 29, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [be41a03a4d](https://linux-hardware.org/?probe=be41a03a4d) | Oct 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [893d006e2f](https://linux-hardware.org/?probe=893d006e2f) | Oct 29, 2022 |
| HP            | 250 G8 Notebook PC          | [59c02d4967](https://linux-hardware.org/?probe=59c02d4967) | Oct 28, 2022 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | [0dde1fbb38](https://linux-hardware.org/?probe=0dde1fbb38) | Oct 28, 2022 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | [8cf64e81cd](https://linux-hardware.org/?probe=8cf64e81cd) | Oct 28, 2022 |
| Avell High... | B.ON                        | [194a1eddc3](https://linux-hardware.org/?probe=194a1eddc3) | Oct 28, 2022 |
| HP            | 255 G8 Notebook PC          | [2ad60a938a](https://linux-hardware.org/?probe=2ad60a938a) | Oct 28, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [7d99f01f0e](https://linux-hardware.org/?probe=7d99f01f0e) | Oct 28, 2022 |
| Lenovo        | ThinkPad W540 20BHS0730D    | [f24dc12e06](https://linux-hardware.org/?probe=f24dc12e06) | Oct 28, 2022 |
| Unknown       | Unknown                     | [a03935aadd](https://linux-hardware.org/?probe=a03935aadd) | Oct 27, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [639503102e](https://linux-hardware.org/?probe=639503102e) | Oct 27, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [84acb8d19b](https://linux-hardware.org/?probe=84acb8d19b) | Oct 27, 2022 |
| Unknown       | Unknown                     | [069ce9d405](https://linux-hardware.org/?probe=069ce9d405) | Oct 27, 2022 |
| Apple         | MacBookAir7,2               | [abadd71c90](https://linux-hardware.org/?probe=abadd71c90) | Oct 27, 2022 |
| Lenovo        | ThinkPad T480s 20L8S5YM0... | [c348de09bf](https://linux-hardware.org/?probe=c348de09bf) | Oct 26, 2022 |
| Lenovo        | ThinkPad T480 20L50000IX    | [bcb1b11c50](https://linux-hardware.org/?probe=bcb1b11c50) | Oct 26, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [56c91f99e7](https://linux-hardware.org/?probe=56c91f99e7) | Oct 26, 2022 |
| HP            | 250 G8 Notebook PC          | [d4ebaa71a2](https://linux-hardware.org/?probe=d4ebaa71a2) | Oct 26, 2022 |
| Dell          | Precision 5570              | [67d7b55dab](https://linux-hardware.org/?probe=67d7b55dab) | Oct 26, 2022 |
| Timi          | A7S                         | [004df6b9a1](https://linux-hardware.org/?probe=004df6b9a1) | Oct 26, 2022 |
| Dell          | Latitude E6440              | [307356784a](https://linux-hardware.org/?probe=307356784a) | Oct 26, 2022 |
| Dell          | Latitude E5570              | [2d59f069b4](https://linux-hardware.org/?probe=2d59f069b4) | Oct 26, 2022 |
| HUAWEI        | HN-WX9X                     | [042ffc026d](https://linux-hardware.org/?probe=042ffc026d) | Oct 26, 2022 |
| Timi          | A7S                         | [77a87009dd](https://linux-hardware.org/?probe=77a87009dd) | Oct 26, 2022 |
| Apple         | MacBookPro10,1              | [212ce8900d](https://linux-hardware.org/?probe=212ce8900d) | Oct 26, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [53e6b23ebf](https://linux-hardware.org/?probe=53e6b23ebf) | Oct 26, 2022 |
| Dell          | Latitude E6430              | [f196a9762f](https://linux-hardware.org/?probe=f196a9762f) | Oct 25, 2022 |
| Dell          | Latitude E6430              | [8062ec17fd](https://linux-hardware.org/?probe=8062ec17fd) | Oct 25, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [2d7fa062e3](https://linux-hardware.org/?probe=2d7fa062e3) | Oct 25, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [cca91f3fe8](https://linux-hardware.org/?probe=cca91f3fe8) | Oct 25, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [8f34a9c24c](https://linux-hardware.org/?probe=8f34a9c24c) | Oct 25, 2022 |
| Lenovo        | ThinkPad T470 20HES0FW00    | [1f939e0414](https://linux-hardware.org/?probe=1f939e0414) | Oct 25, 2022 |
| Acer          | Aspire A715-42G             | [72b73a6552](https://linux-hardware.org/?probe=72b73a6552) | Oct 25, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [26415e4b74](https://linux-hardware.org/?probe=26415e4b74) | Oct 25, 2022 |
| Dell          | Inspiron 7559               | [2a1b8eb060](https://linux-hardware.org/?probe=2a1b8eb060) | Oct 25, 2022 |
| HP            | 255 G8 Notebook PC          | [30c305f07c](https://linux-hardware.org/?probe=30c305f07c) | Oct 25, 2022 |
| HP            | Laptop 15s-eq2xxx           | [3146a3d644](https://linux-hardware.org/?probe=3146a3d644) | Oct 25, 2022 |
| ASUSTek       | GL553VD                     | [20278229cd](https://linux-hardware.org/?probe=20278229cd) | Oct 25, 2022 |
| Acer          | Aspire A515-45              | [4584821ae6](https://linux-hardware.org/?probe=4584821ae6) | Oct 25, 2022 |
| Lenovo        | ThinkPad T495 20NJ000XIX    | [169601c723](https://linux-hardware.org/?probe=169601c723) | Oct 25, 2022 |
| Lenovo        | ThinkPad T495 20NJ000XIX    | [efb9c3d448](https://linux-hardware.org/?probe=efb9c3d448) | Oct 25, 2022 |
| Lenovo        | B51-80 80LM                 | [aaed1997fd](https://linux-hardware.org/?probe=aaed1997fd) | Oct 25, 2022 |
| Fujitsu       | LIFEBOOK A532               | [e176b2ac7c](https://linux-hardware.org/?probe=e176b2ac7c) | Oct 25, 2022 |
| Dell          | Inspiron 13-7359            | [5a6d4ce6e7](https://linux-hardware.org/?probe=5a6d4ce6e7) | Oct 25, 2022 |
| Acer          | Aspire A515-52G             | [f569841512](https://linux-hardware.org/?probe=f569841512) | Oct 24, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | [4948eb3b16](https://linux-hardware.org/?probe=4948eb3b16) | Oct 24, 2022 |
| Lenovo        | ThinkPad T480 20L5000AIX    | [43650773c9](https://linux-hardware.org/?probe=43650773c9) | Oct 24, 2022 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | [d663683611](https://linux-hardware.org/?probe=d663683611) | Oct 24, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [417beae8e5](https://linux-hardware.org/?probe=417beae8e5) | Oct 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | [7733e4f8d5](https://linux-hardware.org/?probe=7733e4f8d5) | Oct 24, 2022 |
| Acer          | Aspire A315-42              | [20dcade848](https://linux-hardware.org/?probe=20dcade848) | Oct 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | [d4c62f39e3](https://linux-hardware.org/?probe=d4c62f39e3) | Oct 24, 2022 |
| Acer          | Aspire A515-45              | [b39d63f4f2](https://linux-hardware.org/?probe=b39d63f4f2) | Oct 24, 2022 |
| ASUSTek       | K54C                        | [acf64b4ced](https://linux-hardware.org/?probe=acf64b4ced) | Oct 24, 2022 |
| Apple         | MacBookAir7,2               | [d7e99b5869](https://linux-hardware.org/?probe=d7e99b5869) | Oct 24, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [c24c3f0836](https://linux-hardware.org/?probe=c24c3f0836) | Oct 23, 2022 |
| Dell          | Vostro 3491                 | [8809be3a93](https://linux-hardware.org/?probe=8809be3a93) | Oct 23, 2022 |
| Lenovo        | ThinkPad T460s 20FAS6EH0... | [794fa1859f](https://linux-hardware.org/?probe=794fa1859f) | Oct 23, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | [e21d202e50](https://linux-hardware.org/?probe=e21d202e50) | Oct 22, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [514642847b](https://linux-hardware.org/?probe=514642847b) | Oct 22, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | [a22e54462c](https://linux-hardware.org/?probe=a22e54462c) | Oct 21, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [07acd27a70](https://linux-hardware.org/?probe=07acd27a70) | Oct 21, 2022 |
| HP            | EliteBook 840 G1            | [837845f259](https://linux-hardware.org/?probe=837845f259) | Oct 20, 2022 |
| Dell          | Latitude E6500              | [d64ffd6f2e](https://linux-hardware.org/?probe=d64ffd6f2e) | Oct 20, 2022 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | [1a99b642cc](https://linux-hardware.org/?probe=1a99b642cc) | Oct 20, 2022 |
| HP            | ZBook Firefly 15 inch G8... | [4c0b27f18e](https://linux-hardware.org/?probe=4c0b27f18e) | Oct 20, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [7cd6e349f0](https://linux-hardware.org/?probe=7cd6e349f0) | Oct 20, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [d042d922e5](https://linux-hardware.org/?probe=d042d922e5) | Oct 20, 2022 |
| HP            | 250 G8 Notebook PC          | [e8dc04cc0e](https://linux-hardware.org/?probe=e8dc04cc0e) | Oct 20, 2022 |
| Dell          | Inspiron 5584               | [79ec522ef8](https://linux-hardware.org/?probe=79ec522ef8) | Oct 20, 2022 |
| HP            | Pavilion dm4                | [d96f382cc2](https://linux-hardware.org/?probe=d96f382cc2) | Oct 19, 2022 |
| HP            | Pavilion dm4                | [171745a6e8](https://linux-hardware.org/?probe=171745a6e8) | Oct 19, 2022 |
| Dell          | Inspiron 5584               | [4dac48ea7f](https://linux-hardware.org/?probe=4dac48ea7f) | Oct 19, 2022 |
| MOTILE        | M141                        | [a6da22306f](https://linux-hardware.org/?probe=a6da22306f) | Oct 19, 2022 |
| Acer          | Aspire A515-51              | [0022d7c5ef](https://linux-hardware.org/?probe=0022d7c5ef) | Oct 19, 2022 |
| HP            | 255 G8 Notebook PC          | [2f69a96661](https://linux-hardware.org/?probe=2f69a96661) | Oct 18, 2022 |
| Samsung       | 270E5J/2570EJ               | [f2750b0a70](https://linux-hardware.org/?probe=f2750b0a70) | Oct 18, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [8bc82af4e5](https://linux-hardware.org/?probe=8bc82af4e5) | Oct 18, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [437cb780cb](https://linux-hardware.org/?probe=437cb780cb) | Oct 18, 2022 |
| Avell High... | B.ON                        | [fc8b4d7534](https://linux-hardware.org/?probe=fc8b4d7534) | Oct 18, 2022 |
| Dell          | Vostro 7580                 | [69cc3a8c62](https://linux-hardware.org/?probe=69cc3a8c62) | Oct 18, 2022 |
| HP            | 255 G8 Notebook PC          | [cb651a5071](https://linux-hardware.org/?probe=cb651a5071) | Oct 17, 2022 |
| Lenovo        | ThinkPad T470s 20HGS1R90... | [e3eba59f05](https://linux-hardware.org/?probe=e3eba59f05) | Oct 17, 2022 |
| MECHREVO      | Code01 Ver2.0               | [5fbae9cfcf](https://linux-hardware.org/?probe=5fbae9cfcf) | Oct 17, 2022 |
| Timi          | Xiaomi Book Pro 14 2022     | [18e52559a4](https://linux-hardware.org/?probe=18e52559a4) | Oct 17, 2022 |
| Samsung       | 950XDB/951XDB/950XDY        | [e39622cea9](https://linux-hardware.org/?probe=e39622cea9) | Oct 17, 2022 |
| Dell          | Inspiron 3521               | [f7b9f3cab2](https://linux-hardware.org/?probe=f7b9f3cab2) | Oct 17, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [e38add57d6](https://linux-hardware.org/?probe=e38add57d6) | Oct 17, 2022 |
| Lenovo        | ThinkPad P50 20EQS6DV00     | [472b64041d](https://linux-hardware.org/?probe=472b64041d) | Oct 16, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [babb66e9c9](https://linux-hardware.org/?probe=babb66e9c9) | Oct 16, 2022 |
| Alienware     | m15 R6                      | [3cb0cb3e9d](https://linux-hardware.org/?probe=3cb0cb3e9d) | Oct 15, 2022 |
| Acer          | Aspire A515-45              | [7a8b3b953d](https://linux-hardware.org/?probe=7a8b3b953d) | Oct 15, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [d56a8a035a](https://linux-hardware.org/?probe=d56a8a035a) | Oct 15, 2022 |
| HP            | ProBook 445 G8 Notebook ... | [6adb156840](https://linux-hardware.org/?probe=6adb156840) | Oct 15, 2022 |
| Dell          | Precision M4500             | [36048a8407](https://linux-hardware.org/?probe=36048a8407) | Oct 15, 2022 |
| Lenovo        | ThinkPad L420 78545EG       | [d2c975644c](https://linux-hardware.org/?probe=d2c975644c) | Oct 15, 2022 |
| ASUSTek       | X553MA                      | [ade1f0f879](https://linux-hardware.org/?probe=ade1f0f879) | Oct 14, 2022 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [fbb018d1ef](https://linux-hardware.org/?probe=fbb018d1ef) | Oct 14, 2022 |
| Dell          | Precision M4800             | [aa9a1680fd](https://linux-hardware.org/?probe=aa9a1680fd) | Oct 14, 2022 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | [973f501233](https://linux-hardware.org/?probe=973f501233) | Oct 13, 2022 |
| Lenovo        | ThinkPad X201 3680FAG       | [f80eb01da1](https://linux-hardware.org/?probe=f80eb01da1) | Oct 13, 2022 |
| HP            | ProBook 640 G4              | [3d832d1780](https://linux-hardware.org/?probe=3d832d1780) | Oct 12, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [d3ade506f7](https://linux-hardware.org/?probe=d3ade506f7) | Oct 12, 2022 |
| Acer          | Nitro AN515-52              | [212c135857](https://linux-hardware.org/?probe=212c135857) | Oct 12, 2022 |
| Lenovo        | ThinkBook 14 G4+ IAP 21C... | [8b554dcfe0](https://linux-hardware.org/?probe=8b554dcfe0) | Oct 12, 2022 |
| Dell          | Latitude E6420              | [0083bd14b8](https://linux-hardware.org/?probe=0083bd14b8) | Oct 12, 2022 |
| Unknown       | Unknown                     | [ac743b08fa](https://linux-hardware.org/?probe=ac743b08fa) | Oct 11, 2022 |
| Acer          | Aspire E5-551               | [9d281c015c](https://linux-hardware.org/?probe=9d281c015c) | Oct 11, 2022 |
| Acer          | Aspire E5-551               | [6c351b94ff](https://linux-hardware.org/?probe=6c351b94ff) | Oct 11, 2022 |
| Lenovo        | ThinkPad X201 3680FAG       | [f44ca565c1](https://linux-hardware.org/?probe=f44ca565c1) | Oct 11, 2022 |
| AMI           | Cherry Trail CR             | [7d3c652547](https://linux-hardware.org/?probe=7d3c652547) | Oct 11, 2022 |
| Lenovo        | ThinkPad T410 2522E38       | [7d923eff3f](https://linux-hardware.org/?probe=7d923eff3f) | Oct 11, 2022 |
| Acer          | Nitro AN515-52              | [8e1e663189](https://linux-hardware.org/?probe=8e1e663189) | Oct 10, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [d6e11d36a8](https://linux-hardware.org/?probe=d6e11d36a8) | Oct 10, 2022 |
| Framework     | Laptop                      | [b5fe425089](https://linux-hardware.org/?probe=b5fe425089) | Oct 10, 2022 |
| HP            | EliteBook 8730w             | [e7545a94b2](https://linux-hardware.org/?probe=e7545a94b2) | Oct 09, 2022 |
| HP            | EliteBook 8730w             | [b938a96086](https://linux-hardware.org/?probe=b938a96086) | Oct 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [62e134c294](https://linux-hardware.org/?probe=62e134c294) | Oct 09, 2022 |
| Dell          | XPS 13 9370                 | [17f73f4f28](https://linux-hardware.org/?probe=17f73f4f28) | Oct 09, 2022 |
| Timi          | Mi Laptop Pro 15            | [f756c2bb92](https://linux-hardware.org/?probe=f756c2bb92) | Oct 09, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | [a431b20f04](https://linux-hardware.org/?probe=a431b20f04) | Oct 07, 2022 |
| Acer          | Aspire A515-57G             | [f8d3a419e6](https://linux-hardware.org/?probe=f8d3a419e6) | Oct 07, 2022 |
| Fujitsu       | LIFEBOOK LH531              | [5ace2d0c1f](https://linux-hardware.org/?probe=5ace2d0c1f) | Oct 06, 2022 |
| MSI           | Modern 15 A5M               | [035a9bb7fa](https://linux-hardware.org/?probe=035a9bb7fa) | Oct 05, 2022 |
| Fujitsu       | LIFEBOOK LH531              | [3338607f1a](https://linux-hardware.org/?probe=3338607f1a) | Oct 05, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [74130061ff](https://linux-hardware.org/?probe=74130061ff) | Oct 05, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [72a5f6b03c](https://linux-hardware.org/?probe=72a5f6b03c) | Oct 05, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [a51c98849b](https://linux-hardware.org/?probe=a51c98849b) | Oct 05, 2022 |
| Dell          | XPS 15 9570                 | [0edf82b5be](https://linux-hardware.org/?probe=0edf82b5be) | Oct 05, 2022 |
| Avell High... | B.ON                        | [2b629889c7](https://linux-hardware.org/?probe=2b629889c7) | Oct 05, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [a4b830a39b](https://linux-hardware.org/?probe=a4b830a39b) | Oct 04, 2022 |
| Acer          | Aspire ES1-572              | [1bd18c9a15](https://linux-hardware.org/?probe=1bd18c9a15) | Oct 04, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | [62b67bffae](https://linux-hardware.org/?probe=62b67bffae) | Oct 04, 2022 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | [e07e70b822](https://linux-hardware.org/?probe=e07e70b822) | Oct 04, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [790114327c](https://linux-hardware.org/?probe=790114327c) | Oct 04, 2022 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | [85bcec60e7](https://linux-hardware.org/?probe=85bcec60e7) | Oct 04, 2022 |
| Dell          | XPS 13 9300                 | [00ecde42a1](https://linux-hardware.org/?probe=00ecde42a1) | Oct 02, 2022 |
| UNOWHY        | Y13G012S4EI                 | [5c4c517651](https://linux-hardware.org/?probe=5c4c517651) | Oct 02, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [9a2de7b77f](https://linux-hardware.org/?probe=9a2de7b77f) | Oct 02, 2022 |
| UNOWHY        | Y13G012S4EI                 | [014d8c23f8](https://linux-hardware.org/?probe=014d8c23f8) | Oct 01, 2022 |
| Google        | Blooglet                    | [0081fa7064](https://linux-hardware.org/?probe=0081fa7064) | Oct 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | [0a022a22c6](https://linux-hardware.org/?probe=0a022a22c6) | Oct 01, 2022 |
| HP            | 655                         | [6b10f9eda8](https://linux-hardware.org/?probe=6b10f9eda8) | Oct 01, 2022 |
| Dell          | Inspiron 5567               | [82e89b9263](https://linux-hardware.org/?probe=82e89b9263) | Oct 01, 2022 |
| Dell          | Inspiron 5567               | [e64a9cf0e2](https://linux-hardware.org/?probe=e64a9cf0e2) | Oct 01, 2022 |
| Toshiba       | PORTEGE Z10t-A              | [1aa913c010](https://linux-hardware.org/?probe=1aa913c010) | Oct 01, 2022 |
| Acer          | Swift SF314-43              | [cfd0c22e29](https://linux-hardware.org/?probe=cfd0c22e29) | Sep 30, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | [71ef5c4f0e](https://linux-hardware.org/?probe=71ef5c4f0e) | Sep 30, 2022 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | [16f1ddb076](https://linux-hardware.org/?probe=16f1ddb076) | Sep 30, 2022 |
| Dell          | XPS 13 7390                 | [c4ccdf9992](https://linux-hardware.org/?probe=c4ccdf9992) | Sep 30, 2022 |
| Lenovo        | ThinkPad E590 20NB002AMB    | [0c8a6ce686](https://linux-hardware.org/?probe=0c8a6ce686) | Sep 29, 2022 |
| TUXEDO        | Book_XA1510                 | [f39b64916d](https://linux-hardware.org/?probe=f39b64916d) | Sep 29, 2022 |
| Lenovo        | ThinkPad T430 23501K0       | [124afba97e](https://linux-hardware.org/?probe=124afba97e) | Sep 28, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [fbc4f29134](https://linux-hardware.org/?probe=fbc4f29134) | Sep 28, 2022 |
| Lenovo        | Legion R70002021 82JW       | [b12e5d06a3](https://linux-hardware.org/?probe=b12e5d06a3) | Sep 28, 2022 |
| Lenovo        | ThinkPad T440s 20ARS06C0... | [a5aa60c709](https://linux-hardware.org/?probe=a5aa60c709) | Sep 28, 2022 |
| Lenovo        | IdeaPad Z510 20287          | [d4797ada2a](https://linux-hardware.org/?probe=d4797ada2a) | Sep 28, 2022 |
| Dell          | XPS 13 9310                 | [4073c084df](https://linux-hardware.org/?probe=4073c084df) | Sep 28, 2022 |
| ASUSTek       | Zenbook UM5401QA_UM5401Q... | [04fbd64661](https://linux-hardware.org/?probe=04fbd64661) | Sep 27, 2022 |
| HP            | Laptop 15-dw3xxx            | [d7dcd834e2](https://linux-hardware.org/?probe=d7dcd834e2) | Sep 27, 2022 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | [56131c4db0](https://linux-hardware.org/?probe=56131c4db0) | Sep 27, 2022 |
| Timi          | TM1604                      | [2ee795db1a](https://linux-hardware.org/?probe=2ee795db1a) | Sep 27, 2022 |
| Lenovo        | V15-ADA 82C7                | [e53b87c0fd](https://linux-hardware.org/?probe=e53b87c0fd) | Sep 26, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [95c0fd6047](https://linux-hardware.org/?probe=95c0fd6047) | Sep 26, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [d9187e470e](https://linux-hardware.org/?probe=d9187e470e) | Sep 26, 2022 |
| Dell          | G15 5511                    | [f960f38940](https://linux-hardware.org/?probe=f960f38940) | Sep 26, 2022 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [109d0ef34c](https://linux-hardware.org/?probe=109d0ef34c) | Sep 26, 2022 |
| MSI           | GS65 Stealth 9SE            | [0c8e0eb1f5](https://linux-hardware.org/?probe=0c8e0eb1f5) | Sep 26, 2022 |
| Dell          | Inspiron 5570               | [6af4756d35](https://linux-hardware.org/?probe=6af4756d35) | Sep 25, 2022 |
| MECHREVO      | Code01 Ver2.0               | [18246c5a9e](https://linux-hardware.org/?probe=18246c5a9e) | Sep 25, 2022 |
| Dell          | XPS 15 9510                 | [1ccf6c5c41](https://linux-hardware.org/?probe=1ccf6c5c41) | Sep 25, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [bdc8453efc](https://linux-hardware.org/?probe=bdc8453efc) | Sep 24, 2022 |
| Acer          | Aspire A314-22              | [31b11c4544](https://linux-hardware.org/?probe=31b11c4544) | Sep 24, 2022 |
| Dell          | Precision 7560              | [8124a7a3eb](https://linux-hardware.org/?probe=8124a7a3eb) | Sep 24, 2022 |
| Lenovo        | ThinkPad P52s 20LCS03L38    | [5d9c8cd268](https://linux-hardware.org/?probe=5d9c8cd268) | Sep 23, 2022 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | [0121aac33a](https://linux-hardware.org/?probe=0121aac33a) | Sep 22, 2022 |
| Samsung       | 950XDB/951XDB/950XDY        | [672d6f2fc8](https://linux-hardware.org/?probe=672d6f2fc8) | Sep 22, 2022 |
| HP            | Laptop 15-bs1xx             | [5657597c18](https://linux-hardware.org/?probe=5657597c18) | Sep 22, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [52bb32a60c](https://linux-hardware.org/?probe=52bb32a60c) | Sep 21, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [0be5b29760](https://linux-hardware.org/?probe=0be5b29760) | Sep 21, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [628fd0d32d](https://linux-hardware.org/?probe=628fd0d32d) | Sep 21, 2022 |
| ASUSTek       | K46CB                       | [88cbbeaee6](https://linux-hardware.org/?probe=88cbbeaee6) | Sep 20, 2022 |
| Valve         | Jupiter                     | [3aeb184ce4](https://linux-hardware.org/?probe=3aeb184ce4) | Sep 20, 2022 |
| HP            | EliteBook 850 G3            | [7bbcf621e1](https://linux-hardware.org/?probe=7bbcf621e1) | Sep 20, 2022 |
| Dell          | Inspiron 5570               | [16d661b4e5](https://linux-hardware.org/?probe=16d661b4e5) | Sep 20, 2022 |
| Lenovo        | Legion R70002021 82JW       | [b84e8d2682](https://linux-hardware.org/?probe=b84e8d2682) | Sep 20, 2022 |
| Lenovo        | Legion R70002021 82JW       | [4779dfc2b0](https://linux-hardware.org/?probe=4779dfc2b0) | Sep 20, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U1S... | [e33202084e](https://linux-hardware.org/?probe=e33202084e) | Sep 20, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [b07937de6a](https://linux-hardware.org/?probe=b07937de6a) | Sep 20, 2022 |
| HP            | Dev One Notebook PC         | [97426638ff](https://linux-hardware.org/?probe=97426638ff) | Sep 20, 2022 |
| HP            | Dev One Notebook PC         | [5367a8e71f](https://linux-hardware.org/?probe=5367a8e71f) | Sep 20, 2022 |
| Dell          | Latitude 7390               | [268add52b3](https://linux-hardware.org/?probe=268add52b3) | Sep 19, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [e149495b74](https://linux-hardware.org/?probe=e149495b74) | Sep 19, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [f454a8f6a5](https://linux-hardware.org/?probe=f454a8f6a5) | Sep 19, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [3862ccf53f](https://linux-hardware.org/?probe=3862ccf53f) | Sep 19, 2022 |
| Acer          | Swift SF314-42              | [f52b35d82d](https://linux-hardware.org/?probe=f52b35d82d) | Sep 19, 2022 |
| Dell          | XPS 13 9305                 | [9d61a37458](https://linux-hardware.org/?probe=9d61a37458) | Sep 19, 2022 |
| Dell          | Inspiron 5566               | [58d84150d6](https://linux-hardware.org/?probe=58d84150d6) | Sep 18, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [cd1441d5a4](https://linux-hardware.org/?probe=cd1441d5a4) | Sep 18, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [dce5b5917c](https://linux-hardware.org/?probe=dce5b5917c) | Sep 18, 2022 |
| HP            | Victus by Laptop 16-d0xx... | [aa3908e5fc](https://linux-hardware.org/?probe=aa3908e5fc) | Sep 17, 2022 |
| HP            | EliteBook 840 G5            | [eb488dae73](https://linux-hardware.org/?probe=eb488dae73) | Sep 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [abca74f17e](https://linux-hardware.org/?probe=abca74f17e) | Sep 17, 2022 |
| HP            | EliteBook 840 G5            | [eb406c0e81](https://linux-hardware.org/?probe=eb406c0e81) | Sep 15, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [a26e1ad502](https://linux-hardware.org/?probe=a26e1ad502) | Sep 15, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [6ff152e455](https://linux-hardware.org/?probe=6ff152e455) | Sep 15, 2022 |
| HUAWEI        | KLVD-WXX9                   | [9e0c10b8e3](https://linux-hardware.org/?probe=9e0c10b8e3) | Sep 14, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [d0d43b3cc5](https://linux-hardware.org/?probe=d0d43b3cc5) | Sep 14, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U4S... | [b7ed5c7f4a](https://linux-hardware.org/?probe=b7ed5c7f4a) | Sep 14, 2022 |
| HP            | EliteBook 840 G5            | [6b6e4efdfc](https://linux-hardware.org/?probe=6b6e4efdfc) | Sep 13, 2022 |
| Samsung       | 950XED                      | [f8a15210f0](https://linux-hardware.org/?probe=f8a15210f0) | Sep 13, 2022 |
| ASUSTek       | X555LJ                      | [5d27ea49aa](https://linux-hardware.org/?probe=5d27ea49aa) | Sep 13, 2022 |
| Toshiba       | Satellite U845W             | [030a371841](https://linux-hardware.org/?probe=030a371841) | Sep 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [410b905321](https://linux-hardware.org/?probe=410b905321) | Sep 11, 2022 |
| MECHREVO      | Code01 Ver2.0               | [c55fd8d477](https://linux-hardware.org/?probe=c55fd8d477) | Sep 11, 2022 |
| MSI           | Alpha 15 B5EEK              | [c59ebfd9e8](https://linux-hardware.org/?probe=c59ebfd9e8) | Sep 11, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [46c51b7097](https://linux-hardware.org/?probe=46c51b7097) | Sep 11, 2022 |
| Dell          | Latitude 7424 Rugged Ext... | [0e5e98a9e2](https://linux-hardware.org/?probe=0e5e98a9e2) | Sep 11, 2022 |
| HP            | 255 G8 Notebook PC          | [d2c057ed6e](https://linux-hardware.org/?probe=d2c057ed6e) | Sep 11, 2022 |
| Lenovo        | ThinkPad T430 23444ZG       | [d83eee9752](https://linux-hardware.org/?probe=d83eee9752) | Sep 11, 2022 |
| Samsung       | 750XED                      | [ea68f0910d](https://linux-hardware.org/?probe=ea68f0910d) | Sep 10, 2022 |
| Samsung       | 750XED                      | [475088329e](https://linux-hardware.org/?probe=475088329e) | Sep 10, 2022 |
| Framework     | Laptop                      | [b0b7801b11](https://linux-hardware.org/?probe=b0b7801b11) | Sep 10, 2022 |
| Lenovo        | ThinkPad X230 23252QG       | [4146ff55f9](https://linux-hardware.org/?probe=4146ff55f9) | Sep 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [3c214d75b2](https://linux-hardware.org/?probe=3c214d75b2) | Sep 10, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [4911a898bd](https://linux-hardware.org/?probe=4911a898bd) | Sep 09, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [f5c538e2c7](https://linux-hardware.org/?probe=f5c538e2c7) | Sep 09, 2022 |
| Lenovo        | Legion Y7000P-1060 81LF     | [b018911117](https://linux-hardware.org/?probe=b018911117) | Sep 09, 2022 |
| Medion        | S4216                       | [1f1e6b24bf](https://linux-hardware.org/?probe=1f1e6b24bf) | Sep 08, 2022 |
| Dell          | Latitude 7350               | [4a30d9431e](https://linux-hardware.org/?probe=4a30d9431e) | Sep 08, 2022 |
| Google        | Rabbid                      | [636b8205ae](https://linux-hardware.org/?probe=636b8205ae) | Sep 08, 2022 |
| Google        | Rabbid                      | [f33074ee09](https://linux-hardware.org/?probe=f33074ee09) | Sep 08, 2022 |
| LG Electro... | 17Z90P-G.AA86D              | [1f304e9792](https://linux-hardware.org/?probe=1f304e9792) | Sep 07, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [a5fdc97073](https://linux-hardware.org/?probe=a5fdc97073) | Sep 07, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [e88363a341](https://linux-hardware.org/?probe=e88363a341) | Sep 07, 2022 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | [ec22409311](https://linux-hardware.org/?probe=ec22409311) | Sep 07, 2022 |
| Acer          | Aspire A315-34              | [893afb133c](https://linux-hardware.org/?probe=893afb133c) | Sep 06, 2022 |
| Acer          | Aspire A515-44G             | [a4f8e52425](https://linux-hardware.org/?probe=a4f8e52425) | Sep 06, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [3ce6c0f44c](https://linux-hardware.org/?probe=3ce6c0f44c) | Sep 06, 2022 |
| Acer          | Aspire A515-44G             | [0daca2662d](https://linux-hardware.org/?probe=0daca2662d) | Sep 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [d55d359a3e](https://linux-hardware.org/?probe=d55d359a3e) | Sep 05, 2022 |
| Dell          | Latitude E6520              | [e37ba07a92](https://linux-hardware.org/?probe=e37ba07a92) | Sep 05, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [92d04feeca](https://linux-hardware.org/?probe=92d04feeca) | Sep 05, 2022 |
| Dell          | Precision 3571              | [d9939fbfd4](https://linux-hardware.org/?probe=d9939fbfd4) | Sep 05, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | [e12af15c84](https://linux-hardware.org/?probe=e12af15c84) | Sep 05, 2022 |
| Google        | Coral                       | [af898f9be4](https://linux-hardware.org/?probe=af898f9be4) | Sep 05, 2022 |
| Acer          | Swift SF314-41              | [aa90cb0d30](https://linux-hardware.org/?probe=aa90cb0d30) | Sep 04, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [c9d51bfae8](https://linux-hardware.org/?probe=c9d51bfae8) | Sep 04, 2022 |
| Acer          | Swift SF314-41              | [1394aca8b2](https://linux-hardware.org/?probe=1394aca8b2) | Sep 03, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [e30f86bc30](https://linux-hardware.org/?probe=e30f86bc30) | Sep 03, 2022 |
| Dell          | Latitude 7350               | [f52406cbf2](https://linux-hardware.org/?probe=f52406cbf2) | Sep 03, 2022 |
| Dell          | XPS 15 9570                 | [b313706909](https://linux-hardware.org/?probe=b313706909) | Sep 03, 2022 |
| TUXEDO        | Book_XA1510                 | [e379f966da](https://linux-hardware.org/?probe=e379f966da) | Sep 03, 2022 |
| Apple         | MacBook5,1                  | [0f5aab705f](https://linux-hardware.org/?probe=0f5aab705f) | Sep 03, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [6b62abaaaf](https://linux-hardware.org/?probe=6b62abaaaf) | Sep 03, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ec466abbf7](https://linux-hardware.org/?probe=ec466abbf7) | Sep 03, 2022 |
| HP            | 15                          | [48493c0282](https://linux-hardware.org/?probe=48493c0282) | Sep 03, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [c073d9fb9f](https://linux-hardware.org/?probe=c073d9fb9f) | Sep 03, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [2199481d0a](https://linux-hardware.org/?probe=2199481d0a) | Sep 03, 2022 |
| Lenovo        | ThinkPad L390 20NSS11E00    | [d5dbbd658f](https://linux-hardware.org/?probe=d5dbbd658f) | Sep 03, 2022 |
| ASUSTek       | N501VW                      | [e7e5ddf474](https://linux-hardware.org/?probe=e7e5ddf474) | Sep 03, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [7c04c344cb](https://linux-hardware.org/?probe=7c04c344cb) | Sep 02, 2022 |
| Dell          | Inspiron 5577               | [b06eacf424](https://linux-hardware.org/?probe=b06eacf424) | Sep 02, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [cd935b0146](https://linux-hardware.org/?probe=cd935b0146) | Sep 02, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [b91c67af87](https://linux-hardware.org/?probe=b91c67af87) | Sep 02, 2022 |
| Dell          | XPS 15 9520                 | [f1cfdb5e32](https://linux-hardware.org/?probe=f1cfdb5e32) | Sep 02, 2022 |
| Acer          | Aspire 5742                 | [fadbc676b4](https://linux-hardware.org/?probe=fadbc676b4) | Sep 02, 2022 |
| Toshiba       | Satellite C55D-B            | [4f9267de27](https://linux-hardware.org/?probe=4f9267de27) | Sep 02, 2022 |
| MECHREVO      | Code01 Ver2.0               | [6456a1b04f](https://linux-hardware.org/?probe=6456a1b04f) | Sep 02, 2022 |
| Acer          | Aspire 4349                 | [1918459ea4](https://linux-hardware.org/?probe=1918459ea4) | Sep 02, 2022 |
| MECHREVO      | Code01 Ver2.0               | [f88772c4dc](https://linux-hardware.org/?probe=f88772c4dc) | Sep 01, 2022 |
| Purism        | Librem 14                   | [54d6cbb49d](https://linux-hardware.org/?probe=54d6cbb49d) | Sep 01, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [c9841acd77](https://linux-hardware.org/?probe=c9841acd77) | Sep 01, 2022 |
| HUAWEI        | HKD-WXX                     | [7ff88a93c2](https://linux-hardware.org/?probe=7ff88a93c2) | Sep 01, 2022 |
| MECHREVO      | Code01 Ver2.0               | [bbe5fe0eac](https://linux-hardware.org/?probe=bbe5fe0eac) | Aug 31, 2022 |
| Toshiba       | TECRA S5                    | [121c8e110b](https://linux-hardware.org/?probe=121c8e110b) | Aug 31, 2022 |
| Toshiba       | TECRA S5                    | [6ec2bd9539](https://linux-hardware.org/?probe=6ec2bd9539) | Aug 31, 2022 |
| Notebook      | NH5xAx                      | [e8487cd15f](https://linux-hardware.org/?probe=e8487cd15f) | Aug 31, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | [ef34b3c3aa](https://linux-hardware.org/?probe=ef34b3c3aa) | Aug 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [3d7c0ee13d](https://linux-hardware.org/?probe=3d7c0ee13d) | Aug 30, 2022 |
| ASUSTek       | E202SA                      | [393cb25da2](https://linux-hardware.org/?probe=393cb25da2) | Aug 30, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [b4a9d1fecc](https://linux-hardware.org/?probe=b4a9d1fecc) | Aug 30, 2022 |
| HP            | EliteBook 820 G3            | [4ea311ca8e](https://linux-hardware.org/?probe=4ea311ca8e) | Aug 30, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [c44a50e117](https://linux-hardware.org/?probe=c44a50e117) | Aug 29, 2022 |
| MSI           | Modern 14 B10MW             | [c107217cf8](https://linux-hardware.org/?probe=c107217cf8) | Aug 28, 2022 |
| Framework     | Laptop                      | [71c896cd39](https://linux-hardware.org/?probe=71c896cd39) | Aug 28, 2022 |
| Dell          | Inspiron 5577               | [b40621d5f6](https://linux-hardware.org/?probe=b40621d5f6) | Aug 28, 2022 |
| Fujitsu Si... | ESPRIMO Mobile U9210        | [1d29556c76](https://linux-hardware.org/?probe=1d29556c76) | Aug 28, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [d056fbc982](https://linux-hardware.org/?probe=d056fbc982) | Aug 28, 2022 |
| BBEN          | G16                         | [6b0b170e1c](https://linux-hardware.org/?probe=6b0b170e1c) | Aug 28, 2022 |
| BBEN          | G16                         | [66fc9bd46b](https://linux-hardware.org/?probe=66fc9bd46b) | Aug 28, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [aa84c700c6](https://linux-hardware.org/?probe=aa84c700c6) | Aug 28, 2022 |
| Dell          | Latitude 3150               | [09f1514148](https://linux-hardware.org/?probe=09f1514148) | Aug 27, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [8841ba5f53](https://linux-hardware.org/?probe=8841ba5f53) | Aug 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X435... | [02c6bde77b](https://linux-hardware.org/?probe=02c6bde77b) | Aug 27, 2022 |
| Dell          | Latitude 7350               | [c784fd2743](https://linux-hardware.org/?probe=c784fd2743) | Aug 26, 2022 |
| Acer          | Aspire A515-45              | [c0b89ea222](https://linux-hardware.org/?probe=c0b89ea222) | Aug 26, 2022 |
| Lenovo        | ThinkPad T430 2344BMU       | [c164d20c15](https://linux-hardware.org/?probe=c164d20c15) | Aug 26, 2022 |
| Dell          | Latitude 7424 Rugged Ext... | [9770e301cd](https://linux-hardware.org/?probe=9770e301cd) | Aug 26, 2022 |
| HUAWEI        | KLVL-WXX9                   | [fcfd89bb32](https://linux-hardware.org/?probe=fcfd89bb32) | Aug 25, 2022 |
| ASUSTek       | X580VD                      | [c579b49e4c](https://linux-hardware.org/?probe=c579b49e4c) | Aug 25, 2022 |
| HP            | ZBook 15 G6                 | [e51675ce88](https://linux-hardware.org/?probe=e51675ce88) | Aug 24, 2022 |
| ASUSTek       | X751LD                      | [7ce95dab0a](https://linux-hardware.org/?probe=7ce95dab0a) | Aug 24, 2022 |
| Acer          | Swift SF114-33              | [115ca42bb8](https://linux-hardware.org/?probe=115ca42bb8) | Aug 24, 2022 |
| Dell          | XPS L421X                   | [227df9dc9e](https://linux-hardware.org/?probe=227df9dc9e) | Aug 24, 2022 |
| Acer          | Nitro AN515-45              | [98c26372c2](https://linux-hardware.org/?probe=98c26372c2) | Aug 23, 2022 |
| LG Electro... | S430-G.BC33P1               | [d0b4cf47fe](https://linux-hardware.org/?probe=d0b4cf47fe) | Aug 23, 2022 |
| Acer          | Swift SF114-33              | [0ab380f8ac](https://linux-hardware.org/?probe=0ab380f8ac) | Aug 23, 2022 |
| MSI           | GS73VR 6RF                  | [870534e620](https://linux-hardware.org/?probe=870534e620) | Aug 23, 2022 |
| MSI           | GL75 Leopard 10SDK          | [7004b23b33](https://linux-hardware.org/?probe=7004b23b33) | Aug 23, 2022 |
| Dell          | XPS 15 9570                 | [6cc47c9a0d](https://linux-hardware.org/?probe=6cc47c9a0d) | Aug 23, 2022 |
| Dell          | Latitude 7390               | [0d626db6e1](https://linux-hardware.org/?probe=0d626db6e1) | Aug 22, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [d08e00053f](https://linux-hardware.org/?probe=d08e00053f) | Aug 22, 2022 |
| Toshiba       | Satellite P55t-C            | [70560700a6](https://linux-hardware.org/?probe=70560700a6) | Aug 22, 2022 |
| ASUSTek       | X555UB                      | [a1db92c63c](https://linux-hardware.org/?probe=a1db92c63c) | Aug 22, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [cb533d9c12](https://linux-hardware.org/?probe=cb533d9c12) | Aug 22, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [ada7663387](https://linux-hardware.org/?probe=ada7663387) | Aug 21, 2022 |
| SLIMBOOK      | PROX14-AMD                  | [f01fb4784c](https://linux-hardware.org/?probe=f01fb4784c) | Aug 21, 2022 |
| HP            | Laptop 14-dk1xxx            | [4875c1533b](https://linux-hardware.org/?probe=4875c1533b) | Aug 21, 2022 |
| BBEN          | G16                         | [f9768aedb9](https://linux-hardware.org/?probe=f9768aedb9) | Aug 21, 2022 |
| BBEN          | G16                         | [d491f08ce0](https://linux-hardware.org/?probe=d491f08ce0) | Aug 21, 2022 |
| HP            | Pavilion g4                 | [f8c2fc628e](https://linux-hardware.org/?probe=f8c2fc628e) | Aug 21, 2022 |
| Acer          | Aspire E5-575               | [8b1a8497c7](https://linux-hardware.org/?probe=8b1a8497c7) | Aug 21, 2022 |
| Acer          | Aspire A315-23G             | [e31fb3f3cf](https://linux-hardware.org/?probe=e31fb3f3cf) | Aug 21, 2022 |
| HP            | ENVY 15                     | [5d984dedf6](https://linux-hardware.org/?probe=5d984dedf6) | Aug 20, 2022 |
| MSI           | Modern 14 B5M               | [9a8166de9b](https://linux-hardware.org/?probe=9a8166de9b) | Aug 20, 2022 |
| realme        | RMNBXXXX                    | [d98be8821f](https://linux-hardware.org/?probe=d98be8821f) | Aug 20, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [4f711bf806](https://linux-hardware.org/?probe=4f711bf806) | Aug 20, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [c6bb19402d](https://linux-hardware.org/?probe=c6bb19402d) | Aug 19, 2022 |
| HP            | EliteBook 840 G6            | [8af519565f](https://linux-hardware.org/?probe=8af519565f) | Aug 18, 2022 |
| Dell          | Inspiron 5558               | [b4bc42c01c](https://linux-hardware.org/?probe=b4bc42c01c) | Aug 18, 2022 |
| Framework     | Laptop                      | [a8988f1665](https://linux-hardware.org/?probe=a8988f1665) | Aug 18, 2022 |
| Dell          | Latitude 7390               | [d726450b55](https://linux-hardware.org/?probe=d726450b55) | Aug 18, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | [0dbc32a26d](https://linux-hardware.org/?probe=0dbc32a26d) | Aug 17, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U2S... | [ff64bb7593](https://linux-hardware.org/?probe=ff64bb7593) | Aug 17, 2022 |
| TPVAOC        | AA183M                      | [089472ea13](https://linux-hardware.org/?probe=089472ea13) | Aug 16, 2022 |
| Dell          | Vostro 2420                 | [1d2b1aa4bf](https://linux-hardware.org/?probe=1d2b1aa4bf) | Aug 16, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [eb37729065](https://linux-hardware.org/?probe=eb37729065) | Aug 16, 2022 |
| HP            | ENVY m7                     | [9142b4fff0](https://linux-hardware.org/?probe=9142b4fff0) | Aug 16, 2022 |
| ASUSTek       | TUF Gaming FX705GE_FX705... | [6132aea83b](https://linux-hardware.org/?probe=6132aea83b) | Aug 16, 2022 |
| Lenovo        | IdeaPad 5-15ARE05 81YQ      | [0a48289c39](https://linux-hardware.org/?probe=0a48289c39) | Aug 16, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [35cd057234](https://linux-hardware.org/?probe=35cd057234) | Aug 16, 2022 |
| Acer          | Celadon-RN                  | [043b0c9fd7](https://linux-hardware.org/?probe=043b0c9fd7) | Aug 15, 2022 |
| Dell          | Vostro 7500                 | [94309eee94](https://linux-hardware.org/?probe=94309eee94) | Aug 15, 2022 |
| HP            | EliteBook 845 14 inch G9... | [4e05ac232c](https://linux-hardware.org/?probe=4e05ac232c) | Aug 15, 2022 |
| Dell          | Vostro 7500                 | [3e084bba8b](https://linux-hardware.org/?probe=3e084bba8b) | Aug 15, 2022 |
| HP            | ENVY Laptop 13-aq0xxx       | [1db8ed0da4](https://linux-hardware.org/?probe=1db8ed0da4) | Aug 14, 2022 |
| HP            | ENVY Laptop 13-aq0xxx       | [105367d5d6](https://linux-hardware.org/?probe=105367d5d6) | Aug 14, 2022 |
| Lenovo        | Y70-70 Touch 80DU           | [7817924a07](https://linux-hardware.org/?probe=7817924a07) | Aug 14, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [97f75c2be0](https://linux-hardware.org/?probe=97f75c2be0) | Aug 13, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1C00... | [dbbae31450](https://linux-hardware.org/?probe=dbbae31450) | Aug 13, 2022 |
| HP            | 250 G6 Notebook PC          | [ee2f627cb6](https://linux-hardware.org/?probe=ee2f627cb6) | Aug 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [26c131aca1](https://linux-hardware.org/?probe=26c131aca1) | Aug 13, 2022 |
| ASUSTek       | GL552VX                     | [16c1976ac6](https://linux-hardware.org/?probe=16c1976ac6) | Aug 12, 2022 |
| Lenovo        | ThinkBook 14s-IWL 20RM      | [0045f412a9](https://linux-hardware.org/?probe=0045f412a9) | Aug 12, 2022 |
| Dell          | XPS 13 9360                 | [a78c885366](https://linux-hardware.org/?probe=a78c885366) | Aug 12, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [e3be6b79c1](https://linux-hardware.org/?probe=e3be6b79c1) | Aug 12, 2022 |
| Acer          | Predator PH315-52           | [fad6aace6a](https://linux-hardware.org/?probe=fad6aace6a) | Aug 11, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [69843536ef](https://linux-hardware.org/?probe=69843536ef) | Aug 11, 2022 |
| HP            | ProBook 640 G5              | [321cb5faf4](https://linux-hardware.org/?probe=321cb5faf4) | Aug 11, 2022 |
| HP            | ProBook 640 G5              | [b71c89e139](https://linux-hardware.org/?probe=b71c89e139) | Aug 11, 2022 |
| HP            | Pavilion Gaming Notebook    | [673ef8a276](https://linux-hardware.org/?probe=673ef8a276) | Aug 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [d61320f9c5](https://linux-hardware.org/?probe=d61320f9c5) | Aug 11, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [bc7a8afe56](https://linux-hardware.org/?probe=bc7a8afe56) | Aug 11, 2022 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | [27b3fb870a](https://linux-hardware.org/?probe=27b3fb870a) | Aug 11, 2022 |
| HP            | Laptop 17-cn0xxx            | [94a67b764b](https://linux-hardware.org/?probe=94a67b764b) | Aug 11, 2022 |
| Dell          | XPS 13 9380                 | [534c1142c2](https://linux-hardware.org/?probe=534c1142c2) | Aug 10, 2022 |
| Dell          | XPS 13 9380                 | [0724d34f68](https://linux-hardware.org/?probe=0724d34f68) | Aug 10, 2022 |
| HP            | EliteBook 845 14 inch G9... | [644f2ccaaf](https://linux-hardware.org/?probe=644f2ccaaf) | Aug 10, 2022 |
| Lenovo        | IdeaPad Y410P 20216         | [df3068aea1](https://linux-hardware.org/?probe=df3068aea1) | Aug 10, 2022 |
| MSI           | GP66 Leopard 11UH           | [a85b442a71](https://linux-hardware.org/?probe=a85b442a71) | Aug 09, 2022 |
| HP            | Laptop 14-fq0xxx            | [598febc046](https://linux-hardware.org/?probe=598febc046) | Aug 09, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [a4e02af6d9](https://linux-hardware.org/?probe=a4e02af6d9) | Aug 09, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [fc8542afef](https://linux-hardware.org/?probe=fc8542afef) | Aug 09, 2022 |
| Alienware     | x15 R1                      | [59b6412e2f](https://linux-hardware.org/?probe=59b6412e2f) | Aug 09, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [1636ef38d5](https://linux-hardware.org/?probe=1636ef38d5) | Aug 09, 2022 |
| HP            | EliteBook 840 G5            | [16b59e0aae](https://linux-hardware.org/?probe=16b59e0aae) | Aug 08, 2022 |
| HP            | ZBook 15 G6                 | [f833eca9da](https://linux-hardware.org/?probe=f833eca9da) | Aug 08, 2022 |
| Lenovo        | IdeaPad 330s-15ARR 81FB     | [4546912e7b](https://linux-hardware.org/?probe=4546912e7b) | Aug 08, 2022 |
| Lenovo        | Legion R70002021 82JW       | [949598482f](https://linux-hardware.org/?probe=949598482f) | Aug 07, 2022 |
| HUAWEI        | CREM-WXX9                   | [409cc97b53](https://linux-hardware.org/?probe=409cc97b53) | Aug 07, 2022 |
| HP            | Laptop 15s-gr0xxx           | [457fa11671](https://linux-hardware.org/?probe=457fa11671) | Aug 07, 2022 |
| Lenovo        | ThinkPad E14 20RA004WUS     | [b140ac0aea](https://linux-hardware.org/?probe=b140ac0aea) | Aug 07, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [3f71cac385](https://linux-hardware.org/?probe=3f71cac385) | Aug 06, 2022 |
| Acer          | Predator G3-571             | [e5e720b21b](https://linux-hardware.org/?probe=e5e720b21b) | Aug 06, 2022 |
| MECHREVO      | Code 01 Series PF5NU1G      | [3c42214ad0](https://linux-hardware.org/?probe=3c42214ad0) | Aug 06, 2022 |
| Lenovo        | ThinkPad T61 6457VE6        | [a6a1de13e4](https://linux-hardware.org/?probe=a6a1de13e4) | Aug 05, 2022 |
| HP            | ZBook 15 G6                 | [034cd98301](https://linux-hardware.org/?probe=034cd98301) | Aug 05, 2022 |
| Dell          | Latitude E5440              | [7d828eb093](https://linux-hardware.org/?probe=7d828eb093) | Aug 05, 2022 |
| Lenovo        | Legion R70002021 82JW       | [7a3c7a2886](https://linux-hardware.org/?probe=7a3c7a2886) | Aug 04, 2022 |
| ASUSTek       | GL752VW                     | [ff8fd29d96](https://linux-hardware.org/?probe=ff8fd29d96) | Aug 03, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [900f1d3f01](https://linux-hardware.org/?probe=900f1d3f01) | Aug 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [4c75e1d374](https://linux-hardware.org/?probe=4c75e1d374) | Aug 03, 2022 |
| ASUSTek       | G550JK                      | [76414b53ee](https://linux-hardware.org/?probe=76414b53ee) | Aug 03, 2022 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | [66c117c18e](https://linux-hardware.org/?probe=66c117c18e) | Aug 03, 2022 |
| HP            | EliteBook 840 G5            | [62a6f6b85a](https://linux-hardware.org/?probe=62a6f6b85a) | Aug 02, 2022 |
| HP            | EliteBook 840 G5            | [f93096f2ff](https://linux-hardware.org/?probe=f93096f2ff) | Aug 02, 2022 |
| HP            | OMEN by Laptop 16-b0xxx     | [9beb1b8221](https://linux-hardware.org/?probe=9beb1b8221) | Aug 02, 2022 |
| Lenovo        | ThinkPad Edge E431 62771... | [563bd9cecd](https://linux-hardware.org/?probe=563bd9cecd) | Aug 02, 2022 |
| TUXEDO        | Pulse 15 Gen2               | [e650b177cc](https://linux-hardware.org/?probe=e650b177cc) | Aug 02, 2022 |
| Lenovo        | ThinkPad E14 20RAS0KX00     | [d9c5b6d4c5](https://linux-hardware.org/?probe=d9c5b6d4c5) | Aug 02, 2022 |
| HP            | Stream Laptop 14-ds0xxx     | [a008ad925d](https://linux-hardware.org/?probe=a008ad925d) | Aug 01, 2022 |
| Acidanther... | MacBookPro13,1              | [5c8158f059](https://linux-hardware.org/?probe=5c8158f059) | Aug 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [d77ac14ae9](https://linux-hardware.org/?probe=d77ac14ae9) | Aug 01, 2022 |
| Lenovo        | ThinkPad T420 4180LN1       | [65d5b19d40](https://linux-hardware.org/?probe=65d5b19d40) | Aug 01, 2022 |
| Lenovo        | ThinkPad T420 4180LN1       | [35304c2321](https://linux-hardware.org/?probe=35304c2321) | Aug 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [b2385a694b](https://linux-hardware.org/?probe=b2385a694b) | Jul 31, 2022 |
| Toshiba       | dynabook Satellite B35/R    | [4600fb0c71](https://linux-hardware.org/?probe=4600fb0c71) | Jul 31, 2022 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | [d3b270c068](https://linux-hardware.org/?probe=d3b270c068) | Jul 31, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [97f6892c6c](https://linux-hardware.org/?probe=97f6892c6c) | Jul 30, 2022 |
| Acer          | Nitro AN515-55              | [3b08b42260](https://linux-hardware.org/?probe=3b08b42260) | Jul 30, 2022 |
| Dell          | Inspiron N4010              | [7589775fb4](https://linux-hardware.org/?probe=7589775fb4) | Jul 30, 2022 |
| Lenovo        | ThinkPad E480 20KN001QRT    | [e0e0792a71](https://linux-hardware.org/?probe=e0e0792a71) | Jul 30, 2022 |
| Clevo         | W150HNM/W170HN              | [31c83153b5](https://linux-hardware.org/?probe=31c83153b5) | Jul 29, 2022 |
| MSI           | GF75 Thin 9SC               | [a6113f2e35](https://linux-hardware.org/?probe=a6113f2e35) | Jul 29, 2022 |
| Toshiba       | Satellite L70-B             | [bee2cdca79](https://linux-hardware.org/?probe=bee2cdca79) | Jul 29, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [ef7aa9cb2e](https://linux-hardware.org/?probe=ef7aa9cb2e) | Jul 29, 2022 |
| Dell          | Latitude 5480               | [2e2d540cb0](https://linux-hardware.org/?probe=2e2d540cb0) | Jul 29, 2022 |
| Framework     | Laptop                      | [626e3266c7](https://linux-hardware.org/?probe=626e3266c7) | Jul 29, 2022 |
| HP            | ZBook 15v G5                | [b08d670a98](https://linux-hardware.org/?probe=b08d670a98) | Jul 28, 2022 |
| HP            | 255 G7 Notebook PC          | [bc1a82a647](https://linux-hardware.org/?probe=bc1a82a647) | Jul 28, 2022 |
| Dell          | XPS 15 9500                 | [e5d7cc54e7](https://linux-hardware.org/?probe=e5d7cc54e7) | Jul 28, 2022 |
| Timi          | TM1703                      | [b3c578658f](https://linux-hardware.org/?probe=b3c578658f) | Jul 28, 2022 |
| Acer          | Aspire A715-42G             | [8d87e3bb3b](https://linux-hardware.org/?probe=8d87e3bb3b) | Jul 28, 2022 |
| Lenovo        | ThinkPad X230 2325TXV       | [2c5c6ba837](https://linux-hardware.org/?probe=2c5c6ba837) | Jul 28, 2022 |
| Apple         | MacBookAir7,2               | [b547e23eb1](https://linux-hardware.org/?probe=b547e23eb1) | Jul 28, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [7d9d58c2da](https://linux-hardware.org/?probe=7d9d58c2da) | Jul 27, 2022 |
| Dell          | G5 5590                     | [ae478a8f82](https://linux-hardware.org/?probe=ae478a8f82) | Jul 27, 2022 |
| Samsung       | 935XDB                      | [d6149a337b](https://linux-hardware.org/?probe=d6149a337b) | Jul 26, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | [75c2236b06](https://linux-hardware.org/?probe=75c2236b06) | Jul 26, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | [6577d30f3e](https://linux-hardware.org/?probe=6577d30f3e) | Jul 26, 2022 |
| Alienware     | m15 R4                      | [2f80ebdd19](https://linux-hardware.org/?probe=2f80ebdd19) | Jul 26, 2022 |
| Dell          | Precision 7560              | [2fdcece648](https://linux-hardware.org/?probe=2fdcece648) | Jul 25, 2022 |
| Dell          | Precision 7560              | [02fb353f1e](https://linux-hardware.org/?probe=02fb353f1e) | Jul 25, 2022 |
| Dell          | Vostro 3491                 | [6ce65dccb7](https://linux-hardware.org/?probe=6ce65dccb7) | Jul 24, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [ce2ecc0fd8](https://linux-hardware.org/?probe=ce2ecc0fd8) | Jul 24, 2022 |
| Timi          | RedmiBook 14 II             | [cd8d5a1ee6](https://linux-hardware.org/?probe=cd8d5a1ee6) | Jul 24, 2022 |
| Lenovo        | ThinkPad X280 20KES2SN00    | [202423ba73](https://linux-hardware.org/?probe=202423ba73) | Jul 24, 2022 |
| Google        | Wolf                        | [f2397aadef](https://linux-hardware.org/?probe=f2397aadef) | Jul 23, 2022 |
| Google        | Wolf                        | [ffa74c4dc0](https://linux-hardware.org/?probe=ffa74c4dc0) | Jul 23, 2022 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | [492b4e1236](https://linux-hardware.org/?probe=492b4e1236) | Jul 23, 2022 |
| ASUSTek       | X555LD                      | [bc783f5d64](https://linux-hardware.org/?probe=bc783f5d64) | Jul 23, 2022 |
| Apple         | MacBookAir7,1               | [51d002e1b7](https://linux-hardware.org/?probe=51d002e1b7) | Jul 23, 2022 |
| Apple         | MacBookAir7,1               | [41d0e95039](https://linux-hardware.org/?probe=41d0e95039) | Jul 23, 2022 |
| Timi          | Redmi Book Pro 15 2022      | [3428364c49](https://linux-hardware.org/?probe=3428364c49) | Jul 22, 2022 |
| Acer          | Nitro AN515-55              | [85f2ffe45a](https://linux-hardware.org/?probe=85f2ffe45a) | Jul 22, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [b8ce5a0377](https://linux-hardware.org/?probe=b8ce5a0377) | Jul 22, 2022 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | [02dd3c2357](https://linux-hardware.org/?probe=02dd3c2357) | Jul 21, 2022 |
| Samsung       | 935XDB                      | [e01b518899](https://linux-hardware.org/?probe=e01b518899) | Jul 21, 2022 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [8505a7d575](https://linux-hardware.org/?probe=8505a7d575) | Jul 21, 2022 |
| Lenovo        | Legion Y7000P 2019 81Q5     | [d101f95ac2](https://linux-hardware.org/?probe=d101f95ac2) | Jul 20, 2022 |
| Lenovo        | V570 HuronRiver Platform    | [7e317412e0](https://linux-hardware.org/?probe=7e317412e0) | Jul 20, 2022 |
| HP            | ProBook 640 G5              | [36a725c595](https://linux-hardware.org/?probe=36a725c595) | Jul 19, 2022 |
| MSI           | Stealth GS77 12UGS          | [8d6d581aac](https://linux-hardware.org/?probe=8d6d581aac) | Jul 19, 2022 |
| Acer          | Aspire A515-45              | [323aa03c61](https://linux-hardware.org/?probe=323aa03c61) | Jul 18, 2022 |
| ASUSTek       | GL752VW                     | [b13a184720](https://linux-hardware.org/?probe=b13a184720) | Jul 18, 2022 |
| HP            | ZHAN 99 Mobile Workstati... | [cafc6119f3](https://linux-hardware.org/?probe=cafc6119f3) | Jul 18, 2022 |
| MSI           | GS75 Stealth 9SF            | [24e8aca8d1](https://linux-hardware.org/?probe=24e8aca8d1) | Jul 17, 2022 |
| System76      | Lemur Pro                   | [a4adde6cf9](https://linux-hardware.org/?probe=a4adde6cf9) | Jul 17, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [321c1a6e7a](https://linux-hardware.org/?probe=321c1a6e7a) | Jul 17, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [03839f9fef](https://linux-hardware.org/?probe=03839f9fef) | Jul 17, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | [ebcca43b7f](https://linux-hardware.org/?probe=ebcca43b7f) | Jul 17, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | [e94cde9ec6](https://linux-hardware.org/?probe=e94cde9ec6) | Jul 17, 2022 |
| Dell          | Latitude E6540              | [595eeced49](https://linux-hardware.org/?probe=595eeced49) | Jul 16, 2022 |
| Dell          | Latitude E6540              | [804dad339b](https://linux-hardware.org/?probe=804dad339b) | Jul 16, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [a6e936c29d](https://linux-hardware.org/?probe=a6e936c29d) | Jul 16, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [d465259da1](https://linux-hardware.org/?probe=d465259da1) | Jul 16, 2022 |
| HP            | ProBook 640 G5              | [93e838afb1](https://linux-hardware.org/?probe=93e838afb1) | Jul 16, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [1dc42453a1](https://linux-hardware.org/?probe=1dc42453a1) | Jul 15, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [164d1ff988](https://linux-hardware.org/?probe=164d1ff988) | Jul 15, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [e4530dd7b4](https://linux-hardware.org/?probe=e4530dd7b4) | Jul 15, 2022 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [c475c84f19](https://linux-hardware.org/?probe=c475c84f19) | Jul 15, 2022 |
| HP            | EliteBook 8570w             | [c21885de7f](https://linux-hardware.org/?probe=c21885de7f) | Jul 15, 2022 |
| MSI           | Stealth GS77 12UGS          | [b5f57e7b95](https://linux-hardware.org/?probe=b5f57e7b95) | Jul 14, 2022 |
| Hyperbook     | Z15 Zen                     | [41129ecc5e](https://linux-hardware.org/?probe=41129ecc5e) | Jul 14, 2022 |
| Dell          | Inspiron 7570               | [872ca81b40](https://linux-hardware.org/?probe=872ca81b40) | Jul 13, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [896226e566](https://linux-hardware.org/?probe=896226e566) | Jul 13, 2022 |
| Lenovo        | ThinkPad T430 2349CV8       | [fac90d81d0](https://linux-hardware.org/?probe=fac90d81d0) | Jul 13, 2022 |
| HP            | Pavilion Laptop 13-an0xx... | [6021e75347](https://linux-hardware.org/?probe=6021e75347) | Jul 13, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [eb05f4aed9](https://linux-hardware.org/?probe=eb05f4aed9) | Jul 13, 2022 |
| Toshiba       | Satellite M645              | [0149367a4e](https://linux-hardware.org/?probe=0149367a4e) | Jul 12, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [eac5600627](https://linux-hardware.org/?probe=eac5600627) | Jul 12, 2022 |
| Notebook      | NL5xRU                      | [a4bc7e790c](https://linux-hardware.org/?probe=a4bc7e790c) | Jul 11, 2022 |
| HP            | ProBook 440 G6              | [6a065093ba](https://linux-hardware.org/?probe=6a065093ba) | Jul 10, 2022 |
| Acer          | Nitro AN515-44              | [1478a70c4b](https://linux-hardware.org/?probe=1478a70c4b) | Jul 10, 2022 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [de4d640168](https://linux-hardware.org/?probe=de4d640168) | Jul 10, 2022 |
| Acer          | Nitro AN515-45              | [a9dd7c4072](https://linux-hardware.org/?probe=a9dd7c4072) | Jul 08, 2022 |
| ASUSTek       | U36SG                       | [878e0283d9](https://linux-hardware.org/?probe=878e0283d9) | Jul 08, 2022 |
| ASUSTek       | GL702VSK                    | [4fe32d25e5](https://linux-hardware.org/?probe=4fe32d25e5) | Jul 08, 2022 |
| Apple         | MacBookPro12,1              | [62fb099dfd](https://linux-hardware.org/?probe=62fb099dfd) | Jul 07, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [92b59598e5](https://linux-hardware.org/?probe=92b59598e5) | Jul 06, 2022 |
| MSI           | GP66 Leopard 10UH           | [dcbe6f403d](https://linux-hardware.org/?probe=dcbe6f403d) | Jul 06, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [9ad51a3a2c](https://linux-hardware.org/?probe=9ad51a3a2c) | Jul 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [341858c479](https://linux-hardware.org/?probe=341858c479) | Jul 05, 2022 |
| MSI           | GP66 Leopard 11UG           | [bc37067029](https://linux-hardware.org/?probe=bc37067029) | Jul 05, 2022 |
| Acer          | Aspire E5-522               | [9693c1d4ff](https://linux-hardware.org/?probe=9693c1d4ff) | Jul 04, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [4829f98af6](https://linux-hardware.org/?probe=4829f98af6) | Jul 04, 2022 |
| HP            | 250 G6 Notebook PC          | [fed0993c92](https://linux-hardware.org/?probe=fed0993c92) | Jul 03, 2022 |
| Dell          | Vostro 2420                 | [ce9585eac5](https://linux-hardware.org/?probe=ce9585eac5) | Jul 03, 2022 |
| Intel         | HuronRiver Platform         | [c0d79569d8](https://linux-hardware.org/?probe=c0d79569d8) | Jul 03, 2022 |
| Acer          | Aspire VX5-591G             | [5393a13046](https://linux-hardware.org/?probe=5393a13046) | Jul 02, 2022 |
| Infinix       | INBOOK X2                   | [eedac976d8](https://linux-hardware.org/?probe=eedac976d8) | Jul 02, 2022 |
| Acer          | Swift SF314-42              | [bd4792ebd8](https://linux-hardware.org/?probe=bd4792ebd8) | Jul 02, 2022 |
| Apple         | MacBookPro14,1              | [aad648ac8d](https://linux-hardware.org/?probe=aad648ac8d) | Jul 02, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | [5950f35d56](https://linux-hardware.org/?probe=5950f35d56) | Jul 02, 2022 |
| ASUSTek       | ROG Strix G713RW_G713RW     | [6904140540](https://linux-hardware.org/?probe=6904140540) | Jul 02, 2022 |
| Razer         | Blade 14 (2022) - RZ09-0... | [927dbb8452](https://linux-hardware.org/?probe=927dbb8452) | Jul 01, 2022 |
| Razer         | Blade 15 Base Model (Ear... | [7e809da3ad](https://linux-hardware.org/?probe=7e809da3ad) | Jul 01, 2022 |
| Lenovo        | ThinkPad W510 4318CTO       | [27cd378ed6](https://linux-hardware.org/?probe=27cd378ed6) | Jul 01, 2022 |
| HP            | Pavilion g4                 | [3626d9afe4](https://linux-hardware.org/?probe=3626d9afe4) | Jul 01, 2022 |
| Dell          | XPS M1330                   | [b891e49fac](https://linux-hardware.org/?probe=b891e49fac) | Jun 30, 2022 |
| HP            | EliteBook 8470p             | [96b07cbbd5](https://linux-hardware.org/?probe=96b07cbbd5) | Jun 30, 2022 |
| ASUSTek       | ROG Strix G713RW_G713RW     | [abebd5c659](https://linux-hardware.org/?probe=abebd5c659) | Jun 30, 2022 |
| Dell          | Vostro 5625                 | [0a047126ba](https://linux-hardware.org/?probe=0a047126ba) | Jun 30, 2022 |
| HUAWEI        | HVY-WXX9                    | [e7f3ea5cf5](https://linux-hardware.org/?probe=e7f3ea5cf5) | Jun 30, 2022 |
| Infinix       | INBOOK X2                   | [1c87102f96](https://linux-hardware.org/?probe=1c87102f96) | Jun 29, 2022 |
| Lenovo        | ThinkPad P50 20EQS5M100     | [d0b6aa0a1a](https://linux-hardware.org/?probe=d0b6aa0a1a) | Jun 29, 2022 |
| Dell          | XPS 13 9310                 | [6a2b56796c](https://linux-hardware.org/?probe=6a2b56796c) | Jun 28, 2022 |
| Acer          | Aspire M5-582PT             | [e159de9f3e](https://linux-hardware.org/?probe=e159de9f3e) | Jun 28, 2022 |
| HP            | EliteBook 840 G2            | [79a978476b](https://linux-hardware.org/?probe=79a978476b) | Jun 28, 2022 |
| Dell          | Latitude 7350               | [427cc37d76](https://linux-hardware.org/?probe=427cc37d76) | Jun 28, 2022 |
| Dell          | Latitude 7350               | [65d1c5c6f5](https://linux-hardware.org/?probe=65d1c5c6f5) | Jun 28, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [20054c6da2](https://linux-hardware.org/?probe=20054c6da2) | Jun 27, 2022 |
| Lenovo        | ThinkPad T580 20LAS6XC00    | [a4b9098138](https://linux-hardware.org/?probe=a4b9098138) | Jun 26, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [0beecf61e4](https://linux-hardware.org/?probe=0beecf61e4) | Jun 26, 2022 |
| Dell          | Inspiron 3442               | [72286bac00](https://linux-hardware.org/?probe=72286bac00) | Jun 26, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [68e2e0bbdb](https://linux-hardware.org/?probe=68e2e0bbdb) | Jun 25, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [27343a622f](https://linux-hardware.org/?probe=27343a622f) | Jun 25, 2022 |
| Dell          | Latitude 5420               | [2149a24612](https://linux-hardware.org/?probe=2149a24612) | Jun 25, 2022 |
| Dell          | Latitude 5490               | [4c3d48724c](https://linux-hardware.org/?probe=4c3d48724c) | Jun 25, 2022 |
| Dell          | Latitude 5490               | [3bb8a81dbf](https://linux-hardware.org/?probe=3bb8a81dbf) | Jun 25, 2022 |
| ASUSTek       | G551JM                      | [2d8e7ffcb2](https://linux-hardware.org/?probe=2d8e7ffcb2) | Jun 24, 2022 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | [5bd3ad4d01](https://linux-hardware.org/?probe=5bd3ad4d01) | Jun 24, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [fac01563a9](https://linux-hardware.org/?probe=fac01563a9) | Jun 24, 2022 |
| Acer          | Nitro AN715-51              | [a8df58056b](https://linux-hardware.org/?probe=a8df58056b) | Jun 24, 2022 |
| Lenovo        | ThinkPad T580 20LAS6XC00    | [55e631d9b6](https://linux-hardware.org/?probe=55e631d9b6) | Jun 24, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [1780abcf08](https://linux-hardware.org/?probe=1780abcf08) | Jun 24, 2022 |
| Lenovo        | Legion Y740-15IRHg 81UH     | [e0da282c48](https://linux-hardware.org/?probe=e0da282c48) | Jun 23, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [a1a0b3b43b](https://linux-hardware.org/?probe=a1a0b3b43b) | Jun 23, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [cacc2464af](https://linux-hardware.org/?probe=cacc2464af) | Jun 23, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [7d5a943ab0](https://linux-hardware.org/?probe=7d5a943ab0) | Jun 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [f2b61e1e02](https://linux-hardware.org/?probe=f2b61e1e02) | Jun 23, 2022 |
| Acer          | Aspire E1-570               | [906b1f465e](https://linux-hardware.org/?probe=906b1f465e) | Jun 23, 2022 |
| Razer         | Blade                       | [6c8b201cd9](https://linux-hardware.org/?probe=6c8b201cd9) | Jun 23, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [51ec938467](https://linux-hardware.org/?probe=51ec938467) | Jun 22, 2022 |
| LG Electro... | 15Z95N-G.AAC6U1             | [c5b4596c19](https://linux-hardware.org/?probe=c5b4596c19) | Jun 22, 2022 |
| Acer          | Nitro AN515-55              | [bc159b637c](https://linux-hardware.org/?probe=bc159b637c) | Jun 22, 2022 |
| Dell          | Vostro 2420                 | [84a4eb23c6](https://linux-hardware.org/?probe=84a4eb23c6) | Jun 21, 2022 |
| Acer          | Ferrari One 200             | [52ba124048](https://linux-hardware.org/?probe=52ba124048) | Jun 21, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [a8d78740e8](https://linux-hardware.org/?probe=a8d78740e8) | Jun 21, 2022 |
| HUAWEI        | KLVL-WXXW                   | [4539c26ede](https://linux-hardware.org/?probe=4539c26ede) | Jun 21, 2022 |
| HUAWEI        | KLVL-WXXW                   | [cf80e45435](https://linux-hardware.org/?probe=cf80e45435) | Jun 21, 2022 |
| Apple         | MacBookPro16,1              | [35f551b127](https://linux-hardware.org/?probe=35f551b127) | Jun 21, 2022 |
| HP            | EliteBook 8570w             | [2530e2e400](https://linux-hardware.org/?probe=2530e2e400) | Jun 21, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [9a9dd8fa0c](https://linux-hardware.org/?probe=9a9dd8fa0c) | Jun 21, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | [ff5ed1835c](https://linux-hardware.org/?probe=ff5ed1835c) | Jun 20, 2022 |
| Philco        | OEM                         | [bee7961704](https://linux-hardware.org/?probe=bee7961704) | Jun 20, 2022 |
| HONOR         | HYM-WXX                     | [9eb7129a46](https://linux-hardware.org/?probe=9eb7129a46) | Jun 20, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [fc053b8a95](https://linux-hardware.org/?probe=fc053b8a95) | Jun 20, 2022 |
| HP            | ENVY dv7                    | [22dec86487](https://linux-hardware.org/?probe=22dec86487) | Jun 20, 2022 |
| ASUSTek       | GL502VMK                    | [d872e88532](https://linux-hardware.org/?probe=d872e88532) | Jun 20, 2022 |
| ASUSTek       | X550JX                      | [999d6e4735](https://linux-hardware.org/?probe=999d6e4735) | Jun 20, 2022 |
| Framework     | Laptop                      | [f5ece7ce85](https://linux-hardware.org/?probe=f5ece7ce85) | Jun 19, 2022 |
| Toshiba       | Satellite Click 10 LX5W-... | [b8f87c8ede](https://linux-hardware.org/?probe=b8f87c8ede) | Jun 19, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [fcbbdaf844](https://linux-hardware.org/?probe=fcbbdaf844) | Jun 18, 2022 |
| HUAWEI        | KPR-WX9                     | [4c08060155](https://linux-hardware.org/?probe=4c08060155) | Jun 18, 2022 |
| HP            | EliteBook 8460p             | [e19c095325](https://linux-hardware.org/?probe=e19c095325) | Jun 18, 2022 |
| Acer          | Nitro AN515-44              | [9ed8b5c759](https://linux-hardware.org/?probe=9ed8b5c759) | Jun 17, 2022 |
| Lenovo        | ThinkPad P50 20EQS31G00     | [2e98922741](https://linux-hardware.org/?probe=2e98922741) | Jun 17, 2022 |
| Dell          | Latitude E5450              | [42f5a53e24](https://linux-hardware.org/?probe=42f5a53e24) | Jun 16, 2022 |
| HP            | Laptop 15-dw2xxx            | [7eee6145a1](https://linux-hardware.org/?probe=7eee6145a1) | Jun 16, 2022 |
| ASUSTek       | X411UA                      | [da7deca26c](https://linux-hardware.org/?probe=da7deca26c) | Jun 16, 2022 |
| ASUSTek       | T100HAN                     | [20105d0e64](https://linux-hardware.org/?probe=20105d0e64) | Jun 16, 2022 |
| Acer          | Swift SF314-511             | [c414ab98c5](https://linux-hardware.org/?probe=c414ab98c5) | Jun 16, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Arch/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Arch          | 1744      | 56.42%  |
| Arch Rolling  | 1337      | 43.25%  |
| Arch V20.5.7  | 2         | 0.06%   |
| Arch V19.04.4 | 2         | 0.06%   |
| Arch V6.9.2   | 1         | 0.03%   |
| Arch V20.3.4  | 1         | 0.03%   |
| Arch V19.07.9 | 1         | 0.03%   |
| Arch V19.06.1 | 1         | 0.03%   |
| Arch V19.01.4 | 1         | 0.03%   |
| Arch 2.7      | 1         | 0.03%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| Arch | 2992      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version         | Notebooks | Percent |
|-----------------|-----------|---------|
| 5.17.1-arch1-1  | 52        | 1.47%   |
| 6.0.2-arch1-1   | 51        | 1.44%   |
| 5.9.14-arch1-1  | 31        | 0.87%   |
| 5.9.1-arch1-1   | 31        | 0.87%   |
| 6.0.9-arch1-1   | 28        | 0.79%   |
| 5.8.5-arch1-1   | 28        | 0.79%   |
| 5.17.5-arch1-1  | 28        | 0.79%   |
| 5.8.10-arch1-1  | 26        | 0.73%   |
| 5.17.9-arch1-1  | 25        | 0.71%   |
| 6.1.1-arch1-1   | 24        | 0.68%   |
| 5.11.16-arch1-1 | 24        | 0.68%   |
| 5.8.14-arch1-1  | 23        | 0.65%   |
| 5.8.1-arch1-1   | 23        | 0.65%   |
| 5.7.12-arch1-1  | 23        | 0.65%   |
| 6.0.12-arch1-1  | 22        | 0.62%   |
| 5.18.1-arch1-1  | 22        | 0.62%   |
| 5.13.13-arch1-1 | 22        | 0.62%   |
| 5.13.12-arch1-1 | 22        | 0.62%   |
| 5.18.16-arch1-1 | 21        | 0.59%   |
| 5.9.10-arch1-1  | 20        | 0.56%   |
| 5.8.12-arch1-1  | 20        | 0.56%   |
| 6.0.7-arch1-1   | 19        | 0.54%   |
| 5.8.3-arch1-1   | 19        | 0.54%   |
| 5.16.16-arch1-1 | 19        | 0.54%   |
| 5.11.11-arch1-1 | 19        | 0.54%   |
| 6.0.10-arch2-1  | 18        | 0.51%   |
| 5.9.11-arch2-1  | 18        | 0.51%   |
| 5.19.13-arch1-1 | 18        | 0.51%   |
| 5.16.2-arch1-1  | 18        | 0.51%   |
| 5.12.15-arch1-1 | 18        | 0.51%   |
| 5.11.2-arch1-1  | 18        | 0.51%   |
| 5.7.6-arch1-1   | 17        | 0.48%   |
| 5.6.13-arch1-1  | 17        | 0.48%   |
| 5.18.14-arch1-1 | 17        | 0.48%   |
| 5.15.2-arch1-1  | 17        | 0.48%   |
| 5.14.14-arch1-1 | 17        | 0.48%   |
| 5.10.16-arch1-1 | 17        | 0.48%   |
| 5.6.15-arch1-1  | 16        | 0.45%   |
| 5.18.12-arch1-1 | 16        | 0.45%   |
| 5.15.7-arch1-1  | 16        | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.17.1  | 65        | 1.84%   |
| 6.0.2   | 60        | 1.69%   |
| 5.9.1   | 40        | 1.13%   |
| 5.9.14  | 38        | 1.07%   |
| 5.8.5   | 38        | 1.07%   |
| 5.17.5  | 38        | 1.07%   |
| 6.0.9   | 34        | 0.96%   |
| 5.13.13 | 31        | 0.88%   |
| 5.8.14  | 30        | 0.85%   |
| 5.17.9  | 30        | 0.85%   |
| 6.1.1   | 29        | 0.82%   |
| 5.8.10  | 29        | 0.82%   |
| 6.0.12  | 27        | 0.76%   |
| 5.18.16 | 27        | 0.76%   |
| 5.8.12  | 26        | 0.73%   |
| 5.8.1   | 26        | 0.73%   |
| 5.18.1  | 26        | 0.73%   |
| 5.16.2  | 26        | 0.73%   |
| 5.13.12 | 26        | 0.73%   |
| 5.11.16 | 26        | 0.73%   |
| 6.0.11  | 25        | 0.71%   |
| 5.7.12  | 25        | 0.71%   |
| 5.19.13 | 24        | 0.68%   |
| 5.16.16 | 24        | 0.68%   |
| 5.14.8  | 24        | 0.68%   |
| 5.11.2  | 24        | 0.68%   |
| 5.10.16 | 24        | 0.68%   |
| 6.0.8   | 23        | 0.65%   |
| 6.0.10  | 23        | 0.65%   |
| 5.18.3  | 23        | 0.65%   |
| 5.12.15 | 23        | 0.65%   |
| 5.14.14 | 22        | 0.62%   |
| 6.0.7   | 21        | 0.59%   |
| 5.9.11  | 21        | 0.59%   |
| 5.9.10  | 21        | 0.59%   |
| 5.8.3   | 21        | 0.59%   |
| 5.19.2  | 21        | 0.59%   |
| 5.15.10 | 21        | 0.59%   |
| 5.11.11 | 21        | 0.59%   |
| 5.7.6   | 20        | 0.56%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 256       | 7.52%   |
| 6.0     | 243       | 7.14%   |
| 5.8     | 232       | 6.82%   |
| 5.18    | 219       | 6.44%   |
| 5.9     | 208       | 6.11%   |
| 5.17    | 198       | 5.82%   |
| 5.4     | 193       | 5.67%   |
| 5.16    | 188       | 5.53%   |
| 5.10    | 182       | 5.35%   |
| 5.19    | 176       | 5.17%   |
| 5.11    | 168       | 4.94%   |
| 5.12    | 153       | 4.5%    |
| 5.13    | 143       | 4.2%    |
| 5.7     | 138       | 4.06%   |
| 5.6     | 135       | 3.97%   |
| 5.14    | 128       | 3.76%   |
| 6.1     | 115       | 3.38%   |
| 5.5     | 93        | 2.73%   |
| 5.3     | 64        | 1.88%   |
| 5.2     | 33        | 0.97%   |
| 4.19    | 26        | 0.76%   |
| 5.0     | 19        | 0.56%   |
| 5.1     | 16        | 0.47%   |
| 4.18    | 16        | 0.47%   |
| 4.17    | 12        | 0.35%   |
| 4.20    | 9         | 0.26%   |
| 4.14    | 9         | 0.26%   |
| 4.15    | 5         | 0.15%   |
| 4.9     | 4         | 0.12%   |
| 4.7     | 4         | 0.12%   |
| 4.16    | 4         | 0.12%   |
| 4.6     | 3         | 0.09%   |
| 4.4     | 3         | 0.09%   |
| 4.8     | 2         | 0.06%   |
| 4.13    | 2         | 0.06%   |
| 4.11    | 2         | 0.06%   |
| Unknown | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 2988      | 99.87%  |
| i686   | 4         | 0.13%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| GNOME                    | 1055      | 33.79%  |
| KDE5                     | 720       | 23.06%  |
| Unknown                  | 414       | 13.26%  |
| XFCE                     | 241       | 7.72%   |
| i3                       | 178       | 5.7%    |
| KDE                      | 139       | 4.45%   |
| sway                     | 44        | 1.41%   |
| MATE                     | 41        | 1.31%   |
| Cinnamon                 | 39        | 1.25%   |
| Budgie                   | 39        | 1.25%   |
| X-Cinnamon               | 36        | 1.15%   |
| LXQt                     | 30        | 0.96%   |
| awesome                  | 22        | 0.7%    |
| Deepin                   | 21        | 0.67%   |
| LXDE                     | 16        | 0.51%   |
| bspwm                    | 16        | 0.51%   |
| GNOME Flashback          | 9         | 0.29%   |
| Unity                    | 8         | 0.26%   |
| qtile                    | 8         | 0.26%   |
| xmonad                   | 7         | 0.22%   |
| Hyprland                 | 6         | 0.19%   |
| DWM                      | 6         | 0.19%   |
| openbox                  | 5         | 0.16%   |
| GNOME Classic            | 5         | 0.16%   |
| Enlightenment            | 4         | 0.13%   |
| i3-with-shmlog           | 3         | 0.1%    |
| X-Generic                | 1         | 0.03%   |
| river                    | 1         | 0.03%   |
| Pantheon                 | 1         | 0.03%   |
| jwm                      | 1         | 0.03%   |
| instantwm                | 1         | 0.03%   |
| ICEWM                    | 1         | 0.03%   |
| herbstluftwm             | 1         | 0.03%   |
| dusk                     | 1         | 0.03%   |
| default                  | 1         | 0.03%   |
| /usr/bin/openbox-session | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 1825      | 58.93%  |
| Wayland | 786       | 25.38%  |
| Tty     | 269       | 8.69%   |
| Unknown | 217       | 7.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1288      | 41.56%  |
| SDDM    | 696       | 22.46%  |
| GDM     | 468       | 15.1%   |
| LightDM | 347       | 11.2%   |
| TDM     | 188       | 6.07%   |
| Ly      | 33        | 1.06%   |
| XDM     | 29        | 0.94%   |
| LXDM    | 24        | 0.77%   |
| SLiM    | 11        | 0.35%   |
| GREETD  | 8         | 0.26%   |
| NODM    | 3         | 0.1%    |
| EMPTTY  | 3         | 0.1%    |
| MDM     | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 1477      | 48.3%   |
| Unknown | 346       | 11.31%  |
| en_GB   | 170       | 5.56%   |
| C       | 149       | 4.87%   |
| it_IT   | 103       | 3.37%   |
| de_DE   | 98        | 3.2%    |
| pt_BR   | 87        | 2.84%   |
| ru_RU   | 78        | 2.55%   |
| fr_FR   | 69        | 2.26%   |
| en_IN   | 42        | 1.37%   |
| pl_PL   | 38        | 1.24%   |
| zh_CN   | 34        | 1.11%   |
| es_ES   | 34        | 1.11%   |
| en_CA   | 30        | 0.98%   |
| en_AU   | 25        | 0.82%   |
| es_MX   | 15        | 0.49%   |
| es_AR   | 13        | 0.43%   |
| en_IE   | 11        | 0.36%   |
| de_AT   | 11        | 0.36%   |
| tr_TR   | 10        | 0.33%   |
| en_DK   | 10        | 0.33%   |
| ja_JP   | 9         | 0.29%   |
| es_CO   | 9         | 0.29%   |
| hu_HU   | 8         | 0.26%   |
| es_CL   | 8         | 0.26%   |
| en_NZ   | 8         | 0.26%   |
| ru_UA   | 7         | 0.23%   |
| en_SG   | 7         | 0.23%   |
| pt_PT   | 6         | 0.2%    |
| nl_NL   | 6         | 0.2%    |
| en_ZA   | 6         | 0.2%    |
| cs_CZ   | 6         | 0.2%    |
| zh_TW   | 5         | 0.16%   |
| fr_CA   | 5         | 0.16%   |
| es_PE   | 5         | 0.16%   |
| ca_ES   | 5         | 0.16%   |
| lv_LV   | 4         | 0.13%   |
| ko_KR   | 4         | 0.13%   |
| fr_CH   | 4         | 0.13%   |
| fr_BE   | 4         | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 1907      | 62.28%  |
| BIOS | 1155      | 37.72%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 2218      | 73.3%   |
| Btrfs   | 551       | 18.21%  |
| Unknown | 109       | 3.6%    |
| Xfs     | 69        | 2.28%   |
| F2fs    | 39        | 1.29%   |
| Zfs     | 16        | 0.53%   |
| Overlay | 16        | 0.53%   |
| Ext2    | 3         | 0.1%    |
| XXXXX   | 2         | 0.07%   |
| XXX4    | 1         | 0.03%   |
| Jfs     | 1         | 0.03%   |
| Aufs    | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 1881      | 61.98%  |
| Unknown | 882       | 29.06%  |
| MBR     | 272       | 8.96%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2719      | 89.97%  |
| Yes       | 303       | 10.03%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2227      | 73.35%  |
| Yes       | 809       | 26.65%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 873       | 29.18%  |
| Dell                   | 490       | 16.38%  |
| Hewlett-Packard        | 412       | 13.77%  |
| ASUSTek Computer       | 350       | 11.7%   |
| Acer                   | 239       | 7.99%   |
| MSI                    | 88        | 2.94%   |
| Apple                  | 57        | 1.91%   |
| HUAWEI                 | 53        | 1.77%   |
| Samsung Electronics    | 47        | 1.57%   |
| Toshiba                | 39        | 1.3%    |
| Notebook               | 29        | 0.97%   |
| Google                 | 21        | 0.7%    |
| Timi                   | 20        | 0.67%   |
| Sony                   | 20        | 0.67%   |
| Framework              | 17        | 0.57%   |
| Alienware              | 16        | 0.53%   |
| TUXEDO                 | 15        | 0.5%    |
| Razer                  | 13        | 0.43%   |
| Unknown                | 13        | 0.43%   |
| Fujitsu                | 12        | 0.4%    |
| LG Electronics         | 10        | 0.33%   |
| System76               | 9         | 0.3%    |
| Avell High Performance | 9         | 0.3%    |
| Gigabyte Technology    | 8         | 0.27%   |
| Schenker               | 7         | 0.23%   |
| Packard Bell           | 7         | 0.23%   |
| Intel                  | 7         | 0.23%   |
| MECHREVO               | 6         | 0.2%    |
| Positivo               | 5         | 0.17%   |
| Chuwi                  | 5         | 0.17%   |
| Teclast                | 4         | 0.13%   |
| SLIMBOOK               | 4         | 0.13%   |
| Medion                 | 4         | 0.13%   |
| Koompi                 | 4         | 0.13%   |
| GPD                    | 4         | 0.13%   |
| PC Specialist          | 3         | 0.1%    |
| Intel Client Systems   | 3         | 0.1%    |
| HONOR                  | 3         | 0.1%    |
| Fujitsu Siemens        | 3         | 0.1%    |
| Eluktronics            | 3         | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 31        | 1.04%   |
| Dell XPS 15 9570                    | 17        | 0.57%   |
| Framework Laptop                    | 16        | 0.53%   |
| HP Notebook                         | 14        | 0.47%   |
| Dell XPS 15 9500                    | 13        | 0.43%   |
| Dell XPS 13 9360                    | 12        | 0.4%    |
| Dell XPS 13 9380                    | 11        | 0.37%   |
| Dell Latitude E6430                 | 10        | 0.33%   |
| Dell Inspiron 15 7000 Gaming        | 10        | 0.33%   |
| HUAWEI NBLK-WAX9X                   | 9         | 0.3%    |
| HP EliteBook 840 G6                 | 9         | 0.3%    |
| Dell XPS 15 7590                    | 9         | 0.3%    |
| Dell XPS 13 9370                    | 9         | 0.3%    |
| Lenovo ThinkBook 15 G2 ITL 20VE     | 8         | 0.27%   |
| Lenovo IdeaPad 5 14ARE05 81YM       | 8         | 0.27%   |
| HUAWEI BOHK-WAX9X                   | 8         | 0.27%   |
| Dell XPS 13 9350                    | 8         | 0.27%   |
| Dell Latitude E7450                 | 8         | 0.27%   |
| ASUS ROG Strix G513QY_G513QY        | 8         | 0.27%   |
| HP EliteBook 840 G5                 | 7         | 0.23%   |
| HP 250 G6 Notebook PC               | 7         | 0.23%   |
| Dell XPS 13 9310                    | 7         | 0.23%   |
| Dell XPS 13 7390                    | 7         | 0.23%   |
| Dell Precision 7540                 | 7         | 0.23%   |
| Dell Inspiron 5570                  | 7         | 0.23%   |
| ASUS TUF Gaming FX505DT_FX505DT     | 7         | 0.23%   |
| Acer Nitro AN515-52                 | 7         | 0.23%   |
| Lenovo Y520-15IKBN 80WK             | 6         | 0.2%    |
| Lenovo Legion 5 15ARH05 82B5        | 6         | 0.2%    |
| HUAWEI MACH-WX9                     | 6         | 0.2%    |
| HP Pavilion Notebook                | 6         | 0.2%    |
| HP Pavilion Gaming Laptop 15-cx0xxx | 6         | 0.2%    |
| HP Pavilion g6                      | 6         | 0.2%    |
| HP Pavilion dv6                     | 6         | 0.2%    |
| HP Laptop 15-da0xxx                 | 6         | 0.2%    |
| Dell XPS 15 9560                    | 6         | 0.2%    |
| Dell Latitude 5480                  | 6         | 0.2%    |
| Dell G3 3579                        | 6         | 0.2%    |
| Dell G3 3500                        | 6         | 0.2%    |
| ASUS X580VD                         | 6         | 0.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 522       | 17.45%  |
| Lenovo IdeaPad    | 168       | 5.61%   |
| Acer Aspire       | 141       | 4.71%   |
| Dell Inspiron     | 132       | 4.41%   |
| Dell Latitude     | 127       | 4.24%   |
| Dell XPS          | 126       | 4.21%   |
| HP Pavilion       | 90        | 3.01%   |
| HP EliteBook      | 84        | 2.81%   |
| HP Laptop         | 57        | 1.91%   |
| Lenovo Legion     | 55        | 1.84%   |
| HP ProBook        | 52        | 1.74%   |
| ASUS VivoBook     | 52        | 1.74%   |
| ASUS ROG          | 48        | 1.6%    |
| Dell Precision    | 42        | 1.4%    |
| Acer Nitro        | 36        | 1.2%    |
| Toshiba Satellite | 31        | 1.04%   |
| Unknown           | 31        | 1.04%   |
| Dell Vostro       | 28        | 0.94%   |
| Acer Swift        | 28        | 0.94%   |
| Lenovo ThinkBook  | 26        | 0.87%   |
| ASUS TUF          | 26        | 0.87%   |
| ASUS ZenBook      | 25        | 0.84%   |
| ASUS ASUS         | 25        | 0.84%   |
| HP ENVY           | 21        | 0.7%    |
| HP OMEN           | 17        | 0.57%   |
| Framework Laptop  | 17        | 0.57%   |
| Lenovo Yoga       | 16        | 0.53%   |
| HP 250            | 15        | 0.5%    |
| HP Notebook       | 14        | 0.47%   |
| Razer Blade       | 13        | 0.43%   |
| Dell G3           | 13        | 0.43%   |
| MSI Modern        | 12        | 0.4%    |
| Fujitsu LIFEBOOK  | 12        | 0.4%    |
| HP ZBook          | 11        | 0.37%   |
| Acer Predator     | 10        | 0.33%   |
| HUAWEI NBLK-WAX9X | 9         | 0.3%    |
| HP 255            | 9         | 0.3%    |
| HUAWEI BOHK-WAX9X | 8         | 0.27%   |
| ASUS Strix        | 8         | 0.27%   |
| HP Compaq         | 7         | 0.23%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 415       | 13.87%  |
| 2020    | 404       | 13.5%   |
| 2018    | 362       | 12.1%   |
| 2021    | 327       | 10.93%  |
| 2017    | 232       | 7.75%   |
| 2015    | 182       | 6.08%   |
| 2016    | 181       | 6.05%   |
| 2012    | 169       | 5.65%   |
| 2013    | 155       | 5.18%   |
| 2011    | 141       | 4.71%   |
| 2014    | 134       | 4.48%   |
| 2010    | 93        | 3.11%   |
| 2022    | 88        | 2.94%   |
| 2008    | 55        | 1.84%   |
| 2009    | 40        | 1.34%   |
| 2007    | 9         | 0.3%    |
| 2006    | 4         | 0.13%   |
| Unknown | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 2992      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 2963      | 98.8%   |
| Enabled  | 36        | 1.2%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2956      | 98.8%   |
| Yes  | 36        | 1.2%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 793       | 26.19%  |
| 16.01-24.0  | 722       | 23.84%  |
| 8.01-16.0   | 687       | 22.69%  |
| 3.01-4.0    | 347       | 11.46%  |
| 32.01-64.0  | 299       | 9.87%   |
| 24.01-32.0  | 52        | 1.72%   |
| 64.01-256.0 | 50        | 1.65%   |
| 1.01-2.0    | 50        | 1.65%   |
| 2.01-3.0    | 23        | 0.76%   |
| 0.51-1.0    | 5         | 0.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 845       | 25.57%  |
| 1.01-2.0   | 833       | 25.2%   |
| 4.01-8.0   | 661       | 20%     |
| 3.01-4.0   | 566       | 17.13%  |
| 8.01-16.0  | 203       | 6.14%   |
| 0.51-1.0   | 138       | 4.18%   |
| 0.01-0.5   | 27        | 0.82%   |
| 16.01-24.0 | 21        | 0.64%   |
| 24.01-32.0 | 10        | 0.3%    |
| 32.01-64.0 | 1         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2076      | 68.24%  |
| 2      | 828       | 27.22%  |
| 3      | 108       | 3.55%   |
| 0      | 14        | 0.46%   |
| 4      | 12        | 0.39%   |
| 5      | 3         | 0.1%    |
| 6      | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2379      | 79.12%  |
| Yes       | 628       | 20.88%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2327      | 77.41%  |
| No        | 679       | 22.59%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2969      | 99.16%  |
| No        | 25        | 0.84%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2567      | 84.97%  |
| No        | 454       | 15.03%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 520       | 17.26%  |
| Germany      | 253       | 8.4%    |
| Russia       | 180       | 5.97%   |
| Italy        | 177       | 5.87%   |
| Brazil       | 164       | 5.44%   |
| France       | 139       | 4.61%   |
| India        | 129       | 4.28%   |
| UK           | 101       | 3.35%   |
| Poland       | 85        | 2.82%   |
| Canada       | 76        | 2.52%   |
| Spain        | 67        | 2.22%   |
| Netherlands  | 60        | 1.99%   |
| China        | 56        | 1.86%   |
| Turkey       | 44        | 1.46%   |
| Australia    | 42        | 1.39%   |
| Ukraine      | 40        | 1.33%   |
| Austria      | 39        | 1.29%   |
| Sweden       | 35        | 1.16%   |
| Indonesia    | 35        | 1.16%   |
| Czechia      | 32        | 1.06%   |
| Belgium      | 31        | 1.03%   |
| Mexico       | 30        | 1%      |
| Romania      | 26        | 0.86%   |
| Argentina    | 26        | 0.86%   |
| Portugal     | 25        | 0.83%   |
| Switzerland  | 23        | 0.76%   |
| Vietnam      | 22        | 0.73%   |
| Iran         | 22        | 0.73%   |
| Japan        | 21        | 0.7%    |
| Finland      | 20        | 0.66%   |
| Colombia     | 20        | 0.66%   |
| New Zealand  | 19        | 0.63%   |
| Hungary      | 19        | 0.63%   |
| Greece       | 19        | 0.63%   |
| Denmark      | 18        | 0.6%    |
| Chile        | 17        | 0.56%   |
| Belarus      | 16        | 0.53%   |
| South Africa | 15        | 0.5%    |
| Norway       | 15        | 0.5%    |
| Bulgaria     | 14        | 0.46%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 53        | 1.66%   |
| Paris             | 32        | 1%      |
| Milan             | 31        | 0.97%   |
| Sao Paulo         | 29        | 0.91%   |
| St Petersburg     | 27        | 0.84%   |
| Berlin            | 26        | 0.81%   |
| Warsaw            | 24        | 0.75%   |
| Munich            | 21        | 0.66%   |
| Vienna            | 20        | 0.63%   |
| Los Angeles       | 20        | 0.63%   |
| Valencia          | 19        | 0.59%   |
| Amsterdam         | 17        | 0.53%   |
| Prague            | 16        | 0.5%    |
| Kyiv              | 16        | 0.5%    |
| Istanbul          | 16        | 0.5%    |
| Bengaluru         | 16        | 0.5%    |
| Sydney            | 15        | 0.47%   |
| Tehran            | 13        | 0.41%   |
| Phoenix           | 13        | 0.41%   |
| Frankfurt am Main | 13        | 0.41%   |
| Rome              | 12        | 0.38%   |
| Montreal          | 12        | 0.38%   |
| Mexico City       | 12        | 0.38%   |
| Melbourne         | 12        | 0.38%   |
| Jakarta           | 12        | 0.38%   |
| Helsinki          | 12        | 0.38%   |
| Hamburg           | 11        | 0.34%   |
| Buenos Aires      | 11        | 0.34%   |
| Athens            | 11        | 0.34%   |
| Turin             | 10        | 0.31%   |
| New York          | 10        | 0.31%   |
| Madrid            | 10        | 0.31%   |
| London            | 10        | 0.31%   |
| Curitiba          | 10        | 0.31%   |
| Cologne           | 10        | 0.31%   |
| Budapest          | 10        | 0.31%   |
| Bogotá           | 10        | 0.31%   |
| Singapore         | 9         | 0.28%   |
| Seattle           | 9         | 0.28%   |
| Ottawa            | 9         | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 847       | 1125   | 21.46%  |
| WDC                         | 422       | 521    | 10.69%  |
| Seagate                     | 351       | 429    | 8.9%    |
| SanDisk                     | 325       | 382    | 8.24%   |
| Toshiba                     | 276       | 321    | 6.99%   |
| SK hynix                    | 221       | 265    | 5.6%    |
| Kingston                    | 193       | 239    | 4.89%   |
| Unknown                     | 161       | 192    | 4.08%   |
| Intel                       | 143       | 185    | 3.62%   |
| Micron Technology           | 118       | 143    | 2.99%   |
| Crucial                     | 116       | 160    | 2.94%   |
| HGST                        | 112       | 120    | 2.84%   |
| Hitachi                     | 60        | 61     | 1.52%   |
| A-DATA Technology           | 50        | 71     | 1.27%   |
| Apple                       | 35        | 42     | 0.89%   |
| Phison                      | 27        | 32     | 0.68%   |
| LITEON                      | 27        | 28     | 0.68%   |
| KIOXIA                      | 27        | 30     | 0.68%   |
| Transcend                   | 21        | 22     | 0.53%   |
| Phison Electronics          | 18        | 20     | 0.46%   |
| SPCC                        | 17        | 18     | 0.43%   |
| Lenovo                      | 17        | 21     | 0.43%   |
| China                       | 17        | 22     | 0.43%   |
| Silicon Motion              | 16        | 16     | 0.41%   |
| JMicron Technology          | 14        | 13     | 0.35%   |
| Micron/Crucial Technology   | 13        | 15     | 0.33%   |
| PNY                         | 12        | 15     | 0.3%    |
| LITEONIT                    | 12        | 12     | 0.3%    |
| Kingston Technology Company | 12        | 12     | 0.3%    |
| ADATA Technology            | 11        | 13     | 0.28%   |
| KingSpec                    | 10        | 11     | 0.25%   |
| GOODRAM                     | 10        | 10     | 0.25%   |
| Patriot                     | 9         | 10     | 0.23%   |
| OCZ                         | 9         | 9      | 0.23%   |
| Lite-On                     | 8         | 10     | 0.2%    |
| Plextor                     | 7         | 7      | 0.18%   |
| FORESEE                     | 7         | 9      | 0.18%   |
| Corsair                     | 7         | 8      | 0.18%   |
| XPG                         | 6         | 10     | 0.15%   |
| Union Memory (Shenzhen)     | 6         | 6      | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                       | 80        | 1.93%   |
| Samsung NVMe SSD Drive 512GB                         | 63        | 1.52%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB  | 60        | 1.45%   |
| SanDisk NVMe SSD Drive 512GB                         | 45        | 1.09%   |
| HGST HTS721010A9E630 1TB                             | 44        | 1.06%   |
| SK hynix NVMe SSD Drive 512GB                        | 39        | 0.94%   |
| Toshiba MQ01ABD100 1TB                               | 36        | 0.87%   |
| Samsung SSD 860 EVO 500GB                            | 36        | 0.87%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB               | 35        | 0.84%   |
| Toshiba MQ04ABF100 1TB                               | 34        | 0.82%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 33        | 0.8%    |
| Kingston SA400S37240G 240GB SSD                      | 31        | 0.75%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1TB       | 28        | 0.68%   |
| Samsung SSD 850 EVO 500GB                            | 27        | 0.65%   |
| SanDisk NVMe SSD Drive 256GB                         | 24        | 0.58%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 24        | 0.58%   |
| Seagate ST1000LM048-2E7172 1TB                       | 23        | 0.56%   |
| Crucial CT500MX500SSD1 500GB                         | 23        | 0.56%   |
| Seagate ST2000LM007-1R8174 2TB                       | 22        | 0.53%   |
| WDC WD10SPZX-21Z10T0 1TB                             | 21        | 0.51%   |
| Unknown MMC Card  64GB                               | 21        | 0.51%   |
| Unknown MMC Card  32GB                               | 21        | 0.51%   |
| SanDisk NVMe SSD Drive 1TB                           | 21        | 0.51%   |
| Samsung SSD 970 EVO Plus 1TB                         | 21        | 0.51%   |
| Toshiba NVMe SSD Drive 512GB                         | 20        | 0.48%   |
| Samsung SSD 970 EVO Plus 500GB                       | 20        | 0.48%   |
| Samsung NVMe SSD Drive 1TB                           | 20        | 0.48%   |
| HGST HTS541010A9E680 1TB                             | 20        | 0.48%   |
| Kingston SA400S37120G 120GB SSD                      | 19        | 0.46%   |
| Seagate ST500LT012-1DG142 500GB                      | 18        | 0.43%   |
| Seagate ST1000LX015-1U7172 1TB                       | 18        | 0.43%   |
| Kingston SA400S37480G 480GB SSD                      | 18        | 0.43%   |
| WDC WD10JPVX-22JC3T0 1TB                             | 17        | 0.41%   |
| Samsung SSD 860 EVO 1TB                              | 17        | 0.41%   |
| Samsung NVMe SSD Drive 500GB                         | 17        | 0.41%   |
| Crucial CT1000MX500SSD1 1TB                          | 17        | 0.41%   |
| Toshiba MQ01ABF050 500GB                             | 16        | 0.39%   |
| Samsung SSD 850 EVO 250GB                            | 16        | 0.39%   |
| SK hynix NVMe SSD Drive 256GB                        | 15        | 0.36%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                   | 15        | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 343       | 419    | 36.68%  |
| WDC                 | 230       | 266    | 24.6%   |
| Toshiba             | 149       | 168    | 15.94%  |
| HGST                | 112       | 120    | 11.98%  |
| Hitachi             | 60        | 61     | 6.42%   |
| Unknown             | 10        | 12     | 1.07%   |
| Samsung Electronics | 9         | 9      | 0.96%   |
| Fujitsu             | 4         | 4      | 0.43%   |
| ASMT                | 4         | 5      | 0.43%   |
| HGST HTS            | 3         | 3      | 0.32%   |
| Apple               | 3         | 3      | 0.32%   |
| SABRENT             | 2         | 2      | 0.21%   |
| SAGE                | 1         | 1      | 0.11%   |
| Pioneer             | 1         | 1      | 0.11%   |
| PHD 3.0             | 1         | 1      | 0.11%   |
| NeoTech             | 1         | 1      | 0.11%   |
| Maxone              | 1         | 1      | 0.11%   |
| ACASIS              | 1         | 1      | 0.11%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 314       | 389    | 26.21%  |
| SanDisk             | 139       | 157    | 11.6%   |
| Kingston            | 133       | 162    | 11.1%   |
| Crucial             | 102       | 136    | 8.51%   |
| WDC                 | 78        | 101    | 6.51%   |
| Toshiba             | 34        | 42     | 2.84%   |
| SK hynix            | 32        | 38     | 2.67%   |
| A-DATA Technology   | 32        | 49     | 2.67%   |
| Micron Technology   | 31        | 38     | 2.59%   |
| Intel               | 29        | 33     | 2.42%   |
| LITEON              | 24        | 25     | 2%      |
| Apple               | 22        | 23     | 1.84%   |
| Transcend           | 21        | 22     | 1.75%   |
| China               | 17        | 22     | 1.42%   |
| SPCC                | 13        | 13     | 1.09%   |
| LITEONIT            | 12        | 12     | 1%      |
| PNY                 | 11        | 14     | 0.92%   |
| KingSpec            | 10        | 11     | 0.83%   |
| Patriot             | 9         | 10     | 0.75%   |
| OCZ                 | 9         | 9      | 0.75%   |
| JMicron Technology  | 9         | 9      | 0.75%   |
| GOODRAM             | 9         | 9      | 0.75%   |
| Plextor             | 7         | 7      | 0.58%   |
| Intenso             | 6         | 7      | 0.5%    |
| FORESEE             | 6         | 8      | 0.5%    |
| Lexar               | 5         | 9      | 0.42%   |
| Gigabyte Technology | 4         | 4      | 0.33%   |
| Unknown             | 3         | 3      | 0.25%   |
| TO Exter            | 3         | 5      | 0.25%   |
| Mushkin             | 3         | 3      | 0.25%   |
| BHT                 | 3         | 5      | 0.25%   |
| ZHITAI              | 2         | 3      | 0.17%   |
| Verbatim            | 2         | 2      | 0.17%   |
| Teclast             | 2         | 2      | 0.17%   |
| Seagate             | 2         | 2      | 0.17%   |
| Netac               | 2         | 2      | 0.17%   |
| Lenovo              | 2         | 2      | 0.17%   |
| HS-SSD-E100         | 2         | 2      | 0.17%   |
| HS-SSD-C100         | 2         | 2      | 0.17%   |
| Hewlett-Packard     | 2         | 2      | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 1510      | 2093   | 40.77%  |
| SSD     | 1101      | 1450   | 29.72%  |
| HDD     | 907       | 1078   | 24.49%  |
| MMC     | 151       | 179    | 4.08%   |
| Unknown | 35        | 37     | 0.94%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1700      | 2422   | 48.81%  |
| NVMe | 1508      | 2083   | 43.3%   |
| MMC  | 151       | 179    | 4.34%   |
| SAS  | 124       | 153    | 3.56%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1204      | 1590   | 60.72%  |
| 0.51-1.0   | 697       | 836    | 35.15%  |
| 1.01-2.0   | 71        | 90     | 3.58%   |
| 3.01-4.0   | 6         | 7      | 0.3%    |
| 4.01-10.0  | 3         | 3      | 0.15%   |
| 2.01-3.0   | 2         | 2      | 0.1%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 843       | 27.05%  |
| 101-250        | 842       | 27.01%  |
| 501-1000       | 588       | 18.86%  |
| 1001-2000      | 344       | 11.04%  |
| 51-100         | 141       | 4.52%   |
| More than 3000 | 98        | 3.14%   |
| 2001-3000      | 83        | 2.66%   |
| Unknown        | 76        | 2.44%   |
| 21-50          | 54        | 1.73%   |
| 1-20           | 48        | 1.54%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 714       | 21.94%  |
| 101-250        | 628       | 19.3%   |
| 21-50          | 549       | 16.87%  |
| 51-100         | 466       | 14.32%  |
| 251-500        | 428       | 13.15%  |
| 501-1000       | 258       | 7.93%   |
| 1001-2000      | 82        | 2.52%   |
| Unknown        | 76        | 2.34%   |
| More than 3000 | 26        | 0.8%    |
| 2001-3000      | 26        | 0.8%    |
| 0              | 1         | 0.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Notebooks | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| HGST HTS721010A9E630 1TB                | 9         | 9      | 4.48%   |
| Seagate ST1000LM035-1RK172 1TB          | 8         | 8      | 3.98%   |
| HGST HTS541010A9E680 1TB                | 6         | 6      | 2.99%   |
| HGST HTS545050A7E680 500GB              | 5         | 6      | 2.49%   |
| SK hynix HFS128G39TND-N210A 128GB SSD   | 4         | 4      | 1.99%   |
| Seagate ST9500325AS 500GB               | 4         | 4      | 1.99%   |
| HGST HTS725050A7E630 500GB              | 4         | 4      | 1.99%   |
| WDC WD10JPVX-22JC3T0 1TB                | 3         | 3      | 1.49%   |
| Seagate ST500LT012-1DG142 500GB         | 3         | 3      | 1.49%   |
| Seagate ST2000LM007-1R8174 2TB          | 3         | 3      | 1.49%   |
| Seagate ST1000LX015-1U7172 1TB          | 3         | 4      | 1.49%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 3         | 3      | 1.49%   |
| Seagate ST1000LM014-SSHD-8GB            | 3         | 3      | 1.49%   |
| Toshiba MQ01ABD100 1TB                  | 2         | 2      | 1%      |
| Toshiba MK3276GSX 320GB                 | 2         | 2      | 1%      |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD | 2         | 2      | 1%      |
| Seagate ST9250315AS 250GB               | 2         | 2      | 1%      |
| Seagate ST500LT012-9WS142 500GB         | 2         | 2      | 1%      |
| Seagate ST500LM021-1KJ152 500GB         | 2         | 2      | 1%      |
| Seagate ST500LM012 HN-M500MBB 500GB     | 2         | 2      | 1%      |
| Seagate ST500LM000-SSHD-8GB             | 2         | 2      | 1%      |
| Seagate ST2000LX001-1RG174 2TB          | 2         | 2      | 1%      |
| Seagate ST1000LM048-2E7172 1TB          | 2         | 2      | 1%      |
| SanDisk SD7SB3Q256G1002 256GB SSD       | 2         | 2      | 1%      |
| Samsung Electronics SSD 970 EVO 2TB     | 2         | 2      | 1%      |
| LITEON CV8-8E128-HP 128GB SSD           | 2         | 2      | 1%      |
| Intel SSDSC2BF240A4L 240GB              | 2         | 2      | 1%      |
| Hitachi HTS723232A7A364 320GB           | 2         | 2      | 1%      |
| Hitachi HTS545050A7E380 500GB           | 2         | 3      | 1%      |
| Hitachi HTS545025B9A300 250GB           | 2         | 2      | 1%      |
| Hitachi HTS541680J9SA00 80GB            | 2         | 2      | 1%      |
| Hitachi HTS541616J9SA00 160GB           | 2         | 2      | 1%      |
| HGST HTS545050A7E380 500GB              | 2         | 2      | 1%      |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 1         | 1      | 0.5%    |
| WDC WDS100T2B0B-00YS70 1TB SSD          | 1         | 1      | 0.5%    |
| WDC WD7500BPKT-00PK4T0 752GB            | 1         | 1      | 0.5%    |
| WDC WD5000LPVX-80V0TT0 500GB            | 1         | 1      | 0.5%    |
| WDC WD5000LPCX-24VHAT0 500GB            | 1         | 1      | 0.5%    |
| WDC WD5000LPCX-00VHAT0 500GB            | 1         | 1      | 0.5%    |
| WDC WD5000BPVT-16HXZT1 500GB            | 1         | 1      | 0.5%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 55        | 58     | 27.36%  |
| HGST                | 28        | 29     | 13.93%  |
| WDC                 | 22        | 24     | 10.95%  |
| Toshiba             | 20        | 22     | 9.95%   |
| Hitachi             | 17        | 18     | 8.46%   |
| Samsung Electronics | 12        | 15     | 5.97%   |
| SK hynix            | 10        | 11     | 4.98%   |
| Intel               | 7         | 8      | 3.48%   |
| SanDisk             | 6         | 7      | 2.99%   |
| Kingston            | 5         | 5      | 2.49%   |
| Crucial             | 5         | 5      | 2.49%   |
| Micron Technology   | 3         | 4      | 1.49%   |
| LITEON              | 3         | 3      | 1.49%   |
| ASMT                | 2         | 2      | 1%      |
| A-DATA Technology   | 2         | 2      | 1%      |
| OCZ                 | 1         | 1      | 0.5%    |
| KingSpec            | 1         | 1      | 0.5%    |
| China               | 1         | 1      | 0.5%    |
| Apple               | 1         | 1      | 0.5%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 55        | 58     | 40.15%  |
| HGST    | 28        | 29     | 20.44%  |
| WDC     | 20        | 22     | 14.6%   |
| Hitachi | 17        | 18     | 12.41%  |
| Toshiba | 15        | 17     | 10.95%  |
| ASMT    | 1         | 1      | 0.73%   |
| Apple   | 1         | 1      | 0.73%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 136       | 146    | 68%     |
| SSD  | 50        | 53     | 25%     |
| NVMe | 14        | 18     | 7%      |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Samsung Electronics MZVLW128HEGR-000L2 128GB     | 1         | 2      | 25%     |
| Samsung Electronics MZNLN128HAHQ-000H1 128GB SSD | 1         | 1      | 25%     |
| Phison ESO128GTLC9-E8C-2 128GB                   | 1         | 1      | 25%     |
| Kingston SV300S37A120G 120GB SSD                 | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 3      | 50%     |
| Phison              | 1         | 1      | 25%     |
| Kingston            | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1549      | 2308   | 47.6%   |
| Works    | 1504      | 2307   | 46.22%  |
| Malfunc  | 197       | 217    | 6.05%   |
| Failed   | 4         | 5      | 0.12%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1860      | 49.35%  |
| Samsung Electronics              | 557       | 14.78%  |
| AMD                              | 375       | 9.95%   |
| SanDisk                          | 281       | 7.46%   |
| SK hynix                         | 186       | 4.93%   |
| Toshiba America Info Systems     | 93        | 2.47%   |
| Micron Technology                | 88        | 2.33%   |
| Kingston Technology Company      | 70        | 1.86%   |
| Phison Electronics               | 55        | 1.46%   |
| Micron/Crucial Technology        | 28        | 0.74%   |
| KIOXIA                           | 28        | 0.74%   |
| ADATA Technology                 | 25        | 0.66%   |
| Silicon Motion                   | 23        | 0.61%   |
| Union Memory (Shenzhen)          | 17        | 0.45%   |
| Lenovo                           | 15        | 0.4%    |
| Realtek Semiconductor            | 11        | 0.29%   |
| Lite-On Technology               | 10        | 0.27%   |
| Apple                            | 10        | 0.27%   |
| Solid State Storage Technology   | 9         | 0.24%   |
| Yangtze Memory Technologies      | 5         | 0.13%   |
| Nvidia                           | 5         | 0.13%   |
| Silicon Integrated Systems [SiS] | 3         | 0.08%   |
| MAXIO Technology (Hangzhou)      | 3         | 0.08%   |
| Biwin Storage Technology         | 3         | 0.08%   |
| Marvell Technology Group         | 2         | 0.05%   |
| INNOGRIT                         | 2         | 0.05%   |
| ASMedia Technology               | 2         | 0.05%   |
| Shenzhen Longsys Electronics     | 1         | 0.03%   |
| Seagate Technology               | 1         | 0.03%   |
| Netac Technology                 | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 355       | 9.09%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 325       | 8.32%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 275       | 7.04%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 176       | 4.51%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 173       | 4.43%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 147       | 3.76%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 116       | 2.97%   |
| Samsung NVMe SSD Controller 980                                                | 115       | 2.94%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 114       | 2.92%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 101       | 2.59%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 96        | 2.46%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 94        | 2.41%   |
| Micron Non-Volatile memory controller                                          | 88        | 2.25%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 86        | 2.2%    |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 74        | 1.89%   |
| Intel Volume Management Device NVMe RAID Controller                            | 73        | 1.87%   |
| Intel SSD 660P Series                                                          | 61        | 1.56%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 56        | 1.43%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 56        | 1.43%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 53        | 1.36%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 51        | 1.31%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 47        | 1.2%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 41        | 1.05%   |
| SanDisk Non-Volatile memory controller                                         | 39        | 1%      |
| SK hynix Non-Volatile memory controller                                        | 38        | 0.97%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 38        | 0.97%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 37        | 0.95%   |
| Phison E12 NVMe Controller                                                     | 34        | 0.87%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 32        | 0.82%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 31        | 0.79%   |
| Intel Tiger Lake-LP SATA Controller                                            | 30        | 0.77%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 30        | 0.77%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 29        | 0.74%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 27        | 0.69%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 26        | 0.67%   |
| Kingston Company Company Non-Volatile memory controller                        | 25        | 0.64%   |
| Intel Comet Lake SATA AHCI Controller                                          | 25        | 0.64%   |
| SK hynix BC511                                                                 | 24        | 0.61%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 24        | 0.61%   |
| Intel Non-Volatile memory controller                                           | 21        | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1941      | 51.77%  |
| NVMe | 1512      | 40.33%  |
| RAID | 249       | 6.64%   |
| IDE  | 47        | 1.25%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 2336      | 78.07%  |
| AMD    | 656       | 21.93%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 77        | 2.57%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 71        | 2.37%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 71        | 2.37%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 66        | 2.2%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 65        | 2.17%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 63        | 2.1%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 62        | 2.07%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 56        | 1.87%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 55        | 1.84%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 45        | 1.5%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 44        | 1.47%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 44        | 1.47%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 42        | 1.4%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 39        | 1.3%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 39        | 1.3%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 38        | 1.27%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 37        | 1.24%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 35        | 1.17%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 35        | 1.17%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 33        | 1.1%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 33        | 1.1%    |
| AMD Ryzen 5 5500U with Radeon Graphics        | 33        | 1.1%    |
| AMD Ryzen 7 4700U with Radeon Graphics        | 29        | 0.97%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 28        | 0.94%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 26        | 0.87%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 26        | 0.87%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 25        | 0.84%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 24        | 0.8%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 24        | 0.8%    |
| Intel Core i5-5300U CPU @ 2.30GHz             | 23        | 0.77%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 23        | 0.77%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 23        | 0.77%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 21        | 0.7%    |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 21        | 0.7%    |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 21        | 0.7%    |
| AMD Ryzen 5 4600H with Radeon Graphics        | 21        | 0.7%    |
| Intel Core i5-4210U CPU @ 1.70GHz             | 19        | 0.63%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 18        | 0.6%    |
| Intel Core i5-3230M CPU @ 2.60GHz             | 18        | 0.6%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 18        | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 867       | 28.96%  |
| Intel Core i5           | 758       | 25.32%  |
| Other                   | 233       | 7.78%   |
| AMD Ryzen 5             | 214       | 7.15%   |
| AMD Ryzen 7             | 205       | 6.85%   |
| Intel Core i3           | 172       | 5.74%   |
| Intel Celeron           | 83        | 2.77%   |
| Intel Core 2 Duo        | 73        | 2.44%   |
| AMD Ryzen 7 PRO         | 59        | 1.97%   |
| Intel Pentium           | 46        | 1.54%   |
| AMD Ryzen 9             | 40        | 1.34%   |
| Intel Atom              | 31        | 1.04%   |
| AMD Ryzen 3             | 28        | 0.94%   |
| Intel Core i9           | 27        | 0.9%    |
| AMD Ryzen 5 PRO         | 16        | 0.53%   |
| AMD A6                  | 15        | 0.5%    |
| Intel Xeon              | 12        | 0.4%    |
| AMD A10                 | 12        | 0.4%    |
| Intel Pentium Silver    | 11        | 0.37%   |
| AMD A4                  | 11        | 0.37%   |
| AMD A8                  | 8         | 0.27%   |
| AMD E2                  | 7         | 0.23%   |
| Intel Pentium Dual-Core | 6         | 0.2%    |
| Intel Genuine           | 6         | 0.2%    |
| Intel Core m3           | 5         | 0.17%   |
| AMD E1                  | 5         | 0.17%   |
| AMD E                   | 5         | 0.17%   |
| Intel Core 2            | 4         | 0.13%   |
| Intel Celeron Dual-Core | 3         | 0.1%    |
| AMD Athlon              | 3         | 0.1%    |
| AMD A12                 | 3         | 0.1%    |
| Intel Pentium Dual      | 2         | 0.07%   |
| Intel Core m7           | 2         | 0.07%   |
| Intel Core m5           | 2         | 0.07%   |
| Intel Core M            | 2         | 0.07%   |
| AMD Turion Neo X2       | 2         | 0.07%   |
| AMD Phenom II           | 2         | 0.07%   |
| AMD Athlon X2           | 2         | 0.07%   |
| Intel Pentium Gold      | 1         | 0.03%   |
| Intel Core 2 Solo       | 1         | 0.03%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 1166      | 38.94%  |
| 2      | 1114      | 37.21%  |
| 8      | 335       | 11.19%  |
| 6      | 324       | 10.82%  |
| 1      | 19        | 0.63%   |
| 14     | 15        | 0.5%    |
| 12     | 14        | 0.47%   |
| 10     | 5         | 0.17%   |
| 5      | 1         | 0.03%   |
| 3      | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2992      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 2557      | 85.35%  |
| 1      | 439       | 14.65%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2931      | 97.9%   |
| Unknown        | 60        | 2%      |
| 32-bit         | 3         | 0.1%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 911       | 29.34%  |
| 0x906ea    | 134       | 4.32%   |
| 0x806ea    | 133       | 4.28%   |
| 0x306a9    | 117       | 3.77%   |
| 0x806ec    | 111       | 3.57%   |
| 0x806c1    | 102       | 3.29%   |
| 0x206a7    | 101       | 3.25%   |
| 0x406e3    | 98        | 3.16%   |
| 0x306d4    | 88        | 2.83%   |
| 0x906e9    | 83        | 2.67%   |
| 0x40651    | 83        | 2.67%   |
| 0x806e9    | 76        | 2.45%   |
| 0x0a50000c | 73        | 2.35%   |
| 0x08108102 | 69        | 2.22%   |
| 0x306c3    | 65        | 2.09%   |
| 0x08600106 | 63        | 2.03%   |
| 0xa0652    | 60        | 1.93%   |
| 0x08108109 | 47        | 1.51%   |
| 0x20655    | 46        | 1.48%   |
| 0x506e3    | 44        | 1.42%   |
| 0x08600104 | 40        | 1.29%   |
| 0x806eb    | 39        | 1.26%   |
| 0x08600103 | 38        | 1.22%   |
| 0x1067a    | 33        | 1.06%   |
| 0x08608103 | 29        | 0.93%   |
| 0x706e5    | 24        | 0.77%   |
| 0x0810100b | 24        | 0.77%   |
| 0x806d1    | 21        | 0.68%   |
| 0x406c4    | 21        | 0.68%   |
| 0x10676    | 19        | 0.61%   |
| 0x30678    | 18        | 0.58%   |
| 0x906ed    | 17        | 0.55%   |
| 0x906a3    | 17        | 0.55%   |
| 0x08608102 | 17        | 0.55%   |
| 0x706a1    | 16        | 0.52%   |
| 0x506c9    | 15        | 0.48%   |
| 0x20652    | 15        | 0.48%   |
| 0x0a404102 | 11        | 0.35%   |
| 0x06006705 | 11        | 0.35%   |
| 0x406c3    | 9         | 0.29%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 830       | 27.73%  |
| Haswell          | 206       | 6.88%   |
| Skylake          | 203       | 6.78%   |
| Zen 2            | 177       | 5.91%   |
| IvyBridge        | 175       | 5.85%   |
| TigerLake        | 158       | 5.28%   |
| Zen+             | 142       | 4.74%   |
| SandyBridge      | 142       | 4.74%   |
| Unknown          | 124       | 4.14%   |
| Broadwell        | 116       | 3.88%   |
| Zen 3            | 113       | 3.78%   |
| CometLake        | 96        | 3.21%   |
| Penryn           | 76        | 2.54%   |
| Westmere         | 72        | 2.41%   |
| Silvermont       | 64        | 2.14%   |
| Icelake          | 51        | 1.7%    |
| Zen              | 46        | 1.54%   |
| Goldmont plus    | 31        | 1.04%   |
| Excavator        | 30        | 1%      |
| Core             | 20        | 0.67%   |
| Goldmont         | 18        | 0.6%    |
| Alderlake Hybrid | 18        | 0.6%    |
| Bonnell          | 13        | 0.43%   |
| Bobcat           | 13        | 0.43%   |
| Puma             | 9         | 0.3%    |
| Nehalem          | 9         | 0.3%    |
| K10 Llano        | 7         | 0.23%   |
| Jaguar           | 7         | 0.23%   |
| Piledriver       | 6         | 0.2%    |
| K10              | 6         | 0.2%    |
| Tremont          | 5         | 0.17%   |
| Steamroller      | 3         | 0.1%    |
| K8 Hammer        | 3         | 0.1%    |
| P6               | 2         | 0.07%   |
| K8 & K10 hybrid  | 2         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2180      | 53.72%  |
| Nvidia                           | 1058      | 26.07%  |
| AMD                              | 816       | 20.11%  |
| Silicon Integrated Systems [SiS] | 3         | 0.07%   |
| ATI Technologies                 | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 192       | 4.65%   |
| Intel UHD Graphics 620                                                                   | 186       | 4.51%   |
| AMD Renoir                                                                               | 169       | 4.1%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 166       | 4.02%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 144       | 3.49%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 143       | 3.47%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 137       | 3.32%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 127       | 3.08%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 116       | 2.81%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 110       | 2.67%   |
| Intel HD Graphics 620                                                                    | 105       | 2.54%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 104       | 2.52%   |
| Intel HD Graphics 5500                                                                   | 97        | 2.35%   |
| Intel HD Graphics 630                                                                    | 88        | 2.13%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 88        | 2.13%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 84        | 2.04%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 72        | 1.75%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 68        | 1.65%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 67        | 1.62%   |
| AMD Lucienne                                                                             | 64        | 1.55%   |
| Intel HD Graphics 530                                                                    | 54        | 1.31%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 52        | 1.26%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 49        | 1.19%   |
| Intel Core Processor Integrated Graphics Controller                                      | 49        | 1.19%   |
| Nvidia GP108M [GeForce MX150]                                                            | 45        | 1.09%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 41        | 0.99%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 40        | 0.97%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 40        | 0.97%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 35        | 0.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 35        | 0.85%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 35        | 0.85%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 31        | 0.75%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 29        | 0.7%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 28        | 0.68%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 27        | 0.65%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 27        | 0.65%   |
| Nvidia TU117M                                                                            | 26        | 0.63%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 26        | 0.63%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 26        | 0.63%   |
| AMD Rembrandt [Radeon 680M]                                                              | 25        | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1244      | 41.43%  |
| Intel + Nvidia           | 805       | 26.81%  |
| 1 x AMD                  | 510       | 16.98%  |
| AMD + Nvidia             | 127       | 4.23%   |
| 1 x Nvidia               | 125       | 4.16%   |
| Intel + AMD              | 123       | 4.1%    |
| 2 x AMD                  | 55        | 1.83%   |
| Other                    | 3         | 0.1%    |
| 2 x Intel                | 3         | 0.1%    |
| 1 x SiS                  | 3         | 0.1%    |
| Intel + 2 x Nvidia       | 2         | 0.07%   |
| Intel + AMD + 1 x Nvidia | 2         | 0.07%   |
| 2 x Nvidia               | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2371      | 78.56%  |
| Proprietary | 638       | 21.14%  |
| Unknown     | 9         | 0.3%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2069      | 67.31%  |
| 0.01-0.5   | 308       | 10.02%  |
| 1.01-2.0   | 276       | 8.98%   |
| 3.01-4.0   | 158       | 5.14%   |
| 0.51-1.0   | 123       | 4%      |
| 7.01-8.0   | 63        | 2.05%   |
| 5.01-6.0   | 57        | 1.85%   |
| 2.01-3.0   | 12        | 0.39%   |
| 8.01-16.0  | 8         | 0.26%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 722       | 19.67%  |
| BOE                     | 521       | 14.19%  |
| LG Display              | 481       | 13.1%   |
| Chimei Innolux          | 480       | 13.08%  |
| Samsung Electronics     | 310       | 8.44%   |
| Sharp                   | 164       | 4.47%   |
| Dell                    | 133       | 3.62%   |
| Goldstar                | 93        | 2.53%   |
| PANDA                   | 92        | 2.51%   |
| Lenovo                  | 77        | 2.1%    |
| Apple                   | 59        | 1.61%   |
| Hewlett-Packard         | 54        | 1.47%   |
| Acer                    | 41        | 1.12%   |
| AOC                     | 37        | 1.01%   |
| BenQ                    | 36        | 0.98%   |
| InfoVision              | 35        | 0.95%   |
| Philips                 | 32        | 0.87%   |
| CSO                     | 28        | 0.76%   |
| Chi Mei Optoelectronics | 28        | 0.76%   |
| Ancor Communications    | 27        | 0.74%   |
| Iiyama                  | 22        | 0.6%    |
| Sony                    | 15        | 0.41%   |
| ViewSonic               | 12        | 0.33%   |
| ASUSTek Computer        | 12        | 0.33%   |
| TMX                     | 8         | 0.22%   |
| JDI                     | 8         | 0.22%   |
| CPT                     | 8         | 0.22%   |
| NEC Computers           | 7         | 0.19%   |
| MSI                     | 7         | 0.19%   |
| Toshiba                 | 6         | 0.16%   |
| Panasonic               | 6         | 0.16%   |
| Pixio                   | 5         | 0.14%   |
| LG Philips              | 5         | 0.14%   |
| InnoLux Display         | 5         | 0.14%   |
| Eizo                    | 5         | 0.14%   |
| LGD                     | 4         | 0.11%   |
| HannStar                | 4         | 0.11%   |
| Fujitsu Siemens         | 4         | 0.11%   |
| Vizio                   | 3         | 0.08%   |
| KDC                     | 3         | 0.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 41        | 1.1%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 39        | 1.05%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch       | 31        | 0.83%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 31        | 0.83%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 24        | 0.65%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 23        | 0.62%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch       | 23        | 0.62%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch       | 19        | 0.51%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                | 17        | 0.46%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 15        | 0.4%    |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 15        | 0.4%    |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 15        | 0.4%    |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch        | 15        | 0.4%    |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 14        | 0.38%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch         | 14        | 0.38%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 14        | 0.38%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 13        | 0.35%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch             | 13        | 0.35%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch     | 13        | 0.35%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 13        | 0.35%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 13        | 0.35%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch         | 12        | 0.32%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch     | 12        | 0.32%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 12        | 0.32%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch              | 11        | 0.3%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 11        | 0.3%    |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 11        | 0.3%    |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                | 11        | 0.3%    |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch       | 11        | 0.3%    |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch        | 11        | 0.3%    |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch       | 11        | 0.3%    |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch              | 10        | 0.27%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch         | 10        | 0.27%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 10        | 0.27%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch      | 10        | 0.27%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch        | 10        | 0.27%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch        | 10        | 0.27%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 10        | 0.27%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch              | 9         | 0.24%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch              | 9         | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1787      | 52.57%  |
| 1366x768 (WXGA)    | 667       | 19.62%  |
| 3840x2160 (4K)     | 179       | 5.27%   |
| 2560x1440 (QHD)    | 140       | 4.12%   |
| 1600x900 (HD+)     | 126       | 3.71%   |
| 1920x1200 (WUXGA)  | 68        | 2%      |
| 1280x800 (WXGA)    | 52        | 1.53%   |
| 2560x1600          | 41        | 1.21%   |
| 1440x900 (WXGA+)   | 37        | 1.09%   |
| 2880x1800          | 33        | 0.97%   |
| 1680x1050 (WSXGA+) | 32        | 0.94%   |
| 3440x1440          | 25        | 0.74%   |
| 3840x2400          | 24        | 0.71%   |
| 2560x1080          | 23        | 0.68%   |
| 3200x1800 (QHD+)   | 18        | 0.53%   |
| 2256x1504          | 17        | 0.5%    |
| 1280x1024 (SXGA)   | 17        | 0.5%    |
| 2160x1440          | 14        | 0.41%   |
| 1360x768           | 13        | 0.38%   |
| 3072x1920          | 8         | 0.24%   |
| 3000x2000          | 8         | 0.24%   |
| 3840x1600          | 6         | 0.18%   |
| 2240x1400          | 6         | 0.18%   |
| 1024x600           | 6         | 0.18%   |
| Unknown            | 6         | 0.18%   |
| 1280x720 (HD)      | 5         | 0.15%   |
| 1920x540           | 4         | 0.12%   |
| 3840x1080          | 3         | 0.09%   |
| 2520x1680          | 3         | 0.09%   |
| 1680x945           | 3         | 0.09%   |
| 1600x1200          | 3         | 0.09%   |
| 800x1280           | 2         | 0.06%   |
| 3456x2160          | 2         | 0.06%   |
| 3200x2000          | 2         | 0.06%   |
| 1920x1280          | 2         | 0.06%   |
| 1400x1050          | 2         | 0.06%   |
| 7680x1440          | 1         | 0.03%   |
| 5520x1080          | 1         | 0.03%   |
| 4480x1440          | 1         | 0.03%   |
| 3840x1100          | 1         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1435      | 39.08%  |
| 13      | 575       | 15.66%  |
| 14      | 515       | 14.03%  |
| 27      | 177       | 4.82%   |
| 17      | 174       | 4.74%   |
| 24      | 154       | 4.19%   |
| 23      | 119       | 3.24%   |
| 12      | 95        | 2.59%   |
| 21      | 69        | 1.88%   |
| 16      | 45        | 1.23%   |
| 34      | 43        | 1.17%   |
| Unknown | 43        | 1.17%   |
| 11      | 41        | 1.12%   |
| 18      | 28        | 0.76%   |
| 31      | 25        | 0.68%   |
| 19      | 19        | 0.52%   |
| 22      | 16        | 0.44%   |
| 20      | 15        | 0.41%   |
| 10      | 11        | 0.3%    |
| 84      | 8         | 0.22%   |
| 72      | 8         | 0.22%   |
| 54      | 6         | 0.16%   |
| 40      | 6         | 0.16%   |
| 29      | 6         | 0.16%   |
| 28      | 6         | 0.16%   |
| 37      | 5         | 0.14%   |
| 25      | 5         | 0.14%   |
| 48      | 4         | 0.11%   |
| 26      | 3         | 0.08%   |
| 42      | 2         | 0.05%   |
| 32      | 2         | 0.05%   |
| 74      | 1         | 0.03%   |
| 65      | 1         | 0.03%   |
| 55      | 1         | 0.03%   |
| 52      | 1         | 0.03%   |
| 50      | 1         | 0.03%   |
| 47      | 1         | 0.03%   |
| 46      | 1         | 0.03%   |
| 43      | 1         | 0.03%   |
| 38      | 1         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 2229      | 61.47%  |
| 201-300     | 440       | 12.13%  |
| 501-600     | 409       | 11.28%  |
| 351-400     | 217       | 5.98%   |
| 401-500     | 136       | 3.75%   |
| 601-700     | 56        | 1.54%   |
| 701-800     | 45        | 1.24%   |
| Unknown     | 43        | 1.19%   |
| 1501-2000   | 17        | 0.47%   |
| 1001-1500   | 16        | 0.44%   |
| 801-900     | 13        | 0.36%   |
| 901-1000    | 3         | 0.08%   |
| 101-200     | 2         | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 2676      | 84.66%  |
| 16/10   | 308       | 9.74%   |
| 3/2     | 54        | 1.71%   |
| 21/9    | 53        | 1.68%   |
| Unknown | 27        | 0.85%   |
| 5/4     | 18        | 0.57%   |
| 4/3     | 11        | 0.35%   |
| 32/9    | 6         | 0.19%   |
| 2.65    | 4         | 0.13%   |
| 0.62    | 2         | 0.06%   |
| 3.40    | 1         | 0.03%   |
| 1.03    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1437      | 39.29%  |
| 81-90          | 854       | 23.35%  |
| 201-250        | 300       | 8.2%    |
| 71-80          | 228       | 6.23%   |
| 301-350        | 180       | 4.92%   |
| 121-130        | 149       | 4.07%   |
| 61-70          | 92        | 2.52%   |
| 351-500        | 72        | 1.97%   |
| 251-300        | 54        | 1.48%   |
| 151-200        | 45        | 1.23%   |
| Unknown        | 43        | 1.18%   |
| 51-60          | 42        | 1.15%   |
| 111-120        | 33        | 0.9%    |
| 141-150        | 31        | 0.85%   |
| More than 1000 | 28        | 0.77%   |
| 501-1000       | 21        | 0.57%   |
| 91-100         | 18        | 0.49%   |
| 131-140        | 17        | 0.46%   |
| 41-50          | 12        | 0.33%   |
| 1-40           | 1         | 0.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1711      | 47.7%   |
| 101-120       | 756       | 21.08%  |
| 51-100        | 524       | 14.61%  |
| 161-240       | 352       | 9.81%   |
| More than 240 | 169       | 4.71%   |
| Unknown       | 43        | 1.2%    |
| 1-50          | 32        | 0.89%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 2376      | 77.65%  |
| 2     | 592       | 19.35%  |
| 3     | 75        | 2.45%   |
| 0     | 11        | 0.36%   |
| 4     | 6         | 0.2%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1826      | 38.71%  |
| Realtek Semiconductor             | 1585      | 33.6%   |
| Qualcomm Atheros                  | 597       | 12.66%  |
| Broadcom                          | 184       | 3.9%    |
| MediaTek                          | 91        | 1.93%   |
| Broadcom Limited                  | 47        | 1%      |
| Lenovo                            | 38        | 0.81%   |
| TP-Link                           | 30        | 0.64%   |
| ASIX Electronics                  | 27        | 0.57%   |
| Ericsson Business Mobile Networks | 25        | 0.53%   |
| Sierra Wireless                   | 24        | 0.51%   |
| Qualcomm                          | 23        | 0.49%   |
| Marvell Technology Group          | 23        | 0.49%   |
| Ralink Technology                 | 17        | 0.36%   |
| Ralink                            | 17        | 0.36%   |
| DisplayLink                       | 17        | 0.36%   |
| Hewlett-Packard                   | 14        | 0.3%    |
| Dell                              | 13        | 0.28%   |
| Samsung Electronics               | 12        | 0.25%   |
| Xiaomi                            | 11        | 0.23%   |
| Apple                             | 11        | 0.23%   |
| Huawei Technologies               | 8         | 0.17%   |
| D-Link                            | 8         | 0.17%   |
| Cypress Semiconductor             | 7         | 0.15%   |
| NetGear                           | 6         | 0.13%   |
| Google                            | 6         | 0.13%   |
| Linksys                           | 5         | 0.11%   |
| JMicron Technology                | 5         | 0.11%   |
| Fibocom                           | 5         | 0.11%   |
| Nvidia                            | 4         | 0.08%   |
| Silicon Integrated Systems [SiS]  | 3         | 0.06%   |
| Qualcomm Atheros Communications   | 3         | 0.06%   |
| Motorola PCS                      | 3         | 0.06%   |
| Microsoft                         | 3         | 0.06%   |
| ASUSTek Computer                  | 3         | 0.06%   |
| Arduino SA                        | 3         | 0.06%   |
| OnePlus Technology (Shenzhen)     | 2         | 0.04%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.02%   |
| U-Blox                            | 1         | 0.02%   |
| SparkFun                          | 1         | 0.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1065      | 18.86%  |
| Intel Wi-Fi 6 AX200                                               | 279       | 4.94%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 192       | 3.4%    |
| Intel Wireless 8265 / 8275                                        | 182       | 3.22%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 132       | 2.34%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 130       | 2.3%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 126       | 2.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 118       | 2.09%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 112       | 1.98%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 109       | 1.93%   |
| Intel Wi-Fi 6 AX201                                               | 109       | 1.93%   |
| Intel Wireless 7265                                               | 102       | 1.81%   |
| Intel Wireless 8260                                               | 90        | 1.59%   |
| Intel Wireless 7260                                               | 85        | 1.51%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 84        | 1.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 82        | 1.45%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 81        | 1.43%   |
| Intel Wireless 3165                                               | 72        | 1.28%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 71        | 1.26%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 70        | 1.24%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 67        | 1.19%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 63        | 1.12%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 62        | 1.1%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 58        | 1.03%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 55        | 0.97%   |
| Intel Ethernet Connection (4) I219-LM                             | 48        | 0.85%   |
| Intel Wireless-AC 9260                                            | 47        | 0.83%   |
| Intel Ethernet Connection (4) I219-V                              | 47        | 0.83%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 43        | 0.76%   |
| Intel Ethernet Connection I217-LM                                 | 40        | 0.71%   |
| Intel Wireless 3160                                               | 39        | 0.69%   |
| Intel Ethernet Connection (6) I219-V                              | 38        | 0.67%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 37        | 0.66%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 36        | 0.64%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 35        | 0.62%   |
| Intel Ethernet Connection (3) I218-LM                             | 34        | 0.6%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 33        | 0.58%   |
| Intel Ethernet Connection I219-LM                                 | 31        | 0.55%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 30        | 0.53%   |
| Intel Ethernet Connection I218-LM                                 | 30        | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1756      | 56.5%   |
| Qualcomm Atheros                  | 505       | 16.25%  |
| Realtek Semiconductor             | 409       | 13.16%  |
| Broadcom                          | 157       | 5.05%   |
| MediaTek                          | 88        | 2.83%   |
| Broadcom Limited                  | 37        | 1.19%   |
| Sierra Wireless                   | 24        | 0.77%   |
| TP-Link                           | 23        | 0.74%   |
| Qualcomm                          | 20        | 0.64%   |
| Ralink Technology                 | 17        | 0.55%   |
| Ralink                            | 17        | 0.55%   |
| Ericsson Business Mobile Networks | 11        | 0.35%   |
| Dell                              | 6         | 0.19%   |
| D-Link                            | 6         | 0.19%   |
| NetGear                           | 5         | 0.16%   |
| Linksys                           | 5         | 0.16%   |
| Hewlett-Packard                   | 5         | 0.16%   |
| Fibocom                           | 5         | 0.16%   |
| Qualcomm Atheros Communications   | 3         | 0.1%    |
| ASUSTek Computer                  | 3         | 0.1%    |
| Xiaomi                            | 2         | 0.06%   |
| Quectel Wireless Solutions        | 1         | 0.03%   |
| Microsoft                         | 1         | 0.03%   |
| Marvell Technology Group          | 1         | 0.03%   |
| Edimax Technology                 | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 279       | 8.95%   |
| Intel Wireless 8265 / 8275                                     | 182       | 5.84%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 130       | 4.17%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 126       | 4.04%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 112       | 3.59%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 109       | 3.49%   |
| Intel Wi-Fi 6 AX201                                            | 109       | 3.49%   |
| Intel Wireless 7265                                            | 102       | 3.27%   |
| Intel Wireless 8260                                            | 90        | 2.89%   |
| Intel Wireless 7260                                            | 85        | 2.73%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 84        | 2.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 82        | 2.63%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 81        | 2.6%    |
| Intel Wireless 3165                                            | 72        | 2.31%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 71        | 2.28%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 70        | 2.24%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 67        | 2.15%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 63        | 2.02%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 62        | 1.99%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 58        | 1.86%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 55        | 1.76%   |
| Intel Wireless-AC 9260                                         | 47        | 1.51%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 43        | 1.38%   |
| Intel Wireless 3160                                            | 39        | 1.25%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 37        | 1.19%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 36        | 1.15%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 35        | 1.12%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 33        | 1.06%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 30        | 0.96%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 28        | 0.9%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 24        | 0.77%   |
| Intel Centrino Ultimate-N 6300                                 | 24        | 0.77%   |
| Intel Centrino Advanced-N 6235                                 | 23        | 0.74%   |
| Broadcom BCM43142 802.11b/g/n                                  | 23        | 0.74%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 20        | 0.64%   |
| Intel Centrino Advanced-N 6200                                 | 20        | 0.64%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 17        | 0.55%   |
| Intel Centrino Wireless-N 2230                                 | 17        | 0.55%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 16        | 0.51%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 15        | 0.48%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1413      | 57.79%  |
| Intel                            | 638       | 26.09%  |
| Qualcomm Atheros                 | 139       | 5.69%   |
| Broadcom                         | 49        | 2%      |
| Lenovo                           | 37        | 1.51%   |
| ASIX Electronics                 | 27        | 1.1%    |
| Marvell Technology Group         | 22        | 0.9%    |
| DisplayLink                      | 17        | 0.7%    |
| Samsung Electronics              | 12        | 0.49%   |
| Apple                            | 11        | 0.45%   |
| Broadcom Limited                 | 10        | 0.41%   |
| Xiaomi                           | 9         | 0.37%   |
| TP-Link                          | 7         | 0.29%   |
| Cypress Semiconductor            | 7         | 0.29%   |
| Google                           | 6         | 0.25%   |
| JMicron Technology               | 5         | 0.2%    |
| Nvidia                           | 4         | 0.16%   |
| Huawei Technologies              | 4         | 0.16%   |
| Silicon Integrated Systems [SiS] | 3         | 0.12%   |
| Qualcomm                         | 3         | 0.12%   |
| Motorola PCS                     | 3         | 0.12%   |
| MediaTek                         | 3         | 0.12%   |
| Hewlett-Packard                  | 3         | 0.12%   |
| OnePlus Technology (Shenzhen)    | 2         | 0.08%   |
| Microsoft                        | 2         | 0.08%   |
| D-Link                           | 2         | 0.08%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.04%   |
| QNAP System                      | 1         | 0.04%   |
| NetGear                          | 1         | 0.04%   |
| LG Electronics                   | 1         | 0.04%   |
| ICS Advent                       | 1         | 0.04%   |
| HTC (High Tech Computer)         | 1         | 0.04%   |
| HMD Global                       | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1065      | 42.81%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 192       | 7.72%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 132       | 5.31%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 118       | 4.74%   |
| Intel Ethernet Connection (4) I219-LM                             | 48        | 1.93%   |
| Intel Ethernet Connection (4) I219-V                              | 47        | 1.89%   |
| Intel Ethernet Connection I217-LM                                 | 40        | 1.61%   |
| Intel Ethernet Connection (6) I219-V                              | 38        | 1.53%   |
| Intel Ethernet Connection (3) I218-LM                             | 34        | 1.37%   |
| Intel Ethernet Connection I219-LM                                 | 31        | 1.25%   |
| Intel Ethernet Connection I218-LM                                 | 30        | 1.21%   |
| Intel 82577LM Gigabit Network Connection                          | 27        | 1.09%   |
| Intel Ethernet Connection (7) I219-LM                             | 25        | 1%      |
| Intel 82567LM Gigabit Network Connection                          | 24        | 0.96%   |
| ASIX AX88179 Gigabit Ethernet                                     | 24        | 0.96%   |
| Intel Ethernet Connection (2) I219-LM                             | 23        | 0.92%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 21        | 0.84%   |
| Intel Ethernet Connection (6) I219-LM                             | 21        | 0.84%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 20        | 0.8%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 18        | 0.72%   |
| Intel Ethernet Connection (10) I219-V                             | 17        | 0.68%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 15        | 0.6%    |
| Intel Ethernet Connection I219-V                                  | 15        | 0.6%    |
| Realtek RTL8125 2.5GbE Controller                                 | 14        | 0.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 14        | 0.56%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 11        | 0.44%   |
| Intel Ethernet Connection (13) I219-V                             | 11        | 0.44%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 11        | 0.44%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 10        | 0.4%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 10        | 0.4%    |
| Intel Ethernet Connection (7) I219-V                              | 10        | 0.4%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 9         | 0.36%   |
| Lenovo USB-C Dock Ethernet                                        | 9         | 0.36%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 8         | 0.32%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 8         | 0.32%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 8         | 0.32%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 8         | 0.32%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 8         | 0.32%   |
| Intel Ethernet Connection (5) I219-LM                             | 8         | 0.32%   |
| Intel 82579V Gigabit Network Connection                           | 8         | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2970      | 55.69%  |
| Ethernet | 2323      | 43.56%  |
| Modem    | 37        | 0.69%   |
| Unknown  | 3         | 0.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2527      | 79.24%  |
| Ethernet | 661       | 20.73%  |
| Modem    | 1         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2116      | 70.63%  |
| 1     | 816       | 27.24%  |
| 3     | 37        | 1.23%   |
| 0     | 26        | 0.87%   |
| 4     | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2564      | 84.48%  |
| Yes  | 471       | 15.52%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1455      | 56.22%  |
| Realtek Semiconductor           | 248       | 9.58%   |
| Qualcomm Atheros Communications | 219       | 8.46%   |
| IMC Networks                    | 122       | 4.71%   |
| Broadcom                        | 116       | 4.48%   |
| Lite-On Technology              | 115       | 4.44%   |
| Foxconn / Hon Hai               | 95        | 3.67%   |
| Apple                           | 44        | 1.7%    |
| Realtek                         | 38        | 1.47%   |
| Dell                            | 32        | 1.24%   |
| Cambridge Silicon Radio         | 23        | 0.89%   |
| Hewlett-Packard                 | 15        | 0.58%   |
| Toshiba                         | 10        | 0.39%   |
| MediaTek                        | 10        | 0.39%   |
| Ralink                          | 9         | 0.35%   |
| USI                             | 6         | 0.23%   |
| Foxconn International           | 6         | 0.23%   |
| ASUSTek Computer                | 5         | 0.19%   |
| Chicony Electronics             | 3         | 0.12%   |
| Askey Computer                  | 3         | 0.12%   |
| TP-Link                         | 2         | 0.08%   |
| Ralink Technology               | 2         | 0.08%   |
| Alps Electric                   | 2         | 0.08%   |
| Unknown                         | 1         | 0.04%   |
| Syntek                          | 1         | 0.04%   |
| Opticis                         | 1         | 0.04%   |
| Micro Star International        | 1         | 0.04%   |
| Marvell Semiconductor           | 1         | 0.04%   |
| Edimax Technology               | 1         | 0.04%   |
| Dynex                           | 1         | 0.04%   |
| Belkin Components               | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 546       | 21.06%  |
| Intel AX200 Bluetooth                               | 261       | 10.07%  |
| Intel Bluetooth Device                              | 249       | 9.6%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 215       | 8.29%   |
| Realtek Bluetooth Radio                             | 150       | 5.78%   |
| Qualcomm Atheros  Bluetooth Device                  | 117       | 4.51%   |
| Lite-On Bluetooth Device                            | 80        | 3.09%   |
| Intel AX210 Bluetooth                               | 67        | 2.58%   |
| Realtek  Bluetooth 4.2 Adapter                      | 57        | 2.2%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 46        | 1.77%   |
| IMC Networks Bluetooth Radio                        | 41        | 1.58%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 40        | 1.54%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 40        | 1.54%   |
| Foxconn / Hon Hai Bluetooth Device                  | 39        | 1.5%    |
| Realtek Bluetooth Radio                             | 38        | 1.47%   |
| IMC Networks Wireless_Device                        | 34        | 1.31%   |
| Intel Wireless-AC 3168 Bluetooth                    | 33        | 1.27%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 31        | 1.2%    |
| IMC Networks Bluetooth Device                       | 30        | 1.16%   |
| Foxconn / Hon Hai Wireless_Device                   | 30        | 1.16%   |
| Apple Bluetooth Host Controller                     | 25        | 0.96%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 23        | 0.89%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 23        | 0.89%   |
| Broadcom BCM2045B (BDC-2.1)                         | 22        | 0.85%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 17        | 0.66%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 15        | 0.58%   |
| Lite-On Atheros AR3012 Bluetooth                    | 13        | 0.5%    |
| Apple Bluetooth USB Host Controller                 | 13        | 0.5%    |
| Realtek RTL8723B Bluetooth                          | 12        | 0.46%   |
| Lite-On Wireless_Device                             | 12        | 0.46%   |
| Dell DW375 Bluetooth Module                         | 12        | 0.46%   |
| Realtek RTL8821A Bluetooth                          | 11        | 0.42%   |
| Dell BCM20702A0 Bluetooth Module                    | 11        | 0.42%   |
| Broadcom HP Portable SoftSailing                    | 10        | 0.39%   |
| Ralink RT3290 Bluetooth                             | 9         | 0.35%   |
| MediaTek Wireless_Device                            | 9         | 0.35%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 9         | 0.35%   |
| HP Broadcom 2070 Bluetooth Combo                    | 9         | 0.35%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 8         | 0.31%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 8         | 0.31%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2301      | 58.7%   |
| AMD                              | 713       | 18.19%  |
| Nvidia                           | 565       | 14.41%  |
| C-Media Electronics              | 39        | 0.99%   |
| Lenovo                           | 34        | 0.87%   |
| Realtek Semiconductor            | 27        | 0.69%   |
| Logitech                         | 19        | 0.48%   |
| Texas Instruments                | 18        | 0.46%   |
| JMTek                            | 18        | 0.46%   |
| Focusrite-Novation               | 15        | 0.38%   |
| Apple                            | 14        | 0.36%   |
| Kingston Technology              | 12        | 0.31%   |
| GN Netcom                        | 11        | 0.28%   |
| Razer USA                        | 9         | 0.23%   |
| SteelSeries ApS                  | 8         | 0.2%    |
| Plantronics                      | 7         | 0.18%   |
| Creative Technology              | 7         | 0.18%   |
| Generalplus Technology           | 5         | 0.13%   |
| Sennheiser Communications        | 4         | 0.1%    |
| Samson Technologies              | 4         | 0.1%    |
| Hewlett-Packard                  | 4         | 0.1%    |
| Silicon Integrated Systems [SiS] | 3         | 0.08%   |
| Corsair                          | 3         | 0.08%   |
| ASUSTek Computer                 | 3         | 0.08%   |
| Yamaha                           | 2         | 0.05%   |
| XMOS                             | 2         | 0.05%   |
| Valve Software                   | 2         | 0.05%   |
| Sony                             | 2         | 0.05%   |
| Schiit Audio                     | 2         | 0.05%   |
| SAVITECH                         | 2         | 0.05%   |
| No brand                         | 2         | 0.05%   |
| Native Instruments               | 2         | 0.05%   |
| Medeli Electronics               | 2         | 0.05%   |
| Mackie Designs                   | 2         | 0.05%   |
| Jieli Technology                 | 2         | 0.05%   |
| GYROCOM C&C                      | 2         | 0.05%   |
| Goldvish                         | 2         | 0.05%   |
| CMX Systems                      | 2         | 0.05%   |
| Blue Microphones                 | 2         | 0.05%   |
| Barco Display Systems            | 2         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 550       | 11.42%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 433       | 8.99%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 283       | 5.88%   |
| Intel Cannon Lake PCH cAVS                                                                        | 205       | 4.26%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 195       | 4.05%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 170       | 3.53%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 158       | 3.28%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 143       | 2.97%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 121       | 2.51%   |
| Intel Broadwell-U Audio Controller                                                                | 115       | 2.39%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 111       | 2.3%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 111       | 2.3%    |
| Intel 8 Series HD Audio Controller                                                                | 111       | 2.3%    |
| Intel CM238 HD Audio Controller                                                                   | 104       | 2.16%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 98        | 2.03%   |
| Intel Comet Lake PCH cAVS                                                                         | 89        | 1.85%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 86        | 1.79%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 85        | 1.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 85        | 1.76%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 81        | 1.68%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 74        | 1.54%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 70        | 1.45%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 68        | 1.41%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 59        | 1.23%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 40        | 0.83%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 39        | 0.81%   |
| AMD FCH Azalia Controller                                                                         | 37        | 0.77%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 33        | 0.69%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 33        | 0.69%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 33        | 0.69%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 33        | 0.69%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 31        | 0.64%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 30        | 0.62%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 28        | 0.58%   |
| AMD Kabini HDMI/DP Audio                                                                          | 27        | 0.56%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 26        | 0.54%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 24        | 0.5%    |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 24        | 0.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 23        | 0.48%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 23        | 0.48%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 786       | 29.85%  |
| SK hynix            | 598       | 22.71%  |
| Micron Technology   | 352       | 13.37%  |
| Kingston            | 258       | 9.8%    |
| Crucial             | 163       | 6.19%   |
| Unknown             | 91        | 3.46%   |
| Ramaxel Technology  | 68        | 2.58%   |
| A-DATA Technology   | 55        | 2.09%   |
| Corsair             | 46        | 1.75%   |
| Elpida              | 37        | 1.41%   |
| G.Skill             | 18        | 0.68%   |
| Nanya Technology    | 16        | 0.61%   |
| Team                | 13        | 0.49%   |
| Transcend           | 12        | 0.46%   |
| Smart               | 12        | 0.46%   |
| Patriot             | 12        | 0.46%   |
| Unknown (ABCD)      | 10        | 0.38%   |
| GOODRAM             | 9         | 0.34%   |
| Smart Brazil        | 6         | 0.23%   |
| Unknown             | 6         | 0.23%   |
| Teikon              | 5         | 0.19%   |
| PNY                 | 5         | 0.19%   |
| Goldkey             | 5         | 0.19%   |
| AMD                 | 5         | 0.19%   |
| Apacer              | 4         | 0.15%   |
| V-GeN               | 3         | 0.11%   |
| Avant               | 3         | 0.11%   |
| 48spaces            | 3         | 0.11%   |
| Silicon Power       | 2         | 0.08%   |
| PKI/Kingston        | 2         | 0.08%   |
| Neo Forza           | 2         | 0.08%   |
| High Bridge         | 2         | 0.08%   |
| Wilk                | 1         | 0.04%   |
| V-Color             | 1         | 0.04%   |
| Unknown (C509)      | 1         | 0.04%   |
| Unknown (0x0C26)    | 1         | 0.04%   |
| Unknown (07F7)      | 1         | 0.04%   |
| Timetec             | 1         | 0.04%   |
| Spectek             | 1         | 0.04%   |
| SHARETRONIC         | 1         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 54        | 1.94%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 50        | 1.8%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 49        | 1.76%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 37        | 1.33%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 32        | 1.15%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 25        | 0.9%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 25        | 0.9%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 24        | 0.86%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 24        | 0.86%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 23        | 0.83%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 23        | 0.83%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 23        | 0.83%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 22        | 0.79%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 21        | 0.75%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 21        | 0.75%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 21        | 0.75%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 20        | 0.72%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 19        | 0.68%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 18        | 0.65%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 18        | 0.65%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 18        | 0.65%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 18        | 0.65%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 18        | 0.65%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 17        | 0.61%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 17        | 0.61%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 17        | 0.61%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 15        | 0.54%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 15        | 0.54%   |
| Samsung RAM M471A2K43CB1-CTD 16384MB SODIMM DDR4 8400MT/s        | 15        | 0.54%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 14        | 0.5%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 14        | 0.5%    |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 14        | 0.5%    |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 13        | 0.47%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 13        | 0.47%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 13        | 0.47%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 12        | 0.43%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 12        | 0.43%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 12        | 0.43%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 12        | 0.43%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8192MB SODIMM DDR4 2667MT/s     | 12        | 0.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 1291      | 59.63%  |
| DDR3    | 572       | 26.42%  |
| LPDDR4  | 101       | 4.67%   |
| LPDDR3  | 90        | 4.16%   |
| DDR2    | 35        | 1.62%   |
| SDRAM   | 29        | 1.34%   |
| LPDDR5  | 25        | 1.15%   |
| DDR5    | 16        | 0.74%   |
| Unknown | 4         | 0.18%   |
| DRAM    | 1         | 0.05%   |
| DDR     | 1         | 0.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1887      | 87.08%  |
| Row Of Chips | 238       | 10.98%  |
| Chip         | 25        | 1.15%   |
| Unknown      | 9         | 0.42%   |
| DIMM         | 8         | 0.37%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 1039      | 43.9%   |
| 4096  | 627       | 26.49%  |
| 16384 | 409       | 17.28%  |
| 2048  | 185       | 7.82%   |
| 32768 | 77        | 3.25%   |
| 1024  | 30        | 1.27%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 607       | 25.55%  |
| 3200    | 476       | 20.03%  |
| 1600    | 415       | 17.47%  |
| 2400    | 238       | 10.02%  |
| 2133    | 149       | 6.27%   |
| 1334    | 82        | 3.45%   |
| 1333    | 54        | 2.27%   |
| 4267    | 49        | 2.06%   |
| 3266    | 49        | 2.06%   |
| 1867    | 38        | 1.6%    |
| 1067    | 28        | 1.18%   |
| 667     | 26        | 1.09%   |
| 6400    | 24        | 1.01%   |
| 4800    | 17        | 0.72%   |
| 4266    | 17        | 0.72%   |
| 4199    | 17        | 0.72%   |
| 8400    | 16        | 0.67%   |
| Unknown | 13        | 0.55%   |
| 1066    | 12        | 0.51%   |
| 2048    | 10        | 0.42%   |
| 2933    | 8         | 0.34%   |
| 975     | 7         | 0.29%   |
| 800     | 7         | 0.29%   |
| 3733    | 3         | 0.13%   |
| 1866    | 2         | 0.08%   |
| 1200    | 2         | 0.08%   |
| 533     | 2         | 0.08%   |
| 400     | 2         | 0.08%   |
| 3400    | 1         | 0.04%   |
| 3000    | 1         | 0.04%   |
| 2666    | 1         | 0.04%   |
| 1776    | 1         | 0.04%   |
| 1639    | 1         | 0.04%   |
| 200     | 1         | 0.04%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 8         | 50%     |
| Samsung Electronics | 2         | 12.5%   |
| Prolific Technology | 2         | 12.5%   |
| Seiko Epson         | 1         | 6.25%   |
| Dymo-CoStar         | 1         | 6.25%   |
| Canon               | 1         | 6.25%   |
| Brother Industries  | 1         | 6.25%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port | 2         | 12.5%   |
| HP DeskJet 2130 series        | 2         | 12.5%   |
| Seiko Epson WF-2530 Series    | 1         | 6.25%   |
| Samsung SCX-3200 Series       | 1         | 6.25%   |
| Samsung M2020 Series          | 1         | 6.25%   |
| HP OfficeJet 5600 (USBHUB)    | 1         | 6.25%   |
| HP LaserJet 1320              | 1         | 6.25%   |
| HP ENVY 5000 series           | 1         | 6.25%   |
| HP DeskJet 840c               | 1         | 6.25%   |
| HP DeskJet 4100 series        | 1         | 6.25%   |
| HP DeskJet 2600 series        | 1         | 6.25%   |
| Dymo-CoStar LabelWriter 400   | 1         | 6.25%   |
| Canon PIXMA MG2500 Series     | 1         | 6.25%   |
| Brother HL-1110 series        | 1         | 6.25%   |

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
| Chicony Electronics                    | 658       | 23.91%  |
| IMC Networks                           | 349       | 12.68%  |
| Acer                                   | 282       | 10.25%  |
| Microdia                               | 260       | 9.45%   |
| Realtek Semiconductor                  | 204       | 7.41%   |
| Quanta                                 | 165       | 6%      |
| Sunplus Innovation Technology          | 138       | 5.01%   |
| Cheng Uei Precision Industry (Foxlink) | 100       | 3.63%   |
| Syntek                                 | 82        | 2.98%   |
| Lite-On Technology                     | 82        | 2.98%   |
| Suyin                                  | 51        | 1.85%   |
| Luxvisions Innotech Limited            | 50        | 1.82%   |
| Logitech                               | 49        | 1.78%   |
| Apple                                  | 49        | 1.78%   |
| Silicon Motion                         | 37        | 1.34%   |
| Alcor Micro                            | 29        | 1.05%   |
| Lenovo                                 | 20        | 0.73%   |
| Samsung Electronics                    | 17        | 0.62%   |
| ALi                                    | 11        | 0.4%    |
| Ricoh                                  | 10        | 0.36%   |
| Importek                               | 10        | 0.36%   |
| Sonix Technology                       | 9         | 0.33%   |
| Primax Electronics                     | 8         | 0.29%   |
| Microsoft                              | 7         | 0.25%   |
| Z-Star Microelectronics                | 5         | 0.18%   |
| Unknown                                | 5         | 0.18%   |
| SunplusIT                              | 5         | 0.18%   |
| Google                                 | 4         | 0.15%   |
| ARC International                      | 4         | 0.15%   |
| OmniVision Technologies                | 3         | 0.11%   |
| MacroSilicon                           | 3         | 0.11%   |
| Valve Software                         | 2         | 0.07%   |
| Razer USA                              | 2         | 0.07%   |
| LG Electronics                         | 2         | 0.07%   |
| Intel                                  | 2         | 0.07%   |
| icSpring                               | 2         | 0.07%   |
| Holitech                               | 2         | 0.07%   |
| HD WEBCAM                              | 2         | 0.07%   |
| DigiTech                               | 2         | 0.07%   |
| YSD-2053--200409                       | 1         | 0.04%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 190       | 6.83%   |
| Microdia Integrated_Webcam_HD                                              | 146       | 5.25%   |
| IMC Networks Integrated Camera                                             | 120       | 4.31%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 100       | 3.6%    |
| Acer Integrated Camera                                                     | 92        | 3.31%   |
| Chicony HD WebCam                                                          | 79        | 2.84%   |
| Realtek Integrated_Webcam_HD                                               | 73        | 2.62%   |
| Sunplus Integrated_Webcam_HD                                               | 63        | 2.27%   |
| Syntek Integrated Camera                                                   | 47        | 1.69%   |
| Quanta HD User Facing                                                      | 43        | 1.55%   |
| Lite-On Integrated Camera                                                  | 41        | 1.47%   |
| Acer HD Webcam                                                             | 37        | 1.33%   |
| Acer SunplusIT Integrated Camera                                           | 35        | 1.26%   |
| Chicony USB2.0 Camera                                                      | 30        | 1.08%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 29        | 1.04%   |
| Chicony Integrated Camera (1280x720@30)                                    | 28        | 1.01%   |
| Microdia Integrated Webcam                                                 | 27        | 0.97%   |
| Chicony HP HD Camera                                                       | 26        | 0.93%   |
| Acer Lenovo EasyCamera                                                     | 25        | 0.9%    |
| Chicony HD User Facing                                                     | 24        | 0.86%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 23        | 0.83%   |
| IMC Networks ov9734_azurewave_camera                                       | 22        | 0.79%   |
| Chicony HP Wide Vision HD Camera                                           | 22        | 0.79%   |
| Realtek USB Camera                                                         | 20        | 0.72%   |
| Chicony EasyCamera                                                         | 20        | 0.72%   |
| Realtek Integrated Webcam                                                  | 19        | 0.68%   |
| Quanta VGA WebCam                                                          | 19        | 0.68%   |
| Syntek Lenovo EasyCamera                                                   | 18        | 0.65%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 18        | 0.65%   |
| Lite-On HP HD Camera                                                       | 18        | 0.65%   |
| Sunplus HD WebCam                                                          | 17        | 0.61%   |
| Samsung Galaxy A5 (MTP)                                                    | 17        | 0.61%   |
| Quanta HP TrueVision HD Camera                                             | 17        | 0.61%   |
| Quanta HD Webcam                                                           | 17        | 0.61%   |
| Microdia Integrated Webcam HD                                              | 17        | 0.61%   |
| Chicony ThinkPad T490 Webcam                                               | 17        | 0.61%   |
| Chicony HP Truevision HD                                                   | 17        | 0.61%   |
| Acer BisonCam, NB Pro                                                      | 17        | 0.61%   |
| Chicony USB2.0 HD UVC WebCam                                               | 16        | 0.58%   |
| Chicony HP TrueVision HD Camera                                            | 16        | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 230       | 35.17%  |
| Validity Sensors                   | 175       | 26.76%  |
| Shenzhen Goodix Technology         | 122       | 18.65%  |
| Elan Microelectronics              | 42        | 6.42%   |
| Upek                               | 26        | 3.98%   |
| LighTuning Technology              | 26        | 3.98%   |
| AuthenTec                          | 20        | 3.06%   |
| STMicroelectronics                 | 8         | 1.22%   |
| Samsung Electronics                | 2         | 0.31%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.31%   |
| Focal-systems.Corp                 | 1         | 0.15%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 102       | 15.6%   |
| Shenzhen Goodix  FingerPrint Device                                        | 72        | 11.01%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 45        | 6.88%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 36        | 5.5%    |
| Unknown                                                                    | 34        | 5.2%    |
| Validity Sensors VFS495 Fingerprint Reader                                 | 27        | 4.13%   |
| Elan ELAN:Fingerprint                                                      | 27        | 4.13%   |
| Shenzhen Goodix Fingerprint Reader                                         | 25        | 3.82%   |
| Shenzhen Goodix FingerPrint                                                | 25        | 3.82%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 24        | 3.67%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 22        | 3.36%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 17        | 2.6%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 17        | 2.6%    |
| Validity Sensors Synaptics WBDI                                            | 16        | 2.45%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 15        | 2.29%   |
| Elan ELAN:ARM-M4                                                           | 15        | 2.29%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 14        | 2.14%   |
| Validity Sensors VFS491                                                    | 13        | 1.99%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 12        | 1.83%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 12        | 1.83%   |
| AuthenTec AES2810                                                          | 11        | 1.68%   |
| Validity Sensors Fingerprint scanner                                       | 9         | 1.38%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 8         | 1.22%   |
| STMicroelectronics Fingerprint Reader                                      | 8         | 1.22%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 0.76%   |
| Synaptics  WBDI                                                            | 5         | 0.76%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 0.61%   |
| Synaptics WBDI Device                                                      | 4         | 0.61%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 3         | 0.46%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 0.46%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 0.46%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 0.46%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.31%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 0.31%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 2         | 0.31%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.31%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 0.31%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 0.31%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.15%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 0.15%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 116       | 44.62%  |
| Broadcom                  | 100       | 38.46%  |
| Upek                      | 18        | 6.92%   |
| Lenovo                    | 10        | 3.85%   |
| O2 Micro                  | 5         | 1.92%   |
| SCM Microsystems          | 3         | 1.15%   |
| Yubico.com                | 2         | 0.77%   |
| Clay Logic                | 2         | 0.77%   |
| Hewlett-Packard           | 1         | 0.38%   |
| Gemalto (was Gemplus)     | 1         | 0.38%   |
| Chicony Electronics       | 1         | 0.38%   |
| Aladdin Knowledge Systems | 1         | 0.38%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 116       | 44.62%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 28        | 10.77%  |
| Broadcom 5880                                                                | 28        | 10.77%  |
| Broadcom BCM5880 Secure Applications Processor                               | 22        | 8.46%   |
| Broadcom 58200                                                               | 20        | 7.69%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 18        | 6.92%   |
| Lenovo Integrated Smart Card Reader                                          | 10        | 3.85%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 1.54%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 0.77%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 0.77%   |
| Clay Logic CanoKey Pigeon                                                    | 2         | 0.77%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.77%   |
| SCM Microsystems SCR3500 C Contact Reader                                    | 1         | 0.38%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.38%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.38%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.38%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.38%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.38%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1818      | 59.31%  |
| 1     | 967       | 31.55%  |
| 2     | 220       | 7.18%   |
| 3     | 51        | 1.66%   |
| 4     | 8         | 0.26%   |
| 7     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 642       | 41.23%  |
| Graphics card            | 286       | 18.37%  |
| Chipcard                 | 233       | 14.96%  |
| Multimedia controller    | 102       | 6.55%   |
| Net/wireless             | 93        | 5.97%   |
| Camera                   | 82        | 5.27%   |
| Bluetooth                | 28        | 1.8%    |
| Net/ethernet             | 17        | 1.09%   |
| Storage                  | 16        | 1.03%   |
| Sound                    | 14        | 0.9%    |
| Communication controller | 13        | 0.83%   |
| Card reader              | 10        | 0.64%   |
| Network                  | 7         | 0.45%   |
| Modem                    | 5         | 0.32%   |
| Wireless                 | 2         | 0.13%   |
| Dvb card                 | 2         | 0.13%   |
| Unassigned class         | 1         | 0.06%   |
| Storage/nvme             | 1         | 0.06%   |
| Storage/ata              | 1         | 0.06%   |
| Flash memory             | 1         | 0.06%   |
| Firewire controller      | 1         | 0.06%   |

