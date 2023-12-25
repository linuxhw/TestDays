Linux in Lithuania - Tested Hardware & Statistics
-------------------------------------------------

A project to collect tested hardware configurations for Linux in Lithuania.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Lithuania/Desktop/README.md) and [notebooks](/Location/Lithuania/Notebook/README.md).

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

Total: 613

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASRock        | B760M Pro RS                | Desktop     | [f648cda96d](https://linux-hardware.org/?probe=f648cda96d) | Dec 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [5a16e00d6c](https://linux-hardware.org/?probe=5a16e00d6c) | Dec 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [262bfe0585](https://linux-hardware.org/?probe=262bfe0585) | Dec 14, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [fbe4d2ec54](https://linux-hardware.org/?probe=fbe4d2ec54) | Dec 08, 2023 |
| ASRock        | B760M Pro RS                | Desktop     | [77b3b5fc4d](https://linux-hardware.org/?probe=77b3b5fc4d) | Dec 07, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [f60bc8a984](https://linux-hardware.org/?probe=f60bc8a984) | Dec 03, 2023 |
| Dell          | Inspiron 7720               | Notebook    | [ec97e6b200](https://linux-hardware.org/?probe=ec97e6b200) | Dec 02, 2023 |
| Lenovo        | G580 20157                  | Notebook    | [f03f814b9c](https://linux-hardware.org/?probe=f03f814b9c) | Nov 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [aaccb61f12](https://linux-hardware.org/?probe=aaccb61f12) | Nov 24, 2023 |
| Dell          | 0NV0M7 A01                  | Desktop     | [f5ced375d8](https://linux-hardware.org/?probe=f5ced375d8) | Nov 17, 2023 |
| ASUSTek       | M50Vn                       | Notebook    | [9c35898e36](https://linux-hardware.org/?probe=9c35898e36) | Nov 16, 2023 |
| HP            | Mini 110-4100               | Notebook    | [a7aaa77ba5](https://linux-hardware.org/?probe=a7aaa77ba5) | Nov 16, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [3281df4dcd](https://linux-hardware.org/?probe=3281df4dcd) | Nov 15, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | Desktop     | [81fb4db1cc](https://linux-hardware.org/?probe=81fb4db1cc) | Nov 15, 2023 |
| Acer          | Extensa 5620                | Notebook    | [3c206e8578](https://linux-hardware.org/?probe=3c206e8578) | Nov 13, 2023 |
| Fujitsu       | LIFEBOOK E554               | Notebook    | [f212dcca29](https://linux-hardware.org/?probe=f212dcca29) | Nov 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [49b3b70e38](https://linux-hardware.org/?probe=49b3b70e38) | Nov 07, 2023 |
| Lenovo        | 3734 SDK0R32862 WIN 3258... | All in one  | [b153378dab](https://linux-hardware.org/?probe=b153378dab) | Nov 06, 2023 |
| ASRock        | X470 Taichi Ultimate        | Desktop     | [2b9b1f909c](https://linux-hardware.org/?probe=2b9b1f909c) | Nov 05, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [c7d2d860fb](https://linux-hardware.org/?probe=c7d2d860fb) | Nov 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [6e619afdba](https://linux-hardware.org/?probe=6e619afdba) | Oct 30, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [7f2d93dc09](https://linux-hardware.org/?probe=7f2d93dc09) | Oct 29, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [40769bf0a3](https://linux-hardware.org/?probe=40769bf0a3) | Oct 27, 2023 |
| MSI           | H81M-P33                    | Desktop     | [f59a3c2021](https://linux-hardware.org/?probe=f59a3c2021) | Oct 25, 2023 |
| Lenovo        | LOQ 15IRH8 82XV             | Notebook    | [a368ef3766](https://linux-hardware.org/?probe=a368ef3766) | Oct 22, 2023 |
| Samsung       | R530/R730/P530              | Notebook    | [ba506f75d1](https://linux-hardware.org/?probe=ba506f75d1) | Oct 21, 2023 |
| MSI           | H81M-P33                    | Desktop     | [04b9d686b6](https://linux-hardware.org/?probe=04b9d686b6) | Oct 21, 2023 |
| Lenovo        | LOQ 15IRH8 82XV             | Notebook    | [6bd80595bd](https://linux-hardware.org/?probe=6bd80595bd) | Oct 19, 2023 |
| HP            | EliteBook 2760p             | Notebook    | [3d62b547f3](https://linux-hardware.org/?probe=3d62b547f3) | Oct 16, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [02211f49db](https://linux-hardware.org/?probe=02211f49db) | Oct 08, 2023 |
| Lenovo        | ThinkPad T450 20BUS0H200    | Notebook    | [c38151f281](https://linux-hardware.org/?probe=c38151f281) | Sep 20, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [87f5275af6](https://linux-hardware.org/?probe=87f5275af6) | Sep 18, 2023 |
| Dell          | Vostro 3400                 | Notebook    | [faddcc51a7](https://linux-hardware.org/?probe=faddcc51a7) | Sep 17, 2023 |
| HP            | 829A                        | Mini pc     | [204c5a2a04](https://linux-hardware.org/?probe=204c5a2a04) | Sep 13, 2023 |
| LIVEFAN       | Unknown                     | Notebook    | [102a13c2c5](https://linux-hardware.org/?probe=102a13c2c5) | Sep 11, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [820eeccddf](https://linux-hardware.org/?probe=820eeccddf) | Sep 10, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [b52a6f9b59](https://linux-hardware.org/?probe=b52a6f9b59) | Sep 10, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [8b6b039242](https://linux-hardware.org/?probe=8b6b039242) | Sep 10, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [cdabed6210](https://linux-hardware.org/?probe=cdabed6210) | Sep 05, 2023 |
| ASUSTek       | ROG Strix G713RM_G713RM     | Notebook    | [0309bcca29](https://linux-hardware.org/?probe=0309bcca29) | Sep 05, 2023 |
| MSI           | Delta 15 A5EFK              | Notebook    | [8d2e359aec](https://linux-hardware.org/?probe=8d2e359aec) | Sep 03, 2023 |
| Intel         | D915GAV AAC64134-400        | Desktop     | [c7cad9e093](https://linux-hardware.org/?probe=c7cad9e093) | Aug 20, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [009242b925](https://linux-hardware.org/?probe=009242b925) | Aug 13, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [6855901c02](https://linux-hardware.org/?probe=6855901c02) | Aug 12, 2023 |
| HP            | Presario CQ57               | Notebook    | [cd84f6fa01](https://linux-hardware.org/?probe=cd84f6fa01) | Aug 06, 2023 |
| ASUSTek       | PN41                        | Mini pc     | [079428c572](https://linux-hardware.org/?probe=079428c572) | Aug 05, 2023 |
| ASUSTek       | PN41                        | Mini pc     | [663f989185](https://linux-hardware.org/?probe=663f989185) | Aug 05, 2023 |
| MSI           | B350 TOMAHAWK               | Desktop     | [3aa0e077c0](https://linux-hardware.org/?probe=3aa0e077c0) | Aug 05, 2023 |
| Acer          | Aspire xxxx                 | Notebook    | [8bc8edb11c](https://linux-hardware.org/?probe=8bc8edb11c) | Aug 03, 2023 |
| Dell          | G5 5590                     | Notebook    | [2745b35776](https://linux-hardware.org/?probe=2745b35776) | Jul 29, 2023 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [ea2f3666ba](https://linux-hardware.org/?probe=ea2f3666ba) | Jul 23, 2023 |
| Hardkernel    | ODROID-N2Plus               | Soc         | [73f0811a7b](https://linux-hardware.org/?probe=73f0811a7b) | Jul 23, 2023 |
| Dell          | Latitude E7250              | Notebook    | [4b91b375d4](https://linux-hardware.org/?probe=4b91b375d4) | Jul 23, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | Notebook    | [2f730cccf1](https://linux-hardware.org/?probe=2f730cccf1) | Jul 18, 2023 |
| Lenovo        | ThinkPad 10 2nd 20E4S0JA... | Tablet      | [d32668cf0c](https://linux-hardware.org/?probe=d32668cf0c) | Jul 15, 2023 |
| ASUSTek       | PRIME H410M-K               | Desktop     | [0dbf02ef16](https://linux-hardware.org/?probe=0dbf02ef16) | Jul 13, 2023 |
| Lenovo        | ThinkPad 10 2nd 20E4S0JA... | Tablet      | [6eb4d71389](https://linux-hardware.org/?probe=6eb4d71389) | Jul 10, 2023 |
| Alienware     | 17                          | Notebook    | [90e6911a60](https://linux-hardware.org/?probe=90e6911a60) | Jul 09, 2023 |
| Lenovo        | ThinkPad 10 2nd 20E4S0JA... | Tablet      | [8a5cbee239](https://linux-hardware.org/?probe=8a5cbee239) | Jul 08, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [2f1b70e168](https://linux-hardware.org/?probe=2f1b70e168) | Jul 08, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [282c9db256](https://linux-hardware.org/?probe=282c9db256) | Jul 08, 2023 |
| HP            | Compaq 6730b (GW687AV)      | Notebook    | [0b81f2e9b0](https://linux-hardware.org/?probe=0b81f2e9b0) | Jul 07, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [d487f9f635](https://linux-hardware.org/?probe=d487f9f635) | Jul 05, 2023 |
| Valve         | Jupiter                     | Notebook    | [d62c8c81d4](https://linux-hardware.org/?probe=d62c8c81d4) | Jul 04, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [97b1fc630a](https://linux-hardware.org/?probe=97b1fc630a) | Jun 25, 2023 |
| Lenovo        | ThinkPad 10 2nd 20E4S0JA... | Tablet      | [1773c81302](https://linux-hardware.org/?probe=1773c81302) | Jun 23, 2023 |
| Lenovo        | ThinkPad 10 2nd 20E4S0JA... | Tablet      | [80b535ff26](https://linux-hardware.org/?probe=80b535ff26) | Jun 23, 2023 |
| ASUSTek       | Z87-A                       | Desktop     | [ca84827c75](https://linux-hardware.org/?probe=ca84827c75) | Jun 21, 2023 |
| ASUSTek       | Z87-A                       | Desktop     | [a30c01fab8](https://linux-hardware.org/?probe=a30c01fab8) | Jun 21, 2023 |
| ASUSTek       | G50V                        | Notebook    | [32048be4b5](https://linux-hardware.org/?probe=32048be4b5) | Jun 16, 2023 |
| ASUSTek       | P5KPL-VM                    | Desktop     | [e2919326cd](https://linux-hardware.org/?probe=e2919326cd) | Jun 16, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [672a491915](https://linux-hardware.org/?probe=672a491915) | Jun 09, 2023 |
| ASUSTek       | P8H61-M LX2                 | Desktop     | [3fb94f0c4b](https://linux-hardware.org/?probe=3fb94f0c4b) | Jun 09, 2023 |
| Unknown       | Unknown                     | Notebook    | [c5accf4cf8](https://linux-hardware.org/?probe=c5accf4cf8) | Jun 09, 2023 |
| Unknown       | Unknown                     | Notebook    | [45e51a6b5d](https://linux-hardware.org/?probe=45e51a6b5d) | Jun 09, 2023 |
| Acer          | Aspire ES1-711              | Notebook    | [79bb8d8e39](https://linux-hardware.org/?probe=79bb8d8e39) | Jun 08, 2023 |
| ASRock        | QC5000M-ITX/PH              | Desktop     | [bdf4ee4d4f](https://linux-hardware.org/?probe=bdf4ee4d4f) | Jun 04, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [72ccbe10aa](https://linux-hardware.org/?probe=72ccbe10aa) | Jun 04, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [d2189d4a5f](https://linux-hardware.org/?probe=d2189d4a5f) | Jun 02, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [ea2d944708](https://linux-hardware.org/?probe=ea2d944708) | Jun 01, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [f9995cb422](https://linux-hardware.org/?probe=f9995cb422) | May 31, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [16f1d67220](https://linux-hardware.org/?probe=16f1d67220) | May 31, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [230a02bfda](https://linux-hardware.org/?probe=230a02bfda) | May 29, 2023 |
| MSI           | Bravo 15 A4DDR              | Notebook    | [0e9ccef97f](https://linux-hardware.org/?probe=0e9ccef97f) | May 27, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [767c697ac8](https://linux-hardware.org/?probe=767c697ac8) | May 27, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [0f593c947e](https://linux-hardware.org/?probe=0f593c947e) | May 27, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [e7a8d68439](https://linux-hardware.org/?probe=e7a8d68439) | May 27, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [3f7beed595](https://linux-hardware.org/?probe=3f7beed595) | May 25, 2023 |
| Dell          | Inspiron 15-3552            | Notebook    | [b2ade78a38](https://linux-hardware.org/?probe=b2ade78a38) | May 24, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [fff0e981f2](https://linux-hardware.org/?probe=fff0e981f2) | May 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [957b9f9de8](https://linux-hardware.org/?probe=957b9f9de8) | May 23, 2023 |
| Lenovo        | 3734 SDK0R32862 WIN 3258... | All in one  | [da9ebc680a](https://linux-hardware.org/?probe=da9ebc680a) | May 16, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [b8933c29ce](https://linux-hardware.org/?probe=b8933c29ce) | May 04, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [2660b0df6d](https://linux-hardware.org/?probe=2660b0df6d) | May 04, 2023 |
| ASRock        | B550M Phantom Gaming 4      | Desktop     | [db7e2a1d87](https://linux-hardware.org/?probe=db7e2a1d87) | Apr 29, 2023 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | Notebook    | [1ccae7d268](https://linux-hardware.org/?probe=1ccae7d268) | Apr 28, 2023 |
| ASUSTek       | P8B75-V                     | Desktop     | [f60927a4d8](https://linux-hardware.org/?probe=f60927a4d8) | Apr 24, 2023 |
| HUAWEI        | MRGF-XX                     | Notebook    | [25233eb8d1](https://linux-hardware.org/?probe=25233eb8d1) | Apr 22, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [517662dd54](https://linux-hardware.org/?probe=517662dd54) | Apr 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [083aef9e64](https://linux-hardware.org/?probe=083aef9e64) | Apr 20, 2023 |
| ASUSTek       | P8B75-V                     | Desktop     | [8957c4fdd0](https://linux-hardware.org/?probe=8957c4fdd0) | Apr 19, 2023 |
| Dell          | Inspiron 7720               | Notebook    | [27df270817](https://linux-hardware.org/?probe=27df270817) | Apr 09, 2023 |
| Lenovo        | ThinkPad W530 243852U       | Notebook    | [ea2ee391a5](https://linux-hardware.org/?probe=ea2ee391a5) | Apr 07, 2023 |
| Lenovo        | ThinkPad E470 20H1006VRT    | Notebook    | [a9b909f3df](https://linux-hardware.org/?probe=a9b909f3df) | Apr 05, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [e13bc4c0b8](https://linux-hardware.org/?probe=e13bc4c0b8) | Apr 04, 2023 |
| Notebook      | L140CU                      | Notebook    | [e24f4b285d](https://linux-hardware.org/?probe=e24f4b285d) | Mar 29, 2023 |
| Notebook      | L140CU                      | Notebook    | [b1b0a5fc03](https://linux-hardware.org/?probe=b1b0a5fc03) | Mar 29, 2023 |
| ASUSTek       | T100HAN                     | Notebook    | [c1f3b9658c](https://linux-hardware.org/?probe=c1f3b9658c) | Mar 26, 2023 |
| ASUSTek       | T100HAN                     | Notebook    | [3f74c992e7](https://linux-hardware.org/?probe=3f74c992e7) | Mar 26, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [644c9b9e55](https://linux-hardware.org/?probe=644c9b9e55) | Mar 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [06bd07f367](https://linux-hardware.org/?probe=06bd07f367) | Mar 21, 2023 |
| HP            | 1825                        | Desktop     | [73a2e18f3a](https://linux-hardware.org/?probe=73a2e18f3a) | Mar 20, 2023 |
| Fujitsu Si... | LIFEBOOK S7110              | Notebook    | [ba879b76da](https://linux-hardware.org/?probe=ba879b76da) | Mar 19, 2023 |
| Fujitsu Si... | LIFEBOOK S7110              | Notebook    | [547559d982](https://linux-hardware.org/?probe=547559d982) | Mar 19, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | Notebook    | [809d9ecb40](https://linux-hardware.org/?probe=809d9ecb40) | Mar 18, 2023 |
| ASUSTek       | N550JK                      | Notebook    | [6b93d4a171](https://linux-hardware.org/?probe=6b93d4a171) | Mar 17, 2023 |
| MSI           | GT72 2PE                    | Notebook    | [0483315836](https://linux-hardware.org/?probe=0483315836) | Mar 16, 2023 |
| ASUSTek       | N61Jq                       | Notebook    | [706eca5e8a](https://linux-hardware.org/?probe=706eca5e8a) | Mar 15, 2023 |
| HP            | 1850                        | Desktop     | [1b56ff36d2](https://linux-hardware.org/?probe=1b56ff36d2) | Mar 10, 2023 |
| ASUSTek       | T100HAN                     | Notebook    | [b4046bce15](https://linux-hardware.org/?probe=b4046bce15) | Mar 10, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [cbdc8bcd6a](https://linux-hardware.org/?probe=cbdc8bcd6a) | Mar 06, 2023 |
| MSI           | GS66 Stealth 10UE           | Notebook    | [4500ce221e](https://linux-hardware.org/?probe=4500ce221e) | Mar 02, 2023 |
| MSI           | GS66 Stealth 10UE           | Notebook    | [f193cf790d](https://linux-hardware.org/?probe=f193cf790d) | Feb 27, 2023 |
| MSI           | GS66 Stealth 10UE           | Notebook    | [eba178253a](https://linux-hardware.org/?probe=eba178253a) | Feb 27, 2023 |
| ASRock        | H67M-GE/HT                  | Desktop     | [3410887193](https://linux-hardware.org/?probe=3410887193) | Feb 25, 2023 |
| MSI           | GS66 Stealth 10UE           | Notebook    | [3382fa1bad](https://linux-hardware.org/?probe=3382fa1bad) | Feb 24, 2023 |
| MSI           | GS66 Stealth 10UE           | Notebook    | [ffcf782944](https://linux-hardware.org/?probe=ffcf782944) | Feb 23, 2023 |
| HP            | EliteBook 2540p             | Notebook    | [bf037f7503](https://linux-hardware.org/?probe=bf037f7503) | Feb 21, 2023 |
| Apple         | MacBookPro11,5              | Notebook    | [7933746ce1](https://linux-hardware.org/?probe=7933746ce1) | Feb 17, 2023 |
| MSI           | GS66 Stealth 10UE           | Notebook    | [587bd9e282](https://linux-hardware.org/?probe=587bd9e282) | Feb 16, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [8ba717ec45](https://linux-hardware.org/?probe=8ba717ec45) | Feb 13, 2023 |
| Gigabyte      | GB-BSi5-1135G7              | Desktop     | [93002e901f](https://linux-hardware.org/?probe=93002e901f) | Feb 10, 2023 |
| MSI           | H61M-P23                    | Desktop     | [86404b5b68](https://linux-hardware.org/?probe=86404b5b68) | Feb 09, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [c0c511ec65](https://linux-hardware.org/?probe=c0c511ec65) | Feb 03, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [175211d52c](https://linux-hardware.org/?probe=175211d52c) | Jan 29, 2023 |
| HP            | EliteBook 2540p             | Notebook    | [f03240c746](https://linux-hardware.org/?probe=f03240c746) | Jan 25, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [a3a0a3a505](https://linux-hardware.org/?probe=a3a0a3a505) | Jan 25, 2023 |
| ASUSTek       | GL552VX                     | Notebook    | [d196ac82e2](https://linux-hardware.org/?probe=d196ac82e2) | Jan 23, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [bd51c2a953](https://linux-hardware.org/?probe=bd51c2a953) | Jan 20, 2023 |
| MSI           | GP70 2PE                    | Notebook    | [697974aa68](https://linux-hardware.org/?probe=697974aa68) | Jan 08, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [10ae4cbb25](https://linux-hardware.org/?probe=10ae4cbb25) | Jan 08, 2023 |
| HP            | ProBook 450 G0              | Notebook    | [e7af660f1a](https://linux-hardware.org/?probe=e7af660f1a) | Jan 05, 2023 |
| Acer          | Iconia Tab W501             | Tablet      | [196d64e793](https://linux-hardware.org/?probe=196d64e793) | Dec 25, 2022 |
| Acer          | Iconia Tab W501             | Tablet      | [32f9cc7e0b](https://linux-hardware.org/?probe=32f9cc7e0b) | Dec 25, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [ec6b0e70a2](https://linux-hardware.org/?probe=ec6b0e70a2) | Dec 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [658e730bd3](https://linux-hardware.org/?probe=658e730bd3) | Dec 20, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [76c76bdd82](https://linux-hardware.org/?probe=76c76bdd82) | Dec 14, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [1db7d2fa59](https://linux-hardware.org/?probe=1db7d2fa59) | Dec 14, 2022 |
| Microsoft     | Surface with Windows RT     | Tablet      | [11fe73ea9d](https://linux-hardware.org/?probe=11fe73ea9d) | Dec 11, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [7a6ba7238f](https://linux-hardware.org/?probe=7a6ba7238f) | Dec 08, 2022 |
| Dell          | Vostro 5502                 | Notebook    | [862097a47c](https://linux-hardware.org/?probe=862097a47c) | Dec 05, 2022 |
| ASUSTek       | X550CL                      | Notebook    | [06c7fdf5c9](https://linux-hardware.org/?probe=06c7fdf5c9) | Nov 26, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [afea73cc2a](https://linux-hardware.org/?probe=afea73cc2a) | Nov 22, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [b7ff70b9b2](https://linux-hardware.org/?probe=b7ff70b9b2) | Nov 14, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [f6bfbc00ba](https://linux-hardware.org/?probe=f6bfbc00ba) | Nov 14, 2022 |
| HP            | 3397                        | Desktop     | [27c0a5213d](https://linux-hardware.org/?probe=27c0a5213d) | Nov 11, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | Notebook    | [5d479ec43f](https://linux-hardware.org/?probe=5d479ec43f) | Nov 08, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [bdca860f08](https://linux-hardware.org/?probe=bdca860f08) | Nov 06, 2022 |
| MSI           | Bravo 15 A4DDR              | Notebook    | [8598cf3c36](https://linux-hardware.org/?probe=8598cf3c36) | Nov 04, 2022 |
| MSI           | MAG Z390 TOMAHAWK           | Desktop     | [4f1e0d9702](https://linux-hardware.org/?probe=4f1e0d9702) | Nov 02, 2022 |
| MSI           | MAG Z390 TOMAHAWK           | Desktop     | [842320d7b3](https://linux-hardware.org/?probe=842320d7b3) | Nov 02, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [496a16216c](https://linux-hardware.org/?probe=496a16216c) | Nov 02, 2022 |
| Lenovo        | ThinkCentre M81 5048E2G     | Desktop     | [35840b3b8c](https://linux-hardware.org/?probe=35840b3b8c) | Oct 23, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [f38198e874](https://linux-hardware.org/?probe=f38198e874) | Oct 23, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [b374c2dff6](https://linux-hardware.org/?probe=b374c2dff6) | Oct 20, 2022 |
| HP            | 3047h                       | Desktop     | [1a0f4c46f9](https://linux-hardware.org/?probe=1a0f4c46f9) | Oct 20, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | Notebook    | [46cb50f2f6](https://linux-hardware.org/?probe=46cb50f2f6) | Oct 19, 2022 |
| BESSTAR Te... | UM700                       | Desktop     | [5c2590f03f](https://linux-hardware.org/?probe=5c2590f03f) | Oct 18, 2022 |
| BESSTAR Te... | UM700                       | Desktop     | [df0afd4326](https://linux-hardware.org/?probe=df0afd4326) | Oct 18, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | Notebook    | [1258429041](https://linux-hardware.org/?probe=1258429041) | Oct 13, 2022 |
| Dell          | G3 3579                     | Notebook    | [2191706dd0](https://linux-hardware.org/?probe=2191706dd0) | Oct 11, 2022 |
| Dell          | G3 3579                     | Notebook    | [7f20851840](https://linux-hardware.org/?probe=7f20851840) | Oct 10, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [53ca822dcd](https://linux-hardware.org/?probe=53ca822dcd) | Oct 07, 2022 |
| Dell          | 0F96C8 A00                  | All in one  | [5b19e47aa9](https://linux-hardware.org/?probe=5b19e47aa9) | Oct 03, 2022 |
| HP            | EliteBook 850 G3            | Notebook    | [7bbcf621e1](https://linux-hardware.org/?probe=7bbcf621e1) | Sep 20, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [96e0712ca0](https://linux-hardware.org/?probe=96e0712ca0) | Sep 19, 2022 |
| Gigabyte      | EX58-UD3R                   | Desktop     | [e482e214bd](https://linux-hardware.org/?probe=e482e214bd) | Sep 12, 2022 |
| MSI           | MAG B460M MORTAR            | Desktop     | [258d99cc9e](https://linux-hardware.org/?probe=258d99cc9e) | Sep 06, 2022 |
| ASUSTek       | X540LA                      | Notebook    | [3ba0635033](https://linux-hardware.org/?probe=3ba0635033) | Sep 04, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [d8505e212b](https://linux-hardware.org/?probe=d8505e212b) | Sep 02, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [8e366d7e21](https://linux-hardware.org/?probe=8e366d7e21) | Sep 02, 2022 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [5ee4e3aec0](https://linux-hardware.org/?probe=5ee4e3aec0) | Sep 02, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [9a05044c38](https://linux-hardware.org/?probe=9a05044c38) | Aug 27, 2022 |
| HP            | ProBook 440 G3              | Notebook    | [e51d4ae241](https://linux-hardware.org/?probe=e51d4ae241) | Aug 20, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [ab3425dd99](https://linux-hardware.org/?probe=ab3425dd99) | Aug 17, 2022 |
| Lenovo        | ThinkPad T590 20N4004EMH    | Notebook    | [42d130e184](https://linux-hardware.org/?probe=42d130e184) | Aug 16, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [5967f639c3](https://linux-hardware.org/?probe=5967f639c3) | Aug 16, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [e63db5769a](https://linux-hardware.org/?probe=e63db5769a) | Aug 14, 2022 |
| Apple         | Mac-A369DDC4E67F1C45 iMa... | All in one  | [6440e9a054](https://linux-hardware.org/?probe=6440e9a054) | Aug 12, 2022 |
| Apple         | Mac-A369DDC4E67F1C45 iMa... | All in one  | [063c2efc80](https://linux-hardware.org/?probe=063c2efc80) | Aug 12, 2022 |
| MSI           | MS-16F1                     | Notebook    | [0a28da4f53](https://linux-hardware.org/?probe=0a28da4f53) | Aug 12, 2022 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [f3a7c88015](https://linux-hardware.org/?probe=f3a7c88015) | Aug 11, 2022 |
| Lenovo        | ThinkPad T430s 2356LNG      | Notebook    | [255560d675](https://linux-hardware.org/?probe=255560d675) | Aug 06, 2022 |
| HP            | Compaq Presario CQ60        | Notebook    | [06fe56588b](https://linux-hardware.org/?probe=06fe56588b) | Jul 27, 2022 |
| ASUSTek       | Maximus Formula             | Desktop     | [2e71fca3d5](https://linux-hardware.org/?probe=2e71fca3d5) | Jul 22, 2022 |
| Dell          | 07T4MC A11                  | Desktop     | [61d394116d](https://linux-hardware.org/?probe=61d394116d) | Jul 20, 2022 |
| ASUSTek       | Maximus Formula             | Desktop     | [3c600cafa6](https://linux-hardware.org/?probe=3c600cafa6) | Jul 17, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [0687ecd744](https://linux-hardware.org/?probe=0687ecd744) | Jul 14, 2022 |
| ASUSTek       | Maximus Formula             | Desktop     | [cd81bcaf19](https://linux-hardware.org/?probe=cd81bcaf19) | Jul 13, 2022 |
| eMachines     | eME443                      | Notebook    | [9197e8ef17](https://linux-hardware.org/?probe=9197e8ef17) | Jul 11, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [00d543ee46](https://linux-hardware.org/?probe=00d543ee46) | Jul 07, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [a6420a89b6](https://linux-hardware.org/?probe=a6420a89b6) | Jun 29, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [58ab145788](https://linux-hardware.org/?probe=58ab145788) | Jun 24, 2022 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | Notebook    | [f23b75e3ca](https://linux-hardware.org/?probe=f23b75e3ca) | Jun 19, 2022 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | Notebook    | [8f2740e70e](https://linux-hardware.org/?probe=8f2740e70e) | Jun 18, 2022 |
| MSI           | Z270-A PRO                  | Desktop     | [0d78267c59](https://linux-hardware.org/?probe=0d78267c59) | Jun 16, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [bd3336efcb](https://linux-hardware.org/?probe=bd3336efcb) | Jun 14, 2022 |
| Panasonic     | CF-52VDA131M                | Notebook    | [aa40370193](https://linux-hardware.org/?probe=aa40370193) | Jun 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [67aa7158d3](https://linux-hardware.org/?probe=67aa7158d3) | May 24, 2022 |
| Dell          | Latitude E5570              | Notebook    | [310aadd79a](https://linux-hardware.org/?probe=310aadd79a) | May 24, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [a068dc57c8](https://linux-hardware.org/?probe=a068dc57c8) | May 13, 2022 |
| Dell          | 0F96C8 A00                  | All in one  | [b0e5c67fda](https://linux-hardware.org/?probe=b0e5c67fda) | May 11, 2022 |
| Alienware     | 17                          | Notebook    | [b30786ba0e](https://linux-hardware.org/?probe=b30786ba0e) | May 10, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [96f6c5bf2a](https://linux-hardware.org/?probe=96f6c5bf2a) | May 10, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20STS... | Notebook    | [3e171a4858](https://linux-hardware.org/?probe=3e171a4858) | May 09, 2022 |
| Dell          | 03NVJ6 A02                  | Desktop     | [9e90322621](https://linux-hardware.org/?probe=9e90322621) | May 06, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [8439c948ec](https://linux-hardware.org/?probe=8439c948ec) | May 06, 2022 |
| Dell          | 03NVJ6 A02                  | Desktop     | [08e665f8bf](https://linux-hardware.org/?probe=08e665f8bf) | May 04, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [36cabd86ba](https://linux-hardware.org/?probe=36cabd86ba) | May 04, 2022 |
| Dell          | Inspiron 7720               | Notebook    | [a2d8358964](https://linux-hardware.org/?probe=a2d8358964) | May 02, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [52609c3695](https://linux-hardware.org/?probe=52609c3695) | Apr 29, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [96fc510369](https://linux-hardware.org/?probe=96fc510369) | Apr 29, 2022 |
| Dell          | Latitude 5401               | Notebook    | [d115db916d](https://linux-hardware.org/?probe=d115db916d) | Apr 23, 2022 |
| Dell          | Latitude 5401               | Notebook    | [c9f380ea26](https://linux-hardware.org/?probe=c9f380ea26) | Apr 23, 2022 |
| ASUSTek       | X55A                        | Notebook    | [9188b40f88](https://linux-hardware.org/?probe=9188b40f88) | Apr 23, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [a3bf1cf766](https://linux-hardware.org/?probe=a3bf1cf766) | Apr 19, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [f2e4d7052d](https://linux-hardware.org/?probe=f2e4d7052d) | Apr 16, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [bacc580e7a](https://linux-hardware.org/?probe=bacc580e7a) | Apr 13, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [8ba327aee7](https://linux-hardware.org/?probe=8ba327aee7) | Apr 07, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [a69ec475f7](https://linux-hardware.org/?probe=a69ec475f7) | Apr 03, 2022 |
| ASUSTek       | PRIME H510M-R               | Desktop     | [6736f1afa6](https://linux-hardware.org/?probe=6736f1afa6) | Apr 03, 2022 |
| Dell          | Vostro 3580                 | Notebook    | [0ec442c0be](https://linux-hardware.org/?probe=0ec442c0be) | Mar 28, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [aa02b40ff7](https://linux-hardware.org/?probe=aa02b40ff7) | Mar 27, 2022 |
| ASUSTek       | X55A                        | Notebook    | [9b02d587bf](https://linux-hardware.org/?probe=9b02d587bf) | Mar 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [c3ffdf7791](https://linux-hardware.org/?probe=c3ffdf7791) | Mar 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [77b0be92c8](https://linux-hardware.org/?probe=77b0be92c8) | Mar 17, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [5d0113f42d](https://linux-hardware.org/?probe=5d0113f42d) | Mar 16, 2022 |
| HP            | ProBook 455 G1              | Notebook    | [c6ad6edf70](https://linux-hardware.org/?probe=c6ad6edf70) | Mar 10, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [4b0c952d9b](https://linux-hardware.org/?probe=4b0c952d9b) | Mar 09, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [2e06b2fed8](https://linux-hardware.org/?probe=2e06b2fed8) | Feb 27, 2022 |
| ASRock        | QC5000M-ITX/PH              | Desktop     | [573ff5a0d0](https://linux-hardware.org/?probe=573ff5a0d0) | Feb 16, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [54f55cc209](https://linux-hardware.org/?probe=54f55cc209) | Feb 16, 2022 |
| Lenovo        | Yoga Creator 7 15IMH05 8... | Notebook    | [12a1b54a3a](https://linux-hardware.org/?probe=12a1b54a3a) | Feb 16, 2022 |
| ASUSTek       | Maximus Formula             | Desktop     | [130c778a64](https://linux-hardware.org/?probe=130c778a64) | Feb 11, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [3c46e807da](https://linux-hardware.org/?probe=3c46e807da) | Feb 09, 2022 |
| ASUSTek       | H110M-C                     | Desktop     | [82f3d6edf9](https://linux-hardware.org/?probe=82f3d6edf9) | Feb 09, 2022 |
| ASUSTek       | X55A                        | Notebook    | [dbbb7b1213](https://linux-hardware.org/?probe=dbbb7b1213) | Feb 07, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [4a36d79506](https://linux-hardware.org/?probe=4a36d79506) | Feb 04, 2022 |
| ASUSTek       | H110M-C                     | Desktop     | [6ba127c715](https://linux-hardware.org/?probe=6ba127c715) | Feb 04, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [5616230c16](https://linux-hardware.org/?probe=5616230c16) | Feb 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [a7d1f29451](https://linux-hardware.org/?probe=a7d1f29451) | Jan 31, 2022 |
| Jumper        | EZbook                      | Notebook    | [4fa449c0ce](https://linux-hardware.org/?probe=4fa449c0ce) | Jan 27, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [269396626c](https://linux-hardware.org/?probe=269396626c) | Jan 23, 2022 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [8f6a587ed3](https://linux-hardware.org/?probe=8f6a587ed3) | Jan 20, 2022 |
| ASUSTek       | H110M-C                     | Desktop     | [be4291793d](https://linux-hardware.org/?probe=be4291793d) | Jan 10, 2022 |
| ASUSTek       | N53SV                       | Notebook    | [a5b43fd8b4](https://linux-hardware.org/?probe=a5b43fd8b4) | Jan 05, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [a769ac4242](https://linux-hardware.org/?probe=a769ac4242) | Jan 01, 2022 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [8e0b4fec6c](https://linux-hardware.org/?probe=8e0b4fec6c) | Dec 26, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [d824937c84](https://linux-hardware.org/?probe=d824937c84) | Dec 22, 2021 |
| Gigabyte      | H61M-DS2 DVI                | Desktop     | [1252e4adb0](https://linux-hardware.org/?probe=1252e4adb0) | Dec 18, 2021 |
| Acer          | Aspire A515-56              | Notebook    | [113924cdba](https://linux-hardware.org/?probe=113924cdba) | Dec 12, 2021 |
| HP            | ENVY x360 Convertible       | Convertible | [bc5923cefe](https://linux-hardware.org/?probe=bc5923cefe) | Dec 04, 2021 |
| HP            | ENVY x360 Convertible       | Convertible | [f8ed9dbcf4](https://linux-hardware.org/?probe=f8ed9dbcf4) | Dec 04, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [cc0c8de988](https://linux-hardware.org/?probe=cc0c8de988) | Nov 27, 2021 |
| ASUSTek       | N53SV                       | Notebook    | [557bb216fc](https://linux-hardware.org/?probe=557bb216fc) | Nov 20, 2021 |
| Dell          | 084J0R A00                  | Desktop     | [2f5b5e4c72](https://linux-hardware.org/?probe=2f5b5e4c72) | Nov 19, 2021 |
| HP            | ENVY x360 Convertible       | Convertible | [d998144d2e](https://linux-hardware.org/?probe=d998144d2e) | Nov 18, 2021 |
| Dell          | 084J0R A00                  | Desktop     | [1907e644a0](https://linux-hardware.org/?probe=1907e644a0) | Nov 18, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [cf48db68a3](https://linux-hardware.org/?probe=cf48db68a3) | Nov 18, 2021 |
| Lenovo        | ThinkPad L440 20ASA10P00    | Notebook    | [3119a05196](https://linux-hardware.org/?probe=3119a05196) | Nov 15, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [f455ee4572](https://linux-hardware.org/?probe=f455ee4572) | Nov 14, 2021 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [b1edada81b](https://linux-hardware.org/?probe=b1edada81b) | Nov 13, 2021 |
| Lenovo        | IdeaPad MIIX 700-12ISK 8... | Notebook    | [b455b4457c](https://linux-hardware.org/?probe=b455b4457c) | Nov 13, 2021 |
| Lenovo        | IdeaPad MIIX 700-12ISK 8... | Notebook    | [3cfeff5a7f](https://linux-hardware.org/?probe=3cfeff5a7f) | Nov 13, 2021 |
| ASUSTek       | X55A                        | Notebook    | [a55961748f](https://linux-hardware.org/?probe=a55961748f) | Nov 10, 2021 |
| ASUSTek       | X55A                        | Notebook    | [8c59513ced](https://linux-hardware.org/?probe=8c59513ced) | Nov 10, 2021 |
| ASUSTek       | K52F                        | Notebook    | [f90cbb4d26](https://linux-hardware.org/?probe=f90cbb4d26) | Nov 04, 2021 |
| Dell          | 0F96C8 A00                  | All in one  | [fe22676441](https://linux-hardware.org/?probe=fe22676441) | Nov 03, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [54e81a5d8d](https://linux-hardware.org/?probe=54e81a5d8d) | Nov 02, 2021 |
| ASUSTek       | N73SV                       | Notebook    | [997a879973](https://linux-hardware.org/?probe=997a879973) | Oct 29, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [3adcb9ecf9](https://linux-hardware.org/?probe=3adcb9ecf9) | Oct 26, 2021 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [1876547e8e](https://linux-hardware.org/?probe=1876547e8e) | Oct 25, 2021 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [078863a9b7](https://linux-hardware.org/?probe=078863a9b7) | Oct 25, 2021 |
| MSI           | MEG X570 UNIFY              | Desktop     | [7b9e7ec5f4](https://linux-hardware.org/?probe=7b9e7ec5f4) | Oct 23, 2021 |
| Toshiba       | Satellite C50D-A-13G        | Notebook    | [32f90e6cf8](https://linux-hardware.org/?probe=32f90e6cf8) | Oct 18, 2021 |
| MSI           | B85M GAMING                 | Desktop     | [55468e657e](https://linux-hardware.org/?probe=55468e657e) | Oct 16, 2021 |
| ASUSTek       | X79-DELUXE                  | Desktop     | [c49552f889](https://linux-hardware.org/?probe=c49552f889) | Oct 14, 2021 |
| ASUSTek       | X79-DELUXE                  | Desktop     | [d606b23e02](https://linux-hardware.org/?probe=d606b23e02) | Oct 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [a927e8ff8e](https://linux-hardware.org/?probe=a927e8ff8e) | Oct 06, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [5db12e2534](https://linux-hardware.org/?probe=5db12e2534) | Oct 02, 2021 |
| Alienware     | 17                          | Notebook    | [1a6f72a2fd](https://linux-hardware.org/?probe=1a6f72a2fd) | Oct 02, 2021 |
| Alienware     | 17                          | Notebook    | [fac8c2f153](https://linux-hardware.org/?probe=fac8c2f153) | Oct 02, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [239dced9a1](https://linux-hardware.org/?probe=239dced9a1) | Sep 19, 2021 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [4db5d51b06](https://linux-hardware.org/?probe=4db5d51b06) | Sep 17, 2021 |
| ASUSTek       | Maximus Formula             | Desktop     | [34c7038f6f](https://linux-hardware.org/?probe=34c7038f6f) | Sep 12, 2021 |
| Dell          | 0F96C8 A00                  | All in one  | [6c5f2b8c6d](https://linux-hardware.org/?probe=6c5f2b8c6d) | Sep 11, 2021 |
| HP            | 250 G4                      | Notebook    | [6c66581e62](https://linux-hardware.org/?probe=6c66581e62) | Sep 06, 2021 |
| HP            | 09F8h                       | Desktop     | [60e1a81b56](https://linux-hardware.org/?probe=60e1a81b56) | Sep 05, 2021 |
| HP            | 250 G4                      | Notebook    | [619fff9116](https://linux-hardware.org/?probe=619fff9116) | Sep 04, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [057cfec49e](https://linux-hardware.org/?probe=057cfec49e) | Sep 01, 2021 |
| ASUSTek       | X551CAP                     | Notebook    | [626023b280](https://linux-hardware.org/?probe=626023b280) | Aug 24, 2021 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [523f5ca193](https://linux-hardware.org/?probe=523f5ca193) | Aug 23, 2021 |
| ASUSTek       | X551CAP                     | Notebook    | [9e64453373](https://linux-hardware.org/?probe=9e64453373) | Aug 23, 2021 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [90e24e0335](https://linux-hardware.org/?probe=90e24e0335) | Aug 22, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [1c59d4f975](https://linux-hardware.org/?probe=1c59d4f975) | Aug 19, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [c358dfd2e6](https://linux-hardware.org/?probe=c358dfd2e6) | Aug 18, 2021 |
| Fujitsu       | D3400-B2 S26361-D3400-B2    | Desktop     | [067c79a9fe](https://linux-hardware.org/?probe=067c79a9fe) | Aug 13, 2021 |
| HP            | Pavilion dv7                | Notebook    | [640a5fb2b3](https://linux-hardware.org/?probe=640a5fb2b3) | Aug 13, 2021 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | Notebook    | [5d33b12497](https://linux-hardware.org/?probe=5d33b12497) | Aug 13, 2021 |
| MSI           | MAG B460M MORTAR            | Desktop     | [652f1a31e9](https://linux-hardware.org/?probe=652f1a31e9) | Aug 10, 2021 |
| MSI           | MAG B460M MORTAR            | Desktop     | [80648f256b](https://linux-hardware.org/?probe=80648f256b) | Aug 10, 2021 |
| HP            | EliteBook 8440p             | Notebook    | [80cb2748cf](https://linux-hardware.org/?probe=80cb2748cf) | Aug 02, 2021 |
| HP            | 250 G4                      | Notebook    | [bd80a8cdf0](https://linux-hardware.org/?probe=bd80a8cdf0) | Aug 02, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [4752d9cb90](https://linux-hardware.org/?probe=4752d9cb90) | Aug 01, 2021 |
| ASRock        | G31M-VS2                    | Desktop     | [ffde05f551](https://linux-hardware.org/?probe=ffde05f551) | Aug 01, 2021 |
| ASRock        | Z87 Extreme4                | Desktop     | [ee3189a7be](https://linux-hardware.org/?probe=ee3189a7be) | Jul 11, 2021 |
| ASRock        | X570M Pro4                  | Desktop     | [714a2fb6ec](https://linux-hardware.org/?probe=714a2fb6ec) | Jul 02, 2021 |
| Gigabyte      | P41-ES3G                    | Desktop     | [653a634621](https://linux-hardware.org/?probe=653a634621) | Jun 29, 2021 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [e78af672d3](https://linux-hardware.org/?probe=e78af672d3) | Jun 18, 2021 |
| Alienware     | 17                          | Notebook    | [9d281e3351](https://linux-hardware.org/?probe=9d281e3351) | Jun 16, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [4020e881a1](https://linux-hardware.org/?probe=4020e881a1) | Jun 16, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [7fa170e5ca](https://linux-hardware.org/?probe=7fa170e5ca) | Jun 10, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [45b678cc45](https://linux-hardware.org/?probe=45b678cc45) | Jun 07, 2021 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | Notebook    | [dab115ff9f](https://linux-hardware.org/?probe=dab115ff9f) | Jun 07, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [63b5d9a81a](https://linux-hardware.org/?probe=63b5d9a81a) | Jun 05, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [56308999d2](https://linux-hardware.org/?probe=56308999d2) | Jun 05, 2021 |
| HP            | ProBook 430 G8 Notebook ... | Notebook    | [20b885e70c](https://linux-hardware.org/?probe=20b885e70c) | Jun 01, 2021 |
| HP            | ProBook 430 G8 Notebook ... | Notebook    | [74979cf76a](https://linux-hardware.org/?probe=74979cf76a) | Jun 01, 2021 |
| ASUSTek       | K52F                        | Notebook    | [92db46133f](https://linux-hardware.org/?probe=92db46133f) | May 24, 2021 |
| Dell          | Precision M4700             | Notebook    | [1d14e22fbd](https://linux-hardware.org/?probe=1d14e22fbd) | May 22, 2021 |
| Dell          | Inspiron 5579               | Notebook    | [83c30b9084](https://linux-hardware.org/?probe=83c30b9084) | May 15, 2021 |
| MSI           | H81M-P33                    | Desktop     | [ab8a093d72](https://linux-hardware.org/?probe=ab8a093d72) | May 12, 2021 |
| ASUSTek       | UX430UAR                    | Notebook    | [84b8a6331d](https://linux-hardware.org/?probe=84b8a6331d) | May 08, 2021 |
| Unknown       | Unknown                     | Notebook    | [50d2466e84](https://linux-hardware.org/?probe=50d2466e84) | May 06, 2021 |
| Unknown       | Unknown                     | Notebook    | [410d40ca5f](https://linux-hardware.org/?probe=410d40ca5f) | May 06, 2021 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | Notebook    | [49aad4b320](https://linux-hardware.org/?probe=49aad4b320) | May 04, 2021 |
| Gigabyte      | M55S-S3                     | Desktop     | [7114f9857a](https://linux-hardware.org/?probe=7114f9857a) | Apr 29, 2021 |
| Lenovo        | ThinkPad P53 20QN0034MH     | Notebook    | [bcb2272cf0](https://linux-hardware.org/?probe=bcb2272cf0) | Apr 25, 2021 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | Notebook    | [26133ce35a](https://linux-hardware.org/?probe=26133ce35a) | Apr 24, 2021 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [dc665ba00d](https://linux-hardware.org/?probe=dc665ba00d) | Apr 14, 2021 |
| Lenovo        | ThinkPad L580 20LW0010GE    | Notebook    | [1e30c2850c](https://linux-hardware.org/?probe=1e30c2850c) | Apr 09, 2021 |
| Gigabyte      | B85M-HD3                    | Desktop     | [499ccddfc2](https://linux-hardware.org/?probe=499ccddfc2) | Apr 09, 2021 |
| Lenovo        | ThinkPad Edge E540 20C6C... | Notebook    | [faca4e4038](https://linux-hardware.org/?probe=faca4e4038) | Apr 08, 2021 |
| MSI           | MAG B460M MORTAR            | Desktop     | [f7341fd5b2](https://linux-hardware.org/?probe=f7341fd5b2) | Apr 01, 2021 |
| Lenovo        | HASWELLREFRESHDT NO DPK     | All in one  | [feedaccb5b](https://linux-hardware.org/?probe=feedaccb5b) | Mar 24, 2021 |
| Gigabyte      | H81M-D2V                    | Desktop     | [d62d3a2dad](https://linux-hardware.org/?probe=d62d3a2dad) | Mar 19, 2021 |
| HP            | 805A                        | Desktop     | [76ad927d3b](https://linux-hardware.org/?probe=76ad927d3b) | Mar 18, 2021 |
| Acer          | Aspire A515-56              | Notebook    | [1bdc8a756f](https://linux-hardware.org/?probe=1bdc8a756f) | Mar 17, 2021 |
| Gigabyte      | B85M-HD3                    | Desktop     | [ad58858e33](https://linux-hardware.org/?probe=ad58858e33) | Mar 17, 2021 |
| ASUSTek       | K50C                        | Notebook    | [4ccd0463c4](https://linux-hardware.org/?probe=4ccd0463c4) | Mar 17, 2021 |
| Lenovo        | ThinkPad T480 20L50002MH    | Notebook    | [554173e0d7](https://linux-hardware.org/?probe=554173e0d7) | Mar 17, 2021 |
| ASUSTek       | K50C                        | Notebook    | [65941d7354](https://linux-hardware.org/?probe=65941d7354) | Mar 17, 2021 |
| Intel         | DH67BL AAG10189-208         | Desktop     | [391c72b961](https://linux-hardware.org/?probe=391c72b961) | Mar 17, 2021 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [530ac66726](https://linux-hardware.org/?probe=530ac66726) | Mar 17, 2021 |
| Intel         | DH55HC AAE70933-501         | Desktop     | [6a44f69309](https://linux-hardware.org/?probe=6a44f69309) | Mar 17, 2021 |
| Gigabyte      | H55M-UD2H                   | Desktop     | [e671743616](https://linux-hardware.org/?probe=e671743616) | Mar 17, 2021 |
| Lenovo        | MIIX 2 10 20359             | Tablet      | [edff48d58f](https://linux-hardware.org/?probe=edff48d58f) | Mar 13, 2021 |
| Dell          | Latitude 7380               | Notebook    | [43510cebc1](https://linux-hardware.org/?probe=43510cebc1) | Mar 13, 2021 |
| Lenovo        | ThinkPad W530 243852U       | Notebook    | [15c953bc70](https://linux-hardware.org/?probe=15c953bc70) | Mar 09, 2021 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [d4e62a32a8](https://linux-hardware.org/?probe=d4e62a32a8) | Mar 04, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [7ab4c4e090](https://linux-hardware.org/?probe=7ab4c4e090) | Mar 03, 2021 |
| Dell          | Inspiron 5758               | Notebook    | [f371afba83](https://linux-hardware.org/?probe=f371afba83) | Feb 27, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [d36796da44](https://linux-hardware.org/?probe=d36796da44) | Feb 27, 2021 |
| Lenovo        | ThinkPad T430 2347EV8       | Notebook    | [3bf5967320](https://linux-hardware.org/?probe=3bf5967320) | Feb 19, 2021 |
| Gigabyte      | Z370M DS3H-CF               | Desktop     | [e4702a62a8](https://linux-hardware.org/?probe=e4702a62a8) | Feb 19, 2021 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [ceffe7a79e](https://linux-hardware.org/?probe=ceffe7a79e) | Feb 16, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | Notebook    | [c2408f8152](https://linux-hardware.org/?probe=c2408f8152) | Feb 16, 2021 |
| Intel         | DH61WW AAG23116-206         | Desktop     | [446351d845](https://linux-hardware.org/?probe=446351d845) | Feb 15, 2021 |
| ASUSTek       | Maximus Formula             | Desktop     | [b5e1004909](https://linux-hardware.org/?probe=b5e1004909) | Feb 12, 2021 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | Desktop     | [504106eb2c](https://linux-hardware.org/?probe=504106eb2c) | Feb 12, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [3aed966657](https://linux-hardware.org/?probe=3aed966657) | Feb 10, 2021 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [c951026b91](https://linux-hardware.org/?probe=c951026b91) | Feb 07, 2021 |
| ASUSTek       | Maximus Formula             | Desktop     | [80724d2ba1](https://linux-hardware.org/?probe=80724d2ba1) | Jan 31, 2021 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [a398ccbc3d](https://linux-hardware.org/?probe=a398ccbc3d) | Jan 31, 2021 |
| Lenovo        | ThinkPad T440p 20AWS4XN0... | Notebook    | [f25ec6b2f3](https://linux-hardware.org/?probe=f25ec6b2f3) | Jan 31, 2021 |
| ASRock        | H61M/U3S3                   | Desktop     | [2d831a72bb](https://linux-hardware.org/?probe=2d831a72bb) | Jan 27, 2021 |
| Acer          | Extensa 5220                | Notebook    | [20ea0cd55c](https://linux-hardware.org/?probe=20ea0cd55c) | Jan 23, 2021 |
| Acer          | Extensa 5220                | Notebook    | [9fe95abf63](https://linux-hardware.org/?probe=9fe95abf63) | Jan 23, 2021 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [a38c700d1b](https://linux-hardware.org/?probe=a38c700d1b) | Jan 16, 2021 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | Notebook    | [b7b3175352](https://linux-hardware.org/?probe=b7b3175352) | Jan 14, 2021 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [95389bff49](https://linux-hardware.org/?probe=95389bff49) | Jan 13, 2021 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | Notebook    | [ed7d9bff15](https://linux-hardware.org/?probe=ed7d9bff15) | Jan 13, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [91885a7829](https://linux-hardware.org/?probe=91885a7829) | Jan 05, 2021 |
| ASUSTek       | Leonite2                    | Desktop     | [9867e750d0](https://linux-hardware.org/?probe=9867e750d0) | Jan 01, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [34198a369d](https://linux-hardware.org/?probe=34198a369d) | Dec 26, 2020 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [f4ab3e4295](https://linux-hardware.org/?probe=f4ab3e4295) | Dec 26, 2020 |
| Acer          | Aspire 1410                 | Notebook    | [3ff80e7b33](https://linux-hardware.org/?probe=3ff80e7b33) | Dec 26, 2020 |
| ASUSTek       | X510UNR                     | Notebook    | [44990d7fc0](https://linux-hardware.org/?probe=44990d7fc0) | Dec 22, 2020 |
| ASUSTek       | X510UNR                     | Notebook    | [e6e91c5ea2](https://linux-hardware.org/?probe=e6e91c5ea2) | Dec 16, 2020 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | Notebook    | [5b56323f14](https://linux-hardware.org/?probe=5b56323f14) | Dec 15, 2020 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | Notebook    | [2c7c774492](https://linux-hardware.org/?probe=2c7c774492) | Dec 15, 2020 |
| ASRock        | B450M Pro4                  | Desktop     | [649ea3d331](https://linux-hardware.org/?probe=649ea3d331) | Dec 10, 2020 |
| Toshiba       | Satellite L855              | Notebook    | [48d0f1a04c](https://linux-hardware.org/?probe=48d0f1a04c) | Dec 08, 2020 |
| ASRock        | G41C-GS                     | Desktop     | [5c89245f08](https://linux-hardware.org/?probe=5c89245f08) | Dec 02, 2020 |
| Dell          | Latitude E7470              | Notebook    | [3c76403f27](https://linux-hardware.org/?probe=3c76403f27) | Dec 01, 2020 |
| Lenovo        | HASWELLREFRESHDT NO DPK     | All in one  | [a37a75cdcb](https://linux-hardware.org/?probe=a37a75cdcb) | Nov 29, 2020 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [b2cc866da6](https://linux-hardware.org/?probe=b2cc866da6) | Nov 24, 2020 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [a58e43a971](https://linux-hardware.org/?probe=a58e43a971) | Nov 20, 2020 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [374504e0bd](https://linux-hardware.org/?probe=374504e0bd) | Nov 20, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [1310e54c33](https://linux-hardware.org/?probe=1310e54c33) | Nov 20, 2020 |
| Gigabyte      | H81M-D2V                    | Desktop     | [49bd67196b](https://linux-hardware.org/?probe=49bd67196b) | Nov 20, 2020 |
| Lenovo        | HASWELLREFRESHDT NO DPK     | All in one  | [574e7cc90c](https://linux-hardware.org/?probe=574e7cc90c) | Nov 18, 2020 |
| Lenovo        | HASWELLREFRESHDT NO DPK     | All in one  | [778d8e5380](https://linux-hardware.org/?probe=778d8e5380) | Nov 18, 2020 |
| ASUSTek       | X510UNR                     | Notebook    | [fb41abdfb1](https://linux-hardware.org/?probe=fb41abdfb1) | Nov 13, 2020 |
| Alienware     | 17                          | Notebook    | [59fdbdd4d7](https://linux-hardware.org/?probe=59fdbdd4d7) | Nov 11, 2020 |
| ASUSTek       | GL553VD                     | Notebook    | [86837daf1c](https://linux-hardware.org/?probe=86837daf1c) | Nov 10, 2020 |
| ASRock        | 880GM-LE FX                 | Desktop     | [c16ef7ddf0](https://linux-hardware.org/?probe=c16ef7ddf0) | Nov 09, 2020 |
| Gigabyte      | H77M-D3H                    | Desktop     | [2788cb02ed](https://linux-hardware.org/?probe=2788cb02ed) | Nov 08, 2020 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | Notebook    | [cf2cbcbe72](https://linux-hardware.org/?probe=cf2cbcbe72) | Nov 05, 2020 |
| HP            | 3048h                       | Desktop     | [96c9bd0ab6](https://linux-hardware.org/?probe=96c9bd0ab6) | Nov 05, 2020 |
| MSI           | Z87M-G43                    | Desktop     | [9de0cc7bbf](https://linux-hardware.org/?probe=9de0cc7bbf) | Nov 03, 2020 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | Notebook    | [39dcf2485b](https://linux-hardware.org/?probe=39dcf2485b) | Nov 03, 2020 |
| Lenovo        | ThinkPad T500 2241W8Q       | Notebook    | [f507c9b3e5](https://linux-hardware.org/?probe=f507c9b3e5) | Oct 25, 2020 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | Notebook    | [1b2dd49d08](https://linux-hardware.org/?probe=1b2dd49d08) | Oct 20, 2020 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | Notebook    | [b3e5017b13](https://linux-hardware.org/?probe=b3e5017b13) | Oct 20, 2020 |
| HP            | 0A64h                       | Desktop     | [88899b775b](https://linux-hardware.org/?probe=88899b775b) | Oct 20, 2020 |
| Dell          | Inspiron 7577               | Notebook    | [09fbf70f49](https://linux-hardware.org/?probe=09fbf70f49) | Oct 16, 2020 |
| HP            | ProBook 450 G1              | Notebook    | [c69e6488fd](https://linux-hardware.org/?probe=c69e6488fd) | Oct 14, 2020 |
| Dell          | G5 5587                     | Notebook    | [ba6fbeb10c](https://linux-hardware.org/?probe=ba6fbeb10c) | Oct 09, 2020 |
| Dell          | G5 5587                     | Notebook    | [8b28232f32](https://linux-hardware.org/?probe=8b28232f32) | Oct 09, 2020 |
| Lenovo        | HASWELLREFRESHDT NO DPK     | All in one  | [5b52249750](https://linux-hardware.org/?probe=5b52249750) | Oct 04, 2020 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [a5e1c0e5f3](https://linux-hardware.org/?probe=a5e1c0e5f3) | Oct 03, 2020 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [0362c406d8](https://linux-hardware.org/?probe=0362c406d8) | Oct 03, 2020 |
| HP            | ProBook 4720s               | Notebook    | [a882fdd653](https://linux-hardware.org/?probe=a882fdd653) | Oct 02, 2020 |
| ASUSTek       | N56VZ                       | Notebook    | [d4d74a6e34](https://linux-hardware.org/?probe=d4d74a6e34) | Sep 29, 2020 |
| ASUSTek       | K52JT                       | Notebook    | [2acb54cb0d](https://linux-hardware.org/?probe=2acb54cb0d) | Sep 28, 2020 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [b765d71b82](https://linux-hardware.org/?probe=b765d71b82) | Sep 28, 2020 |
| Lenovo        | ThinkPad Edge E540 20C6C... | Notebook    | [87092c4768](https://linux-hardware.org/?probe=87092c4768) | Sep 21, 2020 |
| Lenovo        | ThinkPad Edge E540 20C6C... | Notebook    | [48825acdce](https://linux-hardware.org/?probe=48825acdce) | Sep 18, 2020 |
| Gigabyte      | H81M-D2V                    | Desktop     | [c46dd29f7a](https://linux-hardware.org/?probe=c46dd29f7a) | Sep 17, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [aef0cb23ec](https://linux-hardware.org/?probe=aef0cb23ec) | Sep 16, 2020 |
| HP            | ProBook 450 G6              | Notebook    | [6fffc9928f](https://linux-hardware.org/?probe=6fffc9928f) | Sep 10, 2020 |
| HP            | ProBook 450 G6              | Notebook    | [7465caa486](https://linux-hardware.org/?probe=7465caa486) | Sep 10, 2020 |
| Lenovo        | ThinkPad T460s 20F90058M... | Notebook    | [352f3932b4](https://linux-hardware.org/?probe=352f3932b4) | Sep 09, 2020 |
| Dell          | Latitude 5491               | Notebook    | [06d4120fc1](https://linux-hardware.org/?probe=06d4120fc1) | Sep 08, 2020 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [d4d40f1808](https://linux-hardware.org/?probe=d4d40f1808) | Sep 04, 2020 |
| Lenovo        | ThinkPad L440 20ASS10F00    | Notebook    | [cb6b544787](https://linux-hardware.org/?probe=cb6b544787) | Sep 04, 2020 |
| ASUSTek       | PRIME A320M-R               | Desktop     | [0097d71249](https://linux-hardware.org/?probe=0097d71249) | Sep 04, 2020 |
| Timi          | TM1701                      | Notebook    | [4c01fca357](https://linux-hardware.org/?probe=4c01fca357) | Aug 25, 2020 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [4bd12a2bcc](https://linux-hardware.org/?probe=4bd12a2bcc) | Aug 25, 2020 |
| ASRock        | AB350M Pro4                 | Desktop     | [a5338ac2ec](https://linux-hardware.org/?probe=a5338ac2ec) | Aug 22, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [d053bf3f76](https://linux-hardware.org/?probe=d053bf3f76) | Aug 18, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [2551496802](https://linux-hardware.org/?probe=2551496802) | Aug 18, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [8a4f211ca2](https://linux-hardware.org/?probe=8a4f211ca2) | Aug 18, 2020 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [f6a94becbf](https://linux-hardware.org/?probe=f6a94becbf) | Aug 13, 2020 |
| Dell          | XPS M1330                   | Notebook    | [4a907eebb9](https://linux-hardware.org/?probe=4a907eebb9) | Aug 02, 2020 |
| MSI           | H81M-P33                    | Desktop     | [5d7abb7a5b](https://linux-hardware.org/?probe=5d7abb7a5b) | Jul 31, 2020 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [a52cd7499e](https://linux-hardware.org/?probe=a52cd7499e) | Jul 28, 2020 |
| Acer          | Swift SF314-54G             | Notebook    | [a4948f0d33](https://linux-hardware.org/?probe=a4948f0d33) | Jul 24, 2020 |
| Acer          | Swift SF314-54G             | Notebook    | [cd250d0e7b](https://linux-hardware.org/?probe=cd250d0e7b) | Jul 24, 2020 |
| Lenovo        | ThinkPad T500 2241W8Q       | Notebook    | [810f713a78](https://linux-hardware.org/?probe=810f713a78) | Jul 24, 2020 |
| HP            | Pavilion dv6                | Notebook    | [4c09684767](https://linux-hardware.org/?probe=4c09684767) | Jul 23, 2020 |
| ASUSTek       | PRIME H310M-E               | Desktop     | [f31ba594be](https://linux-hardware.org/?probe=f31ba594be) | Jul 19, 2020 |
| ASUSTek       | PRIME H310M-E               | Desktop     | [90f3c751dc](https://linux-hardware.org/?probe=90f3c751dc) | Jul 19, 2020 |
| ASUSTek       | N71Ja                       | Notebook    | [db78759a1a](https://linux-hardware.org/?probe=db78759a1a) | Jul 12, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [0fb6ac937d](https://linux-hardware.org/?probe=0fb6ac937d) | Jul 06, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [fc16d36603](https://linux-hardware.org/?probe=fc16d36603) | Jul 03, 2020 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [9c1c6b6919](https://linux-hardware.org/?probe=9c1c6b6919) | Jun 30, 2020 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [ab2ec330ab](https://linux-hardware.org/?probe=ab2ec330ab) | Jun 24, 2020 |
| Dell          | XPS 15 7590                 | Notebook    | [78351d2937](https://linux-hardware.org/?probe=78351d2937) | Jun 22, 2020 |
| Lenovo        | ThinkPad L460 20FU0007MH    | Notebook    | [27a87ca264](https://linux-hardware.org/?probe=27a87ca264) | Jun 18, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [9c0419884f](https://linux-hardware.org/?probe=9c0419884f) | Jun 17, 2020 |
| Lenovo        | ThinkPad T60 1951FDG        | Notebook    | [ed27c7aa81](https://linux-hardware.org/?probe=ed27c7aa81) | Jun 10, 2020 |
| Lenovo        | ThinkPad T60 1951FDG        | Notebook    | [574368a188](https://linux-hardware.org/?probe=574368a188) | Jun 09, 2020 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [feebe9e438](https://linux-hardware.org/?probe=feebe9e438) | Jun 03, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [ebac9eaefe](https://linux-hardware.org/?probe=ebac9eaefe) | Jun 02, 2020 |
| HP            | EliteBook 8440p             | Notebook    | [cc3e01ff0f](https://linux-hardware.org/?probe=cc3e01ff0f) | May 29, 2020 |
| Lenovo        | Y50-70 20378                | Notebook    | [85443edb8d](https://linux-hardware.org/?probe=85443edb8d) | May 22, 2020 |
| Dell          | Inspiron 1520               | Notebook    | [368e9f53e5](https://linux-hardware.org/?probe=368e9f53e5) | May 22, 2020 |
| Samsung       | RC530/RC730                 | Notebook    | [7e180f5fd2](https://linux-hardware.org/?probe=7e180f5fd2) | May 21, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [04ed3686b1](https://linux-hardware.org/?probe=04ed3686b1) | May 19, 2020 |
| ASUSTek       | X51RL                       | Notebook    | [afee28a69b](https://linux-hardware.org/?probe=afee28a69b) | May 16, 2020 |
| HP            | EliteBook 8440p             | Notebook    | [5856d8fd4a](https://linux-hardware.org/?probe=5856d8fd4a) | Apr 30, 2020 |
| Lenovo        | ThinkPad Edge E320 12985... | Notebook    | [e4a1ece1ec](https://linux-hardware.org/?probe=e4a1ece1ec) | Apr 28, 2020 |
| ASUSTek       | Z9PE-D8 WS                  | Server      | [6100c873a3](https://linux-hardware.org/?probe=6100c873a3) | Apr 26, 2020 |
| Intel         | DP55WB AAE64798-205         | Desktop     | [cbc58485b8](https://linux-hardware.org/?probe=cbc58485b8) | Apr 23, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [70daf3ad77](https://linux-hardware.org/?probe=70daf3ad77) | Apr 20, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [c4b061e0f5](https://linux-hardware.org/?probe=c4b061e0f5) | Apr 19, 2020 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [11251407bd](https://linux-hardware.org/?probe=11251407bd) | Apr 11, 2020 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [37f223475f](https://linux-hardware.org/?probe=37f223475f) | Apr 11, 2020 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [21a5c2580f](https://linux-hardware.org/?probe=21a5c2580f) | Apr 10, 2020 |
| ASUSTek       | M50SA                       | Notebook    | [a7381b478e](https://linux-hardware.org/?probe=a7381b478e) | Apr 10, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [38086a42be](https://linux-hardware.org/?probe=38086a42be) | Apr 01, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [2246b94acb](https://linux-hardware.org/?probe=2246b94acb) | Apr 01, 2020 |
| Acer          | Aspire 5733                 | Notebook    | [0552ab024f](https://linux-hardware.org/?probe=0552ab024f) | Apr 01, 2020 |
| Acer          | Aspire 5733                 | Notebook    | [0fd03337ad](https://linux-hardware.org/?probe=0fd03337ad) | Mar 29, 2020 |
| Acer          | Aspire 5733                 | Notebook    | [055f9887c3](https://linux-hardware.org/?probe=055f9887c3) | Mar 29, 2020 |
| Lenovo        | G550 20023                  | Notebook    | [0e9b1fb324](https://linux-hardware.org/?probe=0e9b1fb324) | Mar 29, 2020 |
| HP            | 630                         | Notebook    | [fc76abe01b](https://linux-hardware.org/?probe=fc76abe01b) | Mar 29, 2020 |
| Lenovo        | ThinkPad L580 20LW0010GE    | Notebook    | [23a0bdb230](https://linux-hardware.org/?probe=23a0bdb230) | Mar 19, 2020 |
| MSI           | H61M-P20                    | Desktop     | [bd9fc44d34](https://linux-hardware.org/?probe=bd9fc44d34) | Mar 17, 2020 |
| ASUSTek       | K43E                        | Notebook    | [ef4c10e588](https://linux-hardware.org/?probe=ef4c10e588) | Mar 11, 2020 |
| ASUSTek       | K43E                        | Notebook    | [d03eae9c55](https://linux-hardware.org/?probe=d03eae9c55) | Mar 10, 2020 |
| MSI           | H61M-P20                    | Desktop     | [9111061475](https://linux-hardware.org/?probe=9111061475) | Mar 10, 2020 |
| ASUSTek       | K53E                        | Notebook    | [8729f56cdc](https://linux-hardware.org/?probe=8729f56cdc) | Mar 07, 2020 |
| MSI           | Z170A GAMING M5             | Desktop     | [f1eb3e7e12](https://linux-hardware.org/?probe=f1eb3e7e12) | Mar 01, 2020 |
| MSI           | Z170A GAMING M5             | Desktop     | [7058bdb7d6](https://linux-hardware.org/?probe=7058bdb7d6) | Mar 01, 2020 |
| ASUSTek       | K53SV                       | Notebook    | [3b537b4a10](https://linux-hardware.org/?probe=3b537b4a10) | Mar 01, 2020 |
| Gigabyte      | X570 GAMING X               | Desktop     | [816d9c42da](https://linux-hardware.org/?probe=816d9c42da) | Feb 28, 2020 |
| HP            | 1589                        | Desktop     | [0c9be85544](https://linux-hardware.org/?probe=0c9be85544) | Feb 21, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [f08088a64d](https://linux-hardware.org/?probe=f08088a64d) | Feb 20, 2020 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [2d24c5a932](https://linux-hardware.org/?probe=2d24c5a932) | Feb 15, 2020 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [c95a831b3c](https://linux-hardware.org/?probe=c95a831b3c) | Feb 11, 2020 |
| HP            | ProBook 4740s               | Notebook    | [4d4d26ef02](https://linux-hardware.org/?probe=4d4d26ef02) | Feb 03, 2020 |
| Lenovo        | ThinkPad E590 20NB0065MH    | Notebook    | [e895371f73](https://linux-hardware.org/?probe=e895371f73) | Feb 03, 2020 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [ca1f92519f](https://linux-hardware.org/?probe=ca1f92519f) | Jan 29, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [226b976601](https://linux-hardware.org/?probe=226b976601) | Jan 27, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [6973864306](https://linux-hardware.org/?probe=6973864306) | Jan 25, 2020 |
| Acer          | Aspire V3-772               | Notebook    | [17005306cd](https://linux-hardware.org/?probe=17005306cd) | Jan 24, 2020 |
| ASUSTek       | K52JT                       | Notebook    | [4335a97dd6](https://linux-hardware.org/?probe=4335a97dd6) | Jan 24, 2020 |
| Dell          | G3 3579                     | Notebook    | [56f84db06b](https://linux-hardware.org/?probe=56f84db06b) | Jan 22, 2020 |
| Lenovo        | ThinkPad T500 2241W8Q       | Notebook    | [f22d44d39f](https://linux-hardware.org/?probe=f22d44d39f) | Jan 22, 2020 |
| Panasonic     | CF-52WEBBYDE                | Notebook    | [0d21ee7063](https://linux-hardware.org/?probe=0d21ee7063) | Jan 17, 2020 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [cf8ada0ad0](https://linux-hardware.org/?probe=cf8ada0ad0) | Jan 16, 2020 |
| ASUSTek       | TUF Gaming FX705DY_TUF70... | Notebook    | [f57bc0120b](https://linux-hardware.org/?probe=f57bc0120b) | Jan 15, 2020 |
| MSI           | B450M PRO-VDH               | Desktop     | [5b95761a5d](https://linux-hardware.org/?probe=5b95761a5d) | Jan 03, 2020 |
| MSI           | B450M PRO-VDH V2            | Desktop     | [660da3e630](https://linux-hardware.org/?probe=660da3e630) | Jan 03, 2020 |
| MSI           | B450M PRO-VDH               | Desktop     | [f45d7203c0](https://linux-hardware.org/?probe=f45d7203c0) | Jan 03, 2020 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [b0c00423bd](https://linux-hardware.org/?probe=b0c00423bd) | Dec 31, 2019 |
| ASUSTek       | ZenBook UX534FTC_UX533FT... | Notebook    | [4ea8d503ae](https://linux-hardware.org/?probe=4ea8d503ae) | Dec 13, 2019 |
| ASUSTek       | ZenBook UX534FTC_UX533FT... | Notebook    | [a298251c28](https://linux-hardware.org/?probe=a298251c28) | Dec 13, 2019 |
| MSI           | B450M PRO-VDH               | Desktop     | [924e886e1f](https://linux-hardware.org/?probe=924e886e1f) | Dec 13, 2019 |
| MSI           | B450M PRO-VDH               | Desktop     | [4a5d98c236](https://linux-hardware.org/?probe=4a5d98c236) | Dec 13, 2019 |
| MSI           | B450M PRO-VDH               | Desktop     | [b919c0cb27](https://linux-hardware.org/?probe=b919c0cb27) | Dec 13, 2019 |
| ASRock        | H61M-VS                     | Desktop     | [6d7e3aa70a](https://linux-hardware.org/?probe=6d7e3aa70a) | Dec 11, 2019 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [5b4aff6fe8](https://linux-hardware.org/?probe=5b4aff6fe8) | Dec 03, 2019 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [abeaa01348](https://linux-hardware.org/?probe=abeaa01348) | Dec 03, 2019 |
| HP            | EliteBook 856               | Notebook    | [80cf2af707](https://linux-hardware.org/?probe=80cf2af707) | Nov 22, 2019 |
| HP            | Pavilion dv6                | Notebook    | [6f6270eb8e](https://linux-hardware.org/?probe=6f6270eb8e) | Nov 16, 2019 |
| HP            | Pavilion dv6                | Notebook    | [c08e4bac64](https://linux-hardware.org/?probe=c08e4bac64) | Nov 16, 2019 |
| HP            | EliteBook 8460p             | Notebook    | [56a12d5f20](https://linux-hardware.org/?probe=56a12d5f20) | Nov 09, 2019 |
| Acer          | AOD260                      | Notebook    | [a911172500](https://linux-hardware.org/?probe=a911172500) | Nov 09, 2019 |
| ASUSTek       | H110M-R                     | Desktop     | [3068ae6e29](https://linux-hardware.org/?probe=3068ae6e29) | Nov 05, 2019 |
| Sony          | VGN-C260E                   | Notebook    | [c623de88ee](https://linux-hardware.org/?probe=c623de88ee) | Oct 24, 2019 |
| Lenovo        | G505s 20255                 | Notebook    | [36deb3b32d](https://linux-hardware.org/?probe=36deb3b32d) | Oct 13, 2019 |
| HP            | Pavilion dv6                | Notebook    | [c2264e7abd](https://linux-hardware.org/?probe=c2264e7abd) | Oct 11, 2019 |
| ASUSTek       | H110M-R                     | Desktop     | [dc23169db8](https://linux-hardware.org/?probe=dc23169db8) | Oct 10, 2019 |
| Lenovo        | ThinkPad T490 20N3000KMH    | Notebook    | [77b1afae40](https://linux-hardware.org/?probe=77b1afae40) | Oct 09, 2019 |
| Fujitsu Si... | D2119 S26361-D2119          | Server      | [1a0dfe074e](https://linux-hardware.org/?probe=1a0dfe074e) | Oct 01, 2019 |
| Fujitsu Si... | D2119 S26361-D2119          | Server      | [7cad023dc8](https://linux-hardware.org/?probe=7cad023dc8) | Oct 01, 2019 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [ec4b0c74d2](https://linux-hardware.org/?probe=ec4b0c74d2) | Sep 27, 2019 |
| HP            | 0A60h                       | Desktop     | [e587b4122a](https://linux-hardware.org/?probe=e587b4122a) | Sep 22, 2019 |
| ASUSTek       | K53SV                       | Notebook    | [61f7ec13d8](https://linux-hardware.org/?probe=61f7ec13d8) | Sep 19, 2019 |
| ASUSTek       | K53E                        | Notebook    | [71fd2610fe](https://linux-hardware.org/?probe=71fd2610fe) | Sep 15, 2019 |
| ASUSTek       | K53E                        | Notebook    | [e435064ad7](https://linux-hardware.org/?probe=e435064ad7) | Sep 15, 2019 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [3baafefb84](https://linux-hardware.org/?probe=3baafefb84) | Aug 27, 2019 |
| Prestigio     | PSB141C02                   | Notebook    | [3e96d56c17](https://linux-hardware.org/?probe=3e96d56c17) | Aug 25, 2019 |
| ASUSTek       | K53E                        | Notebook    | [c1811b7ec3](https://linux-hardware.org/?probe=c1811b7ec3) | Aug 23, 2019 |
| Lenovo        | ThinkPad T490 20N3000KMH    | Notebook    | [15419d9561](https://linux-hardware.org/?probe=15419d9561) | Aug 20, 2019 |
| HP            | Laptop 15-bw0xx             | Notebook    | [7653d7fa4d](https://linux-hardware.org/?probe=7653d7fa4d) | Jul 29, 2019 |
| Lenovo        | G550 20023                  | Notebook    | [601d53f9eb](https://linux-hardware.org/?probe=601d53f9eb) | Jul 23, 2019 |
| Lenovo        | Yoga 510-14ISK 80S7         | Convertible | [5b8d494c04](https://linux-hardware.org/?probe=5b8d494c04) | Jul 12, 2019 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [fd394cc113](https://linux-hardware.org/?probe=fd394cc113) | Jun 05, 2019 |
| Lenovo        | ThinkPad R500 27327KG       | Notebook    | [c8b31c9d99](https://linux-hardware.org/?probe=c8b31c9d99) | Jun 04, 2019 |
| Dell          | Inspiron N5010              | Notebook    | [23d8e1dd30](https://linux-hardware.org/?probe=23d8e1dd30) | May 31, 2019 |
| Acer          | TravelMate 5740G            | Notebook    | [0d4611c952](https://linux-hardware.org/?probe=0d4611c952) | May 25, 2019 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [be887070fe](https://linux-hardware.org/?probe=be887070fe) | May 17, 2019 |
| Toshiba       | Satellite C50D-A-13G        | Notebook    | [c39268dff8](https://linux-hardware.org/?probe=c39268dff8) | May 13, 2019 |
| Toshiba       | Satellite C50D-A-13G        | Notebook    | [e0d133befc](https://linux-hardware.org/?probe=e0d133befc) | May 13, 2019 |
| HP            | ProBook 6555b               | Notebook    | [598fc6c1ca](https://linux-hardware.org/?probe=598fc6c1ca) | May 13, 2019 |
| HP            | ProBook 4540s               | Notebook    | [2e61bfe1be](https://linux-hardware.org/?probe=2e61bfe1be) | Apr 28, 2019 |
| HP            | ProBook 4540s               | Notebook    | [8d460232a9](https://linux-hardware.org/?probe=8d460232a9) | Apr 28, 2019 |
| Dell          | Inspiron 5737               | Notebook    | [2c7d308e3a](https://linux-hardware.org/?probe=2c7d308e3a) | Apr 26, 2019 |
| Dell          | Inspiron 5737               | Notebook    | [dcf03f780e](https://linux-hardware.org/?probe=dcf03f780e) | Apr 26, 2019 |
| Acer          | TravelMate 5740G            | Notebook    | [6b69828c13](https://linux-hardware.org/?probe=6b69828c13) | Apr 07, 2019 |
| Sony          | VPCZ1390S                   | Notebook    | [eb4e58c4d9](https://linux-hardware.org/?probe=eb4e58c4d9) | Mar 05, 2019 |
| Sony          | VPCZ1390S                   | Notebook    | [8995c67e48](https://linux-hardware.org/?probe=8995c67e48) | Mar 05, 2019 |
| ASRock        | X370 Taichi                 | Desktop     | [283ce85ac6](https://linux-hardware.org/?probe=283ce85ac6) | Feb 20, 2019 |
| Lenovo        | ThinkPad X230 2325AEG       | Notebook    | [2b8bcfe576](https://linux-hardware.org/?probe=2b8bcfe576) | Feb 19, 2019 |
| ASUSTek       | X550LB                      | Notebook    | [992697103b](https://linux-hardware.org/?probe=992697103b) | Jan 18, 2019 |
| ASUSTek       | X550LB                      | Notebook    | [5228ac3dbc](https://linux-hardware.org/?probe=5228ac3dbc) | Jan 18, 2019 |
| Dell          | 0XFWHV A00                  | Desktop     | [f9e47efc1f](https://linux-hardware.org/?probe=f9e47efc1f) | Jan 12, 2019 |
| Lenovo        | ThinkPad L440 20ASA10P00    | Notebook    | [dffa2ed3ef](https://linux-hardware.org/?probe=dffa2ed3ef) | Dec 20, 2018 |
| Lenovo        | ThinkPad L440 20ASA10P00    | Notebook    | [e192353344](https://linux-hardware.org/?probe=e192353344) | Dec 20, 2018 |
| Lenovo        | G550 20023                  | Notebook    | [54fd0e13d2](https://linux-hardware.org/?probe=54fd0e13d2) | Oct 29, 2018 |
| MSI           | Z170A GAMING M5             | Desktop     | [68365011c2](https://linux-hardware.org/?probe=68365011c2) | Oct 26, 2018 |
| Lenovo        | G550 20023                  | Notebook    | [3011864d4b](https://linux-hardware.org/?probe=3011864d4b) | Oct 25, 2018 |
| Intel         | DB65AL AAG12530-302         | Desktop     | [be0b280760](https://linux-hardware.org/?probe=be0b280760) | Oct 25, 2018 |
| ASUSTek       | K53E                        | Notebook    | [0e63193763](https://linux-hardware.org/?probe=0e63193763) | Oct 21, 2018 |
| ASUSTek       | K53E                        | Notebook    | [8a053e30bf](https://linux-hardware.org/?probe=8a053e30bf) | Sep 30, 2018 |
| HP            | 0A60h                       | Desktop     | [887d9e063a](https://linux-hardware.org/?probe=887d9e063a) | Sep 24, 2018 |
| ASUSTek       | K53E                        | Notebook    | [8e1eab57d7](https://linux-hardware.org/?probe=8e1eab57d7) | Sep 03, 2018 |
| ASUSTek       | 1225B                       | Notebook    | [fb333d2cde](https://linux-hardware.org/?probe=fb333d2cde) | Aug 23, 2018 |
| HP            | 0A60h                       | Desktop     | [180ad06c55](https://linux-hardware.org/?probe=180ad06c55) | Aug 21, 2018 |
| ASUSTek       | K53E                        | Notebook    | [8ebafe3965](https://linux-hardware.org/?probe=8ebafe3965) | Aug 04, 2018 |
| HP            | 0A60h                       | Desktop     | [4ed0a42e5c](https://linux-hardware.org/?probe=4ed0a42e5c) | Jun 30, 2018 |
| ASUSTek       | K53E                        | Notebook    | [58b632622d](https://linux-hardware.org/?probe=58b632622d) | Apr 15, 2018 |
| ASUSTek       | X555LN                      | Notebook    | [9760e114b0](https://linux-hardware.org/?probe=9760e114b0) | Apr 07, 2018 |
| ASUSTek       | X555LN                      | Notebook    | [c3f232766b](https://linux-hardware.org/?probe=c3f232766b) | Apr 07, 2018 |
| ASUSTek       | K53SV                       | Notebook    | [e3e865dedf](https://linux-hardware.org/?probe=e3e865dedf) | Apr 06, 2018 |
| ASUSTek       | M4A785T-M                   | Desktop     | [0f2664d3b1](https://linux-hardware.org/?probe=0f2664d3b1) | Mar 29, 2018 |
| ASUSTek       | M4A785T-M                   | Desktop     | [1a91c5f47f](https://linux-hardware.org/?probe=1a91c5f47f) | Mar 05, 2018 |
| Intel         | D102GGC2 AAD42789-201       | Desktop     | [d52ebc3540](https://linux-hardware.org/?probe=d52ebc3540) | Jan 09, 2018 |
| Intel         | D102GGC2 AAD42789-201       | Desktop     | [16d64740e8](https://linux-hardware.org/?probe=16d64740e8) | Jan 09, 2018 |
| ASUSTek       | K53SV                       | Notebook    | [041cd61823](https://linux-hardware.org/?probe=041cd61823) | Dec 14, 2017 |
| Acer          | Aspire 5610Z                | Notebook    | [c79786fae0](https://linux-hardware.org/?probe=c79786fae0) | Dec 12, 2017 |
| ASRock        | ALiveDual-eSATA2            | Desktop     | [7330a7e461](https://linux-hardware.org/?probe=7330a7e461) | Sep 27, 2017 |
| Dell          | Inspiron 3537               | Notebook    | [0cb8d57f73](https://linux-hardware.org/?probe=0cb8d57f73) | Sep 25, 2017 |
| ASUSTek       | M50Vc                       | Notebook    | [9224093b58](https://linux-hardware.org/?probe=9224093b58) | Aug 22, 2017 |
| ASUSTek       | K53SV                       | Notebook    | [366e5e884c](https://linux-hardware.org/?probe=366e5e884c) | Jun 23, 2017 |
| Lenovo        | B50-10 80QR                 | Notebook    | [0ba3b01a3b](https://linux-hardware.org/?probe=0ba3b01a3b) | May 17, 2017 |
| ASRock        | 980DE3/U3S3 R2.0            | Desktop     | [ce9b629fa0](https://linux-hardware.org/?probe=ce9b629fa0) | Apr 21, 2017 |
| Lenovo        | B50-10 80QR                 | Notebook    | [0a9d97b358](https://linux-hardware.org/?probe=0a9d97b358) | Apr 11, 2017 |
| Dell          | Precision M4600             | Notebook    | [2a09c39637](https://linux-hardware.org/?probe=2a09c39637) | Mar 15, 2017 |
| Dell          | Precision M4600             | Notebook    | [c9a115e18c](https://linux-hardware.org/?probe=c9a115e18c) | Mar 15, 2017 |
| ASRock        | G41M-VS3                    | Desktop     | [8915ed904a](https://linux-hardware.org/?probe=8915ed904a) | Mar 14, 2017 |
| Acer          | Aspire ES1-711              | Notebook    | [0f7625ddc4](https://linux-hardware.org/?probe=0f7625ddc4) | Mar 10, 2017 |
| Acer          | Aspire ES1-711              | Notebook    | [64cea7b4eb](https://linux-hardware.org/?probe=64cea7b4eb) | Mar 10, 2017 |
| ASRock        | G41C-VS                     | Desktop     | [3688013a36](https://linux-hardware.org/?probe=3688013a36) | Dec 02, 2016 |
| ASRock        | G41C-VS                     | Desktop     | [9f9c0116cd](https://linux-hardware.org/?probe=9f9c0116cd) | Nov 30, 2016 |
| ASRock        | G41C-VS                     | Desktop     | [a1993f9fc4](https://linux-hardware.org/?probe=a1993f9fc4) | Nov 28, 2016 |
| Dell          | Precision M4600             | Notebook    | [e851921cd7](https://linux-hardware.org/?probe=e851921cd7) | Oct 24, 2016 |
| Dell          | Latitude E6440              | Notebook    | [ea1b5da2e7](https://linux-hardware.org/?probe=ea1b5da2e7) | Dec 07, 2015 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Lithuania/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 34        | 7.67%   |
| Ubuntu 18.04                 | 27        | 6.09%   |
| Ubuntu 22.04                 | 21        | 4.74%   |
| Arch Rolling                 | 19        | 4.29%   |
| Arch                         | 10        | 2.26%   |
| ROSA R11                     | 8         | 1.81%   |
| Pop!_OS 21.04                | 8         | 1.81%   |
| OpenMandriva 4.3             | 8         | 1.81%   |
| Zorin 16                     | 7         | 1.58%   |
| ROSA R8.1                    | 7         | 1.58%   |
| ROSA R10                     | 7         | 1.58%   |
| OpenMandriva 4.2             | 7         | 1.58%   |
| OpenMandriva 23.03           | 7         | 1.58%   |
| Linux Mint 21.1              | 7         | 1.58%   |
| KDE neon 20.04               | 7         | 1.58%   |
| Debian 11                    | 7         | 1.58%   |
| Ubuntu 19.10                 | 6         | 1.35%   |
| Ubuntu 19.04                 | 6         | 1.35%   |
| Pop!_OS 22.04                | 6         | 1.35%   |
| Manjaro                      | 6         | 1.35%   |
| ArcoLinux Rolling            | 6         | 1.35%   |
| Xubuntu 20.04                | 5         | 1.13%   |
| Ubuntu 21.10                 | 5         | 1.13%   |
| ROSA R9                      | 5         | 1.13%   |
| ROSA R11.1                   | 5         | 1.13%   |
| Pop!_OS 21.10                | 5         | 1.13%   |
| Pop!_OS 20.04                | 5         | 1.13%   |
| openSUSE Tumbleweed-XXXXXXXX | 5         | 1.13%   |
| OpenMandriva 23.01           | 5         | 1.13%   |
| Manjaro 20.2.1               | 5         | 1.13%   |
| Linux Mint 20                | 5         | 1.13%   |
| Fedora 38                    | 5         | 1.13%   |
| Fedora 33                    | 5         | 1.13%   |
| Debian 10                    | 5         | 1.13%   |
| Ubuntu 20.10                 | 4         | 0.9%    |
| Linux Mint 20.3              | 4         | 0.9%    |
| Linux Mint 20.1              | 4         | 0.9%    |
| Kubuntu 22.04                | 4         | 0.9%    |
| KDE neon 22.04               | 4         | 0.9%    |
| Fedora 36                    | 4         | 0.9%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 107       | 26.1%   |
| OpenMandriva | 32        | 7.8%    |
| ROSA         | 30        | 7.32%   |
| Linux Mint   | 29        | 7.07%   |
| Pop!_OS      | 26        | 6.34%   |
| Arch         | 26        | 6.34%   |
| Manjaro      | 23        | 5.61%   |
| Fedora       | 23        | 5.61%   |
| Debian       | 16        | 3.9%    |
| KDE neon     | 12        | 2.93%   |
| Zorin        | 9         | 2.2%    |
| Xubuntu      | 8         | 1.95%   |
| Kubuntu      | 8         | 1.95%   |
| openSUSE     | 6         | 1.46%   |
| Lubuntu      | 6         | 1.46%   |
| ArcoLinux    | 6         | 1.46%   |
| Gentoo       | 4         | 0.98%   |
| Endless      | 4         | 0.98%   |
| Ubuntu Unity | 3         | 0.73%   |
| RHEL         | 3         | 0.73%   |
| EndeavourOS  | 3         | 0.73%   |
| Elementary   | 3         | 0.73%   |
| CentOS       | 3         | 0.73%   |
| Ubuntu MATE  | 2         | 0.49%   |
| RED          | 2         | 0.49%   |
| Nobara       | 2         | 0.49%   |
| Garuda Linux | 2         | 0.49%   |
| Artix        | 2         | 0.49%   |
| SteamOS      | 1         | 0.24%   |
| PostmarketOS | 1         | 0.24%   |
| Peppermint   | 1         | 0.24%   |
| NixOS        | 1         | 0.24%   |
| Manjaro-ARM  | 1         | 0.24%   |
| LMDE         | 1         | 0.24%   |
| Drauger OS   | 1         | 0.24%   |
| Devuan       | 1         | 0.24%   |
| Deepin       | 1         | 0.24%   |
| Clear Linux  | 1         | 0.24%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.4.0-42-generic                | 7         | 1.46%   |
| 5.10.14-desktop-1omv4002        | 7         | 1.46%   |
| 6.2.6-desktop-1omv2390          | 6         | 1.25%   |
| 5.13.0-40-generic               | 6         | 1.25%   |
| 6.1.1-desktop-1omv2290          | 5         | 1.04%   |
| 5.4.0-48-generic                | 5         | 1.04%   |
| 5.16.7-desktop-1omv4003         | 5         | 1.04%   |
| 5.15.0-56-generic               | 5         | 1.04%   |
| 5.4.0-66-generic                | 4         | 0.83%   |
| 5.3.0-28-generic                | 4         | 0.83%   |
| 6.6.2-desktop-1omv2390          | 3         | 0.62%   |
| 6.3.5-desktop-3omv2390          | 3         | 0.62%   |
| 6.2.0-35-generic                | 3         | 0.62%   |
| 6.2.0-20-generic                | 3         | 0.62%   |
| 5.9.16-1-MANJARO                | 3         | 0.62%   |
| 5.4.0-70-generic                | 3         | 0.62%   |
| 5.4.0-47-generic                | 3         | 0.62%   |
| 5.3.0-26-generic                | 3         | 0.62%   |
| 5.3.0-23-generic                | 3         | 0.62%   |
| 5.11.0-7620-generic             | 3         | 0.62%   |
| 4.9.60-nrj-desktop-1rosa-i586   | 3         | 0.62%   |
| 4.9.41-nrj-desktop-1rosa-x86_64 | 3         | 0.62%   |
| 4.15.0-desktop-60.7rosa-i586    | 3         | 0.62%   |
| 4.15.0-91-generic               | 3         | 0.62%   |
| 6.4.8-desktop-2omv2390          | 2         | 0.42%   |
| 6.2.11-300.fc38.x86_64          | 2         | 0.42%   |
| 6.2.0-32-generic                | 2         | 0.42%   |
| 6.2.0-26-generic                | 2         | 0.42%   |
| 6.1.31-1-lts                    | 2         | 0.42%   |
| 6.1.0-10-amd64                  | 2         | 0.42%   |
| 5.8.3-zen1-1-zen                | 2         | 0.42%   |
| 5.8.12-200.fc32.x86_64          | 2         | 0.42%   |
| 5.8.0-48-generic                | 2         | 0.42%   |
| 5.8.0-44-generic                | 2         | 0.42%   |
| 5.4.0-7634-generic              | 2         | 0.42%   |
| 5.4.0-73-generic                | 2         | 0.42%   |
| 5.4.0-52-generic                | 2         | 0.42%   |
| 5.4.0-31-generic                | 2         | 0.42%   |
| 5.4.0-26-generic                | 2         | 0.42%   |
| 5.3.0-46-generic                | 2         | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 51        | 11.18%  |
| 5.15.0  | 32        | 7.02%   |
| 4.15.0  | 28        | 6.14%   |
| 5.3.0   | 22        | 4.82%   |
| 5.13.0  | 19        | 4.17%   |
| 5.8.0   | 15        | 3.29%   |
| 5.11.0  | 13        | 2.85%   |
| 5.19.0  | 12        | 2.63%   |
| 5.0.0   | 12        | 2.63%   |
| 6.2.0   | 11        | 2.41%   |
| 6.2.6   | 8         | 1.75%   |
| 5.16.7  | 7         | 1.54%   |
| 5.10.14 | 7         | 1.54%   |
| 5.10.0  | 7         | 1.54%   |
| 4.18.0  | 7         | 1.54%   |
| 6.1.0   | 6         | 1.32%   |
| 6.1.1   | 5         | 1.1%    |
| 6.6.2   | 4         | 0.88%   |
| 6.3.5   | 4         | 0.88%   |
| 4.9.60  | 4         | 0.88%   |
| 4.19.0  | 4         | 0.88%   |
| 5.9.16  | 3         | 0.66%   |
| 4.9.9   | 3         | 0.66%   |
| 4.9.41  | 3         | 0.66%   |
| 4.9.20  | 3         | 0.66%   |
| 6.4.8   | 2         | 0.44%   |
| 6.2.7   | 2         | 0.44%   |
| 6.2.11  | 2         | 0.44%   |
| 6.1.31  | 2         | 0.44%   |
| 6.1.11  | 2         | 0.44%   |
| 6.0.6   | 2         | 0.44%   |
| 6.0.0   | 2         | 0.44%   |
| 5.9.13  | 2         | 0.44%   |
| 5.8.3   | 2         | 0.44%   |
| 5.8.18  | 2         | 0.44%   |
| 5.8.12  | 2         | 0.44%   |
| 5.8.11  | 2         | 0.44%   |
| 5.7.17  | 2         | 0.44%   |
| 5.4.70  | 2         | 0.44%   |
| 5.4.32  | 2         | 0.44%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 61        | 13.56%  |
| 5.15    | 47        | 10.44%  |
| 5.10    | 29        | 6.44%   |
| 4.15    | 28        | 6.22%   |
| 6.2     | 27        | 6%      |
| 5.8     | 24        | 5.33%   |
| 6.1     | 23        | 5.11%   |
| 5.13    | 23        | 5.11%   |
| 5.3     | 22        | 4.89%   |
| 4.9     | 18        | 4%      |
| 5.19    | 16        | 3.56%   |
| 5.16    | 16        | 3.56%   |
| 5.11    | 16        | 3.56%   |
| 5.0     | 13        | 2.89%   |
| 6.4     | 8         | 1.78%   |
| 6.6     | 7         | 1.56%   |
| 6.3     | 7         | 1.56%   |
| 5.12    | 7         | 1.56%   |
| 4.18    | 7         | 1.56%   |
| 6.0     | 6         | 1.33%   |
| 5.9     | 6         | 1.33%   |
| 5.18    | 5         | 1.11%   |
| 4.19    | 5         | 1.11%   |
| 5.7     | 4         | 0.89%   |
| 5.17    | 4         | 0.89%   |
| 5.14    | 4         | 0.89%   |
| 4.14    | 4         | 0.89%   |
| 5.6     | 3         | 0.67%   |
| 4.4     | 3         | 0.67%   |
| 4.1     | 3         | 0.67%   |
| 6.5     | 2         | 0.44%   |
| 5.5     | 1         | 0.22%   |
| 3.16    | 1         | 0.22%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 370       | 94.87%  |
| i686    | 17        | 4.36%   |
| aarch64 | 2         | 0.51%   |
| armv7l  | 1         | 0.26%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 154       | 37.02%  |
| KDE5            | 82        | 19.71%  |
| Unknown         | 44        | 10.58%  |
| XFCE            | 34        | 8.17%   |
| X-Cinnamon      | 25        | 6.01%   |
| KDE4            | 24        | 5.77%   |
| KDE             | 13        | 3.13%   |
| LXQt            | 8         | 1.92%   |
| MATE            | 6         | 1.44%   |
| Cinnamon        | 5         | 1.2%    |
| Unity           | 4         | 0.96%   |
| Pantheon        | 3         | 0.72%   |
| GNOME Flashback | 2         | 0.48%   |
| Enlightenment   | 2         | 0.48%   |
| dwm             | 2         | 0.48%   |
| Deepin          | 2         | 0.48%   |
| awesome         | 2         | 0.48%   |
| qtile           | 1         | 0.24%   |
| LXDE            | 1         | 0.24%   |
| i3              | 1         | 0.24%   |
| Budgie          | 1         | 0.24%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 306       | 74.63%  |
| Wayland | 73        | 17.8%   |
| Unknown | 16        | 3.9%    |
| Tty     | 15        | 3.66%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 181       | 44.15%  |
| SDDM    | 72        | 17.56%  |
| GDM     | 49        | 11.95%  |
| LightDM | 37        | 9.02%   |
| GDM3    | 32        | 7.8%    |
| KDM     | 23        | 5.61%   |
| TDM     | 14        | 3.41%   |
| XDM     | 1         | 0.24%   |
| Ly      | 1         | 0.24%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 242       | 60.5%   |
| Unknown | 55        | 13.75%  |
| lt_LT   | 54        | 13.5%   |
| en_GB   | 20        | 5%      |
| ru_RU   | 17        | 4.25%   |
| C       | 6         | 1.5%    |
| en_AU   | 2         | 0.5%    |
| uk_UA   | 1         | 0.25%   |
| nl_NL   | 1         | 0.25%   |
| en_DK   | 1         | 0.25%   |
| de_DE   | 1         | 0.25%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 212       | 53.27%  |
| EFI  | 186       | 46.73%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 286       | 71.14%  |
| Btrfs   | 39        | 9.7%    |
| Overlay | 30        | 7.46%   |
| Unknown | 23        | 5.72%   |
| Tmpfs   | 11        | 2.74%   |
| Xfs     | 9         | 2.24%   |
| Zfs     | 2         | 0.5%    |
| SAMSUNG | 1         | 0.25%   |
| ExX4    | 1         | 0.25%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 189       | 46.55%  |
| GPT     | 159       | 39.16%  |
| MBR     | 58        | 14.29%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 340       | 86.08%  |
| Yes       | 55        | 13.92%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 297       | 74.44%  |
| Yes       | 102       | 25.56%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 83        | 21.45%  |
| Lenovo                  | 78        | 20.16%  |
| Hewlett-Packard         | 48        | 12.4%   |
| Dell                    | 40        | 10.34%  |
| MSI                     | 28        | 7.24%   |
| ASRock                  | 25        | 6.46%   |
| Gigabyte Technology     | 23        | 5.94%   |
| Acer                    | 17        | 4.39%   |
| Intel                   | 7         | 1.81%   |
| Samsung Electronics     | 4         | 1.03%   |
| Apple                   | 4         | 1.03%   |
| Fujitsu Siemens         | 3         | 0.78%   |
| Unknown                 | 3         | 0.78%   |
| Toshiba                 | 2         | 0.52%   |
| Sony                    | 2         | 0.52%   |
| Panasonic               | 2         | 0.52%   |
| HUAWEI                  | 2         | 0.52%   |
| Fujitsu                 | 2         | 0.52%   |
| Valve                   | 1         | 0.26%   |
| Timi                    | 1         | 0.26%   |
| Raspberry Pi Foundation | 1         | 0.26%   |
| Prestigio               | 1         | 0.26%   |
| Packard Bell            | 1         | 0.26%   |
| Notebook                | 1         | 0.26%   |
| Microsoft               | 1         | 0.26%   |
| LIVEFAN                 | 1         | 0.26%   |
| Jumper                  | 1         | 0.26%   |
| Hardkernel              | 1         | 0.26%   |
| eMachines               | 1         | 0.26%   |
| BESSTAR Tech            | 1         | 0.26%   |
| AMI                     | 1         | 0.26%   |
| Alienware               | 1         | 0.26%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Unknown                                               | 4         | 1.03%   |
| MSI MS-7A38                                           | 3         | 0.78%   |
| MSI MS-7817                                           | 3         | 0.78%   |
| ASUS All Series                                       | 3         | 0.78%   |
| MSI MS-7C82                                           | 2         | 0.52%   |
| MSI MS-7A34                                           | 2         | 0.52%   |
| MSI MS-7823                                           | 2         | 0.52%   |
| Lenovo ThinkPad T490 20N3000KMH                       | 2         | 0.52%   |
| Lenovo S40-40 F0AX00EAPB                              | 2         | 0.52%   |
| Lenovo Legion Y530-15ICH 81FV                         | 2         | 0.52%   |
| Lenovo IdeaPad Y700-15ISK 80NV                        | 2         | 0.52%   |
| Lenovo G550 20023                                     | 2         | 0.52%   |
| HP EliteBook 8460p                                    | 2         | 0.52%   |
| Dell Inspiron 7720                                    | 2         | 0.52%   |
| ASUS TUF Gaming X570-PLUS                             | 2         | 0.52%   |
| ASUS TUF Gaming B550-PLUS                             | 2         | 0.52%   |
| ASUS PRIME Z390-A                                     | 2         | 0.52%   |
| ASUS PRIME B450M-K                                    | 2         | 0.52%   |
| ASUS PRIME B450M-A                                    | 2         | 0.52%   |
| ASUS K53E                                             | 2         | 0.52%   |
| ASRock B450 Pro4                                      | 2         | 0.52%   |
| Acer Aspire ES1-711                                   | 2         | 0.52%   |
| Acer Aspire 5750G                                     | 2         | 0.52%   |
| Valve Jupiter                                         | 1         | 0.26%   |
| Toshiba Satellite L855                                | 1         | 0.26%   |
| Toshiba Satellite C50D-A-13G                          | 1         | 0.26%   |
| Timi TM1701                                           | 1         | 0.26%   |
| Sony VPCZ1390S                                        | 1         | 0.26%   |
| Sony VGN-C260E                                        | 1         | 0.26%   |
| Samsung RC530/RC730                                   | 1         | 0.26%   |
| Samsung R530/R730/P530                                | 1         | 0.26%   |
| Samsung 530U3C/530U4C/532U3C                          | 1         | 0.26%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.26%   |
| RPi Raspberry Pi 4 Model B Rev 1.1                    | 1         | 0.26%   |
| Prestigio PSB141C02                                   | 1         | 0.26%   |
| Panasonic CF-52WEBBYDE                                | 1         | 0.26%   |
| Panasonic CF-52VDA131M                                | 1         | 0.26%   |
| Packard Bell EasyNote TE11HC                          | 1         | 0.26%   |
| Notebook L140CU                                       | 1         | 0.26%   |
| MSI MS-7D91                                           | 1         | 0.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 44        | 11.37%  |
| Dell Inspiron     | 13        | 3.36%   |
| ASUS PRIME        | 13        | 3.36%   |
| HP ProBook        | 11        | 2.84%   |
| Acer Aspire       | 11        | 2.84%   |
| Lenovo IdeaPad    | 10        | 2.58%   |
| HP EliteBook      | 10        | 2.58%   |
| HP Compaq         | 9         | 2.33%   |
| Dell Latitude     | 8         | 2.07%   |
| ASUS TUF          | 7         | 1.81%   |
| ASUS VivoBook     | 6         | 1.55%   |
| Lenovo Legion     | 5         | 1.29%   |
| Dell Vostro       | 5         | 1.29%   |
| Lenovo Yoga       | 4         | 1.03%   |
| Dell XPS          | 4         | 1.03%   |
| Dell OptiPlex     | 4         | 1.03%   |
| ASUS ROG          | 4         | 1.03%   |
| Unknown           | 4         | 1.03%   |
| MSI MS-7A38       | 3         | 0.78%   |
| MSI MS-7817       | 3         | 0.78%   |
| HP Laptop         | 3         | 0.78%   |
| HP EliteDesk      | 3         | 0.78%   |
| Gigabyte X570     | 3         | 0.78%   |
| ASUS ASUS         | 3         | 0.78%   |
| ASUS All          | 3         | 0.78%   |
| ASRock B450       | 3         | 0.78%   |
| Toshiba Satellite | 2         | 0.52%   |
| MSI MS-7C82       | 2         | 0.52%   |
| MSI MS-7A34       | 2         | 0.52%   |
| MSI MS-7823       | 2         | 0.52%   |
| Lenovo S40-40     | 2         | 0.52%   |
| Lenovo G550       | 2         | 0.52%   |
| HP Pavilion       | 2         | 0.52%   |
| HP ENVY           | 2         | 0.52%   |
| HP 250            | 2         | 0.52%   |
| Dell Precision    | 2         | 0.52%   |
| Dell G5           | 2         | 0.52%   |
| ASUS ZenBook      | 2         | 0.52%   |
| ASUS K53E         | 2         | 0.52%   |
| ASRock B550M      | 2         | 0.52%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 42        | 10.85%  |
| 2020    | 32        | 8.27%   |
| 2011    | 32        | 8.27%   |
| 2021    | 29        | 7.49%   |
| 2014    | 27        | 6.98%   |
| 2013    | 27        | 6.98%   |
| 2012    | 27        | 6.98%   |
| 2019    | 26        | 6.72%   |
| 2017    | 23        | 5.94%   |
| 2015    | 22        | 5.68%   |
| 2010    | 19        | 4.91%   |
| 2009    | 18        | 4.65%   |
| 2016    | 16        | 4.13%   |
| 2022    | 12        | 3.1%    |
| 2008    | 12        | 3.1%    |
| 2007    | 9         | 2.33%   |
| 2006    | 8         | 2.07%   |
| 2023    | 2         | 0.52%   |
| 2004    | 2         | 0.52%   |
| 2005    | 1         | 0.26%   |
| Unknown | 1         | 0.26%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 232       | 59.95%  |
| Desktop        | 134       | 34.63%  |
| All in one     | 7         | 1.81%   |
| Tablet         | 4         | 1.03%   |
| Convertible    | 3         | 0.78%   |
| Mini pc        | 3         | 0.78%   |
| System on chip | 2         | 0.52%   |
| Server         | 2         | 0.52%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 366       | 93.85%  |
| Enabled  | 24        | 6.15%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 387       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 95        | 24.11%  |
| 3.01-4.0    | 80        | 20.3%   |
| 4.01-8.0    | 77        | 19.54%  |
| 8.01-16.0   | 69        | 17.51%  |
| 32.01-64.0  | 34        | 8.63%   |
| 1.01-2.0    | 16        | 4.06%   |
| 2.01-3.0    | 8         | 2.03%   |
| 64.01-256.0 | 8         | 2.03%   |
| 24.01-32.0  | 4         | 1.02%   |
| 0.51-1.0    | 3         | 0.76%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 136       | 30.36%  |
| 2.01-3.0   | 109       | 24.33%  |
| 4.01-8.0   | 78        | 17.41%  |
| 3.01-4.0   | 56        | 12.5%   |
| 0.51-1.0   | 35        | 7.81%   |
| 8.01-16.0  | 23        | 5.13%   |
| 0.01-0.5   | 5         | 1.12%   |
| 16.01-24.0 | 3         | 0.67%   |
| 24.01-32.0 | 2         | 0.45%   |
| 32.01-64.0 | 1         | 0.22%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 245       | 60.95%  |
| 2       | 105       | 26.12%  |
| 3       | 35        | 8.71%   |
| 4       | 8         | 1.99%   |
| 5       | 6         | 1.49%   |
| 6       | 1         | 0.25%   |
| 0       | 1         | 0.25%   |
| Unknown | 1         | 0.25%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 254       | 64.3%   |
| Yes       | 141       | 35.7%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 342       | 88.14%  |
| No        | 46        | 11.86%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 287       | 73.59%  |
| No        | 103       | 26.41%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 225       | 57.25%  |
| No        | 168       | 42.75%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Computers | Percent |
|-----------|-----------|---------|
| Lithuania | 387       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Computers | Percent |
|--------------|-----------|---------|
| Vilnius      | 204       | 50.5%   |
| Kaunas       | 62        | 15.35%  |
| Klaipėda    | 30        | 7.43%   |
| Šiauliai    | 24        | 5.94%   |
| Mažeikiai   | 9         | 2.23%   |
| Alytus       | 8         | 1.98%   |
| Panevezys    | 6         | 1.49%   |
| Kėdainiai   | 4         | 0.99%   |
| Gargždai    | 4         | 0.99%   |
| Trakai       | 3         | 0.74%   |
| Telšiai     | 3         | 0.74%   |
| Tauragė     | 3         | 0.74%   |
| Šilalė     | 3         | 0.74%   |
| Jonava       | 3         | 0.74%   |
| Visaginas    | 2         | 0.5%    |
| Utena        | 2         | 0.5%    |
| Ukmerge      | 2         | 0.5%    |
| Palanga      | 2         | 0.5%    |
| Marijampolė | 2         | 0.5%    |
| Elektrėnai  | 2         | 0.5%    |
| Anykščiai  | 2         | 0.5%    |
| Agluonenai   | 2         | 0.5%    |
| Želva       | 1         | 0.25%   |
| Vėžaičiai | 1         | 0.25%   |
| Vainutas     | 1         | 0.25%   |
| Širvintos   | 1         | 0.25%   |
| Serdokai     | 1         | 0.25%   |
| Šeduva      | 1         | 0.25%   |
| Rokiškis    | 1         | 0.25%   |
| Rietavas     | 1         | 0.25%   |
| Raseiniai    | 1         | 0.25%   |
| Plungė      | 1         | 0.25%   |
| Pasvalys     | 1         | 0.25%   |
| Nemenčinė  | 1         | 0.25%   |
| Molėtai     | 1         | 0.25%   |
| Mauruciai    | 1         | 0.25%   |
| Maneikiai    | 1         | 0.25%   |
| Lentvaris    | 1         | 0.25%   |
| Karkliniai   | 1         | 0.25%   |
| Joniškėlis | 1         | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 97        | 160    | 17.2%   |
| WDC                         | 72        | 99     | 12.77%  |
| Seagate                     | 63        | 84     | 11.17%  |
| Toshiba                     | 45        | 62     | 7.98%   |
| Kingston                    | 42        | 58     | 7.45%   |
| A-DATA Technology           | 33        | 38     | 5.85%   |
| SanDisk                     | 21        | 24     | 3.72%   |
| Crucial                     | 20        | 23     | 3.55%   |
| Hitachi                     | 19        | 26     | 3.37%   |
| Intel                       | 17        | 20     | 3.01%   |
| Unknown                     | 16        | 33     | 2.84%   |
| Patriot                     | 14        | 15     | 2.48%   |
| SK hynix                    | 10        | 10     | 1.77%   |
| HGST                        | 9         | 11     | 1.6%    |
| Micron Technology           | 8         | 9      | 1.42%   |
| SPCC                        | 5         | 5      | 0.89%   |
| China                       | 5         | 7      | 0.89%   |
| KIOXIA                      | 4         | 4      | 0.71%   |
| Apacer                      | 4         | 6      | 0.71%   |
| MAXIO Technology (Hangzhou) | 3         | 4      | 0.53%   |
| GOODRAM                     | 3         | 3      | 0.53%   |
| XPG                         | 2         | 2      | 0.35%   |
| Transcend                   | 2         | 2      | 0.35%   |
| PNY                         | 2         | 2      | 0.35%   |
| Plextor                     | 2         | 2      | 0.35%   |
| OCZ                         | 2         | 3      | 0.35%   |
| Micron/Crucial Technology   | 2         | 2      | 0.35%   |
| Lite-On Technology          | 2         | 2      | 0.35%   |
| KingSpec                    | 2         | 2      | 0.35%   |
| KingDian                    | 2         | 2      | 0.35%   |
| JMicron Technology          | 2         | 2      | 0.35%   |
| Intenso                     | 2         | 3      | 0.35%   |
| Hewlett-Packard             | 2         | 5      | 0.35%   |
| Gigabyte Technology         | 2         | 2      | 0.35%   |
| FORESEE                     | 2         | 2      | 0.35%   |
| Dahua                       | 2         | 3      | 0.35%   |
| Corsair                     | 2         | 2      | 0.35%   |
| ASMT                        | 2         | 2      | 0.35%   |
| Apple                       | 2         | 3      | 0.35%   |
| ADATA Technology            | 2         | 3      | 0.35%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 7         | 1.15%   |
| Kingston SV300S37A120G 120GB SSD                    | 7         | 1.15%   |
| Kingston SA400S37240G 240GB SSD                     | 7         | 1.15%   |
| Seagate ST500DM002-1BD142 500GB                     | 6         | 0.99%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 6         | 0.99%   |
| Samsung SSD 850 EVO 250GB                           | 6         | 0.99%   |
| Kingston SA400S37480G 480GB SSD                     | 6         | 0.99%   |
| Kingston SA400S37120G 120GB SSD                     | 6         | 0.99%   |
| A-DATA SU650 120GB SSD                              | 6         | 0.99%   |
| Seagate ST500LT012-1DG142 500GB                     | 5         | 0.82%   |
| SanDisk NVMe SSD Drive 256GB                        | 5         | 0.82%   |
| Samsung SSD 860 EVO 250GB                           | 5         | 0.82%   |
| Intel NVMe SSD Drive 512GB                          | 5         | 0.82%   |
| WDC WD20EFRX-68EUZN0 2TB                            | 4         | 0.66%   |
| Unknown MMC Card  64GB                              | 4         | 0.66%   |
| Toshiba MQ01ABF050 500GB                            | 4         | 0.66%   |
| Toshiba MQ01ABD100 1TB                              | 4         | 0.66%   |
| Seagate ST9500325AS 500GB                           | 4         | 0.66%   |
| Samsung SSD 860 EVO 500GB                           | 4         | 0.66%   |
| Samsung SSD 860 EVO 1TB                             | 4         | 0.66%   |
| Samsung SSD 850 EVO 500GB                           | 4         | 0.66%   |
| Patriot Burst 480GB SSD                             | 4         | 0.66%   |
| Unknown MMC Card  128GB                             | 3         | 0.49%   |
| Toshiba DT01ACA100 1TB                              | 3         | 0.49%   |
| Toshiba BG3 NVMe SSD Controller 128GB               | 3         | 0.49%   |
| Seagate ST1000LM035-1RK172 1TB                      | 3         | 0.49%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB              | 3         | 0.49%   |
| Samsung NVMe SSD Drive 500GB                        | 3         | 0.49%   |
| Samsung NVMe SSD Drive 1TB                          | 3         | 0.49%   |
| Samsung HD501LJ 500GB                               | 3         | 0.49%   |
| Patriot Burst 120GB SSD                             | 3         | 0.49%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 1024GB | 3         | 0.49%   |
| Kingston SUV400S37240G 240GB SSD                    | 3         | 0.49%   |
| HGST HTS541010A9E680 1TB                            | 3         | 0.49%   |
| GOODRAM SSD 120GB                                   | 3         | 0.49%   |
| Crucial CT500MX500SSD1 500GB                        | 3         | 0.49%   |
| Crucial CT1000MX500SSD1 1TB                         | 3         | 0.49%   |
| A-DATA SX900 128GB SSD                              | 3         | 0.49%   |
| A-DATA SU650 240GB SSD                              | 3         | 0.49%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 2         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 63        | 84     | 32.47%  |
| WDC                 | 58        | 82     | 29.9%   |
| Toshiba             | 28        | 38     | 14.43%  |
| Hitachi             | 19        | 26     | 9.79%   |
| Samsung Electronics | 12        | 29     | 6.19%   |
| HGST                | 9         | 11     | 4.64%   |
| Unknown             | 1         | 1      | 0.52%   |
| StoreJet            | 1         | 1      | 0.52%   |
| Fujitsu             | 1         | 1      | 0.52%   |
| ExcelStor           | 1         | 1      | 0.52%   |
| Apple               | 1         | 2      | 0.52%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 48        | 73     | 21.43%  |
| Kingston            | 37        | 52     | 16.52%  |
| A-DATA Technology   | 27        | 32     | 12.05%  |
| Crucial             | 18        | 20     | 8.04%   |
| Patriot             | 14        | 15     | 6.25%   |
| SanDisk             | 7         | 8      | 3.13%   |
| WDC                 | 6         | 9      | 2.68%   |
| Toshiba             | 5         | 7      | 2.23%   |
| SPCC                | 5         | 5      | 2.23%   |
| Intel               | 5         | 5      | 2.23%   |
| China               | 5         | 7      | 2.23%   |
| SK hynix            | 4         | 4      | 1.79%   |
| Apacer              | 4         | 6      | 1.79%   |
| GOODRAM             | 3         | 3      | 1.34%   |
| Transcend           | 2         | 2      | 0.89%   |
| PNY                 | 2         | 2      | 0.89%   |
| Plextor             | 2         | 2      | 0.89%   |
| OCZ                 | 2         | 3      | 0.89%   |
| Micron Technology   | 2         | 2      | 0.89%   |
| KingSpec            | 2         | 2      | 0.89%   |
| Intenso             | 2         | 3      | 0.89%   |
| Hewlett-Packard     | 2         | 5      | 0.89%   |
| Gigabyte Technology | 2         | 2      | 0.89%   |
| FORESEE             | 2         | 2      | 0.89%   |
| Dahua               | 2         | 3      | 0.89%   |
| ASMT                | 2         | 2      | 0.89%   |
| XrayDisk            | 1         | 1      | 0.45%   |
| Unknown             | 1         | 1      | 0.45%   |
| Team                | 1         | 1      | 0.45%   |
| Netac               | 1         | 1      | 0.45%   |
| LITEONIT            | 1         | 1      | 0.45%   |
| LITEON              | 1         | 2      | 0.45%   |
| Leven               | 1         | 3      | 0.45%   |
| KingDian            | 1         | 1      | 0.45%   |
| JMicron Technology  | 1         | 1      | 0.45%   |
| Corsair             | 1         | 1      | 0.45%   |
| Colorful            | 1         | 1      | 0.45%   |
| Apple               | 1         | 1      | 0.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 197       | 291    | 38.1%   |
| HDD     | 175       | 276    | 33.85%  |
| NVMe    | 128       | 165    | 24.76%  |
| MMC     | 14        | 32     | 2.71%   |
| Unknown | 3         | 3      | 0.58%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 287       | 548    | 64.06%  |
| NVMe | 127       | 164    | 28.35%  |
| SAS  | 20        | 23     | 4.46%   |
| MMC  | 14        | 32     | 3.13%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 244       | 410    | 67.59%  |
| 0.51-1.0   | 90        | 122    | 24.93%  |
| 1.01-2.0   | 19        | 25     | 5.26%   |
| 3.01-4.0   | 4         | 5      | 1.11%   |
| 2.01-3.0   | 2         | 3      | 0.55%   |
| 4.01-10.0  | 2         | 2      | 0.55%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 124       | 29.04%  |
| 251-500        | 104       | 24.36%  |
| 501-1000       | 52        | 12.18%  |
| 1-20           | 31        | 7.26%   |
| 1001-2000      | 29        | 6.79%   |
| 51-100         | 29        | 6.79%   |
| 21-50          | 21        | 4.92%   |
| Unknown        | 14        | 3.28%   |
| 2001-3000      | 12        | 2.81%   |
| More than 3000 | 11        | 2.58%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 176       | 40%     |
| 101-250        | 60        | 13.64%  |
| 21-50          | 57        | 12.95%  |
| 51-100         | 54        | 12.27%  |
| 251-500        | 40        | 9.09%   |
| 1001-2000      | 16        | 3.64%   |
| 501-1000       | 16        | 3.64%   |
| Unknown        | 14        | 3.18%   |
| More than 3000 | 6         | 1.36%   |
| 2001-3000      | 1         | 0.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD800AAJS-60PSA0 80GB                           | 2         | 2      | 4.17%   |
| WDC WD20EFRX-68EUZN0 2TB                            | 2         | 5      | 4.17%   |
| Toshiba MK3261GSYN 320GB                            | 2         | 2      | 4.17%   |
| WDC WD7500BPVX-60JC3T0 752GB                        | 1         | 1      | 2.08%   |
| WDC WD6400BPVT-80HXZT1 640GB                        | 1         | 1      | 2.08%   |
| WDC WD6400BPVT-22HXZT1 640GB                        | 1         | 2      | 2.08%   |
| WDC WD5000AAKX-001CA0 500GB                         | 1         | 1      | 2.08%   |
| WDC WD3200BPVT-75ZEST0 320GB                        | 1         | 1      | 2.08%   |
| WDC WD1003FBYX-01Y7B0 1TB                           | 1         | 2      | 2.08%   |
| Toshiba MQ01ABD100 1TB                              | 1         | 1      | 2.08%   |
| Toshiba MQ01ABD050 500GB                            | 1         | 2      | 2.08%   |
| Toshiba MK5059GSXP 500GB                            | 1         | 1      | 2.08%   |
| Toshiba MK1652GSX 160GB                             | 1         | 2      | 2.08%   |
| SK hynix HFS256G39TND-N210A 256GB SSD               | 1         | 1      | 2.08%   |
| SK hynix HFS128G3BTND-N210A 128GB SSD               | 1         | 1      | 2.08%   |
| SK hynix BC711 HFM512GD3JX013N 512GB                | 1         | 1      | 2.08%   |
| Seagate ST9640320AS 640GB                           | 1         | 2      | 2.08%   |
| Seagate ST9500325AS 500GB                           | 1         | 1      | 2.08%   |
| Seagate ST500LX012-SSHD-8GB                         | 1         | 1      | 2.08%   |
| Seagate ST3250410AS 250GB                           | 1         | 1      | 2.08%   |
| Seagate ST3250318AS 250GB                           | 1         | 1      | 2.08%   |
| Seagate ST2000VX000-1CU164 2TB                      | 1         | 1      | 2.08%   |
| Samsung Electronics SSD 850 EVO 250GB               | 1         | 1      | 2.08%   |
| Samsung Electronics SSD 840 Series 500GB            | 1         | 3      | 2.08%   |
| Samsung Electronics HM641JI 640GB                   | 1         | 2      | 2.08%   |
| Samsung Electronics HD501LJ 500GB                   | 1         | 1      | 2.08%   |
| Samsung Electronics HD103SJ 1TB                     | 1         | 1      | 2.08%   |
| Samsung Electronics HD080HJ 80GB                    | 1         | 4      | 2.08%   |
| Plextor PX-128M6M 128GB SSD                         | 1         | 1      | 2.08%   |
| Micron Technology MTFDDAK512TBN-1AR15ABHA 512GB SSD | 1         | 1      | 2.08%   |
| Leven JAJS300M240C 240GB                            | 1         | 3      | 2.08%   |
| Kingston SV300S37A120G 120GB SSD                    | 1         | 1      | 2.08%   |
| Hitachi HTS547575A9E384 752GB                       | 1         | 1      | 2.08%   |
| Hitachi HTS545050KTA300 500GB                       | 1         | 1      | 2.08%   |
| Hitachi HTS545032B9A300 320GB                       | 1         | 1      | 2.08%   |
| Hitachi HTS545025B9A300 250GB                       | 1         | 1      | 2.08%   |
| Hitachi HTS543232A7A384 320GB                       | 1         | 1      | 2.08%   |
| HGST HTS725050A7E630 500GB                          | 1         | 1      | 2.08%   |
| HGST HTS541010A9E680 1TB                            | 1         | 2      | 2.08%   |
| ExcelStor Technology J8160S 164GB                   | 1         | 1      | 2.08%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 10        | 15     | 21.28%  |
| Seagate             | 6         | 7      | 12.77%  |
| Samsung Electronics | 6         | 12     | 12.77%  |
| Toshiba             | 5         | 8      | 10.64%  |
| Hitachi             | 5         | 5      | 10.64%  |
| SK hynix            | 3         | 3      | 6.38%   |
| A-DATA Technology   | 3         | 4      | 6.38%   |
| HGST                | 2         | 3      | 4.26%   |
| Plextor             | 1         | 1      | 2.13%   |
| Micron Technology   | 1         | 1      | 2.13%   |
| Leven               | 1         | 3      | 2.13%   |
| Kingston            | 1         | 1      | 2.13%   |
| ExcelStor           | 1         | 1      | 2.13%   |
| Crucial             | 1         | 1      | 2.13%   |
| Colorful            | 1         | 1      | 2.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 10        | 15     | 30.3%   |
| Seagate             | 6         | 7      | 18.18%  |
| Toshiba             | 5         | 8      | 15.15%  |
| Hitachi             | 5         | 5      | 15.15%  |
| Samsung Electronics | 4         | 8      | 12.12%  |
| HGST                | 2         | 3      | 6.06%   |
| ExcelStor           | 1         | 1      | 3.03%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 29        | 47     | 67.44%  |
| SSD  | 13        | 18     | 30.23%  |
| NVMe | 1         | 1      | 2.33%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                       | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate ST3160812A 160GB    | 1         | 2      | 50%     |
| Hitachi HTS541010A9E680 1TB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 2      | 50%     |
| Hitachi | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 222       | 424    | 52.73%  |
| Works    | 158       | 274    | 37.53%  |
| Malfunc  | 39        | 66     | 9.26%   |
| Failed   | 2         | 3      | 0.48%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 259       | 54.41%  |
| AMD                              | 74        | 15.55%  |
| Samsung Electronics              | 43        | 9.03%   |
| SanDisk                          | 18        | 3.78%   |
| Toshiba America Info Systems     | 12        | 2.52%   |
| ASMedia Technology               | 9         | 1.89%   |
| ADATA Technology                 | 8         | 1.68%   |
| SK hynix                         | 6         | 1.26%   |
| Micron Technology                | 6         | 1.26%   |
| Kingston Technology Company      | 5         | 1.05%   |
| Nvidia                           | 4         | 0.84%   |
| Micron/Crucial Technology        | 4         | 0.84%   |
| MAXIO Technology (Hangzhou)      | 4         | 0.84%   |
| KIOXIA                           | 4         | 0.84%   |
| JMicron Technology               | 4         | 0.84%   |
| Phison Electronics               | 3         | 0.63%   |
| Marvell Technology Group         | 3         | 0.63%   |
| Union Memory (Shenzhen)          | 2         | 0.42%   |
| Realtek Semiconductor            | 2         | 0.42%   |
| Lite-On Technology               | 2         | 0.42%   |
| Solidigm                         | 1         | 0.21%   |
| Silicon Integrated Systems [SiS] | 1         | 0.21%   |
| OCZ Technology Group             | 1         | 0.21%   |
| Broadcom / LSI                   | 1         | 0.21%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 45        | 8.02%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 29        | 5.17%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 24        | 4.28%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 22        | 3.92%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 17        | 3.03%   |
| AMD 400 Series Chipset SATA Controller                                         | 15        | 2.67%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 13        | 2.32%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 12        | 2.14%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 12        | 2.14%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 10        | 1.78%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 10        | 1.78%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 9         | 1.6%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 8         | 1.43%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 8         | 1.43%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 8         | 1.43%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 8         | 1.43%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 7         | 1.25%   |
| Intel Volume Management Device NVMe RAID Controller                            | 7         | 1.25%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 7         | 1.25%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 7         | 1.25%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 7         | 1.25%   |
| AMD 500 Series Chipset SATA Controller                                         | 7         | 1.25%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 6         | 1.07%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 6         | 1.07%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 5         | 0.89%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)            | 5         | 0.89%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 5         | 0.89%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 5         | 0.89%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 5         | 0.89%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 5         | 0.89%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 5         | 0.89%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 5         | 0.89%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 5         | 0.89%   |
| AMD 300 Series Chipset SATA Controller                                         | 5         | 0.89%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 4         | 0.71%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 4         | 0.71%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 0.71%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                   | 4         | 0.71%   |
| Intel SSD 660P Series                                                          | 4         | 0.71%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4         | 0.71%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 270       | 56.25%  |
| NVMe | 127       | 26.46%  |
| IDE  | 54        | 11.25%  |
| RAID | 27        | 5.63%   |
| SAS  | 2         | 0.42%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 288       | 74.42%  |
| AMD    | 96        | 24.81%  |
| ARM    | 3         | 0.78%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz           | 6         | 1.55%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 6         | 1.55%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 4         | 1.03%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 4         | 1.03%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz          | 4         | 1.03%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 4         | 1.03%   |
| Intel Core i5-8300H CPU @ 2.30GHz           | 4         | 1.03%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 4         | 1.03%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 4         | 1.03%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 4         | 1.03%   |
| AMD Ryzen 7 5800H with Radeon Graphics      | 4         | 1.03%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz          | 3         | 0.77%   |
| Intel Core i7-3610QM CPU @ 2.30GHz          | 3         | 0.77%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 3         | 0.77%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 3         | 0.77%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 3         | 0.77%   |
| Intel Core i5-2540M CPU @ 2.60GHz           | 3         | 0.77%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 3         | 0.77%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 3         | 0.77%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 3         | 0.77%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 3         | 0.77%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 3         | 0.77%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 3         | 0.77%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 3         | 0.77%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 3         | 0.77%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 3         | 0.77%   |
| AMD FX-8350 Eight-Core Processor            | 3         | 0.77%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 2         | 0.52%   |
| Intel Pentium CPU G3250 @ 3.20GHz           | 2         | 0.52%   |
| Intel Pentium 4 CPU 3.00GHz                 | 2         | 0.52%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 2         | 0.52%   |
| Intel Core i7-9850H CPU @ 2.60GHz           | 2         | 0.52%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 2         | 0.52%   |
| Intel Core i7-4500U CPU @ 1.80GHz           | 2         | 0.52%   |
| Intel Core i7-3740QM CPU @ 2.70GHz          | 2         | 0.52%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 2         | 0.52%   |
| Intel Core i7-2630QM CPU @ 2.00GHz          | 2         | 0.52%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz           | 2         | 0.52%   |
| Intel Core i7 CPU M 640 @ 2.80GHz           | 2         | 0.52%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 2         | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 78        | 20.16%  |
| Intel Core i7           | 69        | 17.83%  |
| Intel Core i3           | 42        | 10.85%  |
| AMD Ryzen 5             | 35        | 9.04%   |
| Other                   | 23        | 5.94%   |
| AMD Ryzen 7             | 21        | 5.43%   |
| Intel Core 2 Duo        | 16        | 4.13%   |
| Intel Celeron           | 16        | 4.13%   |
| Intel Pentium           | 10        | 2.58%   |
| Intel Pentium Dual-Core | 8         | 2.07%   |
| AMD Ryzen 9             | 6         | 1.55%   |
| Intel Xeon              | 5         | 1.29%   |
| Intel Core i9           | 5         | 1.29%   |
| Intel Atom              | 5         | 1.29%   |
| Intel Core 2            | 4         | 1.03%   |
| AMD FX                  | 4         | 1.03%   |
| Intel Pentium 4         | 3         | 0.78%   |
| AMD Ryzen 7 PRO         | 3         | 0.78%   |
| AMD Ryzen 3             | 3         | 0.78%   |
| AMD Phenom II           | 3         | 0.78%   |
| AMD Athlon II X2        | 3         | 0.78%   |
| AMD A8                  | 3         | 0.78%   |
| Intel Pentium Silver    | 2         | 0.52%   |
| Intel Pentium D         | 2         | 0.52%   |
| Intel Genuine           | 2         | 0.52%   |
| AMD Phenom II X4        | 2         | 0.52%   |
| AMD E                   | 2         | 0.52%   |
| AMD Athlon 64 X2        | 2         | 0.52%   |
| Intel Core m7           | 1         | 0.26%   |
| Intel Core 2 Quad       | 1         | 0.26%   |
| AMD Sempron             | 1         | 0.26%   |
| AMD PRO A8              | 1         | 0.26%   |
| AMD C-60                | 1         | 0.26%   |
| AMD C-50                | 1         | 0.26%   |
| AMD Athlon II X4        | 1         | 0.26%   |
| AMD A6                  | 1         | 0.26%   |
| AMD A4                  | 1         | 0.26%   |
| AMD A10                 | 1         | 0.26%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 153       | 39.33%  |
| 4       | 133       | 34.19%  |
| 6       | 51        | 13.11%  |
| 8       | 34        | 8.74%   |
| 1       | 6         | 1.54%   |
| 12      | 5         | 1.29%   |
| 16      | 2         | 0.51%   |
| 10      | 2         | 0.51%   |
| Unknown | 2         | 0.51%   |
| 14      | 1         | 0.26%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 385       | 98.97%  |
| 2       | 3         | 0.77%   |
| Unknown | 1         | 0.26%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 267       | 68.64%  |
| 1       | 120       | 30.85%  |
| Unknown | 2         | 0.51%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 381       | 98.45%  |
| 32-bit         | 3         | 0.78%   |
| Unknown        | 2         | 0.52%   |
| 64-bit         | 1         | 0.26%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 121       | 30.1%   |
| 0x306c3    | 24        | 5.97%   |
| 0x306a9    | 24        | 5.97%   |
| 0x206a7    | 23        | 5.72%   |
| 0x1067a    | 12        | 2.99%   |
| 0x806ea    | 10        | 2.49%   |
| 0x406e3    | 10        | 2.49%   |
| 0x20655    | 8         | 1.99%   |
| 0x806c1    | 7         | 1.74%   |
| 0x906e9    | 6         | 1.49%   |
| 0x806ec    | 6         | 1.49%   |
| 0x506e3    | 6         | 1.49%   |
| 0x40651    | 6         | 1.49%   |
| 0x306d4    | 6         | 1.49%   |
| 0x0a50000c | 6         | 1.49%   |
| 0x010000c8 | 6         | 1.49%   |
| 0x906ea    | 5         | 1.24%   |
| 0x30678    | 5         | 1.24%   |
| 0x08701021 | 5         | 1.24%   |
| 0x08108109 | 4         | 1%      |
| 0x08001137 | 4         | 1%      |
| 0xa0653    | 3         | 0.75%   |
| 0xa0652    | 3         | 0.75%   |
| 0x906ed    | 3         | 0.75%   |
| 0x806eb    | 3         | 0.75%   |
| 0x6fd      | 3         | 0.75%   |
| 0x20652    | 3         | 0.75%   |
| 0x0a50000d | 3         | 0.75%   |
| 0x0800820d | 3         | 0.75%   |
| 0xf43      | 2         | 0.5%    |
| 0x706a1    | 2         | 0.5%    |
| 0x6f2      | 2         | 0.5%    |
| 0x406c3    | 2         | 0.5%    |
| 0x106e5    | 2         | 0.5%    |
| 0x10676    | 2         | 0.5%    |
| 0x0a50000b | 2         | 0.5%    |
| 0x0a404101 | 2         | 0.5%    |
| 0x0a201016 | 2         | 0.5%    |
| 0x0a201009 | 2         | 0.5%    |
| 0x08608103 | 2         | 0.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 52        | 13.44%  |
| Haswell          | 39        | 10.08%  |
| IvyBridge        | 33        | 8.53%   |
| SandyBridge      | 28        | 7.24%   |
| Zen 3            | 26        | 6.72%   |
| Skylake          | 20        | 5.17%   |
| Penryn           | 19        | 4.91%   |
| Unknown          | 16        | 4.13%   |
| Zen 2            | 15        | 3.88%   |
| Westmere         | 14        | 3.62%   |
| Zen+             | 13        | 3.36%   |
| Core             | 13        | 3.36%   |
| CometLake        | 12        | 3.1%    |
| TigerLake        | 11        | 2.84%   |
| K10              | 9         | 2.33%   |
| Zen              | 8         | 2.07%   |
| Silvermont       | 8         | 2.07%   |
| Broadwell        | 8         | 2.07%   |
| Piledriver       | 7         | 1.81%   |
| NetBurst         | 5         | 1.29%   |
| Goldmont plus    | 5         | 1.29%   |
| Nehalem          | 4         | 1.03%   |
| Bobcat           | 4         | 1.03%   |
| Goldmont         | 3         | 0.78%   |
| Alderlake Hybrid | 3         | 0.78%   |
| K8 Hammer        | 2         | 0.52%   |
| Jaguar           | 2         | 0.52%   |
| Icelake          | 2         | 0.52%   |
| Bonnell          | 2         | 0.52%   |
| Tremont          | 1         | 0.26%   |
| Steamroller      | 1         | 0.26%   |
| K8 & K10 hybrid  | 1         | 0.26%   |
| Excavator        | 1         | 0.26%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 217       | 46.87%  |
| Nvidia                           | 135       | 29.16%  |
| AMD                              | 109       | 23.54%  |
| Silicon Integrated Systems [SiS] | 1         | 0.22%   |
| Matrox Electronics Systems       | 1         | 0.22%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 23        | 4.75%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 19        | 3.93%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 13        | 2.69%   |
| Intel UHD Graphics 620                                                        | 11        | 2.27%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 11        | 2.27%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                  | 10        | 2.07%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 9         | 1.86%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 9         | 1.86%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 9         | 1.86%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 8         | 1.65%   |
| Intel Core Processor Integrated Graphics Controller                           | 8         | 1.65%   |
| Intel HD Graphics 5500                                                        | 7         | 1.45%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 7         | 1.45%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 7         | 1.45%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller              | 6         | 1.24%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 6         | 1.24%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                 | 6         | 1.24%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 6         | 1.24%   |
| Nvidia GF108M [GeForce GT 540M]                                               | 5         | 1.03%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 5         | 1.03%   |
| Intel HD Graphics 530                                                         | 5         | 1.03%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 5         | 1.03%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 5         | 1.03%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 4         | 0.83%   |
| Nvidia GP108M [GeForce MX150]                                                 | 4         | 0.83%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 4         | 0.83%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                            | 4         | 0.83%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                           | 4         | 0.83%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 4         | 0.83%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller     | 4         | 0.83%   |
| Intel HD Graphics 630                                                         | 4         | 0.83%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 4         | 0.83%   |
| Intel 4 Series Chipset Integrated Graphics Controller                         | 4         | 0.83%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                    | 4         | 0.83%   |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                              | 4         | 0.83%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                         | 3         | 0.62%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                        | 3         | 0.62%   |
| Nvidia GP108M [GeForce MX330]                                                 | 3         | 0.62%   |
| Nvidia GP104 [GeForce GTX 1070]                                               | 3         | 0.62%   |
| Nvidia GM204 [GeForce GTX 970]                                                | 3         | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 145       | 36.99%  |
| 1 x AMD        | 83        | 21.17%  |
| 1 x Nvidia     | 73        | 18.62%  |
| Intel + Nvidia | 57        | 14.54%  |
| 2 x AMD        | 11        | 2.81%   |
| Intel + AMD    | 11        | 2.81%   |
| AMD + Nvidia   | 4         | 1.02%   |
| Other          | 3         | 0.77%   |
| 2 x Nvidia     | 2         | 0.51%   |
| 2 x Intel      | 1         | 0.26%   |
| 1 x SiS        | 1         | 0.26%   |
| 1 x Matrox     | 1         | 0.26%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 313       | 78.45%  |
| Proprietary | 73        | 18.3%   |
| Unknown     | 13        | 3.26%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 201       | 49.63%  |
| 1.01-2.0   | 65        | 16.05%  |
| 0.01-0.5   | 46        | 11.36%  |
| 0.51-1.0   | 29        | 7.16%   |
| 3.01-4.0   | 26        | 6.42%   |
| 7.01-8.0   | 16        | 3.95%   |
| 5.01-6.0   | 15        | 3.7%    |
| 8.01-16.0  | 5         | 1.23%   |
| 2.01-3.0   | 1         | 0.25%   |
| 16.01-24.0 | 1         | 0.25%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 59        | 13.88%  |
| AU Optronics            | 49        | 11.53%  |
| LG Display              | 48        | 11.29%  |
| Dell                    | 33        | 7.76%   |
| BOE                     | 33        | 7.76%   |
| Chimei Innolux          | 31        | 7.29%   |
| Lenovo                  | 23        | 5.41%   |
| Goldstar                | 22        | 5.18%   |
| Philips                 | 20        | 4.71%   |
| AOC                     | 19        | 4.47%   |
| Chi Mei Optoelectronics | 12        | 2.82%   |
| Hewlett-Packard         | 8         | 1.88%   |
| BenQ                    | 8         | 1.88%   |
| Ancor Communications    | 8         | 1.88%   |
| PANDA                   | 5         | 1.18%   |
| Sony                    | 4         | 0.94%   |
| Sharp                   | 4         | 0.94%   |
| CSO                     | 4         | 0.94%   |
| Apple                   | 3         | 0.71%   |
| ViewSonic               | 2         | 0.47%   |
| NEC Computers           | 2         | 0.47%   |
| LG Philips              | 2         | 0.47%   |
| LG Electronics          | 2         | 0.47%   |
| Iiyama                  | 2         | 0.47%   |
| ASUSTek Computer        | 2         | 0.47%   |
| Valve                   | 1         | 0.24%   |
| Unknown (XXX)           | 1         | 0.24%   |
| Unknown (AAA)           | 1         | 0.24%   |
| Toshiba                 | 1         | 0.24%   |
| MStar                   | 1         | 0.24%   |
| Mi                      | 1         | 0.24%   |
| Medion                  | 1         | 0.24%   |
| LGD                     | 1         | 0.24%   |
| KDC                     | 1         | 0.24%   |
| JDI                     | 1         | 0.24%   |
| InfoVision              | 1         | 0.24%   |
| IBM                     | 1         | 0.24%   |
| HKC                     | 1         | 0.24%   |
| Hitachi                 | 1         | 0.24%   |
| HannStar                | 1         | 0.24%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 4         | 0.9%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 4         | 0.9%    |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch     | 3         | 0.68%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch              | 3         | 0.68%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 3         | 0.68%   |
| Lenovo T24i-10 LEN61A6 1920x1080 527x296mm 23.8-inch                     | 3         | 0.68%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 3         | 0.68%   |
| Dell P2719H DEL4184 1920x1080 598x336mm 27.0-inch                        | 3         | 0.68%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 3         | 0.68%   |
| BenQ GW2765 BNQ78D6 2560x1440 597x336mm 27.0-inch                        | 3         | 0.68%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 3         | 0.68%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 3         | 0.68%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 3         | 0.68%   |
| AOC 27V2G5 AOC2702 1920x1080 598x336mm 27.0-inch                         | 3         | 0.68%   |
| Sony LCD Monitor MS_9005 1920x1200 331x207mm 15.4-inch                   | 2         | 0.45%   |
| Samsung Electronics T24E390 SAM0C20 1920x1080 521x293mm 23.5-inch        | 2         | 0.45%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch      | 2         | 0.45%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 2         | 0.45%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch     | 2         | 0.45%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch    | 2         | 0.45%   |
| Samsung Electronics LCD Monitor C32HG7x 2560x1440                        | 2         | 0.45%   |
| PANDA LM133LF1L01 NCP13FB 1920x1080 294x165mm 13.3-inch                  | 2         | 0.45%   |
| LG Philips LCD Monitor LPL1E01 1280x800 331x207mm 15.4-inch              | 2         | 0.45%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch            | 2         | 0.45%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch             | 2         | 0.45%   |
| LG Display LCD Monitor LGD03D9 1366x768 345x194mm 15.6-inch              | 2         | 0.45%   |
| LG Display LCD Monitor LGD02DA 1920x1080 380x220mm 17.3-inch             | 2         | 0.45%   |
| Lenovo P24h-2L LEN62B2 2560x1440 530x300mm 24.0-inch                     | 2         | 0.45%   |
| Lenovo LEN-M800z-C LEN8000 1920x1080 477x268mm 21.5-inch                 | 2         | 0.45%   |
| Lenovo LEN T2324pA LEN60C7 1920x1080 509x286mm 23.0-inch                 | 2         | 0.45%   |
| Dell U2419H DEL4148 1920x1080 527x296mm 23.8-inch                        | 2         | 0.45%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                         | 2         | 0.45%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                        | 2         | 0.45%   |
| Dell P2314H DEL4099 1920x1080 509x286mm 23.0-inch                        | 2         | 0.45%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 2         | 0.45%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 0.45%   |
| Chimei Innolux LCD Monitor CMN150C 1920x1080 344x193mm 15.5-inch         | 2         | 0.45%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch         | 2         | 0.45%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 2         | 0.45%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch          | 2         | 0.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 189       | 46.32%  |
| 1366x768 (WXGA)    | 64        | 15.69%  |
| 2560x1440 (QHD)    | 30        | 7.35%   |
| 3840x2160 (4K)     | 24        | 5.88%   |
| 1600x900 (HD+)     | 21        | 5.15%   |
| 1280x1024 (SXGA)   | 20        | 4.9%    |
| 1280x800 (WXGA)    | 11        | 2.7%    |
| 1920x1200 (WUXGA)  | 8         | 1.96%   |
| 3440x1440          | 5         | 1.23%   |
| 1680x1050 (WSXGA+) | 5         | 1.23%   |
| 1440x900 (WXGA+)   | 5         | 1.23%   |
| 2560x1600          | 3         | 0.74%   |
| 2560x1080          | 3         | 0.74%   |
| Unknown            | 3         | 0.74%   |
| 3840x2400          | 2         | 0.49%   |
| 3840x1600          | 2         | 0.49%   |
| 3840x1080          | 2         | 0.49%   |
| 2880x1800          | 2         | 0.49%   |
| 800x1280           | 1         | 0.25%   |
| 3200x1080          | 1         | 0.25%   |
| 3120x2080          | 1         | 0.25%   |
| 3000x2000          | 1         | 0.25%   |
| 2160x1440          | 1         | 0.25%   |
| 1360x768           | 1         | 0.25%   |
| 1280x720 (HD)      | 1         | 0.25%   |
| 1024x768 (XGA)     | 1         | 0.25%   |
| 1024x600           | 1         | 0.25%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 128       | 29.98%  |
| 24      | 37        | 8.67%   |
| 27      | 32        | 7.49%   |
| 23      | 31        | 7.26%   |
| 13      | 29        | 6.79%   |
| 14      | 28        | 6.56%   |
| 17      | 27        | 6.32%   |
| 21      | 23        | 5.39%   |
| Unknown | 13        | 3.04%   |
| 19      | 11        | 2.58%   |
| 12      | 10        | 2.34%   |
| 31      | 8         | 1.87%   |
| 18      | 7         | 1.64%   |
| 34      | 6         | 1.41%   |
| 16      | 6         | 1.41%   |
| 40      | 5         | 1.17%   |
| 20      | 5         | 1.17%   |
| 84      | 3         | 0.7%    |
| 54      | 2         | 0.47%   |
| 25      | 2         | 0.47%   |
| 22      | 2         | 0.47%   |
| 10      | 2         | 0.47%   |
| 72      | 1         | 0.23%   |
| 55      | 1         | 0.23%   |
| 52      | 1         | 0.23%   |
| 50      | 1         | 0.23%   |
| 37      | 1         | 0.23%   |
| 33      | 1         | 0.23%   |
| 32      | 1         | 0.23%   |
| 29      | 1         | 0.23%   |
| 11      | 1         | 0.23%   |
| 7       | 1         | 0.23%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 187       | 44.42%  |
| 501-600     | 93        | 22.09%  |
| 401-500     | 38        | 9.03%   |
| 351-400     | 29        | 6.89%   |
| 201-300     | 24        | 5.7%    |
| 601-700     | 13        | 3.09%   |
| Unknown     | 13        | 3.09%   |
| 701-800     | 8         | 1.9%    |
| 801-900     | 6         | 1.43%   |
| 1001-1500   | 5         | 1.19%   |
| 1501-2000   | 4         | 0.95%   |
| 1-100       | 1         | 0.24%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 298       | 78.01%  |
| 16/10   | 38        | 9.95%   |
| 5/4     | 19        | 4.97%   |
| Unknown | 12        | 3.14%   |
| 21/9    | 7         | 1.83%   |
| 3/2     | 5         | 1.31%   |
| 4/3     | 2         | 0.52%   |
| 0.67    | 1         | 0.26%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 125       | 29.27%  |
| 201-250        | 78        | 18.27%  |
| 81-90          | 48        | 11.24%  |
| 301-350        | 32        | 7.49%   |
| 151-200        | 25        | 5.85%   |
| 351-500        | 17        | 3.98%   |
| 141-150        | 16        | 3.75%   |
| 121-130        | 16        | 3.75%   |
| Unknown        | 13        | 3.04%   |
| More than 1000 | 9         | 2.11%   |
| 61-70          | 9         | 2.11%   |
| 251-300        | 9         | 2.11%   |
| 71-80          | 8         | 1.87%   |
| 111-120        | 6         | 1.41%   |
| 501-1000       | 6         | 1.41%   |
| 131-140        | 3         | 0.7%    |
| 91-100         | 3         | 0.7%    |
| 41-50          | 2         | 0.47%   |
| 51-60          | 1         | 0.23%   |
| 1-40           | 1         | 0.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 147       | 35.59%  |
| 121-160       | 127       | 30.75%  |
| 101-120       | 93        | 22.52%  |
| 161-240       | 21        | 5.08%   |
| Unknown       | 13        | 3.15%   |
| More than 240 | 7         | 1.69%   |
| 1-50          | 5         | 1.21%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 306       | 78.26%  |
| 2     | 65        | 16.62%  |
| 0     | 15        | 3.84%   |
| 3     | 5         | 1.28%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 205       | 35.9%   |
| Intel                             | 172       | 30.12%  |
| Qualcomm Atheros                  | 77        | 13.49%  |
| Broadcom                          | 37        | 6.48%   |
| MediaTek                          | 9         | 1.58%   |
| Broadcom Limited                  | 9         | 1.58%   |
| Marvell Technology Group          | 7         | 1.23%   |
| TP-Link                           | 6         | 1.05%   |
| Ralink                            | 6         | 1.05%   |
| Lenovo                            | 4         | 0.7%    |
| Qualcomm Atheros Communications   | 3         | 0.53%   |
| Nvidia                            | 3         | 0.53%   |
| D-Link                            | 3         | 0.53%   |
| Sierra Wireless                   | 2         | 0.35%   |
| Ralink Technology                 | 2         | 0.35%   |
| Microsoft                         | 2         | 0.35%   |
| JMicron Technology                | 2         | 0.35%   |
| Huawei Technologies               | 2         | 0.35%   |
| Hewlett-Packard                   | 2         | 0.35%   |
| Fibocom                           | 2         | 0.35%   |
| Ericsson Business Mobile Networks | 2         | 0.35%   |
| Dell                              | 2         | 0.35%   |
| ASIX Electronics                  | 2         | 0.35%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.18%   |
| U-Blox                            | 1         | 0.18%   |
| Samsung Electronics               | 1         | 0.18%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.18%   |
| MOBILE                            | 1         | 0.18%   |
| Edimax Technology                 | 1         | 0.18%   |
| D-Link System                     | 1         | 0.18%   |
| ASUSTek Computer                  | 1         | 0.18%   |
| Aquantia                          | 1         | 0.18%   |
| 3Com                              | 1         | 0.18%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 148       | 21.83%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 21        | 3.1%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 16        | 2.36%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 16        | 2.36%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 13        | 1.92%   |
| Intel Wi-Fi 6 AX200                                               | 13        | 1.92%   |
| Intel Wireless 8265 / 8275                                        | 11        | 1.62%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 10        | 1.47%   |
| Intel Wireless 7260                                               | 10        | 1.47%   |
| Intel Wi-Fi 6 AX201                                               | 10        | 1.47%   |
| Realtek RTL8125 2.5GbE Controller                                 | 9         | 1.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 9         | 1.33%   |
| Intel Wireless 8260                                               | 9         | 1.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 9         | 1.33%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 8         | 1.18%   |
| Intel Wireless 7265                                               | 8         | 1.18%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 7         | 1.03%   |
| Intel I211 Gigabit Network Connection                             | 7         | 1.03%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 7         | 1.03%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 6         | 0.88%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 6         | 0.88%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 5         | 0.74%   |
| Intel Wireless 3165                                               | 5         | 0.74%   |
| Intel Ethernet Controller I225-V                                  | 5         | 0.74%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 0.74%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 0.74%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 5         | 0.74%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 0.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 0.59%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 0.59%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 4         | 0.59%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 4         | 0.59%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 4         | 0.59%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 4         | 0.59%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 4         | 0.59%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4         | 0.59%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 4         | 0.59%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 0.59%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 0.59%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 142       | 46.86%  |
| Qualcomm Atheros                  | 59        | 19.47%  |
| Realtek Semiconductor             | 34        | 11.22%  |
| Broadcom                          | 25        | 8.25%   |
| MediaTek                          | 9         | 2.97%   |
| TP-Link                           | 6         | 1.98%   |
| Ralink                            | 6         | 1.98%   |
| Qualcomm Atheros Communications   | 3         | 0.99%   |
| D-Link                            | 3         | 0.99%   |
| Sierra Wireless                   | 2         | 0.66%   |
| Ralink Technology                 | 2         | 0.66%   |
| Microsoft                         | 2         | 0.66%   |
| Fibocom                           | 2         | 0.66%   |
| Dell                              | 2         | 0.66%   |
| Broadcom Limited                  | 2         | 0.66%   |
| Ericsson Business Mobile Networks | 1         | 0.33%   |
| Edimax Technology                 | 1         | 0.33%   |
| D-Link System                     | 1         | 0.33%   |
| ASUSTek Computer                  | 1         | 0.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 16        | 5.28%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 13        | 4.29%   |
| Intel Wi-Fi 6 AX200                                                     | 13        | 4.29%   |
| Intel Wireless 8265 / 8275                                              | 11        | 3.63%   |
| Intel Wireless 7260                                                     | 10        | 3.3%    |
| Intel Wi-Fi 6 AX201                                                     | 10        | 3.3%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 2.97%   |
| Intel Wireless 8260                                                     | 9         | 2.97%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 9         | 2.97%   |
| Intel Wireless 7265                                                     | 8         | 2.64%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 7         | 2.31%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 7         | 2.31%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 6         | 1.98%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 6         | 1.98%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 5         | 1.65%   |
| Intel Wireless 3165                                                     | 5         | 1.65%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 1.65%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 5         | 1.65%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.32%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.32%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 1.32%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 4         | 1.32%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 1.32%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 4         | 1.32%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 4         | 1.32%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 1.32%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 3         | 0.99%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 3         | 0.99%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 3         | 0.99%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 0.99%   |
| Intel Wireless-AC 9260                                                  | 3         | 0.99%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 3         | 0.99%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 0.99%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 0.99%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 0.99%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                     | 2         | 0.66%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 0.66%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.66%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.66%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 191       | 53.2%   |
| Intel                         | 86        | 23.96%  |
| Qualcomm Atheros              | 31        | 8.64%   |
| Broadcom                      | 19        | 5.29%   |
| Marvell Technology Group      | 7         | 1.95%   |
| Broadcom Limited              | 7         | 1.95%   |
| Lenovo                        | 4         | 1.11%   |
| Nvidia                        | 3         | 0.84%   |
| JMicron Technology            | 2         | 0.56%   |
| Huawei Technologies           | 2         | 0.56%   |
| ASIX Electronics              | 2         | 0.56%   |
| ZTE WCDMA Technologies MSM    | 1         | 0.28%   |
| OnePlus Technology (Shenzhen) | 1         | 0.28%   |
| MOBILE                        | 1         | 0.28%   |
| Aquantia                      | 1         | 0.28%   |
| 3Com                          | 1         | 0.28%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 148       | 40%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 21        | 5.68%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 16        | 4.32%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 10        | 2.7%    |
| Realtek RTL8125 2.5GbE Controller                                              | 9         | 2.43%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 8         | 2.16%   |
| Intel I211 Gigabit Network Connection                                          | 7         | 1.89%   |
| Intel Ethernet Controller I225-V                                               | 5         | 1.35%   |
| Intel Ethernet Connection I217-LM                                              | 5         | 1.35%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 4         | 1.08%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 4         | 1.08%   |
| Intel Ethernet Connection I219-LM                                              | 4         | 1.08%   |
| Intel Ethernet Connection (4) I219-V                                           | 4         | 1.08%   |
| Intel 82579V Gigabit Network Connection                                        | 4         | 1.08%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 3         | 0.81%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 3         | 0.81%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 3         | 0.81%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 3         | 0.81%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 3         | 0.81%   |
| Intel Ethernet Connection I217-V                                               | 3         | 0.81%   |
| Intel Ethernet Connection (7) I219-V                                           | 3         | 0.81%   |
| Intel Ethernet Connection (7) I219-LM                                          | 3         | 0.81%   |
| Intel Ethernet Connection (6) I219-V                                           | 3         | 0.81%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 3         | 0.81%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 3         | 0.81%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 3         | 0.81%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 2         | 0.54%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 2         | 0.54%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.54%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 2         | 0.54%   |
| Lenovo USB-C Dock Ethernet                                                     | 2         | 0.54%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 2         | 0.54%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 0.54%   |
| Intel Ethernet Connection (2) I219-V                                           | 2         | 0.54%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 0.54%   |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 0.54%   |
| Intel 82578DC Gigabit Network Connection                                       | 2         | 0.54%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 0.54%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 2         | 0.54%   |
| Huawei E353/E3131                                                              | 2         | 0.54%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 342       | 54.03%  |
| WiFi     | 286       | 45.18%  |
| Modem    | 5         | 0.79%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 225       | 54.61%  |
| Ethernet | 187       | 45.39%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 223       | 57.18%  |
| 1     | 151       | 38.72%  |
| 3     | 8         | 2.05%   |
| 0     | 7         | 1.79%   |
| 5     | 1         | 0.26%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 387       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 103       | 45.18%  |
| Qualcomm Atheros Communications | 28        | 12.28%  |
| Cambridge Silicon Radio         | 18        | 7.89%   |
| Realtek Semiconductor           | 15        | 6.58%   |
| IMC Networks                    | 15        | 6.58%   |
| Broadcom                        | 15        | 6.58%   |
| Foxconn / Hon Hai               | 9         | 3.95%   |
| Ralink                          | 4         | 1.75%   |
| ASUSTek Computer                | 4         | 1.75%   |
| Apple                           | 4         | 1.75%   |
| Hewlett-Packard                 | 3         | 1.32%   |
| Dell                            | 3         | 1.32%   |
| Toshiba                         | 2         | 0.88%   |
| Edimax Technology               | 2         | 0.88%   |
| Taiyo Yuden                     | 1         | 0.44%   |
| MediaTek                        | 1         | 0.44%   |
| Lite-On Technology              | 1         | 0.44%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 40        | 17.54%  |
| Intel AX201 Bluetooth                               | 21        | 9.21%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 18        | 7.89%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 14        | 6.14%   |
| Intel AX200 Bluetooth                               | 12        | 5.26%   |
| Qualcomm Atheros  Bluetooth Device                  | 10        | 4.39%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 9         | 3.95%   |
| Realtek Bluetooth Radio                             | 8         | 3.51%   |
| IMC Networks Bluetooth Radio                        | 5         | 2.19%   |
| Ralink RT3290 Bluetooth                             | 4         | 1.75%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 4         | 1.75%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 4         | 1.75%   |
| Intel AX210 Bluetooth                               | 4         | 1.75%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 1.32%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 1.32%   |
| IMC Networks Wireless_Device                        | 3         | 1.32%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 3         | 1.32%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 1.32%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 3         | 1.32%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 1.32%   |
| Realtek 802.11ac WLAN Adapter                       | 2         | 0.88%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 0.88%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 0.88%   |
| Intel Bluetooth Device                              | 2         | 0.88%   |
| Edimax Bluetooth Adapter                            | 2         | 0.88%   |
| Dell Wireless 355 Bluetooth                         | 2         | 0.88%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 0.88%   |
| Broadcom BCM2046 Bluetooth Device                   | 2         | 0.88%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 2         | 0.88%   |
| ASUS BT-270 Bluetooth Adapter                       | 2         | 0.88%   |
| Apple Bluetooth Host Controller                     | 2         | 0.88%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.44%   |
| Toshiba Bluetooth Device                            | 1         | 0.44%   |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)             | 1         | 0.44%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.44%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.44%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.44%   |
| Qualcomm Atheros Bluetooth                          | 1         | 0.44%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.44%   |
| MediaTek Wireless_Device                            | 1         | 0.44%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 280       | 50.54%  |
| AMD                                             | 118       | 21.3%   |
| Nvidia                                          | 95        | 17.15%  |
| C-Media Electronics                             | 10        | 1.81%   |
| JMTek                                           | 7         | 1.26%   |
| Logitech                                        | 4         | 0.72%   |
| Lenovo                                          | 4         | 0.72%   |
| Creative Technology                             | 3         | 0.54%   |
| Yamaha                                          | 2         | 0.36%   |
| SteelSeries ApS                                 | 2         | 0.36%   |
| Realtek Semiconductor                           | 2         | 0.36%   |
| PreSonus Audio Electronics                      | 2         | 0.36%   |
| Hewlett-Packard                                 | 2         | 0.36%   |
| GN Netcom                                       | 2         | 0.36%   |
| Generalplus Technology                          | 2         | 0.36%   |
| ASUSTek Computer                                | 2         | 0.36%   |
| XMOS                                            | 1         | 0.18%   |
| Texas Instruments                               | 1         | 0.18%   |
| Sony                                            | 1         | 0.18%   |
| Silicon Integrated Systems [SiS]                | 1         | 0.18%   |
| Sennheiser Communications                       | 1         | 0.18%   |
| Schiit Audio                                    | 1         | 0.18%   |
| Razer USA                                       | 1         | 0.18%   |
| Panasonic (Matsushita)                          | 1         | 0.18%   |
| Microsoft                                       | 1         | 0.18%   |
| Micro Star International                        | 1         | 0.18%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.18%   |
| Kingston Technology                             | 1         | 0.18%   |
| Focusrite-Novation                              | 1         | 0.18%   |
| DSEA A/S                                        | 1         | 0.18%   |
| Creative Labs                                   | 1         | 0.18%   |
| Audio-Technica                                  | 1         | 0.18%   |
| Allen&Heath                                     | 1         | 0.18%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 38        | 5.75%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 32        | 4.84%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 29        | 4.39%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 28        | 4.24%   |
| Intel Sunrise Point-LP HD Audio                                            | 25        | 3.78%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 21        | 3.18%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 21        | 3.18%   |
| AMD Starship/Matisse HD Audio Controller                                   | 18        | 2.72%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 17        | 2.57%   |
| Intel Cannon Lake PCH cAVS                                                 | 16        | 2.42%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 16        | 2.42%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 15        | 2.27%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 12        | 1.82%   |
| Nvidia GF108 High Definition Audio Controller                              | 11        | 1.66%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 11        | 1.66%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 10        | 1.51%   |
| Nvidia GP107GL High Definition Audio Controller                            | 9         | 1.36%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 9         | 1.36%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 9         | 1.36%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 9         | 1.36%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 8         | 1.21%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 8         | 1.21%   |
| Intel Broadwell-U Audio Controller                                         | 8         | 1.21%   |
| Nvidia TU116 High Definition Audio Controller                              | 7         | 1.06%   |
| Intel Haswell-ULT HD Audio Controller                                      | 7         | 1.06%   |
| Intel Comet Lake PCH cAVS                                                  | 7         | 1.06%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 7         | 1.06%   |
| Intel 8 Series HD Audio Controller                                         | 7         | 1.06%   |
| Intel 200 Series PCH HD Audio                                              | 7         | 1.06%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 7         | 1.06%   |
| Nvidia GP106 High Definition Audio Controller                              | 6         | 0.91%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 5         | 0.76%   |
| Nvidia TU106 High Definition Audio Controller                              | 5         | 0.76%   |
| Intel Comet Lake PCH-LP cAVS                                               | 5         | 0.76%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 5         | 0.76%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 5         | 0.76%   |
| AMD Navi 10 HDMI Audio                                                     | 5         | 0.76%   |
| AMD FCH Azalia Controller                                                  | 5         | 0.76%   |
| Nvidia GP104 High Definition Audio Controller                              | 4         | 0.61%   |
| Nvidia GK107 HDMI Audio Controller                                         | 4         | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 63        | 22.99%  |
| Kingston            | 44        | 16.06%  |
| SK hynix            | 33        | 12.04%  |
| Unknown             | 23        | 8.39%   |
| Micron Technology   | 19        | 6.93%   |
| Crucial             | 18        | 6.57%   |
| G.Skill             | 17        | 6.2%    |
| Ramaxel Technology  | 10        | 3.65%   |
| Patriot             | 10        | 3.65%   |
| Nanya Technology    | 6         | 2.19%   |
| A-DATA Technology   | 6         | 2.19%   |
| Elpida              | 5         | 1.82%   |
| GOODRAM             | 4         | 1.46%   |
| Corsair             | 4         | 1.46%   |
| Unknown (ABCD)      | 3         | 1.09%   |
| Team                | 3         | 1.09%   |
| Transcend           | 2         | 0.73%   |
| Lexar               | 2         | 0.73%   |
| Atermiter           | 1         | 0.36%   |
| Unknown             | 1         | 0.36%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 1.69%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 1.69%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 1.01%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 1.01%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 3         | 1.01%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 3         | 1.01%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 3         | 1.01%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 3         | 1.01%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 1.01%   |
| Patriot RAM 3200 C16 Series 16GB DIMM DDR4 3600MT/s              | 3         | 1.01%   |
| G.Skill RAM F4-3200C16-8GIS 8192MB DIMM DDR4 3200MT/s            | 3         | 1.01%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 2         | 0.68%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 2         | 0.68%   |
| Transcend RAM JM2666HLB-8G 8192MB DIMM DDR4 2667MT/s             | 2         | 0.68%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.68%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 0.68%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 2         | 0.68%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 0.68%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 2         | 0.68%   |
| Samsung RAM M471B5273CH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.68%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.68%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 0.68%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 2         | 0.68%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.68%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.68%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM 4800MT/s               | 2         | 0.68%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 2         | 0.68%   |
| Patriot RAM PSD48G266681 8GB DIMM DDR4 2934MT/s                  | 2         | 0.68%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s             | 2         | 0.68%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 2         | 0.68%   |
| Micron RAM 8ATF2G64HZ-3G2E1 16GB SODIMM DDR4 3200MT/s            | 2         | 0.68%   |
| Kingston RAM MSI16D3LS1KFG/8G 8GB SODIMM DDR3 1600MT/s           | 2         | 0.68%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s             | 2         | 0.68%   |
| GOODRAM RAM W-DL16S08G 8GB SODIMM DDR3 1600MT/s                  | 2         | 0.68%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s            | 2         | 0.68%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s           | 2         | 0.68%   |
| Elpida RAM EBJ41UF8BDU0-GN-F 4GB SODIMM DDR3 1600MT/s            | 2         | 0.68%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 1         | 0.34%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s                     | 1         | 0.34%   |
| Unknown RAM Module 512MB SODIMM DDR2 667MT/s                     | 1         | 0.34%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 100       | 42.37%  |
| DDR3    | 91        | 38.56%  |
| DDR2    | 12        | 5.08%   |
| LPDDR4  | 7         | 2.97%   |
| SDRAM   | 6         | 2.54%   |
| LPDDR3  | 6         | 2.54%   |
| Unknown | 6         | 2.54%   |
| DDR5    | 4         | 1.69%   |
| DDR     | 2         | 0.85%   |
| LPDDR5  | 1         | 0.42%   |
| DRAM    | 1         | 0.42%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 143       | 61.11%  |
| DIMM         | 82        | 35.04%  |
| Row Of Chips | 9         | 3.85%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 99        | 39.76%  |
| 4096  | 74        | 29.72%  |
| 16384 | 32        | 12.85%  |
| 2048  | 25        | 10.04%  |
| 32768 | 8         | 3.21%   |
| 1024  | 7         | 2.81%   |
| 512   | 4         | 1.61%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 66        | 25.58%  |
| 3200    | 41        | 15.89%  |
| 2667    | 38        | 14.73%  |
| 1333    | 18        | 6.98%   |
| 2400    | 11        | 4.26%   |
| 1334    | 11        | 4.26%   |
| 2133    | 10        | 3.88%   |
| 667     | 8         | 3.1%    |
| 800     | 6         | 2.33%   |
| 1867    | 5         | 1.94%   |
| 3600    | 4         | 1.55%   |
| Unknown | 4         | 1.55%   |
| 4800    | 3         | 1.16%   |
| 3733    | 3         | 1.16%   |
| 2800    | 3         | 1.16%   |
| 2666    | 3         | 1.16%   |
| 1067    | 3         | 1.16%   |
| 6400    | 2         | 0.78%   |
| 3866    | 2         | 0.78%   |
| 3800    | 2         | 0.78%   |
| 3266    | 2         | 0.78%   |
| 2934    | 2         | 0.78%   |
| 400     | 2         | 0.78%   |
| 333     | 2         | 0.78%   |
| 4267    | 1         | 0.39%   |
| 3533    | 1         | 0.39%   |
| 3400    | 1         | 0.39%   |
| 3066    | 1         | 0.39%   |
| 3000    | 1         | 0.39%   |
| 2048    | 1         | 0.39%   |
| 1066    | 1         | 0.39%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 3         | 60%     |
| Hewlett-Packard     | 2         | 40%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung SCX-4200 series | 1         | 20%     |
| Samsung ML-1670 Series  | 1         | 20%     |
| Samsung M2070 Series    | 1         | 20%     |
| HP PSC-1315/PSC-1317    | 1         | 20%     |
| HP LaserJet 1020        | 1         | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Canon CanoScan LIDE 25 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 50        | 20.33%  |
| IMC Networks                           | 39        | 15.85%  |
| Microdia                               | 20        | 8.13%   |
| Sunplus Innovation Technology          | 15        | 6.1%    |
| Bison Electronics                      | 15        | 6.1%    |
| Logitech                               | 14        | 5.69%   |
| Suyin                                  | 13        | 5.28%   |
| Realtek Semiconductor                  | 12        | 4.88%   |
| Luxvisions Innotech Limited            | 7         | 2.85%   |
| Syntek                                 | 6         | 2.44%   |
| Alcor Micro                            | 6         | 2.44%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 2.03%   |
| Lite-On Technology                     | 4         | 1.63%   |
| Apple                                  | 4         | 1.63%   |
| Sonix Technology                       | 3         | 1.22%   |
| Silicon Motion                         | 3         | 1.22%   |
| Quanta                                 | 3         | 1.22%   |
| Acer                                   | 3         | 1.22%   |
| Samsung Electronics                    | 2         | 0.81%   |
| Panasonic (Matsushita)                 | 2         | 0.81%   |
| OmniVision Technologies                | 2         | 0.81%   |
| Lenovo                                 | 2         | 0.81%   |
| Genesys Logic                          | 2         | 0.81%   |
| DigiTech                               | 2         | 0.81%   |
| Z-Star Microelectronics                | 1         | 0.41%   |
| Unknown (3730304233333731323245)       | 1         | 0.41%   |
| Ricoh                                  | 1         | 0.41%   |
| Razer USA                              | 1         | 0.41%   |
| Primax Electronics                     | 1         | 0.41%   |
| Pixart Imaging                         | 1         | 0.41%   |
| Intel                                  | 1         | 0.41%   |
| Importek                               | 1         | 0.41%   |
| Huawei Technologies                    | 1         | 0.41%   |
| Cubeternet                             | 1         | 0.41%   |
| Arkmicro Technologies                  | 1         | 0.41%   |
| ALi                                    | 1         | 0.41%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 14        | 5.69%   |
| IMC Networks Integrated Camera                      | 12        | 4.88%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 11        | 4.47%   |
| Microdia Integrated_Webcam_HD                       | 9         | 3.66%   |
| Bison Integrated Camera                             | 5         | 2.03%   |
| Sunplus Integrated_Webcam_HD                        | 4         | 1.63%   |
| Realtek Integrated_Webcam_HD                        | 4         | 1.63%   |
| Syntek Lenovo EasyCamera                            | 3         | 1.22%   |
| Sunplus HP HD Webcam [Fixed]                        | 3         | 1.22%   |
| Microdia Integrated Webcam                          | 3         | 1.22%   |
| Luxvisions Innotech Limited HP HD Camera            | 3         | 1.22%   |
| Logitech Webcam C270                                | 3         | 1.22%   |
| IMC Networks UVC VGA Webcam                         | 3         | 1.22%   |
| IMC Networks 2M Integrated Webcam                   | 3         | 1.22%   |
| Chicony USB2.0 HD UVC WebCam                        | 3         | 1.22%   |
| Chicony ThinkPad T490 Webcam                        | 3         | 1.22%   |
| Suyin Laptop_Integrated_Webcam_HD                   | 2         | 0.81%   |
| Suyin HP Webcam                                     | 2         | 0.81%   |
| Suyin 1.3M HD WebCam                                | 2         | 0.81%   |
| Sunplus HD WebCam                                   | 2         | 0.81%   |
| Sunplus Asus Webcam                                 | 2         | 0.81%   |
| Sonix USB2.0 HD UVC WebCam                          | 2         | 0.81%   |
| Silicon Motion Lenovo EasyCamera                    | 2         | 0.81%   |
| Samsung Galaxy series, misc. (MTP mode)             | 2         | 0.81%   |
| Panasonic (Matsushita) TY-CC20W                     | 2         | 0.81%   |
| Microdia Webcam Vitade AF                           | 2         | 0.81%   |
| Luxvisions Innotech Limited Integrated Camera       | 2         | 0.81%   |
| Logitech HD Webcam C615                             | 2         | 0.81%   |
| Logitech HD Pro Webcam C920                         | 2         | 0.81%   |
| Lite-On Integrated Camera                           | 2         | 0.81%   |
| IMC Networks VGA UVC WebCam                         | 2         | 0.81%   |
| Chicony Webcam                                      | 2         | 0.81%   |
| Chicony VGA Webcam                                  | 2         | 0.81%   |
| Chicony USB2.0 0.3M UVC WebCam                      | 2         | 0.81%   |
| Chicony HP Webcam [2 MP Macro]                      | 2         | 0.81%   |
| Chicony HP Laptop Integrated Webcam [2 MP Fixed]    | 2         | 0.81%   |
| Chicony HP HD Webcam [Fixed]                        | 2         | 0.81%   |
| Chicony HP HD Webcam                                | 2         | 0.81%   |
| Chicony HP HD Camera                                | 2         | 0.81%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 2         | 0.81%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 20        | 38.46%  |
| Validity Sensors           | 15        | 28.85%  |
| Shenzhen Goodix Technology | 6         | 11.54%  |
| Elan Microelectronics      | 4         | 7.69%   |
| AuthenTec                  | 4         | 7.69%   |
| STMicroelectronics         | 2         | 3.85%   |
| LighTuning Technology      | 1         | 1.92%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 11        | 21.15%  |
| Validity Sensors VFS471 Fingerprint Reader                | 4         | 7.69%   |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 3         | 5.77%   |
| Shenzhen Goodix Fingerprint Reader                        | 3         | 5.77%   |
| Elan ELAN:Fingerprint                                     | 3         | 5.77%   |
| Validity Sensors VFS5011 Fingerprint Reader               | 2         | 3.85%   |
| Validity Sensors VFS495 Fingerprint Reader                | 2         | 3.85%   |
| Validity Sensors VFS451 Fingerprint Reader                | 2         | 3.85%   |
| Synaptics Metallica MOH Touch Fingerprint Reader          | 2         | 3.85%   |
| STMicroelectronics Fingerprint Reader                     | 2         | 3.85%   |
| Shenzhen Goodix  FingerPrint Device                       | 2         | 3.85%   |
| AuthenTec AES2810                                         | 2         | 3.85%   |
| AuthenTec AES1600                                         | 2         | 3.85%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor         | 1         | 1.92%   |
| Validity Sensors VFS491                                   | 1         | 1.92%   |
| Validity Sensors VFS301 Fingerprint Reader                | 1         | 1.92%   |
| Validity Sensors VFS 5011 fingerprint sensor              | 1         | 1.92%   |
| Validity Sensors Fingerprint scanner                      | 1         | 1.92%   |
| Synaptics UWP WBDI Device                                 | 1         | 1.92%   |
| Synaptics UWP WBDI                                        | 1         | 1.92%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 1.92%   |
| Synaptics Fingerprint reader [HP G6]                      | 1         | 1.92%   |
| Shenzhen Goodix FingerPrint                               | 1         | 1.92%   |
| LighTuning EgisTec Touch Fingerprint Sensor               | 1         | 1.92%   |
| Elan ELAN:ARM-M4                                          | 1         | 1.92%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 14        | 58.33%  |
| Broadcom              | 6         | 25%     |
| Gemalto (was Gemplus) | 3         | 12.5%   |
| Upek                  | 1         | 4.17%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 14        | 58.33%  |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 8.33%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 8.33%   |
| Broadcom 5880                                                                | 2         | 8.33%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 4.17%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 4.17%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 4.17%   |
| Broadcom 58200                                                               | 1         | 4.17%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 282       | 71.39%  |
| 1     | 83        | 21.01%  |
| 2     | 23        | 5.82%   |
| 3     | 6         | 1.52%   |
| 4     | 1         | 0.25%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 50        | 33.78%  |
| Graphics card            | 33        | 22.3%   |
| Chipcard                 | 22        | 14.86%  |
| Net/wireless             | 12        | 8.11%   |
| Multimedia controller    | 8         | 5.41%   |
| Bluetooth                | 7         | 4.73%   |
| Camera                   | 5         | 3.38%   |
| Communication controller | 4         | 2.7%    |
| Storage/raid             | 1         | 0.68%   |
| Storage                  | 1         | 0.68%   |
| Sound                    | 1         | 0.68%   |
| Network                  | 1         | 0.68%   |
| Net/ethernet             | 1         | 0.68%   |
| Flash memory             | 1         | 0.68%   |
| Card reader              | 1         | 0.68%   |

