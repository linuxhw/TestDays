Parrot - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Parrot.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Parrot/Desktop/README.md) and [notebooks](/Dist/Parrot/Notebook/README.md).

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

Total: 392

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [c4468417e9](https://linux-hardware.org/?probe=c4468417e9) | Jun 01, 2022 |
| Lenovo        | ThinkPad X230 2325N66       | Notebook    | [2061351dbc](https://linux-hardware.org/?probe=2061351dbc) | May 28, 2022 |
| Dell          | Latitude E6540              | Notebook    | [9171fd4d35](https://linux-hardware.org/?probe=9171fd4d35) | May 26, 2022 |
| Dell          | Latitude E6540              | Notebook    | [e7a078f1a1](https://linux-hardware.org/?probe=e7a078f1a1) | May 26, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [dbf37b46f6](https://linux-hardware.org/?probe=dbf37b46f6) | May 25, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [9fcb918138](https://linux-hardware.org/?probe=9fcb918138) | May 25, 2022 |
| Dell          | Latitude 5400               | Notebook    | [fdfa7356be](https://linux-hardware.org/?probe=fdfa7356be) | May 23, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 80X4     | Notebook    | [aa6aefb86a](https://linux-hardware.org/?probe=aa6aefb86a) | May 21, 2022 |
| Lenovo        | 31900058 STD                | Desktop     | [cb4959b996](https://linux-hardware.org/?probe=cb4959b996) | May 21, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [fb7cb376e9](https://linux-hardware.org/?probe=fb7cb376e9) | May 21, 2022 |
| Dell          | Latitude E6410              | Notebook    | [b098a84988](https://linux-hardware.org/?probe=b098a84988) | May 20, 2022 |
| MSI           | G31M3-L V2                  | Desktop     | [29d45c64bb](https://linux-hardware.org/?probe=29d45c64bb) | May 11, 2022 |
| MSI           | GE62 6QE                    | Notebook    | [6a3161d4ee](https://linux-hardware.org/?probe=6a3161d4ee) | May 09, 2022 |
| Timi          | TM1613                      | Notebook    | [114752ffeb](https://linux-hardware.org/?probe=114752ffeb) | May 08, 2022 |
| Timi          | TM1613                      | Notebook    | [b714f7dbd8](https://linux-hardware.org/?probe=b714f7dbd8) | May 08, 2022 |
| HP            | 1495                        | Desktop     | [c845f7b657](https://linux-hardware.org/?probe=c845f7b657) | May 05, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [60a636868c](https://linux-hardware.org/?probe=60a636868c) | Apr 30, 2022 |
| SLIMBOOK      | ONE-AMD-M4                  | Desktop     | [99911022e9](https://linux-hardware.org/?probe=99911022e9) | Apr 26, 2022 |
| ASUSTek       | ROG Strix G733ZX_G733ZX     | Notebook    | [032acaf88c](https://linux-hardware.org/?probe=032acaf88c) | Apr 25, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [56d949b3bb](https://linux-hardware.org/?probe=56d949b3bb) | Apr 23, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [0ee15f97fd](https://linux-hardware.org/?probe=0ee15f97fd) | Apr 23, 2022 |
| Dell          | Inspiron 15 5510            | Notebook    | [73a8933099](https://linux-hardware.org/?probe=73a8933099) | Apr 22, 2022 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [4d911b0d94](https://linux-hardware.org/?probe=4d911b0d94) | Apr 22, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [9c06485301](https://linux-hardware.org/?probe=9c06485301) | Apr 21, 2022 |
| HP            | 18E7                        | Desktop     | [1b6db66cc1](https://linux-hardware.org/?probe=1b6db66cc1) | Apr 19, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [b68f986aaf](https://linux-hardware.org/?probe=b68f986aaf) | Apr 17, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [93306ff9ee](https://linux-hardware.org/?probe=93306ff9ee) | Apr 17, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [7e03ed9f70](https://linux-hardware.org/?probe=7e03ed9f70) | Apr 13, 2022 |
| Apple         | MacBookPro15,1              | Notebook    | [b9187e8521](https://linux-hardware.org/?probe=b9187e8521) | Apr 13, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [bdccad7bf9](https://linux-hardware.org/?probe=bdccad7bf9) | Apr 12, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [cee28f4953](https://linux-hardware.org/?probe=cee28f4953) | Apr 12, 2022 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [0832404b40](https://linux-hardware.org/?probe=0832404b40) | Apr 11, 2022 |
| MSI           | B350 TOMAHAWK               | Desktop     | [b1a322fa38](https://linux-hardware.org/?probe=b1a322fa38) | Apr 11, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [b3afe4ff08](https://linux-hardware.org/?probe=b3afe4ff08) | Apr 11, 2022 |
| ASUSTek       | X540SAA                     | Notebook    | [b670324e44](https://linux-hardware.org/?probe=b670324e44) | Apr 10, 2022 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [8cb4405c5f](https://linux-hardware.org/?probe=8cb4405c5f) | Apr 09, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [320ae25dbf](https://linux-hardware.org/?probe=320ae25dbf) | Apr 09, 2022 |
| Toshiba       | Satellite Click 2 L35W-B    | Notebook    | [f992f9305a](https://linux-hardware.org/?probe=f992f9305a) | Apr 07, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [e422a0e166](https://linux-hardware.org/?probe=e422a0e166) | Apr 05, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [b96e97fa2b](https://linux-hardware.org/?probe=b96e97fa2b) | Apr 04, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [401792c28e](https://linux-hardware.org/?probe=401792c28e) | Apr 01, 2022 |
| Alienware     | M14xR1                      | Notebook    | [f3ea3f497c](https://linux-hardware.org/?probe=f3ea3f497c) | Apr 01, 2022 |
| HP            | Notebook                    | Notebook    | [313ca81d16](https://linux-hardware.org/?probe=313ca81d16) | Mar 27, 2022 |
| ECS           | Nettle2                     | Desktop     | [4939d60e6d](https://linux-hardware.org/?probe=4939d60e6d) | Mar 27, 2022 |
| HP            | 18E7                        | Desktop     | [d8d1c3d468](https://linux-hardware.org/?probe=d8d1c3d468) | Mar 26, 2022 |
| ASUSTek       | X540SAA                     | Notebook    | [988b4570ed](https://linux-hardware.org/?probe=988b4570ed) | Mar 24, 2022 |
| Lenovo        | ThinkPad E15 20RD0086UE     | Notebook    | [f26a636b1b](https://linux-hardware.org/?probe=f26a636b1b) | Mar 24, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [72245fe662](https://linux-hardware.org/?probe=72245fe662) | Mar 22, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [85260f6ed1](https://linux-hardware.org/?probe=85260f6ed1) | Mar 20, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [e849ec3916](https://linux-hardware.org/?probe=e849ec3916) | Mar 20, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [b0769dffdd](https://linux-hardware.org/?probe=b0769dffdd) | Mar 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [2c1ca9145b](https://linux-hardware.org/?probe=2c1ca9145b) | Mar 18, 2022 |
| ASUSTek       | H170M-E D3                  | Desktop     | [167928d6e9](https://linux-hardware.org/?probe=167928d6e9) | Mar 17, 2022 |
| Wistron       | JIG31B3                     | Desktop     | [a360eaf501](https://linux-hardware.org/?probe=a360eaf501) | Mar 15, 2022 |
| ASUSTek       | H170M-E D3                  | Desktop     | [937c0097ca](https://linux-hardware.org/?probe=937c0097ca) | Mar 14, 2022 |
| Toshiba       | Satellite L775D             | Notebook    | [3d09dbe623](https://linux-hardware.org/?probe=3d09dbe623) | Mar 14, 2022 |
| Positivo      | Q232A                       | Notebook    | [87c79b8f05](https://linux-hardware.org/?probe=87c79b8f05) | Mar 13, 2022 |
| ASUSTek       | F2A85-M                     | Desktop     | [36d17e4fdb](https://linux-hardware.org/?probe=36d17e4fdb) | Mar 13, 2022 |
| ASUSTek       | F2A85-M                     | Desktop     | [453d0816b3](https://linux-hardware.org/?probe=453d0816b3) | Mar 13, 2022 |
| ASRock        | Z87M Extreme4               | Desktop     | [dba57ee1b3](https://linux-hardware.org/?probe=dba57ee1b3) | Mar 12, 2022 |
| ASUSTek       | X75VC                       | Notebook    | [3973070120](https://linux-hardware.org/?probe=3973070120) | Mar 12, 2022 |
| Jumper        | EZbook                      | Notebook    | [c374bd5058](https://linux-hardware.org/?probe=c374bd5058) | Mar 11, 2022 |
| Apple         | MacBookAir3,1               | Notebook    | [320f9e6841](https://linux-hardware.org/?probe=320f9e6841) | Mar 11, 2022 |
| Metabox       | Edge-Pro NS50MU             | Notebook    | [1371afa6ac](https://linux-hardware.org/?probe=1371afa6ac) | Mar 11, 2022 |
| MSI           | G31M3-L V2                  | Desktop     | [4c15ba6fb9](https://linux-hardware.org/?probe=4c15ba6fb9) | Mar 10, 2022 |
| Apple         | MacBookPro11,4              | Notebook    | [b27d8c8724](https://linux-hardware.org/?probe=b27d8c8724) | Mar 10, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [e77116d171](https://linux-hardware.org/?probe=e77116d171) | Mar 10, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [161eda858b](https://linux-hardware.org/?probe=161eda858b) | Mar 10, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [36bada67c8](https://linux-hardware.org/?probe=36bada67c8) | Mar 08, 2022 |
| Dell          | Latitude XT2                | Notebook    | [ff6a48346f](https://linux-hardware.org/?probe=ff6a48346f) | Mar 07, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [f9c159a911](https://linux-hardware.org/?probe=f9c159a911) | Mar 06, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [ec13383aff](https://linux-hardware.org/?probe=ec13383aff) | Mar 06, 2022 |
| Jumper        | EZbook                      | Notebook    | [09544efb61](https://linux-hardware.org/?probe=09544efb61) | Mar 05, 2022 |
| Apple         | MacBookPro11,4              | Notebook    | [fb03915a3e](https://linux-hardware.org/?probe=fb03915a3e) | Mar 03, 2022 |
| SLIMBOOK      | ONE-AMD-M4                  | Desktop     | [d92c05a18a](https://linux-hardware.org/?probe=d92c05a18a) | Mar 03, 2022 |
| Daewoo Luc... | Solo Top                    | Desktop     | [7f7b20688f](https://linux-hardware.org/?probe=7f7b20688f) | Mar 03, 2022 |
| Jumper        | EZbook                      | Notebook    | [de9a14c4ec](https://linux-hardware.org/?probe=de9a14c4ec) | Mar 02, 2022 |
| Chuwi         | GemiBook                    | Notebook    | [bb9f45273a](https://linux-hardware.org/?probe=bb9f45273a) | Mar 01, 2022 |
| SLIMBOOK      | ONE-AMD-M4                  | Desktop     | [dc43686a5a](https://linux-hardware.org/?probe=dc43686a5a) | Feb 27, 2022 |
| Samsung       | 550P5C/550P7C               | Notebook    | [f14f73025f](https://linux-hardware.org/?probe=f14f73025f) | Feb 27, 2022 |
| Dell          | 0GXM1W A02                  | Desktop     | [044a00e086](https://linux-hardware.org/?probe=044a00e086) | Feb 25, 2022 |
| Toshiba       | Satellite C75D-B            | Notebook    | [952057ee2b](https://linux-hardware.org/?probe=952057ee2b) | Feb 24, 2022 |
| Acer          | Nitro AN517-41              | Notebook    | [47b906a661](https://linux-hardware.org/?probe=47b906a661) | Feb 23, 2022 |
| Chuwi         | GemiBook                    | Notebook    | [25f5f358cb](https://linux-hardware.org/?probe=25f5f358cb) | Feb 17, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [f83ccc9cce](https://linux-hardware.org/?probe=f83ccc9cce) | Feb 15, 2022 |
| Sony          | SVP1321L1EBI                | Notebook    | [b35a3fbfec](https://linux-hardware.org/?probe=b35a3fbfec) | Feb 13, 2022 |
| HP            | ProBook 4535s               | Notebook    | [0d0cd13f8b](https://linux-hardware.org/?probe=0d0cd13f8b) | Feb 12, 2022 |
| ASUSTek       | Benicia                     | Desktop     | [aceee2d932](https://linux-hardware.org/?probe=aceee2d932) | Feb 12, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [0df06bcae3](https://linux-hardware.org/?probe=0df06bcae3) | Feb 11, 2022 |
| HP            | Notebook                    | Notebook    | [1f47143486](https://linux-hardware.org/?probe=1f47143486) | Feb 06, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [9f4f77f51d](https://linux-hardware.org/?probe=9f4f77f51d) | Feb 06, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [b6d5344f4e](https://linux-hardware.org/?probe=b6d5344f4e) | Feb 04, 2022 |
| SLIMBOOK      | ONE-AMD-M4                  | Desktop     | [225e399fc1](https://linux-hardware.org/?probe=225e399fc1) | Feb 03, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [5aa1140ad5](https://linux-hardware.org/?probe=5aa1140ad5) | Feb 02, 2022 |
| Lenovo        | ThinkPad T480 20L6SCYP00    | Notebook    | [d69eb6fc3e](https://linux-hardware.org/?probe=d69eb6fc3e) | Jan 30, 2022 |
| GPU Compan... | GWTN141-10                  | Notebook    | [89835cd678](https://linux-hardware.org/?probe=89835cd678) | Jan 30, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [880cca4c8f](https://linux-hardware.org/?probe=880cca4c8f) | Jan 24, 2022 |
| Microsoft     | Surface Book                | Tablet      | [327a2ec07f](https://linux-hardware.org/?probe=327a2ec07f) | Jan 22, 2022 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [1e5331da8c](https://linux-hardware.org/?probe=1e5331da8c) | Jan 21, 2022 |
| Dell          | Latitude 7480               | Notebook    | [e184163da5](https://linux-hardware.org/?probe=e184163da5) | Jan 19, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [9901f0a14a](https://linux-hardware.org/?probe=9901f0a14a) | Jan 18, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [3837c06ca1](https://linux-hardware.org/?probe=3837c06ca1) | Jan 18, 2022 |
| Dell          | Inspiron 5580               | Notebook    | [a8e7059c51](https://linux-hardware.org/?probe=a8e7059c51) | Jan 17, 2022 |
| Lenovo        | ThinkPad E14 20RA0016GE     | Notebook    | [46eeb2d4b8](https://linux-hardware.org/?probe=46eeb2d4b8) | Jan 14, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [4e45161acc](https://linux-hardware.org/?probe=4e45161acc) | Jan 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [4c04661023](https://linux-hardware.org/?probe=4c04661023) | Jan 12, 2022 |
| Unknown       | Unknown                     | Desktop     | [bccc675fea](https://linux-hardware.org/?probe=bccc675fea) | Jan 08, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [8f4b5410ad](https://linux-hardware.org/?probe=8f4b5410ad) | Jan 06, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [f75ebfbbc8](https://linux-hardware.org/?probe=f75ebfbbc8) | Jan 01, 2022 |
| Dell          | 04YP6J A01                  | Desktop     | [680408ec06](https://linux-hardware.org/?probe=680408ec06) | Jan 01, 2022 |
| Dell          | 04YP6J A01                  | Desktop     | [623d384766](https://linux-hardware.org/?probe=623d384766) | Jan 01, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [4ec2105ead](https://linux-hardware.org/?probe=4ec2105ead) | Jan 01, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [d0c5b453db](https://linux-hardware.org/?probe=d0c5b453db) | Dec 31, 2021 |
| Lenovo        | IdeaPad Y580                | Notebook    | [cbb37b3b6a](https://linux-hardware.org/?probe=cbb37b3b6a) | Dec 20, 2021 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [5c55046f50](https://linux-hardware.org/?probe=5c55046f50) | Dec 13, 2021 |
| Lenovo        | IdeaPad Y580                | Notebook    | [48d92517e3](https://linux-hardware.org/?probe=48d92517e3) | Dec 11, 2021 |
| Dell          | Precision M4600             | Notebook    | [f386251b14](https://linux-hardware.org/?probe=f386251b14) | Nov 30, 2021 |
| Alienware     | m15 R6                      | Notebook    | [487678d2e5](https://linux-hardware.org/?probe=487678d2e5) | Nov 27, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [550ad36300](https://linux-hardware.org/?probe=550ad36300) | Nov 26, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [db67630cee](https://linux-hardware.org/?probe=db67630cee) | Nov 26, 2021 |
| Toxic         | GM7MQ8P                     | Notebook    | [deb5cbd490](https://linux-hardware.org/?probe=deb5cbd490) | Nov 24, 2021 |
| MSI           | Creator Z16 Hiroshi F A1... | Notebook    | [40f615079d](https://linux-hardware.org/?probe=40f615079d) | Nov 23, 2021 |
| HP            | ZBook Firefly 14 G7 Mobi... | Notebook    | [0dc4672364](https://linux-hardware.org/?probe=0dc4672364) | Nov 21, 2021 |
| Alienware     | 0PGRP5 A02                  | Desktop     | [aeacaefd26](https://linux-hardware.org/?probe=aeacaefd26) | Nov 14, 2021 |
| ASRock        | Z87 Killer                  | Desktop     | [0aafc0d981](https://linux-hardware.org/?probe=0aafc0d981) | Nov 13, 2021 |
| Toshiba       | Satellite L655              | Notebook    | [e41f3dd777](https://linux-hardware.org/?probe=e41f3dd777) | Nov 12, 2021 |
| Dell          | Latitude E6410              | Notebook    | [2f9b89dbb4](https://linux-hardware.org/?probe=2f9b89dbb4) | Nov 09, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [6ef3dbe032](https://linux-hardware.org/?probe=6ef3dbe032) | Nov 09, 2021 |
| Dell          | Latitude E6410              | Notebook    | [099708f286](https://linux-hardware.org/?probe=099708f286) | Nov 07, 2021 |
| Acer          | TravelMate 5720             | Notebook    | [8e19effec8](https://linux-hardware.org/?probe=8e19effec8) | Nov 06, 2021 |
| HP            | Pavilion g7                 | Notebook    | [c1b5449516](https://linux-hardware.org/?probe=c1b5449516) | Nov 05, 2021 |
| Acer          | Aspire TC-780               | Desktop     | [f6de1ed637](https://linux-hardware.org/?probe=f6de1ed637) | Nov 04, 2021 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [833500916c](https://linux-hardware.org/?probe=833500916c) | Nov 03, 2021 |
| Lenovo        | B50-80 80EW                 | Notebook    | [37a983c1e7](https://linux-hardware.org/?probe=37a983c1e7) | Oct 26, 2021 |
| Lenovo        | B50-80 80EW                 | Notebook    | [ca3a74943a](https://linux-hardware.org/?probe=ca3a74943a) | Oct 25, 2021 |
| Dell          | Latitude E7450              | Notebook    | [2d94d751ff](https://linux-hardware.org/?probe=2d94d751ff) | Oct 22, 2021 |
| Dell          | Latitude E7450              | Notebook    | [a2b09ead76](https://linux-hardware.org/?probe=a2b09ead76) | Oct 22, 2021 |
| MSI           | GT60 2OC/2OD                | Notebook    | [56c85806e2](https://linux-hardware.org/?probe=56c85806e2) | Oct 20, 2021 |
| HP            | Laptop 15q-dy0xxx           | Notebook    | [aa4c6c2a25](https://linux-hardware.org/?probe=aa4c6c2a25) | Oct 18, 2021 |
| Dell          | Inspiron MM061              | Notebook    | [5b16f69a60](https://linux-hardware.org/?probe=5b16f69a60) | Oct 17, 2021 |
| Dell          | Inspiron MM061              | Notebook    | [caa2855c26](https://linux-hardware.org/?probe=caa2855c26) | Oct 17, 2021 |
| HP            | Pavilion g7                 | Notebook    | [7e80ec4599](https://linux-hardware.org/?probe=7e80ec4599) | Oct 11, 2021 |
| HP            | Pavilion g7                 | Notebook    | [cd8ce3be30](https://linux-hardware.org/?probe=cd8ce3be30) | Oct 10, 2021 |
| HP            | Pavilion g7                 | Notebook    | [dd3f8159e0](https://linux-hardware.org/?probe=dd3f8159e0) | Oct 10, 2021 |
| MSI           | GT60 2OC/2OD                | Notebook    | [79e12d69ec](https://linux-hardware.org/?probe=79e12d69ec) | Oct 08, 2021 |
| Dell          | 0T2HR0 A00                  | Desktop     | [dc55f173fe](https://linux-hardware.org/?probe=dc55f173fe) | Oct 05, 2021 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [7dcd6067ac](https://linux-hardware.org/?probe=7dcd6067ac) | Oct 04, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [d0cd1577c7](https://linux-hardware.org/?probe=d0cd1577c7) | Oct 04, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [fb11994deb](https://linux-hardware.org/?probe=fb11994deb) | Oct 04, 2021 |
| Dell          | Inspiron 7501               | Notebook    | [1d532e72c0](https://linux-hardware.org/?probe=1d532e72c0) | Oct 02, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [b33c31b0cf](https://linux-hardware.org/?probe=b33c31b0cf) | Oct 02, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [eafc16e86f](https://linux-hardware.org/?probe=eafc16e86f) | Sep 24, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [3eac62e012](https://linux-hardware.org/?probe=3eac62e012) | Sep 24, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [b733e7fac1](https://linux-hardware.org/?probe=b733e7fac1) | Sep 23, 2021 |
| MSI           | GS66 Stealth 10UG           | Notebook    | [c57bcaa35d](https://linux-hardware.org/?probe=c57bcaa35d) | Sep 19, 2021 |
| Lenovo        | B50-80 80EW                 | Notebook    | [493f8d65cb](https://linux-hardware.org/?probe=493f8d65cb) | Sep 18, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [09b7566e74](https://linux-hardware.org/?probe=09b7566e74) | Sep 14, 2021 |
| Acer          | TravelMate 5720             | Notebook    | [b08ac328d1](https://linux-hardware.org/?probe=b08ac328d1) | Sep 14, 2021 |
| Eluktronic... | MAG-15u                     | Notebook    | [f931222022](https://linux-hardware.org/?probe=f931222022) | Sep 13, 2021 |
| Acer          | Swift SF114-33              | Notebook    | [31bc470f08](https://linux-hardware.org/?probe=31bc470f08) | Sep 11, 2021 |
| Lenovo        | ThinkPad X250 20CL001GZA    | Notebook    | [e732588a09](https://linux-hardware.org/?probe=e732588a09) | Sep 05, 2021 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [ede284a3a3](https://linux-hardware.org/?probe=ede284a3a3) | Aug 30, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [03676f1856](https://linux-hardware.org/?probe=03676f1856) | Aug 28, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [41663f4fb2](https://linux-hardware.org/?probe=41663f4fb2) | Aug 26, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [0460f1a29b](https://linux-hardware.org/?probe=0460f1a29b) | Aug 24, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [2ef0cf3a18](https://linux-hardware.org/?probe=2ef0cf3a18) | Aug 16, 2021 |
| Dell          | Inspiron 5593               | Notebook    | [340be8f7fb](https://linux-hardware.org/?probe=340be8f7fb) | Aug 15, 2021 |
| Lenovo        | B50-80 80EW                 | Notebook    | [bd70ed892a](https://linux-hardware.org/?probe=bd70ed892a) | Aug 14, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [b741d2ab2b](https://linux-hardware.org/?probe=b741d2ab2b) | Aug 12, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [3ba02ffef3](https://linux-hardware.org/?probe=3ba02ffef3) | Aug 10, 2021 |
| HP            | Pavilion dv6700             | Notebook    | [8714c1e6ab](https://linux-hardware.org/?probe=8714c1e6ab) | Aug 10, 2021 |
| MSI           | GT60 2OC/2OD                | Notebook    | [5ff69797f3](https://linux-hardware.org/?probe=5ff69797f3) | Aug 09, 2021 |
| ASUSTek       | X75VB                       | Notebook    | [bc26a9b439](https://linux-hardware.org/?probe=bc26a9b439) | Aug 07, 2021 |
| HP            | Pavilion 15                 | Notebook    | [f0f33cb33a](https://linux-hardware.org/?probe=f0f33cb33a) | Aug 06, 2021 |
| Dell          | Latitude E6420              | Notebook    | [9e72687dd4](https://linux-hardware.org/?probe=9e72687dd4) | Aug 05, 2021 |
| Microsoft     | Surface Pro 3               | Tablet      | [57037eb714](https://linux-hardware.org/?probe=57037eb714) | Aug 05, 2021 |
| Microsoft     | Surface Pro 3               | Tablet      | [89852ab731](https://linux-hardware.org/?probe=89852ab731) | Aug 05, 2021 |
| HP            | Pavilion dv7                | Notebook    | [5d8cfc9c95](https://linux-hardware.org/?probe=5d8cfc9c95) | Aug 04, 2021 |
| HP            | Pavilion dv7                | Notebook    | [1d2d7a30f9](https://linux-hardware.org/?probe=1d2d7a30f9) | Aug 04, 2021 |
| ZOTAC         | Unknown                     | Desktop     | [0324aff0a3](https://linux-hardware.org/?probe=0324aff0a3) | Aug 03, 2021 |
| ZOTAC         | Unknown                     | Desktop     | [c1a9e01bd7](https://linux-hardware.org/?probe=c1a9e01bd7) | Aug 03, 2021 |
| ASUSTek       | G74Sx                       | Notebook    | [fb80932ddd](https://linux-hardware.org/?probe=fb80932ddd) | Jul 23, 2021 |
| HP            | 1850                        | Desktop     | [687c780f5c](https://linux-hardware.org/?probe=687c780f5c) | Jul 19, 2021 |
| Dell          | Latitude E7440              | Notebook    | [3a22179f3b](https://linux-hardware.org/?probe=3a22179f3b) | Jul 18, 2021 |
| Dell          | 0T10XW A02                  | Desktop     | [57a4116288](https://linux-hardware.org/?probe=57a4116288) | Jul 17, 2021 |
| ASUSTek       | X450EA                      | Notebook    | [91a0ff32e1](https://linux-hardware.org/?probe=91a0ff32e1) | Jul 06, 2021 |
| ASUSTek       | X450EA                      | Notebook    | [e4dc18ebf9](https://linux-hardware.org/?probe=e4dc18ebf9) | Jul 06, 2021 |
| Dell          | Precision M6400             | Notebook    | [7f2245c976](https://linux-hardware.org/?probe=7f2245c976) | Jun 24, 2021 |
| ASUSTek       | Q524UQ                      | Notebook    | [33d61b2077](https://linux-hardware.org/?probe=33d61b2077) | Jun 17, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [2a633bc008](https://linux-hardware.org/?probe=2a633bc008) | Jun 14, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [e3bb48a049](https://linux-hardware.org/?probe=e3bb48a049) | Jun 14, 2021 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [fa4061e79f](https://linux-hardware.org/?probe=fa4061e79f) | Jun 09, 2021 |
| Gateway       | MP8708                      | Notebook    | [ba382202c2](https://linux-hardware.org/?probe=ba382202c2) | Jun 04, 2021 |
| HP            | ZBook 15 G5                 | Notebook    | [462531aabd](https://linux-hardware.org/?probe=462531aabd) | Jun 03, 2021 |
| ASUSTek       | Q524UQ                      | Notebook    | [b510297404](https://linux-hardware.org/?probe=b510297404) | Jun 03, 2021 |
| Dell          | Inspiron 5558               | Notebook    | [91fdca7228](https://linux-hardware.org/?probe=91fdca7228) | May 31, 2021 |
| HP            | 1850                        | Desktop     | [3bde7e8e11](https://linux-hardware.org/?probe=3bde7e8e11) | May 27, 2021 |
| MSI           | GE73 Raider RGB 8RE         | Notebook    | [5aedb75ad8](https://linux-hardware.org/?probe=5aedb75ad8) | May 21, 2021 |
| Fujitsu       | LIFEBOOK T731               | Notebook    | [1cb3267b57](https://linux-hardware.org/?probe=1cb3267b57) | May 21, 2021 |
| Dell          | Inspiron 5420               | Notebook    | [dc6bc48c4d](https://linux-hardware.org/?probe=dc6bc48c4d) | May 18, 2021 |
| Lenovo        | ThinkPad X260 20F5S5QT00    | Notebook    | [a84514b117](https://linux-hardware.org/?probe=a84514b117) | May 14, 2021 |
| Intel         | NUC8i7HVB J68196-601        | Mini pc     | [d186af4ee3](https://linux-hardware.org/?probe=d186af4ee3) | May 14, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [aa4c3ffed1](https://linux-hardware.org/?probe=aa4c3ffed1) | May 13, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [605367d5d4](https://linux-hardware.org/?probe=605367d5d4) | May 13, 2021 |
| HP            | Pavilion dv4                | Notebook    | [250773011b](https://linux-hardware.org/?probe=250773011b) | May 07, 2021 |
| Dell          | 0C1R19 A02                  | Desktop     | [ff5bb2ee2a](https://linux-hardware.org/?probe=ff5bb2ee2a) | May 03, 2021 |
| HP            | HDX PREMIUM SERIES          | Notebook    | [47374d1b5f](https://linux-hardware.org/?probe=47374d1b5f) | Apr 27, 2021 |
| HP            | HDX PREMIUM SERIES          | Notebook    | [58b0d9473e](https://linux-hardware.org/?probe=58b0d9473e) | Apr 27, 2021 |
| HP            | 8430 1000                   | All in one  | [5c5adcc248](https://linux-hardware.org/?probe=5c5adcc248) | Apr 24, 2021 |
| ASUSTek       | PRIME X399-A                | Desktop     | [4dd4f28ca7](https://linux-hardware.org/?probe=4dd4f28ca7) | Apr 11, 2021 |
| Acer          | Aspire E1-571G              | Notebook    | [ee1ba6ee04](https://linux-hardware.org/?probe=ee1ba6ee04) | Apr 01, 2021 |
| PC Special... | N150CU                      | Notebook    | [39136d47f7](https://linux-hardware.org/?probe=39136d47f7) | Apr 01, 2021 |
| MSI           | GE75 Raider 10SF            | Notebook    | [d15c48b6a1](https://linux-hardware.org/?probe=d15c48b6a1) | Mar 29, 2021 |
| Acer          | Predator PO3-600 V:1.1      | Desktop     | [6ea75bdbb5](https://linux-hardware.org/?probe=6ea75bdbb5) | Mar 26, 2021 |
| Dell          | Inspiron 5420               | Notebook    | [78663f1468](https://linux-hardware.org/?probe=78663f1468) | Mar 25, 2021 |
| MSI           | GE63 Raider RGB 8RE         | Notebook    | [de917105cd](https://linux-hardware.org/?probe=de917105cd) | Mar 22, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [01ab712b94](https://linux-hardware.org/?probe=01ab712b94) | Mar 22, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [67ed2b4e7f](https://linux-hardware.org/?probe=67ed2b4e7f) | Mar 22, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [acda849408](https://linux-hardware.org/?probe=acda849408) | Mar 22, 2021 |
| Wortmann      | TERRA_MOBILE_1542           | Notebook    | [76f7963d8a](https://linux-hardware.org/?probe=76f7963d8a) | Mar 21, 2021 |
| Wortmann      | TERRA_MOBILE_1542           | Notebook    | [12fb4cc711](https://linux-hardware.org/?probe=12fb4cc711) | Mar 21, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [6b26a69326](https://linux-hardware.org/?probe=6b26a69326) | Mar 21, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [a4bf4bb64c](https://linux-hardware.org/?probe=a4bf4bb64c) | Mar 17, 2021 |
| HP            | Pavilion dv6                | Notebook    | [06b3024017](https://linux-hardware.org/?probe=06b3024017) | Mar 14, 2021 |
| Dell          | Inspiron 5420               | Notebook    | [11a466e06d](https://linux-hardware.org/?probe=11a466e06d) | Mar 05, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [89174dda21](https://linux-hardware.org/?probe=89174dda21) | Feb 27, 2021 |
| Dell          | Inspiron 5420               | Notebook    | [489ed0f996](https://linux-hardware.org/?probe=489ed0f996) | Feb 26, 2021 |
| Dell          | Inspiron 5420               | Notebook    | [a357eb71e0](https://linux-hardware.org/?probe=a357eb71e0) | Feb 22, 2021 |
| HP            | 339A                        | Desktop     | [b105e94284](https://linux-hardware.org/?probe=b105e94284) | Feb 20, 2021 |
| HP            | 339A                        | Desktop     | [3dfdd6aa5e](https://linux-hardware.org/?probe=3dfdd6aa5e) | Feb 20, 2021 |
| Lenovo        | IdeaPad 110-14ISK 80UC      | Notebook    | [2cf1bfd6c6](https://linux-hardware.org/?probe=2cf1bfd6c6) | Feb 16, 2021 |
| HP            | Laptop 15-db0xxx            | Notebook    | [c337c59497](https://linux-hardware.org/?probe=c337c59497) | Feb 13, 2021 |
| HP            | ProBook 450 G1              | Notebook    | [284fd25f3e](https://linux-hardware.org/?probe=284fd25f3e) | Feb 11, 2021 |
| MSI           | B250M MORTAR                | Desktop     | [be8a65f362](https://linux-hardware.org/?probe=be8a65f362) | Feb 02, 2021 |
| Dell          | 0CU409                      | Desktop     | [64c8a84081](https://linux-hardware.org/?probe=64c8a84081) | Jan 29, 2021 |
| HP            | ENVY 15                     | Notebook    | [c39474b63f](https://linux-hardware.org/?probe=c39474b63f) | Jan 23, 2021 |
| Positivo B... | VJFE51F11X-B0111H           | Notebook    | [ea1a80dc34](https://linux-hardware.org/?probe=ea1a80dc34) | Jan 21, 2021 |
| Positivo B... | VJFE51F11X-B0111H           | Notebook    | [80dc10f323](https://linux-hardware.org/?probe=80dc10f323) | Jan 21, 2021 |
| Acer          | Aspire X3990                | Desktop     | [a3e9301c7f](https://linux-hardware.org/?probe=a3e9301c7f) | Jan 16, 2021 |
| Acer          | Aspire X3990                | Desktop     | [1660d13b44](https://linux-hardware.org/?probe=1660d13b44) | Jan 12, 2021 |
| HP            | 3047h                       | Desktop     | [8b50e12296](https://linux-hardware.org/?probe=8b50e12296) | Jan 07, 2021 |
| Dell          | Latitude 7390               | Notebook    | [0ef9ffc535](https://linux-hardware.org/?probe=0ef9ffc535) | Dec 27, 2020 |
| Medion        | MS-7621                     | Desktop     | [74c49730d1](https://linux-hardware.org/?probe=74c49730d1) | Dec 27, 2020 |
| Positivo      | POS-PIG43BC                 | Desktop     | [146c7d86bb](https://linux-hardware.org/?probe=146c7d86bb) | Dec 27, 2020 |
| ASUSTek       | X555LAB                     | Notebook    | [ab17ca4eef](https://linux-hardware.org/?probe=ab17ca4eef) | Dec 25, 2020 |
| Lenovo        | ThinkPad T490 20N2S04000    | Notebook    | [4f02aacb6d](https://linux-hardware.org/?probe=4f02aacb6d) | Dec 21, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [33960a08de](https://linux-hardware.org/?probe=33960a08de) | Dec 20, 2020 |
| Toshiba       | Satellite L750              | Notebook    | [748a6b0b09](https://linux-hardware.org/?probe=748a6b0b09) | Dec 16, 2020 |
| Dell          | Latitude E5440              | Notebook    | [7befb8e28b](https://linux-hardware.org/?probe=7befb8e28b) | Nov 29, 2020 |
| Dell          | Latitude E5440              | Notebook    | [3064211887](https://linux-hardware.org/?probe=3064211887) | Nov 28, 2020 |
| Lenovo        | ThinkPad X220 42912XG       | Notebook    | [ce89f09531](https://linux-hardware.org/?probe=ce89f09531) | Nov 26, 2020 |
| HP            | 3047h                       | Desktop     | [b65caab721](https://linux-hardware.org/?probe=b65caab721) | Nov 24, 2020 |
| Acer          | Aspire 5250                 | Notebook    | [11f670b6b1](https://linux-hardware.org/?probe=11f670b6b1) | Nov 23, 2020 |
| HP            | Compaq Presario C700        | Notebook    | [82be91a50a](https://linux-hardware.org/?probe=82be91a50a) | Nov 20, 2020 |
| HP            | Compaq Presario C700        | Notebook    | [f86087eece](https://linux-hardware.org/?probe=f86087eece) | Nov 20, 2020 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [458ab52080](https://linux-hardware.org/?probe=458ab52080) | Nov 17, 2020 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [6608936515](https://linux-hardware.org/?probe=6608936515) | Nov 10, 2020 |
| Foxconn       | 45CMX/45GMX/45CMX-K         | Desktop     | [7918687a8b](https://linux-hardware.org/?probe=7918687a8b) | Nov 07, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [c110de3643](https://linux-hardware.org/?probe=c110de3643) | Oct 31, 2020 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [f95c24897c](https://linux-hardware.org/?probe=f95c24897c) | Oct 30, 2020 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [f7a2b660d8](https://linux-hardware.org/?probe=f7a2b660d8) | Oct 29, 2020 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [c687805b04](https://linux-hardware.org/?probe=c687805b04) | Oct 29, 2020 |
| ASUSTek       | X540YA                      | Notebook    | [501ca10eeb](https://linux-hardware.org/?probe=501ca10eeb) | Oct 25, 2020 |
| ECS           | A740GM-M                    | Desktop     | [423f49affd](https://linux-hardware.org/?probe=423f49affd) | Oct 25, 2020 |
| Dell          | Vostro 3558                 | Notebook    | [8f4f321359](https://linux-hardware.org/?probe=8f4f321359) | Oct 18, 2020 |
| ASUSTek       | TUF Gaming FX705GD          | Notebook    | [8ce3caa35a](https://linux-hardware.org/?probe=8ce3caa35a) | Oct 15, 2020 |
| ASUSTek       | TUF Gaming FX705GD          | Notebook    | [b2d5b6eb69](https://linux-hardware.org/?probe=b2d5b6eb69) | Oct 15, 2020 |
| Lenovo        | ThinkPad T420s 4174W2P      | Notebook    | [c8eacff838](https://linux-hardware.org/?probe=c8eacff838) | Oct 10, 2020 |
| HP            | Pavilion 17                 | Notebook    | [2a0d11caf1](https://linux-hardware.org/?probe=2a0d11caf1) | Oct 09, 2020 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | Notebook    | [f06ac6483c](https://linux-hardware.org/?probe=f06ac6483c) | Oct 06, 2020 |
| Razer         | Blade Stealth               | Notebook    | [564265e066](https://linux-hardware.org/?probe=564265e066) | Oct 01, 2020 |
| Acer          | Predator PH317-53           | Notebook    | [16cddb4fce](https://linux-hardware.org/?probe=16cddb4fce) | Sep 29, 2020 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [2bc8fbe372](https://linux-hardware.org/?probe=2bc8fbe372) | Sep 27, 2020 |
| Toshiba       | Satellite L750              | Notebook    | [74a0ca3614](https://linux-hardware.org/?probe=74a0ca3614) | Sep 25, 2020 |
| HP            | EliteBook Folio 9480m       | Notebook    | [bb1615dd63](https://linux-hardware.org/?probe=bb1615dd63) | Sep 24, 2020 |
| System76      | Gazelle                     | Notebook    | [d96d5e60ae](https://linux-hardware.org/?probe=d96d5e60ae) | Sep 20, 2020 |
| Lenovo        | IdeaPadFlex 4-1470 80SA     | Convertible | [4ad16b3038](https://linux-hardware.org/?probe=4ad16b3038) | Sep 20, 2020 |
| Alienware     | 17 R4                       | Notebook    | [d58b082d72](https://linux-hardware.org/?probe=d58b082d72) | Sep 19, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d77bb0aa31](https://linux-hardware.org/?probe=d77bb0aa31) | Sep 18, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [951e2d1aa6](https://linux-hardware.org/?probe=951e2d1aa6) | Sep 18, 2020 |
| Lenovo        | IdeaPadFlex 4-1470 80SA     | Convertible | [f88025bc71](https://linux-hardware.org/?probe=f88025bc71) | Sep 16, 2020 |
| Dell          | Latitude 3400               | Notebook    | [f7d1872e51](https://linux-hardware.org/?probe=f7d1872e51) | Sep 13, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [090d50eec1](https://linux-hardware.org/?probe=090d50eec1) | Sep 12, 2020 |
| Lenovo        | E41-25 81FS                 | Notebook    | [1e512df642](https://linux-hardware.org/?probe=1e512df642) | Sep 12, 2020 |
| Toshiba       | Satellite L750              | Notebook    | [091facc59a](https://linux-hardware.org/?probe=091facc59a) | Sep 12, 2020 |
| Dell          | Latitude 3400               | Notebook    | [825d226ad5](https://linux-hardware.org/?probe=825d226ad5) | Sep 10, 2020 |
| Apple         | MacBookPro8,1               | Notebook    | [fc23c05e20](https://linux-hardware.org/?probe=fc23c05e20) | Sep 04, 2020 |
| Lenovo        | ThinkPad X240 20AMS4MH00    | Notebook    | [3e6177e73c](https://linux-hardware.org/?probe=3e6177e73c) | Sep 01, 2020 |
| Gigabyte      | H370M DS3H-CF               | Desktop     | [affb4f7587](https://linux-hardware.org/?probe=affb4f7587) | Aug 29, 2020 |
| Lenovo        | IdeaPadFlex 4-1470 80SA     | Convertible | [c87fcab7c7](https://linux-hardware.org/?probe=c87fcab7c7) | Aug 26, 2020 |
| Lenovo        | IdeaPadFlex 4-1470 80SA     | Convertible | [608ad8477d](https://linux-hardware.org/?probe=608ad8477d) | Aug 22, 2020 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [dbf4ca0908](https://linux-hardware.org/?probe=dbf4ca0908) | Aug 10, 2020 |
| Sony          | VPCCB15FG                   | Notebook    | [4d93dfd9c0](https://linux-hardware.org/?probe=4d93dfd9c0) | Aug 09, 2020 |
| Dell          | System Inspiron N7110       | Notebook    | [c4ba9dc0dc](https://linux-hardware.org/?probe=c4ba9dc0dc) | Aug 05, 2020 |
| HP            | Notebook                    | Notebook    | [989b6b7d5d](https://linux-hardware.org/?probe=989b6b7d5d) | Aug 04, 2020 |
| Acer          | Aspire ES1-111M             | Notebook    | [359a7266e5](https://linux-hardware.org/?probe=359a7266e5) | Aug 03, 2020 |
| Lenovo        | G480 20149                  | Notebook    | [bfffb28472](https://linux-hardware.org/?probe=bfffb28472) | Jul 27, 2020 |
| Lenovo        | G480 20149                  | Notebook    | [53b70e68df](https://linux-hardware.org/?probe=53b70e68df) | Jul 27, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [f032f63f3a](https://linux-hardware.org/?probe=f032f63f3a) | Jul 26, 2020 |
| HP            | Notebook                    | Notebook    | [ee51b68070](https://linux-hardware.org/?probe=ee51b68070) | Jul 23, 2020 |
| HP            | Notebook                    | Notebook    | [87cfa4c37e](https://linux-hardware.org/?probe=87cfa4c37e) | Jul 23, 2020 |
| Dell          | System Inspiron N7110       | Notebook    | [3177a50194](https://linux-hardware.org/?probe=3177a50194) | Jul 22, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [f77f8a2639](https://linux-hardware.org/?probe=f77f8a2639) | Jul 15, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [4afe4f5961](https://linux-hardware.org/?probe=4afe4f5961) | Jul 15, 2020 |
| Acer          | Aspire V5-122P              | Notebook    | [a362dee702](https://linux-hardware.org/?probe=a362dee702) | Jul 10, 2020 |
| Dell          | Latitude 7480               | Notebook    | [aab5a5b50a](https://linux-hardware.org/?probe=aab5a5b50a) | Jul 07, 2020 |
| eMachines     | eME728                      | Notebook    | [3f409bf927](https://linux-hardware.org/?probe=3f409bf927) | Jul 05, 2020 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [3c48dbb383](https://linux-hardware.org/?probe=3c48dbb383) | Jul 05, 2020 |
| Apple         | Mac-F221BEC8                | Desktop     | [1d8d1db67e](https://linux-hardware.org/?probe=1d8d1db67e) | Jul 04, 2020 |
| Dell          | 0D6H9T A00                  | Desktop     | [06e9599063](https://linux-hardware.org/?probe=06e9599063) | Jul 04, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [dda8536e62](https://linux-hardware.org/?probe=dda8536e62) | Jun 11, 2020 |
| Dell          | G7 7790                     | Notebook    | [506d29b806](https://linux-hardware.org/?probe=506d29b806) | Jun 02, 2020 |
| Dell          | G7 7790                     | Notebook    | [0551762cbb](https://linux-hardware.org/?probe=0551762cbb) | Jun 02, 2020 |
| Biostar       | H77MU3                      | Desktop     | [048ffba01b](https://linux-hardware.org/?probe=048ffba01b) | May 24, 2020 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [7c05b67968](https://linux-hardware.org/?probe=7c05b67968) | May 22, 2020 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [fc8bf8a5a6](https://linux-hardware.org/?probe=fc8bf8a5a6) | May 22, 2020 |
| Google        | Celes                       | Notebook    | [d417dd63dd](https://linux-hardware.org/?probe=d417dd63dd) | May 22, 2020 |
| Google        | Celes                       | Notebook    | [88d722fa1b](https://linux-hardware.org/?probe=88d722fa1b) | May 22, 2020 |
| ASUSTek       | X75VB                       | Notebook    | [f41d9b003f](https://linux-hardware.org/?probe=f41d9b003f) | May 22, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [8e55010bac](https://linux-hardware.org/?probe=8e55010bac) | May 22, 2020 |
| Fujitsu       | LIFEBOOK A532               | Notebook    | [96ec25db7c](https://linux-hardware.org/?probe=96ec25db7c) | May 21, 2020 |
| Fujitsu       | LIFEBOOK A532               | Notebook    | [b2ecb833ba](https://linux-hardware.org/?probe=b2ecb833ba) | May 21, 2020 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [26293feb91](https://linux-hardware.org/?probe=26293feb91) | May 21, 2020 |
| Dell          | Inspiron MM061              | Notebook    | [a6bb0bfd0b](https://linux-hardware.org/?probe=a6bb0bfd0b) | May 21, 2020 |
| Dell          | 0VYXHD A00                  | Desktop     | [5e5d0a24f3](https://linux-hardware.org/?probe=5e5d0a24f3) | May 15, 2020 |
| ASUSTek       | N56VZ                       | Notebook    | [69ee412460](https://linux-hardware.org/?probe=69ee412460) | May 14, 2020 |
| Dell          | Inspiron MM061              | Notebook    | [0d48c76bfd](https://linux-hardware.org/?probe=0d48c76bfd) | May 11, 2020 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [d64b4a56e0](https://linux-hardware.org/?probe=d64b4a56e0) | May 08, 2020 |
| Dell          | 0VYXHD A00                  | Desktop     | [5a56c30293](https://linux-hardware.org/?probe=5a56c30293) | May 06, 2020 |
| ASUSTek       | X442URR                     | Notebook    | [7595f05acd](https://linux-hardware.org/?probe=7595f05acd) | May 04, 2020 |
| HP            | ProBook 6475b               | Notebook    | [c9ee4e6614](https://linux-hardware.org/?probe=c9ee4e6614) | May 03, 2020 |
| HP            | ProBook 6475b               | Notebook    | [06da2207cd](https://linux-hardware.org/?probe=06da2207cd) | May 02, 2020 |
| HP            | ProBook 6475b               | Notebook    | [b2ff4072ce](https://linux-hardware.org/?probe=b2ff4072ce) | May 02, 2020 |
| Toshiba       | Satellite L300D             | Notebook    | [5a320c4b78](https://linux-hardware.org/?probe=5a320c4b78) | May 02, 2020 |
| Dell          | 05DN3X A00                  | Desktop     | [7424c0caba](https://linux-hardware.org/?probe=7424c0caba) | May 02, 2020 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [3dc6534b5f](https://linux-hardware.org/?probe=3dc6534b5f) | May 01, 2020 |
| Dell          | Latitude E6420              | Notebook    | [ae3ade27d7](https://linux-hardware.org/?probe=ae3ade27d7) | Apr 29, 2020 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [6835f4fe95](https://linux-hardware.org/?probe=6835f4fe95) | Apr 28, 2020 |
| Dell          | Latitude E6420              | Notebook    | [83380135bc](https://linux-hardware.org/?probe=83380135bc) | Apr 27, 2020 |
| Dell          | Latitude E6420              | Notebook    | [12c77f16d5](https://linux-hardware.org/?probe=12c77f16d5) | Apr 27, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [6e636c5fd2](https://linux-hardware.org/?probe=6e636c5fd2) | Apr 27, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [d19700bc2d](https://linux-hardware.org/?probe=d19700bc2d) | Apr 27, 2020 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [72dcfa02ca](https://linux-hardware.org/?probe=72dcfa02ca) | Apr 26, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [37c314650f](https://linux-hardware.org/?probe=37c314650f) | Apr 26, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [9a9b368a7c](https://linux-hardware.org/?probe=9a9b368a7c) | Apr 26, 2020 |
| Dell          | XPS 12-9Q33                 | Notebook    | [f831495ef5](https://linux-hardware.org/?probe=f831495ef5) | Apr 25, 2020 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | Notebook    | [6bf9d537a8](https://linux-hardware.org/?probe=6bf9d537a8) | Apr 21, 2020 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [2dec0ef690](https://linux-hardware.org/?probe=2dec0ef690) | Apr 18, 2020 |
| HP            | Pavilion g6                 | Notebook    | [c54d518ca7](https://linux-hardware.org/?probe=c54d518ca7) | Apr 15, 2020 |
| ASUSTek       | K31CD-K                     | Desktop     | [b4ad316fa2](https://linux-hardware.org/?probe=b4ad316fa2) | Apr 14, 2020 |
| Dell          | 0CU409                      | Desktop     | [661761d2ca](https://linux-hardware.org/?probe=661761d2ca) | Apr 14, 2020 |
| Acer          | Aspire 5250                 | Notebook    | [100d4bacdc](https://linux-hardware.org/?probe=100d4bacdc) | Apr 14, 2020 |
| Dell          | 0CU409                      | Desktop     | [5512733c4a](https://linux-hardware.org/?probe=5512733c4a) | Apr 14, 2020 |
| Gigabyte      | GA-880GM-D2H                | Desktop     | [93da68c7fb](https://linux-hardware.org/?probe=93da68c7fb) | Apr 12, 2020 |
| Dell          | Inspiron 5721               | Notebook    | [23d5dff3bd](https://linux-hardware.org/?probe=23d5dff3bd) | Apr 11, 2020 |
| Dell          | Inspiron 3458               | Notebook    | [d9c91be81b](https://linux-hardware.org/?probe=d9c91be81b) | Apr 06, 2020 |
| Dell          | Inspiron 3458               | Notebook    | [a10080482e](https://linux-hardware.org/?probe=a10080482e) | Apr 05, 2020 |
| Dell          | Inspiron 3458               | Notebook    | [cfb5a6d57c](https://linux-hardware.org/?probe=cfb5a6d57c) | Apr 05, 2020 |
| ASUSTek       | N56VZ                       | Notebook    | [249176d47f](https://linux-hardware.org/?probe=249176d47f) | Apr 01, 2020 |
| Samsung       | RV415/RV515                 | Notebook    | [3b9248b95f](https://linux-hardware.org/?probe=3b9248b95f) | Mar 31, 2020 |
| ASUSTek       | T101HA                      | Tablet      | [224ebfd9b3](https://linux-hardware.org/?probe=224ebfd9b3) | Mar 30, 2020 |
| ASUSTek       | T101HA                      | Tablet      | [79e98a64cf](https://linux-hardware.org/?probe=79e98a64cf) | Mar 30, 2020 |
| Lenovo        | ThinkPad T440s 20ARS01C0... | Notebook    | [aa9f421079](https://linux-hardware.org/?probe=aa9f421079) | Mar 23, 2020 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [cf7e8cd869](https://linux-hardware.org/?probe=cf7e8cd869) | Mar 16, 2020 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [05f8c8eef4](https://linux-hardware.org/?probe=05f8c8eef4) | Feb 29, 2020 |
| HP            | Laptop 17-by0xxx            | Notebook    | [21c7ac4323](https://linux-hardware.org/?probe=21c7ac4323) | Feb 17, 2020 |
| Lenovo        | ThinkPad E14 20RA0016GE     | Notebook    | [dd543cf29b](https://linux-hardware.org/?probe=dd543cf29b) | Feb 09, 2020 |
| Gigabyte      | AX370-Gaming-CF se1         | Desktop     | [2bfc7eae61](https://linux-hardware.org/?probe=2bfc7eae61) | Feb 06, 2020 |
| Gigabyte      | AX370-Gaming-CF se1         | Desktop     | [1e8ccbe5b9](https://linux-hardware.org/?probe=1e8ccbe5b9) | Feb 04, 2020 |
| Notebook      | W510TU                      | Notebook    | [987d9232fe](https://linux-hardware.org/?probe=987d9232fe) | Jan 31, 2020 |
| Notebook      | W510TU                      | Notebook    | [4556eb747b](https://linux-hardware.org/?probe=4556eb747b) | Jan 31, 2020 |
| HP            | EliteBook 8460p             | Notebook    | [8b7c621317](https://linux-hardware.org/?probe=8b7c621317) | Jan 26, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [38658290e2](https://linux-hardware.org/?probe=38658290e2) | Jan 19, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [05e5552eea](https://linux-hardware.org/?probe=05e5552eea) | Jan 19, 2020 |
| HUAWEI        | WRT-WX9                     | Notebook    | [375040e90b](https://linux-hardware.org/?probe=375040e90b) | Jan 05, 2020 |
| Notebook      | W510TU                      | Notebook    | [aa2e59fd60](https://linux-hardware.org/?probe=aa2e59fd60) | Dec 25, 2019 |
| Apple         | MacBookAir7,2               | Notebook    | [1a26d7b485](https://linux-hardware.org/?probe=1a26d7b485) | Dec 21, 2019 |
| Notebook      | W510TU                      | Notebook    | [f2102dfe5b](https://linux-hardware.org/?probe=f2102dfe5b) | Dec 09, 2019 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [51389e5c4a](https://linux-hardware.org/?probe=51389e5c4a) | Dec 07, 2019 |
| Apple         | MacBookAir7,2               | Notebook    | [73a28279bc](https://linux-hardware.org/?probe=73a28279bc) | Dec 05, 2019 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [7bc298d7af](https://linux-hardware.org/?probe=7bc298d7af) | Nov 10, 2019 |
| HP            | 630                         | Notebook    | [687ccfe3b1](https://linux-hardware.org/?probe=687ccfe3b1) | Sep 28, 2019 |
| Acer          | Aspire E5-475               | Notebook    | [3e3fad10fe](https://linux-hardware.org/?probe=3e3fad10fe) | Aug 18, 2019 |
| Gateway       | NE-522                      | Notebook    | [d562b598e5](https://linux-hardware.org/?probe=d562b598e5) | Aug 10, 2019 |
| Lenovo        | Y50-70 Touch 20349          | Notebook    | [c0c73d01ba](https://linux-hardware.org/?probe=c0c73d01ba) | Jun 08, 2019 |
| Apple         | MacBookPro11,4              | Notebook    | [49a28f87b9](https://linux-hardware.org/?probe=49a28f87b9) | May 21, 2019 |
| Acer          | Swift SF314-54              | Notebook    | [89013e65ec](https://linux-hardware.org/?probe=89013e65ec) | Apr 26, 2019 |
| ASUSTek       | X510UQ                      | Notebook    | [74e81c78ab](https://linux-hardware.org/?probe=74e81c78ab) | Feb 16, 2019 |
| ASUSTek       | X510UQ                      | Notebook    | [50fc8650ad](https://linux-hardware.org/?probe=50fc8650ad) | Feb 16, 2019 |
| Dell          | Latitude E7440              | Notebook    | [ce392df9c0](https://linux-hardware.org/?probe=ce392df9c0) | Dec 26, 2018 |
| HP            | Pavilion 15                 | Notebook    | [921bec751d](https://linux-hardware.org/?probe=921bec751d) | Oct 13, 2018 |
| Digma         | CITI E401 ET4007EW          | Notebook    | [597e65c2a4](https://linux-hardware.org/?probe=597e65c2a4) | Jan 07, 2018 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Parrot 5.0   | 82        | 28.57%  |
| Parrot 4.11  | 82        | 28.57%  |
| Parrot 4.10  | 59        | 20.56%  |
| Parrot 4.8   | 23        | 8.01%   |
| Parrot 4.9   | 22        | 7.67%   |
| Parrot 4.7   | 13        | 4.53%   |
| Parrot 4.6   | 2         | 0.7%    |
| Parrot 4.5   | 1         | 0.35%   |
| Parrot 4.4   | 1         | 0.35%   |
| Parrot 4.2.2 | 1         | 0.35%   |
| Parrot 3.10  | 1         | 0.35%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Parrot | 272       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.14.0-9parrot1-amd64    | 50        | 17.01%  |
| 5.16.0-12parrot1-amd64   | 35        | 11.9%   |
| 5.7.0-2parrot2-amd64     | 33        | 11.22%  |
| 5.10.0-6parrot1-amd64    | 30        | 10.2%   |
| 5.5.0-1parrot1-amd64     | 24        | 8.16%   |
| 5.10.0-8parrot1-amd64    | 17        | 5.78%   |
| 5.4.0-4parrot1-amd64     | 16        | 5.44%   |
| 5.15.0-15parrot1-amd64   | 11        | 3.74%   |
| 5.6.0-2parrot1-amd64     | 10        | 3.4%    |
| 5.14.0-2parrot1-amd64    | 10        | 3.4%    |
| 5.9.0-2parrot1-amd64     | 9         | 3.06%   |
| 5.8.0-2parrot1-amd64     | 5         | 1.7%    |
| 5.4.0-2parrot1-amd64     | 5         | 1.7%    |
| 5.10.0-3parrot1-amd64    | 5         | 1.7%    |
| 5.8.0-1parrot1-amd64     | 4         | 1.36%   |
| 5.10.0-5parrot1-amd64    | 4         | 1.36%   |
| 5.4.0-3parrot1-amd64     | 3         | 1.02%   |
| 5.3.0-3parrot3-amd64     | 3         | 1.02%   |
| 5.2.0-2parrot1-amd64     | 3         | 1.02%   |
| 4.19.0-parrot4-28t-amd64 | 3         | 1.02%   |
| 4.18.0-parrot10-amd64    | 2         | 0.68%   |
| 5.7.0-rc6-galliumos      | 1         | 0.34%   |
| 5.4.0-2parrot1-686-pae   | 1         | 0.34%   |
| 5.4.0-1parrot1-amd64     | 1         | 0.34%   |
| 5.3.0-3parrot3-686-pae   | 1         | 0.34%   |
| 5.3.0-1parrot1-amd64     | 1         | 0.34%   |
| 5.15.0-5parrot1-amd64    | 1         | 0.34%   |
| 5.10.0-kali6-amd64       | 1         | 0.34%   |
| 5.10.0-6parrot1-rt-amd64 | 1         | 0.34%   |
| 5.1.0-parrot1-3t-amd64   | 1         | 0.34%   |
| 4.19.0-parrot1-13t-amd64 | 1         | 0.34%   |
| 4.14.0-parrot7-amd64     | 1         | 0.34%   |
| Unknown                  | 1         | 0.34%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14.0  | 58        | 19.86%  |
| 5.10.0  | 58        | 19.86%  |
| 5.16.0  | 35        | 11.99%  |
| 5.7.0   | 34        | 11.64%  |
| 5.4.0   | 26        | 8.9%    |
| 5.5.0   | 24        | 8.22%   |
| 5.15.0  | 12        | 4.11%   |
| 5.6.0   | 10        | 3.42%   |
| 5.9.0   | 9         | 3.08%   |
| 5.8.0   | 9         | 3.08%   |
| 5.3.0   | 5         | 1.71%   |
| 4.19.0  | 4         | 1.37%   |
| 5.2.0   | 3         | 1.03%   |
| 4.18.0  | 2         | 0.68%   |
| 5.1.0   | 1         | 0.34%   |
| 4.14.0  | 1         | 0.34%   |
| Unknown | 1         | 0.34%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14    | 58        | 19.86%  |
| 5.10    | 58        | 19.86%  |
| 5.16    | 35        | 11.99%  |
| 5.7     | 34        | 11.64%  |
| 5.4     | 26        | 8.9%    |
| 5.5     | 24        | 8.22%   |
| 5.15    | 12        | 4.11%   |
| 5.6     | 10        | 3.42%   |
| 5.9     | 9         | 3.08%   |
| 5.8     | 9         | 3.08%   |
| 5.3     | 5         | 1.71%   |
| 4.19    | 4         | 1.37%   |
| 5.2     | 3         | 1.03%   |
| 4.18    | 2         | 0.68%   |
| 5.1     | 1         | 0.34%   |
| 4.14    | 1         | 0.34%   |
| Unknown | 1         | 0.34%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 271       | 99.63%  |
| i686   | 1         | 0.37%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| MATE          | 172       | 61.87%  |
| KDE5          | 54        | 19.42%  |
| KDE           | 20        | 7.19%   |
| Unknown       | 19        | 6.83%   |
| XFCE          | 8         | 2.88%   |
| GNOME         | 2         | 0.72%   |
| LXDE          | 1         | 0.36%   |
| GNOME Classic | 1         | 0.36%   |
| Cinnamon      | 1         | 0.36%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 268       | 98.53%  |
| Wayland | 3         | 1.1%    |
| Unknown | 1         | 0.37%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 103       | 36.79%  |
| LightDM | 94        | 33.57%  |
| TDM     | 71        | 25.36%  |
| GDM     | 7         | 2.5%    |
| SDDM    | 5         | 1.79%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 139       | 50.92%  |
| en_GB   | 20        | 7.33%   |
| fr_FR   | 14        | 5.13%   |
| Unknown | 14        | 5.13%   |
| ru_RU   | 11        | 4.03%   |
| es_ES   | 9         | 3.3%    |
| de_DE   | 9         | 3.3%    |
| pt_BR   | 7         | 2.56%   |
| pl_PL   | 7         | 2.56%   |
| en_IN   | 7         | 2.56%   |
| en_AU   | 7         | 2.56%   |
| it_IT   | 3         | 1.1%    |
| cs_CZ   | 3         | 1.1%    |
| es_MX   | 2         | 0.73%   |
| en_HK   | 2         | 0.73%   |
| en_DK   | 2         | 0.73%   |
| tr_TR   | 1         | 0.37%   |
| ru_UA   | 1         | 0.37%   |
| pt_PT   | 1         | 0.37%   |
| nl_BE   | 1         | 0.37%   |
| mk_MK   | 1         | 0.37%   |
| id_ID   | 1         | 0.37%   |
| fr_CA   | 1         | 0.37%   |
| es_PE   | 1         | 0.37%   |
| es_CO   | 1         | 0.37%   |
| es_CL   | 1         | 0.37%   |
| en_ZA   | 1         | 0.37%   |
| en_NZ   | 1         | 0.37%   |
| en_NG   | 1         | 0.37%   |
| en_CA   | 1         | 0.37%   |
| de_AT   | 1         | 0.37%   |
| C       | 1         | 0.37%   |
| an_ES   | 1         | 0.37%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 182       | 65.94%  |
| EFI  | 94        | 34.06%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 201       | 72.56%  |
| Ext4    | 51        | 18.41%  |
| Xfs     | 10        | 3.61%   |
| Overlay | 8         | 2.89%   |
| Unknown | 7         | 2.53%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 129       | 46.57%  |
| GPT     | 97        | 35.02%  |
| MBR     | 51        | 18.41%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 237       | 85.87%  |
| Yes       | 39        | 14.13%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 180       | 65.93%  |
| Yes       | 93        | 34.07%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 48        | 17.65%  |
| Dell                  | 43        | 15.81%  |
| ASUSTek Computer      | 39        | 14.34%  |
| Lenovo                | 38        | 13.97%  |
| Acer                  | 16        | 5.88%   |
| MSI                   | 14        | 5.15%   |
| Apple                 | 9         | 3.31%   |
| Gigabyte Technology   | 7         | 2.57%   |
| Toshiba               | 6         | 2.21%   |
| Samsung Electronics   | 4         | 1.47%   |
| Microsoft             | 3         | 1.1%    |
| HUAWEI                | 3         | 1.1%    |
| Foxconn               | 3         | 1.1%    |
| ASRock                | 3         | 1.1%    |
| Alienware             | 3         | 1.1%    |
| Sony                  | 2         | 0.74%   |
| Razer                 | 2         | 0.74%   |
| Positivo              | 2         | 0.74%   |
| Gateway               | 2         | 0.74%   |
| Fujitsu               | 2         | 0.74%   |
| ECS                   | 2         | 0.74%   |
| ZOTAC                 | 1         | 0.37%   |
| Wortmann AG           | 1         | 0.37%   |
| Wistron               | 1         | 0.37%   |
| Toxic                 | 1         | 0.37%   |
| Timi                  | 1         | 0.37%   |
| System76              | 1         | 0.37%   |
| SLIMBOOK              | 1         | 0.37%   |
| Positivo Bahia - VAIO | 1         | 0.37%   |
| Notebook              | 1         | 0.37%   |
| Metabox               | 1         | 0.37%   |
| Jumper                | 1         | 0.37%   |
| Intel                 | 1         | 0.37%   |
| GPU Company           | 1         | 0.37%   |
| Google                | 1         | 0.37%   |
| eMachines             | 1         | 0.37%   |
| Eluktronics           | 1         | 0.37%   |
| Digma                 | 1         | 0.37%   |
| Daewoo Lucoms         | 1         | 0.37%   |
| Chuwi                 | 1         | 0.37%   |
| Biostar               | 1         | 0.37%   |
| Unknown               | 1         | 0.37%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                               | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| MSI Modern 15 A5M                                  | 3         | 1.1%    |
| HP Notebook                                        | 3         | 1.1%    |
| HP EliteBook 8470p                                 | 3         | 1.1%    |
| Microsoft Surface Pro 3                            | 2         | 0.74%   |
| Lenovo IdeaPad 3 15IIL05 81WE                      | 2         | 0.74%   |
| HP ProDesk 600 G1 SFF                              | 2         | 0.74%   |
| HP ProBook 650 G1                                  | 2         | 0.74%   |
| HP Pavilion 15                                     | 2         | 0.74%   |
| Gigabyte AX370-Gaming                              | 2         | 0.74%   |
| Foxconn s5710t                                     | 2         | 0.74%   |
| Dell Latitude E7440                                | 2         | 0.74%   |
| Dell Latitude E6420                                | 2         | 0.74%   |
| Dell Latitude E6410                                | 2         | 0.74%   |
| Dell Inspiron MM061                                | 2         | 0.74%   |
| Dell Inspiron 5676                                 | 2         | 0.74%   |
| ASUS Q524UQ                                        | 2         | 0.74%   |
| ASUS M5A78L-M/USB3                                 | 2         | 0.74%   |
| ASUS H110I-PLUS                                    | 2         | 0.74%   |
| ASUS Basic 3221BM                                  | 2         | 0.74%   |
| Apple MacBookPro8,1                                | 2         | 0.74%   |
| Acer Nitro AN515-54                                | 2         | 0.74%   |
| Unknown                                            | 2         | 0.74%   |
| Wortmann AG TERRA_MOBILE_1542                      | 1         | 0.37%   |
| Wistron FMVDD2A0H0                                 | 1         | 0.37%   |
| Toxic GM7MQ8P                                      | 1         | 0.37%   |
| Toshiba Satellite L775D                            | 1         | 0.37%   |
| Toshiba Satellite L750                             | 1         | 0.37%   |
| Toshiba Satellite L655                             | 1         | 0.37%   |
| Toshiba Satellite L300D                            | 1         | 0.37%   |
| Toshiba Satellite Click 2 L35W-B                   | 1         | 0.37%   |
| Toshiba Satellite C75D-B                           | 1         | 0.37%   |
| Timi TM1613                                        | 1         | 0.37%   |
| System76 Gazelle                                   | 1         | 0.37%   |
| Sony VPCCB15FG                                     | 1         | 0.37%   |
| Sony SVP1321L1EBI                                  | 1         | 0.37%   |
| SLIMBOOK ONE-AMD-M4                                | 1         | 0.37%   |
| Samsung RV415/RV515                                | 1         | 0.37%   |
| Samsung 550P5C/550P7C                              | 1         | 0.37%   |
| Samsung 350V5C/351V5C/3540VC/3440VC                | 1         | 0.37%   |
| Samsung 300E4C/300E5C/300E7C                       | 1         | 0.37%   |
| Razer Blade Stealth                                | 1         | 0.37%   |
| Razer Blade 15 Base Model (Early 2020) - RZ09-0328 | 1         | 0.37%   |
| Positivo Q232A                                     | 1         | 0.37%   |
| Positivo POS-PIG43BC                               | 1         | 0.37%   |
| Positivo Bahia - VAIO VJFE51F11X-B0111H            | 1         | 0.37%   |
| Notebook W510TU                                    | 1         | 0.37%   |
| MSI MS-7C02                                        | 1         | 0.37%   |
| MSI MS-7A69                                        | 1         | 0.37%   |
| MSI MS-7A34                                        | 1         | 0.37%   |
| MSI MS-7529                                        | 1         | 0.37%   |
| MSI GT60 2OC/2OD                                   | 1         | 0.37%   |
| MSI GS66 Stealth 10UG                              | 1         | 0.37%   |
| MSI GE75 Raider 10SF                               | 1         | 0.37%   |
| MSI GE73 Raider RGB 8RE                            | 1         | 0.37%   |
| MSI GE63 Raider RGB 8RE                            | 1         | 0.37%   |
| MSI GE62 6QE                                       | 1         | 0.37%   |
| MSI Creator Z16 Hiroshi F A11UE                    | 1         | 0.37%   |
| Microsoft Surface Book                             | 1         | 0.37%   |
| Metabox Edge-Pro NS50MU                            | 1         | 0.37%   |
| Lenovo Yoga S740-14IIL 81RS                        | 1         | 0.37%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Lenovo ThinkPad                         | 15        | 5.51%   |
| Dell Latitude                           | 15        | 5.51%   |
| HP Pavilion                             | 14        | 5.15%   |
| Dell Inspiron                           | 14        | 5.15%   |
| Lenovo IdeaPad                          | 10        | 3.68%   |
| Acer Aspire                             | 8         | 2.94%   |
| HP EliteBook                            | 7         | 2.57%   |
| Toshiba Satellite                       | 6         | 2.21%   |
| HP Laptop                               | 5         | 1.84%   |
| HP Compaq                               | 5         | 1.84%   |
| Dell OptiPlex                           | 5         | 1.84%   |
| HP ProBook                              | 4         | 1.47%   |
| ASUS VivoBook                           | 4         | 1.47%   |
| MSI Modern                              | 3         | 1.1%    |
| Microsoft Surface                       | 3         | 1.1%    |
| HP Notebook                             | 3         | 1.1%    |
| ASUS ROG                                | 3         | 1.1%    |
| Acer Nitro                              | 3         | 1.1%    |
| Razer Blade                             | 2         | 0.74%   |
| Lenovo Yoga                             | 2         | 0.74%   |
| HP ZBook                                | 2         | 0.74%   |
| HP ProDesk                              | 2         | 0.74%   |
| HP ENVY                                 | 2         | 0.74%   |
| Gigabyte AX370-Gaming                   | 2         | 0.74%   |
| Fujitsu LIFEBOOK                        | 2         | 0.74%   |
| Foxconn s5710t                          | 2         | 0.74%   |
| Dell XPS                                | 2         | 0.74%   |
| Dell Vostro                             | 2         | 0.74%   |
| Dell Precision                          | 2         | 0.74%   |
| ASUS Q524UQ                             | 2         | 0.74%   |
| ASUS PRIME                              | 2         | 0.74%   |
| ASUS M5A78L-M                           | 2         | 0.74%   |
| ASUS H110I-PLUS                         | 2         | 0.74%   |
| ASUS Basic                              | 2         | 0.74%   |
| Apple MacBookPro8                       | 2         | 0.74%   |
| Apple MacBookPro11                      | 2         | 0.74%   |
| Acer Swift                              | 2         | 0.74%   |
| Acer Predator                           | 2         | 0.74%   |
| Unknown                                 | 2         | 0.74%   |
| Wortmann AG TERRA                       | 1         | 0.37%   |
| Wistron FMVDD2A0H0                      | 1         | 0.37%   |
| Toxic GM7MQ8P                           | 1         | 0.37%   |
| Timi TM1613                             | 1         | 0.37%   |
| System76 Gazelle                        | 1         | 0.37%   |
| Sony VPCCB15FG                          | 1         | 0.37%   |
| Sony SVP1321L1EBI                       | 1         | 0.37%   |
| SLIMBOOK ONE-AMD-M4                     | 1         | 0.37%   |
| Samsung RV415                           | 1         | 0.37%   |
| Samsung 550P5C                          | 1         | 0.37%   |
| Samsung 350V5C                          | 1         | 0.37%   |
| Samsung 300E4C                          | 1         | 0.37%   |
| Positivo Q232A                          | 1         | 0.37%   |
| Positivo POS-PIG43BC                    | 1         | 0.37%   |
| Positivo Bahia - VAIO VJFE51F11X-B0111H | 1         | 0.37%   |
| Notebook W510TU                         | 1         | 0.37%   |
| MSI MS-7C02                             | 1         | 0.37%   |
| MSI MS-7A69                             | 1         | 0.37%   |
| MSI MS-7A34                             | 1         | 0.37%   |
| MSI MS-7529                             | 1         | 0.37%   |
| MSI GT60                                | 1         | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2011 | 34        | 12.5%   |
| 2019 | 31        | 11.4%   |
| 2018 | 27        | 9.93%   |
| 2013 | 25        | 9.19%   |
| 2016 | 22        | 8.09%   |
| 2017 | 19        | 6.99%   |
| 2021 | 18        | 6.62%   |
| 2020 | 18        | 6.62%   |
| 2014 | 17        | 6.25%   |
| 2012 | 16        | 5.88%   |
| 2010 | 14        | 5.15%   |
| 2015 | 10        | 3.68%   |
| 2007 | 7         | 2.57%   |
| 2009 | 5         | 1.84%   |
| 2008 | 5         | 1.84%   |
| 2006 | 3         | 1.1%    |
| 2022 | 1         | 0.37%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 192       | 70.59%  |
| Desktop     | 69        | 25.37%  |
| Convertible | 5         | 1.84%   |
| Tablet      | 4         | 1.47%   |
| Mini pc     | 1         | 0.37%   |
| All in one  | 1         | 0.37%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 272       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 271       | 99.63%  |
| Yes  | 1         | 0.37%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 64        | 23.27%  |
| 8.01-16.0   | 61        | 22.18%  |
| 16.01-24.0  | 54        | 19.64%  |
| 3.01-4.0    | 51        | 18.55%  |
| 32.01-64.0  | 21        | 7.64%   |
| 1.01-2.0    | 10        | 3.64%   |
| 64.01-256.0 | 7         | 2.55%   |
| 24.01-32.0  | 4         | 1.45%   |
| 2.01-3.0    | 3         | 1.09%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 97        | 33.92%  |
| 2.01-3.0   | 89        | 31.12%  |
| 3.01-4.0   | 41        | 14.34%  |
| 4.01-8.0   | 38        | 13.29%  |
| 0.51-1.0   | 13        | 4.55%   |
| 8.01-16.0  | 6         | 2.1%    |
| 16.01-24.0 | 1         | 0.35%   |
| 0.01-0.5   | 1         | 0.35%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 156       | 56.32%  |
| 2      | 92        | 33.21%  |
| 3      | 22        | 7.94%   |
| 5      | 3         | 1.08%   |
| 4      | 3         | 1.08%   |
| 6      | 1         | 0.36%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 184       | 67.15%  |
| Yes       | 90        | 32.85%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 225       | 82.72%  |
| No        | 47        | 17.28%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 250       | 91.24%  |
| No        | 24        | 8.76%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 187       | 67.75%  |
| No        | 89        | 32.25%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country         | Computers | Percent |
|-----------------|-----------|---------|
| USA             | 88        | 31.88%  |
| Germany         | 20        | 7.25%   |
| Spain           | 13        | 4.71%   |
| France          | 13        | 4.71%   |
| Netherlands     | 11        | 3.99%   |
| Brazil          | 11        | 3.99%   |
| UK              | 9         | 3.26%   |
| Russia          | 9         | 3.26%   |
| India           | 9         | 3.26%   |
| Mexico          | 7         | 2.54%   |
| Canada          | 6         | 2.17%   |
| Australia       | 6         | 2.17%   |
| Italy           | 5         | 1.81%   |
| Poland          | 4         | 1.45%   |
| Indonesia       | 4         | 1.45%   |
| Denmark         | 4         | 1.45%   |
| Sweden          | 3         | 1.09%   |
| South Africa    | 3         | 1.09%   |
| Kenya           | 3         | 1.09%   |
| Iraq            | 3         | 1.09%   |
| Czechia         | 3         | 1.09%   |
| Austria         | 3         | 1.09%   |
| Turkey          | 2         | 0.72%   |
| Portugal        | 2         | 0.72%   |
| Pakistan        | 2         | 0.72%   |
| Morocco         | 2         | 0.72%   |
| Hong Kong       | 2         | 0.72%   |
| Belgium         | 2         | 0.72%   |
| Bangladesh      | 2         | 0.72%   |
| Algeria         | 2         | 0.72%   |
| Vietnam         | 1         | 0.36%   |
| Ukraine         | 1         | 0.36%   |
| Switzerland     | 1         | 0.36%   |
| Romania         | 1         | 0.36%   |
| Puerto Rico     | 1         | 0.36%   |
| Peru            | 1         | 0.36%   |
| North Macedonia | 1         | 0.36%   |
| Nigeria         | 1         | 0.36%   |
| New Zealand     | 1         | 0.36%   |
| Myanmar         | 1         | 0.36%   |
| Latvia          | 1         | 0.36%   |
| Hungary         | 1         | 0.36%   |
| Greece          | 1         | 0.36%   |
| Georgia         | 1         | 0.36%   |
| Finland         | 1         | 0.36%   |
| Egypt           | 1         | 0.36%   |
| Croatia         | 1         | 0.36%   |
| Costa Rica      | 1         | 0.36%   |
| Colombia        | 1         | 0.36%   |
| Chile           | 1         | 0.36%   |
| Belarus         | 1         | 0.36%   |
| Azerbaijan      | 1         | 0.36%   |
| Unknown         | 1         | 0.36%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Amsterdam           | 5         | 1.75%   |
| Madrid              | 4         | 1.4%    |
| Vienna              | 3         | 1.05%   |
| Sydney              | 3         | 1.05%   |
| Seattle             | 3         | 1.05%   |
| Nairobi             | 3         | 1.05%   |
| Melbourne           | 3         | 1.05%   |
| Los Angeles         | 3         | 1.05%   |
| Indianapolis        | 3         | 1.05%   |
| Eugene              | 3         | 1.05%   |
| Dallas              | 3         | 1.05%   |
| Chicago             | 3         | 1.05%   |
| Berlin              | 3         | 1.05%   |
| Warsaw              | 2         | 0.7%    |
| Uherské Hradiště | 2         | 0.7%    |
| Tangier             | 2         | 0.7%    |
| Stockholm           | 2         | 0.7%    |
| Sao Paulo           | 2         | 0.7%    |
| Saint Paul          | 2         | 0.7%    |
| Ruskin              | 2         | 0.7%    |
| Pretoria            | 2         | 0.7%    |
| Paris               | 2         | 0.7%    |
| Ngau Wu Tok         | 2         | 0.7%    |
| Newburgh            | 2         | 0.7%    |
| New York            | 2         | 0.7%    |
| Mostoles            | 2         | 0.7%    |
| Lyon                | 2         | 0.7%    |
| Khabarovsk          | 2         | 0.7%    |
| Houston             | 2         | 0.7%    |
| Dhaka               | 2         | 0.7%    |
| Camden              | 2         | 0.7%    |
| Bussum              | 2         | 0.7%    |
| Barcelona           | 2         | 0.7%    |
| Baghdad             | 2         | 0.7%    |
| Atlanta             | 2         | 0.7%    |
| Zurich              | 1         | 0.35%   |
| Zagreb              | 1         | 0.35%   |
| West Jordan         | 1         | 0.35%   |
| West Chester        | 1         | 0.35%   |
| Washington          | 1         | 0.35%   |
| Volgograd           | 1         | 0.35%   |
| Visalia             | 1         | 0.35%   |
| Vila Nova de Gaia   | 1         | 0.35%   |
| Viby J              | 1         | 0.35%   |
| Veitsbronn          | 1         | 0.35%   |
| Vapi                | 1         | 0.35%   |
| Tulare              | 1         | 0.35%   |
| Ts'khinvali         | 1         | 0.35%   |
| Trivandrum          | 1         | 0.35%   |
| Tottenham           | 1         | 0.35%   |
| Toronto             | 1         | 0.35%   |
| Terrace             | 1         | 0.35%   |
| Tempe               | 1         | 0.35%   |
| Tangerang           | 1         | 0.35%   |
| Sviyazhsk           | 1         | 0.35%   |
| Surabaya            | 1         | 0.35%   |
| Sumaré             | 1         | 0.35%   |
| St Petersburg       | 1         | 0.35%   |
| Springfield         | 1         | 0.35%   |
| Spotsylvania        | 1         | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 59        | 79     | 14.86%  |
| Samsung Electronics | 55        | 70     | 13.85%  |
| Seagate             | 51        | 62     | 12.85%  |
| Toshiba             | 48        | 51     | 12.09%  |
| Unknown             | 25        | 26     | 6.3%    |
| Kingston            | 24        | 25     | 6.05%   |
| Sandisk             | 19        | 23     | 4.79%   |
| Hitachi             | 14        | 17     | 3.53%   |
| Crucial             | 14        | 19     | 3.53%   |
| SK Hynix            | 8         | 8      | 2.02%   |
| HGST                | 8         | 10     | 2.02%   |
| Micron Technology   | 7         | 7      | 1.76%   |
| China               | 6         | 9      | 1.51%   |
| A-DATA Technology   | 6         | 6      | 1.51%   |
| Apple               | 5         | 5      | 1.26%   |
| Intel               | 4         | 7      | 1.01%   |
| LITEONIT            | 3         | 3      | 0.76%   |
| LITEON              | 3         | 3      | 0.76%   |
| JMicron             | 3         | 3      | 0.76%   |
| Fujitsu             | 3         | 3      | 0.76%   |
| Team                | 2         | 3      | 0.5%    |
| SPCC                | 2         | 2      | 0.5%    |
| Silicon Motion      | 2         | 2      | 0.5%    |
| PNY                 | 2         | 2      | 0.5%    |
| Phison              | 2         | 2      | 0.5%    |
| KIOXIA              | 2         | 2      | 0.5%    |
| Intenso             | 2         | 3      | 0.5%    |
| HUAWEI              | 2         | 2      | 0.5%    |
| YMTC                | 1         | 1      | 0.25%   |
| W800SH              | 1         | 1      | 0.25%   |
| Transcend           | 1         | 1      | 0.25%   |
| S3+                 | 1         | 1      | 0.25%   |
| ROG                 | 1         | 1      | 0.25%   |
| PLEXTOR             | 1         | 1      | 0.25%   |
| Patriot             | 1         | 1      | 0.25%   |
| OCZ                 | 1         | 1      | 0.25%   |
| Netac               | 1         | 1      | 0.25%   |
| Lexar               | 1         | 1      | 0.25%   |
| KingSpec            | 1         | 2      | 0.25%   |
| KingFast            | 1         | 2      | 0.25%   |
| FORESEE             | 1         | 1      | 0.25%   |
| Corsair             | 1         | 2      | 0.25%   |
| BHT                 | 1         | 1      | 0.25%   |
| ASMedia             | 1         | 1      | 0.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Toshiba MQ04ABF100 1TB              | 8         | 1.85%   |
| Samsung SSD 860 EVO 500GB           | 7         | 1.62%   |
| Toshiba MQ01ABF050 500GB            | 6         | 1.39%   |
| Toshiba DT01ACA200 2TB              | 5         | 1.16%   |
| Seagate ST2000LM003 HN-M201RAD 2TB  | 5         | 1.16%   |
| Unknown SD/MMC/MS PRO 999GB         | 4         | 0.93%   |
| Unknown MMC Card  32GB              | 4         | 0.93%   |
| Toshiba MQ01ABD100 1TB              | 4         | 0.93%   |
| SanDisk SSD PLUS 1000GB             | 4         | 0.93%   |
| Kingston NVMe SSD Drive 512GB       | 4         | 0.93%   |
| HGST HTS541010A9E680 1TB            | 4         | 0.93%   |
| Toshiba MQ01ABD075 752GB            | 3         | 0.69%   |
| Seagate ST320LT007-9ZV142 320GB     | 3         | 0.69%   |
| Seagate ST31000528AS 1TB            | 3         | 0.69%   |
| Seagate ST250DM000-1BD141 250GB     | 3         | 0.69%   |
| Seagate ST1000LM035-1RK172 1TB      | 3         | 0.69%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 3         | 0.69%   |
| Seagate Expansion 4TB               | 3         | 0.69%   |
| Samsung SSD 860 EVO 250GB           | 3         | 0.69%   |
| Samsung SSD 850 EVO 250GB           | 3         | 0.69%   |
| Samsung HM500JI 500GB               | 3         | 0.69%   |
| Kingston SA400S37480G 480GB SSD     | 3         | 0.69%   |
| Kingston SA400S37240G 240GB SSD     | 3         | 0.69%   |
| JMicron Generic 128GB               | 3         | 0.69%   |
| HGST HTS721010A9E630 1TB            | 3         | 0.69%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 2         | 0.46%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 2         | 0.46%   |
| WDC WDS100T2B0B-00YS70 1TB SSD      | 2         | 0.46%   |
| WDC WD5000LPCX-24C6HT0 500GB        | 2         | 0.46%   |
| WDC WD2500JS-75MHB0 250GB           | 2         | 0.46%   |
| WDC WD2500AAKX-753CA1 250GB         | 2         | 0.46%   |
| WDC WD10SPZX-75Z10T2 1TB            | 2         | 0.46%   |
| WDC WD10SPZX-60Z10T0 1TB            | 2         | 0.46%   |
| WDC WD10EZRX-00L4HB0 1TB            | 2         | 0.46%   |
| WDC WD10EARS-00Y5B1 1TB             | 2         | 0.46%   |
| Toshiba DT01ACA100 1TB              | 2         | 0.46%   |
| Toshiba DT01ACA050 500GB            | 2         | 0.46%   |
| Seagate ST9250315AS 250GB           | 2         | 0.46%   |
| Seagate ST500VT000-1DK142 500GB     | 2         | 0.46%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 2         | 0.46%   |
| Seagate ST500LM000-SSHD-8GB         | 2         | 0.46%   |
| SanDisk SD6SF1M128G1022I 128GB SSD  | 2         | 0.46%   |
| Sandisk NVMe SSD Drive 256GB        | 2         | 0.46%   |
| Sandisk NVMe SSD Drive 1TB          | 2         | 0.46%   |
| Samsung SSD 980 1TB                 | 2         | 0.46%   |
| Samsung SSD 970 EVO Plus 1TB        | 2         | 0.46%   |
| Samsung SSD 840 Series 250GB        | 2         | 0.46%   |
| Samsung MZVLB1T0HBLR-000L2 1TB      | 2         | 0.46%   |
| Kingston SV300S37A240G 240GB SSD    | 2         | 0.46%   |
| Kingston SV300S37A120G 120GB SSD    | 2         | 0.46%   |
| Intenso SSD SATAIII 120GB           | 2         | 0.46%   |
| Hitachi HTS545050B9A300 500GB       | 2         | 0.46%   |
| Fujitsu F300 480GB                  | 2         | 0.46%   |
| Crucial CT500MX500SSD1 500GB        | 2         | 0.46%   |
| Crucial CT480BX500SSD1 480GB        | 2         | 0.46%   |
| Crucial CT1000MX500SSD1 1TB         | 2         | 0.46%   |
| Apple SSD SM0256G 256GB             | 2         | 0.46%   |
| YMTC PC005 512GB                    | 1         | 0.23%   |
| WDC WDS500G2B0C-00PXH0 500GB        | 1         | 0.23%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD    | 1         | 0.23%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 51        | 62     | 29.65%  |
| WDC                 | 45        | 60     | 26.16%  |
| Toshiba             | 41        | 43     | 23.84%  |
| Hitachi             | 14        | 17     | 8.14%   |
| HGST                | 8         | 10     | 4.65%   |
| Samsung Electronics | 7         | 9      | 4.07%   |
| Unknown             | 4         | 4      | 2.33%   |
| Fujitsu             | 1         | 1      | 0.58%   |
| ASMedia             | 1         | 1      | 0.58%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 28        | 36     | 20.9%   |
| Kingston            | 16        | 17     | 11.94%  |
| Crucial             | 13        | 18     | 9.7%    |
| SanDisk             | 12        | 13     | 8.96%   |
| WDC                 | 11        | 12     | 8.21%   |
| China               | 6         | 9      | 4.48%   |
| Toshiba             | 4         | 5      | 2.99%   |
| Apple               | 4         | 4      | 2.99%   |
| Micron Technology   | 3         | 3      | 2.24%   |
| LITEONIT            | 3         | 3      | 2.24%   |
| LITEON              | 3         | 3      | 2.24%   |
| JMicron             | 3         | 3      | 2.24%   |
| Team                | 2         | 3      | 1.49%   |
| SPCC                | 2         | 2      | 1.49%   |
| PNY                 | 2         | 2      | 1.49%   |
| Intenso             | 2         | 3      | 1.49%   |
| Intel               | 2         | 2      | 1.49%   |
| Fujitsu             | 2         | 2      | 1.49%   |
| A-DATA Technology   | 2         | 2      | 1.49%   |
| W800SH              | 1         | 1      | 0.75%   |
| Unknown             | 1         | 1      | 0.75%   |
| Transcend           | 1         | 1      | 0.75%   |
| SK Hynix            | 1         | 1      | 0.75%   |
| S3+                 | 1         | 1      | 0.75%   |
| PLEXTOR             | 1         | 1      | 0.75%   |
| Patriot             | 1         | 1      | 0.75%   |
| OCZ                 | 1         | 1      | 0.75%   |
| Netac               | 1         | 1      | 0.75%   |
| KingSpec            | 1         | 2      | 0.75%   |
| KingFast            | 1         | 1      | 0.75%   |
| FORESEE             | 1         | 1      | 0.75%   |
| Corsair             | 1         | 2      | 0.75%   |
| BHT                 | 1         | 1      | 0.75%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 151       | 207    | 42.18%  |
| SSD     | 117       | 158    | 32.68%  |
| NVMe    | 66        | 81     | 18.44%  |
| MMC     | 19        | 22     | 5.31%   |
| Unknown | 5         | 5      | 1.4%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 220       | 347    | 67.48%  |
| NVMe | 66        | 81     | 20.25%  |
| SAS  | 21        | 23     | 6.44%   |
| MMC  | 19        | 22     | 5.83%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 160       | 232    | 57.55%  |
| 0.51-1.0   | 93        | 106    | 33.45%  |
| 1.01-2.0   | 17        | 19     | 6.12%   |
| 3.01-4.0   | 6         | 6      | 2.16%   |
| 2.01-3.0   | 1         | 1      | 0.36%   |
| 4.01-10.0  | 1         | 1      | 0.36%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 71        | 25.45%  |
| 101-250        | 65        | 23.3%   |
| 501-1000       | 44        | 15.77%  |
| 1001-2000      | 34        | 12.19%  |
| Unknown        | 18        | 6.45%   |
| 51-100         | 15        | 5.38%   |
| 21-50          | 14        | 5.02%   |
| 2001-3000      | 9         | 3.23%   |
| 1-20           | 5         | 1.79%   |
| More than 3000 | 4         | 1.43%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 21-50          | 82        | 28.67%  |
| 1-20           | 50        | 17.48%  |
| 51-100         | 46        | 16.08%  |
| 101-250        | 42        | 14.69%  |
| 251-500        | 31        | 10.84%  |
| Unknown        | 18        | 6.29%   |
| 501-1000       | 12        | 4.2%    |
| 1001-2000      | 3         | 1.05%   |
| More than 3000 | 2         | 0.7%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Samsung Electronics HM500JI 500GB                   | 3         | 3      | 7.69%   |
| SanDisk SD6SF1M128G1022I 128GB SSD                  | 2         | 2      | 5.13%   |
| WDC WD5000AAKS-75V0A0 500GB                         | 1         | 1      | 2.56%   |
| WDC WD2500BEVT-22A23T0 250GB                        | 1         | 1      | 2.56%   |
| WDC WD2003FZEX-00Z4SA0 2TB                          | 1         | 1      | 2.56%   |
| WDC WD10JUCX-63WPNY0 1TB                            | 1         | 1      | 2.56%   |
| WDC WD10EZRX-00L4HB0 1TB                            | 1         | 1      | 2.56%   |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 2.56%   |
| Toshiba MK3265GSXF 320GB                            | 1         | 1      | 2.56%   |
| Seagate ST9500325AS 500GB                           | 1         | 1      | 2.56%   |
| Seagate ST9250410AS 250GB                           | 1         | 1      | 2.56%   |
| Seagate ST500NM0011 500GB                           | 1         | 1      | 2.56%   |
| Seagate ST3500413AS 500GB                           | 1         | 1      | 2.56%   |
| Seagate ST320LT007-9ZV142 320GB                     | 1         | 1      | 2.56%   |
| Seagate ST31000528AS 1TB                            | 1         | 1      | 2.56%   |
| Seagate ST250DM000-1BD141 250GB                     | 1         | 1      | 2.56%   |
| Seagate ST2000LM007-1R8174 2TB                      | 1         | 1      | 2.56%   |
| Seagate ST2000LM003 HN-M201RAD 2TB                  | 1         | 1      | 2.56%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1      | 2.56%   |
| Seagate ST1000DM010-2EP102 1TB                      | 1         | 1      | 2.56%   |
| SanDisk SSD PLUS 480GB                              | 1         | 1      | 2.56%   |
| SanDisk SSD PLUS 1000GB                             | 1         | 1      | 2.56%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD    | 1         | 1      | 2.56%   |
| Samsung Electronics HM160HI 160GB                   | 1         | 1      | 2.56%   |
| PLEXTOR PX-512M6Pro 512GB SSD                       | 1         | 1      | 2.56%   |
| Micron Technology MTFDDAK128MAY-1AH1ZABHA 128GB SSD | 1         | 1      | 2.56%   |
| LITEON CV8-8E128-HP 128GB SSD                       | 1         | 1      | 2.56%   |
| Hitachi HUA722020ALA331 2TB                         | 1         | 1      | 2.56%   |
| Hitachi HTS725050A9A360 500GB                       | 1         | 1      | 2.56%   |
| Hitachi HTS725032A9A364 320GB                       | 1         | 1      | 2.56%   |
| Hitachi HTS542512K9SA00 120GB                       | 1         | 1      | 2.56%   |
| HGST HTS721010A9E630 1TB                            | 1         | 1      | 2.56%   |
| Fujitsu MHY2160BH 160GB                             | 1         | 1      | 2.56%   |
| A-DATA Technology SX7000NP 128GB                    | 1         | 1      | 2.56%   |
| A-DATA Technology SX6000LNP 1TB                     | 1         | 1      | 2.56%   |
| A-DATA Technology SU700 120GB SSD                   | 1         | 1      | 2.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 11     | 24.32%  |
| WDC                 | 5         | 5      | 13.51%  |
| Samsung Electronics | 5         | 5      | 13.51%  |
| SanDisk             | 4         | 4      | 10.81%  |
| Hitachi             | 4         | 4      | 10.81%  |
| A-DATA Technology   | 3         | 3      | 8.11%   |
| Toshiba             | 2         | 2      | 5.41%   |
| PLEXTOR             | 1         | 1      | 2.7%    |
| Micron Technology   | 1         | 1      | 2.7%    |
| LITEON              | 1         | 1      | 2.7%    |
| HGST                | 1         | 1      | 2.7%    |
| Fujitsu             | 1         | 1      | 2.7%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 11     | 34.62%  |
| WDC                 | 5         | 5      | 19.23%  |
| Samsung Electronics | 4         | 4      | 15.38%  |
| Hitachi             | 4         | 4      | 15.38%  |
| Toshiba             | 2         | 2      | 7.69%   |
| HGST                | 1         | 1      | 3.85%   |
| Fujitsu             | 1         | 1      | 3.85%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 24        | 28     | 68.57%  |
| SSD  | 9         | 9      | 25.71%  |
| NVMe | 2         | 2      | 5.71%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                       | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC WD5000AADS-00S9B0 500GB | 1         | 1      | 50%     |
| Intenso SSD SATAIII 120GB   | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Intenso | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 150       | 253    | 47.32%  |
| Works    | 134       | 179    | 42.27%  |
| Malfunc  | 31        | 39     | 9.78%   |
| Failed   | 2         | 2      | 0.63%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 190       | 60.32%  |
| AMD                          | 47        | 14.92%  |
| Samsung Electronics          | 24        | 7.62%   |
| Sandisk                      | 12        | 3.81%   |
| Kingston Technology Company  | 8         | 2.54%   |
| SK Hynix                     | 7         | 2.22%   |
| Nvidia                       | 4         | 1.27%   |
| Micron Technology            | 4         | 1.27%   |
| Toshiba America Info Systems | 3         | 0.95%   |
| Silicon Motion               | 3         | 0.95%   |
| Phison Electronics           | 2         | 0.63%   |
| KIOXIA                       | 2         | 0.63%   |
| ADATA Technology             | 2         | 0.63%   |
| Yangtze Memory Technologies  | 1         | 0.32%   |
| VIA Technologies             | 1         | 0.32%   |
| Realtek Semiconductor        | 1         | 0.32%   |
| Micron/Crucial Technology    | 1         | 0.32%   |
| JMicron Technology           | 1         | 0.32%   |
| ASMedia Technology           | 1         | 0.32%   |
| Apple                        | 1         | 0.32%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                  | Computers | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 34        | 9.47%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 19        | 5.29%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 19        | 5.29%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 15        | 4.18%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 14        | 3.9%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 12        | 3.34%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 11        | 3.06%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 10        | 2.79%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 9         | 2.51%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 9         | 2.51%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 8         | 2.23%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 8         | 2.23%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                      | 6         | 1.67%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 6         | 1.67%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 6         | 1.67%   |
| Sandisk WD Blue SN550 NVMe SSD                                                         | 5         | 1.39%   |
| SK Hynix BC511                                                                         | 4         | 1.11%   |
| Samsung NVMe SSD Controller 980                                                        | 4         | 1.11%   |
| Micron Non-Volatile memory controller                                                  | 4         | 1.11%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 4         | 1.11%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 4         | 1.11%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 4         | 1.11%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 4         | 1.11%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 4         | 1.11%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 4         | 1.11%   |
| AMD X370 Series Chipset SATA Controller                                                | 4         | 1.11%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                        | 3         | 0.84%   |
| Samsung NVMe SSD Controller SM951/PM951                                                | 3         | 0.84%   |
| Kingston Company Company Non-Volatile memory controller                                | 3         | 0.84%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 3         | 0.84%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 3         | 0.84%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                             | 3         | 0.84%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 3         | 0.84%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 3         | 0.84%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 3         | 0.84%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]           | 3         | 0.84%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 3         | 0.84%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller          | 3         | 0.84%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller       | 2         | 0.56%   |
| SK Hynix Gold P31 SSD                                                                  | 2         | 0.56%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 2         | 0.56%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                             | 2         | 0.56%   |
| Sandisk Non-Volatile memory controller                                                 | 2         | 0.56%   |
| Samsung Electronics SATA controller                                                    | 2         | 0.56%   |
| Nvidia MCP61 SATA Controller                                                           | 2         | 0.56%   |
| Nvidia MCP61 IDE                                                                       | 2         | 0.56%   |
| KIOXIA Non-Volatile memory controller                                                  | 2         | 0.56%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                  | 2         | 0.56%   |
| Kingston Company A2000 NVMe SSD                                                        | 2         | 0.56%   |
| Intel SATA Controller [RAID mode]                                                      | 2         | 0.56%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 2         | 0.56%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 2         | 0.56%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 2         | 0.56%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                      | 2         | 0.56%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 2         | 0.56%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 2         | 0.56%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                       | 2         | 0.56%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                       | 2         | 0.56%   |
| AMD FCH SATA Controller [IDE mode]                                                     | 2         | 0.56%   |
| AMD 400 Series Chipset SATA Controller                                                 | 2         | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 195       | 60.37%  |
| NVMe | 66        | 20.43%  |
| IDE  | 36        | 11.15%  |
| RAID | 26        | 8.05%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 215       | 79.04%  |
| AMD    | 57        | 20.96%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz             | 6         | 2.21%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 5         | 1.84%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 5         | 1.84%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 5         | 1.84%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 1.47%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 1.47%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 1.47%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 1.47%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 4         | 1.47%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 1.1%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 3         | 1.1%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 1.1%    |
| Intel Core i5-7400 CPU @ 3.00GHz              | 3         | 1.1%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 1.1%    |
| Intel Core i5-3230M CPU @ 2.60GHz             | 3         | 1.1%    |
| Intel Core i5-2430M CPU @ 2.40GHz             | 3         | 1.1%    |
| Intel Celeron CPU N3060 @ 1.60GHz             | 3         | 1.1%    |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 3         | 1.1%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 1.1%    |
| AMD Ryzen 7 5700U with Radeon Graphics        | 3         | 1.1%    |
| Intel Xeon CPU E3-1246 v3 @ 3.50GHz           | 2         | 0.74%   |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz   | 2         | 0.74%   |
| Intel Pentium CPU G3260 @ 3.30GHz             | 2         | 0.74%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 2         | 0.74%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 0.74%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 0.74%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 2         | 0.74%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 2         | 0.74%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 0.74%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 2         | 0.74%   |
| Intel Core i7-2620M CPU @ 2.70GHz             | 2         | 0.74%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 0.74%   |
| Intel Core i5-6400 CPU @ 2.70GHz              | 2         | 0.74%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 2         | 0.74%   |
| Intel Core i5-4310U CPU @ 2.00GHz             | 2         | 0.74%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 2         | 0.74%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 0.74%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 2         | 0.74%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 2         | 0.74%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 0.74%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 0.74%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 2         | 0.74%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 0.74%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 2         | 0.74%   |
| Intel Core 2 CPU T5600 @ 1.83GHz              | 2         | 0.74%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 2         | 0.74%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 0.74%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 0.74%   |
| AMD Ryzen 7 2700 Eight-Core Processor         | 2         | 0.74%   |
| AMD Ryzen 7 1700X Eight-Core Processor        | 2         | 0.74%   |
| AMD E1-2500 APU with Radeon HD Graphics       | 2         | 0.74%   |
| AMD A6-9225 RADEON R4, 5 COMPUTE CORES 2C+3G  | 2         | 0.74%   |
| Intel Xeon CPU X5460 @ 3.16GHz                | 1         | 0.37%   |
| Intel Xeon CPU E5620 @ 2.40GHz                | 1         | 0.37%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 0.37%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.37%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 0.37%   |
| Intel Pentium Dual-Core CPU E5500 @ 2.80GHz   | 1         | 0.37%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz        | 1         | 0.37%   |
| Intel Pentium CPU N3530 @ 2.16GHz             | 1         | 0.37%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 76        | 27.94%  |
| Intel Core i7           | 66        | 24.26%  |
| Intel Core i3           | 20        | 7.35%   |
| AMD Ryzen 7             | 13        | 4.78%   |
| Other                   | 11        | 4.04%   |
| Intel Core 2 Duo        | 9         | 3.31%   |
| Intel Celeron           | 8         | 2.94%   |
| AMD Ryzen 5             | 8         | 2.94%   |
| Intel Pentium           | 6         | 2.21%   |
| AMD A6                  | 6         | 2.21%   |
| Intel Xeon              | 4         | 1.47%   |
| Intel Pentium Dual-Core | 4         | 1.47%   |
| Intel Core 2            | 3         | 1.1%    |
| Intel Atom              | 3         | 1.1%    |
| AMD Ryzen 3             | 3         | 1.1%    |
| AMD FX                  | 3         | 1.1%    |
| AMD E1                  | 3         | 1.1%    |
| AMD A4                  | 3         | 1.1%    |
| Intel Pentium Silver    | 2         | 0.74%   |
| Intel Core 2 Quad       | 2         | 0.74%   |
| AMD Athlon II X2        | 2         | 0.74%   |
| AMD A8                  | 2         | 0.74%   |
| AMD A10                 | 2         | 0.74%   |
| Intel Pentium Dual      | 1         | 0.37%   |
| Intel Core M            | 1         | 0.37%   |
| Intel Core 2 Extreme    | 1         | 0.37%   |
| AMD Ryzen Threadripper  | 1         | 0.37%   |
| AMD Ryzen 9             | 1         | 0.37%   |
| AMD Phenom II X4        | 1         | 0.37%   |
| AMD Phenom              | 1         | 0.37%   |
| AMD E2                  | 1         | 0.37%   |
| AMD E                   | 1         | 0.37%   |
| AMD C-50                | 1         | 0.37%   |
| AMD Athlon X2           | 1         | 0.37%   |
| AMD Athlon 64 X2        | 1         | 0.37%   |
| AMD Athlon 64           | 1         | 0.37%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 133       | 48.9%   |
| 4      | 92        | 33.82%  |
| 6      | 21        | 7.72%   |
| 8      | 17        | 6.25%   |
| 1      | 4         | 1.47%   |
| 12     | 2         | 0.74%   |
| 3      | 2         | 0.74%   |
| 14     | 1         | 0.37%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 271       | 99.63%  |
| 2      | 1         | 0.37%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 190       | 69.85%  |
| 1      | 82        | 30.15%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 267       | 98.16%  |
| Unknown        | 5         | 1.84%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 137       | 48.93%  |
| 0x206a7    | 17        | 6.07%   |
| 0x306a9    | 9         | 3.21%   |
| 0x806e9    | 8         | 2.86%   |
| 0x906ea    | 7         | 2.5%    |
| 0x306c3    | 7         | 2.5%    |
| 0x806ec    | 6         | 2.14%   |
| 0x806ea    | 6         | 2.14%   |
| 0x1067a    | 6         | 2.14%   |
| 0xa0652    | 5         | 1.79%   |
| 0x406e3    | 5         | 1.79%   |
| 0x40651    | 5         | 1.79%   |
| 0x906e9    | 4         | 1.43%   |
| 0x806c1    | 4         | 1.43%   |
| 0x706e5    | 3         | 1.07%   |
| 0x6f6      | 3         | 1.07%   |
| 0x406c4    | 3         | 1.07%   |
| 0x07030105 | 3         | 1.07%   |
| 0x06006705 | 3         | 1.07%   |
| 0x906ed    | 2         | 0.71%   |
| 0x806d1    | 2         | 0.71%   |
| 0x706a8    | 2         | 0.71%   |
| 0x306d4    | 2         | 0.71%   |
| 0x08701021 | 2         | 0.71%   |
| 0x08600106 | 2         | 0.71%   |
| 0x08108109 | 2         | 0.71%   |
| 0x08001138 | 2         | 0.71%   |
| 0x06001119 | 2         | 0.71%   |
| 0x06000852 | 2         | 0.71%   |
| 0x03000027 | 2         | 0.71%   |
| 0x906a3    | 1         | 0.36%   |
| 0x806eb    | 1         | 0.36%   |
| 0x806c2    | 1         | 0.36%   |
| 0x706a1    | 1         | 0.36%   |
| 0x6fd      | 1         | 0.36%   |
| 0x506e3    | 1         | 0.36%   |
| 0x506c9    | 1         | 0.36%   |
| 0x40661    | 1         | 0.36%   |
| 0x20655    | 1         | 0.36%   |
| 0x106a5    | 1         | 0.36%   |
| 0x0a201016 | 1         | 0.36%   |
| 0x08108102 | 1         | 0.36%   |
| 0x0810100b | 1         | 0.36%   |
| 0x0800820d | 1         | 0.36%   |
| 0x0600111f | 1         | 0.36%   |
| 0x05000029 | 1         | 0.36%   |
| 0x01000095 | 1         | 0.36%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 54        | 19.85%  |
| Haswell          | 29        | 10.66%  |
| SandyBridge      | 24        | 8.82%   |
| IvyBridge        | 19        | 6.99%   |
| Skylake          | 17        | 6.25%   |
| Penryn           | 14        | 5.15%   |
| Broadwell        | 11        | 4.04%   |
| Silvermont       | 9         | 3.31%   |
| Piledriver       | 8         | 2.94%   |
| Core             | 8         | 2.94%   |
| Zen+             | 7         | 2.57%   |
| Zen              | 7         | 2.57%   |
| CometLake        | 7         | 2.57%   |
| TigerLake        | 6         | 2.21%   |
| IceLake          | 6         | 2.21%   |
| Zen 2            | 5         | 1.84%   |
| Westmere         | 5         | 1.84%   |
| Excavator        | 5         | 1.84%   |
| K10              | 4         | 1.47%   |
| Unknown          | 4         | 1.47%   |
| Zen 3            | 3         | 1.1%    |
| Puma             | 3         | 1.1%    |
| Jaguar           | 3         | 1.1%    |
| Goldmont plus    | 3         | 1.1%    |
| K8 Hammer        | 2         | 0.74%   |
| K10 Llano        | 2         | 0.74%   |
| Bobcat           | 2         | 0.74%   |
| Steamroller      | 1         | 0.37%   |
| Nehalem          | 1         | 0.37%   |
| K8 & K10 hybrid  | 1         | 0.37%   |
| Goldmont         | 1         | 0.37%   |
| Alderlake Hybrid | 1         | 0.37%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 182       | 52.3%   |
| Nvidia | 89        | 25.57%  |
| AMD    | 77        | 22.13%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 18        | 5.1%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 14        | 3.97%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 14        | 3.97%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 11        | 3.12%   |
| Intel UHD Graphics 620                                                                   | 9         | 2.55%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 2.55%   |
| Intel HD Graphics 5500                                                                   | 9         | 2.55%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 9         | 2.55%   |
| Intel HD Graphics 620                                                                    | 8         | 2.27%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 7         | 1.98%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 6         | 1.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 1.7%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 6         | 1.7%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 1.42%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 5         | 1.42%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 5         | 1.42%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 1.42%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 4         | 1.13%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 1.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 4         | 1.13%   |
| Intel HD Graphics 630                                                                    | 4         | 1.13%   |
| Intel HD Graphics 530                                                                    | 4         | 1.13%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 1.13%   |
| AMD Lucienne                                                                             | 4         | 1.13%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 3         | 0.85%   |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 0.85%   |
| Nvidia GM107 [GeForce GTX 750]                                                           | 3         | 0.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 0.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 0.85%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 0.85%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 0.85%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 0.85%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3         | 0.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 0.85%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 0.85%   |
| AMD Renoir                                                                               | 3         | 0.85%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 3         | 0.85%   |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                                     | 3         | 0.85%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.57%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 2         | 0.57%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.57%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 2         | 0.57%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 2         | 0.57%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 2         | 0.57%   |
| Nvidia GK107M [GeForce GT 650M]                                                          | 2         | 0.57%   |
| Nvidia GF106 [GeForce GTS 450]                                                           | 2         | 0.57%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 0.57%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 2         | 0.57%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 0.57%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 0.57%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 0.57%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 2         | 0.57%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2         | 0.57%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 2         | 0.57%   |
| AMD Sumo [Radeon HD 6520G]                                                               | 2         | 0.57%   |
| AMD RV515/M54 [Mobility Radeon X1400]                                                    | 2         | 0.57%   |
| AMD RS780L [Radeon 3000]                                                                 | 2         | 0.57%   |
| AMD Kabini [Radeon HD 8240 / R3 Series]                                                  | 2         | 0.57%   |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                                         | 2         | 0.57%   |
| AMD Cezanne                                                                              | 2         | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 110       | 40.44%  |
| 1 x AMD        | 58        | 21.32%  |
| Intel + Nvidia | 51        | 18.75%  |
| 1 x Nvidia     | 34        | 12.5%   |
| Intel + AMD    | 14        | 5.15%   |
| AMD + Nvidia   | 4         | 1.47%   |
| 2 x AMD        | 1         | 0.37%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 241       | 88.28%  |
| Proprietary | 29        | 10.62%  |
| Unknown     | 3         | 1.1%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 198       | 71.48%  |
| 1.01-2.0   | 21        | 7.58%   |
| 0.51-1.0   | 18        | 6.5%    |
| 3.01-4.0   | 16        | 5.78%   |
| 0.01-0.5   | 15        | 5.42%   |
| 7.01-8.0   | 5         | 1.81%   |
| 5.01-6.0   | 3         | 1.08%   |
| 2.01-3.0   | 1         | 0.36%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 48        | 15.95%  |
| LG Display              | 41        | 13.62%  |
| Samsung Electronics     | 35        | 11.63%  |
| Chimei Innolux          | 31        | 10.3%   |
| BOE                     | 29        | 9.63%   |
| Dell                    | 12        | 3.99%   |
| Apple                   | 9         | 2.99%   |
| Acer                    | 9         | 2.99%   |
| Chi Mei Optoelectronics | 7         | 2.33%   |
| Philips                 | 6         | 1.99%   |
| Hewlett-Packard         | 6         | 1.99%   |
| Goldstar                | 6         | 1.99%   |
| Unknown                 | 5         | 1.66%   |
| BenQ                    | 5         | 1.66%   |
| Sharp                   | 4         | 1.33%   |
| Panasonic               | 4         | 1.33%   |
| AOC                     | 4         | 1.33%   |
| Ancor Communications    | 4         | 1.33%   |
| PANDA                   | 3         | 1%      |
| Lenovo                  | 3         | 1%      |
| AUS                     | 3         | 1%      |
| Vizio                   | 2         | 0.66%   |
| ViewSonic               | 2         | 0.66%   |
| Toshiba                 | 2         | 0.66%   |
| NEC Computers           | 2         | 0.66%   |
| Eizo                    | 2         | 0.66%   |
| ___                     | 1         | 0.33%   |
| Unknown (AAA)           | 1         | 0.33%   |
| STD                     | 1         | 0.33%   |
| STA                     | 1         | 0.33%   |
| Sony                    | 1         | 0.33%   |
| Sceptre Tech            | 1         | 0.33%   |
| Sceptre                 | 1         | 0.33%   |
| Sanyo                   | 1         | 0.33%   |
| RIS                     | 1         | 0.33%   |
| ONN                     | 1         | 0.33%   |
| Kogan                   | 1         | 0.33%   |
| Insignia                | 1         | 0.33%   |
| InfoVision              | 1         | 0.33%   |
| Iiyama                  | 1         | 0.33%   |
| CSO                     | 1         | 0.33%   |
| Ativa                   | 1         | 0.33%   |
| AGO                     | 1         | 0.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 3         | 0.98%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 3         | 0.98%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch        | 3         | 0.98%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch        | 3         | 0.98%   |
| Unknown LCD Monitor XMD Mi TV 1360x768                                | 2         | 0.66%   |
| Toshiba TV TSB0105 1920x1080 708x398mm 32.0-inch                      | 2         | 0.66%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch  | 2         | 0.66%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch  | 2         | 0.66%   |
| Samsung Electronics LCD Monitor SEC3542 2160x1440 254x169mm 12.0-inch | 2         | 0.66%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch  | 2         | 0.66%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 2         | 0.66%   |
| Philips PHL 276E9Q PHLC17B 1920x1080 598x336mm 27.0-inch              | 2         | 0.66%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 0.66%   |
| Panasonic VVX16T029D00 MEI96A2 2880x1620 344x193mm 15.5-inch          | 2         | 0.66%   |
| Panasonic TV MEIA08F 1920x540                                         | 2         | 0.66%   |
| NEC Computers EA243WM NEC6864 1920x1200 519x324mm 24.1-inch           | 2         | 0.66%   |
| LG Display LCD Monitor LGD0390 1600x900 382x215mm 17.3-inch           | 2         | 0.66%   |
| LG Display LCD Monitor LGD01E9 1920x1080 345x194mm 15.6-inch          | 2         | 0.66%   |
| Hewlett-Packard LE1901w HWP2842 1440x900 410x256mm 19.0-inch          | 2         | 0.66%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch      | 2         | 0.66%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 2         | 0.66%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 2         | 0.66%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 340x190mm 15.3-inch       | 2         | 0.66%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                 | 2         | 0.66%   |
| BenQ GW2760 BNQ78C6 1920x1080 600x340mm 27.2-inch                     | 2         | 0.66%   |
| AUS LCD Monitor VG245 1920x1080                                       | 2         | 0.66%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch         | 2         | 0.66%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 2         | 0.66%   |
| Acer X223W ACR0011 1680x1050 473x296mm 22.0-inch                      | 2         | 0.66%   |
| ___ LCDTV16 ___9000 1360x768                                          | 1         | 0.33%   |
| Vizio VO42LFHDTV10A VIZ0043 1920x1080 930x520mm 41.9-inch             | 1         | 0.33%   |
| Vizio E220VA VIZ0070 1920x1080 476x268mm 21.5-inch                    | 1         | 0.33%   |
| ViewSonic VX2703 SERIES VSCF62B 1920x1080 597x336mm 27.0-inch         | 1         | 0.33%   |
| ViewSonic VA2446 SERIES VSC732E 1920x1080 521x293mm 23.5-inch         | 1         | 0.33%   |
| Unknown PHILCO 9000 1360x768 1600x900mm 72.3-inch                     | 1         | 0.33%   |
| Unknown LCD Monitor SAMSUNG 3840x1080                                 | 1         | 0.33%   |
| Unknown LCD Monitor HRX 32H4030 1920x1080                             | 1         | 0.33%   |
| Unknown (AAA) LCDTV AAA0042 1360x768 890x500mm 40.2-inch              | 1         | 0.33%   |
| STD Monitor STD0001 1920x1080                                         | 1         | 0.33%   |
| STA XR140EA1T STA0450 1366x768 310x174mm 14.0-inch                    | 1         | 0.33%   |
| Sony SDM-HX73 SNY2870 1280x1024 338x270mm 17.0-inch                   | 1         | 0.33%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch               | 1         | 0.33%   |
| Sharp LCD Monitor SHP14A2 1920x1080 309x174mm 14.0-inch               | 1         | 0.33%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch               | 1         | 0.33%   |
| Sharp LCD Monitor SHP143A 3840x2160 346x194mm 15.6-inch               | 1         | 0.33%   |
| Sceptre Tech Sceptre F24 SPT09AB 1920x1080 530x290mm 23.8-inch        | 1         | 0.33%   |
| Sceptre LCD Monitor P30 2560x1080                                     | 1         | 0.33%   |
| Sanyo LCD SAN0B51 1920x540                                            | 1         | 0.33%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch     | 1         | 0.33%   |
| Samsung Electronics SyncMaster SAM064F 1920x1080 510x290mm 23.1-inch  | 1         | 0.33%   |
| Samsung Electronics SyncMaster SAM0589 1920x1080 521x293mm 23.5-inch  | 1         | 0.33%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 490x320mm 23.0-inch  | 1         | 0.33%   |
| Samsung Electronics SyncMaster SAM027E 1680x1050 470x300mm 22.0-inch  | 1         | 0.33%   |
| Samsung Electronics SMT24A550 SAM07B5 1920x1080 531x299mm 24.0-inch   | 1         | 0.33%   |
| Samsung Electronics S27E510 SAM0C5F 1920x1080 600x340mm 27.2-inch     | 1         | 0.33%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 0.33%   |
| Samsung Electronics LCD Monitor SyncMaster                            | 1         | 0.33%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 353x198mm 15.9-inch | 1         | 0.33%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch  | 1         | 0.33%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch  | 1         | 0.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 129       | 44.48%  |
| 1366x768 (WXGA)    | 72        | 24.83%  |
| 1600x900 (HD+)     | 16        | 5.52%   |
| 1680x1050 (WSXGA+) | 10        | 3.45%   |
| 1280x800 (WXGA)    | 10        | 3.45%   |
| 3840x2160 (4K)     | 7         | 2.41%   |
| 1440x900 (WXGA+)   | 7         | 2.41%   |
| 1280x1024 (SXGA)   | 7         | 2.41%   |
| 1360x768           | 5         | 1.72%   |
| 2160x1440          | 4         | 1.38%   |
| 1920x1200 (WUXGA)  | 4         | 1.38%   |
| 2560x1440 (QHD)    | 3         | 1.03%   |
| 1920x540           | 3         | 1.03%   |
| 3840x1080          | 2         | 0.69%   |
| 2880x1800          | 2         | 0.69%   |
| 2560x1600          | 2         | 0.69%   |
| 2560x1080          | 2         | 0.69%   |
| Unknown            | 2         | 0.69%   |
| 3200x1080          | 1         | 0.34%   |
| 1280x720 (HD)      | 1         | 0.34%   |
| 1024x768 (XGA)     | 1         | 0.34%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 89        | 29.57%  |
| 14      | 32        | 10.63%  |
| 13      | 32        | 10.63%  |
| 17      | 27        | 8.97%   |
| 24      | 16        | 5.32%   |
| Unknown | 16        | 5.32%   |
| 27      | 15        | 4.98%   |
| 23      | 13        | 4.32%   |
| 12      | 10        | 3.32%   |
| 21      | 9         | 2.99%   |
| 22      | 8         | 2.66%   |
| 31      | 7         | 2.33%   |
| 19      | 6         | 1.99%   |
| 11      | 4         | 1.33%   |
| 32      | 3         | 1%      |
| 40      | 2         | 0.66%   |
| 18      | 2         | 0.66%   |
| 16      | 2         | 0.66%   |
| 72      | 1         | 0.33%   |
| 52      | 1         | 0.33%   |
| 48      | 1         | 0.33%   |
| 42      | 1         | 0.33%   |
| 41      | 1         | 0.33%   |
| 34      | 1         | 0.33%   |
| 25      | 1         | 0.33%   |
| 20      | 1         | 0.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 146       | 49.32%  |
| 501-600     | 39        | 13.18%  |
| 351-400     | 28        | 9.46%   |
| 201-300     | 25        | 8.45%   |
| 401-500     | 23        | 7.77%   |
| Unknown     | 16        | 5.41%   |
| 601-700     | 8         | 2.7%    |
| 701-800     | 4         | 1.35%   |
| 801-900     | 2         | 0.68%   |
| 1001-1500   | 2         | 0.68%   |
| 901-1000    | 2         | 0.68%   |
| 1501-2000   | 1         | 0.34%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 217       | 78.34%  |
| 16/10   | 32        | 11.55%  |
| Unknown | 11        | 3.97%   |
| 5/4     | 6         | 2.17%   |
| 32/9    | 4         | 1.44%   |
| 3/2     | 3         | 1.08%   |
| 4/3     | 2         | 0.72%   |
| 6/5     | 1         | 0.36%   |
| 21/9    | 1         | 0.36%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 90        | 30%     |
| 81-90          | 55        | 18.33%  |
| 201-250        | 37        | 12.33%  |
| 121-130        | 20        | 6.67%   |
| Unknown        | 16        | 5.33%   |
| 301-350        | 15        | 5%      |
| 351-500        | 11        | 3.67%   |
| 71-80          | 10        | 3.33%   |
| 151-200        | 10        | 3.33%   |
| 61-70          | 9         | 3%      |
| 251-300        | 6         | 2%      |
| 141-150        | 6         | 2%      |
| 501-1000       | 5         | 1.67%   |
| 51-60          | 4         | 1.33%   |
| 131-140        | 3         | 1%      |
| More than 1000 | 2         | 0.67%   |
| 111-120        | 1         | 0.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 91        | 31.38%  |
| 101-120       | 83        | 28.62%  |
| 51-100        | 73        | 25.17%  |
| Unknown       | 16        | 5.52%   |
| 161-240       | 15        | 5.17%   |
| 1-50          | 7         | 2.41%   |
| More than 240 | 5         | 1.72%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 226       | 82.18%  |
| 2     | 41        | 14.91%  |
| 3     | 4         | 1.45%   |
| 0     | 4         | 1.45%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 154       | 33.33%  |
| Intel                                  | 132       | 28.57%  |
| Qualcomm Atheros                       | 52        | 11.26%  |
| Broadcom                               | 28        | 6.06%   |
| Ralink Technology                      | 12        | 2.6%    |
| Broadcom Limited                       | 9         | 1.95%   |
| Qualcomm Atheros Communications        | 8         | 1.73%   |
| TP-Link                                | 7         | 1.52%   |
| Samsung Electronics                    | 6         | 1.3%    |
| MEDIATEK                               | 6         | 1.3%    |
| Huawei Technologies                    | 5         | 1.08%   |
| NetGear                                | 4         | 0.87%   |
| ASUSTek Computer                       | 4         | 0.87%   |
| Xiaomi                                 | 3         | 0.65%   |
| Ralink                                 | 3         | 0.65%   |
| Nvidia                                 | 3         | 0.65%   |
| Microsoft                              | 3         | 0.65%   |
| Marvell Technology Group               | 3         | 0.65%   |
| D-Link System                          | 3         | 0.65%   |
| OnePlus Technology (Shenzhen)          | 2         | 0.43%   |
| Linksys                                | 2         | 0.43%   |
| ASIX Electronics                       | 2         | 0.43%   |
| ZyXEL Communications                   | 1         | 0.22%   |
| vivo                                   | 1         | 0.22%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.22%   |
| Sagem                                  | 1         | 0.22%   |
| ICS Advent                             | 1         | 0.22%   |
| Gemtek                                 | 1         | 0.22%   |
| Ericsson Business Mobile Networks      | 1         | 0.22%   |
| Davicom Semiconductor                  | 1         | 0.22%   |
| D-Link                                 | 1         | 0.22%   |
| Arduino SA                             | 1         | 0.22%   |
| Apple                                  | 1         | 0.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                              | Computers | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller  | 89        | 16.18%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller              | 30        | 5.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)              | 14        | 2.55%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter         | 12        | 2.18%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                           | 8         | 1.45%   |
| Qualcomm Atheros AR9271 802.11n                                    | 8         | 1.45%   |
| Intel Wireless 7265                                                | 8         | 1.45%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                       | 8         | 1.45%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                           | 8         | 1.45%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)     | 7         | 1.27%   |
| Intel Wireless 8265 / 8275                                         | 7         | 1.27%   |
| Intel Wireless 7260                                                | 7         | 1.27%   |
| Intel Comet Lake PCH CNVi WiFi                                     | 7         | 1.27%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                       | 6         | 1.09%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter           | 6         | 1.09%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter              | 6         | 1.09%   |
| Ralink RT2870/RT3070 Wireless Adapter                              | 6         | 1.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                   | 6         | 1.09%   |
| Intel Wi-Fi 6 AX201                                                | 6         | 1.09%   |
| Intel Wi-Fi 6 AX200                                                | 6         | 1.09%   |
| Intel Ethernet Connection I218-LM                                  | 6         | 1.09%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                 | 5         | 0.91%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter            | 5         | 0.91%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter         | 5         | 0.91%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller          | 5         | 0.91%   |
| Intel Wireless 8260                                                | 5         | 0.91%   |
| Intel Wireless 3165                                                | 5         | 0.91%   |
| Intel Wireless 3160                                                | 5         | 0.91%   |
| Intel Cannon Lake PCH CNVi WiFi                                    | 5         | 0.91%   |
| Samsung Galaxy series, misc. (tethering mode)                      | 4         | 0.73%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                    | 4         | 0.73%   |
| Ralink MT7601U Wireless Adapter                                    | 4         | 0.73%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                   | 4         | 0.73%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                           | 4         | 0.73%   |
| Intel Ethernet Connection (2) I219-V                               | 4         | 0.73%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                    | 4         | 0.73%   |
| Intel Centrino Advanced-N 6235                                     | 4         | 0.73%   |
| Broadcom BCM43142 802.11b/g/n                                      | 4         | 0.73%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter           | 3         | 0.55%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                | 3         | 0.55%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                    | 3         | 0.55%   |
| Realtek RTL8723DE Wireless Network Adapter                         | 3         | 0.55%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                | 3         | 0.55%   |
| Realtek RTL8188EE Wireless Network Adapter                         | 3         | 0.55%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                         | 3         | 0.55%   |
| Realtek 802.11ac NIC                                               | 3         | 0.55%   |
| MEDIATEK MT7921K (RZ608) Wi-Fi 6E 80MHz                            | 3         | 0.55%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                  | 3         | 0.55%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                    | 3         | 0.55%   |
| Intel I211 Gigabit Network Connection                              | 3         | 0.55%   |
| Intel Ethernet Connection I217-V                                   | 3         | 0.55%   |
| Intel Ethernet Connection I217-LM                                  | 3         | 0.55%   |
| Intel Ethernet Connection (4) I219-LM                              | 3         | 0.55%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                  | 3         | 0.55%   |
| Broadcom BCM43228 802.11a/b/g/n                                    | 3         | 0.55%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                | 3         | 0.55%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU] | 3         | 0.55%   |
| Xiaomi Mi/Redmi series (RNDIS)                                     | 2         | 0.36%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)        | 2         | 0.36%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter           | 2         | 0.36%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 112       | 37.84%  |
| Realtek Semiconductor           | 60        | 20.27%  |
| Qualcomm Atheros                | 39        | 13.18%  |
| Broadcom                        | 23        | 7.77%   |
| Ralink Technology               | 12        | 4.05%   |
| Qualcomm Atheros Communications | 8         | 2.7%    |
| TP-Link                         | 7         | 2.36%   |
| Broadcom Limited                | 7         | 2.36%   |
| NetGear                         | 4         | 1.35%   |
| MEDIATEK                        | 4         | 1.35%   |
| ASUSTek Computer                | 4         | 1.35%   |
| Ralink                          | 3         | 1.01%   |
| Microsoft                       | 3         | 1.01%   |
| Marvell Technology Group        | 3         | 1.01%   |
| Linksys                         | 2         | 0.68%   |
| ZyXEL Communications            | 1         | 0.34%   |
| Sagem                           | 1         | 0.34%   |
| Gemtek                          | 1         | 0.34%   |
| D-Link System                   | 1         | 0.34%   |
| D-Link                          | 1         | 0.34%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 12        | 4.04%   |
| Qualcomm Atheros AR9271 802.11n                                         | 8         | 2.69%   |
| Intel Wireless 7265                                                     | 8         | 2.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 8         | 2.69%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 8         | 2.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 2.36%   |
| Intel Wireless 8265 / 8275                                              | 7         | 2.36%   |
| Intel Wireless 7260                                                     | 7         | 2.36%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 7         | 2.36%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 6         | 2.02%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 2.02%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 6         | 2.02%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 6         | 2.02%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 2.02%   |
| Intel Wi-Fi 6 AX201                                                     | 6         | 2.02%   |
| Intel Wi-Fi 6 AX200                                                     | 6         | 2.02%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 5         | 1.68%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 5         | 1.68%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 1.68%   |
| Intel Wireless 8260                                                     | 5         | 1.68%   |
| Intel Wireless 3165                                                     | 5         | 1.68%   |
| Intel Wireless 3160                                                     | 5         | 1.68%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 1.68%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 1.35%   |
| Ralink MT7601U Wireless Adapter                                         | 4         | 1.35%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 4         | 1.35%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 1.35%   |
| Intel Centrino Advanced-N 6235                                          | 4         | 1.35%   |
| Broadcom BCM43142 802.11b/g/n                                           | 4         | 1.35%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.01%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                     | 3         | 1.01%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                         | 3         | 1.01%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 1.01%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 1.01%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 1.01%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 1.01%   |
| Realtek 802.11ac NIC                                                    | 3         | 1.01%   |
| MEDIATEK MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 3         | 1.01%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                       | 3         | 1.01%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 1.01%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 1.01%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 3         | 1.01%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 1.01%   |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU]      | 3         | 1.01%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 0.67%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.67%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.67%   |
| Realtek RTL8187 Wireless Adapter                                        | 2         | 0.67%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 0.67%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.67%   |
| Microsoft Xbox 360 Wireless Adapter                                     | 2         | 0.67%   |
| Intel Wireless-AC 9260                                                  | 2         | 0.67%   |
| Intel Ultimate N WiFi Link 5300                                         | 2         | 0.67%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 0.67%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 0.67%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 2         | 0.67%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 0.67%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 2         | 0.67%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter              | 2         | 0.67%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 2         | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 133       | 55.42%  |
| Intel                 | 53        | 22.08%  |
| Qualcomm Atheros      | 20        | 8.33%   |
| Broadcom              | 9         | 3.75%   |
| Samsung Electronics   | 6         | 2.5%    |
| Xiaomi                | 3         | 1.25%   |
| Nvidia                | 3         | 1.25%   |
| MediaTek              | 2         | 0.83%   |
| D-Link System         | 2         | 0.83%   |
| Broadcom Limited      | 2         | 0.83%   |
| ASIX Electronics      | 2         | 0.83%   |
| vivo                  | 1         | 0.42%   |
| ICS Advent            | 1         | 0.42%   |
| Huawei Technologies   | 1         | 0.42%   |
| Davicom Semiconductor | 1         | 0.42%   |
| Apple                 | 1         | 0.42%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 89        | 36.48%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 30        | 12.3%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 14        | 5.74%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 3.28%   |
| Intel Ethernet Connection I218-LM                                 | 6         | 2.46%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 5         | 2.05%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 4         | 1.64%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4         | 1.64%   |
| Intel Ethernet Connection (2) I219-V                              | 4         | 1.64%   |
| Intel I211 Gigabit Network Connection                             | 3         | 1.23%   |
| Intel Ethernet Connection I217-V                                  | 3         | 1.23%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.23%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.23%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.82%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 0.82%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.82%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.82%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.82%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.82%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.82%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.82%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.82%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.82%   |
| Nvidia MCP61 Ethernet                                             | 2         | 0.82%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.82%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.82%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.82%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2         | 0.82%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.82%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 2         | 0.82%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.41%   |
| vivo 1806                                                         | 1         | 0.41%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.41%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.41%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.41%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.41%   |
| Nvidia MCP89 Ethernet                                             | 1         | 0.41%   |
| MediaTek Vodafone Smart N10                                       | 1         | 0.41%   |
| MediaTek SP514                                                    | 1         | 0.41%   |
| Intel PRO/100 VE Network Connection                               | 1         | 0.41%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.41%   |
| Intel Ethernet controller                                         | 1         | 0.41%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.41%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.41%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.41%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.41%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.41%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.41%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.41%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 0.41%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.41%   |
| ICS Advent USB 10/100 LAN                                         | 1         | 0.41%   |
| Huawei MAR-LX1A                                                   | 1         | 0.41%   |
| Davicom DM9621A USB To FastEther                                  | 1         | 0.41%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 0.41%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 0.41%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 0.41%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express             | 1         | 0.41%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 0.41%   |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe         | 1         | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 251       | 51.86%  |
| Ethernet | 224       | 46.28%  |
| Modem    | 5         | 1.03%   |
| Unknown  | 4         | 0.83%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 203       | 69.28%  |
| Ethernet | 88        | 30.03%  |
| Unknown  | 2         | 0.68%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 161       | 58.97%  |
| 1     | 103       | 37.73%  |
| 3     | 5         | 1.83%   |
| 0     | 4         | 1.47%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used    | Computers | Percent |
|---------|-----------|---------|
| No      | 232       | 84.06%  |
| Yes     | 43        | 15.58%  |
| Unknown | 1         | 0.36%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 87        | 46.52%  |
| Realtek Semiconductor           | 19        | 10.16%  |
| Qualcomm Atheros Communications | 19        | 10.16%  |
| Broadcom                        | 13        | 6.95%   |
| Cambridge Silicon Radio         | 10        | 5.35%   |
| Apple                           | 7         | 3.74%   |
| Lite-On Technology              | 6         | 3.21%   |
| Foxconn / Hon Hai               | 6         | 3.21%   |
| IMC Networks                    | 5         | 2.67%   |
| Dell                            | 4         | 2.14%   |
| MediaTek                        | 3         | 1.6%    |
| Marvell Semiconductor           | 3         | 1.6%    |
| Toshiba                         | 2         | 1.07%   |
| Realtek                         | 1         | 0.53%   |
| Ralink                          | 1         | 0.53%   |
| Dynex                           | 1         | 0.53%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 37        | 19.79%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 17        | 9.09%   |
| Intel AX201 Bluetooth                                                               | 15        | 8.02%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 11        | 5.88%   |
| Realtek Bluetooth Radio                                                             | 10        | 5.35%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 10        | 5.35%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 7         | 3.74%   |
| Intel AX200 Bluetooth                                                               | 6         | 3.21%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 4         | 2.14%   |
| IMC Networks Bluetooth Device                                                       | 4         | 2.14%   |
| Broadcom HP Portable SoftSailing                                                    | 4         | 2.14%   |
| Apple Bluetooth Host Controller                                                     | 4         | 2.14%   |
| MediaTek Wireless_Device                                                            | 3         | 1.6%    |
| Dell DW375 Bluetooth Module                                                         | 3         | 1.6%    |
| Broadcom BCM43142A0 Bluetooth Device                                                | 3         | 1.6%    |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 2         | 1.07%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1.07%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 1.07%   |
| Marvell Bluetooth and Wireless LAN Composite Device                                 | 2         | 1.07%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 2         | 1.07%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 1.07%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 1.07%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 2         | 1.07%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 1.07%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 2         | 1.07%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 2         | 1.07%   |
| Apple Bluetooth USB Host Controller                                                 | 2         | 1.07%   |
| Toshiba BCM43142A0                                                                  | 1         | 0.53%   |
| Toshiba Atheros AR3012 Bluetooth                                                    | 1         | 0.53%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.53%   |
| Realtek 802.11ac WLAN Adapter                                                       | 1         | 0.53%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.53%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.53%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.53%   |
| Qualcomm Atheros Bluetooth                                                          | 1         | 0.53%   |
| Marvell Bluetooth and Wireless LAN Composite                                        | 1         | 0.53%   |
| Lite-On Wireless_Device                                                             | 1         | 0.53%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.53%   |
| Lite-On Bluetooth Radio                                                             | 1         | 0.53%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 0.53%   |
| Intel Bluetooth Device                                                              | 1         | 0.53%   |
| Intel AX210 Bluetooth                                                               | 1         | 0.53%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 0.53%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.53%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth                                       | 1         | 0.53%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]                            | 1         | 0.53%   |
| Dell Broadcom BCM20702A0 Bluetooth                                                  | 1         | 0.53%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 0.53%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 0.53%   |
| Broadcom BCM20702A0                                                                 | 1         | 0.53%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 0.53%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 1         | 0.53%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 208       | 59.43%  |
| AMD                    | 71        | 20.29%  |
| Nvidia                 | 59        | 16.86%  |
| C-Media Electronics    | 4         | 1.14%   |
| Yamaha                 | 1         | 0.29%   |
| SteelSeries ApS        | 1         | 0.29%   |
| Logitech               | 1         | 0.29%   |
| GYROCOM C&C            | 1         | 0.29%   |
| Guillemot              | 1         | 0.29%   |
| GN Netcom              | 1         | 0.29%   |
| Generalplus Technology | 1         | 0.29%   |
| Apple                  | 1         | 0.29%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 28        | 6.47%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 24        | 5.54%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 19        | 4.39%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 15        | 3.46%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 15        | 3.46%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 14        | 3.23%   |
| Intel 8 Series HD Audio Controller                                                                | 14        | 3.23%   |
| AMD FCH Azalia Controller                                                                         | 14        | 3.23%   |
| Intel Cannon Lake PCH cAVS                                                                        | 13        | 3%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 12        | 2.77%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 11        | 2.54%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 11        | 2.54%   |
| Intel Broadwell-U Audio Controller                                                                | 11        | 2.54%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 10        | 2.31%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 10        | 2.31%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 8         | 1.85%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8         | 1.85%   |
| Intel Comet Lake PCH cAVS                                                                         | 7         | 1.62%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 7         | 1.62%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 7         | 1.62%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 7         | 1.62%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 6         | 1.39%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 6         | 1.39%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 1.39%   |
| AMD Kabini HDMI/DP Audio                                                                          | 6         | 1.39%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 6         | 1.39%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 5         | 1.15%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 5         | 1.15%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 5         | 1.15%   |
| AMD High Definition Audio Controller                                                              | 5         | 1.15%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 5         | 1.15%   |
| Nvidia Audio device                                                                               | 4         | 0.92%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 0.92%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 0.92%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 3         | 0.69%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 0.69%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 0.69%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 0.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.69%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 0.69%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3         | 0.69%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 0.69%   |
| Intel 200 Series PCH HD Audio                                                                     | 3         | 0.69%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 3         | 0.69%   |
| AMD Trinity HDMI Audio Controller                                                                 | 3         | 0.69%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3         | 0.69%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 3         | 0.69%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3         | 0.69%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.46%   |
| Nvidia MCP89 High Definition Audio                                                                | 2         | 0.46%   |
| Nvidia MCP61 High Definition Audio                                                                | 2         | 0.46%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 0.46%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.46%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 2         | 0.46%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.46%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 2         | 0.46%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 2         | 0.46%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 2         | 0.46%   |
| Intel USB PnP Sound Device                                                                        | 2         | 0.46%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 0.46%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 54        | 28.13%  |
| SK Hynix            | 31        | 16.15%  |
| Micron Technology   | 25        | 13.02%  |
| Unknown             | 19        | 9.9%    |
| Crucial             | 16        | 8.33%   |
| Kingston            | 13        | 6.77%   |
| Corsair             | 7         | 3.65%   |
| Ramaxel Technology  | 6         | 3.13%   |
| Elpida              | 6         | 3.13%   |
| G.Skill             | 4         | 2.08%   |
| Nanya Technology    | 3         | 1.56%   |
| A-DATA Technology   | 3         | 1.56%   |
| Unknown (ABCD)      | 2         | 1.04%   |
| Team                | 1         | 0.52%   |
| Silicon Power       | 1         | 0.52%   |
| S                   | 1         | 0.52%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s          | 6         | 3%      |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 6         | 3%      |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 3         | 1.5%    |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s         | 3         | 1.5%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s          | 3         | 1.5%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s          | 3         | 1.5%    |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s           | 3         | 1.5%    |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                      | 2         | 1%      |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 2         | 1%      |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM DDR4 2400MT/s | 2         | 1%      |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 2         | 1%      |
| SK Hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s      | 2         | 1%      |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s          | 2         | 1%      |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s          | 2         | 1%      |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s          | 2         | 1%      |
| Samsung RAM M4 70T2953CZ3-CE6 1024MB SODIMM DDR 667MT/s        | 2         | 1%      |
| Micron RAM 4ATF1G64HZ-3G2E1 8192MB Row Of Chips DDR4 3200MT/s  | 2         | 1%      |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s         | 2         | 1%      |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s         | 2         | 1%      |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                     | 2         | 1%      |
| Crucial RAM BLS8G3D1609DS1S00. 8192MB DIMM DDR3 1600MT/s       | 2         | 1%      |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                    | 1         | 0.5%    |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 1         | 0.5%    |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s                   | 1         | 0.5%    |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                    | 1         | 0.5%    |
| Unknown RAM Module 4GB DIMM DDR3 1067MT/s                      | 1         | 0.5%    |
| Unknown RAM Module 4GB DIMM 1600MT/s                           | 1         | 0.5%    |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                 | 1         | 0.5%    |
| Unknown RAM Module 4096MB SODIMM DDR3                          | 1         | 0.5%    |
| Unknown RAM Module 4096MB SODIMM 1066MT/s                      | 1         | 0.5%    |
| Unknown RAM Module 2GB SODIMM DDR3                             | 1         | 0.5%    |
| Unknown RAM Module 2GB DIMM SDRAM                              | 1         | 0.5%    |
| Unknown RAM Module 2GB DIMM                                    | 1         | 0.5%    |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                  | 1         | 0.5%    |
| Unknown RAM Module 2048MB DIMM DDR2 400MT/s                    | 1         | 0.5%    |
| Unknown RAM Module 2048MB DIMM DDR2                            | 1         | 0.5%    |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                     | 1         | 0.5%    |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                  | 1         | 0.5%    |
| Team RAM TEAMGROUP-SD4-2666 16384MB SODIMM DDR4 2667MT/s       | 1         | 0.5%    |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                   | 1         | 0.5%    |
| SK Hynix RAM Module 4096MB SODIMM DDR3 1066MT/s                | 1         | 0.5%    |
| SK Hynix RAM Module 2GB SODIMM DDR3 1600MT/s                   | 1         | 0.5%    |
| SK Hynix RAM Module 2GB SODIMM DDR3 1066MT/s                   | 1         | 0.5%    |
| SK Hynix RAM Module 16GB SODIMM DDR4 3200MT/s                  | 1         | 0.5%    |
| SK Hynix RAM HYMP512U64CP8-Y5 1GB DIMM                         | 1         | 0.5%    |
| SK Hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s            | 1         | 0.5%    |
| SK Hynix RAM HMT851S6AMR6R-PB 4096MB SODIMM DDR3 1600MT/s      | 1         | 0.5%    |
| SK Hynix RAM HMT851S6AMR6A-PB 4GB Chip DDR3 1600MT/s           | 1         | 0.5%    |
| SK Hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 0.5%    |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 0.5%    |
| SK Hynix RAM HMT351S6BFR8C-H9 4096MB SODIMM DDR3 1334MT/s      | 1         | 0.5%    |
| SK Hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s         | 1         | 0.5%    |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s         | 1         | 0.5%    |
| SK Hynix RAM HMA851S6JJR6N-VK 4096MB SODIMM DDR4 2667MT/s      | 1         | 0.5%    |
| SK Hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s         | 1         | 0.5%    |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s   | 1         | 0.5%    |
| SK Hynix RAM HMA82GS6AFR8N-UH 16384MB SODIMM DDR4 2667MT/s     | 1         | 0.5%    |
| SK Hynix RAM HMA81GU6AFR8N-UH 8192MB DIMM DDR4 2400MT/s        | 1         | 0.5%    |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 1         | 0.5%    |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 1         | 0.5%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 69        | 41.57%  |
| DDR3    | 69        | 41.57%  |
| LPDDR4  | 8         | 4.82%   |
| DDR2    | 7         | 4.22%   |
| LPDDR3  | 6         | 3.61%   |
| Unknown | 4         | 2.41%   |
| SDRAM   | 2         | 1.2%    |
| DDR     | 1         | 0.6%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 120       | 73.17%  |
| DIMM         | 31        | 18.9%   |
| Row Of Chips | 11        | 6.71%   |
| Chip         | 1         | 0.61%   |
| Unknown      | 1         | 0.61%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 71        | 39.44%  |
| 8192  | 55        | 30.56%  |
| 16384 | 21        | 11.67%  |
| 2048  | 20        | 11.11%  |
| 1024  | 9         | 5%      |
| 32768 | 4         | 2.22%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 45        | 25.14%  |
| 2667    | 39        | 21.79%  |
| 3200    | 17        | 9.5%    |
| 2400    | 14        | 7.82%   |
| 1334    | 13        | 7.26%   |
| 2133    | 9         | 5.03%   |
| 1333    | 7         | 3.91%   |
| Unknown | 5         | 2.79%   |
| 1867    | 4         | 2.23%   |
| 1067    | 4         | 2.23%   |
| 3600    | 3         | 1.68%   |
| 3266    | 3         | 1.68%   |
| 1066    | 3         | 1.68%   |
| 667     | 3         | 1.68%   |
| 800     | 2         | 1.12%   |
| 4800    | 1         | 0.56%   |
| 4267    | 1         | 0.56%   |
| 3466    | 1         | 0.56%   |
| 2666    | 1         | 0.56%   |
| 2200    | 1         | 0.56%   |
| 1866    | 1         | 0.56%   |
| 533     | 1         | 0.56%   |
| 400     | 1         | 0.56%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 1         | 50%     |
| Brother Industries | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                        | Computers | Percent |
|------------------------------|-----------|---------|
| HP OfficeJet Pro 7720 series | 1         | 50%     |
| Brother HL-1210W series      | 1         | 50%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 55        | 27.78%  |
| Acer                                   | 23        | 11.62%  |
| Microdia                               | 19        | 9.6%    |
| IMC Networks                           | 16        | 8.08%   |
| Sunplus Innovation Technology          | 13        | 6.57%   |
| Realtek Semiconductor                  | 10        | 5.05%   |
| Apple                                  | 8         | 4.04%   |
| Quanta                                 | 7         | 3.54%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 3.03%   |
| Ricoh                                  | 5         | 2.53%   |
| Logitech                               | 4         | 2.02%   |
| Suyin                                  | 3         | 1.52%   |
| Silicon Motion                         | 3         | 1.52%   |
| Samsung Electronics                    | 3         | 1.52%   |
| Luxvisions Innotech Limited            | 3         | 1.52%   |
| Alcor Micro                            | 3         | 1.52%   |
| Syntek                                 | 2         | 1.01%   |
| Microsoft                              | 2         | 1.01%   |
| Lite-On Technology                     | 2         | 1.01%   |
| LG Electronics                         | 2         | 1.01%   |
| Creative Technology                    | 2         | 1.01%   |
| Teslong Camera                         | 1         | 0.51%   |
| Razer USA                              | 1         | 0.51%   |
| Primax Electronics                     | 1         | 0.51%   |
| Jieli Technology                       | 1         | 0.51%   |
| Importek                               | 1         | 0.51%   |
| Goertek Electronics                    | 1         | 0.51%   |
| ALi                                    | 1         | 0.51%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 8         | 4%      |
| Realtek Integrated_Webcam_HD                        | 6         | 3%      |
| Acer HD Webcam                                      | 6         | 3%      |
| Chicony HD Webcam                                   | 5         | 2.5%    |
| Sunplus Integrated_Webcam_HD                        | 4         | 2%      |
| Microdia Webcam Vitade AF                           | 4         | 2%      |
| IMC Networks USB2.0 HD UVC WebCam                   | 4         | 2%      |
| Chicony HP TrueVision HD                            | 4         | 2%      |
| Chicony HD User Facing                              | 4         | 2%      |
| Acer EasyCamera                                     | 4         | 2%      |
| Samsung Galaxy A5 (MTP)                             | 3         | 1.5%    |
| Microdia PC Microscope camera                       | 3         | 1.5%    |
| Microdia Integrated_Webcam_HD                       | 3         | 1.5%    |
| Microdia Integrated Webcam                          | 3         | 1.5%    |
| IMC Networks Integrated Camera                      | 3         | 1.5%    |
| Chicony USB2.0 HD UVC WebCam                        | 3         | 1.5%    |
| Chicony USB2.0 Camera                               | 3         | 1.5%    |
| Chicony EasyCamera                                  | 3         | 1.5%    |
| Apple iPhone 5/5C/5S/6/SE                           | 3         | 1.5%    |
| Alcor Micro SHUNCCM2MP                              | 3         | 1.5%    |
| Acer SunplusIT Integrated Camera                    | 3         | 1.5%    |
| Acer Integrated Camera                              | 3         | 1.5%    |
| Syntek Integrated Camera                            | 2         | 1%      |
| Sunplus HD WebCam                                   | 2         | 1%      |
| Realtek Integrated Webcam                           | 2         | 1%      |
| Quanta HP TrueVision HD Camera                      | 2         | 1%      |
| Microsoft LifeCam Rear                              | 2         | 1%      |
| Microsoft LifeCam Front                             | 2         | 1%      |
| Microdia Laptop_Integrated_Webcam_HD                | 2         | 1%      |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 2         | 1%      |
| Logitech HD Webcam C615                             | 2         | 1%      |
| Lite-On HP Wide Vision HD Camera                    | 2         | 1%      |
| IMC Networks HD Camera                              | 2         | 1%      |
| Creative Live! Cam Sync HD [VF0770]                 | 2         | 1%      |
| Chicony USB2.0 VGA UVC WebCam                       | 2         | 1%      |
| Chicony Integrated HP HD Webcam                     | 2         | 1%      |
| Chicony Integrated Camera (1280x720@30)             | 2         | 1%      |
| Chicony HP HD Webcam [Fixed]                        | 2         | 1%      |
| Chicony HP HD Camera                                | 2         | 1%      |
| Apple FaceTime HD Camera                            | 2         | 1%      |
| Acer Lenovo EasyCamera                              | 2         | 1%      |
| Acer HD Camera                                      | 2         | 1%      |
| Teslong Camera                                      | 1         | 0.5%    |
| Suyin Integrated_Webcam_HD                          | 1         | 0.5%    |
| Suyin HP Truevision HD                              | 1         | 0.5%    |
| Suyin Acer CrystalEye Webcam                        | 1         | 0.5%    |
| Sunplus Laptop_Integrated_Webcam_HD                 | 1         | 0.5%    |
| Sunplus Laptop_Integrated_Webcam_FHD                | 1         | 0.5%    |
| Sunplus Laptop Integrated Webcam FHD                | 1         | 0.5%    |
| Sunplus Integrated Camera                           | 1         | 0.5%    |
| Sunplus HP HD Webcam [Fixed]                        | 1         | 0.5%    |
| Sunplus HK 1080P K20Pro                             | 1         | 0.5%    |
| Sunplus Asus Webcam                                 | 1         | 0.5%    |
| Silicon Motion WebCam SCB-0385N                     | 1         | 0.5%    |
| Silicon Motion WebCam SC-13HDL11939N                | 1         | 0.5%    |
| Silicon Motion WebCam SC-03FFL11939N                | 1         | 0.5%    |
| Ricoh USB2.0 Camera                                 | 1         | 0.5%    |
| Ricoh Pavilion Webcam                               | 1         | 0.5%    |
| Ricoh Laptop_Integrated_Webcam_FHD                  | 1         | 0.5%    |
| Ricoh Integrated Webcam                             | 1         | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 14        | 46.67%  |
| Synaptics                  | 8         | 26.67%  |
| Shenzhen Goodix Technology | 3         | 10%     |
| LighTuning Technology      | 2         | 6.67%   |
| Elan Microelectronics      | 2         | 6.67%   |
| AuthenTec                  | 1         | 3.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 10%     |
| Validity Sensors VFS491                                                    | 2         | 6.67%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 6.67%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 6.67%   |
| Synaptics  WBDI                                                            | 2         | 6.67%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 2         | 6.67%   |
| Shenzhen Goodix  Fingerprint Device                                        | 2         | 6.67%   |
| Elan ELAN:Fingerprint                                                      | 2         | 6.67%   |
| Unknown                                                                    | 2         | 6.67%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 3.33%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 3.33%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 3.33%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 3.33%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 3.33%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 3.33%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 3.33%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 3.33%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 3.33%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 3.33%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 3.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Broadcom         | 8         | 53.33%  |
| Alcor Micro      | 4         | 26.67%  |
| SCM Microsystems | 1         | 6.67%   |
| OmniKey          | 1         | 6.67%   |
| O2 Micro         | 1         | 6.67%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 4         | 26.67%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 13.33%  |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 6.67%   |
| OmniKey CardMan Smart@Link                                                   | 1         | 6.67%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 6.67%   |
| Broadcom 5880                                                                | 1         | 6.67%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 175       | 63.18%  |
| 1     | 83        | 29.96%  |
| 2     | 18        | 6.5%    |
| 3     | 1         | 0.36%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 31        | 26.72%  |
| Net/wireless             | 21        | 18.1%   |
| Graphics card            | 20        | 17.24%  |
| Chipcard                 | 13        | 11.21%  |
| Multimedia controller    | 12        | 10.34%  |
| Camera                   | 7         | 6.03%   |
| Storage                  | 4         | 3.45%   |
| Network                  | 2         | 1.72%   |
| Storage/raid             | 1         | 0.86%   |
| Net/ethernet             | 1         | 0.86%   |
| Modem                    | 1         | 0.86%   |
| Communication controller | 1         | 0.86%   |
| Card reader              | 1         | 0.86%   |
| Bluetooth                | 1         | 0.86%   |

