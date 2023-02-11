Debian - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Debian.

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

Total: 6072

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Apple         | MacBookAir7,2               | [352c998936](https://linux-hardware.org/?probe=352c998936) | Feb 01, 2023 |
| Toshiba       | Satellite P775              | [c03f7668ac](https://linux-hardware.org/?probe=c03f7668ac) | Feb 01, 2023 |
| HP            | Compaq nx9420 (ES444ET#A... | [ac78478b3b](https://linux-hardware.org/?probe=ac78478b3b) | Feb 01, 2023 |
| HUAWEI        | HLYL-WXX9                   | [6e8d45f76b](https://linux-hardware.org/?probe=6e8d45f76b) | Jan 31, 2023 |
| HP            | Notebook                    | [3cea0a0519](https://linux-hardware.org/?probe=3cea0a0519) | Jan 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [1c798340db](https://linux-hardware.org/?probe=1c798340db) | Jan 31, 2023 |
| Fujitsu       | LIFEBOOK S751               | [35948f3b5e](https://linux-hardware.org/?probe=35948f3b5e) | Jan 31, 2023 |
| HP            | Stream Laptop 14-cb1XX      | [3f17be7a85](https://linux-hardware.org/?probe=3f17be7a85) | Jan 30, 2023 |
| HP            | Laptop 17-bs0xx             | [ed57a59e39](https://linux-hardware.org/?probe=ed57a59e39) | Jan 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [3ecd91770e](https://linux-hardware.org/?probe=3ecd91770e) | Jan 30, 2023 |
| MSI           | GE60 0NC/GE60 0ND           | [a7ef98ea02](https://linux-hardware.org/?probe=a7ef98ea02) | Jan 30, 2023 |
| Acer          | Aspire 5552                 | [f1168775a7](https://linux-hardware.org/?probe=f1168775a7) | Jan 30, 2023 |
| Sony          | PCG-Z1VA(UC)                | [db4f48132e](https://linux-hardware.org/?probe=db4f48132e) | Jan 29, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [933e5a5b96](https://linux-hardware.org/?probe=933e5a5b96) | Jan 29, 2023 |
| Lenovo        | S21e-20 80M4                | [7017fcf775](https://linux-hardware.org/?probe=7017fcf775) | Jan 29, 2023 |
| Lenovo        | S21e-20 80M4                | [9afa780018](https://linux-hardware.org/?probe=9afa780018) | Jan 29, 2023 |
| Lenovo        | ThinkPad X220 42915CG       | [d058eeaad5](https://linux-hardware.org/?probe=d058eeaad5) | Jan 29, 2023 |
| HP            | ZBook 17 G3                 | [a1b5cdf1db](https://linux-hardware.org/?probe=a1b5cdf1db) | Jan 28, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [a88e343a83](https://linux-hardware.org/?probe=a88e343a83) | Jan 28, 2023 |
| ASUSTek       | UX410UAR                    | [e9ac16c8ef](https://linux-hardware.org/?probe=e9ac16c8ef) | Jan 28, 2023 |
| Dell          | Inspiron 3581               | [8c8db10ac2](https://linux-hardware.org/?probe=8c8db10ac2) | Jan 28, 2023 |
| HP            | ProBook 430 G6              | [24fd7df5b6](https://linux-hardware.org/?probe=24fd7df5b6) | Jan 28, 2023 |
| HP            | EliteBook 640 14 inch G9... | [bbdf827cef](https://linux-hardware.org/?probe=bbdf827cef) | Jan 27, 2023 |
| Acer          | Aspire 7750G                | [0b05244a15](https://linux-hardware.org/?probe=0b05244a15) | Jan 27, 2023 |
| Dell          | Latitude E7440              | [9ba078f6ab](https://linux-hardware.org/?probe=9ba078f6ab) | Jan 27, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [8ef4f014f2](https://linux-hardware.org/?probe=8ef4f014f2) | Jan 27, 2023 |
| Dell          | Latitude E5430 non-vPro     | [c83903fdc8](https://linux-hardware.org/?probe=c83903fdc8) | Jan 27, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | [376c580dcb](https://linux-hardware.org/?probe=376c580dcb) | Jan 27, 2023 |
| Lenovo        | ThinkPad E560 20EVCTO1WW    | [d3adeb692c](https://linux-hardware.org/?probe=d3adeb692c) | Jan 27, 2023 |
| Lenovo        | ThinkPad E560 20EVCTO1WW    | [46b1227255](https://linux-hardware.org/?probe=46b1227255) | Jan 27, 2023 |
| MSI           | Creator 17 B11UE            | [fcf56cfe4d](https://linux-hardware.org/?probe=fcf56cfe4d) | Jan 27, 2023 |
| Dell          | Latitude 5420               | [379a2dc9ab](https://linux-hardware.org/?probe=379a2dc9ab) | Jan 26, 2023 |
| Dell          | Latitude 5420               | [eec8ef8ddb](https://linux-hardware.org/?probe=eec8ef8ddb) | Jan 26, 2023 |
| Lenovo        | ThinkPad T440 20B7S0JC0P    | [1a36af70e8](https://linux-hardware.org/?probe=1a36af70e8) | Jan 26, 2023 |
| Google        | Careena                     | [75ca1a25dd](https://linux-hardware.org/?probe=75ca1a25dd) | Jan 26, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [a780c8d844](https://linux-hardware.org/?probe=a780c8d844) | Jan 25, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [e6a1506275](https://linux-hardware.org/?probe=e6a1506275) | Jan 25, 2023 |
| Apple         | MacBookPro10,1              | [4643f751cf](https://linux-hardware.org/?probe=4643f751cf) | Jan 25, 2023 |
| Dell          | Latitude E5430 non-vPro     | [3b96eac8a9](https://linux-hardware.org/?probe=3b96eac8a9) | Jan 25, 2023 |
| Panasonic     | FZ55-2                      | [dd9ddb12b6](https://linux-hardware.org/?probe=dd9ddb12b6) | Jan 25, 2023 |
| Lenovo        | ThinkPad X220 4291IR6       | [cc41fa5174](https://linux-hardware.org/?probe=cc41fa5174) | Jan 25, 2023 |
| Dell          | Vostro 5470                 | [bfd4198155](https://linux-hardware.org/?probe=bfd4198155) | Jan 25, 2023 |
| Samsung       | R710                        | [17a3e2ddd9](https://linux-hardware.org/?probe=17a3e2ddd9) | Jan 25, 2023 |
| HP            | ZBook 15 G3                 | [0bde1ca99a](https://linux-hardware.org/?probe=0bde1ca99a) | Jan 24, 2023 |
| Packard Be... | EasyNote MH36               | [07ba548a55](https://linux-hardware.org/?probe=07ba548a55) | Jan 24, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [bf21a44322](https://linux-hardware.org/?probe=bf21a44322) | Jan 23, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [fd6d2ec3c2](https://linux-hardware.org/?probe=fd6d2ec3c2) | Jan 23, 2023 |
| Samsung       | 300E4A/300E5A/300E7A        | [c8ec385a88](https://linux-hardware.org/?probe=c8ec385a88) | Jan 23, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [5648fbf4a0](https://linux-hardware.org/?probe=5648fbf4a0) | Jan 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [62ac206f7e](https://linux-hardware.org/?probe=62ac206f7e) | Jan 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | [5c7625e3f8](https://linux-hardware.org/?probe=5c7625e3f8) | Jan 23, 2023 |
| Fujitsu       | LIFEBOOK S751               | [ff727a3560](https://linux-hardware.org/?probe=ff727a3560) | Jan 22, 2023 |
| Fujitsu       | LIFEBOOK S751               | [df0676ac87](https://linux-hardware.org/?probe=df0676ac87) | Jan 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [ae270718a7](https://linux-hardware.org/?probe=ae270718a7) | Jan 22, 2023 |
| Dell          | G3 3579                     | [63298dcee9](https://linux-hardware.org/?probe=63298dcee9) | Jan 22, 2023 |
| Danew         | Dbook 131                   | [08911c133e](https://linux-hardware.org/?probe=08911c133e) | Jan 22, 2023 |
| Clevo         | W150ER                      | [ba5d06437c](https://linux-hardware.org/?probe=ba5d06437c) | Jan 21, 2023 |
| Acer          | Aspire F5-573G              | [68847eb1e6](https://linux-hardware.org/?probe=68847eb1e6) | Jan 21, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | [4b9d2e6e26](https://linux-hardware.org/?probe=4b9d2e6e26) | Jan 21, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | [15dde971f3](https://linux-hardware.org/?probe=15dde971f3) | Jan 21, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | [f5bb76ae13](https://linux-hardware.org/?probe=f5bb76ae13) | Jan 21, 2023 |
| Google        | Phaser                      | [557e69c5f1](https://linux-hardware.org/?probe=557e69c5f1) | Jan 21, 2023 |
| HP            | EliteBook Folio 9480m       | [cf1b67c224](https://linux-hardware.org/?probe=cf1b67c224) | Jan 21, 2023 |
| HP            | EliteBook 840 G3            | [06f6499264](https://linux-hardware.org/?probe=06f6499264) | Jan 21, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [27e484698b](https://linux-hardware.org/?probe=27e484698b) | Jan 20, 2023 |
| Dell          | Latitude 5501               | [d31f972a20](https://linux-hardware.org/?probe=d31f972a20) | Jan 20, 2023 |
| Lenovo        | G505 20240                  | [c591d80181](https://linux-hardware.org/?probe=c591d80181) | Jan 20, 2023 |
| UMAX          | VisionBook 12Wr             | [0707d617f7](https://linux-hardware.org/?probe=0707d617f7) | Jan 20, 2023 |
| Lenovo        | ThinkPad T490s 20NYS3SX0... | [3e08ab25c6](https://linux-hardware.org/?probe=3e08ab25c6) | Jan 20, 2023 |
| Dell          | Latitude E6540              | [34c018d211](https://linux-hardware.org/?probe=34c018d211) | Jan 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [80cb1c8239](https://linux-hardware.org/?probe=80cb1c8239) | Jan 19, 2023 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [7ecc4d20c3](https://linux-hardware.org/?probe=7ecc4d20c3) | Jan 19, 2023 |
| Lenovo        | ThinkPad E470 20H1004SMX    | [0d8528f0d2](https://linux-hardware.org/?probe=0d8528f0d2) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [0efa802a32](https://linux-hardware.org/?probe=0efa802a32) | Jan 19, 2023 |
| Dell          | XPS 15 9500                 | [606ba17221](https://linux-hardware.org/?probe=606ba17221) | Jan 19, 2023 |
| Insyde        | Braswell                    | [18526fdbe2](https://linux-hardware.org/?probe=18526fdbe2) | Jan 19, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [20749dc72f](https://linux-hardware.org/?probe=20749dc72f) | Jan 19, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | [db998abdae](https://linux-hardware.org/?probe=db998abdae) | Jan 19, 2023 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | [368ed9c856](https://linux-hardware.org/?probe=368ed9c856) | Jan 18, 2023 |
| Novatech      | NL40_50CU                   | [395dab7c43](https://linux-hardware.org/?probe=395dab7c43) | Jan 18, 2023 |
| HP            | Compaq 6910p                | [61d820a040](https://linux-hardware.org/?probe=61d820a040) | Jan 18, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [7b62e27d7a](https://linux-hardware.org/?probe=7b62e27d7a) | Jan 18, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W5... | [393e6cd6d2](https://linux-hardware.org/?probe=393e6cd6d2) | Jan 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [6dab459ed2](https://linux-hardware.org/?probe=6dab459ed2) | Jan 18, 2023 |
| HP            | EliteBook 820 G4            | [430b938694](https://linux-hardware.org/?probe=430b938694) | Jan 18, 2023 |
| HP            | EliteBook 2170p             | [46705d578e](https://linux-hardware.org/?probe=46705d578e) | Jan 18, 2023 |
| HP            | EliteBook 840 G4            | [952c81c314](https://linux-hardware.org/?probe=952c81c314) | Jan 18, 2023 |
| Dell          | Latitude 5500               | [e0ae9cb026](https://linux-hardware.org/?probe=e0ae9cb026) | Jan 17, 2023 |
| Lenovo        | ThinkPad X61 Tablet 7767... | [99e10e5d0f](https://linux-hardware.org/?probe=99e10e5d0f) | Jan 17, 2023 |
| Lenovo        | ThinkPad X61 Tablet 7767... | [624f47d1e3](https://linux-hardware.org/?probe=624f47d1e3) | Jan 17, 2023 |
| HP            | Compaq 6730b (GW687AV)      | [e967b291d5](https://linux-hardware.org/?probe=e967b291d5) | Jan 17, 2023 |
| Dell          | Inspiron 5502               | [43c4f532aa](https://linux-hardware.org/?probe=43c4f532aa) | Jan 17, 2023 |
| Lenovo        | IdeaPad 3 14ARE05 81W3      | [804fe39b80](https://linux-hardware.org/?probe=804fe39b80) | Jan 16, 2023 |
| Positivo      | CHT14B                      | [ab4518f121](https://linux-hardware.org/?probe=ab4518f121) | Jan 16, 2023 |
| Dell          | Inspiron 15-3567            | [020e19b05d](https://linux-hardware.org/?probe=020e19b05d) | Jan 16, 2023 |
| Lenovo        | ThinkPad T490s 20NX0076M... | [4c896e2c0e](https://linux-hardware.org/?probe=4c896e2c0e) | Jan 16, 2023 |
| Dell          | Inspiron 5502               | [9403074843](https://linux-hardware.org/?probe=9403074843) | Jan 16, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | [47d090108d](https://linux-hardware.org/?probe=47d090108d) | Jan 16, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | [219091b4e0](https://linux-hardware.org/?probe=219091b4e0) | Jan 15, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [a09ace045e](https://linux-hardware.org/?probe=a09ace045e) | Jan 15, 2023 |
| Apple         | MacBookAir5,1               | [f316bddcf2](https://linux-hardware.org/?probe=f316bddcf2) | Jan 15, 2023 |
| Acer          | Swift SF314-510G            | [b929f53536](https://linux-hardware.org/?probe=b929f53536) | Jan 15, 2023 |
| Dell          | Inspiron 15-3567            | [5426686264](https://linux-hardware.org/?probe=5426686264) | Jan 15, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [0ec206a07d](https://linux-hardware.org/?probe=0ec206a07d) | Jan 15, 2023 |
| HP            | EliteBook 8570w             | [53eb92efda](https://linux-hardware.org/?probe=53eb92efda) | Jan 15, 2023 |
| Lenovo        | ThinkPad T470 20HES0MV00    | [7e3b019181](https://linux-hardware.org/?probe=7e3b019181) | Jan 14, 2023 |
| HP            | Pavilion g6                 | [7d44980bca](https://linux-hardware.org/?probe=7d44980bca) | Jan 14, 2023 |
| Lenovo        | ThinkPad W520 4284W2U       | [576a509224](https://linux-hardware.org/?probe=576a509224) | Jan 14, 2023 |
| HP            | Laptop 14s-dk0xxx           | [6efb68b8da](https://linux-hardware.org/?probe=6efb68b8da) | Jan 14, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [0899d995dd](https://linux-hardware.org/?probe=0899d995dd) | Jan 14, 2023 |
| Apple         | MacBookPro12,1              | [1402c185c7](https://linux-hardware.org/?probe=1402c185c7) | Jan 14, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [f862a7e702](https://linux-hardware.org/?probe=f862a7e702) | Jan 14, 2023 |
| HONOR         | HLYL-WXX9                   | [e5b02d94cd](https://linux-hardware.org/?probe=e5b02d94cd) | Jan 14, 2023 |
| Dell          | Inspiron 11 - 3147          | [7193100d05](https://linux-hardware.org/?probe=7193100d05) | Jan 14, 2023 |
| HP            | Pavilion g6                 | [7672e1178a](https://linux-hardware.org/?probe=7672e1178a) | Jan 14, 2023 |
| Panasonic     | CFSZ6-2                     | [7a9f534294](https://linux-hardware.org/?probe=7a9f534294) | Jan 13, 2023 |
| Unknown       | Unknown                     | [ce69bfd81b](https://linux-hardware.org/?probe=ce69bfd81b) | Jan 13, 2023 |
| HP            | ProBook 445 G7              | [baf20b6914](https://linux-hardware.org/?probe=baf20b6914) | Jan 13, 2023 |
| ASUSTek       | X450LD                      | [859eb05149](https://linux-hardware.org/?probe=859eb05149) | Jan 13, 2023 |
| Dell          | Latitude 3320               | [f10d2a0741](https://linux-hardware.org/?probe=f10d2a0741) | Jan 13, 2023 |
| Dell          | Latitude 3320               | [613d7d50eb](https://linux-hardware.org/?probe=613d7d50eb) | Jan 13, 2023 |
| HP            | Compaq 6735b                | [01878ee027](https://linux-hardware.org/?probe=01878ee027) | Jan 12, 2023 |
| Dell          | Inspiron 3521               | [694d5be301](https://linux-hardware.org/?probe=694d5be301) | Jan 12, 2023 |
| Lenovo        | ThinkPad T460 20FMA0APAR    | [d4691b9969](https://linux-hardware.org/?probe=d4691b9969) | Jan 12, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [2316d5dc8b](https://linux-hardware.org/?probe=2316d5dc8b) | Jan 12, 2023 |
| Lenovo        | ThinkPad T470p 20J7S1JT0... | [856d91c1ca](https://linux-hardware.org/?probe=856d91c1ca) | Jan 12, 2023 |
| Gateway       | M-6854m                     | [76f293b62b](https://linux-hardware.org/?probe=76f293b62b) | Jan 12, 2023 |
| Dell          | Precision M4400             | [27da7825fb](https://linux-hardware.org/?probe=27da7825fb) | Jan 12, 2023 |
| Dell          | Inspiron 3421               | [055d61383e](https://linux-hardware.org/?probe=055d61383e) | Jan 12, 2023 |
| Acer          | Swift SF314-56              | [46aebbe972](https://linux-hardware.org/?probe=46aebbe972) | Jan 11, 2023 |
| Lenovo        | V110-15ISK 80TL             | [c00918a4c8](https://linux-hardware.org/?probe=c00918a4c8) | Jan 11, 2023 |
| SLIMBOOK      | PRO                         | [551a4bd378](https://linux-hardware.org/?probe=551a4bd378) | Jan 11, 2023 |
| HP            | ProBook 430 G5              | [6403930d67](https://linux-hardware.org/?probe=6403930d67) | Jan 11, 2023 |
| SmbiosType... | SmbiosType1_SystemProduc... | [6c67fc3995](https://linux-hardware.org/?probe=6c67fc3995) | Jan 11, 2023 |
| Aquarius      | NS585                       | [6fbcdf4d2f](https://linux-hardware.org/?probe=6fbcdf4d2f) | Jan 10, 2023 |
| HP            | Mini 110-1000               | [05c4656700](https://linux-hardware.org/?probe=05c4656700) | Jan 10, 2023 |
| SmbiosType... | SmbiosType1_SystemProduc... | [8367c27d81](https://linux-hardware.org/?probe=8367c27d81) | Jan 10, 2023 |
| Aquarius      | NS585                       | [2d37eb6524](https://linux-hardware.org/?probe=2d37eb6524) | Jan 10, 2023 |
| MPMAN         | CONVERTER 102               | [cc1eb56fbc](https://linux-hardware.org/?probe=cc1eb56fbc) | Jan 10, 2023 |
| HP            | 15                          | [f6b287dae1](https://linux-hardware.org/?probe=f6b287dae1) | Jan 10, 2023 |
| Acer          | Nitro AN517-54              | [8ea20821c8](https://linux-hardware.org/?probe=8ea20821c8) | Jan 10, 2023 |
| HP            | Compaq nx9420 (ES444ET#A... | [8d0b4a504d](https://linux-hardware.org/?probe=8d0b4a504d) | Jan 09, 2023 |
| Acer          | Aspire A515-54G             | [dea6736468](https://linux-hardware.org/?probe=dea6736468) | Jan 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [e85e91a7f2](https://linux-hardware.org/?probe=e85e91a7f2) | Jan 09, 2023 |
| Acer          | Aspire one 1-131            | [06c3411258](https://linux-hardware.org/?probe=06c3411258) | Jan 08, 2023 |
| HP            | ZBook 15 G3                 | [648dcae4c6](https://linux-hardware.org/?probe=648dcae4c6) | Jan 08, 2023 |
| ASUSTek       | K53U                        | [63849b1b5a](https://linux-hardware.org/?probe=63849b1b5a) | Jan 08, 2023 |
| Apple         | MacBookAir7,2               | [a4e777ea7d](https://linux-hardware.org/?probe=a4e777ea7d) | Jan 08, 2023 |
| Digma         | Pro Fortis M DN15P3-8CXN... | [077fd44029](https://linux-hardware.org/?probe=077fd44029) | Jan 08, 2023 |
| Lenovo        | ThinkPad T480s 20L8S2SX1... | [3c35917c78](https://linux-hardware.org/?probe=3c35917c78) | Jan 07, 2023 |
| ASUSTek       | X441NA                      | [e546680389](https://linux-hardware.org/?probe=e546680389) | Jan 07, 2023 |
| ASUSTek       | X441NA                      | [d556eedbbf](https://linux-hardware.org/?probe=d556eedbbf) | Jan 07, 2023 |
| Acer          | Aspire 7745G                | [9119962d1f](https://linux-hardware.org/?probe=9119962d1f) | Jan 07, 2023 |
| Gigabyte      | G5 GE                       | [d6a4584809](https://linux-hardware.org/?probe=d6a4584809) | Jan 07, 2023 |
| Dell          | Latitude 2110               | [9910f8985b](https://linux-hardware.org/?probe=9910f8985b) | Jan 07, 2023 |
| HP            | Elite x2 1011 G1 Tablet     | [28c9b60939](https://linux-hardware.org/?probe=28c9b60939) | Jan 07, 2023 |
| TUXEDO        | Aura 15 Gen1                | [fa91397209](https://linux-hardware.org/?probe=fa91397209) | Jan 07, 2023 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | [9776545fc4](https://linux-hardware.org/?probe=9776545fc4) | Jan 06, 2023 |
| Toshiba       | Satellite C55Dt-A           | [f3cfb5dbb5](https://linux-hardware.org/?probe=f3cfb5dbb5) | Jan 06, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | [9b0a8d487e](https://linux-hardware.org/?probe=9b0a8d487e) | Jan 06, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [d069cbd46b](https://linux-hardware.org/?probe=d069cbd46b) | Jan 06, 2023 |
| &#er &&       | Aspire 5100                 | [26da9e8ee1](https://linux-hardware.org/?probe=26da9e8ee1) | Jan 06, 2023 |
| Google        | Stout                       | [5ef816b9a6](https://linux-hardware.org/?probe=5ef816b9a6) | Jan 05, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [3245d27cb7](https://linux-hardware.org/?probe=3245d27cb7) | Jan 05, 2023 |
| HP            | EliteBook 840 Aero G8 No... | [b9f4ca82d2](https://linux-hardware.org/?probe=b9f4ca82d2) | Jan 05, 2023 |
| Acer          | Extensa 2540                | [4442f2c14a](https://linux-hardware.org/?probe=4442f2c14a) | Jan 05, 2023 |
| Acer          | Extensa 2540                | [ec8b49d7b0](https://linux-hardware.org/?probe=ec8b49d7b0) | Jan 04, 2023 |
| Dell          | Inspiron 15-3567            | [0042419ccb](https://linux-hardware.org/?probe=0042419ccb) | Jan 04, 2023 |
| Dell          | Inspiron 15-3567            | [82e42c0d42](https://linux-hardware.org/?probe=82e42c0d42) | Jan 04, 2023 |
| Lenovo        | ThinkPad T430s 2356BQ5      | [fdf6545b20](https://linux-hardware.org/?probe=fdf6545b20) | Jan 04, 2023 |
| HP            | 255 G8 Notebook PC          | [b876c5797a](https://linux-hardware.org/?probe=b876c5797a) | Jan 03, 2023 |
| Dell          | Inspiron 5566               | [258412ac0a](https://linux-hardware.org/?probe=258412ac0a) | Jan 03, 2023 |
| ASUSTek       | F5SL                        | [67882c0f69](https://linux-hardware.org/?probe=67882c0f69) | Jan 02, 2023 |
| ASUSTek       | F5SL                        | [42ef1fbf40](https://linux-hardware.org/?probe=42ef1fbf40) | Jan 02, 2023 |
| Acer          | Aspire V3-574G              | [a889bba557](https://linux-hardware.org/?probe=a889bba557) | Jan 02, 2023 |
| Acer          | Aspire ES1-711              | [735e062168](https://linux-hardware.org/?probe=735e062168) | Jan 02, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [90603e4ab3](https://linux-hardware.org/?probe=90603e4ab3) | Jan 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | [70c50fe035](https://linux-hardware.org/?probe=70c50fe035) | Jan 02, 2023 |
| MSI           | GE75 Raider 8SG             | [b6fa9be350](https://linux-hardware.org/?probe=b6fa9be350) | Jan 02, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [b54f3aab7b](https://linux-hardware.org/?probe=b54f3aab7b) | Jan 02, 2023 |
| HP            | 250 G8 Notebook PC          | [42e877ed10](https://linux-hardware.org/?probe=42e877ed10) | Jan 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | [8d4934bc09](https://linux-hardware.org/?probe=8d4934bc09) | Jan 02, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E0D    | [a1f966e5e8](https://linux-hardware.org/?probe=a1f966e5e8) | Jan 02, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [08fb8de608](https://linux-hardware.org/?probe=08fb8de608) | Jan 02, 2023 |
| Lenovo        | ThinkPad T430u 33519LC      | [87af3fa7f0](https://linux-hardware.org/?probe=87af3fa7f0) | Jan 02, 2023 |
| ASUSTek       | ZenBook UX333FN_U3300FN     | [750a40a3cc](https://linux-hardware.org/?probe=750a40a3cc) | Jan 02, 2023 |
| ASUSTek       | T100TA                      | [2c33e446d4](https://linux-hardware.org/?probe=2c33e446d4) | Jan 02, 2023 |
| Lenovo        | ThinkPad X260 20F5005NAU    | [3f68b8438c](https://linux-hardware.org/?probe=3f68b8438c) | Jan 02, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [bca75efbe5](https://linux-hardware.org/?probe=bca75efbe5) | Jan 02, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | [2396307897](https://linux-hardware.org/?probe=2396307897) | Jan 02, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [13df46e700](https://linux-hardware.org/?probe=13df46e700) | Jan 02, 2023 |
| ASUSTek       | TUF Gaming FX505DT_TUF50... | [f9db70d551](https://linux-hardware.org/?probe=f9db70d551) | Jan 01, 2023 |
| Lenovo        | G565 20071                  | [e974b446ae](https://linux-hardware.org/?probe=e974b446ae) | Jan 01, 2023 |
| Panasonic     | CF-54-2                     | [dfe3d2e06b](https://linux-hardware.org/?probe=dfe3d2e06b) | Jan 01, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [7474151c7e](https://linux-hardware.org/?probe=7474151c7e) | Jan 01, 2023 |
| Dell          | Inspiron 5566               | [9eadf42d31](https://linux-hardware.org/?probe=9eadf42d31) | Jan 01, 2023 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | [8d33275e7b](https://linux-hardware.org/?probe=8d33275e7b) | Dec 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [fb22f9430c](https://linux-hardware.org/?probe=fb22f9430c) | Dec 31, 2022 |
| Lenovo        | IdeaPad Y560                | [c9d3a1d0a3](https://linux-hardware.org/?probe=c9d3a1d0a3) | Dec 31, 2022 |
| Acer          | Aspire A514-54              | [5775c77a91](https://linux-hardware.org/?probe=5775c77a91) | Dec 31, 2022 |
| HP            | Compaq 6710b (KE207ES#AB... | [d7d0be3872](https://linux-hardware.org/?probe=d7d0be3872) | Dec 30, 2022 |
| Dell          | Inspiron 5490               | [c8a80649d2](https://linux-hardware.org/?probe=c8a80649d2) | Dec 30, 2022 |
| HP            | 255 G3                      | [89d6bd459c](https://linux-hardware.org/?probe=89d6bd459c) | Dec 30, 2022 |
| Toshiba       | Satellite L775-12V          | [2c601f6366](https://linux-hardware.org/?probe=2c601f6366) | Dec 29, 2022 |
| Lenovo        | ThinkPad T470p 20J7S1JT0... | [4b7bbb186f](https://linux-hardware.org/?probe=4b7bbb186f) | Dec 29, 2022 |
| MACHCREATO... | AB                          | [52a6beb872](https://linux-hardware.org/?probe=52a6beb872) | Dec 29, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7S... | [5bf3ff5c0e](https://linux-hardware.org/?probe=5bf3ff5c0e) | Dec 29, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7S... | [4f63c4474c](https://linux-hardware.org/?probe=4f63c4474c) | Dec 29, 2022 |
| HP            | EliteBook Folio 1040 G3     | [6aad572cd5](https://linux-hardware.org/?probe=6aad572cd5) | Dec 29, 2022 |
| HP            | ZBook 15 G6                 | [af1655497e](https://linux-hardware.org/?probe=af1655497e) | Dec 29, 2022 |
| HP            | ProBook 6570b               | [46fd918b7c](https://linux-hardware.org/?probe=46fd918b7c) | Dec 29, 2022 |
| HP            | Pavilion g7                 | [444363b7ec](https://linux-hardware.org/?probe=444363b7ec) | Dec 29, 2022 |
| Dell          | Inspiron 5490               | [457c2ae4ae](https://linux-hardware.org/?probe=457c2ae4ae) | Dec 28, 2022 |
| Dell          | Inspiron 5490               | [fdfd0f21c7](https://linux-hardware.org/?probe=fdfd0f21c7) | Dec 28, 2022 |
| Dell          | Inspiron 3583               | [41c7a16579](https://linux-hardware.org/?probe=41c7a16579) | Dec 28, 2022 |
| Toshiba       | Satellite L455D             | [35c085aa82](https://linux-hardware.org/?probe=35c085aa82) | Dec 28, 2022 |
| Dell          | Vostro 3400                 | [27f58a8ad1](https://linux-hardware.org/?probe=27f58a8ad1) | Dec 28, 2022 |
| Acer          | Aspire ES1-531              | [c29088a63f](https://linux-hardware.org/?probe=c29088a63f) | Dec 28, 2022 |
| HP            | ProBook 6470b               | [055705b3f2](https://linux-hardware.org/?probe=055705b3f2) | Dec 28, 2022 |
| Apple         | MacBookAir7,2               | [10dce91da1](https://linux-hardware.org/?probe=10dce91da1) | Dec 27, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [321cc72064](https://linux-hardware.org/?probe=321cc72064) | Dec 27, 2022 |
| Apple         | MacBookAir7,1               | [d174ffb318](https://linux-hardware.org/?probe=d174ffb318) | Dec 27, 2022 |
| MSI           | GE62 2QC                    | [dbd69d70ac](https://linux-hardware.org/?probe=dbd69d70ac) | Dec 27, 2022 |
| Panasonic     | FZ55-2                      | [1699b7c3b2](https://linux-hardware.org/?probe=1699b7c3b2) | Dec 27, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [78c6c15502](https://linux-hardware.org/?probe=78c6c15502) | Dec 27, 2022 |
| Notebook      | L14xMU                      | [7644bc65e2](https://linux-hardware.org/?probe=7644bc65e2) | Dec 27, 2022 |
| Dell          | Inspiron 1012               | [3dd6b8a416](https://linux-hardware.org/?probe=3dd6b8a416) | Dec 26, 2022 |
| Exo           | Smart Serie M               | [942ee3b035](https://linux-hardware.org/?probe=942ee3b035) | Dec 26, 2022 |
| Lenovo        | ThinkPad E560 20EV002FUS    | [3bb1c5cc47](https://linux-hardware.org/?probe=3bb1c5cc47) | Dec 26, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [29a54c4976](https://linux-hardware.org/?probe=29a54c4976) | Dec 26, 2022 |
| Acer          | Aspire ES1-533              | [3b5fa6d85a](https://linux-hardware.org/?probe=3b5fa6d85a) | Dec 26, 2022 |
| Lenovo        | ThinkPad X250 20CLS1UB00    | [fc8b2899fa](https://linux-hardware.org/?probe=fc8b2899fa) | Dec 25, 2022 |
| SANTECH       | NHx0DB,DE                   | [a0996d42bd](https://linux-hardware.org/?probe=a0996d42bd) | Dec 25, 2022 |
| HP            | 470 G8 Notebook PC          | [6d77c48324](https://linux-hardware.org/?probe=6d77c48324) | Dec 25, 2022 |
| ASUSTek       | G751JT                      | [16e989ff99](https://linux-hardware.org/?probe=16e989ff99) | Dec 25, 2022 |
| Dell          | Latitude E6520              | [33a51c934d](https://linux-hardware.org/?probe=33a51c934d) | Dec 25, 2022 |
| Dell          | Inspiron 5490               | [ea09a6daa8](https://linux-hardware.org/?probe=ea09a6daa8) | Dec 25, 2022 |
| Dell          | Inspiron 5490               | [45737153e4](https://linux-hardware.org/?probe=45737153e4) | Dec 25, 2022 |
| HP            | Laptop 15-bw0xx             | [42221f61fb](https://linux-hardware.org/?probe=42221f61fb) | Dec 25, 2022 |
| Unknown       | Apple MacBook Pro (14-in... | [8a5b919c91](https://linux-hardware.org/?probe=8a5b919c91) | Dec 24, 2022 |
| Medion        | E122X                       | [6e4e34bcc3](https://linux-hardware.org/?probe=6e4e34bcc3) | Dec 24, 2022 |
| Medion        | E122X                       | [bf41c45a7d](https://linux-hardware.org/?probe=bf41c45a7d) | Dec 24, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [096d4fc8c2](https://linux-hardware.org/?probe=096d4fc8c2) | Dec 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [c5f2f2db53](https://linux-hardware.org/?probe=c5f2f2db53) | Dec 24, 2022 |
| Lenovo        | ThinkPad X270 20HMS16200    | [6ac6e552a8](https://linux-hardware.org/?probe=6ac6e552a8) | Dec 24, 2022 |
| Dell          | Inspiron 5570               | [1c7e7f8dd2](https://linux-hardware.org/?probe=1c7e7f8dd2) | Dec 24, 2022 |
| HP            | Laptop 15-dy2xxx            | [df787f1286](https://linux-hardware.org/?probe=df787f1286) | Dec 24, 2022 |
| HP            | Laptop 15-dy2xxx            | [0a2ed74cfd](https://linux-hardware.org/?probe=0a2ed74cfd) | Dec 23, 2022 |
| Dell          | Latitude E7440              | [baae52327d](https://linux-hardware.org/?probe=baae52327d) | Dec 23, 2022 |
| Dell          | Latitude E7440              | [bc5d48b831](https://linux-hardware.org/?probe=bc5d48b831) | Dec 23, 2022 |
| Dell          | Latitude E7440              | [fde483d476](https://linux-hardware.org/?probe=fde483d476) | Dec 23, 2022 |
| Dell          | Latitude E7440              | [a746012ffd](https://linux-hardware.org/?probe=a746012ffd) | Dec 23, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | [9e5c4705fa](https://linux-hardware.org/?probe=9e5c4705fa) | Dec 23, 2022 |
| Dell          | Latitude D630               | [8175d003ce](https://linux-hardware.org/?probe=8175d003ce) | Dec 23, 2022 |
| Google        | Reks                        | [ecee690e6e](https://linux-hardware.org/?probe=ecee690e6e) | Dec 23, 2022 |
| Toshiba       | Satellite L10W-B-101        | [54d5cca493](https://linux-hardware.org/?probe=54d5cca493) | Dec 23, 2022 |
| Google        | Reks                        | [58b1b4cac1](https://linux-hardware.org/?probe=58b1b4cac1) | Dec 23, 2022 |
| Dell          | Inspiron 3501               | [297651d437](https://linux-hardware.org/?probe=297651d437) | Dec 23, 2022 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [79b015dcea](https://linux-hardware.org/?probe=79b015dcea) | Dec 23, 2022 |
| Dell          | Inspiron 3501               | [958ee9d145](https://linux-hardware.org/?probe=958ee9d145) | Dec 23, 2022 |
| Dell          | G3 3590                     | [d75d9e6663](https://linux-hardware.org/?probe=d75d9e6663) | Dec 23, 2022 |
| Lenovo        | ThinkPad X260 20F5005NAU    | [5f75bb423d](https://linux-hardware.org/?probe=5f75bb423d) | Dec 23, 2022 |
| Acer          | Aspire 4750                 | [3256c282db](https://linux-hardware.org/?probe=3256c282db) | Dec 23, 2022 |
| HP            | 255 G7 Notebook PC          | [5bedf1557b](https://linux-hardware.org/?probe=5bedf1557b) | Dec 23, 2022 |
| Dell          | Inspiron 5490               | [1c424b5f55](https://linux-hardware.org/?probe=1c424b5f55) | Dec 23, 2022 |
| Unknown       | Unknown                     | [f9c4fecaf4](https://linux-hardware.org/?probe=f9c4fecaf4) | Dec 23, 2022 |
| Unknown       | Unknown                     | [3832db2827](https://linux-hardware.org/?probe=3832db2827) | Dec 23, 2022 |
| Toshiba       | Satellite C55Dt-A           | [67294324c5](https://linux-hardware.org/?probe=67294324c5) | Dec 22, 2022 |
| Dell          | Latitude E7440              | [c6d28912f0](https://linux-hardware.org/?probe=c6d28912f0) | Dec 22, 2022 |
| Dell          | Latitude E7440              | [1a14f26bd3](https://linux-hardware.org/?probe=1a14f26bd3) | Dec 22, 2022 |
| Dell          | Latitude E7440              | [db77bb7a3f](https://linux-hardware.org/?probe=db77bb7a3f) | Dec 22, 2022 |
| Dell          | Latitude E7440              | [d2278ed94d](https://linux-hardware.org/?probe=d2278ed94d) | Dec 22, 2022 |
| Apple         | MacBookAir7,1               | [09ba8ccf48](https://linux-hardware.org/?probe=09ba8ccf48) | Dec 22, 2022 |
| Dell          | Latitude E7440              | [f4e79df709](https://linux-hardware.org/?probe=f4e79df709) | Dec 22, 2022 |
| Apple         | MacBookAir7,1               | [2c3febf6fa](https://linux-hardware.org/?probe=2c3febf6fa) | Dec 22, 2022 |
| Dell          | Latitude E7440              | [cddffa9123](https://linux-hardware.org/?probe=cddffa9123) | Dec 22, 2022 |
| Dell          | Latitude E7440              | [5f911806c8](https://linux-hardware.org/?probe=5f911806c8) | Dec 22, 2022 |
| Lenovo        | ThinkPad X260 20F5005NAU    | [844f589d20](https://linux-hardware.org/?probe=844f589d20) | Dec 22, 2022 |
| Dell          | Latitude D630               | [e1106d8868](https://linux-hardware.org/?probe=e1106d8868) | Dec 22, 2022 |
| Packard Be... | DOT S                       | [c26f1d77e6](https://linux-hardware.org/?probe=c26f1d77e6) | Dec 22, 2022 |
| HP            | Stream Notebook PC 13       | [b049c64ff7](https://linux-hardware.org/?probe=b049c64ff7) | Dec 22, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [5f132c928b](https://linux-hardware.org/?probe=5f132c928b) | Dec 22, 2022 |
| Dell          | G3 3590                     | [8038491eb0](https://linux-hardware.org/?probe=8038491eb0) | Dec 22, 2022 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | [16cae3015a](https://linux-hardware.org/?probe=16cae3015a) | Dec 21, 2022 |
| Apple         | MacBookAir7,2               | [b4e828bef3](https://linux-hardware.org/?probe=b4e828bef3) | Dec 21, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [28013105ef](https://linux-hardware.org/?probe=28013105ef) | Dec 21, 2022 |
| Dell          | Vostro 3583                 | [cf3c6eb18b](https://linux-hardware.org/?probe=cf3c6eb18b) | Dec 21, 2022 |
| Apple         | MacBookAir7,2               | [056d76bae8](https://linux-hardware.org/?probe=056d76bae8) | Dec 21, 2022 |
| Sony          | SVE1112M1EB                 | [74e100e63b](https://linux-hardware.org/?probe=74e100e63b) | Dec 21, 2022 |
| HP            | ZBook Power 15.6 inch G8... | [6b202d6cc2](https://linux-hardware.org/?probe=6b202d6cc2) | Dec 21, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [9438c80c85](https://linux-hardware.org/?probe=9438c80c85) | Dec 21, 2022 |
| Dell          | Inspiron 3501               | [449e38a14d](https://linux-hardware.org/?probe=449e38a14d) | Dec 21, 2022 |
| Dell          | G3 3590                     | [8272655600](https://linux-hardware.org/?probe=8272655600) | Dec 21, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [cd4fa20e66](https://linux-hardware.org/?probe=cd4fa20e66) | Dec 20, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [e676fe186f](https://linux-hardware.org/?probe=e676fe186f) | Dec 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [658e730bd3](https://linux-hardware.org/?probe=658e730bd3) | Dec 20, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [1e53c20bdd](https://linux-hardware.org/?probe=1e53c20bdd) | Dec 20, 2022 |
| ASUSTek       | T100TA                      | [1dc546e14a](https://linux-hardware.org/?probe=1dc546e14a) | Dec 20, 2022 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [2aeb8fd0cd](https://linux-hardware.org/?probe=2aeb8fd0cd) | Dec 19, 2022 |
| HP            | 255 G8 Notebook PC          | [08800ce691](https://linux-hardware.org/?probe=08800ce691) | Dec 19, 2022 |
| ASUSTek       | 900SD                       | [43d2c88062](https://linux-hardware.org/?probe=43d2c88062) | Dec 18, 2022 |
| Dell          | Inspiron 3501               | [956aaecbb9](https://linux-hardware.org/?probe=956aaecbb9) | Dec 18, 2022 |
| Dell          | Inspiron 3501               | [d5ceb48450](https://linux-hardware.org/?probe=d5ceb48450) | Dec 18, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | [756263bf48](https://linux-hardware.org/?probe=756263bf48) | Dec 18, 2022 |
| EUROCOM       | SCORPIUS 3D                 | [4fdf299276](https://linux-hardware.org/?probe=4fdf299276) | Dec 18, 2022 |
| Acer          | TravelMate P253             | [97d650e93f](https://linux-hardware.org/?probe=97d650e93f) | Dec 18, 2022 |
| Dell          | Latitude E6530              | [198a9bc936](https://linux-hardware.org/?probe=198a9bc936) | Dec 18, 2022 |
| HP            | Pavilion g7                 | [9829a799a0](https://linux-hardware.org/?probe=9829a799a0) | Dec 18, 2022 |
| Lenovo        | ThinkPad T470 20HES3JR02    | [f9e4638f19](https://linux-hardware.org/?probe=f9e4638f19) | Dec 18, 2022 |
| Dell          | Inspiron N5110              | [9e4f7a69c9](https://linux-hardware.org/?probe=9e4f7a69c9) | Dec 18, 2022 |
| Dell          | Latitude E4310              | [ace267f47c](https://linux-hardware.org/?probe=ace267f47c) | Dec 18, 2022 |
| Acer          | Aspire E5-573G              | [937a672cb0](https://linux-hardware.org/?probe=937a672cb0) | Dec 17, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [1e2531fdf1](https://linux-hardware.org/?probe=1e2531fdf1) | Dec 17, 2022 |
| Lenovo        | K14 Gen 1 21CUS02600        | [218654b079](https://linux-hardware.org/?probe=218654b079) | Dec 17, 2022 |
| Dell          | Inspiron 14 5425            | [e7d96ccda5](https://linux-hardware.org/?probe=e7d96ccda5) | Dec 17, 2022 |
| HP            | Notebook                    | [844d855f78](https://linux-hardware.org/?probe=844d855f78) | Dec 17, 2022 |
| Unknown       | Unknown                     | [208016df07](https://linux-hardware.org/?probe=208016df07) | Dec 17, 2022 |
| Acer          | TravelMate P253             | [80188fd5bf](https://linux-hardware.org/?probe=80188fd5bf) | Dec 16, 2022 |
| Dell          | Inspiron 7590               | [e8fb837cf5](https://linux-hardware.org/?probe=e8fb837cf5) | Dec 16, 2022 |
| Lenovo        | ThinkPad X230 23255NG       | [5cc0ff812b](https://linux-hardware.org/?probe=5cc0ff812b) | Dec 16, 2022 |
| Lenovo        | ThinkPad X230 23255NG       | [062a6ed428](https://linux-hardware.org/?probe=062a6ed428) | Dec 16, 2022 |
| Google        | Laser14                     | [b07a01ffe4](https://linux-hardware.org/?probe=b07a01ffe4) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [db670caadd](https://linux-hardware.org/?probe=db670caadd) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [d5cf351351](https://linux-hardware.org/?probe=d5cf351351) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [e2056deb8a](https://linux-hardware.org/?probe=e2056deb8a) | Dec 16, 2022 |
| Intel         | powered classmate PC        | [e0401225a2](https://linux-hardware.org/?probe=e0401225a2) | Dec 15, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [13ee187e45](https://linux-hardware.org/?probe=13ee187e45) | Dec 15, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [bec79890c8](https://linux-hardware.org/?probe=bec79890c8) | Dec 15, 2022 |
| Unknown       | T3 MRD                      | [909e1a1604](https://linux-hardware.org/?probe=909e1a1604) | Dec 15, 2022 |
| Google        | Cyan                        | [2b9f20b7da](https://linux-hardware.org/?probe=2b9f20b7da) | Dec 15, 2022 |
| Lenovo        | ThinkPad T430 2349I62       | [f7590c1a07](https://linux-hardware.org/?probe=f7590c1a07) | Dec 15, 2022 |
| Dell          | Latitude 3490               | [af008f69f1](https://linux-hardware.org/?probe=af008f69f1) | Dec 14, 2022 |
| Acer          | Aspire 5738                 | [c0c4581310](https://linux-hardware.org/?probe=c0c4581310) | Dec 14, 2022 |
| Apple         | MacBook6,1                  | [f19d464a26](https://linux-hardware.org/?probe=f19d464a26) | Dec 14, 2022 |
| ASUSTek       | M3N                         | [4e9f8e4c01](https://linux-hardware.org/?probe=4e9f8e4c01) | Dec 14, 2022 |
| ASUSTek       | X302LA                      | [8404a0b0c6](https://linux-hardware.org/?probe=8404a0b0c6) | Dec 14, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [14f87b8695](https://linux-hardware.org/?probe=14f87b8695) | Dec 13, 2022 |
| ASUSTek       | M3N                         | [ff772de294](https://linux-hardware.org/?probe=ff772de294) | Dec 13, 2022 |
| Dell          | Latitude 5520               | [7e5d86eaaf](https://linux-hardware.org/?probe=7e5d86eaaf) | Dec 13, 2022 |
| ASUSTek       | G75VW                       | [8d2a0ec4e4](https://linux-hardware.org/?probe=8d2a0ec4e4) | Dec 13, 2022 |
| Exo           | Smart Serie M               | [7fcf3d09bb](https://linux-hardware.org/?probe=7fcf3d09bb) | Dec 13, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [49fad98b7b](https://linux-hardware.org/?probe=49fad98b7b) | Dec 12, 2022 |
| Google        | Terra                       | [765deab389](https://linux-hardware.org/?probe=765deab389) | Dec 12, 2022 |
| HP            | EliteBook 8460p             | [95dc27194a](https://linux-hardware.org/?probe=95dc27194a) | Dec 12, 2022 |
| MSI           | GP73 Leopard 8RD            | [548de8bdae](https://linux-hardware.org/?probe=548de8bdae) | Dec 12, 2022 |
| Acer          | Aspire A515-56              | [5437de2b1b](https://linux-hardware.org/?probe=5437de2b1b) | Dec 12, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | [dc916ac78c](https://linux-hardware.org/?probe=dc916ac78c) | Dec 12, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | [2bfcc16f6b](https://linux-hardware.org/?probe=2bfcc16f6b) | Dec 12, 2022 |
| Google        | Enguarde                    | [60cce42479](https://linux-hardware.org/?probe=60cce42479) | Dec 12, 2022 |
| Lenovo        | ThinkPad R61e 7650DHU       | [138f60e67c](https://linux-hardware.org/?probe=138f60e67c) | Dec 12, 2022 |
| HP            | EliteBook 8460p             | [99c965b83f](https://linux-hardware.org/?probe=99c965b83f) | Dec 12, 2022 |
| Dell          | Latitude 5411               | [af806502e8](https://linux-hardware.org/?probe=af806502e8) | Dec 12, 2022 |
| Acer          | Nitro AN515-51              | [918c340b04](https://linux-hardware.org/?probe=918c340b04) | Dec 12, 2022 |
| Lenovo        | ThinkPad T470 20HES6HC00    | [ca9d609d9d](https://linux-hardware.org/?probe=ca9d609d9d) | Dec 12, 2022 |
| HP            | Laptop 15-db1xxx            | [3dcbd61f9e](https://linux-hardware.org/?probe=3dcbd61f9e) | Dec 12, 2022 |
| Lenovo        | ThinkPad X201 Tablet 309... | [cd7399049b](https://linux-hardware.org/?probe=cd7399049b) | Dec 11, 2022 |
| Intel         | Kabylake Platform           | [b5c2316016](https://linux-hardware.org/?probe=b5c2316016) | Dec 11, 2022 |
| Lenovo        | G770 20089                  | [f6f1441538](https://linux-hardware.org/?probe=f6f1441538) | Dec 11, 2022 |
| Lenovo        | G50-45 80E3                 | [754e028997](https://linux-hardware.org/?probe=754e028997) | Dec 11, 2022 |
| Lenovo        | G50-45 80E3                 | [fb2f97325d](https://linux-hardware.org/?probe=fb2f97325d) | Dec 11, 2022 |
| Dell          | Latitude 5480               | [01c96ca524](https://linux-hardware.org/?probe=01c96ca524) | Dec 11, 2022 |
| Dell          | Inspiron 13-5368            | [b4ea41e00f](https://linux-hardware.org/?probe=b4ea41e00f) | Dec 11, 2022 |
| Lenovo        | ThinkPad X270 20HMS16200    | [89e7835b90](https://linux-hardware.org/?probe=89e7835b90) | Dec 11, 2022 |
| Notebook      | NJ50_70CU                   | [f77f39af95](https://linux-hardware.org/?probe=f77f39af95) | Dec 11, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [4686ea3469](https://linux-hardware.org/?probe=4686ea3469) | Dec 11, 2022 |
| HP            | Laptop 15s-du3xxx           | [400a0b555d](https://linux-hardware.org/?probe=400a0b555d) | Dec 10, 2022 |
| Dell          | Latitude E7240              | [e0aca47e1b](https://linux-hardware.org/?probe=e0aca47e1b) | Dec 10, 2022 |
| ASUSTek       | VivoBook S15 X510UF         | [5f72ad2758](https://linux-hardware.org/?probe=5f72ad2758) | Dec 10, 2022 |
| Google        | Peppy                       | [59f9af1c52](https://linux-hardware.org/?probe=59f9af1c52) | Dec 10, 2022 |
| Toshiba       | TECRA A11                   | [766f95a2dd](https://linux-hardware.org/?probe=766f95a2dd) | Dec 10, 2022 |
| SANTECH       | NHx0DB,DE                   | [89e8d0f23e](https://linux-hardware.org/?probe=89e8d0f23e) | Dec 10, 2022 |
| Lenovo        | ThinkPad 13 20J10046US      | [170accb6cc](https://linux-hardware.org/?probe=170accb6cc) | Dec 09, 2022 |
| HP            | EliteBook 830 G8 Noteboo... | [5d96a0484a](https://linux-hardware.org/?probe=5d96a0484a) | Dec 08, 2022 |
| HUAWEI        | KLVL-WXXW                   | [adea8bc8d8](https://linux-hardware.org/?probe=adea8bc8d8) | Dec 08, 2022 |
| Toshiba       | Satellite C850-1LJ          | [4af2ab112f](https://linux-hardware.org/?probe=4af2ab112f) | Dec 08, 2022 |
| ASUSTek       | N750JV                      | [e06c6025f3](https://linux-hardware.org/?probe=e06c6025f3) | Dec 08, 2022 |
| Lenovo        | ThinkPad T61 889502U        | [b9d0a07e47](https://linux-hardware.org/?probe=b9d0a07e47) | Dec 08, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [09de0ec660](https://linux-hardware.org/?probe=09de0ec660) | Dec 08, 2022 |
| Lenovo        | ThinkPad T60 1953PKK        | [fc308e2f1c](https://linux-hardware.org/?probe=fc308e2f1c) | Dec 08, 2022 |
| Lenovo        | ThinkPad X201 Tablet 309... | [e13e889312](https://linux-hardware.org/?probe=e13e889312) | Dec 08, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [b0f77fed1f](https://linux-hardware.org/?probe=b0f77fed1f) | Dec 08, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [e56fd20ec9](https://linux-hardware.org/?probe=e56fd20ec9) | Dec 08, 2022 |
| Lenovo        | ThinkPad E495 20NES0J800    | [17182155b5](https://linux-hardware.org/?probe=17182155b5) | Dec 07, 2022 |
| Lenovo        | ThinkPad X230 2320CTO       | [b74f2893d0](https://linux-hardware.org/?probe=b74f2893d0) | Dec 07, 2022 |
| Panasonic     | CFMX4-1                     | [c25c16fc1a](https://linux-hardware.org/?probe=c25c16fc1a) | Dec 06, 2022 |
| Dell          | Latitude 5310               | [06d96a49a1](https://linux-hardware.org/?probe=06d96a49a1) | Dec 06, 2022 |
| HP            | EliteBook 8470p             | [e2be1fe149](https://linux-hardware.org/?probe=e2be1fe149) | Dec 06, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [4e43c26029](https://linux-hardware.org/?probe=4e43c26029) | Dec 06, 2022 |
| Dell          | Latitude 5411               | [62e5941721](https://linux-hardware.org/?probe=62e5941721) | Dec 06, 2022 |
| Dell          | Latitude 5411               | [e0815067bd](https://linux-hardware.org/?probe=e0815067bd) | Dec 06, 2022 |
| Dell          | Latitude 5310               | [f3801600ff](https://linux-hardware.org/?probe=f3801600ff) | Dec 06, 2022 |
| HP            | EliteBook 2570p             | [fc7d866c16](https://linux-hardware.org/?probe=fc7d866c16) | Dec 06, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [03aba4d315](https://linux-hardware.org/?probe=03aba4d315) | Dec 06, 2022 |
| Lenovo        | ThinkPad X230 2325SDE       | [4dc49eeb10](https://linux-hardware.org/?probe=4dc49eeb10) | Dec 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [0e42e5cbeb](https://linux-hardware.org/?probe=0e42e5cbeb) | Dec 06, 2022 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | [5b72cdbdb8](https://linux-hardware.org/?probe=5b72cdbdb8) | Dec 05, 2022 |
| ASUSTek       | X756UQK                     | [b473216b84](https://linux-hardware.org/?probe=b473216b84) | Dec 05, 2022 |
| HUAWEI        | BOD-WXX9                    | [3027fc2c2f](https://linux-hardware.org/?probe=3027fc2c2f) | Dec 05, 2022 |
| HUAWEI        | BOD-WXX9                    | [a07d55ca40](https://linux-hardware.org/?probe=a07d55ca40) | Dec 05, 2022 |
| MSI           | Creator 15M A9SD            | [f8e6206ba6](https://linux-hardware.org/?probe=f8e6206ba6) | Dec 05, 2022 |
| ASUSTek       | PU403UA                     | [20007b4296](https://linux-hardware.org/?probe=20007b4296) | Dec 05, 2022 |
| Acer          | Aspire A315-23G             | [41e6f6a3fa](https://linux-hardware.org/?probe=41e6f6a3fa) | Dec 05, 2022 |
| GMKtec        | NucBox5                     | [cdfbbcc5b2](https://linux-hardware.org/?probe=cdfbbcc5b2) | Dec 04, 2022 |
| ASUSTek       | S500CA                      | [267ffa24d1](https://linux-hardware.org/?probe=267ffa24d1) | Dec 04, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [f5be4eb37d](https://linux-hardware.org/?probe=f5be4eb37d) | Dec 04, 2022 |
| Toshiba       | dynabook R63/P              | [f51571b62c](https://linux-hardware.org/?probe=f51571b62c) | Dec 04, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [b475911aaf](https://linux-hardware.org/?probe=b475911aaf) | Dec 03, 2022 |
| Dell          | Inspiron 15-5578            | [61f5950e07](https://linux-hardware.org/?probe=61f5950e07) | Dec 03, 2022 |
| HP            | Laptop 15-da0xxx            | [9053b5cb8a](https://linux-hardware.org/?probe=9053b5cb8a) | Dec 03, 2022 |
| ASUSTek       | S500CA                      | [7145280e9e](https://linux-hardware.org/?probe=7145280e9e) | Dec 03, 2022 |
| Acer          | Aspire A315-21              | [91eb1913d7](https://linux-hardware.org/?probe=91eb1913d7) | Dec 03, 2022 |
| Unknown       | Unknown                     | [40917baf56](https://linux-hardware.org/?probe=40917baf56) | Dec 03, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [28ab0eb248](https://linux-hardware.org/?probe=28ab0eb248) | Dec 03, 2022 |
| Lenovo        | XiaoXinPro 16ACH 2021 82... | [2085f260e1](https://linux-hardware.org/?probe=2085f260e1) | Dec 03, 2022 |
| Lenovo        | ThinkPad X280 20KE0015BR    | [4c65d4e572](https://linux-hardware.org/?probe=4c65d4e572) | Dec 03, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21E3C... | [c99bd4ef76](https://linux-hardware.org/?probe=c99bd4ef76) | Dec 03, 2022 |
| Dell          | Inspiron 5566               | [54e06d37fc](https://linux-hardware.org/?probe=54e06d37fc) | Dec 02, 2022 |
| ASUSTek       | N750JV                      | [0fc50d63c4](https://linux-hardware.org/?probe=0fc50d63c4) | Dec 02, 2022 |
| Dell          | Latitude 5591               | [f5735acca7](https://linux-hardware.org/?probe=f5735acca7) | Dec 02, 2022 |
| HP            | Unknown                     | [741029c3af](https://linux-hardware.org/?probe=741029c3af) | Dec 02, 2022 |
| Aquarius      | NS585                       | [bbd3bd3ca6](https://linux-hardware.org/?probe=bbd3bd3ca6) | Dec 02, 2022 |
| Aquarius      | NS585                       | [50222418e5](https://linux-hardware.org/?probe=50222418e5) | Dec 02, 2022 |
| Aquarius      | NS585                       | [d55d40681f](https://linux-hardware.org/?probe=d55d40681f) | Dec 02, 2022 |
| Aquarius      | NS585                       | [9013a1cce6](https://linux-hardware.org/?probe=9013a1cce6) | Dec 02, 2022 |
| ASUSTek       | ROG Strix G731GU_G731GU     | [38ce706249](https://linux-hardware.org/?probe=38ce706249) | Dec 02, 2022 |
| ASUSTek       | ROG Strix G731GU_G731GU     | [546f2b82c9](https://linux-hardware.org/?probe=546f2b82c9) | Dec 02, 2022 |
| ASUSTek       | ROG Strix G731GU_G731GU     | [000d536e95](https://linux-hardware.org/?probe=000d536e95) | Dec 02, 2022 |
| HP            | 620                         | [6be09298b6](https://linux-hardware.org/?probe=6be09298b6) | Dec 01, 2022 |
| Lenovo        | ThinkPad T440p 20AN0079M... | [79261239c1](https://linux-hardware.org/?probe=79261239c1) | Dec 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [674157de54](https://linux-hardware.org/?probe=674157de54) | Dec 01, 2022 |
| Lenovo        | V330-15IKB 81AX             | [becc2328fd](https://linux-hardware.org/?probe=becc2328fd) | Dec 01, 2022 |
| MSI           | GL65 Leopard 10SDR          | [73c388fb61](https://linux-hardware.org/?probe=73c388fb61) | Dec 01, 2022 |
| MSI           | GL65 Leopard 10SDR          | [6d44ef56c9](https://linux-hardware.org/?probe=6d44ef56c9) | Dec 01, 2022 |
| HP            | Pavilion dv5                | [0fc7017b0c](https://linux-hardware.org/?probe=0fc7017b0c) | Nov 30, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [183243daeb](https://linux-hardware.org/?probe=183243daeb) | Nov 30, 2022 |
| Notebook      | RIM2520                     | [5f66abbb8b](https://linux-hardware.org/?probe=5f66abbb8b) | Nov 30, 2022 |
| HP            | Elite x2 1011 G1 Tablet     | [1a00258de3](https://linux-hardware.org/?probe=1a00258de3) | Nov 29, 2022 |
| Apple         | MacBookAir6,2               | [e0187bc636](https://linux-hardware.org/?probe=e0187bc636) | Nov 29, 2022 |
| Apple         | MacBookAir6,2               | [99eb1cfce0](https://linux-hardware.org/?probe=99eb1cfce0) | Nov 29, 2022 |
| Dell          | Latitude 7490               | [8934413cf0](https://linux-hardware.org/?probe=8934413cf0) | Nov 29, 2022 |
| Lenovo        | V310-14IKB 80T2             | [b7c976ef9c](https://linux-hardware.org/?probe=b7c976ef9c) | Nov 29, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [9c45563fb6](https://linux-hardware.org/?probe=9c45563fb6) | Nov 29, 2022 |
| Dell          | XPS 15 9500                 | [9c87ab493e](https://linux-hardware.org/?probe=9c87ab493e) | Nov 29, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [1e52ea39e4](https://linux-hardware.org/?probe=1e52ea39e4) | Nov 28, 2022 |
| Lenovo        | ThinkPad X301 2776LEG       | [ebaea0c805](https://linux-hardware.org/?probe=ebaea0c805) | Nov 28, 2022 |
| Dell          | Precision M6400             | [05f69c6917](https://linux-hardware.org/?probe=05f69c6917) | Nov 28, 2022 |
| HP            | ProBook 450 G5              | [e94fd64204](https://linux-hardware.org/?probe=e94fd64204) | Nov 28, 2022 |
| ASUSTek       | GL752VW                     | [edc0678b85](https://linux-hardware.org/?probe=edc0678b85) | Nov 28, 2022 |
| Dell          | XPS 15 9500                 | [f149afb5d1](https://linux-hardware.org/?probe=f149afb5d1) | Nov 28, 2022 |
| ASUSTek       | N61Vg                       | [b5cc07b253](https://linux-hardware.org/?probe=b5cc07b253) | Nov 27, 2022 |
| Lenovo        | ThinkPad T450 20BUS03J00    | [8423f90db0](https://linux-hardware.org/?probe=8423f90db0) | Nov 27, 2022 |
| Lenovo        | ThinkPad T520 4243F53       | [8f9e96442a](https://linux-hardware.org/?probe=8f9e96442a) | Nov 27, 2022 |
| Tactus        | GeoBook 140                 | [e3f4d734da](https://linux-hardware.org/?probe=e3f4d734da) | Nov 27, 2022 |
| ASUSTek       | VivoBook S15 X510UF         | [7bd68a8bb1](https://linux-hardware.org/?probe=7bd68a8bb1) | Nov 27, 2022 |
| HP            | Compaq nx9110 (DU432EA#A... | [1b54092e14](https://linux-hardware.org/?probe=1b54092e14) | Nov 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [32bfa52fc1](https://linux-hardware.org/?probe=32bfa52fc1) | Nov 27, 2022 |
| Lenovo        | ThinkPad T450 20BV0001US    | [3d1b8f282a](https://linux-hardware.org/?probe=3d1b8f282a) | Nov 27, 2022 |
| HP            | Laptop 15s-fq5xxx           | [f1ef96a2e6](https://linux-hardware.org/?probe=f1ef96a2e6) | Nov 26, 2022 |
| MSI           | Creator 15M A9SD            | [8b47bbf475](https://linux-hardware.org/?probe=8b47bbf475) | Nov 26, 2022 |
| HP            | Laptop 15-da3xxx            | [335fce26dd](https://linux-hardware.org/?probe=335fce26dd) | Nov 26, 2022 |
| HP            | 255 G7 Notebook PC          | [8c389cf5d6](https://linux-hardware.org/?probe=8c389cf5d6) | Nov 26, 2022 |
| HP            | Laptop 15s-du3xxx           | [2902b75068](https://linux-hardware.org/?probe=2902b75068) | Nov 26, 2022 |
| HP            | Laptop 15s-du3xxx           | [973662f8d5](https://linux-hardware.org/?probe=973662f8d5) | Nov 26, 2022 |
| Lenovo        | ThinkPad T495 20NJS0L100    | [1e9e7f34df](https://linux-hardware.org/?probe=1e9e7f34df) | Nov 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [bede773ce4](https://linux-hardware.org/?probe=bede773ce4) | Nov 26, 2022 |
| ASUSTek       | A6R                         | [68f38deab1](https://linux-hardware.org/?probe=68f38deab1) | Nov 26, 2022 |
| Dell          | Latitude E7240              | [634ebb2a88](https://linux-hardware.org/?probe=634ebb2a88) | Nov 25, 2022 |
| HP            | Pavilion TS Sleekbook 14    | [26440cddbb](https://linux-hardware.org/?probe=26440cddbb) | Nov 25, 2022 |
| MSI           | Creator 15M A9SD            | [a15ef33296](https://linux-hardware.org/?probe=a15ef33296) | Nov 25, 2022 |
| Lenovo        | ThinkPad E14 20RBS3LE00     | [83203a04f2](https://linux-hardware.org/?probe=83203a04f2) | Nov 25, 2022 |
| ASUSTek       | GL752VW                     | [2dfd7f3926](https://linux-hardware.org/?probe=2dfd7f3926) | Nov 25, 2022 |
| Lenovo        | ThinkPad E470 20H2S00700    | [f82ee02c50](https://linux-hardware.org/?probe=f82ee02c50) | Nov 25, 2022 |
| Fujitsu       | LIFEBOOK E756               | [9e69bdbaff](https://linux-hardware.org/?probe=9e69bdbaff) | Nov 25, 2022 |
| Fujitsu       | LIFEBOOK E756               | [16acde36ab](https://linux-hardware.org/?probe=16acde36ab) | Nov 25, 2022 |
| HP            | 255 G7 Notebook PC          | [f5a6bcf0fb](https://linux-hardware.org/?probe=f5a6bcf0fb) | Nov 24, 2022 |
| ASUSTek       | X551CAP                     | [f40e3110d0](https://linux-hardware.org/?probe=f40e3110d0) | Nov 24, 2022 |
| Dell          | Latitude 5310               | [8b4ad51670](https://linux-hardware.org/?probe=8b4ad51670) | Nov 24, 2022 |
| Dell          | Latitude 5310               | [a5265c8a0e](https://linux-hardware.org/?probe=a5265c8a0e) | Nov 24, 2022 |
| Dell          | Latitude E6500              | [73d607f9e1](https://linux-hardware.org/?probe=73d607f9e1) | Nov 24, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [299634697d](https://linux-hardware.org/?probe=299634697d) | Nov 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [ef378a135b](https://linux-hardware.org/?probe=ef378a135b) | Nov 24, 2022 |
| Aquarius      | NS585                       | [d54530cbcb](https://linux-hardware.org/?probe=d54530cbcb) | Nov 24, 2022 |
| Aquarius      | NS585                       | [64d9bcbcde](https://linux-hardware.org/?probe=64d9bcbcde) | Nov 24, 2022 |
| Apple         | MacBookAir6,2               | [1f43ba0436](https://linux-hardware.org/?probe=1f43ba0436) | Nov 24, 2022 |
| MSI           | Modern 14 A10M              | [0545f4e38b](https://linux-hardware.org/?probe=0545f4e38b) | Nov 23, 2022 |
| Lenovo        | ThinkPad T495 20NK000UUS    | [0e8c0e6f07](https://linux-hardware.org/?probe=0e8c0e6f07) | Nov 23, 2022 |
| Lenovo        | ThinkPad T490 20N3S8T211    | [97ea649145](https://linux-hardware.org/?probe=97ea649145) | Nov 23, 2022 |
| HP            | ProBook 450 G7              | [52d46ed47e](https://linux-hardware.org/?probe=52d46ed47e) | Nov 23, 2022 |
| Dell          | Latitude E6530              | [71623eedf3](https://linux-hardware.org/?probe=71623eedf3) | Nov 23, 2022 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | [df91e2d404](https://linux-hardware.org/?probe=df91e2d404) | Nov 23, 2022 |
| MPMAN         | CONVERTER 102               | [cab847edc0](https://linux-hardware.org/?probe=cab847edc0) | Nov 23, 2022 |
| HP            | Compaq 6720s                | [63a0e0161c](https://linux-hardware.org/?probe=63a0e0161c) | Nov 22, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [363e0b0149](https://linux-hardware.org/?probe=363e0b0149) | Nov 22, 2022 |
| Unknown       | Unknown                     | [1de34b67e2](https://linux-hardware.org/?probe=1de34b67e2) | Nov 22, 2022 |
| Dell          | Latitude 3420               | [30434de3e9](https://linux-hardware.org/?probe=30434de3e9) | Nov 22, 2022 |
| Unknown       | Wiren Board rev. 7.3.1 (... | [1f9ccab914](https://linux-hardware.org/?probe=1f9ccab914) | Nov 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [0565ef1a0d](https://linux-hardware.org/?probe=0565ef1a0d) | Nov 22, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [71c464a407](https://linux-hardware.org/?probe=71c464a407) | Nov 22, 2022 |
| HP            | Pavilion Sleekbook 15       | [add4f71bc0](https://linux-hardware.org/?probe=add4f71bc0) | Nov 22, 2022 |
| HP            | ENVY 6                      | [feb348843e](https://linux-hardware.org/?probe=feb348843e) | Nov 22, 2022 |
| Lenovo        | Y520-15IKBA 80WY            | [c1cccb2b2a](https://linux-hardware.org/?probe=c1cccb2b2a) | Nov 22, 2022 |
| HP            | 255 G6 Notebook PC          | [149cee1720](https://linux-hardware.org/?probe=149cee1720) | Nov 22, 2022 |
| ASUSTek       | K53SD                       | [c127a0db71](https://linux-hardware.org/?probe=c127a0db71) | Nov 21, 2022 |
| Lenovo        | ThinkPad E14 20RAS04700     | [63d93d05db](https://linux-hardware.org/?probe=63d93d05db) | Nov 21, 2022 |
| MSI           | Creator 15M A9SD            | [e6d5440b09](https://linux-hardware.org/?probe=e6d5440b09) | Nov 21, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [b58bad1779](https://linux-hardware.org/?probe=b58bad1779) | Nov 21, 2022 |
| Dell          | Latitude 5310               | [9c19a3de68](https://linux-hardware.org/?probe=9c19a3de68) | Nov 21, 2022 |
| Micro Elec... | MG-VCTR002-2060             | [3ba115909e](https://linux-hardware.org/?probe=3ba115909e) | Nov 21, 2022 |
| HP            | Laptop 15-db0xxx            | [f634446cde](https://linux-hardware.org/?probe=f634446cde) | Nov 21, 2022 |
| Acer          | Popcorn                     | [6f446a097a](https://linux-hardware.org/?probe=6f446a097a) | Nov 20, 2022 |
| ASUSTek       | X550LB                      | [466592b744](https://linux-hardware.org/?probe=466592b744) | Nov 20, 2022 |
| ASUSTek       | X550LB                      | [3ca5ee2f7a](https://linux-hardware.org/?probe=3ca5ee2f7a) | Nov 20, 2022 |
| Chuwi         | LarkBook                    | [bef3087526](https://linux-hardware.org/?probe=bef3087526) | Nov 20, 2022 |
| MPMAN         | CONVERTER 102               | [845925720b](https://linux-hardware.org/?probe=845925720b) | Nov 20, 2022 |
| HP            | Laptop 15s-du3xxx           | [a90cea62ff](https://linux-hardware.org/?probe=a90cea62ff) | Nov 19, 2022 |
| Dell          | XPS 13 9380                 | [d42bddbd11](https://linux-hardware.org/?probe=d42bddbd11) | Nov 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [1af7bd26fd](https://linux-hardware.org/?probe=1af7bd26fd) | Nov 19, 2022 |
| Dell          | Inspiron 15-3567            | [5d6f9e57c5](https://linux-hardware.org/?probe=5d6f9e57c5) | Nov 19, 2022 |
| Tactus        | GeoBook 140                 | [127ec68044](https://linux-hardware.org/?probe=127ec68044) | Nov 19, 2022 |
| Aquarius      | NS585                       | [a0bc8d3f44](https://linux-hardware.org/?probe=a0bc8d3f44) | Nov 19, 2022 |
| Acer          | Aspire ES1-533              | [8c080caac2](https://linux-hardware.org/?probe=8c080caac2) | Nov 19, 2022 |
| Fujitsu       | FMVNQL7PM                   | [28ee68da79](https://linux-hardware.org/?probe=28ee68da79) | Nov 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [ad7abfb8cb](https://linux-hardware.org/?probe=ad7abfb8cb) | Nov 19, 2022 |
| Dell          | Latitude 7410               | [ce222880fe](https://linux-hardware.org/?probe=ce222880fe) | Nov 18, 2022 |
| Dynabook      | TECRA A50-J                 | [c0ae8746e0](https://linux-hardware.org/?probe=c0ae8746e0) | Nov 18, 2022 |
| HP            | 650                         | [43998a620b](https://linux-hardware.org/?probe=43998a620b) | Nov 18, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [0278a1f18d](https://linux-hardware.org/?probe=0278a1f18d) | Nov 18, 2022 |
| Apple         | MacBookAir7,2               | [f0fa194e20](https://linux-hardware.org/?probe=f0fa194e20) | Nov 18, 2022 |
| Google        | Terra                       | [9fcc3fb18a](https://linux-hardware.org/?probe=9fcc3fb18a) | Nov 18, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [3b33d1989a](https://linux-hardware.org/?probe=3b33d1989a) | Nov 18, 2022 |
| ASUSTek       | T100TA                      | [871be7733f](https://linux-hardware.org/?probe=871be7733f) | Nov 17, 2022 |
| MPMAN         | CONVERTER8                  | [0c8f7446f7](https://linux-hardware.org/?probe=0c8f7446f7) | Nov 17, 2022 |
| Dell          | Latitude 5310               | [8c9625dc17](https://linux-hardware.org/?probe=8c9625dc17) | Nov 17, 2022 |
| Dell          | Latitude 5310               | [958c48cd54](https://linux-hardware.org/?probe=958c48cd54) | Nov 17, 2022 |
| Lenovo        | B475 Sabine                 | [5be5a7cd5f](https://linux-hardware.org/?probe=5be5a7cd5f) | Nov 17, 2022 |
| HP            | EliteBook 745 G5            | [9d7fefd253](https://linux-hardware.org/?probe=9d7fefd253) | Nov 17, 2022 |
| MSI           | Creator 15M A9SD            | [f1fdc384f9](https://linux-hardware.org/?probe=f1fdc384f9) | Nov 17, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [814b5d3d2e](https://linux-hardware.org/?probe=814b5d3d2e) | Nov 17, 2022 |
| HP            | Laptop 15-db0xxx            | [5aa50e7f6c](https://linux-hardware.org/?probe=5aa50e7f6c) | Nov 17, 2022 |
| HP            | OMEN by Laptop 15-dh0xxx    | [523e8a1c6b](https://linux-hardware.org/?probe=523e8a1c6b) | Nov 17, 2022 |
| Dell          | Latitude 3320               | [fbaf8e5ab9](https://linux-hardware.org/?probe=fbaf8e5ab9) | Nov 16, 2022 |
| Dell          | Latitude 3320               | [377fbd3b41](https://linux-hardware.org/?probe=377fbd3b41) | Nov 16, 2022 |
| Dell          | Inspiron 13 5310            | [3c9865d86e](https://linux-hardware.org/?probe=3c9865d86e) | Nov 16, 2022 |
| HP            | Laptop 15-db0xxx            | [f6202bb6fa](https://linux-hardware.org/?probe=f6202bb6fa) | Nov 16, 2022 |
| MSI           | Prestige 14Evo A11M         | [78601d078c](https://linux-hardware.org/?probe=78601d078c) | Nov 16, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [8fe0bcfe69](https://linux-hardware.org/?probe=8fe0bcfe69) | Nov 16, 2022 |
| Lenovo        | IdeaPad Z470                | [bc0980a6df](https://linux-hardware.org/?probe=bc0980a6df) | Nov 16, 2022 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | [5ea39eac4c](https://linux-hardware.org/?probe=5ea39eac4c) | Nov 16, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [be72c5d9db](https://linux-hardware.org/?probe=be72c5d9db) | Nov 16, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | [c38c6ddff6](https://linux-hardware.org/?probe=c38c6ddff6) | Nov 16, 2022 |
| Lenovo        | G470 20078                  | [55f47f2c19](https://linux-hardware.org/?probe=55f47f2c19) | Nov 16, 2022 |
| Unknown       | Unknown                     | [a86465b0f3](https://linux-hardware.org/?probe=a86465b0f3) | Nov 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [b5eb364ac6](https://linux-hardware.org/?probe=b5eb364ac6) | Nov 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [f29e7d7659](https://linux-hardware.org/?probe=f29e7d7659) | Nov 16, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [2cc4a2cf6d](https://linux-hardware.org/?probe=2cc4a2cf6d) | Nov 16, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [867825d906](https://linux-hardware.org/?probe=867825d906) | Nov 15, 2022 |
| Dell          | Inspiron 5558               | [0674cb5916](https://linux-hardware.org/?probe=0674cb5916) | Nov 15, 2022 |
| GPU Compan... | GWTN116-3                   | [f8d8191f69](https://linux-hardware.org/?probe=f8d8191f69) | Nov 15, 2022 |
| ASUSTek       | X550VX                      | [8e55592803](https://linux-hardware.org/?probe=8e55592803) | Nov 15, 2022 |
| Dell          | G7 7700                     | [2440bebe2c](https://linux-hardware.org/?probe=2440bebe2c) | Nov 15, 2022 |
| IBM           | ThinkPad X31 2672JBU        | [ea0c82f4eb](https://linux-hardware.org/?probe=ea0c82f4eb) | Nov 15, 2022 |
| HP            | EliteBook 820 G3            | [fe84036164](https://linux-hardware.org/?probe=fe84036164) | Nov 15, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [862e9a2c25](https://linux-hardware.org/?probe=862e9a2c25) | Nov 15, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [a94cf56482](https://linux-hardware.org/?probe=a94cf56482) | Nov 15, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [ee5852d273](https://linux-hardware.org/?probe=ee5852d273) | Nov 15, 2022 |
| Acer          | Aspire A315-23G             | [16e5672a66](https://linux-hardware.org/?probe=16e5672a66) | Nov 15, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [1604955bcb](https://linux-hardware.org/?probe=1604955bcb) | Nov 15, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [100714ed23](https://linux-hardware.org/?probe=100714ed23) | Nov 14, 2022 |
| AXDIA Inte... | MYBOOK 14 PRO               | [8267ec6686](https://linux-hardware.org/?probe=8267ec6686) | Nov 14, 2022 |
| Lenovo        | V14-ADA 82C6                | [7971c5cda7](https://linux-hardware.org/?probe=7971c5cda7) | Nov 14, 2022 |
| Toshiba       | Satellite P50-B-10Q         | [f28064cdad](https://linux-hardware.org/?probe=f28064cdad) | Nov 14, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [233791ab06](https://linux-hardware.org/?probe=233791ab06) | Nov 14, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [c6e254c4ed](https://linux-hardware.org/?probe=c6e254c4ed) | Nov 14, 2022 |
| HP            | 530 Notebook PC(KD092AA#... | [b6c682238c](https://linux-hardware.org/?probe=b6c682238c) | Nov 13, 2022 |
| Chuwi         | LarkBook                    | [8c33c61e14](https://linux-hardware.org/?probe=8c33c61e14) | Nov 13, 2022 |
| HP            | Laptop 15s-eq2xxx           | [36df61fb32](https://linux-hardware.org/?probe=36df61fb32) | Nov 13, 2022 |
| Unknown       | Unknown                     | [344e5842d1](https://linux-hardware.org/?probe=344e5842d1) | Nov 13, 2022 |
| Dell          | Inspiron 3521               | [c644f80930](https://linux-hardware.org/?probe=c644f80930) | Nov 13, 2022 |
| MSI           | GF63 8RD                    | [0ca4cc20c5](https://linux-hardware.org/?probe=0ca4cc20c5) | Nov 13, 2022 |
| HP            | ENVY Laptop 17-ch1xxx       | [ff0881b6e4](https://linux-hardware.org/?probe=ff0881b6e4) | Nov 13, 2022 |
| HP            | 250 G8 Notebook PC          | [7e9c7562d6](https://linux-hardware.org/?probe=7e9c7562d6) | Nov 13, 2022 |
| HP            | EliteBook 8460p             | [8cb389e68e](https://linux-hardware.org/?probe=8cb389e68e) | Nov 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [1067cba3cc](https://linux-hardware.org/?probe=1067cba3cc) | Nov 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [6677ca6be8](https://linux-hardware.org/?probe=6677ca6be8) | Nov 12, 2022 |
| GPU Compan... | GWTC116-2                   | [978facebde](https://linux-hardware.org/?probe=978facebde) | Nov 12, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [904b7c0e89](https://linux-hardware.org/?probe=904b7c0e89) | Nov 12, 2022 |
| HP            | Notebook                    | [2419e7d149](https://linux-hardware.org/?probe=2419e7d149) | Nov 12, 2022 |
| HP            | Notebook                    | [97c6c3c412](https://linux-hardware.org/?probe=97c6c3c412) | Nov 12, 2022 |
| GPU Compan... | GWTC116-2                   | [9e0c2df66d](https://linux-hardware.org/?probe=9e0c2df66d) | Nov 12, 2022 |
| IBM           | ThinkPad X31 2672JBU        | [9f627ba3f8](https://linux-hardware.org/?probe=9f627ba3f8) | Nov 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [59aa7d31d8](https://linux-hardware.org/?probe=59aa7d31d8) | Nov 11, 2022 |
| HP            | ENVY Laptop 17-ch1xxx       | [22ab694d81](https://linux-hardware.org/?probe=22ab694d81) | Nov 11, 2022 |
| Lenovo        | ThinkPad W700 275236U       | [c79bbe36c5](https://linux-hardware.org/?probe=c79bbe36c5) | Nov 11, 2022 |
| NCA Group     | iRU_Notebook                | [6d22b3942e](https://linux-hardware.org/?probe=6d22b3942e) | Nov 11, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [1681f97433](https://linux-hardware.org/?probe=1681f97433) | Nov 11, 2022 |
| HP            | Spectre x2 Detachable       | [0c480bd74d](https://linux-hardware.org/?probe=0c480bd74d) | Nov 11, 2022 |
| ASUSTek       | K50IE                       | [4bd91fccfa](https://linux-hardware.org/?probe=4bd91fccfa) | Nov 11, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [139c944b07](https://linux-hardware.org/?probe=139c944b07) | Nov 11, 2022 |
| Positivo B... | VJFE53F11X-XXXXXX           | [7e81c7cf85](https://linux-hardware.org/?probe=7e81c7cf85) | Nov 10, 2022 |
| HP            | ENVY 17 Leap Motion SE N... | [ae40e6e5b3](https://linux-hardware.org/?probe=ae40e6e5b3) | Nov 10, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [f8cd836199](https://linux-hardware.org/?probe=f8cd836199) | Nov 10, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [8bb3389cc1](https://linux-hardware.org/?probe=8bb3389cc1) | Nov 10, 2022 |
| Lenovo        | ThinkPad T14s Gen 3 21BS... | [24c5edc9f9](https://linux-hardware.org/?probe=24c5edc9f9) | Nov 10, 2022 |
| Lenovo        | G50-30 80G0                 | [1e0c308a85](https://linux-hardware.org/?probe=1e0c308a85) | Nov 10, 2022 |
| ASUSTek       | X550VXK                     | [f752e7959c](https://linux-hardware.org/?probe=f752e7959c) | Nov 10, 2022 |
| ASUSTek       | K50IE                       | [5176f404f1](https://linux-hardware.org/?probe=5176f404f1) | Nov 10, 2022 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [9a69ea4724](https://linux-hardware.org/?probe=9a69ea4724) | Nov 10, 2022 |
| Dell          | Latitude E6530              | [f71e1a930c](https://linux-hardware.org/?probe=f71e1a930c) | Nov 10, 2022 |
| HP            | Pavilion g7                 | [ae04263783](https://linux-hardware.org/?probe=ae04263783) | Nov 09, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [9d27997bce](https://linux-hardware.org/?probe=9d27997bce) | Nov 09, 2022 |
| ASUSTek       | UX31A                       | [e9bc780ce8](https://linux-hardware.org/?probe=e9bc780ce8) | Nov 09, 2022 |
| Gigabyte      | Sabre 15                    | [1edede0895](https://linux-hardware.org/?probe=1edede0895) | Nov 09, 2022 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | [098d4ab9ec](https://linux-hardware.org/?probe=098d4ab9ec) | Nov 09, 2022 |
| Lenovo        | ThinkPad T420 4180PEM       | [ad4d7f338d](https://linux-hardware.org/?probe=ad4d7f338d) | Nov 09, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [52080bf6ef](https://linux-hardware.org/?probe=52080bf6ef) | Nov 09, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [6b1f5f2c2a](https://linux-hardware.org/?probe=6b1f5f2c2a) | Nov 08, 2022 |
| HP            | Pavilion g7                 | [47c2e96181](https://linux-hardware.org/?probe=47c2e96181) | Nov 08, 2022 |
| Aquarius      | NS585                       | [9b20fcc4b8](https://linux-hardware.org/?probe=9b20fcc4b8) | Nov 08, 2022 |
| Razer         | Blade 15 Advanced Model ... | [0596fa3f71](https://linux-hardware.org/?probe=0596fa3f71) | Nov 08, 2022 |
| Dell          | Latitude E7470              | [3938dbeadd](https://linux-hardware.org/?probe=3938dbeadd) | Nov 08, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [da41b87b7c](https://linux-hardware.org/?probe=da41b87b7c) | Nov 07, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [f3c625be2d](https://linux-hardware.org/?probe=f3c625be2d) | Nov 07, 2022 |
| Unknown       | Unknown                     | [6af513692f](https://linux-hardware.org/?probe=6af513692f) | Nov 07, 2022 |
| Unknown       | Unknown                     | [b4859caaba](https://linux-hardware.org/?probe=b4859caaba) | Nov 07, 2022 |
| Lenovo        | G50-70 20351                | [0d4536a010](https://linux-hardware.org/?probe=0d4536a010) | Nov 07, 2022 |
| Lenovo        | ThinkPad W700 275236U       | [d3580b26c6](https://linux-hardware.org/?probe=d3580b26c6) | Nov 06, 2022 |
| HP            | Laptop 15-db0xxx            | [32b59c7a7d](https://linux-hardware.org/?probe=32b59c7a7d) | Nov 06, 2022 |
| HP            | Laptop 15-db0xxx            | [f0c8aff40f](https://linux-hardware.org/?probe=f0c8aff40f) | Nov 06, 2022 |
| Dell          | Latitude E6520              | [9593951427](https://linux-hardware.org/?probe=9593951427) | Nov 06, 2022 |
| Samsung       | 300E4A/300E5A/300E7A        | [e872e8551e](https://linux-hardware.org/?probe=e872e8551e) | Nov 06, 2022 |
| Dell          | Latitude E6520              | [53eedbde1f](https://linux-hardware.org/?probe=53eedbde1f) | Nov 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X531... | [55d115647e](https://linux-hardware.org/?probe=55d115647e) | Nov 06, 2022 |
| ASUSTek       | GL752VW                     | [cc373f85e7](https://linux-hardware.org/?probe=cc373f85e7) | Nov 06, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [47dda70950](https://linux-hardware.org/?probe=47dda70950) | Nov 06, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [5a2028bd2d](https://linux-hardware.org/?probe=5a2028bd2d) | Nov 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [3ec96d66bb](https://linux-hardware.org/?probe=3ec96d66bb) | Nov 05, 2022 |
| Acer          | Aspire 5741G                | [10c1cb72e2](https://linux-hardware.org/?probe=10c1cb72e2) | Nov 05, 2022 |
| Acer          | Aspire V3-572G              | [77f939bab4](https://linux-hardware.org/?probe=77f939bab4) | Nov 05, 2022 |
| ASUSTek       | X756UWK                     | [2d165dd7b0](https://linux-hardware.org/?probe=2d165dd7b0) | Nov 05, 2022 |
| Lenovo        | ThinkPad L380 20M50013MH    | [80ac51627a](https://linux-hardware.org/?probe=80ac51627a) | Nov 05, 2022 |
| ASUSTek       | X756UWK                     | [b89c7882f3](https://linux-hardware.org/?probe=b89c7882f3) | Nov 05, 2022 |
| Dell          | Inspiron 7570               | [158f7b0bcd](https://linux-hardware.org/?probe=158f7b0bcd) | Nov 05, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [605e06c6ad](https://linux-hardware.org/?probe=605e06c6ad) | Nov 04, 2022 |
| ASUSTek       | K53SD                       | [809577d2bb](https://linux-hardware.org/?probe=809577d2bb) | Nov 04, 2022 |
| Google        | Terra                       | [90518f31df](https://linux-hardware.org/?probe=90518f31df) | Nov 04, 2022 |
| Google        | Terra                       | [46ffa8092b](https://linux-hardware.org/?probe=46ffa8092b) | Nov 04, 2022 |
| Google        | Terra                       | [fc3f4b0ba5](https://linux-hardware.org/?probe=fc3f4b0ba5) | Nov 04, 2022 |
| Google        | Terra                       | [41017e02e4](https://linux-hardware.org/?probe=41017e02e4) | Nov 04, 2022 |
| Google        | Terra                       | [7429a311e4](https://linux-hardware.org/?probe=7429a311e4) | Nov 04, 2022 |
| SK hynix      | HyBook                      | [e758cde5ed](https://linux-hardware.org/?probe=e758cde5ed) | Nov 04, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [f0be03da28](https://linux-hardware.org/?probe=f0be03da28) | Nov 04, 2022 |
| Juana Mans... | SF20GM7                     | [8e8c4f52f4](https://linux-hardware.org/?probe=8e8c4f52f4) | Nov 04, 2022 |
| HP            | ProBook 6450b               | [7e595214cb](https://linux-hardware.org/?probe=7e595214cb) | Nov 04, 2022 |
| Acer          | Nitro AN515-55              | [a1cef4e43d](https://linux-hardware.org/?probe=a1cef4e43d) | Nov 04, 2022 |
| Acer          | Nitro AN515-55              | [b58a40d876](https://linux-hardware.org/?probe=b58a40d876) | Nov 04, 2022 |
| Samsung       | 300E4A/300E5A/300E7A        | [391881cdd5](https://linux-hardware.org/?probe=391881cdd5) | Nov 03, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [67e9f8d2f4](https://linux-hardware.org/?probe=67e9f8d2f4) | Nov 03, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [ecf54fa708](https://linux-hardware.org/?probe=ecf54fa708) | Nov 03, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [8681693f03](https://linux-hardware.org/?probe=8681693f03) | Nov 03, 2022 |
| HP            | EliteBook 745 G6            | [d4d0f735d4](https://linux-hardware.org/?probe=d4d0f735d4) | Nov 03, 2022 |
| HP            | EliteBook 745 G6            | [04e15fb2d7](https://linux-hardware.org/?probe=04e15fb2d7) | Nov 03, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [c80c7a9048](https://linux-hardware.org/?probe=c80c7a9048) | Nov 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [455bdc6c45](https://linux-hardware.org/?probe=455bdc6c45) | Nov 03, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [e507b9a974](https://linux-hardware.org/?probe=e507b9a974) | Nov 03, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [7a5f1eaf6c](https://linux-hardware.org/?probe=7a5f1eaf6c) | Nov 03, 2022 |
| SAGER         | D900F                       | [7e0d0de36a](https://linux-hardware.org/?probe=7e0d0de36a) | Nov 03, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [cecc0cca9d](https://linux-hardware.org/?probe=cecc0cca9d) | Nov 03, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [464cc2acc3](https://linux-hardware.org/?probe=464cc2acc3) | Nov 03, 2022 |
| Lenovo        | ThinkPad T430 23501B6       | [f059837f31](https://linux-hardware.org/?probe=f059837f31) | Nov 03, 2022 |
| Dell          | Latitude 5420               | [717e0e6d40](https://linux-hardware.org/?probe=717e0e6d40) | Nov 03, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [d59bd1e8f1](https://linux-hardware.org/?probe=d59bd1e8f1) | Nov 02, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [4342ecb0f9](https://linux-hardware.org/?probe=4342ecb0f9) | Nov 02, 2022 |
| Google        | Terra                       | [46299bf228](https://linux-hardware.org/?probe=46299bf228) | Nov 02, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [fd32769391](https://linux-hardware.org/?probe=fd32769391) | Nov 02, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [d3c1c92563](https://linux-hardware.org/?probe=d3c1c92563) | Nov 02, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [0ffaee423b](https://linux-hardware.org/?probe=0ffaee423b) | Nov 02, 2022 |
| ASUSTek       | 1005HA                      | [1d386943d6](https://linux-hardware.org/?probe=1d386943d6) | Nov 02, 2022 |
| HP            | G42                         | [18c487d99d](https://linux-hardware.org/?probe=18c487d99d) | Nov 02, 2022 |
| Digma         | EVE 11 C422 ES1068EW        | [f5177de131](https://linux-hardware.org/?probe=f5177de131) | Nov 02, 2022 |
| Toshiba       | Satellite L755              | [dc3d60731e](https://linux-hardware.org/?probe=dc3d60731e) | Nov 01, 2022 |
| Acer          | Aspire one                  | [bfb9f97d74](https://linux-hardware.org/?probe=bfb9f97d74) | Oct 31, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [c9e0b81f80](https://linux-hardware.org/?probe=c9e0b81f80) | Oct 31, 2022 |
| HP            | Compaq nc6320 (EV073AV)     | [b73f359ded](https://linux-hardware.org/?probe=b73f359ded) | Oct 31, 2022 |
| ASUSTek       | G75VW                       | [6f1d41a85c](https://linux-hardware.org/?probe=6f1d41a85c) | Oct 31, 2022 |
| Acer          | Aspire one                  | [82b34552f6](https://linux-hardware.org/?probe=82b34552f6) | Oct 31, 2022 |
| MSI           | Pulse GL76 12UEK            | [76a2d8c304](https://linux-hardware.org/?probe=76a2d8c304) | Oct 31, 2022 |
| ASUSTek       | ZenBook UX431FAC_UX431FA    | [95554a578b](https://linux-hardware.org/?probe=95554a578b) | Oct 31, 2022 |
| Aquarius      | NS585                       | [e4b4e0456d](https://linux-hardware.org/?probe=e4b4e0456d) | Oct 31, 2022 |
| Apple         | MacBookPro5,5               | [00e1f1f754](https://linux-hardware.org/?probe=00e1f1f754) | Oct 31, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [a872c9888a](https://linux-hardware.org/?probe=a872c9888a) | Oct 30, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [45f670d99f](https://linux-hardware.org/?probe=45f670d99f) | Oct 30, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | [209fa66bb9](https://linux-hardware.org/?probe=209fa66bb9) | Oct 30, 2022 |
| Acer          | Aspire A515-51G             | [12380f78de](https://linux-hardware.org/?probe=12380f78de) | Oct 30, 2022 |
| HP            | x2 210                      | [8ed0a97ee9](https://linux-hardware.org/?probe=8ed0a97ee9) | Oct 30, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | [e8a1f8f6bf](https://linux-hardware.org/?probe=e8a1f8f6bf) | Oct 30, 2022 |
| Dell          | XPS L322X                   | [cacebfe41e](https://linux-hardware.org/?probe=cacebfe41e) | Oct 30, 2022 |
| ASUSTek       | N751JK                      | [eea92055f3](https://linux-hardware.org/?probe=eea92055f3) | Oct 30, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | [89595b2fa9](https://linux-hardware.org/?probe=89595b2fa9) | Oct 30, 2022 |
| Chuwi         | LarkBook                    | [3ff2ff69ce](https://linux-hardware.org/?probe=3ff2ff69ce) | Oct 30, 2022 |
| Dell          | Latitude 5501               | [67f979a26d](https://linux-hardware.org/?probe=67f979a26d) | Oct 29, 2022 |
| Notebook      | W230SD                      | [76ae019222](https://linux-hardware.org/?probe=76ae019222) | Oct 29, 2022 |
| Dell          | Precision 7520              | [f54f6d6354](https://linux-hardware.org/?probe=f54f6d6354) | Oct 29, 2022 |
| Dell          | Latitude 5590               | [c7fa986fbd](https://linux-hardware.org/?probe=c7fa986fbd) | Oct 29, 2022 |
| ASUSTek       | X75VC                       | [9c1ab509ec](https://linux-hardware.org/?probe=9c1ab509ec) | Oct 29, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [8cc0e0d828](https://linux-hardware.org/?probe=8cc0e0d828) | Oct 29, 2022 |
| Dell          | Latitude E4310              | [fe6c65dd77](https://linux-hardware.org/?probe=fe6c65dd77) | Oct 29, 2022 |
| Insyde        | Braswell                    | [d98b2d9661](https://linux-hardware.org/?probe=d98b2d9661) | Oct 29, 2022 |
| Samsung       | 300V3A/300V4A/300V5A        | [4acb2d0863](https://linux-hardware.org/?probe=4acb2d0863) | Oct 29, 2022 |
| Dell          | Latitude E4310              | [7a610ca46d](https://linux-hardware.org/?probe=7a610ca46d) | Oct 29, 2022 |
| Dell          | XPS 17 9720                 | [270b988521](https://linux-hardware.org/?probe=270b988521) | Oct 29, 2022 |
| Dell          | Precision 7520              | [30f6ad7a26](https://linux-hardware.org/?probe=30f6ad7a26) | Oct 29, 2022 |
| Dell          | Precision 7520              | [b81923dbd2](https://linux-hardware.org/?probe=b81923dbd2) | Oct 29, 2022 |
| MSI           | Modern 15 A10RBS            | [ddc3eded89](https://linux-hardware.org/?probe=ddc3eded89) | Oct 28, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [60d1db050b](https://linux-hardware.org/?probe=60d1db050b) | Oct 28, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [2a9f06c2b4](https://linux-hardware.org/?probe=2a9f06c2b4) | Oct 28, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [787904d265](https://linux-hardware.org/?probe=787904d265) | Oct 28, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [0971db18ed](https://linux-hardware.org/?probe=0971db18ed) | Oct 28, 2022 |
| Toshiba       | Satellite L755              | [0fa70f29d4](https://linux-hardware.org/?probe=0fa70f29d4) | Oct 28, 2022 |
| Lenovo        | ThinkPad T530 239242U       | [dbf70338e9](https://linux-hardware.org/?probe=dbf70338e9) | Oct 28, 2022 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | [e34c4fde2c](https://linux-hardware.org/?probe=e34c4fde2c) | Oct 28, 2022 |
| Dell          | Latitude 5280               | [368f237efe](https://linux-hardware.org/?probe=368f237efe) | Oct 28, 2022 |
| Dell          | XPS 17 9700                 | [81121b7762](https://linux-hardware.org/?probe=81121b7762) | Oct 28, 2022 |
| Toshiba       | Satellite C650D             | [0696abd43c](https://linux-hardware.org/?probe=0696abd43c) | Oct 28, 2022 |
| Toshiba       | Satellite C650D             | [d42867d201](https://linux-hardware.org/?probe=d42867d201) | Oct 28, 2022 |
| ASUSTek       | X555QG                      | [bace747804](https://linux-hardware.org/?probe=bace747804) | Oct 28, 2022 |
| Acer          | Aspire A715-75G             | [78b0c55e62](https://linux-hardware.org/?probe=78b0c55e62) | Oct 28, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [02c6d1fe1a](https://linux-hardware.org/?probe=02c6d1fe1a) | Oct 28, 2022 |
| Lenovo        | ThinkPad E470 20H2S00700    | [768c6c8357](https://linux-hardware.org/?probe=768c6c8357) | Oct 28, 2022 |
| SANTECH       | NHx0DB,DE                   | [db8c0489f4](https://linux-hardware.org/?probe=db8c0489f4) | Oct 28, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [63565608d1](https://linux-hardware.org/?probe=63565608d1) | Oct 28, 2022 |
| Google        | Boten                       | [2ed6baabf0](https://linux-hardware.org/?probe=2ed6baabf0) | Oct 27, 2022 |
| ASUSTek       | N501VW                      | [07f7d43f09](https://linux-hardware.org/?probe=07f7d43f09) | Oct 27, 2022 |
| HP            | ZBook 15 G3                 | [2b886c255e](https://linux-hardware.org/?probe=2b886c255e) | Oct 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [24da197a3a](https://linux-hardware.org/?probe=24da197a3a) | Oct 27, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [3ab1fbc8e8](https://linux-hardware.org/?probe=3ab1fbc8e8) | Oct 27, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [faafe16cfb](https://linux-hardware.org/?probe=faafe16cfb) | Oct 27, 2022 |
| Acer          | Aspire A515-45              | [3a09f9ee6b](https://linux-hardware.org/?probe=3a09f9ee6b) | Oct 27, 2022 |
| THTF          | CR F860-T1                  | [0e20f4f61a](https://linux-hardware.org/?probe=0e20f4f61a) | Oct 27, 2022 |
| Acer          | Aspire ES1-131              | [f0edf4897a](https://linux-hardware.org/?probe=f0edf4897a) | Oct 26, 2022 |
| ASUSTek       | X541UAK                     | [87ee863ba2](https://linux-hardware.org/?probe=87ee863ba2) | Oct 26, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [bfd570bbef](https://linux-hardware.org/?probe=bfd570bbef) | Oct 26, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [58820ca517](https://linux-hardware.org/?probe=58820ca517) | Oct 26, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [6b9a3ab27e](https://linux-hardware.org/?probe=6b9a3ab27e) | Oct 26, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [a5bd8bebc7](https://linux-hardware.org/?probe=a5bd8bebc7) | Oct 26, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [bce3a8b1b3](https://linux-hardware.org/?probe=bce3a8b1b3) | Oct 26, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [65a1d5242f](https://linux-hardware.org/?probe=65a1d5242f) | Oct 26, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [a09e3f3669](https://linux-hardware.org/?probe=a09e3f3669) | Oct 26, 2022 |
| ASUSTek       | 1005HA                      | [118fed891f](https://linux-hardware.org/?probe=118fed891f) | Oct 26, 2022 |
| HP            | Pavilion g6                 | [353259fad4](https://linux-hardware.org/?probe=353259fad4) | Oct 26, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [93b8dd8c3e](https://linux-hardware.org/?probe=93b8dd8c3e) | Oct 25, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [5e08852d18](https://linux-hardware.org/?probe=5e08852d18) | Oct 25, 2022 |
| Lenovo        | Z50-70 20354                | [08b673e57b](https://linux-hardware.org/?probe=08b673e57b) | Oct 25, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [438afb4185](https://linux-hardware.org/?probe=438afb4185) | Oct 25, 2022 |
| Lenovo        | Yoga 900S-12ISK 80ML        | [0c13fbf129](https://linux-hardware.org/?probe=0c13fbf129) | Oct 25, 2022 |
| Toshiba       | dynabook MX/33KBL           | [7ee9057da2](https://linux-hardware.org/?probe=7ee9057da2) | Oct 25, 2022 |
| Dell          | Vostro 5490                 | [6b4c7d3c8b](https://linux-hardware.org/?probe=6b4c7d3c8b) | Oct 24, 2022 |
| Dell          | Latitude E6430              | [3fbd9c277d](https://linux-hardware.org/?probe=3fbd9c277d) | Oct 24, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | [eae727e6a0](https://linux-hardware.org/?probe=eae727e6a0) | Oct 24, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [52701ec9f4](https://linux-hardware.org/?probe=52701ec9f4) | Oct 24, 2022 |
| Packard Be... | DOT S                       | [f280a6ccbc](https://linux-hardware.org/?probe=f280a6ccbc) | Oct 24, 2022 |
| Lenovo        | ThinkPad T470 20HES4VB00    | [f7b39d371a](https://linux-hardware.org/?probe=f7b39d371a) | Oct 24, 2022 |
| Packard Be... | H17HV                       | [2e94cfdd84](https://linux-hardware.org/?probe=2e94cfdd84) | Oct 24, 2022 |
| Alienware     | M11xR3                      | [62bf8b7b02](https://linux-hardware.org/?probe=62bf8b7b02) | Oct 24, 2022 |
| HP            | Pavilion g4                 | [3b6666b5ba](https://linux-hardware.org/?probe=3b6666b5ba) | Oct 24, 2022 |
| Lenovo        | V310-14IKB 80T2             | [73f18a6fbb](https://linux-hardware.org/?probe=73f18a6fbb) | Oct 24, 2022 |
| Dell          | Precision 7750              | [dd51bb7ccd](https://linux-hardware.org/?probe=dd51bb7ccd) | Oct 23, 2022 |
| HP            | Pavilion g4                 | [487a972bda](https://linux-hardware.org/?probe=487a972bda) | Oct 23, 2022 |
| Panasonic     | CF-LX3J-50M3                | [949acb4c3a](https://linux-hardware.org/?probe=949acb4c3a) | Oct 22, 2022 |
| HP            | Pavilion TS 11              | [6437fb22e1](https://linux-hardware.org/?probe=6437fb22e1) | Oct 22, 2022 |
| HP            | Pavilion TS 11              | [a19b5987c6](https://linux-hardware.org/?probe=a19b5987c6) | Oct 22, 2022 |
| Dell          | Latitude E6520              | [88af6c857c](https://linux-hardware.org/?probe=88af6c857c) | Oct 22, 2022 |
| Dell          | Latitude E6520              | [246517ceab](https://linux-hardware.org/?probe=246517ceab) | Oct 22, 2022 |
| ASUSTek       | X756UQK                     | [2570a4e51f](https://linux-hardware.org/?probe=2570a4e51f) | Oct 22, 2022 |
| Toshiba       | Satellite P50-B-103         | [011581fdbf](https://linux-hardware.org/?probe=011581fdbf) | Oct 21, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [45d7e6a1aa](https://linux-hardware.org/?probe=45d7e6a1aa) | Oct 21, 2022 |
| Apple         | MacBook5,2                  | [165ce75570](https://linux-hardware.org/?probe=165ce75570) | Oct 21, 2022 |
| MSI           | Prestige 14Evo A11M         | [c63a7ccdeb](https://linux-hardware.org/?probe=c63a7ccdeb) | Oct 21, 2022 |
| Acer          | Swift SF314-42              | [2449f6a1b7](https://linux-hardware.org/?probe=2449f6a1b7) | Oct 21, 2022 |
| Aquarius      | NS585                       | [c953c5090c](https://linux-hardware.org/?probe=c953c5090c) | Oct 21, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [1e4d67ad76](https://linux-hardware.org/?probe=1e4d67ad76) | Oct 21, 2022 |
| Lenovo        | V310-14IKB 80T2             | [8a0f6b66e6](https://linux-hardware.org/?probe=8a0f6b66e6) | Oct 21, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [1dc7719a4d](https://linux-hardware.org/?probe=1dc7719a4d) | Oct 21, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [7acb5493d7](https://linux-hardware.org/?probe=7acb5493d7) | Oct 21, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [b13dc58884](https://linux-hardware.org/?probe=b13dc58884) | Oct 20, 2022 |
| ASUSTek       | G75VW                       | [194959e65e](https://linux-hardware.org/?probe=194959e65e) | Oct 20, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [914bab2302](https://linux-hardware.org/?probe=914bab2302) | Oct 20, 2022 |
| HP            | EliteBook 745 G3            | [3bfbc8dcac](https://linux-hardware.org/?probe=3bfbc8dcac) | Oct 20, 2022 |
| HP            | Laptop 15-ef2xxx            | [823d998220](https://linux-hardware.org/?probe=823d998220) | Oct 20, 2022 |
| HP            | EliteBook 840 Aero G8 No... | [80738ede80](https://linux-hardware.org/?probe=80738ede80) | Oct 20, 2022 |
| Apple         | MacBook5,2                  | [1e76467975](https://linux-hardware.org/?probe=1e76467975) | Oct 20, 2022 |
| Aquarius      | NS585                       | [a134ed693c](https://linux-hardware.org/?probe=a134ed693c) | Oct 20, 2022 |
| HP            | ENVY Laptop 17-ch1xxx       | [162e7a20b2](https://linux-hardware.org/?probe=162e7a20b2) | Oct 20, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [35d4f4cf0e](https://linux-hardware.org/?probe=35d4f4cf0e) | Oct 20, 2022 |
| HP            | 245 G7                      | [9ec088c343](https://linux-hardware.org/?probe=9ec088c343) | Oct 19, 2022 |
| ASUSTek       | X541NA                      | [5b61fd3a38](https://linux-hardware.org/?probe=5b61fd3a38) | Oct 19, 2022 |
| Dell          | Inspiron 7590               | [43ec5b2df8](https://linux-hardware.org/?probe=43ec5b2df8) | Oct 19, 2022 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | [67ebd92594](https://linux-hardware.org/?probe=67ebd92594) | Oct 19, 2022 |
| Acer          | Aspire A315-23G             | [93584b3b67](https://linux-hardware.org/?probe=93584b3b67) | Oct 19, 2022 |
| Fujitsu       | LIFEBOOK E753               | [1fbb05ae6b](https://linux-hardware.org/?probe=1fbb05ae6b) | Oct 18, 2022 |
| HP            | EliteBook 745 G3            | [e800d683ef](https://linux-hardware.org/?probe=e800d683ef) | Oct 18, 2022 |
| ASUSTek       | G75VW                       | [5ee12be257](https://linux-hardware.org/?probe=5ee12be257) | Oct 18, 2022 |
| UNOWHY        | Y13G010S4EI                 | [f7f13866aa](https://linux-hardware.org/?probe=f7f13866aa) | Oct 18, 2022 |
| Sony          | VPCEH3U1E                   | [aff8f19a59](https://linux-hardware.org/?probe=aff8f19a59) | Oct 18, 2022 |
| Sony          | VPCEH3U1E                   | [c33d20c223](https://linux-hardware.org/?probe=c33d20c223) | Oct 18, 2022 |
| Lenovo        | IdeaPad 5 Pro 16IAH7 82S... | [dfa3140411](https://linux-hardware.org/?probe=dfa3140411) | Oct 17, 2022 |
| Dell          | XPS 17 9700                 | [5368bd3ad6](https://linux-hardware.org/?probe=5368bd3ad6) | Oct 17, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [e076f9208c](https://linux-hardware.org/?probe=e076f9208c) | Oct 17, 2022 |
| ASUSTek       | G75VW                       | [10bcc184e7](https://linux-hardware.org/?probe=10bcc184e7) | Oct 17, 2022 |
| SLIMBOOK      | TITAN                       | [87177b2371](https://linux-hardware.org/?probe=87177b2371) | Oct 17, 2022 |
| ASUSTek       | UX21A                       | [1d7d76b463](https://linux-hardware.org/?probe=1d7d76b463) | Oct 16, 2022 |
| ASUSTek       | G75VW                       | [a88a291921](https://linux-hardware.org/?probe=a88a291921) | Oct 16, 2022 |
| Lenovo        | Legion Y545 81Q6            | [b6162e2c5e](https://linux-hardware.org/?probe=b6162e2c5e) | Oct 16, 2022 |
| Dell          | Inspiron 1545               | [d9928a4ee9](https://linux-hardware.org/?probe=d9928a4ee9) | Oct 16, 2022 |
| Dell          | Latitude 3320               | [300f16471f](https://linux-hardware.org/?probe=300f16471f) | Oct 16, 2022 |
| Dell          | Latitude 3320               | [e4645890b8](https://linux-hardware.org/?probe=e4645890b8) | Oct 16, 2022 |
| Dell          | Inspiron N5110              | [ae7d737ee5](https://linux-hardware.org/?probe=ae7d737ee5) | Oct 16, 2022 |
| Dell          | Inspiron N5110              | [5cbc449f36](https://linux-hardware.org/?probe=5cbc449f36) | Oct 16, 2022 |
| HP            | Laptop 15-ef2xxx            | [fb37bc6617](https://linux-hardware.org/?probe=fb37bc6617) | Oct 15, 2022 |
| HP            | EliteBook Folio 1040 G1     | [81df2d786a](https://linux-hardware.org/?probe=81df2d786a) | Oct 15, 2022 |
| Panasonic     | CF-LX3J-50M3                | [95386977de](https://linux-hardware.org/?probe=95386977de) | Oct 14, 2022 |
| Lenovo        | ThinkPad T14s Gen 3 21BS... | [766f4b2d1f](https://linux-hardware.org/?probe=766f4b2d1f) | Oct 14, 2022 |
| Lenovo        | ThinkPad T14s Gen 3 21BS... | [bf46cd0c9e](https://linux-hardware.org/?probe=bf46cd0c9e) | Oct 14, 2022 |
| Dell          | Vostro 15 5510              | [8cf96a6d0b](https://linux-hardware.org/?probe=8cf96a6d0b) | Oct 14, 2022 |
| Dell          | Vostro 15 5510              | [a68e7df338](https://linux-hardware.org/?probe=a68e7df338) | Oct 14, 2022 |
| Dell          | Latitude E6330              | [1b1f5a27f7](https://linux-hardware.org/?probe=1b1f5a27f7) | Oct 14, 2022 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [4e29271bab](https://linux-hardware.org/?probe=4e29271bab) | Oct 14, 2022 |
| Dell          | Inspiron 5502               | [41fb5ecf07](https://linux-hardware.org/?probe=41fb5ecf07) | Oct 14, 2022 |
| MSI           | MS-N014                     | [87e6e540be](https://linux-hardware.org/?probe=87e6e540be) | Oct 14, 2022 |
| Google        | Robo                        | [d070697e72](https://linux-hardware.org/?probe=d070697e72) | Oct 13, 2022 |
| Acer          | Swift SF314-57              | [a1b02901a1](https://linux-hardware.org/?probe=a1b02901a1) | Oct 13, 2022 |
| Acer          | Swift SF314-57              | [a0f4cd454d](https://linux-hardware.org/?probe=a0f4cd454d) | Oct 13, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [0ce5415fa5](https://linux-hardware.org/?probe=0ce5415fa5) | Oct 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [dfc5a5f754](https://linux-hardware.org/?probe=dfc5a5f754) | Oct 13, 2022 |
| Lenovo        | ThinkPad T530 23595JU       | [e560a29570](https://linux-hardware.org/?probe=e560a29570) | Oct 12, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [00d174fcf4](https://linux-hardware.org/?probe=00d174fcf4) | Oct 12, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [ccee0b66d9](https://linux-hardware.org/?probe=ccee0b66d9) | Oct 12, 2022 |
| MSI           | GE72 2QF                    | [22904f1270](https://linux-hardware.org/?probe=22904f1270) | Oct 12, 2022 |
| MSI           | GE72 2QF                    | [ecd8555f97](https://linux-hardware.org/?probe=ecd8555f97) | Oct 12, 2022 |
| Thomson       | N14C4WH64                   | [bfc16b9ded](https://linux-hardware.org/?probe=bfc16b9ded) | Oct 12, 2022 |
| ASUSTek       | E402MA                      | [807cf84523](https://linux-hardware.org/?probe=807cf84523) | Oct 11, 2022 |
| ASUSTek       | N53Jg                       | [0b4302ed6c](https://linux-hardware.org/?probe=0b4302ed6c) | Oct 11, 2022 |
| Apple         | MacBookAir7,2               | [8b4c66e10a](https://linux-hardware.org/?probe=8b4c66e10a) | Oct 11, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [04cb107be2](https://linux-hardware.org/?probe=04cb107be2) | Oct 11, 2022 |
| Dell          | Precision 7720              | [2252c7bd79](https://linux-hardware.org/?probe=2252c7bd79) | Oct 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [6ccdbecf19](https://linux-hardware.org/?probe=6ccdbecf19) | Oct 10, 2022 |
| Apple         | MacBook5,2                  | [4687cf8900](https://linux-hardware.org/?probe=4687cf8900) | Oct 10, 2022 |
| Toshiba       | Satellite A100              | [f280857c1c](https://linux-hardware.org/?probe=f280857c1c) | Oct 09, 2022 |
| Dell          | Inspiron 14 5420            | [d9f937a8c4](https://linux-hardware.org/?probe=d9f937a8c4) | Oct 09, 2022 |
| HP            | Pavilion TS 11              | [1a6ea38863](https://linux-hardware.org/?probe=1a6ea38863) | Oct 09, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [7785f0ebfb](https://linux-hardware.org/?probe=7785f0ebfb) | Oct 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [f15acdf9d4](https://linux-hardware.org/?probe=f15acdf9d4) | Oct 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [487fd1959f](https://linux-hardware.org/?probe=487fd1959f) | Oct 08, 2022 |
| MSI           | Prestige 14Evo A11M         | [68137e0e8d](https://linux-hardware.org/?probe=68137e0e8d) | Oct 07, 2022 |
| HP            | Pavilion dv7                | [4564037395](https://linux-hardware.org/?probe=4564037395) | Oct 07, 2022 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | [e6eac5c882](https://linux-hardware.org/?probe=e6eac5c882) | Oct 07, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | [b27c3b70a7](https://linux-hardware.org/?probe=b27c3b70a7) | Oct 07, 2022 |
| Google        | Setzer                      | [cdb57d7ddf](https://linux-hardware.org/?probe=cdb57d7ddf) | Oct 07, 2022 |
| Shanghai Z... | ZXE CRB                     | [479f3d24f2](https://linux-hardware.org/?probe=479f3d24f2) | Oct 06, 2022 |
| Shanghai Z... | ZXE CRB                     | [5bacb77f8b](https://linux-hardware.org/?probe=5bacb77f8b) | Oct 06, 2022 |
| HP            | EliteBook 8470p             | [1b09c0a820](https://linux-hardware.org/?probe=1b09c0a820) | Oct 06, 2022 |
| HP            | EliteBook 8470p             | [0fa7893206](https://linux-hardware.org/?probe=0fa7893206) | Oct 06, 2022 |
| Acer          | Predator PH315-53           | [0f3387ce35](https://linux-hardware.org/?probe=0f3387ce35) | Oct 06, 2022 |
| Toshiba       | Satellite L40               | [0f3e9273a6](https://linux-hardware.org/?probe=0f3e9273a6) | Oct 06, 2022 |
| Google        | Akemi                       | [5a165f46bc](https://linux-hardware.org/?probe=5a165f46bc) | Oct 05, 2022 |
| Dell          | Precision 3541              | [bfef2cb8a3](https://linux-hardware.org/?probe=bfef2cb8a3) | Oct 05, 2022 |
| HP            | EliteBook 8570p             | [3079a45a56](https://linux-hardware.org/?probe=3079a45a56) | Oct 05, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [96b4cda722](https://linux-hardware.org/?probe=96b4cda722) | Oct 05, 2022 |
| HP            | EliteBook 8460p             | [02d4090cce](https://linux-hardware.org/?probe=02d4090cce) | Oct 05, 2022 |
| HP            | EliteBook 8460p             | [4f037d4c3d](https://linux-hardware.org/?probe=4f037d4c3d) | Oct 05, 2022 |
| Toshiba       | NB505                       | [9de39780b5](https://linux-hardware.org/?probe=9de39780b5) | Oct 05, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [dea0d04059](https://linux-hardware.org/?probe=dea0d04059) | Oct 05, 2022 |
| Acer          | Aspire A315-23G             | [ab3508b938](https://linux-hardware.org/?probe=ab3508b938) | Oct 05, 2022 |
| Acer          | Aspire E1-571               | [602710e8d3](https://linux-hardware.org/?probe=602710e8d3) | Oct 04, 2022 |
| HP            | EliteBook 8460p             | [8b9d1152e4](https://linux-hardware.org/?probe=8b9d1152e4) | Oct 04, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [8631c6f717](https://linux-hardware.org/?probe=8631c6f717) | Oct 04, 2022 |
| MSI           | GF65 Thin 10SDR             | [1c2a3b90e2](https://linux-hardware.org/?probe=1c2a3b90e2) | Oct 04, 2022 |
| HP            | EliteBook 735 G6            | [c3f86b0e1a](https://linux-hardware.org/?probe=c3f86b0e1a) | Oct 04, 2022 |
| Dell          | Latitude E5430 non-vPro     | [33b42f3ed1](https://linux-hardware.org/?probe=33b42f3ed1) | Oct 04, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [5b2fac59ea](https://linux-hardware.org/?probe=5b2fac59ea) | Oct 04, 2022 |
| Shanghai Z... | ZXE CRB                     | [b981993409](https://linux-hardware.org/?probe=b981993409) | Oct 04, 2022 |
| Lenovo        | ThinkPad Twist 20C41A3      | [3da96ac399](https://linux-hardware.org/?probe=3da96ac399) | Oct 04, 2022 |
| Acer          | Aspire A315-56              | [e799907aba](https://linux-hardware.org/?probe=e799907aba) | Oct 04, 2022 |
| Dell          | Precision M4800             | [1099761dca](https://linux-hardware.org/?probe=1099761dca) | Oct 04, 2022 |
| ASUSTek       | PU403UA                     | [8bf4879487](https://linux-hardware.org/?probe=8bf4879487) | Oct 04, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [31fa8b62ff](https://linux-hardware.org/?probe=31fa8b62ff) | Oct 04, 2022 |
| UNOWHY        | Y13G010S4EI                 | [38f5b56e5d](https://linux-hardware.org/?probe=38f5b56e5d) | Oct 04, 2022 |
| Dell          | Inspiron 5590               | [ed3bf1e99b](https://linux-hardware.org/?probe=ed3bf1e99b) | Oct 04, 2022 |
| Lenovo        | ThinkPad T420 4236WS7       | [e42a5888c7](https://linux-hardware.org/?probe=e42a5888c7) | Oct 04, 2022 |
| Dell          | Latitude E7240              | [84ce32d994](https://linux-hardware.org/?probe=84ce32d994) | Oct 03, 2022 |
| Dell          | Latitude E5430 non-vPro     | [81ac41d8b9](https://linux-hardware.org/?probe=81ac41d8b9) | Oct 03, 2022 |
| Dell          | Latitude 2110               | [3fbbac2c8a](https://linux-hardware.org/?probe=3fbbac2c8a) | Oct 03, 2022 |
| ASUSTek       | 1225B                       | [9bb2d54ca7](https://linux-hardware.org/?probe=9bb2d54ca7) | Oct 03, 2022 |
| Lenovo        | ThinkPad E14 20RA001HRT     | [1427143cf0](https://linux-hardware.org/?probe=1427143cf0) | Oct 03, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [64f2393fde](https://linux-hardware.org/?probe=64f2393fde) | Oct 03, 2022 |
| Toshiba       | Satellite L855              | [66e22581f7](https://linux-hardware.org/?probe=66e22581f7) | Oct 03, 2022 |
| Dell          | Precision 3570              | [f4f047eecf](https://linux-hardware.org/?probe=f4f047eecf) | Oct 03, 2022 |
| Apple         | MacBookAir7,2               | [ae39aea3e9](https://linux-hardware.org/?probe=ae39aea3e9) | Oct 02, 2022 |
| Lenovo        | ThinkPad T460s 20F90060G... | [8d17d38142](https://linux-hardware.org/?probe=8d17d38142) | Oct 02, 2022 |
| ASUSTek       | X71Q                        | [830c8ab6d2](https://linux-hardware.org/?probe=830c8ab6d2) | Oct 02, 2022 |
| Dell          | Vostro 5320                 | [93a0c7d88f](https://linux-hardware.org/?probe=93a0c7d88f) | Oct 02, 2022 |
| Toshiba       | Satellite L45               | [79ff097329](https://linux-hardware.org/?probe=79ff097329) | Oct 02, 2022 |
| Acer          | Aspire A715-41G             | [1a473e9809](https://linux-hardware.org/?probe=1a473e9809) | Oct 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [9cd72ed352](https://linux-hardware.org/?probe=9cd72ed352) | Oct 01, 2022 |
| HP            | Pavilion TS 11              | [5bc67115db](https://linux-hardware.org/?probe=5bc67115db) | Oct 01, 2022 |
| HP            | Pavilion TS 11              | [4758af490a](https://linux-hardware.org/?probe=4758af490a) | Oct 01, 2022 |
| Lenovo        | ThinkPad T440s 20AQCTO1W... | [fbe1e53387](https://linux-hardware.org/?probe=fbe1e53387) | Oct 01, 2022 |
| Lenovo        | ThinkPad L380 20M5SSIN11    | [0cad79b1f7](https://linux-hardware.org/?probe=0cad79b1f7) | Sep 30, 2022 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | [786e0c1f5d](https://linux-hardware.org/?probe=786e0c1f5d) | Sep 30, 2022 |
| HP            | Pavilion Notebook           | [ee72cbd627](https://linux-hardware.org/?probe=ee72cbd627) | Sep 29, 2022 |
| HP            | Compaq nx6325 (EY344EA#A... | [8808f98c62](https://linux-hardware.org/?probe=8808f98c62) | Sep 29, 2022 |
| ASUSTek       | N53SV                       | [6652e85ddd](https://linux-hardware.org/?probe=6652e85ddd) | Sep 29, 2022 |
| HUAWEI        | KLVL-WXXW                   | [fd8b95bb3b](https://linux-hardware.org/?probe=fd8b95bb3b) | Sep 29, 2022 |
| Lenovo        | ThinkPad T460 20FMS43J0V    | [0453cd781f](https://linux-hardware.org/?probe=0453cd781f) | Sep 28, 2022 |
| HP            | 250 G7 Notebook PC          | [6ad96a2beb](https://linux-hardware.org/?probe=6ad96a2beb) | Sep 28, 2022 |
| Dell          | Vostro 15 5510              | [973307d03b](https://linux-hardware.org/?probe=973307d03b) | Sep 28, 2022 |
| Acer          | Aspire A315-23G             | [3eaaf54d1b](https://linux-hardware.org/?probe=3eaaf54d1b) | Sep 28, 2022 |
| Lenovo        | ThinkPad T420 4236WS7       | [ca9c7bf57b](https://linux-hardware.org/?probe=ca9c7bf57b) | Sep 28, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [fb2de59c3f](https://linux-hardware.org/?probe=fb2de59c3f) | Sep 27, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [70f86aa587](https://linux-hardware.org/?probe=70f86aa587) | Sep 27, 2022 |
| Fujitsu       | LIFEBOOK E752               | [f4e2b14498](https://linux-hardware.org/?probe=f4e2b14498) | Sep 26, 2022 |
| Lenovo        | G50-70 20351                | [77c0454f45](https://linux-hardware.org/?probe=77c0454f45) | Sep 26, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [4f58ff1174](https://linux-hardware.org/?probe=4f58ff1174) | Sep 26, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [df5fcf14f9](https://linux-hardware.org/?probe=df5fcf14f9) | Sep 26, 2022 |
| MSI           | Alpha 15 A4DEK              | [f3c74059d5](https://linux-hardware.org/?probe=f3c74059d5) | Sep 26, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [ac296ea23b](https://linux-hardware.org/?probe=ac296ea23b) | Sep 26, 2022 |
| HP            | 250 G8 Notebook PC          | [f4ea1372b7](https://linux-hardware.org/?probe=f4ea1372b7) | Sep 26, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [dc6d36a0eb](https://linux-hardware.org/?probe=dc6d36a0eb) | Sep 26, 2022 |
| HP            | 250 G8 Notebook PC          | [ae83bec6ad](https://linux-hardware.org/?probe=ae83bec6ad) | Sep 26, 2022 |
| MSI           | Alpha 15 A4DEK              | [d2e3e7736c](https://linux-hardware.org/?probe=d2e3e7736c) | Sep 26, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [6527be1bb2](https://linux-hardware.org/?probe=6527be1bb2) | Sep 26, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [56e06deea2](https://linux-hardware.org/?probe=56e06deea2) | Sep 26, 2022 |
| MSI           | GF63 8RD                    | [f6ef1dbd07](https://linux-hardware.org/?probe=f6ef1dbd07) | Sep 25, 2022 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | [2d7ce63bce](https://linux-hardware.org/?probe=2d7ce63bce) | Sep 25, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [f844479504](https://linux-hardware.org/?probe=f844479504) | Sep 25, 2022 |
| Dell          | Inspiron 15-3567            | [9ae6efbc0f](https://linux-hardware.org/?probe=9ae6efbc0f) | Sep 25, 2022 |
| HUAWEI        | RLEF-XX                     | [7bab2cbc57](https://linux-hardware.org/?probe=7bab2cbc57) | Sep 25, 2022 |
| MSI           | GF75 Thin 10SC              | [0bda368d15](https://linux-hardware.org/?probe=0bda368d15) | Sep 24, 2022 |
| Lenovo        | ThinkPad T420 4236WS7       | [23f425e425](https://linux-hardware.org/?probe=23f425e425) | Sep 24, 2022 |
| Dell          | Inspiron 14 5425            | [209be443ac](https://linux-hardware.org/?probe=209be443ac) | Sep 24, 2022 |
| Lenovo        | ThinkPad T420 4236WS7       | [f3527878e5](https://linux-hardware.org/?probe=f3527878e5) | Sep 24, 2022 |
| Unknown       | Apple MacBook Pro (14-in... | [89a019875a](https://linux-hardware.org/?probe=89a019875a) | Sep 24, 2022 |
| ASUSTek       | G501VW                      | [550d6e5438](https://linux-hardware.org/?probe=550d6e5438) | Sep 24, 2022 |
| Dell          | Latitude 3320               | [3296a12784](https://linux-hardware.org/?probe=3296a12784) | Sep 24, 2022 |
| Lenovo        | ThinkPad T530 23595JU       | [0adb7bc0b1](https://linux-hardware.org/?probe=0adb7bc0b1) | Sep 24, 2022 |
| VIT           | P2402                       | [0242b6bb07](https://linux-hardware.org/?probe=0242b6bb07) | Sep 24, 2022 |
| Samsung       | 550XBE/350XBE               | [dec88709ee](https://linux-hardware.org/?probe=dec88709ee) | Sep 23, 2022 |
| Google        | Robo                        | [4772493ae3](https://linux-hardware.org/?probe=4772493ae3) | Sep 23, 2022 |
| Samsung       | 550XBE/350XBE               | [e17fb419bd](https://linux-hardware.org/?probe=e17fb419bd) | Sep 23, 2022 |
| MECHREVO      | Jiaolong Series GM5ZG0O     | [077c05c78d](https://linux-hardware.org/?probe=077c05c78d) | Sep 23, 2022 |
| Acer          | Aspire ES1-732              | [d6ccc5301b](https://linux-hardware.org/?probe=d6ccc5301b) | Sep 23, 2022 |
| Dell          | XPS 15 9520                 | [1a7e610c32](https://linux-hardware.org/?probe=1a7e610c32) | Sep 23, 2022 |
| Lenovo        | ThinkPad T495 20NKS0PG00    | [f77dda559d](https://linux-hardware.org/?probe=f77dda559d) | Sep 23, 2022 |
| Lenovo        | ThinkPad T420 4236WS7       | [c9457ee571](https://linux-hardware.org/?probe=c9457ee571) | Sep 23, 2022 |
| Lenovo        | ThinkPad T420 4236WS7       | [412296c83f](https://linux-hardware.org/?probe=412296c83f) | Sep 22, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | [db6f733994](https://linux-hardware.org/?probe=db6f733994) | Sep 22, 2022 |
| Lenovo        | ThinkPad T420 4236WS7       | [21ba0d8f46](https://linux-hardware.org/?probe=21ba0d8f46) | Sep 22, 2022 |
| Lenovo        | ThinkPad X220 4291G26       | [33654dfbfa](https://linux-hardware.org/?probe=33654dfbfa) | Sep 22, 2022 |
| Lenovo        | ThinkPad T420 4236WS7       | [0c4627555a](https://linux-hardware.org/?probe=0c4627555a) | Sep 22, 2022 |
| Dell          | Inspiron 5537               | [7e3170527c](https://linux-hardware.org/?probe=7e3170527c) | Sep 22, 2022 |
| HP            | Notebook                    | [18b9221add](https://linux-hardware.org/?probe=18b9221add) | Sep 22, 2022 |
| Toshiba       | Satellite P745              | [963d04c729](https://linux-hardware.org/?probe=963d04c729) | Sep 22, 2022 |
| Dell          | Vostro 15 5510              | [630b3877c4](https://linux-hardware.org/?probe=630b3877c4) | Sep 22, 2022 |
| MSI           | GS60 2PE                    | [1aaaa99706](https://linux-hardware.org/?probe=1aaaa99706) | Sep 22, 2022 |
| HP            | Presario CQ57               | [322f46c499](https://linux-hardware.org/?probe=322f46c499) | Sep 22, 2022 |
| HP            | Stream Notebook PC 13       | [a5dff5d1f6](https://linux-hardware.org/?probe=a5dff5d1f6) | Sep 22, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [5e7597fb17](https://linux-hardware.org/?probe=5e7597fb17) | Sep 22, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen2... | [87a3d977b1](https://linux-hardware.org/?probe=87a3d977b1) | Sep 22, 2022 |
| Avell High... | B.ON                        | [95c7e35ef3](https://linux-hardware.org/?probe=95c7e35ef3) | Sep 22, 2022 |
| Lenovo        | G50-45 80E3                 | [41af175db4](https://linux-hardware.org/?probe=41af175db4) | Sep 21, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [080fdb990e](https://linux-hardware.org/?probe=080fdb990e) | Sep 21, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [69d5dcb9b7](https://linux-hardware.org/?probe=69d5dcb9b7) | Sep 21, 2022 |
| Avell High... | B.ON                        | [aaebcf57bb](https://linux-hardware.org/?probe=aaebcf57bb) | Sep 21, 2022 |
| Dell          | Latitude 7530               | [39b655888c](https://linux-hardware.org/?probe=39b655888c) | Sep 21, 2022 |
| Acer          | Aspire A515-45              | [6fb7c9c27a](https://linux-hardware.org/?probe=6fb7c9c27a) | Sep 21, 2022 |
| Dell          | Precision 7540              | [fb7472fe87](https://linux-hardware.org/?probe=fb7472fe87) | Sep 21, 2022 |
| Dell          | Inspiron MP061              | [8e6955cbf6](https://linux-hardware.org/?probe=8e6955cbf6) | Sep 21, 2022 |
| AXDIA Inte... | MYBOOK 14 PRO               | [0ada4a5b83](https://linux-hardware.org/?probe=0ada4a5b83) | Sep 20, 2022 |
| HP            | Folio 13                    | [eafa8204e9](https://linux-hardware.org/?probe=eafa8204e9) | Sep 20, 2022 |
| Lenovo        | ThinkPad T490 20N2001YUS    | [5861c90514](https://linux-hardware.org/?probe=5861c90514) | Sep 20, 2022 |
| HP            | EliteBook 840 14 inch G9... | [450a86c900](https://linux-hardware.org/?probe=450a86c900) | Sep 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [f03ae050eb](https://linux-hardware.org/?probe=f03ae050eb) | Sep 20, 2022 |
| Lenovo        | ThinkPad X260 20F5003EMB    | [302eacc4ff](https://linux-hardware.org/?probe=302eacc4ff) | Sep 20, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U30... | [317ff73ff5](https://linux-hardware.org/?probe=317ff73ff5) | Sep 20, 2022 |
| Chuwi         | CoreBook X                  | [4c963415cd](https://linux-hardware.org/?probe=4c963415cd) | Sep 20, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [ba7800b231](https://linux-hardware.org/?probe=ba7800b231) | Sep 20, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0fa5921ddf](https://linux-hardware.org/?probe=0fa5921ddf) | Sep 20, 2022 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [d14a12b8ca](https://linux-hardware.org/?probe=d14a12b8ca) | Sep 20, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [04252a0991](https://linux-hardware.org/?probe=04252a0991) | Sep 20, 2022 |
| Acer          | TravelMate P414-51          | [2ebd8f21d3](https://linux-hardware.org/?probe=2ebd8f21d3) | Sep 20, 2022 |
| Lenovo        | ThinkPad SL400 2743AQC      | [beb74c65cc](https://linux-hardware.org/?probe=beb74c65cc) | Sep 19, 2022 |
| MSI           | Prestige 14Evo A11M         | [4b412dd569](https://linux-hardware.org/?probe=4b412dd569) | Sep 19, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [b415f7be91](https://linux-hardware.org/?probe=b415f7be91) | Sep 19, 2022 |
| HUAWEI        | HN-WX9X                     | [4a7bdd8ed1](https://linux-hardware.org/?probe=4a7bdd8ed1) | Sep 19, 2022 |
| HP            | 15                          | [50f64276d5](https://linux-hardware.org/?probe=50f64276d5) | Sep 19, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [0f049ae5d6](https://linux-hardware.org/?probe=0f049ae5d6) | Sep 19, 2022 |
| HP            | 15                          | [d74a694eb8](https://linux-hardware.org/?probe=d74a694eb8) | Sep 19, 2022 |
| HP            | G42                         | [3f584eb1af](https://linux-hardware.org/?probe=3f584eb1af) | Sep 19, 2022 |
| HUAWEI        | HN-WX9X                     | [46e9732572](https://linux-hardware.org/?probe=46e9732572) | Sep 19, 2022 |
| Panasonic     | CF-53JAWZYDE                | [f8b1ca10d1](https://linux-hardware.org/?probe=f8b1ca10d1) | Sep 19, 2022 |
| Acer          | Aspire A315-23G             | [9e3edc5b61](https://linux-hardware.org/?probe=9e3edc5b61) | Sep 18, 2022 |
| Lenovo        | IdeaPad 720s-13ARR 81BR     | [fa45602fc5](https://linux-hardware.org/?probe=fa45602fc5) | Sep 18, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Debian/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Debian 11                       | 2779      | 63.16%  |
| Debian 10                       | 848       | 19.27%  |
| Debian Testing                  | 357       | 8.11%   |
| Debian 9                        | 146       | 3.32%   |
| Debian Unstable                 | 128       | 2.91%   |
| Debian                          | 99        | 2.25%   |
| Debian 11-updates               | 26        | 0.59%   |
| Debian 8                        | 10        | 0.23%   |
| Debian Sid                      | 3         | 0.07%   |
| Debian Testing/unstable         | 2         | 0.05%   |
| Debian Testing-proposed-updates | 1         | 0.02%   |
| Debian 99                       | 1         | 0.02%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Debian | 4279      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.10.0-8-amd64    | 583       | 12.05%  |
| 5.10.0-10-amd64   | 491       | 10.15%  |
| 5.10.0-9-amd64    | 171       | 3.53%   |
| 5.10.0-7-amd64    | 171       | 3.53%   |
| 5.10.0-18-amd64   | 171       | 3.53%   |
| 5.10.0-16-amd64   | 166       | 3.43%   |
| 5.10.0-19-amd64   | 159       | 3.29%   |
| 5.10.0-13-amd64   | 149       | 3.08%   |
| 5.10.0-20-amd64   | 135       | 2.79%   |
| 5.10.0-11-amd64   | 103       | 2.13%   |
| 4.19.0-9-amd64    | 85        | 1.76%   |
| 4.19.0-6-amd64    | 82        | 1.69%   |
| 5.10.0-14-amd64   | 80        | 1.65%   |
| 5.10.0-17-amd64   | 72        | 1.49%   |
| 4.19.0-13-amd64   | 69        | 1.43%   |
| 4.19.0-8-amd64    | 68        | 1.41%   |
| 4.19.0-16-amd64   | 52        | 1.07%   |
| 4.19.0-10-amd64   | 52        | 1.07%   |
| 5.15.0-2-amd64    | 51        | 1.05%   |
| 5.10.0-15-amd64   | 47        | 0.97%   |
| 4.19.0-12-amd64   | 47        | 0.97%   |
| 4.19.0-14-amd64   | 42        | 0.87%   |
| 5.10.0-6-amd64    | 41        | 0.85%   |
| 5.10.0-2-amd64    | 40        | 0.83%   |
| 5.10.0-12-amd64   | 40        | 0.83%   |
| 4.19.0-17-amd64   | 40        | 0.83%   |
| 4.9.0-8-amd64     | 39        | 0.81%   |
| 5.18.0-2-amd64    | 31        | 0.64%   |
| 5.10.0-3-amd64    | 31        | 0.64%   |
| 5.19.0-1-amd64    | 27        | 0.56%   |
| 6.0.0-6-amd64     | 26        | 0.54%   |
| 5.10.0-13-686-pae | 26        | 0.54%   |
| 5.4.0-4-amd64     | 25        | 0.52%   |
| 5.17.0-1-amd64    | 24        | 0.5%    |
| 5.18.0-4-amd64    | 23        | 0.48%   |
| 5.19.0-2-amd64    | 22        | 0.45%   |
| 5.16.0-6-amd64    | 22        | 0.45%   |
| 4.19.0-11-amd64   | 22        | 0.45%   |
| 5.7.0-1-amd64     | 21        | 0.43%   |
| 4.19.0-5-amd64    | 21        | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 2660      | 58.81%  |
| 4.19.0  | 651       | 14.39%  |
| 4.9.0   | 120       | 2.65%   |
| 6.0.0   | 111       | 2.45%   |
| 5.18.0  | 104       | 2.3%    |
| 5.15.0  | 91        | 2.01%   |
| 5.9.0   | 74        | 1.64%   |
| 5.16.0  | 66        | 1.46%   |
| 5.4.0   | 64        | 1.41%   |
| 5.19.0  | 64        | 1.41%   |
| 5.7.0   | 59        | 1.3%    |
| 5.8.0   | 56        | 1.24%   |
| 5.14.0  | 53        | 1.17%   |
| 5.6.0   | 45        | 0.99%   |
| 5.17.0  | 39        | 0.86%   |
| 5.3.0   | 19        | 0.42%   |
| 5.5.0   | 16        | 0.35%   |
| 6.1.0   | 15        | 0.33%   |
| 5.2.0   | 12        | 0.27%   |
| 4.18.0  | 12        | 0.27%   |
| 3.16.0  | 8         | 0.18%   |
| 5.12.0  | 6         | 0.13%   |
| 5.17.5  | 3         | 0.07%   |
| 5.13.19 | 3         | 0.07%   |
| 5.13.0  | 3         | 0.07%   |
| 5.11.0  | 3         | 0.07%   |
| 5.10.60 | 3         | 0.07%   |
| 5.10.10 | 3         | 0.07%   |
| 5.0.0   | 3         | 0.07%   |
| 6.0.2   | 2         | 0.04%   |
| 5.8.2   | 2         | 0.04%   |
| 5.8.16  | 2         | 0.04%   |
| 5.4.21  | 2         | 0.04%   |
| 5.3.5   | 2         | 0.04%   |
| 5.18.15 | 2         | 0.04%   |
| 5.17.11 | 2         | 0.04%   |
| 5.16.12 | 2         | 0.04%   |
| 5.15.5  | 2         | 0.04%   |
| 5.15.35 | 2         | 0.04%   |
| 5.15.32 | 2         | 0.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 2682      | 59.42%  |
| 4.19    | 655       | 14.51%  |
| 4.9     | 123       | 2.72%   |
| 6.0     | 117       | 2.59%   |
| 5.18    | 109       | 2.41%   |
| 5.15    | 107       | 2.37%   |
| 5.9     | 80        | 1.77%   |
| 5.4     | 76        | 1.68%   |
| 5.16    | 70        | 1.55%   |
| 5.19    | 68        | 1.51%   |
| 5.7     | 62        | 1.37%   |
| 5.8     | 61        | 1.35%   |
| 5.14    | 58        | 1.28%   |
| 5.6     | 49        | 1.09%   |
| 5.17    | 48        | 1.06%   |
| 5.3     | 23        | 0.51%   |
| 5.5     | 19        | 0.42%   |
| 5.2     | 17        | 0.38%   |
| 6.1     | 16        | 0.35%   |
| 5.13    | 12        | 0.27%   |
| 4.18    | 12        | 0.27%   |
| 5.12    | 9         | 0.2%    |
| 5.11    | 9         | 0.2%    |
| 3.16    | 8         | 0.18%   |
| 3.10    | 4         | 0.09%   |
| 5.1     | 3         | 0.07%   |
| 5.0     | 3         | 0.07%   |
| 4.17    | 2         | 0.04%   |
| 4.15    | 2         | 0.04%   |
| 5.4.104 | 1         | 0.02%   |
| 5.15.6  | 1         | 0.02%   |
| 4.4     | 1         | 0.02%   |
| 4.20    | 1         | 0.02%   |
| 4.14    | 1         | 0.02%   |
| 4.13    | 1         | 0.02%   |
| 4.12    | 1         | 0.02%   |
| 4.10    | 1         | 0.02%   |
| 3.8     | 1         | 0.02%   |
| 3.0     | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 4075      | 95.21%  |
| i686    | 193       | 4.51%   |
| armv7l  | 9         | 0.21%   |
| aarch64 | 2         | 0.05%   |
| i586    | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Unknown           | 1146      | 26.14%  |
| GNOME             | 1144      | 26.09%  |
| XFCE              | 569       | 12.98%  |
| KDE5              | 532       | 12.14%  |
| MATE              | 182       | 4.15%   |
| X-Cinnamon        | 148       | 3.38%   |
| LXDE              | 133       | 3.03%   |
| Cinnamon          | 127       | 2.9%    |
| KDE               | 109       | 2.49%   |
| i3                | 86        | 1.96%   |
| LXQt              | 62        | 1.41%   |
| GNOME Flashback   | 32        | 0.73%   |
| lightdm-xsession  | 24        | 0.55%   |
| openbox           | 13        | 0.3%    |
| Budgie            | 13        | 0.3%    |
| trinity           | 11        | 0.25%   |
| GNOME Classic     | 9         | 0.21%   |
| sway              | 4         | 0.09%   |
| ICEWM             | 4         | 0.09%   |
| Fluxbox           | 4         | 0.09%   |
| bspwm             | 4         | 0.09%   |
| awesome           | 4         | 0.09%   |
| Enlightenment     | 3         | 0.07%   |
| DWM               | 3         | 0.07%   |
| Cutefish          | 3         | 0.07%   |
| x-session-manager | 2         | 0.05%   |
| Unity             | 2         | 0.05%   |
| KDE4              | 2         | 0.05%   |
| default           | 2         | 0.05%   |
| xmonad            | 1         | 0.02%   |
| wmaker-common     | 1         | 0.02%   |
| matchbox          | 1         | 0.02%   |
| jwm               | 1         | 0.02%   |
| i3-gaps           | 1         | 0.02%   |
| GNUstep           | 1         | 0.02%   |
| Deepin            | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| X11         | 2445      | 56.01%  |
| Unknown     | 919       | 21.05%  |
| Wayland     | 827       | 18.95%  |
| Tty         | 171       | 3.92%   |
| Unspecified | 2         | 0.05%   |
| Web         | 1         | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1784      | 40.64%  |
| GDM     | 860       | 19.59%  |
| LightDM | 665       | 15.15%  |
| SDDM    | 522       | 11.89%  |
| TDM     | 310       | 7.06%   |
| GDM3    | 201       | 4.58%   |
| XDM     | 18        | 0.41%   |
| SLiM    | 13        | 0.3%    |
| NODM    | 8         | 0.18%   |
| KDM     | 7         | 0.16%   |
| WDM     | 1         | 0.02%   |
| LXDM    | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 1280      | 29.43%  |
| Unknown | 936       | 21.52%  |
| ru_RU   | 294       | 6.76%   |
| de_DE   | 261       | 6%      |
| fr_FR   | 231       | 5.31%   |
| en_GB   | 179       | 4.11%   |
| pt_BR   | 148       | 3.4%    |
| es_ES   | 130       | 2.99%   |
| it_IT   | 121       | 2.78%   |
| pl_PL   | 85        | 1.95%   |
| en_CA   | 50        | 1.15%   |
| C       | 44        | 1.01%   |
| es_MX   | 41        | 0.94%   |
| en_AU   | 40        | 0.92%   |
| en_IN   | 38        | 0.87%   |
| zh_CN   | 34        | 0.78%   |
| es_CL   | 28        | 0.64%   |
| es_AR   | 26        | 0.6%    |
| en_IE   | 26        | 0.6%    |
| hu_HU   | 23        | 0.53%   |
| de_CH   | 17        | 0.39%   |
| pt_PT   | 16        | 0.37%   |
| nl_NL   | 14        | 0.32%   |
| es_VE   | 14        | 0.32%   |
| cs_CZ   | 14        | 0.32%   |
| fi_FI   | 13        | 0.3%    |
| en_NZ   | 13        | 0.3%    |
| ja_JP   | 12        | 0.28%   |
| de_AT   | 12        | 0.28%   |
| sv_SE   | 11        | 0.25%   |
| es_CO   | 11        | 0.25%   |
| en_ZA   | 11        | 0.25%   |
| tr_TR   | 10        | 0.23%   |
| ko_KR   | 10        | 0.23%   |
| en_SG   | 9         | 0.21%   |
| ru_UA   | 8         | 0.18%   |
| fr_BE   | 7         | 0.16%   |
| da_DK   | 7         | 0.16%   |
| zh_TW   | 6         | 0.14%   |
| uk_UA   | 6         | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 2641      | 61.11%  |
| BIOS | 1681      | 38.89%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 3023      | 70.29%  |
| Overlay | 976       | 22.69%  |
| Btrfs   | 133       | 3.09%   |
| Unknown | 78        | 1.81%   |
| Xfs     | 40        | 0.93%   |
| Ext2    | 14        | 0.33%   |
| Zfs     | 12        | 0.28%   |
| Tmpfs   | 7         | 0.16%   |
| Rootfs  | 7         | 0.16%   |
| Ext3    | 6         | 0.14%   |
| Aufs    | 4         | 0.09%   |
| F2fs    | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 2655      | 61.05%  |
| Unknown | 871       | 20.03%  |
| MBR     | 823       | 18.92%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3527      | 81.47%  |
| Yes       | 802       | 18.53%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3206      | 74.04%  |
| Yes       | 1124      | 25.96%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 947       | 22.13%  |
| Hewlett-Packard        | 631       | 14.75%  |
| Dell                   | 609       | 14.23%  |
| Apple                  | 588       | 13.74%  |
| ASUSTek Computer       | 400       | 9.35%   |
| Acer                   | 265       | 6.19%   |
| Google                 | 136       | 3.18%   |
| Toshiba                | 71        | 1.66%   |
| MSI                    | 69        | 1.61%   |
| Samsung Electronics    | 63        | 1.47%   |
| Aquarius               | 44        | 1.03%   |
| Sony                   | 39        | 0.91%   |
| HUAWEI                 | 37        | 0.86%   |
| Unknown                | 32        | 0.75%   |
| Notebook               | 24        | 0.56%   |
| Fujitsu                | 18        | 0.42%   |
| Panasonic              | 14        | 0.33%   |
| Medion                 | 13        | 0.3%    |
| Alienware              | 13        | 0.3%    |
| Positivo               | 11        | 0.26%   |
| Intel                  | 11        | 0.26%   |
| IBM                    | 11        | 0.26%   |
| Timi                   | 10        | 0.23%   |
| Packard Bell           | 10        | 0.23%   |
| TUXEDO                 | 9         | 0.21%   |
| Clevo                  | 9         | 0.21%   |
| LG Electronics         | 8         | 0.19%   |
| Fujitsu Siemens        | 8         | 0.19%   |
| Razer                  | 7         | 0.16%   |
| SLIMBOOK               | 6         | 0.14%   |
| PC Specialist          | 6         | 0.14%   |
| GPU Company            | 6         | 0.14%   |
| Gigabyte Technology    | 6         | 0.14%   |
| HONOR                  | 5         | 0.12%   |
| Chuwi                  | 5         | 0.12%   |
| Avell High Performance | 5         | 0.12%   |
| System76               | 4         | 0.09%   |
| Insyde                 | 4         | 0.09%   |
| Gateway                | 4         | 0.09%   |
| eMachines              | 4         | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Apple MacBook5,2                      | 306       | 7.15%   |
| Apple MacBookAir7,1                   | 77        | 1.8%    |
| Apple MacBookAir7,2                   | 76        | 1.78%   |
| Google Enguarde                       | 74        | 1.73%   |
| Apple MacBook2,1                      | 56        | 1.31%   |
| Aquarius NS585                        | 44        | 1.03%   |
| Unknown                               | 44        | 1.03%   |
| Lenovo ThinkPad E475 20H40006US       | 24        | 0.56%   |
| Google Terra                          | 23        | 0.54%   |
| Apple MacBook4,1                      | 23        | 0.54%   |
| HP Notebook                           | 22        | 0.51%   |
| Lenovo ThinkPad 13 2nd Gen 20J10046US | 16        | 0.37%   |
| HP Pavilion g6                        | 16        | 0.37%   |
| Acer Aspire A315-23                   | 16        | 0.37%   |
| ASUS 1005HA                           | 15        | 0.35%   |
| Dell Latitude E7440                   | 12        | 0.28%   |
| HP EliteBook 8460p                    | 11        | 0.26%   |
| Google Reks                           | 11        | 0.26%   |
| HP Laptop 15-db0xxx                   | 10        | 0.23%   |
| HP 250 G7 Notebook PC                 | 9         | 0.21%   |
| Samsung 300E4C/300E5C/300E7C          | 8         | 0.19%   |
| Dell XPS 13 9310                      | 8         | 0.19%   |
| Dell Latitude E7450                   | 8         | 0.19%   |
| Dell Latitude E6420                   | 8         | 0.19%   |
| Dell Inspiron 5570                    | 8         | 0.19%   |
| Lenovo IdeaPad S145-15API 81V7        | 7         | 0.16%   |
| HP Stream Notebook PC 13              | 7         | 0.16%   |
| HP Pavilion Notebook                  | 7         | 0.16%   |
| HP Pavilion Gaming Laptop 15-ec1xxx   | 7         | 0.16%   |
| HP Pavilion dv6                       | 7         | 0.16%   |
| HP Laptop 15-db1xxx                   | 7         | 0.16%   |
| HP Laptop 15-bw0xx                    | 7         | 0.16%   |
| HP EliteBook 8470p                    | 7         | 0.16%   |
| HP EliteBook 840 G8 Notebook PC       | 7         | 0.16%   |
| HP EliteBook 840 G3                   | 7         | 0.16%   |
| Dell Latitude E7470                   | 7         | 0.16%   |
| Dell Latitude E6430                   | 7         | 0.16%   |
| Dell Latitude E6330                   | 7         | 0.16%   |
| Dell Latitude 7490                    | 7         | 0.16%   |
| Dell Latitude 7480                    | 7         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 627       | 14.65%  |
| Apple MacBook5    | 307       | 7.17%   |
| Dell Latitude     | 229       | 5.35%   |
| Dell Inspiron     | 193       | 4.51%   |
| Acer Aspire       | 174       | 4.07%   |
| Lenovo IdeaPad    | 168       | 3.93%   |
| Apple MacBookAir7 | 153       | 3.58%   |
| HP EliteBook      | 127       | 2.97%   |
| HP Pavilion       | 96        | 2.24%   |
| HP Laptop         | 85        | 1.99%   |
| HP ProBook        | 81        | 1.89%   |
| Google Enguarde   | 74        | 1.73%   |
| Dell XPS          | 65        | 1.52%   |
| ASUS VivoBook     | 56        | 1.31%   |
| Apple MacBook2    | 56        | 1.31%   |
| Toshiba Satellite | 54        | 1.26%   |
| Dell Vostro       | 53        | 1.24%   |
| Dell Precision    | 44        | 1.03%   |
| Aquarius NS585    | 44        | 1.03%   |
| Unknown           | 44        | 1.03%   |
| HP Compaq         | 39        | 0.91%   |
| HP 250            | 29        | 0.68%   |
| ASUS ZenBook      | 27        | 0.63%   |
| HP ZBook          | 25        | 0.58%   |
| Lenovo Legion     | 24        | 0.56%   |
| Google Terra      | 23        | 0.54%   |
| Apple MacBook4    | 23        | 0.54%   |
| HP Notebook       | 22        | 0.51%   |
| ASUS ASUS         | 22        | 0.51%   |
| Acer Swift        | 21        | 0.49%   |
| Lenovo ThinkBook  | 20        | 0.47%   |
| Acer Nitro        | 19        | 0.44%   |
| HP 255            | 18        | 0.42%   |
| Acer TravelMate   | 18        | 0.42%   |
| HP ENVY           | 16        | 0.37%   |
| ASUS ROG          | 16        | 0.37%   |
| HP OMEN           | 15        | 0.35%   |
| Fujitsu LIFEBOOK  | 15        | 0.35%   |
| ASUS 1005HA       | 15        | 0.35%   |
| HP Stream         | 14        | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 436       | 10.19%  |
| 2009    | 433       | 10.12%  |
| 2020    | 390       | 9.11%   |
| 2021    | 353       | 8.25%   |
| 2016    | 279       | 6.52%   |
| 2018    | 277       | 6.47%   |
| 2011    | 273       | 6.38%   |
| 2012    | 272       | 6.36%   |
| 2015    | 267       | 6.24%   |
| 2017    | 266       | 6.22%   |
| 2013    | 203       | 4.74%   |
| 2014    | 184       | 4.3%    |
| 2010    | 162       | 3.79%   |
| 2022    | 141       | 3.3%    |
| 2008    | 134       | 3.13%   |
| 2007    | 122       | 2.85%   |
| 2006    | 27        | 0.63%   |
| 2005    | 22        | 0.51%   |
| Unknown | 14        | 0.33%   |
| 2004    | 11        | 0.26%   |
| 2003    | 11        | 0.26%   |
| 2002    | 2         | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 4279      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 3964      | 92.21%  |
| Enabled  | 335       | 7.79%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 4130      | 96.5%   |
| Yes  | 150       | 3.5%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1121      | 25.96%  |
| 3.01-4.0    | 830       | 19.22%  |
| 16.01-24.0  | 677       | 15.68%  |
| 8.01-16.0   | 657       | 15.22%  |
| 1.01-2.0    | 531       | 12.3%   |
| 32.01-64.0  | 235       | 5.44%   |
| 2.01-3.0    | 89        | 2.06%   |
| 0.51-1.0    | 75        | 1.74%   |
| 24.01-32.0  | 40        | 0.93%   |
| 64.01-256.0 | 40        | 0.93%   |
| 0.01-0.5    | 21        | 0.49%   |
| Unknown     | 2         | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1813      | 39.59%  |
| 2.01-3.0   | 920       | 20.09%  |
| 4.01-8.0   | 586       | 12.79%  |
| 3.01-4.0   | 482       | 10.52%  |
| 0.51-1.0   | 476       | 10.39%  |
| 8.01-16.0  | 159       | 3.47%   |
| 0.01-0.5   | 117       | 2.55%   |
| 16.01-24.0 | 13        | 0.28%   |
| Unknown    | 7         | 0.15%   |
| 32.01-64.0 | 3         | 0.07%   |
| 24.01-32.0 | 3         | 0.07%   |
| 0          | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3405      | 78.49%  |
| 2      | 801       | 18.46%  |
| 3      | 86        | 1.98%   |
| 0      | 26        | 0.6%    |
| 4      | 14        | 0.32%   |
| 5      | 4         | 0.09%   |
| 7      | 2         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2784      | 64.8%   |
| Yes       | 1512      | 35.2%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3482      | 81.09%  |
| No        | 812       | 18.91%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4197      | 97.99%  |
| No        | 86        | 2.01%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3438      | 79.81%  |
| No        | 870       | 20.19%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 1170      | 27.15%  |
| Germany      | 389       | 9.03%   |
| Russia       | 343       | 7.96%   |
| France       | 292       | 6.78%   |
| Brazil       | 219       | 5.08%   |
| Spain        | 183       | 4.25%   |
| Italy        | 162       | 3.76%   |
| Poland       | 121       | 2.81%   |
| UK           | 96        | 2.23%   |
| Netherlands  | 72        | 1.67%   |
| Canada       | 70        | 1.62%   |
| Switzerland  | 61        | 1.42%   |
| Mexico       | 58        | 1.35%   |
| India        | 56        | 1.3%    |
| Ukraine      | 49        | 1.14%   |
| China        | 49        | 1.14%   |
| Argentina    | 46        | 1.07%   |
| Australia    | 45        | 1.04%   |
| Sweden       | 39        | 0.91%   |
| Portugal     | 38        | 0.88%   |
| Turkey       | 35        | 0.81%   |
| Hungary      | 34        | 0.79%   |
| Chile        | 34        | 0.79%   |
| Belgium      | 31        | 0.72%   |
| Czechia      | 30        | 0.7%    |
| Austria      | 30        | 0.7%    |
| Greece       | 28        | 0.65%   |
| Norway       | 26        | 0.6%    |
| Romania      | 23        | 0.53%   |
| Finland      | 23        | 0.53%   |
| Ireland      | 22        | 0.51%   |
| Indonesia    | 22        | 0.51%   |
| Japan        | 21        | 0.49%   |
| Colombia     | 21        | 0.49%   |
| Venezuela    | 17        | 0.39%   |
| New Zealand  | 17        | 0.39%   |
| Denmark      | 16        | 0.37%   |
| Thailand     | 15        | 0.35%   |
| Bulgaria     | 14        | 0.32%   |
| South Africa | 13        | 0.3%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Bangor            | 565       | 12.44%  |
| Dover-Foxcroft    | 229       | 5.04%   |
| Voronezh          | 140       | 3.08%   |
| Moscow            | 52        | 1.14%   |
| Paris             | 50        | 1.1%    |
| St Petersburg     | 48        | 1.06%   |
| Berlin            | 42        | 0.92%   |
| Seville           | 35        | 0.77%   |
| Madrid            | 35        | 0.77%   |
| Sao Paulo         | 34        | 0.75%   |
| Warsaw            | 30        | 0.66%   |
| Munich            | 29        | 0.64%   |
| Milan             | 23        | 0.51%   |
| Amsterdam         | 23        | 0.51%   |
| Vienna            | 22        | 0.48%   |
| Hamburg           | 21        | 0.46%   |
| Zurich            | 17        | 0.37%   |
| Prague            | 17        | 0.37%   |
| London            | 17        | 0.37%   |
| Barcelona         | 17        | 0.37%   |
| Frankfurt am Main | 16        | 0.35%   |
| Athens            | 16        | 0.35%   |
| Sydney            | 15        | 0.33%   |
| Budapest          | 15        | 0.33%   |
| Dublin            | 14        | 0.31%   |
| Perm              | 13        | 0.29%   |
| Mexico City       | 13        | 0.29%   |
| Lisbon            | 13        | 0.29%   |
| Istanbul          | 13        | 0.29%   |
| Helsinki          | 12        | 0.26%   |
| Brasília         | 12        | 0.26%   |
| Toronto           | 11        | 0.24%   |
| Singapore         | 11        | 0.24%   |
| Blizniew          | 11        | 0.24%   |
| Bangkok           | 11        | 0.24%   |
| Zagreb            | 10        | 0.22%   |
| Turin             | 10        | 0.22%   |
| San José         | 10        | 0.22%   |
| Rome              | 10        | 0.22%   |
| New York          | 10        | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 731       | 932    | 14.27%  |
| WDC                       | 582       | 709    | 11.36%  |
| Seagate                   | 488       | 581    | 9.53%   |
| Toshiba                   | 399       | 446    | 7.79%   |
| Unknown                   | 345       | 444    | 6.74%   |
| Kingston                  | 282       | 343    | 5.51%   |
| Fujitsu                   | 252       | 259    | 4.92%   |
| SanDisk                   | 246       | 298    | 4.8%    |
| Crucial                   | 197       | 239    | 3.85%   |
| SK hynix                  | 195       | 238    | 3.81%   |
| Apple                     | 178       | 217    | 3.48%   |
| Hitachi                   | 146       | 170    | 2.85%   |
| Intel                     | 119       | 142    | 2.32%   |
| A-DATA Technology         | 119       | 206    | 2.32%   |
| Micron Technology         | 114       | 121    | 2.23%   |
| HGST                      | 104       | 120    | 2.03%   |
| KIOXIA                    | 47        | 58     | 0.92%   |
| LITEON                    | 30        | 35     | 0.59%   |
| China                     | 28        | 30     | 0.55%   |
| Transcend                 | 26        | 32     | 0.51%   |
| Unknown                   | 25        | 26     | 0.49%   |
| Silicon Motion            | 22        | 23     | 0.43%   |
| Intenso                   | 22        | 29     | 0.43%   |
| PNY                       | 20        | 23     | 0.39%   |
| Phison                    | 20        | 28     | 0.39%   |
| SPCC                      | 19        | 23     | 0.37%   |
| SABRENT                   | 16        | 17     | 0.31%   |
| Patriot                   | 16        | 18     | 0.31%   |
| LITEONIT                  | 15        | 17     | 0.29%   |
| SSSTC                     | 14        | 14     | 0.27%   |
| Team                      | 12        | 14     | 0.23%   |
| OCZ                       | 11        | 13     | 0.21%   |
| Micron/Crucial Technology | 11        | 11     | 0.21%   |
| GOODRAM                   | 11        | 13     | 0.21%   |
| LDLC                      | 9         | 9      | 0.18%   |
| JMicron Technology        | 9         | 9      | 0.18%   |
| Plextor                   | 8         | 8      | 0.16%   |
| Lenovo                    | 8         | 10     | 0.16%   |
| Hewlett-Packard           | 8         | 8      | 0.16%   |
| ASMT                      | 8         | 14     | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB       | 201       | 3.84%   |
| Apple SSD AP0128H 121GB              | 77        | 1.47%   |
| Apple SSD SM0128G 121GB              | 72        | 1.37%   |
| Seagate ST1000LM035-1RK172 1TB       | 63        | 1.2%    |
| Kingston SA400S37240G 240GB SSD      | 57        | 1.09%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 53        | 1.01%   |
| Kingston SA400S37120G 120GB SSD      | 51        | 0.97%   |
| Toshiba MK1655GSXF 160GB             | 46        | 0.88%   |
| A-DATA SU800 512GB SSD               | 46        | 0.88%   |
| Toshiba MK1653GSX 160GB              | 43        | 0.82%   |
| Unknown AGND3R  16GB                 | 39        | 0.74%   |
| HGST HTS721010A9E630 1TB             | 39        | 0.74%   |
| Toshiba MQ01ABD100 1TB               | 37        | 0.71%   |
| Toshiba MQ04ABF100 1TB               | 32        | 0.61%   |
| Toshiba MQ01ABF050 500GB             | 32        | 0.61%   |
| Unknown HAG2e  16GB                  | 31        | 0.59%   |
| Unknown MMC Card  32GB               | 30        | 0.57%   |
| Crucial CT500MX500SSD1 500GB         | 30        | 0.57%   |
| Unknown SDW16G  16GB                 | 25        | 0.48%   |
| Samsung SSD 860 EVO 500GB            | 25        | 0.48%   |
| Samsung SSD 850 EVO 250GB            | 25        | 0.48%   |
| Unknown                              | 25        | 0.48%   |
| Seagate ST1000LM048-2E7172 1TB       | 24        | 0.46%   |
| Kingston SA400S37480G 480GB SSD      | 24        | 0.46%   |
| Seagate ST500LT012-1DG142 500GB      | 23        | 0.44%   |
| Samsung SSD 860 EVO 1TB              | 22        | 0.42%   |
| Samsung SSD 970 EVO Plus 1TB         | 21        | 0.4%    |
| Unknown MMC Card  64GB               | 20        | 0.38%   |
| Samsung SSD 860 EVO 250GB            | 20        | 0.38%   |
| Crucial CT1000MX500SSD1 1TB          | 20        | 0.38%   |
| Seagate ST9500325AS 500GB            | 19        | 0.36%   |
| Kingston SV300S37A120G 120GB SSD     | 19        | 0.36%   |
| WDC WD10SPZX-24Z10 1TB               | 18        | 0.34%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB | 18        | 0.34%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 18        | 0.34%   |
| Samsung MZVLB512HBJQ-000L7 512GB     | 18        | 0.34%   |
| HGST HTS725050A7E630 500GB           | 18        | 0.34%   |
| Crucial CT240BX500SSD1 240GB         | 18        | 0.34%   |
| Seagate ST1000LM049-2GH172 1TB       | 17        | 0.32%   |
| WDC WD1600BUDT-63DPZY0 160GB         | 16        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 472       | 562    | 27.86%  |
| WDC                 | 341       | 386    | 20.13%  |
| Toshiba             | 295       | 324    | 17.41%  |
| Fujitsu             | 252       | 259    | 14.88%  |
| Hitachi             | 146       | 170    | 8.62%   |
| HGST                | 104       | 120    | 6.14%   |
| Samsung Electronics | 30        | 32     | 1.77%   |
| SABRENT             | 16        | 17     | 0.94%   |
| Unknown             | 12        | 15     | 0.71%   |
| IBM/Hitachi         | 5         | 6      | 0.3%    |
| ASMT                | 5         | 10     | 0.3%    |
| Intenso             | 4         | 5      | 0.24%   |
| SILICONMOTION       | 2         | 2      | 0.12%   |
| USB3.0              | 1         | 1      | 0.06%   |
| Unknown (CF)        | 1         | 1      | 0.06%   |
| SAGE                | 1         | 1      | 0.06%   |
| QNAP                | 1         | 2      | 0.06%   |
| PHD 3.0             | 1         | 1      | 0.06%   |
| Maxone              | 1         | 1      | 0.06%   |
| IBM                 | 1         | 1      | 0.06%   |
| Hewlett-Packard     | 1         | 1      | 0.06%   |
| ASMT109x            | 1         | 1      | 0.06%   |
| Apple               | 1         | 1      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 344       | 435    | 20.49%  |
| Kingston            | 225       | 282    | 13.4%   |
| SanDisk             | 186       | 230    | 11.08%  |
| Crucial             | 177       | 217    | 10.54%  |
| Apple               | 92        | 99     | 5.48%   |
| A-DATA Technology   | 88        | 163    | 5.24%   |
| WDC                 | 67        | 87     | 3.99%   |
| Micron Technology   | 51        | 54     | 3.04%   |
| SK hynix            | 39        | 47     | 2.32%   |
| Intel               | 36        | 40     | 2.14%   |
| Toshiba             | 28        | 31     | 1.67%   |
| China               | 28        | 30     | 1.67%   |
| LITEON              | 25        | 29     | 1.49%   |
| Transcend           | 24        | 30     | 1.43%   |
| PNY                 | 16        | 18     | 0.95%   |
| Intenso             | 16        | 21     | 0.95%   |
| SPCC                | 15        | 18     | 0.89%   |
| Patriot             | 15        | 17     | 0.89%   |
| LITEONIT            | 15        | 17     | 0.89%   |
| Team                | 11        | 13     | 0.66%   |
| OCZ                 | 11        | 13     | 0.66%   |
| Plextor             | 8         | 8      | 0.48%   |
| LDLC                | 8         | 8      | 0.48%   |
| Goodram             | 8         | 10     | 0.48%   |
| Netac               | 7         | 11     | 0.42%   |
| KingSpec            | 7         | 7      | 0.42%   |
| KingDian            | 6         | 6      | 0.36%   |
| Seagate             | 5         | 5      | 0.3%    |
| Lexar               | 5         | 6      | 0.3%    |
| JMicron Technology  | 5         | 5      | 0.3%    |
| Corsair             | 5         | 5      | 0.3%    |
| Unknown             | 5         | 5      | 0.3%    |
| Hewlett-Packard     | 4         | 5      | 0.24%   |
| Dogfish             | 4         | 6      | 0.24%   |
| BIWIN               | 4         | 4      | 0.24%   |
| ASUS-PHISON         | 4         | 5      | 0.24%   |
| Apacer              | 4         | 4      | 0.24%   |
| ZTC                 | 3         | 7      | 0.18%   |
| KIOXIA-EXCERIA      | 3         | 4      | 0.18%   |
| Kingchuxing         | 3         | 3      | 0.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1646      | 1919   | 33.5%   |
| SSD     | 1567      | 2096   | 31.89%  |
| NVMe    | 1288      | 1670   | 26.22%  |
| MMC     | 367       | 468    | 7.47%   |
| Unknown | 45        | 50     | 0.92%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2904      | 3877   | 61.77%  |
| NVMe | 1288      | 1666   | 27.4%   |
| MMC  | 367       | 468    | 7.81%   |
| SAS  | 142       | 192    | 3.02%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2256      | 2826   | 71.19%  |
| 0.51-1.0   | 812       | 1065   | 25.62%  |
| 1.01-2.0   | 64        | 78     | 2.02%   |
| 3.01-4.0   | 19        | 22     | 0.6%    |
| 4.01-10.0  | 16        | 21     | 0.5%    |
| 20.01-50.0 | 1         | 2      | 0.03%   |
| 2.01-3.0   | 1         | 1      | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1257      | 28.39%  |
| 251-500        | 900       | 20.33%  |
| Unknown        | 723       | 16.33%  |
| 501-1000       | 566       | 12.78%  |
| 51-100         | 290       | 6.55%   |
| 1-20           | 221       | 4.99%   |
| 1001-2000      | 220       | 4.97%   |
| 21-50          | 158       | 3.57%   |
| 2001-3000      | 52        | 1.17%   |
| More than 3000 | 41        | 0.93%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1597      | 34.97%  |
| Unknown        | 723       | 15.83%  |
| 21-50          | 582       | 12.74%  |
| 101-250        | 581       | 12.72%  |
| 51-100         | 478       | 10.47%  |
| 251-500        | 318       | 6.96%   |
| 501-1000       | 186       | 4.07%   |
| 1001-2000      | 63        | 1.38%   |
| More than 3000 | 16        | 0.35%   |
| 2001-3000      | 12        | 0.26%   |
| 0              | 11        | 0.24%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB        | 20        | 20     | 4.71%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 11        | 13     | 2.59%   |
| Toshiba MK1653GSX 160GB               | 9         | 9      | 2.12%   |
| Seagate ST9500325AS 500GB             | 9         | 9      | 2.12%   |
| Toshiba MK1655GSXF 160GB              | 7         | 7      | 1.65%   |
| Seagate ST9500420AS 500GB             | 6         | 6      | 1.41%   |
| Seagate ST1000LM035-1RK172 1TB        | 6         | 6      | 1.41%   |
| Hitachi HTS545050B9A300 500GB         | 6         | 6      | 1.41%   |
| Hitachi HTS543216L9SA02 160GB         | 6         | 6      | 1.41%   |
| Toshiba MQ01ABD100 1TB                | 5         | 5      | 1.18%   |
| Seagate ST500LT012-9WS142 500GB       | 5         | 6      | 1.18%   |
| Seagate ST500LM021-1KJ152 500GB       | 5         | 5      | 1.18%   |
| Hitachi HTS542512K9SA00 120GB         | 5         | 6      | 1.18%   |
| HGST HTS725050A7E630 500GB            | 5         | 5      | 1.18%   |
| WDC WD1600BUDT-63DPZY0 160GB          | 4         | 4      | 0.94%   |
| Toshiba MQ01ABF050 500GB              | 4         | 4      | 0.94%   |
| Seagate ST500LM000-SSHD-8GB           | 4         | 4      | 0.94%   |
| Seagate ST320LT007-9ZV142 320GB       | 4         | 6      | 0.94%   |
| Hitachi HTS547575A9E384 752GB         | 4         | 4      | 0.94%   |
| Toshiba MQ04ABF100 1TB                | 3         | 3      | 0.71%   |
| SK hynix PC711 HFS512GDE9X073N 512GB  | 3         | 3      | 0.71%   |
| SK hynix HFS256G39MND-2300A 256GB SSD | 3         | 4      | 0.71%   |
| Seagate ST9320325AS 320GB             | 3         | 3      | 0.71%   |
| Seagate ST9250315AS 250GB             | 3         | 4      | 0.71%   |
| Seagate ST500LT012-1DG142 500GB       | 3         | 3      | 0.71%   |
| Kingston SA400S37240G 240GB SSD       | 3         | 3      | 0.71%   |
| Hitachi HTS547550A9E384 500GB         | 3         | 3      | 0.71%   |
| Hitachi HTS542516K9SA00 160GB         | 3         | 3      | 0.71%   |
| HGST HTS721010A9E630 1TB              | 3         | 4      | 0.71%   |
| HGST HTS541010A9E680 1TB              | 3         | 3      | 0.71%   |
| Crucial CT275MX300SSD1 275GB          | 3         | 3      | 0.71%   |
| WDC WD7500BPVX-22JC3T0 752GB          | 2         | 2      | 0.47%   |
| WDC WD7500BPKT-75PK4T0 752GB          | 2         | 2      | 0.47%   |
| WDC WD5000LPVX-75V0TT0 500GB          | 2         | 2      | 0.47%   |
| WDC WD10SPZX-60Z10T0 1TB              | 2         | 3      | 0.47%   |
| WDC WD10JPVX-22JC3T0 1TB              | 2         | 2      | 0.47%   |
| WDC WD10JPCX-24UE4T0 1TB              | 2         | 3      | 0.47%   |
| Toshiba MQ01ACF050 500GB              | 2         | 2      | 0.47%   |
| Toshiba MQ01ABD050 500GB              | 2         | 2      | 0.47%   |
| SK hynix SH920 mSATA 128GB SSD        | 2         | 2      | 0.47%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 92        | 100    | 21.7%   |
| Hitachi             | 64        | 69     | 15.09%  |
| Toshiba             | 49        | 50     | 11.56%  |
| WDC                 | 42        | 44     | 9.91%   |
| Fujitsu             | 34        | 34     | 8.02%   |
| HGST                | 22        | 23     | 5.19%   |
| Samsung Electronics | 21        | 23     | 4.95%   |
| SK hynix            | 17        | 18     | 4.01%   |
| Kingston            | 13        | 14     | 3.07%   |
| Micron Technology   | 12        | 12     | 2.83%   |
| SanDisk             | 9         | 11     | 2.12%   |
| Intel               | 9         | 10     | 2.12%   |
| Crucial             | 8         | 9      | 1.89%   |
| A-DATA Technology   | 8         | 9      | 1.89%   |
| LITEONIT            | 3         | 4      | 0.71%   |
| LITEON              | 3         | 3      | 0.71%   |
| IBM/Hitachi         | 2         | 2      | 0.47%   |
| Corsair             | 2         | 2      | 0.47%   |
| Unknown             | 2         | 2      | 0.47%   |
| Team                | 1         | 1      | 0.24%   |
| SSSTC               | 1         | 1      | 0.24%   |
| ShiJi               | 1         | 1      | 0.24%   |
| Plextor             | 1         | 1      | 0.24%   |
| Lenovo              | 1         | 1      | 0.24%   |
| KingSpec            | 1         | 1      | 0.24%   |
| KingDian            | 1         | 1      | 0.24%   |
| IBM                 | 1         | 1      | 0.24%   |
| GOODRAM             | 1         | 1      | 0.24%   |
| DGM                 | 1         | 1      | 0.24%   |
| China               | 1         | 1      | 0.24%   |
| Apple               | 1         | 1      | 0.24%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 92        | 100    | 29.21%  |
| Hitachi             | 64        | 69     | 20.32%  |
| Toshiba             | 48        | 49     | 15.24%  |
| WDC                 | 41        | 43     | 13.02%  |
| Fujitsu             | 34        | 34     | 10.79%  |
| HGST                | 22        | 23     | 6.98%   |
| Samsung Electronics | 11        | 11     | 3.49%   |
| IBM/Hitachi         | 2         | 2      | 0.63%   |
| IBM                 | 1         | 1      | 0.32%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 312       | 332    | 74.11%  |
| SSD  | 96        | 106    | 22.8%   |
| NVMe | 13        | 13     | 3.09%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                           | Notebooks | Drives | Percent |
|-------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-35A0RT0 500GB                    | 1         | 1      | 14.29%  |
| Toshiba MK6465GSX 640GB                         | 1         | 1      | 14.29%  |
| Seagate ST500LT012-1DG142 500GB                 | 1         | 1      | 14.29%  |
| Seagate ST500LM000-1EJ162 500GB                 | 1         | 1      | 14.29%  |
| Samsung Electronics MZVLB512HAJQ-000H1 512GB    | 1         | 1      | 14.29%  |
| Samsung Electronics MZMPC032HBCD-000H1 32GB SSD | 1         | 1      | 14.29%  |
| Hitachi HTS545050A7E380 500GB                   | 1         | 2      | 14.29%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2         | 2      | 28.57%  |
| Samsung Electronics | 2         | 2      | 28.57%  |
| WDC                 | 1         | 1      | 14.29%  |
| Toshiba             | 1         | 1      | 14.29%  |
| Hitachi             | 1         | 2      | 14.29%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 2896      | 3862   | 63.12%  |
| Detected | 1266      | 1881   | 27.59%  |
| Malfunc  | 418       | 451    | 9.11%   |
| Failed   | 7         | 8      | 0.15%   |
| Limited  | 1         | 1      | 0.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2611      | 55.31%  |
| Samsung Electronics              | 456       | 9.66%   |
| AMD                              | 404       | 8.56%   |
| Nvidia                           | 327       | 6.93%   |
| SanDisk                          | 220       | 4.66%   |
| SK hynix                         | 145       | 3.07%   |
| Apple                            | 84        | 1.78%   |
| Toshiba America Info Systems     | 82        | 1.74%   |
| Micron Technology                | 63        | 1.33%   |
| Kingston Technology Company      | 57        | 1.21%   |
| KIOXIA                           | 47        | 1%      |
| Phison Electronics               | 38        | 0.8%    |
| ADATA Technology                 | 37        | 0.78%   |
| Silicon Motion                   | 33        | 0.7%    |
| Micron/Crucial Technology        | 31        | 0.66%   |
| Solid State Storage Technology   | 18        | 0.38%   |
| Silicon Integrated Systems [SiS] | 12        | 0.25%   |
| Union Memory (Shenzhen)          | 11        | 0.23%   |
| Lite-On Technology               | 6         | 0.13%   |
| Shenzhen Longsys Electronics     | 5         | 0.11%   |
| Realtek Semiconductor            | 5         | 0.11%   |
| Lenovo                           | 5         | 0.11%   |
| Silicon Image                    | 3         | 0.06%   |
| Seagate Technology               | 3         | 0.06%   |
| MAXIO Technology (Hangzhou)      | 3         | 0.06%   |
| Unknown                          | 3         | 0.06%   |
| VIA Technologies                 | 2         | 0.04%   |
| ULi Electronics                  | 2         | 0.04%   |
| Marvell Technology Group         | 2         | 0.04%   |
| ASMedia Technology               | 2         | 0.04%   |
| Yangtze Memory Technologies      | 1         | 0.02%   |
| JMicron Technology               | 1         | 0.02%   |
| Biwin Storage Technology         | 1         | 0.02%   |
| Adaptec                          | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 351       | 6.93%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 345       | 6.81%   |
| Nvidia MCP79 AHCI Controller                                                   | 313       | 6.18%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 289       | 5.7%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 200       | 3.95%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 196       | 3.87%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 188       | 3.71%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 129       | 2.55%   |
| Intel Volume Management Device NVMe RAID Controller                            | 122       | 2.41%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 109       | 2.15%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 99        | 1.95%   |
| Samsung NVMe SSD Controller 980                                                | 97        | 1.91%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 95        | 1.87%   |
| Samsung Electronics SATA controller                                            | 82        | 1.62%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 82        | 1.62%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 81        | 1.6%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 80        | 1.58%   |
| Apple S1X NVMe Controller                                                      | 78        | 1.54%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 76        | 1.5%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 74        | 1.46%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 70        | 1.38%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 68        | 1.34%   |
| Micron Non-Volatile memory controller                                          | 63        | 1.24%   |
| Intel Comet Lake SATA AHCI Controller                                          | 62        | 1.22%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 58        | 1.14%   |
| Intel Tiger Lake-LP SATA Controller                                            | 56        | 1.1%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 56        | 1.1%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 52        | 1.03%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 51        | 1.01%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 51        | 1.01%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 46        | 0.91%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 44        | 0.87%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 44        | 0.87%   |
| Intel SSD 660P Series                                                          | 42        | 0.83%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 40        | 0.79%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 39        | 0.77%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 37        | 0.73%   |
| Sandisk Non-Volatile memory controller                                         | 35        | 0.69%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 34        | 0.67%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 34        | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 2953      | 59.83%  |
| NVMe | 1297      | 26.28%  |
| IDE  | 361       | 7.31%   |
| RAID | 324       | 6.56%   |
| SCSI | 1         | 0.02%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 3684      | 86.07%  |
| AMD          | 581       | 13.57%  |
| ARM          | 10        | 0.23%   |
| CentaurHauls | 3         | 0.07%   |
| Unknown      | 2         | 0.05%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU P7450 @ 2.13GHz          | 308       | 7.19%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 145       | 3.38%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 91        | 2.12%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 78        | 1.82%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 69        | 1.61%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 69        | 1.61%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 65        | 1.52%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 63        | 1.47%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 62        | 1.45%   |
| Intel Core 2 CPU T7200 @ 2.00GHz              | 60        | 1.4%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 57        | 1.33%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 55        | 1.28%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 53        | 1.24%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 51        | 1.19%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 50        | 1.17%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 46        | 1.07%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 45        | 1.05%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 44        | 1.03%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 39        | 0.91%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 39        | 0.91%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 37        | 0.86%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 35        | 0.82%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 33        | 0.77%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 30        | 0.7%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 30        | 0.7%    |
| AMD Ryzen 5 5500U with Radeon Graphics        | 30        | 0.7%    |
| Intel Atom CPU N270 @ 1.60GHz                 | 29        | 0.68%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 27        | 0.63%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 27        | 0.63%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 26        | 0.61%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 25        | 0.58%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 25        | 0.58%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz          | 25        | 0.58%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 25        | 0.58%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 24        | 0.56%   |
| AMD PRO A6-9500B R5, 6 COMPUTE CORES 2C+4G    | 24        | 0.56%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 23        | 0.54%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 22        | 0.51%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 22        | 0.51%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 22        | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1065      | 24.87%  |
| Intel Core i7           | 816       | 19.06%  |
| Intel Core 2 Duo        | 481       | 11.23%  |
| Other                   | 319       | 7.45%   |
| Intel Celeron           | 319       | 7.45%   |
| Intel Core i3           | 287       | 6.7%    |
| AMD Ryzen 5             | 168       | 3.92%   |
| Intel Atom              | 127       | 2.97%   |
| AMD Ryzen 7             | 94        | 2.2%    |
| Intel Pentium           | 81        | 1.89%   |
| Intel Core 2            | 70        | 1.63%   |
| AMD Ryzen 7 PRO         | 43        | 1%      |
| Intel Pentium M         | 31        | 0.72%   |
| AMD A6                  | 30        | 0.7%    |
| Intel Pentium Dual-Core | 24        | 0.56%   |
| AMD A4                  | 24        | 0.56%   |
| AMD Ryzen 3             | 22        | 0.51%   |
| Intel Genuine           | 21        | 0.49%   |
| Intel Pentium Dual      | 20        | 0.47%   |
| AMD A8                  | 18        | 0.42%   |
| AMD E1                  | 16        | 0.37%   |
| AMD Ryzen 5 PRO         | 15        | 0.35%   |
| Intel Celeron M         | 13        | 0.3%    |
| AMD Ryzen 9             | 13        | 0.3%    |
| AMD A10                 | 12        | 0.28%   |
| AMD E2                  | 11        | 0.26%   |
| AMD E                   | 10        | 0.23%   |
| Intel Pentium Silver    | 9         | 0.21%   |
| Intel Pentium 4         | 9         | 0.21%   |
| Intel Core i9           | 8         | 0.19%   |
| Intel Core m3           | 7         | 0.16%   |
| AMD A12                 | 7         | 0.16%   |
| AMD Turion 64 X2 Mobile | 6         | 0.14%   |
| AMD Athlon              | 6         | 0.14%   |
| Intel Xeon              | 5         | 0.12%   |
| Intel Celeron Dual-Core | 5         | 0.12%   |
| ARM ARMv7               | 5         | 0.12%   |
| AMD C-60                | 5         | 0.12%   |
| Intel Mobile Pentium 4  | 4         | 0.09%   |
| AMD Athlon II           | 4         | 0.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 2397      | 55.97%  |
| 4      | 1257      | 29.35%  |
| 6      | 226       | 5.28%   |
| 1      | 190       | 4.44%   |
| 8      | 166       | 3.88%   |
| 14     | 18        | 0.42%   |
| 12     | 15        | 0.35%   |
| 10     | 13        | 0.3%    |
| 3      | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 4278      | 99.98%  |
| 2      | 1         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 2834      | 66.18%  |
| 1      | 1447      | 33.79%  |
| 4      | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4096      | 95.68%  |
| 32-bit         | 112       | 2.62%   |
| Unknown        | 71        | 1.66%   |
| 64-bit         | 2         | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 915       | 20.9%   |
| 0x1067a    | 394       | 9%      |
| 0x306d4    | 243       | 5.55%   |
| 0x306a9    | 205       | 4.68%   |
| 0x206a7    | 191       | 4.36%   |
| 0x806ec    | 172       | 3.93%   |
| 0x806c1    | 161       | 3.68%   |
| 0x806e9    | 122       | 2.79%   |
| 0x30678    | 116       | 2.65%   |
| 0x806ea    | 115       | 2.63%   |
| 0x40651    | 110       | 2.51%   |
| 0x406e3    | 101       | 2.31%   |
| 0x906ea    | 73        | 1.67%   |
| 0x6f6      | 66        | 1.51%   |
| 0x306c3    | 66        | 1.51%   |
| 0x406c4    | 63        | 1.44%   |
| 0xa0652    | 60        | 1.37%   |
| 0x20655    | 57        | 1.3%    |
| 0x08600106 | 51        | 1.17%   |
| 0x08108109 | 49        | 1.12%   |
| 0x0a50000c | 48        | 1.1%    |
| 0x906eb    | 44        | 1.01%   |
| 0x10676    | 44        | 1.01%   |
| 0x706e5    | 42        | 0.96%   |
| 0x08108102 | 42        | 0.96%   |
| 0x08608103 | 40        | 0.91%   |
| 0x6fd      | 37        | 0.85%   |
| 0x806eb    | 34        | 0.78%   |
| 0x706a8    | 34        | 0.78%   |
| 0x106ca    | 34        | 0.78%   |
| 0x906e9    | 32        | 0.73%   |
| 0x106c2    | 32        | 0.73%   |
| 0x906a3    | 31        | 0.71%   |
| 0x506e3    | 31        | 0.71%   |
| 0x0600611a | 30        | 0.69%   |
| 0x06006705 | 28        | 0.64%   |
| 0x506c9    | 27        | 0.62%   |
| 0x6d8      | 26        | 0.59%   |
| 0x20652    | 24        | 0.55%   |
| 0x406c3    | 22        | 0.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 803       | 18.74%  |
| Penryn           | 472       | 11.02%  |
| IvyBridge        | 279       | 6.51%   |
| Broadwell        | 275       | 6.42%   |
| SandyBridge      | 263       | 6.14%   |
| Haswell          | 240       | 5.6%    |
| Silvermont       | 230       | 5.37%   |
| TigerLake        | 197       | 4.6%    |
| Skylake          | 191       | 4.46%   |
| Core             | 145       | 3.38%   |
| Zen+             | 114       | 2.66%   |
| Westmere         | 111       | 2.59%   |
| Zen 2            | 100       | 2.33%   |
| Unknown          | 91        | 2.12%   |
| CometLake        | 83        | 1.94%   |
| Bonnell          | 83        | 1.94%   |
| Excavator        | 81        | 1.89%   |
| IceLake          | 65        | 1.52%   |
| P6               | 62        | 1.45%   |
| Zen 3            | 61        | 1.42%   |
| Goldmont plus    | 59        | 1.38%   |
| Goldmont         | 36        | 0.84%   |
| Zen              | 34        | 0.79%   |
| Alderlake Hybrid | 34        | 0.79%   |
| Bobcat           | 30        | 0.7%    |
| Puma             | 23        | 0.54%   |
| Jaguar           | 18        | 0.42%   |
| K8 Hammer        | 17        | 0.4%    |
| K10 Llano        | 16        | 0.37%   |
| NetBurst         | 14        | 0.33%   |
| Nehalem          | 13        | 0.3%    |
| Piledriver       | 11        | 0.26%   |
| Tremont          | 10        | 0.23%   |
| K10              | 10        | 0.23%   |
| K8 & K10 hybrid  | 7         | 0.16%   |
| Steamroller      | 6         | 0.14%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3124      | 60.77%  |
| Nvidia                           | 1188      | 23.11%  |
| AMD                              | 815       | 15.85%  |
| Silicon Integrated Systems [SiS] | 7         | 0.14%   |
| Zhaoxin                          | 2         | 0.04%   |
| VIA Technologies                 | 2         | 0.04%   |
| S3 Graphics                      | 2         | 0.04%   |
| Neomagic                         | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia C79 [GeForce 9400M G]                                                             | 306       | 5.69%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 256       | 4.76%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 234       | 4.35%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 180       | 3.35%   |
| Intel UHD Graphics 620                                                                   | 175       | 3.25%   |
| Intel HD Graphics 6000                                                                   | 153       | 2.85%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 143       | 2.66%   |
| Intel HD Graphics 620                                                                    | 142       | 2.64%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 137       | 2.55%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 134       | 2.49%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 133       | 2.47%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 119       | 2.21%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 117       | 2.18%   |
| Intel HD Graphics 5500                                                                   | 110       | 2.05%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 109       | 2.03%   |
| AMD Renoir                                                                               | 99        | 1.84%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 96        | 1.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 95        | 1.77%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 85        | 1.58%   |
| Intel Core Processor Integrated Graphics Controller                                      | 85        | 1.58%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 81        | 1.51%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 76        | 1.41%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 72        | 1.34%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 72        | 1.34%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 65        | 1.21%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 56        | 1.04%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 54        | 1%      |
| AMD Lucienne                                                                             | 47        | 0.87%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 44        | 0.82%   |
| Intel HD Graphics 630                                                                    | 43        | 0.8%    |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 43        | 0.8%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 43        | 0.8%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 42        | 0.78%   |
| Intel HD Graphics 530                                                                    | 39        | 0.73%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 38        | 0.71%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 34        | 0.63%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 33        | 0.61%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 33        | 0.61%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 32        | 0.6%    |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 31        | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 2306      | 53.78%  |
| Intel + Nvidia     | 671       | 15.65%  |
| 1 x AMD            | 570       | 13.29%  |
| 1 x Nvidia         | 459       | 10.7%   |
| Intel + AMD        | 139       | 3.24%   |
| AMD + Nvidia       | 58        | 1.35%   |
| 2 x AMD            | 48        | 1.12%   |
| Other              | 19        | 0.44%   |
| 1 x SiS            | 7         | 0.16%   |
| 1 x Zhaoxin        | 2         | 0.05%   |
| 1 x VIA            | 2         | 0.05%   |
| 1 x S3 Graphics    | 2         | 0.05%   |
| Intel + 2 x Nvidia | 2         | 0.05%   |
| 2 x Nvidia         | 1         | 0.02%   |
| 2 x Intel          | 1         | 0.02%   |
| 1 x Neomagic       | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 3731      | 86.55%  |
| Proprietary | 304       | 7.05%   |
| Unknown     | 276       | 6.4%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 3157      | 72.83%  |
| 0.01-0.5       | 644       | 14.86%  |
| 1.01-2.0       | 235       | 5.42%   |
| 0.51-1.0       | 122       | 2.81%   |
| 3.01-4.0       | 120       | 2.77%   |
| 5.01-6.0       | 26        | 0.6%    |
| 7.01-8.0       | 21        | 0.48%   |
| 2.01-3.0       | 8         | 0.18%   |
| More than 64.0 | 1         | 0.02%   |
| 8.01-16.0      | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 831       | 17.89%  |
| BOE                     | 604       | 13%     |
| Apple                   | 586       | 12.62%  |
| LG Display              | 561       | 12.08%  |
| Chimei Innolux          | 512       | 11.02%  |
| Samsung Electronics     | 372       | 8.01%   |
| Dell                    | 126       | 2.71%   |
| Lenovo                  | 111       | 2.39%   |
| Goldstar                | 96        | 2.07%   |
| Sharp                   | 91        | 1.96%   |
| Chi Mei Optoelectronics | 77        | 1.66%   |
| InfoVision              | 63        | 1.36%   |
| Hewlett-Packard         | 55        | 1.18%   |
| PANDA                   | 45        | 0.97%   |
| BenQ                    | 43        | 0.93%   |
| Philips                 | 40        | 0.86%   |
| AOC                     | 33        | 0.71%   |
| Iiyama                  | 32        | 0.69%   |
| HannStar                | 31        | 0.67%   |
| Ancor Communications    | 30        | 0.65%   |
| LG Philips              | 29        | 0.62%   |
| Acer                    | 28        | 0.6%    |
| CSO                     | 25        | 0.54%   |
| Unknown                 | 22        | 0.47%   |
| ViewSonic               | 18        | 0.39%   |
| Sony                    | 17        | 0.37%   |
| CPT                     | 15        | 0.32%   |
| Eizo                    | 14        | 0.3%    |
| Quanta Display          | 9         | 0.19%   |
| ASUSTek Computer        | 8         | 0.17%   |
| NEC Computers           | 7         | 0.15%   |
| Panasonic               | 6         | 0.13%   |
| Pixio                   | 4         | 0.09%   |
| MSI                     | 4         | 0.09%   |
| LGD                     | 4         | 0.09%   |
| InnoLux Display         | 4         | 0.09%   |
| AGO                     | 4         | 0.09%   |
| Toshiba                 | 3         | 0.06%   |
| TMX                     | 3         | 0.06%   |
| SLD                     | 3         | 0.06%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9C5B 1280x800 286x179mm 13.3-inch                 | 200       | 4.25%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch               | 152       | 3.23%   |
| BOE LCD Monitor BOE0609 1366x768 256x144mm 11.6-inch                 | 52        | 1.11%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch        | 43        | 0.91%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                 | 43        | 0.91%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 41        | 0.87%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                 | 41        | 0.87%   |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                 | 37        | 0.79%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 30        | 0.64%   |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                 | 29        | 0.62%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 27        | 0.57%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                 | 27        | 0.57%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch        | 26        | 0.55%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch      | 24        | 0.51%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 23        | 0.49%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 22        | 0.47%   |
| HannStar HSD100IFW1 HSD03E9 1024x600 220x129mm 10.0-inch             | 22        | 0.47%   |
| Apple Color LCD APP9C5C 1280x800 286x179mm 13.3-inch                 | 21        | 0.45%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 19        | 0.4%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 18        | 0.38%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 16        | 0.34%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 16        | 0.34%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 15        | 0.32%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 15        | 0.32%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                | 15        | 0.32%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 15        | 0.32%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch       | 15        | 0.32%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 15        | 0.32%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 14        | 0.3%    |
| Apple Color LCD APP9C5E 1280x800 286x178mm 13.3-inch                 | 14        | 0.3%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch       | 13        | 0.28%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch        | 13        | 0.28%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch          | 12        | 0.26%   |
| BOE LCD Monitor BOE0718 1920x1080 309x173mm 13.9-inch                | 12        | 0.26%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch       | 12        | 0.26%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch        | 12        | 0.26%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch       | 12        | 0.26%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch     | 11        | 0.23%   |
| BOE LCD Monitor BOE06CF 1366x768 277x156mm 12.5-inch                 | 11        | 0.23%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch        | 11        | 0.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1643      | 37.44%  |
| 1366x768 (WXGA)    | 1235      | 28.14%  |
| 1280x800 (WXGA)    | 514       | 11.71%  |
| 1600x900 (HD+)     | 185       | 4.22%   |
| 1440x900 (WXGA+)   | 132       | 3.01%   |
| 3840x2160 (4K)     | 128       | 2.92%   |
| 2560x1440 (QHD)    | 95        | 2.16%   |
| 1920x1200 (WUXGA)  | 90        | 2.05%   |
| 1024x600           | 65        | 1.48%   |
| 1280x1024 (SXGA)   | 34        | 0.77%   |
| 2560x1600          | 30        | 0.68%   |
| 1680x1050 (WSXGA+) | 28        | 0.64%   |
| 2560x1080          | 25        | 0.57%   |
| 1360x768           | 21        | 0.48%   |
| 2288x1287          | 19        | 0.43%   |
| 1024x768 (XGA)     | 18        | 0.41%   |
| 3840x2400          | 17        | 0.39%   |
| 2880x1800          | 16        | 0.36%   |
| 3440x1440          | 15        | 0.34%   |
| 3200x1800 (QHD+)   | 9         | 0.21%   |
| 2160x1440          | 8         | 0.18%   |
| 1600x1200          | 7         | 0.16%   |
| 3840x1080          | 6         | 0.14%   |
| Unknown            | 6         | 0.14%   |
| 1400x1050          | 5         | 0.11%   |
| 3840x1100          | 3         | 0.07%   |
| 2256x1504          | 3         | 0.07%   |
| 2240x1400          | 3         | 0.07%   |
| 1280x720 (HD)      | 3         | 0.07%   |
| 3840x1200          | 2         | 0.05%   |
| 3072x1920          | 2         | 0.05%   |
| 2880x1920          | 2         | 0.05%   |
| 2304x1440          | 2         | 0.05%   |
| 1920x1280          | 2         | 0.05%   |
| 1024x576           | 2         | 0.05%   |
| 800x1280           | 1         | 0.02%   |
| 7680x2160          | 1         | 0.02%   |
| 640x480            | 1         | 0.02%   |
| 3840x1600          | 1         | 0.02%   |
| 2880x1620          | 1         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1415      | 30.44%  |
| 13      | 1057      | 22.74%  |
| 14      | 586       | 12.61%  |
| 11      | 273       | 5.87%   |
| 17      | 255       | 5.49%   |
| 12      | 176       | 3.79%   |
| 24      | 156       | 3.36%   |
| 27      | 123       | 2.65%   |
| 23      | 116       | 2.5%    |
| 21      | 93        | 2%      |
| 10      | 64        | 1.38%   |
| 18      | 41        | 0.88%   |
| Unknown | 37        | 0.8%    |
| 34      | 34        | 0.73%   |
| 19      | 29        | 0.62%   |
| 16      | 25        | 0.54%   |
| 31      | 22        | 0.47%   |
| 142     | 19        | 0.41%   |
| 22      | 17        | 0.37%   |
| 25      | 15        | 0.32%   |
| 20      | 12        | 0.26%   |
| 72      | 10        | 0.22%   |
| 40      | 10        | 0.22%   |
| 32      | 9         | 0.19%   |
| 8       | 7         | 0.15%   |
| 54      | 6         | 0.13%   |
| 29      | 6         | 0.13%   |
| 84      | 4         | 0.09%   |
| 46      | 4         | 0.09%   |
| 28      | 4         | 0.09%   |
| 52      | 3         | 0.06%   |
| 49      | 3         | 0.06%   |
| 48      | 3         | 0.06%   |
| 43      | 3         | 0.06%   |
| 33      | 2         | 0.04%   |
| 26      | 2         | 0.04%   |
| 58      | 1         | 0.02%   |
| 55      | 1         | 0.02%   |
| 47      | 1         | 0.02%   |
| 41      | 1         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 2327      | 50.51%  |
| 201-300        | 1223      | 26.55%  |
| 501-600        | 374       | 8.12%   |
| 351-400        | 299       | 6.49%   |
| 401-500        | 174       | 3.78%   |
| 601-700        | 50        | 1.09%   |
| 701-800        | 44        | 0.96%   |
| Unknown        | 37        | 0.8%    |
| 1001-1500      | 24        | 0.52%   |
| More than 2000 | 19        | 0.41%   |
| 1501-2000      | 14        | 0.3%    |
| 801-900        | 12        | 0.26%   |
| 101-200        | 8         | 0.17%   |
| 901-1000       | 2         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 3132      | 75.43%  |
| 16/10   | 834       | 20.09%  |
| 21/9    | 37        | 0.89%   |
| 4/3     | 35        | 0.84%   |
| 5/4     | 33        | 0.79%   |
| 3/2     | 26        | 0.63%   |
| Unknown | 20        | 0.48%   |
| 1.00    | 19        | 0.46%   |
| 32/9    | 5         | 0.12%   |
| 2.65    | 4         | 0.1%    |
| 3.40    | 3         | 0.07%   |
| 3.20    | 2         | 0.05%   |
| 3.73    | 1         | 0.02%   |
| 0.62    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1415      | 30.54%  |
| 81-90          | 1363      | 29.41%  |
| 201-250        | 295       | 6.37%   |
| 51-60          | 276       | 5.96%   |
| 71-80          | 274       | 5.91%   |
| 121-130        | 203       | 4.38%   |
| 61-70          | 170       | 3.67%   |
| 301-350        | 124       | 2.68%   |
| 251-300        | 73        | 1.58%   |
| 351-500        | 72        | 1.55%   |
| 151-200        | 65        | 1.4%    |
| 41-50          | 64        | 1.38%   |
| 141-150        | 57        | 1.23%   |
| More than 1000 | 46        | 0.99%   |
| Unknown        | 37        | 0.8%    |
| 131-140        | 32        | 0.69%   |
| 501-1000       | 24        | 0.52%   |
| 91-100         | 20        | 0.43%   |
| 111-120        | 16        | 0.35%   |
| 1-40           | 8         | 0.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1906      | 41.95%  |
| 101-120       | 1533      | 33.74%  |
| 51-100        | 650       | 14.3%   |
| 161-240       | 275       | 6.05%   |
| More than 240 | 87        | 1.91%   |
| 1-50          | 56        | 1.23%   |
| Unknown       | 37        | 0.81%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 3406      | 77.85%  |
| 2     | 633       | 14.47%  |
| 0     | 264       | 6.03%   |
| 3     | 70        | 1.6%    |
| 5     | 1         | 0.02%   |
| 4     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 2133      | 31%     |
| Realtek Semiconductor             | 1867      | 27.13%  |
| Qualcomm Atheros                  | 920       | 13.37%  |
| Broadcom                          | 642       | 9.33%   |
| Nvidia                            | 323       | 4.69%   |
| Broadcom Limited                  | 246       | 3.58%   |
| Marvell Technology Group          | 141       | 2.05%   |
| MediaTek                          | 58        | 0.84%   |
| Ralink                            | 56        | 0.81%   |
| TP-Link                           | 42        | 0.61%   |
| ASIX Electronics                  | 42        | 0.61%   |
| Dell                              | 34        | 0.49%   |
| Lenovo                            | 32        | 0.47%   |
| Sierra Wireless                   | 28        | 0.41%   |
| Samsung Electronics               | 28        | 0.41%   |
| JMicron Technology                | 25        | 0.36%   |
| Ericsson Business Mobile Networks | 23        | 0.33%   |
| Ralink Technology                 | 19        | 0.28%   |
| Qualcomm                          | 19        | 0.28%   |
| DisplayLink                       | 17        | 0.25%   |
| Huawei Technologies               | 15        | 0.22%   |
| Hewlett-Packard                   | 15        | 0.22%   |
| Xiaomi                            | 14        | 0.2%    |
| Fibocom                           | 13        | 0.19%   |
| Silicon Integrated Systems [SiS]  | 11        | 0.16%   |
| Qualcomm Atheros Communications   | 8         | 0.12%   |
| Cypress Semiconductor             | 8         | 0.12%   |
| NetGear                           | 6         | 0.09%   |
| ICS Advent                        | 6         | 0.09%   |
| Attansic Technology               | 6         | 0.09%   |
| ASUSTek Computer                  | 6         | 0.09%   |
| OPPO Electronics                  | 5         | 0.07%   |
| Apple                             | 5         | 0.07%   |
| AMD                               | 5         | 0.07%   |
| Motorola PCS                      | 4         | 0.06%   |
| Microchip Technology              | 4         | 0.06%   |
| Edimax Technology                 | 4         | 0.06%   |
| U-Blox                            | 3         | 0.04%   |
| 3Com                              | 3         | 0.04%   |
| Wilocity                          | 2         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 1135      | 13.87%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 332       | 4.06%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 314       | 3.84%   |
| Nvidia MCP79 Ethernet                                                                 | 313       | 3.82%   |
| Intel Wireless 7260                                                                   | 191       | 2.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 190       | 2.32%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 172       | 2.1%    |
| Intel Wireless 8265 / 8275                                                            | 171       | 2.09%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 168       | 2.05%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 158       | 1.93%   |
| Intel Wi-Fi 6 AX200                                                                   | 157       | 1.92%   |
| Intel Wireless 7265                                                                   | 155       | 1.89%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 140       | 1.71%   |
| Intel Wi-Fi 6 AX201                                                                   | 137       | 1.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 117       | 1.43%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 110       | 1.34%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 108       | 1.32%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 106       | 1.3%    |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 99        | 1.21%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 98        | 1.2%    |
| Intel Wireless 8260                                                                   | 92        | 1.12%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 90        | 1.1%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 89        | 1.09%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 73        | 0.89%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 67        | 0.82%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 66        | 0.81%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 59        | 0.72%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 58        | 0.71%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                               | 58        | 0.71%   |
| Intel Wireless 3165                                                                   | 55        | 0.67%   |
| Intel Ethernet Connection I218-LM                                                     | 55        | 0.67%   |
| Intel Ethernet Connection (4) I219-LM                                                 | 55        | 0.67%   |
| Intel Ethernet Connection (4) I219-V                                                  | 53        | 0.65%   |
| Intel Ethernet Connection I219-LM                                                     | 50        | 0.61%   |
| Intel Ethernet Connection (3) I218-LM                                                 | 50        | 0.61%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 46        | 0.56%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 43        | 0.53%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 43        | 0.53%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                      | 43        | 0.53%   |
| Intel 82577LM Gigabit Network Connection                                              | 41        | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2014      | 46.1%   |
| Qualcomm Atheros                      | 821       | 18.79%  |
| Broadcom                              | 545       | 12.47%  |
| Realtek Semiconductor                 | 513       | 11.74%  |
| Broadcom Limited                      | 210       | 4.81%   |
| Ralink                                | 56        | 1.28%   |
| MediaTek                              | 56        | 1.28%   |
| Sierra Wireless                       | 28        | 0.64%   |
| TP-Link                               | 24        | 0.55%   |
| Ralink Technology                     | 19        | 0.43%   |
| Dell                                  | 19        | 0.43%   |
| Fibocom                               | 12        | 0.27%   |
| Qualcomm Atheros Communications       | 8         | 0.18%   |
| Qualcomm                              | 8         | 0.18%   |
| NetGear                               | 6         | 0.14%   |
| ASUSTek Computer                      | 6         | 0.14%   |
| Edimax Technology                     | 4         | 0.09%   |
| Hewlett-Packard                       | 3         | 0.07%   |
| Ericsson Business Mobile Networks     | 3         | 0.07%   |
| Wilocity                              | 2         | 0.05%   |
| D-Link System                         | 2         | 0.05%   |
| Belkin Components                     | 2         | 0.05%   |
| 3Com                                  | 2         | 0.05%   |
| ZyXEL Communications                  | 1         | 0.02%   |
| Z-Com                                 | 1         | 0.02%   |
| Quectel Wireless Solutions            | 1         | 0.02%   |
| Microsoft                             | 1         | 0.02%   |
| Cinterion                             | 1         | 0.02%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 314       | 7.15%   |
| Intel Wireless 7260                                                                   | 191       | 4.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 190       | 4.33%   |
| Intel Wireless 8265 / 8275                                                            | 171       | 3.9%    |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 158       | 3.6%    |
| Intel Wi-Fi 6 AX200                                                                   | 157       | 3.58%   |
| Intel Wireless 7265                                                                   | 155       | 3.53%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 140       | 3.19%   |
| Intel Wi-Fi 6 AX201                                                                   | 137       | 3.12%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 117       | 2.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 110       | 2.51%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 108       | 2.46%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 106       | 2.41%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 99        | 2.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 98        | 2.23%   |
| Intel Wireless 8260                                                                   | 92        | 2.1%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 90        | 2.05%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 89        | 2.03%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 73        | 1.66%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 67        | 1.53%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 66        | 1.5%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 59        | 1.34%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 58        | 1.32%   |
| Intel Wireless 3165                                                                   | 55        | 1.25%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 46        | 1.05%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 43        | 0.98%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 43        | 0.98%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                      | 43        | 0.98%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 41        | 0.93%   |
| Intel Wireless-AC 9260                                                                | 40        | 0.91%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 38        | 0.87%   |
| Intel Centrino Ultimate-N 6300                                                        | 38        | 0.87%   |
| Intel Wireless 3160                                                                   | 36        | 0.82%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 35        | 0.8%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 32        | 0.73%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                              | 31        | 0.71%   |
| Intel Centrino Advanced-N 6200                                                        | 31        | 0.71%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 30        | 0.68%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 30        | 0.68%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 29        | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1676      | 46.07%  |
| Intel                            | 861       | 23.67%  |
| Nvidia                           | 323       | 8.88%   |
| Qualcomm Atheros                 | 202       | 5.55%   |
| Marvell Technology Group         | 141       | 3.88%   |
| Broadcom                         | 128       | 3.52%   |
| ASIX Electronics                 | 42        | 1.15%   |
| Broadcom Limited                 | 39        | 1.07%   |
| Lenovo                           | 32        | 0.88%   |
| Samsung Electronics              | 28        | 0.77%   |
| JMicron Technology               | 25        | 0.69%   |
| TP-Link                          | 18        | 0.49%   |
| DisplayLink                      | 17        | 0.47%   |
| Xiaomi                           | 14        | 0.38%   |
| Silicon Integrated Systems [SiS] | 11        | 0.3%    |
| Qualcomm                         | 10        | 0.27%   |
| Huawei Technologies              | 10        | 0.27%   |
| Cypress Semiconductor            | 8         | 0.22%   |
| ICS Advent                       | 6         | 0.16%   |
| Attansic Technology              | 6         | 0.16%   |
| OPPO Electronics                 | 5         | 0.14%   |
| Apple                            | 5         | 0.14%   |
| Microchip Technology             | 4         | 0.11%   |
| Hewlett-Packard                  | 4         | 0.11%   |
| Motorola PCS                     | 3         | 0.08%   |
| Spreadtrum Communications        | 2         | 0.05%   |
| National Semiconductor           | 2         | 0.05%   |
| MediaTek                         | 2         | 0.05%   |
| LG Electronics                   | 2         | 0.05%   |
| D-Link                           | 2         | 0.05%   |
| VIA Technologies                 | 1         | 0.03%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.03%   |
| MosChip Semiconductor            | 1         | 0.03%   |
| Linksys                          | 1         | 0.03%   |
| HTC (High Tech Computer)         | 1         | 0.03%   |
| Google                           | 1         | 0.03%   |
| Foxconn / Hon Hai                | 1         | 0.03%   |
| Digitech Systems                 | 1         | 0.03%   |
| Davicom Semiconductor            | 1         | 0.03%   |
| 3Com                             | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1135      | 30.88%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 332       | 9.03%   |
| Nvidia MCP79 Ethernet                                             | 313       | 8.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 172       | 4.68%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 168       | 4.57%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 58        | 1.58%   |
| Intel Ethernet Connection I218-LM                                 | 55        | 1.5%    |
| Intel Ethernet Connection (4) I219-LM                             | 55        | 1.5%    |
| Intel Ethernet Connection (4) I219-V                              | 53        | 1.44%   |
| Intel Ethernet Connection I219-LM                                 | 50        | 1.36%   |
| Intel Ethernet Connection (3) I218-LM                             | 50        | 1.36%   |
| Intel 82577LM Gigabit Network Connection                          | 41        | 1.12%   |
| Intel Ethernet Connection (6) I219-V                              | 39        | 1.06%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 36        | 0.98%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 35        | 0.95%   |
| Intel 82567LM Gigabit Network Connection                          | 33        | 0.9%    |
| ASIX AX88179 Gigabit Ethernet                                     | 33        | 0.9%    |
| Intel Ethernet Connection I219-V                                  | 29        | 0.79%   |
| Intel Ethernet Connection (10) I219-V                             | 26        | 0.71%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 25        | 0.68%   |
| Intel Ethernet Connection (13) I219-V                             | 25        | 0.68%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 24        | 0.65%   |
| Intel Ethernet Connection I217-LM                                 | 23        | 0.63%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 22        | 0.6%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 20        | 0.54%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 19        | 0.52%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 18        | 0.49%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 17        | 0.46%   |
| Intel 82579V Gigabit Network Connection                           | 17        | 0.46%   |
| Intel Ethernet Connection (7) I219-LM                             | 16        | 0.44%   |
| Intel Ethernet Connection (6) I219-LM                             | 16        | 0.44%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 15        | 0.41%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 15        | 0.41%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 14        | 0.38%   |
| Intel 82566MM Gigabit Network Connection                          | 14        | 0.38%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 13        | 0.35%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 13        | 0.35%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 13        | 0.35%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 13        | 0.35%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 12        | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 4199      | 53.85%  |
| Ethernet | 3479      | 44.62%  |
| Modem    | 111       | 1.42%   |
| Unknown  | 8         | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3283      | 72.65%  |
| Ethernet | 1236      | 27.35%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 3153      | 73.53%  |
| 1     | 1025      | 23.9%   |
| 0     | 68        | 1.59%   |
| 3     | 40        | 0.93%   |
| 5     | 1         | 0.02%   |
| 4     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3683      | 84.96%  |
| Yes  | 652       | 15.04%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1510      | 43.54%  |
| Apple                           | 576       | 16.61%  |
| Qualcomm Atheros Communications | 314       | 9.05%   |
| Realtek Semiconductor           | 294       | 8.48%   |
| Broadcom                        | 173       | 4.99%   |
| IMC Networks                    | 128       | 3.69%   |
| Lite-On Technology              | 126       | 3.63%   |
| Foxconn / Hon Hai               | 84        | 2.42%   |
| Dell                            | 58        | 1.67%   |
| Hewlett-Packard                 | 41        | 1.18%   |
| Cambridge Silicon Radio         | 40        | 1.15%   |
| ASUSTek Computer                | 25        | 0.72%   |
| Toshiba                         | 22        | 0.63%   |
| Realtek                         | 22        | 0.63%   |
| Ralink                          | 19        | 0.55%   |
| Foxconn International           | 9         | 0.26%   |
| Alps Electric                   | 6         | 0.17%   |
| Ralink Technology               | 5         | 0.14%   |
| Taiyo Yuden                     | 3         | 0.09%   |
| MediaTek                        | 3         | 0.09%   |
| Unknown                         | 2         | 0.06%   |
| Fujitsu                         | 2         | 0.06%   |
| USI                             | 1         | 0.03%   |
| Qcom                            | 1         | 0.03%   |
| Opticis                         | 1         | 0.03%   |
| Edimax Technology               | 1         | 0.03%   |
| Chicony Electronics             | 1         | 0.03%   |
| Askey Computer                  | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 655       | 18.87%  |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 303       | 8.73%   |
| Intel Bluetooth Device                              | 302       | 8.7%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 249       | 7.17%   |
| Realtek Bluetooth Radio                             | 179       | 5.16%   |
| Qualcomm Atheros  Bluetooth Device                  | 179       | 5.16%   |
| Apple Bluetooth USB Host Controller                 | 157       | 4.52%   |
| Intel AX200 Bluetooth                               | 149       | 4.29%   |
| Lite-On Bluetooth Device                            | 80        | 2.3%    |
| Realtek  Bluetooth 4.2 Adapter                      | 76        | 2.19%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 76        | 2.19%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 43        | 1.24%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 41        | 1.18%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 40        | 1.15%   |
| IMC Networks Bluetooth Radio                        | 39        | 1.12%   |
| Broadcom BCM2045B (BDC-2.1)                         | 38        | 1.09%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 35        | 1.01%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 34        | 0.98%   |
| IMC Networks Bluetooth Device                       | 33        | 0.95%   |
| Apple Bluetooth Host Controller                     | 33        | 0.95%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 30        | 0.86%   |
| Foxconn / Hon Hai Bluetooth Device                  | 30        | 0.86%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 29        | 0.84%   |
| Intel Wireless-AC 3168 Bluetooth                    | 29        | 0.84%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 29        | 0.84%   |
| Realtek Bluetooth Radio                             | 22        | 0.63%   |
| Intel AX210 Bluetooth                               | 22        | 0.63%   |
| Dell DW375 Bluetooth Module                         | 21        | 0.61%   |
| IMC Networks Wireless_Device                        | 20        | 0.58%   |
| Ralink RT3290 Bluetooth                             | 19        | 0.55%   |
| Foxconn / Hon Hai Wireless_Device                   | 19        | 0.55%   |
| HP Broadcom 2070 Bluetooth Combo                    | 18        | 0.52%   |
| Lite-On Atheros AR3012 Bluetooth                    | 17        | 0.49%   |
| Realtek RTL8723B Bluetooth                          | 16        | 0.46%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 16        | 0.46%   |
| Dell BCM20702A0 Bluetooth Module                    | 15        | 0.43%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 13        | 0.37%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 13        | 0.37%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 12        | 0.35%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 11        | 0.32%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 3299      | 66.49%  |
| Nvidia                                       | 720       | 14.51%  |
| AMD                                          | 649       | 13.08%  |
| C-Media Electronics                          | 35        | 0.71%   |
| Logitech                                     | 28        | 0.56%   |
| Lenovo                                       | 26        | 0.52%   |
| Realtek Semiconductor                        | 25        | 0.5%    |
| Texas Instruments                            | 17        | 0.34%   |
| Plantronics                                  | 15        | 0.3%    |
| GN Netcom                                    | 14        | 0.28%   |
| Silicon Integrated Systems [SiS]             | 12        | 0.24%   |
| Hewlett-Packard                              | 12        | 0.24%   |
| Generalplus Technology                       | 9         | 0.18%   |
| Creative Technology                          | 6         | 0.12%   |
| ASUSTek Computer                             | 6         | 0.12%   |
| Focusrite-Novation                           | 5         | 0.1%    |
| RODE Microphones                             | 4         | 0.08%   |
| Kingston Technology                          | 4         | 0.08%   |
| JMTek                                        | 4         | 0.08%   |
| Dell                                         | 4         | 0.08%   |
| Sennheiser Communications                    | 3         | 0.06%   |
| Razer USA                                    | 3         | 0.06%   |
| Microsoft                                    | 3         | 0.06%   |
| BEHRINGER International                      | 3         | 0.06%   |
| Zhaoxin                                      | 2         | 0.04%   |
| XMOS                                         | 2         | 0.04%   |
| VIA Technologies                             | 2         | 0.04%   |
| ULi Electronics                              | 2         | 0.04%   |
| SAVITECH                                     | 2         | 0.04%   |
| M-Audio                                      | 2         | 0.04%   |
| ESS Technology                               | 2         | 0.04%   |
| Conexant Systems                             | 2         | 0.04%   |
| CMX Systems                                  | 2         | 0.04%   |
| Blue Microphones                             | 2         | 0.04%   |
| Apple                                        | 2         | 0.04%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.02%   |
| Yamaha                                       | 1         | 0.02%   |
| Veho                                         | 1         | 0.02%   |
| Trust                                        | 1         | 0.02%   |
| Toshiba                                      | 1         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 494       | 8.26%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 353       | 5.9%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 328       | 5.48%   |
| Nvidia MCP79 High Definition Audio                                                                | 315       | 5.27%   |
| Intel Broadwell-U Audio Controller                                                                | 275       | 4.6%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 271       | 4.53%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 213       | 3.56%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 195       | 3.26%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 174       | 2.91%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 165       | 2.76%   |
| Intel Cannon Lake PCH cAVS                                                                        | 151       | 2.52%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 145       | 2.42%   |
| Intel 8 Series HD Audio Controller                                                                | 145       | 2.42%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 144       | 2.41%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 138       | 2.31%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 129       | 2.16%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 123       | 2.06%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 122       | 2.04%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 111       | 1.86%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 94        | 1.57%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 91        | 1.52%   |
| AMD FCH Azalia Controller                                                                         | 87        | 1.45%   |
| AMD Kabini HDMI/DP Audio                                                                          | 84        | 1.4%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 82        | 1.37%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 78        | 1.3%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 78        | 1.3%    |
| Intel Comet Lake PCH cAVS                                                                         | 75        | 1.25%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 59        | 0.99%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 57        | 0.95%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 48        | 0.8%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 47        | 0.79%   |
| Intel CM238 HD Audio Controller                                                                   | 47        | 0.79%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 45        | 0.75%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 42        | 0.7%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 40        | 0.67%   |
| AMD High Definition Audio Controller                                                              | 38        | 0.64%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 36        | 0.6%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 36        | 0.6%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 31        | 0.52%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 28        | 0.47%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 1170      | 28.66%  |
| Samsung Electronics | 1087      | 26.63%  |
| Micron Technology   | 420       | 10.29%  |
| Kingston            | 279       | 6.83%   |
| Unknown             | 272       | 6.66%   |
| Crucial             | 205       | 5.02%   |
| Elpida              | 120       | 2.94%   |
| A-DATA Technology   | 84        | 2.06%   |
| Ramaxel Technology  | 73        | 1.79%   |
| Nanya Technology    | 46        | 1.13%   |
| Corsair             | 39        | 0.96%   |
| Unknown             | 37        | 0.91%   |
| Unknown (ABCD)      | 32        | 0.78%   |
| Smart               | 32        | 0.78%   |
| GOODRAM             | 21        | 0.51%   |
| G.Skill             | 18        | 0.44%   |
| Transcend           | 17        | 0.42%   |
| Team                | 16        | 0.39%   |
| Teikon              | 10        | 0.24%   |
| Patriot             | 7         | 0.17%   |
| Apacer              | 7         | 0.17%   |
| 48spaces            | 7         | 0.17%   |
| Smart Brazil        | 6         | 0.15%   |
| Silicon Power       | 6         | 0.15%   |
| ASint Technology    | 5         | 0.12%   |
| Qimonda             | 4         | 0.1%    |
| PNY                 | 4         | 0.1%    |
| AMD                 | 4         | 0.1%    |
| Wilk                | 3         | 0.07%   |
| Neo Forza           | 3         | 0.07%   |
| Goldkey             | 3         | 0.07%   |
| Avant               | 3         | 0.07%   |
| Unknown (89F7)      | 2         | 0.05%   |
| Unifosa             | 2         | 0.05%   |
| TEXTORM             | 2         | 0.05%   |
| Shenzhen WODPOSIT   | 2         | 0.05%   |
| PUSKILL             | 2         | 0.05%   |
| Kllisre             | 2         | 0.05%   |
| Infineon            | 2         | 0.05%   |
| High Bridge         | 2         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM Module 1GB SODIMM DDR2 800MT/s                      | 257       | 5.99%   |
| SK hynix RAM Module 1GB SODIMM DDR2 667MT/s                      | 68        | 1.58%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s            | 66        | 1.54%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                      | 63        | 1.47%   |
| Crucial RAM CT8G4SFRA266.C8FD1 8GB SODIMM DDR4 2667MT/s          | 44        | 1.03%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 42        | 0.98%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 41        | 0.96%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                       | 38        | 0.89%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 37        | 0.86%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 37        | 0.86%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 37        | 0.86%   |
| Unknown                                                          | 37        | 0.86%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 34        | 0.79%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 33        | 0.77%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 33        | 0.77%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 29        | 0.68%   |
| Samsung RAM Module 1GB SODIMM DDR2 800MT/s                       | 29        | 0.68%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 28        | 0.65%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 28        | 0.65%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 28        | 0.65%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 27        | 0.63%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 25        | 0.58%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 25        | 0.58%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 25        | 0.58%   |
| Crucial RAM CT8G4SFS824A.M8FE 8GB SODIMM DDR4 2667MT/s           | 25        | 0.58%   |
| SK hynix RAM Module 2GB SODIMM DDR2 800MT/s                      | 24        | 0.56%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 24        | 0.56%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 23        | 0.54%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 23        | 0.54%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 22        | 0.51%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 21        | 0.49%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 21        | 0.49%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 21        | 0.49%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 20        | 0.47%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 20        | 0.47%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 20        | 0.47%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 19        | 0.44%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 18        | 0.42%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 18        | 0.42%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 17        | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 1386      | 39.1%   |
| DDR3    | 1206      | 34.02%  |
| DDR2    | 533       | 15.04%  |
| LPDDR4  | 124       | 3.5%    |
| LPDDR3  | 122       | 3.44%   |
| SDRAM   | 80        | 2.26%   |
| DDR     | 39        | 1.1%    |
| Unknown | 19        | 0.54%   |
| LPDDR5  | 13        | 0.37%   |
| DDR5    | 13        | 0.37%   |
| DRAM    | 9         | 0.25%   |
| RAM     | 1         | 0.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 3234      | 91.05%  |
| Row Of Chips | 226       | 6.36%   |
| Unknown      | 53        | 1.49%   |
| Chip         | 29        | 0.82%   |
| DIMM         | 10        | 0.28%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 1162      | 30.26%  |
| 4096  | 1036      | 26.98%  |
| 2048  | 586       | 15.26%  |
| 1024  | 523       | 13.62%  |
| 16384 | 398       | 10.36%  |
| 32768 | 76        | 1.98%   |
| 512   | 41        | 1.07%   |
| 256   | 16        | 0.42%   |
| 128   | 2         | 0.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 915       | 24.1%   |
| 2667    | 674       | 17.76%  |
| 3200    | 527       | 13.88%  |
| 800     | 332       | 8.75%   |
| 2400    | 235       | 6.19%   |
| 667     | 171       | 4.5%    |
| 2133    | 161       | 4.24%   |
| 1334    | 158       | 4.16%   |
| 1333    | 128       | 3.37%   |
| Unknown | 98        | 2.58%   |
| 1067    | 52        | 1.37%   |
| 4267    | 49        | 1.29%   |
| 1867    | 43        | 1.13%   |
| 3266    | 37        | 0.97%   |
| 4199    | 28        | 0.74%   |
| 533     | 21        | 0.55%   |
| 1066    | 20        | 0.53%   |
| 975     | 19        | 0.5%    |
| 2048    | 18        | 0.47%   |
| 8400    | 15        | 0.4%    |
| 4800    | 15        | 0.4%    |
| 6400    | 13        | 0.34%   |
| 400     | 11        | 0.29%   |
| 4266    | 10        | 0.26%   |
| 333     | 9         | 0.24%   |
| 266     | 8         | 0.21%   |
| 1866    | 7         | 0.18%   |
| 3733    | 4         | 0.11%   |
| 2933    | 3         | 0.08%   |
| 933     | 3         | 0.08%   |
| 2666    | 2         | 0.05%   |
| 1776    | 2         | 0.05%   |
| 1639    | 2         | 0.05%   |
| 3000    | 1         | 0.03%   |
| 2134    | 1         | 0.03%   |
| 1596    | 1         | 0.03%   |
| 200     | 1         | 0.03%   |
| 133     | 1         | 0.03%   |
| 100     | 1         | 0.03%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 10        | 37.04%  |
| Xerox               | 4         | 14.81%  |
| Canon               | 3         | 11.11%  |
| Brother Industries  | 3         | 11.11%  |
| Samsung Electronics | 2         | 7.41%   |
| Kyocera             | 2         | 7.41%   |
| Xiaomi              | 1         | 3.7%    |
| STMicroelectronics  | 1         | 3.7%    |
| Pantum              | 1         | 3.7%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Xerox B205                                                | 4         | 14.29%  |
| Xiaomi MiMouse 2                                          | 1         | 3.57%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 3.57%   |
| Samsung ML-2010P Mono Laser Printer                       | 1         | 3.57%   |
| Samsung CLX-3300 Series                                   | 1         | 3.57%   |
| Pantum P2500W series                                      | 1         | 3.57%   |
| Kyocera FS-1120MFP                                        | 1         | 3.57%   |
| Kyocera ECOSYS P2335d                                     | 1         | 3.57%   |
| HP OfficeJet 3830 series                                  | 1         | 3.57%   |
| HP LaserJet P1102                                         | 1         | 3.57%   |
| HP LaserJet 1200                                          | 1         | 3.57%   |
| HP LaserJet 1160 series                                   | 1         | 3.57%   |
| HP LaserJet 1022                                          | 1         | 3.57%   |
| HP LaserJet 1020                                          | 1         | 3.57%   |
| HP Ink Tank 110 series                                    | 1         | 3.57%   |
| HP EWS UPD                                                | 1         | 3.57%   |
| HP DeskJet 2600 series                                    | 1         | 3.57%   |
| HP Deskjet 2540 series                                    | 1         | 3.57%   |
| HP DeskJet 2130 series                                    | 1         | 3.57%   |
| Canon PIXMA MX920 Series                                  | 1         | 3.57%   |
| Canon LBP3010/LBP3018/LBP3050                             | 1         | 3.57%   |
| Canon G3010 series                                        | 1         | 3.57%   |
| Brother PT-9500PC                                         | 1         | 3.57%   |
| Brother MFC-L2707DW                                       | 1         | 3.57%   |
| Brother HL-L2340D series                                  | 1         | 3.57%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 5         | 45.45%  |
| Seiko Epson     | 4         | 36.36%  |
| Mustek Systems  | 1         | 9.09%   |
| Hewlett-Packard | 1         | 9.09%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 120                           | 2         | 18.18%  |
| Seiko Epson GT-9800F [Perfection 3200]            | 1         | 9.09%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]     | 1         | 9.09%   |
| Seiko Epson GT-7700U [Perfection 1240U]           | 1         | 9.09%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO] | 1         | 9.09%   |
| Mustek Systems SNAPSCAN e22                       | 1         | 9.09%   |
| HP Scanjet 200                                    | 1         | 9.09%   |
| Canon CanoScan LIDE 25                            | 1         | 9.09%   |
| Canon CanoScan LiDE 220                           | 1         | 9.09%   |
| Canon CanoScan LiDE 110                           | 1         | 9.09%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 795       | 24.05%  |
| IMC Networks                           | 382       | 11.55%  |
| Acer                                   | 318       | 9.62%   |
| Realtek Semiconductor                  | 281       | 8.5%    |
| Microdia                               | 276       | 8.35%   |
| Quanta                                 | 245       | 7.41%   |
| Sunplus Innovation Technology          | 173       | 5.23%   |
| Suyin                                  | 108       | 3.27%   |
| Cheng Uei Precision Industry (Foxlink) | 101       | 3.06%   |
| Lite-On Technology                     | 82        | 2.48%   |
| Syntek                                 | 72        | 2.18%   |
| Luxvisions Innotech Limited            | 61        | 1.85%   |
| Apple                                  | 50        | 1.51%   |
| Logitech                               | 47        | 1.42%   |
| Silicon Motion                         | 46        | 1.39%   |
| Alcor Micro                            | 38        | 1.15%   |
| Ricoh                                  | 30        | 0.91%   |
| Lenovo                                 | 29        | 0.88%   |
| Z-Star Microelectronics                | 18        | 0.54%   |
| Primax Electronics                     | 17        | 0.51%   |
| Samsung Electronics                    | 14        | 0.42%   |
| Sonix Technology                       | 13        | 0.39%   |
| ALi                                    | 10        | 0.3%    |
| Importek                               | 9         | 0.27%   |
| Genesys Logic                          | 8         | 0.24%   |
| icSpring                               | 7         | 0.21%   |
| SunplusIT                              | 6         | 0.18%   |
| Intel                                  | 5         | 0.15%   |
| OmniVision Technologies                | 4         | 0.12%   |
| Y Media                                | 3         | 0.09%   |
| Sunplus Technology                     | 3         | 0.09%   |
| Pixart Imaging                         | 3         | 0.09%   |
| Microsoft                              | 3         | 0.09%   |
| MacroSilicon                           | 3         | 0.09%   |
| GEMBIRD                                | 3         | 0.09%   |
| ARC International                      | 3         | 0.09%   |
| Unknown                                | 2         | 0.06%   |
| Tobii Technology AB                    | 2         | 0.06%   |
| Mimaki Engineering                     | 2         | 0.06%   |
| Generalplus Technology                 | 2         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 220       | 6.61%   |
| IMC Networks Integrated Camera                      | 129       | 3.88%   |
| Microdia Integrated_Webcam_HD                       | 128       | 3.85%   |
| Realtek Integrated_Webcam_HD                        | 104       | 3.13%   |
| Acer Integrated Camera                              | 85        | 2.55%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 83        | 2.49%   |
| Chicony HD WebCam                                   | 74        | 2.22%   |
| Quanta Chromebook HD Camera                         | 68        | 2.04%   |
| Sunplus Integrated_Webcam_HD                        | 61        | 1.83%   |
| Acer BisonCam, NB Pro                               | 59        | 1.77%   |
| Chicony HP HD Camera                                | 43        | 1.29%   |
| Chicony USB2.0 HD UVC WebCam                        | 40        | 1.2%    |
| Syntek Integrated Camera                            | 38        | 1.14%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 35        | 1.05%   |
| Quanta HP TrueVision HD Camera                      | 34        | 1.02%   |
| Lite-On Integrated Camera                           | 33        | 0.99%   |
| Acer Lenovo EasyCamera                              | 33        | 0.99%   |
| Microdia Integrated Webcam                          | 32        | 0.96%   |
| Acer SunplusIT Integrated Camera                    | 29        | 0.87%   |
| Quanta HD User Facing                               | 25        | 0.75%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 25        | 0.75%   |
| Realtek USB Camera                                  | 24        | 0.72%   |
| Chicony Integrated Camera (1280x720@30)             | 24        | 0.72%   |
| Quanta VGA WebCam                                   | 23        | 0.69%   |
| Quanta HP HD Camera                                 | 23        | 0.69%   |
| Chicony HP TrueVision HD Camera                     | 23        | 0.69%   |
| Sunplus HD WebCam                                   | 21        | 0.63%   |
| Chicony HD User Facing                              | 21        | 0.63%   |
| Chicony EasyCamera                                  | 21        | 0.63%   |
| Lite-On HP HD Camera                                | 20        | 0.6%    |
| Realtek USB2.0 HD UVC WebCam                        | 19        | 0.57%   |
| Realtek Integrated Webcam                           | 19        | 0.57%   |
| Chicony USB2.0 Camera                               | 19        | 0.57%   |
| Chicony HP TrueVision HD                            | 19        | 0.57%   |
| Chicony Lenovo EasyCamera                           | 18        | 0.54%   |
| Apple iPhone 5/5C/5S/6/SE                           | 18        | 0.54%   |
| Suyin HP TrueVision HD                              | 17        | 0.51%   |
| Acer HD Webcam                                      | 17        | 0.51%   |
| Quanta HD Webcam                                    | 16        | 0.48%   |
| Luxvisions Innotech Limited HP HD Camera            | 16        | 0.48%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 234       | 33.1%   |
| Synaptics                          | 216       | 30.55%  |
| Shenzhen Goodix Technology         | 96        | 13.58%  |
| AuthenTec                          | 44        | 6.22%   |
| Upek                               | 42        | 5.94%   |
| Elan Microelectronics              | 34        | 4.81%   |
| LighTuning Technology              | 22        | 3.11%   |
| STMicroelectronics                 | 15        | 2.12%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.28%   |
| Samsung Electronics                | 1         | 0.14%   |
| Microsoft                          | 1         | 0.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 100       | 14.14%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 55        | 7.78%   |
| Shenzhen Goodix  Fingerprint Device                                        | 55        | 7.78%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 46        | 6.51%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 43        | 6.08%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 38        | 5.37%   |
| Unknown                                                                    | 34        | 4.81%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 28        | 3.96%   |
| Shenzhen Goodix Fingerprint Reader                                         | 23        | 3.25%   |
| Elan ELAN:Fingerprint                                                      | 21        | 2.97%   |
| Shenzhen Goodix FingerPrint                                                | 18        | 2.55%   |
| AuthenTec AES2810                                                          | 18        | 2.55%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 16        | 2.26%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 15        | 2.12%   |
| Validity Sensors Synaptics WBDI                                            | 14        | 1.98%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 14        | 1.98%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 14        | 1.98%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 13        | 1.84%   |
| STMicroelectronics Fingerprint Reader                                      | 13        | 1.84%   |
| Elan ELAN:ARM-M4                                                           | 13        | 1.84%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 12        | 1.7%    |
| Validity Sensors VFS491                                                    | 11        | 1.56%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 10        | 1.41%   |
| Validity Sensors VFS Fingerprint sensor                                    | 9         | 1.27%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 9         | 1.27%   |
| Synaptics  WBDI                                                            | 9         | 1.27%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 8         | 1.13%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 6         | 0.85%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 0.71%   |
| Validity Sensors Fingerprint scanner                                       | 5         | 0.71%   |
| Upek TCS5B Fingerprint sensor                                              | 4         | 0.57%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 0.57%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 4         | 0.57%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 0.42%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.28%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.28%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 0.28%   |
| STMicroelectronics TouchChipÂ Fingerprint Reader                          | 2         | 0.28%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 2         | 0.28%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.28%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 134       | 37.54%  |
| Alcor Micro               | 131       | 36.69%  |
| Upek                      | 26        | 7.28%   |
| Lenovo                    | 26        | 7.28%   |
| O2 Micro                  | 24        | 6.72%   |
| Gemalto (was Gemplus)     | 4         | 1.12%   |
| Clay Logic                | 3         | 0.84%   |
| Yubico.com                | 2         | 0.56%   |
| Aladdin Knowledge Systems | 2         | 0.56%   |
| SCM Microsystems          | 1         | 0.28%   |
| OmniKey                   | 1         | 0.28%   |
| Cherry                    | 1         | 0.28%   |
| C3PO                      | 1         | 0.28%   |
| Advanced Card Systems     | 1         | 0.28%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 129       | 36.13%  |
| Broadcom BCM5880 Secure Applications Processor                               | 44        | 12.32%  |
| Broadcom 5880                                                                | 34        | 9.52%   |
| Broadcom 58200                                                               | 34        | 9.52%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 26        | 7.28%   |
| Lenovo Integrated Smart Card Reader                                          | 26        | 7.28%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 21        | 5.88%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 20        | 5.6%    |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 0.84%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 0.56%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 0.56%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 0.56%   |
| Clay Logic Nitrokey Start                                                    | 2         | 0.56%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.56%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 0.56%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 0.56%   |
| SCM Microsystems uTrust FIDO2 Security Key                                   | 1         | 0.28%   |
| OmniKey CardMan 4321                                                         | 1         | 0.28%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.28%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.28%   |
| C3PO LTC31v2                                                                 | 1         | 0.28%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.28%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 2526      | 57.87%  |
| 1     | 1381      | 31.64%  |
| 2     | 359       | 8.22%   |
| 3     | 83        | 1.9%    |
| 4     | 10        | 0.23%   |
| 5     | 5         | 0.11%   |
| 6     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 703       | 30.65%  |
| Graphics card            | 570       | 24.85%  |
| Chipcard                 | 326       | 14.21%  |
| Multimedia controller    | 234       | 10.2%   |
| Net/wireless             | 199       | 8.67%   |
| Bluetooth                | 57        | 2.48%   |
| Camera                   | 45        | 1.96%   |
| Card reader              | 38        | 1.66%   |
| Storage                  | 34        | 1.48%   |
| Communication controller | 31        | 1.35%   |
| Sound                    | 16        | 0.7%    |
| Net/ethernet             | 15        | 0.65%   |
| Network                  | 8         | 0.35%   |
| Modem                    | 6         | 0.26%   |
| Flash memory             | 5         | 0.22%   |
| Unassigned class         | 2         | 0.09%   |
| Firewire controller      | 2         | 0.09%   |
| Wireless                 | 1         | 0.04%   |
| Tv card                  | 1         | 0.04%   |
| Storage/ide              | 1         | 0.04%   |

