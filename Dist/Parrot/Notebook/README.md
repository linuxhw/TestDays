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

Total: 285

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| MSI           | GS66 Stealth 10UG           | [c57bcaa35d](https://linux-hardware.org/?probe=c57bcaa35d) | Sep 19, 2021 |
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
| Parrot 5.0   | 63        | 29.86%  |
| Parrot 4.11  | 60        | 28.44%  |
| Parrot 4.10  | 44        | 20.85%  |
| Parrot 4.8   | 15        | 7.11%   |
| Parrot 4.9   | 13        | 6.16%   |
| Parrot 4.7   | 10        | 4.74%   |
| Parrot 4.6   | 2         | 0.95%   |
| Parrot 4.5   | 1         | 0.47%   |
| Parrot 4.4   | 1         | 0.47%   |
| Parrot 4.2.2 | 1         | 0.47%   |
| Parrot 3.10  | 1         | 0.47%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Parrot | 199       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.14.0-9parrot1-amd64    | 35        | 16.36%  |
| 5.16.0-12parrot1-amd64   | 28        | 13.08%  |
| 5.7.0-2parrot2-amd64     | 26        | 12.15%  |
| 5.10.0-6parrot1-amd64    | 23        | 10.75%  |
| 5.10.0-8parrot1-amd64    | 14        | 6.54%   |
| 5.5.0-1parrot1-amd64     | 12        | 5.61%   |
| 5.4.0-4parrot1-amd64     | 11        | 5.14%   |
| 5.6.0-2parrot1-amd64     | 9         | 4.21%   |
| 5.14.0-2parrot1-amd64    | 8         | 3.74%   |
| 5.9.0-2parrot1-amd64     | 7         | 3.27%   |
| 5.15.0-15parrot1-amd64   | 5         | 2.34%   |
| 5.4.0-2parrot1-amd64     | 3         | 1.4%    |
| 5.2.0-2parrot1-amd64     | 3         | 1.4%    |
| 5.10.0-5parrot1-amd64    | 3         | 1.4%    |
| 5.10.0-3parrot1-amd64    | 3         | 1.4%    |
| 4.19.0-parrot4-28t-amd64 | 3         | 1.4%    |
| 5.8.0-2parrot1-amd64     | 2         | 0.93%   |
| 5.8.0-1parrot1-amd64     | 2         | 0.93%   |
| 5.4.0-3parrot1-amd64     | 2         | 0.93%   |
| 4.18.0-parrot10-amd64    | 2         | 0.93%   |
| 5.7.0-rc6-galliumos      | 1         | 0.47%   |
| 5.4.0-2parrot1-686-pae   | 1         | 0.47%   |
| 5.4.0-1parrot1-amd64     | 1         | 0.47%   |
| 5.3.0-3parrot3-amd64     | 1         | 0.47%   |
| 5.3.0-3parrot3-686-pae   | 1         | 0.47%   |
| 5.3.0-1parrot1-amd64     | 1         | 0.47%   |
| 5.15.0-5parrot1-amd64    | 1         | 0.47%   |
| 5.10.0-kali6-amd64       | 1         | 0.47%   |
| 5.10.0-6parrot1-rt-amd64 | 1         | 0.47%   |
| 5.1.0-parrot1-3t-amd64   | 1         | 0.47%   |
| 4.19.0-parrot1-13t-amd64 | 1         | 0.47%   |
| 4.14.0-parrot7-amd64     | 1         | 0.47%   |
| Unknown                  | 1         | 0.47%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 45        | 21.13%  |
| 5.14.0  | 42        | 19.72%  |
| 5.16.0  | 28        | 13.15%  |
| 5.7.0   | 27        | 12.68%  |
| 5.4.0   | 18        | 8.45%   |
| 5.5.0   | 12        | 5.63%   |
| 5.6.0   | 9         | 4.23%   |
| 5.9.0   | 7         | 3.29%   |
| 5.15.0  | 6         | 2.82%   |
| 5.8.0   | 4         | 1.88%   |
| 4.19.0  | 4         | 1.88%   |
| 5.3.0   | 3         | 1.41%   |
| 5.2.0   | 3         | 1.41%   |
| 4.18.0  | 2         | 0.94%   |
| 5.1.0   | 1         | 0.47%   |
| 4.14.0  | 1         | 0.47%   |
| Unknown | 1         | 0.47%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 45        | 21.13%  |
| 5.14    | 42        | 19.72%  |
| 5.16    | 28        | 13.15%  |
| 5.7     | 27        | 12.68%  |
| 5.4     | 18        | 8.45%   |
| 5.5     | 12        | 5.63%   |
| 5.6     | 9         | 4.23%   |
| 5.9     | 7         | 3.29%   |
| 5.15    | 6         | 2.82%   |
| 5.8     | 4         | 1.88%   |
| 4.19    | 4         | 1.88%   |
| 5.3     | 3         | 1.41%   |
| 5.2     | 3         | 1.41%   |
| 4.18    | 2         | 0.94%   |
| 5.1     | 1         | 0.47%   |
| 4.14    | 1         | 0.47%   |
| Unknown | 1         | 0.47%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 198       | 99.5%   |
| i686   | 1         | 0.5%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| MATE          | 126       | 62.07%  |
| KDE5          | 42        | 20.69%  |
| Unknown       | 16        | 7.88%   |
| KDE           | 13        | 6.4%    |
| XFCE          | 4         | 1.97%   |
| LXDE          | 1         | 0.49%   |
| GNOME Classic | 1         | 0.49%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 197       | 98.99%  |
| Wayland | 1         | 0.5%    |
| Unknown | 1         | 0.5%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 78        | 38.05%  |
| LightDM | 70        | 34.15%  |
| TDM     | 50        | 24.39%  |
| GDM     | 5         | 2.44%   |
| SDDM    | 2         | 0.98%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 101       | 50.5%   |
| en_GB   | 20        | 10%     |
| Unknown | 14        | 7%      |
| fr_FR   | 10        | 5%      |
| ru_RU   | 7         | 3.5%    |
| es_ES   | 7         | 3.5%    |
| de_DE   | 6         | 3%      |
| pt_BR   | 5         | 2.5%    |
| pl_PL   | 5         | 2.5%    |
| en_IN   | 4         | 2%      |
| en_AU   | 4         | 2%      |
| tr_TR   | 1         | 0.5%    |
| pt_PT   | 1         | 0.5%    |
| nl_BE   | 1         | 0.5%    |
| it_IT   | 1         | 0.5%    |
| id_ID   | 1         | 0.5%    |
| fr_CA   | 1         | 0.5%    |
| es_PE   | 1         | 0.5%    |
| es_MX   | 1         | 0.5%    |
| es_CO   | 1         | 0.5%    |
| es_CL   | 1         | 0.5%    |
| es_AR   | 1         | 0.5%    |
| en_ZA   | 1         | 0.5%    |
| en_NZ   | 1         | 0.5%    |
| en_NG   | 1         | 0.5%    |
| en_DK   | 1         | 0.5%    |
| cs_CZ   | 1         | 0.5%    |
| C       | 1         | 0.5%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 126       | 62.69%  |
| EFI  | 75        | 37.31%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Btrfs   | 142       | 69.95%  |
| Ext4    | 40        | 19.7%   |
| Xfs     | 8         | 3.94%   |
| Unknown | 7         | 3.45%   |
| Overlay | 6         | 2.96%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 89        | 44.06%  |
| GPT     | 71        | 35.15%  |
| MBR     | 42        | 20.79%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 175       | 87.5%   |
| Yes       | 25        | 12.5%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 136       | 68%     |
| Yes       | 64        | 32%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 41        | 20.6%   |
| Lenovo                | 37        | 18.59%  |
| Dell                  | 33        | 16.58%  |
| ASUSTek Computer      | 18        | 9.05%   |
| Acer                  | 13        | 6.53%   |
| MSI                   | 10        | 5.03%   |
| Apple                 | 8         | 4.02%   |
| Toshiba               | 7         | 3.52%   |
| Samsung Electronics   | 4         | 2.01%   |
| HUAWEI                | 3         | 1.51%   |
| Sony                  | 2         | 1.01%   |
| Razer                 | 2         | 1.01%   |
| Gateway               | 2         | 1.01%   |
| Fujitsu               | 2         | 1.01%   |
| Alienware             | 2         | 1.01%   |
| Wortmann AG           | 1         | 0.5%    |
| Toxic                 | 1         | 0.5%    |
| Timi                  | 1         | 0.5%    |
| System76              | 1         | 0.5%    |
| Positivo Bahia - VAIO | 1         | 0.5%    |
| Positivo              | 1         | 0.5%    |
| Notebook              | 1         | 0.5%    |
| Metabox               | 1         | 0.5%    |
| Jumper                | 1         | 0.5%    |
| GPU Company           | 1         | 0.5%    |
| Google                | 1         | 0.5%    |
| eMachines             | 1         | 0.5%    |
| Eluktronics           | 1         | 0.5%    |
| Digma                 | 1         | 0.5%    |
| Chuwi                 | 1         | 0.5%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                               | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| MSI Modern 15 A5M                                  | 3         | 1.51%   |
| Lenovo IdeaPad 3 15IIL05 81WE                      | 3         | 1.51%   |
| HP Notebook                                        | 3         | 1.51%   |
| HP EliteBook 8470p                                 | 3         | 1.51%   |
| HP ProBook 650 G1                                  | 2         | 1.01%   |
| HP Pavilion dv6                                    | 2         | 1.01%   |
| HP Pavilion 15                                     | 2         | 1.01%   |
| Dell Latitude E7440                                | 2         | 1.01%   |
| Dell Latitude E6420                                | 2         | 1.01%   |
| Dell Latitude E6410                                | 2         | 1.01%   |
| Dell Inspiron MM061                                | 2         | 1.01%   |
| ASUS Q524UQ                                        | 2         | 1.01%   |
| Apple MacBookPro8,1                                | 2         | 1.01%   |
| Acer Nitro AN515-54                                | 2         | 1.01%   |
| Wortmann AG TERRA_MOBILE_1542                      | 1         | 0.5%    |
| Toxic GM7MQ8P                                      | 1         | 0.5%    |
| Toshiba Satellite-L845                             | 1         | 0.5%    |
| Toshiba Satellite L775D                            | 1         | 0.5%    |
| Toshiba Satellite L750                             | 1         | 0.5%    |
| Toshiba Satellite L655                             | 1         | 0.5%    |
| Toshiba Satellite L300D                            | 1         | 0.5%    |
| Toshiba Satellite Click 2 L35W-B                   | 1         | 0.5%    |
| Toshiba Satellite C75D-B                           | 1         | 0.5%    |
| Timi TM1613                                        | 1         | 0.5%    |
| System76 Gazelle                                   | 1         | 0.5%    |
| Sony VPCCB15FG                                     | 1         | 0.5%    |
| Sony SVP1321L1EBI                                  | 1         | 0.5%    |
| Samsung RV415/RV515                                | 1         | 0.5%    |
| Samsung 550P5C/550P7C                              | 1         | 0.5%    |
| Samsung 350V5C/351V5C/3540VC/3440VC                | 1         | 0.5%    |
| Samsung 300E4C/300E5C/300E7C                       | 1         | 0.5%    |
| Razer Blade Stealth                                | 1         | 0.5%    |
| Razer Blade 15 Base Model (Early 2020) - RZ09-0328 | 1         | 0.5%    |
| Positivo Q232A                                     | 1         | 0.5%    |
| Positivo Bahia - VAIO VJFE51F11X-B0111H            | 1         | 0.5%    |
| Notebook W510TU                                    | 1         | 0.5%    |
| MSI GT60 2OC/2OD                                   | 1         | 0.5%    |
| MSI GS66 Stealth 10UG                              | 1         | 0.5%    |
| MSI GE75 Raider 10SF                               | 1         | 0.5%    |
| MSI GE73 Raider RGB 8RE                            | 1         | 0.5%    |
| MSI GE63 Raider RGB 8RE                            | 1         | 0.5%    |
| MSI GE62 6QE                                       | 1         | 0.5%    |
| MSI Creator Z16 Hiroshi F A11UE                    | 1         | 0.5%    |
| Metabox Edge-Pro NS50MU                            | 1         | 0.5%    |
| Lenovo Yoga S740-14IIL 81RS                        | 1         | 0.5%    |
| Lenovo Y520-15IKBN 80WK                            | 1         | 0.5%    |
| Lenovo Y50-70 Touch 20349                          | 1         | 0.5%    |
| Lenovo V330-15IKB 81AX                             | 1         | 0.5%    |
| Lenovo V110-15ISK 80TL                             | 1         | 0.5%    |
| Lenovo ThinkPad X260 20F5S5QT00                    | 1         | 0.5%    |
| Lenovo ThinkPad X250 20CL001GZA                    | 1         | 0.5%    |
| Lenovo ThinkPad X240 20AMS4MH00                    | 1         | 0.5%    |
| Lenovo ThinkPad X230 2325N66                       | 1         | 0.5%    |
| Lenovo ThinkPad X220 42912XG                       | 1         | 0.5%    |
| Lenovo ThinkPad X1 Extreme Gen 3 20TK001GUS        | 1         | 0.5%    |
| Lenovo ThinkPad X1 Carbon 7th 20QD003AMC           | 1         | 0.5%    |
| Lenovo ThinkPad X1 Carbon 5th 20HRCTO1WW           | 1         | 0.5%    |
| Lenovo ThinkPad T490 20N2S04000                    | 1         | 0.5%    |
| Lenovo ThinkPad T480 20L6SCYP00                    | 1         | 0.5%    |
| Lenovo ThinkPad T470p 20J7S0CF00                   | 1         | 0.5%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                    | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Lenovo ThinkPad                         | 17        | 8.54%   |
| HP Pavilion                             | 14        | 7.04%   |
| Dell Latitude                           | 14        | 7.04%   |
| Dell Inspiron                           | 13        | 6.53%   |
| Lenovo IdeaPad                          | 11        | 5.53%   |
| HP EliteBook                            | 7         | 3.52%   |
| Toshiba Satellite                       | 6         | 3.02%   |
| Acer Aspire                             | 6         | 3.02%   |
| HP ProBook                              | 5         | 2.51%   |
| HP Laptop                               | 5         | 2.51%   |
| ASUS VivoBook                           | 4         | 2.01%   |
| MSI Modern                              | 3         | 1.51%   |
| HP Notebook                             | 3         | 1.51%   |
| Acer Nitro                              | 3         | 1.51%   |
| Razer Blade                             | 2         | 1.01%   |
| HP ZBook                                | 2         | 1.01%   |
| Fujitsu LIFEBOOK                        | 2         | 1.01%   |
| Dell Precision                          | 2         | 1.01%   |
| ASUS Q524UQ                             | 2         | 1.01%   |
| Apple MacBookPro8                       | 2         | 1.01%   |
| Apple MacBookPro11                      | 2         | 1.01%   |
| Acer Swift                              | 2         | 1.01%   |
| Wortmann AG TERRA                       | 1         | 0.5%    |
| Toxic GM7MQ8P                           | 1         | 0.5%    |
| Toshiba Satellite-L845                  | 1         | 0.5%    |
| Timi TM1613                             | 1         | 0.5%    |
| System76 Gazelle                        | 1         | 0.5%    |
| Sony VPCCB15FG                          | 1         | 0.5%    |
| Sony SVP1321L1EBI                       | 1         | 0.5%    |
| Samsung RV415                           | 1         | 0.5%    |
| Samsung 550P5C                          | 1         | 0.5%    |
| Samsung 350V5C                          | 1         | 0.5%    |
| Samsung 300E4C                          | 1         | 0.5%    |
| Positivo Q232A                          | 1         | 0.5%    |
| Positivo Bahia - VAIO VJFE51F11X-B0111H | 1         | 0.5%    |
| Notebook W510TU                         | 1         | 0.5%    |
| MSI GT60                                | 1         | 0.5%    |
| MSI GS66                                | 1         | 0.5%    |
| MSI GE75                                | 1         | 0.5%    |
| MSI GE73                                | 1         | 0.5%    |
| MSI GE63                                | 1         | 0.5%    |
| MSI GE62                                | 1         | 0.5%    |
| MSI Creator                             | 1         | 0.5%    |
| Metabox Edge-Pro                        | 1         | 0.5%    |
| Lenovo Yoga                             | 1         | 0.5%    |
| Lenovo Y520-15IKBN                      | 1         | 0.5%    |
| Lenovo Y50-70                           | 1         | 0.5%    |
| Lenovo V330-15IKB                       | 1         | 0.5%    |
| Lenovo V110-15ISK                       | 1         | 0.5%    |
| Lenovo Legion                           | 1         | 0.5%    |
| Lenovo G480                             | 1         | 0.5%    |
| Lenovo E41-25                           | 1         | 0.5%    |
| Lenovo B50-80                           | 1         | 0.5%    |
| Jumper EZbook                           | 1         | 0.5%    |
| HUAWEI WRT-WX9                          | 1         | 0.5%    |
| HUAWEI HVY-WXX9                         | 1         | 0.5%    |
| HUAWEI BOHK-WAX9X                       | 1         | 0.5%    |
| HP HDX                                  | 1         | 0.5%    |
| HP ENVY                                 | 1         | 0.5%    |
| HP Compaq                               | 1         | 0.5%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 27        | 13.57%  |
| 2011 | 25        | 12.56%  |
| 2020 | 18        | 9.05%   |
| 2018 | 18        | 9.05%   |
| 2016 | 16        | 8.04%   |
| 2013 | 16        | 8.04%   |
| 2014 | 15        | 7.54%   |
| 2021 | 13        | 6.53%   |
| 2017 | 12        | 6.03%   |
| 2012 | 12        | 6.03%   |
| 2010 | 8         | 4.02%   |
| 2015 | 5         | 2.51%   |
| 2008 | 5         | 2.51%   |
| 2007 | 3         | 1.51%   |
| 2006 | 3         | 1.51%   |
| 2009 | 2         | 1.01%   |
| 2022 | 1         | 0.5%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 199       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 199       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 198       | 99.5%   |
| Yes  | 1         | 0.5%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 49        | 24.62%  |
| 8.01-16.0   | 44        | 22.11%  |
| 3.01-4.0    | 39        | 19.6%   |
| 16.01-24.0  | 35        | 17.59%  |
| 32.01-64.0  | 14        | 7.04%   |
| 1.01-2.0    | 7         | 3.52%   |
| 64.01-256.0 | 5         | 2.51%   |
| 24.01-32.0  | 3         | 1.51%   |
| 2.01-3.0    | 3         | 1.51%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 70        | 33.33%  |
| 2.01-3.0  | 68        | 32.38%  |
| 3.01-4.0  | 32        | 15.24%  |
| 4.01-8.0  | 25        | 11.9%   |
| 0.51-1.0  | 9         | 4.29%   |
| 8.01-16.0 | 5         | 2.38%   |
| 0.01-0.5  | 1         | 0.48%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 131       | 65.17%  |
| 2      | 61        | 30.35%  |
| 3      | 8         | 3.98%   |
| 0      | 1         | 0.5%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 131       | 65.83%  |
| Yes       | 68        | 34.17%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 160       | 80.4%   |
| No        | 39        | 19.6%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 196       | 98.49%  |
| No        | 3         | 1.51%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 162       | 79.8%   |
| No        | 41        | 20.2%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 62        | 30.85%  |
| Germany      | 13        | 6.47%   |
| France       | 11        | 5.47%   |
| Spain        | 10        | 4.98%   |
| UK           | 9         | 4.48%   |
| Netherlands  | 7         | 3.48%   |
| Brazil       | 7         | 3.48%   |
| Russia       | 6         | 2.99%   |
| India        | 6         | 2.99%   |
| Kenya        | 4         | 1.99%   |
| Indonesia    | 4         | 1.99%   |
| Canada       | 4         | 1.99%   |
| Australia    | 4         | 1.99%   |
| Sweden       | 3         | 1.49%   |
| South Africa | 3         | 1.49%   |
| Poland       | 3         | 1.49%   |
| Mexico       | 3         | 1.49%   |
| Italy        | 3         | 1.49%   |
| Iraq         | 3         | 1.49%   |
| Denmark      | 3         | 1.49%   |
| Turkey       | 2         | 1%      |
| Portugal     | 2         | 1%      |
| Czechia      | 2         | 1%      |
| Bangladesh   | 2         | 1%      |
| Switzerland  | 1         | 0.5%    |
| Puerto Rico  | 1         | 0.5%    |
| Peru         | 1         | 0.5%    |
| Pakistan     | 1         | 0.5%    |
| Nigeria      | 1         | 0.5%    |
| New Zealand  | 1         | 0.5%    |
| Myanmar      | 1         | 0.5%    |
| Morocco      | 1         | 0.5%    |
| Latvia       | 1         | 0.5%    |
| Hungary      | 1         | 0.5%    |
| Greece       | 1         | 0.5%    |
| Georgia      | 1         | 0.5%    |
| Finland      | 1         | 0.5%    |
| Croatia      | 1         | 0.5%    |
| Costa Rica   | 1         | 0.5%    |
| Colombia     | 1         | 0.5%    |
| Chile        | 1         | 0.5%    |
| Bulgaria     | 1         | 0.5%    |
| Belgium      | 1         | 0.5%    |
| Belarus      | 1         | 0.5%    |
| Azerbaijan   | 1         | 0.5%    |
| Austria      | 1         | 0.5%    |
| Argentina    | 1         | 0.5%    |
| Algeria      | 1         | 0.5%    |
| Unknown      | 1         | 0.5%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Nairobi               | 4         | 1.91%   |
| Seattle               | 3         | 1.44%   |
| Dallas                | 3         | 1.44%   |
| Amsterdam             | 3         | 1.44%   |
| Sydney                | 2         | 0.96%   |
| Stockholm             | 2         | 0.96%   |
| Ruskin                | 2         | 0.96%   |
| Pretoria              | 2         | 0.96%   |
| Paris                 | 2         | 0.96%   |
| New York              | 2         | 0.96%   |
| Mostoles              | 2         | 0.96%   |
| Melbourne             | 2         | 0.96%   |
| Madrid                | 2         | 0.96%   |
| Houston               | 2         | 0.96%   |
| Dhaka                 | 2         | 0.96%   |
| Chicago               | 2         | 0.96%   |
| Camden                | 2         | 0.96%   |
| Berlin                | 2         | 0.96%   |
| Baghdad               | 2         | 0.96%   |
| Zurich                | 1         | 0.48%   |
| Zagreb                | 1         | 0.48%   |
| West Jordan           | 1         | 0.48%   |
| Washington            | 1         | 0.48%   |
| Warsaw                | 1         | 0.48%   |
| Volgograd             | 1         | 0.48%   |
| Visalia               | 1         | 0.48%   |
| Villa Carlos Paz      | 1         | 0.48%   |
| Vila Nova de Gaia     | 1         | 0.48%   |
| Vienna                | 1         | 0.48%   |
| Veitsbronn            | 1         | 0.48%   |
| Tulare                | 1         | 0.48%   |
| Ts'khinvali           | 1         | 0.48%   |
| Trivandrum            | 1         | 0.48%   |
| Tottenham             | 1         | 0.48%   |
| Toronto               | 1         | 0.48%   |
| Tempe                 | 1         | 0.48%   |
| Tangier               | 1         | 0.48%   |
| Tangerang             | 1         | 0.48%   |
| Sviyazhsk             | 1         | 0.48%   |
| Surabaya              | 1         | 0.48%   |
| Sumaré               | 1         | 0.48%   |
| St Petersburg         | 1         | 0.48%   |
| Spotsylvania          | 1         | 0.48%   |
| South Hamilton        | 1         | 0.48%   |
| Soro                  | 1         | 0.48%   |
| Skive                 | 1         | 0.48%   |
| Sinntal               | 1         | 0.48%   |
| Shelbyville           | 1         | 0.48%   |
| Secaucus              | 1         | 0.48%   |
| Scotts Valley         | 1         | 0.48%   |
| Saulkrasti            | 1         | 0.48%   |
| Sao Paulo             | 1         | 0.48%   |
| Santo André          | 1         | 0.48%   |
| Santa Monica          | 1         | 0.48%   |
| Sant Boi de Llobregat | 1         | 0.48%   |
| Sannois               | 1         | 0.48%   |
| San José             | 1         | 0.48%   |
| Saint Paul            | 1         | 0.48%   |
| Rotterdam             | 1         | 0.48%   |
| Rome                  | 1         | 0.48%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 38        | 44     | 14.62%  |
| Toshiba             | 37        | 40     | 14.23%  |
| WDC                 | 33        | 41     | 12.69%  |
| Unknown             | 21        | 22     | 8.08%   |
| Seagate             | 21        | 21     | 8.08%   |
| Kingston            | 17        | 17     | 6.54%   |
| SanDisk             | 11        | 13     | 4.23%   |
| Crucial             | 10        | 15     | 3.85%   |
| Hitachi             | 9         | 11     | 3.46%   |
| Micron Technology   | 7         | 7      | 2.69%   |
| HGST                | 7         | 9      | 2.69%   |
| SK hynix            | 6         | 6      | 2.31%   |
| Apple               | 5         | 5      | 1.92%   |
| A-DATA Technology   | 5         | 5      | 1.92%   |
| China               | 4         | 4      | 1.54%   |
| LITEON              | 3         | 3      | 1.15%   |
| Intel               | 3         | 4      | 1.15%   |
| KIOXIA              | 2         | 2      | 0.77%   |
| HUAWEI              | 2         | 2      | 0.77%   |
| YMTC                | 1         | 1      | 0.38%   |
| W800SH              | 1         | 1      | 0.38%   |
| Transcend           | 1         | 1      | 0.38%   |
| Team                | 1         | 1      | 0.38%   |
| Silicon Motion      | 1         | 1      | 0.38%   |
| S3+                 | 1         | 1      | 0.38%   |
| PNY                 | 1         | 1      | 0.38%   |
| Phison              | 1         | 1      | 0.38%   |
| Patriot             | 1         | 1      | 0.38%   |
| Netac               | 1         | 1      | 0.38%   |
| LITEONIT            | 1         | 1      | 0.38%   |
| Lexar               | 1         | 1      | 0.38%   |
| KingSpec            | 1         | 2      | 0.38%   |
| KingFast            | 1         | 2      | 0.38%   |
| Intenso             | 1         | 2      | 0.38%   |
| Fujitsu             | 1         | 1      | 0.38%   |
| Corsair             | 1         | 2      | 0.38%   |
| BHT                 | 1         | 1      | 0.38%   |
| ASMedia             | 1         | 1      | 0.38%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Toshiba MQ04ABF100 1TB               | 10        | 3.69%   |
| Toshiba MQ01ABF050 500GB             | 6         | 2.21%   |
| Unknown MMC Card  32GB               | 4         | 1.48%   |
| Toshiba MQ01ABD100 1TB               | 4         | 1.48%   |
| Samsung SSD 860 EVO 500GB            | 4         | 1.48%   |
| Kingston NVMe SSD Drive 512GB        | 4         | 1.48%   |
| WDC WD10SPZX-75Z10T2 1TB             | 3         | 1.11%   |
| Toshiba MQ01ABD075 752GB             | 3         | 1.11%   |
| Seagate ST2000LM003 HN-M201RAD 2TB   | 3         | 1.11%   |
| Seagate ST1000LM035-1RK172 1TB       | 3         | 1.11%   |
| SanDisk SSD PLUS 1000GB              | 3         | 1.11%   |
| HGST HTS721010A9E630 1TB             | 3         | 1.11%   |
| HGST HTS541010A9E680 1TB             | 3         | 1.11%   |
| WDC WD5000LPCX-24C6HT0 500GB         | 2         | 0.74%   |
| WDC WD10SPZX-60Z10T0 1TB             | 2         | 0.74%   |
| Unknown SD/MMC/MS PRO 128GB          | 2         | 0.74%   |
| Seagate ST9250315AS 250GB            | 2         | 0.74%   |
| Seagate ST320LT007-9ZV142 320GB      | 2         | 0.74%   |
| SanDisk NVMe SSD Drive 256GB         | 2         | 0.74%   |
| SanDisk NVMe SSD Drive 1TB           | 2         | 0.74%   |
| Samsung SSD 980 1TB                  | 2         | 0.74%   |
| Samsung SSD 850 EVO 250GB            | 2         | 0.74%   |
| Samsung HM500JI 500GB                | 2         | 0.74%   |
| Kingston SV300S37A240G 240GB SSD     | 2         | 0.74%   |
| Kingston SV300S37A120G 120GB SSD     | 2         | 0.74%   |
| Kingston SA400S37240G 240GB SSD      | 2         | 0.74%   |
| Crucial CT500MX500SSD1 500GB         | 2         | 0.74%   |
| Crucial CT1000MX500SSD1 1TB          | 2         | 0.74%   |
| Apple SSD SM0256G 256GB              | 2         | 0.74%   |
| YMTC PC005 512GB                     | 1         | 0.37%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 1         | 0.37%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 1         | 0.37%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 1         | 0.37%   |
| WDC WDS100T2B0C-00PXH0 1TB           | 1         | 0.37%   |
| WDC WDS100T2B0B-00YS70 1TB SSD       | 1         | 0.37%   |
| WDC WDBNCE2500PNC 250GB SSD          | 1         | 0.37%   |
| WDC WD800BEVS-22RST0 80GB            | 1         | 0.37%   |
| WDC WD7500BPVX-22JC3T0 752GB         | 1         | 0.37%   |
| WDC WD6400BPVT-75HXZT1 640GB         | 1         | 0.37%   |
| WDC WD5000LPVT-16G33T0 500GB         | 1         | 0.37%   |
| WDC WD5000LPLX-08ZNTT0 500GB         | 1         | 0.37%   |
| WDC WD5000LPCX-24VHAT0 500GB         | 1         | 0.37%   |
| WDC WD3200LPVX-00V0TT0 320GB         | 1         | 0.37%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 1         | 0.37%   |
| WDC WD3200BPVT-00JJ5T0 320GB         | 1         | 0.37%   |
| WDC WD3200BPVT-00HXZT1 320GB         | 1         | 0.37%   |
| WDC WD3200BEVT-60A23T0 320GB         | 1         | 0.37%   |
| WDC WD2500BPVT-00JJ5T0 250GB         | 1         | 0.37%   |
| WDC WD2500BEVT-22A23T0 250GB         | 1         | 0.37%   |
| WDC WD10SPZX-24Z10 1TB               | 1         | 0.37%   |
| WDC WD10SPZX-21Z 1TB                 | 1         | 0.37%   |
| WDC WD10SPZX-17Z10T1 1TB             | 1         | 0.37%   |
| WDC WD10SPZX-08Z10 1TB               | 1         | 0.37%   |
| WDC WD10SPCX-24HWST1 1TB             | 1         | 0.37%   |
| WDC WD10S21X-24R1BT0-SSHD-8GB        | 1         | 0.37%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB | 1         | 0.37%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB | 1         | 0.37%   |
| WDC PC SN730 SDBPNTY-512G-1032 512GB | 1         | 0.37%   |
| WDC PC SN720 SDAPNTW-512G-1014 512GB | 1         | 0.37%   |
| W800SH 512GB SSD                     | 1         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 31        | 33     | 30.39%  |
| WDC                 | 26        | 30     | 25.49%  |
| Seagate             | 21        | 21     | 20.59%  |
| Hitachi             | 9         | 11     | 8.82%   |
| HGST                | 7         | 9      | 6.86%   |
| Samsung Electronics | 4         | 4      | 3.92%   |
| Unknown             | 2         | 2      | 1.96%   |
| Fujitsu             | 1         | 1      | 0.98%   |
| ASMedia             | 1         | 1      | 0.98%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 16        | 19     | 19.51%  |
| Kingston            | 9         | 9      | 10.98%  |
| Crucial             | 9         | 14     | 10.98%  |
| SanDisk             | 6         | 7      | 7.32%   |
| WDC                 | 5         | 6      | 6.1%    |
| Toshiba             | 4         | 5      | 4.88%   |
| China               | 4         | 4      | 4.88%   |
| Apple               | 4         | 4      | 4.88%   |
| Micron Technology   | 3         | 3      | 3.66%   |
| LITEON              | 3         | 3      | 3.66%   |
| Intel               | 2         | 2      | 2.44%   |
| A-DATA Technology   | 2         | 2      | 2.44%   |
| W800SH              | 1         | 1      | 1.22%   |
| Unknown             | 1         | 1      | 1.22%   |
| Transcend           | 1         | 1      | 1.22%   |
| Team                | 1         | 1      | 1.22%   |
| SK hynix            | 1         | 1      | 1.22%   |
| S3+                 | 1         | 1      | 1.22%   |
| PNY                 | 1         | 1      | 1.22%   |
| Patriot             | 1         | 1      | 1.22%   |
| Netac               | 1         | 1      | 1.22%   |
| LITEONIT            | 1         | 1      | 1.22%   |
| KingSpec            | 1         | 2      | 1.22%   |
| KingFast            | 1         | 1      | 1.22%   |
| Intenso             | 1         | 2      | 1.22%   |
| Corsair             | 1         | 2      | 1.22%   |
| BHT                 | 1         | 1      | 1.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 99        | 112    | 39.76%  |
| SSD     | 75        | 96     | 30.12%  |
| NVMe    | 54        | 63     | 21.69%  |
| MMC     | 17        | 19     | 6.83%   |
| Unknown | 4         | 4      | 1.61%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 155       | 199    | 65.13%  |
| NVMe | 54        | 63     | 22.69%  |
| MMC  | 17        | 19     | 7.14%   |
| SAS  | 12        | 13     | 5.04%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 105       | 131    | 59.66%  |
| 0.51-1.0   | 64        | 69     | 36.36%  |
| 1.01-2.0   | 7         | 8      | 3.98%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 50        | 24.88%  |
| 101-250        | 48        | 23.88%  |
| 501-1000       | 31        | 15.42%  |
| 1001-2000      | 23        | 11.44%  |
| Unknown        | 16        | 7.96%   |
| 21-50          | 12        | 5.97%   |
| 51-100         | 11        | 5.47%   |
| 2001-3000      | 4         | 1.99%   |
| More than 3000 | 3         | 1.49%   |
| 1-20           | 3         | 1.49%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 21-50          | 60        | 29.13%  |
| 51-100         | 40        | 19.42%  |
| 1-20           | 36        | 17.48%  |
| 101-250        | 23        | 11.17%  |
| 251-500        | 22        | 10.68%  |
| Unknown        | 16        | 7.77%   |
| 501-1000       | 7         | 3.4%    |
| More than 3000 | 1         | 0.49%   |
| 1001-2000      | 1         | 0.49%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Samsung Electronics HM500JI 500GB                   | 2         | 2      | 10.53%  |
| WDC WD3200BPVT-00JJ5T0 320GB                        | 1         | 1      | 5.26%   |
| WDC WD2500BEVT-22A23T0 250GB                        | 1         | 1      | 5.26%   |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 5.26%   |
| Toshiba MK3265GSXF 320GB                            | 1         | 1      | 5.26%   |
| Seagate ST2000LM007-1R8174 2TB                      | 1         | 1      | 5.26%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1      | 5.26%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD    | 1         | 1      | 5.26%   |
| Samsung Electronics HM160HI 160GB                   | 1         | 1      | 5.26%   |
| Micron Technology MTFDDAK128MAY-1AH1ZABHA 128GB SSD | 1         | 1      | 5.26%   |
| LITEON CV8-8E128-HP 128GB SSD                       | 1         | 1      | 5.26%   |
| Hitachi HTS725050A9A360 500GB                       | 1         | 1      | 5.26%   |
| Hitachi HTS725032A9A364 320GB                       | 1         | 1      | 5.26%   |
| Hitachi HTS542512K9SA00 120GB                       | 1         | 1      | 5.26%   |
| HGST HTS721010A9E630 1TB                            | 1         | 1      | 5.26%   |
| Fujitsu MHY2160BH 160GB                             | 1         | 1      | 5.26%   |
| A-DATA Technology SX6000LNP 1TB                     | 1         | 1      | 5.26%   |
| A-DATA Technology SU700 120GB SSD                   | 1         | 1      | 5.26%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 4      | 21.05%  |
| Hitachi             | 3         | 3      | 15.79%  |
| WDC                 | 2         | 2      | 10.53%  |
| Toshiba             | 2         | 2      | 10.53%  |
| Seagate             | 2         | 2      | 10.53%  |
| A-DATA Technology   | 2         | 2      | 10.53%  |
| Micron Technology   | 1         | 1      | 5.26%   |
| LITEON              | 1         | 1      | 5.26%   |
| HGST                | 1         | 1      | 5.26%   |
| Fujitsu             | 1         | 1      | 5.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 21.43%  |
| Hitachi             | 3         | 3      | 21.43%  |
| WDC                 | 2         | 2      | 14.29%  |
| Toshiba             | 2         | 2      | 14.29%  |
| Seagate             | 2         | 2      | 14.29%  |
| HGST                | 1         | 1      | 7.14%   |
| Fujitsu             | 1         | 1      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 14        | 14     | 73.68%  |
| SSD  | 4         | 4      | 21.05%  |
| NVMe | 1         | 1      | 5.26%   |

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
| Detected | 102       | 151    | 46.58%  |
| Works    | 99        | 124    | 45.21%  |
| Malfunc  | 18        | 19     | 8.22%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 147       | 63.64%  |
| AMD                          | 22        | 9.52%   |
| Samsung Electronics          | 21        | 9.09%   |
| SanDisk                      | 9         | 3.9%    |
| Kingston Technology Company  | 8         | 3.46%   |
| SK hynix                     | 5         | 2.16%   |
| Micron Technology            | 4         | 1.73%   |
| Toshiba America Info Systems | 2         | 0.87%   |
| Silicon Motion               | 2         | 0.87%   |
| Nvidia                       | 2         | 0.87%   |
| KIOXIA                       | 2         | 0.87%   |
| ADATA Technology             | 2         | 0.87%   |
| Yangtze Memory Technologies  | 1         | 0.43%   |
| Realtek Semiconductor        | 1         | 0.43%   |
| Phison Electronics           | 1         | 0.43%   |
| Micron/Crucial Technology    | 1         | 0.43%   |
| Apple                        | 1         | 0.43%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 19        | 7.6%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 19        | 7.6%    |
| AMD FCH SATA Controller [AHCI mode]                                                    | 17        | 6.8%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 16        | 6.4%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 12        | 4.8%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 12        | 4.8%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 9         | 3.6%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 9         | 3.6%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 8         | 3.2%    |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 5         | 2%      |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 5         | 2%      |
| Samsung NVMe SSD Controller 980                                                        | 4         | 1.6%    |
| Micron Non-Volatile memory controller                                                  | 4         | 1.6%    |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 4         | 1.6%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 4         | 1.6%    |
| SK hynix BC511                                                                         | 3         | 1.2%    |
| SanDisk WD Blue SN550 NVMe SSD                                                         | 3         | 1.2%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 3         | 1.2%    |
| Kingston Company Company Non-Volatile memory controller                                | 3         | 1.2%    |
| Intel Volume Management Device NVMe RAID Controller                                    | 3         | 1.2%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 3         | 1.2%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 3         | 1.2%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 3         | 1.2%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 3         | 1.2%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 3         | 1.2%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 3         | 1.2%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 3         | 1.2%    |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 3         | 1.2%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 3         | 1.2%    |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller       | 2         | 0.8%    |
| SK hynix Gold P31 SSD                                                                  | 2         | 0.8%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 2         | 0.8%    |
| SanDisk Non-Volatile memory controller                                                 | 2         | 0.8%    |
| Samsung NVMe SSD Controller SM951/PM951                                                | 2         | 0.8%    |
| Samsung Electronics SATA controller                                                    | 2         | 0.8%    |
| KIOXIA Non-Volatile memory controller                                                  | 2         | 0.8%    |
| Kingston Company U-SNS8154P3 NVMe SSD                                                  | 2         | 0.8%    |
| Kingston Company A2000 NVMe SSD                                                        | 2         | 0.8%    |
| Intel Comet Lake SATA AHCI Controller                                                  | 2         | 0.8%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 2         | 0.8%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 2         | 0.8%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 2         | 0.8%    |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 2         | 0.8%    |
| AMD FCH SATA Controller [IDE mode]                                                     | 2         | 0.8%    |
| Yangtze Memory Non-Volatile memory controller                                          | 1         | 0.4%    |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                        | 1         | 0.4%    |
| SanDisk PC SN520 NVMe SSD                                                              | 1         | 0.4%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 1         | 0.4%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 1         | 0.4%    |
| Samsung Apple PCIe SSD                                                                 | 1         | 0.4%    |
| Realtek RTS5763DL NVMe SSD Controller                                                  | 1         | 0.4%    |
| Phison E12 NVMe Controller                                                             | 1         | 0.4%    |
| Nvidia MCP89 SATA Controller (AHCI mode)                                               | 1         | 0.4%    |
| Nvidia MCP89 SATA Controller                                                           | 1         | 0.4%    |
| Micron/Crucial NVMe Controller                                                         | 1         | 0.4%    |
| Kingston Company OM3PDP3 NVMe SSD                                                      | 1         | 0.4%    |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                        | 1         | 0.4%    |
| Intel SSD 600P Series                                                                  | 1         | 0.4%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 1         | 0.4%    |
| Intel Mobile 4 Series Chipset PT IDER Controller                                       | 1         | 0.4%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 139       | 59.15%  |
| NVMe | 54        | 22.98%  |
| RAID | 22        | 9.36%   |
| IDE  | 20        | 8.51%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 169       | 84.92%  |
| AMD    | 30        | 15.08%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz             | 6         | 3.02%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 6         | 3.02%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 5         | 2.51%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 2.01%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 2.01%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 2.01%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 4         | 2.01%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 4         | 2.01%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 1.51%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 3         | 1.51%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 1.51%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 1.51%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 1.51%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 3         | 1.51%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 3         | 1.51%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 3         | 1.51%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 3         | 1.51%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 3         | 1.51%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 3         | 1.51%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 2         | 1.01%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 1.01%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 1.01%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 2         | 1.01%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 2         | 1.01%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 1.01%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 2         | 1.01%   |
| Intel Core i7-2620M CPU @ 2.70GHz             | 2         | 1.01%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.01%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 2         | 1.01%   |
| Intel Core i5-4310U CPU @ 2.00GHz             | 2         | 1.01%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 1.01%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 1.01%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 1.01%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 1.01%   |
| Intel Core 2 CPU T5600 @ 1.83GHz              | 2         | 1.01%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 2         | 1.01%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 2         | 1.01%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 1.01%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 1.01%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 1.01%   |
| AMD E1-2500 APU with Radeon HD Graphics       | 2         | 1.01%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 0.5%    |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.5%    |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 0.5%    |
| Intel Pentium CPU N3530 @ 2.16GHz             | 1         | 0.5%    |
| Intel Pentium CPU B960 @ 2.20GHz              | 1         | 0.5%    |
| Intel Pentium CPU 4415U @ 2.30GHz             | 1         | 0.5%    |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 0.5%    |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 1         | 0.5%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.5%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 0.5%    |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 0.5%    |
| Intel Core i7-5600U CPU @ 2.60GHz             | 1         | 0.5%    |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 0.5%    |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 1         | 0.5%    |
| Intel Core i7-4770HQ CPU @ 2.20GHz            | 1         | 0.5%    |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 0.5%    |
| Intel Core i7-4700HQ CPU @ 2.40GHz            | 1         | 0.5%    |
| Intel Core i7-4558U CPU @ 2.80GHz             | 1         | 0.5%    |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 60        | 30.15%  |
| Intel Core i7           | 57        | 28.64%  |
| Intel Core i3           | 17        | 8.54%   |
| Other                   | 10        | 5.03%   |
| Intel Celeron           | 8         | 4.02%   |
| AMD Ryzen 7             | 8         | 4.02%   |
| Intel Core 2 Duo        | 6         | 3.02%   |
| AMD A6                  | 5         | 2.51%   |
| AMD Ryzen 5             | 4         | 2.01%   |
| Intel Pentium           | 3         | 1.51%   |
| Intel Core 2            | 3         | 1.51%   |
| AMD E1                  | 3         | 1.51%   |
| Intel Pentium Silver    | 2         | 1.01%   |
| Intel Atom              | 2         | 1.01%   |
| AMD Ryzen 3             | 2         | 1.01%   |
| AMD A4                  | 2         | 1.01%   |
| Intel Pentium Dual-Core | 1         | 0.5%    |
| Intel Core 2 Quad       | 1         | 0.5%    |
| Intel Core 2 Extreme    | 1         | 0.5%    |
| AMD E2                  | 1         | 0.5%    |
| AMD E                   | 1         | 0.5%    |
| AMD C-50                | 1         | 0.5%    |
| AMD Athlon X2           | 1         | 0.5%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 109       | 54.77%  |
| 4      | 62        | 31.16%  |
| 6      | 15        | 7.54%   |
| 8      | 10        | 5.03%   |
| 1      | 2         | 1.01%   |
| 14     | 1         | 0.5%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 199       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 154       | 77.39%  |
| 1      | 45        | 22.61%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 194       | 97.49%  |
| Unknown        | 5         | 2.51%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 92        | 45.1%   |
| 0x206a7    | 14        | 6.86%   |
| 0x306a9    | 8         | 3.92%   |
| 0x906ea    | 7         | 3.43%   |
| 0x806e9    | 7         | 3.43%   |
| 0x806ec    | 6         | 2.94%   |
| 0xa0652    | 5         | 2.45%   |
| 0x806ea    | 5         | 2.45%   |
| 0x706e5    | 4         | 1.96%   |
| 0x406e3    | 4         | 1.96%   |
| 0x306c3    | 4         | 1.96%   |
| 0x1067a    | 4         | 1.96%   |
| 0x806c1    | 3         | 1.47%   |
| 0x6f6      | 3         | 1.47%   |
| 0x40651    | 3         | 1.47%   |
| 0x07030105 | 3         | 1.47%   |
| 0x906e9    | 2         | 0.98%   |
| 0x806d1    | 2         | 0.98%   |
| 0x706a8    | 2         | 0.98%   |
| 0x406c4    | 2         | 0.98%   |
| 0x306d4    | 2         | 0.98%   |
| 0x08600106 | 2         | 0.98%   |
| 0x08108109 | 2         | 0.98%   |
| 0x06006705 | 2         | 0.98%   |
| 0x03000027 | 2         | 0.98%   |
| 0x906ed    | 1         | 0.49%   |
| 0x906a3    | 1         | 0.49%   |
| 0x806eb    | 1         | 0.49%   |
| 0x806c2    | 1         | 0.49%   |
| 0x706a1    | 1         | 0.49%   |
| 0x6fd      | 1         | 0.49%   |
| 0x506e3    | 1         | 0.49%   |
| 0x506c9    | 1         | 0.49%   |
| 0x40661    | 1         | 0.49%   |
| 0x20655    | 1         | 0.49%   |
| 0x08108102 | 1         | 0.49%   |
| 0x0810100b | 1         | 0.49%   |
| 0x06001119 | 1         | 0.49%   |
| 0x05000029 | 1         | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 43        | 21.61%  |
| SandyBridge      | 20        | 10.05%  |
| Haswell          | 18        | 9.05%   |
| IvyBridge        | 17        | 8.54%   |
| Skylake          | 12        | 6.03%   |
| Broadwell        | 10        | 5.03%   |
| Silvermont       | 8         | 4.02%   |
| Penryn           | 8         | 4.02%   |
| IceLake          | 7         | 3.52%   |
| CometLake        | 7         | 3.52%   |
| Zen+             | 5         | 2.51%   |
| TigerLake        | 5         | 2.51%   |
| Core             | 5         | 2.51%   |
| Westmere         | 4         | 2.01%   |
| Excavator        | 4         | 2.01%   |
| Unknown          | 4         | 2.01%   |
| Puma             | 3         | 1.51%   |
| Jaguar           | 3         | 1.51%   |
| Goldmont plus    | 3         | 1.51%   |
| Zen 3            | 2         | 1.01%   |
| Zen 2            | 2         | 1.01%   |
| K10 Llano        | 2         | 1.01%   |
| Bobcat           | 2         | 1.01%   |
| Zen              | 1         | 0.5%    |
| Piledriver       | 1         | 0.5%    |
| K8 & K10 hybrid  | 1         | 0.5%    |
| Goldmont         | 1         | 0.5%    |
| Alderlake Hybrid | 1         | 0.5%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 156       | 58.65%  |
| Nvidia | 62        | 23.31%  |
| AMD    | 48        | 18.05%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 17        | 6.27%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 15        | 5.54%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 12        | 4.43%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 10        | 3.69%   |
| Intel UHD Graphics 620                                                                   | 9         | 3.32%   |
| Intel HD Graphics 5500                                                                   | 9         | 3.32%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 9         | 3.32%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 8         | 2.95%   |
| Intel HD Graphics 620                                                                    | 7         | 2.58%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 7         | 2.58%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 1.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 1.85%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 1.85%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 5         | 1.85%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 1.85%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 1.48%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 1.48%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 1.48%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 1.48%   |
| AMD Lucienne                                                                             | 4         | 1.48%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 3         | 1.11%   |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 1.11%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 3         | 1.11%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 1.11%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 1.11%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.11%   |
| Intel HD Graphics 530                                                                    | 3         | 1.11%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 1.11%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 1.11%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.74%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 2         | 0.74%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.74%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 2         | 0.74%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 2         | 0.74%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 2         | 0.74%   |
| Nvidia GK107M [GeForce GT 650M]                                                          | 2         | 0.74%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 0.74%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 2         | 0.74%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 0.74%   |
| Intel HD Graphics 630                                                                    | 2         | 0.74%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 0.74%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                            | 2         | 0.74%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 2         | 0.74%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 0.74%   |
| AMD Sumo [Radeon HD 6520G]                                                               | 2         | 0.74%   |
| AMD RV515/M54 [Mobility Radeon X1400]                                                    | 2         | 0.74%   |
| AMD Renoir                                                                               | 2         | 0.74%   |
| AMD Kabini [Radeon HD 8240 / R3 Series]                                                  | 2         | 0.74%   |
| AMD Cezanne                                                                              | 2         | 0.74%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.37%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.37%   |
| Nvidia TU117M                                                                            | 1         | 0.37%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.37%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 1         | 0.37%   |
| Nvidia TU104M [GeForce RTX 2080 SUPER Mobile / Max-Q]                                    | 1         | 0.37%   |
| Nvidia GT218M [GeForce 315M]                                                             | 1         | 0.37%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.37%   |
| Nvidia GP108M [GeForce MX230]                                                            | 1         | 0.37%   |
| Nvidia GP108GLM [Quadro P520]                                                            | 1         | 0.37%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 0.37%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 91        | 45.73%  |
| Intel + Nvidia | 53        | 26.63%  |
| 1 x AMD        | 33        | 16.58%  |
| Intel + AMD    | 12        | 6.03%   |
| 1 x Nvidia     | 7         | 3.52%   |
| AMD + Nvidia   | 2         | 1.01%   |
| 2 x AMD        | 1         | 0.5%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 183       | 91.96%  |
| Proprietary | 15        | 7.54%   |
| Unknown     | 1         | 0.5%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 154       | 76.62%  |
| 1.01-2.0   | 15        | 7.46%   |
| 0.01-0.5   | 12        | 5.97%   |
| 0.51-1.0   | 9         | 4.48%   |
| 3.01-4.0   | 7         | 3.48%   |
| 5.01-6.0   | 2         | 1%      |
| 7.01-8.0   | 1         | 0.5%    |
| 2.01-3.0   | 1         | 0.5%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 51        | 23.29%  |
| LG Display              | 39        | 17.81%  |
| Chimei Innolux          | 31        | 14.16%  |
| BOE                     | 31        | 14.16%  |
| Samsung Electronics     | 20        | 9.13%   |
| Apple                   | 9         | 4.11%   |
| Chi Mei Optoelectronics | 7         | 3.2%    |
| Lenovo                  | 4         | 1.83%   |
| Sharp                   | 3         | 1.37%   |
| PANDA                   | 3         | 1.37%   |
| Dell                    | 3         | 1.37%   |
| Acer                    | 3         | 1.37%   |
| Ancor Communications    | 2         | 0.91%   |
| Unknown (AAA)           | 1         | 0.46%   |
| STA                     | 1         | 0.46%   |
| Sceptre Tech            | 1         | 0.46%   |
| SANYO                   | 1         | 0.46%   |
| Philips                 | 1         | 0.46%   |
| Panasonic               | 1         | 0.46%   |
| ONN                     | 1         | 0.46%   |
| Kogan                   | 1         | 0.46%   |
| Hewlett-Packard         | 1         | 0.46%   |
| Goldstar                | 1         | 0.46%   |
| Eizo                    | 1         | 0.46%   |
| CSO                     | 1         | 0.46%   |
| BenQ                    | 1         | 0.46%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 3         | 1.37%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 3         | 1.37%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch        | 3         | 1.37%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch        | 3         | 1.37%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch  | 2         | 0.91%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch  | 2         | 0.91%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch  | 2         | 0.91%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 0.91%   |
| LG Display LCD Monitor LGD0390 1600x900 382x215mm 17.3-inch           | 2         | 0.91%   |
| LG Display LCD Monitor LGD01E9 1920x1080 345x194mm 15.6-inch          | 2         | 0.91%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch      | 2         | 0.91%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 2         | 0.91%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 2         | 0.91%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 340x190mm 15.3-inch       | 2         | 0.91%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                 | 2         | 0.91%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch         | 2         | 0.91%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 2         | 0.91%   |
| Unknown (AAA) LCDTV AAA0042 1360x768 890x500mm 40.2-inch              | 1         | 0.46%   |
| STA XR140EA1T STA0450 1366x768 310x174mm 14.0-inch                    | 1         | 0.46%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch               | 1         | 0.46%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch               | 1         | 0.46%   |
| Sharp LCD Monitor SHP143A 3840x2160 346x194mm 15.6-inch               | 1         | 0.46%   |
| Sceptre Tech Sceptre F24 SPT09AB 1920x1080 530x290mm 23.8-inch        | 1         | 0.46%   |
| SANYO LCD SAN0B51 1920x540                                            | 1         | 0.46%   |
| Samsung Electronics SyncMaster SAM0589 1920x1080 521x293mm 23.5-inch  | 1         | 0.46%   |
| Samsung Electronics SMT24A550 SAM07B5 1920x1080 531x299mm 24.0-inch   | 1         | 0.46%   |
| Samsung Electronics S27E510 SAM0C5F 1920x1080 600x340mm 27.2-inch     | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch  | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SEC4145 1366x768 309x174mm 14.0-inch  | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SEC3942 1366x768 309x174mm 14.0-inch  | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 367x230mm 17.1-inch  | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SEC345A 1366x768 309x174mm 14.0-inch  | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SEC314A 1920x1080 408x230mm 18.4-inch | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 277x156mm 12.5-inch  | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SDC3652 1366x768 344x194mm 15.5-inch  | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SAM0F3D 1366x768 522x293mm 23.6-inch  | 1         | 0.46%   |
| Philips PHL 276E9Q PHLC17B 1920x1080 598x336mm 27.0-inch              | 1         | 0.46%   |
| PANDA LCD Monitor NCP004B 1920x1080 344x194mm 15.5-inch               | 1         | 0.46%   |
| Panasonic LCD Monitor MEI96A2 2560x1440 309x173mm 13.9-inch           | 1         | 0.46%   |
| ONN ONA18HO015 ONN0101 1920x1080 698x393mm 31.5-inch                  | 1         | 0.46%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch         | 1         | 0.46%   |
| LG Display LP154WX4-TLCC LGD0242 1280x800 331x207mm 15.4-inch         | 1         | 0.46%   |
| LG Display LCD Monitor LGD0690 2560x1440 344x194mm 15.5-inch          | 1         | 0.46%   |
| LG Display LCD Monitor LGD0683 1920x1080 344x194mm 15.5-inch          | 1         | 0.46%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch          | 1         | 0.46%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch          | 1         | 0.46%   |
| LG Display LCD Monitor LGD05D2 1920x1080 344x194mm 15.5-inch          | 1         | 0.46%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch          | 1         | 0.46%   |
| LG Display LCD Monitor LGD0589 1920x1080 294x165mm 13.3-inch          | 1         | 0.46%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch          | 1         | 0.46%   |
| LG Display LCD Monitor LGD0557 1920x1080 309x174mm 14.0-inch          | 1         | 0.46%   |
| LG Display LCD Monitor LGD0503 1366x768 344x194mm 15.5-inch           | 1         | 0.46%   |
| LG Display LCD Monitor LGD04FA 1366x768 309x174mm 14.0-inch           | 1         | 0.46%   |
| LG Display LCD Monitor LGD045A 1366x768 293x165mm 13.2-inch           | 1         | 0.46%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch          | 1         | 0.46%   |
| LG Display LCD Monitor LGD03FD 1920x1080 276x156mm 12.5-inch          | 1         | 0.46%   |
| LG Display LCD Monitor LGD03F8 1366x768 345x194mm 15.6-inch           | 1         | 0.46%   |
| LG Display LCD Monitor LGD03E5 1366x768 309x174mm 14.0-inch           | 1         | 0.46%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 85        | 40.87%  |
| 1366x768 (WXGA)    | 76        | 36.54%  |
| 1600x900 (HD+)     | 16        | 7.69%   |
| 1280x800 (WXGA)    | 10        | 4.81%   |
| 3840x2160 (4K)     | 3         | 1.44%   |
| 1680x1050 (WSXGA+) | 3         | 1.44%   |
| 1440x900 (WXGA+)   | 3         | 1.44%   |
| 2880x1800          | 2         | 0.96%   |
| 2560x1600          | 2         | 0.96%   |
| 2560x1440 (QHD)    | 2         | 0.96%   |
| 2160x1440          | 2         | 0.96%   |
| 1920x540           | 1         | 0.48%   |
| 1920x1200 (WUXGA)  | 1         | 0.48%   |
| 1280x1024 (SXGA)   | 1         | 0.48%   |
| 1024x768 (XGA)     | 1         | 0.48%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 90        | 41.47%  |
| 14      | 33        | 15.21%  |
| 13      | 30        | 13.82%  |
| 17      | 22        | 10.14%  |
| 12      | 9         | 4.15%   |
| 27      | 4         | 1.84%   |
| 24      | 4         | 1.84%   |
| 21      | 4         | 1.84%   |
| 11      | 4         | 1.84%   |
| 31      | 3         | 1.38%   |
| 22      | 3         | 1.38%   |
| 23      | 2         | 0.92%   |
| 18      | 2         | 0.92%   |
| 16      | 2         | 0.92%   |
| 52      | 1         | 0.46%   |
| 40      | 1         | 0.46%   |
| 32      | 1         | 0.46%   |
| 19      | 1         | 0.46%   |
| Unknown | 1         | 0.46%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 143       | 66.2%   |
| 351-400     | 25        | 11.57%  |
| 201-300     | 23        | 10.65%  |
| 501-600     | 10        | 4.63%   |
| 401-500     | 8         | 3.7%    |
| 601-700     | 3         | 1.39%   |
| 801-900     | 1         | 0.46%   |
| 701-800     | 1         | 0.46%   |
| 1001-1500   | 1         | 0.46%   |
| Unknown     | 1         | 0.46%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 175       | 86.63%  |
| 16/10 | 22        | 10.89%  |
| 3/2   | 2         | 0.99%   |
| 6/5   | 1         | 0.5%    |
| 4/3   | 1         | 0.5%    |
| 32/9  | 1         | 0.5%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 91        | 41.94%  |
| 81-90          | 55        | 25.35%  |
| 121-130        | 19        | 8.76%   |
| 201-250        | 12        | 5.53%   |
| 61-70          | 9         | 4.15%   |
| 71-80          | 8         | 3.69%   |
| 51-60          | 4         | 1.84%   |
| 351-500        | 4         | 1.84%   |
| 301-350        | 4         | 1.84%   |
| 131-140        | 3         | 1.38%   |
| 141-150        | 2         | 0.92%   |
| More than 1000 | 1         | 0.46%   |
| 251-300        | 1         | 0.46%   |
| 151-200        | 1         | 0.46%   |
| 111-120        | 1         | 0.46%   |
| 501-1000       | 1         | 0.46%   |
| Unknown        | 1         | 0.46%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 89        | 41.2%   |
| 101-120       | 80        | 37.04%  |
| 51-100        | 28        | 12.96%  |
| 161-240       | 12        | 5.56%   |
| More than 240 | 3         | 1.39%   |
| 1-50          | 3         | 1.39%   |
| Unknown       | 1         | 0.46%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 173       | 86.5%   |
| 2     | 23        | 11.5%   |
| 3     | 3         | 1.5%    |
| 0     | 1         | 0.5%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 111       | 33.43%  |
| Realtek Semiconductor                  | 103       | 31.02%  |
| Qualcomm Atheros                       | 45        | 13.55%  |
| Broadcom                               | 22        | 6.63%   |
| Broadcom Limited                       | 7         | 2.11%   |
| Samsung Electronics                    | 6         | 1.81%   |
| MediaTek                               | 5         | 1.51%   |
| Qualcomm Atheros Communications        | 4         | 1.2%    |
| Huawei Technologies                    | 4         | 1.2%    |
| Xiaomi                                 | 3         | 0.9%    |
| TP-Link                                | 3         | 0.9%    |
| Ralink Technology                      | 3         | 0.9%    |
| NetGear                                | 2         | 0.6%    |
| ASUSTek Computer                       | 2         | 0.6%    |
| ASIX Electronics                       | 2         | 0.6%    |
| ZyXEL Communications                   | 1         | 0.3%    |
| Sony Ericsson Mobile Communications AB | 1         | 0.3%    |
| Sagem                                  | 1         | 0.3%    |
| Ralink                                 | 1         | 0.3%    |
| Nvidia                                 | 1         | 0.3%    |
| Linksys                                | 1         | 0.3%    |
| Lenovo                                 | 1         | 0.3%    |
| Ericsson Business Mobile Networks      | 1         | 0.3%    |
| Arduino SA                             | 1         | 0.3%    |
| Apple                                  | 1         | 0.3%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 51        | 12.59%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 27        | 6.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 10        | 2.47%   |
| Intel Wireless 8265 / 8275                                              | 8         | 1.98%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 8         | 1.98%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 8         | 1.98%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 7         | 1.73%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 7         | 1.73%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 1.73%   |
| Intel Wireless 7265                                                     | 7         | 1.73%   |
| Intel Wireless 7260                                                     | 7         | 1.73%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 7         | 1.73%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 1.48%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 1.48%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 1.48%   |
| Intel Ethernet Connection I218-LM                                       | 6         | 1.48%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 5         | 1.23%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller               | 5         | 1.23%   |
| Intel Wireless 3165                                                     | 5         | 1.23%   |
| Intel Wi-Fi 6 AX201                                                     | 5         | 1.23%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 1.23%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 1.23%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 4         | 0.99%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 0.99%   |
| Qualcomm Atheros AR9271 802.11n                                         | 4         | 0.99%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 4         | 0.99%   |
| Intel Wireless 8260                                                     | 4         | 0.99%   |
| Intel Wireless 3160                                                     | 4         | 0.99%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 0.99%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 0.99%   |
| Intel Centrino Advanced-N 6235                                          | 4         | 0.99%   |
| Broadcom BCM43142 802.11b/g/n                                           | 4         | 0.99%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 0.74%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 0.74%   |
| Realtek 802.11ac NIC                                                    | 3         | 0.74%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 3         | 0.74%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 3         | 0.74%   |
| Intel Ethernet Connection (6) I219-V                                    | 3         | 0.74%   |
| Intel Ethernet Connection (4) I219-LM                                   | 3         | 0.74%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 0.74%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 3         | 0.74%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 0.74%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 2         | 0.49%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.49%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 0.49%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.49%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                         | 2         | 0.49%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 0.49%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 0.49%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 0.49%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 2         | 0.49%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                        | 2         | 0.49%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 0.49%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.49%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 2         | 0.49%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.49%   |
| Intel Ultimate N WiFi Link 5300                                         | 2         | 0.49%   |
| Intel Ethernet Connection I217-V                                        | 2         | 0.49%   |
| Intel Ethernet Connection (3) I218-LM                                   | 2         | 0.49%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 107       | 47.14%  |
| Realtek Semiconductor           | 40        | 17.62%  |
| Qualcomm Atheros                | 33        | 14.54%  |
| Broadcom                        | 19        | 8.37%   |
| Broadcom Limited                | 6         | 2.64%   |
| Qualcomm Atheros Communications | 4         | 1.76%   |
| MediaTek                        | 4         | 1.76%   |
| TP-Link                         | 3         | 1.32%   |
| Ralink Technology               | 3         | 1.32%   |
| NetGear                         | 2         | 0.88%   |
| ASUSTek Computer                | 2         | 0.88%   |
| ZyXEL Communications            | 1         | 0.44%   |
| Sagem                           | 1         | 0.44%   |
| Ralink                          | 1         | 0.44%   |
| Linksys                         | 1         | 0.44%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 8         | 3.52%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 8         | 3.52%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 8         | 3.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 7         | 3.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 3.08%   |
| Intel Wireless 7265                                                     | 7         | 3.08%   |
| Intel Wireless 7260                                                     | 7         | 3.08%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 7         | 3.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 2.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 2.64%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 2.64%   |
| Intel Wireless 3165                                                     | 5         | 2.2%    |
| Intel Wi-Fi 6 AX201                                                     | 5         | 2.2%    |
| Intel Wi-Fi 6 AX200                                                     | 5         | 2.2%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 2.2%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 4         | 1.76%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 1.76%   |
| Qualcomm Atheros AR9271 802.11n                                         | 4         | 1.76%   |
| Intel Wireless 8260                                                     | 4         | 1.76%   |
| Intel Wireless 3160                                                     | 4         | 1.76%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 1.76%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 1.76%   |
| Intel Centrino Advanced-N 6235                                          | 4         | 1.76%   |
| Broadcom BCM43142 802.11b/g/n                                           | 4         | 1.76%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.32%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 1.32%   |
| Realtek 802.11ac NIC                                                    | 3         | 1.32%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 3         | 1.32%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 1.32%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 3         | 1.32%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 1.32%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.88%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 0.88%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.88%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                         | 2         | 0.88%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 0.88%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 0.88%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 0.88%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 0.88%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.88%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.88%   |
| Intel Ultimate N WiFi Link 5300                                         | 2         | 0.88%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 0.88%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 2         | 0.88%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 0.88%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 2         | 0.88%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 0.88%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 0.88%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 2         | 0.88%   |
| ZyXEL NWD2205 802.11n Wireless N Adapter [Realtek RTL8192CU]            | 1         | 0.44%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 0.44%   |
| Sagem XG-76NA 802.11bg                                                  | 1         | 0.44%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.44%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 0.44%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                     | 1         | 0.44%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1         | 0.44%   |
| Realtek RTL8187 Wireless Adapter                                        | 1         | 0.44%   |
| Ralink RT5372 Wireless Adapter                                          | 1         | 0.44%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 0.44%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                       | 1         | 0.44%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 89        | 52.66%  |
| Intel                 | 37        | 21.89%  |
| Qualcomm Atheros      | 19        | 11.24%  |
| Broadcom              | 7         | 4.14%   |
| Samsung Electronics   | 6         | 3.55%   |
| Xiaomi                | 3         | 1.78%   |
| ASIX Electronics      | 2         | 1.18%   |
| Nvidia                | 1         | 0.59%   |
| MediaTek              | 1         | 0.59%   |
| Lenovo                | 1         | 0.59%   |
| Huawei Technologies   | 1         | 0.59%   |
| Broadcom Limited      | 1         | 0.59%   |
| Apple                 | 1         | 0.59%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 51        | 29.65%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 27        | 15.7%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 5.81%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 4.07%   |
| Intel Ethernet Connection I218-LM                                 | 6         | 3.49%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 5         | 2.91%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 5         | 2.91%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4         | 2.33%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 1.74%   |
| Intel Ethernet Connection (6) I219-V                              | 3         | 1.74%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.74%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 1.16%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 1.16%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 1.16%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 1.16%   |
| Intel Ethernet Connection I217-V                                  | 2         | 1.16%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.16%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.16%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 1.16%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 2         | 1.16%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.58%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.58%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.58%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.58%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.58%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.58%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.58%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.58%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.58%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.58%   |
| Nvidia MCP89 Ethernet                                             | 1         | 0.58%   |
| MediaTek TECNO SPARK 3                                            | 1         | 0.58%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 0.58%   |
| Intel PRO/100 VE Network Connection                               | 1         | 0.58%   |
| Intel Ethernet controller                                         | 1         | 0.58%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.58%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.58%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.58%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.58%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.58%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 0.58%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.58%   |
| Huawei COL-L29                                                    | 1         | 0.58%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 0.58%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 0.58%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 0.58%   |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe         | 1         | 0.58%   |
| ASIX AX88772A Fast Ethernet                                       | 1         | 0.58%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 0.58%   |
| Apple iBridge                                                     | 1         | 0.58%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 197       | 54.42%  |
| Ethernet | 159       | 43.92%  |
| Modem    | 5         | 1.38%   |
| Unknown  | 1         | 0.28%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 168       | 78.5%   |
| Ethernet | 45        | 21.03%  |
| Unknown  | 1         | 0.47%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 143       | 71.86%  |
| 1     | 52        | 26.13%  |
| 3     | 2         | 1.01%   |
| 0     | 2         | 1.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Notebooks | Percent |
|---------|-----------|---------|
| No      | 170       | 84.16%  |
| Yes     | 31        | 15.35%  |
| Unknown | 1         | 0.5%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 82        | 50.62%  |
| Realtek Semiconductor           | 16        | 9.88%   |
| Qualcomm Atheros Communications | 16        | 9.88%   |
| Broadcom                        | 13        | 8.02%   |
| Lite-On Technology              | 6         | 3.7%    |
| Foxconn / Hon Hai               | 6         | 3.7%    |
| Apple                           | 6         | 3.7%    |
| MediaTek                        | 3         | 1.85%   |
| IMC Networks                    | 3         | 1.85%   |
| Dell                            | 3         | 1.85%   |
| Cambridge Silicon Radio         | 3         | 1.85%   |
| Toshiba                         | 2         | 1.23%   |
| Realtek                         | 1         | 0.62%   |
| Ralink                          | 1         | 0.62%   |
| Dynex                           | 1         | 0.62%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 35        | 21.6%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 18        | 11.11%  |
| Intel Bluetooth Device                                                              | 15        | 9.26%   |
| Realtek Bluetooth Radio                                                             | 8         | 4.94%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 8         | 4.94%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 5         | 3.09%   |
| Intel AX200 Bluetooth                                                               | 5         | 3.09%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 4         | 2.47%   |
| Broadcom HP Portable SoftSailing                                                    | 4         | 2.47%   |
| Apple Bluetooth Host Controller                                                     | 4         | 2.47%   |
| MediaTek Wireless_Device                                                            | 3         | 1.85%   |
| Dell DW375 Bluetooth Module                                                         | 3         | 1.85%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 3         | 1.85%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 3         | 1.85%   |
| Realtek RTL8821A Bluetooth                                                          | 2         | 1.23%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 2         | 1.23%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1.23%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 1.23%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 2         | 1.23%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 2         | 1.23%   |
| IMC Networks Bluetooth Device                                                       | 2         | 1.23%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 1.23%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 2         | 1.23%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 2         | 1.23%   |
| Apple Bluetooth USB Host Controller                                                 | 2         | 1.23%   |
| Toshiba Bluetooth USB Host Controller                                               | 1         | 0.62%   |
| Toshiba BCM43142A0                                                                  | 1         | 0.62%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.62%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.62%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.62%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.62%   |
| Qualcomm Atheros Bluetooth                                                          | 1         | 0.62%   |
| Lite-On Wireless_Device                                                             | 1         | 0.62%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.62%   |
| Lite-On Bluetooth Radio                                                             | 1         | 0.62%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 0.62%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 0.62%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 0.62%   |
| Intel AX210 Bluetooth                                                               | 1         | 0.62%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 0.62%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.62%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth                                       | 1         | 0.62%   |
| Dynex BCM20702A0                                                                    | 1         | 0.62%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 0.62%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 0.62%   |
| Broadcom BCM20702A0                                                                 | 1         | 0.62%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 0.62%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor    | Notebooks | Percent |
|-----------|-----------|---------|
| Intel     | 164       | 69.79%  |
| AMD       | 34        | 14.47%  |
| Nvidia    | 33        | 14.04%  |
| Lenovo    | 1         | 0.43%   |
| Guillemot | 1         | 0.43%   |
| GN Netcom | 1         | 0.43%   |
| Apple     | 1         | 0.43%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 26        | 9%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 20        | 6.92%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 17        | 5.88%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 13        | 4.5%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 12        | 4.15%   |
| Intel 8 Series HD Audio Controller                                                                | 12        | 4.15%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 10        | 3.46%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 10        | 3.46%   |
| Intel Cannon Lake PCH cAVS                                                                        | 10        | 3.46%   |
| Intel Broadwell-U Audio Controller                                                                | 10        | 3.46%   |
| AMD FCH Azalia Controller                                                                         | 9         | 3.11%   |
| Intel Comet Lake PCH cAVS                                                                         | 7         | 2.42%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 2.08%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 6         | 2.08%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 2.08%   |
| AMD Kabini HDMI/DP Audio                                                                          | 6         | 2.08%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 1.73%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 1.73%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 5         | 1.73%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 1.73%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1.38%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 4         | 1.38%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 1.38%   |
| Nvidia Audio device                                                                               | 4         | 1.38%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 1.38%   |
| AMD High Definition Audio Controller                                                              | 4         | 1.38%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 1.38%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 1.04%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 1.04%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 1.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1.04%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 1.04%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 1.04%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.04%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 3         | 1.04%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 1.04%   |
| Nvidia MCP89 High Definition Audio                                                                | 2         | 0.69%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.69%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.69%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 2         | 0.69%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 2         | 0.69%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 0.69%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.69%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 2         | 0.69%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.35%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.35%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.35%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.35%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 1         | 0.35%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.35%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.35%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                                      | 1         | 0.35%   |
| Intel USB PnP Sound Device                                                                        | 1         | 0.35%   |
| Intel Crystal Well HD Audio Controller                                                            | 1         | 0.35%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.35%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 0.35%   |
| Guillemot DJ Control Air                                                                          | 1         | 0.35%   |
| GN Netcom Jabra Evolve 65                                                                         | 1         | 0.35%   |
| Apple Audio Device                                                                                | 1         | 0.35%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 0.35%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 47        | 31.33%  |
| SK hynix            | 27        | 18%     |
| Micron Technology   | 25        | 16.67%  |
| Crucial             | 10        | 6.67%   |
| Kingston            | 9         | 6%      |
| Unknown             | 7         | 4.67%   |
| Ramaxel Technology  | 6         | 4%      |
| Elpida              | 6         | 4%      |
| Corsair             | 3         | 2%      |
| Unknown (ABCD)      | 2         | 1.33%   |
| Nanya Technology    | 2         | 1.33%   |
| G.Skill             | 2         | 1.33%   |
| A-DATA Technology   | 2         | 1.33%   |
| Team                | 1         | 0.67%   |
| Saikano             | 1         | 0.67%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 6         | 3.82%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 6         | 3.82%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 1.91%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 3         | 1.91%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 3         | 1.91%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 3         | 1.91%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8192MB SODIMM DDR4 2667MT/s             | 3         | 1.91%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s              | 3         | 1.91%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 2         | 1.27%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s           | 2         | 1.27%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 2         | 1.27%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 2         | 1.27%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s         | 2         | 1.27%   |
| Samsung RAM M471A1K43CB1-CRC 8192MB SODIMM DDR4 2667MT/s            | 2         | 1.27%   |
| Samsung RAM M4 70T2953CZ3-CE6 1GB SODIMM DDR 667MT/s                | 2         | 1.27%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8192MB Row Of Chips DDR4 3200MT/s       | 2         | 1.27%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s              | 2         | 1.27%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                          | 2         | 1.27%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                         | 1         | 0.64%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                         | 1         | 0.64%   |
| Unknown RAM Module 4096MB SODIMM DDR3                               | 1         | 0.64%   |
| Unknown RAM Module 4096MB SODIMM 1066MT/s                           | 1         | 0.64%   |
| Unknown RAM Module 2GB SODIMM DDR3                                  | 1         | 0.64%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                       | 1         | 0.64%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                          | 1         | 0.64%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                       | 1         | 0.64%   |
| Team RAM TEAMGROUP-SD4-2666 32GB SODIMM DDR4 2667MT/s               | 1         | 0.64%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s                | 1         | 0.64%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1066MT/s                     | 1         | 0.64%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1066MT/s                        | 1         | 0.64%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                       | 1         | 0.64%   |
| SK hynix RAM HMT851S6AMR6R-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 0.64%   |
| SK hynix RAM HMT851S6AMR6A-PB 4GB Chip DDR3 1600MT/s                | 1         | 0.64%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.64%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 0.64%   |
| SK hynix RAM HMT351S6BFR8C-H9 4096MB SODIMM DDR3 1334MT/s           | 1         | 0.64%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s              | 1         | 0.64%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s              | 1         | 0.64%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 1         | 0.64%   |
| SK hynix RAM HMA851S6DJR6N-XN 4096MB SODIMM DDR4 3200MT/s           | 1         | 0.64%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s        | 1         | 0.64%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s             | 1         | 0.64%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 0.64%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 1         | 0.64%   |
| SK hynix RAM H9HCNNNBKMALHR-NEE 4096MB Row Of Chips LPDDR4 4267MT/s | 1         | 0.64%   |
| Samsung RAM Module 2GB SODIMM LPDDR4 2400MT/s                       | 1         | 0.64%   |
| Samsung RAM Module 2048MB SODIMM DDR3 1333MT/s                      | 1         | 0.64%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                        | 1         | 0.64%   |
| Samsung RAM M474A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 1         | 0.64%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s               | 1         | 0.64%   |
| Samsung RAM M471B5173CB0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.64%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 0.64%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 0.64%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 0.64%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 1         | 0.64%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 1         | 0.64%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s              | 1         | 0.64%   |
| Samsung RAM M471A2K43DB1-CTD 16384MB SODIMM DDR4 2667MT/s           | 1         | 0.64%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s              | 1         | 0.64%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s              | 1         | 0.64%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 56        | 43.75%  |
| DDR3    | 52        | 40.63%  |
| LPDDR4  | 8         | 6.25%   |
| LPDDR3  | 5         | 3.91%   |
| DDR2    | 4         | 3.13%   |
| Unknown | 2         | 1.56%   |
| DDR     | 1         | 0.78%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 115       | 89.84%  |
| Row Of Chips | 11        | 8.59%   |
| Chip         | 1         | 0.78%   |
| Unknown      | 1         | 0.78%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 59        | 42.45%  |
| 8192  | 40        | 28.78%  |
| 16384 | 18        | 12.95%  |
| 2048  | 12        | 8.63%   |
| 1024  | 7         | 5.04%   |
| 32768 | 3         | 2.16%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 37        | 26.43%  |
| 1600    | 32        | 22.86%  |
| 3200    | 15        | 10.71%  |
| 1334    | 13        | 9.29%   |
| 2400    | 10        | 7.14%   |
| 2133    | 7         | 5%      |
| 1333    | 5         | 3.57%   |
| 3266    | 3         | 2.14%   |
| 1867    | 3         | 2.14%   |
| 1067    | 3         | 2.14%   |
| 1066    | 3         | 2.14%   |
| 667     | 3         | 2.14%   |
| Unknown | 2         | 1.43%   |
| 4800    | 1         | 0.71%   |
| 4267    | 1         | 0.71%   |
| 800     | 1         | 0.71%   |
| 533     | 1         | 0.71%   |

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
| Chicony Electronics                    | 55        | 30.05%  |
| Acer                                   | 23        | 12.57%  |
| Microdia                               | 17        | 9.29%   |
| IMC Networks                           | 17        | 9.29%   |
| Sunplus Innovation Technology          | 13        | 7.1%    |
| Realtek Semiconductor                  | 9         | 4.92%   |
| Apple                                  | 7         | 3.83%   |
| Quanta                                 | 6         | 3.28%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 3.28%   |
| Ricoh                                  | 5         | 2.73%   |
| Suyin                                  | 3         | 1.64%   |
| Silicon Motion                         | 3         | 1.64%   |
| Samsung Electronics                    | 3         | 1.64%   |
| Luxvisions Innotech Limited            | 3         | 1.64%   |
| Lite-On Technology                     | 3         | 1.64%   |
| Alcor Micro                            | 3         | 1.64%   |
| Syntek                                 | 2         | 1.09%   |
| Primax Electronics                     | 1         | 0.55%   |
| LG Electronics                         | 1         | 0.55%   |
| Importek                               | 1         | 0.55%   |
| Goertek Electronics                    | 1         | 0.55%   |
| ALi                                    | 1         | 0.55%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 8         | 4.37%   |
| Acer HD Webcam                                      | 6         | 3.28%   |
| Realtek Integrated_Webcam_HD                        | 5         | 2.73%   |
| IMC Networks Integrated Camera                      | 5         | 2.73%   |
| Chicony HD Webcam                                   | 5         | 2.73%   |
| Sunplus Integrated_Webcam_HD                        | 4         | 2.19%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 4         | 2.19%   |
| Chicony HP TrueVision HD                            | 4         | 2.19%   |
| Chicony HD User Facing                              | 4         | 2.19%   |
| Acer EasyCamera                                     | 4         | 2.19%   |
| Samsung Galaxy series, misc. (MTP mode)             | 3         | 1.64%   |
| Microdia Webcam Vitade AF                           | 3         | 1.64%   |
| Microdia Integrated_Webcam_HD                       | 3         | 1.64%   |
| Microdia Integrated Webcam                          | 3         | 1.64%   |
| Chicony USB2.0 HD UVC WebCam                        | 3         | 1.64%   |
| Chicony USB2.0 Camera                               | 3         | 1.64%   |
| Alcor Micro USB 2.0 Camera                          | 3         | 1.64%   |
| Acer SunplusIT Integrated Camera                    | 3         | 1.64%   |
| Syntek Integrated Camera                            | 2         | 1.09%   |
| Sunplus HD WebCam                                   | 2         | 1.09%   |
| Realtek Integrated Webcam                           | 2         | 1.09%   |
| Quanta VGA WebCam                                   | 2         | 1.09%   |
| Quanta HP TrueVision HD Camera                      | 2         | 1.09%   |
| Microdia PC Microscope camera                       | 2         | 1.09%   |
| Microdia Laptop_Integrated_Webcam_HD                | 2         | 1.09%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 2         | 1.09%   |
| Lite-On HP Wide Vision HD Camera                    | 2         | 1.09%   |
| IMC Networks HD Camera                              | 2         | 1.09%   |
| Chicony USB2.0 VGA UVC WebCam                       | 2         | 1.09%   |
| Chicony TOSHIBA Web Camera - HD                     | 2         | 1.09%   |
| Chicony Integrated HP HD Webcam                     | 2         | 1.09%   |
| Chicony Integrated Camera (1280x720@30)             | 2         | 1.09%   |
| Chicony HP HD Webcam [Fixed]                        | 2         | 1.09%   |
| Chicony HP HD Camera                                | 2         | 1.09%   |
| Chicony EasyCamera                                  | 2         | 1.09%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 2         | 1.09%   |
| Apple iPhone 5/5C/5S/6/SE                           | 2         | 1.09%   |
| Apple FaceTime HD Camera                            | 2         | 1.09%   |
| Acer Lenovo EasyCamera                              | 2         | 1.09%   |
| Acer Integrated Camera                              | 2         | 1.09%   |
| Acer HD Camera                                      | 2         | 1.09%   |
| Suyin Integrated_Webcam_HD                          | 1         | 0.55%   |
| Suyin HP Truevision HD                              | 1         | 0.55%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 0.55%   |
| Sunplus Laptop_Integrated_Webcam_HD                 | 1         | 0.55%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 1         | 0.55%   |
| Sunplus Laptop Integrated Webcam FHD                | 1         | 0.55%   |
| Sunplus Integrated Camera                           | 1         | 0.55%   |
| Sunplus HP HD Webcam [Fixed]                        | 1         | 0.55%   |
| Sunplus FHD Camera Microphone                       | 1         | 0.55%   |
| Sunplus Asus Webcam                                 | 1         | 0.55%   |
| Silicon Motion WebCam SCB-0385N                     | 1         | 0.55%   |
| Silicon Motion WebCam SC-13HDL11939N                | 1         | 0.55%   |
| Silicon Motion WebCam SC-03FFL11939N                | 1         | 0.55%   |
| Ricoh USB2.0 Camera                                 | 1         | 0.55%   |
| Ricoh Pavilion Webcam                               | 1         | 0.55%   |
| Ricoh Laptop_Integrated_Webcam_FHD                  | 1         | 0.55%   |
| Ricoh Integrated Webcam                             | 1         | 0.55%   |
| Ricoh HD Webcam                                     | 1         | 0.55%   |
| Realtek Integrated Webcam HD                        | 1         | 0.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 17        | 53.13%  |
| Synaptics                  | 7         | 21.88%  |
| Shenzhen Goodix Technology | 3         | 9.38%   |
| LighTuning Technology      | 2         | 6.25%   |
| Elan Microelectronics      | 2         | 6.25%   |
| AuthenTec                  | 1         | 3.13%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 9.38%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 9.38%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 9.38%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 2         | 6.25%   |
| Validity Sensors VFS491                                                    | 2         | 6.25%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 6.25%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 6.25%   |
| Shenzhen Goodix  Fingerprint Device                                        | 2         | 6.25%   |
| Elan ELAN:Fingerprint                                                      | 2         | 6.25%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 3.13%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 3.13%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 3.13%   |
| Synaptics  WBDI                                                            | 1         | 3.13%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 3.13%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 3.13%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 3.13%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 3.13%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 3.13%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 3.13%   |
| Unknown                                                                    | 1         | 3.13%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 8         | 57.14%  |
| Alcor Micro | 4         | 28.57%  |
| OmniKey     | 1         | 7.14%   |
| O2 Micro    | 1         | 7.14%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 35.71%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 4         | 28.57%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 14.29%  |
| OmniKey CardMan Smart@Link                                                   | 1         | 7.14%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 7.14%   |
| Broadcom 5880                                                                | 1         | 7.14%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 117       | 57.64%  |
| 1     | 70        | 34.48%  |
| 2     | 15        | 7.39%   |
| 3     | 1         | 0.49%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 33        | 33.33%  |
| Graphics card         | 16        | 16.16%  |
| Chipcard              | 13        | 13.13%  |
| Net/wireless          | 12        | 12.12%  |
| Multimedia controller | 10        | 10.1%   |
| Camera                | 6         | 6.06%   |
| Storage               | 4         | 4.04%   |
| Network               | 2         | 2.02%   |
| Modem                 | 1         | 1.01%   |
| Card reader           | 1         | 1.01%   |
| Bluetooth             | 1         | 1.01%   |

