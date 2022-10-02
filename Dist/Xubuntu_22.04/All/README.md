Xubuntu 22.04 - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Xubuntu 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Xubuntu_22.04/Desktop/README.md) and [notebooks](/Dist/Xubuntu_22.04/Notebook/README.md).

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

Total: 198

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | B70-80 80MR                 | Notebook    | [69aec9e100](https://linux-hardware.org/?probe=69aec9e100) | Oct 01, 2022 |
| HP            | Notebook                    | Notebook    | [fec2594d37](https://linux-hardware.org/?probe=fec2594d37) | Oct 01, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [ddf1904011](https://linux-hardware.org/?probe=ddf1904011) | Oct 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [025a55eab7](https://linux-hardware.org/?probe=025a55eab7) | Sep 30, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [875b1df312](https://linux-hardware.org/?probe=875b1df312) | Sep 30, 2022 |
| Sony          | SVE1512C6EB                 | Notebook    | [c47a3a5bd7](https://linux-hardware.org/?probe=c47a3a5bd7) | Sep 30, 2022 |
| Lenovo        | ThinkPad T420 42361L0       | Notebook    | [abe6563e67](https://linux-hardware.org/?probe=abe6563e67) | Sep 30, 2022 |
| Dell          | Latitude 5420               | Notebook    | [36ddd1d6d7](https://linux-hardware.org/?probe=36ddd1d6d7) | Sep 30, 2022 |
| Lenovo        | IdeaPad N585 20179          | Notebook    | [dcdafbbd9b](https://linux-hardware.org/?probe=dcdafbbd9b) | Sep 28, 2022 |
| HP            | Pavilion dv7                | Notebook    | [5479c35130](https://linux-hardware.org/?probe=5479c35130) | Sep 28, 2022 |
| Toshiba       | Satellite Pro R50-C         | Notebook    | [834ef0ec59](https://linux-hardware.org/?probe=834ef0ec59) | Sep 27, 2022 |
| Toshiba       | Satellite Pro R50-C         | Notebook    | [564d385b61](https://linux-hardware.org/?probe=564d385b61) | Sep 27, 2022 |
| Dell          | CS24-TY                     | Server      | [029e2bdb60](https://linux-hardware.org/?probe=029e2bdb60) | Sep 27, 2022 |
| MSI           | H170M PRO-VDH               | Desktop     | [f7254adff2](https://linux-hardware.org/?probe=f7254adff2) | Sep 25, 2022 |
| Toshiba       | Satellite C650              | Notebook    | [c7920c2e68](https://linux-hardware.org/?probe=c7920c2e68) | Sep 24, 2022 |
| Packard Be... | EasyNote MH45               | Notebook    | [c312580997](https://linux-hardware.org/?probe=c312580997) | Sep 24, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [5588f73920](https://linux-hardware.org/?probe=5588f73920) | Sep 24, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a83e57d8c1](https://linux-hardware.org/?probe=a83e57d8c1) | Sep 23, 2022 |
| Tactus        | GeoBook 140                 | Notebook    | [7d8700d0e1](https://linux-hardware.org/?probe=7d8700d0e1) | Sep 23, 2022 |
| Dell          | Latitude 5411               | Notebook    | [018a9c569a](https://linux-hardware.org/?probe=018a9c569a) | Sep 23, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [c3a88ed62d](https://linux-hardware.org/?probe=c3a88ed62d) | Sep 22, 2022 |
| Lenovo        | ThinkPad T61 7659AB7        | Notebook    | [aa07f9c271](https://linux-hardware.org/?probe=aa07f9c271) | Sep 20, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [966ae734c2](https://linux-hardware.org/?probe=966ae734c2) | Sep 20, 2022 |
| Lenovo        | ThinkPad T61p 6457A24       | Notebook    | [d98e9a64bd](https://linux-hardware.org/?probe=d98e9a64bd) | Sep 20, 2022 |
| Lenovo        | ThinkPad X220 42918F6       | Notebook    | [69dda668fc](https://linux-hardware.org/?probe=69dda668fc) | Sep 18, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [e2b4056812](https://linux-hardware.org/?probe=e2b4056812) | Sep 18, 2022 |
| ASRock        | 960GC-GS FX                 | Desktop     | [3e40742ff0](https://linux-hardware.org/?probe=3e40742ff0) | Sep 18, 2022 |
| Acer          | Swift SF314-511             | Notebook    | [914d532c78](https://linux-hardware.org/?probe=914d532c78) | Sep 17, 2022 |
| ASUSTek       | ET1612I                     | Desktop     | [0ddd9554cc](https://linux-hardware.org/?probe=0ddd9554cc) | Sep 16, 2022 |
| Pine Micro... | Pine64 Rock64               | Soc         | [dbd6ac01d6](https://linux-hardware.org/?probe=dbd6ac01d6) | Sep 16, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [588c189149](https://linux-hardware.org/?probe=588c189149) | Sep 16, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [4b94d21772](https://linux-hardware.org/?probe=4b94d21772) | Sep 16, 2022 |
| Dell          | Latitude 7490               | Notebook    | [ce54bcd741](https://linux-hardware.org/?probe=ce54bcd741) | Sep 15, 2022 |
| Dell          | Inspiron 3576               | Notebook    | [02023473b8](https://linux-hardware.org/?probe=02023473b8) | Sep 15, 2022 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [6d40add21a](https://linux-hardware.org/?probe=6d40add21a) | Sep 15, 2022 |
| Dell          | Latitude 7420               | Convertible | [5d119f6255](https://linux-hardware.org/?probe=5d119f6255) | Sep 14, 2022 |
| Dell          | 0DR845                      | Desktop     | [158b3832bc](https://linux-hardware.org/?probe=158b3832bc) | Sep 13, 2022 |
| Dell          | Precision 5540              | Notebook    | [229337f709](https://linux-hardware.org/?probe=229337f709) | Sep 13, 2022 |
| ASUSTek       | K30BD                       | Desktop     | [d6daf0e1f8](https://linux-hardware.org/?probe=d6daf0e1f8) | Sep 13, 2022 |
| ASUSTek       | H61M-C                      | Desktop     | [bb07dfab63](https://linux-hardware.org/?probe=bb07dfab63) | Sep 13, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [e59aa2e1d5](https://linux-hardware.org/?probe=e59aa2e1d5) | Sep 13, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [930da2e105](https://linux-hardware.org/?probe=930da2e105) | Sep 13, 2022 |
| Dell          | 0DR845                      | Desktop     | [f65bf44380](https://linux-hardware.org/?probe=f65bf44380) | Sep 13, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [3f56f510f8](https://linux-hardware.org/?probe=3f56f510f8) | Sep 12, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [940507a1ec](https://linux-hardware.org/?probe=940507a1ec) | Sep 12, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [7b7a1cfeb9](https://linux-hardware.org/?probe=7b7a1cfeb9) | Sep 11, 2022 |
| Dell          | 03NVJ6 A01                  | Desktop     | [3f51b6da48](https://linux-hardware.org/?probe=3f51b6da48) | Sep 10, 2022 |
| Rockchip      | RK3318 BOX                  | Soc         | [bf1aba4ebe](https://linux-hardware.org/?probe=bf1aba4ebe) | Sep 10, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [1f2be56ed4](https://linux-hardware.org/?probe=1f2be56ed4) | Sep 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [31717bdcb1](https://linux-hardware.org/?probe=31717bdcb1) | Sep 09, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [31a50780b4](https://linux-hardware.org/?probe=31a50780b4) | Sep 08, 2022 |
| Dell          | Inspiron 5406 2n1           | Convertible | [b0412cee20](https://linux-hardware.org/?probe=b0412cee20) | Sep 07, 2022 |
| ASUSTek       | PRIME A320M-C R2.0          | Desktop     | [7649a53341](https://linux-hardware.org/?probe=7649a53341) | Sep 06, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [c1ca471555](https://linux-hardware.org/?probe=c1ca471555) | Sep 06, 2022 |
| ASUSTek       | PRIME B560-PLUS             | Desktop     | [989e0d5d57](https://linux-hardware.org/?probe=989e0d5d57) | Sep 06, 2022 |
| ASUSTek       | PRIME B560-PLUS             | Desktop     | [f51b1f139e](https://linux-hardware.org/?probe=f51b1f139e) | Sep 06, 2022 |
| Panasonic     | CF-D1DVA06F3                | Notebook    | [e3cc43135a](https://linux-hardware.org/?probe=e3cc43135a) | Sep 05, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [dd775ffe8f](https://linux-hardware.org/?probe=dd775ffe8f) | Sep 05, 2022 |
| ASUSTek       | PRIME H270M-PLUS            | Desktop     | [668995f3ff](https://linux-hardware.org/?probe=668995f3ff) | Sep 04, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [1bd6f2ba6f](https://linux-hardware.org/?probe=1bd6f2ba6f) | Sep 04, 2022 |
| Google        | Kip                         | Notebook    | [e92d971d5e](https://linux-hardware.org/?probe=e92d971d5e) | Sep 04, 2022 |
| ASUSTek       | K30BD                       | Desktop     | [6042bda5d7](https://linux-hardware.org/?probe=6042bda5d7) | Sep 03, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [059bb72ff2](https://linux-hardware.org/?probe=059bb72ff2) | Sep 03, 2022 |
| Google        | Reks                        | Notebook    | [d88eecb32d](https://linux-hardware.org/?probe=d88eecb32d) | Sep 03, 2022 |
| Clientron     | C800                        | Mini pc     | [18fcb4170b](https://linux-hardware.org/?probe=18fcb4170b) | Sep 03, 2022 |
| HP            | EliteBook 2570p             | Notebook    | [506f9da93b](https://linux-hardware.org/?probe=506f9da93b) | Sep 03, 2022 |
| HP            | 8433 11                     | Desktop     | [00868f25c6](https://linux-hardware.org/?probe=00868f25c6) | Aug 31, 2022 |
| sunxi         | Allwinner sun7i (A20) Fa... | Soc         | [632a8a0ad8](https://linux-hardware.org/?probe=632a8a0ad8) | Aug 30, 2022 |
| ASUSTek       | Z97-C                       | Desktop     | [9bdae9239f](https://linux-hardware.org/?probe=9bdae9239f) | Aug 29, 2022 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [e692fe97cb](https://linux-hardware.org/?probe=e692fe97cb) | Aug 28, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [b9953ab67e](https://linux-hardware.org/?probe=b9953ab67e) | Aug 27, 2022 |
| Lenovo        | V340-17IWL 81RG             | Notebook    | [f725a87544](https://linux-hardware.org/?probe=f725a87544) | Aug 27, 2022 |
| Lenovo        | 14w 81MQ000JUS              | Notebook    | [d71f12bede](https://linux-hardware.org/?probe=d71f12bede) | Aug 27, 2022 |
| Lenovo        | V340-17IWL 81RG             | Notebook    | [8a689fc0fd](https://linux-hardware.org/?probe=8a689fc0fd) | Aug 27, 2022 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [7bf3626764](https://linux-hardware.org/?probe=7bf3626764) | Aug 25, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [5bb7561235](https://linux-hardware.org/?probe=5bb7561235) | Aug 25, 2022 |
| Lenovo        | ThinkPad P70 20ERCTO1WW     | Notebook    | [d269aaa456](https://linux-hardware.org/?probe=d269aaa456) | Aug 25, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [c37bc2a345](https://linux-hardware.org/?probe=c37bc2a345) | Aug 24, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [92be7f3368](https://linux-hardware.org/?probe=92be7f3368) | Aug 24, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [5652f2c73d](https://linux-hardware.org/?probe=5652f2c73d) | Aug 24, 2022 |
| Lenovo        | 14w 81MQ000JUS              | Notebook    | [1ff769c6ef](https://linux-hardware.org/?probe=1ff769c6ef) | Aug 23, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [5dabf74b7f](https://linux-hardware.org/?probe=5dabf74b7f) | Aug 21, 2022 |
| HP            | EliteBook 8540p             | Notebook    | [cdd3dd9925](https://linux-hardware.org/?probe=cdd3dd9925) | Aug 19, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [ed1f055157](https://linux-hardware.org/?probe=ed1f055157) | Aug 19, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [764eaea2ba](https://linux-hardware.org/?probe=764eaea2ba) | Aug 19, 2022 |
| eMachines     | ET1350                      | Desktop     | [96e9f7aba7](https://linux-hardware.org/?probe=96e9f7aba7) | Aug 18, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [015ccc4b06](https://linux-hardware.org/?probe=015ccc4b06) | Aug 18, 2022 |
| HP            | 8591                        | Desktop     | [4235eb97c1](https://linux-hardware.org/?probe=4235eb97c1) | Aug 18, 2022 |
| Dell          | 0YXT71 A00                  | Desktop     | [def7e10c65](https://linux-hardware.org/?probe=def7e10c65) | Aug 17, 2022 |
| ASUSTek       | K53TA                       | Notebook    | [db6525efb3](https://linux-hardware.org/?probe=db6525efb3) | Aug 15, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [b98fcab3a6](https://linux-hardware.org/?probe=b98fcab3a6) | Aug 15, 2022 |
| Lenovo        | ThinkPad T460s 20FAS0Q90... | Notebook    | [644c7518e9](https://linux-hardware.org/?probe=644c7518e9) | Aug 14, 2022 |
| ASUSTek       | X101CH                      | Notebook    | [174bc50211](https://linux-hardware.org/?probe=174bc50211) | Aug 14, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [fd06db829d](https://linux-hardware.org/?probe=fd06db829d) | Aug 14, 2022 |
| Toshiba       | PT10F                       | Notebook    | [08b7dc52a2](https://linux-hardware.org/?probe=08b7dc52a2) | Aug 12, 2022 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [5bb07e1a28](https://linux-hardware.org/?probe=5bb07e1a28) | Aug 11, 2022 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [0fadd2421f](https://linux-hardware.org/?probe=0fadd2421f) | Aug 08, 2022 |
| Lenovo        | ThinkPad T460s 20FAS6JY0... | Notebook    | [7d85d4f00b](https://linux-hardware.org/?probe=7d85d4f00b) | Aug 06, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [eeff2bac06](https://linux-hardware.org/?probe=eeff2bac06) | Aug 05, 2022 |
| Acer          | Aspire V3-551G              | Notebook    | [8b0237ee5e](https://linux-hardware.org/?probe=8b0237ee5e) | Aug 03, 2022 |
| Lenovo        | ThinkPad T430 23501K1       | Notebook    | [fdd30ffa23](https://linux-hardware.org/?probe=fdd30ffa23) | Aug 03, 2022 |
| Acer          | Aspire V3-551G              | Notebook    | [4b8ed45c90](https://linux-hardware.org/?probe=4b8ed45c90) | Aug 03, 2022 |
| GMKtec        | NucBox5                     | Notebook    | [5023bc1773](https://linux-hardware.org/?probe=5023bc1773) | Aug 02, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [745f6815cb](https://linux-hardware.org/?probe=745f6815cb) | Jul 30, 2022 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | Desktop     | [01bcafef3c](https://linux-hardware.org/?probe=01bcafef3c) | Jul 30, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [9a97caa028](https://linux-hardware.org/?probe=9a97caa028) | Jul 28, 2022 |
| Schenker      | WORK (Early 2021)           | Notebook    | [8666cc396a](https://linux-hardware.org/?probe=8666cc396a) | Jul 28, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [d00325cd68](https://linux-hardware.org/?probe=d00325cd68) | Jul 28, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [da54317b9a](https://linux-hardware.org/?probe=da54317b9a) | Jul 27, 2022 |
| ASUSTek       | X450CP                      | Notebook    | [dceda2fe9d](https://linux-hardware.org/?probe=dceda2fe9d) | Jul 27, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [c380d02bbf](https://linux-hardware.org/?probe=c380d02bbf) | Jul 25, 2022 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [a27a0707b8](https://linux-hardware.org/?probe=a27a0707b8) | Jul 25, 2022 |
| PCWare        | IPX1800E2                   | Desktop     | [4426727633](https://linux-hardware.org/?probe=4426727633) | Jul 24, 2022 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [ba0058e96e](https://linux-hardware.org/?probe=ba0058e96e) | Jul 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [75b4088788](https://linux-hardware.org/?probe=75b4088788) | Jul 20, 2022 |
| Lenovo        | Win8 STD MM DPK IPG         | All in one  | [5889a04334](https://linux-hardware.org/?probe=5889a04334) | Jul 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [3c2afd2b5e](https://linux-hardware.org/?probe=3c2afd2b5e) | Jul 20, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [2a10c24690](https://linux-hardware.org/?probe=2a10c24690) | Jul 20, 2022 |
| Dell          | 0PM2CW A04                  | Server      | [8162a1a915](https://linux-hardware.org/?probe=8162a1a915) | Jul 17, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [d5a64d7baa](https://linux-hardware.org/?probe=d5a64d7baa) | Jul 16, 2022 |
| Acer          | Aspire E1-532               | Notebook    | [13d38a6632](https://linux-hardware.org/?probe=13d38a6632) | Jul 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [a6ae556389](https://linux-hardware.org/?probe=a6ae556389) | Jul 16, 2022 |
| ASUSTek       | X453MA                      | Notebook    | [da05c4539d](https://linux-hardware.org/?probe=da05c4539d) | Jul 11, 2022 |
| MSI           | GF63 Thin 9RCX              | Notebook    | [f2f3db370a](https://linux-hardware.org/?probe=f2f3db370a) | Jul 10, 2022 |
| MSI           | A320M PRO-E                 | Desktop     | [d16a812a12](https://linux-hardware.org/?probe=d16a812a12) | Jul 10, 2022 |
| Acer          | Aspire E5-521               | Notebook    | [7becd2f2df](https://linux-hardware.org/?probe=7becd2f2df) | Jul 10, 2022 |
| Acer          | Aspire E5-521               | Notebook    | [f27a09f9eb](https://linux-hardware.org/?probe=f27a09f9eb) | Jul 07, 2022 |
| ASUSTek       | ZenBook UX435EG_UX435EG     | Notebook    | [51b138f349](https://linux-hardware.org/?probe=51b138f349) | Jul 04, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [2f915d68e5](https://linux-hardware.org/?probe=2f915d68e5) | Jul 04, 2022 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [7b470f27d3](https://linux-hardware.org/?probe=7b470f27d3) | Jul 03, 2022 |
| Samsung       | 370E4K                      | Notebook    | [a6512c1606](https://linux-hardware.org/?probe=a6512c1606) | Jul 03, 2022 |
| Dell          | 0GXM1W A00                  | Desktop     | [d48eb55102](https://linux-hardware.org/?probe=d48eb55102) | Jul 01, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [9ce5b9c45c](https://linux-hardware.org/?probe=9ce5b9c45c) | Jun 30, 2022 |
| Acer          | Aspire E5-521               | Notebook    | [717281a3f9](https://linux-hardware.org/?probe=717281a3f9) | Jun 29, 2022 |
| Acer          | Aspire E5-521               | Notebook    | [f532d90f38](https://linux-hardware.org/?probe=f532d90f38) | Jun 29, 2022 |
| Standard      | Unknown                     | Notebook    | [1a94acbc05](https://linux-hardware.org/?probe=1a94acbc05) | Jun 29, 2022 |
| Supermicro    | X10SRA                      | Server      | [4646cb2fae](https://linux-hardware.org/?probe=4646cb2fae) | Jun 27, 2022 |
| Standard      | Unknown                     | Notebook    | [93ac825a25](https://linux-hardware.org/?probe=93ac825a25) | Jun 27, 2022 |
| HP            | Pavilion dv5                | Notebook    | [4009a4fd8c](https://linux-hardware.org/?probe=4009a4fd8c) | Jun 24, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [db4763808b](https://linux-hardware.org/?probe=db4763808b) | Jun 22, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [e9d8c28a34](https://linux-hardware.org/?probe=e9d8c28a34) | Jun 22, 2022 |
| Acer          | Switch SW312-31             | Tablet      | [ded5eaba87](https://linux-hardware.org/?probe=ded5eaba87) | Jun 19, 2022 |
| Google        | Kindred                     | Notebook    | [c12b15c596](https://linux-hardware.org/?probe=c12b15c596) | Jun 17, 2022 |
| Medion        | E2221T MD60684              | Convertible | [559733f94d](https://linux-hardware.org/?probe=559733f94d) | Jun 16, 2022 |
| HP            | ProBook 445 G7              | Notebook    | [f41d413820](https://linux-hardware.org/?probe=f41d413820) | Jun 13, 2022 |
| GPU Compan... | GWTN141-4                   | Notebook    | [ba579cb383](https://linux-hardware.org/?probe=ba579cb383) | Jun 11, 2022 |
| MSI           | G31TM-P21                   | Desktop     | [824dc8a1c9](https://linux-hardware.org/?probe=824dc8a1c9) | Jun 11, 2022 |
| Dell          | Latitude 7280               | Notebook    | [7900c8009a](https://linux-hardware.org/?probe=7900c8009a) | Jun 10, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [7bd963dd56](https://linux-hardware.org/?probe=7bd963dd56) | Jun 09, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [77a5e1c6f9](https://linux-hardware.org/?probe=77a5e1c6f9) | Jun 08, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [33dbe3e5db](https://linux-hardware.org/?probe=33dbe3e5db) | Jun 08, 2022 |
| AMI           | Intel                       | Notebook    | [79b1f29bc4](https://linux-hardware.org/?probe=79b1f29bc4) | Jun 07, 2022 |
| AMI           | Intel                       | Notebook    | [d7746ec6d5](https://linux-hardware.org/?probe=d7746ec6d5) | Jun 07, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [2d31db0d12](https://linux-hardware.org/?probe=2d31db0d12) | Jun 07, 2022 |
| Digma         | EVE 15 C413 ES5059EW        | Notebook    | [26eb7d39e1](https://linux-hardware.org/?probe=26eb7d39e1) | Jun 06, 2022 |
| HP            | Pavilion g7                 | Notebook    | [b31de17368](https://linux-hardware.org/?probe=b31de17368) | Jun 06, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [48738fc474](https://linux-hardware.org/?probe=48738fc474) | Jun 06, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [e8dd7b95a6](https://linux-hardware.org/?probe=e8dd7b95a6) | Jun 03, 2022 |
| Dell          | Latitude D820               | Notebook    | [8c2336469f](https://linux-hardware.org/?probe=8c2336469f) | Jun 01, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [db6d025d69](https://linux-hardware.org/?probe=db6d025d69) | Jun 01, 2022 |
| LG Electro... | 22V280 FAB1                 | All in one  | [d61829e715](https://linux-hardware.org/?probe=d61829e715) | May 26, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [496399846f](https://linux-hardware.org/?probe=496399846f) | May 26, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [2c541b20f6](https://linux-hardware.org/?probe=2c541b20f6) | May 26, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [aa8d9cb3b9](https://linux-hardware.org/?probe=aa8d9cb3b9) | May 25, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [a22a5ebbff](https://linux-hardware.org/?probe=a22a5ebbff) | May 25, 2022 |
| HP            | Mini 5103                   | Notebook    | [aa7f4e957e](https://linux-hardware.org/?probe=aa7f4e957e) | May 23, 2022 |
| ASUSTek       | X99-A II                    | Desktop     | [288a6b3b20](https://linux-hardware.org/?probe=288a6b3b20) | May 23, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [3e34ce179d](https://linux-hardware.org/?probe=3e34ce179d) | May 22, 2022 |
| Google        | Snappy                      | Notebook    | [c88d27b24a](https://linux-hardware.org/?probe=c88d27b24a) | May 20, 2022 |
| Google        | Snappy                      | Notebook    | [9fc85cd49a](https://linux-hardware.org/?probe=9fc85cd49a) | May 20, 2022 |
| Google        | Snappy                      | Notebook    | [cb9e7730ad](https://linux-hardware.org/?probe=cb9e7730ad) | May 20, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [ee3726a591](https://linux-hardware.org/?probe=ee3726a591) | May 19, 2022 |
| Lenovo        | ThinkPad E580 20KS001JGE    | Notebook    | [724c06c08c](https://linux-hardware.org/?probe=724c06c08c) | May 19, 2022 |
| ASUSTek       | UL30A                       | Notebook    | [c121dd37ba](https://linux-hardware.org/?probe=c121dd37ba) | May 16, 2022 |
| Google        | Droid                       | Notebook    | [e938864c93](https://linux-hardware.org/?probe=e938864c93) | May 15, 2022 |
| Fujitsu       | D2917-A1 S26361-D2917-A1    | Desktop     | [6f58937bed](https://linux-hardware.org/?probe=6f58937bed) | May 13, 2022 |
| Unknown       | Unknown                     | Notebook    | [f802e84b8e](https://linux-hardware.org/?probe=f802e84b8e) | May 08, 2022 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [bd94a8145a](https://linux-hardware.org/?probe=bd94a8145a) | May 08, 2022 |
| Dell          | Inspiron 7501               | Notebook    | [a8a1e1e3a2](https://linux-hardware.org/?probe=a8a1e1e3a2) | May 07, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [e7ad5ed098](https://linux-hardware.org/?probe=e7ad5ed098) | May 06, 2022 |
| Dell          | Latitude 7420               | Notebook    | [384325350c](https://linux-hardware.org/?probe=384325350c) | May 05, 2022 |
| Google        | Auron_Yuna                  | Notebook    | [795d9af5a7](https://linux-hardware.org/?probe=795d9af5a7) | May 05, 2022 |
| Acer          | Veriton M490G               | Desktop     | [f55983d536](https://linux-hardware.org/?probe=f55983d536) | May 04, 2022 |
| Dell          | XPS M1530                   | Notebook    | [760cae00c1](https://linux-hardware.org/?probe=760cae00c1) | May 03, 2022 |
| ASRock        | P55 Pro                     | Desktop     | [e626676348](https://linux-hardware.org/?probe=e626676348) | May 02, 2022 |
| Dell          | XPS M1530                   | Notebook    | [757d1b099e](https://linux-hardware.org/?probe=757d1b099e) | Apr 30, 2022 |
| ASUSTek       | T100HAN                     | Notebook    | [5ee200cfbe](https://linux-hardware.org/?probe=5ee200cfbe) | Apr 30, 2022 |
| HP            | 09F8h                       | Desktop     | [8605181df9](https://linux-hardware.org/?probe=8605181df9) | Apr 26, 2022 |
| Acer          | Aspire ES1-512              | Notebook    | [f0ed67e309](https://linux-hardware.org/?probe=f0ed67e309) | Apr 26, 2022 |
| Supermicro    | X11SPL-F                    | Server      | [34f6e28125](https://linux-hardware.org/?probe=34f6e28125) | Apr 26, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [bd286b124a](https://linux-hardware.org/?probe=bd286b124a) | Apr 25, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [c16cb4e0d6](https://linux-hardware.org/?probe=c16cb4e0d6) | Apr 24, 2022 |
| Lenovo        | ThinkPad T470s 20HF004MM... | Notebook    | [69a5e98a04](https://linux-hardware.org/?probe=69a5e98a04) | Apr 22, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [3e1029ed36](https://linux-hardware.org/?probe=3e1029ed36) | Apr 22, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [d88db86125](https://linux-hardware.org/?probe=d88db86125) | Apr 20, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [b073554afc](https://linux-hardware.org/?probe=b073554afc) | Apr 08, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [c3dcb61dd5](https://linux-hardware.org/?probe=c3dcb61dd5) | Apr 02, 2022 |
| Rockchip      | RK3318 BOX                  | Soc         | [6098716d3e](https://linux-hardware.org/?probe=6098716d3e) | Mar 30, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Computers | Percent |
|----------------------------|-----------|---------|
| 5.15.0-47-generic          | 28        | 17.28%  |
| 5.15.0-46-generic          | 17        | 10.49%  |
| 5.15.0-27-generic          | 14        | 8.64%   |
| 5.15.0-48-generic          | 12        | 7.41%   |
| 5.15.0-25-generic          | 12        | 7.41%   |
| 5.15.0-41-generic          | 9         | 5.56%   |
| 5.15.0-40-generic          | 9         | 5.56%   |
| 5.15.0-43-generic          | 7         | 4.32%   |
| 5.15.0-39-generic          | 5         | 3.09%   |
| 5.15.0-37-generic          | 5         | 3.09%   |
| 5.15.0-35-generic          | 5         | 3.09%   |
| 5.15.0-33-generic          | 4         | 2.47%   |
| 5.15.0-30-generic          | 4         | 2.47%   |
| 5.17.0-1013-oem            | 2         | 1.23%   |
| 5.15.0-46-lowlatency       | 2         | 1.23%   |
| 5.4.0-126-generic          | 1         | 0.62%   |
| 5.4.0-122-generic          | 1         | 0.62%   |
| 5.19.5-051905-generic      | 1         | 0.62%   |
| 5.19.1                     | 1         | 0.62%   |
| 5.19.0-8.2-liquorix-amd64  | 1         | 0.62%   |
| 5.19.0-051900-generic      | 1         | 0.62%   |
| 5.18.12-051812-generic     | 1         | 0.62%   |
| 5.18.0-10.1-liquorix-amd64 | 1         | 0.62%   |
| 5.18.0                     | 1         | 0.62%   |
| 5.17.3-051703-generic      | 1         | 0.62%   |
| 5.17.0-ashpy3-lyesdef      | 1         | 0.62%   |
| 5.17.0-8-generic           | 1         | 0.62%   |
| 5.17.0-1015-oem            | 1         | 0.62%   |
| 5.17.0-1003-oem            | 1         | 0.62%   |
| 5.16.9-051609-generic      | 1         | 0.62%   |
| 5.15.68-rockchip64         | 1         | 0.62%   |
| 5.15.61-bcm2711            | 1         | 0.62%   |
| 5.15.59-rockchip64         | 1         | 0.62%   |
| 5.15.48-sunxi              | 1         | 0.62%   |
| 5.15.23-rockchip64         | 1         | 0.62%   |
| 5.15.0-50-lowlatency       | 1         | 0.62%   |
| 5.15.0-48-lowlatency       | 1         | 0.62%   |
| 5.15.0-39-lowlatency       | 1         | 0.62%   |
| 5.15.0-27-lowlatency       | 1         | 0.62%   |
| 5.15.0-18-generic          | 1         | 0.62%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.15.0   | 135       | 85.44%  |
| 5.17.0   | 6         | 3.8%    |
| 5.4.0    | 2         | 1.27%   |
| 5.19.0   | 2         | 1.27%   |
| 5.18.0   | 2         | 1.27%   |
| 5.19.5   | 1         | 0.63%   |
| 5.19.1   | 1         | 0.63%   |
| 5.18.12  | 1         | 0.63%   |
| 5.17.3   | 1         | 0.63%   |
| 5.16.9   | 1         | 0.63%   |
| 5.15.68  | 1         | 0.63%   |
| 5.15.61  | 1         | 0.63%   |
| 5.15.59  | 1         | 0.63%   |
| 5.15.48  | 1         | 0.63%   |
| 5.15.23  | 1         | 0.63%   |
| 4.19.241 | 1         | 0.63%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 140       | 88.61%  |
| 5.17    | 7         | 4.43%   |
| 5.19    | 4         | 2.53%   |
| 5.18    | 3         | 1.9%    |
| 5.4     | 2         | 1.27%   |
| 5.16    | 1         | 0.63%   |
| 4.19    | 1         | 0.63%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 152       | 96.82%  |
| aarch64 | 4         | 2.55%   |
| armv7l  | 1         | 0.64%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| XFCE            | 151       | 96.18%  |
| GNOME           | 4         | 2.55%   |
| i3              | 1         | 0.64%   |
| GNOME Flashback | 1         | 0.64%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 152       | 96.2%   |
| Tty     | 4         | 2.53%   |
| Wayland | 2         | 1.27%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 141       | 89.81%  |
| Unknown | 8         | 5.1%    |
| GDM3    | 6         | 3.82%   |
| SLiM    | 1         | 0.64%   |
| SDDM    | 1         | 0.64%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 64        | 40.76%  |
| fr_FR | 22        | 14.01%  |
| de_DE | 16        | 10.19%  |
| it_IT | 10        | 6.37%   |
| en_GB | 7         | 4.46%   |
| pt_BR | 6         | 3.82%   |
| en_CA | 5         | 3.18%   |
| ru_RU | 4         | 2.55%   |
| es_ES | 4         | 2.55%   |
| en_AU | 3         | 1.91%   |
| ja_JP | 2         | 1.27%   |
| hu_HU | 2         | 1.27%   |
| cs_CZ | 2         | 1.27%   |
| tr_TR | 1         | 0.64%   |
| sv_SE | 1         | 0.64%   |
| nl_NL | 1         | 0.64%   |
| nl_BE | 1         | 0.64%   |
| fi_FI | 1         | 0.64%   |
| es_CO | 1         | 0.64%   |
| es_CL | 1         | 0.64%   |
| es_AR | 1         | 0.64%   |
| C     | 1         | 0.64%   |
| bg_BG | 1         | 0.64%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 80        | 50.96%  |
| BIOS | 77        | 49.04%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 144       | 91.72%  |
| Overlay | 6         | 3.82%   |
| Zfs     | 4         | 2.55%   |
| Btrfs   | 2         | 1.27%   |
| Ext3    | 1         | 0.64%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 85        | 54.14%  |
| Unknown | 59        | 37.58%  |
| MBR     | 13        | 8.28%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 138       | 87.34%  |
| Yes       | 20        | 12.66%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 105       | 66.88%  |
| Yes       | 52        | 33.12%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 33        | 21.02%  |
| Lenovo                  | 24        | 15.29%  |
| Hewlett-Packard         | 20        | 12.74%  |
| Dell                    | 20        | 12.74%  |
| MSI                     | 9         | 5.73%   |
| Acer                    | 8         | 5.1%    |
| Google                  | 5         | 3.18%   |
| Toshiba                 | 3         | 1.91%   |
| Gigabyte Technology     | 3         | 1.91%   |
| ASRock                  | 3         | 1.91%   |
| Supermicro              | 2         | 1.27%   |
| Rockchip                | 2         | 1.27%   |
| Apple                   | 2         | 1.27%   |
| Tactus                  | 1         | 0.64%   |
| sunxi                   | 1         | 0.64%   |
| Standard                | 1         | 0.64%   |
| Sony                    | 1         | 0.64%   |
| Schenker                | 1         | 0.64%   |
| Samsung Electronics     | 1         | 0.64%   |
| Raspberry Pi Foundation | 1         | 0.64%   |
| Pine Microsystems       | 1         | 0.64%   |
| PCWare                  | 1         | 0.64%   |
| Panasonic               | 1         | 0.64%   |
| Packard Bell            | 1         | 0.64%   |
| Medion                  | 1         | 0.64%   |
| Mediacom                | 1         | 0.64%   |
| LG Electronics          | 1         | 0.64%   |
| HUAWEI                  | 1         | 0.64%   |
| GPU Company             | 1         | 0.64%   |
| Fujitsu                 | 1         | 0.64%   |
| Foxconn                 | 1         | 0.64%   |
| eMachines               | 1         | 0.64%   |
| Digma                   | 1         | 0.64%   |
| Chuwi                   | 1         | 0.64%   |
| AMI                     | 1         | 0.64%   |
| Unknown                 | 1         | 0.64%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| HP EliteBook 840 G3                   | 3         | 1.91%   |
| ASUS All Series                       | 3         | 1.91%   |
| Rockchip RK3318 BOX                   | 2         | 1.27%   |
| MSI MS-7D43                           | 2         | 1.27%   |
| Dell OptiPlex 7010                    | 2         | 1.27%   |
| Dell Latitude 7420                    | 2         | 1.27%   |
| Unknown                               | 2         | 1.27%   |
| Toshiba Satellite Pro R50-C           | 1         | 0.64%   |
| Toshiba Satellite C650                | 1         | 0.64%   |
| Toshiba PT10F                         | 1         | 0.64%   |
| Tactus GeoBook 140                    | 1         | 0.64%   |
| Supermicro X10SRA                     | 1         | 0.64%   |
| Supermicro Super Server               | 1         | 0.64%   |
| sunxi Allwinner sun7i (A20) Family    | 1         | 0.64%   |
| Sony SVE1512C6EB                      | 1         | 0.64%   |
| Schenker WORK (Early 2021)            | 1         | 0.64%   |
| Samsung 370E4K                        | 1         | 0.64%   |
| RPi Raspberry Pi 4 Model B Rev 1.5    | 1         | 0.64%   |
| Pine Microsystems Pine64 Rock64       | 1         | 0.64%   |
| PCWare IPX1800E2                      | 1         | 0.64%   |
| Panasonic CF-D1DVA06F3                | 1         | 0.64%   |
| Packard Bell EasyNote MH45            | 1         | 0.64%   |
| MSI MS-7C91                           | 1         | 0.64%   |
| MSI MS-7C52                           | 1         | 0.64%   |
| MSI MS-7C08                           | 1         | 0.64%   |
| MSI MS-7982                           | 1         | 0.64%   |
| MSI MS-7529                           | 1         | 0.64%   |
| MSI Hyrican PC A320M PRO-E            | 1         | 0.64%   |
| MSI GF63 Thin 9RCX                    | 1         | 0.64%   |
| Medion E2221T MD60684                 | 1         | 0.64%   |
| Mediacom SmartBook 14 FullHD - SB14UC | 1         | 0.64%   |
| LG 22V280-L.BY31P1                    | 1         | 0.64%   |
| Lenovo Yoga 7 14ITL5 82BH             | 1         | 0.64%   |
| Lenovo V340-17IWL 81RG                | 1         | 0.64%   |
| Lenovo V330-15IKB 81AX                | 1         | 0.64%   |
| Lenovo ThinkPad X220 42918F6          | 1         | 0.64%   |
| Lenovo ThinkPad T61p 6457A24          | 1         | 0.64%   |
| Lenovo ThinkPad T61 7659AB7           | 1         | 0.64%   |
| Lenovo ThinkPad T470s 20HF004MMX      | 1         | 0.64%   |
| Lenovo ThinkPad T460s 20FAS6JY00      | 1         | 0.64%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 12        | 7.64%   |
| Dell Latitude            | 7         | 4.46%   |
| ASUS PRIME               | 7         | 4.46%   |
| HP EliteBook             | 6         | 3.82%   |
| HP Pavilion              | 5         | 3.18%   |
| Acer Aspire              | 5         | 3.18%   |
| Dell OptiPlex            | 4         | 2.55%   |
| Dell Inspiron            | 4         | 2.55%   |
| Lenovo IdeaPad           | 3         | 1.91%   |
| ASUS ROG                 | 3         | 1.91%   |
| ASUS All                 | 3         | 1.91%   |
| Toshiba Satellite        | 2         | 1.27%   |
| Rockchip RK3318          | 2         | 1.27%   |
| MSI MS-7D43              | 2         | 1.27%   |
| Lenovo ThinkCentre       | 2         | 1.27%   |
| HP Laptop                | 2         | 1.27%   |
| HP 255                   | 2         | 1.27%   |
| Dell XPS                 | 2         | 1.27%   |
| ASUS TUF                 | 2         | 1.27%   |
| ASUS ASUS                | 2         | 1.27%   |
| Unknown                  | 2         | 1.27%   |
| Toshiba PT10F            | 1         | 0.64%   |
| Tactus GeoBook           | 1         | 0.64%   |
| Supermicro X10SRA        | 1         | 0.64%   |
| Supermicro Super         | 1         | 0.64%   |
| sunxi Allwinner          | 1         | 0.64%   |
| Sony SVE1512C6EB         | 1         | 0.64%   |
| Schenker WORK            | 1         | 0.64%   |
| Samsung 370E4K           | 1         | 0.64%   |
| RPi Raspberry            | 1         | 0.64%   |
| Pine Microsystems Pine64 | 1         | 0.64%   |
| PCWare IPX1800E2         | 1         | 0.64%   |
| Panasonic CF-D1DVA06F3   | 1         | 0.64%   |
| Packard Bell EasyNote    | 1         | 0.64%   |
| MSI MS-7C91              | 1         | 0.64%   |
| MSI MS-7C52              | 1         | 0.64%   |
| MSI MS-7C08              | 1         | 0.64%   |
| MSI MS-7982              | 1         | 0.64%   |
| MSI MS-7529              | 1         | 0.64%   |
| MSI Hyrican              | 1         | 0.64%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 19        | 12.1%   |
| 2020    | 15        | 9.55%   |
| 2018    | 14        | 8.92%   |
| 2019    | 12        | 7.64%   |
| 2014    | 12        | 7.64%   |
| 2017    | 11        | 7.01%   |
| 2012    | 10        | 6.37%   |
| 2016    | 8         | 5.1%    |
| 2015    | 8         | 5.1%    |
| 2013    | 8         | 5.1%    |
| 2010    | 8         | 5.1%    |
| 2011    | 7         | 4.46%   |
| 2009    | 6         | 3.82%   |
| 2022    | 5         | 3.18%   |
| Unknown | 5         | 3.18%   |
| 2008    | 4         | 2.55%   |
| 2007    | 3         | 1.91%   |
| 2006    | 1         | 0.64%   |
| 2005    | 1         | 0.64%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 91        | 57.96%  |
| Desktop        | 49        | 31.21%  |
| System on chip | 5         | 3.18%   |
| Convertible    | 4         | 2.55%   |
| Server         | 4         | 2.55%   |
| All in one     | 3         | 1.91%   |
| Tablet         | 1         | 0.64%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 143       | 91.08%  |
| Enabled  | 14        | 8.92%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 152       | 96.82%  |
| Yes  | 5         | 3.18%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 47        | 29.94%  |
| 3.01-4.0    | 38        | 24.2%   |
| 16.01-24.0  | 30        | 19.11%  |
| 8.01-16.0   | 14        | 8.92%   |
| 32.01-64.0  | 11        | 7.01%   |
| 1.01-2.0    | 9         | 5.73%   |
| 64.01-256.0 | 4         | 2.55%   |
| 0.51-1.0    | 2         | 1.27%   |
| 24.01-32.0  | 1         | 0.64%   |
| 2.01-3.0    | 1         | 0.64%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 73        | 45.34%  |
| 2.01-3.0  | 40        | 24.84%  |
| 3.01-4.0  | 17        | 10.56%  |
| 4.01-8.0  | 15        | 9.32%   |
| 0.51-1.0  | 13        | 8.07%   |
| 8.01-16.0 | 2         | 1.24%   |
| 0.01-0.5  | 1         | 0.62%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 107       | 67.72%  |
| 2      | 32        | 20.25%  |
| 3      | 9         | 5.7%    |
| 4      | 6         | 3.8%    |
| 5      | 2         | 1.27%   |
| 7      | 1         | 0.63%   |
| 6      | 1         | 0.63%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 89        | 56.33%  |
| Yes       | 69        | 43.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 124       | 78.98%  |
| No        | 33        | 21.02%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 117       | 74.52%  |
| No        | 40        | 25.48%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 87        | 55.41%  |
| No        | 70        | 44.59%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 24        | 15.29%  |
| Germany     | 21        | 13.38%  |
| France      | 20        | 12.74%  |
| Italy       | 15        | 9.55%   |
| UK          | 7         | 4.46%   |
| Russia      | 6         | 3.82%   |
| Brazil      | 6         | 3.82%   |
| Sweden      | 5         | 3.18%   |
| Canada      | 5         | 3.18%   |
| Spain       | 3         | 1.91%   |
| Netherlands | 3         | 1.91%   |
| Indonesia   | 3         | 1.91%   |
| Czechia     | 3         | 1.91%   |
| Belgium     | 3         | 1.91%   |
| Australia   | 3         | 1.91%   |
| Turkey      | 2         | 1.27%   |
| Portugal    | 2         | 1.27%   |
| Mexico      | 2         | 1.27%   |
| Japan       | 2         | 1.27%   |
| Iran        | 2         | 1.27%   |
| Hungary     | 2         | 1.27%   |
| Finland     | 2         | 1.27%   |
| Colombia    | 2         | 1.27%   |
| Argentina   | 2         | 1.27%   |
| Vietnam     | 1         | 0.64%   |
| Poland      | 1         | 0.64%   |
| Malaysia    | 1         | 0.64%   |
| Madagascar  | 1         | 0.64%   |
| Israel      | 1         | 0.64%   |
| India       | 1         | 0.64%   |
| Guernsey    | 1         | 0.64%   |
| Guadeloupe  | 1         | 0.64%   |
| Egypt       | 1         | 0.64%   |
| Chile       | 1         | 0.64%   |
| Bulgaria    | 1         | 0.64%   |
| Austria     | 1         | 0.64%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Paris               | 5         | 3.13%   |
| Berlin              | 4         | 2.5%    |
| Melbourne           | 3         | 1.88%   |
| Uppsala             | 2         | 1.25%   |
| St Petersburg       | 2         | 1.25%   |
| Oklahoma City       | 2         | 1.25%   |
| Leipzig             | 2         | 1.25%   |
| Lavras              | 2         | 1.25%   |
| Jakarta             | 2         | 1.25%   |
| Helsinki            | 2         | 1.25%   |
| Farmington          | 2         | 1.25%   |
| Clermont-Ferrand    | 2         | 1.25%   |
| Budapest            | 2         | 1.25%   |
| Biella              | 2         | 1.25%   |
| Auxerre             | 2         | 1.25%   |
| Ankara              | 2         | 1.25%   |
| Yokohama            | 1         | 0.63%   |
| Washington          | 1         | 0.63%   |
| Waarder             | 1         | 0.63%   |
| Vidin               | 1         | 0.63%   |
| Vicenza             | 1         | 0.63%   |
| Västerås          | 1         | 0.63%   |
| Valparaiso de Goias | 1         | 0.63%   |
| Unkel               | 1         | 0.63%   |
| Tustin              | 1         | 0.63%   |
| Treviso             | 1         | 0.63%   |
| Tourouvre           | 1         | 0.63%   |
| Toronto             | 1         | 0.63%   |
| Toamasina           | 1         | 0.63%   |
| Thornton-Cleveleys  | 1         | 0.63%   |
| Teresina            | 1         | 0.63%   |
| Tehran              | 1         | 0.63%   |
| Surrey              | 1         | 0.63%   |
| Surabaya            | 1         | 0.63%   |
| Stuttgart           | 1         | 0.63%   |
| St Peter Port       | 1         | 0.63%   |
| Sombrio             | 1         | 0.63%   |
| Schmalkalden        | 1         | 0.63%   |
| Schaarbeek          | 1         | 0.63%   |
| Santiago de Cali    | 1         | 0.63%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 36        | 44     | 16.82%  |
| WDC                 | 33        | 40     | 15.42%  |
| Seagate             | 27        | 35     | 12.62%  |
| Unknown             | 15        | 17     | 7.01%   |
| Kingston            | 11        | 12     | 5.14%   |
| Toshiba             | 10        | 10     | 4.67%   |
| SK hynix            | 10        | 10     | 4.67%   |
| SanDisk             | 8         | 8      | 3.74%   |
| Hitachi             | 8         | 10     | 3.74%   |
| Crucial             | 6         | 9      | 2.8%    |
| PNY                 | 5         | 5      | 2.34%   |
| Intel               | 5         | 5      | 2.34%   |
| China               | 5         | 5      | 2.34%   |
| Unknown             | 4         | 4      | 1.87%   |
| Patriot             | 3         | 3      | 1.4%    |
| TEXTORM             | 2         | 2      | 0.93%   |
| Phison              | 2         | 5      | 0.93%   |
| Micron Technology   | 2         | 2      | 0.93%   |
| Maxtor              | 2         | 2      | 0.93%   |
| USB3.0              | 1         | 2      | 0.47%   |
| SSSTC               | 1         | 1      | 0.47%   |
| SSK                 | 1         | 1      | 0.47%   |
| Silicon Motion      | 1         | 1      | 0.47%   |
| OCZ                 | 1         | 1      | 0.47%   |
| Netac               | 1         | 1      | 0.47%   |
| LITEON              | 1         | 1      | 0.47%   |
| Lexar               | 1         | 1      | 0.47%   |
| Lenovo              | 1         | 1      | 0.47%   |
| KIOXIA              | 1         | 1      | 0.47%   |
| INNOVATION IT       | 1         | 1      | 0.47%   |
| HGST                | 1         | 1      | 0.47%   |
| Hewlett-Packard     | 1         | 3      | 0.47%   |
| FORESEE             | 1         | 1      | 0.47%   |
| Emtec               | 1         | 1      | 0.47%   |
| CHN25SATAS1         | 1         | 1      | 0.47%   |
| ASMT                | 1         | 1      | 0.47%   |
| ASMedia             | 1         | 1      | 0.47%   |
| Apple               | 1         | 2      | 0.47%   |
| A-DATA Technology   | 1         | 3      | 0.47%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB           | 4         | 1.7%    |
| Samsung SSD 850 EVO 500GB           | 4         | 1.7%    |
| Unknown                             | 4         | 1.7%    |
| Seagate ST500LM012 HN-M500MBB 500GB | 3         | 1.28%   |
| Samsung NVMe SSD Drive 256GB        | 3         | 1.28%   |
| PNY CS900 120GB SSD                 | 3         | 1.28%   |
| Kingston SA400S37480G 480GB SSD     | 3         | 1.28%   |
| Kingston SA400S37240G 240GB SSD     | 3         | 1.28%   |
| WDC WD10EZEX-00BBHA0 1TB            | 2         | 0.85%   |
| Toshiba MQ01ABF050 500GB            | 2         | 0.85%   |
| Toshiba DT01ACA200 2TB              | 2         | 0.85%   |
| TEXTORM BM5 240GB SSD               | 2         | 0.85%   |
| SK hynix NVMe SSD Drive 1024GB      | 2         | 0.85%   |
| Seagate ST500LT012-1DG142 500GB     | 2         | 0.85%   |
| Seagate ST500DM002-1BD142 500GB     | 2         | 0.85%   |
| Seagate ST1000DM003-1SB102 1TB      | 2         | 0.85%   |
| SanDisk SDSSDA240G 240GB            | 2         | 0.85%   |
| SanDisk DF4032  32GB                | 2         | 0.85%   |
| Samsung SSD 840 Series 120GB        | 2         | 0.85%   |
| Patriot Burst 480GB SSD             | 2         | 0.85%   |
| Intel SSDPEKNU512GZ 512GB           | 2         | 0.85%   |
| Hitachi HDS721050CLA362 500GB       | 2         | 0.85%   |
| Hitachi HDS721010CLA332 1TB         | 2         | 0.85%   |
| WDC WDS960G2G0C-00AJM0 960GB        | 1         | 0.43%   |
| WDC WDS500G2B0C 500GB               | 1         | 0.43%   |
| WDC WDS500G2B0B-00YS70 500GB SSD    | 1         | 0.43%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD    | 1         | 0.43%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 1         | 0.43%   |
| WDC WDS100T3X0C-00SJG0 1TB          | 1         | 0.43%   |
| WDC WD800JD-75MSA3 80GB             | 1         | 0.43%   |
| WDC WD800JD-22MSA1 80GB             | 1         | 0.43%   |
| WDC WD7500BPVT-60HXZT3 752GB        | 1         | 0.43%   |
| WDC WD740ADFD-00NLR5 74GB           | 1         | 0.43%   |
| WDC WD6400BPVT-80HXZT1 640GB        | 1         | 0.43%   |
| WDC WD6400BEVT-80A0RT0 640GB        | 1         | 0.43%   |
| WDC WD6400AAKS-65A7B0 640GB         | 1         | 0.43%   |
| WDC WD5003AZEX-00K1GA0 500GB        | 1         | 0.43%   |
| WDC WD5000AVCS-612DY1 500GB         | 1         | 0.43%   |
| WDC WD5000AAVS-00ZTB0 500GB         | 1         | 0.43%   |
| WDC WD5000AAKX-60U6AA0 500GB        | 1         | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 27        | 35     | 35.06%  |
| WDC                 | 26        | 32     | 33.77%  |
| Toshiba             | 9         | 9      | 11.69%  |
| Hitachi             | 8         | 10     | 10.39%  |
| Samsung Electronics | 3         | 5      | 3.9%    |
| USB3.0              | 1         | 2      | 1.3%    |
| Maxtor              | 1         | 1      | 1.3%    |
| HGST                | 1         | 1      | 1.3%    |
| ASMT                | 1         | 1      | 1.3%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 19        | 22     | 27.54%  |
| Kingston            | 9         | 9      | 13.04%  |
| Crucial             | 5         | 8      | 7.25%   |
| China               | 5         | 5      | 7.25%   |
| SanDisk             | 4         | 4      | 5.8%    |
| PNY                 | 4         | 4      | 5.8%    |
| WDC                 | 3         | 3      | 4.35%   |
| Patriot             | 3         | 3      | 4.35%   |
| TEXTORM             | 2         | 2      | 2.9%    |
| SK hynix            | 2         | 2      | 2.9%    |
| Toshiba             | 1         | 1      | 1.45%   |
| SSSTC               | 1         | 1      | 1.45%   |
| OCZ                 | 1         | 1      | 1.45%   |
| Netac               | 1         | 1      | 1.45%   |
| Micron Technology   | 1         | 1      | 1.45%   |
| Maxtor              | 1         | 1      | 1.45%   |
| LITEON              | 1         | 1      | 1.45%   |
| Intel               | 1         | 1      | 1.45%   |
| INNOVATION IT       | 1         | 1      | 1.45%   |
| FORESEE             | 1         | 1      | 1.45%   |
| ASMedia             | 1         | 1      | 1.45%   |
| A-DATA Technology   | 1         | 3      | 1.45%   |
| Unknown             | 1         | 1      | 1.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 64        | 96     | 32.99%  |
| SSD     | 61        | 77     | 31.44%  |
| NVMe    | 46        | 54     | 23.71%  |
| MMC     | 20        | 24     | 10.31%  |
| Unknown | 3         | 3      | 1.55%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 107       | 167    | 59.44%  |
| NVMe | 46        | 54     | 25.56%  |
| MMC  | 20        | 24     | 11.11%  |
| SAS  | 7         | 9      | 3.89%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 84        | 121    | 65.63%  |
| 0.51-1.0   | 30        | 36     | 23.44%  |
| 1.01-2.0   | 8         | 8      | 6.25%   |
| 3.01-4.0   | 3         | 4      | 2.34%   |
| 2.01-3.0   | 2         | 3      | 1.56%   |
| 10.01-20.0 | 1         | 1      | 0.78%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 42        | 26.42%  |
| 251-500        | 38        | 23.9%   |
| 501-1000       | 22        | 13.84%  |
| 51-100         | 16        | 10.06%  |
| 1001-2000      | 13        | 8.18%   |
| 1-20           | 11        | 6.92%   |
| 21-50          | 9         | 5.66%   |
| More than 3000 | 5         | 3.14%   |
| 2001-3000      | 2         | 1.26%   |
| Unknown        | 1         | 0.63%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 56        | 35%     |
| 21-50          | 34        | 21.25%  |
| 101-250        | 22        | 13.75%  |
| 251-500        | 21        | 13.13%  |
| 51-100         | 16        | 10%     |
| 501-1000       | 5         | 3.13%   |
| More than 3000 | 3         | 1.88%   |
| 1001-2000      | 2         | 1.25%   |
| Unknown        | 1         | 0.63%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WDS240G2G0B-00EPW0 240GB SSD   | 1         | 1      | 5.26%   |
| WDC WD2002FYPS-02W3B0 2TB          | 1         | 1      | 5.26%   |
| WDC WD10EZEX-60ZF5A0 1TB           | 1         | 1      | 5.26%   |
| WDC WD10EAVS-00D7B1 1TB            | 1         | 1      | 5.26%   |
| WDC WD10EARS-00Y5B1 1TB            | 1         | 1      | 5.26%   |
| Toshiba DT01ACA100 1TB             | 1         | 1      | 5.26%   |
| SSSTC CVB-8D128-HP 128GB SSD       | 1         | 1      | 5.26%   |
| Seagate ST500LT012-9WS142 500GB    | 1         | 1      | 5.26%   |
| Seagate ST500LT012-1DG142 500GB    | 1         | 1      | 5.26%   |
| Seagate ST3750840AS 752GB          | 1         | 1      | 5.26%   |
| Seagate ST3250318AS 250GB          | 1         | 2      | 5.26%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 5.26%   |
| Maxtor STM3160215AS 160GB          | 1         | 1      | 5.26%   |
| Kingston SNS4151S332GD 32GB SSD    | 1         | 1      | 5.26%   |
| Hitachi HTS543212L9A300 120GB      | 1         | 1      | 5.26%   |
| Hitachi HTS541080G9SA00 80GB       | 1         | 1      | 5.26%   |
| Hitachi HDS721010CLA332 1TB        | 1         | 1      | 5.26%   |
| Hitachi HCP725032GLA380 320GB      | 1         | 2      | 5.26%   |
| Crucial CT128MX100SSD1 128GB       | 1         | 1      | 5.26%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| WDC      | 5         | 5      | 26.32%  |
| Seagate  | 5         | 6      | 26.32%  |
| Hitachi  | 4         | 5      | 21.05%  |
| Toshiba  | 1         | 1      | 5.26%   |
| SSSTC    | 1         | 1      | 5.26%   |
| Maxtor   | 1         | 1      | 5.26%   |
| Kingston | 1         | 1      | 5.26%   |
| Crucial  | 1         | 1      | 5.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 6      | 33.33%  |
| WDC     | 4         | 4      | 26.67%  |
| Hitachi | 4         | 5      | 26.67%  |
| Toshiba | 1         | 1      | 6.67%   |
| Maxtor  | 1         | 1      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 13        | 17     | 81.25%  |
| SSD  | 3         | 4      | 18.75%  |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 78        | 119    | 46.99%  |
| Detected | 73        | 114    | 43.98%  |
| Malfunc  | 15        | 21     | 9.04%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 97        | 54.8%   |
| AMD                          | 32        | 18.08%  |
| Samsung Electronics          | 15        | 8.47%   |
| SK hynix                     | 8         | 4.52%   |
| SanDisk                      | 5         | 2.82%   |
| Phison Electronics           | 3         | 1.69%   |
| Kingston Technology Company  | 3         | 1.69%   |
| Silicon Motion               | 2         | 1.13%   |
| Nvidia                       | 2         | 1.13%   |
| JMicron Technology           | 2         | 1.13%   |
| ASMedia Technology           | 2         | 1.13%   |
| Shenzhen Longsys Electronics | 1         | 0.56%   |
| Micron/Crucial Technology    | 1         | 0.56%   |
| Lenovo                       | 1         | 0.56%   |
| KIOXIA                       | 1         | 0.56%   |
| Biwin Storage Technology     | 1         | 0.56%   |
| Apple                        | 1         | 0.56%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 25        | 12.02%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 8         | 3.85%   |
| Samsung NVMe SSD Controller 980                                                | 6         | 2.88%   |
| Intel Volume Management Device NVMe RAID Controller                            | 6         | 2.88%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 6         | 2.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 6         | 2.88%   |
| AMD 400 Series Chipset SATA Controller                                         | 6         | 2.88%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 5         | 2.4%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 5         | 2.4%    |
| SK hynix Gold P31 SSD                                                          | 4         | 1.92%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 1.92%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 3         | 1.44%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 1.44%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 1.44%   |
| Intel SATA Controller [RAID mode]                                              | 3         | 1.44%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 3         | 1.44%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 1.44%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 1.44%   |
| AMD FCH SATA Controller D                                                      | 3         | 1.44%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 2         | 0.96%   |
| SK hynix Non-Volatile memory controller                                        | 2         | 0.96%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 2         | 0.96%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 2         | 0.96%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 0.96%   |
| Phison E12 NVMe Controller                                                     | 2         | 0.96%   |
| Nvidia MCP61 SATA Controller                                                   | 2         | 0.96%   |
| Nvidia MCP61 IDE                                                               | 2         | 0.96%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 2         | 0.96%   |
| JMicron JMB363 SATA/IDE Controller                                             | 2         | 0.96%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 0.96%   |
| Intel Non-Volatile memory controller                                           | 2         | 0.96%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 0.96%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 2         | 0.96%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 2         | 0.96%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 0.96%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 2         | 0.96%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 0.96%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 2         | 0.96%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 0.96%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2         | 0.96%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 107       | 58.47%  |
| NVMe | 46        | 25.14%  |
| IDE  | 19        | 10.38%  |
| RAID | 11        | 6.01%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 114       | 72.61%  |
| AMD    | 38        | 24.2%   |
| ARM    | 5         | 3.18%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz           | 4         | 2.53%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 4         | 2.53%   |
| ARM Processor                               | 4         | 2.53%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 3         | 1.9%    |
| Intel 11th Gen Core i5-1145G7 @ 2.60GHz     | 3         | 1.9%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 3         | 1.9%    |
| AMD Ryzen 5 3600 6-Core Processor           | 3         | 1.9%    |
| Intel Core i7-9750H CPU @ 2.60GHz           | 2         | 1.27%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 2         | 1.27%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 2         | 1.27%   |
| Intel Core i3-3217U CPU @ 1.80GHz           | 2         | 1.27%   |
| Intel Core i3 CPU M 330 @ 2.13GHz           | 2         | 1.27%   |
| Intel Celeron CPU N3450 @ 1.10GHz           | 2         | 1.27%   |
| Intel Celeron CPU 847 @ 1.10GHz             | 2         | 1.27%   |
| Intel Celeron 3205U @ 1.50GHz               | 2         | 1.27%   |
| Intel 12th Gen Core i7-12700                | 2         | 1.27%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 2         | 1.27%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz     | 2         | 1.27%   |
| AMD Ryzen 7 5700U with Radeon Graphics      | 2         | 1.27%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 2         | 1.27%   |
| Intel Xeon Gold 6144 CPU @ 3.50GHz          | 1         | 0.63%   |
| Intel Xeon CPU L5520 @ 2.27GHz              | 1         | 0.63%   |
| Intel Xeon CPU E5-2660 v3 @ 2.60GHz         | 1         | 0.63%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz        | 1         | 0.63%   |
| Intel Xeon CPU E3-1240 V2 @ 3.40GHz         | 1         | 0.63%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz    | 1         | 0.63%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz | 1         | 0.63%   |
| Intel Pentium CPU P6000 @ 1.87GHz           | 1         | 0.63%   |
| Intel Pentium CPU N4200 @ 1.10GHz           | 1         | 0.63%   |
| Intel Pentium CPU G2030 @ 3.00GHz           | 1         | 0.63%   |
| Intel Pentium CPU B980 @ 2.40GHz            | 1         | 0.63%   |
| Intel Pentium CPU 5405U @ 2.30GHz           | 1         | 0.63%   |
| Intel Pentium 4 CPU 3.00GHz                 | 1         | 0.63%   |
| Intel Genuine CPU U7300 @ 1.30GHz           | 1         | 0.63%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 1         | 0.63%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 0.63%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 0.63%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 0.63%   |
| Intel Core i7-6800K CPU @ 3.40GHz           | 1         | 0.63%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1         | 0.63%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 26        | 16.46%  |
| Intel Celeron           | 22        | 13.92%  |
| Other                   | 17        | 10.76%  |
| Intel Core i7           | 17        | 10.76%  |
| AMD Ryzen 5             | 11        | 6.96%   |
| Intel Core i3           | 9         | 5.7%    |
| Intel Core 2 Duo        | 7         | 4.43%   |
| AMD Ryzen 7             | 6         | 3.8%    |
| Intel Pentium           | 5         | 3.16%   |
| Intel Atom              | 5         | 3.16%   |
| Intel Xeon              | 4         | 2.53%   |
| AMD Ryzen 9             | 4         | 2.53%   |
| AMD A6                  | 4         | 2.53%   |
| AMD Ryzen 3             | 2         | 1.27%   |
| Intel Xeon Gold         | 1         | 0.63%   |
| Intel Pentium Silver    | 1         | 0.63%   |
| Intel Pentium Dual-Core | 1         | 0.63%   |
| Intel Pentium 4         | 1         | 0.63%   |
| Intel Genuine           | 1         | 0.63%   |
| Intel Core 2            | 1         | 0.63%   |
| ARM Allwinner           | 1         | 0.63%   |
| AMD Sempron             | 1         | 0.63%   |
| AMD Ryzen 7 PRO         | 1         | 0.63%   |
| AMD Ryzen 5 PRO         | 1         | 0.63%   |
| AMD Phenom II X4        | 1         | 0.63%   |
| AMD FX                  | 1         | 0.63%   |
| AMD E2                  | 1         | 0.63%   |
| AMD E1                  | 1         | 0.63%   |
| AMD Athlon II X2        | 1         | 0.63%   |
| AMD Athlon II           | 1         | 0.63%   |
| AMD A8                  | 1         | 0.63%   |
| AMD A4                  | 1         | 0.63%   |
| AMD A10                 | 1         | 0.63%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 66        | 41.77%  |
| 4       | 54        | 34.18%  |
| 6       | 13        | 8.23%   |
| 8       | 11        | 6.96%   |
| 12      | 4         | 2.53%   |
| 1       | 4         | 2.53%   |
| Unknown | 3         | 1.9%    |
| 16      | 1         | 0.63%   |
| 10      | 1         | 0.63%   |
| 3       | 1         | 0.63%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 153       | 97.45%  |
| Unknown | 3         | 1.91%   |
| 2       | 1         | 0.64%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 90        | 57.32%  |
| 1       | 64        | 40.76%  |
| Unknown | 3         | 1.91%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 155       | 98.73%  |
| Unknown        | 2         | 1.27%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 56        | 35.67%  |
| 0x806c1    | 9         | 5.73%   |
| 0x306a9    | 7         | 4.46%   |
| 0x30678    | 5         | 3.18%   |
| 0x406e3    | 4         | 2.55%   |
| 0x206a7    | 4         | 2.55%   |
| 0x906ea    | 3         | 1.91%   |
| 0x506c9    | 3         | 1.91%   |
| 0x306d4    | 3         | 1.91%   |
| 0x1067a    | 3         | 1.91%   |
| 0x08608103 | 3         | 1.91%   |
| 0x0800820d | 3         | 1.91%   |
| 0xa0652    | 2         | 1.27%   |
| 0x90672    | 2         | 1.27%   |
| 0x806ec    | 2         | 1.27%   |
| 0x806e9    | 2         | 1.27%   |
| 0x6fb      | 2         | 1.27%   |
| 0x506ca    | 2         | 1.27%   |
| 0x406c4    | 2         | 1.27%   |
| 0x406c3    | 2         | 1.27%   |
| 0x20652    | 2         | 1.27%   |
| 0x106e5    | 2         | 1.27%   |
| 0x0a50000c | 2         | 1.27%   |
| 0x08701021 | 2         | 1.27%   |
| 0x08108109 | 2         | 1.27%   |
| 0xa0653    | 1         | 0.64%   |
| 0x906ed    | 1         | 0.64%   |
| 0x906c0    | 1         | 0.64%   |
| 0x806ea    | 1         | 0.64%   |
| 0x706a8    | 1         | 0.64%   |
| 0x706a1    | 1         | 0.64%   |
| 0x6f6      | 1         | 0.64%   |
| 0x506e3    | 1         | 0.64%   |
| 0x50654    | 1         | 0.64%   |
| 0x40651    | 1         | 0.64%   |
| 0x306f2    | 1         | 0.64%   |
| 0x306c3    | 1         | 0.64%   |
| 0x30661    | 1         | 0.64%   |
| 0x20655    | 1         | 0.64%   |
| 0x106a5    | 1         | 0.64%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 15        | 9.49%   |
| IvyBridge        | 12        | 7.59%   |
| TigerLake        | 11        | 6.96%   |
| Skylake          | 10        | 6.33%   |
| Silvermont       | 10        | 6.33%   |
| SandyBridge      | 9         | 5.7%    |
| Unknown          | 9         | 5.7%    |
| Zen 2            | 7         | 4.43%   |
| Zen+             | 6         | 3.8%    |
| Penryn           | 6         | 3.8%    |
| Haswell          | 6         | 3.8%    |
| Goldmont         | 6         | 3.8%    |
| Zen 3            | 5         | 3.16%   |
| Westmere         | 5         | 3.16%   |
| Core             | 4         | 2.53%   |
| Broadwell        | 4         | 2.53%   |
| Zen              | 3         | 1.9%    |
| Piledriver       | 3         | 1.9%    |
| Nehalem          | 3         | 1.9%    |
| K10              | 3         | 1.9%    |
| Goldmont plus    | 3         | 1.9%    |
| CometLake        | 3         | 1.9%    |
| Puma             | 2         | 1.27%   |
| K10 Llano        | 2         | 1.27%   |
| Excavator        | 2         | 1.27%   |
| Bonnell          | 2         | 1.27%   |
| Alderlake Hybrid | 2         | 1.27%   |
| Tremont          | 1         | 0.63%   |
| NetBurst         | 1         | 0.63%   |
| Jaguar           | 1         | 0.63%   |
| IceLake          | 1         | 0.63%   |
| Bobcat           | 1         | 0.63%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 97        | 55.75%  |
| Nvidia                     | 39        | 22.41%  |
| AMD                        | 35        | 20.11%  |
| ASPEED Technology          | 2         | 1.15%   |
| Matrox Electronics Systems | 1         | 0.57%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 9         | 5.06%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9         | 5.06%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 7         | 3.93%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 3.37%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 6         | 3.37%   |
| Intel HD Graphics 500                                                                    | 5         | 2.81%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4         | 2.25%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 2.25%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3         | 1.69%   |
| Intel HD Graphics 620                                                                    | 3         | 1.69%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3         | 1.69%   |
| AMD Lucienne                                                                             | 3         | 1.69%   |
| AMD Cezanne                                                                              | 3         | 1.69%   |
| Nvidia GT216 [GeForce GT 220]                                                            | 2         | 1.12%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 2         | 1.12%   |
| Intel UHD Graphics 620                                                                   | 2         | 1.12%   |
| Intel Tiger Lake UHD Graphics                                                            | 2         | 1.12%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.12%   |
| Intel HD Graphics                                                                        | 2         | 1.12%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 1.12%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 1.12%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 1.12%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.12%   |
| Intel AlderLake-S GT1                                                                    | 2         | 1.12%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 2         | 1.12%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 2         | 1.12%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 1.12%   |
| AMD Renoir                                                                               | 2         | 1.12%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 1.12%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 1.12%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.56%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 1         | 0.56%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.56%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 1         | 0.56%   |
| Nvidia TU104 [GeForce RTX 2080]                                                          | 1         | 0.56%   |
| Nvidia TU104 [GeForce RTX 2060]                                                          | 1         | 0.56%   |
| Nvidia GT218 [GeForce 310]                                                               | 1         | 0.56%   |
| Nvidia GT216M [NVS 5100M]                                                                | 1         | 0.56%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.56%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 1         | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 81        | 51.59%  |
| 1 x AMD         | 26        | 16.56%  |
| 1 x Nvidia      | 23        | 14.65%  |
| Intel + Nvidia  | 10        | 6.37%   |
| Other           | 6         | 3.82%   |
| AMD + Nvidia    | 4         | 2.55%   |
| 2 x AMD         | 2         | 1.27%   |
| Nvidia + ASPEED | 2         | 1.27%   |
| Intel + AMD     | 2         | 1.27%   |
| AMD + Matrox    | 1         | 0.64%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 128       | 81.53%  |
| Proprietary | 20        | 12.74%  |
| Unknown     | 9         | 5.73%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 116       | 73.89%  |
| 0.01-0.5   | 14        | 8.92%   |
| 1.01-2.0   | 11        | 7.01%   |
| 0.51-1.0   | 8         | 5.1%    |
| 3.01-4.0   | 3         | 1.91%   |
| 8.01-16.0  | 3         | 1.91%   |
| 7.01-8.0   | 1         | 0.64%   |
| 5.01-6.0   | 1         | 0.64%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 23        | 13.94%  |
| AU Optronics            | 20        | 12.12%  |
| LG Display              | 18        | 10.91%  |
| Chimei Innolux          | 12        | 7.27%   |
| Dell                    | 11        | 6.67%   |
| BOE                     | 11        | 6.67%   |
| Hewlett-Packard         | 7         | 4.24%   |
| Goldstar                | 6         | 3.64%   |
| ViewSonic               | 5         | 3.03%   |
| Chi Mei Optoelectronics | 5         | 3.03%   |
| PANDA                   | 4         | 2.42%   |
| Lenovo                  | 4         | 2.42%   |
| Iiyama                  | 4         | 2.42%   |
| Acer                    | 4         | 2.42%   |
| Philips                 | 3         | 1.82%   |
| InfoVision              | 3         | 1.82%   |
| Toshiba                 | 2         | 1.21%   |
| BenQ                    | 2         | 1.21%   |
| Apple                   | 2         | 1.21%   |
| AOC                     | 2         | 1.21%   |
| Vestel Elektronik       | 1         | 0.61%   |
| TEO                     | 1         | 0.61%   |
| TCL                     | 1         | 0.61%   |
| Sharp                   | 1         | 0.61%   |
| Sceptre Tech            | 1         | 0.61%   |
| RTK                     | 1         | 0.61%   |
| Panasonic               | 1         | 0.61%   |
| Nixeus                  | 1         | 0.61%   |
| Medion                  | 1         | 0.61%   |
| MAG                     | 1         | 0.61%   |
| LG Philips              | 1         | 0.61%   |
| LG Electronics          | 1         | 0.61%   |
| KDC                     | 1         | 0.61%   |
| HannStar                | 1         | 0.61%   |
| Fujitsu Siemens         | 1         | 0.61%   |
| CSO                     | 1         | 0.61%   |
| Ancor Communications    | 1         | 0.61%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 3         | 1.81%   |
| LG Display LCD Monitor LGD0430 1366x768 345x194mm 15.6-inch              | 2         | 1.2%    |
| Hewlett-Packard 2309 HWP2821 1920x1080 510x287mm 23.0-inch               | 2         | 1.2%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 2         | 1.2%    |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                     | 2         | 1.2%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 2         | 1.2%    |
| ViewSonic XG2703-GS VSCBA32 2560x1440 598x336mm 27.0-inch                | 1         | 0.6%    |
| ViewSonic XG2401 SERIES VSCBB31 1920x1080 531x299mm 24.0-inch            | 1         | 0.6%    |
| ViewSonic VX3276-UHD VSC5138 3840x2160 697x392mm 31.5-inch               | 1         | 0.6%    |
| ViewSonic VA2259 Series VSC5E32 1920x1080 476x268mm 21.5-inch            | 1         | 0.6%    |
| ViewSonic VA1948 SERIES VSCE827 1440x900 408x255mm 18.9-inch             | 1         | 0.6%    |
| Vestel Elektronik 24W_LCD_TV VES3700 1920x1080 706x398mm 31.9-inch       | 1         | 0.6%    |
| Toshiba TV TSB0109 1920x1080 1594x900mm 72.1-inch                        | 1         | 0.6%    |
| Toshiba ScreenXpert TSB8888 1080x2160                                    | 1         | 0.6%    |
| TEO TL765 TEO6700 1280x1024 338x270mm 17.0-inch                          | 1         | 0.6%    |
| TCL LCD TV TCL0030 1920x1080 708x398mm 32.0-inch                         | 1         | 0.6%    |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                  | 1         | 0.6%    |
| Sceptre Tech Sceptre N43 SPT110C 3840x2160 575x323mm 26.0-inch           | 1         | 0.6%    |
| Samsung Electronics SyncMaster SAM0657 1920x1080                         | 1         | 0.6%    |
| Samsung Electronics SyncMaster SAM0653 1920x1080                         | 1         | 0.6%    |
| Samsung Electronics SyncMaster SAM027C 1680x1050 433x271mm 20.1-inch     | 1         | 0.6%    |
| Samsung Electronics SyncMaster SAM00E5 1280x1024 338x270mm 17.0-inch     | 1         | 0.6%    |
| Samsung Electronics SME1920N SAM06A3 1366x768 410x230mm 18.5-inch        | 1         | 0.6%    |
| Samsung Electronics SM2333TN SAM06FC 1920x1080 477x268mm 21.5-inch       | 1         | 0.6%    |
| Samsung Electronics S24E650 SAM0C86 1920x1200 518x324mm 24.1-inch        | 1         | 0.6%    |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch        | 1         | 0.6%    |
| Samsung Electronics S19C150 SAM0AE6 1366x768 410x230mm 18.5-inch         | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC4E45 1280x800 331x207mm 15.4-inch     | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch     | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC3849 1366x768 309x174mm 14.0-inch     | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC3454 1600x900 382x215mm 17.3-inch     | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SDC4A52 1366x768 344x194mm 15.5-inch     | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch    | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SAM7048 1360x768 522x293mm 23.6-inch     | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SAM0B30 1920x1080 885x498mm 40.0-inch    | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SAM07BB 1360x768 410x256mm 19.0-inch     | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SAM0530 1360x768                         | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SAM04FD 1360x768                         | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SAM03BC 1920x1080                        | 1         | 0.6%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 73        | 46.2%   |
| 1366x768 (WXGA)    | 36        | 22.78%  |
| 1600x900 (HD+)     | 7         | 4.43%   |
| 1280x1024 (SXGA)   | 7         | 4.43%   |
| 3840x2160 (4K)     | 6         | 3.8%    |
| 1440x900 (WXGA+)   | 6         | 3.8%    |
| 2560x1440 (QHD)    | 3         | 1.9%    |
| 1920x1200 (WUXGA)  | 3         | 1.9%    |
| 1680x1050 (WSXGA+) | 3         | 1.9%    |
| 1280x800 (WXGA)    | 3         | 1.9%    |
| 1360x768           | 2         | 1.27%   |
| 1024x600           | 2         | 1.27%   |
| 3840x1600          | 1         | 0.63%   |
| 2880x1800          | 1         | 0.63%   |
| 2560x1600          | 1         | 0.63%   |
| 2560x1080          | 1         | 0.63%   |
| 2160x1440          | 1         | 0.63%   |
| 1366x912           | 1         | 0.63%   |
| 1024x768 (XGA)     | 1         | 0.63%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 41        | 24.7%   |
| 14      | 19        | 11.45%  |
| 13      | 18        | 10.84%  |
| 23      | 13        | 7.83%   |
| 24      | 11        | 6.63%   |
| 17      | 10        | 6.02%   |
| 21      | 8         | 4.82%   |
| 27      | 6         | 3.61%   |
| 19      | 6         | 3.61%   |
| Unknown | 6         | 3.61%   |
| 18      | 5         | 3.01%   |
| 26      | 4         | 2.41%   |
| 12      | 3         | 1.81%   |
| 31      | 2         | 1.2%    |
| 20      | 2         | 1.2%    |
| 11      | 2         | 1.2%    |
| 10      | 2         | 1.2%    |
| 84      | 1         | 0.6%    |
| 72      | 1         | 0.6%    |
| 54      | 1         | 0.6%    |
| 37      | 1         | 0.6%    |
| 32      | 1         | 0.6%    |
| 30      | 1         | 0.6%    |
| 25      | 1         | 0.6%    |
| 22      | 1         | 0.6%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 78        | 46.99%  |
| 501-600     | 35        | 21.08%  |
| 401-500     | 21        | 12.65%  |
| 201-300     | 12        | 7.23%   |
| 351-400     | 6         | 3.61%   |
| Unknown     | 6         | 3.61%   |
| 601-700     | 3         | 1.81%   |
| 1501-2000   | 2         | 1.2%    |
| 801-900     | 1         | 0.6%    |
| 701-800     | 1         | 0.6%    |
| 1001-1500   | 1         | 0.6%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 121       | 79.08%  |
| 16/10   | 20        | 13.07%  |
| 5/4     | 6         | 3.92%   |
| 3/2     | 2         | 1.31%   |
| Unknown | 2         | 1.31%   |
| 4/3     | 1         | 0.65%   |
| 21/9    | 1         | 0.65%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 41        | 24.85%  |
| 81-90          | 33        | 20%     |
| 201-250        | 25        | 15.15%  |
| 151-200        | 14        | 8.48%   |
| 301-350        | 8         | 4.85%   |
| 141-150        | 8         | 4.85%   |
| 251-300        | 6         | 3.64%   |
| Unknown        | 6         | 3.64%   |
| 71-80          | 5         | 3.03%   |
| 351-500        | 4         | 2.42%   |
| 121-130        | 4         | 2.42%   |
| More than 1000 | 3         | 1.82%   |
| 61-70          | 2         | 1.21%   |
| 51-60          | 2         | 1.21%   |
| 41-50          | 2         | 1.21%   |
| 131-140        | 1         | 0.61%   |
| 501-1000       | 1         | 0.61%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 57        | 34.97%  |
| 101-120       | 47        | 28.83%  |
| 121-160       | 45        | 27.61%  |
| Unknown       | 6         | 3.68%   |
| More than 240 | 3         | 1.84%   |
| 161-240       | 3         | 1.84%   |
| 1-50          | 2         | 1.23%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 134       | 85.35%  |
| 2     | 18        | 11.46%  |
| 0     | 4         | 2.55%   |
| 3     | 1         | 0.64%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 79        | 36.92%  |
| Realtek Semiconductor             | 76        | 35.51%  |
| Qualcomm Atheros                  | 19        | 8.88%   |
| Broadcom                          | 12        | 5.61%   |
| MediaTek                          | 3         | 1.4%    |
| Sierra Wireless                   | 2         | 0.93%   |
| Ralink Technology                 | 2         | 0.93%   |
| Nvidia                            | 2         | 0.93%   |
| Marvell Technology Group          | 2         | 0.93%   |
| Huawei Technologies               | 2         | 0.93%   |
| Dell                              | 2         | 0.93%   |
| TRENDnet                          | 1         | 0.47%   |
| TP-Link                           | 1         | 0.47%   |
| Samsung Electronics               | 1         | 0.47%   |
| Ralink                            | 1         | 0.47%   |
| Qualcomm Atheros Communications   | 1         | 0.47%   |
| Microsoft                         | 1         | 0.47%   |
| Microchip Technology              | 1         | 0.47%   |
| Hewlett-Packard                   | 1         | 0.47%   |
| Ericsson Business Mobile Networks | 1         | 0.47%   |
| D-Link System                     | 1         | 0.47%   |
| BUFFALO                           | 1         | 0.47%   |
| Broadcom Limited                  | 1         | 0.47%   |
| Attansic Technology               | 1         | 0.47%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 50        | 19.23%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 3.85%   |
| Intel Wi-Fi 6 AX201                                               | 9         | 3.46%   |
| Intel Wi-Fi 6 AX200                                               | 7         | 2.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 2.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 6         | 2.31%   |
| Intel Wireless 8260                                               | 6         | 2.31%   |
| Realtek 802.11ac NIC                                              | 5         | 1.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 1.92%   |
| Intel Wireless 3165                                               | 5         | 1.92%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 1.92%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.54%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 1.54%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 4         | 1.54%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 1.54%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1.54%   |
| Intel Wireless 8265 / 8275                                        | 4         | 1.54%   |
| Intel I211 Gigabit Network Connection                             | 4         | 1.54%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 1.54%   |
| Intel Wireless 7265                                               | 3         | 1.15%   |
| Intel Ethernet Connection (2) I218-V                              | 3         | 1.15%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 1.15%   |
| Sierra Wireless EM7455                                            | 2         | 0.77%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 0.77%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.77%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 2         | 0.77%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 0.77%   |
| Nvidia MCP61 Ethernet                                             | 2         | 0.77%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 0.77%   |
| Intel Wireless 7260                                               | 2         | 0.77%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 2         | 0.77%   |
| Intel I210 Gigabit Network Connection                             | 2         | 0.77%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.77%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 0.77%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 0.77%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 2         | 0.77%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 0.77%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 2         | 0.77%   |
| Intel 82566MM Gigabit Network Connection                          | 2         | 0.77%   |
| Huawei YAL-L21                                                    | 2         | 0.77%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 58        | 46.03%  |
| Realtek Semiconductor           | 28        | 22.22%  |
| Qualcomm Atheros                | 18        | 14.29%  |
| Broadcom                        | 7         | 5.56%   |
| MediaTek                        | 3         | 2.38%   |
| Sierra Wireless                 | 2         | 1.59%   |
| Ralink Technology               | 2         | 1.59%   |
| Dell                            | 2         | 1.59%   |
| TRENDnet                        | 1         | 0.79%   |
| Ralink                          | 1         | 0.79%   |
| Qualcomm Atheros Communications | 1         | 0.79%   |
| Microsoft                       | 1         | 0.79%   |
| D-Link System                   | 1         | 0.79%   |
| BUFFALO                         | 1         | 0.79%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                                        | 9         | 7.03%   |
| Intel Wi-Fi 6 AX200                                                        | 7         | 5.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 6         | 4.69%   |
| Intel Wireless 8260                                                        | 6         | 4.69%   |
| Realtek 802.11ac NIC                                                       | 5         | 3.91%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                 | 5         | 3.91%   |
| Intel Wireless 3165                                                        | 5         | 3.91%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                   | 4         | 3.13%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                            | 4         | 3.13%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                 | 4         | 3.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 4         | 3.13%   |
| Intel Wireless 8265 / 8275                                                 | 4         | 3.13%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                               | 4         | 3.13%   |
| Intel Wireless 7265                                                        | 3         | 2.34%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                        | 3         | 2.34%   |
| Sierra Wireless EM7455                                                     | 2         | 1.56%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                 | 2         | 1.56%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                           | 2         | 1.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)             | 2         | 1.56%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter              | 2         | 1.56%   |
| Intel Wireless 7260                                                        | 2         | 1.56%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection              | 2         | 1.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 2         | 1.56%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                            | 2         | 1.56%   |
| Intel Comet Lake PCH CNVi WiFi                                             | 2         | 1.56%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                               | 2         | 1.56%   |
| TRENDnet TEW-805UB 300Mbps+867Mbps Wireless AC Adapter [Realtek RTL8812AU] | 1         | 0.78%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                   | 1         | 0.78%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                   | 1         | 0.78%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                   | 1         | 0.78%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                 | 1         | 0.78%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                 | 1         | 0.78%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                   | 1         | 0.78%   |
| Realtek 802.11n WLAN Adapter                                               | 1         | 0.78%   |
| Ralink RT2770 Wireless Adapter                                             | 1         | 0.78%   |
| Ralink MT7601U Wireless Adapter                                            | 1         | 0.78%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                     | 1         | 0.78%   |
| Qualcomm Atheros AR9271 802.11n                                            | 1         | 0.78%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                           | 1         | 0.78%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)             | 1         | 0.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 65        | 50.78%  |
| Intel                    | 43        | 33.59%  |
| Broadcom                 | 5         | 3.91%   |
| Qualcomm Atheros         | 4         | 3.13%   |
| Nvidia                   | 2         | 1.56%   |
| Marvell Technology Group | 2         | 1.56%   |
| Huawei Technologies      | 2         | 1.56%   |
| TP-Link                  | 1         | 0.78%   |
| Samsung Electronics      | 1         | 0.78%   |
| Hewlett-Packard          | 1         | 0.78%   |
| Broadcom Limited         | 1         | 0.78%   |
| Attansic Technology      | 1         | 0.78%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 50        | 38.46%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 10        | 7.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 7         | 5.38%   |
| Intel Ethernet Connection I219-LM                                              | 5         | 3.85%   |
| Realtek RTL8125 2.5GbE Controller                                              | 4         | 3.08%   |
| Intel I211 Gigabit Network Connection                                          | 4         | 3.08%   |
| Intel Ethernet Connection (2) I218-V                                           | 3         | 2.31%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2         | 1.54%   |
| Nvidia MCP61 Ethernet                                                          | 2         | 1.54%   |
| Intel I210 Gigabit Network Connection                                          | 2         | 1.54%   |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 1.54%   |
| Intel Ethernet Connection (2) I219-V                                           | 2         | 1.54%   |
| Intel 82566MM Gigabit Network Connection                                       | 2         | 1.54%   |
| Huawei YAL-L21                                                                 | 2         | 1.54%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 0.77%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.77%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.77%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.77%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.77%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.77%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.77%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 0.77%   |
| Intel I350 Gigabit Fiber Network Connection                                    | 1         | 0.77%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.77%   |
| Intel Ethernet Connection I217-V                                               | 1         | 0.77%   |
| Intel Ethernet Connection I217-LM                                              | 1         | 0.77%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.77%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.77%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 0.77%   |
| Intel Ethernet Connection (14) I219-V                                          | 1         | 0.77%   |
| Intel Ethernet Connection (13) I219-V                                          | 1         | 0.77%   |
| Intel Ethernet Connection (13) I219-LM                                         | 1         | 0.77%   |
| Intel Ethernet Connection (11) I219-LM                                         | 1         | 0.77%   |
| Intel 82578DM Gigabit Network Connection                                       | 1         | 0.77%   |
| Intel 82578DC Gigabit Network Connection                                       | 1         | 0.77%   |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 0.77%   |
| Intel 82576 Gigabit Network Connection                                         | 1         | 0.77%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 1         | 0.77%   |
| Intel 82566DM-2 Gigabit Network Connection                                     | 1         | 0.77%   |
| HP lt4120 Snapdragon X5 LTE                                                    | 1         | 0.77%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 123       | 50.83%  |
| WiFi     | 117       | 48.35%  |
| Modem    | 2         | 0.83%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 93        | 60%     |
| Ethernet | 62        | 40%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 81        | 51.59%  |
| 1     | 65        | 41.4%   |
| 0     | 9         | 5.73%   |
| 4     | 1         | 0.64%   |
| 3     | 1         | 0.64%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 103       | 65.19%  |
| Yes  | 55        | 34.81%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 45        | 51.14%  |
| Realtek Semiconductor           | 11        | 12.5%   |
| Cambridge Silicon Radio         | 7         | 7.95%   |
| Lite-On Technology              | 5         | 5.68%   |
| Broadcom                        | 5         | 5.68%   |
| IMC Networks                    | 3         | 3.41%   |
| Foxconn / Hon Hai               | 3         | 3.41%   |
| Qualcomm Atheros Communications | 2         | 2.27%   |
| Toshiba                         | 1         | 1.14%   |
| Realtek                         | 1         | 1.14%   |
| Hewlett-Packard                 | 1         | 1.14%   |
| Dell                            | 1         | 1.14%   |
| Chicony Electronics             | 1         | 1.14%   |
| Apple                           | 1         | 1.14%   |
| Alps Electric                   | 1         | 1.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 21        | 23.86%  |
| Intel AX201 Bluetooth                               | 11        | 12.5%   |
| Realtek Bluetooth Radio                             | 7         | 7.95%   |
| Intel AX200 Bluetooth                               | 7         | 7.95%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7         | 7.95%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 3.41%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 3.41%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 2.27%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 2.27%   |
| IMC Networks Wireless_Device                        | 2         | 2.27%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 2.27%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 2.27%   |
| Toshiba Bluetooth Device                            | 1         | 1.14%   |
| Realtek RTL8723B Bluetooth                          | 1         | 1.14%   |
| Realtek Bluetooth Radio                             | 1         | 1.14%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.14%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.14%   |
| Lite-On Bluetooth Radio                             | 1         | 1.14%   |
| Lite-On Bluetooth Device                            | 1         | 1.14%   |
| Lite-On BCM43142A0                                  | 1         | 1.14%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.14%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.14%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 1.14%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 1.14%   |
| Dell Wireless 350 Bluetooth                         | 1         | 1.14%   |
| Chicony Bluetooth (RTL8723BE)                       | 1         | 1.14%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.14%   |
| Broadcom BCM2210 Bluetooth                          | 1         | 1.14%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 1.14%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 1.14%   |
| Alps Electric UGTZ4 Bluetooth                       | 1         | 1.14%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 108       | 55.96%  |
| AMD                         | 40        | 20.73%  |
| Nvidia                      | 30        | 15.54%  |
| Texas Instruments           | 2         | 1.04%   |
| JMTek                       | 2         | 1.04%   |
| C-Media Electronics         | 2         | 1.04%   |
| Tenx Technology             | 1         | 0.52%   |
| SAVITECH                    | 1         | 0.52%   |
| MAG Technology              | 1         | 0.52%   |
| Logitech                    | 1         | 0.52%   |
| Lenovo                      | 1         | 0.52%   |
| Generalplus Technology      | 1         | 0.52%   |
| FiiO Electronics Technology | 1         | 0.52%   |
| Corsair                     | 1         | 0.52%   |
| ASUSTek Computer            | 1         | 0.52%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 13        | 5.8%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 11        | 4.91%   |
| AMD Family 17h/19h HD Audio Controller                                     | 11        | 4.91%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 10        | 4.46%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 10        | 4.46%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 8         | 3.57%   |
| AMD FCH Azalia Controller                                                  | 8         | 3.57%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 7         | 3.13%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 6         | 2.68%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 6         | 2.68%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 6         | 2.68%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 6         | 2.68%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5         | 2.23%   |
| AMD Starship/Matisse HD Audio Controller                                   | 5         | 2.23%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 1.79%   |
| Nvidia GT216 HDMI Audio Controller                                         | 3         | 1.34%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 1.34%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 1.34%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.34%   |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 1.34%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 1.34%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 1.34%   |
| Intel 200 Series PCH HD Audio                                              | 3         | 1.34%   |
| AMD Kabini HDMI/DP Audio                                                   | 3         | 1.34%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 0.89%   |
| Nvidia TU104 HD Audio Controller                                           | 2         | 0.89%   |
| Nvidia MCP61 High Definition Audio                                         | 2         | 0.89%   |
| Nvidia GM206 High Definition Audio Controller                              | 2         | 0.89%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 0.89%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 0.89%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 2         | 0.89%   |
| Intel Alder Lake-S HD Audio Controller                                     | 2         | 0.89%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2         | 0.89%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 0.89%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 0.89%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 2         | 0.89%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 0.89%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 0.89%   |
| AMD High Definition Audio Controller                                       | 2         | 0.89%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 0.89%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Samsung Electronics        | 32        | 28.07%  |
| Unknown                    | 21        | 18.42%  |
| SK hynix                   | 17        | 14.91%  |
| Kingston                   | 9         | 7.89%   |
| Micron Technology          | 8         | 7.02%   |
| Crucial                    | 8         | 7.02%   |
| Corsair                    | 4         | 3.51%   |
| Unknown (ABCD)             | 3         | 2.63%   |
| G.Skill                    | 3         | 2.63%   |
| Smart                      | 2         | 1.75%   |
| Unknown (7F7F7F7F7F7F6B00) | 1         | 0.88%   |
| Ramaxel Technology         | 1         | 0.88%   |
| Nanya Technology           | 1         | 0.88%   |
| GLOWAY                     | 1         | 0.88%   |
| Foxline                    | 1         | 0.88%   |
| fef5                       | 1         | 0.88%   |
| Essencore                  | 1         | 0.88%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s            | 3         | 2.54%   |
| Unknown RAM Module 4GB Chip DDR4 2133MT/s                                   | 2         | 1.69%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s                      | 2         | 1.69%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                       | 2         | 1.69%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s                    | 2         | 1.69%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s                       | 2         | 1.69%   |
| Kingston RAM 9905713-026.A00G 4GB DIMM DDR4 2667MT/s                        | 2         | 1.69%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                                 | 1         | 0.85%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s                                 | 1         | 0.85%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                                        | 1         | 0.85%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                                 | 1         | 0.85%   |
| Unknown RAM Module 4GB DIMM SDRAM                                           | 1         | 0.85%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                                   | 1         | 0.85%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                                 | 1         | 0.85%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                                 | 1         | 0.85%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                  | 1         | 0.85%   |
| Unknown RAM Module 2GB SODIMM 667MT/s                                       | 1         | 0.85%   |
| Unknown RAM Module 2GB DIMM SDRAM                                           | 1         | 0.85%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                                   | 1         | 0.85%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                                        | 1         | 0.85%   |
| Unknown RAM Module 1GB SODIMM LPDDR3 1600MT/s                               | 1         | 0.85%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                                  | 1         | 0.85%   |
| Unknown RAM Module 1536MB SODIMM LPDDR4 2133MT/s                            | 1         | 0.85%   |
| Unknown RAM CL17-17-17 D4-2400 16384MB DIMM DDR4 2400MT/s                   | 1         | 0.85%   |
| Unknown RAM 2400 C16 Series 8192MB DIMM DDR4 1200MT/s                       | 1         | 0.85%   |
| Unknown RAM 202020202020202020202020202020202020 4096MB SODIMM DDR2 800MT/s | 1         | 0.85%   |
| Unknown (7F7F7F7F7F7F6B00) RAM 8D7T3MN8-NATP 2GB SODIMM DDR 667MT/s         | 1         | 0.85%   |
| Smart RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s                       | 1         | 0.85%   |
| Smart RAM SF564128CJ8NWMNSEG 4096MB SODIMM DDR3 1600MT/s                    | 1         | 0.85%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                                | 1         | 0.85%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1066MT/s                                | 1         | 0.85%   |
| SK hynix RAM Module 16GB DIMM DDR4 2667MT/s                                 | 1         | 0.85%   |
| SK hynix RAM HMT451U7AFR8A-PB 4GB DIMM DDR3 1600MT/s                        | 1         | 0.85%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s                        | 1         | 0.85%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB DDR3 1600MT/s                             | 1         | 0.85%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.85%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.85%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s                        | 1         | 0.85%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.85%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s                      | 1         | 0.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 46        | 45.1%   |
| DDR3    | 29        | 28.43%  |
| LPDDR4  | 11        | 10.78%  |
| Unknown | 5         | 4.9%    |
| LPDDR3  | 4         | 3.92%   |
| DDR2    | 3         | 2.94%   |
| SDRAM   | 2         | 1.96%   |
| DDR5    | 1         | 0.98%   |
| DDR     | 1         | 0.98%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 55        | 53.4%   |
| DIMM         | 35        | 33.98%  |
| Row Of Chips | 9         | 8.74%   |
| Chip         | 2         | 1.94%   |
| Unknown      | 2         | 1.94%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 35        | 33.65%  |
| 4096  | 34        | 32.69%  |
| 2048  | 16        | 15.38%  |
| 16384 | 12        | 11.54%  |
| 32768 | 3         | 2.88%   |
| 1024  | 3         | 2.88%   |
| 1536  | 1         | 0.96%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 19        | 17.76%  |
| 3200    | 16        | 14.95%  |
| 2667    | 13        | 12.15%  |
| 2133    | 9         | 8.41%   |
| 2400    | 7         | 6.54%   |
| 1333    | 6         | 5.61%   |
| 4267    | 4         | 3.74%   |
| 3600    | 4         | 3.74%   |
| 1334    | 4         | 3.74%   |
| 1066    | 4         | 3.74%   |
| 667     | 4         | 3.74%   |
| 3000    | 2         | 1.87%   |
| 2666    | 2         | 1.87%   |
| 1867    | 2         | 1.87%   |
| Unknown | 2         | 1.87%   |
| 4800    | 1         | 0.93%   |
| 3733    | 1         | 0.93%   |
| 3266    | 1         | 0.93%   |
| 3020    | 1         | 0.93%   |
| 2800    | 1         | 0.93%   |
| 2000    | 1         | 0.93%   |
| 1800    | 1         | 0.93%   |
| 1776    | 1         | 0.93%   |
| 800     | 1         | 0.93%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 3         | 60%     |
| Minolta         | 1         | 20%     |
| Canon           | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                       | Computers | Percent |
|-----------------------------|-----------|---------|
| Minolta PagePro 1300W       | 1         | 20%     |
| HP DeskJet D1360            | 1         | 20%     |
| HP DeskJet 840c             | 1         | 20%     |
| HP Deskjet 3070 B611 series | 1         | 20%     |
| Canon TS3500 series         | 1         | 20%     |

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


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 100 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 25        | 25%     |
| Realtek Semiconductor                  | 8         | 8%      |
| Quanta                                 | 7         | 7%      |
| Sunplus Innovation Technology          | 6         | 6%      |
| Microdia                               | 6         | 6%      |
| Acer                                   | 5         | 5%      |
| Suyin                                  | 4         | 4%      |
| Logitech                               | 4         | 4%      |
| IMC Networks                           | 4         | 4%      |
| Cheng Uei Precision Industry (Foxlink) | 4         | 4%      |
| Luxvisions Innotech Limited            | 3         | 3%      |
| Lite-On Technology                     | 3         | 3%      |
| Z-Star Microelectronics                | 2         | 2%      |
| Silicon Motion                         | 2         | 2%      |
| Apple                                  | 2         | 2%      |
| Alcor Micro                            | 2         | 2%      |
| USB Camera CS                          | 1         | 1%      |
| Syntek                                 | 1         | 1%      |
| SunplusIT                              | 1         | 1%      |
| Sunplus Technology                     | 1         | 1%      |
| Sonix Technology                       | 1         | 1%      |
| Samsung Electronics                    | 1         | 1%      |
| Primax Electronics                     | 1         | 1%      |
| OmniVision Technologies                | 1         | 1%      |
| Microsoft                              | 1         | 1%      |
| KYE Systems (Mouse Systems)            | 1         | 1%      |
| Importek                               | 1         | 1%      |
| Guillemot                              | 1         | 1%      |
| Creative Technology                    | 1         | 1%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony integrated camera                           | 6         | 6%      |
| Sunplus Integrated_Webcam_FHD                       | 3         | 3%      |
| Sunplus Integrated_Webcam_HD                        | 2         | 2%      |
| Realtek Integrated_Webcam_HD                        | 2         | 2%      |
| Quanta HD User Facing                               | 2         | 2%      |
| Microdia Integrated_Webcam_HD                       | 2         | 2%      |
| Logitech HD Pro Webcam C920                         | 2         | 2%      |
| Logitech BRIO Ultra HD Webcam                       | 2         | 2%      |
| IMC Networks USB2.0 HD UVC WebCam                   | 2         | 2%      |
| Chicony TOSHIBA Web Camera - HD                     | 2         | 2%      |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 2         | 2%      |
| Z-Star Traveler TV 6500 SF Dia-scanner              | 1         | 1%      |
| Z-Star Lenovo USB2.0 UVC Camera                     | 1         | 1%      |
| USB Camera CS USB Camera CS                         | 1         | 1%      |
| Syntek Lenovo EasyCamera                            | 1         | 1%      |
| Suyin HP TrueVision HD Integrated Webcam            | 1         | 1%      |
| Suyin HD WebCam                                     | 1         | 1%      |
| Suyin Asus Integrated Webcam [CN031B]               | 1         | 1%      |
| Suyin 1.3M HD WebCam                                | 1         | 1%      |
| SunplusIT USB camera                                | 1         | 1%      |
| Sunplus HD Camera                                   | 1         | 1%      |
| Sunplus ASUS USB2.0 Webcam                          | 1         | 1%      |
| Sonix USB2.0 HD UVC WebCam                          | 1         | 1%      |
| Silicon Motion ATIV VGA Camera                      | 1         | 1%      |
| Silicon Motion 300k Pixel Camera                    | 1         | 1%      |
| Samsung Galaxy A5 (MTP)                             | 1         | 1%      |
| Realtek USB Camera                                  | 1         | 1%      |
| Realtek Streaming Webcam                            | 1         | 1%      |
| Realtek Lenovo EasyCamera                           | 1         | 1%      |
| Realtek Integrated Webcam_HD                        | 1         | 1%      |
| Realtek HP Truevision HD                            | 1         | 1%      |
| Realtek Acer 640 x 480 laptop camera                | 1         | 1%      |
| Quanta USB2.0 HD UVC WebCam                         | 1         | 1%      |
| Quanta Lenovo EasyCamera                            | 1         | 1%      |
| Quanta HP Webcam                                    | 1         | 1%      |
| Quanta HP TrueVision HD Camera                      | 1         | 1%      |
| Quanta HP HD Camera                                 | 1         | 1%      |
| Primax Villem                                       | 1         | 1%      |
| OmniVision OV2640 Webcam                            | 1         | 1%      |
| Microsoft LifeCam VX-2000                           | 1         | 1%      |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 6         | 42.86%  |
| Synaptics                  | 2         | 14.29%  |
| STMicroelectronics         | 2         | 14.29%  |
| Shenzhen Goodix Technology | 2         | 14.29%  |
| Upek                       | 1         | 7.14%   |
| Elan Microelectronics      | 1         | 7.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 3         | 21.43%  |
| STMicroelectronics Fingerprint Reader                  | 2         | 14.29%  |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 7.14%   |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 7.14%   |
| Validity Sensors Synaptics WBDI                        | 1         | 7.14%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 7.14%   |
| Synaptics  WBDI                                        | 1         | 7.14%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 7.14%   |
| Shenzhen Goodix  Fingerprint Device                    | 1         | 7.14%   |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 7.14%   |
| Elan ELAN:Fingerprint                                  | 1         | 7.14%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Broadcom         | 5         | 41.67%  |
| Alcor Micro      | 4         | 33.33%  |
| O2 Micro         | 1         | 8.33%   |
| Lenovo           | 1         | 8.33%   |
| In Focus Systems | 1         | 8.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader   | 4         | 33.33%  |
| Broadcom 58200                        | 3         | 25%     |
| Broadcom 5880                         | 2         | 16.67%  |
| O2 Micro Oz776 SmartCard Reader       | 1         | 8.33%   |
| Lenovo Integrated Smart Card Reader   | 1         | 8.33%   |
| In Focus Systems EMV Smartcard Reader | 1         | 8.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 113       | 71.07%  |
| 1     | 35        | 22.01%  |
| 2     | 9         | 5.66%   |
| 5     | 1         | 0.63%   |
| 3     | 1         | 0.63%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 13        | 24.07%  |
| Chipcard                 | 12        | 22.22%  |
| Graphics card            | 11        | 20.37%  |
| Net/wireless             | 4         | 7.41%   |
| Camera                   | 4         | 7.41%   |
| Unassigned class         | 3         | 5.56%   |
| Multimedia controller    | 3         | 5.56%   |
| Sound                    | 1         | 1.85%   |
| Network                  | 1         | 1.85%   |
| Communication controller | 1         | 1.85%   |
| Card reader              | 1         | 1.85%   |

