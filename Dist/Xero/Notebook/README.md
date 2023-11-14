Xero - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------

A project to collect tested hardware configurations for Xero.

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

Total: 254

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad 320-15ABR 80XS      | [c64e4d8a0b](https://linux-hardware.org/?probe=c64e4d8a0b) | Nov 05, 2023 |
| Lenovo        | XiaoXinPro 14 IRH8 83AL     | [de5461c78b](https://linux-hardware.org/?probe=de5461c78b) | Nov 05, 2023 |
| MSI           | Bravo 15 B5DD               | [72b02cceec](https://linux-hardware.org/?probe=72b02cceec) | Nov 05, 2023 |
| MSI           | Bravo 15 B5DD               | [8a35411be4](https://linux-hardware.org/?probe=8a35411be4) | Nov 05, 2023 |
| HP            | Pavilion dv6                | [60ff7a74af](https://linux-hardware.org/?probe=60ff7a74af) | Nov 05, 2023 |
| Acer          | Aspire A315-58              | [95f3002643](https://linux-hardware.org/?probe=95f3002643) | Nov 05, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [6ea9e5b141](https://linux-hardware.org/?probe=6ea9e5b141) | Nov 04, 2023 |
| Toshiba       | Satellite C55-C             | [07e66cf3c5](https://linux-hardware.org/?probe=07e66cf3c5) | Nov 04, 2023 |
| Lenovo        | ThinkPad P43s 20RH0021MX    | [082adbf921](https://linux-hardware.org/?probe=082adbf921) | Nov 04, 2023 |
| Acer          | Nitro AN515-54              | [3ddccb994b](https://linux-hardware.org/?probe=3ddccb994b) | Nov 03, 2023 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | [e5158e3f58](https://linux-hardware.org/?probe=e5158e3f58) | Oct 31, 2023 |
| MSI           | Thin GF63 12VE              | [1776ca1088](https://linux-hardware.org/?probe=1776ca1088) | Oct 30, 2023 |
| Lenovo        | ThinkPad T460 20FN002JUS    | [bf9ff8ba5b](https://linux-hardware.org/?probe=bf9ff8ba5b) | Oct 29, 2023 |
| HP            | Presario CQ57               | [f35a975672](https://linux-hardware.org/?probe=f35a975672) | Oct 29, 2023 |
| HUAWEI        | BOM-WXX9                    | [57c7ce8322](https://linux-hardware.org/?probe=57c7ce8322) | Oct 28, 2023 |
| Dell          | Latitude E6440              | [8d106c22bf](https://linux-hardware.org/?probe=8d106c22bf) | Oct 28, 2023 |
| Dell          | Latitude 3590               | [2d288fa42e](https://linux-hardware.org/?probe=2d288fa42e) | Oct 27, 2023 |
| LG Electro... | R310-K.AP31B                | [ac3922c573](https://linux-hardware.org/?probe=ac3922c573) | Oct 24, 2023 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | [26691d6dfc](https://linux-hardware.org/?probe=26691d6dfc) | Oct 23, 2023 |
| Lenovo        | ThinkPad T420 4180DT9       | [8f8c03ab3b](https://linux-hardware.org/?probe=8f8c03ab3b) | Oct 22, 2023 |
| Apple         | MacBookPro9,2               | [dac0aa7f70](https://linux-hardware.org/?probe=dac0aa7f70) | Oct 22, 2023 |
| Lenovo        | ThinkPad T430s 23539MU      | [4f6872735a](https://linux-hardware.org/?probe=4f6872735a) | Oct 21, 2023 |
| Google        | Pirika                      | [98eea3bc0f](https://linux-hardware.org/?probe=98eea3bc0f) | Oct 20, 2023 |
| Fujitsu       | LIFEBOOK A3510              | [a3bc73fa83](https://linux-hardware.org/?probe=a3bc73fa83) | Oct 19, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d561271316](https://linux-hardware.org/?probe=d561271316) | Oct 19, 2023 |
| HP            | Pavilion dv6                | [0846a94456](https://linux-hardware.org/?probe=0846a94456) | Oct 17, 2023 |
| MSI           | GE72 6QF                    | [94f1c85d10](https://linux-hardware.org/?probe=94f1c85d10) | Oct 13, 2023 |
| Dell          | Vostro 2520                 | [aa4d9c935e](https://linux-hardware.org/?probe=aa4d9c935e) | Oct 12, 2023 |
| Compal        | PCW20                       | [94330b69a9](https://linux-hardware.org/?probe=94330b69a9) | Oct 11, 2023 |
| Dell          | Inspiron 3421               | [1da5f9aefa](https://linux-hardware.org/?probe=1da5f9aefa) | Oct 09, 2023 |
| Dell          | Latitude E6430              | [45d51130b0](https://linux-hardware.org/?probe=45d51130b0) | Oct 08, 2023 |
| Medion        | E15408                      | [5104fa354e](https://linux-hardware.org/?probe=5104fa354e) | Oct 07, 2023 |
| HP            | Laptop 15s-fr2xxx           | [2dc2d438ea](https://linux-hardware.org/?probe=2dc2d438ea) | Oct 07, 2023 |
| Apple         | MacBookAir5,2               | [6c5a7d30f3](https://linux-hardware.org/?probe=6c5a7d30f3) | Oct 06, 2023 |
| ASUSTek       | G551JM                      | [9274bccdad](https://linux-hardware.org/?probe=9274bccdad) | Oct 05, 2023 |
| Apple         | MacBookAir5,2               | [7ad16296eb](https://linux-hardware.org/?probe=7ad16296eb) | Oct 05, 2023 |
| HP            | ElitePad 1000 G2            | [fcfe482832](https://linux-hardware.org/?probe=fcfe482832) | Oct 04, 2023 |
| Lenovo        | ThinkPad P50 20EQS0T52R     | [39983ac5b1](https://linux-hardware.org/?probe=39983ac5b1) | Oct 04, 2023 |
| Dell          | Inspiron 13-5378            | [06c1e095a7](https://linux-hardware.org/?probe=06c1e095a7) | Oct 03, 2023 |
| MSI           | Bravo 15 B5DD               | [1df2dc7261](https://linux-hardware.org/?probe=1df2dc7261) | Oct 01, 2023 |
| Lenovo        | ThinkPad X200 745536T       | [62740874ab](https://linux-hardware.org/?probe=62740874ab) | Sep 30, 2023 |
| Juana Mans... | SF20GM7                     | [b4a58da74c](https://linux-hardware.org/?probe=b4a58da74c) | Sep 30, 2023 |
| Lenovo        | ThinkPad X200 745536T       | [618cd9dd90](https://linux-hardware.org/?probe=618cd9dd90) | Sep 29, 2023 |
| ASUSTek       | X505BA                      | [1caa3c5c7e](https://linux-hardware.org/?probe=1caa3c5c7e) | Sep 28, 2023 |
| Lenovo        | G570 20079                  | [cf0c9cc177](https://linux-hardware.org/?probe=cf0c9cc177) | Sep 28, 2023 |
| Apple         | MacBookAir7,2               | [0c9b2c687a](https://linux-hardware.org/?probe=0c9b2c687a) | Sep 28, 2023 |
| ASUSTek       | X555LN                      | [773691291a](https://linux-hardware.org/?probe=773691291a) | Sep 28, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [243f89703d](https://linux-hardware.org/?probe=243f89703d) | Sep 26, 2023 |
| HP            | Laptop 15s-eq1xxx           | [8142da7d40](https://linux-hardware.org/?probe=8142da7d40) | Sep 25, 2023 |
| ASUSTek       | G750JX                      | [dc6cea804c](https://linux-hardware.org/?probe=dc6cea804c) | Sep 24, 2023 |
| ASUSTek       | X541UAK                     | [b063bf9f1e](https://linux-hardware.org/?probe=b063bf9f1e) | Sep 24, 2023 |
| ASUSTek       | X542UN                      | [76f91b9954](https://linux-hardware.org/?probe=76f91b9954) | Sep 24, 2023 |
| Lenovo        | ThinkPad T440 20B6006DUS    | [4428a91f65](https://linux-hardware.org/?probe=4428a91f65) | Sep 23, 2023 |
| Acer          | Nitro AN515-58              | [fc49b16c1c](https://linux-hardware.org/?probe=fc49b16c1c) | Sep 22, 2023 |
| Apple         | MacBookPro9,1               | [27f3ee04f8](https://linux-hardware.org/?probe=27f3ee04f8) | Sep 21, 2023 |
| ASUSTek       | GL503VMF                    | [0e43a1da82](https://linux-hardware.org/?probe=0e43a1da82) | Sep 21, 2023 |
| Apple         | MacBookPro8,1               | [c1ca0a1d1c](https://linux-hardware.org/?probe=c1ca0a1d1c) | Sep 19, 2023 |
| Lenovo        | IdeaPad N585 20179          | [e80d14f9e4](https://linux-hardware.org/?probe=e80d14f9e4) | Sep 18, 2023 |
| Lenovo        | Z51-70 80K6                 | [8368825071](https://linux-hardware.org/?probe=8368825071) | Sep 17, 2023 |
| Acer          | Aspire 5742                 | [603e2a55fb](https://linux-hardware.org/?probe=603e2a55fb) | Sep 15, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [04bf6410bd](https://linux-hardware.org/?probe=04bf6410bd) | Sep 14, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [0c62999a52](https://linux-hardware.org/?probe=0c62999a52) | Sep 14, 2023 |
| Dell          | Inspiron 3583               | [cad3ce176d](https://linux-hardware.org/?probe=cad3ce176d) | Sep 14, 2023 |
| ASUSTek       | UX305FA                     | [e4ade39a1c](https://linux-hardware.org/?probe=e4ade39a1c) | Sep 14, 2023 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | [e793b9e3d9](https://linux-hardware.org/?probe=e793b9e3d9) | Sep 12, 2023 |
| MSI           | GE62 7RD                    | [ff590de77d](https://linux-hardware.org/?probe=ff590de77d) | Sep 11, 2023 |
| ASUSTek       | X510UAR                     | [671415f9ca](https://linux-hardware.org/?probe=671415f9ca) | Sep 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [1ff3e228da](https://linux-hardware.org/?probe=1ff3e228da) | Sep 10, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [75ca1d0c52](https://linux-hardware.org/?probe=75ca1d0c52) | Sep 10, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [f01636c129](https://linux-hardware.org/?probe=f01636c129) | Sep 09, 2023 |
| Apple         | MacBookPro11,2              | [83b997b3ab](https://linux-hardware.org/?probe=83b997b3ab) | Sep 09, 2023 |
| Lenovo        | V330-15IKB 81AX             | [edb578f198](https://linux-hardware.org/?probe=edb578f198) | Sep 09, 2023 |
| Google        | Pirika                      | [fc27e22f1c](https://linux-hardware.org/?probe=fc27e22f1c) | Sep 08, 2023 |
| Dell          | Inspiron 7460               | [03726302da](https://linux-hardware.org/?probe=03726302da) | Sep 07, 2023 |
| HP            | ProBook 455 15.6 inch G9... | [5b7ab92e89](https://linux-hardware.org/?probe=5b7ab92e89) | Sep 06, 2023 |
| Acer          | Aspire 5742                 | [ff917b0920](https://linux-hardware.org/?probe=ff917b0920) | Sep 02, 2023 |
| HUAWEI        | HN-WX9X                     | [efd67d7c17](https://linux-hardware.org/?probe=efd67d7c17) | Sep 02, 2023 |
| Dell          | Latitude 5420               | [2acb1da32c](https://linux-hardware.org/?probe=2acb1da32c) | Sep 02, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [9de67aa419](https://linux-hardware.org/?probe=9de67aa419) | Sep 01, 2023 |
| Dell          | G15 5530                    | [ababfa6c5e](https://linux-hardware.org/?probe=ababfa6c5e) | Aug 31, 2023 |
| HP            | 255 G8 Notebook PC          | [92552fa038](https://linux-hardware.org/?probe=92552fa038) | Aug 30, 2023 |
| Acer          | Aspire A315-58              | [75ef08524c](https://linux-hardware.org/?probe=75ef08524c) | Aug 30, 2023 |
| Dell          | Latitude E6520              | [4918e66ad8](https://linux-hardware.org/?probe=4918e66ad8) | Aug 29, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [fc7834595f](https://linux-hardware.org/?probe=fc7834595f) | Aug 29, 2023 |
| Acer          | Aspire V5-471               | [c5d2dabe27](https://linux-hardware.org/?probe=c5d2dabe27) | Aug 28, 2023 |
| Timi          | Redmi Book Pro 14 2022      | [8f85c500ec](https://linux-hardware.org/?probe=8f85c500ec) | Aug 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [211472aacc](https://linux-hardware.org/?probe=211472aacc) | Aug 26, 2023 |
| HP            | Laptop 14-dq2xxx            | [0c46e2d419](https://linux-hardware.org/?probe=0c46e2d419) | Aug 26, 2023 |
| HP            | Laptop 15-da2xxx            | [01636af413](https://linux-hardware.org/?probe=01636af413) | Aug 25, 2023 |
| Google        | Pirika                      | [f0937aba65](https://linux-hardware.org/?probe=f0937aba65) | Aug 23, 2023 |
| Lenovo        | ThinkPad P50 20EQS4XN00     | [a517cc57b8](https://linux-hardware.org/?probe=a517cc57b8) | Aug 23, 2023 |
| VIT           | P2402                       | [fa87ae71d4](https://linux-hardware.org/?probe=fa87ae71d4) | Aug 22, 2023 |
| VIT           | P2402                       | [7b83628f3c](https://linux-hardware.org/?probe=7b83628f3c) | Aug 22, 2023 |
| ASUSTek       | X510UAR                     | [cdef569014](https://linux-hardware.org/?probe=cdef569014) | Aug 22, 2023 |
| HP            | Laptop 15-dy1xxx            | [e00521ec88](https://linux-hardware.org/?probe=e00521ec88) | Aug 22, 2023 |
| HUAWEI        | HVY-WXX9                    | [d63bd363bc](https://linux-hardware.org/?probe=d63bd363bc) | Aug 22, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [882234a7b8](https://linux-hardware.org/?probe=882234a7b8) | Aug 22, 2023 |
| Dell          | Inspiron 5558               | [ee47d4b6a7](https://linux-hardware.org/?probe=ee47d4b6a7) | Aug 20, 2023 |
| HONOR         | BBR-WAX9                    | [1d013fbf4b](https://linux-hardware.org/?probe=1d013fbf4b) | Aug 20, 2023 |
| Lenovo        | Rev B 82KU                  | [114345f952](https://linux-hardware.org/?probe=114345f952) | Aug 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [faaba537ca](https://linux-hardware.org/?probe=faaba537ca) | Aug 18, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [d7ec063f46](https://linux-hardware.org/?probe=d7ec063f46) | Aug 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [c078e667a4](https://linux-hardware.org/?probe=c078e667a4) | Aug 15, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [1c643cc90f](https://linux-hardware.org/?probe=1c643cc90f) | Aug 13, 2023 |
| Fujitsu       | LIFEBOOK A3510              | [3e830ffabc](https://linux-hardware.org/?probe=3e830ffabc) | Aug 12, 2023 |
| Dell          | G3 3590                     | [084d659110](https://linux-hardware.org/?probe=084d659110) | Aug 11, 2023 |
| LNV           | L40-70                      | [66fe107447](https://linux-hardware.org/?probe=66fe107447) | Aug 11, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [eee160a070](https://linux-hardware.org/?probe=eee160a070) | Aug 10, 2023 |
| HP            | Laptop 15s-eq3xxx           | [284cfb0f6d](https://linux-hardware.org/?probe=284cfb0f6d) | Aug 08, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [c9c978701a](https://linux-hardware.org/?probe=c9c978701a) | Aug 08, 2023 |
| WEIGO         | CDA-141AU                   | [35c705bd70](https://linux-hardware.org/?probe=35c705bd70) | Aug 05, 2023 |
| Dell          | Inspiron 3558               | [5331913f13](https://linux-hardware.org/?probe=5331913f13) | Aug 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [8b84e48f4c](https://linux-hardware.org/?probe=8b84e48f4c) | Aug 04, 2023 |
| HP            | Laptop 15-dy1xxx            | [6dbeaa5f27](https://linux-hardware.org/?probe=6dbeaa5f27) | Aug 04, 2023 |
| Acer          | Aspire V3-371               | [5d5a4b489b](https://linux-hardware.org/?probe=5d5a4b489b) | Aug 03, 2023 |
| Fujitsu       | LIFEBOOK A3510              | [7281304bf0](https://linux-hardware.org/?probe=7281304bf0) | Aug 02, 2023 |
| Dell          | G3 3590                     | [78aeeb1aa3](https://linux-hardware.org/?probe=78aeeb1aa3) | Aug 02, 2023 |
| Dell          | G3 3590                     | [47d3c9b9fe](https://linux-hardware.org/?probe=47d3c9b9fe) | Aug 02, 2023 |
| Dell          | XPS 15 7590                 | [39216c08ff](https://linux-hardware.org/?probe=39216c08ff) | Aug 01, 2023 |
| Lenovo        | ThinkPad T480 20L6S2CE00    | [eb14620792](https://linux-hardware.org/?probe=eb14620792) | Jul 30, 2023 |
| Apple         | MacBookPro11,1              | [3fb2cba3db](https://linux-hardware.org/?probe=3fb2cba3db) | Jul 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [a467ce5440](https://linux-hardware.org/?probe=a467ce5440) | Jul 28, 2023 |
| Acer          | Aspire A315-42              | [3afa5a3034](https://linux-hardware.org/?probe=3afa5a3034) | Jul 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [dc632de3b5](https://linux-hardware.org/?probe=dc632de3b5) | Jul 27, 2023 |
| HP            | Laptop 14-fq1xxx            | [5de59d7736](https://linux-hardware.org/?probe=5de59d7736) | Jul 27, 2023 |
| Apple         | MacBook7,1                  | [762861205a](https://linux-hardware.org/?probe=762861205a) | Jul 26, 2023 |
| Lenovo        | ThinkPad T470p 20J6003DG... | [5693ac5e4c](https://linux-hardware.org/?probe=5693ac5e4c) | Jul 25, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [032db75736](https://linux-hardware.org/?probe=032db75736) | Jul 23, 2023 |
| Dell          | XPS 15 7590                 | [f5174240a7](https://linux-hardware.org/?probe=f5174240a7) | Jul 23, 2023 |
| Dell          | Inspiron 3476               | [eb12521a96](https://linux-hardware.org/?probe=eb12521a96) | Jul 23, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [c95c0b0730](https://linux-hardware.org/?probe=c95c0b0730) | Jul 22, 2023 |
| Lenovo        | ThinkPad T420 4236C92       | [a7b56f640a](https://linux-hardware.org/?probe=a7b56f640a) | Jul 18, 2023 |
| Lenovo        | ThinkPad T480 20L6S2CE00    | [e88c64ac3c](https://linux-hardware.org/?probe=e88c64ac3c) | Jul 16, 2023 |
| Lenovo        | ThinkPad T450 20BUS1BW01    | [db28c39c19](https://linux-hardware.org/?probe=db28c39c19) | Jul 14, 2023 |
| Lenovo        | ThinkPad T460s 20F90057M... | [698c4a8958](https://linux-hardware.org/?probe=698c4a8958) | Jul 14, 2023 |
| ASUSTek       | GL553VW                     | [9946c63986](https://linux-hardware.org/?probe=9946c63986) | Jul 12, 2023 |
| HP            | Laptop 15-dy2xxx            | [06f4243bee](https://linux-hardware.org/?probe=06f4243bee) | Jul 12, 2023 |
| Lenovo        | ThinkPad T450 20BUS1BW01    | [91d748c376](https://linux-hardware.org/?probe=91d748c376) | Jul 11, 2023 |
| Lenovo        | ThinkPad P72 20MCS0EU00     | [394bdbc596](https://linux-hardware.org/?probe=394bdbc596) | Jul 11, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [a5d9143c99](https://linux-hardware.org/?probe=a5d9143c99) | Jul 10, 2023 |
| Lenovo        | ThinkPad T480 20L6S2CE00    | [bbc78272ea](https://linux-hardware.org/?probe=bbc78272ea) | Jul 10, 2023 |
| Apple         | MacBook5,1                  | [b5ddf3381c](https://linux-hardware.org/?probe=b5ddf3381c) | Jul 10, 2023 |
| Lenovo        | ThinkPad T470p 20J6003DG... | [a7632f8c4b](https://linux-hardware.org/?probe=a7632f8c4b) | Jul 09, 2023 |
| HP            | ENVY Laptop 13-aq0xxx       | [8fcda3580f](https://linux-hardware.org/?probe=8fcda3580f) | Jul 08, 2023 |
| Alienware     | 17                          | [b8b8032da9](https://linux-hardware.org/?probe=b8b8032da9) | Jul 08, 2023 |
| Lenovo        | ThinkPad T460s 20F90057M... | [cd45163d47](https://linux-hardware.org/?probe=cd45163d47) | Jul 08, 2023 |
| Dell          | Latitude 7480               | [4c07c7b04a](https://linux-hardware.org/?probe=4c07c7b04a) | Jul 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [b23ba37244](https://linux-hardware.org/?probe=b23ba37244) | Jul 06, 2023 |
| Apple         | MacBookPro8,1               | [d25474786c](https://linux-hardware.org/?probe=d25474786c) | Jul 05, 2023 |
| Acer          | TravelMate 8572T            | [67f4a2af7e](https://linux-hardware.org/?probe=67f4a2af7e) | Jul 05, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [7fee63007e](https://linux-hardware.org/?probe=7fee63007e) | Jul 02, 2023 |
| Acer          | Aspire 7715Z                | [b288a09d6e](https://linux-hardware.org/?probe=b288a09d6e) | Jul 01, 2023 |
| Lenovo        | ThinkPad T460s 20F90057M... | [a78e2b4096](https://linux-hardware.org/?probe=a78e2b4096) | Jun 29, 2023 |
| Medion        | Akoya P7818                 | [cfe9ae82fa](https://linux-hardware.org/?probe=cfe9ae82fa) | Jun 29, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [b67f86bedc](https://linux-hardware.org/?probe=b67f86bedc) | Jun 21, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [5314aeb7e0](https://linux-hardware.org/?probe=5314aeb7e0) | Jun 21, 2023 |
| Acer          | Aspire E5-573G              | [277ddf45b4](https://linux-hardware.org/?probe=277ddf45b4) | Jun 08, 2023 |
| Acer          | Aspire E1-572               | [6dc6a9d6f5](https://linux-hardware.org/?probe=6dc6a9d6f5) | May 29, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [ba6e80b2b7](https://linux-hardware.org/?probe=ba6e80b2b7) | Apr 02, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [195ab3d907](https://linux-hardware.org/?probe=195ab3d907) | Apr 02, 2023 |
| Lenovo        | ThinkPad T440 20B7A0CYMH    | [428491a9d5](https://linux-hardware.org/?probe=428491a9d5) | Mar 29, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [f8cd7d94b2](https://linux-hardware.org/?probe=f8cd7d94b2) | Mar 23, 2023 |
| Dell          | G5 5500                     | [f9b3b5d852](https://linux-hardware.org/?probe=f9b3b5d852) | Mar 19, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [90ef6ca2b7](https://linux-hardware.org/?probe=90ef6ca2b7) | Mar 18, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [b769745990](https://linux-hardware.org/?probe=b769745990) | Mar 18, 2023 |
| Dell          | Latitude 5420               | [318da7f6c0](https://linux-hardware.org/?probe=318da7f6c0) | Mar 18, 2023 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [d1bf2f0a8b](https://linux-hardware.org/?probe=d1bf2f0a8b) | Mar 12, 2023 |
| Apple         | MacBookPro11,3              | [bccc889328](https://linux-hardware.org/?probe=bccc889328) | Mar 10, 2023 |
| Lenovo        | ThinkPad P51 20HJS11Y00     | [0843074b87](https://linux-hardware.org/?probe=0843074b87) | Mar 09, 2023 |
| Lenovo        | IdeaPad S540-15IML D 81N... | [31e144de96](https://linux-hardware.org/?probe=31e144de96) | Mar 08, 2023 |
| Dell          | Inspiron 3505               | [324020ca8b](https://linux-hardware.org/?probe=324020ca8b) | Feb 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [efd9f878d2](https://linux-hardware.org/?probe=efd9f878d2) | Feb 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [3c2d4cf289](https://linux-hardware.org/?probe=3c2d4cf289) | Feb 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [0de8121880](https://linux-hardware.org/?probe=0de8121880) | Feb 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [f39ab69b74](https://linux-hardware.org/?probe=f39ab69b74) | Feb 01, 2023 |
| HP            | ProBook 6565b               | [0ef00f6bcc](https://linux-hardware.org/?probe=0ef00f6bcc) | Jan 25, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [5661d09dd0](https://linux-hardware.org/?probe=5661d09dd0) | Jan 15, 2023 |
| HP            | 245 G7 Notebook PC          | [3997d98a9a](https://linux-hardware.org/?probe=3997d98a9a) | Jan 11, 2023 |
| HUAWEI        | BOM-WXX9                    | [21fcd391f1](https://linux-hardware.org/?probe=21fcd391f1) | Jan 08, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | [86cf09380a](https://linux-hardware.org/?probe=86cf09380a) | Jan 02, 2023 |
| ASUSTek       | X540LA                      | [65f5548781](https://linux-hardware.org/?probe=65f5548781) | Dec 30, 2022 |
| HUAWEI        | BOM-WXX9                    | [fb1d454bc2](https://linux-hardware.org/?probe=fb1d454bc2) | Dec 29, 2022 |
| HUAWEI        | BOM-WXX9                    | [62010fe267](https://linux-hardware.org/?probe=62010fe267) | Dec 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [6b34107dcf](https://linux-hardware.org/?probe=6b34107dcf) | Dec 21, 2022 |
| HP            | ZBook 15 G4                 | [669d7e74a2](https://linux-hardware.org/?probe=669d7e74a2) | Dec 19, 2022 |
| HP            | ZBook 15 G4                 | [91391127d1](https://linux-hardware.org/?probe=91391127d1) | Dec 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [3111a63a09](https://linux-hardware.org/?probe=3111a63a09) | Dec 16, 2022 |
| Lenovo        | ThinkPad T490s 20NX001KM... | [49f30d3eee](https://linux-hardware.org/?probe=49f30d3eee) | Dec 06, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [16f086de33](https://linux-hardware.org/?probe=16f086de33) | Nov 25, 2022 |
| Medion        | P6816                       | [3aadacefe7](https://linux-hardware.org/?probe=3aadacefe7) | Nov 17, 2022 |
| Dell          | Latitude E6530              | [c87c9abe22](https://linux-hardware.org/?probe=c87c9abe22) | Nov 14, 2022 |
| Toshiba       | TECRA A11                   | [ba91b9d331](https://linux-hardware.org/?probe=ba91b9d331) | Nov 09, 2022 |
| Lenovo        | ThinkPad L450 20DT0000GE    | [1a925e0302](https://linux-hardware.org/?probe=1a925e0302) | Nov 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [4cd7aa6350](https://linux-hardware.org/?probe=4cd7aa6350) | Nov 01, 2022 |
| ASUSTek       | K53SJ                       | [8c85e545f2](https://linux-hardware.org/?probe=8c85e545f2) | Oct 23, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [ef1974cfc8](https://linux-hardware.org/?probe=ef1974cfc8) | Oct 10, 2022 |
| HP            | Laptop 15s-fq2xxx           | [69e60dfe44](https://linux-hardware.org/?probe=69e60dfe44) | Oct 07, 2022 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [a7764ad0f6](https://linux-hardware.org/?probe=a7764ad0f6) | Oct 03, 2022 |
| MSI           | Katana GF66 11UE            | [36b2cba297](https://linux-hardware.org/?probe=36b2cba297) | Sep 05, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [b28edd3886](https://linux-hardware.org/?probe=b28edd3886) | Aug 26, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [97770c5716](https://linux-hardware.org/?probe=97770c5716) | Aug 26, 2022 |
| Lenovo        | ThinkPad T430s 2356FG9      | [9a10c152af](https://linux-hardware.org/?probe=9a10c152af) | Aug 17, 2022 |
| Aquarius      | NS585                       | [db9cbd5688](https://linux-hardware.org/?probe=db9cbd5688) | Aug 17, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [7c46c8f737](https://linux-hardware.org/?probe=7c46c8f737) | Jul 15, 2022 |
| ASUSTek       | G551JM                      | [599c7b9eae](https://linux-hardware.org/?probe=599c7b9eae) | Jul 14, 2022 |
| ASUSTek       | G551JM                      | [9f4536df1c](https://linux-hardware.org/?probe=9f4536df1c) | Jul 14, 2022 |
| ASUSTek       | UX303LN                     | [9ce42e1b01](https://linux-hardware.org/?probe=9ce42e1b01) | Jun 12, 2022 |
| Dell          | Inspiron 1545               | [ce0e24a314](https://linux-hardware.org/?probe=ce0e24a314) | May 28, 2022 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [53475a6004](https://linux-hardware.org/?probe=53475a6004) | May 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [80d32848bf](https://linux-hardware.org/?probe=80d32848bf) | May 21, 2022 |
| Dell          | Precision M3800             | [7b63874768](https://linux-hardware.org/?probe=7b63874768) | Apr 25, 2022 |
| Dell          | Precision M3800             | [fbabacd835](https://linux-hardware.org/?probe=fbabacd835) | Apr 24, 2022 |
| Lenovo        | ThinkPad X230 2325HR9       | [a9d9d3fbb2](https://linux-hardware.org/?probe=a9d9d3fbb2) | Apr 21, 2022 |
| Acer          | Aspire A515-54G             | [52b660d8fb](https://linux-hardware.org/?probe=52b660d8fb) | Apr 11, 2022 |
| Dell          | Precision M3800             | [1ef57b39a7](https://linux-hardware.org/?probe=1ef57b39a7) | Apr 10, 2022 |
| Dell          | Precision M3800             | [9fc15d1ae6](https://linux-hardware.org/?probe=9fc15d1ae6) | Mar 31, 2022 |
| MSI           | GF63 Thin 9SCX              | [4501fa1556](https://linux-hardware.org/?probe=4501fa1556) | Mar 25, 2022 |
| Dell          | Latitude 7480               | [bf00ec6a76](https://linux-hardware.org/?probe=bf00ec6a76) | Mar 23, 2022 |
| HUAWEI        | WRT-WX9                     | [70ec26bed6](https://linux-hardware.org/?probe=70ec26bed6) | Mar 22, 2022 |
| Dell          | Latitude 7480               | [faddba28a8](https://linux-hardware.org/?probe=faddba28a8) | Mar 19, 2022 |
| Apple         | MacBookAir6,2               | [b71110144d](https://linux-hardware.org/?probe=b71110144d) | Mar 19, 2022 |
| HP            | Laptop 15-da0xxx            | [bb9074ccdf](https://linux-hardware.org/?probe=bb9074ccdf) | Mar 18, 2022 |
| Lenovo        | IdeaPad 3 15IML05 81WR      | [918c951cd1](https://linux-hardware.org/?probe=918c951cd1) | Mar 12, 2022 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [e251c9f079](https://linux-hardware.org/?probe=e251c9f079) | Mar 11, 2022 |
| Dell          | Venue 11 Pro 7130 vPro      | [57b302b119](https://linux-hardware.org/?probe=57b302b119) | Mar 05, 2022 |
| Lenovo        | ThinkPad T460 20FMS1XX00    | [78e82c6674](https://linux-hardware.org/?probe=78e82c6674) | Feb 24, 2022 |
| Dell          | Latitude E6430              | [e1de4e80fe](https://linux-hardware.org/?probe=e1de4e80fe) | Feb 15, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [a3c5f00a2a](https://linux-hardware.org/?probe=a3c5f00a2a) | Feb 10, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [e53fb31614](https://linux-hardware.org/?probe=e53fb31614) | Feb 10, 2022 |
| Lenovo        | Legion Y740-15IRHg 81UH     | [b0cc5e0cbc](https://linux-hardware.org/?probe=b0cc5e0cbc) | Jan 29, 2022 |
| Acer          | Aspire A315-58G             | [cb4f253c1c](https://linux-hardware.org/?probe=cb4f253c1c) | Jan 28, 2022 |
| Dell          | Latitude E6520              | [ee96960cec](https://linux-hardware.org/?probe=ee96960cec) | Jan 25, 2022 |
| HP            | Laptop 15s-eq0xxx           | [0df160c245](https://linux-hardware.org/?probe=0df160c245) | Jan 21, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [3df8a1c560](https://linux-hardware.org/?probe=3df8a1c560) | Jan 08, 2022 |
| Dell          | Vostro 3590                 | [9e77a2584c](https://linux-hardware.org/?probe=9e77a2584c) | Dec 30, 2021 |
| ASUSTek       | ASUS EXPERTBOOK B9400CEA... | [78e3fbdf6a](https://linux-hardware.org/?probe=78e3fbdf6a) | Dec 28, 2021 |
| HP            | Notebook                    | [c14ea64659](https://linux-hardware.org/?probe=c14ea64659) | Dec 23, 2021 |
| ASUSTek       | X510UNR                     | [0733a05806](https://linux-hardware.org/?probe=0733a05806) | Dec 21, 2021 |
| ASUSTek       | ASUS EXPERTBOOK B9400CEA... | [b4425de4a6](https://linux-hardware.org/?probe=b4425de4a6) | Dec 17, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [6f3bd18b3f](https://linux-hardware.org/?probe=6f3bd18b3f) | Dec 06, 2021 |
| Pegatron      | D15K                        | [eaeaad8d39](https://linux-hardware.org/?probe=eaeaad8d39) | Nov 29, 2021 |
| MSI           | GP73 Leopard 8RD            | [5bafb43f78](https://linux-hardware.org/?probe=5bafb43f78) | Nov 21, 2021 |
| Acer          | Aspire A315-58G             | [911895fcf2](https://linux-hardware.org/?probe=911895fcf2) | Nov 19, 2021 |
| Acer          | Aspire A315-58G             | [5748b3cd05](https://linux-hardware.org/?probe=5748b3cd05) | Nov 12, 2021 |
| Lenovo        | ThinkPad W530 24384CU       | [d18d3495e0](https://linux-hardware.org/?probe=d18d3495e0) | Nov 05, 2021 |
| Acer          | Aspire A315-58G             | [905fce5118](https://linux-hardware.org/?probe=905fce5118) | Oct 29, 2021 |
| HP            | ENVY Sleekbook 4            | [ebea056239](https://linux-hardware.org/?probe=ebea056239) | Oct 29, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [2a54689fb3](https://linux-hardware.org/?probe=2a54689fb3) | Oct 24, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [fb95cbb063](https://linux-hardware.org/?probe=fb95cbb063) | Oct 19, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [6cd76dfa2a](https://linux-hardware.org/?probe=6cd76dfa2a) | Oct 13, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [e3a8d1ca32](https://linux-hardware.org/?probe=e3a8d1ca32) | Oct 11, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [c7c4a74bb8](https://linux-hardware.org/?probe=c7c4a74bb8) | Oct 11, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [68865693c7](https://linux-hardware.org/?probe=68865693c7) | Oct 09, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [e804a59920](https://linux-hardware.org/?probe=e804a59920) | Oct 02, 2021 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Xero Rolling | 196       | 96.08%  |
| Xero         | 8         | 3.92%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| Xero | 203       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version          | Notebooks | Percent |
|------------------|-----------|---------|
| 6.4.12-arch1-1   | 31        | 14.22%  |
| 6.5.5-arch1-1    | 23        | 10.55%  |
| 6.4.9-arch1-1    | 15        | 6.88%   |
| 6.4.3-arch1-2    | 13        | 5.96%   |
| 6.5.9-arch2-1    | 9         | 4.13%   |
| 6.4.2-arch1-1    | 6         | 2.75%   |
| 6.4.4-arch1-1    | 4         | 1.83%   |
| 6.4.1-arch2-1    | 4         | 1.83%   |
| 6.0.12-arch1-1   | 4         | 1.83%   |
| 5.16.15-arch1-1  | 4         | 1.83%   |
| 6.5.3-arch1-1    | 3         | 1.38%   |
| 6.2.6-arch1-1    | 3         | 1.38%   |
| 6.1.1-arch1-1    | 3         | 1.38%   |
| 6.4.2-zen1-1-zen | 2         | 0.92%   |
| 6.4.11-arch2-1   | 2         | 0.92%   |
| 6.4.10-arch1-1   | 2         | 0.92%   |
| 6.3.9-arch1-1    | 2         | 0.92%   |
| 6.3.8-arch1-1    | 2         | 0.92%   |
| 6.2.7-arch1-1    | 2         | 0.92%   |
| 6.0.7-arch1-1    | 2         | 0.92%   |
| 5.18.16-arch1-1  | 2         | 0.92%   |
| 5.18.11-arch1-1  | 2         | 0.92%   |
| 5.17.9-arch1-1   | 2         | 0.92%   |
| 5.16.8-arch1-1   | 2         | 0.92%   |
| 5.16.2-arch1-1   | 2         | 0.92%   |
| 5.16.1-arch1-1   | 2         | 0.92%   |
| 5.15.33-1-lts    | 2         | 0.92%   |
| 5.14.14-arch1-1  | 2         | 0.92%   |
| 6.5.8-arch1-1    | 1         | 0.46%   |
| 6.5.4-zen2-1-zen | 1         | 0.46%   |
| 6.5.4-arch2-1    | 1         | 0.46%   |
| 6.5.2-zen1-1-zen | 1         | 0.46%   |
| 6.5.2-arch1-1    | 1         | 0.46%   |
| 6.5.1-arch1-1    | 1         | 0.46%   |
| 6.4.8-arch1-1    | 1         | 0.46%   |
| 6.4.7-zen1-1-zen | 1         | 0.46%   |
| 6.4.7-arch1-3    | 1         | 0.46%   |
| 6.4.7-arch1-1    | 1         | 0.46%   |
| 6.4.6-arch1-1    | 1         | 0.46%   |
| 6.4.11-arch1-1   | 1         | 0.46%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.4.12  | 31        | 14.22%  |
| 6.5.5   | 23        | 10.55%  |
| 6.4.9   | 15        | 6.88%   |
| 6.4.3   | 13        | 5.96%   |
| 6.5.9   | 9         | 4.13%   |
| 6.4.2   | 8         | 3.67%   |
| 6.4.1   | 5         | 2.29%   |
| 6.4.4   | 4         | 1.83%   |
| 6.4.10  | 4         | 1.83%   |
| 6.0.12  | 4         | 1.83%   |
| 5.16.15 | 4         | 1.83%   |
| 6.5.3   | 3         | 1.38%   |
| 6.4.7   | 3         | 1.38%   |
| 6.4.11  | 3         | 1.38%   |
| 6.3.9   | 3         | 1.38%   |
| 6.2.6   | 3         | 1.38%   |
| 6.1.1   | 3         | 1.38%   |
| 5.14.16 | 3         | 1.38%   |
| 5.14.14 | 3         | 1.38%   |
| 6.5.4   | 2         | 0.92%   |
| 6.5.2   | 2         | 0.92%   |
| 6.3.8   | 2         | 0.92%   |
| 6.2.7   | 2         | 0.92%   |
| 6.1.38  | 2         | 0.92%   |
| 6.0.8   | 2         | 0.92%   |
| 6.0.7   | 2         | 0.92%   |
| 5.18.16 | 2         | 0.92%   |
| 5.18.11 | 2         | 0.92%   |
| 5.17.9  | 2         | 0.92%   |
| 5.16.8  | 2         | 0.92%   |
| 5.16.2  | 2         | 0.92%   |
| 5.16.1  | 2         | 0.92%   |
| 5.15.33 | 2         | 0.92%   |
| 5.14.8  | 2         | 0.92%   |
| 6.5.8   | 1         | 0.46%   |
| 6.5.1   | 1         | 0.46%   |
| 6.4.8   | 1         | 0.46%   |
| 6.4.6   | 1         | 0.46%   |
| 6.3.6   | 1         | 0.46%   |
| 6.3.4   | 1         | 0.46%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.4     | 85        | 40.09%  |
| 6.5     | 40        | 18.87%  |
| 5.16    | 14        | 6.6%    |
| 6.1     | 12        | 5.66%   |
| 6.0     | 12        | 5.66%   |
| 5.15    | 9         | 4.25%   |
| 5.14    | 9         | 4.25%   |
| 6.3     | 7         | 3.3%    |
| 6.2     | 7         | 3.3%    |
| 5.19    | 5         | 2.36%   |
| 5.18    | 5         | 2.36%   |
| 5.17    | 4         | 1.89%   |
| 5.10    | 3         | 1.42%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 203       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| KDE5     | 193       | 93.69%  |
| XFCE     | 6         | 2.91%   |
| GNOME    | 3         | 1.46%   |
| Hyprland | 2         | 0.97%   |
| LeftWM   | 1         | 0.49%   |
| KDE      | 1         | 0.49%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 172       | 83.9%   |
| Wayland | 31        | 15.12%  |
| Tty     | 1         | 0.49%   |
| Unknown | 1         | 0.49%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 172       | 82.69%  |
| Unknown | 18        | 8.65%   |
| LightDM | 17        | 8.17%   |
| GDM     | 1         | 0.48%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 92        | 45.1%   |
| de_DE | 14        | 6.86%   |
| en_IN | 13        | 6.37%   |
| es_MX | 12        | 5.88%   |
| pl_PL | 9         | 4.41%   |
| ru_RU | 6         | 2.94%   |
| pt_BR | 6         | 2.94%   |
| fr_FR | 6         | 2.94%   |
| en_GB | 5         | 2.45%   |
| en_CA | 4         | 1.96%   |
| en_AU | 4         | 1.96%   |
| C     | 4         | 1.96%   |
| it_IT | 3         | 1.47%   |
| hu_HU | 3         | 1.47%   |
| es_AR | 3         | 1.47%   |
| vi_VN | 2         | 0.98%   |
| nb_NO | 2         | 0.98%   |
| es_ES | 2         | 0.98%   |
| zh_CN | 1         | 0.49%   |
| tr_TR | 1         | 0.49%   |
| nl_NL | 1         | 0.49%   |
| ko_KR | 1         | 0.49%   |
| es_VE | 1         | 0.49%   |
| es_SV | 1         | 0.49%   |
| es_CL | 1         | 0.49%   |
| en_ZA | 1         | 0.49%   |
| en_PH | 1         | 0.49%   |
| en_DK | 1         | 0.49%   |
| en_AG | 1         | 0.49%   |
| da_DK | 1         | 0.49%   |
| ca_ES | 1         | 0.49%   |
| ar_EG | 1         | 0.49%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 153       | 74.63%  |
| BIOS | 52        | 25.37%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 85        | 41.06%  |
| Btrfs   | 61        | 29.47%  |
| Xfs     | 57        | 27.54%  |
| Overlay | 4         | 1.93%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 160       | 78.05%  |
| MBR     | 27        | 13.17%  |
| Unknown | 18        | 8.78%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 170       | 81.73%  |
| Yes       | 38        | 18.27%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 134       | 65.05%  |
| Yes       | 72        | 34.95%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 57        | 28.08%  |
| ASUSTek Computer | 33        | 16.26%  |
| Dell             | 30        | 14.78%  |
| Hewlett-Packard  | 26        | 12.81%  |
| Acer             | 13        | 6.4%    |
| Apple            | 12        | 5.91%   |
| MSI              | 8         | 3.94%   |
| HUAWEI           | 5         | 2.46%   |
| Medion           | 3         | 1.48%   |
| Toshiba          | 2         | 0.99%   |
| Timi             | 2         | 0.99%   |
| WEIGO            | 1         | 0.49%   |
| VIT              | 1         | 0.49%   |
| Pegatron         | 1         | 0.49%   |
| LNV              | 1         | 0.49%   |
| LG Electronics   | 1         | 0.49%   |
| Juana Manso      | 1         | 0.49%   |
| HONOR            | 1         | 0.49%   |
| Google           | 1         | 0.49%   |
| Fujitsu          | 1         | 0.49%   |
| Compal           | 1         | 0.49%   |
| Aquarius         | 1         | 0.49%   |
| Alienware        | 1         | 0.49%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Dell Precision M3800                       | 3         | 1.48%   |
| MSI Bravo 15 B5DD                          | 2         | 0.99%   |
| Lenovo IdeaPad Gaming 3 15IHU6 82K1        | 2         | 0.99%   |
| HUAWEI BOM-WXX9                            | 2         | 0.99%   |
| Dell Latitude E6520                        | 2         | 0.99%   |
| Dell Latitude E6430                        | 2         | 0.99%   |
| Dell Latitude 7480                         | 2         | 0.99%   |
| Dell Latitude 5420                         | 2         | 0.99%   |
| Apple MacBookPro8,1                        | 2         | 0.99%   |
| WEIGO CDA-141AU                            | 1         | 0.49%   |
| VIT P2402                                  | 1         | 0.49%   |
| Toshiba TECRA A11                          | 1         | 0.49%   |
| Toshiba Satellite C55-C                    | 1         | 0.49%   |
| Timi Redmi Book Pro 15 2022                | 1         | 0.49%   |
| Timi Redmi Book Pro 14 2022                | 1         | 0.49%   |
| Pegatron D15K                              | 1         | 0.49%   |
| MSI Thin GF63 12VE                         | 1         | 0.49%   |
| MSI Katana GF66 11UE                       | 1         | 0.49%   |
| MSI GP73 Leopard 8RD                       | 1         | 0.49%   |
| MSI GF63 Thin 9SCX                         | 1         | 0.49%   |
| MSI GE72 6QF                               | 1         | 0.49%   |
| MSI GE62 7RD                               | 1         | 0.49%   |
| Medion P6816                               | 1         | 0.49%   |
| Medion E15408                              | 1         | 0.49%   |
| Medion Akoya P7818                         | 1         | 0.49%   |
| LNV L40-70                                 | 1         | 0.49%   |
| LG R310-K.AP31B                            | 1         | 0.49%   |
| Lenovo Z51-70 80K6                         | 1         | 0.49%   |
| Lenovo Yoga 3 Pro-1370 80HE                | 1         | 0.49%   |
| Lenovo Y520-15IKBN 80WK                    | 1         | 0.49%   |
| Lenovo XiaoXinPro 14 IRH8 83AL             | 1         | 0.49%   |
| Lenovo V330-15IKB 81AX                     | 1         | 0.49%   |
| Lenovo ThinkPad X230 2325HR9               | 1         | 0.49%   |
| Lenovo ThinkPad X200 745536T               | 1         | 0.49%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XW0055MH | 1         | 0.49%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BTS0WK00   | 1         | 0.49%   |
| Lenovo ThinkPad W530 24384CU               | 1         | 0.49%   |
| Lenovo ThinkPad T490s 20NX001KMX           | 1         | 0.49%   |
| Lenovo ThinkPad T480s 20L7CTO1WW           | 1         | 0.49%   |
| Lenovo ThinkPad T480 20L6S2CE00            | 1         | 0.49%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 26        | 12.81%  |
| Lenovo IdeaPad     | 18        | 8.87%   |
| HP Laptop          | 11        | 5.42%   |
| Dell Latitude      | 11        | 5.42%   |
| Acer Aspire        | 10        | 4.93%   |
| Dell Inspiron      | 9         | 4.43%   |
| ASUS VivoBook      | 9         | 4.43%   |
| Lenovo Legion      | 6         | 2.96%   |
| ASUS ASUS          | 5         | 2.46%   |
| Dell Precision     | 3         | 1.48%   |
| ASUS ROG           | 3         | 1.48%   |
| Apple MacBookPro11 | 3         | 1.48%   |
| Timi Redmi         | 2         | 0.99%   |
| MSI Bravo          | 2         | 0.99%   |
| HUAWEI BOM-WXX9    | 2         | 0.99%   |
| HP ProBook         | 2         | 0.99%   |
| HP Pavilion        | 2         | 0.99%   |
| HP ENVY            | 2         | 0.99%   |
| Dell Vostro        | 2         | 0.99%   |
| Apple MacBookPro9  | 2         | 0.99%   |
| Apple MacBookPro8  | 2         | 0.99%   |
| Acer Nitro         | 2         | 0.99%   |
| WEIGO CDA-141AU    | 1         | 0.49%   |
| VIT P2402          | 1         | 0.49%   |
| Toshiba TECRA      | 1         | 0.49%   |
| Toshiba Satellite  | 1         | 0.49%   |
| Pegatron D15K      | 1         | 0.49%   |
| MSI Thin           | 1         | 0.49%   |
| MSI Katana         | 1         | 0.49%   |
| MSI GP73           | 1         | 0.49%   |
| MSI GF63           | 1         | 0.49%   |
| MSI GE72           | 1         | 0.49%   |
| MSI GE62           | 1         | 0.49%   |
| Medion P6816       | 1         | 0.49%   |
| Medion E15408      | 1         | 0.49%   |
| Medion Akoya       | 1         | 0.49%   |
| LNV L40-70         | 1         | 0.49%   |
| LG R310-K.AP31B    | 1         | 0.49%   |
| Lenovo Z51-70      | 1         | 0.49%   |
| Lenovo Yoga        | 1         | 0.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 28        | 13.79%  |
| 2019 | 28        | 13.79%  |
| 2020 | 26        | 12.81%  |
| 2012 | 17        | 8.37%   |
| 2017 | 14        | 6.9%    |
| 2015 | 13        | 6.4%    |
| 2013 | 13        | 6.4%    |
| 2018 | 11        | 5.42%   |
| 2011 | 11        | 5.42%   |
| 2022 | 10        | 4.93%   |
| 2014 | 10        | 4.93%   |
| 2016 | 8         | 3.94%   |
| 2023 | 4         | 1.97%   |
| 2010 | 4         | 1.97%   |
| 2008 | 4         | 1.97%   |
| 2009 | 2         | 0.99%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 203       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 202       | 99.51%  |
| Enabled  | 1         | 0.49%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 202       | 99.51%  |
| Yes  | 1         | 0.49%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 75        | 36.76%  |
| 16.01-24.0  | 44        | 21.57%  |
| 8.01-16.0   | 37        | 18.14%  |
| 3.01-4.0    | 32        | 15.69%  |
| 32.01-64.0  | 8         | 3.92%   |
| 24.01-32.0  | 6         | 2.94%   |
| 64.01-256.0 | 2         | 0.98%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 73        | 34.76%  |
| 1.01-2.0   | 71        | 33.81%  |
| 4.01-8.0   | 29        | 13.81%  |
| 3.01-4.0   | 29        | 13.81%  |
| 8.01-16.0  | 5         | 2.38%   |
| 0.51-1.0   | 2         | 0.95%   |
| 16.01-24.0 | 1         | 0.48%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 137       | 66.5%   |
| 2      | 58        | 28.16%  |
| 3      | 10        | 4.85%   |
| 4      | 1         | 0.49%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 155       | 76.35%  |
| Yes       | 48        | 23.65%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 150       | 73.89%  |
| No        | 53        | 26.11%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 198       | 97.54%  |
| No        | 5         | 2.46%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 180       | 88.24%  |
| No        | 24        | 11.76%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 29        | 14.22%  |
| Germany      | 21        | 10.29%  |
| India        | 18        | 8.82%   |
| Poland       | 10        | 4.9%    |
| Russia       | 8         | 3.92%   |
| France       | 8         | 3.92%   |
| Vietnam      | 6         | 2.94%   |
| Turkey       | 6         | 2.94%   |
| Canada       | 6         | 2.94%   |
| Mexico       | 5         | 2.45%   |
| Italy        | 5         | 2.45%   |
| Brazil       | 5         | 2.45%   |
| Argentina    | 5         | 2.45%   |
| Norway       | 4         | 1.96%   |
| Hungary      | 4         | 1.96%   |
| Chile        | 4         | 1.96%   |
| Australia    | 4         | 1.96%   |
| Thailand     | 3         | 1.47%   |
| Spain        | 3         | 1.47%   |
| Netherlands  | 3         | 1.47%   |
| Morocco      | 3         | 1.47%   |
| Malaysia     | 3         | 1.47%   |
| Romania      | 2         | 0.98%   |
| Pakistan     | 2         | 0.98%   |
| Indonesia    | 2         | 0.98%   |
| Greece       | 2         | 0.98%   |
| Egypt        | 2         | 0.98%   |
| Denmark      | 2         | 0.98%   |
| China        | 2         | 0.98%   |
| Zambia       | 1         | 0.49%   |
| Venezuela    | 1         | 0.49%   |
| UK           | 1         | 0.49%   |
| Tunisia      | 1         | 0.49%   |
| Togo         | 1         | 0.49%   |
| Switzerland  | 1         | 0.49%   |
| Sweden       | 1         | 0.49%   |
| South Korea  | 1         | 0.49%   |
| South Africa | 1         | 0.49%   |
| Portugal     | 1         | 0.49%   |
| Philippines  | 1         | 0.49%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Istanbul         | 4         | 1.94%   |
| Longmont         | 3         | 1.46%   |
| Hanoi            | 3         | 1.46%   |
| Gdansk           | 3         | 1.46%   |
| Chennai          | 3         | 1.46%   |
| Warsaw           | 2         | 0.97%   |
| Ufa              | 2         | 0.97%   |
| Tangerang        | 2         | 0.97%   |
| Stuttgart        | 2         | 0.97%   |
| Seattle          | 2         | 0.97%   |
| Pune             | 2         | 0.97%   |
| Norfolk          | 2         | 0.97%   |
| Madurai          | 2         | 0.97%   |
| Kuala Lumpur     | 2         | 0.97%   |
| Ho Chi Minh City | 2         | 0.97%   |
| Hamburg          | 2         | 0.97%   |
| Cairo            | 2         | 0.97%   |
| Zurich           | 1         | 0.49%   |
| Zenica           | 1         | 0.49%   |
| Zeeland          | 1         | 0.49%   |
| Zalaegerszeg     | 1         | 0.49%   |
| Zabrze           | 1         | 0.49%   |
| Wolfsburg        | 1         | 0.49%   |
| Wasilla          | 1         | 0.49%   |
| Viburnum         | 1         | 0.49%   |
| Vejle            | 1         | 0.49%   |
| Vechelde         | 1         | 0.49%   |
| Vallenar         | 1         | 0.49%   |
| Valladolid       | 1         | 0.49%   |
| Ulan Bator       | 1         | 0.49%   |
| Ubatuba          | 1         | 0.49%   |
| Trondheim        | 1         | 0.49%   |
| Toronto          | 1         | 0.49%   |
| Toluca           | 1         | 0.49%   |
| Tirana           | 1         | 0.49%   |
| Tigre            | 1         | 0.49%   |
| Thornhill        | 1         | 0.49%   |
| Tavarede         | 1         | 0.49%   |
| Taranto          | 1         | 0.49%   |
| Tampere          | 1         | 0.49%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 51        | 57     | 18.96%  |
| Seagate                      | 27        | 31     | 10.04%  |
| WDC                          | 20        | 23     | 7.43%   |
| Toshiba                      | 17        | 18     | 6.32%   |
| Kingston                     | 17        | 21     | 6.32%   |
| SanDisk                      | 15        | 16     | 5.58%   |
| Intel                        | 12        | 16     | 4.46%   |
| SK hynix                     | 9         | 9      | 3.35%   |
| Micron Technology            | 9         | 10     | 3.35%   |
| Unknown                      | 8         | 12     | 2.97%   |
| KIOXIA                       | 6         | 7      | 2.23%   |
| HGST                         | 6         | 7      | 2.23%   |
| Crucial                      | 6         | 6      | 2.23%   |
| Apple                        | 5         | 5      | 1.86%   |
| Transcend                    | 3         | 3      | 1.12%   |
| OWC                          | 3         | 3      | 1.12%   |
| LITEONIT                     | 3         | 3      | 1.12%   |
| Hitachi                      | 3         | 3      | 1.12%   |
| Apacer                       | 3         | 3      | 1.12%   |
| A-DATA Technology            | 3         | 3      | 1.12%   |
| Shenzhen Longsys Electronics | 2         | 2      | 0.74%   |
| SAGE                         | 2         | 2      | 0.74%   |
| Phison Electronics           | 2         | 2      | 0.74%   |
| Phison                       | 2         | 2      | 0.74%   |
| Kingston Technology Company  | 2         | 2      | 0.74%   |
| JMicron Technology           | 2         | 2      | 0.74%   |
| China                        | 2         | 2      | 0.74%   |
| Vaseky                       | 1         | 1      | 0.37%   |
| Union Memory (Shenzhen)      | 1         | 1      | 0.37%   |
| TO Exter                     | 1         | 1      | 0.37%   |
| tecmiyo                      | 1         | 1      | 0.37%   |
| TARGET                       | 1         | 1      | 0.37%   |
| SandWind                     | 1         | 1      | 0.37%   |
| S3+                          | 1         | 1      | 0.37%   |
| Realtek Semiconductor        | 1         | 1      | 0.37%   |
| PNY                          | 1         | 1      | 0.37%   |
| Plextor                      | 1         | 1      | 0.37%   |
| OSCOO                        | 1         | 1      | 0.37%   |
| NT-1TB                       | 1         | 1      | 0.37%   |
| Micron/Crucial Technology    | 1         | 1      | 0.37%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Toshiba MQ04ABF100 1TB                              | 6         | 2.16%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB   | 6         | 2.16%   |
| Seagate ST1000LM035-1RK172 1TB                      | 5         | 1.8%    |
| Kingston SA400S37480G 480GB SSD                     | 5         | 1.8%    |
| Unknown MMC Card  64GB                              | 4         | 1.44%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 4         | 1.44%   |
| WDC WD10SPZX-24Z10 1TB                              | 3         | 1.08%   |
| Seagate ST1000LM049-2GH172 1TB                      | 3         | 1.08%   |
| Seagate One Touch HDD 5TB                           | 3         | 1.08%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 121GB | 3         | 1.08%   |
| Micron 2210_MTFDHBA512QFD 512GB                     | 3         | 1.08%   |
| Kingston SA400S37240G 240GB SSD                     | 3         | 1.08%   |
| HGST HTS721010A9E630 1TB                            | 3         | 1.08%   |
| Unknown MMC Card  128GB                             | 2         | 0.72%   |
| Toshiba XG6 NVMe SSD Controller 256GB               | 2         | 0.72%   |
| Toshiba MK2555GSX 250GB                             | 2         | 0.72%   |
| Seagate ST750LM022 HN-M750MBB 752GB                 | 2         | 0.72%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 2         | 0.72%   |
| Seagate Expansion 1TB                               | 2         | 0.72%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB   | 2         | 0.72%   |
| Samsung SSD 980 1TB                                 | 2         | 0.72%   |
| Samsung SSD 860 EVO 250GB                           | 2         | 0.72%   |
| Samsung MZVLQ512HBLU-00BH1 512GB                    | 2         | 0.72%   |
| Samsung MZALQ256HBJD-00BL2 256GB                    | 2         | 0.72%   |
| Samsung MZALQ256HAJD-000L2 256GB                    | 2         | 0.72%   |
| SAGE 3639S 160GB                                    | 2         | 0.72%   |
| Phison E12 NVMe Controller 1TB                      | 2         | 0.72%   |
| OWC Mercury Electra 3G SSD                          | 2         | 0.72%   |
| Micron 2200V_MTFDHBA512TCK 512GB                    | 2         | 0.72%   |
| KIOXIA KBG40ZNV256G 256GB                           | 2         | 0.72%   |
| Kingston SA400S37960G 960GB SSD                     | 2         | 0.72%   |
| Kingston OM8PCP3512F-AI1 512GB                      | 2         | 0.72%   |
| JMicron Generic 256GB                               | 2         | 0.72%   |
| Intel SSD 660P Series 1024GB                        | 2         | 0.72%   |
| Intel HBRPEKNX0101AHO 16GB                          | 2         | 0.72%   |
| Intel HBRPEKNX0101AH 256GB                          | 2         | 0.72%   |
| Crucial CT500MX500SSD1 500GB                        | 2         | 0.72%   |
| Apacer AS350 256GB SSD                              | 2         | 0.72%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 1         | 0.36%   |
| WDC WDS250G2B0A-00SM50 250GB SSD                    | 1         | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 26        | 29     | 42.62%  |
| WDC                 | 11        | 12     | 18.03%  |
| Toshiba             | 11        | 11     | 18.03%  |
| HGST                | 6         | 7      | 9.84%   |
| Hitachi             | 3         | 3      | 4.92%   |
| SAGE                | 2         | 2      | 3.28%   |
| Unknown             | 1         | 1      | 1.64%   |
| Samsung Electronics | 1         | 1      | 1.64%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 19        | 21     | 20.21%  |
| Kingston            | 10        | 12     | 10.64%  |
| SanDisk             | 7         | 7      | 7.45%   |
| Crucial             | 6         | 6      | 6.38%   |
| Apple               | 5         | 5      | 5.32%   |
| WDC                 | 4         | 5      | 4.26%   |
| Transcend           | 3         | 3      | 3.19%   |
| OWC                 | 3         | 3      | 3.19%   |
| LITEONIT            | 3         | 3      | 3.19%   |
| Apacer              | 3         | 3      | 3.19%   |
| Micron Technology   | 2         | 2      | 2.13%   |
| Intel               | 2         | 2      | 2.13%   |
| China               | 2         | 2      | 2.13%   |
| A-DATA Technology   | 2         | 2      | 2.13%   |
| Vaseky              | 1         | 1      | 1.06%   |
| Toshiba             | 1         | 1      | 1.06%   |
| TO Exter            | 1         | 1      | 1.06%   |
| tecmiyo             | 1         | 1      | 1.06%   |
| TARGET              | 1         | 1      | 1.06%   |
| SK hynix            | 1         | 1      | 1.06%   |
| S3+                 | 1         | 1      | 1.06%   |
| PNY                 | 1         | 1      | 1.06%   |
| Plextor             | 1         | 1      | 1.06%   |
| Phison              | 1         | 1      | 1.06%   |
| OSCOO               | 1         | 1      | 1.06%   |
| NT-1TB              | 1         | 1      | 1.06%   |
| LITEON              | 1         | 1      | 1.06%   |
| Kingmax             | 1         | 1      | 1.06%   |
| KingFast            | 1         | 1      | 1.06%   |
| Intenso             | 1         | 1      | 1.06%   |
| Imation             | 1         | 1      | 1.06%   |
| Hewlett-Packard     | 1         | 1      | 1.06%   |
| GOODRAM             | 1         | 1      | 1.06%   |
| GLOWAY              | 1         | 1      | 1.06%   |
| Emtec               | 1         | 1      | 1.06%   |
| Biostar             | 1         | 1      | 1.06%   |
| Azerty              | 1         | 1      | 1.06%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 97        | 119    | 39.11%  |
| SSD     | 82        | 99     | 33.06%  |
| HDD     | 58        | 66     | 23.39%  |
| MMC     | 8         | 12     | 3.23%   |
| Unknown | 3         | 3      | 1.21%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 122       | 154    | 50.62%  |
| NVMe | 95        | 115    | 39.42%  |
| SAS  | 16        | 18     | 6.64%   |
| MMC  | 8         | 12     | 3.32%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 85        | 100    | 59.03%  |
| 0.51-1.0   | 54        | 60     | 37.5%   |
| 4.01-10.0  | 3         | 3      | 2.08%   |
| 1.01-2.0   | 2         | 2      | 1.39%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 63        | 30%     |
| 251-500        | 45        | 21.43%  |
| 501-1000       | 26        | 12.38%  |
| 1001-2000      | 19        | 9.05%   |
| More than 3000 | 18        | 8.57%   |
| 51-100         | 11        | 5.24%   |
| Unknown        | 9         | 4.29%   |
| 2001-3000      | 8         | 3.81%   |
| 21-50          | 7         | 3.33%   |
| 1-20           | 4         | 1.9%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 82        | 39.23%  |
| 21-50          | 45        | 21.53%  |
| 51-100         | 27        | 12.92%  |
| 101-250        | 23        | 11%     |
| 251-500        | 10        | 4.78%   |
| Unknown        | 9         | 4.31%   |
| 501-1000       | 5         | 2.39%   |
| 2001-3000      | 4         | 1.91%   |
| More than 3000 | 2         | 0.96%   |
| 1001-2000      | 2         | 0.96%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                           | Notebooks | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| Toshiba MK2555GSX 250GB                                         | 2         | 2      | 6.06%   |
| WDC WD5000LPCX-22VHAT0 500GB                                    | 1         | 1      | 3.03%   |
| WDC WD10SPZX-24Z10 1TB                                          | 1         | 1      | 3.03%   |
| WDC WD10JPVX-60JC3T0 1TB                                        | 1         | 1      | 3.03%   |
| WDC WD Blue SA510 2.5 500GB                                     | 1         | 2      | 3.03%   |
| Toshiba MQ04ABF100 1TB                                          | 1         | 1      | 3.03%   |
| Toshiba MQ01ABF050M 500GB                                       | 1         | 1      | 3.03%   |
| Toshiba MQ01ABF050 500GB                                        | 1         | 1      | 3.03%   |
| Toshiba MK3261GSY 320GB                                         | 1         | 1      | 3.03%   |
| TARGET SSD 128G                                                 | 1         | 1      | 3.03%   |
| SK hynix HFS128G3BTND-N210A 128GB SSD                           | 1         | 1      | 3.03%   |
| SK hynix BC711 HFM512GD3JX013N 512GB                            | 1         | 1      | 3.03%   |
| Seagate ST9500325AS 500GB                                       | 1         | 1      | 3.03%   |
| Seagate ST9320423AS 320GB                                       | 1         | 1      | 3.03%   |
| Seagate ST500LT012-1DG142 500GB                                 | 1         | 1      | 3.03%   |
| Seagate ST500LM000-SSHD-8GB                                     | 1         | 1      | 3.03%   |
| Seagate ST320LT012-9WS14C 320GB                                 | 1         | 1      | 3.03%   |
| Seagate ST1000LM049-2GH172 1TB                                  | 1         | 1      | 3.03%   |
| Seagate ST1000LM048-2E7172 1TB                                  | 1         | 1      | 3.03%   |
| Seagate ST1000LM035-1RK172 1TB                                  | 1         | 1      | 3.03%   |
| Seagate ST1000LM014-SSHD-8GB                                    | 1         | 1      | 3.03%   |
| Samsung Electronics NVMe SSD Controller SM961/PM961/SM963 121GB | 1         | 1      | 3.03%   |
| Samsung Electronics HM100UI 1TB                                 | 1         | 1      | 3.03%   |
| SAGE 3639S 160GB                                                | 1         | 1      | 3.03%   |
| OWC Aura 2012 240GB SSD                                         | 1         | 1      | 3.03%   |
| LITEONIT DMT-80M6M-11 mSATA 80GB SSD                            | 1         | 1      | 3.03%   |
| Hitachi HTS547575A9E384 752GB                                   | 1         | 1      | 3.03%   |
| HGST HTS725032A7E630 320GB                                      | 1         | 1      | 3.03%   |
| HGST HTS721010A9E630 1TB                                        | 1         | 1      | 3.03%   |
| Crucial CT480BX200SSD1 480GB                                    | 1         | 1      | 3.03%   |
| Apple SSD SM0256F 256GB                                         | 1         | 1      | 3.03%   |
| A-DATA Technology SP900NS38 256GB SSD                           | 1         | 1      | 3.03%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 9      | 27.27%  |
| Toshiba             | 6         | 6      | 18.18%  |
| WDC                 | 4         | 5      | 12.12%  |
| SK hynix            | 2         | 2      | 6.06%   |
| Samsung Electronics | 2         | 2      | 6.06%   |
| HGST                | 2         | 2      | 6.06%   |
| TARGET              | 1         | 1      | 3.03%   |
| SAGE                | 1         | 1      | 3.03%   |
| OWC                 | 1         | 1      | 3.03%   |
| LITEONIT            | 1         | 1      | 3.03%   |
| Hitachi             | 1         | 1      | 3.03%   |
| Crucial             | 1         | 1      | 3.03%   |
| Apple               | 1         | 1      | 3.03%   |
| A-DATA Technology   | 1         | 1      | 3.03%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 9      | 39.13%  |
| Toshiba             | 6         | 6      | 26.09%  |
| WDC                 | 3         | 3      | 13.04%  |
| HGST                | 2         | 2      | 8.7%    |
| Samsung Electronics | 1         | 1      | 4.35%   |
| SAGE                | 1         | 1      | 4.35%   |
| Hitachi             | 1         | 1      | 4.35%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 23        | 23     | 69.7%   |
| SSD  | 8         | 9      | 24.24%  |
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
| Works    | 161       | 212    | 70.61%  |
| Detected | 34        | 52     | 14.91%  |
| Malfunc  | 32        | 34     | 14.04%  |
| Fixed    | 1         | 1      | 0.44%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 144       | 55.6%   |
| Samsung Electronics                     | 35        | 13.51%  |
| AMD                                     | 19        | 7.34%   |
| SanDisk                                 | 12        | 4.63%   |
| Kingston Technology Company             | 9         | 3.47%   |
| SK hynix                                | 8         | 3.09%   |
| Micron Technology                       | 7         | 2.7%    |
| KIOXIA                                  | 6         | 2.32%   |
| Toshiba America Info Systems            | 5         | 1.93%   |
| Phison Electronics                      | 3         | 1.16%   |
| Shenzhen Longsys Electronics            | 2         | 0.77%   |
| Nvidia                                  | 2         | 0.77%   |
| ADATA Technology                        | 2         | 0.77%   |
| Shenzhen Unionmemory Information System | 1         | 0.39%   |
| Seagate Technology                      | 1         | 0.39%   |
| Realtek Semiconductor                   | 1         | 0.39%   |
| Micron/Crucial Technology               | 1         | 0.39%   |
| Marvell Technology Group                | 1         | 0.39%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Volume Management Device NVMe RAID Controller                            | 17        | 6.18%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 17        | 6.18%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 15        | 5.45%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 15        | 5.45%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 15        | 5.45%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 14        | 5.09%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 13        | 4.73%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 10        | 3.64%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 8         | 2.91%   |
| Intel Tiger Lake-LP SATA Controller                                            | 8         | 2.91%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 7         | 2.55%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 6         | 2.18%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 5         | 1.82%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 5         | 1.82%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 5         | 1.82%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 5         | 1.82%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 5         | 1.82%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 1.82%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 1.45%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4         | 1.45%   |
| Micron 2200S NVMe SSD [Cassandra]                                              | 4         | 1.45%   |
| Intel Optane NVME SSD H10 with Solid State Storage [Teton Glacier]             | 4         | 1.45%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 1.45%   |
| Samsung S4LN053X01 AHCI SSD Controller(Apple slot)                             | 3         | 1.09%   |
| Phison E12 NVMe Controller                                                     | 3         | 1.09%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 3         | 1.09%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                  | 3         | 1.09%   |
| Kingston Company A1000/U-SNS8154P3 x2 NVMe SSD                                 | 3         | 1.09%   |
| Intel SSD 660P Series                                                          | 3         | 1.09%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 3         | 1.09%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 3         | 1.09%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 0.73%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)            | 2         | 0.73%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2         | 0.73%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 2         | 0.73%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 2         | 0.73%   |
| SanDisk PC SN520 x2 M.2 2242 NVMe SSD                                          | 2         | 0.73%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 2         | 0.73%   |
| Kingston Company NV2 NVMe SSD SM2267XT                                         | 2         | 0.73%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 2         | 0.73%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 141       | 52.22%  |
| NVMe | 95        | 35.19%  |
| RAID | 34        | 12.59%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 167       | 82.27%  |
| AMD    | 36        | 17.73%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 8         | 3.94%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 5         | 2.46%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 5         | 2.46%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 5         | 2.46%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 5         | 2.46%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 1.97%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 4         | 1.97%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 1.97%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 1.97%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 4         | 1.97%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 1.97%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 4         | 1.97%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 1.48%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 3         | 1.48%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 1.48%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 1.48%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 1.48%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 1.48%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 1.48%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 3         | 1.48%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 1.48%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 2         | 0.99%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 0.99%   |
| Intel Core i7-4712HQ CPU @ 2.30GHz            | 2         | 0.99%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 2         | 0.99%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 0.99%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 0.99%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 0.99%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 2         | 0.99%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 0.99%   |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz          | 2         | 0.99%   |
| Intel 12th Gen Core i5-12450H                 | 2         | 0.99%   |
| Intel 11th Gen Core i5-11400H @ 2.70GHz       | 2         | 0.99%   |
| Intel 11th Gen Core i5-11320H @ 3.20GHz       | 2         | 0.99%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 2         | 0.99%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 0.99%   |
| AMD Ryzen 5 5625U with Radeon Graphics        | 2         | 0.99%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 2         | 0.99%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 2         | 0.99%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 0.99%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 57        | 28.08%  |
| Intel Core i7           | 46        | 22.66%  |
| Other                   | 29        | 14.29%  |
| AMD Ryzen 5             | 19        | 9.36%   |
| Intel Core i3           | 18        | 8.87%   |
| Intel Core 2 Duo        | 6         | 2.96%   |
| AMD Ryzen 7             | 5         | 2.46%   |
| Intel Celeron           | 4         | 1.97%   |
| AMD Ryzen 3             | 3         | 1.48%   |
| Intel Xeon              | 2         | 0.99%   |
| Intel Pentium           | 2         | 0.99%   |
| Intel Pentium Silver    | 1         | 0.49%   |
| Intel Pentium Dual-Core | 1         | 0.49%   |
| Intel Core M            | 1         | 0.49%   |
| Intel Atom              | 1         | 0.49%   |
| AMD Ryzen 7 PRO         | 1         | 0.49%   |
| AMD E1                  | 1         | 0.49%   |
| AMD E                   | 1         | 0.49%   |
| AMD C-60                | 1         | 0.49%   |
| AMD Athlon              | 1         | 0.49%   |
| AMD A6                  | 1         | 0.49%   |
| AMD A4                  | 1         | 0.49%   |
| AMD A12                 | 1         | 0.49%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 95        | 46.8%   |
| 4      | 72        | 35.47%  |
| 6      | 23        | 11.33%  |
| 8      | 9         | 4.43%   |
| 12     | 2         | 0.99%   |
| 14     | 1         | 0.49%   |
| 10     | 1         | 0.49%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 203       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 181       | 88.73%  |
| 1      | 23        | 11.27%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 203       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 129       | 62.62%  |
| 0x806c1    | 7         | 3.4%    |
| 0x806ec    | 6         | 2.91%   |
| 0x08108109 | 5         | 2.43%   |
| 0x906ea    | 4         | 1.94%   |
| 0x306a9    | 4         | 1.94%   |
| 0x08608103 | 4         | 1.94%   |
| 0x906e9    | 3         | 1.46%   |
| 0x806e9    | 3         | 1.46%   |
| 0x206a7    | 3         | 1.46%   |
| 0x806eb    | 2         | 0.97%   |
| 0x706a8    | 2         | 0.97%   |
| 0x40651    | 2         | 0.97%   |
| 0x0a50000c | 2         | 0.97%   |
| 0x0a404102 | 2         | 0.97%   |
| 0x08600106 | 2         | 0.97%   |
| 0x08108102 | 2         | 0.97%   |
| 0x06006705 | 2         | 0.97%   |
| 0x05000101 | 2         | 0.97%   |
| 0xa0652    | 1         | 0.49%   |
| 0x906ed    | 1         | 0.49%   |
| 0x906eb    | 1         | 0.49%   |
| 0x906a3    | 1         | 0.49%   |
| 0x806d1    | 1         | 0.49%   |
| 0x706e5    | 1         | 0.49%   |
| 0x506e3    | 1         | 0.49%   |
| 0x406e3    | 1         | 0.49%   |
| 0x40661    | 1         | 0.49%   |
| 0x306d4    | 1         | 0.49%   |
| 0x306c3    | 1         | 0.49%   |
| 0x20652    | 1         | 0.49%   |
| 0x1067a    | 1         | 0.49%   |
| 0x0a50000d | 1         | 0.49%   |
| 0x0a404101 | 1         | 0.49%   |
| 0x08608104 | 1         | 0.49%   |
| 0x0810100b | 1         | 0.49%   |
| 0x0600611a | 1         | 0.49%   |
| 0x0500010d | 1         | 0.49%   |
| 0x03000027 | 1         | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 46        | 22.66%  |
| TigerLake        | 19        | 9.36%   |
| Haswell          | 18        | 8.87%   |
| IvyBridge        | 14        | 6.9%    |
| Broadwell        | 14        | 6.9%    |
| SandyBridge      | 11        | 5.42%   |
| IceLake          | 11        | 5.42%   |
| Zen+             | 8         | 3.94%   |
| Skylake          | 8         | 3.94%   |
| Unknown          | 8         | 3.94%   |
| Penryn           | 7         | 3.45%   |
| Zen 3            | 6         | 2.96%   |
| Zen 2            | 6         | 2.96%   |
| Alderlake Hybrid | 6         | 2.96%   |
| Goldmont plus    | 4         | 1.97%   |
| CometLake        | 4         | 1.97%   |
| Westmere         | 3         | 1.48%   |
| Excavator        | 3         | 1.48%   |
| Bobcat           | 3         | 1.48%   |
| Zen              | 1         | 0.49%   |
| Tremont          | 1         | 0.49%   |
| Silvermont       | 1         | 0.49%   |
| K10 Llano        | 1         | 0.49%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 159       | 58.03%  |
| Nvidia | 73        | 26.64%  |
| AMD    | 42        | 15.33%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                          | 13        | 4.69%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 11        | 3.97%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 11        | 3.97%   |
| Intel HD Graphics 5500                                                    | 10        | 3.61%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 8         | 2.89%   |
| Intel UHD Graphics 620                                                    | 8         | 2.89%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                 | 8         | 2.89%   |
| Intel HD Graphics 620                                                     | 8         | 2.89%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 8         | 2.89%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 8         | 2.89%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 8         | 2.89%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 7         | 2.53%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 7         | 2.53%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 6         | 2.17%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 6         | 2.17%   |
| Intel HD Graphics 630                                                     | 5         | 1.81%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]             | 5         | 1.81%   |
| AMD Lucienne                                                              | 5         | 1.81%   |
| Nvidia GP108M [GeForce MX150]                                             | 4         | 1.44%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 4         | 1.44%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 4         | 1.44%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 4         | 1.44%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 4         | 1.44%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 4         | 1.44%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 3         | 1.08%   |
| Nvidia GM108M [GeForce 940MX]                                             | 3         | 1.08%   |
| Nvidia GK107GLM [Quadro K1100M]                                           | 3         | 1.08%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 3         | 1.08%   |
| Intel HD Graphics 530                                                     | 3         | 1.08%   |
| Intel Core Processor Integrated Graphics Controller                       | 3         | 1.08%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 3         | 1.08%   |
| AMD Rembrandt [Radeon 680M]                                               | 3         | 1.08%   |
| Nvidia GP108M [GeForce MX250]                                             | 2         | 0.72%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 2         | 0.72%   |
| Nvidia GM108M [GeForce 840M]                                              | 2         | 0.72%   |
| Nvidia GK106M [GeForce GTX 770M]                                          | 2         | 0.72%   |
| Nvidia GF108GLM [NVS 5200M]                                               | 2         | 0.72%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 2         | 0.72%   |
| Intel HD Graphics 5300                                                    | 2         | 0.72%   |
| Intel Crystal Well Integrated Graphics Controller                         | 2         | 0.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 92        | 45.32%  |
| Intel + Nvidia | 59        | 29.06%  |
| 1 x AMD        | 27        | 13.3%   |
| 1 x Nvidia     | 7         | 3.45%   |
| AMD + Nvidia   | 7         | 3.45%   |
| Intel + AMD    | 5         | 2.46%   |
| 2 x Intel      | 3         | 1.48%   |
| 2 x AMD        | 3         | 1.48%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 171       | 83.01%  |
| Proprietary | 35        | 16.99%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 138       | 67.65%  |
| 1.01-2.0   | 21        | 10.29%  |
| 0.01-0.5   | 19        | 9.31%   |
| 3.01-4.0   | 13        | 6.37%   |
| 0.51-1.0   | 5         | 2.45%   |
| 5.01-6.0   | 4         | 1.96%   |
| 2.01-3.0   | 4         | 1.96%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 50        | 21.19%  |
| AU Optronics            | 40        | 16.95%  |
| Chimei Innolux          | 37        | 15.68%  |
| LG Display              | 30        | 12.71%  |
| Samsung Electronics     | 17        | 7.2%    |
| Apple                   | 13        | 5.51%   |
| PANDA                   | 6         | 2.54%   |
| Sharp                   | 5         | 2.12%   |
| Goldstar                | 4         | 1.69%   |
| Philips                 | 3         | 1.27%   |
| Chi Mei Optoelectronics | 3         | 1.27%   |
| BenQ                    | 3         | 1.27%   |
| TMX                     | 2         | 0.85%   |
| Sony                    | 2         | 0.85%   |
| Lenovo                  | 2         | 0.85%   |
| Hewlett-Packard         | 2         | 0.85%   |
| Dell                    | 2         | 0.85%   |
| CSO                     | 2         | 0.85%   |
| Yamaha                  | 1         | 0.42%   |
| Toshiba                 | 1         | 0.42%   |
| Sceptre Tech            | 1         | 0.42%   |
| RTK                     | 1         | 0.42%   |
| LGD                     | 1         | 0.42%   |
| LG Philips              | 1         | 0.42%   |
| KDB                     | 1         | 0.42%   |
| ITE                     | 1         | 0.42%   |
| HUAWEI                  | 1         | 0.42%   |
| HKC                     | 1         | 0.42%   |
| Eizo                    | 1         | 0.42%   |
| CTO                     | 1         | 0.42%   |
| Acer                    | 1         | 0.42%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch        | 4         | 1.69%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch        | 4         | 1.69%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch         | 3         | 1.27%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                   | 3         | 1.27%   |
| BOE LCD Monitor BOE084E 1920x1080 382x215mm 17.3-inch                   | 3         | 1.27%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                    | 3         | 1.27%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch       | 2         | 0.84%   |
| Samsung Electronics LCD Monitor SAM0F14 3840x2160 1872x1053mm 84.6-inch | 2         | 0.84%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                 | 2         | 0.84%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch            | 2         | 0.84%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch             | 2         | 0.84%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch        | 2         | 0.84%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch         | 2         | 0.84%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch        | 2         | 0.84%   |
| BOE LCD Monitor BOE0A81 1920x1080 344x194mm 15.5-inch                   | 2         | 0.84%   |
| BOE LCD Monitor BOE0816 1366x768 344x193mm 15.5-inch                    | 2         | 0.84%   |
| BOE LCD Monitor BOE0704 1366x768 344x194mm 15.5-inch                    | 2         | 0.84%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                   | 2         | 0.84%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch          | 2         | 0.84%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch           | 2         | 0.84%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch          | 2         | 0.84%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch           | 2         | 0.84%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch          | 2         | 0.84%   |
| Apple Color LCD APPA022 2880x1800 331x207mm 15.4-inch                   | 2         | 0.84%   |
| Yamaha RX-V473 YMH3171 1920x540                                         | 1         | 0.42%   |
| Toshiba TV TSB0205 1360x768 886x498mm 40.0-inch                         | 1         | 0.42%   |
| TMX TL156VDXP0101 TMX1561 1920x1080 344x194mm 15.5-inch                 | 1         | 0.42%   |
| TMX TL156MDMP11-0 TMX1560 3200x2000 336x210mm 15.6-inch                 | 1         | 0.42%   |
| Sony TV SNYF500 1360x768                                                | 1         | 0.42%   |
| Sony TV SNY3002 1920x1080 886x498mm 40.0-inch                           | 1         | 0.42%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                 | 1         | 0.42%   |
| Sharp LCD Monitor SHP14B9 3840x2160 344x194mm 15.5-inch                 | 1         | 0.42%   |
| Sharp LCD Monitor SHP143B 3840x2160 346x194mm 15.6-inch                 | 1         | 0.42%   |
| Sharp LCD Monitor SHP1431 3840x2160 350x190mm 15.7-inch                 | 1         | 0.42%   |
| Sharp LCD Monitor SHP13F8 3200x1800 346x194mm 15.6-inch                 | 1         | 0.42%   |
| Sceptre Tech C27 SPT0ADD 1920x1080 598x336mm 27.0-inch                  | 1         | 0.42%   |
| Samsung Electronics SMBX2450L SAM071F 1920x1080 521x293mm 23.5-inch     | 1         | 0.42%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 1         | 0.42%   |
| Samsung Electronics S24E650 SAM0CB8 1920x1080 521x293mm 23.5-inch       | 1         | 0.42%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch       | 1         | 0.42%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 119       | 52.89%  |
| 1366x768 (WXGA)    | 52        | 23.11%  |
| 1600x900 (HD+)     | 11        | 4.89%   |
| 3840x2160 (4K)     | 8         | 3.56%   |
| 1280x800 (WXGA)    | 7         | 3.11%   |
| 1440x900 (WXGA+)   | 4         | 1.78%   |
| 2880x1800          | 3         | 1.33%   |
| 2560x1600          | 3         | 1.33%   |
| 2560x1440 (QHD)    | 3         | 1.33%   |
| 1920x1200 (WUXGA)  | 3         | 1.33%   |
| 3200x1800 (QHD+)   | 2         | 0.89%   |
| 2560x1080          | 2         | 0.89%   |
| 2160x1440          | 2         | 0.89%   |
| 1680x1050 (WSXGA+) | 2         | 0.89%   |
| 3840x2400          | 1         | 0.44%   |
| 3200x2000          | 1         | 0.44%   |
| 1920x540           | 1         | 0.44%   |
| 1360x768           | 1         | 0.44%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 108       | 45.76%  |
| 13      | 37        | 15.68%  |
| 14      | 34        | 14.41%  |
| 17      | 12        | 5.08%   |
| 23      | 6         | 2.54%   |
| 24      | 5         | 2.12%   |
| 21      | 5         | 2.12%   |
| 31      | 4         | 1.69%   |
| 84      | 3         | 1.27%   |
| 27      | 3         | 1.27%   |
| 16      | 3         | 1.27%   |
| 72      | 2         | 0.85%   |
| 12      | 2         | 0.85%   |
| Unknown | 2         | 0.85%   |
| 54      | 1         | 0.42%   |
| 46      | 1         | 0.42%   |
| 41      | 1         | 0.42%   |
| 34      | 1         | 0.42%   |
| 28      | 1         | 0.42%   |
| 20      | 1         | 0.42%   |
| 19      | 1         | 0.42%   |
| 18      | 1         | 0.42%   |
| 11      | 1         | 0.42%   |
| 10      | 1         | 0.42%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 162       | 68.35%  |
| 201-300     | 22        | 9.28%   |
| 501-600     | 14        | 5.91%   |
| 351-400     | 14        | 5.91%   |
| 401-500     | 9         | 3.8%    |
| 601-700     | 5         | 2.11%   |
| 1501-2000   | 5         | 2.11%   |
| 1001-1500   | 2         | 0.84%   |
| Unknown     | 2         | 0.84%   |
| 701-800     | 1         | 0.42%   |
| 901-1000    | 1         | 0.42%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 178       | 85.99%  |
| 16/10   | 23        | 11.11%  |
| 3/2     | 2         | 0.97%   |
| 21/9    | 2         | 0.97%   |
| 32/9    | 1         | 0.48%   |
| Unknown | 1         | 0.48%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 110       | 46.81%  |
| 81-90          | 60        | 25.53%  |
| 201-250        | 12        | 5.11%   |
| 121-130        | 12        | 5.11%   |
| 71-80          | 11        | 4.68%   |
| More than 1000 | 6         | 2.55%   |
| 351-500        | 5         | 2.13%   |
| 151-200        | 5         | 2.13%   |
| 301-350        | 3         | 1.28%   |
| 61-70          | 2         | 0.85%   |
| 501-1000       | 2         | 0.85%   |
| Unknown        | 2         | 0.85%   |
| 51-60          | 1         | 0.43%   |
| 41-50          | 1         | 0.43%   |
| 251-300        | 1         | 0.43%   |
| 141-150        | 1         | 0.43%   |
| 111-120        | 1         | 0.43%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 114       | 48.93%  |
| 101-120       | 61        | 26.18%  |
| 51-100        | 27        | 11.59%  |
| 161-240       | 16        | 6.87%   |
| More than 240 | 9         | 3.86%   |
| 1-50          | 4         | 1.72%   |
| Unknown       | 2         | 0.86%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 167       | 82.27%  |
| 2     | 33        | 16.26%  |
| 3     | 3         | 1.48%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 112       | 37.09%  |
| Realtek Semiconductor             | 105       | 34.77%  |
| Qualcomm Atheros                  | 28        | 9.27%   |
| Broadcom                          | 18        | 5.96%   |
| Broadcom Limited                  | 9         | 2.98%   |
| MediaTek                          | 5         | 1.66%   |
| ASIX Electronics                  | 4         | 1.32%   |
| TP-Link                           | 3         | 0.99%   |
| Sierra Wireless                   | 2         | 0.66%   |
| Samsung Electronics               | 2         | 0.66%   |
| Qualcomm                          | 2         | 0.66%   |
| Nvidia                            | 2         | 0.66%   |
| Ericsson Business Mobile Networks | 2         | 0.66%   |
| Ralink Technology                 | 1         | 0.33%   |
| Ralink                            | 1         | 0.33%   |
| OPPO Electronics                  | 1         | 0.33%   |
| Microchip Technology              | 1         | 0.33%   |
| Marvell Technology Group          | 1         | 0.33%   |
| Huawei Technologies               | 1         | 0.33%   |
| Dell                              | 1         | 0.33%   |
| ASUSTek Computer                  | 1         | 0.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 68        | 18.53%  |
| Intel Wi-Fi 6 AX201                                                  | 14        | 3.81%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 11        | 3%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 11        | 3%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 11        | 3%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 11        | 3%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                             | 10        | 2.72%   |
| Intel Wireless 8265 / 8275                                           | 9         | 2.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 8         | 2.18%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 7         | 1.91%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 7         | 1.91%   |
| Intel Wireless 7265                                                  | 6         | 1.63%   |
| Intel Wireless 7260                                                  | 6         | 1.63%   |
| Intel Wi-Fi 6 AX200                                                  | 6         | 1.63%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 6         | 1.63%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 6         | 1.63%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 5         | 1.36%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 5         | 1.36%   |
| Intel Wireless 8260                                                  | 5         | 1.36%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 4         | 1.09%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 4         | 1.09%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                    | 4         | 1.09%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 4         | 1.09%   |
| ASIX AX88179 Gigabit Ethernet                                        | 4         | 1.09%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 3         | 0.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 3         | 0.82%   |
| Intel Wireless 3165                                                  | 3         | 0.82%   |
| Intel Ethernet Connection (4) I219-LM                                | 3         | 0.82%   |
| Intel Ethernet Connection (2) I219-LM                                | 3         | 0.82%   |
| Intel Centrino Wireless-N 2230                                       | 3         | 0.82%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 3         | 0.82%   |
| Broadcom Limited BCM4352 802.11ac Dual Band Wireless Network Adapter | 3         | 0.82%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 2         | 0.54%   |
| Sierra Wireless EM7455                                               | 2         | 0.54%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)          | 2         | 0.54%   |
| Realtek RTL8723DE Wireless Network Adapter                           | 2         | 0.54%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller            | 2         | 0.54%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 2         | 0.54%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 2         | 0.54%   |
| Intel Wireless 3160                                                  | 2         | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 110       | 52.88%  |
| Realtek Semiconductor | 36        | 17.31%  |
| Qualcomm Atheros      | 23        | 11.06%  |
| Broadcom              | 16        | 7.69%   |
| Broadcom Limited      | 8         | 3.85%   |
| MediaTek              | 5         | 2.4%    |
| TP-Link               | 3         | 1.44%   |
| Sierra Wireless       | 2         | 0.96%   |
| Ralink Technology     | 1         | 0.48%   |
| Ralink                | 1         | 0.48%   |
| Qualcomm              | 1         | 0.48%   |
| Dell                  | 1         | 0.48%   |
| ASUSTek Computer      | 1         | 0.48%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                                  | 14        | 6.73%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 11        | 5.29%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 11        | 5.29%   |
| Intel Wireless 8265 / 8275                                           | 9         | 4.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 8         | 3.85%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 7         | 3.37%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 7         | 3.37%   |
| Intel Wireless 7265                                                  | 6         | 2.88%   |
| Intel Wireless 7260                                                  | 6         | 2.88%   |
| Intel Wi-Fi 6 AX200                                                  | 6         | 2.88%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 6         | 2.88%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 6         | 2.88%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 5         | 2.4%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 5         | 2.4%    |
| Intel Wireless 8260                                                  | 5         | 2.4%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 4         | 1.92%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 4         | 1.92%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 4         | 1.92%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 3         | 1.44%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 3         | 1.44%   |
| Intel Wireless 3165                                                  | 3         | 1.44%   |
| Intel Centrino Wireless-N 2230                                       | 3         | 1.44%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 3         | 1.44%   |
| Broadcom Limited BCM4352 802.11ac Dual Band Wireless Network Adapter | 3         | 1.44%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 2         | 0.96%   |
| Sierra Wireless EM7455                                               | 2         | 0.96%   |
| Realtek RTL8723DE Wireless Network Adapter                           | 2         | 0.96%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 2         | 0.96%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 2         | 0.96%   |
| Intel Wireless 3160                                                  | 2         | 0.96%   |
| Intel Gemini Lake PCH CNVi WiFi                                      | 2         | 0.96%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 2         | 0.96%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 2         | 0.96%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 2         | 0.96%   |
| Intel Centrino Ultimate-N 6300                                       | 2         | 0.96%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter         | 2         | 0.96%   |
| Broadcom BCM4352 802.11ac Dual Band Wireless Network Adapter         | 2         | 0.96%   |
| Broadcom BCM43224 802.11a/b/g/n                                      | 2         | 0.96%   |
| Broadcom BCM43142 802.11b/g/n                                        | 2         | 0.96%   |
| TP-Link 802.11ac NIC                                                 | 1         | 0.48%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 88        | 57.14%  |
| Intel                    | 38        | 24.68%  |
| Qualcomm Atheros         | 8         | 5.19%   |
| Broadcom                 | 6         | 3.9%    |
| ASIX Electronics         | 4         | 2.6%    |
| Samsung Electronics      | 2         | 1.3%    |
| Nvidia                   | 2         | 1.3%    |
| Qualcomm                 | 1         | 0.65%   |
| OPPO Electronics         | 1         | 0.65%   |
| Microchip Technology     | 1         | 0.65%   |
| Marvell Technology Group | 1         | 0.65%   |
| Huawei Technologies      | 1         | 0.65%   |
| Broadcom Limited         | 1         | 0.65%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 68        | 43.31%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 7.01%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 7.01%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 10        | 6.37%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 2.55%   |
| ASIX AX88179 Gigabit Ethernet                                     | 4         | 2.55%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.91%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 1.91%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 1.27%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 1.27%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.27%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.27%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.27%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 1.27%   |
| Intel Ethernet Connection (3) I218-V                              | 2         | 1.27%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 1.27%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.64%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.64%   |
| Qualcomm Redmi Note 8                                             | 1         | 0.64%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.64%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.64%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.64%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.64%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.64%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.64%   |
| OPPO RMX2027                                                      | 1         | 0.64%   |
| Nvidia MCP89 Ethernet                                             | 1         | 0.64%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.64%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                     | 1         | 0.64%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.64%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.64%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.64%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.64%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.64%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.64%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 0.64%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 0.64%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 0.64%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.64%   |
| Huawei ALP-AL00                                                   | 1         | 0.64%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 198       | 56.73%  |
| Ethernet | 149       | 42.69%  |
| Modem    | 2         | 0.57%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 158       | 78.61%  |
| Ethernet | 43        | 21.39%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 131       | 64.53%  |
| 1     | 70        | 34.48%  |
| 0     | 2         | 0.99%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 130       | 64.04%  |
| Yes  | 73        | 35.96%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 93        | 51.38%  |
| Realtek Semiconductor           | 22        | 12.15%  |
| IMC Networks                    | 12        | 6.63%   |
| Apple                           | 12        | 6.63%   |
| Qualcomm Atheros Communications | 11        | 6.08%   |
| Broadcom                        | 10        | 5.52%   |
| Lite-On Technology              | 7         | 3.87%   |
| Foxconn / Hon Hai               | 5         | 2.76%   |
| Realtek                         | 4         | 2.21%   |
| Toshiba                         | 2         | 1.1%    |
| USI                             | 1         | 0.55%   |
| Dell                            | 1         | 0.55%   |
| Cambridge Silicon Radio         | 1         | 0.55%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 30        | 16.57%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 27        | 14.92%  |
| Intel AX201 Bluetooth                               | 21        | 11.6%   |
| Realtek Bluetooth Radio                             | 16        | 8.84%   |
| Qualcomm Atheros  Bluetooth Device                  | 10        | 5.52%   |
| Apple Bluetooth Host Controller                     | 7         | 3.87%   |
| Intel AX200 Bluetooth                               | 6         | 3.31%   |
| Realtek  Bluetooth 4.2 Adapter                      | 5         | 2.76%   |
| IMC Networks Bluetooth Radio                        | 5         | 2.76%   |
| Realtek Bluetooth Radio                             | 4         | 2.21%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 4         | 2.21%   |
| IMC Networks Wireless_Device                        | 4         | 2.21%   |
| Apple Bluetooth USB Host Controller                 | 4         | 2.21%   |
| Lite-On Bluetooth Device                            | 3         | 1.66%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 1.66%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 1.1%    |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 1.1%    |
| IMC Networks BCM20702A0                             | 2         | 1.1%    |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 1.1%    |
| Broadcom BCM20702A0 Bluetooth                       | 2         | 1.1%    |
| USI Bluetooth Device                                | 1         | 0.55%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 0.55%   |
| Toshiba BCM43142A0                                  | 1         | 0.55%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.55%   |
| Qualcomm Atheros Bluetooth (AR3011)                 | 1         | 0.55%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 0.55%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.55%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.55%   |
| Intel Bluetooth Device                              | 1         | 0.55%   |
| Intel AX210 Bluetooth                               | 1         | 0.55%   |
| IMC Networks Bluetooth Device                       | 1         | 0.55%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth     | 1         | 0.55%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 0.55%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 1         | 0.55%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 0.55%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 0.55%   |
| Broadcom HP Portable Valentine                      | 1         | 0.55%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 0.55%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 0.55%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 0.55%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 164       | 65.08%  |
| Nvidia                     | 39        | 15.48%  |
| AMD                        | 38        | 15.08%  |
| GN Netcom                  | 2         | 0.79%   |
| Samsung Electronics        | 1         | 0.4%    |
| Realtek Semiconductor      | 1         | 0.4%    |
| PreSonus Audio Electronics | 1         | 0.4%    |
| Lenovo                     | 1         | 0.4%    |
| JMTek                      | 1         | 0.4%    |
| Digidesign                 | 1         | 0.4%    |
| C-Media Electronics        | 1         | 0.4%    |
| Barco Display Systems      | 1         | 0.4%    |
| ASUSTek Computer           | 1         | 0.4%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 26        | 8.31%   |
| Intel Sunrise Point-LP HD Audio                                            | 21        | 6.71%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 19        | 6.07%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 17        | 5.43%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 14        | 4.47%   |
| Intel Broadwell-U Audio Controller                                         | 14        | 4.47%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 14        | 4.47%   |
| Intel Cannon Lake PCH cAVS                                                 | 11        | 3.51%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 9         | 2.88%   |
| Intel Haswell-ULT HD Audio Controller                                      | 9         | 2.88%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 9         | 2.88%   |
| Intel 8 Series HD Audio Controller                                         | 9         | 2.88%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 8         | 2.56%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 8         | 2.56%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 8         | 2.56%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 7         | 2.24%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6         | 1.92%   |
| Intel CM238 HD Audio Controller                                            | 6         | 1.92%   |
| Intel Comet Lake PCH-LP cAVS                                               | 5         | 1.6%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 1.6%    |
| Nvidia TU116 High Definition Audio Controller                              | 4         | 1.28%   |
| Nvidia GA106 High Definition Audio Controller                              | 4         | 1.28%   |
| Nvidia Audio device                                                        | 4         | 1.28%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 1.28%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 4         | 1.28%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 1.28%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3         | 0.96%   |
| Nvidia GK107 HDMI Audio Controller                                         | 3         | 0.96%   |
| Intel Comet Lake PCH cAVS                                                  | 3         | 0.96%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 0.96%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 3         | 0.96%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 3         | 0.96%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 0.64%   |
| Nvidia GK106 HDMI Audio Controller                                         | 2         | 0.64%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 0.64%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 0.64%   |
| Intel Crystal Well HD Audio Controller                                     | 2         | 0.64%   |
| AMD Wrestler HDMI Audio                                                    | 2         | 0.64%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 0.64%   |
| AMD Navi 10 HDMI Audio                                                     | 2         | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 70        | 29.91%  |
| Samsung Electronics | 66        | 28.21%  |
| Micron Technology   | 33        | 14.1%   |
| Kingston            | 14        | 5.98%   |
| Crucial             | 14        | 5.98%   |
| Ramaxel Technology  | 10        | 4.27%   |
| Elpida              | 7         | 2.99%   |
| Unknown             | 5         | 2.14%   |
| Smart               | 2         | 0.85%   |
| GOODRAM             | 2         | 0.85%   |
| Corsair             | 2         | 0.85%   |
| Timetec             | 1         | 0.43%   |
| Team                | 1         | 0.43%   |
| Smart Brazil        | 1         | 0.43%   |
| PNY                 | 1         | 0.43%   |
| Nanya Technology    | 1         | 0.43%   |
| Magnum Tech         | 1         | 0.43%   |
| KingFast            | 1         | 0.43%   |
| Kimtigo             | 1         | 0.43%   |
| A-DATA Technology   | 1         | 0.43%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 8         | 3.29%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 6         | 2.47%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 6         | 2.47%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 2.06%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 5         | 2.06%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 4         | 1.65%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 4         | 1.65%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s      | 4         | 1.65%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 1.23%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.23%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 3         | 1.23%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 1.23%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 1.23%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 1.23%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.23%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 3         | 1.23%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 2         | 0.82%   |
| SK hynix RAM HMT451S6MFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 0.82%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.82%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.82%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 2         | 0.82%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 0.82%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.82%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 0.82%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 2         | 0.82%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.82%   |
| SK hynix RAM HMA81GS6DJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.82%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.82%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 4GB Row Of Chips LPDDR5 6400MT/s | 2         | 0.82%   |
| Samsung RAM Module 4GB SODIMM DDR3 1333MT/s                      | 2         | 0.82%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.82%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.82%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.82%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s            | 2         | 0.82%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 2         | 0.82%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s         | 2         | 0.82%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.82%   |
| Micron RAM 4ATF51264HZ-2G3E1 4GB SODIMM DDR4 2667MT/s            | 2         | 0.82%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.82%   |
| Kingston RAM KF3200C20S4/16G 16GB SODIMM DDR4 3200MT/s           | 2         | 0.82%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 106       | 56.68%  |
| DDR3   | 60        | 32.09%  |
| LPDDR5 | 4         | 2.14%   |
| LPDDR4 | 4         | 2.14%   |
| LPDDR3 | 4         | 2.14%   |
| DDR5   | 3         | 1.6%    |
| DDR2   | 3         | 1.6%    |
| SDRAM  | 2         | 1.07%   |
| DDR    | 1         | 0.53%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 169       | 87.56%  |
| Row Of Chips | 21        | 10.88%  |
| Chip         | 3         | 1.55%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 98        | 46.23%  |
| 4096  | 73        | 34.43%  |
| 16384 | 23        | 10.85%  |
| 2048  | 17        | 8.02%   |
| 32768 | 1         | 0.47%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 54        | 25.96%  |
| 3200    | 47        | 22.6%   |
| 1600    | 45        | 21.63%  |
| 2400    | 10        | 4.81%   |
| 1333    | 10        | 4.81%   |
| 2133    | 7         | 3.37%   |
| 3266    | 6         | 2.88%   |
| 6400    | 4         | 1.92%   |
| 1334    | 4         | 1.92%   |
| 1067    | 4         | 1.92%   |
| 4800    | 3         | 1.44%   |
| 4267    | 2         | 0.96%   |
| 4199    | 2         | 0.96%   |
| 1066    | 2         | 0.96%   |
| 800     | 2         | 0.96%   |
| Unknown | 2         | 0.96%   |
| 8400    | 1         | 0.48%   |
| 2933    | 1         | 0.48%   |
| 2666    | 1         | 0.48%   |
| 975     | 1         | 0.48%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Notebooks | Percent |
|------------------------|-----------|---------|
| HP DeskJet 2700 series | 1         | 100%    |

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


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 200 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| IMC Networks                           | 37        | 19.37%  |
| Chicony Electronics                    | 37        | 19.37%  |
| Bison Electronics                      | 18        | 9.42%   |
| Realtek Semiconductor                  | 16        | 8.38%   |
| Microdia                               | 13        | 6.81%   |
| Quanta                                 | 11        | 5.76%   |
| Sunplus Innovation Technology          | 10        | 5.24%   |
| Apple                                  | 9         | 4.71%   |
| Syntek                                 | 7         | 3.66%   |
| Lite-On Technology                     | 5         | 2.62%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 2.62%   |
| Suyin                                  | 4         | 2.09%   |
| Luxvisions Innotech Limited            | 4         | 2.09%   |
| SunplusIT                              | 2         | 1.05%   |
| Acer                                   | 2         | 1.05%   |
| Y Media                                | 1         | 0.52%   |
| Sonix Technology                       | 1         | 0.52%   |
| Silicon Motion                         | 1         | 0.52%   |
| Samsung Electronics                    | 1         | 0.52%   |
| Ricoh                                  | 1         | 0.52%   |
| OPPO Electronics                       | 1         | 0.52%   |
| LG Innotek                             | 1         | 0.52%   |
| Intel                                  | 1         | 0.52%   |
| Alpha Imaging Technology               | 1         | 0.52%   |
| ALi                                    | 1         | 0.52%   |
| Alcor Micro                            | 1         | 0.52%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                              | 12        | 6.22%   |
| Chicony Integrated Camera                                      | 12        | 6.22%   |
| IMC Networks Integrated Camera                                 | 8         | 4.15%   |
| Syntek Integrated Camera                                       | 7         | 3.63%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 7         | 3.63%   |
| Realtek Integrated_Webcam_HD                                   | 6         | 3.11%   |
| Quanta HP TrueVision HD Camera                                 | 6         | 3.11%   |
| Microdia Integrated_Webcam_HD                                  | 5         | 2.59%   |
| Lite-On Integrated Camera                                      | 5         | 2.59%   |
| Bison HD Webcam                                                | 5         | 2.59%   |
| IMC Networks HD Camera                                         | 4         | 2.07%   |
| Apple FaceTime HD Camera                                       | 4         | 2.07%   |
| Quanta HD User Facing                                          | 3         | 1.55%   |
| Chicony HP TrueVision HD Camera                                | 3         | 1.55%   |
| Bison Lenovo Integrated Webcam                                 | 3         | 1.55%   |
| Sunplus Laptop Integrated Webcam FHD                           | 2         | 1.04%   |
| Sunplus Integrated_Webcam_HD                                   | 2         | 1.04%   |
| Realtek USB2.0 HD UVC WebCam                                   | 2         | 1.04%   |
| Realtek Integrated Webcam_HD                                   | 2         | 1.04%   |
| Microdia USB 2.0 Camera                                        | 2         | 1.04%   |
| Microdia Integrated Webcam                                     | 2         | 1.04%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 2         | 1.04%   |
| IMC Networks VGA UVC WebCam                                    | 2         | 1.04%   |
| Chicony Integrated IR Camera                                   | 2         | 1.04%   |
| Chicony HD WebCam                                              | 2         | 1.04%   |
| Chicony EasyCamera                                             | 2         | 1.04%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 2         | 1.04%   |
| Bison ThinkPad Integrated Camera                               | 2         | 1.04%   |
| Bison SunplusIT Integrated Camera                              | 2         | 1.04%   |
| Bison Integrated RGB Camera                                    | 2         | 1.04%   |
| Bison Integrated Camera                                        | 2         | 1.04%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                | 2         | 1.04%   |
| Apple Built-in iSight                                          | 2         | 1.04%   |
| Y Media USB Camera                                             | 1         | 0.52%   |
| Suyin USB 2.0 Camera                                           | 1         | 0.52%   |
| Suyin Integrated_Webcam_HD                                     | 1         | 0.52%   |
| Suyin HD WebCam                                                | 1         | 0.52%   |
| Suyin Asus Integrated Webcam                                   | 1         | 0.52%   |
| SunplusIT XiaoMi USB 2.0 Webcam                                | 1         | 0.52%   |
| SunplusIT USB 2M Camera                                        | 1         | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 10        | 34.48%  |
| Synaptics                  | 8         | 27.59%  |
| Shenzhen Goodix Technology | 6         | 20.69%  |
| Elan Microelectronics      | 2         | 6.9%    |
| AuthenTec                  | 2         | 6.9%    |
| LighTuning Technology      | 1         | 3.45%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                      | 5         | 17.24%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor        | 4         | 13.79%  |
| Validity Sensors VFS 5011 fingerprint sensor             | 3         | 10.34%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 2         | 6.9%    |
| Synaptics Metallica MIS Touch Fingerprint Reader         | 2         | 6.9%    |
| Validity Sensors VFS5011 Fingerprint Reader              | 1         | 3.45%   |
| Validity Sensors VFS495 Fingerprint Reader               | 1         | 3.45%   |
| Validity Sensors Synaptics WBDI                          | 1         | 3.45%   |
| Synaptics WBDI                                           | 1         | 3.45%   |
| Synaptics UWP WBDI                                       | 1         | 3.45%   |
| Synaptics  WBDI                                          | 1         | 3.45%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 3.45%   |
| Shenzhen Goodix Fingerprint Reader                       | 1         | 3.45%   |
| LighTuning Fingerprint Reader                            | 1         | 3.45%   |
| Elan ELAN:Fingerprint                                    | 1         | 3.45%   |
| Elan ELAN:ARM-M4                                         | 1         | 3.45%   |
| AuthenTec Fingerprint Sensor                             | 1         | 3.45%   |
| AuthenTec AES2810                                        | 1         | 3.45%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Alcor Micro                       | 6         | 35.29%  |
| Broadcom                          | 5         | 29.41%  |
| Upek                              | 3         | 17.65%  |
| Yubico.com                        | 1         | 5.88%   |
| VASCO Data Security International | 1         | 5.88%   |
| Clay Logic                        | 1         | 5.88%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                             | 6         | 35.29%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)      | 3         | 17.65%  |
| Broadcom BCM5880 Secure Applications Processor                  | 3         | 17.65%  |
| Yubico.com Yubikey NEO(-N) OTP+CCID                             | 1         | 5.88%   |
| VASCO Data Security International Digipass 905 SmartCard Reader | 1         | 5.88%   |
| Clay Logic Nitrokey Pro                                         | 1         | 5.88%   |
| Broadcom 5880                                                   | 1         | 5.88%   |
| Broadcom 58200                                                  | 1         | 5.88%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 142       | 69.61%  |
| 1     | 50        | 24.51%  |
| 2     | 11        | 5.39%   |
| 3     | 1         | 0.49%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 29        | 39.19%  |
| Chipcard              | 15        | 20.27%  |
| Graphics card         | 12        | 16.22%  |
| Multimedia controller | 7         | 9.46%   |
| Camera                | 5         | 6.76%   |
| Storage               | 2         | 2.7%    |
| Net/wireless          | 2         | 2.7%    |
| Network               | 1         | 1.35%   |
| Net/ethernet          | 1         | 1.35%   |

