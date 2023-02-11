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

Total: 379

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d800b8a4b9](https://linux-hardware.org/?probe=d800b8a4b9) | Jan 30, 2023 |
| Apple         | MacBookAir7,2               | [91e33f05ed](https://linux-hardware.org/?probe=91e33f05ed) | Jan 24, 2023 |
| MSI           | Katana GF66 12UC            | [543136f475](https://linux-hardware.org/?probe=543136f475) | Jan 20, 2023 |
| HP            | Laptop 15-dy1xxx            | [4b76c154f3](https://linux-hardware.org/?probe=4b76c154f3) | Jan 20, 2023 |
| Quanta        | TW9/SW9                     | [4a196739f5](https://linux-hardware.org/?probe=4a196739f5) | Jan 18, 2023 |
| Lenovo        | ThinkPad E590 20NB0003AD    | [fe3de007e1](https://linux-hardware.org/?probe=fe3de007e1) | Jan 16, 2023 |
| Intel Clie... | LAPBC510                    | [493f0e9608](https://linux-hardware.org/?probe=493f0e9608) | Jan 13, 2023 |
| Intel Clie... | LAPBC510                    | [ac0b81bf2e](https://linux-hardware.org/?probe=ac0b81bf2e) | Jan 13, 2023 |
| Dell          | XPS 13 9380                 | [d8ab62070c](https://linux-hardware.org/?probe=d8ab62070c) | Jan 11, 2023 |
| Dell          | Latitude E6520              | [96679022de](https://linux-hardware.org/?probe=96679022de) | Jan 06, 2023 |
| Acer          | Aspire A315-58              | [3629e42dc4](https://linux-hardware.org/?probe=3629e42dc4) | Jan 04, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [0df48a29e1](https://linux-hardware.org/?probe=0df48a29e1) | Jan 03, 2023 |
| Unknown       | Unknown                     | [1e55cad727](https://linux-hardware.org/?probe=1e55cad727) | Dec 25, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [aaac67afbe](https://linux-hardware.org/?probe=aaac67afbe) | Dec 23, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [5bbf457036](https://linux-hardware.org/?probe=5bbf457036) | Dec 22, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [be01b942ed](https://linux-hardware.org/?probe=be01b942ed) | Dec 22, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [4fc06d2c89](https://linux-hardware.org/?probe=4fc06d2c89) | Dec 22, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [3c22afd21b](https://linux-hardware.org/?probe=3c22afd21b) | Dec 22, 2022 |
| HUAWEI        | BOD-WXX9                    | [7895ac3dc1](https://linux-hardware.org/?probe=7895ac3dc1) | Dec 17, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | [30f6db8749](https://linux-hardware.org/?probe=30f6db8749) | Dec 17, 2022 |
| Dell          | G3 3500                     | [5b23644904](https://linux-hardware.org/?probe=5b23644904) | Dec 05, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [90db11aeba](https://linux-hardware.org/?probe=90db11aeba) | Dec 04, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [6c74973e99](https://linux-hardware.org/?probe=6c74973e99) | Dec 04, 2022 |
| Intel Clie... | LAPBC510                    | [e903f5edea](https://linux-hardware.org/?probe=e903f5edea) | Dec 02, 2022 |
| MSI           | GT60                        | [07557bed1b](https://linux-hardware.org/?probe=07557bed1b) | Nov 29, 2022 |
| Quanta        | TW9/SW9                     | [5bfeb648aa](https://linux-hardware.org/?probe=5bfeb648aa) | Nov 28, 2022 |
| Quanta        | TW9/SW9                     | [ba75780c3e](https://linux-hardware.org/?probe=ba75780c3e) | Nov 28, 2022 |
| Intel Clie... | LAPBC510                    | [f58ff7b6fa](https://linux-hardware.org/?probe=f58ff7b6fa) | Nov 27, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [3050d57edc](https://linux-hardware.org/?probe=3050d57edc) | Nov 17, 2022 |
| HP            | Laptop 15-bs0xx             | [b152ccfb56](https://linux-hardware.org/?probe=b152ccfb56) | Nov 14, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [104fb805bd](https://linux-hardware.org/?probe=104fb805bd) | Nov 09, 2022 |
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
| Parrot 5.0   | 81        | 28.62%  |
| Parrot 4.11  | 66        | 23.32%  |
| Parrot 5.1   | 47        | 16.61%  |
| Parrot 4.10  | 45        | 15.9%   |
| Parrot 4.8   | 15        | 5.3%    |
| Parrot 4.9   | 13        | 4.59%   |
| Parrot 4.7   | 10        | 3.53%   |
| Parrot 4.6   | 2         | 0.71%   |
| Parrot 4.5   | 1         | 0.35%   |
| Parrot 4.4   | 1         | 0.35%   |
| Parrot 4.2.2 | 1         | 0.35%   |
| Parrot 3.10  | 1         | 0.35%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Parrot | 269       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.14.0-9parrot1-amd64    | 37        | 12.85%  |
| 5.16.0-12parrot1-amd64   | 34        | 11.81%  |
| 5.7.0-2parrot2-amd64     | 26        | 9.03%   |
| 5.18.0-14parrot1-amd64   | 26        | 9.03%   |
| 5.10.0-6parrot1-amd64    | 25        | 8.68%   |
| 6.0.0-2parrot1-amd64     | 19        | 6.6%    |
| 5.18.0-1parrot1-amd64    | 14        | 4.86%   |
| 5.10.0-8parrot1-amd64    | 14        | 4.86%   |
| 5.5.0-1parrot1-amd64     | 12        | 4.17%   |
| 5.4.0-4parrot1-amd64     | 11        | 3.82%   |
| 5.6.0-2parrot1-amd64     | 9         | 3.13%   |
| 5.14.0-2parrot1-amd64    | 9         | 3.13%   |
| 5.9.0-2parrot1-amd64     | 7         | 2.43%   |
| 5.15.0-15parrot1-amd64   | 5         | 1.74%   |
| 6.0.0-12parrot1-amd64    | 3         | 1.04%   |
| 5.8.0-2parrot1-amd64     | 3         | 1.04%   |
| 5.4.0-2parrot1-amd64     | 3         | 1.04%   |
| 5.2.0-2parrot1-amd64     | 3         | 1.04%   |
| 5.10.0-5parrot1-amd64    | 3         | 1.04%   |
| 5.10.0-3parrot1-amd64    | 3         | 1.04%   |
| 4.19.0-parrot4-28t-amd64 | 3         | 1.04%   |
| 5.8.0-1parrot1-amd64     | 2         | 0.69%   |
| 5.4.0-3parrot1-amd64     | 2         | 0.69%   |
| 4.18.0-parrot10-amd64    | 2         | 0.69%   |
| 5.7.0-rc6-galliumos      | 1         | 0.35%   |
| 5.4.0-2parrot1-686-pae   | 1         | 0.35%   |
| 5.4.0-1parrot1-amd64     | 1         | 0.35%   |
| 5.3.0-3parrot3-amd64     | 1         | 0.35%   |
| 5.3.0-3parrot3-686-pae   | 1         | 0.35%   |
| 5.3.0-1parrot1-amd64     | 1         | 0.35%   |
| 5.15.0-5parrot1-amd64    | 1         | 0.35%   |
| 5.10.0-kali6-amd64       | 1         | 0.35%   |
| 5.10.0-6parrot1-rt-amd64 | 1         | 0.35%   |
| 5.1.0-parrot1-3t-amd64   | 1         | 0.35%   |
| 4.19.0-parrot1-13t-amd64 | 1         | 0.35%   |
| 4.14.0-parrot7-amd64     | 1         | 0.35%   |
| Unknown                  | 1         | 0.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 47        | 16.43%  |
| 5.14.0  | 45        | 15.73%  |
| 5.18.0  | 39        | 13.64%  |
| 5.16.0  | 34        | 11.89%  |
| 5.7.0   | 27        | 9.44%   |
| 6.0.0   | 22        | 7.69%   |
| 5.4.0   | 18        | 6.29%   |
| 5.5.0   | 12        | 4.2%    |
| 5.6.0   | 9         | 3.15%   |
| 5.9.0   | 7         | 2.45%   |
| 5.15.0  | 6         | 2.1%    |
| 5.8.0   | 5         | 1.75%   |
| 4.19.0  | 4         | 1.4%    |
| 5.3.0   | 3         | 1.05%   |
| 5.2.0   | 3         | 1.05%   |
| 4.18.0  | 2         | 0.7%    |
| 5.1.0   | 1         | 0.35%   |
| 4.14.0  | 1         | 0.35%   |
| Unknown | 1         | 0.35%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 47        | 16.43%  |
| 5.14    | 45        | 15.73%  |
| 5.18    | 39        | 13.64%  |
| 5.16    | 34        | 11.89%  |
| 5.7     | 27        | 9.44%   |
| 6.0     | 22        | 7.69%   |
| 5.4     | 18        | 6.29%   |
| 5.5     | 12        | 4.2%    |
| 5.6     | 9         | 3.15%   |
| 5.9     | 7         | 2.45%   |
| 5.15    | 6         | 2.1%    |
| 5.8     | 5         | 1.75%   |
| 4.19    | 4         | 1.4%    |
| 5.3     | 3         | 1.05%   |
| 5.2     | 3         | 1.05%   |
| 4.18    | 2         | 0.7%    |
| 5.1     | 1         | 0.35%   |
| 4.14    | 1         | 0.35%   |
| Unknown | 1         | 0.35%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 268       | 99.63%  |
| i686   | 1         | 0.37%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| MATE          | 186       | 67.88%  |
| KDE5          | 50        | 18.25%  |
| Unknown       | 18        | 6.57%   |
| KDE           | 13        | 4.74%   |
| XFCE          | 5         | 1.82%   |
| LXDE          | 1         | 0.36%   |
| GNOME Classic | 1         | 0.36%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 265       | 98.51%  |
| Tty     | 2         | 0.74%   |
| Wayland | 1         | 0.37%   |
| Unknown | 1         | 0.37%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 122       | 44.36%  |
| Unknown | 95        | 34.55%  |
| TDM     | 50        | 18.18%  |
| GDM     | 5         | 1.82%   |
| SDDM    | 3         | 1.09%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 138       | 51.11%  |
| en_GB   | 24        | 8.89%   |
| fr_FR   | 16        | 5.93%   |
| Unknown | 14        | 5.19%   |
| ru_RU   | 9         | 3.33%   |
| es_ES   | 9         | 3.33%   |
| pl_PL   | 8         | 2.96%   |
| pt_BR   | 7         | 2.59%   |
| de_DE   | 7         | 2.59%   |
| it_IT   | 5         | 1.85%   |
| en_IN   | 5         | 1.85%   |
| en_AU   | 5         | 1.85%   |
| es_MX   | 2         | 0.74%   |
| es_AR   | 2         | 0.74%   |
| en_CA   | 2         | 0.74%   |
| tr_TR   | 1         | 0.37%   |
| pt_PT   | 1         | 0.37%   |
| nl_BE   | 1         | 0.37%   |
| id_ID   | 1         | 0.37%   |
| fr_CA   | 1         | 0.37%   |
| fi_FI   | 1         | 0.37%   |
| es_PE   | 1         | 0.37%   |
| es_CO   | 1         | 0.37%   |
| es_CL   | 1         | 0.37%   |
| en_ZW   | 1         | 0.37%   |
| en_ZA   | 1         | 0.37%   |
| en_NZ   | 1         | 0.37%   |
| en_NG   | 1         | 0.37%   |
| en_DK   | 1         | 0.37%   |
| cs_CZ   | 1         | 0.37%   |
| C       | 1         | 0.37%   |
| arn_CL  | 1         | 0.37%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 160       | 58.82%  |
| EFI  | 112       | 41.18%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Btrfs   | 210       | 76.92%  |
| Ext4    | 41        | 15.02%  |
| Xfs     | 8         | 2.93%   |
| Overlay | 7         | 2.56%   |
| Unknown | 7         | 2.56%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 110       | 40.29%  |
| Unknown | 110       | 40.29%  |
| MBR     | 53        | 19.41%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 239       | 87.87%  |
| Yes       | 33        | 12.13%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 180       | 66.18%  |
| Yes       | 92        | 33.82%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo                | 52        | 19.33%  |
| Hewlett-Packard       | 52        | 19.33%  |
| Dell                  | 44        | 16.36%  |
| ASUSTek Computer      | 26        | 9.67%   |
| Acer                  | 18        | 6.69%   |
| MSI                   | 12        | 4.46%   |
| Apple                 | 10        | 3.72%   |
| Toshiba               | 8         | 2.97%   |
| HUAWEI                | 5         | 1.86%   |
| Samsung Electronics   | 4         | 1.49%   |
| Sony                  | 3         | 1.12%   |
| Fujitsu               | 3         | 1.12%   |
| Alienware             | 3         | 1.12%   |
| Razer                 | 2         | 0.74%   |
| Quanta                | 2         | 0.74%   |
| Gateway               | 2         | 0.74%   |
| Unknown               | 2         | 0.74%   |
| Wortmann AG           | 1         | 0.37%   |
| Toxic                 | 1         | 0.37%   |
| Timi                  | 1         | 0.37%   |
| System76              | 1         | 0.37%   |
| Standard              | 1         | 0.37%   |
| Positivo Bahia - VAIO | 1         | 0.37%   |
| Positivo              | 1         | 0.37%   |
| Panasonic             | 1         | 0.37%   |
| Notebook              | 1         | 0.37%   |
| Metabox               | 1         | 0.37%   |
| Jumper                | 1         | 0.37%   |
| Irbis                 | 1         | 0.37%   |
| Intel Client Systems  | 1         | 0.37%   |
| GPU Company           | 1         | 0.37%   |
| Google                | 1         | 0.37%   |
| eMachines             | 1         | 0.37%   |
| Eluktronics           | 1         | 0.37%   |
| Digma                 | 1         | 0.37%   |
| Clevo                 | 1         | 0.37%   |
| Chuwi                 | 1         | 0.37%   |
| BANGHO                | 1         | 0.37%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                               | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Unknown                                            | 4         | 1.49%   |
| MSI Modern 15 A5M                                  | 3         | 1.12%   |
| Lenovo IdeaPad 3 15IIL05 81WE                      | 3         | 1.12%   |
| HP Notebook                                        | 3         | 1.12%   |
| HP EliteBook 8470p                                 | 3         | 1.12%   |
| Dell Latitude E6420                                | 3         | 1.12%   |
| Dell Inspiron MM061                                | 3         | 1.12%   |
| Quanta TW9/SW9                                     | 2         | 0.74%   |
| HP ProBook 650 G1                                  | 2         | 0.74%   |
| HP Pavilion dv6                                    | 2         | 0.74%   |
| HP Pavilion 15                                     | 2         | 0.74%   |
| Dell Latitude E7440                                | 2         | 0.74%   |
| Dell Latitude E6410                                | 2         | 0.74%   |
| ASUS Q524UQ                                        | 2         | 0.74%   |
| Apple MacBookPro8,1                                | 2         | 0.74%   |
| Apple MacBookAir7,2                                | 2         | 0.74%   |
| Acer Nitro AN515-54                                | 2         | 0.74%   |
| Acer Aspire ES1-111M                               | 2         | 0.74%   |
| Wortmann AG TERRA_MOBILE_1542                      | 1         | 0.37%   |
| Toxic GM7MQ8P                                      | 1         | 0.37%   |
| Toshiba Satellite-L845                             | 1         | 0.37%   |
| Toshiba Satellite L775D                            | 1         | 0.37%   |
| Toshiba Satellite L750                             | 1         | 0.37%   |
| Toshiba Satellite L655                             | 1         | 0.37%   |
| Toshiba Satellite L300D                            | 1         | 0.37%   |
| Toshiba Satellite Click 2 L35W-B                   | 1         | 0.37%   |
| Toshiba Satellite C855D                            | 1         | 0.37%   |
| Toshiba Satellite C75D-B                           | 1         | 0.37%   |
| Timi TM1613                                        | 1         | 0.37%   |
| System76 Gazelle                                   | 1         | 0.37%   |
| Sony VPCSB1C5E                                     | 1         | 0.37%   |
| Sony VPCCB15FG                                     | 1         | 0.37%   |
| Sony SVP1321L1EBI                                  | 1         | 0.37%   |
| Samsung RV415/RV515                                | 1         | 0.37%   |
| Samsung 550P5C/550P7C                              | 1         | 0.37%   |
| Samsung 350V5C/351V5C/3540VC/3440VC                | 1         | 0.37%   |
| Samsung 300E4C/300E5C/300E7C                       | 1         | 0.37%   |
| Razer Blade Stealth                                | 1         | 0.37%   |
| Razer Blade 15 Base Model (Early 2020) - RZ09-0328 | 1         | 0.37%   |
| Positivo Q232A                                     | 1         | 0.37%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 27        | 10.04%  |
| Dell Latitude          | 19        | 7.06%   |
| Dell Inspiron          | 17        | 6.32%   |
| HP Pavilion            | 14        | 5.2%    |
| Lenovo IdeaPad         | 12        | 4.46%   |
| HP Laptop              | 9         | 3.35%   |
| HP EliteBook           | 9         | 3.35%   |
| Acer Aspire            | 9         | 3.35%   |
| Toshiba Satellite      | 7         | 2.6%    |
| HP ProBook             | 5         | 1.86%   |
| ASUS VivoBook          | 4         | 1.49%   |
| ASUS ASUS              | 4         | 1.49%   |
| Acer Nitro             | 4         | 1.49%   |
| Unknown                | 4         | 1.49%   |
| MSI Modern             | 3         | 1.12%   |
| HP Notebook            | 3         | 1.12%   |
| Fujitsu LIFEBOOK       | 3         | 1.12%   |
| Razer Blade            | 2         | 0.74%   |
| Quanta TW9             | 2         | 0.74%   |
| MSI Katana             | 2         | 0.74%   |
| MSI GT60               | 2         | 0.74%   |
| Lenovo Legion          | 2         | 0.74%   |
| HP ZBook               | 2         | 0.74%   |
| HP Victus              | 2         | 0.74%   |
| HP 250                 | 2         | 0.74%   |
| Dell XPS               | 2         | 0.74%   |
| Dell Precision         | 2         | 0.74%   |
| ASUS Zenbook           | 2         | 0.74%   |
| ASUS TUF               | 2         | 0.74%   |
| ASUS Q524UQ            | 2         | 0.74%   |
| Apple MacBookPro8      | 2         | 0.74%   |
| Apple MacBookPro11     | 2         | 0.74%   |
| Apple MacBookAir7      | 2         | 0.74%   |
| Alienware m15          | 2         | 0.74%   |
| Acer Swift             | 2         | 0.74%   |
| Acer Predator          | 2         | 0.74%   |
| Wortmann AG TERRA      | 1         | 0.37%   |
| Toxic GM7MQ8P          | 1         | 0.37%   |
| Toshiba Satellite-L845 | 1         | 0.37%   |
| Timi TM1613            | 1         | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 34        | 12.64%  |
| 2019 | 33        | 12.27%  |
| 2011 | 31        | 11.52%  |
| 2020 | 24        | 8.92%   |
| 2018 | 22        | 8.18%   |
| 2013 | 22        | 8.18%   |
| 2012 | 19        | 7.06%   |
| 2016 | 17        | 6.32%   |
| 2017 | 14        | 5.2%    |
| 2014 | 14        | 5.2%    |
| 2010 | 10        | 3.72%   |
| 2015 | 8         | 2.97%   |
| 2008 | 7         | 2.6%    |
| 2022 | 5         | 1.86%   |
| 2006 | 4         | 1.49%   |
| 2007 | 3         | 1.12%   |
| 2009 | 2         | 0.74%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 269       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 269       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 268       | 99.63%  |
| Yes  | 1         | 0.37%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 71        | 26.3%   |
| 8.01-16.0   | 63        | 23.33%  |
| 16.01-24.0  | 53        | 19.63%  |
| 3.01-4.0    | 50        | 18.52%  |
| 32.01-64.0  | 16        | 5.93%   |
| 1.01-2.0    | 7         | 2.59%   |
| 64.01-256.0 | 4         | 1.48%   |
| 24.01-32.0  | 3         | 1.11%   |
| 2.01-3.0    | 3         | 1.11%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 101       | 35.69%  |
| 2.01-3.0  | 90        | 31.8%   |
| 3.01-4.0  | 46        | 16.25%  |
| 4.01-8.0  | 28        | 9.89%   |
| 0.51-1.0  | 11        | 3.89%   |
| 8.01-16.0 | 6         | 2.12%   |
| 0.01-0.5  | 1         | 0.35%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 184       | 67.65%  |
| 2      | 79        | 29.04%  |
| 3      | 8         | 2.94%   |
| 0      | 1         | 0.37%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 180       | 66.67%  |
| Yes       | 90        | 33.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 217       | 80.37%  |
| No        | 53        | 19.63%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 266       | 98.88%  |
| No        | 3         | 1.12%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 215       | 78.75%  |
| No        | 58        | 21.25%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 80        | 29.52%  |
| France       | 18        | 6.64%   |
| Germany      | 15        | 5.54%   |
| Spain        | 12        | 4.43%   |
| UK           | 11        | 4.06%   |
| Russia       | 11        | 4.06%   |
| Brazil       | 9         | 3.32%   |
| Netherlands  | 8         | 2.95%   |
| Italy        | 7         | 2.58%   |
| Kenya        | 6         | 2.21%   |
| India        | 6         | 2.21%   |
| Canada       | 5         | 1.85%   |
| Australia    | 5         | 1.85%   |
| Sweden       | 4         | 1.48%   |
| Poland       | 4         | 1.48%   |
| Mexico       | 4         | 1.48%   |
| Indonesia    | 4         | 1.48%   |
| South Africa | 3         | 1.11%   |
| Iraq         | 3         | 1.11%   |
| Finland      | 3         | 1.11%   |
| Denmark      | 3         | 1.11%   |
| Czechia      | 3         | 1.11%   |
| Bangladesh   | 3         | 1.11%   |
| Turkey       | 2         | 0.74%   |
| Switzerland  | 2         | 0.74%   |
| Puerto Rico  | 2         | 0.74%   |
| Portugal     | 2         | 0.74%   |
| Nepal        | 2         | 0.74%   |
| Chile        | 2         | 0.74%   |
| Austria      | 2         | 0.74%   |
| Argentina    | 2         | 0.74%   |
| Zimbabwe     | 1         | 0.37%   |
| Sudan        | 1         | 0.37%   |
| Saudi Arabia | 1         | 0.37%   |
| Peru         | 1         | 0.37%   |
| Pakistan     | 1         | 0.37%   |
| Nigeria      | 1         | 0.37%   |
| New Zealand  | 1         | 0.37%   |
| Namibia      | 1         | 0.37%   |
| Myanmar      | 1         | 0.37%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Nairobi           | 5         | 1.75%   |
| Moscow            | 5         | 1.75%   |
| Dallas            | 4         | 1.4%    |
| Amsterdam         | 4         | 1.4%    |
| Seattle           | 3         | 1.05%   |
| Paris             | 3         | 1.05%   |
| Melbourne         | 3         | 1.05%   |
| Lyon              | 3         | 1.05%   |
| London            | 3         | 1.05%   |
| Houston           | 3         | 1.05%   |
| Dhaka             | 3         | 1.05%   |
| Chicago           | 3         | 1.05%   |
| Zurich            | 2         | 0.7%    |
| Warsaw            | 2         | 0.7%    |
| Sydney            | 2         | 0.7%    |
| Stockholm         | 2         | 0.7%    |
| St Petersburg     | 2         | 0.7%    |
| San Juan          | 2         | 0.7%    |
| Ruskin            | 2         | 0.7%    |
| Rome              | 2         | 0.7%    |
| Pretoria          | 2         | 0.7%    |
| Prague            | 2         | 0.7%    |
| New York          | 2         | 0.7%    |
| Mostoles          | 2         | 0.7%    |
| Madrid            | 2         | 0.7%    |
| Helsinki          | 2         | 0.7%    |
| Dublin            | 2         | 0.7%    |
| Dresden           | 2         | 0.7%    |
| Camden            | 2         | 0.7%    |
| Berlin            | 2         | 0.7%    |
| Barcelona         | 2         | 0.7%    |
| Baghdad           | 2         | 0.7%    |
| Zagreb            | 1         | 0.35%   |
| West Jordan       | 1         | 0.35%   |
| Washington        | 1         | 0.35%   |
| Volgograd         | 1         | 0.35%   |
| Visalia           | 1         | 0.35%   |
| Villa Carlos Paz  | 1         | 0.35%   |
| Vila Nova de Gaia | 1         | 0.35%   |
| Vienna            | 1         | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 51        | 62     | 14.96%  |
| WDC                 | 44        | 53     | 12.9%   |
| Toshiba             | 41        | 46     | 12.02%  |
| Unknown             | 27        | 29     | 7.92%   |
| Seagate             | 24        | 24     | 7.04%   |
| Kingston            | 20        | 20     | 5.87%   |
| Sandisk             | 15        | 18     | 4.4%    |
| Hitachi             | 13        | 15     | 3.81%   |
| Crucial             | 12        | 17     | 3.52%   |
| Micron Technology   | 11        | 11     | 3.23%   |
| SK hynix            | 9         | 9      | 2.64%   |
| HGST                | 9         | 12     | 2.64%   |
| Intel               | 8         | 13     | 2.35%   |
| China               | 6         | 6      | 1.76%   |
| Apple               | 6         | 6      | 1.76%   |
| A-DATA Technology   | 6         | 6      | 1.76%   |
| YMTC                | 3         | 3      | 0.88%   |
| LITEON              | 3         | 3      | 0.88%   |
| Team                | 2         | 2      | 0.59%   |
| PNY                 | 2         | 2      | 0.59%   |
| KIOXIA              | 2         | 3      | 0.59%   |
| HUAWEI              | 2         | 2      | 0.59%   |
| BR                  | 2         | 2      | 0.59%   |
| Unknown             | 2         | 2      | 0.59%   |
| W800SH              | 1         | 1      | 0.29%   |
| Transcend           | 1         | 1      | 0.29%   |
| Silicon Motion      | 1         | 1      | 0.29%   |
| S3+                 | 1         | 1      | 0.29%   |
| RZX                 | 1         | 1      | 0.29%   |
| Phison              | 1         | 1      | 0.29%   |
| Patriot             | 1         | 1      | 0.29%   |
| Netac               | 1         | 1      | 0.29%   |
| LITEONIT            | 1         | 1      | 0.29%   |
| Lexar               | 1         | 1      | 0.29%   |
| KingSpec            | 1         | 2      | 0.29%   |
| KingFast            | 1         | 2      | 0.29%   |
| Intenso             | 1         | 2      | 0.29%   |
| HS-SSD-C100         | 1         | 1      | 0.29%   |
| Hikvision           | 1         | 1      | 0.29%   |
| Fujitsu             | 1         | 1      | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Toshiba MQ04ABF100 1TB             | 10        | 2.78%   |
| Toshiba MQ01ABF050 500GB           | 7         | 1.94%   |
| Toshiba MQ01ABD100 1TB             | 6         | 1.67%   |
| Kingston NVMe SSD Drive 512GB      | 5         | 1.39%   |
| Unknown SD/MMC/MS PRO 2GB          | 4         | 1.11%   |
| Unknown MMC Card  32GB             | 4         | 1.11%   |
| Seagate ST1000LM035-1RK172 1TB     | 4         | 1.11%   |
| Samsung SSD 860 EVO 500GB          | 4         | 1.11%   |
| WDC WD10SPZX-75Z10T2 1TB           | 3         | 0.83%   |
| Toshiba MQ01ABD075 752GB           | 3         | 0.83%   |
| Seagate ST2000LM003 HN-M201RAD 2TB | 3         | 0.83%   |
| SanDisk SSD PLUS 1000GB            | 3         | 0.83%   |
| SanDisk NVMe SSD Drive 1TB         | 3         | 0.83%   |
| Samsung SSD 850 EVO 250GB          | 3         | 0.83%   |
| HGST HTS721010A9E630 1TB           | 3         | 0.83%   |
| HGST HTS541010A9E680 1TB           | 3         | 0.83%   |
| YMTC PC005 256GB                   | 2         | 0.56%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD   | 2         | 0.56%   |
| WDC WD5000LPCX-24C6HT0 500GB       | 2         | 0.56%   |
| WDC WD10SPZX-60Z10T0 1TB           | 2         | 0.56%   |
| WDC WD10SPZX-08Z10 1TB             | 2         | 0.56%   |
| Unknown MMC Card  64GB             | 2         | 0.56%   |
| Team TM8PS7512G 512GB SSD          | 2         | 0.56%   |
| Seagate ST9250315AS 250GB          | 2         | 0.56%   |
| Seagate ST500LT012-1DG142 500GB    | 2         | 0.56%   |
| Seagate ST320LT007-9ZV142 320GB    | 2         | 0.56%   |
| SanDisk NVMe SSD Drive 256GB       | 2         | 0.56%   |
| Samsung SSD 980 1TB                | 2         | 0.56%   |
| Samsung SSD 970 EVO Plus 500GB     | 2         | 0.56%   |
| Samsung NVMe SSD Drive 512GB       | 2         | 0.56%   |
| Samsung NVMe SSD Drive 1024GB      | 2         | 0.56%   |
| Samsung HM500JI 500GB              | 2         | 0.56%   |
| Kingston SV300S37A240G 240GB SSD   | 2         | 0.56%   |
| Kingston SV300S37A120G 120GB SSD   | 2         | 0.56%   |
| Kingston SA400S37240G 240GB SSD    | 2         | 0.56%   |
| Intel SSDPEKNU512GZ 512GB          | 2         | 0.56%   |
| Crucial CT500MX500SSD1 500GB       | 2         | 0.56%   |
| Crucial CT1000P1SSD8 1TB           | 2         | 0.56%   |
| Crucial CT1000MX500SSD1 1TB        | 2         | 0.56%   |
| China SATA SSD 120GB               | 2         | 0.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 33        | 37     | 27.27%  |
| WDC                 | 31        | 35     | 25.62%  |
| Seagate             | 24        | 24     | 19.83%  |
| Hitachi             | 13        | 15     | 10.74%  |
| HGST                | 9         | 12     | 7.44%   |
| Samsung Electronics | 5         | 5      | 4.13%   |
| Unknown             | 4         | 5      | 3.31%   |
| Fujitsu             | 1         | 1      | 0.83%   |
| ASMedia             | 1         | 1      | 0.83%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 21        | 24     | 20.39%  |
| Crucial             | 10        | 15     | 9.71%   |
| Kingston            | 9         | 9      | 8.74%   |
| SanDisk             | 8         | 9      | 7.77%   |
| WDC                 | 6         | 7      | 5.83%   |
| China               | 6         | 6      | 5.83%   |
| Apple               | 5         | 5      | 4.85%   |
| Toshiba             | 4         | 5      | 3.88%   |
| Micron Technology   | 4         | 4      | 3.88%   |
| LITEON              | 3         | 3      | 2.91%   |
| Team                | 2         | 2      | 1.94%   |
| PNY                 | 2         | 2      | 1.94%   |
| Intel               | 2         | 2      | 1.94%   |
| BR                  | 2         | 2      | 1.94%   |
| A-DATA Technology   | 2         | 2      | 1.94%   |
| W800SH              | 1         | 1      | 0.97%   |
| Unknown             | 1         | 1      | 0.97%   |
| Transcend           | 1         | 1      | 0.97%   |
| SK hynix            | 1         | 1      | 0.97%   |
| S3+                 | 1         | 1      | 0.97%   |
| RZX                 | 1         | 1      | 0.97%   |
| Patriot             | 1         | 1      | 0.97%   |
| Netac               | 1         | 1      | 0.97%   |
| LITEONIT            | 1         | 1      | 0.97%   |
| KingSpec            | 1         | 2      | 0.97%   |
| KingFast            | 1         | 1      | 0.97%   |
| Intenso             | 1         | 2      | 0.97%   |
| HS-SSD-C100         | 1         | 1      | 0.97%   |
| Corsair             | 1         | 2      | 0.97%   |
| BHT                 | 1         | 1      | 0.97%   |
| ASMT                | 1         | 1      | 0.97%   |
| Unknown             | 1         | 1      | 0.97%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 118       | 135    | 35.98%  |
| SSD     | 95        | 117    | 28.96%  |
| NVMe    | 89        | 110    | 27.13%  |
| MMC     | 21        | 24     | 6.4%    |
| Unknown | 5         | 5      | 1.52%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 193       | 241    | 60.69%  |
| NVMe | 89        | 110    | 27.99%  |
| MMC  | 21        | 24     | 6.6%    |
| SAS  | 15        | 16     | 4.72%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 135       | 167    | 63.68%  |
| 0.51-1.0   | 72        | 79     | 33.96%  |
| 1.01-2.0   | 5         | 6      | 2.36%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 70        | 25.64%  |
| 101-250        | 58        | 21.25%  |
| 501-1000       | 49        | 17.95%  |
| Unknown        | 29        | 10.62%  |
| 1001-2000      | 26        | 9.52%   |
| 51-100         | 16        | 5.86%   |
| 21-50          | 13        | 4.76%   |
| 1-20           | 5         | 1.83%   |
| 2001-3000      | 4         | 1.47%   |
| More than 3000 | 3         | 1.1%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 21-50          | 89        | 31.79%  |
| 51-100         | 50        | 17.86%  |
| 1-20           | 40        | 14.29%  |
| 101-250        | 34        | 12.14%  |
| Unknown        | 29        | 10.36%  |
| 251-500        | 26        | 9.29%   |
| 501-1000       | 9         | 3.21%   |
| More than 3000 | 1         | 0.36%   |
| 1001-2000      | 1         | 0.36%   |
| 0              | 1         | 0.36%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                              | 2         | 2      | 7.14%   |
| Samsung Electronics HM500JI 500GB                   | 2         | 2      | 7.14%   |
| WDC WD3200BPVT-00JJ5T0 320GB                        | 1         | 1      | 3.57%   |
| WDC WD3200BEKT-75PVMT1 320GB                        | 1         | 1      | 3.57%   |
| WDC WD2500BEVT-22A23T0 250GB                        | 1         | 1      | 3.57%   |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 3.57%   |
| Toshiba MK3265GSXF 320GB                            | 1         | 1      | 3.57%   |
| Seagate ST320LM001 HN-M320MBB 320GB                 | 1         | 1      | 3.57%   |
| Seagate ST2000LM007-1R8174 2TB                      | 1         | 1      | 3.57%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1      | 3.57%   |
| SanDisk SD8SBAT256G1122 256GB SSD                   | 1         | 1      | 3.57%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD    | 1         | 1      | 3.57%   |
| Samsung Electronics HM160HI 160GB                   | 1         | 1      | 3.57%   |
| Micron Technology MTFDDAK128MAY-1AH1ZABHA 128GB SSD | 1         | 1      | 3.57%   |
| LITEON CV8-8E128-HP 128GB SSD                       | 1         | 1      | 3.57%   |
| Intel HBRPEKNX0202AHO 32GB                          | 1         | 1      | 3.57%   |
| Hitachi HTS725050A9A360 500GB                       | 1         | 1      | 3.57%   |
| Hitachi HTS725032A9A364 320GB                       | 1         | 1      | 3.57%   |
| Hitachi HTS723216L9SA60 160GB                       | 1         | 1      | 3.57%   |
| Hitachi HTS542512K9SA00 120GB                       | 1         | 1      | 3.57%   |
| HGST HTS725032A7E630 320GB                          | 1         | 1      | 3.57%   |
| HGST HTS721010A9E630 1TB                            | 1         | 1      | 3.57%   |
| Fujitsu MHY2160BH 160GB                             | 1         | 1      | 3.57%   |
| Crucial CT525MX300SSD1 528GB                        | 1         | 1      | 3.57%   |
| A-DATA Technology SX6000LNP 1TB                     | 1         | 1      | 3.57%   |
| A-DATA Technology SU700 120GB SSD                   | 1         | 1      | 3.57%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 4         | 4      | 14.29%  |
| Samsung Electronics | 4         | 4      | 14.29%  |
| Hitachi             | 4         | 4      | 14.29%  |
| WDC                 | 3         | 3      | 10.71%  |
| Seagate             | 3         | 3      | 10.71%  |
| HGST                | 2         | 2      | 7.14%   |
| A-DATA Technology   | 2         | 2      | 7.14%   |
| SanDisk             | 1         | 1      | 3.57%   |
| Micron Technology   | 1         | 1      | 3.57%   |
| LITEON              | 1         | 1      | 3.57%   |
| Intel               | 1         | 1      | 3.57%   |
| Fujitsu             | 1         | 1      | 3.57%   |
| Crucial             | 1         | 1      | 3.57%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 4         | 4      | 20%     |
| Hitachi             | 4         | 4      | 20%     |
| WDC                 | 3         | 3      | 15%     |
| Seagate             | 3         | 3      | 15%     |
| Samsung Electronics | 3         | 3      | 15%     |
| HGST                | 2         | 2      | 10%     |
| Fujitsu             | 1         | 1      | 5%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 20        | 20     | 71.43%  |
| SSD  | 6         | 6      | 21.43%  |
| NVMe | 2         | 2      | 7.14%   |

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
| Works    | 142       | 176    | 47.65%  |
| Detected | 129       | 187    | 43.29%  |
| Malfunc  | 27        | 28     | 9.06%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 201       | 62.23%  |
| Samsung Electronics          | 30        | 9.29%   |
| AMD                          | 27        | 8.36%   |
| SanDisk                      | 16        | 4.95%   |
| Kingston Technology Company  | 11        | 3.41%   |
| SK hynix                     | 8         | 2.48%   |
| Micron Technology            | 7         | 2.17%   |
| Yangtze Memory Technologies  | 3         | 0.93%   |
| Toshiba America Info Systems | 3         | 0.93%   |
| Silicon Motion               | 3         | 0.93%   |
| Nvidia                       | 3         | 0.93%   |
| KIOXIA                       | 3         | 0.93%   |
| ADATA Technology             | 3         | 0.93%   |
| Micron/Crucial Technology    | 2         | 0.62%   |
| Realtek Semiconductor        | 1         | 0.31%   |
| Phison Electronics           | 1         | 0.31%   |
| Apple                        | 1         | 0.31%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 23        | 6.52%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 22        | 6.23%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 22        | 6.23%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 19        | 5.38%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 18        | 5.1%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 15        | 4.25%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 13        | 3.68%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 11        | 3.12%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 10        | 2.83%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 9         | 2.55%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 8         | 2.27%   |
| Micron Non-Volatile memory controller                                                  | 7         | 1.98%   |
| SanDisk WD Blue SN550 NVMe SSD                                                         | 6         | 1.7%    |
| Samsung NVMe SSD Controller 980                                                        | 6         | 1.7%    |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 6         | 1.7%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 6         | 1.7%    |
| Kingston Company Company Non-Volatile memory controller                                | 5         | 1.42%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 5         | 1.42%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 5         | 1.42%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 5         | 1.42%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 5         | 1.42%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                         | 4         | 1.13%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 4         | 1.13%   |
| SanDisk Non-Volatile memory controller                                                 | 4         | 1.13%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 4         | 1.13%   |
| Intel Non-Volatile memory controller                                                   | 4         | 1.13%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 4         | 1.13%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 4         | 1.13%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 4         | 1.13%   |
| Yangtze Memory Non-Volatile memory controller                                          | 3         | 0.85%   |
| SK hynix BC511                                                                         | 3         | 0.85%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 3         | 0.85%   |
| Samsung Electronics SATA controller                                                    | 3         | 0.85%   |
| KIOXIA NVMe SSD Controller BG4                                                         | 3         | 0.85%   |
| Intel Tiger Lake-LP SATA Controller                                                    | 3         | 0.85%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 3         | 0.85%   |
| Intel Alder Lake-P SATA AHCI Controller                                                | 3         | 0.85%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 3         | 0.85%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 3         | 0.85%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 3         | 0.85%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 184       | 55.09%  |
| NVMe | 89        | 26.65%  |
| RAID | 36        | 10.78%  |
| IDE  | 25        | 7.49%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 231       | 85.87%  |
| AMD    | 38        | 14.13%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz       | 10        | 3.72%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 7         | 2.6%    |
| Intel Core i5-3210M CPU @ 2.50GHz       | 6         | 2.23%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 5         | 1.86%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 5         | 1.86%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 4         | 1.49%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 4         | 1.49%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 4         | 1.49%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 4         | 1.49%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 4         | 1.49%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 4         | 1.49%   |
| Intel Core i3-5005U CPU @ 2.00GHz       | 4         | 1.49%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz      | 4         | 1.49%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 3         | 1.12%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 3         | 1.12%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 3         | 1.12%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 3         | 1.12%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 3         | 1.12%   |
| Intel Core i5-2430M CPU @ 2.40GHz       | 3         | 1.12%   |
| Intel Core i3-6006U CPU @ 2.00GHz       | 3         | 1.12%   |
| Intel Core 2 CPU T5600 @ 1.83GHz        | 3         | 1.12%   |
| Intel Celeron J4125 CPU @ 2.00GHz       | 3         | 1.12%   |
| Intel Celeron CPU N3060 @ 1.60GHz       | 3         | 1.12%   |
| Intel 12th Gen Core i5-12500H           | 3         | 1.12%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 3         | 1.12%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 3         | 1.12%   |
| AMD Ryzen 7 5800H with Radeon Graphics  | 3         | 1.12%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 3         | 1.12%   |
| Intel Core i7-8850H CPU @ 2.60GHz       | 2         | 0.74%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 2         | 0.74%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 2         | 0.74%   |
| Intel Core i7-4600U CPU @ 2.10GHz       | 2         | 0.74%   |
| Intel Core i7-4510U CPU @ 2.00GHz       | 2         | 0.74%   |
| Intel Core i7-3630QM CPU @ 2.40GHz      | 2         | 0.74%   |
| Intel Core i7-3610QM CPU @ 2.30GHz      | 2         | 0.74%   |
| Intel Core i7-3520M CPU @ 2.90GHz       | 2         | 0.74%   |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 2         | 0.74%   |
| Intel Core i7-2620M CPU @ 2.70GHz       | 2         | 0.74%   |
| Intel Core i7-10875H CPU @ 2.30GHz      | 2         | 0.74%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 2         | 0.74%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 74        | 27.51%  |
| Intel Core i7           | 69        | 25.65%  |
| Other                   | 26        | 9.67%   |
| Intel Core i3           | 25        | 9.29%   |
| Intel Celeron           | 16        | 5.95%   |
| AMD Ryzen 7             | 11        | 4.09%   |
| Intel Core 2 Duo        | 9         | 3.35%   |
| AMD Ryzen 5             | 7         | 2.6%    |
| AMD A6                  | 6         | 2.23%   |
| Intel Core 2            | 4         | 1.49%   |
| Intel Pentium           | 3         | 1.12%   |
| AMD Ryzen 3             | 3         | 1.12%   |
| AMD E1                  | 3         | 1.12%   |
| Intel Pentium Silver    | 2         | 0.74%   |
| Intel Atom              | 2         | 0.74%   |
| AMD A4                  | 2         | 0.74%   |
| Intel Pentium Dual-Core | 1         | 0.37%   |
| Intel Core 2 Quad       | 1         | 0.37%   |
| Intel Core 2 Extreme    | 1         | 0.37%   |
| AMD E2                  | 1         | 0.37%   |
| AMD E                   | 1         | 0.37%   |
| AMD C-50                | 1         | 0.37%   |
| AMD Athlon X2           | 1         | 0.37%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 143       | 53.16%  |
| 4      | 80        | 29.74%  |
| 6      | 22        | 8.18%   |
| 8      | 14        | 5.2%    |
| 12     | 4         | 1.49%   |
| 14     | 3         | 1.12%   |
| 1      | 3         | 1.12%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 269       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 205       | 76.21%  |
| 1      | 64        | 23.79%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 264       | 98.14%  |
| Unknown        | 5         | 1.86%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 115       | 41.82%  |
| 0x206a7    | 20        | 7.27%   |
| 0x306a9    | 12        | 4.36%   |
| 0x806ec    | 10        | 3.64%   |
| 0x806e9    | 8         | 2.91%   |
| 0xa0652    | 7         | 2.55%   |
| 0x906ea    | 7         | 2.55%   |
| 0x906a3    | 7         | 2.55%   |
| 0x406e3    | 7         | 2.55%   |
| 0x806c1    | 6         | 2.18%   |
| 0x706a8    | 6         | 2.18%   |
| 0x806ea    | 5         | 1.82%   |
| 0x706e5    | 5         | 1.82%   |
| 0x40651    | 5         | 1.82%   |
| 0x6f6      | 4         | 1.45%   |
| 0x306c3    | 4         | 1.45%   |
| 0x1067a    | 4         | 1.45%   |
| 0x806d1    | 3         | 1.09%   |
| 0x306d4    | 3         | 1.09%   |
| 0x08600106 | 3         | 1.09%   |
| 0x07030105 | 3         | 1.09%   |
| 0x906e9    | 2         | 0.73%   |
| 0x806eb    | 2         | 0.73%   |
| 0x6fd      | 2         | 0.73%   |
| 0x406c4    | 2         | 0.73%   |
| 0x08608103 | 2         | 0.73%   |
| 0x08108109 | 2         | 0.73%   |
| 0x06006705 | 2         | 0.73%   |
| 0x03000027 | 2         | 0.73%   |
| 0xa0660    | 1         | 0.36%   |
| 0x906ed    | 1         | 0.36%   |
| 0x806c2    | 1         | 0.36%   |
| 0x706a1    | 1         | 0.36%   |
| 0x506e3    | 1         | 0.36%   |
| 0x506c9    | 1         | 0.36%   |
| 0x40661    | 1         | 0.36%   |
| 0x30678    | 1         | 0.36%   |
| 0x20655    | 1         | 0.36%   |
| 0x106e5    | 1         | 0.36%   |
| 0x0a50000c | 1         | 0.36%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 52        | 19.33%  |
| SandyBridge      | 30        | 11.15%  |
| IvyBridge        | 21        | 7.81%   |
| Haswell          | 20        | 7.43%   |
| Skylake          | 15        | 5.58%   |
| TigerLake        | 12        | 4.46%   |
| Broadwell        | 12        | 4.46%   |
| Penryn           | 10        | 3.72%   |
| CometLake        | 10        | 3.72%   |
| Unknown          | 10        | 3.72%   |
| Silvermont       | 9         | 3.35%   |
| IceLake          | 8         | 2.97%   |
| Goldmont plus    | 8         | 2.97%   |
| Core             | 7         | 2.6%    |
| Alderlake Hybrid | 6         | 2.23%   |
| Zen+             | 5         | 1.86%   |
| Zen 2            | 5         | 1.86%   |
| Westmere         | 5         | 1.86%   |
| Zen 3            | 4         | 1.49%   |
| Excavator        | 4         | 1.49%   |
| Puma             | 3         | 1.12%   |
| Jaguar           | 3         | 1.12%   |
| Piledriver       | 2         | 0.74%   |
| K10 Llano        | 2         | 0.74%   |
| Bobcat           | 2         | 0.74%   |
| Zen              | 1         | 0.37%   |
| Nehalem          | 1         | 0.37%   |
| K8 & K10 hybrid  | 1         | 0.37%   |
| Goldmont         | 1         | 0.37%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 214       | 59.61%  |
| Nvidia | 87        | 24.23%  |
| AMD    | 58        | 16.16%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 27        | 7.4%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 19        | 5.21%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 14        | 3.84%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 13        | 3.56%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 11        | 3.01%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 11        | 3.01%   |
| Intel HD Graphics 5500                                                                   | 10        | 2.74%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 10        | 2.74%   |
| Intel UHD Graphics 620                                                                   | 9         | 2.47%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 9         | 2.47%   |
| Intel HD Graphics 620                                                                    | 8         | 2.19%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 7         | 1.92%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 1.64%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 1.64%   |
| AMD Lucienne                                                                             | 6         | 1.64%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 5         | 1.37%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 5         | 1.37%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 5         | 1.37%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 1.37%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 1.37%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 1.37%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 5         | 1.37%   |
| AMD Renoir                                                                               | 5         | 1.37%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 1.37%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 4         | 1.1%    |
| Nvidia GM108M [GeForce 940MX]                                                            | 4         | 1.1%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 1.1%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1.1%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 1.1%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 1.1%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4         | 1.1%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 3         | 0.82%   |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 0.82%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 0.82%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 3         | 0.82%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 0.82%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 0.82%   |
| Intel HD Graphics 630                                                                    | 3         | 0.82%   |
| Intel HD Graphics 530                                                                    | 3         | 0.82%   |
| AMD RV515/M54 [Mobility Radeon X1400]                                                    | 3         | 0.82%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 130       | 48.33%  |
| Intel + Nvidia | 71        | 26.39%  |
| 1 x AMD        | 38        | 14.13%  |
| Intel + AMD    | 13        | 4.83%   |
| 1 x Nvidia     | 9         | 3.35%   |
| AMD + Nvidia   | 6         | 2.23%   |
| 2 x Nvidia     | 1         | 0.37%   |
| 2 x AMD        | 1         | 0.37%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 241       | 89.59%  |
| Proprietary | 26        | 9.67%   |
| Unknown     | 2         | 0.74%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 212       | 78.23%  |
| 1.01-2.0   | 18        | 6.64%   |
| 0.01-0.5   | 14        | 5.17%   |
| 0.51-1.0   | 13        | 4.8%    |
| 3.01-4.0   | 9         | 3.32%   |
| 5.01-6.0   | 2         | 0.74%   |
| 2.01-3.0   | 2         | 0.74%   |
| 7.01-8.0   | 1         | 0.37%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 67        | 22.33%  |
| LG Display              | 51        | 17%     |
| BOE                     | 49        | 16.33%  |
| Chimei Innolux          | 38        | 12.67%  |
| Samsung Electronics     | 29        | 9.67%   |
| Apple                   | 11        | 3.67%   |
| Chi Mei Optoelectronics | 8         | 2.67%   |
| Sharp                   | 5         | 1.67%   |
| PANDA                   | 4         | 1.33%   |
| Lenovo                  | 4         | 1.33%   |
| Dell                    | 4         | 1.33%   |
| Acer                    | 3         | 1%      |
| Sceptre Tech            | 2         | 0.67%   |
| Hewlett-Packard         | 2         | 0.67%   |
| Eizo                    | 2         | 0.67%   |
| Ancor Communications    | 2         | 0.67%   |
| ___                     | 1         | 0.33%   |
| ViewSonic               | 1         | 0.33%   |
| Unknown (AAA)           | 1         | 0.33%   |
| Unknown                 | 1         | 0.33%   |
| STD                     | 1         | 0.33%   |
| STA                     | 1         | 0.33%   |
| SANYO                   | 1         | 0.33%   |
| Planar                  | 1         | 0.33%   |
| Philips                 | 1         | 0.33%   |
| Panasonic               | 1         | 0.33%   |
| ONN                     | 1         | 0.33%   |
| NEC Computers           | 1         | 0.33%   |
| LG Philips              | 1         | 0.33%   |
| Kogan                   | 1         | 0.33%   |
| InfoVision              | 1         | 0.33%   |
| Goldstar                | 1         | 0.33%   |
| CSO                     | 1         | 0.33%   |
| BenQ                    | 1         | 0.33%   |
| AOC                     | 1         | 0.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 4         | 1.33%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 4         | 1.33%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch | 3         | 1%      |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 3         | 1%      |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch         | 3         | 1%      |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 3         | 1%      |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch       | 3         | 1%      |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch       | 3         | 1%      |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch        | 3         | 1%      |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch       | 3         | 1%      |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch | 2         | 0.67%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch | 2         | 0.67%   |
| LG Display LCD Monitor LGD0390 1600x900 382x215mm 17.3-inch          | 2         | 0.67%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch         | 2         | 0.67%   |
| LG Display LCD Monitor LGD01E9 1920x1080 345x194mm 15.6-inch         | 2         | 0.67%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch     | 2         | 0.67%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 2         | 0.67%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch      | 2         | 0.67%   |
| BOE LCD Monitor BOE08BE 1920x1080 382x215mm 17.3-inch                | 2         | 0.67%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                | 2         | 0.67%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                | 2         | 0.67%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 2         | 0.67%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch        | 2         | 0.67%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch        | 2         | 0.67%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch        | 2         | 0.67%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                 | 2         | 0.67%   |
| ___ LCD TV ___9000 1360x768                                          | 1         | 0.33%   |
| ViewSonic VA2718-FHD VSCD839 1920x1080 598x336mm 27.0-inch           | 1         | 0.33%   |
| Unknown LCD TV 9000 1360x768 1600x900mm 72.3-inch                    | 1         | 0.33%   |
| Unknown (AAA) LCDTV AAA0042 1360x768 890x500mm 40.2-inch             | 1         | 0.33%   |
| STD HDMI TV STD00C7 1680x1050 698x392mm 31.5-inch                    | 1         | 0.33%   |
| STA XR140EA1T STA0450 1366x768 310x174mm 14.0-inch                   | 1         | 0.33%   |
| Sharp LCD Monitor SHP1542 1920x1080 309x174mm 14.0-inch              | 1         | 0.33%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch              | 1         | 0.33%   |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch              | 1         | 0.33%   |
| Sharp LCD Monitor SHP1447 1920x1080 290x170mm 13.2-inch              | 1         | 0.33%   |
| Sharp LCD Monitor SHP143A 3840x2160 346x194mm 15.6-inch              | 1         | 0.33%   |
| Sceptre Tech Sceptre F24 SPT09AB 1920x1080 530x290mm 23.8-inch       | 1         | 0.33%   |
| Sceptre Tech Sceptre B30 SPT0BC2 2560x1080 690x291mm 29.5-inch       | 1         | 0.33%   |
| SANYO LCD SAN0B51 1920x540                                           | 1         | 0.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 122       | 42.96%  |
| 1366x768 (WXGA)    | 99        | 34.86%  |
| 1600x900 (HD+)     | 17        | 5.99%   |
| 1280x800 (WXGA)    | 11        | 3.87%   |
| 1440x900 (WXGA+)   | 7         | 2.46%   |
| 3840x2160 (4K)     | 5         | 1.76%   |
| 1680x1050 (WSXGA+) | 4         | 1.41%   |
| 2880x1800          | 3         | 1.06%   |
| 2560x1600          | 3         | 1.06%   |
| 2560x1440 (QHD)    | 2         | 0.7%    |
| 2160x1440          | 2         | 0.7%    |
| 1920x1200 (WUXGA)  | 2         | 0.7%    |
| 1024x768 (XGA)     | 2         | 0.7%    |
| 2560x1080          | 1         | 0.35%   |
| 1920x540           | 1         | 0.35%   |
| 1920x515           | 1         | 0.35%   |
| 1360x768           | 1         | 0.35%   |
| 1280x1024 (SXGA)   | 1         | 0.35%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 128       | 42.95%  |
| 14      | 41        | 13.76%  |
| 13      | 38        | 12.75%  |
| 17      | 26        | 8.72%   |
| 12      | 12        | 4.03%   |
| 27      | 7         | 2.35%   |
| 24      | 7         | 2.35%   |
| 11      | 7         | 2.35%   |
| 16      | 5         | 1.68%   |
| 31      | 4         | 1.34%   |
| 21      | 4         | 1.34%   |
| 23      | 3         | 1.01%   |
| 22      | 3         | 1.01%   |
| Unknown | 3         | 1.01%   |
| 19      | 2         | 0.67%   |
| 18      | 2         | 0.67%   |
| 72      | 1         | 0.34%   |
| 54      | 1         | 0.34%   |
| 48      | 1         | 0.34%   |
| 40      | 1         | 0.34%   |
| 32      | 1         | 0.34%   |
| 29      | 1         | 0.34%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 192       | 64.65%  |
| 201-300     | 34        | 11.45%  |
| 351-400     | 32        | 10.77%  |
| 501-600     | 17        | 5.72%   |
| 401-500     | 9         | 3.03%   |
| 601-700     | 5         | 1.68%   |
| Unknown     | 3         | 1.01%   |
| 1001-1500   | 2         | 0.67%   |
| 801-900     | 1         | 0.34%   |
| 701-800     | 1         | 0.34%   |
| 1501-2000   | 1         | 0.34%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 236       | 86.45%  |
| 16/10 | 29        | 10.62%  |
| 4/3   | 2         | 0.73%   |
| 3/2   | 2         | 0.73%   |
| 6/5   | 1         | 0.37%   |
| 32/9  | 1         | 0.37%   |
| 3.73  | 1         | 0.37%   |
| 21/9  | 1         | 0.37%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 131       | 43.96%  |
| 81-90          | 66        | 22.15%  |
| 121-130        | 23        | 7.72%   |
| 201-250        | 15        | 5.03%   |
| 71-80          | 13        | 4.36%   |
| 61-70          | 12        | 4.03%   |
| 301-350        | 8         | 2.68%   |
| 51-60          | 7         | 2.35%   |
| 351-500        | 5         | 1.68%   |
| More than 1000 | 3         | 1.01%   |
| 131-140        | 3         | 1.01%   |
| Unknown        | 3         | 1.01%   |
| 251-300        | 2         | 0.67%   |
| 151-200        | 2         | 0.67%   |
| 141-150        | 2         | 0.67%   |
| 111-120        | 2         | 0.67%   |
| 501-1000       | 1         | 0.34%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 129       | 43.58%  |
| 101-120       | 99        | 33.45%  |
| 51-100        | 41        | 13.85%  |
| 161-240       | 15        | 5.07%   |
| More than 240 | 5         | 1.69%   |
| 1-50          | 4         | 1.35%   |
| Unknown       | 3         | 1.01%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 230       | 84.87%  |
| 2     | 34        | 12.55%  |
| 3     | 5         | 1.85%   |
| 0     | 2         | 0.74%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 156       | 34.51%  |
| Realtek Semiconductor                  | 144       | 31.86%  |
| Qualcomm Atheros                       | 55        | 12.17%  |
| Broadcom                               | 24        | 5.31%   |
| MediaTek                               | 10        | 2.21%   |
| Broadcom Limited                       | 9         | 1.99%   |
| TP-Link                                | 7         | 1.55%   |
| Samsung Electronics                    | 7         | 1.55%   |
| Xiaomi                                 | 4         | 0.88%   |
| Qualcomm Atheros Communications        | 4         | 0.88%   |
| Huawei Technologies                    | 4         | 0.88%   |
| Ralink Technology                      | 3         | 0.66%   |
| NetGear                                | 3         | 0.66%   |
| ASUSTek Computer                       | 3         | 0.66%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.44%   |
| Nvidia                                 | 2         | 0.44%   |
| ASIX Electronics                       | 2         | 0.44%   |
| Apple                                  | 2         | 0.44%   |
| ZyXEL Communications                   | 1         | 0.22%   |
| Sagem                                  | 1         | 0.22%   |
| Ralink                                 | 1         | 0.22%   |
| Linksys                                | 1         | 0.22%   |
| Lenovo                                 | 1         | 0.22%   |
| JMicron Technology                     | 1         | 0.22%   |
| Ericsson Business Mobile Networks      | 1         | 0.22%   |
| DisplayLink                            | 1         | 0.22%   |
| D-Link                                 | 1         | 0.22%   |
| Belkin Components                      | 1         | 0.22%   |
| Arduino SA                             | 1         | 0.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 78        | 14.36%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 29        | 5.34%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 17        | 3.13%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 15        | 2.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 10        | 1.84%   |
| Intel Wireless 8265 / 8275                                        | 9         | 1.66%   |
| Intel Wireless 7260                                               | 9         | 1.66%   |
| Intel Wi-Fi 6 AX201                                               | 9         | 1.66%   |
| Intel Wi-Fi 6 AX200                                               | 9         | 1.66%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 8         | 1.47%   |
| Intel Wireless 7265                                               | 8         | 1.47%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 8         | 1.47%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 8         | 1.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 7         | 1.29%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 1.29%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 7         | 1.29%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 7         | 1.29%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 7         | 1.29%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 6         | 1.1%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 6         | 1.1%    |
| Intel Wireless 3165                                               | 6         | 1.1%    |
| Intel Ethernet Connection I218-LM                                 | 6         | 1.1%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 6         | 1.1%    |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 6         | 1.1%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 5         | 0.92%   |
| Realtek 802.11ac NIC                                              | 5         | 0.92%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 5         | 0.92%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 5         | 0.92%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 4         | 0.74%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 0.74%   |
| Qualcomm Atheros AR9271 802.11n                                   | 4         | 0.74%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4         | 0.74%   |
| Intel Wireless 8260                                               | 4         | 0.74%   |
| Intel Wireless 3160                                               | 4         | 0.74%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 4         | 0.74%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4         | 0.74%   |
| Intel Centrino Advanced-N 6235                                    | 4         | 0.74%   |
| Broadcom BCM43142 802.11b/g/n                                     | 4         | 0.74%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.55%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 3         | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 152       | 49.35%  |
| Realtek Semiconductor             | 54        | 17.53%  |
| Qualcomm Atheros                  | 40        | 12.99%  |
| Broadcom                          | 20        | 6.49%   |
| MediaTek                          | 8         | 2.6%    |
| TP-Link                           | 7         | 2.27%   |
| Broadcom Limited                  | 7         | 2.27%   |
| Qualcomm Atheros Communications   | 4         | 1.3%    |
| Ralink Technology                 | 3         | 0.97%   |
| NetGear                           | 3         | 0.97%   |
| ASUSTek Computer                  | 3         | 0.97%   |
| ZyXEL Communications              | 1         | 0.32%   |
| Sagem                             | 1         | 0.32%   |
| Ralink                            | 1         | 0.32%   |
| Linksys                           | 1         | 0.32%   |
| Ericsson Business Mobile Networks | 1         | 0.32%   |
| D-Link                            | 1         | 0.32%   |
| Belkin Components                 | 1         | 0.32%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 15        | 4.87%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 10        | 3.25%   |
| Intel Wireless 8265 / 8275                                     | 9         | 2.92%   |
| Intel Wireless 7260                                            | 9         | 2.92%   |
| Intel Wi-Fi 6 AX201                                            | 9         | 2.92%   |
| Intel Wi-Fi 6 AX200                                            | 9         | 2.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 8         | 2.6%    |
| Intel Wireless 7265                                            | 8         | 2.6%    |
| Intel Comet Lake PCH CNVi WiFi                                 | 8         | 2.6%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 8         | 2.6%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 7         | 2.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 7         | 2.27%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 7         | 2.27%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 7         | 2.27%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 6         | 1.95%   |
| Intel Wireless 3165                                            | 6         | 1.95%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 6         | 1.95%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 6         | 1.95%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 5         | 1.62%   |
| Realtek 802.11ac NIC                                           | 5         | 1.62%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 5         | 1.62%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 4         | 1.3%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 1.3%    |
| Qualcomm Atheros AR9271 802.11n                                | 4         | 1.3%    |
| Intel Wireless 8260                                            | 4         | 1.3%    |
| Intel Wireless 3160                                            | 4         | 1.3%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 4         | 1.3%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 4         | 1.3%    |
| Intel Centrino Advanced-N 6235                                 | 4         | 1.3%    |
| Broadcom BCM43142 802.11b/g/n                                  | 4         | 1.3%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 3         | 0.97%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 3         | 0.97%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 3         | 0.97%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 3         | 0.97%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 3         | 0.97%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 3         | 0.97%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3         | 0.97%   |
| Intel Centrino Wireless-N 2230                                 | 3         | 0.97%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 3         | 0.97%   |
| Intel Centrino Advanced-N 6200                                 | 3         | 0.97%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 124       | 54.63%  |
| Intel                                  | 46        | 20.26%  |
| Qualcomm Atheros                       | 23        | 10.13%  |
| Broadcom                               | 8         | 3.52%   |
| Samsung Electronics                    | 7         | 3.08%   |
| Xiaomi                                 | 4         | 1.76%   |
| Nvidia                                 | 2         | 0.88%   |
| MediaTek                               | 2         | 0.88%   |
| Broadcom Limited                       | 2         | 0.88%   |
| ASIX Electronics                       | 2         | 0.88%   |
| Apple                                  | 2         | 0.88%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.44%   |
| Lenovo                                 | 1         | 0.44%   |
| JMicron Technology                     | 1         | 0.44%   |
| Huawei Technologies                    | 1         | 0.44%   |
| DisplayLink                            | 1         | 0.44%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 78        | 33.91%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 29        | 12.61%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 17        | 7.39%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 3.04%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 6         | 2.61%   |
| Intel Ethernet Connection I218-LM                                 | 6         | 2.61%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 5         | 2.17%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4         | 1.74%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 1.3%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 1.3%    |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 3         | 1.3%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 1.3%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 1.3%    |
| Intel Ethernet Connection (6) I219-V                              | 3         | 1.3%    |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.3%    |
| Broadcom BCM4401-B0 100Base-TX                                    | 3         | 1.3%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.87%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.87%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 0.87%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 2         | 0.87%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.87%   |
| MediaTek File-CD Gadget                                           | 2         | 0.87%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.87%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.87%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.87%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 0.87%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.87%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.43%   |
| Sony Ericsson Mobile AB G8341                                     | 1         | 0.43%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.43%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.43%   |
| Realtek Realtek Ethernet controller                               | 1         | 0.43%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.43%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.43%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.43%   |
| Nvidia MCP89 Ethernet                                             | 1         | 0.43%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.43%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 0.43%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.43%   |
| Intel PRO/100 VE Network Connection                               | 1         | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 267       | 54.71%  |
| Ethernet | 216       | 44.26%  |
| Modem    | 4         | 0.82%   |
| Unknown  | 1         | 0.2%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 219       | 77.11%  |
| Ethernet | 64        | 22.54%  |
| Unknown  | 1         | 0.35%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 193       | 71.75%  |
| 1     | 68        | 25.28%  |
| 0     | 5         | 1.86%   |
| 3     | 3         | 1.12%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Notebooks | Percent |
|---------|-----------|---------|
| No      | 223       | 81.68%  |
| Yes     | 49        | 17.95%  |
| Unknown | 1         | 0.37%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 109       | 50.23%  |
| Realtek Semiconductor           | 22        | 10.14%  |
| Qualcomm Atheros Communications | 22        | 10.14%  |
| Broadcom                        | 15        | 6.91%   |
| IMC Networks                    | 8         | 3.69%   |
| Foxconn / Hon Hai               | 8         | 3.69%   |
| Apple                           | 8         | 3.69%   |
| Lite-On Technology              | 7         | 3.23%   |
| Dell                            | 4         | 1.84%   |
| Cambridge Silicon Radio         | 4         | 1.84%   |
| MediaTek                        | 3         | 1.38%   |
| Toshiba                         | 2         | 0.92%   |
| TP-Link                         | 1         | 0.46%   |
| Realtek                         | 1         | 0.46%   |
| Ralink                          | 1         | 0.46%   |
| Dynex                           | 1         | 0.46%   |
| Alps Electric                   | 1         | 0.46%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 38        | 17.51%  |
| Intel Bluetooth Device                                                              | 28        | 12.9%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 23        | 10.6%   |
| Realtek Bluetooth Radio                                                             | 13        | 5.99%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 9         | 4.15%   |
| Intel AX200 Bluetooth                                                               | 8         | 3.69%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 6         | 2.76%   |
| Apple Bluetooth Host Controller                                                     | 5         | 2.3%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 4         | 1.84%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 4         | 1.84%   |
| Dell DW375 Bluetooth Module                                                         | 4         | 1.84%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 4         | 1.84%   |
| Broadcom HP Portable SoftSailing                                                    | 4         | 1.84%   |
| Qualcomm Atheros Bluetooth                                                          | 3         | 1.38%   |
| MediaTek Wireless_Device                                                            | 3         | 1.38%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 1.38%   |
| IMC Networks Wireless_Device                                                        | 3         | 1.38%   |
| IMC Networks Bluetooth Radio                                                        | 3         | 1.38%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 3         | 1.38%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 3         | 1.38%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 3         | 1.38%   |
| Apple Bluetooth USB Host Controller                                                 | 3         | 1.38%   |
| Realtek RTL8821A Bluetooth                                                          | 2         | 0.92%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 2         | 0.92%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 0.92%   |
| Lite-On Wireless_Device                                                             | 2         | 0.92%   |
| Lite-On Bluetooth Device                                                            | 2         | 0.92%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 0.92%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 2         | 0.92%   |
| IMC Networks Bluetooth Device                                                       | 2         | 0.92%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 0.92%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 2         | 0.92%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 2         | 0.92%   |
| TP-Link TPuLink UB500 Adapter                                                       | 1         | 0.46%   |
| Toshiba Bluetooth USB Host Controller                                               | 1         | 0.46%   |
| Toshiba BCM43142A0                                                                  | 1         | 0.46%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.46%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.46%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.46%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.46%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor    | Notebooks | Percent |
|-----------|-----------|---------|
| Intel     | 225       | 69.44%  |
| Nvidia    | 52        | 16.05%  |
| AMD       | 42        | 12.96%  |
| Lenovo    | 1         | 0.31%   |
| JMTek     | 1         | 0.31%   |
| Guillemot | 1         | 0.31%   |
| GN Netcom | 1         | 0.31%   |
| Apple     | 1         | 0.31%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 30        | 7.71%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 27        | 6.94%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 24        | 6.17%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 20        | 5.14%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 14        | 3.6%    |
| Intel 8 Series HD Audio Controller                                                                | 14        | 3.6%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 13        | 3.34%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 12        | 3.08%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 12        | 3.08%   |
| Intel Broadwell-U Audio Controller                                                                | 12        | 3.08%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 12        | 3.08%   |
| Intel Cannon Lake PCH cAVS                                                                        | 11        | 2.83%   |
| AMD FCH Azalia Controller                                                                         | 10        | 2.57%   |
| Intel Comet Lake PCH cAVS                                                                         | 9         | 2.31%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 8         | 2.06%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 7         | 1.8%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 7         | 1.8%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 7         | 1.8%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 6         | 1.54%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 6         | 1.54%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 6         | 1.54%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 1.54%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 1.54%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 1.54%   |
| AMD Kabini HDMI/DP Audio                                                                          | 6         | 1.54%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 1.29%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 5         | 1.29%   |
| Nvidia Audio device                                                                               | 5         | 1.29%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 1.29%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 5         | 1.29%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 1.03%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 1.03%   |
| AMD High Definition Audio Controller                                                              | 4         | 1.03%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 1.03%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 0.77%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 0.77%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 0.77%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.77%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 0.77%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 0.77%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 61        | 29.05%  |
| Micron Technology   | 38        | 18.1%   |
| SK hynix            | 36        | 17.14%  |
| Crucial             | 15        | 7.14%   |
| Kingston            | 11        | 5.24%   |
| Unknown             | 8         | 3.81%   |
| Ramaxel Technology  | 7         | 3.33%   |
| Elpida              | 7         | 3.33%   |
| Unknown (ABCD)      | 5         | 2.38%   |
| Nanya Technology    | 4         | 1.9%    |
| A-DATA Technology   | 4         | 1.9%    |
| Corsair             | 3         | 1.43%   |
| Team                | 2         | 0.95%   |
| G.Skill             | 2         | 0.95%   |
| Transcend           | 1         | 0.48%   |
| Timetec             | 1         | 0.48%   |
| Teikon              | 1         | 0.48%   |
| Smart               | 1         | 0.48%   |
| Saikano             | 1         | 0.48%   |
| PNY                 | 1         | 0.48%   |
| ChangXin Memory     | 1         | 0.48%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 3.2%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 2.74%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 5         | 2.28%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 1.83%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 4         | 1.83%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 1.37%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 3         | 1.37%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 1.37%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 3         | 1.37%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 1.37%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 1.37%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 3         | 1.37%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 3         | 1.37%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 2         | 0.91%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s             | 2         | 0.91%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.91%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 0.91%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.91%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 2         | 0.91%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.91%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.91%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.91%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.91%   |
| Samsung RAM M4 70T2953CZ3-CE6 1GB SODIMM DDR2 667MT/s            | 2         | 0.91%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 2         | 0.91%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.91%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 2         | 0.91%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 2         | 0.91%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 2         | 0.91%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s           | 2         | 0.91%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                       | 2         | 0.91%   |
| Crucial RAM CT102464BF160B.C16 8192MB SODIMM DDR3 1600MT/s       | 2         | 0.91%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.46%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 1         | 0.46%   |
| Unknown RAM Module 4096MB SODIMM 1066MT/s                        | 1         | 0.46%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.46%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 0.46%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                       | 1         | 0.46%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 1         | 0.46%   |
| Transcend RAM JM1333KSN-4G 4GB SODIMM DDR3 1334MT/s              | 1         | 0.46%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 79        | 44.38%  |
| DDR3    | 67        | 37.64%  |
| LPDDR4  | 13        | 7.3%    |
| LPDDR3  | 7         | 3.93%   |
| DDR2    | 5         | 2.81%   |
| DDR5    | 3         | 1.69%   |
| SDRAM   | 1         | 0.56%   |
| LPDDR5  | 1         | 0.56%   |
| DDR     | 1         | 0.56%   |
| Unknown | 1         | 0.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 159       | 89.33%  |
| Row Of Chips | 17        | 9.55%   |
| Chip         | 1         | 0.56%   |
| Unknown      | 1         | 0.56%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 75        | 39.47%  |
| 4096  | 65        | 34.21%  |
| 16384 | 21        | 11.05%  |
| 2048  | 19        | 10%     |
| 1024  | 8         | 4.21%   |
| 32768 | 2         | 1.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 44        | 22.56%  |
| 1600    | 43        | 22.05%  |
| 3200    | 29        | 14.87%  |
| 2400    | 17        | 8.72%   |
| 1334    | 15        | 7.69%   |
| 2133    | 9         | 4.62%   |
| 1333    | 8         | 4.1%    |
| 1867    | 4         | 2.05%   |
| 4800    | 3         | 1.54%   |
| 3266    | 3         | 1.54%   |
| 1067    | 3         | 1.54%   |
| 1066    | 3         | 1.54%   |
| 667     | 3         | 1.54%   |
| 4267    | 2         | 1.03%   |
| Unknown | 2         | 1.03%   |
| 8400    | 1         | 0.51%   |
| 6400    | 1         | 0.51%   |
| 3733    | 1         | 0.51%   |
| 2048    | 1         | 0.51%   |
| 975     | 1         | 0.51%   |
| 800     | 1         | 0.51%   |
| 533     | 1         | 0.51%   |

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
| Chicony Electronics                    | 66        | 27.62%  |
| IMC Networks                           | 26        | 10.88%  |
| Acer                                   | 25        | 10.46%  |
| Microdia                               | 20        | 8.37%   |
| Sunplus Innovation Technology          | 15        | 6.28%   |
| Realtek Semiconductor                  | 12        | 5.02%   |
| Quanta                                 | 12        | 5.02%   |
| Apple                                  | 9         | 3.77%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 2.93%   |
| Syntek                                 | 6         | 2.51%   |
| Suyin                                  | 5         | 2.09%   |
| Ricoh                                  | 5         | 2.09%   |
| Luxvisions Innotech Limited            | 5         | 2.09%   |
| Samsung Electronics                    | 4         | 1.67%   |
| Sonix Technology                       | 3         | 1.26%   |
| Silicon Motion                         | 3         | 1.26%   |
| Lite-On Technology                     | 3         | 1.26%   |
| Alcor Micro                            | 3         | 1.26%   |
| Importek                               | 2         | 0.84%   |
| icSpring                               | 2         | 0.84%   |
| USB Camera CS                          | 1         | 0.42%   |
| Primax Electronics                     | 1         | 0.42%   |
| Logitech                               | 1         | 0.42%   |
| LG Electronics                         | 1         | 0.42%   |
| Goertek Electronics                    | 1         | 0.42%   |
| ALi                                    | 1         | 0.42%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony integrated camera                            | 9         | 3.77%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 8         | 3.35%   |
| Realtek Integrated_Webcam_HD                         | 7         | 2.93%   |
| IMC Networks Integrated Camera                       | 7         | 2.93%   |
| Acer HD Webcam                                       | 7         | 2.93%   |
| Microdia Integrated_Webcam_HD                        | 6         | 2.51%   |
| Chicony HD Webcam                                    | 6         | 2.51%   |
| Chicony HD User Facing                               | 6         | 2.51%   |
| Syntek Integrated Camera                             | 5         | 2.09%   |
| Chicony USB2.0 Camera                                | 5         | 2.09%   |
| Chicony HP Truevision HD                             | 5         | 2.09%   |
| Sunplus Integrated_Webcam_HD                         | 4         | 1.67%   |
| Samsung Galaxy A5 (MTP)                              | 4         | 1.67%   |
| Acer SunplusIT Integrated Camera                     | 4         | 1.67%   |
| Acer EasyCamera                                      | 4         | 1.67%   |
| Quanta HP TrueVision HD Camera                       | 3         | 1.26%   |
| Quanta HD User Facing                                | 3         | 1.26%   |
| Microdia Webcam Vitade AF                            | 3         | 1.26%   |
| Microdia Integrated Webcam                           | 3         | 1.26%   |
| IMC Networks HD Camera                               | 3         | 1.26%   |
| Chicony USB2.0 HD UVC WebCam                         | 3         | 1.26%   |
| Apple iPhone 5/5C/5S/6/SE                            | 3         | 1.26%   |
| Alcor Micro USB Camera                               | 3         | 1.26%   |
| Acer Integrated Camera                               | 3         | 1.26%   |
| Sunplus Laptop_Integrated_Webcam_FHD                 | 2         | 0.84%   |
| Sunplus HD WebCam                                    | 2         | 0.84%   |
| Sonix USB2.0 HD UVC WebCam                           | 2         | 0.84%   |
| Realtek Integrated Webcam                            | 2         | 0.84%   |
| Microdia PC Microscope camera                        | 2         | 0.84%   |
| Microdia Laptop_Integrated_Webcam_HD                 | 2         | 0.84%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 2         | 0.84%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 2         | 0.84%   |
| Lite-On HP Wide Vision HD Camera                     | 2         | 0.84%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 2         | 0.84%   |
| icSpring camera                                      | 2         | 0.84%   |
| Chicony USB2.0 VGA UVC WebCam                        | 2         | 0.84%   |
| Chicony TOSHIBA Web Camera - HD                      | 2         | 0.84%   |
| Chicony Lenovo Integrated Camera (0.3MP)             | 2         | 0.84%   |
| Chicony Integrated HP HD Webcam                      | 2         | 0.84%   |
| Chicony Integrated Camera [ThinkPad]                 | 2         | 0.84%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 18        | 40%     |
| Synaptics                  | 11        | 24.44%  |
| Shenzhen Goodix Technology | 6         | 13.33%  |
| Elan Microelectronics      | 4         | 8.89%   |
| Upek                       | 2         | 4.44%   |
| LighTuning Technology      | 2         | 4.44%   |
| AuthenTec                  | 2         | 4.44%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 5         | 11.11%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 4         | 8.89%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 6.67%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 6.67%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 6.67%   |
| Validity Sensors VFS491                                                    | 2         | 4.44%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 4.44%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 4.44%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 4.44%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 4.44%   |
| Elan ELAN:Fingerprint                                                      | 2         | 4.44%   |
| Elan ELAN:ARM-M4                                                           | 2         | 4.44%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 2.22%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 2.22%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.22%   |
| Synaptics  WBDI                                                            | 1         | 2.22%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 2.22%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 2.22%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 2.22%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 2.22%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 2.22%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 2.22%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 2.22%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 2.22%   |
| Unknown                                                                    | 1         | 2.22%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 11        | 64.71%  |
| Alcor Micro | 4         | 23.53%  |
| OmniKey     | 1         | 5.88%   |
| O2 Micro    | 1         | 5.88%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 7         | 41.18%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 4         | 23.53%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 17.65%  |
| OmniKey CardMan Smart@Link                                                   | 1         | 5.88%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 5.88%   |
| Broadcom 5880                                                                | 1         | 5.88%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 164       | 60.07%  |
| 1     | 87        | 31.87%  |
| 2     | 20        | 7.33%   |
| 3     | 2         | 0.73%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 46        | 35.94%  |
| Graphics card         | 20        | 15.63%  |
| Chipcard              | 16        | 12.5%   |
| Net/wireless          | 14        | 10.94%  |
| Multimedia controller | 13        | 10.16%  |
| Camera                | 7         | 5.47%   |
| Storage               | 6         | 4.69%   |
| Network               | 3         | 2.34%   |
| Modem                 | 1         | 0.78%   |
| Card reader           | 1         | 0.78%   |
| Bluetooth             | 1         | 0.78%   |

