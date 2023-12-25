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

Total: 293

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | Laptop 15-ef2xxx            | [31291c7bc9](https://linux-hardware.org/?probe=31291c7bc9) | Dec 24, 2023 |
| Dell          | Latitude 5440               | [d7462b97ac](https://linux-hardware.org/?probe=d7462b97ac) | Dec 22, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TES... | [4e773891cd](https://linux-hardware.org/?probe=4e773891cd) | Dec 21, 2023 |
| Dell          | Latitude E5540              | [af5e30a046](https://linux-hardware.org/?probe=af5e30a046) | Dec 20, 2023 |
| Dell          | Latitude D630               | [914826699f](https://linux-hardware.org/?probe=914826699f) | Dec 20, 2023 |
| HUAWEI        | KLVL-WXX9                   | [12f149be7f](https://linux-hardware.org/?probe=12f149be7f) | Dec 18, 2023 |
| MSI           | Bravo 15 B5DD               | [7bb3bd0328](https://linux-hardware.org/?probe=7bb3bd0328) | Dec 18, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [9986fed725](https://linux-hardware.org/?probe=9986fed725) | Dec 15, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [4a964fa296](https://linux-hardware.org/?probe=4a964fa296) | Dec 15, 2023 |
| Lenovo        | IdeaPad Slim 3 15IAH8 83... | [f942d9c43e](https://linux-hardware.org/?probe=f942d9c43e) | Dec 13, 2023 |
| HP            | ProBook 450 G1              | [f6f31f5ed6](https://linux-hardware.org/?probe=f6f31f5ed6) | Dec 13, 2023 |
| HP            | Pavilion dv7                | [1c31a8cd6f](https://linux-hardware.org/?probe=1c31a8cd6f) | Dec 12, 2023 |
| MECHREVO      | Kuangshi16Pro Series GM6... | [e551d0d31e](https://linux-hardware.org/?probe=e551d0d31e) | Dec 11, 2023 |
| HUAWEI        | KLVL-WXX9                   | [2abe635055](https://linux-hardware.org/?probe=2abe635055) | Dec 10, 2023 |
| Dell          | Inspiron 5570               | [87ef304fb0](https://linux-hardware.org/?probe=87ef304fb0) | Dec 07, 2023 |
| Alienware     | M17xR3                      | [0522045eab](https://linux-hardware.org/?probe=0522045eab) | Dec 07, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [d7e2b60dc8](https://linux-hardware.org/?probe=d7e2b60dc8) | Dec 06, 2023 |
| Lenovo        | V14 G2 ALC 82KC             | [31de30cc0e](https://linux-hardware.org/?probe=31de30cc0e) | Dec 06, 2023 |
| Timi          | RedmiBook 14-APCS           | [468a017a07](https://linux-hardware.org/?probe=468a017a07) | Dec 04, 2023 |
| Panasonic     | CF-52SL3DD1M                | [efdec9a15c](https://linux-hardware.org/?probe=efdec9a15c) | Dec 04, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [29d9e5aa67](https://linux-hardware.org/?probe=29d9e5aa67) | Dec 03, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [d45f900b4c](https://linux-hardware.org/?probe=d45f900b4c) | Dec 03, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [3ed69dec15](https://linux-hardware.org/?probe=3ed69dec15) | Nov 30, 2023 |
| Lenovo        | IdeaPad Slim 3 14IAN8 82... | [7eed706de5](https://linux-hardware.org/?probe=7eed706de5) | Nov 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [791f093fc3](https://linux-hardware.org/?probe=791f093fc3) | Nov 25, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX95D... | [0a24a8ef6d](https://linux-hardware.org/?probe=0a24a8ef6d) | Nov 24, 2023 |
| Lenovo        | IdeaPad 5 Pro 16IHU6 82L... | [cc934b68d9](https://linux-hardware.org/?probe=cc934b68d9) | Nov 22, 2023 |
| Toshiba       | Satellite P50-B-11V         | [448150c108](https://linux-hardware.org/?probe=448150c108) | Nov 21, 2023 |
| HP            | Pavilion dv7                | [b11ea54568](https://linux-hardware.org/?probe=b11ea54568) | Nov 20, 2023 |
| HP            | Laptop 15s-fr2xxx           | [fff3e03a74](https://linux-hardware.org/?probe=fff3e03a74) | Nov 20, 2023 |
| ASUSTek       | X540LJ                      | [fef63b579f](https://linux-hardware.org/?probe=fef63b579f) | Nov 17, 2023 |
| Lenovo        | Yoga 2 13 20344             | [ebb7ed0d8c](https://linux-hardware.org/?probe=ebb7ed0d8c) | Nov 16, 2023 |
| Acer          | Nitro AN515-57              | [39c7028c1e](https://linux-hardware.org/?probe=39c7028c1e) | Nov 15, 2023 |
| HUAWEI        | RLEF-XX                     | [5a7374e5b0](https://linux-hardware.org/?probe=5a7374e5b0) | Nov 13, 2023 |
| Lenovo        | ThinkPad X395 20NLS0J400    | [f5d1d61be6](https://linux-hardware.org/?probe=f5d1d61be6) | Nov 10, 2023 |
| Toshiba       | Satellite Pro L300          | [8cc0e1c14d](https://linux-hardware.org/?probe=8cc0e1c14d) | Nov 09, 2023 |
| HP            | Pavilion dv6                | [919942c11f](https://linux-hardware.org/?probe=919942c11f) | Nov 08, 2023 |
| ASUSTek       | UX310UQK                    | [98bc0094ec](https://linux-hardware.org/?probe=98bc0094ec) | Nov 06, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX95D... | [050ecd56d1](https://linux-hardware.org/?probe=050ecd56d1) | Nov 06, 2023 |
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
| Xero Rolling | 228       | 96.61%  |
| Xero         | 8         | 3.39%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| Xero | 235       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version          | Notebooks | Percent |
|------------------|-----------|---------|
| 6.4.12-arch1-1   | 32        | 12.65%  |
| 6.5.5-arch1-1    | 24        | 9.49%   |
| 6.5.9-arch2-1    | 21        | 8.3%    |
| 6.4.9-arch1-1    | 15        | 5.93%   |
| 6.4.3-arch1-2    | 13        | 5.14%   |
| 6.6.7-arch1-1    | 6         | 2.37%   |
| 6.4.2-arch1-1    | 6         | 2.37%   |
| 6.6.4-arch1-1    | 4         | 1.58%   |
| 6.6.3-arch1-1    | 4         | 1.58%   |
| 6.4.4-arch1-1    | 4         | 1.58%   |
| 6.4.1-arch2-1    | 4         | 1.58%   |
| 6.0.12-arch1-1   | 4         | 1.58%   |
| 5.16.15-arch1-1  | 4         | 1.58%   |
| 6.6.1-arch1-1    | 3         | 1.19%   |
| 6.5.3-arch1-1    | 3         | 1.19%   |
| 6.2.6-arch1-1    | 3         | 1.19%   |
| 6.1.1-arch1-1    | 3         | 1.19%   |
| 6.6.5-arch1-1    | 2         | 0.79%   |
| 6.4.2-zen1-1-zen | 2         | 0.79%   |
| 6.4.11-arch2-1   | 2         | 0.79%   |
| 6.4.10-arch1-1   | 2         | 0.79%   |
| 6.3.9-arch1-1    | 2         | 0.79%   |
| 6.3.8-arch1-1    | 2         | 0.79%   |
| 6.2.7-arch1-1    | 2         | 0.79%   |
| 6.0.7-arch1-1    | 2         | 0.79%   |
| 5.18.16-arch1-1  | 2         | 0.79%   |
| 5.18.11-arch1-1  | 2         | 0.79%   |
| 5.17.9-arch1-1   | 2         | 0.79%   |
| 5.16.8-arch1-1   | 2         | 0.79%   |
| 5.16.2-arch1-1   | 2         | 0.79%   |
| 5.16.1-arch1-1   | 2         | 0.79%   |
| 5.15.33-1-lts    | 2         | 0.79%   |
| 5.14.14-arch1-1  | 2         | 0.79%   |
| 6.6.6-zen1-1-zen | 1         | 0.4%    |
| 6.6.6-arch1-1    | 1         | 0.4%    |
| 6.5.8-arch1-1    | 1         | 0.4%    |
| 6.5.4-zen2-1-zen | 1         | 0.4%    |
| 6.5.4-arch2-1    | 1         | 0.4%    |
| 6.5.2-zen1-1-zen | 1         | 0.4%    |
| 6.5.2-arch1-1    | 1         | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.4.12  | 32        | 12.65%  |
| 6.5.5   | 24        | 9.49%   |
| 6.5.9   | 21        | 8.3%    |
| 6.4.9   | 15        | 5.93%   |
| 6.4.3   | 13        | 5.14%   |
| 6.4.2   | 8         | 3.16%   |
| 6.6.7   | 6         | 2.37%   |
| 6.4.1   | 5         | 1.98%   |
| 6.6.4   | 4         | 1.58%   |
| 6.6.3   | 4         | 1.58%   |
| 6.4.4   | 4         | 1.58%   |
| 6.4.10  | 4         | 1.58%   |
| 6.0.12  | 4         | 1.58%   |
| 5.16.15 | 4         | 1.58%   |
| 6.6.1   | 3         | 1.19%   |
| 6.5.3   | 3         | 1.19%   |
| 6.4.7   | 3         | 1.19%   |
| 6.4.11  | 3         | 1.19%   |
| 6.3.9   | 3         | 1.19%   |
| 6.2.6   | 3         | 1.19%   |
| 6.1.1   | 3         | 1.19%   |
| 5.14.16 | 3         | 1.19%   |
| 5.14.14 | 3         | 1.19%   |
| 6.6.6   | 2         | 0.79%   |
| 6.6.5   | 2         | 0.79%   |
| 6.5.4   | 2         | 0.79%   |
| 6.5.2   | 2         | 0.79%   |
| 6.3.8   | 2         | 0.79%   |
| 6.2.7   | 2         | 0.79%   |
| 6.1.38  | 2         | 0.79%   |
| 6.0.8   | 2         | 0.79%   |
| 6.0.7   | 2         | 0.79%   |
| 5.18.16 | 2         | 0.79%   |
| 5.18.11 | 2         | 0.79%   |
| 5.17.9  | 2         | 0.79%   |
| 5.16.8  | 2         | 0.79%   |
| 5.16.2  | 2         | 0.79%   |
| 5.16.1  | 2         | 0.79%   |
| 5.15.33 | 2         | 0.79%   |
| 5.14.8  | 2         | 0.79%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.4     | 86        | 34.96%  |
| 6.5     | 52        | 21.14%  |
| 6.6     | 21        | 8.54%   |
| 5.16    | 14        | 5.69%   |
| 6.1     | 12        | 4.88%   |
| 6.0     | 12        | 4.88%   |
| 5.15    | 9         | 3.66%   |
| 5.14    | 9         | 3.66%   |
| 6.3     | 7         | 2.85%   |
| 6.2     | 7         | 2.85%   |
| 5.19    | 5         | 2.03%   |
| 5.18    | 5         | 2.03%   |
| 5.17    | 4         | 1.63%   |
| 5.10    | 3         | 1.22%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 235       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| KDE5     | 225       | 94.54%  |
| XFCE     | 6         | 2.52%   |
| GNOME    | 3         | 1.26%   |
| Hyprland | 2         | 0.84%   |
| LeftWM   | 1         | 0.42%   |
| KDE      | 1         | 0.42%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 185       | 77.41%  |
| Wayland | 52        | 21.76%  |
| Tty     | 1         | 0.42%   |
| Unknown | 1         | 0.42%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 204       | 85%     |
| Unknown | 18        | 7.5%    |
| LightDM | 17        | 7.08%   |
| GDM     | 1         | 0.42%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 104       | 44.07%  |
| en_IN | 15        | 6.36%   |
| de_DE | 15        | 6.36%   |
| es_MX | 14        | 5.93%   |
| pl_PL | 11        | 4.66%   |
| fr_FR | 7         | 2.97%   |
| ru_RU | 6         | 2.54%   |
| pt_BR | 6         | 2.54%   |
| it_IT | 5         | 2.12%   |
| hu_HU | 5         | 2.12%   |
| en_GB | 5         | 2.12%   |
| zh_CN | 4         | 1.69%   |
| es_ES | 4         | 1.69%   |
| en_CA | 4         | 1.69%   |
| en_AU | 4         | 1.69%   |
| C     | 4         | 1.69%   |
| es_AR | 3         | 1.27%   |
| vi_VN | 2         | 0.85%   |
| tr_TR | 2         | 0.85%   |
| nb_NO | 2         | 0.85%   |
| en_ZA | 2         | 0.85%   |
| nl_NL | 1         | 0.42%   |
| ko_KR | 1         | 0.42%   |
| es_VE | 1         | 0.42%   |
| es_SV | 1         | 0.42%   |
| es_CL | 1         | 0.42%   |
| es_BO | 1         | 0.42%   |
| en_PH | 1         | 0.42%   |
| en_DK | 1         | 0.42%   |
| en_AG | 1         | 0.42%   |
| da_DK | 1         | 0.42%   |
| ca_ES | 1         | 0.42%   |
| ar_EG | 1         | 0.42%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 176       | 74.26%  |
| BIOS | 61        | 25.74%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 111       | 46.25%  |
| Btrfs   | 68        | 28.33%  |
| Xfs     | 57        | 23.75%  |
| Overlay | 4         | 1.67%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 184       | 77.64%  |
| MBR     | 35        | 14.77%  |
| Unknown | 18        | 7.59%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 194       | 80.83%  |
| Yes       | 46        | 19.17%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 149       | 62.61%  |
| Yes       | 89        | 37.39%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 66        | 28.09%  |
| ASUSTek Computer | 37        | 15.74%  |
| Dell             | 34        | 14.47%  |
| Hewlett-Packard  | 31        | 13.19%  |
| Acer             | 14        | 5.96%   |
| Apple            | 12        | 5.11%   |
| MSI              | 8         | 3.4%    |
| HUAWEI           | 8         | 3.4%    |
| Toshiba          | 4         | 1.7%    |
| Timi             | 3         | 1.28%   |
| Medion           | 3         | 1.28%   |
| Alienware        | 2         | 0.85%   |
| WEIGO            | 1         | 0.43%   |
| VIT              | 1         | 0.43%   |
| Pegatron         | 1         | 0.43%   |
| Panasonic        | 1         | 0.43%   |
| MECHREVO         | 1         | 0.43%   |
| LNV              | 1         | 0.43%   |
| LG Electronics   | 1         | 0.43%   |
| Juana Manso      | 1         | 0.43%   |
| HONOR            | 1         | 0.43%   |
| Google           | 1         | 0.43%   |
| Fujitsu          | 1         | 0.43%   |
| Compal           | 1         | 0.43%   |
| Aquarius         | 1         | 0.43%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Dell Precision M3800                  | 3         | 1.28%   |
| MSI Bravo 15 B5DD                     | 2         | 0.85%   |
| Lenovo IdeaPad Gaming 3 15IHU6 82K1   | 2         | 0.85%   |
| HUAWEI BOM-WXX9                       | 2         | 0.85%   |
| HP Pavilion dv7                       | 2         | 0.85%   |
| Dell Latitude E6520                   | 2         | 0.85%   |
| Dell Latitude E6430                   | 2         | 0.85%   |
| Dell Latitude 7480                    | 2         | 0.85%   |
| Dell Latitude 5420                    | 2         | 0.85%   |
| Apple MacBookPro8,1                   | 2         | 0.85%   |
| WEIGO CDA-141AU                       | 1         | 0.43%   |
| VIT P2402                             | 1         | 0.43%   |
| Toshiba TECRA A11                     | 1         | 0.43%   |
| Toshiba Satellite Pro L300            | 1         | 0.43%   |
| Toshiba Satellite P50-B-11V           | 1         | 0.43%   |
| Toshiba Satellite C55-C               | 1         | 0.43%   |
| Timi RedmiBook 14-APCS                | 1         | 0.43%   |
| Timi Redmi Book Pro 15 2022           | 1         | 0.43%   |
| Timi Redmi Book Pro 14 2022           | 1         | 0.43%   |
| Pegatron D15K                         | 1         | 0.43%   |
| Panasonic CF-52SL3DD1M                | 1         | 0.43%   |
| MSI Thin GF63 12VE                    | 1         | 0.43%   |
| MSI Katana GF66 11UE                  | 1         | 0.43%   |
| MSI GP73 Leopard 8RD                  | 1         | 0.43%   |
| MSI GF63 Thin 9SCX                    | 1         | 0.43%   |
| MSI GE72 6QF                          | 1         | 0.43%   |
| MSI GE62 7RD                          | 1         | 0.43%   |
| Medion P6816                          | 1         | 0.43%   |
| Medion E15408                         | 1         | 0.43%   |
| Medion Akoya P7818                    | 1         | 0.43%   |
| MECHREVO Kuangshi16Pro Series GM6PX0X | 1         | 0.43%   |
| LNV L40-70                            | 1         | 0.43%   |
| LG R310-K.AP31B                       | 1         | 0.43%   |
| Lenovo Z51-70 80K6                    | 1         | 0.43%   |
| Lenovo Yoga 3 Pro-1370 80HE           | 1         | 0.43%   |
| Lenovo Yoga 2 13 20344                | 1         | 0.43%   |
| Lenovo Y520-15IKBN 80WK               | 1         | 0.43%   |
| Lenovo XiaoXinPro 14 IRH8 83AL        | 1         | 0.43%   |
| Lenovo V330-15IKB 81AX                | 1         | 0.43%   |
| Lenovo V14 G2 ALC 82KC                | 1         | 0.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 29        | 12.34%  |
| Lenovo IdeaPad         | 22        | 9.36%   |
| Dell Latitude          | 14        | 5.96%   |
| HP Laptop              | 12        | 5.11%   |
| Dell Inspiron          | 10        | 4.26%   |
| Acer Aspire            | 10        | 4.26%   |
| ASUS VivoBook          | 9         | 3.83%   |
| Lenovo Legion          | 6         | 2.55%   |
| ASUS ASUS              | 6         | 2.55%   |
| HP Pavilion            | 5         | 2.13%   |
| Toshiba Satellite      | 3         | 1.28%   |
| HP ProBook             | 3         | 1.28%   |
| Dell Precision         | 3         | 1.28%   |
| ASUS ROG               | 3         | 1.28%   |
| Apple MacBookPro11     | 3         | 1.28%   |
| Acer Nitro             | 3         | 1.28%   |
| Timi Redmi             | 2         | 0.85%   |
| MSI Bravo              | 2         | 0.85%   |
| Lenovo Yoga            | 2         | 0.85%   |
| HUAWEI BOM-WXX9        | 2         | 0.85%   |
| HP ENVY                | 2         | 0.85%   |
| Dell Vostro            | 2         | 0.85%   |
| ASUS TUF               | 2         | 0.85%   |
| Apple MacBookPro9      | 2         | 0.85%   |
| Apple MacBookPro8      | 2         | 0.85%   |
| WEIGO CDA-141AU        | 1         | 0.43%   |
| VIT P2402              | 1         | 0.43%   |
| Toshiba TECRA          | 1         | 0.43%   |
| Timi RedmiBook         | 1         | 0.43%   |
| Pegatron D15K          | 1         | 0.43%   |
| Panasonic CF-52SL3DD1M | 1         | 0.43%   |
| MSI Thin               | 1         | 0.43%   |
| MSI Katana             | 1         | 0.43%   |
| MSI GP73               | 1         | 0.43%   |
| MSI GF63               | 1         | 0.43%   |
| MSI GE72               | 1         | 0.43%   |
| MSI GE62               | 1         | 0.43%   |
| Medion P6816           | 1         | 0.43%   |
| Medion E15408          | 1         | 0.43%   |
| Medion Akoya           | 1         | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 36        | 15.32%  |
| 2019 | 31        | 13.19%  |
| 2020 | 28        | 11.91%  |
| 2012 | 17        | 7.23%   |
| 2017 | 15        | 6.38%   |
| 2013 | 14        | 5.96%   |
| 2015 | 13        | 5.53%   |
| 2014 | 13        | 5.53%   |
| 2011 | 13        | 5.53%   |
| 2018 | 12        | 5.11%   |
| 2022 | 10        | 4.26%   |
| 2023 | 9         | 3.83%   |
| 2016 | 9         | 3.83%   |
| 2008 | 7         | 2.98%   |
| 2010 | 4         | 1.7%    |
| 2009 | 2         | 0.85%   |
| 2007 | 2         | 0.85%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 235       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 234       | 99.57%  |
| Enabled  | 1         | 0.43%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 234       | 99.57%  |
| Yes  | 1         | 0.43%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 84        | 35.59%  |
| 16.01-24.0  | 49        | 20.76%  |
| 8.01-16.0   | 47        | 19.92%  |
| 3.01-4.0    | 37        | 15.68%  |
| 32.01-64.0  | 10        | 4.24%   |
| 24.01-32.0  | 6         | 2.54%   |
| 64.01-256.0 | 2         | 0.85%   |
| 2.01-3.0    | 1         | 0.42%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 87        | 35.66%  |
| 2.01-3.0   | 84        | 34.43%  |
| 3.01-4.0   | 34        | 13.93%  |
| 4.01-8.0   | 31        | 12.7%   |
| 8.01-16.0  | 5         | 2.05%   |
| 0.51-1.0   | 2         | 0.82%   |
| 16.01-24.0 | 1         | 0.41%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 158       | 66.39%  |
| 2      | 68        | 28.57%  |
| 3      | 11        | 4.62%   |
| 4      | 1         | 0.42%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 176       | 74.58%  |
| Yes       | 60        | 25.42%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 173       | 73.62%  |
| No        | 62        | 26.38%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 230       | 97.87%  |
| No        | 5         | 2.13%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 209       | 88.56%  |
| No        | 27        | 11.44%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 34        | 14.41%  |
| Germany      | 22        | 9.32%   |
| India        | 20        | 8.47%   |
| Poland       | 12        | 5.08%   |
| France       | 10        | 4.24%   |
| Russia       | 8         | 3.39%   |
| Turkey       | 7         | 2.97%   |
| Vietnam      | 6         | 2.54%   |
| Italy        | 6         | 2.54%   |
| Hungary      | 6         | 2.54%   |
| Canada       | 6         | 2.54%   |
| Argentina    | 6         | 2.54%   |
| Spain        | 5         | 2.12%   |
| Mexico       | 5         | 2.12%   |
| China        | 5         | 2.12%   |
| Brazil       | 5         | 2.12%   |
| Norway       | 4         | 1.69%   |
| Morocco      | 4         | 1.69%   |
| Malaysia     | 4         | 1.69%   |
| Chile        | 4         | 1.69%   |
| Australia    | 4         | 1.69%   |
| Thailand     | 3         | 1.27%   |
| Netherlands  | 3         | 1.27%   |
| Indonesia    | 3         | 1.27%   |
| Greece       | 3         | 1.27%   |
| Syria        | 2         | 0.85%   |
| South Africa | 2         | 0.85%   |
| Romania      | 2         | 0.85%   |
| Portugal     | 2         | 0.85%   |
| Pakistan     | 2         | 0.85%   |
| Egypt        | 2         | 0.85%   |
| Denmark      | 2         | 0.85%   |
| Zambia       | 1         | 0.42%   |
| Venezuela    | 1         | 0.42%   |
| UK           | 1         | 0.42%   |
| Tunisia      | 1         | 0.42%   |
| Togo         | 1         | 0.42%   |
| Switzerland  | 1         | 0.42%   |
| Sweden       | 1         | 0.42%   |
| South Korea  | 1         | 0.42%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Istanbul         | 4         | 1.67%   |
| Longmont         | 3         | 1.26%   |
| Hanoi            | 3         | 1.26%   |
| Gdansk           | 3         | 1.26%   |
| Chennai          | 3         | 1.26%   |
| Warsaw           | 2         | 0.84%   |
| Ufa              | 2         | 0.84%   |
| Tangerang        | 2         | 0.84%   |
| Stuttgart        | 2         | 0.84%   |
| Seattle          | 2         | 0.84%   |
| Pune             | 2         | 0.84%   |
| Pretoria         | 2         | 0.84%   |
| Norfolk          | 2         | 0.84%   |
| Mariahalom       | 2         | 0.84%   |
| Madurai          | 2         | 0.84%   |
| Kuala Lumpur     | 2         | 0.84%   |
| Ho Chi Minh City | 2         | 0.84%   |
| Hamburg          | 2         | 0.84%   |
| Damascus         | 2         | 0.84%   |
| Casablanca       | 2         | 0.84%   |
| Cairo            | 2         | 0.84%   |
| Bengaluru        | 2         | 0.84%   |
| Zurich           | 1         | 0.42%   |
| Zenica           | 1         | 0.42%   |
| Zeeland          | 1         | 0.42%   |
| Zalaegerszeg     | 1         | 0.42%   |
| Zabrze           | 1         | 0.42%   |
| Wuhan            | 1         | 0.42%   |
| Wolfsburg        | 1         | 0.42%   |
| Wasilla          | 1         | 0.42%   |
| Virginia Beach   | 1         | 0.42%   |
| Vigo             | 1         | 0.42%   |
| Viburnum         | 1         | 0.42%   |
| Vejle            | 1         | 0.42%   |
| Vechelde         | 1         | 0.42%   |
| Vallenar         | 1         | 0.42%   |
| Valladolid       | 1         | 0.42%   |
| Ulan Bator       | 1         | 0.42%   |
| Ubatuba          | 1         | 0.42%   |
| Trondheim        | 1         | 0.42%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 60        | 66     | 19.11%  |
| Seagate                      | 30        | 34     | 9.55%   |
| WDC                          | 24        | 27     | 7.64%   |
| Toshiba                      | 21        | 22     | 6.69%   |
| Sandisk                      | 19        | 21     | 6.05%   |
| Kingston                     | 18        | 23     | 5.73%   |
| SK hynix                     | 14        | 14     | 4.46%   |
| Intel                        | 12        | 17     | 3.82%   |
| Micron Technology            | 10        | 11     | 3.18%   |
| Unknown                      | 8         | 12     | 2.55%   |
| KIOXIA                       | 6         | 7      | 1.91%   |
| HGST                         | 6         | 7      | 1.91%   |
| Crucial                      | 6         | 6      | 1.91%   |
| Apple                        | 5         | 5      | 1.59%   |
| JMicron Technology           | 4         | 4      | 1.27%   |
| Hitachi                      | 4         | 4      | 1.27%   |
| Transcend                    | 3         | 3      | 0.96%   |
| Phison Electronics           | 3         | 3      | 0.96%   |
| OWC                          | 3         | 3      | 0.96%   |
| LITEONIT                     | 3         | 3      | 0.96%   |
| Apacer                       | 3         | 3      | 0.96%   |
| A-DATA Technology            | 3         | 3      | 0.96%   |
| Yangtze Memory Technologies  | 2         | 2      | 0.64%   |
| Silicon Motion               | 2         | 2      | 0.64%   |
| Shenzhen Longsys Electronics | 2         | 2      | 0.64%   |
| SAGE                         | 2         | 2      | 0.64%   |
| Phison                       | 2         | 2      | 0.64%   |
| Micron/Crucial Technology    | 2         | 2      | 0.64%   |
| Kingston Technology Company  | 2         | 2      | 0.64%   |
| China                        | 2         | 2      | 0.64%   |
| Zebronics                    | 1         | 1      | 0.32%   |
| Vaseky                       | 1         | 1      | 0.32%   |
| Union Memory (Shenzhen)      | 1         | 1      | 0.32%   |
| TO Exter                     | 1         | 1      | 0.32%   |
| tecmiyo                      | 1         | 1      | 0.32%   |
| Team                         | 1         | 1      | 0.32%   |
| TARGET                       | 1         | 1      | 0.32%   |
| SandWind                     | 1         | 1      | 0.32%   |
| S3+                          | 1         | 1      | 0.32%   |
| Realtek Semiconductor        | 1         | 1      | 0.32%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 7         | 2.17%   |
| Toshiba MQ04ABF100 1TB                              | 6         | 1.86%   |
| Seagate ST1000LM035-1RK172 1TB                      | 5         | 1.55%   |
| Kingston SA400S37480G 480GB SSD                     | 5         | 1.55%   |
| Unknown MMC Card  64GB                              | 4         | 1.24%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB    | 4         | 1.24%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 4         | 1.24%   |
| WDC WD10SPZX-24Z10 1TB                              | 3         | 0.93%   |
| Toshiba XG6 NVMe SSD Controller 512GB               | 3         | 0.93%   |
| Seagate ST1000LM049-2GH172 1TB                      | 3         | 0.93%   |
| Seagate One Touch HDD 5TB                           | 3         | 0.93%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 3         | 0.93%   |
| Micron 2210_MTFDHBA512QFD 512GB                     | 3         | 0.93%   |
| Kingston SA400S37240G 240GB SSD                     | 3         | 0.93%   |
| JMicron Generic 250GB                               | 3         | 0.93%   |
| HGST HTS721010A9E630 1TB                            | 3         | 0.93%   |
| Unknown MMC Card  128GB                             | 2         | 0.62%   |
| Toshiba MK2555GSX 250GB                             | 2         | 0.62%   |
| Seagate ST750LM022 HN-M750MBB 752GB                 | 2         | 0.62%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 2         | 0.62%   |
| Seagate Expansion 1TB                               | 2         | 0.62%   |
| Seagate BUP Slim BK 1TB                             | 2         | 0.62%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB                | 2         | 0.62%   |
| Samsung SSD 980 1TB                                 | 2         | 0.62%   |
| Samsung SSD 870 EVO 500GB                           | 2         | 0.62%   |
| Samsung SSD 860 EVO 250GB                           | 2         | 0.62%   |
| Samsung SSD 860 EVO 1TB                             | 2         | 0.62%   |
| Samsung MZVLQ512HBLU-00BH1 512GB                    | 2         | 0.62%   |
| Samsung MZVLQ512HBLU-00B00 512GB                    | 2         | 0.62%   |
| Samsung MZALQ512HBLU-00BL2 512GB                    | 2         | 0.62%   |
| Samsung MZALQ256HBJD-00BL2 256GB                    | 2         | 0.62%   |
| Samsung MZALQ256HAJD-000L2 256GB                    | 2         | 0.62%   |
| SAGE 3639S 500GB                                    | 2         | 0.62%   |
| Phison E12 NVMe Controller 512GB                    | 2         | 0.62%   |
| OWC Mercury Electra 3G SSD                          | 2         | 0.62%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                 | 2         | 0.62%   |
| Micron 2200V_MTFDHBA512TCK 512GB                    | 2         | 0.62%   |
| KIOXIA KBG40ZNV256G 256GB                           | 2         | 0.62%   |
| Kingston SA400S37960G 960GB SSD                     | 2         | 0.62%   |
| Kingston OM8PCP3512F-AI1 512GB                      | 2         | 0.62%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 29        | 32     | 39.73%  |
| WDC                 | 15        | 16     | 20.55%  |
| Toshiba             | 13        | 13     | 17.81%  |
| HGST                | 6         | 7      | 8.22%   |
| Hitachi             | 4         | 4      | 5.48%   |
| SAGE                | 2         | 2      | 2.74%   |
| Unknown             | 1         | 1      | 1.37%   |
| TO Exter            | 1         | 1      | 1.37%   |
| Samsung Electronics | 1         | 1      | 1.37%   |
| KESU                | 1         | 1      | 1.37%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 23        | 25     | 21.3%   |
| Kingston            | 11        | 13     | 10.19%  |
| SanDisk             | 7         | 7      | 6.48%   |
| Crucial             | 6         | 6      | 5.56%   |
| Apple               | 5         | 5      | 4.63%   |
| WDC                 | 4         | 5      | 3.7%    |
| SK hynix            | 4         | 4      | 3.7%    |
| Transcend           | 3         | 3      | 2.78%   |
| OWC                 | 3         | 3      | 2.78%   |
| LITEONIT            | 3         | 3      | 2.78%   |
| JMicron Technology  | 3         | 3      | 2.78%   |
| Apacer              | 3         | 3      | 2.78%   |
| Toshiba             | 2         | 2      | 1.85%   |
| Micron Technology   | 2         | 2      | 1.85%   |
| Intel               | 2         | 2      | 1.85%   |
| China               | 2         | 2      | 1.85%   |
| A-DATA Technology   | 2         | 2      | 1.85%   |
| Zebronics           | 1         | 1      | 0.93%   |
| Vaseky              | 1         | 1      | 0.93%   |
| tecmiyo             | 1         | 1      | 0.93%   |
| Team                | 1         | 1      | 0.93%   |
| TARGET              | 1         | 1      | 0.93%   |
| S3+                 | 1         | 1      | 0.93%   |
| PNY                 | 1         | 1      | 0.93%   |
| Plextor             | 1         | 1      | 0.93%   |
| Phison              | 1         | 1      | 0.93%   |
| OSCOO               | 1         | 1      | 0.93%   |
| NT-1TB              | 1         | 1      | 0.93%   |
| LITEON              | 1         | 1      | 0.93%   |
| Kingmax             | 1         | 1      | 0.93%   |
| KingFast            | 1         | 1      | 0.93%   |
| Kingchuxing         | 1         | 1      | 0.93%   |
| Intenso             | 1         | 1      | 0.93%   |
| Imation             | 1         | 1      | 0.93%   |
| Hewlett-Packard     | 1         | 1      | 0.93%   |
| GOODRAM             | 1         | 1      | 0.93%   |
| GLOWAY              | 1         | 1      | 0.93%   |
| Emtec               | 1         | 1      | 0.93%   |
| Biostar             | 1         | 1      | 0.93%   |
| Azerty              | 1         | 1      | 0.93%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 113       | 140    | 39.1%   |
| SSD     | 95        | 113    | 32.87%  |
| HDD     | 69        | 78     | 23.88%  |
| MMC     | 8         | 12     | 2.77%   |
| Unknown | 4         | 4      | 1.38%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 138       | 172    | 49.11%  |
| NVMe | 113       | 138    | 40.21%  |
| SAS  | 22        | 25     | 7.83%   |
| MMC  | 8         | 12     | 2.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 97        | 115    | 58.43%  |
| 0.51-1.0   | 65        | 72     | 39.16%  |
| 4.01-10.0  | 3         | 3      | 1.81%   |
| 1.01-2.0   | 1         | 1      | 0.6%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 72        | 29.75%  |
| 251-500        | 53        | 21.9%   |
| 501-1000       | 31        | 12.81%  |
| More than 3000 | 22        | 9.09%   |
| 1001-2000      | 19        | 7.85%   |
| 51-100         | 14        | 5.79%   |
| Unknown        | 10        | 4.13%   |
| 21-50          | 9         | 3.72%   |
| 2001-3000      | 8         | 3.31%   |
| 1-20           | 4         | 1.65%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 101       | 41.74%  |
| 21-50          | 51        | 21.07%  |
| 51-100         | 30        | 12.4%   |
| 101-250        | 25        | 10.33%  |
| 251-500        | 12        | 4.96%   |
| Unknown        | 10        | 4.13%   |
| 501-1000       | 5         | 2.07%   |
| 2001-3000      | 4         | 1.65%   |
| More than 3000 | 2         | 0.83%   |
| 1001-2000      | 2         | 0.83%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                           | Notebooks | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| Toshiba MK2555GSX 250GB                                         | 2         | 2      | 5.56%   |
| WDC WD5000LPCX-22VHAT0 500GB                                    | 1         | 1      | 2.78%   |
| WDC WD2500BEVS-22UST0 250GB                                     | 1         | 1      | 2.78%   |
| WDC WD10SPZX-24Z10 1TB                                          | 1         | 1      | 2.78%   |
| WDC WD10JPVX-60JC3T0 1TB                                        | 1         | 1      | 2.78%   |
| WDC WD10 EZEX-08WN4A0 1TB                                       | 1         | 1      | 2.78%   |
| WDC WD Blue SA510 2.5 500GB                                     | 1         | 2      | 2.78%   |
| Toshiba MQ04ABF100 1TB                                          | 1         | 1      | 2.78%   |
| Toshiba MQ01ABF050M 500GB                                       | 1         | 1      | 2.78%   |
| Toshiba MQ01ABF050 500GB                                        | 1         | 1      | 2.78%   |
| Toshiba MK3261GSY 320GB                                         | 1         | 1      | 2.78%   |
| TARGET SSD 128G                                                 | 1         | 1      | 2.78%   |
| SK hynix HFS512G39TND-N210A 512GB SSD                           | 1         | 1      | 2.78%   |
| SK hynix HFS128G3BTND-N210A 128GB SSD                           | 1         | 1      | 2.78%   |
| SK hynix BC711 HFM512GD3JX013N 512GB                            | 1         | 1      | 2.78%   |
| Seagate ST9500325AS 500GB                                       | 1         | 1      | 2.78%   |
| Seagate ST9320423AS 320GB                                       | 1         | 1      | 2.78%   |
| Seagate ST500LT012-1DG142 500GB                                 | 1         | 1      | 2.78%   |
| Seagate ST500LM000-SSHD-8GB                                     | 1         | 1      | 2.78%   |
| Seagate ST320LT012-9WS14C 320GB                                 | 1         | 1      | 2.78%   |
| Seagate ST1000LM049-2GH172 1TB                                  | 1         | 1      | 2.78%   |
| Seagate ST1000LM048-2E7172 1TB                                  | 1         | 1      | 2.78%   |
| Seagate ST1000LM035-1RK172 1TB                                  | 1         | 1      | 2.78%   |
| Seagate ST1000LM014-SSHD-8GB                                    | 1         | 1      | 2.78%   |
| Samsung Electronics NVMe SSD Controller SM961/PM961/SM963 256GB | 1         | 1      | 2.78%   |
| Samsung Electronics HM100UI 1TB                                 | 1         | 1      | 2.78%   |
| SAGE 3639S 500GB                                                | 1         | 1      | 2.78%   |
| OWC Aura 2012 240GB SSD                                         | 1         | 1      | 2.78%   |
| LITEONIT DMT-80M6M-11 mSATA 80GB SSD                            | 1         | 1      | 2.78%   |
| Hitachi HTS547575A9E384 752GB                                   | 1         | 1      | 2.78%   |
| HGST HTS725032A7E630 320GB                                      | 1         | 1      | 2.78%   |
| HGST HTS721010A9E630 1TB                                        | 1         | 1      | 2.78%   |
| Crucial CT480BX200SSD1 480GB                                    | 1         | 1      | 2.78%   |
| Apple SSD SM0256F 256GB                                         | 1         | 1      | 2.78%   |
| A-DATA Technology SP900NS38 256GB SSD                           | 1         | 1      | 2.78%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 9      | 25%     |
| WDC                 | 6         | 7      | 16.67%  |
| Toshiba             | 6         | 6      | 16.67%  |
| SK hynix            | 3         | 3      | 8.33%   |
| Samsung Electronics | 2         | 2      | 5.56%   |
| HGST                | 2         | 2      | 5.56%   |
| TARGET              | 1         | 1      | 2.78%   |
| SAGE                | 1         | 1      | 2.78%   |
| OWC                 | 1         | 1      | 2.78%   |
| LITEONIT            | 1         | 1      | 2.78%   |
| Hitachi             | 1         | 1      | 2.78%   |
| Crucial             | 1         | 1      | 2.78%   |
| Apple               | 1         | 1      | 2.78%   |
| A-DATA Technology   | 1         | 1      | 2.78%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 9      | 36%     |
| Toshiba             | 6         | 6      | 24%     |
| WDC                 | 5         | 5      | 20%     |
| HGST                | 2         | 2      | 8%      |
| Samsung Electronics | 1         | 1      | 4%      |
| SAGE                | 1         | 1      | 4%      |
| Hitachi             | 1         | 1      | 4%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 25        | 25     | 69.44%  |
| SSD  | 9         | 10     | 25%     |
| NVMe | 2         | 2      | 5.56%   |

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
| Works    | 190       | 251    | 71.7%   |
| Detected | 39        | 58     | 14.72%  |
| Malfunc  | 35        | 37     | 13.21%  |
| Fixed    | 1         | 1      | 0.38%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 158       | 53.2%   |
| Samsung Electronics                     | 40        | 13.47%  |
| AMD                                     | 23        | 7.74%   |
| SanDisk                                 | 16        | 5.39%   |
| SK hynix                                | 10        | 3.37%   |
| Kingston Technology Company             | 9         | 3.03%   |
| Micron Technology                       | 8         | 2.69%   |
| Toshiba America Info Systems            | 6         | 2.02%   |
| KIOXIA                                  | 6         | 2.02%   |
| Phison Electronics                      | 4         | 1.35%   |
| Yangtze Memory Technologies             | 2         | 0.67%   |
| Silicon Motion                          | 2         | 0.67%   |
| Shenzhen Longsys Electronics            | 2         | 0.67%   |
| Nvidia                                  | 2         | 0.67%   |
| Micron/Crucial Technology               | 2         | 0.67%   |
| ADATA Technology                        | 2         | 0.67%   |
| Shenzhen Unionmemory Information System | 1         | 0.34%   |
| Seagate Technology                      | 1         | 0.34%   |
| Realtek Semiconductor                   | 1         | 0.34%   |
| Marvell Technology Group                | 1         | 0.34%   |
| Biwin Storage Technology                | 1         | 0.34%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Volume Management Device NVMe RAID Controller                            | 20        | 6.31%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 19        | 5.99%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 17        | 5.36%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 17        | 5.36%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 16        | 5.05%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 15        | 4.73%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 14        | 4.42%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 10        | 3.15%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 9         | 2.84%   |
| Intel Tiger Lake-LP SATA Controller                                            | 9         | 2.84%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 8         | 2.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 8         | 2.52%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 7         | 2.21%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 7         | 2.21%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 5         | 1.58%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 5         | 1.58%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 5         | 1.58%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 5         | 1.58%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 4         | 1.26%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 1.26%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4         | 1.26%   |
| Micron 2200S NVMe SSD [Cassandra]                                              | 4         | 1.26%   |
| Intel Optane NVME SSD H10 with Solid State Storage [Teton Glacier]             | 4         | 1.26%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 1.26%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 4         | 1.26%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 3         | 0.95%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 3         | 0.95%   |
| Samsung S4LN053X01 AHCI SSD Controller(Apple slot)                             | 3         | 0.95%   |
| Phison E12 NVMe Controller                                                     | 3         | 0.95%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 3         | 0.95%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                  | 3         | 0.95%   |
| Kingston Company A1000/U-SNS8154P3 x2 NVMe SSD                                 | 3         | 0.95%   |
| Intel SSD 660P Series                                                          | 3         | 0.95%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 3         | 0.95%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 3         | 0.95%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)            | 2         | 0.63%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2         | 0.63%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 2         | 0.63%   |
| SanDisk PC SN520 x2 M.2 2242 NVMe SSD                                          | 2         | 0.63%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                  | 2         | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 156       | 50.49%  |
| NVMe | 113       | 36.57%  |
| RAID | 38        | 12.3%   |
| IDE  | 2         | 0.65%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 189       | 80.43%  |
| AMD    | 46        | 19.57%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 8         | 3.4%    |
| AMD Ryzen 5 5500U with Radeon Graphics        | 6         | 2.55%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 5         | 2.13%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 5         | 2.13%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 5         | 2.13%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 5         | 2.13%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 1.7%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 1.7%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 4         | 1.7%    |
| Intel Core i5-9300H CPU @ 2.40GHz             | 4         | 1.7%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 1.7%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 1.7%    |
| Intel Core i3-5005U CPU @ 2.00GHz             | 4         | 1.7%    |
| Intel Celeron N4020 CPU @ 1.10GHz             | 4         | 1.7%    |
| Intel 12th Gen Core i5-12450H                 | 4         | 1.7%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 1.7%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 4         | 1.7%    |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 3         | 1.28%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 1.28%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 1.28%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 1.28%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 1.28%   |
| Intel 11th Gen Core i5-11300H @ 3.10GHz       | 3         | 1.28%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 1.28%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 3         | 1.28%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.28%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 2         | 0.85%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 0.85%   |
| Intel Core i7-4712HQ CPU @ 2.30GHz            | 2         | 0.85%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 2         | 0.85%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 2         | 0.85%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 0.85%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 0.85%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 0.85%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 2         | 0.85%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 2         | 0.85%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 0.85%   |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz          | 2         | 0.85%   |
| Intel 11th Gen Core i5-11400H @ 2.70GHz       | 2         | 0.85%   |
| Intel 11th Gen Core i5-11320H @ 3.20GHz       | 2         | 0.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 58        | 24.68%  |
| Intel Core i7           | 51        | 21.7%   |
| Other                   | 38        | 16.17%  |
| Intel Core i3           | 23        | 9.79%   |
| AMD Ryzen 5             | 23        | 9.79%   |
| Intel Core 2 Duo        | 8         | 3.4%    |
| AMD Ryzen 7             | 7         | 2.98%   |
| Intel Celeron           | 4         | 1.7%    |
| AMD Ryzen 3             | 4         | 1.7%    |
| Intel Xeon              | 2         | 0.85%   |
| Intel Pentium           | 2         | 0.85%   |
| AMD Ryzen 7 PRO         | 2         | 0.85%   |
| Intel Pentium Silver    | 1         | 0.43%   |
| Intel Pentium Dual-Core | 1         | 0.43%   |
| Intel Core M            | 1         | 0.43%   |
| Intel Atom              | 1         | 0.43%   |
| AMD Turion II Dual-Core | 1         | 0.43%   |
| AMD Phenom II           | 1         | 0.43%   |
| AMD E1                  | 1         | 0.43%   |
| AMD E                   | 1         | 0.43%   |
| AMD C-60                | 1         | 0.43%   |
| AMD Athlon              | 1         | 0.43%   |
| AMD A6                  | 1         | 0.43%   |
| AMD A4                  | 1         | 0.43%   |
| AMD A12                 | 1         | 0.43%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 104       | 44.26%  |
| 4      | 86        | 36.6%   |
| 6      | 25        | 10.64%  |
| 8      | 14        | 5.96%   |
| 12     | 3         | 1.28%   |
| 16     | 1         | 0.43%   |
| 14     | 1         | 0.43%   |
| 10     | 1         | 0.43%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 235       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 208       | 88.14%  |
| 1      | 28        | 11.86%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 235       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 152       | 63.87%  |
| 0x08108109 | 8         | 3.36%   |
| 0x806c1    | 7         | 2.94%   |
| 0x806ec    | 6         | 2.52%   |
| 0x906ea    | 4         | 1.68%   |
| 0x306a9    | 4         | 1.68%   |
| 0x08608103 | 4         | 1.68%   |
| 0x906e9    | 3         | 1.26%   |
| 0x806e9    | 3         | 1.26%   |
| 0x206a7    | 3         | 1.26%   |
| 0x0a50000c | 3         | 1.26%   |
| 0x08600106 | 3         | 1.26%   |
| 0x08108102 | 3         | 1.26%   |
| 0x806eb    | 2         | 0.84%   |
| 0x706a8    | 2         | 0.84%   |
| 0x40651    | 2         | 0.84%   |
| 0x0a404102 | 2         | 0.84%   |
| 0x08608104 | 2         | 0.84%   |
| 0x06006705 | 2         | 0.84%   |
| 0x05000101 | 2         | 0.84%   |
| 0xa0652    | 1         | 0.42%   |
| 0x906ed    | 1         | 0.42%   |
| 0x906eb    | 1         | 0.42%   |
| 0x906a3    | 1         | 0.42%   |
| 0x806d1    | 1         | 0.42%   |
| 0x706e5    | 1         | 0.42%   |
| 0x506e3    | 1         | 0.42%   |
| 0x406e3    | 1         | 0.42%   |
| 0x40661    | 1         | 0.42%   |
| 0x306d4    | 1         | 0.42%   |
| 0x306c3    | 1         | 0.42%   |
| 0x20652    | 1         | 0.42%   |
| 0x1067a    | 1         | 0.42%   |
| 0x0a50000d | 1         | 0.42%   |
| 0x0a404101 | 1         | 0.42%   |
| 0x08608102 | 1         | 0.42%   |
| 0x0810100b | 1         | 0.42%   |
| 0x0600611a | 1         | 0.42%   |
| 0x0500010d | 1         | 0.42%   |
| 0x03000027 | 1         | 0.42%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 49        | 20.85%  |
| TigerLake        | 23        | 9.79%   |
| Haswell          | 22        | 9.36%   |
| Broadwell        | 15        | 6.38%   |
| IvyBridge        | 14        | 5.96%   |
| SandyBridge      | 13        | 5.53%   |
| Zen+             | 12        | 5.11%   |
| IceLake          | 12        | 5.11%   |
| Alderlake Hybrid | 10        | 4.26%   |
| Unknown          | 10        | 4.26%   |
| Skylake          | 8         | 3.4%    |
| Zen 3            | 7         | 2.98%   |
| Zen 2            | 7         | 2.98%   |
| Penryn           | 7         | 2.98%   |
| Goldmont plus    | 4         | 1.7%    |
| CometLake        | 4         | 1.7%    |
| Westmere         | 3         | 1.28%   |
| Excavator        | 3         | 1.28%   |
| Bobcat           | 3         | 1.28%   |
| K10              | 2         | 0.85%   |
| Core             | 2         | 0.85%   |
| Zen              | 1         | 0.43%   |
| Tremont          | 1         | 0.43%   |
| Silvermont       | 1         | 0.43%   |
| K10 Llano        | 1         | 0.43%   |
| Gracemont        | 1         | 0.43%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 179       | 56.47%  |
| Nvidia | 82        | 25.87%  |
| AMD    | 56        | 17.67%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 15        | 4.64%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 13        | 4.02%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 12        | 3.72%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 12        | 3.72%   |
| Intel HD Graphics 5500                                                    | 11        | 3.41%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 10        | 3.1%    |
| Intel UHD Graphics 620                                                    | 10        | 3.1%    |
| Intel Haswell-ULT Integrated Graphics Controller                          | 10        | 3.1%    |
| Intel HD Graphics 620                                                     | 9         | 2.79%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                 | 8         | 2.48%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 8         | 2.48%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 8         | 2.48%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 7         | 2.17%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 7         | 2.17%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 7         | 2.17%   |
| AMD Lucienne                                                              | 7         | 2.17%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 6         | 1.86%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]             | 6         | 1.86%   |
| Intel HD Graphics 630                                                     | 5         | 1.55%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 5         | 1.55%   |
| Nvidia GP108M [GeForce MX150]                                             | 4         | 1.24%   |
| Nvidia GM108M [GeForce 940MX]                                             | 4         | 1.24%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 4         | 1.24%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 4         | 1.24%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 4         | 1.24%   |
| Intel Alder Lake-P GT1 [UHD Graphics]                                     | 4         | 1.24%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 3         | 0.93%   |
| Nvidia GK107GLM [Quadro K1100M]                                           | 3         | 0.93%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 3         | 0.93%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 3         | 0.93%   |
| Intel HD Graphics 530                                                     | 3         | 0.93%   |
| Intel Core Processor Integrated Graphics Controller                       | 3         | 0.93%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 3         | 0.93%   |
| AMD Rembrandt [Radeon 680M]                                               | 3         | 0.93%   |
| Nvidia GP108M [GeForce MX250]                                             | 2         | 0.62%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 2         | 0.62%   |
| Nvidia GM108M [GeForce 840M]                                              | 2         | 0.62%   |
| Nvidia GK208BM [GeForce 920M]                                             | 2         | 0.62%   |
| Nvidia GK106M [GeForce GTX 770M]                                          | 2         | 0.62%   |
| Nvidia GF108GLM [NVS 5200M]                                               | 2         | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 101       | 42.98%  |
| Intel + Nvidia | 65        | 27.66%  |
| 1 x AMD        | 35        | 14.89%  |
| AMD + Nvidia   | 9         | 3.83%   |
| 1 x Nvidia     | 8         | 3.4%    |
| Intel + AMD    | 8         | 3.4%    |
| 2 x Intel      | 5         | 2.13%   |
| 2 x AMD        | 4         | 1.7%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 199       | 83.61%  |
| Proprietary | 39        | 16.39%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 151       | 63.98%  |
| 1.01-2.0   | 27        | 11.44%  |
| 0.01-0.5   | 23        | 9.75%   |
| 3.01-4.0   | 17        | 7.2%    |
| 0.51-1.0   | 9         | 3.81%   |
| 5.01-6.0   | 4         | 1.69%   |
| 2.01-3.0   | 4         | 1.69%   |
| 7.01-8.0   | 1         | 0.42%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 59        | 21.85%  |
| AU Optronics            | 49        | 18.15%  |
| Chimei Innolux          | 42        | 15.56%  |
| LG Display              | 33        | 12.22%  |
| Samsung Electronics     | 19        | 7.04%   |
| Apple                   | 13        | 4.81%   |
| PANDA                   | 7         | 2.59%   |
| Sharp                   | 5         | 1.85%   |
| Goldstar                | 4         | 1.48%   |
| Sony                    | 3         | 1.11%   |
| Philips                 | 3         | 1.11%   |
| CSO                     | 3         | 1.11%   |
| Chi Mei Optoelectronics | 3         | 1.11%   |
| BenQ                    | 3         | 1.11%   |
| TMX                     | 2         | 0.74%   |
| RTK                     | 2         | 0.74%   |
| Lenovo                  | 2         | 0.74%   |
| Hewlett-Packard         | 2         | 0.74%   |
| Dell                    | 2         | 0.74%   |
| Yamaha                  | 1         | 0.37%   |
| Wacom                   | 1         | 0.37%   |
| Vizio                   | 1         | 0.37%   |
| Toshiba                 | 1         | 0.37%   |
| Sceptre Tech            | 1         | 0.37%   |
| LGD                     | 1         | 0.37%   |
| LG Philips              | 1         | 0.37%   |
| KDB                     | 1         | 0.37%   |
| ITE                     | 1         | 0.37%   |
| HUAWEI                  | 1         | 0.37%   |
| HKC                     | 1         | 0.37%   |
| Eizo                    | 1         | 0.37%   |
| CTO                     | 1         | 0.37%   |
| Acer                    | 1         | 0.37%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch        | 5         | 1.85%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch        | 4         | 1.48%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch         | 3         | 1.11%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                   | 3         | 1.11%   |
| BOE LCD Monitor BOE084E 1920x1080 382x215mm 17.3-inch                   | 3         | 1.11%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch          | 3         | 1.11%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                    | 3         | 1.11%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch       | 2         | 0.74%   |
| Samsung Electronics LCD Monitor SAM0F14 3840x2160 1872x1053mm 84.6-inch | 2         | 0.74%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                 | 2         | 0.74%   |
| LG Display LCD Monitor LGD05FE 1920x1080 344x194mm 15.5-inch            | 2         | 0.74%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch            | 2         | 0.74%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch             | 2         | 0.74%   |
| LG Display LCD Monitor LGD02DA 1920x1080 380x220mm 17.3-inch            | 2         | 0.74%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch        | 2         | 0.74%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch         | 2         | 0.74%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch        | 2         | 0.74%   |
| BOE LCD Monitor BOE0A81 1920x1080 344x194mm 15.5-inch                   | 2         | 0.74%   |
| BOE LCD Monitor BOE09AE 1920x1080 309x174mm 14.0-inch                   | 2         | 0.74%   |
| BOE LCD Monitor BOE0816 1366x768 344x193mm 15.5-inch                    | 2         | 0.74%   |
| BOE LCD Monitor BOE0704 1366x768 344x194mm 15.5-inch                    | 2         | 0.74%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                   | 2         | 0.74%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch           | 2         | 0.74%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch           | 2         | 0.74%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch          | 2         | 0.74%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch           | 2         | 0.74%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch          | 2         | 0.74%   |
| Apple Color LCD APPA022 2880x1800 331x207mm 15.4-inch                   | 2         | 0.74%   |
| Yamaha RX-V473 YMH3171 1920x540                                         | 1         | 0.37%   |
| Wacom Cintiq 16 WAC1071 1920x1080 344x193mm 15.5-inch                   | 1         | 0.37%   |
| Vizio V505-H1 VIZ1039 3840x2160 941x529mm 42.5-inch                     | 1         | 0.37%   |
| Toshiba TV TSB0205 1360x768 886x498mm 40.0-inch                         | 1         | 0.37%   |
| TMX TL156VDXP0101 TMX1561 1920x1080 344x194mm 15.5-inch                 | 1         | 0.37%   |
| TMX LCD Monitor TMX1560 1920x1080 344x194mm 15.5-inch                   | 1         | 0.37%   |
| Sony TV SNYF500 1360x768                                                | 1         | 0.37%   |
| Sony TV SNY3002 1920x1080 1018x573mm 46.0-inch                          | 1         | 0.37%   |
| Sony LCD Monitor MS_9005 1920x1200 331x207mm 15.4-inch                  | 1         | 0.37%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                 | 1         | 0.37%   |
| Sharp LCD Monitor SHP14B9 3840x2160 344x194mm 15.5-inch                 | 1         | 0.37%   |
| Sharp LCD Monitor SHP143B 3840x2160 346x194mm 15.6-inch                 | 1         | 0.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 137       | 53.1%   |
| 1366x768 (WXGA)    | 56        | 21.71%  |
| 1600x900 (HD+)     | 13        | 5.04%   |
| 3840x2160 (4K)     | 9         | 3.49%   |
| 1280x800 (WXGA)    | 7         | 2.71%   |
| 2560x1600          | 5         | 1.94%   |
| 2560x1440 (QHD)    | 5         | 1.94%   |
| 1920x1200 (WUXGA)  | 5         | 1.94%   |
| 1440x900 (WXGA+)   | 5         | 1.94%   |
| 2880x1800          | 3         | 1.16%   |
| 2160x1440          | 3         | 1.16%   |
| 3200x1800 (QHD+)   | 2         | 0.78%   |
| 2560x1080          | 2         | 0.78%   |
| 1680x1050 (WSXGA+) | 2         | 0.78%   |
| 3840x2400          | 1         | 0.39%   |
| 3200x2000          | 1         | 0.39%   |
| 1920x540           | 1         | 0.39%   |
| 1360x768           | 1         | 0.39%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 123       | 45.56%  |
| 13      | 42        | 15.56%  |
| 14      | 40        | 14.81%  |
| 17      | 15        | 5.56%   |
| 16      | 7         | 2.59%   |
| 23      | 6         | 2.22%   |
| 24      | 5         | 1.85%   |
| 21      | 5         | 1.85%   |
| 31      | 4         | 1.48%   |
| 84      | 3         | 1.11%   |
| 27      | 3         | 1.11%   |
| 72      | 2         | 0.74%   |
| 12      | 2         | 0.74%   |
| Unknown | 2         | 0.74%   |
| 69      | 1         | 0.37%   |
| 54      | 1         | 0.37%   |
| 46      | 1         | 0.37%   |
| 41      | 1         | 0.37%   |
| 34      | 1         | 0.37%   |
| 28      | 1         | 0.37%   |
| 20      | 1         | 0.37%   |
| 19      | 1         | 0.37%   |
| 18      | 1         | 0.37%   |
| 11      | 1         | 0.37%   |
| 10      | 1         | 0.37%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 186       | 68.89%  |
| 201-300     | 26        | 9.63%   |
| 351-400     | 18        | 6.67%   |
| 501-600     | 14        | 5.19%   |
| 401-500     | 9         | 3.33%   |
| 1501-2000   | 6         | 2.22%   |
| 601-700     | 5         | 1.85%   |
| 1001-1500   | 2         | 0.74%   |
| Unknown     | 2         | 0.74%   |
| 701-800     | 1         | 0.37%   |
| 901-1000    | 1         | 0.37%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 203       | 84.94%  |
| 16/10   | 29        | 12.13%  |
| 3/2     | 3         | 1.26%   |
| 21/9    | 2         | 0.84%   |
| 32/9    | 1         | 0.42%   |
| Unknown | 1         | 0.42%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 125       | 46.64%  |
| 81-90          | 68        | 25.37%  |
| 121-130        | 15        | 5.6%    |
| 71-80          | 14        | 5.22%   |
| 201-250        | 12        | 4.48%   |
| More than 1000 | 7         | 2.61%   |
| 351-500        | 5         | 1.87%   |
| 151-200        | 5         | 1.87%   |
| 111-120        | 4         | 1.49%   |
| 301-350        | 3         | 1.12%   |
| 61-70          | 2         | 0.75%   |
| 501-1000       | 2         | 0.75%   |
| Unknown        | 2         | 0.75%   |
| 51-60          | 1         | 0.37%   |
| 41-50          | 1         | 0.37%   |
| 251-300        | 1         | 0.37%   |
| 141-150        | 1         | 0.37%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 131       | 49.25%  |
| 101-120       | 66        | 24.81%  |
| 51-100        | 30        | 11.28%  |
| 161-240       | 24        | 9.02%   |
| More than 240 | 9         | 3.38%   |
| 1-50          | 4         | 1.5%    |
| Unknown       | 2         | 0.75%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 197       | 83.83%  |
| 2     | 35        | 14.89%  |
| 3     | 3         | 1.28%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 128       | 36.57%  |
| Realtek Semiconductor             | 126       | 36%     |
| Qualcomm Atheros                  | 34        | 9.71%   |
| Broadcom                          | 21        | 6%      |
| Broadcom Limited                  | 9         | 2.57%   |
| ASIX Electronics                  | 6         | 1.71%   |
| MediaTek                          | 5         | 1.43%   |
| TP-Link                           | 3         | 0.86%   |
| Sierra Wireless                   | 2         | 0.57%   |
| Samsung Electronics               | 2         | 0.57%   |
| Qualcomm                          | 2         | 0.57%   |
| Nvidia                            | 2         | 0.57%   |
| Ericsson Business Mobile Networks | 2         | 0.57%   |
| Ralink Technology                 | 1         | 0.29%   |
| Ralink                            | 1         | 0.29%   |
| OPPO Electronics                  | 1         | 0.29%   |
| Microchip Technology              | 1         | 0.29%   |
| Marvell Technology Group          | 1         | 0.29%   |
| Huawei Technologies               | 1         | 0.29%   |
| Dell                              | 1         | 0.29%   |
| ASUSTek Computer                  | 1         | 0.29%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 79        | 18.68%  |
| Intel Wi-Fi 6 AX201                                                  | 17        | 4.02%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 14        | 3.31%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 14        | 3.31%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 13        | 3.07%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 12        | 2.84%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                             | 10        | 2.36%   |
| Intel Wireless 8265 / 8275                                           | 10        | 2.36%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 8         | 1.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 8         | 1.89%   |
| Intel Wireless 7260                                                  | 7         | 1.65%   |
| Intel Wi-Fi 6 AX200                                                  | 7         | 1.65%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 7         | 1.65%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 6         | 1.42%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 6         | 1.42%   |
| Intel Wireless 8260                                                  | 6         | 1.42%   |
| Intel Wireless 7265                                                  | 6         | 1.42%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 6         | 1.42%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 6         | 1.42%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 6         | 1.42%   |
| ASIX AX88179 Gigabit Ethernet                                        | 6         | 1.42%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 5         | 1.18%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 4         | 0.95%   |
| Intel Ethernet Connection (4) I219-LM                                | 4         | 0.95%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 4         | 0.95%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                    | 4         | 0.95%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 4         | 0.95%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 3         | 0.71%   |
| Intel Wireless 3165                                                  | 3         | 0.71%   |
| Intel Wireless 3160                                                  | 3         | 0.71%   |
| Intel Ethernet Connection I218-LM                                    | 3         | 0.71%   |
| Intel Ethernet Connection (2) I219-LM                                | 3         | 0.71%   |
| Intel Centrino Wireless-N 2230                                       | 3         | 0.71%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 3         | 0.71%   |
| Broadcom Limited BCM4352 802.11ac Dual Band Wireless Network Adapter | 3         | 0.71%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 3         | 0.71%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 2         | 0.47%   |
| Sierra Wireless EM7455                                               | 2         | 0.47%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)          | 2         | 0.47%   |
| Realtek RTL8852AE WiFi 6 802.11ax PCIe Adapter                       | 2         | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 126       | 52.5%   |
| Realtek Semiconductor | 45        | 18.75%  |
| Qualcomm Atheros      | 28        | 11.67%  |
| Broadcom              | 18        | 7.5%    |
| Broadcom Limited      | 8         | 3.33%   |
| MediaTek              | 5         | 2.08%   |
| TP-Link               | 3         | 1.25%   |
| Sierra Wireless       | 2         | 0.83%   |
| Ralink Technology     | 1         | 0.42%   |
| Ralink                | 1         | 0.42%   |
| Qualcomm              | 1         | 0.42%   |
| Dell                  | 1         | 0.42%   |
| ASUSTek Computer      | 1         | 0.42%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                                  | 17        | 7.08%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 14        | 5.83%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 13        | 5.42%   |
| Intel Wireless 8265 / 8275                                           | 10        | 4.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 8         | 3.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 8         | 3.33%   |
| Intel Wireless 7260                                                  | 7         | 2.92%   |
| Intel Wi-Fi 6 AX200                                                  | 7         | 2.92%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 7         | 2.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 6         | 2.5%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 6         | 2.5%    |
| Intel Wireless 8260                                                  | 6         | 2.5%    |
| Intel Wireless 7265                                                  | 6         | 2.5%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 6         | 2.5%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 6         | 2.5%    |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 6         | 2.5%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 5         | 2.08%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 4         | 1.67%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 4         | 1.67%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 4         | 1.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 3         | 1.25%   |
| Intel Wireless 3165                                                  | 3         | 1.25%   |
| Intel Wireless 3160                                                  | 3         | 1.25%   |
| Intel Centrino Wireless-N 2230                                       | 3         | 1.25%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 3         | 1.25%   |
| Broadcom Limited BCM4352 802.11ac Dual Band Wireless Network Adapter | 3         | 1.25%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 3         | 1.25%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 2         | 0.83%   |
| Sierra Wireless EM7455                                               | 2         | 0.83%   |
| Realtek RTL8852AE WiFi 6 802.11ax PCIe Adapter                       | 2         | 0.83%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 2         | 0.83%   |
| Realtek RTL8723DE Wireless Network Adapter                           | 2         | 0.83%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 2         | 0.83%   |
| Intel Wireless-AC 9260                                               | 2         | 0.83%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 2         | 0.83%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 2         | 0.83%   |
| Intel Gemini Lake PCH CNVi WiFi                                      | 2         | 0.83%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 2         | 0.83%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 2         | 0.83%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 2         | 0.83%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 104       | 59.09%  |
| Intel                    | 42        | 23.86%  |
| Qualcomm Atheros         | 9         | 5.11%   |
| Broadcom                 | 7         | 3.98%   |
| ASIX Electronics         | 6         | 3.41%   |
| Nvidia                   | 2         | 1.14%   |
| Qualcomm                 | 1         | 0.57%   |
| OPPO Electronics         | 1         | 0.57%   |
| Microchip Technology     | 1         | 0.57%   |
| Marvell Technology Group | 1         | 0.57%   |
| Huawei Technologies      | 1         | 0.57%   |
| Broadcom Limited         | 1         | 0.57%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 79        | 44.13%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 7.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 12        | 6.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 10        | 5.59%   |
| ASIX AX88179 Gigabit Ethernet                                     | 6         | 3.35%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 2.23%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 2.23%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.68%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 1.68%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 1.12%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 1.12%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.12%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.12%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 1.12%   |
| Intel Ethernet Connection (3) I218-V                              | 2         | 1.12%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 1.12%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.56%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.56%   |
| Qualcomm Fairphone 4 5G                                           | 1         | 0.56%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.56%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.56%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.56%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.56%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.56%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.56%   |
| OPPO RMX3623                                                      | 1         | 0.56%   |
| Nvidia MCP89 Ethernet                                             | 1         | 0.56%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.56%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                     | 1         | 0.56%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.56%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.56%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.56%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.56%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.56%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.56%   |
| Intel Ethernet Connection (23) I219-LM                            | 1         | 0.56%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 0.56%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 0.56%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 0.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 230       | 56.65%  |
| Ethernet | 172       | 42.36%  |
| Modem    | 4         | 0.99%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 186       | 79.49%  |
| Ethernet | 48        | 20.51%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 152       | 64.68%  |
| 1     | 81        | 34.47%  |
| 0     | 2         | 0.85%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 154       | 65.53%  |
| Yes  | 81        | 34.47%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 106       | 50.48%  |
| Realtek Semiconductor           | 27        | 12.86%  |
| Qualcomm Atheros Communications | 14        | 6.67%   |
| IMC Networks                    | 14        | 6.67%   |
| Apple                           | 12        | 5.71%   |
| Broadcom                        | 11        | 5.24%   |
| Lite-On Technology              | 7         | 3.33%   |
| Realtek                         | 6         | 2.86%   |
| Foxconn / Hon Hai               | 5         | 2.38%   |
| Dell                            | 3         | 1.43%   |
| Toshiba                         | 2         | 0.95%   |
| USI                             | 1         | 0.48%   |
| Cambridge Silicon Radio         | 1         | 0.48%   |
| Alps Electric                   | 1         | 0.48%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface              | 34        | 16.19%  |
| Intel AX201 Bluetooth                           | 28        | 13.33%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)  | 27        | 12.86%  |
| Realtek Bluetooth Radio                         | 17        | 8.1%    |
| Qualcomm Atheros  Bluetooth Device              | 11        | 5.24%   |
| Intel AX200 Bluetooth                           | 7         | 3.33%   |
| Apple Bluetooth Host Controller                 | 7         | 3.33%   |
| Realtek 802.11ac WLAN Adapter                   | 6         | 2.86%   |
| IMC Networks Bluetooth Radio                    | 6         | 2.86%   |
| Realtek  Bluetooth 4.2 Adapter                  | 5         | 2.38%   |
| Realtek 802.11ac WLAN Adapter                   | 4         | 1.9%    |
| Intel Centrino Bluetooth Wireless Transceiver   | 4         | 1.9%    |
| IMC Networks Wireless_Device                    | 4         | 1.9%    |
| Apple Bluetooth USB Host Controller             | 4         | 1.9%    |
| Lite-On Bluetooth Device                        | 3         | 1.43%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]      | 3         | 1.43%   |
| Lite-On Atheros AR3012 Bluetooth                | 2         | 0.95%   |
| Intel Wireless-AC 9260 Bluetooth Adapter        | 2         | 0.95%   |
| Intel Wireless-AC 3168 Bluetooth                | 2         | 0.95%   |
| IMC Networks Bluetooth Device                   | 2         | 0.95%   |
| IMC Networks BCM20702A0                         | 2         | 0.95%   |
| Broadcom BCM20702A0 Bluetooth                   | 2         | 0.95%   |
| USI Bluetooth Device                            | 1         | 0.48%   |
| Toshiba Integrated Bluetooth HCI                | 1         | 0.48%   |
| Toshiba BCM43142A0                              | 1         | 0.48%   |
| Realtek RTL8723B Bluetooth                      | 1         | 0.48%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0          | 1         | 0.48%   |
| Qualcomm Atheros Bluetooth (AR3011)             | 1         | 0.48%   |
| Qualcomm Atheros AR3012 Bluetooth               | 1         | 0.48%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth      | 1         | 0.48%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device    | 1         | 0.48%   |
| Intel Bluetooth Device                          | 1         | 0.48%   |
| Intel AX210 Bluetooth                           | 1         | 0.48%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter    | 1         | 0.48%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth | 1         | 0.48%   |
| Foxconn / Hon Hai Bluetooth Device              | 1         | 0.48%   |
| Foxconn / Hon Hai Bluetooth Adapter             | 1         | 0.48%   |
| Foxconn / Hon Hai Acer Bluetooth module         | 1         | 0.48%   |
| Dell Wireless 360 Bluetooth                     | 1         | 0.48%   |
| Dell DW375 Bluetooth Module                     | 1         | 0.48%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 186       | 63.27%  |
| AMD                        | 50        | 17.01%  |
| Nvidia                     | 44        | 14.97%  |
| GN Netcom                  | 2         | 0.68%   |
| Generalplus Technology     | 2         | 0.68%   |
| C-Media Electronics        | 2         | 0.68%   |
| Samsung Electronics        | 1         | 0.34%   |
| Realtek Semiconductor      | 1         | 0.34%   |
| PreSonus Audio Electronics | 1         | 0.34%   |
| Lenovo                     | 1         | 0.34%   |
| JMTek                      | 1         | 0.34%   |
| Digidesign                 | 1         | 0.34%   |
| Barco Display Systems      | 1         | 0.34%   |
| ASUSTek Computer           | 1         | 0.34%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 34        | 9.21%   |
| Intel Sunrise Point-LP HD Audio                                            | 24        | 6.5%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 23        | 6.23%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 18        | 4.88%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 17        | 4.61%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 15        | 4.07%   |
| Intel Broadwell-U Audio Controller                                         | 15        | 4.07%   |
| Intel Haswell-ULT HD Audio Controller                                      | 11        | 2.98%   |
| Intel Cannon Lake PCH cAVS                                                 | 11        | 2.98%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 11        | 2.98%   |
| Intel 8 Series HD Audio Controller                                         | 11        | 2.98%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 11        | 2.98%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 10        | 2.71%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 9         | 2.44%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 8         | 2.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 8         | 2.17%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 8         | 2.17%   |
| Nvidia GA106 High Definition Audio Controller                              | 6         | 1.63%   |
| Intel CM238 HD Audio Controller                                            | 6         | 1.63%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 6         | 1.63%   |
| Nvidia Audio device                                                        | 5         | 1.36%   |
| Intel Comet Lake PCH-LP cAVS                                               | 5         | 1.36%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 1.36%   |
| Nvidia TU116 High Definition Audio Controller                              | 4         | 1.08%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 1.08%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 1.08%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4         | 1.08%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3         | 0.81%   |
| Nvidia GK107 HDMI Audio Controller                                         | 3         | 0.81%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 0.81%   |
| Intel Comet Lake PCH cAVS                                                  | 3         | 0.81%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 0.81%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 3         | 0.81%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 3         | 0.81%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 0.54%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 0.54%   |
| Nvidia GK106 HDMI Audio Controller                                         | 2         | 0.54%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 0.54%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 2         | 0.54%   |
| Intel Crystal Well HD Audio Controller                                     | 2         | 0.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 80        | 29.52%  |
| Samsung Electronics | 72        | 26.57%  |
| Micron Technology   | 44        | 16.24%  |
| Crucial             | 16        | 5.9%    |
| Kingston            | 14        | 5.17%   |
| Ramaxel Technology  | 11        | 4.06%   |
| Elpida              | 8         | 2.95%   |
| Unknown             | 7         | 2.58%   |
| A-DATA Technology   | 3         | 1.11%   |
| Team                | 2         | 0.74%   |
| Smart               | 2         | 0.74%   |
| GOODRAM             | 2         | 0.74%   |
| Corsair             | 2         | 0.74%   |
| Timetec             | 1         | 0.37%   |
| Smart Brazil        | 1         | 0.37%   |
| Qimonda             | 1         | 0.37%   |
| PNY                 | 1         | 0.37%   |
| Nanya Technology    | 1         | 0.37%   |
| Magnum Tech         | 1         | 0.37%   |
| KingFast            | 1         | 0.37%   |
| Kimtigo             | 1         | 0.37%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 8         | 2.84%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 7         | 2.48%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 6         | 2.13%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 5         | 1.77%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 1.77%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 5         | 1.77%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 4         | 1.42%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 4         | 1.42%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 1.42%   |
| Micron RAM 4ATF51264HZ_3G2J1 4GB Row Of Chips DDR4 3200MT/s      | 4         | 1.42%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.06%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 1.06%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.06%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 1.06%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 3         | 1.06%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.06%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 3         | 1.06%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 3         | 1.06%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 2         | 0.71%   |
| SK hynix RAM HMT451S6MFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 0.71%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.71%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.71%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 0.71%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 0.71%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 0.71%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.71%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 0.71%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 2         | 0.71%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.71%   |
| SK hynix RAM HMA81GS6DJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.71%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.71%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 2         | 0.71%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s | 2         | 0.71%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 2         | 0.71%   |
| Samsung RAM Module 4GB SODIMM DDR3 1333MT/s                      | 2         | 0.71%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 2         | 0.71%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.71%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.71%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.71%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s            | 2         | 0.71%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 121       | 55.25%  |
| DDR3   | 68        | 31.05%  |
| LPDDR5 | 6         | 2.74%   |
| DDR2   | 6         | 2.74%   |
| LPDDR4 | 5         | 2.28%   |
| LPDDR3 | 5         | 2.28%   |
| DDR5   | 5         | 2.28%   |
| SDRAM  | 2         | 0.91%   |
| DDR    | 1         | 0.46%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 194       | 85.84%  |
| Row Of Chips | 29        | 12.83%  |
| Chip         | 3         | 1.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 115       | 46.56%  |
| 4096  | 81        | 32.79%  |
| 16384 | 27        | 10.93%  |
| 2048  | 21        | 8.5%    |
| 32768 | 2         | 0.81%   |
| 1024  | 1         | 0.4%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 58        | 24.17%  |
| 3200    | 56        | 23.33%  |
| 1600    | 49        | 20.42%  |
| 2400    | 12        | 5%      |
| 1333    | 11        | 4.58%   |
| 2133    | 9         | 3.75%   |
| 6400    | 6         | 2.5%    |
| 3266    | 6         | 2.5%    |
| 4800    | 5         | 2.08%   |
| 1334    | 5         | 2.08%   |
| 1067    | 4         | 1.67%   |
| 4267    | 3         | 1.25%   |
| 800     | 3         | 1.25%   |
| 4199    | 2         | 0.83%   |
| 1066    | 2         | 0.83%   |
| 667     | 2         | 0.83%   |
| Unknown | 2         | 0.83%   |
| 8400    | 1         | 0.42%   |
| 2933    | 1         | 0.42%   |
| 2666    | 1         | 0.42%   |
| 1867    | 1         | 0.42%   |
| 975     | 1         | 0.42%   |

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
| Chicony Electronics                    | 44        | 20.18%  |
| IMC Networks                           | 43        | 19.72%  |
| Bison Electronics                      | 18        | 8.26%   |
| Realtek Semiconductor                  | 17        | 7.8%    |
| Quanta                                 | 15        | 6.88%   |
| Microdia                               | 15        | 6.88%   |
| Sunplus Innovation Technology          | 11        | 5.05%   |
| Apple                                  | 9         | 4.13%   |
| Syntek                                 | 8         | 3.67%   |
| Lite-On Technology                     | 6         | 2.75%   |
| Suyin                                  | 5         | 2.29%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 2.29%   |
| Luxvisions Innotech Limited            | 4         | 1.83%   |
| Acer                                   | 4         | 1.83%   |
| SunplusIT                              | 2         | 0.92%   |
| Samsung Electronics                    | 2         | 0.92%   |
| Y Media                                | 1         | 0.46%   |
| Sonix Technology                       | 1         | 0.46%   |
| Silicon Motion                         | 1         | 0.46%   |
| Ricoh                                  | 1         | 0.46%   |
| OPPO Electronics                       | 1         | 0.46%   |
| LG Innotek                             | 1         | 0.46%   |
| Intel                                  | 1         | 0.46%   |
| Alpha Imaging Technology               | 1         | 0.46%   |
| ALi                                    | 1         | 0.46%   |
| Alcor Micro                            | 1         | 0.46%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                      | 15        | 6.82%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 13        | 5.91%   |
| IMC Networks Integrated Camera                                 | 10        | 4.55%   |
| Syntek Integrated Camera                                       | 8         | 3.64%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 7         | 3.18%   |
| Realtek Integrated_Webcam_HD                                   | 6         | 2.73%   |
| Quanta HP TrueVision HD Camera                                 | 6         | 2.73%   |
| Microdia Integrated_Webcam_HD                                  | 6         | 2.73%   |
| Lite-On Integrated Camera                                      | 6         | 2.73%   |
| IMC Networks HD Camera                                         | 5         | 2.27%   |
| Bison HD Webcam                                                | 5         | 2.27%   |
| Quanta HD User Facing                                          | 4         | 1.82%   |
| Apple FaceTime HD Camera                                       | 4         | 1.82%   |
| Realtek USB2.0 HD UVC WebCam                                   | 3         | 1.36%   |
| Chicony HP TrueVision HD Camera                                | 3         | 1.36%   |
| Chicony HD Webcam                                              | 3         | 1.36%   |
| Bison Lenovo Integrated Webcam                                 | 3         | 1.36%   |
| Sunplus Laptop Integrated Webcam FHD                           | 2         | 0.91%   |
| Sunplus Integrated_Webcam_HD                                   | 2         | 0.91%   |
| Sunplus Integrated_Webcam_FHD                                  | 2         | 0.91%   |
| Samsung Galaxy series, misc. (MTP mode)                        | 2         | 0.91%   |
| Realtek Integrated Webcam_HD                                   | 2         | 0.91%   |
| Microdia USB 2.0 Camera                                        | 2         | 0.91%   |
| Microdia Laptop_Integrated_Webcam_HD                           | 2         | 0.91%   |
| Microdia Integrated Webcam                                     | 2         | 0.91%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 2         | 0.91%   |
| IMC Networks VGA UVC WebCam                                    | 2         | 0.91%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 2         | 0.91%   |
| Chicony USB 2.0 Camera                                         | 2         | 0.91%   |
| Chicony Integrated IR Camera                                   | 2         | 0.91%   |
| Chicony EasyCamera                                             | 2         | 0.91%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 2         | 0.91%   |
| Bison ThinkPad Integrated Camera                               | 2         | 0.91%   |
| Bison SunplusIT Integrated Camera                              | 2         | 0.91%   |
| Bison Integrated Camera                                        | 2         | 0.91%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                             | 2         | 0.91%   |
| Apple Built-in iSight                                          | 2         | 0.91%   |
| Y Media USB Camera                                             | 1         | 0.45%   |
| Suyin USB 2.0 Camera                                           | 1         | 0.45%   |
| Suyin Laptop_Integrated_Webcam_3M                              | 1         | 0.45%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 12        | 34.29%  |
| Synaptics                  | 10        | 28.57%  |
| Shenzhen Goodix Technology | 8         | 22.86%  |
| Elan Microelectronics      | 2         | 5.71%   |
| AuthenTec                  | 2         | 5.71%   |
| LighTuning Technology      | 1         | 2.86%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                      | 7         | 20%     |
| Validity Sensors VFS7500 Touch Fingerprint Sensor        | 4         | 11.43%  |
| Validity Sensors VFS 5011 fingerprint sensor             | 3         | 8.57%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 3         | 8.57%   |
| Synaptics Metallica MIS Touch Fingerprint Reader         | 3         | 8.57%   |
| Validity Sensors VFS5011 Fingerprint Reader              | 1         | 2.86%   |
| Validity Sensors VFS495 Fingerprint Reader               | 1         | 2.86%   |
| Validity Sensors VFS301 Fingerprint Reader               | 1         | 2.86%   |
| Validity Sensors Synaptics WBDI                          | 1         | 2.86%   |
| Validity Sensors Fingerprint scanner                     | 1         | 2.86%   |
| Synaptics WBDI                                           | 1         | 2.86%   |
| Synaptics UWP WBDI                                       | 1         | 2.86%   |
| Synaptics  WBDI                                          | 1         | 2.86%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 2.86%   |
| Shenzhen Goodix Fingerprint Reader                       | 1         | 2.86%   |
| LighTuning Fingerprint Reader                            | 1         | 2.86%   |
| Elan ELAN:Fingerprint                                    | 1         | 2.86%   |
| Elan ELAN:ARM-M4                                         | 1         | 2.86%   |
| AuthenTec Fingerprint Sensor                             | 1         | 2.86%   |
| AuthenTec AES2810                                        | 1         | 2.86%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Alcor Micro                       | 6         | 31.58%  |
| Broadcom                          | 5         | 26.32%  |
| Upek                              | 3         | 15.79%  |
| Yubico.com                        | 1         | 5.26%   |
| VASCO Data Security International | 1         | 5.26%   |
| O2 Micro                          | 1         | 5.26%   |
| Gemalto (was Gemplus)             | 1         | 5.26%   |
| Clay Logic                        | 1         | 5.26%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                             | 6         | 31.58%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)      | 3         | 15.79%  |
| Broadcom BCM5880 Secure Applications Processor                  | 3         | 15.79%  |
| Yubico.com Yubikey NEO(-N) OTP+CCID                             | 1         | 5.26%   |
| VASCO Data Security International Digipass 905 SmartCard Reader | 1         | 5.26%   |
| O2 Micro OZ776 CCID Smartcard Reader                            | 1         | 5.26%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader               | 1         | 5.26%   |
| Clay Logic Nitrokey Pro                                         | 1         | 5.26%   |
| Broadcom 5880                                                   | 1         | 5.26%   |
| Broadcom 58200                                                  | 1         | 5.26%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 164       | 69.49%  |
| 1     | 58        | 24.58%  |
| 2     | 13        | 5.51%   |
| 3     | 1         | 0.42%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 35        | 40.23%  |
| Chipcard              | 17        | 19.54%  |
| Graphics card         | 15        | 17.24%  |
| Multimedia controller | 8         | 9.2%    |
| Camera                | 6         | 6.9%    |
| Storage               | 2         | 2.3%    |
| Net/wireless          | 2         | 2.3%    |
| Network               | 1         | 1.15%   |
| Net/ethernet          | 1         | 1.15%   |

