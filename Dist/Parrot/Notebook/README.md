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

Total: 331

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | Presario CQ58               | [4bb50cd19d](https://linux-hardware.org/?probe=4bb50cd19d) | Sep 28, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | [9616464154](https://linux-hardware.org/?probe=9616464154) | Sep 26, 2022 |
| Dell          | Latitude 3350               | [e2de1deaa2](https://linux-hardware.org/?probe=e2de1deaa2) | Sep 25, 2022 |
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
| Parrot 5.0   | 80        | 32.79%  |
| Parrot 4.11  | 63        | 25.82%  |
| Parrot 4.10  | 45        | 18.44%  |
| Parrot 4.8   | 15        | 6.15%   |
| Parrot 4.9   | 13        | 5.33%   |
| Parrot 5.1   | 12        | 4.92%   |
| Parrot 4.7   | 10        | 4.1%    |
| Parrot 4.6   | 2         | 0.82%   |
| Parrot 4.5   | 1         | 0.41%   |
| Parrot 4.4   | 1         | 0.41%   |
| Parrot 4.2.2 | 1         | 0.41%   |
| Parrot 3.10  | 1         | 0.41%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Parrot | 231       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.14.0-9parrot1-amd64    | 36        | 14.46%  |
| 5.16.0-12parrot1-amd64   | 33        | 13.25%  |
| 5.7.0-2parrot2-amd64     | 26        | 10.44%  |
| 5.10.0-6parrot1-amd64    | 25        | 10.04%  |
| 5.18.0-1parrot1-amd64    | 14        | 5.62%   |
| 5.10.0-8parrot1-amd64    | 14        | 5.62%   |
| 5.5.0-1parrot1-amd64     | 12        | 4.82%   |
| 5.4.0-4parrot1-amd64     | 11        | 4.42%   |
| 5.18.0-14parrot1-amd64   | 11        | 4.42%   |
| 5.6.0-2parrot1-amd64     | 9         | 3.61%   |
| 5.14.0-2parrot1-amd64    | 9         | 3.61%   |
| 5.9.0-2parrot1-amd64     | 7         | 2.81%   |
| 5.15.0-15parrot1-amd64   | 5         | 2.01%   |
| 5.8.0-2parrot1-amd64     | 3         | 1.2%    |
| 5.4.0-2parrot1-amd64     | 3         | 1.2%    |
| 5.2.0-2parrot1-amd64     | 3         | 1.2%    |
| 5.10.0-5parrot1-amd64    | 3         | 1.2%    |
| 5.10.0-3parrot1-amd64    | 3         | 1.2%    |
| 4.19.0-parrot4-28t-amd64 | 3         | 1.2%    |
| 5.8.0-1parrot1-amd64     | 2         | 0.8%    |
| 5.4.0-3parrot1-amd64     | 2         | 0.8%    |
| 4.18.0-parrot10-amd64    | 2         | 0.8%    |
| 5.7.0-rc6-galliumos      | 1         | 0.4%    |
| 5.4.0-2parrot1-686-pae   | 1         | 0.4%    |
| 5.4.0-1parrot1-amd64     | 1         | 0.4%    |
| 5.3.0-3parrot3-amd64     | 1         | 0.4%    |
| 5.3.0-3parrot3-686-pae   | 1         | 0.4%    |
| 5.3.0-1parrot1-amd64     | 1         | 0.4%    |
| 5.15.0-5parrot1-amd64    | 1         | 0.4%    |
| 5.10.0-kali6-amd64       | 1         | 0.4%    |
| 5.10.0-6parrot1-rt-amd64 | 1         | 0.4%    |
| 5.1.0-parrot1-3t-amd64   | 1         | 0.4%    |
| 4.19.0-parrot1-13t-amd64 | 1         | 0.4%    |
| 4.14.0-parrot7-amd64     | 1         | 0.4%    |
| Unknown                  | 1         | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 47        | 19.03%  |
| 5.14.0  | 44        | 17.81%  |
| 5.16.0  | 33        | 13.36%  |
| 5.7.0   | 27        | 10.93%  |
| 5.18.0  | 24        | 9.72%   |
| 5.4.0   | 18        | 7.29%   |
| 5.5.0   | 12        | 4.86%   |
| 5.6.0   | 9         | 3.64%   |
| 5.9.0   | 7         | 2.83%   |
| 5.15.0  | 6         | 2.43%   |
| 5.8.0   | 5         | 2.02%   |
| 4.19.0  | 4         | 1.62%   |
| 5.3.0   | 3         | 1.21%   |
| 5.2.0   | 3         | 1.21%   |
| 4.18.0  | 2         | 0.81%   |
| 5.1.0   | 1         | 0.4%    |
| 4.14.0  | 1         | 0.4%    |
| Unknown | 1         | 0.4%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 47        | 19.03%  |
| 5.14    | 44        | 17.81%  |
| 5.16    | 33        | 13.36%  |
| 5.7     | 27        | 10.93%  |
| 5.18    | 24        | 9.72%   |
| 5.4     | 18        | 7.29%   |
| 5.5     | 12        | 4.86%   |
| 5.6     | 9         | 3.64%   |
| 5.9     | 7         | 2.83%   |
| 5.15    | 6         | 2.43%   |
| 5.8     | 5         | 2.02%   |
| 4.19    | 4         | 1.62%   |
| 5.3     | 3         | 1.21%   |
| 5.2     | 3         | 1.21%   |
| 4.18    | 2         | 0.81%   |
| 5.1     | 1         | 0.4%    |
| 4.14    | 1         | 0.4%    |
| Unknown | 1         | 0.4%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 230       | 99.57%  |
| i686   | 1         | 0.43%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| MATE          | 152       | 64.41%  |
| KDE5          | 47        | 19.92%  |
| Unknown       | 17        | 7.2%    |
| KDE           | 13        | 5.51%   |
| XFCE          | 5         | 2.12%   |
| LXDE          | 1         | 0.42%   |
| GNOME Classic | 1         | 0.42%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 227       | 98.27%  |
| Tty     | 2         | 0.87%   |
| Wayland | 1         | 0.43%   |
| Unknown | 1         | 0.43%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 90        | 37.97%  |
| Unknown | 90        | 37.97%  |
| TDM     | 50        | 21.1%   |
| GDM     | 5         | 2.11%   |
| SDDM    | 2         | 0.84%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 121       | 52.16%  |
| en_GB   | 22        | 9.48%   |
| Unknown | 14        | 6.03%   |
| fr_FR   | 12        | 5.17%   |
| es_ES   | 8         | 3.45%   |
| ru_RU   | 7         | 3.02%   |
| pl_PL   | 7         | 3.02%   |
| pt_BR   | 6         | 2.59%   |
| de_DE   | 6         | 2.59%   |
| en_IN   | 5         | 2.16%   |
| en_AU   | 4         | 1.72%   |
| it_IT   | 2         | 0.86%   |
| tr_TR   | 1         | 0.43%   |
| pt_PT   | 1         | 0.43%   |
| nl_BE   | 1         | 0.43%   |
| id_ID   | 1         | 0.43%   |
| fr_CA   | 1         | 0.43%   |
| fi_FI   | 1         | 0.43%   |
| es_PE   | 1         | 0.43%   |
| es_MX   | 1         | 0.43%   |
| es_CO   | 1         | 0.43%   |
| es_CL   | 1         | 0.43%   |
| es_AR   | 1         | 0.43%   |
| en_ZA   | 1         | 0.43%   |
| en_NZ   | 1         | 0.43%   |
| en_NG   | 1         | 0.43%   |
| en_DK   | 1         | 0.43%   |
| en_CA   | 1         | 0.43%   |
| cs_CZ   | 1         | 0.43%   |
| C       | 1         | 0.43%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 146       | 62.39%  |
| EFI  | 88        | 37.61%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Btrfs   | 173       | 73.62%  |
| Ext4    | 41        | 17.45%  |
| Xfs     | 8         | 3.4%    |
| Unknown | 7         | 2.98%   |
| Overlay | 6         | 2.55%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 105       | 44.68%  |
| GPT     | 84        | 35.74%  |
| MBR     | 46        | 19.57%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 205       | 87.61%  |
| Yes       | 29        | 12.39%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 157       | 67.09%  |
| Yes       | 77        | 32.91%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 47        | 20.35%  |
| Lenovo                | 43        | 18.61%  |
| Dell                  | 40        | 17.32%  |
| ASUSTek Computer      | 20        | 8.66%   |
| Acer                  | 16        | 6.93%   |
| MSI                   | 10        | 4.33%   |
| Apple                 | 9         | 3.9%    |
| Toshiba               | 8         | 3.46%   |
| Samsung Electronics   | 4         | 1.73%   |
| HUAWEI                | 4         | 1.73%   |
| Sony                  | 3         | 1.3%    |
| Fujitsu               | 3         | 1.3%    |
| Razer                 | 2         | 0.87%   |
| Gateway               | 2         | 0.87%   |
| Alienware             | 2         | 0.87%   |
| Wortmann AG           | 1         | 0.43%   |
| Toxic                 | 1         | 0.43%   |
| Timi                  | 1         | 0.43%   |
| System76              | 1         | 0.43%   |
| Standard              | 1         | 0.43%   |
| Positivo Bahia - VAIO | 1         | 0.43%   |
| Positivo              | 1         | 0.43%   |
| Panasonic             | 1         | 0.43%   |
| Notebook              | 1         | 0.43%   |
| Metabox               | 1         | 0.43%   |
| Jumper                | 1         | 0.43%   |
| GPU Company           | 1         | 0.43%   |
| Google                | 1         | 0.43%   |
| eMachines             | 1         | 0.43%   |
| Eluktronics           | 1         | 0.43%   |
| Digma                 | 1         | 0.43%   |
| Chuwi                 | 1         | 0.43%   |
| Unknown               | 1         | 0.43%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                               | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| MSI Modern 15 A5M                                  | 3         | 1.3%    |
| Lenovo IdeaPad 3 15IIL05 81WE                      | 3         | 1.3%    |
| HP Notebook                                        | 3         | 1.3%    |
| HP EliteBook 8470p                                 | 3         | 1.3%    |
| Dell Latitude E6420                                | 3         | 1.3%    |
| Dell Inspiron MM061                                | 3         | 1.3%    |
| HP ProBook 650 G1                                  | 2         | 0.87%   |
| HP Pavilion dv6                                    | 2         | 0.87%   |
| HP Pavilion 15                                     | 2         | 0.87%   |
| Dell Latitude E7440                                | 2         | 0.87%   |
| Dell Latitude E6410                                | 2         | 0.87%   |
| ASUS Q524UQ                                        | 2         | 0.87%   |
| Apple MacBookPro8,1                                | 2         | 0.87%   |
| Acer Nitro AN515-54                                | 2         | 0.87%   |
| Unknown                                            | 2         | 0.87%   |
| Wortmann AG TERRA_MOBILE_1542                      | 1         | 0.43%   |
| Toxic GM7MQ8P                                      | 1         | 0.43%   |
| Toshiba Satellite-L845                             | 1         | 0.43%   |
| Toshiba Satellite L775D                            | 1         | 0.43%   |
| Toshiba Satellite L750                             | 1         | 0.43%   |
| Toshiba Satellite L655                             | 1         | 0.43%   |
| Toshiba Satellite L300D                            | 1         | 0.43%   |
| Toshiba Satellite Click 2 L35W-B                   | 1         | 0.43%   |
| Toshiba Satellite C855D                            | 1         | 0.43%   |
| Toshiba Satellite C75D-B                           | 1         | 0.43%   |
| Timi TM1613                                        | 1         | 0.43%   |
| System76 Gazelle                                   | 1         | 0.43%   |
| Sony VPCSB1C5E                                     | 1         | 0.43%   |
| Sony VPCCB15FG                                     | 1         | 0.43%   |
| Sony SVP1321L1EBI                                  | 1         | 0.43%   |
| Samsung RV415/RV515                                | 1         | 0.43%   |
| Samsung 550P5C/550P7C                              | 1         | 0.43%   |
| Samsung 350V5C/351V5C/3540VC/3440VC                | 1         | 0.43%   |
| Samsung 300E4C/300E5C/300E7C                       | 1         | 0.43%   |
| Razer Blade Stealth                                | 1         | 0.43%   |
| Razer Blade 15 Base Model (Early 2020) - RZ09-0328 | 1         | 0.43%   |
| Positivo Q232A                                     | 1         | 0.43%   |
| Positivo Bahia - VAIO VJFE51F11X-B0111H            | 1         | 0.43%   |
| Panasonic CF-31JBGNNDM                             | 1         | 0.43%   |
| Notebook W510TU                                    | 1         | 0.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 21        | 9.09%   |
| Dell Latitude          | 17        | 7.36%   |
| Dell Inspiron          | 16        | 6.93%   |
| HP Pavilion            | 14        | 6.06%   |
| Lenovo IdeaPad         | 11        | 4.76%   |
| HP EliteBook           | 9         | 3.9%    |
| Toshiba Satellite      | 7         | 3.03%   |
| HP Laptop              | 7         | 3.03%   |
| Acer Aspire            | 7         | 3.03%   |
| HP ProBook             | 5         | 2.16%   |
| ASUS VivoBook          | 4         | 1.73%   |
| Acer Nitro             | 4         | 1.73%   |
| MSI Modern             | 3         | 1.3%    |
| HP Notebook            | 3         | 1.3%    |
| Fujitsu LIFEBOOK       | 3         | 1.3%    |
| Razer Blade            | 2         | 0.87%   |
| HP ZBook               | 2         | 0.87%   |
| HP 250                 | 2         | 0.87%   |
| Dell Vostro            | 2         | 0.87%   |
| Dell Precision         | 2         | 0.87%   |
| ASUS TUF               | 2         | 0.87%   |
| ASUS Q524UQ            | 2         | 0.87%   |
| Apple MacBookPro8      | 2         | 0.87%   |
| Apple MacBookPro11     | 2         | 0.87%   |
| Acer Swift             | 2         | 0.87%   |
| Acer Predator          | 2         | 0.87%   |
| Unknown                | 2         | 0.87%   |
| Wortmann AG TERRA      | 1         | 0.43%   |
| Toxic GM7MQ8P          | 1         | 0.43%   |
| Toshiba Satellite-L845 | 1         | 0.43%   |
| Timi TM1613            | 1         | 0.43%   |
| System76 Gazelle       | 1         | 0.43%   |
| Sony VPCSB1C5E         | 1         | 0.43%   |
| Sony VPCCB15FG         | 1         | 0.43%   |
| Sony SVP1321L1EBI      | 1         | 0.43%   |
| Samsung RV415          | 1         | 0.43%   |
| Samsung 550P5C         | 1         | 0.43%   |
| Samsung 350V5C         | 1         | 0.43%   |
| Samsung 300E4C         | 1         | 0.43%   |
| Positivo Q232A         | 1         | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 28        | 12.12%  |
| 2011 | 28        | 12.12%  |
| 2020 | 22        | 9.52%   |
| 2013 | 22        | 9.52%   |
| 2018 | 20        | 8.66%   |
| 2021 | 19        | 8.23%   |
| 2012 | 18        | 7.79%   |
| 2016 | 16        | 6.93%   |
| 2014 | 13        | 5.63%   |
| 2017 | 12        | 5.19%   |
| 2010 | 8         | 3.46%   |
| 2015 | 7         | 3.03%   |
| 2008 | 6         | 2.6%    |
| 2006 | 4         | 1.73%   |
| 2022 | 3         | 1.3%    |
| 2007 | 3         | 1.3%    |
| 2009 | 2         | 0.87%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 231       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 231       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 230       | 99.57%  |
| Yes  | 1         | 0.43%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 60        | 25.97%  |
| 8.01-16.0   | 51        | 22.08%  |
| 16.01-24.0  | 44        | 19.05%  |
| 3.01-4.0    | 43        | 18.61%  |
| 32.01-64.0  | 15        | 6.49%   |
| 1.01-2.0    | 7         | 3.03%   |
| 64.01-256.0 | 5         | 2.16%   |
| 24.01-32.0  | 3         | 1.3%    |
| 2.01-3.0    | 3         | 1.3%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 83        | 33.88%  |
| 2.01-3.0  | 79        | 32.24%  |
| 3.01-4.0  | 41        | 16.73%  |
| 4.01-8.0  | 26        | 10.61%  |
| 0.51-1.0  | 10        | 4.08%   |
| 8.01-16.0 | 5         | 2.04%   |
| 0.01-0.5  | 1         | 0.41%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 157       | 67.09%  |
| 2      | 68        | 29.06%  |
| 3      | 8         | 3.42%   |
| 0      | 1         | 0.43%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 150       | 64.94%  |
| Yes       | 81        | 35.06%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 189       | 81.47%  |
| No        | 43        | 18.53%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 228       | 98.7%   |
| No        | 3         | 1.3%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 188       | 80%     |
| No        | 47        | 20%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 75        | 32.19%  |
| Germany      | 14        | 6.01%   |
| France       | 12        | 5.15%   |
| Spain        | 11        | 4.72%   |
| UK           | 10        | 4.29%   |
| Russia       | 8         | 3.43%   |
| Brazil       | 8         | 3.43%   |
| Netherlands  | 7         | 3%      |
| India        | 6         | 2.58%   |
| Kenya        | 5         | 2.15%   |
| Canada       | 5         | 2.15%   |
| Sweden       | 4         | 1.72%   |
| Italy        | 4         | 1.72%   |
| Indonesia    | 4         | 1.72%   |
| Australia    | 4         | 1.72%   |
| South Africa | 3         | 1.29%   |
| Poland       | 3         | 1.29%   |
| Mexico       | 3         | 1.29%   |
| Iraq         | 3         | 1.29%   |
| Denmark      | 3         | 1.29%   |
| Turkey       | 2         | 0.86%   |
| Switzerland  | 2         | 0.86%   |
| Puerto Rico  | 2         | 0.86%   |
| Portugal     | 2         | 0.86%   |
| Nepal        | 2         | 0.86%   |
| Finland      | 2         | 0.86%   |
| Czechia      | 2         | 0.86%   |
| Bangladesh   | 2         | 0.86%   |
| Saudi Arabia | 1         | 0.43%   |
| Peru         | 1         | 0.43%   |
| Pakistan     | 1         | 0.43%   |
| Nigeria      | 1         | 0.43%   |
| New Zealand  | 1         | 0.43%   |
| Namibia      | 1         | 0.43%   |
| Myanmar      | 1         | 0.43%   |
| Morocco      | 1         | 0.43%   |
| Latvia       | 1         | 0.43%   |
| Hungary      | 1         | 0.43%   |
| Greece       | 1         | 0.43%   |
| Georgia      | 1         | 0.43%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Nairobi           | 5         | 2.05%   |
| Dallas            | 4         | 1.64%   |
| Seattle           | 3         | 1.23%   |
| Houston           | 3         | 1.23%   |
| Amsterdam         | 3         | 1.23%   |
| Zurich            | 2         | 0.82%   |
| Sydney            | 2         | 0.82%   |
| Stockholm         | 2         | 0.82%   |
| St Petersburg     | 2         | 0.82%   |
| Ruskin            | 2         | 0.82%   |
| Pretoria          | 2         | 0.82%   |
| Paris             | 2         | 0.82%   |
| New York          | 2         | 0.82%   |
| Mostoles          | 2         | 0.82%   |
| Moscow            | 2         | 0.82%   |
| Melbourne         | 2         | 0.82%   |
| Madrid            | 2         | 0.82%   |
| London            | 2         | 0.82%   |
| Dublin            | 2         | 0.82%   |
| Dresden           | 2         | 0.82%   |
| Dhaka             | 2         | 0.82%   |
| Chicago           | 2         | 0.82%   |
| Camden            | 2         | 0.82%   |
| Berlin            | 2         | 0.82%   |
| Barcelona         | 2         | 0.82%   |
| Baghdad           | 2         | 0.82%   |
| Zagreb            | 1         | 0.41%   |
| West Jordan       | 1         | 0.41%   |
| Washington        | 1         | 0.41%   |
| Warsaw            | 1         | 0.41%   |
| Volgograd         | 1         | 0.41%   |
| Visalia           | 1         | 0.41%   |
| Villa Carlos Paz  | 1         | 0.41%   |
| Vila Nova de Gaia | 1         | 0.41%   |
| Vienna            | 1         | 0.41%   |
| Veitsbronn        | 1         | 0.41%   |
| Västerås        | 1         | 0.41%   |
| Tulare            | 1         | 0.41%   |
| Ts'khinvali       | 1         | 0.41%   |
| Trivandrum        | 1         | 0.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 44        | 52     | 14.86%  |
| Toshiba             | 39        | 43     | 13.18%  |
| WDC                 | 38        | 46     | 12.84%  |
| Unknown             | 23        | 25     | 7.77%   |
| Seagate             | 23        | 23     | 7.77%   |
| Kingston            | 18        | 18     | 6.08%   |
| SanDisk             | 13        | 15     | 4.39%   |
| Hitachi             | 11        | 13     | 3.72%   |
| Crucial             | 10        | 15     | 3.38%   |
| Micron Technology   | 9         | 9      | 3.04%   |
| HGST                | 8         | 10     | 2.7%    |
| SK hynix            | 6         | 6      | 2.03%   |
| China               | 6         | 6      | 2.03%   |
| Intel               | 5         | 9      | 1.69%   |
| Apple               | 5         | 5      | 1.69%   |
| A-DATA Technology   | 5         | 5      | 1.69%   |
| LITEON              | 3         | 3      | 1.01%   |
| YMTC                | 2         | 2      | 0.68%   |
| Team                | 2         | 2      | 0.68%   |
| PNY                 | 2         | 2      | 0.68%   |
| KIOXIA              | 2         | 3      | 0.68%   |
| HUAWEI              | 2         | 2      | 0.68%   |
| W800SH              | 1         | 1      | 0.34%   |
| Transcend           | 1         | 1      | 0.34%   |
| Silicon Motion      | 1         | 1      | 0.34%   |
| S3+                 | 1         | 1      | 0.34%   |
| RZX                 | 1         | 1      | 0.34%   |
| Phison              | 1         | 1      | 0.34%   |
| Patriot             | 1         | 1      | 0.34%   |
| Netac               | 1         | 1      | 0.34%   |
| LITEONIT            | 1         | 1      | 0.34%   |
| Lexar               | 1         | 1      | 0.34%   |
| KingSpec            | 1         | 2      | 0.34%   |
| KingFast            | 1         | 2      | 0.34%   |
| Intenso             | 1         | 2      | 0.34%   |
| Hikvision           | 1         | 1      | 0.34%   |
| Fujitsu             | 1         | 1      | 0.34%   |
| Corsair             | 1         | 2      | 0.34%   |
| BR                  | 1         | 1      | 0.34%   |
| BHT                 | 1         | 1      | 0.34%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Toshiba MQ04ABF100 1TB             | 10        | 3.23%   |
| Toshiba MQ01ABF050 500GB           | 7         | 2.26%   |
| Toshiba MQ01ABD100 1TB             | 5         | 1.61%   |
| Kingston NVMe SSD Drive 512GB      | 5         | 1.61%   |
| Unknown MMC Card  32GB             | 4         | 1.29%   |
| Samsung SSD 860 EVO 500GB          | 4         | 1.29%   |
| WDC WD10SPZX-75Z10T2 1TB           | 3         | 0.97%   |
| Unknown SD/MMC/MS PRO 2GB          | 3         | 0.97%   |
| Toshiba MQ01ABD075 752GB           | 3         | 0.97%   |
| Seagate ST2000LM003 HN-M201RAD 2TB | 3         | 0.97%   |
| Seagate ST1000LM035-1RK172 1TB     | 3         | 0.97%   |
| SanDisk SSD PLUS 1000GB            | 3         | 0.97%   |
| Samsung SSD 850 EVO 250GB          | 3         | 0.97%   |
| HGST HTS721010A9E630 1TB           | 3         | 0.97%   |
| HGST HTS541010A9E680 1TB           | 3         | 0.97%   |
| WDC WD5000LPCX-24C6HT0 500GB       | 2         | 0.65%   |
| WDC WD10SPZX-60Z10T0 1TB           | 2         | 0.65%   |
| Team TM8PS7512G 512GB SSD          | 2         | 0.65%   |
| Seagate ST9250315AS 250GB          | 2         | 0.65%   |
| Seagate ST500LT012-1DG142 500GB    | 2         | 0.65%   |
| Seagate ST320LT007-9ZV142 320GB    | 2         | 0.65%   |
| SanDisk NVMe SSD Drive 256GB       | 2         | 0.65%   |
| SanDisk NVMe SSD Drive 1TB         | 2         | 0.65%   |
| Samsung SSD 980 1TB                | 2         | 0.65%   |
| Samsung NVMe SSD Drive 512GB       | 2         | 0.65%   |
| Samsung NVMe SSD Drive 1024GB      | 2         | 0.65%   |
| Samsung HM500JI 500GB              | 2         | 0.65%   |
| Kingston SV300S37A240G 240GB SSD   | 2         | 0.65%   |
| Kingston SV300S37A120G 120GB SSD   | 2         | 0.65%   |
| Kingston SA400S37240G 240GB SSD    | 2         | 0.65%   |
| Crucial CT500MX500SSD1 500GB       | 2         | 0.65%   |
| Crucial CT1000MX500SSD1 1TB        | 2         | 0.65%   |
| China SATA SSD 120GB               | 2         | 0.65%   |
| Apple SSD SM0256G 256GB            | 2         | 0.65%   |
| YMTC PC005 512GB                   | 1         | 0.32%   |
| YMTC PC005 256GB                   | 1         | 0.32%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 1         | 0.32%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD   | 1         | 0.32%   |
| WDC WDS120G2G0A-00JH30 120GB SSD   | 1         | 0.32%   |
| WDC WDS100T2B0C-00PXH0 1TB         | 1         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 33        | 36     | 29.2%   |
| WDC                 | 29        | 33     | 25.66%  |
| Seagate             | 23        | 23     | 20.35%  |
| Hitachi             | 11        | 13     | 9.73%   |
| HGST                | 8         | 10     | 7.08%   |
| Samsung Electronics | 4         | 4      | 3.54%   |
| Unknown             | 3         | 4      | 2.65%   |
| Fujitsu             | 1         | 1      | 0.88%   |
| ASMedia             | 1         | 1      | 0.88%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 19        | 22     | 20.21%  |
| Kingston            | 9         | 9      | 9.57%   |
| Crucial             | 9         | 14     | 9.57%   |
| SanDisk             | 7         | 8      | 7.45%   |
| China               | 6         | 6      | 6.38%   |
| WDC                 | 5         | 6      | 5.32%   |
| Toshiba             | 4         | 5      | 4.26%   |
| Micron Technology   | 4         | 4      | 4.26%   |
| Apple               | 4         | 4      | 4.26%   |
| LITEON              | 3         | 3      | 3.19%   |
| Team                | 2         | 2      | 2.13%   |
| PNY                 | 2         | 2      | 2.13%   |
| Intel               | 2         | 2      | 2.13%   |
| A-DATA Technology   | 2         | 2      | 2.13%   |
| W800SH              | 1         | 1      | 1.06%   |
| Unknown             | 1         | 1      | 1.06%   |
| Transcend           | 1         | 1      | 1.06%   |
| SK hynix            | 1         | 1      | 1.06%   |
| S3+                 | 1         | 1      | 1.06%   |
| RZX                 | 1         | 1      | 1.06%   |
| Patriot             | 1         | 1      | 1.06%   |
| Netac               | 1         | 1      | 1.06%   |
| LITEONIT            | 1         | 1      | 1.06%   |
| KingSpec            | 1         | 2      | 1.06%   |
| KingFast            | 1         | 1      | 1.06%   |
| Intenso             | 1         | 2      | 1.06%   |
| Corsair             | 1         | 2      | 1.06%   |
| BR                  | 1         | 1      | 1.06%   |
| BHT                 | 1         | 1      | 1.06%   |
| ASMT                | 1         | 1      | 1.06%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 110       | 125    | 38.6%   |
| SSD     | 86        | 108    | 30.18%  |
| NVMe    | 67        | 81     | 23.51%  |
| MMC     | 18        | 20     | 6.32%   |
| Unknown | 4         | 4      | 1.4%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 175       | 221    | 63.87%  |
| NVMe | 67        | 81     | 24.45%  |
| MMC  | 18        | 20     | 6.57%   |
| SAS  | 14        | 16     | 5.11%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 124       | 155    | 63.59%  |
| 0.51-1.0   | 65        | 71     | 33.33%  |
| 1.01-2.0   | 6         | 7      | 3.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 62        | 26.38%  |
| 101-250        | 51        | 21.7%   |
| 501-1000       | 40        | 17.02%  |
| 1001-2000      | 25        | 10.64%  |
| Unknown        | 20        | 8.51%   |
| 21-50          | 13        | 5.53%   |
| 51-100         | 12        | 5.11%   |
| 1-20           | 5         | 2.13%   |
| 2001-3000      | 4         | 1.7%    |
| More than 3000 | 3         | 1.28%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 21-50          | 71        | 29.58%  |
| 51-100         | 45        | 18.75%  |
| 1-20           | 39        | 16.25%  |
| 101-250        | 30        | 12.5%   |
| 251-500        | 25        | 10.42%  |
| Unknown        | 20        | 8.33%   |
| 501-1000       | 7         | 2.92%   |
| More than 3000 | 1         | 0.42%   |
| 1001-2000      | 1         | 0.42%   |
| 0              | 1         | 0.42%   |

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
| Detected | 119       | 174    | 46.67%  |
| Works    | 115       | 142    | 45.1%   |
| Malfunc  | 21        | 22     | 8.24%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 174       | 63.74%  |
| Samsung Electronics          | 25        | 9.16%   |
| AMD                          | 25        | 9.16%   |
| SanDisk                      | 12        | 4.4%    |
| Kingston Technology Company  | 9         | 3.3%    |
| SK hynix                     | 5         | 1.83%   |
| Micron Technology            | 5         | 1.83%   |
| Silicon Motion               | 3         | 1.1%    |
| Nvidia                       | 3         | 1.1%    |
| Yangtze Memory Technologies  | 2         | 0.73%   |
| Toshiba America Info Systems | 2         | 0.73%   |
| KIOXIA                       | 2         | 0.73%   |
| ADATA Technology             | 2         | 0.73%   |
| Realtek Semiconductor        | 1         | 0.37%   |
| Phison Electronics           | 1         | 0.37%   |
| Micron/Crucial Technology    | 1         | 0.37%   |
| Apple                        | 1         | 0.37%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 21        | 7.05%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 20        | 6.71%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 20        | 6.71%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 17        | 5.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 17        | 5.7%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 13        | 4.36%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 10        | 3.36%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 10        | 3.36%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 9         | 3.02%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 8         | 2.68%   |
| Samsung NVMe SSD Controller 980                                                        | 6         | 2.01%   |
| SanDisk WD Blue SN550 NVMe SSD                                                         | 5         | 1.68%   |
| Micron Non-Volatile memory controller                                                  | 5         | 1.68%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 5         | 1.68%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 5         | 1.68%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 5         | 1.68%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 5         | 1.68%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 4         | 1.34%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 4         | 1.34%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 4         | 1.34%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 4         | 1.34%   |
| SK hynix BC511                                                                         | 3         | 1.01%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 3         | 1.01%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 3         | 1.01%   |
| SanDisk Non-Volatile memory controller                                                 | 3         | 1.01%   |
| Kingston Company Company Non-Volatile memory controller                                | 3         | 1.01%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 3         | 1.01%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 3         | 1.01%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 3         | 1.01%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 3         | 1.01%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 3         | 1.01%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 3         | 1.01%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 3         | 1.01%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 3         | 1.01%   |
| Yangtze Memory Non-Volatile memory controller                                          | 2         | 0.67%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller       | 2         | 0.67%   |
| SK hynix Gold P31 SSD                                                                  | 2         | 0.67%   |
| Samsung NVMe SSD Controller SM951/PM951                                                | 2         | 0.67%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 2         | 0.67%   |
| Samsung Electronics SATA controller                                                    | 2         | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 161       | 57.3%   |
| NVMe | 67        | 23.84%  |
| RAID | 30        | 10.68%  |
| IDE  | 23        | 8.19%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 197       | 85.28%  |
| AMD    | 34        | 14.72%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz       | 8         | 3.46%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 6         | 2.6%    |
| Intel Core i5-3210M CPU @ 2.50GHz       | 6         | 2.6%    |
| Intel Core i7-9750H CPU @ 2.60GHz       | 4         | 1.73%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 4         | 1.73%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 4         | 1.73%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 4         | 1.73%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 4         | 1.73%   |
| Intel Core i3-5005U CPU @ 2.00GHz       | 4         | 1.73%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 3         | 1.3%    |
| Intel Core i7-6500U CPU @ 2.50GHz       | 3         | 1.3%    |
| Intel Core i7-10750H CPU @ 2.60GHz      | 3         | 1.3%    |
| Intel Core i5-8250U CPU @ 1.60GHz       | 3         | 1.3%    |
| Intel Core i5-7200U CPU @ 2.50GHz       | 3         | 1.3%    |
| Intel Core i5-3230M CPU @ 2.60GHz       | 3         | 1.3%    |
| Intel Core i5-2450M CPU @ 2.50GHz       | 3         | 1.3%    |
| Intel Core i5-2430M CPU @ 2.40GHz       | 3         | 1.3%    |
| Intel Core i3-1005G1 CPU @ 1.20GHz      | 3         | 1.3%    |
| Intel Core 2 CPU T5600 @ 1.83GHz        | 3         | 1.3%    |
| Intel Celeron CPU N3060 @ 1.60GHz       | 3         | 1.3%    |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 3         | 1.3%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 3         | 1.3%    |
| AMD Ryzen 7 5700U with Radeon Graphics  | 3         | 1.3%    |
| Intel Core i7-8850H CPU @ 2.60GHz       | 2         | 0.87%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 2         | 0.87%   |
| Intel Core i7-4600U CPU @ 2.10GHz       | 2         | 0.87%   |
| Intel Core i7-4510U CPU @ 2.00GHz       | 2         | 0.87%   |
| Intel Core i7-3630QM CPU @ 2.40GHz      | 2         | 0.87%   |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 2         | 0.87%   |
| Intel Core i7-2620M CPU @ 2.70GHz       | 2         | 0.87%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 2         | 0.87%   |
| Intel Core i5-8300H CPU @ 2.30GHz       | 2         | 0.87%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 2         | 0.87%   |
| Intel Core i5-4310U CPU @ 2.00GHz       | 2         | 0.87%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 2         | 0.87%   |
| Intel Core i5-2410M CPU @ 2.30GHz       | 2         | 0.87%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 2         | 0.87%   |
| Intel Core i3-6006U CPU @ 2.00GHz       | 2         | 0.87%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz    | 2         | 0.87%   |
| Intel Celeron J4125 CPU @ 2.00GHz       | 2         | 0.87%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 67        | 29%     |
| Intel Core i7           | 61        | 26.41%  |
| Intel Core i3           | 20        | 8.66%   |
| Other                   | 17        | 7.36%   |
| Intel Celeron           | 12        | 5.19%   |
| AMD Ryzen 7             | 9         | 3.9%    |
| Intel Core 2 Duo        | 8         | 3.46%   |
| AMD Ryzen 5             | 6         | 2.6%    |
| AMD A6                  | 6         | 2.6%    |
| Intel Core 2            | 4         | 1.73%   |
| Intel Pentium           | 3         | 1.3%    |
| AMD E1                  | 3         | 1.3%    |
| Intel Pentium Silver    | 2         | 0.87%   |
| Intel Atom              | 2         | 0.87%   |
| AMD Ryzen 3             | 2         | 0.87%   |
| AMD A4                  | 2         | 0.87%   |
| Intel Pentium Dual-Core | 1         | 0.43%   |
| Intel Core 2 Quad       | 1         | 0.43%   |
| Intel Core 2 Extreme    | 1         | 0.43%   |
| AMD E2                  | 1         | 0.43%   |
| AMD E                   | 1         | 0.43%   |
| AMD C-50                | 1         | 0.43%   |
| AMD Athlon X2           | 1         | 0.43%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 126       | 54.55%  |
| 4      | 69        | 29.87%  |
| 6      | 18        | 7.79%   |
| 8      | 12        | 5.19%   |
| 1      | 3         | 1.3%    |
| 12     | 2         | 0.87%   |
| 14     | 1         | 0.43%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 231       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 176       | 76.19%  |
| 1      | 55        | 23.81%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 226       | 97.84%  |
| Unknown        | 5         | 2.16%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 108       | 45.57%  |
| 0x206a7    | 17        | 7.17%   |
| 0x306a9    | 10        | 4.22%   |
| 0x806ec    | 9         | 3.8%    |
| 0x906ea    | 7         | 2.95%   |
| 0x806e9    | 7         | 2.95%   |
| 0xa0652    | 5         | 2.11%   |
| 0x806ea    | 5         | 2.11%   |
| 0x406e3    | 5         | 2.11%   |
| 0x806c1    | 4         | 1.69%   |
| 0x706e5    | 4         | 1.69%   |
| 0x6f6      | 4         | 1.69%   |
| 0x40651    | 4         | 1.69%   |
| 0x306c3    | 4         | 1.69%   |
| 0x1067a    | 4         | 1.69%   |
| 0x906a3    | 3         | 1.27%   |
| 0x706a8    | 3         | 1.27%   |
| 0x08600106 | 3         | 1.27%   |
| 0x07030105 | 3         | 1.27%   |
| 0x906e9    | 2         | 0.84%   |
| 0x806d1    | 2         | 0.84%   |
| 0x406c4    | 2         | 0.84%   |
| 0x306d4    | 2         | 0.84%   |
| 0x08108109 | 2         | 0.84%   |
| 0x06006705 | 2         | 0.84%   |
| 0x03000027 | 2         | 0.84%   |
| 0x906ed    | 1         | 0.42%   |
| 0x806eb    | 1         | 0.42%   |
| 0x806c2    | 1         | 0.42%   |
| 0x706a1    | 1         | 0.42%   |
| 0x6fd      | 1         | 0.42%   |
| 0x506e3    | 1         | 0.42%   |
| 0x506c9    | 1         | 0.42%   |
| 0x40661    | 1         | 0.42%   |
| 0x20655    | 1         | 0.42%   |
| 0x08608103 | 1         | 0.42%   |
| 0x08108102 | 1         | 0.42%   |
| 0x0810100b | 1         | 0.42%   |
| 0x06001119 | 1         | 0.42%   |
| 0x05000029 | 1         | 0.42%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 47        | 20.35%  |
| SandyBridge      | 27        | 11.69%  |
| IvyBridge        | 19        | 8.23%   |
| Haswell          | 19        | 8.23%   |
| Skylake          | 13        | 5.63%   |
| Broadwell        | 11        | 4.76%   |
| Penryn           | 10        | 4.33%   |
| TigerLake        | 8         | 3.46%   |
| Silvermont       | 8         | 3.46%   |
| IceLake          | 7         | 3.03%   |
| CometLake        | 7         | 3.03%   |
| Unknown          | 7         | 3.03%   |
| Core             | 6         | 2.6%    |
| Zen+             | 5         | 2.16%   |
| Goldmont plus    | 5         | 2.16%   |
| Zen 2            | 4         | 1.73%   |
| Westmere         | 4         | 1.73%   |
| Excavator        | 4         | 1.73%   |
| Puma             | 3         | 1.3%    |
| Jaguar           | 3         | 1.3%    |
| Alderlake Hybrid | 3         | 1.3%    |
| Zen 3            | 2         | 0.87%   |
| Piledriver       | 2         | 0.87%   |
| K10 Llano        | 2         | 0.87%   |
| Bobcat           | 2         | 0.87%   |
| Zen              | 1         | 0.43%   |
| K8 & K10 hybrid  | 1         | 0.43%   |
| Goldmont         | 1         | 0.43%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 181       | 58.96%  |
| Nvidia | 72        | 23.45%  |
| AMD    | 54        | 17.59%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 24        | 7.67%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 17        | 5.43%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 13        | 4.15%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 11        | 3.51%   |
| Intel HD Graphics 5500                                                                   | 10        | 3.19%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 10        | 3.19%   |
| Intel UHD Graphics 620                                                                   | 9         | 2.88%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 2.88%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 8         | 2.56%   |
| Intel HD Graphics 620                                                                    | 7         | 2.24%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 7         | 2.24%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 1.6%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 1.6%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 1.6%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 5         | 1.6%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 1.6%    |
| AMD Lucienne                                                                             | 5         | 1.6%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 1.28%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 4         | 1.28%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 1.28%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 1.28%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 1.28%   |
| AMD Renoir                                                                               | 4         | 1.28%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 3         | 0.96%   |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 0.96%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 3         | 0.96%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 3         | 0.96%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 0.96%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 0.96%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 0.96%   |
| Intel HD Graphics 530                                                                    | 3         | 0.96%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 0.96%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 0.96%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 3         | 0.96%   |
| AMD RV515/M54 [Mobility Radeon X1400]                                                    | 3         | 0.96%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.64%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.64%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 2         | 0.64%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.64%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 108       | 46.75%  |
| Intel + Nvidia | 60        | 25.97%  |
| 1 x AMD        | 37        | 16.02%  |
| Intel + AMD    | 13        | 5.63%   |
| 1 x Nvidia     | 8         | 3.46%   |
| AMD + Nvidia   | 3         | 1.3%    |
| 2 x Nvidia     | 1         | 0.43%   |
| 2 x AMD        | 1         | 0.43%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 209       | 90.48%  |
| Proprietary | 20        | 8.66%   |
| Unknown     | 2         | 0.87%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 182       | 78.11%  |
| 1.01-2.0   | 17        | 7.3%    |
| 0.01-0.5   | 13        | 5.58%   |
| 0.51-1.0   | 10        | 4.29%   |
| 3.01-4.0   | 7         | 3%      |
| 5.01-6.0   | 2         | 0.86%   |
| 7.01-8.0   | 1         | 0.43%   |
| 2.01-3.0   | 1         | 0.43%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 57        | 22.35%  |
| LG Display              | 44        | 17.25%  |
| BOE                     | 39        | 15.29%  |
| Chimei Innolux          | 33        | 12.94%  |
| Samsung Electronics     | 25        | 9.8%    |
| Apple                   | 10        | 3.92%   |
| Chi Mei Optoelectronics | 7         | 2.75%   |
| Sharp                   | 4         | 1.57%   |
| Lenovo                  | 4         | 1.57%   |
| Dell                    | 4         | 1.57%   |
| PANDA                   | 3         | 1.18%   |
| Acer                    | 3         | 1.18%   |
| Sceptre Tech            | 2         | 0.78%   |
| Hewlett-Packard         | 2         | 0.78%   |
| Ancor Communications    | 2         | 0.78%   |
| Unknown (AAA)           | 1         | 0.39%   |
| STD                     | 1         | 0.39%   |
| STA                     | 1         | 0.39%   |
| SANYO                   | 1         | 0.39%   |
| Planar                  | 1         | 0.39%   |
| Philips                 | 1         | 0.39%   |
| Panasonic               | 1         | 0.39%   |
| ONN                     | 1         | 0.39%   |
| NEC Computers           | 1         | 0.39%   |
| Kogan                   | 1         | 0.39%   |
| InfoVision              | 1         | 0.39%   |
| Goldstar                | 1         | 0.39%   |
| Eizo                    | 1         | 0.39%   |
| CSO                     | 1         | 0.39%   |
| BenQ                    | 1         | 0.39%   |
| AOC                     | 1         | 0.39%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 3         | 1.18%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 3         | 1.18%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch        | 3         | 1.18%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch        | 3         | 1.18%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch  | 2         | 0.78%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch  | 2         | 0.78%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch  | 2         | 0.78%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 0.78%   |
| LG Display LCD Monitor LGD0390 1600x900 382x215mm 17.3-inch           | 2         | 0.78%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 2         | 0.78%   |
| LG Display LCD Monitor LGD01E9 1920x1080 345x194mm 15.6-inch          | 2         | 0.78%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch      | 2         | 0.78%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 2         | 0.78%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 2         | 0.78%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch       | 2         | 0.78%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                 | 2         | 0.78%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch        | 2         | 0.78%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.78%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch         | 2         | 0.78%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 2         | 0.78%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch         | 2         | 0.78%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch         | 2         | 0.78%   |
| Unknown (AAA) LCDTV AAA0042 1360x768 890x500mm 40.2-inch              | 1         | 0.39%   |
| STD HDMI TV STD00C7 1920x1080 698x392mm 31.5-inch                     | 1         | 0.39%   |
| STA XR140EA1T STA0450 1366x768 310x174mm 14.0-inch                    | 1         | 0.39%   |
| Sharp LCD Monitor SHP1542 1920x1080 309x174mm 14.0-inch               | 1         | 0.39%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch               | 1         | 0.39%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch               | 1         | 0.39%   |
| Sharp LCD Monitor SHP143A 3840x2160 346x194mm 15.6-inch               | 1         | 0.39%   |
| Sceptre Tech Sceptre F24 SPT09AB 1920x1080 521x293mm 23.5-inch        | 1         | 0.39%   |
| Sceptre Tech Sceptre B30 SPT0BC2 2560x1080 690x291mm 29.5-inch        | 1         | 0.39%   |
| SANYO LCD SAN0B51 1920x540                                            | 1         | 0.39%   |
| Samsung Electronics SyncMaster SAM0589 1920x1080 521x293mm 23.5-inch  | 1         | 0.39%   |
| Samsung Electronics SMT24A550 SAM07B5 1920x1080 531x299mm 24.0-inch   | 1         | 0.39%   |
| Samsung Electronics S27E510 SAM0C5F 1920x1080 600x340mm 27.2-inch     | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 353x198mm 15.9-inch  | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch  | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC4145 1366x768 309x174mm 14.0-inch  | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC3942 1366x768 309x174mm 14.0-inch  | 1         | 0.39%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 102       | 42.15%  |
| 1366x768 (WXGA)    | 86        | 35.54%  |
| 1600x900 (HD+)     | 15        | 6.2%    |
| 1280x800 (WXGA)    | 10        | 4.13%   |
| 1440x900 (WXGA+)   | 5         | 2.07%   |
| 3840x2160 (4K)     | 4         | 1.65%   |
| 1680x1050 (WSXGA+) | 4         | 1.65%   |
| 2560x1600          | 3         | 1.24%   |
| 2880x1800          | 2         | 0.83%   |
| 2560x1440 (QHD)    | 2         | 0.83%   |
| 2160x1440          | 2         | 0.83%   |
| 1920x1200 (WUXGA)  | 2         | 0.83%   |
| 1024x768 (XGA)     | 2         | 0.83%   |
| 2560x1080          | 1         | 0.41%   |
| 1920x540           | 1         | 0.41%   |
| 1280x1024 (SXGA)   | 1         | 0.41%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 107       | 42.29%  |
| 14      | 37        | 14.62%  |
| 13      | 33        | 13.04%  |
| 17      | 24        | 9.49%   |
| 12      | 10        | 3.95%   |
| 24      | 6         | 2.37%   |
| 11      | 5         | 1.98%   |
| 31      | 4         | 1.58%   |
| 27      | 4         | 1.58%   |
| 21      | 4         | 1.58%   |
| 23      | 3         | 1.19%   |
| 22      | 3         | 1.19%   |
| 16      | 3         | 1.19%   |
| 19      | 2         | 0.79%   |
| 18      | 2         | 0.79%   |
| 54      | 1         | 0.4%    |
| 48      | 1         | 0.4%    |
| 40      | 1         | 0.4%    |
| 32      | 1         | 0.4%    |
| 29      | 1         | 0.4%    |
| Unknown | 1         | 0.4%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 165       | 65.48%  |
| 351-400     | 28        | 11.11%  |
| 201-300     | 27        | 10.71%  |
| 501-600     | 13        | 5.16%   |
| 401-500     | 9         | 3.57%   |
| 601-700     | 5         | 1.98%   |
| 1001-1500   | 2         | 0.79%   |
| 801-900     | 1         | 0.4%    |
| 701-800     | 1         | 0.4%    |
| Unknown     | 1         | 0.4%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 201       | 85.9%   |
| 16/10 | 26        | 11.11%  |
| 4/3   | 2         | 0.85%   |
| 3/2   | 2         | 0.85%   |
| 6/5   | 1         | 0.43%   |
| 32/9  | 1         | 0.43%   |
| 21/9  | 1         | 0.43%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 108       | 42.69%  |
| 81-90          | 60        | 23.72%  |
| 121-130        | 21        | 8.3%    |
| 201-250        | 14        | 5.53%   |
| 71-80          | 10        | 3.95%   |
| 61-70          | 10        | 3.95%   |
| 51-60          | 5         | 1.98%   |
| 351-500        | 5         | 1.98%   |
| 301-350        | 5         | 1.98%   |
| 131-140        | 3         | 1.19%   |
| More than 1000 | 2         | 0.79%   |
| 251-300        | 2         | 0.79%   |
| 151-200        | 2         | 0.79%   |
| 141-150        | 2         | 0.79%   |
| 111-120        | 2         | 0.79%   |
| 501-1000       | 1         | 0.4%    |
| Unknown        | 1         | 0.4%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 105       | 41.83%  |
| 101-120       | 89        | 35.46%  |
| 51-100        | 36        | 14.34%  |
| 161-240       | 14        | 5.58%   |
| More than 240 | 3         | 1.2%    |
| 1-50          | 3         | 1.2%    |
| Unknown       | 1         | 0.4%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 199       | 85.41%  |
| 2     | 28        | 12.02%  |
| 3     | 4         | 1.72%   |
| 0     | 2         | 0.86%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 130       | 33.33%  |
| Realtek Semiconductor                  | 124       | 31.79%  |
| Qualcomm Atheros                       | 50        | 12.82%  |
| Broadcom                               | 24        | 6.15%   |
| MediaTek                               | 7         | 1.79%   |
| Broadcom Limited                       | 7         | 1.79%   |
| TP-Link                                | 6         | 1.54%   |
| Samsung Electronics                    | 6         | 1.54%   |
| Huawei Technologies                    | 5         | 1.28%   |
| Qualcomm Atheros Communications        | 4         | 1.03%   |
| Xiaomi                                 | 3         | 0.77%   |
| Ralink Technology                      | 3         | 0.77%   |
| NetGear                                | 3         | 0.77%   |
| ASUSTek Computer                       | 3         | 0.77%   |
| Nvidia                                 | 2         | 0.51%   |
| ASIX Electronics                       | 2         | 0.51%   |
| Apple                                  | 2         | 0.51%   |
| ZyXEL Communications                   | 1         | 0.26%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.26%   |
| Sagem                                  | 1         | 0.26%   |
| Ralink                                 | 1         | 0.26%   |
| Linksys                                | 1         | 0.26%   |
| Lenovo                                 | 1         | 0.26%   |
| Ericsson Business Mobile Networks      | 1         | 0.26%   |
| Belkin Components                      | 1         | 0.26%   |
| Arduino SA                             | 1         | 0.26%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 63        | 13.32%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 29        | 6.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 14        | 2.96%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 12        | 2.54%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 9         | 1.9%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 1.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 8         | 1.69%   |
| Intel Wireless 8265 / 8275                                        | 8         | 1.69%   |
| Intel Wireless 7265                                               | 8         | 1.69%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 8         | 1.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 7         | 1.48%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 7         | 1.48%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 7         | 1.48%   |
| Intel Wireless 7260                                               | 7         | 1.48%   |
| Intel Wi-Fi 6 AX200                                               | 7         | 1.48%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 7         | 1.48%   |
| Intel Wireless 3165                                               | 6         | 1.27%   |
| Intel Wi-Fi 6 AX201                                               | 6         | 1.27%   |
| Intel Ethernet Connection I218-LM                                 | 6         | 1.27%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 6         | 1.27%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 5         | 1.06%   |
| Realtek 802.11ac NIC                                              | 5         | 1.06%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 5         | 1.06%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 1.06%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 0.85%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 4         | 0.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 0.85%   |
| Qualcomm Atheros AR9271 802.11n                                   | 4         | 0.85%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4         | 0.85%   |
| Intel Wireless 8260                                               | 4         | 0.85%   |
| Intel Wireless 3160                                               | 4         | 0.85%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 4         | 0.85%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4         | 0.85%   |
| Intel Centrino Advanced-N 6235                                    | 4         | 0.85%   |
| Broadcom BCM43142 802.11b/g/n                                     | 4         | 0.85%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 3         | 0.63%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 3         | 0.63%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 3         | 0.63%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 0.63%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 3         | 0.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 126       | 47.37%  |
| Realtek Semiconductor             | 46        | 17.29%  |
| Qualcomm Atheros                  | 38        | 14.29%  |
| Broadcom                          | 20        | 7.52%   |
| TP-Link                           | 6         | 2.26%   |
| Broadcom Limited                  | 6         | 2.26%   |
| MediaTek                          | 5         | 1.88%   |
| Qualcomm Atheros Communications   | 4         | 1.5%    |
| Ralink Technology                 | 3         | 1.13%   |
| NetGear                           | 3         | 1.13%   |
| ASUSTek Computer                  | 3         | 1.13%   |
| ZyXEL Communications              | 1         | 0.38%   |
| Sagem                             | 1         | 0.38%   |
| Ralink                            | 1         | 0.38%   |
| Linksys                           | 1         | 0.38%   |
| Ericsson Business Mobile Networks | 1         | 0.38%   |
| Belkin Components                 | 1         | 0.38%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 12        | 4.51%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 9         | 3.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 8         | 3.01%   |
| Intel Wireless 8265 / 8275                                     | 8         | 3.01%   |
| Intel Wireless 7265                                            | 8         | 3.01%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 8         | 3.01%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 7         | 2.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 7         | 2.63%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 7         | 2.63%   |
| Intel Wireless 7260                                            | 7         | 2.63%   |
| Intel Wi-Fi 6 AX200                                            | 7         | 2.63%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 7         | 2.63%   |
| Intel Wireless 3165                                            | 6         | 2.26%   |
| Intel Wi-Fi 6 AX201                                            | 6         | 2.26%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 6         | 2.26%   |
| Realtek 802.11ac NIC                                           | 5         | 1.88%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 5         | 1.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 4         | 1.5%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 4         | 1.5%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 1.5%    |
| Qualcomm Atheros AR9271 802.11n                                | 4         | 1.5%    |
| Intel Wireless 8260                                            | 4         | 1.5%    |
| Intel Wireless 3160                                            | 4         | 1.5%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 4         | 1.5%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 4         | 1.5%    |
| Intel Centrino Advanced-N 6235                                 | 4         | 1.5%    |
| Broadcom BCM43142 802.11b/g/n                                  | 4         | 1.5%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 3         | 1.13%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 3         | 1.13%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 3         | 1.13%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 3         | 1.13%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 3         | 1.13%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 3         | 1.13%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 3         | 1.13%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 1.13%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 2         | 0.75%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 2         | 0.75%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 2         | 0.75%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 2         | 0.75%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 107       | 53.77%  |
| Intel                 | 43        | 21.61%  |
| Qualcomm Atheros      | 20        | 10.05%  |
| Broadcom              | 8         | 4.02%   |
| Samsung Electronics   | 6         | 3.02%   |
| Xiaomi                | 3         | 1.51%   |
| Nvidia                | 2         | 1.01%   |
| MediaTek              | 2         | 1.01%   |
| Huawei Technologies   | 2         | 1.01%   |
| ASIX Electronics      | 2         | 1.01%   |
| Apple                 | 2         | 1.01%   |
| Lenovo                | 1         | 0.5%    |
| Broadcom Limited      | 1         | 0.5%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 63        | 31.19%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 29        | 14.36%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 14        | 6.93%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 3.96%   |
| Intel Ethernet Connection I218-LM                                 | 6         | 2.97%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 5         | 2.48%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 5         | 2.48%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4         | 1.98%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 1.49%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 3         | 1.49%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 1.49%   |
| Intel Ethernet Connection (6) I219-V                              | 3         | 1.49%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.49%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 3         | 1.49%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.99%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.99%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.99%   |
| MediaTek Nokia 5.1 Plus                                           | 2         | 0.99%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.99%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.99%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.99%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 0.99%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.99%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.5%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.5%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.5%    |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.5%    |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.5%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.5%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.5%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.5%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.5%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.5%    |
| Nvidia MCP89 Ethernet                                             | 1         | 0.5%    |
| Nvidia MCP79 Ethernet                                             | 1         | 0.5%    |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 0.5%    |
| Intel PRO/100 VE Network Connection                               | 1         | 0.5%    |
| Intel Ethernet controller                                         | 1         | 0.5%    |
| Intel Ethernet Connection I219-V                                  | 1         | 0.5%    |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.5%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 229       | 54.27%  |
| Ethernet | 188       | 44.55%  |
| Modem    | 4         | 0.95%   |
| Unknown  | 1         | 0.24%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 191       | 77.64%  |
| Ethernet | 54        | 21.95%  |
| Unknown  | 1         | 0.41%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 168       | 72.73%  |
| 1     | 58        | 25.11%  |
| 0     | 3         | 1.3%    |
| 3     | 2         | 0.87%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Notebooks | Percent |
|---------|-----------|---------|
| No      | 192       | 81.7%   |
| Yes     | 42        | 17.87%  |
| Unknown | 1         | 0.43%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 95        | 50.26%  |
| Qualcomm Atheros Communications | 21        | 11.11%  |
| Realtek Semiconductor           | 18        | 9.52%   |
| Broadcom                        | 14        | 7.41%   |
| Lite-On Technology              | 7         | 3.7%    |
| Foxconn / Hon Hai               | 7         | 3.7%    |
| Apple                           | 7         | 3.7%    |
| IMC Networks                    | 4         | 2.12%   |
| Cambridge Silicon Radio         | 4         | 2.12%   |
| MediaTek                        | 3         | 1.59%   |
| Dell                            | 3         | 1.59%   |
| Toshiba                         | 2         | 1.06%   |
| Realtek                         | 1         | 0.53%   |
| Ralink                          | 1         | 0.53%   |
| Dynex                           | 1         | 0.53%   |
| Alps Electric                   | 1         | 0.53%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 37        | 19.58%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 21        | 11.11%  |
| Intel AX201 Bluetooth                                                               | 20        | 10.58%  |
| Realtek Bluetooth Radio                                                             | 12        | 6.35%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 9         | 4.76%   |
| Intel AX200 Bluetooth                                                               | 7         | 3.7%    |
| Realtek  Bluetooth 4.2 Adapter                                                      | 5         | 2.65%   |
| Apple Bluetooth Host Controller                                                     | 5         | 2.65%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 4         | 2.12%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 4         | 2.12%   |
| Broadcom HP Portable SoftSailing                                                    | 4         | 2.12%   |
| Qualcomm Atheros Bluetooth                                                          | 3         | 1.59%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 1.59%   |
| MediaTek Wireless_Device                                                            | 3         | 1.59%   |
| Dell DW375 Bluetooth Module                                                         | 3         | 1.59%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 3         | 1.59%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 2         | 1.06%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 1.06%   |
| Lite-On Wireless_Device                                                             | 2         | 1.06%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 2         | 1.06%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 2         | 1.06%   |
| IMC Networks Bluetooth Radio                                                        | 2         | 1.06%   |
| IMC Networks Bluetooth Device                                                       | 2         | 1.06%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 1.06%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 1.06%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 2         | 1.06%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 2         | 1.06%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 2         | 1.06%   |
| Apple Bluetooth USB Host Controller                                                 | 2         | 1.06%   |
| Toshiba Bluetooth USB Host Controller                                               | 1         | 0.53%   |
| Toshiba BCM43142A0                                                                  | 1         | 0.53%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.53%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.53%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.53%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.53%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.53%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.53%   |
| Lite-On Bluetooth Radio                                                             | 1         | 0.53%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 0.53%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 0.53%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor    | Notebooks | Percent |
|-----------|-----------|---------|
| Intel     | 191       | 70.22%  |
| Nvidia    | 39        | 14.34%  |
| AMD       | 38        | 13.97%  |
| Lenovo    | 1         | 0.37%   |
| Guillemot | 1         | 0.37%   |
| GN Netcom | 1         | 0.37%   |
| Apple     | 1         | 0.37%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 27        | 8.13%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 24        | 7.23%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 22        | 6.63%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 16        | 4.82%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 13        | 3.92%   |
| Intel 8 Series HD Audio Controller                                                                | 13        | 3.92%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 11        | 3.31%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 11        | 3.31%   |
| Intel Cannon Lake PCH cAVS                                                                        | 11        | 3.31%   |
| Intel Broadwell-U Audio Controller                                                                | 11        | 3.31%   |
| AMD FCH Azalia Controller                                                                         | 10        | 3.01%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 9         | 2.71%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 8         | 2.41%   |
| Intel Comet Lake PCH cAVS                                                                         | 7         | 2.11%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 1.81%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 1.81%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 1.81%   |
| AMD Kabini HDMI/DP Audio                                                                          | 6         | 1.81%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 1.51%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 5         | 1.51%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 1.51%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 1.51%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1.2%    |
| Nvidia TU106 High Definition Audio Controller                                                     | 4         | 1.2%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 1.2%    |
| Nvidia Audio device                                                                               | 4         | 1.2%    |
| Intel Tiger Lake-H HD Audio Controller                                                            | 4         | 1.2%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 1.2%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 1.2%    |
| AMD High Definition Audio Controller                                                              | 4         | 1.2%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 1.2%    |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 0.9%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.9%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 0.9%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 3         | 0.9%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 0.9%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 0.9%    |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 3         | 0.9%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 0.9%    |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 53        | 30.64%  |
| SK hynix            | 31        | 17.92%  |
| Micron Technology   | 28        | 16.18%  |
| Crucial             | 11        | 6.36%   |
| Kingston            | 10        | 5.78%   |
| Unknown             | 8         | 4.62%   |
| Ramaxel Technology  | 7         | 4.05%   |
| Elpida              | 7         | 4.05%   |
| Unknown (ABCD)      | 3         | 1.73%   |
| Corsair             | 3         | 1.73%   |
| Team                | 2         | 1.16%   |
| Nanya Technology    | 2         | 1.16%   |
| G.Skill             | 2         | 1.16%   |
| A-DATA Technology   | 2         | 1.16%   |
| Teikon              | 1         | 0.58%   |
| Smart               | 1         | 0.58%   |
| Saikano             | 1         | 0.58%   |
| PNY                 | 1         | 0.58%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 3.31%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 3.31%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 2.21%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 3         | 1.66%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 3         | 1.66%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 3         | 1.66%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 1.66%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 1.66%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 3         | 1.66%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 3         | 1.66%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 2         | 1.1%    |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 1.1%    |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 1.1%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 1.1%    |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 2         | 1.1%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.1%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1.1%    |
| Samsung RAM M4 70T2953CZ3-CE6 1GB SODIMM DDR 667MT/s             | 2         | 1.1%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 2         | 1.1%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8192MB SODIMM DDR4 3200MT/s          | 2         | 1.1%    |
| Micron RAM 16JSF51264HZ-1G4D1 4096MB SODIMM DDR3 1334MT/s        | 2         | 1.1%    |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                       | 2         | 1.1%    |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.55%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 1         | 0.55%   |
| Unknown RAM Module 4096MB SODIMM 1066MT/s                        | 1         | 0.55%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.55%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 0.55%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                       | 1         | 0.55%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 1         | 0.55%   |
| Teikon RAM TMT451S6BFR8A-PBHJ 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.55%   |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s             | 1         | 0.55%   |
| Team RAM TEAMGROUP-SD3-1600 8GB SODIMM DDR3 1600MT/s             | 1         | 0.55%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.55%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s             | 1         | 0.55%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1066MT/s                  | 1         | 0.55%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1066MT/s                     | 1         | 0.55%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                    | 1         | 0.55%   |
| SK hynix RAM HMT851S6AMR6R-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.55%   |
| SK hynix RAM HMT851S6AMR6A-PB 4GB Chip DDR3 1600MT/s             | 1         | 0.55%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.55%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 65        | 44.52%  |
| DDR3    | 59        | 40.41%  |
| LPDDR4  | 9         | 6.16%   |
| LPDDR3  | 5         | 3.42%   |
| DDR2    | 4         | 2.74%   |
| SDRAM   | 1         | 0.68%   |
| DDR5    | 1         | 0.68%   |
| DDR     | 1         | 0.68%   |
| Unknown | 1         | 0.68%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 133       | 91.1%   |
| Row Of Chips | 11        | 7.53%   |
| Chip         | 1         | 0.68%   |
| Unknown      | 1         | 0.68%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 63        | 40.13%  |
| 8192  | 51        | 32.48%  |
| 16384 | 19        | 12.1%   |
| 2048  | 14        | 8.92%   |
| 1024  | 7         | 4.46%   |
| 32768 | 3         | 1.91%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 40        | 24.84%  |
| 1600    | 39        | 24.22%  |
| 3200    | 21        | 13.04%  |
| 1334    | 13        | 8.07%   |
| 2400    | 12        | 7.45%   |
| 2133    | 7         | 4.35%   |
| 1333    | 6         | 3.73%   |
| 3266    | 3         | 1.86%   |
| 1867    | 3         | 1.86%   |
| 1067    | 3         | 1.86%   |
| 1066    | 3         | 1.86%   |
| 667     | 3         | 1.86%   |
| Unknown | 2         | 1.24%   |
| 8400    | 1         | 0.62%   |
| 4800    | 1         | 0.62%   |
| 4267    | 1         | 0.62%   |
| 2048    | 1         | 0.62%   |
| 800     | 1         | 0.62%   |
| 533     | 1         | 0.62%   |

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
| Chicony Electronics                    | 63        | 29.86%  |
| Acer                                   | 24        | 11.37%  |
| IMC Networks                           | 21        | 9.95%   |
| Microdia                               | 18        | 8.53%   |
| Sunplus Innovation Technology          | 14        | 6.64%   |
| Realtek Semiconductor                  | 10        | 4.74%   |
| Quanta                                 | 9         | 4.27%   |
| Apple                                  | 9         | 4.27%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 2.84%   |
| Ricoh                                  | 5         | 2.37%   |
| Syntek                                 | 4         | 1.9%    |
| Suyin                                  | 4         | 1.9%    |
| Samsung Electronics                    | 4         | 1.9%    |
| Luxvisions Innotech Limited            | 4         | 1.9%    |
| Silicon Motion                         | 3         | 1.42%   |
| Lite-On Technology                     | 3         | 1.42%   |
| Alcor Micro                            | 3         | 1.42%   |
| Importek                               | 2         | 0.95%   |
| Primax Electronics                     | 1         | 0.47%   |
| LG Electronics                         | 1         | 0.47%   |
| icSpring                               | 1         | 0.47%   |
| Goertek Electronics                    | 1         | 0.47%   |
| ALi                                    | 1         | 0.47%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony integrated camera                           | 9         | 4.27%   |
| Acer HD Webcam                                      | 7         | 3.32%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 6         | 2.84%   |
| IMC Networks Integrated Camera                      | 6         | 2.84%   |
| Chicony HD Webcam                                   | 6         | 2.84%   |
| Chicony HD User Facing                              | 6         | 2.84%   |
| Realtek Integrated_Webcam_HD                        | 5         | 2.37%   |
| Microdia Integrated_Webcam_HD                       | 5         | 2.37%   |
| Chicony HP Truevision HD                            | 5         | 2.37%   |
| Sunplus Integrated_Webcam_HD                        | 4         | 1.9%    |
| Samsung Galaxy A5 (MTP)                             | 4         | 1.9%    |
| Chicony USB2.0 Camera                               | 4         | 1.9%    |
| Acer EasyCamera                                     | 4         | 1.9%    |
| Syntek Integrated Camera                            | 3         | 1.42%   |
| Quanta HP TrueVision HD Camera                      | 3         | 1.42%   |
| Microdia Webcam Vitade AF                           | 3         | 1.42%   |
| Microdia Integrated Webcam                          | 3         | 1.42%   |
| IMC Networks HD Camera                              | 3         | 1.42%   |
| Chicony USB2.0 HD UVC WebCam                        | 3         | 1.42%   |
| Apple iPhone5/5C/5S/6                               | 3         | 1.42%   |
| Alcor Micro SHUNCCM2MP                              | 3         | 1.42%   |
| Acer SunplusIT Integrated Camera                    | 3         | 1.42%   |
| Sunplus HD WebCam                                   | 2         | 0.95%   |
| Realtek Integrated Webcam                           | 2         | 0.95%   |
| Quanta HD User Facing                               | 2         | 0.95%   |
| Microdia PC Microscope camera                       | 2         | 0.95%   |
| Microdia Laptop_Integrated_Webcam_HD                | 2         | 0.95%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 2         | 0.95%   |
| Lite-On HP Wide Vision HD Camera                    | 2         | 0.95%   |
| Chicony USB2.0 VGA UVC WebCam                       | 2         | 0.95%   |
| Chicony TOSHIBA Web Camera - HD                     | 2         | 0.95%   |
| Chicony Integrated HP HD Webcam                     | 2         | 0.95%   |
| Chicony Integrated Camera [ThinkPad]                | 2         | 0.95%   |
| Chicony Integrated Camera (1280x720@30)             | 2         | 0.95%   |
| Chicony HP HD Webcam [Fixed]                        | 2         | 0.95%   |
| Chicony HP HD Camera                                | 2         | 0.95%   |
| Chicony FJ Camera                                   | 2         | 0.95%   |
| Chicony EasyCamera                                  | 2         | 0.95%   |
| Apple FaceTime HD Camera                            | 2         | 0.95%   |
| Apple Built-in iSight                               | 2         | 0.95%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 17        | 44.74%  |
| Synaptics                  | 9         | 23.68%  |
| Shenzhen Goodix Technology | 4         | 10.53%  |
| Elan Microelectronics      | 3         | 7.89%   |
| LighTuning Technology      | 2         | 5.26%   |
| AuthenTec                  | 2         | 5.26%   |
| Upek                       | 1         | 2.63%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 7.89%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 7.89%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 7.89%   |
| Shenzhen Goodix  FingerPrint Device                                        | 3         | 7.89%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 2         | 5.26%   |
| Validity Sensors VFS491                                                    | 2         | 5.26%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 5.26%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 5.26%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 5.26%   |
| Elan ELAN:Fingerprint                                                      | 2         | 5.26%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 2.63%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 2.63%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.63%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 2.63%   |
| Synaptics  WBDI                                                            | 1         | 2.63%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 2.63%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 2.63%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 2.63%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 2.63%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 2.63%   |
| Elan ELAN:ARM-M4                                                           | 1         | 2.63%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 2.63%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 2.63%   |
| Unknown                                                                    | 1         | 2.63%   |

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
| 0     | 139       | 59.15%  |
| 1     | 76        | 32.34%  |
| 2     | 18        | 7.66%   |
| 3     | 2         | 0.85%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 39        | 34.51%  |
| Graphics card         | 17        | 15.04%  |
| Chipcard              | 15        | 13.27%  |
| Net/wireless          | 14        | 12.39%  |
| Multimedia controller | 10        | 8.85%   |
| Camera                | 7         | 6.19%   |
| Storage               | 5         | 4.42%   |
| Network               | 3         | 2.65%   |
| Modem                 | 1         | 0.88%   |
| Card reader           | 1         | 0.88%   |
| Bluetooth             | 1         | 0.88%   |

