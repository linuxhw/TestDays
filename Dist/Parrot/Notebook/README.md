Parrot - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Parrot.

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

Total: 349

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | ZenBook UX482EA_UX482EA     | [a65efa454e](https://linux-hardware.org/?probe=a65efa454e) | Nov 01, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | [3380dfae20](https://linux-hardware.org/?probe=3380dfae20) | Nov 01, 2022 |
| HP            | Victus by Laptop 16-d1xx... | [f141a6cddf](https://linux-hardware.org/?probe=f141a6cddf) | Oct 31, 2022 |
| HP            | Victus by Laptop 16-d1xx... | [b9890126af](https://linux-hardware.org/?probe=b9890126af) | Oct 31, 2022 |
| Dell          | Latitude 3350               | [e545da88bf](https://linux-hardware.org/?probe=e545da88bf) | Oct 28, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [afd2f21c66](https://linux-hardware.org/?probe=afd2f21c66) | Oct 26, 2022 |
| Acer          | Aspire ES1-111M             | [ebff9e2fa5](https://linux-hardware.org/?probe=ebff9e2fa5) | Oct 25, 2022 |
| Dell          | Latitude E5500              | [10cb5545fd](https://linux-hardware.org/?probe=10cb5545fd) | Oct 24, 2022 |
| Dell          | Inspiron 13-7378            | [fbd3c71f34](https://linux-hardware.org/?probe=fbd3c71f34) | Oct 23, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [6a85eb0ff4](https://linux-hardware.org/?probe=6a85eb0ff4) | Oct 14, 2022 |
| Clevo         | W25xHPx                     | [04196b2306](https://linux-hardware.org/?probe=04196b2306) | Oct 13, 2022 |
| Irbis         | NB121                       | [04f312f46b](https://linux-hardware.org/?probe=04f312f46b) | Oct 13, 2022 |
| Irbis         | NB121                       | [ff99468633](https://linux-hardware.org/?probe=ff99468633) | Oct 13, 2022 |
| Toshiba       | Satellite C75D-B            | [7ba818df9e](https://linux-hardware.org/?probe=7ba818df9e) | Oct 11, 2022 |
| Alienware     | m15 R7                      | [79aa2b2dd4](https://linux-hardware.org/?probe=79aa2b2dd4) | Oct 10, 2022 |
| Lenovo        | LEGIONC7 82EH               | [880c4773fd](https://linux-hardware.org/?probe=880c4773fd) | Oct 06, 2022 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [f02e3f9e3b](https://linux-hardware.org/?probe=f02e3f9e3b) | Oct 04, 2022 |
| Lenovo        | ThinkPad E570 20H5009MUS    | [5b3df02ed5](https://linux-hardware.org/?probe=5b3df02ed5) | Oct 03, 2022 |
| HP            | Unknown                     | [0a6433c4fe](https://linux-hardware.org/?probe=0a6433c4fe) | Oct 03, 2022 |
| Lenovo        | ThinkPad E570 20H5009MUS    | [70451644fc](https://linux-hardware.org/?probe=70451644fc) | Oct 03, 2022 |
| BANGHO        | GAMER GM-X 15s              | [d3e2d5452a](https://linux-hardware.org/?probe=d3e2d5452a) | Oct 03, 2022 |
| HP            | Presario CQ58               | [4bb50cd19d](https://linux-hardware.org/?probe=4bb50cd19d) | Sep 28, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | [9616464154](https://linux-hardware.org/?probe=9616464154) | Sep 26, 2022 |
| Dell          | Latitude 3350               | [62c380dcd0](https://linux-hardware.org/?probe=62c380dcd0) | Sep 22, 2022 |
| MSI           | Katana GF66 12UD            | [c0c6c57498](https://linux-hardware.org/?probe=c0c6c57498) | Sep 17, 2022 |
| HUAWEI        | BOHB-WAX9                   | [5dc824a596](https://linux-hardware.org/?probe=5dc824a596) | Sep 16, 2022 |
| Toshiba       | Satellite C855D             | [bae94a45be](https://linux-hardware.org/?probe=bae94a45be) | Sep 13, 2022 |
| HP            | Laptop 15s-eq1xxx           | [f8de7730b6](https://linux-hardware.org/?probe=f8de7730b6) | Sep 11, 2022 |
| Dell          | Inspiron 14 5410            | [315af016c7](https://linux-hardware.org/?probe=315af016c7) | Sep 09, 2022 |
| Dell          | Latitude E6400              | [1de889aa64](https://linux-hardware.org/?probe=1de889aa64) | Sep 05, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [b50b1adb0f](https://linux-hardware.org/?probe=b50b1adb0f) | Sep 01, 2022 |
| Acer          | Predator PT516-51s          | [5739f0b1a0](https://linux-hardware.org/?probe=5739f0b1a0) | Aug 28, 2022 |
| Acer          | Aspire A517-52              | [b61f6861a6](https://linux-hardware.org/?probe=b61f6861a6) | Aug 21, 2022 |
| Standard      | Unknown                     | [782f229d6c](https://linux-hardware.org/?probe=782f229d6c) | Aug 17, 2022 |
| Panasonic     | CF-31JBGNNDM                | [008621e9e0](https://linux-hardware.org/?probe=008621e9e0) | Aug 14, 2022 |
| Lenovo        | ThinkPad T420 4180MNU       | [437387fdc3](https://linux-hardware.org/?probe=437387fdc3) | Aug 10, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | [47608d95ea](https://linux-hardware.org/?probe=47608d95ea) | Aug 10, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | [0bd14e553d](https://linux-hardware.org/?probe=0bd14e553d) | Aug 10, 2022 |
| Lenovo        | ThinkPad T420 4180MNU       | [dae7cc7b69](https://linux-hardware.org/?probe=dae7cc7b69) | Aug 08, 2022 |
| Dell          | Inspiron 13-7359            | [1a13c37dce](https://linux-hardware.org/?probe=1a13c37dce) | Aug 08, 2022 |
| HP            | Laptop 15-dy2xxx            | [a7e9a050ea](https://linux-hardware.org/?probe=a7e9a050ea) | Aug 02, 2022 |
| HP            | EliteBook 850 G6            | [1dca756b58](https://linux-hardware.org/?probe=1dca756b58) | Jul 31, 2022 |
| Dell          | Latitude E6420              | [a6b2ee6088](https://linux-hardware.org/?probe=a6b2ee6088) | Jul 30, 2022 |
| HP            | 250 G2                      | [5650fd3dd6](https://linux-hardware.org/?probe=5650fd3dd6) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH532/G21          | [99fd83f85d](https://linux-hardware.org/?probe=99fd83f85d) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH532/G21          | [e64903db3d](https://linux-hardware.org/?probe=e64903db3d) | Jul 28, 2022 |
| Acer          | Nitro AN515-57              | [26be63e8a0](https://linux-hardware.org/?probe=26be63e8a0) | Jul 25, 2022 |
| Acer          | Nitro AN515-57              | [0bacf44374](https://linux-hardware.org/?probe=0bacf44374) | Jul 23, 2022 |
| Sony          | VPCSB1C5E                   | [184e5b179e](https://linux-hardware.org/?probe=184e5b179e) | Jul 23, 2022 |
| Acer          | Nitro AN515-57              | [4d3cf557ba](https://linux-hardware.org/?probe=4d3cf557ba) | Jul 23, 2022 |
| Lenovo        | Z40-70 80E6                 | [e77b84e593](https://linux-hardware.org/?probe=e77b84e593) | Jul 22, 2022 |
| Acer          | Predator PT516-51s          | [8337c958e2](https://linux-hardware.org/?probe=8337c958e2) | Jul 22, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [90cf247d2d](https://linux-hardware.org/?probe=90cf247d2d) | Jul 20, 2022 |
| HP            | Laptop 15-dy2xxx            | [2d31c995c8](https://linux-hardware.org/?probe=2d31c995c8) | Jul 19, 2022 |
| HP            | Laptop 15-dy2xxx            | [2c55e11e85](https://linux-hardware.org/?probe=2c55e11e85) | Jul 18, 2022 |
| Unknown       | Unknown                     | [a7de2e1421](https://linux-hardware.org/?probe=a7de2e1421) | Jul 14, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [713bd9f4b0](https://linux-hardware.org/?probe=713bd9f4b0) | Jul 14, 2022 |
| Dell          | Inspiron MM061              | [49e71e9dc1](https://linux-hardware.org/?probe=49e71e9dc1) | Jul 13, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [2ffa772ac9](https://linux-hardware.org/?probe=2ffa772ac9) | Jul 10, 2022 |
| Apple         | MacBookPro5,1               | [fd79c5481a](https://linux-hardware.org/?probe=fd79c5481a) | Jul 09, 2022 |
| Lenovo        | ThinkPad L430 2465C32       | [f088c4ae11](https://linux-hardware.org/?probe=f088c4ae11) | Jul 09, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [48aa7eac9f](https://linux-hardware.org/?probe=48aa7eac9f) | Jul 09, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [8a96de43eb](https://linux-hardware.org/?probe=8a96de43eb) | Jul 08, 2022 |
| Acer          | Predator PT516-51s          | [9309da8b72](https://linux-hardware.org/?probe=9309da8b72) | Jul 05, 2022 |
| HP            | Laptop 15-bs2xx             | [fc35a0726c](https://linux-hardware.org/?probe=fc35a0726c) | Jul 03, 2022 |
| HP            | Pavilion dv6                | [ff3ebff8ff](https://linux-hardware.org/?probe=ff3ebff8ff) | Jun 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [86c0fc94e6](https://linux-hardware.org/?probe=86c0fc94e6) | Jun 23, 2022 |
| HP            | ProBook 440 G5              | [2969400046](https://linux-hardware.org/?probe=2969400046) | Jun 20, 2022 |
| Toshiba       | Satellite-L845              | [d617282ee0](https://linux-hardware.org/?probe=d617282ee0) | Jun 18, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [4cafd85b65](https://linux-hardware.org/?probe=4cafd85b65) | Jun 15, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [2a3c65eda7](https://linux-hardware.org/?probe=2a3c65eda7) | Jun 10, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [e2efffbd81](https://linux-hardware.org/?probe=e2efffbd81) | Jun 07, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [c509b12c63](https://linux-hardware.org/?probe=c509b12c63) | Jun 07, 2022 |
| Dell          | Inspiron 15-3567            | [fd246079ad](https://linux-hardware.org/?probe=fd246079ad) | Jun 04, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [c4468417e9](https://linux-hardware.org/?probe=c4468417e9) | Jun 01, 2022 |
| Lenovo        | ThinkPad X230 2325N66       | [2061351dbc](https://linux-hardware.org/?probe=2061351dbc) | May 28, 2022 |
| Dell          | Latitude E6540              | [9171fd4d35](https://linux-hardware.org/?probe=9171fd4d35) | May 26, 2022 |
| Dell          | Latitude E6540              | [e7a078f1a1](https://linux-hardware.org/?probe=e7a078f1a1) | May 26, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | [dbf37b46f6](https://linux-hardware.org/?probe=dbf37b46f6) | May 25, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | [9fcb918138](https://linux-hardware.org/?probe=9fcb918138) | May 25, 2022 |
| Dell          | Latitude 5400               | [fdfa7356be](https://linux-hardware.org/?probe=fdfa7356be) | May 23, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 80X4     | [aa6aefb86a](https://linux-hardware.org/?probe=aa6aefb86a) | May 21, 2022 |
| Dell          | Latitude E6410              | [b098a84988](https://linux-hardware.org/?probe=b098a84988) | May 20, 2022 |
| MSI           | GE62 6QE                    | [6a3161d4ee](https://linux-hardware.org/?probe=6a3161d4ee) | May 09, 2022 |
| Timi          | TM1613                      | [114752ffeb](https://linux-hardware.org/?probe=114752ffeb) | May 08, 2022 |
| Timi          | TM1613                      | [b714f7dbd8](https://linux-hardware.org/?probe=b714f7dbd8) | May 08, 2022 |
| Lenovo        | V330-15IKB 81AX             | [60a636868c](https://linux-hardware.org/?probe=60a636868c) | Apr 30, 2022 |
| ASUSTek       | ROG Strix G733ZX_G733ZX     | [032acaf88c](https://linux-hardware.org/?probe=032acaf88c) | Apr 25, 2022 |
| HUAWEI        | HVY-WXX9                    | [56d949b3bb](https://linux-hardware.org/?probe=56d949b3bb) | Apr 23, 2022 |
| HP            | EliteBook 8470p             | [0ee15f97fd](https://linux-hardware.org/?probe=0ee15f97fd) | Apr 23, 2022 |
| Dell          | Inspiron 15 5510            | [73a8933099](https://linux-hardware.org/?probe=73a8933099) | Apr 22, 2022 |
| Lenovo        | IdeaPad L340-17API 81LY     | [4d911b0d94](https://linux-hardware.org/?probe=4d911b0d94) | Apr 22, 2022 |
| MSI           | Modern 15 A5M               | [7e03ed9f70](https://linux-hardware.org/?probe=7e03ed9f70) | Apr 13, 2022 |
| Apple         | MacBookPro15,1              | [b9187e8521](https://linux-hardware.org/?probe=b9187e8521) | Apr 13, 2022 |
| MSI           | Modern 15 A5M               | [bdccad7bf9](https://linux-hardware.org/?probe=bdccad7bf9) | Apr 12, 2022 |
| Razer         | Blade 15 Base Model (Ear... | [0832404b40](https://linux-hardware.org/?probe=0832404b40) | Apr 11, 2022 |
| ASUSTek       | X540SAA                     | [b670324e44](https://linux-hardware.org/?probe=b670324e44) | Apr 10, 2022 |
| Lenovo        | IdeaPad L340-17API 81LY     | [8cb4405c5f](https://linux-hardware.org/?probe=8cb4405c5f) | Apr 09, 2022 |
| Toshiba       | Satellite Click 2 L35W-B    | [f992f9305a](https://linux-hardware.org/?probe=f992f9305a) | Apr 07, 2022 |
| MSI           | Modern 15 A5M               | [e422a0e166](https://linux-hardware.org/?probe=e422a0e166) | Apr 05, 2022 |
| MSI           | Modern 15 A5M               | [b96e97fa2b](https://linux-hardware.org/?probe=b96e97fa2b) | Apr 04, 2022 |
| MSI           | Modern 15 A5M               | [401792c28e](https://linux-hardware.org/?probe=401792c28e) | Apr 01, 2022 |
| Alienware     | M14xR1                      | [f3ea3f497c](https://linux-hardware.org/?probe=f3ea3f497c) | Apr 01, 2022 |
| HP            | Notebook                    | [313ca81d16](https://linux-hardware.org/?probe=313ca81d16) | Mar 27, 2022 |
| ASUSTek       | X540SAA                     | [988b4570ed](https://linux-hardware.org/?probe=988b4570ed) | Mar 24, 2022 |
| Lenovo        | ThinkPad E15 20RD0086UE     | [f26a636b1b](https://linux-hardware.org/?probe=f26a636b1b) | Mar 24, 2022 |
| MSI           | Modern 15 A5M               | [72245fe662](https://linux-hardware.org/?probe=72245fe662) | Mar 22, 2022 |
| Toshiba       | Satellite L775D             | [3d09dbe623](https://linux-hardware.org/?probe=3d09dbe623) | Mar 14, 2022 |
| Positivo      | Q232A                       | [87c79b8f05](https://linux-hardware.org/?probe=87c79b8f05) | Mar 13, 2022 |
| ASUSTek       | X75VC                       | [3973070120](https://linux-hardware.org/?probe=3973070120) | Mar 12, 2022 |
| Jumper        | EZbook                      | [c374bd5058](https://linux-hardware.org/?probe=c374bd5058) | Mar 11, 2022 |
| Apple         | MacBookAir3,1               | [320f9e6841](https://linux-hardware.org/?probe=320f9e6841) | Mar 11, 2022 |
| Metabox       | Edge-Pro NS50MU             | [1371afa6ac](https://linux-hardware.org/?probe=1371afa6ac) | Mar 11, 2022 |
| Apple         | MacBookPro11,4              | [b27d8c8724](https://linux-hardware.org/?probe=b27d8c8724) | Mar 10, 2022 |
| Dell          | Inspiron 5570               | [e77116d171](https://linux-hardware.org/?probe=e77116d171) | Mar 10, 2022 |
| Dell          | Latitude XT2                | [ff6a48346f](https://linux-hardware.org/?probe=ff6a48346f) | Mar 07, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [f9c159a911](https://linux-hardware.org/?probe=f9c159a911) | Mar 06, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [ec13383aff](https://linux-hardware.org/?probe=ec13383aff) | Mar 06, 2022 |
| Jumper        | EZbook                      | [09544efb61](https://linux-hardware.org/?probe=09544efb61) | Mar 05, 2022 |
| Apple         | MacBookPro11,4              | [fb03915a3e](https://linux-hardware.org/?probe=fb03915a3e) | Mar 03, 2022 |
| Jumper        | EZbook                      | [de9a14c4ec](https://linux-hardware.org/?probe=de9a14c4ec) | Mar 02, 2022 |
| Chuwi         | GemiBook                    | [bb9f45273a](https://linux-hardware.org/?probe=bb9f45273a) | Mar 01, 2022 |
| Samsung       | 550P5C/550P7C               | [f14f73025f](https://linux-hardware.org/?probe=f14f73025f) | Feb 27, 2022 |
| Toshiba       | Satellite C75D-B            | [952057ee2b](https://linux-hardware.org/?probe=952057ee2b) | Feb 24, 2022 |
| Acer          | Nitro AN517-41              | [47b906a661](https://linux-hardware.org/?probe=47b906a661) | Feb 23, 2022 |
| Chuwi         | GemiBook                    | [25f5f358cb](https://linux-hardware.org/?probe=25f5f358cb) | Feb 17, 2022 |
| Acer          | Nitro AN515-54              | [f83ccc9cce](https://linux-hardware.org/?probe=f83ccc9cce) | Feb 15, 2022 |
| Sony          | SVP1321L1EBI                | [b35a3fbfec](https://linux-hardware.org/?probe=b35a3fbfec) | Feb 13, 2022 |
| HP            | ProBook 4535s               | [0d0cd13f8b](https://linux-hardware.org/?probe=0d0cd13f8b) | Feb 12, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0df06bcae3](https://linux-hardware.org/?probe=0df06bcae3) | Feb 11, 2022 |
| HP            | Notebook                    | [1f47143486](https://linux-hardware.org/?probe=1f47143486) | Feb 06, 2022 |
| Apple         | MacBook7,1                  | [9f4f77f51d](https://linux-hardware.org/?probe=9f4f77f51d) | Feb 06, 2022 |
| Apple         | MacBook7,1                  | [b6d5344f4e](https://linux-hardware.org/?probe=b6d5344f4e) | Feb 04, 2022 |
| Dell          | Inspiron N5110              | [5aa1140ad5](https://linux-hardware.org/?probe=5aa1140ad5) | Feb 02, 2022 |
| Lenovo        | ThinkPad T480 20L6SCYP00    | [d69eb6fc3e](https://linux-hardware.org/?probe=d69eb6fc3e) | Jan 30, 2022 |
| GPU Compan... | GWTN141-10                  | [89835cd678](https://linux-hardware.org/?probe=89835cd678) | Jan 30, 2022 |
| Acer          | Aspire A315-21              | [880cca4c8f](https://linux-hardware.org/?probe=880cca4c8f) | Jan 24, 2022 |
| Dell          | Latitude 7480               | [e184163da5](https://linux-hardware.org/?probe=e184163da5) | Jan 19, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [9901f0a14a](https://linux-hardware.org/?probe=9901f0a14a) | Jan 18, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [3837c06ca1](https://linux-hardware.org/?probe=3837c06ca1) | Jan 18, 2022 |
| Dell          | Inspiron 5580               | [a8e7059c51](https://linux-hardware.org/?probe=a8e7059c51) | Jan 17, 2022 |
| Lenovo        | ThinkPad E14 20RA0016GE     | [46eeb2d4b8](https://linux-hardware.org/?probe=46eeb2d4b8) | Jan 14, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [4e45161acc](https://linux-hardware.org/?probe=4e45161acc) | Jan 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [4c04661023](https://linux-hardware.org/?probe=4c04661023) | Jan 12, 2022 |
| HP            | EliteBook 8470p             | [d0c5b453db](https://linux-hardware.org/?probe=d0c5b453db) | Dec 31, 2021 |
| Lenovo        | IdeaPad Y580                | [cbb37b3b6a](https://linux-hardware.org/?probe=cbb37b3b6a) | Dec 20, 2021 |
| Lenovo        | IdeaPad Y580                | [48d92517e3](https://linux-hardware.org/?probe=48d92517e3) | Dec 11, 2021 |
| Dell          | Precision M4600             | [f386251b14](https://linux-hardware.org/?probe=f386251b14) | Nov 30, 2021 |
| Alienware     | m15 R6                      | [487678d2e5](https://linux-hardware.org/?probe=487678d2e5) | Nov 27, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [550ad36300](https://linux-hardware.org/?probe=550ad36300) | Nov 26, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [db67630cee](https://linux-hardware.org/?probe=db67630cee) | Nov 26, 2021 |
| Toxic         | GM7MQ8P                     | [deb5cbd490](https://linux-hardware.org/?probe=deb5cbd490) | Nov 24, 2021 |
| MSI           | Creator Z16 Hiroshi F A1... | [40f615079d](https://linux-hardware.org/?probe=40f615079d) | Nov 23, 2021 |
| HP            | ZBook Firefly 14 G7 Mobi... | [0dc4672364](https://linux-hardware.org/?probe=0dc4672364) | Nov 21, 2021 |
| Toshiba       | Satellite L655              | [e41f3dd777](https://linux-hardware.org/?probe=e41f3dd777) | Nov 12, 2021 |
| Dell          | Latitude E6410              | [2f9b89dbb4](https://linux-hardware.org/?probe=2f9b89dbb4) | Nov 09, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | [6ef3dbe032](https://linux-hardware.org/?probe=6ef3dbe032) | Nov 09, 2021 |
| Dell          | Latitude E6410              | [099708f286](https://linux-hardware.org/?probe=099708f286) | Nov 07, 2021 |
| Acer          | TravelMate 5720             | [8e19effec8](https://linux-hardware.org/?probe=8e19effec8) | Nov 06, 2021 |
| HP            | Pavilion g7                 | [c1b5449516](https://linux-hardware.org/?probe=c1b5449516) | Nov 05, 2021 |
| Lenovo        | Yoga S740-14IIL 81RS        | [833500916c](https://linux-hardware.org/?probe=833500916c) | Nov 03, 2021 |
| Lenovo        | B50-80 80EW                 | [37a983c1e7](https://linux-hardware.org/?probe=37a983c1e7) | Oct 26, 2021 |
| Lenovo        | B50-80 80EW                 | [ca3a74943a](https://linux-hardware.org/?probe=ca3a74943a) | Oct 25, 2021 |
| Dell          | Latitude E7450              | [2d94d751ff](https://linux-hardware.org/?probe=2d94d751ff) | Oct 22, 2021 |
| Dell          | Latitude E7450              | [a2b09ead76](https://linux-hardware.org/?probe=a2b09ead76) | Oct 22, 2021 |
| MSI           | GT60 2OC/2OD                | [56c85806e2](https://linux-hardware.org/?probe=56c85806e2) | Oct 20, 2021 |
| HP            | Laptop 15q-dy0xxx           | [aa4c6c2a25](https://linux-hardware.org/?probe=aa4c6c2a25) | Oct 18, 2021 |
| Dell          | Inspiron MM061              | [5b16f69a60](https://linux-hardware.org/?probe=5b16f69a60) | Oct 17, 2021 |
| Dell          | Inspiron MM061              | [caa2855c26](https://linux-hardware.org/?probe=caa2855c26) | Oct 17, 2021 |
| HP            | Pavilion g7                 | [7e80ec4599](https://linux-hardware.org/?probe=7e80ec4599) | Oct 11, 2021 |
| HP            | Pavilion g7                 | [cd8ce3be30](https://linux-hardware.org/?probe=cd8ce3be30) | Oct 10, 2021 |
| HP            | Pavilion g7                 | [dd3f8159e0](https://linux-hardware.org/?probe=dd3f8159e0) | Oct 10, 2021 |
| MSI           | GT60 2OC/2OD                | [79e12d69ec](https://linux-hardware.org/?probe=79e12d69ec) | Oct 08, 2021 |
| HP            | EliteBook 840 G3            | [fb11994deb](https://linux-hardware.org/?probe=fb11994deb) | Oct 04, 2021 |
| Dell          | Inspiron 7501               | [1d532e72c0](https://linux-hardware.org/?probe=1d532e72c0) | Oct 02, 2021 |
| HP            | 250 G7 Notebook PC          | [b33c31b0cf](https://linux-hardware.org/?probe=b33c31b0cf) | Oct 02, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [eafc16e86f](https://linux-hardware.org/?probe=eafc16e86f) | Sep 24, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [3eac62e012](https://linux-hardware.org/?probe=3eac62e012) | Sep 24, 2021 |
| Dell          | Vostro 5470                 | [c57bcaa35d](https://linux-hardware.org/?probe=c57bcaa35d) | Sep 19, 2021 |
| Lenovo        | B50-80 80EW                 | [493f8d65cb](https://linux-hardware.org/?probe=493f8d65cb) | Sep 18, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [09b7566e74](https://linux-hardware.org/?probe=09b7566e74) | Sep 14, 2021 |
| Acer          | TravelMate 5720             | [b08ac328d1](https://linux-hardware.org/?probe=b08ac328d1) | Sep 14, 2021 |
| Eluktronic... | MAG-15u                     | [f931222022](https://linux-hardware.org/?probe=f931222022) | Sep 13, 2021 |
| Acer          | Swift SF114-33              | [31bc470f08](https://linux-hardware.org/?probe=31bc470f08) | Sep 11, 2021 |
| Lenovo        | ThinkPad X250 20CL001GZA    | [e732588a09](https://linux-hardware.org/?probe=e732588a09) | Sep 05, 2021 |
| HP            | Laptop 15s-eq1xxx           | [ede284a3a3](https://linux-hardware.org/?probe=ede284a3a3) | Aug 30, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [03676f1856](https://linux-hardware.org/?probe=03676f1856) | Aug 28, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [41663f4fb2](https://linux-hardware.org/?probe=41663f4fb2) | Aug 26, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [0460f1a29b](https://linux-hardware.org/?probe=0460f1a29b) | Aug 24, 2021 |
| HP            | ProBook 650 G1              | [2ef0cf3a18](https://linux-hardware.org/?probe=2ef0cf3a18) | Aug 16, 2021 |
| Dell          | Inspiron 5593               | [340be8f7fb](https://linux-hardware.org/?probe=340be8f7fb) | Aug 15, 2021 |
| Lenovo        | B50-80 80EW                 | [bd70ed892a](https://linux-hardware.org/?probe=bd70ed892a) | Aug 14, 2021 |
| HP            | Pavilion dv6700             | [8714c1e6ab](https://linux-hardware.org/?probe=8714c1e6ab) | Aug 10, 2021 |
| MSI           | GT60 2OC/2OD                | [5ff69797f3](https://linux-hardware.org/?probe=5ff69797f3) | Aug 09, 2021 |
| ASUSTek       | X75VB                       | [bc26a9b439](https://linux-hardware.org/?probe=bc26a9b439) | Aug 07, 2021 |
| HP            | Pavilion 15                 | [f0f33cb33a](https://linux-hardware.org/?probe=f0f33cb33a) | Aug 06, 2021 |
| Dell          | Latitude E6420              | [9e72687dd4](https://linux-hardware.org/?probe=9e72687dd4) | Aug 05, 2021 |
| HP            | Pavilion dv7                | [5d8cfc9c95](https://linux-hardware.org/?probe=5d8cfc9c95) | Aug 04, 2021 |
| HP            | Pavilion dv7                | [1d2d7a30f9](https://linux-hardware.org/?probe=1d2d7a30f9) | Aug 04, 2021 |
| ASUSTek       | G74Sx                       | [fb80932ddd](https://linux-hardware.org/?probe=fb80932ddd) | Jul 23, 2021 |
| Dell          | Latitude E7440              | [3a22179f3b](https://linux-hardware.org/?probe=3a22179f3b) | Jul 18, 2021 |
| ASUSTek       | X450EA                      | [91a0ff32e1](https://linux-hardware.org/?probe=91a0ff32e1) | Jul 06, 2021 |
| ASUSTek       | X450EA                      | [e4dc18ebf9](https://linux-hardware.org/?probe=e4dc18ebf9) | Jul 06, 2021 |
| Dell          | Precision M6400             | [7f2245c976](https://linux-hardware.org/?probe=7f2245c976) | Jun 24, 2021 |
| ASUSTek       | Q524UQ                      | [33d61b2077](https://linux-hardware.org/?probe=33d61b2077) | Jun 17, 2021 |
| Apple         | MacBookPro8,1               | [2a633bc008](https://linux-hardware.org/?probe=2a633bc008) | Jun 14, 2021 |
| Apple         | MacBookPro8,1               | [e3bb48a049](https://linux-hardware.org/?probe=e3bb48a049) | Jun 14, 2021 |
| HP            | Laptop 15-dw0xxx            | [fa4061e79f](https://linux-hardware.org/?probe=fa4061e79f) | Jun 09, 2021 |
| Gateway       | MP8708                      | [ba382202c2](https://linux-hardware.org/?probe=ba382202c2) | Jun 04, 2021 |
| HP            | ZBook 15 G5                 | [462531aabd](https://linux-hardware.org/?probe=462531aabd) | Jun 03, 2021 |
| ASUSTek       | Q524UQ                      | [b510297404](https://linux-hardware.org/?probe=b510297404) | Jun 03, 2021 |
| Dell          | Inspiron 5558               | [91fdca7228](https://linux-hardware.org/?probe=91fdca7228) | May 31, 2021 |
| MSI           | GE73 Raider RGB 8RE         | [5aedb75ad8](https://linux-hardware.org/?probe=5aedb75ad8) | May 21, 2021 |
| Fujitsu       | LIFEBOOK T731               | [1cb3267b57](https://linux-hardware.org/?probe=1cb3267b57) | May 21, 2021 |
| Dell          | Inspiron 5420               | [dc6bc48c4d](https://linux-hardware.org/?probe=dc6bc48c4d) | May 18, 2021 |
| Lenovo        | ThinkPad X260 20F5S5QT00    | [a84514b117](https://linux-hardware.org/?probe=a84514b117) | May 14, 2021 |
| Apple         | MacBookPro11,1              | [aa4c3ffed1](https://linux-hardware.org/?probe=aa4c3ffed1) | May 13, 2021 |
| HP            | ProBook 650 G1              | [605367d5d4](https://linux-hardware.org/?probe=605367d5d4) | May 13, 2021 |
| HP            | Pavilion dv4                | [250773011b](https://linux-hardware.org/?probe=250773011b) | May 07, 2021 |
| HP            | HDX PREMIUM SERIES          | [47374d1b5f](https://linux-hardware.org/?probe=47374d1b5f) | Apr 27, 2021 |
| HP            | HDX PREMIUM SERIES          | [58b0d9473e](https://linux-hardware.org/?probe=58b0d9473e) | Apr 27, 2021 |
| Acer          | Aspire E1-571G              | [ee1ba6ee04](https://linux-hardware.org/?probe=ee1ba6ee04) | Apr 01, 2021 |
| PC Special... | N150CU                      | [39136d47f7](https://linux-hardware.org/?probe=39136d47f7) | Apr 01, 2021 |
| MSI           | GE75 Raider 10SF            | [d15c48b6a1](https://linux-hardware.org/?probe=d15c48b6a1) | Mar 29, 2021 |
| Dell          | Inspiron 5420               | [78663f1468](https://linux-hardware.org/?probe=78663f1468) | Mar 25, 2021 |
| MSI           | GE63 Raider RGB 8RE         | [de917105cd](https://linux-hardware.org/?probe=de917105cd) | Mar 22, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [01ab712b94](https://linux-hardware.org/?probe=01ab712b94) | Mar 22, 2021 |
| HP            | Pavilion Notebook           | [67ed2b4e7f](https://linux-hardware.org/?probe=67ed2b4e7f) | Mar 22, 2021 |
| HP            | Pavilion Notebook           | [acda849408](https://linux-hardware.org/?probe=acda849408) | Mar 22, 2021 |
| Wortmann      | TERRA_MOBILE_1542           | [76f7963d8a](https://linux-hardware.org/?probe=76f7963d8a) | Mar 21, 2021 |
| Wortmann      | TERRA_MOBILE_1542           | [12fb4cc711](https://linux-hardware.org/?probe=12fb4cc711) | Mar 21, 2021 |
| Acer          | Nitro AN515-54              | [a4bf4bb64c](https://linux-hardware.org/?probe=a4bf4bb64c) | Mar 17, 2021 |
| HP            | Pavilion dv6                | [06b3024017](https://linux-hardware.org/?probe=06b3024017) | Mar 14, 2021 |
| Dell          | Inspiron 5420               | [11a466e06d](https://linux-hardware.org/?probe=11a466e06d) | Mar 05, 2021 |
| Apple         | MacBookPro8,1               | [89174dda21](https://linux-hardware.org/?probe=89174dda21) | Feb 27, 2021 |
| Dell          | Inspiron 5420               | [489ed0f996](https://linux-hardware.org/?probe=489ed0f996) | Feb 26, 2021 |
| Dell          | Inspiron 5420               | [a357eb71e0](https://linux-hardware.org/?probe=a357eb71e0) | Feb 22, 2021 |
| Lenovo        | IdeaPad 110-14ISK 80UC      | [2cf1bfd6c6](https://linux-hardware.org/?probe=2cf1bfd6c6) | Feb 16, 2021 |
| HP            | Laptop 15-db0xxx            | [c337c59497](https://linux-hardware.org/?probe=c337c59497) | Feb 13, 2021 |
| HP            | ProBook 450 G1              | [284fd25f3e](https://linux-hardware.org/?probe=284fd25f3e) | Feb 11, 2021 |
| HP            | ENVY 15                     | [c39474b63f](https://linux-hardware.org/?probe=c39474b63f) | Jan 23, 2021 |
| Positivo B... | VJFE51F11X-B0111H           | [ea1a80dc34](https://linux-hardware.org/?probe=ea1a80dc34) | Jan 21, 2021 |
| Positivo B... | VJFE51F11X-B0111H           | [80dc10f323](https://linux-hardware.org/?probe=80dc10f323) | Jan 21, 2021 |
| Dell          | Latitude 7390               | [0ef9ffc535](https://linux-hardware.org/?probe=0ef9ffc535) | Dec 27, 2020 |
| ASUSTek       | X555LAB                     | [ab17ca4eef](https://linux-hardware.org/?probe=ab17ca4eef) | Dec 25, 2020 |
| Lenovo        | ThinkPad T490 20N2S04000    | [4f02aacb6d](https://linux-hardware.org/?probe=4f02aacb6d) | Dec 21, 2020 |
| HP            | EliteBook 8470p             | [33960a08de](https://linux-hardware.org/?probe=33960a08de) | Dec 20, 2020 |
| Toshiba       | Satellite L750              | [748a6b0b09](https://linux-hardware.org/?probe=748a6b0b09) | Dec 16, 2020 |
| Dell          | Latitude E5440              | [7befb8e28b](https://linux-hardware.org/?probe=7befb8e28b) | Nov 29, 2020 |
| Dell          | Latitude E5440              | [3064211887](https://linux-hardware.org/?probe=3064211887) | Nov 28, 2020 |
| Lenovo        | ThinkPad X220 42912XG       | [ce89f09531](https://linux-hardware.org/?probe=ce89f09531) | Nov 26, 2020 |
| Acer          | Aspire 5250                 | [11f670b6b1](https://linux-hardware.org/?probe=11f670b6b1) | Nov 23, 2020 |
| HP            | Compaq Presario C700        | [82be91a50a](https://linux-hardware.org/?probe=82be91a50a) | Nov 20, 2020 |
| HP            | Compaq Presario C700        | [f86087eece](https://linux-hardware.org/?probe=f86087eece) | Nov 20, 2020 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [458ab52080](https://linux-hardware.org/?probe=458ab52080) | Nov 17, 2020 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [6608936515](https://linux-hardware.org/?probe=6608936515) | Nov 10, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [c110de3643](https://linux-hardware.org/?probe=c110de3643) | Oct 31, 2020 |
| ASUSTek       | X540YA                      | [501ca10eeb](https://linux-hardware.org/?probe=501ca10eeb) | Oct 25, 2020 |
| Dell          | Vostro 3558                 | [8f4f321359](https://linux-hardware.org/?probe=8f4f321359) | Oct 18, 2020 |
| ASUSTek       | TUF Gaming FX705GD          | [8ce3caa35a](https://linux-hardware.org/?probe=8ce3caa35a) | Oct 15, 2020 |
| ASUSTek       | TUF Gaming FX705GD          | [b2d5b6eb69](https://linux-hardware.org/?probe=b2d5b6eb69) | Oct 15, 2020 |
| Lenovo        | ThinkPad T420s 4174W2P      | [c8eacff838](https://linux-hardware.org/?probe=c8eacff838) | Oct 10, 2020 |
| HP            | Pavilion 17                 | [2a0d11caf1](https://linux-hardware.org/?probe=2a0d11caf1) | Oct 09, 2020 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [f06ac6483c](https://linux-hardware.org/?probe=f06ac6483c) | Oct 06, 2020 |
| Razer         | Blade Stealth               | [564265e066](https://linux-hardware.org/?probe=564265e066) | Oct 01, 2020 |
| Acer          | Predator PH317-53           | [16cddb4fce](https://linux-hardware.org/?probe=16cddb4fce) | Sep 29, 2020 |
| Toshiba       | Satellite L750              | [74a0ca3614](https://linux-hardware.org/?probe=74a0ca3614) | Sep 25, 2020 |
| HP            | EliteBook Folio 9480m       | [bb1615dd63](https://linux-hardware.org/?probe=bb1615dd63) | Sep 24, 2020 |
| System76      | Gazelle                     | [d96d5e60ae](https://linux-hardware.org/?probe=d96d5e60ae) | Sep 20, 2020 |
| Alienware     | 17 R4                       | [d58b082d72](https://linux-hardware.org/?probe=d58b082d72) | Sep 19, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [d77bb0aa31](https://linux-hardware.org/?probe=d77bb0aa31) | Sep 18, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [951e2d1aa6](https://linux-hardware.org/?probe=951e2d1aa6) | Sep 18, 2020 |
| Dell          | Latitude 3400               | [f7d1872e51](https://linux-hardware.org/?probe=f7d1872e51) | Sep 13, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [090d50eec1](https://linux-hardware.org/?probe=090d50eec1) | Sep 12, 2020 |
| Lenovo        | E41-25 81FS                 | [1e512df642](https://linux-hardware.org/?probe=1e512df642) | Sep 12, 2020 |
| Toshiba       | Satellite L750              | [091facc59a](https://linux-hardware.org/?probe=091facc59a) | Sep 12, 2020 |
| Dell          | Latitude 3400               | [825d226ad5](https://linux-hardware.org/?probe=825d226ad5) | Sep 10, 2020 |
| Apple         | MacBookPro8,1               | [fc23c05e20](https://linux-hardware.org/?probe=fc23c05e20) | Sep 04, 2020 |
| Lenovo        | ThinkPad X240 20AMS4MH00    | [3e6177e73c](https://linux-hardware.org/?probe=3e6177e73c) | Sep 01, 2020 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [dbf4ca0908](https://linux-hardware.org/?probe=dbf4ca0908) | Aug 10, 2020 |
| Sony          | VPCCB15FG                   | [4d93dfd9c0](https://linux-hardware.org/?probe=4d93dfd9c0) | Aug 09, 2020 |
| Dell          | System Inspiron N7110       | [c4ba9dc0dc](https://linux-hardware.org/?probe=c4ba9dc0dc) | Aug 05, 2020 |
| HP            | Notebook                    | [989b6b7d5d](https://linux-hardware.org/?probe=989b6b7d5d) | Aug 04, 2020 |
| Acer          | Aspire ES1-111M             | [359a7266e5](https://linux-hardware.org/?probe=359a7266e5) | Aug 03, 2020 |
| Lenovo        | G480 20149                  | [bfffb28472](https://linux-hardware.org/?probe=bfffb28472) | Jul 27, 2020 |
| Lenovo        | G480 20149                  | [53b70e68df](https://linux-hardware.org/?probe=53b70e68df) | Jul 27, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [f032f63f3a](https://linux-hardware.org/?probe=f032f63f3a) | Jul 26, 2020 |
| HP            | Notebook                    | [ee51b68070](https://linux-hardware.org/?probe=ee51b68070) | Jul 23, 2020 |
| HP            | Notebook                    | [87cfa4c37e](https://linux-hardware.org/?probe=87cfa4c37e) | Jul 23, 2020 |
| Dell          | System Inspiron N7110       | [3177a50194](https://linux-hardware.org/?probe=3177a50194) | Jul 22, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [f77f8a2639](https://linux-hardware.org/?probe=f77f8a2639) | Jul 15, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [4afe4f5961](https://linux-hardware.org/?probe=4afe4f5961) | Jul 15, 2020 |
| Acer          | Aspire V5-122P              | [a362dee702](https://linux-hardware.org/?probe=a362dee702) | Jul 10, 2020 |
| Dell          | Latitude 7480               | [aab5a5b50a](https://linux-hardware.org/?probe=aab5a5b50a) | Jul 07, 2020 |
| eMachines     | eME728                      | [3f409bf927](https://linux-hardware.org/?probe=3f409bf927) | Jul 05, 2020 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [3c48dbb383](https://linux-hardware.org/?probe=3c48dbb383) | Jul 05, 2020 |
| Dell          | G7 7790                     | [506d29b806](https://linux-hardware.org/?probe=506d29b806) | Jun 02, 2020 |
| Dell          | G7 7790                     | [0551762cbb](https://linux-hardware.org/?probe=0551762cbb) | Jun 02, 2020 |
| Google        | Celes                       | [d417dd63dd](https://linux-hardware.org/?probe=d417dd63dd) | May 22, 2020 |
| Google        | Celes                       | [88d722fa1b](https://linux-hardware.org/?probe=88d722fa1b) | May 22, 2020 |
| ASUSTek       | X75VB                       | [f41d9b003f](https://linux-hardware.org/?probe=f41d9b003f) | May 22, 2020 |
| Fujitsu       | LIFEBOOK A532               | [96ec25db7c](https://linux-hardware.org/?probe=96ec25db7c) | May 21, 2020 |
| Fujitsu       | LIFEBOOK A532               | [b2ecb833ba](https://linux-hardware.org/?probe=b2ecb833ba) | May 21, 2020 |
| Dell          | Inspiron MM061              | [a6bb0bfd0b](https://linux-hardware.org/?probe=a6bb0bfd0b) | May 21, 2020 |
| ASUSTek       | N56VZ                       | [69ee412460](https://linux-hardware.org/?probe=69ee412460) | May 14, 2020 |
| Dell          | Inspiron MM061              | [0d48c76bfd](https://linux-hardware.org/?probe=0d48c76bfd) | May 11, 2020 |
| Lenovo        | V110-15ISK 80TL             | [d64b4a56e0](https://linux-hardware.org/?probe=d64b4a56e0) | May 08, 2020 |
| ASUSTek       | X442URR                     | [7595f05acd](https://linux-hardware.org/?probe=7595f05acd) | May 04, 2020 |
| HP            | ProBook 6475b               | [c9ee4e6614](https://linux-hardware.org/?probe=c9ee4e6614) | May 03, 2020 |
| HP            | ProBook 6475b               | [06da2207cd](https://linux-hardware.org/?probe=06da2207cd) | May 02, 2020 |
| HP            | ProBook 6475b               | [b2ff4072ce](https://linux-hardware.org/?probe=b2ff4072ce) | May 02, 2020 |
| Toshiba       | Satellite L300D             | [5a320c4b78](https://linux-hardware.org/?probe=5a320c4b78) | May 02, 2020 |
| Dell          | Latitude E6420              | [ae3ade27d7](https://linux-hardware.org/?probe=ae3ade27d7) | Apr 29, 2020 |
| Dell          | Latitude E6420              | [83380135bc](https://linux-hardware.org/?probe=83380135bc) | Apr 27, 2020 |
| Dell          | Latitude E6420              | [12c77f16d5](https://linux-hardware.org/?probe=12c77f16d5) | Apr 27, 2020 |
| Dell          | XPS 12-9Q33                 | [f831495ef5](https://linux-hardware.org/?probe=f831495ef5) | Apr 25, 2020 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | [6bf9d537a8](https://linux-hardware.org/?probe=6bf9d537a8) | Apr 21, 2020 |
| Lenovo        | V110-15ISK 80TL             | [2dec0ef690](https://linux-hardware.org/?probe=2dec0ef690) | Apr 18, 2020 |
| HP            | Pavilion g6                 | [c54d518ca7](https://linux-hardware.org/?probe=c54d518ca7) | Apr 15, 2020 |
| Acer          | Aspire 5250                 | [100d4bacdc](https://linux-hardware.org/?probe=100d4bacdc) | Apr 14, 2020 |
| Dell          | Inspiron 5721               | [23d5dff3bd](https://linux-hardware.org/?probe=23d5dff3bd) | Apr 11, 2020 |
| Dell          | Inspiron 3458               | [d9c91be81b](https://linux-hardware.org/?probe=d9c91be81b) | Apr 06, 2020 |
| Dell          | Inspiron 3458               | [a10080482e](https://linux-hardware.org/?probe=a10080482e) | Apr 05, 2020 |
| Dell          | Inspiron 3458               | [cfb5a6d57c](https://linux-hardware.org/?probe=cfb5a6d57c) | Apr 05, 2020 |
| ASUSTek       | N56VZ                       | [249176d47f](https://linux-hardware.org/?probe=249176d47f) | Apr 01, 2020 |
| Samsung       | RV415/RV515                 | [3b9248b95f](https://linux-hardware.org/?probe=3b9248b95f) | Mar 31, 2020 |
| Lenovo        | ThinkPad T440s 20ARS01C0... | [aa9f421079](https://linux-hardware.org/?probe=aa9f421079) | Mar 23, 2020 |
| HP            | Laptop 17-by0xxx            | [21c7ac4323](https://linux-hardware.org/?probe=21c7ac4323) | Feb 17, 2020 |
| Lenovo        | ThinkPad E14 20RA0016GE     | [dd543cf29b](https://linux-hardware.org/?probe=dd543cf29b) | Feb 09, 2020 |
| Notebook      | W510TU                      | [987d9232fe](https://linux-hardware.org/?probe=987d9232fe) | Jan 31, 2020 |
| Notebook      | W510TU                      | [4556eb747b](https://linux-hardware.org/?probe=4556eb747b) | Jan 31, 2020 |
| HP            | EliteBook 8460p             | [8b7c621317](https://linux-hardware.org/?probe=8b7c621317) | Jan 26, 2020 |
| HUAWEI        | WRT-WX9                     | [375040e90b](https://linux-hardware.org/?probe=375040e90b) | Jan 05, 2020 |
| Notebook      | W510TU                      | [aa2e59fd60](https://linux-hardware.org/?probe=aa2e59fd60) | Dec 25, 2019 |
| Apple         | MacBookAir7,2               | [1a26d7b485](https://linux-hardware.org/?probe=1a26d7b485) | Dec 21, 2019 |
| Notebook      | W510TU                      | [f2102dfe5b](https://linux-hardware.org/?probe=f2102dfe5b) | Dec 09, 2019 |
| Apple         | MacBookAir7,2               | [73a28279bc](https://linux-hardware.org/?probe=73a28279bc) | Dec 05, 2019 |
| HP            | Pavilion Laptop 15-cs0xx... | [7bc298d7af](https://linux-hardware.org/?probe=7bc298d7af) | Nov 10, 2019 |
| HP            | 630                         | [687ccfe3b1](https://linux-hardware.org/?probe=687ccfe3b1) | Sep 28, 2019 |
| Acer          | Aspire E5-475               | [3e3fad10fe](https://linux-hardware.org/?probe=3e3fad10fe) | Aug 18, 2019 |
| Gateway       | NE-522                      | [d562b598e5](https://linux-hardware.org/?probe=d562b598e5) | Aug 10, 2019 |
| Lenovo        | Y50-70 Touch 20349          | [c0c73d01ba](https://linux-hardware.org/?probe=c0c73d01ba) | Jun 08, 2019 |
| Apple         | MacBookPro11,4              | [49a28f87b9](https://linux-hardware.org/?probe=49a28f87b9) | May 21, 2019 |
| Acer          | Swift SF314-54              | [89013e65ec](https://linux-hardware.org/?probe=89013e65ec) | Apr 26, 2019 |
| ASUSTek       | X510UQ                      | [74e81c78ab](https://linux-hardware.org/?probe=74e81c78ab) | Feb 16, 2019 |
| ASUSTek       | X510UQ                      | [50fc8650ad](https://linux-hardware.org/?probe=50fc8650ad) | Feb 16, 2019 |
| Dell          | Latitude E7440              | [ce392df9c0](https://linux-hardware.org/?probe=ce392df9c0) | Dec 26, 2018 |
| HP            | Pavilion 15                 | [921bec751d](https://linux-hardware.org/?probe=921bec751d) | Oct 13, 2018 |
| Digma         | CITI E401 ET4007EW          | [597e65c2a4](https://linux-hardware.org/?probe=597e65c2a4) | Jan 07, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Parrot 5.0   | 81        | 31.15%  |
| Parrot 4.11  | 64        | 24.62%  |
| Parrot 4.10  | 45        | 17.31%  |
| Parrot 5.1   | 26        | 10%     |
| Parrot 4.8   | 15        | 5.77%   |
| Parrot 4.9   | 13        | 5%      |
| Parrot 4.7   | 10        | 3.85%   |
| Parrot 4.6   | 2         | 0.77%   |
| Parrot 4.5   | 1         | 0.38%   |
| Parrot 4.4   | 1         | 0.38%   |
| Parrot 4.2.2 | 1         | 0.38%   |
| Parrot 3.10  | 1         | 0.38%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Parrot | 246       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.14.0-9parrot1-amd64    | 36        | 13.58%  |
| 5.16.0-12parrot1-amd64   | 34        | 12.83%  |
| 5.7.0-2parrot2-amd64     | 26        | 9.81%   |
| 5.10.0-6parrot1-amd64    | 25        | 9.43%   |
| 5.18.0-14parrot1-amd64   | 23        | 8.68%   |
| 5.18.0-1parrot1-amd64    | 14        | 5.28%   |
| 5.10.0-8parrot1-amd64    | 14        | 5.28%   |
| 5.5.0-1parrot1-amd64     | 12        | 4.53%   |
| 5.4.0-4parrot1-amd64     | 11        | 4.15%   |
| 5.6.0-2parrot1-amd64     | 9         | 3.4%    |
| 5.14.0-2parrot1-amd64    | 9         | 3.4%    |
| 5.9.0-2parrot1-amd64     | 7         | 2.64%   |
| 5.15.0-15parrot1-amd64   | 5         | 1.89%   |
| 6.0.0-2parrot1-amd64     | 3         | 1.13%   |
| 5.8.0-2parrot1-amd64     | 3         | 1.13%   |
| 5.4.0-2parrot1-amd64     | 3         | 1.13%   |
| 5.2.0-2parrot1-amd64     | 3         | 1.13%   |
| 5.10.0-5parrot1-amd64    | 3         | 1.13%   |
| 5.10.0-3parrot1-amd64    | 3         | 1.13%   |
| 4.19.0-parrot4-28t-amd64 | 3         | 1.13%   |
| 5.8.0-1parrot1-amd64     | 2         | 0.75%   |
| 5.4.0-3parrot1-amd64     | 2         | 0.75%   |
| 4.18.0-parrot10-amd64    | 2         | 0.75%   |
| 5.7.0-rc6-galliumos      | 1         | 0.38%   |
| 5.4.0-2parrot1-686-pae   | 1         | 0.38%   |
| 5.4.0-1parrot1-amd64     | 1         | 0.38%   |
| 5.3.0-3parrot3-amd64     | 1         | 0.38%   |
| 5.3.0-3parrot3-686-pae   | 1         | 0.38%   |
| 5.3.0-1parrot1-amd64     | 1         | 0.38%   |
| 5.15.0-5parrot1-amd64    | 1         | 0.38%   |
| 5.10.0-kali6-amd64       | 1         | 0.38%   |
| 5.10.0-6parrot1-rt-amd64 | 1         | 0.38%   |
| 5.1.0-parrot1-3t-amd64   | 1         | 0.38%   |
| 4.19.0-parrot1-13t-amd64 | 1         | 0.38%   |
| 4.14.0-parrot7-amd64     | 1         | 0.38%   |
| Unknown                  | 1         | 0.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 47        | 17.87%  |
| 5.14.0  | 44        | 16.73%  |
| 5.18.0  | 36        | 13.69%  |
| 5.16.0  | 34        | 12.93%  |
| 5.7.0   | 27        | 10.27%  |
| 5.4.0   | 18        | 6.84%   |
| 5.5.0   | 12        | 4.56%   |
| 5.6.0   | 9         | 3.42%   |
| 5.9.0   | 7         | 2.66%   |
| 5.15.0  | 6         | 2.28%   |
| 5.8.0   | 5         | 1.9%    |
| 4.19.0  | 4         | 1.52%   |
| 6.0.0   | 3         | 1.14%   |
| 5.3.0   | 3         | 1.14%   |
| 5.2.0   | 3         | 1.14%   |
| 4.18.0  | 2         | 0.76%   |
| 5.1.0   | 1         | 0.38%   |
| 4.14.0  | 1         | 0.38%   |
| Unknown | 1         | 0.38%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 47        | 17.87%  |
| 5.14    | 44        | 16.73%  |
| 5.18    | 36        | 13.69%  |
| 5.16    | 34        | 12.93%  |
| 5.7     | 27        | 10.27%  |
| 5.4     | 18        | 6.84%   |
| 5.5     | 12        | 4.56%   |
| 5.6     | 9         | 3.42%   |
| 5.9     | 7         | 2.66%   |
| 5.15    | 6         | 2.28%   |
| 5.8     | 5         | 1.9%    |
| 4.19    | 4         | 1.52%   |
| 6.0     | 3         | 1.14%   |
| 5.3     | 3         | 1.14%   |
| 5.2     | 3         | 1.14%   |
| 4.18    | 2         | 0.76%   |
| 5.1     | 1         | 0.38%   |
| 4.14    | 1         | 0.38%   |
| Unknown | 1         | 0.38%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 245       | 99.59%  |
| i686   | 1         | 0.41%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| MATE          | 165       | 65.74%  |
| KDE5          | 48        | 19.12%  |
| Unknown       | 18        | 7.17%   |
| KDE           | 13        | 5.18%   |
| XFCE          | 5         | 1.99%   |
| LXDE          | 1         | 0.4%    |
| GNOME Classic | 1         | 0.4%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 242       | 98.37%  |
| Tty     | 2         | 0.81%   |
| Wayland | 1         | 0.41%   |
| Unknown | 1         | 0.41%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 103       | 40.87%  |
| Unknown | 92        | 36.51%  |
| TDM     | 50        | 19.84%  |
| GDM     | 5         | 1.98%   |
| SDDM    | 2         | 0.79%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 127       | 51.42%  |
| en_GB   | 22        | 8.91%   |
| Unknown | 14        | 5.67%   |
| fr_FR   | 13        | 5.26%   |
| ru_RU   | 8         | 3.24%   |
| es_ES   | 8         | 3.24%   |
| pl_PL   | 7         | 2.83%   |
| pt_BR   | 6         | 2.43%   |
| de_DE   | 6         | 2.43%   |
| it_IT   | 5         | 2.02%   |
| en_IN   | 5         | 2.02%   |
| en_AU   | 4         | 1.62%   |
| es_AR   | 2         | 0.81%   |
| en_CA   | 2         | 0.81%   |
| tr_TR   | 1         | 0.4%    |
| pt_PT   | 1         | 0.4%    |
| nl_BE   | 1         | 0.4%    |
| id_ID   | 1         | 0.4%    |
| fr_CA   | 1         | 0.4%    |
| fi_FI   | 1         | 0.4%    |
| es_PE   | 1         | 0.4%    |
| es_MX   | 1         | 0.4%    |
| es_CO   | 1         | 0.4%    |
| es_CL   | 1         | 0.4%    |
| en_ZW   | 1         | 0.4%    |
| en_ZA   | 1         | 0.4%    |
| en_NZ   | 1         | 0.4%    |
| en_NG   | 1         | 0.4%    |
| en_DK   | 1         | 0.4%    |
| cs_CZ   | 1         | 0.4%    |
| C       | 1         | 0.4%    |
| arn_CL  | 1         | 0.4%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 153       | 61.45%  |
| EFI  | 96        | 38.55%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Btrfs   | 188       | 75.2%   |
| Ext4    | 41        | 16.4%   |
| Xfs     | 8         | 3.2%    |
| Unknown | 7         | 2.8%    |
| Overlay | 6         | 2.4%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 107       | 42.8%   |
| GPT     | 94        | 37.6%   |
| MBR     | 49        | 19.6%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 218       | 87.55%  |
| Yes       | 31        | 12.45%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 166       | 66.67%  |
| Yes       | 83        | 33.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 49        | 19.92%  |
| Lenovo                | 47        | 19.11%  |
| Dell                  | 42        | 17.07%  |
| ASUSTek Computer      | 22        | 8.94%   |
| Acer                  | 17        | 6.91%   |
| MSI                   | 10        | 4.07%   |
| Apple                 | 9         | 3.66%   |
| Toshiba               | 8         | 3.25%   |
| Samsung Electronics   | 4         | 1.63%   |
| HUAWEI                | 4         | 1.63%   |
| Sony                  | 3         | 1.22%   |
| Fujitsu               | 3         | 1.22%   |
| Alienware             | 3         | 1.22%   |
| Razer                 | 2         | 0.81%   |
| Gateway               | 2         | 0.81%   |
| Wortmann AG           | 1         | 0.41%   |
| Toxic                 | 1         | 0.41%   |
| Timi                  | 1         | 0.41%   |
| System76              | 1         | 0.41%   |
| Standard              | 1         | 0.41%   |
| Positivo Bahia - VAIO | 1         | 0.41%   |
| Positivo              | 1         | 0.41%   |
| Panasonic             | 1         | 0.41%   |
| Notebook              | 1         | 0.41%   |
| Metabox               | 1         | 0.41%   |
| Jumper                | 1         | 0.41%   |
| Irbis                 | 1         | 0.41%   |
| GPU Company           | 1         | 0.41%   |
| Google                | 1         | 0.41%   |
| eMachines             | 1         | 0.41%   |
| Eluktronics           | 1         | 0.41%   |
| Digma                 | 1         | 0.41%   |
| Clevo                 | 1         | 0.41%   |
| Chuwi                 | 1         | 0.41%   |
| BANGHO                | 1         | 0.41%   |
| Unknown               | 1         | 0.41%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                               | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| MSI Modern 15 A5M                                  | 3         | 1.22%   |
| Lenovo IdeaPad 3 15IIL05 81WE                      | 3         | 1.22%   |
| HP Notebook                                        | 3         | 1.22%   |
| HP EliteBook 8470p                                 | 3         | 1.22%   |
| Dell Latitude E6420                                | 3         | 1.22%   |
| Dell Inspiron MM061                                | 3         | 1.22%   |
| Unknown                                            | 3         | 1.22%   |
| HP ProBook 650 G1                                  | 2         | 0.81%   |
| HP Pavilion dv6                                    | 2         | 0.81%   |
| HP Pavilion 15                                     | 2         | 0.81%   |
| Dell Latitude E7440                                | 2         | 0.81%   |
| Dell Latitude E6410                                | 2         | 0.81%   |
| ASUS Q524UQ                                        | 2         | 0.81%   |
| Apple MacBookPro8,1                                | 2         | 0.81%   |
| Acer Nitro AN515-54                                | 2         | 0.81%   |
| Acer Aspire ES1-111M                               | 2         | 0.81%   |
| Wortmann AG TERRA_MOBILE_1542                      | 1         | 0.41%   |
| Toxic GM7MQ8P                                      | 1         | 0.41%   |
| Toshiba Satellite-L845                             | 1         | 0.41%   |
| Toshiba Satellite L775D                            | 1         | 0.41%   |
| Toshiba Satellite L750                             | 1         | 0.41%   |
| Toshiba Satellite L655                             | 1         | 0.41%   |
| Toshiba Satellite L300D                            | 1         | 0.41%   |
| Toshiba Satellite Click 2 L35W-B                   | 1         | 0.41%   |
| Toshiba Satellite C855D                            | 1         | 0.41%   |
| Toshiba Satellite C75D-B                           | 1         | 0.41%   |
| Timi TM1613                                        | 1         | 0.41%   |
| System76 Gazelle                                   | 1         | 0.41%   |
| Sony VPCSB1C5E                                     | 1         | 0.41%   |
| Sony VPCCB15FG                                     | 1         | 0.41%   |
| Sony SVP1321L1EBI                                  | 1         | 0.41%   |
| Samsung RV415/RV515                                | 1         | 0.41%   |
| Samsung 550P5C/550P7C                              | 1         | 0.41%   |
| Samsung 350V5C/351V5C/3540VC/3440VC                | 1         | 0.41%   |
| Samsung 300E4C/300E5C/300E7C                       | 1         | 0.41%   |
| Razer Blade Stealth                                | 1         | 0.41%   |
| Razer Blade 15 Base Model (Early 2020) - RZ09-0328 | 1         | 0.41%   |
| Positivo Q232A                                     | 1         | 0.41%   |
| Positivo Bahia - VAIO VJFE51F11X-B0111H            | 1         | 0.41%   |
| Panasonic CF-31JBGNNDM                             | 1         | 0.41%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 23        | 9.35%   |
| Dell Latitude          | 18        | 7.32%   |
| Dell Inspiron          | 17        | 6.91%   |
| HP Pavilion            | 14        | 5.69%   |
| Lenovo IdeaPad         | 12        | 4.88%   |
| HP EliteBook           | 9         | 3.66%   |
| Acer Aspire            | 8         | 3.25%   |
| Toshiba Satellite      | 7         | 2.85%   |
| HP Laptop              | 7         | 2.85%   |
| HP ProBook             | 5         | 2.03%   |
| ASUS VivoBook          | 4         | 1.63%   |
| Acer Nitro             | 4         | 1.63%   |
| MSI Modern             | 3         | 1.22%   |
| HP Notebook            | 3         | 1.22%   |
| Fujitsu LIFEBOOK       | 3         | 1.22%   |
| Unknown                | 3         | 1.22%   |
| Razer Blade            | 2         | 0.81%   |
| HP ZBook               | 2         | 0.81%   |
| HP 250                 | 2         | 0.81%   |
| Dell Vostro            | 2         | 0.81%   |
| Dell Precision         | 2         | 0.81%   |
| ASUS TUF               | 2         | 0.81%   |
| ASUS Q524UQ            | 2         | 0.81%   |
| Apple MacBookPro8      | 2         | 0.81%   |
| Apple MacBookPro11     | 2         | 0.81%   |
| Alienware m15          | 2         | 0.81%   |
| Acer Swift             | 2         | 0.81%   |
| Acer Predator          | 2         | 0.81%   |
| Wortmann AG TERRA      | 1         | 0.41%   |
| Toxic GM7MQ8P          | 1         | 0.41%   |
| Toshiba Satellite-L845 | 1         | 0.41%   |
| Timi TM1613            | 1         | 0.41%   |
| System76 Gazelle       | 1         | 0.41%   |
| Sony VPCSB1C5E         | 1         | 0.41%   |
| Sony VPCCB15FG         | 1         | 0.41%   |
| Sony SVP1321L1EBI      | 1         | 0.41%   |
| Samsung RV415          | 1         | 0.41%   |
| Samsung 550P5C         | 1         | 0.41%   |
| Samsung 350V5C         | 1         | 0.41%   |
| Samsung 300E4C         | 1         | 0.41%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2011 | 30        | 12.2%   |
| 2019 | 29        | 11.79%  |
| 2020 | 24        | 9.76%   |
| 2021 | 23        | 9.35%   |
| 2013 | 22        | 8.94%   |
| 2018 | 21        | 8.54%   |
| 2012 | 18        | 7.32%   |
| 2016 | 17        | 6.91%   |
| 2014 | 14        | 5.69%   |
| 2017 | 13        | 5.28%   |
| 2010 | 8         | 3.25%   |
| 2015 | 7         | 2.85%   |
| 2008 | 7         | 2.85%   |
| 2022 | 4         | 1.63%   |
| 2006 | 4         | 1.63%   |
| 2007 | 3         | 1.22%   |
| 2009 | 2         | 0.81%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 246       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 246       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 245       | 99.59%  |
| Yes  | 1         | 0.41%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 62        | 25.1%   |
| 8.01-16.0   | 54        | 21.86%  |
| 16.01-24.0  | 49        | 19.84%  |
| 3.01-4.0    | 48        | 19.43%  |
| 32.01-64.0  | 16        | 6.48%   |
| 1.01-2.0    | 7         | 2.83%   |
| 64.01-256.0 | 5         | 2.02%   |
| 24.01-32.0  | 3         | 1.21%   |
| 2.01-3.0    | 3         | 1.21%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 92        | 35.38%  |
| 2.01-3.0  | 81        | 31.15%  |
| 3.01-4.0  | 43        | 16.54%  |
| 4.01-8.0  | 27        | 10.38%  |
| 0.51-1.0  | 11        | 4.23%   |
| 8.01-16.0 | 5         | 1.92%   |
| 0.01-0.5  | 1         | 0.38%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 168       | 67.47%  |
| 2      | 72        | 28.92%  |
| 3      | 8         | 3.21%   |
| 0      | 1         | 0.4%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 163       | 65.99%  |
| Yes       | 84        | 34.01%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 199       | 80.57%  |
| No        | 48        | 19.43%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 243       | 98.78%  |
| No        | 3         | 1.22%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 197       | 78.8%   |
| No        | 53        | 21.2%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 79        | 31.85%  |
| Germany      | 14        | 5.65%   |
| France       | 13        | 5.24%   |
| Spain        | 11        | 4.44%   |
| UK           | 10        | 4.03%   |
| Russia       | 9         | 3.63%   |
| Brazil       | 8         | 3.23%   |
| Netherlands  | 7         | 2.82%   |
| Italy        | 7         | 2.82%   |
| India        | 6         | 2.42%   |
| Canada       | 6         | 2.42%   |
| Kenya        | 5         | 2.02%   |
| Sweden       | 4         | 1.61%   |
| Indonesia    | 4         | 1.61%   |
| Australia    | 4         | 1.61%   |
| South Africa | 3         | 1.21%   |
| Poland       | 3         | 1.21%   |
| Mexico       | 3         | 1.21%   |
| Iraq         | 3         | 1.21%   |
| Denmark      | 3         | 1.21%   |
| Turkey       | 2         | 0.81%   |
| Switzerland  | 2         | 0.81%   |
| Puerto Rico  | 2         | 0.81%   |
| Portugal     | 2         | 0.81%   |
| Nepal        | 2         | 0.81%   |
| Finland      | 2         | 0.81%   |
| Czechia      | 2         | 0.81%   |
| Chile        | 2         | 0.81%   |
| Bangladesh   | 2         | 0.81%   |
| Argentina    | 2         | 0.81%   |
| Zimbabwe     | 1         | 0.4%    |
| Saudi Arabia | 1         | 0.4%    |
| Peru         | 1         | 0.4%    |
| Pakistan     | 1         | 0.4%    |
| Nigeria      | 1         | 0.4%    |
| New Zealand  | 1         | 0.4%    |
| Namibia      | 1         | 0.4%    |
| Myanmar      | 1         | 0.4%    |
| Morocco      | 1         | 0.4%    |
| Luxembourg   | 1         | 0.4%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Nairobi           | 5         | 1.92%   |
| Dallas            | 4         | 1.53%   |
| Seattle           | 3         | 1.15%   |
| Moscow            | 3         | 1.15%   |
| Houston           | 3         | 1.15%   |
| Chicago           | 3         | 1.15%   |
| Amsterdam         | 3         | 1.15%   |
| Zurich            | 2         | 0.77%   |
| Sydney            | 2         | 0.77%   |
| Stockholm         | 2         | 0.77%   |
| St Petersburg     | 2         | 0.77%   |
| San Juan          | 2         | 0.77%   |
| Ruskin            | 2         | 0.77%   |
| Rome              | 2         | 0.77%   |
| Pretoria          | 2         | 0.77%   |
| Paris             | 2         | 0.77%   |
| New York          | 2         | 0.77%   |
| Mostoles          | 2         | 0.77%   |
| Melbourne         | 2         | 0.77%   |
| Madrid            | 2         | 0.77%   |
| Lyon              | 2         | 0.77%   |
| London            | 2         | 0.77%   |
| Edmonton          | 2         | 0.77%   |
| Dublin            | 2         | 0.77%   |
| Dresden           | 2         | 0.77%   |
| Dhaka             | 2         | 0.77%   |
| Camden            | 2         | 0.77%   |
| Berlin            | 2         | 0.77%   |
| Barcelona         | 2         | 0.77%   |
| Baghdad           | 2         | 0.77%   |
| Zagreb            | 1         | 0.38%   |
| West Jordan       | 1         | 0.38%   |
| Washington        | 1         | 0.38%   |
| Warsaw            | 1         | 0.38%   |
| Volgograd         | 1         | 0.38%   |
| Visalia           | 1         | 0.38%   |
| Villa Carlos Paz  | 1         | 0.38%   |
| Vila Nova de Gaia | 1         | 0.38%   |
| Vienna            | 1         | 0.38%   |
| Veitsbronn        | 1         | 0.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 48        | 56     | 15.19%  |
| WDC                 | 40        | 48     | 12.66%  |
| Toshiba             | 40        | 45     | 12.66%  |
| Unknown             | 26        | 28     | 8.23%   |
| Seagate             | 24        | 24     | 7.59%   |
| Kingston            | 19        | 19     | 6.01%   |
| SanDisk             | 15        | 18     | 4.75%   |
| Hitachi             | 12        | 14     | 3.8%    |
| Crucial             | 10        | 15     | 3.16%   |
| Micron Technology   | 9         | 9      | 2.85%   |
| SK hynix            | 8         | 8      | 2.53%   |
| HGST                | 8         | 11     | 2.53%   |
| China               | 6         | 6      | 1.9%    |
| Intel               | 5         | 9      | 1.58%   |
| Apple               | 5         | 5      | 1.58%   |
| A-DATA Technology   | 5         | 5      | 1.58%   |
| LITEON              | 3         | 3      | 0.95%   |
| YMTC                | 2         | 2      | 0.63%   |
| Team                | 2         | 2      | 0.63%   |
| PNY                 | 2         | 2      | 0.63%   |
| KIOXIA              | 2         | 3      | 0.63%   |
| HUAWEI              | 2         | 2      | 0.63%   |
| Unknown             | 2         | 2      | 0.63%   |
| W800SH              | 1         | 1      | 0.32%   |
| Transcend           | 1         | 1      | 0.32%   |
| Silicon Motion      | 1         | 1      | 0.32%   |
| S3+                 | 1         | 1      | 0.32%   |
| RZX                 | 1         | 1      | 0.32%   |
| Phison              | 1         | 1      | 0.32%   |
| Patriot             | 1         | 1      | 0.32%   |
| Netac               | 1         | 1      | 0.32%   |
| LITEONIT            | 1         | 1      | 0.32%   |
| Lexar               | 1         | 1      | 0.32%   |
| KingSpec            | 1         | 2      | 0.32%   |
| KingFast            | 1         | 2      | 0.32%   |
| Intenso             | 1         | 2      | 0.32%   |
| HS-SSD-C100         | 1         | 1      | 0.32%   |
| Hikvision           | 1         | 1      | 0.32%   |
| Fujitsu             | 1         | 1      | 0.32%   |
| Corsair             | 1         | 2      | 0.32%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Toshiba MQ04ABF100 1TB             | 10        | 3.02%   |
| Toshiba MQ01ABF050 500GB           | 7         | 2.11%   |
| Toshiba MQ01ABD100 1TB             | 5         | 1.51%   |
| Kingston NVMe SSD Drive 512GB      | 5         | 1.51%   |
| Unknown SD/MMC/MS PRO 1TB          | 4         | 1.21%   |
| Unknown MMC Card  32GB             | 4         | 1.21%   |
| Seagate ST1000LM035-1RK172 1TB     | 4         | 1.21%   |
| Samsung SSD 860 EVO 500GB          | 4         | 1.21%   |
| WDC WD10SPZX-75Z10T2 1TB           | 3         | 0.91%   |
| Toshiba MQ01ABD075 752GB           | 3         | 0.91%   |
| Seagate ST2000LM003 HN-M201RAD 2TB | 3         | 0.91%   |
| SanDisk SSD PLUS 1000GB            | 3         | 0.91%   |
| SanDisk NVMe SSD Drive 1TB         | 3         | 0.91%   |
| Samsung SSD 850 EVO 250GB          | 3         | 0.91%   |
| HGST HTS721010A9E630 1TB           | 3         | 0.91%   |
| HGST HTS541010A9E680 1TB           | 3         | 0.91%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD   | 2         | 0.6%    |
| WDC WD5000LPCX-24C6HT0 500GB       | 2         | 0.6%    |
| WDC WD10SPZX-60Z10T0 1TB           | 2         | 0.6%    |
| Unknown MMC Card  64GB             | 2         | 0.6%    |
| Team TM8PS7512G 512GB SSD          | 2         | 0.6%    |
| Seagate ST9250315AS 250GB          | 2         | 0.6%    |
| Seagate ST500LT012-1DG142 500GB    | 2         | 0.6%    |
| Seagate ST320LT007-9ZV142 320GB    | 2         | 0.6%    |
| SanDisk NVMe SSD Drive 256GB       | 2         | 0.6%    |
| Samsung SSD 980 1TB                | 2         | 0.6%    |
| Samsung SSD 970 EVO Plus 500GB     | 2         | 0.6%    |
| Samsung NVMe SSD Drive 512GB       | 2         | 0.6%    |
| Samsung NVMe SSD Drive 1024GB      | 2         | 0.6%    |
| Samsung HM500JI 500GB              | 2         | 0.6%    |
| Kingston SV300S37A240G 240GB SSD   | 2         | 0.6%    |
| Kingston SV300S37A120G 120GB SSD   | 2         | 0.6%    |
| Kingston SA400S37240G 240GB SSD    | 2         | 0.6%    |
| Crucial CT500MX500SSD1 500GB       | 2         | 0.6%    |
| Crucial CT1000MX500SSD1 1TB        | 2         | 0.6%    |
| China SATA SSD 120GB               | 2         | 0.6%    |
| Apple SSD SM0256G 256GB            | 2         | 0.6%    |
| Unknown                            | 2         | 0.6%    |
| YMTC PC005 512GB                   | 1         | 0.3%    |
| YMTC PC005 256GB                   | 1         | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 33        | 37     | 28.21%  |
| WDC                 | 29        | 33     | 24.79%  |
| Seagate             | 24        | 24     | 20.51%  |
| Hitachi             | 12        | 14     | 10.26%  |
| HGST                | 8         | 11     | 6.84%   |
| Samsung Electronics | 5         | 5      | 4.27%   |
| Unknown             | 4         | 5      | 3.42%   |
| Fujitsu             | 1         | 1      | 0.85%   |
| ASMedia             | 1         | 1      | 0.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 21        | 24     | 21%     |
| Kingston            | 9         | 9      | 9%      |
| Crucial             | 9         | 14     | 9%      |
| SanDisk             | 8         | 9      | 8%      |
| WDC                 | 6         | 7      | 6%      |
| China               | 6         | 6      | 6%      |
| Toshiba             | 4         | 5      | 4%      |
| Micron Technology   | 4         | 4      | 4%      |
| Apple               | 4         | 4      | 4%      |
| LITEON              | 3         | 3      | 3%      |
| Team                | 2         | 2      | 2%      |
| PNY                 | 2         | 2      | 2%      |
| Intel               | 2         | 2      | 2%      |
| A-DATA Technology   | 2         | 2      | 2%      |
| W800SH              | 1         | 1      | 1%      |
| Unknown             | 1         | 1      | 1%      |
| Transcend           | 1         | 1      | 1%      |
| SK hynix            | 1         | 1      | 1%      |
| S3+                 | 1         | 1      | 1%      |
| RZX                 | 1         | 1      | 1%      |
| Patriot             | 1         | 1      | 1%      |
| Netac               | 1         | 1      | 1%      |
| LITEONIT            | 1         | 1      | 1%      |
| KingSpec            | 1         | 2      | 1%      |
| KingFast            | 1         | 1      | 1%      |
| Intenso             | 1         | 2      | 1%      |
| HS-SSD-C100         | 1         | 1      | 1%      |
| Corsair             | 1         | 2      | 1%      |
| BR                  | 1         | 1      | 1%      |
| BHT                 | 1         | 1      | 1%      |
| ASMT                | 1         | 1      | 1%      |
| Unknown             | 1         | 1      | 1%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 114       | 131    | 37.5%   |
| SSD     | 92        | 114    | 30.26%  |
| NVMe    | 74        | 89     | 24.34%  |
| MMC     | 20        | 23     | 6.58%   |
| Unknown | 4         | 4      | 1.32%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 184       | 232    | 62.8%   |
| NVMe | 74        | 89     | 25.26%  |
| MMC  | 20        | 23     | 6.83%   |
| SAS  | 15        | 17     | 5.12%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 128       | 158    | 62.75%  |
| 0.51-1.0   | 71        | 81     | 34.8%   |
| 1.01-2.0   | 5         | 6      | 2.45%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 65        | 26%     |
| 101-250        | 54        | 21.6%   |
| 501-1000       | 41        | 16.4%   |
| 1001-2000      | 27        | 10.8%   |
| Unknown        | 24        | 9.6%    |
| 51-100         | 14        | 5.6%    |
| 21-50          | 13        | 5.2%    |
| 1-20           | 5         | 2%      |
| 2001-3000      | 4         | 1.6%    |
| More than 3000 | 3         | 1.2%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 21-50          | 77        | 29.96%  |
| 51-100         | 48        | 18.68%  |
| 1-20           | 40        | 15.56%  |
| 101-250        | 31        | 12.06%  |
| 251-500        | 26        | 10.12%  |
| Unknown        | 24        | 9.34%   |
| 501-1000       | 8         | 3.11%   |
| More than 3000 | 1         | 0.39%   |
| 1001-2000      | 1         | 0.39%   |
| 0              | 1         | 0.39%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Samsung Electronics HM500JI 500GB                   | 2         | 2      | 8.33%   |
| WDC WD3200BPVT-00JJ5T0 320GB                        | 1         | 1      | 4.17%   |
| WDC WD2500BEVT-22A23T0 250GB                        | 1         | 1      | 4.17%   |
| Toshiba MQ01ABD100 1TB                              | 1         | 1      | 4.17%   |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 4.17%   |
| Toshiba MK3265GSXF 320GB                            | 1         | 1      | 4.17%   |
| Seagate ST320LM001 HN-M320MBB 320GB                 | 1         | 1      | 4.17%   |
| Seagate ST2000LM007-1R8174 2TB                      | 1         | 1      | 4.17%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1      | 4.17%   |
| SanDisk SD8SBAT256G1122 256GB SSD                   | 1         | 1      | 4.17%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD    | 1         | 1      | 4.17%   |
| Samsung Electronics HM160HI 160GB                   | 1         | 1      | 4.17%   |
| Micron Technology MTFDDAK128MAY-1AH1ZABHA 128GB SSD | 1         | 1      | 4.17%   |
| LITEON CV8-8E128-HP 128GB SSD                       | 1         | 1      | 4.17%   |
| Intel HBRPEKNX0202AHO 32GB                          | 1         | 1      | 4.17%   |
| Hitachi HTS725050A9A360 500GB                       | 1         | 1      | 4.17%   |
| Hitachi HTS725032A9A364 320GB                       | 1         | 1      | 4.17%   |
| Hitachi HTS723216L9SA60 160GB                       | 1         | 1      | 4.17%   |
| Hitachi HTS542512K9SA00 120GB                       | 1         | 1      | 4.17%   |
| HGST HTS721010A9E630 1TB                            | 1         | 1      | 4.17%   |
| Fujitsu MHY2160BH 160GB                             | 1         | 1      | 4.17%   |
| A-DATA Technology SX6000LNP 1TB                     | 1         | 1      | 4.17%   |
| A-DATA Technology SU700 120GB SSD                   | 1         | 1      | 4.17%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 4      | 16.67%  |
| Hitachi             | 4         | 4      | 16.67%  |
| Toshiba             | 3         | 3      | 12.5%   |
| Seagate             | 3         | 3      | 12.5%   |
| WDC                 | 2         | 2      | 8.33%   |
| A-DATA Technology   | 2         | 2      | 8.33%   |
| SanDisk             | 1         | 1      | 4.17%   |
| Micron Technology   | 1         | 1      | 4.17%   |
| LITEON              | 1         | 1      | 4.17%   |
| Intel               | 1         | 1      | 4.17%   |
| HGST                | 1         | 1      | 4.17%   |
| Fujitsu             | 1         | 1      | 4.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 4         | 4      | 23.53%  |
| Toshiba             | 3         | 3      | 17.65%  |
| Seagate             | 3         | 3      | 17.65%  |
| Samsung Electronics | 3         | 3      | 17.65%  |
| WDC                 | 2         | 2      | 11.76%  |
| HGST                | 1         | 1      | 5.88%   |
| Fujitsu             | 1         | 1      | 5.88%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 17        | 17     | 70.83%  |
| SSD  | 5         | 5      | 20.83%  |
| NVMe | 2         | 2      | 8.33%   |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 125       | 184    | 45.79%  |
| Works    | 125       | 153    | 45.79%  |
| Malfunc  | 23        | 24     | 8.42%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 187       | 63.82%  |
| Samsung Electronics          | 26        | 8.87%   |
| AMD                          | 25        | 8.53%   |
| SanDisk                      | 14        | 4.78%   |
| Kingston Technology Company  | 10        | 3.41%   |
| SK hynix                     | 7         | 2.39%   |
| Micron Technology            | 5         | 1.71%   |
| Silicon Motion               | 3         | 1.02%   |
| Nvidia                       | 3         | 1.02%   |
| KIOXIA                       | 3         | 1.02%   |
| Yangtze Memory Technologies  | 2         | 0.68%   |
| Toshiba America Info Systems | 2         | 0.68%   |
| ADATA Technology             | 2         | 0.68%   |
| Realtek Semiconductor        | 1         | 0.34%   |
| Phison Electronics           | 1         | 0.34%   |
| Micron/Crucial Technology    | 1         | 0.34%   |
| Apple                        | 1         | 0.34%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 22        | 6.9%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 21        | 6.58%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 20        | 6.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 18        | 5.64%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 17        | 5.33%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 14        | 4.39%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 11        | 3.45%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 10        | 3.13%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 10        | 3.13%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 9         | 2.82%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 7         | 2.19%   |
| SanDisk WD Blue SN550 NVMe SSD                                                         | 6         | 1.88%   |
| Samsung NVMe SSD Controller 980                                                        | 6         | 1.88%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 6         | 1.88%   |
| Micron Non-Volatile memory controller                                                  | 5         | 1.57%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 5         | 1.57%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 5         | 1.57%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 5         | 1.57%   |
| Kingston Company Company Non-Volatile memory controller                                | 4         | 1.25%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 4         | 1.25%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 4         | 1.25%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 4         | 1.25%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 4         | 1.25%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 4         | 1.25%   |
| SK hynix Gold P31 SSD                                                                  | 3         | 0.94%   |
| SK hynix BC511                                                                         | 3         | 0.94%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 3         | 0.94%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 3         | 0.94%   |
| SanDisk Non-Volatile memory controller                                                 | 3         | 0.94%   |
| KIOXIA NVMe SSD Controller BG4                                                         | 3         | 0.94%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 3         | 0.94%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 3         | 0.94%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 3         | 0.94%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 3         | 0.94%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 3         | 0.94%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 3         | 0.94%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 3         | 0.94%   |
| Yangtze Memory Non-Volatile memory controller                                          | 2         | 0.63%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller       | 2         | 0.63%   |
| Samsung NVMe SSD Controller SM951/PM951                                                | 2         | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 170       | 56.48%  |
| NVMe | 74        | 24.58%  |
| RAID | 32        | 10.63%  |
| IDE  | 25        | 8.31%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 212       | 86.18%  |
| AMD    | 34        | 13.82%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz       | 9         | 3.66%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 6         | 2.44%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 6         | 2.44%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 4         | 1.63%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 4         | 1.63%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 4         | 1.63%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 4         | 1.63%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 4         | 1.63%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 4         | 1.63%   |
| Intel Core i3-5005U CPU @ 2.00GHz       | 4         | 1.63%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 3         | 1.22%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 3         | 1.22%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 3         | 1.22%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 3         | 1.22%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 3         | 1.22%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 3         | 1.22%   |
| Intel Core i5-2430M CPU @ 2.40GHz       | 3         | 1.22%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz      | 3         | 1.22%   |
| Intel Core 2 CPU T5600 @ 1.83GHz        | 3         | 1.22%   |
| Intel Celeron CPU N3060 @ 1.60GHz       | 3         | 1.22%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 3         | 1.22%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 3         | 1.22%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 3         | 1.22%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 3         | 1.22%   |
| Intel Core i7-8850H CPU @ 2.60GHz       | 2         | 0.81%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 2         | 0.81%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 2         | 0.81%   |
| Intel Core i7-4600U CPU @ 2.10GHz       | 2         | 0.81%   |
| Intel Core i7-4510U CPU @ 2.00GHz       | 2         | 0.81%   |
| Intel Core i7-3630QM CPU @ 2.40GHz      | 2         | 0.81%   |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 2         | 0.81%   |
| Intel Core i7-2620M CPU @ 2.70GHz       | 2         | 0.81%   |
| Intel Core i7-10875H CPU @ 2.30GHz      | 2         | 0.81%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 2         | 0.81%   |
| Intel Core i5-8300H CPU @ 2.30GHz       | 2         | 0.81%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 2         | 0.81%   |
| Intel Core i5-4310U CPU @ 2.00GHz       | 2         | 0.81%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 2         | 0.81%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 2         | 0.81%   |
| Intel Core i5-2410M CPU @ 2.30GHz       | 2         | 0.81%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 69        | 28.05%  |
| Intel Core i7           | 64        | 26.02%  |
| Intel Core i3           | 23        | 9.35%   |
| Other                   | 20        | 8.13%   |
| Intel Celeron           | 15        | 6.1%    |
| Intel Core 2 Duo        | 9         | 3.66%   |
| AMD Ryzen 7             | 9         | 3.66%   |
| AMD Ryzen 5             | 6         | 2.44%   |
| AMD A6                  | 6         | 2.44%   |
| Intel Core 2            | 4         | 1.63%   |
| Intel Pentium           | 3         | 1.22%   |
| AMD E1                  | 3         | 1.22%   |
| Intel Pentium Silver    | 2         | 0.81%   |
| Intel Atom              | 2         | 0.81%   |
| AMD Ryzen 3             | 2         | 0.81%   |
| AMD A4                  | 2         | 0.81%   |
| Intel Pentium Dual-Core | 1         | 0.41%   |
| Intel Core 2 Quad       | 1         | 0.41%   |
| Intel Core 2 Extreme    | 1         | 0.41%   |
| AMD E2                  | 1         | 0.41%   |
| AMD E                   | 1         | 0.41%   |
| AMD C-50                | 1         | 0.41%   |
| AMD Athlon X2           | 1         | 0.41%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 136       | 55.28%  |
| 4      | 71        | 28.86%  |
| 6      | 18        | 7.32%   |
| 8      | 13        | 5.28%   |
| 14     | 3         | 1.22%   |
| 1      | 3         | 1.22%   |
| 12     | 2         | 0.81%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 246       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 185       | 75.2%   |
| 1      | 61        | 24.8%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 241       | 97.97%  |
| Unknown        | 5         | 2.03%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 110       | 43.65%  |
| 0x206a7    | 19        | 7.54%   |
| 0x806ec    | 10        | 3.97%   |
| 0x306a9    | 10        | 3.97%   |
| 0x806e9    | 8         | 3.17%   |
| 0x906ea    | 7         | 2.78%   |
| 0xa0652    | 6         | 2.38%   |
| 0x406e3    | 6         | 2.38%   |
| 0x906a3    | 5         | 1.98%   |
| 0x806ea    | 5         | 1.98%   |
| 0x706a8    | 5         | 1.98%   |
| 0x40651    | 5         | 1.98%   |
| 0x806c1    | 4         | 1.59%   |
| 0x706e5    | 4         | 1.59%   |
| 0x6f6      | 4         | 1.59%   |
| 0x306c3    | 4         | 1.59%   |
| 0x1067a    | 4         | 1.59%   |
| 0x08600106 | 3         | 1.19%   |
| 0x07030105 | 3         | 1.19%   |
| 0x906e9    | 2         | 0.79%   |
| 0x806d1    | 2         | 0.79%   |
| 0x6fd      | 2         | 0.79%   |
| 0x406c4    | 2         | 0.79%   |
| 0x306d4    | 2         | 0.79%   |
| 0x08108109 | 2         | 0.79%   |
| 0x06006705 | 2         | 0.79%   |
| 0x03000027 | 2         | 0.79%   |
| 0x906ed    | 1         | 0.4%    |
| 0x806eb    | 1         | 0.4%    |
| 0x806c2    | 1         | 0.4%    |
| 0x706a1    | 1         | 0.4%    |
| 0x506e3    | 1         | 0.4%    |
| 0x506c9    | 1         | 0.4%    |
| 0x40661    | 1         | 0.4%    |
| 0x30678    | 1         | 0.4%    |
| 0x20655    | 1         | 0.4%    |
| 0x08608103 | 1         | 0.4%    |
| 0x08108102 | 1         | 0.4%    |
| 0x0810100b | 1         | 0.4%    |
| 0x06001119 | 1         | 0.4%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 50        | 20.33%  |
| SandyBridge      | 29        | 11.79%  |
| Haswell          | 20        | 8.13%   |
| IvyBridge        | 19        | 7.72%   |
| Skylake          | 14        | 5.69%   |
| Broadwell        | 11        | 4.47%   |
| Penryn           | 10        | 4.07%   |
| TigerLake        | 9         | 3.66%   |
| Silvermont       | 9         | 3.66%   |
| CometLake        | 8         | 3.25%   |
| Unknown          | 8         | 3.25%   |
| Icelake          | 7         | 2.85%   |
| Goldmont plus    | 7         | 2.85%   |
| Core             | 7         | 2.85%   |
| Zen+             | 5         | 2.03%   |
| Zen 2            | 4         | 1.63%   |
| Westmere         | 4         | 1.63%   |
| Excavator        | 4         | 1.63%   |
| Alderlake Hybrid | 4         | 1.63%   |
| Puma             | 3         | 1.22%   |
| Jaguar           | 3         | 1.22%   |
| Zen 3            | 2         | 0.81%   |
| Piledriver       | 2         | 0.81%   |
| K10 Llano        | 2         | 0.81%   |
| Bobcat           | 2         | 0.81%   |
| Zen              | 1         | 0.41%   |
| K8 & K10 hybrid  | 1         | 0.41%   |
| Goldmont         | 1         | 0.41%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 196       | 59.76%  |
| Nvidia | 78        | 23.78%  |
| AMD    | 54        | 16.46%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 26        | 7.78%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 17        | 5.09%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 14        | 4.19%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 11        | 3.29%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 10        | 2.99%   |
| Intel HD Graphics 5500                                                                   | 10        | 2.99%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 10        | 2.99%   |
| Intel UHD Graphics 620                                                                   | 9         | 2.69%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 9         | 2.69%   |
| Intel HD Graphics 620                                                                    | 8         | 2.4%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 8         | 2.4%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 1.8%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 1.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 1.5%    |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 5         | 1.5%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 1.5%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 5         | 1.5%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 1.5%    |
| AMD Lucienne                                                                             | 5         | 1.5%    |
| Nvidia GM108M [GeForce 940MX]                                                            | 4         | 1.2%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 1.2%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 4         | 1.2%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 4         | 1.2%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1.2%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 1.2%    |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 1.2%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 1.2%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 1.2%    |
| AMD Renoir                                                                               | 4         | 1.2%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 3         | 0.9%    |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 0.9%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 0.9%    |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 3         | 0.9%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 0.9%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 0.9%    |
| Intel HD Graphics 630                                                                    | 3         | 0.9%    |
| Intel HD Graphics 530                                                                    | 3         | 0.9%    |
| AMD RV515/M54 [Mobility Radeon X1400]                                                    | 3         | 0.9%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.6%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 117       | 47.56%  |
| Intel + Nvidia | 66        | 26.83%  |
| 1 x AMD        | 37        | 15.04%  |
| Intel + AMD    | 13        | 5.28%   |
| 1 x Nvidia     | 8         | 3.25%   |
| AMD + Nvidia   | 3         | 1.22%   |
| 2 x Nvidia     | 1         | 0.41%   |
| 2 x AMD        | 1         | 0.41%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 221       | 89.84%  |
| Proprietary | 23        | 9.35%   |
| Unknown     | 2         | 0.81%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 195       | 78.63%  |
| 1.01-2.0   | 18        | 7.26%   |
| 0.01-0.5   | 13        | 5.24%   |
| 0.51-1.0   | 11        | 4.44%   |
| 3.01-4.0   | 7         | 2.82%   |
| 5.01-6.0   | 2         | 0.81%   |
| 7.01-8.0   | 1         | 0.4%    |
| 2.01-3.0   | 1         | 0.4%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 63        | 23.25%  |
| LG Display              | 47        | 17.34%  |
| BOE                     | 44        | 16.24%  |
| Chimei Innolux          | 34        | 12.55%  |
| Samsung Electronics     | 25        | 9.23%   |
| Apple                   | 10        | 3.69%   |
| Chi Mei Optoelectronics | 7         | 2.58%   |
| Sharp                   | 4         | 1.48%   |
| Lenovo                  | 4         | 1.48%   |
| Dell                    | 4         | 1.48%   |
| PANDA                   | 3         | 1.11%   |
| Acer                    | 3         | 1.11%   |
| Sceptre Tech            | 2         | 0.74%   |
| Hewlett-Packard         | 2         | 0.74%   |
| Ancor Communications    | 2         | 0.74%   |
| Unknown (AAA)           | 1         | 0.37%   |
| STD                     | 1         | 0.37%   |
| STA                     | 1         | 0.37%   |
| SANYO                   | 1         | 0.37%   |
| Planar                  | 1         | 0.37%   |
| Philips                 | 1         | 0.37%   |
| Panasonic               | 1         | 0.37%   |
| ONN                     | 1         | 0.37%   |
| NEC Computers           | 1         | 0.37%   |
| LG Philips              | 1         | 0.37%   |
| Kogan                   | 1         | 0.37%   |
| InfoVision              | 1         | 0.37%   |
| Goldstar                | 1         | 0.37%   |
| Eizo                    | 1         | 0.37%   |
| CSO                     | 1         | 0.37%   |
| BenQ                    | 1         | 0.37%   |
| AOC                     | 1         | 0.37%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 3         | 1.11%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 3         | 1.11%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 3         | 1.11%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 3         | 1.11%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch        | 3         | 1.11%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch        | 3         | 1.11%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 344x194mm 15.5-inch  | 2         | 0.74%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch  | 2         | 0.74%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch  | 2         | 0.74%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 0.74%   |
| LG Display LCD Monitor LGD0390 1600x900 382x215mm 17.3-inch           | 2         | 0.74%   |
| LG Display LCD Monitor LGD01E9 1920x1080 345x194mm 15.6-inch          | 2         | 0.74%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch      | 2         | 0.74%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 2         | 0.74%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch       | 2         | 0.74%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                 | 2         | 0.74%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch        | 2         | 0.74%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.74%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch         | 2         | 0.74%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 2         | 0.74%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch         | 2         | 0.74%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch         | 2         | 0.74%   |
| Unknown (AAA) LCDTV AAA0042 1360x768 890x500mm 40.2-inch              | 1         | 0.37%   |
| STD HDMI TV STD00C7 1680x1050 698x392mm 31.5-inch                     | 1         | 0.37%   |
| STA XR140EA1T STA0450 1366x768 310x174mm 14.0-inch                    | 1         | 0.37%   |
| Sharp LCD Monitor SHP1542 1920x1080 309x174mm 14.0-inch               | 1         | 0.37%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch               | 1         | 0.37%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch               | 1         | 0.37%   |
| Sharp LCD Monitor SHP143A 3840x2160 346x194mm 15.6-inch               | 1         | 0.37%   |
| Sceptre Tech Sceptre F24 SPT09AB 1920x1080 521x293mm 23.5-inch        | 1         | 0.37%   |
| Sceptre Tech Sceptre B30 SPT0BC2 2560x1080 690x291mm 29.5-inch        | 1         | 0.37%   |
| SANYO LCD SAN0B51 1920x540                                            | 1         | 0.37%   |
| Samsung Electronics SyncMaster SAM0589 1920x1080 521x293mm 23.5-inch  | 1         | 0.37%   |
| Samsung Electronics SMT24A550 SAM07B5 1920x1080 531x299mm 24.0-inch   | 1         | 0.37%   |
| Samsung Electronics S27E510 SAM0C5F 1920x1080 600x340mm 27.2-inch     | 1         | 0.37%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch | 1         | 0.37%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.37%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch  | 1         | 0.37%   |
| Samsung Electronics LCD Monitor SEC4145 1366x768 310x170mm 13.9-inch  | 1         | 0.37%   |
| Samsung Electronics LCD Monitor SEC3942 1366x768 309x174mm 14.0-inch  | 1         | 0.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 109       | 42.25%  |
| 1366x768 (WXGA)    | 92        | 35.66%  |
| 1600x900 (HD+)     | 16        | 6.2%    |
| 1280x800 (WXGA)    | 11        | 4.26%   |
| 1440x900 (WXGA+)   | 5         | 1.94%   |
| 3840x2160 (4K)     | 4         | 1.55%   |
| 1680x1050 (WSXGA+) | 4         | 1.55%   |
| 2560x1600          | 3         | 1.16%   |
| 2880x1800          | 2         | 0.78%   |
| 2560x1440 (QHD)    | 2         | 0.78%   |
| 2160x1440          | 2         | 0.78%   |
| 1920x1200 (WUXGA)  | 2         | 0.78%   |
| 1024x768 (XGA)     | 2         | 0.78%   |
| 2560x1080          | 1         | 0.39%   |
| 1920x540           | 1         | 0.39%   |
| 1920x515           | 1         | 0.39%   |
| 1280x1024 (SXGA)   | 1         | 0.39%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 114       | 42.38%  |
| 14      | 39        | 14.5%   |
| 13      | 36        | 13.38%  |
| 17      | 24        | 8.92%   |
| 12      | 11        | 4.09%   |
| 24      | 6         | 2.23%   |
| 11      | 6         | 2.23%   |
| 31      | 4         | 1.49%   |
| 27      | 4         | 1.49%   |
| 21      | 4         | 1.49%   |
| 16      | 4         | 1.49%   |
| 23      | 3         | 1.12%   |
| 22      | 3         | 1.12%   |
| 19      | 2         | 0.74%   |
| 18      | 2         | 0.74%   |
| Unknown | 2         | 0.74%   |
| 54      | 1         | 0.37%   |
| 48      | 1         | 0.37%   |
| 40      | 1         | 0.37%   |
| 32      | 1         | 0.37%   |
| 29      | 1         | 0.37%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 176       | 65.67%  |
| 201-300     | 30        | 11.19%  |
| 351-400     | 29        | 10.82%  |
| 501-600     | 13        | 4.85%   |
| 401-500     | 9         | 3.36%   |
| 601-700     | 5         | 1.87%   |
| 1001-1500   | 2         | 0.75%   |
| Unknown     | 2         | 0.75%   |
| 801-900     | 1         | 0.37%   |
| 701-800     | 1         | 0.37%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 215       | 86%     |
| 16/10 | 27        | 10.8%   |
| 4/3   | 2         | 0.8%    |
| 3/2   | 2         | 0.8%    |
| 6/5   | 1         | 0.4%    |
| 32/9  | 1         | 0.4%    |
| 3.73  | 1         | 0.4%    |
| 21/9  | 1         | 0.4%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 116       | 43.12%  |
| 81-90          | 64        | 23.79%  |
| 121-130        | 21        | 7.81%   |
| 201-250        | 14        | 5.2%    |
| 71-80          | 11        | 4.09%   |
| 61-70          | 11        | 4.09%   |
| 51-60          | 6         | 2.23%   |
| 351-500        | 5         | 1.86%   |
| 301-350        | 5         | 1.86%   |
| 131-140        | 3         | 1.12%   |
| More than 1000 | 2         | 0.74%   |
| 251-300        | 2         | 0.74%   |
| 151-200        | 2         | 0.74%   |
| 141-150        | 2         | 0.74%   |
| 111-120        | 2         | 0.74%   |
| Unknown        | 2         | 0.74%   |
| 501-1000       | 1         | 0.37%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 114       | 42.7%   |
| 101-120       | 93        | 34.83%  |
| 51-100        | 37        | 13.86%  |
| 161-240       | 15        | 5.62%   |
| More than 240 | 3         | 1.12%   |
| 1-50          | 3         | 1.12%   |
| Unknown       | 2         | 0.75%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 212       | 85.48%  |
| 2     | 30        | 12.1%   |
| 3     | 4         | 1.61%   |
| 0     | 2         | 0.81%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 143       | 34.46%  |
| Realtek Semiconductor                  | 132       | 31.81%  |
| Qualcomm Atheros                       | 51        | 12.29%  |
| Broadcom                               | 24        | 5.78%   |
| MediaTek                               | 8         | 1.93%   |
| Broadcom Limited                       | 8         | 1.93%   |
| TP-Link                                | 6         | 1.45%   |
| Samsung Electronics                    | 6         | 1.45%   |
| Huawei Technologies                    | 5         | 1.2%    |
| Qualcomm Atheros Communications        | 4         | 0.96%   |
| Xiaomi                                 | 3         | 0.72%   |
| Ralink Technology                      | 3         | 0.72%   |
| NetGear                                | 3         | 0.72%   |
| ASUSTek Computer                       | 3         | 0.72%   |
| Nvidia                                 | 2         | 0.48%   |
| ASIX Electronics                       | 2         | 0.48%   |
| Apple                                  | 2         | 0.48%   |
| ZyXEL Communications                   | 1         | 0.24%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.24%   |
| Sagem                                  | 1         | 0.24%   |
| Ralink                                 | 1         | 0.24%   |
| Linksys                                | 1         | 0.24%   |
| Lenovo                                 | 1         | 0.24%   |
| JMicron Technology                     | 1         | 0.24%   |
| Ericsson Business Mobile Networks      | 1         | 0.24%   |
| Belkin Components                      | 1         | 0.24%   |
| Arduino SA                             | 1         | 0.24%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 69        | 13.8%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 29        | 5.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 15        | 3%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 13        | 2.6%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 10        | 2%      |
| Intel Wireless 8265 / 8275                                        | 9         | 1.8%    |
| Intel Wireless 7260                                               | 9         | 1.8%    |
| Intel Wi-Fi 6 AX200                                               | 9         | 1.8%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 1.6%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 8         | 1.6%    |
| Intel Wireless 7265                                               | 8         | 1.6%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 8         | 1.6%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 8         | 1.6%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 7         | 1.4%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 7         | 1.4%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 7         | 1.4%    |
| Intel Wireless 3165                                               | 6         | 1.2%    |
| Intel Wi-Fi 6 AX201                                               | 6         | 1.2%    |
| Intel Ethernet Connection I218-LM                                 | 6         | 1.2%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 6         | 1.2%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 6         | 1.2%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 5         | 1%      |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 5         | 1%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 0.8%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 4         | 0.8%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 0.8%    |
| Realtek 802.11ac NIC                                              | 4         | 0.8%    |
| Qualcomm Atheros AR9271 802.11n                                   | 4         | 0.8%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4         | 0.8%    |
| Intel Wireless 8260                                               | 4         | 0.8%    |
| Intel Wireless 3160                                               | 4         | 0.8%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 4         | 0.8%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4         | 0.8%    |
| Intel Centrino Advanced-N 6235                                    | 4         | 0.8%    |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 4         | 0.8%    |
| Broadcom BCM43142 802.11b/g/n                                     | 4         | 0.8%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 3         | 0.6%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 3         | 0.6%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 3         | 0.6%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 0.6%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 139       | 49.29%  |
| Realtek Semiconductor           | 48        | 17.02%  |
| Qualcomm Atheros                | 39        | 13.83%  |
| Broadcom                        | 20        | 7.09%   |
| TP-Link                         | 6         | 2.13%   |
| MediaTek                        | 6         | 2.13%   |
| Broadcom Limited                | 6         | 2.13%   |
| Qualcomm Atheros Communications | 4         | 1.42%   |
| Ralink Technology               | 3         | 1.06%   |
| NetGear                         | 3         | 1.06%   |
| ASUSTek Computer                | 3         | 1.06%   |
| ZyXEL Communications            | 1         | 0.35%   |
| Sagem                           | 1         | 0.35%   |
| Ralink                          | 1         | 0.35%   |
| Linksys                         | 1         | 0.35%   |
| Belkin Components               | 1         | 0.35%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 13        | 4.61%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 10        | 3.55%   |
| Intel Wireless 8265 / 8275                                     | 9         | 3.19%   |
| Intel Wireless 7260                                            | 9         | 3.19%   |
| Intel Wi-Fi 6 AX200                                            | 9         | 3.19%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 8         | 2.84%   |
| Intel Wireless 7265                                            | 8         | 2.84%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 8         | 2.84%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 8         | 2.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 7         | 2.48%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 7         | 2.48%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 7         | 2.48%   |
| Intel Wireless 3165                                            | 6         | 2.13%   |
| Intel Wi-Fi 6 AX201                                            | 6         | 2.13%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 6         | 2.13%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 6         | 2.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 4         | 1.42%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 4         | 1.42%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 1.42%   |
| Realtek 802.11ac NIC                                           | 4         | 1.42%   |
| Qualcomm Atheros AR9271 802.11n                                | 4         | 1.42%   |
| Intel Wireless 8260                                            | 4         | 1.42%   |
| Intel Wireless 3160                                            | 4         | 1.42%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 4         | 1.42%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 4         | 1.42%   |
| Intel Centrino Advanced-N 6235                                 | 4         | 1.42%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 4         | 1.42%   |
| Broadcom BCM43142 802.11b/g/n                                  | 4         | 1.42%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 3         | 1.06%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 3         | 1.06%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 3         | 1.06%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 3         | 1.06%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 3         | 1.06%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 3         | 1.06%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 3         | 1.06%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 3         | 1.06%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 1.06%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 2         | 0.71%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 2         | 0.71%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 2         | 0.71%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 114       | 54.55%  |
| Intel                 | 44        | 21.05%  |
| Qualcomm Atheros      | 20        | 9.57%   |
| Broadcom              | 8         | 3.83%   |
| Samsung Electronics   | 6         | 2.87%   |
| Xiaomi                | 3         | 1.44%   |
| Nvidia                | 2         | 0.96%   |
| MediaTek              | 2         | 0.96%   |
| Huawei Technologies   | 2         | 0.96%   |
| Broadcom Limited      | 2         | 0.96%   |
| ASIX Electronics      | 2         | 0.96%   |
| Apple                 | 2         | 0.96%   |
| Lenovo                | 1         | 0.48%   |
| JMicron Technology    | 1         | 0.48%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 69        | 32.55%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 29        | 13.68%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 15        | 7.08%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 3.77%   |
| Intel Ethernet Connection I218-LM                                 | 6         | 2.83%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 5         | 2.36%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 5         | 2.36%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4         | 1.89%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 1.42%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 3         | 1.42%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 1.42%   |
| Intel Ethernet Connection (6) I219-V                              | 3         | 1.42%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.42%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 3         | 1.42%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.94%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.94%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.94%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 0.94%   |
| MediaTek TECNO Pouvoir 3 Air                                      | 2         | 0.94%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.94%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.94%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.94%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 0.94%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.94%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.47%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.47%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.47%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.47%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.47%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.47%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.47%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.47%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.47%   |
| Nvidia MCP89 Ethernet                                             | 1         | 0.47%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.47%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 0.47%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.47%   |
| Intel PRO/100 VE Network Connection                               | 1         | 0.47%   |
| Intel Ethernet controller                                         | 1         | 0.47%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.47%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 244       | 54.46%  |
| Ethernet | 198       | 44.2%   |
| Modem    | 5         | 1.12%   |
| Unknown  | 1         | 0.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 203       | 77.78%  |
| Ethernet | 57        | 21.84%  |
| Unknown  | 1         | 0.38%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 178       | 72.36%  |
| 1     | 62        | 25.2%   |
| 0     | 4         | 1.63%   |
| 3     | 2         | 0.81%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Notebooks | Percent |
|---------|-----------|---------|
| No      | 205       | 82%     |
| Yes     | 44        | 17.6%   |
| Unknown | 1         | 0.4%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 102       | 51.26%  |
| Qualcomm Atheros Communications | 22        | 11.06%  |
| Realtek Semiconductor           | 18        | 9.05%   |
| Broadcom                        | 15        | 7.54%   |
| Lite-On Technology              | 7         | 3.52%   |
| Foxconn / Hon Hai               | 7         | 3.52%   |
| Apple                           | 7         | 3.52%   |
| IMC Networks                    | 5         | 2.51%   |
| Cambridge Silicon Radio         | 4         | 2.01%   |
| MediaTek                        | 3         | 1.51%   |
| Dell                            | 3         | 1.51%   |
| Toshiba                         | 2         | 1.01%   |
| Realtek                         | 1         | 0.5%    |
| Ralink                          | 1         | 0.5%    |
| Dynex                           | 1         | 0.5%    |
| Alps Electric                   | 1         | 0.5%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 38        | 19.1%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 23        | 11.56%  |
| Intel AX201 Bluetooth                                                               | 22        | 11.06%  |
| Realtek Bluetooth Radio                                                             | 10        | 5.03%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 9         | 4.52%   |
| Intel AX200 Bluetooth                                                               | 8         | 4.02%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 5         | 2.51%   |
| Apple Bluetooth Host Controller                                                     | 5         | 2.51%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 4         | 2.01%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 4         | 2.01%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 4         | 2.01%   |
| Broadcom HP Portable SoftSailing                                                    | 4         | 2.01%   |
| Qualcomm Atheros Bluetooth                                                          | 3         | 1.51%   |
| MediaTek Wireless_Device                                                            | 3         | 1.51%   |
| Dell DW375 Bluetooth Module                                                         | 3         | 1.51%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 3         | 1.51%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 3         | 1.51%   |
| Realtek RTL8821A Bluetooth                                                          | 2         | 1.01%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 2         | 1.01%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 1.01%   |
| Lite-On Wireless_Device                                                             | 2         | 1.01%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 2         | 1.01%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 1.01%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 2         | 1.01%   |
| IMC Networks Bluetooth Radio                                                        | 2         | 1.01%   |
| IMC Networks Bluetooth Device                                                       | 2         | 1.01%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 1.01%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 1.01%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 2         | 1.01%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 2         | 1.01%   |
| Apple Bluetooth USB Host Controller                                                 | 2         | 1.01%   |
| Toshiba Bluetooth USB Host Controller                                               | 1         | 0.5%    |
| Toshiba BCM43142A0                                                                  | 1         | 0.5%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.5%    |
| Realtek Bluetooth Radio                                                             | 1         | 0.5%    |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.5%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.5%    |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.5%    |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.5%    |
| Lite-On Bluetooth Radio                                                             | 1         | 0.5%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor    | Notebooks | Percent |
|-----------|-----------|---------|
| Intel     | 206       | 70.55%  |
| Nvidia    | 44        | 15.07%  |
| AMD       | 38        | 13.01%  |
| Lenovo    | 1         | 0.34%   |
| Guillemot | 1         | 0.34%   |
| GN Netcom | 1         | 0.34%   |
| Apple     | 1         | 0.34%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 29        | 8.22%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 26        | 7.37%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 22        | 6.23%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 16        | 4.53%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 14        | 3.97%   |
| Intel 8 Series HD Audio Controller                                                                | 14        | 3.97%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 11        | 3.12%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 11        | 3.12%   |
| Intel Cannon Lake PCH cAVS                                                                        | 11        | 3.12%   |
| Intel Broadwell-U Audio Controller                                                                | 11        | 3.12%   |
| AMD FCH Azalia Controller                                                                         | 10        | 2.83%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 9         | 2.55%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 9         | 2.55%   |
| Intel Comet Lake PCH cAVS                                                                         | 8         | 2.27%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 7         | 1.98%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 7         | 1.98%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 1.7%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 1.7%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 1.7%    |
| AMD Kabini HDMI/DP Audio                                                                          | 6         | 1.7%    |
| Nvidia TU106 High Definition Audio Controller                                                     | 5         | 1.42%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 1.42%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 1.42%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 5         | 1.42%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 5         | 1.42%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1.13%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 4         | 1.13%   |
| Nvidia Audio device                                                                               | 4         | 1.13%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 4         | 1.13%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 1.13%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 1.13%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 1.13%   |
| AMD High Definition Audio Controller                                                              | 4         | 1.13%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 1.13%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 0.85%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 0.85%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 0.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.85%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 0.85%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 0.85%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 57        | 30.65%  |
| SK hynix            | 33        | 17.74%  |
| Micron Technology   | 31        | 16.67%  |
| Crucial             | 12        | 6.45%   |
| Kingston            | 10        | 5.38%   |
| Unknown             | 8         | 4.3%    |
| Ramaxel Technology  | 7         | 3.76%   |
| Elpida              | 7         | 3.76%   |
| Unknown (ABCD)      | 4         | 2.15%   |
| Corsair             | 3         | 1.61%   |
| A-DATA Technology   | 3         | 1.61%   |
| Team                | 2         | 1.08%   |
| Nanya Technology    | 2         | 1.08%   |
| G.Skill             | 2         | 1.08%   |
| Timetec             | 1         | 0.54%   |
| Teikon              | 1         | 0.54%   |
| Smart               | 1         | 0.54%   |
| Saikano             | 1         | 0.54%   |
| PNY                 | 1         | 0.54%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 3.06%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 3.06%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 4         | 2.04%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 2.04%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 1.53%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 3         | 1.53%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 1.53%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 1.53%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 1.53%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 3         | 1.53%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 3         | 1.53%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 2         | 1.02%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 1.02%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.02%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 1.02%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 2         | 1.02%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.02%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.02%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1.02%   |
| Samsung RAM M4 70T2953CZ3-CE6 1GB SODIMM DDR 667MT/s             | 2         | 1.02%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 2         | 1.02%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 1.02%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 2         | 1.02%   |
| Micron RAM 16JSF51264HZ-1G4D1 4096MB SODIMM DDR3 1334MT/s        | 2         | 1.02%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                       | 2         | 1.02%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 2         | 1.02%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.51%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 1         | 0.51%   |
| Unknown RAM Module 4096MB SODIMM 1066MT/s                        | 1         | 0.51%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.51%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 0.51%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                       | 1         | 0.51%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 1         | 0.51%   |
| Timetec RAM SD3-1333 8GB SODIMM DDR3 1333MT/s                    | 1         | 0.51%   |
| Teikon RAM TMT451S6BFR8A-PBHJ 4GB SODIMM DDR3 1600MT/s           | 1         | 0.51%   |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s             | 1         | 0.51%   |
| Team RAM TEAMGROUP-SD3-1600 8GB SODIMM DDR3 1600MT/s             | 1         | 0.51%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.51%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s             | 1         | 0.51%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1066MT/s                  | 1         | 0.51%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 70        | 44.3%   |
| DDR3    | 62        | 39.24%  |
| LPDDR4  | 10        | 6.33%   |
| LPDDR3  | 5         | 3.16%   |
| DDR2    | 5         | 3.16%   |
| DDR5    | 3         | 1.9%    |
| SDRAM   | 1         | 0.63%   |
| DDR     | 1         | 0.63%   |
| Unknown | 1         | 0.63%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 144       | 91.14%  |
| Row Of Chips | 12        | 7.59%   |
| Chip         | 1         | 0.63%   |
| Unknown      | 1         | 0.63%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 66        | 38.82%  |
| 8192  | 59        | 34.71%  |
| 16384 | 20        | 11.76%  |
| 2048  | 15        | 8.82%   |
| 1024  | 7         | 4.12%   |
| 32768 | 3         | 1.76%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 42        | 24.28%  |
| 1600    | 41        | 23.7%   |
| 3200    | 22        | 12.72%  |
| 2400    | 15        | 8.67%   |
| 1334    | 13        | 7.51%   |
| 2133    | 7         | 4.05%   |
| 1333    | 7         | 4.05%   |
| 4800    | 3         | 1.73%   |
| 3266    | 3         | 1.73%   |
| 1867    | 3         | 1.73%   |
| 1067    | 3         | 1.73%   |
| 1066    | 3         | 1.73%   |
| 667     | 3         | 1.73%   |
| Unknown | 2         | 1.16%   |
| 8400    | 1         | 0.58%   |
| 4267    | 1         | 0.58%   |
| 2048    | 1         | 0.58%   |
| 975     | 1         | 0.58%   |
| 800     | 1         | 0.58%   |
| 533     | 1         | 0.58%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Brother Industries | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Brother HL-1210W series | 1         | 100%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 65        | 29.41%  |
| Acer                                   | 24        | 10.86%  |
| IMC Networks                           | 23        | 10.41%  |
| Microdia                               | 19        | 8.6%    |
| Sunplus Innovation Technology          | 14        | 6.33%   |
| Realtek Semiconductor                  | 11        | 4.98%   |
| Quanta                                 | 9         | 4.07%   |
| Apple                                  | 9         | 4.07%   |
| Syntek                                 | 6         | 2.71%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 2.71%   |
| Ricoh                                  | 5         | 2.26%   |
| Luxvisions Innotech Limited            | 5         | 2.26%   |
| Suyin                                  | 4         | 1.81%   |
| Samsung Electronics                    | 4         | 1.81%   |
| Silicon Motion                         | 3         | 1.36%   |
| Lite-On Technology                     | 3         | 1.36%   |
| Alcor Micro                            | 3         | 1.36%   |
| Importek                               | 2         | 0.9%    |
| USB Camera CS                          | 1         | 0.45%   |
| Primax Electronics                     | 1         | 0.45%   |
| LG Electronics                         | 1         | 0.45%   |
| icSpring                               | 1         | 0.45%   |
| Goertek Electronics                    | 1         | 0.45%   |
| ALi                                    | 1         | 0.45%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony integrated camera                            | 9         | 4.07%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 7         | 3.17%   |
| Acer HD Webcam                                       | 7         | 3.17%   |
| Realtek Integrated_Webcam_HD                         | 6         | 2.71%   |
| IMC Networks Integrated Camera                       | 6         | 2.71%   |
| Chicony HD Webcam                                    | 6         | 2.71%   |
| Chicony HD User Facing                               | 6         | 2.71%   |
| Syntek Integrated Camera                             | 5         | 2.26%   |
| Microdia Integrated_Webcam_HD                        | 5         | 2.26%   |
| Chicony USB2.0 Camera                                | 5         | 2.26%   |
| Chicony HP Truevision HD                             | 5         | 2.26%   |
| Sunplus Integrated_Webcam_HD                         | 4         | 1.81%   |
| Samsung Galaxy series, misc. (MTP mode)              | 4         | 1.81%   |
| Acer EasyCamera                                      | 4         | 1.81%   |
| Quanta HP TrueVision HD Camera                       | 3         | 1.36%   |
| Microdia Webcam Vitade AF                            | 3         | 1.36%   |
| Microdia Integrated Webcam                           | 3         | 1.36%   |
| IMC Networks HD Camera                               | 3         | 1.36%   |
| Chicony USB2.0 HD UVC WebCam                         | 3         | 1.36%   |
| Apple iPhone 5/5C/5S/6/SE                            | 3         | 1.36%   |
| Alcor Micro USB 2.0 WebCamera                        | 3         | 1.36%   |
| Acer SunplusIT Integrated Camera                     | 3         | 1.36%   |
| Sunplus HD WebCam                                    | 2         | 0.9%    |
| Realtek Integrated Webcam                            | 2         | 0.9%    |
| Quanta HD User Facing                                | 2         | 0.9%    |
| Microdia PC Microscope camera                        | 2         | 0.9%    |
| Microdia Laptop_Integrated_Webcam_HD                 | 2         | 0.9%    |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 2         | 0.9%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 2         | 0.9%    |
| Lite-On HP Wide Vision HD Camera                     | 2         | 0.9%    |
| IMC Networks USB2.0 VGA UVC WebCam                   | 2         | 0.9%    |
| Chicony USB2.0 VGA UVC WebCam                        | 2         | 0.9%    |
| Chicony TOSHIBA Web Camera - HD                      | 2         | 0.9%    |
| Chicony Lenovo Integrated Camera (0.3MP)             | 2         | 0.9%    |
| Chicony Integrated HP HD Webcam                      | 2         | 0.9%    |
| Chicony Integrated Camera [ThinkPad]                 | 2         | 0.9%    |
| Chicony Integrated Camera (1280x720@30)              | 2         | 0.9%    |
| Chicony HP HD Webcam [Fixed]                         | 2         | 0.9%    |
| Chicony HP HD Camera                                 | 2         | 0.9%    |
| Chicony FJ Camera                                    | 2         | 0.9%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 18        | 43.9%   |
| Synaptics                  | 9         | 21.95%  |
| Shenzhen Goodix Technology | 5         | 12.2%   |
| Elan Microelectronics      | 3         | 7.32%   |
| Upek                       | 2         | 4.88%   |
| LighTuning Technology      | 2         | 4.88%   |
| AuthenTec                  | 2         | 4.88%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 4         | 9.76%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 7.32%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 7.32%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 7.32%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 7.32%   |
| Validity Sensors VFS491                                                    | 2         | 4.88%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 4.88%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 4.88%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 4.88%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 4.88%   |
| Elan ELAN:Fingerprint                                                      | 2         | 4.88%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 2.44%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 2.44%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.44%   |
| Synaptics  WBDI                                                            | 1         | 2.44%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 2.44%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 2.44%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 2.44%   |
| LighTuning EgisTec_ES603                                                   | 1         | 2.44%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 2.44%   |
| Elan ELAN:ARM-M4                                                           | 1         | 2.44%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 2.44%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 2.44%   |
| Unknown                                                                    | 1         | 2.44%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 10        | 62.5%   |
| Alcor Micro | 4         | 25%     |
| OmniKey     | 1         | 6.25%   |
| O2 Micro    | 1         | 6.25%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 37.5%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 4         | 25%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 18.75%  |
| OmniKey CardMan Smart@Link                                                   | 1         | 6.25%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 6.25%   |
| Broadcom 5880                                                                | 1         | 6.25%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 151       | 60.4%   |
| 1     | 79        | 31.6%   |
| 2     | 18        | 7.2%    |
| 3     | 2         | 0.8%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 42        | 36.21%  |
| Graphics card         | 17        | 14.66%  |
| Chipcard              | 15        | 12.93%  |
| Net/wireless          | 14        | 12.07%  |
| Multimedia controller | 10        | 8.62%   |
| Camera                | 7         | 6.03%   |
| Storage               | 5         | 4.31%   |
| Network               | 3         | 2.59%   |
| Modem                 | 1         | 0.86%   |
| Card reader           | 1         | 0.86%   |
| Bluetooth             | 1         | 0.86%   |

