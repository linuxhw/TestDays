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

Total: 321

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [7615eb5b46](https://linux-hardware.org/?probe=7615eb5b46) | Jul 20, 2022 |
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
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [39351344b4](https://linux-hardware.org/?probe=39351344b4) | Jun 14, 2022 |
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
| Parrot 5.0   | 80        | 33.9%   |
| Parrot 4.11  | 63        | 26.69%  |
| Parrot 4.10  | 44        | 18.64%  |
| Parrot 4.8   | 15        | 6.36%   |
| Parrot 4.9   | 13        | 5.51%   |
| Parrot 4.7   | 10        | 4.24%   |
| Parrot 5.1   | 5         | 2.12%   |
| Parrot 4.6   | 2         | 0.85%   |
| Parrot 4.5   | 1         | 0.42%   |
| Parrot 4.4   | 1         | 0.42%   |
| Parrot 4.2.2 | 1         | 0.42%   |
| Parrot 3.10  | 1         | 0.42%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Parrot | 223       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.14.0-9parrot1-amd64    | 36        | 15%     |
| 5.16.0-12parrot1-amd64   | 33        | 13.75%  |
| 5.7.0-2parrot2-amd64     | 26        | 10.83%  |
| 5.10.0-6parrot1-amd64    | 25        | 10.42%  |
| 5.18.0-1parrot1-amd64    | 14        | 5.83%   |
| 5.10.0-8parrot1-amd64    | 14        | 5.83%   |
| 5.5.0-1parrot1-amd64     | 12        | 5%      |
| 5.4.0-4parrot1-amd64     | 11        | 4.58%   |
| 5.6.0-2parrot1-amd64     | 9         | 3.75%   |
| 5.14.0-2parrot1-amd64    | 8         | 3.33%   |
| 5.9.0-2parrot1-amd64     | 7         | 2.92%   |
| 5.15.0-15parrot1-amd64   | 5         | 2.08%   |
| 5.18.0-14parrot1-amd64   | 4         | 1.67%   |
| 5.4.0-2parrot1-amd64     | 3         | 1.25%   |
| 5.2.0-2parrot1-amd64     | 3         | 1.25%   |
| 5.10.0-5parrot1-amd64    | 3         | 1.25%   |
| 5.10.0-3parrot1-amd64    | 3         | 1.25%   |
| 4.19.0-parrot4-28t-amd64 | 3         | 1.25%   |
| 5.8.0-2parrot1-amd64     | 2         | 0.83%   |
| 5.8.0-1parrot1-amd64     | 2         | 0.83%   |
| 5.4.0-3parrot1-amd64     | 2         | 0.83%   |
| 4.18.0-parrot10-amd64    | 2         | 0.83%   |
| 5.7.0-rc6-galliumos      | 1         | 0.42%   |
| 5.4.0-2parrot1-686-pae   | 1         | 0.42%   |
| 5.4.0-1parrot1-amd64     | 1         | 0.42%   |
| 5.3.0-3parrot3-amd64     | 1         | 0.42%   |
| 5.3.0-3parrot3-686-pae   | 1         | 0.42%   |
| 5.3.0-1parrot1-amd64     | 1         | 0.42%   |
| 5.15.0-5parrot1-amd64    | 1         | 0.42%   |
| 5.10.0-kali6-amd64       | 1         | 0.42%   |
| 5.10.0-6parrot1-rt-amd64 | 1         | 0.42%   |
| 5.1.0-parrot1-3t-amd64   | 1         | 0.42%   |
| 4.19.0-parrot1-13t-amd64 | 1         | 0.42%   |
| 4.14.0-parrot7-amd64     | 1         | 0.42%   |
| Unknown                  | 1         | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 47        | 19.75%  |
| 5.14.0  | 43        | 18.07%  |
| 5.16.0  | 33        | 13.87%  |
| 5.7.0   | 27        | 11.34%  |
| 5.4.0   | 18        | 7.56%   |
| 5.18.0  | 17        | 7.14%   |
| 5.5.0   | 12        | 5.04%   |
| 5.6.0   | 9         | 3.78%   |
| 5.9.0   | 7         | 2.94%   |
| 5.15.0  | 6         | 2.52%   |
| 5.8.0   | 4         | 1.68%   |
| 4.19.0  | 4         | 1.68%   |
| 5.3.0   | 3         | 1.26%   |
| 5.2.0   | 3         | 1.26%   |
| 4.18.0  | 2         | 0.84%   |
| 5.1.0   | 1         | 0.42%   |
| 4.14.0  | 1         | 0.42%   |
| Unknown | 1         | 0.42%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 47        | 19.75%  |
| 5.14    | 43        | 18.07%  |
| 5.16    | 33        | 13.87%  |
| 5.7     | 27        | 11.34%  |
| 5.4     | 18        | 7.56%   |
| 5.18    | 17        | 7.14%   |
| 5.5     | 12        | 5.04%   |
| 5.6     | 9         | 3.78%   |
| 5.9     | 7         | 2.94%   |
| 5.15    | 6         | 2.52%   |
| 5.8     | 4         | 1.68%   |
| 4.19    | 4         | 1.68%   |
| 5.3     | 3         | 1.26%   |
| 5.2     | 3         | 1.26%   |
| 4.18    | 2         | 0.84%   |
| 5.1     | 1         | 0.42%   |
| 4.14    | 1         | 0.42%   |
| Unknown | 1         | 0.42%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 222       | 99.55%  |
| i686   | 1         | 0.45%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| MATE          | 144       | 63.16%  |
| KDE5          | 47        | 20.61%  |
| Unknown       | 17        | 7.46%   |
| KDE           | 13        | 5.7%    |
| XFCE          | 5         | 2.19%   |
| LXDE          | 1         | 0.44%   |
| GNOME Classic | 1         | 0.44%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 219       | 98.21%  |
| Tty     | 2         | 0.9%    |
| Wayland | 1         | 0.45%   |
| Unknown | 1         | 0.45%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 86        | 37.55%  |
| Unknown | 86        | 37.55%  |
| TDM     | 50        | 21.83%  |
| GDM     | 5         | 2.18%   |
| SDDM    | 2         | 0.87%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 116       | 51.79%  |
| en_GB   | 21        | 9.38%   |
| Unknown | 14        | 6.25%   |
| fr_FR   | 11        | 4.91%   |
| es_ES   | 8         | 3.57%   |
| ru_RU   | 7         | 3.13%   |
| pl_PL   | 7         | 3.13%   |
| pt_BR   | 6         | 2.68%   |
| de_DE   | 6         | 2.68%   |
| en_IN   | 4         | 1.79%   |
| en_AU   | 4         | 1.79%   |
| it_IT   | 2         | 0.89%   |
| tr_TR   | 1         | 0.45%   |
| pt_PT   | 1         | 0.45%   |
| nl_BE   | 1         | 0.45%   |
| id_ID   | 1         | 0.45%   |
| fr_CA   | 1         | 0.45%   |
| fi_FI   | 1         | 0.45%   |
| es_PE   | 1         | 0.45%   |
| es_MX   | 1         | 0.45%   |
| es_CO   | 1         | 0.45%   |
| es_CL   | 1         | 0.45%   |
| es_AR   | 1         | 0.45%   |
| en_ZA   | 1         | 0.45%   |
| en_NZ   | 1         | 0.45%   |
| en_NG   | 1         | 0.45%   |
| en_DK   | 1         | 0.45%   |
| en_CA   | 1         | 0.45%   |
| cs_CZ   | 1         | 0.45%   |
| C       | 1         | 0.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 141       | 62.39%  |
| EFI  | 85        | 37.61%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Btrfs   | 165       | 72.69%  |
| Ext4    | 41        | 18.06%  |
| Xfs     | 8         | 3.52%   |
| Unknown | 7         | 3.08%   |
| Overlay | 6         | 2.64%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 100       | 44.05%  |
| GPT     | 81        | 35.68%  |
| MBR     | 46        | 20.26%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 197       | 87.17%  |
| Yes       | 29        | 12.83%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 153       | 67.7%   |
| Yes       | 73        | 32.3%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 46        | 20.63%  |
| Lenovo                | 42        | 18.83%  |
| Dell                  | 37        | 16.59%  |
| ASUSTek Computer      | 20        | 8.97%   |
| Acer                  | 16        | 7.17%   |
| MSI                   | 9         | 4.04%   |
| Apple                 | 9         | 4.04%   |
| Toshiba               | 7         | 3.14%   |
| Samsung Electronics   | 4         | 1.79%   |
| Sony                  | 3         | 1.35%   |
| HUAWEI                | 3         | 1.35%   |
| Fujitsu               | 3         | 1.35%   |
| Razer                 | 2         | 0.9%    |
| Gateway               | 2         | 0.9%    |
| Alienware             | 2         | 0.9%    |
| Wortmann AG           | 1         | 0.45%   |
| Toxic                 | 1         | 0.45%   |
| Timi                  | 1         | 0.45%   |
| System76              | 1         | 0.45%   |
| Standard              | 1         | 0.45%   |
| Positivo Bahia - VAIO | 1         | 0.45%   |
| Positivo              | 1         | 0.45%   |
| Panasonic             | 1         | 0.45%   |
| Notebook              | 1         | 0.45%   |
| Metabox               | 1         | 0.45%   |
| Jumper                | 1         | 0.45%   |
| GPU Company           | 1         | 0.45%   |
| Google                | 1         | 0.45%   |
| eMachines             | 1         | 0.45%   |
| Eluktronics           | 1         | 0.45%   |
| Digma                 | 1         | 0.45%   |
| Chuwi                 | 1         | 0.45%   |
| Unknown               | 1         | 0.45%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                               | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| MSI Modern 15 A5M                                  | 3         | 1.35%   |
| Lenovo IdeaPad 3 15IIL05 81WE                      | 3         | 1.35%   |
| HP Notebook                                        | 3         | 1.35%   |
| HP EliteBook 8470p                                 | 3         | 1.35%   |
| Dell Latitude E6420                                | 3         | 1.35%   |
| Dell Inspiron MM061                                | 3         | 1.35%   |
| HP ProBook 650 G1                                  | 2         | 0.9%    |
| HP Pavilion dv6                                    | 2         | 0.9%    |
| HP Pavilion 15                                     | 2         | 0.9%    |
| Dell Latitude E7440                                | 2         | 0.9%    |
| Dell Latitude E6410                                | 2         | 0.9%    |
| ASUS Q524UQ                                        | 2         | 0.9%    |
| Apple MacBookPro8,1                                | 2         | 0.9%    |
| Acer Nitro AN515-54                                | 2         | 0.9%    |
| Unknown                                            | 2         | 0.9%    |
| Wortmann AG TERRA_MOBILE_1542                      | 1         | 0.45%   |
| Toxic GM7MQ8P                                      | 1         | 0.45%   |
| Toshiba Satellite-L845                             | 1         | 0.45%   |
| Toshiba Satellite L775D                            | 1         | 0.45%   |
| Toshiba Satellite L750                             | 1         | 0.45%   |
| Toshiba Satellite L655                             | 1         | 0.45%   |
| Toshiba Satellite L300D                            | 1         | 0.45%   |
| Toshiba Satellite Click 2 L35W-B                   | 1         | 0.45%   |
| Toshiba Satellite C75D-B                           | 1         | 0.45%   |
| Timi TM1613                                        | 1         | 0.45%   |
| System76 Gazelle                                   | 1         | 0.45%   |
| Sony VPCSB1C5E                                     | 1         | 0.45%   |
| Sony VPCCB15FG                                     | 1         | 0.45%   |
| Sony SVP1321L1EBI                                  | 1         | 0.45%   |
| Samsung RV415/RV515                                | 1         | 0.45%   |
| Samsung 550P5C/550P7C                              | 1         | 0.45%   |
| Samsung 350V5C/351V5C/3540VC/3440VC                | 1         | 0.45%   |
| Samsung 300E4C/300E5C/300E7C                       | 1         | 0.45%   |
| Razer Blade Stealth                                | 1         | 0.45%   |
| Razer Blade 15 Base Model (Early 2020) - RZ09-0328 | 1         | 0.45%   |
| Positivo Q232A                                     | 1         | 0.45%   |
| Positivo Bahia - VAIO VJFE51F11X-B0111H            | 1         | 0.45%   |
| Panasonic CF-31JBGNNDM                             | 1         | 0.45%   |
| Notebook W510TU                                    | 1         | 0.45%   |
| MSI GT60 2OC/2OD                                   | 1         | 0.45%   |
| MSI GE75 Raider 10SF                               | 1         | 0.45%   |
| MSI GE73 Raider RGB 8RE                            | 1         | 0.45%   |
| MSI GE63 Raider RGB 8RE                            | 1         | 0.45%   |
| MSI GE62 6QE                                       | 1         | 0.45%   |
| MSI Creator Z16 Hiroshi F A11UE                    | 1         | 0.45%   |
| Metabox Edge-Pro NS50MU                            | 1         | 0.45%   |
| Lenovo Z40-70 80E6                                 | 1         | 0.45%   |
| Lenovo Yoga S740-14IIL 81RS                        | 1         | 0.45%   |
| Lenovo Y520-15IKBN 80WK                            | 1         | 0.45%   |
| Lenovo Y50-70 Touch 20349                          | 1         | 0.45%   |
| Lenovo V330-15IKB 81AX                             | 1         | 0.45%   |
| Lenovo V110-15ISK 80TL                             | 1         | 0.45%   |
| Lenovo ThinkPad X260 20F5S5QT00                    | 1         | 0.45%   |
| Lenovo ThinkPad X250 20CL001GZA                    | 1         | 0.45%   |
| Lenovo ThinkPad X240 20AMS4MH00                    | 1         | 0.45%   |
| Lenovo ThinkPad X230 Tablet 343727U                | 1         | 0.45%   |
| Lenovo ThinkPad X230 2325N66                       | 1         | 0.45%   |
| Lenovo ThinkPad X220 42912XG                       | 1         | 0.45%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TK001GUS        | 1         | 0.45%   |
| Lenovo ThinkPad X1 Carbon 7th 20QD003AMC           | 1         | 0.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                    | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Lenovo ThinkPad                         | 20        | 8.97%   |
| Dell Latitude                           | 15        | 6.73%   |
| Dell Inspiron                           | 15        | 6.73%   |
| HP Pavilion                             | 14        | 6.28%   |
| Lenovo IdeaPad                          | 11        | 4.93%   |
| HP EliteBook                            | 9         | 4.04%   |
| HP Laptop                               | 7         | 3.14%   |
| Acer Aspire                             | 7         | 3.14%   |
| Toshiba Satellite                       | 6         | 2.69%   |
| HP ProBook                              | 5         | 2.24%   |
| ASUS VivoBook                           | 4         | 1.79%   |
| Acer Nitro                              | 4         | 1.79%   |
| MSI Modern                              | 3         | 1.35%   |
| HP Notebook                             | 3         | 1.35%   |
| Fujitsu LIFEBOOK                        | 3         | 1.35%   |
| Razer Blade                             | 2         | 0.9%    |
| HP ZBook                                | 2         | 0.9%    |
| HP 250                                  | 2         | 0.9%    |
| Dell Vostro                             | 2         | 0.9%    |
| Dell Precision                          | 2         | 0.9%    |
| ASUS TUF                                | 2         | 0.9%    |
| ASUS Q524UQ                             | 2         | 0.9%    |
| Apple MacBookPro8                       | 2         | 0.9%    |
| Apple MacBookPro11                      | 2         | 0.9%    |
| Acer Swift                              | 2         | 0.9%    |
| Acer Predator                           | 2         | 0.9%    |
| Unknown                                 | 2         | 0.9%    |
| Wortmann AG TERRA                       | 1         | 0.45%   |
| Toxic GM7MQ8P                           | 1         | 0.45%   |
| Toshiba Satellite-L845                  | 1         | 0.45%   |
| Timi TM1613                             | 1         | 0.45%   |
| System76 Gazelle                        | 1         | 0.45%   |
| Sony VPCSB1C5E                          | 1         | 0.45%   |
| Sony VPCCB15FG                          | 1         | 0.45%   |
| Sony SVP1321L1EBI                       | 1         | 0.45%   |
| Samsung RV415                           | 1         | 0.45%   |
| Samsung 550P5C                          | 1         | 0.45%   |
| Samsung 350V5C                          | 1         | 0.45%   |
| Samsung 300E4C                          | 1         | 0.45%   |
| Positivo Q232A                          | 1         | 0.45%   |
| Positivo Bahia - VAIO VJFE51F11X-B0111H | 1         | 0.45%   |
| Panasonic CF-31JBGNNDM                  | 1         | 0.45%   |
| Notebook W510TU                         | 1         | 0.45%   |
| MSI GT60                                | 1         | 0.45%   |
| MSI GE75                                | 1         | 0.45%   |
| MSI GE73                                | 1         | 0.45%   |
| MSI GE63                                | 1         | 0.45%   |
| MSI GE62                                | 1         | 0.45%   |
| MSI Creator                             | 1         | 0.45%   |
| Metabox Edge-Pro                        | 1         | 0.45%   |
| Lenovo Z40-70                           | 1         | 0.45%   |
| Lenovo Yoga                             | 1         | 0.45%   |
| Lenovo Y520-15IKBN                      | 1         | 0.45%   |
| Lenovo Y50-70                           | 1         | 0.45%   |
| Lenovo V330-15IKB                       | 1         | 0.45%   |
| Lenovo V110-15ISK                       | 1         | 0.45%   |
| Lenovo ThinkBook                        | 1         | 0.45%   |
| Lenovo Legion                           | 1         | 0.45%   |
| Lenovo G480                             | 1         | 0.45%   |
| Lenovo E41-25                           | 1         | 0.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 28        | 12.56%  |
| 2011 | 28        | 12.56%  |
| 2013 | 22        | 9.87%   |
| 2020 | 21        | 9.42%   |
| 2018 | 20        | 8.97%   |
| 2021 | 17        | 7.62%   |
| 2012 | 16        | 7.17%   |
| 2016 | 15        | 6.73%   |
| 2014 | 13        | 5.83%   |
| 2017 | 12        | 5.38%   |
| 2010 | 8         | 3.59%   |
| 2015 | 7         | 3.14%   |
| 2008 | 5         | 2.24%   |
| 2006 | 4         | 1.79%   |
| 2007 | 3         | 1.35%   |
| 2022 | 2         | 0.9%    |
| 2009 | 2         | 0.9%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 223       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 223       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 222       | 99.55%  |
| Yes  | 1         | 0.45%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 58        | 26.01%  |
| 8.01-16.0   | 49        | 21.97%  |
| 16.01-24.0  | 42        | 18.83%  |
| 3.01-4.0    | 41        | 18.39%  |
| 32.01-64.0  | 15        | 6.73%   |
| 1.01-2.0    | 7         | 3.14%   |
| 64.01-256.0 | 5         | 2.24%   |
| 24.01-32.0  | 3         | 1.35%   |
| 2.01-3.0    | 3         | 1.35%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 80        | 33.9%   |
| 2.01-3.0  | 77        | 32.63%  |
| 3.01-4.0  | 37        | 15.68%  |
| 4.01-8.0  | 26        | 11.02%  |
| 0.51-1.0  | 10        | 4.24%   |
| 8.01-16.0 | 5         | 2.12%   |
| 0.01-0.5  | 1         | 0.42%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 149       | 65.93%  |
| 2      | 68        | 30.09%  |
| 3      | 8         | 3.54%   |
| 0      | 1         | 0.44%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 143       | 64.13%  |
| Yes       | 80        | 35.87%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 182       | 81.25%  |
| No        | 42        | 18.75%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 220       | 98.65%  |
| No        | 3         | 1.35%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 181       | 79.74%  |
| No        | 46        | 20.26%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 72        | 32%     |
| Germany      | 13        | 5.78%   |
| Spain        | 11        | 4.89%   |
| France       | 11        | 4.89%   |
| UK           | 10        | 4.44%   |
| Russia       | 8         | 3.56%   |
| Brazil       | 8         | 3.56%   |
| Netherlands  | 7         | 3.11%   |
| India        | 6         | 2.67%   |
| Canada       | 5         | 2.22%   |
| Sweden       | 4         | 1.78%   |
| Kenya        | 4         | 1.78%   |
| Italy        | 4         | 1.78%   |
| Indonesia    | 4         | 1.78%   |
| Australia    | 4         | 1.78%   |
| South Africa | 3         | 1.33%   |
| Poland       | 3         | 1.33%   |
| Mexico       | 3         | 1.33%   |
| Iraq         | 3         | 1.33%   |
| Denmark      | 3         | 1.33%   |
| Turkey       | 2         | 0.89%   |
| Switzerland  | 2         | 0.89%   |
| Puerto Rico  | 2         | 0.89%   |
| Portugal     | 2         | 0.89%   |
| Nepal        | 2         | 0.89%   |
| Finland      | 2         | 0.89%   |
| Czechia      | 2         | 0.89%   |
| Bangladesh   | 2         | 0.89%   |
| Peru         | 1         | 0.44%   |
| Pakistan     | 1         | 0.44%   |
| Nigeria      | 1         | 0.44%   |
| New Zealand  | 1         | 0.44%   |
| Myanmar      | 1         | 0.44%   |
| Morocco      | 1         | 0.44%   |
| Latvia       | 1         | 0.44%   |
| Hungary      | 1         | 0.44%   |
| Greece       | 1         | 0.44%   |
| Georgia      | 1         | 0.44%   |
| Croatia      | 1         | 0.44%   |
| Costa Rica   | 1         | 0.44%   |
| Colombia     | 1         | 0.44%   |
| Chile        | 1         | 0.44%   |
| Bulgaria     | 1         | 0.44%   |
| Benin        | 1         | 0.44%   |
| Belgium      | 1         | 0.44%   |
| Belarus      | 1         | 0.44%   |
| Azerbaijan   | 1         | 0.44%   |
| Austria      | 1         | 0.44%   |
| Argentina    | 1         | 0.44%   |
| Algeria      | 1         | 0.44%   |
| Unknown      | 1         | 0.44%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Nairobi               | 4         | 1.69%   |
| Dallas                | 4         | 1.69%   |
| Seattle               | 3         | 1.27%   |
| Amsterdam             | 3         | 1.27%   |
| Zurich                | 2         | 0.85%   |
| Sydney                | 2         | 0.85%   |
| Stockholm             | 2         | 0.85%   |
| St Petersburg         | 2         | 0.85%   |
| Ruskin                | 2         | 0.85%   |
| Pretoria              | 2         | 0.85%   |
| Paris                 | 2         | 0.85%   |
| New York              | 2         | 0.85%   |
| Mostoles              | 2         | 0.85%   |
| Moscow                | 2         | 0.85%   |
| Melbourne             | 2         | 0.85%   |
| Madrid                | 2         | 0.85%   |
| London                | 2         | 0.85%   |
| Houston               | 2         | 0.85%   |
| Dublin                | 2         | 0.85%   |
| Dhaka                 | 2         | 0.85%   |
| Chicago               | 2         | 0.85%   |
| Camden                | 2         | 0.85%   |
| Berlin                | 2         | 0.85%   |
| Barcelona             | 2         | 0.85%   |
| Baghdad               | 2         | 0.85%   |
| Zagreb                | 1         | 0.42%   |
| West Jordan           | 1         | 0.42%   |
| Washington            | 1         | 0.42%   |
| Warsaw                | 1         | 0.42%   |
| Volgograd             | 1         | 0.42%   |
| Visalia               | 1         | 0.42%   |
| Villa Carlos Paz      | 1         | 0.42%   |
| Vila Nova de Gaia     | 1         | 0.42%   |
| Vienna                | 1         | 0.42%   |
| Veitsbronn            | 1         | 0.42%   |
| Västerås            | 1         | 0.42%   |
| Tulare                | 1         | 0.42%   |
| Ts'khinvali           | 1         | 0.42%   |
| Trivandrum            | 1         | 0.42%   |
| Tottenham             | 1         | 0.42%   |
| Toronto               | 1         | 0.42%   |
| Tempe                 | 1         | 0.42%   |
| Tangier               | 1         | 0.42%   |
| Tangerang             | 1         | 0.42%   |
| Tampere               | 1         | 0.42%   |
| Sviyazhsk             | 1         | 0.42%   |
| Surabaya              | 1         | 0.42%   |
| Sumaré               | 1         | 0.42%   |
| Spotsylvania          | 1         | 0.42%   |
| South Hamilton        | 1         | 0.42%   |
| Soro                  | 1         | 0.42%   |
| Skive                 | 1         | 0.42%   |
| Sinntal               | 1         | 0.42%   |
| Shelbyville           | 1         | 0.42%   |
| Secaucus              | 1         | 0.42%   |
| Scotts Valley         | 1         | 0.42%   |
| Saulkrasti            | 1         | 0.42%   |
| Sao Paulo             | 1         | 0.42%   |
| Sao Bernardo do Campo | 1         | 0.42%   |
| Santo André          | 1         | 0.42%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 43        | 51     | 14.93%  |
| Toshiba             | 39        | 43     | 13.54%  |
| WDC                 | 35        | 43     | 12.15%  |
| Unknown             | 23        | 25     | 7.99%   |
| Seagate             | 23        | 23     | 7.99%   |
| Kingston            | 18        | 18     | 6.25%   |
| SanDisk             | 12        | 14     | 4.17%   |
| Hitachi             | 11        | 13     | 3.82%   |
| Crucial             | 10        | 15     | 3.47%   |
| Micron Technology   | 8         | 8      | 2.78%   |
| HGST                | 7         | 9      | 2.43%   |
| SK hynix            | 6         | 6      | 2.08%   |
| China               | 6         | 6      | 2.08%   |
| Intel               | 5         | 9      | 1.74%   |
| Apple               | 5         | 5      | 1.74%   |
| A-DATA Technology   | 5         | 5      | 1.74%   |
| LITEON              | 3         | 3      | 1.04%   |
| Team                | 2         | 2      | 0.69%   |
| PNY                 | 2         | 2      | 0.69%   |
| KIOXIA              | 2         | 2      | 0.69%   |
| HUAWEI              | 2         | 2      | 0.69%   |
| YMTC                | 1         | 1      | 0.35%   |
| W800SH              | 1         | 1      | 0.35%   |
| Transcend           | 1         | 1      | 0.35%   |
| Silicon Motion      | 1         | 1      | 0.35%   |
| S3+                 | 1         | 1      | 0.35%   |
| RZX                 | 1         | 1      | 0.35%   |
| Phison              | 1         | 1      | 0.35%   |
| Patriot             | 1         | 1      | 0.35%   |
| Netac               | 1         | 1      | 0.35%   |
| LITEONIT            | 1         | 1      | 0.35%   |
| Lexar               | 1         | 1      | 0.35%   |
| KingSpec            | 1         | 2      | 0.35%   |
| KingFast            | 1         | 2      | 0.35%   |
| Intenso             | 1         | 2      | 0.35%   |
| Hikvision           | 1         | 1      | 0.35%   |
| Fujitsu             | 1         | 1      | 0.35%   |
| Corsair             | 1         | 2      | 0.35%   |
| BR                  | 1         | 1      | 0.35%   |
| BHT                 | 1         | 1      | 0.35%   |
| ASMT                | 1         | 1      | 0.35%   |
| ASMedia             | 1         | 1      | 0.35%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Toshiba MQ04ABF100 1TB                  | 10        | 3.31%   |
| Toshiba MQ01ABF050 500GB                | 7         | 2.32%   |
| Toshiba MQ01ABD100 1TB                  | 5         | 1.66%   |
| Kingston NVMe SSD Drive 512GB           | 5         | 1.66%   |
| Unknown MMC Card  32GB                  | 4         | 1.32%   |
| Samsung SSD 860 EVO 500GB               | 4         | 1.32%   |
| WDC WD10SPZX-75Z10T2 1TB                | 3         | 0.99%   |
| Unknown SD/MMC/MS PRO 128GB             | 3         | 0.99%   |
| Toshiba MQ01ABD075 752GB                | 3         | 0.99%   |
| Seagate ST2000LM003 HN-M201RAD 2TB      | 3         | 0.99%   |
| Seagate ST1000LM035-1RK172 1TB          | 3         | 0.99%   |
| SanDisk SSD PLUS 1000GB                 | 3         | 0.99%   |
| Samsung SSD 850 EVO 250GB               | 3         | 0.99%   |
| HGST HTS721010A9E630 1TB                | 3         | 0.99%   |
| HGST HTS541010A9E680 1TB                | 3         | 0.99%   |
| WDC WD5000LPCX-24C6HT0 500GB            | 2         | 0.66%   |
| WDC WD10SPZX-60Z10T0 1TB                | 2         | 0.66%   |
| Team TM8PS7512G 512GB SSD               | 2         | 0.66%   |
| Seagate ST9250315AS 250GB               | 2         | 0.66%   |
| Seagate ST500LT012-1DG142 500GB         | 2         | 0.66%   |
| Seagate ST320LT007-9ZV142 320GB         | 2         | 0.66%   |
| SanDisk NVMe SSD Drive 256GB            | 2         | 0.66%   |
| SanDisk NVMe SSD Drive 1TB              | 2         | 0.66%   |
| Samsung SSD 980 1TB                     | 2         | 0.66%   |
| Samsung SM963 2.5" NVMe PCIe SSD 1024GB | 2         | 0.66%   |
| Samsung HM500JI 500GB                   | 2         | 0.66%   |
| Kingston SV300S37A240G 240GB SSD        | 2         | 0.66%   |
| Kingston SV300S37A120G 120GB SSD        | 2         | 0.66%   |
| Kingston SA400S37240G 240GB SSD         | 2         | 0.66%   |
| Crucial CT500MX500SSD1 500GB            | 2         | 0.66%   |
| Crucial CT1000MX500SSD1 1TB             | 2         | 0.66%   |
| China SATA SSD 120GB                    | 2         | 0.66%   |
| Apple SSD SM0256G 256GB                 | 2         | 0.66%   |
| YMTC PC005 512GB                        | 1         | 0.33%   |
| WDC WDS500G2B0A-00SM50 500GB SSD        | 1         | 0.33%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD        | 1         | 0.33%   |
| WDC WDS120G2G0A-00JH30 120GB SSD        | 1         | 0.33%   |
| WDC WDS100T2B0C-00PXH0 1TB              | 1         | 0.33%   |
| WDC WDS100T2B0B-00YS70 1TB SSD          | 1         | 0.33%   |
| WDC WDBNCE2500PNC 250GB SSD             | 1         | 0.33%   |
| WDC WD800BEVS-22RST0 80GB               | 1         | 0.33%   |
| WDC WD7500BPVX-22JC3T0 752GB            | 1         | 0.33%   |
| WDC WD6400BPVT-75HXZT1 640GB            | 1         | 0.33%   |
| WDC WD5000LPVT-16G33T0 500GB            | 1         | 0.33%   |
| WDC WD5000LPLX-08ZNTT0 500GB            | 1         | 0.33%   |
| WDC WD5000LPCX-60VHAT1 500GB            | 1         | 0.33%   |
| WDC WD5000LPCX-24VHAT0 500GB            | 1         | 0.33%   |
| WDC WD3200LPVX-00V0TT0 320GB            | 1         | 0.33%   |
| WDC WD3200BPVT-22JJ5T0 320GB            | 1         | 0.33%   |
| WDC WD3200BPVT-00JJ5T0 320GB            | 1         | 0.33%   |
| WDC WD3200BPVT-00HXZT1 320GB            | 1         | 0.33%   |
| WDC WD3200BEVT-60A23T0 320GB            | 1         | 0.33%   |
| WDC WD2500BPVT-00JJ5T0 250GB            | 1         | 0.33%   |
| WDC WD2500BEVT-22A23T0 250GB            | 1         | 0.33%   |
| WDC WD10SPZX-24Z10 1TB                  | 1         | 0.33%   |
| WDC WD10SPZX-21Z 1TB                    | 1         | 0.33%   |
| WDC WD10SPZX-17Z10T1 1TB                | 1         | 0.33%   |
| WDC WD10SPZX-08Z10 1TB                  | 1         | 0.33%   |
| WDC WD10SPCX-24HWST1 1TB                | 1         | 0.33%   |
| WDC WD10S21X-24R1BT0-SSHD-8GB           | 1         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 33        | 36     | 30%     |
| WDC                 | 27        | 31     | 24.55%  |
| Seagate             | 23        | 23     | 20.91%  |
| Hitachi             | 11        | 13     | 10%     |
| HGST                | 7         | 9      | 6.36%   |
| Samsung Electronics | 4         | 4      | 3.64%   |
| Unknown             | 3         | 4      | 2.73%   |
| Fujitsu             | 1         | 1      | 0.91%   |
| ASMedia             | 1         | 1      | 0.91%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 19        | 22     | 20.43%  |
| Kingston            | 9         | 9      | 9.68%   |
| Crucial             | 9         | 14     | 9.68%   |
| SanDisk             | 6         | 7      | 6.45%   |
| China               | 6         | 6      | 6.45%   |
| WDC                 | 5         | 6      | 5.38%   |
| Toshiba             | 4         | 5      | 4.3%    |
| Micron Technology   | 4         | 4      | 4.3%    |
| Apple               | 4         | 4      | 4.3%    |
| LITEON              | 3         | 3      | 3.23%   |
| Team                | 2         | 2      | 2.15%   |
| PNY                 | 2         | 2      | 2.15%   |
| Intel               | 2         | 2      | 2.15%   |
| A-DATA Technology   | 2         | 2      | 2.15%   |
| W800SH              | 1         | 1      | 1.08%   |
| Unknown             | 1         | 1      | 1.08%   |
| Transcend           | 1         | 1      | 1.08%   |
| SK hynix            | 1         | 1      | 1.08%   |
| S3+                 | 1         | 1      | 1.08%   |
| RZX                 | 1         | 1      | 1.08%   |
| Patriot             | 1         | 1      | 1.08%   |
| Netac               | 1         | 1      | 1.08%   |
| LITEONIT            | 1         | 1      | 1.08%   |
| KingSpec            | 1         | 2      | 1.08%   |
| KingFast            | 1         | 1      | 1.08%   |
| Intenso             | 1         | 2      | 1.08%   |
| Corsair             | 1         | 2      | 1.08%   |
| BR                  | 1         | 1      | 1.08%   |
| BHT                 | 1         | 1      | 1.08%   |
| ASMT                | 1         | 1      | 1.08%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 107       | 122    | 38.63%  |
| SSD     | 85        | 107    | 30.69%  |
| NVMe    | 63        | 76     | 22.74%  |
| MMC     | 18        | 20     | 6.5%    |
| Unknown | 4         | 4      | 1.44%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 171       | 217    | 64.29%  |
| NVMe | 63        | 76     | 23.68%  |
| MMC  | 18        | 20     | 6.77%   |
| SAS  | 14        | 16     | 5.26%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 119       | 150    | 62.3%   |
| 0.51-1.0   | 65        | 71     | 34.03%  |
| 1.01-2.0   | 7         | 8      | 3.66%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 60        | 26.43%  |
| 101-250        | 51        | 22.47%  |
| 501-1000       | 37        | 16.3%   |
| 1001-2000      | 25        | 11.01%  |
| Unknown        | 19        | 8.37%   |
| 21-50          | 12        | 5.29%   |
| 51-100         | 11        | 4.85%   |
| 1-20           | 5         | 2.2%    |
| 2001-3000      | 4         | 1.76%   |
| More than 3000 | 3         | 1.32%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 21-50          | 69        | 29.74%  |
| 51-100         | 44        | 18.97%  |
| 1-20           | 39        | 16.81%  |
| 101-250        | 26        | 11.21%  |
| 251-500        | 25        | 10.78%  |
| Unknown        | 19        | 8.19%   |
| 501-1000       | 7         | 3.02%   |
| More than 3000 | 1         | 0.43%   |
| 1001-2000      | 1         | 0.43%   |
| 0              | 1         | 0.43%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Samsung Electronics HM500JI 500GB                   | 2         | 2      | 9.09%   |
| WDC WD3200BPVT-00JJ5T0 320GB                        | 1         | 1      | 4.55%   |
| WDC WD2500BEVT-22A23T0 250GB                        | 1         | 1      | 4.55%   |
| Toshiba MQ01ABD100 1TB                              | 1         | 1      | 4.55%   |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 4.55%   |
| Toshiba MK3265GSXF 320GB                            | 1         | 1      | 4.55%   |
| Seagate ST320LM001 HN-M320MBB 320GB                 | 1         | 1      | 4.55%   |
| Seagate ST2000LM007-1R8174 2TB                      | 1         | 1      | 4.55%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1      | 4.55%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD    | 1         | 1      | 4.55%   |
| Samsung Electronics HM160HI 160GB                   | 1         | 1      | 4.55%   |
| Micron Technology MTFDDAK128MAY-1AH1ZABHA 128GB SSD | 1         | 1      | 4.55%   |
| LITEON CV8-8E128-HP 128GB SSD                       | 1         | 1      | 4.55%   |
| Intel HBRPEKNX0202AHO 32GB                          | 1         | 1      | 4.55%   |
| Hitachi HTS725050A9A360 500GB                       | 1         | 1      | 4.55%   |
| Hitachi HTS725032A9A364 320GB                       | 1         | 1      | 4.55%   |
| Hitachi HTS542512K9SA00 120GB                       | 1         | 1      | 4.55%   |
| HGST HTS721010A9E630 1TB                            | 1         | 1      | 4.55%   |
| Fujitsu MHY2160BH 160GB                             | 1         | 1      | 4.55%   |
| A-DATA Technology SX6000LNP 1TB                     | 1         | 1      | 4.55%   |
| A-DATA Technology SU700 120GB SSD                   | 1         | 1      | 4.55%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 4      | 18.18%  |
| Toshiba             | 3         | 3      | 13.64%  |
| Seagate             | 3         | 3      | 13.64%  |
| Hitachi             | 3         | 3      | 13.64%  |
| WDC                 | 2         | 2      | 9.09%   |
| A-DATA Technology   | 2         | 2      | 9.09%   |
| Micron Technology   | 1         | 1      | 4.55%   |
| LITEON              | 1         | 1      | 4.55%   |
| Intel               | 1         | 1      | 4.55%   |
| HGST                | 1         | 1      | 4.55%   |
| Fujitsu             | 1         | 1      | 4.55%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 3         | 3      | 18.75%  |
| Seagate             | 3         | 3      | 18.75%  |
| Samsung Electronics | 3         | 3      | 18.75%  |
| Hitachi             | 3         | 3      | 18.75%  |
| WDC                 | 2         | 2      | 12.5%   |
| HGST                | 1         | 1      | 6.25%   |
| Fujitsu             | 1         | 1      | 6.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 16        | 16     | 72.73%  |
| SSD  | 4         | 4      | 18.18%  |
| NVMe | 2         | 2      | 9.09%   |

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
| Detected | 114       | 169    | 46.15%  |
| Works    | 112       | 138    | 45.34%  |
| Malfunc  | 21        | 22     | 8.5%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 168       | 64.12%  |
| Samsung Electronics          | 24        | 9.16%   |
| AMD                          | 24        | 9.16%   |
| SanDisk                      | 11        | 4.2%    |
| Kingston Technology Company  | 9         | 3.44%   |
| SK hynix                     | 5         | 1.91%   |
| Micron Technology            | 4         | 1.53%   |
| Silicon Motion               | 3         | 1.15%   |
| Nvidia                       | 3         | 1.15%   |
| Toshiba America Info Systems | 2         | 0.76%   |
| KIOXIA                       | 2         | 0.76%   |
| ADATA Technology             | 2         | 0.76%   |
| Yangtze Memory Technologies  | 1         | 0.38%   |
| Realtek Semiconductor        | 1         | 0.38%   |
| Phison Electronics           | 1         | 0.38%   |
| Micron/Crucial Technology    | 1         | 0.38%   |
| Apple                        | 1         | 0.38%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 20        | 6.97%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 20        | 6.97%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 19        | 6.62%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 17        | 5.92%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 16        | 5.57%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 13        | 4.53%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 10        | 3.48%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 10        | 3.48%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 8         | 2.79%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 7         | 2.44%   |
| SanDisk WD Blue SN550 NVMe SSD                                                         | 5         | 1.74%   |
| Samsung NVMe SSD Controller 980                                                        | 5         | 1.74%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 5         | 1.74%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 5         | 1.74%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 5         | 1.74%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 5         | 1.74%   |
| Micron Non-Volatile memory controller                                                  | 4         | 1.39%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 4         | 1.39%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 4         | 1.39%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 4         | 1.39%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 4         | 1.39%   |
| SK hynix BC511                                                                         | 3         | 1.05%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 3         | 1.05%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 3         | 1.05%   |
| Kingston Company Company Non-Volatile memory controller                                | 3         | 1.05%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 3         | 1.05%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 3         | 1.05%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 3         | 1.05%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 3         | 1.05%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 3         | 1.05%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 3         | 1.05%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 3         | 1.05%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller       | 2         | 0.7%    |
| SK hynix Gold P31 SSD                                                                  | 2         | 0.7%    |
| SanDisk Non-Volatile memory controller                                                 | 2         | 0.7%    |
| Samsung NVMe SSD Controller SM951/PM951                                                | 2         | 0.7%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 2         | 0.7%    |
| Samsung Electronics SATA controller                                                    | 2         | 0.7%    |
| KIOXIA NVMe SSD Controller BG4                                                         | 2         | 0.7%    |
| Kingston Company U-SNS8154P3 NVMe SSD                                                  | 2         | 0.7%    |
| Kingston Company OM3PDP3 NVMe SSD                                                      | 2         | 0.7%    |
| Kingston Company A2000 NVMe SSD                                                        | 2         | 0.7%    |
| Intel Tiger Lake-LP SATA Controller                                                    | 2         | 0.7%    |
| Intel Comet Lake SATA AHCI Controller                                                  | 2         | 0.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 2         | 0.7%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 2         | 0.7%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                                   | 2         | 0.7%    |
| AMD FCH SATA Controller [IDE mode]                                                     | 2         | 0.7%    |
| Yangtze Memory Non-Volatile memory controller                                          | 1         | 0.35%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                        | 1         | 0.35%   |
| SanDisk PC SN520 NVMe SSD                                                              | 1         | 0.35%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 1         | 0.35%   |
| Samsung Apple PCIe SSD                                                                 | 1         | 0.35%   |
| Realtek RTS5763DL NVMe SSD Controller                                                  | 1         | 0.35%   |
| Phison E12 NVMe Controller                                                             | 1         | 0.35%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                               | 1         | 0.35%   |
| Nvidia MCP89 SATA Controller                                                           | 1         | 0.35%   |
| Nvidia MCP79 AHCI Controller                                                           | 1         | 0.35%   |
| Micron/Crucial NVMe Controller                                                         | 1         | 0.35%   |
| Intel SSD 660P Series                                                                  | 1         | 0.35%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 156       | 57.78%  |
| NVMe | 63        | 23.33%  |
| RAID | 28        | 10.37%  |
| IDE  | 23        | 8.52%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 191       | 85.65%  |
| AMD    | 32        | 14.35%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz             | 8         | 3.59%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 6         | 2.69%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 6         | 2.69%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 1.79%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 1.79%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 1.79%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 4         | 1.79%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 4         | 1.79%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 4         | 1.79%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 1.35%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 3         | 1.35%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 3         | 1.35%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 1.35%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 1.35%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 3         | 1.35%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 3         | 1.35%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 3         | 1.35%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 3         | 1.35%   |
| Intel Core 2 CPU T5600 @ 1.83GHz              | 3         | 1.35%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 3         | 1.35%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 3         | 1.35%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 1.35%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 3         | 1.35%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 2         | 0.9%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 0.9%    |
| Intel Core i7-4600U CPU @ 2.10GHz             | 2         | 0.9%    |
| Intel Core i7-4510U CPU @ 2.00GHz             | 2         | 0.9%    |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 0.9%    |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 2         | 0.9%    |
| Intel Core i7-2620M CPU @ 2.70GHz             | 2         | 0.9%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 0.9%    |
| Intel Core i5-8300H CPU @ 2.30GHz             | 2         | 0.9%    |
| Intel Core i5-5300U CPU @ 2.30GHz             | 2         | 0.9%    |
| Intel Core i5-4310U CPU @ 2.00GHz             | 2         | 0.9%    |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 0.9%    |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 0.9%    |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 0.9%    |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 0.9%    |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz          | 2         | 0.9%    |
| Intel Celeron J4125 CPU @ 2.00GHz             | 2         | 0.9%    |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 2         | 0.9%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 0.9%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 0.9%    |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 0.9%    |
| AMD E1-2500 APU with Radeon HD Graphics       | 2         | 0.9%    |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 0.45%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.45%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 0.45%   |
| Intel Pentium CPU N3530 @ 2.16GHz             | 1         | 0.45%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 1         | 0.45%   |
| Intel Pentium CPU 4415U @ 2.30GHz             | 1         | 0.45%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 0.45%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 1         | 0.45%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.45%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 0.45%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 0.45%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 1         | 0.45%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 0.45%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 1         | 0.45%   |
| Intel Core i7-4770HQ CPU @ 2.20GHz            | 1         | 0.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 66        | 29.6%   |
| Intel Core i7           | 61        | 27.35%  |
| Intel Core i3           | 19        | 8.52%   |
| Other                   | 15        | 6.73%   |
| Intel Celeron           | 11        | 4.93%   |
| AMD Ryzen 7             | 9         | 4.04%   |
| Intel Core 2 Duo        | 7         | 3.14%   |
| AMD Ryzen 5             | 5         | 2.24%   |
| AMD A6                  | 5         | 2.24%   |
| Intel Core 2            | 4         | 1.79%   |
| Intel Pentium           | 3         | 1.35%   |
| AMD E1                  | 3         | 1.35%   |
| Intel Pentium Silver    | 2         | 0.9%    |
| Intel Atom              | 2         | 0.9%    |
| AMD Ryzen 3             | 2         | 0.9%    |
| AMD A4                  | 2         | 0.9%    |
| Intel Pentium Dual-Core | 1         | 0.45%   |
| Intel Core 2 Quad       | 1         | 0.45%   |
| Intel Core 2 Extreme    | 1         | 0.45%   |
| AMD E2                  | 1         | 0.45%   |
| AMD E                   | 1         | 0.45%   |
| AMD C-50                | 1         | 0.45%   |
| AMD Athlon X2           | 1         | 0.45%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 122       | 54.71%  |
| 4      | 68        | 30.49%  |
| 6      | 17        | 7.62%   |
| 8      | 12        | 5.38%   |
| 1      | 2         | 0.9%    |
| 14     | 1         | 0.45%   |
| 12     | 1         | 0.45%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 223       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 171       | 76.68%  |
| 1      | 52        | 23.32%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 218       | 97.76%  |
| Unknown        | 5         | 2.24%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 103       | 44.98%  |
| 0x206a7    | 17        | 7.42%   |
| 0x306a9    | 10        | 4.37%   |
| 0x806ec    | 8         | 3.49%   |
| 0x906ea    | 7         | 3.06%   |
| 0x806e9    | 7         | 3.06%   |
| 0xa0652    | 5         | 2.18%   |
| 0x806ea    | 5         | 2.18%   |
| 0x406e3    | 5         | 2.18%   |
| 0x806c1    | 4         | 1.75%   |
| 0x706e5    | 4         | 1.75%   |
| 0x6f6      | 4         | 1.75%   |
| 0x40651    | 4         | 1.75%   |
| 0x306c3    | 4         | 1.75%   |
| 0x1067a    | 4         | 1.75%   |
| 0x706a8    | 3         | 1.31%   |
| 0x08600106 | 3         | 1.31%   |
| 0x07030105 | 3         | 1.31%   |
| 0x906e9    | 2         | 0.87%   |
| 0x906a3    | 2         | 0.87%   |
| 0x806d1    | 2         | 0.87%   |
| 0x406c4    | 2         | 0.87%   |
| 0x306d4    | 2         | 0.87%   |
| 0x08108109 | 2         | 0.87%   |
| 0x06006705 | 2         | 0.87%   |
| 0x03000027 | 2         | 0.87%   |
| 0x906ed    | 1         | 0.44%   |
| 0x806eb    | 1         | 0.44%   |
| 0x806c2    | 1         | 0.44%   |
| 0x706a1    | 1         | 0.44%   |
| 0x6fd      | 1         | 0.44%   |
| 0x506e3    | 1         | 0.44%   |
| 0x506c9    | 1         | 0.44%   |
| 0x40661    | 1         | 0.44%   |
| 0x20655    | 1         | 0.44%   |
| 0x08108102 | 1         | 0.44%   |
| 0x0810100b | 1         | 0.44%   |
| 0x06001119 | 1         | 0.44%   |
| 0x05000029 | 1         | 0.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 46        | 20.63%  |
| SandyBridge      | 26        | 11.66%  |
| IvyBridge        | 19        | 8.52%   |
| Haswell          | 19        | 8.52%   |
| Skylake          | 13        | 5.83%   |
| Broadwell        | 10        | 4.48%   |
| Penryn           | 9         | 4.04%   |
| Silvermont       | 8         | 3.59%   |
| TigerLake        | 7         | 3.14%   |
| IceLake          | 7         | 3.14%   |
| CometLake        | 7         | 3.14%   |
| Core             | 6         | 2.69%   |
| Unknown          | 6         | 2.69%   |
| Zen+             | 5         | 2.24%   |
| Goldmont plus    | 5         | 2.24%   |
| Zen 2            | 4         | 1.79%   |
| Westmere         | 4         | 1.79%   |
| Excavator        | 4         | 1.79%   |
| Puma             | 3         | 1.35%   |
| Jaguar           | 3         | 1.35%   |
| Zen 3            | 2         | 0.9%    |
| K10 Llano        | 2         | 0.9%    |
| Bobcat           | 2         | 0.9%    |
| Alderlake Hybrid | 2         | 0.9%    |
| Zen              | 1         | 0.45%   |
| Piledriver       | 1         | 0.45%   |
| K8 & K10 hybrid  | 1         | 0.45%   |
| Goldmont         | 1         | 0.45%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 176       | 59.06%  |
| Nvidia | 70        | 23.49%  |
| AMD    | 52        | 17.45%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 23        | 7.57%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 17        | 5.59%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 13        | 4.28%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 11        | 3.62%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 10        | 3.29%   |
| Intel UHD Graphics 620                                                                   | 9         | 2.96%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 2.96%   |
| Intel HD Graphics 5500                                                                   | 9         | 2.96%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 7         | 2.3%    |
| Intel HD Graphics 620                                                                    | 7         | 2.3%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 7         | 2.3%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 1.64%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 1.64%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 5         | 1.64%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 1.64%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 1.32%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 4         | 1.32%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 1.32%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 1.32%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 1.32%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 1.32%   |
| AMD Renoir                                                                               | 4         | 1.32%   |
| AMD Lucienne                                                                             | 4         | 1.32%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 3         | 0.99%   |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 0.99%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 3         | 0.99%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 0.99%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 0.99%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 0.99%   |
| Intel HD Graphics 530                                                                    | 3         | 0.99%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 0.99%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 0.99%   |
| AMD RV515/M54 [Mobility Radeon X1400]                                                    | 3         | 0.99%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.66%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.66%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 2         | 0.66%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.66%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.66%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 2         | 0.66%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 2         | 0.66%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.66%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 2         | 0.66%   |
| Nvidia GK107M [GeForce GT 650M]                                                          | 2         | 0.66%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 2         | 0.66%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 0.66%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 2         | 0.66%   |
| Intel HD Graphics 630                                                                    | 2         | 0.66%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 0.66%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 2         | 0.66%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                            | 2         | 0.66%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 2         | 0.66%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 0.66%   |
| AMD Sumo [Radeon HD 6520G]                                                               | 2         | 0.66%   |
| AMD Kabini [Radeon HD 8240 / R3 Series]                                                  | 2         | 0.66%   |
| AMD Cezanne                                                                              | 2         | 0.66%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.33%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.33%   |
| Nvidia TU117M                                                                            | 1         | 0.33%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 1         | 0.33%   |
| Nvidia TU104M [GeForce RTX 2080 SUPER Mobile / Max-Q]                                    | 1         | 0.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 104       | 46.64%  |
| Intel + Nvidia | 59        | 26.46%  |
| 1 x AMD        | 35        | 15.7%   |
| Intel + AMD    | 13        | 5.83%   |
| 1 x Nvidia     | 7         | 3.14%   |
| AMD + Nvidia   | 3         | 1.35%   |
| 2 x Nvidia     | 1         | 0.45%   |
| 2 x AMD        | 1         | 0.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 203       | 91.03%  |
| Proprietary | 19        | 8.52%   |
| Unknown     | 1         | 0.45%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 175       | 77.78%  |
| 1.01-2.0   | 17        | 7.56%   |
| 0.01-0.5   | 13        | 5.78%   |
| 0.51-1.0   | 9         | 4%      |
| 3.01-4.0   | 7         | 3.11%   |
| 5.01-6.0   | 2         | 0.89%   |
| 7.01-8.0   | 1         | 0.44%   |
| 2.01-3.0   | 1         | 0.44%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 55        | 22.36%  |
| LG Display              | 44        | 17.89%  |
| BOE                     | 37        | 15.04%  |
| Chimei Innolux          | 33        | 13.41%  |
| Samsung Electronics     | 23        | 9.35%   |
| Apple                   | 10        | 4.07%   |
| Chi Mei Optoelectronics | 7         | 2.85%   |
| Lenovo                  | 4         | 1.63%   |
| Dell                    | 4         | 1.63%   |
| Sharp                   | 3         | 1.22%   |
| PANDA                   | 3         | 1.22%   |
| Acer                    | 3         | 1.22%   |
| Sceptre Tech            | 2         | 0.81%   |
| Hewlett-Packard         | 2         | 0.81%   |
| Ancor Communications    | 2         | 0.81%   |
| Unknown (AAA)           | 1         | 0.41%   |
| STA                     | 1         | 0.41%   |
| SANYO                   | 1         | 0.41%   |
| Philips                 | 1         | 0.41%   |
| Panasonic               | 1         | 0.41%   |
| ONN                     | 1         | 0.41%   |
| NEC Computers           | 1         | 0.41%   |
| Kogan                   | 1         | 0.41%   |
| InfoVision              | 1         | 0.41%   |
| Goldstar                | 1         | 0.41%   |
| Eizo                    | 1         | 0.41%   |
| CSO                     | 1         | 0.41%   |
| BenQ                    | 1         | 0.41%   |
| AOC                     | 1         | 0.41%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch           | 3         | 1.22%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch        | 3         | 1.22%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch         | 3         | 1.22%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch         | 3         | 1.22%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch   | 2         | 0.81%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch   | 2         | 0.81%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch   | 2         | 0.81%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                | 2         | 0.81%   |
| LG Display LCD Monitor LGD0390 1600x900 382x215mm 17.3-inch            | 2         | 0.81%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch            | 2         | 0.81%   |
| LG Display LCD Monitor LGD01E9 1920x1080 345x194mm 15.6-inch           | 2         | 0.81%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch       | 2         | 0.81%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 2         | 0.81%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch        | 2         | 0.81%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch        | 2         | 0.81%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                  | 2         | 0.81%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch         | 2         | 0.81%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch          | 2         | 0.81%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch          | 2         | 0.81%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch          | 2         | 0.81%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 340x190mm 15.3-inch          | 2         | 0.81%   |
| Unknown (AAA) LCDTV AAA0042 1360x768 890x500mm 40.2-inch               | 1         | 0.41%   |
| STA XR140EA1T STA0450 1366x768 310x174mm 14.0-inch                     | 1         | 0.41%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch                | 1         | 0.41%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch                | 1         | 0.41%   |
| Sharp LCD Monitor SHP143A 3840x2160 346x194mm 15.6-inch                | 1         | 0.41%   |
| Sceptre Tech Sceptre F24 SPT09AB 1920x1080 522x293mm 23.6-inch         | 1         | 0.41%   |
| Sceptre Tech Sceptre B30 SPT0BC2 2560x1080 690x291mm 29.5-inch         | 1         | 0.41%   |
| SANYO LCD SAN0B51 1920x540                                             | 1         | 0.41%   |
| Samsung Electronics SyncMaster SAM0589 1920x1080 521x293mm 23.5-inch   | 1         | 0.41%   |
| Samsung Electronics SMT24A550 SAM07B5 1920x1080 531x299mm 24.0-inch    | 1         | 0.41%   |
| Samsung Electronics S27E510 SAM0C5F 1920x1080 600x340mm 27.2-inch      | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch  | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch   | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch   | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC4145 1366x768 309x174mm 14.0-inch   | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC3942 1366x768 309x174mm 14.0-inch   | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 367x230mm 17.1-inch   | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC345A 1366x768 309x174mm 14.0-inch   | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC314A 1920x1080 408x230mm 18.4-inch  | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 353x198mm 15.9-inch   | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 277x156mm 12.5-inch   | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SDC864D 1920x1080 293x165mm 13.2-inch  | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SDC3652 1366x768 344x194mm 15.5-inch   | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SAM0F3D 1366x768 522x293mm 23.6-inch   | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 1060x626mm 48.5-inch | 1         | 0.41%   |
| Philips PHL 276E9Q PHLC17B 1920x1080 598x336mm 27.0-inch               | 1         | 0.41%   |
| PANDA LCD Monitor NCP004B 1920x1080 344x194mm 15.5-inch                | 1         | 0.41%   |
| Panasonic LCD Monitor MEI96A2 3840x2160 382x215mm 17.3-inch            | 1         | 0.41%   |
| ONN ONA24HB19T01 ONN0101 1920x1080 517x323mm 24.0-inch                 | 1         | 0.41%   |
| NEC Computers EA243WM NEC6863 1920x1200 519x324mm 24.1-inch            | 1         | 0.41%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch          | 1         | 0.41%   |
| LG Display LP154WX4-TLCC LGD0242 1280x800 331x207mm 15.4-inch          | 1         | 0.41%   |
| LG Display LCD Monitor LGD0690 2560x1440 344x194mm 15.5-inch           | 1         | 0.41%   |
| LG Display LCD Monitor LGD0683 1920x1080 344x194mm 15.5-inch           | 1         | 0.41%   |
| LG Display LCD Monitor LGD066D 1920x1080 344x194mm 15.5-inch           | 1         | 0.41%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch           | 1         | 0.41%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch           | 1         | 0.41%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch           | 1         | 0.41%   |
| LG Display LCD Monitor LGD05D2 1920x1080 344x194mm 15.5-inch           | 1         | 0.41%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 99        | 42.31%  |
| 1366x768 (WXGA)    | 83        | 35.47%  |
| 1600x900 (HD+)     | 15        | 6.41%   |
| 1280x800 (WXGA)    | 10        | 4.27%   |
| 1680x1050 (WSXGA+) | 4         | 1.71%   |
| 1440x900 (WXGA+)   | 4         | 1.71%   |
| 3840x2160 (4K)     | 3         | 1.28%   |
| 2560x1600          | 3         | 1.28%   |
| 2880x1800          | 2         | 0.85%   |
| 2560x1440 (QHD)    | 2         | 0.85%   |
| 2160x1440          | 2         | 0.85%   |
| 1920x1200 (WUXGA)  | 2         | 0.85%   |
| 1024x768 (XGA)     | 2         | 0.85%   |
| 2560x1080          | 1         | 0.43%   |
| 1920x540           | 1         | 0.43%   |
| 1280x1024 (SXGA)   | 1         | 0.43%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 102       | 41.8%   |
| 14      | 36        | 14.75%  |
| 13      | 32        | 13.11%  |
| 17      | 24        | 9.84%   |
| 12      | 10        | 4.1%    |
| 24      | 6         | 2.46%   |
| 11      | 5         | 2.05%   |
| 27      | 4         | 1.64%   |
| 21      | 4         | 1.64%   |
| 31      | 3         | 1.23%   |
| 23      | 3         | 1.23%   |
| 22      | 3         | 1.23%   |
| 16      | 3         | 1.23%   |
| 18      | 2         | 0.82%   |
| 52      | 1         | 0.41%   |
| 48      | 1         | 0.41%   |
| 40      | 1         | 0.41%   |
| 32      | 1         | 0.41%   |
| 29      | 1         | 0.41%   |
| 19      | 1         | 0.41%   |
| Unknown | 1         | 0.41%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 159       | 65.43%  |
| 351-400     | 28        | 11.52%  |
| 201-300     | 26        | 10.7%   |
| 501-600     | 13        | 5.35%   |
| 401-500     | 8         | 3.29%   |
| 601-700     | 4         | 1.65%   |
| 1001-1500   | 2         | 0.82%   |
| 801-900     | 1         | 0.41%   |
| 701-800     | 1         | 0.41%   |
| Unknown     | 1         | 0.41%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 194       | 85.84%  |
| 16/10 | 25        | 11.06%  |
| 4/3   | 2         | 0.88%   |
| 3/2   | 2         | 0.88%   |
| 6/5   | 1         | 0.44%   |
| 32/9  | 1         | 0.44%   |
| 21/9  | 1         | 0.44%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 103       | 42.21%  |
| 81-90          | 59        | 24.18%  |
| 121-130        | 21        | 8.61%   |
| 201-250        | 14        | 5.74%   |
| 61-70          | 10        | 4.1%    |
| 71-80          | 9         | 3.69%   |
| 51-60          | 5         | 2.05%   |
| 301-350        | 5         | 2.05%   |
| 351-500        | 4         | 1.64%   |
| 131-140        | 3         | 1.23%   |
| More than 1000 | 2         | 0.82%   |
| 251-300        | 2         | 0.82%   |
| 141-150        | 2         | 0.82%   |
| 111-120        | 2         | 0.82%   |
| 151-200        | 1         | 0.41%   |
| 501-1000       | 1         | 0.41%   |
| Unknown        | 1         | 0.41%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 101       | 41.74%  |
| 101-120       | 86        | 35.54%  |
| 51-100        | 33        | 13.64%  |
| 161-240       | 14        | 5.79%   |
| 1-50          | 4         | 1.65%   |
| More than 240 | 3         | 1.24%   |
| Unknown       | 1         | 0.41%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 194       | 86.22%  |
| 2     | 26        | 11.56%  |
| 3     | 4         | 1.78%   |
| 0     | 1         | 0.44%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 124       | 33.07%  |
| Realtek Semiconductor                  | 119       | 31.73%  |
| Qualcomm Atheros                       | 48        | 12.8%   |
| Broadcom                               | 24        | 6.4%    |
| MediaTek                               | 7         | 1.87%   |
| Broadcom Limited                       | 7         | 1.87%   |
| Samsung Electronics                    | 6         | 1.6%    |
| TP-Link                                | 5         | 1.33%   |
| Huawei Technologies                    | 5         | 1.33%   |
| Qualcomm Atheros Communications        | 4         | 1.07%   |
| Xiaomi                                 | 3         | 0.8%    |
| Ralink Technology                      | 3         | 0.8%    |
| NetGear                                | 3         | 0.8%    |
| ASUSTek Computer                       | 3         | 0.8%    |
| Nvidia                                 | 2         | 0.53%   |
| ASIX Electronics                       | 2         | 0.53%   |
| Apple                                  | 2         | 0.53%   |
| ZyXEL Communications                   | 1         | 0.27%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.27%   |
| Sagem                                  | 1         | 0.27%   |
| Ralink                                 | 1         | 0.27%   |
| Linksys                                | 1         | 0.27%   |
| Lenovo                                 | 1         | 0.27%   |
| Ericsson Business Mobile Networks      | 1         | 0.27%   |
| Arduino SA                             | 1         | 0.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 60        | 13.16%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 28        | 6.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 14        | 3.07%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 12        | 2.63%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 1.97%   |
| Intel Wireless 8265 / 8275                                              | 8         | 1.75%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 8         | 1.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 1.54%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 7         | 1.54%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 7         | 1.54%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 1.54%   |
| Intel Wireless 7265                                                     | 7         | 1.54%   |
| Intel Wireless 7260                                                     | 7         | 1.54%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 7         | 1.54%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 1.32%   |
| Intel Wireless 3165                                                     | 6         | 1.32%   |
| Intel Wi-Fi 6 AX200                                                     | 6         | 1.32%   |
| Intel Ethernet Connection I218-LM                                       | 6         | 1.32%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 6         | 1.32%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 5         | 1.1%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller               | 5         | 1.1%    |
| Intel Wi-Fi 6 AX201                                                     | 5         | 1.1%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 0.88%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 4         | 0.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 0.88%   |
| Realtek 802.11ac NIC                                                    | 4         | 0.88%   |
| Qualcomm Atheros AR9271 802.11n                                         | 4         | 0.88%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 4         | 0.88%   |
| Intel Wireless 8260                                                     | 4         | 0.88%   |
| Intel Wireless 3160                                                     | 4         | 0.88%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 0.88%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 0.88%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 0.88%   |
| Intel Centrino Advanced-N 6235                                          | 4         | 0.88%   |
| Broadcom BCM43142 802.11b/g/n                                           | 4         | 0.88%   |
| TP-Link TL-WN722N v2                                                    | 3         | 0.66%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 3         | 0.66%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 0.66%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                        | 3         | 0.66%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 3         | 0.66%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 3         | 0.66%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 3         | 0.66%   |
| Intel Ethernet Connection (6) I219-V                                    | 3         | 0.66%   |
| Intel Ethernet Connection (4) I219-LM                                   | 3         | 0.66%   |
| Broadcom BCM4401-B0 100Base-TX                                          | 3         | 0.66%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 3         | 0.66%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 0.66%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 2         | 0.44%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.44%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                         | 2         | 0.44%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 0.44%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 2         | 0.44%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 0.44%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 0.44%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 2         | 0.44%   |
| Realtek RTL8125 2.5GbE Controller                                       | 2         | 0.44%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 0.44%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.44%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 2         | 0.44%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 120       | 46.88%  |
| Realtek Semiconductor             | 46        | 17.97%  |
| Qualcomm Atheros                  | 36        | 14.06%  |
| Broadcom                          | 20        | 7.81%   |
| Broadcom Limited                  | 6         | 2.34%   |
| TP-Link                           | 5         | 1.95%   |
| MediaTek                          | 5         | 1.95%   |
| Qualcomm Atheros Communications   | 4         | 1.56%   |
| Ralink Technology                 | 3         | 1.17%   |
| NetGear                           | 3         | 1.17%   |
| ASUSTek Computer                  | 3         | 1.17%   |
| ZyXEL Communications              | 1         | 0.39%   |
| Sagem                             | 1         | 0.39%   |
| Ralink                            | 1         | 0.39%   |
| Linksys                           | 1         | 0.39%   |
| Ericsson Business Mobile Networks | 1         | 0.39%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 12        | 4.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 3.52%   |
| Intel Wireless 8265 / 8275                                              | 8         | 3.13%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 8         | 3.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 2.73%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 7         | 2.73%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 2.73%   |
| Intel Wireless 7265                                                     | 7         | 2.73%   |
| Intel Wireless 7260                                                     | 7         | 2.73%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 7         | 2.73%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 2.34%   |
| Intel Wireless 3165                                                     | 6         | 2.34%   |
| Intel Wi-Fi 6 AX200                                                     | 6         | 2.34%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 6         | 2.34%   |
| Intel Wi-Fi 6 AX201                                                     | 5         | 1.95%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.56%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 4         | 1.56%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 1.56%   |
| Realtek 802.11ac NIC                                                    | 4         | 1.56%   |
| Qualcomm Atheros AR9271 802.11n                                         | 4         | 1.56%   |
| Intel Wireless 8260                                                     | 4         | 1.56%   |
| Intel Wireless 3160                                                     | 4         | 1.56%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 1.56%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 1.56%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 1.56%   |
| Intel Centrino Advanced-N 6235                                          | 4         | 1.56%   |
| Broadcom BCM43142 802.11b/g/n                                           | 4         | 1.56%   |
| TP-Link TL-WN722N v2                                                    | 3         | 1.17%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 3         | 1.17%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 1.17%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 3         | 1.17%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 3         | 1.17%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 3         | 1.17%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 1.17%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.78%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                         | 2         | 0.78%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 0.78%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 2         | 0.78%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 0.78%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 0.78%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 0.78%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.78%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.78%   |
| NetGear A6210                                                           | 2         | 0.78%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 2         | 0.78%   |
| Intel Ultimate N WiFi Link 5300                                         | 2         | 0.78%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 0.78%   |
| Intel Centrino Wireless-N 2200                                          | 2         | 0.78%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 2         | 0.78%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 0.78%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 2         | 0.78%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 2         | 0.78%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 0.78%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 0.78%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 2         | 0.78%   |
| ZyXEL NWD2205 802.11n Wireless N Adapter [Realtek RTL8192CU]            | 1         | 0.39%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 0.39%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 1         | 0.39%   |
| Sagem XG-76NA 802.11bg                                                  | 1         | 0.39%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.39%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 102       | 53.13%  |
| Intel                 | 42        | 21.88%  |
| Qualcomm Atheros      | 19        | 9.9%    |
| Broadcom              | 8         | 4.17%   |
| Samsung Electronics   | 6         | 3.13%   |
| Xiaomi                | 3         | 1.56%   |
| Nvidia                | 2         | 1.04%   |
| MediaTek              | 2         | 1.04%   |
| Huawei Technologies   | 2         | 1.04%   |
| ASIX Electronics      | 2         | 1.04%   |
| Apple                 | 2         | 1.04%   |
| Lenovo                | 1         | 0.52%   |
| Broadcom Limited      | 1         | 0.52%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 60        | 30.77%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 28        | 14.36%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 14        | 7.18%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 3.59%   |
| Intel Ethernet Connection I218-LM                                 | 6         | 3.08%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 5         | 2.56%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 5         | 2.56%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4         | 2.05%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 1.54%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 1.54%   |
| Intel Ethernet Connection (6) I219-V                              | 3         | 1.54%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.54%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 3         | 1.54%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 1.03%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 1.03%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 1.03%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 1.03%   |
| MediaTek moto e6s                                                 | 2         | 1.03%   |
| Intel Ethernet Connection I217-V                                  | 2         | 1.03%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.03%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.03%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 1.03%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.51%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.51%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.51%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.51%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.51%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.51%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.51%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.51%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.51%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.51%   |
| Nvidia MCP89 Ethernet                                             | 1         | 0.51%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.51%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 0.51%   |
| Intel PRO/100 VE Network Connection                               | 1         | 0.51%   |
| Intel Ethernet controller                                         | 1         | 0.51%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.51%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.51%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.51%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.51%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.51%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.51%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 0.51%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.51%   |
| Huawei JNY-LX1                                                    | 1         | 0.51%   |
| Huawei Ideos (tethering mode)                                     | 1         | 0.51%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 0.51%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 0.51%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 0.51%   |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe         | 1         | 0.51%   |
| ASIX AX88772A Fast Ethernet                                       | 1         | 0.51%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 0.51%   |
| Apple iPad 4/Mini1                                                | 1         | 0.51%   |
| Apple iBridge                                                     | 1         | 0.51%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 221       | 54.3%   |
| Ethernet | 181       | 44.47%  |
| Modem    | 4         | 0.98%   |
| Unknown  | 1         | 0.25%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 185       | 77.73%  |
| Ethernet | 52        | 21.85%  |
| Unknown  | 1         | 0.42%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 162       | 72.65%  |
| 1     | 56        | 25.11%  |
| 0     | 3         | 1.35%   |
| 3     | 2         | 0.9%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Notebooks | Percent |
|---------|-----------|---------|
| No      | 188       | 82.82%  |
| Yes     | 38        | 16.74%  |
| Unknown | 1         | 0.44%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 90        | 49.45%  |
| Qualcomm Atheros Communications | 19        | 10.44%  |
| Realtek Semiconductor           | 18        | 9.89%   |
| Broadcom                        | 14        | 7.69%   |
| Lite-On Technology              | 7         | 3.85%   |
| Foxconn / Hon Hai               | 7         | 3.85%   |
| Apple                           | 7         | 3.85%   |
| IMC Networks                    | 4         | 2.2%    |
| Cambridge Silicon Radio         | 4         | 2.2%    |
| MediaTek                        | 3         | 1.65%   |
| Dell                            | 3         | 1.65%   |
| Toshiba                         | 2         | 1.1%    |
| Realtek                         | 1         | 0.55%   |
| Ralink                          | 1         | 0.55%   |
| Dynex                           | 1         | 0.55%   |
| Alps Electric                   | 1         | 0.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 36        | 19.78%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 20        | 10.99%  |
| Intel AX201 Bluetooth                                                               | 18        | 9.89%   |
| Realtek Bluetooth Radio                                                             | 10        | 5.49%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 9         | 4.95%   |
| Intel AX200 Bluetooth                                                               | 6         | 3.3%    |
| Realtek  Bluetooth 4.2 Adapter                                                      | 5         | 2.75%   |
| Apple Bluetooth Host Controller                                                     | 5         | 2.75%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 4         | 2.2%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 4         | 2.2%    |
| Broadcom HP Portable SoftSailing                                                    | 4         | 2.2%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 1.65%   |
| MediaTek Wireless_Device                                                            | 3         | 1.65%   |
| Dell DW375 Bluetooth Module                                                         | 3         | 1.65%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 3         | 1.65%   |
| Realtek RTL8821A Bluetooth                                                          | 2         | 1.1%    |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 2         | 1.1%    |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 1.1%    |
| Lite-On Wireless_Device                                                             | 2         | 1.1%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 2         | 1.1%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 2         | 1.1%    |
| IMC Networks Bluetooth Radio                                                        | 2         | 1.1%    |
| IMC Networks Bluetooth Device                                                       | 2         | 1.1%    |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 1.1%    |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 1.1%    |
| Foxconn / Hon Hai BCM20702A0                                                        | 2         | 1.1%    |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 2         | 1.1%    |
| Broadcom BCM2045B (BDC-2.1)                                                         | 2         | 1.1%    |
| Apple Bluetooth USB Host Controller                                                 | 2         | 1.1%    |
| Toshiba Bluetooth USB Host Controller                                               | 1         | 0.55%   |
| Toshiba BCM43142A0                                                                  | 1         | 0.55%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.55%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.55%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.55%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.55%   |
| Qualcomm Atheros Bluetooth                                                          | 1         | 0.55%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.55%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.55%   |
| Lite-On Bluetooth Radio                                                             | 1         | 0.55%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 0.55%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 0.55%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 0.55%   |
| Intel Bluetooth Device                                                              | 1         | 0.55%   |
| Intel AX210 Bluetooth                                                               | 1         | 0.55%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth                                       | 1         | 0.55%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]                            | 1         | 0.55%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 0.55%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 0.55%   |
| Broadcom BCM20702A0                                                                 | 1         | 0.55%   |
| Alps Electric UGTZ4 Bluetooth                                                       | 1         | 0.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor    | Notebooks | Percent |
|-----------|-----------|---------|
| Intel     | 185       | 70.08%  |
| Nvidia    | 39        | 14.77%  |
| AMD       | 36        | 13.64%  |
| Lenovo    | 1         | 0.38%   |
| Guillemot | 1         | 0.38%   |
| GN Netcom | 1         | 0.38%   |
| Apple     | 1         | 0.38%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 27        | 8.41%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 24        | 7.48%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 21        | 6.54%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 15        | 4.67%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 13        | 4.05%   |
| Intel 8 Series HD Audio Controller                                                                | 13        | 4.05%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 11        | 3.43%   |
| Intel Cannon Lake PCH cAVS                                                                        | 11        | 3.43%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 10        | 3.12%   |
| Intel Broadwell-U Audio Controller                                                                | 10        | 3.12%   |
| AMD FCH Azalia Controller                                                                         | 9         | 2.8%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 8         | 2.49%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 7         | 2.18%   |
| Intel Comet Lake PCH cAVS                                                                         | 7         | 2.18%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 1.87%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 1.87%   |
| AMD Kabini HDMI/DP Audio                                                                          | 6         | 1.87%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 1.56%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 5         | 1.56%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 1.56%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 1.56%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1.25%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 4         | 1.25%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 1.25%   |
| Nvidia Audio device                                                                               | 4         | 1.25%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 4         | 1.25%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 1.25%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 1.25%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 1.25%   |
| AMD High Definition Audio Controller                                                              | 4         | 1.25%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 1.25%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 0.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.93%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 0.93%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 0.93%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 0.93%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 3         | 0.93%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 0.93%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.62%   |
| Nvidia MCP89 High Definition Audio                                                                | 2         | 0.62%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.62%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.62%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 2         | 0.62%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 0.62%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 2         | 0.62%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.62%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 0.62%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 2         | 0.62%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.31%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.31%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.31%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.31%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 1         | 0.31%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.31%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                                      | 1         | 0.31%   |
| Intel USB PnP Sound Device                                                                        | 1         | 0.31%   |
| Intel Crystal Well HD Audio Controller                                                            | 1         | 0.31%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.31%   |
| Guillemot DJ Control Air                                                                          | 1         | 0.31%   |
| GN Netcom Jabra EVOLVE 65                                                                         | 1         | 0.31%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 51        | 30%     |
| SK hynix            | 30        | 17.65%  |
| Micron Technology   | 28        | 16.47%  |
| Crucial             | 11        | 6.47%   |
| Kingston            | 10        | 5.88%   |
| Unknown             | 8         | 4.71%   |
| Ramaxel Technology  | 7         | 4.12%   |
| Elpida              | 7         | 4.12%   |
| Unknown (ABCD)      | 3         | 1.76%   |
| Corsair             | 3         | 1.76%   |
| Team                | 2         | 1.18%   |
| Nanya Technology    | 2         | 1.18%   |
| G.Skill             | 2         | 1.18%   |
| A-DATA Technology   | 2         | 1.18%   |
| Teikon              | 1         | 0.59%   |
| Smart               | 1         | 0.59%   |
| Saikano             | 1         | 0.59%   |
| PNY                 | 1         | 0.59%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s            | 6         | 3.37%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s            | 6         | 3.37%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 4         | 2.25%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 3         | 1.69%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 3         | 1.69%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 3         | 1.69%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 3         | 1.69%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 3         | 1.69%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s                | 3         | 1.69%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s              | 3         | 1.69%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                         | 2         | 1.12%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 2         | 1.12%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s              | 2         | 1.12%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 2         | 1.12%   |
| Samsung RAM M471A5244CB0-CTD 4096MB Row Of Chips DDR4 2667MT/s      | 2         | 1.12%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 2         | 1.12%   |
| Samsung RAM M4 70T2953CZ3-CE6 1GB SODIMM DDR 667MT/s                | 2         | 1.12%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 2         | 1.12%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s          | 2         | 1.12%   |
| Micron RAM 16JSF51264HZ-1G4D1 4096MB SODIMM DDR3 1334MT/s           | 2         | 1.12%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                          | 2         | 1.12%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                         | 1         | 0.56%   |
| Unknown RAM Module 4096MB SODIMM DDR3                               | 1         | 0.56%   |
| Unknown RAM Module 4096MB SODIMM 1066MT/s                           | 1         | 0.56%   |
| Unknown RAM Module 2GB SODIMM DDR3                                  | 1         | 0.56%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                       | 1         | 0.56%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                          | 1         | 0.56%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                       | 1         | 0.56%   |
| Teikon RAM TMT451S6BFR8A-PBHJ 4096MB SODIMM DDR3 1600MT/s           | 1         | 0.56%   |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s                | 1         | 0.56%   |
| Team RAM TEAMGROUP-SD3-1600 8192MB SODIMM DDR3 1600MT/s             | 1         | 0.56%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s               | 1         | 0.56%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s                | 1         | 0.56%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1066MT/s                     | 1         | 0.56%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1066MT/s                        | 1         | 0.56%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                       | 1         | 0.56%   |
| SK hynix RAM HMT851S6AMR6R-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 0.56%   |
| SK hynix RAM HMT851S6AMR6A-PB 4GB Chip DDR3 1600MT/s                | 1         | 0.56%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.56%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.56%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s              | 1         | 0.56%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s              | 1         | 0.56%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s              | 1         | 0.56%   |
| SK hynix RAM HMA851S6JJR6N-VK 4096MB SODIMM DDR4 2667MT/s           | 1         | 0.56%   |
| SK hynix RAM HMA851S6CJR6N-VK 4096MB Row Of Chips DDR4 2667MT/s     | 1         | 0.56%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s             | 1         | 0.56%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 0.56%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 1         | 0.56%   |
| SK hynix RAM H9HCNNNBKMALHR-NEE 4096MB Row Of Chips LPDDR4 4267MT/s | 1         | 0.56%   |
| Samsung RAM Module 8GB SODIMM DDR4 2667MT/s                         | 1         | 0.56%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s                         | 1         | 0.56%   |
| Samsung RAM Module 2GB SODIMM LPDDR4 2400MT/s                       | 1         | 0.56%   |
| Samsung RAM Module 2048MB SODIMM DDR3 1333MT/s                      | 1         | 0.56%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                        | 1         | 0.56%   |
| Samsung RAM M474A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 1         | 0.56%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s               | 1         | 0.56%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.56%   |
| Samsung RAM M471B5173CB0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.56%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 0.56%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 0.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 62        | 43.36%  |
| DDR3    | 59        | 41.26%  |
| LPDDR4  | 9         | 6.29%   |
| LPDDR3  | 5         | 3.5%    |
| DDR2    | 4         | 2.8%    |
| SDRAM   | 1         | 0.7%    |
| DDR5    | 1         | 0.7%    |
| DDR     | 1         | 0.7%    |
| Unknown | 1         | 0.7%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 130       | 90.91%  |
| Row Of Chips | 11        | 7.69%   |
| Chip         | 1         | 0.7%    |
| Unknown      | 1         | 0.7%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 65        | 41.94%  |
| 8192  | 47        | 30.32%  |
| 16384 | 19        | 12.26%  |
| 2048  | 14        | 9.03%   |
| 1024  | 7         | 4.52%   |
| 32768 | 3         | 1.94%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 39        | 24.68%  |
| 1600    | 39        | 24.68%  |
| 3200    | 19        | 12.03%  |
| 1334    | 13        | 8.23%   |
| 2400    | 12        | 7.59%   |
| 2133    | 7         | 4.43%   |
| 1333    | 6         | 3.8%    |
| 3266    | 3         | 1.9%    |
| 1867    | 3         | 1.9%    |
| 1067    | 3         | 1.9%    |
| 1066    | 3         | 1.9%    |
| 667     | 3         | 1.9%    |
| Unknown | 2         | 1.27%   |
| 8400    | 1         | 0.63%   |
| 4800    | 1         | 0.63%   |
| 4267    | 1         | 0.63%   |
| 2048    | 1         | 0.63%   |
| 800     | 1         | 0.63%   |
| 533     | 1         | 0.63%   |

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
| Chicony Electronics                    | 63        | 31.03%  |
| Acer                                   | 23        | 11.33%  |
| IMC Networks                           | 19        | 9.36%   |
| Microdia                               | 17        | 8.37%   |
| Sunplus Innovation Technology          | 13        | 6.4%    |
| Realtek Semiconductor                  | 10        | 4.93%   |
| Quanta                                 | 9         | 4.43%   |
| Apple                                  | 9         | 4.43%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 2.96%   |
| Ricoh                                  | 5         | 2.46%   |
| Syntek                                 | 4         | 1.97%   |
| Luxvisions Innotech Limited            | 4         | 1.97%   |
| Suyin                                  | 3         | 1.48%   |
| Silicon Motion                         | 3         | 1.48%   |
| Samsung Electronics                    | 3         | 1.48%   |
| Lite-On Technology                     | 3         | 1.48%   |
| Alcor Micro                            | 3         | 1.48%   |
| Primax Electronics                     | 1         | 0.49%   |
| LG Electronics                         | 1         | 0.49%   |
| Importek                               | 1         | 0.49%   |
| icSpring                               | 1         | 0.49%   |
| Goertek Electronics                    | 1         | 0.49%   |
| ALi                                    | 1         | 0.49%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony integrated camera                           | 9         | 4.43%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 6         | 2.96%   |
| Chicony HD Webcam                                   | 6         | 2.96%   |
| Chicony HD User Facing                              | 6         | 2.96%   |
| Acer HD Webcam                                      | 6         | 2.96%   |
| Realtek Integrated_Webcam_HD                        | 5         | 2.46%   |
| IMC Networks Integrated Camera                      | 5         | 2.46%   |
| Chicony HP Truevision HD                            | 5         | 2.46%   |
| Sunplus Integrated_Webcam_HD                        | 4         | 1.97%   |
| Microdia Integrated_Webcam_HD                       | 4         | 1.97%   |
| Chicony USB2.0 Camera                               | 4         | 1.97%   |
| Acer EasyCamera                                     | 4         | 1.97%   |
| Syntek Integrated Camera                            | 3         | 1.48%   |
| Samsung Galaxy series, misc. (MTP mode)             | 3         | 1.48%   |
| Quanta HP TrueVision HD Camera                      | 3         | 1.48%   |
| Microdia Webcam Vitade AF                           | 3         | 1.48%   |
| Microdia Integrated Webcam                          | 3         | 1.48%   |
| Chicony USB2.0 HD UVC WebCam                        | 3         | 1.48%   |
| Apple iPhone 5/5C/5S/6/SE                           | 3         | 1.48%   |
| Alcor Micro USB 2.0 Camera                          | 3         | 1.48%   |
| Acer SunplusIT Integrated Camera                    | 3         | 1.48%   |
| Sunplus HD WebCam                                   | 2         | 0.99%   |
| Realtek Integrated Webcam                           | 2         | 0.99%   |
| Quanta HD User Facing                               | 2         | 0.99%   |
| Microdia PC Microscope camera                       | 2         | 0.99%   |
| Microdia Laptop_Integrated_Webcam_HD                | 2         | 0.99%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 2         | 0.99%   |
| Lite-On HP Wide Vision HD Camera                    | 2         | 0.99%   |
| IMC Networks HD Camera                              | 2         | 0.99%   |
| Chicony USB2.0 VGA UVC WebCam                       | 2         | 0.99%   |
| Chicony TOSHIBA Web Camera - HD                     | 2         | 0.99%   |
| Chicony Integrated HP HD Webcam                     | 2         | 0.99%   |
| Chicony Integrated Camera [ThinkPad]                | 2         | 0.99%   |
| Chicony Integrated Camera (1280x720@30)             | 2         | 0.99%   |
| Chicony HP HD Webcam [Fixed]                        | 2         | 0.99%   |
| Chicony HP HD Camera                                | 2         | 0.99%   |
| Chicony FJ Camera                                   | 2         | 0.99%   |
| Chicony EasyCamera                                  | 2         | 0.99%   |
| Apple FaceTime HD Camera                            | 2         | 0.99%   |
| Apple Built-in iSight                               | 2         | 0.99%   |
| Acer Lenovo EasyCamera                              | 2         | 0.99%   |
| Acer Integrated Camera                              | 2         | 0.99%   |
| Acer HD Camera                                      | 2         | 0.99%   |
| Syntek Lenovo EasyCamera                            | 1         | 0.49%   |
| Suyin Integrated_Webcam_HD                          | 1         | 0.49%   |
| Suyin HP Truevision HD                              | 1         | 0.49%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 0.49%   |
| Sunplus Laptop_Integrated_Webcam_HD                 | 1         | 0.49%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 1         | 0.49%   |
| Sunplus Laptop Integrated Webcam FHD                | 1         | 0.49%   |
| Sunplus Integrated Camera                           | 1         | 0.49%   |
| Sunplus HP HD Webcam [Fixed]                        | 1         | 0.49%   |
| Sunplus Depstech webcam MIC                         | 1         | 0.49%   |
| Sunplus ASUS USB2.0 Webcam                          | 1         | 0.49%   |
| Silicon Motion WebCam SCB-0385N                     | 1         | 0.49%   |
| Silicon Motion WebCam SC-13HDL11939N                | 1         | 0.49%   |
| Silicon Motion WebCam SC-03FFL11939N                | 1         | 0.49%   |
| Ricoh USB2.0 Camera                                 | 1         | 0.49%   |
| Ricoh Pavilion Webcam                               | 1         | 0.49%   |
| Ricoh Laptop_Integrated_Webcam_FHD                  | 1         | 0.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 17        | 45.95%  |
| Synaptics                  | 9         | 24.32%  |
| Shenzhen Goodix Technology | 3         | 8.11%   |
| Elan Microelectronics      | 3         | 8.11%   |
| LighTuning Technology      | 2         | 5.41%   |
| AuthenTec                  | 2         | 5.41%   |
| Upek                       | 1         | 2.7%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 8.11%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 8.11%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 8.11%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 2         | 5.41%   |
| Validity Sensors VFS491                                                    | 2         | 5.41%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 5.41%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 5.41%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 5.41%   |
| Shenzhen Goodix  Fingerprint Device                                        | 2         | 5.41%   |
| Elan ELAN:Fingerprint                                                      | 2         | 5.41%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 2.7%    |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 2.7%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.7%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 2.7%    |
| Synaptics  WBDI                                                            | 1         | 2.7%    |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 2.7%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 2.7%    |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 2.7%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 2.7%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 2.7%    |
| Elan ELAN:ARM-M4                                                           | 1         | 2.7%    |
| AuthenTec Fingerprint Sensor                                               | 1         | 2.7%    |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 2.7%    |
| Unknown                                                                    | 1         | 2.7%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 9         | 60%     |
| Alcor Micro | 4         | 26.67%  |
| OmniKey     | 1         | 6.67%   |
| O2 Micro    | 1         | 6.67%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 40%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 4         | 26.67%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 13.33%  |
| OmniKey CardMan Smart@Link                                                   | 1         | 6.67%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 6.67%   |
| Broadcom 5880                                                                | 1         | 6.67%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 134       | 59.03%  |
| 1     | 76        | 33.48%  |
| 2     | 15        | 6.61%   |
| 3     | 2         | 0.88%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 38        | 35.19%  |
| Graphics card         | 16        | 14.81%  |
| Chipcard              | 14        | 12.96%  |
| Net/wireless          | 13        | 12.04%  |
| Multimedia controller | 10        | 9.26%   |
| Camera                | 6         | 5.56%   |
| Storage               | 5         | 4.63%   |
| Network               | 3         | 2.78%   |
| Modem                 | 1         | 0.93%   |
| Card reader           | 1         | 0.93%   |
| Bluetooth             | 1         | 0.93%   |

