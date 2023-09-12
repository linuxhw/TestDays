Linux in Germany - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Germany.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Germany/Desktop/README.md) and [notebooks](/Location/Germany/Notebook/README.md).

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

Total: 31169

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad P15v Gen 2i 21A... | Notebook    | [69fc5aab82](https://linux-hardware.org/?probe=69fc5aab82) | Sep 07, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | Notebook    | [384d2074ad](https://linux-hardware.org/?probe=384d2074ad) | Sep 07, 2023 |
| Lenovo        | IdeaPad Y580 2099           | Notebook    | [d0db961274](https://linux-hardware.org/?probe=d0db961274) | Sep 07, 2023 |
| Sony          | SVF1521V6EB                 | Notebook    | [1d08716b2c](https://linux-hardware.org/?probe=1d08716b2c) | Sep 07, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21BT... | Notebook    | [79ddc77f63](https://linux-hardware.org/?probe=79ddc77f63) | Sep 07, 2023 |
| ASRock        | A68M-ITX                    | Desktop     | [f995094d6b](https://linux-hardware.org/?probe=f995094d6b) | Sep 07, 2023 |
| Dell          | Latitude E5450              | Notebook    | [1478760d8c](https://linux-hardware.org/?probe=1478760d8c) | Sep 06, 2023 |
| Unknown       | Unknown                     | Soc         | [c002635827](https://linux-hardware.org/?probe=c002635827) | Sep 06, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [00e5bebc6a](https://linux-hardware.org/?probe=00e5bebc6a) | Sep 06, 2023 |
| Fujitsu       | D3236-S1 S26361-D3236-S1    | Desktop     | [1e743d0b2d](https://linux-hardware.org/?probe=1e743d0b2d) | Sep 06, 2023 |
| Medion        | Akoya P2213T                | Notebook    | [2464869ce2](https://linux-hardware.org/?probe=2464869ce2) | Sep 06, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [50777cde40](https://linux-hardware.org/?probe=50777cde40) | Sep 06, 2023 |
| Dell          | Precision M4700             | Notebook    | [3e354770b6](https://linux-hardware.org/?probe=3e354770b6) | Sep 06, 2023 |
| Lenovo        | ThinkPad T580 20LAS01H00    | Notebook    | [129e989480](https://linux-hardware.org/?probe=129e989480) | Sep 06, 2023 |
| ASRock        | H77 Pro4/MVP                | Desktop     | [9e650e7107](https://linux-hardware.org/?probe=9e650e7107) | Sep 06, 2023 |
| Intel         | NUC11PABi5 M68265-501       | Mini pc     | [3266fb476d](https://linux-hardware.org/?probe=3266fb476d) | Sep 06, 2023 |
| Shenzhen M... | F7BFD                       | Desktop     | [3f1c2a5cfa](https://linux-hardware.org/?probe=3f1c2a5cfa) | Sep 06, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [9e7c97275d](https://linux-hardware.org/?probe=9e7c97275d) | Sep 06, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [09e4ad77a9](https://linux-hardware.org/?probe=09e4ad77a9) | Sep 06, 2023 |
| Biostar       | G31-M7 TE                   | Desktop     | [2ef74da3f9](https://linux-hardware.org/?probe=2ef74da3f9) | Sep 06, 2023 |
| DFI           | CH960                       | Desktop     | [f0caeeeae0](https://linux-hardware.org/?probe=f0caeeeae0) | Sep 06, 2023 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [bf3fa40a81](https://linux-hardware.org/?probe=bf3fa40a81) | Sep 06, 2023 |
| ASUSTek       | K70IO                       | Notebook    | [bb32d5e30c](https://linux-hardware.org/?probe=bb32d5e30c) | Sep 06, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [659838923d](https://linux-hardware.org/?probe=659838923d) | Sep 06, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [1c4301b1ba](https://linux-hardware.org/?probe=1c4301b1ba) | Sep 06, 2023 |
| Alienware     | 0H869M A00                  | Desktop     | [64132daa63](https://linux-hardware.org/?probe=64132daa63) | Sep 06, 2023 |
| HP            | EliteBook x360 1020 G2      | Convertible | [583006d2de](https://linux-hardware.org/?probe=583006d2de) | Sep 06, 2023 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [80e1d849fd](https://linux-hardware.org/?probe=80e1d849fd) | Sep 06, 2023 |
| Dell          | Latitude 3190               | Notebook    | [60f82737fa](https://linux-hardware.org/?probe=60f82737fa) | Sep 06, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [8e0ee8ad83](https://linux-hardware.org/?probe=8e0ee8ad83) | Sep 06, 2023 |
| ASRock        | H61M-DGS R2.0               | Desktop     | [69a1288adb](https://linux-hardware.org/?probe=69a1288adb) | Sep 06, 2023 |
| ASRock        | H61M-DGS R2.0               | Desktop     | [f00617a2cf](https://linux-hardware.org/?probe=f00617a2cf) | Sep 06, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | Notebook    | [b6b2af8418](https://linux-hardware.org/?probe=b6b2af8418) | Sep 06, 2023 |
| Dell          | Latitude E7270              | Notebook    | [b8dcc3bac9](https://linux-hardware.org/?probe=b8dcc3bac9) | Sep 06, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | Notebook    | [89767db9e4](https://linux-hardware.org/?probe=89767db9e4) | Sep 06, 2023 |
| VALE          | Notebook Classic C140       | Notebook    | [c2e792fccf](https://linux-hardware.org/?probe=c2e792fccf) | Sep 06, 2023 |
| VALE          | Notebook Classic C140       | Notebook    | [fb00b74b14](https://linux-hardware.org/?probe=fb00b74b14) | Sep 06, 2023 |
| VALE          | Notebook Classic C140       | Notebook    | [675a9e9b79](https://linux-hardware.org/?probe=675a9e9b79) | Sep 06, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [2ce7b78a76](https://linux-hardware.org/?probe=2ce7b78a76) | Sep 06, 2023 |
| ASRockRack    | B565D4-V1L                  | Desktop     | [ff236ef40e](https://linux-hardware.org/?probe=ff236ef40e) | Sep 06, 2023 |
| ASUSTek       | K70IO                       | Notebook    | [e4f165224f](https://linux-hardware.org/?probe=e4f165224f) | Sep 06, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [55c623e23d](https://linux-hardware.org/?probe=55c623e23d) | Sep 06, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [db0c457b51](https://linux-hardware.org/?probe=db0c457b51) | Sep 06, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [8d550b32d9](https://linux-hardware.org/?probe=8d550b32d9) | Sep 06, 2023 |
| Toshiba       | Satellite A210              | Notebook    | [54f5fb9c03](https://linux-hardware.org/?probe=54f5fb9c03) | Sep 06, 2023 |
| ASRock        | A320M-HDV R3.0              | Desktop     | [0d796a5d20](https://linux-hardware.org/?probe=0d796a5d20) | Sep 05, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [f73f6d9301](https://linux-hardware.org/?probe=f73f6d9301) | Sep 05, 2023 |
| ASRock        | N68C-S UCC                  | Desktop     | [c2e1fe7134](https://linux-hardware.org/?probe=c2e1fe7134) | Sep 05, 2023 |
| DFI           | CH960                       | Desktop     | [29c9bcf1ed](https://linux-hardware.org/?probe=29c9bcf1ed) | Sep 05, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [38aad324f2](https://linux-hardware.org/?probe=38aad324f2) | Sep 05, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [61c5e35c02](https://linux-hardware.org/?probe=61c5e35c02) | Sep 05, 2023 |
| Dell          | Latitude E7270              | Notebook    | [5a2067c4c2](https://linux-hardware.org/?probe=5a2067c4c2) | Sep 05, 2023 |
| Dell          | Inspiron 3480               | Notebook    | [3d639d27ba](https://linux-hardware.org/?probe=3d639d27ba) | Sep 05, 2023 |
| MSI           | Z270 GAMING PRO CARBON      | Desktop     | [6644f7f91e](https://linux-hardware.org/?probe=6644f7f91e) | Sep 05, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [344c861540](https://linux-hardware.org/?probe=344c861540) | Sep 05, 2023 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [5971b283b6](https://linux-hardware.org/?probe=5971b283b6) | Sep 05, 2023 |
| MSI           | MAG B560M MORTAR WIFI       | Desktop     | [376e22722b](https://linux-hardware.org/?probe=376e22722b) | Sep 05, 2023 |
| Samsung       | 750XDA                      | Notebook    | [efe919fb13](https://linux-hardware.org/?probe=efe919fb13) | Sep 05, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [846d8027c3](https://linux-hardware.org/?probe=846d8027c3) | Sep 05, 2023 |
| Gigabyte      | H310M H                     | Desktop     | [47b2450a3e](https://linux-hardware.org/?probe=47b2450a3e) | Sep 05, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [acdd8a41d9](https://linux-hardware.org/?probe=acdd8a41d9) | Sep 05, 2023 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [4823d1487d](https://linux-hardware.org/?probe=4823d1487d) | Sep 05, 2023 |
| Lenovo        | Dory CRB                    | Desktop     | [4c136b6049](https://linux-hardware.org/?probe=4c136b6049) | Sep 04, 2023 |
| Fujitsu       | D3183-A1 S26361-D3183-A1    | Desktop     | [85e1b123db](https://linux-hardware.org/?probe=85e1b123db) | Sep 04, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [66dedbf64b](https://linux-hardware.org/?probe=66dedbf64b) | Sep 04, 2023 |
| TUXEDO        | Unknown                     | Notebook    | [c6b62e2a29](https://linux-hardware.org/?probe=c6b62e2a29) | Sep 04, 2023 |
| HP            | 8055                        | Desktop     | [2ed2e99af3](https://linux-hardware.org/?probe=2ed2e99af3) | Sep 04, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [9f577988e1](https://linux-hardware.org/?probe=9f577988e1) | Sep 04, 2023 |
| TUXEDO        | Pulse 15 Gen2               | Notebook    | [3dd77a8c87](https://linux-hardware.org/?probe=3dd77a8c87) | Sep 04, 2023 |
| Lenovo        | 3000 N200 0769EGG           | Notebook    | [44fd3c6e60](https://linux-hardware.org/?probe=44fd3c6e60) | Sep 04, 2023 |
| HP            | 2129                        | Desktop     | [d021b12b77](https://linux-hardware.org/?probe=d021b12b77) | Sep 04, 2023 |
| HP            | Laptop 17-by0xxx            | Notebook    | [7c149b5f95](https://linux-hardware.org/?probe=7c149b5f95) | Sep 04, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [f5e7afad66](https://linux-hardware.org/?probe=f5e7afad66) | Sep 04, 2023 |
| Acer          | Aspire 8930                 | Notebook    | [9901032e2b](https://linux-hardware.org/?probe=9901032e2b) | Sep 04, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [37e16bb39c](https://linux-hardware.org/?probe=37e16bb39c) | Sep 04, 2023 |
| Lenovo        | V130-15IKB 81HN             | Notebook    | [760698ac8a](https://linux-hardware.org/?probe=760698ac8a) | Sep 04, 2023 |
| ASUSTek       | X75A1                       | Notebook    | [d8be6d6952](https://linux-hardware.org/?probe=d8be6d6952) | Sep 04, 2023 |
| ASRock        | H61M-DGS R2.0               | Desktop     | [3edb7718df](https://linux-hardware.org/?probe=3edb7718df) | Sep 04, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [5128231fd7](https://linux-hardware.org/?probe=5128231fd7) | Sep 04, 2023 |
| ASRockRack    | X470D4U                     | Desktop     | [d38e269d11](https://linux-hardware.org/?probe=d38e269d11) | Sep 04, 2023 |
| Fujitsu       | D3603-A1 S26361-D3603-A1    | Desktop     | [caa794eff8](https://linux-hardware.org/?probe=caa794eff8) | Sep 04, 2023 |
| HUAWEI        | BC11HGSC0 V100R003          | Server      | [6ce4aa2350](https://linux-hardware.org/?probe=6ce4aa2350) | Sep 04, 2023 |
| HP            | 829E                        | Mini pc     | [205ab47a36](https://linux-hardware.org/?probe=205ab47a36) | Sep 04, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | Notebook    | [49d36f6acc](https://linux-hardware.org/?probe=49d36f6acc) | Sep 04, 2023 |
| Gigabyte      | H510M S2H                   | Desktop     | [82f3e710d9](https://linux-hardware.org/?probe=82f3e710d9) | Sep 04, 2023 |
| Medion        | TJ4125                      | Desktop     | [e2e111051c](https://linux-hardware.org/?probe=e2e111051c) | Sep 03, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [9d4d9e6ffa](https://linux-hardware.org/?probe=9d4d9e6ffa) | Sep 03, 2023 |
| Acer          | Aspire XC-830               | Desktop     | [a3356b9a91](https://linux-hardware.org/?probe=a3356b9a91) | Sep 03, 2023 |
| ASUSTek       | X55A                        | Notebook    | [da721dec12](https://linux-hardware.org/?probe=da721dec12) | Sep 03, 2023 |
| Lenovo        | Flex 2-15D 20377            | Notebook    | [88c1e6be3b](https://linux-hardware.org/?probe=88c1e6be3b) | Sep 03, 2023 |
| HP            | EliteBook 2740p             | Notebook    | [c6d9dc5a3b](https://linux-hardware.org/?probe=c6d9dc5a3b) | Sep 03, 2023 |
| Medion        | Akoya E4214 MD99570         | Notebook    | [1454b9c6a8](https://linux-hardware.org/?probe=1454b9c6a8) | Sep 03, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [493d16ff67](https://linux-hardware.org/?probe=493d16ff67) | Sep 03, 2023 |
| ASUSTek       | P5E-VM SE                   | Desktop     | [6ce264a945](https://linux-hardware.org/?probe=6ce264a945) | Sep 03, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [c6a4b0aca9](https://linux-hardware.org/?probe=c6a4b0aca9) | Sep 03, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [0778936f6b](https://linux-hardware.org/?probe=0778936f6b) | Sep 03, 2023 |
| Lenovo        | Flex 2-15D 20377            | Notebook    | [7b0445b6d8](https://linux-hardware.org/?probe=7b0445b6d8) | Sep 03, 2023 |
| Fujitsu       | D3223-C1 S26361-D3223-C1    | Desktop     | [75c1744e6f](https://linux-hardware.org/?probe=75c1744e6f) | Sep 03, 2023 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | Notebook    | [cdf37a1590](https://linux-hardware.org/?probe=cdf37a1590) | Sep 03, 2023 |
| Lenovo        | Legion S7 16IAH7 82TF       | Notebook    | [f4c15b0551](https://linux-hardware.org/?probe=f4c15b0551) | Sep 03, 2023 |
| Valve         | Jupiter                     | Notebook    | [25261ec140](https://linux-hardware.org/?probe=25261ec140) | Sep 03, 2023 |
| IP3 Tech      | rev1.0                      | All in one  | [d2c6f51ff8](https://linux-hardware.org/?probe=d2c6f51ff8) | Sep 03, 2023 |
| Acer          | Aspire A515-55              | Notebook    | [71305b0cca](https://linux-hardware.org/?probe=71305b0cca) | Sep 03, 2023 |
| HP            | 828A                        | Desktop     | [13126d5ce1](https://linux-hardware.org/?probe=13126d5ce1) | Sep 03, 2023 |
| Dell          | 0VHWTR A02                  | Desktop     | [be2e4d0e02](https://linux-hardware.org/?probe=be2e4d0e02) | Sep 03, 2023 |
| Acer          | Aspire 5741G                | Notebook    | [b49fa94760](https://linux-hardware.org/?probe=b49fa94760) | Sep 03, 2023 |
| Pegatron      | IPMSB-GS                    | Desktop     | [35b8f645a7](https://linux-hardware.org/?probe=35b8f645a7) | Sep 03, 2023 |
| Acer          | Nitro N50-600 V:1.1         | Desktop     | [d15e4d0045](https://linux-hardware.org/?probe=d15e4d0045) | Sep 03, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [8e63bb873b](https://linux-hardware.org/?probe=8e63bb873b) | Sep 03, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [439817c540](https://linux-hardware.org/?probe=439817c540) | Sep 03, 2023 |
| Dell          | Inspiron 5770               | Notebook    | [1bed4ada1e](https://linux-hardware.org/?probe=1bed4ada1e) | Sep 03, 2023 |
| VALE          | Notebook Classic C140       | Notebook    | [05b3dfb69a](https://linux-hardware.org/?probe=05b3dfb69a) | Sep 03, 2023 |
| ASRock        | Z77 Extreme4                | Desktop     | [1115c7ff24](https://linux-hardware.org/?probe=1115c7ff24) | Sep 03, 2023 |
| ASUSTek       | X55A                        | Notebook    | [1ba0e59208](https://linux-hardware.org/?probe=1ba0e59208) | Sep 03, 2023 |
| Gigabyte      | H310M H                     | Desktop     | [ab3739f4e8](https://linux-hardware.org/?probe=ab3739f4e8) | Sep 03, 2023 |
| HP            | ProLiant MicroServer        | Desktop     | [b312bca31d](https://linux-hardware.org/?probe=b312bca31d) | Sep 03, 2023 |
| HP            | ProLiant MicroServer        | Desktop     | [734d6a99e7](https://linux-hardware.org/?probe=734d6a99e7) | Sep 03, 2023 |
| Gigabyte      | Z97X-SLI-CF                 | Desktop     | [ffc201e884](https://linux-hardware.org/?probe=ffc201e884) | Sep 02, 2023 |
| Medion        | S15449                      | Notebook    | [7e8cd1a434](https://linux-hardware.org/?probe=7e8cd1a434) | Sep 02, 2023 |
| Chuwi         | GemiBook XPro               | Notebook    | [a76e69489c](https://linux-hardware.org/?probe=a76e69489c) | Sep 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [5a331fce10](https://linux-hardware.org/?probe=5a331fce10) | Sep 02, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [fdb735b431](https://linux-hardware.org/?probe=fdb735b431) | Sep 02, 2023 |
| ASRock        | Z790 PG SONIC               | Desktop     | [72f1cf1ac0](https://linux-hardware.org/?probe=72f1cf1ac0) | Sep 02, 2023 |
| Microsoft     | Surface Pro 8               | Tablet      | [219bfdb3a5](https://linux-hardware.org/?probe=219bfdb3a5) | Sep 02, 2023 |
| Fujitsu Si... | LIFEBOOK E8410              | Notebook    | [31618d06c6](https://linux-hardware.org/?probe=31618d06c6) | Sep 02, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [c3dc3fd84b](https://linux-hardware.org/?probe=c3dc3fd84b) | Sep 02, 2023 |
| MSI           | MAG B560M MORTAR WIFI       | Desktop     | [388f380783](https://linux-hardware.org/?probe=388f380783) | Sep 02, 2023 |
| MSI           | Z270 GAMING PRO CARBON      | Desktop     | [43a2fbe118](https://linux-hardware.org/?probe=43a2fbe118) | Sep 02, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [70f99195d8](https://linux-hardware.org/?probe=70f99195d8) | Sep 02, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [9259a8f3f3](https://linux-hardware.org/?probe=9259a8f3f3) | Sep 02, 2023 |
| ASRock        | B660M Pro RS                | Desktop     | [f24f7fb5bf](https://linux-hardware.org/?probe=f24f7fb5bf) | Sep 02, 2023 |
| Biostar       | H81MHV3 5.0                 | Desktop     | [8e05d94e36](https://linux-hardware.org/?probe=8e05d94e36) | Sep 02, 2023 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | Desktop     | [32a90ea48e](https://linux-hardware.org/?probe=32a90ea48e) | Sep 02, 2023 |
| Lenovo        | ThinkPad T540p 20BFCTO      | Notebook    | [6c4bd340bc](https://linux-hardware.org/?probe=6c4bd340bc) | Sep 02, 2023 |
| Dell          | Latitude 5500               | Notebook    | [77e18d6323](https://linux-hardware.org/?probe=77e18d6323) | Sep 02, 2023 |
| Lenovo        | ThinkPad T520 42435JG       | Notebook    | [aad827567e](https://linux-hardware.org/?probe=aad827567e) | Sep 02, 2023 |
| MSI           | MS-1688                     | Notebook    | [30cd2d6e9a](https://linux-hardware.org/?probe=30cd2d6e9a) | Sep 02, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [fc9ec80df9](https://linux-hardware.org/?probe=fc9ec80df9) | Sep 02, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F6... | Notebook    | [2fc5b41456](https://linux-hardware.org/?probe=2fc5b41456) | Sep 02, 2023 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [aa1ec8baed](https://linux-hardware.org/?probe=aa1ec8baed) | Sep 02, 2023 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [38371fb896](https://linux-hardware.org/?probe=38371fb896) | Sep 02, 2023 |
| Dell          | Latitude 3590               | Notebook    | [9406fe5cf7](https://linux-hardware.org/?probe=9406fe5cf7) | Sep 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [7dabe0d117](https://linux-hardware.org/?probe=7dabe0d117) | Sep 01, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [318dc8ce55](https://linux-hardware.org/?probe=318dc8ce55) | Sep 01, 2023 |
| Acer          | One S1003                   | Tablet      | [b49022d342](https://linux-hardware.org/?probe=b49022d342) | Sep 01, 2023 |
| Fujitsu       | D3400-A1 S26361-D3400-A1    | Desktop     | [f11dacb362](https://linux-hardware.org/?probe=f11dacb362) | Sep 01, 2023 |
| Pegatron      | 2AB6                        | Desktop     | [a0649549b3](https://linux-hardware.org/?probe=a0649549b3) | Sep 01, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [76b83d4e93](https://linux-hardware.org/?probe=76b83d4e93) | Sep 01, 2023 |
| Acer          | Aspire 7740                 | Notebook    | [1ab9e5eddb](https://linux-hardware.org/?probe=1ab9e5eddb) | Sep 01, 2023 |
| HP            | Laptop 17-bs0xx             | Notebook    | [c4727ff179](https://linux-hardware.org/?probe=c4727ff179) | Sep 01, 2023 |
| Intel         | NUC5i7RYB H73774-101        | Mini pc     | [35e287844f](https://linux-hardware.org/?probe=35e287844f) | Sep 01, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [bb0b1a142a](https://linux-hardware.org/?probe=bb0b1a142a) | Sep 01, 2023 |
| Acer          | Aspire A317-32              | Notebook    | [0a46c781fc](https://linux-hardware.org/?probe=0a46c781fc) | Sep 01, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [027ceec09f](https://linux-hardware.org/?probe=027ceec09f) | Sep 01, 2023 |
| Medion        | A17                         | Notebook    | [31b4226638](https://linux-hardware.org/?probe=31b4226638) | Sep 01, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [f39e23df01](https://linux-hardware.org/?probe=f39e23df01) | Sep 01, 2023 |
| Lenovo        | ThinkPad X250 20CL001DGE    | Notebook    | [f6bc603569](https://linux-hardware.org/?probe=f6bc603569) | Sep 01, 2023 |
| HP            | 339A                        | Desktop     | [e4423b3eb7](https://linux-hardware.org/?probe=e4423b3eb7) | Sep 01, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | Notebook    | [6736962dbe](https://linux-hardware.org/?probe=6736962dbe) | Sep 01, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [bda3b1837c](https://linux-hardware.org/?probe=bda3b1837c) | Sep 01, 2023 |
| Acer          | Aspire V3-771               | Notebook    | [67082ec830](https://linux-hardware.org/?probe=67082ec830) | Sep 01, 2023 |
| Razer         | Blade                       | Notebook    | [8daaeab270](https://linux-hardware.org/?probe=8daaeab270) | Sep 01, 2023 |
| ASUSTek       | H81M2                       | Desktop     | [55dd352412](https://linux-hardware.org/?probe=55dd352412) | Sep 01, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [d8e4c2da1e](https://linux-hardware.org/?probe=d8e4c2da1e) | Sep 01, 2023 |
| ASUSTek       | P8Q77-M                     | Desktop     | [0192700365](https://linux-hardware.org/?probe=0192700365) | Sep 01, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | Desktop     | [6434195348](https://linux-hardware.org/?probe=6434195348) | Sep 01, 2023 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [6f84a1d68f](https://linux-hardware.org/?probe=6f84a1d68f) | Sep 01, 2023 |
| Medion        | B250H4-EM                   | Desktop     | [c2e1f2eb0b](https://linux-hardware.org/?probe=c2e1f2eb0b) | Sep 01, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [4725c2be8e](https://linux-hardware.org/?probe=4725c2be8e) | Sep 01, 2023 |
| Lenovo        | V15-IGL 82C3                | Notebook    | [4ab20a426a](https://linux-hardware.org/?probe=4ab20a426a) | Sep 01, 2023 |
| Dell          | Inspiron 5579               | Notebook    | [14fa68270f](https://linux-hardware.org/?probe=14fa68270f) | Sep 01, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [0dbf80863b](https://linux-hardware.org/?probe=0dbf80863b) | Sep 01, 2023 |
| Fujitsu       | D3410-B2 S26361-D3410-B2    | Desktop     | [924293e07f](https://linux-hardware.org/?probe=924293e07f) | Sep 01, 2023 |
| HP            | ZBook 15                    | Notebook    | [8a20670725](https://linux-hardware.org/?probe=8a20670725) | Sep 01, 2023 |
| MSI           | N6105                       | Notebook    | [8ee14b4635](https://linux-hardware.org/?probe=8ee14b4635) | Sep 01, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [d728ff01da](https://linux-hardware.org/?probe=d728ff01da) | Sep 01, 2023 |
| MSI           | N6105                       | Notebook    | [7f41073c40](https://linux-hardware.org/?probe=7f41073c40) | Sep 01, 2023 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [3a4c0e0930](https://linux-hardware.org/?probe=3a4c0e0930) | Aug 31, 2023 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [b6a24176aa](https://linux-hardware.org/?probe=b6a24176aa) | Aug 31, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [40c7e7f27b](https://linux-hardware.org/?probe=40c7e7f27b) | Aug 31, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [281e7176d8](https://linux-hardware.org/?probe=281e7176d8) | Aug 31, 2023 |
| HP            | 18E5                        | Desktop     | [75c3b34f87](https://linux-hardware.org/?probe=75c3b34f87) | Aug 31, 2023 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [5b632410e7](https://linux-hardware.org/?probe=5b632410e7) | Aug 31, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | Desktop     | [d0a3fefd23](https://linux-hardware.org/?probe=d0a3fefd23) | Aug 31, 2023 |
| Lenovo        | ThinkPad L470 20J40010GE    | Notebook    | [53adc42d66](https://linux-hardware.org/?probe=53adc42d66) | Aug 31, 2023 |
| Lenovo        | ThinkPad X380 Yoga 20LH0... | Convertible | [2d86125311](https://linux-hardware.org/?probe=2d86125311) | Aug 31, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [5ef4c889a4](https://linux-hardware.org/?probe=5ef4c889a4) | Aug 31, 2023 |
| Acer          | Swift SF114-34              | Notebook    | [987f4bab43](https://linux-hardware.org/?probe=987f4bab43) | Aug 31, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | Desktop     | [710315c4f1](https://linux-hardware.org/?probe=710315c4f1) | Aug 31, 2023 |
| Dell          | 0GM819                      | Desktop     | [8144006f85](https://linux-hardware.org/?probe=8144006f85) | Aug 31, 2023 |
| HP            | 8768 A                      | Desktop     | [99787646c5](https://linux-hardware.org/?probe=99787646c5) | Aug 31, 2023 |
| Dell          | 0GM819                      | Desktop     | [f7c99aa51b](https://linux-hardware.org/?probe=f7c99aa51b) | Aug 31, 2023 |
| Lenovo        | ThinkPad T420 42364A1       | Notebook    | [968cd5e999](https://linux-hardware.org/?probe=968cd5e999) | Aug 31, 2023 |
| Gigabyte      | H97-HD3                     | Desktop     | [ba11958a48](https://linux-hardware.org/?probe=ba11958a48) | Aug 31, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [5720a360fb](https://linux-hardware.org/?probe=5720a360fb) | Aug 31, 2023 |
| Acer          | Aspire A317-33              | Notebook    | [8e27446a62](https://linux-hardware.org/?probe=8e27446a62) | Aug 31, 2023 |
| ASUSTek       | PN40                        | Mini pc     | [980ae9bc2d](https://linux-hardware.org/?probe=980ae9bc2d) | Aug 31, 2023 |
| Gigabyte      | H55M-USB3                   | Desktop     | [9ebfdab7fa](https://linux-hardware.org/?probe=9ebfdab7fa) | Aug 31, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [ee8a1b4fb5](https://linux-hardware.org/?probe=ee8a1b4fb5) | Aug 31, 2023 |
| Lenovo        | ThinkPad X220 4290EC5       | Notebook    | [d75bd4dfbd](https://linux-hardware.org/?probe=d75bd4dfbd) | Aug 31, 2023 |
| Gigabyte      | H97-HD3                     | Desktop     | [158ed240bf](https://linux-hardware.org/?probe=158ed240bf) | Aug 31, 2023 |
| Medion        | Akoya E6239                 | Notebook    | [ec5460d846](https://linux-hardware.org/?probe=ec5460d846) | Aug 31, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [19cb61cbf6](https://linux-hardware.org/?probe=19cb61cbf6) | Aug 31, 2023 |
| Dell          | Latitude 5590               | Notebook    | [59d99ec581](https://linux-hardware.org/?probe=59d99ec581) | Aug 31, 2023 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | Desktop     | [f0e20e0089](https://linux-hardware.org/?probe=f0e20e0089) | Aug 31, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F6... | Notebook    | [3384884acc](https://linux-hardware.org/?probe=3384884acc) | Aug 31, 2023 |
| Lenovo        | SDK0J40700 WIN              | Desktop     | [12785fd41a](https://linux-hardware.org/?probe=12785fd41a) | Aug 31, 2023 |
| Acer          | Aspire E5-774G              | Notebook    | [0e6c0b300b](https://linux-hardware.org/?probe=0e6c0b300b) | Aug 31, 2023 |
| ASRock        | NUC-8265U                   | Desktop     | [6f9f173920](https://linux-hardware.org/?probe=6f9f173920) | Aug 31, 2023 |
| Lenovo        | IdeaPad Pro 5 16APH8 83A... | Notebook    | [3c434cdeda](https://linux-hardware.org/?probe=3c434cdeda) | Aug 31, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [085b3d4330](https://linux-hardware.org/?probe=085b3d4330) | Aug 31, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [98b18bb67a](https://linux-hardware.org/?probe=98b18bb67a) | Aug 31, 2023 |
| MSI           | GS70 2OD                    | Notebook    | [1bc4bba326](https://linux-hardware.org/?probe=1bc4bba326) | Aug 31, 2023 |
| Dell          | 08WKV3 A00                  | Desktop     | [31138e2c0a](https://linux-hardware.org/?probe=31138e2c0a) | Aug 31, 2023 |
| Medion        | P7818                       | Notebook    | [b2e6745157](https://linux-hardware.org/?probe=b2e6745157) | Aug 30, 2023 |
| HP            | ZBook 14u G5                | Notebook    | [5d458370a6](https://linux-hardware.org/?probe=5d458370a6) | Aug 30, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [42f87cb09b](https://linux-hardware.org/?probe=42f87cb09b) | Aug 30, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [9faf6d1836](https://linux-hardware.org/?probe=9faf6d1836) | Aug 30, 2023 |
| MSI           | H61MA-E35                   | Desktop     | [5eee145629](https://linux-hardware.org/?probe=5eee145629) | Aug 30, 2023 |
| LattePanda    | 3 Delta LP-BS-7-S70JR120... | Desktop     | [04d647ae08](https://linux-hardware.org/?probe=04d647ae08) | Aug 30, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [a452d9eadf](https://linux-hardware.org/?probe=a452d9eadf) | Aug 30, 2023 |
| Lenovo        | V15-IGL 82C3                | Notebook    | [3a0999b4a7](https://linux-hardware.org/?probe=3a0999b4a7) | Aug 30, 2023 |
| Valve         | Jupiter                     | Notebook    | [acd834caed](https://linux-hardware.org/?probe=acd834caed) | Aug 30, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [d963970016](https://linux-hardware.org/?probe=d963970016) | Aug 30, 2023 |
| MSI           | Z97-G43                     | Desktop     | [74492b4424](https://linux-hardware.org/?probe=74492b4424) | Aug 30, 2023 |
| Valve         | Jupiter                     | Notebook    | [1e494aa7bf](https://linux-hardware.org/?probe=1e494aa7bf) | Aug 30, 2023 |
| Medion        | B460H6-EM                   | Desktop     | [fac263bf1a](https://linux-hardware.org/?probe=fac263bf1a) | Aug 30, 2023 |
| Fujitsu       | D3061-B1 S26361-D3061-B1    | Desktop     | [5de56db01e](https://linux-hardware.org/?probe=5de56db01e) | Aug 30, 2023 |
| ASUSTek       | M5A78L-M LE                 | Desktop     | [58446213e2](https://linux-hardware.org/?probe=58446213e2) | Aug 30, 2023 |
| Lenovo        | V17 G4 IRU 83A2             | Notebook    | [a5fd9c62e8](https://linux-hardware.org/?probe=a5fd9c62e8) | Aug 30, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [28c0349031](https://linux-hardware.org/?probe=28c0349031) | Aug 30, 2023 |
| Pegatron      | 2AB6                        | Desktop     | [272508eb60](https://linux-hardware.org/?probe=272508eb60) | Aug 30, 2023 |
| Dell          | Latitude E6510              | Notebook    | [ccc08ed4ed](https://linux-hardware.org/?probe=ccc08ed4ed) | Aug 30, 2023 |
| ASUSTek       | P8H67-V                     | Desktop     | [24b196c99a](https://linux-hardware.org/?probe=24b196c99a) | Aug 30, 2023 |
| Dell          | Latitude E6510              | Notebook    | [dcf1be6cbe](https://linux-hardware.org/?probe=dcf1be6cbe) | Aug 30, 2023 |
| Gigabyte      | EP35-DS3                    | Desktop     | [c317e9aa3a](https://linux-hardware.org/?probe=c317e9aa3a) | Aug 30, 2023 |
| Lenovo        | ThinkPad T420 4236MBG       | Notebook    | [dc28b42a00](https://linux-hardware.org/?probe=dc28b42a00) | Aug 30, 2023 |
| HP            | EliteBook x360 1020 G2      | Convertible | [2a5e5f7d35](https://linux-hardware.org/?probe=2a5e5f7d35) | Aug 30, 2023 |
| ASRock        | H170M-ITX/ac                | Desktop     | [7921e28c6b](https://linux-hardware.org/?probe=7921e28c6b) | Aug 30, 2023 |
| HP            | 8054                        | Desktop     | [f73271d96e](https://linux-hardware.org/?probe=f73271d96e) | Aug 30, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [f59364572a](https://linux-hardware.org/?probe=f59364572a) | Aug 30, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [76805c8b77](https://linux-hardware.org/?probe=76805c8b77) | Aug 30, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [cc6b5178f0](https://linux-hardware.org/?probe=cc6b5178f0) | Aug 30, 2023 |
| MSI           | MPG B460I GAMING EDGE WI... | Desktop     | [5a4e0650a2](https://linux-hardware.org/?probe=5a4e0650a2) | Aug 30, 2023 |
| ASUSTek       | P8Z68-V PRO GEN3            | Desktop     | [a9d960e012](https://linux-hardware.org/?probe=a9d960e012) | Aug 29, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [0b44043b10](https://linux-hardware.org/?probe=0b44043b10) | Aug 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [abdd8929db](https://linux-hardware.org/?probe=abdd8929db) | Aug 29, 2023 |
| Lenovo        | ThinkPad W541 20EGS0N00H    | Notebook    | [ed94f8b9b9](https://linux-hardware.org/?probe=ed94f8b9b9) | Aug 29, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [64686e9027](https://linux-hardware.org/?probe=64686e9027) | Aug 29, 2023 |
| MSI           | Z97 GAMING 7                | Desktop     | [ea78ba2d46](https://linux-hardware.org/?probe=ea78ba2d46) | Aug 29, 2023 |
| Notebook      | W230ST                      | Notebook    | [0061b93424](https://linux-hardware.org/?probe=0061b93424) | Aug 29, 2023 |
| HP            | Pavilion g6                 | Notebook    | [b1836fb080](https://linux-hardware.org/?probe=b1836fb080) | Aug 29, 2023 |
| Lenovo        | ThinkCentre M57 6087D44     | Desktop     | [0b30efa677](https://linux-hardware.org/?probe=0b30efa677) | Aug 29, 2023 |
| Fujitsu       | LIFEBOOK S792               | Notebook    | [7547ab7e8e](https://linux-hardware.org/?probe=7547ab7e8e) | Aug 29, 2023 |
| ASUSTek       | ROG Strix G634JZ_G634JZ     | Notebook    | [481b37b0fc](https://linux-hardware.org/?probe=481b37b0fc) | Aug 29, 2023 |
| Gigabyte      | H81M-D2V                    | Desktop     | [079adcbbe9](https://linux-hardware.org/?probe=079adcbbe9) | Aug 29, 2023 |
| HP            | Pavilion Gaming Laptop      | Notebook    | [c9fa671277](https://linux-hardware.org/?probe=c9fa671277) | Aug 29, 2023 |
| ASUSTek       | K93SV                       | Notebook    | [01701d7ab0](https://linux-hardware.org/?probe=01701d7ab0) | Aug 29, 2023 |
| ASUSTek       | K93SV                       | Notebook    | [6da5e2d119](https://linux-hardware.org/?probe=6da5e2d119) | Aug 29, 2023 |
| Gigabyte      | P55-UD4                     | Desktop     | [071fa35482](https://linux-hardware.org/?probe=071fa35482) | Aug 29, 2023 |
| Dell          | 0KWVT8 A03                  | Desktop     | [04ee67e1ad](https://linux-hardware.org/?probe=04ee67e1ad) | Aug 29, 2023 |
| Clevo         | W150HRM                     | Notebook    | [142e1026a1](https://linux-hardware.org/?probe=142e1026a1) | Aug 29, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [41ce572b6d](https://linux-hardware.org/?probe=41ce572b6d) | Aug 29, 2023 |
| Lenovo        | ThinkCentre M91p 4518B84    | Desktop     | [e2fd5511ee](https://linux-hardware.org/?probe=e2fd5511ee) | Aug 29, 2023 |
| Gigabyte      | GA-880GA-UD3H               | Desktop     | [183437f6de](https://linux-hardware.org/?probe=183437f6de) | Aug 29, 2023 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [599a95cff7](https://linux-hardware.org/?probe=599a95cff7) | Aug 29, 2023 |
| Packard Be... | EasyNote ENTF71BM           | Notebook    | [e5923577ad](https://linux-hardware.org/?probe=e5923577ad) | Aug 28, 2023 |
| Gigabyte      | Z390 UD                     | Desktop     | [9cbff867a4](https://linux-hardware.org/?probe=9cbff867a4) | Aug 28, 2023 |
| HP            | Split 13 x2 PC              | Notebook    | [ab71a69e7e](https://linux-hardware.org/?probe=ab71a69e7e) | Aug 28, 2023 |
| Gigabyte      | Z390 UD                     | Desktop     | [8cc632de8d](https://linux-hardware.org/?probe=8cc632de8d) | Aug 28, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [6d4609efa2](https://linux-hardware.org/?probe=6d4609efa2) | Aug 28, 2023 |
| Gigabyte      | Z390 UD                     | Desktop     | [16c1728f79](https://linux-hardware.org/?probe=16c1728f79) | Aug 28, 2023 |
| Sony          | VPCEH2N1E                   | Notebook    | [a3e59b2f83](https://linux-hardware.org/?probe=a3e59b2f83) | Aug 28, 2023 |
| Fujitsu       | D3817-A1 S26361-D3817-A1... | Desktop     | [50e64dbfa2](https://linux-hardware.org/?probe=50e64dbfa2) | Aug 28, 2023 |
| Lenovo        | ThinkPad T430s 2356H83      | Notebook    | [d623d73283](https://linux-hardware.org/?probe=d623d73283) | Aug 28, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [c04be07d75](https://linux-hardware.org/?probe=c04be07d75) | Aug 28, 2023 |
| HP            | EliteBook 830 G8 Noteboo... | Notebook    | [7abf0d31d8](https://linux-hardware.org/?probe=7abf0d31d8) | Aug 28, 2023 |
| Lenovo        | ThinkPad E470 20H2S00700    | Notebook    | [cea73826dc](https://linux-hardware.org/?probe=cea73826dc) | Aug 28, 2023 |
| HP            | Split 13 x2 PC              | Notebook    | [3df006557e](https://linux-hardware.org/?probe=3df006557e) | Aug 28, 2023 |
| ASRock        | H97M Pro4                   | Desktop     | [a9cd91e3be](https://linux-hardware.org/?probe=a9cd91e3be) | Aug 28, 2023 |
| Bluechip C... | TRAVELline TL14W4           | Notebook    | [7959987246](https://linux-hardware.org/?probe=7959987246) | Aug 28, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [63305912c4](https://linux-hardware.org/?probe=63305912c4) | Aug 28, 2023 |
| Lenovo        | ThinkPad L512 259766G       | Notebook    | [4b92af4aba](https://linux-hardware.org/?probe=4b92af4aba) | Aug 28, 2023 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [d8c81e6e37](https://linux-hardware.org/?probe=d8c81e6e37) | Aug 28, 2023 |
| Dell          | Latitude 7480               | Notebook    | [12f61ffe4a](https://linux-hardware.org/?probe=12f61ffe4a) | Aug 28, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [5b0183001d](https://linux-hardware.org/?probe=5b0183001d) | Aug 28, 2023 |
| Lenovo        | ThinkPad X380 Yoga 20LH0... | Convertible | [d302b80de1](https://linux-hardware.org/?probe=d302b80de1) | Aug 27, 2023 |
| ASUSTek       | X550VXK                     | Notebook    | [897e4f89ec](https://linux-hardware.org/?probe=897e4f89ec) | Aug 27, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [a27df9649c](https://linux-hardware.org/?probe=a27df9649c) | Aug 27, 2023 |
| Acer          | Aspire E5-774G              | Notebook    | [6e40336ff6](https://linux-hardware.org/?probe=6e40336ff6) | Aug 27, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [cb2419d3df](https://linux-hardware.org/?probe=cb2419d3df) | Aug 27, 2023 |
| Dell          | Latitude E6410              | Notebook    | [451d5477e5](https://linux-hardware.org/?probe=451d5477e5) | Aug 27, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [4357727561](https://linux-hardware.org/?probe=4357727561) | Aug 27, 2023 |
| TERRA         | TERRAPC                     | Notebook    | [2031fd343b](https://linux-hardware.org/?probe=2031fd343b) | Aug 27, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [f2b0e180d4](https://linux-hardware.org/?probe=f2b0e180d4) | Aug 27, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [929efec703](https://linux-hardware.org/?probe=929efec703) | Aug 27, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [eadbc95dc7](https://linux-hardware.org/?probe=eadbc95dc7) | Aug 27, 2023 |
| Dell          | 0FGCC7 A02                  | Server      | [dc59cd86a0](https://linux-hardware.org/?probe=dc59cd86a0) | Aug 27, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [be9aaf7726](https://linux-hardware.org/?probe=be9aaf7726) | Aug 27, 2023 |
| Notebook      | NHx0EH_EJ_EK                | Notebook    | [a37b52dfbe](https://linux-hardware.org/?probe=a37b52dfbe) | Aug 27, 2023 |
| Gigabyte      | P55-UD4                     | Desktop     | [db36b0429d](https://linux-hardware.org/?probe=db36b0429d) | Aug 27, 2023 |
| Lenovo        | ThinkPad L590 20Q70019GE    | Notebook    | [7df198a7b4](https://linux-hardware.org/?probe=7df198a7b4) | Aug 27, 2023 |
| HP            | ZBook 14u G5                | Notebook    | [d012bb60bf](https://linux-hardware.org/?probe=d012bb60bf) | Aug 27, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS       | Desktop     | [f108558763](https://linux-hardware.org/?probe=f108558763) | Aug 27, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [713e62f936](https://linux-hardware.org/?probe=713e62f936) | Aug 27, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | Notebook    | [08ec98196f](https://linux-hardware.org/?probe=08ec98196f) | Aug 27, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [b0a8f65bca](https://linux-hardware.org/?probe=b0a8f65bca) | Aug 27, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [4112e03a31](https://linux-hardware.org/?probe=4112e03a31) | Aug 27, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [fa48902a10](https://linux-hardware.org/?probe=fa48902a10) | Aug 27, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [8586d608af](https://linux-hardware.org/?probe=8586d608af) | Aug 26, 2023 |
| Dell          | 0782GW A00                  | Desktop     | [038c293f3b](https://linux-hardware.org/?probe=038c293f3b) | Aug 26, 2023 |
| Dell          | 0782GW A00                  | Desktop     | [4b8fa7c22e](https://linux-hardware.org/?probe=4b8fa7c22e) | Aug 26, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [6f81752b36](https://linux-hardware.org/?probe=6f81752b36) | Aug 26, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [9e0b5b0b7e](https://linux-hardware.org/?probe=9e0b5b0b7e) | Aug 26, 2023 |
| Dell          | Precision 7720              | Notebook    | [2281163932](https://linux-hardware.org/?probe=2281163932) | Aug 26, 2023 |
| Dell          | Latitude 7380               | Notebook    | [396738805e](https://linux-hardware.org/?probe=396738805e) | Aug 26, 2023 |
| Dell          | Latitude 7380               | Notebook    | [4a0db5ad8a](https://linux-hardware.org/?probe=4a0db5ad8a) | Aug 26, 2023 |
| ASUSTek       | Z77-A                       | Desktop     | [1aa1747b87](https://linux-hardware.org/?probe=1aa1747b87) | Aug 26, 2023 |
| Samsung       | Galaxy Book 12 LTE          | Tablet      | [c2efac4748](https://linux-hardware.org/?probe=c2efac4748) | Aug 26, 2023 |
| Dell          | 0VRWRC A00                  | Desktop     | [e3a47f55c9](https://linux-hardware.org/?probe=e3a47f55c9) | Aug 26, 2023 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [c53e992822](https://linux-hardware.org/?probe=c53e992822) | Aug 26, 2023 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [d8bb515dfb](https://linux-hardware.org/?probe=d8bb515dfb) | Aug 26, 2023 |
| MSI           | PRO Z790-A WIFI             | Desktop     | [f3874bf2fc](https://linux-hardware.org/?probe=f3874bf2fc) | Aug 26, 2023 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | Desktop     | [9bde22726b](https://linux-hardware.org/?probe=9bde22726b) | Aug 26, 2023 |
| Dell          | Precision M4800             | Notebook    | [89b88a1d3a](https://linux-hardware.org/?probe=89b88a1d3a) | Aug 26, 2023 |
| VALE          | Notebook Classic C140       | Notebook    | [c5cae456b6](https://linux-hardware.org/?probe=c5cae456b6) | Aug 26, 2023 |
| HP            | 2129                        | Desktop     | [7ebe21012d](https://linux-hardware.org/?probe=7ebe21012d) | Aug 26, 2023 |
| Acer          | Aspire E1-570               | Notebook    | [6c8db1b4dd](https://linux-hardware.org/?probe=6c8db1b4dd) | Aug 26, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [fcfb9cd970](https://linux-hardware.org/?probe=fcfb9cd970) | Aug 26, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [c3490914f6](https://linux-hardware.org/?probe=c3490914f6) | Aug 26, 2023 |
| HUAWEI        | CREF-XX                     | Notebook    | [c5b6554c6b](https://linux-hardware.org/?probe=c5b6554c6b) | Aug 26, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [a29a9ddeb6](https://linux-hardware.org/?probe=a29a9ddeb6) | Aug 26, 2023 |
| ASUSTek       | AT5NM10-I                   | Desktop     | [15edd1ec31](https://linux-hardware.org/?probe=15edd1ec31) | Aug 26, 2023 |
| Wortmann      | TERRA_MOBILE_1749           | Notebook    | [d58f29d427](https://linux-hardware.org/?probe=d58f29d427) | Aug 26, 2023 |
| MSI           | H81M-P33                    | Desktop     | [e86c3faf2e](https://linux-hardware.org/?probe=e86c3faf2e) | Aug 26, 2023 |
| Lenovo        | Legion 5 82B5               | Notebook    | [c154878ecd](https://linux-hardware.org/?probe=c154878ecd) | Aug 26, 2023 |
| HP            | 84F5                        | Mini pc     | [2ba73e7bda](https://linux-hardware.org/?probe=2ba73e7bda) | Aug 26, 2023 |
| Acer          | Aspire A315-56              | Notebook    | [e212f5bc28](https://linux-hardware.org/?probe=e212f5bc28) | Aug 25, 2023 |
| Valve         | Jupiter                     | Notebook    | [437c3eee58](https://linux-hardware.org/?probe=437c3eee58) | Aug 25, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [baa3bc61e9](https://linux-hardware.org/?probe=baa3bc61e9) | Aug 25, 2023 |
| HP            | 84F5                        | Mini pc     | [314beb9d40](https://linux-hardware.org/?probe=314beb9d40) | Aug 25, 2023 |
| HP            | ProBook 440 G3              | Notebook    | [0f16274ad6](https://linux-hardware.org/?probe=0f16274ad6) | Aug 25, 2023 |
| HP            | EliteBook 850 G5            | Notebook    | [2d3a15b432](https://linux-hardware.org/?probe=2d3a15b432) | Aug 25, 2023 |
| HP            | 859C                        | Desktop     | [978d715b29](https://linux-hardware.org/?probe=978d715b29) | Aug 25, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [1bc8a402b3](https://linux-hardware.org/?probe=1bc8a402b3) | Aug 25, 2023 |
| HUAWEI        | RLEF-XX                     | Notebook    | [b5c86f44b7](https://linux-hardware.org/?probe=b5c86f44b7) | Aug 25, 2023 |
| ASUSTek       | H97I-PLUS                   | Desktop     | [2c9e75e34a](https://linux-hardware.org/?probe=2c9e75e34a) | Aug 25, 2023 |
| ASUSTek       | P8Q77-M                     | Desktop     | [8445b944a5](https://linux-hardware.org/?probe=8445b944a5) | Aug 25, 2023 |
| Dell          | Precision 5480              | Notebook    | [c4f1e9b39b](https://linux-hardware.org/?probe=c4f1e9b39b) | Aug 25, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [255eeb3d65](https://linux-hardware.org/?probe=255eeb3d65) | Aug 25, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [26c7035d28](https://linux-hardware.org/?probe=26c7035d28) | Aug 25, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [e5317c3887](https://linux-hardware.org/?probe=e5317c3887) | Aug 25, 2023 |
| ASUSTek       | M4A87TD EVO                 | Desktop     | [70a6d20dbf](https://linux-hardware.org/?probe=70a6d20dbf) | Aug 25, 2023 |
| HP            | Laptop 17-by3xxx            | Notebook    | [081372c3c4](https://linux-hardware.org/?probe=081372c3c4) | Aug 25, 2023 |
| Fujitsu       | LIFEBOOK A530               | Notebook    | [01c6935221](https://linux-hardware.org/?probe=01c6935221) | Aug 25, 2023 |
| Acer          | Aspire VN7-793G             | Notebook    | [5d748b1e22](https://linux-hardware.org/?probe=5d748b1e22) | Aug 25, 2023 |
| TUXEDO        | Unknown                     | Notebook    | [13bb5e57f4](https://linux-hardware.org/?probe=13bb5e57f4) | Aug 25, 2023 |
| AZW           | SER V2.0                    | Mini pc     | [be2b9dc5de](https://linux-hardware.org/?probe=be2b9dc5de) | Aug 25, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [3b3b6c16a0](https://linux-hardware.org/?probe=3b3b6c16a0) | Aug 25, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [34a73b6b37](https://linux-hardware.org/?probe=34a73b6b37) | Aug 25, 2023 |
| Lenovo        | ThinkPad W530 2447GW3       | Notebook    | [3438523e90](https://linux-hardware.org/?probe=3438523e90) | Aug 25, 2023 |
| Lenovo        | ThinkPad W530 2447GW3       | Notebook    | [72d1d1be0b](https://linux-hardware.org/?probe=72d1d1be0b) | Aug 24, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [85984e2830](https://linux-hardware.org/?probe=85984e2830) | Aug 24, 2023 |
| Gigabyte      | P35-DS3R                    | Desktop     | [798717deb6](https://linux-hardware.org/?probe=798717deb6) | Aug 24, 2023 |
| TERRA         | TERRAPC                     | Notebook    | [b33c6ce6e8](https://linux-hardware.org/?probe=b33c6ce6e8) | Aug 24, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U30... | Notebook    | [24c8bedd43](https://linux-hardware.org/?probe=24c8bedd43) | Aug 24, 2023 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [a2b21f0903](https://linux-hardware.org/?probe=a2b21f0903) | Aug 24, 2023 |
| Dell          | Inspiron 5759               | Notebook    | [bf7413fc5f](https://linux-hardware.org/?probe=bf7413fc5f) | Aug 24, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [c86651dbd3](https://linux-hardware.org/?probe=c86651dbd3) | Aug 24, 2023 |
| Acer          | Aspire VN7-571G             | Notebook    | [c35939bf03](https://linux-hardware.org/?probe=c35939bf03) | Aug 24, 2023 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | Mini pc     | [329842693e](https://linux-hardware.org/?probe=329842693e) | Aug 24, 2023 |
| Lenovo        | ThinkPad T560 20FJS18V00    | Notebook    | [5f18850003](https://linux-hardware.org/?probe=5f18850003) | Aug 24, 2023 |
| Lenovo        | ThinkPad T560 20FJS18V00    | Notebook    | [de37c3c7eb](https://linux-hardware.org/?probe=de37c3c7eb) | Aug 24, 2023 |
| Acer          | Aspire VN7-571G             | Notebook    | [de43925ba1](https://linux-hardware.org/?probe=de43925ba1) | Aug 24, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [ce5f964a0c](https://linux-hardware.org/?probe=ce5f964a0c) | Aug 24, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | Desktop     | [c15e2ed529](https://linux-hardware.org/?probe=c15e2ed529) | Aug 24, 2023 |
| Dell          | Precision M4500             | Notebook    | [98b37ce3a4](https://linux-hardware.org/?probe=98b37ce3a4) | Aug 24, 2023 |
| ASUSTek       | PN52                        | Mini pc     | [97d1d3f664](https://linux-hardware.org/?probe=97d1d3f664) | Aug 23, 2023 |
| ASRock        | FP6D4-P1                    | Desktop     | [722789f2ac](https://linux-hardware.org/?probe=722789f2ac) | Aug 23, 2023 |
| Gigabyte      | G5 GE                       | Notebook    | [357d34e951](https://linux-hardware.org/?probe=357d34e951) | Aug 23, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [fae1a274d9](https://linux-hardware.org/?probe=fae1a274d9) | Aug 23, 2023 |
| Thomson       | GENEO14C-4WH128             | Notebook    | [b145cbea54](https://linux-hardware.org/?probe=b145cbea54) | Aug 23, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [acc3f87d28](https://linux-hardware.org/?probe=acc3f87d28) | Aug 23, 2023 |
| Apple         | MacBookPro8,3               | Notebook    | [3fa6f3e446](https://linux-hardware.org/?probe=3fa6f3e446) | Aug 23, 2023 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [6811a2231b](https://linux-hardware.org/?probe=6811a2231b) | Aug 23, 2023 |
| TUXEDO        | Pulse 15 Gen2               | Notebook    | [da78ac9e8e](https://linux-hardware.org/?probe=da78ac9e8e) | Aug 23, 2023 |
| HP            | Laptop 17-cp2xxx            | Notebook    | [e2a5a3b1d0](https://linux-hardware.org/?probe=e2a5a3b1d0) | Aug 23, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [2f4fd95449](https://linux-hardware.org/?probe=2f4fd95449) | Aug 23, 2023 |
| ASRock        | 990FX Killer                | Desktop     | [20a65c4f0d](https://linux-hardware.org/?probe=20a65c4f0d) | Aug 23, 2023 |
| Panasonic     | CFMX4-1                     | Notebook    | [fd352acae8](https://linux-hardware.org/?probe=fd352acae8) | Aug 23, 2023 |
| HP            | Victus by Laptop 16-e1xx... | Notebook    | [d31df9053b](https://linux-hardware.org/?probe=d31df9053b) | Aug 23, 2023 |
| ASRock        | Z77 Extreme6                | Desktop     | [6477cdd647](https://linux-hardware.org/?probe=6477cdd647) | Aug 23, 2023 |
| Dell          | Precision 7780              | Notebook    | [a0627634fc](https://linux-hardware.org/?probe=a0627634fc) | Aug 23, 2023 |
| Fujitsu       | LIFEBOOK E736               | Notebook    | [e5e47ca15c](https://linux-hardware.org/?probe=e5e47ca15c) | Aug 23, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [6fa7d1e35d](https://linux-hardware.org/?probe=6fa7d1e35d) | Aug 23, 2023 |
| Lenovo        | ThinkPad P51s 20HCS0660Y    | Notebook    | [e5c40536c3](https://linux-hardware.org/?probe=e5c40536c3) | Aug 23, 2023 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [36e12540f3](https://linux-hardware.org/?probe=36e12540f3) | Aug 23, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [5663c30e5e](https://linux-hardware.org/?probe=5663c30e5e) | Aug 23, 2023 |
| HP            | x2 210 G2                   | Tablet      | [a1ffe6462e](https://linux-hardware.org/?probe=a1ffe6462e) | Aug 23, 2023 |
| HP            | EliteBook 2540p             | Notebook    | [62f32fc664](https://linux-hardware.org/?probe=62f32fc664) | Aug 22, 2023 |
| ASRock        | H310CM-ITX/ac               | Desktop     | [5725adebf5](https://linux-hardware.org/?probe=5725adebf5) | Aug 22, 2023 |
| Medion        | E6417 MD99252               | Notebook    | [029d764eeb](https://linux-hardware.org/?probe=029d764eeb) | Aug 22, 2023 |
| Acer          | Nitro N50-600 V:1.1         | Desktop     | [6e915a1913](https://linux-hardware.org/?probe=6e915a1913) | Aug 22, 2023 |
| Medion        | B460H6-EM                   | Desktop     | [7da77cb4d7](https://linux-hardware.org/?probe=7da77cb4d7) | Aug 22, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [5a9553b9a2](https://linux-hardware.org/?probe=5a9553b9a2) | Aug 22, 2023 |
| HP            | Laptop 17-cp3xxx            | Notebook    | [d5c63b82fb](https://linux-hardware.org/?probe=d5c63b82fb) | Aug 22, 2023 |
| Dell          | Precision M4500             | Notebook    | [71b77267fd](https://linux-hardware.org/?probe=71b77267fd) | Aug 22, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [3a3b362bd0](https://linux-hardware.org/?probe=3a3b362bd0) | Aug 22, 2023 |
| HP            | x2 210 G2                   | Tablet      | [c0b004af0e](https://linux-hardware.org/?probe=c0b004af0e) | Aug 22, 2023 |
| Acer          | Aspire V3-771               | Notebook    | [0a5af3a07b](https://linux-hardware.org/?probe=0a5af3a07b) | Aug 22, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [ec3c1320fd](https://linux-hardware.org/?probe=ec3c1320fd) | Aug 22, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [888f62077c](https://linux-hardware.org/?probe=888f62077c) | Aug 22, 2023 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [bf401f98a7](https://linux-hardware.org/?probe=bf401f98a7) | Aug 22, 2023 |
| Supermicro    | H12SSL-i                    | Desktop     | [0981b40b5c](https://linux-hardware.org/?probe=0981b40b5c) | Aug 22, 2023 |
| Dell          | 06D7TR A00                  | Desktop     | [6e44011ff7](https://linux-hardware.org/?probe=6e44011ff7) | Aug 22, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [b460d0aa2d](https://linux-hardware.org/?probe=b460d0aa2d) | Aug 22, 2023 |
| HP            | 859C                        | Desktop     | [63f9e00825](https://linux-hardware.org/?probe=63f9e00825) | Aug 22, 2023 |
| Dell          | 06D7TR A00                  | Desktop     | [f80faa8301](https://linux-hardware.org/?probe=f80faa8301) | Aug 22, 2023 |
| Win Elemen... | M9                          | Desktop     | [f161447dfc](https://linux-hardware.org/?probe=f161447dfc) | Aug 22, 2023 |
| HP            | 255 G5                      | Notebook    | [d7087d2b8f](https://linux-hardware.org/?probe=d7087d2b8f) | Aug 22, 2023 |
| HP            | 255 G5                      | Notebook    | [b16f43457c](https://linux-hardware.org/?probe=b16f43457c) | Aug 22, 2023 |
| HP            | 18E7                        | Desktop     | [c750e8d3e6](https://linux-hardware.org/?probe=c750e8d3e6) | Aug 22, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [443006ec08](https://linux-hardware.org/?probe=443006ec08) | Aug 22, 2023 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [625ff7df38](https://linux-hardware.org/?probe=625ff7df38) | Aug 22, 2023 |
| Raspberry ... | Raspberry Pi 400 Rev 1.1    | Soc         | [9d52ec36c5](https://linux-hardware.org/?probe=9d52ec36c5) | Aug 22, 2023 |
| Lenovo        | ThinkPad P51s 20HCS0660Y    | Notebook    | [0f2259e2b8](https://linux-hardware.org/?probe=0f2259e2b8) | Aug 22, 2023 |
| Raspberry ... | Raspberry Pi 400 Rev 1.1    | Soc         | [a114ce9928](https://linux-hardware.org/?probe=a114ce9928) | Aug 22, 2023 |
| Lenovo        | ThinkPad T470s 20HGS09L2... | Notebook    | [55974065ac](https://linux-hardware.org/?probe=55974065ac) | Aug 22, 2023 |
| ASUSTek       | ROG Maximus Z790 HERO       | Desktop     | [b4aa1b8daa](https://linux-hardware.org/?probe=b4aa1b8daa) | Aug 22, 2023 |
| Medion        | Akoya P7818                 | Notebook    | [770447675e](https://linux-hardware.org/?probe=770447675e) | Aug 21, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [fdfc3b92f9](https://linux-hardware.org/?probe=fdfc3b92f9) | Aug 21, 2023 |
| Dell          | 0V52N7 A02                  | Server      | [5f5f76ff98](https://linux-hardware.org/?probe=5f5f76ff98) | Aug 21, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [75776f43bf](https://linux-hardware.org/?probe=75776f43bf) | Aug 21, 2023 |
| Shuttle       | FH170                       | Desktop     | [f96106ab4c](https://linux-hardware.org/?probe=f96106ab4c) | Aug 21, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [fa1f2a4b75](https://linux-hardware.org/?probe=fa1f2a4b75) | Aug 21, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [4bc2673b83](https://linux-hardware.org/?probe=4bc2673b83) | Aug 21, 2023 |
| ASUSTek       | P8Z68-V GEN3                | Desktop     | [aad70f30d7](https://linux-hardware.org/?probe=aad70f30d7) | Aug 21, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [cdbe8c2f04](https://linux-hardware.org/?probe=cdbe8c2f04) | Aug 21, 2023 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [33e8c204b0](https://linux-hardware.org/?probe=33e8c204b0) | Aug 21, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [156c7f4eae](https://linux-hardware.org/?probe=156c7f4eae) | Aug 21, 2023 |
| Dell          | Latitude E6330              | Notebook    | [cd36022d48](https://linux-hardware.org/?probe=cd36022d48) | Aug 21, 2023 |
| MSI           | GE63 Raider RGB 8RF         | Notebook    | [dd12e382c8](https://linux-hardware.org/?probe=dd12e382c8) | Aug 21, 2023 |
| HP            | 822A                        | Desktop     | [1bb168776a](https://linux-hardware.org/?probe=1bb168776a) | Aug 21, 2023 |
| Dell          | Inspiron 16 Plus 7620       | Notebook    | [b15b51b481](https://linux-hardware.org/?probe=b15b51b481) | Aug 21, 2023 |
| Dell          | 0D883F A04                  | Desktop     | [f76b91821d](https://linux-hardware.org/?probe=f76b91821d) | Aug 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2e4f8c0f7c](https://linux-hardware.org/?probe=2e4f8c0f7c) | Aug 21, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [a7cd220563](https://linux-hardware.org/?probe=a7cd220563) | Aug 21, 2023 |
| Fujitsu       | D3602-A1 S26361-D3602-A1    | Desktop     | [8144c6d466](https://linux-hardware.org/?probe=8144c6d466) | Aug 21, 2023 |
| Medion        | WIM2210                     | Notebook    | [5ef8675128](https://linux-hardware.org/?probe=5ef8675128) | Aug 21, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | Notebook    | [e6dceda4bc](https://linux-hardware.org/?probe=e6dceda4bc) | Aug 21, 2023 |
| AZW           | GTR V11                     | Desktop     | [9aefbc3e69](https://linux-hardware.org/?probe=9aefbc3e69) | Aug 20, 2023 |
| ASUSTek       | PRIME N100I-D D4            | Desktop     | [34ef0ea7ff](https://linux-hardware.org/?probe=34ef0ea7ff) | Aug 20, 2023 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [2e8e2ad7f5](https://linux-hardware.org/?probe=2e8e2ad7f5) | Aug 20, 2023 |
| MSI           | MAG B550M MORTAR            | Desktop     | [1c177ea7e4](https://linux-hardware.org/?probe=1c177ea7e4) | Aug 20, 2023 |
| Medion        | DEFENDER E10                | Notebook    | [8434727e07](https://linux-hardware.org/?probe=8434727e07) | Aug 20, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [f8f877ce04](https://linux-hardware.org/?probe=f8f877ce04) | Aug 20, 2023 |
| Fujitsu       | D3223-C1 S26361-D3223-C1    | Desktop     | [bca7b6990c](https://linux-hardware.org/?probe=bca7b6990c) | Aug 20, 2023 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | Desktop     | [9f7605c000](https://linux-hardware.org/?probe=9f7605c000) | Aug 20, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [a8a0c22567](https://linux-hardware.org/?probe=a8a0c22567) | Aug 20, 2023 |
| ASRock        | B550M-HDV                   | Desktop     | [2e8b5e3b34](https://linux-hardware.org/?probe=2e8b5e3b34) | Aug 20, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [0f2cba56cc](https://linux-hardware.org/?probe=0f2cba56cc) | Aug 20, 2023 |
| Lenovo        | Yoga 920-13IKB 80Y7         | Convertible | [4456ccbc85](https://linux-hardware.org/?probe=4456ccbc85) | Aug 20, 2023 |
| Acer          | Aspire V3-771               | Notebook    | [ccbacb7123](https://linux-hardware.org/?probe=ccbacb7123) | Aug 20, 2023 |
| Medion        | D3F3-EM                     | Desktop     | [3a91d248b9](https://linux-hardware.org/?probe=3a91d248b9) | Aug 20, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [fee22676ae](https://linux-hardware.org/?probe=fee22676ae) | Aug 20, 2023 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [7463f81c62](https://linux-hardware.org/?probe=7463f81c62) | Aug 20, 2023 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [e182ba305d](https://linux-hardware.org/?probe=e182ba305d) | Aug 20, 2023 |
| HP            | 18E7                        | Desktop     | [0bd07157fb](https://linux-hardware.org/?probe=0bd07157fb) | Aug 20, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [b2e1bdd7a8](https://linux-hardware.org/?probe=b2e1bdd7a8) | Aug 20, 2023 |
| Schenker      | XMG PRO (E23)               | Notebook    | [9b1639077c](https://linux-hardware.org/?probe=9b1639077c) | Aug 20, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [aed7eacff0](https://linux-hardware.org/?probe=aed7eacff0) | Aug 20, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [3803f61627](https://linux-hardware.org/?probe=3803f61627) | Aug 20, 2023 |
| ASUSTek       | PRIME N100I-D D4            | Desktop     | [101202101b](https://linux-hardware.org/?probe=101202101b) | Aug 19, 2023 |
| MSI           | B350 TOMAHAWK               | Desktop     | [8b6ec2d9e2](https://linux-hardware.org/?probe=8b6ec2d9e2) | Aug 19, 2023 |
| Hardkernel    | ODROID-N2Plus               | Soc         | [ae3c86cccf](https://linux-hardware.org/?probe=ae3c86cccf) | Aug 19, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | Notebook    | [a11383f5b3](https://linux-hardware.org/?probe=a11383f5b3) | Aug 19, 2023 |
| Medion        | D3F3-EM                     | Desktop     | [ccd1591521](https://linux-hardware.org/?probe=ccd1591521) | Aug 19, 2023 |
| ASRock        | Q1900M                      | Desktop     | [1e1e781c93](https://linux-hardware.org/?probe=1e1e781c93) | Aug 19, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [679cf99998](https://linux-hardware.org/?probe=679cf99998) | Aug 19, 2023 |
| MSI           | B350 TOMAHAWK               | Desktop     | [cf83ce90b0](https://linux-hardware.org/?probe=cf83ce90b0) | Aug 19, 2023 |
| ASRock        | Z270 Pro4                   | Desktop     | [de0587ccf3](https://linux-hardware.org/?probe=de0587ccf3) | Aug 19, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [12ec49f019](https://linux-hardware.org/?probe=12ec49f019) | Aug 19, 2023 |
| HP            | 8055                        | Desktop     | [f50f16cbd2](https://linux-hardware.org/?probe=f50f16cbd2) | Aug 19, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [816ff5d908](https://linux-hardware.org/?probe=816ff5d908) | Aug 19, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [79af5911ee](https://linux-hardware.org/?probe=79af5911ee) | Aug 19, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [d172fc10d8](https://linux-hardware.org/?probe=d172fc10d8) | Aug 19, 2023 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [60545dcc97](https://linux-hardware.org/?probe=60545dcc97) | Aug 19, 2023 |
| Notebook      | NL5xNU                      | Notebook    | [768e7b97fc](https://linux-hardware.org/?probe=768e7b97fc) | Aug 19, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [b7347b4f7c](https://linux-hardware.org/?probe=b7347b4f7c) | Aug 19, 2023 |
| Toshiba       | Satellite C870-19R          | Notebook    | [f351a7a707](https://linux-hardware.org/?probe=f351a7a707) | Aug 19, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [1e39da3f6e](https://linux-hardware.org/?probe=1e39da3f6e) | Aug 18, 2023 |
| Lenovo        | ThinkPad X270 20HMS12K00    | Notebook    | [a58174338d](https://linux-hardware.org/?probe=a58174338d) | Aug 18, 2023 |
| Acer          | Extensa 5235                | Notebook    | [1dc9843f33](https://linux-hardware.org/?probe=1dc9843f33) | Aug 18, 2023 |
| Acer          | Aspire VN7-793G             | Notebook    | [b88e1a5605](https://linux-hardware.org/?probe=b88e1a5605) | Aug 18, 2023 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [d3586db858](https://linux-hardware.org/?probe=d3586db858) | Aug 18, 2023 |
| ASRock        | B660M Steel Legend          | Desktop     | [31c15ac9dd](https://linux-hardware.org/?probe=31c15ac9dd) | Aug 18, 2023 |
| Dell          | 0X8582                      | Desktop     | [c9661782e6](https://linux-hardware.org/?probe=c9661782e6) | Aug 18, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [bb62633b47](https://linux-hardware.org/?probe=bb62633b47) | Aug 18, 2023 |
| Lenovo        | IdeaPad Pro 5 14APH8 83A... | Notebook    | [f7d0bbc3d9](https://linux-hardware.org/?probe=f7d0bbc3d9) | Aug 18, 2023 |
| ASUSTek       | X550ZA                      | Notebook    | [7f23195701](https://linux-hardware.org/?probe=7f23195701) | Aug 18, 2023 |
| Lenovo        | ThinkPad T420 418063G       | Notebook    | [f8e7a666cc](https://linux-hardware.org/?probe=f8e7a666cc) | Aug 18, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [3c8853c045](https://linux-hardware.org/?probe=3c8853c045) | Aug 18, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | Notebook    | [8bc31c82d1](https://linux-hardware.org/?probe=8bc31c82d1) | Aug 18, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [beddeba8b6](https://linux-hardware.org/?probe=beddeba8b6) | Aug 18, 2023 |
| System76      | Pangolin                    | Notebook    | [5191e3a345](https://linux-hardware.org/?probe=5191e3a345) | Aug 18, 2023 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | Desktop     | [e9b5fbc6ba](https://linux-hardware.org/?probe=e9b5fbc6ba) | Aug 18, 2023 |
| Schenker      | MEDIA (M22)                 | Notebook    | [463903cc03](https://linux-hardware.org/?probe=463903cc03) | Aug 18, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [e66c463188](https://linux-hardware.org/?probe=e66c463188) | Aug 18, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [e37325dbc2](https://linux-hardware.org/?probe=e37325dbc2) | Aug 18, 2023 |
| Toshiba       | Satellite C870-19R          | Notebook    | [f906e0ccdb](https://linux-hardware.org/?probe=f906e0ccdb) | Aug 18, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [79d5cb1a00](https://linux-hardware.org/?probe=79d5cb1a00) | Aug 18, 2023 |
| Alienware     | 17 R4                       | Notebook    | [c16cb58f29](https://linux-hardware.org/?probe=c16cb58f29) | Aug 18, 2023 |
| Medion        | S14406                      | Convertible | [c510f62cbb](https://linux-hardware.org/?probe=c510f62cbb) | Aug 18, 2023 |
| Dell          | Latitude E5470              | Notebook    | [42398338fe](https://linux-hardware.org/?probe=42398338fe) | Aug 18, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [7092a32ce5](https://linux-hardware.org/?probe=7092a32ce5) | Aug 17, 2023 |
| Lenovo        | IdeaPad Pro 5 14APH8 83A... | Notebook    | [df194863d1](https://linux-hardware.org/?probe=df194863d1) | Aug 17, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | Notebook    | [e2e5abcbbd](https://linux-hardware.org/?probe=e2e5abcbbd) | Aug 17, 2023 |
| MSI           | Z77A-G45                    | Desktop     | [b72192373b](https://linux-hardware.org/?probe=b72192373b) | Aug 17, 2023 |
| Lenovo        | IdeaPad Pro 5 14APH8 83A... | Notebook    | [87a6bd39ae](https://linux-hardware.org/?probe=87a6bd39ae) | Aug 17, 2023 |
| HP            | EliteBook 8540p             | Notebook    | [ab0d47228c](https://linux-hardware.org/?probe=ab0d47228c) | Aug 17, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HM... | Notebook    | [d3eadf71c1](https://linux-hardware.org/?probe=d3eadf71c1) | Aug 17, 2023 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | Desktop     | [9c90e63339](https://linux-hardware.org/?probe=9c90e63339) | Aug 17, 2023 |
| Acer          | Nitro AN517-41              | Notebook    | [a925a31ef1](https://linux-hardware.org/?probe=a925a31ef1) | Aug 17, 2023 |
| Acer          | Aspire Z5710                | All in one  | [10e9ce60c2](https://linux-hardware.org/?probe=10e9ce60c2) | Aug 17, 2023 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [b63e7d3466](https://linux-hardware.org/?probe=b63e7d3466) | Aug 17, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | Desktop     | [cb98230ea1](https://linux-hardware.org/?probe=cb98230ea1) | Aug 17, 2023 |
| Acer          | Aspire E1-571G              | Notebook    | [6aec4cb61e](https://linux-hardware.org/?probe=6aec4cb61e) | Aug 17, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | Desktop     | [a2ff8100b0](https://linux-hardware.org/?probe=a2ff8100b0) | Aug 17, 2023 |
| ASUSTek       | F2A55-M LK                  | Desktop     | [c2acb99219](https://linux-hardware.org/?probe=c2acb99219) | Aug 17, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [af0ba5f26c](https://linux-hardware.org/?probe=af0ba5f26c) | Aug 17, 2023 |
| Schenker      | XMG CORE 15(M20, RTX 206... | Notebook    | [81dcd4b2dd](https://linux-hardware.org/?probe=81dcd4b2dd) | Aug 17, 2023 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [4c36ef643e](https://linux-hardware.org/?probe=4c36ef643e) | Aug 17, 2023 |
| Shuttle       | DS20U                       | Desktop     | [3a1ceb6021](https://linux-hardware.org/?probe=3a1ceb6021) | Aug 17, 2023 |
| Intel         | SandyBridge Platform        | Notebook    | [0e1961a9b3](https://linux-hardware.org/?probe=0e1961a9b3) | Aug 17, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [f0b1f6f364](https://linux-hardware.org/?probe=f0b1f6f364) | Aug 17, 2023 |
| MSI           | MPG B460I GAMING EDGE WI... | Desktop     | [2da4b77f8a](https://linux-hardware.org/?probe=2da4b77f8a) | Aug 17, 2023 |
| HP            | 2B43                        | Desktop     | [2c3ffc174e](https://linux-hardware.org/?probe=2c3ffc174e) | Aug 17, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [ae88c56896](https://linux-hardware.org/?probe=ae88c56896) | Aug 17, 2023 |
| Fujitsu       | D2828-A2 S26361-D2828-A2    | Desktop     | [bfc46e751d](https://linux-hardware.org/?probe=bfc46e751d) | Aug 17, 2023 |
| Lenovo        | ThinkPad T480s 20L7001VG... | Notebook    | [b0b2f8a7e1](https://linux-hardware.org/?probe=b0b2f8a7e1) | Aug 16, 2023 |
| Lenovo        | ThinkPad T480s 20L7001VG... | Notebook    | [07b5827382](https://linux-hardware.org/?probe=07b5827382) | Aug 16, 2023 |
| HP            | Pavilion g7                 | Notebook    | [403fee3152](https://linux-hardware.org/?probe=403fee3152) | Aug 16, 2023 |
| Gigabyte      | H81M-D2V                    | Desktop     | [68639ddf06](https://linux-hardware.org/?probe=68639ddf06) | Aug 16, 2023 |
| ASUSTek       | X55A                        | Notebook    | [03099661ec](https://linux-hardware.org/?probe=03099661ec) | Aug 16, 2023 |
| Packard Be... | EasyNote ENTG81BA           | Notebook    | [086cffe9b9](https://linux-hardware.org/?probe=086cffe9b9) | Aug 16, 2023 |
| Dell          | XPS 9320                    | Notebook    | [f9d12ed2ff](https://linux-hardware.org/?probe=f9d12ed2ff) | Aug 16, 2023 |
| Dell          | 0F642F A00                  | Desktop     | [910bc81fd1](https://linux-hardware.org/?probe=910bc81fd1) | Aug 16, 2023 |
| ASUSTek       | F2A55-M LK                  | Desktop     | [e14c769e1b](https://linux-hardware.org/?probe=e14c769e1b) | Aug 16, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [50b5957370](https://linux-hardware.org/?probe=50b5957370) | Aug 16, 2023 |
| ASRock        | H61M-DGS R2.0               | Desktop     | [ccd21d7858](https://linux-hardware.org/?probe=ccd21d7858) | Aug 16, 2023 |
| Lenovo        | ThinkBook 14s Yoga G3 IR... | Convertible | [74da3f5482](https://linux-hardware.org/?probe=74da3f5482) | Aug 16, 2023 |
| Gigabyte      | H510M S2H                   | Desktop     | [e5661bef5b](https://linux-hardware.org/?probe=e5661bef5b) | Aug 16, 2023 |
| HP            | Notebook                    | Notebook    | [bc495ab997](https://linux-hardware.org/?probe=bc495ab997) | Aug 16, 2023 |
| Dell          | Latitude E6430              | Notebook    | [87849c0e6c](https://linux-hardware.org/?probe=87849c0e6c) | Aug 16, 2023 |
| Lenovo        | Yoga 300-11IBY 80M0         | Notebook    | [6026ba6c8a](https://linux-hardware.org/?probe=6026ba6c8a) | Aug 16, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [9dee158ae4](https://linux-hardware.org/?probe=9dee158ae4) | Aug 16, 2023 |
| Lenovo        | ThinkPad X240 20AMS0J003    | Notebook    | [c60cb88cbc](https://linux-hardware.org/?probe=c60cb88cbc) | Aug 16, 2023 |
| Dell          | Latitude E5400              | Notebook    | [7d861c3812](https://linux-hardware.org/?probe=7d861c3812) | Aug 16, 2023 |
| Dell          | Latitude 5420               | Notebook    | [12d46be852](https://linux-hardware.org/?probe=12d46be852) | Aug 16, 2023 |
| Acer          | Aspire S5-371               | Notebook    | [210e2bbe4d](https://linux-hardware.org/?probe=210e2bbe4d) | Aug 16, 2023 |
| Lenovo        | ThinkPad L580 20LW000WGE    | Notebook    | [69e443b8a8](https://linux-hardware.org/?probe=69e443b8a8) | Aug 16, 2023 |
| Acer          | Aspire S5-371               | Notebook    | [c5b4372bbf](https://linux-hardware.org/?probe=c5b4372bbf) | Aug 16, 2023 |
| Schenker      | XMG CORE 15(M20, RTX 206... | Notebook    | [ca4998e0fe](https://linux-hardware.org/?probe=ca4998e0fe) | Aug 16, 2023 |
| Acer          | Aspire G7750                | Desktop     | [2ff2db272f](https://linux-hardware.org/?probe=2ff2db272f) | Aug 16, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [b31bf50c6e](https://linux-hardware.org/?probe=b31bf50c6e) | Aug 16, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [a247bcbeb2](https://linux-hardware.org/?probe=a247bcbeb2) | Aug 16, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [fc9b14b9cb](https://linux-hardware.org/?probe=fc9b14b9cb) | Aug 15, 2023 |
| ASRock        | B360M Pro4                  | Desktop     | [948ab98a6f](https://linux-hardware.org/?probe=948ab98a6f) | Aug 15, 2023 |
| Dell          | 007MXD A00                  | Mini pc     | [1eab959e9a](https://linux-hardware.org/?probe=1eab959e9a) | Aug 15, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [374096baa6](https://linux-hardware.org/?probe=374096baa6) | Aug 15, 2023 |
| Notebook      | W230ST                      | Notebook    | [2f56cbf689](https://linux-hardware.org/?probe=2f56cbf689) | Aug 15, 2023 |
| HP            | Elite x2 1012 G1            | Notebook    | [07f71a9888](https://linux-hardware.org/?probe=07f71a9888) | Aug 15, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [32a347b989](https://linux-hardware.org/?probe=32a347b989) | Aug 15, 2023 |
| Dell          | Latitude E5470              | Notebook    | [f09173281d](https://linux-hardware.org/?probe=f09173281d) | Aug 15, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [26a0de5b36](https://linux-hardware.org/?probe=26a0de5b36) | Aug 15, 2023 |
| Acer          | Aspire V5-573G              | Notebook    | [f53da0a40d](https://linux-hardware.org/?probe=f53da0a40d) | Aug 15, 2023 |
| Lenovo        | 3307 SDK0J40700 WIN 3258... | Mini pc     | [8f8507e0a9](https://linux-hardware.org/?probe=8f8507e0a9) | Aug 15, 2023 |
| Lenovo        | ThinkPad T490 20N2004EGE    | Notebook    | [11552492c0](https://linux-hardware.org/?probe=11552492c0) | Aug 15, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [4c24f10db4](https://linux-hardware.org/?probe=4c24f10db4) | Aug 15, 2023 |
| Valve         | Jupiter                     | Notebook    | [590dbcbd7b](https://linux-hardware.org/?probe=590dbcbd7b) | Aug 15, 2023 |
| Toshiba       | Satellite Pro C70-A         | Notebook    | [dbb00fe95b](https://linux-hardware.org/?probe=dbb00fe95b) | Aug 15, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [fd5dd48ab1](https://linux-hardware.org/?probe=fd5dd48ab1) | Aug 15, 2023 |
| ASUSTek       | N76VZ                       | Notebook    | [639ec473a1](https://linux-hardware.org/?probe=639ec473a1) | Aug 15, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [cd3074537b](https://linux-hardware.org/?probe=cd3074537b) | Aug 15, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [18060bdbd7](https://linux-hardware.org/?probe=18060bdbd7) | Aug 14, 2023 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [cbd08a7649](https://linux-hardware.org/?probe=cbd08a7649) | Aug 14, 2023 |
| Valve         | Jupiter                     | Notebook    | [acf70a31a9](https://linux-hardware.org/?probe=acf70a31a9) | Aug 14, 2023 |
| MSI           | U90/U100                    | Notebook    | [e8ae0fbcfb](https://linux-hardware.org/?probe=e8ae0fbcfb) | Aug 14, 2023 |
| Medion        | E6417 MD99252               | Notebook    | [893816496c](https://linux-hardware.org/?probe=893816496c) | Aug 14, 2023 |
| Medion        | MS-7800                     | Desktop     | [afab92f1e4](https://linux-hardware.org/?probe=afab92f1e4) | Aug 14, 2023 |
| Lenovo        | 1046 SBB1C50531 WIN 3556... | Desktop     | [f24668bfd7](https://linux-hardware.org/?probe=f24668bfd7) | Aug 14, 2023 |
| Gigabyte      | P35-DS3R                    | Desktop     | [4bb45d75da](https://linux-hardware.org/?probe=4bb45d75da) | Aug 14, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [5297d177b4](https://linux-hardware.org/?probe=5297d177b4) | Aug 14, 2023 |
| Acer          | Aspire A517-53G             | Notebook    | [ceebf749ba](https://linux-hardware.org/?probe=ceebf749ba) | Aug 14, 2023 |
| ASRock        | H97 Performance             | Desktop     | [54fc07549a](https://linux-hardware.org/?probe=54fc07549a) | Aug 14, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | Notebook    | [bbe00bbe48](https://linux-hardware.org/?probe=bbe00bbe48) | Aug 14, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [0b194349eb](https://linux-hardware.org/?probe=0b194349eb) | Aug 14, 2023 |
| Acer          | Aspire E5-571G              | Notebook    | [f523831970](https://linux-hardware.org/?probe=f523831970) | Aug 14, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [10f2a6448d](https://linux-hardware.org/?probe=10f2a6448d) | Aug 14, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [29aa72820d](https://linux-hardware.org/?probe=29aa72820d) | Aug 14, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [e9b2347b46](https://linux-hardware.org/?probe=e9b2347b46) | Aug 14, 2023 |
| Gigabyte      | B760 GAMING X AX            | Desktop     | [fd4109923b](https://linux-hardware.org/?probe=fd4109923b) | Aug 14, 2023 |
| Gigabyte      | B760 GAMING X AX            | Desktop     | [c2d8da14dd](https://linux-hardware.org/?probe=c2d8da14dd) | Aug 14, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [aadb9e5aab](https://linux-hardware.org/?probe=aadb9e5aab) | Aug 14, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [e2fadc37f2](https://linux-hardware.org/?probe=e2fadc37f2) | Aug 14, 2023 |
| Unknown       | CN700-8237                  | Desktop     | [5890f075f7](https://linux-hardware.org/?probe=5890f075f7) | Aug 13, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | Desktop     | [b0e10f6505](https://linux-hardware.org/?probe=b0e10f6505) | Aug 13, 2023 |
| Lenovo        | ThinkPad X220 4290EC5       | Notebook    | [a3982248d3](https://linux-hardware.org/?probe=a3982248d3) | Aug 13, 2023 |
| Fujitsu       | D3223-A1 S26361-D3223-A1    | Desktop     | [9862e96420](https://linux-hardware.org/?probe=9862e96420) | Aug 13, 2023 |
| Lenovo        | ThinkPad E595 20NF0006GE    | Notebook    | [c9c068e82b](https://linux-hardware.org/?probe=c9c068e82b) | Aug 13, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [66bcc74be2](https://linux-hardware.org/?probe=66bcc74be2) | Aug 13, 2023 |
| Gigabyte      | B360HD3PLM-CF               | Desktop     | [650f840aa5](https://linux-hardware.org/?probe=650f840aa5) | Aug 13, 2023 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | Notebook    | [b6e2112ccb](https://linux-hardware.org/?probe=b6e2112ccb) | Aug 13, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [d1cd4f43fc](https://linux-hardware.org/?probe=d1cd4f43fc) | Aug 13, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [6fbaeffc1d](https://linux-hardware.org/?probe=6fbaeffc1d) | Aug 13, 2023 |
| Dell          | 0CRWCR A01                  | All in one  | [c7e0716355](https://linux-hardware.org/?probe=c7e0716355) | Aug 13, 2023 |
| Medion        | TJ4125                      | Desktop     | [e24dc34df5](https://linux-hardware.org/?probe=e24dc34df5) | Aug 13, 2023 |
| Acer          | Aspire A317-33              | Notebook    | [e069c1f3d5](https://linux-hardware.org/?probe=e069c1f3d5) | Aug 13, 2023 |
| Lenovo        | ThinkPad W530 24477V0       | Notebook    | [2e09955f2f](https://linux-hardware.org/?probe=2e09955f2f) | Aug 13, 2023 |
| Acer          | Aspire A315-51              | Notebook    | [c94361f09d](https://linux-hardware.org/?probe=c94361f09d) | Aug 13, 2023 |
| Acer          | Extensa 5220                | Notebook    | [fb3e613b5c](https://linux-hardware.org/?probe=fb3e613b5c) | Aug 13, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [396327d1fa](https://linux-hardware.org/?probe=396327d1fa) | Aug 13, 2023 |
| Acer          | Aspire E5-721               | Notebook    | [9a7018c6cb](https://linux-hardware.org/?probe=9a7018c6cb) | Aug 13, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [448534f935](https://linux-hardware.org/?probe=448534f935) | Aug 13, 2023 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [3d99363ed5](https://linux-hardware.org/?probe=3d99363ed5) | Aug 13, 2023 |
| HP            | 3048h                       | Desktop     | [482d637e99](https://linux-hardware.org/?probe=482d637e99) | Aug 13, 2023 |
| Foxconn       | TPS01                       | Desktop     | [8e5b20544d](https://linux-hardware.org/?probe=8e5b20544d) | Aug 13, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [06316c3471](https://linux-hardware.org/?probe=06316c3471) | Aug 13, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [dc72ce1b47](https://linux-hardware.org/?probe=dc72ce1b47) | Aug 13, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [e0e2f927ae](https://linux-hardware.org/?probe=e0e2f927ae) | Aug 13, 2023 |
| HP            | 82A5                        | Mini pc     | [de3ae5a3fd](https://linux-hardware.org/?probe=de3ae5a3fd) | Aug 13, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | Notebook    | [b0524c4203](https://linux-hardware.org/?probe=b0524c4203) | Aug 13, 2023 |
| Acer          | Aspire 7520                 | Notebook    | [7e84fe60a8](https://linux-hardware.org/?probe=7e84fe60a8) | Aug 13, 2023 |
| Gigabyte      | H81M-D2V                    | Desktop     | [2996bc5d6c](https://linux-hardware.org/?probe=2996bc5d6c) | Aug 13, 2023 |
| Dell          | XPS 13 9300                 | Notebook    | [ed549bc47c](https://linux-hardware.org/?probe=ed549bc47c) | Aug 12, 2023 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [4d954b8546](https://linux-hardware.org/?probe=4d954b8546) | Aug 12, 2023 |
| MSI           | Z97 GAMING 7                | Desktop     | [8414f16824](https://linux-hardware.org/?probe=8414f16824) | Aug 12, 2023 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [b8c62e2fe3](https://linux-hardware.org/?probe=b8c62e2fe3) | Aug 12, 2023 |
| Toshiba       | Satellite C50D-B            | Notebook    | [61f00a0418](https://linux-hardware.org/?probe=61f00a0418) | Aug 12, 2023 |
| HP            | ZBook Studio x360 G5        | Convertible | [b499b34ebf](https://linux-hardware.org/?probe=b499b34ebf) | Aug 12, 2023 |
| ASUSTek       | Z170-K                      | Desktop     | [689401dab4](https://linux-hardware.org/?probe=689401dab4) | Aug 12, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [151c51f46f](https://linux-hardware.org/?probe=151c51f46f) | Aug 12, 2023 |
| ASRock        | 960GM/U3S3 FX               | Desktop     | [c2e2948843](https://linux-hardware.org/?probe=c2e2948843) | Aug 12, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [6289a9e628](https://linux-hardware.org/?probe=6289a9e628) | Aug 12, 2023 |
| ASRock        | 960GM/U3S3 FX               | Desktop     | [807a844b61](https://linux-hardware.org/?probe=807a844b61) | Aug 12, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [71f554fd2c](https://linux-hardware.org/?probe=71f554fd2c) | Aug 12, 2023 |
| BESSTAR Te... | TH50                        | Desktop     | [dd2c1243af](https://linux-hardware.org/?probe=dd2c1243af) | Aug 12, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [f1aa84a40b](https://linux-hardware.org/?probe=f1aa84a40b) | Aug 12, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [edd42a9a6d](https://linux-hardware.org/?probe=edd42a9a6d) | Aug 12, 2023 |
| ASRock        | H61M-DGS R2.0               | Desktop     | [6af1365446](https://linux-hardware.org/?probe=6af1365446) | Aug 12, 2023 |
| ASRock        | H61M-DGS R2.0               | Desktop     | [70e9fe8cdb](https://linux-hardware.org/?probe=70e9fe8cdb) | Aug 12, 2023 |
| Dell          | Vostro 15-3568              | Notebook    | [b422d7c8cc](https://linux-hardware.org/?probe=b422d7c8cc) | Aug 12, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [756901f27f](https://linux-hardware.org/?probe=756901f27f) | Aug 12, 2023 |
| ASUSTek       | M5A78L-M LE                 | Desktop     | [a68db843ea](https://linux-hardware.org/?probe=a68db843ea) | Aug 12, 2023 |
| Valve         | Jupiter                     | Notebook    | [61e105aa9d](https://linux-hardware.org/?probe=61e105aa9d) | Aug 12, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [da8cf53467](https://linux-hardware.org/?probe=da8cf53467) | Aug 12, 2023 |
| Dell          | Latitude E7270              | Notebook    | [63fd1b0d6b](https://linux-hardware.org/?probe=63fd1b0d6b) | Aug 12, 2023 |
| ASRock        | 970A-G                      | Desktop     | [5a2b77eaee](https://linux-hardware.org/?probe=5a2b77eaee) | Aug 12, 2023 |
| Acer          | Extensa 215-55              | Notebook    | [aea9ada5e8](https://linux-hardware.org/?probe=aea9ada5e8) | Aug 11, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [ab2473ff49](https://linux-hardware.org/?probe=ab2473ff49) | Aug 11, 2023 |
| Biostar       | B660GTQ                     | Desktop     | [520d57cadc](https://linux-hardware.org/?probe=520d57cadc) | Aug 11, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [65d55091fa](https://linux-hardware.org/?probe=65d55091fa) | Aug 11, 2023 |
| Gigabyte      | Z790 GAMING X AX            | Desktop     | [a6d2358585](https://linux-hardware.org/?probe=a6d2358585) | Aug 11, 2023 |
| Toshiba       | Satellite T110              | Notebook    | [ecb4e047b3](https://linux-hardware.org/?probe=ecb4e047b3) | Aug 11, 2023 |
| Acer          | Aspire E5-721               | Notebook    | [f4abfc94d4](https://linux-hardware.org/?probe=f4abfc94d4) | Aug 11, 2023 |
| Acer          | Extensa 215-55              | Notebook    | [036866525c](https://linux-hardware.org/?probe=036866525c) | Aug 11, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [7f2903e1a4](https://linux-hardware.org/?probe=7f2903e1a4) | Aug 11, 2023 |
| Toshiba       | Satellite T110              | Notebook    | [8180105119](https://linux-hardware.org/?probe=8180105119) | Aug 11, 2023 |
| Medion        | P651x series                | Notebook    | [46505da47d](https://linux-hardware.org/?probe=46505da47d) | Aug 11, 2023 |
| Dell          | 0CRWCR A01                  | All in one  | [74283f31aa](https://linux-hardware.org/?probe=74283f31aa) | Aug 11, 2023 |
| HP            | Laptop 17-cp1xxx            | Notebook    | [ac523f4e3b](https://linux-hardware.org/?probe=ac523f4e3b) | Aug 11, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [320138e7f5](https://linux-hardware.org/?probe=320138e7f5) | Aug 11, 2023 |
| Acer          | Aspire G7713                | Desktop     | [cb79bdce06](https://linux-hardware.org/?probe=cb79bdce06) | Aug 11, 2023 |
| Fujitsu       | LIFEBOOK S762               | Notebook    | [1ced8ae4d0](https://linux-hardware.org/?probe=1ced8ae4d0) | Aug 11, 2023 |
| Fujitsu       | LIFEBOOK S762               | Notebook    | [cb0b5cbd5d](https://linux-hardware.org/?probe=cb0b5cbd5d) | Aug 11, 2023 |
| ASUSTek       | ROG Strix G513QY            | Notebook    | [eacd0cc54d](https://linux-hardware.org/?probe=eacd0cc54d) | Aug 11, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [6a1d87f2aa](https://linux-hardware.org/?probe=6a1d87f2aa) | Aug 10, 2023 |
| Acer          | Aspire E1-731               | Notebook    | [b75a766ee9](https://linux-hardware.org/?probe=b75a766ee9) | Aug 10, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [eee160a070](https://linux-hardware.org/?probe=eee160a070) | Aug 10, 2023 |
| HP            | ProLiant ML115 G5           | Desktop     | [305ccefd04](https://linux-hardware.org/?probe=305ccefd04) | Aug 10, 2023 |
| ASRock        | H61M-DGS R2.0               | Desktop     | [4f05b77547](https://linux-hardware.org/?probe=4f05b77547) | Aug 10, 2023 |
| HP            | ProBook 430 G2              | Notebook    | [426901227d](https://linux-hardware.org/?probe=426901227d) | Aug 10, 2023 |
| Gigabyte      | B365M H                     | Desktop     | [b23c1e6e73](https://linux-hardware.org/?probe=b23c1e6e73) | Aug 10, 2023 |
| Lenovo        | ThinkPad T420 4236W1W       | Notebook    | [0b8fc947af](https://linux-hardware.org/?probe=0b8fc947af) | Aug 10, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [3e66a1f712](https://linux-hardware.org/?probe=3e66a1f712) | Aug 10, 2023 |
| Fujitsu       | LIFEBOOK A530               | Notebook    | [05e64e3a0a](https://linux-hardware.org/?probe=05e64e3a0a) | Aug 10, 2023 |
| Lenovo        | ThinkPad P51 20HH0015IX     | Notebook    | [77c11473b2](https://linux-hardware.org/?probe=77c11473b2) | Aug 10, 2023 |
| Acer          | Aspire E5-721               | Notebook    | [6743c7ca9d](https://linux-hardware.org/?probe=6743c7ca9d) | Aug 10, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [083e25221d](https://linux-hardware.org/?probe=083e25221d) | Aug 10, 2023 |
| MSI           | A320M PRO-VD/S              | Desktop     | [7f7c988470](https://linux-hardware.org/?probe=7f7c988470) | Aug 10, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [d5d888506b](https://linux-hardware.org/?probe=d5d888506b) | Aug 10, 2023 |
| Dell          | Inspiron 5415               | Notebook    | [69123aa283](https://linux-hardware.org/?probe=69123aa283) | Aug 10, 2023 |
| Dell          | Inspiron 5415               | Notebook    | [9c28979b9d](https://linux-hardware.org/?probe=9c28979b9d) | Aug 10, 2023 |
| ASUSTek       | H87-PRO                     | Desktop     | [817c5f9f93](https://linux-hardware.org/?probe=817c5f9f93) | Aug 09, 2023 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [b1a8fc0704](https://linux-hardware.org/?probe=b1a8fc0704) | Aug 09, 2023 |
| HP            | 859C                        | Desktop     | [24dd090f2c](https://linux-hardware.org/?probe=24dd090f2c) | Aug 09, 2023 |
| ASRock        | Z77 Extreme4                | Desktop     | [aadaab77db](https://linux-hardware.org/?probe=aadaab77db) | Aug 09, 2023 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [920797388b](https://linux-hardware.org/?probe=920797388b) | Aug 09, 2023 |
| ASUSTek       | Pro WS 565-ACE              | Desktop     | [3d9112e038](https://linux-hardware.org/?probe=3d9112e038) | Aug 09, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [d255d00dc8](https://linux-hardware.org/?probe=d255d00dc8) | Aug 09, 2023 |
| Wortmann      | TERRA_MOBILE_1749           | Notebook    | [3986ff4298](https://linux-hardware.org/?probe=3986ff4298) | Aug 09, 2023 |
| HP            | EliteBook 830 G8 Noteboo... | Notebook    | [2f7f77225a](https://linux-hardware.org/?probe=2f7f77225a) | Aug 09, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [13b739e83a](https://linux-hardware.org/?probe=13b739e83a) | Aug 09, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [90291816a0](https://linux-hardware.org/?probe=90291816a0) | Aug 09, 2023 |
| Dell          | 0272WF A00                  | Server      | [39abbc5ab8](https://linux-hardware.org/?probe=39abbc5ab8) | Aug 09, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [fdbe025351](https://linux-hardware.org/?probe=fdbe025351) | Aug 09, 2023 |
| ASUSTek       | ROG Strix G713IH_G713IH     | Notebook    | [352fd5fea3](https://linux-hardware.org/?probe=352fd5fea3) | Aug 09, 2023 |
| HP            | 8433 11                     | Desktop     | [93432b3df2](https://linux-hardware.org/?probe=93432b3df2) | Aug 09, 2023 |
| NZXT          | N7 Z590                     | Desktop     | [3831033bdc](https://linux-hardware.org/?probe=3831033bdc) | Aug 09, 2023 |
| Unknown       | HX90                        | Desktop     | [7a14bb927e](https://linux-hardware.org/?probe=7a14bb927e) | Aug 09, 2023 |
| MSI           | Z97-G43                     | Desktop     | [b6edd8931f](https://linux-hardware.org/?probe=b6edd8931f) | Aug 09, 2023 |
| Dell          | 0CRWCR A01                  | All in one  | [8f3bc0a06a](https://linux-hardware.org/?probe=8f3bc0a06a) | Aug 09, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [afef0bb361](https://linux-hardware.org/?probe=afef0bb361) | Aug 09, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [dfcebaef82](https://linux-hardware.org/?probe=dfcebaef82) | Aug 09, 2023 |
| ASUSTek       | ROG Strix G713IH_G713IH     | Notebook    | [76bbb6695d](https://linux-hardware.org/?probe=76bbb6695d) | Aug 09, 2023 |
| Acer          | Aspire A317-33              | Notebook    | [6dd8126a05](https://linux-hardware.org/?probe=6dd8126a05) | Aug 09, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [284cfb0f6d](https://linux-hardware.org/?probe=284cfb0f6d) | Aug 08, 2023 |
| Lenovo        | ThinkPad T440 20B7S4NV07    | Notebook    | [af7992a11e](https://linux-hardware.org/?probe=af7992a11e) | Aug 08, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [b15a5e767a](https://linux-hardware.org/?probe=b15a5e767a) | Aug 08, 2023 |
| Acer          | Aspire E5-721               | Notebook    | [82a8a2346a](https://linux-hardware.org/?probe=82a8a2346a) | Aug 08, 2023 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | Notebook    | [4f4c3a2b96](https://linux-hardware.org/?probe=4f4c3a2b96) | Aug 08, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [7889f62638](https://linux-hardware.org/?probe=7889f62638) | Aug 08, 2023 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [2e30c62b25](https://linux-hardware.org/?probe=2e30c62b25) | Aug 08, 2023 |
| Acer          | Aspire 8930                 | Notebook    | [1a39769fb2](https://linux-hardware.org/?probe=1a39769fb2) | Aug 08, 2023 |
| HP            | 255 G5                      | Notebook    | [b38a912e23](https://linux-hardware.org/?probe=b38a912e23) | Aug 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [5aa44fc15a](https://linux-hardware.org/?probe=5aa44fc15a) | Aug 08, 2023 |
| ASUSTek       | P5Q                         | Desktop     | [f485bf4b6e](https://linux-hardware.org/?probe=f485bf4b6e) | Aug 08, 2023 |
| Acer          | Aspire 4820TG               | Notebook    | [49a63e5cc4](https://linux-hardware.org/?probe=49a63e5cc4) | Aug 08, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [c90663d505](https://linux-hardware.org/?probe=c90663d505) | Aug 08, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [c415fd317b](https://linux-hardware.org/?probe=c415fd317b) | Aug 08, 2023 |
| Lenovo        | 3136 SDK0J40700 WIN 3258... | Mini pc     | [1a0f72e2d0](https://linux-hardware.org/?probe=1a0f72e2d0) | Aug 08, 2023 |
| Toshiba       | Satellite C50-A510          | Notebook    | [335af4e25a](https://linux-hardware.org/?probe=335af4e25a) | Aug 08, 2023 |
| Lenovo        | 1037 SDK0Q40104 WIN 3305... | Server      | [f9d26a8832](https://linux-hardware.org/?probe=f9d26a8832) | Aug 08, 2023 |
| HP            | Pavilion 17                 | Notebook    | [4833cfdbd8](https://linux-hardware.org/?probe=4833cfdbd8) | Aug 08, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [1d117f6031](https://linux-hardware.org/?probe=1d117f6031) | Aug 07, 2023 |
| Pegatron      | 2AB5                        | Desktop     | [9579022e6f](https://linux-hardware.org/?probe=9579022e6f) | Aug 07, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [791adb121f](https://linux-hardware.org/?probe=791adb121f) | Aug 07, 2023 |
| Dell          | Inspiron 3505               | Notebook    | [e07624ae41](https://linux-hardware.org/?probe=e07624ae41) | Aug 07, 2023 |
| Lenovo        | ThinkPad T530 2394EN6       | Notebook    | [d348a65379](https://linux-hardware.org/?probe=d348a65379) | Aug 07, 2023 |
| ASRock        | Z97 Extreme4                | Desktop     | [27c70b528b](https://linux-hardware.org/?probe=27c70b528b) | Aug 07, 2023 |
| Dell          | 0X2MKR A00                  | All in one  | [101fc74a47](https://linux-hardware.org/?probe=101fc74a47) | Aug 07, 2023 |
| Insyde        | BayTrail                    | Notebook    | [df18553ec6](https://linux-hardware.org/?probe=df18553ec6) | Aug 07, 2023 |
| HP            | Elite x2 1012 G1            | Notebook    | [fea0f58ed5](https://linux-hardware.org/?probe=fea0f58ed5) | Aug 07, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [783906b878](https://linux-hardware.org/?probe=783906b878) | Aug 07, 2023 |
| Wortmann      | TERRA_MOBILE_1749           | Notebook    | [22624fbda5](https://linux-hardware.org/?probe=22624fbda5) | Aug 07, 2023 |
| Acer          | Aspire V3-771               | Notebook    | [ebdbffb7da](https://linux-hardware.org/?probe=ebdbffb7da) | Aug 07, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [62d3a8d08d](https://linux-hardware.org/?probe=62d3a8d08d) | Aug 07, 2023 |
| ASUSTek       | X540SA                      | Notebook    | [db952b584b](https://linux-hardware.org/?probe=db952b584b) | Aug 07, 2023 |
| Supermicro    | X10DRiB                     | Server      | [aeb76679f7](https://linux-hardware.org/?probe=aeb76679f7) | Aug 07, 2023 |
| ASUSTek       | N552VX                      | Notebook    | [1c616233ca](https://linux-hardware.org/?probe=1c616233ca) | Aug 07, 2023 |
| ASUSTek       | N76VM                       | Notebook    | [083980d0fb](https://linux-hardware.org/?probe=083980d0fb) | Aug 07, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [dbcb2c4a80](https://linux-hardware.org/?probe=dbcb2c4a80) | Aug 07, 2023 |
| HP            | Laptop 17-ak0xx             | Notebook    | [67749cdc51](https://linux-hardware.org/?probe=67749cdc51) | Aug 07, 2023 |
| Fujitsu       | LIFEBOOK A359               | Notebook    | [60a09f6ca3](https://linux-hardware.org/?probe=60a09f6ca3) | Aug 07, 2023 |
| Packard Be... | EasyNote LS11HR             | Notebook    | [df59aff876](https://linux-hardware.org/?probe=df59aff876) | Aug 07, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E02    | Notebook    | [a3e3489451](https://linux-hardware.org/?probe=a3e3489451) | Aug 07, 2023 |
| Timi          | TM1607                      | Notebook    | [c545853106](https://linux-hardware.org/?probe=c545853106) | Aug 07, 2023 |
| ASUSTek       | PRIME B560M-K               | Desktop     | [a5ae5a237a](https://linux-hardware.org/?probe=a5ae5a237a) | Aug 06, 2023 |
| Clevo         | W150HRM                     | Notebook    | [1ddcfcbecc](https://linux-hardware.org/?probe=1ddcfcbecc) | Aug 06, 2023 |
| Foxconn       | 2ADA                        | Desktop     | [17d44b6d2c](https://linux-hardware.org/?probe=17d44b6d2c) | Aug 06, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [99635bf61d](https://linux-hardware.org/?probe=99635bf61d) | Aug 06, 2023 |
| HP            | EliteBook 8540p             | Notebook    | [4709894444](https://linux-hardware.org/?probe=4709894444) | Aug 06, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [c19229d536](https://linux-hardware.org/?probe=c19229d536) | Aug 06, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [1d8737323b](https://linux-hardware.org/?probe=1d8737323b) | Aug 06, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [6a53759849](https://linux-hardware.org/?probe=6a53759849) | Aug 06, 2023 |
| Gigabyte      | EP35-DS4                    | Desktop     | [761d545a1e](https://linux-hardware.org/?probe=761d545a1e) | Aug 06, 2023 |
| ASRock        | H61M-DGS R2.0               | Desktop     | [032b99ac4f](https://linux-hardware.org/?probe=032b99ac4f) | Aug 06, 2023 |
| ASRock        | Q1900M                      | Desktop     | [51f69dffd5](https://linux-hardware.org/?probe=51f69dffd5) | Aug 06, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [80c705f1a7](https://linux-hardware.org/?probe=80c705f1a7) | Aug 06, 2023 |
| MSI           | H81M-P33                    | Desktop     | [ebed30097f](https://linux-hardware.org/?probe=ebed30097f) | Aug 06, 2023 |
| Packard Be... | EasyNote LS11HR             | Notebook    | [8c8e1cef1c](https://linux-hardware.org/?probe=8c8e1cef1c) | Aug 06, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [0e79a19ed6](https://linux-hardware.org/?probe=0e79a19ed6) | Aug 06, 2023 |
| Dell          | Latitude E5520              | Notebook    | [132e7834f7](https://linux-hardware.org/?probe=132e7834f7) | Aug 06, 2023 |
| ASUSTek       | N76VM                       | Notebook    | [80d45ff242](https://linux-hardware.org/?probe=80d45ff242) | Aug 06, 2023 |
| HP            | 2B4B                        | Desktop     | [f85fada33f](https://linux-hardware.org/?probe=f85fada33f) | Aug 06, 2023 |
| Fujitsu       | D3128-A1 S26361-D3128-A1    | Desktop     | [ac2bdfc67b](https://linux-hardware.org/?probe=ac2bdfc67b) | Aug 06, 2023 |
| ASUSTek       | PRIME B650-PLUS             | Desktop     | [93917e587f](https://linux-hardware.org/?probe=93917e587f) | Aug 06, 2023 |
| Lenovo        | ThinkPad T560 20FJS18V00    | Notebook    | [27d1d39b58](https://linux-hardware.org/?probe=27d1d39b58) | Aug 06, 2023 |
| ASRock        | X470 Taichi                 | Desktop     | [f9d29dca0d](https://linux-hardware.org/?probe=f9d29dca0d) | Aug 06, 2023 |
| ASUSTek       | K54L                        | Notebook    | [3ce0c0b7b2](https://linux-hardware.org/?probe=3ce0c0b7b2) | Aug 06, 2023 |
| ASUSTek       | K54L                        | Notebook    | [b28f27325f](https://linux-hardware.org/?probe=b28f27325f) | Aug 06, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [51442067d5](https://linux-hardware.org/?probe=51442067d5) | Aug 06, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [48ec623298](https://linux-hardware.org/?probe=48ec623298) | Aug 06, 2023 |
| Dell          | Latitude E5570              | Notebook    | [cbcea81a37](https://linux-hardware.org/?probe=cbcea81a37) | Aug 06, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [2726702c6a](https://linux-hardware.org/?probe=2726702c6a) | Aug 06, 2023 |
| BESSTAR Te... | GB1                         | Mini pc     | [2058978754](https://linux-hardware.org/?probe=2058978754) | Aug 06, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [a2847b90c6](https://linux-hardware.org/?probe=a2847b90c6) | Aug 06, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [d9107b9cb9](https://linux-hardware.org/?probe=d9107b9cb9) | Aug 06, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [06e86f7f63](https://linux-hardware.org/?probe=06e86f7f63) | Aug 06, 2023 |
| HP            | ENVY Laptop 17-ch1xxx       | Notebook    | [89119ae1fc](https://linux-hardware.org/?probe=89119ae1fc) | Aug 06, 2023 |
| Gigabyte      | Z590 GAMING X               | Desktop     | [a8c865c9bb](https://linux-hardware.org/?probe=a8c865c9bb) | Aug 06, 2023 |
| Dell          | Inspiron MM061              | Notebook    | [3e037493db](https://linux-hardware.org/?probe=3e037493db) | Aug 06, 2023 |
| TUXEDO        | N7x0WU                      | Notebook    | [1c2cb06178](https://linux-hardware.org/?probe=1c2cb06178) | Aug 06, 2023 |
| Lenovo        | ThinkPad X201 Tablet 298... | Notebook    | [7132bbeb85](https://linux-hardware.org/?probe=7132bbeb85) | Aug 06, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [ed642341d8](https://linux-hardware.org/?probe=ed642341d8) | Aug 06, 2023 |
| Medion        | TJ4125                      | Desktop     | [e35dc275ce](https://linux-hardware.org/?probe=e35dc275ce) | Aug 06, 2023 |
| Valve         | Jupiter                     | Notebook    | [efbeafcf8f](https://linux-hardware.org/?probe=efbeafcf8f) | Aug 05, 2023 |
| Valve         | Jupiter                     | Notebook    | [eadfa77bef](https://linux-hardware.org/?probe=eadfa77bef) | Aug 05, 2023 |
| ASUSTek       | K73SV                       | Notebook    | [c908f2bfdd](https://linux-hardware.org/?probe=c908f2bfdd) | Aug 05, 2023 |
| ASUSTek       | S301LA                      | Notebook    | [cc5477fc6b](https://linux-hardware.org/?probe=cc5477fc6b) | Aug 05, 2023 |
| HP            | ProBook x360 435 G7         | Convertible | [f9a938863a](https://linux-hardware.org/?probe=f9a938863a) | Aug 05, 2023 |
| Unknown       | Unknown                     | Soc         | [0de2cc20ed](https://linux-hardware.org/?probe=0de2cc20ed) | Aug 05, 2023 |
| ASRock        | B550M-HDV                   | Desktop     | [83ee40459a](https://linux-hardware.org/?probe=83ee40459a) | Aug 05, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | Desktop     | [9365c3de56](https://linux-hardware.org/?probe=9365c3de56) | Aug 05, 2023 |
| Gigabyte      | Z590 GAMING X               | Desktop     | [231ad3947e](https://linux-hardware.org/?probe=231ad3947e) | Aug 05, 2023 |
| Acer          | Aspire TC-895 V:1.0         | Desktop     | [85d2740423](https://linux-hardware.org/?probe=85d2740423) | Aug 05, 2023 |
| Dell          | Venue 11 Pro 7140           | Notebook    | [7188a418fc](https://linux-hardware.org/?probe=7188a418fc) | Aug 05, 2023 |
| Fujitsu       | D3011-A1 S26361-D3011-A1    | Desktop     | [597856f529](https://linux-hardware.org/?probe=597856f529) | Aug 05, 2023 |
| Lenovo        | 3178 SDK0J40700 WIN 3258... | Desktop     | [4e0084cd74](https://linux-hardware.org/?probe=4e0084cd74) | Aug 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [8ee9cccace](https://linux-hardware.org/?probe=8ee9cccace) | Aug 05, 2023 |
| MSI           | A68HM GRENADE               | Desktop     | [a186d8863f](https://linux-hardware.org/?probe=a186d8863f) | Aug 05, 2023 |
| Dell          | Latitude 7490               | Notebook    | [73efa45f4f](https://linux-hardware.org/?probe=73efa45f4f) | Aug 05, 2023 |
| Dell          | Latitude 7490               | Notebook    | [ce0e015b6e](https://linux-hardware.org/?probe=ce0e015b6e) | Aug 05, 2023 |
| Shuttle       | DS47D                       | Notebook    | [7d1ceb9b3a](https://linux-hardware.org/?probe=7d1ceb9b3a) | Aug 05, 2023 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [3cfd827251](https://linux-hardware.org/?probe=3cfd827251) | Aug 05, 2023 |
| ASRock        | P67 Pro3                    | Desktop     | [da235e8c08](https://linux-hardware.org/?probe=da235e8c08) | Aug 05, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [fed2da6500](https://linux-hardware.org/?probe=fed2da6500) | Aug 05, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [2531b9d0db](https://linux-hardware.org/?probe=2531b9d0db) | Aug 05, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | Notebook    | [7d17fc9ff6](https://linux-hardware.org/?probe=7d17fc9ff6) | Aug 05, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [ccbf514dc7](https://linux-hardware.org/?probe=ccbf514dc7) | Aug 04, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | Desktop     | [9ffeb0adcd](https://linux-hardware.org/?probe=9ffeb0adcd) | Aug 04, 2023 |
| Supermicro    | X9SRE/X9SRE-3F/X9SRi/X9S... | Server      | [b19db5b96a](https://linux-hardware.org/?probe=b19db5b96a) | Aug 04, 2023 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [e6e6cc7b2e](https://linux-hardware.org/?probe=e6e6cc7b2e) | Aug 04, 2023 |
| Acer          | Swift SF514-52T             | Notebook    | [6b6773eeef](https://linux-hardware.org/?probe=6b6773eeef) | Aug 04, 2023 |
| Dell          | Latitude E6330              | Notebook    | [c4b0f9dfd2](https://linux-hardware.org/?probe=c4b0f9dfd2) | Aug 04, 2023 |
| ASRockRack    | X470D4U                     | Desktop     | [3c7626751d](https://linux-hardware.org/?probe=3c7626751d) | Aug 04, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | Desktop     | [2886f9202b](https://linux-hardware.org/?probe=2886f9202b) | Aug 04, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [7bc7a7e01c](https://linux-hardware.org/?probe=7bc7a7e01c) | Aug 04, 2023 |
| Dell          | Latitude E6330              | Notebook    | [3c74e4818b](https://linux-hardware.org/?probe=3c74e4818b) | Aug 04, 2023 |
| Lenovo        | ThinkPad T420 4236MBG       | Notebook    | [aaaa17358f](https://linux-hardware.org/?probe=aaaa17358f) | Aug 04, 2023 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | Notebook    | [5e28b5b07a](https://linux-hardware.org/?probe=5e28b5b07a) | Aug 04, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [b8fa3962ed](https://linux-hardware.org/?probe=b8fa3962ed) | Aug 04, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [5799f1a89c](https://linux-hardware.org/?probe=5799f1a89c) | Aug 04, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [01846991de](https://linux-hardware.org/?probe=01846991de) | Aug 04, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [058011da0f](https://linux-hardware.org/?probe=058011da0f) | Aug 04, 2023 |
| Acer          | Swift SF114-34              | Notebook    | [2af2b0aecb](https://linux-hardware.org/?probe=2af2b0aecb) | Aug 04, 2023 |
| ASUSTek       | N501JW                      | Notebook    | [e7d254dbe5](https://linux-hardware.org/?probe=e7d254dbe5) | Aug 04, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [5157c58f81](https://linux-hardware.org/?probe=5157c58f81) | Aug 04, 2023 |
| Medion        | TJ4125                      | Desktop     | [0adec5cb7e](https://linux-hardware.org/?probe=0adec5cb7e) | Aug 04, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [5746742389](https://linux-hardware.org/?probe=5746742389) | Aug 04, 2023 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [3793d876eb](https://linux-hardware.org/?probe=3793d876eb) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [af4f153b11](https://linux-hardware.org/?probe=af4f153b11) | Aug 04, 2023 |
| Medion        | B360H4-EM V1.0              | Desktop     | [18146f8bc9](https://linux-hardware.org/?probe=18146f8bc9) | Aug 04, 2023 |
| ASRock        | X370 Taichi                 | Desktop     | [af453d6ef1](https://linux-hardware.org/?probe=af453d6ef1) | Aug 04, 2023 |
| Dell          | 0CRWCR A01                  | All in one  | [16511212ba](https://linux-hardware.org/?probe=16511212ba) | Aug 04, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | Notebook    | [848ed7bc51](https://linux-hardware.org/?probe=848ed7bc51) | Aug 04, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [d3df0e8ee1](https://linux-hardware.org/?probe=d3df0e8ee1) | Aug 04, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [2cb4df0aab](https://linux-hardware.org/?probe=2cb4df0aab) | Aug 04, 2023 |
| Medion        | E3223                       | Convertible | [6202d5444f](https://linux-hardware.org/?probe=6202d5444f) | Aug 04, 2023 |
| Acer          | Extensa 5630                | Notebook    | [8b3c2a89a1](https://linux-hardware.org/?probe=8b3c2a89a1) | Aug 04, 2023 |
| Acer          | Extensa 5630                | Notebook    | [ba6669a5e7](https://linux-hardware.org/?probe=ba6669a5e7) | Aug 04, 2023 |
| HP            | ProBook 640 G2              | Notebook    | [7cacb46425](https://linux-hardware.org/?probe=7cacb46425) | Aug 04, 2023 |
| Dell          | 0WXD1Y A00                  | Server      | [fab223d590](https://linux-hardware.org/?probe=fab223d590) | Aug 04, 2023 |
| Medion        | Erazer X7841 MD99556        | Notebook    | [c9f4247fc1](https://linux-hardware.org/?probe=c9f4247fc1) | Aug 04, 2023 |
| ASUSTek       | B85-PRO GAMER               | Desktop     | [d4bb94e07e](https://linux-hardware.org/?probe=d4bb94e07e) | Aug 04, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [1abcf2ad6f](https://linux-hardware.org/?probe=1abcf2ad6f) | Aug 04, 2023 |
| Dell          | 0W13NR A06                  | Server      | [b1820a9229](https://linux-hardware.org/?probe=b1820a9229) | Aug 04, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [b2004d5d59](https://linux-hardware.org/?probe=b2004d5d59) | Aug 04, 2023 |
| ASRock        | Z97 Extreme4                | Desktop     | [4252e9a028](https://linux-hardware.org/?probe=4252e9a028) | Aug 04, 2023 |
| ASUSTek       | ROG STRIX B450-E GAMING     | Desktop     | [724beebcb2](https://linux-hardware.org/?probe=724beebcb2) | Aug 04, 2023 |
| Lenovo        | ThinkPad T450 20BUS3ES0A    | Notebook    | [1038e99486](https://linux-hardware.org/?probe=1038e99486) | Aug 04, 2023 |
| TUXEDO        | Aura 15 Gen2                | Notebook    | [07d668ee3d](https://linux-hardware.org/?probe=07d668ee3d) | Aug 03, 2023 |
| Acer          | Aspire V5-572P              | Notebook    | [1d27d25f8d](https://linux-hardware.org/?probe=1d27d25f8d) | Aug 03, 2023 |
| HP            | 3031h                       | Desktop     | [95b5c80f67](https://linux-hardware.org/?probe=95b5c80f67) | Aug 03, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [983329d56b](https://linux-hardware.org/?probe=983329d56b) | Aug 03, 2023 |
| HP            | 8055                        | Desktop     | [21c8e1fdc2](https://linux-hardware.org/?probe=21c8e1fdc2) | Aug 03, 2023 |
| HP            | Notebook                    | Notebook    | [499fc30d3a](https://linux-hardware.org/?probe=499fc30d3a) | Aug 03, 2023 |
| Medion        | MS-7616                     | Desktop     | [7b9dae91ad](https://linux-hardware.org/?probe=7b9dae91ad) | Aug 03, 2023 |
| Dell          | 0F642F A00                  | Desktop     | [b2c444dc4f](https://linux-hardware.org/?probe=b2c444dc4f) | Aug 03, 2023 |
| ASUSTek       | P8H77-M                     | Desktop     | [1764158bf6](https://linux-hardware.org/?probe=1764158bf6) | Aug 03, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [88e9cc22bf](https://linux-hardware.org/?probe=88e9cc22bf) | Aug 03, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [39e2c1bfad](https://linux-hardware.org/?probe=39e2c1bfad) | Aug 03, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [37725aaff8](https://linux-hardware.org/?probe=37725aaff8) | Aug 03, 2023 |
| Gigabyte      | B450M S2H V2                | Desktop     | [a01412b320](https://linux-hardware.org/?probe=a01412b320) | Aug 03, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | Notebook    | [620397fdc9](https://linux-hardware.org/?probe=620397fdc9) | Aug 03, 2023 |
| ZOTAC         | ZBOX-PI335                  | Mini pc     | [8b5204eccf](https://linux-hardware.org/?probe=8b5204eccf) | Aug 03, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Notebook    | [882d963e19](https://linux-hardware.org/?probe=882d963e19) | Aug 03, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [88a569c8ee](https://linux-hardware.org/?probe=88a569c8ee) | Aug 03, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [52319a8cef](https://linux-hardware.org/?probe=52319a8cef) | Aug 03, 2023 |
| ASUSTek       | B85-PRO GAMER               | Desktop     | [e888742592](https://linux-hardware.org/?probe=e888742592) | Aug 03, 2023 |
| HP            | 3031h                       | Desktop     | [04c8ac1eee](https://linux-hardware.org/?probe=04c8ac1eee) | Aug 03, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Notebook    | [38d0bcf5d1](https://linux-hardware.org/?probe=38d0bcf5d1) | Aug 03, 2023 |
| Acer          | Aspire VN7-793G             | Notebook    | [c7e996a3c2](https://linux-hardware.org/?probe=c7e996a3c2) | Aug 03, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [a956adcb38](https://linux-hardware.org/?probe=a956adcb38) | Aug 03, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [35cf0fd859](https://linux-hardware.org/?probe=35cf0fd859) | Aug 03, 2023 |
| Samsung       | 900X3C/900X3D/900X3E/900... | Notebook    | [a3401e5a4b](https://linux-hardware.org/?probe=a3401e5a4b) | Aug 03, 2023 |
| Lenovo        | ThinkPad P51s 20HCS0660Y    | Notebook    | [6e8234ed89](https://linux-hardware.org/?probe=6e8234ed89) | Aug 03, 2023 |
| Dell          | Latitude 5420               | Notebook    | [491cea9604](https://linux-hardware.org/?probe=491cea9604) | Aug 03, 2023 |
| Packard Be... | EasyNote LS11HR             | Notebook    | [6e79cf1bf0](https://linux-hardware.org/?probe=6e79cf1bf0) | Aug 03, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [881ac0a0e0](https://linux-hardware.org/?probe=881ac0a0e0) | Aug 02, 2023 |
| MSI           | X370 GAMING PRO             | Desktop     | [b684b97e44](https://linux-hardware.org/?probe=b684b97e44) | Aug 02, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [221b0f2db2](https://linux-hardware.org/?probe=221b0f2db2) | Aug 02, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [c3beec95b8](https://linux-hardware.org/?probe=c3beec95b8) | Aug 02, 2023 |
| Dell          | Latitude E6320              | Notebook    | [9b42be4945](https://linux-hardware.org/?probe=9b42be4945) | Aug 02, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [433a85501a](https://linux-hardware.org/?probe=433a85501a) | Aug 02, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [101e2e7e7e](https://linux-hardware.org/?probe=101e2e7e7e) | Aug 02, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [16cafd9d32](https://linux-hardware.org/?probe=16cafd9d32) | Aug 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [cf7cad0e02](https://linux-hardware.org/?probe=cf7cad0e02) | Aug 02, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [37fe1d55f8](https://linux-hardware.org/?probe=37fe1d55f8) | Aug 02, 2023 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [34cfa173f7](https://linux-hardware.org/?probe=34cfa173f7) | Aug 02, 2023 |
| Lenovo        | ThinkPad X220 4290EC5       | Notebook    | [6ffb3ac7e7](https://linux-hardware.org/?probe=6ffb3ac7e7) | Aug 02, 2023 |
| Medion        | X681X                       | Notebook    | [8209a37737](https://linux-hardware.org/?probe=8209a37737) | Aug 02, 2023 |
| Schenker      | VISION 15 (SVS15E21)        | Notebook    | [0f5b976e39](https://linux-hardware.org/?probe=0f5b976e39) | Aug 02, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [4e092275e4](https://linux-hardware.org/?probe=4e092275e4) | Aug 02, 2023 |
| HP            | Pavilion dv7                | Notebook    | [bd9bc8e7a6](https://linux-hardware.org/?probe=bd9bc8e7a6) | Aug 02, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [0ae0b35097](https://linux-hardware.org/?probe=0ae0b35097) | Aug 02, 2023 |
| Dell          | Precision M4500             | Notebook    | [b425204301](https://linux-hardware.org/?probe=b425204301) | Aug 02, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [502969280a](https://linux-hardware.org/?probe=502969280a) | Aug 02, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [60cb0baf9d](https://linux-hardware.org/?probe=60cb0baf9d) | Aug 02, 2023 |
| Acer          | Aspire A3SP14-31PT          | Convertible | [aa4285c237](https://linux-hardware.org/?probe=aa4285c237) | Aug 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [57bac048da](https://linux-hardware.org/?probe=57bac048da) | Aug 02, 2023 |
| Dell          | 0NKW6Y A01                  | Desktop     | [6bae407930](https://linux-hardware.org/?probe=6bae407930) | Aug 02, 2023 |
| Dell          | Inspiron 13-5368            | Notebook    | [479ca68bae](https://linux-hardware.org/?probe=479ca68bae) | Aug 02, 2023 |
| HP            | ProBook 455 15.6 inch G9... | Notebook    | [8fb651def8](https://linux-hardware.org/?probe=8fb651def8) | Aug 02, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [c6078d0836](https://linux-hardware.org/?probe=c6078d0836) | Aug 02, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [0a3c5e5c4d](https://linux-hardware.org/?probe=0a3c5e5c4d) | Aug 02, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [9f852ea211](https://linux-hardware.org/?probe=9f852ea211) | Aug 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [7748df9ae9](https://linux-hardware.org/?probe=7748df9ae9) | Aug 01, 2023 |
| Acer          | Aspire ES1-521              | Notebook    | [127d7abd32](https://linux-hardware.org/?probe=127d7abd32) | Aug 01, 2023 |
| ASRock        | Z170 Extreme4               | Desktop     | [7ef89d48d6](https://linux-hardware.org/?probe=7ef89d48d6) | Aug 01, 2023 |
| Acer          | Aspire A517-52              | Notebook    | [aa9fd10def](https://linux-hardware.org/?probe=aa9fd10def) | Aug 01, 2023 |
| Dell          | Precision 7550              | Notebook    | [ab0d21bb4e](https://linux-hardware.org/?probe=ab0d21bb4e) | Aug 01, 2023 |
| Lenovo        | ThinkPad X250 20CM001PGE    | Notebook    | [9c5503cd84](https://linux-hardware.org/?probe=9c5503cd84) | Aug 01, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [1abb46d019](https://linux-hardware.org/?probe=1abb46d019) | Aug 01, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [6f59479d87](https://linux-hardware.org/?probe=6f59479d87) | Aug 01, 2023 |
| HP            | 18E4                        | Desktop     | [20ebffd9a8](https://linux-hardware.org/?probe=20ebffd9a8) | Aug 01, 2023 |
| Lenovo        | ThinkPad X220 4290EC5       | Notebook    | [e6d6527380](https://linux-hardware.org/?probe=e6d6527380) | Aug 01, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [9e892c6bc7](https://linux-hardware.org/?probe=9e892c6bc7) | Aug 01, 2023 |
| Lenovo        | ThinkPad X270 20HMS12K00    | Notebook    | [bc84705e8f](https://linux-hardware.org/?probe=bc84705e8f) | Aug 01, 2023 |
| Medion        | E5214                       | Notebook    | [98cb0db418](https://linux-hardware.org/?probe=98cb0db418) | Aug 01, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [b53d4c2fad](https://linux-hardware.org/?probe=b53d4c2fad) | Aug 01, 2023 |
| Dell          | Latitude E6220              | Notebook    | [5b4b97df21](https://linux-hardware.org/?probe=5b4b97df21) | Aug 01, 2023 |
| ASRock        | H61M/U3S3                   | Desktop     | [33c887e577](https://linux-hardware.org/?probe=33c887e577) | Aug 01, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [244a32825d](https://linux-hardware.org/?probe=244a32825d) | Aug 01, 2023 |
| Lenovo        | 1066 SDK0T76528 WIN 3556... | Desktop     | [df0702afb0](https://linux-hardware.org/?probe=df0702afb0) | Aug 01, 2023 |
| Lenovo        | 1066 SDK0T76528 WIN 3556... | Desktop     | [0ac623dd70](https://linux-hardware.org/?probe=0ac623dd70) | Aug 01, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [3a500cdb55](https://linux-hardware.org/?probe=3a500cdb55) | Aug 01, 2023 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [1090d19a71](https://linux-hardware.org/?probe=1090d19a71) | Aug 01, 2023 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [49e503da8e](https://linux-hardware.org/?probe=49e503da8e) | Aug 01, 2023 |
| TrekStor      | Primetab T13B               | Tablet      | [cdbe4dbe82](https://linux-hardware.org/?probe=cdbe4dbe82) | Aug 01, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [b57f8ee5f8](https://linux-hardware.org/?probe=b57f8ee5f8) | Aug 01, 2023 |
| ASUSTek       | P8H67-M                     | Desktop     | [7bebd786bd](https://linux-hardware.org/?probe=7bebd786bd) | Aug 01, 2023 |
| ASRock        | X300-ITX                    | Desktop     | [70a181c62b](https://linux-hardware.org/?probe=70a181c62b) | Jul 31, 2023 |
| MSI           | H97 PC Mate                 | Desktop     | [3e200ead3c](https://linux-hardware.org/?probe=3e200ead3c) | Jul 31, 2023 |
| Dell          | Latitude 7640               | Notebook    | [ddb87f6cdb](https://linux-hardware.org/?probe=ddb87f6cdb) | Jul 31, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [a7cf8e8ef1](https://linux-hardware.org/?probe=a7cf8e8ef1) | Jul 31, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [5d12cf34ca](https://linux-hardware.org/?probe=5d12cf34ca) | Jul 31, 2023 |
| TUXEDO        | N7x0WU                      | Notebook    | [05c525a9a7](https://linux-hardware.org/?probe=05c525a9a7) | Jul 31, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [b42946849e](https://linux-hardware.org/?probe=b42946849e) | Jul 31, 2023 |
| HP            | Laptop 17-bs0xx             | Notebook    | [49dac3f2d9](https://linux-hardware.org/?probe=49dac3f2d9) | Jul 31, 2023 |
| Dell          | Precision 3571              | Notebook    | [83a85ddae5](https://linux-hardware.org/?probe=83a85ddae5) | Jul 31, 2023 |
| HP            | Pavilion 17                 | Notebook    | [38fe3ae501](https://linux-hardware.org/?probe=38fe3ae501) | Jul 31, 2023 |
| HP            | Laptop 17-bs0xx             | Notebook    | [aca7e14a0e](https://linux-hardware.org/?probe=aca7e14a0e) | Jul 31, 2023 |
| Apple         | Mac-DB15BD556843C820 iMa... | All in one  | [ec04257798](https://linux-hardware.org/?probe=ec04257798) | Jul 31, 2023 |
| HP            | ProBook 4720s               | Notebook    | [f1e4220c67](https://linux-hardware.org/?probe=f1e4220c67) | Jul 31, 2023 |
| HP            | ProBook 640 G2              | Notebook    | [9e297e7c8e](https://linux-hardware.org/?probe=9e297e7c8e) | Jul 31, 2023 |
| ASUSTek       | M4N78-AM                    | Desktop     | [a4740d2b14](https://linux-hardware.org/?probe=a4740d2b14) | Jul 31, 2023 |
| Medion        | Erazer X7841 MD99556        | Notebook    | [7b9d9dfa25](https://linux-hardware.org/?probe=7b9d9dfa25) | Jul 31, 2023 |
| Apple         | MacBookAir3,1               | Notebook    | [1859204a6f](https://linux-hardware.org/?probe=1859204a6f) | Jul 31, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [e8b1218a57](https://linux-hardware.org/?probe=e8b1218a57) | Jul 31, 2023 |
| Lenovo        | ThinkPad P50 20EQS20D00     | Notebook    | [4ef8aa09c6](https://linux-hardware.org/?probe=4ef8aa09c6) | Jul 31, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [264f400d7e](https://linux-hardware.org/?probe=264f400d7e) | Jul 30, 2023 |
| HP            | 3398                        | Desktop     | [444f9d27d5](https://linux-hardware.org/?probe=444f9d27d5) | Jul 30, 2023 |
| HP            | 8056                        | Desktop     | [3a98a11778](https://linux-hardware.org/?probe=3a98a11778) | Jul 30, 2023 |
| Acer          | Aspire 5741G                | Notebook    | [3c56ffebcb](https://linux-hardware.org/?probe=3c56ffebcb) | Jul 30, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [f201460a34](https://linux-hardware.org/?probe=f201460a34) | Jul 30, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [63017a7eb1](https://linux-hardware.org/?probe=63017a7eb1) | Jul 30, 2023 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | Notebook    | [1fe8eab1c6](https://linux-hardware.org/?probe=1fe8eab1c6) | Jul 30, 2023 |
| ASUSTek       | PN40                        | Mini pc     | [9336495f4e](https://linux-hardware.org/?probe=9336495f4e) | Jul 30, 2023 |
| Dell          | Latitude 5421               | Notebook    | [3872b1f799](https://linux-hardware.org/?probe=3872b1f799) | Jul 30, 2023 |
| HP            | Pavilion 15                 | Notebook    | [7dcc58cdf2](https://linux-hardware.org/?probe=7dcc58cdf2) | Jul 30, 2023 |
| Acer          | Aspire G7713                | Desktop     | [e0624d410e](https://linux-hardware.org/?probe=e0624d410e) | Jul 30, 2023 |
| MSI           | MS-B1591                    | Desktop     | [9bdfd87437](https://linux-hardware.org/?probe=9bdfd87437) | Jul 30, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [de6e904009](https://linux-hardware.org/?probe=de6e904009) | Jul 30, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [6928788f05](https://linux-hardware.org/?probe=6928788f05) | Jul 30, 2023 |
| Medion        | E5214                       | Notebook    | [d1c634ee07](https://linux-hardware.org/?probe=d1c634ee07) | Jul 30, 2023 |
| Dell          | Latitude E6510              | Notebook    | [f8ebba29c6](https://linux-hardware.org/?probe=f8ebba29c6) | Jul 30, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | Desktop     | [356dae8360](https://linux-hardware.org/?probe=356dae8360) | Jul 30, 2023 |
| Lenovo        | ThinkPad T440p 20AN009FG... | Notebook    | [f2cc6379cc](https://linux-hardware.org/?probe=f2cc6379cc) | Jul 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [a15a3cfa70](https://linux-hardware.org/?probe=a15a3cfa70) | Jul 30, 2023 |
| Apple         | MacBookPro9,1               | Notebook    | [3b030b25ac](https://linux-hardware.org/?probe=3b030b25ac) | Jul 30, 2023 |
| Lenovo        | ThinkPad X220 42914XG       | Notebook    | [053a30cc87](https://linux-hardware.org/?probe=053a30cc87) | Jul 30, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [d788283742](https://linux-hardware.org/?probe=d788283742) | Jul 30, 2023 |
| Dell          | Latitude E5520              | Notebook    | [09aa4e35c4](https://linux-hardware.org/?probe=09aa4e35c4) | Jul 30, 2023 |
| Acer          | Aspire A315-42              | Notebook    | [3d1aebd069](https://linux-hardware.org/?probe=3d1aebd069) | Jul 30, 2023 |
| Dell          | 0272WF A00                  | Server      | [ab789b12e1](https://linux-hardware.org/?probe=ab789b12e1) | Jul 30, 2023 |
| ASUSTek       | Zephyrus S GX701GX_GX701... | Notebook    | [69da742061](https://linux-hardware.org/?probe=69da742061) | Jul 30, 2023 |
| Lenovo        | ThinkPad X201 3680BF5       | Notebook    | [dd11ccaaad](https://linux-hardware.org/?probe=dd11ccaaad) | Jul 29, 2023 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [fde88e808d](https://linux-hardware.org/?probe=fde88e808d) | Jul 29, 2023 |
| Gigabyte      | MZAPLBP-00                  | Desktop     | [b70677782d](https://linux-hardware.org/?probe=b70677782d) | Jul 29, 2023 |
| Dell          | Inspiron 16 7610            | Notebook    | [e7befe5a64](https://linux-hardware.org/?probe=e7befe5a64) | Jul 29, 2023 |
| Gigabyte      | MZAPLBP-00                  | Desktop     | [ae8a9f3aaf](https://linux-hardware.org/?probe=ae8a9f3aaf) | Jul 29, 2023 |
| Acer          | Aspire A517-52              | Notebook    | [1df8f3a3ed](https://linux-hardware.org/?probe=1df8f3a3ed) | Jul 29, 2023 |
| ASUSTek       | K53U                        | Notebook    | [c1b84117db](https://linux-hardware.org/?probe=c1b84117db) | Jul 29, 2023 |
| Dell          | Latitude 7380               | Notebook    | [ec068abcb3](https://linux-hardware.org/?probe=ec068abcb3) | Jul 29, 2023 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [f36740f05f](https://linux-hardware.org/?probe=f36740f05f) | Jul 29, 2023 |
| Medion        | H110H4-EM                   | Desktop     | [7c2b005f92](https://linux-hardware.org/?probe=7c2b005f92) | Jul 29, 2023 |
| ASRock        | H61M-DGS R2.0               | Desktop     | [9d6da42aec](https://linux-hardware.org/?probe=9d6da42aec) | Jul 29, 2023 |
| Panasonic     | CF-20-1                     | Notebook    | [0b59968d03](https://linux-hardware.org/?probe=0b59968d03) | Jul 29, 2023 |
| Dell          | 0272WF A00                  | Server      | [2867ef6d1f](https://linux-hardware.org/?probe=2867ef6d1f) | Jul 29, 2023 |
| Dell          | Latitude 7380               | Notebook    | [a5ea12f136](https://linux-hardware.org/?probe=a5ea12f136) | Jul 29, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Germany/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 2841      | 12.94%  |
| Ubuntu 18.04                 | 1247      | 5.68%   |
| Ubuntu 22.04                 | 1174      | 5.35%   |
| Debian 11                    | 619       | 2.82%   |
| Linux Mint 20.3              | 584       | 2.66%   |
| Linux Mint 20.2              | 567       | 2.58%   |
| OpenMandriva 4.2             | 566       | 2.58%   |
| OpenMandriva 4.3             | 548       | 2.5%    |
| Linux Mint 21.1              | 463       | 2.11%   |
| Arch Rolling                 | 394       | 1.79%   |
| Manjaro                      | 390       | 1.78%   |
| Linux Mint 20.1              | 363       | 1.65%   |
| Ubuntu 20.10                 | 344       | 1.57%   |
| Ubuntu 21.10                 | 342       | 1.56%   |
| Zorin 16                     | 337       | 1.53%   |
| Linux Mint 20                | 295       | 1.34%   |
| Arch                         | 287       | 1.31%   |
| Linux Mint 19.3              | 286       | 1.3%    |
| Xubuntu 20.04                | 260       | 1.18%   |
| KDE neon 20.04               | 252       | 1.15%   |
| Ubuntu 21.04                 | 238       | 1.08%   |
| openSUSE Tumbleweed-XXXXXXXX | 221       | 1.01%   |
| Pop!_OS 22.04                | 219       | 1%      |
| Ubuntu 19.10                 | 216       | 0.98%   |
| Ubuntu 22.10                 | 214       | 0.97%   |
| Ubuntu 19.04                 | 203       | 0.92%   |
| Linux Mint 21                | 200       | 0.91%   |
| OpenMandriva 23.03           | 188       | 0.86%   |
| OpenMandriva 23.01           | 183       | 0.83%   |
| Debian 10                    | 171       | 0.78%   |
| Fedora 37                    | 163       | 0.74%   |
| Fedora 38                    | 159       | 0.72%   |
| Fedora 36                    | 159       | 0.72%   |
| Ubuntu 23.04                 | 154       | 0.7%    |
| BlackPanther 18.1            | 146       | 0.66%   |
| ArcoLinux Rolling            | 145       | 0.66%   |
| Kubuntu 20.04                | 142       | 0.65%   |
| Pop!_OS 20.10                | 138       | 0.63%   |
| Fedora 33                    | 138       | 0.63%   |
| Debian 12                    | 125       | 0.57%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 6691      | 32.58%  |
| Linux Mint    | 2856      | 13.91%  |
| OpenMandriva  | 1636      | 7.97%   |
| Debian        | 1087      | 5.29%   |
| Fedora        | 926       | 4.51%   |
| Manjaro       | 821       | 4%      |
| Arch          | 660       | 3.21%   |
| Pop!_OS       | 639       | 3.11%   |
| Xubuntu       | 521       | 2.54%   |
| Zorin         | 469       | 2.28%   |
| Kubuntu       | 460       | 2.24%   |
| openSUSE      | 408       | 1.99%   |
| ROSA          | 361       | 1.76%   |
| KDE neon      | 330       | 1.61%   |
| Gentoo        | 221       | 1.08%   |
| Elementary    | 171       | 0.83%   |
| ArcoLinux     | 160       | 0.78%   |
| Ubuntu MATE   | 157       | 0.76%   |
| BlackPanther  | 157       | 0.76%   |
| Endless       | 143       | 0.7%    |
| Kali          | 118       | 0.57%   |
| Ubuntu Unity  | 114       | 0.56%   |
| LMDE          | 114       | 0.56%   |
| Lubuntu       | 109       | 0.53%   |
| EndeavourOS   | 100       | 0.49%   |
| Ubuntu Budgie | 96        | 0.47%   |
| SteamOS       | 95        | 0.46%   |
| MX            | 66        | 0.32%   |
| Garuda Linux  | 55        | 0.27%   |
| CentOS        | 55        | 0.27%   |
| Clear Linux   | 51        | 0.25%   |
| Raspbian      | 47        | 0.23%   |
| TUXEDO OS     | 42        | 0.2%    |
| Nobara        | 41        | 0.2%    |
| Parrot        | 30        | 0.15%   |
| LinuxFX       | 27        | 0.13%   |
| Peppermint    | 26        | 0.13%   |
| Xero          | 25        | 0.12%   |
| QTS           | 21        | 0.1%    |
| NixOS         | 21        | 0.1%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 540       | 2.19%   |
| 5.16.7-desktop-1omv4003  | 515       | 2.09%   |
| 5.4.0-42-generic         | 301       | 1.22%   |
| 5.15.0-56-generic        | 269       | 1.09%   |
| 5.4.0-58-generic         | 228       | 0.93%   |
| 5.15.0-58-generic        | 197       | 0.8%    |
| 6.2.6-desktop-1omv2390   | 184       | 0.75%   |
| 5.4.0-91-generic         | 179       | 0.73%   |
| 5.4.0-52-generic         | 178       | 0.72%   |
| 5.4.0-48-generic         | 175       | 0.71%   |
| 6.1.1-desktop-1omv2290   | 173       | 0.7%    |
| 5.15.0-52-generic        | 145       | 0.59%   |
| 5.15.0-48-generic        | 143       | 0.58%   |
| 5.4.0-26-generic         | 140       | 0.57%   |
| 5.19.0-35-generic        | 140       | 0.57%   |
| 5.15.0-60-generic        | 139       | 0.56%   |
| 5.15.0-46-generic        | 139       | 0.56%   |
| 5.8.0-43-generic         | 118       | 0.48%   |
| 5.4.0-65-generic         | 118       | 0.48%   |
| 5.11.0-27-generic        | 116       | 0.47%   |
| 5.15.0-67-generic        | 115       | 0.47%   |
| 5.13.0-39-generic        | 115       | 0.47%   |
| 5.4.0-54-generic         | 113       | 0.46%   |
| 5.4.0-40-generic         | 113       | 0.46%   |
| 5.11.0-37-generic        | 112       | 0.45%   |
| 5.11.0-38-generic        | 111       | 0.45%   |
| 5.13.0-28-generic        | 110       | 0.45%   |
| 5.4.0-29-generic         | 109       | 0.44%   |
| 5.3.0-40-generic         | 107       | 0.43%   |
| 5.11.0-40-generic        | 107       | 0.43%   |
| 5.15.0-53-generic        | 106       | 0.43%   |
| 5.15.0-47-generic        | 103       | 0.42%   |
| 5.4.0-72-generic         | 102       | 0.41%   |
| 4.18.16-desktop-1bP      | 102       | 0.41%   |
| 5.13.0-30-generic        | 99        | 0.4%    |
| 5.4.0-33-generic         | 98        | 0.4%    |
| 5.4.0-37-generic         | 96        | 0.39%   |
| 5.4.0-56-generic         | 94        | 0.38%   |
| 5.4.0-74-generic         | 93        | 0.38%   |
| 5.4.0-81-generic         | 92        | 0.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 4038      | 17.8%   |
| 5.15.0  | 2188      | 9.64%   |
| 5.8.0   | 1200      | 5.29%   |
| 4.15.0  | 1180      | 5.2%    |
| 5.11.0  | 1135      | 5%      |
| 5.13.0  | 1114      | 4.91%   |
| 5.19.0  | 804       | 3.54%   |
| 5.3.0   | 701       | 3.09%   |
| 5.10.0  | 653       | 2.88%   |
| 5.10.14 | 545       | 2.4%    |
| 5.16.7  | 524       | 2.31%   |
| 5.0.0   | 486       | 2.14%   |
| 4.18.0  | 370       | 1.63%   |
| 6.2.0   | 325       | 1.43%   |
| 6.2.6   | 260       | 1.15%   |
| 6.1.1   | 195       | 0.86%   |
| 6.1.0   | 192       | 0.85%   |
| 4.19.0  | 176       | 0.78%   |
| 4.18.16 | 111       | 0.49%   |
| 6.4.11  | 84        | 0.37%   |
| 6.0.0   | 84        | 0.37%   |
| 5.14.0  | 78        | 0.34%   |
| 5.3.18  | 74        | 0.33%   |
| 5.14.21 | 68        | 0.3%    |
| 4.9.20  | 63        | 0.28%   |
| 4.4.0   | 62        | 0.27%   |
| 5.18.0  | 58        | 0.26%   |
| 4.9.60  | 58        | 0.26%   |
| 6.0.12  | 52        | 0.23%   |
| 5.17.5  | 52        | 0.23%   |
| 5.6.14  | 50        | 0.22%   |
| 5.17.1  | 50        | 0.22%   |
| 5.11.12 | 50        | 0.22%   |
| 5.9.16  | 48        | 0.21%   |
| 5.6.0   | 47        | 0.21%   |
| 5.16.0  | 46        | 0.2%    |
| 6.1.12  | 44        | 0.19%   |
| 5.12.4  | 44        | 0.19%   |
| 5.9.0   | 43        | 0.19%   |
| 5.16.13 | 43        | 0.19%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 4285      | 19.14%  |
| 5.15    | 2691      | 12.02%  |
| 5.10    | 1548      | 6.92%   |
| 5.8     | 1432      | 6.4%    |
| 5.11    | 1358      | 6.07%   |
| 5.13    | 1276      | 5.7%    |
| 4.15    | 1189      | 5.31%   |
| 5.19    | 1006      | 4.49%   |
| 5.3     | 840       | 3.75%   |
| 6.2     | 785       | 3.51%   |
| 5.16    | 780       | 3.48%   |
| 6.1     | 772       | 3.45%   |
| 5.0     | 509       | 2.27%   |
| 4.18    | 495       | 2.21%   |
| 6.0     | 358       | 1.6%    |
| 6.4     | 282       | 1.26%   |
| 5.9     | 274       | 1.22%   |
| 5.14    | 272       | 1.22%   |
| 5.18    | 247       | 1.1%    |
| 4.9     | 240       | 1.07%   |
| 6.3     | 239       | 1.07%   |
| 5.6     | 237       | 1.06%   |
| 4.19    | 227       | 1.01%   |
| 5.17    | 220       | 0.98%   |
| 5.12    | 170       | 0.76%   |
| 5.7     | 151       | 0.67%   |
| 5.5     | 100       | 0.45%   |
| 4.4     | 72        | 0.32%   |
| 5.2     | 43        | 0.19%   |
| 5.1     | 43        | 0.19%   |
| 4.1     | 39        | 0.17%   |
| 4.14    | 37        | 0.17%   |
| 4.12    | 36        | 0.16%   |
| 3.10    | 28        | 0.13%   |
| 4.13    | 27        | 0.12%   |
| 4.20    | 14        | 0.06%   |
| 6.5     | 13        | 0.06%   |
| 4.17    | 11        | 0.05%   |
| 5       | 6         | 0.03%   |
| 4.8     | 6         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| x86_64   | 19072     | 96.16%  |
| i686     | 495       | 2.5%    |
| aarch64  | 193       | 0.97%   |
| armv7l   | 52        | 0.26%   |
| armv6l   | 10        | 0.05%   |
| ppc      | 5         | 0.03%   |
| riscv64  | 2         | 0.01%   |
| armv8l   | 2         | 0.01%   |
| armv5tel | 2         | 0.01%   |
| mips     | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| GNOME             | 8176      | 39.39%  |
| KDE5              | 3713      | 17.89%  |
| Unknown           | 2352      | 11.33%  |
| X-Cinnamon        | 2276      | 10.96%  |
| XFCE              | 1549      | 7.46%   |
| MATE              | 595       | 2.87%   |
| KDE               | 489       | 2.36%   |
| Cinnamon          | 298       | 1.44%   |
| KDE4              | 203       | 0.98%   |
| Pantheon          | 168       | 0.81%   |
| LXQt              | 159       | 0.77%   |
| Budgie            | 126       | 0.61%   |
| i3                | 118       | 0.57%   |
| Unity             | 117       | 0.56%   |
| LXDE              | 106       | 0.51%   |
| GNOME Flashback   | 41        | 0.2%    |
| Deepin            | 40        | 0.19%   |
| GNOME Classic     | 29        | 0.14%   |
| sway              | 25        | 0.12%   |
| awesome           | 25        | 0.12%   |
| lightdm-xsession  | 19        | 0.09%   |
| openbox           | 17        | 0.08%   |
| Hyprland          | 16        | 0.08%   |
| bspwm             | 12        | 0.06%   |
| qtile             | 9         | 0.04%   |
| DWM               | 9         | 0.04%   |
| xmonad            | 8         | 0.04%   |
| herbstluftwm      | 8         | 0.04%   |
| trinity           | 7         | 0.03%   |
| chadwm            | 7         | 0.03%   |
| enlightenment     | 6         | 0.03%   |
| LeftWM            | 4         | 0.02%   |
| ICEWM             | 4         | 0.02%   |
| Yaru:ubuntu:GNOME | 3         | 0.01%   |
| x-session-manager | 2         | 0.01%   |
| Phosh:GNOME       | 2         | 0.01%   |
| i3-with-shmlog    | 2         | 0.01%   |
| fluxbox           | 2         | 0.01%   |
| default           | 2         | 0.01%   |
| cwm               | 2         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 15640     | 76.44%  |
| Wayland     | 3134      | 15.32%  |
| Unknown     | 1189      | 5.81%   |
| Tty         | 493       | 2.41%   |
| Web         | 3         | 0.01%   |
| Unspecified | 2         | 0.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 9971      | 48.19%  |
| SDDM    | 3209      | 15.51%  |
| GDM3    | 2511      | 12.14%  |
| LightDM | 2365      | 11.43%  |
| GDM     | 1684      | 8.14%   |
| TDM     | 641       | 3.1%    |
| KDM     | 205       | 0.99%   |
| XDM     | 36        | 0.17%   |
| SLiM    | 28        | 0.14%   |
| LXDM    | 13        | 0.06%   |
| NODM    | 10        | 0.05%   |
| MDM     | 6         | 0.03%   |
| GREETD  | 6         | 0.03%   |
| Ly      | 5         | 0.02%   |
| WDM     | 1         | 0.005%  |
| LY-DM   | 1         | 0.005%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| de_DE      | 13111     | 64.61%  |
| en_US      | 3683      | 18.15%  |
| Unknown    | 2126      | 10.48%  |
| en_GB      | 384       | 1.89%   |
| C          | 316       | 1.56%   |
| ru_RU      | 92        | 0.45%   |
| en_DE      | 62        | 0.31%   |
| pl_PL      | 51        | 0.25%   |
| POSIX      | 50        | 0.25%   |
| it_IT      | 36        | 0.18%   |
| fr_FR      | 35        | 0.17%   |
| es_ES      | 29        | 0.14%   |
| de_AT      | 29        | 0.14%   |
| C.UTF8     | 22        | 0.11%   |
| hu_HU      | 19        | 0.09%   |
| de_CH      | 18        | 0.09%   |
| en_IE      | 17        | 0.08%   |
| nl_NL      | 16        | 0.08%   |
| en_DK      | 13        | 0.06%   |
| en_CA      | 13        | 0.06%   |
| ro_RO      | 12        | 0.06%   |
| ru_UA      | 10        | 0.05%   |
| de_BE      | 10        | 0.05%   |
| tr_TR      | 8         | 0.04%   |
| en_IN      | 8         | 0.04%   |
| en_AU      | 7         | 0.03%   |
| pt_BR      | 6         | 0.03%   |
| en_AG      | 6         | 0.03%   |
| bg_BG      | 6         | 0.03%   |
| uk_UA      | 5         | 0.02%   |
| el_GR      | 5         | 0.02%   |
| sk_SK      | 4         | 0.02%   |
| pt_PT      | 4         | 0.02%   |
| de_IT      | 4         | 0.02%   |
| de_DE@euro | 4         | 0.02%   |
| de_DE.UTF8 | 4         | 0.02%   |
| cs_CZ      | 4         | 0.02%   |
| nds_DE     | 3         | 0.01%   |
| hr_HR      | 3         | 0.01%   |
| de_LI      | 3         | 0.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 10766     | 53.02%  |
| EFI  | 9541      | 46.98%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type          | Computers | Percent |
|---------------|-----------|---------|
| Ext4          | 15364     | 75.39%  |
| Overlay       | 1731      | 8.49%   |
| Btrfs         | 1706      | 8.37%   |
| Unknown       | 624       | 3.06%   |
| Tmpfs         | 381       | 1.87%   |
| Xfs           | 245       | 1.2%    |
| Zfs           | 140       | 0.69%   |
| Ext2          | 73        | 0.36%   |
| Ext3          | 54        | 0.26%   |
| F2fs          | 35        | 0.17%   |
| Reiserfs      | 7         | 0.03%   |
| Rootfs        | 4         | 0.02%   |
| Aufs          | 4         | 0.02%   |
| XXXXXXX       | 3         | 0.01%   |
| Jfs           | 2         | 0.01%   |
| XXXXX         | 1         | 0.005%  |
| XXXX          | 1         | 0.005%  |
| XXXfs         | 1         | 0.005%  |
| XXX4          | 1         | 0.005%  |
| OveXlay       | 1         | 0.005%  |
| Fuse.snapfuse | 1         | 0.005%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 10613     | 51.98%  |
| GPT     | 7442      | 36.45%  |
| MBR     | 2364      | 11.58%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 16841     | 83.01%  |
| Yes       | 3446      | 16.99%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 14317     | 70.76%  |
| Yes       | 5917      | 29.24%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 3212      | 16.2%   |
| ASUSTek Computer        | 2837      | 14.31%  |
| Hewlett-Packard         | 2216      | 11.18%  |
| Dell                    | 1671      | 8.43%   |
| Acer                    | 1332      | 6.72%   |
| MSI                     | 1324      | 6.68%   |
| Gigabyte Technology     | 1320      | 6.66%   |
| ASRock                  | 969       | 4.89%   |
| Fujitsu                 | 619       | 3.12%   |
| Medion                  | 533       | 2.69%   |
| Apple                   | 378       | 1.91%   |
| Toshiba                 | 266       | 1.34%   |
| Intel                   | 229       | 1.16%   |
| Samsung Electronics     | 226       | 1.14%   |
| TUXEDO                  | 209       | 1.05%   |
| Raspberry Pi Foundation | 176       | 0.89%   |
| Sony                    | 173       | 0.87%   |
| Fujitsu Siemens         | 168       | 0.85%   |
| Unknown                 | 153       | 0.77%   |
| HUAWEI                  | 129       | 0.65%   |
| Packard Bell            | 116       | 0.59%   |
| Notebook                | 96        | 0.48%   |
| Valve                   | 94        | 0.47%   |
| Biostar                 | 81        | 0.41%   |
| Schenker                | 75        | 0.38%   |
| Supermicro              | 70        | 0.35%   |
| Microsoft               | 69        | 0.35%   |
| Foxconn                 | 58        | 0.29%   |
| Wortmann AG             | 57        | 0.29%   |
| BESSTAR Tech            | 50        | 0.25%   |
| ZOTAC                   | 43        | 0.22%   |
| Shuttle                 | 43        | 0.22%   |
| Pegatron                | 41        | 0.21%   |
| TrekStor                | 39        | 0.2%    |
| AMI                     | 35        | 0.18%   |
| Google                  | 27        | 0.14%   |
| Chuwi                   | 27        | 0.14%   |
| IBM                     | 26        | 0.13%   |
| ASRockRack              | 25        | 0.13%   |
| AZW                     | 23        | 0.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                          | Computers | Percent |
|-------------------------------|-----------|---------|
| Unknown                       | 238       | 1.2%    |
| ASUS All Series               | 134       | 0.68%   |
| Valve Jupiter                 | 94        | 0.47%   |
| MSI MS-7C37                   | 71        | 0.36%   |
| RPi Raspberry Pi              | 70        | 0.35%   |
| MSI MS-7B86                   | 62        | 0.31%   |
| HP Notebook                   | 52        | 0.26%   |
| MSI MS-7A38                   | 48        | 0.24%   |
| ASUS PRIME A320M-K            | 47        | 0.24%   |
| ASUS PRIME B350-PLUS          | 38        | 0.19%   |
| ASRock B450M Pro4             | 37        | 0.19%   |
| MSI MS-7B79                   | 35        | 0.18%   |
| MSI MS-7C02                   | 34        | 0.17%   |
| ASUS M5A78L-M/USB3            | 34        | 0.17%   |
| MSI MS-7B89                   | 33        | 0.17%   |
| Gigabyte X570 AORUS ELITE     | 32        | 0.16%   |
| Dell OptiPlex 7010            | 32        | 0.16%   |
| MSI MS-7C56                   | 31        | 0.16%   |
| Lenovo IdeaPad 5 15ARE05 81YQ | 30        | 0.15%   |
| ASUS PRIME X370-PRO           | 30        | 0.15%   |
| Gigabyte 970A-DS3P            | 29        | 0.15%   |
| ASUS P50IJ                    | 29        | 0.15%   |
| Dell OptiPlex 790             | 28        | 0.14%   |
| HP 255 G7 Notebook PC         | 27        | 0.14%   |
| MSI MS-7693                   | 25        | 0.13%   |
| ASUS A68HM-PLUS               | 25        | 0.13%   |
| MSI MS-7C52                   | 24        | 0.12%   |
| Dell Latitude E6420           | 24        | 0.12%   |
| ASUS TUF Gaming X570-PLUS     | 24        | 0.12%   |
| ASUS A0000001                 | 24        | 0.12%   |
| MSI MS-7C91                   | 23        | 0.12%   |
| HP Laptop 15s-eq2xxx          | 23        | 0.12%   |
| Gigabyte GA-78LMT-USB3 6.0    | 23        | 0.12%   |
| Dell Latitude E6430           | 23        | 0.12%   |
| ASUS M5A97 R2.0               | 23        | 0.12%   |
| ASRock 970 Pro3 R2.0          | 23        | 0.12%   |
| Supermicro Super Server       | 22        | 0.11%   |
| Dell OptiPlex 780             | 22        | 0.11%   |
| Dell Latitude E6410           | 22        | 0.11%   |
| ASUS TUF Gaming B550-PLUS     | 22        | 0.11%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 1861      | 9.39%   |
| Acer Aspire           | 883       | 4.45%   |
| Dell Latitude         | 570       | 2.88%   |
| Lenovo IdeaPad        | 424       | 2.14%   |
| ASUS PRIME            | 360       | 1.82%   |
| HP EliteBook          | 352       | 1.78%   |
| HP Pavilion           | 282       | 1.42%   |
| ASUS ROG              | 264       | 1.33%   |
| Fujitsu LIFEBOOK      | 251       | 1.27%   |
| Dell OptiPlex         | 250       | 1.26%   |
| HP Laptop             | 249       | 1.26%   |
| Fujitsu ESPRIMO       | 244       | 1.23%   |
| HP Compaq             | 238       | 1.2%    |
| Unknown               | 238       | 1.2%    |
| Dell XPS              | 225       | 1.13%   |
| Toshiba Satellite     | 216       | 1.09%   |
| Dell Inspiron         | 215       | 1.08%   |
| Dell Precision        | 210       | 1.06%   |
| HP ProBook            | 204       | 1.03%   |
| RPi Raspberry         | 174       | 0.88%   |
| Lenovo ThinkCentre    | 165       | 0.83%   |
| ASUS All              | 134       | 0.68%   |
| ASUS TUF              | 130       | 0.66%   |
| Lenovo Yoga           | 126       | 0.64%   |
| Acer Swift            | 110       | 0.55%   |
| ASUS VivoBook         | 109       | 0.55%   |
| HP ENVY               | 108       | 0.54%   |
| Valve Jupiter         | 94        | 0.47%   |
| Acer TravelMate       | 88        | 0.44%   |
| ASUS M5A78L-M         | 86        | 0.43%   |
| Medion Akoya          | 83        | 0.42%   |
| Packard Bell EasyNote | 75        | 0.38%   |
| Dell Vostro           | 73        | 0.37%   |
| ASUS ZenBook          | 72        | 0.36%   |
| MSI MS-7C37           | 71        | 0.36%   |
| Gigabyte X570         | 71        | 0.36%   |
| HP EliteDesk          | 70        | 0.35%   |
| Microsoft Surface     | 69        | 0.35%   |
| HP 255                | 65        | 0.33%   |
| HP ZBook              | 64        | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 1781      | 8.98%   |
| 2019    | 1739      | 8.77%   |
| 2020    | 1731      | 8.73%   |
| 2012    | 1687      | 8.51%   |
| 2011    | 1457      | 7.35%   |
| 2013    | 1344      | 6.78%   |
| 2017    | 1299      | 6.55%   |
| 2021    | 1194      | 6.02%   |
| 2014    | 1123      | 5.66%   |
| 2010    | 1111      | 5.6%    |
| 2015    | 990       | 4.99%   |
| 2016    | 943       | 4.76%   |
| 2009    | 862       | 4.35%   |
| 2008    | 784       | 3.95%   |
| 2022    | 637       | 3.21%   |
| 2007    | 450       | 2.27%   |
| Unknown | 255       | 1.29%   |
| 2006    | 212       | 1.07%   |
| 2023    | 92        | 0.46%   |
| 2005    | 83        | 0.42%   |
| 2004    | 26        | 0.13%   |
| 2003    | 13        | 0.07%   |
| 2002    | 5         | 0.03%   |
| 2000    | 5         | 0.03%   |
| 2001    | 1         | 0.01%   |
| 1999    | 1         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 10251     | 51.71%  |
| Desktop        | 7890      | 39.8%   |
| Convertible    | 550       | 2.77%   |
| Mini pc        | 346       | 1.75%   |
| System on chip | 234       | 1.18%   |
| Tablet         | 234       | 1.18%   |
| All in one     | 174       | 0.88%   |
| Server         | 132       | 0.67%   |
| Phone          | 12        | 0.06%   |
| Stick pc       | 2         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 18521     | 92.72%  |
| Enabled  | 1454      | 7.28%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 19770     | 99.72%  |
| Yes  | 55        | 0.28%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 4457      | 22.12%  |
| 16.01-24.0      | 3994      | 19.82%  |
| 3.01-4.0        | 3795      | 18.83%  |
| 8.01-16.0       | 3695      | 18.34%  |
| 32.01-64.0      | 2064      | 10.24%  |
| 1.01-2.0        | 672       | 3.34%   |
| 64.01-256.0     | 617       | 3.06%   |
| 24.01-32.0      | 377       | 1.87%   |
| 2.01-3.0        | 272       | 1.35%   |
| 0.51-1.0        | 149       | 0.74%   |
| More than 256.0 | 28        | 0.14%   |
| 0.01-0.5        | 25        | 0.12%   |
| Unknown         | 4         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 8745      | 39.37%  |
| 2.01-3.0    | 5276      | 23.76%  |
| 4.01-8.0    | 2802      | 12.62%  |
| 3.01-4.0    | 2453      | 11.04%  |
| 0.51-1.0    | 1566      | 7.05%   |
| 8.01-16.0   | 784       | 3.53%   |
| 0.01-0.5    | 339       | 1.53%   |
| 16.01-24.0  | 132       | 0.59%   |
| 24.01-32.0  | 47        | 0.21%   |
| 32.01-64.0  | 42        | 0.19%   |
| 64.01-256.0 | 11        | 0.05%   |
| Unknown     | 8         | 0.04%   |
| 0           | 5         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 11712     | 56.94%  |
| 2       | 5160      | 25.09%  |
| 3       | 1741      | 8.46%   |
| 4       | 898       | 4.37%   |
| 5       | 422       | 2.05%   |
| 0       | 212       | 1.03%   |
| 6       | 203       | 0.99%   |
| 7       | 97        | 0.47%   |
| 8       | 43        | 0.21%   |
| 9       | 23        | 0.11%   |
| 10      | 15        | 0.07%   |
| Unknown | 11        | 0.05%   |
| 13      | 9         | 0.04%   |
| 17      | 5         | 0.02%   |
| 12      | 5         | 0.02%   |
| 11      | 4         | 0.02%   |
| 14      | 2         | 0.01%   |
| 79      | 1         | 0.005%  |
| 32      | 1         | 0.005%  |
| 29      | 1         | 0.005%  |
| 23      | 1         | 0.005%  |
| 22      | 1         | 0.005%  |
| 20      | 1         | 0.005%  |
| 16      | 1         | 0.005%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 10664     | 53.29%  |
| Yes       | 9348      | 46.71%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 17442     | 87.72%  |
| No        | 2441      | 12.28%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 14146     | 70.83%  |
| No        | 5826      | 29.17%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 11013     | 54.67%  |
| No        | 9132      | 45.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Germany | 19825     | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Berlin               | 1795      | 8.31%   |
| Munich               | 908       | 4.2%    |
| Hamburg              | 831       | 3.85%   |
| Frankfurt am Main    | 673       | 3.12%   |
| Cologne              | 479       | 2.22%   |
| Stuttgart            | 416       | 1.93%   |
| Leipzig              | 333       | 1.54%   |
| Nuremberg            | 244       | 1.13%   |
| Dresden              | 242       | 1.12%   |
| Essen                | 230       | 1.06%   |
| Düsseldorf          | 229       | 1.06%   |
| Karlsruhe            | 204       | 0.94%   |
| Mannheim             | 203       | 0.94%   |
| Dortmund             | 178       | 0.82%   |
| Duisburg             | 148       | 0.69%   |
| Hanover              | 143       | 0.66%   |
| Bonn                 | 142       | 0.66%   |
| Bremen               | 133       | 0.62%   |
| Wuppertal            | 124       | 0.57%   |
| Augsburg             | 117       | 0.54%   |
| Bochum               | 114       | 0.53%   |
| Bielefeld            | 114       | 0.53%   |
| Munster              | 110       | 0.51%   |
| Darmstadt            | 110       | 0.51%   |
| Braunschweig         | 106       | 0.49%   |
| Wiesbaden            | 98        | 0.45%   |
| Mainz                | 96        | 0.44%   |
| Chemnitz             | 95        | 0.44%   |
| Kiel                 | 93        | 0.43%   |
| Aachen               | 90        | 0.42%   |
| Regensburg           | 89        | 0.41%   |
| Falkenstein          | 86        | 0.4%    |
| Halle                | 78        | 0.36%   |
| Freiburg im Breisgau | 73        | 0.34%   |
| Krefeld              | 71        | 0.33%   |
| Bamberg              | 71        | 0.33%   |
| Erfurt               | 70        | 0.32%   |
| Mönchengladbach     | 69        | 0.32%   |
| Reutlingen           | 68        | 0.31%   |
| Ulm                  | 67        | 0.31%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 6278      | 10148  | 21.2%   |
| WDC                         | 3918      | 6392   | 13.23%  |
| Seagate                     | 3542      | 5650   | 11.96%  |
| SanDisk                     | 2295      | 3297   | 7.75%   |
| Toshiba                     | 1861      | 2604   | 6.28%   |
| Crucial                     | 1440      | 2069   | 4.86%   |
| Unknown                     | 1365      | 1945   | 4.61%   |
| Kingston                    | 975       | 1301   | 3.29%   |
| Hitachi                     | 876       | 1163   | 2.96%   |
| Intenso                     | 834       | 1157   | 2.82%   |
| SK hynix                    | 655       | 823    | 2.21%   |
| Intel                       | 619       | 863    | 2.09%   |
| Micron Technology           | 476       | 628    | 1.61%   |
| HGST                        | 394       | 580    | 1.33%   |
| Phison                      | 225       | 314    | 0.76%   |
| A-DATA Technology           | 223       | 295    | 0.75%   |
| Transcend                   | 167       | 207    | 0.56%   |
| KIOXIA                      | 167       | 208    | 0.56%   |
| OCZ                         | 161       | 211    | 0.54%   |
| Apple                       | 153       | 194    | 0.52%   |
| Micron/Crucial Technology   | 147       | 202    | 0.5%    |
| Fujitsu                     | 131       | 168    | 0.44%   |
| China                       | 115       | 140    | 0.39%   |
| Unknown                     | 110       | 126    | 0.37%   |
| LITEON                      | 105       | 115    | 0.35%   |
| Phison Electronics          | 103       | 129    | 0.35%   |
| Patriot                     | 102       | 142    | 0.34%   |
| SPCC                        | 95        | 128    | 0.32%   |
| Silicon Motion              | 92        | 121    | 0.31%   |
| JMicron Technology          | 86        | 96     | 0.29%   |
| Maxtor                      | 81        | 122    | 0.27%   |
| Corsair                     | 78        | 101    | 0.26%   |
| ASMT                        | 78        | 98     | 0.26%   |
| Kingston Technology Company | 71        | 92     | 0.24%   |
| LITEONIT                    | 62        | 74     | 0.21%   |
| Leven                       | 61        | 82     | 0.21%   |
| PNY                         | 55        | 85     | 0.19%   |
| Netac                       | 51        | 65     | 0.17%   |
| SABRENT                     | 47        | 57     | 0.16%   |
| Apacer                      | 46        | 53     | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB                             | 384       | 1.15%   |
| Samsung SSD 860 EVO 500GB                             | 336       | 1.01%   |
| Samsung SSD 850 EVO 500GB                             | 306       | 0.92%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB   | 291       | 0.88%   |
| Crucial CT1000MX500SSD1 1TB                           | 232       | 0.7%    |
| Unknown MMC Card  64GB                                | 229       | 0.69%   |
| Unknown MMC Card  32GB                                | 227       | 0.68%   |
| Crucial CT500MX500SSD1 500GB                          | 219       | 0.66%   |
| Samsung SSD 860 EVO 1TB                               | 211       | 0.63%   |
| Samsung NVMe SSD Drive 500GB                          | 180       | 0.54%   |
| Toshiba MQ01ABD100 1TB                                | 166       | 0.5%    |
| SanDisk SSD PLUS 240GB                                | 163       | 0.49%   |
| Samsung NVMe SSD Drive 512GB                          | 160       | 0.48%   |
| Samsung SSD 860 EVO 250GB                             | 157       | 0.47%   |
| Toshiba DT01ACA100 1TB                                | 153       | 0.46%   |
| Samsung SSD 840 EVO 250GB                             | 153       | 0.46%   |
| Samsung NVMe SSD Drive 1TB                            | 153       | 0.46%   |
| SanDisk SSD PLUS 1000GB                               | 152       | 0.46%   |
| Seagate ST500DM002-1BD142 500GB                       | 150       | 0.45%   |
| Samsung SSD 970 EVO Plus 1TB                          | 149       | 0.45%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 148       | 0.45%   |
| Crucial CT240BX500SSD1 240GB                          | 136       | 0.41%   |
| Unknown SD/MMC/MS PRO 1GB                             | 133       | 0.4%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1024GB | 131       | 0.39%   |
| Unknown MMC Card  128GB                               | 123       | 0.37%   |
| SanDisk SSD PLUS 480GB                                | 123       | 0.37%   |
| SanDisk NVMe SSD Drive 512GB                          | 118       | 0.35%   |
| Samsung SSD 840 EVO 120GB                             | 114       | 0.34%   |
| Toshiba HDWD110 1TB                                   | 112       | 0.34%   |
| Seagate ST1000LM035-1RK172 1TB                        | 111       | 0.33%   |
| Kingston SA400S37240G 240GB SSD                       | 111       | 0.33%   |
| Seagate ST9500325AS 500GB                             | 110       | 0.33%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB                | 110       | 0.33%   |
| Unknown                                               | 110       | 0.33%   |
| Samsung SSD 860 QVO 1TB                               | 104       | 0.31%   |
| Intenso SSD SATAIII 240GB                             | 103       | 0.31%   |
| Seagate ST2000DM008-2FR102 2TB                        | 102       | 0.31%   |
| Seagate ST1000DM010-2EP102 1TB                        | 102       | 0.31%   |
| Samsung SSD 970 EVO Plus 500GB                        | 101       | 0.3%    |
| Samsung SSD 870 QVO 1TB                               | 99        | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3463      | 5528   | 32.19%  |
| WDC                 | 3196      | 5338   | 29.71%  |
| Toshiba             | 1331      | 1894   | 12.37%  |
| Hitachi             | 876       | 1163   | 8.14%   |
| Samsung Electronics | 800       | 1221   | 7.44%   |
| HGST                | 394       | 580    | 3.66%   |
| Unknown             | 141       | 208    | 1.31%   |
| Fujitsu             | 131       | 168    | 1.22%   |
| Intenso             | 82        | 125    | 0.76%   |
| Maxtor              | 77        | 115    | 0.72%   |
| SABRENT             | 38        | 47     | 0.35%   |
| Apple               | 37        | 41     | 0.34%   |
| ASMT                | 22        | 25     | 0.2%    |
| USB3.0              | 14        | 15     | 0.13%   |
| WD MediaMax         | 13        | 19     | 0.12%   |
| ASMedia             | 13        | 15     | 0.12%   |
| IBM/Hitachi         | 11        | 11     | 0.1%    |
| ExcelStor           | 11        | 12     | 0.1%    |
| USB                 | 10        | 11     | 0.09%   |
| Inateck             | 8         | 8      | 0.07%   |
| SSK                 | 7         | 8      | 0.07%   |
| Hewlett-Packard     | 7         | 26     | 0.07%   |
| External            | 7         | 7      | 0.07%   |
| HGST HTS            | 6         | 6      | 0.06%   |
| IBM                 | 5         | 6      | 0.05%   |
| Dell                | 5         | 9      | 0.05%   |
| HPE                 | 4         | 13     | 0.04%   |
| MDT                 | 3         | 3      | 0.03%   |
| Maxone              | 3         | 4      | 0.03%   |
| LIO-ORG             | 3         | 10     | 0.03%   |
| Unknown             | 3         | 3      | 0.03%   |
| SILICONMOTION       | 2         | 3      | 0.02%   |
| QUANTUM             | 2         | 2      | 0.02%   |
| MARVELL             | 2         | 2      | 0.02%   |
| Magnetic Data       | 2         | 3      | 0.02%   |
| LaCie               | 2         | 2      | 0.02%   |
| KESU                | 2         | 2      | 0.02%   |
| IET                 | 2         | 2      | 0.02%   |
| IB-377U3            | 2         | 2      | 0.02%   |
| DELLBOSS            | 2         | 2      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3496      | 5195   | 31.2%   |
| SanDisk             | 1712      | 2518   | 15.28%  |
| Crucial             | 1328      | 1902   | 11.85%  |
| Kingston            | 645       | 871    | 5.76%   |
| Intenso             | 634       | 852    | 5.66%   |
| WDC                 | 429       | 561    | 3.83%   |
| Intel               | 248       | 342    | 2.21%   |
| Micron Technology   | 233       | 309    | 2.08%   |
| Toshiba             | 225       | 280    | 2.01%   |
| A-DATA Technology   | 184       | 244    | 1.64%   |
| OCZ                 | 157       | 203    | 1.4%    |
| Transcend           | 152       | 183    | 1.36%   |
| SK hynix            | 152       | 184    | 1.36%   |
| China               | 112       | 136    | 1%      |
| LITEON              | 97        | 107    | 0.87%   |
| Patriot             | 90        | 127    | 0.8%    |
| Apple               | 85        | 99     | 0.76%   |
| SPCC                | 80        | 106    | 0.71%   |
| LITEONIT            | 62        | 74     | 0.55%   |
| JMicron Technology  | 60        | 66     | 0.54%   |
| Leven               | 59        | 80     | 0.53%   |
| ASMT                | 51        | 66     | 0.46%   |
| Netac               | 46        | 59     | 0.41%   |
| Corsair             | 44        | 61     | 0.39%   |
| INNOVATION IT       | 43        | 57     | 0.38%   |
| Apacer              | 42        | 49     | 0.37%   |
| Unknown             | 42        | 51     | 0.37%   |
| PNY                 | 41        | 67     | 0.37%   |
| Verbatim            | 39        | 60     | 0.35%   |
| Phison              | 33        | 56     | 0.29%   |
| Unknown             | 32        | 33     | 0.29%   |
| Hewlett-Packard     | 27        | 34     | 0.24%   |
| Emtec               | 27        | 30     | 0.24%   |
| Seagate             | 24        | 31     | 0.21%   |
| KingDian            | 23        | 28     | 0.21%   |
| Team                | 20        | 27     | 0.18%   |
| Plextor             | 19        | 20     | 0.17%   |
| Mushkin             | 19        | 33     | 0.17%   |
| GOODRAM             | 17        | 22     | 0.15%   |
| Fanxiang            | 17        | 22     | 0.15%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 9582      | 15718  | 36.32%  |
| HDD     | 8872      | 16685  | 33.63%  |
| NVMe    | 6224      | 9140   | 23.59%  |
| MMC     | 1224      | 1631   | 4.64%   |
| Unknown | 479       | 736    | 1.82%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 14745     | 31043  | 62.71%  |
| NVMe | 6218      | 9114   | 26.44%  |
| SAS  | 1327      | 2122   | 5.64%   |
| MMC  | 1224      | 1631   | 5.21%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 11257     | 18374  | 57.47%  |
| 0.51-1.0        | 5346      | 8480   | 27.29%  |
| 1.01-2.0        | 1729      | 2952   | 8.83%   |
| 3.01-4.0        | 532       | 1054   | 2.72%   |
| 2.01-3.0        | 356       | 665    | 1.82%   |
| 4.01-10.0       | 296       | 735    | 1.51%   |
| 10.01-20.0      | 63        | 128    | 0.32%   |
| 20.01-50.0      | 4         | 8      | 0.02%   |
| 0               | 2         | 2      | 0.01%   |
| More than 100.0 | 1         | 1      | 0.01%   |
| 50.01-100.0     | 1         | 4      | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 5494      | 25.8%   |
| 251-500        | 4570      | 21.46%  |
| 501-1000       | 3138      | 14.74%  |
| 1001-2000      | 1698      | 7.97%   |
| 1-20           | 1620      | 7.61%   |
| 51-100         | 1328      | 6.24%   |
| More than 3000 | 1179      | 5.54%   |
| Unknown        | 811       | 3.81%   |
| 21-50          | 780       | 3.66%   |
| 2001-3000      | 675       | 3.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 8220      | 37.07%  |
| 21-50          | 3655      | 16.48%  |
| 101-250        | 2697      | 12.16%  |
| 51-100         | 2400      | 10.82%  |
| 251-500        | 1725      | 7.78%   |
| 501-1000       | 1201      | 5.42%   |
| Unknown        | 811       | 3.66%   |
| 1001-2000      | 757       | 3.41%   |
| More than 3000 | 419       | 1.89%   |
| 2001-3000      | 281       | 1.27%   |
| 0              | 7         | 0.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 20        | 28     | 1.34%   |
| Toshiba MQ01ABD100 1TB                | 14        | 18     | 0.94%   |
| Seagate ST9500325AS 500GB             | 14        | 20     | 0.94%   |
| Crucial CT525MX300SSD1 528GB          | 14        | 16     | 0.94%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 13        | 17     | 0.87%   |
| SanDisk SSD PLUS 480GB                | 13        | 14     | 0.87%   |
| Seagate ST9320325AS 320GB             | 12        | 13     | 0.81%   |
| Samsung Electronics HD103UJ 1TB       | 12        | 12     | 0.81%   |
| WDC WD20EARS-00MVWB0 2TB              | 10        | 13     | 0.67%   |
| Seagate ST1000LM035-1RK172 1TB        | 10        | 10     | 0.67%   |
| SanDisk SSD PLUS 240GB                | 10        | 12     | 0.67%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 9         | 10     | 0.61%   |
| WDC WD10EARS-00Y5B1 1TB               | 9         | 11     | 0.61%   |
| Seagate ST500LT012-1DG142 500GB       | 9         | 9      | 0.61%   |
| Samsung Electronics SP2504C 250GB     | 9         | 10     | 0.61%   |
| Samsung Electronics HD501LJ 500GB     | 9         | 19     | 0.61%   |
| WDC WD20EFRX-68EUZN0 2TB              | 8         | 13     | 0.54%   |
| Seagate ST500LT012-9WS142 500GB       | 8         | 10     | 0.54%   |
| Seagate ST500LM000-1EJ162 500GB       | 8         | 11     | 0.54%   |
| Seagate ST3500418AS 500GB             | 8         | 9      | 0.54%   |
| SanDisk SSD PLUS 1000GB               | 8         | 9      | 0.54%   |
| HGST HTS725050A7E630 500GB            | 8         | 8      | 0.54%   |
| HGST HTS545050A7E680 500GB            | 8         | 12     | 0.54%   |
| HGST HTS541010A9E680 1TB              | 8         | 8      | 0.54%   |
| WDC WD30EFRX-68EUZN0 3TB              | 7         | 10     | 0.47%   |
| WDC WD10JPVX-22JC3T0 1TB              | 7         | 9      | 0.47%   |
| Seagate ST500LM000-SSHD-8GB           | 7         | 7      | 0.47%   |
| Seagate ST31000528AS 1TB              | 7         | 8      | 0.47%   |
| Seagate ST1000DM003-9YN162 1TB        | 7         | 9      | 0.47%   |
| Samsung Electronics SSD 970 EVO 500GB | 7         | 8      | 0.47%   |
| Kingston SV300S37A120G 120GB SSD      | 7         | 8      | 0.47%   |
| HGST HTS721010A9E630 1TB              | 7         | 8      | 0.47%   |
| WDC WD5000AADS-00S9B0 500GB           | 6         | 7      | 0.4%    |
| WDC WD20EARX-00PASB0 2TB              | 6         | 6      | 0.4%    |
| Toshiba DT01ACA100 1TB                | 6         | 7      | 0.4%    |
| Seagate ST9250315AS 250GB             | 6         | 7      | 0.4%    |
| Seagate ST2000DM001-1CH164 2TB        | 6         | 6      | 0.4%    |
| Seagate ST2000DL003-9VT166 2TB        | 6         | 6      | 0.4%    |
| Seagate ST1000DM003-1CH162 1TB        | 6         | 8      | 0.4%    |
| Samsung Electronics HD753LJ 752GB     | 6         | 7      | 0.4%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 351       | 442    | 24.11%  |
| WDC                   | 301       | 419    | 20.67%  |
| Samsung Electronics   | 190       | 237    | 13.05%  |
| Hitachi               | 111       | 136    | 7.62%   |
| Toshiba               | 85        | 95     | 5.84%   |
| SanDisk               | 79        | 92     | 5.43%   |
| Crucial               | 51        | 59     | 3.5%    |
| HGST                  | 44        | 54     | 3.02%   |
| Intel                 | 34        | 35     | 2.34%   |
| SK hynix              | 28        | 31     | 1.92%   |
| Micron Technology     | 26        | 35     | 1.79%   |
| Kingston              | 20        | 22     | 1.37%   |
| Intenso               | 20        | 22     | 1.37%   |
| Fujitsu               | 18        | 21     | 1.24%   |
| Maxtor                | 15        | 24     | 1.03%   |
| A-DATA Technology     | 9         | 10     | 0.62%   |
| Transcend             | 8         | 9      | 0.55%   |
| Apple                 | 7         | 8      | 0.48%   |
| OCZ                   | 5         | 7      | 0.34%   |
| WD MediaMax           | 4         | 4      | 0.27%   |
| IBM                   | 4         | 4      | 0.27%   |
| ASMedia               | 4         | 4      | 0.27%   |
| Unknown               | 3         | 3      | 0.21%   |
| MDT                   | 3         | 3      | 0.21%   |
| China                 | 3         | 3      | 0.21%   |
| XPG                   | 2         | 2      | 0.14%   |
| PNY                   | 2         | 3      | 0.14%   |
| LITEONIT              | 2         | 5      | 0.14%   |
| LITEON                | 2         | 2      | 0.14%   |
| IBM/Hitachi           | 2         | 2      | 0.14%   |
| USB3.0                | 1         | 1      | 0.07%   |
| TO Exter              | 1         | 1      | 0.07%   |
| SSSTC                 | 1         | 1      | 0.07%   |
| SPCC                  | 1         | 1      | 0.07%   |
| Realtek Semiconductor | 1         | 1      | 0.07%   |
| RDM-II                | 1         | 1      | 0.07%   |
| Plextor               | 1         | 1      | 0.07%   |
| Phison                | 1         | 1      | 0.07%   |
| OCZ-VERTEX2           | 1         | 1      | 0.07%   |
| Netac                 | 1         | 1      | 0.07%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 350       | 441    | 33.78%  |
| WDC                 | 280       | 396    | 27.03%  |
| Samsung Electronics | 113       | 145    | 10.91%  |
| Hitachi             | 111       | 136    | 10.71%  |
| Toshiba             | 79        | 87     | 7.63%   |
| HGST                | 44        | 54     | 4.25%   |
| Fujitsu             | 18        | 21     | 1.74%   |
| Maxtor              | 15        | 24     | 1.45%   |
| Apple               | 5         | 6      | 0.48%   |
| WD MediaMax         | 4         | 4      | 0.39%   |
| IBM                 | 4         | 4      | 0.39%   |
| MDT                 | 3         | 3      | 0.29%   |
| Intenso             | 2         | 2      | 0.19%   |
| IBM/Hitachi         | 2         | 2      | 0.19%   |
| USB3.0              | 1         | 1      | 0.1%    |
| Unknown             | 1         | 1      | 0.1%    |
| IB                  | 1         | 1      | 0.1%    |
| Hewlett-Packard     | 1         | 1      | 0.1%    |
| ExcelStor           | 1         | 1      | 0.1%    |
| ASMedia             | 1         | 1      | 0.1%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 972       | 1331   | 70.08%  |
| SSD  | 352       | 413    | 25.38%  |
| NVMe | 63        | 74     | 4.54%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Samsung Electronics HD103UJ 1TB                  | 3         | 5      | 9.09%   |
| Samsung Electronics SSD 980 1TB                  | 2         | 2      | 6.06%   |
| Samsung Electronics HD252HJ 250GB                | 2         | 2      | 6.06%   |
| WDC WD5000BEVT-00A0RT0 500GB                     | 1         | 1      | 3.03%   |
| WDC WD40EZRZ-00GXCB0 4TB                         | 1         | 2      | 3.03%   |
| WDC WD30EZRS-00J99B0 3TB                         | 1         | 1      | 3.03%   |
| WDC WD1600YS-23SHB0 160GB                        | 1         | 1      | 3.03%   |
| WDC PC SN520 SDAPMUW-512G-1001 512GB             | 1         | 1      | 3.03%   |
| TPH00800640GB 640GB                              | 1         | 1      | 3.03%   |
| Toshiba MK5065GSX 500GB                          | 1         | 1      | 3.03%   |
| Toshiba MK3265GSX 320GB                          | 1         | 1      | 3.03%   |
| Toshiba MK1059GSM 1TB                            | 1         | 1      | 3.03%   |
| Toshiba MG03ACA300 3TB                           | 1         | 1      | 3.03%   |
| Seagate ST9500325AS 500GB                        | 1         | 1      | 3.03%   |
| Seagate ST9320325AS 320GB                        | 1         | 1      | 3.03%   |
| Seagate ST3640323AS 640GB                        | 1         | 1      | 3.03%   |
| Samsung Electronics SSD 980 500GB                | 1         | 1      | 3.03%   |
| Samsung Electronics SSD 850 250GB                | 1         | 1      | 3.03%   |
| Samsung Electronics MZVLB1T0HALR-00000 1TB       | 1         | 2      | 3.03%   |
| Samsung Electronics MZNTY128HDHP-00000 128GB SSD | 1         | 1      | 3.03%   |
| Samsung Electronics MZ7LN256HCHP-00000 256GB SSD | 1         | 2      | 3.03%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD   | 1         | 1      | 3.03%   |
| Maxtor STM3500320AS 500GB                        | 1         | 1      | 3.03%   |
| Intenso SSD SATAIII 240GB                        | 1         | 1      | 3.03%   |
| Intel SSDSCKGF256A5 SATA 256GB                   | 1         | 1      | 3.03%   |
| Intel SSDSA2BW160G3 160GB                        | 1         | 1      | 3.03%   |
| Hitachi HTS541010G9SA00 100GB                    | 1         | 1      | 3.03%   |
| Hitachi HDP725040GLA360 400GB                    | 1         | 1      | 3.03%   |
| HGST HTS721010A9E630 1TB                         | 1         | 1      | 3.03%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 16     | 36.36%  |
| WDC                 | 5         | 6      | 15.15%  |
| Toshiba             | 4         | 4      | 12.12%  |
| Seagate             | 3         | 3      | 9.09%   |
| Intel               | 2         | 2      | 6.06%   |
| Hitachi             | 2         | 2      | 6.06%   |
| TPH00800640GB       | 1         | 1      | 3.03%   |
| Micron Technology   | 1         | 1      | 3.03%   |
| Maxtor              | 1         | 1      | 3.03%   |
| Intenso             | 1         | 1      | 3.03%   |
| HGST                | 1         | 1      | 3.03%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 12322     | 27160  | 57.38%  |
| Works    | 7767      | 14893  | 36.17%  |
| Malfunc  | 1351      | 1818   | 6.29%   |
| Failed   | 33        | 38     | 0.15%   |
| Limited  | 1         | 1      | 0.005%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 12348     | 49.23%  |
| AMD                              | 4390      | 17.5%   |
| Samsung Electronics              | 2710      | 10.8%   |
| SanDisk                          | 943       | 3.76%   |
| ASMedia Technology               | 492       | 1.96%   |
| SK hynix                         | 474       | 1.89%   |
| Kingston Technology Company      | 397       | 1.58%   |
| Nvidia                           | 386       | 1.54%   |
| Phison Electronics               | 360       | 1.44%   |
| Toshiba America Info Systems     | 319       | 1.27%   |
| JMicron Technology               | 317       | 1.26%   |
| Marvell Technology Group         | 313       | 1.25%   |
| Micron/Crucial Technology        | 277       | 1.1%    |
| Micron Technology                | 247       | 0.98%   |
| KIOXIA                           | 182       | 0.73%   |
| Silicon Motion                   | 123       | 0.49%   |
| VIA Technologies                 | 88        | 0.35%   |
| ADATA Technology                 | 82        | 0.33%   |
| LSI Logic / Symbios Logic        | 63        | 0.25%   |
| Silicon Image                    | 62        | 0.25%   |
| Broadcom / LSI                   | 59        | 0.24%   |
| Union Memory (Shenzhen)          | 57        | 0.23%   |
| Adaptec                          | 56        | 0.22%   |
| Seagate Technology               | 37        | 0.15%   |
| Silicon Integrated Systems [SiS] | 36        | 0.14%   |
| Realtek Semiconductor            | 29        | 0.12%   |
| Solid State Storage Technology   | 28        | 0.11%   |
| MAXIO Technology (Hangzhou)      | 28        | 0.11%   |
| Lenovo                           | 26        | 0.1%    |
| Apple                            | 25        | 0.1%    |
| Lite-On Technology               | 20        | 0.08%   |
| Shenzhen Longsys Electronics     | 15        | 0.06%   |
| Hewlett-Packard                  | 14        | 0.06%   |
| O2 Micro                         | 12        | 0.05%   |
| Integrated Technology Express    | 10        | 0.04%   |
| OCZ Technology Group             | 9         | 0.04%   |
| 3ware                            | 9         | 0.04%   |
| ULi Electronics                  | 4         | 0.02%   |
| INNOGRIT                         | 4         | 0.02%   |
| HighPoint Technologies           | 4         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 2736      | 9.36%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1543      | 5.28%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 901       | 3.08%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 888       | 3.04%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 884       | 3.02%   |
| AMD 400 Series Chipset SATA Controller                                         | 669       | 2.29%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 657       | 2.25%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 642       | 2.2%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 639       | 2.19%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 530       | 1.81%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 502       | 1.72%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 475       | 1.63%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 456       | 1.56%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 424       | 1.45%   |
| Samsung NVMe SSD Controller 980                                                | 419       | 1.43%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 412       | 1.41%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 400       | 1.37%   |
| AMD 500 Series Chipset SATA Controller                                         | 379       | 1.3%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 373       | 1.28%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 363       | 1.24%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 332       | 1.14%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 328       | 1.12%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 316       | 1.08%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 315       | 1.08%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 314       | 1.07%   |
| Intel Volume Management Device NVMe RAID Controller                            | 309       | 1.06%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 305       | 1.04%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 267       | 0.91%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 262       | 0.9%    |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 259       | 0.89%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 244       | 0.83%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 233       | 0.8%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 220       | 0.75%   |
| Intel SATA Controller [RAID mode]                                              | 210       | 0.72%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 199       | 0.68%   |
| JMicron JMB363 SATA/IDE Controller                                             | 194       | 0.66%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 190       | 0.65%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 183       | 0.63%   |
| Intel SSD 660P Series                                                          | 182       | 0.62%   |
| Intel Comet Lake SATA AHCI Controller                                          | 179       | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 14727     | 57.99%  |
| NVMe | 6282      | 24.74%  |
| IDE  | 2943      | 11.59%  |
| RAID | 1282      | 5.05%   |
| SAS  | 91        | 0.36%   |
| SCSI | 72        | 0.28%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 14068     | 70.96%  |
| AMD                   | 5486      | 27.67%  |
| ARM                   | 247       | 1.25%   |
| QUALCOMM              | 6         | 0.03%   |
| Unknown               | 6         | 0.03%   |
| CentaurHauls          | 3         | 0.02%   |
| thead,c906            | 2         | 0.01%   |
| Marvell Semiconductor | 2         | 0.01%   |
| PowerMac3,6           | 1         | 0.01%   |
| PowerMac10,2          | 1         | 0.01%   |
| PowerBook5,6          | 1         | 0.01%   |
| PowerBook5,4          | 1         | 0.01%   |
| PowerBook3,4          | 1         | 0.01%   |
| MIPS                  | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor             | 201       | 1.01%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 191       | 0.96%   |
| ARM Processor                                 | 178       | 0.89%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 175       | 0.88%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 171       | 0.86%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 163       | 0.82%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 161       | 0.81%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 159       | 0.8%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 156       | 0.78%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 153       | 0.77%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 141       | 0.71%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 139       | 0.7%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 137       | 0.69%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 132       | 0.66%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 128       | 0.64%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 128       | 0.64%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 123       | 0.62%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 119       | 0.6%    |
| AMD Ryzen 7 2700X Eight-Core Processor        | 116       | 0.58%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 108       | 0.54%   |
| AMD FX-8350 Eight-Core Processor              | 108       | 0.54%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 104       | 0.52%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 101       | 0.51%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 96        | 0.48%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 96        | 0.48%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 94        | 0.47%   |
| AMD Custom APU 0405                           | 94        | 0.47%   |
| AMD FX-6300 Six-Core Processor                | 90        | 0.45%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 84        | 0.42%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 83        | 0.42%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 82        | 0.41%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 82        | 0.41%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 81        | 0.41%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 81        | 0.41%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 79        | 0.4%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 76        | 0.38%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 76        | 0.38%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 76        | 0.38%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 75        | 0.38%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 75        | 0.38%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 4318      | 21.74%  |
| Intel Core i7           | 3332      | 16.77%  |
| AMD Ryzen 5             | 1306      | 6.57%   |
| Other                   | 1254      | 6.31%   |
| Intel Core i3           | 1157      | 5.82%   |
| AMD Ryzen 7             | 1133      | 5.7%    |
| Intel Core 2 Duo        | 926       | 4.66%   |
| Intel Celeron           | 819       | 4.12%   |
| Intel Pentium           | 557       | 2.8%    |
| AMD FX                  | 434       | 2.18%   |
| Intel Xeon              | 431       | 2.17%   |
| Intel Atom              | 407       | 2.05%   |
| AMD Ryzen 9             | 289       | 1.45%   |
| Intel Pentium Dual-Core | 231       | 1.16%   |
| AMD Ryzen 3             | 215       | 1.08%   |
| Intel Core 2 Quad       | 212       | 1.07%   |
| AMD A8                  | 183       | 0.92%   |
| AMD Phenom II X4        | 167       | 0.84%   |
| AMD Ryzen 7 PRO         | 149       | 0.75%   |
| AMD A4                  | 133       | 0.67%   |
| AMD A10                 | 132       | 0.66%   |
| Intel Pentium Silver    | 131       | 0.66%   |
| AMD Athlon II X2        | 123       | 0.62%   |
| Intel Core 2            | 121       | 0.61%   |
| AMD A6                  | 114       | 0.57%   |
| Intel Core i9           | 102       | 0.51%   |
| AMD E                   | 97        | 0.49%   |
| AMD Ryzen 5 PRO         | 88        | 0.44%   |
| Intel Pentium Dual      | 85        | 0.43%   |
| AMD Athlon 64 X2        | 76        | 0.38%   |
| Intel Genuine           | 68        | 0.34%   |
| AMD Athlon              | 68        | 0.34%   |
| AMD Athlon II X4        | 64        | 0.32%   |
| ARM BCM                 | 56        | 0.28%   |
| Intel Pentium 4         | 55        | 0.28%   |
| AMD Phenom II X6        | 47        | 0.24%   |
| AMD Ryzen Threadripper  | 46        | 0.23%   |
| AMD E2                  | 45        | 0.23%   |
| Intel Pentium M         | 44        | 0.22%   |
| AMD Turion 64 X2 Mobile | 44        | 0.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 7589      | 38.16%  |
| 4       | 7416      | 37.29%  |
| 6       | 1880      | 9.45%   |
| 8       | 1575      | 7.92%   |
| 1       | 492       | 2.47%   |
| 12      | 294       | 1.48%   |
| 16      | 158       | 0.79%   |
| 3       | 155       | 0.78%   |
| 10      | 100       | 0.5%    |
| 14      | 87        | 0.44%   |
| Unknown | 60        | 0.3%    |
| 24      | 28        | 0.14%   |
| 32      | 16        | 0.08%   |
| 18      | 10        | 0.05%   |
| 5       | 8         | 0.04%   |
| 20      | 5         | 0.03%   |
| 40      | 4         | 0.02%   |
| 80      | 2         | 0.01%   |
| 64      | 2         | 0.01%   |
| 36      | 2         | 0.01%   |
| 68      | 1         | 0.01%   |
| 28      | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 19649     | 99.1%   |
| 2       | 143       | 0.72%   |
| Unknown | 27        | 0.14%   |
| 4       | 7         | 0.04%   |
| 3       | 1         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 12774     | 64.28%  |
| 1       | 7029      | 35.37%  |
| Unknown | 60        | 0.3%    |
| 4       | 6         | 0.03%   |
| 8       | 2         | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 19198     | 96.61%  |
| Unknown        | 439       | 2.21%   |
| 32-bit         | 211       | 1.06%   |
| 64-bit         | 23        | 0.12%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 5272      | 25.48%  |
| 0x206a7    | 1087      | 5.25%   |
| 0x306a9    | 1061      | 5.13%   |
| 0x306c3    | 857       | 4.14%   |
| 0x1067a    | 718       | 3.47%   |
| 0x506e3    | 418       | 2.02%   |
| 0x906ea    | 403       | 1.95%   |
| 0x806ea    | 396       | 1.91%   |
| 0x806ec    | 373       | 1.8%    |
| 0x806c1    | 365       | 1.76%   |
| 0x40651    | 357       | 1.73%   |
| 0x406e3    | 351       | 1.7%    |
| 0x20655    | 334       | 1.61%   |
| 0x08701021 | 325       | 1.57%   |
| 0x806e9    | 315       | 1.52%   |
| 0x306d4    | 269       | 1.3%    |
| 0x906e9    | 266       | 1.29%   |
| 0x0800820d | 240       | 1.16%   |
| 0x010000c8 | 238       | 1.15%   |
| 0x06000852 | 235       | 1.14%   |
| 0x08108109 | 217       | 1.05%   |
| 0x6fd      | 206       | 1%      |
| 0x10676    | 204       | 0.99%   |
| 0x0a50000c | 201       | 0.97%   |
| 0x08600106 | 198       | 0.96%   |
| 0x406c4    | 193       | 0.93%   |
| 0x30678    | 175       | 0.85%   |
| 0x06001119 | 165       | 0.8%    |
| 0x08108102 | 164       | 0.79%   |
| 0x20652    | 163       | 0.79%   |
| 0x08608103 | 162       | 0.78%   |
| 0x706a1    | 156       | 0.75%   |
| 0x6fb      | 144       | 0.7%    |
| 0x08701013 | 136       | 0.66%   |
| 0x506c9    | 132       | 0.64%   |
| 0x806eb    | 126       | 0.61%   |
| 0x106e5    | 122       | 0.59%   |
| 0x706e5    | 111       | 0.54%   |
| 0x706a8    | 107       | 0.52%   |
| 0xa0652    | 104       | 0.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 2633      | 13.24%  |
| Haswell          | 1632      | 8.21%   |
| SandyBridge      | 1429      | 7.19%   |
| IvyBridge        | 1379      | 6.94%   |
| Penryn           | 1123      | 5.65%   |
| Skylake          | 1103      | 5.55%   |
| Zen 2            | 1076      | 5.41%   |
| Unknown          | 912       | 4.59%   |
| Zen+             | 795       | 4%      |
| Westmere         | 676       | 3.4%    |
| Zen 3            | 625       | 3.14%   |
| Silvermont       | 595       | 2.99%   |
| Core             | 585       | 2.94%   |
| Piledriver       | 549       | 2.76%   |
| K10              | 531       | 2.67%   |
| Zen              | 470       | 2.36%   |
| TigerLake        | 461       | 2.32%   |
| Broadwell        | 382       | 1.92%   |
| Goldmont plus    | 328       | 1.65%   |
| CometLake        | 291       | 1.46%   |
| IceLake          | 234       | 1.18%   |
| Nehalem          | 216       | 1.09%   |
| Alderlake Hybrid | 212       | 1.07%   |
| K8 Hammer        | 196       | 0.99%   |
| Excavator        | 195       | 0.98%   |
| Goldmont         | 176       | 0.89%   |
| Bonnell          | 173       | 0.87%   |
| Bobcat           | 161       | 0.81%   |
| Puma             | 121       | 0.61%   |
| P6               | 113       | 0.57%   |
| NetBurst         | 95        | 0.48%   |
| Bulldozer        | 87        | 0.44%   |
| Jaguar           | 79        | 0.4%    |
| Steamroller      | 76        | 0.38%   |
| K10 Llano        | 64        | 0.32%   |
| Tremont          | 57        | 0.29%   |
| K8 & K10 hybrid  | 37        | 0.19%   |
| K6               | 7         | 0.04%   |
| Gracemont        | 6         | 0.03%   |
| CannonLake       | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 10483     | 46.53%  |
| Nvidia                                       | 6058      | 26.89%  |
| AMD                                          | 5743      | 25.49%  |
| ASPEED Technology                            | 95        | 0.42%   |
| Matrox Electronics Systems                   | 91        | 0.4%    |
| Silicon Integrated Systems [SiS]             | 18        | 0.08%   |
| VIA Technologies                             | 16        | 0.07%   |
| ATI Technologies                             | 9         | 0.04%   |
| S3 Graphics                                  | 8         | 0.04%   |
| XGI Technology (eXtreme Graphics Innovation) | 3         | 0.01%   |
| Silicon Motion                               | 1         | 0.004%  |
| Neomagic                                     | 1         | 0.004%  |
| Huawei Technologies                          | 1         | 0.004%  |
| Dome Imaging Systems                         | 1         | 0.004%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 989       | 4.26%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 820       | 3.53%   |
| AMD Renoir                                                                               | 452       | 1.95%   |
| Intel UHD Graphics 620                                                                   | 449       | 1.93%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 445       | 1.92%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 440       | 1.89%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 418       | 1.8%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 412       | 1.77%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 383       | 1.65%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 373       | 1.61%   |
| Intel Core Processor Integrated Graphics Controller                                      | 372       | 1.6%    |
| Intel HD Graphics 620                                                                    | 361       | 1.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 339       | 1.46%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 331       | 1.43%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 328       | 1.41%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 326       | 1.4%    |
| Intel HD Graphics 530                                                                    | 319       | 1.37%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 275       | 1.18%   |
| Intel HD Graphics 5500                                                                   | 273       | 1.18%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 271       | 1.17%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 266       | 1.15%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 265       | 1.14%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 245       | 1.05%   |
| AMD Lucienne                                                                             | 228       | 0.98%   |
| Intel HD Graphics 630                                                                    | 223       | 0.96%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 213       | 0.92%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 187       | 0.81%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 185       | 0.8%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 171       | 0.74%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 167       | 0.72%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 157       | 0.68%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 145       | 0.62%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 135       | 0.58%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 135       | 0.58%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 135       | 0.58%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 131       | 0.56%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 124       | 0.53%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 124       | 0.53%   |
| Intel HD Graphics 500                                                                    | 120       | 0.52%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 117       | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| 1 x Intel                         | 7866      | 39.36%  |
| 1 x AMD                           | 4840      | 24.22%  |
| 1 x Nvidia                        | 3746      | 18.74%  |
| Intel + Nvidia                    | 1990      | 9.96%   |
| Intel + AMD                       | 420       | 2.1%    |
| Other                             | 283       | 1.42%   |
| 2 x AMD                           | 259       | 1.3%    |
| AMD + Nvidia                      | 227       | 1.14%   |
| 1 x Matrox                        | 80        | 0.4%    |
| 2 x Nvidia                        | 78        | 0.39%   |
| 1 x ASPEED                        | 73        | 0.37%   |
| 2 x Intel                         | 31        | 0.16%   |
| 1 x SiS                           | 18        | 0.09%   |
| 1 x VIA                           | 16        | 0.08%   |
| Nvidia + ASPEED                   | 14        | 0.07%   |
| 1 x S3 Graphics                   | 8         | 0.04%   |
| Nvidia + Matrox                   | 7         | 0.04%   |
| AMD + ASPEED                      | 7         | 0.04%   |
| AMD + Matrox                      | 4         | 0.02%   |
| Nvidia + XGI                      | 2         | 0.01%   |
| Intel + 2 x Nvidia                | 2         | 0.01%   |
| Intel + AMD + 1 x Nvidia          | 2         | 0.01%   |
| 5 x AMD                           | 1         | 0.01%   |
| 4 x Nvidia                        | 1         | 0.01%   |
| 2 x Nvidia + 1 x ASPEED           | 1         | 0.01%   |
| 2 x Intel + 1 x Nvidia            | 1         | 0.01%   |
| 2 x AMD + 1 x Nvidia + 1 x ASPEED | 1         | 0.01%   |
| 1 x Silicon Motion                | 1         | 0.01%   |
| Nvidia + Dome Imaging Systems     | 1         | 0.01%   |
| 1 x Neomagic                      | 1         | 0.01%   |
| 1 x Intel + 4 x AMD               | 1         | 0.01%   |
| 1 x Huawei Technologies           | 1         | 0.01%   |
| AMD + XGI                         | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 15980     | 79.2%   |
| Proprietary | 3124      | 15.48%  |
| Unknown     | 1074      | 5.32%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 11123     | 54.12%  |
| 1.01-2.0       | 2476      | 12.05%  |
| 0.01-0.5       | 2400      | 11.68%  |
| 0.51-1.0       | 1640      | 7.98%   |
| 3.01-4.0       | 1241      | 6.04%   |
| 7.01-8.0       | 896       | 4.36%   |
| 5.01-6.0       | 375       | 1.82%   |
| 8.01-16.0      | 250       | 1.22%   |
| 2.01-3.0       | 111       | 0.54%   |
| 16.01-24.0     | 30        | 0.15%   |
| 4.01-5.0       | 10        | 0.05%   |
| More than 64.0 | 1         | 0.005%  |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 2685      | 12.58%  |
| AU Optronics            | 2415      | 11.32%  |
| LG Display              | 1903      | 8.92%   |
| Chimei Innolux          | 1463      | 6.86%   |
| BOE                     | 1307      | 6.12%   |
| Goldstar                | 1037      | 4.86%   |
| Dell                    | 1032      | 4.84%   |
| Acer                    | 853       | 4%      |
| BenQ                    | 770       | 3.61%   |
| Hewlett-Packard         | 551       | 2.58%   |
| Ancor Communications    | 550       | 2.58%   |
| Lenovo                  | 531       | 2.49%   |
| AOC                     | 437       | 2.05%   |
| Philips                 | 424       | 1.99%   |
| Iiyama                  | 344       | 1.61%   |
| Apple                   | 339       | 1.59%   |
| Sharp                   | 336       | 1.57%   |
| Fujitsu Siemens         | 335       | 1.57%   |
| Chi Mei Optoelectronics | 305       | 1.43%   |
| Eizo                    | 293       | 1.37%   |
| Medion                  | 210       | 0.98%   |
| PANDA                   | 164       | 0.77%   |
| ASUSTek Computer        | 151       | 0.71%   |
| Sony                    | 149       | 0.7%    |
| InfoVision              | 139       | 0.65%   |
| HannStar                | 135       | 0.63%   |
| LG Philips              | 132       | 0.62%   |
| Unknown                 | 129       | 0.6%    |
| LG Electronics          | 123       | 0.58%   |
| ViewSonic               | 122       | 0.57%   |
| NEC Computers           | 119       | 0.56%   |
| Panasonic               | 115       | 0.54%   |
| Vestel Elektronik       | 82        | 0.38%   |
| CSO                     | 81        | 0.38%   |
| Belinea                 | 71        | 0.33%   |
| Compal                  | 69        | 0.32%   |
| Toshiba                 | 65        | 0.3%    |
| Valve                   | 63        | 0.3%    |
| CPT                     | 58        | 0.27%   |
| Grundig                 | 53        | 0.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch             | 84        | 0.38%   |
| Vestel Elektronik 40W_LCD_TV VES3700 1920x540                             | 82        | 0.37%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 76        | 0.34%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 74        | 0.33%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 67        | 0.3%    |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch      | 62        | 0.28%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                        | 60        | 0.27%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 59        | 0.27%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x194mm 15.5-inch                   | 58        | 0.26%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                       | 56        | 0.25%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch              | 56        | 0.25%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch         | 53        | 0.24%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                     | 53        | 0.24%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 51        | 0.23%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch               | 50        | 0.23%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 50        | 0.23%   |
| Grundig WXGA GRU4448 1600x1200                                            | 49        | 0.22%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch         | 48        | 0.22%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 48        | 0.22%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch          | 47        | 0.21%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch          | 47        | 0.21%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch          | 46        | 0.21%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch            | 45        | 0.2%    |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch               | 44        | 0.2%    |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 44        | 0.2%    |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                   | 43        | 0.19%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch           | 43        | 0.19%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch     | 43        | 0.19%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 42        | 0.19%   |
| BOE LCD Monitor BOE0660 1600x900 382x215mm 17.3-inch                      | 42        | 0.19%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 41        | 0.18%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch            | 41        | 0.18%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch         | 40        | 0.18%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 40        | 0.18%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch             | 40        | 0.18%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch             | 40        | 0.18%   |
| Panasonic TV MEIA296 3840x2160 1280x720mm 57.8-inch                       | 39        | 0.18%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 39        | 0.18%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                  | 37        | 0.17%   |
| AU Optronics LCD Monitor AUO219E 1600x900 382x214mm 17.2-inch             | 37        | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 8937      | 43.55%  |
| 1366x768 (WXGA)    | 2448      | 11.93%  |
| 3840x2160 (4K)     | 1458      | 7.11%   |
| 2560x1440 (QHD)    | 1142      | 5.57%   |
| 1600x900 (HD+)     | 1134      | 5.53%   |
| 1680x1050 (WSXGA+) | 842       | 4.1%    |
| 1280x1024 (SXGA)   | 800       | 3.9%    |
| 1920x1200 (WUXGA)  | 681       | 3.32%   |
| 1280x800 (WXGA)    | 519       | 2.53%   |
| 1440x900 (WXGA+)   | 392       | 1.91%   |
| Unknown            | 315       | 1.54%   |
| 3440x1440          | 252       | 1.23%   |
| 3840x1080          | 153       | 0.75%   |
| 2560x1600          | 134       | 0.65%   |
| 2560x1080          | 110       | 0.54%   |
| 2880x1800          | 86        | 0.42%   |
| 1024x600           | 81        | 0.39%   |
| 1600x1200          | 79        | 0.39%   |
| 1920x540           | 76        | 0.37%   |
| 800x1280           | 75        | 0.37%   |
| 1024x768 (XGA)     | 67        | 0.33%   |
| 1360x768           | 65        | 0.32%   |
| 3840x2400          | 54        | 0.26%   |
| 2160x1440          | 52        | 0.25%   |
| 3200x1800 (QHD+)   | 35        | 0.17%   |
| 2736x1824          | 34        | 0.17%   |
| 3840x1600          | 33        | 0.16%   |
| 1920x1280          | 30        | 0.15%   |
| 3840x1200          | 25        | 0.12%   |
| 2256x1504          | 25        | 0.12%   |
| 1280x720 (HD)      | 22        | 0.11%   |
| 4480x1440          | 21        | 0.1%    |
| 1680x945           | 21        | 0.1%    |
| 3000x2000          | 19        | 0.09%   |
| 1400x1050          | 18        | 0.09%   |
| 5760x2160          | 16        | 0.08%   |
| 2288x1287          | 16        | 0.08%   |
| 2048x1152          | 16        | 0.08%   |
| 3200x1080          | 13        | 0.06%   |
| 5760x1080          | 11        | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 4428      | 20.85%  |
| 27      | 1962      | 9.24%   |
| 24      | 1943      | 9.15%   |
| 17      | 1691      | 7.96%   |
| 13      | 1599      | 7.53%   |
| 14      | 1425      | 6.71%   |
| 23      | 1317      | 6.2%    |
| Unknown | 1235      | 5.82%   |
| 21      | 881       | 4.15%   |
| 19      | 662       | 3.12%   |
| 22      | 594       | 2.8%    |
| 12      | 462       | 2.18%   |
| 31      | 419       | 1.97%   |
| 34      | 278       | 1.31%   |
| 84      | 231       | 1.09%   |
| 11      | 228       | 1.07%   |
| 20      | 199       | 0.94%   |
| 18      | 177       | 0.83%   |
| 16      | 159       | 0.75%   |
| 10      | 127       | 0.6%    |
| 54      | 126       | 0.59%   |
| 40      | 121       | 0.57%   |
| 72      | 118       | 0.56%   |
| 32      | 106       | 0.5%    |
| 25      | 106       | 0.5%    |
| 7       | 61        | 0.29%   |
| 28      | 59        | 0.28%   |
| 26      | 54        | 0.25%   |
| 65      | 46        | 0.22%   |
| 48      | 39        | 0.18%   |
| 37      | 37        | 0.17%   |
| 33      | 36        | 0.17%   |
| 52      | 31        | 0.15%   |
| 35      | 28        | 0.13%   |
| 36      | 25        | 0.12%   |
| 42      | 23        | 0.11%   |
| 3       | 23        | 0.11%   |
| 55      | 19        | 0.09%   |
| 49      | 19        | 0.09%   |
| 29      | 16        | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 6695      | 32.09%  |
| 501-600        | 4810      | 23.05%  |
| 351-400        | 2194      | 10.52%  |
| 401-500        | 1988      | 9.53%   |
| 201-300        | 1764      | 8.45%   |
| Unknown        | 1235      | 5.92%   |
| 601-700        | 705       | 3.38%   |
| 701-800        | 445       | 2.13%   |
| 1501-2000      | 353       | 1.69%   |
| 1001-1500      | 330       | 1.58%   |
| 801-900        | 203       | 0.97%   |
| 1-100          | 75        | 0.36%   |
| 901-1000       | 38        | 0.18%   |
| 101-200        | 16        | 0.08%   |
| More than 2000 | 14        | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 13763     | 71.1%   |
| 16/10   | 2706      | 13.98%  |
| Unknown | 1067      | 5.51%   |
| 5/4     | 734       | 3.79%   |
| 21/9    | 361       | 1.86%   |
| 3/2     | 285       | 1.47%   |
| 4/3     | 201       | 1.04%   |
| 6/5     | 77        | 0.4%    |
| 32/9    | 67        | 0.35%   |
| 0.67    | 56        | 0.29%   |
| 1.00    | 16        | 0.08%   |
| 0.56    | 5         | 0.03%   |
| 3.73    | 4         | 0.02%   |
| 3.20    | 4         | 0.02%   |
| 0.62    | 3         | 0.02%   |
| 3.40    | 1         | 0.01%   |
| 1.96    | 1         | 0.01%   |
| 0.89    | 1         | 0.01%   |
| 0.75    | 1         | 0.01%   |
| 0.65    | 1         | 0.01%   |
| 0.63    | 1         | 0.01%   |
| 0.45    | 1         | 0.01%   |
| 0.25    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 4420      | 21%     |
| 201-250        | 3652      | 17.35%  |
| 81-90          | 2237      | 10.63%  |
| 301-350        | 2007      | 9.54%   |
| 121-130        | 1264      | 6.01%   |
| Unknown        | 1235      | 5.87%   |
| 151-200        | 1117      | 5.31%   |
| 351-500        | 926       | 4.4%    |
| 251-300        | 838       | 3.98%   |
| 71-80          | 788       | 3.74%   |
| More than 1000 | 624       | 2.96%   |
| 61-70          | 433       | 2.06%   |
| 141-150        | 351       | 1.67%   |
| 501-1000       | 298       | 1.42%   |
| 131-140        | 241       | 1.15%   |
| 51-60          | 235       | 1.12%   |
| 41-50          | 120       | 0.57%   |
| 111-120        | 120       | 0.57%   |
| 1-40           | 91        | 0.43%   |
| 91-100         | 49        | 0.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 7125      | 34.88%  |
| 121-160       | 5213      | 25.52%  |
| 101-120       | 4693      | 22.98%  |
| 161-240       | 1345      | 6.59%   |
| Unknown       | 1235      | 6.05%   |
| More than 240 | 442       | 2.16%   |
| 1-50          | 372       | 1.82%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 15814     | 77.76%  |
| 2     | 2956      | 14.54%  |
| 0     | 1117      | 5.49%   |
| 3     | 407       | 2%      |
| 4     | 40        | 0.2%    |
| 5     | 3         | 0.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 10052     | 34.43%  |
| Intel                             | 9999      | 34.25%  |
| Qualcomm Atheros                  | 2900      | 9.93%   |
| Broadcom                          | 1548      | 5.3%    |
| Marvell Technology Group          | 351       | 1.2%    |
| Broadcom Limited                  | 346       | 1.19%   |
| Nvidia                            | 311       | 1.07%   |
| MediaTek                          | 305       | 1.04%   |
| Ralink Technology                 | 250       | 0.86%   |
| Sierra Wireless                   | 241       | 0.83%   |
| TP-Link                           | 223       | 0.76%   |
| Ralink                            | 188       | 0.64%   |
| Ericsson Business Mobile Networks | 185       | 0.63%   |
| Dell                              | 173       | 0.59%   |
| ASIX Electronics                  | 170       | 0.58%   |
| Lenovo                            | 129       | 0.44%   |
| AVM                               | 127       | 0.43%   |
| Microsoft                         | 118       | 0.4%    |
| Samsung Electronics               | 93        | 0.32%   |
| DisplayLink                       | 89        | 0.3%    |
| Huawei Technologies               | 86        | 0.29%   |
| Edimax Technology                 | 86        | 0.29%   |
| Hewlett-Packard                   | 85        | 0.29%   |
| D-Link System                     | 73        | 0.25%   |
| IMC Networks                      | 63        | 0.22%   |
| Aquantia                          | 62        | 0.21%   |
| ASUSTek Computer                  | 60        | 0.21%   |
| Fibocom                           | 57        | 0.2%    |
| D-Link                            | 54        | 0.18%   |
| Qualcomm Atheros Communications   | 50        | 0.17%   |
| VIA Technologies                  | 42        | 0.14%   |
| NetGear                           | 40        | 0.14%   |
| JMicron Technology                | 36        | 0.12%   |
| Qualcomm                          | 34        | 0.12%   |
| Microchip Technology              | 32        | 0.11%   |
| Xiaomi                            | 30        | 0.1%    |
| Silicon Integrated Systems [SiS]  | 27        | 0.09%   |
| Belkin Components                 | 27        | 0.09%   |
| Mellanox Technologies             | 23        | 0.08%   |
| Sitecom Europe                    | 21        | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7298      | 21.03%  |
| Intel Wi-Fi 6 AX200                                               | 913       | 2.63%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 886       | 2.55%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 696       | 2.01%   |
| Intel Wireless 8265 / 8275                                        | 625       | 1.8%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 617       | 1.78%   |
| Intel I211 Gigabit Network Connection                             | 548       | 1.58%   |
| Intel Wireless 7260                                               | 441       | 1.27%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 439       | 1.27%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 434       | 1.25%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 432       | 1.24%   |
| Realtek RTL8125 2.5GbE Controller                                 | 430       | 1.24%   |
| Intel Wireless 8260                                               | 409       | 1.18%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 355       | 1.02%   |
| Intel Wireless 7265                                               | 352       | 1.01%   |
| Intel Wi-Fi 6 AX201                                               | 338       | 0.97%   |
| Intel Ethernet Connection (2) I219-V                              | 329       | 0.95%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 321       | 0.93%   |
| Intel Ethernet Connection I217-LM                                 | 300       | 0.86%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 284       | 0.82%   |
| Intel Wireless 3165                                               | 279       | 0.8%    |
| Intel Wireless-AC 9260                                            | 251       | 0.72%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 250       | 0.72%   |
| Intel 82579V Gigabit Network Connection                           | 239       | 0.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 235       | 0.68%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 226       | 0.65%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 224       | 0.65%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 220       | 0.63%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 210       | 0.61%   |
| Intel Ethernet Controller I225-V                                  | 205       | 0.59%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 204       | 0.59%   |
| Intel Wireless 3160                                               | 187       | 0.54%   |
| Intel Ethernet Connection I219-LM                                 | 182       | 0.52%   |
| Intel 82577LM Gigabit Network Connection                          | 180       | 0.52%   |
| Intel Centrino Ultimate-N 6300                                    | 178       | 0.51%   |
| Intel Ethernet Connection I217-V                                  | 173       | 0.5%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 169       | 0.49%   |
| Intel Ethernet Connection (2) I219-LM                             | 162       | 0.47%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 162       | 0.47%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 161       | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 7281      | 48.11%  |
| Realtek Semiconductor                 | 2355      | 15.56%  |
| Qualcomm Atheros                      | 2203      | 14.56%  |
| Broadcom                              | 921       | 6.09%   |
| MediaTek                              | 299       | 1.98%   |
| Ralink Technology                     | 250       | 1.65%   |
| Sierra Wireless                       | 241       | 1.59%   |
| TP-Link                               | 213       | 1.41%   |
| Ralink                                | 188       | 1.24%   |
| Broadcom Limited                      | 164       | 1.08%   |
| AVM                                   | 127       | 0.84%   |
| Microsoft                             | 109       | 0.72%   |
| Edimax Technology                     | 86        | 0.57%   |
| Dell                                  | 85        | 0.56%   |
| IMC Networks                          | 63        | 0.42%   |
| D-Link System                         | 60        | 0.4%    |
| ASUSTek Computer                      | 60        | 0.4%    |
| Fibocom                               | 57        | 0.38%   |
| Qualcomm Atheros Communications       | 50        | 0.33%   |
| D-Link                                | 49        | 0.32%   |
| Marvell Technology Group              | 42        | 0.28%   |
| NetGear                               | 39        | 0.26%   |
| Ericsson Business Mobile Networks     | 26        | 0.17%   |
| Qualcomm                              | 25        | 0.17%   |
| Belkin Components                     | 24        | 0.16%   |
| Sitecom Europe                        | 20        | 0.13%   |
| Hewlett-Packard                       | 17        | 0.11%   |
| ZyXEL Communications                  | 11        | 0.07%   |
| ZyDAS                                 | 10        | 0.07%   |
| Wacom                                 | 6         | 0.04%   |
| Linksys                               | 6         | 0.04%   |
| Philips (or NXP)                      | 4         | 0.03%   |
| Fujitsu Siemens Computers             | 4         | 0.03%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 4         | 0.03%   |
| Winbond Electronics                   | 3         | 0.02%   |
| Texas Instruments                     | 3         | 0.02%   |
| Quectel Wireless Solutions            | 3         | 0.02%   |
| Gemtek                                | 3         | 0.02%   |
| Tenda                                 | 2         | 0.01%   |
| Sweex                                 | 2         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 913       | 5.99%   |
| Intel Wireless 8265 / 8275                                              | 625       | 4.1%    |
| Intel Wireless 7260                                                     | 441       | 2.89%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 439       | 2.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 434       | 2.85%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 432       | 2.83%   |
| Intel Wireless 8260                                                     | 409       | 2.68%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 355       | 2.33%   |
| Intel Wireless 7265                                                     | 352       | 2.31%   |
| Intel Wi-Fi 6 AX201                                                     | 338       | 2.22%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 321       | 2.11%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 284       | 1.86%   |
| Intel Wireless 3165                                                     | 279       | 1.83%   |
| Intel Wireless-AC 9260                                                  | 251       | 1.65%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 250       | 1.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 226       | 1.48%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 224       | 1.47%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 220       | 1.44%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 210       | 1.38%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 204       | 1.34%   |
| Intel Wireless 3160                                                     | 187       | 1.23%   |
| Intel Centrino Ultimate-N 6300                                          | 178       | 1.17%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 169       | 1.11%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 162       | 1.06%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 161       | 1.06%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 158       | 1.04%   |
| Broadcom BCM43142 802.11b/g/n                                           | 156       | 1.02%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 152       | 1%      |
| Intel WiFi Link 5100                                                    | 152       | 1%      |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 148       | 0.97%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 140       | 0.92%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 139       | 0.91%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 138       | 0.91%   |
| Intel Centrino Advanced-N 6200                                          | 137       | 0.9%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 130       | 0.85%   |
| Intel Centrino Wireless-N 2230                                          | 128       | 0.84%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 120       | 0.79%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 118       | 0.77%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 115       | 0.75%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 112       | 0.73%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 9121      | 49.37%  |
| Intel                            | 5665      | 30.66%  |
| Qualcomm Atheros                 | 1029      | 5.57%   |
| Broadcom                         | 829       | 4.49%   |
| Nvidia                           | 311       | 1.68%   |
| Marvell Technology Group         | 309       | 1.67%   |
| Broadcom Limited                 | 189       | 1.02%   |
| ASIX Electronics                 | 170       | 0.92%   |
| Lenovo                           | 129       | 0.7%    |
| DisplayLink                      | 89        | 0.48%   |
| Samsung Electronics              | 86        | 0.47%   |
| Aquantia                         | 62        | 0.34%   |
| VIA Technologies                 | 41        | 0.22%   |
| Huawei Technologies              | 39        | 0.21%   |
| JMicron Technology               | 36        | 0.19%   |
| Xiaomi                           | 30        | 0.16%   |
| Microchip Technology             | 28        | 0.15%   |
| Hewlett-Packard                  | 28        | 0.15%   |
| Silicon Integrated Systems [SiS] | 25        | 0.14%   |
| Mellanox Technologies            | 20        | 0.11%   |
| 3Com                             | 18        | 0.1%    |
| Google                           | 17        | 0.09%   |
| Apple                            | 16        | 0.09%   |
| American Megatrends              | 14        | 0.08%   |
| D-Link System                    | 13        | 0.07%   |
| Attansic Technology              | 11        | 0.06%   |
| TP-Link                          | 10        | 0.05%   |
| Qualcomm                         | 9         | 0.05%   |
| Microsoft                        | 9         | 0.05%   |
| Standard Microsystems            | 8         | 0.04%   |
| ICS Advent                       | 7         | 0.04%   |
| OPPO Electronics                 | 6         | 0.03%   |
| HMD Global                       | 6         | 0.03%   |
| Emulex                           | 6         | 0.03%   |
| ZTE WCDMA Technologies MSM       | 5         | 0.03%   |
| MediaTek                         | 5         | 0.03%   |
| D-Link                           | 5         | 0.03%   |
| ADMtek                           | 5         | 0.03%   |
| OnePlus Technology (Shenzhen)    | 4         | 0.02%   |
| MosChip Semiconductor            | 4         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7298      | 38.6%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 886       | 4.69%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 696       | 3.68%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 617       | 3.26%   |
| Intel I211 Gigabit Network Connection                             | 548       | 2.9%    |
| Realtek RTL8125 2.5GbE Controller                                 | 430       | 2.27%   |
| Intel Ethernet Connection (2) I219-V                              | 329       | 1.74%   |
| Intel Ethernet Connection I217-LM                                 | 300       | 1.59%   |
| Intel 82579V Gigabit Network Connection                           | 239       | 1.26%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 235       | 1.24%   |
| Intel Ethernet Controller I225-V                                  | 205       | 1.08%   |
| Intel Ethernet Connection I219-LM                                 | 182       | 0.96%   |
| Intel 82577LM Gigabit Network Connection                          | 180       | 0.95%   |
| Intel Ethernet Connection I217-V                                  | 173       | 0.92%   |
| Intel Ethernet Connection (2) I219-LM                             | 162       | 0.86%   |
| Intel I210 Gigabit Network Connection                             | 157       | 0.83%   |
| Intel Ethernet Connection (4) I219-V                              | 152       | 0.8%    |
| Intel Ethernet Connection (4) I219-LM                             | 147       | 0.78%   |
| Intel Ethernet Connection (7) I219-V                              | 146       | 0.77%   |
| Intel 82567LM Gigabit Network Connection                          | 135       | 0.71%   |
| ASIX AX88179 Gigabit Ethernet                                     | 134       | 0.71%   |
| Intel Ethernet Connection I218-LM                                 | 133       | 0.7%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 121       | 0.64%   |
| Intel Ethernet Connection (6) I219-V                              | 121       | 0.64%   |
| Intel Ethernet Connection (3) I218-LM                             | 120       | 0.63%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 109       | 0.58%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 106       | 0.56%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 105       | 0.56%   |
| Nvidia MCP61 Ethernet                                             | 105       | 0.56%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 105       | 0.56%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 96        | 0.51%   |
| Intel Ethernet Connection (7) I219-LM                             | 94        | 0.5%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 91        | 0.48%   |
| Intel Ethernet Connection (2) I218-V                              | 91        | 0.48%   |
| Intel 82574L Gigabit Network Connection                           | 87        | 0.46%   |
| Intel Ethernet Connection I219-V                                  | 86        | 0.45%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 80        | 0.42%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 80        | 0.42%   |
| Intel Ethernet Connection (10) I219-V                             | 78        | 0.41%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 74        | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 17425     | 54.31%  |
| WiFi     | 14119     | 44%     |
| Modem    | 500       | 1.56%   |
| Unknown  | 43        | 0.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 10365     | 50.22%  |
| Ethernet | 10268     | 49.75%  |
| Unknown  | 5         | 0.02%   |
| Modem    | 1         | 0.005%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 10496     | 52.76%  |
| 1     | 8398      | 42.22%  |
| 0     | 458       | 2.3%    |
| 3     | 409       | 2.06%   |
| 4     | 78        | 0.39%   |
| 5     | 23        | 0.12%   |
| 6     | 14        | 0.07%   |
| 8     | 7         | 0.04%   |
| 7     | 3         | 0.02%   |
| 18    | 2         | 0.01%   |
| 10    | 2         | 0.01%   |
| 12    | 1         | 0.01%   |
| 9     | 1         | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 13109     | 63.91%  |
| Yes  | 7403      | 36.09%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 5375      | 48.13%  |
| Realtek Semiconductor           | 1153      | 10.32%  |
| Cambridge Silicon Radio         | 804       | 7.2%    |
| Broadcom                        | 671       | 6.01%   |
| Qualcomm Atheros Communications | 526       | 4.71%   |
| Foxconn / Hon Hai               | 415       | 3.72%   |
| Lite-On Technology              | 406       | 3.64%   |
| IMC Networks                    | 399       | 3.57%   |
| Apple                           | 349       | 3.13%   |
| Dell                            | 193       | 1.73%   |
| ASUSTek Computer                | 187       | 1.67%   |
| Hewlett-Packard                 | 101       | 0.9%    |
| Toshiba                         | 75        | 0.67%   |
| MediaTek                        | 70        | 0.63%   |
| Realtek                         | 64        | 0.57%   |
| Foxconn International           | 45        | 0.4%    |
| Marvell Semiconductor           | 39        | 0.35%   |
| Alps Electric                   | 32        | 0.29%   |
| Askey Computer                  | 31        | 0.28%   |
| Ralink                          | 25        | 0.22%   |
| Integrated System Solution      | 25        | 0.22%   |
| TP-Link                         | 24        | 0.21%   |
| Belkin Components               | 24        | 0.21%   |
| Edimax Technology               | 20        | 0.18%   |
| Taiyo Yuden                     | 18        | 0.16%   |
| Chicony Electronics             | 13        | 0.12%   |
| Qcom                            | 12        | 0.11%   |
| USI                             | 11        | 0.1%    |
| Ralink Technology               | 9         | 0.08%   |
| Logitech                        | 8         | 0.07%   |
| HTC (High Tech Computer)        | 7         | 0.06%   |
| Fujitsu                         | 7         | 0.06%   |
| Unknown                         | 5         | 0.04%   |
| Micro Star International        | 4         | 0.04%   |
| SINO WEALTH                     | 2         | 0.02%   |
| Motorola PCS                    | 2         | 0.02%   |
| ISSC                            | 2         | 0.02%   |
| Fujitsu Siemens Computers       | 2         | 0.02%   |
| Conwise Technology              | 2         | 0.02%   |
| AVM                             | 2         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 2144      | 19.18%  |
| Intel AX200 Bluetooth                               | 858       | 7.68%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 803       | 7.19%   |
| Realtek Bluetooth Radio                             | 789       | 7.06%   |
| Intel AX201 Bluetooth                               | 781       | 6.99%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 611       | 5.47%   |
| Intel Bluetooth Device                              | 357       | 3.19%   |
| Realtek  Bluetooth 4.2 Adapter                      | 292       | 2.61%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 236       | 2.11%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 203       | 1.82%   |
| Qualcomm Atheros  Bluetooth Device                  | 192       | 1.72%   |
| IMC Networks Bluetooth Radio                        | 192       | 1.72%   |
| Apple Bluetooth Host Controller                     | 157       | 1.4%    |
| Broadcom BCM2045B (BDC-2.1)                         | 142       | 1.27%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 129       | 1.15%   |
| Lite-On Bluetooth Device                            | 125       | 1.12%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 123       | 1.1%    |
| Intel AX210 Bluetooth                               | 123       | 1.1%    |
| Foxconn / Hon Hai Bluetooth Device                  | 117       | 1.05%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 109       | 0.98%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 95        | 0.85%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 87        | 0.78%   |
| IMC Networks Bluetooth Device                       | 87        | 0.78%   |
| Apple Bluetooth USB Host Controller                 | 82        | 0.73%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 81        | 0.72%   |
| Dell DW375 Bluetooth Module                         | 79        | 0.71%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 79        | 0.71%   |
| Lite-On Atheros AR3012 Bluetooth                    | 75        | 0.67%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 72        | 0.64%   |
| MediaTek Wireless_Device                            | 68        | 0.61%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 66        | 0.59%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 65        | 0.58%   |
| HP Broadcom 2070 Bluetooth Combo                    | 61        | 0.55%   |
| Realtek 802.11ac WLAN Adapter                       | 60        | 0.54%   |
| Foxconn / Hon Hai BCM20702A0                        | 58        | 0.52%   |
| IMC Networks Wireless_Device                        | 54        | 0.48%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 49        | 0.44%   |
| Broadcom BCM2045 Bluetooth                          | 49        | 0.44%   |
| Dell BCM20702A0 Bluetooth Module                    | 48        | 0.43%   |
| Foxconn International BCM43142A0 Bluetooth module   | 45        | 0.4%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 13259     | 48.49%  |
| AMD                              | 6368      | 23.29%  |
| Nvidia                           | 4481      | 16.39%  |
| C-Media Electronics              | 520       | 1.9%    |
| Logitech                         | 231       | 0.84%   |
| Creative Labs                    | 222       | 0.81%   |
| GN Netcom                        | 178       | 0.65%   |
| Lenovo                           | 142       | 0.52%   |
| Texas Instruments                | 131       | 0.48%   |
| Realtek Semiconductor            | 112       | 0.41%   |
| JMTek                            | 88        | 0.32%   |
| Focusrite-Novation               | 86        | 0.31%   |
| Plantronics                      | 84        | 0.31%   |
| Creative Technology              | 79        | 0.29%   |
| Kingston Technology              | 77        | 0.28%   |
| VIA Technologies                 | 71        | 0.26%   |
| Razer USA                        | 63        | 0.23%   |
| ASUSTek Computer                 | 55        | 0.2%    |
| Generalplus Technology           | 53        | 0.19%   |
| Sennheiser Communications        | 48        | 0.18%   |
| Yamaha                           | 41        | 0.15%   |
| SteelSeries ApS                  | 41        | 0.15%   |
| Hewlett-Packard                  | 38        | 0.14%   |
| Corsair                          | 38        | 0.14%   |
| RODE Microphones                 | 37        | 0.14%   |
| Silicon Integrated Systems [SiS] | 34        | 0.12%   |
| BEHRINGER International          | 31        | 0.11%   |
| Samson Technologies              | 27        | 0.1%    |
| DSEA A/S                         | 27        | 0.1%    |
| TerraTec Electronic              | 26        | 0.1%    |
| Dell                             | 25        | 0.09%   |
| Micro Star International         | 21        | 0.08%   |
| Native Instruments               | 19        | 0.07%   |
| Blue Microphones                 | 19        | 0.07%   |
| M-Audio                          | 18        | 0.07%   |
| GYROCOM C&C                      | 18        | 0.07%   |
| Conexant Systems                 | 16        | 0.06%   |
| Apple                            | 16        | 0.06%   |
| ROCCAT                           | 15        | 0.05%   |
| Sony                             | 13        | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 1777      | 5.42%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 1408      | 4.3%    |
| Intel Sunrise Point-LP HD Audio                                            | 1378      | 4.21%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 1245      | 3.8%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 1016      | 3.1%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 970       | 2.96%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 930       | 2.84%   |
| AMD Starship/Matisse HD Audio Controller                                   | 803       | 2.45%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 762       | 2.33%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 717       | 2.19%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 696       | 2.12%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 618       | 1.89%   |
| AMD FCH Azalia Controller                                                  | 572       | 1.75%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 567       | 1.73%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 563       | 1.72%   |
| Intel Cannon Lake PCH cAVS                                                 | 553       | 1.69%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 472       | 1.44%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 460       | 1.4%    |
| Intel Haswell-ULT HD Audio Controller                                      | 447       | 1.36%   |
| Intel 8 Series HD Audio Controller                                         | 445       | 1.36%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 385       | 1.18%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 377       | 1.15%   |
| Nvidia GP107GL High Definition Audio Controller                            | 355       | 1.08%   |
| Intel Broadwell-U Audio Controller                                         | 349       | 1.07%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 341       | 1.04%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 324       | 0.99%   |
| Intel 200 Series PCH HD Audio                                              | 322       | 0.98%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 311       | 0.95%   |
| Nvidia GF108 High Definition Audio Controller                              | 298       | 0.91%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 294       | 0.9%    |
| Intel Comet Lake PCH-LP cAVS                                               | 291       | 0.89%   |
| AMD Kabini HDMI/DP Audio                                                   | 247       | 0.75%   |
| Nvidia GP106 High Definition Audio Controller                              | 246       | 0.75%   |
| Nvidia High Definition Audio Controller                                    | 241       | 0.74%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 233       | 0.71%   |
| Nvidia GP104 High Definition Audio Controller                              | 232       | 0.71%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 220       | 0.67%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 212       | 0.65%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 211       | 0.64%   |
| Nvidia TU106 High Definition Audio Controller                              | 192       | 0.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 2741      | 23.82%  |
| SK hynix            | 1928      | 16.76%  |
| Unknown             | 1167      | 10.14%  |
| Kingston            | 1069      | 9.29%   |
| Micron Technology   | 1062      | 9.23%   |
| Crucial             | 848       | 7.37%   |
| G.Skill             | 695       | 6.04%   |
| Corsair             | 623       | 5.42%   |
| Ramaxel Technology  | 213       | 1.85%   |
| A-DATA Technology   | 165       | 1.43%   |
| Elpida              | 163       | 1.42%   |
| Nanya Technology    | 150       | 1.3%    |
| Unknown (ABCD)      | 149       | 1.3%    |
| Unknown             | 66        | 0.57%   |
| Team                | 61        | 0.53%   |
| Transcend           | 49        | 0.43%   |
| Patriot             | 33        | 0.29%   |
| GOODRAM             | 24        | 0.21%   |
| Avant               | 19        | 0.17%   |
| ASint Technology    | 19        | 0.17%   |
| Toshiba             | 17        | 0.15%   |
| GeIL                | 16        | 0.14%   |
| 48spaces            | 14        | 0.12%   |
| CSX                 | 12        | 0.1%    |
| Unifosa             | 11        | 0.1%    |
| Qimonda             | 8         | 0.07%   |
| PNY                 | 8         | 0.07%   |
| Lexar               | 8         | 0.07%   |
| Hewlett-Packard     | 8         | 0.07%   |
| Apacer              | 7         | 0.06%   |
| Timetec             | 6         | 0.05%   |
| SHARETRONIC         | 6         | 0.05%   |
| Mushkin             | 6         | 0.05%   |
| Aeneon              | 5         | 0.04%   |
| Unknown (AB)        | 4         | 0.03%   |
| Patriot Memory      | 4         | 0.03%   |
| Swissbit            | 3         | 0.03%   |
| Silicon Power       | 3         | 0.03%   |
| Neo Forza           | 3         | 0.03%   |
| Innodisk            | 3         | 0.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 105       | 0.85%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 97        | 0.78%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 96        | 0.78%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 93        | 0.75%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 88        | 0.71%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 85        | 0.69%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s              | 83        | 0.67%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 79        | 0.64%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 76        | 0.61%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 75        | 0.61%   |
| Unknown                                                          | 66        | 0.53%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 61        | 0.49%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 61        | 0.49%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 59        | 0.48%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 59        | 0.48%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 58        | 0.47%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 56        | 0.45%   |
| G.Skill RAM F4-3200C16-8GVKB 8192MB DIMM DDR4 3866MT/s           | 56        | 0.45%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 53        | 0.43%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 52        | 0.42%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 51        | 0.41%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 50        | 0.4%    |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 50        | 0.4%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 49        | 0.4%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 49        | 0.4%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 48        | 0.39%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 48        | 0.39%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 47        | 0.38%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s               | 46        | 0.37%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 44        | 0.36%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 44        | 0.36%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 44        | 0.36%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 42        | 0.34%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 42        | 0.34%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 42        | 0.34%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 41        | 0.33%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 41        | 0.33%   |
| G.Skill RAM F4-3200C16-16GVK 16384MB DIMM DDR4 3600MT/s          | 41        | 0.33%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 39        | 0.32%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 39        | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind            | Computers | Percent |
|-----------------|-----------|---------|
| DDR4            | 4799      | 47.21%  |
| DDR3            | 3359      | 33.04%  |
| DDR2            | 458       | 4.51%   |
| LPDDR4          | 419       | 4.12%   |
| Unknown         | 332       | 3.27%   |
| SDRAM           | 280       | 2.75%   |
| LPDDR3          | 236       | 2.32%   |
| DDR5            | 102       | 1%      |
| LPDDR5          | 75        | 0.74%   |
| DDR             | 69        | 0.68%   |
| DRAM            | 34        | 0.33%   |
| Logical non-vol | 1         | 0.01%   |
| EEPROM          | 1         | 0.01%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| SODIMM          | 5626      | 55.51%  |
| DIMM            | 3726      | 36.76%  |
| Row Of Chips    | 671       | 6.62%   |
| Chip            | 79        | 0.78%   |
| Unknown         | 14        | 0.14%   |
| FB-DIMM         | 10        | 0.1%    |
| RIMM            | 9         | 0.09%   |
| Proprietary Car | 1         | 0.01%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size   | Computers | Percent |
|--------|-----------|---------|
| 8192   | 4301      | 39.35%  |
| 4096   | 2821      | 25.81%  |
| 16384  | 1700      | 15.55%  |
| 2048   | 1318      | 12.06%  |
| 32768  | 398       | 3.64%   |
| 1024   | 332       | 3.04%   |
| 512    | 44        | 0.4%    |
| 256    | 5         | 0.05%   |
| 65536  | 4         | 0.04%   |
| 128    | 4         | 0.04%   |
| 129408 | 1         | 0.01%   |
| 384    | 1         | 0.01%   |
| 16     | 1         | 0.01%   |
| 1      | 1         | 0.01%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 2115      | 19.31%  |
| 3200    | 1656      | 15.12%  |
| 2667    | 1503      | 13.72%  |
| 1333    | 811       | 7.41%   |
| 2400    | 784       | 7.16%   |
| 2133    | 538       | 4.91%   |
| 1334    | 351       | 3.21%   |
| 3600    | 286       | 2.61%   |
| 800     | 247       | 2.26%   |
| 667     | 247       | 2.26%   |
| Unknown | 229       | 2.09%   |
| 1867    | 196       | 1.79%   |
| 4267    | 164       | 1.5%    |
| 1067    | 162       | 1.48%   |
| 3266    | 115       | 1.05%   |
| 1866    | 99        | 0.9%    |
| 1066    | 97        | 0.89%   |
| 1800    | 83        | 0.76%   |
| 3000    | 77        | 0.7%    |
| 2666    | 77        | 0.7%    |
| 2933    | 73        | 0.67%   |
| 6400    | 72        | 0.66%   |
| 4800    | 69        | 0.63%   |
| 3733    | 66        | 0.6%    |
| 4199    | 63        | 0.58%   |
| 3866    | 61        | 0.56%   |
| 3400    | 61        | 0.56%   |
| 3800    | 44        | 0.4%    |
| 2048    | 43        | 0.39%   |
| 4266    | 40        | 0.37%   |
| 8400    | 38        | 0.35%   |
| 533     | 38        | 0.35%   |
| 400     | 38        | 0.35%   |
| 3533    | 28        | 0.26%   |
| 975     | 28        | 0.26%   |
| 3666    | 24        | 0.22%   |
| 2800    | 22        | 0.2%    |
| 333     | 20        | 0.18%   |
| 4000    | 18        | 0.16%   |
| 3500    | 18        | 0.16%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Hewlett-Packard          | 225       | 29.34%  |
| Brother Industries       | 147       | 19.17%  |
| Canon                    | 140       | 18.25%  |
| Samsung Electronics      | 96        | 12.52%  |
| Seiko Epson              | 56        | 7.3%    |
| Kyocera                  | 22        | 2.87%   |
| Prolific Technology      | 18        | 2.35%   |
| Dymo-CoStar              | 17        | 2.22%   |
| Lexmark International    | 13        | 1.69%   |
| QinHeng Electronics      | 12        | 1.56%   |
| Dell                     | 4         | 0.52%   |
| Xerox                    | 3         | 0.39%   |
| Ricoh                    | 3         | 0.39%   |
| Oki Data                 | 2         | 0.26%   |
| Magic Control Technology | 2         | 0.26%   |
| STMicroelectronics       | 1         | 0.13%   |
| Seiko Instruments        | 1         | 0.13%   |
| Panasonic (Matsushita)   | 1         | 0.13%   |
| MIIIW                    | 1         | 0.13%   |
| ATEN International       | 1         | 0.13%   |
| Agere Systems (Lucent)   | 1         | 0.13%   |
| Unknown                  | 1         | 0.13%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port                         | 18        | 2.33%   |
| Samsung M2020 Series                                  | 17        | 2.2%    |
| Brother HL-2030 Laser Printer                         | 13        | 1.68%   |
| QinHeng CH340S                                        | 12        | 1.55%   |
| Canon PIXMA MX920 Series                              | 12        | 1.55%   |
| Canon CanoScan LiDE 300                               | 12        | 1.55%   |
| HP ENVY 4520 series                                   | 10        | 1.3%    |
| Canon LiDE 400                                        | 10        | 1.3%    |
| Samsung C48x Series Color Laser Multifunction Printer | 9         | 1.17%   |
| Canon iP7200 series                                   | 9         | 1.17%   |
| Canon PIXMA MG3600 Series                             | 8         | 1.04%   |
| HP Deskjet 2540 series                                | 7         | 0.91%   |
| Canon TR8500 series                                   | 7         | 0.91%   |
| Brother MFC-L2710DW series                            | 7         | 0.91%   |
| Seiko Epson XP-2100 Series                            | 6         | 0.78%   |
| Seiko Epson ET-2710 Series                            | 6         | 0.78%   |
| Samsung M2070 Series                                  | 6         | 0.78%   |
| HP OfficeJet 3830 series                              | 6         | 0.78%   |
| HP ENVY 4500 series                                   | 6         | 0.78%   |
| HP DeskJet 2700 series                                | 6         | 0.78%   |
| Brother HL-3142CW series                              | 6         | 0.78%   |
| Samsung SCX-472x Series                               | 5         | 0.65%   |
| Samsung ML-1640 Series Laser Printer                  | 5         | 0.65%   |
| HP Officejet 4620 series                              | 5         | 0.65%   |
| HP DeskJet F4200 series                               | 5         | 0.65%   |
| HP DeskJet 3700 series                                | 5         | 0.65%   |
| HP Deskjet 3520 series                                | 5         | 0.65%   |
| HP DeskJet 2600 series                                | 5         | 0.65%   |
| HP DeskJet 1110 series                                | 5         | 0.65%   |
| Dymo-CoStar LabelWriter 450                           | 5         | 0.65%   |
| Dymo-CoStar LabelWriter 400                           | 5         | 0.65%   |
| Canon TS700 series                                    | 5         | 0.65%   |
| Canon Pixma iP4500 Printer                            | 5         | 0.65%   |
| Brother MFC-L3750CDW                                  | 5         | 0.65%   |
| Samsung M283x Series                                  | 4         | 0.52%   |
| Kyocera Mita FS-820                                   | 4         | 0.52%   |
| HP Officejet Pro 8100                                 | 4         | 0.52%   |
| HP OfficeJet 5200 series                              | 4         | 0.52%   |
| HP OfficeJet 4650 series                              | 4         | 0.52%   |
| HP Officejet 2620 series                              | 4         | 0.52%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                                         | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Canon                                          | 189       | 71.86%  |
| Seiko Epson                                    | 42        | 15.97%  |
| Hewlett-Packard                                | 14        | 5.32%   |
| AGFA-Gevaert NV                                | 8         | 3.04%   |
| Mustek Systems                                 | 6         | 2.28%   |
| Siemens Information and Communication Products | 1         | 0.38%   |
| Plustek                                        | 1         | 0.38%   |
| Nikon                                          | 1         | 0.38%   |
| Microtek International                         | 1         | 0.38%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                           | Computers | Percent |
|---------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 220                                                         | 28        | 10.61%  |
| Canon CanoScan LiDE 210                                                         | 25        | 9.47%   |
| Canon CanoScan LiDE 110                                                         | 21        | 7.95%   |
| Canon CanoScan N670U/N676U/LiDE 20                                              | 18        | 6.82%   |
| Canon CanoScan LIDE 25                                                          | 18        | 6.82%   |
| Canon CanoScan LiDE 120                                                         | 13        | 4.92%   |
| Canon CanoScan LiDE 100                                                         | 13        | 4.92%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]                             | 8         | 3.03%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                                          | 8         | 3.03%   |
| Canon CanoScan LiDE 90                                                          | 7         | 2.65%   |
| Canon CanoScan LiDE 200                                                         | 6         | 2.27%   |
| Seiko Epson GT-X770 [Perfection V500]                                           | 5         | 1.89%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                        | 5         | 1.89%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                                   | 5         | 1.89%   |
| Canon CanoScan LiDE 60                                                          | 5         | 1.89%   |
| Canon CanoScan 9000F Mark II                                                    | 4         | 1.52%   |
| Canon CanoScan 8800F                                                            | 4         | 1.52%   |
| AGFA-Gevaert NV SnapScan 1212U (?)                                              | 4         | 1.52%   |
| HP ScanJet 3970c                                                                | 3         | 1.14%   |
| Canon CanoScan N1240U/LiDE 30                                                   | 3         | 1.14%   |
| Canon CanoScan LiDE 600F                                                        | 3         | 1.14%   |
| Canon CanoScan LiDE 500F                                                        | 3         | 1.14%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                         | 2         | 0.76%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                              | 2         | 0.76%   |
| Seiko Epson GT-8200U/GT-8200UF [Perfection 1650/1650 PHOTO]                     | 2         | 0.76%   |
| Seiko Epson GT-6600U [Perfection 610]                                           | 2         | 0.76%   |
| Mustek Systems ScanExpress 1200 CU                                              | 2         | 0.76%   |
| HP HP4470C                                                                      | 2         | 0.76%   |
| Canon CanoScan LiDE 700F                                                        | 2         | 0.76%   |
| Canon CanoScan 3200F                                                            | 2         | 0.76%   |
| Siemens Information and Communication Products ID-Mouse with Fingerprint Reader | 1         | 0.38%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]                                     | 1         | 0.38%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo]                         | 1         | 0.38%   |
| Seiko Epson GT-F700 [Perfection V350]                                           | 1         | 0.38%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                               | 1         | 0.38%   |
| Seiko Epson GT-9700F [Perfection 2450 PHOTO]                                    | 1         | 0.38%   |
| Seiko Epson GT-9400UF [Perfection 3170]                                         | 1         | 0.38%   |
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO]                   | 1         | 0.38%   |
| Seiko Epson GT-7700U [Perfection 1240U]                                         | 1         | 0.38%   |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]                               | 1         | 0.38%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 2834      | 25.63%  |
| IMC Networks                           | 894       | 8.09%   |
| Microdia                               | 762       | 6.89%   |
| Logitech                               | 761       | 6.88%   |
| Bison Electronics                      | 705       | 6.38%   |
| Realtek Semiconductor                  | 692       | 6.26%   |
| Quanta                                 | 477       | 4.31%   |
| Sunplus Innovation Technology          | 474       | 4.29%   |
| Cheng Uei Precision Industry (Foxlink) | 377       | 3.41%   |
| Suyin                                  | 347       | 3.14%   |
| Apple                                  | 290       | 2.62%   |
| Lite-On Technology                     | 247       | 2.23%   |
| Syntek                                 | 245       | 2.22%   |
| Microsoft                              | 164       | 1.48%   |
| Alcor Micro                            | 160       | 1.45%   |
| Acer                                   | 159       | 1.44%   |
| Silicon Motion                         | 121       | 1.09%   |
| Luxvisions Innotech Limited            | 117       | 1.06%   |
| Ricoh                                  | 112       | 1.01%   |
| Lenovo                                 | 100       | 0.9%    |
| Samsung Electronics                    | 94        | 0.85%   |
| Z-Star Microelectronics                | 78        | 0.71%   |
| Generalplus Technology                 | 56        | 0.51%   |
| ALi                                    | 56        | 0.51%   |
| Creative Technology                    | 47        | 0.43%   |
| ARC International                      | 41        | 0.37%   |
| Sonix Technology                       | 37        | 0.33%   |
| Primax Electronics                     | 36        | 0.33%   |
| SunplusIT                              | 29        | 0.26%   |
| DigiTech                               | 29        | 0.26%   |
| Importek                               | 28        | 0.25%   |
| Sunplus Technology                     | 25        | 0.23%   |
| Cubeternet                             | 25        | 0.23%   |
| Trust                                  | 22        | 0.2%    |
| MacroSilicon                           | 19        | 0.17%   |
| Jieli Technology                       | 19        | 0.17%   |
| Genesys Logic                          | 18        | 0.16%   |
| GEMBIRD                                | 17        | 0.15%   |
| KYE Systems (Mouse Systems)            | 15        | 0.14%   |
| 2M UVC CAMERA                          | 13        | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 613       | 5.5%    |
| IMC Networks Integrated Camera                   | 330       | 2.96%   |
| Chicony HD Webcam                                | 269       | 2.41%   |
| Microdia Integrated_Webcam_HD                    | 224       | 2.01%   |
| Bison Integrated Camera                          | 203       | 1.82%   |
| Realtek Integrated_Webcam_HD                     | 177       | 1.59%   |
| IMC Networks USB2.0 HD UVC WebCam                | 171       | 1.53%   |
| Logitech Webcam C270                             | 156       | 1.4%    |
| Syntek Integrated Camera                         | 141       | 1.26%   |
| Logitech HD Pro Webcam C920                      | 141       | 1.26%   |
| Chicony USB2.0 Camera                            | 140       | 1.26%   |
| Chicony FJ Camera                                | 140       | 1.26%   |
| Lite-On Integrated Camera                        | 107       | 0.96%   |
| Chicony HP HD Camera                             | 97        | 0.87%   |
| Apple Built-in iSight                            | 94        | 0.84%   |
| Sunplus HD WebCam                                | 93        | 0.83%   |
| Samsung Galaxy series, misc. (MTP mode)          | 91        | 0.82%   |
| Chicony USB 2.0 Camera                           | 90        | 0.81%   |
| Microdia Integrated Webcam                       | 88        | 0.79%   |
| Quanta HD User Facing                            | 83        | 0.74%   |
| Chicony USB2.0 HD UVC WebCam                     | 79        | 0.71%   |
| Sunplus Integrated_Webcam_HD                     | 78        | 0.7%    |
| Chicony HD User Facing                           | 78        | 0.7%    |
| Bison SunplusIT Integrated Camera                | 77        | 0.69%   |
| Chicony Integrated Camera (1280x720@30)          | 72        | 0.65%   |
| Microsoft LifeCam HD-3000                        | 70        | 0.63%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 65        | 0.58%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 65        | 0.58%   |
| Quanta HP Webcam                                 | 64        | 0.57%   |
| Apple FaceTime HD Camera (Built-in)              | 64        | 0.57%   |
| Quanta HP HD Camera                              | 63        | 0.56%   |
| Bison BisonCam, NB Pro                           | 63        | 0.56%   |
| Chicony TOSHIBA Web Camera - HD                  | 61        | 0.55%   |
| Realtek USB Camera                               | 60        | 0.54%   |
| Chicony Integrated IR Camera                     | 60        | 0.54%   |
| Chicony HP Webcam                                | 60        | 0.54%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                  | 60        | 0.54%   |
| Chicony ThinkPad T490 Webcam                     | 56        | 0.5%    |
| Chicony Lenovo Integrated Camera (0.3MP)         | 56        | 0.5%    |
| Suyin Acer/HP Integrated Webcam [CN0314]         | 55        | 0.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 760       | 30.83%  |
| Synaptics                          | 708       | 28.72%  |
| Shenzhen Goodix Technology         | 313       | 12.7%   |
| AuthenTec                          | 207       | 8.4%    |
| Upek                               | 164       | 6.65%   |
| LighTuning Technology              | 139       | 5.64%   |
| Elan Microelectronics              | 104       | 4.22%   |
| STMicroelectronics                 | 40        | 1.62%   |
| HOLTEK                             | 11        | 0.45%   |
| Realtek USB2.0 Finger Print Bridge | 7         | 0.28%   |
| Samsung Electronics                | 6         | 0.24%   |
| Focal-systems.Corp                 | 2         | 0.08%   |
| DigitalPersona                     | 2         | 0.08%   |
| Next Biometrics                    | 1         | 0.04%   |
| Dell                               | 1         | 0.04%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 259       | 10.51%  |
| Shenzhen Goodix  Fingerprint Device                                        | 176       | 7.14%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 153       | 6.21%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 140       | 5.68%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 121       | 4.91%   |
| Validity Sensors Synaptics WBDI                                            | 107       | 4.34%   |
| Shenzhen Goodix Fingerprint Reader                                         | 95        | 3.85%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 87        | 3.53%   |
| AuthenTec AES2810                                                          | 72        | 2.92%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 69        | 2.8%    |
| Synaptics UWP WBDI                                                         | 60        | 2.43%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 60        | 2.43%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 55        | 2.23%   |
| Synaptics WBDI                                                             | 49        | 1.99%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 47        | 1.91%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 46        | 1.87%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 45        | 1.83%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 45        | 1.83%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 42        | 1.7%    |
| Shenzhen Goodix FingerPrint                                                | 42        | 1.7%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 41        | 1.66%   |
| STMicroelectronics Fingerprint Reader                                      | 40        | 1.62%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 36        | 1.46%   |
| Synaptics Fingerprint reader [HP G6]                                       | 36        | 1.46%   |
| Elan ELAN:Fingerprint                                                      | 35        | 1.42%   |
| Validity Sensors VFS491                                                    | 33        | 1.34%   |
| Synaptics  WBDI                                                            | 33        | 1.34%   |
| Elan ELAN:ARM-M4                                                           | 33        | 1.34%   |
| AuthenTec Fingerprint Sensor                                               | 33        | 1.34%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 32        | 1.3%    |
| AuthenTec AES1600                                                          | 32        | 1.3%    |
| LighTuning Fingerprint Reader                                              | 29        | 1.18%   |
| Elan WBF Fingerprint Sensor                                                | 26        | 1.05%   |
| Synaptics UWP WBDI Device                                                  | 23        | 0.93%   |
| Unknown                                                                    | 22        | 0.89%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 21        | 0.85%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 21        | 0.85%   |
| Validity Sensors Fingerprint scanner                                       | 19        | 0.77%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 18        | 0.73%   |
| Synaptics WBDI Device                                                      | 13        | 0.53%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 566       | 39.94%  |
| Broadcom                  | 411       | 29%     |
| O2 Micro                  | 121       | 8.54%   |
| Lenovo                    | 111       | 7.83%   |
| Upek                      | 79        | 5.58%   |
| Reiner SCT Kartensysteme  | 27        | 1.91%   |
| Gemalto (was Gemplus)     | 18        | 1.27%   |
| Yubico.com                | 15        | 1.06%   |
| OmniKey                   | 13        | 0.92%   |
| Clay Logic                | 12        | 0.85%   |
| Cherry                    | 10        | 0.71%   |
| SCM Microsystems          | 8         | 0.56%   |
| Fujitsu Siemens Computers | 5         | 0.35%   |
| Advanced Card Systems     | 5         | 0.35%   |
| Kobil Systems             | 4         | 0.28%   |
| Realtek Semiconductor     | 3         | 0.21%   |
| NXP Semiconductors        | 2         | 0.14%   |
| In Focus Systems          | 2         | 0.14%   |
| Chicony Electronics       | 2         | 0.14%   |
| Purism, SPC               | 1         | 0.07%   |
| Microchip Technology      | 1         | 0.07%   |
| Aladdin Knowledge Systems | 1         | 0.07%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 564       | 39.8%   |
| Broadcom BCM5880 Secure Applications Processor                               | 160       | 11.29%  |
| Lenovo Integrated Smart Card Reader                                          | 110       | 7.76%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 109       | 7.69%   |
| Broadcom 5880                                                                | 91        | 6.42%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 79        | 5.58%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 78        | 5.5%    |
| Broadcom 58200                                                               | 76        | 5.36%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 14        | 0.99%   |
| O2 Micro Oz776 SmartCard Reader                                              | 12        | 0.85%   |
| Clay Logic Nitrokey Pro                                                      | 12        | 0.85%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                          | 9         | 0.64%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 9         | 0.64%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 9         | 0.64%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 8         | 0.56%   |
| Reiner SCT Kartensysteme cyberJack one                                       | 7         | 0.49%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 6         | 0.42%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 6         | 0.42%   |
| OmniKey CardMan 3021 / 3121                                                  | 5         | 0.35%   |
| Reiner SCT Kartensysteme tanJack USB                                         | 4         | 0.28%   |
| SCM Microsystems SCR335 SmartCard Reader                                     | 3         | 0.21%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 3         | 0.21%   |
| OmniKey CardMan 4321                                                         | 3         | 0.21%   |
| OmniKey CardMan 3121 (HID Technologies)                                      | 3         | 0.21%   |
| Advanced Card Systems ACR122U                                                | 3         | 0.21%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 0.14%   |
| Reiner SCT Kartensysteme cyberJack e-com/pinpad                              | 2         | 0.14%   |
| NXP Semiconductors PR533                                                     | 2         | 0.14%   |
| Kobil Systems Smart Token                                                    | 2         | 0.14%   |
| Kobil Systems KOBIL Class 3 Reader                                           | 2         | 0.14%   |
| In Focus Systems EMV Smartcard Reader                                        | 2         | 0.14%   |
| Fujitsu Siemens Computers Keyboard KB SCR                                    | 2         | 0.14%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 2         | 0.14%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 0.14%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 2         | 0.14%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 0.07%   |
| SCM Microsystems SCR3500 A Contact Reader                                    | 1         | 0.07%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 0.07%   |
| Purism, SPC Librem Key                                                       | 1         | 0.07%   |
| OmniKey CardMan Smart@Link                                                   | 1         | 0.07%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 13827     | 67.87%  |
| 1     | 4881      | 23.96%  |
| 2     | 1305      | 6.41%   |
| 3     | 247       | 1.21%   |
| 4     | 69        | 0.34%   |
| 5     | 31        | 0.15%   |
| 7     | 5         | 0.02%   |
| 6     | 5         | 0.02%   |
| 8     | 2         | 0.01%   |
| 9     | 1         | 0.005%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 2432      | 29.22%  |
| Graphics card            | 1750      | 21.03%  |
| Chipcard                 | 1239      | 14.89%  |
| Net/wireless             | 917       | 11.02%  |
| Multimedia controller    | 473       | 5.68%   |
| Communication controller | 355       | 4.27%   |
| Camera                   | 194       | 2.33%   |
| Card reader              | 156       | 1.87%   |
| Storage                  | 152       | 1.83%   |
| Unassigned class         | 145       | 1.74%   |
| Bluetooth                | 131       | 1.57%   |
| Sound                    | 130       | 1.56%   |
| Net/ethernet             | 54        | 0.65%   |
| Modem                    | 51        | 0.61%   |
| Network                  | 40        | 0.48%   |
| Storage/raid             | 25        | 0.3%    |
| Storage/ide              | 20        | 0.24%   |
| Dvb card                 | 16        | 0.19%   |
| Flash memory             | 11        | 0.13%   |
| Firewire controller      | 10        | 0.12%   |
| Tv card                  | 6         | 0.07%   |
| Storage/nvme             | 5         | 0.06%   |
| Unclassified device      | 4         | 0.05%   |
| Storage/ata              | 4         | 0.05%   |
| Video                    | 2         | 0.02%   |

