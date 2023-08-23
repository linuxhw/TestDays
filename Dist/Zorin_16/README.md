Zorin 16 - Tested Hardware & Statistics
---------------------------------------

A project to collect tested hardware configurations for Zorin 16.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Zorin_16/Desktop/README.md) and [notebooks](/Dist/Zorin_16/Notebook/README.md).

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 5057

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad Duet 3 11IAN8 82... | Tablet      | [b61e23d1ec](https://linux-hardware.org/?probe=b61e23d1ec) | Aug 12, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [5ba59f878a](https://linux-hardware.org/?probe=5ba59f878a) | Aug 12, 2023 |
| Acer          | One Z1402                   | Notebook    | [9fd6a2d41b](https://linux-hardware.org/?probe=9fd6a2d41b) | Aug 12, 2023 |
| Biostar       | A770 A2+                    | Desktop     | [d35bac0620](https://linux-hardware.org/?probe=d35bac0620) | Aug 12, 2023 |
| Biostar       | A770 A2+                    | Desktop     | [fb7d0009fd](https://linux-hardware.org/?probe=fb7d0009fd) | Aug 12, 2023 |
| Dell          | 0XKD8M A00                  | All in one  | [6cbd6d691c](https://linux-hardware.org/?probe=6cbd6d691c) | Aug 11, 2023 |
| Unknown       | Unknown                     | Notebook    | [b68d99fd89](https://linux-hardware.org/?probe=b68d99fd89) | Aug 11, 2023 |
| HP            | 3032h                       | Desktop     | [1727f042cd](https://linux-hardware.org/?probe=1727f042cd) | Aug 11, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [48a0f64b34](https://linux-hardware.org/?probe=48a0f64b34) | Aug 11, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [a708832571](https://linux-hardware.org/?probe=a708832571) | Aug 11, 2023 |
| HP            | 350 G2                      | Notebook    | [dde52cb361](https://linux-hardware.org/?probe=dde52cb361) | Aug 10, 2023 |
| Clevo         | W251EFQ/W270EFQ             | Notebook    | [cde80ecaf6](https://linux-hardware.org/?probe=cde80ecaf6) | Aug 10, 2023 |
| Dell          | XPS 13 9365                 | Convertible | [a2756bd55e](https://linux-hardware.org/?probe=a2756bd55e) | Aug 10, 2023 |
| Intel         | DZ68BC AAG30742-401         | Desktop     | [9bf37df045](https://linux-hardware.org/?probe=9bf37df045) | Aug 10, 2023 |
| HP            | ProBook 450 G6              | Notebook    | [c205f19d5e](https://linux-hardware.org/?probe=c205f19d5e) | Aug 09, 2023 |
| HP            | 350 G2                      | Notebook    | [3b79bb8a69](https://linux-hardware.org/?probe=3b79bb8a69) | Aug 09, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [6e9ca3c833](https://linux-hardware.org/?probe=6e9ca3c833) | Aug 09, 2023 |
| HP            | 3032h                       | Desktop     | [03a8cc31ea](https://linux-hardware.org/?probe=03a8cc31ea) | Aug 09, 2023 |
| HP            | Presario CQ56               | Notebook    | [cf373b9083](https://linux-hardware.org/?probe=cf373b9083) | Aug 09, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [6047747c8f](https://linux-hardware.org/?probe=6047747c8f) | Aug 09, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [8a11b56d79](https://linux-hardware.org/?probe=8a11b56d79) | Aug 09, 2023 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [7c59be984f](https://linux-hardware.org/?probe=7c59be984f) | Aug 09, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [03a4763a96](https://linux-hardware.org/?probe=03a4763a96) | Aug 08, 2023 |
| Acidanther... | Mac-AA95B1DDAB278B95 iMa... | All in one  | [9c789edd52](https://linux-hardware.org/?probe=9c789edd52) | Aug 08, 2023 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [2e30c62b25](https://linux-hardware.org/?probe=2e30c62b25) | Aug 08, 2023 |
| Intel         | X79M-S                      | Desktop     | [8250cad3d6](https://linux-hardware.org/?probe=8250cad3d6) | Aug 08, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [de86921bce](https://linux-hardware.org/?probe=de86921bce) | Aug 08, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [c90663d505](https://linux-hardware.org/?probe=c90663d505) | Aug 08, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [965220ce86](https://linux-hardware.org/?probe=965220ce86) | Aug 07, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [87ee840e89](https://linux-hardware.org/?probe=87ee840e89) | Aug 07, 2023 |
| LG Electro... | 14Z90N-V.AA78B              | Notebook    | [af79c7f5f5](https://linux-hardware.org/?probe=af79c7f5f5) | Aug 07, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [72a4a0eed2](https://linux-hardware.org/?probe=72a4a0eed2) | Aug 06, 2023 |
| ASUSTek       | X405UA                      | Notebook    | [97acf73dea](https://linux-hardware.org/?probe=97acf73dea) | Aug 06, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [c95daf7007](https://linux-hardware.org/?probe=c95daf7007) | Aug 06, 2023 |
| Pegatron      | IPMMB-MQ1                   | Desktop     | [70c450c395](https://linux-hardware.org/?probe=70c450c395) | Aug 06, 2023 |
| MSI           | Z170A GAMING PRO CARBON     | Desktop     | [6b22ae1f36](https://linux-hardware.org/?probe=6b22ae1f36) | Aug 06, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [c40308638c](https://linux-hardware.org/?probe=c40308638c) | Aug 05, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [1af709c14e](https://linux-hardware.org/?probe=1af709c14e) | Aug 05, 2023 |
| Gigabyte      | Z97X-UD5H                   | Desktop     | [3bc330734d](https://linux-hardware.org/?probe=3bc330734d) | Aug 05, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [3b5e9f52a2](https://linux-hardware.org/?probe=3b5e9f52a2) | Aug 05, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | Notebook    | [8b6db0bfbb](https://linux-hardware.org/?probe=8b6db0bfbb) | Aug 05, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | Desktop     | [5d998a099e](https://linux-hardware.org/?probe=5d998a099e) | Aug 05, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | Desktop     | [e57d71e056](https://linux-hardware.org/?probe=e57d71e056) | Aug 05, 2023 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [dbbf788e9d](https://linux-hardware.org/?probe=dbbf788e9d) | Aug 05, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [5f0be846f0](https://linux-hardware.org/?probe=5f0be846f0) | Aug 05, 2023 |
| Dell          | Venue 11 Pro 7140           | Notebook    | [7188a418fc](https://linux-hardware.org/?probe=7188a418fc) | Aug 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [8ee9cccace](https://linux-hardware.org/?probe=8ee9cccace) | Aug 05, 2023 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [7ffb6822e6](https://linux-hardware.org/?probe=7ffb6822e6) | Aug 05, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [db336dcf75](https://linux-hardware.org/?probe=db336dcf75) | Aug 05, 2023 |
| Itautec       | Infoway                     | Notebook    | [1708f5baae](https://linux-hardware.org/?probe=1708f5baae) | Aug 04, 2023 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [3793d876eb](https://linux-hardware.org/?probe=3793d876eb) | Aug 04, 2023 |
| GPD           | G1621-02                    | Notebook    | [d7361e9896](https://linux-hardware.org/?probe=d7361e9896) | Aug 04, 2023 |
| Apple         | MacBook8,1                  | Notebook    | [cf6d77d650](https://linux-hardware.org/?probe=cf6d77d650) | Aug 04, 2023 |
| Lenovo        | Gardenia CRB SDK0J40700 ... | All in one  | [9f27152a86](https://linux-hardware.org/?probe=9f27152a86) | Aug 04, 2023 |
| Dell          | Latitude 7490               | Notebook    | [955c961132](https://linux-hardware.org/?probe=955c961132) | Aug 04, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [61cb65a2e9](https://linux-hardware.org/?probe=61cb65a2e9) | Aug 04, 2023 |
| Dell          | Inspiron 3531               | Notebook    | [f011e5c6cf](https://linux-hardware.org/?probe=f011e5c6cf) | Aug 03, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [f27f9b2a7f](https://linux-hardware.org/?probe=f27f9b2a7f) | Aug 03, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [8193f810ab](https://linux-hardware.org/?probe=8193f810ab) | Aug 03, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [35cf0fd859](https://linux-hardware.org/?probe=35cf0fd859) | Aug 03, 2023 |
| Intel         | X79M-S                      | Desktop     | [5a4d94f325](https://linux-hardware.org/?probe=5a4d94f325) | Aug 02, 2023 |
| Notebook      | NJ50_70CU                   | Notebook    | [59cd10f50e](https://linux-hardware.org/?probe=59cd10f50e) | Aug 02, 2023 |
| HP            | 89B5 A                      | Desktop     | [cb6f36f32c](https://linux-hardware.org/?probe=cb6f36f32c) | Aug 02, 2023 |
| Acer          | Aspire M3-581G              | Notebook    | [82814fbe1e](https://linux-hardware.org/?probe=82814fbe1e) | Aug 02, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [37fe1d55f8](https://linux-hardware.org/?probe=37fe1d55f8) | Aug 02, 2023 |
| HP            | Pavilion dv7                | Notebook    | [bd9bc8e7a6](https://linux-hardware.org/?probe=bd9bc8e7a6) | Aug 02, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [ee5b34b232](https://linux-hardware.org/?probe=ee5b34b232) | Aug 02, 2023 |
| ASUSTek       | K54C                        | Notebook    | [f4fcf79e7e](https://linux-hardware.org/?probe=f4fcf79e7e) | Aug 02, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [cfce53f1a3](https://linux-hardware.org/?probe=cfce53f1a3) | Aug 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [731a8b0e31](https://linux-hardware.org/?probe=731a8b0e31) | Aug 02, 2023 |
| Dell          | Inspiron 5577               | Notebook    | [1204832e26](https://linux-hardware.org/?probe=1204832e26) | Aug 01, 2023 |
| Dell          | Inspiron 5577               | Notebook    | [219723a17d](https://linux-hardware.org/?probe=219723a17d) | Aug 01, 2023 |
| Dell          | Latitude E5470              | Notebook    | [3be826cec4](https://linux-hardware.org/?probe=3be826cec4) | Aug 01, 2023 |
| AZW           | GTR V01                     | Mini pc     | [f3f9a4366b](https://linux-hardware.org/?probe=f3f9a4366b) | Aug 01, 2023 |
| HP            | Stream Laptop 14-cb1XX      | Notebook    | [957e1805d3](https://linux-hardware.org/?probe=957e1805d3) | Aug 01, 2023 |
| HP            | Stream Laptop 14-cb1XX      | Notebook    | [a522e7336c](https://linux-hardware.org/?probe=a522e7336c) | Aug 01, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [287740b630](https://linux-hardware.org/?probe=287740b630) | Aug 01, 2023 |
| HP            | 1496                        | Desktop     | [24863488f0](https://linux-hardware.org/?probe=24863488f0) | Aug 01, 2023 |
| MSI           | GE72MVR 7RG                 | Notebook    | [d935650def](https://linux-hardware.org/?probe=d935650def) | Jul 31, 2023 |
| Dell          | Inspiron 3421               | Notebook    | [d1651e3e43](https://linux-hardware.org/?probe=d1651e3e43) | Jul 31, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [d4efd6692b](https://linux-hardware.org/?probe=d4efd6692b) | Jul 30, 2023 |
| Apple         | MacBookPro4,1               | Notebook    | [eedbe7eb59](https://linux-hardware.org/?probe=eedbe7eb59) | Jul 30, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [1a77aeef9d](https://linux-hardware.org/?probe=1a77aeef9d) | Jul 30, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [a6e35103c8](https://linux-hardware.org/?probe=a6e35103c8) | Jul 30, 2023 |
| Sony          | VPCF13Z1E                   | Notebook    | [e52969e6a8](https://linux-hardware.org/?probe=e52969e6a8) | Jul 30, 2023 |
| ASUSTek       | M4N68T-M LE                 | Desktop     | [90dce7a9cf](https://linux-hardware.org/?probe=90dce7a9cf) | Jul 30, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [0ce1be51b9](https://linux-hardware.org/?probe=0ce1be51b9) | Jul 30, 2023 |
| MSI           | GS73VR 7RF                  | Notebook    | [9df7170f38](https://linux-hardware.org/?probe=9df7170f38) | Jul 29, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [b1125cd76c](https://linux-hardware.org/?probe=b1125cd76c) | Jul 29, 2023 |
| HP            | Pavilion dv4                | Notebook    | [47e9cba85c](https://linux-hardware.org/?probe=47e9cba85c) | Jul 29, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [472c0bf0b0](https://linux-hardware.org/?probe=472c0bf0b0) | Jul 29, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [2da43364f8](https://linux-hardware.org/?probe=2da43364f8) | Jul 29, 2023 |
| ASUSTek       | K53U                        | Notebook    | [c1b84117db](https://linux-hardware.org/?probe=c1b84117db) | Jul 29, 2023 |
| HP            | Pavilion 15                 | Notebook    | [df29d1164c](https://linux-hardware.org/?probe=df29d1164c) | Jul 29, 2023 |
| HP            | Pavilion 15                 | Notebook    | [804d28484b](https://linux-hardware.org/?probe=804d28484b) | Jul 29, 2023 |
| ASUSTek       | H97-PRO GAMER               | Desktop     | [1771e4ca4b](https://linux-hardware.org/?probe=1771e4ca4b) | Jul 29, 2023 |
| ASUSTek       | H97-PRO GAMER               | Desktop     | [e668b29cf4](https://linux-hardware.org/?probe=e668b29cf4) | Jul 29, 2023 |
| HP            | ZBook 15 G5                 | Notebook    | [dfe51162d1](https://linux-hardware.org/?probe=dfe51162d1) | Jul 29, 2023 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [bc92202f16](https://linux-hardware.org/?probe=bc92202f16) | Jul 29, 2023 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | Desktop     | [8c930cc5e4](https://linux-hardware.org/?probe=8c930cc5e4) | Jul 29, 2023 |
| HP            | Pavilion g7                 | Notebook    | [18eb2a894b](https://linux-hardware.org/?probe=18eb2a894b) | Jul 29, 2023 |
| MSI           | B75MA-E33                   | Desktop     | [310207e0fd](https://linux-hardware.org/?probe=310207e0fd) | Jul 29, 2023 |
| HP            | ZBook 15 G5                 | Notebook    | [8996d2d4fd](https://linux-hardware.org/?probe=8996d2d4fd) | Jul 28, 2023 |
| Microsoft     | Surface 3                   | Tablet      | [7583695051](https://linux-hardware.org/?probe=7583695051) | Jul 28, 2023 |
| Microsoft     | Surface 3                   | Tablet      | [fe7c4fd681](https://linux-hardware.org/?probe=fe7c4fd681) | Jul 28, 2023 |
| Google        | Edgar                       | Notebook    | [7e19b1e507](https://linux-hardware.org/?probe=7e19b1e507) | Jul 28, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [7e30723b3b](https://linux-hardware.org/?probe=7e30723b3b) | Jul 28, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [9e892612ab](https://linux-hardware.org/?probe=9e892612ab) | Jul 28, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [4d413cb864](https://linux-hardware.org/?probe=4d413cb864) | Jul 28, 2023 |
| HP            | 3397                        | Desktop     | [e61ccd6dbf](https://linux-hardware.org/?probe=e61ccd6dbf) | Jul 27, 2023 |
| HP            | EliteBook 8560p             | Notebook    | [b7ce548e5b](https://linux-hardware.org/?probe=b7ce548e5b) | Jul 27, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [e7fdf45ff0](https://linux-hardware.org/?probe=e7fdf45ff0) | Jul 27, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [2f12124bed](https://linux-hardware.org/?probe=2f12124bed) | Jul 27, 2023 |
| Sony          | VPCF13Z1E                   | Notebook    | [5022f7359c](https://linux-hardware.org/?probe=5022f7359c) | Jul 26, 2023 |
| MP            | MS-7848                     | Desktop     | [3dd9f22548](https://linux-hardware.org/?probe=3dd9f22548) | Jul 26, 2023 |
| Intel         | NUC13ANBi7 M89645-203       | Mini pc     | [238c98ee81](https://linux-hardware.org/?probe=238c98ee81) | Jul 26, 2023 |
| Lenovo        | No DPK                      | All in one  | [1b1fa8ccec](https://linux-hardware.org/?probe=1b1fa8ccec) | Jul 26, 2023 |
| Acer          | Elena                       | Desktop     | [78eff851f2](https://linux-hardware.org/?probe=78eff851f2) | Jul 26, 2023 |
| ASRock        | Z97M Pro4                   | Desktop     | [1b062f3c31](https://linux-hardware.org/?probe=1b062f3c31) | Jul 26, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [45bc8cd978](https://linux-hardware.org/?probe=45bc8cd978) | Jul 26, 2023 |
| ASRock        | Z97M Pro4                   | Desktop     | [bca4424b5d](https://linux-hardware.org/?probe=bca4424b5d) | Jul 26, 2023 |
| ASUSTek       | B250 MINING EXPERT          | Desktop     | [0236b3ce26](https://linux-hardware.org/?probe=0236b3ce26) | Jul 26, 2023 |
| Sony          | VPCF13Z1E                   | Notebook    | [f5290b8791](https://linux-hardware.org/?probe=f5290b8791) | Jul 25, 2023 |
| Sony          | VPCF13Z1E                   | Notebook    | [99aacf2d95](https://linux-hardware.org/?probe=99aacf2d95) | Jul 25, 2023 |
| Dell          | 088DT1 A01                  | Desktop     | [1355a4f2f4](https://linux-hardware.org/?probe=1355a4f2f4) | Jul 25, 2023 |
| Acer          | TravelMate B113             | Notebook    | [b6fdce48b3](https://linux-hardware.org/?probe=b6fdce48b3) | Jul 25, 2023 |
| Toshiba       | QOSMIO X770                 | Notebook    | [7eda84257a](https://linux-hardware.org/?probe=7eda84257a) | Jul 25, 2023 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [47fec524e4](https://linux-hardware.org/?probe=47fec524e4) | Jul 25, 2023 |
| Dell          | Inspiron 3721               | Notebook    | [a0874e626b](https://linux-hardware.org/?probe=a0874e626b) | Jul 24, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [431abc64d1](https://linux-hardware.org/?probe=431abc64d1) | Jul 24, 2023 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [c16c981a88](https://linux-hardware.org/?probe=c16c981a88) | Jul 24, 2023 |
| Lenovo        | ThinkPad E15 20RD0011GE     | Notebook    | [8ca6d932b3](https://linux-hardware.org/?probe=8ca6d932b3) | Jul 24, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [35d95135f4](https://linux-hardware.org/?probe=35d95135f4) | Jul 23, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [de254aad44](https://linux-hardware.org/?probe=de254aad44) | Jul 23, 2023 |
| Microtech     | ebookPro                    | Notebook    | [4427543f1a](https://linux-hardware.org/?probe=4427543f1a) | Jul 23, 2023 |
| HP            | 8350                        | Desktop     | [f17382c501](https://linux-hardware.org/?probe=f17382c501) | Jul 23, 2023 |
| Dell          | Latitude E6400              | Notebook    | [77a598aa4d](https://linux-hardware.org/?probe=77a598aa4d) | Jul 23, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [13bb65f561](https://linux-hardware.org/?probe=13bb65f561) | Jul 23, 2023 |
| Acer          | AO756                       | Notebook    | [23e3fc369f](https://linux-hardware.org/?probe=23e3fc369f) | Jul 23, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [c271fa70b8](https://linux-hardware.org/?probe=c271fa70b8) | Jul 23, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [19356a725e](https://linux-hardware.org/?probe=19356a725e) | Jul 22, 2023 |
| HP            | Pavilion dv4                | Notebook    | [4854c4b18c](https://linux-hardware.org/?probe=4854c4b18c) | Jul 22, 2023 |
| Dell          | 0MN1TX A04                  | Desktop     | [4ff31f4185](https://linux-hardware.org/?probe=4ff31f4185) | Jul 22, 2023 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [b8cf03e7b7](https://linux-hardware.org/?probe=b8cf03e7b7) | Jul 22, 2023 |
| HP            | EliteBook 820 G4            | Notebook    | [3051483589](https://linux-hardware.org/?probe=3051483589) | Jul 22, 2023 |
| ASUSTek       | F1A55-M LX                  | Desktop     | [87b85c2e28](https://linux-hardware.org/?probe=87b85c2e28) | Jul 22, 2023 |
| Medion        | E15301                      | Notebook    | [e20403ff58](https://linux-hardware.org/?probe=e20403ff58) | Jul 22, 2023 |
| Toshiba       | Satellite L50-B             | Notebook    | [5e7da1cf33](https://linux-hardware.org/?probe=5e7da1cf33) | Jul 22, 2023 |
| ASRock        | B85M                        | Desktop     | [c4f0b0b1fa](https://linux-hardware.org/?probe=c4f0b0b1fa) | Jul 22, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [306d51185f](https://linux-hardware.org/?probe=306d51185f) | Jul 21, 2023 |
| AMI           | Cherry Trail CR             | Notebook    | [42d75ac45a](https://linux-hardware.org/?probe=42d75ac45a) | Jul 21, 2023 |
| HP            | EliteBook 820 G4            | Notebook    | [c85c21d42e](https://linux-hardware.org/?probe=c85c21d42e) | Jul 21, 2023 |
| HP            | 3048h                       | Desktop     | [1be902df43](https://linux-hardware.org/?probe=1be902df43) | Jul 21, 2023 |
| Dell          | Latitude E6440              | Notebook    | [b60d8ab453](https://linux-hardware.org/?probe=b60d8ab453) | Jul 21, 2023 |
| HP            | 3047h                       | Desktop     | [07de35877b](https://linux-hardware.org/?probe=07de35877b) | Jul 21, 2023 |
| Gigabyte      | Z170XP-SLI-CF               | Desktop     | [9afd0f1d0f](https://linux-hardware.org/?probe=9afd0f1d0f) | Jul 21, 2023 |
| Dell          | Latitude 3520               | Notebook    | [7037e164fd](https://linux-hardware.org/?probe=7037e164fd) | Jul 20, 2023 |
| HP            | 15                          | Notebook    | [36b4035b57](https://linux-hardware.org/?probe=36b4035b57) | Jul 20, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [35c4e6ad97](https://linux-hardware.org/?probe=35c4e6ad97) | Jul 20, 2023 |
| HP            | 8767 A                      | Desktop     | [d5275f1025](https://linux-hardware.org/?probe=d5275f1025) | Jul 20, 2023 |
| Dell          | 0F5C5X A00                  | Desktop     | [3832c8f626](https://linux-hardware.org/?probe=3832c8f626) | Jul 20, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [71f9656ab2](https://linux-hardware.org/?probe=71f9656ab2) | Jul 19, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [854bbb5dee](https://linux-hardware.org/?probe=854bbb5dee) | Jul 19, 2023 |
| HP            | 15                          | Notebook    | [0eeb522bec](https://linux-hardware.org/?probe=0eeb522bec) | Jul 19, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [205b94b373](https://linux-hardware.org/?probe=205b94b373) | Jul 19, 2023 |
| Dell          | 0C27VV A02                  | Desktop     | [da1c963814](https://linux-hardware.org/?probe=da1c963814) | Jul 19, 2023 |
| Dell          | 0C27VV A02                  | Desktop     | [02008985ce](https://linux-hardware.org/?probe=02008985ce) | Jul 19, 2023 |
| Sony          | VPCEE23FX                   | Notebook    | [2cb9bf9d50](https://linux-hardware.org/?probe=2cb9bf9d50) | Jul 18, 2023 |
| SONIQ Digi... | Soniq 11.6inch Convertib... | Convertible | [8e01cf8f1e](https://linux-hardware.org/?probe=8e01cf8f1e) | Jul 17, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [9be017a8a3](https://linux-hardware.org/?probe=9be017a8a3) | Jul 16, 2023 |
| Dell          | Inspiron 3421               | Notebook    | [71c4faf60f](https://linux-hardware.org/?probe=71c4faf60f) | Jul 16, 2023 |
| Dell          | Inspiron 5537               | Notebook    | [428df654fb](https://linux-hardware.org/?probe=428df654fb) | Jul 16, 2023 |
| Dell          | 04075X A00                  | All in one  | [46795bfa31](https://linux-hardware.org/?probe=46795bfa31) | Jul 16, 2023 |
| Dell          | Inspiron 3531               | Notebook    | [0e7f83761f](https://linux-hardware.org/?probe=0e7f83761f) | Jul 15, 2023 |
| Dell          | Inspiron 3531               | Notebook    | [d73dcbb938](https://linux-hardware.org/?probe=d73dcbb938) | Jul 15, 2023 |
| Intel         | NUC8BEB J72688-307          | Mini pc     | [21bef8253a](https://linux-hardware.org/?probe=21bef8253a) | Jul 15, 2023 |
| Dell          | Latitude E4300              | Notebook    | [a9e8fb7884](https://linux-hardware.org/?probe=a9e8fb7884) | Jul 15, 2023 |
| Unknown       | SLR-0308                    | Notebook    | [8626e36716](https://linux-hardware.org/?probe=8626e36716) | Jul 15, 2023 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [57b17e7ae1](https://linux-hardware.org/?probe=57b17e7ae1) | Jul 15, 2023 |
| Gigabyte      | Z370M AORUS Gaming-CF       | Desktop     | [64a0d52846](https://linux-hardware.org/?probe=64a0d52846) | Jul 15, 2023 |
| Lenovo        | ThinkPad 10 2nd 20E4S0JA... | Tablet      | [d32668cf0c](https://linux-hardware.org/?probe=d32668cf0c) | Jul 15, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [2f5c2842c2](https://linux-hardware.org/?probe=2f5c2842c2) | Jul 14, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [4155214585](https://linux-hardware.org/?probe=4155214585) | Jul 14, 2023 |
| Alienware     | M11xR3                      | Notebook    | [9397339221](https://linux-hardware.org/?probe=9397339221) | Jul 14, 2023 |
| HUAWEI        | RLEF-XX                     | Notebook    | [23793e7d9c](https://linux-hardware.org/?probe=23793e7d9c) | Jul 14, 2023 |
| Dell          | 0FDY5C A00                  | Desktop     | [35399aae18](https://linux-hardware.org/?probe=35399aae18) | Jul 14, 2023 |
| Dell          | 0D441T A03                  | Desktop     | [622890c12a](https://linux-hardware.org/?probe=622890c12a) | Jul 14, 2023 |
| AZW           | SER                         | Mini pc     | [8fdb4e6f42](https://linux-hardware.org/?probe=8fdb4e6f42) | Jul 14, 2023 |
| AZW           | SER                         | Mini pc     | [537e7c9c94](https://linux-hardware.org/?probe=537e7c9c94) | Jul 13, 2023 |
| HP            | 15                          | Notebook    | [215a87518e](https://linux-hardware.org/?probe=215a87518e) | Jul 13, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [34fe8ff1ad](https://linux-hardware.org/?probe=34fe8ff1ad) | Jul 13, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [a3d301a82a](https://linux-hardware.org/?probe=a3d301a82a) | Jul 13, 2023 |
| Lenovo        | IdeaPad Creator 5 15IMH0... | Notebook    | [56093a48aa](https://linux-hardware.org/?probe=56093a48aa) | Jul 13, 2023 |
| HP            | Pavilion dv7                | Notebook    | [b2e0e73adc](https://linux-hardware.org/?probe=b2e0e73adc) | Jul 13, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [81f693b5b0](https://linux-hardware.org/?probe=81f693b5b0) | Jul 12, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [b690698c10](https://linux-hardware.org/?probe=b690698c10) | Jul 12, 2023 |
| Dell          | Inspiron 3421               | Notebook    | [d347a1b82e](https://linux-hardware.org/?probe=d347a1b82e) | Jul 12, 2023 |
| Lenovo        | ThinkPad 8 20BN001RMN       | Tablet      | [6801265f9f](https://linux-hardware.org/?probe=6801265f9f) | Jul 12, 2023 |
| HP            | 8299                        | Desktop     | [763cebf303](https://linux-hardware.org/?probe=763cebf303) | Jul 12, 2023 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [bae54aa498](https://linux-hardware.org/?probe=bae54aa498) | Jul 12, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [7190b16550](https://linux-hardware.org/?probe=7190b16550) | Jul 12, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [7c6ad4407b](https://linux-hardware.org/?probe=7c6ad4407b) | Jul 11, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | Notebook    | [052461ef4d](https://linux-hardware.org/?probe=052461ef4d) | Jul 11, 2023 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [c81c5855d4](https://linux-hardware.org/?probe=c81c5855d4) | Jul 11, 2023 |
| HP            | Compaq 2510p                | Notebook    | [a7cb1d43fb](https://linux-hardware.org/?probe=a7cb1d43fb) | Jul 11, 2023 |
| HP            | Pavilion g4                 | Notebook    | [6e76f09416](https://linux-hardware.org/?probe=6e76f09416) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [ecc4006807](https://linux-hardware.org/?probe=ecc4006807) | Jul 11, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [ab81f36697](https://linux-hardware.org/?probe=ab81f36697) | Jul 11, 2023 |
| HP            | ProBook 450 G6              | Notebook    | [8e5774c497](https://linux-hardware.org/?probe=8e5774c497) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [2c690e981a](https://linux-hardware.org/?probe=2c690e981a) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [732d09609d](https://linux-hardware.org/?probe=732d09609d) | Jul 10, 2023 |
| Dell          | 09WH54 A00                  | Desktop     | [b118891f3d](https://linux-hardware.org/?probe=b118891f3d) | Jul 10, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [08770a11c6](https://linux-hardware.org/?probe=08770a11c6) | Jul 10, 2023 |
| ASRock        | B460M Pro4                  | Desktop     | [c972293107](https://linux-hardware.org/?probe=c972293107) | Jul 10, 2023 |
| HP            | Compaq 2510p                | Notebook    | [98d500c68c](https://linux-hardware.org/?probe=98d500c68c) | Jul 10, 2023 |
| Lenovo        | ThinkPad Yoga 260 20FES3... | Notebook    | [621eaf410c](https://linux-hardware.org/?probe=621eaf410c) | Jul 10, 2023 |
| Lenovo        | ThinkPad Yoga 260 20FES3... | Notebook    | [3631291aa8](https://linux-hardware.org/?probe=3631291aa8) | Jul 10, 2023 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [2ed1092e31](https://linux-hardware.org/?probe=2ed1092e31) | Jul 10, 2023 |
| Lenovo        | ThinkPad 10 2nd 20E4S0JA... | Tablet      | [6eb4d71389](https://linux-hardware.org/?probe=6eb4d71389) | Jul 10, 2023 |
| HP            | Notebook                    | Notebook    | [7d4bc75f38](https://linux-hardware.org/?probe=7d4bc75f38) | Jul 09, 2023 |
| ASUSTek       | K54C                        | Notebook    | [3f0ca5ad18](https://linux-hardware.org/?probe=3f0ca5ad18) | Jul 09, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [213c80bbee](https://linux-hardware.org/?probe=213c80bbee) | Jul 09, 2023 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [938e9efd55](https://linux-hardware.org/?probe=938e9efd55) | Jul 09, 2023 |
| Unknown       | SLR-0308                    | Notebook    | [d5b0d30e8d](https://linux-hardware.org/?probe=d5b0d30e8d) | Jul 09, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [e6693c16ff](https://linux-hardware.org/?probe=e6693c16ff) | Jul 09, 2023 |
| Dell          | Latitude E5470              | Notebook    | [e04195b0f7](https://linux-hardware.org/?probe=e04195b0f7) | Jul 08, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [be65f2aa45](https://linux-hardware.org/?probe=be65f2aa45) | Jul 08, 2023 |
| OTVOC         | N1                          | Notebook    | [1b4d619110](https://linux-hardware.org/?probe=1b4d619110) | Jul 07, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [2d342d7a37](https://linux-hardware.org/?probe=2d342d7a37) | Jul 07, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [7b62ed78d1](https://linux-hardware.org/?probe=7b62ed78d1) | Jul 07, 2023 |
| Toshiba       | Satellite L670              | Notebook    | [fdc3192779](https://linux-hardware.org/?probe=fdc3192779) | Jul 06, 2023 |
| Lenovo        | Legion Y7000P-1060 81LF     | Notebook    | [203ffa97b4](https://linux-hardware.org/?probe=203ffa97b4) | Jul 06, 2023 |
| Dell          | 0HN7XN A01                  | Desktop     | [24a4044173](https://linux-hardware.org/?probe=24a4044173) | Jul 06, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [8a9c93e501](https://linux-hardware.org/?probe=8a9c93e501) | Jul 06, 2023 |
| Toshiba       | Satellite L670              | Notebook    | [1db76edeb5](https://linux-hardware.org/?probe=1db76edeb5) | Jul 06, 2023 |
| Dell          | 0GFYJR A00                  | Server      | [573c8bd5bd](https://linux-hardware.org/?probe=573c8bd5bd) | Jul 06, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [854ca6ff4f](https://linux-hardware.org/?probe=854ca6ff4f) | Jul 06, 2023 |
| ASUSTek       | ZenBook UX482EG_UX482EG     | Notebook    | [774ebec1d8](https://linux-hardware.org/?probe=774ebec1d8) | Jul 05, 2023 |
| ASRock        | FP6D4-P1                    | Desktop     | [42b5bdcdd7](https://linux-hardware.org/?probe=42b5bdcdd7) | Jul 05, 2023 |
| Positivo      | POS-EIH61CE SIM             | Desktop     | [48b35c757d](https://linux-hardware.org/?probe=48b35c757d) | Jul 05, 2023 |
| Intel         | H55                         | Desktop     | [8f8ff68380](https://linux-hardware.org/?probe=8f8ff68380) | Jul 04, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | Desktop     | [9bca67bb40](https://linux-hardware.org/?probe=9bca67bb40) | Jul 04, 2023 |
| HP            | EliteBook 820 G4            | Notebook    | [58ced183c2](https://linux-hardware.org/?probe=58ced183c2) | Jul 04, 2023 |
| HP            | 21F5 0A                     | Desktop     | [bc7304ba1c](https://linux-hardware.org/?probe=bc7304ba1c) | Jul 04, 2023 |
| HP            | 2B3E                        | All in one  | [bfa310e490](https://linux-hardware.org/?probe=bfa310e490) | Jul 04, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [452fe27c46](https://linux-hardware.org/?probe=452fe27c46) | Jul 04, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [168d5b0b7b](https://linux-hardware.org/?probe=168d5b0b7b) | Jul 04, 2023 |
| Foxconn       | G41S/G41S-K                 | Desktop     | [21adb87fbd](https://linux-hardware.org/?probe=21adb87fbd) | Jul 04, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [7672f159bf](https://linux-hardware.org/?probe=7672f159bf) | Jul 03, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [d3aeb3e580](https://linux-hardware.org/?probe=d3aeb3e580) | Jul 03, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [c073941827](https://linux-hardware.org/?probe=c073941827) | Jul 03, 2023 |
| HP            | 2B3E                        | All in one  | [c6f01baa52](https://linux-hardware.org/?probe=c6f01baa52) | Jul 03, 2023 |
| OTVOC         | N1                          | Notebook    | [833ed0c86b](https://linux-hardware.org/?probe=833ed0c86b) | Jul 02, 2023 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [729dbec695](https://linux-hardware.org/?probe=729dbec695) | Jul 02, 2023 |
| HP            | ENVY m6                     | Notebook    | [748e336af0](https://linux-hardware.org/?probe=748e336af0) | Jul 02, 2023 |
| MSI           | MS-B9181                    | Desktop     | [fef890b931](https://linux-hardware.org/?probe=fef890b931) | Jul 02, 2023 |
| MSI           | MS-B9181                    | Desktop     | [47b3ce0c58](https://linux-hardware.org/?probe=47b3ce0c58) | Jul 02, 2023 |
| MSI           | PRO Z690-A WIFI             | Desktop     | [2bc4b36c94](https://linux-hardware.org/?probe=2bc4b36c94) | Jul 02, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS AC    | Desktop     | [c787bf91c3](https://linux-hardware.org/?probe=c787bf91c3) | Jul 02, 2023 |
| Unknown       | V00                         | Mini pc     | [ab56e54ced](https://linux-hardware.org/?probe=ab56e54ced) | Jul 01, 2023 |
| Unknown       | V00                         | Mini pc     | [36483eddb0](https://linux-hardware.org/?probe=36483eddb0) | Jul 01, 2023 |
| HP            | Compaq 6830s                | Notebook    | [9a777f4318](https://linux-hardware.org/?probe=9a777f4318) | Jul 01, 2023 |
| TrekStor      | YOURBOOK C11B               | Convertible | [8c2340f01f](https://linux-hardware.org/?probe=8c2340f01f) | Jul 01, 2023 |
| Win Elemen... | M9                          | Desktop     | [2e5ea821f1](https://linux-hardware.org/?probe=2e5ea821f1) | Jul 01, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS AC    | Desktop     | [a4e29f77e5](https://linux-hardware.org/?probe=a4e29f77e5) | Jul 01, 2023 |
| Dell          | Latitude E6400              | Notebook    | [c8f88ff5b6](https://linux-hardware.org/?probe=c8f88ff5b6) | Jun 30, 2023 |
| HP            | Pro x2 612 G2               | Tablet      | [e47898dc3d](https://linux-hardware.org/?probe=e47898dc3d) | Jun 29, 2023 |
| MSI           | H61M-P31                    | Desktop     | [9012219f61](https://linux-hardware.org/?probe=9012219f61) | Jun 29, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [bb1cb1ef13](https://linux-hardware.org/?probe=bb1cb1ef13) | Jun 29, 2023 |
| Gigabyte      | P31-DS3L                    | Desktop     | [0d32728bdf](https://linux-hardware.org/?probe=0d32728bdf) | Jun 28, 2023 |
| Acer          | Aspire 5738                 | Notebook    | [b4fcb0d0c0](https://linux-hardware.org/?probe=b4fcb0d0c0) | Jun 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | Notebook    | [9d6748ef56](https://linux-hardware.org/?probe=9d6748ef56) | Jun 28, 2023 |
| HP            | ENVY m6                     | Notebook    | [715d68bfc0](https://linux-hardware.org/?probe=715d68bfc0) | Jun 28, 2023 |
| Dell          | Latitude E6400              | Notebook    | [0f9255924f](https://linux-hardware.org/?probe=0f9255924f) | Jun 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | Notebook    | [64433a8783](https://linux-hardware.org/?probe=64433a8783) | Jun 27, 2023 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [663ce69f30](https://linux-hardware.org/?probe=663ce69f30) | Jun 27, 2023 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [73eab89788](https://linux-hardware.org/?probe=73eab89788) | Jun 27, 2023 |
| Lenovo        | V110-15IKB 80TH             | Notebook    | [e6b9f96475](https://linux-hardware.org/?probe=e6b9f96475) | Jun 27, 2023 |
| HP            | Pavilion dv6700             | Notebook    | [182bf6e4a7](https://linux-hardware.org/?probe=182bf6e4a7) | Jun 27, 2023 |
| Lenovo        | ThinkPad Yoga 11e 20DA50... | Notebook    | [b756e54029](https://linux-hardware.org/?probe=b756e54029) | Jun 27, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [0a35c3c750](https://linux-hardware.org/?probe=0a35c3c750) | Jun 27, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [18ab778722](https://linux-hardware.org/?probe=18ab778722) | Jun 26, 2023 |
| Dell          | XPS 13 9365                 | Convertible | [da86501858](https://linux-hardware.org/?probe=da86501858) | Jun 26, 2023 |
| Dell          | Latitude 3189               | Notebook    | [ad7c98c905](https://linux-hardware.org/?probe=ad7c98c905) | Jun 26, 2023 |
| Dell          | Latitude 3189               | Notebook    | [8547503af5](https://linux-hardware.org/?probe=8547503af5) | Jun 25, 2023 |
| Dell          | Latitude 3189               | Notebook    | [3f44430a36](https://linux-hardware.org/?probe=3f44430a36) | Jun 25, 2023 |
| Lenovo        | ThinkPad E560 20EV000UIX    | Notebook    | [ac6bd9497a](https://linux-hardware.org/?probe=ac6bd9497a) | Jun 25, 2023 |
| Toshiba       | Satellite U400              | Notebook    | [58b2ad81eb](https://linux-hardware.org/?probe=58b2ad81eb) | Jun 25, 2023 |
| Acer          | Aspire M3-581G              | Notebook    | [0c348c2570](https://linux-hardware.org/?probe=0c348c2570) | Jun 25, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [2d7e4f3505](https://linux-hardware.org/?probe=2d7e4f3505) | Jun 24, 2023 |
| Acer          | Aspire 5738                 | Notebook    | [8112b061f0](https://linux-hardware.org/?probe=8112b061f0) | Jun 24, 2023 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [be14b80f2c](https://linux-hardware.org/?probe=be14b80f2c) | Jun 24, 2023 |
| Positivo      | POS-AG31AP                  | Desktop     | [bd3b3228c6](https://linux-hardware.org/?probe=bd3b3228c6) | Jun 24, 2023 |
| Intel         | D946GZIS AAD66165-301       | Desktop     | [dac65b1c2c](https://linux-hardware.org/?probe=dac65b1c2c) | Jun 24, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [23134d6c71](https://linux-hardware.org/?probe=23134d6c71) | Jun 24, 2023 |
| Dell          | Latitude E6400              | Notebook    | [74be208929](https://linux-hardware.org/?probe=74be208929) | Jun 24, 2023 |
| ASUSTek       | P5B                         | Desktop     | [a62968d622](https://linux-hardware.org/?probe=a62968d622) | Jun 24, 2023 |
| Acer          | AOD270                      | Notebook    | [af596f2c11](https://linux-hardware.org/?probe=af596f2c11) | Jun 24, 2023 |
| Acer          | AOD270                      | Notebook    | [d3204f80d5](https://linux-hardware.org/?probe=d3204f80d5) | Jun 24, 2023 |
| Toshiba       | Satellite U400              | Notebook    | [aa6254ebd2](https://linux-hardware.org/?probe=aa6254ebd2) | Jun 24, 2023 |
| ASUSTek       | F2A85-V PRO                 | Desktop     | [011552703c](https://linux-hardware.org/?probe=011552703c) | Jun 24, 2023 |
| Lenovo        | ThinkPad 10 2nd 20E4S0JA... | Tablet      | [1773c81302](https://linux-hardware.org/?probe=1773c81302) | Jun 23, 2023 |
| Lenovo        | ThinkPad 10 2nd 20E4S0JA... | Tablet      | [80b535ff26](https://linux-hardware.org/?probe=80b535ff26) | Jun 23, 2023 |
| HP            | EliteBook 8560p             | Notebook    | [177d2fe509](https://linux-hardware.org/?probe=177d2fe509) | Jun 22, 2023 |
| Positivo      | POS-AG31AP                  | Desktop     | [1dd704fab9](https://linux-hardware.org/?probe=1dd704fab9) | Jun 22, 2023 |
| Google        | Kefka                       | Notebook    | [2580ed90ee](https://linux-hardware.org/?probe=2580ed90ee) | Jun 22, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [ae8c13c6fd](https://linux-hardware.org/?probe=ae8c13c6fd) | Jun 22, 2023 |
| Dell          | 0G9322                      | Desktop     | [a742a26282](https://linux-hardware.org/?probe=a742a26282) | Jun 22, 2023 |
| AZW           | SER                         | Mini pc     | [9ef166eb46](https://linux-hardware.org/?probe=9ef166eb46) | Jun 22, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | Desktop     | [1e11366a3e](https://linux-hardware.org/?probe=1e11366a3e) | Jun 21, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [3d558ea9aa](https://linux-hardware.org/?probe=3d558ea9aa) | Jun 21, 2023 |
| Dell          | Vostro 5481                 | Notebook    | [b28f58f09e](https://linux-hardware.org/?probe=b28f58f09e) | Jun 20, 2023 |
| Intel         | D34010WYK H14771-304        | Desktop     | [0d3af8114b](https://linux-hardware.org/?probe=0d3af8114b) | Jun 20, 2023 |
| HP            | ENVY m6                     | Notebook    | [ea4c3aca13](https://linux-hardware.org/?probe=ea4c3aca13) | Jun 20, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [72ef7ff0aa](https://linux-hardware.org/?probe=72ef7ff0aa) | Jun 20, 2023 |
| Dell          | G7 7588                     | Notebook    | [946a645897](https://linux-hardware.org/?probe=946a645897) | Jun 20, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [88d7f8992f](https://linux-hardware.org/?probe=88d7f8992f) | Jun 19, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [93587f51a9](https://linux-hardware.org/?probe=93587f51a9) | Jun 19, 2023 |
| Sony          | VPCCA15FX                   | Notebook    | [ed7dba1a4c](https://linux-hardware.org/?probe=ed7dba1a4c) | Jun 19, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [bc371b62c9](https://linux-hardware.org/?probe=bc371b62c9) | Jun 19, 2023 |
| Sony          | VPCCA15FX                   | Notebook    | [c5660d0020](https://linux-hardware.org/?probe=c5660d0020) | Jun 19, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [8086cf1231](https://linux-hardware.org/?probe=8086cf1231) | Jun 19, 2023 |
| Lenovo        | ThinkPad T440 20B7S0VA05    | Notebook    | [307c8a76ab](https://linux-hardware.org/?probe=307c8a76ab) | Jun 19, 2023 |
| AZW           | GTR V02                     | Desktop     | [f9bee18426](https://linux-hardware.org/?probe=f9bee18426) | Jun 19, 2023 |
| GPU Compan... | GWNC21524                   | Notebook    | [46bd956cbf](https://linux-hardware.org/?probe=46bd956cbf) | Jun 19, 2023 |
| Toshiba       | TECRA M10                   | Notebook    | [37f232dce0](https://linux-hardware.org/?probe=37f232dce0) | Jun 19, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [7546cac791](https://linux-hardware.org/?probe=7546cac791) | Jun 19, 2023 |
| ASUSTek       | P5LD2                       | Desktop     | [7038963b77](https://linux-hardware.org/?probe=7038963b77) | Jun 18, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [e1fc794bc5](https://linux-hardware.org/?probe=e1fc794bc5) | Jun 18, 2023 |
| ASUSTek       | VivoBook S13 X330FA_S330... | Notebook    | [b816a11527](https://linux-hardware.org/?probe=b816a11527) | Jun 18, 2023 |
| Acer          | Aspire 5738                 | Notebook    | [8247e349fc](https://linux-hardware.org/?probe=8247e349fc) | Jun 17, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [bb6859a141](https://linux-hardware.org/?probe=bb6859a141) | Jun 17, 2023 |
| HP            | ProBook 650 G5              | Notebook    | [1d158627b0](https://linux-hardware.org/?probe=1d158627b0) | Jun 17, 2023 |
| Dell          | Latitude 7370               | Notebook    | [5c2378adc5](https://linux-hardware.org/?probe=5c2378adc5) | Jun 17, 2023 |
| Dell          | Latitude 7370               | Notebook    | [44dba24aed](https://linux-hardware.org/?probe=44dba24aed) | Jun 17, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [3614dc460e](https://linux-hardware.org/?probe=3614dc460e) | Jun 17, 2023 |
| HP            | Laptop 14-bw0xx             | Notebook    | [f38253d79c](https://linux-hardware.org/?probe=f38253d79c) | Jun 17, 2023 |
| Apple         | Mac-F2238AC8                | All in one  | [7d9f25dc5f](https://linux-hardware.org/?probe=7d9f25dc5f) | Jun 17, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [a2bbc6abd3](https://linux-hardware.org/?probe=a2bbc6abd3) | Jun 17, 2023 |
| Haier         | Y11B                        | Notebook    | [0c2abeea6e](https://linux-hardware.org/?probe=0c2abeea6e) | Jun 17, 2023 |
| HP            | ProBook 650 G5              | Notebook    | [9c53e4cd72](https://linux-hardware.org/?probe=9c53e4cd72) | Jun 17, 2023 |
| HP            | G62                         | Notebook    | [2e1e964887](https://linux-hardware.org/?probe=2e1e964887) | Jun 16, 2023 |
| Acer          | Aspire V5-571P              | Notebook    | [2adeb26f8a](https://linux-hardware.org/?probe=2adeb26f8a) | Jun 15, 2023 |
| ASRock        | B85M                        | Desktop     | [19f8b16937](https://linux-hardware.org/?probe=19f8b16937) | Jun 15, 2023 |
| Lenovo        | Win8 STD MM DPK IPG         | All in one  | [c503081708](https://linux-hardware.org/?probe=c503081708) | Jun 15, 2023 |
| Dell          | 0KC9NP A01                  | Desktop     | [b00d413241](https://linux-hardware.org/?probe=b00d413241) | Jun 14, 2023 |
| Dell          | 0KC9NP A01                  | Desktop     | [1d487a1ed5](https://linux-hardware.org/?probe=1d487a1ed5) | Jun 14, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [eab79964fb](https://linux-hardware.org/?probe=eab79964fb) | Jun 14, 2023 |
| Dell          | Venue 11 Pro 5130           | Notebook    | [e1bb6b17b8](https://linux-hardware.org/?probe=e1bb6b17b8) | Jun 14, 2023 |
| Vorke         | V1 Plus                     | Desktop     | [a63988d437](https://linux-hardware.org/?probe=a63988d437) | Jun 14, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [9fe9d9f03f](https://linux-hardware.org/?probe=9fe9d9f03f) | Jun 13, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | Desktop     | [c1992a1680](https://linux-hardware.org/?probe=c1992a1680) | Jun 13, 2023 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [b737ce6557](https://linux-hardware.org/?probe=b737ce6557) | Jun 13, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [f46f1000c0](https://linux-hardware.org/?probe=f46f1000c0) | Jun 13, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [535d3d42b7](https://linux-hardware.org/?probe=535d3d42b7) | Jun 13, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [2794a5aa86](https://linux-hardware.org/?probe=2794a5aa86) | Jun 12, 2023 |
| ASUSTek       | P5B                         | Desktop     | [6308a1c633](https://linux-hardware.org/?probe=6308a1c633) | Jun 12, 2023 |
| HP            | ENVY m6                     | Notebook    | [b3c165b329](https://linux-hardware.org/?probe=b3c165b329) | Jun 12, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [373e36422d](https://linux-hardware.org/?probe=373e36422d) | Jun 12, 2023 |
| MSI           | GL62M 7RDX                  | Notebook    | [d1fb646d9a](https://linux-hardware.org/?probe=d1fb646d9a) | Jun 11, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9cb593e9e1](https://linux-hardware.org/?probe=9cb593e9e1) | Jun 11, 2023 |
| ASUSTek       | U43Jc                       | Notebook    | [1af7e59490](https://linux-hardware.org/?probe=1af7e59490) | Jun 11, 2023 |
| ASUSTek       | U43Jc                       | Notebook    | [15e8e27585](https://linux-hardware.org/?probe=15e8e27585) | Jun 11, 2023 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | Desktop     | [9ea7188339](https://linux-hardware.org/?probe=9ea7188339) | Jun 11, 2023 |
| HP            | 8350                        | Desktop     | [8a40ff28c8](https://linux-hardware.org/?probe=8a40ff28c8) | Jun 11, 2023 |
| ASUSTek       | P5B                         | Desktop     | [794635cbea](https://linux-hardware.org/?probe=794635cbea) | Jun 10, 2023 |
| Samsung       | N150/N210/N220              | Notebook    | [977d645961](https://linux-hardware.org/?probe=977d645961) | Jun 10, 2023 |
| Notebook      | NJ50_70CU                   | Notebook    | [d39b8694fd](https://linux-hardware.org/?probe=d39b8694fd) | Jun 10, 2023 |
| Packard Be... | EasyNote TE11BZ             | Notebook    | [a8f9a31f17](https://linux-hardware.org/?probe=a8f9a31f17) | Jun 10, 2023 |
| MP            | MS-7848                     | Desktop     | [cd63c98850](https://linux-hardware.org/?probe=cd63c98850) | Jun 10, 2023 |
| Google        | Pirika                      | Notebook    | [67fce0a645](https://linux-hardware.org/?probe=67fce0a645) | Jun 10, 2023 |
| Dell          | Precision 7520              | Notebook    | [c52fb2f851](https://linux-hardware.org/?probe=c52fb2f851) | Jun 10, 2023 |
| Nvidia        | MCP79                       | Desktop     | [8203509a77](https://linux-hardware.org/?probe=8203509a77) | Jun 09, 2023 |
| ASRock        | H81M-HDS                    | Desktop     | [e1ff6f4e2f](https://linux-hardware.org/?probe=e1ff6f4e2f) | Jun 08, 2023 |
| ASUSTek       | P5B                         | Desktop     | [32baec6c0f](https://linux-hardware.org/?probe=32baec6c0f) | Jun 08, 2023 |
| Shenzhen M... | F7BFD                       | Desktop     | [74cf1d0b63](https://linux-hardware.org/?probe=74cf1d0b63) | Jun 08, 2023 |
| Shenzhen M... | F7BFD                       | Desktop     | [88cbeea389](https://linux-hardware.org/?probe=88cbeea389) | Jun 08, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [20d28155d8](https://linux-hardware.org/?probe=20d28155d8) | Jun 08, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [517cbd7f48](https://linux-hardware.org/?probe=517cbd7f48) | Jun 08, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [2ad7aefc45](https://linux-hardware.org/?probe=2ad7aefc45) | Jun 07, 2023 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [2ad409f60a](https://linux-hardware.org/?probe=2ad409f60a) | Jun 07, 2023 |
| HP            | 8350                        | Desktop     | [113be26d4c](https://linux-hardware.org/?probe=113be26d4c) | Jun 07, 2023 |
| Dell          | 0G9322                      | Desktop     | [e81a7f788a](https://linux-hardware.org/?probe=e81a7f788a) | Jun 07, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [5254a5fe09](https://linux-hardware.org/?probe=5254a5fe09) | Jun 07, 2023 |
| HP            | Pavilion Laptop 14-ec1xx... | Notebook    | [de4c183b01](https://linux-hardware.org/?probe=de4c183b01) | Jun 06, 2023 |
| Samsung       | 300E5M/300E5L               | Notebook    | [e066300eac](https://linux-hardware.org/?probe=e066300eac) | Jun 06, 2023 |
| Nvidia        | MCP79                       | Desktop     | [bf109ed28f](https://linux-hardware.org/?probe=bf109ed28f) | Jun 06, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [79f63dcf8e](https://linux-hardware.org/?probe=79f63dcf8e) | Jun 06, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [d48dc73993](https://linux-hardware.org/?probe=d48dc73993) | Jun 06, 2023 |
| Acer          | Aspire 5736Z                | Notebook    | [a98deb1f54](https://linux-hardware.org/?probe=a98deb1f54) | Jun 06, 2023 |
| ASUSTek       | CM1730,CM1830               | Desktop     | [2cc76d0cd9](https://linux-hardware.org/?probe=2cc76d0cd9) | Jun 05, 2023 |
| ASUSTek       | CM1730,CM1830               | Desktop     | [7dc46d923e](https://linux-hardware.org/?probe=7dc46d923e) | Jun 05, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [8308d5da16](https://linux-hardware.org/?probe=8308d5da16) | Jun 05, 2023 |
| ASUSTek       | P5Q                         | Desktop     | [85c6e06d3b](https://linux-hardware.org/?probe=85c6e06d3b) | Jun 05, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [2f8dbb707f](https://linux-hardware.org/?probe=2f8dbb707f) | Jun 05, 2023 |
| Dell          | 00010C A00                  | Desktop     | [fb12198605](https://linux-hardware.org/?probe=fb12198605) | Jun 05, 2023 |
| Dell          | 00010C A00                  | Desktop     | [d94442285c](https://linux-hardware.org/?probe=d94442285c) | Jun 05, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [e3b8e1a109](https://linux-hardware.org/?probe=e3b8e1a109) | Jun 04, 2023 |
| Dell          | Latitude E5250              | Notebook    | [e85c6a09d1](https://linux-hardware.org/?probe=e85c6a09d1) | Jun 04, 2023 |
| Toshiba       | IS 1412                     | Notebook    | [b1b0369688](https://linux-hardware.org/?probe=b1b0369688) | Jun 04, 2023 |
| Lenovo        | ThinkPad T450 20BUS0LW02    | Notebook    | [27f6e7df80](https://linux-hardware.org/?probe=27f6e7df80) | Jun 04, 2023 |
| ASUSTek       | B75M-A                      | Desktop     | [55139a968d](https://linux-hardware.org/?probe=55139a968d) | Jun 04, 2023 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | Desktop     | [413aba0d3f](https://linux-hardware.org/?probe=413aba0d3f) | Jun 04, 2023 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [83967c7908](https://linux-hardware.org/?probe=83967c7908) | Jun 04, 2023 |
| Intel         | NUC8BEB J72693-304          | Mini pc     | [a20f9c3365](https://linux-hardware.org/?probe=a20f9c3365) | Jun 03, 2023 |
| Dell          | 0G9322                      | Desktop     | [a1c5ec8909](https://linux-hardware.org/?probe=a1c5ec8909) | Jun 03, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [55f28b41b4](https://linux-hardware.org/?probe=55f28b41b4) | Jun 03, 2023 |
| Toshiba       | IS 1412                     | Notebook    | [6ea1bc7e6a](https://linux-hardware.org/?probe=6ea1bc7e6a) | Jun 03, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [01387c3030](https://linux-hardware.org/?probe=01387c3030) | Jun 03, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [20260fb3b3](https://linux-hardware.org/?probe=20260fb3b3) | Jun 03, 2023 |
| HP            | 339A                        | Desktop     | [bb4619f4eb](https://linux-hardware.org/?probe=bb4619f4eb) | Jun 02, 2023 |
| Gateway       | SX2851                      | Desktop     | [262ddffda9](https://linux-hardware.org/?probe=262ddffda9) | Jun 02, 2023 |
| IPASON        | P3                          | Notebook    | [bd9e0660a4](https://linux-hardware.org/?probe=bd9e0660a4) | Jun 02, 2023 |
| ASUSTek       | K70IJ                       | Notebook    | [5b877dfec5](https://linux-hardware.org/?probe=5b877dfec5) | Jun 02, 2023 |
| MSI           | H81M-E34                    | Desktop     | [26362cac22](https://linux-hardware.org/?probe=26362cac22) | Jun 02, 2023 |
| MSI           | H81M-E34                    | Desktop     | [9f04387a7c](https://linux-hardware.org/?probe=9f04387a7c) | Jun 01, 2023 |
| Toshiba       | Satellite L650              | Notebook    | [63eb6978fa](https://linux-hardware.org/?probe=63eb6978fa) | Jun 01, 2023 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [abc4bba144](https://linux-hardware.org/?probe=abc4bba144) | Jun 01, 2023 |
| MSI           | 890FXA-GD70                 | Desktop     | [bcc4cd9597](https://linux-hardware.org/?probe=bcc4cd9597) | Jun 01, 2023 |
| HP            | 82B5                        | All in one  | [77ecbfa91c](https://linux-hardware.org/?probe=77ecbfa91c) | Jun 01, 2023 |
| Lenovo        | IdeaPad 3 17ITL6 82H9       | Notebook    | [a7af6cac2c](https://linux-hardware.org/?probe=a7af6cac2c) | Jun 01, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [923c9a18ff](https://linux-hardware.org/?probe=923c9a18ff) | Jun 01, 2023 |
| HP            | Pavilion dv6500             | Notebook    | [0198d67a15](https://linux-hardware.org/?probe=0198d67a15) | May 31, 2023 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [449b742c95](https://linux-hardware.org/?probe=449b742c95) | May 31, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [0ddd2982db](https://linux-hardware.org/?probe=0ddd2982db) | May 31, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [93d1ee7e2d](https://linux-hardware.org/?probe=93d1ee7e2d) | May 31, 2023 |
| Sony          | SVF14214CXW                 | Notebook    | [51568ce56e](https://linux-hardware.org/?probe=51568ce56e) | May 30, 2023 |
| Dell          | Latitude 3480               | Notebook    | [56d1834385](https://linux-hardware.org/?probe=56d1834385) | May 30, 2023 |
| Sony          | SVF14214CXW                 | Notebook    | [6cf7c2d7f2](https://linux-hardware.org/?probe=6cf7c2d7f2) | May 30, 2023 |
| Dell          | Inspiron 5748               | Notebook    | [08b61d608c](https://linux-hardware.org/?probe=08b61d608c) | May 30, 2023 |
| ASUSTek       | U43Jc                       | Notebook    | [db28d8f731](https://linux-hardware.org/?probe=db28d8f731) | May 28, 2023 |
| ASUSTek       | U43Jc                       | Notebook    | [36bd3a5288](https://linux-hardware.org/?probe=36bd3a5288) | May 28, 2023 |
| Lenovo        | ThinkPad E490 20N8A01YGI    | Notebook    | [c46cf56eb1](https://linux-hardware.org/?probe=c46cf56eb1) | May 27, 2023 |
| Acer          | Predator G3-605             | Desktop     | [f33c170be3](https://linux-hardware.org/?probe=f33c170be3) | May 27, 2023 |
| Lenovo        | B50-70 80EU                 | Notebook    | [8c51cdf4ef](https://linux-hardware.org/?probe=8c51cdf4ef) | May 27, 2023 |
| HP            | Pavilion dv6                | Notebook    | [9f96328490](https://linux-hardware.org/?probe=9f96328490) | May 27, 2023 |
| Acer          | Aspire ES1-523              | Notebook    | [681fbd4a1f](https://linux-hardware.org/?probe=681fbd4a1f) | May 27, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [48a2156205](https://linux-hardware.org/?probe=48a2156205) | May 27, 2023 |
| Dell          | 0G9322                      | Desktop     | [4d1450ba3a](https://linux-hardware.org/?probe=4d1450ba3a) | May 27, 2023 |
| Dell          | 0G9322                      | Desktop     | [d742ccb0c4](https://linux-hardware.org/?probe=d742ccb0c4) | May 27, 2023 |
| HP            | 21D0                        | Desktop     | [7f83859a91](https://linux-hardware.org/?probe=7f83859a91) | May 27, 2023 |
| HP            | 81BA                        | All in one  | [d41186191f](https://linux-hardware.org/?probe=d41186191f) | May 27, 2023 |
| MSI           | H97 GUARD-PRO               | Desktop     | [3737e6c832](https://linux-hardware.org/?probe=3737e6c832) | May 27, 2023 |
| Toshiba       | TECRA M10                   | Notebook    | [3ce97963e7](https://linux-hardware.org/?probe=3ce97963e7) | May 26, 2023 |
| Toshiba       | TECRA M10                   | Notebook    | [2c574f9677](https://linux-hardware.org/?probe=2c574f9677) | May 26, 2023 |
| HP            | ProBook 4740s               | Notebook    | [457a56d75c](https://linux-hardware.org/?probe=457a56d75c) | May 26, 2023 |
| Intel         | NUC6CAYB J23203-408         | Mini pc     | [53d45d0d79](https://linux-hardware.org/?probe=53d45d0d79) | May 26, 2023 |
| ASUSTek       | G50VT                       | Notebook    | [6e4a2588b1](https://linux-hardware.org/?probe=6e4a2588b1) | May 26, 2023 |
| Intel         | NUC6CAYB J23203-408         | Mini pc     | [8d7ce86449](https://linux-hardware.org/?probe=8d7ce86449) | May 26, 2023 |
| HP            | 18E5                        | Desktop     | [23e2edb1fe](https://linux-hardware.org/?probe=23e2edb1fe) | May 26, 2023 |
| Dell          | 0K095G A02                  | Desktop     | [f11b8418c9](https://linux-hardware.org/?probe=f11b8418c9) | May 26, 2023 |
| HP            | 21D0                        | Desktop     | [8e52c2613c](https://linux-hardware.org/?probe=8e52c2613c) | May 26, 2023 |
| Google        | Lars                        | Notebook    | [25cc6549c3](https://linux-hardware.org/?probe=25cc6549c3) | May 25, 2023 |
| HP            | ProBook 6440b               | Notebook    | [5ed14b01a3](https://linux-hardware.org/?probe=5ed14b01a3) | May 25, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [61dc4c5620](https://linux-hardware.org/?probe=61dc4c5620) | May 25, 2023 |
| Apple         | MacBookAir4,1               | Notebook    | [d25345cb25](https://linux-hardware.org/?probe=d25345cb25) | May 25, 2023 |
| ECS           | H510H6-M2                   | Desktop     | [eba710b3de](https://linux-hardware.org/?probe=eba710b3de) | May 24, 2023 |
| Vorke         | V1 Plus                     | Desktop     | [81c0b82d6c](https://linux-hardware.org/?probe=81c0b82d6c) | May 24, 2023 |
| HP            | Pavilion g6                 | Notebook    | [f6fbdf57b5](https://linux-hardware.org/?probe=f6fbdf57b5) | May 24, 2023 |
| ECS           | H510H6-M2                   | Desktop     | [b36784601b](https://linux-hardware.org/?probe=b36784601b) | May 24, 2023 |
| HP            | Pavilion Notebook 15-bc5... | Notebook    | [933989a15b](https://linux-hardware.org/?probe=933989a15b) | May 24, 2023 |
| HP            | Stream Notebook             | Notebook    | [74d40533fc](https://linux-hardware.org/?probe=74d40533fc) | May 24, 2023 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [504a24887e](https://linux-hardware.org/?probe=504a24887e) | May 24, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [ca3ed99a5c](https://linux-hardware.org/?probe=ca3ed99a5c) | May 24, 2023 |
| Pegatron      | 2AC2A                       | Desktop     | [f9e504a430](https://linux-hardware.org/?probe=f9e504a430) | May 24, 2023 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [8c7d3913b8](https://linux-hardware.org/?probe=8c7d3913b8) | May 24, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [e1baf451db](https://linux-hardware.org/?probe=e1baf451db) | May 23, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [61ef8e4e63](https://linux-hardware.org/?probe=61ef8e4e63) | May 23, 2023 |
| HP            | 21EF                        | Desktop     | [f1d5c9381c](https://linux-hardware.org/?probe=f1d5c9381c) | May 23, 2023 |
| MSI           | H81M-E34                    | Desktop     | [4247f30888](https://linux-hardware.org/?probe=4247f30888) | May 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [977cf42905](https://linux-hardware.org/?probe=977cf42905) | May 23, 2023 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [08746538f6](https://linux-hardware.org/?probe=08746538f6) | May 23, 2023 |
| Dell          | Latitude E5450              | Notebook    | [642802d511](https://linux-hardware.org/?probe=642802d511) | May 23, 2023 |
| Dell          | Inspiron 1501               | Notebook    | [4703a17f03](https://linux-hardware.org/?probe=4703a17f03) | May 23, 2023 |
| HP            | Pavilion g6                 | Notebook    | [4d0edc38d5](https://linux-hardware.org/?probe=4d0edc38d5) | May 23, 2023 |
| HP            | 21EF                        | Desktop     | [3249975d27](https://linux-hardware.org/?probe=3249975d27) | May 22, 2023 |
| Packard Be... | EasyNote MH35               | Notebook    | [ea7710b373](https://linux-hardware.org/?probe=ea7710b373) | May 22, 2023 |
| ASRock        | H77M                        | Desktop     | [7f173e0b75](https://linux-hardware.org/?probe=7f173e0b75) | May 22, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [dfb369a8d2](https://linux-hardware.org/?probe=dfb369a8d2) | May 22, 2023 |
| HP            | EliteBook Folio G1          | Notebook    | [81477cd76f](https://linux-hardware.org/?probe=81477cd76f) | May 22, 2023 |
| HP            | EliteBook Folio G1          | Notebook    | [73d4310fa2](https://linux-hardware.org/?probe=73d4310fa2) | May 22, 2023 |
| HP            | 18E5                        | Desktop     | [d1bc34770d](https://linux-hardware.org/?probe=d1bc34770d) | May 22, 2023 |
| Microsoft     | Surface Book                | Tablet      | [01c76b5ed7](https://linux-hardware.org/?probe=01c76b5ed7) | May 21, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [b6465d2950](https://linux-hardware.org/?probe=b6465d2950) | May 21, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [b9de7bf2f3](https://linux-hardware.org/?probe=b9de7bf2f3) | May 21, 2023 |
| Dell          | 0FGCC7 A01                  | Server      | [3900d6a330](https://linux-hardware.org/?probe=3900d6a330) | May 21, 2023 |
| Dell          | 02N3WF A01                  | Desktop     | [8d0096c040](https://linux-hardware.org/?probe=8d0096c040) | May 21, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [4087cdd6cb](https://linux-hardware.org/?probe=4087cdd6cb) | May 20, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [8db744994d](https://linux-hardware.org/?probe=8db744994d) | May 20, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | Notebook    | [6bef224193](https://linux-hardware.org/?probe=6bef224193) | May 20, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [d11ecdffaf](https://linux-hardware.org/?probe=d11ecdffaf) | May 20, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [0bcd2c7244](https://linux-hardware.org/?probe=0bcd2c7244) | May 20, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [c1594f6dab](https://linux-hardware.org/?probe=c1594f6dab) | May 20, 2023 |
| Dell          | Latitude E7450              | Notebook    | [b76cb7567c](https://linux-hardware.org/?probe=b76cb7567c) | May 20, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [c1f679b4d4](https://linux-hardware.org/?probe=c1f679b4d4) | May 20, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [0c163f5c69](https://linux-hardware.org/?probe=0c163f5c69) | May 20, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [8a6ad6c590](https://linux-hardware.org/?probe=8a6ad6c590) | May 19, 2023 |
| Dell          | 0GDG8Y A00                  | Desktop     | [514fe06c9e](https://linux-hardware.org/?probe=514fe06c9e) | May 19, 2023 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [aae519e65d](https://linux-hardware.org/?probe=aae519e65d) | May 19, 2023 |
| Tactus        | GeoBook 140                 | Notebook    | [534c32884a](https://linux-hardware.org/?probe=534c32884a) | May 19, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [31568d83f7](https://linux-hardware.org/?probe=31568d83f7) | May 18, 2023 |
| Gigabyte      | H81M-DS2                    | Desktop     | [754dc9d1fc](https://linux-hardware.org/?probe=754dc9d1fc) | May 18, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [0608bc6ac3](https://linux-hardware.org/?probe=0608bc6ac3) | May 18, 2023 |
| Philco        | PHN14C                      | Notebook    | [4efea72b8f](https://linux-hardware.org/?probe=4efea72b8f) | May 18, 2023 |
| Acer          | Aspire A514-55              | Notebook    | [e096b3a75c](https://linux-hardware.org/?probe=e096b3a75c) | May 18, 2023 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [ee37475637](https://linux-hardware.org/?probe=ee37475637) | May 18, 2023 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [68406e2c40](https://linux-hardware.org/?probe=68406e2c40) | May 18, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [cadb0eb363](https://linux-hardware.org/?probe=cadb0eb363) | May 17, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [cd3c24c6a2](https://linux-hardware.org/?probe=cd3c24c6a2) | May 17, 2023 |
| Acer          | Revo 70                     | Desktop     | [6cbc11e75b](https://linux-hardware.org/?probe=6cbc11e75b) | May 17, 2023 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [e18deba45b](https://linux-hardware.org/?probe=e18deba45b) | May 17, 2023 |
| HP            | 2B02                        | Desktop     | [a6bf09d51c](https://linux-hardware.org/?probe=a6bf09d51c) | May 17, 2023 |
| Pegatron      | Benicia                     | Desktop     | [e6ee1c66f6](https://linux-hardware.org/?probe=e6ee1c66f6) | May 17, 2023 |
| Framework     | Laptop                      | Notebook    | [b8739c141d](https://linux-hardware.org/?probe=b8739c141d) | May 16, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [d3c3cc9f96](https://linux-hardware.org/?probe=d3c3cc9f96) | May 15, 2023 |
| Dell          | XPS 17 9700                 | Notebook    | [7b95691784](https://linux-hardware.org/?probe=7b95691784) | May 15, 2023 |
| Intel         | Tiger Hill                  | Desktop     | [fdbe67045c](https://linux-hardware.org/?probe=fdbe67045c) | May 15, 2023 |
| Samsung       | N150/N210/N220              | Notebook    | [3f18889439](https://linux-hardware.org/?probe=3f18889439) | May 15, 2023 |
| ASUSTek       | ROG Strix G512LW_G512LW     | Notebook    | [03c67bbed5](https://linux-hardware.org/?probe=03c67bbed5) | May 15, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [496f6048ec](https://linux-hardware.org/?probe=496f6048ec) | May 15, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [dd8c6c3811](https://linux-hardware.org/?probe=dd8c6c3811) | May 15, 2023 |
| HP            | 18E5                        | Desktop     | [7d5ceb9f5d](https://linux-hardware.org/?probe=7d5ceb9f5d) | May 15, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [d27a3510ed](https://linux-hardware.org/?probe=d27a3510ed) | May 14, 2023 |
| HP            | Presario CQ61               | Notebook    | [0967999006](https://linux-hardware.org/?probe=0967999006) | May 14, 2023 |
| Google        | Bluebird                    | Notebook    | [c10880ed1b](https://linux-hardware.org/?probe=c10880ed1b) | May 14, 2023 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [24c81ddf59](https://linux-hardware.org/?probe=24c81ddf59) | May 14, 2023 |
| Acer          | Aspire E5-574               | Notebook    | [89fbcb7903](https://linux-hardware.org/?probe=89fbcb7903) | May 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [83e208da09](https://linux-hardware.org/?probe=83e208da09) | May 14, 2023 |
| Lenovo        | IdeaPad Z470                | Notebook    | [2b11351f94](https://linux-hardware.org/?probe=2b11351f94) | May 14, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [38b6dd7b3f](https://linux-hardware.org/?probe=38b6dd7b3f) | May 14, 2023 |
| Dell          | Latitude 3340               | Notebook    | [59d83d9cef](https://linux-hardware.org/?probe=59d83d9cef) | May 14, 2023 |
| SKIKK         | Niflheim 17 II              | Notebook    | [ce9c27f16f](https://linux-hardware.org/?probe=ce9c27f16f) | May 14, 2023 |
| ASUSTek       | K8N-DRE                     | Desktop     | [395dc0cfb3](https://linux-hardware.org/?probe=395dc0cfb3) | May 13, 2023 |
| ASUSTek       | K8N-DRE                     | Desktop     | [f55a0c735f](https://linux-hardware.org/?probe=f55a0c735f) | May 13, 2023 |
| Vorke         | V1 Plus                     | Desktop     | [19f095fc02](https://linux-hardware.org/?probe=19f095fc02) | May 13, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [e844f3a6fe](https://linux-hardware.org/?probe=e844f3a6fe) | May 13, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [bd9eca79bb](https://linux-hardware.org/?probe=bd9eca79bb) | May 13, 2023 |
| Acer          | Predator G3-605             | Desktop     | [2d1485d58b](https://linux-hardware.org/?probe=2d1485d58b) | May 13, 2023 |
| Gigabyte      | A520M DS3H                  | Desktop     | [e053d0d304](https://linux-hardware.org/?probe=e053d0d304) | May 13, 2023 |
| Chuwi         | GemiBook XPro               | Notebook    | [53b6692944](https://linux-hardware.org/?probe=53b6692944) | May 13, 2023 |
| Chuwi         | GemiBook XPro               | Notebook    | [297921aabf](https://linux-hardware.org/?probe=297921aabf) | May 13, 2023 |
| Acer          | Predator G3-605             | Desktop     | [d3fc5ad399](https://linux-hardware.org/?probe=d3fc5ad399) | May 13, 2023 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [080f1c13d8](https://linux-hardware.org/?probe=080f1c13d8) | May 13, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [e2c57c80fc](https://linux-hardware.org/?probe=e2c57c80fc) | May 13, 2023 |
| Acer          | Aspire E1-570               | Notebook    | [135675c3ad](https://linux-hardware.org/?probe=135675c3ad) | May 13, 2023 |
| Google        | Kled                        | Notebook    | [f4e834ff36](https://linux-hardware.org/?probe=f4e834ff36) | May 12, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [d041d35517](https://linux-hardware.org/?probe=d041d35517) | May 12, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [d3ab5dcb5d](https://linux-hardware.org/?probe=d3ab5dcb5d) | May 12, 2023 |
| Dell          | Precision M2800             | Notebook    | [571407d9a3](https://linux-hardware.org/?probe=571407d9a3) | May 12, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [89b8dfaad7](https://linux-hardware.org/?probe=89b8dfaad7) | May 12, 2023 |
| Chuwi         | GemiBook XPro               | Notebook    | [e13fe43842](https://linux-hardware.org/?probe=e13fe43842) | May 12, 2023 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [c86f346e1d](https://linux-hardware.org/?probe=c86f346e1d) | May 12, 2023 |
| HP            | ProBook 4535s               | Notebook    | [0d2f9561ce](https://linux-hardware.org/?probe=0d2f9561ce) | May 12, 2023 |
| HP            | EliteBook 820 G4            | Notebook    | [34bd8e2402](https://linux-hardware.org/?probe=34bd8e2402) | May 12, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [5a1484127d](https://linux-hardware.org/?probe=5a1484127d) | May 12, 2023 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [730cce9495](https://linux-hardware.org/?probe=730cce9495) | May 12, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [381ca3ca78](https://linux-hardware.org/?probe=381ca3ca78) | May 11, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [40b6afc886](https://linux-hardware.org/?probe=40b6afc886) | May 11, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [2c8128a196](https://linux-hardware.org/?probe=2c8128a196) | May 11, 2023 |
| HP            | EliteBook 820 G4            | Notebook    | [a7327f2e2e](https://linux-hardware.org/?probe=a7327f2e2e) | May 11, 2023 |
| HP            | EliteBook 745 G3            | Notebook    | [256ad0c4d8](https://linux-hardware.org/?probe=256ad0c4d8) | May 11, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [2c96614c16](https://linux-hardware.org/?probe=2c96614c16) | May 11, 2023 |
| Toshiba       | TECRA M10                   | Notebook    | [cf43cf62c7](https://linux-hardware.org/?probe=cf43cf62c7) | May 10, 2023 |
| Toshiba       | TECRA M10                   | Notebook    | [d2be66b23b](https://linux-hardware.org/?probe=d2be66b23b) | May 10, 2023 |
| HP            | Pavilion dv7                | Notebook    | [794d198929](https://linux-hardware.org/?probe=794d198929) | May 10, 2023 |
| 16280-BM-3... | BADWARE-335861024712484 ... | Desktop     | [8f3baa5ed5](https://linux-hardware.org/?probe=8f3baa5ed5) | May 10, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [719d80a236](https://linux-hardware.org/?probe=719d80a236) | May 10, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [b25b524237](https://linux-hardware.org/?probe=b25b524237) | May 10, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [22778449cc](https://linux-hardware.org/?probe=22778449cc) | May 10, 2023 |
| ASUSTek       | A55BM-E                     | Desktop     | [4b1cb4d8cf](https://linux-hardware.org/?probe=4b1cb4d8cf) | May 10, 2023 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [ffd84ff48e](https://linux-hardware.org/?probe=ffd84ff48e) | May 09, 2023 |
| Lenovo        | Yoga 7 14ACN6 82N7          | Convertible | [ba75f23f44](https://linux-hardware.org/?probe=ba75f23f44) | May 09, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [abf6d2bf1d](https://linux-hardware.org/?probe=abf6d2bf1d) | May 09, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [0b1518261e](https://linux-hardware.org/?probe=0b1518261e) | May 09, 2023 |
| ASUSTek       | H81I-PLUS                   | Desktop     | [93d7a459be](https://linux-hardware.org/?probe=93d7a459be) | May 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [d45b33c736](https://linux-hardware.org/?probe=d45b33c736) | May 09, 2023 |
| ASUSTek       | GL702VI                     | Notebook    | [3598875ef3](https://linux-hardware.org/?probe=3598875ef3) | May 09, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [372fa59e86](https://linux-hardware.org/?probe=372fa59e86) | May 09, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [9ac068efc7](https://linux-hardware.org/?probe=9ac068efc7) | May 09, 2023 |
| Dell          | Latitude E6520              | Notebook    | [668b26cd28](https://linux-hardware.org/?probe=668b26cd28) | May 09, 2023 |
| HP            | Laptop 15                   | Notebook    | [20a0a03b80](https://linux-hardware.org/?probe=20a0a03b80) | May 08, 2023 |
| Acer          | Aspire E5-574               | Notebook    | [d48affb6b2](https://linux-hardware.org/?probe=d48affb6b2) | May 08, 2023 |
| HP            | 655                         | Notebook    | [be3dec1f65](https://linux-hardware.org/?probe=be3dec1f65) | May 08, 2023 |
| Positivo      | S14CT01                     | Notebook    | [63a129c031](https://linux-hardware.org/?probe=63a129c031) | May 08, 2023 |
| Dell          | Latitude 5520               | Notebook    | [4d8ef45cbc](https://linux-hardware.org/?probe=4d8ef45cbc) | May 07, 2023 |
| TrekStor      | SurfTab twin 11.6           | Convertible | [d6085d9a0b](https://linux-hardware.org/?probe=d6085d9a0b) | May 07, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [96cfd64792](https://linux-hardware.org/?probe=96cfd64792) | May 07, 2023 |
| SKIKK         | Niflheim 17 II              | Notebook    | [0304fddec7](https://linux-hardware.org/?probe=0304fddec7) | May 07, 2023 |
| SKIKK         | Niflheim 17 II              | Notebook    | [2a30823af1](https://linux-hardware.org/?probe=2a30823af1) | May 07, 2023 |
| HP            | 339A                        | Desktop     | [8b646a0fa1](https://linux-hardware.org/?probe=8b646a0fa1) | May 07, 2023 |
| HP            | 339A                        | Desktop     | [e23aaae239](https://linux-hardware.org/?probe=e23aaae239) | May 07, 2023 |
| Intel         | D946GZIS AAD66165-301       | Desktop     | [c350f5ed12](https://linux-hardware.org/?probe=c350f5ed12) | May 06, 2023 |
| Fujitsu Si... | AMILO PRO V3515             | Notebook    | [a6da9a31d7](https://linux-hardware.org/?probe=a6da9a31d7) | May 06, 2023 |
| ASUSTek       | P8Z68 DELUXE/GEN3           | Desktop     | [288e495c16](https://linux-hardware.org/?probe=288e495c16) | May 06, 2023 |
| ASRockRack    | D1521D4I2                   | Desktop     | [136a9303c0](https://linux-hardware.org/?probe=136a9303c0) | May 06, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [7b0b45831c](https://linux-hardware.org/?probe=7b0b45831c) | May 06, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [b7bf9f8683](https://linux-hardware.org/?probe=b7bf9f8683) | May 06, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [46894747b1](https://linux-hardware.org/?probe=46894747b1) | May 05, 2023 |
| HP            | ProBook 6570b               | Notebook    | [480e352bf8](https://linux-hardware.org/?probe=480e352bf8) | May 05, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [2723e21a6e](https://linux-hardware.org/?probe=2723e21a6e) | May 05, 2023 |
| TrekStor      | SurfTab twin 11.6           | Convertible | [2d5ecba977](https://linux-hardware.org/?probe=2d5ecba977) | May 05, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [9a0649d500](https://linux-hardware.org/?probe=9a0649d500) | May 05, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [6069763b68](https://linux-hardware.org/?probe=6069763b68) | May 05, 2023 |
| Lenovo        | Legion 7 16ACHg6 82N6       | Notebook    | [d8582f94de](https://linux-hardware.org/?probe=d8582f94de) | May 05, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [4ac4356e10](https://linux-hardware.org/?probe=4ac4356e10) | May 05, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [37fd24fab6](https://linux-hardware.org/?probe=37fd24fab6) | May 05, 2023 |
| Lenovo        | ThinkPad Yoga 11e 4th Ge... | Convertible | [b9ef1562db](https://linux-hardware.org/?probe=b9ef1562db) | May 05, 2023 |
| Lenovo        | ThinkPad T520 4242A25       | Notebook    | [6290e7f2fb](https://linux-hardware.org/?probe=6290e7f2fb) | May 05, 2023 |
| Lenovo        | ThinkPad Yoga 11e 4th Ge... | Convertible | [02fa09745c](https://linux-hardware.org/?probe=02fa09745c) | May 05, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [d571b75547](https://linux-hardware.org/?probe=d571b75547) | May 05, 2023 |
| Unknown       | X133                        | Notebook    | [b38ee0b3cc](https://linux-hardware.org/?probe=b38ee0b3cc) | May 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [cf49833602](https://linux-hardware.org/?probe=cf49833602) | May 04, 2023 |
| ASRock        | B550M-HDV                   | Desktop     | [408cbd96c0](https://linux-hardware.org/?probe=408cbd96c0) | May 04, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [9684be9c3a](https://linux-hardware.org/?probe=9684be9c3a) | May 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [5b46ed614a](https://linux-hardware.org/?probe=5b46ed614a) | May 04, 2023 |
| Unknown       | E450                        | Notebook    | [a3261aab47](https://linux-hardware.org/?probe=a3261aab47) | May 04, 2023 |
| Gigabyte      | Z590 VISION G               | Desktop     | [d37eb8bf49](https://linux-hardware.org/?probe=d37eb8bf49) | May 04, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [15160b0649](https://linux-hardware.org/?probe=15160b0649) | May 04, 2023 |
| ASRock        | H81M-HDS                    | Desktop     | [60e11bdf11](https://linux-hardware.org/?probe=60e11bdf11) | May 04, 2023 |
| KUU           | Andes II                    | Notebook    | [b15876e521](https://linux-hardware.org/?probe=b15876e521) | May 04, 2023 |
| Gigabyte      | MFLP5IP-00                  | Desktop     | [c9c14a6da2](https://linux-hardware.org/?probe=c9c14a6da2) | May 03, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [c338210639](https://linux-hardware.org/?probe=c338210639) | May 03, 2023 |
| Acer          | Aspire E1-570               | Notebook    | [bf515886ac](https://linux-hardware.org/?probe=bf515886ac) | May 03, 2023 |
| Dell          | 09WH54 A00                  | Desktop     | [0afa4006cd](https://linux-hardware.org/?probe=0afa4006cd) | May 03, 2023 |
| Acer          | Aspire V5-531               | Notebook    | [d8c61ad691](https://linux-hardware.org/?probe=d8c61ad691) | May 02, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [d3757c615f](https://linux-hardware.org/?probe=d3757c615f) | May 02, 2023 |
| Intel         | D946GZIS AAD66165-301       | Desktop     | [e61e22863f](https://linux-hardware.org/?probe=e61e22863f) | May 02, 2023 |
| Dell          | Latitude E6540              | Notebook    | [e6f334c91c](https://linux-hardware.org/?probe=e6f334c91c) | May 01, 2023 |
| Intel         | H55                         | Desktop     | [04dd5e834e](https://linux-hardware.org/?probe=04dd5e834e) | May 01, 2023 |
| Acer          | Aspire A315-21              | Notebook    | [f2c5618e4d](https://linux-hardware.org/?probe=f2c5618e4d) | May 01, 2023 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [83abb6a8e0](https://linux-hardware.org/?probe=83abb6a8e0) | May 01, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [f395109c45](https://linux-hardware.org/?probe=f395109c45) | May 01, 2023 |
| ASUSTek       | K53U                        | Notebook    | [0745a61353](https://linux-hardware.org/?probe=0745a61353) | May 01, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [cbc75f825e](https://linux-hardware.org/?probe=cbc75f825e) | May 01, 2023 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | Notebook    | [e316615297](https://linux-hardware.org/?probe=e316615297) | May 01, 2023 |
| Acer          | Aspire E5-574               | Notebook    | [bcd38374a3](https://linux-hardware.org/?probe=bcd38374a3) | May 01, 2023 |
| ASUSTek       | PN41                        | Mini pc     | [99d3eca719](https://linux-hardware.org/?probe=99d3eca719) | May 01, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [1a00a1321e](https://linux-hardware.org/?probe=1a00a1321e) | Apr 30, 2023 |
| MSI           | IONA                        | Desktop     | [966ec83038](https://linux-hardware.org/?probe=966ec83038) | Apr 30, 2023 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [6987a21849](https://linux-hardware.org/?probe=6987a21849) | Apr 30, 2023 |
| Foxconn       | G41S/G41S-K                 | Desktop     | [946a95c594](https://linux-hardware.org/?probe=946a95c594) | Apr 30, 2023 |
| Foxconn       | G41S/G41S-K                 | Desktop     | [58cebf39d1](https://linux-hardware.org/?probe=58cebf39d1) | Apr 30, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [f1faff33de](https://linux-hardware.org/?probe=f1faff33de) | Apr 30, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [8b89ffd983](https://linux-hardware.org/?probe=8b89ffd983) | Apr 30, 2023 |
| HP            | Pavilion dv7                | Notebook    | [68b51fde68](https://linux-hardware.org/?probe=68b51fde68) | Apr 30, 2023 |
| Positivo      | S14CT01                     | Notebook    | [b11ef938e1](https://linux-hardware.org/?probe=b11ef938e1) | Apr 29, 2023 |
| Toshiba       | Satellite C650D             | Notebook    | [472dedd62a](https://linux-hardware.org/?probe=472dedd62a) | Apr 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [4b0542737c](https://linux-hardware.org/?probe=4b0542737c) | Apr 29, 2023 |
| Apple         | Mac-F2208EC8                | Mini pc     | [6bad65ad2d](https://linux-hardware.org/?probe=6bad65ad2d) | Apr 29, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [25bc3aa225](https://linux-hardware.org/?probe=25bc3aa225) | Apr 29, 2023 |
| Sony          | VPCF215FX                   | Notebook    | [49c7606269](https://linux-hardware.org/?probe=49c7606269) | Apr 29, 2023 |
| Apple         | MacBook6,1                  | Notebook    | [58b09d7887](https://linux-hardware.org/?probe=58b09d7887) | Apr 29, 2023 |
| Apple         | MacBook6,1                  | Notebook    | [7d91fe30f7](https://linux-hardware.org/?probe=7d91fe30f7) | Apr 29, 2023 |
| Positivo      | S14CT01                     | Notebook    | [58988f4876](https://linux-hardware.org/?probe=58988f4876) | Apr 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [e908fdb73d](https://linux-hardware.org/?probe=e908fdb73d) | Apr 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [a984eefe43](https://linux-hardware.org/?probe=a984eefe43) | Apr 28, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [d9010fa8d0](https://linux-hardware.org/?probe=d9010fa8d0) | Apr 28, 2023 |
| Lenovo        | ThinkPad Edge 25453BG       | Notebook    | [2b5c6e2ded](https://linux-hardware.org/?probe=2b5c6e2ded) | Apr 28, 2023 |
| HP            | Laptop 14-em0xxx            | Notebook    | [8d06549ae0](https://linux-hardware.org/?probe=8d06549ae0) | Apr 28, 2023 |
| Lenovo        | IdeaPad Y470                | Notebook    | [58c809428e](https://linux-hardware.org/?probe=58c809428e) | Apr 28, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [896574c24a](https://linux-hardware.org/?probe=896574c24a) | Apr 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | Notebook    | [f1290d4846](https://linux-hardware.org/?probe=f1290d4846) | Apr 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [c4941a5c16](https://linux-hardware.org/?probe=c4941a5c16) | Apr 27, 2023 |
| Pegatron      | IPM41-D3                    | Desktop     | [faf8704eb3](https://linux-hardware.org/?probe=faf8704eb3) | Apr 26, 2023 |
| Dell          | Vostro 1510                 | Notebook    | [71c860d51c](https://linux-hardware.org/?probe=71c860d51c) | Apr 26, 2023 |
| Medion        | E2215T MD60198              | Notebook    | [390ccbba6f](https://linux-hardware.org/?probe=390ccbba6f) | Apr 26, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [86dad710fa](https://linux-hardware.org/?probe=86dad710fa) | Apr 26, 2023 |
| Lenovo        | 3000 N200 0769A97           | Notebook    | [a293f4f1f7](https://linux-hardware.org/?probe=a293f4f1f7) | Apr 26, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | Notebook    | [c40de2e155](https://linux-hardware.org/?probe=c40de2e155) | Apr 26, 2023 |
| Intel         | D34010WYK H14771-304        | Desktop     | [4fbbe6e603](https://linux-hardware.org/?probe=4fbbe6e603) | Apr 26, 2023 |
| Lenovo        | 30FD SDK0J40697 WIN 3305... | Desktop     | [07e9099105](https://linux-hardware.org/?probe=07e9099105) | Apr 26, 2023 |
| HP            | 1632                        | Desktop     | [0355cb4e69](https://linux-hardware.org/?probe=0355cb4e69) | Apr 25, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | Notebook    | [7abd61de30](https://linux-hardware.org/?probe=7abd61de30) | Apr 25, 2023 |
| HP            | EliteBook 2730p             | Notebook    | [51c0fadfdb](https://linux-hardware.org/?probe=51c0fadfdb) | Apr 25, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | Notebook    | [927c9a0377](https://linux-hardware.org/?probe=927c9a0377) | Apr 25, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [4231d023e9](https://linux-hardware.org/?probe=4231d023e9) | Apr 25, 2023 |
| eMachines     | MCP61PM-GM                  | Desktop     | [ff00693839](https://linux-hardware.org/?probe=ff00693839) | Apr 25, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [9bab79728a](https://linux-hardware.org/?probe=9bab79728a) | Apr 24, 2023 |
| Toshiba       | Satellite C45-A             | Notebook    | [7720195dfe](https://linux-hardware.org/?probe=7720195dfe) | Apr 24, 2023 |
| ASUSTek       | P5Q                         | Desktop     | [57e3cfa7dc](https://linux-hardware.org/?probe=57e3cfa7dc) | Apr 24, 2023 |
| Intel         | D946GZIS AAD66165-301       | Desktop     | [9d5ada0fc4](https://linux-hardware.org/?probe=9d5ada0fc4) | Apr 24, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [154380c27c](https://linux-hardware.org/?probe=154380c27c) | Apr 24, 2023 |
| Dell          | Inspiron 5565               | Notebook    | [6622474d4b](https://linux-hardware.org/?probe=6622474d4b) | Apr 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [60d1d4aec8](https://linux-hardware.org/?probe=60d1d4aec8) | Apr 24, 2023 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [c087d6cbae](https://linux-hardware.org/?probe=c087d6cbae) | Apr 24, 2023 |
| Gigabyte      | B650M DS3H                  | Desktop     | [3d07651a47](https://linux-hardware.org/?probe=3d07651a47) | Apr 24, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [d9429d7e06](https://linux-hardware.org/?probe=d9429d7e06) | Apr 23, 2023 |
| Lenovo        | ThinkPad T440s 20ARS1BH0... | Notebook    | [b76462c15b](https://linux-hardware.org/?probe=b76462c15b) | Apr 23, 2023 |
| Dell          | 03NVJ6 A01                  | Desktop     | [8db1376917](https://linux-hardware.org/?probe=8db1376917) | Apr 23, 2023 |
| Pegatron      | 2AB5                        | Desktop     | [5f771d8ee5](https://linux-hardware.org/?probe=5f771d8ee5) | Apr 23, 2023 |
| Unknown       | G41                         | Desktop     | [cbe978cc34](https://linux-hardware.org/?probe=cbe978cc34) | Apr 23, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [49a0b005f8](https://linux-hardware.org/?probe=49a0b005f8) | Apr 23, 2023 |
| MSI           | GP62 7RD                    | Notebook    | [277bb2d2e3](https://linux-hardware.org/?probe=277bb2d2e3) | Apr 23, 2023 |
| Acer          | AOD270                      | Notebook    | [d7d653d3d6](https://linux-hardware.org/?probe=d7d653d3d6) | Apr 23, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [25ee911879](https://linux-hardware.org/?probe=25ee911879) | Apr 23, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [468824c4d9](https://linux-hardware.org/?probe=468824c4d9) | Apr 23, 2023 |
| Gigabyte      | B760M GAMING X AX DDR4      | Desktop     | [a68d32d442](https://linux-hardware.org/?probe=a68d32d442) | Apr 23, 2023 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [401f407dae](https://linux-hardware.org/?probe=401f407dae) | Apr 23, 2023 |
| HP            | Laptop 14-em0xxx            | Notebook    | [55ea4ded18](https://linux-hardware.org/?probe=55ea4ded18) | Apr 22, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | Desktop     | [3c3719b07f](https://linux-hardware.org/?probe=3c3719b07f) | Apr 22, 2023 |
| Dell          | 0F373D A00                  | Desktop     | [206de0188d](https://linux-hardware.org/?probe=206de0188d) | Apr 22, 2023 |
| Lenovo        | B590 62743NG                | Notebook    | [ca0be4b423](https://linux-hardware.org/?probe=ca0be4b423) | Apr 22, 2023 |
| Lenovo        | B590 62743NG                | Notebook    | [74e38a8db9](https://linux-hardware.org/?probe=74e38a8db9) | Apr 22, 2023 |
| Dell          | 03NVJ6 A01                  | Desktop     | [e60b9070a6](https://linux-hardware.org/?probe=e60b9070a6) | Apr 22, 2023 |
| ASUSTek       | M5A78L LE                   | Desktop     | [b19724085f](https://linux-hardware.org/?probe=b19724085f) | Apr 21, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [4dc6862db9](https://linux-hardware.org/?probe=4dc6862db9) | Apr 21, 2023 |
| Lenovo        | IdeaPadFlex 6-14IKB 81EM    | Convertible | [0a5da1a9a0](https://linux-hardware.org/?probe=0a5da1a9a0) | Apr 21, 2023 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [570077aa64](https://linux-hardware.org/?probe=570077aa64) | Apr 21, 2023 |
| AIERXUAN      | XIAOXUAN Pro                | Notebook    | [e472034313](https://linux-hardware.org/?probe=e472034313) | Apr 21, 2023 |
| AIERXUAN      | XIAOXUAN Pro                | Notebook    | [e500ddd5d9](https://linux-hardware.org/?probe=e500ddd5d9) | Apr 21, 2023 |
| Dell          | Inspiron 3531               | Notebook    | [6222a9aa08](https://linux-hardware.org/?probe=6222a9aa08) | Apr 21, 2023 |
| Gigabyte      | B650M DS3H                  | Desktop     | [de196a2cfa](https://linux-hardware.org/?probe=de196a2cfa) | Apr 21, 2023 |
| Microsoft     | Surface Book                | Tablet      | [13c23678aa](https://linux-hardware.org/?probe=13c23678aa) | Apr 21, 2023 |
| MSI           | GS73VR 7RF                  | Notebook    | [2eb85cc7fe](https://linux-hardware.org/?probe=2eb85cc7fe) | Apr 20, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [d428839f7c](https://linux-hardware.org/?probe=d428839f7c) | Apr 20, 2023 |
| HP            | 2ADE                        | Desktop     | [1a3d108a58](https://linux-hardware.org/?probe=1a3d108a58) | Apr 20, 2023 |
| HP            | 8054                        | Desktop     | [0f2c12c877](https://linux-hardware.org/?probe=0f2c12c877) | Apr 20, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [7d380bf016](https://linux-hardware.org/?probe=7d380bf016) | Apr 20, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [7029b5ee48](https://linux-hardware.org/?probe=7029b5ee48) | Apr 20, 2023 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [9093d27c30](https://linux-hardware.org/?probe=9093d27c30) | Apr 19, 2023 |
| Notebook      | NL40_50CU                   | Notebook    | [069a675d2a](https://linux-hardware.org/?probe=069a675d2a) | Apr 19, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [bb0be3d9e3](https://linux-hardware.org/?probe=bb0be3d9e3) | Apr 19, 2023 |
| Notebook      | NL40_50CU                   | Notebook    | [e58c3ad9d7](https://linux-hardware.org/?probe=e58c3ad9d7) | Apr 19, 2023 |
| Lenovo        | SHARKBAY 31900058 STD or... | Desktop     | [1331c6ef06](https://linux-hardware.org/?probe=1331c6ef06) | Apr 19, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [65eb0fa6be](https://linux-hardware.org/?probe=65eb0fa6be) | Apr 19, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [c36b1a5778](https://linux-hardware.org/?probe=c36b1a5778) | Apr 19, 2023 |
| Apple         | Mac-F2268DC8                | All in one  | [86e2d42f73](https://linux-hardware.org/?probe=86e2d42f73) | Apr 19, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | Notebook    | [1548cc4309](https://linux-hardware.org/?probe=1548cc4309) | Apr 19, 2023 |
| Notebook      | NL40_50CU                   | Notebook    | [85c7be8d12](https://linux-hardware.org/?probe=85c7be8d12) | Apr 19, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [2a7fe6d74b](https://linux-hardware.org/?probe=2a7fe6d74b) | Apr 18, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [be92b53515](https://linux-hardware.org/?probe=be92b53515) | Apr 18, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [7da02a75b5](https://linux-hardware.org/?probe=7da02a75b5) | Apr 18, 2023 |
| ASL           | BayTrail JHS773             | Desktop     | [3a5977ad04](https://linux-hardware.org/?probe=3a5977ad04) | Apr 18, 2023 |
| Dell          | 0T656F A02                  | Desktop     | [0d291f14a1](https://linux-hardware.org/?probe=0d291f14a1) | Apr 18, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [119560d8db](https://linux-hardware.org/?probe=119560d8db) | Apr 17, 2023 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [79029817b8](https://linux-hardware.org/?probe=79029817b8) | Apr 17, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [a99920ebba](https://linux-hardware.org/?probe=a99920ebba) | Apr 17, 2023 |
| Acer          | Aspire E5-574               | Notebook    | [2f60207985](https://linux-hardware.org/?probe=2f60207985) | Apr 17, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [307e22b0d6](https://linux-hardware.org/?probe=307e22b0d6) | Apr 17, 2023 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [895f57e6d5](https://linux-hardware.org/?probe=895f57e6d5) | Apr 17, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [b2311e7cac](https://linux-hardware.org/?probe=b2311e7cac) | Apr 17, 2023 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [b9d869fe6b](https://linux-hardware.org/?probe=b9d869fe6b) | Apr 16, 2023 |
| Dell          | Vostro 3580                 | Notebook    | [b7d9953b54](https://linux-hardware.org/?probe=b7d9953b54) | Apr 16, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [f146ce9da7](https://linux-hardware.org/?probe=f146ce9da7) | Apr 16, 2023 |
| Apple         | MacBookPro5,3               | Notebook    | [ea8d83a743](https://linux-hardware.org/?probe=ea8d83a743) | Apr 16, 2023 |
| Lenovo        | ThinkPad P52s 20LCS1DU01    | Notebook    | [3fc78b3451](https://linux-hardware.org/?probe=3fc78b3451) | Apr 16, 2023 |
| HONOR         | BBR-WAX9                    | Notebook    | [a56688fd70](https://linux-hardware.org/?probe=a56688fd70) | Apr 16, 2023 |
| HONOR         | BBR-WAX9                    | Notebook    | [798405022f](https://linux-hardware.org/?probe=798405022f) | Apr 16, 2023 |
| AZW           | SEi                         | Notebook    | [a382976bf2](https://linux-hardware.org/?probe=a382976bf2) | Apr 15, 2023 |
| AZW           | SEi                         | Notebook    | [980b83cf5e](https://linux-hardware.org/?probe=980b83cf5e) | Apr 15, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [2b6f0394d7](https://linux-hardware.org/?probe=2b6f0394d7) | Apr 15, 2023 |
| Acer          | Aspire ES1-731G             | Notebook    | [1ef0f89c83](https://linux-hardware.org/?probe=1ef0f89c83) | Apr 15, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [ba3d9dd7e7](https://linux-hardware.org/?probe=ba3d9dd7e7) | Apr 15, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [506ba2605a](https://linux-hardware.org/?probe=506ba2605a) | Apr 15, 2023 |
| Gigabyte      | GA-MA74GM-S2H               | Desktop     | [c7568482a9](https://linux-hardware.org/?probe=c7568482a9) | Apr 15, 2023 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [b66c208e18](https://linux-hardware.org/?probe=b66c208e18) | Apr 15, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [2ca7c3fccc](https://linux-hardware.org/?probe=2ca7c3fccc) | Apr 15, 2023 |
| Intel         | H61                         | Desktop     | [81c7094e68](https://linux-hardware.org/?probe=81c7094e68) | Apr 15, 2023 |
| Lenovo        | ThinkPad T430s 2352CTO      | Notebook    | [a4c5130b84](https://linux-hardware.org/?probe=a4c5130b84) | Apr 15, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [e122e8dab8](https://linux-hardware.org/?probe=e122e8dab8) | Apr 15, 2023 |
| MSI           | B75MA-E33                   | Desktop     | [d50de3a52c](https://linux-hardware.org/?probe=d50de3a52c) | Apr 14, 2023 |
| QIYIDA        | X99-H9 V2.0                 | Desktop     | [fcfa1ed488](https://linux-hardware.org/?probe=fcfa1ed488) | Apr 14, 2023 |
| Biostar       | TZ75B                       | Desktop     | [c6720e2db2](https://linux-hardware.org/?probe=c6720e2db2) | Apr 14, 2023 |
| Foxconn       | G31MVP FAB:1.0              | Desktop     | [41eac5ca2f](https://linux-hardware.org/?probe=41eac5ca2f) | Apr 14, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [e9c2f8d5ba](https://linux-hardware.org/?probe=e9c2f8d5ba) | Apr 14, 2023 |
| HP            | 8430 1000                   | All in one  | [b813f95c6f](https://linux-hardware.org/?probe=b813f95c6f) | Apr 14, 2023 |
| HP            | 8430 1000                   | All in one  | [59572d294b](https://linux-hardware.org/?probe=59572d294b) | Apr 14, 2023 |
| Positivo      | Q4128C-S                    | Notebook    | [8dc2eb7738](https://linux-hardware.org/?probe=8dc2eb7738) | Apr 14, 2023 |
| Intel         | H61                         | Desktop     | [8aeeb449f8](https://linux-hardware.org/?probe=8aeeb449f8) | Apr 14, 2023 |
| ASRock        | B550 Steel Legend           | Desktop     | [9da868694f](https://linux-hardware.org/?probe=9da868694f) | Apr 14, 2023 |
| HP            | EliteBook 830 G6            | Notebook    | [75ce029800](https://linux-hardware.org/?probe=75ce029800) | Apr 13, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [4267100894](https://linux-hardware.org/?probe=4267100894) | Apr 13, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [5e9f89e556](https://linux-hardware.org/?probe=5e9f89e556) | Apr 13, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [9e6cfba525](https://linux-hardware.org/?probe=9e6cfba525) | Apr 13, 2023 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | Desktop     | [d72e78c1b0](https://linux-hardware.org/?probe=d72e78c1b0) | Apr 13, 2023 |
| Acer          | Aspire E5-771G              | Notebook    | [504d600530](https://linux-hardware.org/?probe=504d600530) | Apr 13, 2023 |
| HP            | Compaq Presario F700        | Notebook    | [2ae0d7557b](https://linux-hardware.org/?probe=2ae0d7557b) | Apr 13, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [ac4059b403](https://linux-hardware.org/?probe=ac4059b403) | Apr 13, 2023 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [6f7e9a6bb2](https://linux-hardware.org/?probe=6f7e9a6bb2) | Apr 13, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [27bfaf568a](https://linux-hardware.org/?probe=27bfaf568a) | Apr 12, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [653a25793d](https://linux-hardware.org/?probe=653a25793d) | Apr 12, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [dccecbecf9](https://linux-hardware.org/?probe=dccecbecf9) | Apr 12, 2023 |
| Acer          | Aspire 5742G                | Notebook    | [878333e620](https://linux-hardware.org/?probe=878333e620) | Apr 12, 2023 |
| Acer          | Aspire A315-56              | Notebook    | [b504683b39](https://linux-hardware.org/?probe=b504683b39) | Apr 12, 2023 |
| Acer          | Aspire A315-56              | Notebook    | [8b8d053221](https://linux-hardware.org/?probe=8b8d053221) | Apr 12, 2023 |
| Toshiba       | Satellite C650D             | Notebook    | [fb8b24d111](https://linux-hardware.org/?probe=fb8b24d111) | Apr 12, 2023 |
| Gigabyte      | EX58-EXTREME                | Desktop     | [82a946e356](https://linux-hardware.org/?probe=82a946e356) | Apr 12, 2023 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [1627e0654a](https://linux-hardware.org/?probe=1627e0654a) | Apr 11, 2023 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [57aa7d103d](https://linux-hardware.org/?probe=57aa7d103d) | Apr 11, 2023 |
| ASUSTek       | P5K                         | Desktop     | [36bc294c5b](https://linux-hardware.org/?probe=36bc294c5b) | Apr 11, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [a2aa745e5c](https://linux-hardware.org/?probe=a2aa745e5c) | Apr 10, 2023 |
| Apple         | MacBookPro14,2              | Notebook    | [1bc09aed8a](https://linux-hardware.org/?probe=1bc09aed8a) | Apr 10, 2023 |
| Dell          | XPS 13 9343                 | Notebook    | [f847287142](https://linux-hardware.org/?probe=f847287142) | Apr 09, 2023 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [5c0467f4cb](https://linux-hardware.org/?probe=5c0467f4cb) | Apr 09, 2023 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [f410666614](https://linux-hardware.org/?probe=f410666614) | Apr 09, 2023 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [a651483f3c](https://linux-hardware.org/?probe=a651483f3c) | Apr 07, 2023 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [c871e7c68b](https://linux-hardware.org/?probe=c871e7c68b) | Apr 07, 2023 |
| Thomson       | WWNEO14C-4BK32F             | Notebook    | [8b461d224b](https://linux-hardware.org/?probe=8b461d224b) | Apr 06, 2023 |
| Quanta        | XV1                         | All in one  | [7cce1c6f6f](https://linux-hardware.org/?probe=7cce1c6f6f) | Apr 06, 2023 |
| MSI           | B75MA-E33                   | Desktop     | [27e5e2df0d](https://linux-hardware.org/?probe=27e5e2df0d) | Apr 06, 2023 |
| Dell          | 0GY6Y8 A01                  | Desktop     | [ecba971f16](https://linux-hardware.org/?probe=ecba971f16) | Apr 06, 2023 |
| HP            | ProBook 4540s               | Notebook    | [02754e47f3](https://linux-hardware.org/?probe=02754e47f3) | Apr 05, 2023 |
| Acer          | Aspire 5742G                | Notebook    | [5363e4031e](https://linux-hardware.org/?probe=5363e4031e) | Apr 05, 2023 |
| ASUSTek       | H87-PRO                     | Desktop     | [085dc66a77](https://linux-hardware.org/?probe=085dc66a77) | Apr 05, 2023 |
| HP            | Notebook                    | Notebook    | [4ac4839ccd](https://linux-hardware.org/?probe=4ac4839ccd) | Apr 05, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [5a864191a9](https://linux-hardware.org/?probe=5a864191a9) | Apr 05, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [bb24498044](https://linux-hardware.org/?probe=bb24498044) | Apr 05, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [68d14e873f](https://linux-hardware.org/?probe=68d14e873f) | Apr 05, 2023 |
| eMachines     | MCP61PM-GM                  | Desktop     | [dc35ec4564](https://linux-hardware.org/?probe=dc35ec4564) | Apr 04, 2023 |
| Google        | Cyan                        | Notebook    | [f02aa2a210](https://linux-hardware.org/?probe=f02aa2a210) | Apr 04, 2023 |
| Gigabyte      | H410M S2 V3                 | Desktop     | [fdff0f112e](https://linux-hardware.org/?probe=fdff0f112e) | Apr 04, 2023 |
| HP            | 82B5                        | All in one  | [59fe255866](https://linux-hardware.org/?probe=59fe255866) | Apr 04, 2023 |
| Medion        | MS-7707                     | Desktop     | [c490d9dc74](https://linux-hardware.org/?probe=c490d9dc74) | Apr 04, 2023 |
| eMachines     | MCP61PM-GM                  | Desktop     | [59f9325843](https://linux-hardware.org/?probe=59f9325843) | Apr 03, 2023 |
| Toshiba       | Satellite C650              | Notebook    | [190547d5cd](https://linux-hardware.org/?probe=190547d5cd) | Apr 03, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [e05fcde338](https://linux-hardware.org/?probe=e05fcde338) | Apr 03, 2023 |
| Acer          | Veriton X4610G              | Desktop     | [49b3c45306](https://linux-hardware.org/?probe=49b3c45306) | Apr 03, 2023 |
| Dell          | Latitude E6430              | Notebook    | [5c205ea646](https://linux-hardware.org/?probe=5c205ea646) | Apr 03, 2023 |
| Fujitsu       | LIFEBOOK T935               | Notebook    | [1cc4178b9a](https://linux-hardware.org/?probe=1cc4178b9a) | Apr 02, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [f78d5a9d04](https://linux-hardware.org/?probe=f78d5a9d04) | Apr 02, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [45086032e1](https://linux-hardware.org/?probe=45086032e1) | Apr 02, 2023 |
| Notebook      | NJ50GU                      | Notebook    | [91e860cd94](https://linux-hardware.org/?probe=91e860cd94) | Apr 02, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [ea4626fdcc](https://linux-hardware.org/?probe=ea4626fdcc) | Apr 02, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [118effffda](https://linux-hardware.org/?probe=118effffda) | Apr 02, 2023 |
| Dell          | 0D883F A04                  | Desktop     | [5bdaaa0d23](https://linux-hardware.org/?probe=5bdaaa0d23) | Apr 02, 2023 |
| Lenovo        | V570 1066EDG                | Notebook    | [8a8a256b79](https://linux-hardware.org/?probe=8a8a256b79) | Apr 02, 2023 |
| Fujitsu       | STYLISTIC Q508              | Tablet      | [50862798b5](https://linux-hardware.org/?probe=50862798b5) | Apr 02, 2023 |
| Fujitsu       | STYLISTIC Q508              | Tablet      | [1340f929dd](https://linux-hardware.org/?probe=1340f929dd) | Apr 02, 2023 |
| Monster       | HUMA H4 V5.2                | Notebook    | [fdd74dbc8c](https://linux-hardware.org/?probe=fdd74dbc8c) | Apr 02, 2023 |
| Lenovo        | ThinkPad 10 20C3S0Q200      | Tablet      | [e014609915](https://linux-hardware.org/?probe=e014609915) | Apr 01, 2023 |
| Pegatron      | 2ACF                        | Desktop     | [c015b7fd50](https://linux-hardware.org/?probe=c015b7fd50) | Apr 01, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [644ab9aa21](https://linux-hardware.org/?probe=644ab9aa21) | Apr 01, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [61b490cae8](https://linux-hardware.org/?probe=61b490cae8) | Apr 01, 2023 |
| Lenovo        | ThinkPad 10 20C3S0Q200      | Tablet      | [9ee9bc67cf](https://linux-hardware.org/?probe=9ee9bc67cf) | Apr 01, 2023 |
| Medion        | H61H2-LM3                   | Desktop     | [1fb4c6ac6a](https://linux-hardware.org/?probe=1fb4c6ac6a) | Apr 01, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [2132a3308c](https://linux-hardware.org/?probe=2132a3308c) | Apr 01, 2023 |
| Acer          | Predator G3-605             | Desktop     | [eb21663788](https://linux-hardware.org/?probe=eb21663788) | Apr 01, 2023 |
| Medion        | H61H2-LM3                   | Desktop     | [80bb5bbf28](https://linux-hardware.org/?probe=80bb5bbf28) | Apr 01, 2023 |
| Lenovo        | ThinkPad T410 2518P9G       | Notebook    | [4f74fa6cd2](https://linux-hardware.org/?probe=4f74fa6cd2) | Apr 01, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [1fa4ec7b05](https://linux-hardware.org/?probe=1fa4ec7b05) | Apr 01, 2023 |
| Medion        | H61H2-LM3                   | Desktop     | [2e79b95cb4](https://linux-hardware.org/?probe=2e79b95cb4) | Apr 01, 2023 |
| ASUSTek       | T100TA                      | Notebook    | [1f0b0c32ca](https://linux-hardware.org/?probe=1f0b0c32ca) | Apr 01, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [af258dcd36](https://linux-hardware.org/?probe=af258dcd36) | Mar 31, 2023 |
| ASUSTek       | X450LD                      | Notebook    | [1ca0cdc1e8](https://linux-hardware.org/?probe=1ca0cdc1e8) | Mar 31, 2023 |
| Dell          | 0K240Y A02                  | Desktop     | [ca6aacf14e](https://linux-hardware.org/?probe=ca6aacf14e) | Mar 31, 2023 |
| Positivo      | S14SL01                     | Notebook    | [e1c79f71b7](https://linux-hardware.org/?probe=e1c79f71b7) | Mar 30, 2023 |
| Dell          | 09M8Y8 A01                  | Desktop     | [2c13e40cd2](https://linux-hardware.org/?probe=2c13e40cd2) | Mar 30, 2023 |
| ASUSTek       | Benicia                     | Desktop     | [7332efabad](https://linux-hardware.org/?probe=7332efabad) | Mar 30, 2023 |
| HP            | kip                         | Notebook    | [fe84eac39e](https://linux-hardware.org/?probe=fe84eac39e) | Mar 30, 2023 |
| Positivo      | Q232A                       | Notebook    | [2282c5ce96](https://linux-hardware.org/?probe=2282c5ce96) | Mar 30, 2023 |
| Apple         | Mac-F2268DC8                | All in one  | [0e8950a217](https://linux-hardware.org/?probe=0e8950a217) | Mar 30, 2023 |
| Positivo      | Q232A                       | Notebook    | [98e6b249af](https://linux-hardware.org/?probe=98e6b249af) | Mar 29, 2023 |
| HOUTER        | ORO-PC                      | Desktop     | [9547c4bdac](https://linux-hardware.org/?probe=9547c4bdac) | Mar 29, 2023 |
| Acer          | FIH57                       | All in one  | [7a6b0e67f0](https://linux-hardware.org/?probe=7a6b0e67f0) | Mar 29, 2023 |
| Dell          | Precision M4500             | Notebook    | [cf7e033a17](https://linux-hardware.org/?probe=cf7e033a17) | Mar 29, 2023 |
| Dell          | Latitude 7430               | Notebook    | [fdef205301](https://linux-hardware.org/?probe=fdef205301) | Mar 29, 2023 |
| Dell          | Latitude 3590               | Notebook    | [9b5971401c](https://linux-hardware.org/?probe=9b5971401c) | Mar 29, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [a927671ce2](https://linux-hardware.org/?probe=a927671ce2) | Mar 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [ebf2728d28](https://linux-hardware.org/?probe=ebf2728d28) | Mar 29, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [422e4056ea](https://linux-hardware.org/?probe=422e4056ea) | Mar 28, 2023 |
| MSI           | B560M-A PRO                 | Desktop     | [62bfea11fe](https://linux-hardware.org/?probe=62bfea11fe) | Mar 28, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [c97dbb0917](https://linux-hardware.org/?probe=c97dbb0917) | Mar 28, 2023 |
| Thomson       | WWNEO14C-4BK32F             | Notebook    | [90fa9585c9](https://linux-hardware.org/?probe=90fa9585c9) | Mar 28, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [ccef379a7f](https://linux-hardware.org/?probe=ccef379a7f) | Mar 28, 2023 |
| ASRock        | Z68 Pro3-M                  | Desktop     | [60f0809fbf](https://linux-hardware.org/?probe=60f0809fbf) | Mar 28, 2023 |
| Toshiba       | Satellite C55-A-1J8         | Notebook    | [c6ba40cd5c](https://linux-hardware.org/?probe=c6ba40cd5c) | Mar 27, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [dcbcf69a04](https://linux-hardware.org/?probe=dcbcf69a04) | Mar 27, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [dd242e4ae3](https://linux-hardware.org/?probe=dd242e4ae3) | Mar 27, 2023 |
| Dell          | 0J8H4R A00                  | Desktop     | [63d85fd315](https://linux-hardware.org/?probe=63d85fd315) | Mar 27, 2023 |
| Dell          | Inspiron 5555               | Notebook    | [cf226d028d](https://linux-hardware.org/?probe=cf226d028d) | Mar 27, 2023 |
| HP            | 8430 1000                   | All in one  | [c0d9a96bbf](https://linux-hardware.org/?probe=c0d9a96bbf) | Mar 27, 2023 |
| Lenovo        | 11061GG ThinkServer TS13... | Desktop     | [174e514c30](https://linux-hardware.org/?probe=174e514c30) | Mar 26, 2023 |
| Packard Be... | MCP73PV                     | Desktop     | [87d1fd7511](https://linux-hardware.org/?probe=87d1fd7511) | Mar 26, 2023 |
| Dell          | XPS 13 9365                 | Convertible | [05ecadea38](https://linux-hardware.org/?probe=05ecadea38) | Mar 26, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [76fc7291a6](https://linux-hardware.org/?probe=76fc7291a6) | Mar 26, 2023 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [c322e1c537](https://linux-hardware.org/?probe=c322e1c537) | Mar 26, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [7fa1fc4759](https://linux-hardware.org/?probe=7fa1fc4759) | Mar 26, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [cca501adf9](https://linux-hardware.org/?probe=cca501adf9) | Mar 26, 2023 |
| Lenovo        | ThinkPad Edge E530c 3366... | Notebook    | [b4787579d2](https://linux-hardware.org/?probe=b4787579d2) | Mar 25, 2023 |
| HP            | Compaq 6730s                | Notebook    | [ca30390612](https://linux-hardware.org/?probe=ca30390612) | Mar 25, 2023 |
| AZW           | MINI S                      | Desktop     | [f3381963ae](https://linux-hardware.org/?probe=f3381963ae) | Mar 25, 2023 |
| ASRock        | AB350 Gaming K4             | Desktop     | [ecc09c1362](https://linux-hardware.org/?probe=ecc09c1362) | Mar 25, 2023 |
| WEIPAI        | S15                         | Notebook    | [e6a15d7fa9](https://linux-hardware.org/?probe=e6a15d7fa9) | Mar 25, 2023 |
| HP            | Stream Notebook             | Notebook    | [b1ae4b8667](https://linux-hardware.org/?probe=b1ae4b8667) | Mar 25, 2023 |
| ASUSTek       | G53SX                       | Notebook    | [ab9ed0121f](https://linux-hardware.org/?probe=ab9ed0121f) | Mar 25, 2023 |
| Dell          | 0D28YY A01                  | Desktop     | [38b08369e7](https://linux-hardware.org/?probe=38b08369e7) | Mar 25, 2023 |
| Dell          | Latitude E5510              | Notebook    | [8a9a1eec2c](https://linux-hardware.org/?probe=8a9a1eec2c) | Mar 24, 2023 |
| Framework     | Laptop                      | Notebook    | [4e1bd28ce3](https://linux-hardware.org/?probe=4e1bd28ce3) | Mar 24, 2023 |
| QIYIDA        | X99-H9 V2.0                 | Desktop     | [ce9cdcc598](https://linux-hardware.org/?probe=ce9cdcc598) | Mar 24, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [628d2ea05c](https://linux-hardware.org/?probe=628d2ea05c) | Mar 24, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [e859e77bc7](https://linux-hardware.org/?probe=e859e77bc7) | Mar 24, 2023 |
| Dell          | Inspiron 5555               | Notebook    | [efab305a00](https://linux-hardware.org/?probe=efab305a00) | Mar 24, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [ce7e17cb45](https://linux-hardware.org/?probe=ce7e17cb45) | Mar 24, 2023 |
| ASRock        | X570 Steel Legend           | Desktop     | [05d4059f59](https://linux-hardware.org/?probe=05d4059f59) | Mar 24, 2023 |
| Acer          | FIH57                       | All in one  | [1f63978352](https://linux-hardware.org/?probe=1f63978352) | Mar 23, 2023 |
| Dell          | Inspiron 3721               | Notebook    | [e992b8f3a0](https://linux-hardware.org/?probe=e992b8f3a0) | Mar 23, 2023 |
| HP            | Pavilion 15                 | Notebook    | [32a0c3ec32](https://linux-hardware.org/?probe=32a0c3ec32) | Mar 23, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [78fab808a1](https://linux-hardware.org/?probe=78fab808a1) | Mar 23, 2023 |
| HP            | Pavilion dv6                | Notebook    | [625fff449a](https://linux-hardware.org/?probe=625fff449a) | Mar 23, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [c83000783a](https://linux-hardware.org/?probe=c83000783a) | Mar 23, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [e8ad290196](https://linux-hardware.org/?probe=e8ad290196) | Mar 23, 2023 |
| Intel         | G41                         | Desktop     | [c9fccfc8c1](https://linux-hardware.org/?probe=c9fccfc8c1) | Mar 22, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [d0b0015eb2](https://linux-hardware.org/?probe=d0b0015eb2) | Mar 22, 2023 |
| Orbsmart      | AW-11L                      | Mini pc     | [f66ed5bf1f](https://linux-hardware.org/?probe=f66ed5bf1f) | Mar 21, 2023 |
| Dell          | Latitude E7240              | Notebook    | [a3e408033c](https://linux-hardware.org/?probe=a3e408033c) | Mar 21, 2023 |
| ASUSTek       | G53SX                       | Notebook    | [a6c90e3ad8](https://linux-hardware.org/?probe=a6c90e3ad8) | Mar 21, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [9409e4e133](https://linux-hardware.org/?probe=9409e4e133) | Mar 20, 2023 |
| Acer          | Revo RL80                   | Desktop     | [23ee51b834](https://linux-hardware.org/?probe=23ee51b834) | Mar 20, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [93ae4afbbc](https://linux-hardware.org/?probe=93ae4afbbc) | Mar 20, 2023 |
| Dell          | Inspiron 5405               | Notebook    | [bb59d0b5e9](https://linux-hardware.org/?probe=bb59d0b5e9) | Mar 20, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [e7344d03c0](https://linux-hardware.org/?probe=e7344d03c0) | Mar 20, 2023 |
| Apple         | Mac-F2208EC8                | Mini pc     | [4b47e3ed6c](https://linux-hardware.org/?probe=4b47e3ed6c) | Mar 20, 2023 |
| MSI           | B75MA-E33                   | Desktop     | [cddf0b016f](https://linux-hardware.org/?probe=cddf0b016f) | Mar 20, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [75996f8bcf](https://linux-hardware.org/?probe=75996f8bcf) | Mar 19, 2023 |
| HP            | 158A                        | Desktop     | [61467de4d5](https://linux-hardware.org/?probe=61467de4d5) | Mar 19, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [2b86166550](https://linux-hardware.org/?probe=2b86166550) | Mar 19, 2023 |
| Dell          | Inspiron 5423               | Notebook    | [70f51cbfcb](https://linux-hardware.org/?probe=70f51cbfcb) | Mar 19, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [f0f20a06ef](https://linux-hardware.org/?probe=f0f20a06ef) | Mar 19, 2023 |
| Acer          | Aspire M3-581G              | Notebook    | [1434607f7e](https://linux-hardware.org/?probe=1434607f7e) | Mar 19, 2023 |
| Microtech     | CoreBook                    | Notebook    | [d50c0297a6](https://linux-hardware.org/?probe=d50c0297a6) | Mar 19, 2023 |
| HP            | 2B01                        | Desktop     | [1a096f9b36](https://linux-hardware.org/?probe=1a096f9b36) | Mar 19, 2023 |
| Lenovo        | ThinkPad X260 20F600A2MZ    | Notebook    | [5c59b55c2a](https://linux-hardware.org/?probe=5c59b55c2a) | Mar 19, 2023 |
| Lenovo        | ThinkPad T420 4180RK8       | Notebook    | [752373923e](https://linux-hardware.org/?probe=752373923e) | Mar 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [ee8b155a83](https://linux-hardware.org/?probe=ee8b155a83) | Mar 18, 2023 |
| Quanta        | XV1                         | All in one  | [2bbbb73d41](https://linux-hardware.org/?probe=2bbbb73d41) | Mar 18, 2023 |
| MSI           | B75MA-E33                   | Desktop     | [314245636a](https://linux-hardware.org/?probe=314245636a) | Mar 18, 2023 |
| Dell          | Inspiron 3721               | Notebook    | [c7b5ea67bb](https://linux-hardware.org/?probe=c7b5ea67bb) | Mar 18, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [211a71ed78](https://linux-hardware.org/?probe=211a71ed78) | Mar 18, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | Desktop     | [5f4a932bcd](https://linux-hardware.org/?probe=5f4a932bcd) | Mar 18, 2023 |
| ASUSTek       | K52Jc                       | Notebook    | [07dc0a0959](https://linux-hardware.org/?probe=07dc0a0959) | Mar 18, 2023 |
| ASUSTek       | K52Jc                       | Notebook    | [f61ec5ce9f](https://linux-hardware.org/?probe=f61ec5ce9f) | Mar 18, 2023 |
| HP            | 83E1                        | Desktop     | [2a1ade4f84](https://linux-hardware.org/?probe=2a1ade4f84) | Mar 17, 2023 |
| Dell          | 0D28YY A01                  | Desktop     | [76b31023a4](https://linux-hardware.org/?probe=76b31023a4) | Mar 17, 2023 |
| ASUSTek       | G53SX                       | Notebook    | [901e03fa6e](https://linux-hardware.org/?probe=901e03fa6e) | Mar 17, 2023 |
| ASUSTek       | G53SX                       | Notebook    | [a012da47e9](https://linux-hardware.org/?probe=a012da47e9) | Mar 17, 2023 |
| HP            | Pavilion dm1                | Notebook    | [8707341105](https://linux-hardware.org/?probe=8707341105) | Mar 16, 2023 |
| Alienware     | 15 R3                       | Notebook    | [c1f4b90efb](https://linux-hardware.org/?probe=c1f4b90efb) | Mar 16, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [a029e62352](https://linux-hardware.org/?probe=a029e62352) | Mar 16, 2023 |
| HP            | 158A                        | Desktop     | [4a023a55d8](https://linux-hardware.org/?probe=4a023a55d8) | Mar 16, 2023 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [06dd580c2e](https://linux-hardware.org/?probe=06dd580c2e) | Mar 16, 2023 |
| Google        | Babymega                    | Notebook    | [beead110bb](https://linux-hardware.org/?probe=beead110bb) | Mar 16, 2023 |
| Google        | Babymega                    | Notebook    | [0a45acf149](https://linux-hardware.org/?probe=0a45acf149) | Mar 16, 2023 |
| Acer          | Aspire 5736Z                | Notebook    | [d9e1bb3da7](https://linux-hardware.org/?probe=d9e1bb3da7) | Mar 16, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [3388dd991a](https://linux-hardware.org/?probe=3388dd991a) | Mar 15, 2023 |
| AZW           | GTR V01                     | Mini pc     | [98d84656e8](https://linux-hardware.org/?probe=98d84656e8) | Mar 15, 2023 |
| Clevo         | W251EFQ/W270EFQ             | Notebook    | [f5175006b7](https://linux-hardware.org/?probe=f5175006b7) | Mar 15, 2023 |
| Clevo         | W251EFQ/W270EFQ             | Notebook    | [9565625dc4](https://linux-hardware.org/?probe=9565625dc4) | Mar 15, 2023 |
| Lenovo        | ThinkPad T430 23492D1       | Notebook    | [34e2b05336](https://linux-hardware.org/?probe=34e2b05336) | Mar 14, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [f6a3a68640](https://linux-hardware.org/?probe=f6a3a68640) | Mar 14, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [cbb20e87cb](https://linux-hardware.org/?probe=cbb20e87cb) | Mar 14, 2023 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | Desktop     | [eb761f4a30](https://linux-hardware.org/?probe=eb761f4a30) | Mar 14, 2023 |
| ASUSTek       | U36SD                       | Notebook    | [74e2dfbbc6](https://linux-hardware.org/?probe=74e2dfbbc6) | Mar 14, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [cc372ccf7d](https://linux-hardware.org/?probe=cc372ccf7d) | Mar 14, 2023 |
| Dell          | Inspiron 5423               | Notebook    | [4987f344f2](https://linux-hardware.org/?probe=4987f344f2) | Mar 14, 2023 |
| QIYIDA        | X99-H9 V2.0                 | Desktop     | [0f440670f2](https://linux-hardware.org/?probe=0f440670f2) | Mar 14, 2023 |
| Gigabyte      | H55M-S2H                    | Desktop     | [55d6288663](https://linux-hardware.org/?probe=55d6288663) | Mar 14, 2023 |
| Google        | Celes                       | Notebook    | [4fd0271747](https://linux-hardware.org/?probe=4fd0271747) | Mar 13, 2023 |
| HP            | 83E1                        | Desktop     | [d286798430](https://linux-hardware.org/?probe=d286798430) | Mar 13, 2023 |
| Soncview      | G41D3C                      | Desktop     | [877ff67a70](https://linux-hardware.org/?probe=877ff67a70) | Mar 13, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [77569b52db](https://linux-hardware.org/?probe=77569b52db) | Mar 13, 2023 |
| Quanta        | XV1                         | All in one  | [930e98f517](https://linux-hardware.org/?probe=930e98f517) | Mar 13, 2023 |
| HP            | Pavilion dv6                | Notebook    | [9d5d0051ea](https://linux-hardware.org/?probe=9d5d0051ea) | Mar 13, 2023 |
| Gigabyte      | H97M-D3H                    | Desktop     | [178af6e35b](https://linux-hardware.org/?probe=178af6e35b) | Mar 12, 2023 |
| HP            | Pavilion 15                 | Notebook    | [d5eb709e13](https://linux-hardware.org/?probe=d5eb709e13) | Mar 12, 2023 |
| HP            | 18E7                        | Desktop     | [2042edf904](https://linux-hardware.org/?probe=2042edf904) | Mar 12, 2023 |
| Toshiba       | PORTEGE X30-D               | Notebook    | [9b7e4e10af](https://linux-hardware.org/?probe=9b7e4e10af) | Mar 12, 2023 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [d777dadd73](https://linux-hardware.org/?probe=d777dadd73) | Mar 12, 2023 |
| Novatech      | 15.6 nSpire Laptop          | Notebook    | [f5814aa2e6](https://linux-hardware.org/?probe=f5814aa2e6) | Mar 12, 2023 |
| Dell          | 0GM819                      | Desktop     | [1db4004d05](https://linux-hardware.org/?probe=1db4004d05) | Mar 12, 2023 |
| Medion        | MS-7707                     | Desktop     | [a0621e0cd1](https://linux-hardware.org/?probe=a0621e0cd1) | Mar 12, 2023 |
| Lenovo        | ThinkPad X270 20HMS1KL0C    | Notebook    | [f27bb76a32](https://linux-hardware.org/?probe=f27bb76a32) | Mar 12, 2023 |
| Gigabyte      | EX58-EXTREME                | Desktop     | [f45a0d4c01](https://linux-hardware.org/?probe=f45a0d4c01) | Mar 12, 2023 |
| Medion        | MS-7707                     | Desktop     | [4c9432026b](https://linux-hardware.org/?probe=4c9432026b) | Mar 12, 2023 |
| Acer          | TravelMate B113             | Notebook    | [e5f001172d](https://linux-hardware.org/?probe=e5f001172d) | Mar 12, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [91da2169aa](https://linux-hardware.org/?probe=91da2169aa) | Mar 12, 2023 |
| Gigabyte      | X670E AORUS XTREME          | Desktop     | [83cb566647](https://linux-hardware.org/?probe=83cb566647) | Mar 12, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [fd63e92774](https://linux-hardware.org/?probe=fd63e92774) | Mar 12, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [6a0426cb65](https://linux-hardware.org/?probe=6a0426cb65) | Mar 12, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [bd0c265909](https://linux-hardware.org/?probe=bd0c265909) | Mar 11, 2023 |
| Acer          | TravelMate B113             | Notebook    | [ba6dc5dcb5](https://linux-hardware.org/?probe=ba6dc5dcb5) | Mar 11, 2023 |
| HP            | Pavilion dv6                | Notebook    | [fca49aa86c](https://linux-hardware.org/?probe=fca49aa86c) | Mar 11, 2023 |
| Acer          | WG43M                       | Desktop     | [5858448536](https://linux-hardware.org/?probe=5858448536) | Mar 11, 2023 |
| Acer          | WG43M                       | Desktop     | [3d562885d0](https://linux-hardware.org/?probe=3d562885d0) | Mar 11, 2023 |
| Clevo         | W251EFQ/W270EFQ             | Notebook    | [daad1ee8d5](https://linux-hardware.org/?probe=daad1ee8d5) | Mar 11, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [4b9462a4ff](https://linux-hardware.org/?probe=4b9462a4ff) | Mar 11, 2023 |
| Dell          | 0T10XW A00                  | Desktop     | [a47baaadde](https://linux-hardware.org/?probe=a47baaadde) | Mar 11, 2023 |
| HP            | 2B3B                        | All in one  | [cb25c51987](https://linux-hardware.org/?probe=cb25c51987) | Mar 11, 2023 |
| ASUSTek       | T100TAM                     | Notebook    | [1d647e564b](https://linux-hardware.org/?probe=1d647e564b) | Mar 10, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [434a8e0e37](https://linux-hardware.org/?probe=434a8e0e37) | Mar 10, 2023 |
| Medion        | Akoya E1318T                | Notebook    | [8b24b109ec](https://linux-hardware.org/?probe=8b24b109ec) | Mar 10, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [6648af3696](https://linux-hardware.org/?probe=6648af3696) | Mar 10, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [807d1626b4](https://linux-hardware.org/?probe=807d1626b4) | Mar 10, 2023 |
| Toshiba       | Satellite L855              | Notebook    | [3b0a7cfbf0](https://linux-hardware.org/?probe=3b0a7cfbf0) | Mar 10, 2023 |
| Toshiba       | Satellite L855              | Notebook    | [08bfa4188e](https://linux-hardware.org/?probe=08bfa4188e) | Mar 10, 2023 |
| HP            | ProBook 4530s               | Notebook    | [e9c9dd943e](https://linux-hardware.org/?probe=e9c9dd943e) | Mar 10, 2023 |
| Dell          | Precision M6700             | Notebook    | [7a02d78344](https://linux-hardware.org/?probe=7a02d78344) | Mar 10, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [565c8963d4](https://linux-hardware.org/?probe=565c8963d4) | Mar 10, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | Notebook    | [99d5f17b22](https://linux-hardware.org/?probe=99d5f17b22) | Mar 09, 2023 |
| Acer          | Aspire M3-581G              | Notebook    | [65b41dc560](https://linux-hardware.org/?probe=65b41dc560) | Mar 09, 2023 |
| HP            | Pavilion TS 15              | Notebook    | [5c0b7a773e](https://linux-hardware.org/?probe=5c0b7a773e) | Mar 09, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [bd1ab8d62d](https://linux-hardware.org/?probe=bd1ab8d62d) | Mar 09, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Zorin_16/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.15.0-56-generic | 229       | 6.02%   |
| 5.11.0-38-generic | 180       | 4.73%   |
| 5.11.0-27-generic | 155       | 4.07%   |
| 5.15.0-46-generic | 152       | 3.99%   |
| 5.15.0-52-generic | 151       | 3.97%   |
| 5.15.0-58-generic | 150       | 3.94%   |
| 5.15.0-67-generic | 142       | 3.73%   |
| 5.15.0-69-generic | 136       | 3.57%   |
| 5.13.0-30-generic | 126       | 3.31%   |
| 5.11.0-40-generic | 124       | 3.26%   |
| 5.13.0-39-generic | 121       | 3.18%   |
| 5.15.0-60-generic | 108       | 2.84%   |
| 5.11.0-41-generic | 108       | 2.84%   |
| 5.11.0-37-generic | 107       | 2.81%   |
| 5.15.0-76-generic | 101       | 2.65%   |
| 5.11.0-43-generic | 101       | 2.65%   |
| 5.15.0-71-generic | 100       | 2.63%   |
| 5.15.0-48-generic | 95        | 2.5%    |
| 5.11.0-34-generic | 94        | 2.47%   |
| 5.13.0-40-generic | 90        | 2.37%   |
| 5.15.0-78-generic | 81        | 2.13%   |
| 5.15.0-53-generic | 81        | 2.13%   |
| 5.15.0-41-generic | 77        | 2.02%   |
| 5.13.0-44-generic | 76        | 2%      |
| 5.13.0-35-generic | 74        | 1.94%   |
| 5.13.0-28-generic | 73        | 1.92%   |
| 5.15.0-73-generic | 68        | 1.79%   |
| 5.13.0-52-generic | 59        | 1.55%   |
| 5.13.0-27-generic | 59        | 1.55%   |
| 5.15.0-72-generic | 58        | 1.52%   |
| 5.13.0-41-generic | 54        | 1.42%   |
| 5.13.0-51-generic | 42        | 1.1%    |
| 5.15.0-43-generic | 40        | 1.05%   |
| 5.11.0-36-generic | 39        | 1.02%   |
| 5.15.0-75-generic | 38        | 1%      |
| 5.15.0-57-generic | 35        | 0.92%   |
| 5.11.0-46-generic | 35        | 0.92%   |
| 5.11.0-44-generic | 34        | 0.89%   |
| 5.13.0-37-generic | 29        | 0.76%   |
| 5.13.0-48-generic | 23        | 0.6%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 1641      | 47.35%  |
| 5.11.0  | 950       | 27.41%  |
| 5.13.0  | 768       | 22.16%  |
| 5.8.0   | 53        | 1.53%   |
| 5.14.0  | 10        | 0.29%   |
| 5.4.0   | 4         | 0.12%   |
| 6.3.2   | 2         | 0.06%   |
| 5.19.12 | 2         | 0.06%   |
| 5.18.15 | 2         | 0.06%   |
| 5.17.5  | 2         | 0.06%   |
| 5.17.1  | 2         | 0.06%   |
| 5.16.0  | 2         | 0.06%   |
| 5.10.0  | 2         | 0.06%   |
| 6.3.1   | 1         | 0.03%   |
| 6.2.7   | 1         | 0.03%   |
| 6.2.16  | 1         | 0.03%   |
| 6.2.14  | 1         | 0.03%   |
| 6.1.8   | 1         | 0.03%   |
| 6.1.7   | 1         | 0.03%   |
| 6.0.9   | 1         | 0.03%   |
| 6.0.8   | 1         | 0.03%   |
| 6.0.19  | 1         | 0.03%   |
| 6.0.0   | 1         | 0.03%   |
| 5.4.180 | 1         | 0.03%   |
| 5.19.9  | 1         | 0.03%   |
| 5.19.6  | 1         | 0.03%   |
| 5.19.2  | 1         | 0.03%   |
| 5.19.14 | 1         | 0.03%   |
| 5.19.1  | 1         | 0.03%   |
| 5.19.0  | 1         | 0.03%   |
| 5.18.6  | 1         | 0.03%   |
| 5.17.9  | 1         | 0.03%   |
| 5.16.5  | 1         | 0.03%   |
| 5.16.14 | 1         | 0.03%   |
| 5.16.12 | 1         | 0.03%   |
| 5.15.49 | 1         | 0.03%   |
| 5.15.24 | 1         | 0.03%   |
| 5.15.13 | 1         | 0.03%   |
| 5.13.18 | 1         | 0.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 1644      | 47.45%  |
| 5.11    | 950       | 27.42%  |
| 5.13    | 769       | 22.19%  |
| 5.8     | 53        | 1.53%   |
| 5.14    | 10        | 0.29%   |
| 5.19    | 8         | 0.23%   |
| 5.4     | 5         | 0.14%   |
| 5.17    | 5         | 0.14%   |
| 5.16    | 5         | 0.14%   |
| 6.0     | 4         | 0.12%   |
| 6.3     | 3         | 0.09%   |
| 6.2     | 3         | 0.09%   |
| 5.18    | 3         | 0.09%   |
| 5.10    | 2         | 0.06%   |
| 6.1     | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 3313      | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 2853      | 85.5%   |
| XFCE       | 443       | 13.28%  |
| Unknown    | 20        | 0.6%    |
| KDE5       | 5         | 0.15%   |
| X-Cinnamon | 4         | 0.12%   |
| Cinnamon   | 3         | 0.09%   |
| Budgie     | 3         | 0.09%   |
| i3         | 2         | 0.06%   |
| Unity      | 1         | 0.03%   |
| MATE       | 1         | 0.03%   |
| LXDE       | 1         | 0.03%   |
| KDE        | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 3266      | 98.05%  |
| Wayland | 56        | 1.68%   |
| Unknown | 7         | 0.21%   |
| Tty     | 2         | 0.06%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2598      | 77.32%  |
| GDM     | 339       | 10.09%  |
| GDM3    | 306       | 9.11%   |
| LightDM | 113       | 3.36%   |
| SDDM    | 2         | 0.06%   |
| TDM     | 1         | 0.03%   |
| LXDM    | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 1320      | 39.66%  |
| de_DE | 307       | 9.22%   |
| en_GB | 229       | 6.88%   |
| pt_BR | 193       | 5.8%    |
| fr_FR | 117       | 3.52%   |
| it_IT | 106       | 3.19%   |
| es_ES | 100       | 3%      |
| en_CA | 88        | 2.64%   |
| en_IN | 84        | 2.52%   |
| pl_PL | 80        | 2.4%    |
| en_AU | 68        | 2.04%   |
| nl_NL | 56        | 1.68%   |
| es_MX | 46        | 1.38%   |
| ru_RU | 44        | 1.32%   |
| en_ZA | 35        | 1.05%   |
| pt_PT | 31        | 0.93%   |
| es_AR | 29        | 0.87%   |
| cs_CZ | 28        | 0.84%   |
| hu_HU | 23        | 0.69%   |
| sv_SE | 21        | 0.63%   |
| tr_TR | 19        | 0.57%   |
| en_NZ | 19        | 0.57%   |
| nl_BE | 17        | 0.51%   |
| fr_BE | 17        | 0.51%   |
| de_CH | 16        | 0.48%   |
| es_CL | 14        | 0.42%   |
| fr_CA | 12        | 0.36%   |
| de_AT | 12        | 0.36%   |
| ja_JP | 11        | 0.33%   |
| es_CO | 11        | 0.33%   |
| nb_NO | 9         | 0.27%   |
| fi_FI | 9         | 0.27%   |
| en_PH | 9         | 0.27%   |
| el_GR | 9         | 0.27%   |
| es_VE | 8         | 0.24%   |
| ar_EG | 8         | 0.24%   |
| es_CR | 7         | 0.21%   |
| sk_SK | 6         | 0.18%   |
| hr_HR | 6         | 0.18%   |
| da_DK | 6         | 0.18%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1921      | 57.27%  |
| BIOS | 1433      | 42.73%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 3107      | 93.25%  |
| Zfs      | 63        | 1.89%   |
| Tmpfs    | 54        | 1.62%   |
| Overlay  | 54        | 1.62%   |
| Btrfs    | 30        | 0.9%    |
| Xfs      | 9         | 0.27%   |
| Ext2     | 8         | 0.24%   |
| Ext3     | 5         | 0.15%   |
| Reiserfs | 1         | 0.03%   |
| Jfs      | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2773      | 82.65%  |
| GPT     | 451       | 13.44%  |
| MBR     | 131       | 3.9%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3231      | 97.26%  |
| Yes       | 91        | 2.74%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2998      | 90.17%  |
| Yes       | 327       | 9.83%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 560       | 16.9%   |
| ASUSTek Computer    | 485       | 14.64%  |
| Dell                | 440       | 13.28%  |
| Lenovo              | 419       | 12.65%  |
| Gigabyte Technology | 194       | 5.86%   |
| Acer                | 164       | 4.95%   |
| MSI                 | 160       | 4.83%   |
| Apple               | 121       | 3.65%   |
| ASRock              | 87        | 2.63%   |
| Toshiba             | 76        | 2.29%   |
| Intel               | 55        | 1.66%   |
| Samsung Electronics | 36        | 1.09%   |
| Unknown             | 36        | 1.09%   |
| Google              | 30        | 0.91%   |
| Sony                | 28        | 0.85%   |
| Fujitsu             | 26        | 0.78%   |
| Microsoft           | 23        | 0.69%   |
| Packard Bell        | 19        | 0.57%   |
| Biostar             | 18        | 0.54%   |
| Positivo            | 17        | 0.51%   |
| Pegatron            | 15        | 0.45%   |
| HUAWEI              | 15        | 0.45%   |
| Foxconn             | 15        | 0.45%   |
| Medion              | 11        | 0.33%   |
| Chuwi               | 11        | 0.33%   |
| Alienware           | 11        | 0.33%   |
| AZW                 | 10        | 0.3%    |
| Notebook            | 8         | 0.24%   |
| GPU Company         | 7         | 0.21%   |
| AMI                 | 7         | 0.21%   |
| Multilaser          | 6         | 0.18%   |
| Gateway             | 6         | 0.18%   |
| Fujitsu Siemens     | 6         | 0.18%   |
| LG Electronics      | 5         | 0.15%   |
| BESSTAR Tech        | 5         | 0.15%   |
| Thomson             | 4         | 0.12%   |
| Razer               | 4         | 0.12%   |
| OEM                 | 4         | 0.12%   |
| Microtech           | 4         | 0.12%   |
| Jumper              | 4         | 0.12%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| Unknown                          | 46        | 1.39%   |
| ASUS All Series                  | 31        | 0.94%   |
| HP Notebook                      | 21        | 0.63%   |
| HP Pavilion Notebook             | 14        | 0.42%   |
| Dell OptiPlex 7010               | 12        | 0.36%   |
| HP 15                            | 10        | 0.3%    |
| MSI MS-7817                      | 8         | 0.24%   |
| HP Pavilion dv7                  | 8         | 0.24%   |
| HP Pavilion dv6                  | 8         | 0.24%   |
| HP Pavilion 15                   | 8         | 0.24%   |
| Dell OptiPlex 790                | 8         | 0.24%   |
| Apple MacBookPro8,1              | 8         | 0.24%   |
| Apple iMac12,1                   | 8         | 0.24%   |
| Lenovo MIIX 320-10ICR 80XF       | 7         | 0.21%   |
| Dell OptiPlex 780                | 7         | 0.21%   |
| Apple iMac12,2                   | 7         | 0.21%   |
| Apple iMac10,1                   | 7         | 0.21%   |
| MSI MS-7C02                      | 6         | 0.18%   |
| Microsoft Surface Pro            | 6         | 0.18%   |
| Gigabyte A320M-S2H               | 6         | 0.18%   |
| Dell OptiPlex 380                | 6         | 0.18%   |
| Dell Latitude E6540              | 6         | 0.18%   |
| ASUS M5A78L-M/USB3               | 6         | 0.18%   |
| Microsoft Surface Pro 4          | 5         | 0.15%   |
| HP ProBook 640 G1                | 5         | 0.15%   |
| HP Pavilion g6                   | 5         | 0.15%   |
| HP Compaq Pro 6300 SFF           | 5         | 0.15%   |
| GPU Company GWTC116-2            | 5         | 0.15%   |
| Gigabyte B450 AORUS M            | 5         | 0.15%   |
| Dell Precision WorkStation T3500 | 5         | 0.15%   |
| Dell OptiPlex 990                | 5         | 0.15%   |
| Dell OptiPlex 3020               | 5         | 0.15%   |
| Dell OptiPlex 3010               | 5         | 0.15%   |
| Dell Latitude E6520              | 5         | 0.15%   |
| Dell Inspiron 15-3567            | 5         | 0.15%   |
| ASUS M5A97 R2.0                  | 5         | 0.15%   |
| Apple MacBookPro12,1             | 5         | 0.15%   |
| Toshiba Satellite C660           | 4         | 0.12%   |
| Toshiba Satellite C55-C          | 4         | 0.12%   |
| MSI MS-7C37                      | 4         | 0.12%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 131       | 3.95%   |
| HP Pavilion           | 117       | 3.53%   |
| Dell Latitude         | 117       | 3.53%   |
| Dell Inspiron         | 117       | 3.53%   |
| Acer Aspire           | 109       | 3.29%   |
| Lenovo IdeaPad        | 107       | 3.23%   |
| Dell OptiPlex         | 85        | 2.57%   |
| HP EliteBook          | 62        | 1.87%   |
| Toshiba Satellite     | 61        | 1.84%   |
| HP Compaq             | 51        | 1.54%   |
| ASUS ROG              | 48        | 1.45%   |
| HP ProBook            | 46        | 1.39%   |
| Unknown               | 46        | 1.39%   |
| ASUS PRIME            | 43        | 1.3%    |
| HP Laptop             | 39        | 1.18%   |
| Lenovo ThinkCentre    | 36        | 1.09%   |
| ASUS VivoBook         | 36        | 1.09%   |
| ASUS TUF              | 33        | 1%      |
| Dell Precision        | 31        | 0.94%   |
| ASUS All              | 31        | 0.94%   |
| HP ENVY               | 29        | 0.88%   |
| Dell XPS              | 29        | 0.88%   |
| Lenovo Yoga           | 26        | 0.78%   |
| Dell Vostro           | 26        | 0.78%   |
| Microsoft Surface     | 23        | 0.69%   |
| HP Notebook           | 21        | 0.63%   |
| HP Stream             | 18        | 0.54%   |
| HP EliteDesk          | 17        | 0.51%   |
| Packard Bell EasyNote | 15        | 0.45%   |
| Apple iMac12          | 15        | 0.45%   |
| ASUS ZenBook          | 13        | 0.39%   |
| HP ProDesk            | 12        | 0.36%   |
| HP OMEN               | 12        | 0.36%   |
| HP 15                 | 12        | 0.36%   |
| Gigabyte B450         | 12        | 0.36%   |
| Fujitsu ESPRIMO       | 12        | 0.36%   |
| ASUS ASUS             | 12        | 0.36%   |
| Lenovo MIIX           | 11        | 0.33%   |
| Dell Studio           | 11        | 0.33%   |
| Lenovo Legion         | 10        | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 287       | 8.66%   |
| 2011    | 283       | 8.54%   |
| 2021    | 278       | 8.39%   |
| 2013    | 268       | 8.09%   |
| 2018    | 262       | 7.91%   |
| 2020    | 252       | 7.61%   |
| 2019    | 234       | 7.06%   |
| 2014    | 226       | 6.82%   |
| 2017    | 210       | 6.34%   |
| 2010    | 189       | 5.7%    |
| 2016    | 180       | 5.43%   |
| 2015    | 165       | 4.98%   |
| 2008    | 142       | 4.29%   |
| 2009    | 117       | 3.53%   |
| 2022    | 91        | 2.75%   |
| 2007    | 76        | 2.29%   |
| 2023    | 23        | 0.69%   |
| 2006    | 21        | 0.63%   |
| 2005    | 6         | 0.18%   |
| Unknown | 3         | 0.09%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 1812      | 54.69%  |
| Desktop     | 1205      | 36.37%  |
| All in one  | 87        | 2.63%   |
| Convertible | 86        | 2.6%    |
| Tablet      | 61        | 1.84%   |
| Mini pc     | 54        | 1.63%   |
| Server      | 8         | 0.24%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 2917      | 87.31%  |
| Enabled  | 424       | 12.69%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3279      | 98.97%  |
| Yes  | 34        | 1.03%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 900       | 26.92%  |
| 3.01-4.0        | 735       | 21.99%  |
| 16.01-24.0      | 573       | 17.14%  |
| 8.01-16.0       | 566       | 16.93%  |
| 32.01-64.0      | 262       | 7.84%   |
| 1.01-2.0        | 156       | 4.67%   |
| 64.01-256.0     | 60        | 1.79%   |
| 24.01-32.0      | 42        | 1.26%   |
| 2.01-3.0        | 42        | 1.26%   |
| 0.51-1.0        | 6         | 0.18%   |
| More than 256.0 | 1         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1377      | 38.21%  |
| 2.01-3.0   | 1180      | 32.74%  |
| 3.01-4.0   | 491       | 13.62%  |
| 4.01-8.0   | 416       | 11.54%  |
| 0.51-1.0   | 63        | 1.75%   |
| 8.01-16.0  | 61        | 1.69%   |
| 16.01-24.0 | 9         | 0.25%   |
| 24.01-32.0 | 4         | 0.11%   |
| 32.01-64.0 | 2         | 0.06%   |
| 0.01-0.5   | 1         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 2163      | 63.88%  |
| 2      | 808       | 23.86%  |
| 3      | 201       | 5.94%   |
| 4      | 98        | 2.89%   |
| 5      | 49        | 1.45%   |
| 6      | 30        | 0.89%   |
| 0      | 15        | 0.44%   |
| 7      | 11        | 0.32%   |
| 8      | 8         | 0.24%   |
| 51     | 1         | 0.03%   |
| 30     | 1         | 0.03%   |
| 11     | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1902      | 57.13%  |
| Yes       | 1427      | 42.87%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2757      | 83.04%  |
| No        | 563       | 16.96%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2639      | 79.34%  |
| No        | 687       | 20.66%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1961      | 58.61%  |
| No        | 1385      | 41.39%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 794       | 23.89%  |
| Germany      | 329       | 9.9%    |
| Brazil       | 215       | 6.47%   |
| UK           | 209       | 6.29%   |
| Italy        | 118       | 3.55%   |
| Canada       | 114       | 3.43%   |
| Spain        | 109       | 3.28%   |
| France       | 108       | 3.25%   |
| Netherlands  | 93        | 2.8%    |
| India        | 87        | 2.62%   |
| Poland       | 78        | 2.35%   |
| Australia    | 69        | 2.08%   |
| Mexico       | 63        | 1.9%    |
| Belgium      | 46        | 1.38%   |
| Russia       | 43        | 1.29%   |
| South Africa | 39        | 1.17%   |
| Sweden       | 38        | 1.14%   |
| Portugal     | 38        | 1.14%   |
| Argentina    | 37        | 1.11%   |
| Switzerland  | 32        | 0.96%   |
| Czechia      | 31        | 0.93%   |
| Austria      | 31        | 0.93%   |
| Turkey       | 29        | 0.87%   |
| Hungary      | 28        | 0.84%   |
| Romania      | 27        | 0.81%   |
| Norway       | 27        | 0.81%   |
| Greece       | 24        | 0.72%   |
| New Zealand  | 21        | 0.63%   |
| Japan        | 20        | 0.6%    |
| Egypt        | 19        | 0.57%   |
| Denmark      | 18        | 0.54%   |
| Colombia     | 18        | 0.54%   |
| Chile        | 18        | 0.54%   |
| Indonesia    | 17        | 0.51%   |
| Finland      | 17        | 0.51%   |
| Malaysia     | 12        | 0.36%   |
| Bulgaria     | 12        | 0.36%   |
| Venezuela    | 11        | 0.33%   |
| Serbia       | 11        | 0.33%   |
| Croatia      | 11        | 0.33%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Berlin            | 29        | 0.84%   |
| Munich            | 25        | 0.72%   |
| Athens            | 20        | 0.58%   |
| Madrid            | 19        | 0.55%   |
| Sydney            | 18        | 0.52%   |
| Rome              | 18        | 0.52%   |
| Sao Paulo         | 17        | 0.49%   |
| Vienna            | 16        | 0.46%   |
| New York          | 16        | 0.46%   |
| Rio de Janeiro    | 15        | 0.43%   |
| Milan             | 14        | 0.4%    |
| Paris             | 13        | 0.38%   |
| Montreal          | 13        | 0.38%   |
| London            | 13        | 0.38%   |
| Hamburg           | 13        | 0.38%   |
| Denver            | 13        | 0.38%   |
| Dallas            | 13        | 0.38%   |
| Johannesburg      | 12        | 0.35%   |
| Cape Town         | 12        | 0.35%   |
| Melbourne         | 11        | 0.32%   |
| Amsterdam         | 11        | 0.32%   |
| Stockholm         | 10        | 0.29%   |
| Salt Lake City    | 10        | 0.29%   |
| Phoenix           | 10        | 0.29%   |
| Perth             | 10        | 0.29%   |
| Moscow            | 10        | 0.29%   |
| Istanbul          | 10        | 0.29%   |
| Delhi             | 10        | 0.29%   |
| Bucharest         | 10        | 0.29%   |
| Bengaluru         | 10        | 0.29%   |
| Valencia          | 9         | 0.26%   |
| Mexico City       | 9         | 0.26%   |
| Krakow            | 9         | 0.26%   |
| Jakarta           | 9         | 0.26%   |
| Houston           | 9         | 0.26%   |
| Frankfurt am Main | 9         | 0.26%   |
| Cairo             | 9         | 0.26%   |
| Buenos Aires      | 9         | 0.26%   |
| Brisbane          | 9         | 0.26%   |
| Bogotá           | 9         | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 708       | 1012   | 15.11%  |
| Samsung Electronics       | 620       | 888    | 13.23%  |
| WDC                       | 609       | 832    | 13%     |
| Toshiba                   | 328       | 419    | 7%      |
| SanDisk                   | 286       | 341    | 6.1%    |
| Unknown                   | 283       | 384    | 6.04%   |
| Kingston                  | 250       | 342    | 5.34%   |
| Crucial                   | 168       | 205    | 3.59%   |
| Hitachi                   | 141       | 189    | 3.01%   |
| Intel                     | 97        | 127    | 2.07%   |
| SK hynix                  | 91        | 108    | 1.94%   |
| HGST                      | 81        | 100    | 1.73%   |
| A-DATA Technology         | 68        | 84     | 1.45%   |
| Micron Technology         | 63        | 73     | 1.34%   |
| China                     | 62        | 74     | 1.32%   |
| Apple                     | 54        | 63     | 1.15%   |
| Intenso                   | 39        | 42     | 0.83%   |
| Silicon Motion            | 35        | 44     | 0.75%   |
| Phison                    | 32        | 36     | 0.68%   |
| PNY                       | 29        | 37     | 0.62%   |
| KIOXIA                    | 29        | 32     | 0.62%   |
| SPCC                      | 28        | 36     | 0.6%    |
| Patriot                   | 25        | 34     | 0.53%   |
| Netac                     | 25        | 28     | 0.53%   |
| Unknown                   | 23        | 26     | 0.49%   |
| GOODRAM                   | 22        | 26     | 0.47%   |
| JMicron Technology        | 20        | 25     | 0.43%   |
| OCZ                       | 18        | 21     | 0.38%   |
| Micron/Crucial Technology | 18        | 22     | 0.38%   |
| Lexar                     | 16        | 16     | 0.34%   |
| Phison Electronics        | 15        | 17     | 0.32%   |
| LITEON                    | 15        | 17     | 0.32%   |
| Team                      | 13        | 16     | 0.28%   |
| Transcend                 | 12        | 29     | 0.26%   |
| Realtek Semiconductor     | 12        | 13     | 0.26%   |
| Maxtor                    | 12        | 16     | 0.26%   |
| KingSpec                  | 12        | 14     | 0.26%   |
| Fujitsu                   | 12        | 13     | 0.26%   |
| LITEONIT                  | 11        | 13     | 0.23%   |
| Hewlett-Packard           | 11        | 15     | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                              | 88        | 1.71%   |
| Unknown MMC Card  64GB                              | 82        | 1.6%    |
| Kingston SA400S37240G 240GB SSD                     | 61        | 1.19%   |
| Seagate ST500DM002-1BD142 500GB                     | 44        | 0.86%   |
| Seagate ST1000LM035-1RK172 1TB                      | 43        | 0.84%   |
| Unknown MMC Card  128GB                             | 37        | 0.72%   |
| Toshiba MQ01ABD100 1TB                              | 37        | 0.72%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 37        | 0.72%   |
| Crucial CT240BX500SSD1 240GB                        | 36        | 0.7%    |
| Samsung SSD 860 EVO 500GB                           | 35        | 0.68%   |
| Kingston SA400S37480G 480GB SSD                     | 35        | 0.68%   |
| Kingston SA400S37120G 120GB SSD                     | 32        | 0.62%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 30        | 0.58%   |
| Unknown SD/MMC/MS PRO 128GB                         | 27        | 0.53%   |
| Seagate ST1000DM010-2EP102 1TB                      | 27        | 0.53%   |
| Toshiba MQ04ABF100 1TB                              | 26        | 0.51%   |
| Toshiba MQ01ABF050 500GB                            | 26        | 0.51%   |
| Samsung NVMe SSD Drive 256GB                        | 26        | 0.51%   |
| Seagate ST500LT012-1DG142 500GB                     | 25        | 0.49%   |
| Samsung NVMe SSD Drive 512GB                        | 25        | 0.49%   |
| Samsung NVMe SSD Drive 1TB                          | 25        | 0.49%   |
| Crucial CT500MX500SSD1 500GB                        | 25        | 0.49%   |
| Samsung SSD 850 EVO 500GB                           | 23        | 0.45%   |
| Samsung SSD 850 EVO 250GB                           | 23        | 0.45%   |
| Unknown                                             | 23        | 0.45%   |
| Seagate ST9500325AS 500GB                           | 21        | 0.41%   |
| SanDisk NVMe SSD Drive 256GB                        | 21        | 0.41%   |
| Samsung NVMe SSD Drive 500GB                        | 21        | 0.41%   |
| Seagate Expansion 1TB                               | 20        | 0.39%   |
| Samsung SSD 870 EVO 1TB                             | 20        | 0.39%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 19        | 0.37%   |
| Seagate ST1000DM003-1CH162 1TB                      | 19        | 0.37%   |
| Unknown MMC Card  16GB                              | 18        | 0.35%   |
| Toshiba HDWD110 1TB                                 | 18        | 0.35%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 18        | 0.35%   |
| HGST HTS721010A9E630 1TB                            | 18        | 0.35%   |
| Seagate ST3500418AS 500GB                           | 17        | 0.33%   |
| SanDisk NVMe SSD Drive 1TB                          | 17        | 0.33%   |
| Kingston SV300S37A120G 120GB SSD                    | 17        | 0.33%   |
| Crucial CT1000MX500SSD1 1TB                         | 17        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 699       | 989    | 36.93%  |
| WDC                 | 523       | 706    | 27.63%  |
| Toshiba             | 258       | 336    | 13.63%  |
| Hitachi             | 141       | 189    | 7.45%   |
| HGST                | 81        | 100    | 4.28%   |
| Samsung Electronics | 77        | 96     | 4.07%   |
| Unknown             | 27        | 34     | 1.43%   |
| Apple               | 26        | 29     | 1.37%   |
| JMicron Technology  | 14        | 16     | 0.74%   |
| Maxtor              | 12        | 16     | 0.63%   |
| Fujitsu             | 12        | 13     | 0.63%   |
| ASMT                | 4         | 4      | 0.21%   |
| USB3.0              | 3         | 4      | 0.16%   |
| Super Talent        | 3         | 4      | 0.16%   |
| Intenso             | 3         | 3      | 0.16%   |
| Hewlett-Packard     | 3         | 6      | 0.16%   |
| SSK                 | 2         | 2      | 0.11%   |
| SABRENT             | 1         | 1      | 0.05%   |
| QUANTUM             | 1         | 1      | 0.05%   |
| KESU                | 1         | 1      | 0.05%   |
| External            | 1         | 1      | 0.05%   |
| ACASIS              | 1         | 1      | 0.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 315       | 439    | 19.72%  |
| Kingston            | 209       | 278    | 13.09%  |
| Crucial             | 161       | 196    | 10.08%  |
| SanDisk             | 158       | 187    | 9.89%   |
| WDC                 | 70        | 90     | 4.38%   |
| China               | 61        | 73     | 3.82%   |
| A-DATA Technology   | 61        | 77     | 3.82%   |
| Toshiba             | 38        | 44     | 2.38%   |
| Intel               | 36        | 43     | 2.25%   |
| PNY                 | 29        | 37     | 1.82%   |
| Micron Technology   | 28        | 32     | 1.75%   |
| SPCC                | 27        | 35     | 1.69%   |
| SK hynix            | 26        | 26     | 1.63%   |
| Netac               | 25        | 27     | 1.57%   |
| Intenso             | 25        | 27     | 1.57%   |
| Patriot             | 24        | 33     | 1.5%    |
| Apple               | 23        | 27     | 1.44%   |
| GOODRAM             | 20        | 24     | 1.25%   |
| OCZ                 | 17        | 20     | 1.06%   |
| LITEON              | 15        | 17     | 0.94%   |
| Lexar               | 15        | 15     | 0.94%   |
| Team                | 13        | 16     | 0.81%   |
| Transcend           | 12        | 29     | 0.75%   |
| LITEONIT            | 11        | 13     | 0.69%   |
| KingSpec            | 11        | 13     | 0.69%   |
| Unknown             | 10        | 13     | 0.63%   |
| Gigabyte Technology | 9         | 10     | 0.56%   |
| Hewlett-Packard     | 8         | 9      | 0.5%    |
| Apacer              | 8         | 10     | 0.5%    |
| Leven               | 6         | 7      | 0.38%   |
| Plextor             | 5         | 6      | 0.31%   |
| FORESEE             | 5         | 6      | 0.31%   |
| Verbatim            | 4         | 4      | 0.25%   |
| Mushkin             | 4         | 4      | 0.25%   |
| KIOXIA-EXCERIA      | 4         | 8      | 0.25%   |
| Teclast             | 3         | 3      | 0.19%   |
| Seagate             | 3         | 6      | 0.19%   |
| OWC                 | 3         | 3      | 0.19%   |
| NGFF                | 3         | 3      | 0.19%   |
| Fanxiang            | 3         | 4      | 0.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1624      | 2552   | 38.08%  |
| SSD     | 1439      | 2032   | 33.74%  |
| NVMe    | 838       | 1122   | 19.65%  |
| MMC     | 266       | 352    | 6.24%   |
| Unknown | 98        | 124    | 2.3%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2589      | 4442   | 66.73%  |
| NVMe | 833       | 1111   | 21.47%  |
| MMC  | 266       | 352    | 6.86%   |
| SAS  | 192       | 277    | 4.95%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1908      | 2777   | 60.63%  |
| 0.51-1.0   | 899       | 1254   | 28.57%  |
| 1.01-2.0   | 207       | 293    | 6.58%   |
| 3.01-4.0   | 50        | 111    | 1.59%   |
| 4.01-10.0  | 49        | 75     | 1.56%   |
| 2.01-3.0   | 30        | 55     | 0.95%   |
| 10.01-20.0 | 4         | 19     | 0.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1107      | 32.25%  |
| 251-500        | 840       | 24.47%  |
| 501-1000       | 516       | 15.03%  |
| 51-100         | 283       | 8.24%   |
| 1001-2000      | 208       | 6.06%   |
| 21-50          | 168       | 4.89%   |
| More than 3000 | 116       | 3.38%   |
| 1-20           | 83        | 2.42%   |
| 2001-3000      | 69        | 2.01%   |
| Unknown        | 43        | 1.25%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1363      | 38.07%  |
| 21-50          | 990       | 27.65%  |
| 51-100         | 428       | 11.96%  |
| 101-250        | 347       | 9.69%   |
| 251-500        | 182       | 5.08%   |
| 501-1000       | 111       | 3.1%    |
| More than 3000 | 54        | 1.51%   |
| 1001-2000      | 45        | 1.26%   |
| Unknown        | 43        | 1.2%    |
| 2001-3000      | 17        | 0.47%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                   | 3         | 3      | 3.09%   |
| HGST HTS541010A9E680 1TB                 | 3         | 3      | 3.09%   |
| Toshiba MQ02ABD100H 1TB                  | 2         | 2      | 2.06%   |
| SK hynix BC711 HFM512GD3JX013N 512GB     | 2         | 2      | 2.06%   |
| Seagate ST9500420AS 500GB                | 2         | 2      | 2.06%   |
| Seagate ST9500325AS 500GB                | 2         | 2      | 2.06%   |
| Seagate ST500LT012-1DG142 500GB          | 2         | 2      | 2.06%   |
| Kingston SUV400S37240G 240GB SSD         | 2         | 2      | 2.06%   |
| HGST HTS545050A7E380 500GB               | 2         | 3      | 2.06%   |
| WDC WD6400BEVT-22A0RT0 640GB             | 1         | 1      | 1.03%   |
| WDC WD5000LPVX-75V0TT0 500GB             | 1         | 1      | 1.03%   |
| WDC WD5000LPCX-60VHAT0 500GB             | 1         | 1      | 1.03%   |
| WDC WD5000BEVT-24A0RT0 500GB             | 1         | 1      | 1.03%   |
| WDC WD3200AAKS-22B3A0 320GB              | 1         | 1      | 1.03%   |
| WDC WD3200AAJS-00L7A0 320GB              | 1         | 1      | 1.03%   |
| WDC WD30EFRX-68EUZN0 3TB                 | 1         | 1      | 1.03%   |
| WDC WD1200BEVS-60UST0 120GB              | 1         | 1      | 1.03%   |
| WDC WD10SPZX-75Z10T2 1TB                 | 1         | 1      | 1.03%   |
| WDC WD10JPVX-22JC3T0 1TB                 | 1         | 1      | 1.03%   |
| WDC WD10JPVT-55A1YT0 1TB                 | 1         | 1      | 1.03%   |
| WDC WD10EZEX-21M2NA0 1TB                 | 1         | 2      | 1.03%   |
| WDC WD10EURX-63FH1Y0 1TB                 | 1         | 1      | 1.03%   |
| WDC WD Green 2.5 1000GB                  | 1         | 1      | 1.03%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD | 1         | 1      | 1.03%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD     | 1         | 1      | 1.03%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD | 1         | 1      | 1.03%   |
| Toshiba MQ01ABF050 500GB                 | 1         | 1      | 1.03%   |
| Toshiba MQ01ABD075 752GB                 | 1         | 1      | 1.03%   |
| Toshiba MK8046GSX 80GB                   | 1         | 1      | 1.03%   |
| Toshiba MK3265GSX 320GB                  | 1         | 1      | 1.03%   |
| Toshiba MG03ACA200 2TB                   | 1         | 1      | 1.03%   |
| Toshiba DT01ACA100 1TB                   | 1         | 1      | 1.03%   |
| Teclast 128GB NS550-2242 SSD             | 1         | 1      | 1.03%   |
| Silicon Motion Inland NVMe SSD 256GB     | 1         | 1      | 1.03%   |
| Seagate ST9320310AS 320GB                | 1         | 1      | 1.03%   |
| Seagate ST9250315AS 250GB                | 1         | 1      | 1.03%   |
| Seagate ST9200420ASG 200GB               | 1         | 1      | 1.03%   |
| Seagate ST9160411ASG 160GB               | 1         | 1      | 1.03%   |
| Seagate ST8000DM004-2CX188 8TB           | 1         | 1      | 1.03%   |
| Seagate ST500LT012-9WS142 500GB          | 1         | 1      | 1.03%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 33        | 34     | 34.38%  |
| WDC                 | 14        | 15     | 14.58%  |
| Toshiba             | 14        | 14     | 14.58%  |
| HGST                | 8         | 9      | 8.33%   |
| Kingston            | 6         | 6      | 6.25%   |
| Samsung Electronics | 4         | 4      | 4.17%   |
| Hitachi             | 3         | 3      | 3.13%   |
| SK hynix            | 2         | 2      | 2.08%   |
| A-DATA Technology   | 2         | 2      | 2.08%   |
| Teclast             | 1         | 1      | 1.04%   |
| Silicon Motion      | 1         | 1      | 1.04%   |
| OCZ                 | 1         | 1      | 1.04%   |
| Netac               | 1         | 1      | 1.04%   |
| Maxtor              | 1         | 1      | 1.04%   |
| LITEONIT            | 1         | 1      | 1.04%   |
| Intel               | 1         | 1      | 1.04%   |
| Hewlett-Packard     | 1         | 1      | 1.04%   |
| Drevo               | 1         | 1      | 1.04%   |
| Unknown             | 1         | 1      | 1.04%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 33        | 34     | 46.48%  |
| WDC                 | 13        | 14     | 18.31%  |
| Toshiba             | 11        | 11     | 15.49%  |
| HGST                | 8         | 9      | 11.27%  |
| Hitachi             | 3         | 3      | 4.23%   |
| Samsung Electronics | 2         | 2      | 2.82%   |
| Maxtor              | 1         | 1      | 1.41%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 67        | 74     | 72.83%  |
| SSD  | 21        | 21     | 22.83%  |
| NVMe | 4         | 4      | 4.35%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                          | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate ST2000LX001-1RG174 2TB | 1         | 1      | 50%     |
| SanDisk SSD i100 24GB          | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| SanDisk | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2942      | 5454   | 85.97%  |
| Works    | 386       | 626    | 11.28%  |
| Malfunc  | 91        | 99     | 2.66%   |
| Failed   | 2         | 2      | 0.06%   |
| Fixed    | 1         | 1      | 0.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2253      | 57.33%  |
| AMD                              | 632       | 16.08%  |
| Samsung Electronics              | 289       | 7.35%   |
| SanDisk                          | 141       | 3.59%   |
| SK hynix                         | 61        | 1.55%   |
| Nvidia                           | 58        | 1.48%   |
| Kingston Technology Company      | 55        | 1.4%    |
| Phison Electronics               | 50        | 1.27%   |
| ASMedia Technology               | 50        | 1.27%   |
| Silicon Motion                   | 39        | 0.99%   |
| Micron Technology                | 36        | 0.92%   |
| Toshiba America Info Systems     | 32        | 0.81%   |
| KIOXIA                           | 31        | 0.79%   |
| JMicron Technology               | 31        | 0.79%   |
| Marvell Technology Group         | 29        | 0.74%   |
| Micron/Crucial Technology        | 25        | 0.64%   |
| ADATA Technology                 | 19        | 0.48%   |
| Realtek Semiconductor            | 13        | 0.33%   |
| VIA Technologies                 | 9         | 0.23%   |
| MAXIO Technology (Hangzhou)      | 9         | 0.23%   |
| Silicon Image                    | 8         | 0.2%    |
| Seagate Technology               | 8         | 0.2%    |
| Union Memory (Shenzhen)          | 6         | 0.15%   |
| Solid State Storage Technology   | 6         | 0.15%   |
| Lite-On Technology               | 6         | 0.15%   |
| LSI Logic / Symbios Logic        | 4         | 0.1%    |
| Broadcom / LSI                   | 4         | 0.1%    |
| Apple                            | 4         | 0.1%    |
| Silicon Integrated Systems [SiS] | 3         | 0.08%   |
| INNOGRIT                         | 3         | 0.08%   |
| Yangtze Memory Technologies      | 2         | 0.05%   |
| OCZ Technology Group             | 2         | 0.05%   |
| Netac Technology                 | 2         | 0.05%   |
| Lenovo                           | 2         | 0.05%   |
| TenaFe                           | 1         | 0.03%   |
| Shenzhen Longsys Electronics     | 1         | 0.03%   |
| Integrated Technology Express    | 1         | 0.03%   |
| HighPoint Technologies           | 1         | 0.03%   |
| Dell                             | 1         | 0.03%   |
| Biwin Storage Technology         | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 425       | 9.38%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 175       | 3.86%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 165       | 3.64%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 149       | 3.29%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 124       | 2.74%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 124       | 2.74%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 115       | 2.54%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 93        | 2.05%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 88        | 1.94%   |
| AMD 400 Series Chipset SATA Controller                                                  | 79        | 1.74%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 76        | 1.68%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 76        | 1.68%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 73        | 1.61%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 71        | 1.57%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 69        | 1.52%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 68        | 1.5%    |
| Samsung NVMe SSD Controller 980                                                         | 66        | 1.46%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 63        | 1.39%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 63        | 1.39%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 63        | 1.39%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 63        | 1.39%   |
| Intel SATA Controller [RAID mode]                                                       | 59        | 1.3%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 52        | 1.15%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 52        | 1.15%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 48        | 1.06%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 47        | 1.04%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 46        | 1.02%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 46        | 1.02%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 44        | 0.97%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 42        | 0.93%   |
| AMD 500 Series Chipset SATA Controller                                                  | 40        | 0.88%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 39        | 0.86%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 38        | 0.84%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 37        | 0.82%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 37        | 0.82%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 35        | 0.77%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 31        | 0.68%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 30        | 0.66%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 30        | 0.66%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 30        | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2472      | 60.92%  |
| NVMe | 833       | 20.53%  |
| IDE  | 449       | 11.06%  |
| RAID | 295       | 7.27%   |
| SAS  | 6         | 0.15%   |
| SCSI | 3         | 0.07%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 2582      | 77.94%  |
| AMD    | 731       | 22.06%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 50        | 1.51%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 38        | 1.15%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 35        | 1.05%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 27        | 0.81%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 27        | 0.81%   |
| AMD Ryzen 5 3600 6-Core Processor             | 27        | 0.81%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 26        | 0.78%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 25        | 0.75%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 22        | 0.66%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 21        | 0.63%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 21        | 0.63%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 21        | 0.63%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 20        | 0.6%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 20        | 0.6%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 19        | 0.57%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 19        | 0.57%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 19        | 0.57%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 18        | 0.54%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 18        | 0.54%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 18        | 0.54%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 18        | 0.54%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 18        | 0.54%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 18        | 0.54%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 17        | 0.51%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 15        | 0.45%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 15        | 0.45%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 15        | 0.45%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 14        | 0.42%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 14        | 0.42%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 14        | 0.42%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 14        | 0.42%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 14        | 0.42%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 14        | 0.42%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 13        | 0.39%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 13        | 0.39%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 13        | 0.39%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 13        | 0.39%   |
| Intel Core i3-4160 CPU @ 3.60GHz              | 13        | 0.39%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 13        | 0.39%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 13        | 0.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 778       | 23.46%  |
| Intel Core i7           | 468       | 14.11%  |
| Intel Core i3           | 311       | 9.38%   |
| Intel Celeron           | 226       | 6.82%   |
| AMD Ryzen 5             | 175       | 5.28%   |
| Other                   | 174       | 5.25%   |
| Intel Core 2 Duo        | 166       | 5.01%   |
| Intel Atom              | 109       | 3.29%   |
| AMD Ryzen 7             | 109       | 3.29%   |
| Intel Pentium           | 99        | 2.99%   |
| Intel Xeon              | 71        | 2.14%   |
| AMD FX                  | 49        | 1.48%   |
| AMD Ryzen 9             | 46        | 1.39%   |
| Intel Pentium Dual-Core | 43        | 1.3%    |
| AMD A6                  | 40        | 1.21%   |
| AMD Ryzen 3             | 33        | 1%      |
| Intel Core 2 Quad       | 31        | 0.93%   |
| AMD A4                  | 31        | 0.93%   |
| AMD A10                 | 30        | 0.9%    |
| AMD A8                  | 29        | 0.87%   |
| Intel Pentium Dual      | 28        | 0.84%   |
| AMD Athlon II X2        | 20        | 0.6%    |
| Intel Core 2            | 19        | 0.57%   |
| AMD E1                  | 16        | 0.48%   |
| Intel Core i9           | 14        | 0.42%   |
| Intel Pentium Silver    | 13        | 0.39%   |
| AMD Phenom II X4        | 13        | 0.39%   |
| Intel Pentium Gold      | 11        | 0.33%   |
| Intel Core M            | 11        | 0.33%   |
| AMD E                   | 11        | 0.33%   |
| AMD Phenom II X6        | 10        | 0.3%    |
| AMD Athlon 64 X2        | 10        | 0.3%    |
| AMD Athlon              | 10        | 0.3%    |
| AMD Turion 64 X2 Mobile | 8         | 0.24%   |
| Intel Pentium 4         | 7         | 0.21%   |
| AMD E2                  | 7         | 0.21%   |
| AMD Athlon II X4        | 7         | 0.21%   |
| AMD Athlon II           | 6         | 0.18%   |
| Intel Core m5           | 5         | 0.15%   |
| AMD Athlon II X3        | 5         | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 1552      | 46.79%  |
| 4      | 1194      | 36%     |
| 6      | 259       | 7.81%   |
| 8      | 173       | 5.22%   |
| 1      | 44        | 1.33%   |
| 12     | 30        | 0.9%    |
| 3      | 22        | 0.66%   |
| 16     | 17        | 0.51%   |
| 10     | 17        | 0.51%   |
| 14     | 6         | 0.18%   |
| 40     | 1         | 0.03%   |
| 28     | 1         | 0.03%   |
| 24     | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 3301      | 99.64%  |
| 2      | 12        | 0.36%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 1987      | 59.96%  |
| 1      | 1327      | 40.04%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3313      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x206a7    | 263       | 7.81%   |
| 0x306a9    | 253       | 7.52%   |
| Unknown    | 230       | 6.83%   |
| 0x306c3    | 190       | 5.64%   |
| 0x1067a    | 157       | 4.66%   |
| 0x40651    | 98        | 2.91%   |
| 0x806c1    | 93        | 2.76%   |
| 0x20655    | 85        | 2.53%   |
| 0x406e3    | 82        | 2.44%   |
| 0x806e9    | 81        | 2.41%   |
| 0x306d4    | 79        | 2.35%   |
| 0x406c4    | 77        | 2.29%   |
| 0x506e3    | 72        | 2.14%   |
| 0x30678    | 70        | 2.08%   |
| 0x906ea    | 64        | 1.9%    |
| 0x806ea    | 61        | 1.81%   |
| 0x806ec    | 58        | 1.72%   |
| 0x906e9    | 54        | 1.6%    |
| 0x6fd      | 51        | 1.52%   |
| 0x08701021 | 49        | 1.46%   |
| 0x706a8    | 46        | 1.37%   |
| 0x506c9    | 38        | 1.13%   |
| 0x08108109 | 38        | 1.13%   |
| 0x10676    | 37        | 1.1%    |
| 0x706e5    | 36        | 1.07%   |
| 0x20652    | 35        | 1.04%   |
| 0x06000852 | 34        | 1.01%   |
| 0x010000c8 | 33        | 0.98%   |
| 0x406c3    | 31        | 0.92%   |
| 0x6fb      | 29        | 0.86%   |
| 0x0a50000c | 29        | 0.86%   |
| 0x07030105 | 25        | 0.74%   |
| 0x06001119 | 25        | 0.74%   |
| 0x06006705 | 24        | 0.71%   |
| 0xa0653    | 22        | 0.65%   |
| 0x08600106 | 22        | 0.65%   |
| 0x0800820d | 22        | 0.65%   |
| 0xa0652    | 20        | 0.59%   |
| 0x08608103 | 20        | 0.59%   |
| 0x0700010f | 19        | 0.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 390       | 11.77%  |
| Haswell          | 317       | 9.57%   |
| SandyBridge      | 284       | 8.57%   |
| IvyBridge        | 268       | 8.09%   |
| Penryn           | 199       | 6%      |
| Silvermont       | 190       | 5.73%   |
| Skylake          | 161       | 4.86%   |
| Westmere         | 130       | 3.92%   |
| Core             | 112       | 3.38%   |
| Zen 2            | 109       | 3.29%   |
| TigerLake        | 104       | 3.14%   |
| Zen 3            | 96        | 2.9%    |
| Broadwell        | 85        | 2.56%   |
| Zen+             | 84        | 2.53%   |
| K10              | 73        | 2.2%    |
| CometLake        | 67        | 2.02%   |
| Goldmont plus    | 66        | 1.99%   |
| Piledriver       | 65        | 1.96%   |
| Unknown          | 63        | 1.9%    |
| Icelake          | 60        | 1.81%   |
| Excavator        | 58        | 1.75%   |
| Zen              | 49        | 1.48%   |
| Goldmont         | 41        | 1.24%   |
| Puma             | 40        | 1.21%   |
| Nehalem          | 34        | 1.03%   |
| K8 Hammer        | 25        | 0.75%   |
| Jaguar           | 23        | 0.69%   |
| Alderlake Hybrid | 22        | 0.66%   |
| Bobcat           | 20        | 0.6%    |
| K10 Llano        | 17        | 0.51%   |
| Tremont          | 13        | 0.39%   |
| Bulldozer        | 12        | 0.36%   |
| Bonnell          | 12        | 0.36%   |
| Steamroller      | 10        | 0.3%    |
| NetBurst         | 10        | 0.3%    |
| K8 & K10 hybrid  | 5         | 0.15%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2007      | 53%     |
| Nvidia                           | 900       | 23.77%  |
| AMD                              | 867       | 22.89%  |
| VIA Technologies                 | 4         | 0.11%   |
| Matrox Electronics Systems       | 4         | 0.11%   |
| Silicon Integrated Systems [SiS] | 3         | 0.08%   |
| ASPEED Technology                | 2         | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 217       | 5.59%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 159       | 4.09%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 110       | 2.83%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 99        | 2.55%   |
| Intel Core Processor Integrated Graphics Controller                                      | 84        | 2.16%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 83        | 2.14%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 78        | 2.01%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 74        | 1.91%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 69        | 1.78%   |
| Intel HD Graphics 620                                                                    | 67        | 1.73%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 60        | 1.55%   |
| Intel UHD Graphics 620                                                                   | 59        | 1.52%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 58        | 1.49%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 58        | 1.49%   |
| Intel HD Graphics 5500                                                                   | 50        | 1.29%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 45        | 1.16%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 43        | 1.11%   |
| Intel HD Graphics 630                                                                    | 43        | 1.11%   |
| Intel HD Graphics 530                                                                    | 43        | 1.11%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 43        | 1.11%   |
| AMD Renoir                                                                               | 41        | 1.06%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 37        | 0.95%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 36        | 0.93%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 36        | 0.93%   |
| Intel HD Graphics 500                                                                    | 35        | 0.9%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 34        | 0.88%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 32        | 0.82%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 30        | 0.77%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 30        | 0.77%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 30        | 0.77%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 30        | 0.77%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 28        | 0.72%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 28        | 0.72%   |
| AMD Lucienne                                                                             | 28        | 0.72%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 25        | 0.64%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 24        | 0.62%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 22        | 0.57%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 21        | 0.54%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 21        | 0.54%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 20        | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| 1 x Intel            | 1597      | 47.97%  |
| 1 x AMD              | 701       | 21.06%  |
| 1 x Nvidia           | 564       | 16.94%  |
| Intel + Nvidia       | 277       | 8.32%   |
| Intel + AMD          | 80        | 2.4%    |
| AMD + Nvidia         | 44        | 1.32%   |
| 2 x AMD              | 41        | 1.23%   |
| Other                | 5         | 0.15%   |
| 2 x Nvidia           | 5         | 0.15%   |
| 1 x VIA              | 4         | 0.12%   |
| 1 x SiS              | 3         | 0.09%   |
| 1 x Matrox           | 3         | 0.09%   |
| 1 x ASPEED           | 2         | 0.06%   |
| 2 x Intel            | 1         | 0.03%   |
| 2 x AMD + 1 x Nvidia | 1         | 0.03%   |
| AMD + Matrox         | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 2704      | 81.06%  |
| Proprietary | 533       | 15.98%  |
| Unknown     | 99        | 2.97%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1979      | 58.65%  |
| 0.01-0.5   | 411       | 12.18%  |
| 1.01-2.0   | 317       | 9.4%    |
| 0.51-1.0   | 278       | 8.24%   |
| 3.01-4.0   | 160       | 4.74%   |
| 7.01-8.0   | 109       | 3.23%   |
| 5.01-6.0   | 51        | 1.51%   |
| 8.01-16.0  | 37        | 1.1%    |
| 2.01-3.0   | 28        | 0.83%   |
| 16.01-24.0 | 4         | 0.12%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 424       | 12.59%  |
| AU Optronics            | 389       | 11.55%  |
| Chimei Innolux          | 302       | 8.97%   |
| BOE                     | 292       | 8.67%   |
| LG Display              | 284       | 8.43%   |
| Dell                    | 166       | 4.93%   |
| Goldstar                | 152       | 4.51%   |
| Hewlett-Packard         | 118       | 3.5%    |
| Apple                   | 106       | 3.15%   |
| Acer                    | 98        | 2.91%   |
| AOC                     | 78        | 2.32%   |
| Philips                 | 74        | 2.2%    |
| Chi Mei Optoelectronics | 61        | 1.81%   |
| Ancor Communications    | 58        | 1.72%   |
| BenQ                    | 57        | 1.69%   |
| Lenovo                  | 55        | 1.63%   |
| Sharp                   | 44        | 1.31%   |
| LG Electronics          | 29        | 0.86%   |
| LG Philips              | 28        | 0.83%   |
| Sony                    | 26        | 0.77%   |
| PANDA                   | 25        | 0.74%   |
| InfoVision              | 25        | 0.74%   |
| ViewSonic               | 24        | 0.71%   |
| Unknown                 | 24        | 0.71%   |
| Unknown                 | 22        | 0.65%   |
| Vizio                   | 21        | 0.62%   |
| Iiyama                  | 20        | 0.59%   |
| ASUSTek Computer        | 20        | 0.59%   |
| Fujitsu Siemens         | 15        | 0.45%   |
| Sceptre Tech            | 12        | 0.36%   |
| Panasonic               | 12        | 0.36%   |
| Eizo                    | 12        | 0.36%   |
| Toshiba                 | 11        | 0.33%   |
| MSI                     | 11        | 0.33%   |
| CPT                     | 11        | 0.33%   |
| NEC Computers           | 10        | 0.3%    |
| HPN                     | 10        | 0.3%    |
| HannStar                | 9         | 0.27%   |
| Microstep               | 6         | 0.18%   |
| LGD                     | 6         | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                  | 24        | 0.69%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 20        | 0.58%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 16        | 0.46%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 16        | 0.46%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 15        | 0.43%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 14        | 0.41%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 13        | 0.38%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 13        | 0.38%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 13        | 0.38%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 12        | 0.35%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 12        | 0.35%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 11        | 0.32%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 11        | 0.32%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 11        | 0.32%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x173mm 12.3-inch             | 9         | 0.26%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 9         | 0.26%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 9         | 0.26%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                    | 9         | 0.26%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 9         | 0.26%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 9         | 0.26%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 9         | 0.26%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch    | 8         | 0.23%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 8         | 0.23%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 8         | 0.23%   |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch            | 8         | 0.23%   |
| Apple iMac APPA00C 1920x1080 475x267mm 21.5-inch                         | 8         | 0.23%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 7         | 0.2%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 7         | 0.2%    |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 7         | 0.2%    |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 7         | 0.2%    |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 7         | 0.2%    |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 7         | 0.2%    |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 7         | 0.2%    |
| Samsung Electronics LCD Monitor SDC5441 1366x768 309x174mm 14.0-inch     | 6         | 0.17%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 6         | 0.17%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 6         | 0.17%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 6         | 0.17%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 6         | 0.17%   |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch            | 6         | 0.17%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch           | 6         | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1216      | 37.04%  |
| 1366x768 (WXGA)    | 835       | 25.43%  |
| 3840x2160 (4K)     | 175       | 5.33%   |
| 1600x900 (HD+)     | 175       | 5.33%   |
| 1280x800 (WXGA)    | 98        | 2.99%   |
| 2560x1440 (QHD)    | 97        | 2.95%   |
| 1680x1050 (WSXGA+) | 91        | 2.77%   |
| 1440x900 (WXGA+)   | 87        | 2.65%   |
| 1280x1024 (SXGA)   | 80        | 2.44%   |
| Unknown            | 61        | 1.86%   |
| 1920x1200 (WUXGA)  | 51        | 1.55%   |
| 1360x768           | 37        | 1.13%   |
| 3440x1440          | 33        | 1.01%   |
| 3840x1080          | 27        | 0.82%   |
| 2560x1080          | 23        | 0.7%    |
| 2560x1600          | 22        | 0.67%   |
| 1920x540           | 16        | 0.49%   |
| 2736x1824          | 15        | 0.46%   |
| 2160x1440          | 11        | 0.34%   |
| 3200x1800 (QHD+)   | 10        | 0.3%    |
| 2880x1800          | 10        | 0.3%    |
| 2256x1504          | 10        | 0.3%    |
| 1024x768 (XGA)     | 9         | 0.27%   |
| 1600x1200          | 7         | 0.21%   |
| 3840x2400          | 6         | 0.18%   |
| 1280x720 (HD)      | 6         | 0.18%   |
| 5760x1080          | 4         | 0.12%   |
| 3840x1600          | 4         | 0.12%   |
| 1920x1280          | 4         | 0.12%   |
| 1024x600           | 4         | 0.12%   |
| 4480x1440          | 3         | 0.09%   |
| 3600x1080          | 3         | 0.09%   |
| 2880x1920          | 3         | 0.09%   |
| 1920x515           | 3         | 0.09%   |
| 5760x2160          | 2         | 0.06%   |
| 5120x1440          | 2         | 0.06%   |
| 4480x1600          | 2         | 0.06%   |
| 4480x1080          | 2         | 0.06%   |
| 3360x1080          | 2         | 0.06%   |
| 3200x1200          | 2         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 857       | 25.71%  |
| 13      | 320       | 9.6%    |
| Unknown | 267       | 8.01%   |
| 14      | 242       | 7.26%   |
| 17      | 192       | 5.76%   |
| 27      | 189       | 5.67%   |
| 24      | 167       | 5.01%   |
| 21      | 152       | 4.56%   |
| 23      | 144       | 4.32%   |
| 19      | 88        | 2.64%   |
| 11      | 88        | 2.64%   |
| 31      | 77        | 2.31%   |
| 12      | 75        | 2.25%   |
| 20      | 72        | 2.16%   |
| 18      | 70        | 2.1%    |
| 22      | 63        | 1.89%   |
| 34      | 41        | 1.23%   |
| 40      | 22        | 0.66%   |
| 84      | 20        | 0.6%    |
| 16      | 18        | 0.54%   |
| 54      | 17        | 0.51%   |
| 32      | 16        | 0.48%   |
| 26      | 15        | 0.45%   |
| 72      | 14        | 0.42%   |
| 10      | 12        | 0.36%   |
| 25      | 10        | 0.3%    |
| 36      | 7         | 0.21%   |
| 52      | 6         | 0.18%   |
| 49      | 6         | 0.18%   |
| 65      | 5         | 0.15%   |
| 47      | 5         | 0.15%   |
| 28      | 5         | 0.15%   |
| 48      | 4         | 0.12%   |
| 37      | 4         | 0.12%   |
| 35      | 4         | 0.12%   |
| 29      | 4         | 0.12%   |
| 74      | 3         | 0.09%   |
| 64      | 3         | 0.09%   |
| 42      | 3         | 0.09%   |
| 39      | 3         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 1278      | 38.89%  |
| 501-600     | 473       | 14.39%  |
| 401-500     | 397       | 12.08%  |
| 201-300     | 331       | 10.07%  |
| Unknown     | 267       | 8.13%   |
| 351-400     | 229       | 6.97%   |
| 601-700     | 107       | 3.26%   |
| 701-800     | 67        | 2.04%   |
| 1001-1500   | 56        | 1.7%    |
| 1501-2000   | 40        | 1.22%   |
| 801-900     | 33        | 1%      |
| 901-1000    | 6         | 0.18%   |
| 101-200     | 2         | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2285      | 73.92%  |
| 16/10   | 358       | 11.58%  |
| Unknown | 239       | 7.73%   |
| 5/4     | 70        | 2.26%   |
| 3/2     | 49        | 1.59%   |
| 21/9    | 49        | 1.59%   |
| 4/3     | 24        | 0.78%   |
| 32/9    | 8         | 0.26%   |
| 6/5     | 4         | 0.13%   |
| 3.73    | 3         | 0.1%    |
| 0.62    | 2         | 0.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 852       | 25.72%  |
| 81-90          | 453       | 13.68%  |
| 201-250        | 418       | 12.62%  |
| Unknown        | 267       | 8.06%   |
| 151-200        | 218       | 6.58%   |
| 301-350        | 197       | 5.95%   |
| 351-500        | 147       | 4.44%   |
| 121-130        | 134       | 4.05%   |
| 71-80          | 118       | 3.56%   |
| 141-150        | 93        | 2.81%   |
| 51-60          | 90        | 2.72%   |
| More than 1000 | 86        | 2.6%    |
| 61-70          | 64        | 1.93%   |
| 251-300        | 64        | 1.93%   |
| 501-1000       | 52        | 1.57%   |
| 131-140        | 21        | 0.63%   |
| 111-120        | 19        | 0.57%   |
| 41-50          | 10        | 0.3%    |
| 91-100         | 7         | 0.21%   |
| 1-40           | 2         | 0.06%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 989       | 30.55%  |
| 51-100        | 955       | 29.5%   |
| 121-160       | 720       | 22.24%  |
| Unknown       | 267       | 8.25%   |
| 161-240       | 161       | 4.97%   |
| 1-50          | 88        | 2.72%   |
| More than 240 | 57        | 1.76%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 2829      | 84.05%  |
| 2     | 402       | 11.94%  |
| 0     | 102       | 3.03%   |
| 3     | 29        | 0.86%   |
| 4     | 3         | 0.09%   |
| 5     | 1         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1759      | 34.96%  |
| Intel                             | 1433      | 28.48%  |
| Qualcomm Atheros                  | 618       | 12.28%  |
| Broadcom                          | 368       | 7.31%   |
| Broadcom Limited                  | 101       | 2.01%   |
| Ralink Technology                 | 76        | 1.51%   |
| TP-Link                           | 69        | 1.37%   |
| Marvell Technology Group          | 68        | 1.35%   |
| Ralink                            | 60        | 1.19%   |
| MediaTek                          | 58        | 1.15%   |
| Nvidia                            | 50        | 0.99%   |
| Samsung Electronics               | 33        | 0.66%   |
| ASIX Electronics                  | 28        | 0.56%   |
| NetGear                           | 22        | 0.44%   |
| Dell                              | 21        | 0.42%   |
| Xiaomi                            | 19        | 0.38%   |
| DisplayLink                       | 15        | 0.3%    |
| Qualcomm Atheros Communications   | 14        | 0.28%   |
| Microsoft                         | 14        | 0.28%   |
| Huawei Technologies               | 14        | 0.28%   |
| JMicron Technology                | 11        | 0.22%   |
| Hewlett-Packard                   | 11        | 0.22%   |
| D-Link                            | 11        | 0.22%   |
| Sierra Wireless                   | 10        | 0.2%    |
| D-Link System                     | 10        | 0.2%    |
| OPPO Electronics                  | 9         | 0.18%   |
| Edimax Technology                 | 9         | 0.18%   |
| ASUSTek Computer                  | 9         | 0.18%   |
| Qualcomm                          | 7         | 0.14%   |
| Motorola PCS                      | 7         | 0.14%   |
| Linksys                           | 6         | 0.12%   |
| T & A Mobile Phones               | 5         | 0.1%    |
| Google                            | 5         | 0.1%    |
| Ericsson Business Mobile Networks | 5         | 0.1%    |
| Aquantia                          | 5         | 0.1%    |
| VIA Technologies                  | 4         | 0.08%   |
| OnePlus Technology (Shenzhen)     | 4         | 0.08%   |
| Belkin Components                 | 4         | 0.08%   |
| Silicon Integrated Systems [SiS]  | 3         | 0.06%   |
| Lenovo                            | 3         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1114      | 19.01%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 262       | 4.47%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 156       | 2.66%   |
| Intel Wi-Fi 6 AX200                                               | 108       | 1.84%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 104       | 1.77%   |
| Intel Wireless 7265                                               | 96        | 1.64%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 88        | 1.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 82        | 1.4%    |
| Intel Wireless 7260                                               | 79        | 1.35%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 75        | 1.28%   |
| Intel Wireless 8265 / 8275                                        | 74        | 1.26%   |
| Realtek RTL8125 2.5GbE Controller                                 | 70        | 1.19%   |
| Intel Wi-Fi 6 AX201                                               | 70        | 1.19%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 67        | 1.14%   |
| Intel Ethernet Connection I217-LM                                 | 63        | 1.08%   |
| Intel I211 Gigabit Network Connection                             | 56        | 0.96%   |
| Broadcom BCM43142 802.11b/g/n                                     | 56        | 0.96%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 54        | 0.92%   |
| Intel Wireless 3165                                               | 54        | 0.92%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 53        | 0.9%    |
| Intel Wireless 8260                                               | 52        | 0.89%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 47        | 0.8%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 43        | 0.73%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 42        | 0.72%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 42        | 0.72%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 41        | 0.7%    |
| Realtek 802.11ac NIC                                              | 40        | 0.68%   |
| Intel Ethernet Connection (2) I219-V                              | 40        | 0.68%   |
| Intel Ethernet Controller I225-V                                  | 37        | 0.63%   |
| Ralink MT7601U Wireless Adapter                                   | 35        | 0.6%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 35        | 0.6%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 34        | 0.58%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 33        | 0.56%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 32        | 0.55%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 31        | 0.53%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 31        | 0.53%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 30        | 0.51%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 29        | 0.49%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 29        | 0.49%   |
| Intel WiFi Link 5100                                              | 26        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1085      | 38.49%  |
| Realtek Semiconductor                 | 522       | 18.52%  |
| Qualcomm Atheros                      | 491       | 17.42%  |
| Broadcom                              | 259       | 9.19%   |
| Ralink Technology                     | 76        | 2.7%    |
| Broadcom Limited                      | 65        | 2.31%   |
| Ralink                                | 60        | 2.13%   |
| TP-Link                               | 59        | 2.09%   |
| MediaTek                              | 51        | 1.81%   |
| NetGear                               | 22        | 0.78%   |
| Marvell Technology Group              | 19        | 0.67%   |
| Qualcomm Atheros Communications       | 14        | 0.5%    |
| Microsoft                             | 11        | 0.39%   |
| D-Link                                | 11        | 0.39%   |
| Sierra Wireless                       | 10        | 0.35%   |
| Edimax Technology                     | 9         | 0.32%   |
| Dell                                  | 9         | 0.32%   |
| D-Link System                         | 8         | 0.28%   |
| ASUSTek Computer                      | 8         | 0.28%   |
| Linksys                               | 6         | 0.21%   |
| Belkin Components                     | 4         | 0.14%   |
| ZyDAS                                 | 2         | 0.07%   |
| TRENDnet                              | 2         | 0.07%   |
| Gemtek                                | 2         | 0.07%   |
| Fibocom                               | 2         | 0.07%   |
| AVM                                   | 2         | 0.07%   |
| ZyXEL Communications                  | 1         | 0.04%   |
| Xiaomi                                | 1         | 0.04%   |
| Qualcomm                              | 1         | 0.04%   |
| Panasonic (Matsushita)                | 1         | 0.04%   |
| Ovislink                              | 1         | 0.04%   |
| Mercucys                              | 1         | 0.04%   |
| Hewlett-Packard                       | 1         | 0.04%   |
| Askey Computer                        | 1         | 0.04%   |
| ADMtek                                | 1         | 0.04%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 108       | 3.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 104       | 3.65%   |
| Intel Wireless 7265                                            | 96        | 3.37%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 88        | 3.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 82        | 2.88%   |
| Intel Wireless 7260                                            | 79        | 2.77%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 75        | 2.63%   |
| Intel Wireless 8265 / 8275                                     | 74        | 2.6%    |
| Intel Wi-Fi 6 AX201                                            | 70        | 2.46%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 67        | 2.35%   |
| Broadcom BCM43142 802.11b/g/n                                  | 56        | 1.97%   |
| Intel Wireless 3165                                            | 54        | 1.9%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 53        | 1.86%   |
| Intel Wireless 8260                                            | 52        | 1.83%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 47        | 1.65%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 43        | 1.51%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 42        | 1.47%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 42        | 1.47%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 41        | 1.44%   |
| Realtek 802.11ac NIC                                           | 40        | 1.4%    |
| Ralink MT7601U Wireless Adapter                                | 35        | 1.23%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 33        | 1.16%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 32        | 1.12%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 31        | 1.09%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 31        | 1.09%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 30        | 1.05%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 29        | 1.02%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 29        | 1.02%   |
| Intel WiFi Link 5100                                           | 26        | 0.91%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 24        | 0.84%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 23        | 0.81%   |
| Intel Centrino Ultimate-N 6300                                 | 23        | 0.81%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 22        | 0.77%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 21        | 0.74%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 21        | 0.74%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 21        | 0.74%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 20        | 0.7%    |
| Intel Wireless-AC 9260                                         | 20        | 0.7%    |
| Intel Wireless 3160                                            | 20        | 0.7%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 19        | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1528      | 52.65%  |
| Intel                             | 716       | 24.67%  |
| Qualcomm Atheros                  | 174       | 6%      |
| Broadcom                          | 162       | 5.58%   |
| Nvidia                            | 50        | 1.72%   |
| Marvell Technology Group          | 49        | 1.69%   |
| Broadcom Limited                  | 38        | 1.31%   |
| ASIX Electronics                  | 28        | 0.96%   |
| Samsung Electronics               | 20        | 0.69%   |
| Xiaomi                            | 18        | 0.62%   |
| DisplayLink                       | 15        | 0.52%   |
| JMicron Technology                | 11        | 0.38%   |
| Huawei Technologies               | 11        | 0.38%   |
| TP-Link                           | 10        | 0.34%   |
| OPPO Electronics                  | 9         | 0.31%   |
| MediaTek                          | 7         | 0.24%   |
| Qualcomm                          | 6         | 0.21%   |
| Google                            | 5         | 0.17%   |
| Aquantia                          | 5         | 0.17%   |
| VIA Technologies                  | 4         | 0.14%   |
| Motorola PCS                      | 4         | 0.14%   |
| Silicon Integrated Systems [SiS]  | 3         | 0.1%    |
| Hewlett-Packard                   | 3         | 0.1%    |
| Sundance Technology Inc / IC Plus | 2         | 0.07%   |
| OnePlus Technology (Shenzhen)     | 2         | 0.07%   |
| Microsoft                         | 2         | 0.07%   |
| Lenovo                            | 2         | 0.07%   |
| HMD Global                        | 2         | 0.07%   |
| D-Link System                     | 2         | 0.07%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.03%   |
| Tenda                             | 1         | 0.03%   |
| T & A Mobile Phones               | 1         | 0.03%   |
| Sun Microsystems                  | 1         | 0.03%   |
| Research In Motion                | 1         | 0.03%   |
| Novatel Wireless                  | 1         | 0.03%   |
| Motorola BCS                      | 1         | 0.03%   |
| LG Electronics                    | 1         | 0.03%   |
| ICS Advent                        | 1         | 0.03%   |
| HTC (High Tech Computer)          | 1         | 0.03%   |
| GoPro                             | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1114      | 37.88%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 262       | 8.91%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 156       | 5.3%    |
| Realtek RTL8125 2.5GbE Controller                                 | 70        | 2.38%   |
| Intel Ethernet Connection I217-LM                                 | 63        | 2.14%   |
| Intel I211 Gigabit Network Connection                             | 56        | 1.9%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 54        | 1.84%   |
| Intel Ethernet Connection (2) I219-V                              | 40        | 1.36%   |
| Intel Ethernet Controller I225-V                                  | 37        | 1.26%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 35        | 1.19%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 34        | 1.16%   |
| Intel Ethernet Connection I218-LM                                 | 23        | 0.78%   |
| Intel Ethernet Connection I217-V                                  | 23        | 0.78%   |
| ASIX AX88179 Gigabit Ethernet                                     | 23        | 0.78%   |
| Intel Ethernet Connection I219-LM                                 | 22        | 0.75%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 21        | 0.71%   |
| Intel 82577LM Gigabit Network Connection                          | 20        | 0.68%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 20        | 0.68%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 19        | 0.65%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 19        | 0.65%   |
| Nvidia MCP79 Ethernet                                             | 19        | 0.65%   |
| Intel Ethernet Connection (2) I219-LM                             | 19        | 0.65%   |
| Intel 82567LM Gigabit Network Connection                          | 18        | 0.61%   |
| Nvidia MCP61 Ethernet                                             | 16        | 0.54%   |
| Intel 82579V Gigabit Network Connection                           | 16        | 0.54%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 16        | 0.54%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 15        | 0.51%   |
| Intel Ethernet Connection (4) I219-LM                             | 15        | 0.51%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 14        | 0.48%   |
| Intel Ethernet Connection I219-V                                  | 14        | 0.48%   |
| Intel Ethernet Connection (7) I219-V                              | 14        | 0.48%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 13        | 0.44%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 13        | 0.44%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 13        | 0.44%   |
| Intel Ethernet Connection (2) I218-V                              | 13        | 0.44%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 13        | 0.44%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 13        | 0.44%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 12        | 0.41%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 12        | 0.41%   |
| Intel Ethernet Connection (4) I219-V                              | 12        | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2749      | 50.35%  |
| WiFi     | 2642      | 48.39%  |
| Modem    | 57        | 1.04%   |
| Unknown  | 12        | 0.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2070      | 60.23%  |
| Ethernet | 1362      | 39.63%  |
| Modem    | 3         | 0.09%   |
| Unknown  | 2         | 0.06%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1795      | 53.95%  |
| 1     | 1359      | 40.85%  |
| 0     | 114       | 3.43%   |
| 3     | 53        | 1.59%   |
| 5     | 3         | 0.09%   |
| 4     | 2         | 0.06%   |
| 7     | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2292      | 68.13%  |
| Yes  | 1072      | 31.87%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 824       | 41.45%  |
| Realtek Semiconductor           | 238       | 11.97%  |
| Qualcomm Atheros Communications | 179       | 9%      |
| Broadcom                        | 115       | 5.78%   |
| Apple                           | 112       | 5.63%   |
| Cambridge Silicon Radio         | 104       | 5.23%   |
| IMC Networks                    | 87        | 4.38%   |
| Foxconn / Hon Hai               | 52        | 2.62%   |
| Lite-On Technology              | 51        | 2.57%   |
| Dell                            | 35        | 1.76%   |
| ASUSTek Computer                | 32        | 1.61%   |
| Hewlett-Packard                 | 31        | 1.56%   |
| Toshiba                         | 24        | 1.21%   |
| Marvell Semiconductor           | 17        | 0.86%   |
| Ralink                          | 16        | 0.8%    |
| MediaTek                        | 16        | 0.8%    |
| TP-Link                         | 7         | 0.35%   |
| Realtek                         | 7         | 0.35%   |
| Integrated System Solution      | 6         | 0.3%    |
| Foxconn International           | 6         | 0.3%    |
| Dynex                           | 5         | 0.25%   |
| Alps Electric                   | 5         | 0.25%   |
| Belkin Components               | 4         | 0.2%    |
| Unknown                         | 3         | 0.15%   |
| Askey Computer                  | 2         | 0.1%    |
| Actions                         | 2         | 0.1%    |
| Sitecom Europe                  | 1         | 0.05%   |
| Ralink Technology               | 1         | 0.05%   |
| Qcom                            | 1         | 0.05%   |
| National Semiconductor          | 1         | 0.05%   |
| Micro Star International        | 1         | 0.05%   |
| Edimax Technology               | 1         | 0.05%   |
| D-Link System                   | 1         | 0.05%   |
| Chicony Electronics             | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 357       | 17.93%  |
| Realtek Bluetooth Radio                             | 161       | 8.09%   |
| Intel AX201 Bluetooth                               | 124       | 6.23%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 104       | 5.22%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 103       | 5.17%   |
| Intel AX200 Bluetooth                               | 94        | 4.72%   |
| Qualcomm Atheros  Bluetooth Device                  | 77        | 3.87%   |
| Realtek  Bluetooth 4.2 Adapter                      | 51        | 2.56%   |
| Intel AX210 Bluetooth                               | 44        | 2.21%   |
| Apple Bluetooth Host Controller                     | 40        | 2.01%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 32        | 1.61%   |
| IMC Networks Bluetooth Device                       | 32        | 1.61%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 32        | 1.61%   |
| Intel Wireless-AC 3168 Bluetooth                    | 29        | 1.46%   |
| Apple Bluetooth USB Host Controller                 | 28        | 1.41%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 27        | 1.36%   |
| IMC Networks Bluetooth Radio                        | 26        | 1.31%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 25        | 1.26%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 24        | 1.21%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 21        | 1.05%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 18        | 0.9%    |
| Qualcomm Atheros AR9462 Bluetooth                   | 18        | 0.9%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 18        | 0.9%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 18        | 0.9%    |
| Marvell Bluetooth and Wireless LAN Composite        | 17        | 0.85%   |
| Ralink RT3290 Bluetooth                             | 16        | 0.8%    |
| Lite-On Atheros AR3012 Bluetooth                    | 16        | 0.8%    |
| Foxconn / Hon Hai Bluetooth Device                  | 16        | 0.8%    |
| MediaTek Wireless_Device                            | 15        | 0.75%   |
| IMC Networks Wireless_Device                        | 14        | 0.7%    |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 14        | 0.7%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 13        | 0.65%   |
| HP Broadcom 2070 Bluetooth Combo                    | 13        | 0.65%   |
| Dell DW375 Bluetooth Module                         | 13        | 0.65%   |
| Broadcom BCM2045B (BDC-2.1)                         | 12        | 0.6%    |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 12        | 0.6%    |
| Apple Bluetooth HCI                                 | 12        | 0.6%    |
| Lite-On Bluetooth Device                            | 10        | 0.5%    |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 9         | 0.45%   |
| Toshiba Bluetooth Device                            | 8         | 0.4%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 2435      | 55.05%  |
| AMD                                          | 923       | 20.87%  |
| Nvidia                                       | 712       | 16.1%   |
| C-Media Electronics                          | 52        | 1.18%   |
| Creative Labs                                | 20        | 0.45%   |
| Logitech                                     | 18        | 0.41%   |
| Texas Instruments                            | 16        | 0.36%   |
| Kingston Technology                          | 16        | 0.36%   |
| JMTek                                        | 15        | 0.34%   |
| Generalplus Technology                       | 14        | 0.32%   |
| ASUSTek Computer                             | 14        | 0.32%   |
| Realtek Semiconductor                        | 12        | 0.27%   |
| Razer USA                                    | 10        | 0.23%   |
| Plantronics                                  | 10        | 0.23%   |
| VIA Technologies                             | 9         | 0.2%    |
| Creative Technology                          | 9         | 0.2%    |
| GN Netcom                                    | 7         | 0.16%   |
| SteelSeries ApS                              | 6         | 0.14%   |
| Lenovo                                       | 6         | 0.14%   |
| Tenx Technology                              | 5         | 0.11%   |
| FUXIN                                        | 5         | 0.11%   |
| Focusrite-Novation                           | 5         | 0.11%   |
| Micro Star International                     | 4         | 0.09%   |
| Corsair                                      | 4         | 0.09%   |
| Zoran Co. Personal Media Division (Nogatech) | 3         | 0.07%   |
| Silicon Integrated Systems [SiS]             | 3         | 0.07%   |
| RODE Microphones                             | 3         | 0.07%   |
| DSEA A/S                                     | 3         | 0.07%   |
| BEHRINGER International                      | 3         | 0.07%   |
| Astro Gaming                                 | 3         | 0.07%   |
| Yamaha                                       | 2         | 0.05%   |
| XMOS                                         | 2         | 0.05%   |
| Thesycon Systemsoftware & Consulting         | 2         | 0.05%   |
| Sony                                         | 2         | 0.05%   |
| SAVITECH                                     | 2         | 0.05%   |
| Samsung Electronics                          | 2         | 0.05%   |
| PreSonus Audio Electronics                   | 2         | 0.05%   |
| Numark                                       | 2         | 0.05%   |
| KTMicro                                      | 2         | 0.05%   |
| Jieli Technology                             | 2         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 273       | 5.19%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 265       | 5.03%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 235       | 4.46%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 221       | 4.2%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 186       | 3.53%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 143       | 2.72%   |
| AMD FCH Azalia Controller                                                                         | 129       | 2.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 126       | 2.39%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 126       | 2.39%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 110       | 2.09%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 110       | 2.09%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 106       | 2.01%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 104       | 1.98%   |
| Intel 8 Series HD Audio Controller                                                                | 101       | 1.92%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 97        | 1.84%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 90        | 1.71%   |
| Intel Cannon Lake PCH cAVS                                                                        | 83        | 1.58%   |
| Intel Broadwell-U Audio Controller                                                                | 81        | 1.54%   |
| AMD Kabini HDMI/DP Audio                                                                          | 79        | 1.5%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 76        | 1.44%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 75        | 1.42%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 72        | 1.37%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 66        | 1.25%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 64        | 1.22%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 61        | 1.16%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 55        | 1.04%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 55        | 1.04%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 54        | 1.03%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 50        | 0.95%   |
| Intel 200 Series PCH HD Audio                                                                     | 47        | 0.89%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 47        | 0.89%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 46        | 0.87%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 41        | 0.78%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 41        | 0.78%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 41        | 0.78%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 39        | 0.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 39        | 0.74%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 38        | 0.72%   |
| Nvidia High Definition Audio Controller                                                           | 37        | 0.7%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 37        | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Samsung Electronics    | 170       | 23.38%  |
| SK hynix               | 134       | 18.43%  |
| Micron Technology      | 76        | 10.45%  |
| Unknown                | 69        | 9.49%   |
| Kingston               | 56        | 7.7%    |
| Crucial                | 38        | 5.23%   |
| Unknown (ABCD)         | 21        | 2.89%   |
| G.Skill                | 20        | 2.75%   |
| Corsair                | 20        | 2.75%   |
| A-DATA Technology      | 15        | 2.06%   |
| Elpida                 | 13        | 1.79%   |
| Ramaxel Technology     | 12        | 1.65%   |
| Team                   | 10        | 1.38%   |
| Nanya Technology       | 8         | 1.1%    |
| Unknown                | 8         | 1.1%    |
| Smart                  | 5         | 0.69%   |
| Patriot                | 5         | 0.69%   |
| Timetec                | 3         | 0.41%   |
| Avant                  | 3         | 0.41%   |
| Wilk                   | 2         | 0.28%   |
| Unifosa                | 2         | 0.28%   |
| Transcend              | 2         | 0.28%   |
| Teikon                 | 2         | 0.28%   |
| Qimonda                | 2         | 0.28%   |
| ff                     | 2         | 0.28%   |
| fef5                   | 2         | 0.28%   |
| 4ea5                   | 2         | 0.28%   |
| Unknown (08B5)         | 1         | 0.14%   |
| Unknown (07F7)         | 1         | 0.14%   |
| Unknown (000080B30080) | 1         | 0.14%   |
| SUPER KINGSTEK         | 1         | 0.14%   |
| Strontium              | 1         | 0.14%   |
| Smart Brazil           | 1         | 0.14%   |
| Silicon Power          | 1         | 0.14%   |
| SHARETRONIC            | 1         | 0.14%   |
| PUSKILL                | 1         | 0.14%   |
| ProMos/Mosel Vitelic   | 1         | 0.14%   |
| PNY                    | 1         | 0.14%   |
| Patriot Memory         | 1         | 0.14%   |
| Netlist                | 1         | 0.14%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 19        | 2.45%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 9         | 1.16%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 8         | 1.03%   |
| Unknown                                                          | 8         | 1.03%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.9%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 0.9%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 0.9%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 0.78%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 0.78%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s         | 6         | 0.78%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 6         | 0.78%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 5         | 0.65%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 5         | 0.65%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.65%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.65%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 5         | 0.65%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 4         | 0.52%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                     | 4         | 0.52%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.52%   |
| Samsung RAM UBE3D4AA-MGCR 8GB Row Of Chips LPDDR4 4267MT/s       | 4         | 0.52%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.52%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 4         | 0.52%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 4         | 0.52%   |
| Samsung RAM M471A1G44BB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 4         | 0.52%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 4         | 0.52%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 4         | 0.52%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 3         | 0.39%   |
| Unknown RAM Module 2048MB SODIMM DDR3                            | 3         | 0.39%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 3000MT/s               | 3         | 0.39%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                  | 3         | 0.39%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 975MT/s             | 3         | 0.39%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 3         | 0.39%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s             | 3         | 0.39%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.39%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 3         | 0.39%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 3         | 0.39%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 3         | 0.39%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 3         | 0.39%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 0.39%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 3         | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 262       | 41.59%  |
| DDR3    | 225       | 35.71%  |
| LPDDR4  | 48        | 7.62%   |
| LPDDR3  | 27        | 4.29%   |
| DDR2    | 26        | 4.13%   |
| SDRAM   | 17        | 2.7%    |
| Unknown | 14        | 2.22%   |
| DDR5    | 5         | 0.79%   |
| DDR     | 4         | 0.63%   |
| LPDDR5  | 2         | 0.32%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 389       | 62.14%  |
| DIMM         | 163       | 26.04%  |
| Row Of Chips | 62        | 9.9%    |
| Unknown      | 7         | 1.12%   |
| Chip         | 4         | 0.64%   |
| FB-DIMM      | 1         | 0.16%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 259       | 36.95%  |
| 4096  | 221       | 31.53%  |
| 2048  | 108       | 15.41%  |
| 16384 | 73        | 10.41%  |
| 1024  | 21        | 3%      |
| 32768 | 17        | 2.43%   |
| 512   | 2         | 0.29%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 141       | 20.67%  |
| 3200    | 106       | 15.54%  |
| 2667    | 85        | 12.46%  |
| 2400    | 62        | 9.09%   |
| 1333    | 43        | 6.3%    |
| 2133    | 27        | 3.96%   |
| 1334    | 26        | 3.81%   |
| 4267    | 17        | 2.49%   |
| 1867    | 17        | 2.49%   |
| 667     | 14        | 2.05%   |
| Unknown | 13        | 1.91%   |
| 3600    | 12        | 1.76%   |
| 800     | 12        | 1.76%   |
| 3266    | 10        | 1.47%   |
| 1066    | 10        | 1.47%   |
| 2048    | 7         | 1.03%   |
| 3000    | 6         | 0.88%   |
| 1866    | 6         | 0.88%   |
| 1800    | 5         | 0.73%   |
| 1067    | 5         | 0.73%   |
| 4800    | 4         | 0.59%   |
| 2933    | 4         | 0.59%   |
| 975     | 4         | 0.59%   |
| 8400    | 3         | 0.44%   |
| 6400    | 3         | 0.44%   |
| 4266    | 3         | 0.44%   |
| 3733    | 3         | 0.44%   |
| 4199    | 2         | 0.29%   |
| 3866    | 2         | 0.29%   |
| 3800    | 2         | 0.29%   |
| 3666    | 2         | 0.29%   |
| 3466    | 2         | 0.29%   |
| 3400    | 2         | 0.29%   |
| 3333    | 2         | 0.29%   |
| 2666    | 2         | 0.29%   |
| 400     | 2         | 0.29%   |
| 5354    | 1         | 0.15%   |
| 5200    | 1         | 0.15%   |
| 4000    | 1         | 0.15%   |
| 3933    | 1         | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 20        | 27.03%  |
| Canon                 | 13        | 17.57%  |
| Brother Industries    | 13        | 17.57%  |
| Seiko Epson           | 12        | 16.22%  |
| Samsung Electronics   | 9         | 12.16%  |
| Lexmark International | 3         | 4.05%   |
| Zebra                 | 1         | 1.35%   |
| Ricoh                 | 1         | 1.35%   |
| QinHeng Electronics   | 1         | 1.35%   |
| Konica Minolta        | 1         | 1.35%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Seiko Epson L3110 Series                     | 3         | 4.05%   |
| Samsung C460 Series                          | 2         | 2.7%    |
| HP LaserJet Professional P1102w              | 2         | 2.7%    |
| HP ENVY Photo 6200 series                    | 2         | 2.7%    |
| HP DeskJet 2700 series                       | 2         | 2.7%    |
| HP DeskJet 2130 series                       | 2         | 2.7%    |
| Canon TS3100 series                          | 2         | 2.7%    |
| Canon LiDE 400                               | 2         | 2.7%    |
| Brother HL-2140 series                       | 2         | 2.7%    |
| Zebra ZP 450 Printer                         | 1         | 1.35%   |
| Seiko Epson XP-7100 Series                   | 1         | 1.35%   |
| Seiko Epson XP-200 Series                    | 1         | 1.35%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1         | 1.35%   |
| Seiko Epson L805 Series                      | 1         | 1.35%   |
| Seiko Epson L355 Series                      | 1         | 1.35%   |
| Seiko Epson L3250 Series                     | 1         | 1.35%   |
| Seiko Epson ET-2820 Series                   | 1         | 1.35%   |
| Seiko Epson ET-2710 Series                   | 1         | 1.35%   |
| Seiko Epson AcuLaser C1700                   | 1         | 1.35%   |
| Samsung SCX-483x 5x3x Series                 | 1         | 1.35%   |
| Samsung SCX-4623 Series                      | 1         | 1.35%   |
| Samsung SCX-4200 series                      | 1         | 1.35%   |
| Samsung SCX-3400 Series                      | 1         | 1.35%   |
| Samsung ML-2950 Series                       | 1         | 1.35%   |
| Samsung ML-216x Series Laser Printer         | 1         | 1.35%   |
| Samsung M2020 Series                         | 1         | 1.35%   |
| Ricoh SP 112SU                               | 1         | 1.35%   |
| QinHeng CH340S                               | 1         | 1.35%   |
| Lexmark International MX317dn                | 1         | 1.35%   |
| Lexmark International Laser Printer E232     | 1         | 1.35%   |
| Lexmark International 2400 series            | 1         | 1.35%   |
| Konica Minolta PagePro 1380MF                | 1         | 1.35%   |
| HP Smart Tank 510 series                     | 1         | 1.35%   |
| HP PSC 1100 series                           | 1         | 1.35%   |
| HP OfficeJet Pro 9010 series                 | 1         | 1.35%   |
| HP Officejet 6600                            | 1         | 1.35%   |
| HP OfficeJet 5600 (USBHUB)                   | 1         | 1.35%   |
| HP OfficeJet 4650 series                     | 1         | 1.35%   |
| HP LaserJet 1200                             | 1         | 1.35%   |
| HP LaserJet 1000                             | 1         | 1.35%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 8         | 61.54%  |
| Seiko Epson     | 3         | 23.08%  |
| Hewlett-Packard | 2         | 15.38%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X750 [Perfection 4490 Photo] | 2         | 14.29%  |
| Seiko Epson Scanner                         | 1         | 7.14%   |
| HP ScanJet 2400c                            | 1         | 7.14%   |
| HP PSC 1200                                 | 1         | 7.14%   |
| Canon CanoScan N670U/N676U/LiDE 20          | 1         | 7.14%   |
| Canon CanoScan LiDE 90                      | 1         | 7.14%   |
| Canon CanoScan LiDE 60                      | 1         | 7.14%   |
| Canon CanoScan LIDE 25                      | 1         | 7.14%   |
| Canon CanoScan LiDE 220                     | 1         | 7.14%   |
| Canon CanoScan LiDE 110                     | 1         | 7.14%   |
| Canon CanoScan LiDE 100                     | 1         | 7.14%   |
| Canon CanoScan D660U                        | 1         | 7.14%   |
| Canon CanoScan 8800F                        | 1         | 7.14%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 398       | 20.5%   |
| Microdia                               | 175       | 9.02%   |
| Realtek Semiconductor                  | 163       | 8.4%    |
| IMC Networks                           | 139       | 7.16%   |
| Sunplus Innovation Technology          | 110       | 5.67%   |
| Apple                                  | 104       | 5.36%   |
| Cheng Uei Precision Industry (Foxlink) | 87        | 4.48%   |
| Logitech                               | 79        | 4.07%   |
| Quanta                                 | 76        | 3.92%   |
| Bison Electronics                      | 76        | 3.92%   |
| Suyin                                  | 68        | 3.5%    |
| Syntek                                 | 52        | 2.68%   |
| Acer                                   | 49        | 2.52%   |
| Lite-On Technology                     | 34        | 1.75%   |
| Silicon Motion                         | 31        | 1.6%    |
| Alcor Micro                            | 31        | 1.6%    |
| Samsung Electronics                    | 20        | 1.03%   |
| Luxvisions Innotech Limited            | 19        | 0.98%   |
| Microsoft                              | 18        | 0.93%   |
| Ricoh                                  | 17        | 0.88%   |
| icSpring                               | 14        | 0.72%   |
| Sonix Technology                       | 13        | 0.67%   |
| Primax Electronics                     | 12        | 0.62%   |
| Generalplus Technology                 | 11        | 0.57%   |
| Z-Star Microelectronics                | 10        | 0.52%   |
| ARC International                      | 10        | 0.52%   |
| GEMBIRD                                | 9         | 0.46%   |
| Lenovo                                 | 8         | 0.41%   |
| ALi                                    | 8         | 0.41%   |
| SunplusIT                              | 7         | 0.36%   |
| Shenzhen Kingcome Optoelectronic       | 5         | 0.26%   |
| Importek                               | 5         | 0.26%   |
| Y Media                                | 4         | 0.21%   |
| Sunplus Technology                     | 4         | 0.21%   |
| Razer USA                              | 4         | 0.21%   |
| Jieli Technology                       | 4         | 0.21%   |
| Genesys Logic                          | 4         | 0.21%   |
| Tobii Technology AB                    | 3         | 0.15%   |
| OmniVision Technologies                | 3         | 0.15%   |
| Intel                                  | 3         | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 63        | 3.22%   |
| Microdia Integrated_Webcam_HD                    | 41        | 2.1%    |
| Apple FaceTime HD Camera (Built-in)              | 40        | 2.05%   |
| IMC Networks USB2.0 HD UVC WebCam                | 36        | 1.84%   |
| Syntek Integrated Camera                         | 32        | 1.64%   |
| Realtek Integrated_Webcam_HD                     | 31        | 1.59%   |
| Chicony HD WebCam                                | 31        | 1.59%   |
| Microdia Integrated Webcam                       | 26        | 1.33%   |
| Chicony HP Truevision HD                         | 26        | 1.33%   |
| Apple Built-in iSight                            | 25        | 1.28%   |
| IMC Networks Integrated Camera                   | 24        | 1.23%   |
| Realtek USB Camera                               | 23        | 1.18%   |
| Acer Integrated Camera                           | 23        | 1.18%   |
| Chicony TOSHIBA Web Camera - HD                  | 21        | 1.07%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                  | 21        | 1.07%   |
| Samsung Galaxy series, misc. (MTP mode)          | 20        | 1.02%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 19        | 0.97%   |
| Sunplus Integrated_Webcam_HD                     | 18        | 0.92%   |
| Sunplus HD WebCam                                | 18        | 0.92%   |
| Logitech Webcam C270                             | 17        | 0.87%   |
| Bison Integrated Camera                          | 16        | 0.82%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 15        | 0.77%   |
| Realtek Integrated Webcam                        | 14        | 0.72%   |
| Realtek HP Truevision HD                         | 14        | 0.72%   |
| Microdia Webcam Vitade AF                        | 14        | 0.72%   |
| icSpring camera                                  | 14        | 0.72%   |
| Apple FaceTime HD Camera                         | 14        | 0.72%   |
| Alcor Micro USB 2.0 Camera                       | 14        | 0.72%   |
| Logitech HD Pro Webcam C920                      | 13        | 0.67%   |
| Lite-On HP HD Camera                             | 13        | 0.67%   |
| Chicony Lenovo EasyCamera                        | 13        | 0.67%   |
| Chicony HP Wide Vision HD Camera                 | 13        | 0.67%   |
| Chicony HP TrueVision HD Camera                  | 13        | 0.67%   |
| Chicony HP HD Camera                             | 13        | 0.67%   |
| Chicony EasyCamera                               | 13        | 0.67%   |
| Realtek Integrated Webcam HD                     | 12        | 0.61%   |
| Quanta HP Wide Vision HD Camera                  | 12        | 0.61%   |
| Microdia USB 2.0 Camera                          | 12        | 0.61%   |
| Acer Lenovo EasyCamera                           | 12        | 0.61%   |
| Chicony VGA WebCam                               | 11        | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 126       | 40.78%  |
| Synaptics                          | 48        | 15.53%  |
| Shenzhen Goodix Technology         | 42        | 13.59%  |
| AuthenTec                          | 30        | 9.71%   |
| Upek                               | 21        | 6.8%    |
| Elan Microelectronics              | 19        | 6.15%   |
| LighTuning Technology              | 10        | 3.24%   |
| STMicroelectronics                 | 6         | 1.94%   |
| Samsung Electronics                | 2         | 0.65%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.65%   |
| Next Biometrics                    | 1         | 0.32%   |
| HOLTEK                             | 1         | 0.32%   |
| Focal-systems.Corp                 | 1         | 0.32%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 24        | 7.77%   |
| Shenzhen Goodix  FingerPrint Device                                        | 24        | 7.77%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 20        | 6.47%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 15        | 4.85%   |
| Shenzhen Goodix Fingerprint Reader                                         | 15        | 4.85%   |
| Validity Sensors VFS491                                                    | 14        | 4.53%   |
| Elan ELAN:ARM-M4                                                           | 14        | 4.53%   |
| Validity Sensors Fingerprint scanner                                       | 11        | 3.56%   |
| AuthenTec AES2810                                                          | 11        | 3.56%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 10        | 3.24%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 10        | 3.24%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 9         | 2.91%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 8         | 2.59%   |
| Synaptics  WBDI                                                            | 8         | 2.59%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 7         | 2.27%   |
| Validity Sensors Synaptics WBDI                                            | 7         | 2.27%   |
| Synaptics UWP WBDI                                                         | 7         | 2.27%   |
| Synaptics Fingerprint reader [HP G6]                                       | 7         | 2.27%   |
| Synaptics WBDI                                                             | 6         | 1.94%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 6         | 1.94%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 1.94%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 5         | 1.62%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 5         | 1.62%   |
| Elan ELAN:Fingerprint                                                      | 5         | 1.62%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 1.29%   |
| LighTuning Fingerprint Sensor                                              | 4         | 1.29%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 1.29%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 1.29%   |
| AuthenTec AES1600                                                          | 4         | 1.29%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 0.97%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 0.97%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.65%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.65%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 0.65%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 0.65%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 0.65%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 0.65%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 2         | 0.65%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 2         | 0.65%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.32%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 69        | 53.08%  |
| Alcor Micro                       | 20        | 15.38%  |
| O2 Micro                          | 13        | 10%     |
| Lenovo                            | 6         | 4.62%   |
| Upek                              | 5         | 3.85%   |
| Realtek Semiconductor             | 3         | 2.31%   |
| Yubico.com                        | 2         | 1.54%   |
| VASCO Data Security International | 2         | 1.54%   |
| SCM Microsystems                  | 2         | 1.54%   |
| Fujitsu Siemens Computers         | 2         | 1.54%   |
| Advanced Card Systems             | 2         | 1.54%   |
| Reiner SCT Kartensysteme          | 1         | 0.77%   |
| OmniKey                           | 1         | 0.77%   |
| Jing-Mold Enterprise              | 1         | 0.77%   |
| Chicony Electronics               | 1         | 0.77%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 29        | 22.31%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 20        | 15.38%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 17        | 13.08%  |
| Broadcom 5880                                                                | 16        | 12.31%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 12        | 9.23%   |
| Lenovo Integrated Smart Card Reader                                          | 6         | 4.62%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 3.85%   |
| Broadcom 58200                                                               | 5         | 3.85%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 3         | 2.31%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 1.54%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 2         | 1.54%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 1.54%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.77%   |
| VASCO Data Security International DIGIPASS 870                               | 1         | 0.77%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.77%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.77%   |
| Reiner SCT Kartensysteme cyberJack e-com/pinpad                              | 1         | 0.77%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.77%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.77%   |
| Jing-Mold Enterprise HP USB Business Slim Smartcard CCID Keyboard            | 1         | 0.77%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.77%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.77%   |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 1         | 0.77%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2420      | 71.72%  |
| 1     | 776       | 23%     |
| 2     | 163       | 4.83%   |
| 3     | 13        | 0.39%   |
| 8     | 1         | 0.03%   |
| 4     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 303       | 27.2%   |
| Graphics card            | 222       | 19.93%  |
| Net/wireless             | 192       | 17.24%  |
| Multimedia controller    | 135       | 12.12%  |
| Chipcard                 | 119       | 10.68%  |
| Storage                  | 24        | 2.15%   |
| Bluetooth                | 23        | 2.06%   |
| Communication controller | 22        | 1.97%   |
| Sound                    | 11        | 0.99%   |
| Unassigned class         | 9         | 0.81%   |
| Camera                   | 9         | 0.81%   |
| Net/ethernet             | 8         | 0.72%   |
| Modem                    | 7         | 0.63%   |
| Network                  | 6         | 0.54%   |
| Storage/raid             | 5         | 0.45%   |
| Dvb card                 | 5         | 0.45%   |
| Card reader              | 5         | 0.45%   |
| Storage/ide              | 4         | 0.36%   |
| Storage/nvme             | 2         | 0.18%   |
| Flash memory             | 2         | 0.18%   |
| Unclassified device      | 1         | 0.09%   |

