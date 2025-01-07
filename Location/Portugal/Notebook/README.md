Linux in Portugal - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Portugal.

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

Total: 2033

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad E16 Gen 2 21M5C... | [fe15c1092e](https://linux-hardware.org/?probe=fe15c1092e) | Jan 05, 2025 |
| Apple         | MacBookPro12,1              | [0699689325](https://linux-hardware.org/?probe=0699689325) | Jan 05, 2025 |
| Apple         | MacBookAir7,2               | [0b5dbc9283](https://linux-hardware.org/?probe=0b5dbc9283) | Dec 31, 2024 |
| Apple         | MacBookAir7,2               | [531feb4d85](https://linux-hardware.org/?probe=531feb4d85) | Dec 31, 2024 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [cc9cdf2e68](https://linux-hardware.org/?probe=cc9cdf2e68) | Dec 31, 2024 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [fae705de3f](https://linux-hardware.org/?probe=fae705de3f) | Dec 31, 2024 |
| Acer          | Aspire ES1-572              | [ab8d0c7c3f](https://linux-hardware.org/?probe=ab8d0c7c3f) | Dec 30, 2024 |
| HP            | EliteBook 840 G6            | [5c7d77f22a](https://linux-hardware.org/?probe=5c7d77f22a) | Dec 30, 2024 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [5099a4c834](https://linux-hardware.org/?probe=5099a4c834) | Dec 28, 2024 |
| Toshiba       | Satellite A200              | [9a071c6521](https://linux-hardware.org/?probe=9a071c6521) | Dec 27, 2024 |
| Toshiba       | Satellite A200              | [eea353e34a](https://linux-hardware.org/?probe=eea353e34a) | Dec 27, 2024 |
| ASUSTek       | ASUS Zenbook 14 UX3405MA... | [95d37ca286](https://linux-hardware.org/?probe=95d37ca286) | Dec 25, 2024 |
| Lenovo        | ThinkPad L390 20NR001HPG    | [30c7fd95ce](https://linux-hardware.org/?probe=30c7fd95ce) | Dec 22, 2024 |
| Lenovo        | ThinkPad L15 Gen 3 21C30... | [95bcab10c4](https://linux-hardware.org/?probe=95bcab10c4) | Dec 22, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [532c54f7ee](https://linux-hardware.org/?probe=532c54f7ee) | Dec 22, 2024 |
| Dell          | Inspiron 5566               | [35f435cd1f](https://linux-hardware.org/?probe=35f435cd1f) | Dec 18, 2024 |
| Samsung       | 730U3E/740U3E               | [c5e5057be2](https://linux-hardware.org/?probe=c5e5057be2) | Dec 17, 2024 |
| Lenovo        | ThinkPad A485 20MVS08500    | [64a9a91c57](https://linux-hardware.org/?probe=64a9a91c57) | Dec 14, 2024 |
| Dell          | Latitude 7490               | [14889ddf55](https://linux-hardware.org/?probe=14889ddf55) | Dec 12, 2024 |
| HP            | ENVY 15                     | [bf3def9537](https://linux-hardware.org/?probe=bf3def9537) | Dec 12, 2024 |
| HP            | ENVY 15                     | [3f3b8dc457](https://linux-hardware.org/?probe=3f3b8dc457) | Dec 12, 2024 |
| Lenovo        | ThinkPad A485 20MVS08500    | [bf16c326f0](https://linux-hardware.org/?probe=bf16c326f0) | Dec 11, 2024 |
| Lenovo        | IdeaPad Pro 5 14IMH9 83D... | [1482125b7f](https://linux-hardware.org/?probe=1482125b7f) | Dec 10, 2024 |
| MSI           | Katana GF66 11UE            | [b74e19bf4f](https://linux-hardware.org/?probe=b74e19bf4f) | Dec 10, 2024 |
| Lenovo        | IdeaPad Pro 5 14IMH9 83D... | [64809e77e6](https://linux-hardware.org/?probe=64809e77e6) | Dec 10, 2024 |
| Lenovo        | Y520-15IKBN 80WK            | [23c377735b](https://linux-hardware.org/?probe=23c377735b) | Dec 09, 2024 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [3119155502](https://linux-hardware.org/?probe=3119155502) | Dec 07, 2024 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [4a921c31f8](https://linux-hardware.org/?probe=4a921c31f8) | Dec 07, 2024 |
| Dell          | Latitude 7280               | [8abf259624](https://linux-hardware.org/?probe=8abf259624) | Dec 06, 2024 |
| Samsung       | 530U3C/530U4C/532U3C        | [aaecf0d069](https://linux-hardware.org/?probe=aaecf0d069) | Dec 05, 2024 |
| Gigabyte      | G5 KF5                      | [e80cdb16ef](https://linux-hardware.org/?probe=e80cdb16ef) | Dec 03, 2024 |
| Apple         | MacBookPro8,1               | [424834b527](https://linux-hardware.org/?probe=424834b527) | Dec 01, 2024 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | [403c3abe32](https://linux-hardware.org/?probe=403c3abe32) | Dec 01, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [7b31095891](https://linux-hardware.org/?probe=7b31095891) | Nov 29, 2024 |
| Lenovo        | ThinkPad E14 Gen 6 21M7C... | [a4553836b7](https://linux-hardware.org/?probe=a4553836b7) | Nov 28, 2024 |
| Acer          | Aspire E5-521G              | [234e21b8b6](https://linux-hardware.org/?probe=234e21b8b6) | Nov 28, 2024 |
| Samsung       | 730U3E/740U3E               | [d3202d1f51](https://linux-hardware.org/?probe=d3202d1f51) | Nov 27, 2024 |
| Unknown       | Unknown                     | [2800502e8a](https://linux-hardware.org/?probe=2800502e8a) | Nov 26, 2024 |
| Unknown       | Unknown                     | [e58584102b](https://linux-hardware.org/?probe=e58584102b) | Nov 26, 2024 |
| Acer          | Aspire E5-521G              | [7a5907751e](https://linux-hardware.org/?probe=7a5907751e) | Nov 25, 2024 |
| Toshiba       | Satellite C660D             | [1a7221b221](https://linux-hardware.org/?probe=1a7221b221) | Nov 22, 2024 |
| TongFang      | GX4HRXL                     | [6783d8fc06](https://linux-hardware.org/?probe=6783d8fc06) | Nov 21, 2024 |
| TongFang      | GX4HRXL                     | [0475501c8c](https://linux-hardware.org/?probe=0475501c8c) | Nov 21, 2024 |
| Lenovo        | LOQ 15APH8 82XT             | [4a80bcfae8](https://linux-hardware.org/?probe=4a80bcfae8) | Nov 20, 2024 |
| MSI           | Prestige 16 AI Studio B1... | [fa335a2999](https://linux-hardware.org/?probe=fa335a2999) | Nov 20, 2024 |
| Lenovo        | LOQ 15APH8 82XT             | [1f4cfc38ad](https://linux-hardware.org/?probe=1f4cfc38ad) | Nov 18, 2024 |
| Chuwi         | CoreBook X                  | [da340df136](https://linux-hardware.org/?probe=da340df136) | Nov 18, 2024 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | [9f1e8708e9](https://linux-hardware.org/?probe=9f1e8708e9) | Nov 18, 2024 |
| ASUSTek       | X550JK                      | [82b0e4d59c](https://linux-hardware.org/?probe=82b0e4d59c) | Nov 17, 2024 |
| ASUSTek       | X550JK                      | [b343c33a78](https://linux-hardware.org/?probe=b343c33a78) | Nov 17, 2024 |
| HP            | Laptop 15-bs0xx             | [a708aafedc](https://linux-hardware.org/?probe=a708aafedc) | Nov 16, 2024 |
| Dell          | Latitude E5500              | [872edd1a02](https://linux-hardware.org/?probe=872edd1a02) | Nov 15, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [47389ed4d4](https://linux-hardware.org/?probe=47389ed4d4) | Nov 15, 2024 |
| Acer          | Aspire A515-51G             | [6fe0c808b4](https://linux-hardware.org/?probe=6fe0c808b4) | Nov 15, 2024 |
| Acer          | Aspire A515-51G             | [8aae6438ce](https://linux-hardware.org/?probe=8aae6438ce) | Nov 15, 2024 |
| ASUSTek       | X201EV                      | [841c78f732](https://linux-hardware.org/?probe=841c78f732) | Nov 10, 2024 |
| Acer          | Extensa 5620                | [3ce6a80956](https://linux-hardware.org/?probe=3ce6a80956) | Nov 10, 2024 |
| Acer          | Extensa 5620                | [2aadd1b426](https://linux-hardware.org/?probe=2aadd1b426) | Nov 10, 2024 |
| Valve         | Jupiter                     | [709ca74058](https://linux-hardware.org/?probe=709ca74058) | Nov 09, 2024 |
| MSI           | Prestige 16 AI Studio B1... | [f0052fafb7](https://linux-hardware.org/?probe=f0052fafb7) | Nov 07, 2024 |
| ASUSTek       | G75VW                       | [a51b619e09](https://linux-hardware.org/?probe=a51b619e09) | Nov 05, 2024 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | [2f6eabb514](https://linux-hardware.org/?probe=2f6eabb514) | Nov 03, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [3b039374f1](https://linux-hardware.org/?probe=3b039374f1) | Oct 30, 2024 |
| Dell          | Latitude 5290 2-in-1        | [dcbfa3ffe4](https://linux-hardware.org/?probe=dcbfa3ffe4) | Oct 28, 2024 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [cccd0be2aa](https://linux-hardware.org/?probe=cccd0be2aa) | Oct 26, 2024 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [658de26f3f](https://linux-hardware.org/?probe=658de26f3f) | Oct 25, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [4b872572eb](https://linux-hardware.org/?probe=4b872572eb) | Oct 25, 2024 |
| Lenovo        | ThinkPad E15 20RD005VRT     | [0faadd1106](https://linux-hardware.org/?probe=0faadd1106) | Oct 24, 2024 |
| ASUSTek       | P50IJ                       | [bf855fcb57](https://linux-hardware.org/?probe=bf855fcb57) | Oct 24, 2024 |
| ASUSTek       | UX303UB                     | [14619c281d](https://linux-hardware.org/?probe=14619c281d) | Oct 23, 2024 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [c393ac5f48](https://linux-hardware.org/?probe=c393ac5f48) | Oct 23, 2024 |
| Clevo         | M7x0S                       | [053c1ee14c](https://linux-hardware.org/?probe=053c1ee14c) | Oct 22, 2024 |
| HP            | ENVY 17                     | [16523159a4](https://linux-hardware.org/?probe=16523159a4) | Oct 22, 2024 |
| HP            | ENVY 17                     | [adfa890697](https://linux-hardware.org/?probe=adfa890697) | Oct 22, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [f5b00c79d2](https://linux-hardware.org/?probe=f5b00c79d2) | Oct 22, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [ba78d31b05](https://linux-hardware.org/?probe=ba78d31b05) | Oct 21, 2024 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [5ddfbb59eb](https://linux-hardware.org/?probe=5ddfbb59eb) | Oct 20, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [9bd3ebe34d](https://linux-hardware.org/?probe=9bd3ebe34d) | Oct 19, 2024 |
| AMI           | Intel                       | [eb14c5b7de](https://linux-hardware.org/?probe=eb14c5b7de) | Oct 19, 2024 |
| HP            | Stream Laptop 14-cb101np    | [e8bc94e534](https://linux-hardware.org/?probe=e8bc94e534) | Oct 17, 2024 |
| HP            | Pavilion Laptop 15-ck0xx    | [0027b8603f](https://linux-hardware.org/?probe=0027b8603f) | Oct 16, 2024 |
| HP            | Pavilion Laptop 15-ck0xx    | [f45e1e8c54](https://linux-hardware.org/?probe=f45e1e8c54) | Oct 16, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [5a3c293945](https://linux-hardware.org/?probe=5a3c293945) | Oct 15, 2024 |
| Positivo      | VJF154                      | [dbd1be19a4](https://linux-hardware.org/?probe=dbd1be19a4) | Oct 12, 2024 |
| Positivo      | VJF154                      | [11a95affa0](https://linux-hardware.org/?probe=11a95affa0) | Oct 12, 2024 |
| Acer          | Aspire ES1-520              | [a111863b78](https://linux-hardware.org/?probe=a111863b78) | Oct 08, 2024 |
| Dell          | Latitude E5570              | [81ce53f60c](https://linux-hardware.org/?probe=81ce53f60c) | Oct 07, 2024 |
| HUAWEI        | BOHK-WAX9X                  | [e13f29974f](https://linux-hardware.org/?probe=e13f29974f) | Oct 05, 2024 |
| Positivo      | VJF154                      | [70bb906734](https://linux-hardware.org/?probe=70bb906734) | Oct 04, 2024 |
| Dell          | Latitude 7280               | [6799bfcd82](https://linux-hardware.org/?probe=6799bfcd82) | Oct 03, 2024 |
| Acer          | Nitro AN515-58              | [a4ffdce5bf](https://linux-hardware.org/?probe=a4ffdce5bf) | Oct 01, 2024 |
| Lenovo        | LOQ 15APH8 82XT             | [d6687a8b24](https://linux-hardware.org/?probe=d6687a8b24) | Oct 01, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [a266632de8](https://linux-hardware.org/?probe=a266632de8) | Sep 30, 2024 |
| Notebook      | NLxxPUx                     | [72f90857d6](https://linux-hardware.org/?probe=72f90857d6) | Sep 29, 2024 |
| ASUSTek       | X540SA                      | [2d7db2ffb3](https://linux-hardware.org/?probe=2d7db2ffb3) | Sep 28, 2024 |
| PC Special... | Ionico 15 M                 | [1f586c152d](https://linux-hardware.org/?probe=1f586c152d) | Sep 27, 2024 |
| HP            | ENVY 15                     | [cec3ec4958](https://linux-hardware.org/?probe=cec3ec4958) | Sep 26, 2024 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [eed7d93749](https://linux-hardware.org/?probe=eed7d93749) | Sep 26, 2024 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [3dc1653a8b](https://linux-hardware.org/?probe=3dc1653a8b) | Sep 25, 2024 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [8eb59e41d3](https://linux-hardware.org/?probe=8eb59e41d3) | Sep 24, 2024 |
| ASUSTek       | X411UN                      | [d4bc8d6e18](https://linux-hardware.org/?probe=d4bc8d6e18) | Sep 20, 2024 |
| ASUSTek       | X411UN                      | [58db6ddb64](https://linux-hardware.org/?probe=58db6ddb64) | Sep 20, 2024 |
| HP            | EliteBook 840 G6            | [80f2bfeaf7](https://linux-hardware.org/?probe=80f2bfeaf7) | Sep 19, 2024 |
| HP            | OMEN by Laptop 16-c0xxx     | [27fbea506b](https://linux-hardware.org/?probe=27fbea506b) | Sep 18, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [d41454dadb](https://linux-hardware.org/?probe=d41454dadb) | Sep 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [7f8844716d](https://linux-hardware.org/?probe=7f8844716d) | Sep 15, 2024 |
| MSI           | GF63 Thin 9SC               | [c1b1468e8c](https://linux-hardware.org/?probe=c1b1468e8c) | Sep 15, 2024 |
| MSI           | GF63 Thin 9SC               | [2eb493dceb](https://linux-hardware.org/?probe=2eb493dceb) | Sep 15, 2024 |
| Lenovo        | ThinkPad T14 Gen 5 21MCC... | [0f630f3be3](https://linux-hardware.org/?probe=0f630f3be3) | Sep 14, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [bf0a437c11](https://linux-hardware.org/?probe=bf0a437c11) | Sep 14, 2024 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [a8541433e2](https://linux-hardware.org/?probe=a8541433e2) | Sep 13, 2024 |
| Acer          | Extensa 215-55              | [578e2dbf44](https://linux-hardware.org/?probe=578e2dbf44) | Sep 12, 2024 |
| HP            | 15                          | [528cbd024c](https://linux-hardware.org/?probe=528cbd024c) | Sep 12, 2024 |
| HP            | EliteBook 8440p             | [8f43afd63c](https://linux-hardware.org/?probe=8f43afd63c) | Sep 09, 2024 |
| HP            | EliteBook 820 G2            | [0ea31e9a91](https://linux-hardware.org/?probe=0ea31e9a91) | Sep 09, 2024 |
| HP            | Spectre Pro x360 G1         | [8fa4b550fc](https://linux-hardware.org/?probe=8fa4b550fc) | Sep 08, 2024 |
| HP            | Compaq Presario CQ61        | [7f219497f7](https://linux-hardware.org/?probe=7f219497f7) | Sep 07, 2024 |
| Notebook      | W65KJ1_KK1                  | [54dc17b5cd](https://linux-hardware.org/?probe=54dc17b5cd) | Sep 07, 2024 |
| Dell          | XPS 15 9510                 | [c36d4de7b4](https://linux-hardware.org/?probe=c36d4de7b4) | Sep 06, 2024 |
| Medion        | M14L-256                    | [d675ebbba3](https://linux-hardware.org/?probe=d675ebbba3) | Sep 03, 2024 |
| Lenovo        | ThinkPad E470 20H2S09A00    | [b691dad5ba](https://linux-hardware.org/?probe=b691dad5ba) | Sep 02, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JN0... | [46b2c8c407](https://linux-hardware.org/?probe=46b2c8c407) | Sep 02, 2024 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [b93d783998](https://linux-hardware.org/?probe=b93d783998) | Aug 31, 2024 |
| Chuwi         | GemiBook Pro                | [de36345abe](https://linux-hardware.org/?probe=de36345abe) | Aug 27, 2024 |
| Acer          | Aspire E5-551G              | [c28309e2cf](https://linux-hardware.org/?probe=c28309e2cf) | Aug 27, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [6ef394b941](https://linux-hardware.org/?probe=6ef394b941) | Aug 27, 2024 |
| HUAWEI        | BOHK-WAX9X                  | [b0c4590621](https://linux-hardware.org/?probe=b0c4590621) | Aug 27, 2024 |
| Acer          | Aspire VN7-792G             | [5b9c3467d8](https://linux-hardware.org/?probe=5b9c3467d8) | Aug 25, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [e0df5dade1](https://linux-hardware.org/?probe=e0df5dade1) | Aug 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [cec8363b7e](https://linux-hardware.org/?probe=cec8363b7e) | Aug 23, 2024 |
| ASUSTek       | N551JK                      | [68cbab902c](https://linux-hardware.org/?probe=68cbab902c) | Aug 22, 2024 |
| HP            | Laptop 15s-eq0xxx           | [0bb57c91c7](https://linux-hardware.org/?probe=0bb57c91c7) | Aug 21, 2024 |
| Chuwi         | GemiBook Pro                | [d91995f58b](https://linux-hardware.org/?probe=d91995f58b) | Aug 19, 2024 |
| Dell          | Precision 3581              | [ba1f860fda](https://linux-hardware.org/?probe=ba1f860fda) | Aug 16, 2024 |
| Dell          | Precision 3581              | [fab693cd72](https://linux-hardware.org/?probe=fab693cd72) | Aug 16, 2024 |
| HP            | ENVY Notebook               | [fa59ee7fd3](https://linux-hardware.org/?probe=fa59ee7fd3) | Aug 14, 2024 |
| HP            | Casablanca H510             | [53794a587e](https://linux-hardware.org/?probe=53794a587e) | Aug 12, 2024 |
| Acer          | Extensa 5635G               | [9f423ffc83](https://linux-hardware.org/?probe=9f423ffc83) | Aug 11, 2024 |
| Acer          | Aspire 5738                 | [3778c0a752](https://linux-hardware.org/?probe=3778c0a752) | Aug 10, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [fef6ca7ee4](https://linux-hardware.org/?probe=fef6ca7ee4) | Aug 09, 2024 |
| Gateway       | NV54 Series                 | [5d5a0e08e3](https://linux-hardware.org/?probe=5d5a0e08e3) | Aug 09, 2024 |
| HUAWEI        | KLVL-WXXW                   | [a113fdc5cb](https://linux-hardware.org/?probe=a113fdc5cb) | Aug 08, 2024 |
| HP            | Laptop 15s-eq0xxx           | [959b339997](https://linux-hardware.org/?probe=959b339997) | Aug 07, 2024 |
| HP            | Laptop 15s-eq0xxx           | [6a79a09c14](https://linux-hardware.org/?probe=6a79a09c14) | Aug 07, 2024 |
| Acer          | Aspire 5738                 | [a66d532e8d](https://linux-hardware.org/?probe=a66d532e8d) | Aug 02, 2024 |
| ASUSTek       | X542URR                     | [fc12ea2e03](https://linux-hardware.org/?probe=fc12ea2e03) | Aug 02, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [c7919b571d](https://linux-hardware.org/?probe=c7919b571d) | Jul 31, 2024 |
| Fujitsu       | LIFEBOOK U939               | [59f90b88f5](https://linux-hardware.org/?probe=59f90b88f5) | Jul 31, 2024 |
| HUAWEI        | RLEF-XX                     | [2169ee13f7](https://linux-hardware.org/?probe=2169ee13f7) | Jul 29, 2024 |
| Acer          | Aspire 5738                 | [2e72dc261e](https://linux-hardware.org/?probe=2e72dc261e) | Jul 28, 2024 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [253d386a46](https://linux-hardware.org/?probe=253d386a46) | Jul 26, 2024 |
| ASUSTek       | K52JB                       | [b84fe5605a](https://linux-hardware.org/?probe=b84fe5605a) | Jul 25, 2024 |
| Acer          | Aspire A315-44P             | [4c33085f6e](https://linux-hardware.org/?probe=4c33085f6e) | Jul 23, 2024 |
| Acer          | Aspire 5738                 | [4118b16aa8](https://linux-hardware.org/?probe=4118b16aa8) | Jul 20, 2024 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [dd666c1878](https://linux-hardware.org/?probe=dd666c1878) | Jul 20, 2024 |
| HP            | G62                         | [212822c040](https://linux-hardware.org/?probe=212822c040) | Jul 20, 2024 |
| Toshiba       | QOSMIO X770                 | [c79d310c82](https://linux-hardware.org/?probe=c79d310c82) | Jul 20, 2024 |
| Toshiba       | QOSMIO X770                 | [8bc354cc7e](https://linux-hardware.org/?probe=8bc354cc7e) | Jul 20, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [d73df831dd](https://linux-hardware.org/?probe=d73df831dd) | Jul 19, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [3bfa6b7e07](https://linux-hardware.org/?probe=3bfa6b7e07) | Jul 19, 2024 |
| Lenovo        | LOQ 15APH8 82XT             | [38cee88852](https://linux-hardware.org/?probe=38cee88852) | Jul 19, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [de0ec9eb92](https://linux-hardware.org/?probe=de0ec9eb92) | Jul 18, 2024 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [8f829dd4ac](https://linux-hardware.org/?probe=8f829dd4ac) | Jul 17, 2024 |
| Toshiba       | TECRA R950                  | [cc1743ae14](https://linux-hardware.org/?probe=cc1743ae14) | Jul 17, 2024 |
| MSI           | GP62 2QD                    | [d535c8391d](https://linux-hardware.org/?probe=d535c8391d) | Jul 16, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [a3e43daae8](https://linux-hardware.org/?probe=a3e43daae8) | Jul 15, 2024 |
| Lenovo        | ThinkPad P51s 20HB000VPG    | [fc2a09d595](https://linux-hardware.org/?probe=fc2a09d595) | Jul 11, 2024 |
| Apple         | MacBookPro11,1              | [ea25c8dde3](https://linux-hardware.org/?probe=ea25c8dde3) | Jul 11, 2024 |
| ASUSTek       | X542URR                     | [865ff968f2](https://linux-hardware.org/?probe=865ff968f2) | Jul 11, 2024 |
| HP            | Notebook                    | [51b2655beb](https://linux-hardware.org/?probe=51b2655beb) | Jul 11, 2024 |
| Acer          | Aspire V3-572G              | [18fe6672c4](https://linux-hardware.org/?probe=18fe6672c4) | Jul 11, 2024 |
| Dell          | Latitude 7480               | [7bd2a14f0d](https://linux-hardware.org/?probe=7bd2a14f0d) | Jul 11, 2024 |
| ASUSTek       | K52JB                       | [d50ec4eed9](https://linux-hardware.org/?probe=d50ec4eed9) | Jul 09, 2024 |
| Lenovo        | Yoga Slim 7 Pro 14ARH7 8... | [0eff33b928](https://linux-hardware.org/?probe=0eff33b928) | Jul 09, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d7c2d0c8e1](https://linux-hardware.org/?probe=d7c2d0c8e1) | Jul 08, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [70c8da551c](https://linux-hardware.org/?probe=70c8da551c) | Jul 06, 2024 |
| Acer          | Aspire V3-572G              | [9f7a6011ec](https://linux-hardware.org/?probe=9f7a6011ec) | Jul 06, 2024 |
| Lenovo        | G50-70 20351                | [41d1f88c89](https://linux-hardware.org/?probe=41d1f88c89) | Jul 06, 2024 |
| HP            | EliteBook 860 16 inch G9... | [ecf533ca1a](https://linux-hardware.org/?probe=ecf533ca1a) | Jul 05, 2024 |
| Lenovo        | 3000 G410                   | [8d4dba044b](https://linux-hardware.org/?probe=8d4dba044b) | Jul 04, 2024 |
| HP            | Laptop 15s-eq2xxx           | [063d89b1aa](https://linux-hardware.org/?probe=063d89b1aa) | Jul 02, 2024 |
| ASUSTek       | X540LJ                      | [c61b3420e8](https://linux-hardware.org/?probe=c61b3420e8) | Jul 01, 2024 |
| Apple         | MacBookPro5,5               | [417a336215](https://linux-hardware.org/?probe=417a336215) | Jun 30, 2024 |
| ASUSTek       | K52JB                       | [cda7f38058](https://linux-hardware.org/?probe=cda7f38058) | Jun 29, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [9ea8077d23](https://linux-hardware.org/?probe=9ea8077d23) | Jun 28, 2024 |
| Apple         | MacBookPro5,5               | [00bc13ac3d](https://linux-hardware.org/?probe=00bc13ac3d) | Jun 28, 2024 |
| Toshiba       | Satellite L50-B             | [d011c502a1](https://linux-hardware.org/?probe=d011c502a1) | Jun 23, 2024 |
| Apple         | MacBookPro8,1               | [0617f79fab](https://linux-hardware.org/?probe=0617f79fab) | Jun 22, 2024 |
| Lenovo        | Yoga Pro 9 16IMH9 83DN      | [b74a2d1e4d](https://linux-hardware.org/?probe=b74a2d1e4d) | Jun 22, 2024 |
| Valve         | Jupiter                     | [cfb741b75a](https://linux-hardware.org/?probe=cfb741b75a) | Jun 22, 2024 |
| Acer          | Predator PH315-53           | [f99972c013](https://linux-hardware.org/?probe=f99972c013) | Jun 21, 2024 |
| Positivo      | H14BU08                     | [22fef1c434](https://linux-hardware.org/?probe=22fef1c434) | Jun 16, 2024 |
| Chuwi         | X312B                       | [e3f70e6b1d](https://linux-hardware.org/?probe=e3f70e6b1d) | Jun 16, 2024 |
| Acer          | Nitro AN515-58              | [35406d518c](https://linux-hardware.org/?probe=35406d518c) | Jun 14, 2024 |
| INSYS         | GW1-W149                    | [a83f2e7832](https://linux-hardware.org/?probe=a83f2e7832) | Jun 14, 2024 |
| INSYS         | GW1-W149                    | [1cc31e3a28](https://linux-hardware.org/?probe=1cc31e3a28) | Jun 12, 2024 |
| HP            | G62                         | [bf227180be](https://linux-hardware.org/?probe=bf227180be) | Jun 12, 2024 |
| Medion        | M14L-256                    | [264a58412a](https://linux-hardware.org/?probe=264a58412a) | Jun 10, 2024 |
| HP            | OMEN by Laptop 16-c0xxx     | [9e5813c818](https://linux-hardware.org/?probe=9e5813c818) | Jun 10, 2024 |
| ASUSTek       | K52JB                       | [8b00c7ecac](https://linux-hardware.org/?probe=8b00c7ecac) | Jun 10, 2024 |
| Clevo         | M7x0S                       | [083608ca16](https://linux-hardware.org/?probe=083608ca16) | Jun 09, 2024 |
| Clevo         | M7x0S                       | [d18139eed5](https://linux-hardware.org/?probe=d18139eed5) | Jun 09, 2024 |
| Dell          | Latitude E7470              | [5ffd29a612](https://linux-hardware.org/?probe=5ffd29a612) | Jun 08, 2024 |
| HP            | Compaq Presario CQ61        | [4a7e35bc25](https://linux-hardware.org/?probe=4a7e35bc25) | Jun 07, 2024 |
| Apple         | MacBookPro7,1               | [2b7a701c8d](https://linux-hardware.org/?probe=2b7a701c8d) | Jun 07, 2024 |
| Apple         | MacBookPro7,1               | [ce136ae7b1](https://linux-hardware.org/?probe=ce136ae7b1) | Jun 07, 2024 |
| HP            | Compaq Presario CQ61        | [36506257c0](https://linux-hardware.org/?probe=36506257c0) | Jun 06, 2024 |
| LG Electro... | P1-J331P                    | [a24862e047](https://linux-hardware.org/?probe=a24862e047) | Jun 02, 2024 |
| LG Electro... | P1-J331P                    | [948cbb9a59](https://linux-hardware.org/?probe=948cbb9a59) | Jun 02, 2024 |
| HP            | G62                         | [8134433799](https://linux-hardware.org/?probe=8134433799) | Jun 02, 2024 |
| Lenovo        | Legion Y530-15ICH 81FV      | [ab1fae990c](https://linux-hardware.org/?probe=ab1fae990c) | Jun 02, 2024 |
| Lenovo        | ThinkPad X61 7673V4Q        | [f0cd5ab7c3](https://linux-hardware.org/?probe=f0cd5ab7c3) | Jun 02, 2024 |
| HP            | Notebook                    | [3cc66a2fed](https://linux-hardware.org/?probe=3cc66a2fed) | May 31, 2024 |
| Acer          | Nitro AN515-58              | [596586e57d](https://linux-hardware.org/?probe=596586e57d) | May 31, 2024 |
| Acer          | Nitro AN515-58              | [2d90991e7f](https://linux-hardware.org/?probe=2d90991e7f) | May 28, 2024 |
| Avell High... | A62 LIV                     | [970d874c5d](https://linux-hardware.org/?probe=970d874c5d) | May 26, 2024 |
| SLIMBOOK      | EXCALIBUR-16-AMD7           | [875be34b1d](https://linux-hardware.org/?probe=875be34b1d) | May 25, 2024 |
| Lenovo        | LOQ 16IRH8 82XW             | [2918fb5b8f](https://linux-hardware.org/?probe=2918fb5b8f) | May 24, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [6f1ba28a0e](https://linux-hardware.org/?probe=6f1ba28a0e) | May 22, 2024 |
| Dynabook      | PORTEGE X50-G               | [995067b4e8](https://linux-hardware.org/?probe=995067b4e8) | May 22, 2024 |
| Acer          | Aspire V3-572G              | [afbfc24291](https://linux-hardware.org/?probe=afbfc24291) | May 22, 2024 |
| HP            | Pavilion Laptop 14-ec0xx... | [cd9282328c](https://linux-hardware.org/?probe=cd9282328c) | May 20, 2024 |
| HP            | Pavilion Laptop 14-ec0xx... | [874014185a](https://linux-hardware.org/?probe=874014185a) | May 20, 2024 |
| HP            | OMEN by Laptop 15-ce0xx     | [77c05dbd69](https://linux-hardware.org/?probe=77c05dbd69) | May 17, 2024 |
| Acer          | Nitro AN515-51              | [cba3f4fd9d](https://linux-hardware.org/?probe=cba3f4fd9d) | May 17, 2024 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [37000360b7](https://linux-hardware.org/?probe=37000360b7) | May 16, 2024 |
| Medion        | M14L-256                    | [94e8eba5f5](https://linux-hardware.org/?probe=94e8eba5f5) | May 15, 2024 |
| Dell          | Latitude 5410               | [f953fc7767](https://linux-hardware.org/?probe=f953fc7767) | May 13, 2024 |
| Packard Be... | EasyNote TS11HR             | [0681add602](https://linux-hardware.org/?probe=0681add602) | May 12, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [884ad885b6](https://linux-hardware.org/?probe=884ad885b6) | May 10, 2024 |
| MSI           | Cyborg 15 A12VF             | [1168634a54](https://linux-hardware.org/?probe=1168634a54) | May 06, 2024 |
| ASUSTek       | F5SL                        | [da423af0cb](https://linux-hardware.org/?probe=da423af0cb) | May 05, 2024 |
| ASUSTek       | ROG Strix G733QM_G733QM     | [c7e3ed99cc](https://linux-hardware.org/?probe=c7e3ed99cc) | May 04, 2024 |
| INSYS         | GW1-W149                    | [1219dfdc44](https://linux-hardware.org/?probe=1219dfdc44) | May 02, 2024 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | [f899f3dccf](https://linux-hardware.org/?probe=f899f3dccf) | May 01, 2024 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [56c9f37671](https://linux-hardware.org/?probe=56c9f37671) | Apr 29, 2024 |
| Acer          | Nitro AN515-58              | [5192e9d32b](https://linux-hardware.org/?probe=5192e9d32b) | Apr 27, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [4f05e448a7](https://linux-hardware.org/?probe=4f05e448a7) | Apr 26, 2024 |
| HUAWEI        | BOM-WXX9                    | [5fe5c7ed8d](https://linux-hardware.org/?probe=5fe5c7ed8d) | Apr 26, 2024 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [70560c5a36](https://linux-hardware.org/?probe=70560c5a36) | Apr 25, 2024 |
| Acer          | Nitro AN515-58              | [4512bf861b](https://linux-hardware.org/?probe=4512bf861b) | Apr 24, 2024 |
| Dell          | Latitude 5290 2-in-1        | [de4f7d0a06](https://linux-hardware.org/?probe=de4f7d0a06) | Apr 23, 2024 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [62d4436d4e](https://linux-hardware.org/?probe=62d4436d4e) | Apr 21, 2024 |
| Medion        | M14L-256                    | [21ced95f8d](https://linux-hardware.org/?probe=21ced95f8d) | Apr 21, 2024 |
| LNV           | M14LC2-256                  | [582ccc43d4](https://linux-hardware.org/?probe=582ccc43d4) | Apr 21, 2024 |
| Dell          | Latitude 13                 | [88b6f3f2c8](https://linux-hardware.org/?probe=88b6f3f2c8) | Apr 20, 2024 |
| HP            | Pavilion Notebook           | [8b925ca8f0](https://linux-hardware.org/?probe=8b925ca8f0) | Apr 19, 2024 |
| INSYS         | GW1-W149                    | [2f53f6286d](https://linux-hardware.org/?probe=2f53f6286d) | Apr 15, 2024 |
| Apple         | MacBookAir2,1               | [9145361a08](https://linux-hardware.org/?probe=9145361a08) | Apr 15, 2024 |
| Apple         | MacBookAir2,1               | [94a43b871f](https://linux-hardware.org/?probe=94a43b871f) | Apr 14, 2024 |
| Apple         | MacBookPro11,3              | [159bfe4be5](https://linux-hardware.org/?probe=159bfe4be5) | Apr 13, 2024 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [22b0bf7e14](https://linux-hardware.org/?probe=22b0bf7e14) | Apr 13, 2024 |
| Apple         | MacBookPro9,1               | [421b7a0e3a](https://linux-hardware.org/?probe=421b7a0e3a) | Apr 12, 2024 |
| Toshiba       | Satellite Pro C50-A-1C8     | [64265aeb0e](https://linux-hardware.org/?probe=64265aeb0e) | Apr 12, 2024 |
| ASUSTek       | X542URR                     | [e3a4e15a6e](https://linux-hardware.org/?probe=e3a4e15a6e) | Apr 12, 2024 |
| Dell          | Precision 3571              | [6bef26b856](https://linux-hardware.org/?probe=6bef26b856) | Apr 10, 2024 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [67c665fbe5](https://linux-hardware.org/?probe=67c665fbe5) | Apr 09, 2024 |
| ASUSTek       | K55VM                       | [081e45fb7f](https://linux-hardware.org/?probe=081e45fb7f) | Apr 08, 2024 |
| Dell          | Precision 3571              | [fdab7d40f5](https://linux-hardware.org/?probe=fdab7d40f5) | Apr 07, 2024 |
| HP            | EliteBook 840 14 inch G9... | [3eb7bba175](https://linux-hardware.org/?probe=3eb7bba175) | Apr 04, 2024 |
| ASUSTek       | ROG Strix G733QM_G733QM     | [556039fa6c](https://linux-hardware.org/?probe=556039fa6c) | Apr 04, 2024 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [9bc584b914](https://linux-hardware.org/?probe=9bc584b914) | Apr 03, 2024 |
| Lenovo        | ThinkPad L15 Gen 3 21C30... | [7a09978e27](https://linux-hardware.org/?probe=7a09978e27) | Apr 03, 2024 |
| Lenovo        | ThinkPad L380 20M50011PG    | [663de4db43](https://linux-hardware.org/?probe=663de4db43) | Apr 03, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [955dc4530f](https://linux-hardware.org/?probe=955dc4530f) | Apr 02, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [083640b754](https://linux-hardware.org/?probe=083640b754) | Mar 31, 2024 |
| Medion        | M14L-256                    | [28c0f833c0](https://linux-hardware.org/?probe=28c0f833c0) | Mar 31, 2024 |
| Dell          | Vostro 1015                 | [f9ca91d526](https://linux-hardware.org/?probe=f9ca91d526) | Mar 29, 2024 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [5b4456a2d6](https://linux-hardware.org/?probe=5b4456a2d6) | Mar 29, 2024 |
| Sony          | VPCY11S1E                   | [905655032f](https://linux-hardware.org/?probe=905655032f) | Mar 29, 2024 |
| INET          | Z156                        | [fd38934a49](https://linux-hardware.org/?probe=fd38934a49) | Mar 27, 2024 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [c2dedfbe62](https://linux-hardware.org/?probe=c2dedfbe62) | Mar 25, 2024 |
| ASUSTek       | F5RL                        | [6d1c82c10a](https://linux-hardware.org/?probe=6d1c82c10a) | Mar 24, 2024 |
| Medion        | M14L-256                    | [d2fb66e78e](https://linux-hardware.org/?probe=d2fb66e78e) | Mar 22, 2024 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [99ff7d5b73](https://linux-hardware.org/?probe=99ff7d5b73) | Mar 21, 2024 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [8041a52ffe](https://linux-hardware.org/?probe=8041a52ffe) | Mar 21, 2024 |
| Unknown       | Apple MacBook Pro (13-in... | [3bc7983914](https://linux-hardware.org/?probe=3bc7983914) | Mar 20, 2024 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | [f7da71747e](https://linux-hardware.org/?probe=f7da71747e) | Mar 18, 2024 |
| Dell          | Inspiron 15-3567            | [4c1a37011d](https://linux-hardware.org/?probe=4c1a37011d) | Mar 18, 2024 |
| Dell          | Inspiron 15-3567            | [b322a7f7ff](https://linux-hardware.org/?probe=b322a7f7ff) | Mar 18, 2024 |
| Toshiba       | Satellite C660D             | [63b9e3f1b8](https://linux-hardware.org/?probe=63b9e3f1b8) | Mar 18, 2024 |
| Medion        | E15301                      | [a3f6fc8c36](https://linux-hardware.org/?probe=a3f6fc8c36) | Mar 17, 2024 |
| HP            | Pavilion dv6000 (GF677EA... | [ecbe5ffb1f](https://linux-hardware.org/?probe=ecbe5ffb1f) | Mar 16, 2024 |
| HP            | Pavilion Power Laptop 15... | [8529154b4a](https://linux-hardware.org/?probe=8529154b4a) | Mar 15, 2024 |
| Acer          | Aspire 5742                 | [280af1d066](https://linux-hardware.org/?probe=280af1d066) | Mar 12, 2024 |
| HP            | OMEN by Laptop              | [754b3828fc](https://linux-hardware.org/?probe=754b3828fc) | Mar 12, 2024 |
| HP            | EliteBook Folio 9470m       | [ddf5a549da](https://linux-hardware.org/?probe=ddf5a549da) | Mar 11, 2024 |
| ASUSTek       | ROG Strix G513IE_G513IE     | [695773aa7b](https://linux-hardware.org/?probe=695773aa7b) | Mar 10, 2024 |
| Samsung       | 870Z5E/880Z5E/680Z5E        | [fd7305258c](https://linux-hardware.org/?probe=fd7305258c) | Mar 10, 2024 |
| ASUSTek       | X555LJ                      | [72da032893](https://linux-hardware.org/?probe=72da032893) | Mar 09, 2024 |
| HP            | Laptop 15s-eq0xxx           | [e4a401d044](https://linux-hardware.org/?probe=e4a401d044) | Mar 08, 2024 |
| Lenovo        | ThinkPad T440p              | [fb060608ab](https://linux-hardware.org/?probe=fb060608ab) | Mar 08, 2024 |
| Dell          | Latitude 7280               | [b40f34a4ed](https://linux-hardware.org/?probe=b40f34a4ed) | Mar 02, 2024 |
| AMI           | Intel                       | [e9dc6ddc46](https://linux-hardware.org/?probe=e9dc6ddc46) | Mar 01, 2024 |
| SLIMBOOK      | EXECUTIVE-14                | [39d528dadf](https://linux-hardware.org/?probe=39d528dadf) | Mar 01, 2024 |
| SLIMBOOK      | EXECUTIVE-14                | [5fc24348a8](https://linux-hardware.org/?probe=5fc24348a8) | Mar 01, 2024 |
| HP            | Pavilion Laptop 15-eh2xx... | [0510a78cfe](https://linux-hardware.org/?probe=0510a78cfe) | Feb 29, 2024 |
| Dell          | Latitude 7400               | [97c11ef92d](https://linux-hardware.org/?probe=97c11ef92d) | Feb 28, 2024 |
| HP            | EliteBook 840 14 inch G9... | [fd37aa8001](https://linux-hardware.org/?probe=fd37aa8001) | Feb 27, 2024 |
| Acer          | NC-E1-530-21174G            | [56d0444e6b](https://linux-hardware.org/?probe=56d0444e6b) | Feb 27, 2024 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | [0812dc5f8e](https://linux-hardware.org/?probe=0812dc5f8e) | Feb 26, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [527feb458b](https://linux-hardware.org/?probe=527feb458b) | Feb 26, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [3b3a145c76](https://linux-hardware.org/?probe=3b3a145c76) | Feb 23, 2024 |
| Lenovo        | ThinkPad T440p              | [da00bee2f4](https://linux-hardware.org/?probe=da00bee2f4) | Feb 23, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [500e3a58df](https://linux-hardware.org/?probe=500e3a58df) | Feb 20, 2024 |
| Medion        | M14L-256                    | [b8b493a84b](https://linux-hardware.org/?probe=b8b493a84b) | Feb 18, 2024 |
| HP            | Pavilion dv6                | [27bd273fa1](https://linux-hardware.org/?probe=27bd273fa1) | Feb 16, 2024 |
| HP            | ENVY Sleekbook 6 PC         | [1fa513616f](https://linux-hardware.org/?probe=1fa513616f) | Feb 16, 2024 |
| HP            | ENVY Sleekbook 6 PC         | [697d384203](https://linux-hardware.org/?probe=697d384203) | Feb 16, 2024 |
| HP            | Pavilion dv6                | [fd84d867f4](https://linux-hardware.org/?probe=fd84d867f4) | Feb 15, 2024 |
| Lenovo        | IdeaPad 500S-13ISK 80Q2     | [e6ae670af4](https://linux-hardware.org/?probe=e6ae670af4) | Feb 15, 2024 |
| Dell          | Latitude 7490               | [2401d4da6d](https://linux-hardware.org/?probe=2401d4da6d) | Feb 15, 2024 |
| HP            | G62                         | [b6daa4e6b1](https://linux-hardware.org/?probe=b6daa4e6b1) | Feb 12, 2024 |
| HP            | ProBook 6475b               | [e8a155c0d9](https://linux-hardware.org/?probe=e8a155c0d9) | Feb 09, 2024 |
| ASUSTek       | K54LY                       | [44e7b53945](https://linux-hardware.org/?probe=44e7b53945) | Feb 08, 2024 |
| Medion        | M14L-256                    | [f36647da46](https://linux-hardware.org/?probe=f36647da46) | Feb 07, 2024 |
| Apple         | MacBookPro5,1               | [965e14a38d](https://linux-hardware.org/?probe=965e14a38d) | Feb 06, 2024 |
| Apple         | MacBookPro5,1               | [0f0883d52e](https://linux-hardware.org/?probe=0f0883d52e) | Feb 06, 2024 |
| Dell          | Latitude E5450              | [03b9a11c55](https://linux-hardware.org/?probe=03b9a11c55) | Feb 06, 2024 |
| Dell          | XPS 9320                    | [74d4b364f8](https://linux-hardware.org/?probe=74d4b364f8) | Feb 03, 2024 |
| Dell          | Latitude 7280               | [0a79c87afb](https://linux-hardware.org/?probe=0a79c87afb) | Jan 31, 2024 |
| ASUSTek       | GL552JX                     | [4aebfef2d8](https://linux-hardware.org/?probe=4aebfef2d8) | Jan 31, 2024 |
| Minix         | NEO Z83-4A                  | [a563c8089f](https://linux-hardware.org/?probe=a563c8089f) | Jan 31, 2024 |
| Valve         | Jupiter                     | [282271ee83](https://linux-hardware.org/?probe=282271ee83) | Jan 31, 2024 |
| Valve         | Jupiter                     | [1cdbb473c3](https://linux-hardware.org/?probe=1cdbb473c3) | Jan 30, 2024 |
| HP            | Pavilion Power Laptop 15... | [8098729533](https://linux-hardware.org/?probe=8098729533) | Jan 30, 2024 |
| ASUSTek       | GL552JX                     | [4acec8f3e2](https://linux-hardware.org/?probe=4acec8f3e2) | Jan 30, 2024 |
| Medion        | M14L-256                    | [6bff8bee51](https://linux-hardware.org/?probe=6bff8bee51) | Jan 28, 2024 |
| Toshiba       | Satellite P50-B-10Z         | [574103da6a](https://linux-hardware.org/?probe=574103da6a) | Jan 28, 2024 |
| Dell          | Latitude 7490               | [8687d67e07](https://linux-hardware.org/?probe=8687d67e07) | Jan 27, 2024 |
| HP            | EliteBook 2560p             | [ed987e9ac7](https://linux-hardware.org/?probe=ed987e9ac7) | Jan 27, 2024 |
| HP            | Laptop 15-db0xxx            | [077619fc48](https://linux-hardware.org/?probe=077619fc48) | Jan 27, 2024 |
| Sony          | SVF1521J7EW                 | [ad472454ae](https://linux-hardware.org/?probe=ad472454ae) | Jan 27, 2024 |
| INSYS         | GW1-W149                    | [a37edb118a](https://linux-hardware.org/?probe=a37edb118a) | Jan 26, 2024 |
| Sony          | VGN-CS11S_Q                 | [df687ca726](https://linux-hardware.org/?probe=df687ca726) | Jan 26, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [660c45b7e5](https://linux-hardware.org/?probe=660c45b7e5) | Jan 26, 2024 |
| Sony          | VGN-CS11S_Q                 | [4c9e427a30](https://linux-hardware.org/?probe=4c9e427a30) | Jan 25, 2024 |
| Lenovo        | Legion Y530-15ICH 81FV      | [4a41cdcc67](https://linux-hardware.org/?probe=4a41cdcc67) | Jan 25, 2024 |
| Hampoo        | I2W6_AP135 Reserved         | [fe5025efdd](https://linux-hardware.org/?probe=fe5025efdd) | Jan 21, 2024 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [d10912daa4](https://linux-hardware.org/?probe=d10912daa4) | Jan 21, 2024 |
| Lenovo        | ThinkPad T460 20FMS0CR00    | [1bfe0bce6d](https://linux-hardware.org/?probe=1bfe0bce6d) | Jan 21, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [53887e0fb9](https://linux-hardware.org/?probe=53887e0fb9) | Jan 21, 2024 |
| Dell          | Latitude 7280               | [2b43daee98](https://linux-hardware.org/?probe=2b43daee98) | Jan 20, 2024 |
| Medion        | M14L-256                    | [095760429f](https://linux-hardware.org/?probe=095760429f) | Jan 18, 2024 |
| Unknown       | Unknown                     | [6e08825a5c](https://linux-hardware.org/?probe=6e08825a5c) | Jan 17, 2024 |
| HP            | Laptop 14s-dq0xxx           | [d8a2561e72](https://linux-hardware.org/?probe=d8a2561e72) | Jan 12, 2024 |
| ASUSTek       | ZenBook S UX391UA           | [bc0571ca78](https://linux-hardware.org/?probe=bc0571ca78) | Jan 11, 2024 |
| ASUSTek       | ZenBook S UX391UA           | [21d336676f](https://linux-hardware.org/?probe=21d336676f) | Jan 11, 2024 |
| HUAWEI        | NBLB-WAX9N                  | [8d8f216f10](https://linux-hardware.org/?probe=8d8f216f10) | Jan 10, 2024 |
| Sony          | VGN-FZ31Z                   | [3df7d503da](https://linux-hardware.org/?probe=3df7d503da) | Jan 09, 2024 |
| Dell          | XPS 15 9530                 | [26570f8a8b](https://linux-hardware.org/?probe=26570f8a8b) | Jan 08, 2024 |
| ASUSTek       | X550CC                      | [b4987d6897](https://linux-hardware.org/?probe=b4987d6897) | Jan 08, 2024 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [f101013f61](https://linux-hardware.org/?probe=f101013f61) | Jan 07, 2024 |
| ASUSTek       | N550JK                      | [5fe8e3ca15](https://linux-hardware.org/?probe=5fe8e3ca15) | Jan 07, 2024 |
| Acer          | Aspire ES1-572              | [6de42f8573](https://linux-hardware.org/?probe=6de42f8573) | Jan 06, 2024 |
| HP            | Pavilion 10 TS              | [cd7638b3d6](https://linux-hardware.org/?probe=cd7638b3d6) | Jan 05, 2024 |
| ASUSTek       | P50IJ                       | [5a72912f2f](https://linux-hardware.org/?probe=5a72912f2f) | Jan 03, 2024 |
| Acer          | Aspire ES1-520              | [a869979bc4](https://linux-hardware.org/?probe=a869979bc4) | Jan 02, 2024 |
| Lenovo        | Y520-15IKBN 80WK            | [8701a130d2](https://linux-hardware.org/?probe=8701a130d2) | Jan 02, 2024 |
| ASUSTek       | K53SC                       | [1f2ddea9fa](https://linux-hardware.org/?probe=1f2ddea9fa) | Dec 31, 2023 |
| Medion        | M14L-256                    | [0dbbd4db74](https://linux-hardware.org/?probe=0dbbd4db74) | Dec 31, 2023 |
| Toshiba       | Satellite Pro C50-A-1C8     | [8b28cb5a8f](https://linux-hardware.org/?probe=8b28cb5a8f) | Dec 30, 2023 |
| Lenovo        | IdeaPad 320S-13IKB 81AK     | [11892aa026](https://linux-hardware.org/?probe=11892aa026) | Dec 30, 2023 |
| HP            | OMEN by Laptop              | [71d20fd45b](https://linux-hardware.org/?probe=71d20fd45b) | Dec 28, 2023 |
| Acer          | Aspire E5-571G              | [a143ecb3c3](https://linux-hardware.org/?probe=a143ecb3c3) | Dec 27, 2023 |
| Dell          | Latitude 7490               | [3c17f0bdce](https://linux-hardware.org/?probe=3c17f0bdce) | Dec 25, 2023 |
| Dell          | Latitude 7490               | [69205c648f](https://linux-hardware.org/?probe=69205c648f) | Dec 24, 2023 |
| Unknown       | Unknown                     | [006211d916](https://linux-hardware.org/?probe=006211d916) | Dec 23, 2023 |
| Toshiba       | QOSMIO X770                 | [dceb1203ed](https://linux-hardware.org/?probe=dceb1203ed) | Dec 23, 2023 |
| Toshiba       | QOSMIO X770                 | [b9557b6218](https://linux-hardware.org/?probe=b9557b6218) | Dec 23, 2023 |
| Toshiba       | Satellite Pro C50-A-1C8     | [bfc1ebaf00](https://linux-hardware.org/?probe=bfc1ebaf00) | Dec 22, 2023 |
| HP            | 350 G1                      | [c219133bce](https://linux-hardware.org/?probe=c219133bce) | Dec 20, 2023 |
| Dell          | Latitude E6510              | [e9aceddae8](https://linux-hardware.org/?probe=e9aceddae8) | Dec 19, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [7b5e55e475](https://linux-hardware.org/?probe=7b5e55e475) | Dec 18, 2023 |
| ASUSTek       | ROG Zephyrus S15 GX502LX... | [357f74bcc2](https://linux-hardware.org/?probe=357f74bcc2) | Dec 17, 2023 |
| Medion        | M14L-256                    | [6cd85934b3](https://linux-hardware.org/?probe=6cd85934b3) | Dec 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [7a1a444ed0](https://linux-hardware.org/?probe=7a1a444ed0) | Dec 15, 2023 |
| HP            | Laptop 15s-eq0xxx           | [cee2ad1e7c](https://linux-hardware.org/?probe=cee2ad1e7c) | Dec 15, 2023 |
| HP            | EliteBook 8530w             | [6ce01d863a](https://linux-hardware.org/?probe=6ce01d863a) | Dec 14, 2023 |
| Toshiba       | Satellite Pro C50-A-1C8     | [a56ec48040](https://linux-hardware.org/?probe=a56ec48040) | Dec 13, 2023 |
| Toshiba       | Satellite Pro C50-A-1C8     | [490ceeb636](https://linux-hardware.org/?probe=490ceeb636) | Dec 13, 2023 |
| HP            | Laptop 15-fd0xxx            | [cdcd6ddfc6](https://linux-hardware.org/?probe=cdcd6ddfc6) | Dec 13, 2023 |
| HP            | Laptop 15-fd0xxx            | [e6f39159ad](https://linux-hardware.org/?probe=e6f39159ad) | Dec 13, 2023 |
| Medion        | M14L-256                    | [b5e0624a7f](https://linux-hardware.org/?probe=b5e0624a7f) | Dec 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [af7be431fb](https://linux-hardware.org/?probe=af7be431fb) | Dec 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [d27df22c9a](https://linux-hardware.org/?probe=d27df22c9a) | Dec 11, 2023 |
| HP            | EliteBook 840 14 inch G1... | [17dd4245b8](https://linux-hardware.org/?probe=17dd4245b8) | Dec 11, 2023 |
| Lenovo        | ThinkPad T530 242922G       | [2b8062d3cc](https://linux-hardware.org/?probe=2b8062d3cc) | Dec 09, 2023 |
| Acer          | Aspire A515-45              | [ccc3f6589d](https://linux-hardware.org/?probe=ccc3f6589d) | Dec 07, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [e7fabdedad](https://linux-hardware.org/?probe=e7fabdedad) | Dec 07, 2023 |
| Lenovo        | Yoga Pro 7 14APH8 82Y8      | [3ffedf98eb](https://linux-hardware.org/?probe=3ffedf98eb) | Dec 07, 2023 |
| Dell          | Latitude E5440              | [56987fc258](https://linux-hardware.org/?probe=56987fc258) | Dec 06, 2023 |
| Dell          | Latitude E5440              | [6cdafbd9d1](https://linux-hardware.org/?probe=6cdafbd9d1) | Dec 06, 2023 |
| ASUSTek       | 1015PEM                     | [cbaedb564f](https://linux-hardware.org/?probe=cbaedb564f) | Dec 06, 2023 |
| Dell          | Inspiron 1545               | [d54ba07f49](https://linux-hardware.org/?probe=d54ba07f49) | Dec 06, 2023 |
| ASUSTek       | ROG Strix G634JZ_G634JZ     | [2ffb70a1ca](https://linux-hardware.org/?probe=2ffb70a1ca) | Dec 03, 2023 |
| Gigabyte      | AERO 15 KD                  | [58b6cdf11c](https://linux-hardware.org/?probe=58b6cdf11c) | Dec 02, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [d4a1f56f8d](https://linux-hardware.org/?probe=d4a1f56f8d) | Dec 01, 2023 |
| HP            | Pavilion Notebook           | [06fdc9d8e6](https://linux-hardware.org/?probe=06fdc9d8e6) | Dec 01, 2023 |
| Dell          | Inspiron 5570               | [6642e4462f](https://linux-hardware.org/?probe=6642e4462f) | Nov 30, 2023 |
| TUXEDO        | Book BA1510                 | [0c59322d62](https://linux-hardware.org/?probe=0c59322d62) | Nov 29, 2023 |
| Gigabyte      | AERO 15 KD                  | [772e5ce3f6](https://linux-hardware.org/?probe=772e5ce3f6) | Nov 29, 2023 |
| Dell          | Latitude 7490               | [70a7c438a1](https://linux-hardware.org/?probe=70a7c438a1) | Nov 27, 2023 |
| Lenovo        | Yoga Pro 7 14APH8 82Y8      | [2ca445207e](https://linux-hardware.org/?probe=2ca445207e) | Nov 26, 2023 |
| HP            | Laptop 15s-fq2xxx           | [aa4097f060](https://linux-hardware.org/?probe=aa4097f060) | Nov 24, 2023 |
| Valve         | Jupiter                     | [399542e5be](https://linux-hardware.org/?probe=399542e5be) | Nov 24, 2023 |
| Samsung       | 870Z5E/880Z5E/680Z5E        | [db22f8c316](https://linux-hardware.org/?probe=db22f8c316) | Nov 23, 2023 |
| Acer          | Nitro AN515-58              | [ca5e9fbf52](https://linux-hardware.org/?probe=ca5e9fbf52) | Nov 23, 2023 |
| Acer          | Nitro AN515-58              | [ab672024d6](https://linux-hardware.org/?probe=ab672024d6) | Nov 23, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [bf30102553](https://linux-hardware.org/?probe=bf30102553) | Nov 23, 2023 |
| ASUSTek       | X542URR                     | [7fb275b8f2](https://linux-hardware.org/?probe=7fb275b8f2) | Nov 22, 2023 |
| Samsung       | RC530/RC730                 | [8d328f4394](https://linux-hardware.org/?probe=8d328f4394) | Nov 21, 2023 |
| Toshiba       | Satellite P50-B-11V         | [448150c108](https://linux-hardware.org/?probe=448150c108) | Nov 21, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [ebfe063207](https://linux-hardware.org/?probe=ebfe063207) | Nov 19, 2023 |
| Timi          | TM1701                      | [f14bab873b](https://linux-hardware.org/?probe=f14bab873b) | Nov 18, 2023 |
| HP            | Laptop 15s-eq2xxx           | [f5414a4ffe](https://linux-hardware.org/?probe=f5414a4ffe) | Nov 18, 2023 |
| MSI           | Prestige 14Evo A12M         | [39c61d33cc](https://linux-hardware.org/?probe=39c61d33cc) | Nov 18, 2023 |
| Jumper        | EZbook                      | [5623f4ec87](https://linux-hardware.org/?probe=5623f4ec87) | Nov 15, 2023 |
| HP            | EliteBook 840 14 inch G1... | [f4d839670e](https://linux-hardware.org/?probe=f4d839670e) | Nov 13, 2023 |
| Dell          | Latitude 13                 | [4999e3eba9](https://linux-hardware.org/?probe=4999e3eba9) | Nov 09, 2023 |
| Dell          | Latitude 13                 | [acb0bd4f9d](https://linux-hardware.org/?probe=acb0bd4f9d) | Nov 09, 2023 |
| HP            | Dragonfly 13.5 inch G4 N... | [4f037eafa8](https://linux-hardware.org/?probe=4f037eafa8) | Nov 08, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | [216e0bed29](https://linux-hardware.org/?probe=216e0bed29) | Nov 07, 2023 |
| Apple         | MacBookPro11,4              | [45dfbee68a](https://linux-hardware.org/?probe=45dfbee68a) | Nov 05, 2023 |
| Notebook      | N141CU                      | [8f817eeabf](https://linux-hardware.org/?probe=8f817eeabf) | Nov 04, 2023 |
| POV           | I102A                       | [955f97d47e](https://linux-hardware.org/?probe=955f97d47e) | Nov 04, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [abe3da8a30](https://linux-hardware.org/?probe=abe3da8a30) | Nov 03, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [e7ccaf83d7](https://linux-hardware.org/?probe=e7ccaf83d7) | Nov 03, 2023 |
| Fujitsu       | LIFEBOOK S937               | [e4e8acb8db](https://linux-hardware.org/?probe=e4e8acb8db) | Nov 03, 2023 |
| Sony          | VGN-CS21S_R                 | [a7eb8de9f5](https://linux-hardware.org/?probe=a7eb8de9f5) | Nov 01, 2023 |
| Apple         | MacBookPro8,1               | [f1387b3bd9](https://linux-hardware.org/?probe=f1387b3bd9) | Nov 01, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [639a14d08d](https://linux-hardware.org/?probe=639a14d08d) | Nov 01, 2023 |
| ASUSTek       | X555LD                      | [2c79650ee2](https://linux-hardware.org/?probe=2c79650ee2) | Oct 29, 2023 |
| Dell          | Latitude E5400              | [169d73bee0](https://linux-hardware.org/?probe=169d73bee0) | Oct 28, 2023 |
| Clevo         | W240EL/W250ELQ/W270ELQ      | [cb44c39574](https://linux-hardware.org/?probe=cb44c39574) | Oct 27, 2023 |
| Lenovo        | ThinkPad P1 Gen 6 21FV00... | [3cf7c10977](https://linux-hardware.org/?probe=3cf7c10977) | Oct 25, 2023 |
| HP            | EliteBook 820 G2            | [d6d5273a5a](https://linux-hardware.org/?probe=d6d5273a5a) | Oct 25, 2023 |
| Dell          | Inspiron 11-3168            | [07fd1e8be9](https://linux-hardware.org/?probe=07fd1e8be9) | Oct 25, 2023 |
| Gigabyte      | G5 KC                       | [32743a624c](https://linux-hardware.org/?probe=32743a624c) | Oct 24, 2023 |
| Gigabyte      | G5 KC                       | [23d64978d9](https://linux-hardware.org/?probe=23d64978d9) | Oct 24, 2023 |
| Sony          | VGN-FZ21M                   | [ba7c93bcd4](https://linux-hardware.org/?probe=ba7c93bcd4) | Oct 21, 2023 |
| Toshiba       | Satellite Pro C50-A-1C8     | [801d54f088](https://linux-hardware.org/?probe=801d54f088) | Oct 21, 2023 |
| Toshiba       | Satellite Pro C50-A-1C8     | [69d0758d3d](https://linux-hardware.org/?probe=69d0758d3d) | Oct 19, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [2408be3605](https://linux-hardware.org/?probe=2408be3605) | Oct 16, 2023 |
| Gigabyte      | G7 GD                       | [667243780c](https://linux-hardware.org/?probe=667243780c) | Oct 15, 2023 |
| HP            | EliteBook 840 G2            | [3055b32637](https://linux-hardware.org/?probe=3055b32637) | Oct 15, 2023 |
| HP            | ZBook Studio G7 Mobile W... | [bd6f7ac948](https://linux-hardware.org/?probe=bd6f7ac948) | Oct 13, 2023 |
| Samsung       | 550XCJ/550XCR               | [3b06edb6bf](https://linux-hardware.org/?probe=3b06edb6bf) | Oct 13, 2023 |
| Lenovo        | Yoga Pro 7 14APH8 82Y8      | [adad0100ea](https://linux-hardware.org/?probe=adad0100ea) | Oct 13, 2023 |
| Lenovo        | ThinkPad X250 20CM0048US    | [cf66338531](https://linux-hardware.org/?probe=cf66338531) | Oct 13, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [20b1614237](https://linux-hardware.org/?probe=20b1614237) | Oct 12, 2023 |
| HP            | ProBook 455 15.6 inch G1... | [cc3dbe7ccd](https://linux-hardware.org/?probe=cc3dbe7ccd) | Oct 12, 2023 |
| HP            | ProBook 455 15.6 inch G1... | [8c1ef64452](https://linux-hardware.org/?probe=8c1ef64452) | Oct 12, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [d5040f4ca4](https://linux-hardware.org/?probe=d5040f4ca4) | Oct 12, 2023 |
| MSI           | Prestige 16Studio A13VE     | [0209063983](https://linux-hardware.org/?probe=0209063983) | Oct 12, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [c715105687](https://linux-hardware.org/?probe=c715105687) | Oct 10, 2023 |
| ASUSTek       | K52JB                       | [a2a5c14c8a](https://linux-hardware.org/?probe=a2a5c14c8a) | Oct 09, 2023 |
| MSI           | Summit E16Flip A12UCT       | [882d0daf54](https://linux-hardware.org/?probe=882d0daf54) | Oct 09, 2023 |
| ASUSTek       | K52JB                       | [b3fd22ad8e](https://linux-hardware.org/?probe=b3fd22ad8e) | Oct 08, 2023 |
| HP            | Pavilion 15                 | [ae1e07dd63](https://linux-hardware.org/?probe=ae1e07dd63) | Oct 08, 2023 |
| Dell          | XPS 15 9500                 | [ee251b10d4](https://linux-hardware.org/?probe=ee251b10d4) | Oct 07, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | [08aa11c398](https://linux-hardware.org/?probe=08aa11c398) | Oct 05, 2023 |
| HP            | Laptop 15-db0xxx            | [9b841951f2](https://linux-hardware.org/?probe=9b841951f2) | Oct 05, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [8ba8fa3184](https://linux-hardware.org/?probe=8ba8fa3184) | Oct 05, 2023 |
| HP            | EliteBook 840 G2            | [a90e584705](https://linux-hardware.org/?probe=a90e584705) | Oct 04, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [bf9ddbe725](https://linux-hardware.org/?probe=bf9ddbe725) | Oct 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | [3a8b2b229a](https://linux-hardware.org/?probe=3a8b2b229a) | Oct 03, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [b0b5262c87](https://linux-hardware.org/?probe=b0b5262c87) | Oct 02, 2023 |
| MSI           | GF65 Thin 9SEXR             | [1d315fb87d](https://linux-hardware.org/?probe=1d315fb87d) | Oct 02, 2023 |
| Lenovo        | Yoga Pro 7 14APH8 82Y8      | [d929b857db](https://linux-hardware.org/?probe=d929b857db) | Oct 01, 2023 |
| ASUSTek       | F7SR                        | [b895fd8bb2](https://linux-hardware.org/?probe=b895fd8bb2) | Sep 30, 2023 |
| ASUSTek       | F7SR                        | [1b7493ae6e](https://linux-hardware.org/?probe=1b7493ae6e) | Sep 30, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [b6acaf4c61](https://linux-hardware.org/?probe=b6acaf4c61) | Sep 27, 2023 |
| ASUSTek       | K52JB                       | [7524eea19f](https://linux-hardware.org/?probe=7524eea19f) | Sep 26, 2023 |
| HP            | G62                         | [50fef7b3fa](https://linux-hardware.org/?probe=50fef7b3fa) | Sep 26, 2023 |
| Samsung       | 300E5M/300E5L               | [1df46b6215](https://linux-hardware.org/?probe=1df46b6215) | Sep 25, 2023 |
| Samsung       | 300E5M/300E5L               | [1d90b7b714](https://linux-hardware.org/?probe=1d90b7b714) | Sep 25, 2023 |
| ASUSTek       | K55VM                       | [3dd45a6297](https://linux-hardware.org/?probe=3dd45a6297) | Sep 24, 2023 |
| Notebook      | P7xxTM                      | [e14cfa2f1f](https://linux-hardware.org/?probe=e14cfa2f1f) | Sep 22, 2023 |
| Notebook      | P7xxTM                      | [41b1348520](https://linux-hardware.org/?probe=41b1348520) | Sep 22, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [98ab1e6859](https://linux-hardware.org/?probe=98ab1e6859) | Sep 21, 2023 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | [7377101d6d](https://linux-hardware.org/?probe=7377101d6d) | Sep 20, 2023 |
| HP            | Laptop 15-bs0xx             | [963330511d](https://linux-hardware.org/?probe=963330511d) | Sep 19, 2023 |
| HP            | Laptop 15-bs0xx             | [5f8df7dfcb](https://linux-hardware.org/?probe=5f8df7dfcb) | Sep 19, 2023 |
| HP            | Laptop 15-fc0xxx            | [50c2f9349d](https://linux-hardware.org/?probe=50c2f9349d) | Sep 18, 2023 |
| MSI           | PS42 8RB                    | [2fa07ede2a](https://linux-hardware.org/?probe=2fa07ede2a) | Sep 16, 2023 |
| PC Special... | P7xxTM1                     | [2bdbc2f2e7](https://linux-hardware.org/?probe=2bdbc2f2e7) | Sep 12, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [03e666ab42](https://linux-hardware.org/?probe=03e666ab42) | Sep 12, 2023 |
| ASUSTek       | GL553VW                     | [3859055e8d](https://linux-hardware.org/?probe=3859055e8d) | Sep 11, 2023 |
| Lenovo        | ThinkPad T480s 20L8S6RF0... | [6c62d111db](https://linux-hardware.org/?probe=6c62d111db) | Sep 10, 2023 |
| Acer          | Aspire 5742G                | [8dc4477486](https://linux-hardware.org/?probe=8dc4477486) | Sep 10, 2023 |
| Acer          | Aspire 5742G                | [e737851117](https://linux-hardware.org/?probe=e737851117) | Sep 10, 2023 |
| Dell          | Inspiron 11-3168            | [57ef365bf9](https://linux-hardware.org/?probe=57ef365bf9) | Sep 10, 2023 |
| Dell          | Latitude E7240              | [79a666783a](https://linux-hardware.org/?probe=79a666783a) | Sep 07, 2023 |
| Lenovo        | ThinkPad P1 Gen 6 21FV00... | [c9a07c44d5](https://linux-hardware.org/?probe=c9a07c44d5) | Sep 06, 2023 |
| HP            | mt40                        | [c3a4682e40](https://linux-hardware.org/?probe=c3a4682e40) | Sep 04, 2023 |
| Lenovo        | ThinkPad SL510 28473QB      | [e1ff8baa87](https://linux-hardware.org/?probe=e1ff8baa87) | Sep 04, 2023 |
| ASUSTek       | X555LJ                      | [c13b1a693d](https://linux-hardware.org/?probe=c13b1a693d) | Sep 03, 2023 |
| Acer          | Aspire A515-57              | [1e01a32799](https://linux-hardware.org/?probe=1e01a32799) | Sep 01, 2023 |
| Lenovo        | ThinkPad T440p 20AWS1BL0... | [f1e1512fc9](https://linux-hardware.org/?probe=f1e1512fc9) | Sep 01, 2023 |
| Apple         | MacBookPro11,1              | [b3caa97382](https://linux-hardware.org/?probe=b3caa97382) | Aug 30, 2023 |
| Lenovo        | 3000 G410                   | [26c592ddd6](https://linux-hardware.org/?probe=26c592ddd6) | Aug 29, 2023 |
| HP            | Laptop 15s-eq1xxx           | [fe431ea565](https://linux-hardware.org/?probe=fe431ea565) | Aug 29, 2023 |
| HUAWEI        | KLVL-WXXW                   | [5e7257145a](https://linux-hardware.org/?probe=5e7257145a) | Aug 26, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [627068909d](https://linux-hardware.org/?probe=627068909d) | Aug 25, 2023 |
| HP            | 15                          | [76decc7899](https://linux-hardware.org/?probe=76decc7899) | Aug 25, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [7e6a7de337](https://linux-hardware.org/?probe=7e6a7de337) | Aug 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | [e0a5f63a8b](https://linux-hardware.org/?probe=e0a5f63a8b) | Aug 22, 2023 |
| Acer          | Aspire ES1-520              | [99cdeba16c](https://linux-hardware.org/?probe=99cdeba16c) | Aug 20, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [a665e45380](https://linux-hardware.org/?probe=a665e45380) | Aug 19, 2023 |
| Sony          | VPCF13Z1E                   | [98c9e71be9](https://linux-hardware.org/?probe=98c9e71be9) | Aug 19, 2023 |
| Samsung       | 530U3C/530U4C/532U3C        | [b5e6b20270](https://linux-hardware.org/?probe=b5e6b20270) | Aug 18, 2023 |
| Chuwi         | GemiBook XPro               | [41b34e60fd](https://linux-hardware.org/?probe=41b34e60fd) | Aug 18, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [82c579f8a7](https://linux-hardware.org/?probe=82c579f8a7) | Aug 16, 2023 |
| HP            | Pavilion dv6                | [ee8c1f96e8](https://linux-hardware.org/?probe=ee8c1f96e8) | Aug 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [7050972395](https://linux-hardware.org/?probe=7050972395) | Aug 16, 2023 |
| HP            | Laptop 15s-eq2xxx           | [c2cfa9bd7a](https://linux-hardware.org/?probe=c2cfa9bd7a) | Aug 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | [67a1535765](https://linux-hardware.org/?probe=67a1535765) | Aug 15, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [823e276406](https://linux-hardware.org/?probe=823e276406) | Aug 13, 2023 |
| LNV           | L40-70                      | [66fe107447](https://linux-hardware.org/?probe=66fe107447) | Aug 11, 2023 |
| HP            | 250 G3                      | [512fd5d81f](https://linux-hardware.org/?probe=512fd5d81f) | Aug 10, 2023 |
| HP            | Notebook                    | [02ceb78a4f](https://linux-hardware.org/?probe=02ceb78a4f) | Aug 07, 2023 |
| Medion        | M14L-256                    | [7d0a8921dc](https://linux-hardware.org/?probe=7d0a8921dc) | Aug 07, 2023 |
| Apple         | MacBook7,1                  | [38d285144e](https://linux-hardware.org/?probe=38d285144e) | Aug 06, 2023 |
| Teclast       | F7S                         | [a844443394](https://linux-hardware.org/?probe=a844443394) | Aug 06, 2023 |
| Unknown       | Unknown                     | [9431f6f4e8](https://linux-hardware.org/?probe=9431f6f4e8) | Aug 06, 2023 |
| Teclast       | F7S                         | [71ab18cda5](https://linux-hardware.org/?probe=71ab18cda5) | Aug 05, 2023 |
| HUAWEI        | RLEF-XX                     | [5b0c2b27e7](https://linux-hardware.org/?probe=5b0c2b27e7) | Aug 04, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [2825bbd67b](https://linux-hardware.org/?probe=2825bbd67b) | Aug 04, 2023 |
| ASUSTek       | UX430UNR                    | [89c8324528](https://linux-hardware.org/?probe=89c8324528) | Aug 01, 2023 |
| Sony          | VPCF13Z1E                   | [e52969e6a8](https://linux-hardware.org/?probe=e52969e6a8) | Jul 30, 2023 |
| Lenovo        | G50-45 80E3                 | [002504b8be](https://linux-hardware.org/?probe=002504b8be) | Jul 29, 2023 |
| HP            | Laptop 15-fc0xxx            | [30dabbbc28](https://linux-hardware.org/?probe=30dabbbc28) | Jul 28, 2023 |
| HP            | EliteBook 840 G3            | [5a1f6f3395](https://linux-hardware.org/?probe=5a1f6f3395) | Jul 27, 2023 |
| Sony          | VPCF13Z1E                   | [5022f7359c](https://linux-hardware.org/?probe=5022f7359c) | Jul 26, 2023 |
| Sony          | VPCF13Z1E                   | [f5290b8791](https://linux-hardware.org/?probe=f5290b8791) | Jul 25, 2023 |
| Sony          | VPCF13Z1E                   | [99aacf2d95](https://linux-hardware.org/?probe=99aacf2d95) | Jul 25, 2023 |
| MSI           | Summit E16Flip A12UCT       | [daf09efe6e](https://linux-hardware.org/?probe=daf09efe6e) | Jul 24, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [c1e386e9cc](https://linux-hardware.org/?probe=c1e386e9cc) | Jul 22, 2023 |
| Acer          | Extensa 5635ZG              | [337f0cec05](https://linux-hardware.org/?probe=337f0cec05) | Jul 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [069bfd995c](https://linux-hardware.org/?probe=069bfd995c) | Jul 15, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | [7d2f78f0d3](https://linux-hardware.org/?probe=7d2f78f0d3) | Jul 15, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [20e49aa241](https://linux-hardware.org/?probe=20e49aa241) | Jul 14, 2023 |
| HP            | Pavilion dv3                | [94eeea2364](https://linux-hardware.org/?probe=94eeea2364) | Jul 12, 2023 |
| HP            | EliteBook 645 14 inch G9... | [65f4b4e813](https://linux-hardware.org/?probe=65f4b4e813) | Jul 11, 2023 |
| HP            | EliteBook 840 G6            | [a61e80c022](https://linux-hardware.org/?probe=a61e80c022) | Jul 11, 2023 |
| Dell          | Latitude E5500              | [03798c7840](https://linux-hardware.org/?probe=03798c7840) | Jul 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [50f23f3476](https://linux-hardware.org/?probe=50f23f3476) | Jul 09, 2023 |
| Dell          | XPS 13 9350                 | [9fc07d1102](https://linux-hardware.org/?probe=9fc07d1102) | Jul 08, 2023 |
| HP            | 350 G1                      | [d965c2785d](https://linux-hardware.org/?probe=d965c2785d) | Jul 04, 2023 |
| HP            | 350 G1                      | [bb742c9ffb](https://linux-hardware.org/?probe=bb742c9ffb) | Jul 04, 2023 |
| Acer          | Aspire 5737Z                | [842aa57faf](https://linux-hardware.org/?probe=842aa57faf) | Jun 30, 2023 |
| ASUSTek       | K56CB                       | [952909bc80](https://linux-hardware.org/?probe=952909bc80) | Jun 29, 2023 |
| MSI           | PS63 Modern 8SC             | [dcbb8108cf](https://linux-hardware.org/?probe=dcbb8108cf) | Jun 29, 2023 |
| Lenovo        | ThinkPad T430 2349OB6       | [f2f66bb9d0](https://linux-hardware.org/?probe=f2f66bb9d0) | Jun 29, 2023 |
| Toshiba       | Satellite X200              | [4a3e7008cf](https://linux-hardware.org/?probe=4a3e7008cf) | Jun 28, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [c05a780b64](https://linux-hardware.org/?probe=c05a780b64) | Jun 27, 2023 |
| Gigabyte      | AERO 15 KD                  | [1a17b8ee06](https://linux-hardware.org/?probe=1a17b8ee06) | Jun 26, 2023 |
| Gigabyte      | AERO 15 KD                  | [2fd779cefc](https://linux-hardware.org/?probe=2fd779cefc) | Jun 26, 2023 |
| Dell          | XPS 9315                    | [41bb8bd332](https://linux-hardware.org/?probe=41bb8bd332) | Jun 25, 2023 |
| HP            | EliteBook 840 G5            | [4ad837baa7](https://linux-hardware.org/?probe=4ad837baa7) | Jun 24, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [fe084d5ddb](https://linux-hardware.org/?probe=fe084d5ddb) | Jun 24, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [4b866ca19f](https://linux-hardware.org/?probe=4b866ca19f) | Jun 22, 2023 |
| HP            | Dragonfly 13.5 inch G4 N... | [22c2768f76](https://linux-hardware.org/?probe=22c2768f76) | Jun 22, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [f93c91b6d9](https://linux-hardware.org/?probe=f93c91b6d9) | Jun 18, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [2f19a23a54](https://linux-hardware.org/?probe=2f19a23a54) | Jun 17, 2023 |
| Acer          | Aspire ES1-520              | [3d8b5e9564](https://linux-hardware.org/?probe=3d8b5e9564) | Jun 17, 2023 |
| Acer          | Aspire ES1-520              | [fb8da18b42](https://linux-hardware.org/?probe=fb8da18b42) | Jun 17, 2023 |
| Dell          | Latitude E5400              | [f5d066d8fc](https://linux-hardware.org/?probe=f5d066d8fc) | Jun 16, 2023 |
| Toshiba       | Satellite X200              | [d57a63387d](https://linux-hardware.org/?probe=d57a63387d) | Jun 15, 2023 |
| Toshiba       | Satellite L650              | [d92c0dea02](https://linux-hardware.org/?probe=d92c0dea02) | Jun 14, 2023 |
| Sony          | SVF1521J7EW                 | [2d04d992c2](https://linux-hardware.org/?probe=2d04d992c2) | Jun 10, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [8632ddc565](https://linux-hardware.org/?probe=8632ddc565) | Jun 09, 2023 |
| Chuwi         | GemiBook Pro                | [83adb0e53a](https://linux-hardware.org/?probe=83adb0e53a) | Jun 07, 2023 |
| Lenovo        | ThinkPad T440p              | [d46387134e](https://linux-hardware.org/?probe=d46387134e) | Jun 07, 2023 |
| Chuwi         | GemiBook Pro                | [1378fdec29](https://linux-hardware.org/?probe=1378fdec29) | Jun 07, 2023 |
| Lenovo        | ThinkPad T440p              | [c058d92130](https://linux-hardware.org/?probe=c058d92130) | Jun 05, 2023 |
| ASUSTek       | N56VB                       | [f47c68a2a7](https://linux-hardware.org/?probe=f47c68a2a7) | Jun 04, 2023 |
| Apple         | MacBookPro9,2               | [6964a1da79](https://linux-hardware.org/?probe=6964a1da79) | Jun 03, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | [767241151a](https://linux-hardware.org/?probe=767241151a) | Jun 03, 2023 |
| Dell          | Latitude 5491               | [6a8a7e6188](https://linux-hardware.org/?probe=6a8a7e6188) | Jun 03, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [3de77b392a](https://linux-hardware.org/?probe=3de77b392a) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [109dbbfff0](https://linux-hardware.org/?probe=109dbbfff0) | Jun 02, 2023 |
| HP            | Unknown                     | [626075d6f2](https://linux-hardware.org/?probe=626075d6f2) | Jun 02, 2023 |
| HP            | Unknown                     | [2289bb8d24](https://linux-hardware.org/?probe=2289bb8d24) | Jun 02, 2023 |
| HP            | Laptop 15s-eq2xxx           | [302ae0e2dc](https://linux-hardware.org/?probe=302ae0e2dc) | Jun 02, 2023 |
| Chuwi         | GemiBook Pro                | [f17ebfac4b](https://linux-hardware.org/?probe=f17ebfac4b) | May 31, 2023 |
| HP            | Unknown                     | [3eb658702b](https://linux-hardware.org/?probe=3eb658702b) | May 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [93ac1fb021](https://linux-hardware.org/?probe=93ac1fb021) | May 31, 2023 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | [5881fb6ae2](https://linux-hardware.org/?probe=5881fb6ae2) | May 30, 2023 |
| HP            | Unknown                     | [2007104aeb](https://linux-hardware.org/?probe=2007104aeb) | May 30, 2023 |
| Lenovo        | ThinkPad E490 20N8000RPG    | [73b8bfb3a5](https://linux-hardware.org/?probe=73b8bfb3a5) | May 29, 2023 |
| Lenovo        | ThinkPad X230 23301E0       | [84781c068a](https://linux-hardware.org/?probe=84781c068a) | May 29, 2023 |
| Lenovo        | ThinkPad X230 23301E0       | [97f0880258](https://linux-hardware.org/?probe=97f0880258) | May 29, 2023 |
| Chuwi         | GemiBook Pro                | [5684d2005d](https://linux-hardware.org/?probe=5684d2005d) | May 28, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [462ae1c4f5](https://linux-hardware.org/?probe=462ae1c4f5) | May 28, 2023 |
| HP            | 15                          | [f5373f2397](https://linux-hardware.org/?probe=f5373f2397) | May 27, 2023 |
| HP            | 15                          | [f30c3b3a95](https://linux-hardware.org/?probe=f30c3b3a95) | May 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [0f3f548ff0](https://linux-hardware.org/?probe=0f3f548ff0) | May 27, 2023 |
| Sony          | VGN-FZ31Z                   | [31c6913c14](https://linux-hardware.org/?probe=31c6913c14) | May 26, 2023 |
| ASUSTek       | K55VJ                       | [66c9773a5f](https://linux-hardware.org/?probe=66c9773a5f) | May 26, 2023 |
| ASUSTek       | K55VJ                       | [65cc5e45b0](https://linux-hardware.org/?probe=65cc5e45b0) | May 26, 2023 |
| Chuwi         | GemiBook Pro                | [ac87b1945b](https://linux-hardware.org/?probe=ac87b1945b) | May 26, 2023 |
| ASUSTek       | GL702ZC                     | [c60d7fabbb](https://linux-hardware.org/?probe=c60d7fabbb) | May 25, 2023 |
| Acer          | Nitro AN515-52              | [b5a283de1d](https://linux-hardware.org/?probe=b5a283de1d) | May 25, 2023 |
| Acer          | Nitro AN515-52              | [0a65452634](https://linux-hardware.org/?probe=0a65452634) | May 24, 2023 |
| ASUSTek       | GL702ZC                     | [9764417bf8](https://linux-hardware.org/?probe=9764417bf8) | May 24, 2023 |
| HP            | Victus by Laptop 16-d1xx... | [d03d942df4](https://linux-hardware.org/?probe=d03d942df4) | May 24, 2023 |
| Dell          | XPS 15 9500                 | [4c512786cc](https://linux-hardware.org/?probe=4c512786cc) | May 24, 2023 |
| Dell          | XPS 15 9500                 | [da0b980bc3](https://linux-hardware.org/?probe=da0b980bc3) | May 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [0aba7a98b9](https://linux-hardware.org/?probe=0aba7a98b9) | May 24, 2023 |
| HP            | ENVY Laptop 13-ba1xxx       | [a11fdd0361](https://linux-hardware.org/?probe=a11fdd0361) | May 23, 2023 |
| ASUSTek       | N56VB                       | [0e982abd6b](https://linux-hardware.org/?probe=0e982abd6b) | May 22, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [d1c4b3ee44](https://linux-hardware.org/?probe=d1c4b3ee44) | May 22, 2023 |
| Acer          | Nitro AN515-52              | [f250413f11](https://linux-hardware.org/?probe=f250413f11) | May 21, 2023 |
| HP            | EliteBook 820 G2            | [23fb35880e](https://linux-hardware.org/?probe=23fb35880e) | May 21, 2023 |
| HP            | EliteBook 820 G2            | [d52da23326](https://linux-hardware.org/?probe=d52da23326) | May 21, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | [6bef224193](https://linux-hardware.org/?probe=6bef224193) | May 20, 2023 |
| HP            | Unknown                     | [8ae91264ca](https://linux-hardware.org/?probe=8ae91264ca) | May 19, 2023 |
| HP            | Pavilion Notebook           | [73d62695e4](https://linux-hardware.org/?probe=73d62695e4) | May 18, 2023 |
| Acer          | Aspire E5-521               | [05227be8bc](https://linux-hardware.org/?probe=05227be8bc) | May 18, 2023 |
| HP            | Pavilion Notebook           | [56aa17165e](https://linux-hardware.org/?probe=56aa17165e) | May 18, 2023 |
| Lenovo        | ThinkPad X61 7673V4Q        | [7df5747f30](https://linux-hardware.org/?probe=7df5747f30) | May 18, 2023 |
| HUAWEI        | KLVL-WXXW                   | [72b5dfc390](https://linux-hardware.org/?probe=72b5dfc390) | May 15, 2023 |
| Lenovo        | ThinkPad X230 23301E0       | [681e1f8c61](https://linux-hardware.org/?probe=681e1f8c61) | May 15, 2023 |
| HUAWEI        | KLVL-WXXW                   | [d7e4640b82](https://linux-hardware.org/?probe=d7e4640b82) | May 15, 2023 |
| ASUSTek       | X541UJ                      | [9be042ca8a](https://linux-hardware.org/?probe=9be042ca8a) | May 14, 2023 |
| ASUSTek       | N56VB                       | [87d2f8b907](https://linux-hardware.org/?probe=87d2f8b907) | May 14, 2023 |
| ASUSTek       | N56VB                       | [7e2caae7ea](https://linux-hardware.org/?probe=7e2caae7ea) | May 14, 2023 |
| Valve         | Jupiter                     | [9a9b88a86c](https://linux-hardware.org/?probe=9a9b88a86c) | May 14, 2023 |
| Apple         | MacBookPro11,2              | [a2199ee2c6](https://linux-hardware.org/?probe=a2199ee2c6) | May 13, 2023 |
| Lenovo        | ThinkPad X230 23301E0       | [9a5e07f865](https://linux-hardware.org/?probe=9a5e07f865) | May 13, 2023 |
| Lenovo        | ThinkPad X61 7673V4Q        | [38acb76489](https://linux-hardware.org/?probe=38acb76489) | May 11, 2023 |
| HP            | G62                         | [68f5984aa8](https://linux-hardware.org/?probe=68f5984aa8) | May 11, 2023 |
| Dell          | Latitude 5420               | [a3c2a7c9bf](https://linux-hardware.org/?probe=a3c2a7c9bf) | May 11, 2023 |
| Sony          | VGN-FZ31Z                   | [6fe358200a](https://linux-hardware.org/?probe=6fe358200a) | May 09, 2023 |
| Lenovo        | G50-70 20351                | [70c3231200](https://linux-hardware.org/?probe=70c3231200) | May 07, 2023 |
| Notebook      | N141CU                      | [535b4ca746](https://linux-hardware.org/?probe=535b4ca746) | May 07, 2023 |
| Acer          | Aspire E5-523G              | [7a77c66c97](https://linux-hardware.org/?probe=7a77c66c97) | May 06, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [678b4ca4ed](https://linux-hardware.org/?probe=678b4ca4ed) | May 06, 2023 |
| Valve         | Jupiter                     | [04f1f6146c](https://linux-hardware.org/?probe=04f1f6146c) | May 04, 2023 |
| Dell          | Precision 5540              | [3139d97ce0](https://linux-hardware.org/?probe=3139d97ce0) | May 04, 2023 |
| Toshiba       | PORTEGE Z830                | [a8cc4a63c2](https://linux-hardware.org/?probe=a8cc4a63c2) | May 03, 2023 |
| HP            | Unknown                     | [4d0dc62d87](https://linux-hardware.org/?probe=4d0dc62d87) | May 03, 2023 |
| HP            | Unknown                     | [95bbd82535](https://linux-hardware.org/?probe=95bbd82535) | May 03, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [f3e8baa565](https://linux-hardware.org/?probe=f3e8baa565) | May 01, 2023 |
| HUAWEI        | RLEF-XX                     | [168396ff77](https://linux-hardware.org/?probe=168396ff77) | May 01, 2023 |
| HUAWEI        | RLEF-XX                     | [b7ca4beb49](https://linux-hardware.org/?probe=b7ca4beb49) | Apr 30, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | [d4cfc1e964](https://linux-hardware.org/?probe=d4cfc1e964) | Apr 30, 2023 |
| ASUSTek       | X542URR                     | [910cdd940c](https://linux-hardware.org/?probe=910cdd940c) | Apr 28, 2023 |
| Lenovo        | G50-70 20351                | [a808e47839](https://linux-hardware.org/?probe=a808e47839) | Apr 28, 2023 |
| Lenovo        | G50-70 20351                | [67ae1efc54](https://linux-hardware.org/?probe=67ae1efc54) | Apr 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [3a6e27c6ce](https://linux-hardware.org/?probe=3a6e27c6ce) | Apr 26, 2023 |
| Dell          | Inspiron 5521               | [8de2e801a3](https://linux-hardware.org/?probe=8de2e801a3) | Apr 23, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [1fc445ac89](https://linux-hardware.org/?probe=1fc445ac89) | Apr 22, 2023 |
| HP            | EliteBook 850 G5            | [ba9bbe1e70](https://linux-hardware.org/?probe=ba9bbe1e70) | Apr 21, 2023 |
| Dell          | Precision 5540              | [66b58fad6c](https://linux-hardware.org/?probe=66b58fad6c) | Apr 19, 2023 |
| Dell          | Precision 5540              | [e114fb911c](https://linux-hardware.org/?probe=e114fb911c) | Apr 19, 2023 |
| Lenovo        | ThinkBook 15-IML 20RW       | [b4c6c1198f](https://linux-hardware.org/?probe=b4c6c1198f) | Apr 19, 2023 |
| ASUSTek       | X541UJ                      | [1aa63436a5](https://linux-hardware.org/?probe=1aa63436a5) | Apr 19, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [a2b27dd2d6](https://linux-hardware.org/?probe=a2b27dd2d6) | Apr 17, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [14517ef743](https://linux-hardware.org/?probe=14517ef743) | Apr 17, 2023 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | [1280936eba](https://linux-hardware.org/?probe=1280936eba) | Apr 13, 2023 |
| Fujitsu       | LIFEBOOK U7411              | [b054f2bcd1](https://linux-hardware.org/?probe=b054f2bcd1) | Apr 12, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [238037e4b8](https://linux-hardware.org/?probe=238037e4b8) | Apr 11, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | [69f8d7dfdf](https://linux-hardware.org/?probe=69f8d7dfdf) | Apr 11, 2023 |
| Chuwi         | GemiBook Pro                | [e0f6223c25](https://linux-hardware.org/?probe=e0f6223c25) | Apr 10, 2023 |
| Chuwi         | GemiBook Pro                | [cb009d5401](https://linux-hardware.org/?probe=cb009d5401) | Apr 10, 2023 |
| Chuwi         | GemiBook Pro                | [617f2a18bb](https://linux-hardware.org/?probe=617f2a18bb) | Apr 09, 2023 |
| Chuwi         | GemiBook Pro                | [5ff7c0183d](https://linux-hardware.org/?probe=5ff7c0183d) | Apr 07, 2023 |
| Fujitsu       | LIFEBOOK E751               | [0bdc444de8](https://linux-hardware.org/?probe=0bdc444de8) | Apr 05, 2023 |
| Dell          | Latitude 5430               | [6494113c9b](https://linux-hardware.org/?probe=6494113c9b) | Apr 04, 2023 |
| ASUSTek       | TUF Gaming FX705DY_TUF70... | [85e0077c83](https://linux-hardware.org/?probe=85e0077c83) | Apr 03, 2023 |
| HP            | Stream Laptop 14-ax0XX      | [aead33a5e6](https://linux-hardware.org/?probe=aead33a5e6) | Apr 01, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | [1da5570114](https://linux-hardware.org/?probe=1da5570114) | Apr 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [a1fa08efc6](https://linux-hardware.org/?probe=a1fa08efc6) | Mar 30, 2023 |
| HUAWEI        | RLEF-XX                     | [e9988edacd](https://linux-hardware.org/?probe=e9988edacd) | Mar 30, 2023 |
| Dell          | Latitude 7430               | [fdef205301](https://linux-hardware.org/?probe=fdef205301) | Mar 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [ebf2728d28](https://linux-hardware.org/?probe=ebf2728d28) | Mar 29, 2023 |
| Acer          | Nitro AN515-45              | [0aabfe954d](https://linux-hardware.org/?probe=0aabfe954d) | Mar 28, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | [b7a0579d38](https://linux-hardware.org/?probe=b7a0579d38) | Mar 28, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | [88d5c3bb9f](https://linux-hardware.org/?probe=88d5c3bb9f) | Mar 28, 2023 |
| HUAWEI        | BOHB-WAX9                   | [d7b0ec58d5](https://linux-hardware.org/?probe=d7b0ec58d5) | Mar 27, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [701b74ce3e](https://linux-hardware.org/?probe=701b74ce3e) | Mar 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [537fc6af0e](https://linux-hardware.org/?probe=537fc6af0e) | Mar 26, 2023 |
| Lenovo        | IP 5-14ALC05 82LM           | [5bacaa401a](https://linux-hardware.org/?probe=5bacaa401a) | Mar 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [7fb78c1c79](https://linux-hardware.org/?probe=7fb78c1c79) | Mar 20, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [f13da06079](https://linux-hardware.org/?probe=f13da06079) | Mar 15, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [e7dd32b931](https://linux-hardware.org/?probe=e7dd32b931) | Mar 15, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [557a08d242](https://linux-hardware.org/?probe=557a08d242) | Mar 15, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [48370f2817](https://linux-hardware.org/?probe=48370f2817) | Mar 14, 2023 |
| Toshiba       | Satellite P300              | [1872bc8b57](https://linux-hardware.org/?probe=1872bc8b57) | Mar 14, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [59d2c50a02](https://linux-hardware.org/?probe=59d2c50a02) | Mar 14, 2023 |
| ASUSTek       | X202EV                      | [db21e9ac28](https://linux-hardware.org/?probe=db21e9ac28) | Mar 13, 2023 |
| HP            | ENVY Notebook               | [8a063efa19](https://linux-hardware.org/?probe=8a063efa19) | Mar 09, 2023 |
| MSI           | GF65 Thin 9SD               | [ea69b96e55](https://linux-hardware.org/?probe=ea69b96e55) | Mar 09, 2023 |
| Dell          | Latitude E4310              | [8dbe3e01fa](https://linux-hardware.org/?probe=8dbe3e01fa) | Mar 08, 2023 |
| Lenovo        | ThinkPad T470 20HD0001PG    | [be61e16d11](https://linux-hardware.org/?probe=be61e16d11) | Mar 08, 2023 |
| Dell          | Latitude E5570              | [5a5d668611](https://linux-hardware.org/?probe=5a5d668611) | Mar 07, 2023 |
| MSI           | GF72 8RD                    | [54eb266d2a](https://linux-hardware.org/?probe=54eb266d2a) | Mar 04, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C30... | [1fb81359e0](https://linux-hardware.org/?probe=1fb81359e0) | Mar 03, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [5715b4e8af](https://linux-hardware.org/?probe=5715b4e8af) | Mar 03, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [26b308e28a](https://linux-hardware.org/?probe=26b308e28a) | Mar 02, 2023 |
| HUAWEI        | BOHB-WAX9                   | [73c765dbe2](https://linux-hardware.org/?probe=73c765dbe2) | Mar 01, 2023 |
| Lenovo        | ThinkPad T480 20L6SEH700    | [4a187e016b](https://linux-hardware.org/?probe=4a187e016b) | Feb 27, 2023 |
| HP            | Compaq 6730b (FU594ES#AB... | [810cdb1ad1](https://linux-hardware.org/?probe=810cdb1ad1) | Feb 26, 2023 |
| Lenovo        | ThinkPad T480 20L5S03600    | [5c9736ab0c](https://linux-hardware.org/?probe=5c9736ab0c) | Feb 25, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | [7b59cbd067](https://linux-hardware.org/?probe=7b59cbd067) | Feb 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [d99e163be6](https://linux-hardware.org/?probe=d99e163be6) | Feb 24, 2023 |
| HP            | mt40                        | [16e5f8eb5d](https://linux-hardware.org/?probe=16e5f8eb5d) | Feb 23, 2023 |
| MSI           | GF72 8RD                    | [cf6dad63da](https://linux-hardware.org/?probe=cf6dad63da) | Feb 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [022527aa4c](https://linux-hardware.org/?probe=022527aa4c) | Feb 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [3b1afb00a2](https://linux-hardware.org/?probe=3b1afb00a2) | Feb 21, 2023 |
| HUAWEI        | BOHB-WAX9                   | [387aa81d4c](https://linux-hardware.org/?probe=387aa81d4c) | Feb 18, 2023 |
| HUAWEI        | BOHB-WAX9                   | [ebaa8145e1](https://linux-hardware.org/?probe=ebaa8145e1) | Feb 18, 2023 |
| HUAWEI        | BOD-WXX9                    | [a56a788adf](https://linux-hardware.org/?probe=a56a788adf) | Feb 17, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [bb1c4209c7](https://linux-hardware.org/?probe=bb1c4209c7) | Feb 17, 2023 |
| HP            | Laptop 15-bs1xx             | [88d9514231](https://linux-hardware.org/?probe=88d9514231) | Feb 17, 2023 |
| HP            | Stream Laptop 14-ax0XX      | [42b7f88059](https://linux-hardware.org/?probe=42b7f88059) | Feb 16, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [ef69c22820](https://linux-hardware.org/?probe=ef69c22820) | Feb 16, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [4e6c625797](https://linux-hardware.org/?probe=4e6c625797) | Feb 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [c2d957f650](https://linux-hardware.org/?probe=c2d957f650) | Feb 15, 2023 |
| Toshiba       | Satellite L500              | [da3617cc40](https://linux-hardware.org/?probe=da3617cc40) | Feb 14, 2023 |
| Gigabyte      | P65                         | [b3d7faba21](https://linux-hardware.org/?probe=b3d7faba21) | Feb 12, 2023 |
| Gigabyte      | P65                         | [25d871afca](https://linux-hardware.org/?probe=25d871afca) | Feb 11, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [b6b590fcdf](https://linux-hardware.org/?probe=b6b590fcdf) | Feb 11, 2023 |
| Dell          | Latitude 7370               | [30c62c9e44](https://linux-hardware.org/?probe=30c62c9e44) | Feb 10, 2023 |
| Dell          | Latitude 7370               | [b4e7a5cb63](https://linux-hardware.org/?probe=b4e7a5cb63) | Feb 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [25e4994344](https://linux-hardware.org/?probe=25e4994344) | Feb 09, 2023 |
| HP            | ProBook 640 G1              | [d0319bdf17](https://linux-hardware.org/?probe=d0319bdf17) | Feb 09, 2023 |
| Acer          | Aspire S7-391               | [3777a7d1e9](https://linux-hardware.org/?probe=3777a7d1e9) | Feb 08, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [f268d3da5e](https://linux-hardware.org/?probe=f268d3da5e) | Feb 08, 2023 |
| Acer          | Aspire V3-572G              | [7b48d97053](https://linux-hardware.org/?probe=7b48d97053) | Feb 07, 2023 |
| Toshiba       | Satellite C660              | [b2247eafed](https://linux-hardware.org/?probe=b2247eafed) | Feb 05, 2023 |
| Dell          | Precision 7550              | [9608ff008d](https://linux-hardware.org/?probe=9608ff008d) | Feb 04, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [e3ab731c3c](https://linux-hardware.org/?probe=e3ab731c3c) | Feb 02, 2023 |
| ASUSTek       | ZenBook UX425JA_UX425JA     | [367646ee16](https://linux-hardware.org/?probe=367646ee16) | Feb 02, 2023 |
| ASUSTek       | X555LD                      | [b70d834fe5](https://linux-hardware.org/?probe=b70d834fe5) | Jan 29, 2023 |
| INSYS         | GW1-W149                    | [5a4337006d](https://linux-hardware.org/?probe=5a4337006d) | Jan 28, 2023 |
| Acer          | Aspire 7750G                | [0b05244a15](https://linux-hardware.org/?probe=0b05244a15) | Jan 27, 2023 |
| ASUSTek       | X541UJ                      | [d9ceb3c732](https://linux-hardware.org/?probe=d9ceb3c732) | Jan 27, 2023 |
| HP            | ProBook 640 G2              | [4e8cd1aa46](https://linux-hardware.org/?probe=4e8cd1aa46) | Jan 26, 2023 |
| Lenovo        | ThinkPad L490 20Q5002GPG    | [a9567dc72b](https://linux-hardware.org/?probe=a9567dc72b) | Jan 26, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [a8ee7729d5](https://linux-hardware.org/?probe=a8ee7729d5) | Jan 23, 2023 |
| ASUSTek       | UX360CA                     | [98fa78d117](https://linux-hardware.org/?probe=98fa78d117) | Jan 22, 2023 |
| Acer          | Aspire E1-522               | [ad5202642a](https://linux-hardware.org/?probe=ad5202642a) | Jan 22, 2023 |
| Chuwi         | GemiBook Pro                | [f52614c5aa](https://linux-hardware.org/?probe=f52614c5aa) | Jan 21, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [27e484698b](https://linux-hardware.org/?probe=27e484698b) | Jan 20, 2023 |
| Apple         | MacBookPro6,2               | [09dbcb3ae4](https://linux-hardware.org/?probe=09dbcb3ae4) | Jan 20, 2023 |
| Apple         | MacBookPro6,2               | [a929c23a1b](https://linux-hardware.org/?probe=a929c23a1b) | Jan 20, 2023 |
| Lenovo        | ThinkPad T470p 20J60018M... | [9324b897c3](https://linux-hardware.org/?probe=9324b897c3) | Jan 19, 2023 |
| Apple         | MacBookPro6,2               | [95074766b9](https://linux-hardware.org/?probe=95074766b9) | Jan 18, 2023 |
| Acer          | Predator PH315-51           | [0b2ae38776](https://linux-hardware.org/?probe=0b2ae38776) | Jan 16, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | [bbf1dabe59](https://linux-hardware.org/?probe=bbf1dabe59) | Jan 14, 2023 |
| ASUSTek       | X541UV                      | [d45c8ef0ac](https://linux-hardware.org/?probe=d45c8ef0ac) | Jan 13, 2023 |
| Acer          | Aspire V5-122               | [a25a7c3fb1](https://linux-hardware.org/?probe=a25a7c3fb1) | Jan 12, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | [e9783891d1](https://linux-hardware.org/?probe=e9783891d1) | Jan 12, 2023 |
| Acer          | Aspire 5742G                | [07f15478a7](https://linux-hardware.org/?probe=07f15478a7) | Jan 11, 2023 |
| Unknown       | Unknown                     | [ce97b4a08f](https://linux-hardware.org/?probe=ce97b4a08f) | Jan 08, 2023 |
| ASUSTek       | GL753VE                     | [7e0d372f98](https://linux-hardware.org/?probe=7e0d372f98) | Jan 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [50d2637c41](https://linux-hardware.org/?probe=50d2637c41) | Jan 07, 2023 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | [b69c9f59d5](https://linux-hardware.org/?probe=b69c9f59d5) | Jan 06, 2023 |
| HP            | Pavilion dv6                | [9f0fb0adf5](https://linux-hardware.org/?probe=9f0fb0adf5) | Jan 04, 2023 |
| Toshiba       | Satellite C50D-B            | [e4bc0d4130](https://linux-hardware.org/?probe=e4bc0d4130) | Jan 04, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [e24802533e](https://linux-hardware.org/?probe=e24802533e) | Jan 03, 2023 |
| Acer          | Aspire 4310                 | [e179184ea3](https://linux-hardware.org/?probe=e179184ea3) | Jan 02, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [113a2a45b2](https://linux-hardware.org/?probe=113a2a45b2) | Jan 01, 2023 |
| Toshiba       | Satellite L775-12V          | [2c601f6366](https://linux-hardware.org/?probe=2c601f6366) | Dec 29, 2022 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | [f980d6ed2e](https://linux-hardware.org/?probe=f980d6ed2e) | Dec 23, 2022 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | [a5dcdfece2](https://linux-hardware.org/?probe=a5dcdfece2) | Dec 23, 2022 |
| Dell          | Latitude E4310              | [6386845196](https://linux-hardware.org/?probe=6386845196) | Dec 23, 2022 |
| Dell          | XPS 13 9370                 | [982f470134](https://linux-hardware.org/?probe=982f470134) | Dec 21, 2022 |
| Dell          | Latitude E4310              | [7b184a032b](https://linux-hardware.org/?probe=7b184a032b) | Dec 21, 2022 |
| Dell          | Inspiron N5050              | [41fb3c537a](https://linux-hardware.org/?probe=41fb3c537a) | Dec 19, 2022 |
| Thomson       | PT-NEO14A.2WH32             | [d028ff11a9](https://linux-hardware.org/?probe=d028ff11a9) | Dec 18, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [49fad98b7b](https://linux-hardware.org/?probe=49fad98b7b) | Dec 12, 2022 |
| Dell          | Precision 5510              | [77b7f6dd95](https://linux-hardware.org/?probe=77b7f6dd95) | Dec 12, 2022 |
| Sony          | VGN-FZ31Z                   | [4f392d3575](https://linux-hardware.org/?probe=4f392d3575) | Dec 10, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [8008043900](https://linux-hardware.org/?probe=8008043900) | Dec 10, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [de42f36422](https://linux-hardware.org/?probe=de42f36422) | Dec 10, 2022 |
| Acer          | Aspire A315-55G             | [0c6e399e4f](https://linux-hardware.org/?probe=0c6e399e4f) | Dec 09, 2022 |
| Acer          | Aspire A315-55G             | [9c083ab22c](https://linux-hardware.org/?probe=9c083ab22c) | Dec 09, 2022 |
| MSI           | GF72 8RD                    | [f943786d2c](https://linux-hardware.org/?probe=f943786d2c) | Dec 09, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [29c71a771b](https://linux-hardware.org/?probe=29c71a771b) | Dec 08, 2022 |
| HP            | Pavilion dv6                | [8a940a493b](https://linux-hardware.org/?probe=8a940a493b) | Dec 03, 2022 |
| MSI           | GF72 8RD                    | [c03f783ea5](https://linux-hardware.org/?probe=c03f783ea5) | Dec 01, 2022 |
| Acer          | Nitro AN515-58              | [6bb64e8108](https://linux-hardware.org/?probe=6bb64e8108) | Nov 29, 2022 |
| Acer          | Aspire E1-570G              | [bbb8e289a9](https://linux-hardware.org/?probe=bbb8e289a9) | Nov 29, 2022 |
| Acer          | Aspire E1-570G              | [def1faf044](https://linux-hardware.org/?probe=def1faf044) | Nov 28, 2022 |
| ASUSTek       | N61Vg                       | [b5cc07b253](https://linux-hardware.org/?probe=b5cc07b253) | Nov 27, 2022 |
| MSI           | GF72 8RD                    | [fb92041c1b](https://linux-hardware.org/?probe=fb92041c1b) | Nov 26, 2022 |
| HUAWEI        | BOM-WXX9                    | [59a39475dd](https://linux-hardware.org/?probe=59a39475dd) | Nov 26, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | [fa21163ace](https://linux-hardware.org/?probe=fa21163ace) | Nov 26, 2022 |
| ASUSTek       | F7SR                        | [ecdba533ea](https://linux-hardware.org/?probe=ecdba533ea) | Nov 25, 2022 |
| ASUSTek       | F7SR                        | [8102d8b361](https://linux-hardware.org/?probe=8102d8b361) | Nov 25, 2022 |
| MSI           | Summit E16Flip A12UCT       | [95f653bddb](https://linux-hardware.org/?probe=95f653bddb) | Nov 24, 2022 |
| MSI           | Summit E16Flip A12UCT       | [a4a2b60b09](https://linux-hardware.org/?probe=a4a2b60b09) | Nov 24, 2022 |
| HUAWEI        | BOD-WXX9                    | [2de63dfd54](https://linux-hardware.org/?probe=2de63dfd54) | Nov 23, 2022 |
| HUAWEI        | BOD-WXX9                    | [814f45a510](https://linux-hardware.org/?probe=814f45a510) | Nov 23, 2022 |
| Apple         | MacBookAir5,1               | [2ded48104d](https://linux-hardware.org/?probe=2ded48104d) | Nov 22, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [0584338e31](https://linux-hardware.org/?probe=0584338e31) | Nov 22, 2022 |
| Acer          | Popcorn                     | [6f446a097a](https://linux-hardware.org/?probe=6f446a097a) | Nov 20, 2022 |
| Apple         | MacBookPro8,1               | [dfb9f9524e](https://linux-hardware.org/?probe=dfb9f9524e) | Nov 20, 2022 |
| Dell          | XPS 13 9360                 | [250885e79f](https://linux-hardware.org/?probe=250885e79f) | Nov 19, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | [02c6e2e360](https://linux-hardware.org/?probe=02c6e2e360) | Nov 18, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | [d4c27f1388](https://linux-hardware.org/?probe=d4c27f1388) | Nov 18, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [3b33d1989a](https://linux-hardware.org/?probe=3b33d1989a) | Nov 18, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [0401b9e939](https://linux-hardware.org/?probe=0401b9e939) | Nov 17, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [68db7ff193](https://linux-hardware.org/?probe=68db7ff193) | Nov 16, 2022 |
| Acer          | Aspire V3-575G              | [9044e30d53](https://linux-hardware.org/?probe=9044e30d53) | Nov 16, 2022 |
| ASUSTek       | G752VS                      | [364d6d09ab](https://linux-hardware.org/?probe=364d6d09ab) | Nov 14, 2022 |
| HUAWEI        | BOM-WXX9                    | [c54708e797](https://linux-hardware.org/?probe=c54708e797) | Nov 14, 2022 |
| HUAWEI        | BOM-WXX9                    | [c332019d7e](https://linux-hardware.org/?probe=c332019d7e) | Nov 14, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [e54df5cb0d](https://linux-hardware.org/?probe=e54df5cb0d) | Nov 13, 2022 |
| ASUSTek       | A6JC                        | [dce6c2a8f4](https://linux-hardware.org/?probe=dce6c2a8f4) | Nov 13, 2022 |
| Packard Be... | EasyNote LV11HC             | [244d508935](https://linux-hardware.org/?probe=244d508935) | Nov 12, 2022 |
| HUAWEI        | HVY-WXX9                    | [c1f18206f4](https://linux-hardware.org/?probe=c1f18206f4) | Nov 11, 2022 |
| eMachines     | G525                        | [38b8684942](https://linux-hardware.org/?probe=38b8684942) | Nov 10, 2022 |
| ASUSTek       | N61Vg                       | [5205b24cb0](https://linux-hardware.org/?probe=5205b24cb0) | Nov 08, 2022 |
| Dell          | Latitude E6510              | [befb811cfe](https://linux-hardware.org/?probe=befb811cfe) | Nov 05, 2022 |
| Acer          | Nitro AN515-55              | [a1cef4e43d](https://linux-hardware.org/?probe=a1cef4e43d) | Nov 04, 2022 |
| Acer          | Nitro AN515-55              | [b58a40d876](https://linux-hardware.org/?probe=b58a40d876) | Nov 04, 2022 |
| ASUSTek       | N61Vg                       | [27f288e5f1](https://linux-hardware.org/?probe=27f288e5f1) | Nov 01, 2022 |
| Dell          | Latitude E6510              | [b346d71347](https://linux-hardware.org/?probe=b346d71347) | Oct 29, 2022 |
| Acer          | Aspire SW5-012              | [90dd31edc8](https://linux-hardware.org/?probe=90dd31edc8) | Oct 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [50a8c356f0](https://linux-hardware.org/?probe=50a8c356f0) | Oct 28, 2022 |
| Acer          | Aspire ES1-131              | [f0edf4897a](https://linux-hardware.org/?probe=f0edf4897a) | Oct 26, 2022 |
| Dell          | Latitude 7320               | [f249267def](https://linux-hardware.org/?probe=f249267def) | Oct 26, 2022 |
| Samsung       | 870Z5E/880Z5E/680Z5E        | [8ebb941ac6](https://linux-hardware.org/?probe=8ebb941ac6) | Oct 26, 2022 |
| ASUSTek       | X542URR                     | [fe6fb20830](https://linux-hardware.org/?probe=fe6fb20830) | Oct 25, 2022 |
| Toshiba       | NB300                       | [c5aa7d3c5f](https://linux-hardware.org/?probe=c5aa7d3c5f) | Oct 25, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [ede3bcd3f3](https://linux-hardware.org/?probe=ede3bcd3f3) | Oct 24, 2022 |
| ASUSTek       | S550CB                      | [a81f0ecac8](https://linux-hardware.org/?probe=a81f0ecac8) | Oct 24, 2022 |
| Apple         | MacBookPro10,1              | [6354f13944](https://linux-hardware.org/?probe=6354f13944) | Oct 21, 2022 |
| HP            | G62                         | [721c09b331](https://linux-hardware.org/?probe=721c09b331) | Oct 19, 2022 |
| HP            | EliteBook 840 G6            | [e5f7b07e9c](https://linux-hardware.org/?probe=e5f7b07e9c) | Oct 19, 2022 |
| HP            | EliteBook 840 G6            | [25bb674789](https://linux-hardware.org/?probe=25bb674789) | Oct 19, 2022 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | [40771441a2](https://linux-hardware.org/?probe=40771441a2) | Oct 17, 2022 |
| ASUSTek       | X541UV                      | [ba7c1c3d83](https://linux-hardware.org/?probe=ba7c1c3d83) | Oct 14, 2022 |
| Toshiba       | Satellite L650              | [89f43e5484](https://linux-hardware.org/?probe=89f43e5484) | Oct 12, 2022 |
| Toshiba       | Satellite L650              | [43f57daebb](https://linux-hardware.org/?probe=43f57daebb) | Oct 12, 2022 |
| HP            | EliteBook 840 G2            | [d83c027361](https://linux-hardware.org/?probe=d83c027361) | Oct 12, 2022 |
| ASUSTek       | N53SV                       | [2460d79ba8](https://linux-hardware.org/?probe=2460d79ba8) | Oct 10, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [184ecb5e76](https://linux-hardware.org/?probe=184ecb5e76) | Oct 08, 2022 |
| ASUSTek       | G752VS                      | [df98c91ed6](https://linux-hardware.org/?probe=df98c91ed6) | Oct 08, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [8061516838](https://linux-hardware.org/?probe=8061516838) | Oct 06, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [a3d3100ffa](https://linux-hardware.org/?probe=a3d3100ffa) | Oct 05, 2022 |
| Acer          | Aspire ES1-520              | [b50cfdccab](https://linux-hardware.org/?probe=b50cfdccab) | Oct 05, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [8d863ae2d8](https://linux-hardware.org/?probe=8d863ae2d8) | Oct 04, 2022 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [1e0190a274](https://linux-hardware.org/?probe=1e0190a274) | Oct 03, 2022 |
| HP            | ENVY 15                     | [950623d8b2](https://linux-hardware.org/?probe=950623d8b2) | Oct 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [d9a196cd8e](https://linux-hardware.org/?probe=d9a196cd8e) | Oct 02, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [516795a4a8](https://linux-hardware.org/?probe=516795a4a8) | Oct 02, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [7ff2c5ad1c](https://linux-hardware.org/?probe=7ff2c5ad1c) | Oct 01, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [a64cec6a4d](https://linux-hardware.org/?probe=a64cec6a4d) | Oct 01, 2022 |
| MSI           | Modern 14 A10M              | [5c5666fa97](https://linux-hardware.org/?probe=5c5666fa97) | Sep 29, 2022 |
| GIADA         | ChiefRiver Platform         | [d0f71cdc7f](https://linux-hardware.org/?probe=d0f71cdc7f) | Sep 26, 2022 |
| HP            | ProBook 440 14 inch G9 N... | [84d47822bf](https://linux-hardware.org/?probe=84d47822bf) | Sep 24, 2022 |
| HP            | ProBook 440 14 inch G9 N... | [3afd2e892b](https://linux-hardware.org/?probe=3afd2e892b) | Sep 24, 2022 |
| Acer          | Predator PH315-51           | [24ae1f3fb8](https://linux-hardware.org/?probe=24ae1f3fb8) | Sep 23, 2022 |
| ASUSTek       | X556UF                      | [47f145c034](https://linux-hardware.org/?probe=47f145c034) | Sep 23, 2022 |
| ASUSTek       | X556UF                      | [2f1fe986d8](https://linux-hardware.org/?probe=2f1fe986d8) | Sep 23, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [7910fab01e](https://linux-hardware.org/?probe=7910fab01e) | Sep 22, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [910b604abc](https://linux-hardware.org/?probe=910b604abc) | Sep 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [b72e23e590](https://linux-hardware.org/?probe=b72e23e590) | Sep 20, 2022 |
| Toshiba       | Satellite P845T             | [0d5f5ac925](https://linux-hardware.org/?probe=0d5f5ac925) | Sep 17, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [dd6d053ae2](https://linux-hardware.org/?probe=dd6d053ae2) | Sep 17, 2022 |
| ASUSTek       | N550LF                      | [73f2edfe65](https://linux-hardware.org/?probe=73f2edfe65) | Sep 16, 2022 |
| ASUSTek       | X555LJ                      | [5d27ea49aa](https://linux-hardware.org/?probe=5d27ea49aa) | Sep 13, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [d4fb6aa0ae](https://linux-hardware.org/?probe=d4fb6aa0ae) | Sep 13, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [e558fd5212](https://linux-hardware.org/?probe=e558fd5212) | Sep 13, 2022 |
| Lenovo        | ThinkPad W540 20BG0016US    | [9f0543edc4](https://linux-hardware.org/?probe=9f0543edc4) | Sep 11, 2022 |
| Chuwi         | CoreBook X                  | [4f29128588](https://linux-hardware.org/?probe=4f29128588) | Sep 11, 2022 |
| System76      | Oryx Pro                    | [d84de42ab6](https://linux-hardware.org/?probe=d84de42ab6) | Sep 10, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [ab939db2c0](https://linux-hardware.org/?probe=ab939db2c0) | Sep 10, 2022 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | [f9604390e8](https://linux-hardware.org/?probe=f9604390e8) | Sep 10, 2022 |
| HP            | EliteBook 840 G6            | [132a8e025a](https://linux-hardware.org/?probe=132a8e025a) | Sep 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [5d61bcd114](https://linux-hardware.org/?probe=5d61bcd114) | Sep 06, 2022 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [bcd73bee62](https://linux-hardware.org/?probe=bcd73bee62) | Sep 06, 2022 |
| HP            | Pavilion g6                 | [770b1a8154](https://linux-hardware.org/?probe=770b1a8154) | Sep 05, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [c2cd1091cd](https://linux-hardware.org/?probe=c2cd1091cd) | Sep 04, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [66724351c4](https://linux-hardware.org/?probe=66724351c4) | Sep 04, 2022 |
| Sony          | VGN-FZ31Z                   | [b99831e9f4](https://linux-hardware.org/?probe=b99831e9f4) | Sep 03, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [a74d79fc0b](https://linux-hardware.org/?probe=a74d79fc0b) | Sep 02, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [8a7e7ce8ea](https://linux-hardware.org/?probe=8a7e7ce8ea) | Sep 01, 2022 |
| ASUSTek       | X541UJ                      | [0cd33aa36a](https://linux-hardware.org/?probe=0cd33aa36a) | Aug 31, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [11efd3dbe0](https://linux-hardware.org/?probe=11efd3dbe0) | Aug 30, 2022 |
| Toshiba       | Satellite A300              | [f90886ae85](https://linux-hardware.org/?probe=f90886ae85) | Aug 30, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [3b26a2ffe2](https://linux-hardware.org/?probe=3b26a2ffe2) | Aug 29, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [98ac365e3c](https://linux-hardware.org/?probe=98ac365e3c) | Aug 28, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [73db272ecb](https://linux-hardware.org/?probe=73db272ecb) | Aug 28, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [ee07c7a93a](https://linux-hardware.org/?probe=ee07c7a93a) | Aug 27, 2022 |
| HP            | Laptop 15s-fq2xxx           | [8ffebf0c43](https://linux-hardware.org/?probe=8ffebf0c43) | Aug 26, 2022 |
| ASUSTek       | N61Vg                       | [30be913709](https://linux-hardware.org/?probe=30be913709) | Aug 25, 2022 |
| HP            | ProBook 640 G2              | [fc50d4e200](https://linux-hardware.org/?probe=fc50d4e200) | Aug 25, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [cb533d9c12](https://linux-hardware.org/?probe=cb533d9c12) | Aug 22, 2022 |
| Lenovo        | ThinkPad P50 20EN0005PG     | [69c8e5eedc](https://linux-hardware.org/?probe=69c8e5eedc) | Aug 19, 2022 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [2bf774fae7](https://linux-hardware.org/?probe=2bf774fae7) | Aug 18, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [57732104cd](https://linux-hardware.org/?probe=57732104cd) | Aug 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [315da58d24](https://linux-hardware.org/?probe=315da58d24) | Aug 16, 2022 |
| Lenovo        | ThinkPad T430 2349V4B       | [0f919e20c7](https://linux-hardware.org/?probe=0f919e20c7) | Aug 14, 2022 |
| Apple         | MacBookPro5,5               | [76483c9f78](https://linux-hardware.org/?probe=76483c9f78) | Aug 14, 2022 |
| ASUSTek       | N53SN                       | [6cb4ac4247](https://linux-hardware.org/?probe=6cb4ac4247) | Aug 14, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [73a3d7c1cf](https://linux-hardware.org/?probe=73a3d7c1cf) | Aug 12, 2022 |
| MSI           | Modern 14 A10RB             | [9979c66e3e](https://linux-hardware.org/?probe=9979c66e3e) | Aug 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [9d6be5eb68](https://linux-hardware.org/?probe=9d6be5eb68) | Aug 08, 2022 |
| Apple         | MacBookAir6,1               | [154468415c](https://linux-hardware.org/?probe=154468415c) | Aug 05, 2022 |
| Apple         | MacBookAir6,1               | [6f355de994](https://linux-hardware.org/?probe=6f355de994) | Aug 04, 2022 |
| Toshiba       | Satellite U840              | [5ebf9417bf](https://linux-hardware.org/?probe=5ebf9417bf) | Aug 04, 2022 |
| MSI           | Modern 14 A10RB             | [abf1fcf08b](https://linux-hardware.org/?probe=abf1fcf08b) | Aug 02, 2022 |
| HP            | Laptop 15s-eq0xxx           | [d1ae6a188c](https://linux-hardware.org/?probe=d1ae6a188c) | Jul 31, 2022 |
| HP            | Laptop 15s-eq0xxx           | [bce4496b78](https://linux-hardware.org/?probe=bce4496b78) | Jul 31, 2022 |
| HP            | Pavilion dv2000 (RQ116PA... | [c6ce2d4317](https://linux-hardware.org/?probe=c6ce2d4317) | Jul 31, 2022 |
| HP            | Pavilion dv2000 (RQ116PA... | [eca5fa0c39](https://linux-hardware.org/?probe=eca5fa0c39) | Jul 31, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [bc5b132a8d](https://linux-hardware.org/?probe=bc5b132a8d) | Jul 29, 2022 |
| Toshiba       | Satellite U840              | [c3f00f5b90](https://linux-hardware.org/?probe=c3f00f5b90) | Jul 29, 2022 |
| ASUSTek       | N53SN                       | [2e35ef4a8a](https://linux-hardware.org/?probe=2e35ef4a8a) | Jul 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [e95cafce19](https://linux-hardware.org/?probe=e95cafce19) | Jul 26, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [ae16c8863a](https://linux-hardware.org/?probe=ae16c8863a) | Jul 25, 2022 |
| ASUSTek       | X540LJ                      | [264bb2f2a1](https://linux-hardware.org/?probe=264bb2f2a1) | Jul 23, 2022 |
| ASUSTek       | X540LJ                      | [fc5c252e6e](https://linux-hardware.org/?probe=fc5c252e6e) | Jul 23, 2022 |
| Acer          | Aspire A515-45              | [323aa03c61](https://linux-hardware.org/?probe=323aa03c61) | Jul 18, 2022 |
| Dell          | XPS 15 7590                 | [528f562110](https://linux-hardware.org/?probe=528f562110) | Jul 18, 2022 |
| Packard Be... | EasyNote LV11HC             | [c0693d5f9a](https://linux-hardware.org/?probe=c0693d5f9a) | Jul 18, 2022 |
| Sony          | SVF1521F6EW                 | [3f359d9763](https://linux-hardware.org/?probe=3f359d9763) | Jul 17, 2022 |
| Sony          | VPCEB3L1E                   | [310a2ada05](https://linux-hardware.org/?probe=310a2ada05) | Jul 13, 2022 |
| Sony          | VPCEB3L1E                   | [247411abde](https://linux-hardware.org/?probe=247411abde) | Jul 13, 2022 |
| Sony          | VPCEB3L1E                   | [9af59fca26](https://linux-hardware.org/?probe=9af59fca26) | Jul 08, 2022 |
| ASUSTek       | X540LJ                      | [5994a314d0](https://linux-hardware.org/?probe=5994a314d0) | Jul 05, 2022 |
| ASUSTek       | K53SC                       | [4f31f807cb](https://linux-hardware.org/?probe=4f31f807cb) | Jul 05, 2022 |
| Sony          | VGN-FZ31Z                   | [62d8b20ff8](https://linux-hardware.org/?probe=62d8b20ff8) | Jul 04, 2022 |
| HP            | Stream Laptop 14-ax0XX      | [03bede7266](https://linux-hardware.org/?probe=03bede7266) | Jul 03, 2022 |
| Acer          | Aspire A515-54G             | [c0975c6877](https://linux-hardware.org/?probe=c0975c6877) | Jul 02, 2022 |
| ASUSTek       | N61Jq                       | [19b3d15d92](https://linux-hardware.org/?probe=19b3d15d92) | Jul 02, 2022 |
| Acer          | Aspire A515-54G             | [92d695d6be](https://linux-hardware.org/?probe=92d695d6be) | Jul 02, 2022 |
| HP            | EliteBook 840 G1            | [b691598870](https://linux-hardware.org/?probe=b691598870) | Jul 01, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [91c5f849c5](https://linux-hardware.org/?probe=91c5f849c5) | Jun 29, 2022 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | [17cb04c5f5](https://linux-hardware.org/?probe=17cb04c5f5) | Jun 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [1c4ace32a2](https://linux-hardware.org/?probe=1c4ace32a2) | Jun 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [d4b96de9b6](https://linux-hardware.org/?probe=d4b96de9b6) | Jun 24, 2022 |
| Sony          | VPCEH2J1E                   | [7dde3ae196](https://linux-hardware.org/?probe=7dde3ae196) | Jun 23, 2022 |
| HP            | EliteBook 820 G1            | [ff4b7698ed](https://linux-hardware.org/?probe=ff4b7698ed) | Jun 23, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [fd65aaa4b3](https://linux-hardware.org/?probe=fd65aaa4b3) | Jun 21, 2022 |
| Toshiba       | NB305                       | [1280ac15ba](https://linux-hardware.org/?probe=1280ac15ba) | Jun 17, 2022 |
| HP            | Pavilion Notebook           | [d9b85c0e15](https://linux-hardware.org/?probe=d9b85c0e15) | Jun 16, 2022 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [4b1946451e](https://linux-hardware.org/?probe=4b1946451e) | Jun 15, 2022 |
| ASUSTek       | E403SA                      | [9ca6a865ff](https://linux-hardware.org/?probe=9ca6a865ff) | Jun 11, 2022 |
| Apple         | MacBookAir6,1               | [f0883ab59b](https://linux-hardware.org/?probe=f0883ab59b) | Jun 10, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [35dc89f7ff](https://linux-hardware.org/?probe=35dc89f7ff) | Jun 09, 2022 |
| Toshiba       | QOSMIO X770                 | [d11736c26f](https://linux-hardware.org/?probe=d11736c26f) | Jun 09, 2022 |
| Toshiba       | Satellite T130              | [b5ba2dac2a](https://linux-hardware.org/?probe=b5ba2dac2a) | Jun 06, 2022 |
| Toshiba       | Satellite T130              | [3fe154a2ce](https://linux-hardware.org/?probe=3fe154a2ce) | Jun 06, 2022 |
| Sony          | VGN-FZ31Z                   | [f9b7b79d5a](https://linux-hardware.org/?probe=f9b7b79d5a) | Jun 04, 2022 |
| Dell          | Latitude E6400              | [67a5bdc1aa](https://linux-hardware.org/?probe=67a5bdc1aa) | Jun 04, 2022 |
| HP            | Compaq nx7300 (RU464EA#A... | [a44ec57985](https://linux-hardware.org/?probe=a44ec57985) | Jun 02, 2022 |
| HP            | EliteBook 840 G2            | [8aff04335d](https://linux-hardware.org/?probe=8aff04335d) | Jun 01, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [029a55ffb4](https://linux-hardware.org/?probe=029a55ffb4) | Jun 01, 2022 |
| Chuwi         | GemiBook Pro                | [24fb23a450](https://linux-hardware.org/?probe=24fb23a450) | May 31, 2022 |
| Lenovo        | ThinkPad T530 2394C98       | [b5aebb2490](https://linux-hardware.org/?probe=b5aebb2490) | May 30, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [f47dbc0616](https://linux-hardware.org/?probe=f47dbc0616) | May 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [e72ac27af1](https://linux-hardware.org/?probe=e72ac27af1) | May 30, 2022 |
| Acer          | Swift SF314-54              | [eb522816a1](https://linux-hardware.org/?probe=eb522816a1) | May 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [de7ed0046e](https://linux-hardware.org/?probe=de7ed0046e) | May 29, 2022 |
| Lenovo        | ThinkPad X230 2325N66       | [2061351dbc](https://linux-hardware.org/?probe=2061351dbc) | May 28, 2022 |
| Lenovo        | ThinkPad L490 20Q5002GPG    | [9e1d2f7e8a](https://linux-hardware.org/?probe=9e1d2f7e8a) | May 26, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [533beb13eb](https://linux-hardware.org/?probe=533beb13eb) | May 26, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [d98649058e](https://linux-hardware.org/?probe=d98649058e) | May 24, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [00a44d4f7e](https://linux-hardware.org/?probe=00a44d4f7e) | May 21, 2022 |
| HP            | EliteBook 8540w             | [2f973c22ec](https://linux-hardware.org/?probe=2f973c22ec) | May 19, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [1ef52e97fa](https://linux-hardware.org/?probe=1ef52e97fa) | May 18, 2022 |
| Apple         | MacBookAir7,2               | [a46fea4edb](https://linux-hardware.org/?probe=a46fea4edb) | May 18, 2022 |
| Notebook      | NB50TJ1_TK1                 | [8789da25ba](https://linux-hardware.org/?probe=8789da25ba) | May 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [58f371c0d7](https://linux-hardware.org/?probe=58f371c0d7) | May 13, 2022 |
| Lenovo        | ThinkPad X61 7673AQ5        | [42a17c86f4](https://linux-hardware.org/?probe=42a17c86f4) | May 13, 2022 |
| MSI           | GT72VR 6RD                  | [c4cf6c9cd0](https://linux-hardware.org/?probe=c4cf6c9cd0) | May 12, 2022 |
| MSI           | Modern 15 A10RAS            | [3e844bb07a](https://linux-hardware.org/?probe=3e844bb07a) | May 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [f837aaeb12](https://linux-hardware.org/?probe=f837aaeb12) | May 08, 2022 |
| HP            | Pavilion g6                 | [69406bff46](https://linux-hardware.org/?probe=69406bff46) | May 08, 2022 |
| HP            | Pavilion g6                 | [56ca785331](https://linux-hardware.org/?probe=56ca785331) | May 08, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [d24187e845](https://linux-hardware.org/?probe=d24187e845) | May 05, 2022 |
| HP            | ProBook 640 G2              | [50ccff3e1a](https://linux-hardware.org/?probe=50ccff3e1a) | May 04, 2022 |
| ASUSTek       | X540SAA                     | [9943699a6b](https://linux-hardware.org/?probe=9943699a6b) | May 04, 2022 |
| HP            | EliteBook 840 G5            | [47aaf6f556](https://linux-hardware.org/?probe=47aaf6f556) | May 04, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [0a6358dc13](https://linux-hardware.org/?probe=0a6358dc13) | May 03, 2022 |
| Sony          | VGN-FZ31Z                   | [ebe91972ba](https://linux-hardware.org/?probe=ebe91972ba) | May 01, 2022 |
| HP            | ENVY Laptop 15-ep0xxx       | [96dbfb494e](https://linux-hardware.org/?probe=96dbfb494e) | Apr 29, 2022 |
| ASUSTek       | X540SAA                     | [6c8e397ca3](https://linux-hardware.org/?probe=6c8e397ca3) | Apr 29, 2022 |
| Lenovo        | G50-45 80E3                 | [910267bbd5](https://linux-hardware.org/?probe=910267bbd5) | Apr 28, 2022 |
| Lenovo        | G50-45 80E3                 | [22dd67107b](https://linux-hardware.org/?probe=22dd67107b) | Apr 28, 2022 |
| HP            | Laptop 15s-fq2xxx           | [91c7a6b5a0](https://linux-hardware.org/?probe=91c7a6b5a0) | Apr 27, 2022 |
| Lenovo        | ThinkPad L490 20Q5002GPG    | [9e591226b7](https://linux-hardware.org/?probe=9e591226b7) | Apr 26, 2022 |
| Lenovo        | ThinkPad X201 Tablet 083... | [e3ece9d899](https://linux-hardware.org/?probe=e3ece9d899) | Apr 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [5c309ec35d](https://linux-hardware.org/?probe=5c309ec35d) | Apr 26, 2022 |
| Lenovo        | ThinkPad X201 Tablet 083... | [8e7b2c79a0](https://linux-hardware.org/?probe=8e7b2c79a0) | Apr 25, 2022 |
| ASUSTek       | X540LJ                      | [8e0c841b78](https://linux-hardware.org/?probe=8e0c841b78) | Apr 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [710ddc650e](https://linux-hardware.org/?probe=710ddc650e) | Apr 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [7fc8d31b49](https://linux-hardware.org/?probe=7fc8d31b49) | Apr 24, 2022 |
| ASUSTek       | 1215N                       | [93ad513620](https://linux-hardware.org/?probe=93ad513620) | Apr 24, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [6162231453](https://linux-hardware.org/?probe=6162231453) | Apr 23, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [9146df4426](https://linux-hardware.org/?probe=9146df4426) | Apr 23, 2022 |
| Apple         | MacBookPro7,1               | [2641eee3f1](https://linux-hardware.org/?probe=2641eee3f1) | Apr 21, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Portugal/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 141       | 9.59%   |
| Ubuntu 22.04                 | 101       | 6.87%   |
| Ubuntu 18.04                 | 88        | 5.99%   |
| Pop!_OS 22.04                | 40        | 2.72%   |
| Arch Rolling                 | 37        | 2.52%   |
| OpenMandriva 4.3             | 33        | 2.24%   |
| Zorin 16                     | 28        | 1.9%    |
| Debian 12                    | 25        | 1.7%    |
| Zorin 15                     | 24        | 1.63%   |
| Zorin 17                     | 23        | 1.56%   |
| Ubuntu 24.04                 | 23        | 1.56%   |
| OpenMandriva 4.2             | 22        | 1.5%    |
| Fedora 38                    | 21        | 1.43%   |
| Debian 11                    | 21        | 1.43%   |
| KDE neon 20.04               | 19        | 1.29%   |
| Pop!_OS 20.04                | 18        | 1.22%   |
| Linux Mint 20.3              | 18        | 1.22%   |
| Fedora 39                    | 17        | 1.16%   |
| Debian 10                    | 17        | 1.16%   |
| Fedora 40                    | 16        | 1.09%   |
| Fedora 34                    | 16        | 1.09%   |
| Manjaro                      | 15        | 1.02%   |
| Linux Mint 21.2              | 15        | 1.02%   |
| Ubuntu 19.10                 | 14        | 0.95%   |
| Linux Mint 20.1              | 14        | 0.95%   |
| Pop!_OS 21.04                | 13        | 0.88%   |
| OpenMandriva 23.08           | 13        | 0.88%   |
| Linux Mint 19.3              | 13        | 0.88%   |
| Arch                         | 13        | 0.88%   |
| Xubuntu 20.04                | 12        | 0.82%   |
| Ubuntu 21.10                 | 12        | 0.82%   |
| Ubuntu 19.04                 | 12        | 0.82%   |
| Pop!_OS 20.10                | 12        | 0.82%   |
| openSUSE Tumbleweed-XXXXXXXX | 12        | 0.82%   |
| OpenMandriva 4.50            | 12        | 0.82%   |
| Fedora 36                    | 12        | 0.82%   |
| Linux Mint 21.1              | 11        | 0.75%   |
| Linux Mint 21                | 11        | 0.75%   |
| Linux Mint 20                | 11        | 0.75%   |
| Fedora 33                    | 11        | 0.75%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Ubuntu           | 415       | 29.92%  |
| Linux Mint       | 119       | 8.58%   |
| Fedora           | 115       | 8.29%   |
| OpenMandriva     | 103       | 7.43%   |
| Pop!_OS          | 91        | 6.56%   |
| Zorin            | 74        | 5.34%   |
| Debian           | 71        | 5.12%   |
| Arch             | 50        | 3.6%    |
| Manjaro          | 38        | 2.74%   |
| KDE neon         | 34        | 2.45%   |
| Endless          | 33        | 2.38%   |
| Xubuntu          | 24        | 1.73%   |
| Kubuntu          | 19        | 1.37%   |
| openSUSE         | 18        | 1.3%    |
| Elementary       | 18        | 1.3%    |
| ROSA             | 13        | 0.94%   |
| ArcoLinux        | 13        | 0.94%   |
| Kali             | 10        | 0.72%   |
| NixOS            | 9         | 0.65%   |
| Lubuntu          | 8         | 0.58%   |
| EndeavourOS      | 7         | 0.5%    |
| Ubuntu Unity     | 6         | 0.43%   |
| Ubuntu MATE      | 6         | 0.43%   |
| SteamOS          | 6         | 0.43%   |
| Slackware        | 6         | 0.43%   |
| LMDE             | 6         | 0.43%   |
| Nobara           | 5         | 0.36%   |
| Gentoo           | 5         | 0.36%   |
| Clear Linux      | 5         | 0.36%   |
| Ubuntu Budgie    | 4         | 0.29%   |
| TUXEDO OS        | 4         | 0.29%   |
| Peppermint       | 4         | 0.29%   |
| Parrot           | 4         | 0.29%   |
| MX               | 4         | 0.29%   |
| Devuan           | 4         | 0.29%   |
| Xero             | 2         | 0.14%   |
| Void Linux       | 2         | 0.14%   |
| UbuntuDDE        | 2         | 0.14%   |
| Rocky Linux      | 2         | 0.14%   |
| org.kde.Platform | 2         | 0.14%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 25        | 1.55%   |
| 5.4.0-42-generic         | 24        | 1.49%   |
| 5.10.14-desktop-1omv4002 | 21        | 1.3%    |
| 5.15.0-56-generic        | 14        | 0.87%   |
| 5.14.14-desktop-1omv4050 | 13        | 0.8%    |
| 6.2.6-76060206-generic   | 12        | 0.74%   |
| 5.3.0-46-generic         | 12        | 0.74%   |
| 5.4.0-29-generic         | 11        | 0.68%   |
| 5.15.0-52-generic        | 11        | 0.68%   |
| 6.1.1-desktop-1omv2290   | 10        | 0.62%   |
| 5.4.0-58-generic         | 10        | 0.62%   |
| 5.4.0-52-generic         | 10        | 0.62%   |
| 5.15.0-48-generic        | 10        | 0.62%   |
| 5.15.0-46-generic        | 10        | 0.62%   |
| 5.11.0-38-generic        | 10        | 0.62%   |
| 6.4.11-desktop-1omv2390  | 9         | 0.56%   |
| 5.3.0-28-generic         | 9         | 0.56%   |
| 5.15.0-41-generic        | 9         | 0.56%   |
| 4.18.0-15-generic        | 9         | 0.56%   |
| 6.8.0-49-generic         | 8         | 0.5%    |
| 5.4.0-7634-generic       | 8         | 0.5%    |
| 5.4.0-26-generic         | 8         | 0.5%    |
| 5.11.0-43-generic        | 8         | 0.5%    |
| 5.0.0-37-generic         | 8         | 0.5%    |
| 5.0.0-25-generic         | 8         | 0.5%    |
| 4.18.0-25-generic        | 8         | 0.5%    |
| 6.6.2-desktop-1omv2390   | 7         | 0.43%   |
| 6.5.0-35-generic         | 7         | 0.43%   |
| 6.2.6-desktop-1omv2390   | 7         | 0.43%   |
| 6.2.0-36-generic         | 7         | 0.43%   |
| 6.2.0-26-generic         | 7         | 0.43%   |
| 5.4.0-31-generic         | 7         | 0.43%   |
| 5.19.0-76051900-generic  | 7         | 0.43%   |
| 5.15.0-58-generic        | 7         | 0.43%   |
| 5.13.0-39-generic        | 7         | 0.43%   |
| 4.15.0-46-generic        | 7         | 0.43%   |
| 6.5.0-14-generic         | 6         | 0.37%   |
| 6.2.0-39-generic         | 6         | 0.37%   |
| 6.2.0-37-generic         | 6         | 0.37%   |
| 6.2.0-20-generic         | 6         | 0.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 189       | 12.39%  |
| 5.15.0  | 117       | 7.67%   |
| 4.15.0  | 67        | 4.39%   |
| 5.8.0   | 63        | 4.13%   |
| 5.11.0  | 60        | 3.93%   |
| 5.3.0   | 55        | 3.6%    |
| 6.5.0   | 54        | 3.54%   |
| 5.13.0  | 49        | 3.21%   |
| 6.8.0   | 47        | 3.08%   |
| 6.2.0   | 47        | 3.08%   |
| 5.19.0  | 45        | 2.95%   |
| 5.0.0   | 39        | 2.56%   |
| 6.1.0   | 36        | 2.36%   |
| 4.18.0  | 36        | 2.36%   |
| 5.10.0  | 28        | 1.83%   |
| 5.16.7  | 25        | 1.64%   |
| 5.10.14 | 22        | 1.44%   |
| 6.2.6   | 19        | 1.25%   |
| 4.19.0  | 17        | 1.11%   |
| 5.14.14 | 13        | 0.85%   |
| 6.1.1   | 12        | 0.79%   |
| 6.4.11  | 9         | 0.59%   |
| 6.6.2   | 8         | 0.52%   |
| 6.6.10  | 6         | 0.39%   |
| 6.9.3   | 5         | 0.33%   |
| 6.6.15  | 5         | 0.33%   |
| 6.5.6   | 5         | 0.33%   |
| 6.0.12  | 5         | 0.33%   |
| 5.14.0  | 5         | 0.33%   |
| 4.4.0   | 5         | 0.33%   |
| 6.8.7   | 4         | 0.26%   |
| 6.8.11  | 4         | 0.26%   |
| 6.7.9   | 4         | 0.26%   |
| 6.6.3   | 4         | 0.26%   |
| 6.5.5   | 4         | 0.26%   |
| 6.4.8   | 4         | 0.26%   |
| 6.3.8   | 4         | 0.26%   |
| 6.2.15  | 4         | 0.26%   |
| 6.2.14  | 4         | 0.26%   |
| 6.0.0   | 4         | 0.26%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 199       | 13.17%  |
| 5.15    | 145       | 9.6%    |
| 6.2     | 80        | 5.29%   |
| 5.8     | 77        | 5.1%    |
| 6.5     | 76        | 5.03%   |
| 6.1     | 72        | 4.77%   |
| 5.11    | 68        | 4.5%    |
| 4.15    | 67        | 4.43%   |
| 5.10    | 65        | 4.3%    |
| 6.8     | 61        | 4.04%   |
| 5.19    | 59        | 3.9%    |
| 5.3     | 58        | 3.84%   |
| 5.13    | 54        | 3.57%   |
| 6.6     | 44        | 2.91%   |
| 5.16    | 44        | 2.91%   |
| 5.0     | 40        | 2.65%   |
| 4.18    | 37        | 2.45%   |
| 5.14    | 28        | 1.85%   |
| 6.4     | 26        | 1.72%   |
| 6.3     | 21        | 1.39%   |
| 6.0     | 20        | 1.32%   |
| 4.19    | 20        | 1.32%   |
| 6.11    | 17        | 1.13%   |
| 5.12    | 16        | 1.06%   |
| 6.9     | 14        | 0.93%   |
| 4.9     | 12        | 0.79%   |
| 6.10    | 11        | 0.73%   |
| 5.9     | 10        | 0.66%   |
| 5.7     | 10        | 0.66%   |
| 5.6     | 10        | 0.66%   |
| 5.17    | 10        | 0.66%   |
| 6.7     | 9         | 0.6%    |
| 6.12    | 7         | 0.46%   |
| 5.18    | 7         | 0.46%   |
| 5.5     | 6         | 0.4%    |
| 4.4     | 5         | 0.33%   |
| 5.2     | 2         | 0.13%   |
| 4.12    | 1         | 0.07%   |
| 4.1     | 1         | 0.07%   |
| 3.10    | 1         | 0.07%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 1282      | 96.17%  |
| i686    | 50        | 3.75%   |
| aarch64 | 1         | 0.08%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 660       | 47.11%  |
| KDE5             | 230       | 16.42%  |
| Unknown          | 149       | 10.64%  |
| XFCE             | 103       | 7.35%   |
| X-Cinnamon       | 93        | 6.64%   |
| MATE             | 26        | 1.86%   |
| KDE              | 25        | 1.78%   |
| Pantheon         | 16        | 1.14%   |
| KDE6             | 12        | 0.86%   |
| i3               | 12        | 0.86%   |
| KDE4             | 11        | 0.79%   |
| LXQt             | 10        | 0.71%   |
| Cinnamon         | 10        | 0.71%   |
| Budgie           | 8         | 0.57%   |
| Unity            | 7         | 0.5%    |
| LXDE             | 5         | 0.36%   |
| GNOME Flashback  | 4         | 0.29%   |
| Deepin           | 4         | 0.29%   |
| DWM              | 2         | 0.14%   |
| awesome          | 2         | 0.14%   |
| xmonad           | 1         | 0.07%   |
| Openbox          | 1         | 0.07%   |
| Lubuntu          | 1         | 0.07%   |
| lightdm-xsession | 1         | 0.07%   |
| Hyprland         | 1         | 0.07%   |
| fluxbox          | 1         | 0.07%   |
| Enlightenment    | 1         | 0.07%   |
| Endless:GNOME    | 1         | 0.07%   |
| DDE              | 1         | 0.07%   |
| Cutefish         | 1         | 0.07%   |
| COSMIC           | 1         | 0.07%   |
| bspwm            | 1         | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 960       | 69.77%  |
| Wayland | 335       | 24.35%  |
| Unknown | 77        | 5.6%    |
| Tty     | 4         | 0.29%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 701       | 50.4%   |
| GDM3    | 202       | 14.52%  |
| SDDM    | 201       | 14.45%  |
| GDM     | 125       | 8.99%   |
| LightDM | 116       | 8.34%   |
| TDM     | 28        | 2.01%   |
| KDM     | 10        | 0.72%   |
| XDM     | 3         | 0.22%   |
| SLiM    | 3         | 0.22%   |
| GREETD  | 2         | 0.14%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| pt_PT   | 544       | 39.74%  |
| en_US   | 502       | 36.67%  |
| Unknown | 139       | 10.15%  |
| en_GB   | 90        | 6.57%   |
| pt_BR   | 30        | 2.19%   |
| C       | 30        | 2.19%   |
| de_DE   | 7         | 0.51%   |
| fr_FR   | 5         | 0.37%   |
| es_ES   | 5         | 0.37%   |
| en_IE   | 4         | 0.29%   |
| POSIX   | 3         | 0.22%   |
| ru_RU   | 2         | 0.15%   |
| it_IT   | 2         | 0.15%   |
| he_IL   | 2         | 0.15%   |
| sk_SK   | 1         | 0.07%   |
| en_IN   | 1         | 0.07%   |
| en_DK   | 1         | 0.07%   |
| Default | 1         | 0.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 692       | 50.51%  |
| EFI  | 678       | 49.49%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 995       | 72.57%  |
| Btrfs    | 156       | 11.38%  |
| Overlay  | 75        | 5.47%   |
| Tmpfs    | 73        | 5.32%   |
| Unknown  | 45        | 3.28%   |
| Xfs      | 12        | 0.88%   |
| Zfs      | 8         | 0.58%   |
| Ext2     | 4         | 0.29%   |
| Ext3     | 2         | 0.15%   |
| Reiserfs | 1         | 0.07%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 727       | 53.1%   |
| GPT     | 526       | 38.42%  |
| MBR     | 116       | 8.47%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1215      | 89.93%  |
| Yes       | 136       | 10.07%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 992       | 73.1%   |
| Yes       | 365       | 26.9%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 258       | 19.4%   |
| Hewlett-Packard     | 251       | 18.87%  |
| ASUSTek Computer    | 224       | 16.84%  |
| Acer                | 123       | 9.25%   |
| Toshiba             | 87        | 6.54%   |
| Dell                | 80        | 6.02%   |
| Sony                | 48        | 3.61%   |
| Apple               | 40        | 3.01%   |
| MSI                 | 34        | 2.56%   |
| HUAWEI              | 29        | 2.18%   |
| Samsung Electronics | 20        | 1.5%    |
| Notebook            | 12        | 0.9%    |
| Chuwi               | 9         | 0.68%   |
| Fujitsu             | 8         | 0.6%    |
| TUXEDO              | 7         | 0.53%   |
| Packard Bell        | 7         | 0.53%   |
| Unknown             | 7         | 0.53%   |
| Valve               | 6         | 0.45%   |
| Gigabyte Technology | 6         | 0.45%   |
| Clevo               | 6         | 0.45%   |
| SLIMBOOK            | 4         | 0.3%    |
| LG Electronics      | 4         | 0.3%    |
| INSYS               | 4         | 0.3%    |
| Teclast             | 3         | 0.23%   |
| Positivo            | 3         | 0.23%   |
| Phoenix/SiS         | 3         | 0.23%   |
| PC Specialist       | 3         | 0.23%   |
| Medion              | 3         | 0.23%   |
| Intel               | 3         | 0.23%   |
| Fujitsu Siemens     | 3         | 0.23%   |
| eMachines           | 3         | 0.23%   |
| TongFang            | 2         | 0.15%   |
| OBSIDIAN-PC         | 2         | 0.15%   |
| LNV                 | 2         | 0.15%   |
| Jumper              | 2         | 0.15%   |
| AMI                 | 2         | 0.15%   |
| Alienware           | 2         | 0.15%   |
| Timi                | 1         | 0.08%   |
| Thomson             | 1         | 0.08%   |
| System76            | 1         | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Sony VGN-FZ31Z                         | 22        | 1.65%   |
| Lenovo IdeaPad 1 14ADA05 82GW          | 14        | 1.05%   |
| HP G62                                 | 11        | 0.83%   |
| Unknown                                | 11        | 0.83%   |
| Lenovo Legion 5 15ACH6H 82JU           | 10        | 0.75%   |
| HP Pavilion dv6                        | 10        | 0.75%   |
| HP Notebook                            | 9         | 0.68%   |
| Toshiba Satellite C660                 | 8         | 0.6%    |
| HP Pavilion g6                         | 8         | 0.6%    |
| Valve Jupiter                          | 6         | 0.45%   |
| Toshiba Satellite L650                 | 6         | 0.45%   |
| HP Pavilion Notebook                   | 6         | 0.45%   |
| ASUS X555LJ                            | 6         | 0.45%   |
| Apple MacBookPro8,1                    | 6         | 0.45%   |
| Acer Extensa 5620                      | 6         | 0.45%   |
| Toshiba Satellite A200                 | 5         | 0.38%   |
| Lenovo Y520-15IKBN 80WK                | 5         | 0.38%   |
| Lenovo Legion Y530-15ICH 81FV          | 5         | 0.38%   |
| HP Pavilion Gaming Laptop 15-ec2xxx    | 5         | 0.38%   |
| HP OMEN by Laptop                      | 5         | 0.38%   |
| HP Compaq Presario CQ61                | 5         | 0.38%   |
| HP 15                                  | 5         | 0.38%   |
| ASUS X555LD                            | 5         | 0.38%   |
| ASUS X541UV                            | 5         | 0.38%   |
| ASUS VivoBook_ASUSLaptop X512DA_F512DA | 5         | 0.38%   |
| ASUS VivoBook 15_ASUS Laptop X507LA    | 5         | 0.38%   |
| Acer Aspire ES1-520                    | 5         | 0.38%   |
| Toshiba Satellite L500                 | 4         | 0.3%    |
| Toshiba Satellite L40                  | 4         | 0.3%    |
| Lenovo Legion 5 15ARH05H 82B1          | 4         | 0.3%    |
| Lenovo IdeaPad 320-15AST 80XV          | 4         | 0.3%    |
| Lenovo G50-45 80E3                     | 4         | 0.3%    |
| HUAWEI NBLK-WAX9X                      | 4         | 0.3%    |
| HUAWEI BOHK-WAX9X                      | 4         | 0.3%    |
| HP Pavilion 15                         | 4         | 0.3%    |
| HP OMEN by Laptop 15-dc0xxx            | 4         | 0.3%    |
| HP Laptop 15s-eq2xxx                   | 4         | 0.3%    |
| HP Laptop 15s-eq0xxx                   | 4         | 0.3%    |
| HP ENVY 15                             | 4         | 0.3%    |
| HP EliteBook 840 G6                    | 4         | 0.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 122       | 9.17%   |
| Acer Aspire           | 94        | 7.07%   |
| Toshiba Satellite     | 75        | 5.64%   |
| Lenovo IdeaPad        | 73        | 5.49%   |
| HP Pavilion           | 69        | 5.19%   |
| ASUS VivoBook         | 53        | 3.98%   |
| HP EliteBook          | 40        | 3.01%   |
| Dell Latitude         | 39        | 2.93%   |
| HP Laptop             | 28        | 2.11%   |
| Lenovo Legion         | 26        | 1.95%   |
| Sony VGN-FZ31Z        | 22        | 1.65%   |
| HP Compaq             | 19        | 1.43%   |
| Dell XPS              | 18        | 1.35%   |
| HP ProBook            | 17        | 1.28%   |
| HP OMEN               | 15        | 1.13%   |
| Dell Inspiron         | 14        | 1.05%   |
| ASUS ZenBook          | 13        | 0.98%   |
| ASUS ROG              | 12        | 0.9%    |
| Acer Extensa          | 12        | 0.9%    |
| HP G62                | 11        | 0.83%   |
| HP ENVY               | 11        | 0.83%   |
| Unknown               | 11        | 0.83%   |
| Lenovo Yoga           | 9         | 0.68%   |
| HP Notebook           | 9         | 0.68%   |
| Acer Nitro            | 9         | 0.68%   |
| Packard Bell EasyNote | 7         | 0.53%   |
| Fujitsu LIFEBOOK      | 7         | 0.53%   |
| Dell Precision        | 7         | 0.53%   |
| Apple MacBookPro8     | 7         | 0.53%   |
| Valve Jupiter         | 6         | 0.45%   |
| MSI Modern            | 6         | 0.45%   |
| HP 15                 | 6         | 0.45%   |
| ASUS X555LJ           | 6         | 0.45%   |
| ASUS TUF              | 6         | 0.45%   |
| Apple MacBookPro11    | 6         | 0.45%   |
| Lenovo Y520-15IKBN    | 5         | 0.38%   |
| Lenovo ThinkBook      | 5         | 0.38%   |
| HP Stream             | 5         | 0.38%   |
| Chuwi GemiBook        | 5         | 0.38%   |
| ASUS X555LD           | 5         | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 119       | 8.95%   |
| 2019    | 107       | 8.05%   |
| 2018    | 104       | 7.82%   |
| 2021    | 100       | 7.52%   |
| 2010    | 95        | 7.14%   |
| 2015    | 80        | 6.02%   |
| 2013    | 80        | 6.02%   |
| 2014    | 77        | 5.79%   |
| 2007    | 70        | 5.26%   |
| 2008    | 67        | 5.04%   |
| 2017    | 66        | 4.96%   |
| 2012    | 65        | 4.89%   |
| 2016    | 61        | 4.59%   |
| 2009    | 58        | 4.36%   |
| 2022    | 57        | 4.29%   |
| 2011    | 57        | 4.29%   |
| 2023    | 37        | 2.78%   |
| 2006    | 11        | 0.83%   |
| 2024    | 9         | 0.68%   |
| 2005    | 7         | 0.53%   |
| Unknown | 3         | 0.23%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1330      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1210      | 89.23%  |
| Enabled  | 146       | 10.77%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1324      | 99.55%  |
| Yes  | 6         | 0.45%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 344       | 25.5%   |
| 3.01-4.0    | 323       | 23.94%  |
| 8.01-16.0   | 240       | 17.79%  |
| 16.01-24.0  | 199       | 14.75%  |
| 32.01-64.0  | 105       | 7.78%   |
| 1.01-2.0    | 72        | 5.34%   |
| 2.01-3.0    | 26        | 1.93%   |
| 64.01-256.0 | 15        | 1.11%   |
| 24.01-32.0  | 14        | 1.04%   |
| 0.51-1.0    | 11        | 0.82%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 485       | 32.64%  |
| 2.01-3.0   | 368       | 24.76%  |
| 4.01-8.0   | 253       | 17.03%  |
| 3.01-4.0   | 200       | 13.46%  |
| 0.51-1.0   | 100       | 6.73%   |
| 8.01-16.0  | 56        | 3.77%   |
| 16.01-24.0 | 10        | 0.67%   |
| 0.01-0.5   | 9         | 0.61%   |
| 24.01-32.0 | 4         | 0.27%   |
| 32.01-64.0 | 1         | 0.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1008      | 74.17%  |
| 2      | 288       | 21.19%  |
| 3      | 44        | 3.24%   |
| 0      | 11        | 0.81%   |
| 4      | 6         | 0.44%   |
| 5      | 2         | 0.15%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 899       | 67.39%  |
| Yes       | 435       | 32.61%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1076      | 80.3%   |
| No        | 264       | 19.7%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1291      | 97.07%  |
| No        | 39        | 2.93%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1009      | 75.02%  |
| No        | 336       | 24.98%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Notebooks | Percent |
|----------|-----------|---------|
| Portugal | 1330      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lisbon                  | 325       | 22.7%   |
| Porto                   | 152       | 10.61%  |
| Vila Nova de Gaia       | 36        | 2.51%   |
| Funchal                 | 36        | 2.51%   |
| Amadora                 | 30        | 2.09%   |
| Aveiro                  | 27        | 1.89%   |
| Coimbra                 | 26        | 1.82%   |
| Braga                   | 26        | 1.82%   |
| Setúbal                | 21        | 1.47%   |
| Guimaraes               | 18        | 1.26%   |
| Cascais                 | 18        | 1.26%   |
| Loures                  | 15        | 1.05%   |
| Barreiro                | 15        | 1.05%   |
| Almada                  | 15        | 1.05%   |
| Leiria                  | 14        | 0.98%   |
| Faro                    | 14        | 0.98%   |
| Portimao                | 12        | 0.84%   |
| Bragança               | 12        | 0.84%   |
| Póvoa de Varzim        | 11        | 0.77%   |
| Mem Martins             | 11        | 0.77%   |
| Maia                    | 10        | 0.7%    |
| Barcelos                | 10        | 0.7%    |
| Alverca do Ribatejo     | 10        | 0.7%    |
| Viseu                   | 9         | 0.63%   |
| Sintra                  | 9         | 0.63%   |
| Albufeira               | 9         | 0.63%   |
| Santo Tirso             | 8         | 0.56%   |
| Santarém               | 8         | 0.56%   |
| Odivelas                | 8         | 0.56%   |
| Matosinhos Municipality | 8         | 0.56%   |
| Feira                   | 8         | 0.56%   |
| Carnaxide               | 8         | 0.56%   |
| Caldas da Rainha        | 8         | 0.56%   |
| Viana do Castelo        | 7         | 0.49%   |
| Sao Joao da Madeira     | 7         | 0.49%   |
| Paços de Ferreira      | 7         | 0.49%   |
| Lagos                   | 7         | 0.49%   |
| Evora                   | 7         | 0.49%   |
| Vila do Conde           | 6         | 0.42%   |
| Seixal                  | 6         | 0.42%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 252       | 330    | 15.25%  |
| WDC                         | 154       | 203    | 9.32%   |
| Toshiba                     | 152       | 181    | 9.2%    |
| Seagate                     | 146       | 183    | 8.84%   |
| Kingston                    | 117       | 137    | 7.08%   |
| Sandisk                     | 101       | 122    | 6.11%   |
| Unknown                     | 95        | 132    | 5.75%   |
| Crucial                     | 66        | 82     | 4%      |
| Micron Technology           | 55        | 66     | 3.33%   |
| Intel                       | 51        | 84     | 3.09%   |
| Hitachi                     | 50        | 53     | 3.03%   |
| SK hynix                    | 49        | 65     | 2.97%   |
| HGST                        | 48        | 63     | 2.91%   |
| KIOXIA                      | 22        | 34     | 1.33%   |
| Fujitsu                     | 20        | 21     | 1.21%   |
| Phison Electronics          | 18        | 21     | 1.09%   |
| China                       | 18        | 20     | 1.09%   |
| Apple                       | 16        | 18     | 0.97%   |
| A-DATA Technology           | 13        | 13     | 0.79%   |
| S3+                         | 12        | 24     | 0.73%   |
| JMicron Technology          | 11        | 12     | 0.67%   |
| GOODRAM                     | 11        | 11     | 0.67%   |
| Kingston Technology Company | 10        | 10     | 0.61%   |
| LITEON                      | 9         | 10     | 0.54%   |
| KIOXIA-EXCERIA              | 8         | 8      | 0.48%   |
| Unknown                     | 8         | 16     | 0.48%   |
| Silicon Motion              | 7         | 9      | 0.42%   |
| Emtec                       | 7         | 8      | 0.42%   |
| BlueRay                     | 7         | 10     | 0.42%   |
| Transcend                   | 6         | 7      | 0.36%   |
| PNY                         | 6         | 8      | 0.36%   |
| Phison                      | 6         | 6      | 0.36%   |
| Netac                       | 5         | 7      | 0.3%    |
| Micron/Crucial Technology   | 5         | 8      | 0.3%    |
| Maxtor                      | 5         | 13     | 0.3%    |
| USB                         | 4         | 4      | 0.24%   |
| Team                        | 4         | 5      | 0.24%   |
| OCZ                         | 4         | 4      | 0.24%   |
| Union Memory (Shenzhen)     | 3         | 6      | 0.18%   |
| Lenovo                      | 3         | 3      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 22        | 1.29%   |
| Toshiba MQ01ABD100 1TB                               | 21        | 1.23%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 21        | 1.23%   |
| HGST HTS721010A9E630 1TB                             | 21        | 1.23%   |
| Unknown MMC Card  32GB                               | 20        | 1.17%   |
| Unknown MMC Card  64GB                               | 19        | 1.11%   |
| Toshiba MQ01ABF050 500GB                             | 19        | 1.11%   |
| Seagate ST500LT012-1DG142 500GB                      | 17        | 0.99%   |
| Kingston SA400S37240G 240GB SSD                      | 17        | 0.99%   |
| Seagate ST1000LM035-1RK172 1TB                       | 16        | 0.94%   |
| Kingston SA400S37120G 120GB SSD                      | 15        | 0.88%   |
| Crucial CT240M500SSD1 240GB                          | 15        | 0.88%   |
| Unknown MMC64G  64GB                                 | 14        | 0.82%   |
| Kingston SV300S37A120G 120GB SSD                     | 14        | 0.82%   |
| SanDisk NVMe SSD Drive 512GB                         | 12        | 0.7%    |
| Phison PS5013 E13 NVMe Controller 512GB              | 12        | 0.7%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 11        | 0.64%   |
| Toshiba TR200 240GB SSD                              | 10        | 0.58%   |
| Kingston SA400S37480G 480GB SSD                      | 10        | 0.58%   |
| Toshiba MQ04ABF100 1TB                               | 9         | 0.53%   |
| Seagate ST9500325AS 500GB                            | 9         | 0.53%   |
| Sandisk WD Blue SN550 NVMe SSD 256GB                 | 9         | 0.53%   |
| Samsung SSD 850 EVO 500GB                            | 9         | 0.53%   |
| Crucial CT500MX500SSD1 500GB                         | 9         | 0.53%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                     | 8         | 0.47%   |
| Unknown MMC Card  16GB                               | 8         | 0.47%   |
| Seagate ST9320325AS 320GB                            | 8         | 0.47%   |
| Samsung SSD 860 QVO 1TB                              | 8         | 0.47%   |
| Samsung SSD 860 EVO 500GB                            | 8         | 0.47%   |
| Samsung SSD 850 EVO 250GB                            | 8         | 0.47%   |
| Samsung NVMe SSD Drive 512GB                         | 8         | 0.47%   |
| JMicron Generic 500GB                                | 8         | 0.47%   |
| Intel SSDPEKNU512GZ 512GB                            | 8         | 0.47%   |
| Crucial CT240BX500SSD1 240GB                         | 8         | 0.47%   |
| Unknown                                              | 8         | 0.47%   |
| WDC WD3200BEVT-22ZCT0 320GB                          | 7         | 0.41%   |
| WDC WD10JPVX-22JC3T0 1TB                             | 7         | 0.41%   |
| Unknown MMC Card  128GB                              | 7         | 0.41%   |
| SanDisk NVMe SSD Drive 256GB                         | 7         | 0.41%   |
| Samsung SSD 860 EVO 1TB                              | 7         | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 144       | 177    | 29.27%  |
| Toshiba             | 103       | 128    | 20.93%  |
| WDC                 | 98        | 119    | 19.92%  |
| Hitachi             | 50        | 53     | 10.16%  |
| HGST                | 48        | 63     | 9.76%   |
| Fujitsu             | 20        | 21     | 4.07%   |
| Samsung Electronics | 15        | 16     | 3.05%   |
| JMicron Technology  | 8         | 9      | 1.63%   |
| USB                 | 4         | 4      | 0.81%   |
| Intenso             | 1         | 1      | 0.2%    |
| ASMedia             | 1         | 1      | 0.2%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 97        | 123    | 18.06%  |
| Kingston            | 91        | 107    | 16.95%  |
| Crucial             | 62        | 77     | 11.55%  |
| SanDisk             | 33        | 40     | 6.15%   |
| WDC                 | 25        | 29     | 4.66%   |
| Toshiba             | 25        | 27     | 4.66%   |
| China               | 18        | 20     | 3.35%   |
| Apple               | 14        | 14     | 2.61%   |
| Micron Technology   | 13        | 17     | 2.42%   |
| S3+                 | 12        | 24     | 2.23%   |
| Intel               | 12        | 20     | 2.23%   |
| A-DATA Technology   | 12        | 12     | 2.23%   |
| GOODRAM             | 11        | 11     | 2.05%   |
| SK hynix            | 8         | 8      | 1.49%   |
| KIOXIA-EXCERIA      | 7         | 7      | 1.3%    |
| Emtec               | 7         | 8      | 1.3%    |
| Transcend           | 6         | 7      | 1.12%   |
| LITEON              | 6         | 7      | 1.12%   |
| BlueRay             | 6         | 8      | 1.12%   |
| Unknown             | 6         | 14     | 1.12%   |
| PNY                 | 5         | 7      | 0.93%   |
| Netac               | 5         | 7      | 0.93%   |
| Maxtor              | 5         | 13     | 0.93%   |
| Team                | 4         | 5      | 0.74%   |
| OCZ                 | 4         | 4      | 0.74%   |
| 2-Power             | 3         | 4      | 0.56%   |
| Wibtek              | 2         | 2      | 0.37%   |
| Verbatim            | 2         | 2      | 0.37%   |
| Teclast             | 2         | 2      | 0.37%   |
| TCSUNBOW            | 2         | 2      | 0.37%   |
| Seagate             | 2         | 4      | 0.37%   |
| Plextor             | 2         | 2      | 0.37%   |
| LITEONIT            | 2         | 2      | 0.37%   |
| KingDian            | 2         | 2      | 0.37%   |
| INNOVATION IT       | 2         | 2      | 0.37%   |
| Hewlett-Packard     | 2         | 2      | 0.37%   |
| Dogfish             | 2         | 2      | 0.37%   |
| Corsair             | 2         | 2      | 0.37%   |
| VNYEZ               | 1         | 1      | 0.19%   |
| Vaseky              | 1         | 1      | 0.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 500       | 663    | 31.87%  |
| NVMe    | 484       | 690    | 30.85%  |
| HDD     | 477       | 592    | 30.4%   |
| MMC     | 92        | 132    | 5.86%   |
| Unknown | 16        | 18     | 1.02%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 872       | 1218   | 58.29%  |
| NVMe | 483       | 686    | 32.29%  |
| MMC  | 92        | 132    | 6.15%   |
| SAS  | 49        | 59     | 3.28%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 696       | 937    | 73.5%   |
| 0.51-1.0   | 227       | 289    | 23.97%  |
| 1.01-2.0   | 19        | 24     | 2.01%   |
| 3.01-4.0   | 3         | 3      | 0.32%   |
| 4.01-10.0  | 2         | 2      | 0.21%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 428       | 30.46%  |
| 251-500        | 358       | 25.48%  |
| 501-1000       | 191       | 13.59%  |
| 51-100         | 110       | 7.83%   |
| 1-20           | 92        | 6.55%   |
| 1001-2000      | 77        | 5.48%   |
| 21-50          | 54        | 3.84%   |
| More than 3000 | 37        | 2.63%   |
| Unknown        | 37        | 2.63%   |
| 2001-3000      | 21        | 1.49%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 576       | 39.43%  |
| 21-50          | 299       | 20.47%  |
| 101-250        | 191       | 13.07%  |
| 51-100         | 170       | 11.64%  |
| 251-500        | 100       | 6.84%   |
| 501-1000       | 45        | 3.08%   |
| Unknown        | 37        | 2.53%   |
| 1001-2000      | 25        | 1.71%   |
| More than 3000 | 13        | 0.89%   |
| 2001-3000      | 4         | 0.27%   |
| 0              | 1         | 0.07%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Crucial CT240M500SSD1 240GB           | 15        | 16     | 15.46%  |
| Kingston SV300S37A120G 120GB SSD      | 6         | 6      | 6.19%   |
| Seagate ST9320325AS 320GB             | 4         | 5      | 4.12%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 3         | 3      | 3.09%   |
| Kingston SV300S37A240G 240GB SSD      | 3         | 3      | 3.09%   |
| Hitachi HTS545050A7E380 500GB         | 3         | 3      | 3.09%   |
| China G521N256GB                      | 3         | 4      | 3.09%   |
| Seagate ST500LT012-1DG142 500GB       | 2         | 2      | 2.06%   |
| Hitachi HTS543216L9A300 160GB         | 2         | 2      | 2.06%   |
| HGST HTS721010A9E630 1TB              | 2         | 2      | 2.06%   |
| WDC WD7500BPVX-60JC3T0 752GB          | 1         | 2      | 1.03%   |
| WDC WD6400BEVT-22A0RT0 640GB          | 1         | 1      | 1.03%   |
| WDC WD5000BPVT-80HXZT1 500GB          | 1         | 1      | 1.03%   |
| WDC WD3200BEVT-22A23T0 320GB          | 1         | 1      | 1.03%   |
| WDC WD1600BEVT-75A23T0 160GB          | 1         | 1      | 1.03%   |
| WDC WD10JPVT-22A1YT0 1TB              | 1         | 1      | 1.03%   |
| WDC WD10JPCX-24UE4T0 1TB              | 1         | 1      | 1.03%   |
| VNYEZ SSD MSATA 128GB                 | 1         | 1      | 1.03%   |
| USB 3.1 320GB                         | 1         | 1      | 1.03%   |
| Toshiba Q300. 240GB SSD               | 1         | 1      | 1.03%   |
| Toshiba MQ01ACF050 500GB              | 1         | 1      | 1.03%   |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 1.03%   |
| Toshiba MQ01ABD100 1TB                | 1         | 1      | 1.03%   |
| Toshiba MK7575GSX 752GB               | 1         | 1      | 1.03%   |
| Toshiba MK5065GSX 500GB               | 1         | 1      | 1.03%   |
| Toshiba MK3276GSX 320GB               | 1         | 1      | 1.03%   |
| Toshiba MK2561GSYN 250GB              | 1         | 1      | 1.03%   |
| Toshiba HDWL120 2TB                   | 1         | 1      | 1.03%   |
| SK hynix HFS512G39TND-N210A 512GB SSD | 1         | 1      | 1.03%   |
| SK hynix HFS256G32MND-2900A 256GB SSD | 1         | 1      | 1.03%   |
| SK hynix BC711 HFM256GD3JX013N 256GB  | 1         | 1      | 1.03%   |
| Seagate ST9750420AS 752GB             | 1         | 1      | 1.03%   |
| Seagate ST9500325ASG 500GB            | 1         | 1      | 1.03%   |
| Seagate ST9500325AS 500GB             | 1         | 1      | 1.03%   |
| Seagate ST9250827AS 250GB             | 1         | 1      | 1.03%   |
| Seagate ST9160310AS 160GB             | 1         | 2      | 1.03%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 1         | 1      | 1.03%   |
| Seagate ST320LT007-9ZV142 320GB       | 1         | 1      | 1.03%   |
| Seagate ST1000LX015-1U7172 1TB        | 1         | 1      | 1.03%   |
| Seagate ST1000LM049-2GH172 1TB        | 1         | 1      | 1.03%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 19        | 21     | 19.79%  |
| Crucial                   | 15        | 16     | 15.63%  |
| Hitachi                   | 13        | 13     | 13.54%  |
| Toshiba                   | 9         | 9      | 9.38%   |
| Kingston                  | 9         | 10     | 9.38%   |
| WDC                       | 7         | 8      | 7.29%   |
| HGST                      | 4         | 4      | 4.17%   |
| China                     | 4         | 5      | 4.17%   |
| SK hynix                  | 3         | 3      | 3.13%   |
| Samsung Electronics       | 3         | 3      | 3.13%   |
| VNYEZ                     | 1         | 1      | 1.04%   |
| USB                       | 1         | 1      | 1.04%   |
| SanDisk                   | 1         | 1      | 1.04%   |
| OCZ                       | 1         | 1      | 1.04%   |
| Micron/Crucial Technology | 1         | 1      | 1.04%   |
| Micron Technology         | 1         | 1      | 1.04%   |
| LITEON                    | 1         | 1      | 1.04%   |
| Intel                     | 1         | 2      | 1.04%   |
| Fujitsu                   | 1         | 1      | 1.04%   |
| A-DATA Technology         | 1         | 1      | 1.04%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 21     | 34.55%  |
| Hitachi             | 13        | 13     | 23.64%  |
| Toshiba             | 8         | 8      | 14.55%  |
| WDC                 | 7         | 8      | 12.73%  |
| HGST                | 4         | 4      | 7.27%   |
| Samsung Electronics | 2         | 2      | 3.64%   |
| USB                 | 1         | 1      | 1.82%   |
| Fujitsu             | 1         | 1      | 1.82%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 54        | 58     | 56.84%  |
| SSD  | 38        | 42     | 40%     |
| NVMe | 3         | 3      | 3.16%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                    | Notebooks | Drives | Percent |
|--------------------------|-----------|--------|---------|
| HGST HTS541010B7E610 1TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| HGST   | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 860       | 1328   | 61.34%  |
| Works    | 448       | 663    | 31.95%  |
| Malfunc  | 93        | 103    | 6.63%   |
| Failed   | 1         | 1      | 0.07%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 872       | 56.29%  |
| Samsung Electronics              | 156       | 10.07%  |
| AMD                              | 156       | 10.07%  |
| SanDisk                          | 92        | 5.94%   |
| Micron Technology                | 42        | 2.71%   |
| SK hynix                         | 39        | 2.52%   |
| Kingston Technology Company      | 35        | 2.26%   |
| Toshiba America Info Systems     | 27        | 1.74%   |
| Phison Electronics               | 25        | 1.61%   |
| KIOXIA                           | 21        | 1.36%   |
| Nvidia                           | 17        | 1.1%    |
| Silicon Integrated Systems [SiS] | 15        | 0.97%   |
| Micron/Crucial Technology        | 10        | 0.65%   |
| Silicon Motion                   | 8         | 0.52%   |
| Union Memory (Shenzhen)          | 7         | 0.45%   |
| Lite-On Technology               | 6         | 0.39%   |
| JMicron Technology               | 4         | 0.26%   |
| Lenovo                           | 3         | 0.19%   |
| Solidigm                         | 2         | 0.13%   |
| Solid State Storage Technology   | 2         | 0.13%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.13%   |
| ADATA Technology                 | 2         | 0.13%   |
| Silicon Image                    | 1         | 0.06%   |
| Realtek Semiconductor            | 1         | 0.06%   |
| O2 Micro                         | 1         | 0.06%   |
| Marvell Technology Group         | 1         | 0.06%   |
| Enmotus                          | 1         | 0.06%   |
| Apple                            | 1         | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 145       | 8.51%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 86        | 5.05%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 79        | 4.64%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 78        | 4.58%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 72        | 4.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 61        | 3.58%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 59        | 3.46%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 54        | 3.17%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 52        | 3.05%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 51        | 2.99%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 43        | 2.52%   |
| Intel Volume Management Device NVMe RAID Controller                            | 39        | 2.29%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 37        | 2.17%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 36        | 2.11%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 32        | 1.88%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 29        | 1.7%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 28        | 1.64%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 24        | 1.41%   |
| Intel Comet Lake SATA AHCI Controller                                          | 21        | 1.23%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 20        | 1.17%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 19        | 1.12%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 16        | 0.94%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 16        | 0.94%   |
| Intel SSD 660P Series                                                          | 16        | 0.94%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 15        | 0.88%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 14        | 0.82%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 14        | 0.82%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 14        | 0.82%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 14        | 0.82%   |
| Intel Tiger Lake-LP SATA Controller                                            | 13        | 0.76%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 13        | 0.76%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 12        | 0.7%    |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 12        | 0.7%    |
| Micron 3400 NVMe SSD [Hendrix]                                                 | 12        | 0.7%    |
| Kingston Company A1000/U-SNS8154P3 x2 NVMe SSD                                 | 11        | 0.65%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 11        | 0.65%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 11        | 0.65%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 10        | 0.59%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 10        | 0.59%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 10        | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 905       | 55.76%  |
| NVMe | 483       | 29.76%  |
| IDE  | 134       | 8.26%   |
| RAID | 101       | 6.22%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 1067      | 80.23%  |
| AMD     | 262       | 19.7%   |
| Unknown | 1         | 0.08%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 26        | 1.95%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 25        | 1.88%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 23        | 1.73%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 21        | 1.58%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 20        | 1.5%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 19        | 1.43%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 18        | 1.35%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 18        | 1.35%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 18        | 1.35%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 17        | 1.28%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 17        | 1.28%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 16        | 1.2%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 15        | 1.13%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 14        | 1.05%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 14        | 1.05%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 14        | 1.05%   |
| AMD 3020e with Radeon Graphics                | 14        | 1.05%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 13        | 0.98%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 13        | 0.98%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 13        | 0.98%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 12        | 0.9%    |
| Intel Core i3-5005U CPU @ 2.00GHz             | 12        | 0.9%    |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 11        | 0.83%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 11        | 0.83%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 11        | 0.83%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 11        | 0.83%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 10        | 0.75%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 10        | 0.75%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 10        | 0.75%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 10        | 0.75%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz        | 9         | 0.68%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 9         | 0.68%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 9         | 0.68%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 9         | 0.68%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 9         | 0.68%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 9         | 0.68%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 8         | 0.6%    |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 8         | 0.6%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 8         | 0.6%    |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 8         | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 313       | 23.53%  |
| Intel Core i5           | 247       | 18.57%  |
| Other                   | 131       | 9.85%   |
| Intel Core 2 Duo        | 99        | 7.44%   |
| AMD Ryzen 7             | 84        | 6.32%   |
| Intel Core i3           | 83        | 6.24%   |
| Intel Celeron           | 60        | 4.51%   |
| AMD Ryzen 5             | 55        | 4.14%   |
| Intel Atom              | 37        | 2.78%   |
| Intel Pentium Dual-Core | 32        | 2.41%   |
| Intel Pentium Dual      | 26        | 1.95%   |
| Intel Pentium           | 21        | 1.58%   |
| AMD A4                  | 16        | 1.2%    |
| Intel Genuine           | 15        | 1.13%   |
| AMD A8                  | 13        | 0.98%   |
| AMD A6                  | 13        | 0.98%   |
| Intel Core 2            | 11        | 0.83%   |
| AMD Ryzen 9             | 10        | 0.75%   |
| AMD Ryzen 3             | 10        | 0.75%   |
| AMD E2                  | 8         | 0.6%    |
| Intel Pentium M         | 5         | 0.38%   |
| Intel Core              | 5         | 0.38%   |
| AMD Ryzen 7 PRO         | 5         | 0.38%   |
| AMD E                   | 4         | 0.3%    |
| AMD A10                 | 4         | 0.3%    |
| AMD Athlon              | 3         | 0.23%   |
| Intel Core m3           | 2         | 0.15%   |
| Intel Core i9           | 2         | 0.15%   |
| Intel Celeron M         | 2         | 0.15%   |
| AMD Ryzen 5 PRO         | 2         | 0.15%   |
| AMD Mobile Sempron      | 2         | 0.15%   |
| AMD E1                  | 2         | 0.15%   |
| Intel Core m7           | 1         | 0.08%   |
| Intel Celeron Dual-Core | 1         | 0.08%   |
| AMD Turion 64 X2 Mobile | 1         | 0.08%   |
| AMD Turion              | 1         | 0.08%   |
| AMD Quad-Core           | 1         | 0.08%   |
| AMD Phenom II           | 1         | 0.08%   |
| AMD FX                  | 1         | 0.08%   |
| AMD Athlon 64 X2        | 1         | 0.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 641       | 48.2%   |
| 4      | 419       | 31.5%   |
| 8      | 99        | 7.44%   |
| 6      | 88        | 6.62%   |
| 1      | 31        | 2.33%   |
| 10     | 21        | 1.58%   |
| 14     | 13        | 0.98%   |
| 12     | 11        | 0.83%   |
| 16     | 4         | 0.3%    |
| 24     | 2         | 0.15%   |
| 3      | 1         | 0.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1330      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 933       | 69.99%  |
| 1      | 400       | 30.01%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1283      | 96.1%   |
| Unknown        | 29        | 2.17%   |
| 32-bit         | 19        | 1.42%   |
| 64-bit         | 4         | 0.3%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 532       | 38.36%  |
| 0x306a9    | 53        | 3.82%   |
| 0x206a7    | 49        | 3.53%   |
| 0x1067a    | 49        | 3.53%   |
| 0x806ec    | 39        | 2.81%   |
| 0x10676    | 38        | 2.74%   |
| 0x806ea    | 37        | 2.67%   |
| 0x906ea    | 33        | 2.38%   |
| 0x6fd      | 31        | 2.24%   |
| 0x806c1    | 28        | 2.02%   |
| 0x40651    | 28        | 2.02%   |
| 0x306d4    | 22        | 1.59%   |
| 0x20655    | 22        | 1.59%   |
| 0x406e3    | 19        | 1.37%   |
| 0x806e9    | 18        | 1.3%    |
| 0x806eb    | 17        | 1.23%   |
| 0x20652    | 16        | 1.15%   |
| 0x08108109 | 16        | 1.15%   |
| 0x306c3    | 15        | 1.08%   |
| 0x0a50000c | 15        | 1.08%   |
| 0x08200103 | 14        | 1.01%   |
| 0xa0652    | 13        | 0.94%   |
| 0x506e3    | 13        | 0.94%   |
| 0x30678    | 13        | 0.94%   |
| 0x406c4    | 10        | 0.72%   |
| 0x406c3    | 10        | 0.72%   |
| 0x0a50000d | 10        | 0.72%   |
| 0x07030105 | 10        | 0.72%   |
| 0x08108102 | 9         | 0.65%   |
| 0x906e9    | 8         | 0.58%   |
| 0x6f6      | 8         | 0.58%   |
| 0x106ca    | 8         | 0.58%   |
| 0x906a3    | 7         | 0.5%    |
| 0x706e5    | 7         | 0.5%    |
| 0x106e5    | 7         | 0.5%    |
| 0x08608103 | 7         | 0.5%    |
| 0x08600106 | 7         | 0.5%    |
| 0x08600104 | 7         | 0.5%    |
| 0x08600103 | 7         | 0.5%    |
| 0x6d8      | 6         | 0.43%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KabyLake          | 228       | 17.09%  |
| Penryn            | 119       | 8.92%   |
| IvyBridge         | 86        | 6.45%   |
| Haswell           | 84        | 6.3%    |
| Unknown           | 73        | 5.47%   |
| SandyBridge       | 72        | 5.4%    |
| Core              | 63        | 4.72%   |
| Skylake           | 59        | 4.42%   |
| Westmere          | 58        | 4.35%   |
| Silvermont        | 51        | 3.82%   |
| TigerLake         | 50        | 3.75%   |
| Zen 3             | 46        | 3.45%   |
| Broadwell         | 44        | 3.3%    |
| Zen+              | 36        | 2.7%    |
| Zen 2             | 31        | 2.32%   |
| Alderlake Hybrid  | 30        | 2.25%   |
| Zen               | 26        | 1.95%   |
| CometLake         | 24        | 1.8%    |
| Puma              | 22        | 1.65%   |
| Bonnell           | 16        | 1.2%    |
| Excavator         | 15        | 1.12%   |
| P6                | 13        | 0.97%   |
| Jaguar            | 13        | 0.97%   |
| Icelake           | 13        | 0.97%   |
| Goldmont plus     | 10        | 0.75%   |
| Nehalem           | 9         | 0.67%   |
| Goldmont          | 7         | 0.52%   |
| Bobcat            | 6         | 0.45%   |
| Tremont           | 5         | 0.37%   |
| Steamroller       | 5         | 0.37%   |
| Piledriver        | 4         | 0.3%    |
| Meteorlake Hybrid | 4         | 0.3%    |
| K8 Hammer         | 4         | 0.3%    |
| K8 & K10 hybrid   | 4         | 0.3%    |
| K10 Llano         | 2         | 0.15%   |
| K10               | 1         | 0.07%   |
| Gracemont         | 1         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 880       | 50.17%  |
| Nvidia                           | 491       | 27.99%  |
| AMD                              | 372       | 21.21%  |
| Silicon Integrated Systems [SiS] | 11        | 0.63%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 85        | 4.68%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 56        | 3.08%   |
| Intel UHD Graphics 620                                                                   | 51        | 2.81%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 50        | 2.75%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 47        | 2.59%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 47        | 2.59%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 41        | 2.26%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 40        | 2.2%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 39        | 2.15%   |
| Intel HD Graphics 5500                                                                   | 37        | 2.04%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 36        | 1.98%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 34        | 1.87%   |
| Intel Core Processor Integrated Graphics Controller                                      | 33        | 1.82%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 32        | 1.76%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 32        | 1.76%   |
| Intel HD Graphics 620                                                                    | 29        | 1.6%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 29        | 1.6%    |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 28        | 1.54%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 26        | 1.43%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 26        | 1.43%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 26        | 1.43%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 23        | 1.27%   |
| Nvidia G86M [GeForce 8600M GS]                                                           | 22        | 1.21%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 22        | 1.21%   |
| AMD Lucienne                                                                             | 22        | 1.21%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 20        | 1.1%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 19        | 1.05%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 18        | 0.99%   |
| Intel HD Graphics 530                                                                    | 18        | 0.99%   |
| Nvidia GP108M [GeForce MX150]                                                            | 17        | 0.94%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 17        | 0.94%   |
| Intel HD Graphics 630                                                                    | 16        | 0.88%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 16        | 0.88%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 15        | 0.83%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 13        | 0.72%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 13        | 0.72%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 12        | 0.66%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 12        | 0.66%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 12        | 0.66%   |
| AMD Barcelo                                                                              | 12        | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 504       | 37.7%   |
| Intel + Nvidia | 313       | 23.41%  |
| 1 x AMD        | 241       | 18.03%  |
| 1 x Nvidia     | 126       | 9.42%   |
| Intel + AMD    | 58        | 4.34%   |
| AMD + Nvidia   | 52        | 3.89%   |
| 2 x AMD        | 23        | 1.72%   |
| 1 x SiS        | 11        | 0.82%   |
| 2 x Intel      | 7         | 0.52%   |
| Other          | 1         | 0.07%   |
| 2 x Nvidia     | 1         | 0.07%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1072      | 78.94%  |
| Proprietary | 228       | 16.79%  |
| Unknown     | 58        | 4.27%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 818       | 59.8%   |
| 0.01-0.5   | 214       | 15.64%  |
| 1.01-2.0   | 158       | 11.55%  |
| 0.51-1.0   | 81        | 5.92%   |
| 3.01-4.0   | 59        | 4.31%   |
| 5.01-6.0   | 24        | 1.75%   |
| 7.01-8.0   | 10        | 0.73%   |
| 2.01-3.0   | 3         | 0.22%   |
| 8.01-16.0  | 1         | 0.07%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 268       | 18.52%  |
| Chimei Innolux          | 215       | 14.86%  |
| LG Display              | 184       | 12.72%  |
| BOE                     | 177       | 12.23%  |
| Samsung Electronics     | 138       | 9.54%   |
| Goldstar                | 48        | 3.32%   |
| Apple                   | 37        | 2.56%   |
| Chi Mei Optoelectronics | 35        | 2.42%   |
| LG Philips              | 28        | 1.94%   |
| Lenovo                  | 25        | 1.73%   |
| Hewlett-Packard         | 25        | 1.73%   |
| Dell                    | 25        | 1.73%   |
| AOC                     | 25        | 1.73%   |
| Sharp                   | 23        | 1.59%   |
| PANDA                   | 23        | 1.59%   |
| Ancor Communications    | 20        | 1.38%   |
| Philips                 | 10        | 0.69%   |
| BenQ                    | 10        | 0.69%   |
| ASUSTek Computer        | 9         | 0.62%   |
| Sony                    | 8         | 0.55%   |
| InfoVision              | 7         | 0.48%   |
| CSO                     | 7         | 0.48%   |
| CPT                     | 7         | 0.48%   |
| Acer                    | 7         | 0.48%   |
| Valve                   | 6         | 0.41%   |
| Seiko/Epson             | 6         | 0.41%   |
| ViewSonic               | 5         | 0.35%   |
| MSI                     | 5         | 0.35%   |
| HannStar                | 5         | 0.35%   |
| ZTR                     | 3         | 0.21%   |
| Toshiba                 | 3         | 0.21%   |
| Panasonic               | 3         | 0.21%   |
| LGD                     | 3         | 0.21%   |
| LG Electronics          | 3         | 0.21%   |
| HUAWEI                  | 3         | 0.21%   |
| HKC                     | 3         | 0.21%   |
| BOE Technology Group    | 3         | 0.21%   |
| Unknown                 | 2         | 0.14%   |
| Plain Tree Systems      | 2         | 0.14%   |
| Mi                      | 2         | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 14        | 0.95%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 14        | 0.95%   |
| AU Optronics LCD Monitor AUO723C 1366x768 309x173mm 13.9-inch            | 14        | 0.95%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 13        | 0.89%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 13        | 0.89%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 10        | 0.68%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 9         | 0.61%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 8         | 0.54%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 8         | 0.54%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 8         | 0.54%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 677x290mm 29.0-inch                 | 7         | 0.48%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 7         | 0.48%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch          | 7         | 0.48%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 7         | 0.48%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 350x190mm 15.7-inch | 7         | 0.48%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 7         | 0.48%   |
| BOE LCD Monitor BOE0704 1366x768 344x194mm 15.5-inch                     | 7         | 0.48%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 7         | 0.48%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 6         | 0.41%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 6         | 0.41%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch     | 6         | 0.41%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 6         | 0.41%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 6         | 0.41%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 6         | 0.41%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 6         | 0.41%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                    | 6         | 0.41%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                    | 6         | 0.41%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 6         | 0.41%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 5         | 0.34%   |
| LG Philips LCD Monitor LPLDD00 1280x800 331x207mm 15.4-inch              | 5         | 0.34%   |
| LG Display LCD Monitor LGD045D 1366x768 345x194mm 15.6-inch              | 5         | 0.34%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 5         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 5         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15B7 1366x768 344x193mm 15.5-inch          | 5         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 5         | 0.34%   |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 309x173mm 13.9-inch         | 5         | 0.34%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 5         | 0.34%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch           | 5         | 0.34%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch           | 5         | 0.34%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 5         | 0.34%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 529       | 39.36%  |
| 1366x768 (WXGA)    | 423       | 31.47%  |
| 1280x800 (WXGA)    | 72        | 5.36%   |
| 3840x2160 (4K)     | 43        | 3.2%    |
| 2560x1440 (QHD)    | 33        | 2.46%   |
| 1600x900 (HD+)     | 33        | 2.46%   |
| 1920x1200 (WUXGA)  | 31        | 2.31%   |
| 1440x900 (WXGA+)   | 23        | 1.71%   |
| 2880x1800          | 16        | 1.19%   |
| 2560x1600          | 15        | 1.12%   |
| 1680x1050 (WSXGA+) | 15        | 1.12%   |
| 2560x1080          | 13        | 0.97%   |
| 1280x1024 (SXGA)   | 13        | 0.97%   |
| 2160x1440          | 12        | 0.89%   |
| 3840x2400          | 7         | 0.52%   |
| 1024x600           | 7         | 0.52%   |
| 800x1280           | 6         | 0.45%   |
| 3440x1440          | 6         | 0.45%   |
| 1360x768           | 6         | 0.45%   |
| Unknown            | 6         | 0.45%   |
| 1024x768 (XGA)     | 5         | 0.37%   |
| 3200x1800 (QHD+)   | 3         | 0.22%   |
| 2288x1287          | 3         | 0.22%   |
| 3072x1920          | 2         | 0.15%   |
| 2880x1620          | 2         | 0.15%   |
| 2240x1400          | 2         | 0.15%   |
| 1920x1280          | 2         | 0.15%   |
| 1600x1200          | 2         | 0.15%   |
| 1400x1050          | 2         | 0.15%   |
| 640x480            | 1         | 0.07%   |
| 5760x1080          | 1         | 0.07%   |
| 3840x1600          | 1         | 0.07%   |
| 3840x1100          | 1         | 0.07%   |
| 3840x1080          | 1         | 0.07%   |
| 3520x1080          | 1         | 0.07%   |
| 3280x1080          | 1         | 0.07%   |
| 3200x2000          | 1         | 0.07%   |
| 3000x2000          | 1         | 0.07%   |
| 2726x768           | 1         | 0.07%   |
| 2256x1504          | 1         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 661       | 45.81%  |
| 14      | 181       | 12.54%  |
| 13      | 171       | 11.85%  |
| 24      | 61        | 4.23%   |
| 17      | 58        | 4.02%   |
| 21      | 39        | 2.7%    |
| 27      | 36        | 2.49%   |
| 16      | 29        | 2.01%   |
| Unknown | 28        | 1.94%   |
| 31      | 24        | 1.66%   |
| 23      | 24        | 1.66%   |
| 12      | 24        | 1.66%   |
| 34      | 18        | 1.25%   |
| 11      | 18        | 1.25%   |
| 19      | 11        | 0.76%   |
| 10      | 11        | 0.76%   |
| 22      | 9         | 0.62%   |
| 7       | 6         | 0.42%   |
| 40      | 5         | 0.35%   |
| 18      | 5         | 0.35%   |
| 84      | 3         | 0.21%   |
| 28      | 3         | 0.21%   |
| 25      | 3         | 0.21%   |
| 20      | 3         | 0.21%   |
| 72      | 2         | 0.14%   |
| 26      | 2         | 0.14%   |
| 60      | 1         | 0.07%   |
| 54      | 1         | 0.07%   |
| 46      | 1         | 0.07%   |
| 43      | 1         | 0.07%   |
| 37      | 1         | 0.07%   |
| 33      | 1         | 0.07%   |
| 32      | 1         | 0.07%   |
| 8       | 1         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 938       | 65.82%  |
| 201-300     | 140       | 9.82%   |
| 501-600     | 115       | 8.07%   |
| 351-400     | 70        | 4.91%   |
| 401-500     | 62        | 4.35%   |
| 601-700     | 30        | 2.11%   |
| Unknown     | 28        | 1.96%   |
| 701-800     | 20        | 1.4%    |
| 801-900     | 6         | 0.42%   |
| 1-100       | 6         | 0.42%   |
| 1501-2000   | 5         | 0.35%   |
| 1001-1500   | 3         | 0.21%   |
| 101-200     | 1         | 0.07%   |
| 901-1000    | 1         | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1002      | 78.16%  |
| 16/10   | 189       | 14.74%  |
| Unknown | 25        | 1.95%   |
| 21/9    | 20        | 1.56%   |
| 3/2     | 17        | 1.33%   |
| 5/4     | 12        | 0.94%   |
| 4/3     | 9         | 0.7%    |
| 0.67    | 6         | 0.47%   |
| 6/5     | 1         | 0.08%   |
| 3.40    | 1         | 0.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 661       | 45.9%   |
| 81-90          | 284       | 19.72%  |
| 201-250        | 107       | 7.43%   |
| 71-80          | 63        | 4.38%   |
| 351-500        | 44        | 3.06%   |
| 121-130        | 40        | 2.78%   |
| 301-350        | 38        | 2.64%   |
| Unknown        | 28        | 1.94%   |
| 111-120        | 24        | 1.67%   |
| 61-70          | 23        | 1.6%    |
| 151-200        | 23        | 1.6%    |
| 251-300        | 20        | 1.39%   |
| 51-60          | 19        | 1.32%   |
| 141-150        | 13        | 0.9%    |
| 41-50          | 11        | 0.76%   |
| 131-140        | 10        | 0.69%   |
| 501-1000       | 9         | 0.63%   |
| 91-100         | 9         | 0.63%   |
| More than 1000 | 7         | 0.49%   |
| 1-40           | 7         | 0.49%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 518       | 36.79%  |
| 101-120       | 447       | 31.75%  |
| 51-100        | 273       | 19.39%  |
| 161-240       | 102       | 7.24%   |
| More than 240 | 34        | 2.41%   |
| Unknown       | 28        | 1.99%   |
| 1-50          | 6         | 0.43%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1053      | 77.03%  |
| 2     | 218       | 15.95%  |
| 0     | 67        | 4.9%    |
| 3     | 26        | 1.9%    |
| 4     | 3         | 0.22%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 712       | 33.66%  |
| Intel                                  | 619       | 29.27%  |
| Qualcomm Atheros                       | 318       | 15.04%  |
| Broadcom                               | 153       | 7.23%   |
| Marvell Technology Group               | 49        | 2.32%   |
| MediaTek                               | 40        | 1.89%   |
| TP-Link                                | 37        | 1.75%   |
| Broadcom Limited                       | 29        | 1.37%   |
| Ralink                                 | 20        | 0.95%   |
| Silicon Integrated Systems [SiS]       | 15        | 0.71%   |
| Nvidia                                 | 11        | 0.52%   |
| ASIX Electronics                       | 11        | 0.52%   |
| Ralink Technology                      | 7         | 0.33%   |
| Qualcomm Atheros Communications        | 6         | 0.28%   |
| Lenovo                                 | 6         | 0.28%   |
| JMicron Technology                     | 6         | 0.28%   |
| Sierra Wireless                        | 5         | 0.24%   |
| Ericsson Business Mobile Networks      | 5         | 0.24%   |
| DisplayLink                            | 5         | 0.24%   |
| Dell                                   | 5         | 0.24%   |
| ICS Advent                             | 4         | 0.19%   |
| Hewlett-Packard                        | 4         | 0.19%   |
| D-Link                                 | 4         | 0.19%   |
| Attansic Technology                    | 4         | 0.19%   |
| ASUSTek Computer                       | 4         | 0.19%   |
| Samsung Electronics                    | 3         | 0.14%   |
| Qualcomm                               | 3         | 0.14%   |
| Huawei Technologies                    | 3         | 0.14%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.09%   |
| Xiaomi                                 | 2         | 0.09%   |
| Suzhou Motorcomm Electronic Technology | 2         | 0.09%   |
| Mercucys                               | 2         | 0.09%   |
| LSI                                    | 2         | 0.09%   |
| Fibocom                                | 2         | 0.09%   |
| ASR Microelectronics                   | 2         | 0.09%   |
| TRENDnet                               | 1         | 0.05%   |
| Toshiba                                | 1         | 0.05%   |
| T & A Mobile Phones                    | 1         | 0.05%   |
| SparkFun                               | 1         | 0.05%   |
| OPPO Electronics                       | 1         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 423       | 16.95%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 139       | 5.57%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 60        | 2.4%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 55        | 2.2%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 54        | 2.16%   |
| Intel Wi-Fi 6 AX200                                                     | 50        | 2%      |
| Intel Wireless 8265 / 8275                                              | 46        | 1.84%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 43        | 1.72%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 38        | 1.52%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 36        | 1.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 35        | 1.4%    |
| Intel Wi-Fi 6 AX201                                                     | 35        | 1.4%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 33        | 1.32%   |
| Intel Wireless 7265                                                     | 32        | 1.28%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 31        | 1.24%   |
| Intel Wireless 7260                                                     | 30        | 1.2%    |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 29        | 1.16%   |
| Broadcom BCM43142 802.11b/g/n                                           | 29        | 1.16%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 29        | 1.16%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 28        | 1.12%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 28        | 1.12%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 28        | 1.12%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 28        | 1.12%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 27        | 1.08%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                    | 27        | 1.08%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 27        | 1.08%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]         | 25        | 1%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 24        | 0.96%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 22        | 0.88%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 21        | 0.84%   |
| Intel Wireless 8260                                                     | 20        | 0.8%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 20        | 0.8%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 18        | 0.72%   |
| Intel WiFi Link 5100                                                    | 16        | 0.64%   |
| Intel Wireless 3165                                                     | 15        | 0.6%    |
| Intel Wireless 3160                                                     | 15        | 0.6%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 14        | 0.56%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 14        | 0.56%   |
| Intel Ethernet Connection (4) I219-LM                                   | 14        | 0.56%   |
| Intel Centrino Advanced-N 6235                                          | 14        | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 600       | 44.48%  |
| Qualcomm Atheros                | 278       | 20.61%  |
| Realtek Semiconductor           | 225       | 16.68%  |
| Broadcom                        | 120       | 8.9%    |
| MediaTek                        | 34        | 2.52%   |
| Ralink                          | 20        | 1.48%   |
| Broadcom Limited                | 20        | 1.48%   |
| TP-Link                         | 12        | 0.89%   |
| Ralink Technology               | 7         | 0.52%   |
| Qualcomm Atheros Communications | 6         | 0.44%   |
| Sierra Wireless                 | 5         | 0.37%   |
| Dell                            | 5         | 0.37%   |
| D-Link                          | 4         | 0.3%    |
| ASUSTek Computer                | 4         | 0.3%    |
| Mercucys                        | 2         | 0.15%   |
| Fibocom                         | 2         | 0.15%   |
| TRENDnet                        | 1         | 0.07%   |
| Qualcomm                        | 1         | 0.07%   |
| Micro Star International        | 1         | 0.07%   |
| D-Link System                   | 1         | 0.07%   |
| Belkin Components               | 1         | 0.07%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 60        | 4.44%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 55        | 4.07%   |
| Intel Wi-Fi 6 AX200                                                     | 50        | 3.7%    |
| Intel Wireless 8265 / 8275                                              | 46        | 3.4%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 43        | 3.18%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 38        | 2.81%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 36        | 2.66%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 35        | 2.59%   |
| Intel Wi-Fi 6 AX201                                                     | 35        | 2.59%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 33        | 2.44%   |
| Intel Wireless 7265                                                     | 32        | 2.37%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 31        | 2.29%   |
| Intel Wireless 7260                                                     | 30        | 2.22%   |
| Broadcom BCM43142 802.11b/g/n                                           | 29        | 2.15%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 29        | 2.15%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 28        | 2.07%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 28        | 2.07%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 28        | 2.07%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 28        | 2.07%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 27        | 2%      |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 27        | 2%      |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 27        | 2%      |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 22        | 1.63%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 21        | 1.55%   |
| Intel Wireless 8260                                                     | 20        | 1.48%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 20        | 1.48%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 18        | 1.33%   |
| Intel WiFi Link 5100                                                    | 16        | 1.18%   |
| Intel Wireless 3165                                                     | 15        | 1.11%   |
| Intel Wireless 3160                                                     | 15        | 1.11%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 14        | 1.04%   |
| Intel Centrino Advanced-N 6235                                          | 14        | 1.04%   |
| Intel Raptor Lake PCH CNVi WiFi                                         | 13        | 0.96%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 12        | 0.89%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 12        | 0.89%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 12        | 0.89%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 12        | 0.89%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 11        | 0.81%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 10        | 0.74%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 10        | 0.74%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 630       | 56.55%  |
| Intel                                  | 179       | 16.07%  |
| Qualcomm Atheros                       | 77        | 6.91%   |
| Broadcom                               | 54        | 4.85%   |
| Marvell Technology Group               | 49        | 4.4%    |
| TP-Link                                | 26        | 2.33%   |
| Silicon Integrated Systems [SiS]       | 15        | 1.35%   |
| Nvidia                                 | 11        | 0.99%   |
| ASIX Electronics                       | 11        | 0.99%   |
| Broadcom Limited                       | 9         | 0.81%   |
| MediaTek                               | 6         | 0.54%   |
| Lenovo                                 | 6         | 0.54%   |
| JMicron Technology                     | 6         | 0.54%   |
| DisplayLink                            | 5         | 0.45%   |
| ICS Advent                             | 4         | 0.36%   |
| Attansic Technology                    | 4         | 0.36%   |
| Hewlett-Packard                        | 3         | 0.27%   |
| Xiaomi                                 | 2         | 0.18%   |
| Suzhou Motorcomm Electronic Technology | 2         | 0.18%   |
| Samsung Electronics                    | 2         | 0.18%   |
| Qualcomm                               | 2         | 0.18%   |
| LSI                                    | 2         | 0.18%   |
| Huawei Technologies                    | 2         | 0.18%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.09%   |
| T & A Mobile Phones                    | 1         | 0.09%   |
| OPPO Electronics                       | 1         | 0.09%   |
| Microsoft                              | 1         | 0.09%   |
| Archos                                 | 1         | 0.09%   |
| Apple                                  | 1         | 0.09%   |
| Allwinner Technology                   | 1         | 0.09%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 423       | 37.63%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 139       | 12.37%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 54        | 4.8%    |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                           | 27        | 2.4%    |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 25        | 2.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 24        | 2.14%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 14        | 1.25%   |
| Intel Ethernet Connection (4) I219-LM                                          | 14        | 1.25%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 11        | 0.98%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 11        | 0.98%   |
| Intel Ethernet Connection I218-LM                                              | 11        | 0.98%   |
| Intel 82579V Gigabit Network Connection                                        | 10        | 0.89%   |
| Intel 82577LM Gigabit Network Connection                                       | 10        | 0.89%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 9         | 0.8%    |
| Intel Ethernet Connection (6) I219-V                                           | 9         | 0.8%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 9         | 0.8%    |
| Intel Ethernet Connection I219-LM                                              | 8         | 0.71%   |
| Intel Ethernet Connection I217-LM                                              | 8         | 0.71%   |
| Intel Ethernet Connection (3) I218-LM                                          | 8         | 0.71%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 8         | 0.71%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 7         | 0.62%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 7         | 0.62%   |
| Intel Ethernet Connection (6) I219-LM                                          | 7         | 0.62%   |
| Intel Ethernet Connection (4) I219-V                                           | 7         | 0.62%   |
| Intel Ethernet Connection (10) I219-V                                          | 7         | 0.62%   |
| Intel 82567LM Gigabit Network Connection                                       | 7         | 0.62%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 7         | 0.62%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 6         | 0.53%   |
| Realtek Killer E2600 GbE Controller                                            | 6         | 0.53%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 6         | 0.53%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 6         | 0.53%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 6         | 0.53%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 6         | 0.53%   |
| Realtek RTL8125 2.5GbE Controller                                              | 5         | 0.44%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 5         | 0.44%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 5         | 0.44%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                  | 5         | 0.44%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 5         | 0.44%   |
| Intel Ethernet Connection (10) I219-LM                                         | 5         | 0.44%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 5         | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1290      | 54.07%  |
| Ethernet | 1075      | 45.05%  |
| Modem    | 17        | 0.71%   |
| Unknown  | 4         | 0.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1054      | 74.59%  |
| Ethernet | 357       | 25.27%  |
| Modem    | 2         | 0.14%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 944       | 70.87%  |
| 1     | 361       | 27.1%   |
| 0     | 21        | 1.58%   |
| 3     | 6         | 0.45%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 917       | 67.33%  |
| Yes  | 445       | 32.67%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 453       | 44.59%  |
| Realtek Semiconductor           | 120       | 11.81%  |
| IMC Networks                    | 78        | 7.68%   |
| Qualcomm Atheros Communications | 68        | 6.69%   |
| Foxconn / Hon Hai               | 55        | 5.41%   |
| Lite-On Technology              | 49        | 4.82%   |
| Broadcom                        | 42        | 4.13%   |
| Apple                           | 39        | 3.84%   |
| Toshiba                         | 20        | 1.97%   |
| Hewlett-Packard                 | 18        | 1.77%   |
| Realtek                         | 15        | 1.48%   |
| ASUSTek Computer                | 14        | 1.38%   |
| Ralink                          | 12        | 1.18%   |
| Dell                            | 12        | 1.18%   |
| Cambridge Silicon Radio         | 6         | 0.59%   |
| Alps Electric                   | 6         | 0.59%   |
| Ralink Technology               | 2         | 0.2%    |
| Chicony Electronics             | 2         | 0.2%    |
| USI                             | 1         | 0.1%    |
| Roper                           | 1         | 0.1%    |
| MediaTek                        | 1         | 0.1%    |
| Foxconn International           | 1         | 0.1%    |
| Conwise Technology              | 1         | 0.1%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 160       | 15.75%  |
| Intel AX201 Bluetooth                                                               | 88        | 8.66%   |
| Realtek Bluetooth Radio                                                             | 83        | 8.17%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 76        | 7.48%   |
| Intel AX200 Bluetooth                                                               | 49        | 4.82%   |
| IMC Networks Bluetooth Device                                                       | 31        | 3.05%   |
| Intel AX211 Bluetooth                                                               | 29        | 2.85%   |
| Apple Bluetooth Host Controller                                                     | 25        | 2.46%   |
| IMC Networks Bluetooth Radio                                                        | 24        | 2.36%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 21        | 2.07%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 21        | 2.07%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 20        | 1.97%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 19        | 1.87%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 18        | 1.77%   |
| Realtek Bluetooth Radio                                                             | 15        | 1.48%   |
| IMC Networks Wireless_Device                                                        | 15        | 1.48%   |
| Ralink RT3290 Bluetooth                                                             | 12        | 1.18%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 12        | 1.18%   |
| Lite-On Bluetooth Device                                                            | 12        | 1.18%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 12        | 1.18%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 12        | 1.18%   |
| Apple Bluetooth USB Host Controller                                                 | 12        | 1.18%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 11        | 1.08%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 11        | 1.08%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 10        | 0.98%   |
| Intel AX210 Bluetooth                                                               | 8         | 0.79%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 7         | 0.69%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 7         | 0.69%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 7         | 0.69%   |
| Realtek RTL8821A Bluetooth                                                          | 6         | 0.59%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 6         | 0.59%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 6         | 0.59%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 6         | 0.59%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 6         | 0.59%   |
| Toshiba Integrated Bluetooth HCI                                                    | 5         | 0.49%   |
| Toshiba Askey Bluetooth Module                                                      | 5         | 0.49%   |
| Lite-On BCM43142A0                                                                  | 5         | 0.49%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 5         | 0.49%   |
| Foxconn / Hon Hai BCM43142A0 broadcom bluetooth                                     | 5         | 0.49%   |
| Dell DW375 Bluetooth Module                                                         | 5         | 0.49%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1019      | 60.94%  |
| AMD                                          | 313       | 18.72%  |
| Nvidia                                       | 215       | 12.86%  |
| Silicon Integrated Systems [SiS]             | 15        | 0.9%    |
| C-Media Electronics                          | 15        | 0.9%    |
| GN Netcom                                    | 10        | 0.6%    |
| Realtek Semiconductor                        | 9         | 0.54%   |
| Plantronics                                  | 7         | 0.42%   |
| Lenovo                                       | 7         | 0.42%   |
| Hewlett-Packard                              | 6         | 0.36%   |
| Texas Instruments                            | 5         | 0.3%    |
| JMTek                                        | 5         | 0.3%    |
| Razer USA                                    | 4         | 0.24%   |
| Logitech                                     | 4         | 0.24%   |
| Creative Technology                          | 4         | 0.24%   |
| Sony                                         | 3         | 0.18%   |
| Kingston Technology                          | 2         | 0.12%   |
| Generalplus Technology                       | 2         | 0.12%   |
| Corsair                                      | 2         | 0.12%   |
| ASUSTek Computer                             | 2         | 0.12%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.06%   |
| XMOS                                         | 1         | 0.06%   |
| Trust                                        | 1         | 0.06%   |
| Sennheiser Communications                    | 1         | 0.06%   |
| Samsung Electronics                          | 1         | 0.06%   |
| Micro Star International                     | 1         | 0.06%   |
| M2Tech                                       | 1         | 0.06%   |
| KTMICRO                                      | 1         | 0.06%   |
| JBL                                          | 1         | 0.06%   |
| Huawei Technologies                          | 1         | 0.06%   |
| GYROCOM C&C                                  | 1         | 0.06%   |
| Guillemot                                    | 1         | 0.06%   |
| Focusrite-Novation                           | 1         | 0.06%   |
| ESS Technology                               | 1         | 0.06%   |
| EGO SYStems                                  | 1         | 0.06%   |
| DSEA A/S                                     | 1         | 0.06%   |
| DEXP U700 microphone                         | 1         | 0.06%   |
| Dell                                         | 1         | 0.06%   |
| Conexant Systems                             | 1         | 0.06%   |
| Conexant                                     | 1         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 170       | 8.48%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 118       | 5.89%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 94        | 4.69%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 83        | 4.14%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 68        | 3.39%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 67        | 3.34%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 64        | 3.19%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 60        | 2.99%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 59        | 2.94%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 50        | 2.5%    |
| Intel Cannon Lake PCH cAVS                                                                        | 48        | 2.4%    |
| AMD FCH Azalia Controller                                                                         | 48        | 2.4%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 47        | 2.35%   |
| Intel 8 Series HD Audio Controller                                                                | 46        | 2.3%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 44        | 2.2%    |
| Intel Broadwell-U Audio Controller                                                                | 44        | 2.2%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 42        | 2.1%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 42        | 2.1%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 38        | 1.9%    |
| AMD Kabini HDMI/DP Audio                                                                          | 37        | 1.85%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 33        | 1.65%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 32        | 1.6%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 32        | 1.6%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 25        | 1.25%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 23        | 1.15%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 22        | 1.1%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 20        | 1%      |
| Intel Comet Lake PCH cAVS                                                                         | 19        | 0.95%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 18        | 0.9%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 18        | 0.9%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 16        | 0.8%    |
| Nvidia TU106 High Definition Audio Controller                                                     | 15        | 0.75%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 15        | 0.75%   |
| Intel CM238 HD Audio Controller                                                                   | 15        | 0.75%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 15        | 0.75%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 15        | 0.75%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 15        | 0.75%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 14        | 0.7%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 14        | 0.7%    |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 14        | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 232       | 30.25%  |
| SK hynix            | 173       | 22.56%  |
| Unknown             | 86        | 11.21%  |
| Micron Technology   | 82        | 10.69%  |
| Kingston            | 64        | 8.34%   |
| Crucial             | 23        | 3%      |
| Ramaxel Technology  | 18        | 2.35%   |
| Elpida              | 16        | 2.09%   |
| G.Skill             | 12        | 1.56%   |
| Corsair             | 11        | 1.43%   |
| A-DATA Technology   | 11        | 1.43%   |
| Unknown             | 7         | 0.91%   |
| Team                | 4         | 0.52%   |
| Unknown (ABCD)      | 3         | 0.39%   |
| Transcend           | 3         | 0.39%   |
| Nanya Technology    | 3         | 0.39%   |
| Teikon              | 2         | 0.26%   |
| Lexar               | 2         | 0.26%   |
| Unknown (268C)      | 1         | 0.13%   |
| Unknown (0x7301)    | 1         | 0.13%   |
| Unigen              | 1         | 0.13%   |
| Toshiba             | 1         | 0.13%   |
| Smart               | 1         | 0.13%   |
| Silicon Power       | 1         | 0.13%   |
| PUSKILL             | 1         | 0.13%   |
| Netlist             | 1         | 0.13%   |
| Kllisre             | 1         | 0.13%   |
| GOODRAM             | 1         | 0.13%   |
| Goldkey             | 1         | 0.13%   |
| Essencore Limited   | 1         | 0.13%   |
| ASint Technology    | 1         | 0.13%   |
| Apacer              | 1         | 0.13%   |
| 48spaces            | 1         | 0.13%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2                             | 26        | 3.23%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 18        | 2.24%   |
| Samsung RAM M471A5244CB0-CWE 4096MB Row Of Chips DDR4 3200MT/s | 16        | 1.99%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s         | 11        | 1.37%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s         | 10        | 1.24%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s          | 10        | 1.24%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s          | 9         | 1.12%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 8         | 0.99%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s          | 8         | 0.99%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s         | 7         | 0.87%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s          | 7         | 0.87%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s         | 7         | 0.87%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s          | 7         | 0.87%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s          | 7         | 0.87%   |
| Unknown                                                        | 7         | 0.87%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s         | 6         | 0.75%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 6         | 0.75%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s          | 6         | 0.75%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s          | 6         | 0.75%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 5         | 0.62%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s   | 5         | 0.62%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s         | 5         | 0.62%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s        | 5         | 0.62%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 5         | 0.62%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s          | 5         | 0.62%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s          | 5         | 0.62%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s         | 5         | 0.62%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s           | 5         | 0.62%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s         | 4         | 0.5%    |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s         | 4         | 0.5%    |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s         | 4         | 0.5%    |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s          | 4         | 0.5%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s          | 4         | 0.5%    |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s       | 4         | 0.5%    |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s         | 4         | 0.5%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s          | 4         | 0.5%    |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s           | 4         | 0.5%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s          | 4         | 0.5%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s           | 4         | 0.5%    |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s          | 4         | 0.5%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 319       | 48.7%   |
| DDR3    | 178       | 27.18%  |
| DDR2    | 60        | 9.16%   |
| LPDDR4  | 26        | 3.97%   |
| LPDDR5  | 20        | 3.05%   |
| LPDDR3  | 20        | 3.05%   |
| SDRAM   | 13        | 1.98%   |
| DDR5    | 13        | 1.98%   |
| DDR     | 4         | 0.61%   |
| Unknown | 2         | 0.31%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 560       | 85.37%  |
| Row Of Chips | 87        | 13.26%  |
| DIMM         | 4         | 0.61%   |
| Chip         | 3         | 0.46%   |
| Unknown      | 2         | 0.3%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Notebooks | Percent |
|---------|-----------|---------|
| 8192    | 254       | 35.52%  |
| 4096    | 188       | 26.29%  |
| 16384   | 119       | 16.64%  |
| 2048    | 101       | 14.13%  |
| 1024    | 25        | 3.5%    |
| 32768   | 22        | 3.08%   |
| 512     | 5         | 0.7%    |
| Unknown | 1         | 0.14%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 148       | 21.17%  |
| 3200    | 143       | 20.46%  |
| 1600    | 112       | 16.02%  |
| Unknown | 48        | 6.87%   |
| 2400    | 38        | 5.44%   |
| 2133    | 30        | 4.29%   |
| 1334    | 26        | 3.72%   |
| 1333    | 19        | 2.72%   |
| 667     | 17        | 2.43%   |
| 6400    | 13        | 1.86%   |
| 1067    | 13        | 1.86%   |
| 8400    | 12        | 1.72%   |
| 4267    | 11        | 1.57%   |
| 3266    | 9         | 1.29%   |
| 4800    | 7         | 1%      |
| 4199    | 7         | 1%      |
| 5600    | 6         | 0.86%   |
| 1867    | 5         | 0.72%   |
| 800     | 5         | 0.72%   |
| 533     | 5         | 0.72%   |
| 7500    | 4         | 0.57%   |
| 4266    | 3         | 0.43%   |
| 1066    | 3         | 0.43%   |
| 975     | 3         | 0.43%   |
| 7467    | 2         | 0.29%   |
| 2933    | 2         | 0.29%   |
| 2048    | 2         | 0.29%   |
| 1866    | 2         | 0.29%   |
| 3733    | 1         | 0.14%   |
| 3000    | 1         | 0.14%   |
| 1200    | 1         | 0.14%   |
| 666     | 1         | 0.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 5         | 50%     |
| Seiko Epson            | 2         | 20%     |
| STMicroelectronics     | 1         | 10%     |
| Samsung Electronics    | 1         | 10%     |
| Panasonic (Matsushita) | 1         | 10%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| STMicroelectronics LED badge -- mini LED display -- 11x44             | 1         | 10%     |
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 1         | 10%     |
| Seiko Epson AcuLaser C1700                                            | 1         | 10%     |
| Samsung ML-1640 Series Laser Printer                                  | 1         | 10%     |
| Panasonic (Matsushita) KX-FLB851SP                                    | 1         | 10%     |
| HP OfficeJet 3830 series                                              | 1         | 10%     |
| HP LaserJet CP 1025                                                   | 1         | 10%     |
| HP DeskJet F4100 Printer series                                       | 1         | 10%     |
| HP Deskjet 3050A                                                      | 1         | 10%     |
| HP DeskJet 2130 series                                                | 1         | 10%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Notebooks | Percent |
|----------------|-----------|---------|
| Mustek Systems | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Mustek Systems BearPaw 2448 CU Pro | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 301       | 25.25%  |
| IMC Networks                           | 155       | 13%     |
| Realtek Semiconductor                  | 86        | 7.21%   |
| Bison Electronics                      | 72        | 6.04%   |
| Suyin                                  | 63        | 5.29%   |
| Quanta                                 | 63        | 5.29%   |
| Microdia                               | 51        | 4.28%   |
| Sunplus Innovation Technology          | 44        | 3.69%   |
| Cheng Uei Precision Industry (Foxlink) | 41        | 3.44%   |
| Syntek                                 | 37        | 3.1%    |
| Ricoh                                  | 36        | 3.02%   |
| Lite-On Technology                     | 34        | 2.85%   |
| Apple                                  | 29        | 2.43%   |
| Luxvisions Innotech Limited            | 25        | 2.1%    |
| Acer                                   | 23        | 1.93%   |
| Silicon Motion                         | 19        | 1.59%   |
| Sonix Technology                       | 14        | 1.17%   |
| Logitech                               | 12        | 1.01%   |
| Alcor Micro                            | 9         | 0.76%   |
| Lenovo                                 | 8         | 0.67%   |
| Importek                               | 8         | 0.67%   |
| Z-Star Microelectronics                | 7         | 0.59%   |
| Generalplus Technology                 | 5         | 0.42%   |
| SunplusIT                              | 4         | 0.34%   |
| Samsung Electronics                    | 4         | 0.34%   |
| Creative Technology                    | 4         | 0.34%   |
| WaveRider Communications               | 3         | 0.25%   |
| icSpring                               | 3         | 0.25%   |
| ALi                                    | 3         | 0.25%   |
| Y Media                                | 2         | 0.17%   |
| Shinetech                              | 2         | 0.17%   |
| Primax Electronics                     | 2         | 0.17%   |
| Microsoft                              | 2         | 0.17%   |
| MacroSilicon                           | 2         | 0.17%   |
| kingcome                               | 2         | 0.17%   |
| Genesys Logic                          | 2         | 0.17%   |
| DigiTech                               | 2         | 0.17%   |
| Anker PowerConf C200                   | 2         | 0.17%   |
| Trust                                  | 1         | 0.08%   |
| Tripath Technology                     | 1         | 0.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 45        | 3.76%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 44        | 3.68%   |
| IMC Networks Integrated Camera                      | 34        | 2.84%   |
| Chicony HD WebCam                                   | 27        | 2.26%   |
| Ricoh Visual Communication Camera VGP-VCC8 [R5U870] | 23        | 1.92%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 21        | 1.76%   |
| Chicony USB2.0 VGA UVC WebCam                       | 20        | 1.67%   |
| Microdia Integrated_Webcam_HD                       | 17        | 1.42%   |
| Chicony USB 2.0 Camera                              | 17        | 1.42%   |
| Bison Integrated Camera                             | 17        | 1.42%   |
| Syntek Integrated Camera                            | 15        | 1.25%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 15        | 1.25%   |
| Realtek EasyCamera                                  | 14        | 1.17%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 13        | 1.09%   |
| Chicony TOSHIBA Web Camera - HD                     | 13        | 1.09%   |
| Chicony CNF9055 Toshiba Webcam                      | 13        | 1.09%   |
| Realtek USB Camera                                  | 12        | 1%      |
| Realtek Integrated_Webcam_HD                        | 12        | 1%      |
| Quanta HP Wide Vision HD Camera                     | 12        | 1%      |
| Sunplus HD WebCam                                   | 11        | 0.92%   |
| Quanta HP TrueVision HD Camera                      | 11        | 0.92%   |
| Lite-On Integrated Camera                           | 11        | 0.92%   |
| Chicony HP Truevision HD                            | 11        | 0.92%   |
| IMC Networks HD Camera                              | 10        | 0.84%   |
| Bison HD Webcam                                     | 10        | 0.84%   |
| Apple FaceTime HD Camera                            | 9         | 0.75%   |
| Apple Built-in iSight                               | 9         | 0.75%   |
| Suyin USB 2.0 Camera                                | 8         | 0.67%   |
| Suyin HP Truevision HD                              | 8         | 0.67%   |
| Realtek 2SF022                                      | 8         | 0.67%   |
| IMC Networks ov9734_azurewave_camera                | 8         | 0.67%   |
| Chicony VGA Webcam                                  | 8         | 0.67%   |
| Chicony USB2.0 Camera                               | 8         | 0.67%   |
| Chicony Integrated Camera (1280x720@30)             | 8         | 0.67%   |
| Chicony HP HD Camera                                | 8         | 0.67%   |
| Syntek Lenovo EasyCamera                            | 7         | 0.59%   |
| Realtek USB2.0 HD UVC WebCam                        | 7         | 0.59%   |
| Realtek HD WebCam                                   | 7         | 0.59%   |
| Quanta HP HD Camera                                 | 7         | 0.59%   |
| Chicony USB2.0 HD UVC WebCam                        | 7         | 0.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 66        | 34.92%  |
| Validity Sensors                   | 58        | 30.69%  |
| Shenzhen Goodix Technology         | 29        | 15.34%  |
| AuthenTec                          | 11        | 5.82%   |
| Elan Microelectronics              | 8         | 4.23%   |
| Upek                               | 6         | 3.17%   |
| LighTuning Technology              | 5         | 2.65%   |
| STMicroelectronics                 | 3         | 1.59%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 1.59%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 22        | 11.64%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 14        | 7.41%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 8         | 4.23%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 8         | 4.23%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 4.23%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 6         | 3.17%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 6         | 3.17%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 6         | 3.17%   |
| Synaptics Fingerprint reader [HP G6]                                       | 6         | 3.17%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 5         | 2.65%   |
| Validity Sensors Synaptics WBDI                                            | 5         | 2.65%   |
| Validity Sensors Fingerprint scanner                                       | 5         | 2.65%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 5         | 2.65%   |
| Synaptics UWP WBDI Device                                                  | 5         | 2.65%   |
| Synaptics Prometheus Fingerprint Reader                                    | 5         | 2.65%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 4         | 2.12%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 2.12%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 4         | 2.12%   |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 2.12%   |
| Elan ELAN:Fingerprint                                                      | 4         | 2.12%   |
| Elan ELAN:ARM-M4                                                           | 4         | 2.12%   |
| AuthenTec AES2810                                                          | 4         | 2.12%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 1.59%   |
| Validity Sensors VFS491                                                    | 3         | 1.59%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 1.59%   |
| Synaptics WBDI Device                                                      | 3         | 1.59%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 1.59%   |
| STMicroelectronics Fingerprint Reader                                      | 3         | 1.59%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 1.59%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 3         | 1.59%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 1.59%   |
| AuthenTec AES1600                                                          | 3         | 1.59%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 1.06%   |
| Synaptics WBDI                                                             | 2         | 1.06%   |
| LighTuning Fingerprint Reader                                              | 2         | 1.06%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 1.06%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 0.53%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.53%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.53%   |
| Synaptics UWP WBDI                                                         | 1         | 0.53%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 32        | 37.65%  |
| Broadcom              | 27        | 31.76%  |
| O2 Micro              | 6         | 7.06%   |
| Gemalto (was Gemplus) | 6         | 7.06%   |
| Upek                  | 3         | 3.53%   |
| Lenovo                | 3         | 3.53%   |
| SCM Microsystems      | 2         | 2.35%   |
| Realtek Semiconductor | 2         | 2.35%   |
| Yubico.com            | 1         | 1.18%   |
| CHERRY                | 1         | 1.18%   |
| Bit4id                | 1         | 1.18%   |
| Advanced Card Systems | 1         | 1.18%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 32        | 37.65%  |
| Broadcom 58200                                                               | 9         | 10.59%  |
| Broadcom 5880                                                                | 8         | 9.41%   |
| Broadcom BCM5880 Secure Applications Processor                               | 7         | 8.24%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 5         | 5.88%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 4         | 4.71%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 3.53%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 3.53%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 3.53%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 2.35%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 2.35%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 2.35%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 1.18%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.18%   |
| CHERRY SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 1.18%   |
| Bit4id miniLector EVO                                                        | 1         | 1.18%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 1.18%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 856       | 62.12%  |
| 1     | 398       | 28.88%  |
| 2     | 99        | 7.18%   |
| 3     | 19        | 1.38%   |
| 4     | 4         | 0.29%   |
| 5     | 2         | 0.15%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 187       | 29.04%  |
| Graphics card            | 181       | 28.11%  |
| Net/wireless             | 69        | 10.71%  |
| Chipcard                 | 68        | 10.56%  |
| Multimedia controller    | 55        | 8.54%   |
| Camera                   | 22        | 3.42%   |
| Bluetooth                | 18        | 2.8%    |
| Card reader              | 13        | 2.02%   |
| Communication controller | 9         | 1.4%    |
| Storage                  | 7         | 1.09%   |
| Modem                    | 4         | 0.62%   |
| Flash memory             | 4         | 0.62%   |
| Net/ethernet             | 3         | 0.47%   |
| Network                  | 2         | 0.31%   |
| Storage/ata              | 1         | 0.16%   |
| Sound                    | 1         | 0.16%   |

