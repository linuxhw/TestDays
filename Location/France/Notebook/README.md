Linux in France - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in France.

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

Total: 7238

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad X240 20AMS5XY00    | [3b98c592e0](https://linux-hardware.org/?probe=3b98c592e0) | Jun 10, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [c768cfa03d](https://linux-hardware.org/?probe=c768cfa03d) | Jun 10, 2023 |
| Lenovo        | ThinkPad T550 20CJS1XB00    | [3d3375df75](https://linux-hardware.org/?probe=3d3375df75) | Jun 10, 2023 |
| Dell          | XPS 13 9370                 | [c605e51eca](https://linux-hardware.org/?probe=c605e51eca) | Jun 09, 2023 |
| Dell          | XPS 9320                    | [c9f26e18c2](https://linux-hardware.org/?probe=c9f26e18c2) | Jun 09, 2023 |
| Dell          | Precision 3551              | [0e484bd6a5](https://linux-hardware.org/?probe=0e484bd6a5) | Jun 08, 2023 |
| Dell          | Precision 5510              | [24317d94ff](https://linux-hardware.org/?probe=24317d94ff) | Jun 08, 2023 |
| HP            | EliteBook 840 G3            | [cd3bb98a1e](https://linux-hardware.org/?probe=cd3bb98a1e) | Jun 08, 2023 |
| HUAWEI        | MACHD-WXX9                  | [f87fe0fe34](https://linux-hardware.org/?probe=f87fe0fe34) | Jun 08, 2023 |
| MSI           | CreatorPro X17 A12UKS       | [ee827c186c](https://linux-hardware.org/?probe=ee827c186c) | Jun 07, 2023 |
| Dell          | Latitude 5530               | [1e3452635f](https://linux-hardware.org/?probe=1e3452635f) | Jun 07, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [53341e2d0d](https://linux-hardware.org/?probe=53341e2d0d) | Jun 07, 2023 |
| HP            | Pavilion g7                 | [f8cccf0fec](https://linux-hardware.org/?probe=f8cccf0fec) | Jun 06, 2023 |
| Dell          | Latitude 5530               | [44aa9db289](https://linux-hardware.org/?probe=44aa9db289) | Jun 06, 2023 |
| MSI           | Crosshair 15 C12VF          | [6cd11169d0](https://linux-hardware.org/?probe=6cd11169d0) | Jun 05, 2023 |
| HP            | ENVY Laptop 13-ba0xxx       | [22143d333a](https://linux-hardware.org/?probe=22143d333a) | Jun 05, 2023 |
| Acer          | Aspire ES1-711              | [5534470ef5](https://linux-hardware.org/?probe=5534470ef5) | Jun 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [a06e6ab7ad](https://linux-hardware.org/?probe=a06e6ab7ad) | Jun 05, 2023 |
| ASUSTek       | G750JM                      | [cdb3539c93](https://linux-hardware.org/?probe=cdb3539c93) | Jun 05, 2023 |
| ASUSTek       | K95VJ                       | [9bbcec82c6](https://linux-hardware.org/?probe=9bbcec82c6) | Jun 05, 2023 |
| ASUSTek       | UX303UA                     | [41514924ed](https://linux-hardware.org/?probe=41514924ed) | Jun 04, 2023 |
| Jumper        | EZbook                      | [950179fe29](https://linux-hardware.org/?probe=950179fe29) | Jun 04, 2023 |
| Toshiba       | Satellite L655              | [1b9656a4a1](https://linux-hardware.org/?probe=1b9656a4a1) | Jun 04, 2023 |
| ASUSTek       | G750JM                      | [f492ab6829](https://linux-hardware.org/?probe=f492ab6829) | Jun 04, 2023 |
| UNOWHY        | Y13G002S4EI                 | [f1b932f397](https://linux-hardware.org/?probe=f1b932f397) | Jun 04, 2023 |
| IP3 Tech      | AP1                         | [d24ecf10e2](https://linux-hardware.org/?probe=d24ecf10e2) | Jun 04, 2023 |
| Toshiba       | Satellite Pro L300          | [968005c798](https://linux-hardware.org/?probe=968005c798) | Jun 04, 2023 |
| ASUSTek       | ROG Strix G713RM_G713RM     | [d45c069b9f](https://linux-hardware.org/?probe=d45c069b9f) | Jun 04, 2023 |
| Samsung       | 950XED                      | [185834c02e](https://linux-hardware.org/?probe=185834c02e) | Jun 04, 2023 |
| Schenker      | XMG FOCUS (M22)             | [31203c3645](https://linux-hardware.org/?probe=31203c3645) | Jun 03, 2023 |
| HONOR         | HGF-WX6                     | [13d0d7b145](https://linux-hardware.org/?probe=13d0d7b145) | Jun 03, 2023 |
| HUAWEI        | CREM-WXX9                   | [75ba9fba2f](https://linux-hardware.org/?probe=75ba9fba2f) | Jun 03, 2023 |
| Acer          | Aspire E5-772G              | [5bd684bed6](https://linux-hardware.org/?probe=5bd684bed6) | Jun 02, 2023 |
| Acer          | Aspire E5-772G              | [f454cdf394](https://linux-hardware.org/?probe=f454cdf394) | Jun 02, 2023 |
| Toshiba       | Satellite L655              | [9b83a4575b](https://linux-hardware.org/?probe=9b83a4575b) | Jun 02, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [d856669333](https://linux-hardware.org/?probe=d856669333) | Jun 02, 2023 |
| Valve         | Jupiter                     | [d1fec35ece](https://linux-hardware.org/?probe=d1fec35ece) | Jun 02, 2023 |
| Gigabyte      | G5 GE                       | [558ee7e63f](https://linux-hardware.org/?probe=558ee7e63f) | Jun 02, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [4d170e024e](https://linux-hardware.org/?probe=4d170e024e) | Jun 02, 2023 |
| Acer          | Aspire 7745G                | [7739f949e1](https://linux-hardware.org/?probe=7739f949e1) | Jun 02, 2023 |
| UNOWHY        | Y13G002S4EI                 | [0bb0a8be66](https://linux-hardware.org/?probe=0bb0a8be66) | Jun 01, 2023 |
| HP            | Laptop 14s-dq0xxx           | [0017659aa2](https://linux-hardware.org/?probe=0017659aa2) | Jun 01, 2023 |
| Dell          | Latitude E5510              | [4a0bc9e53f](https://linux-hardware.org/?probe=4a0bc9e53f) | Jun 01, 2023 |
| ASUSTek       | X751MA                      | [1b1a5c05ac](https://linux-hardware.org/?probe=1b1a5c05ac) | Jun 01, 2023 |
| HP            | EliteBook 650 15.6 inch ... | [3ca0d2f1a7](https://linux-hardware.org/?probe=3ca0d2f1a7) | Jun 01, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [ffc6b5e345](https://linux-hardware.org/?probe=ffc6b5e345) | Jun 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [f66667b7fb](https://linux-hardware.org/?probe=f66667b7fb) | Jun 01, 2023 |
| Dell          | Latitude E5510              | [9457826049](https://linux-hardware.org/?probe=9457826049) | Jun 01, 2023 |
| Samsung       | N150/N210/N220              | [449400ebe9](https://linux-hardware.org/?probe=449400ebe9) | May 31, 2023 |
| Acer          | Aspire 3830TG               | [abd7d9a412](https://linux-hardware.org/?probe=abd7d9a412) | May 31, 2023 |
| Packard Be... | EasyNote LJ75               | [95c733d00f](https://linux-hardware.org/?probe=95c733d00f) | May 31, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [ceaf9120eb](https://linux-hardware.org/?probe=ceaf9120eb) | May 31, 2023 |
| MSI           | GE70 2QE                    | [a075b8b77d](https://linux-hardware.org/?probe=a075b8b77d) | May 31, 2023 |
| Lenovo        | ThinkPad T480 20L6S7PE0G    | [239faf8c55](https://linux-hardware.org/?probe=239faf8c55) | May 31, 2023 |
| Dell          | Inspiron 3502               | [3c734d2900](https://linux-hardware.org/?probe=3c734d2900) | May 31, 2023 |
| ASUSTek       | K52Jc                       | [ad0b57d7c6](https://linux-hardware.org/?probe=ad0b57d7c6) | May 31, 2023 |
| ASUSTek       | K52Jc                       | [7709d9fd16](https://linux-hardware.org/?probe=7709d9fd16) | May 31, 2023 |
| Dell          | Latitude E5510              | [52e1023195](https://linux-hardware.org/?probe=52e1023195) | May 31, 2023 |
| Dell          | Latitude E5510              | [aa0f6a81b6](https://linux-hardware.org/?probe=aa0f6a81b6) | May 30, 2023 |
| Acer          | Aspire V3-574G              | [728459dd4a](https://linux-hardware.org/?probe=728459dd4a) | May 30, 2023 |
| Samsung       | R610                        | [4e3be533ba](https://linux-hardware.org/?probe=4e3be533ba) | May 30, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [86e04155f2](https://linux-hardware.org/?probe=86e04155f2) | May 30, 2023 |
| Dell          | Latitude 3480               | [56d1834385](https://linux-hardware.org/?probe=56d1834385) | May 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [cddd43859b](https://linux-hardware.org/?probe=cddd43859b) | May 30, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [d4cc055d3a](https://linux-hardware.org/?probe=d4cc055d3a) | May 30, 2023 |
| HP            | Elite Dragonfly 13.5 inc... | [1e0fbe86da](https://linux-hardware.org/?probe=1e0fbe86da) | May 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [509bb7aae7](https://linux-hardware.org/?probe=509bb7aae7) | May 29, 2023 |
| Lenovo        | ThinkPad T440p 20AWS19P0... | [8d25da413c](https://linux-hardware.org/?probe=8d25da413c) | May 29, 2023 |
| Acer          | Aspire E5-772G              | [ae0b46c29f](https://linux-hardware.org/?probe=ae0b46c29f) | May 28, 2023 |
| Dell          | XPS 9320                    | [33e7d964ad](https://linux-hardware.org/?probe=33e7d964ad) | May 28, 2023 |
| Shuttle       | X50V5                       | [277cc7ca36](https://linux-hardware.org/?probe=277cc7ca36) | May 28, 2023 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | [d62f60891d](https://linux-hardware.org/?probe=d62f60891d) | May 27, 2023 |
| HP            | Pavilion dv6                | [9f96328490](https://linux-hardware.org/?probe=9f96328490) | May 27, 2023 |
| Dell          | Precision 3581              | [9fb00fd492](https://linux-hardware.org/?probe=9fb00fd492) | May 27, 2023 |
| Dell          | Inspiron 5567               | [9dc73257dc](https://linux-hardware.org/?probe=9dc73257dc) | May 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [efe0b55153](https://linux-hardware.org/?probe=efe0b55153) | May 27, 2023 |
| Dell          | Latitude 3520               | [bfa8a18cb5](https://linux-hardware.org/?probe=bfa8a18cb5) | May 26, 2023 |
| Dell          | G15 5510                    | [f9e862a5dd](https://linux-hardware.org/?probe=f9e862a5dd) | May 26, 2023 |
| ASUSTek       | ROG Strix G513QR_G513QR     | [76a373f9dd](https://linux-hardware.org/?probe=76a373f9dd) | May 26, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [4c3aa6334b](https://linux-hardware.org/?probe=4c3aa6334b) | May 26, 2023 |
| Lenovo        | ThinkPad T450 20BUS06B00    | [d86873ceab](https://linux-hardware.org/?probe=d86873ceab) | May 26, 2023 |
| Toshiba       | Satellite L300              | [10adda3362](https://linux-hardware.org/?probe=10adda3362) | May 25, 2023 |
| ASUSTek       | N75SF                       | [38840055c8](https://linux-hardware.org/?probe=38840055c8) | May 25, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [ab42ac444e](https://linux-hardware.org/?probe=ab42ac444e) | May 24, 2023 |
| Dell          | Precision 5470              | [e0a145106b](https://linux-hardware.org/?probe=e0a145106b) | May 24, 2023 |
| HP            | Pavilion Notebook 15-bc5... | [933989a15b](https://linux-hardware.org/?probe=933989a15b) | May 24, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [d92b2ec905](https://linux-hardware.org/?probe=d92b2ec905) | May 24, 2023 |
| ASUSTek       | K55VJ                       | [2b12b33767](https://linux-hardware.org/?probe=2b12b33767) | May 24, 2023 |
| Dell          | Inspiron 14 5401            | [16d8b1c945](https://linux-hardware.org/?probe=16d8b1c945) | May 24, 2023 |
| HP            | Laptop 17-by3xxx            | [dcafbb2a69](https://linux-hardware.org/?probe=dcafbb2a69) | May 23, 2023 |
| HP            | Laptop 17-by3xxx            | [cbe27885cb](https://linux-hardware.org/?probe=cbe27885cb) | May 23, 2023 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | [f8ef460648](https://linux-hardware.org/?probe=f8ef460648) | May 23, 2023 |
| HP            | ProBook 450 G3              | [4400f1205b](https://linux-hardware.org/?probe=4400f1205b) | May 23, 2023 |
| Lenovo        | ThinkPad W520 4284CY1       | [91945b5bb5](https://linux-hardware.org/?probe=91945b5bb5) | May 23, 2023 |
| Apple         | MacBookPro8,1               | [fadd25f4c5](https://linux-hardware.org/?probe=fadd25f4c5) | May 23, 2023 |
| HP            | Pavilion 17                 | [eb6c222cf7](https://linux-hardware.org/?probe=eb6c222cf7) | May 23, 2023 |
| UNOWHY        | Y13G011S4EI                 | [3642f34cd6](https://linux-hardware.org/?probe=3642f34cd6) | May 23, 2023 |
| ASUSTek       | K73SD                       | [063e42ac60](https://linux-hardware.org/?probe=063e42ac60) | May 22, 2023 |
| ASUSTek       | UX301LAB                    | [69f7b4ae4f](https://linux-hardware.org/?probe=69f7b4ae4f) | May 22, 2023 |
| HUAWEI        | HLYL-WXX9                   | [28a8978593](https://linux-hardware.org/?probe=28a8978593) | May 22, 2023 |
| HP            | Laptop 15-da0xxx            | [82f235bfbb](https://linux-hardware.org/?probe=82f235bfbb) | May 22, 2023 |
| Dell          | Latitude E4200              | [f352cc3ee4](https://linux-hardware.org/?probe=f352cc3ee4) | May 22, 2023 |
| HP            | ProBook 4310s               | [1a32d434c0](https://linux-hardware.org/?probe=1a32d434c0) | May 21, 2023 |
| MSI           | PS63 Modern 8MO             | [5d6f78bfbb](https://linux-hardware.org/?probe=5d6f78bfbb) | May 21, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [bfaa8e099f](https://linux-hardware.org/?probe=bfaa8e099f) | May 21, 2023 |
| ASUSTek       | G752VY                      | [2762dac255](https://linux-hardware.org/?probe=2762dac255) | May 21, 2023 |
| HP            | EliteBook 640 14 inch G9... | [32e623c724](https://linux-hardware.org/?probe=32e623c724) | May 21, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [473ea193d5](https://linux-hardware.org/?probe=473ea193d5) | May 21, 2023 |
| Toshiba       | Satellite P300              | [ed99950768](https://linux-hardware.org/?probe=ed99950768) | May 20, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [c5fee7bb50](https://linux-hardware.org/?probe=c5fee7bb50) | May 20, 2023 |
| Lenovo        | ThinkPad W510 4391DK3       | [ac8db768ce](https://linux-hardware.org/?probe=ac8db768ce) | May 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [de162ff16c](https://linux-hardware.org/?probe=de162ff16c) | May 20, 2023 |
| Timi          | Xiaomi Book Pro 16 2022     | [c1089ff84e](https://linux-hardware.org/?probe=c1089ff84e) | May 20, 2023 |
| Dell          | Precision 5470              | [e600af2d5a](https://linux-hardware.org/?probe=e600af2d5a) | May 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [73aafcfb9c](https://linux-hardware.org/?probe=73aafcfb9c) | May 19, 2023 |
| ASUSTek       | F7Se                        | [1cd79e84fd](https://linux-hardware.org/?probe=1cd79e84fd) | May 19, 2023 |
| Toshiba       | PORTEGE Z830                | [f4548ca81b](https://linux-hardware.org/?probe=f4548ca81b) | May 18, 2023 |
| Toshiba       | Satellite C855-22N          | [f5ccfb46ea](https://linux-hardware.org/?probe=f5ccfb46ea) | May 18, 2023 |
| Lenovo        | ThinkPad T550 20CJS1XB00    | [d1569df0f6](https://linux-hardware.org/?probe=d1569df0f6) | May 18, 2023 |
| HP            | Compaq Presario CQ60        | [5b51a121e2](https://linux-hardware.org/?probe=5b51a121e2) | May 18, 2023 |
| Dell          | Precision 5520              | [6e4c751579](https://linux-hardware.org/?probe=6e4c751579) | May 18, 2023 |
| HP            | ProBook 4310s               | [dfcb51e697](https://linux-hardware.org/?probe=dfcb51e697) | May 17, 2023 |
| Dell          | Latitude 7490               | [392cde1432](https://linux-hardware.org/?probe=392cde1432) | May 17, 2023 |
| Lenovo        | ThinkPad Edge E530 62722... | [baa1b942cf](https://linux-hardware.org/?probe=baa1b942cf) | May 17, 2023 |
| Dell          | Inspiron 5580               | [7ced5f9473](https://linux-hardware.org/?probe=7ced5f9473) | May 17, 2023 |
| Acer          | TravelMate X514-51          | [24465d2184](https://linux-hardware.org/?probe=24465d2184) | May 17, 2023 |
| Acer          | Aspire 5742G                | [04a6fe63c1](https://linux-hardware.org/?probe=04a6fe63c1) | May 17, 2023 |
| Apple         | MacBookAir7,2               | [add6bcd4f7](https://linux-hardware.org/?probe=add6bcd4f7) | May 16, 2023 |
| Apple         | MacBookAir7,2               | [2616bd6b98](https://linux-hardware.org/?probe=2616bd6b98) | May 16, 2023 |
| Fujitsu Si... | AMILO A1645                 | [d825262368](https://linux-hardware.org/?probe=d825262368) | May 16, 2023 |
| Fujitsu Si... | AMILO A1645                 | [18ca79ef29](https://linux-hardware.org/?probe=18ca79ef29) | May 16, 2023 |
| SLIMBOOK      | Executive                   | [0a70f31ce9](https://linux-hardware.org/?probe=0a70f31ce9) | May 16, 2023 |
| Dell          | Precision 5530              | [16366ef886](https://linux-hardware.org/?probe=16366ef886) | May 16, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [05441101a8](https://linux-hardware.org/?probe=05441101a8) | May 16, 2023 |
| Lenovo        | ThinkPad T440 20B7S1MF0D    | [6173458650](https://linux-hardware.org/?probe=6173458650) | May 16, 2023 |
| ASUSTek       | T100TA                      | [050d9ad83f](https://linux-hardware.org/?probe=050d9ad83f) | May 16, 2023 |
| Toshiba       | Satellite L655              | [2fa63538ef](https://linux-hardware.org/?probe=2fa63538ef) | May 15, 2023 |
| Dell          | XPS 17 9700                 | [55eb2f47b9](https://linux-hardware.org/?probe=55eb2f47b9) | May 15, 2023 |
| Sony          | VPCF11M1E                   | [b42c56ac73](https://linux-hardware.org/?probe=b42c56ac73) | May 14, 2023 |
| HUAWEI        | CREM-WXX9                   | [b08b887e1a](https://linux-hardware.org/?probe=b08b887e1a) | May 14, 2023 |
| Sony          | VGN-FW51MF_H                | [572b403a00](https://linux-hardware.org/?probe=572b403a00) | May 14, 2023 |
| Lenovo        | IdeaPad S540-14IWL 81ND     | [d200313f91](https://linux-hardware.org/?probe=d200313f91) | May 14, 2023 |
| Sony          | VGN-FW51MF_H                | [0b0cc4f60e](https://linux-hardware.org/?probe=0b0cc4f60e) | May 14, 2023 |
| HP            | EliteBook 8560w             | [d8735e3006](https://linux-hardware.org/?probe=d8735e3006) | May 14, 2023 |
| ASUSTek       | K55VJ                       | [bf3ff003f9](https://linux-hardware.org/?probe=bf3ff003f9) | May 14, 2023 |
| HP            | EliteBook 8560w             | [ffe7a5c97b](https://linux-hardware.org/?probe=ffe7a5c97b) | May 14, 2023 |
| HP            | Notebook                    | [decd46d3ed](https://linux-hardware.org/?probe=decd46d3ed) | May 14, 2023 |
| Dell          | Latitude E5420              | [571765685f](https://linux-hardware.org/?probe=571765685f) | May 14, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [6335ace28b](https://linux-hardware.org/?probe=6335ace28b) | May 14, 2023 |
| AMI           | Intel                       | [958f5ffc92](https://linux-hardware.org/?probe=958f5ffc92) | May 14, 2023 |
| AMI           | Intel                       | [0c9a68a20c](https://linux-hardware.org/?probe=0c9a68a20c) | May 13, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | [0f3a2fae1b](https://linux-hardware.org/?probe=0f3a2fae1b) | May 13, 2023 |
| Dell          | Latitude 7490               | [16cfe08da3](https://linux-hardware.org/?probe=16cfe08da3) | May 13, 2023 |
| Jumper        | EZbook                      | [56321a4f9c](https://linux-hardware.org/?probe=56321a4f9c) | May 13, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | [ef37458c10](https://linux-hardware.org/?probe=ef37458c10) | May 13, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [804de32208](https://linux-hardware.org/?probe=804de32208) | May 13, 2023 |
| MSI           | GL73 8RC                    | [4eb76264f2](https://linux-hardware.org/?probe=4eb76264f2) | May 12, 2023 |
| ASUSTek       | X411UA                      | [bd54bb7c02](https://linux-hardware.org/?probe=bd54bb7c02) | May 12, 2023 |
| HUAWEI        | HVY-WXX9                    | [9ca71ebd01](https://linux-hardware.org/?probe=9ca71ebd01) | May 12, 2023 |
| Dell          | Precision 5550              | [f6d4846655](https://linux-hardware.org/?probe=f6d4846655) | May 12, 2023 |
| HUAWEI        | NBD-WXX9                    | [d8c0bd3bff](https://linux-hardware.org/?probe=d8c0bd3bff) | May 12, 2023 |
| Dell          | Latitude 7490               | [a187ae7b7e](https://linux-hardware.org/?probe=a187ae7b7e) | May 12, 2023 |
| HP            | Stream Notebook             | [5ed3be74da](https://linux-hardware.org/?probe=5ed3be74da) | May 12, 2023 |
| Toshiba       | Satellite Pro C660          | [848eedb681](https://linux-hardware.org/?probe=848eedb681) | May 12, 2023 |
| HUAWEI        | MACHD-WXX9                  | [f5d0a04a09](https://linux-hardware.org/?probe=f5d0a04a09) | May 12, 2023 |
| Medion        | Crawler E40                 | [d0df38a2da](https://linux-hardware.org/?probe=d0df38a2da) | May 12, 2023 |
| Medion        | Crawler E40                 | [c58193ce55](https://linux-hardware.org/?probe=c58193ce55) | May 12, 2023 |
| HP            | ProBook 450 G7              | [ba542c09f2](https://linux-hardware.org/?probe=ba542c09f2) | May 12, 2023 |
| Dell          | Latitude 7400               | [c8ce2e462f](https://linux-hardware.org/?probe=c8ce2e462f) | May 11, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [a1cb5cae49](https://linux-hardware.org/?probe=a1cb5cae49) | May 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [7b53d1c3dc](https://linux-hardware.org/?probe=7b53d1c3dc) | May 11, 2023 |
| Apple         | MacBookPro6,2               | [f56ecb2642](https://linux-hardware.org/?probe=f56ecb2642) | May 11, 2023 |
| Dell          | Latitude E4310              | [84d1a3fda9](https://linux-hardware.org/?probe=84d1a3fda9) | May 11, 2023 |
| Lenovo        | ThinkPad X240 20AMS1J100    | [86edc6c6d6](https://linux-hardware.org/?probe=86edc6c6d6) | May 11, 2023 |
| ASUSTek       | X411UA                      | [bc27160391](https://linux-hardware.org/?probe=bc27160391) | May 10, 2023 |
| Toshiba       | Satellite C660D             | [0337ec13a6](https://linux-hardware.org/?probe=0337ec13a6) | May 10, 2023 |
| Dell          | Precision 5520              | [5dfdbeff37](https://linux-hardware.org/?probe=5dfdbeff37) | May 10, 2023 |
| Fujitsu       | LIFEBOOK A3510              | [7df7ca9fbf](https://linux-hardware.org/?probe=7df7ca9fbf) | May 10, 2023 |
| ASUSTek       | X550CC                      | [4d0b606423](https://linux-hardware.org/?probe=4d0b606423) | May 10, 2023 |
| HP            | Presario CQ62               | [7619e0cff9](https://linux-hardware.org/?probe=7619e0cff9) | May 10, 2023 |
| Sony          | SVE1713K1EB                 | [96244b73e7](https://linux-hardware.org/?probe=96244b73e7) | May 10, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [0b797e8428](https://linux-hardware.org/?probe=0b797e8428) | May 10, 2023 |
| Notebook      | N150ZU                      | [bfd69adf4e](https://linux-hardware.org/?probe=bfd69adf4e) | May 10, 2023 |
| Thomson       | N14C64WF                    | [4e5a5f6e51](https://linux-hardware.org/?probe=4e5a5f6e51) | May 10, 2023 |
| Dell          | G5 5590                     | [c07c29d5de](https://linux-hardware.org/?probe=c07c29d5de) | May 09, 2023 |
| Apple         | MacBookPro6,2               | [db93afa653](https://linux-hardware.org/?probe=db93afa653) | May 09, 2023 |
| ASUSTek       | X200MA                      | [1f7840b315](https://linux-hardware.org/?probe=1f7840b315) | May 08, 2023 |
| Acer          | Swift SFA16-41              | [7934eebd9b](https://linux-hardware.org/?probe=7934eebd9b) | May 08, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | [4c3f70e8d3](https://linux-hardware.org/?probe=4c3f70e8d3) | May 08, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [dc97e2fc43](https://linux-hardware.org/?probe=dc97e2fc43) | May 08, 2023 |
| Acer          | Aspire 7741                 | [995e6d9580](https://linux-hardware.org/?probe=995e6d9580) | May 08, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [0d2ac684c8](https://linux-hardware.org/?probe=0d2ac684c8) | May 08, 2023 |
| HP            | EliteBook 725 G4            | [bf3ce4741e](https://linux-hardware.org/?probe=bf3ce4741e) | May 08, 2023 |
| Dell          | Inspiron 16 Plus 7620       | [ea808c2e80](https://linux-hardware.org/?probe=ea808c2e80) | May 08, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [f4d1f788e1](https://linux-hardware.org/?probe=f4d1f788e1) | May 08, 2023 |
| Dell          | Inspiron 16 Plus 7620       | [382b81c0d1](https://linux-hardware.org/?probe=382b81c0d1) | May 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X432... | [395097d3a3](https://linux-hardware.org/?probe=395097d3a3) | May 08, 2023 |
| Acer          | Aspire V3-772G              | [bbf20cfdad](https://linux-hardware.org/?probe=bbf20cfdad) | May 08, 2023 |
| HP            | EliteBook 840 G5            | [48d87e5c6e](https://linux-hardware.org/?probe=48d87e5c6e) | May 08, 2023 |
| Sony          | VPCZ12C5E                   | [512da95fb0](https://linux-hardware.org/?probe=512da95fb0) | May 08, 2023 |
| Lenovo        | ThinkPad T440 20B7A0CYFR    | [f945ec106e](https://linux-hardware.org/?probe=f945ec106e) | May 07, 2023 |
| Dell          | Precision 5510              | [9a4ba61d41](https://linux-hardware.org/?probe=9a4ba61d41) | May 07, 2023 |
| Dell          | MXG061                      | [8ef701b61d](https://linux-hardware.org/?probe=8ef701b61d) | May 07, 2023 |
| ASUSTek       | K73SJ                       | [99ede66d8d](https://linux-hardware.org/?probe=99ede66d8d) | May 07, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [816f9e047a](https://linux-hardware.org/?probe=816f9e047a) | May 07, 2023 |
| MSI           | Katana GF66 11UE            | [e69f8169fc](https://linux-hardware.org/?probe=e69f8169fc) | May 07, 2023 |
| Lenovo        | ThinkPad SL500 27464DG      | [f2bb35c6d3](https://linux-hardware.org/?probe=f2bb35c6d3) | May 07, 2023 |
| Sony          | VPCZ12C5E                   | [67e1fdf9c2](https://linux-hardware.org/?probe=67e1fdf9c2) | May 07, 2023 |
| ASUSTek       | K73SJ                       | [13b8c8be10](https://linux-hardware.org/?probe=13b8c8be10) | May 07, 2023 |
| Valve         | Jupiter                     | [270eaa3e12](https://linux-hardware.org/?probe=270eaa3e12) | May 07, 2023 |
| HP            | Presario CQ57               | [370295ac6d](https://linux-hardware.org/?probe=370295ac6d) | May 07, 2023 |
| Alienware     | 18                          | [4c6abf91cd](https://linux-hardware.org/?probe=4c6abf91cd) | May 07, 2023 |
| HP            | Elite Dragonfly 13.5 inc... | [50b503ae3e](https://linux-hardware.org/?probe=50b503ae3e) | May 07, 2023 |
| HP            | Elite Dragonfly 13.5 inc... | [64bbfa416b](https://linux-hardware.org/?probe=64bbfa416b) | May 07, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAS... | [6c404ee491](https://linux-hardware.org/?probe=6c404ee491) | May 06, 2023 |
| Acer          | Aspire AV15-51              | [9d7736a816](https://linux-hardware.org/?probe=9d7736a816) | May 06, 2023 |
| Unknown       | Unknown                     | [dd406112de](https://linux-hardware.org/?probe=dd406112de) | May 06, 2023 |
| Dell          | Precision 7550              | [5f962aaea0](https://linux-hardware.org/?probe=5f962aaea0) | May 06, 2023 |
| Acer          | Aspire 7720                 | [e28510b64d](https://linux-hardware.org/?probe=e28510b64d) | May 06, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [c67960852a](https://linux-hardware.org/?probe=c67960852a) | May 06, 2023 |
| Notebook      | N7x0WU                      | [985f971691](https://linux-hardware.org/?probe=985f971691) | May 06, 2023 |
| ASUSTek       | Strix GL504GS_GL504GS       | [cdb842cc09](https://linux-hardware.org/?probe=cdb842cc09) | May 06, 2023 |
| Acer          | NC-V3-772G-747A8G1TMAKK     | [58f420d816](https://linux-hardware.org/?probe=58f420d816) | May 06, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [b4f013c967](https://linux-hardware.org/?probe=b4f013c967) | May 06, 2023 |
| Acer          | Aspire E5-571G              | [4b45fabd96](https://linux-hardware.org/?probe=4b45fabd96) | May 05, 2023 |
| Acer          | Aspire 7720                 | [2e216b0830](https://linux-hardware.org/?probe=2e216b0830) | May 05, 2023 |
| Lenovo        | ThinkPad T450 20BUS46900    | [523dce6a6d](https://linux-hardware.org/?probe=523dce6a6d) | May 05, 2023 |
| Unknown       | X133                        | [b38ee0b3cc](https://linux-hardware.org/?probe=b38ee0b3cc) | May 05, 2023 |
| eMachines     | eMG620                      | [224dc7209e](https://linux-hardware.org/?probe=224dc7209e) | May 04, 2023 |
| Dell          | Latitude 7490               | [65d9b877b5](https://linux-hardware.org/?probe=65d9b877b5) | May 04, 2023 |
| Dell          | Latitude 7490               | [383b9d3aec](https://linux-hardware.org/?probe=383b9d3aec) | May 04, 2023 |
| Dell          | XPS 15 9550                 | [e31c30bd52](https://linux-hardware.org/?probe=e31c30bd52) | May 04, 2023 |
| ASUSTek       | K61IC                       | [727b9fae92](https://linux-hardware.org/?probe=727b9fae92) | May 03, 2023 |
| Notebook      | N7x0WU                      | [b11821f4a1](https://linux-hardware.org/?probe=b11821f4a1) | May 03, 2023 |
| HP            | Unknown                     | [b99510884b](https://linux-hardware.org/?probe=b99510884b) | May 03, 2023 |
| HP            | EliteBook 640 14 inch G9... | [fc1bd7fffc](https://linux-hardware.org/?probe=fc1bd7fffc) | May 03, 2023 |
| HP            | EliteBook 640 14 inch G9... | [c8373114ef](https://linux-hardware.org/?probe=c8373114ef) | May 03, 2023 |
| HP            | Pavilion dm4                | [cb567d8263](https://linux-hardware.org/?probe=cb567d8263) | May 03, 2023 |
| UNOWHY        | Y13G011S4EI                 | [581cd68800](https://linux-hardware.org/?probe=581cd68800) | May 02, 2023 |
| HP            | OMEN by Laptop              | [a60578cfe2](https://linux-hardware.org/?probe=a60578cfe2) | May 02, 2023 |
| MSI           | Katana GF76 12UEK           | [5af5d6aec3](https://linux-hardware.org/?probe=5af5d6aec3) | May 01, 2023 |
| Notebook      | NS5x_NS7xPU                 | [ee97e0f5f0](https://linux-hardware.org/?probe=ee97e0f5f0) | May 01, 2023 |
| ASUSTek       | ZenBook UX535LI             | [35adc352dd](https://linux-hardware.org/?probe=35adc352dd) | May 01, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [3be920565f](https://linux-hardware.org/?probe=3be920565f) | May 01, 2023 |
| Sony          | VGN-AW11M_H                 | [2c9f98ca31](https://linux-hardware.org/?probe=2c9f98ca31) | May 01, 2023 |
| HUAWEI        | CREM-WXX9                   | [ba99960d5f](https://linux-hardware.org/?probe=ba99960d5f) | May 01, 2023 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [4bec088d90](https://linux-hardware.org/?probe=4bec088d90) | Apr 30, 2023 |
| Valve         | Jupiter                     | [3bee1a3271](https://linux-hardware.org/?probe=3bee1a3271) | Apr 30, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [e1d1572c51](https://linux-hardware.org/?probe=e1d1572c51) | Apr 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | [2dd85470a0](https://linux-hardware.org/?probe=2dd85470a0) | Apr 30, 2023 |
| ASUSTek       | X751MA                      | [00fbe71b59](https://linux-hardware.org/?probe=00fbe71b59) | Apr 30, 2023 |
| Samsung       | 950XED                      | [41f620de17](https://linux-hardware.org/?probe=41f620de17) | Apr 30, 2023 |
| Packard Be... | EasyNote ENTF71BM           | [99a89a2055](https://linux-hardware.org/?probe=99a89a2055) | Apr 30, 2023 |
| HP            | EliteBook 840 G1            | [6f4c134615](https://linux-hardware.org/?probe=6f4c134615) | Apr 29, 2023 |
| Sony          | VPCF11M1E                   | [16772fe220](https://linux-hardware.org/?probe=16772fe220) | Apr 29, 2023 |
| MSI           | P65 Creator 9SF             | [4e682b2c20](https://linux-hardware.org/?probe=4e682b2c20) | Apr 29, 2023 |
| Acer          | Aspire E5-722               | [d02052aeab](https://linux-hardware.org/?probe=d02052aeab) | Apr 29, 2023 |
| Dell          | XPS 13 9310                 | [2f3308a2ee](https://linux-hardware.org/?probe=2f3308a2ee) | Apr 29, 2023 |
| COPELION I... | QX-250 Series               | [409821566f](https://linux-hardware.org/?probe=409821566f) | Apr 29, 2023 |
| HUAWEI        | CREM-WXX9                   | [c17b468722](https://linux-hardware.org/?probe=c17b468722) | Apr 29, 2023 |
| Acer          | Aspire 5349                 | [aa8c0bb2b9](https://linux-hardware.org/?probe=aa8c0bb2b9) | Apr 29, 2023 |
| Acer          | Swift SF114-32              | [f4eea7ce60](https://linux-hardware.org/?probe=f4eea7ce60) | Apr 29, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | [09d6d7e570](https://linux-hardware.org/?probe=09d6d7e570) | Apr 28, 2023 |
| Lenovo        | ThinkPad L560 20F2S13L00    | [7695cef903](https://linux-hardware.org/?probe=7695cef903) | Apr 28, 2023 |
| HP            | EliteBook 8540p             | [d4bb8a135d](https://linux-hardware.org/?probe=d4bb8a135d) | Apr 28, 2023 |
| HP            | Laptop 14-em0xxx            | [8d06549ae0](https://linux-hardware.org/?probe=8d06549ae0) | Apr 28, 2023 |
| Dell          | Precision 3551              | [99ff11c325](https://linux-hardware.org/?probe=99ff11c325) | Apr 28, 2023 |
| Dell          | Precision 3551              | [93a38e7384](https://linux-hardware.org/?probe=93a38e7384) | Apr 28, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [e80ea5c4ae](https://linux-hardware.org/?probe=e80ea5c4ae) | Apr 28, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [990335263d](https://linux-hardware.org/?probe=990335263d) | Apr 28, 2023 |
| Toshiba       | TECRA Z40-C                 | [31bdde77c9](https://linux-hardware.org/?probe=31bdde77c9) | Apr 28, 2023 |
| Toshiba       | TECRA Z40-C                 | [eb550390c1](https://linux-hardware.org/?probe=eb550390c1) | Apr 28, 2023 |
| ASUSTek       | T100TA                      | [7c34e35183](https://linux-hardware.org/?probe=7c34e35183) | Apr 28, 2023 |
| ASUSTek       | T100TA                      | [266477f792](https://linux-hardware.org/?probe=266477f792) | Apr 28, 2023 |
| Apple         | MacBookPro6,2               | [ceaa38e624](https://linux-hardware.org/?probe=ceaa38e624) | Apr 28, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [b21dd8d75a](https://linux-hardware.org/?probe=b21dd8d75a) | Apr 27, 2023 |
| Dell          | Latitude E7270              | [5bacf4eea3](https://linux-hardware.org/?probe=5bacf4eea3) | Apr 27, 2023 |
| ASUSTek       | S551LN                      | [710070cf4a](https://linux-hardware.org/?probe=710070cf4a) | Apr 27, 2023 |
| Acer          | Nitro AN515-57              | [f549cb502c](https://linux-hardware.org/?probe=f549cb502c) | Apr 27, 2023 |
| HP            | Pavilion g6                 | [716373f59a](https://linux-hardware.org/?probe=716373f59a) | Apr 27, 2023 |
| Timi          | TM1703                      | [7e6b948ea9](https://linux-hardware.org/?probe=7e6b948ea9) | Apr 26, 2023 |
| Samsung       | 950XED                      | [02586ee1ba](https://linux-hardware.org/?probe=02586ee1ba) | Apr 26, 2023 |
| Dell          | Vostro 1520                 | [ef4bb434d9](https://linux-hardware.org/?probe=ef4bb434d9) | Apr 26, 2023 |
| Dell          | XPS 15 9500                 | [e37d368767](https://linux-hardware.org/?probe=e37d368767) | Apr 26, 2023 |
| ASUSTek       | K73BR                       | [547b19cd2c](https://linux-hardware.org/?probe=547b19cd2c) | Apr 26, 2023 |
| Dell          | Latitude 5430               | [75ac9d10bf](https://linux-hardware.org/?probe=75ac9d10bf) | Apr 26, 2023 |
| Lenovo        | ThinkPad X250 20CMCTO1WW    | [bf207e9dc3](https://linux-hardware.org/?probe=bf207e9dc3) | Apr 25, 2023 |
| LDLC          | SPC-I                       | [899fb46a02](https://linux-hardware.org/?probe=899fb46a02) | Apr 25, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [253f35c2c3](https://linux-hardware.org/?probe=253f35c2c3) | Apr 24, 2023 |
| Samsung       | 950XED                      | [6226147e11](https://linux-hardware.org/?probe=6226147e11) | Apr 24, 2023 |
| LG Electro... | 16Z90Q-G.AD78F              | [99bbc09adb](https://linux-hardware.org/?probe=99bbc09adb) | Apr 24, 2023 |
| HP            | 15                          | [fd68fb06af](https://linux-hardware.org/?probe=fd68fb06af) | Apr 23, 2023 |
| Sony          | VPCEH3U1E                   | [6fa28ef21c](https://linux-hardware.org/?probe=6fa28ef21c) | Apr 23, 2023 |
| HP            | ProBook 6570b               | [4e2ba781e2](https://linux-hardware.org/?probe=4e2ba781e2) | Apr 23, 2023 |
| Dell          | Latitude 5591               | [b4dfa57eea](https://linux-hardware.org/?probe=b4dfa57eea) | Apr 23, 2023 |
| Dell          | Latitude 5591               | [1a45f96f80](https://linux-hardware.org/?probe=1a45f96f80) | Apr 23, 2023 |
| Toshiba       | PORTEGE Z20t-C              | [45d7bd0907](https://linux-hardware.org/?probe=45d7bd0907) | Apr 23, 2023 |
| ASUSTek       | S551LN                      | [9ba55985fd](https://linux-hardware.org/?probe=9ba55985fd) | Apr 23, 2023 |
| Toshiba       | PORTEGE Z20t-C              | [c7367bfdff](https://linux-hardware.org/?probe=c7367bfdff) | Apr 23, 2023 |
| Acer          | Swift SF314-42              | [2508f138a4](https://linux-hardware.org/?probe=2508f138a4) | Apr 23, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [aa01246f8b](https://linux-hardware.org/?probe=aa01246f8b) | Apr 23, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [9a6f040039](https://linux-hardware.org/?probe=9a6f040039) | Apr 23, 2023 |
| Apple         | MacBookPro5,5               | [bee14868f2](https://linux-hardware.org/?probe=bee14868f2) | Apr 23, 2023 |
| Lenovo        | ThinkPad T420 4236EJ3       | [77a309dcf1](https://linux-hardware.org/?probe=77a309dcf1) | Apr 22, 2023 |
| Lenovo        | ThinkPad T420 4236EJ3       | [4c60675864](https://linux-hardware.org/?probe=4c60675864) | Apr 22, 2023 |
| Dell          | XPS 13 9333                 | [0fedfa2911](https://linux-hardware.org/?probe=0fedfa2911) | Apr 22, 2023 |
| Apple         | MacBookPro11,5              | [7a873a7baa](https://linux-hardware.org/?probe=7a873a7baa) | Apr 22, 2023 |
| MSI           | Prestige 15 A10SC           | [f64336848a](https://linux-hardware.org/?probe=f64336848a) | Apr 22, 2023 |
| HP            | Laptop 14-em0xxx            | [55ea4ded18](https://linux-hardware.org/?probe=55ea4ded18) | Apr 22, 2023 |
| Compal        | HEL81I                      | [426788b00c](https://linux-hardware.org/?probe=426788b00c) | Apr 22, 2023 |
| Dell          | Precision 5510              | [94b5586a2c](https://linux-hardware.org/?probe=94b5586a2c) | Apr 22, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | [0f5a55a8d1](https://linux-hardware.org/?probe=0f5a55a8d1) | Apr 22, 2023 |
| Lenovo        | IdeaPad Yoga 13 20175       | [89b64bbfb6](https://linux-hardware.org/?probe=89b64bbfb6) | Apr 22, 2023 |
| HP            | Elite Dragonfly 13.5 inc... | [2a5d9adcd4](https://linux-hardware.org/?probe=2a5d9adcd4) | Apr 21, 2023 |
| MSI           | GS65 Stealth 8SE            | [f813e87465](https://linux-hardware.org/?probe=f813e87465) | Apr 21, 2023 |
| HUAWEI        | HLYL-WXX9                   | [78adec215e](https://linux-hardware.org/?probe=78adec215e) | Apr 21, 2023 |
| MSI           | GS65 Stealth 8SE            | [53951da2d7](https://linux-hardware.org/?probe=53951da2d7) | Apr 21, 2023 |
| ASUSTek       | S551LN                      | [c974888840](https://linux-hardware.org/?probe=c974888840) | Apr 21, 2023 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [acbe851404](https://linux-hardware.org/?probe=acbe851404) | Apr 21, 2023 |
| PC Special... | TN1-156M                    | [ef6b57e807](https://linux-hardware.org/?probe=ef6b57e807) | Apr 21, 2023 |
| HP            | Notebook                    | [150b1d6ae7](https://linux-hardware.org/?probe=150b1d6ae7) | Apr 21, 2023 |
| MSI           | GS73VR 7RF                  | [2eb85cc7fe](https://linux-hardware.org/?probe=2eb85cc7fe) | Apr 20, 2023 |
| Valve         | Jupiter                     | [a0ee1dbeff](https://linux-hardware.org/?probe=a0ee1dbeff) | Apr 20, 2023 |
| ASUSTek       | K61IC                       | [985a269b26](https://linux-hardware.org/?probe=985a269b26) | Apr 20, 2023 |
| MSI           | CR61 3M                     | [0ee98cd841](https://linux-hardware.org/?probe=0ee98cd841) | Apr 20, 2023 |
| Acer          | TravelMate 5320             | [fa41e30258](https://linux-hardware.org/?probe=fa41e30258) | Apr 20, 2023 |
| Acer          | Aspire E3-111               | [9af253f4e0](https://linux-hardware.org/?probe=9af253f4e0) | Apr 20, 2023 |
| ASUSTek       | G771JW                      | [fd6d8a7cd7](https://linux-hardware.org/?probe=fd6d8a7cd7) | Apr 20, 2023 |
| Acer          | Aspire 5738                 | [fc12fc0a9d](https://linux-hardware.org/?probe=fc12fc0a9d) | Apr 19, 2023 |
| Lenovo        | ThinkPad T440p 20AWS1B30... | [c0207e5f9a](https://linux-hardware.org/?probe=c0207e5f9a) | Apr 19, 2023 |
| PC Special... | NV4XMB,ME,MZ                | [65c0a28c58](https://linux-hardware.org/?probe=65c0a28c58) | Apr 18, 2023 |
| ASUSTek       | X751BP                      | [0bea82acba](https://linux-hardware.org/?probe=0bea82acba) | Apr 18, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [ec0532e3e3](https://linux-hardware.org/?probe=ec0532e3e3) | Apr 18, 2023 |
| Lenovo        | ThinkPad L520 5015AH2       | [db4749ffef](https://linux-hardware.org/?probe=db4749ffef) | Apr 18, 2023 |
| ASUSTek       | K55A                        | [99fe712761](https://linux-hardware.org/?probe=99fe712761) | Apr 17, 2023 |
| ASUSTek       | UX303LB                     | [48c19abe8c](https://linux-hardware.org/?probe=48c19abe8c) | Apr 17, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | [d12e0064fc](https://linux-hardware.org/?probe=d12e0064fc) | Apr 17, 2023 |
| HP            | Pavilion 17                 | [b06b49ac95](https://linux-hardware.org/?probe=b06b49ac95) | Apr 17, 2023 |
| Dell          | Precision 3571              | [d1fcff8b8f](https://linux-hardware.org/?probe=d1fcff8b8f) | Apr 17, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [f3a91915df](https://linux-hardware.org/?probe=f3a91915df) | Apr 17, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [d5db24c28d](https://linux-hardware.org/?probe=d5db24c28d) | Apr 17, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [89eb2b2c32](https://linux-hardware.org/?probe=89eb2b2c32) | Apr 17, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [4296a1241d](https://linux-hardware.org/?probe=4296a1241d) | Apr 17, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [f0353d1327](https://linux-hardware.org/?probe=f0353d1327) | Apr 16, 2023 |
| ASUSTek       | K53BE                       | [f21e7219ce](https://linux-hardware.org/?probe=f21e7219ce) | Apr 16, 2023 |
| Dell          | Vostro 15 7510              | [d9e766f446](https://linux-hardware.org/?probe=d9e766f446) | Apr 16, 2023 |
| HP            | OMEN by Laptop 15-ce0xx     | [da62023f35](https://linux-hardware.org/?probe=da62023f35) | Apr 15, 2023 |
| Dell          | Latitude E5520              | [5e04eeccae](https://linux-hardware.org/?probe=5e04eeccae) | Apr 15, 2023 |
| ASUSTek       | G771JW                      | [f534984150](https://linux-hardware.org/?probe=f534984150) | Apr 15, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [0e89a3c19b](https://linux-hardware.org/?probe=0e89a3c19b) | Apr 15, 2023 |
| ASUSTek       | X540YA                      | [8de126d84d](https://linux-hardware.org/?probe=8de126d84d) | Apr 15, 2023 |
| ASUSTek       | X302LJ                      | [e045b269b1](https://linux-hardware.org/?probe=e045b269b1) | Apr 14, 2023 |
| Toshiba       | Satellite L655              | [c3c64a7016](https://linux-hardware.org/?probe=c3c64a7016) | Apr 14, 2023 |
| HP            | ProBook 640 G1              | [2b7836fd04](https://linux-hardware.org/?probe=2b7836fd04) | Apr 14, 2023 |
| HP            | Laptop 17-cp0xxx            | [6fdb6931f0](https://linux-hardware.org/?probe=6fdb6931f0) | Apr 14, 2023 |
| HP            | ProBook 6570b               | [af45cce5b8](https://linux-hardware.org/?probe=af45cce5b8) | Apr 14, 2023 |
| Dell          | Inspiron 15 3511            | [6cfca82c2f](https://linux-hardware.org/?probe=6cfca82c2f) | Apr 14, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | [df35f6916a](https://linux-hardware.org/?probe=df35f6916a) | Apr 14, 2023 |
| HP            | Pavilion dv6                | [d938ba339d](https://linux-hardware.org/?probe=d938ba339d) | Apr 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [b223f5fbf1](https://linux-hardware.org/?probe=b223f5fbf1) | Apr 13, 2023 |
| Dell          | G15 5510                    | [6b4ef54307](https://linux-hardware.org/?probe=6b4ef54307) | Apr 13, 2023 |
| Dell          | XPS L322X                   | [cbf247e5a6](https://linux-hardware.org/?probe=cbf247e5a6) | Apr 13, 2023 |
| HP            | Pavilion TS 15              | [43b322dcf3](https://linux-hardware.org/?probe=43b322dcf3) | Apr 12, 2023 |
| HP            | Pavilion dv6                | [09b80dd551](https://linux-hardware.org/?probe=09b80dd551) | Apr 12, 2023 |
| HP            | Pavilion dv7                | [4363479bf0](https://linux-hardware.org/?probe=4363479bf0) | Apr 12, 2023 |
| Dell          | Precision 3571              | [e6e8267b6a](https://linux-hardware.org/?probe=e6e8267b6a) | Apr 12, 2023 |
| Dell          | Latitude 5420               | [248e22982d](https://linux-hardware.org/?probe=248e22982d) | Apr 12, 2023 |
| Dell          | Precision 7520              | [1d23894711](https://linux-hardware.org/?probe=1d23894711) | Apr 12, 2023 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | [905a2aee02](https://linux-hardware.org/?probe=905a2aee02) | Apr 12, 2023 |
| Acer          | Aspire 5742G                | [878333e620](https://linux-hardware.org/?probe=878333e620) | Apr 12, 2023 |
| MSI           | GP72MVR 7RFX                | [17f60a29f5](https://linux-hardware.org/?probe=17f60a29f5) | Apr 11, 2023 |
| Valve         | Jupiter                     | [32bf664d90](https://linux-hardware.org/?probe=32bf664d90) | Apr 11, 2023 |
| HP            | Pavilion g6                 | [f4190d2c4e](https://linux-hardware.org/?probe=f4190d2c4e) | Apr 11, 2023 |
| ASUSTek       | UX303UA                     | [6e9b87d6e1](https://linux-hardware.org/?probe=6e9b87d6e1) | Apr 11, 2023 |
| Gigabyte      | X7X7                        | [8f58573ff3](https://linux-hardware.org/?probe=8f58573ff3) | Apr 11, 2023 |
| MSI           | Prestige 14Evo B13M         | [a3967e84ad](https://linux-hardware.org/?probe=a3967e84ad) | Apr 11, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [eb294beef7](https://linux-hardware.org/?probe=eb294beef7) | Apr 11, 2023 |
| ASUSTek       | G751JY                      | [618a195c21](https://linux-hardware.org/?probe=618a195c21) | Apr 10, 2023 |
| ASUSTek       | ZenBook S UX391UA           | [704f5bcf78](https://linux-hardware.org/?probe=704f5bcf78) | Apr 10, 2023 |
| Sony          | VPCEB1M1E                   | [c182925286](https://linux-hardware.org/?probe=c182925286) | Apr 09, 2023 |
| ASUSTek       | ZenBook S UX391UA           | [fe939f268b](https://linux-hardware.org/?probe=fe939f268b) | Apr 09, 2023 |
| ASUSTek       | ZenBook S UX391UA           | [955a648772](https://linux-hardware.org/?probe=955a648772) | Apr 09, 2023 |
| Toshiba       | Satellite C660              | [bb9f88795d](https://linux-hardware.org/?probe=bb9f88795d) | Apr 09, 2023 |
| Apple         | MacBook3,1                  | [ee2678d76f](https://linux-hardware.org/?probe=ee2678d76f) | Apr 09, 2023 |
| ASUSTek       | P552LA                      | [803ac095e7](https://linux-hardware.org/?probe=803ac095e7) | Apr 08, 2023 |
| ASUSTek       | X756UQ                      | [bff5545041](https://linux-hardware.org/?probe=bff5545041) | Apr 08, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [12faf271f6](https://linux-hardware.org/?probe=12faf271f6) | Apr 08, 2023 |
| ASUSTek       | X751LN                      | [8bf4f37814](https://linux-hardware.org/?probe=8bf4f37814) | Apr 08, 2023 |
| HP            | ENVY dv6                    | [0d89a1797e](https://linux-hardware.org/?probe=0d89a1797e) | Apr 08, 2023 |
| HP            | ZBook 17 G2                 | [fc2425ffde](https://linux-hardware.org/?probe=fc2425ffde) | Apr 08, 2023 |
| Acer          | Nitro AN517-54              | [185c4824b7](https://linux-hardware.org/?probe=185c4824b7) | Apr 07, 2023 |
| Dell          | G3 3500                     | [cae0e09f03](https://linux-hardware.org/?probe=cae0e09f03) | Apr 07, 2023 |
| Dell          | G3 3500                     | [9f77f9158a](https://linux-hardware.org/?probe=9f77f9158a) | Apr 07, 2023 |
| HP            | Laptop 17-cp0xxx            | [cb0b33006e](https://linux-hardware.org/?probe=cb0b33006e) | Apr 07, 2023 |
| ASUSTek       | S551LN                      | [2c731aefae](https://linux-hardware.org/?probe=2c731aefae) | Apr 07, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [d5c75a0967](https://linux-hardware.org/?probe=d5c75a0967) | Apr 06, 2023 |
| MSI           | GL73 8RC                    | [c134ae92fc](https://linux-hardware.org/?probe=c134ae92fc) | Apr 06, 2023 |
| HP            | Sona                        | [64fa63647b](https://linux-hardware.org/?probe=64fa63647b) | Apr 06, 2023 |
| Dell          | Precision 7560              | [b474fb4429](https://linux-hardware.org/?probe=b474fb4429) | Apr 06, 2023 |
| ASUSTek       | S551LN                      | [bab2c0f0e4](https://linux-hardware.org/?probe=bab2c0f0e4) | Apr 06, 2023 |
| Dell          | Latitude E7470              | [64721a0d8a](https://linux-hardware.org/?probe=64721a0d8a) | Apr 05, 2023 |
| Acer          | Aspire E1-570               | [ad70ba8e9d](https://linux-hardware.org/?probe=ad70ba8e9d) | Apr 05, 2023 |
| Acer          | Aspire 5742G                | [5363e4031e](https://linux-hardware.org/?probe=5363e4031e) | Apr 05, 2023 |
| eMachines     | eMachiens G443              | [58c297218a](https://linux-hardware.org/?probe=58c297218a) | Apr 05, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [5d0489d439](https://linux-hardware.org/?probe=5d0489d439) | Apr 05, 2023 |
| Toshiba       | Satellite C855D-12J         | [cb3dedf5e8](https://linux-hardware.org/?probe=cb3dedf5e8) | Apr 05, 2023 |
| HP            | Notebook                    | [99a9d4cae5](https://linux-hardware.org/?probe=99a9d4cae5) | Apr 05, 2023 |
| System76      | Lemur Pro                   | [2232424d5a](https://linux-hardware.org/?probe=2232424d5a) | Apr 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [f98b9efce7](https://linux-hardware.org/?probe=f98b9efce7) | Apr 05, 2023 |
| ASUSTek       | X71Q                        | [9a7d0f4b2b](https://linux-hardware.org/?probe=9a7d0f4b2b) | Apr 05, 2023 |
| HP            | ProBook 645 G4              | [dad967cc87](https://linux-hardware.org/?probe=dad967cc87) | Apr 05, 2023 |
| HP            | ProBook 645 G4              | [0f75295895](https://linux-hardware.org/?probe=0f75295895) | Apr 05, 2023 |
| Valve         | Jupiter                     | [2d32794500](https://linux-hardware.org/?probe=2d32794500) | Apr 05, 2023 |
| HONOR         | NMH-WCX9                    | [9ea45909a2](https://linux-hardware.org/?probe=9ea45909a2) | Apr 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [f04b34af52](https://linux-hardware.org/?probe=f04b34af52) | Apr 04, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | [fa9fe4337a](https://linux-hardware.org/?probe=fa9fe4337a) | Apr 04, 2023 |
| Valve         | Jupiter                     | [9ef9150c8c](https://linux-hardware.org/?probe=9ef9150c8c) | Apr 04, 2023 |
| MSI           | PS42 Modern 8MO             | [60633671a2](https://linux-hardware.org/?probe=60633671a2) | Apr 04, 2023 |
| ASUSTek       | X550JK                      | [b75b9b9fa2](https://linux-hardware.org/?probe=b75b9b9fa2) | Apr 04, 2023 |
| MSI           | CR61 2M/CX61 2OC/CX61 2O... | [ceeafa59a2](https://linux-hardware.org/?probe=ceeafa59a2) | Apr 04, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | [a1dceb9ce7](https://linux-hardware.org/?probe=a1dceb9ce7) | Apr 04, 2023 |
| HUAWEI        | HVY-WXX9                    | [ec6a09a6ba](https://linux-hardware.org/?probe=ec6a09a6ba) | Apr 04, 2023 |
| Acer          | NU-SF314-42-R3S0            | [6f56806ef1](https://linux-hardware.org/?probe=6f56806ef1) | Apr 04, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [1dbae9d685](https://linux-hardware.org/?probe=1dbae9d685) | Apr 04, 2023 |
| Dell          | XPS 15 9520                 | [1158a2ec97](https://linux-hardware.org/?probe=1158a2ec97) | Apr 04, 2023 |
| Dell          | XPS 15 9500                 | [84f877fde3](https://linux-hardware.org/?probe=84f877fde3) | Apr 04, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [86de0a83c3](https://linux-hardware.org/?probe=86de0a83c3) | Apr 04, 2023 |
| ASUSTek       | GL553VD                     | [1978d77ba2](https://linux-hardware.org/?probe=1978d77ba2) | Apr 03, 2023 |
| Acer          | Aspire 4820TG               | [ef04e5d464](https://linux-hardware.org/?probe=ef04e5d464) | Apr 03, 2023 |
| Acer          | Aspire 4820TG               | [f9eb684250](https://linux-hardware.org/?probe=f9eb684250) | Apr 03, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [661283d296](https://linux-hardware.org/?probe=661283d296) | Apr 03, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [3c10c8c51a](https://linux-hardware.org/?probe=3c10c8c51a) | Apr 03, 2023 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | [49b1cef736](https://linux-hardware.org/?probe=49b1cef736) | Apr 03, 2023 |
| HP            | Pavilion 17                 | [487bc77c07](https://linux-hardware.org/?probe=487bc77c07) | Apr 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [1c15668c5d](https://linux-hardware.org/?probe=1c15668c5d) | Apr 03, 2023 |
| ASUSTek       | ASUS ExpertBook P2451FA_... | [05261a9b98](https://linux-hardware.org/?probe=05261a9b98) | Apr 03, 2023 |
| Dell          | Inspiron 7577               | [ada2cb6e08](https://linux-hardware.org/?probe=ada2cb6e08) | Apr 02, 2023 |
| Dell          | Inspiron 7577               | [a761c8f978](https://linux-hardware.org/?probe=a761c8f978) | Apr 02, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [e800b0ff2e](https://linux-hardware.org/?probe=e800b0ff2e) | Apr 02, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [a0dddcbb95](https://linux-hardware.org/?probe=a0dddcbb95) | Apr 02, 2023 |
| Sony          | SVF1521A6EW                 | [e382f0f4f1](https://linux-hardware.org/?probe=e382f0f4f1) | Apr 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [37beaa5cbb](https://linux-hardware.org/?probe=37beaa5cbb) | Apr 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [892ffd1727](https://linux-hardware.org/?probe=892ffd1727) | Apr 02, 2023 |
| HP            | Laptop 17-ca0xxx            | [6399f19b22](https://linux-hardware.org/?probe=6399f19b22) | Apr 02, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [ba6e80b2b7](https://linux-hardware.org/?probe=ba6e80b2b7) | Apr 02, 2023 |
| Notebook      | P15SM                       | [070f808c28](https://linux-hardware.org/?probe=070f808c28) | Apr 02, 2023 |
| ASUSTek       | G71V                        | [6594dac071](https://linux-hardware.org/?probe=6594dac071) | Apr 02, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [195ab3d907](https://linux-hardware.org/?probe=195ab3d907) | Apr 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [0941828bd0](https://linux-hardware.org/?probe=0941828bd0) | Apr 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [95c5f574c9](https://linux-hardware.org/?probe=95c5f574c9) | Apr 01, 2023 |
| Lenovo        | ThinkPad L560 20F2S1AJ00    | [8987605dde](https://linux-hardware.org/?probe=8987605dde) | Apr 01, 2023 |
| Valve         | Jupiter                     | [f9083bca8d](https://linux-hardware.org/?probe=f9083bca8d) | Apr 01, 2023 |
| Google        | Lulu                        | [0183eadbc8](https://linux-hardware.org/?probe=0183eadbc8) | Apr 01, 2023 |
| Dell          | Vostro 1520                 | [2132a3308c](https://linux-hardware.org/?probe=2132a3308c) | Apr 01, 2023 |
| ASUSTek       | N752VX                      | [d426499408](https://linux-hardware.org/?probe=d426499408) | Apr 01, 2023 |
| HP            | Presario CQ58               | [e8f8f289ac](https://linux-hardware.org/?probe=e8f8f289ac) | Apr 01, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [87bc2601f3](https://linux-hardware.org/?probe=87bc2601f3) | Apr 01, 2023 |
| ASUSTek       | S551LN                      | [916adbdf9f](https://linux-hardware.org/?probe=916adbdf9f) | Apr 01, 2023 |
| Acer          | Aspire 7720                 | [073d49ce6b](https://linux-hardware.org/?probe=073d49ce6b) | Mar 31, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | [683d3101d8](https://linux-hardware.org/?probe=683d3101d8) | Mar 31, 2023 |
| Dell          | Inspiron 7577               | [5800e3859c](https://linux-hardware.org/?probe=5800e3859c) | Mar 31, 2023 |
| Acer          | Nitro AN515-54              | [9e7aa15a9f](https://linux-hardware.org/?probe=9e7aa15a9f) | Mar 31, 2023 |
| Notebook      | NL40_50GU                   | [a46afd7246](https://linux-hardware.org/?probe=a46afd7246) | Mar 31, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [81c43aeb0d](https://linux-hardware.org/?probe=81c43aeb0d) | Mar 30, 2023 |
| Apple         | MacBookAir7,2               | [d9cbbe0a35](https://linux-hardware.org/?probe=d9cbbe0a35) | Mar 30, 2023 |
| Dell          | Precision 5510              | [4bbf7f5ef2](https://linux-hardware.org/?probe=4bbf7f5ef2) | Mar 30, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [0f8c22b288](https://linux-hardware.org/?probe=0f8c22b288) | Mar 30, 2023 |
| ASUSTek       | K55A                        | [cf40bdccfc](https://linux-hardware.org/?probe=cf40bdccfc) | Mar 30, 2023 |
| ASUSTek       | K55A                        | [b6c168d185](https://linux-hardware.org/?probe=b6c168d185) | Mar 30, 2023 |
| Lenovo        | V15-ADA 82C7                | [552ad08e05](https://linux-hardware.org/?probe=552ad08e05) | Mar 30, 2023 |
| Sony          | SVF1521C2EW                 | [978ae8afac](https://linux-hardware.org/?probe=978ae8afac) | Mar 30, 2023 |
| Alienware     | m15 Ryzen Ed. R5            | [0f273e6227](https://linux-hardware.org/?probe=0f273e6227) | Mar 30, 2023 |
| Lenovo        | G700 20251                  | [7580b631a9](https://linux-hardware.org/?probe=7580b631a9) | Mar 29, 2023 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | [5c65763b9d](https://linux-hardware.org/?probe=5c65763b9d) | Mar 29, 2023 |
| Lenovo        | U41-70 80JV                 | [975da67142](https://linux-hardware.org/?probe=975da67142) | Mar 29, 2023 |
| HP            | Laptop 17-by0xxx            | [89a0332dfd](https://linux-hardware.org/?probe=89a0332dfd) | Mar 29, 2023 |
| HP            | EliteBook 8770w             | [46a3f1d497](https://linux-hardware.org/?probe=46a3f1d497) | Mar 29, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [11c94aa91b](https://linux-hardware.org/?probe=11c94aa91b) | Mar 29, 2023 |
| Toshiba       | Satellite P200              | [c55a4d3166](https://linux-hardware.org/?probe=c55a4d3166) | Mar 29, 2023 |
| Notebook      | NL40_50CU                   | [fe471635fb](https://linux-hardware.org/?probe=fe471635fb) | Mar 29, 2023 |
| Dell          | Vostro 5568                 | [0004be15a4](https://linux-hardware.org/?probe=0004be15a4) | Mar 28, 2023 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [2f1975360e](https://linux-hardware.org/?probe=2f1975360e) | Mar 28, 2023 |
| HP            | Compaq 6510b (GR680ET)      | [716c4212c7](https://linux-hardware.org/?probe=716c4212c7) | Mar 28, 2023 |
| Lenovo        | V145-15AST 81MT             | [7fff3bb217](https://linux-hardware.org/?probe=7fff3bb217) | Mar 28, 2023 |
| Acer          | Aspire E5-532G              | [35e076d9b5](https://linux-hardware.org/?probe=35e076d9b5) | Mar 28, 2023 |
| ASUSTek       | N61Jq                       | [0ca1f04770](https://linux-hardware.org/?probe=0ca1f04770) | Mar 28, 2023 |
| Sony          | SVF1521C2EW                 | [2bafb0a0e4](https://linux-hardware.org/?probe=2bafb0a0e4) | Mar 28, 2023 |
| HP            | Laptop 14s-fq2xxx           | [8b64ddb550](https://linux-hardware.org/?probe=8b64ddb550) | Mar 27, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21B9C... | [0744b26f5c](https://linux-hardware.org/?probe=0744b26f5c) | Mar 27, 2023 |
| HP            | EliteBook 840 G3            | [58d5e99cd1](https://linux-hardware.org/?probe=58d5e99cd1) | Mar 27, 2023 |
| Dell          | Latitude E5430 non-vPro     | [17794caffa](https://linux-hardware.org/?probe=17794caffa) | Mar 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [08627c5990](https://linux-hardware.org/?probe=08627c5990) | Mar 27, 2023 |
| Dell          | XPS 15 9570                 | [5be538736f](https://linux-hardware.org/?probe=5be538736f) | Mar 27, 2023 |
| Acer          | Aspire 4820TG               | [e634227889](https://linux-hardware.org/?probe=e634227889) | Mar 27, 2023 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | [7cd7234999](https://linux-hardware.org/?probe=7cd7234999) | Mar 27, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [c3dbea760e](https://linux-hardware.org/?probe=c3dbea760e) | Mar 26, 2023 |
| ASUSTek       | K50IE                       | [bde872583b](https://linux-hardware.org/?probe=bde872583b) | Mar 26, 2023 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | [2d83ebd124](https://linux-hardware.org/?probe=2d83ebd124) | Mar 26, 2023 |
| ASUSTek       | X75VD                       | [9997ce4485](https://linux-hardware.org/?probe=9997ce4485) | Mar 26, 2023 |
| MSI           | MAG Z490 TOMAHAWK           | [f9c5ae93de](https://linux-hardware.org/?probe=f9c5ae93de) | Mar 26, 2023 |
| Fujitsu Si... | AMILO Pi 3625               | [076352cb68](https://linux-hardware.org/?probe=076352cb68) | Mar 26, 2023 |
| MSI           | MAG Z490 TOMAHAWK           | [414c36eb9d](https://linux-hardware.org/?probe=414c36eb9d) | Mar 26, 2023 |
| Valve         | Jupiter                     | [b7c75f2713](https://linux-hardware.org/?probe=b7c75f2713) | Mar 26, 2023 |
| Dell          | Latitude 5520               | [47372d09fe](https://linux-hardware.org/?probe=47372d09fe) | Mar 25, 2023 |
| Dell          | Latitude 5520               | [0c69ef5724](https://linux-hardware.org/?probe=0c69ef5724) | Mar 25, 2023 |
| Packard Be... | EasyNote SB65               | [f49cf1aa7a](https://linux-hardware.org/?probe=f49cf1aa7a) | Mar 25, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | [22aa7f3036](https://linux-hardware.org/?probe=22aa7f3036) | Mar 25, 2023 |
| Dell          | XPS 9315                    | [050fede003](https://linux-hardware.org/?probe=050fede003) | Mar 25, 2023 |
| Toshiba       | KIRA                        | [e96de49ce8](https://linux-hardware.org/?probe=e96de49ce8) | Mar 25, 2023 |
| HP            | ProBook 645 G4              | [6a03f43f29](https://linux-hardware.org/?probe=6a03f43f29) | Mar 25, 2023 |
| Unknown       | Unknown                     | [fb97269a4d](https://linux-hardware.org/?probe=fb97269a4d) | Mar 24, 2023 |
| Packard Be... | H17HV                       | [c4bddccbd8](https://linux-hardware.org/?probe=c4bddccbd8) | Mar 24, 2023 |
| Dell          | Precision 3551              | [bc979e320b](https://linux-hardware.org/?probe=bc979e320b) | Mar 24, 2023 |
| Dell          | Precision 3551              | [0509bee16a](https://linux-hardware.org/?probe=0509bee16a) | Mar 24, 2023 |
| HP            | EliteBook 850 G5            | [cde421908c](https://linux-hardware.org/?probe=cde421908c) | Mar 24, 2023 |
| Lenovo        | ThinkPad Edge E530 62722... | [479f7f7a25](https://linux-hardware.org/?probe=479f7f7a25) | Mar 23, 2023 |
| HP            | Pavilion dv7                | [c0cec2e941](https://linux-hardware.org/?probe=c0cec2e941) | Mar 23, 2023 |
| Dell          | XPS 15 9510                 | [e6db3c2c26](https://linux-hardware.org/?probe=e6db3c2c26) | Mar 23, 2023 |
| Lenovo        | ThinkPad P70 20ESS2VP00     | [bb6fdb6236](https://linux-hardware.org/?probe=bb6fdb6236) | Mar 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [28cd6cb051](https://linux-hardware.org/?probe=28cd6cb051) | Mar 23, 2023 |
| Valve         | Jupiter                     | [9d1c01a6cd](https://linux-hardware.org/?probe=9d1c01a6cd) | Mar 23, 2023 |
| Toshiba       | Satellite C870-198          | [7969002105](https://linux-hardware.org/?probe=7969002105) | Mar 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [ba101f37d0](https://linux-hardware.org/?probe=ba101f37d0) | Mar 22, 2023 |
| Notebook      | P15SM                       | [082e2c3c16](https://linux-hardware.org/?probe=082e2c3c16) | Mar 21, 2023 |
| Dell          | Latitude E7240              | [a3e408033c](https://linux-hardware.org/?probe=a3e408033c) | Mar 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [8606a64427](https://linux-hardware.org/?probe=8606a64427) | Mar 21, 2023 |
| ASUSTek       | VivoBook E14 E402WAS        | [95154b40cc](https://linux-hardware.org/?probe=95154b40cc) | Mar 21, 2023 |
| Lenovo        | B50-10 80QR                 | [134bf99094](https://linux-hardware.org/?probe=134bf99094) | Mar 21, 2023 |
| MSI           | GF63 Thin 10SCSR            | [45610ce6bf](https://linux-hardware.org/?probe=45610ce6bf) | Mar 21, 2023 |
| ASUSTek       | GL553VD                     | [ea7e302020](https://linux-hardware.org/?probe=ea7e302020) | Mar 21, 2023 |
| ASUSTek       | GL553VD                     | [8ed4a1e3ba](https://linux-hardware.org/?probe=8ed4a1e3ba) | Mar 21, 2023 |
| HP            | EliteBook 850 G5            | [5ca3a1b044](https://linux-hardware.org/?probe=5ca3a1b044) | Mar 21, 2023 |
| HUAWEI        | KLVL-WXX9                   | [2da4187f91](https://linux-hardware.org/?probe=2da4187f91) | Mar 21, 2023 |
| HP            | EliteBook 840 G5            | [a204a0f2c0](https://linux-hardware.org/?probe=a204a0f2c0) | Mar 21, 2023 |
| Dell          | XPS 15 9510                 | [d23fb1d0f6](https://linux-hardware.org/?probe=d23fb1d0f6) | Mar 21, 2023 |
| Dell          | Latitude E6420              | [e564f25125](https://linux-hardware.org/?probe=e564f25125) | Mar 20, 2023 |
| HP            | Pavilion dm4                | [7983ee084c](https://linux-hardware.org/?probe=7983ee084c) | Mar 20, 2023 |
| HP            | Laptop 15s-eq1xxx           | [3aee61f2bb](https://linux-hardware.org/?probe=3aee61f2bb) | Mar 20, 2023 |
| Notebook      | NS50_70MU                   | [cb2c031349](https://linux-hardware.org/?probe=cb2c031349) | Mar 20, 2023 |
| Dell          | Latitude E5500              | [9c76627b98](https://linux-hardware.org/?probe=9c76627b98) | Mar 20, 2023 |
| Dell          | Latitude 5520               | [4153e72c6b](https://linux-hardware.org/?probe=4153e72c6b) | Mar 19, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [3387f1f1c8](https://linux-hardware.org/?probe=3387f1f1c8) | Mar 19, 2023 |
| Acer          | Swift SF514-53T             | [9d37ace881](https://linux-hardware.org/?probe=9d37ace881) | Mar 19, 2023 |
| Acer          | Swift SF514-53T             | [93ce0e9d73](https://linux-hardware.org/?probe=93ce0e9d73) | Mar 19, 2023 |
| Toshiba       | Satellite Pro C50-A-1EM     | [a49e9997f1](https://linux-hardware.org/?probe=a49e9997f1) | Mar 19, 2023 |
| ASUSTek       | X550VX                      | [dcc37300fd](https://linux-hardware.org/?probe=dcc37300fd) | Mar 19, 2023 |
| HP            | ZBook 17 G3                 | [cb3b7c5bfb](https://linux-hardware.org/?probe=cb3b7c5bfb) | Mar 19, 2023 |
| Dell          | Precision M4800             | [26912746f6](https://linux-hardware.org/?probe=26912746f6) | Mar 18, 2023 |
| HP            | OMEN by Laptop 17-an0xx     | [5a11bc39d5](https://linux-hardware.org/?probe=5a11bc39d5) | Mar 18, 2023 |
| Dell          | Inspiron 1120               | [d864592854](https://linux-hardware.org/?probe=d864592854) | Mar 18, 2023 |
| HP            | Laptop 15-db0xxx            | [bb43e46d71](https://linux-hardware.org/?probe=bb43e46d71) | Mar 18, 2023 |
| Lenovo        | ThinkPad P50 20EQS1MY00     | [beeb327f26](https://linux-hardware.org/?probe=beeb327f26) | Mar 18, 2023 |
| Acer          | Aspire 7750G                | [39d6b256fa](https://linux-hardware.org/?probe=39d6b256fa) | Mar 18, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [4ff2145364](https://linux-hardware.org/?probe=4ff2145364) | Mar 17, 2023 |
| Dell          | Precision 3520              | [2afa31184a](https://linux-hardware.org/?probe=2afa31184a) | Mar 17, 2023 |
| Dell          | Precision 3520              | [819b4aa330](https://linux-hardware.org/?probe=819b4aa330) | Mar 17, 2023 |
| Acer          | Aspire 9410                 | [b124194b0c](https://linux-hardware.org/?probe=b124194b0c) | Mar 17, 2023 |
| MSI           | GP62 6QE                    | [3db109542c](https://linux-hardware.org/?probe=3db109542c) | Mar 17, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [7cededfaa9](https://linux-hardware.org/?probe=7cededfaa9) | Mar 17, 2023 |
| TUXEDO        | Pulse 14 Gen1               | [525b267c31](https://linux-hardware.org/?probe=525b267c31) | Mar 17, 2023 |
| Dell          | Latitude E7470              | [f2dd0afe92](https://linux-hardware.org/?probe=f2dd0afe92) | Mar 17, 2023 |
| Unknown       | Unknown                     | [3eb0bf05b4](https://linux-hardware.org/?probe=3eb0bf05b4) | Mar 17, 2023 |
| HP            | Pavilion dm1                | [8707341105](https://linux-hardware.org/?probe=8707341105) | Mar 16, 2023 |
| Dell          | Vostro 1520                 | [a029e62352](https://linux-hardware.org/?probe=a029e62352) | Mar 16, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [d0ab04cac0](https://linux-hardware.org/?probe=d0ab04cac0) | Mar 16, 2023 |
| Lenovo        | ThinkPad Edge E530 62722... | [fac1a255b7](https://linux-hardware.org/?probe=fac1a255b7) | Mar 16, 2023 |
| Toshiba       | Satellite C55-A-1T6         | [71751e4045](https://linux-hardware.org/?probe=71751e4045) | Mar 16, 2023 |
| HP            | ZBook 15 G5                 | [2af12bdf73](https://linux-hardware.org/?probe=2af12bdf73) | Mar 16, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | [a01912ff82](https://linux-hardware.org/?probe=a01912ff82) | Mar 15, 2023 |
| Toshiba       | PORTEGE Z30-B               | [06db6fa9b3](https://linux-hardware.org/?probe=06db6fa9b3) | Mar 15, 2023 |
| Dell          | Inspiron 7577               | [d19eaf791f](https://linux-hardware.org/?probe=d19eaf791f) | Mar 15, 2023 |
| ASUSTek       | N751JK                      | [d148f91b52](https://linux-hardware.org/?probe=d148f91b52) | Mar 15, 2023 |
| Dell          | Inspiron 7577               | [a519acdd2e](https://linux-hardware.org/?probe=a519acdd2e) | Mar 15, 2023 |
| Lenovo        | ThinkPad X230 2325BA3       | [45533fd7eb](https://linux-hardware.org/?probe=45533fd7eb) | Mar 14, 2023 |
| HP            | Notebook                    | [de2e2f370b](https://linux-hardware.org/?probe=de2e2f370b) | Mar 14, 2023 |
| HUAWEI        | CREM-WXX9                   | [933110cc30](https://linux-hardware.org/?probe=933110cc30) | Mar 14, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [b3d9dfdb16](https://linux-hardware.org/?probe=b3d9dfdb16) | Mar 14, 2023 |
| Dell          | Inspiron 3583               | [9eaa09faf0](https://linux-hardware.org/?probe=9eaa09faf0) | Mar 14, 2023 |
| Dell          | Precision 5570              | [f0d98798a2](https://linux-hardware.org/?probe=f0d98798a2) | Mar 14, 2023 |
| Acer          | Aspire A715-74G             | [54d17115b9](https://linux-hardware.org/?probe=54d17115b9) | Mar 13, 2023 |
| Acer          | Aspire A715-74G             | [79932e56ad](https://linux-hardware.org/?probe=79932e56ad) | Mar 13, 2023 |
| Dell          | Precision 7560              | [0b0c4e4b1c](https://linux-hardware.org/?probe=0b0c4e4b1c) | Mar 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [3c4e911c6d](https://linux-hardware.org/?probe=3c4e911c6d) | Mar 13, 2023 |
| MSI           | GV62 7RE                    | [1de50d9986](https://linux-hardware.org/?probe=1de50d9986) | Mar 13, 2023 |
| Toshiba       | Satellite Pro L500          | [303f47547b](https://linux-hardware.org/?probe=303f47547b) | Mar 12, 2023 |
| Acer          | Aspire ES1-523              | [4247bd6835](https://linux-hardware.org/?probe=4247bd6835) | Mar 12, 2023 |
| Dell          | Inspiron 5565               | [9415690de2](https://linux-hardware.org/?probe=9415690de2) | Mar 12, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [4ee87a1213](https://linux-hardware.org/?probe=4ee87a1213) | Mar 12, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [406d19d44f](https://linux-hardware.org/?probe=406d19d44f) | Mar 12, 2023 |
| Chuwi         | GemiBook Pro                | [fc04961aef](https://linux-hardware.org/?probe=fc04961aef) | Mar 11, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [73fe7fd06e](https://linux-hardware.org/?probe=73fe7fd06e) | Mar 11, 2023 |
| HP            | EliteBook 840 G4            | [c4792e57b9](https://linux-hardware.org/?probe=c4792e57b9) | Mar 11, 2023 |
| BESSTAR Te... | X300                        | [3f12a2f32e](https://linux-hardware.org/?probe=3f12a2f32e) | Mar 11, 2023 |
| BESSTAR Te... | X300                        | [a6ba9c1545](https://linux-hardware.org/?probe=a6ba9c1545) | Mar 11, 2023 |
| HP            | Laptop 17-cn2xxx            | [239832f304](https://linux-hardware.org/?probe=239832f304) | Mar 11, 2023 |
| Dell          | Precision 5570              | [470ba58973](https://linux-hardware.org/?probe=470ba58973) | Mar 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [3823c10f89](https://linux-hardware.org/?probe=3823c10f89) | Mar 11, 2023 |
| Lenovo        | G505 20240                  | [201f4fc780](https://linux-hardware.org/?probe=201f4fc780) | Mar 11, 2023 |
| Lenovo        | ThinkPad P53 20QN0007FR     | [960d07f083](https://linux-hardware.org/?probe=960d07f083) | Mar 11, 2023 |
| Fujitsu Si... | LIFEBOOK E8410              | [c2230a6690](https://linux-hardware.org/?probe=c2230a6690) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | [54e498fb2e](https://linux-hardware.org/?probe=54e498fb2e) | Mar 10, 2023 |
| System76      | Gazelle Professional        | [42f5755b1d](https://linux-hardware.org/?probe=42f5755b1d) | Mar 10, 2023 |
| Dell          | Latitude 5530               | [335933aedb](https://linux-hardware.org/?probe=335933aedb) | Mar 10, 2023 |
| Lenovo        | ThinkPad Edge E530 62722... | [da07981235](https://linux-hardware.org/?probe=da07981235) | Mar 10, 2023 |
| Lenovo        | ThinkPad Edge E530 62722... | [6e55c3caff](https://linux-hardware.org/?probe=6e55c3caff) | Mar 10, 2023 |
| HP            | ProBook 430 G2              | [4f689d1291](https://linux-hardware.org/?probe=4f689d1291) | Mar 10, 2023 |
| Toshiba       | TECRA Z40-A                 | [43c7df46f9](https://linux-hardware.org/?probe=43c7df46f9) | Mar 09, 2023 |
| Toshiba       | Satellite L300              | [a35bb278ba](https://linux-hardware.org/?probe=a35bb278ba) | Mar 09, 2023 |
| Dell          | Latitude E5450              | [6a40dced5b](https://linux-hardware.org/?probe=6a40dced5b) | Mar 09, 2023 |
| HP            | Presario CQ61               | [0eab7ae44e](https://linux-hardware.org/?probe=0eab7ae44e) | Mar 09, 2023 |
| ASUSTek       | UX410UAR                    | [4fa93928b1](https://linux-hardware.org/?probe=4fa93928b1) | Mar 09, 2023 |
| Acer          | Aspire 7250                 | [026f2228a3](https://linux-hardware.org/?probe=026f2228a3) | Mar 08, 2023 |
| Fujitsu       | LIFEBOOK E734               | [a4e6e8e566](https://linux-hardware.org/?probe=a4e6e8e566) | Mar 08, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [cc67f30d28](https://linux-hardware.org/?probe=cc67f30d28) | Mar 08, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [82fee79835](https://linux-hardware.org/?probe=82fee79835) | Mar 08, 2023 |
| Toshiba       | Satellite L300              | [13418c9605](https://linux-hardware.org/?probe=13418c9605) | Mar 08, 2023 |
| ASUSTek       | X705UAR                     | [21ea5828e3](https://linux-hardware.org/?probe=21ea5828e3) | Mar 08, 2023 |
| Dell          | XPS 15 9570                 | [0312ea16b6](https://linux-hardware.org/?probe=0312ea16b6) | Mar 08, 2023 |
| Dell          | Precision 3560              | [0873d45206](https://linux-hardware.org/?probe=0873d45206) | Mar 08, 2023 |
| Dell          | Precision 3520              | [99eaeb743c](https://linux-hardware.org/?probe=99eaeb743c) | Mar 08, 2023 |
| Dell          | Precision 3520              | [acf74c7740](https://linux-hardware.org/?probe=acf74c7740) | Mar 08, 2023 |
| Dell          | XPS 15 9570                 | [fc0152a6de](https://linux-hardware.org/?probe=fc0152a6de) | Mar 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [42e5be35d6](https://linux-hardware.org/?probe=42e5be35d6) | Mar 08, 2023 |
| Acer          | Aspire ES1-732              | [03a5f04251](https://linux-hardware.org/?probe=03a5f04251) | Mar 07, 2023 |
| Chuwi         | LapBook Plus                | [55365bb7ab](https://linux-hardware.org/?probe=55365bb7ab) | Mar 07, 2023 |
| Dell          | Latitude 5590               | [10e7ed8ff6](https://linux-hardware.org/?probe=10e7ed8ff6) | Mar 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [ac92e5ce13](https://linux-hardware.org/?probe=ac92e5ce13) | Mar 07, 2023 |
| AZW           | GT-R                        | [cce9cccb8f](https://linux-hardware.org/?probe=cce9cccb8f) | Mar 07, 2023 |
| Acer          | Aspire A114-31              | [33ce987151](https://linux-hardware.org/?probe=33ce987151) | Mar 06, 2023 |
| ASUSTek       | K52JT                       | [802fe86b5c](https://linux-hardware.org/?probe=802fe86b5c) | Mar 06, 2023 |
| Dell          | Latitude 5400               | [9e2592768b](https://linux-hardware.org/?probe=9e2592768b) | Mar 06, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [28dd9d3ce4](https://linux-hardware.org/?probe=28dd9d3ce4) | Mar 06, 2023 |
| ASUSTek       | UX303LB                     | [4137763385](https://linux-hardware.org/?probe=4137763385) | Mar 06, 2023 |
| ASUSTek       | X550JX                      | [a9a82b2395](https://linux-hardware.org/?probe=a9a82b2395) | Mar 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | [9b1357d5c0](https://linux-hardware.org/?probe=9b1357d5c0) | Mar 06, 2023 |
| Sony          | SVE1513I4E                  | [76d0570787](https://linux-hardware.org/?probe=76d0570787) | Mar 05, 2023 |
| Dell          | Latitude E7450              | [1c1d26f569](https://linux-hardware.org/?probe=1c1d26f569) | Mar 05, 2023 |
| HUAWEI        | HVY-WXX9                    | [28dbdcfbb7](https://linux-hardware.org/?probe=28dbdcfbb7) | Mar 05, 2023 |
| Lenovo        | ThinkPad T550 20CJS02E00    | [d8535715f8](https://linux-hardware.org/?probe=d8535715f8) | Mar 05, 2023 |
| Acer          | Aspire 5750G                | [1c918f0aa3](https://linux-hardware.org/?probe=1c918f0aa3) | Mar 05, 2023 |
| HP            | EliteBook 6930p             | [6757b860c8](https://linux-hardware.org/?probe=6757b860c8) | Mar 05, 2023 |
| Lenovo        | G50-80 80L0                 | [6e4cec1477](https://linux-hardware.org/?probe=6e4cec1477) | Mar 05, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | [ff4621a345](https://linux-hardware.org/?probe=ff4621a345) | Mar 05, 2023 |
| Lenovo        | ThinkPad X270 20HMS4EC0D    | [108c90e7f7](https://linux-hardware.org/?probe=108c90e7f7) | Mar 05, 2023 |
| LG Electro... | R580-K.APC4BE1              | [9cac5bdcfc](https://linux-hardware.org/?probe=9cac5bdcfc) | Mar 05, 2023 |
| HP            | Pavilion g7                 | [1f09b36fde](https://linux-hardware.org/?probe=1f09b36fde) | Mar 04, 2023 |
| Acer          | Aspire 5935                 | [f76641318f](https://linux-hardware.org/?probe=f76641318f) | Mar 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [fdb3bcda29](https://linux-hardware.org/?probe=fdb3bcda29) | Mar 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | [9b0664e4d7](https://linux-hardware.org/?probe=9b0664e4d7) | Mar 04, 2023 |
| Dell          | Latitude E6230              | [1909328685](https://linux-hardware.org/?probe=1909328685) | Mar 04, 2023 |
| Dell          | Inspiron 1120               | [41f23e384c](https://linux-hardware.org/?probe=41f23e384c) | Mar 04, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [63e9a399f8](https://linux-hardware.org/?probe=63e9a399f8) | Mar 04, 2023 |
| HP            | ZBook 15 G4                 | [38a0ce48ed](https://linux-hardware.org/?probe=38a0ce48ed) | Mar 04, 2023 |
| Google        | Lulu                        | [eb4cf4fb11](https://linux-hardware.org/?probe=eb4cf4fb11) | Mar 03, 2023 |
| HP            | Pavilion 17                 | [de3dcf402a](https://linux-hardware.org/?probe=de3dcf402a) | Mar 03, 2023 |
| Dell          | Latitude E7440              | [36439d1a64](https://linux-hardware.org/?probe=36439d1a64) | Mar 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [a553120d6e](https://linux-hardware.org/?probe=a553120d6e) | Mar 03, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [c4c7ebf544](https://linux-hardware.org/?probe=c4c7ebf544) | Mar 03, 2023 |
| TUXEDO        | InfinityBook S 14 Gen6      | [756ac6782b](https://linux-hardware.org/?probe=756ac6782b) | Mar 03, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [dae34bbf69](https://linux-hardware.org/?probe=dae34bbf69) | Mar 02, 2023 |
| Acer          | Aspire 1640Z                | [915a8900d0](https://linux-hardware.org/?probe=915a8900d0) | Mar 02, 2023 |
| Dell          | Latitude E7440              | [b84f760e8e](https://linux-hardware.org/?probe=b84f760e8e) | Mar 02, 2023 |
| Apple         | MacBookPro9,2               | [75befd2e82](https://linux-hardware.org/?probe=75befd2e82) | Mar 02, 2023 |
| Dell          | Vostro 15 5510              | [96a16581c6](https://linux-hardware.org/?probe=96a16581c6) | Mar 02, 2023 |
| Dell          | Latitude 3510               | [0bad8d504d](https://linux-hardware.org/?probe=0bad8d504d) | Mar 02, 2023 |
| Dell          | XPS 15 9520                 | [e28307db49](https://linux-hardware.org/?probe=e28307db49) | Mar 01, 2023 |
| HP            | ZBook 17 G3                 | [cf6ef752c9](https://linux-hardware.org/?probe=cf6ef752c9) | Mar 01, 2023 |
| ASUSTek       | X556URK                     | [aa7492e59a](https://linux-hardware.org/?probe=aa7492e59a) | Mar 01, 2023 |
| Lenovo        | IdeaPad 720-15IKB 81AG      | [704b0f3226](https://linux-hardware.org/?probe=704b0f3226) | Mar 01, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | [bd4fd4080d](https://linux-hardware.org/?probe=bd4fd4080d) | Mar 01, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | [90d8927f0a](https://linux-hardware.org/?probe=90d8927f0a) | Mar 01, 2023 |
| HP            | Laptop 17-ca1xxx            | [7f93c1a4e3](https://linux-hardware.org/?probe=7f93c1a4e3) | Feb 28, 2023 |
| HUAWEI        | CREM-WXX9                   | [22d51a725f](https://linux-hardware.org/?probe=22d51a725f) | Feb 28, 2023 |
| Dell          | Latitude 5400               | [00cd14a724](https://linux-hardware.org/?probe=00cd14a724) | Feb 28, 2023 |
| HP            | Laptop 15s-eq1xxx           | [c070966ad7](https://linux-hardware.org/?probe=c070966ad7) | Feb 28, 2023 |
| Apple         | MacBookAir3,1               | [573644760d](https://linux-hardware.org/?probe=573644760d) | Feb 28, 2023 |
| Acer          | Aspire A515-57              | [6c511739eb](https://linux-hardware.org/?probe=6c511739eb) | Feb 28, 2023 |
| Timi          | TM1701                      | [ab658664bb](https://linux-hardware.org/?probe=ab658664bb) | Feb 28, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | [b5a4a1809f](https://linux-hardware.org/?probe=b5a4a1809f) | Feb 28, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | [88745e1f03](https://linux-hardware.org/?probe=88745e1f03) | Feb 28, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20C0S23... | [3cd99ed8f4](https://linux-hardware.org/?probe=3cd99ed8f4) | Feb 28, 2023 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [594ff7091b](https://linux-hardware.org/?probe=594ff7091b) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [1f80bce21e](https://linux-hardware.org/?probe=1f80bce21e) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [08e6c7285a](https://linux-hardware.org/?probe=08e6c7285a) | Feb 27, 2023 |
| Acer          | Aspire E5-571               | [5f035002e1](https://linux-hardware.org/?probe=5f035002e1) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [05d3c9f96c](https://linux-hardware.org/?probe=05d3c9f96c) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [f70d3317a2](https://linux-hardware.org/?probe=f70d3317a2) | Feb 27, 2023 |
| Dell          | Latitude 5400               | [b788c61c95](https://linux-hardware.org/?probe=b788c61c95) | Feb 27, 2023 |
| HP            | Pavilion m6                 | [1e9d802ab6](https://linux-hardware.org/?probe=1e9d802ab6) | Feb 27, 2023 |
| ASUSTek       | E402MA                      | [c49b50f583](https://linux-hardware.org/?probe=c49b50f583) | Feb 27, 2023 |
| ASUSTek       | E402MA                      | [4083a9232f](https://linux-hardware.org/?probe=4083a9232f) | Feb 27, 2023 |
| HP            | Pavilion m6                 | [0d35b0b080](https://linux-hardware.org/?probe=0d35b0b080) | Feb 27, 2023 |
| HP            | Pavilion 17                 | [dfd1ca1091](https://linux-hardware.org/?probe=dfd1ca1091) | Feb 27, 2023 |
| Lenovo        | G50-80 80L0                 | [19727a16be](https://linux-hardware.org/?probe=19727a16be) | Feb 26, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [e763fc25e7](https://linux-hardware.org/?probe=e763fc25e7) | Feb 26, 2023 |
| HONOR         | BBR-WAX9                    | [3fe348fb3f](https://linux-hardware.org/?probe=3fe348fb3f) | Feb 26, 2023 |
| Lenovo        | ThinkPad T430u 3353A11      | [3f35f45bf0](https://linux-hardware.org/?probe=3f35f45bf0) | Feb 26, 2023 |
| Dell          | Latitude E5450              | [62ce48db27](https://linux-hardware.org/?probe=62ce48db27) | Feb 26, 2023 |
| Lenovo        | ThinkPad T420 4236EJ3       | [d0b043c11b](https://linux-hardware.org/?probe=d0b043c11b) | Feb 26, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | [b80c1e685f](https://linux-hardware.org/?probe=b80c1e685f) | Feb 26, 2023 |
| Acer          | Nitro AN515-52              | [08d12e1049](https://linux-hardware.org/?probe=08d12e1049) | Feb 26, 2023 |
| Dell          | Latitude E5530 non-vPro     | [5634c4795c](https://linux-hardware.org/?probe=5634c4795c) | Feb 26, 2023 |
| HUAWEI        | CREM-WXX9                   | [c026a25fb2](https://linux-hardware.org/?probe=c026a25fb2) | Feb 26, 2023 |
| HP            | ENVY 17                     | [dea1551bf3](https://linux-hardware.org/?probe=dea1551bf3) | Feb 26, 2023 |
| Valve         | Jupiter                     | [1b7321e88d](https://linux-hardware.org/?probe=1b7321e88d) | Feb 26, 2023 |
| HP            | ENVY 17                     | [0f347a1b6c](https://linux-hardware.org/?probe=0f347a1b6c) | Feb 26, 2023 |
| HP            | Laptop 15s-eq2xxx           | [3142c6a90c](https://linux-hardware.org/?probe=3142c6a90c) | Feb 25, 2023 |
| Chuwi         | GemiBook Pro                | [9894743527](https://linux-hardware.org/?probe=9894743527) | Feb 25, 2023 |
| Dell          | XPS 9315                    | [86fea0e08a](https://linux-hardware.org/?probe=86fea0e08a) | Feb 25, 2023 |
| Sony          | SVE1513B1EW                 | [c99ef001e4](https://linux-hardware.org/?probe=c99ef001e4) | Feb 25, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [f1db9ad466](https://linux-hardware.org/?probe=f1db9ad466) | Feb 25, 2023 |
| Chuwi         | GemiBook Pro                | [f8f1005d73](https://linux-hardware.org/?probe=f8f1005d73) | Feb 24, 2023 |
| HP            | Pavilion dv6000 (GF657EA... | [fe52d35d1a](https://linux-hardware.org/?probe=fe52d35d1a) | Feb 24, 2023 |
| Lenovo        | G50-80 80E5                 | [3f28f459bf](https://linux-hardware.org/?probe=3f28f459bf) | Feb 24, 2023 |
| Lenovo        | G50-80 80E5                 | [8ed4158090](https://linux-hardware.org/?probe=8ed4158090) | Feb 24, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | [041c57ebe6](https://linux-hardware.org/?probe=041c57ebe6) | Feb 24, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | [6b2160527d](https://linux-hardware.org/?probe=6b2160527d) | Feb 23, 2023 |
| ASUSTek       | T100TAF                     | [4fce660f2d](https://linux-hardware.org/?probe=4fce660f2d) | Feb 23, 2023 |
| ASUSTek       | ROG Strix G713RW_G713RW     | [5368c6d0a2](https://linux-hardware.org/?probe=5368c6d0a2) | Feb 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [8fde9cab5c](https://linux-hardware.org/?probe=8fde9cab5c) | Feb 22, 2023 |
| Toshiba       | Satellite L655              | [2b16b06c7f](https://linux-hardware.org/?probe=2b16b06c7f) | Feb 22, 2023 |
| Lenovo        | G50-80 80E5                 | [51b83f1e27](https://linux-hardware.org/?probe=51b83f1e27) | Feb 22, 2023 |
| Lenovo        | V130-15IGM 81HL             | [40205862f6](https://linux-hardware.org/?probe=40205862f6) | Feb 22, 2023 |
| Notebook      | N8xEJEK                     | [1548ea7cab](https://linux-hardware.org/?probe=1548ea7cab) | Feb 21, 2023 |
| Notebook      | N8xEJEK                     | [a8a28d6f2b](https://linux-hardware.org/?probe=a8a28d6f2b) | Feb 21, 2023 |
| ASUSTek       | X55VD                       | [6b71d8369a](https://linux-hardware.org/?probe=6b71d8369a) | Feb 21, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [9978852d07](https://linux-hardware.org/?probe=9978852d07) | Feb 21, 2023 |
| Apple         | MacBookPro9,2               | [80df77e6a1](https://linux-hardware.org/?probe=80df77e6a1) | Feb 21, 2023 |
| Dell          | Vostro 15 7510              | [df764baed8](https://linux-hardware.org/?probe=df764baed8) | Feb 21, 2023 |
| HP            | Pavilion 15                 | [9aee694156](https://linux-hardware.org/?probe=9aee694156) | Feb 21, 2023 |
| HP            | Pavilion 15                 | [fafd1c2888](https://linux-hardware.org/?probe=fafd1c2888) | Feb 21, 2023 |
| ASUSTek       | K70IC                       | [e5aad61a1b](https://linux-hardware.org/?probe=e5aad61a1b) | Feb 21, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [751f76b561](https://linux-hardware.org/?probe=751f76b561) | Feb 21, 2023 |
| ASUSTek       | UX410UQK                    | [0a23974b1b](https://linux-hardware.org/?probe=0a23974b1b) | Feb 21, 2023 |
| Dell          | XPS 13 7390                 | [a3ed8101b1](https://linux-hardware.org/?probe=a3ed8101b1) | Feb 20, 2023 |
| Toshiba       | TECRA R850                  | [082f5559c7](https://linux-hardware.org/?probe=082f5559c7) | Feb 20, 2023 |
| Lenovo        | IdeaPad L340-17API 81LY     | [e26b379150](https://linux-hardware.org/?probe=e26b379150) | Feb 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [ba0144c710](https://linux-hardware.org/?probe=ba0144c710) | Feb 20, 2023 |
| Toshiba       | Satellite L655              | [a5124a64e6](https://linux-hardware.org/?probe=a5124a64e6) | Feb 19, 2023 |
| ASUSTek       | P553UA                      | [b999af6719](https://linux-hardware.org/?probe=b999af6719) | Feb 19, 2023 |
| HP            | EliteBook 8440p             | [24e71c037b](https://linux-hardware.org/?probe=24e71c037b) | Feb 18, 2023 |
| Sony          | VGN-NW21MF_W                | [e46cfcff64](https://linux-hardware.org/?probe=e46cfcff64) | Feb 17, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [bfeb3ab070](https://linux-hardware.org/?probe=bfeb3ab070) | Feb 17, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [12f305c12f](https://linux-hardware.org/?probe=12f305c12f) | Feb 17, 2023 |
| Toshiba       | Satellite C70-C-18E         | [7642482909](https://linux-hardware.org/?probe=7642482909) | Feb 17, 2023 |
| Apple         | MacBookPro9,1               | [4ab4c99cab](https://linux-hardware.org/?probe=4ab4c99cab) | Feb 17, 2023 |
| eMachines     | eMachiens G443              | [096a4bb9e4](https://linux-hardware.org/?probe=096a4bb9e4) | Feb 16, 2023 |
| HP            | Pavilion dv6500             | [95a9115968](https://linux-hardware.org/?probe=95a9115968) | Feb 16, 2023 |
| ASUSTek       | X75VD                       | [81c64d5916](https://linux-hardware.org/?probe=81c64d5916) | Feb 16, 2023 |
| Dell          | Precision 5570              | [d5f9d13ae3](https://linux-hardware.org/?probe=d5f9d13ae3) | Feb 16, 2023 |
| Dell          | Latitude 7330               | [caf4a2b3ac](https://linux-hardware.org/?probe=caf4a2b3ac) | Feb 16, 2023 |
| Dell          | Vostro 1510                 | [a9e4d33e06](https://linux-hardware.org/?probe=a9e4d33e06) | Feb 16, 2023 |
| Dell          | Precision 5750              | [7b814aee7c](https://linux-hardware.org/?probe=7b814aee7c) | Feb 16, 2023 |
| ASUSTek       | S551LN                      | [676c244c1d](https://linux-hardware.org/?probe=676c244c1d) | Feb 16, 2023 |
| ASUSTek       | N76VZ                       | [ed9bd6b127](https://linux-hardware.org/?probe=ed9bd6b127) | Feb 16, 2023 |
| HP            | 250 G6 Notebook PC          | [745ae4d0fb](https://linux-hardware.org/?probe=745ae4d0fb) | Feb 15, 2023 |
| Dell          | Precision 5570              | [d0f2fa25c3](https://linux-hardware.org/?probe=d0f2fa25c3) | Feb 15, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [0b622220d7](https://linux-hardware.org/?probe=0b622220d7) | Feb 15, 2023 |
| Alienware     | m15 Ryzen Ed. R5            | [542f27e209](https://linux-hardware.org/?probe=542f27e209) | Feb 14, 2023 |
| ASUSTek       | ROG Strix G731GU_G731GU     | [977650806e](https://linux-hardware.org/?probe=977650806e) | Feb 14, 2023 |
| Lenovo        | ThinkPad X240 20AMS4AN00    | [ec8fbb6350](https://linux-hardware.org/?probe=ec8fbb6350) | Feb 14, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [25dbf25c62](https://linux-hardware.org/?probe=25dbf25c62) | Feb 14, 2023 |
| Google        | Lulu                        | [15fa093522](https://linux-hardware.org/?probe=15fa093522) | Feb 14, 2023 |
| Lenovo        | ThinkPad L520 5015AH2       | [8f2bad1d66](https://linux-hardware.org/?probe=8f2bad1d66) | Feb 13, 2023 |
| HUAWEI        | CREM-WXX9                   | [02ae55d12c](https://linux-hardware.org/?probe=02ae55d12c) | Feb 13, 2023 |
| Thomson       | N17V3C4WH128                | [57eacd1a37](https://linux-hardware.org/?probe=57eacd1a37) | Feb 13, 2023 |
| Dell          | Inspiron 14 5420            | [45862fde09](https://linux-hardware.org/?probe=45862fde09) | Feb 13, 2023 |
| Dell          | Inspiron 14 5420            | [8153aeb3fb](https://linux-hardware.org/?probe=8153aeb3fb) | Feb 13, 2023 |
| Dell          | XPS 13 9370                 | [36bf8af789](https://linux-hardware.org/?probe=36bf8af789) | Feb 13, 2023 |
| Dell          | Latitude E6320              | [32ad32fb45](https://linux-hardware.org/?probe=32ad32fb45) | Feb 13, 2023 |
| Apple         | MacBookPro13,3              | [628feb8b19](https://linux-hardware.org/?probe=628feb8b19) | Feb 13, 2023 |
| Apple         | MacBookPro13,3              | [2f591ee9e3](https://linux-hardware.org/?probe=2f591ee9e3) | Feb 13, 2023 |
| Toshiba       | Satellite Pro R50-B         | [0634db3367](https://linux-hardware.org/?probe=0634db3367) | Feb 13, 2023 |
| ASUSTek       | G771JM                      | [af72d8c72f](https://linux-hardware.org/?probe=af72d8c72f) | Feb 12, 2023 |
| MSI           | GF65 Thin 9SEXR             | [7d57fccbf0](https://linux-hardware.org/?probe=7d57fccbf0) | Feb 12, 2023 |
| HUAWEI        | CREM-WXX9                   | [09266b8b06](https://linux-hardware.org/?probe=09266b8b06) | Feb 12, 2023 |
| Acer          | Extensa 2540                | [6e7e38afb4](https://linux-hardware.org/?probe=6e7e38afb4) | Feb 12, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [095fa7a182](https://linux-hardware.org/?probe=095fa7a182) | Feb 12, 2023 |
| Acer          | Aspire E5-574G              | [cdbd2ad757](https://linux-hardware.org/?probe=cdbd2ad757) | Feb 12, 2023 |
| Dell          | Vostro 15 3515              | [22d5eabee5](https://linux-hardware.org/?probe=22d5eabee5) | Feb 11, 2023 |
| HP            | Notebook                    | [523c719e5b](https://linux-hardware.org/?probe=523c719e5b) | Feb 11, 2023 |
| HP            | Notebook                    | [d4e29128dd](https://linux-hardware.org/?probe=d4e29128dd) | Feb 11, 2023 |
| Gigabyte      | GB-BKi5(H)A-7200            | [57ff1b0fe3](https://linux-hardware.org/?probe=57ff1b0fe3) | Feb 11, 2023 |
| ASUSTek       | G75VW                       | [e2eeee26af](https://linux-hardware.org/?probe=e2eeee26af) | Feb 11, 2023 |
| Dell          | Precision 5570              | [8398c80e6b](https://linux-hardware.org/?probe=8398c80e6b) | Feb 11, 2023 |
| Lenovo        | ThinkPad T480s 20L7001PF... | [f6d2fc27d1](https://linux-hardware.org/?probe=f6d2fc27d1) | Feb 10, 2023 |
| Acer          | TravelMate 7730             | [a9a9e21b5a](https://linux-hardware.org/?probe=a9a9e21b5a) | Feb 10, 2023 |
| MSI           | GE60 2QE                    | [4d8865f2bd](https://linux-hardware.org/?probe=4d8865f2bd) | Feb 10, 2023 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | [9da08e5265](https://linux-hardware.org/?probe=9da08e5265) | Feb 10, 2023 |
| Acer          | Aspire E1-570               | [df85a15b13](https://linux-hardware.org/?probe=df85a15b13) | Feb 10, 2023 |
| ASUSTek       | X541UAK                     | [fb254cca56](https://linux-hardware.org/?probe=fb254cca56) | Feb 10, 2023 |
| Lenovo        | Yoga 500-14ACL 80NA         | [3bdbc623a8](https://linux-hardware.org/?probe=3bdbc623a8) | Feb 10, 2023 |
| Lenovo        | Yoga 500-15IBD 80N6         | [077853b2db](https://linux-hardware.org/?probe=077853b2db) | Feb 09, 2023 |
| Acer          | Swift SF314-54              | [8d92b8e7c5](https://linux-hardware.org/?probe=8d92b8e7c5) | Feb 09, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [a77dd320a8](https://linux-hardware.org/?probe=a77dd320a8) | Feb 09, 2023 |
| Dell          | Precision 5570              | [52cd3af211](https://linux-hardware.org/?probe=52cd3af211) | Feb 09, 2023 |
| Sony          | SVE1513U1ESI                | [77dafc35f5](https://linux-hardware.org/?probe=77dafc35f5) | Feb 09, 2023 |
| Lenovo        | ThinkPad L512 2550WC7       | [8b8efe2813](https://linux-hardware.org/?probe=8b8efe2813) | Feb 09, 2023 |
| Dell          | Precision M6500             | [dcabcd8d63](https://linux-hardware.org/?probe=dcabcd8d63) | Feb 09, 2023 |
| Sony          | VGN-NS38E_S                 | [891c180950](https://linux-hardware.org/?probe=891c180950) | Feb 08, 2023 |
| HUAWEI        | CREM-WXX9                   | [965758f3ea](https://linux-hardware.org/?probe=965758f3ea) | Feb 08, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [cc897fe72d](https://linux-hardware.org/?probe=cc897fe72d) | Feb 08, 2023 |
| EXTRA Comp... | A9100                       | [67278c37d9](https://linux-hardware.org/?probe=67278c37d9) | Feb 08, 2023 |
| Fujitsu       | LIFEBOOK U7411              | [fcd6a27cd6](https://linux-hardware.org/?probe=fcd6a27cd6) | Feb 08, 2023 |
| Dell          | Precision 5570              | [6c257e667d](https://linux-hardware.org/?probe=6c257e667d) | Feb 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [b07e05a4ed](https://linux-hardware.org/?probe=b07e05a4ed) | Feb 08, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [d37cc19110](https://linux-hardware.org/?probe=d37cc19110) | Feb 08, 2023 |
| Dell          | Precision 5570              | [e81b3de663](https://linux-hardware.org/?probe=e81b3de663) | Feb 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [eca3a05d41](https://linux-hardware.org/?probe=eca3a05d41) | Feb 07, 2023 |
| Notebook      | NL5xNU                      | [b7fb43ba75](https://linux-hardware.org/?probe=b7fb43ba75) | Feb 07, 2023 |
| HP            | Pavilion 17                 | [9bd81582a4](https://linux-hardware.org/?probe=9bd81582a4) | Feb 07, 2023 |
| HP            | Pavilion 17                 | [45eb87271b](https://linux-hardware.org/?probe=45eb87271b) | Feb 07, 2023 |
| TUXEDO        | InfinityBook S 14 Gen6      | [9e019a0396](https://linux-hardware.org/?probe=9e019a0396) | Feb 07, 2023 |
| Dell          | Precision 5570              | [d279e97c00](https://linux-hardware.org/?probe=d279e97c00) | Feb 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [cd59ace4d1](https://linux-hardware.org/?probe=cd59ace4d1) | Feb 07, 2023 |
| Toshiba       | Satellite C870-196          | [85ded7d8d0](https://linux-hardware.org/?probe=85ded7d8d0) | Feb 06, 2023 |
| ASUSTek       | K72JT                       | [9620d41f62](https://linux-hardware.org/?probe=9620d41f62) | Feb 06, 2023 |
| Dell          | Latitude E5430 non-vPro     | [7d2d46a579](https://linux-hardware.org/?probe=7d2d46a579) | Feb 06, 2023 |
| Dell          | Latitude 5520               | [e9782f4262](https://linux-hardware.org/?probe=e9782f4262) | Feb 06, 2023 |
| ASUSTek       | X71Q                        | [c89b078e8f](https://linux-hardware.org/?probe=c89b078e8f) | Feb 06, 2023 |
| Notebook      | NLx0MU                      | [9a05c88c59](https://linux-hardware.org/?probe=9a05c88c59) | Feb 06, 2023 |
| Lenovo        | ThinkPad X250 20CLS2TQ22    | [112a65a03e](https://linux-hardware.org/?probe=112a65a03e) | Feb 06, 2023 |
| Notebook      | NJ50_70CU                   | [c0c9951f8d](https://linux-hardware.org/?probe=c0c9951f8d) | Feb 05, 2023 |
| Acer          | Nitro AN515-45              | [bb420e8f71](https://linux-hardware.org/?probe=bb420e8f71) | Feb 05, 2023 |
| HP            | Pro x2 612 G1 Tablet        | [6e00c72683](https://linux-hardware.org/?probe=6e00c72683) | Feb 05, 2023 |
| HP            | Laptop 17-ak0xx             | [ed6c6cc366](https://linux-hardware.org/?probe=ed6c6cc366) | Feb 05, 2023 |
| Acer          | Aspire A317-53              | [2f56f41681](https://linux-hardware.org/?probe=2f56f41681) | Feb 05, 2023 |
| Sony          | VPCEH1E1E                   | [76589a7570](https://linux-hardware.org/?probe=76589a7570) | Feb 05, 2023 |
| Google        | Rabbid                      | [e309afd2d9](https://linux-hardware.org/?probe=e309afd2d9) | Feb 05, 2023 |
| Sony          | VGN-Z31MN_B                 | [bfb9a55ce9](https://linux-hardware.org/?probe=bfb9a55ce9) | Feb 05, 2023 |
| Acer          | Nitro AN517-52              | [e409f042e2](https://linux-hardware.org/?probe=e409f042e2) | Feb 05, 2023 |
| Google        | Rabbid                      | [3afddd7ab1](https://linux-hardware.org/?probe=3afddd7ab1) | Feb 05, 2023 |
| Toshiba       | Satellite C660              | [8d67e1438d](https://linux-hardware.org/?probe=8d67e1438d) | Feb 05, 2023 |
| Lenovo        | ThinkPad X260 20F5S65B0J    | [cca484a94e](https://linux-hardware.org/?probe=cca484a94e) | Feb 04, 2023 |
| ASUSTek       | UX331UA                     | [4b5a781cb4](https://linux-hardware.org/?probe=4b5a781cb4) | Feb 04, 2023 |
| HUAWEI        | CREM-WXX9                   | [43a0910ff6](https://linux-hardware.org/?probe=43a0910ff6) | Feb 04, 2023 |
| Apple         | MacBookPro8,1               | [9765b77a43](https://linux-hardware.org/?probe=9765b77a43) | Feb 04, 2023 |
| Dell          | Precision 5570              | [11d65e48fa](https://linux-hardware.org/?probe=11d65e48fa) | Feb 04, 2023 |
| MSI           | GF63 Thin 11UD              | [8b60b63594](https://linux-hardware.org/?probe=8b60b63594) | Feb 04, 2023 |
| Dell          | Precision 5570              | [5378f40d0d](https://linux-hardware.org/?probe=5378f40d0d) | Feb 04, 2023 |
| Dell          | G3 3500                     | [a25e0c9862](https://linux-hardware.org/?probe=a25e0c9862) | Feb 03, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [001a819e3d](https://linux-hardware.org/?probe=001a819e3d) | Feb 03, 2023 |
| HP            | Laptop 14s-fq2xxx           | [f63797ea26](https://linux-hardware.org/?probe=f63797ea26) | Feb 03, 2023 |
| Lenovo        | ThinkPad P53 20QNCTO1WW     | [cc7e8a75d3](https://linux-hardware.org/?probe=cc7e8a75d3) | Feb 03, 2023 |
| HUAWEI        | BOM-WXX9                    | [9b453ade5b](https://linux-hardware.org/?probe=9b453ade5b) | Feb 03, 2023 |
| HUAWEI        | BOM-WXX9                    | [2d0b0d4330](https://linux-hardware.org/?probe=2d0b0d4330) | Feb 02, 2023 |
| HUAWEI        | CREM-WXX9                   | [f794d33e76](https://linux-hardware.org/?probe=f794d33e76) | Feb 02, 2023 |
| HP            | EliteBook 840 G2            | [7dd8dceb80](https://linux-hardware.org/?probe=7dd8dceb80) | Feb 02, 2023 |
| HP            | EliteBook 840 G2            | [3339c49f38](https://linux-hardware.org/?probe=3339c49f38) | Feb 02, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [80921f3386](https://linux-hardware.org/?probe=80921f3386) | Feb 01, 2023 |
| Lenovo        | ThinkPad X230 23259S9       | [3d9e74535f](https://linux-hardware.org/?probe=3d9e74535f) | Feb 01, 2023 |
| Dell          | Inspiron 5570               | [d186290a3f](https://linux-hardware.org/?probe=d186290a3f) | Feb 01, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [e477495ef6](https://linux-hardware.org/?probe=e477495ef6) | Feb 01, 2023 |
| Lenovo        | ThinkPad T400 6473PMG       | [07cba1c44b](https://linux-hardware.org/?probe=07cba1c44b) | Feb 01, 2023 |
| ASUSTek       | S551LN                      | [b7361dbc53](https://linux-hardware.org/?probe=b7361dbc53) | Feb 01, 2023 |
| Dell          | Inspiron 7501               | [426493e8a5](https://linux-hardware.org/?probe=426493e8a5) | Feb 01, 2023 |
| HP            | Notebook                    | [3cea0a0519](https://linux-hardware.org/?probe=3cea0a0519) | Jan 31, 2023 |
| Dell          | G3 3500                     | [4b519ab8a8](https://linux-hardware.org/?probe=4b519ab8a8) | Jan 31, 2023 |
| Acer          | Aspire E5-575G              | [463b7f859f](https://linux-hardware.org/?probe=463b7f859f) | Jan 31, 2023 |
| Dell          | Inspiron 7400               | [a6b124fd34](https://linux-hardware.org/?probe=a6b124fd34) | Jan 31, 2023 |
| HP            | Notebook                    | [82d58b21c4](https://linux-hardware.org/?probe=82d58b21c4) | Jan 31, 2023 |
| Dell          | Latitude 7410               | [fd07971a70](https://linux-hardware.org/?probe=fd07971a70) | Jan 31, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [4a2fcb6bd0](https://linux-hardware.org/?probe=4a2fcb6bd0) | Jan 31, 2023 |
| HUAWEI        | WRTB-WXX9                   | [60967eaaaf](https://linux-hardware.org/?probe=60967eaaaf) | Jan 31, 2023 |
| Lenovo        | ThinkPad T500 2055AZ1       | [1086813401](https://linux-hardware.org/?probe=1086813401) | Jan 30, 2023 |
| Lenovo        | ThinkPad T500 2055AZ1       | [0b43f40c2a](https://linux-hardware.org/?probe=0b43f40c2a) | Jan 30, 2023 |
| Acer          | Aspire E5-575G              | [532f5a8dbe](https://linux-hardware.org/?probe=532f5a8dbe) | Jan 30, 2023 |
| Acer          | Aspire M5-581TG             | [970a402846](https://linux-hardware.org/?probe=970a402846) | Jan 30, 2023 |
| Acer          | Aspire M5-581TG             | [c2d425d254](https://linux-hardware.org/?probe=c2d425d254) | Jan 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [1ecef01472](https://linux-hardware.org/?probe=1ecef01472) | Jan 30, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [a5d6a22838](https://linux-hardware.org/?probe=a5d6a22838) | Jan 30, 2023 |
| Dell          | Latitude 7390               | [b154892be4](https://linux-hardware.org/?probe=b154892be4) | Jan 30, 2023 |
| HP            | ENVY Laptop 13-ah1xxx       | [360756b46a](https://linux-hardware.org/?probe=360756b46a) | Jan 30, 2023 |
| HUAWEI        | MACHD-WXX9                  | [cac5b8faa5](https://linux-hardware.org/?probe=cac5b8faa5) | Jan 29, 2023 |
| HP            | ZBook 14 G2                 | [4b1e1bc7e1](https://linux-hardware.org/?probe=4b1e1bc7e1) | Jan 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [47246aa8b5](https://linux-hardware.org/?probe=47246aa8b5) | Jan 29, 2023 |
| MSI           | CR700                       | [35d1ff1eac](https://linux-hardware.org/?probe=35d1ff1eac) | Jan 29, 2023 |
| Intel         | Unknown                     | [f387a4b732](https://linux-hardware.org/?probe=f387a4b732) | Jan 29, 2023 |
| Intel         | Unknown                     | [79aa357327](https://linux-hardware.org/?probe=79aa357327) | Jan 29, 2023 |
| HP            | ProBook 650 G1              | [830394a75e](https://linux-hardware.org/?probe=830394a75e) | Jan 29, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [90644628b4](https://linux-hardware.org/?probe=90644628b4) | Jan 29, 2023 |
| ASUSTek       | X550LB                      | [9590dd2f30](https://linux-hardware.org/?probe=9590dd2f30) | Jan 28, 2023 |
| Dell          | Latitude 7280               | [358f4c431f](https://linux-hardware.org/?probe=358f4c431f) | Jan 28, 2023 |
| Dell          | Latitude 7280               | [903e0489c4](https://linux-hardware.org/?probe=903e0489c4) | Jan 28, 2023 |
| Lenovo        | ThinkPad T430u 3353A11      | [c93d5da3f1](https://linux-hardware.org/?probe=c93d5da3f1) | Jan 28, 2023 |
| ASUSTek       | UX410UAR                    | [e9ac16c8ef](https://linux-hardware.org/?probe=e9ac16c8ef) | Jan 28, 2023 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | [57e0449f0f](https://linux-hardware.org/?probe=57e0449f0f) | Jan 28, 2023 |
| Valve         | Jupiter                     | [be17d6fd70](https://linux-hardware.org/?probe=be17d6fd70) | Jan 27, 2023 |
| TUXEDO        | InfinityBook S 15 Gen6      | [f5ebfcecc5](https://linux-hardware.org/?probe=f5ebfcecc5) | Jan 27, 2023 |
| HP            | Laptop 17-cp0xxx            | [e87b8175b1](https://linux-hardware.org/?probe=e87b8175b1) | Jan 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [56cb1ce2a6](https://linux-hardware.org/?probe=56cb1ce2a6) | Jan 27, 2023 |
| ASUSTek       | K73E                        | [66e0036452](https://linux-hardware.org/?probe=66e0036452) | Jan 27, 2023 |
| ASUSTek       | K73E                        | [91f049a01d](https://linux-hardware.org/?probe=91f049a01d) | Jan 27, 2023 |
| Dell          | Latitude E6420              | [a772965137](https://linux-hardware.org/?probe=a772965137) | Jan 27, 2023 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [117d80ff4d](https://linux-hardware.org/?probe=117d80ff4d) | Jan 27, 2023 |
| Lenovo        | ThinkPad T430u 3353A11      | [cf42b2f763](https://linux-hardware.org/?probe=cf42b2f763) | Jan 26, 2023 |
| Dell          | Latitude 5420               | [379a2dc9ab](https://linux-hardware.org/?probe=379a2dc9ab) | Jan 26, 2023 |
| Dell          | Latitude 5420               | [eec8ef8ddb](https://linux-hardware.org/?probe=eec8ef8ddb) | Jan 26, 2023 |
| HP            | 625                         | [06c4fa5119](https://linux-hardware.org/?probe=06c4fa5119) | Jan 25, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [7403ca2f73](https://linux-hardware.org/?probe=7403ca2f73) | Jan 25, 2023 |
| ASUSTek       | X510UAR                     | [7996de313e](https://linux-hardware.org/?probe=7996de313e) | Jan 25, 2023 |
| ASUSTek       | X510UAR                     | [3f4e15d14a](https://linux-hardware.org/?probe=3f4e15d14a) | Jan 25, 2023 |
| Toshiba       | Satellite Pro R50-B         | [d08118920b](https://linux-hardware.org/?probe=d08118920b) | Jan 25, 2023 |
| Lenovo        | ThinkPad L380 20M6S2YE00    | [e6c626133e](https://linux-hardware.org/?probe=e6c626133e) | Jan 25, 2023 |
| TrekStor      | Surfbook A13B               | [4306d9ba1c](https://linux-hardware.org/?probe=4306d9ba1c) | Jan 25, 2023 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [148b797f1a](https://linux-hardware.org/?probe=148b797f1a) | Jan 25, 2023 |
| ASUSTek       | X301A1                      | [f9ea8894f0](https://linux-hardware.org/?probe=f9ea8894f0) | Jan 25, 2023 |
| Sony          | VGN-NW21MF_W                | [dd4ac0a026](https://linux-hardware.org/?probe=dd4ac0a026) | Jan 24, 2023 |
| ASUSTek       | X540LJ                      | [41c91fdc7b](https://linux-hardware.org/?probe=41c91fdc7b) | Jan 24, 2023 |
| ASUSTek       | X540LJ                      | [199569e288](https://linux-hardware.org/?probe=199569e288) | Jan 24, 2023 |
| HP            | ProBook 6570b               | [841250ba59](https://linux-hardware.org/?probe=841250ba59) | Jan 24, 2023 |
| HP            | EliteBook 2560p             | [f57750e125](https://linux-hardware.org/?probe=f57750e125) | Jan 24, 2023 |
| Dell          | Precision 3551              | [1338d3df20](https://linux-hardware.org/?probe=1338d3df20) | Jan 23, 2023 |
| MSI           | Stealth GS66 12UH           | [9e79dca70b](https://linux-hardware.org/?probe=9e79dca70b) | Jan 23, 2023 |
| Dell          | Inspiron 7537               | [9181895f24](https://linux-hardware.org/?probe=9181895f24) | Jan 23, 2023 |
| Dell          | Latitude E4310              | [c32e006e62](https://linux-hardware.org/?probe=c32e006e62) | Jan 23, 2023 |
| Dell          | Latitude E4310              | [5045d5e911](https://linux-hardware.org/?probe=5045d5e911) | Jan 23, 2023 |
| Lenovo        | G50-70 20351                | [e0da886a95](https://linux-hardware.org/?probe=e0da886a95) | Jan 23, 2023 |
| ASUSTek       | T300CHI                     | [bc020f2d3e](https://linux-hardware.org/?probe=bc020f2d3e) | Jan 23, 2023 |
| Lenovo        | ThinkPad X200 7458VL3       | [3a91fa2c72](https://linux-hardware.org/?probe=3a91fa2c72) | Jan 23, 2023 |
| MSI           | PX60 6QE                    | [d820232c9c](https://linux-hardware.org/?probe=d820232c9c) | Jan 22, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [bc070879ba](https://linux-hardware.org/?probe=bc070879ba) | Jan 22, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [75f64e4cd4](https://linux-hardware.org/?probe=75f64e4cd4) | Jan 22, 2023 |
| Acer          | Aspire E1-570               | [30b3f2f346](https://linux-hardware.org/?probe=30b3f2f346) | Jan 22, 2023 |
| HP            | ProBook 4330s               | [f96c2452d3](https://linux-hardware.org/?probe=f96c2452d3) | Jan 22, 2023 |
| Lenovo        | ThinkPad P51 20HJS16Q0K     | [00e6c3575f](https://linux-hardware.org/?probe=00e6c3575f) | Jan 22, 2023 |
| Dell          | Latitude E5470              | [1a2810f035](https://linux-hardware.org/?probe=1a2810f035) | Jan 22, 2023 |
| Lenovo        | ThinkPad X260 20F5S4BY00    | [873bf3c874](https://linux-hardware.org/?probe=873bf3c874) | Jan 22, 2023 |
| HP            | 625                         | [838d72399b](https://linux-hardware.org/?probe=838d72399b) | Jan 22, 2023 |
| Dell          | XPS 15 9520                 | [893ebdd842](https://linux-hardware.org/?probe=893ebdd842) | Jan 22, 2023 |
| Lenovo        | ThinkPad E480 20KNCTO1WW    | [68ff3c02cb](https://linux-hardware.org/?probe=68ff3c02cb) | Jan 22, 2023 |
| ASUSTek       | G750JM                      | [8cb76e0d6d](https://linux-hardware.org/?probe=8cb76e0d6d) | Jan 22, 2023 |
| Dell          | G15 5510                    | [7cee6347e3](https://linux-hardware.org/?probe=7cee6347e3) | Jan 22, 2023 |
| MSI           | PS42 Modern 8MO             | [dfb621ce10](https://linux-hardware.org/?probe=dfb621ce10) | Jan 22, 2023 |
| MSI           | PS42 Modern 8MO             | [e1d7b236d3](https://linux-hardware.org/?probe=e1d7b236d3) | Jan 22, 2023 |
| Danew         | Dbook 131                   | [08911c133e](https://linux-hardware.org/?probe=08911c133e) | Jan 22, 2023 |
| Dell          | G3 3500                     | [941c11250c](https://linux-hardware.org/?probe=941c11250c) | Jan 21, 2023 |
| HP            | 625                         | [9a8a243973](https://linux-hardware.org/?probe=9a8a243973) | Jan 21, 2023 |
| Acer          | Aspire E1-570               | [9a0a65b69a](https://linux-hardware.org/?probe=9a0a65b69a) | Jan 21, 2023 |
| ASUSTek       | N751JK                      | [a67a4d078f](https://linux-hardware.org/?probe=a67a4d078f) | Jan 21, 2023 |
| Dell          | G7 7700                     | [427a79e665](https://linux-hardware.org/?probe=427a79e665) | Jan 21, 2023 |
| MSI           | GP75 Leopard 9SD            | [5b41a33a67](https://linux-hardware.org/?probe=5b41a33a67) | Jan 21, 2023 |
| Acer          | Predator PH315-52           | [5e28e4cbdc](https://linux-hardware.org/?probe=5e28e4cbdc) | Jan 21, 2023 |
| Acer          | Aspire 1640                 | [5b271fa3eb](https://linux-hardware.org/?probe=5b271fa3eb) | Jan 21, 2023 |
| Acer          | Aspire 1640                 | [fb70812654](https://linux-hardware.org/?probe=fb70812654) | Jan 21, 2023 |
| HP            | Laptop 15-dw0xxx            | [8de3cfc52e](https://linux-hardware.org/?probe=8de3cfc52e) | Jan 21, 2023 |
| HP            | EliteBook Folio 9480m       | [cf1b67c224](https://linux-hardware.org/?probe=cf1b67c224) | Jan 21, 2023 |
| HP            | EliteBook 840 G3            | [06f6499264](https://linux-hardware.org/?probe=06f6499264) | Jan 21, 2023 |
| MSI           | Katana GF66 12UC            | [543136f475](https://linux-hardware.org/?probe=543136f475) | Jan 20, 2023 |
| MSI           | CR650                       | [3d3a46f5c6](https://linux-hardware.org/?probe=3d3a46f5c6) | Jan 20, 2023 |
| MSI           | CR650                       | [7d3b1f25c4](https://linux-hardware.org/?probe=7d3b1f25c4) | Jan 20, 2023 |
| Dell          | Inspiron 5391               | [050e28c342](https://linux-hardware.org/?probe=050e28c342) | Jan 20, 2023 |
| Dell          | Latitude 7410               | [488f794ad5](https://linux-hardware.org/?probe=488f794ad5) | Jan 20, 2023 |
| Acer          | Aspire A515-57              | [3041b852df](https://linux-hardware.org/?probe=3041b852df) | Jan 20, 2023 |
| Dell          | Inspiron 14 5410            | [beaa2fdddb](https://linux-hardware.org/?probe=beaa2fdddb) | Jan 20, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [ccf1934924](https://linux-hardware.org/?probe=ccf1934924) | Jan 20, 2023 |
| Acer          | Swift SF314-57              | [6a813e0dd0](https://linux-hardware.org/?probe=6a813e0dd0) | Jan 20, 2023 |
| ASUSTek       | ROG Strix G533QS_G533QS     | [105b2daa8e](https://linux-hardware.org/?probe=105b2daa8e) | Jan 20, 2023 |
| Dell          | Precision 3551              | [4ff5a0ab8d](https://linux-hardware.org/?probe=4ff5a0ab8d) | Jan 19, 2023 |
| Apple         | MacBookPro8,1               | [b7f8407c8f](https://linux-hardware.org/?probe=b7f8407c8f) | Jan 19, 2023 |
| Dell          | XPS 15 9500                 | [606ba17221](https://linux-hardware.org/?probe=606ba17221) | Jan 19, 2023 |
| Lenovo        | IdeaPad 320-17AST 80XW      | [ae0457cc50](https://linux-hardware.org/?probe=ae0457cc50) | Jan 19, 2023 |
| Dell          | Latitude E5440              | [b1ac8af8ad](https://linux-hardware.org/?probe=b1ac8af8ad) | Jan 19, 2023 |
| Dell          | Latitude E5440              | [9b6d732a7c](https://linux-hardware.org/?probe=9b6d732a7c) | Jan 19, 2023 |
| Toshiba       | Satellite C70-A             | [ffaa715bdd](https://linux-hardware.org/?probe=ffaa715bdd) | Jan 19, 2023 |
| ASUSTek       | VivoBook E14 E402WAS        | [39f2ca64d4](https://linux-hardware.org/?probe=39f2ca64d4) | Jan 19, 2023 |
| Dell          | Vostro 1720                 | [1d06cb4ad8](https://linux-hardware.org/?probe=1d06cb4ad8) | Jan 18, 2023 |
| ASUSTek       | UX32VD                      | [7851952137](https://linux-hardware.org/?probe=7851952137) | Jan 18, 2023 |
| ASUSTek       | X411UN                      | [fad0f7ce44](https://linux-hardware.org/?probe=fad0f7ce44) | Jan 18, 2023 |
| Apple         | MacBookPro5,5               | [3dba9611d3](https://linux-hardware.org/?probe=3dba9611d3) | Jan 18, 2023 |
| Gigabyte      | P15FV5                      | [5a03ba32c0](https://linux-hardware.org/?probe=5a03ba32c0) | Jan 18, 2023 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | [04d0c02d29](https://linux-hardware.org/?probe=04d0c02d29) | Jan 18, 2023 |
| Dell          | Inspiron 7537               | [95cc108754](https://linux-hardware.org/?probe=95cc108754) | Jan 18, 2023 |
| Packard Be... | EasyNote LE69KB             | [b1caf1d323](https://linux-hardware.org/?probe=b1caf1d323) | Jan 17, 2023 |
| Dell          | Latitude 5500               | [e0ae9cb026](https://linux-hardware.org/?probe=e0ae9cb026) | Jan 17, 2023 |
| Toshiba       | Satellite L655D             | [38b26485d3](https://linux-hardware.org/?probe=38b26485d3) | Jan 17, 2023 |
| Lenovo        | ThinkPad T61 766112G        | [fb772cc0cf](https://linux-hardware.org/?probe=fb772cc0cf) | Jan 17, 2023 |
| Dell          | Latitude E5540              | [e8e30eb563](https://linux-hardware.org/?probe=e8e30eb563) | Jan 17, 2023 |
| Dell          | Vostro 1720                 | [d02dee9ab2](https://linux-hardware.org/?probe=d02dee9ab2) | Jan 17, 2023 |
| Dell          | Inspiron 14 5418            | [e3bfdaa6a4](https://linux-hardware.org/?probe=e3bfdaa6a4) | Jan 17, 2023 |
| Dell          | Latitude 5410               | [c97379d747](https://linux-hardware.org/?probe=c97379d747) | Jan 17, 2023 |
| MSI           | GP70 2OD                    | [7405037963](https://linux-hardware.org/?probe=7405037963) | Jan 17, 2023 |
| HP            | ZBook 14 G2                 | [d501532972](https://linux-hardware.org/?probe=d501532972) | Jan 17, 2023 |
| Toshiba       | Satellite A200              | [68ae2ab1d0](https://linux-hardware.org/?probe=68ae2ab1d0) | Jan 17, 2023 |
| HP            | EliteBook 820 G3            | [4abc3c8796](https://linux-hardware.org/?probe=4abc3c8796) | Jan 17, 2023 |
| Dell          | Studio 1735                 | [96d3df9639](https://linux-hardware.org/?probe=96d3df9639) | Jan 17, 2023 |
| Google        | Lulu                        | [b0e2a5a9b3](https://linux-hardware.org/?probe=b0e2a5a9b3) | Jan 16, 2023 |
| Samsung       | R530/R730/P530              | [e6752958eb](https://linux-hardware.org/?probe=e6752958eb) | Jan 16, 2023 |
| Acer          | Aspire 8942G                | [907b837cec](https://linux-hardware.org/?probe=907b837cec) | Jan 16, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [7100a33e7e](https://linux-hardware.org/?probe=7100a33e7e) | Jan 15, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [9ac2f0ab83](https://linux-hardware.org/?probe=9ac2f0ab83) | Jan 15, 2023 |
| HP            | Compaq 15                   | [ddfd4fd188](https://linux-hardware.org/?probe=ddfd4fd188) | Jan 15, 2023 |
| Dell          | Latitude E6420              | [3594f88292](https://linux-hardware.org/?probe=3594f88292) | Jan 15, 2023 |
| Toshiba       | TECRA A11                   | [3d58fc9423](https://linux-hardware.org/?probe=3d58fc9423) | Jan 15, 2023 |
| HP            | EliteBook 840 G2            | [4850c49a4a](https://linux-hardware.org/?probe=4850c49a4a) | Jan 15, 2023 |
| HP            | EliteBook 840 G2            | [972e3e026a](https://linux-hardware.org/?probe=972e3e026a) | Jan 15, 2023 |
| Acer          | Nitro AN515-44              | [f1e7eba4ca](https://linux-hardware.org/?probe=f1e7eba4ca) | Jan 15, 2023 |
| HP            | ZBook 14 G2                 | [239512c0c1](https://linux-hardware.org/?probe=239512c0c1) | Jan 15, 2023 |
| Acer          | Aspire 7250                 | [bcb2916be8](https://linux-hardware.org/?probe=bcb2916be8) | Jan 15, 2023 |
| HP            | EliteBook 8570w             | [53eb92efda](https://linux-hardware.org/?probe=53eb92efda) | Jan 15, 2023 |
| Dell          | Inspiron 5749               | [445264f815](https://linux-hardware.org/?probe=445264f815) | Jan 15, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/France/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 966       | 17.91%  |
| Ubuntu 22.04       | 368       | 6.82%   |
| Ubuntu 18.04       | 310       | 5.75%   |
| Debian 11          | 208       | 3.86%   |
| OpenMandriva 4.2   | 174       | 3.23%   |
| OpenMandriva 4.3   | 146       | 2.71%   |
| Linux Mint 20.3    | 124       | 2.3%    |
| Xubuntu 20.04      | 108       | 2%      |
| Arch Rolling       | 84        | 1.56%   |
| Arch               | 80        | 1.48%   |
| OpenMandriva 23.01 | 74        | 1.37%   |
| Ubuntu 21.10       | 71        | 1.32%   |
| Debian 10          | 69        | 1.28%   |
| Linux Mint 21.1    | 68        | 1.26%   |
| Linux Mint 20.2    | 64        | 1.19%   |
| Ubuntu 19.10       | 59        | 1.09%   |
| Zorin 16           | 58        | 1.08%   |
| Ubuntu 21.04       | 57        | 1.06%   |
| Ubuntu 20.10       | 53        | 0.98%   |
| Manjaro            | 53        | 0.98%   |
| Linux Mint 19.3    | 50        | 0.93%   |
| Xubuntu 18.04      | 49        | 0.91%   |
| Fedora 33          | 49        | 0.91%   |
| Fedora 37          | 47        | 0.87%   |
| Fedora 34          | 45        | 0.83%   |
| Ubuntu 22.10       | 44        | 0.82%   |
| OpenMandriva 23.03 | 44        | 0.82%   |
| Linux Mint 21      | 44        | 0.82%   |
| Linux Mint 20.1    | 43        | 0.8%    |
| Kubuntu 20.04      | 42        | 0.78%   |
| Pop!_OS 22.04      | 41        | 0.76%   |
| Fedora 32          | 40        | 0.74%   |
| Ubuntu 19.04       | 39        | 0.72%   |
| Linux Mint 20      | 39        | 0.72%   |
| Fedora 36          | 39        | 0.72%   |
| KDE neon 20.04     | 37        | 0.69%   |
| Pop!_OS 20.04      | 36        | 0.67%   |
| Ubuntu MATE 20.04  | 35        | 0.65%   |
| Fedora 35          | 35        | 0.65%   |
| Lubuntu 20.04      | 34        | 0.63%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1916      | 37.5%   |
| OpenMandriva  | 465       | 9.1%    |
| Linux Mint    | 441       | 8.63%   |
| Debian        | 356       | 6.97%   |
| Fedora        | 274       | 5.36%   |
| Xubuntu       | 206       | 4.03%   |
| Arch          | 162       | 3.17%   |
| Pop!_OS       | 145       | 2.84%   |
| Manjaro       | 140       | 2.74%   |
| Kubuntu       | 125       | 2.45%   |
| Zorin         | 86        | 1.68%   |
| ROSA          | 75        | 1.47%   |
| Ubuntu MATE   | 69        | 1.35%   |
| Lubuntu       | 65        | 1.27%   |
| KDE neon      | 56        | 1.1%    |
| openSUSE      | 47        | 0.92%   |
| Endless       | 43        | 0.84%   |
| Kali          | 40        | 0.78%   |
| Gentoo        | 35        | 0.68%   |
| ArcoLinux     | 32        | 0.63%   |
| Elementary    | 30        | 0.59%   |
| Ubuntu Budgie | 28        | 0.55%   |
| SteamOS       | 24        | 0.47%   |
| Ubuntu Unity  | 22        | 0.43%   |
| Parrot        | 19        | 0.37%   |
| BlackPanther  | 19        | 0.37%   |
| EndeavourOS   | 18        | 0.35%   |
| LMDE          | 16        | 0.31%   |
| Ubuntu Studio | 11        | 0.22%   |
| MX            | 11        | 0.22%   |
| CentOS        | 11        | 0.22%   |
| Kaisen        | 9         | 0.18%   |
| NixOS         | 7         | 0.14%   |
| Clear Linux   | 7         | 0.14%   |
| Peppermint    | 6         | 0.12%   |
| Mageia        | 6         | 0.12%   |
| Linux Lite    | 6         | 0.12%   |
| Xero          | 5         | 0.1%    |
| RHEL          | 5         | 0.1%    |
| LinuxFX       | 4         | 0.08%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 164       | 2.79%   |
| 5.16.7-desktop-1omv4003  | 137       | 2.33%   |
| 5.15.0-56-generic        | 80        | 1.36%   |
| 5.4.0-42-generic         | 73        | 1.24%   |
| 6.1.1-desktop-1omv2290   | 65        | 1.11%   |
| 5.15.0-58-generic        | 59        | 1.01%   |
| 5.15.0-52-generic        | 52        | 0.89%   |
| 5.11.0-38-generic        | 51        | 0.87%   |
| 5.4.0-58-generic         | 44        | 0.75%   |
| 5.4.0-52-generic         | 44        | 0.75%   |
| 5.15.0-48-generic        | 44        | 0.75%   |
| 5.11.0-27-generic        | 42        | 0.72%   |
| 5.4.0-26-generic         | 40        | 0.68%   |
| 6.2.6-desktop-1omv2390   | 39        | 0.66%   |
| 5.4.0-48-generic         | 36        | 0.61%   |
| 5.8.0-50-generic         | 35        | 0.6%    |
| 5.15.0-46-generic        | 35        | 0.6%    |
| 5.11.0-37-generic        | 35        | 0.6%    |
| 5.8.0-43-generic         | 33        | 0.56%   |
| 5.4.0-91-generic         | 33        | 0.56%   |
| 5.4.0-65-generic         | 33        | 0.56%   |
| 5.8.0-44-generic         | 32        | 0.55%   |
| 5.19.0-35-generic        | 32        | 0.55%   |
| 5.13.0-30-generic        | 32        | 0.55%   |
| 5.11.0-43-generic        | 32        | 0.55%   |
| 5.4.0-37-generic         | 31        | 0.53%   |
| 5.15.0-43-generic        | 31        | 0.53%   |
| 5.11.0-40-generic        | 31        | 0.53%   |
| 5.19.0-41-generic        | 30        | 0.51%   |
| 5.15.0-60-generic        | 30        | 0.51%   |
| 5.15.0-47-generic        | 30        | 0.51%   |
| 5.13.0-40-generic        | 30        | 0.51%   |
| 5.19.0-38-generic        | 29        | 0.49%   |
| 5.15.0-53-generic        | 29        | 0.49%   |
| 5.11.0-34-generic        | 29        | 0.49%   |
| 5.8.0-59-generic         | 28        | 0.48%   |
| 5.8.0-48-generic         | 28        | 0.48%   |
| 5.4.0-54-generic         | 27        | 0.46%   |
| 5.15.0-41-generic        | 27        | 0.46%   |
| 5.13.0-28-generic        | 27        | 0.46%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 956       | 17.28%  |
| 5.15.0  | 607       | 10.97%  |
| 5.11.0  | 357       | 6.45%   |
| 5.8.0   | 350       | 6.33%   |
| 5.13.0  | 313       | 5.66%   |
| 5.10.0  | 240       | 4.34%   |
| 4.15.0  | 226       | 4.09%   |
| 5.19.0  | 201       | 3.63%   |
| 5.3.0   | 176       | 3.18%   |
| 5.10.14 | 165       | 2.98%   |
| 5.16.7  | 137       | 2.48%   |
| 5.0.0   | 99        | 1.79%   |
| 6.1.1   | 75        | 1.36%   |
| 4.18.0  | 66        | 1.19%   |
| 4.19.0  | 64        | 1.16%   |
| 6.2.6   | 43        | 0.78%   |
| 5.14.0  | 33        | 0.6%    |
| 6.1.0   | 32        | 0.58%   |
| 6.0.0   | 26        | 0.47%   |
| 6.2.0   | 20        | 0.36%   |
| 5.17.5  | 20        | 0.36%   |
| 5.16.0  | 19        | 0.34%   |
| 5.11.12 | 19        | 0.34%   |
| 4.18.16 | 18        | 0.33%   |
| 5.18.0  | 17        | 0.31%   |
| 5.18.12 | 15        | 0.27%   |
| 5.16.13 | 15        | 0.27%   |
| 4.9.20  | 15        | 0.27%   |
| 5.9.0   | 14        | 0.25%   |
| 5.6.0   | 14        | 0.25%   |
| 5.9.11  | 13        | 0.23%   |
| 5.17.0  | 13        | 0.23%   |
| 6.2.8   | 12        | 0.22%   |
| 5.19.12 | 12        | 0.22%   |
| 4.4.0   | 12        | 0.22%   |
| 6.0.9   | 11        | 0.2%    |
| 5.14.9  | 11        | 0.2%    |
| 4.9.0   | 11        | 0.2%    |
| 5.9.16  | 10        | 0.18%   |
| 5.7.0   | 10        | 0.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 1005      | 18.42%  |
| 5.15    | 714       | 13.09%  |
| 5.10    | 485       | 8.89%   |
| 5.11    | 408       | 7.48%   |
| 5.8     | 391       | 7.17%   |
| 5.13    | 350       | 6.42%   |
| 5.19    | 254       | 4.66%   |
| 4.15    | 226       | 4.14%   |
| 5.16    | 207       | 3.79%   |
| 5.3     | 201       | 3.68%   |
| 6.1     | 167       | 3.06%   |
| 6.2     | 121       | 2.22%   |
| 5.0     | 103       | 1.89%   |
| 5.14    | 92        | 1.69%   |
| 6.0     | 88        | 1.61%   |
| 4.18    | 86        | 1.58%   |
| 5.9     | 71        | 1.3%    |
| 4.19    | 70        | 1.28%   |
| 5.18    | 67        | 1.23%   |
| 5.17    | 62        | 1.14%   |
| 5.6     | 50        | 0.92%   |
| 4.9     | 47        | 0.86%   |
| 5.7     | 42        | 0.77%   |
| 5.12    | 38        | 0.7%    |
| 6.3     | 23        | 0.42%   |
| 5.5     | 23        | 0.42%   |
| 4.4     | 14        | 0.26%   |
| 4.1     | 11        | 0.2%    |
| 4.14    | 8         | 0.15%   |
| 5.2     | 7         | 0.13%   |
| 4.13    | 5         | 0.09%   |
| 4.12    | 5         | 0.09%   |
| 4.10    | 4         | 0.07%   |
| 3.10    | 3         | 0.05%   |
| 5.1     | 2         | 0.04%   |
| 4.20    | 2         | 0.04%   |
| 4.8     | 1         | 0.02%   |
| 4.17    | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 4851      | 97.55%  |
| i686    | 119       | 2.39%   |
| aarch64 | 2         | 0.04%   |
| Unknown | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| GNOME             | 2399      | 46.53%  |
| KDE5              | 875       | 16.97%  |
| XFCE              | 471       | 9.13%   |
| Unknown           | 422       | 8.18%   |
| X-Cinnamon        | 292       | 5.66%   |
| MATE              | 201       | 3.9%    |
| Cinnamon          | 83        | 1.61%   |
| LXQt              | 73        | 1.42%   |
| KDE               | 62        | 1.2%    |
| i3                | 56        | 1.09%   |
| KDE4              | 50        | 0.97%   |
| Budgie            | 34        | 0.66%   |
| Pantheon          | 31        | 0.6%    |
| Unity             | 23        | 0.45%   |
| LXDE              | 20        | 0.39%   |
| GNOME Flashback   | 19        | 0.37%   |
| Deepin            | 9         | 0.17%   |
| sway              | 6         | 0.12%   |
| GNOME Classic     | 6         | 0.12%   |
| awesome           | 5         | 0.1%    |
| i3-with-shmlog    | 3         | 0.06%   |
| trinity           | 2         | 0.04%   |
| bspwm             | 2         | 0.04%   |
| Yaru:ubuntu:GNOME | 1         | 0.02%   |
| xmonad            | 1         | 0.02%   |
| wmaker-common     | 1         | 0.02%   |
| qtile             | 1         | 0.02%   |
| openbox           | 1         | 0.02%   |
| Lubuntu           | 1         | 0.02%   |
| lightdm-xsession  | 1         | 0.02%   |
| ICEWM             | 1         | 0.02%   |
| Hyprland          | 1         | 0.02%   |
| GNUstep           | 1         | 0.02%   |
| Enlightenment     | 1         | 0.02%   |
| dwm-sc            | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 3972      | 77.5%   |
| Wayland | 857       | 16.72%  |
| Unknown | 218       | 4.25%   |
| Tty     | 77        | 1.5%    |
| Xcb     | 1         | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1877      | 36.34%  |
| GDM     | 930       | 18.01%  |
| SDDM    | 860       | 16.65%  |
| GDM3    | 631       | 12.22%  |
| LightDM | 613       | 11.87%  |
| TDM     | 182       | 3.52%   |
| KDM     | 48        | 0.93%   |
| XDM     | 9         | 0.17%   |
| SLiM    | 6         | 0.12%   |
| NODM    | 2         | 0.04%   |
| Ly      | 2         | 0.04%   |
| LXDM    | 2         | 0.04%   |
| GREETD  | 2         | 0.04%   |
| MDM     | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| fr_FR       | 3462      | 68.36%  |
| en_US       | 942       | 18.6%   |
| Unknown     | 394       | 7.78%   |
| en_GB       | 82        | 1.62%   |
| C           | 46        | 0.91%   |
| ru_RU       | 14        | 0.28%   |
| de_DE       | 13        | 0.26%   |
| it_IT       | 11        | 0.22%   |
| pl_PL       | 10        | 0.2%    |
| es_ES       | 9         | 0.18%   |
| fr_CH       | 8         | 0.16%   |
| POSIX       | 5         | 0.1%    |
| nl_NL       | 5         | 0.1%    |
| fr_CA       | 5         | 0.1%    |
| fr_BE       | 4         | 0.08%   |
| en_IN       | 4         | 0.08%   |
| en_IE       | 4         | 0.08%   |
| ru_UA       | 3         | 0.06%   |
| pt_PT       | 3         | 0.06%   |
| pt_BR       | 3         | 0.06%   |
| en_AU       | 3         | 0.06%   |
| sv_SE       | 2         | 0.04%   |
| ro_RO       | 2         | 0.04%   |
| hu_HU       | 2         | 0.04%   |
| en_CA       | 2         | 0.04%   |
| en_AG       | 2         | 0.04%   |
| cs_CZ       | 2         | 0.04%   |
| zh_CN       | 1         | 0.02%   |
| UTF-8       | 1         | 0.02%   |
| tr_TR       | 1         | 0.02%   |
| sk_SK       | 1         | 0.02%   |
| oc_FR       | 1         | 0.02%   |
| nb_NO       | 1         | 0.02%   |
| fr_LU       | 1         | 0.02%   |
| fr_FR@euro  | 1         | 0.02%   |
| fr_FR.UTF8  | 1         | 0.02%   |
| fr_FR.utf-8 | 1         | 0.02%   |
| es_VE       | 1         | 0.02%   |
| es_UY       | 1         | 0.02%   |
| es_AR       | 1         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 2901      | 57.2%   |
| BIOS | 2171      | 42.8%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 4088      | 80.63%  |
| Overlay  | 405       | 7.99%   |
| Btrfs    | 346       | 6.82%   |
| Unknown  | 110       | 2.17%   |
| Xfs      | 40        | 0.79%   |
| Tmpfs    | 28        | 0.55%   |
| Zfs      | 25        | 0.49%   |
| F2fs     | 10        | 0.2%    |
| Ext3     | 8         | 0.16%   |
| Ext2     | 8         | 0.16%   |
| Reiserfs | 1         | 0.02%   |
| Jfs      | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 2377      | 46.71%  |
| Unknown | 2040      | 40.09%  |
| MBR     | 672       | 13.2%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 4359      | 86.2%   |
| Yes       | 698       | 13.8%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3516      | 69.8%   |
| Yes       | 1521      | 30.2%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dell                | 886       | 17.82%  |
| Hewlett-Packard     | 831       | 16.71%  |
| ASUSTek Computer    | 820       | 16.49%  |
| Lenovo              | 818       | 16.45%  |
| Acer                | 367       | 7.38%   |
| MSI                 | 185       | 3.72%   |
| Toshiba             | 166       | 3.34%   |
| Apple               | 104       | 2.09%   |
| Notebook            | 87        | 1.75%   |
| HUAWEI              | 79        | 1.59%   |
| Samsung Electronics | 67        | 1.35%   |
| Sony                | 65        | 1.31%   |
| Packard Bell        | 58        | 1.17%   |
| TUXEDO              | 29        | 0.58%   |
| Valve               | 26        | 0.52%   |
| Timi                | 23        | 0.46%   |
| Unknown             | 23        | 0.46%   |
| UNOWHY              | 20        | 0.4%    |
| Thomson             | 20        | 0.4%    |
| Gigabyte Technology | 20        | 0.4%    |
| eMachines           | 20        | 0.4%    |
| Clevo               | 20        | 0.4%    |
| Fujitsu Siemens     | 18        | 0.36%   |
| Fujitsu             | 17        | 0.34%   |
| Alienware           | 17        | 0.34%   |
| PC Specialist       | 15        | 0.3%    |
| Google              | 14        | 0.28%   |
| Razer               | 12        | 0.24%   |
| Chuwi               | 12        | 0.24%   |
| Medion              | 11        | 0.22%   |
| Teclast             | 9         | 0.18%   |
| Intel               | 7         | 0.14%   |
| HONOR               | 7         | 0.14%   |
| BESSTAR Tech        | 6         | 0.12%   |
| System76            | 5         | 0.1%    |
| Schenker            | 4         | 0.08%   |
| Panasonic           | 4         | 0.08%   |
| LDLC                | 4         | 0.08%   |
| AZW                 | 4         | 0.08%   |
| AMI                 | 4         | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| HP Notebook                     | 40        | 0.8%    |
| Unknown                         | 40        | 0.8%    |
| HP Pavilion dv6                 | 28        | 0.56%   |
| HP Pavilion 17                  | 27        | 0.54%   |
| Valve Jupiter                   | 26        | 0.52%   |
| HP Pavilion dv7                 | 24        | 0.48%   |
| ASUS S551LN                     | 22        | 0.44%   |
| HP Pavilion g7                  | 18        | 0.36%   |
| Dell XPS 13 9310                | 18        | 0.36%   |
| HP Pavilion Notebook            | 15        | 0.3%    |
| Dell XPS 13 9380                | 15        | 0.3%    |
| Dell XPS 13 7390                | 15        | 0.3%    |
| Dell Latitude E6420             | 15        | 0.3%    |
| HUAWEI HVY-WXX9                 | 14        | 0.28%   |
| HP EliteBook 840 G3             | 14        | 0.28%   |
| Dell XPS 15 9570                | 14        | 0.28%   |
| HP Pavilion g6                  | 13        | 0.26%   |
| HP EliteBook 840 G2             | 13        | 0.26%   |
| Dell XPS 15 7590                | 13        | 0.26%   |
| Dell Latitude 5420              | 13        | 0.26%   |
| HP Pavilion 15                  | 12        | 0.24%   |
| Dell XPS 15 9500                | 12        | 0.24%   |
| Dell Latitude 5400              | 12        | 0.24%   |
| HUAWEI NBLK-WAX9X               | 11        | 0.22%   |
| HP ProBook 650 G1               | 11        | 0.22%   |
| HP OMEN by Laptop               | 11        | 0.22%   |
| Dell Latitude 7490              | 11        | 0.22%   |
| Lenovo G50-30 80G0              | 10        | 0.2%    |
| HP EliteBook 840 G8 Notebook PC | 10        | 0.2%    |
| Dell XPS 13 9370                | 10        | 0.2%    |
| Dell Latitude E6400             | 10        | 0.2%    |
| Toshiba Satellite C660          | 9         | 0.18%   |
| Lenovo G50-45 80E3              | 9         | 0.18%   |
| HP ProBook 640 G1               | 9         | 0.18%   |
| HP EliteBook 840 G1             | 9         | 0.18%   |
| Dell Latitude E5500             | 9         | 0.18%   |
| Dell Latitude 5520              | 9         | 0.18%   |
| Acer Aspire ES1-523             | 9         | 0.18%   |
| UNOWHY Y13G010S4EI              | 8         | 0.16%   |
| Lenovo Legion 5 15ACH6H 82JU    | 8         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 474       | 9.53%   |
| Dell Latitude         | 351       | 7.06%   |
| Acer Aspire           | 250       | 5.03%   |
| HP Pavilion           | 223       | 4.49%   |
| HP EliteBook          | 163       | 3.28%   |
| Lenovo IdeaPad        | 161       | 3.24%   |
| Dell XPS              | 161       | 3.24%   |
| Toshiba Satellite     | 136       | 2.74%   |
| Dell Precision        | 136       | 2.74%   |
| Dell Inspiron         | 130       | 2.61%   |
| HP ProBook            | 125       | 2.51%   |
| ASUS VivoBook         | 124       | 2.49%   |
| HP Laptop             | 76        | 1.53%   |
| Packard Bell EasyNote | 51        | 1.03%   |
| ASUS ZenBook          | 49        | 0.99%   |
| Acer Swift            | 46        | 0.93%   |
| Dell Vostro           | 43        | 0.86%   |
| Lenovo Legion         | 40        | 0.8%    |
| HP Notebook           | 40        | 0.8%    |
| ASUS ROG              | 40        | 0.8%    |
| Unknown               | 40        | 0.8%    |
| HP Compaq             | 36        | 0.72%   |
| HP ZBook              | 35        | 0.7%    |
| ASUS ASUS             | 31        | 0.62%   |
| Valve Jupiter         | 26        | 0.52%   |
| Acer Nitro            | 26        | 0.52%   |
| HP OMEN               | 24        | 0.48%   |
| HP ENVY               | 23        | 0.46%   |
| ASUS S551LN           | 22        | 0.44%   |
| ASUS TUF              | 18        | 0.36%   |
| Acer TravelMate       | 18        | 0.36%   |
| Lenovo Yoga           | 17        | 0.34%   |
| Lenovo ThinkBook      | 17        | 0.34%   |
| Dell G5               | 17        | 0.34%   |
| MSI Modern            | 16        | 0.32%   |
| Dell G3               | 16        | 0.32%   |
| Fujitsu LIFEBOOK      | 15        | 0.3%    |
| Toshiba PORTEGE       | 14        | 0.28%   |
| HUAWEI HVY-WXX9       | 14        | 0.28%   |
| Apple MacBookPro5     | 13        | 0.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 522       | 10.5%   |
| 2019    | 492       | 9.9%    |
| 2018    | 428       | 8.61%   |
| 2021    | 389       | 7.82%   |
| 2012    | 350       | 7.04%   |
| 2013    | 344       | 6.92%   |
| 2015    | 331       | 6.66%   |
| 2011    | 319       | 6.42%   |
| 2017    | 277       | 5.57%   |
| 2016    | 265       | 5.33%   |
| 2014    | 260       | 5.23%   |
| 2010    | 247       | 4.97%   |
| 2008    | 225       | 4.53%   |
| 2022    | 177       | 3.56%   |
| 2009    | 177       | 3.56%   |
| 2007    | 97        | 1.95%   |
| 2006    | 35        | 0.7%    |
| 2005    | 16        | 0.32%   |
| 2023    | 12        | 0.24%   |
| Unknown | 4         | 0.08%   |
| 2004    | 3         | 0.06%   |
| 2003    | 1         | 0.02%   |
| 2002    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 4972      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 4419      | 88.13%  |
| Enabled  | 595       | 11.87%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 4951      | 99.56%  |
| Yes  | 22        | 0.44%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1372      | 27.34%  |
| 3.01-4.0    | 1215      | 24.21%  |
| 16.01-24.0  | 883       | 17.6%   |
| 8.01-16.0   | 777       | 15.48%  |
| 32.01-64.0  | 327       | 6.52%   |
| 1.01-2.0    | 209       | 4.17%   |
| 2.01-3.0    | 92        | 1.83%   |
| 64.01-256.0 | 54        | 1.08%   |
| 24.01-32.0  | 47        | 0.94%   |
| 0.51-1.0    | 34        | 0.68%   |
| 0.01-0.5    | 6         | 0.12%   |
| Unknown     | 2         | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1910      | 35.14%  |
| 2.01-3.0   | 1394      | 25.65%  |
| 4.01-8.0   | 781       | 14.37%  |
| 3.01-4.0   | 707       | 13.01%  |
| 0.51-1.0   | 338       | 6.22%   |
| 8.01-16.0  | 228       | 4.2%    |
| 0.01-0.5   | 48        | 0.88%   |
| 16.01-24.0 | 19        | 0.35%   |
| 24.01-32.0 | 6         | 0.11%   |
| 32.01-64.0 | 2         | 0.04%   |
| Unknown    | 2         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3695      | 73.18%  |
| 2      | 1170      | 23.17%  |
| 3      | 115       | 2.28%   |
| 0      | 42        | 0.83%   |
| 4      | 16        | 0.32%   |
| 5      | 6         | 0.12%   |
| 6      | 3         | 0.06%   |
| 7      | 2         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3067      | 61.41%  |
| Yes       | 1927      | 38.59%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4052      | 81.19%  |
| No        | 939       | 18.81%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4885      | 98.13%  |
| No        | 93        | 1.87%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3829      | 76.12%  |
| No        | 1201      | 23.88%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| France  | 4972      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Paris            | 842       | 15.59%  |
| Lyon             | 117       | 2.17%   |
| Toulouse         | 97        | 1.8%    |
| Marseille        | 97        | 1.8%    |
| Nantes           | 71        | 1.31%   |
| Montpellier      | 64        | 1.18%   |
| Bordeaux         | 51        | 0.94%   |
| Lille            | 50        | 0.93%   |
| Rennes           | 49        | 0.91%   |
| Strasbourg       | 47        | 0.87%   |
| Grenoble         | 41        | 0.76%   |
| Villeurbanne     | 30        | 0.56%   |
| Roubaix          | 30        | 0.56%   |
| Brest            | 30        | 0.56%   |
| Clichy-sous-Bois | 29        | 0.54%   |
| Nice             | 27        | 0.5%    |
| Caen             | 27        | 0.5%    |
| Rouen            | 22        | 0.41%   |
| Poitiers         | 20        | 0.37%   |
| Clermont-Ferrand | 19        | 0.35%   |
| Cergy            | 19        | 0.35%   |
| Argenteuil       | 19        | 0.35%   |
| Nancy            | 18        | 0.33%   |
| Metz             | 18        | 0.33%   |
| Toulon           | 17        | 0.31%   |
| Orléans         | 17        | 0.31%   |
| La Rochelle      | 17        | 0.31%   |
| Besançon        | 17        | 0.31%   |
| Aix-en-Provence  | 17        | 0.31%   |
| Versailles       | 16        | 0.3%    |
| Tours            | 16        | 0.3%    |
| Saint-Denis      | 16        | 0.3%    |
| Palaiseau        | 16        | 0.3%    |
| Limoges          | 16        | 0.3%    |
| Pau              | 15        | 0.28%   |
| Le Mans          | 15        | 0.28%   |
| Villejuif        | 14        | 0.26%   |
| Valenciennes     | 14        | 0.26%   |
| Ivry-sur-Seine   | 14        | 0.26%   |
| Colmar           | 14        | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 948       | 1281   | 15.49%  |
| WDC                         | 664       | 835    | 10.85%  |
| Seagate                     | 642       | 819    | 10.49%  |
| Toshiba                     | 514       | 640    | 8.4%    |
| Crucial                     | 369       | 471    | 6.03%   |
| SanDisk                     | 367       | 459    | 6%      |
| SK hynix                    | 309       | 373    | 5.05%   |
| Unknown                     | 305       | 403    | 4.98%   |
| Kingston                    | 278       | 329    | 4.54%   |
| HGST                        | 266       | 318    | 4.35%   |
| Hitachi                     | 186       | 210    | 3.04%   |
| Micron Technology           | 185       | 215    | 3.02%   |
| Intel                       | 178       | 216    | 2.91%   |
| KIOXIA                      | 86        | 100    | 1.4%    |
| PNY                         | 53        | 57     | 0.87%   |
| Apple                       | 47        | 61     | 0.77%   |
| LDLC                        | 44        | 62     | 0.72%   |
| Fujitsu                     | 40        | 48     | 0.65%   |
| LITEON                      | 39        | 45     | 0.64%   |
| Transcend                   | 36        | 40     | 0.59%   |
| China                       | 35        | 41     | 0.57%   |
| SPCC                        | 31        | 34     | 0.51%   |
| Phison                      | 30        | 32     | 0.49%   |
| JMicron Technology          | 30        | 33     | 0.49%   |
| LITEONIT                    | 24        | 26     | 0.39%   |
| Micron/Crucial Technology   | 19        | 22     | 0.31%   |
| Corsair                     | 19        | 23     | 0.31%   |
| Unknown                     | 19        | 20     | 0.31%   |
| Kingston Technology Company | 18        | 20     | 0.29%   |
| A-DATA Technology           | 14        | 19     | 0.23%   |
| SSSTC                       | 12        | 15     | 0.2%    |
| Silicon Motion              | 12        | 15     | 0.2%    |
| Phison Electronics          | 12        | 12     | 0.2%    |
| Netac                       | 11        | 13     | 0.18%   |
| Emtec                       | 11        | 11     | 0.18%   |
| BHT                         | 10        | 14     | 0.16%   |
| YMTC                        | 9         | 10     | 0.15%   |
| Lite-On                     | 9         | 13     | 0.15%   |
| ASMT                        | 9         | 11     | 0.15%   |
| OCZ                         | 8         | 12     | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| HGST HTS721010A9E630 1TB           | 100       | 1.58%   |
| Seagate ST1000LM035-1RK172 1TB     | 99        | 1.56%   |
| Toshiba MQ01ABD100 1TB             | 84        | 1.32%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 83        | 1.31%   |
| Crucial CT500MX500SSD1 500GB       | 66        | 1.04%   |
| Crucial CT240BX500SSD1 240GB       | 66        | 1.04%   |
| Unknown MMC Card  32GB             | 61        | 0.96%   |
| Toshiba MQ04ABF100 1TB             | 58        | 0.91%   |
| Samsung SSD 860 EVO 500GB          | 53        | 0.84%   |
| HGST HTS541010A9E680 1TB           | 51        | 0.8%    |
| Unknown MMC Card  64GB             | 44        | 0.69%   |
| Kingston SA400S37240G 240GB SSD    | 40        | 0.63%   |
| Seagate ST500LT012-1DG142 500GB    | 39        | 0.61%   |
| SanDisk NVMe SSD Drive 512GB       | 38        | 0.6%    |
| Samsung NVMe SSD Drive 512GB       | 37        | 0.58%   |
| Seagate ST9500325AS 500GB          | 35        | 0.55%   |
| Crucial CT1000MX500SSD1 1TB        | 34        | 0.54%   |
| Toshiba MQ01ABF050 500GB           | 32        | 0.5%    |
| Seagate ST1000LM048-2E7172 1TB     | 31        | 0.49%   |
| HGST HTS725050A7E630 500GB         | 31        | 0.49%   |
| Samsung SSD 870 QVO 1TB            | 29        | 0.46%   |
| Samsung SSD 850 EVO 500GB          | 29        | 0.46%   |
| KIOXIA KBG40ZNS512G NVMe 512GB     | 28        | 0.44%   |
| WDC WD10JPVX-22JC3T0 1TB           | 27        | 0.43%   |
| Unknown MMC Card  128GB            | 25        | 0.39%   |
| Toshiba NVMe SSD Drive 512GB       | 25        | 0.39%   |
| Samsung SSD 850 EVO 250GB          | 25        | 0.39%   |
| Crucial CT480BX500SSD1 480GB       | 25        | 0.39%   |
| Crucial CT120BX500SSD1 120GB       | 25        | 0.39%   |
| Samsung NVMe SSD Drive 256GB       | 24        | 0.38%   |
| Samsung SSD 860 EVO 1TB            | 23        | 0.36%   |
| Intel NVMe SSD Drive 512GB         | 23        | 0.36%   |
| SK hynix NVMe SSD Drive 512GB      | 22        | 0.35%   |
| Seagate ST1000LM049-2GH172 1TB     | 22        | 0.35%   |
| Kingston SA400S37480G 480GB SSD    | 21        | 0.33%   |
| Samsung NVMe SSD Drive 1TB         | 20        | 0.32%   |
| HGST HTS545050A7E680 500GB         | 20        | 0.32%   |
| Seagate ST500LM021-1KJ152 500GB    | 19        | 0.3%    |
| Seagate Expansion 1TB              | 19        | 0.3%    |
| SanDisk NVMe SSD Drive 256GB       | 19        | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 633       | 803    | 31.57%  |
| WDC                 | 440       | 559    | 21.95%  |
| Toshiba             | 352       | 424    | 17.56%  |
| HGST                | 266       | 318    | 13.27%  |
| Hitachi             | 186       | 210    | 9.28%   |
| Samsung Electronics | 39        | 58     | 1.95%   |
| Fujitsu             | 39        | 47     | 1.95%   |
| Unknown             | 13        | 14     | 0.65%   |
| Apple               | 7         | 7      | 0.35%   |
| IBM/Hitachi         | 5         | 6      | 0.25%   |
| ASMT                | 4         | 6      | 0.2%    |
| JMicron Technology  | 3         | 4      | 0.15%   |
| HGST HTS            | 3         | 5      | 0.15%   |
| ASMedia             | 3         | 3      | 0.15%   |
| LaCie               | 2         | 2      | 0.1%    |
| Inateck             | 2         | 2      | 0.1%    |
| USB3.0              | 1         | 1      | 0.05%   |
| SILICONMOTION       | 1         | 1      | 0.05%   |
| PHD 3.0             | 1         | 1      | 0.05%   |
| Magnetic Data       | 1         | 1      | 0.05%   |
| Intenso             | 1         | 1      | 0.05%   |
| Generic-            | 1         | 1      | 0.05%   |
| External            | 1         | 1      | 0.05%   |
| APPLE HD            | 1         | 1      | 0.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 448       | 591    | 22.72%  |
| Crucial             | 338       | 433    | 17.14%  |
| SanDisk             | 230       | 283    | 11.66%  |
| Kingston            | 203       | 244    | 10.29%  |
| Micron Technology   | 69        | 90     | 3.5%    |
| SK hynix            | 67        | 81     | 3.4%    |
| WDC                 | 50        | 56     | 2.54%   |
| Intel               | 48        | 50     | 2.43%   |
| PNY                 | 46        | 50     | 2.33%   |
| Toshiba             | 37        | 44     | 1.88%   |
| LDLC                | 37        | 52     | 1.88%   |
| Apple               | 36        | 48     | 1.83%   |
| Transcend           | 34        | 38     | 1.72%   |
| China               | 34        | 40     | 1.72%   |
| LITEON              | 33        | 37     | 1.67%   |
| SPCC                | 27        | 30     | 1.37%   |
| LITEONIT            | 24        | 26     | 1.22%   |
| JMicron Technology  | 15        | 16     | 0.76%   |
| Emtec               | 11        | 11     | 0.56%   |
| A-DATA Technology   | 11        | 16     | 0.56%   |
| Corsair             | 10        | 13     | 0.51%   |
| BHT                 | 10        | 14     | 0.51%   |
| Netac               | 9         | 11     | 0.46%   |
| OCZ                 | 8         | 12     | 0.41%   |
| KingSpec            | 8         | 9      | 0.41%   |
| Dogfish             | 7         | 10     | 0.35%   |
| Teclast             | 6         | 8      | 0.3%    |
| Patriot             | 6         | 6      | 0.3%    |
| Intenso             | 6         | 7      | 0.3%    |
| SABRENT             | 5         | 5      | 0.25%   |
| Plextor             | 5         | 10     | 0.25%   |
| Fanxiang            | 5         | 5      | 0.25%   |
| ASMT                | 5         | 5      | 0.25%   |
| Verbatim            | 4         | 4      | 0.2%    |
| KingDian            | 4         | 5      | 0.2%    |
| Unknown             | 4         | 4      | 0.2%    |
| Unknown             | 3         | 4      | 0.15%   |
| TCSUNBOW            | 3         | 4      | 0.15%   |
| BAITITON            | 3         | 3      | 0.15%   |
| Union Memory        | 2         | 2      | 0.1%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1943      | 2476   | 33.2%   |
| SSD     | 1819      | 2453   | 31.08%  |
| NVMe    | 1713      | 2216   | 29.27%  |
| MMC     | 308       | 418    | 5.26%   |
| Unknown | 69        | 76     | 1.18%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3346      | 4764   | 60.23%  |
| NVMe | 1713      | 2213   | 30.84%  |
| MMC  | 308       | 418    | 5.54%   |
| SAS  | 188       | 244    | 3.38%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2391      | 3188   | 63.74%  |
| 0.51-1.0   | 1241      | 1583   | 33.08%  |
| 1.01-2.0   | 96        | 130    | 2.56%   |
| 3.01-4.0   | 8         | 10     | 0.21%   |
| 10.01-20.0 | 7         | 8      | 0.19%   |
| 4.01-10.0  | 7         | 9      | 0.19%   |
| 2.01-3.0   | 1         | 1      | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1428      | 27.46%  |
| 251-500        | 1385      | 26.63%  |
| 501-1000       | 894       | 17.19%  |
| 1-20           | 396       | 7.61%   |
| 51-100         | 323       | 6.21%   |
| 1001-2000      | 276       | 5.31%   |
| 21-50          | 226       | 4.35%   |
| Unknown        | 126       | 2.42%   |
| More than 3000 | 74        | 1.42%   |
| 2001-3000      | 73        | 1.4%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 2083      | 38.54%  |
| 21-50          | 968       | 17.91%  |
| 101-250        | 758       | 14.02%  |
| 51-100         | 694       | 12.84%  |
| 251-500        | 417       | 7.72%   |
| 501-1000       | 240       | 4.44%   |
| Unknown        | 126       | 2.33%   |
| 1001-2000      | 70        | 1.3%    |
| 2001-3000      | 31        | 0.57%   |
| More than 3000 | 16        | 0.3%    |
| 0              | 2         | 0.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| HGST HTS721010A9E630 1TB                         | 20        | 23     | 4.32%   |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 13        | 14     | 2.81%   |
| HGST HTS541010A9E680 1TB                         | 12        | 13     | 2.59%   |
| Seagate ST9500325AS 500GB                        | 11        | 12     | 2.38%   |
| Toshiba MQ01ABD100 1TB                           | 9         | 11     | 1.94%   |
| Seagate ST500LT012-1DG142 500GB                  | 8         | 8      | 1.73%   |
| Seagate ST500LM021-1KJ152 500GB                  | 8         | 10     | 1.73%   |
| WDC WD10JPVX-22JC3T0 1TB                         | 7         | 7      | 1.51%   |
| Seagate ST1000LM035-1RK172 1TB                   | 7         | 7      | 1.51%   |
| Toshiba MQ01ABF050 500GB                         | 6         | 6      | 1.3%    |
| Toshiba MQ01ABD050 500GB                         | 5         | 5      | 1.08%   |
| Seagate ST320LT007-9ZV142 320GB                  | 5         | 6      | 1.08%   |
| Hitachi HTS547575A9E384 752GB                    | 5         | 5      | 1.08%   |
| Hitachi HTS545050A7E380 500GB                    | 5         | 5      | 1.08%   |
| HGST HTS725050A7E630 500GB                       | 5         | 5      | 1.08%   |
| HGST HTS545050A7E380 500GB                       | 5         | 5      | 1.08%   |
| Toshiba MK3265GSX 320GB                          | 4         | 5      | 0.86%   |
| SK hynix HFS256G39TND-N210A 256GB SSD            | 4         | 4      | 0.86%   |
| Hitachi HTS727575A9E364 752GB                    | 4         | 4      | 0.86%   |
| Hitachi HTS545050B9A300 500GB                    | 4         | 4      | 0.86%   |
| Hitachi HTS543232A7A384 320GB                    | 4         | 6      | 0.86%   |
| HGST HTS545050A7E680 500GB                       | 4         | 4      | 0.86%   |
| Crucial CT525MX300SSD1 528GB                     | 4         | 4      | 0.86%   |
| Toshiba MK7575GSX 752GB                          | 3         | 3      | 0.65%   |
| Toshiba MK5055GSX 500GB                          | 3         | 3      | 0.65%   |
| Toshiba MK3261GSYN 320GB                         | 3         | 3      | 0.65%   |
| SK hynix PC711 HFS512GDE9X073N 512GB             | 3         | 3      | 0.65%   |
| Seagate ST9250827AS 250GB                        | 3         | 4      | 0.65%   |
| Seagate ST1000LM048-2E7172 1TB                   | 3         | 3      | 0.65%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 3         | 3      | 0.65%   |
| Hitachi HTS547550A9E384 500GB                    | 3         | 3      | 0.65%   |
| HGST HTS541075A9E680 752GB                       | 3         | 3      | 0.65%   |
| WDC WD5000BEKT-75KA9T0 500GB                     | 2         | 2      | 0.43%   |
| WDC WD3200BPVT-80ZEST0 320GB                     | 2         | 2      | 0.43%   |
| WDC WD3200BPVT-22ZEST0 320GB                     | 2         | 2      | 0.43%   |
| WDC WD10JPCX-24UE4T0 1TB                         | 2         | 2      | 0.43%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD             | 2         | 2      | 0.43%   |
| Toshiba MQ04ABF100 1TB                           | 2         | 2      | 0.43%   |
| Toshiba MQ01ACF050 500GB                         | 2         | 2      | 0.43%   |
| Toshiba MQ01ABD075 752GB                         | 2         | 2      | 0.43%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 97        | 109    | 21%     |
| Toshiba             | 65        | 69     | 14.07%  |
| Hitachi             | 54        | 56     | 11.69%  |
| WDC                 | 53        | 56     | 11.47%  |
| HGST                | 53        | 57     | 11.47%  |
| Samsung Electronics | 25        | 28     | 5.41%   |
| SK hynix            | 17        | 19     | 3.68%   |
| SanDisk             | 16        | 17     | 3.46%   |
| Crucial             | 16        | 16     | 3.46%   |
| Intel               | 13        | 14     | 2.81%   |
| Kingston            | 12        | 12     | 2.6%    |
| Fujitsu             | 7         | 7      | 1.52%   |
| Micron Technology   | 4         | 4      | 0.87%   |
| Netac               | 2         | 2      | 0.43%   |
| LITEONIT            | 2         | 2      | 0.43%   |
| LITEON              | 2         | 2      | 0.43%   |
| LDLC                | 2         | 4      | 0.43%   |
| Intenso             | 2         | 2      | 0.43%   |
| Dogfish             | 2         | 2      | 0.43%   |
| Corsair             | 2         | 3      | 0.43%   |
| China               | 2         | 2      | 0.43%   |
| Unknown             | 1         | 1      | 0.22%   |
| TakeMS              | 1         | 1      | 0.22%   |
| SPCC                | 1         | 1      | 0.22%   |
| Phison              | 1         | 1      | 0.22%   |
| OCZ                 | 1         | 1      | 0.22%   |
| Magnetic Data       | 1         | 1      | 0.22%   |
| KingSpec            | 1         | 1      | 0.22%   |
| JMicron Technology  | 1         | 1      | 0.22%   |
| IBM/Hitachi         | 1         | 1      | 0.22%   |
| ASMT                | 1         | 1      | 0.22%   |
| ASENNO              | 1         | 1      | 0.22%   |
| Apple               | 1         | 1      | 0.22%   |
| Apacer              | 1         | 1      | 0.22%   |
| A-DATA Technology   | 1         | 1      | 0.22%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 97        | 109    | 28.87%  |
| Toshiba             | 61        | 65     | 18.15%  |
| Hitachi             | 54        | 56     | 16.07%  |
| HGST                | 53        | 57     | 15.77%  |
| WDC                 | 51        | 54     | 15.18%  |
| Samsung Electronics | 9         | 9      | 2.68%   |
| Fujitsu             | 7         | 7      | 2.08%   |
| Unknown             | 1         | 1      | 0.3%    |
| Magnetic Data       | 1         | 1      | 0.3%    |
| IBM/Hitachi         | 1         | 1      | 0.3%    |
| ASMT                | 1         | 1      | 0.3%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 333       | 361    | 72.71%  |
| SSD     | 110       | 118    | 24.02%  |
| NVMe    | 14        | 17     | 3.06%   |
| Unknown | 1         | 1      | 0.22%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD7500BPVT-22HXZT1 752GB          | 2         | 3      | 11.76%  |
| WDC WD3200BEVT-11ZCT0 320GB           | 2         | 2      | 11.76%  |
| WDC WD5000BEVT-35A0RT0 500GB          | 1         | 1      | 5.88%   |
| WDC WD10SPZX-21Z10T0 1TB              | 1         | 1      | 5.88%   |
| Toshiba MQ04ABF100 1TB                | 1         | 1      | 5.88%   |
| Toshiba MQ02ABF050H 500GB             | 1         | 1      | 5.88%   |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 5.88%   |
| Toshiba MQ01ABD075 752GB              | 1         | 1      | 5.88%   |
| Toshiba MK5055GSX 500GB               | 1         | 1      | 5.88%   |
| Toshiba MK3259GSXP 320GB              | 1         | 2      | 5.88%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 1         | 1      | 5.88%   |
| Seagate ST1000LM048-2E7172 1TB        | 1         | 1      | 5.88%   |
| Samsung Electronics HM251JI 250GB     | 1         | 1      | 5.88%   |
| HGST HTS721010A9E630 1TB              | 1         | 1      | 5.88%   |
| HGST HTS545050A7E380 500GB            | 1         | 1      | 5.88%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 7      | 35.29%  |
| Toshiba             | 6         | 7      | 35.29%  |
| HGST                | 2         | 2      | 11.76%  |
| SK hynix            | 1         | 1      | 5.88%   |
| Seagate             | 1         | 1      | 5.88%   |
| Samsung Electronics | 1         | 1      | 5.88%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 2458      | 3268   | 46.04%  |
| Detected | 2415      | 3853   | 45.23%  |
| Malfunc  | 447       | 497    | 8.37%   |
| Failed   | 17        | 19     | 0.32%   |
| Fixed    | 1         | 1      | 0.02%   |
| Limited  | 1         | 1      | 0.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 3526      | 60.16%  |
| AMD                                     | 553       | 9.44%   |
| Samsung Electronics                     | 509       | 8.68%   |
| SanDisk                                 | 295       | 5.03%   |
| SK hynix                                | 236       | 4.03%   |
| Toshiba America Info Systems            | 141       | 2.41%   |
| Micron Technology                       | 117       | 2%      |
| Kingston Technology Company             | 93        | 1.59%   |
| KIOXIA                                  | 82        | 1.4%    |
| Phison Electronics                      | 57        | 0.97%   |
| Nvidia                                  | 53        | 0.9%    |
| Micron/Crucial Technology               | 51        | 0.87%   |
| Silicon Motion                          | 16        | 0.27%   |
| Lite-On Technology                      | 16        | 0.27%   |
| Union Memory (Shenzhen)                 | 15        | 0.26%   |
| Solid State Storage Technology          | 14        | 0.24%   |
| Silicon Integrated Systems [SiS]        | 14        | 0.24%   |
| JMicron Technology                      | 12        | 0.2%    |
| Marvell Technology Group                | 11        | 0.19%   |
| Yangtze Memory Technologies             | 10        | 0.17%   |
| Lenovo                                  | 6         | 0.1%    |
| Seagate Technology                      | 4         | 0.07%   |
| Realtek Semiconductor                   | 4         | 0.07%   |
| ASMedia Technology                      | 4         | 0.07%   |
| Apple                                   | 4         | 0.07%   |
| ADATA Technology                        | 4         | 0.07%   |
| VIA Technologies                        | 3         | 0.05%   |
| Silicon Image                           | 3         | 0.05%   |
| O2 Micro                                | 3         | 0.05%   |
| ULi Electronics                         | 1         | 0.02%   |
| Shenzhen Unionmemory Information System | 1         | 0.02%   |
| Shenzhen Longsys Electronics            | 1         | 0.02%   |
| MAXIO Technology (Hangzhou)             | 1         | 0.02%   |
| INNOGRIT                                | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 450       | 7.19%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 353       | 5.64%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 343       | 5.48%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 289       | 4.62%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 224       | 3.58%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 212       | 3.39%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 203       | 3.24%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 198       | 3.16%   |
| Intel Volume Management Device NVMe RAID Controller                              | 196       | 3.13%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 174       | 2.78%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 168       | 2.68%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 165       | 2.63%   |
| Samsung NVMe SSD Controller 980                                                  | 154       | 2.46%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 128       | 2.04%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 125       | 2%      |
| Micron NVMe Storage Controller                                                   | 115       | 1.84%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 103       | 1.64%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 92        | 1.47%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 87        | 1.39%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 84        | 1.34%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 80        | 1.28%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 79        | 1.26%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 75        | 1.2%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 73        | 1.17%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 67        | 1.07%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 66        | 1.05%   |
| Intel Comet Lake SATA AHCI Controller                                            | 61        | 0.97%   |
| SK hynix Non-Volatile memory controller                                          | 57        | 0.91%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 57        | 0.91%   |
| Intel Tiger Lake-LP SATA Controller                                              | 57        | 0.91%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 57        | 0.91%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 56        | 0.89%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 51        | 0.81%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 49        | 0.78%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 49        | 0.78%   |
| Intel SSD 660P Series                                                            | 47        | 0.75%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 47        | 0.75%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 45        | 0.72%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 44        | 0.7%    |
| Toshiba America Info Systems XG5 NVMe SSD Controller                             | 38        | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 3484      | 57.54%  |
| NVMe | 1730      | 28.57%  |
| RAID | 506       | 8.36%   |
| IDE  | 335       | 5.53%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 4162      | 83.71%  |
| AMD    | 808       | 16.25%  |
| ARM    | 2         | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 102       | 2.05%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 71        | 1.43%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 70        | 1.41%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 69        | 1.39%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 67        | 1.35%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 63        | 1.27%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 62        | 1.25%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 56        | 1.13%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 54        | 1.08%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 53        | 1.06%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 49        | 0.98%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 48        | 0.96%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 48        | 0.96%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 48        | 0.96%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 47        | 0.94%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 47        | 0.94%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 46        | 0.92%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 45        | 0.9%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 45        | 0.9%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 43        | 0.86%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 42        | 0.84%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 39        | 0.78%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 37        | 0.74%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 36        | 0.72%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 36        | 0.72%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 34        | 0.68%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 34        | 0.68%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 33        | 0.66%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 32        | 0.64%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 31        | 0.62%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 31        | 0.62%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 31        | 0.62%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 30        | 0.6%    |
| Intel 12th Gen Core i7-12700H                 | 30        | 0.6%    |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 28        | 0.56%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 27        | 0.54%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 27        | 0.54%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 27        | 0.54%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 27        | 0.54%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 27        | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1192      | 23.96%  |
| Intel Core i7           | 1070      | 21.51%  |
| Other                   | 474       | 9.53%   |
| Intel Core i3           | 426       | 8.56%   |
| Intel Celeron           | 288       | 5.79%   |
| Intel Core 2 Duo        | 271       | 5.45%   |
| AMD Ryzen 5             | 178       | 3.58%   |
| AMD Ryzen 7             | 152       | 3.06%   |
| Intel Pentium           | 141       | 2.83%   |
| Intel Atom              | 99        | 1.99%   |
| Intel Pentium Dual-Core | 54        | 1.09%   |
| AMD E1                  | 52        | 1.05%   |
| AMD E2                  | 38        | 0.76%   |
| AMD A4                  | 38        | 0.76%   |
| AMD Ryzen 7 PRO         | 36        | 0.72%   |
| Intel Pentium Dual      | 34        | 0.68%   |
| AMD A6                  | 33        | 0.66%   |
| AMD Ryzen 9             | 31        | 0.62%   |
| AMD E                   | 30        | 0.6%    |
| Intel Core 2            | 28        | 0.56%   |
| Intel Core i9           | 27        | 0.54%   |
| Intel Genuine           | 23        | 0.46%   |
| AMD A8                  | 21        | 0.42%   |
| AMD Ryzen 5 PRO         | 17        | 0.34%   |
| Intel Pentium Silver    | 16        | 0.32%   |
| AMD Ryzen 3             | 16        | 0.32%   |
| AMD Athlon              | 16        | 0.32%   |
| Intel Xeon              | 15        | 0.3%    |
| Intel Pentium M         | 11        | 0.22%   |
| Intel Celeron Dual-Core | 11        | 0.22%   |
| AMD Athlon II           | 11        | 0.22%   |
| AMD Athlon X2           | 10        | 0.2%    |
| Intel Core m3           | 9         | 0.18%   |
| AMD Turion 64 X2 Mobile | 9         | 0.18%   |
| Intel Celeron M         | 8         | 0.16%   |
| AMD Athlon II Dual-Core | 8         | 0.16%   |
| AMD A12                 | 8         | 0.16%   |
| AMD Athlon 64 X2        | 7         | 0.14%   |
| AMD C-60                | 6         | 0.12%   |
| AMD A10                 | 6         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 2430      | 48.84%  |
| 4       | 1679      | 33.75%  |
| 6       | 361       | 7.26%   |
| 8       | 273       | 5.49%   |
| 1       | 118       | 2.37%   |
| 14      | 39        | 0.78%   |
| 12      | 36        | 0.72%   |
| 10      | 27        | 0.54%   |
| Unknown | 9         | 0.18%   |
| 16      | 2         | 0.04%   |
| 3       | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 4970      | 99.94%  |
| 2      | 3         | 0.06%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 3578      | 71.83%  |
| 1       | 1393      | 27.97%  |
| Unknown | 9         | 0.18%   |
| 4       | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4887      | 98.11%  |
| Unknown        | 48        | 0.96%   |
| 32-bit         | 44        | 0.88%   |
| 64-bit         | 2         | 0.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1043      | 20.28%  |
| 0x306a9    | 299       | 5.81%   |
| 0x206a7    | 288       | 5.6%    |
| 0x806c1    | 206       | 4.01%   |
| 0x806ec    | 190       | 3.7%    |
| 0x1067a    | 183       | 3.56%   |
| 0x906ea    | 174       | 3.38%   |
| 0x40651    | 152       | 2.96%   |
| 0x306d4    | 152       | 2.96%   |
| 0x406e3    | 150       | 2.92%   |
| 0x806ea    | 145       | 2.82%   |
| 0x306c3    | 141       | 2.74%   |
| 0x806e9    | 121       | 2.35%   |
| 0x20655    | 120       | 2.33%   |
| 0x6fd      | 90        | 1.75%   |
| 0xa0652    | 84        | 1.63%   |
| 0x506e3    | 83        | 1.61%   |
| 0x906e9    | 71        | 1.38%   |
| 0x08600106 | 66        | 1.28%   |
| 0x08108109 | 65        | 1.26%   |
| 0x30678    | 62        | 1.21%   |
| 0x10676    | 54        | 1.05%   |
| 0x706e5    | 51        | 0.99%   |
| 0x906a3    | 50        | 0.97%   |
| 0x806d1    | 50        | 0.97%   |
| 0x406c4    | 47        | 0.91%   |
| 0x0a50000c | 46        | 0.89%   |
| 0x806eb    | 44        | 0.86%   |
| 0x07030105 | 43        | 0.84%   |
| 0x506c9    | 41        | 0.8%    |
| 0x706a1    | 40        | 0.78%   |
| 0x406c3    | 40        | 0.78%   |
| 0x08108102 | 40        | 0.78%   |
| 0x05000119 | 37        | 0.72%   |
| 0x20652    | 36        | 0.7%    |
| 0x06006705 | 34        | 0.66%   |
| 0x906ed    | 33        | 0.64%   |
| 0x706a8    | 32        | 0.62%   |
| 0x08608103 | 31        | 0.6%    |
| 0x0700010f | 28        | 0.54%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 973       | 19.55%  |
| Haswell          | 382       | 7.67%   |
| IvyBridge        | 352       | 7.07%   |
| SandyBridge      | 326       | 6.55%   |
| Skylake          | 288       | 5.79%   |
| Penryn           | 271       | 5.44%   |
| TigerLake        | 253       | 5.08%   |
| Silvermont       | 190       | 3.82%   |
| Broadwell        | 188       | 3.78%   |
| Westmere         | 187       | 3.76%   |
| Core             | 171       | 3.44%   |
| Unknown          | 144       | 2.89%   |
| Zen 2            | 142       | 2.85%   |
| Zen+             | 117       | 2.35%   |
| CometLake        | 112       | 2.25%   |
| Icelake          | 111       | 2.23%   |
| Zen 3            | 88        | 1.77%   |
| Goldmont plus    | 87        | 1.75%   |
| Alderlake Hybrid | 79        | 1.59%   |
| Puma             | 67        | 1.35%   |
| Bobcat           | 67        | 1.35%   |
| Excavator        | 58        | 1.17%   |
| Goldmont         | 52        | 1.04%   |
| Bonnell          | 41        | 0.82%   |
| Jaguar           | 39        | 0.78%   |
| Zen              | 36        | 0.72%   |
| K10              | 32        | 0.64%   |
| K8 Hammer        | 27        | 0.54%   |
| P6               | 24        | 0.48%   |
| Nehalem          | 21        | 0.42%   |
| Piledriver       | 15        | 0.3%    |
| K8 & K10 hybrid  | 14        | 0.28%   |
| K10 Llano        | 12        | 0.24%   |
| Tremont          | 6         | 0.12%   |
| NetBurst         | 3         | 0.06%   |
| Steamroller      | 2         | 0.04%   |
| K6               | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3734      | 58.02%  |
| Nvidia                           | 1574      | 24.46%  |
| AMD                              | 1117      | 17.36%  |
| Silicon Integrated Systems [SiS] | 9         | 0.14%   |
| VIA Technologies                 | 2         | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 326       | 4.93%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 289       | 4.37%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 239       | 3.61%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 230       | 3.48%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 187       | 2.83%   |
| Intel HD Graphics 5500                                                                   | 167       | 2.52%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 165       | 2.49%   |
| Intel UHD Graphics 620                                                                   | 164       | 2.48%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 163       | 2.46%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 160       | 2.42%   |
| Intel HD Graphics 620                                                                    | 150       | 2.27%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 149       | 2.25%   |
| AMD Renoir                                                                               | 138       | 2.09%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 135       | 2.04%   |
| Intel Core Processor Integrated Graphics Controller                                      | 119       | 1.8%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 118       | 1.78%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 98        | 1.48%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 97        | 1.47%   |
| Intel HD Graphics 530                                                                    | 93        | 1.41%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 93        | 1.41%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 92        | 1.39%   |
| Intel HD Graphics 630                                                                    | 81        | 1.22%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 74        | 1.12%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 72        | 1.09%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 69        | 1.04%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 68        | 1.03%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 68        | 1.03%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 64        | 0.97%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 58        | 0.88%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 53        | 0.8%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 51        | 0.77%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 50        | 0.76%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 47        | 0.71%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 46        | 0.7%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 45        | 0.68%   |
| Nvidia GM108M [GeForce 840M]                                                             | 45        | 0.68%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 44        | 0.67%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 42        | 0.63%   |
| AMD Lucienne                                                                             | 41        | 0.62%   |
| Intel HD Graphics 500                                                                    | 40        | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 2360      | 47.32%  |
| Intel + Nvidia     | 1179      | 23.64%  |
| 1 x AMD            | 759       | 15.22%  |
| 1 x Nvidia         | 294       | 5.9%    |
| Intel + AMD        | 184       | 3.69%   |
| AMD + Nvidia       | 96        | 1.93%   |
| 2 x AMD            | 79        | 1.58%   |
| 2 x Intel          | 13        | 0.26%   |
| 1 x SiS            | 9         | 0.18%   |
| 2 x Nvidia         | 6         | 0.12%   |
| Other              | 5         | 0.1%    |
| 1 x VIA            | 2         | 0.04%   |
| Intel + 2 x Nvidia | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 4248      | 84.54%  |
| Proprietary | 651       | 12.96%  |
| Unknown     | 126       | 2.51%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 3120      | 61.36%  |
| 0.01-0.5   | 667       | 13.12%  |
| 1.01-2.0   | 566       | 11.13%  |
| 0.51-1.0   | 299       | 5.88%   |
| 3.01-4.0   | 287       | 5.64%   |
| 5.01-6.0   | 81        | 1.59%   |
| 7.01-8.0   | 40        | 0.79%   |
| 2.01-3.0   | 22        | 0.43%   |
| 8.01-16.0  | 3         | 0.06%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 1128      | 20.04%  |
| Chimei Innolux          | 758       | 13.47%  |
| LG Display              | 743       | 13.2%   |
| BOE                     | 681       | 12.1%   |
| Samsung Electronics     | 588       | 10.45%  |
| Sharp                   | 193       | 3.43%   |
| Chi Mei Optoelectronics | 149       | 2.65%   |
| Dell                    | 147       | 2.61%   |
| Iiyama                  | 111       | 1.97%   |
| Apple                   | 103       | 1.83%   |
| Lenovo                  | 94        | 1.67%   |
| PANDA                   | 75        | 1.33%   |
| LG Philips              | 72        | 1.28%   |
| Acer                    | 71        | 1.26%   |
| Hewlett-Packard         | 69        | 1.23%   |
| InfoVision              | 63        | 1.12%   |
| Goldstar                | 62        | 1.1%    |
| BenQ                    | 47        | 0.83%   |
| Ancor Communications    | 45        | 0.8%    |
| AOC                     | 41        | 0.73%   |
| Philips                 | 40        | 0.71%   |
| ViewSonic               | 31        | 0.55%   |
| CSO                     | 25        | 0.44%   |
| CPT                     | 19        | 0.34%   |
| Sony                    | 18        | 0.32%   |
| ASUSTek Computer        | 18        | 0.32%   |
| HannStar                | 15        | 0.27%   |
| Fujitsu Siemens         | 14        | 0.25%   |
| Valve                   | 11        | 0.2%    |
| Toshiba                 | 11        | 0.2%    |
| Analogix                | 11        | 0.2%    |
| Vestel Elektronik       | 10        | 0.18%   |
| Seiko/Epson             | 9         | 0.16%   |
| LGD                     | 9         | 0.16%   |
| Unknown                 | 6         | 0.11%   |
| TMX                     | 6         | 0.11%   |
| Quanta Display          | 5         | 0.09%   |
| Panasonic               | 5         | 0.09%   |
| MSI                     | 5         | 0.09%   |
| LPL                     | 5         | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 46        | 0.81%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 35        | 0.62%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch      | 34        | 0.6%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 33        | 0.58%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 28        | 0.49%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 28        | 0.49%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch            | 26        | 0.46%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch             | 26        | 0.46%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch      | 25        | 0.44%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 25        | 0.44%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch           | 24        | 0.42%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 24        | 0.42%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 24        | 0.42%   |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch            | 23        | 0.4%    |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch             | 23        | 0.4%    |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch             | 22        | 0.39%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch          | 21        | 0.37%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 382x214mm 17.2-inch           | 21        | 0.37%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 19        | 0.33%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 18        | 0.32%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 18        | 0.32%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch           | 18        | 0.32%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                   | 17        | 0.3%    |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch          | 17        | 0.3%    |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 17        | 0.3%    |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch             | 17        | 0.3%    |
| AU Optronics LCD Monitor AUO219E 1600x900 382x214mm 17.2-inch             | 17        | 0.3%    |
| AU Optronics LCD Monitor AUO109E 1600x900 382x214mm 17.2-inch             | 17        | 0.3%    |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                   | 16        | 0.28%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch  | 16        | 0.28%   |
| AU Optronics LCD Monitor AUO6287 1440x900 367x229mm 17.0-inch             | 16        | 0.28%   |
| AU Optronics LCD Monitor AUO119E 1600x900 382x214mm 17.2-inch             | 16        | 0.28%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                   | 15        | 0.26%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch            | 15        | 0.26%   |
| Samsung Electronics LCD Monitor SEC314F 1600x900 382x215mm 17.3-inch      | 14        | 0.25%   |
| Samsung Electronics LCD Monitor SDC4852 1920x1080 344x194mm 15.5-inch     | 14        | 0.25%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 14        | 0.25%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch           | 14        | 0.25%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                     | 14        | 0.25%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                     | 14        | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2286      | 43.72%  |
| 1366x768 (WXGA)    | 1274      | 24.36%  |
| 1600x900 (HD+)     | 496       | 9.49%   |
| 1280x800 (WXGA)    | 194       | 3.71%   |
| 3840x2160 (4K)     | 166       | 3.17%   |
| 1440x900 (WXGA+)   | 134       | 2.56%   |
| 1920x1200 (WUXGA)  | 132       | 2.52%   |
| 2560x1440 (QHD)    | 126       | 2.41%   |
| 1680x1050 (WSXGA+) | 59        | 1.13%   |
| 1280x1024 (SXGA)   | 34        | 0.65%   |
| 1024x600           | 33        | 0.63%   |
| 2560x1600          | 31        | 0.59%   |
| 2880x1800          | 28        | 0.54%   |
| 3440x1440          | 27        | 0.52%   |
| 3840x2400          | 24        | 0.46%   |
| 800x1280           | 21        | 0.4%    |
| 2160x1440          | 20        | 0.38%   |
| 2560x1080          | 15        | 0.29%   |
| Unknown            | 12        | 0.23%   |
| 3200x1800 (QHD+)   | 11        | 0.21%   |
| 1360x768           | 10        | 0.19%   |
| 3840x1080          | 9         | 0.17%   |
| 3000x2000          | 9         | 0.17%   |
| 1920x540           | 8         | 0.15%   |
| 1600x1200          | 7         | 0.13%   |
| 1680x945           | 6         | 0.11%   |
| 1024x768 (XGA)     | 6         | 0.11%   |
| 3840x1200          | 4         | 0.08%   |
| 3072x1920          | 4         | 0.08%   |
| 2520x1680          | 4         | 0.08%   |
| 2288x1287          | 4         | 0.08%   |
| 1920x515           | 4         | 0.08%   |
| 1400x1050          | 4         | 0.08%   |
| 2256x1504          | 3         | 0.06%   |
| 5760x2160          | 2         | 0.04%   |
| 3840x1600          | 2         | 0.04%   |
| 3456x2160          | 2         | 0.04%   |
| 3286x1080          | 2         | 0.04%   |
| 2048x1152          | 2         | 0.04%   |
| 720x1280           | 1         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 2094      | 37.25%  |
| 13      | 780       | 13.87%  |
| 17      | 776       | 13.8%   |
| 14      | 551       | 9.8%    |
| 24      | 234       | 4.16%   |
| 23      | 172       | 3.06%   |
| 27      | 159       | 2.83%   |
| 12      | 153       | 2.72%   |
| 21      | 113       | 2.01%   |
| Unknown | 73        | 1.3%    |
| 11      | 71        | 1.26%   |
| 16      | 68        | 1.21%   |
| 18      | 45        | 0.8%    |
| 10      | 44        | 0.78%   |
| 34      | 38        | 0.68%   |
| 19      | 38        | 0.68%   |
| 22      | 37        | 0.66%   |
| 31      | 21        | 0.37%   |
| 20      | 19        | 0.34%   |
| 84      | 17        | 0.3%    |
| 72      | 14        | 0.25%   |
| 7       | 11        | 0.2%    |
| 3       | 11        | 0.2%    |
| 25      | 10        | 0.18%   |
| 32      | 8         | 0.14%   |
| 40      | 7         | 0.12%   |
| 54      | 6         | 0.11%   |
| 52      | 6         | 0.11%   |
| 33      | 6         | 0.11%   |
| 26      | 6         | 0.11%   |
| 49      | 4         | 0.07%   |
| 65      | 3         | 0.05%   |
| 48      | 3         | 0.05%   |
| 43      | 3         | 0.05%   |
| 142     | 2         | 0.04%   |
| 50      | 2         | 0.04%   |
| 46      | 2         | 0.04%   |
| 36      | 2         | 0.04%   |
| 35      | 2         | 0.04%   |
| 28      | 2         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 2980      | 53.51%  |
| 351-400        | 877       | 15.75%  |
| 201-300        | 692       | 12.43%  |
| 501-600        | 525       | 9.43%   |
| 401-500        | 232       | 4.17%   |
| Unknown        | 73        | 1.31%   |
| 701-800        | 53        | 0.95%   |
| 601-700        | 37        | 0.66%   |
| 1501-2000      | 32        | 0.57%   |
| 1001-1500      | 30        | 0.54%   |
| 1-100          | 21        | 0.38%   |
| 801-900        | 12        | 0.22%   |
| More than 2000 | 2         | 0.04%   |
| 101-200        | 2         | 0.04%   |
| 901-1000       | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 4111      | 83.12%  |
| 16/10   | 597       | 12.07%  |
| 3/2     | 49        | 0.99%   |
| Unknown | 47        | 0.95%   |
| 21/9    | 44        | 0.89%   |
| 5/4     | 33        | 0.67%   |
| 4/3     | 24        | 0.49%   |
| 6/5     | 11        | 0.22%   |
| 0.67    | 11        | 0.22%   |
| 32/9    | 7         | 0.14%   |
| 3.20    | 4         | 0.08%   |
| 3.73    | 3         | 0.06%   |
| 1.00    | 2         | 0.04%   |
| 3.88    | 1         | 0.02%   |
| 0.62    | 1         | 0.02%   |
| 0.56    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 2093      | 37.33%  |
| 81-90          | 981       | 17.5%   |
| 121-130        | 640       | 11.42%  |
| 201-250        | 451       | 8.04%   |
| 71-80          | 352       | 6.28%   |
| 301-350        | 164       | 2.93%   |
| 61-70          | 143       | 2.55%   |
| 131-140        | 124       | 2.21%   |
| 151-200        | 94        | 1.68%   |
| 351-500        | 76        | 1.36%   |
| Unknown        | 73        | 1.3%    |
| 51-60          | 71        | 1.27%   |
| 251-300        | 70        | 1.25%   |
| 111-120        | 62        | 1.11%   |
| More than 1000 | 53        | 0.95%   |
| 141-150        | 52        | 0.93%   |
| 41-50          | 45        | 0.8%    |
| 1-40           | 23        | 0.41%   |
| 501-1000       | 23        | 0.41%   |
| 91-100         | 16        | 0.29%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 2171      | 39.37%  |
| 101-120       | 1689      | 30.63%  |
| 51-100        | 985       | 17.86%  |
| 161-240       | 403       | 7.31%   |
| More than 240 | 152       | 2.76%   |
| Unknown       | 73        | 1.32%   |
| 1-50          | 41        | 0.74%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 4052      | 79.61%  |
| 2     | 801       | 15.74%  |
| 0     | 132       | 2.59%   |
| 3     | 98        | 1.93%   |
| 4     | 5         | 0.1%    |
| 6     | 1         | 0.02%   |
| 5     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 2717      | 34.34%  |
| Realtek Semiconductor             | 2544      | 32.15%  |
| Qualcomm Atheros                  | 1188      | 15.02%  |
| Broadcom                          | 517       | 6.53%   |
| Broadcom Limited                  | 109       | 1.38%   |
| Marvell Technology Group          | 99        | 1.25%   |
| MediaTek                          | 97        | 1.23%   |
| Ralink                            | 82        | 1.04%   |
| ASIX Electronics                  | 54        | 0.68%   |
| Dell                              | 43        | 0.54%   |
| Samsung Electronics               | 37        | 0.47%   |
| Nvidia                            | 34        | 0.43%   |
| Xiaomi                            | 31        | 0.39%   |
| DisplayLink                       | 29        | 0.37%   |
| Ericsson Business Mobile Networks | 28        | 0.35%   |
| Sierra Wireless                   | 24        | 0.3%    |
| TP-Link                           | 22        | 0.28%   |
| Qualcomm                          | 20        | 0.25%   |
| NetGear                           | 20        | 0.25%   |
| Lenovo                            | 19        | 0.24%   |
| JMicron Technology                | 19        | 0.24%   |
| Ralink Technology                 | 18        | 0.23%   |
| Huawei Technologies               | 18        | 0.23%   |
| Attansic Technology               | 14        | 0.18%   |
| Hewlett-Packard                   | 13        | 0.16%   |
| Silicon Integrated Systems [SiS]  | 11        | 0.14%   |
| OPPO Electronics                  | 8         | 0.1%    |
| D-Link                            | 8         | 0.1%    |
| Google                            | 7         | 0.09%   |
| Apple                             | 6         | 0.08%   |
| Toshiba                           | 5         | 0.06%   |
| Fibocom                           | 5         | 0.06%   |
| D-Link System                     | 5         | 0.06%   |
| OnePlus Technology (Shenzhen)     | 4         | 0.05%   |
| ICS Advent                        | 4         | 0.05%   |
| Arduino SA                        | 4         | 0.05%   |
| VIA Technologies                  | 3         | 0.04%   |
| U-Blox                            | 3         | 0.04%   |
| Shenzhen Goodix Technology        | 3         | 0.04%   |
| Belkin Components                 | 3         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1500      | 15.75%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 412       | 4.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 272       | 2.86%   |
| Intel Wi-Fi 6 AX200                                               | 233       | 2.45%   |
| Intel Wireless 8265 / 8275                                        | 202       | 2.12%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 193       | 2.03%   |
| Intel Wi-Fi 6 AX201                                               | 193       | 2.03%   |
| Intel Wireless 7265                                               | 187       | 1.96%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 174       | 1.83%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 165       | 1.73%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 159       | 1.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 151       | 1.59%   |
| Intel Wireless 8260                                               | 151       | 1.59%   |
| Intel Wireless 7260                                               | 148       | 1.55%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 145       | 1.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 124       | 1.3%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 121       | 1.27%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 118       | 1.24%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 115       | 1.21%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 110       | 1.16%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 98        | 1.03%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 98        | 1.03%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 93        | 0.98%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 92        | 0.97%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 91        | 0.96%   |
| Intel Wireless 3165                                               | 79        | 0.83%   |
| Broadcom BCM43142 802.11b/g/n                                     | 74        | 0.78%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 73        | 0.77%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 67        | 0.7%    |
| Intel Ethernet Connection (4) I219-LM                             | 67        | 0.7%    |
| Intel Ethernet Connection (3) I218-LM                             | 62        | 0.65%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 61        | 0.64%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 61        | 0.64%   |
| Intel Ethernet Connection I219-LM                                 | 61        | 0.64%   |
| Intel WiFi Link 5100                                              | 60        | 0.63%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 58        | 0.61%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 55        | 0.58%   |
| Intel Wireless 3160                                               | 53        | 0.56%   |
| Intel Wireless-AC 9260                                            | 51        | 0.54%   |
| Intel Ethernet Connection I218-LM                                 | 50        | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2583      | 50.84%  |
| Qualcomm Atheros                      | 975       | 19.19%  |
| Realtek Semiconductor                 | 748       | 14.72%  |
| Broadcom                              | 377       | 7.42%   |
| MediaTek                              | 90        | 1.77%   |
| Ralink                                | 82        | 1.61%   |
| Broadcom Limited                      | 73        | 1.44%   |
| Sierra Wireless                       | 24        | 0.47%   |
| Dell                                  | 22        | 0.43%   |
| Ralink Technology                     | 18        | 0.35%   |
| NetGear                               | 17        | 0.33%   |
| TP-Link                               | 15        | 0.3%    |
| Qualcomm                              | 15        | 0.3%    |
| D-Link                                | 7         | 0.14%   |
| Hewlett-Packard                       | 6         | 0.12%   |
| Fibocom                               | 5         | 0.1%    |
| D-Link System                         | 5         | 0.1%    |
| Belkin Components                     | 3         | 0.06%   |
| ASUSTek Computer                      | 3         | 0.06%   |
| Qualcomm Atheros Communications       | 2         | 0.04%   |
| Microsoft                             | 2         | 0.04%   |
| Edimax Technology                     | 2         | 0.04%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.04%   |
| ZyDAS                                 | 1         | 0.02%   |
| Texas Instruments                     | 1         | 0.02%   |
| Sagem                                 | 1         | 0.02%   |
| Guillemot                             | 1         | 0.02%   |
| Accton Technology                     | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 233       | 4.56%   |
| Intel Wireless 8265 / 8275                                              | 202       | 3.96%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 193       | 3.78%   |
| Intel Wi-Fi 6 AX201                                                     | 193       | 3.78%   |
| Intel Wireless 7265                                                     | 187       | 3.66%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 174       | 3.41%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 159       | 3.11%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 151       | 2.96%   |
| Intel Wireless 8260                                                     | 151       | 2.96%   |
| Intel Wireless 7260                                                     | 148       | 2.9%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 145       | 2.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 124       | 2.43%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 121       | 2.37%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 118       | 2.31%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 115       | 2.25%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 110       | 2.15%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 98        | 1.92%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 98        | 1.92%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 93        | 1.82%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 92        | 1.8%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 91        | 1.78%   |
| Intel Wireless 3165                                                     | 79        | 1.55%   |
| Broadcom BCM43142 802.11b/g/n                                           | 74        | 1.45%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 73        | 1.43%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 61        | 1.19%   |
| Intel WiFi Link 5100                                                    | 60        | 1.17%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 58        | 1.14%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 55        | 1.08%   |
| Intel Wireless 3160                                                     | 53        | 1.04%   |
| Intel Wireless-AC 9260                                                  | 51        | 1%      |
| Intel Centrino Wireless-N 2230                                          | 49        | 0.96%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 47        | 0.92%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 47        | 0.92%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 40        | 0.78%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 40        | 0.78%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 39        | 0.76%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 38        | 0.74%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 37        | 0.72%   |
| Intel Centrino Advanced-N 6200                                          | 35        | 0.69%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 35        | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 2267      | 53.2%   |
| Intel                            | 966       | 22.67%  |
| Qualcomm Atheros                 | 372       | 8.73%   |
| Broadcom                         | 199       | 4.67%   |
| Marvell Technology Group         | 99        | 2.32%   |
| ASIX Electronics                 | 54        | 1.27%   |
| Broadcom Limited                 | 39        | 0.92%   |
| Nvidia                           | 34        | 0.8%    |
| Xiaomi                           | 31        | 0.73%   |
| DisplayLink                      | 29        | 0.68%   |
| Samsung Electronics              | 27        | 0.63%   |
| Lenovo                           | 19        | 0.45%   |
| JMicron Technology               | 19        | 0.45%   |
| Attansic Technology              | 14        | 0.33%   |
| Huawei Technologies              | 12        | 0.28%   |
| Silicon Integrated Systems [SiS] | 11        | 0.26%   |
| OPPO Electronics                 | 8         | 0.19%   |
| TP-Link                          | 7         | 0.16%   |
| MediaTek                         | 7         | 0.16%   |
| Google                           | 7         | 0.16%   |
| Apple                            | 6         | 0.14%   |
| Qualcomm                         | 5         | 0.12%   |
| ICS Advent                       | 4         | 0.09%   |
| NetGear                          | 3         | 0.07%   |
| VIA Technologies                 | 2         | 0.05%   |
| OnePlus Technology (Shenzhen)    | 2         | 0.05%   |
| Motorola PCS                     | 2         | 0.05%   |
| Linksys                          | 2         | 0.05%   |
| Hisense                          | 2         | 0.05%   |
| Cypress Semiconductor            | 2         | 0.05%   |
| Aquantia                         | 2         | 0.05%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.02%   |
| ULi Electronics                  | 1         | 0.02%   |
| T & A Mobile Phones              | 1         | 0.02%   |
| Microchip Technology             | 1         | 0.02%   |
| Hewlett-Packard                  | 1         | 0.02%   |
| Davicom Semiconductor            | 1         | 0.02%   |
| D-Link                           | 1         | 0.02%   |
| Archos                           | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1500      | 34.87%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 412       | 9.58%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 272       | 6.32%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 165       | 3.84%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 67        | 1.56%   |
| Intel Ethernet Connection (4) I219-LM                             | 67        | 1.56%   |
| Intel Ethernet Connection (3) I218-LM                             | 62        | 1.44%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 61        | 1.42%   |
| Intel Ethernet Connection I219-LM                                 | 61        | 1.42%   |
| Intel Ethernet Connection I218-LM                                 | 50        | 1.16%   |
| ASIX AX88179 Gigabit Ethernet                                     | 50        | 1.16%   |
| Intel Ethernet Connection I217-LM                                 | 48        | 1.12%   |
| Intel 82577LM Gigabit Network Connection                          | 42        | 0.98%   |
| Intel 82567LM Gigabit Network Connection                          | 39        | 0.91%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 35        | 0.81%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 34        | 0.79%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 33        | 0.77%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 32        | 0.74%   |
| Intel Ethernet Connection (6) I219-V                              | 32        | 0.74%   |
| Intel Ethernet Connection (7) I219-LM                             | 31        | 0.72%   |
| Intel Ethernet Connection I219-V                                  | 29        | 0.67%   |
| Intel Ethernet Connection (4) I219-V                              | 29        | 0.67%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 28        | 0.65%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 27        | 0.63%   |
| Intel Ethernet Connection I217-V                                  | 27        | 0.63%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 26        | 0.6%    |
| Intel Ethernet Connection (6) I219-LM                             | 25        | 0.58%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 25        | 0.58%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 24        | 0.56%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 24        | 0.56%   |
| Intel Ethernet Connection (13) I219-V                             | 24        | 0.56%   |
| Intel Ethernet Connection (13) I219-LM                            | 24        | 0.56%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 22        | 0.51%   |
| Nvidia MCP79 Ethernet                                             | 22        | 0.51%   |
| Intel Ethernet Connection (2) I219-LM                             | 22        | 0.51%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 22        | 0.51%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 22        | 0.51%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 21        | 0.49%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 21        | 0.49%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 19        | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 4885      | 54.03%  |
| Ethernet | 4046      | 44.75%  |
| Modem    | 104       | 1.15%   |
| Unknown  | 7         | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3922      | 74.25%  |
| Ethernet | 1359      | 25.73%  |
| Modem    | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 3623      | 72.77%  |
| 1     | 1241      | 24.92%  |
| 0     | 70        | 1.41%   |
| 3     | 45        | 0.9%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3243      | 63.25%  |
| Yes  | 1884      | 36.75%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2015      | 52.26%  |
| Realtek Semiconductor           | 315       | 8.17%   |
| IMC Networks                    | 299       | 7.75%   |
| Qualcomm Atheros Communications | 255       | 6.61%   |
| Broadcom                        | 197       | 5.11%   |
| Foxconn / Hon Hai               | 139       | 3.6%    |
| Lite-On Technology              | 138       | 3.58%   |
| Apple                           | 101       | 2.62%   |
| Dell                            | 84        | 2.18%   |
| Cambridge Silicon Radio         | 57        | 1.48%   |
| Realtek                         | 44        | 1.14%   |
| Hewlett-Packard                 | 41        | 1.06%   |
| Toshiba                         | 38        | 0.99%   |
| Ralink                          | 33        | 0.86%   |
| ASUSTek Computer                | 25        | 0.65%   |
| Ralink Technology               | 21        | 0.54%   |
| Foxconn International           | 14        | 0.36%   |
| Alps Electric                   | 14        | 0.36%   |
| Chicony Electronics             | 7         | 0.18%   |
| USI                             | 6         | 0.16%   |
| MediaTek                        | 5         | 0.13%   |
| TP-Link                         | 2         | 0.05%   |
| Syntek                          | 1         | 0.03%   |
| Qcom                            | 1         | 0.03%   |
| Integrated System Solution      | 1         | 0.03%   |
| Fujitsu                         | 1         | 0.03%   |
| Corsair                         | 1         | 0.03%   |
| Unknown                         | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 783       | 20.3%   |
| Intel AX201 Bluetooth                               | 428       | 11.09%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 310       | 8.04%   |
| Intel AX200 Bluetooth                               | 221       | 5.73%   |
| Realtek Bluetooth Radio                             | 199       | 5.16%   |
| IMC Networks Bluetooth Device                       | 110       | 2.85%   |
| Qualcomm Atheros  Bluetooth Device                  | 104       | 2.7%    |
| Intel Bluetooth Device                              | 104       | 2.7%    |
| IMC Networks Bluetooth Radio                        | 90        | 2.33%   |
| Realtek  Bluetooth 4.2 Adapter                      | 77        | 2%      |
| Intel Centrino Bluetooth Wireless Transceiver       | 72        | 1.87%   |
| Foxconn / Hon Hai Bluetooth Device                  | 58        | 1.5%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 57        | 1.48%   |
| Apple Bluetooth Host Controller                     | 56        | 1.45%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 49        | 1.27%   |
| Realtek Bluetooth Radio                             | 44        | 1.14%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 44        | 1.14%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 43        | 1.11%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 43        | 1.11%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 41        | 1.06%   |
| Lite-On Bluetooth Device                            | 37        | 0.96%   |
| Dell DW375 Bluetooth Module                         | 37        | 0.96%   |
| IMC Networks Wireless_Device                        | 35        | 0.91%   |
| Ralink RT3290 Bluetooth                             | 33        | 0.86%   |
| Intel AX210 Bluetooth                               | 29        | 0.75%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 29        | 0.75%   |
| Broadcom BCM2045B (BDC-2.1)                         | 29        | 0.75%   |
| Apple Bluetooth USB Host Controller                 | 28        | 0.73%   |
| Lite-On Atheros AR3012 Bluetooth                    | 27        | 0.7%    |
| Intel Wireless-AC 3168 Bluetooth                    | 26        | 0.67%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 26        | 0.67%   |
| HP Broadcom 2070 Bluetooth Combo                    | 23        | 0.6%    |
| Broadcom BCM43142A0 Bluetooth Device                | 20        | 0.52%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 19        | 0.49%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 19        | 0.49%   |
| Realtek RTL8723B Bluetooth                          | 18        | 0.47%   |
| Dell BCM20702A0 Bluetooth Module                    | 17        | 0.44%   |
| Broadcom HP Portable SoftSailing                    | 17        | 0.44%   |
| IMC Networks Bluetooth                              | 16        | 0.41%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 16        | 0.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 4048      | 65.42%  |
| AMD                                          | 948       | 15.32%  |
| Nvidia                                       | 773       | 12.49%  |
| Realtek Semiconductor                        | 61        | 0.99%   |
| Logitech                                     | 36        | 0.58%   |
| GN Netcom                                    | 36        | 0.58%   |
| C-Media Electronics                          | 32        | 0.52%   |
| Plantronics                                  | 25        | 0.4%    |
| JMTek                                        | 20        | 0.32%   |
| Kingston Technology                          | 19        | 0.31%   |
| Lenovo                                       | 17        | 0.27%   |
| Hewlett-Packard                              | 14        | 0.23%   |
| Silicon Integrated Systems [SiS]             | 13        | 0.21%   |
| Corsair                                      | 13        | 0.21%   |
| SteelSeries ApS                              | 8         | 0.13%   |
| Generalplus Technology                       | 7         | 0.11%   |
| Texas Instruments                            | 6         | 0.1%    |
| Focusrite-Novation                           | 6         | 0.1%    |
| Razer USA                                    | 5         | 0.08%   |
| VIA Technologies                             | 4         | 0.06%   |
| Sony                                         | 4         | 0.06%   |
| DSEA A/S                                     | 4         | 0.06%   |
| Apple                                        | 4         | 0.06%   |
| No brand                                     | 3         | 0.05%   |
| M-Audio                                      | 3         | 0.05%   |
| Elitegroup Computer Systems (ECS)            | 3         | 0.05%   |
| Conexant Systems                             | 3         | 0.05%   |
| Blue Microphones                             | 3         | 0.05%   |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 0.03%   |
| ZOOM                                         | 2         | 0.03%   |
| XMOS                                         | 2         | 0.03%   |
| Sennheiser Communications                    | 2         | 0.03%   |
| RODE Microphones                             | 2         | 0.03%   |
| PreSonus Audio Electronics                   | 2         | 0.03%   |
| OnePlus Technology (Shenzhen)                | 2         | 0.03%   |
| Dell                                         | 2         | 0.03%   |
| Cambridge Audio                              | 2         | 0.03%   |
| BR23                                         | 2         | 0.03%   |
| BEHRINGER International                      | 2         | 0.03%   |
| Barco Display Systems                        | 2         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 514       | 6.92%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 425       | 5.72%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 413       | 5.56%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 265       | 3.57%   |
| Intel Cannon Lake PCH cAVS                                                                        | 256       | 3.45%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 252       | 3.39%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 249       | 3.35%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 233       | 3.14%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 208       | 2.8%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 194       | 2.61%   |
| Intel 8 Series HD Audio Controller                                                                | 189       | 2.54%   |
| Intel Broadwell-U Audio Controller                                                                | 188       | 2.53%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 187       | 2.52%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 187       | 2.52%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 163       | 2.19%   |
| AMD FCH Azalia Controller                                                                         | 163       | 2.19%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 152       | 2.05%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 143       | 1.92%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 140       | 1.88%   |
| AMD Kabini HDMI/DP Audio                                                                          | 119       | 1.6%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 113       | 1.52%   |
| Intel Comet Lake PCH cAVS                                                                         | 103       | 1.39%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 100       | 1.35%   |
| Intel CM238 HD Audio Controller                                                                   | 99        | 1.33%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 97        | 1.31%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 93        | 1.25%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 87        | 1.17%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 84        | 1.13%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 80        | 1.08%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 76        | 1.02%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 75        | 1.01%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 73        | 0.98%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 68        | 0.92%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 66        | 0.89%   |
| Realtek Semiconductor USB Audio                                                                   | 60        | 0.81%   |
| AMD Wrestler HDMI Audio                                                                           | 60        | 0.81%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 58        | 0.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 58        | 0.78%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 58        | 0.78%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 53        | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 1152      | 30.27%  |
| SK hynix                                         | 994       | 26.12%  |
| Micron Technology                                | 467       | 12.27%  |
| Kingston                                         | 266       | 6.99%   |
| Unknown                                          | 261       | 6.86%   |
| Crucial                                          | 184       | 4.83%   |
| Elpida                                           | 72        | 1.89%   |
| Ramaxel Technology                               | 69        | 1.81%   |
| Corsair                                          | 56        | 1.47%   |
| Nanya Technology                                 | 48        | 1.26%   |
| A-DATA Technology                                | 48        | 1.26%   |
| Unknown (ABCD)                                   | 42        | 1.1%    |
| G.Skill                                          | 41        | 1.08%   |
| Unknown                                          | 15        | 0.39%   |
| Transcend                                        | 11        | 0.29%   |
| ASint Technology                                 | 6         | 0.16%   |
| Patriot                                          | 5         | 0.13%   |
| Timetec                                          | 4         | 0.11%   |
| Apacer                                           | 4         | 0.11%   |
| V-Color                                          | 3         | 0.08%   |
| Toshiba                                          | 3         | 0.08%   |
| Team                                             | 3         | 0.08%   |
| SHARETRONIC                                      | 3         | 0.08%   |
| Qimonda                                          | 3         | 0.08%   |
| PNY                                              | 3         | 0.08%   |
| TEXTORM                                          | 2         | 0.05%   |
| Neo Forza                                        | 2         | 0.05%   |
| Lexar                                            | 2         | 0.05%   |
| Goldkey                                          | 2         | 0.05%   |
| ChangXin Memory                                  | 2         | 0.05%   |
| 48spaces                                         | 2         | 0.05%   |
| Wilk                                             | 1         | 0.03%   |
| Unknown (F301)                                   | 1         | 0.03%   |
| Unknown (0x8634)                                 | 1         | 0.03%   |
| Unknown (0x7301)                                 | 1         | 0.03%   |
| Unknown (0x5846)                                 | 1         | 0.03%   |
| Unknown (0x4D3420373054353636334548332D43463720) | 1         | 0.03%   |
| Unknown (0x4D342037305432383634515A332D43463720) | 1         | 0.03%   |
| Unknown (0x36345431323830323145444C335342322020) | 1         | 0.03%   |
| Unknown (0x0C97)                                 | 1         | 0.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 57        | 1.43%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 56        | 1.4%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 55        | 1.38%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 53        | 1.33%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 51        | 1.28%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 49        | 1.23%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 42        | 1.05%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 41        | 1.03%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 41        | 1.03%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 39        | 0.98%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 39        | 0.98%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 38        | 0.95%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 37        | 0.93%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 37        | 0.93%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 37        | 0.93%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 36        | 0.9%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 36        | 0.9%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 32        | 0.8%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 29        | 0.73%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 26        | 0.65%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s        | 26        | 0.65%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 24        | 0.6%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 24        | 0.6%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 22        | 0.55%   |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                       | 22        | 0.55%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 21        | 0.53%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 21        | 0.53%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 21        | 0.53%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 19        | 0.48%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 19        | 0.48%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 19        | 0.48%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 19        | 0.48%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 19        | 0.48%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 18        | 0.45%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s        | 18        | 0.45%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 18        | 0.45%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 17        | 0.43%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 17        | 0.43%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 17        | 0.43%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 16        | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 1502      | 46.07%  |
| DDR3    | 1152      | 35.34%  |
| DDR2    | 170       | 5.21%   |
| LPDDR4  | 146       | 4.48%   |
| LPDDR3  | 104       | 3.19%   |
| SDRAM   | 73        | 2.24%   |
| LPDDR5  | 36        | 1.1%    |
| DDR5    | 34        | 1.04%   |
| Unknown | 24        | 0.74%   |
| DDR     | 13        | 0.4%    |
| DRAM    | 6         | 0.18%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 2916      | 89.61%  |
| Row Of Chips | 296       | 9.1%    |
| Chip         | 17        | 0.52%   |
| DIMM         | 13        | 0.4%    |
| Unknown      | 12        | 0.37%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 1284      | 36.34%  |
| 4096  | 1132      | 32.04%  |
| 2048  | 464       | 13.13%  |
| 16384 | 458       | 12.96%  |
| 1024  | 113       | 3.2%    |
| 32768 | 72        | 2.04%   |
| 512   | 9         | 0.25%   |
| 256   | 1         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 834       | 23.87%  |
| 2667    | 678       | 19.4%   |
| 3200    | 628       | 17.97%  |
| 2400    | 225       | 6.44%   |
| 1334    | 185       | 5.29%   |
| 2133    | 174       | 4.98%   |
| 1333    | 110       | 3.15%   |
| 667     | 94        | 2.69%   |
| 4267    | 64        | 1.83%   |
| Unknown | 57        | 1.63%   |
| 3266    | 56        | 1.6%    |
| 1067    | 50        | 1.43%   |
| 1867    | 39        | 1.12%   |
| 800     | 39        | 1.12%   |
| 4800    | 38        | 1.09%   |
| 6400    | 35        | 1%      |
| 4199    | 35        | 1%      |
| 2048    | 32        | 0.92%   |
| 1066    | 25        | 0.72%   |
| 975     | 23        | 0.66%   |
| 533     | 17        | 0.49%   |
| 4266    | 15        | 0.43%   |
| 8400    | 9         | 0.26%   |
| 2933    | 7         | 0.2%    |
| 1866    | 6         | 0.17%   |
| 333     | 5         | 0.14%   |
| 3000    | 4         | 0.11%   |
| 3733    | 3         | 0.09%   |
| 1639    | 3         | 0.09%   |
| 400     | 2         | 0.06%   |
| 933     | 1         | 0.03%   |
| 266     | 1         | 0.03%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 15        | 37.5%   |
| Canon               | 10        | 25%     |
| Seiko Epson         | 4         | 10%     |
| Samsung Electronics | 4         | 10%     |
| Brother Industries  | 4         | 10%     |
| Xiaomi              | 1         | 2.5%    |
| STMicroelectronics  | 1         | 2.5%    |
| QinHeng Electronics | 1         | 2.5%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| HP DeskJet 2700 series                                    | 4         | 10%     |
| HP DeskJet 3630 series                                    | 3         | 7.5%    |
| Canon PIXMA MG2500 Series                                 | 3         | 7.5%    |
| Seiko Epson WF-2830 Series                                | 2         | 5%      |
| Canon PIXMA MG3600 Series                                 | 2         | 5%      |
| Xiaomi MiMouse 2                                          | 1         | 2.5%    |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 2.5%    |
| Seiko Epson XP-255 257 Series                             | 1         | 2.5%    |
| Seiko Epson XP-2150 Series                                | 1         | 2.5%    |
| Samsung SCX-3200 Series                                   | 1         | 2.5%    |
| Samsung ML-2010P Mono Laser Printer                       | 1         | 2.5%    |
| Samsung M2070 Series                                      | 1         | 2.5%    |
| Samsung M2020 Series                                      | 1         | 2.5%    |
| QinHeng CH340S                                            | 1         | 2.5%    |
| HP Photosmart B010 series                                 | 1         | 2.5%    |
| HP OfficeJet Pro 69                                       | 1         | 2.5%    |
| HP OfficeJet 3830 series                                  | 1         | 2.5%    |
| HP ENVY Photo 6200 series                                 | 1         | 2.5%    |
| HP ENVY 5540 series                                       | 1         | 2.5%    |
| HP ENVY 4500 series                                       | 1         | 2.5%    |
| HP Deskjet F4500 series                                   | 1         | 2.5%    |
| HP DeskJet 2600 series                                    | 1         | 2.5%    |
| Canon TS6100 series                                       | 1         | 2.5%    |
| Canon PIXMA MP495                                         | 1         | 2.5%    |
| Canon PIXMA MP270 All-In-One Printer                      | 1         | 2.5%    |
| Canon PIXMA MG3500 Series                                 | 1         | 2.5%    |
| Canon MG2100 series                                       | 1         | 2.5%    |
| Brother MFC-L8690CDW series                               | 1         | 2.5%    |
| Brother MFC-L2710DW series                                | 1         | 2.5%    |
| Brother MFC-1810                                          | 1         | 2.5%    |
| Brother DCP-L3550CDW                                      | 1         | 2.5%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 6         | 54.55%  |
| Seiko Epson     | 4         | 36.36%  |
| Hewlett-Packard | 1         | 9.09%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                       | 3         | 27.27%  |
| Seiko Epson Scanner                           | 1         | 9.09%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]   | 1         | 9.09%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO] | 1         | 9.09%   |
| Seiko Epson GT-7700U [Perfection 1240U]       | 1         | 9.09%   |
| HP ScanJet 3570c                              | 1         | 9.09%   |
| Canon CanoScan N670U/N676U/LiDE 20            | 1         | 9.09%   |
| Canon CanoScan N650U/N656U                    | 1         | 9.09%   |
| Canon CanoScan N1240U/LiDE 30                 | 1         | 9.09%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1106      | 24.9%   |
| IMC Networks                           | 513       | 11.55%  |
| Microdia                               | 438       | 9.86%   |
| Realtek Semiconductor                  | 420       | 9.46%   |
| Sunplus Innovation Technology          | 273       | 6.15%   |
| Bison Electronics                      | 193       | 4.34%   |
| Suyin                                  | 186       | 4.19%   |
| Cheng Uei Precision Industry (Foxlink) | 182       | 4.1%    |
| Acer                                   | 177       | 3.98%   |
| Quanta                                 | 165       | 3.71%   |
| Lite-On Technology                     | 114       | 2.57%   |
| Apple                                  | 97        | 2.18%   |
| Syntek                                 | 86        | 1.94%   |
| Alcor Micro                            | 61        | 1.37%   |
| Logitech                               | 53        | 1.19%   |
| Luxvisions Innotech Limited            | 52        | 1.17%   |
| Ricoh                                  | 48        | 1.08%   |
| Silicon Motion                         | 43        | 0.97%   |
| Samsung Electronics                    | 26        | 0.59%   |
| Lenovo                                 | 22        | 0.5%    |
| Sonix Technology                       | 21        | 0.47%   |
| Primax Electronics                     | 18        | 0.41%   |
| Z-Star Microelectronics                | 15        | 0.34%   |
| Importek                               | 15        | 0.34%   |
| DigiTech                               | 14        | 0.32%   |
| ALi                                    | 12        | 0.27%   |
| icSpring                               | 8         | 0.18%   |
| Y Media                                | 7         | 0.16%   |
| GEMBIRD                                | 7         | 0.16%   |
| OmniVision Technologies                | 6         | 0.14%   |
| Microsoft                              | 5         | 0.11%   |
| SunplusIT                              | 4         | 0.09%   |
| Denron                                 | 4         | 0.09%   |
| Xiaomi                                 | 3         | 0.07%   |
| Sunplus Technology                     | 3         | 0.07%   |
| Pixart Imaging                         | 3         | 0.07%   |
| Intel                                  | 3         | 0.07%   |
| Generalplus Technology                 | 3         | 0.07%   |
| ARC International                      | 3         | 0.07%   |
| webcam                                 | 2         | 0.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD            | 238       | 5.34%   |
| Realtek Integrated_Webcam_HD             | 185       | 4.15%   |
| Chicony Integrated Camera                | 168       | 3.77%   |
| IMC Networks USB2.0 HD UVC WebCam        | 122       | 2.74%   |
| Chicony HD WebCam                        | 96        | 2.15%   |
| IMC Networks Integrated Camera           | 92        | 2.06%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 87        | 1.95%   |
| Sunplus Integrated_Webcam_HD             | 74        | 1.66%   |
| Realtek USB Camera                       | 67        | 1.5%    |
| Acer HD Webcam                           | 56        | 1.26%   |
| Chicony USB2.0 Camera                    | 54        | 1.21%   |
| Chicony USB2.0 VGA UVC WebCam            | 51        | 1.14%   |
| Bison Integrated Camera                  | 50        | 1.12%   |
| Chicony HP HD Camera                     | 46        | 1.03%   |
| Chicony USB2.0 HD UVC WebCam             | 44        | 0.99%   |
| Chicony TOSHIBA Web Camera - HD          | 42        | 0.94%   |
| Sunplus Asus Webcam                      | 41        | 0.92%   |
| Microdia Integrated Webcam               | 41        | 0.92%   |
| Acer BisonCam,NB Pro                     | 40        | 0.9%    |
| Chicony HP Truevision HD                 | 39        | 0.87%   |
| Syntek Integrated Camera                 | 38        | 0.85%   |
| Lite-On Integrated Camera                | 37        | 0.83%   |
| Chicony USB 2.0 Camera                   | 37        | 0.83%   |
| Chicony HP TrueVision HD Camera          | 36        | 0.81%   |
| Chicony HP HD Webcam                     | 36        | 0.81%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X          | 32        | 0.72%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 31        | 0.7%    |
| Apple Built-in iSight                    | 31        | 0.7%    |
| Quanta HP HD Camera                      | 30        | 0.67%   |
| Chicony VGA Webcam                       | 30        | 0.67%   |
| Sunplus HD WebCam                        | 29        | 0.65%   |
| Realtek USB2.0 HD UVC WebCam             | 28        | 0.63%   |
| Lite-On HP HD Camera                     | 28        | 0.63%   |
| Alcor Micro USB 2.0 Camera               | 28        | 0.63%   |
| Acer Integrated Camera                   | 28        | 0.63%   |
| IMC Networks UVC VGA Webcam              | 27        | 0.61%   |
| Samsung Galaxy series, misc. (MTP mode)  | 26        | 0.58%   |
| IMC Networks ov9734_azurewave_camera     | 25        | 0.56%   |
| Quanta HD User Facing                    | 23        | 0.52%   |
| Chicony EasyCamera                       | 23        | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 290       | 35.76%  |
| Synaptics                          | 169       | 20.84%  |
| Shenzhen Goodix Technology         | 154       | 18.99%  |
| AuthenTec                          | 65        | 8.01%   |
| LighTuning Technology              | 43        | 5.3%    |
| Elan Microelectronics              | 42        | 5.18%   |
| Upek                               | 35        | 4.32%   |
| STMicroelectronics                 | 11        | 1.36%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.12%   |
| Focal-systems.Corp                 | 1         | 0.12%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 81        | 9.99%   |
| Shenzhen Goodix  FingerPrint Device                                        | 81        | 9.99%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 69        | 8.51%   |
| Shenzhen Goodix FingerPrint                                                | 43        | 5.3%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 37        | 4.56%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 31        | 3.82%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 30        | 3.7%    |
| Shenzhen Goodix Fingerprint Reader                                         | 30        | 3.7%    |
| Elan ELAN:Fingerprint                                                      | 29        | 3.58%   |
| Validity Sensors VFS491                                                    | 24        | 2.96%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 24        | 2.96%   |
| AuthenTec AES2810                                                          | 24        | 2.96%   |
| Validity Sensors Fingerprint scanner                                       | 20        | 2.47%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 18        | 2.22%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 17        | 2.1%    |
| Validity Sensors VFS301 Fingerprint Reader                                 | 16        | 1.97%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 16        | 1.97%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 14        | 1.73%   |
| AuthenTec Fingerprint Sensor                                               | 14        | 1.73%   |
| AuthenTec AES1600                                                          | 14        | 1.73%   |
| Validity Sensors Synaptics WBDI                                            | 13        | 1.6%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 13        | 1.6%    |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 13        | 1.6%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 12        | 1.48%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 11        | 1.36%   |
| Validity Sensors VFS Fingerprint sensor                                    | 11        | 1.36%   |
| STMicroelectronics Fingerprint Reader                                      | 11        | 1.36%   |
| Elan ELAN:ARM-M4                                                           | 11        | 1.36%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 10        | 1.23%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 9         | 1.11%   |
| Unknown                                                                    | 8         | 0.99%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 6         | 0.74%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 5         | 0.62%   |
| Upek TCS5B Fingerprint sensor                                              | 5         | 0.62%   |
| Synaptics WBDI Device                                                      | 5         | 0.62%   |
| Synaptics UWP WBDI                                                         | 5         | 0.62%   |
| Synaptics WBDI                                                             | 4         | 0.49%   |
| Synaptics  WBDI                                                            | 4         | 0.49%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 3         | 0.37%   |
| Synaptics UWP WBDI Device                                                  | 3         | 0.37%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 235       | 57.04%  |
| Alcor Micro               | 88        | 21.36%  |
| O2 Micro                  | 37        | 8.98%   |
| Upek                      | 17        | 4.13%   |
| Lenovo                    | 16        | 3.88%   |
| Hewlett-Packard           | 5         | 1.21%   |
| Gemalto (was Gemplus)     | 4         | 0.97%   |
| Yubico.com                | 3         | 0.73%   |
| Clay Logic                | 2         | 0.49%   |
| Aladdin Knowledge Systems | 2         | 0.49%   |
| SpringCard                | 1         | 0.24%   |
| OmniKey                   | 1         | 0.24%   |
| Chicony Electronics       | 1         | 0.24%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 88        | 21.36%  |
| Broadcom BCM5880 Secure Applications Processor                               | 78        | 18.93%  |
| Broadcom 58200                                                               | 73        | 17.72%  |
| Broadcom 5880                                                                | 49        | 11.89%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 34        | 8.25%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 33        | 8.01%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 17        | 4.13%   |
| Lenovo Integrated Smart Card Reader                                          | 16        | 3.88%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 5         | 1.21%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 0.97%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 3         | 0.73%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 0.49%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 0.49%   |
| SpringCard Two                                                               | 1         | 0.24%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.24%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.24%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.24%   |
| Clay Logic Nitrokey Start                                                    | 1         | 0.24%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.24%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.24%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.24%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 3174      | 61.96%  |
| 1     | 1553      | 30.31%  |
| 2     | 315       | 6.15%   |
| 3     | 63        | 1.23%   |
| 4     | 7         | 0.14%   |
| 5     | 5         | 0.1%    |
| 6     | 3         | 0.06%   |
| 7     | 2         | 0.04%   |
| 8     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 802       | 34.03%  |
| Graphics card            | 497       | 21.09%  |
| Chipcard                 | 384       | 16.29%  |
| Net/wireless             | 205       | 8.7%    |
| Multimedia controller    | 96        | 4.07%   |
| Camera                   | 89        | 3.78%   |
| Bluetooth                | 68        | 2.89%   |
| Storage                  | 58        | 2.46%   |
| Communication controller | 43        | 1.82%   |
| Card reader              | 38        | 1.61%   |
| Sound                    | 23        | 0.98%   |
| Net/ethernet             | 17        | 0.72%   |
| Modem                    | 17        | 0.72%   |
| Network                  | 7         | 0.3%    |
| Flash memory             | 4         | 0.17%   |
| Wireless                 | 2         | 0.08%   |
| Unclassified device      | 2         | 0.08%   |
| Unassigned class         | 1         | 0.04%   |
| Storage/nvme             | 1         | 0.04%   |
| Storage/ata              | 1         | 0.04%   |
| Firewire controller      | 1         | 0.04%   |
| Dvb card                 | 1         | 0.04%   |

