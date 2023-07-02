Linux in Poland - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in Poland.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Poland/Desktop/README.md) and [notebooks](/Location/Poland/Notebook/README.md).

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

Total: 7668

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Packard Be... | EasyNote TSX66HR            | Notebook    | [96253a3da8](https://linux-hardware.org/?probe=96253a3da8) | Jul 01, 2023 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [eea1d9623c](https://linux-hardware.org/?probe=eea1d9623c) | Jun 30, 2023 |
| HP            | EliteBook 820 G2            | Notebook    | [c99236ef84](https://linux-hardware.org/?probe=c99236ef84) | Jun 30, 2023 |
| Lenovo        | ThinkPad T430s 23554L7      | Notebook    | [501b0860c8](https://linux-hardware.org/?probe=501b0860c8) | Jun 30, 2023 |
| Dell          | Latitude E6540              | Notebook    | [a526c901ee](https://linux-hardware.org/?probe=a526c901ee) | Jun 30, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [287d7d6f60](https://linux-hardware.org/?probe=287d7d6f60) | Jun 29, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [723de914e2](https://linux-hardware.org/?probe=723de914e2) | Jun 29, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [363067c171](https://linux-hardware.org/?probe=363067c171) | Jun 29, 2023 |
| Medion        | BTDD-TI                     | All in one  | [64b84cf34d](https://linux-hardware.org/?probe=64b84cf34d) | Jun 29, 2023 |
| Gigabyte      | P31-DS3L                    | Desktop     | [0d32728bdf](https://linux-hardware.org/?probe=0d32728bdf) | Jun 28, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [34df27504f](https://linux-hardware.org/?probe=34df27504f) | Jun 28, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [5a82f91882](https://linux-hardware.org/?probe=5a82f91882) | Jun 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | Notebook    | [9d6748ef56](https://linux-hardware.org/?probe=9d6748ef56) | Jun 28, 2023 |
| Toshiba       | TECRA R950                  | Notebook    | [cab34ec3dc](https://linux-hardware.org/?probe=cab34ec3dc) | Jun 28, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [ff919014cd](https://linux-hardware.org/?probe=ff919014cd) | Jun 28, 2023 |
| HP            | 21B4 A01                    | Desktop     | [50656fb7ec](https://linux-hardware.org/?probe=50656fb7ec) | Jun 28, 2023 |
| HP            | 21B4 A01                    | Desktop     | [4d9322819d](https://linux-hardware.org/?probe=4d9322819d) | Jun 28, 2023 |
| ASUSTek       | K54C                        | Notebook    | [4152d1fcff](https://linux-hardware.org/?probe=4152d1fcff) | Jun 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | Notebook    | [64433a8783](https://linux-hardware.org/?probe=64433a8783) | Jun 27, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [1aa332e26f](https://linux-hardware.org/?probe=1aa332e26f) | Jun 27, 2023 |
| Valve         | Jupiter                     | Notebook    | [0817dd25ff](https://linux-hardware.org/?probe=0817dd25ff) | Jun 27, 2023 |
| Dell          | Latitude 3190               | Notebook    | [5f68b5235f](https://linux-hardware.org/?probe=5f68b5235f) | Jun 27, 2023 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [157d424ec0](https://linux-hardware.org/?probe=157d424ec0) | Jun 26, 2023 |
| Toshiba       | TECRA R950                  | Notebook    | [f02bb9a43a](https://linux-hardware.org/?probe=f02bb9a43a) | Jun 26, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [b4fcf1904c](https://linux-hardware.org/?probe=b4fcf1904c) | Jun 26, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [e55023fb8b](https://linux-hardware.org/?probe=e55023fb8b) | Jun 26, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [0b72aec1b9](https://linux-hardware.org/?probe=0b72aec1b9) | Jun 26, 2023 |
| HP            | 255 G5 Notebook PC          | Notebook    | [cad891675f](https://linux-hardware.org/?probe=cad891675f) | Jun 25, 2023 |
| HP            | 21B4 A01                    | Desktop     | [e277fd2772](https://linux-hardware.org/?probe=e277fd2772) | Jun 25, 2023 |
| Biostar       | H81MHV3 5.0                 | Desktop     | [0f95f72b43](https://linux-hardware.org/?probe=0f95f72b43) | Jun 25, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [3c54b7ee02](https://linux-hardware.org/?probe=3c54b7ee02) | Jun 25, 2023 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [b4ab698b09](https://linux-hardware.org/?probe=b4ab698b09) | Jun 25, 2023 |
| eMachines     | eME732ZG                    | Notebook    | [4e1d6873ff](https://linux-hardware.org/?probe=4e1d6873ff) | Jun 24, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [0ec7fedf29](https://linux-hardware.org/?probe=0ec7fedf29) | Jun 24, 2023 |
| Packard Be... | EasyNote TK85               | Notebook    | [314e344780](https://linux-hardware.org/?probe=314e344780) | Jun 24, 2023 |
| Intel         | H81                         | Desktop     | [65ad18a4bd](https://linux-hardware.org/?probe=65ad18a4bd) | Jun 24, 2023 |
| Lenovo        | ThinkPad T430 2347BS4       | Notebook    | [a8a9689ea6](https://linux-hardware.org/?probe=a8a9689ea6) | Jun 24, 2023 |
| Lenovo        | ThinkPad L390 20NSS04400    | Notebook    | [feced26491](https://linux-hardware.org/?probe=feced26491) | Jun 23, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [c75670186a](https://linux-hardware.org/?probe=c75670186a) | Jun 23, 2023 |
| MSI           | B360M PRO-VD 2019-01-24     | Desktop     | [a036f44a4c](https://linux-hardware.org/?probe=a036f44a4c) | Jun 22, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [17db397c48](https://linux-hardware.org/?probe=17db397c48) | Jun 22, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [0b8cf1cae7](https://linux-hardware.org/?probe=0b8cf1cae7) | Jun 22, 2023 |
| Medion        | BTDD-TI                     | All in one  | [8845f67824](https://linux-hardware.org/?probe=8845f67824) | Jun 22, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [d4d7534ac3](https://linux-hardware.org/?probe=d4d7534ac3) | Jun 22, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [0f5435c665](https://linux-hardware.org/?probe=0f5435c665) | Jun 22, 2023 |
| Toshiba       | Satellite Pro C70-B         | Notebook    | [f96a1a3552](https://linux-hardware.org/?probe=f96a1a3552) | Jun 21, 2023 |
| Lenovo        | ThinkPad L470 20J5S01S00    | Notebook    | [5de086be7a](https://linux-hardware.org/?probe=5de086be7a) | Jun 21, 2023 |
| Toshiba       | Satellite Pro C70-B         | Notebook    | [52c4c32098](https://linux-hardware.org/?probe=52c4c32098) | Jun 21, 2023 |
| Notebook      | NV4xPZ                      | Notebook    | [873c70b184](https://linux-hardware.org/?probe=873c70b184) | Jun 21, 2023 |
| Gigabyte      | H510M S2H V2                | Desktop     | [d7c44291c1](https://linux-hardware.org/?probe=d7c44291c1) | Jun 20, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [bbfb6ff07f](https://linux-hardware.org/?probe=bbfb6ff07f) | Jun 20, 2023 |
| Lenovo        | B570 HuronRiver Platform    | Notebook    | [b51dda105a](https://linux-hardware.org/?probe=b51dda105a) | Jun 20, 2023 |
| Gigabyte      | H510M S2H V2                | Desktop     | [f2d80b2558](https://linux-hardware.org/?probe=f2d80b2558) | Jun 19, 2023 |
| Toshiba       | Satellite A300              | Notebook    | [f37d67a18d](https://linux-hardware.org/?probe=f37d67a18d) | Jun 19, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [1559b0a68d](https://linux-hardware.org/?probe=1559b0a68d) | Jun 19, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [22d8476417](https://linux-hardware.org/?probe=22d8476417) | Jun 19, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [e2fc6bb607](https://linux-hardware.org/?probe=e2fc6bb607) | Jun 19, 2023 |
| Razer         | Blade Stealth 13 (Early ... | Notebook    | [e3843be450](https://linux-hardware.org/?probe=e3843be450) | Jun 18, 2023 |
| ASRock        | Z87 Extreme4                | Desktop     | [dcd3e79cb1](https://linux-hardware.org/?probe=dcd3e79cb1) | Jun 18, 2023 |
| HP            | Pavilion dv2                | Notebook    | [3f3b0104a4](https://linux-hardware.org/?probe=3f3b0104a4) | Jun 18, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [17c61c0aee](https://linux-hardware.org/?probe=17c61c0aee) | Jun 18, 2023 |
| Gigabyte      | Z170-Gaming K3-CF           | Desktop     | [6e40a39112](https://linux-hardware.org/?probe=6e40a39112) | Jun 18, 2023 |
| HP            | Notebook                    | Notebook    | [60eebb0602](https://linux-hardware.org/?probe=60eebb0602) | Jun 18, 2023 |
| HP            | Pavilion x2 Detachable      | Tablet      | [e01ed6ab42](https://linux-hardware.org/?probe=e01ed6ab42) | Jun 17, 2023 |
| Dell          | Latitude 5420               | Notebook    | [f7c9224ef1](https://linux-hardware.org/?probe=f7c9224ef1) | Jun 17, 2023 |
| Dell          | Latitude 5420               | Notebook    | [f553a4e5e7](https://linux-hardware.org/?probe=f553a4e5e7) | Jun 17, 2023 |
| Dell          | Latitude 9420               | Convertible | [c60ca4bcc4](https://linux-hardware.org/?probe=c60ca4bcc4) | Jun 17, 2023 |
| Dell          | Latitude 9420               | Convertible | [444f324394](https://linux-hardware.org/?probe=444f324394) | Jun 16, 2023 |
| MSI           | B85-G43 GAMING              | Desktop     | [93da970965](https://linux-hardware.org/?probe=93da970965) | Jun 16, 2023 |
| ASRock        | H61M-VG3                    | Desktop     | [858be00df4](https://linux-hardware.org/?probe=858be00df4) | Jun 16, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [0d47dc3760](https://linux-hardware.org/?probe=0d47dc3760) | Jun 16, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [dc48180bc7](https://linux-hardware.org/?probe=dc48180bc7) | Jun 16, 2023 |
| STONE COMP... | NOTCHA-286                  | Notebook    | [9536ebc16b](https://linux-hardware.org/?probe=9536ebc16b) | Jun 16, 2023 |
| Dell          | Latitude E6400              | Notebook    | [7c59595887](https://linux-hardware.org/?probe=7c59595887) | Jun 16, 2023 |
| STONE COMP... | NOTCHA-286                  | Notebook    | [00a14ade70](https://linux-hardware.org/?probe=00a14ade70) | Jun 16, 2023 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [558c031517](https://linux-hardware.org/?probe=558c031517) | Jun 16, 2023 |
| Valve         | Jupiter                     | Notebook    | [29869b2464](https://linux-hardware.org/?probe=29869b2464) | Jun 15, 2023 |
| Valve         | Jupiter                     | Notebook    | [bdd96d41a7](https://linux-hardware.org/?probe=bdd96d41a7) | Jun 15, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [a1c36c44b1](https://linux-hardware.org/?probe=a1c36c44b1) | Jun 15, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [8d88084588](https://linux-hardware.org/?probe=8d88084588) | Jun 15, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [16ad11571a](https://linux-hardware.org/?probe=16ad11571a) | Jun 15, 2023 |
| Lenovo        | ThinkPad T490 20N20032US    | Notebook    | [3df7663e0d](https://linux-hardware.org/?probe=3df7663e0d) | Jun 15, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | Desktop     | [c612df2e8c](https://linux-hardware.org/?probe=c612df2e8c) | Jun 15, 2023 |
| ASUSTek       | K52N                        | Notebook    | [eb2ec7cb3d](https://linux-hardware.org/?probe=eb2ec7cb3d) | Jun 15, 2023 |
| ASRock        | B85M                        | Desktop     | [19f8b16937](https://linux-hardware.org/?probe=19f8b16937) | Jun 15, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [8a04ec65f7](https://linux-hardware.org/?probe=8a04ec65f7) | Jun 15, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [7670492b40](https://linux-hardware.org/?probe=7670492b40) | Jun 15, 2023 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [dbe7676807](https://linux-hardware.org/?probe=dbe7676807) | Jun 15, 2023 |
| ASUSTek       | P5G41C-M LX                 | Desktop     | [7ae654d4e2](https://linux-hardware.org/?probe=7ae654d4e2) | Jun 14, 2023 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [39e2711f1f](https://linux-hardware.org/?probe=39e2711f1f) | Jun 13, 2023 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [2ae3c4aaca](https://linux-hardware.org/?probe=2ae3c4aaca) | Jun 13, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [ad01f2c38d](https://linux-hardware.org/?probe=ad01f2c38d) | Jun 13, 2023 |
| ASUSTek       | P5G41C-M LX                 | Desktop     | [1361d3551c](https://linux-hardware.org/?probe=1361d3551c) | Jun 12, 2023 |
| Xunlong       | Orange Pi PC                | Soc         | [2a93adb1f0](https://linux-hardware.org/?probe=2a93adb1f0) | Jun 12, 2023 |
| Dell          | 0TKM9Y A00                  | Mini pc     | [1fad9d3d52](https://linux-hardware.org/?probe=1fad9d3d52) | Jun 12, 2023 |
| Dell          | Latitude 3190               | Notebook    | [2c8d7ef5b6](https://linux-hardware.org/?probe=2c8d7ef5b6) | Jun 12, 2023 |
| MSI           | GE62 6QC                    | Notebook    | [5581a5c589](https://linux-hardware.org/?probe=5581a5c589) | Jun 12, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [2ea9fd5a4a](https://linux-hardware.org/?probe=2ea9fd5a4a) | Jun 12, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [273795ce3d](https://linux-hardware.org/?probe=273795ce3d) | Jun 12, 2023 |
| Google        | Blorb                       | Notebook    | [0083999b8a](https://linux-hardware.org/?probe=0083999b8a) | Jun 12, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [8a9a32ba11](https://linux-hardware.org/?probe=8a9a32ba11) | Jun 12, 2023 |
| Google        | Blorb                       | Notebook    | [516c0548dc](https://linux-hardware.org/?probe=516c0548dc) | Jun 12, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [de08f65c4d](https://linux-hardware.org/?probe=de08f65c4d) | Jun 11, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [b88dfc7e5c](https://linux-hardware.org/?probe=b88dfc7e5c) | Jun 11, 2023 |
| HP            | 3397                        | Desktop     | [9f71c4173c](https://linux-hardware.org/?probe=9f71c4173c) | Jun 11, 2023 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [67867c022f](https://linux-hardware.org/?probe=67867c022f) | Jun 11, 2023 |
| Dell          | Precision 5520              | Notebook    | [bcbd324c4b](https://linux-hardware.org/?probe=bcbd324c4b) | Jun 11, 2023 |
| Dell          | Precision 5520              | Notebook    | [ab408edcbd](https://linux-hardware.org/?probe=ab408edcbd) | Jun 11, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [d6681f05ec](https://linux-hardware.org/?probe=d6681f05ec) | Jun 11, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [0e257c3bd8](https://linux-hardware.org/?probe=0e257c3bd8) | Jun 11, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [bfde2cf63d](https://linux-hardware.org/?probe=bfde2cf63d) | Jun 10, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [7c79725474](https://linux-hardware.org/?probe=7c79725474) | Jun 10, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [5e060b53c2](https://linux-hardware.org/?probe=5e060b53c2) | Jun 10, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [0d548e314b](https://linux-hardware.org/?probe=0d548e314b) | Jun 10, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [2627421665](https://linux-hardware.org/?probe=2627421665) | Jun 09, 2023 |
| HP            | Stream Laptop 14-ds0xxx     | Notebook    | [fb9e2f9fc8](https://linux-hardware.org/?probe=fb9e2f9fc8) | Jun 09, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [92fd36b27a](https://linux-hardware.org/?probe=92fd36b27a) | Jun 09, 2023 |
| Panasonic     | CF-53ASCZGFG                | Notebook    | [39e04925ee](https://linux-hardware.org/?probe=39e04925ee) | Jun 08, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [5d8df77ade](https://linux-hardware.org/?probe=5d8df77ade) | Jun 08, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [c98ac6e82c](https://linux-hardware.org/?probe=c98ac6e82c) | Jun 08, 2023 |
| MSI           | Z87-G43                     | Desktop     | [554f8ea405](https://linux-hardware.org/?probe=554f8ea405) | Jun 08, 2023 |
| ASRock        | H81M-VG4                    | Desktop     | [04d84e44a5](https://linux-hardware.org/?probe=04d84e44a5) | Jun 08, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [7879db73f8](https://linux-hardware.org/?probe=7879db73f8) | Jun 08, 2023 |
| Unknown       | Unknown                     | Soc         | [b23e0f6e09](https://linux-hardware.org/?probe=b23e0f6e09) | Jun 08, 2023 |
| Fujitsu       | CELSIUS H730                | Notebook    | [a1e397f4a7](https://linux-hardware.org/?probe=a1e397f4a7) | Jun 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [c142d83ce5](https://linux-hardware.org/?probe=c142d83ce5) | Jun 07, 2023 |
| Gigabyte      | B250-FinTech-CF             | Desktop     | [022138ad16](https://linux-hardware.org/?probe=022138ad16) | Jun 06, 2023 |
| Toshiba       | Satellite L40               | Notebook    | [16c5f74991](https://linux-hardware.org/?probe=16c5f74991) | Jun 06, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [e56988bf8e](https://linux-hardware.org/?probe=e56988bf8e) | Jun 06, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [50304f8088](https://linux-hardware.org/?probe=50304f8088) | Jun 06, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [fc49284b9f](https://linux-hardware.org/?probe=fc49284b9f) | Jun 06, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [1df787c227](https://linux-hardware.org/?probe=1df787c227) | Jun 05, 2023 |
| Gigabyte      | B250-FinTech-CF             | Desktop     | [e22c496628](https://linux-hardware.org/?probe=e22c496628) | Jun 05, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [83982c1aa9](https://linux-hardware.org/?probe=83982c1aa9) | Jun 05, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [38882f47af](https://linux-hardware.org/?probe=38882f47af) | Jun 05, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [72eb9f0d86](https://linux-hardware.org/?probe=72eb9f0d86) | Jun 05, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [580ae6529e](https://linux-hardware.org/?probe=580ae6529e) | Jun 05, 2023 |
| Dell          | Latitude 3190               | Notebook    | [fa8eba55f0](https://linux-hardware.org/?probe=fa8eba55f0) | Jun 05, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [969354604a](https://linux-hardware.org/?probe=969354604a) | Jun 04, 2023 |
| HP            | 21B4 A01                    | Desktop     | [5d394c52ed](https://linux-hardware.org/?probe=5d394c52ed) | Jun 04, 2023 |
| ASUSTek       | P5G41T-M                    | Desktop     | [8706eff580](https://linux-hardware.org/?probe=8706eff580) | Jun 04, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [7af9263ba9](https://linux-hardware.org/?probe=7af9263ba9) | Jun 04, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [ae24cbf98d](https://linux-hardware.org/?probe=ae24cbf98d) | Jun 04, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [514b3788ed](https://linux-hardware.org/?probe=514b3788ed) | Jun 04, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [e3770a95f6](https://linux-hardware.org/?probe=e3770a95f6) | Jun 04, 2023 |
| Dell          | Latitude D620               | Notebook    | [0e1b7f4320](https://linux-hardware.org/?probe=0e1b7f4320) | Jun 03, 2023 |
| Acer          | Aspire A114-31              | Notebook    | [7a760e7ad6](https://linux-hardware.org/?probe=7a760e7ad6) | Jun 03, 2023 |
| Lenovo        | ThinkPad L490 20Q5002DMH    | Notebook    | [6d42b7647b](https://linux-hardware.org/?probe=6d42b7647b) | Jun 02, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [fa4bd41f4b](https://linux-hardware.org/?probe=fa4bd41f4b) | Jun 02, 2023 |
| ASUSTek       | P8H61                       | Desktop     | [7e9f999121](https://linux-hardware.org/?probe=7e9f999121) | Jun 02, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [1a4437e831](https://linux-hardware.org/?probe=1a4437e831) | Jun 02, 2023 |
| Lenovo        | B50-70 20384                | Notebook    | [5e3a2796a9](https://linux-hardware.org/?probe=5e3a2796a9) | Jun 01, 2023 |
| HP            | EliteBook 820 G2            | Notebook    | [c9409c532d](https://linux-hardware.org/?probe=c9409c532d) | Jun 01, 2023 |
| Toshiba       | Satellite L650              | Notebook    | [63eb6978fa](https://linux-hardware.org/?probe=63eb6978fa) | Jun 01, 2023 |
| HP            | 845A                        | Desktop     | [b68054952b](https://linux-hardware.org/?probe=b68054952b) | Jun 01, 2023 |
| Supermicro    | X8DTU                       | Server      | [2e1d03c7da](https://linux-hardware.org/?probe=2e1d03c7da) | Jun 01, 2023 |
| Lenovo        | B51-80 80LM                 | Notebook    | [69429cb044](https://linux-hardware.org/?probe=69429cb044) | Jun 01, 2023 |
| Unknown       | Unknown                     | Phone       | [bd6f4745f0](https://linux-hardware.org/?probe=bd6f4745f0) | Jun 01, 2023 |
| HP            | 82B5                        | All in one  | [77ecbfa91c](https://linux-hardware.org/?probe=77ecbfa91c) | Jun 01, 2023 |
| ASUSTek       | Z97-P                       | Desktop     | [b819db60d1](https://linux-hardware.org/?probe=b819db60d1) | Jun 01, 2023 |
| Intel         | DB75EN AAG39650-302         | Desktop     | [9872e0cb5c](https://linux-hardware.org/?probe=9872e0cb5c) | May 31, 2023 |
| Inventec      | 0PY33N A01                  | Mini pc     | [01452a68b3](https://linux-hardware.org/?probe=01452a68b3) | May 31, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [46ccbd2d62](https://linux-hardware.org/?probe=46ccbd2d62) | May 31, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [b90cb27f97](https://linux-hardware.org/?probe=b90cb27f97) | May 31, 2023 |
| Gigabyte      | B250-FinTech-CF             | Desktop     | [1903d991a3](https://linux-hardware.org/?probe=1903d991a3) | May 30, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [7fed965224](https://linux-hardware.org/?probe=7fed965224) | May 30, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [3b186c07a2](https://linux-hardware.org/?probe=3b186c07a2) | May 30, 2023 |
| Dell          | 02N3WF A01                  | Desktop     | [c02695ea7d](https://linux-hardware.org/?probe=c02695ea7d) | May 30, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [1df34e179b](https://linux-hardware.org/?probe=1df34e179b) | May 30, 2023 |
| Dell          | 040DDP A01                  | Desktop     | [bce6b61241](https://linux-hardware.org/?probe=bce6b61241) | May 29, 2023 |
| Dell          | Latitude 3190               | Notebook    | [fe4a8422c8](https://linux-hardware.org/?probe=fe4a8422c8) | May 29, 2023 |
| ASRock        | H110M-DVS R3.0              | Desktop     | [505b123692](https://linux-hardware.org/?probe=505b123692) | May 29, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [ca1cea162c](https://linux-hardware.org/?probe=ca1cea162c) | May 29, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [edfe02a7ae](https://linux-hardware.org/?probe=edfe02a7ae) | May 29, 2023 |
| Lenovo        | MIIX 300-10IBY 80NR         | Tablet      | [92b569d076](https://linux-hardware.org/?probe=92b569d076) | May 28, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [4d002c31be](https://linux-hardware.org/?probe=4d002c31be) | May 28, 2023 |
| Dell          | Latitude 7480               | Notebook    | [9eb2396796](https://linux-hardware.org/?probe=9eb2396796) | May 28, 2023 |
| Dell          | Vostro 1015                 | Notebook    | [c51af54d34](https://linux-hardware.org/?probe=c51af54d34) | May 28, 2023 |
| Gateway       | DT55                        | Desktop     | [22d84550c6](https://linux-hardware.org/?probe=22d84550c6) | May 28, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [c2408a1885](https://linux-hardware.org/?probe=c2408a1885) | May 28, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [d06e7ba405](https://linux-hardware.org/?probe=d06e7ba405) | May 28, 2023 |
| HP            | Pavilion x2 Detachable      | Tablet      | [9099d721d2](https://linux-hardware.org/?probe=9099d721d2) | May 27, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [8311d009bd](https://linux-hardware.org/?probe=8311d009bd) | May 27, 2023 |
| Lenovo        | ThinkPad T470 20HES0FA03    | Notebook    | [c8c8087ee8](https://linux-hardware.org/?probe=c8c8087ee8) | May 27, 2023 |
| ASRock        | H81M-VG4                    | Desktop     | [4e7b273239](https://linux-hardware.org/?probe=4e7b273239) | May 27, 2023 |
| ASUSTek       | X555LN                      | Notebook    | [8f16767017](https://linux-hardware.org/?probe=8f16767017) | May 26, 2023 |
| ASUSTek       | A8N-E                       | Desktop     | [2baf5b889b](https://linux-hardware.org/?probe=2baf5b889b) | May 26, 2023 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [a7fbdc21bc](https://linux-hardware.org/?probe=a7fbdc21bc) | May 26, 2023 |
| Dell          | Latitude E5440              | Notebook    | [4a5501c365](https://linux-hardware.org/?probe=4a5501c365) | May 26, 2023 |
| Notebook      | NV4xPZ                      | Notebook    | [750cb90d83](https://linux-hardware.org/?probe=750cb90d83) | May 26, 2023 |
| Acer          | WG43M                       | Desktop     | [9afcfc4a44](https://linux-hardware.org/?probe=9afcfc4a44) | May 26, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [53db1863ab](https://linux-hardware.org/?probe=53db1863ab) | May 25, 2023 |
| ASUSTek       | GL552VW                     | Notebook    | [0466edde83](https://linux-hardware.org/?probe=0466edde83) | May 25, 2023 |
| ASUSTek       | X551MA                      | Notebook    | [d72352c0dc](https://linux-hardware.org/?probe=d72352c0dc) | May 25, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [654aa3909f](https://linux-hardware.org/?probe=654aa3909f) | May 24, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [06333c9c97](https://linux-hardware.org/?probe=06333c9c97) | May 24, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [dd15a8197e](https://linux-hardware.org/?probe=dd15a8197e) | May 24, 2023 |
| Acer          | Aspire E5-571G              | Notebook    | [6531b22151](https://linux-hardware.org/?probe=6531b22151) | May 24, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [ba72bf9d52](https://linux-hardware.org/?probe=ba72bf9d52) | May 24, 2023 |
| Google        | Snappy                      | Notebook    | [8e9ad9e9d3](https://linux-hardware.org/?probe=8e9ad9e9d3) | May 24, 2023 |
| Lenovo        | Unknown                     | Notebook    | [e7148e7a18](https://linux-hardware.org/?probe=e7148e7a18) | May 23, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B3402FEA... | Convertible | [b5e28ef2ab](https://linux-hardware.org/?probe=b5e28ef2ab) | May 23, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [7b6c90320b](https://linux-hardware.org/?probe=7b6c90320b) | May 23, 2023 |
| Gigabyte      | B250-FinTech-CF             | Desktop     | [d8d33293ef](https://linux-hardware.org/?probe=d8d33293ef) | May 23, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [e4f2e7ecb6](https://linux-hardware.org/?probe=e4f2e7ecb6) | May 23, 2023 |
| HP            | 530                         | Notebook    | [70600de142](https://linux-hardware.org/?probe=70600de142) | May 23, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [b7fbda70d3](https://linux-hardware.org/?probe=b7fbda70d3) | May 23, 2023 |
| ASUSTek       | PRIME B760M-A D4            | Desktop     | [6ba02717d9](https://linux-hardware.org/?probe=6ba02717d9) | May 22, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [74a0ea4304](https://linux-hardware.org/?probe=74a0ea4304) | May 22, 2023 |
| MSI           | B360M PRO-VDH               | Desktop     | [93a41eca5e](https://linux-hardware.org/?probe=93a41eca5e) | May 22, 2023 |
| Dell          | Latitude 3190               | Notebook    | [adf9fc9bdb](https://linux-hardware.org/?probe=adf9fc9bdb) | May 22, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [46de86898c](https://linux-hardware.org/?probe=46de86898c) | May 22, 2023 |
| Medion        | BTDD-TI                     | All in one  | [ef28026334](https://linux-hardware.org/?probe=ef28026334) | May 22, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [e7af79968d](https://linux-hardware.org/?probe=e7af79968d) | May 22, 2023 |
| ASUSTek       | K84L                        | Notebook    | [5f14f3b293](https://linux-hardware.org/?probe=5f14f3b293) | May 21, 2023 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [b160fbf41e](https://linux-hardware.org/?probe=b160fbf41e) | May 21, 2023 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [cc90a5ca05](https://linux-hardware.org/?probe=cc90a5ca05) | May 21, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [03b17bc271](https://linux-hardware.org/?probe=03b17bc271) | May 21, 2023 |
| HP            | Unknown                     | Notebook    | [8894bf0f31](https://linux-hardware.org/?probe=8894bf0f31) | May 21, 2023 |
| Gigabyte      | GA-78LMT-S2PT               | Desktop     | [04ea462ce6](https://linux-hardware.org/?probe=04ea462ce6) | May 21, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [2e68f6cae7](https://linux-hardware.org/?probe=2e68f6cae7) | May 21, 2023 |
| Lenovo        | MIIX 300-10IBY 80NR         | Tablet      | [f7d7036598](https://linux-hardware.org/?probe=f7d7036598) | May 21, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [72adb50172](https://linux-hardware.org/?probe=72adb50172) | May 20, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [50e85498e7](https://linux-hardware.org/?probe=50e85498e7) | May 20, 2023 |
| Valve         | Jupiter                     | Notebook    | [cf5c419d13](https://linux-hardware.org/?probe=cf5c419d13) | May 20, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [87e60904b9](https://linux-hardware.org/?probe=87e60904b9) | May 20, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [fc125408b5](https://linux-hardware.org/?probe=fc125408b5) | May 20, 2023 |
| Dell          | 0F3KHR A01                  | Desktop     | [c48ab194c6](https://linux-hardware.org/?probe=c48ab194c6) | May 20, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [5acf485cbf](https://linux-hardware.org/?probe=5acf485cbf) | May 20, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [5a0f8e19ee](https://linux-hardware.org/?probe=5a0f8e19ee) | May 19, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [8c6b9dc52f](https://linux-hardware.org/?probe=8c6b9dc52f) | May 19, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [db9774a799](https://linux-hardware.org/?probe=db9774a799) | May 19, 2023 |
| Gigabyte      | F2A88X-D3H                  | Desktop     | [76bae0c7fb](https://linux-hardware.org/?probe=76bae0c7fb) | May 19, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | Notebook    | [26e8deafbf](https://linux-hardware.org/?probe=26e8deafbf) | May 19, 2023 |
| Intel         | NUC12WSBi7 M46422-304       | Mini pc     | [b63f2ef351](https://linux-hardware.org/?probe=b63f2ef351) | May 18, 2023 |
| Medion        | BTDD-TI                     | All in one  | [cc45e1f2f4](https://linux-hardware.org/?probe=cc45e1f2f4) | May 18, 2023 |
| MSI           | GL75 9SE                    | Notebook    | [7fd4d531c9](https://linux-hardware.org/?probe=7fd4d531c9) | May 18, 2023 |
| ASUSTek       | PRIME Z790-P                | Desktop     | [99d6173179](https://linux-hardware.org/?probe=99d6173179) | May 18, 2023 |
| Dell          | 0GDG8Y A00                  | Desktop     | [bc0a4ba851](https://linux-hardware.org/?probe=bc0a4ba851) | May 18, 2023 |
| Lenovo        | 1030 SDK0J40697 WIN 3305... | Desktop     | [af1e17cc95](https://linux-hardware.org/?probe=af1e17cc95) | May 17, 2023 |
| ASUSTek       | P5G41T-M                    | Desktop     | [89d938fcef](https://linux-hardware.org/?probe=89d938fcef) | May 17, 2023 |
| HP            | EliteBook 820 G2            | Notebook    | [200610da74](https://linux-hardware.org/?probe=200610da74) | May 17, 2023 |
| Google        | Snappy                      | Notebook    | [d13d8adaf4](https://linux-hardware.org/?probe=d13d8adaf4) | May 17, 2023 |
| Intel         | DB75EN AAG39650-302         | Desktop     | [2f6a330442](https://linux-hardware.org/?probe=2f6a330442) | May 17, 2023 |
| Google        | Snappy                      | Notebook    | [0c095bb37a](https://linux-hardware.org/?probe=0c095bb37a) | May 17, 2023 |
| Pegatron      | VIOLET                      | Desktop     | [197ec890d6](https://linux-hardware.org/?probe=197ec890d6) | May 16, 2023 |
| Pegatron      | VIOLET                      | Desktop     | [fa6dc417d4](https://linux-hardware.org/?probe=fa6dc417d4) | May 16, 2023 |
| Foxconn       | P35A01                      | Desktop     | [d3f10a59ba](https://linux-hardware.org/?probe=d3f10a59ba) | May 16, 2023 |
| Intel         | DB75EN AAG39650-302         | Desktop     | [db27da6896](https://linux-hardware.org/?probe=db27da6896) | May 15, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [d4ad39c5d7](https://linux-hardware.org/?probe=d4ad39c5d7) | May 15, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [4a352d010e](https://linux-hardware.org/?probe=4a352d010e) | May 15, 2023 |
| Dell          | Latitude 3190               | Notebook    | [1d867407a6](https://linux-hardware.org/?probe=1d867407a6) | May 15, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [0aa84055bf](https://linux-hardware.org/?probe=0aa84055bf) | May 15, 2023 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [3466945196](https://linux-hardware.org/?probe=3466945196) | May 15, 2023 |
| HP            | 339A                        | Desktop     | [35fdefb4eb](https://linux-hardware.org/?probe=35fdefb4eb) | May 15, 2023 |
| Lenovo        | B590 20206                  | Notebook    | [70b604bc30](https://linux-hardware.org/?probe=70b604bc30) | May 14, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [5f508efff4](https://linux-hardware.org/?probe=5f508efff4) | May 14, 2023 |
| Lenovo        | B50-70 20384                | Notebook    | [1d3db7b456](https://linux-hardware.org/?probe=1d3db7b456) | May 14, 2023 |
| Fujitsu       | CELSIUS H760                | Notebook    | [5e6faf68dd](https://linux-hardware.org/?probe=5e6faf68dd) | May 14, 2023 |
| Lenovo        | B50-70 20384                | Notebook    | [9459f4eae8](https://linux-hardware.org/?probe=9459f4eae8) | May 14, 2023 |
| Lenovo        | ThinkCentre M58 7627AD5     | Desktop     | [e0b4de3daf](https://linux-hardware.org/?probe=e0b4de3daf) | May 14, 2023 |
| Fujitsu       | LIFEBOOK S752               | Notebook    | [97e9f91d90](https://linux-hardware.org/?probe=97e9f91d90) | May 14, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [660bd404a0](https://linux-hardware.org/?probe=660bd404a0) | May 14, 2023 |
| ASUSTek       | K53BR                       | Notebook    | [96a60a2970](https://linux-hardware.org/?probe=96a60a2970) | May 14, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [091a42a1c0](https://linux-hardware.org/?probe=091a42a1c0) | May 14, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [aa5dc9770e](https://linux-hardware.org/?probe=aa5dc9770e) | May 13, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [51c66f0f57](https://linux-hardware.org/?probe=51c66f0f57) | May 13, 2023 |
| Inventec      | D CLASS A02                 | Desktop     | [309a617781](https://linux-hardware.org/?probe=309a617781) | May 13, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [31d034ce6e](https://linux-hardware.org/?probe=31d034ce6e) | May 13, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [55abeba9a3](https://linux-hardware.org/?probe=55abeba9a3) | May 13, 2023 |
| Dell          | 0GWHMW A00                  | Desktop     | [d2dbc10885](https://linux-hardware.org/?probe=d2dbc10885) | May 13, 2023 |
| Gigabyte      | B360M DS3H                  | Desktop     | [82dbe1cdf7](https://linux-hardware.org/?probe=82dbe1cdf7) | May 13, 2023 |
| Fujitsu       | CELSIUS H760                | Notebook    | [7bb1e2b54e](https://linux-hardware.org/?probe=7bb1e2b54e) | May 13, 2023 |
| Toshiba       | Satellite C55-A-1KZ         | Notebook    | [37c165fa30](https://linux-hardware.org/?probe=37c165fa30) | May 13, 2023 |
| Dell          | Precision 3571              | Notebook    | [9a20dccb42](https://linux-hardware.org/?probe=9a20dccb42) | May 13, 2023 |
| GPU Compan... | GWTN156-11                  | Notebook    | [afb2844cb4](https://linux-hardware.org/?probe=afb2844cb4) | May 13, 2023 |
| Dell          | 0NDYHG A01                  | Desktop     | [8fdc05a6ad](https://linux-hardware.org/?probe=8fdc05a6ad) | May 13, 2023 |
| Samsung       | RF510/RF410/RF710           | Notebook    | [4820c25349](https://linux-hardware.org/?probe=4820c25349) | May 12, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [6950584e4c](https://linux-hardware.org/?probe=6950584e4c) | May 12, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [29b8cfc7e6](https://linux-hardware.org/?probe=29b8cfc7e6) | May 12, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [9f88d81e33](https://linux-hardware.org/?probe=9f88d81e33) | May 12, 2023 |
| HP            | ProBook 4535s               | Notebook    | [0d2f9561ce](https://linux-hardware.org/?probe=0d2f9561ce) | May 12, 2023 |
| HP            | 3047h                       | Desktop     | [bb0087d307](https://linux-hardware.org/?probe=bb0087d307) | May 12, 2023 |
| Dell          | Latitude 7390               | Notebook    | [cbd8c5fdbe](https://linux-hardware.org/?probe=cbd8c5fdbe) | May 12, 2023 |
| Dell          | Latitude 7390               | Notebook    | [5677bfdac5](https://linux-hardware.org/?probe=5677bfdac5) | May 12, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS       | Desktop     | [b9a3dfd029](https://linux-hardware.org/?probe=b9a3dfd029) | May 12, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | Desktop     | [39f854e5de](https://linux-hardware.org/?probe=39f854e5de) | May 11, 2023 |
| Toshiba       | Satellite L40               | Notebook    | [9945f20a3a](https://linux-hardware.org/?probe=9945f20a3a) | May 11, 2023 |
| Intel         | DB75EN AAG39650-302         | Desktop     | [e0ebf9fa8a](https://linux-hardware.org/?probe=e0ebf9fa8a) | May 11, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [4ca3ad7158](https://linux-hardware.org/?probe=4ca3ad7158) | May 11, 2023 |
| ASUSTek       | B85-PLUS                    | Desktop     | [9346ce422f](https://linux-hardware.org/?probe=9346ce422f) | May 11, 2023 |
| Valve         | Jupiter                     | Notebook    | [5bfb32e683](https://linux-hardware.org/?probe=5bfb32e683) | May 11, 2023 |
| HP            | EliteBook 745 G3            | Notebook    | [256ad0c4d8](https://linux-hardware.org/?probe=256ad0c4d8) | May 11, 2023 |
| Intel         | NUC12WSBi7 M46422-303       | Mini pc     | [7a97d5d5ab](https://linux-hardware.org/?probe=7a97d5d5ab) | May 10, 2023 |
| Lenovo        | ThinkPad L470 20J5S01S00    | Notebook    | [8886b2b825](https://linux-hardware.org/?probe=8886b2b825) | May 10, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [d764690667](https://linux-hardware.org/?probe=d764690667) | May 10, 2023 |
| MSI           | B85-G43                     | Desktop     | [878fbbb243](https://linux-hardware.org/?probe=878fbbb243) | May 09, 2023 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [58000b3a57](https://linux-hardware.org/?probe=58000b3a57) | May 09, 2023 |
| Fujitsu Si... | AMILO Pro Series V3525      | Notebook    | [6272f76b0b](https://linux-hardware.org/?probe=6272f76b0b) | May 09, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [a3e5adab46](https://linux-hardware.org/?probe=a3e5adab46) | May 08, 2023 |
| Fujitsu Si... | AMILO Pro Series V3525      | Notebook    | [e3cc11d5e4](https://linux-hardware.org/?probe=e3cc11d5e4) | May 08, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [afe5236688](https://linux-hardware.org/?probe=afe5236688) | May 08, 2023 |
| Dell          | Latitude 3190               | Notebook    | [fb4df1325b](https://linux-hardware.org/?probe=fb4df1325b) | May 08, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [a8e82695ee](https://linux-hardware.org/?probe=a8e82695ee) | May 08, 2023 |
| Valve         | Jupiter                     | Notebook    | [e6397e7f9f](https://linux-hardware.org/?probe=e6397e7f9f) | May 08, 2023 |
| HP            | 15                          | Notebook    | [162a4b16ae](https://linux-hardware.org/?probe=162a4b16ae) | May 08, 2023 |
| Dell          | Latitude 5520               | Notebook    | [4d8ef45cbc](https://linux-hardware.org/?probe=4d8ef45cbc) | May 07, 2023 |
| Acer          | TravelMate 6592             | Notebook    | [d655aad3c5](https://linux-hardware.org/?probe=d655aad3c5) | May 07, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [c0ade7c98e](https://linux-hardware.org/?probe=c0ade7c98e) | May 07, 2023 |
| Dell          | Latitude 5290               | Notebook    | [255da608b8](https://linux-hardware.org/?probe=255da608b8) | May 07, 2023 |
| ASUSTek       | Zenbook UM6702RC_RM6702R... | Notebook    | [3cf83f50f0](https://linux-hardware.org/?probe=3cf83f50f0) | May 07, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [a1e7385ffa](https://linux-hardware.org/?probe=a1e7385ffa) | May 07, 2023 |
| Gigabyte      | G41M-Combo                  | Desktop     | [077ced1a40](https://linux-hardware.org/?probe=077ced1a40) | May 06, 2023 |
| Fujitsu Si... | D2804-A1 S26361-D2804-A1    | Desktop     | [4278efc4ca](https://linux-hardware.org/?probe=4278efc4ca) | May 06, 2023 |
| Toshiba       | Satellite L300D             | Notebook    | [0e2dfb1c74](https://linux-hardware.org/?probe=0e2dfb1c74) | May 06, 2023 |
| Gigabyte      | GA-MA785GMT-UD2H            | Desktop     | [50fba20da2](https://linux-hardware.org/?probe=50fba20da2) | May 05, 2023 |
| ASUSTek       | K75DE                       | Notebook    | [d99045be1c](https://linux-hardware.org/?probe=d99045be1c) | May 05, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [8774a893d6](https://linux-hardware.org/?probe=8774a893d6) | May 05, 2023 |
| Gigabyte      | Z590 UD AC                  | Desktop     | [b8f920797f](https://linux-hardware.org/?probe=b8f920797f) | May 05, 2023 |
| Dell          | Inspiron 5770               | Notebook    | [c545869ec5](https://linux-hardware.org/?probe=c545869ec5) | May 05, 2023 |
| Gigabyte      | GA-MA790XT-UD4P             | Desktop     | [c9a5bee99d](https://linux-hardware.org/?probe=c9a5bee99d) | May 05, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [6aa9a8317d](https://linux-hardware.org/?probe=6aa9a8317d) | May 04, 2023 |
| HP            | EliteBook x360 1030 G3      | Convertible | [08a19ae7b9](https://linux-hardware.org/?probe=08a19ae7b9) | May 04, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [51ae873492](https://linux-hardware.org/?probe=51ae873492) | May 04, 2023 |
| HP            | EliteBook 8540p             | Notebook    | [11b0a5baa1](https://linux-hardware.org/?probe=11b0a5baa1) | May 04, 2023 |
| Google        | Meep                        | Notebook    | [1e5e0e6673](https://linux-hardware.org/?probe=1e5e0e6673) | May 04, 2023 |
| Dell          | Latitude 5490               | Notebook    | [20c5ad2ee2](https://linux-hardware.org/?probe=20c5ad2ee2) | May 03, 2023 |
| Dell          | Latitude E6410              | Notebook    | [8830853258](https://linux-hardware.org/?probe=8830853258) | May 03, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [91f2551511](https://linux-hardware.org/?probe=91f2551511) | May 03, 2023 |
| Packard Be... | EasyNote TE69BM             | Notebook    | [fc905a42fb](https://linux-hardware.org/?probe=fc905a42fb) | May 03, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [560b69d616](https://linux-hardware.org/?probe=560b69d616) | May 03, 2023 |
| Dell          | 09WH54 A00                  | Desktop     | [0afa4006cd](https://linux-hardware.org/?probe=0afa4006cd) | May 03, 2023 |
| Packard Be... | EasyNote LJ65               | Notebook    | [795672236a](https://linux-hardware.org/?probe=795672236a) | May 02, 2023 |
| Packard Be... | EasyNote LJ65               | Notebook    | [77860cab79](https://linux-hardware.org/?probe=77860cab79) | May 02, 2023 |
| HP            | 1589                        | Desktop     | [c817b08584](https://linux-hardware.org/?probe=c817b08584) | May 02, 2023 |
| HP            | 1589                        | Desktop     | [890241aeb6](https://linux-hardware.org/?probe=890241aeb6) | May 02, 2023 |
| Lenovo        | SHARKBAY NO DPK             | Desktop     | [01bd34ece8](https://linux-hardware.org/?probe=01bd34ece8) | May 01, 2023 |
| Gigabyte      | H110M-DS2-CF                | Desktop     | [211eb49a00](https://linux-hardware.org/?probe=211eb49a00) | May 01, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [15c40bae27](https://linux-hardware.org/?probe=15c40bae27) | May 01, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [a644bc676e](https://linux-hardware.org/?probe=a644bc676e) | May 01, 2023 |
| HP            | Compaq 6910p                | Notebook    | [a697e756f5](https://linux-hardware.org/?probe=a697e756f5) | May 01, 2023 |
| Dell          | Latitude 3190               | Notebook    | [59c654b2ec](https://linux-hardware.org/?probe=59c654b2ec) | May 01, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [c03693e806](https://linux-hardware.org/?probe=c03693e806) | May 01, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [2fcc250a35](https://linux-hardware.org/?probe=2fcc250a35) | May 01, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [93fef964a7](https://linux-hardware.org/?probe=93fef964a7) | Apr 30, 2023 |
| MSI           | B450M PRO-M2                | Desktop     | [b650f0a26e](https://linux-hardware.org/?probe=b650f0a26e) | Apr 30, 2023 |
| Dell          | Latitude XT2                | Notebook    | [3cfd979c60](https://linux-hardware.org/?probe=3cfd979c60) | Apr 30, 2023 |
| Acer          | AO725                       | Notebook    | [03e5f661fb](https://linux-hardware.org/?probe=03e5f661fb) | Apr 30, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [408aa18a63](https://linux-hardware.org/?probe=408aa18a63) | Apr 30, 2023 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [44c60dcec2](https://linux-hardware.org/?probe=44c60dcec2) | Apr 30, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [ff639a78ec](https://linux-hardware.org/?probe=ff639a78ec) | Apr 30, 2023 |
| Dell          | Inspiron MXC061             | Notebook    | [2d1ab773dd](https://linux-hardware.org/?probe=2d1ab773dd) | Apr 30, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [54f8ed91cf](https://linux-hardware.org/?probe=54f8ed91cf) | Apr 30, 2023 |
| ASRock        | Z370 Gaming K6              | Desktop     | [a5ff738639](https://linux-hardware.org/?probe=a5ff738639) | Apr 29, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [7c378d88a2](https://linux-hardware.org/?probe=7c378d88a2) | Apr 29, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [ee996917df](https://linux-hardware.org/?probe=ee996917df) | Apr 29, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [f502c40867](https://linux-hardware.org/?probe=f502c40867) | Apr 29, 2023 |
| Acer          | Aspire V5-552G              | Notebook    | [07c58a5169](https://linux-hardware.org/?probe=07c58a5169) | Apr 29, 2023 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [a8adc86550](https://linux-hardware.org/?probe=a8adc86550) | Apr 28, 2023 |
| Acer          | Aspire VX5-591G             | Notebook    | [2461a8058f](https://linux-hardware.org/?probe=2461a8058f) | Apr 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | Notebook    | [f1290d4846](https://linux-hardware.org/?probe=f1290d4846) | Apr 28, 2023 |
| ASRock        | Z170 Extreme4               | Desktop     | [b2c012c1e2](https://linux-hardware.org/?probe=b2c012c1e2) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [2474e8e580](https://linux-hardware.org/?probe=2474e8e580) | Apr 27, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [adb8f367ea](https://linux-hardware.org/?probe=adb8f367ea) | Apr 27, 2023 |
| HP            | EliteBook 2560p             | Notebook    | [23b5cbfb33](https://linux-hardware.org/?probe=23b5cbfb33) | Apr 27, 2023 |
| Acer          | Aspire 7250                 | Notebook    | [8e8e082e3d](https://linux-hardware.org/?probe=8e8e082e3d) | Apr 26, 2023 |
| Acer          | Aspire 5737Z                | Notebook    | [121eda50b8](https://linux-hardware.org/?probe=121eda50b8) | Apr 26, 2023 |
| ASUSTek       | P5K/EPU                     | Desktop     | [33ef71c7e7](https://linux-hardware.org/?probe=33ef71c7e7) | Apr 26, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [f1f2ad2731](https://linux-hardware.org/?probe=f1f2ad2731) | Apr 26, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [a3065a1b59](https://linux-hardware.org/?probe=a3065a1b59) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d8088982c3](https://linux-hardware.org/?probe=d8088982c3) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [4cffa55fb1](https://linux-hardware.org/?probe=4cffa55fb1) | Apr 26, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [e6380a2186](https://linux-hardware.org/?probe=e6380a2186) | Apr 26, 2023 |
| HP            | Laptop 15                   | Notebook    | [34a2ebf6a1](https://linux-hardware.org/?probe=34a2ebf6a1) | Apr 26, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [872138980a](https://linux-hardware.org/?probe=872138980a) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2122bd37a5](https://linux-hardware.org/?probe=2122bd37a5) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [af7b14d259](https://linux-hardware.org/?probe=af7b14d259) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [7fbd802154](https://linux-hardware.org/?probe=7fbd802154) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [ffe6065419](https://linux-hardware.org/?probe=ffe6065419) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [94ddc76aae](https://linux-hardware.org/?probe=94ddc76aae) | Apr 26, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [856de630ec](https://linux-hardware.org/?probe=856de630ec) | Apr 25, 2023 |
| Dell          | Cherry Trail CR A00         | Mini pc     | [f1fb89d0f7](https://linux-hardware.org/?probe=f1fb89d0f7) | Apr 25, 2023 |
| Dell          | 03NVJ6 A02                  | Desktop     | [74a0632f6e](https://linux-hardware.org/?probe=74a0632f6e) | Apr 25, 2023 |
| Lenovo        | ThinkPad X200 7459KM3       | Notebook    | [cbea785e27](https://linux-hardware.org/?probe=cbea785e27) | Apr 25, 2023 |
| Dell          | Latitude E5470              | Notebook    | [3eb401d939](https://linux-hardware.org/?probe=3eb401d939) | Apr 25, 2023 |
| Dell          | Latitude E5470              | Notebook    | [37fabb89aa](https://linux-hardware.org/?probe=37fabb89aa) | Apr 25, 2023 |
| Lenovo        | G700                        | Notebook    | [75ee4cf99d](https://linux-hardware.org/?probe=75ee4cf99d) | Apr 24, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [9649423c20](https://linux-hardware.org/?probe=9649423c20) | Apr 24, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [af486ae4ae](https://linux-hardware.org/?probe=af486ae4ae) | Apr 24, 2023 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [de3ad583ab](https://linux-hardware.org/?probe=de3ad583ab) | Apr 24, 2023 |
| Medion        | X681X                       | Notebook    | [d72837ad07](https://linux-hardware.org/?probe=d72837ad07) | Apr 24, 2023 |
| HP            | EliteBook 650 15.6 inch ... | Notebook    | [78686e5784](https://linux-hardware.org/?probe=78686e5784) | Apr 24, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [76b3daef92](https://linux-hardware.org/?probe=76b3daef92) | Apr 24, 2023 |
| Dell          | Vostro 5402                 | Notebook    | [b6cb9c9140](https://linux-hardware.org/?probe=b6cb9c9140) | Apr 24, 2023 |
| Dell          | Latitude 3190               | Notebook    | [2c21a51932](https://linux-hardware.org/?probe=2c21a51932) | Apr 24, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [7bbac9f9bf](https://linux-hardware.org/?probe=7bbac9f9bf) | Apr 24, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [35c362eb4f](https://linux-hardware.org/?probe=35c362eb4f) | Apr 24, 2023 |
| Samsung       | R510/P510                   | Notebook    | [4b58936ad7](https://linux-hardware.org/?probe=4b58936ad7) | Apr 23, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [f98c5f7d2e](https://linux-hardware.org/?probe=f98c5f7d2e) | Apr 23, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [e959cc70fa](https://linux-hardware.org/?probe=e959cc70fa) | Apr 23, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | Notebook    | [18306b3af6](https://linux-hardware.org/?probe=18306b3af6) | Apr 23, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [652e029529](https://linux-hardware.org/?probe=652e029529) | Apr 23, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | Notebook    | [bee909cfcd](https://linux-hardware.org/?probe=bee909cfcd) | Apr 23, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | Notebook    | [c101faa12e](https://linux-hardware.org/?probe=c101faa12e) | Apr 23, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [1c439a695b](https://linux-hardware.org/?probe=1c439a695b) | Apr 23, 2023 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [3d51a6183c](https://linux-hardware.org/?probe=3d51a6183c) | Apr 23, 2023 |
| Dell          | Precision 7550              | Notebook    | [31830a82c6](https://linux-hardware.org/?probe=31830a82c6) | Apr 22, 2023 |
| Dell          | Latitude D620               | Notebook    | [7b0c5ec6f2](https://linux-hardware.org/?probe=7b0c5ec6f2) | Apr 22, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [510237facd](https://linux-hardware.org/?probe=510237facd) | Apr 22, 2023 |
| Gigabyte      | AORUS 15P XD                | Notebook    | [22925aa0c9](https://linux-hardware.org/?probe=22925aa0c9) | Apr 22, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [c1139db413](https://linux-hardware.org/?probe=c1139db413) | Apr 22, 2023 |
| MSI           | P55-GD65                    | Desktop     | [90cc53b6dd](https://linux-hardware.org/?probe=90cc53b6dd) | Apr 22, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [3056a65306](https://linux-hardware.org/?probe=3056a65306) | Apr 22, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [51ef82c2fd](https://linux-hardware.org/?probe=51ef82c2fd) | Apr 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [be207ea29f](https://linux-hardware.org/?probe=be207ea29f) | Apr 21, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [87d3a8b29f](https://linux-hardware.org/?probe=87d3a8b29f) | Apr 20, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [b7f138b04c](https://linux-hardware.org/?probe=b7f138b04c) | Apr 20, 2023 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [cde1ecf1c6](https://linux-hardware.org/?probe=cde1ecf1c6) | Apr 20, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [904089ce14](https://linux-hardware.org/?probe=904089ce14) | Apr 20, 2023 |
| Dell          | Precision M6600             | Notebook    | [e71bf9e7bb](https://linux-hardware.org/?probe=e71bf9e7bb) | Apr 20, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [3b07dc847f](https://linux-hardware.org/?probe=3b07dc847f) | Apr 20, 2023 |
| MSI           | Creator Z17 A12UHST         | Notebook    | [1396746fba](https://linux-hardware.org/?probe=1396746fba) | Apr 20, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [b2f977f4a1](https://linux-hardware.org/?probe=b2f977f4a1) | Apr 19, 2023 |
| Acer          | Aspire A715-71G             | Notebook    | [83b48fff59](https://linux-hardware.org/?probe=83b48fff59) | Apr 19, 2023 |
| Dell          | Latitude 7410               | Notebook    | [36e2aea9ea](https://linux-hardware.org/?probe=36e2aea9ea) | Apr 19, 2023 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [09a37b3301](https://linux-hardware.org/?probe=09a37b3301) | Apr 19, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | Notebook    | [1548cc4309](https://linux-hardware.org/?probe=1548cc4309) | Apr 19, 2023 |
| Dell          | Precision M6800             | Notebook    | [b39d3f31df](https://linux-hardware.org/?probe=b39d3f31df) | Apr 18, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [af6c719754](https://linux-hardware.org/?probe=af6c719754) | Apr 18, 2023 |
| Gigabyte      | G5 GE                       | Notebook    | [f1baab4be4](https://linux-hardware.org/?probe=f1baab4be4) | Apr 17, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [a0b6c23c0b](https://linux-hardware.org/?probe=a0b6c23c0b) | Apr 17, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [35ec02005f](https://linux-hardware.org/?probe=35ec02005f) | Apr 17, 2023 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [0244194778](https://linux-hardware.org/?probe=0244194778) | Apr 17, 2023 |
| Acer          | Swift SFA16-41              | Notebook    | [1232f86e3e](https://linux-hardware.org/?probe=1232f86e3e) | Apr 17, 2023 |
| Dell          | Latitude D830               | Notebook    | [3da091adc2](https://linux-hardware.org/?probe=3da091adc2) | Apr 17, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [7ca92cfada](https://linux-hardware.org/?probe=7ca92cfada) | Apr 17, 2023 |
| Lenovo        | ThinkPad T480s 20L8SF1X0... | Notebook    | [d567c29052](https://linux-hardware.org/?probe=d567c29052) | Apr 17, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [c59c5c0cdf](https://linux-hardware.org/?probe=c59c5c0cdf) | Apr 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [391b43ba8c](https://linux-hardware.org/?probe=391b43ba8c) | Apr 16, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [c8513ddcf3](https://linux-hardware.org/?probe=c8513ddcf3) | Apr 16, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [b74080b280](https://linux-hardware.org/?probe=b74080b280) | Apr 16, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [4fad8fc758](https://linux-hardware.org/?probe=4fad8fc758) | Apr 16, 2023 |
| Dell          | Latitude E6330              | Notebook    | [1a75476b96](https://linux-hardware.org/?probe=1a75476b96) | Apr 16, 2023 |
| Acer          | AO722                       | Notebook    | [af4e100c16](https://linux-hardware.org/?probe=af4e100c16) | Apr 15, 2023 |
| Kiano         | Elegance 14.2               | Notebook    | [34062f30df](https://linux-hardware.org/?probe=34062f30df) | Apr 15, 2023 |
| Acer          | Aspire 5336                 | Notebook    | [7613566248](https://linux-hardware.org/?probe=7613566248) | Apr 15, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [9206720811](https://linux-hardware.org/?probe=9206720811) | Apr 14, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [3c77a2b081](https://linux-hardware.org/?probe=3c77a2b081) | Apr 14, 2023 |
| Valve         | Jupiter                     | Notebook    | [c1558fbc72](https://linux-hardware.org/?probe=c1558fbc72) | Apr 14, 2023 |
| MSI           | B85-G43                     | Desktop     | [0363360efa](https://linux-hardware.org/?probe=0363360efa) | Apr 14, 2023 |
| Lenovo        | Legion 5 15IAH7 82RC        | Notebook    | [9cb53e6d6f](https://linux-hardware.org/?probe=9cb53e6d6f) | Apr 13, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [9341670151](https://linux-hardware.org/?probe=9341670151) | Apr 13, 2023 |
| Lenovo        | ThinkPad X220 4291AY8       | Notebook    | [b2bc70473d](https://linux-hardware.org/?probe=b2bc70473d) | Apr 13, 2023 |
| Dell          | 0GXM1W A00                  | Desktop     | [f96d907026](https://linux-hardware.org/?probe=f96d907026) | Apr 13, 2023 |
| ASUSTek       | A68HM-K                     | Desktop     | [5586a15d29](https://linux-hardware.org/?probe=5586a15d29) | Apr 13, 2023 |
| Fujitsu Si... | AMILO PRO V3515             | Notebook    | [be2d8594c3](https://linux-hardware.org/?probe=be2d8594c3) | Apr 13, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [1d6ace19a5](https://linux-hardware.org/?probe=1d6ace19a5) | Apr 13, 2023 |
| ASRock        | Z170 Extreme4               | Desktop     | [d21971f30f](https://linux-hardware.org/?probe=d21971f30f) | Apr 13, 2023 |
| Dell          | Latitude E6230              | Notebook    | [a7cce7ebde](https://linux-hardware.org/?probe=a7cce7ebde) | Apr 12, 2023 |
| Acer          | WG43M                       | Desktop     | [e22afb229d](https://linux-hardware.org/?probe=e22afb229d) | Apr 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3460C... | Notebook    | [f1999ee14e](https://linux-hardware.org/?probe=f1999ee14e) | Apr 11, 2023 |
| HP            | 8158 A01                    | Mini pc     | [a7d7e5c675](https://linux-hardware.org/?probe=a7d7e5c675) | Apr 11, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [b85f3476ed](https://linux-hardware.org/?probe=b85f3476ed) | Apr 11, 2023 |
| Dell          | Latitude 7390               | Notebook    | [9361f06955](https://linux-hardware.org/?probe=9361f06955) | Apr 11, 2023 |
| Lenovo        | ThinkPad T480 20L5S12H00    | Notebook    | [c550410c5b](https://linux-hardware.org/?probe=c550410c5b) | Apr 11, 2023 |
| HP            | Pavilion dv7                | Notebook    | [000c77d7d5](https://linux-hardware.org/?probe=000c77d7d5) | Apr 10, 2023 |
| HP            | Pavilion dv7                | Notebook    | [08e5108cda](https://linux-hardware.org/?probe=08e5108cda) | Apr 10, 2023 |
| HP            | 3032h                       | Desktop     | [824604840a](https://linux-hardware.org/?probe=824604840a) | Apr 10, 2023 |
| ASRock        | X370 Gaming X               | Desktop     | [d829fac91c](https://linux-hardware.org/?probe=d829fac91c) | Apr 10, 2023 |
| ASRock        | X370 Gaming X               | Desktop     | [bd05976130](https://linux-hardware.org/?probe=bd05976130) | Apr 10, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [001091b5fd](https://linux-hardware.org/?probe=001091b5fd) | Apr 10, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [34f1d57aec](https://linux-hardware.org/?probe=34f1d57aec) | Apr 10, 2023 |
| ASRock        | X370 Gaming X               | Desktop     | [0beaf2366c](https://linux-hardware.org/?probe=0beaf2366c) | Apr 09, 2023 |
| Lenovo        | ThinkPad T450 20BUS0QT04    | Notebook    | [90d7e2bb21](https://linux-hardware.org/?probe=90d7e2bb21) | Apr 09, 2023 |
| Lenovo        | ThinkPad X220 4291LR6       | Notebook    | [ea86227d59](https://linux-hardware.org/?probe=ea86227d59) | Apr 09, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [6b6b2a8633](https://linux-hardware.org/?probe=6b6b2a8633) | Apr 09, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [00489240d2](https://linux-hardware.org/?probe=00489240d2) | Apr 09, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [6f8748297a](https://linux-hardware.org/?probe=6f8748297a) | Apr 09, 2023 |
| Lenovo        | IdeaPad S540-14IWL 81ND     | Notebook    | [869d7607e9](https://linux-hardware.org/?probe=869d7607e9) | Apr 08, 2023 |
| Acer          | Aspire 5336                 | Notebook    | [6e419f3401](https://linux-hardware.org/?probe=6e419f3401) | Apr 08, 2023 |
| Toshiba       | Satellite L750D             | Notebook    | [d510eabb78](https://linux-hardware.org/?probe=d510eabb78) | Apr 08, 2023 |
| Toshiba       | Satellite L750D             | Notebook    | [3c8c0e7455](https://linux-hardware.org/?probe=3c8c0e7455) | Apr 08, 2023 |
| MSI           | MS-B0A21                    | Desktop     | [93db7f66f1](https://linux-hardware.org/?probe=93db7f66f1) | Apr 08, 2023 |
| Samsung       | 300E4A/300E5A/300E7A        | Notebook    | [370d1404f2](https://linux-hardware.org/?probe=370d1404f2) | Apr 08, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [b8dd840f5d](https://linux-hardware.org/?probe=b8dd840f5d) | Apr 08, 2023 |
| Samsung       | 400B4C/400B5C/200B4C/200... | Notebook    | [8026ca606e](https://linux-hardware.org/?probe=8026ca606e) | Apr 07, 2023 |
| Dell          | Inspiron 11-3162            | Notebook    | [accdfd2253](https://linux-hardware.org/?probe=accdfd2253) | Apr 07, 2023 |
| Samsung       | 730U3E/740U3E               | Notebook    | [7d4b6838e2](https://linux-hardware.org/?probe=7d4b6838e2) | Apr 07, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [413528fa5a](https://linux-hardware.org/?probe=413528fa5a) | Apr 07, 2023 |
| MSI           | GP76 Leopard 10UE           | Notebook    | [c7b870bb22](https://linux-hardware.org/?probe=c7b870bb22) | Apr 07, 2023 |
| Toshiba       | Satellite C855-12N          | Notebook    | [69e30b2fd8](https://linux-hardware.org/?probe=69e30b2fd8) | Apr 07, 2023 |
| HP            | 620                         | Notebook    | [2e14b2c046](https://linux-hardware.org/?probe=2e14b2c046) | Apr 07, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [b6f721687e](https://linux-hardware.org/?probe=b6f721687e) | Apr 06, 2023 |
| HP            | ProBook 4740s               | Notebook    | [14fb51de44](https://linux-hardware.org/?probe=14fb51de44) | Apr 06, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [a71051ab5a](https://linux-hardware.org/?probe=a71051ab5a) | Apr 06, 2023 |
| eMachines     | E720 V1.09                  | Notebook    | [278ca903ac](https://linux-hardware.org/?probe=278ca903ac) | Apr 06, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [93cb5f66a1](https://linux-hardware.org/?probe=93cb5f66a1) | Apr 06, 2023 |
| Samsung       | 730U3E/740U3E               | Notebook    | [2be8e6430c](https://linux-hardware.org/?probe=2be8e6430c) | Apr 05, 2023 |
| Kruger&Mat... | KM1406                      | Notebook    | [1b536904d4](https://linux-hardware.org/?probe=1b536904d4) | Apr 05, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [f1398d5ada](https://linux-hardware.org/?probe=f1398d5ada) | Apr 05, 2023 |
| Toshiba       | Satellite C50-A             | Notebook    | [8e02a6dbed](https://linux-hardware.org/?probe=8e02a6dbed) | Apr 05, 2023 |
| ASRock        | B75 Pro3-M                  | Desktop     | [81b76a458e](https://linux-hardware.org/?probe=81b76a458e) | Apr 05, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [b469666726](https://linux-hardware.org/?probe=b469666726) | Apr 05, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [b9e77efbb1](https://linux-hardware.org/?probe=b9e77efbb1) | Apr 05, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [56119c4c93](https://linux-hardware.org/?probe=56119c4c93) | Apr 05, 2023 |
| Google        | Cyan                        | Notebook    | [f02aa2a210](https://linux-hardware.org/?probe=f02aa2a210) | Apr 04, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [0c0196b199](https://linux-hardware.org/?probe=0c0196b199) | Apr 04, 2023 |
| Dell          | 0Y2K8N A01                  | Desktop     | [379f9d7af7](https://linux-hardware.org/?probe=379f9d7af7) | Apr 04, 2023 |
| HP            | 82B5                        | All in one  | [59fe255866](https://linux-hardware.org/?probe=59fe255866) | Apr 04, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [6e8ca2befa](https://linux-hardware.org/?probe=6e8ca2befa) | Apr 04, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [04afa2e378](https://linux-hardware.org/?probe=04afa2e378) | Apr 04, 2023 |
| Lenovo        | B50-80 80LT                 | Notebook    | [163bfb5525](https://linux-hardware.org/?probe=163bfb5525) | Apr 03, 2023 |
| MSI           | B360M PRO-VD 2019-01-24     | Desktop     | [64fa944dfd](https://linux-hardware.org/?probe=64fa944dfd) | Apr 03, 2023 |
| HP            | Compaq CQ58                 | Notebook    | [f0026163c3](https://linux-hardware.org/?probe=f0026163c3) | Apr 03, 2023 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [6906a8d309](https://linux-hardware.org/?probe=6906a8d309) | Apr 03, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [71a388a292](https://linux-hardware.org/?probe=71a388a292) | Apr 03, 2023 |
| HP            | Compaq CQ58                 | Notebook    | [7c4676c380](https://linux-hardware.org/?probe=7c4676c380) | Apr 03, 2023 |
| HP            | Stream Notebook             | Notebook    | [27610e0a39](https://linux-hardware.org/?probe=27610e0a39) | Apr 03, 2023 |
| MSI           | PH67A-C43                   | Desktop     | [8e7c8a3d67](https://linux-hardware.org/?probe=8e7c8a3d67) | Apr 03, 2023 |
| Dell          | Latitude 3190               | Notebook    | [a1fa664431](https://linux-hardware.org/?probe=a1fa664431) | Apr 03, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [59bdd9d328](https://linux-hardware.org/?probe=59bdd9d328) | Apr 03, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [79ec23e706](https://linux-hardware.org/?probe=79ec23e706) | Apr 03, 2023 |
| ASUSTek       | TP300LJ                     | Notebook    | [7da5aab332](https://linux-hardware.org/?probe=7da5aab332) | Apr 02, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [c98048fb64](https://linux-hardware.org/?probe=c98048fb64) | Apr 02, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [0385e01f4d](https://linux-hardware.org/?probe=0385e01f4d) | Apr 02, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [20b1ee364f](https://linux-hardware.org/?probe=20b1ee364f) | Apr 02, 2023 |
| Lenovo        | ThinkPad T470 20HES0FA03    | Notebook    | [7274c8222b](https://linux-hardware.org/?probe=7274c8222b) | Apr 02, 2023 |
| ASUSTek       | ROG Rampage VI EXTREME      | Desktop     | [03fe72ba57](https://linux-hardware.org/?probe=03fe72ba57) | Apr 02, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [60e80d51ab](https://linux-hardware.org/?probe=60e80d51ab) | Apr 02, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [a51ad3deda](https://linux-hardware.org/?probe=a51ad3deda) | Apr 02, 2023 |
| HP            | ProBook 455 G1              | Notebook    | [869f36fc4c](https://linux-hardware.org/?probe=869f36fc4c) | Apr 01, 2023 |
| MSI           | MPG X570S CARBON MAX WIF... | Desktop     | [b7848305ec](https://linux-hardware.org/?probe=b7848305ec) | Apr 01, 2023 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [383835a445](https://linux-hardware.org/?probe=383835a445) | Apr 01, 2023 |
| Lenovo        | G560 20042                  | Notebook    | [c5a4783dfb](https://linux-hardware.org/?probe=c5a4783dfb) | Apr 01, 2023 |
| Dell          | 0TTDMJ A00                  | Desktop     | [5d6606235d](https://linux-hardware.org/?probe=5d6606235d) | Apr 01, 2023 |
| Gigabyte      | Z170-HD3 DDR3-CF            | Desktop     | [dff9959cd7](https://linux-hardware.org/?probe=dff9959cd7) | Mar 31, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [e5a729243d](https://linux-hardware.org/?probe=e5a729243d) | Mar 31, 2023 |
| Samsung       | 950XED                      | Notebook    | [c3b37a213a](https://linux-hardware.org/?probe=c3b37a213a) | Mar 31, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [4d69417ed0](https://linux-hardware.org/?probe=4d69417ed0) | Mar 31, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [e2c6f05595](https://linux-hardware.org/?probe=e2c6f05595) | Mar 31, 2023 |
| HUAWEI        | KPL-W0X                     | Notebook    | [6e93ca4159](https://linux-hardware.org/?probe=6e93ca4159) | Mar 31, 2023 |
| Acer          | TravelMate 8172Z            | Notebook    | [10cc090653](https://linux-hardware.org/?probe=10cc090653) | Mar 31, 2023 |
| Dell          | Latitude D620               | Notebook    | [801ede47a2](https://linux-hardware.org/?probe=801ede47a2) | Mar 31, 2023 |
| Acer          | WG43M                       | Desktop     | [3b626d2ff9](https://linux-hardware.org/?probe=3b626d2ff9) | Mar 31, 2023 |
| ASUSTek       | K53SJ                       | Notebook    | [aa9a729217](https://linux-hardware.org/?probe=aa9a729217) | Mar 30, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [6b9737a62f](https://linux-hardware.org/?probe=6b9737a62f) | Mar 30, 2023 |
| ASRock        | X670E PG Lightning          | Desktop     | [6078dd3087](https://linux-hardware.org/?probe=6078dd3087) | Mar 30, 2023 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [f78b6ab8c5](https://linux-hardware.org/?probe=f78b6ab8c5) | Mar 30, 2023 |
| ASUSTek       | M4A77T/USB3                 | Desktop     | [b593e25f2a](https://linux-hardware.org/?probe=b593e25f2a) | Mar 30, 2023 |
| Intel         | DQ45CB E30148-207           | Desktop     | [e47e1626c3](https://linux-hardware.org/?probe=e47e1626c3) | Mar 29, 2023 |
| Dell          | Latitude E6530              | Notebook    | [eb7392d1ae](https://linux-hardware.org/?probe=eb7392d1ae) | Mar 29, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [680c7a04ed](https://linux-hardware.org/?probe=680c7a04ed) | Mar 29, 2023 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [e7b163ea80](https://linux-hardware.org/?probe=e7b163ea80) | Mar 29, 2023 |
| GPD           | G1621-02                    | Notebook    | [2ed8b6c147](https://linux-hardware.org/?probe=2ed8b6c147) | Mar 29, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [fa1a582da6](https://linux-hardware.org/?probe=fa1a582da6) | Mar 29, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [9edda5f374](https://linux-hardware.org/?probe=9edda5f374) | Mar 28, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [c25f99afed](https://linux-hardware.org/?probe=c25f99afed) | Mar 28, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [94cdfc44d1](https://linux-hardware.org/?probe=94cdfc44d1) | Mar 28, 2023 |
| Kiano         | Elegance 14.2               | Notebook    | [ea2013b347](https://linux-hardware.org/?probe=ea2013b347) | Mar 28, 2023 |
| Lenovo        | ThinkPad T470p 20J7S0QK0... | Notebook    | [7f5fb11940](https://linux-hardware.org/?probe=7f5fb11940) | Mar 28, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Notebook    | [856b789461](https://linux-hardware.org/?probe=856b789461) | Mar 28, 2023 |
| Dell          | Latitude 7490               | Notebook    | [41d01ead49](https://linux-hardware.org/?probe=41d01ead49) | Mar 28, 2023 |
| Dell          | 0G261D A00                  | Desktop     | [f63f67f28f](https://linux-hardware.org/?probe=f63f67f28f) | Mar 28, 2023 |
| ASRock        | Z77 Extreme6                | Desktop     | [365cc196f2](https://linux-hardware.org/?probe=365cc196f2) | Mar 27, 2023 |
| Dell          | Inspiron 5735               | Notebook    | [823a6ece98](https://linux-hardware.org/?probe=823a6ece98) | Mar 27, 2023 |
| Lenovo        | ThinkPad X250 20CLS47P00    | Notebook    | [e287203572](https://linux-hardware.org/?probe=e287203572) | Mar 27, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [60012fd503](https://linux-hardware.org/?probe=60012fd503) | Mar 27, 2023 |
| Gigabyte      | H310M H                     | Desktop     | [16ba0fa199](https://linux-hardware.org/?probe=16ba0fa199) | Mar 27, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [7d0c0336c1](https://linux-hardware.org/?probe=7d0c0336c1) | Mar 27, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [aaeb6059a2](https://linux-hardware.org/?probe=aaeb6059a2) | Mar 27, 2023 |
| HP            | 895D                        | Desktop     | [1cba23395d](https://linux-hardware.org/?probe=1cba23395d) | Mar 27, 2023 |
| Dell          | Precision 7670              | Notebook    | [eece926391](https://linux-hardware.org/?probe=eece926391) | Mar 27, 2023 |
| Dell          | Latitude 3190               | Notebook    | [757f1fc2e7](https://linux-hardware.org/?probe=757f1fc2e7) | Mar 27, 2023 |
| HP            | 1998                        | Desktop     | [2d5e0737e5](https://linux-hardware.org/?probe=2d5e0737e5) | Mar 27, 2023 |
| Dell          | Precision 7670              | Notebook    | [5b8f0590ec](https://linux-hardware.org/?probe=5b8f0590ec) | Mar 27, 2023 |
| ASUSTek       | STRIX X99 GAMING            | Desktop     | [1c37ecb6c7](https://linux-hardware.org/?probe=1c37ecb6c7) | Mar 26, 2023 |
| ASRock        | AM1H-ITX                    | Desktop     | [8f1dcf05eb](https://linux-hardware.org/?probe=8f1dcf05eb) | Mar 26, 2023 |
| HP            | ProLiant DL360 G7           | Server      | [4e4f63c868](https://linux-hardware.org/?probe=4e4f63c868) | Mar 26, 2023 |
| Acer          | WG43M                       | Desktop     | [74320e2d13](https://linux-hardware.org/?probe=74320e2d13) | Mar 26, 2023 |
| Lenovo        | ThinkPad T520 4243RP3       | Notebook    | [38fa314d2f](https://linux-hardware.org/?probe=38fa314d2f) | Mar 26, 2023 |
| ASRock        | X370 Gaming X               | Desktop     | [0a19e934c3](https://linux-hardware.org/?probe=0a19e934c3) | Mar 26, 2023 |
| MSI           | Creator Z16 A11UET          | Notebook    | [0133ab37af](https://linux-hardware.org/?probe=0133ab37af) | Mar 26, 2023 |
| Sony          | VGN-BX61VN                  | Notebook    | [76f62cf9c1](https://linux-hardware.org/?probe=76f62cf9c1) | Mar 26, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [250e0a99d1](https://linux-hardware.org/?probe=250e0a99d1) | Mar 26, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [45abc5547d](https://linux-hardware.org/?probe=45abc5547d) | Mar 26, 2023 |
| Lenovo        | G510 20238                  | Notebook    | [f406bad420](https://linux-hardware.org/?probe=f406bad420) | Mar 26, 2023 |
| ASUSTek       | PRIME H310-PLUS             | Desktop     | [4fcf740ee9](https://linux-hardware.org/?probe=4fcf740ee9) | Mar 25, 2023 |
| MSI           | B360M PRO-VD 2019-01-24     | Desktop     | [71fc8dc05c](https://linux-hardware.org/?probe=71fc8dc05c) | Mar 25, 2023 |
| Lenovo        | ThinkPad W520 4282PQ7       | Notebook    | [ff42aa158f](https://linux-hardware.org/?probe=ff42aa158f) | Mar 25, 2023 |
| HP            | EliteBook x360 1040 G5      | Convertible | [1301dd9965](https://linux-hardware.org/?probe=1301dd9965) | Mar 25, 2023 |
| HP            | Notebook                    | Notebook    | [7c4088912e](https://linux-hardware.org/?probe=7c4088912e) | Mar 25, 2023 |
| HP            | EliteBook x360 1040 G5      | Convertible | [eaf933f33a](https://linux-hardware.org/?probe=eaf933f33a) | Mar 25, 2023 |
| ASUSTek       | PRIME H310-PLUS             | Desktop     | [caa720b95b](https://linux-hardware.org/?probe=caa720b95b) | Mar 25, 2023 |
| Lenovo        | ThinkPad T480s 20L7S0YA0... | Notebook    | [f4cb79dbf8](https://linux-hardware.org/?probe=f4cb79dbf8) | Mar 25, 2023 |
| Valve         | Jupiter                     | Notebook    | [6a7628c31d](https://linux-hardware.org/?probe=6a7628c31d) | Mar 25, 2023 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [c7bf2c9968](https://linux-hardware.org/?probe=c7bf2c9968) | Mar 25, 2023 |
| HP            | Pavilion dv6                | Notebook    | [29a94d3d9e](https://linux-hardware.org/?probe=29a94d3d9e) | Mar 25, 2023 |
| HP            | Pavilion dv6                | Notebook    | [c3a6c3f669](https://linux-hardware.org/?probe=c3a6c3f669) | Mar 25, 2023 |
| Samsung       | 950QED                      | Convertible | [14fa80f70c](https://linux-hardware.org/?probe=14fa80f70c) | Mar 25, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [7f32708bde](https://linux-hardware.org/?probe=7f32708bde) | Mar 24, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [446c510c65](https://linux-hardware.org/?probe=446c510c65) | Mar 24, 2023 |
| Toshiba       | Satellite C855-12N          | Notebook    | [cb9692876c](https://linux-hardware.org/?probe=cb9692876c) | Mar 24, 2023 |
| HP            | 304Ah                       | Desktop     | [43990fede2](https://linux-hardware.org/?probe=43990fede2) | Mar 24, 2023 |
| Toshiba       | Satellite Pro A50-C         | Notebook    | [2fe9003124](https://linux-hardware.org/?probe=2fe9003124) | Mar 24, 2023 |
| Toshiba       | Satellite Pro A50-C         | Notebook    | [95c5c45220](https://linux-hardware.org/?probe=95c5c45220) | Mar 24, 2023 |
| MSI           | Creator Z17 A12UHST         | Notebook    | [47814b01b6](https://linux-hardware.org/?probe=47814b01b6) | Mar 24, 2023 |
| Sony          | SVE1512M6ESI                | Notebook    | [db00c70eb7](https://linux-hardware.org/?probe=db00c70eb7) | Mar 24, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [d18034c36c](https://linux-hardware.org/?probe=d18034c36c) | Mar 24, 2023 |
| Dell          | 0NDYHG A01                  | Desktop     | [93bc601af0](https://linux-hardware.org/?probe=93bc601af0) | Mar 23, 2023 |
| Dell          | Latitude E7450              | Notebook    | [c1e43b6a40](https://linux-hardware.org/?probe=c1e43b6a40) | Mar 23, 2023 |
| Lenovo        | G580                        | Notebook    | [367ed9241a](https://linux-hardware.org/?probe=367ed9241a) | Mar 23, 2023 |
| Dell          | 0DPRKF A01                  | Server      | [fdc74a5707](https://linux-hardware.org/?probe=fdc74a5707) | Mar 23, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d32ee19009](https://linux-hardware.org/?probe=d32ee19009) | Mar 23, 2023 |
| Lenovo        | G580                        | Notebook    | [6ee526d77a](https://linux-hardware.org/?probe=6ee526d77a) | Mar 22, 2023 |
| Acer          | Aspire VN7-791              | Notebook    | [054efde4e8](https://linux-hardware.org/?probe=054efde4e8) | Mar 22, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [f6ad6626ff](https://linux-hardware.org/?probe=f6ad6626ff) | Mar 22, 2023 |
| HUAWEI        | KPL-W0X                     | Notebook    | [0ae6ab3ff6](https://linux-hardware.org/?probe=0ae6ab3ff6) | Mar 21, 2023 |
| Unknown       | Unknown                     | Notebook    | [31ee1d66d8](https://linux-hardware.org/?probe=31ee1d66d8) | Mar 21, 2023 |
| Gigabyte      | EX38-DS4                    | Desktop     | [6dd3e18637](https://linux-hardware.org/?probe=6dd3e18637) | Mar 21, 2023 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [57663c8d60](https://linux-hardware.org/?probe=57663c8d60) | Mar 21, 2023 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [f5cbd1977f](https://linux-hardware.org/?probe=f5cbd1977f) | Mar 20, 2023 |
| Gigabyte      | A520I AC                    | Desktop     | [a9e094374a](https://linux-hardware.org/?probe=a9e094374a) | Mar 20, 2023 |
| Dell          | Latitude 3190               | Notebook    | [f4bea67dcc](https://linux-hardware.org/?probe=f4bea67dcc) | Mar 20, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [a03658793c](https://linux-hardware.org/?probe=a03658793c) | Mar 20, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [6df656c198](https://linux-hardware.org/?probe=6df656c198) | Mar 20, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [1bad88b80e](https://linux-hardware.org/?probe=1bad88b80e) | Mar 20, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [ba804b8e21](https://linux-hardware.org/?probe=ba804b8e21) | Mar 20, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [7b4a68e88a](https://linux-hardware.org/?probe=7b4a68e88a) | Mar 20, 2023 |
| MSI           | B360M PRO-VD 2019-01-24     | Desktop     | [cd708d0e58](https://linux-hardware.org/?probe=cd708d0e58) | Mar 19, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [a71c5a4629](https://linux-hardware.org/?probe=a71c5a4629) | Mar 19, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [888ec192b4](https://linux-hardware.org/?probe=888ec192b4) | Mar 19, 2023 |
| ASRock        | X370 Gaming X               | Desktop     | [4f98540a7b](https://linux-hardware.org/?probe=4f98540a7b) | Mar 19, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [efbab00e4b](https://linux-hardware.org/?probe=efbab00e4b) | Mar 19, 2023 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [919ccc204b](https://linux-hardware.org/?probe=919ccc204b) | Mar 19, 2023 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [703ea3d03c](https://linux-hardware.org/?probe=703ea3d03c) | Mar 18, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c89c2e1369](https://linux-hardware.org/?probe=c89c2e1369) | Mar 18, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [31299394e0](https://linux-hardware.org/?probe=31299394e0) | Mar 18, 2023 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [e40cf4f577](https://linux-hardware.org/?probe=e40cf4f577) | Mar 18, 2023 |
| Dell          | Venue 11 Pro 7130 MS        | Notebook    | [2a3bb3e212](https://linux-hardware.org/?probe=2a3bb3e212) | Mar 18, 2023 |
| Dell          | Venue 11 Pro 7130 MS        | Notebook    | [56fab2cb17](https://linux-hardware.org/?probe=56fab2cb17) | Mar 18, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [2d7a146140](https://linux-hardware.org/?probe=2d7a146140) | Mar 18, 2023 |
| ASUSTek       | K52Jc                       | Notebook    | [07dc0a0959](https://linux-hardware.org/?probe=07dc0a0959) | Mar 18, 2023 |
| ASUSTek       | K52Jc                       | Notebook    | [f61ec5ce9f](https://linux-hardware.org/?probe=f61ec5ce9f) | Mar 18, 2023 |
| Dell          | Latitude 5420               | Notebook    | [318da7f6c0](https://linux-hardware.org/?probe=318da7f6c0) | Mar 18, 2023 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [a5775c7491](https://linux-hardware.org/?probe=a5775c7491) | Mar 17, 2023 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [2a17e297a2](https://linux-hardware.org/?probe=2a17e297a2) | Mar 17, 2023 |
| Toshiba       | QOSMIO X500                 | Notebook    | [2ce878e92e](https://linux-hardware.org/?probe=2ce878e92e) | Mar 17, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [96742a0cb2](https://linux-hardware.org/?probe=96742a0cb2) | Mar 17, 2023 |
| Dell          | 0T1D10 A01                  | Desktop     | [c640b09a8b](https://linux-hardware.org/?probe=c640b09a8b) | Mar 17, 2023 |
| Dell          | G5 5590                     | Notebook    | [9686d438e6](https://linux-hardware.org/?probe=9686d438e6) | Mar 17, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [728c9ad9f5](https://linux-hardware.org/?probe=728c9ad9f5) | Mar 17, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [593bd6b3ac](https://linux-hardware.org/?probe=593bd6b3ac) | Mar 17, 2023 |
| Dell          | Latitude E7440              | Notebook    | [8a6e751b61](https://linux-hardware.org/?probe=8a6e751b61) | Mar 16, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [4a452568eb](https://linux-hardware.org/?probe=4a452568eb) | Mar 16, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [f53eccbbe9](https://linux-hardware.org/?probe=f53eccbbe9) | Mar 16, 2023 |
| Dell          | Latitude 5511               | Notebook    | [7444a8c723](https://linux-hardware.org/?probe=7444a8c723) | Mar 16, 2023 |
| HP            | ProLiant DL360 Gen9         | Server      | [e75695c0ea](https://linux-hardware.org/?probe=e75695c0ea) | Mar 16, 2023 |
| HP            | ProLiant DL360 Gen9         | Server      | [d8bdd6ff7c](https://linux-hardware.org/?probe=d8bdd6ff7c) | Mar 16, 2023 |
| Dell          | Latitude D620               | Notebook    | [1731735e10](https://linux-hardware.org/?probe=1731735e10) | Mar 16, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [eb0beb38eb](https://linux-hardware.org/?probe=eb0beb38eb) | Mar 16, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [c54f2ca880](https://linux-hardware.org/?probe=c54f2ca880) | Mar 16, 2023 |
| Sony          | VPCEH1S1E                   | Notebook    | [9e8a96156c](https://linux-hardware.org/?probe=9e8a96156c) | Mar 15, 2023 |
| Lenovo        | ThinkPad T440p 20AWS19P0... | Notebook    | [6a2d338526](https://linux-hardware.org/?probe=6a2d338526) | Mar 15, 2023 |
| Dell          | 03NVJ6 A02                  | Desktop     | [b5281b4ba4](https://linux-hardware.org/?probe=b5281b4ba4) | Mar 15, 2023 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | Notebook    | [59d7fa9a34](https://linux-hardware.org/?probe=59d7fa9a34) | Mar 15, 2023 |
| Dell          | Latitude 7390               | Notebook    | [7cc6b3a278](https://linux-hardware.org/?probe=7cc6b3a278) | Mar 15, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [8c2507428d](https://linux-hardware.org/?probe=8c2507428d) | Mar 15, 2023 |
| MSI           | B85-G43                     | Desktop     | [d8334d09fa](https://linux-hardware.org/?probe=d8334d09fa) | Mar 15, 2023 |
| Dell          | 0773VG A00                  | Desktop     | [320dab99e7](https://linux-hardware.org/?probe=320dab99e7) | Mar 15, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | Notebook    | [97fe8661ed](https://linux-hardware.org/?probe=97fe8661ed) | Mar 14, 2023 |
| Dell          | 0C96W1 A03                  | Desktop     | [171959ac44](https://linux-hardware.org/?probe=171959ac44) | Mar 14, 2023 |
| Dell          | 0C96W1 A03                  | Desktop     | [9456c9ff8e](https://linux-hardware.org/?probe=9456c9ff8e) | Mar 14, 2023 |
| Kiano         | Elegance 14.2               | Notebook    | [f9ed050c6a](https://linux-hardware.org/?probe=f9ed050c6a) | Mar 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [daa3d3869e](https://linux-hardware.org/?probe=daa3d3869e) | Mar 14, 2023 |
| Gigabyte      | P55M-UD2                    | Desktop     | [74cdc2f679](https://linux-hardware.org/?probe=74cdc2f679) | Mar 14, 2023 |
| HP            | ProBook 450 G3              | Notebook    | [d422d0d291](https://linux-hardware.org/?probe=d422d0d291) | Mar 14, 2023 |
| Lenovo        | ThinkPad X301 2776LEG       | Notebook    | [7b0df25d34](https://linux-hardware.org/?probe=7b0df25d34) | Mar 14, 2023 |
| Lenovo        | ThinkPad X301 2776LEG       | Notebook    | [65fe38f62e](https://linux-hardware.org/?probe=65fe38f62e) | Mar 14, 2023 |
| Toshiba       | Satellite L40               | Notebook    | [bfc73429bb](https://linux-hardware.org/?probe=bfc73429bb) | Mar 13, 2023 |
| Samsung       | 300E4A/300E5A/300E7A        | Notebook    | [6c76af84cb](https://linux-hardware.org/?probe=6c76af84cb) | Mar 13, 2023 |
| Acer          | Aspire A315-24P             | Notebook    | [b9cfb4b900](https://linux-hardware.org/?probe=b9cfb4b900) | Mar 13, 2023 |
| Acer          | Aspire A315-24P             | Notebook    | [fba21e619d](https://linux-hardware.org/?probe=fba21e619d) | Mar 13, 2023 |
| HP            | Pavilion dv6                | Notebook    | [f649c78020](https://linux-hardware.org/?probe=f649c78020) | Mar 13, 2023 |
| MSI           | B85-G43                     | Desktop     | [e270b5804a](https://linux-hardware.org/?probe=e270b5804a) | Mar 13, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [bc375a2ddd](https://linux-hardware.org/?probe=bc375a2ddd) | Mar 13, 2023 |
| Dell          | 051FJ8 A02                  | Desktop     | [4c5eee300d](https://linux-hardware.org/?probe=4c5eee300d) | Mar 13, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [a0590e6829](https://linux-hardware.org/?probe=a0590e6829) | Mar 13, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [73d5ba11c5](https://linux-hardware.org/?probe=73d5ba11c5) | Mar 13, 2023 |
| Dell          | Latitude 3190               | Notebook    | [97cc3ffc79](https://linux-hardware.org/?probe=97cc3ffc79) | Mar 13, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [540bfa93eb](https://linux-hardware.org/?probe=540bfa93eb) | Mar 13, 2023 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | Desktop     | [0b0840b785](https://linux-hardware.org/?probe=0b0840b785) | Mar 13, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [8f1fe0703b](https://linux-hardware.org/?probe=8f1fe0703b) | Mar 12, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [0e2618e3ea](https://linux-hardware.org/?probe=0e2618e3ea) | Mar 12, 2023 |
| ASUSTek       | X551MA                      | Notebook    | [37b002e8ec](https://linux-hardware.org/?probe=37b002e8ec) | Mar 12, 2023 |
| Gigabyte      | B85M-D3H-A                  | Desktop     | [4265744c52](https://linux-hardware.org/?probe=4265744c52) | Mar 12, 2023 |
| Lenovo        | ThinkPad X240 20AMS0XP0S    | Notebook    | [a2ee9a2818](https://linux-hardware.org/?probe=a2ee9a2818) | Mar 12, 2023 |
| ASUSTek       | N550JK                      | Notebook    | [bb5d069d90](https://linux-hardware.org/?probe=bb5d069d90) | Mar 12, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [afe81d4bfa](https://linux-hardware.org/?probe=afe81d4bfa) | Mar 12, 2023 |
| HP            | 213D A01                    | Desktop     | [8c6054a4f7](https://linux-hardware.org/?probe=8c6054a4f7) | Mar 12, 2023 |
| Google        | Electro                     | Notebook    | [86cbc9d907](https://linux-hardware.org/?probe=86cbc9d907) | Mar 12, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [566beba012](https://linux-hardware.org/?probe=566beba012) | Mar 12, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [d173735b81](https://linux-hardware.org/?probe=d173735b81) | Mar 11, 2023 |
| Dell          | Precision M6600             | Notebook    | [9d5e2f1e01](https://linux-hardware.org/?probe=9d5e2f1e01) | Mar 11, 2023 |
| Acer          | Extensa 5620                | Notebook    | [f95239bf35](https://linux-hardware.org/?probe=f95239bf35) | Mar 11, 2023 |
| Kiano         | Elegance 14.2               | Notebook    | [5714b30108](https://linux-hardware.org/?probe=5714b30108) | Mar 11, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [8736fd04a8](https://linux-hardware.org/?probe=8736fd04a8) | Mar 11, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [82b5297ab8](https://linux-hardware.org/?probe=82b5297ab8) | Mar 11, 2023 |
| MSI           | Z170-A PRO                  | Desktop     | [a83243223a](https://linux-hardware.org/?probe=a83243223a) | Mar 10, 2023 |
| HP            | 0AA0h                       | Desktop     | [f86f0bc187](https://linux-hardware.org/?probe=f86f0bc187) | Mar 10, 2023 |
| Lenovo        | ThinkPad T440p 20AWS19P0... | Notebook    | [44867c946f](https://linux-hardware.org/?probe=44867c946f) | Mar 10, 2023 |
| Dell          | Latitude E6530              | Notebook    | [70b72984bc](https://linux-hardware.org/?probe=70b72984bc) | Mar 10, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [bf4c797c87](https://linux-hardware.org/?probe=bf4c797c87) | Mar 10, 2023 |
| Hampoo        | P02BD6_HI-122LP             | Tablet      | [bfd26d4727](https://linux-hardware.org/?probe=bfd26d4727) | Mar 10, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | Notebook    | [2d99e047c9](https://linux-hardware.org/?probe=2d99e047c9) | Mar 10, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | Notebook    | [99d5f17b22](https://linux-hardware.org/?probe=99d5f17b22) | Mar 09, 2023 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [7a7e8bc855](https://linux-hardware.org/?probe=7a7e8bc855) | Mar 09, 2023 |
| ASRock        | AM1H-ITX                    | Desktop     | [a0eb3774fc](https://linux-hardware.org/?probe=a0eb3774fc) | Mar 09, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [9acfcb9b4f](https://linux-hardware.org/?probe=9acfcb9b4f) | Mar 09, 2023 |
| Lenovo        | IdeaPad Y580                | Notebook    | [cc2d7d8a95](https://linux-hardware.org/?probe=cc2d7d8a95) | Mar 09, 2023 |
| Dell          | Latitude E6440              | Notebook    | [b00f44cd46](https://linux-hardware.org/?probe=b00f44cd46) | Mar 09, 2023 |
| Dell          | Latitude E6440              | Notebook    | [3b9229e07a](https://linux-hardware.org/?probe=3b9229e07a) | Mar 09, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [c50daaf3b9](https://linux-hardware.org/?probe=c50daaf3b9) | Mar 09, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [670e89da85](https://linux-hardware.org/?probe=670e89da85) | Mar 09, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [fdc32a6871](https://linux-hardware.org/?probe=fdc32a6871) | Mar 09, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [21f11cf791](https://linux-hardware.org/?probe=21f11cf791) | Mar 09, 2023 |
| ASUSTek       | A68HM-K                     | Desktop     | [12fa2455f7](https://linux-hardware.org/?probe=12fa2455f7) | Mar 08, 2023 |
| HP            | EliteBook 8570w             | Notebook    | [dfd9b7a9b9](https://linux-hardware.org/?probe=dfd9b7a9b9) | Mar 08, 2023 |
| HP            | ENVY 6                      | Notebook    | [4873f7b85f](https://linux-hardware.org/?probe=4873f7b85f) | Mar 08, 2023 |
| ASRock        | Z370M Pro4                  | Desktop     | [c4bb8436ac](https://linux-hardware.org/?probe=c4bb8436ac) | Mar 08, 2023 |
| Lenovo        | MAHOBAY                     | Desktop     | [c756678fad](https://linux-hardware.org/?probe=c756678fad) | Mar 08, 2023 |
| Lenovo        | ThinkPad T61 7661BM5        | Notebook    | [daf29f1a82](https://linux-hardware.org/?probe=daf29f1a82) | Mar 08, 2023 |
| Dell          | 03NVJ6 A02                  | Desktop     | [34696138fe](https://linux-hardware.org/?probe=34696138fe) | Mar 08, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [233722f0e1](https://linux-hardware.org/?probe=233722f0e1) | Mar 07, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [43a939870d](https://linux-hardware.org/?probe=43a939870d) | Mar 07, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [f64ba0ea72](https://linux-hardware.org/?probe=f64ba0ea72) | Mar 07, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [397eb062bf](https://linux-hardware.org/?probe=397eb062bf) | Mar 07, 2023 |
| Dell          | 0T1D10 A01                  | Desktop     | [ef67915ff3](https://linux-hardware.org/?probe=ef67915ff3) | Mar 07, 2023 |
| Dell          | Latitude 7290               | Notebook    | [38f12088b2](https://linux-hardware.org/?probe=38f12088b2) | Mar 07, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [59cb6854e5](https://linux-hardware.org/?probe=59cb6854e5) | Mar 07, 2023 |
| ASUSTek       | A88XM-E                     | Desktop     | [b809f137cd](https://linux-hardware.org/?probe=b809f137cd) | Mar 07, 2023 |
| Dell          | 0K6VXP A00                  | Mini pc     | [838825a42b](https://linux-hardware.org/?probe=838825a42b) | Mar 06, 2023 |
| Microsoft     | Surface Laptop Go 2         | Tablet      | [f5a1ceaa74](https://linux-hardware.org/?probe=f5a1ceaa74) | Mar 06, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [0cda9f83b1](https://linux-hardware.org/?probe=0cda9f83b1) | Mar 06, 2023 |
| HUAWEI        | KPL-W0X                     | Notebook    | [76ebbe553f](https://linux-hardware.org/?probe=76ebbe553f) | Mar 06, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [42edcf638d](https://linux-hardware.org/?probe=42edcf638d) | Mar 06, 2023 |
| Dell          | Latitude 3190               | Notebook    | [a3a4113ab4](https://linux-hardware.org/?probe=a3a4113ab4) | Mar 06, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [31a734c56b](https://linux-hardware.org/?probe=31a734c56b) | Mar 06, 2023 |
| Biostar       | TA780G M2+                  | Desktop     | [f5ddb4d21a](https://linux-hardware.org/?probe=f5ddb4d21a) | Mar 05, 2023 |
| Lenovo        | Legion 5 17ACH6 82K0        | Notebook    | [6db57d4d9f](https://linux-hardware.org/?probe=6db57d4d9f) | Mar 05, 2023 |
| MSI           | B550M PRO                   | Desktop     | [6d904e2413](https://linux-hardware.org/?probe=6d904e2413) | Mar 05, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [91fc2d53f8](https://linux-hardware.org/?probe=91fc2d53f8) | Mar 05, 2023 |
| HP            | 18E5                        | Desktop     | [969462a8a0](https://linux-hardware.org/?probe=969462a8a0) | Mar 05, 2023 |
| Dell          | 03NVJ6 A02                  | Desktop     | [80e769b994](https://linux-hardware.org/?probe=80e769b994) | Mar 05, 2023 |
| ASUSTek       | X551MA                      | Notebook    | [b77e06361b](https://linux-hardware.org/?probe=b77e06361b) | Mar 05, 2023 |
| Lenovo        | ThinkPad T440p 20AWS37F0... | Notebook    | [48677f9f86](https://linux-hardware.org/?probe=48677f9f86) | Mar 05, 2023 |
| IGEL Techn... | H830C                       | Notebook    | [3619b3fcee](https://linux-hardware.org/?probe=3619b3fcee) | Mar 05, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [92b81bb3a1](https://linux-hardware.org/?probe=92b81bb3a1) | Mar 05, 2023 |
| ASUSTek       | A88XM-E                     | Desktop     | [ea145a8349](https://linux-hardware.org/?probe=ea145a8349) | Mar 05, 2023 |
| ASUSTek       | N71Vg                       | Notebook    | [4d83fda5ba](https://linux-hardware.org/?probe=4d83fda5ba) | Mar 05, 2023 |
| Gigabyte      | PH67A-D3-B3                 | Desktop     | [145a0a3b7d](https://linux-hardware.org/?probe=145a0a3b7d) | Mar 05, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Notebook    | [8b36c984f8](https://linux-hardware.org/?probe=8b36c984f8) | Mar 05, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [65006682e6](https://linux-hardware.org/?probe=65006682e6) | Mar 05, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [d9a9f6b904](https://linux-hardware.org/?probe=d9a9f6b904) | Mar 05, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [773ac5157e](https://linux-hardware.org/?probe=773ac5157e) | Mar 05, 2023 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | Desktop     | [cf87d901a9](https://linux-hardware.org/?probe=cf87d901a9) | Mar 05, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [5eb43b511f](https://linux-hardware.org/?probe=5eb43b511f) | Mar 05, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [8db9ca3a4b](https://linux-hardware.org/?probe=8db9ca3a4b) | Mar 05, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [541a6200bc](https://linux-hardware.org/?probe=541a6200bc) | Mar 05, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [789ca3b7bd](https://linux-hardware.org/?probe=789ca3b7bd) | Mar 05, 2023 |
| HP            | 15                          | Notebook    | [0efd9be7ae](https://linux-hardware.org/?probe=0efd9be7ae) | Mar 04, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [241283977d](https://linux-hardware.org/?probe=241283977d) | Mar 04, 2023 |
| HP            | 15                          | Notebook    | [b8a33a3d73](https://linux-hardware.org/?probe=b8a33a3d73) | Mar 04, 2023 |
| Lenovo        | ThinkPad T420 4177R3U       | Notebook    | [525dd38cf1](https://linux-hardware.org/?probe=525dd38cf1) | Mar 04, 2023 |
| Toshiba       | Satellite L40               | Notebook    | [bd108fcfba](https://linux-hardware.org/?probe=bd108fcfba) | Mar 04, 2023 |
| HP            | Notebook                    | Notebook    | [229fbff95c](https://linux-hardware.org/?probe=229fbff95c) | Mar 04, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [afe8ef7318](https://linux-hardware.org/?probe=afe8ef7318) | Mar 04, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [82acbe37f7](https://linux-hardware.org/?probe=82acbe37f7) | Mar 04, 2023 |
| Dell          | Vostro 3350                 | Notebook    | [1bfad93a1e](https://linux-hardware.org/?probe=1bfad93a1e) | Mar 04, 2023 |
| Dell          | Vostro 3350                 | Notebook    | [f782f8e288](https://linux-hardware.org/?probe=f782f8e288) | Mar 04, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [0b0c5a6895](https://linux-hardware.org/?probe=0b0c5a6895) | Mar 04, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [c16eae7537](https://linux-hardware.org/?probe=c16eae7537) | Mar 04, 2023 |
| IGEL Techn... | H830C                       | Notebook    | [4625dc0660](https://linux-hardware.org/?probe=4625dc0660) | Mar 04, 2023 |
| Toshiba       | Satellite L40               | Notebook    | [e3f1423c39](https://linux-hardware.org/?probe=e3f1423c39) | Mar 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | Notebook    | [0228fd4ab1](https://linux-hardware.org/?probe=0228fd4ab1) | Mar 04, 2023 |
| Dell          | Latitude 5480               | Notebook    | [4679c9328e](https://linux-hardware.org/?probe=4679c9328e) | Mar 03, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [9186971572](https://linux-hardware.org/?probe=9186971572) | Mar 03, 2023 |
| ASRock        | Z87 Extreme4                | Desktop     | [d085a259d5](https://linux-hardware.org/?probe=d085a259d5) | Mar 03, 2023 |
| Dell          | 03NVJ6 A01                  | Desktop     | [0e8d1a9e75](https://linux-hardware.org/?probe=0e8d1a9e75) | Mar 03, 2023 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | Notebook    | [25f45efbc1](https://linux-hardware.org/?probe=25f45efbc1) | Mar 03, 2023 |
| ASUSTek       | X551MA                      | Notebook    | [608c8a42da](https://linux-hardware.org/?probe=608c8a42da) | Mar 03, 2023 |
| ASUSTek       | X551MA                      | Notebook    | [fa55d9fb5c](https://linux-hardware.org/?probe=fa55d9fb5c) | Mar 03, 2023 |
| Lenovo        | ThinkPad T480s 20L8S2B50... | Notebook    | [8268a3bbf3](https://linux-hardware.org/?probe=8268a3bbf3) | Mar 03, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [1a83a85925](https://linux-hardware.org/?probe=1a83a85925) | Mar 03, 2023 |
| Supermicro    | X11SCL-F                    | Server      | [ef92c1fc32](https://linux-hardware.org/?probe=ef92c1fc32) | Mar 03, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [a40e18910c](https://linux-hardware.org/?probe=a40e18910c) | Mar 03, 2023 |
| ASUSTek       | N61Vn                       | Notebook    | [9528e36d7b](https://linux-hardware.org/?probe=9528e36d7b) | Mar 03, 2023 |
| ASUSTek       | Maximus VII RANGER          | Desktop     | [3934b91be7](https://linux-hardware.org/?probe=3934b91be7) | Mar 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [726752f23a](https://linux-hardware.org/?probe=726752f23a) | Mar 02, 2023 |
| Dell          | 0HFG24 A01                  | Server      | [b53826c91c](https://linux-hardware.org/?probe=b53826c91c) | Mar 02, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [a5288ab43b](https://linux-hardware.org/?probe=a5288ab43b) | Mar 02, 2023 |
| HP            | ZBook Power G7 Mobile Wo... | Notebook    | [e87ce2454c](https://linux-hardware.org/?probe=e87ce2454c) | Mar 02, 2023 |
| Dell          | Latitude D830               | Notebook    | [83415c82ac](https://linux-hardware.org/?probe=83415c82ac) | Mar 02, 2023 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [a79b4ff73c](https://linux-hardware.org/?probe=a79b4ff73c) | Mar 02, 2023 |
| Acer          | Aspire V3-574G              | Notebook    | [e943ab2cde](https://linux-hardware.org/?probe=e943ab2cde) | Mar 01, 2023 |
| Huanan        | X99-F8 NALEX, NALEX         | Desktop     | [ada9b78c86](https://linux-hardware.org/?probe=ada9b78c86) | Mar 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [9b0d952fa9](https://linux-hardware.org/?probe=9b0d952fa9) | Mar 01, 2023 |
| Notebook      | NS50_70MU                   | Notebook    | [18ff6f22a6](https://linux-hardware.org/?probe=18ff6f22a6) | Mar 01, 2023 |
| Dell          | Latitude 7330               | Convertible | [0ad2e974ba](https://linux-hardware.org/?probe=0ad2e974ba) | Mar 01, 2023 |
| Dell          | Latitude 5420               | Notebook    | [0596aff5c4](https://linux-hardware.org/?probe=0596aff5c4) | Feb 28, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [52522a762d](https://linux-hardware.org/?probe=52522a762d) | Feb 28, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [07bb534dc9](https://linux-hardware.org/?probe=07bb534dc9) | Feb 28, 2023 |
| Lenovo        | Yoga710-14ISK 80TY          | Notebook    | [756e003316](https://linux-hardware.org/?probe=756e003316) | Feb 28, 2023 |
| HP            | ZBook 15u G3                | Notebook    | [9c49a1748b](https://linux-hardware.org/?probe=9c49a1748b) | Feb 28, 2023 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [260ece1650](https://linux-hardware.org/?probe=260ece1650) | Feb 28, 2023 |
| Lenovo        | ThinkPad E560 20EV000UUK    | Notebook    | [7060b60651](https://linux-hardware.org/?probe=7060b60651) | Feb 27, 2023 |
| HP            | ProBook 430 G6              | Notebook    | [a184aa7141](https://linux-hardware.org/?probe=a184aa7141) | Feb 27, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [d7bb021829](https://linux-hardware.org/?probe=d7bb021829) | Feb 27, 2023 |
| ASUSTek       | K75VJ                       | Notebook    | [7fc0fff829](https://linux-hardware.org/?probe=7fc0fff829) | Feb 27, 2023 |
| Dell          | Latitude 7390               | Notebook    | [a2167ae72b](https://linux-hardware.org/?probe=a2167ae72b) | Feb 27, 2023 |
| Schenker      | VISION (E22)                | Notebook    | [498444ca02](https://linux-hardware.org/?probe=498444ca02) | Feb 27, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [1ce9430009](https://linux-hardware.org/?probe=1ce9430009) | Feb 27, 2023 |
| HP            | Notebook                    | Notebook    | [a1180ad479](https://linux-hardware.org/?probe=a1180ad479) | Feb 27, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [409bb06e5e](https://linux-hardware.org/?probe=409bb06e5e) | Feb 27, 2023 |
| HP            | Notebook                    | Notebook    | [ee2645efa8](https://linux-hardware.org/?probe=ee2645efa8) | Feb 27, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [d57bb59dee](https://linux-hardware.org/?probe=d57bb59dee) | Feb 27, 2023 |
| ASUSTek       | K52F                        | Notebook    | [fa30ea101a](https://linux-hardware.org/?probe=fa30ea101a) | Feb 27, 2023 |
| Dell          | Latitude 3190               | Notebook    | [279b385865](https://linux-hardware.org/?probe=279b385865) | Feb 27, 2023 |
| HP            | Notebook                    | Notebook    | [0d838134b7](https://linux-hardware.org/?probe=0d838134b7) | Feb 27, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [aa86292f52](https://linux-hardware.org/?probe=aa86292f52) | Feb 27, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [f8d42c3767](https://linux-hardware.org/?probe=f8d42c3767) | Feb 27, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [589b06afc1](https://linux-hardware.org/?probe=589b06afc1) | Feb 26, 2023 |
| Acer          | Aspire ES1-711              | Notebook    | [8e397cc54f](https://linux-hardware.org/?probe=8e397cc54f) | Feb 26, 2023 |
| Gigabyte      | GA-MA78LMT-US2H             | Desktop     | [df54545112](https://linux-hardware.org/?probe=df54545112) | Feb 26, 2023 |
| Dell          | 0K6VXP A00                  | Mini pc     | [9357168131](https://linux-hardware.org/?probe=9357168131) | Feb 26, 2023 |
| Gigabyte      | MMLP5AP-00                  | Notebook    | [eb5ca5bb8d](https://linux-hardware.org/?probe=eb5ca5bb8d) | Feb 26, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [f09bf9b926](https://linux-hardware.org/?probe=f09bf9b926) | Feb 26, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [cf1d88a388](https://linux-hardware.org/?probe=cf1d88a388) | Feb 26, 2023 |
| Valve         | Jupiter                     | Notebook    | [f7289abeb1](https://linux-hardware.org/?probe=f7289abeb1) | Feb 26, 2023 |
| Dell          | Latitude D630               | Notebook    | [cfdc009ff1](https://linux-hardware.org/?probe=cfdc009ff1) | Feb 26, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [782598981d](https://linux-hardware.org/?probe=782598981d) | Feb 25, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [6a75456290](https://linux-hardware.org/?probe=6a75456290) | Feb 25, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [73caef7b95](https://linux-hardware.org/?probe=73caef7b95) | Feb 25, 2023 |
| Acer          | Aspire E5-571G              | Notebook    | [07fe4333eb](https://linux-hardware.org/?probe=07fe4333eb) | Feb 25, 2023 |
| Gigabyte      | G31M-S2L                    | Desktop     | [563101d2b2](https://linux-hardware.org/?probe=563101d2b2) | Feb 25, 2023 |
| ASRock        | AM1H-ITX                    | Desktop     | [2029821da8](https://linux-hardware.org/?probe=2029821da8) | Feb 25, 2023 |
| Sony          | VGN-FZ31M                   | Notebook    | [6b830e36f1](https://linux-hardware.org/?probe=6b830e36f1) | Feb 25, 2023 |
| MSI           | B350M MORTAR                | Desktop     | [6a7ac3b38b](https://linux-hardware.org/?probe=6a7ac3b38b) | Feb 24, 2023 |
| Gigabyte      | GA-MA78LMT-US2H             | Desktop     | [b2681528bd](https://linux-hardware.org/?probe=b2681528bd) | Feb 24, 2023 |
| ASUSTek       | B150M-A D3                  | Desktop     | [01caadaee0](https://linux-hardware.org/?probe=01caadaee0) | Feb 24, 2023 |
| ASRock        | M3A770DE                    | Desktop     | [b025c7a092](https://linux-hardware.org/?probe=b025c7a092) | Feb 24, 2023 |
| HP            | ZBook 15u G3                | Notebook    | [92879d708d](https://linux-hardware.org/?probe=92879d708d) | Feb 24, 2023 |
| HP            | ZBook 15u G3                | Notebook    | [8a698df80f](https://linux-hardware.org/?probe=8a698df80f) | Feb 24, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [f1fa3164f9](https://linux-hardware.org/?probe=f1fa3164f9) | Feb 24, 2023 |
| Gigabyte      | B85M-HD3 R4                 | Desktop     | [db83755f3f](https://linux-hardware.org/?probe=db83755f3f) | Feb 24, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [79aa51c612](https://linux-hardware.org/?probe=79aa51c612) | Feb 23, 2023 |
| Gigabyte      | Z97-HD3                     | Desktop     | [016a51a4af](https://linux-hardware.org/?probe=016a51a4af) | Feb 23, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [00591dc764](https://linux-hardware.org/?probe=00591dc764) | Feb 23, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [a85b9d1452](https://linux-hardware.org/?probe=a85b9d1452) | Feb 23, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Notebook    | [e2cdf5625c](https://linux-hardware.org/?probe=e2cdf5625c) | Feb 23, 2023 |
| Dell          | XPS 9320                    | Notebook    | [94e7c2d282](https://linux-hardware.org/?probe=94e7c2d282) | Feb 23, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Notebook    | [bfbb3aab2c](https://linux-hardware.org/?probe=bfbb3aab2c) | Feb 23, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [821d952d15](https://linux-hardware.org/?probe=821d952d15) | Feb 23, 2023 |
| ASUSTek       | 1215B                       | Notebook    | [970d77d150](https://linux-hardware.org/?probe=970d77d150) | Feb 22, 2023 |
| Notebook      | NS50_70MU                   | Notebook    | [a213ec0ba4](https://linux-hardware.org/?probe=a213ec0ba4) | Feb 22, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [b7071da133](https://linux-hardware.org/?probe=b7071da133) | Feb 22, 2023 |
| Gigabyte      | GA-MA78LMT-US2H             | Desktop     | [39e6d492c4](https://linux-hardware.org/?probe=39e6d492c4) | Feb 22, 2023 |
| Gigabyte      | GA-MA78LMT-US2H             | Desktop     | [40bc5397ea](https://linux-hardware.org/?probe=40bc5397ea) | Feb 22, 2023 |
| ASRock        | Z690 Extreme                | Desktop     | [16e67a28e4](https://linux-hardware.org/?probe=16e67a28e4) | Feb 22, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | Desktop     | [cb79c0ad47](https://linux-hardware.org/?probe=cb79c0ad47) | Feb 22, 2023 |
| ASUSTek       | P10S-I Series               | Desktop     | [f2049b8af1](https://linux-hardware.org/?probe=f2049b8af1) | Feb 21, 2023 |
| Dell          | Latitude 5491               | Notebook    | [fd68ba9595](https://linux-hardware.org/?probe=fd68ba9595) | Feb 21, 2023 |
| ASUSTek       | P10S-I Series               | Desktop     | [ec5a8efdcd](https://linux-hardware.org/?probe=ec5a8efdcd) | Feb 21, 2023 |
| Dell          | 0K6VXP A00                  | Mini pc     | [c3ddf6d592](https://linux-hardware.org/?probe=c3ddf6d592) | Feb 21, 2023 |
| Fujitsu       | LIFEBOOK E744               | Notebook    | [bdcee122d3](https://linux-hardware.org/?probe=bdcee122d3) | Feb 21, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [88be67bbc1](https://linux-hardware.org/?probe=88be67bbc1) | Feb 21, 2023 |
| Lenovo        | ThinkPad R61 8933W4S        | Notebook    | [fec1a43d91](https://linux-hardware.org/?probe=fec1a43d91) | Feb 21, 2023 |
| ASRock        | A520M-HVS                   | Desktop     | [cc8628ae2c](https://linux-hardware.org/?probe=cc8628ae2c) | Feb 20, 2023 |
| Dell          | System XPS L502X            | Notebook    | [7352f47bb0](https://linux-hardware.org/?probe=7352f47bb0) | Feb 20, 2023 |
| Lenovo        | ThinkPad T410s 2924W3S      | Notebook    | [24081de7f1](https://linux-hardware.org/?probe=24081de7f1) | Feb 20, 2023 |
| HP            | 620                         | Notebook    | [c3dae62545](https://linux-hardware.org/?probe=c3dae62545) | Feb 20, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [e61bce94ea](https://linux-hardware.org/?probe=e61bce94ea) | Feb 20, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [211cd972f0](https://linux-hardware.org/?probe=211cd972f0) | Feb 20, 2023 |
| Acer          | Aspire A515-44              | Notebook    | [5fc82de1e4](https://linux-hardware.org/?probe=5fc82de1e4) | Feb 20, 2023 |
| Dell          | 0K6VXP A00                  | Mini pc     | [a691e5fdbb](https://linux-hardware.org/?probe=a691e5fdbb) | Feb 20, 2023 |
| Fujitsu       | LIFEBOOK E559               | Notebook    | [5e4c3607c7](https://linux-hardware.org/?probe=5e4c3607c7) | Feb 20, 2023 |
| Dell          | Latitude 3190               | Notebook    | [c05229588b](https://linux-hardware.org/?probe=c05229588b) | Feb 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [0d1a7d0dbe](https://linux-hardware.org/?probe=0d1a7d0dbe) | Feb 20, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [3ddfaa902f](https://linux-hardware.org/?probe=3ddfaa902f) | Feb 20, 2023 |
| Acer          | Aspire A515-44              | Notebook    | [14e85e829f](https://linux-hardware.org/?probe=14e85e829f) | Feb 20, 2023 |
| Dell          | Latitude E7270              | Notebook    | [4eb17c846c](https://linux-hardware.org/?probe=4eb17c846c) | Feb 20, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [cc8a99e630](https://linux-hardware.org/?probe=cc8a99e630) | Feb 20, 2023 |
| Lenovo        | G510 20238                  | Notebook    | [7bc24845b3](https://linux-hardware.org/?probe=7bc24845b3) | Feb 20, 2023 |
| Dell          | 0NHNHP A01                  | Server      | [da74244bff](https://linux-hardware.org/?probe=da74244bff) | Feb 19, 2023 |
| Lenovo        | G510 20238                  | Notebook    | [d6f20de9d5](https://linux-hardware.org/?probe=d6f20de9d5) | Feb 19, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [7b0fb49186](https://linux-hardware.org/?probe=7b0fb49186) | Feb 19, 2023 |
| Dell          | Vostro 5502                 | Notebook    | [49252b4695](https://linux-hardware.org/?probe=49252b4695) | Feb 19, 2023 |
| HP            | Unknown                     | Notebook    | [69b276cb01](https://linux-hardware.org/?probe=69b276cb01) | Feb 19, 2023 |
| Gigabyte      | B75M-D2V                    | Desktop     | [fe04dfeaac](https://linux-hardware.org/?probe=fe04dfeaac) | Feb 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [5300c136fd](https://linux-hardware.org/?probe=5300c136fd) | Feb 19, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [9d2009fd11](https://linux-hardware.org/?probe=9d2009fd11) | Feb 19, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [5ff3cab69f](https://linux-hardware.org/?probe=5ff3cab69f) | Feb 19, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [5cade7cfc3](https://linux-hardware.org/?probe=5cade7cfc3) | Feb 19, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [238f636180](https://linux-hardware.org/?probe=238f636180) | Feb 18, 2023 |
| Dell          | 0PU052                      | Desktop     | [a460806b91](https://linux-hardware.org/?probe=a460806b91) | Feb 18, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [9b53b2b842](https://linux-hardware.org/?probe=9b53b2b842) | Feb 18, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [cdfcc639d3](https://linux-hardware.org/?probe=cdfcc639d3) | Feb 18, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [cbf0e3814c](https://linux-hardware.org/?probe=cbf0e3814c) | Feb 18, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [a424b3aa47](https://linux-hardware.org/?probe=a424b3aa47) | Feb 18, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | Desktop     | [28965259ad](https://linux-hardware.org/?probe=28965259ad) | Feb 18, 2023 |
| Dell          | Latitude 3520               | Notebook    | [8df8f4c6fc](https://linux-hardware.org/?probe=8df8f4c6fc) | Feb 18, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [27958da7cc](https://linux-hardware.org/?probe=27958da7cc) | Feb 18, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [2f3a14eeaa](https://linux-hardware.org/?probe=2f3a14eeaa) | Feb 18, 2023 |
| MSI           | GL65 9SD                    | Notebook    | [a702514760](https://linux-hardware.org/?probe=a702514760) | Feb 17, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [be29883368](https://linux-hardware.org/?probe=be29883368) | Feb 17, 2023 |
| Dell          | Latitude 5491               | Notebook    | [8a3298cdff](https://linux-hardware.org/?probe=8a3298cdff) | Feb 17, 2023 |
| Dell          | Latitude 5511               | Notebook    | [5c3a80271b](https://linux-hardware.org/?probe=5c3a80271b) | Feb 17, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [4a5c7432ae](https://linux-hardware.org/?probe=4a5c7432ae) | Feb 17, 2023 |
| Dell          | 03NVJ6 A02                  | Desktop     | [5201547dce](https://linux-hardware.org/?probe=5201547dce) | Feb 17, 2023 |
| Dell          | 03NVJ6 A02                  | Desktop     | [a77d2c8a54](https://linux-hardware.org/?probe=a77d2c8a54) | Feb 17, 2023 |
| Gigabyte      | GA-MA790X-UD3P              | Desktop     | [8efdbecd75](https://linux-hardware.org/?probe=8efdbecd75) | Feb 17, 2023 |
| HP            | ZBook Studio G3             | Notebook    | [af86e6cb72](https://linux-hardware.org/?probe=af86e6cb72) | Feb 17, 2023 |
| Lenovo        | ThinkPad T61 7661BM5        | Notebook    | [c829d5ed74](https://linux-hardware.org/?probe=c829d5ed74) | Feb 16, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [c96e404e3f](https://linux-hardware.org/?probe=c96e404e3f) | Feb 16, 2023 |
| ASRock        | J3355M                      | Desktop     | [9118f960dd](https://linux-hardware.org/?probe=9118f960dd) | Feb 16, 2023 |
| Acer          | One S1003                   | Tablet      | [2d5943e055](https://linux-hardware.org/?probe=2d5943e055) | Feb 16, 2023 |
| Gigabyte      | EP35-DS4                    | Desktop     | [00d960f926](https://linux-hardware.org/?probe=00d960f926) | Feb 16, 2023 |
| Lenovo        | ThinkPad L13 20R30006PB     | Notebook    | [aad1f06bb9](https://linux-hardware.org/?probe=aad1f06bb9) | Feb 16, 2023 |
| Gigabyte      | MZAPLBP-00                  | Desktop     | [b043125d6e](https://linux-hardware.org/?probe=b043125d6e) | Feb 16, 2023 |
| Gigabyte      | GA-MA790XT-UD4P             | Desktop     | [3ce39f40e7](https://linux-hardware.org/?probe=3ce39f40e7) | Feb 16, 2023 |
| MSI           | Creator Z17 A12UHST         | Notebook    | [a70040c510](https://linux-hardware.org/?probe=a70040c510) | Feb 16, 2023 |
| RTD Embedd... | CMA34CR                     | Notebook    | [dd8527bd65](https://linux-hardware.org/?probe=dd8527bd65) | Feb 16, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [73787e9141](https://linux-hardware.org/?probe=73787e9141) | Feb 16, 2023 |
| Dell          | Latitude 5480               | Notebook    | [ee1b786fd9](https://linux-hardware.org/?probe=ee1b786fd9) | Feb 15, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [09301690c5](https://linux-hardware.org/?probe=09301690c5) | Feb 15, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [5a6d751e4b](https://linux-hardware.org/?probe=5a6d751e4b) | Feb 15, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [74a61dff13](https://linux-hardware.org/?probe=74a61dff13) | Feb 15, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [b53cdde5a7](https://linux-hardware.org/?probe=b53cdde5a7) | Feb 15, 2023 |
| HP            | EliteBook 650 15.6 inch ... | Notebook    | [2be1a08ef2](https://linux-hardware.org/?probe=2be1a08ef2) | Feb 15, 2023 |
| MSI           | MS-7235                     | Desktop     | [519f3742a3](https://linux-hardware.org/?probe=519f3742a3) | Feb 15, 2023 |
| ASUSTek       | P8H67-M                     | Desktop     | [ae4f47209a](https://linux-hardware.org/?probe=ae4f47209a) | Feb 15, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [59f88fb4d0](https://linux-hardware.org/?probe=59f88fb4d0) | Feb 15, 2023 |
| ASUSTek       | P8H67-M                     | Desktop     | [f1c6e21bfb](https://linux-hardware.org/?probe=f1c6e21bfb) | Feb 15, 2023 |
| Dell          | 0GXM1W A00                  | Desktop     | [3ab6d305fc](https://linux-hardware.org/?probe=3ab6d305fc) | Feb 15, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [2c0799202c](https://linux-hardware.org/?probe=2c0799202c) | Feb 15, 2023 |
| GPU Compan... | GWTN141-4                   | Notebook    | [1492f5c475](https://linux-hardware.org/?probe=1492f5c475) | Feb 15, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [1161e39e43](https://linux-hardware.org/?probe=1161e39e43) | Feb 15, 2023 |
| Dell          | System XPS L502X            | Notebook    | [2ea016be2a](https://linux-hardware.org/?probe=2ea016be2a) | Feb 14, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [65a5587c6d](https://linux-hardware.org/?probe=65a5587c6d) | Feb 14, 2023 |
| Gigabyte      | H55M-USB3                   | Desktop     | [08b959d9ec](https://linux-hardware.org/?probe=08b959d9ec) | Feb 14, 2023 |
| Acer          | Aspire A315-35              | Notebook    | [971fa91888](https://linux-hardware.org/?probe=971fa91888) | Feb 14, 2023 |
| Google        | Lillipup                    | Notebook    | [af7451beff](https://linux-hardware.org/?probe=af7451beff) | Feb 14, 2023 |
| Unknown       | Unknown                     | Notebook    | [1f80b65b37](https://linux-hardware.org/?probe=1f80b65b37) | Feb 13, 2023 |
| Unknown       | Unknown                     | Notebook    | [8b28eb095c](https://linux-hardware.org/?probe=8b28eb095c) | Feb 13, 2023 |
| Medion        | Akoya THE TOUCH 10          | Notebook    | [ec6afad108](https://linux-hardware.org/?probe=ec6afad108) | Feb 13, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [e474459ee0](https://linux-hardware.org/?probe=e474459ee0) | Feb 13, 2023 |
| Timi          | TM1613                      | Notebook    | [ce33c5c02e](https://linux-hardware.org/?probe=ce33c5c02e) | Feb 13, 2023 |
| Lenovo        | IdeaPad S210 Touch 20257    | Notebook    | [d132553080](https://linux-hardware.org/?probe=d132553080) | Feb 13, 2023 |
| Dell          | Latitude 5511               | Notebook    | [161095d97a](https://linux-hardware.org/?probe=161095d97a) | Feb 13, 2023 |
| TrekStor      | Surfbook W2                 | Notebook    | [f43f606f80](https://linux-hardware.org/?probe=f43f606f80) | Feb 13, 2023 |
| Dell          | Latitude 3190               | Notebook    | [f2fd97186c](https://linux-hardware.org/?probe=f2fd97186c) | Feb 13, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [7eb2b7e26f](https://linux-hardware.org/?probe=7eb2b7e26f) | Feb 13, 2023 |
| HP            | 3397                        | Desktop     | [83dc4a9ea0](https://linux-hardware.org/?probe=83dc4a9ea0) | Feb 13, 2023 |
| HP            | 3397                        | Desktop     | [cc7019baaa](https://linux-hardware.org/?probe=cc7019baaa) | Feb 13, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [36a0d5221f](https://linux-hardware.org/?probe=36a0d5221f) | Feb 13, 2023 |
| Dell          | Latitude E6420              | Notebook    | [6ffa1ea310](https://linux-hardware.org/?probe=6ffa1ea310) | Feb 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [04cfa15383](https://linux-hardware.org/?probe=04cfa15383) | Feb 12, 2023 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [45f78c29cb](https://linux-hardware.org/?probe=45f78c29cb) | Feb 12, 2023 |
| Lenovo        | ThinkPad T470s 20HGS1LM0... | Notebook    | [8ee6dd00d1](https://linux-hardware.org/?probe=8ee6dd00d1) | Feb 12, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [5120a4cdb5](https://linux-hardware.org/?probe=5120a4cdb5) | Feb 12, 2023 |
| HP            | 3397                        | Desktop     | [cc5cdaf09b](https://linux-hardware.org/?probe=cc5cdaf09b) | Feb 12, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [ed3233c97b](https://linux-hardware.org/?probe=ed3233c97b) | Feb 11, 2023 |
| HP            | 3397                        | Desktop     | [b22590d882](https://linux-hardware.org/?probe=b22590d882) | Feb 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [40116058d1](https://linux-hardware.org/?probe=40116058d1) | Feb 11, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [2695a9350a](https://linux-hardware.org/?probe=2695a9350a) | Feb 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [8e00bdf032](https://linux-hardware.org/?probe=8e00bdf032) | Feb 11, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [4f99163f99](https://linux-hardware.org/?probe=4f99163f99) | Feb 11, 2023 |
| Lenovo        | ThinkPad T430 2347BS4       | Notebook    | [682be07637](https://linux-hardware.org/?probe=682be07637) | Feb 11, 2023 |
| Valve         | Jupiter                     | Notebook    | [081d9e5294](https://linux-hardware.org/?probe=081d9e5294) | Feb 11, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [d8a854baec](https://linux-hardware.org/?probe=d8a854baec) | Feb 11, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [6c1d31a394](https://linux-hardware.org/?probe=6c1d31a394) | Feb 10, 2023 |
| HP            | ProBook 430 G3              | Notebook    | [e995a466a1](https://linux-hardware.org/?probe=e995a466a1) | Feb 10, 2023 |
| Dell          | 04YJ19 A00                  | Desktop     | [972fb9a299](https://linux-hardware.org/?probe=972fb9a299) | Feb 10, 2023 |
| Toshiba       | Satellite L750              | Notebook    | [b6239c152e](https://linux-hardware.org/?probe=b6239c152e) | Feb 10, 2023 |
| Acer          | Aspire ES1-111M             | Notebook    | [82eea49fcd](https://linux-hardware.org/?probe=82eea49fcd) | Feb 09, 2023 |
| Acer          | Aspire ES1-111M             | Notebook    | [accbac47d5](https://linux-hardware.org/?probe=accbac47d5) | Feb 09, 2023 |
| Lenovo        | ThinkPad T530 2429MY2       | Notebook    | [9b5ffc7c58](https://linux-hardware.org/?probe=9b5ffc7c58) | Feb 09, 2023 |
| Dell          | 060J9C A00                  | Mini pc     | [38f4064394](https://linux-hardware.org/?probe=38f4064394) | Feb 09, 2023 |
| MSI           | Creator Z17 A12UHST         | Notebook    | [8885828bb8](https://linux-hardware.org/?probe=8885828bb8) | Feb 09, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [f669c49cf5](https://linux-hardware.org/?probe=f669c49cf5) | Feb 09, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [ddaad5aa0d](https://linux-hardware.org/?probe=ddaad5aa0d) | Feb 09, 2023 |
| Gigabyte      | B660 DS3H AX DDR4           | Desktop     | [73ae27760d](https://linux-hardware.org/?probe=73ae27760d) | Feb 09, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [467c3e9149](https://linux-hardware.org/?probe=467c3e9149) | Feb 09, 2023 |
| Intel         | DG31PR AAD97573-301         | Desktop     | [665f8e7d81](https://linux-hardware.org/?probe=665f8e7d81) | Feb 09, 2023 |
| Valve         | Jupiter                     | Notebook    | [26cb195bab](https://linux-hardware.org/?probe=26cb195bab) | Feb 08, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [c71dba27f2](https://linux-hardware.org/?probe=c71dba27f2) | Feb 08, 2023 |
| Dell          | Latitude 3570               | Notebook    | [dc460632ef](https://linux-hardware.org/?probe=dc460632ef) | Feb 08, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [2b4bc22652](https://linux-hardware.org/?probe=2b4bc22652) | Feb 08, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [842956e023](https://linux-hardware.org/?probe=842956e023) | Feb 08, 2023 |
| ASRock        | X470 Gaming K4              | Desktop     | [086ea7a0e6](https://linux-hardware.org/?probe=086ea7a0e6) | Feb 08, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [dd8fbe3d62](https://linux-hardware.org/?probe=dd8fbe3d62) | Feb 08, 2023 |
| Dell          | 0DR845                      | Desktop     | [537252420b](https://linux-hardware.org/?probe=537252420b) | Feb 07, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Poland/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 586       | 10.98%  |
| OpenMandriva 4.2   | 317       | 5.94%   |
| Ubuntu 18.04       | 280       | 5.25%   |
| Ubuntu 22.04       | 229       | 4.29%   |
| OpenMandriva 4.3   | 227       | 4.25%   |
| Debian 11          | 158       | 2.96%   |
| Arch Rolling       | 128       | 2.4%    |
| ROSA R10           | 98        | 1.84%   |
| OpenMandriva 23.01 | 88        | 1.65%   |
| Zorin 16           | 74        | 1.39%   |
| OpenMandriva 23.03 | 73        | 1.37%   |
| Manjaro            | 71        | 1.33%   |
| Linux Mint 21.1    | 71        | 1.33%   |
| ROSA R9            | 70        | 1.31%   |
| Linux Mint 20.3    | 70        | 1.31%   |
| ROSA R11           | 69        | 1.29%   |
| Arch               | 68        | 1.27%   |
| Linux Mint 20.1    | 66        | 1.24%   |
| Fedora 37          | 66        | 1.24%   |
| ROSA R11.1         | 65        | 1.22%   |
| KDE neon 20.04     | 64        | 1.2%    |
| Fedora 36          | 60        | 1.12%   |
| Ubuntu 20.10       | 57        | 1.07%   |
| Linux Mint 20.2    | 53        | 0.99%   |
| Ubuntu 21.04       | 50        | 0.94%   |
| Linux Mint 20      | 49        | 0.92%   |
| Ubuntu 19.10       | 48        | 0.9%    |
| Linux Mint 19.3    | 48        | 0.9%    |
| Pop!_OS 22.04      | 46        | 0.86%   |
| Ubuntu 22.10       | 45        | 0.84%   |
| Ubuntu 21.10       | 44        | 0.82%   |
| Fedora 35          | 43        | 0.81%   |
| ROSA R8            | 42        | 0.79%   |
| Fedora 33          | 41        | 0.77%   |
| Debian 10          | 40        | 0.75%   |
| Linux Mint 21      | 39        | 0.73%   |
| Fedora 34          | 39        | 0.73%   |
| Xubuntu 20.04      | 38        | 0.71%   |
| Fedora 32          | 38        | 0.71%   |
| Pop!_OS 20.04      | 37        | 0.69%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1341      | 27.12%  |
| OpenMandriva  | 720       | 14.56%  |
| Linux Mint    | 408       | 8.25%   |
| ROSA          | 333       | 6.74%   |
| Fedora        | 330       | 6.67%   |
| Debian        | 242       | 4.89%   |
| Manjaro       | 194       | 3.92%   |
| Arch          | 188       | 3.8%    |
| Pop!_OS       | 143       | 2.89%   |
| Zorin         | 113       | 2.29%   |
| Kubuntu       | 96        | 1.94%   |
| KDE neon      | 90        | 1.82%   |
| Xubuntu       | 78        | 1.58%   |
| Gentoo        | 46        | 0.93%   |
| Kali          | 45        | 0.91%   |
| openSUSE      | 43        | 0.87%   |
| ArcoLinux     | 40        | 0.81%   |
| Endless       | 36        | 0.73%   |
| Lubuntu       | 35        | 0.71%   |
| Elementary    | 33        | 0.67%   |
| EndeavourOS   | 30        | 0.61%   |
| LMDE          | 28        | 0.57%   |
| SteamOS       | 24        | 0.49%   |
| Ubuntu Unity  | 21        | 0.42%   |
| Clear Linux   | 21        | 0.42%   |
| BlackPanther  | 18        | 0.36%   |
| MX            | 17        | 0.34%   |
| Ubuntu MATE   | 16        | 0.32%   |
| Nobara        | 15        | 0.3%    |
| CentOS        | 14        | 0.28%   |
| Ubuntu Budgie | 13        | 0.26%   |
| Garuda Linux  | 12        | 0.24%   |
| LinuxFX       | 10        | 0.2%    |
| Peppermint    | 9         | 0.18%   |
| Raspbian      | 8         | 0.16%   |
| NixOS         | 8         | 0.16%   |
| Linux Lite    | 8         | 0.16%   |
| Xero          | 6         | 0.12%   |
| Parrot        | 6         | 0.12%   |
| EuroLinux     | 6         | 0.12%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002        | 303       | 5.09%   |
| 5.16.7-desktop-1omv4003         | 208       | 3.5%    |
| 6.1.1-desktop-1omv2290          | 79        | 1.33%   |
| 5.4.0-42-generic                | 78        | 1.31%   |
| 6.2.6-desktop-1omv2390          | 68        | 1.14%   |
| 5.15.0-56-generic               | 58        | 0.97%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 54        | 0.91%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 53        | 0.89%   |
| 5.15.0-43-generic               | 41        | 0.69%   |
| 5.4.0-26-generic                | 40        | 0.67%   |
| 5.15.0-58-generic               | 39        | 0.66%   |
| 4.15.0-desktop-45.1rosa-x86_64  | 39        | 0.66%   |
| 5.4.0-52-generic                | 38        | 0.64%   |
| 5.4.0-48-generic                | 36        | 0.6%    |
| 5.15.0-52-generic               | 36        | 0.6%    |
| 5.19.0-35-generic               | 34        | 0.57%   |
| 5.4.0-58-generic                | 33        | 0.55%   |
| 5.4.0-29-generic                | 30        | 0.5%    |
| 5.3.0-46-generic                | 30        | 0.5%    |
| 5.4.0-54-generic                | 28        | 0.47%   |
| 5.8.0-43-generic                | 27        | 0.45%   |
| 5.13.0-39-generic               | 27        | 0.45%   |
| 5.11.0-37-generic               | 27        | 0.45%   |
| 5.4.0-40-generic                | 26        | 0.44%   |
| 5.4.0-37-generic                | 25        | 0.42%   |
| 5.15.0-48-generic               | 25        | 0.42%   |
| 5.19.0-32-generic               | 24        | 0.4%    |
| 4.1.34-nrj-desktop-2rosa-x86_64 | 24        | 0.4%    |
| 5.4.0-66-generic                | 23        | 0.39%   |
| 5.4.0-33-generic                | 23        | 0.39%   |
| 5.13.0-27-generic               | 23        | 0.39%   |
| 5.3.0-42-generic                | 22        | 0.37%   |
| 5.11.0-27-generic               | 22        | 0.37%   |
| 5.0.0-37-generic                | 22        | 0.37%   |
| 5.16.13-desktop-1omv4003        | 21        | 0.35%   |
| 5.15.0-60-generic               | 21        | 0.35%   |
| 5.8.0-48-generic                | 20        | 0.34%   |
| 5.4.0-65-generic                | 20        | 0.34%   |
| 5.4.0-56-generic                | 20        | 0.34%   |
| 5.13.0-40-generic               | 20        | 0.34%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 759       | 13.54%  |
| 5.15.0  | 401       | 7.15%   |
| 5.10.14 | 305       | 5.44%   |
| 4.15.0  | 287       | 5.12%   |
| 5.11.0  | 223       | 3.98%   |
| 5.8.0   | 222       | 3.96%   |
| 5.16.7  | 211       | 3.76%   |
| 5.13.0  | 202       | 3.6%    |
| 5.3.0   | 166       | 2.96%   |
| 5.10.0  | 163       | 2.91%   |
| 5.19.0  | 145       | 2.59%   |
| 5.0.0   | 101       | 1.8%    |
| 4.18.0  | 90        | 1.61%   |
| 6.2.6   | 83        | 1.48%   |
| 6.1.1   | 80        | 1.43%   |
| 4.9.60  | 66        | 1.18%   |
| 4.9.20  | 62        | 1.11%   |
| 4.19.0  | 54        | 0.96%   |
| 6.1.0   | 35        | 0.62%   |
| 5.14.0  | 34        | 0.61%   |
| 4.1.34  | 32        | 0.57%   |
| 4.1.38  | 28        | 0.5%    |
| 6.0.0   | 26        | 0.46%   |
| 5.16.13 | 23        | 0.41%   |
| 5.17.5  | 20        | 0.36%   |
| 5.11.12 | 19        | 0.34%   |
| 5.9.0   | 18        | 0.32%   |
| 5.4.32  | 18        | 0.32%   |
| 6.2.0   | 17        | 0.3%    |
| 6.0.12  | 17        | 0.3%    |
| 4.9.76  | 16        | 0.29%   |
| 4.9.155 | 16        | 0.29%   |
| 4.9.124 | 16        | 0.29%   |
| 6.0.7   | 15        | 0.27%   |
| 5.17.0  | 15        | 0.27%   |
| 6.0.8   | 14        | 0.25%   |
| 6.1.12  | 13        | 0.23%   |
| 5.6.0   | 13        | 0.23%   |
| 5.4.83  | 13        | 0.23%   |
| 5.15.12 | 13        | 0.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 860       | 15.81%  |
| 5.10    | 582       | 10.7%   |
| 5.15    | 543       | 9.98%   |
| 5.16    | 305       | 5.61%   |
| 5.11    | 289       | 5.31%   |
| 4.15    | 287       | 5.28%   |
| 5.8     | 280       | 5.15%   |
| 5.13    | 233       | 4.28%   |
| 6.1     | 212       | 3.9%    |
| 5.19    | 203       | 3.73%   |
| 5.3     | 186       | 3.42%   |
| 4.9     | 184       | 3.38%   |
| 6.2     | 175       | 3.22%   |
| 6.0     | 131       | 2.41%   |
| 5.0     | 111       | 2.04%   |
| 4.18    | 102       | 1.88%   |
| 5.14    | 90        | 1.65%   |
| 5.17    | 79        | 1.45%   |
| 5.9     | 74        | 1.36%   |
| 5.6     | 70        | 1.29%   |
| 5.18    | 70        | 1.29%   |
| 4.19    | 67        | 1.23%   |
| 4.1     | 63        | 1.16%   |
| 5.12    | 60        | 1.1%    |
| 6.3     | 45        | 0.83%   |
| 5.5     | 39        | 0.72%   |
| 5.7     | 35        | 0.64%   |
| 4.4     | 17        | 0.31%   |
| 5.1     | 8         | 0.15%   |
| 3.10    | 7         | 0.13%   |
| 5.2     | 5         | 0.09%   |
| 4.20    | 4         | 0.07%   |
| 4.16    | 3         | 0.06%   |
| 4.13    | 3         | 0.06%   |
| 4.8     | 2         | 0.04%   |
| 4.7     | 2         | 0.04%   |
| 4.14    | 2         | 0.04%   |
| 4.12    | 2         | 0.04%   |
| 4.10    | 2         | 0.04%   |
| 3.18    | 2         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 4554      | 95.79%  |
| i686    | 150       | 3.16%   |
| aarch64 | 25        | 0.53%   |
| armv7l  | 18        | 0.38%   |
| armv8l  | 3         | 0.06%   |
| armv6l  | 2         | 0.04%   |
| ppc64   | 1         | 0.02%   |
| ppc     | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 1793      | 35.79%  |
| KDE5            | 1308      | 26.11%  |
| Unknown         | 492       | 9.82%   |
| XFCE            | 353       | 7.05%   |
| X-Cinnamon      | 279       | 5.57%   |
| KDE4            | 177       | 3.53%   |
| KDE             | 126       | 2.51%   |
| MATE            | 121       | 2.42%   |
| Cinnamon        | 68        | 1.36%   |
| LXQt            | 63        | 1.26%   |
| LXDE            | 47        | 0.94%   |
| Pantheon        | 32        | 0.64%   |
| i3              | 32        | 0.64%   |
| Unity           | 24        | 0.48%   |
| Budgie          | 21        | 0.42%   |
| Deepin          | 16        | 0.32%   |
| GNOME Flashback | 11        | 0.22%   |
| GNOME Classic   | 6         | 0.12%   |
| awesome         | 6         | 0.12%   |
| Hyprland        | 5         | 0.1%    |
| qtile           | 4         | 0.08%   |
| openbox         | 4         | 0.08%   |
| sway            | 3         | 0.06%   |
| icewm           | 3         | 0.06%   |
| fluxbox         | 3         | 0.06%   |
| DWM             | 3         | 0.06%   |
| Trinity         | 2         | 0.04%   |
| xmonad          | 1         | 0.02%   |
| stumpwm         | 1         | 0.02%   |
| ratflow         | 1         | 0.02%   |
| qt5ct           | 1         | 0.02%   |
| jwm             | 1         | 0.02%   |
| GNUstep         | 1         | 0.02%   |
| gnome-xorg      | 1         | 0.02%   |
| BunsenLabs      | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 3882      | 79.14%  |
| Wayland     | 682       | 13.9%   |
| Unknown     | 241       | 4.91%   |
| Tty         | 99        | 2.02%   |
| Unspecified | 1         | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2039      | 40.94%  |
| SDDM    | 1216      | 24.41%  |
| GDM     | 530       | 10.64%  |
| GDM3    | 417       | 8.37%   |
| LightDM | 413       | 8.29%   |
| KDM     | 187       | 3.75%   |
| TDM     | 152       | 3.05%   |
| XDM     | 11        | 0.22%   |
| SLiM    | 3         | 0.06%   |
| Ly      | 3         | 0.06%   |
| LXDM    | 3         | 0.06%   |
| SLIMSKI | 2         | 0.04%   |
| NODM    | 2         | 0.04%   |
| MDM     | 2         | 0.04%   |
| SU      | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| pl_PL       | 2670      | 53.99%  |
| en_US       | 1273      | 25.74%  |
| Unknown     | 649       | 13.12%  |
| en_GB       | 142       | 2.87%   |
| C           | 91        | 1.84%   |
| ru_RU       | 28        | 0.57%   |
| szl_PL      | 12        | 0.24%   |
| de_DE       | 11        | 0.22%   |
| uk_UA       | 9         | 0.18%   |
| en_CA       | 8         | 0.16%   |
| ru_UA       | 7         | 0.14%   |
| en_IE       | 6         | 0.12%   |
| fr_FR       | 5         | 0.1%    |
| en_AG       | 4         | 0.08%   |
| it_IT       | 3         | 0.06%   |
| en_DK       | 3         | 0.06%   |
| C.UTF8      | 3         | 0.06%   |
| POSIX       | 2         | 0.04%   |
| nl_NL       | 2         | 0.04%   |
| hu_HU       | 2         | 0.04%   |
| en_US.utf-8 | 2         | 0.04%   |
| en_IN       | 2         | 0.04%   |
| sv_SE       | 1         | 0.02%   |
| sk_SK       | 1         | 0.02%   |
| es_ES       | 1         | 0.02%   |
| es_AR       | 1         | 0.02%   |
| en_US.UTF8  | 1         | 0.02%   |
| en_SE       | 1         | 0.02%   |
| en_AU       | 1         | 0.02%   |
| el_GR       | 1         | 0.02%   |
| de_CH       | 1         | 0.02%   |
| af_ZA       | 1         | 0.02%   |
| aa_DJ       | 1         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 2658      | 54.65%  |
| EFI  | 2206      | 45.35%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 3339      | 67.63%  |
| Overlay  | 687       | 13.92%  |
| Btrfs    | 438       | 8.87%   |
| Unknown  | 299       | 6.06%   |
| Xfs      | 69        | 1.4%    |
| Zfs      | 33        | 0.67%   |
| Tmpfs    | 30        | 0.61%   |
| F2fs     | 19        | 0.38%   |
| Ext2     | 7         | 0.14%   |
| Ext3     | 6         | 0.12%   |
| Rootfs   | 3         | 0.06%   |
| Jfs      | 3         | 0.06%   |
| XXXXX    | 1         | 0.02%   |
| SquXshfs | 1         | 0.02%   |
| Bcachefs | 1         | 0.02%   |
| Aufs     | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2250      | 45.72%  |
| GPT     | 1816      | 36.9%   |
| MBR     | 855       | 17.37%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3966      | 81.32%  |
| Yes       | 911       | 18.68%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3183      | 65.52%  |
| Yes       | 1675      | 34.48%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 832       | 17.53%  |
| Dell                    | 761       | 16.04%  |
| ASUSTek Computer        | 720       | 15.17%  |
| Hewlett-Packard         | 579       | 12.2%   |
| Gigabyte Technology     | 415       | 8.75%   |
| MSI                     | 354       | 7.46%   |
| Acer                    | 202       | 4.26%   |
| ASRock                  | 167       | 3.52%   |
| Samsung Electronics     | 80        | 1.69%   |
| Toshiba                 | 79        | 1.66%   |
| Fujitsu                 | 53        | 1.12%   |
| Apple                   | 42        | 0.89%   |
| Sony                    | 37        | 0.78%   |
| Fujitsu Siemens         | 34        | 0.72%   |
| Intel                   | 31        | 0.65%   |
| HUAWEI                  | 31        | 0.65%   |
| Raspberry Pi Foundation | 23        | 0.48%   |
| Unknown                 | 22        | 0.46%   |
| Valve                   | 19        | 0.4%    |
| Google                  | 18        | 0.38%   |
| Packard Bell            | 16        | 0.34%   |
| Notebook                | 15        | 0.32%   |
| Medion                  | 15        | 0.32%   |
| Foxconn                 | 14        | 0.3%    |
| Kiano                   | 11        | 0.23%   |
| eMachines               | 11        | 0.23%   |
| Inventec                | 9         | 0.19%   |
| Timi                    | 8         | 0.17%   |
| AMI                     | 7         | 0.15%   |
| Supermicro              | 5         | 0.11%   |
| Huanan                  | 5         | 0.11%   |
| ZOTAC                   | 4         | 0.08%   |
| mPTech                  | 4         | 0.08%   |
| Kruger&Matz             | 4         | 0.08%   |
| Gateway                 | 4         | 0.08%   |
| ECS                     | 4         | 0.08%   |
| Alienware               | 4         | 0.08%   |
| Xunlong                 | 3         | 0.06%   |
| sunxi                   | 3         | 0.06%   |
| Pegatron                | 3         | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 47        | 0.99%   |
| ASUS All Series                     | 33        | 0.7%    |
| Dell Inspiron 3451                  | 31        | 0.65%   |
| Valve Jupiter                       | 19        | 0.4%    |
| Gigabyte B450M DS3H                 | 18        | 0.38%   |
| ASUS SABERTOOTH Z77                 | 18        | 0.38%   |
| MSI MS-7B86                         | 17        | 0.36%   |
| MSI MS-7817                         | 16        | 0.34%   |
| Dell Latitude E6400                 | 16        | 0.34%   |
| Dell OptiPlex 780                   | 15        | 0.32%   |
| Dell Latitude E6540                 | 14        | 0.3%    |
| MSI MS-7C02                         | 13        | 0.27%   |
| Lenovo G50-30 80G0                  | 13        | 0.27%   |
| Dell Latitude 5480                  | 12        | 0.25%   |
| HP Pavilion dv7                     | 11        | 0.23%   |
| Dell OptiPlex 7010                  | 11        | 0.23%   |
| Dell Latitude E6430                 | 11        | 0.23%   |
| Dell Latitude D630                  | 11        | 0.23%   |
| Dell Latitude 5490                  | 11        | 0.23%   |
| Gigabyte B450 AORUS ELITE           | 10        | 0.21%   |
| MSI MS-7C37                         | 9         | 0.19%   |
| MSI MS-7B79                         | 9         | 0.19%   |
| MSI MS-7721                         | 9         | 0.19%   |
| Lenovo Legion Y530-15ICH 81FV       | 9         | 0.19%   |
| Lenovo G580 20150                   | 9         | 0.19%   |
| HP 15                               | 9         | 0.19%   |
| Gigabyte B85M-D3H                   | 9         | 0.19%   |
| Dell OptiPlex 755                   | 9         | 0.19%   |
| Dell Latitude E7440                 | 9         | 0.19%   |
| Dell Latitude E6420                 | 9         | 0.19%   |
| Dell Latitude 5420                  | 9         | 0.19%   |
| ASUS X555LJ                         | 9         | 0.19%   |
| ASUS TUF Gaming X570-PLUS           | 9         | 0.19%   |
| MSI MS-7A38                         | 8         | 0.17%   |
| MSI MS-7816                         | 8         | 0.17%   |
| Lenovo G510 20238                   | 8         | 0.17%   |
| HP Pavilion Gaming Laptop 15-ec1xxx | 8         | 0.17%   |
| HP Pavilion dv6                     | 8         | 0.17%   |
| HP Notebook                         | 8         | 0.17%   |
| Gigabyte B550 AORUS ELITE V2        | 8         | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 342       | 7.21%   |
| Dell Latitude         | 314       | 6.62%   |
| Dell Inspiron         | 155       | 3.27%   |
| Lenovo IdeaPad        | 150       | 3.16%   |
| Acer Aspire           | 120       | 2.53%   |
| HP EliteBook          | 102       | 2.15%   |
| Dell OptiPlex         | 101       | 2.13%   |
| HP Pavilion           | 96        | 2.02%   |
| Dell Precision        | 67        | 1.41%   |
| HP ProBook            | 66        | 1.39%   |
| HP Compaq             | 66        | 1.39%   |
| ASUS PRIME            | 66        | 1.39%   |
| Toshiba Satellite     | 64        | 1.35%   |
| ASUS TUF              | 54        | 1.14%   |
| Lenovo Legion         | 53        | 1.12%   |
| Unknown               | 47        | 0.99%   |
| ASUS ROG              | 45        | 0.95%   |
| Dell Vostro           | 43        | 0.91%   |
| Lenovo ThinkCentre    | 40        | 0.84%   |
| ASUS VivoBook         | 37        | 0.78%   |
| HP Laptop             | 35        | 0.74%   |
| ASUS All              | 33        | 0.7%    |
| Dell XPS              | 31        | 0.65%   |
| ASUS ASUS             | 26        | 0.55%   |
| Gigabyte B450M        | 25        | 0.53%   |
| RPi Raspberry         | 23        | 0.48%   |
| Fujitsu LIFEBOOK      | 21        | 0.44%   |
| HP EliteDesk          | 20        | 0.42%   |
| ASUS SABERTOOTH       | 20        | 0.42%   |
| Valve Jupiter         | 19        | 0.4%    |
| HP 250                | 19        | 0.4%    |
| Fujitsu ESPRIMO       | 18        | 0.38%   |
| MSI MS-7B86           | 17        | 0.36%   |
| Lenovo Yoga           | 17        | 0.36%   |
| Packard Bell EasyNote | 16        | 0.34%   |
| MSI MS-7817           | 16        | 0.34%   |
| HP ZBook              | 16        | 0.34%   |
| Lenovo ThinkBook      | 15        | 0.32%   |
| Gigabyte B550         | 15        | 0.32%   |
| Acer Extensa          | 15        | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 409       | 8.62%   |
| 2018    | 403       | 8.49%   |
| 2013    | 395       | 8.32%   |
| 2019    | 379       | 7.99%   |
| 2020    | 350       | 7.38%   |
| 2011    | 346       | 7.29%   |
| 2014    | 303       | 6.39%   |
| 2017    | 278       | 5.86%   |
| 2015    | 267       | 5.63%   |
| 2008    | 259       | 5.46%   |
| 2010    | 246       | 5.18%   |
| 2021    | 236       | 4.97%   |
| 2009    | 216       | 4.55%   |
| 2016    | 212       | 4.47%   |
| 2007    | 196       | 4.13%   |
| 2022    | 109       | 2.3%    |
| 2006    | 76        | 1.6%    |
| Unknown | 39        | 0.82%   |
| 2005    | 11        | 0.23%   |
| 2023    | 8         | 0.17%   |
| 2004    | 6         | 0.13%   |
| 2001    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 2828      | 59.6%   |
| Desktop        | 1717      | 36.19%  |
| Convertible    | 54        | 1.14%   |
| System on chip | 40        | 0.84%   |
| Mini pc        | 36        | 0.76%   |
| Server         | 26        | 0.55%   |
| All in one     | 20        | 0.42%   |
| Tablet         | 18        | 0.38%   |
| Phone          | 6         | 0.13%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 4491      | 94.03%  |
| Enabled  | 285       | 5.97%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4724      | 99.56%  |
| Yes  | 21        | 0.44%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 1029      | 21.25%  |
| 4.01-8.0        | 993       | 20.5%   |
| 16.01-24.0      | 885       | 18.27%  |
| 8.01-16.0       | 881       | 18.19%  |
| 32.01-64.0      | 497       | 10.26%  |
| 1.01-2.0        | 198       | 4.09%   |
| 2.01-3.0        | 121       | 2.5%    |
| 64.01-256.0     | 108       | 2.23%   |
| 24.01-32.0      | 83        | 1.71%   |
| 0.51-1.0        | 41        | 0.85%   |
| 0.01-0.5        | 4         | 0.08%   |
| More than 256.0 | 3         | 0.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 1986      | 36.81%  |
| 2.01-3.0    | 1150      | 21.32%  |
| 4.01-8.0    | 739       | 13.7%   |
| 3.01-4.0    | 623       | 11.55%  |
| 0.51-1.0    | 488       | 9.05%   |
| 8.01-16.0   | 242       | 4.49%   |
| 0.01-0.5    | 95        | 1.76%   |
| 16.01-24.0  | 47        | 0.87%   |
| 24.01-32.0  | 13        | 0.24%   |
| Unknown     | 5         | 0.09%   |
| 32.01-64.0  | 4         | 0.07%   |
| 64.01-256.0 | 3         | 0.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2895      | 58.66%  |
| 2       | 1239      | 25.11%  |
| 3       | 423       | 8.57%   |
| 4       | 165       | 3.34%   |
| 5       | 74        | 1.5%    |
| 0       | 74        | 1.5%    |
| 6       | 31        | 0.63%   |
| 7       | 16        | 0.32%   |
| 8       | 7         | 0.14%   |
| 11      | 3         | 0.06%   |
| 9       | 3         | 0.06%   |
| 10      | 2         | 0.04%   |
| 13      | 1         | 0.02%   |
| 12      | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2727      | 56.68%  |
| Yes       | 2084      | 43.32%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4275      | 89.89%  |
| No        | 481       | 10.11%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3597      | 75.13%  |
| No        | 1191      | 24.87%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2713      | 56.22%  |
| No        | 2113      | 43.78%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Poland  | 4745      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Warsaw                 | 1075      | 20.69%  |
| Krakow                 | 377       | 7.25%   |
| Wroclaw                | 312       | 6%      |
| Poznan                 | 264       | 5.08%   |
| Gdansk                 | 169       | 3.25%   |
| Lodz                   | 159       | 3.06%   |
| Katowice               | 134       | 2.58%   |
| Lublin                 | 72        | 1.39%   |
| Gdynia                 | 63        | 1.21%   |
| Szczecin               | 57        | 1.1%    |
| Bialystok              | 48        | 0.92%   |
| Częstochowa           | 41        | 0.79%   |
| Gliwice                | 40        | 0.77%   |
| Rzeszów               | 38        | 0.73%   |
| Torun                  | 37        | 0.71%   |
| Ruda Śląska          | 33        | 0.63%   |
| Bytom                  | 33        | 0.63%   |
| Bydgoszcz              | 33        | 0.63%   |
| Płock                 | 29        | 0.56%   |
| Sosnowiec              | 26        | 0.5%    |
| Kielce                 | 25        | 0.48%   |
| Elblag                 | 25        | 0.48%   |
| Zabrze                 | 24        | 0.46%   |
| Rybnik                 | 24        | 0.46%   |
| Bielsko-Biala          | 24        | 0.46%   |
| Olsztyn                | 23        | 0.44%   |
| Strzyzow               | 21        | 0.4%    |
| Chorzów               | 21        | 0.4%    |
| Radom                  | 20        | 0.38%   |
| Opole                  | 20        | 0.38%   |
| Tarnów                | 19        | 0.37%   |
| Siemianowice Śląskie | 19        | 0.37%   |
| Tychy                  | 17        | 0.33%   |
| Debica                 | 14        | 0.27%   |
| Cieszyn                | 14        | 0.27%   |
| Zielona Góra          | 13        | 0.25%   |
| Piaseczno              | 13        | 0.25%   |
| Blizniew               | 13        | 0.25%   |
| Słupsk                | 12        | 0.23%   |
| Legnica                | 12        | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 981       | 1522   | 13.89%  |
| Samsung Electronics       | 965       | 1472   | 13.67%  |
| WDC                       | 956       | 1461   | 13.54%  |
| GOODRAM                   | 477       | 706    | 6.76%   |
| Toshiba                   | 437       | 650    | 6.19%   |
| Crucial                   | 272       | 446    | 3.85%   |
| Kingston                  | 269       | 387    | 3.81%   |
| A-DATA Technology         | 262       | 359    | 3.71%   |
| Unknown                   | 261       | 380    | 3.7%    |
| SanDisk                   | 257       | 353    | 3.64%   |
| Hitachi                   | 235       | 337    | 3.33%   |
| Intel                     | 174       | 234    | 2.46%   |
| SK hynix                  | 151       | 198    | 2.14%   |
| HGST                      | 106       | 138    | 1.5%    |
| Micron Technology         | 103       | 136    | 1.46%   |
| Patriot                   | 92        | 120    | 1.3%    |
| SPCC                      | 72        | 114    | 1.02%   |
| Plextor                   | 58        | 77     | 0.82%   |
| PNY                       | 52        | 57     | 0.74%   |
| KIOXIA                    | 50        | 56     | 0.71%   |
| XPG                       | 43        | 62     | 0.61%   |
| Phison                    | 40        | 54     | 0.57%   |
| Fujitsu                   | 40        | 44     | 0.57%   |
| Apacer                    | 37        | 60     | 0.52%   |
| China                     | 34        | 44     | 0.48%   |
| Phison Electronics        | 30        | 41     | 0.42%   |
| OCZ                       | 30        | 33     | 0.42%   |
| LITEON                    | 27        | 36     | 0.38%   |
| Silicon Motion            | 26        | 32     | 0.37%   |
| Corsair                   | 25        | 35     | 0.35%   |
| Transcend                 | 24        | 27     | 0.34%   |
| Maxtor                    | 22        | 22     | 0.31%   |
| Realtek Semiconductor     | 20        | 32     | 0.28%   |
| KIOXIA-EXCERIA            | 20        | 26     | 0.28%   |
| JMicron Technology        | 19        | 23     | 0.27%   |
| ASMT                      | 19        | 20     | 0.27%   |
| Apple                     | 19        | 23     | 0.27%   |
| Micron/Crucial Technology | 18        | 18     | 0.25%   |
| Unknown                   | 18        | 20     | 0.25%   |
| Lite-On                   | 17        | 20     | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST500LT012-1DG142 500GB                     | 65        | 0.84%   |
| Crucial CT500MX500SSD1 500GB                        | 64        | 0.83%   |
| Seagate ST1000LM035-1RK172 1TB                      | 58        | 0.75%   |
| Toshiba HDWD110 1TB                                 | 55        | 0.71%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 55        | 0.71%   |
| Samsung SSD 850 EVO 250GB                           | 53        | 0.68%   |
| GOODRAM SSD 120GB                                   | 50        | 0.65%   |
| GOODRAM SSDPR-CX400-256-G2 256GB                    | 48        | 0.62%   |
| Crucial CT1000MX500SSD1 1TB                         | 45        | 0.58%   |
| Unknown MMC Card  32GB                              | 42        | 0.54%   |
| Samsung SSD 860 EVO 500GB                           | 42        | 0.54%   |
| Seagate ST500DM002-1BD142 500GB                     | 39        | 0.5%    |
| GOODRAM SSD 240GB                                   | 37        | 0.48%   |
| Kingston SA400S37240G 240GB SSD                     | 36        | 0.47%   |
| GOODRAM SSDPR-CX400-512-G2 512GB                    | 36        | 0.47%   |
| GOODRAM SSDPR-CX400-512 512GB                       | 36        | 0.47%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 35        | 0.45%   |
| Crucial CT240BX500SSD1 240GB                        | 34        | 0.44%   |
| Unknown MMC Card  64GB                              | 33        | 0.43%   |
| Toshiba MQ01ABD100 1TB                              | 33        | 0.43%   |
| Samsung SSD 860 EVO 250GB                           | 33        | 0.43%   |
| Kingston SV300S37A120G 120GB SSD                    | 33        | 0.43%   |
| Seagate ST9500325AS 500GB                           | 32        | 0.41%   |
| Samsung NVMe SSD Drive 500GB                        | 32        | 0.41%   |
| A-DATA SU800 256GB SSD                              | 32        | 0.41%   |
| Seagate ST1000DM010-2EP102 1TB                      | 30        | 0.39%   |
| Patriot Burst 120GB SSD                             | 30        | 0.39%   |
| Seagate ST1000DM003-1ER162 1TB                      | 29        | 0.37%   |
| Samsung SSD 980 1TB                                 | 29        | 0.37%   |
| Seagate ST3500418AS 500GB                           | 28        | 0.36%   |
| Samsung NVMe SSD Drive 512GB                        | 28        | 0.36%   |
| GOODRAM SSDPR-CX400-256 256GB                       | 28        | 0.36%   |
| Seagate Expansion 1TB                               | 27        | 0.35%   |
| Samsung NVMe SSD Drive 256GB                        | 27        | 0.35%   |
| Kingston SA400S37480G 480GB SSD                     | 26        | 0.34%   |
| Intel NVMe SSD Drive 512GB                          | 26        | 0.34%   |
| HGST HTS721010A9E630 1TB                            | 26        | 0.34%   |
| GOODRAM SSDPR-CX400-128 128GB                       | 26        | 0.34%   |
| SanDisk SDSSDA240G 240GB                            | 25        | 0.32%   |
| Samsung HD502HJ 500GB                               | 25        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 977       | 1514   | 35.81%  |
| WDC                 | 797       | 1237   | 29.22%  |
| Toshiba             | 337       | 525    | 12.35%  |
| Hitachi             | 235       | 337    | 8.61%   |
| Samsung Electronics | 168       | 237    | 6.16%   |
| HGST                | 106       | 138    | 3.89%   |
| Fujitsu             | 40        | 44     | 1.47%   |
| Maxtor              | 20        | 20     | 0.73%   |
| Unknown             | 9         | 9      | 0.33%   |
| Apple               | 6         | 6      | 0.22%   |
| ASMT                | 5         | 6      | 0.18%   |
| ASMedia             | 5         | 6      | 0.18%   |
| USB3.0              | 3         | 3      | 0.11%   |
| WD MediaMax         | 2         | 3      | 0.07%   |
| SAGE                | 2         | 2      | 0.07%   |
| PHD 3.0             | 2         | 2      | 0.07%   |
| IBM/Hitachi         | 2         | 2      | 0.07%   |
| Unknown             | 2         | 2      | 0.07%   |
| Synology            | 1         | 1      | 0.04%   |
| StoreJet            | 1         | 1      | 0.04%   |
| MARVELL             | 1         | 1      | 0.04%   |
| LaCie               | 1         | 2      | 0.04%   |
| JMicron Technology  | 1         | 4      | 0.04%   |
| HPE                 | 1         | 1      | 0.04%   |
| HGST HTS            | 1         | 1      | 0.04%   |
| Hewlett-Packard     | 1         | 1      | 0.04%   |
| ExcelStor           | 1         | 1      | 0.04%   |
| ASMT109x            | 1         | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| GOODRAM             | 464       | 681    | 17.98%  |
| Samsung Electronics | 426       | 598    | 16.51%  |
| Crucial             | 263       | 435    | 10.19%  |
| A-DATA Technology   | 217       | 295    | 8.41%   |
| Kingston            | 193       | 267    | 7.48%   |
| SanDisk             | 166       | 235    | 6.43%   |
| WDC                 | 89        | 104    | 3.45%   |
| Patriot             | 83        | 111    | 3.22%   |
| SPCC                | 65        | 105    | 2.52%   |
| Intel               | 56        | 67     | 2.17%   |
| Micron Technology   | 52        | 67     | 2.02%   |
| Plextor             | 49        | 68     | 1.9%    |
| Toshiba             | 46        | 51     | 1.78%   |
| SK hynix            | 42        | 51     | 1.63%   |
| PNY                 | 39        | 43     | 1.51%   |
| Apacer              | 34        | 57     | 1.32%   |
| China               | 33        | 43     | 1.28%   |
| OCZ                 | 30        | 33     | 1.16%   |
| LITEON              | 27        | 36     | 1.05%   |
| Transcend           | 23        | 26     | 0.89%   |
| LITEONIT            | 16        | 18     | 0.62%   |
| KIOXIA-EXCERIA      | 16        | 21     | 0.62%   |
| ASMT                | 14        | 14     | 0.54%   |
| Apple               | 12        | 12     | 0.47%   |
| Corsair             | 10        | 11     | 0.39%   |
| KingSpec            | 8         | 9      | 0.31%   |
| Intenso             | 8         | 13     | 0.31%   |
| Gigabyte Technology | 6         | 7      | 0.23%   |
| Team                | 5         | 5      | 0.19%   |
| Lexar               | 5         | 5      | 0.19%   |
| BIWIN               | 5         | 5      | 0.19%   |
| Argon               | 4         | 6      | 0.16%   |
| WDC WDS2            | 3         | 3      | 0.12%   |
| POLION              | 3         | 3      | 0.12%   |
| Phison              | 3         | 3      | 0.12%   |
| 2-Power             | 3         | 3      | 0.12%   |
| Unknown             | 3         | 3      | 0.12%   |
| Union Memory        | 2         | 3      | 0.08%   |
| Ramaxel Technology  | 2         | 3      | 0.08%   |
| Netac               | 2         | 3      | 0.08%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2324      | 4107   | 37.06%  |
| SSD     | 2247      | 3581   | 35.83%  |
| NVMe    | 1374      | 2089   | 21.91%  |
| MMC     | 243       | 347    | 3.87%   |
| Unknown | 83        | 122    | 1.32%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3680      | 7508   | 66.67%  |
| NVMe | 1364      | 2071   | 24.71%  |
| MMC  | 243       | 347    | 4.4%    |
| SAS  | 233       | 320    | 4.22%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 3005      | 4952   | 64.87%  |
| 0.51-1.0   | 1205      | 1936   | 26.01%  |
| 1.01-2.0   | 237       | 379    | 5.12%   |
| 3.01-4.0   | 65        | 134    | 1.4%    |
| 2.01-3.0   | 61        | 160    | 1.32%   |
| 4.01-10.0  | 44        | 96     | 0.95%   |
| 10.01-20.0 | 15        | 31     | 0.32%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1419      | 27.52%  |
| 251-500        | 977       | 18.95%  |
| 1-20           | 631       | 12.24%  |
| 501-1000       | 598       | 11.6%   |
| 51-100         | 428       | 8.3%    |
| 1001-2000      | 346       | 6.71%   |
| 21-50          | 260       | 5.04%   |
| Unknown        | 225       | 4.36%   |
| More than 3000 | 156       | 3.03%   |
| 2001-3000      | 117       | 2.27%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2206      | 41.55%  |
| 21-50          | 781       | 14.71%  |
| 101-250        | 636       | 11.98%  |
| 51-100         | 589       | 11.09%  |
| 251-500        | 336       | 6.33%   |
| 501-1000       | 277       | 5.22%   |
| Unknown        | 225       | 4.24%   |
| 1001-2000      | 152       | 2.86%   |
| 2001-3000      | 55        | 1.04%   |
| More than 3000 | 50        | 0.94%   |
| 0              | 2         | 0.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB            | 14        | 17     | 2.02%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 10        | 12     | 1.44%   |
| Seagate ST500LT012-9WS142 500GB      | 9         | 28     | 1.3%    |
| Seagate ST500LT012-1DG142 500GB      | 8         | 11     | 1.15%   |
| Seagate ST3500418AS 500GB            | 8         | 11     | 1.15%   |
| Seagate ST500DM002-1BD142 500GB      | 7         | 7      | 1.01%   |
| SK hynix PC711 HFS512GDE9X073N 512GB | 6         | 7      | 0.86%   |
| Seagate ST1000DM003-9YN162 1TB       | 6         | 6      | 0.86%   |
| HGST HTS545050A7E680 500GB           | 6         | 6      | 0.86%   |
| Kingston SV300S37A120G 120GB SSD     | 5         | 5      | 0.72%   |
| GOODRAM SSD 120GB                    | 5         | 5      | 0.72%   |
| ASMT 2135 18TB                       | 5         | 5      | 0.72%   |
| WDC WD5000BEVT-22ZAT0 500GB          | 4         | 4      | 0.58%   |
| WDC WD10JPVX-22JC3T0 1TB             | 4         | 4      | 0.58%   |
| Toshiba MQ01ABD100 1TB               | 4         | 5      | 0.58%   |
| Seagate ST9500420AS 500GB            | 4         | 4      | 0.58%   |
| Seagate ST9320325AS 320GB            | 4         | 4      | 0.58%   |
| Seagate ST92505610AS 250GB           | 4         | 4      | 0.58%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 4         | 4      | 0.58%   |
| Seagate ST3320613AS 320GB            | 4         | 4      | 0.58%   |
| Seagate ST1000LM014-1EJ164 1TB       | 4         | 5      | 0.58%   |
| Seagate ST1000DX001-1CM162 1TB       | 4         | 7      | 0.58%   |
| Kingston SA400S37480G 480GB SSD      | 4         | 4      | 0.58%   |
| Hitachi HTS541612J9SA00 120GB        | 4         | 5      | 0.58%   |
| WDC WD3200BPVT-80ZEST0 320GB         | 3         | 3      | 0.43%   |
| Toshiba MK3265GSX 320GB              | 3         | 3      | 0.43%   |
| Toshiba MK1637GSX 160GB              | 3         | 3      | 0.43%   |
| Toshiba MK1246GSX 120GB              | 3         | 3      | 0.43%   |
| Seagate ST980811AS 80GB              | 3         | 3      | 0.43%   |
| Seagate ST9250827AS 250GB            | 3         | 3      | 0.43%   |
| Seagate ST9250410AS 250GB            | 3         | 3      | 0.43%   |
| Seagate ST9250315AS 250GB            | 3         | 3      | 0.43%   |
| Seagate ST9160821AS 160GB            | 3         | 4      | 0.43%   |
| Seagate ST3500312CS 500GB            | 3         | 3      | 0.43%   |
| Seagate ST3320418AS 320GB            | 3         | 3      | 0.43%   |
| Seagate ST3250410AS 250GB            | 3         | 3      | 0.43%   |
| Seagate ST320LT020-9YG142 320GB      | 3         | 3      | 0.43%   |
| Seagate ST31500341AS 1TB             | 3         | 4      | 0.43%   |
| Seagate ST2000DX002-2DV164 2TB       | 3         | 5      | 0.43%   |
| Seagate ST1000LM035-1RK172 1TB       | 3         | 3      | 0.43%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 194       | 260    | 29.13%  |
| WDC                   | 126       | 181    | 18.92%  |
| Hitachi               | 57        | 72     | 8.56%   |
| Samsung Electronics   | 54        | 61     | 8.11%   |
| Toshiba               | 48        | 59     | 7.21%   |
| A-DATA Technology     | 30        | 33     | 4.5%    |
| SanDisk               | 17        | 20     | 2.55%   |
| HGST                  | 17        | 18     | 2.55%   |
| SK hynix              | 14        | 15     | 2.1%    |
| Kingston              | 14        | 14     | 2.1%    |
| Fujitsu               | 9         | 11     | 1.35%   |
| GOODRAM               | 8         | 8      | 1.2%    |
| Intel                 | 7         | 7      | 1.05%   |
| LITEON                | 6         | 6      | 0.9%    |
| ASMT                  | 6         | 7      | 0.9%    |
| Micron Technology     | 5         | 5      | 0.75%   |
| Maxtor                | 5         | 5      | 0.75%   |
| Crucial               | 5         | 12     | 0.75%   |
| LITEONIT              | 4         | 4      | 0.6%    |
| China                 | 4         | 4      | 0.6%    |
| Apacer                | 4         | 7      | 0.6%    |
| SPCC                  | 3         | 3      | 0.45%   |
| Patriot               | 3         | 5      | 0.45%   |
| OCZ                   | 3         | 3      | 0.45%   |
| Hewlett-Packard       | 3         | 3      | 0.45%   |
| ASMedia               | 3         | 3      | 0.45%   |
| XPG                   | 1         | 1      | 0.15%   |
| WDC WDS2              | 1         | 1      | 0.15%   |
| WD MediaMax           | 1         | 2      | 0.15%   |
| SSSTC                 | 1         | 1      | 0.15%   |
| SAGE                  | 1         | 1      | 0.15%   |
| RENICE                | 1         | 1      | 0.15%   |
| Realtek Semiconductor | 1         | 1      | 0.15%   |
| Plextor               | 1         | 1      | 0.15%   |
| Platinet              | 1         | 1      | 0.15%   |
| Lexar                 | 1         | 1      | 0.15%   |
| Lenovo                | 1         | 1      | 0.15%   |
| KingSpec              | 1         | 1      | 0.15%   |
| KingFast              | 1         | 1      | 0.15%   |
| JMicron Technology    | 1         | 2      | 0.15%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 194       | 260    | 38.88%  |
| WDC                 | 123       | 177    | 24.65%  |
| Hitachi             | 57        | 72     | 11.42%  |
| Toshiba             | 45        | 56     | 9.02%   |
| Samsung Electronics | 40        | 46     | 8.02%   |
| HGST                | 17        | 18     | 3.41%   |
| Fujitsu             | 9         | 11     | 1.8%    |
| Maxtor              | 5         | 5      | 1%      |
| ASMedia             | 3         | 3      | 0.6%    |
| WD MediaMax         | 1         | 2      | 0.2%    |
| SAGE                | 1         | 1      | 0.2%    |
| JMicron Technology  | 1         | 2      | 0.2%    |
| Hewlett-Packard     | 1         | 1      | 0.2%    |
| ASMT                | 1         | 2      | 0.2%    |
| Unknown             | 1         | 1      | 0.2%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 465       | 657    | 73.93%  |
| SSD  | 140       | 162    | 22.26%  |
| NVMe | 24        | 27     | 3.82%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD800BEVS-75RST0 80GB         | 1         | 1      | 7.69%   |
| WDC WD3200BEVT-22ZCT0 320GB       | 1         | 1      | 7.69%   |
| WDC WD3200BEKT-75PVMT1 320GB      | 1         | 1      | 7.69%   |
| WDC WD2500BEVS-22UST0 250GB       | 1         | 1      | 7.69%   |
| WDC WD1600AAJS-75M0A0 160GB       | 1         | 1      | 7.69%   |
| Toshiba MK3265GSXN 320GB          | 1         | 1      | 7.69%   |
| Toshiba DT01ACA100 1TB            | 1         | 2      | 7.69%   |
| Seagate ST500DM002-1BC142 500GB   | 1         | 1      | 7.69%   |
| Seagate ST320LT020-9YG142 320GB   | 1         | 1      | 7.69%   |
| Seagate ST31000528AS 1TB          | 1         | 1      | 7.69%   |
| Samsung Electronics HD250HJ 250GB | 1         | 1      | 7.69%   |
| OCZ-AGIL ITY3 64GB SSD            | 1         | 1      | 7.69%   |
| HGST HTS725025A7 250GB            | 1         | 1      | 7.69%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 38.46%  |
| Seagate             | 3         | 3      | 23.08%  |
| Toshiba             | 2         | 3      | 15.38%  |
| Samsung Electronics | 1         | 1      | 7.69%   |
| OCZ-AGIL            | 1         | 1      | 7.69%   |
| HGST                | 1         | 1      | 7.69%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2425      | 5123   | 46.44%  |
| Works    | 2171      | 4263   | 41.57%  |
| Malfunc  | 613       | 846    | 11.74%  |
| Failed   | 13        | 14     | 0.25%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3285      | 55.01%  |
| AMD                              | 868       | 14.53%  |
| Samsung Electronics              | 450       | 7.54%   |
| SanDisk                          | 169       | 2.83%   |
| Phison Electronics               | 117       | 1.96%   |
| SK hynix                         | 105       | 1.76%   |
| ASMedia Technology               | 99        | 1.66%   |
| JMicron Technology               | 98        | 1.64%   |
| ADATA Technology                 | 96        | 1.61%   |
| Nvidia                           | 92        | 1.54%   |
| Kingston Technology Company      | 91        | 1.52%   |
| Toshiba America Info Systems     | 58        | 0.97%   |
| KIOXIA                           | 56        | 0.94%   |
| Micron Technology                | 52        | 0.87%   |
| Silicon Motion                   | 49        | 0.82%   |
| Marvell Technology Group         | 47        | 0.79%   |
| Realtek Semiconductor            | 33        | 0.55%   |
| Lite-On Technology               | 29        | 0.49%   |
| Micron/Crucial Technology        | 26        | 0.44%   |
| VIA Technologies                 | 22        | 0.37%   |
| LSI Logic / Symbios Logic        | 19        | 0.32%   |
| Union Memory (Shenzhen)          | 16        | 0.27%   |
| Shenzhen Longsys Electronics     | 15        | 0.25%   |
| Silicon Integrated Systems [SiS] | 11        | 0.18%   |
| Solid State Storage Technology   | 9         | 0.15%   |
| Hewlett-Packard                  | 9         | 0.15%   |
| Silicon Image                    | 8         | 0.13%   |
| Broadcom / LSI                   | 8         | 0.13%   |
| Lenovo                           | 7         | 0.12%   |
| MAXIO Technology (Hangzhou)      | 5         | 0.08%   |
| INNOGRIT                         | 3         | 0.05%   |
| Apple                            | 3         | 0.05%   |
| Yangtze Memory Technologies      | 2         | 0.03%   |
| ULi Electronics                  | 2         | 0.03%   |
| Integrated Technology Express    | 2         | 0.03%   |
| Adaptec                          | 2         | 0.03%   |
| Tekram Technology                | 1         | 0.02%   |
| Seagate Technology               | 1         | 0.02%   |
| OCZ Technology Group             | 1         | 0.02%   |
| O2 Micro                         | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 570       | 8.09%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 241       | 3.42%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 230       | 3.26%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 229       | 3.25%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 198       | 2.81%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 171       | 2.43%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 168       | 2.38%   |
| AMD 400 Series Chipset SATA Controller                                         | 162       | 2.3%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 138       | 1.96%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 122       | 1.73%   |
| Samsung NVMe SSD Controller 980                                                | 121       | 1.72%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 119       | 1.69%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 111       | 1.57%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 109       | 1.55%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 104       | 1.48%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 102       | 1.45%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 99        | 1.4%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 97        | 1.38%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 95        | 1.35%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 90        | 1.28%   |
| Intel Volume Management Device NVMe RAID Controller                            | 88        | 1.25%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 87        | 1.23%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 85        | 1.21%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 82        | 1.16%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 81        | 1.15%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 79        | 1.12%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 78        | 1.11%   |
| Intel SSD 660P Series                                                          | 74        | 1.05%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 74        | 1.05%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 71        | 1.01%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 68        | 0.96%   |
| JMicron JMB363 SATA/IDE Controller                                             | 67        | 0.95%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 62        | 0.88%   |
| Intel SATA Controller [RAID mode]                                              | 59        | 0.84%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 59        | 0.84%   |
| Phison E12 NVMe Controller                                                     | 55        | 0.78%   |
| AMD 500 Series Chipset SATA Controller                                         | 55        | 0.78%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 48        | 0.68%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 45        | 0.64%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 44        | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 3432      | 56.48%  |
| NVMe | 1381      | 22.73%  |
| IDE  | 866       | 14.25%  |
| RAID | 366       | 6.02%   |
| SAS  | 17        | 0.28%   |
| SCSI | 14        | 0.23%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 3580      | 75.45%  |
| AMD          | 1114      | 23.48%  |
| ARM          | 44        | 0.93%   |
| QUALCOMM     | 3         | 0.06%   |
| PowerMac11,2 | 1         | 0.02%   |
| PowerBook6,7 | 1         | 0.02%   |
| CentaurHauls | 1         | 0.02%   |
| AppliedMicro | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron CPU N2840 @ 2.16GHz             | 50        | 1.05%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 46        | 0.96%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 44        | 0.92%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 43        | 0.9%    |
| AMD Ryzen 5 3600 6-Core Processor             | 41        | 0.86%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 39        | 0.82%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 38        | 0.8%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 37        | 0.78%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 36        | 0.76%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 36        | 0.76%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 35        | 0.73%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 34        | 0.71%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 32        | 0.67%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 31        | 0.65%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 31        | 0.65%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 28        | 0.59%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 28        | 0.59%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 27        | 0.57%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 27        | 0.57%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 25        | 0.52%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 25        | 0.52%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 25        | 0.52%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 24        | 0.5%    |
| Intel Core i5-8300H CPU @ 2.30GHz             | 24        | 0.5%    |
| Intel Core i5-5300U CPU @ 2.30GHz             | 23        | 0.48%   |
| Intel Core i5-3570K CPU @ 3.40GHz             | 23        | 0.48%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 23        | 0.48%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 22        | 0.46%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 22        | 0.46%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 22        | 0.46%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 21        | 0.44%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 21        | 0.44%   |
| ARM Processor                                 | 21        | 0.44%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 21        | 0.44%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 21        | 0.44%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 21        | 0.44%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 20        | 0.42%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 20        | 0.42%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 20        | 0.42%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 20        | 0.42%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1153      | 24.22%  |
| Intel Core i7           | 729       | 15.32%  |
| Intel Core i3           | 335       | 7.04%   |
| Intel Core 2 Duo        | 312       | 6.55%   |
| AMD Ryzen 5             | 306       | 6.43%   |
| Other                   | 240       | 5.04%   |
| Intel Celeron           | 209       | 4.39%   |
| AMD Ryzen 7             | 194       | 4.08%   |
| Intel Pentium           | 136       | 2.86%   |
| Intel Xeon              | 121       | 2.54%   |
| Intel Atom              | 80        | 1.68%   |
| Intel Pentium Dual-Core | 72        | 1.51%   |
| Intel Core 2 Quad       | 65        | 1.37%   |
| AMD Ryzen 9             | 56        | 1.18%   |
| AMD FX                  | 48        | 1.01%   |
| Intel Core 2            | 41        | 0.86%   |
| AMD Phenom II X4        | 38        | 0.8%    |
| AMD A6                  | 38        | 0.8%    |
| AMD Ryzen 3             | 37        | 0.78%   |
| AMD A8                  | 35        | 0.74%   |
| Intel Pentium Dual      | 33        | 0.69%   |
| AMD Athlon 64 X2        | 33        | 0.69%   |
| AMD A10                 | 32        | 0.67%   |
| AMD Athlon II X2        | 28        | 0.59%   |
| AMD A4                  | 20        | 0.42%   |
| AMD Ryzen 7 PRO         | 19        | 0.4%    |
| Intel Genuine           | 18        | 0.38%   |
| AMD Athlon II X4        | 18        | 0.38%   |
| AMD E                   | 17        | 0.36%   |
| Intel Core i9           | 16        | 0.34%   |
| AMD GX                  | 13        | 0.27%   |
| AMD E1                  | 13        | 0.27%   |
| ARM BCM                 | 12        | 0.25%   |
| Intel Celeron M         | 11        | 0.23%   |
| AMD Ryzen Threadripper  | 11        | 0.23%   |
| AMD Athlon              | 11        | 0.23%   |
| AMD Ryzen 5 PRO         | 9         | 0.19%   |
| AMD Athlon X2           | 9         | 0.19%   |
| Intel Pentium M         | 8         | 0.17%   |
| Intel Pentium Gold      | 8         | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2065      | 43.26%  |
| 4       | 1621      | 33.95%  |
| 6       | 457       | 9.57%   |
| 8       | 290       | 6.07%   |
| 1       | 107       | 2.24%   |
| 12      | 75        | 1.57%   |
| Unknown | 70        | 1.47%   |
| 16      | 23        | 0.48%   |
| 3       | 23        | 0.48%   |
| 10      | 17        | 0.36%   |
| 14      | 13        | 0.27%   |
| 32      | 3         | 0.06%   |
| 24      | 2         | 0.04%   |
| 20      | 2         | 0.04%   |
| 192     | 1         | 0.02%   |
| 64      | 1         | 0.02%   |
| 48      | 1         | 0.02%   |
| 44      | 1         | 0.02%   |
| 18      | 1         | 0.02%   |
| 5       | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 4696      | 98.9%   |
| 2       | 45        | 0.95%   |
| Unknown | 6         | 0.13%   |
| 4       | 1         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2899      | 60.72%  |
| 1       | 1804      | 37.79%  |
| Unknown | 70        | 1.47%   |
| 8       | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4614      | 97.03%  |
| Unknown        | 85        | 1.79%   |
| 32-bit         | 54        | 1.14%   |
| 64-bit         | 2         | 0.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1092      | 22.1%   |
| 0x306a9    | 291       | 5.89%   |
| 0x206a7    | 283       | 5.73%   |
| 0x306c3    | 244       | 4.94%   |
| 0x1067a    | 222       | 4.49%   |
| 0x906ea    | 132       | 2.67%   |
| 0x506e3    | 115       | 2.33%   |
| 0x40651    | 106       | 2.14%   |
| 0x20655    | 92        | 1.86%   |
| 0x806ec    | 91        | 1.84%   |
| 0x30678    | 89        | 1.8%    |
| 0x6fd      | 88        | 1.78%   |
| 0x906e9    | 87        | 1.76%   |
| 0x806c1    | 83        | 1.68%   |
| 0x306d4    | 83        | 1.68%   |
| 0x406e3    | 79        | 1.6%    |
| 0x806ea    | 78        | 1.58%   |
| 0x10676    | 77        | 1.56%   |
| 0x0800820d | 67        | 1.36%   |
| 0x806e9    | 66        | 1.34%   |
| 0x010000c8 | 60        | 1.21%   |
| 0x08701021 | 58        | 1.17%   |
| 0x0a50000c | 54        | 1.09%   |
| 0x6fb      | 46        | 0.93%   |
| 0x06001119 | 42        | 0.85%   |
| 0x08108109 | 36        | 0.73%   |
| 0x20652    | 34        | 0.69%   |
| 0x08600106 | 34        | 0.69%   |
| 0x6f6      | 32        | 0.65%   |
| 0xa0652    | 31        | 0.63%   |
| 0x08108102 | 29        | 0.59%   |
| 0x806eb    | 28        | 0.57%   |
| 0x08701013 | 27        | 0.55%   |
| 0x906ed    | 26        | 0.53%   |
| 0x406c4    | 26        | 0.53%   |
| 0xa0653    | 24        | 0.49%   |
| 0x106e5    | 22        | 0.45%   |
| 0x08001138 | 22        | 0.45%   |
| 0x06000852 | 22        | 0.45%   |
| 0x706e5    | 21        | 0.42%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 661       | 13.88%  |
| Haswell          | 444       | 9.33%   |
| IvyBridge        | 362       | 7.6%    |
| Penryn           | 350       | 7.35%   |
| SandyBridge      | 347       | 7.29%   |
| Skylake          | 249       | 5.23%   |
| Core             | 228       | 4.79%   |
| Zen 2            | 214       | 4.49%   |
| Zen+             | 170       | 3.57%   |
| Westmere         | 168       | 3.53%   |
| Silvermont       | 168       | 3.53%   |
| Unknown          | 150       | 3.15%   |
| K10              | 123       | 2.58%   |
| Broadwell        | 121       | 2.54%   |
| Zen 3            | 120       | 2.52%   |
| TigerLake        | 102       | 2.14%   |
| Zen              | 90        | 1.89%   |
| Piledriver       | 85        | 1.79%   |
| CometLake        | 85        | 1.79%   |
| K8 Hammer        | 65        | 1.37%   |
| IceLake          | 50        | 1.05%   |
| Bobcat           | 45        | 0.95%   |
| Alderlake Hybrid | 44        | 0.92%   |
| Nehalem          | 39        | 0.82%   |
| Bonnell          | 34        | 0.71%   |
| P6               | 33        | 0.69%   |
| Goldmont plus    | 30        | 0.63%   |
| Jaguar           | 27        | 0.57%   |
| Excavator        | 26        | 0.55%   |
| Goldmont         | 24        | 0.5%    |
| Steamroller      | 23        | 0.48%   |
| Puma             | 20        | 0.42%   |
| NetBurst         | 19        | 0.4%    |
| K10 Llano        | 17        | 0.36%   |
| K8 & K10 hybrid  | 15        | 0.32%   |
| Bulldozer        | 12        | 0.25%   |
| Tremont          | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2672      | 47.19%  |
| Nvidia                           | 1695      | 29.94%  |
| AMD                              | 1260      | 22.25%  |
| Matrox Electronics Systems       | 15        | 0.26%   |
| ASPEED Technology                | 7         | 0.12%   |
| VIA Technologies                 | 6         | 0.11%   |
| Silicon Integrated Systems [SiS] | 6         | 0.11%   |
| S3 Graphics                      | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 277       | 4.7%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 227       | 3.85%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 131       | 2.22%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 109       | 1.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 106       | 1.8%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 105       | 1.78%   |
| Intel UHD Graphics 620                                                                   | 104       | 1.76%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 101       | 1.71%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 100       | 1.7%    |
| Intel HD Graphics 5500                                                                   | 99        | 1.68%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 94        | 1.59%   |
| AMD Renoir                                                                               | 94        | 1.59%   |
| Intel Core Processor Integrated Graphics Controller                                      | 93        | 1.58%   |
| Intel HD Graphics 530                                                                    | 92        | 1.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 90        | 1.53%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 89        | 1.51%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 84        | 1.43%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 81        | 1.37%   |
| Intel HD Graphics 620                                                                    | 80        | 1.36%   |
| Intel HD Graphics 630                                                                    | 74        | 1.26%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 72        | 1.22%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 72        | 1.22%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 63        | 1.07%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 61        | 1.03%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 54        | 0.92%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 52        | 0.88%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 45        | 0.76%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 44        | 0.75%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 42        | 0.71%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 42        | 0.71%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 42        | 0.71%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 40        | 0.68%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 40        | 0.68%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 39        | 0.66%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 37        | 0.63%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 32        | 0.54%   |
| Nvidia GT218 [GeForce 210]                                                               | 30        | 0.51%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 30        | 0.51%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 30        | 0.51%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 29        | 0.49%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1828      | 38.13%  |
| 1 x Nvidia               | 965       | 20.13%  |
| 1 x AMD                  | 926       | 19.32%  |
| Intel + Nvidia           | 628       | 13.1%   |
| Intel + AMD              | 171       | 3.57%   |
| AMD + Nvidia             | 94        | 1.96%   |
| 2 x AMD                  | 71        | 1.48%   |
| Other                    | 54        | 1.13%   |
| 1 x Matrox               | 15        | 0.31%   |
| 2 x Intel                | 14        | 0.29%   |
| 1 x VIA                  | 6         | 0.13%   |
| 1 x SiS                  | 6         | 0.13%   |
| 2 x Nvidia               | 5         | 0.1%    |
| 1 x ASPEED               | 4         | 0.08%   |
| Nvidia + ASPEED          | 3         | 0.06%   |
| 3 x AMD                  | 2         | 0.04%   |
| 1 x S3 Graphics          | 1         | 0.02%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 3795      | 78.39%  |
| Proprietary | 833       | 17.21%  |
| Unknown     | 213       | 4.4%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2510      | 50.93%  |
| 1.01-2.0   | 649       | 13.17%  |
| 0.01-0.5   | 629       | 12.76%  |
| 0.51-1.0   | 434       | 8.81%   |
| 3.01-4.0   | 330       | 6.7%    |
| 7.01-8.0   | 186       | 3.77%   |
| 5.01-6.0   | 124       | 2.52%   |
| 8.01-16.0  | 42        | 0.85%   |
| 2.01-3.0   | 17        | 0.34%   |
| 16.01-24.0 | 6         | 0.12%   |
| 4.01-5.0   | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 733       | 13.98%  |
| AU Optronics            | 608       | 11.59%  |
| LG Display              | 515       | 9.82%   |
| BOE                     | 384       | 7.32%   |
| Chimei Innolux          | 358       | 6.83%   |
| Dell                    | 317       | 6.05%   |
| Goldstar                | 290       | 5.53%   |
| Iiyama                  | 172       | 3.28%   |
| Philips                 | 170       | 3.24%   |
| Lenovo                  | 131       | 2.5%    |
| BenQ                    | 131       | 2.5%    |
| Hewlett-Packard         | 129       | 2.46%   |
| Acer                    | 124       | 2.36%   |
| Chi Mei Optoelectronics | 111       | 2.12%   |
| AOC                     | 110       | 2.1%    |
| NEC Computers           | 82        | 1.56%   |
| Eizo                    | 82        | 1.56%   |
| Ancor Communications    | 66        | 1.26%   |
| Sharp                   | 54        | 1.03%   |
| LG Philips              | 44        | 0.84%   |
| PANDA                   | 41        | 0.78%   |
| Sony                    | 37        | 0.71%   |
| Fujitsu Siemens         | 36        | 0.69%   |
| LG Electronics          | 33        | 0.63%   |
| InfoVision              | 31        | 0.59%   |
| Apple                   | 30        | 0.57%   |
| ASUSTek Computer        | 26        | 0.5%    |
| Unknown                 | 21        | 0.4%    |
| Toshiba                 | 18        | 0.34%   |
| MSI                     | 18        | 0.34%   |
| HannStar                | 17        | 0.32%   |
| Idek Iiyama             | 16        | 0.31%   |
| CPT                     | 15        | 0.29%   |
| ViewSonic               | 14        | 0.27%   |
| Valve                   | 14        | 0.27%   |
| Panasonic               | 14        | 0.27%   |
| Gateway                 | 14        | 0.27%   |
| CSO                     | 12        | 0.23%   |
| Belinea                 | 12        | 0.23%   |
| Mi                      | 10        | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0629 1366x768 309x173mm 13.9-inch                     | 31        | 0.57%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 31        | 0.57%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch     | 28        | 0.51%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 26        | 0.48%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 25        | 0.46%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 25        | 0.46%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 22        | 0.4%    |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch     | 20        | 0.37%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 19        | 0.35%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 19        | 0.35%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 18        | 0.33%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch                  | 17        | 0.31%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 17        | 0.31%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                  | 16        | 0.29%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 16        | 0.29%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 16        | 0.29%   |
| Philips 273PQPY PHLC096 1920x1080 597x336mm 27.0-inch                    | 14        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 14        | 0.26%   |
| BOE LCD Monitor BOE06FB 1920x1080 344x194mm 15.5-inch                    | 14        | 0.26%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 14        | 0.26%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 13        | 0.24%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                  | 13        | 0.24%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch             | 13        | 0.24%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 13        | 0.24%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 13        | 0.24%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 13        | 0.24%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 13        | 0.24%   |
| AOC 24B2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                       | 13        | 0.24%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 12        | 0.22%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 12        | 0.22%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 12        | 0.22%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 11        | 0.2%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 11        | 0.2%    |
| Iiyama PL2530H IVM6132 1920x1080 544x303mm 24.5-inch                     | 11        | 0.2%    |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 11        | 0.2%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 11        | 0.2%    |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 11        | 0.2%    |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 11        | 0.2%    |
| Samsung Electronics LCD Monitor SDC4852 1920x1080 344x194mm 15.5-inch    | 10        | 0.18%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 10        | 0.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2102      | 42.34%  |
| 1366x768 (WXGA)    | 853       | 17.18%  |
| 2560x1440 (QHD)    | 230       | 4.63%   |
| 1280x1024 (SXGA)   | 226       | 4.55%   |
| 3840x2160 (4K)     | 223       | 4.49%   |
| 1600x900 (HD+)     | 221       | 4.45%   |
| 1280x800 (WXGA)    | 189       | 3.81%   |
| 1680x1050 (WSXGA+) | 181       | 3.65%   |
| 1920x1200 (WUXGA)  | 173       | 3.48%   |
| 1440x900 (WXGA+)   | 142       | 2.86%   |
| 3440x1440          | 52        | 1.05%   |
| Unknown            | 50        | 1.01%   |
| 2560x1080          | 41        | 0.83%   |
| 2560x1600          | 26        | 0.52%   |
| 1024x600           | 26        | 0.52%   |
| 1360x768           | 23        | 0.46%   |
| 1024x768 (XGA)     | 21        | 0.42%   |
| 1600x1200          | 19        | 0.38%   |
| 3840x1080          | 16        | 0.32%   |
| 800x1280           | 15        | 0.3%    |
| 1920x540           | 11        | 0.22%   |
| 3840x2400          | 10        | 0.2%    |
| 2160x1440          | 10        | 0.2%    |
| 2880x1800          | 8         | 0.16%   |
| 3200x1800 (QHD+)   | 7         | 0.14%   |
| 2288x1287          | 7         | 0.14%   |
| 1280x720 (HD)      | 7         | 0.14%   |
| 2048x1152          | 5         | 0.1%    |
| 1680x945           | 4         | 0.08%   |
| 1400x1050          | 4         | 0.08%   |
| 1280x768           | 4         | 0.08%   |
| 5120x1440          | 3         | 0.06%   |
| 3840x1600          | 3         | 0.06%   |
| 3840x1200          | 3         | 0.06%   |
| 3286x1080          | 3         | 0.06%   |
| 3200x1080          | 3         | 0.06%   |
| 1280x960           | 3         | 0.06%   |
| 5760x1080          | 2         | 0.04%   |
| 4480x1440          | 2         | 0.04%   |
| 3600x1080          | 2         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1415      | 26.96%  |
| 24      | 421       | 8.02%   |
| 13      | 410       | 7.81%   |
| 14      | 370       | 7.05%   |
| 23      | 350       | 6.67%   |
| 17      | 334       | 6.36%   |
| 27      | 315       | 6%      |
| 21      | 311       | 5.93%   |
| Unknown | 258       | 4.92%   |
| 19      | 189       | 3.6%    |
| 12      | 108       | 2.06%   |
| 22      | 107       | 2.04%   |
| 34      | 86        | 1.64%   |
| 18      | 75        | 1.43%   |
| 31      | 62        | 1.18%   |
| 20      | 49        | 0.93%   |
| 11      | 47        | 0.9%    |
| 25      | 34        | 0.65%   |
| 16      | 30        | 0.57%   |
| 10      | 30        | 0.57%   |
| 84      | 29        | 0.55%   |
| 72      | 27        | 0.51%   |
| 32      | 22        | 0.42%   |
| 40      | 20        | 0.38%   |
| 54      | 15        | 0.29%   |
| 48      | 13        | 0.25%   |
| 65      | 12        | 0.23%   |
| 7       | 12        | 0.23%   |
| 46      | 10        | 0.19%   |
| 33      | 10        | 0.19%   |
| 28      | 9         | 0.17%   |
| 42      | 8         | 0.15%   |
| 43      | 7         | 0.13%   |
| 142     | 6         | 0.11%   |
| 26      | 6         | 0.11%   |
| 37      | 5         | 0.1%    |
| 3       | 5         | 0.1%    |
| 49      | 4         | 0.08%   |
| 39      | 4         | 0.08%   |
| 29      | 4         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 2068      | 40.15%  |
| 501-600        | 1034      | 20.07%  |
| 401-500        | 600       | 11.65%  |
| 351-400        | 420       | 8.15%   |
| 201-300        | 363       | 7.05%   |
| Unknown        | 258       | 5.01%   |
| 701-800        | 119       | 2.31%   |
| 601-700        | 96        | 1.86%   |
| 1001-1500      | 66        | 1.28%   |
| 1501-2000      | 56        | 1.09%   |
| 801-900        | 33        | 0.64%   |
| 1-100          | 16        | 0.31%   |
| 901-1000       | 15        | 0.29%   |
| More than 2000 | 6         | 0.12%   |
| 101-200        | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 3345      | 70.96%  |
| 16/10   | 693       | 14.7%   |
| Unknown | 228       | 4.84%   |
| 5/4     | 212       | 4.5%    |
| 21/9    | 93        | 1.97%   |
| 3/2     | 54        | 1.15%   |
| 4/3     | 51        | 1.08%   |
| 0.67    | 12        | 0.25%   |
| 6/5     | 9         | 0.19%   |
| 32/9    | 9         | 0.19%   |
| 1.00    | 6         | 0.13%   |
| 0.62    | 1         | 0.02%   |
| 0.56    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1409      | 27.09%  |
| 201-250        | 915       | 17.59%  |
| 81-90          | 623       | 11.98%  |
| 301-350        | 320       | 6.15%   |
| 151-200        | 313       | 6.02%   |
| Unknown        | 258       | 4.96%   |
| 251-300        | 215       | 4.13%   |
| 121-130        | 193       | 3.71%   |
| 351-500        | 189       | 3.63%   |
| 141-150        | 153       | 2.94%   |
| 71-80          | 150       | 2.88%   |
| More than 1000 | 112       | 2.15%   |
| 61-70          | 103       | 1.98%   |
| 501-1000       | 63        | 1.21%   |
| 51-60          | 47        | 0.9%    |
| 131-140        | 47        | 0.9%    |
| 41-50          | 30        | 0.58%   |
| 111-120        | 24        | 0.46%   |
| 91-100         | 20        | 0.38%   |
| 1-40           | 17        | 0.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1754      | 34.73%  |
| 121-160       | 1376      | 27.25%  |
| 101-120       | 1290      | 25.54%  |
| Unknown       | 258       | 5.11%   |
| 161-240       | 198       | 3.92%   |
| 1-50          | 100       | 1.98%   |
| More than 240 | 74        | 1.47%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3838      | 78.62%  |
| 2     | 724       | 14.83%  |
| 0     | 195       | 3.99%   |
| 3     | 108       | 2.21%   |
| 4     | 15        | 0.31%   |
| 6     | 1         | 0.02%   |
| 5     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 2421      | 32.98%  |
| Intel                                  | 2324      | 31.66%  |
| Qualcomm Atheros                       | 885       | 12.06%  |
| Broadcom                               | 421       | 5.73%   |
| Broadcom Limited                       | 124       | 1.69%   |
| TP-Link                                | 112       | 1.53%   |
| Marvell Technology Group               | 93        | 1.27%   |
| Huawei Technologies                    | 88        | 1.2%    |
| Dell                                   | 80        | 1.09%   |
| MediaTek                               | 73        | 0.99%   |
| Ralink                                 | 71        | 0.97%   |
| Ralink Technology                      | 69        | 0.94%   |
| Nvidia                                 | 64        | 0.87%   |
| Qualcomm Atheros Communications        | 52        | 0.71%   |
| Samsung Electronics                    | 39        | 0.53%   |
| Xiaomi                                 | 33        | 0.45%   |
| Microsoft                              | 31        | 0.42%   |
| Ericsson Business Mobile Networks      | 28        | 0.38%   |
| ASUSTek Computer                       | 27        | 0.37%   |
| Hewlett-Packard                        | 24        | 0.33%   |
| ASIX Electronics                       | 19        | 0.26%   |
| Sierra Wireless                        | 18        | 0.25%   |
| JMicron Technology                     | 17        | 0.23%   |
| Lenovo                                 | 15        | 0.2%    |
| NetGear                                | 12        | 0.16%   |
| Aquantia                               | 12        | 0.16%   |
| VIA Technologies                       | 11        | 0.15%   |
| Motorola PCS                           | 11        | 0.15%   |
| Edimax Technology                      | 11        | 0.15%   |
| Fibocom                                | 10        | 0.14%   |
| DisplayLink                            | 10        | 0.14%   |
| Silicon Integrated Systems [SiS]       | 9         | 0.12%   |
| Qualcomm                               | 9         | 0.12%   |
| D-Link                                 | 9         | 0.12%   |
| ZTE WCDMA Technologies MSM             | 7         | 0.1%    |
| Microchip Technology                   | 6         | 0.08%   |
| HTC (High Tech Computer)               | 6         | 0.08%   |
| Sony Ericsson Mobile Communications AB | 5         | 0.07%   |
| OPPO Electronics                       | 5         | 0.07%   |
| OnePlus Technology (Shenzhen)          | 5         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1748      | 20.32%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 261       | 3.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 237       | 2.75%   |
| Intel Wi-Fi 6 AX200                                               | 165       | 1.92%   |
| Intel Wireless 8265 / 8275                                        | 137       | 1.59%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 130       | 1.51%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 121       | 1.41%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 115       | 1.34%   |
| Intel Wireless 7260                                               | 112       | 1.3%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 99        | 1.15%   |
| Intel Wireless 8260                                               | 99        | 1.15%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 91        | 1.06%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 90        | 1.05%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 89        | 1.03%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 85        | 0.99%   |
| Intel Wireless 7265                                               | 79        | 0.92%   |
| Intel Wi-Fi 6 AX201                                               | 79        | 0.92%   |
| Intel I211 Gigabit Network Connection                             | 78        | 0.91%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 78        | 0.91%   |
| Realtek RTL8125 2.5GbE Controller                                 | 77        | 0.9%    |
| Intel Ethernet Connection I217-LM                                 | 75        | 0.87%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 74        | 0.86%   |
| Intel Wireless 3160                                               | 67        | 0.78%   |
| Intel Wireless 3165                                               | 61        | 0.71%   |
| Intel Ethernet Connection (2) I219-V                              | 60        | 0.7%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 58        | 0.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 55        | 0.64%   |
| Intel 82579V Gigabit Network Connection                           | 55        | 0.64%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 54        | 0.63%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 53        | 0.62%   |
| Intel 82567LM Gigabit Network Connection                          | 53        | 0.62%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 52        | 0.6%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 50        | 0.58%   |
| Broadcom BCM43142 802.11b/g/n                                     | 50        | 0.58%   |
| Intel Centrino Ultimate-N 6300                                    | 48        | 0.56%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 47        | 0.55%   |
| Intel Ethernet Connection (4) I219-LM                             | 47        | 0.55%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 47        | 0.55%   |
| Huawei E353/E3131                                                 | 47        | 0.55%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 46        | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1789      | 46.69%  |
| Qualcomm Atheros                | 672       | 17.54%  |
| Realtek Semiconductor           | 490       | 12.79%  |
| Broadcom                        | 251       | 6.55%   |
| TP-Link                         | 107       | 2.79%   |
| Ralink                          | 71        | 1.85%   |
| Ralink Technology               | 69        | 1.8%    |
| MediaTek                        | 69        | 1.8%    |
| Broadcom Limited                | 61        | 1.59%   |
| Qualcomm Atheros Communications | 52        | 1.36%   |
| Dell                            | 50        | 1.3%    |
| Microsoft                       | 30        | 0.78%   |
| ASUSTek Computer                | 27        | 0.7%    |
| Sierra Wireless                 | 18        | 0.47%   |
| Edimax Technology               | 11        | 0.29%   |
| Fibocom                         | 10        | 0.26%   |
| D-Link                          | 9         | 0.23%   |
| NetGear                         | 8         | 0.21%   |
| Qualcomm                        | 6         | 0.16%   |
| Hewlett-Packard                 | 6         | 0.16%   |
| Sagem                           | 4         | 0.1%    |
| D-Link System                   | 3         | 0.08%   |
| Belkin Components               | 3         | 0.08%   |
| ZyXEL Communications            | 2         | 0.05%   |
| ZyDAS                           | 2         | 0.05%   |
| Marvell Technology Group        | 2         | 0.05%   |
| Linksys                         | 2         | 0.05%   |
| Z-Com                           | 1         | 0.03%   |
| Wacom                           | 1         | 0.03%   |
| Sweex                           | 1         | 0.03%   |
| Realtek                         | 1         | 0.03%   |
| Ovislink                        | 1         | 0.03%   |
| IMC Networks                    | 1         | 0.03%   |
| AVM                             | 1         | 0.03%   |
| Accton Technology               | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 165       | 4.29%   |
| Intel Wireless 8265 / 8275                                              | 137       | 3.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 130       | 3.38%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 121       | 3.15%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 115       | 2.99%   |
| Intel Wireless 7260                                                     | 112       | 2.91%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 99        | 2.58%   |
| Intel Wireless 8260                                                     | 99        | 2.58%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 91        | 2.37%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 89        | 2.32%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 85        | 2.21%   |
| Intel Wireless 7265                                                     | 79        | 2.06%   |
| Intel Wi-Fi 6 AX201                                                     | 79        | 2.06%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 78        | 2.03%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 74        | 1.93%   |
| Intel Wireless 3160                                                     | 67        | 1.74%   |
| Intel Wireless 3165                                                     | 61        | 1.59%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 58        | 1.51%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 55        | 1.43%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 54        | 1.41%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 53        | 1.38%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 52        | 1.35%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 50        | 1.3%    |
| Broadcom BCM43142 802.11b/g/n                                           | 50        | 1.3%    |
| Intel Centrino Ultimate-N 6300                                          | 48        | 1.25%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 47        | 1.22%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 46        | 1.2%    |
| Intel WiFi Link 5100                                                    | 44        | 1.14%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 41        | 1.07%   |
| Qualcomm Atheros AR9271 802.11n                                         | 39        | 1.01%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 39        | 1.01%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 39        | 1.01%   |
| Intel Wireless-AC 9260                                                  | 38        | 0.99%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 36        | 0.94%   |
| Intel Centrino Advanced-N 6235                                          | 35        | 0.91%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 33        | 0.86%   |
| Intel Centrino Advanced-N 6200                                          | 33        | 0.86%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 32        | 0.83%   |
| Ralink MT7601U Wireless Adapter                                         | 31        | 0.81%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 31        | 0.81%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 2222      | 49.06%  |
| Intel                                  | 1274      | 28.13%  |
| Qualcomm Atheros                       | 309       | 6.82%   |
| Broadcom                               | 211       | 4.66%   |
| Marvell Technology Group               | 92        | 2.03%   |
| Nvidia                                 | 64        | 1.41%   |
| Broadcom Limited                       | 64        | 1.41%   |
| Huawei Technologies                    | 58        | 1.28%   |
| Xiaomi                                 | 32        | 0.71%   |
| Samsung Electronics                    | 27        | 0.6%    |
| ASIX Electronics                       | 19        | 0.42%   |
| JMicron Technology                     | 17        | 0.38%   |
| Lenovo                                 | 15        | 0.33%   |
| Aquantia                               | 12        | 0.26%   |
| VIA Technologies                       | 11        | 0.24%   |
| Motorola PCS                           | 10        | 0.22%   |
| DisplayLink                            | 10        | 0.22%   |
| Silicon Integrated Systems [SiS]       | 9         | 0.2%    |
| TP-Link                                | 6         | 0.13%   |
| Microchip Technology                   | 6         | 0.13%   |
| HTC (High Tech Computer)               | 6         | 0.13%   |
| OPPO Electronics                       | 5         | 0.11%   |
| Sony Ericsson Mobile Communications AB | 4         | 0.09%   |
| NetGear                                | 4         | 0.09%   |
| ICS Advent                             | 4         | 0.09%   |
| Hewlett-Packard                        | 4         | 0.09%   |
| Qualcomm                               | 3         | 0.07%   |
| OnePlus Technology (Shenzhen)          | 3         | 0.07%   |
| MediaTek                               | 3         | 0.07%   |
| Attansic Technology                    | 3         | 0.07%   |
| Apple                                  | 3         | 0.07%   |
| Research In Motion                     | 2         | 0.04%   |
| QLogic                                 | 2         | 0.04%   |
| Google                                 | 2         | 0.04%   |
| 3Com                                   | 2         | 0.04%   |
| QinHeng Electronics                    | 1         | 0.02%   |
| NetXen Incorporated                    | 1         | 0.02%   |
| Mellanox Technologies                  | 1         | 0.02%   |
| LG Electronics                         | 1         | 0.02%   |
| HMD Global                             | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1748      | 38.01%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 261       | 5.68%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 237       | 5.15%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 90        | 1.96%   |
| Intel I211 Gigabit Network Connection                             | 78        | 1.7%    |
| Realtek RTL8125 2.5GbE Controller                                 | 77        | 1.67%   |
| Intel Ethernet Connection I217-LM                                 | 75        | 1.63%   |
| Intel Ethernet Connection (2) I219-V                              | 60        | 1.3%    |
| Intel 82579V Gigabit Network Connection                           | 55        | 1.2%    |
| Intel 82567LM Gigabit Network Connection                          | 53        | 1.15%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 47        | 1.02%   |
| Intel Ethernet Connection (4) I219-LM                             | 47        | 1.02%   |
| Huawei E353/E3131                                                 | 47        | 1.02%   |
| Intel Ethernet Connection I218-LM                                 | 44        | 0.96%   |
| Intel 82577LM Gigabit Network Connection                          | 42        | 0.91%   |
| Intel Ethernet Connection (7) I219-V                              | 40        | 0.87%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 39        | 0.85%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 36        | 0.78%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 35        | 0.76%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 35        | 0.76%   |
| Intel Ethernet Connection (2) I219-LM                             | 35        | 0.76%   |
| Intel Ethernet Connection (7) I219-LM                             | 34        | 0.74%   |
| Intel Ethernet Connection (6) I219-V                              | 32        | 0.7%    |
| Intel Ethernet Connection (3) I218-LM                             | 31        | 0.67%   |
| Nvidia MCP61 Ethernet                                             | 30        | 0.65%   |
| Intel Ethernet Connection I219-LM                                 | 30        | 0.65%   |
| Intel Ethernet Controller I225-V                                  | 27        | 0.59%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 26        | 0.57%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 26        | 0.57%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 26        | 0.57%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 23        | 0.5%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 23        | 0.5%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 23        | 0.5%    |
| Intel Ethernet Connection (4) I219-V                              | 22        | 0.48%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 22        | 0.48%   |
| Intel Ethernet Connection (2) I218-V                              | 21        | 0.46%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 21        | 0.46%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 20        | 0.43%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 20        | 0.43%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 20        | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 4264      | 53.2%   |
| WiFi     | 3594      | 44.84%  |
| Modem    | 143       | 1.78%   |
| Unknown  | 14        | 0.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2769      | 57.23%  |
| Ethernet | 2065      | 42.68%  |
| Modem    | 3         | 0.06%   |
| Unknown  | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2797      | 58.69%  |
| 1     | 1781      | 37.37%  |
| 0     | 103       | 2.16%   |
| 3     | 60        | 1.26%   |
| 4     | 13        | 0.27%   |
| 5     | 4         | 0.08%   |
| 6     | 3         | 0.06%   |
| 17    | 1         | 0.02%   |
| 10    | 1         | 0.02%   |
| 9     | 1         | 0.02%   |
| 8     | 1         | 0.02%   |
| 7     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4451      | 92.96%  |
| Yes  | 337       | 7.04%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1254      | 45.65%  |
| Qualcomm Atheros Communications | 251       | 9.14%   |
| Realtek Semiconductor           | 184       | 6.7%    |
| Broadcom                        | 182       | 6.63%   |
| Cambridge Silicon Radio         | 174       | 6.33%   |
| IMC Networks                    | 121       | 4.4%    |
| ASUSTek Computer                | 94        | 3.42%   |
| Dell                            | 88        | 3.2%    |
| Foxconn / Hon Hai               | 76        | 2.77%   |
| Lite-On Technology              | 69        | 2.51%   |
| Hewlett-Packard                 | 61        | 2.22%   |
| Apple                           | 39        | 1.42%   |
| Toshiba                         | 30        | 1.09%   |
| Ralink                          | 20        | 0.73%   |
| Foxconn International           | 17        | 0.62%   |
| Realtek                         | 14        | 0.51%   |
| TP-Link                         | 10        | 0.36%   |
| MediaTek                        | 9         | 0.33%   |
| Alps Electric                   | 8         | 0.29%   |
| Integrated System Solution      | 7         | 0.25%   |
| Chicony Electronics             | 6         | 0.22%   |
| Taiyo Yuden                     | 5         | 0.18%   |
| Edimax Technology               | 5         | 0.18%   |
| Ralink Technology               | 3         | 0.11%   |
| Conwise Technology              | 3         | 0.11%   |
| USI                             | 2         | 0.07%   |
| Opticis                         | 2         | 0.07%   |
| Micro Star International        | 2         | 0.07%   |
| Askey Computer                  | 2         | 0.07%   |
| Unknown                         | 2         | 0.07%   |
| SINO WEALTH                     | 1         | 0.04%   |
| Marvell Semiconductor           | 1         | 0.04%   |
| Logitech                        | 1         | 0.04%   |
| Fujitsu                         | 1         | 0.04%   |
| Creative Technology             | 1         | 0.04%   |
| Belkin Components               | 1         | 0.04%   |
| AboCom Systems                  | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 545       | 19.82%  |
| Intel AX201 Bluetooth                               | 178       | 6.47%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 174       | 6.33%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 160       | 5.82%   |
| Intel AX200 Bluetooth                               | 158       | 5.75%   |
| Realtek Bluetooth Radio                             | 118       | 4.29%   |
| Qualcomm Atheros  Bluetooth Device                  | 109       | 3.96%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 60        | 2.18%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 55        | 2%      |
| IMC Networks Bluetooth Radio                        | 52        | 1.89%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 52        | 1.89%   |
| Intel Wireless-AC 3168 Bluetooth                    | 51        | 1.85%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 47        | 1.71%   |
| Broadcom BCM2045B (BDC-2.1)                         | 38        | 1.38%   |
| Realtek  Bluetooth 4.2 Adapter                      | 37        | 1.35%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 35        | 1.27%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 33        | 1.2%    |
| Dell BCM20702A0 Bluetooth Module                    | 29        | 1.05%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 26        | 0.95%   |
| IMC Networks Wireless_Device                        | 25        | 0.91%   |
| HP Broadcom 2070 Bluetooth Combo                    | 25        | 0.91%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 25        | 0.91%   |
| Dell DW375 Bluetooth Module                         | 24        | 0.87%   |
| Intel AX210 Bluetooth                               | 23        | 0.84%   |
| Intel Bluetooth Device                              | 21        | 0.76%   |
| Ralink RT3290 Bluetooth                             | 20        | 0.73%   |
| Lite-On Bluetooth Device                            | 20        | 0.73%   |
| Realtek RTL8723B Bluetooth                          | 19        | 0.69%   |
| IMC Networks Bluetooth Device                       | 19        | 0.69%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 18        | 0.65%   |
| Lite-On Atheros AR3012 Bluetooth                    | 17        | 0.62%   |
| Foxconn International BCM43142A0 Bluetooth module   | 17        | 0.62%   |
| Broadcom BCM2070 Bluetooth Device                   | 17        | 0.62%   |
| Apple Bluetooth Host Controller                     | 17        | 0.62%   |
| Realtek Bluetooth Radio                             | 14        | 0.51%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 14        | 0.51%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 14        | 0.51%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 13        | 0.47%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 13        | 0.47%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 13        | 0.47%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 3434      | 52.56%  |
| AMD                                  | 1298      | 19.87%  |
| Nvidia                               | 1157      | 17.71%  |
| C-Media Electronics                  | 94        | 1.44%   |
| Creative Labs                        | 84        | 1.29%   |
| Creative Technology                  | 48        | 0.73%   |
| Logitech                             | 27        | 0.41%   |
| Realtek Semiconductor                | 24        | 0.37%   |
| VIA Technologies                     | 21        | 0.32%   |
| JMTek                                | 21        | 0.32%   |
| Texas Instruments                    | 20        | 0.31%   |
| Plantronics                          | 17        | 0.26%   |
| Lenovo                               | 17        | 0.26%   |
| Kingston Technology                  | 15        | 0.23%   |
| SteelSeries ApS                      | 14        | 0.21%   |
| GN Netcom                            | 13        | 0.2%    |
| Generalplus Technology               | 12        | 0.18%   |
| Silicon Integrated Systems [SiS]     | 11        | 0.17%   |
| GYROCOM C&C                          | 11        | 0.17%   |
| Dell                                 | 11        | 0.17%   |
| ASUSTek Computer                     | 9         | 0.14%   |
| SAVITECH                             | 8         | 0.12%   |
| Hewlett-Packard                      | 8         | 0.12%   |
| BEHRINGER International              | 8         | 0.12%   |
| Razer USA                            | 7         | 0.11%   |
| Focusrite-Novation                   | 7         | 0.11%   |
| Samson Technologies                  | 6         | 0.09%   |
| Sony                                 | 5         | 0.08%   |
| Sennheiser Communications            | 5         | 0.08%   |
| RODE Microphones                     | 5         | 0.08%   |
| AudioQuest                           | 5         | 0.08%   |
| Valve Software                       | 4         | 0.06%   |
| Trust                                | 4         | 0.06%   |
| M-Audio                              | 4         | 0.06%   |
| AOKEO                                | 4         | 0.06%   |
| USB MICROPHONE                       | 3         | 0.05%   |
| Thesycon Systemsoftware & Consulting | 3         | 0.05%   |
| ROCCAT                               | 3         | 0.05%   |
| PreSonus Audio Electronics           | 3         | 0.05%   |
| DCMT Technology                      | 3         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 383       | 4.97%   |
| AMD Family 17h/19h HD Audio Controller                                     | 334       | 4.34%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 300       | 3.9%    |
| Intel Sunrise Point-LP HD Audio                                            | 292       | 3.79%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 246       | 3.19%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 223       | 2.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 200       | 2.6%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 190       | 2.47%   |
| Intel Cannon Lake PCH cAVS                                                 | 188       | 2.44%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 171       | 2.22%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 165       | 2.14%   |
| AMD Starship/Matisse HD Audio Controller                                   | 157       | 2.04%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 156       | 2.03%   |
| AMD FCH Azalia Controller                                                  | 150       | 1.95%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 139       | 1.8%    |
| Intel 8 Series HD Audio Controller                                         | 137       | 1.78%   |
| Intel Haswell-ULT HD Audio Controller                                      | 135       | 1.75%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 134       | 1.74%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 123       | 1.6%    |
| Nvidia GP107GL High Definition Audio Controller                            | 113       | 1.47%   |
| Intel Broadwell-U Audio Controller                                         | 113       | 1.47%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 111       | 1.44%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 110       | 1.43%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 102       | 1.32%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 102       | 1.32%   |
| Nvidia GF108 High Definition Audio Controller                              | 93        | 1.21%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 91        | 1.18%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 82        | 1.06%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 73        | 0.95%   |
| Nvidia GP106 High Definition Audio Controller                              | 72        | 0.93%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 71        | 0.92%   |
| Intel 200 Series PCH HD Audio                                              | 67        | 0.87%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 61        | 0.79%   |
| Intel CM238 HD Audio Controller                                            | 61        | 0.79%   |
| Nvidia TU116 High Definition Audio Controller                              | 60        | 0.78%   |
| Intel Comet Lake PCH-LP cAVS                                               | 56        | 0.73%   |
| Nvidia High Definition Audio Controller                                    | 55        | 0.71%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 55        | 0.71%   |
| AMD Kabini HDMI/DP Audio                                                   | 55        | 0.71%   |
| Nvidia GP104 High Definition Audio Controller                              | 54        | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 746       | 21.12%  |
| SK hynix                     | 585       | 16.56%  |
| Kingston                     | 469       | 13.28%  |
| Unknown                      | 406       | 11.49%  |
| Micron Technology            | 298       | 8.44%   |
| GOODRAM                      | 213       | 6.03%   |
| Crucial                      | 157       | 4.45%   |
| G.Skill                      | 99        | 2.8%    |
| Corsair                      | 82        | 2.32%   |
| A-DATA Technology            | 76        | 2.15%   |
| Ramaxel Technology           | 67        | 1.9%    |
| Patriot                      | 56        | 1.59%   |
| Nanya Technology             | 56        | 1.59%   |
| Elpida                       | 50        | 1.42%   |
| Unknown                      | 25        | 0.71%   |
| Wilk                         | 17        | 0.48%   |
| Unknown (ABCD)               | 16        | 0.45%   |
| Qimonda                      | 13        | 0.37%   |
| Apacer                       | 12        | 0.34%   |
| Wilk Elektronik              | 9         | 0.25%   |
| GeIL                         | 9         | 0.25%   |
| ASint Technology             | 9         | 0.25%   |
| 48spaces                     | 5         | 0.14%   |
| Unifosa                      | 4         | 0.11%   |
| Silicon Power                | 4         | 0.11%   |
| Patriot Memory (PDP Systems) | 4         | 0.11%   |
| fef5                         | 4         | 0.11%   |
| Transcend                    | 3         | 0.08%   |
| Team                         | 3         | 0.08%   |
| OCZ                          | 3         | 0.08%   |
| Toshiba                      | 2         | 0.06%   |
| SHARETRONIC                  | 2         | 0.06%   |
| PNY                          | 2         | 0.06%   |
| AMD                          | 2         | 0.06%   |
| Aeneon                       | 2         | 0.06%   |
| Unknown (8A02)               | 1         | 0.03%   |
| Unknown (768A)               | 1         | 0.03%   |
| Unknown (0x7FFF)             | 1         | 0.03%   |
| Unknown (0x0702)             | 1         | 0.03%   |
| tigo                         | 1         | 0.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s      | 39        | 1.01%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s      | 37        | 0.96%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 34        | 0.88%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s      | 30        | 0.78%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                 | 28        | 0.73%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 28        | 0.73%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s     | 28        | 0.73%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s     | 28        | 0.73%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s     | 27        | 0.7%    |
| Samsung RAM M471B5173EB0-YK0 4096MB SODIMM DDR3 1600MT/s   | 25        | 0.65%   |
| GOODRAM RAM GR2666S464L19/16G 16GB SODIMM DDR4 2667MT/s    | 25        | 0.65%   |
| Unknown                                                    | 25        | 0.65%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s      | 24        | 0.62%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s      | 23        | 0.6%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s      | 22        | 0.57%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s      | 21        | 0.54%   |
| Kingston RAM 9905403-559.A00LF 8GB DIMM DDR3 1600MT/s      | 19        | 0.49%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                     | 18        | 0.47%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s     | 17        | 0.44%   |
| GOODRAM RAM GR3200S464L22/16G 16GB SODIMM DDR4 3200MT/s    | 17        | 0.44%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3266MT/s         | 16        | 0.41%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s      | 16        | 0.41%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 800MT/s       | 15        | 0.39%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s      | 15        | 0.39%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s      | 15        | 0.39%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s     | 14        | 0.36%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s     | 14        | 0.36%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s      | 14        | 0.36%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s      | 14        | 0.36%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                    | 13        | 0.34%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                       | 13        | 0.34%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s     | 13        | 0.34%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s      | 13        | 0.34%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s      | 13        | 0.34%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s      | 13        | 0.34%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s      | 13        | 0.34%   |
| Kingston RAM KHX2400C14S4/16G 16384MB SODIMM DDR4 2667MT/s | 13        | 0.34%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s        | 13        | 0.34%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s        | 13        | 0.34%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s    | 13        | 0.34%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1181      | 39.52%  |
| DDR3    | 1107      | 37.05%  |
| DDR2    | 235       | 7.86%   |
| Unknown | 143       | 4.79%   |
| SDRAM   | 135       | 4.52%   |
| LPDDR4  | 70        | 2.34%   |
| LPDDR3  | 41        | 1.37%   |
| DDR     | 32        | 1.07%   |
| DDR5    | 26        | 0.87%   |
| LPDDR5  | 12        | 0.4%    |
| DRAM    | 6         | 0.2%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| SODIMM          | 1778      | 60.54%  |
| DIMM            | 1028      | 35%     |
| Row Of Chips    | 104       | 3.54%   |
| Chip            | 12        | 0.41%   |
| Unknown         | 11        | 0.37%   |
| RIMM            | 2         | 0.07%   |
| Proprietary Car | 1         | 0.03%   |
| FB-DIMM         | 1         | 0.03%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 8192    | 1008      | 30.71%  |
| 4096    | 929       | 28.31%  |
| 2048    | 561       | 17.09%  |
| 16384   | 447       | 13.62%  |
| 1024    | 202       | 6.15%   |
| 32768   | 98        | 2.99%   |
| 512     | 27        | 0.82%   |
| Unknown | 4         | 0.12%   |
| 1536    | 2         | 0.06%   |
| 256     | 2         | 0.06%   |
| 131072  | 1         | 0.03%   |
| 64      | 1         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 753       | 22.98%  |
| 2667    | 414       | 12.63%  |
| 3200    | 388       | 11.84%  |
| 1333    | 210       | 6.41%   |
| 2400    | 197       | 6.01%   |
| 1334    | 141       | 4.3%    |
| 2133    | 129       | 3.94%   |
| 667     | 129       | 3.94%   |
| 800     | 122       | 3.72%   |
| Unknown | 80        | 2.44%   |
| 3600    | 78        | 2.38%   |
| 1067    | 55        | 1.68%   |
| 4199    | 43        | 1.31%   |
| 1867    | 40        | 1.22%   |
| 533     | 32        | 0.98%   |
| 3266    | 31        | 0.95%   |
| 2048    | 28        | 0.85%   |
| 1066    | 28        | 0.85%   |
| 975     | 26        | 0.79%   |
| 3000    | 25        | 0.76%   |
| 4800    | 22        | 0.67%   |
| 4267    | 20        | 0.61%   |
| 1800    | 20        | 0.61%   |
| 400     | 20        | 0.61%   |
| 1866    | 19        | 0.58%   |
| 3400    | 18        | 0.55%   |
| 3866    | 15        | 0.46%   |
| 2933    | 15        | 0.46%   |
| 3733    | 14        | 0.43%   |
| 6400    | 13        | 0.4%    |
| 2666    | 13        | 0.4%    |
| 8400    | 11        | 0.34%   |
| 3533    | 10        | 0.31%   |
| 333     | 10        | 0.31%   |
| 3800    | 9         | 0.27%   |
| 3333    | 9         | 0.27%   |
| 4266    | 7         | 0.21%   |
| 3933    | 7         | 0.21%   |
| 2866    | 7         | 0.21%   |
| 3466    | 6         | 0.18%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 49        | 45.37%  |
| Samsung Electronics   | 15        | 13.89%  |
| Brother Industries    | 12        | 11.11%  |
| Canon                 | 10        | 9.26%   |
| Seiko Epson           | 7         | 6.48%   |
| Prolific Technology   | 5         | 4.63%   |
| Zebra                 | 3         | 2.78%   |
| Xerox                 | 2         | 1.85%   |
| Lexmark International | 2         | 1.85%   |
| Minolta               | 1         | 0.93%   |
| MIIIW                 | 1         | 0.93%   |
| Datamax-O'Neil        | 1         | 0.93%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port           | 5         | 4.55%   |
| HP LaserJet 1020                        | 5         | 4.55%   |
| Samsung M2020 Series                    | 3         | 2.73%   |
| HP LaserJet P2015 series                | 3         | 2.73%   |
| Canon iP7200 series                     | 3         | 2.73%   |
| Seiko Epson AL-M310DN                   | 2         | 1.82%   |
| Samsung SCX-3400 Series                 | 2         | 1.82%   |
| Samsung ML-216x Series Laser Printer    | 2         | 1.82%   |
| Samsung ML-2010P Mono Laser Printer     | 2         | 1.82%   |
| HP LaserJet P1102                       | 2         | 1.82%   |
| HP LaserJet M14-M17                     | 2         | 1.82%   |
| HP Deskjet F4500 series                 | 2         | 1.82%   |
| HP DeskJet F4100 Printer series         | 2         | 1.82%   |
| HP Deskjet F2280 series                 | 2         | 1.82%   |
| HP DeskJet 845c                         | 2         | 1.82%   |
| HP DeskJet 840c                         | 2         | 1.82%   |
| HP DeskJet 3700 series                  | 2         | 1.82%   |
| HP DeskJet 2620 All-in-One Printer      | 2         | 1.82%   |
| HP Deskjet 2540 series                  | 2         | 1.82%   |
| HP Deskjet 1050 J410                    | 2         | 1.82%   |
| Canon MG5600 series                     | 2         | 1.82%   |
| Canon LiDE 400                          | 2         | 1.82%   |
| Brother DCP-J105                        | 2         | 1.82%   |
| Brother DCP-1610W                       | 2         | 1.82%   |
| Zebra ZTC GX420t                        | 1         | 0.91%   |
| Zebra LP2844 Printer                    | 1         | 0.91%   |
| Zebra LP2824                            | 1         | 0.91%   |
| Xerox WorkCentre PE16                   | 1         | 0.91%   |
| Xerox Phaser 6000B                      | 1         | 0.91%   |
| Seiko Epson Stylus NX230/SX235W Series  | 1         | 0.91%   |
| Seiko Epson L405 Series                 | 1         | 0.91%   |
| Seiko Epson L396 Series                 | 1         | 0.91%   |
| Seiko Epson L1110 Series                | 1         | 0.91%   |
| Seiko Epson ET-2710 Series              | 1         | 0.91%   |
| Samsung Xerox Phaser 3117 Laser Printer | 1         | 0.91%   |
| Samsung SCX-6545 Series                 | 1         | 0.91%   |
| Samsung SCX-4300 Series                 | 1         | 0.91%   |
| Samsung SCX-4200 series                 | 1         | 0.91%   |
| Samsung ML-3050/ML-3051 Laser Printer   | 1         | 0.91%   |
| Samsung ML-2540 Series Laser Printer    | 1         | 0.91%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Canon                       | 13        | 65%     |
| Seiko Epson                 | 2         | 10%     |
| Plustek                     | 2         | 10%     |
| Ultima Electronics          | 1         | 5%      |
| Microtek International      | 1         | 5%      |
| Acer Peripherals (now BenQ) | 1         | 5%      |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 210                                  | 5         | 25%     |
| Canon CanoScan N670U/N676U/LiDE 20                       | 2         | 10%     |
| Canon CanoScan LiDE 120                                  | 2         | 10%     |
| Canon CanoScan LiDE 110                                  | 2         | 10%     |
| Ultima Artec E+ 48U                                      | 1         | 5%      |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]      | 1         | 5%      |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1         | 5%      |
| Plustek OpticSlim 1200 Scanner                           | 1         | 5%      |
| Plustek OpticPro 1248U Scanner #2                        | 1         | 5%      |
| Microtek International USB1200 Scanner                   | 1         | 5%      |
| Canon CanoScan N1240U/LiDE 30                            | 1         | 5%      |
| Canon CanoScan LIDE 25                                   | 1         | 5%      |
| Acer Peripherals (now BenQ) S2W 3300U/4300U              | 1         | 5%      |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 608       | 22.15%  |
| Microdia                               | 268       | 9.76%   |
| IMC Networks                           | 262       | 9.54%   |
| Realtek Semiconductor                  | 235       | 8.56%   |
| Sunplus Innovation Technology          | 138       | 5.03%   |
| Quanta                                 | 125       | 4.55%   |
| Bison Electronics                      | 118       | 4.3%    |
| Suyin                                  | 115       | 4.19%   |
| Logitech                               | 107       | 3.9%    |
| Acer                                   | 92        | 3.35%   |
| Cheng Uei Precision Industry (Foxlink) | 89        | 3.24%   |
| Syntek                                 | 81        | 2.95%   |
| Lite-On Technology                     | 61        | 2.22%   |
| Silicon Motion                         | 56        | 2.04%   |
| Apple                                  | 39        | 1.42%   |
| Creative Technology                    | 34        | 1.24%   |
| Ricoh                                  | 30        | 1.09%   |
| Alcor Micro                            | 29        | 1.06%   |
| Luxvisions Innotech Limited            | 27        | 0.98%   |
| Lenovo                                 | 26        | 0.95%   |
| Z-Star Microelectronics                | 23        | 0.84%   |
| Samsung Electronics                    | 21        | 0.77%   |
| Microsoft                              | 20        | 0.73%   |
| DigiTech                               | 11        | 0.4%    |
| Sonix Technology                       | 10        | 0.36%   |
| Primax Electronics                     | 9         | 0.33%   |
| Intel                                  | 9         | 0.33%   |
| Generalplus Technology                 | 9         | 0.33%   |
| ALi                                    | 9         | 0.33%   |
| Cubeternet                             | 8         | 0.29%   |
| Hewlett-Packard                        | 7         | 0.26%   |
| Jieli Technology                       | 5         | 0.18%   |
| Importek                               | 5         | 0.18%   |
| Sunplus Technology                     | 4         | 0.15%   |
| Razer USA                              | 4         | 0.15%   |
| LG Electronics                         | 4         | 0.15%   |
| GEMBIRD                                | 4         | 0.15%   |
| Aveo Technology                        | 4         | 0.15%   |
| Xiongmai                               | 3         | 0.11%   |
| Trust                                  | 3         | 0.11%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 116       | 4.21%   |
| Microdia Integrated_Webcam_HD            | 85        | 3.09%   |
| Realtek Integrated_Webcam_HD             | 75        | 2.72%   |
| IMC Networks Integrated Camera           | 72        | 2.61%   |
| IMC Networks USB2.0 HD UVC WebCam        | 65        | 2.36%   |
| Sunplus Integrated_Webcam_HD             | 55        | 2%      |
| Chicony Lenovo EasyCamera                | 46        | 1.67%   |
| Chicony HD WebCam                        | 42        | 1.53%   |
| Microdia Integrated Webcam               | 39        | 1.42%   |
| Suyin Integrated_Webcam_HD               | 36        | 1.31%   |
| Syntek Integrated Camera                 | 31        | 1.13%   |
| Acer Lenovo EasyCamera                   | 31        | 1.13%   |
| Syntek Lenovo EasyCamera                 | 30        | 1.09%   |
| Realtek Lenovo EasyCamera                | 29        | 1.05%   |
| Quanta HP TrueVision HD Camera           | 27        | 0.98%   |
| Bison Integrated Camera                  | 27        | 0.98%   |
| Lite-On Integrated Camera                | 25        | 0.91%   |
| Logitech Webcam C270                     | 24        | 0.87%   |
| Realtek USB Camera                       | 23        | 0.84%   |
| Chicony USB2.0 HD UVC WebCam             | 23        | 0.84%   |
| Chicony HP HD Camera                     | 23        | 0.84%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 21        | 0.76%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 20        | 0.73%   |
| Samsung Galaxy A5 (MTP)                  | 19        | 0.69%   |
| Realtek Integrated Webcam HD             | 19        | 0.69%   |
| Quanta HD User Facing                    | 19        | 0.69%   |
| Bison SunplusIT Integrated Camera        | 19        | 0.69%   |
| Realtek Integrated Webcam                | 18        | 0.65%   |
| Creative Live! Cam Sync HD [VF0770]      | 18        | 0.65%   |
| Acer Integrated Camera                   | 18        | 0.65%   |
| Microdia Laptop_Integrated_Webcam_HD     | 17        | 0.62%   |
| IMC Networks Integrated Webcam           | 17        | 0.62%   |
| Chicony USB 2.0 Camera                   | 17        | 0.62%   |
| Chicony Integrated Camera (1280x720@30)  | 16        | 0.58%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X          | 16        | 0.58%   |
| Acer Lenovo Integrated Webcam            | 16        | 0.58%   |
| Lite-On HP HD Camera                     | 15        | 0.54%   |
| Chicony USB2.0 VGA UVC WebCam            | 15        | 0.54%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 15        | 0.54%   |
| Bison Lenovo EasyCamera                  | 15        | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 196       | 36.57%  |
| Synaptics                          | 130       | 24.25%  |
| Shenzhen Goodix Technology         | 66        | 12.31%  |
| AuthenTec                          | 60        | 11.19%  |
| Upek                               | 36        | 6.72%   |
| Elan Microelectronics              | 18        | 3.36%   |
| LighTuning Technology              | 15        | 2.8%    |
| STMicroelectronics                 | 14        | 2.61%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.19%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 41        | 7.65%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 40        | 7.46%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 35        | 6.53%   |
| Shenzhen Goodix  FingerPrint Device                                        | 35        | 6.53%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 27        | 5.04%   |
| Shenzhen Goodix Fingerprint Reader                                         | 25        | 4.66%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 23        | 4.29%   |
| AuthenTec AES2810                                                          | 23        | 4.29%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 22        | 4.1%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 18        | 3.36%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 14        | 2.61%   |
| STMicroelectronics Fingerprint Reader                                      | 14        | 2.61%   |
| Validity Sensors VFS491                                                    | 13        | 2.43%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 13        | 2.43%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 13        | 2.43%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 12        | 2.24%   |
| Elan ELAN:Fingerprint                                                      | 12        | 2.24%   |
| Validity Sensors Synaptics WBDI                                            | 10        | 1.87%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 10        | 1.87%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 9         | 1.68%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 9         | 1.68%   |
| Validity Sensors Fingerprint scanner                                       | 9         | 1.68%   |
| Synaptics  WBDI                                                            | 9         | 1.68%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 9         | 1.68%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 1.31%   |
| AuthenTec AES1600                                                          | 7         | 1.31%   |
| Shenzhen Goodix FingerPrint                                                | 6         | 1.12%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 6         | 1.12%   |
| Validity Sensors VFS Fingerprint sensor                                    | 5         | 0.93%   |
| Synaptics WBDI                                                             | 5         | 0.93%   |
| Synaptics UWP WBDI                                                         | 5         | 0.93%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 5         | 0.93%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 0.93%   |
| Elan ELAN:ARM-M4                                                           | 5         | 0.93%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 0.75%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 0.75%   |
| LighTuning Fingerprint Reader                                              | 4         | 0.75%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 4         | 0.75%   |
| Synaptics WBDI Device                                                      | 3         | 0.56%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.37%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 227       | 55.64%  |
| Alcor Micro               | 79        | 19.36%  |
| O2 Micro                  | 45        | 11.03%  |
| Upek                      | 21        | 5.15%   |
| Lenovo                    | 20        | 4.9%    |
| Gemalto (was Gemplus)     | 5         | 1.23%   |
| Advanced Card Systems     | 3         | 0.74%   |
| OmniKey                   | 2         | 0.49%   |
| Clay Logic                | 2         | 0.49%   |
| SCM Microsystems          | 1         | 0.25%   |
| Reiner SCT Kartensysteme  | 1         | 0.25%   |
| Cherry                    | 1         | 0.25%   |
| Aladdin Knowledge Systems | 1         | 0.25%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 76        | 18.63%  |
| Broadcom BCM5880 Secure Applications Processor                               | 69        | 16.91%  |
| Broadcom 58200                                                               | 59        | 14.46%  |
| Broadcom 5880                                                                | 57        | 13.97%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 41        | 10.05%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 38        | 9.31%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 21        | 5.15%   |
| Lenovo Integrated Smart Card Reader                                          | 20        | 4.9%    |
| O2 Micro Oz776 SmartCard Reader                                              | 7         | 1.72%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 0.74%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 0.49%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 2         | 0.49%   |
| Clay Logic Nitrokey Pro                                                      | 2         | 0.49%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 0.49%   |
| Advanced Card Systems ACR39U                                                 | 2         | 0.49%   |
| SCM Microsystems SCR333 SmartCard Reader                                     | 1         | 0.25%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.25%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.25%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.25%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.25%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.25%   |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 1         | 0.25%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 3319      | 68.04%  |
| 1     | 1235      | 25.32%  |
| 2     | 271       | 5.56%   |
| 3     | 40        | 0.82%   |
| 4     | 6         | 0.12%   |
| 7     | 3         | 0.06%   |
| 6     | 2         | 0.04%   |
| 5     | 2         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 531       | 28.32%  |
| Graphics card            | 427       | 22.77%  |
| Chipcard                 | 364       | 19.41%  |
| Net/wireless             | 164       | 8.75%   |
| Multimedia controller    | 65        | 3.47%   |
| Communication controller | 52        | 2.77%   |
| Bluetooth                | 52        | 2.77%   |
| Storage                  | 50        | 2.67%   |
| Camera                   | 41        | 2.19%   |
| Unassigned class         | 29        | 1.55%   |
| Sound                    | 23        | 1.23%   |
| Card reader              | 19        | 1.01%   |
| Net/ethernet             | 10        | 0.53%   |
| Modem                    | 10        | 0.53%   |
| Network                  | 8         | 0.43%   |
| Firewire controller      | 8         | 0.43%   |
| Dvb card                 | 6         | 0.32%   |
| Storage/ide              | 5         | 0.27%   |
| Storage/raid             | 4         | 0.21%   |
| Flash memory             | 4         | 0.21%   |
| Wireless                 | 1         | 0.05%   |
| Unclassified device      | 1         | 0.05%   |
| Tv card                  | 1         | 0.05%   |

