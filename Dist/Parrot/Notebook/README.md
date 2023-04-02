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

Total: 401

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Google        | Lillipup                    | [09292890c9](https://linux-hardware.org/?probe=09292890c9) | Mar 30, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [0180776452](https://linux-hardware.org/?probe=0180776452) | Mar 26, 2023 |
| ASUSTek       | X510UAR                     | [728805785d](https://linux-hardware.org/?probe=728805785d) | Mar 25, 2023 |
| HP            | ZBook Firefly 14 inch G9... | [35030027f5](https://linux-hardware.org/?probe=35030027f5) | Mar 21, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | [0927eb4ba9](https://linux-hardware.org/?probe=0927eb4ba9) | Mar 17, 2023 |
| MSI           | Katana GF66 12UC            | [8307fbf791](https://linux-hardware.org/?probe=8307fbf791) | Mar 14, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | [b5d8bdc57d](https://linux-hardware.org/?probe=b5d8bdc57d) | Mar 12, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | [4525fa2931](https://linux-hardware.org/?probe=4525fa2931) | Mar 12, 2023 |
| HP            | ZBook Firefly 15.6 inch ... | [47f7858a60](https://linux-hardware.org/?probe=47f7858a60) | Mar 07, 2023 |
| Acer          | Aspire E5-575               | [143b06f2d6](https://linux-hardware.org/?probe=143b06f2d6) | Mar 06, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [fe287f85c8](https://linux-hardware.org/?probe=fe287f85c8) | Mar 05, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [d3bb7ff642](https://linux-hardware.org/?probe=d3bb7ff642) | Mar 05, 2023 |
| HP            | Pavilion 15                 | [3a06e7e211](https://linux-hardware.org/?probe=3a06e7e211) | Mar 05, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [85bc55a850](https://linux-hardware.org/?probe=85bc55a850) | Feb 26, 2023 |
| Lenovo        | ThinkPad X230 23253Z5       | [1237b75ae4](https://linux-hardware.org/?probe=1237b75ae4) | Feb 24, 2023 |
| Dell          | Inspiron 3421               | [fd899aea79](https://linux-hardware.org/?probe=fd899aea79) | Feb 22, 2023 |
| Alienware     | 17 R5                       | [1d234f85b4](https://linux-hardware.org/?probe=1d234f85b4) | Feb 22, 2023 |
| Alienware     | 17 R5                       | [5b6b8eee92](https://linux-hardware.org/?probe=5b6b8eee92) | Feb 22, 2023 |
| Google        | Robo360                     | [e7c85b2410](https://linux-hardware.org/?probe=e7c85b2410) | Feb 09, 2023 |
| Apple         | MacBookPro9,2               | [725e7248ee](https://linux-hardware.org/?probe=725e7248ee) | Feb 04, 2023 |
| Acer          | Swift SFX14-51G             | [9f67df0760](https://linux-hardware.org/?probe=9f67df0760) | Feb 03, 2023 |
| Lenovo        | ThinkPad T460 20FMS2J300    | [741b347456](https://linux-hardware.org/?probe=741b347456) | Feb 02, 2023 |
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
| Parrot 5.0   | 82        | 27.33%  |
| Parrot 4.11  | 66        | 22%     |
| Parrot 5.1   | 50        | 16.67%  |
| Parrot 4.10  | 45        | 15%     |
| Parrot 4.8   | 15        | 5%      |
| Parrot 5.2   | 13        | 4.33%   |
| Parrot 4.9   | 13        | 4.33%   |
| Parrot 4.7   | 10        | 3.33%   |
| Parrot 4.6   | 2         | 0.67%   |
| Parrot 4.5   | 1         | 0.33%   |
| Parrot 4.4   | 1         | 0.33%   |
| Parrot 4.2.2 | 1         | 0.33%   |
| Parrot 3.10  | 1         | 0.33%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Parrot | 285       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.14.0-9parrot1-amd64    | 37        | 12.13%  |
| 5.16.0-12parrot1-amd64   | 35        | 11.48%  |
| 5.7.0-2parrot2-amd64     | 26        | 8.52%   |
| 5.18.0-14parrot1-amd64   | 26        | 8.52%   |
| 5.10.0-6parrot1-amd64    | 25        | 8.2%    |
| 6.0.0-2parrot1-amd64     | 21        | 6.89%   |
| 6.0.0-12parrot1-amd64    | 17        | 5.57%   |
| 5.18.0-1parrot1-amd64    | 14        | 4.59%   |
| 5.10.0-8parrot1-amd64    | 14        | 4.59%   |
| 5.5.0-1parrot1-amd64     | 12        | 3.93%   |
| 5.4.0-4parrot1-amd64     | 11        | 3.61%   |
| 5.6.0-2parrot1-amd64     | 9         | 2.95%   |
| 5.14.0-2parrot1-amd64    | 9         | 2.95%   |
| 5.9.0-2parrot1-amd64     | 7         | 2.3%    |
| 5.15.0-15parrot1-amd64   | 5         | 1.64%   |
| 5.8.0-2parrot1-amd64     | 3         | 0.98%   |
| 5.4.0-2parrot1-amd64     | 3         | 0.98%   |
| 5.2.0-2parrot1-amd64     | 3         | 0.98%   |
| 5.10.0-5parrot1-amd64    | 3         | 0.98%   |
| 5.10.0-3parrot1-amd64    | 3         | 0.98%   |
| 4.19.0-parrot4-28t-amd64 | 3         | 0.98%   |
| 5.8.0-1parrot1-amd64     | 2         | 0.66%   |
| 5.4.0-3parrot1-amd64     | 2         | 0.66%   |
| 4.18.0-parrot10-amd64    | 2         | 0.66%   |
| 5.7.0-rc6-galliumos      | 1         | 0.33%   |
| 5.4.0-2parrot1-686-pae   | 1         | 0.33%   |
| 5.4.0-1parrot1-amd64     | 1         | 0.33%   |
| 5.3.0-3parrot3-amd64     | 1         | 0.33%   |
| 5.3.0-3parrot3-686-pae   | 1         | 0.33%   |
| 5.3.0-1parrot1-amd64     | 1         | 0.33%   |
| 5.15.0-5parrot1-amd64    | 1         | 0.33%   |
| 5.10.0-kali6-amd64       | 1         | 0.33%   |
| 5.10.0-6parrot1-rt-amd64 | 1         | 0.33%   |
| 5.1.0-parrot1-3t-amd64   | 1         | 0.33%   |
| 4.19.0-parrot1-13t-amd64 | 1         | 0.33%   |
| 4.14.0-parrot7-amd64     | 1         | 0.33%   |
| Unknown                  | 1         | 0.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 47        | 15.51%  |
| 5.14.0  | 45        | 14.85%  |
| 5.18.0  | 39        | 12.87%  |
| 6.0.0   | 38        | 12.54%  |
| 5.16.0  | 35        | 11.55%  |
| 5.7.0   | 27        | 8.91%   |
| 5.4.0   | 18        | 5.94%   |
| 5.5.0   | 12        | 3.96%   |
| 5.6.0   | 9         | 2.97%   |
| 5.9.0   | 7         | 2.31%   |
| 5.15.0  | 6         | 1.98%   |
| 5.8.0   | 5         | 1.65%   |
| 4.19.0  | 4         | 1.32%   |
| 5.3.0   | 3         | 0.99%   |
| 5.2.0   | 3         | 0.99%   |
| 4.18.0  | 2         | 0.66%   |
| 5.1.0   | 1         | 0.33%   |
| 4.14.0  | 1         | 0.33%   |
| Unknown | 1         | 0.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 47        | 15.51%  |
| 5.14    | 45        | 14.85%  |
| 5.18    | 39        | 12.87%  |
| 6.0     | 38        | 12.54%  |
| 5.16    | 35        | 11.55%  |
| 5.7     | 27        | 8.91%   |
| 5.4     | 18        | 5.94%   |
| 5.5     | 12        | 3.96%   |
| 5.6     | 9         | 2.97%   |
| 5.9     | 7         | 2.31%   |
| 5.15    | 6         | 1.98%   |
| 5.8     | 5         | 1.65%   |
| 4.19    | 4         | 1.32%   |
| 5.3     | 3         | 0.99%   |
| 5.2     | 3         | 0.99%   |
| 4.18    | 2         | 0.66%   |
| 5.1     | 1         | 0.33%   |
| 4.14    | 1         | 0.33%   |
| Unknown | 1         | 0.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 284       | 99.65%  |
| i686   | 1         | 0.35%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| MATE          | 201       | 69.31%  |
| KDE5          | 51        | 17.59%  |
| Unknown       | 18        | 6.21%   |
| KDE           | 13        | 4.48%   |
| XFCE          | 5         | 1.72%   |
| LXDE          | 1         | 0.34%   |
| GNOME Classic | 1         | 0.34%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 281       | 98.6%   |
| Tty     | 2         | 0.7%    |
| Wayland | 1         | 0.35%   |
| Unknown | 1         | 0.35%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 138       | 47.26%  |
| Unknown | 95        | 32.53%  |
| TDM     | 50        | 17.12%  |
| GDM     | 5         | 1.71%   |
| SDDM    | 4         | 1.37%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 151       | 52.8%   |
| en_GB   | 24        | 8.39%   |
| fr_FR   | 16        | 5.59%   |
| Unknown | 14        | 4.9%    |
| es_ES   | 10        | 3.5%    |
| ru_RU   | 9         | 3.15%   |
| pl_PL   | 8         | 2.8%    |
| pt_BR   | 7         | 2.45%   |
| de_DE   | 7         | 2.45%   |
| en_IN   | 6         | 2.1%    |
| en_AU   | 6         | 2.1%    |
| it_IT   | 5         | 1.75%   |
| es_MX   | 2         | 0.7%    |
| es_AR   | 2         | 0.7%    |
| en_CA   | 2         | 0.7%    |
| tr_TR   | 1         | 0.35%   |
| pt_PT   | 1         | 0.35%   |
| nl_BE   | 1         | 0.35%   |
| id_ID   | 1         | 0.35%   |
| fr_CA   | 1         | 0.35%   |
| fi_FI   | 1         | 0.35%   |
| es_PE   | 1         | 0.35%   |
| es_CO   | 1         | 0.35%   |
| es_CL   | 1         | 0.35%   |
| en_ZW   | 1         | 0.35%   |
| en_ZA   | 1         | 0.35%   |
| en_NZ   | 1         | 0.35%   |
| en_NG   | 1         | 0.35%   |
| en_DK   | 1         | 0.35%   |
| cs_CZ   | 1         | 0.35%   |
| C       | 1         | 0.35%   |
| arn_CL  | 1         | 0.35%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 163       | 56.4%   |
| EFI  | 126       | 43.6%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Btrfs   | 224       | 77.51%  |
| Ext4    | 42        | 14.53%  |
| Xfs     | 9         | 3.11%   |
| Overlay | 7         | 2.42%   |
| Unknown | 7         | 2.42%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 125       | 43.1%   |
| Unknown | 110       | 37.93%  |
| MBR     | 55        | 18.97%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 254       | 87.89%  |
| Yes       | 35        | 12.11%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 189       | 65.63%  |
| Yes       | 99        | 34.38%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo                | 57        | 20%     |
| Hewlett-Packard       | 55        | 19.3%   |
| Dell                  | 45        | 15.79%  |
| ASUSTek Computer      | 27        | 9.47%   |
| Acer                  | 20        | 7.02%   |
| MSI                   | 13        | 4.56%   |
| Apple                 | 11        | 3.86%   |
| Toshiba               | 8         | 2.81%   |
| HUAWEI                | 5         | 1.75%   |
| Samsung Electronics   | 4         | 1.4%    |
| Alienware             | 4         | 1.4%    |
| Sony                  | 3         | 1.05%   |
| Fujitsu               | 3         | 1.05%   |
| Razer                 | 2         | 0.7%    |
| Quanta                | 2         | 0.7%    |
| Google                | 2         | 0.7%    |
| Gateway               | 2         | 0.7%    |
| Unknown               | 2         | 0.7%    |
| Wortmann AG           | 1         | 0.35%   |
| Toxic                 | 1         | 0.35%   |
| Timi                  | 1         | 0.35%   |
| System76              | 1         | 0.35%   |
| Standard              | 1         | 0.35%   |
| Positivo Bahia - VAIO | 1         | 0.35%   |
| Positivo              | 1         | 0.35%   |
| Panasonic             | 1         | 0.35%   |
| Notebook              | 1         | 0.35%   |
| Metabox               | 1         | 0.35%   |
| Jumper                | 1         | 0.35%   |
| Irbis                 | 1         | 0.35%   |
| Intel Client Systems  | 1         | 0.35%   |
| GPU Company           | 1         | 0.35%   |
| eMachines             | 1         | 0.35%   |
| Eluktronics           | 1         | 0.35%   |
| Digma                 | 1         | 0.35%   |
| Clevo                 | 1         | 0.35%   |
| Chuwi                 | 1         | 0.35%   |
| BANGHO                | 1         | 0.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                               | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Unknown                                            | 4         | 1.4%    |
| MSI Modern 15 A5M                                  | 3         | 1.05%   |
| Lenovo IdeaPad 3 15IIL05 81WE                      | 3         | 1.05%   |
| HP Pavilion 15                                     | 3         | 1.05%   |
| HP Notebook                                        | 3         | 1.05%   |
| HP EliteBook 8470p                                 | 3         | 1.05%   |
| Dell Latitude E6420                                | 3         | 1.05%   |
| Dell Inspiron MM061                                | 3         | 1.05%   |
| Quanta TW9/SW9                                     | 2         | 0.7%    |
| MSI Katana GF66 12UC                               | 2         | 0.7%    |
| HP ProBook 650 G1                                  | 2         | 0.7%    |
| HP Pavilion dv6                                    | 2         | 0.7%    |
| Dell Latitude E7440                                | 2         | 0.7%    |
| Dell Latitude E6410                                | 2         | 0.7%    |
| ASUS Q524UQ                                        | 2         | 0.7%    |
| Apple MacBookPro8,1                                | 2         | 0.7%    |
| Apple MacBookAir7,2                                | 2         | 0.7%    |
| Acer Nitro AN515-54                                | 2         | 0.7%    |
| Acer Aspire ES1-111M                               | 2         | 0.7%    |
| Wortmann AG TERRA_MOBILE_1542                      | 1         | 0.35%   |
| Toxic GM7MQ8P                                      | 1         | 0.35%   |
| Toshiba Satellite-L845                             | 1         | 0.35%   |
| Toshiba Satellite L775D                            | 1         | 0.35%   |
| Toshiba Satellite L750                             | 1         | 0.35%   |
| Toshiba Satellite L655                             | 1         | 0.35%   |
| Toshiba Satellite L300D                            | 1         | 0.35%   |
| Toshiba Satellite Click 2 L35W-B                   | 1         | 0.35%   |
| Toshiba Satellite C855D                            | 1         | 0.35%   |
| Toshiba Satellite C75D-B                           | 1         | 0.35%   |
| Timi TM1613                                        | 1         | 0.35%   |
| System76 Gazelle                                   | 1         | 0.35%   |
| Sony VPCSB1C5E                                     | 1         | 0.35%   |
| Sony VPCCB15FG                                     | 1         | 0.35%   |
| Sony SVP1321L1EBI                                  | 1         | 0.35%   |
| Samsung RV415/RV515                                | 1         | 0.35%   |
| Samsung 550P5C/550P7C                              | 1         | 0.35%   |
| Samsung 350V5C/351V5C/3540VC/3440VC                | 1         | 0.35%   |
| Samsung 300E4C/300E5C/300E7C                       | 1         | 0.35%   |
| Razer Blade Stealth                                | 1         | 0.35%   |
| Razer Blade 15 Base Model (Early 2020) - RZ09-0328 | 1         | 0.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 31        | 10.88%  |
| Dell Latitude          | 19        | 6.67%   |
| Dell Inspiron          | 18        | 6.32%   |
| HP Pavilion            | 15        | 5.26%   |
| Lenovo IdeaPad         | 13        | 4.56%   |
| Acer Aspire            | 10        | 3.51%   |
| HP Laptop              | 9         | 3.16%   |
| HP EliteBook           | 9         | 3.16%   |
| Toshiba Satellite      | 7         | 2.46%   |
| HP ProBook             | 5         | 1.75%   |
| HP ZBook               | 4         | 1.4%    |
| ASUS VivoBook          | 4         | 1.4%    |
| ASUS ASUS              | 4         | 1.4%    |
| Acer Nitro             | 4         | 1.4%    |
| Unknown                | 4         | 1.4%    |
| MSI Modern             | 3         | 1.05%   |
| MSI Katana             | 3         | 1.05%   |
| HP Notebook            | 3         | 1.05%   |
| Fujitsu LIFEBOOK       | 3         | 1.05%   |
| Acer Swift             | 3         | 1.05%   |
| Razer Blade            | 2         | 0.7%    |
| Quanta TW9             | 2         | 0.7%    |
| MSI GT60               | 2         | 0.7%    |
| Lenovo Legion          | 2         | 0.7%    |
| HP Victus              | 2         | 0.7%    |
| HP 250                 | 2         | 0.7%    |
| Dell XPS               | 2         | 0.7%    |
| Dell Precision         | 2         | 0.7%    |
| ASUS Zenbook           | 2         | 0.7%    |
| ASUS TUF               | 2         | 0.7%    |
| ASUS Q524UQ            | 2         | 0.7%    |
| Apple MacBookPro8      | 2         | 0.7%    |
| Apple MacBookPro11     | 2         | 0.7%    |
| Apple MacBookAir7      | 2         | 0.7%    |
| Alienware m15          | 2         | 0.7%    |
| Acer Predator          | 2         | 0.7%    |
| Wortmann AG TERRA      | 1         | 0.35%   |
| Toxic GM7MQ8P          | 1         | 0.35%   |
| Toshiba Satellite-L845 | 1         | 0.35%   |
| Timi TM1613            | 1         | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 35        | 12.28%  |
| 2019 | 33        | 11.58%  |
| 2011 | 31        | 10.88%  |
| 2020 | 25        | 8.77%   |
| 2018 | 23        | 8.07%   |
| 2013 | 23        | 8.07%   |
| 2012 | 22        | 7.72%   |
| 2016 | 19        | 6.67%   |
| 2017 | 15        | 5.26%   |
| 2014 | 14        | 4.91%   |
| 2022 | 10        | 3.51%   |
| 2010 | 10        | 3.51%   |
| 2015 | 8         | 2.81%   |
| 2008 | 7         | 2.46%   |
| 2006 | 4         | 1.4%    |
| 2007 | 3         | 1.05%   |
| 2009 | 2         | 0.7%    |
| 2023 | 1         | 0.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 285       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 285       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 283       | 99.3%   |
| Yes  | 2         | 0.7%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 74        | 25.78%  |
| 8.01-16.0   | 65        | 22.65%  |
| 16.01-24.0  | 58        | 20.21%  |
| 3.01-4.0    | 53        | 18.47%  |
| 32.01-64.0  | 20        | 6.97%   |
| 1.01-2.0    | 7         | 2.44%   |
| 64.01-256.0 | 4         | 1.39%   |
| 24.01-32.0  | 3         | 1.05%   |
| 2.01-3.0    | 3         | 1.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 104       | 34.67%  |
| 2.01-3.0  | 99        | 33%     |
| 3.01-4.0  | 47        | 15.67%  |
| 4.01-8.0  | 31        | 10.33%  |
| 0.51-1.0  | 11        | 3.67%   |
| 8.01-16.0 | 7         | 2.33%   |
| 0.01-0.5  | 1         | 0.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 196       | 68.06%  |
| 2      | 83        | 28.82%  |
| 3      | 8         | 2.78%   |
| 0      | 1         | 0.35%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 193       | 67.48%  |
| Yes       | 93        | 32.52%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 230       | 80.42%  |
| No        | 56        | 19.58%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 282       | 98.95%  |
| No        | 3         | 1.05%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 230       | 79.58%  |
| No        | 59        | 20.42%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 90        | 31.36%  |
| France       | 18        | 6.27%   |
| Germany      | 15        | 5.23%   |
| Spain        | 13        | 4.53%   |
| UK           | 11        | 3.83%   |
| Russia       | 11        | 3.83%   |
| Brazil       | 10        | 3.48%   |
| Netherlands  | 8         | 2.79%   |
| Italy        | 7         | 2.44%   |
| India        | 7         | 2.44%   |
| Kenya        | 6         | 2.09%   |
| Australia    | 6         | 2.09%   |
| Canada       | 5         | 1.74%   |
| Sweden       | 4         | 1.39%   |
| Poland       | 4         | 1.39%   |
| Mexico       | 4         | 1.39%   |
| Indonesia    | 4         | 1.39%   |
| South Africa | 3         | 1.05%   |
| Iraq         | 3         | 1.05%   |
| Finland      | 3         | 1.05%   |
| Denmark      | 3         | 1.05%   |
| Czechia      | 3         | 1.05%   |
| Bangladesh   | 3         | 1.05%   |
| Turkey       | 2         | 0.7%    |
| Switzerland  | 2         | 0.7%    |
| Puerto Rico  | 2         | 0.7%    |
| Portugal     | 2         | 0.7%    |
| Nepal        | 2         | 0.7%    |
| Namibia      | 2         | 0.7%    |
| Mongolia     | 2         | 0.7%    |
| Chile        | 2         | 0.7%    |
| Austria      | 2         | 0.7%    |
| Argentina    | 2         | 0.7%    |
| Zimbabwe     | 1         | 0.35%   |
| Sudan        | 1         | 0.35%   |
| Saudi Arabia | 1         | 0.35%   |
| Peru         | 1         | 0.35%   |
| Pakistan     | 1         | 0.35%   |
| Nigeria      | 1         | 0.35%   |
| New Zealand  | 1         | 0.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| Nairobi       | 5         | 1.66%   |
| Moscow        | 5         | 1.66%   |
| Houston       | 4         | 1.32%   |
| Dallas        | 4         | 1.32%   |
| Amsterdam     | 4         | 1.32%   |
| Sydney        | 3         | 0.99%   |
| Seattle       | 3         | 0.99%   |
| Paris         | 3         | 0.99%   |
| Melbourne     | 3         | 0.99%   |
| Lyon          | 3         | 0.99%   |
| London        | 3         | 0.99%   |
| Dhaka         | 3         | 0.99%   |
| Chicago       | 3         | 0.99%   |
| Zurich        | 2         | 0.66%   |
| Warsaw        | 2         | 0.66%   |
| Visalia       | 2         | 0.66%   |
| Ulan Bator    | 2         | 0.66%   |
| Stockholm     | 2         | 0.66%   |
| St Petersburg | 2         | 0.66%   |
| San Juan      | 2         | 0.66%   |
| Ruskin        | 2         | 0.66%   |
| Rome          | 2         | 0.66%   |
| Reading       | 2         | 0.66%   |
| Pretoria      | 2         | 0.66%   |
| Prague        | 2         | 0.66%   |
| New York      | 2         | 0.66%   |
| Mostoles      | 2         | 0.66%   |
| Madrid        | 2         | 0.66%   |
| Los Angeles   | 2         | 0.66%   |
| Helsinki      | 2         | 0.66%   |
| Greenville    | 2         | 0.66%   |
| Dublin        | 2         | 0.66%   |
| Dresden       | 2         | 0.66%   |
| Camden        | 2         | 0.66%   |
| Berlin        | 2         | 0.66%   |
| Barcelona     | 2         | 0.66%   |
| Baghdad       | 2         | 0.66%   |
| Zagreb        | 1         | 0.33%   |
| Windhoek      | 1         | 0.33%   |
| West Jordan   | 1         | 0.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 55        | 68     | 15.24%  |
| WDC                 | 45        | 54     | 12.47%  |
| Toshiba             | 42        | 47     | 11.63%  |
| Unknown             | 28        | 30     | 7.76%   |
| Seagate             | 25        | 25     | 6.93%   |
| Kingston            | 23        | 23     | 6.37%   |
| Sandisk             | 15        | 19     | 4.16%   |
| Hitachi             | 13        | 15     | 3.6%    |
| Micron Technology   | 12        | 12     | 3.32%   |
| Crucial             | 12        | 17     | 3.32%   |
| HGST                | 11        | 14     | 3.05%   |
| SK hynix            | 9         | 10     | 2.49%   |
| Intel               | 8         | 13     | 2.22%   |
| China               | 6         | 6      | 1.66%   |
| Apple               | 6         | 6      | 1.66%   |
| A-DATA Technology   | 6         | 6      | 1.66%   |
| KIOXIA              | 4         | 5      | 1.11%   |
| YMTC                | 3         | 3      | 0.83%   |
| LITEON              | 3         | 3      | 0.83%   |
| Unknown             | 3         | 3      | 0.83%   |
| Team                | 2         | 2      | 0.55%   |
| PNY                 | 2         | 2      | 0.55%   |
| Phison              | 2         | 2      | 0.55%   |
| HUAWEI              | 2         | 2      | 0.55%   |
| BR                  | 2         | 2      | 0.55%   |
| W800SH              | 1         | 1      | 0.28%   |
| Unknown (583)       | 1         | 1      | 0.28%   |
| Transcend           | 1         | 1      | 0.28%   |
| Silicon Motion      | 1         | 1      | 0.28%   |
| S3+                 | 1         | 1      | 0.28%   |
| RZX                 | 1         | 1      | 0.28%   |
| Patriot             | 1         | 1      | 0.28%   |
| Netac               | 1         | 1      | 0.28%   |
| LITEONIT            | 1         | 1      | 0.28%   |
| Lexar               | 1         | 1      | 0.28%   |
| KingSpec            | 1         | 2      | 0.28%   |
| KingFast            | 1         | 2      | 0.28%   |
| Intenso             | 1         | 2      | 0.28%   |
| HS-SSD-C100         | 1         | 1      | 0.28%   |
| Hikvision           | 1         | 1      | 0.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Toshiba MQ04ABF100 1TB              | 10        | 2.62%   |
| Toshiba MQ01ABF050 500GB            | 7         | 1.84%   |
| Toshiba MQ01ABD100 1TB              | 7         | 1.84%   |
| Kingston NVMe SSD Drive 512GB       | 5         | 1.31%   |
| Unknown SD/MMC/MS PRO 64GB          | 4         | 1.05%   |
| Unknown MMC Card  32GB              | 4         | 1.05%   |
| Seagate ST1000LM035-1RK172 1TB      | 4         | 1.05%   |
| Samsung SSD 860 EVO 500GB           | 4         | 1.05%   |
| HGST HTS721010A9E630 1TB            | 4         | 1.05%   |
| HGST HTS541010A9E680 1TB            | 4         | 1.05%   |
| WDC WD10SPZX-75Z10T2 1TB            | 3         | 0.79%   |
| Toshiba MQ01ABD075 752GB            | 3         | 0.79%   |
| Seagate ST2000LM003 HN-M201RAD 2TB  | 3         | 0.79%   |
| SanDisk SSD PLUS 1000GB             | 3         | 0.79%   |
| SanDisk NVMe SSD Drive 1TB          | 3         | 0.79%   |
| Samsung SSD 850 EVO 250GB           | 3         | 0.79%   |
| Unknown                             | 3         | 0.79%   |
| YMTC PC005 256GB                    | 2         | 0.52%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD    | 2         | 0.52%   |
| WDC WD5000LPCX-24C6HT0 500GB        | 2         | 0.52%   |
| WDC WD10SPZX-60Z10T0 1TB            | 2         | 0.52%   |
| WDC WD10SPZX-08Z10 1TB              | 2         | 0.52%   |
| Unknown MMC Card  64GB              | 2         | 0.52%   |
| Team TM8PS7512G 512GB SSD           | 2         | 0.52%   |
| Seagate ST9250315AS 250GB           | 2         | 0.52%   |
| Seagate ST500LT012-1DG142 500GB     | 2         | 0.52%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 2         | 0.52%   |
| Seagate ST320LT007-9ZV142 320GB     | 2         | 0.52%   |
| SanDisk NVMe SSD Drive 256GB        | 2         | 0.52%   |
| Samsung SSD 980 1TB                 | 2         | 0.52%   |
| Samsung SSD 970 EVO Plus 500GB      | 2         | 0.52%   |
| Samsung SSD 970 EVO Plus 1TB        | 2         | 0.52%   |
| Samsung NVMe SSD Drive 512GB        | 2         | 0.52%   |
| Samsung NVMe SSD Drive 1024GB       | 2         | 0.52%   |
| Samsung HM500JI 500GB               | 2         | 0.52%   |
| Micron 2450_MTFDKBA1T0TFK 1TB       | 2         | 0.52%   |
| Kingston SV300S37A240G 240GB SSD    | 2         | 0.52%   |
| Kingston SV300S37A120G 120GB SSD    | 2         | 0.52%   |
| Kingston SA400S37240G 240GB SSD     | 2         | 0.52%   |
| Intel SSDPEKNU512GZ 512GB           | 2         | 0.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 34        | 38     | 27.2%   |
| WDC                 | 31        | 35     | 24.8%   |
| Seagate             | 25        | 25     | 20%     |
| Hitachi             | 13        | 15     | 10.4%   |
| HGST                | 11        | 14     | 8.8%    |
| Samsung Electronics | 5         | 5      | 4%      |
| Unknown             | 4         | 5      | 3.2%    |
| Fujitsu             | 1         | 1      | 0.8%    |
| ASMedia             | 1         | 1      | 0.8%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 21        | 24     | 19.63%  |
| Kingston            | 11        | 11     | 10.28%  |
| Crucial             | 10        | 15     | 9.35%   |
| SanDisk             | 8         | 9      | 7.48%   |
| WDC                 | 6         | 7      | 5.61%   |
| China               | 6         | 6      | 5.61%   |
| Apple               | 5         | 5      | 4.67%   |
| Toshiba             | 4         | 5      | 3.74%   |
| Micron Technology   | 4         | 4      | 3.74%   |
| LITEON              | 3         | 3      | 2.8%    |
| Team                | 2         | 2      | 1.87%   |
| PNY                 | 2         | 2      | 1.87%   |
| Intel               | 2         | 2      | 1.87%   |
| BR                  | 2         | 2      | 1.87%   |
| A-DATA Technology   | 2         | 2      | 1.87%   |
| Unknown             | 2         | 2      | 1.87%   |
| W800SH              | 1         | 1      | 0.93%   |
| Unknown             | 1         | 1      | 0.93%   |
| Transcend           | 1         | 1      | 0.93%   |
| SK hynix            | 1         | 1      | 0.93%   |
| S3+                 | 1         | 1      | 0.93%   |
| RZX                 | 1         | 1      | 0.93%   |
| Patriot             | 1         | 1      | 0.93%   |
| Netac               | 1         | 1      | 0.93%   |
| LITEONIT            | 1         | 1      | 0.93%   |
| KingSpec            | 1         | 2      | 0.93%   |
| KingFast            | 1         | 1      | 0.93%   |
| Intenso             | 1         | 2      | 0.93%   |
| HS-SSD-C100         | 1         | 1      | 0.93%   |
| Hewlett-Packard     | 1         | 1      | 0.93%   |
| Corsair             | 1         | 2      | 0.93%   |
| BHT                 | 1         | 1      | 0.93%   |
| ASMT                | 1         | 1      | 0.93%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 122       | 139    | 35.16%  |
| NVMe    | 99        | 125    | 28.53%  |
| SSD     | 99        | 121    | 28.53%  |
| MMC     | 22        | 25     | 6.34%   |
| Unknown | 5         | 5      | 1.44%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 201       | 249    | 59.47%  |
| NVMe | 99        | 124    | 29.29%  |
| MMC  | 22        | 25     | 6.51%   |
| SAS  | 16        | 17     | 4.73%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 138       | 170    | 62.73%  |
| 0.51-1.0   | 76        | 83     | 34.55%  |
| 1.01-2.0   | 6         | 7      | 2.73%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 72        | 24.91%  |
| 101-250        | 60        | 20.76%  |
| 501-1000       | 51        | 17.65%  |
| Unknown        | 32        | 11.07%  |
| 1001-2000      | 31        | 10.73%  |
| 51-100         | 16        | 5.54%   |
| 21-50          | 13        | 4.5%    |
| 1-20           | 6         | 2.08%   |
| More than 3000 | 4         | 1.38%   |
| 2001-3000      | 4         | 1.38%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 21-50          | 96        | 32.32%  |
| 51-100         | 53        | 17.85%  |
| 1-20           | 41        | 13.8%   |
| 101-250        | 35        | 11.78%  |
| Unknown        | 32        | 10.77%  |
| 251-500        | 26        | 8.75%   |
| 501-1000       | 9         | 3.03%   |
| 0              | 2         | 0.67%   |
| More than 3000 | 1         | 0.34%   |
| 2001-3000      | 1         | 0.34%   |
| 1001-2000      | 1         | 0.34%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                              | 2         | 2      | 6.06%   |
| Samsung Electronics HM500JI 500GB                   | 2         | 2      | 6.06%   |
| WDC WD3200BPVT-00JJ5T0 320GB                        | 1         | 1      | 3.03%   |
| WDC WD3200BEKT-75PVMT1 320GB                        | 1         | 1      | 3.03%   |
| WDC WD2500BEVT-22A23T0 250GB                        | 1         | 1      | 3.03%   |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 3.03%   |
| Toshiba MK3265GSXF 320GB                            | 1         | 1      | 3.03%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 1         | 1      | 3.03%   |
| Seagate ST320LM001 HN-M320MBB 320GB                 | 1         | 1      | 3.03%   |
| Seagate ST2000LM007-1R8174 2TB                      | 1         | 1      | 3.03%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1      | 3.03%   |
| SanDisk SD8SBAT256G1122 256GB SSD                   | 1         | 1      | 3.03%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD    | 1         | 1      | 3.03%   |
| Samsung Electronics HM160HI 160GB                   | 1         | 1      | 3.03%   |
| Micron Technology MTFDDAK128MAY-1AH1ZABHA 128GB SSD | 1         | 1      | 3.03%   |
| LITEON CV8-8E128-HP 128GB SSD                       | 1         | 1      | 3.03%   |
| Kingston SUV400S37480G 480GB SSD                    | 1         | 1      | 3.03%   |
| Intel HBRPEKNX0202AHO 32GB                          | 1         | 1      | 3.03%   |
| Hitachi HTS725050A9A360 500GB                       | 1         | 1      | 3.03%   |
| Hitachi HTS725032A9A364 320GB                       | 1         | 1      | 3.03%   |
| Hitachi HTS723216L9SA60 160GB                       | 1         | 1      | 3.03%   |
| Hitachi HTS542512K9SA00 120GB                       | 1         | 1      | 3.03%   |
| HGST HTS725032A7E630 320GB                          | 1         | 1      | 3.03%   |
| HGST HTS721010A9E630 1TB                            | 1         | 1      | 3.03%   |
| HGST HTS541010A9E680 1TB                            | 1         | 1      | 3.03%   |
| Hewlett-Packard SSD S700 Pro 1TB                    | 1         | 1      | 3.03%   |
| Fujitsu MHY2160BH 160GB                             | 1         | 1      | 3.03%   |
| Crucial CT525MX300SSD1 528GB                        | 1         | 1      | 3.03%   |
| A-DATA Technology SX6000LNP 1TB                     | 1         | 1      | 3.03%   |
| A-DATA Technology SU700 120GB SSD                   | 1         | 1      | 3.03%   |
| Unknown                                             | 1         | 1      | 3.03%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 4         | 4      | 12.12%  |
| Seagate             | 4         | 4      | 12.12%  |
| Samsung Electronics | 4         | 4      | 12.12%  |
| Hitachi             | 4         | 4      | 12.12%  |
| WDC                 | 3         | 3      | 9.09%   |
| HGST                | 3         | 3      | 9.09%   |
| A-DATA Technology   | 2         | 2      | 6.06%   |
| SanDisk             | 1         | 1      | 3.03%   |
| Micron Technology   | 1         | 1      | 3.03%   |
| LITEON              | 1         | 1      | 3.03%   |
| Kingston            | 1         | 1      | 3.03%   |
| Intel               | 1         | 1      | 3.03%   |
| Hewlett-Packard     | 1         | 1      | 3.03%   |
| Fujitsu             | 1         | 1      | 3.03%   |
| Crucial             | 1         | 1      | 3.03%   |
| Unknown             | 1         | 1      | 3.03%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 4         | 4      | 18.18%  |
| Seagate             | 4         | 4      | 18.18%  |
| Hitachi             | 4         | 4      | 18.18%  |
| WDC                 | 3         | 3      | 13.64%  |
| Samsung Electronics | 3         | 3      | 13.64%  |
| HGST                | 3         | 3      | 13.64%  |
| Fujitsu             | 1         | 1      | 4.55%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 22        | 22     | 66.67%  |
| SSD  | 9         | 9      | 27.27%  |
| NVMe | 2         | 2      | 6.06%   |

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
| Works    | 154       | 192    | 48.58%  |
| Detected | 131       | 190    | 41.32%  |
| Malfunc  | 32        | 33     | 10.09%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 213       | 61.74%  |
| Samsung Electronics          | 34        | 9.86%   |
| AMD                          | 27        | 7.83%   |
| SanDisk                      | 17        | 4.93%   |
| Kingston Technology Company  | 12        | 3.48%   |
| SK hynix                     | 8         | 2.32%   |
| Micron Technology            | 8         | 2.32%   |
| Toshiba America Info Systems | 4         | 1.16%   |
| KIOXIA                       | 4         | 1.16%   |
| Yangtze Memory Technologies  | 3         | 0.87%   |
| Silicon Motion               | 3         | 0.87%   |
| Nvidia                       | 3         | 0.87%   |
| ADATA Technology             | 3         | 0.87%   |
| Phison Electronics           | 2         | 0.58%   |
| Micron/Crucial Technology    | 2         | 0.58%   |
| Realtek Semiconductor        | 1         | 0.29%   |
| Apple                        | 1         | 0.29%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 26        | 6.91%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 23        | 6.12%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 22        | 5.85%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 22        | 5.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 18        | 4.79%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 17        | 4.52%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 15        | 3.99%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 11        | 2.93%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 11        | 2.93%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 9         | 2.39%   |
| Micron NVMe Storage Controller                                                         | 8         | 2.13%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 8         | 2.13%   |
| SanDisk WD Blue SN550 NVMe SSD                                                         | 7         | 1.86%   |
| Samsung NVMe SSD Controller 980                                                        | 7         | 1.86%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 6         | 1.6%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 6         | 1.6%    |
| Kingston Company Company Non-Volatile memory controller                                | 5         | 1.33%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 5         | 1.33%   |
| Intel Alder Lake-P SATA AHCI Controller                                                | 5         | 1.33%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 5         | 1.33%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 5         | 1.33%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 5         | 1.33%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                         | 4         | 1.06%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 4         | 1.06%   |
| SanDisk NVMe Controller                                                                | 4         | 1.06%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 4         | 1.06%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 4         | 1.06%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 4         | 1.06%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 4         | 1.06%   |
| Yangtze Memory Non-Volatile memory controller                                          | 3         | 0.8%    |
| SK hynix BC511                                                                         | 3         | 0.8%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 3         | 0.8%    |
| Samsung Electronics SATA controller                                                    | 3         | 0.8%    |
| KIOXIA NVMe SSD Controller BG4                                                         | 3         | 0.8%    |
| Intel Tiger Lake-LP SATA Controller                                                    | 3         | 0.8%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 3         | 0.8%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 3         | 0.8%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 3         | 0.8%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 3         | 0.8%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 3         | 0.8%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 193       | 54.21%  |
| NVMe | 99        | 27.81%  |
| RAID | 39        | 10.96%  |
| IDE  | 25        | 7.02%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 246       | 86.32%  |
| AMD    | 39        | 13.68%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz       | 10        | 3.51%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 7         | 2.46%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 7         | 2.46%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 5         | 1.75%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 5         | 1.75%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 5         | 1.75%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 4         | 1.4%    |
| Intel Core i7-8750H CPU @ 2.20GHz       | 4         | 1.4%    |
| Intel Core i7-8550U CPU @ 1.80GHz       | 4         | 1.4%    |
| Intel Core i7-6500U CPU @ 2.50GHz       | 4         | 1.4%    |
| Intel Core i7-10750H CPU @ 2.60GHz      | 4         | 1.4%    |
| Intel Core i5-8250U CPU @ 1.60GHz       | 4         | 1.4%    |
| Intel Core i5-6200U CPU @ 2.30GHz       | 4         | 1.4%    |
| Intel Core i3-5005U CPU @ 2.00GHz       | 4         | 1.4%    |
| Intel Core i3-1005G1 CPU @ 1.20GHz      | 4         | 1.4%    |
| Intel 12th Gen Core i7-12700H           | 4         | 1.4%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 4         | 1.4%    |
| Intel Core i5-7200U CPU @ 2.50GHz       | 3         | 1.05%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 3         | 1.05%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 3         | 1.05%   |
| Intel Core i5-2430M CPU @ 2.40GHz       | 3         | 1.05%   |
| Intel Core i3-6006U CPU @ 2.00GHz       | 3         | 1.05%   |
| Intel Core 2 CPU T5600 @ 1.83GHz        | 3         | 1.05%   |
| Intel Celeron J4125 CPU @ 2.00GHz       | 3         | 1.05%   |
| Intel Celeron CPU N3060 @ 1.60GHz       | 3         | 1.05%   |
| Intel 12th Gen Core i5-12500H           | 3         | 1.05%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 3         | 1.05%   |
| AMD Ryzen 7 5800H with Radeon Graphics  | 3         | 1.05%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 3         | 1.05%   |
| Intel Core i7-8850H CPU @ 2.60GHz       | 2         | 0.7%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 2         | 0.7%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 2         | 0.7%    |
| Intel Core i7-6600U CPU @ 2.60GHz       | 2         | 0.7%    |
| Intel Core i7-4600U CPU @ 2.10GHz       | 2         | 0.7%    |
| Intel Core i7-4510U CPU @ 2.00GHz       | 2         | 0.7%    |
| Intel Core i7-3630QM CPU @ 2.40GHz      | 2         | 0.7%    |
| Intel Core i7-3610QM CPU @ 2.30GHz      | 2         | 0.7%    |
| Intel Core i7-3520M CPU @ 2.90GHz       | 2         | 0.7%    |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 2         | 0.7%    |
| Intel Core i7-2620M CPU @ 2.70GHz       | 2         | 0.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 77        | 27.02%  |
| Intel Core i7           | 71        | 24.91%  |
| Other                   | 33        | 11.58%  |
| Intel Core i3           | 28        | 9.82%   |
| Intel Celeron           | 16        | 5.61%   |
| AMD Ryzen 7             | 11        | 3.86%   |
| Intel Core 2 Duo        | 9         | 3.16%   |
| AMD Ryzen 5             | 8         | 2.81%   |
| AMD A6                  | 6         | 2.11%   |
| Intel Core 2            | 4         | 1.4%    |
| Intel Pentium           | 3         | 1.05%   |
| AMD Ryzen 3             | 3         | 1.05%   |
| AMD E1                  | 3         | 1.05%   |
| Intel Pentium Silver    | 2         | 0.7%    |
| Intel Atom              | 2         | 0.7%    |
| AMD A4                  | 2         | 0.7%    |
| Intel Pentium Dual-Core | 1         | 0.35%   |
| Intel Core 2 Quad       | 1         | 0.35%   |
| Intel Core 2 Extreme    | 1         | 0.35%   |
| AMD E2                  | 1         | 0.35%   |
| AMD E                   | 1         | 0.35%   |
| AMD C-50                | 1         | 0.35%   |
| AMD Athlon X2           | 1         | 0.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 150       | 52.63%  |
| 4      | 82        | 28.77%  |
| 6      | 24        | 8.42%   |
| 8      | 14        | 4.91%   |
| 14     | 5         | 1.75%   |
| 12     | 5         | 1.75%   |
| 1      | 3         | 1.05%   |
| 10     | 2         | 0.7%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 285       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 215       | 75.44%  |
| 1      | 70        | 24.56%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 280       | 98.25%  |
| Unknown        | 5         | 1.75%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 116       | 39.73%  |
| 0x206a7    | 20        | 6.85%   |
| 0x306a9    | 15        | 5.14%   |
| 0x906a3    | 10        | 3.42%   |
| 0x806ec    | 10        | 3.42%   |
| 0x406e3    | 9         | 3.08%   |
| 0x906ea    | 8         | 2.74%   |
| 0x806e9    | 8         | 2.74%   |
| 0x806c1    | 8         | 2.74%   |
| 0xa0652    | 7         | 2.4%    |
| 0x806ea    | 6         | 2.05%   |
| 0x706a8    | 6         | 2.05%   |
| 0x706e5    | 5         | 1.71%   |
| 0x40651    | 5         | 1.71%   |
| 0x6f6      | 4         | 1.37%   |
| 0x306c3    | 4         | 1.37%   |
| 0x1067a    | 4         | 1.37%   |
| 0x806d1    | 3         | 1.03%   |
| 0x306d4    | 3         | 1.03%   |
| 0x0a50000c | 3         | 1.03%   |
| 0x08600106 | 3         | 1.03%   |
| 0x07030105 | 3         | 1.03%   |
| 0x906e9    | 2         | 0.68%   |
| 0x906a4    | 2         | 0.68%   |
| 0x806eb    | 2         | 0.68%   |
| 0x6fd      | 2         | 0.68%   |
| 0x406c4    | 2         | 0.68%   |
| 0x08608103 | 2         | 0.68%   |
| 0x08108109 | 2         | 0.68%   |
| 0x06006705 | 2         | 0.68%   |
| 0x03000027 | 2         | 0.68%   |
| 0xa0660    | 1         | 0.34%   |
| 0x906ed    | 1         | 0.34%   |
| 0x806c2    | 1         | 0.34%   |
| 0x706a1    | 1         | 0.34%   |
| 0x506e3    | 1         | 0.34%   |
| 0x506c9    | 1         | 0.34%   |
| 0x40661    | 1         | 0.34%   |
| 0x30678    | 1         | 0.34%   |
| 0x20655    | 1         | 0.34%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 54        | 18.95%  |
| SandyBridge      | 30        | 10.53%  |
| IvyBridge        | 25        | 8.77%   |
| Haswell          | 20        | 7.02%   |
| Skylake          | 17        | 5.96%   |
| TigerLake        | 14        | 4.91%   |
| Broadwell        | 12        | 4.21%   |
| Alderlake Hybrid | 11        | 3.86%   |
| Penryn           | 10        | 3.51%   |
| CometLake        | 10        | 3.51%   |
| Unknown          | 10        | 3.51%   |
| Silvermont       | 9         | 3.16%   |
| IceLake          | 8         | 2.81%   |
| Goldmont plus    | 8         | 2.81%   |
| Core             | 7         | 2.46%   |
| Zen+             | 5         | 1.75%   |
| Zen 3            | 5         | 1.75%   |
| Zen 2            | 5         | 1.75%   |
| Westmere         | 5         | 1.75%   |
| Excavator        | 4         | 1.4%    |
| Puma             | 3         | 1.05%   |
| Jaguar           | 3         | 1.05%   |
| Piledriver       | 2         | 0.7%    |
| K10 Llano        | 2         | 0.7%    |
| Bobcat           | 2         | 0.7%    |
| Zen              | 1         | 0.35%   |
| Nehalem          | 1         | 0.35%   |
| K8 & K10 hybrid  | 1         | 0.35%   |
| Goldmont         | 1         | 0.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 229       | 59.95%  |
| Nvidia | 93        | 24.35%  |
| AMD    | 60        | 15.71%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 27        | 6.96%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 23        | 5.93%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 14        | 3.61%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 13        | 3.35%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 13        | 3.35%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 12        | 3.09%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 11        | 2.84%   |
| Intel UHD Graphics 620                                                                   | 10        | 2.58%   |
| Intel HD Graphics 5500                                                                   | 10        | 2.58%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 10        | 2.58%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 9         | 2.32%   |
| Intel HD Graphics 620                                                                    | 8         | 2.06%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 1.55%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 1.55%   |
| AMD Lucienne                                                                             | 6         | 1.55%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 5         | 1.29%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 5         | 1.29%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 5         | 1.29%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 1.29%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 1.29%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 1.29%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 5         | 1.29%   |
| AMD Renoir                                                                               | 5         | 1.29%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 1.29%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 4         | 1.03%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 4         | 1.03%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 1.03%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 4         | 1.03%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1.03%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 1.03%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 1.03%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4         | 1.03%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 3         | 0.77%   |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 0.77%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 0.77%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 3         | 0.77%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 0.77%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 0.77%   |
| Intel HD Graphics 630                                                                    | 3         | 0.77%   |
| Intel HD Graphics 530                                                                    | 3         | 0.77%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 138       | 48.25%  |
| Intel + Nvidia | 76        | 26.57%  |
| 1 x AMD        | 39        | 13.64%  |
| Intel + AMD    | 14        | 4.9%    |
| 1 x Nvidia     | 11        | 3.85%   |
| AMD + Nvidia   | 6         | 2.1%    |
| 2 x Nvidia     | 1         | 0.35%   |
| 2 x AMD        | 1         | 0.35%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 256       | 89.51%  |
| Proprietary | 28        | 9.79%   |
| Unknown     | 2         | 0.7%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 221       | 76.74%  |
| 1.01-2.0   | 18        | 6.25%   |
| 0.51-1.0   | 15        | 5.21%   |
| 3.01-4.0   | 14        | 4.86%   |
| 0.01-0.5   | 14        | 4.86%   |
| 7.01-8.0   | 2         | 0.69%   |
| 5.01-6.0   | 2         | 0.69%   |
| 2.01-3.0   | 2         | 0.69%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 70        | 22.08%  |
| LG Display              | 55        | 17.35%  |
| BOE                     | 53        | 16.72%  |
| Chimei Innolux          | 39        | 12.3%   |
| Samsung Electronics     | 29        | 9.15%   |
| Apple                   | 12        | 3.79%   |
| Chi Mei Optoelectronics | 8         | 2.52%   |
| Sharp                   | 5         | 1.58%   |
| PANDA                   | 4         | 1.26%   |
| Lenovo                  | 4         | 1.26%   |
| Dell                    | 4         | 1.26%   |
| Acer                    | 3         | 0.95%   |
| Sceptre Tech            | 2         | 0.63%   |
| Hewlett-Packard         | 2         | 0.63%   |
| Eizo                    | 2         | 0.63%   |
| CSO                     | 2         | 0.63%   |
| Ancor Communications    | 2         | 0.63%   |
| ___                     | 1         | 0.32%   |
| VIZ                     | 1         | 0.32%   |
| ViewSonic               | 1         | 0.32%   |
| Unknown (AAA)           | 1         | 0.32%   |
| Unknown                 | 1         | 0.32%   |
| STD                     | 1         | 0.32%   |
| STA                     | 1         | 0.32%   |
| SANYO                   | 1         | 0.32%   |
| Planar                  | 1         | 0.32%   |
| Philips                 | 1         | 0.32%   |
| Panasonic               | 1         | 0.32%   |
| ONN                     | 1         | 0.32%   |
| NEC Computers           | 1         | 0.32%   |
| LG Philips              | 1         | 0.32%   |
| Kogan                   | 1         | 0.32%   |
| InfoVision              | 1         | 0.32%   |
| Goldstar                | 1         | 0.32%   |
| Element                 | 1         | 0.32%   |
| BOE Technology Group    | 1         | 0.32%   |
| BenQ                    | 1         | 0.32%   |
| AOC                     | 1         | 0.32%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 4         | 1.26%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 4         | 1.26%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch | 3         | 0.95%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 3         | 0.95%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch         | 3         | 0.95%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 3         | 0.95%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch       | 3         | 0.95%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch       | 3         | 0.95%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch        | 3         | 0.95%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch       | 3         | 0.95%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch | 2         | 0.63%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch | 2         | 0.63%   |
| LG Display LCD Monitor LGD0390 1600x900 382x215mm 17.3-inch          | 2         | 0.63%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch         | 2         | 0.63%   |
| LG Display LCD Monitor LGD01E9 1920x1080 345x194mm 15.6-inch         | 2         | 0.63%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch     | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch      | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 2         | 0.63%   |
| BOE LCD Monitor BOE08E2 1920x1080 344x194mm 15.5-inch                | 2         | 0.63%   |
| BOE LCD Monitor BOE08BE 1920x1080 382x215mm 17.3-inch                | 2         | 0.63%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                | 2         | 0.63%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch        | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch        | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch        | 2         | 0.63%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                 | 2         | 0.63%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                 | 2         | 0.63%   |
| ___ LCD TV ___9000 1360x768                                          | 1         | 0.32%   |
| VIZ LCD Monitor VA19L HDTV10T                                        | 1         | 0.32%   |
| ViewSonic VA2718-FHD VSCD839 1920x1080 598x336mm 27.0-inch           | 1         | 0.32%   |
| Unknown LCD TV 9000 1360x768 1600x900mm 72.3-inch                    | 1         | 0.32%   |
| Unknown (AAA) LCDTV AAA0042 1360x768 890x500mm 40.2-inch             | 1         | 0.32%   |
| STD HDMI TV STD00C7 1360x768 698x392mm 31.5-inch                     | 1         | 0.32%   |
| STA XR140EA1T STA0450 1366x768 310x174mm 14.0-inch                   | 1         | 0.32%   |
| Sharp LCD Monitor SHP1542 1920x1080 309x174mm 14.0-inch              | 1         | 0.32%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch              | 1         | 0.32%   |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch              | 1         | 0.32%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch              | 1         | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 129       | 42.72%  |
| 1366x768 (WXGA)    | 103       | 34.11%  |
| 1600x900 (HD+)     | 17        | 5.63%   |
| 1280x800 (WXGA)    | 12        | 3.97%   |
| 1440x900 (WXGA+)   | 7         | 2.32%   |
| 3840x2160 (4K)     | 5         | 1.66%   |
| 2560x1440 (QHD)    | 4         | 1.32%   |
| 1680x1050 (WSXGA+) | 4         | 1.32%   |
| 2880x1800          | 3         | 0.99%   |
| 2560x1600          | 3         | 0.99%   |
| 1920x1200 (WUXGA)  | 3         | 0.99%   |
| 2160x1440          | 2         | 0.66%   |
| 1024x768 (XGA)     | 2         | 0.66%   |
| 3200x1080          | 1         | 0.33%   |
| 2560x1080          | 1         | 0.33%   |
| 2240x1400          | 1         | 0.33%   |
| 1920x540           | 1         | 0.33%   |
| 1920x515           | 1         | 0.33%   |
| 1360x768           | 1         | 0.33%   |
| 1280x1024 (SXGA)   | 1         | 0.33%   |
| Unknown            | 1         | 0.33%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 136       | 43.17%  |
| 14      | 44        | 13.97%  |
| 13      | 40        | 12.7%   |
| 17      | 27        | 8.57%   |
| 12      | 13        | 4.13%   |
| 27      | 7         | 2.22%   |
| 24      | 7         | 2.22%   |
| 11      | 7         | 2.22%   |
| 31      | 5         | 1.59%   |
| 16      | 5         | 1.59%   |
| 21      | 4         | 1.27%   |
| Unknown | 4         | 1.27%   |
| 23      | 3         | 0.95%   |
| 22      | 3         | 0.95%   |
| 32      | 2         | 0.63%   |
| 19      | 2         | 0.63%   |
| 72      | 1         | 0.32%   |
| 54      | 1         | 0.32%   |
| 48      | 1         | 0.32%   |
| 40      | 1         | 0.32%   |
| 29      | 1         | 0.32%   |
| 18      | 1         | 0.32%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 203       | 64.65%  |
| 201-300     | 37        | 11.78%  |
| 351-400     | 33        | 10.51%  |
| 501-600     | 17        | 5.41%   |
| 401-500     | 8         | 2.55%   |
| 601-700     | 6         | 1.91%   |
| Unknown     | 4         | 1.27%   |
| 701-800     | 2         | 0.64%   |
| 1001-1500   | 2         | 0.64%   |
| 801-900     | 1         | 0.32%   |
| 1501-2000   | 1         | 0.32%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 248       | 85.81%  |
| 16/10   | 32        | 11.07%  |
| 4/3     | 2         | 0.69%   |
| 3/2     | 2         | 0.69%   |
| 6/5     | 1         | 0.35%   |
| 32/9    | 1         | 0.35%   |
| 3.73    | 1         | 0.35%   |
| 21/9    | 1         | 0.35%   |
| Unknown | 1         | 0.35%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 139       | 44.13%  |
| 81-90          | 70        | 22.22%  |
| 121-130        | 24        | 7.62%   |
| 201-250        | 15        | 4.76%   |
| 71-80          | 14        | 4.44%   |
| 61-70          | 13        | 4.13%   |
| 301-350        | 8         | 2.54%   |
| 51-60          | 7         | 2.22%   |
| 351-500        | 7         | 2.22%   |
| Unknown        | 4         | 1.27%   |
| More than 1000 | 3         | 0.95%   |
| 131-140        | 3         | 0.95%   |
| 251-300        | 2         | 0.63%   |
| 151-200        | 2         | 0.63%   |
| 111-120        | 2         | 0.63%   |
| 141-150        | 1         | 0.32%   |
| 501-1000       | 1         | 0.32%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 136       | 43.59%  |
| 101-120       | 102       | 32.69%  |
| 51-100        | 42        | 13.46%  |
| 161-240       | 19        | 6.09%   |
| More than 240 | 5         | 1.6%    |
| 1-50          | 4         | 1.28%   |
| Unknown       | 4         | 1.28%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 246       | 85.42%  |
| 2     | 35        | 12.15%  |
| 3     | 5         | 1.74%   |
| 0     | 2         | 0.69%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 166       | 34.44%  |
| Realtek Semiconductor                  | 153       | 31.74%  |
| Qualcomm Atheros                       | 58        | 12.03%  |
| Broadcom                               | 25        | 5.19%   |
| MediaTek                               | 11        | 2.28%   |
| Broadcom Limited                       | 9         | 1.87%   |
| TP-Link                                | 7         | 1.45%   |
| Samsung Electronics                    | 7         | 1.45%   |
| Xiaomi                                 | 5         | 1.04%   |
| Qualcomm Atheros Communications        | 4         | 0.83%   |
| Huawei Technologies                    | 4         | 0.83%   |
| Ralink Technology                      | 3         | 0.62%   |
| NetGear                                | 3         | 0.62%   |
| ASUSTek Computer                       | 3         | 0.62%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.41%   |
| Ralink                                 | 2         | 0.41%   |
| Nvidia                                 | 2         | 0.41%   |
| Ericsson Business Mobile Networks      | 2         | 0.41%   |
| ASIX Electronics                       | 2         | 0.41%   |
| Apple                                  | 2         | 0.41%   |
| ZyXEL Communications                   | 1         | 0.21%   |
| Sagem                                  | 1         | 0.21%   |
| Qualcomm                               | 1         | 0.21%   |
| OPPO Electronics                       | 1         | 0.21%   |
| Mercucys                               | 1         | 0.21%   |
| Linksys                                | 1         | 0.21%   |
| Lenovo                                 | 1         | 0.21%   |
| JMicron Technology                     | 1         | 0.21%   |
| DisplayLink                            | 1         | 0.21%   |
| D-Link                                 | 1         | 0.21%   |
| Belkin Components                      | 1         | 0.21%   |
| Arduino SA                             | 1         | 0.21%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 81        | 13.99%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 31        | 5.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 18        | 3.11%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 16        | 2.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 11        | 1.9%    |
| Intel Wi-Fi 6 AX201                                               | 11        | 1.9%    |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 11        | 1.9%    |
| Intel Wireless 8265 / 8275                                        | 10        | 1.73%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 9         | 1.55%   |
| Intel Wireless 7260                                               | 9         | 1.55%   |
| Intel Wi-Fi 6 AX200                                               | 9         | 1.55%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 8         | 1.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 8         | 1.38%   |
| Intel Wireless 7265                                               | 8         | 1.38%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 8         | 1.38%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 8         | 1.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 7         | 1.21%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 7         | 1.21%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 7         | 1.21%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 6         | 1.04%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 6         | 1.04%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 6         | 1.04%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 6         | 1.04%   |
| Intel Wireless 3165                                               | 6         | 1.04%   |
| Intel Ethernet Connection I218-LM                                 | 6         | 1.04%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 6         | 1.04%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 5         | 0.86%   |
| Realtek 802.11ac NIC                                              | 5         | 0.86%   |
| Intel Wireless 8260                                               | 5         | 0.86%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 4         | 0.69%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 0.69%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 4         | 0.69%   |
| Qualcomm Atheros AR9271 802.11n                                   | 4         | 0.69%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4         | 0.69%   |
| Intel Wireless 3160                                               | 4         | 0.69%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 4         | 0.69%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4         | 0.69%   |
| Intel Centrino Advanced-N 6235                                    | 4         | 0.69%   |
| Broadcom BCM43142 802.11b/g/n                                     | 4         | 0.69%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 162       | 49.54%  |
| Realtek Semiconductor           | 57        | 17.43%  |
| Qualcomm Atheros                | 43        | 13.15%  |
| Broadcom                        | 21        | 6.42%   |
| MediaTek                        | 9         | 2.75%   |
| TP-Link                         | 7         | 2.14%   |
| Broadcom Limited                | 7         | 2.14%   |
| Qualcomm Atheros Communications | 4         | 1.22%   |
| Ralink Technology               | 3         | 0.92%   |
| NetGear                         | 3         | 0.92%   |
| ASUSTek Computer                | 3         | 0.92%   |
| Ralink                          | 2         | 0.61%   |
| ZyXEL Communications            | 1         | 0.31%   |
| Sagem                           | 1         | 0.31%   |
| Mercucys                        | 1         | 0.31%   |
| Linksys                         | 1         | 0.31%   |
| D-Link                          | 1         | 0.31%   |
| Belkin Components               | 1         | 0.31%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 16        | 4.89%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 11        | 3.36%   |
| Intel Wi-Fi 6 AX201                                            | 11        | 3.36%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 11        | 3.36%   |
| Intel Wireless 8265 / 8275                                     | 10        | 3.06%   |
| Intel Wireless 7260                                            | 9         | 2.75%   |
| Intel Wi-Fi 6 AX200                                            | 9         | 2.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 8         | 2.45%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 8         | 2.45%   |
| Intel Wireless 7265                                            | 8         | 2.45%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 8         | 2.45%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 8         | 2.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 7         | 2.14%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 7         | 2.14%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 7         | 2.14%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 6         | 1.83%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 6         | 1.83%   |
| Intel Wireless 3165                                            | 6         | 1.83%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 6         | 1.83%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 5         | 1.53%   |
| Realtek 802.11ac NIC                                           | 5         | 1.53%   |
| Intel Wireless 8260                                            | 5         | 1.53%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 4         | 1.22%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 1.22%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 4         | 1.22%   |
| Qualcomm Atheros AR9271 802.11n                                | 4         | 1.22%   |
| Intel Wireless 3160                                            | 4         | 1.22%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 4         | 1.22%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 4         | 1.22%   |
| Intel Centrino Advanced-N 6235                                 | 4         | 1.22%   |
| Broadcom BCM43142 802.11b/g/n                                  | 4         | 1.22%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 3         | 0.92%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 3         | 0.92%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 3         | 0.92%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 3         | 0.92%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 3         | 0.92%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 3         | 0.92%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3         | 0.92%   |
| Intel Centrino Wireless-N 2230                                 | 3         | 0.92%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 3         | 0.92%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 131       | 54.13%  |
| Intel                                  | 49        | 20.25%  |
| Qualcomm Atheros                       | 24        | 9.92%   |
| Broadcom                               | 9         | 3.72%   |
| Samsung Electronics                    | 7         | 2.89%   |
| Xiaomi                                 | 5         | 2.07%   |
| Nvidia                                 | 2         | 0.83%   |
| MediaTek                               | 2         | 0.83%   |
| Broadcom Limited                       | 2         | 0.83%   |
| ASIX Electronics                       | 2         | 0.83%   |
| Apple                                  | 2         | 0.83%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.41%   |
| Qualcomm                               | 1         | 0.41%   |
| OPPO Electronics                       | 1         | 0.41%   |
| Lenovo                                 | 1         | 0.41%   |
| JMicron Technology                     | 1         | 0.41%   |
| Huawei Technologies                    | 1         | 0.41%   |
| DisplayLink                            | 1         | 0.41%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 81        | 33.06%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 31        | 12.65%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 18        | 7.35%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 9         | 3.67%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 6         | 2.45%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 6         | 2.45%   |
| Intel Ethernet Connection I218-LM                                 | 6         | 2.45%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4         | 1.63%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 1.22%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 1.22%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 3         | 1.22%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 1.22%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 1.22%   |
| Intel Ethernet Connection (6) I219-V                              | 3         | 1.22%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.22%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 1.22%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 3         | 1.22%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 2         | 0.82%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.82%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.82%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 0.82%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 2         | 0.82%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.82%   |
| MediaTek U318AA                                                   | 2         | 0.82%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.82%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.82%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.82%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.82%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 0.82%   |
| Sony Ericsson Mobile AB G8341                                     | 1         | 0.41%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.41%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.41%   |
| Realtek PCIe GbE Family Controller                                | 1         | 0.41%   |
| Qualcomm QM215-QRD _SN:E72764DE                                   | 1         | 0.41%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.41%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.41%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.41%   |
| OPPO RMX3263                                                      | 1         | 0.41%   |
| Nvidia MCP89 Ethernet                                             | 1         | 0.41%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 283       | 54.63%  |
| Ethernet | 228       | 44.02%  |
| Modem    | 6         | 1.16%   |
| Unknown  | 1         | 0.19%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 228       | 76.51%  |
| Ethernet | 69        | 23.15%  |
| Unknown  | 1         | 0.34%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 203       | 71.23%  |
| 1     | 74        | 25.96%  |
| 0     | 5         | 1.75%   |
| 3     | 3         | 1.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Notebooks | Percent |
|---------|-----------|---------|
| No      | 234       | 80.97%  |
| Yes     | 54        | 18.69%  |
| Unknown | 1         | 0.35%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 117       | 50.43%  |
| Qualcomm Atheros Communications | 24        | 10.34%  |
| Realtek Semiconductor           | 22        | 9.48%   |
| Broadcom                        | 16        | 6.9%    |
| Foxconn / Hon Hai               | 9         | 3.88%   |
| Apple                           | 9         | 3.88%   |
| Lite-On Technology              | 8         | 3.45%   |
| IMC Networks                    | 8         | 3.45%   |
| Dell                            | 4         | 1.72%   |
| Cambridge Silicon Radio         | 4         | 1.72%   |
| MediaTek                        | 3         | 1.29%   |
| Toshiba                         | 2         | 0.86%   |
| Ralink                          | 2         | 0.86%   |
| TP-Link                         | 1         | 0.43%   |
| Realtek                         | 1         | 0.43%   |
| Dynex                           | 1         | 0.43%   |
| Alps Electric                   | 1         | 0.43%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 40        | 17.24%  |
| Intel AX201 Bluetooth                                                               | 30        | 12.93%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 23        | 9.91%   |
| Realtek Bluetooth Radio                                                             | 13        | 5.6%    |
| Qualcomm Atheros  Bluetooth Device                                                  | 10        | 4.31%   |
| Intel AX200 Bluetooth                                                               | 8         | 3.45%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 6         | 2.59%   |
| Apple Bluetooth Host Controller                                                     | 5         | 2.16%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 4         | 1.72%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 4         | 1.72%   |
| Intel Bluetooth Device                                                              | 4         | 1.72%   |
| Dell DW375 Bluetooth Module                                                         | 4         | 1.72%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 4         | 1.72%   |
| Broadcom HP Portable SoftSailing                                                    | 4         | 1.72%   |
| Apple Bluetooth USB Host Controller                                                 | 4         | 1.72%   |
| Qualcomm Atheros Bluetooth                                                          | 3         | 1.29%   |
| MediaTek Wireless_Device                                                            | 3         | 1.29%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 1.29%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 1.29%   |
| IMC Networks Wireless_Device                                                        | 3         | 1.29%   |
| IMC Networks Bluetooth Radio                                                        | 3         | 1.29%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 3         | 1.29%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 3         | 1.29%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 3         | 1.29%   |
| Realtek RTL8821A Bluetooth                                                          | 2         | 0.86%   |
| Ralink RT3290 Bluetooth                                                             | 2         | 0.86%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 2         | 0.86%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 2         | 0.86%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 0.86%   |
| Lite-On Wireless_Device                                                             | 2         | 0.86%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 0.86%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 2         | 0.86%   |
| IMC Networks Bluetooth Device                                                       | 2         | 0.86%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 0.86%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 2         | 0.86%   |
| TP-Link UB500 Adapter                                                               | 1         | 0.43%   |
| Toshiba Bluetooth USB Host Controller                                               | 1         | 0.43%   |
| Toshiba BCM43142A0                                                                  | 1         | 0.43%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.43%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.43%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor    | Notebooks | Percent |
|-----------|-----------|---------|
| Intel     | 240       | 70.38%  |
| Nvidia    | 53        | 15.54%  |
| AMD       | 43        | 12.61%  |
| Lenovo    | 1         | 0.29%   |
| JMTek     | 1         | 0.29%   |
| Guillemot | 1         | 0.29%   |
| GN Netcom | 1         | 0.29%   |
| Apple     | 1         | 0.29%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 33        | 8.11%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 28        | 6.88%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 27        | 6.63%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 21        | 5.16%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 14        | 3.44%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 14        | 3.44%   |
| Intel 8 Series HD Audio Controller                                                                | 14        | 3.44%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 13        | 3.19%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 13        | 3.19%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 12        | 2.95%   |
| Intel Cannon Lake PCH cAVS                                                                        | 12        | 2.95%   |
| Intel Broadwell-U Audio Controller                                                                | 12        | 2.95%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 12        | 2.95%   |
| AMD FCH Azalia Controller                                                                         | 10        | 2.46%   |
| Intel Comet Lake PCH cAVS                                                                         | 9         | 2.21%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 8         | 1.97%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 7         | 1.72%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 7         | 1.72%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 6         | 1.47%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 6         | 1.47%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 6         | 1.47%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 1.47%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 1.47%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 1.47%   |
| AMD Kabini HDMI/DP Audio                                                                          | 6         | 1.47%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 1.23%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 5         | 1.23%   |
| Nvidia Audio device                                                                               | 5         | 1.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 1.23%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 5         | 1.23%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 0.98%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 0.98%   |
| AMD High Definition Audio Controller                                                              | 4         | 0.98%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 0.98%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 0.74%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 0.74%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 0.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.74%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 0.74%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 0.74%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 67        | 29%     |
| Micron Technology   | 43        | 18.61%  |
| SK hynix            | 41        | 17.75%  |
| Crucial             | 15        | 6.49%   |
| Kingston            | 11        | 4.76%   |
| Unknown             | 8         | 3.46%   |
| Elpida              | 8         | 3.46%   |
| Ramaxel Technology  | 7         | 3.03%   |
| Unknown (ABCD)      | 5         | 2.16%   |
| A-DATA Technology   | 5         | 2.16%   |
| Nanya Technology    | 4         | 1.73%   |
| Corsair             | 3         | 1.3%    |
| Transcend           | 2         | 0.87%   |
| Team                | 2         | 0.87%   |
| Smart               | 2         | 0.87%   |
| G.Skill             | 2         | 0.87%   |
| Timetec             | 1         | 0.43%   |
| Teikon              | 1         | 0.43%   |
| Saikano             | 1         | 0.43%   |
| PNY                 | 1         | 0.43%   |
| fef5                | 1         | 0.43%   |
| ChangXin Memory     | 1         | 0.43%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 2.9%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 2.49%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 5         | 2.07%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 1.66%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 4         | 1.66%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 1.24%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 3         | 1.24%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 1.24%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 3         | 1.24%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 1.24%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.24%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 1.24%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 1.24%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 3         | 1.24%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 3         | 1.24%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 2         | 0.83%   |
| Transcend RAM JM1333KSN-4G 4GB SODIMM DDR3 1334MT/s              | 2         | 0.83%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 2         | 0.83%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s             | 2         | 0.83%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.83%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 0.83%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 0.83%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.83%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 2         | 0.83%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.83%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.83%   |
| Samsung RAM M4 70T2953CZ3-CE6 1024MB SODIMM DDR2 667MT/s         | 2         | 0.83%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 2         | 0.83%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.83%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 2         | 0.83%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 2         | 0.83%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 2         | 0.83%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s           | 2         | 0.83%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                       | 2         | 0.83%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 2         | 0.83%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.41%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 1         | 0.41%   |
| Unknown RAM Module 4096MB SODIMM 1066MT/s                        | 1         | 0.41%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.41%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 87        | 44.16%  |
| DDR3    | 72        | 36.55%  |
| LPDDR4  | 15        | 7.61%   |
| LPDDR3  | 7         | 3.55%   |
| DDR2    | 5         | 2.54%   |
| DDR5    | 4         | 2.03%   |
| Unknown | 3         | 1.52%   |
| LPDDR5  | 2         | 1.02%   |
| SDRAM   | 1         | 0.51%   |
| DDR     | 1         | 0.51%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 173       | 88.27%  |
| Row Of Chips | 20        | 10.2%   |
| Unknown      | 2         | 1.02%   |
| Chip         | 1         | 0.51%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 79        | 37.8%   |
| 4096  | 70        | 33.49%  |
| 16384 | 26        | 12.44%  |
| 2048  | 21        | 10.05%  |
| 1024  | 10        | 4.78%   |
| 32768 | 3         | 1.44%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 48        | 22.33%  |
| 2667    | 47        | 21.86%  |
| 3200    | 34        | 15.81%  |
| 2400    | 19        | 8.84%   |
| 1334    | 16        | 7.44%   |
| 2133    | 10        | 4.65%   |
| 1333    | 7         | 3.26%   |
| 4800    | 5         | 2.33%   |
| 1867    | 4         | 1.86%   |
| 3266    | 3         | 1.4%    |
| 1067    | 3         | 1.4%    |
| 1066    | 3         | 1.4%    |
| 667     | 3         | 1.4%    |
| 6400    | 2         | 0.93%   |
| 4267    | 2         | 0.93%   |
| 3733    | 2         | 0.93%   |
| Unknown | 2         | 0.93%   |
| 8400    | 1         | 0.47%   |
| 2048    | 1         | 0.47%   |
| 975     | 1         | 0.47%   |
| 800     | 1         | 0.47%   |
| 533     | 1         | 0.47%   |

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
| Chicony Electronics                    | 74        | 28.91%  |
| IMC Networks                           | 28        | 10.94%  |
| Acer                                   | 26        | 10.16%  |
| Microdia                               | 20        | 7.81%   |
| Sunplus Innovation Technology          | 16        | 6.25%   |
| Realtek Semiconductor                  | 14        | 5.47%   |
| Quanta                                 | 12        | 4.69%   |
| Apple                                  | 10        | 3.91%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 2.73%   |
| Syntek                                 | 6         | 2.34%   |
| Suyin                                  | 5         | 1.95%   |
| Ricoh                                  | 5         | 1.95%   |
| Luxvisions Innotech Limited            | 5         | 1.95%   |
| Samsung Electronics                    | 4         | 1.56%   |
| Sonix Technology                       | 3         | 1.17%   |
| Silicon Motion                         | 3         | 1.17%   |
| Lite-On Technology                     | 3         | 1.17%   |
| Alcor Micro                            | 3         | 1.17%   |
| USB Camera                             | 2         | 0.78%   |
| Importek                               | 2         | 0.78%   |
| USB Camera CS                          | 1         | 0.39%   |
| Tobii Technology AB                    | 1         | 0.39%   |
| Primax Electronics                     | 1         | 0.39%   |
| Logitech                               | 1         | 0.39%   |
| LG Electronics                         | 1         | 0.39%   |
| Goertek Electronics                    | 1         | 0.39%   |
| Bison Electronics                      | 1         | 0.39%   |
| ALi                                    | 1         | 0.39%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 13        | 5.08%   |
| Realtek Integrated_Webcam_HD                         | 9         | 3.52%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 8         | 3.13%   |
| IMC Networks Integrated Camera                       | 8         | 3.13%   |
| Acer HD Webcam                                       | 8         | 3.13%   |
| Microdia Integrated_Webcam_HD                        | 6         | 2.34%   |
| Chicony HP Truevision HD                             | 6         | 2.34%   |
| Chicony HD Webcam                                    | 6         | 2.34%   |
| Chicony HD User Facing                               | 6         | 2.34%   |
| Syntek Integrated Camera                             | 5         | 1.95%   |
| Chicony USB2.0 Camera                                | 5         | 1.95%   |
| Sunplus Integrated_Webcam_HD                         | 4         | 1.56%   |
| Samsung Galaxy A5 (MTP)                              | 4         | 1.56%   |
| Acer SunplusIT Integrated Camera                     | 4         | 1.56%   |
| Acer EasyCamera                                      | 4         | 1.56%   |
| Quanta HP TrueVision HD Camera                       | 3         | 1.17%   |
| Quanta HD User Facing                                | 3         | 1.17%   |
| Microdia Webcam Vitade AF                            | 3         | 1.17%   |
| Microdia Integrated Webcam                           | 3         | 1.17%   |
| IMC Networks HD Camera                               | 3         | 1.17%   |
| Chicony USB2.0 HD UVC WebCam                         | 3         | 1.17%   |
| Chicony HP HD Camera                                 | 3         | 1.17%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                      | 3         | 1.17%   |
| Apple FaceTime HD Camera                             | 3         | 1.17%   |
| Alcor Micro USB 2.0 Camera                           | 3         | 1.17%   |
| Acer Integrated Camera                               | 3         | 1.17%   |
| USB Camera USB Camera                                | 2         | 0.78%   |
| Sunplus Laptop_Integrated_Webcam_FHD                 | 2         | 0.78%   |
| Sunplus Laptop Integrated Webcam FHD                 | 2         | 0.78%   |
| Sunplus HD WebCam                                    | 2         | 0.78%   |
| Sonix USB2.0 HD UVC WebCam                           | 2         | 0.78%   |
| Realtek Integrated Webcam                            | 2         | 0.78%   |
| Quanta VGA WebCam                                    | 2         | 0.78%   |
| Microdia PC Microscope camera                        | 2         | 0.78%   |
| Microdia Laptop_Integrated_Webcam_HD                 | 2         | 0.78%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 2         | 0.78%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 2         | 0.78%   |
| Lite-On HP Wide Vision HD Camera                     | 2         | 0.78%   |
| IMC Networks VGA UVC WebCam                          | 2         | 0.78%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 2         | 0.78%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 19        | 38.78%  |
| Synaptics                  | 14        | 28.57%  |
| Shenzhen Goodix Technology | 6         | 12.24%  |
| Elan Microelectronics      | 4         | 8.16%   |
| Upek                       | 2         | 4.08%   |
| LighTuning Technology      | 2         | 4.08%   |
| AuthenTec                  | 2         | 4.08%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 5         | 10.2%   |
| Shenzhen Goodix  Fingerprint Device                                        | 5         | 10.2%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 6.12%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 6.12%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 6.12%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 6.12%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 3         | 6.12%   |
| Validity Sensors VFS491                                                    | 2         | 4.08%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 4.08%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 4.08%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 4.08%   |
| Elan ELAN:Fingerprint                                                      | 2         | 4.08%   |
| Elan ELAN:ARM-M4                                                           | 2         | 4.08%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 2.04%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 2.04%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.04%   |
| Synaptics  WBDI                                                            | 1         | 2.04%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 2.04%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 2.04%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 2.04%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 2.04%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 2.04%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 2.04%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 2.04%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 2.04%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 11        | 61.11%  |
| Alcor Micro | 5         | 27.78%  |
| OmniKey     | 1         | 5.56%   |
| O2 Micro    | 1         | 5.56%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 7         | 38.89%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 5         | 27.78%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 16.67%  |
| OmniKey CardMan Smart@Link                                                   | 1         | 5.56%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 5.56%   |
| Broadcom 5880                                                                | 1         | 5.56%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 171       | 58.97%  |
| 1     | 95        | 32.76%  |
| 2     | 22        | 7.59%   |
| 3     | 2         | 0.69%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 50        | 35.71%  |
| Graphics card         | 22        | 15.71%  |
| Net/wireless          | 17        | 12.14%  |
| Chipcard              | 17        | 12.14%  |
| Multimedia controller | 13        | 9.29%   |
| Camera                | 7         | 5%      |
| Storage               | 6         | 4.29%   |
| Network               | 3         | 2.14%   |
| Bluetooth             | 2         | 1.43%   |
| Net/ethernet          | 1         | 0.71%   |
| Modem                 | 1         | 0.71%   |
| Card reader           | 1         | 0.71%   |

