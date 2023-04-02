Gentoo - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Gentoo.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Gentoo/Desktop/README.md) and [notebooks](/Dist/Gentoo/Notebook/README.md).

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

Total: 2461

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | XPS 15 9570                 | Notebook    | [7beef34820](https://linux-hardware.org/?probe=7beef34820) | Apr 01, 2023 |
| Gigabyte      | B150M-D2V DDR3-CF           | Desktop     | [3599b8e875](https://linux-hardware.org/?probe=3599b8e875) | Mar 31, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [9e60f40931](https://linux-hardware.org/?probe=9e60f40931) | Mar 30, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [7d0c0336c1](https://linux-hardware.org/?probe=7d0c0336c1) | Mar 27, 2023 |
| ASRock        | AM1H-ITX                    | Desktop     | [8f1dcf05eb](https://linux-hardware.org/?probe=8f1dcf05eb) | Mar 26, 2023 |
| ASRock        | X370 Gaming X               | Desktop     | [0a19e934c3](https://linux-hardware.org/?probe=0a19e934c3) | Mar 26, 2023 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | Notebook    | [85fb1a6778](https://linux-hardware.org/?probe=85fb1a6778) | Mar 26, 2023 |
| ASUSTek       | Maximus VIII HERO ALPHA     | Desktop     | [cc262bb41a](https://linux-hardware.org/?probe=cc262bb41a) | Mar 26, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [f2b287b461](https://linux-hardware.org/?probe=f2b287b461) | Mar 25, 2023 |
| Acer          | Aspire A517-52G             | Notebook    | [ce3133a010](https://linux-hardware.org/?probe=ce3133a010) | Mar 25, 2023 |
| Gigabyte      | B150M-D2V DDR3-CF           | Desktop     | [276aa0b036](https://linux-hardware.org/?probe=276aa0b036) | Mar 25, 2023 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [72f90312db](https://linux-hardware.org/?probe=72f90312db) | Mar 25, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [dac7782920](https://linux-hardware.org/?probe=dac7782920) | Mar 24, 2023 |
| HP            | EliteBook 745 G6            | Notebook    | [96fe7c184c](https://linux-hardware.org/?probe=96fe7c184c) | Mar 24, 2023 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [2c8daaa4f2](https://linux-hardware.org/?probe=2c8daaa4f2) | Mar 24, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [4bf7fa5f9c](https://linux-hardware.org/?probe=4bf7fa5f9c) | Mar 23, 2023 |
| Dell          | Latitude 7480               | Notebook    | [35b30305ec](https://linux-hardware.org/?probe=35b30305ec) | Mar 23, 2023 |
| HP            | EliteBook 745 G6            | Notebook    | [caf636a252](https://linux-hardware.org/?probe=caf636a252) | Mar 22, 2023 |
| Lenovo        | ThinkPad X200 7459L61       | Notebook    | [42742477e3](https://linux-hardware.org/?probe=42742477e3) | Mar 22, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [644c9b9e55](https://linux-hardware.org/?probe=644c9b9e55) | Mar 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [06bd07f367](https://linux-hardware.org/?probe=06bd07f367) | Mar 21, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [015c8dac04](https://linux-hardware.org/?probe=015c8dac04) | Mar 21, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [7b4a68e88a](https://linux-hardware.org/?probe=7b4a68e88a) | Mar 20, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [f048ae8dec](https://linux-hardware.org/?probe=f048ae8dec) | Mar 19, 2023 |
| MSI           | 990FXA-GD80                 | Desktop     | [e79acda971](https://linux-hardware.org/?probe=e79acda971) | Mar 19, 2023 |
| ASRock        | X370 Gaming X               | Desktop     | [4f98540a7b](https://linux-hardware.org/?probe=4f98540a7b) | Mar 19, 2023 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [dc0a9ba834](https://linux-hardware.org/?probe=dc0a9ba834) | Mar 19, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [cb3b7c5bfb](https://linux-hardware.org/?probe=cb3b7c5bfb) | Mar 19, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [135aa0e418](https://linux-hardware.org/?probe=135aa0e418) | Mar 18, 2023 |
| Supermicro    | X10SDV-4C-TLN2F             | Server      | [210b2e16e3](https://linux-hardware.org/?probe=210b2e16e3) | Mar 18, 2023 |
| Microsoft     | Surface Laptop 3            | Tablet      | [67c8f562e5](https://linux-hardware.org/?probe=67c8f562e5) | Mar 18, 2023 |
| Unknown       | Unknown                     | Notebook    | [d2af864fbb](https://linux-hardware.org/?probe=d2af864fbb) | Mar 17, 2023 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [7e11b106d7](https://linux-hardware.org/?probe=7e11b106d7) | Mar 17, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [d0ab04cac0](https://linux-hardware.org/?probe=d0ab04cac0) | Mar 16, 2023 |
| Star Labs     | StarBook                    | Notebook    | [0b249699ba](https://linux-hardware.org/?probe=0b249699ba) | Mar 16, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [fab37d7522](https://linux-hardware.org/?probe=fab37d7522) | Mar 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [b606e7c92f](https://linux-hardware.org/?probe=b606e7c92f) | Mar 16, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [4d5bb23ec0](https://linux-hardware.org/?probe=4d5bb23ec0) | Mar 15, 2023 |
| ASRock        | H81M-HDS                    | Desktop     | [58f8534073](https://linux-hardware.org/?probe=58f8534073) | Mar 14, 2023 |
| Foxconn       | TPS01                       | Desktop     | [60ae6d3891](https://linux-hardware.org/?probe=60ae6d3891) | Mar 14, 2023 |
| Fujitsu Si... | D1547 S26361-D1547          | Desktop     | [95a9c8655d](https://linux-hardware.org/?probe=95a9c8655d) | Mar 14, 2023 |
| Dell          | Precision 7770              | Notebook    | [b13d6bed73](https://linux-hardware.org/?probe=b13d6bed73) | Mar 14, 2023 |
| Dell          | Precision 7770              | Notebook    | [38f84c4cfc](https://linux-hardware.org/?probe=38f84c4cfc) | Mar 14, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [06d54f03f9](https://linux-hardware.org/?probe=06d54f03f9) | Mar 13, 2023 |
| Unknown       | Unknown                     | Soc         | [211fbfe507](https://linux-hardware.org/?probe=211fbfe507) | Mar 13, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [a0590e6829](https://linux-hardware.org/?probe=a0590e6829) | Mar 13, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [3b52326a3e](https://linux-hardware.org/?probe=3b52326a3e) | Mar 12, 2023 |
| Samsung       | 950QDB                      | Convertible | [525ce83d74](https://linux-hardware.org/?probe=525ce83d74) | Mar 12, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [e3c4587227](https://linux-hardware.org/?probe=e3c4587227) | Mar 12, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | Desktop     | [0932f02541](https://linux-hardware.org/?probe=0932f02541) | Mar 12, 2023 |
| Lenovo        | ThinkPad Edge E330 3354A... | Notebook    | [b343b9ea49](https://linux-hardware.org/?probe=b343b9ea49) | Mar 11, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [9d14bee09f](https://linux-hardware.org/?probe=9d14bee09f) | Mar 10, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [a443422517](https://linux-hardware.org/?probe=a443422517) | Mar 10, 2023 |
| Dell          | Precision 7770              | Notebook    | [7d5207e1c1](https://linux-hardware.org/?probe=7d5207e1c1) | Mar 09, 2023 |
| ASRock        | AM1H-ITX                    | Desktop     | [a0eb3774fc](https://linux-hardware.org/?probe=a0eb3774fc) | Mar 09, 2023 |
| Dell          | Latitude E6540              | Notebook    | [3bf25841b3](https://linux-hardware.org/?probe=3bf25841b3) | Mar 09, 2023 |
| Supermicro    | X10DRi-LN4+                 | Desktop     | [4e805ce5a1](https://linux-hardware.org/?probe=4e805ce5a1) | Mar 08, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [87cbc99c85](https://linux-hardware.org/?probe=87cbc99c85) | Mar 08, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [ad6e1bbda5](https://linux-hardware.org/?probe=ad6e1bbda5) | Mar 08, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [e455dce9f3](https://linux-hardware.org/?probe=e455dce9f3) | Mar 07, 2023 |
| ASRock        | H170 Pro4                   | Desktop     | [7d749add31](https://linux-hardware.org/?probe=7d749add31) | Mar 07, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [4d48b829ca](https://linux-hardware.org/?probe=4d48b829ca) | Mar 07, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [397eb062bf](https://linux-hardware.org/?probe=397eb062bf) | Mar 07, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [dee1b60a0d](https://linux-hardware.org/?probe=dee1b60a0d) | Mar 07, 2023 |
| Microsoft     | Surface Laptop 3            | Tablet      | [70eb1caef5](https://linux-hardware.org/?probe=70eb1caef5) | Mar 07, 2023 |
| Dell          | Precision 7770              | Notebook    | [dea25f9c87](https://linux-hardware.org/?probe=dea25f9c87) | Mar 07, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [6493617e39](https://linux-hardware.org/?probe=6493617e39) | Mar 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [ffd546b665](https://linux-hardware.org/?probe=ffd546b665) | Mar 07, 2023 |
| Supermicro    | X10DRi-LN4+                 | Desktop     | [d445859477](https://linux-hardware.org/?probe=d445859477) | Mar 07, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [5f35f09385](https://linux-hardware.org/?probe=5f35f09385) | Mar 06, 2023 |
| Dell          | Precision 7770              | Notebook    | [aa1ff5150c](https://linux-hardware.org/?probe=aa1ff5150c) | Mar 06, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [42edcf638d](https://linux-hardware.org/?probe=42edcf638d) | Mar 06, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [f0cde07b9f](https://linux-hardware.org/?probe=f0cde07b9f) | Mar 05, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [ccca18039f](https://linux-hardware.org/?probe=ccca18039f) | Mar 05, 2023 |
| MSI           | GS65 Stealth Thin 8RF       | Notebook    | [24373477d9](https://linux-hardware.org/?probe=24373477d9) | Mar 05, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [541a6200bc](https://linux-hardware.org/?probe=541a6200bc) | Mar 05, 2023 |
| IBM           | ThinkPad T41 23737JU        | Notebook    | [5495bd2109](https://linux-hardware.org/?probe=5495bd2109) | Mar 03, 2023 |
| Apple         | MacBookPro9,1               | Notebook    | [6553b59bfe](https://linux-hardware.org/?probe=6553b59bfe) | Mar 03, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [9a42993edb](https://linux-hardware.org/?probe=9a42993edb) | Mar 03, 2023 |
| ASUSTek       | 1016P                       | Notebook    | [739984c8cf](https://linux-hardware.org/?probe=739984c8cf) | Mar 03, 2023 |
| MSI           | GS65 Stealth Thin 8RF       | Notebook    | [e8f0217102](https://linux-hardware.org/?probe=e8f0217102) | Mar 03, 2023 |
| Huanan        | X99-F8D V2.4                | Desktop     | [e260724901](https://linux-hardware.org/?probe=e260724901) | Mar 03, 2023 |
| MSI           | GS66 Stealth 10UE           | Notebook    | [4500ce221e](https://linux-hardware.org/?probe=4500ce221e) | Mar 02, 2023 |
| ASUSTek       | 1016P                       | Notebook    | [29798857a5](https://linux-hardware.org/?probe=29798857a5) | Mar 02, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [8f8eaa9d53](https://linux-hardware.org/?probe=8f8eaa9d53) | Mar 01, 2023 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [7f93c1a4e3](https://linux-hardware.org/?probe=7f93c1a4e3) | Feb 28, 2023 |
| Lenovo        | Legion 5P 15IMH05 82AW      | Notebook    | [0de52a6150](https://linux-hardware.org/?probe=0de52a6150) | Feb 28, 2023 |
| Acer          | Aspire A515-45G             | Notebook    | [5f8c1e2d90](https://linux-hardware.org/?probe=5f8c1e2d90) | Feb 28, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [373f4f8123](https://linux-hardware.org/?probe=373f4f8123) | Feb 27, 2023 |
| MSI           | GS66 Stealth 10UE           | Notebook    | [f193cf790d](https://linux-hardware.org/?probe=f193cf790d) | Feb 27, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [aa86292f52](https://linux-hardware.org/?probe=aa86292f52) | Feb 27, 2023 |
| MSI           | GS66 Stealth 10UE           | Notebook    | [eba178253a](https://linux-hardware.org/?probe=eba178253a) | Feb 27, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [f8d42c3767](https://linux-hardware.org/?probe=f8d42c3767) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [54e5bda708](https://linux-hardware.org/?probe=54e5bda708) | Feb 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [83af08dd1d](https://linux-hardware.org/?probe=83af08dd1d) | Feb 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [c5a45c78fc](https://linux-hardware.org/?probe=c5a45c78fc) | Feb 26, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [cf1d88a388](https://linux-hardware.org/?probe=cf1d88a388) | Feb 26, 2023 |
| realme        | RMNBXXXX                    | Notebook    | [6ea10cb77a](https://linux-hardware.org/?probe=6ea10cb77a) | Feb 26, 2023 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [7f2823a756](https://linux-hardware.org/?probe=7f2823a756) | Feb 26, 2023 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [0b1c4036b1](https://linux-hardware.org/?probe=0b1c4036b1) | Feb 26, 2023 |
| Lenovo        | 1048 SDK0T08861 WIN 3305... | Desktop     | [e6b48cdec4](https://linux-hardware.org/?probe=e6b48cdec4) | Feb 26, 2023 |
| ASRock        | AM1H-ITX                    | Desktop     | [2029821da8](https://linux-hardware.org/?probe=2029821da8) | Feb 25, 2023 |
| Valve         | Jupiter                     | Notebook    | [3ad0d92361](https://linux-hardware.org/?probe=3ad0d92361) | Feb 25, 2023 |
| ASRock        | X370 Professional Gaming    | Desktop     | [cff46cb07b](https://linux-hardware.org/?probe=cff46cb07b) | Feb 24, 2023 |
| MSI           | GS66 Stealth 10UE           | Notebook    | [3382fa1bad](https://linux-hardware.org/?probe=3382fa1bad) | Feb 24, 2023 |
| MSI           | Vector GP66 12UEO           | Notebook    | [9b6bf9479e](https://linux-hardware.org/?probe=9b6bf9479e) | Feb 24, 2023 |
| MSI           | GS66 Stealth 10UE           | Notebook    | [ffcf782944](https://linux-hardware.org/?probe=ffcf782944) | Feb 23, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B3402FBA... | Convertible | [cede8b490a](https://linux-hardware.org/?probe=cede8b490a) | Feb 22, 2023 |
| ASUSTek       | P10S-I Series               | Desktop     | [f2049b8af1](https://linux-hardware.org/?probe=f2049b8af1) | Feb 21, 2023 |
| ASUSTek       | P10S-I Series               | Desktop     | [ec5a8efdcd](https://linux-hardware.org/?probe=ec5a8efdcd) | Feb 21, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [6a44442cfc](https://linux-hardware.org/?probe=6a44442cfc) | Feb 21, 2023 |
| Gigabyte      | Z590 UD                     | Desktop     | [a8da25537c](https://linux-hardware.org/?probe=a8da25537c) | Feb 21, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [da640089bd](https://linux-hardware.org/?probe=da640089bd) | Feb 21, 2023 |
| Alienware     | 17                          | Notebook    | [848d5cd7e9](https://linux-hardware.org/?probe=848d5cd7e9) | Feb 20, 2023 |
| Dell          | Precision 7770              | Notebook    | [d8db6fecdd](https://linux-hardware.org/?probe=d8db6fecdd) | Feb 20, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [cc8a99e630](https://linux-hardware.org/?probe=cc8a99e630) | Feb 20, 2023 |
| Valve         | Jupiter                     | Notebook    | [c9c9830572](https://linux-hardware.org/?probe=c9c9830572) | Feb 19, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [7b0fb49186](https://linux-hardware.org/?probe=7b0fb49186) | Feb 19, 2023 |
| ASUSTek       | ROG Strix G732LXS_G732LX... | Notebook    | [6424058c59](https://linux-hardware.org/?probe=6424058c59) | Feb 19, 2023 |
| ASUSTek       | PRIME H570M-PLUS            | Desktop     | [4fac3ddf27](https://linux-hardware.org/?probe=4fac3ddf27) | Feb 19, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [e2facdc650](https://linux-hardware.org/?probe=e2facdc650) | Feb 19, 2023 |
| ASUSTek       | Strix 17 GL703GE            | Notebook    | [48ca6dc3eb](https://linux-hardware.org/?probe=48ca6dc3eb) | Feb 19, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [84e946f098](https://linux-hardware.org/?probe=84e946f098) | Feb 18, 2023 |
| Gigabyte      | B650 AORUS PRO AX           | Desktop     | [a526504d18](https://linux-hardware.org/?probe=a526504d18) | Feb 18, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [46289356fa](https://linux-hardware.org/?probe=46289356fa) | Feb 18, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | Desktop     | [fa6a3fe6e3](https://linux-hardware.org/?probe=fa6a3fe6e3) | Feb 17, 2023 |
| Unknown       | Unknown                     | Notebook    | [7d36f8eee5](https://linux-hardware.org/?probe=7d36f8eee5) | Feb 16, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [39b9facc37](https://linux-hardware.org/?probe=39b9facc37) | Feb 16, 2023 |
| MSI           | GS66 Stealth 10UE           | Notebook    | [587bd9e282](https://linux-hardware.org/?probe=587bd9e282) | Feb 16, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [2c0799202c](https://linux-hardware.org/?probe=2c0799202c) | Feb 15, 2023 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [991db4f096](https://linux-hardware.org/?probe=991db4f096) | Feb 14, 2023 |
| MSI           | Vector GP66 12UEO           | Notebook    | [040bddeff8](https://linux-hardware.org/?probe=040bddeff8) | Feb 14, 2023 |
| Unknown       | Unknown                     | Notebook    | [1f80b65b37](https://linux-hardware.org/?probe=1f80b65b37) | Feb 13, 2023 |
| Unknown       | Unknown                     | Notebook    | [8b28eb095c](https://linux-hardware.org/?probe=8b28eb095c) | Feb 13, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [e474459ee0](https://linux-hardware.org/?probe=e474459ee0) | Feb 13, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [1263022267](https://linux-hardware.org/?probe=1263022267) | Feb 13, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [94ca7f3e34](https://linux-hardware.org/?probe=94ca7f3e34) | Feb 13, 2023 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [6a952f7024](https://linux-hardware.org/?probe=6a952f7024) | Feb 13, 2023 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [e8ba753fae](https://linux-hardware.org/?probe=e8ba753fae) | Feb 13, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [7eb2b7e26f](https://linux-hardware.org/?probe=7eb2b7e26f) | Feb 13, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [36a0d5221f](https://linux-hardware.org/?probe=36a0d5221f) | Feb 13, 2023 |
| Apple         | MacBookPro10,2              | Notebook    | [aedfc67444](https://linux-hardware.org/?probe=aedfc67444) | Feb 12, 2023 |
| Unknown       | Unknown                     | Notebook    | [e0fd4c1db9](https://linux-hardware.org/?probe=e0fd4c1db9) | Feb 11, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [95337ab460](https://linux-hardware.org/?probe=95337ab460) | Feb 11, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [12c06a594d](https://linux-hardware.org/?probe=12c06a594d) | Feb 10, 2023 |
| Supermicro    | H11SSL-i                    | Server      | [ba881ed411](https://linux-hardware.org/?probe=ba881ed411) | Feb 10, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [469eaa6fba](https://linux-hardware.org/?probe=469eaa6fba) | Feb 10, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | Desktop     | [1423d5ac1b](https://linux-hardware.org/?probe=1423d5ac1b) | Feb 10, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | Desktop     | [bb589c5e58](https://linux-hardware.org/?probe=bb589c5e58) | Feb 10, 2023 |
| Gigabyte      | B650 AORUS PRO AX           | Desktop     | [4998be684f](https://linux-hardware.org/?probe=4998be684f) | Feb 10, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [2cfb05371e](https://linux-hardware.org/?probe=2cfb05371e) | Feb 09, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [4468518165](https://linux-hardware.org/?probe=4468518165) | Feb 09, 2023 |
| Apple         | MacBookPro10,2              | Notebook    | [85b07c179c](https://linux-hardware.org/?probe=85b07c179c) | Feb 09, 2023 |
| Apple         | MacBookPro10,2              | Notebook    | [238c7a2c08](https://linux-hardware.org/?probe=238c7a2c08) | Feb 09, 2023 |
| MSI           | X370 XPOWER GAMING TITAN... | Desktop     | [f09cd898c8](https://linux-hardware.org/?probe=f09cd898c8) | Feb 09, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [c71dba27f2](https://linux-hardware.org/?probe=c71dba27f2) | Feb 08, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [83b847229c](https://linux-hardware.org/?probe=83b847229c) | Feb 08, 2023 |
| Dell          | Precision 7770              | Notebook    | [69b0982ad7](https://linux-hardware.org/?probe=69b0982ad7) | Feb 08, 2023 |
| Dell          | Precision 7770              | Notebook    | [28ba6f72d0](https://linux-hardware.org/?probe=28ba6f72d0) | Feb 07, 2023 |
| Dell          | Precision 7770              | Notebook    | [d05aabf7a5](https://linux-hardware.org/?probe=d05aabf7a5) | Feb 06, 2023 |
| Valve         | Jupiter                     | Notebook    | [42a3945648](https://linux-hardware.org/?probe=42a3945648) | Feb 06, 2023 |
| Gigabyte      | B150M-D2V DDR3-CF           | Desktop     | [bc0593280c](https://linux-hardware.org/?probe=bc0593280c) | Feb 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | Notebook    | [2ac999e9b0](https://linux-hardware.org/?probe=2ac999e9b0) | Feb 05, 2023 |
| Valve         | Jupiter                     | Notebook    | [5f77ae27c2](https://linux-hardware.org/?probe=5f77ae27c2) | Feb 04, 2023 |
| Radxa         | ROCK 5B                     | Soc         | [78a631609d](https://linux-hardware.org/?probe=78a631609d) | Feb 04, 2023 |
| Gigabyte      | B150M-D2V DDR3-CF           | Desktop     | [e12e1d2598](https://linux-hardware.org/?probe=e12e1d2598) | Feb 04, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [be3ef90301](https://linux-hardware.org/?probe=be3ef90301) | Feb 04, 2023 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | Notebook    | [37d0cc301b](https://linux-hardware.org/?probe=37d0cc301b) | Feb 03, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [a8dcc6b4c1](https://linux-hardware.org/?probe=a8dcc6b4c1) | Feb 03, 2023 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | Notebook    | [a08ee9b387](https://linux-hardware.org/?probe=a08ee9b387) | Feb 03, 2023 |
| Dell          | Precision 7770              | Notebook    | [20f6b87742](https://linux-hardware.org/?probe=20f6b87742) | Feb 03, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [0cf18835cc](https://linux-hardware.org/?probe=0cf18835cc) | Feb 02, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [80921f3386](https://linux-hardware.org/?probe=80921f3386) | Feb 01, 2023 |
| ASUSTek       | GL702VT                     | Notebook    | [83abe24c59](https://linux-hardware.org/?probe=83abe24c59) | Feb 01, 2023 |
| MSI           | GP60 2PE                    | Notebook    | [a1bb8934a0](https://linux-hardware.org/?probe=a1bb8934a0) | Feb 01, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CH0... | Notebook    | [78eeec802b](https://linux-hardware.org/?probe=78eeec802b) | Feb 01, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [9fb41ee5bc](https://linux-hardware.org/?probe=9fb41ee5bc) | Feb 01, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [4bb9990abe](https://linux-hardware.org/?probe=4bb9990abe) | Feb 01, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [396877a008](https://linux-hardware.org/?probe=396877a008) | Jan 31, 2023 |
| Sony          | PCG-GRT230(UC)              | Notebook    | [0a7c76da78](https://linux-hardware.org/?probe=0a7c76da78) | Jan 30, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [5a2c721748](https://linux-hardware.org/?probe=5a2c721748) | Jan 30, 2023 |
| ASUSTek       | ProArt B550-CREATOR         | Desktop     | [c93e84b79b](https://linux-hardware.org/?probe=c93e84b79b) | Jan 29, 2023 |
| Google        | Helios                      | Notebook    | [c8b5d0660b](https://linux-hardware.org/?probe=c8b5d0660b) | Jan 28, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [f71299a9c6](https://linux-hardware.org/?probe=f71299a9c6) | Jan 27, 2023 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [a30690db0c](https://linux-hardware.org/?probe=a30690db0c) | Jan 27, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [9001ac4e36](https://linux-hardware.org/?probe=9001ac4e36) | Jan 27, 2023 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [90f37ac742](https://linux-hardware.org/?probe=90f37ac742) | Jan 26, 2023 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [e524d7c4d9](https://linux-hardware.org/?probe=e524d7c4d9) | Jan 26, 2023 |
| Dell          | XPS 9320                    | Notebook    | [a1040b4a3f](https://linux-hardware.org/?probe=a1040b4a3f) | Jan 26, 2023 |
| Dell          | Latitude 5530               | Notebook    | [b365359e5f](https://linux-hardware.org/?probe=b365359e5f) | Jan 24, 2023 |
| Lenovo        | 1030 SDK0Q40104 WIN 3305... | Desktop     | [6a876fb2b4](https://linux-hardware.org/?probe=6a876fb2b4) | Jan 23, 2023 |
| Lenovo        | 1030 SDK0Q40104 WIN 3305... | Desktop     | [287d005187](https://linux-hardware.org/?probe=287d005187) | Jan 23, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [c2f89a9e58](https://linux-hardware.org/?probe=c2f89a9e58) | Jan 23, 2023 |
| Dell          | Precision 7770              | Notebook    | [47044d362f](https://linux-hardware.org/?probe=47044d362f) | Jan 22, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [2f02d895e2](https://linux-hardware.org/?probe=2f02d895e2) | Jan 22, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [92280be854](https://linux-hardware.org/?probe=92280be854) | Jan 22, 2023 |
| Lenovo        | ThinkPad T470s 20HGS27Y0... | Notebook    | [e1678320fc](https://linux-hardware.org/?probe=e1678320fc) | Jan 22, 2023 |
| Gigabyte      | B150M-D2V DDR3-CF           | Desktop     | [69bf20ee28](https://linux-hardware.org/?probe=69bf20ee28) | Jan 21, 2023 |
| Gigabyte      | B150M-D2V DDR3-CF           | Desktop     | [dfd88e113a](https://linux-hardware.org/?probe=dfd88e113a) | Jan 21, 2023 |
| Dell          | XPS 9320                    | Notebook    | [ebe686793d](https://linux-hardware.org/?probe=ebe686793d) | Jan 21, 2023 |
| Dell          | XPS 9320                    | Notebook    | [706152a268](https://linux-hardware.org/?probe=706152a268) | Jan 21, 2023 |
| Dell          | XPS 17 9700                 | Notebook    | [d37b338c87](https://linux-hardware.org/?probe=d37b338c87) | Jan 21, 2023 |
| Dell          | XPS 17 9700                 | Notebook    | [413cd3b7cf](https://linux-hardware.org/?probe=413cd3b7cf) | Jan 21, 2023 |
| Lenovo        | ThinkPad X1 Titanium Gen... | Convertible | [69f4adcf81](https://linux-hardware.org/?probe=69f4adcf81) | Jan 20, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [1f935f0c7b](https://linux-hardware.org/?probe=1f935f0c7b) | Jan 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [6c2dd878d0](https://linux-hardware.org/?probe=6c2dd878d0) | Jan 19, 2023 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [0e8d25f649](https://linux-hardware.org/?probe=0e8d25f649) | Jan 19, 2023 |
| ASUSTek       | PRIME H570M-PLUS            | Desktop     | [4932579d3e](https://linux-hardware.org/?probe=4932579d3e) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [5f73278ca0](https://linux-hardware.org/?probe=5f73278ca0) | Jan 19, 2023 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [a1b3ac9ccc](https://linux-hardware.org/?probe=a1b3ac9ccc) | Jan 19, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [b11a63e25d](https://linux-hardware.org/?probe=b11a63e25d) | Jan 19, 2023 |
| ASUSTek       | ROG Strix G732LXS_G732LX... | Notebook    | [753a61e1de](https://linux-hardware.org/?probe=753a61e1de) | Jan 19, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [7aa00b2d9f](https://linux-hardware.org/?probe=7aa00b2d9f) | Jan 19, 2023 |
| ASUSTek       | ROG Strix G732LXS_G732LX... | Notebook    | [b14d57e1a3](https://linux-hardware.org/?probe=b14d57e1a3) | Jan 19, 2023 |
| Dell          | Precision 7720              | Notebook    | [9a00916b91](https://linux-hardware.org/?probe=9a00916b91) | Jan 19, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [0770f064de](https://linux-hardware.org/?probe=0770f064de) | Jan 19, 2023 |
| Schenker      | XMG PRO (E22)               | Notebook    | [475e812e56](https://linux-hardware.org/?probe=475e812e56) | Jan 19, 2023 |
| ASRock        | AM1H-ITX                    | Desktop     | [7427c997d7](https://linux-hardware.org/?probe=7427c997d7) | Jan 18, 2023 |
| Dell          | Latitude 5410               | Notebook    | [da523f9f4c](https://linux-hardware.org/?probe=da523f9f4c) | Jan 18, 2023 |
| Lenovo        | ThinkPad X1 Titanium Gen... | Convertible | [b4e1da9857](https://linux-hardware.org/?probe=b4e1da9857) | Jan 17, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | Desktop     | [d78fd14781](https://linux-hardware.org/?probe=d78fd14781) | Jan 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d6b6c22af1](https://linux-hardware.org/?probe=d6b6c22af1) | Jan 17, 2023 |
| ASUSTek       | X99-A/USB                   | Desktop     | [0d5c9f7a33](https://linux-hardware.org/?probe=0d5c9f7a33) | Jan 16, 2023 |
| Dell          | Precision 7720              | Notebook    | [f8e1c53257](https://linux-hardware.org/?probe=f8e1c53257) | Jan 16, 2023 |
| MSI           | Bravo 15 B5DD               | Notebook    | [8e35281ea5](https://linux-hardware.org/?probe=8e35281ea5) | Jan 16, 2023 |
| Acer          | Predator PH315-51           | Notebook    | [0b2ae38776](https://linux-hardware.org/?probe=0b2ae38776) | Jan 16, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [5e6192ed2b](https://linux-hardware.org/?probe=5e6192ed2b) | Jan 16, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [94ba7a4ca6](https://linux-hardware.org/?probe=94ba7a4ca6) | Jan 16, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [25cf332260](https://linux-hardware.org/?probe=25cf332260) | Jan 15, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [3f12fad87c](https://linux-hardware.org/?probe=3f12fad87c) | Jan 15, 2023 |
| Lenovo        | ThinkPad X1 Titanium Gen... | Convertible | [ca74e79834](https://linux-hardware.org/?probe=ca74e79834) | Jan 15, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [eeeb041ca6](https://linux-hardware.org/?probe=eeeb041ca6) | Jan 13, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [306315e4d8](https://linux-hardware.org/?probe=306315e4d8) | Jan 12, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [4fe502c977](https://linux-hardware.org/?probe=4fe502c977) | Jan 10, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [aac6fb4537](https://linux-hardware.org/?probe=aac6fb4537) | Jan 09, 2023 |
| Google        | Sasuke                      | Notebook    | [aa3a09aaef](https://linux-hardware.org/?probe=aa3a09aaef) | Jan 07, 2023 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [b5dd8ee9f3](https://linux-hardware.org/?probe=b5dd8ee9f3) | Jan 07, 2023 |
| Timi          | Mi Laptop Pro 15            | Notebook    | [7ea6f8ee94](https://linux-hardware.org/?probe=7ea6f8ee94) | Jan 06, 2023 |
| Dell          | 0J3C2F A02                  | Desktop     | [0944e31ade](https://linux-hardware.org/?probe=0944e31ade) | Jan 06, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [659196ed95](https://linux-hardware.org/?probe=659196ed95) | Jan 06, 2023 |
| HP            | 212A                        | Desktop     | [21acb67653](https://linux-hardware.org/?probe=21acb67653) | Jan 06, 2023 |
| Lenovo        | ThinkPad T480 20L6S04Q00    | Notebook    | [0dbae6cda4](https://linux-hardware.org/?probe=0dbae6cda4) | Jan 06, 2023 |
| Lenovo        | ThinkPad T480 20L6S04Q00    | Notebook    | [bca9343f96](https://linux-hardware.org/?probe=bca9343f96) | Jan 06, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [bb78c165c7](https://linux-hardware.org/?probe=bb78c165c7) | Jan 06, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [40a6c7370b](https://linux-hardware.org/?probe=40a6c7370b) | Jan 05, 2023 |
| Acer          | TravelMate B115-M           | Notebook    | [c39cf71ff8](https://linux-hardware.org/?probe=c39cf71ff8) | Jan 05, 2023 |
| ASRock        | AM1H-ITX                    | Desktop     | [3b32e784a3](https://linux-hardware.org/?probe=3b32e784a3) | Jan 03, 2023 |
| Dell          | Precision 7720              | Notebook    | [59813a7461](https://linux-hardware.org/?probe=59813a7461) | Jan 03, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [92052e9c47](https://linux-hardware.org/?probe=92052e9c47) | Jan 02, 2023 |
| Supermicro    | H12SSL-NT                   | Server      | [954e228bd5](https://linux-hardware.org/?probe=954e228bd5) | Dec 31, 2022 |
| Dell          | 0TWFTR A02                  | All in one  | [5f63c2fd15](https://linux-hardware.org/?probe=5f63c2fd15) | Dec 31, 2022 |
| Phoenix       | 945GM                       | Desktop     | [d391eaf6e2](https://linux-hardware.org/?probe=d391eaf6e2) | Dec 31, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [a5030d74d4](https://linux-hardware.org/?probe=a5030d74d4) | Dec 31, 2022 |
| HP            | ProLiant DL360p Gen8        | Server      | [9b6998f35c](https://linux-hardware.org/?probe=9b6998f35c) | Dec 31, 2022 |
| Lenovo        | ThinkPad W540 20BG0033RT    | Notebook    | [5cfa12cec1](https://linux-hardware.org/?probe=5cfa12cec1) | Dec 31, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [4b130212a2](https://linux-hardware.org/?probe=4b130212a2) | Dec 30, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [0c7ced8708](https://linux-hardware.org/?probe=0c7ced8708) | Dec 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [bd53b75b7b](https://linux-hardware.org/?probe=bd53b75b7b) | Dec 30, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [9a05e8c413](https://linux-hardware.org/?probe=9a05e8c413) | Dec 30, 2022 |
| Unknown       | Freecom Silverstore HNCN... | Desktop     | [723fbcd23f](https://linux-hardware.org/?probe=723fbcd23f) | Dec 29, 2022 |
| Dell          | Precision 7720              | Notebook    | [56db0ab146](https://linux-hardware.org/?probe=56db0ab146) | Dec 28, 2022 |
| Dell          | Precision 7720              | Notebook    | [e94a7bb989](https://linux-hardware.org/?probe=e94a7bb989) | Dec 28, 2022 |
| Dell          | G3 3500                     | Notebook    | [78e803b44e](https://linux-hardware.org/?probe=78e803b44e) | Dec 28, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [03cca95360](https://linux-hardware.org/?probe=03cca95360) | Dec 27, 2022 |
| System76      | Darter Pro                  | Notebook    | [c5aebaaece](https://linux-hardware.org/?probe=c5aebaaece) | Dec 27, 2022 |
| Dell          | G5 5505                     | Notebook    | [87f62bee87](https://linux-hardware.org/?probe=87f62bee87) | Dec 26, 2022 |
| Supermicro    | X10SL7-F                    | Server      | [9c75de7af7](https://linux-hardware.org/?probe=9c75de7af7) | Dec 26, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [5d2498f405](https://linux-hardware.org/?probe=5d2498f405) | Dec 26, 2022 |
| Star Labs     | StarLite                    | Notebook    | [0d27e6f7ee](https://linux-hardware.org/?probe=0d27e6f7ee) | Dec 25, 2022 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [d759e5fe02](https://linux-hardware.org/?probe=d759e5fe02) | Dec 25, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [77390ced3c](https://linux-hardware.org/?probe=77390ced3c) | Dec 24, 2022 |
| Supermicro    | X10DSC+                     | Desktop     | [cf559d5e84](https://linux-hardware.org/?probe=cf559d5e84) | Dec 24, 2022 |
| Dell          | Vostro 5490                 | Notebook    | [f694fa24c8](https://linux-hardware.org/?probe=f694fa24c8) | Dec 23, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | Notebook    | [0c1d9b9b28](https://linux-hardware.org/?probe=0c1d9b9b28) | Dec 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [25cbb2c39a](https://linux-hardware.org/?probe=25cbb2c39a) | Dec 23, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | Notebook    | [000660b461](https://linux-hardware.org/?probe=000660b461) | Dec 23, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [0277928378](https://linux-hardware.org/?probe=0277928378) | Dec 23, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [ec6b0e70a2](https://linux-hardware.org/?probe=ec6b0e70a2) | Dec 21, 2022 |
| Supermicro    | X10SRL-FB                   | Server      | [5fd1a2d6e1](https://linux-hardware.org/?probe=5fd1a2d6e1) | Dec 21, 2022 |
| HP            | 0980h                       | Desktop     | [d54665c87c](https://linux-hardware.org/?probe=d54665c87c) | Dec 21, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | Notebook    | [638667a90f](https://linux-hardware.org/?probe=638667a90f) | Dec 20, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [b9aed745da](https://linux-hardware.org/?probe=b9aed745da) | Dec 20, 2022 |
| HP            | 0980h                       | Desktop     | [3faf0c7996](https://linux-hardware.org/?probe=3faf0c7996) | Dec 20, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [c7cea6dd19](https://linux-hardware.org/?probe=c7cea6dd19) | Dec 20, 2022 |
| HP            | 83E9                        | Desktop     | [02e854bd7c](https://linux-hardware.org/?probe=02e854bd7c) | Dec 20, 2022 |
| Dell          | Inspiron 15 3511            | Notebook    | [3d33008fb2](https://linux-hardware.org/?probe=3d33008fb2) | Dec 19, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [2318fda45f](https://linux-hardware.org/?probe=2318fda45f) | Dec 19, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [70a0e2a296](https://linux-hardware.org/?probe=70a0e2a296) | Dec 19, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [e0f5a5db4c](https://linux-hardware.org/?probe=e0f5a5db4c) | Dec 18, 2022 |
| Lenovo        | ThinkPad T470p 20J7S25C0... | Notebook    | [3dc497faf1](https://linux-hardware.org/?probe=3dc497faf1) | Dec 18, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [f15a27fd5e](https://linux-hardware.org/?probe=f15a27fd5e) | Dec 17, 2022 |
| HP            | 83E9                        | Desktop     | [cdf4ff19a6](https://linux-hardware.org/?probe=cdf4ff19a6) | Dec 17, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [d8774d83a7](https://linux-hardware.org/?probe=d8774d83a7) | Dec 16, 2022 |
| HP            | 83E9                        | Desktop     | [53f1974d93](https://linux-hardware.org/?probe=53f1974d93) | Dec 16, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [1860105d14](https://linux-hardware.org/?probe=1860105d14) | Dec 16, 2022 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [3807037a5c](https://linux-hardware.org/?probe=3807037a5c) | Dec 15, 2022 |
| Acer          | Predator PH315-51           | Notebook    | [34676168fa](https://linux-hardware.org/?probe=34676168fa) | Dec 14, 2022 |
| Acer          | Predator PH315-51           | Notebook    | [0f9b4ae170](https://linux-hardware.org/?probe=0f9b4ae170) | Dec 14, 2022 |
| HP            | 212A                        | Desktop     | [c21bb6d20d](https://linux-hardware.org/?probe=c21bb6d20d) | Dec 14, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [8370a57760](https://linux-hardware.org/?probe=8370a57760) | Dec 12, 2022 |
| Gigabyte      | B650 AORUS PRO AX           | Desktop     | [b7374c7211](https://linux-hardware.org/?probe=b7374c7211) | Dec 12, 2022 |
| Supermicro    | H12SSL-NT                   | Server      | [82bfec7c72](https://linux-hardware.org/?probe=82bfec7c72) | Dec 12, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [177dded9e0](https://linux-hardware.org/?probe=177dded9e0) | Dec 12, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [7541ce9ac6](https://linux-hardware.org/?probe=7541ce9ac6) | Dec 11, 2022 |
| MSI           | K9N2 Diamond                | Desktop     | [0a42d5e656](https://linux-hardware.org/?probe=0a42d5e656) | Dec 11, 2022 |
| Star Labs     | StarLite                    | Notebook    | [0d83c191fa](https://linux-hardware.org/?probe=0d83c191fa) | Dec 10, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [6dd02812db](https://linux-hardware.org/?probe=6dd02812db) | Dec 10, 2022 |
| HP            | ProBook 6570b               | Notebook    | [073546a981](https://linux-hardware.org/?probe=073546a981) | Dec 10, 2022 |
| Supermicro    | H12SSL-NT                   | Server      | [afb0183c71](https://linux-hardware.org/?probe=afb0183c71) | Dec 10, 2022 |
| Star Labs     | StarLite                    | Notebook    | [4446ba1d6a](https://linux-hardware.org/?probe=4446ba1d6a) | Dec 10, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [bede7701b9](https://linux-hardware.org/?probe=bede7701b9) | Dec 08, 2022 |
| Google        | Eve                         | Notebook    | [d78558c833](https://linux-hardware.org/?probe=d78558c833) | Dec 08, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [26f56cc499](https://linux-hardware.org/?probe=26f56cc499) | Dec 08, 2022 |
| Google        | Eve                         | Notebook    | [92d1d03fed](https://linux-hardware.org/?probe=92d1d03fed) | Dec 08, 2022 |
| Gigabyte      | B650 AORUS PRO AX           | Desktop     | [15f27b7ac6](https://linux-hardware.org/?probe=15f27b7ac6) | Dec 08, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [15d7102174](https://linux-hardware.org/?probe=15d7102174) | Dec 08, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [52525a1058](https://linux-hardware.org/?probe=52525a1058) | Dec 08, 2022 |
| ASRock        | AB350M                      | Desktop     | [95a14fd558](https://linux-hardware.org/?probe=95a14fd558) | Dec 07, 2022 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [13ac8bc162](https://linux-hardware.org/?probe=13ac8bc162) | Dec 06, 2022 |
| Samsung       | 950QED                      | Convertible | [396d57bb34](https://linux-hardware.org/?probe=396d57bb34) | Dec 06, 2022 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [c3510d4787](https://linux-hardware.org/?probe=c3510d4787) | Dec 06, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [ccf3e1f074](https://linux-hardware.org/?probe=ccf3e1f074) | Dec 05, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [60b1be0a32](https://linux-hardware.org/?probe=60b1be0a32) | Dec 05, 2022 |
| Gigabyte      | B650M DS3H                  | Desktop     | [73b49404f9](https://linux-hardware.org/?probe=73b49404f9) | Dec 05, 2022 |
| Toshiba       | Satellite L50-B             | Notebook    | [6d92129c25](https://linux-hardware.org/?probe=6d92129c25) | Dec 05, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [9fec7bdfdc](https://linux-hardware.org/?probe=9fec7bdfdc) | Dec 04, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [22fc01fd20](https://linux-hardware.org/?probe=22fc01fd20) | Dec 04, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [84a50cd483](https://linux-hardware.org/?probe=84a50cd483) | Dec 03, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [debbc3f9ff](https://linux-hardware.org/?probe=debbc3f9ff) | Dec 03, 2022 |
| ASUSTek       | P8Z68-V PRO                 | Desktop     | [2adb8631b0](https://linux-hardware.org/?probe=2adb8631b0) | Dec 03, 2022 |
| HP            | G62                         | Notebook    | [494d9e65e4](https://linux-hardware.org/?probe=494d9e65e4) | Dec 03, 2022 |
| Pegatron      | 2AC2                        | Desktop     | [29d43d4af8](https://linux-hardware.org/?probe=29d43d4af8) | Dec 03, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ee24c782fa](https://linux-hardware.org/?probe=ee24c782fa) | Dec 02, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [f9379c4ffb](https://linux-hardware.org/?probe=f9379c4ffb) | Dec 01, 2022 |
| Unknown       | Unknown                     | Notebook    | [dceef2a9d5](https://linux-hardware.org/?probe=dceef2a9d5) | Dec 01, 2022 |
| Pegatron      | 2AC2                        | Desktop     | [3d92c6cbc8](https://linux-hardware.org/?probe=3d92c6cbc8) | Dec 01, 2022 |
| HP            | EliteBook 820 G3            | Notebook    | [d313455fa8](https://linux-hardware.org/?probe=d313455fa8) | Dec 01, 2022 |
| HP            | EliteBook 820 G3            | Notebook    | [31b9efe771](https://linux-hardware.org/?probe=31b9efe771) | Dec 01, 2022 |
| Lenovo        | ThinkBook 14s-IWL 20RM      | Notebook    | [d77cb5ebb0](https://linux-hardware.org/?probe=d77cb5ebb0) | Nov 30, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [e3f55c7b9d](https://linux-hardware.org/?probe=e3f55c7b9d) | Nov 28, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [54407c7caa](https://linux-hardware.org/?probe=54407c7caa) | Nov 28, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [6bf87b9885](https://linux-hardware.org/?probe=6bf87b9885) | Nov 28, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [af7d162434](https://linux-hardware.org/?probe=af7d162434) | Nov 28, 2022 |
| HP            | 86EE                        | All in one  | [8533afb703](https://linux-hardware.org/?probe=8533afb703) | Nov 27, 2022 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [02c62a5eb8](https://linux-hardware.org/?probe=02c62a5eb8) | Nov 27, 2022 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [6206268283](https://linux-hardware.org/?probe=6206268283) | Nov 27, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [f2fe1d140e](https://linux-hardware.org/?probe=f2fe1d140e) | Nov 26, 2022 |
| Acer          | Swift SF314-57              | Notebook    | [ba4ed6c5f4](https://linux-hardware.org/?probe=ba4ed6c5f4) | Nov 26, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [1bd15590c9](https://linux-hardware.org/?probe=1bd15590c9) | Nov 25, 2022 |
| Razer         | Blade Pro                   | Notebook    | [dabfd64904](https://linux-hardware.org/?probe=dabfd64904) | Nov 25, 2022 |
| MSI           | TRX40 PRO WIFI              | Desktop     | [3617f324a2](https://linux-hardware.org/?probe=3617f324a2) | Nov 24, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | Notebook    | [fa4e2d1d61](https://linux-hardware.org/?probe=fa4e2d1d61) | Nov 23, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [b0d3226df4](https://linux-hardware.org/?probe=b0d3226df4) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [c150f785ea](https://linux-hardware.org/?probe=c150f785ea) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [4f36ecd91b](https://linux-hardware.org/?probe=4f36ecd91b) | Nov 19, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [f58f70b732](https://linux-hardware.org/?probe=f58f70b732) | Nov 19, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [16fc755db2](https://linux-hardware.org/?probe=16fc755db2) | Nov 19, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [8ffb460b9e](https://linux-hardware.org/?probe=8ffb460b9e) | Nov 19, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [ea05374336](https://linux-hardware.org/?probe=ea05374336) | Nov 19, 2022 |
| Unknown       | QNAP TS-221                 | Desktop     | [b9ff535a3f](https://linux-hardware.org/?probe=b9ff535a3f) | Nov 18, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [74a3983b1e](https://linux-hardware.org/?probe=74a3983b1e) | Nov 18, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | Desktop     | [45fbc31f55](https://linux-hardware.org/?probe=45fbc31f55) | Nov 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | Desktop     | [a5eb8c6aaa](https://linux-hardware.org/?probe=a5eb8c6aaa) | Nov 17, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [8a94d169c5](https://linux-hardware.org/?probe=8a94d169c5) | Nov 17, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [fbe52d681e](https://linux-hardware.org/?probe=fbe52d681e) | Nov 17, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [5fd36e3d66](https://linux-hardware.org/?probe=5fd36e3d66) | Nov 17, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [62b2a72fa9](https://linux-hardware.org/?probe=62b2a72fa9) | Nov 16, 2022 |
| Unknown       | Unknown                     | Notebook    | [f3222cf843](https://linux-hardware.org/?probe=f3222cf843) | Nov 16, 2022 |
| Unknown       | Unknown                     | Notebook    | [9217d900c4](https://linux-hardware.org/?probe=9217d900c4) | Nov 16, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [b870eb1d72](https://linux-hardware.org/?probe=b870eb1d72) | Nov 15, 2022 |
| MSI           | MEG X570 GODLIKE            | Desktop     | [de10599614](https://linux-hardware.org/?probe=de10599614) | Nov 15, 2022 |
| ASUSTek       | X510UNR                     | Notebook    | [dea1636b05](https://linux-hardware.org/?probe=dea1636b05) | Nov 15, 2022 |
| ASUSTek       | X510UNR                     | Notebook    | [9ed613b632](https://linux-hardware.org/?probe=9ed613b632) | Nov 15, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [642a889fcc](https://linux-hardware.org/?probe=642a889fcc) | Nov 14, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | Notebook    | [1798f04a0b](https://linux-hardware.org/?probe=1798f04a0b) | Nov 14, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZM... | Notebook    | [346303c711](https://linux-hardware.org/?probe=346303c711) | Nov 14, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | Notebook    | [64fb474239](https://linux-hardware.org/?probe=64fb474239) | Nov 14, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [7f21362848](https://linux-hardware.org/?probe=7f21362848) | Nov 14, 2022 |
| MSI           | GT72 2QD                    | Notebook    | [cbd0b88f5f](https://linux-hardware.org/?probe=cbd0b88f5f) | Nov 14, 2022 |
| MSI           | GT72 2QD                    | Notebook    | [0e9a1a51a5](https://linux-hardware.org/?probe=0e9a1a51a5) | Nov 14, 2022 |
| Lenovo        | ThinkPad S2 3rd Gen 20L1... | Notebook    | [2e29461f3b](https://linux-hardware.org/?probe=2e29461f3b) | Nov 13, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [cd18d68895](https://linux-hardware.org/?probe=cd18d68895) | Nov 13, 2022 |
| Supermicro    | X10DRT-P                    | Server      | [a56f11112b](https://linux-hardware.org/?probe=a56f11112b) | Nov 13, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [fa18a7779e](https://linux-hardware.org/?probe=fa18a7779e) | Nov 13, 2022 |
| Lenovo        | Yoga 6 13ARE05 82FN         | Convertible | [9d91de9f87](https://linux-hardware.org/?probe=9d91de9f87) | Nov 12, 2022 |
| Lenovo        | Yoga 6 13ARE05 82FN         | Convertible | [da754cf27a](https://linux-hardware.org/?probe=da754cf27a) | Nov 11, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [9db585ddc5](https://linux-hardware.org/?probe=9db585ddc5) | Nov 11, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [332cc61ddc](https://linux-hardware.org/?probe=332cc61ddc) | Nov 11, 2022 |
| ASUSTek       | PRIME Z370-P II             | Desktop     | [7a41c26bea](https://linux-hardware.org/?probe=7a41c26bea) | Nov 09, 2022 |
| Dell          | Precision 5540              | Notebook    | [2d459a448d](https://linux-hardware.org/?probe=2d459a448d) | Nov 09, 2022 |
| Acer          | Nitro AN515-58              | Notebook    | [9f4cb2a547](https://linux-hardware.org/?probe=9f4cb2a547) | Nov 09, 2022 |
| Toshiba       | Satellite L50-B             | Notebook    | [8939445388](https://linux-hardware.org/?probe=8939445388) | Nov 09, 2022 |
| Toshiba       | Satellite L50-B             | Notebook    | [420aaf8ede](https://linux-hardware.org/?probe=420aaf8ede) | Nov 09, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [a8f533624d](https://linux-hardware.org/?probe=a8f533624d) | Nov 08, 2022 |
| Dell          | G3 3500                     | Notebook    | [d3ae8a9d72](https://linux-hardware.org/?probe=d3ae8a9d72) | Nov 07, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [159ca02eca](https://linux-hardware.org/?probe=159ca02eca) | Nov 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [972094820e](https://linux-hardware.org/?probe=972094820e) | Nov 07, 2022 |
| ASRock        | B550 Extreme4               | Desktop     | [16154018bb](https://linux-hardware.org/?probe=16154018bb) | Nov 06, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [d238949b9f](https://linux-hardware.org/?probe=d238949b9f) | Nov 06, 2022 |
| Unknown       | X79-P3                      | Desktop     | [f069ed7bd9](https://linux-hardware.org/?probe=f069ed7bd9) | Nov 04, 2022 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [7b65a89d4f](https://linux-hardware.org/?probe=7b65a89d4f) | Nov 04, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [9a7d0e6d37](https://linux-hardware.org/?probe=9a7d0e6d37) | Nov 03, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [81a04d40a3](https://linux-hardware.org/?probe=81a04d40a3) | Nov 03, 2022 |
| Lenovo        | ThinkPad S2 3rd Gen 20L1... | Notebook    | [dda5d2dd10](https://linux-hardware.org/?probe=dda5d2dd10) | Nov 03, 2022 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | Desktop     | [953e399168](https://linux-hardware.org/?probe=953e399168) | Nov 03, 2022 |
| Lenovo        | ThinkPad S2 3rd Gen 20L1... | Notebook    | [c0f68304d1](https://linux-hardware.org/?probe=c0f68304d1) | Nov 03, 2022 |
| Acer          | Nitro AN515-43              | Notebook    | [8ca3bfde82](https://linux-hardware.org/?probe=8ca3bfde82) | Nov 02, 2022 |
| ASUSTek       | N55SF                       | Notebook    | [02af74ebb6](https://linux-hardware.org/?probe=02af74ebb6) | Nov 02, 2022 |
| Dell          | G3 3500                     | Notebook    | [c595a16f59](https://linux-hardware.org/?probe=c595a16f59) | Nov 02, 2022 |
| ASRock        | N68C-GS UCC                 | Desktop     | [9430ecf81c](https://linux-hardware.org/?probe=9430ecf81c) | Nov 02, 2022 |
| Lenovo        | ThinkPad S2 3rd Gen 20L1... | Notebook    | [48c0ef6251](https://linux-hardware.org/?probe=48c0ef6251) | Nov 02, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [5f81698e9a](https://linux-hardware.org/?probe=5f81698e9a) | Nov 02, 2022 |
| Lenovo        | ThinkPad S2 3rd Gen 20L1... | Notebook    | [1cc623c804](https://linux-hardware.org/?probe=1cc623c804) | Nov 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [310895b721](https://linux-hardware.org/?probe=310895b721) | Nov 01, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [1a88842782](https://linux-hardware.org/?probe=1a88842782) | Nov 01, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [966eb5bb18](https://linux-hardware.org/?probe=966eb5bb18) | Oct 31, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [860f45c4c1](https://linux-hardware.org/?probe=860f45c4c1) | Oct 31, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [c085788e44](https://linux-hardware.org/?probe=c085788e44) | Oct 31, 2022 |
| Lenovo        | ThinkPad Z16 Gen 1 21D4C... | Notebook    | [2e39c3ce92](https://linux-hardware.org/?probe=2e39c3ce92) | Oct 30, 2022 |
| Acidanther... | Mac-AA95B1DDAB278B95 iMa... | All in one  | [33df9c20bf](https://linux-hardware.org/?probe=33df9c20bf) | Oct 30, 2022 |
| Acidanther... | Mac-AA95B1DDAB278B95 iMa... | All in one  | [c63ee0d1b7](https://linux-hardware.org/?probe=c63ee0d1b7) | Oct 30, 2022 |
| Dell          | Vostro 5490                 | Notebook    | [057163f0e4](https://linux-hardware.org/?probe=057163f0e4) | Oct 29, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | Notebook    | [42fcb880db](https://linux-hardware.org/?probe=42fcb880db) | Oct 29, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | Notebook    | [242fbb2c79](https://linux-hardware.org/?probe=242fbb2c79) | Oct 29, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [98fe919d0e](https://linux-hardware.org/?probe=98fe919d0e) | Oct 29, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [9a6e9239e1](https://linux-hardware.org/?probe=9a6e9239e1) | Oct 29, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | Notebook    | [7800fc7b5b](https://linux-hardware.org/?probe=7800fc7b5b) | Oct 29, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [836d9e4de1](https://linux-hardware.org/?probe=836d9e4de1) | Oct 29, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [b7b7481628](https://linux-hardware.org/?probe=b7b7481628) | Oct 29, 2022 |
| Acer          | AOD257                      | Notebook    | [d3efba72cc](https://linux-hardware.org/?probe=d3efba72cc) | Oct 28, 2022 |
| Dell          | Vostro 5490                 | Notebook    | [ac6587adbb](https://linux-hardware.org/?probe=ac6587adbb) | Oct 27, 2022 |
| Acer          | AOD257                      | Notebook    | [c399f9db2b](https://linux-hardware.org/?probe=c399f9db2b) | Oct 27, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [a44f774778](https://linux-hardware.org/?probe=a44f774778) | Oct 27, 2022 |
| Dell          | Precision 5570              | Notebook    | [d74abc314b](https://linux-hardware.org/?probe=d74abc314b) | Oct 25, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [c1ce4e70e0](https://linux-hardware.org/?probe=c1ce4e70e0) | Oct 25, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [64e6199c96](https://linux-hardware.org/?probe=64e6199c96) | Oct 25, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [35cf015c33](https://linux-hardware.org/?probe=35cf015c33) | Oct 25, 2022 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [cc2fc1e863](https://linux-hardware.org/?probe=cc2fc1e863) | Oct 24, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [9115752bd4](https://linux-hardware.org/?probe=9115752bd4) | Oct 24, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [aaad9f52d4](https://linux-hardware.org/?probe=aaad9f52d4) | Oct 24, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [ce77ed764b](https://linux-hardware.org/?probe=ce77ed764b) | Oct 24, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [d18380bf4c](https://linux-hardware.org/?probe=d18380bf4c) | Oct 24, 2022 |
| Gigabyte      | TRX40 DESIGNARE             | Desktop     | [16f90b14dc](https://linux-hardware.org/?probe=16f90b14dc) | Oct 22, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [b89b177dd7](https://linux-hardware.org/?probe=b89b177dd7) | Oct 22, 2022 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [80032ce2ea](https://linux-hardware.org/?probe=80032ce2ea) | Oct 22, 2022 |
| Huanan        | X99-F8 GAMING V2.0          | Desktop     | [7bc7482286](https://linux-hardware.org/?probe=7bc7482286) | Oct 21, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [f3890a4db1](https://linux-hardware.org/?probe=f3890a4db1) | Oct 21, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [cb901021a7](https://linux-hardware.org/?probe=cb901021a7) | Oct 21, 2022 |
| Lenovo        | ThinkPad R500 2714CTO       | Notebook    | [77de0f71bd](https://linux-hardware.org/?probe=77de0f71bd) | Oct 21, 2022 |
| Gigabyte      | G5 KD                       | Notebook    | [c0f91f7282](https://linux-hardware.org/?probe=c0f91f7282) | Oct 20, 2022 |
| Gigabyte      | G5 KD                       | Notebook    | [35db9f3cd8](https://linux-hardware.org/?probe=35db9f3cd8) | Oct 19, 2022 |
| Gigabyte      | F2A88XM-DS2                 | Desktop     | [d066cccd5a](https://linux-hardware.org/?probe=d066cccd5a) | Oct 19, 2022 |
| Notebook      | NS50_70MU                   | Notebook    | [0f13ae1769](https://linux-hardware.org/?probe=0f13ae1769) | Oct 19, 2022 |
| Lenovo        | ThinkPad R500 2714CTO       | Notebook    | [e480e5d6ae](https://linux-hardware.org/?probe=e480e5d6ae) | Oct 18, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [4644a299f3](https://linux-hardware.org/?probe=4644a299f3) | Oct 18, 2022 |
| Dell          | Precision 7760              | Notebook    | [44b60a4fcf](https://linux-hardware.org/?probe=44b60a4fcf) | Oct 18, 2022 |
| ASRock        | X670E Steel Legend          | Desktop     | [2b0983acd6](https://linux-hardware.org/?probe=2b0983acd6) | Oct 18, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [71ab3d919c](https://linux-hardware.org/?probe=71ab3d919c) | Oct 18, 2022 |
| Sony          | PCG-GRT230(UC)              | Notebook    | [b33a31225b](https://linux-hardware.org/?probe=b33a31225b) | Oct 18, 2022 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [caf126d0af](https://linux-hardware.org/?probe=caf126d0af) | Oct 18, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [41d3e4e97d](https://linux-hardware.org/?probe=41d3e4e97d) | Oct 17, 2022 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | Notebook    | [6243f8cdb8](https://linux-hardware.org/?probe=6243f8cdb8) | Oct 17, 2022 |
| Dell          | G3 3500                     | Notebook    | [64698d52bb](https://linux-hardware.org/?probe=64698d52bb) | Oct 17, 2022 |
| Dell          | G3 3500                     | Notebook    | [902fc2d51b](https://linux-hardware.org/?probe=902fc2d51b) | Oct 17, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [926d661756](https://linux-hardware.org/?probe=926d661756) | Oct 17, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [e8377da07e](https://linux-hardware.org/?probe=e8377da07e) | Oct 17, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [f60fd55235](https://linux-hardware.org/?probe=f60fd55235) | Oct 16, 2022 |
| Supermicro    | X10SL7-F                    | Server      | [8bfcad8486](https://linux-hardware.org/?probe=8bfcad8486) | Oct 16, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [d2b5d08432](https://linux-hardware.org/?probe=d2b5d08432) | Oct 15, 2022 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [843e47e886](https://linux-hardware.org/?probe=843e47e886) | Oct 14, 2022 |
| Dell          | G3 3500                     | Notebook    | [f7cc47bb67](https://linux-hardware.org/?probe=f7cc47bb67) | Oct 13, 2022 |
| MSI           | Pulse GL66 11UGK            | Notebook    | [d71c1d033a](https://linux-hardware.org/?probe=d71c1d033a) | Oct 13, 2022 |
| MSI           | Pulse GL66 11UGK            | Notebook    | [07783bd6a7](https://linux-hardware.org/?probe=07783bd6a7) | Oct 13, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [f57f16d11b](https://linux-hardware.org/?probe=f57f16d11b) | Oct 13, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [55e6578ade](https://linux-hardware.org/?probe=55e6578ade) | Oct 13, 2022 |
| Gigabyte      | H81M-H                      | Desktop     | [63731688d0](https://linux-hardware.org/?probe=63731688d0) | Oct 13, 2022 |
| HP            | EliteBook 830 G6            | Notebook    | [0dc42d7e5e](https://linux-hardware.org/?probe=0dc42d7e5e) | Oct 12, 2022 |
| Notebook      | NS5x_NS7xPU                 | Notebook    | [b35f6c63de](https://linux-hardware.org/?probe=b35f6c63de) | Oct 12, 2022 |
| HP            | 2B26 A01                    | All in one  | [dec1b9e40f](https://linux-hardware.org/?probe=dec1b9e40f) | Oct 12, 2022 |
| HP            | 2B26 A01                    | All in one  | [3a0980d3d4](https://linux-hardware.org/?probe=3a0980d3d4) | Oct 12, 2022 |
| ASUSTek       | ROG Flow X13 GV301RE_GV3... | Convertible | [c88027a227](https://linux-hardware.org/?probe=c88027a227) | Oct 11, 2022 |
| IBM           | ThinkPad T42 2373K1U        | Notebook    | [934a3226e9](https://linux-hardware.org/?probe=934a3226e9) | Oct 11, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [1ae81569dd](https://linux-hardware.org/?probe=1ae81569dd) | Oct 11, 2022 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [11fb952122](https://linux-hardware.org/?probe=11fb952122) | Oct 10, 2022 |
| Intel Clie... | LAPBC710                    | Notebook    | [42b7bc6ee4](https://linux-hardware.org/?probe=42b7bc6ee4) | Oct 10, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [b04149c5ea](https://linux-hardware.org/?probe=b04149c5ea) | Oct 10, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [d7bcf0afa3](https://linux-hardware.org/?probe=d7bcf0afa3) | Oct 09, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [99d95e9424](https://linux-hardware.org/?probe=99d95e9424) | Oct 09, 2022 |
| Valve         | Jupiter                     | Notebook    | [1c71987bd5](https://linux-hardware.org/?probe=1c71987bd5) | Oct 08, 2022 |
| MSI           | X470 GAMING PLUS            | Desktop     | [cbac2de735](https://linux-hardware.org/?probe=cbac2de735) | Oct 08, 2022 |
| Intel Clie... | LAPBC710                    | Notebook    | [bacb30816f](https://linux-hardware.org/?probe=bacb30816f) | Oct 07, 2022 |
| ASUSTek       | ProArt Studiobook H7600Z... | Notebook    | [5db7aac5d3](https://linux-hardware.org/?probe=5db7aac5d3) | Oct 07, 2022 |
| HP            | Laptop 15-ra0xx             | Notebook    | [d81190b4e7](https://linux-hardware.org/?probe=d81190b4e7) | Oct 06, 2022 |
| ASUSTek       | T101HA                      | Tablet      | [237fe18fcd](https://linux-hardware.org/?probe=237fe18fcd) | Oct 05, 2022 |
| Alienware     | x14                         | Notebook    | [ad37874de1](https://linux-hardware.org/?probe=ad37874de1) | Oct 05, 2022 |
| Quanta        | S210-X12MS 31S2MMB0040      | Server      | [73fb38c162](https://linux-hardware.org/?probe=73fb38c162) | Oct 05, 2022 |
| Lenovo        | ThinkPad T430 2344BZU       | Notebook    | [ae4533cfd6](https://linux-hardware.org/?probe=ae4533cfd6) | Oct 03, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [6437ed8b0e](https://linux-hardware.org/?probe=6437ed8b0e) | Oct 03, 2022 |
| ASUSTek       | ROG Maximus XIII APEX       | Desktop     | [ae88619ae9](https://linux-hardware.org/?probe=ae88619ae9) | Oct 03, 2022 |
| MSI           | GE66 Raider 11UE            | Notebook    | [0eb2e22fc1](https://linux-hardware.org/?probe=0eb2e22fc1) | Oct 03, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [60bab6fe12](https://linux-hardware.org/?probe=60bab6fe12) | Oct 02, 2022 |
| Sony          | PCG-GRT230(UC)              | Notebook    | [cab24d4c04](https://linux-hardware.org/?probe=cab24d4c04) | Oct 01, 2022 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | Notebook    | [1cfda531dd](https://linux-hardware.org/?probe=1cfda531dd) | Oct 01, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [6d9c960574](https://linux-hardware.org/?probe=6d9c960574) | Sep 28, 2022 |
| HP            | EliteBook 8770w             | Notebook    | [e5ec559da4](https://linux-hardware.org/?probe=e5ec559da4) | Sep 28, 2022 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [4479784a2e](https://linux-hardware.org/?probe=4479784a2e) | Sep 28, 2022 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [d0808e8abe](https://linux-hardware.org/?probe=d0808e8abe) | Sep 27, 2022 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [b3b8d3e04f](https://linux-hardware.org/?probe=b3b8d3e04f) | Sep 26, 2022 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [9795d4f9aa](https://linux-hardware.org/?probe=9795d4f9aa) | Sep 26, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [6d3f575c3d](https://linux-hardware.org/?probe=6d3f575c3d) | Sep 26, 2022 |
| Sony          | PCG-GRT230(UC)              | Notebook    | [af843c265c](https://linux-hardware.org/?probe=af843c265c) | Sep 26, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [c447921f07](https://linux-hardware.org/?probe=c447921f07) | Sep 25, 2022 |
| Lenovo        | ThinkPad P73 20QRS0G700     | Notebook    | [b32a413aa9](https://linux-hardware.org/?probe=b32a413aa9) | Sep 25, 2022 |
| Lenovo        | Yoga 310-11IAP 80U2         | Convertible | [6c8a53f608](https://linux-hardware.org/?probe=6c8a53f608) | Sep 25, 2022 |
| Lenovo        | ThinkPad P73 20QRS0G700     | Notebook    | [6ea4c40a80](https://linux-hardware.org/?probe=6ea4c40a80) | Sep 25, 2022 |
| ASRock        | J3160M                      | Desktop     | [c9cc54f48e](https://linux-hardware.org/?probe=c9cc54f48e) | Sep 25, 2022 |
| HP            | EliteBook 830 G6            | Notebook    | [cdbc7c7949](https://linux-hardware.org/?probe=cdbc7c7949) | Sep 25, 2022 |
| Supermicro    | H11SSL-i                    | Server      | [dd3ce003e4](https://linux-hardware.org/?probe=dd3ce003e4) | Sep 25, 2022 |
| HP            | EliteBook 830 G6            | Notebook    | [907383d255](https://linux-hardware.org/?probe=907383d255) | Sep 25, 2022 |
| Matsushita... | CF-29LTQGZBM                | Notebook    | [29f52f862c](https://linux-hardware.org/?probe=29f52f862c) | Sep 24, 2022 |
| Acer          | Predator PH315-51           | Notebook    | [24ae1f3fb8](https://linux-hardware.org/?probe=24ae1f3fb8) | Sep 23, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [de7c138e21](https://linux-hardware.org/?probe=de7c138e21) | Sep 22, 2022 |
| Lenovo        | ThinkPad L580 20LWCTO1WW    | Notebook    | [a80367f777](https://linux-hardware.org/?probe=a80367f777) | Sep 21, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [d22f082243](https://linux-hardware.org/?probe=d22f082243) | Sep 21, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [e4f1a8245a](https://linux-hardware.org/?probe=e4f1a8245a) | Sep 21, 2022 |
| ASUSTek       | AM1M-A                      | Desktop     | [a6e61a9993](https://linux-hardware.org/?probe=a6e61a9993) | Sep 19, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [eb1c0556c3](https://linux-hardware.org/?probe=eb1c0556c3) | Sep 19, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [5a9ab0de04](https://linux-hardware.org/?probe=5a9ab0de04) | Sep 18, 2022 |
| System76      | Gazelle Professional        | Notebook    | [95f19a0c4c](https://linux-hardware.org/?probe=95f19a0c4c) | Sep 18, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d4d8cc3f34](https://linux-hardware.org/?probe=d4d8cc3f34) | Sep 16, 2022 |
| Dell          | G7 7588                     | Notebook    | [583c4a4c91](https://linux-hardware.org/?probe=583c4a4c91) | Sep 16, 2022 |
| Gigabyte      | Z590 UD                     | Desktop     | [475ed7f917](https://linux-hardware.org/?probe=475ed7f917) | Sep 15, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [7ad1180946](https://linux-hardware.org/?probe=7ad1180946) | Sep 14, 2022 |
| Timi          | TM1604                      | Notebook    | [80f52c9545](https://linux-hardware.org/?probe=80f52c9545) | Sep 14, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [7bc7cbca76](https://linux-hardware.org/?probe=7bc7cbca76) | Sep 12, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [225bd59ba7](https://linux-hardware.org/?probe=225bd59ba7) | Sep 12, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [ed5273b278](https://linux-hardware.org/?probe=ed5273b278) | Sep 11, 2022 |
| Intel         | X79G V2.x                   | Desktop     | [3cb7aa6549](https://linux-hardware.org/?probe=3cb7aa6549) | Sep 11, 2022 |
| MSI           | B450M MORTAR                | Desktop     | [2e0d41f272](https://linux-hardware.org/?probe=2e0d41f272) | Sep 10, 2022 |
| MSI           | B450M MORTAR                | Desktop     | [06ee689632](https://linux-hardware.org/?probe=06ee689632) | Sep 10, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [5cfe072b9c](https://linux-hardware.org/?probe=5cfe072b9c) | Sep 10, 2022 |
| ASRock        | Z390 Phantom Gaming 4S      | Desktop     | [146e7ebf49](https://linux-hardware.org/?probe=146e7ebf49) | Sep 08, 2022 |
| Gigabyte      | B660 GAMING X AX DDR4       | Desktop     | [3d12a72937](https://linux-hardware.org/?probe=3d12a72937) | Sep 06, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [cc1fde17e8](https://linux-hardware.org/?probe=cc1fde17e8) | Sep 06, 2022 |
| Dell          | Latitude D410               | Notebook    | [6782e0a28f](https://linux-hardware.org/?probe=6782e0a28f) | Sep 05, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [12fbd247f5](https://linux-hardware.org/?probe=12fbd247f5) | Sep 05, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [1d90e3b685](https://linux-hardware.org/?probe=1d90e3b685) | Sep 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [88392a79f5](https://linux-hardware.org/?probe=88392a79f5) | Sep 04, 2022 |
| win elemen... | MoreFine S500+              | Notebook    | [d02a951b89](https://linux-hardware.org/?probe=d02a951b89) | Sep 04, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [8320ded55c](https://linux-hardware.org/?probe=8320ded55c) | Sep 02, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [e16313490d](https://linux-hardware.org/?probe=e16313490d) | Sep 01, 2022 |
| Toshiba       | Satellite C850D-118         | Notebook    | [1950f0aeac](https://linux-hardware.org/?probe=1950f0aeac) | Aug 31, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [d146908413](https://linux-hardware.org/?probe=d146908413) | Aug 31, 2022 |
| Toshiba       | Satellite C850D-118         | Notebook    | [07000e4194](https://linux-hardware.org/?probe=07000e4194) | Aug 30, 2022 |
| Lenovo        | ThinkPad P50 20EQS33R0J     | Notebook    | [72f6962ac8](https://linux-hardware.org/?probe=72f6962ac8) | Aug 30, 2022 |
| ASRock        | X370 Gaming X               | Desktop     | [e915bb3a8c](https://linux-hardware.org/?probe=e915bb3a8c) | Aug 29, 2022 |
| win elemen... | MoreFine S500+              | Notebook    | [5a51c31ac9](https://linux-hardware.org/?probe=5a51c31ac9) | Aug 29, 2022 |
| Eluktronic... | MAX-17                      | Notebook    | [627ecbeb36](https://linux-hardware.org/?probe=627ecbeb36) | Aug 29, 2022 |
| Dell          | Precision 3570              | Notebook    | [7f7a44c923](https://linux-hardware.org/?probe=7f7a44c923) | Aug 29, 2022 |
| Timi          | A35                         | Notebook    | [df50ea1876](https://linux-hardware.org/?probe=df50ea1876) | Aug 29, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [499889da7e](https://linux-hardware.org/?probe=499889da7e) | Aug 28, 2022 |
| ASRock        | X370 Gaming X               | Desktop     | [489691c2e3](https://linux-hardware.org/?probe=489691c2e3) | Aug 28, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [f30320f76e](https://linux-hardware.org/?probe=f30320f76e) | Aug 27, 2022 |
| Lenovo        | 3716 SDK0R32862 WIN 3258... | Desktop     | [7e810b23be](https://linux-hardware.org/?probe=7e810b23be) | Aug 26, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [cf7da7df12](https://linux-hardware.org/?probe=cf7da7df12) | Aug 26, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [76db86107b](https://linux-hardware.org/?probe=76db86107b) | Aug 26, 2022 |
| Lenovo        | Yoga S940-14IWL 81Q7        | Notebook    | [416e5db831](https://linux-hardware.org/?probe=416e5db831) | Aug 26, 2022 |
| Lenovo        | ThinkPad Yoga 460 20EMCT... | Convertible | [73c79e8944](https://linux-hardware.org/?probe=73c79e8944) | Aug 25, 2022 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [294fe7d6c8](https://linux-hardware.org/?probe=294fe7d6c8) | Aug 24, 2022 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [2952e542e1](https://linux-hardware.org/?probe=2952e542e1) | Aug 24, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [0df091061c](https://linux-hardware.org/?probe=0df091061c) | Aug 24, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [d22f756c4c](https://linux-hardware.org/?probe=d22f756c4c) | Aug 24, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [0c80683e2a](https://linux-hardware.org/?probe=0c80683e2a) | Aug 23, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [f38202db0d](https://linux-hardware.org/?probe=f38202db0d) | Aug 21, 2022 |
| MSI           | Z590-A PRO                  | Desktop     | [8445aa0041](https://linux-hardware.org/?probe=8445aa0041) | Aug 20, 2022 |
| Timi          | A35                         | Notebook    | [cf89c68d08](https://linux-hardware.org/?probe=cf89c68d08) | Aug 19, 2022 |
| IBM           | 2722BDG                     | Notebook    | [e0fe2162a3](https://linux-hardware.org/?probe=e0fe2162a3) | Aug 18, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [1ea309e90c](https://linux-hardware.org/?probe=1ea309e90c) | Aug 17, 2022 |
| Gigabyte      | B450 GAMING X               | Desktop     | [80760b8e4b](https://linux-hardware.org/?probe=80760b8e4b) | Aug 16, 2022 |
| Dell          | G3 3500                     | Notebook    | [6a860d7c0f](https://linux-hardware.org/?probe=6a860d7c0f) | Aug 15, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [48637ddb10](https://linux-hardware.org/?probe=48637ddb10) | Aug 14, 2022 |
| Purism        | Librem 15 v4                | Notebook    | [4448709e50](https://linux-hardware.org/?probe=4448709e50) | Aug 13, 2022 |
| Purism        | Librem 15 v4                | Notebook    | [9e76f9e7ff](https://linux-hardware.org/?probe=9e76f9e7ff) | Aug 13, 2022 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [ee6f495403](https://linux-hardware.org/?probe=ee6f495403) | Aug 13, 2022 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [289850f128](https://linux-hardware.org/?probe=289850f128) | Aug 13, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [8d95c82a1d](https://linux-hardware.org/?probe=8d95c82a1d) | Aug 12, 2022 |
| Timi          | A35                         | Notebook    | [944f3f0942](https://linux-hardware.org/?probe=944f3f0942) | Aug 12, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [166edbd7db](https://linux-hardware.org/?probe=166edbd7db) | Aug 12, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [7d7ceef044](https://linux-hardware.org/?probe=7d7ceef044) | Aug 12, 2022 |
| Acer          | Swift SF314-512             | Notebook    | [c374f64c25](https://linux-hardware.org/?probe=c374f64c25) | Aug 11, 2022 |
| Notebook      | N141CU                      | Notebook    | [4d96f7358c](https://linux-hardware.org/?probe=4d96f7358c) | Aug 10, 2022 |
| Acer          | Swift SF314-512             | Notebook    | [0c23760c27](https://linux-hardware.org/?probe=0c23760c27) | Aug 10, 2022 |
| Unknown       | QNAP TS-221                 | Desktop     | [8d3f7ca9cf](https://linux-hardware.org/?probe=8d3f7ca9cf) | Aug 10, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [2781a13b80](https://linux-hardware.org/?probe=2781a13b80) | Aug 10, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [9b228ae787](https://linux-hardware.org/?probe=9b228ae787) | Aug 10, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [9f2e51f185](https://linux-hardware.org/?probe=9f2e51f185) | Aug 10, 2022 |
| ASRock        | P67 Extreme4 Gen3           | Desktop     | [b94e1be5ab](https://linux-hardware.org/?probe=b94e1be5ab) | Aug 09, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [0e7d0b5d33](https://linux-hardware.org/?probe=0e7d0b5d33) | Aug 09, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [1f10876798](https://linux-hardware.org/?probe=1f10876798) | Aug 08, 2022 |
| Microsoft     | Surface Go 3                | Tablet      | [f97852a196](https://linux-hardware.org/?probe=f97852a196) | Aug 08, 2022 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | Notebook    | [78f846e0e5](https://linux-hardware.org/?probe=78f846e0e5) | Aug 08, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [ac538e23dc](https://linux-hardware.org/?probe=ac538e23dc) | Aug 07, 2022 |
| Microsoft     | Surface Go 3                | Tablet      | [ca880d8154](https://linux-hardware.org/?probe=ca880d8154) | Aug 06, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [3e7a65077d](https://linux-hardware.org/?probe=3e7a65077d) | Aug 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [2ff6a7fe85](https://linux-hardware.org/?probe=2ff6a7fe85) | Aug 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [d54acf14ff](https://linux-hardware.org/?probe=d54acf14ff) | Aug 06, 2022 |
| Toshiba       | NB100                       | Notebook    | [b91ee9b36b](https://linux-hardware.org/?probe=b91ee9b36b) | Aug 05, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [019849a487](https://linux-hardware.org/?probe=019849a487) | Aug 04, 2022 |
| Gigabyte      | B450 GAMING X               | Desktop     | [b875ef6dbf](https://linux-hardware.org/?probe=b875ef6dbf) | Aug 04, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [4caa777a81](https://linux-hardware.org/?probe=4caa777a81) | Aug 04, 2022 |
| Pine Micro... | Pine64 PinePhonePro         | Phone       | [f14436327b](https://linux-hardware.org/?probe=f14436327b) | Aug 04, 2022 |
| Samsung       | 700G7C                      | Notebook    | [cd554f5d17](https://linux-hardware.org/?probe=cd554f5d17) | Aug 03, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [3db1e1ee37](https://linux-hardware.org/?probe=3db1e1ee37) | Aug 03, 2022 |
| Fujitsu       | LIFEBOOK U758               | Notebook    | [fa1566785a](https://linux-hardware.org/?probe=fa1566785a) | Aug 03, 2022 |
| Pine Micro... | Pine64 PinePhonePro         | Phone       | [2cea7378e8](https://linux-hardware.org/?probe=2cea7378e8) | Aug 03, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [69188053f5](https://linux-hardware.org/?probe=69188053f5) | Aug 02, 2022 |
| ASRock        | B75M-GL R2.0                | Desktop     | [eed9f05678](https://linux-hardware.org/?probe=eed9f05678) | Aug 01, 2022 |
| Fanless Mi... | PCG02 GLE                   | Stick pc    | [19d2273e6b](https://linux-hardware.org/?probe=19d2273e6b) | Aug 01, 2022 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | Desktop     | [effa59ed64](https://linux-hardware.org/?probe=effa59ed64) | Aug 01, 2022 |
| ASRock        | B550M Steel Legend          | Desktop     | [0ac4f27d0f](https://linux-hardware.org/?probe=0ac4f27d0f) | Jul 31, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f22250f00c](https://linux-hardware.org/?probe=f22250f00c) | Jul 31, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [de9a854095](https://linux-hardware.org/?probe=de9a854095) | Jul 31, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [1051593809](https://linux-hardware.org/?probe=1051593809) | Jul 31, 2022 |
| Gigabyte      | 970A-DS3                    | Desktop     | [78f00bd2aa](https://linux-hardware.org/?probe=78f00bd2aa) | Jul 30, 2022 |
| Razer         | Blade 15 Studio Edition ... | Notebook    | [359f708604](https://linux-hardware.org/?probe=359f708604) | Jul 30, 2022 |
| Lenovo        | 1046 SDK0T08861 WIN 3305... | Desktop     | [d3d824f468](https://linux-hardware.org/?probe=d3d824f468) | Jul 29, 2022 |
| MSI           | B450M MORTAR                | Desktop     | [29a26324b9](https://linux-hardware.org/?probe=29a26324b9) | Jul 29, 2022 |
| ASUSTek       | ROG G703GI_G7BI             | Notebook    | [88a326be83](https://linux-hardware.org/?probe=88a326be83) | Jul 28, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [e7f56631b1](https://linux-hardware.org/?probe=e7f56631b1) | Jul 27, 2022 |
| Supermicro    | X10SRL-FB                   | Server      | [a8dc9cfc07](https://linux-hardware.org/?probe=a8dc9cfc07) | Jul 27, 2022 |
| Intel         | D54250WYK H13922-303        | Desktop     | [5ff32931fa](https://linux-hardware.org/?probe=5ff32931fa) | Jul 27, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [dc7eff27cf](https://linux-hardware.org/?probe=dc7eff27cf) | Jul 26, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [f3972b3a7d](https://linux-hardware.org/?probe=f3972b3a7d) | Jul 26, 2022 |
| Timi          | Mi Laptop Pro 15 2020       | Notebook    | [5455e664e0](https://linux-hardware.org/?probe=5455e664e0) | Jul 26, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [b15fb90c18](https://linux-hardware.org/?probe=b15fb90c18) | Jul 26, 2022 |
| ASRock        | X399 Taichi                 | Desktop     | [d2eb8a032b](https://linux-hardware.org/?probe=d2eb8a032b) | Jul 26, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [c98fed5f84](https://linux-hardware.org/?probe=c98fed5f84) | Jul 25, 2022 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | Desktop     | [dae325b47b](https://linux-hardware.org/?probe=dae325b47b) | Jul 25, 2022 |
| Dell          | 0FKD45 A03                  | Server      | [0caba2e4b0](https://linux-hardware.org/?probe=0caba2e4b0) | Jul 25, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [8f46b7dcca](https://linux-hardware.org/?probe=8f46b7dcca) | Jul 25, 2022 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [64dad58b71](https://linux-hardware.org/?probe=64dad58b71) | Jul 25, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [6302f1ee8b](https://linux-hardware.org/?probe=6302f1ee8b) | Jul 25, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [e1e16aa154](https://linux-hardware.org/?probe=e1e16aa154) | Jul 25, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [153acd77c2](https://linux-hardware.org/?probe=153acd77c2) | Jul 24, 2022 |
| ASRock        | AM1H-ITX                    | Desktop     | [a15c82ba0c](https://linux-hardware.org/?probe=a15c82ba0c) | Jul 24, 2022 |
| TYAN Compu... | S7025                       | Server      | [844d96fcd7](https://linux-hardware.org/?probe=844d96fcd7) | Jul 22, 2022 |
| Unknown       | QNAP TS-221                 | Desktop     | [fb3741faab](https://linux-hardware.org/?probe=fb3741faab) | Jul 21, 2022 |
| ASRock        | X570 Taichi                 | Desktop     | [56d5853243](https://linux-hardware.org/?probe=56d5853243) | Jul 19, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [d3d26541f1](https://linux-hardware.org/?probe=d3d26541f1) | Jul 19, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [8f2f1582e8](https://linux-hardware.org/?probe=8f2f1582e8) | Jul 17, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [056d74f1a9](https://linux-hardware.org/?probe=056d74f1a9) | Jul 17, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [e6b6d3b5e6](https://linux-hardware.org/?probe=e6b6d3b5e6) | Jul 16, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [93f8a4ce9f](https://linux-hardware.org/?probe=93f8a4ce9f) | Jul 16, 2022 |
| Gigabyte      | Z590 UD                     | Desktop     | [e9e0b50bbb](https://linux-hardware.org/?probe=e9e0b50bbb) | Jul 15, 2022 |
| Dell          | Latitude 5289               | Convertible | [a0844cdadd](https://linux-hardware.org/?probe=a0844cdadd) | Jul 15, 2022 |
| ASUSTek       | ROG G703GI_G7BI             | Notebook    | [4d636c74d3](https://linux-hardware.org/?probe=4d636c74d3) | Jul 14, 2022 |
| MSI           | Z87-G45 GAMING              | Desktop     | [8602f7246a](https://linux-hardware.org/?probe=8602f7246a) | Jul 12, 2022 |
| Lenovo        | ThinkPad X13 Yoga Gen 2 ... | Convertible | [0d6de2415e](https://linux-hardware.org/?probe=0d6de2415e) | Jul 11, 2022 |
| MSI           | GS63VR 6RF                  | Notebook    | [30ad17796f](https://linux-hardware.org/?probe=30ad17796f) | Jul 11, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [94e9d2f65a](https://linux-hardware.org/?probe=94e9d2f65a) | Jul 10, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [f67a64f833](https://linux-hardware.org/?probe=f67a64f833) | Jul 10, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [6d15b85193](https://linux-hardware.org/?probe=6d15b85193) | Jul 10, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [8f36480ad7](https://linux-hardware.org/?probe=8f36480ad7) | Jul 10, 2022 |
| Dell          | 0J3C2F A02                  | Desktop     | [dccb88852f](https://linux-hardware.org/?probe=dccb88852f) | Jul 10, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [0237c9df10](https://linux-hardware.org/?probe=0237c9df10) | Jul 10, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [85dbd84c37](https://linux-hardware.org/?probe=85dbd84c37) | Jul 09, 2022 |
| Dell          | 0J3C2F A02                  | Desktop     | [aa87616696](https://linux-hardware.org/?probe=aa87616696) | Jul 09, 2022 |
| Dell          | Latitude D420               | Notebook    | [2e3ded5234](https://linux-hardware.org/?probe=2e3ded5234) | Jul 08, 2022 |
| MSI           | GS63VR 6RF                  | Notebook    | [097cc820d3](https://linux-hardware.org/?probe=097cc820d3) | Jul 08, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [5bdfb575ae](https://linux-hardware.org/?probe=5bdfb575ae) | Jul 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [850003c6da](https://linux-hardware.org/?probe=850003c6da) | Jul 05, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [1b94ade16a](https://linux-hardware.org/?probe=1b94ade16a) | Jul 05, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [685e3d36bc](https://linux-hardware.org/?probe=685e3d36bc) | Jul 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [b436712f17](https://linux-hardware.org/?probe=b436712f17) | Jul 04, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [d442c531e8](https://linux-hardware.org/?probe=d442c531e8) | Jul 03, 2022 |
| Gigabyte      | Z690 AORUS MASTER           | Desktop     | [cf8784ac23](https://linux-hardware.org/?probe=cf8784ac23) | Jul 03, 2022 |
| HP            | EliteBook 2560p             | Notebook    | [c1e5d91a40](https://linux-hardware.org/?probe=c1e5d91a40) | Jul 02, 2022 |
| Supermicro    | X10SRL-FB                   | Server      | [253c441703](https://linux-hardware.org/?probe=253c441703) | Jul 02, 2022 |
| Toshiba       | Satellite A200              | Notebook    | [d030e357db](https://linux-hardware.org/?probe=d030e357db) | Jul 02, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [1af80d1cdb](https://linux-hardware.org/?probe=1af80d1cdb) | Jul 01, 2022 |
| Timi          | RedmiBook 13                | Notebook    | [fb3b3f37d5](https://linux-hardware.org/?probe=fb3b3f37d5) | Jun 30, 2022 |
| Dell          | Latitude D420               | Notebook    | [c531c131ec](https://linux-hardware.org/?probe=c531c131ec) | Jun 28, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [4c0fa03f61](https://linux-hardware.org/?probe=4c0fa03f61) | Jun 28, 2022 |
| ASUSTek       | X555LJ                      | Notebook    | [0c6dd4c77c](https://linux-hardware.org/?probe=0c6dd4c77c) | Jun 27, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [79dca3a17c](https://linux-hardware.org/?probe=79dca3a17c) | Jun 26, 2022 |
| Fujitsu       | D3417-B2 S26361-D3417-B2    | Desktop     | [f03dcf744a](https://linux-hardware.org/?probe=f03dcf744a) | Jun 26, 2022 |
| Dell          | Precision 7550              | Notebook    | [4779d18806](https://linux-hardware.org/?probe=4779d18806) | Jun 24, 2022 |
| Gigabyte      | Z590 UD                     | Desktop     | [74060af6fc](https://linux-hardware.org/?probe=74060af6fc) | Jun 23, 2022 |
| Lenovo        | ThinkPad X13 Yoga Gen 2 ... | Convertible | [bab7d495b0](https://linux-hardware.org/?probe=bab7d495b0) | Jun 21, 2022 |
| AVITA         | NS14A6                      | Notebook    | [e3169acbbb](https://linux-hardware.org/?probe=e3169acbbb) | Jun 20, 2022 |
| Intel         | S5000XVN                    | Server      | [da50147a63](https://linux-hardware.org/?probe=da50147a63) | Jun 20, 2022 |
| Lenovo        | ThinkPad T460 20FMS421US    | Notebook    | [b290cf5fe0](https://linux-hardware.org/?probe=b290cf5fe0) | Jun 19, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [2028b239fc](https://linux-hardware.org/?probe=2028b239fc) | Jun 19, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [20c198dd50](https://linux-hardware.org/?probe=20c198dd50) | Jun 19, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [27fd147a80](https://linux-hardware.org/?probe=27fd147a80) | Jun 19, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [9d03e8cba7](https://linux-hardware.org/?probe=9d03e8cba7) | Jun 18, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [17b77e3069](https://linux-hardware.org/?probe=17b77e3069) | Jun 17, 2022 |
| Dell          | Inspiron 15 5510            | Notebook    | [286f8505c9](https://linux-hardware.org/?probe=286f8505c9) | Jun 17, 2022 |
| Dell          | G3 3500                     | Notebook    | [396a536231](https://linux-hardware.org/?probe=396a536231) | Jun 17, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [fe7fa5fe7a](https://linux-hardware.org/?probe=fe7fa5fe7a) | Jun 17, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [6fa09c2dd0](https://linux-hardware.org/?probe=6fa09c2dd0) | Jun 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [d3f9fd8f0c](https://linux-hardware.org/?probe=d3f9fd8f0c) | Jun 16, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [59350b295e](https://linux-hardware.org/?probe=59350b295e) | Jun 13, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [223b882103](https://linux-hardware.org/?probe=223b882103) | Jun 12, 2022 |
| Lenovo        | ThinkPad A485 20MUCTO1WW    | Notebook    | [283958f1a4](https://linux-hardware.org/?probe=283958f1a4) | Jun 12, 2022 |
| HP            | OMEN by Laptop              | Notebook    | [7b531e1607](https://linux-hardware.org/?probe=7b531e1607) | Jun 09, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [197f417cea](https://linux-hardware.org/?probe=197f417cea) | Jun 09, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [80a6dc4a46](https://linux-hardware.org/?probe=80a6dc4a46) | Jun 09, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [f237211ddb](https://linux-hardware.org/?probe=f237211ddb) | Jun 09, 2022 |
| Pegatron      | 2ACE                        | Desktop     | [838cad5bc2](https://linux-hardware.org/?probe=838cad5bc2) | Jun 06, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [5745c8b787](https://linux-hardware.org/?probe=5745c8b787) | Jun 06, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [fd5c0c6f83](https://linux-hardware.org/?probe=fd5c0c6f83) | Jun 06, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [cb81a60917](https://linux-hardware.org/?probe=cb81a60917) | Jun 05, 2022 |
| Dell          | G3 3500                     | Notebook    | [edbd452524](https://linux-hardware.org/?probe=edbd452524) | Jun 05, 2022 |
| Unknown       | Unknown                     | Desktop     | [c6f9883076](https://linux-hardware.org/?probe=c6f9883076) | Jun 05, 2022 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [f2ca17eb5d](https://linux-hardware.org/?probe=f2ca17eb5d) | Jun 05, 2022 |
| Unknown       | Unknown                     | Desktop     | [4abb49be35](https://linux-hardware.org/?probe=4abb49be35) | Jun 04, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [0c1909c43b](https://linux-hardware.org/?probe=0c1909c43b) | Jun 03, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [102ed915c5](https://linux-hardware.org/?probe=102ed915c5) | Jun 02, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [d17975e27b](https://linux-hardware.org/?probe=d17975e27b) | Jun 02, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [0a458659f6](https://linux-hardware.org/?probe=0a458659f6) | Jun 01, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [09fcdacb15](https://linux-hardware.org/?probe=09fcdacb15) | Jun 01, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [d33b756434](https://linux-hardware.org/?probe=d33b756434) | Jun 01, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [2c33cbbbe2](https://linux-hardware.org/?probe=2c33cbbbe2) | May 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [6e43e1d4f1](https://linux-hardware.org/?probe=6e43e1d4f1) | May 30, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [bd36f27f9b](https://linux-hardware.org/?probe=bd36f27f9b) | May 29, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [77989d3d20](https://linux-hardware.org/?probe=77989d3d20) | May 28, 2022 |
| Dell          | Inspiron 15 5510            | Notebook    | [641c79318b](https://linux-hardware.org/?probe=641c79318b) | May 27, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [86021dcc38](https://linux-hardware.org/?probe=86021dcc38) | May 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e879d3c292](https://linux-hardware.org/?probe=e879d3c292) | May 27, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | Notebook    | [ecebcc6033](https://linux-hardware.org/?probe=ecebcc6033) | May 26, 2022 |
| ASUSTek       | 1005HA                      | Notebook    | [0948f30719](https://linux-hardware.org/?probe=0948f30719) | May 26, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [b8603fccc0](https://linux-hardware.org/?probe=b8603fccc0) | May 26, 2022 |
| ASUSTek       | 1005HA                      | Notebook    | [1d5fe9025a](https://linux-hardware.org/?probe=1d5fe9025a) | May 25, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [38ac6de56d](https://linux-hardware.org/?probe=38ac6de56d) | May 25, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [af256d7649](https://linux-hardware.org/?probe=af256d7649) | May 24, 2022 |
| Intel         | D54250WYK H13922-303        | Desktop     | [59eda31291](https://linux-hardware.org/?probe=59eda31291) | May 24, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [b253c6e007](https://linux-hardware.org/?probe=b253c6e007) | May 24, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [add67dab1a](https://linux-hardware.org/?probe=add67dab1a) | May 24, 2022 |
| ASRockRack    | E3C232D2I                   | Desktop     | [0442460b97](https://linux-hardware.org/?probe=0442460b97) | May 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [4e370a75aa](https://linux-hardware.org/?probe=4e370a75aa) | May 23, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [e254f29ffd](https://linux-hardware.org/?probe=e254f29ffd) | May 23, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [93700a286d](https://linux-hardware.org/?probe=93700a286d) | May 23, 2022 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [6f78dba14b](https://linux-hardware.org/?probe=6f78dba14b) | May 23, 2022 |
| ASUSTek       | Rampage V EXTREME           | Desktop     | [ce350dd874](https://linux-hardware.org/?probe=ce350dd874) | May 23, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [f129f3b1d5](https://linux-hardware.org/?probe=f129f3b1d5) | May 22, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [32b5f99569](https://linux-hardware.org/?probe=32b5f99569) | May 22, 2022 |
| Acer          | Aspire E5-571G              | Notebook    | [8f47f3a71c](https://linux-hardware.org/?probe=8f47f3a71c) | May 22, 2022 |
| Supermicro    | H12SSL-NT                   | Server      | [6492614879](https://linux-hardware.org/?probe=6492614879) | May 21, 2022 |
| HP            | ProBook 430 G7              | Notebook    | [04a6359630](https://linux-hardware.org/?probe=04a6359630) | May 21, 2022 |
| Lenovo        | ThinkPad T460 20FMS421US    | Notebook    | [47297bafb5](https://linux-hardware.org/?probe=47297bafb5) | May 21, 2022 |
| Lenovo        | ThinkPad T460 20FMS421US    | Notebook    | [7b878500c1](https://linux-hardware.org/?probe=7b878500c1) | May 21, 2022 |
| MSI           | MS-7A34                     | Notebook    | [8956078328](https://linux-hardware.org/?probe=8956078328) | May 21, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | Notebook    | [bdc04b3c5d](https://linux-hardware.org/?probe=bdc04b3c5d) | May 19, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [f7225b80ed](https://linux-hardware.org/?probe=f7225b80ed) | May 18, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [84a0dc5b83](https://linux-hardware.org/?probe=84a0dc5b83) | May 18, 2022 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | Notebook    | [a49d97c9e6](https://linux-hardware.org/?probe=a49d97c9e6) | May 17, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [1dbb37fcd0](https://linux-hardware.org/?probe=1dbb37fcd0) | May 17, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [d5477b3bb9](https://linux-hardware.org/?probe=d5477b3bb9) | May 17, 2022 |
| ASUSTek       | PRIME Z690M-PLUS D4         | Desktop     | [818ee286b7](https://linux-hardware.org/?probe=818ee286b7) | May 17, 2022 |
| Dell          | Vostro 5568                 | Notebook    | [c7075dab69](https://linux-hardware.org/?probe=c7075dab69) | May 16, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [0de514cd0b](https://linux-hardware.org/?probe=0de514cd0b) | May 16, 2022 |
| ASUSTek       | ROG Maximus XIII APEX       | Desktop     | [56fb967887](https://linux-hardware.org/?probe=56fb967887) | May 16, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [f64f274146](https://linux-hardware.org/?probe=f64f274146) | May 16, 2022 |
| MSI           | GE66 Raider 11UE            | Notebook    | [d1a9527039](https://linux-hardware.org/?probe=d1a9527039) | May 16, 2022 |
| MSI           | GE66 Raider 11UE            | Notebook    | [d675d89c8a](https://linux-hardware.org/?probe=d675d89c8a) | May 16, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [9afc74ed46](https://linux-hardware.org/?probe=9afc74ed46) | May 16, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [28b47bc364](https://linux-hardware.org/?probe=28b47bc364) | May 15, 2022 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [49a3292018](https://linux-hardware.org/?probe=49a3292018) | May 15, 2022 |
| HP            | ZBook 15 G3                 | Notebook    | [020e862674](https://linux-hardware.org/?probe=020e862674) | May 15, 2022 |
| HP            | Pavilion ZV6100 (EE984EA... | Notebook    | [59c5dbcb22](https://linux-hardware.org/?probe=59c5dbcb22) | May 15, 2022 |
| ASUSTek       | Z8NR-D12                    | Desktop     | [e65adcd0da](https://linux-hardware.org/?probe=e65adcd0da) | May 14, 2022 |
| Dell          | 0J3C2F A02                  | Desktop     | [07e2cea31c](https://linux-hardware.org/?probe=07e2cea31c) | May 13, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [cf73bc12e8](https://linux-hardware.org/?probe=cf73bc12e8) | May 13, 2022 |
| Lenovo        | ThinkPad P73 20QSS09S00     | Notebook    | [8438c92818](https://linux-hardware.org/?probe=8438c92818) | May 12, 2022 |
| ASUSTek       | PRIME H370-PLUS             | Desktop     | [df570dd8e0](https://linux-hardware.org/?probe=df570dd8e0) | May 12, 2022 |
| Fanless Mi... | PCG02 GLE                   | Stick pc    | [8328bbecb9](https://linux-hardware.org/?probe=8328bbecb9) | May 12, 2022 |
| Gigabyte      | Z590 UD                     | Desktop     | [2fcf37c00a](https://linux-hardware.org/?probe=2fcf37c00a) | May 11, 2022 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [474578814d](https://linux-hardware.org/?probe=474578814d) | May 10, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [5ccbf39183](https://linux-hardware.org/?probe=5ccbf39183) | May 10, 2022 |
| HP            | 8704                        | Desktop     | [b66f290b02](https://linux-hardware.org/?probe=b66f290b02) | May 09, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [0f04e6b439](https://linux-hardware.org/?probe=0f04e6b439) | May 09, 2022 |
| Dell          | 0J3C2F A02                  | Desktop     | [bd6c3ca5b4](https://linux-hardware.org/?probe=bd6c3ca5b4) | May 09, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [81aa293c77](https://linux-hardware.org/?probe=81aa293c77) | May 08, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [ee92f88374](https://linux-hardware.org/?probe=ee92f88374) | May 07, 2022 |
| Dell          | Inspiron 1525               | Notebook    | [67dbf0ac88](https://linux-hardware.org/?probe=67dbf0ac88) | May 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [8919eebaa3](https://linux-hardware.org/?probe=8919eebaa3) | May 05, 2022 |
| ASRock        | A320M Pro4                  | Desktop     | [b51c7ae18b](https://linux-hardware.org/?probe=b51c7ae18b) | May 04, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [48fa5d3b93](https://linux-hardware.org/?probe=48fa5d3b93) | May 04, 2022 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [01369642f4](https://linux-hardware.org/?probe=01369642f4) | May 03, 2022 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [83ca73d4cd](https://linux-hardware.org/?probe=83ca73d4cd) | May 03, 2022 |
| Acer          | Aspire E5-571G              | Notebook    | [8df6782398](https://linux-hardware.org/?probe=8df6782398) | May 02, 2022 |
| Dell          | Precision 3520              | Notebook    | [caae9a5055](https://linux-hardware.org/?probe=caae9a5055) | May 02, 2022 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [fcca76f1e5](https://linux-hardware.org/?probe=fcca76f1e5) | May 01, 2022 |
| ASRock        | X370 Gaming X               | Desktop     | [b24677a908](https://linux-hardware.org/?probe=b24677a908) | May 01, 2022 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | Notebook    | [55402e38ae](https://linux-hardware.org/?probe=55402e38ae) | May 01, 2022 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | Notebook    | [df7b5507c1](https://linux-hardware.org/?probe=df7b5507c1) | Apr 30, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [07a115654d](https://linux-hardware.org/?probe=07a115654d) | Apr 30, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [970d30df6d](https://linux-hardware.org/?probe=970d30df6d) | Apr 29, 2022 |
| HP            | ZBook 15 G3                 | Notebook    | [94d74e9b78](https://linux-hardware.org/?probe=94d74e9b78) | Apr 29, 2022 |
| ASRock        | A520M Pro4                  | Desktop     | [45630a42df](https://linux-hardware.org/?probe=45630a42df) | Apr 29, 2022 |
| Dell          | 0J37VM A00                  | Desktop     | [76f13aa200](https://linux-hardware.org/?probe=76f13aa200) | Apr 28, 2022 |
| Dell          | G3 3500                     | Notebook    | [e3f0210b87](https://linux-hardware.org/?probe=e3f0210b87) | Apr 24, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [a934bef382](https://linux-hardware.org/?probe=a934bef382) | Apr 24, 2022 |
| Lenovo        | ThinkPad X390 Yoga 20NN0... | Convertible | [3c1ff82bb0](https://linux-hardware.org/?probe=3c1ff82bb0) | Apr 24, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [b61b2af9eb](https://linux-hardware.org/?probe=b61b2af9eb) | Apr 23, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [82b11931ed](https://linux-hardware.org/?probe=82b11931ed) | Apr 21, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [6af0b2a3c9](https://linux-hardware.org/?probe=6af0b2a3c9) | Apr 21, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | Notebook    | [8273c9ecb4](https://linux-hardware.org/?probe=8273c9ecb4) | Apr 20, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [4121c8fcc2](https://linux-hardware.org/?probe=4121c8fcc2) | Apr 20, 2022 |
| Lenovo        | ThinkPad X220 4291QT1       | Notebook    | [9ffcb6bf7a](https://linux-hardware.org/?probe=9ffcb6bf7a) | Apr 18, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [fb3e0b6b22](https://linux-hardware.org/?probe=fb3e0b6b22) | Apr 18, 2022 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | Desktop     | [fa96d5405d](https://linux-hardware.org/?probe=fa96d5405d) | Apr 17, 2022 |
| ASRockRack    | X470D4U                     | Desktop     | [1b9b990e65](https://linux-hardware.org/?probe=1b9b990e65) | Apr 17, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [217905d42a](https://linux-hardware.org/?probe=217905d42a) | Apr 17, 2022 |
| Lenovo        | ThinkPad X220 4291QT1       | Notebook    | [00a23bc10c](https://linux-hardware.org/?probe=00a23bc10c) | Apr 17, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [47fc027d41](https://linux-hardware.org/?probe=47fc027d41) | Apr 17, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [9eac0ebbce](https://linux-hardware.org/?probe=9eac0ebbce) | Apr 17, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [46dd37cb4b](https://linux-hardware.org/?probe=46dd37cb4b) | Apr 16, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [2a3f36f9c0](https://linux-hardware.org/?probe=2a3f36f9c0) | Apr 16, 2022 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | Desktop     | [474bb81b18](https://linux-hardware.org/?probe=474bb81b18) | Apr 15, 2022 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | Desktop     | [f6a1a50a75](https://linux-hardware.org/?probe=f6a1a50a75) | Apr 15, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [d14605acc1](https://linux-hardware.org/?probe=d14605acc1) | Apr 15, 2022 |
| ASUSTek       | Z97-K/USB                   | Desktop     | [16aaadda77](https://linux-hardware.org/?probe=16aaadda77) | Apr 14, 2022 |
| Gigabyte      | B460 HD3                    | Desktop     | [c3c9ea3a20](https://linux-hardware.org/?probe=c3c9ea3a20) | Apr 14, 2022 |
| ASRock        | A320M-ITX                   | Desktop     | [eaf6bbd74e](https://linux-hardware.org/?probe=eaf6bbd74e) | Apr 13, 2022 |
| Acer          | Aspire VX5-591G             | Notebook    | [8d091affca](https://linux-hardware.org/?probe=8d091affca) | Apr 13, 2022 |
| ASUSTek       | PRIME H570M-PLUS            | Desktop     | [5e6ce90c93](https://linux-hardware.org/?probe=5e6ce90c93) | Apr 13, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [cfd276f151](https://linux-hardware.org/?probe=cfd276f151) | Apr 13, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [5620bf468d](https://linux-hardware.org/?probe=5620bf468d) | Apr 13, 2022 |
| Dell          | 084YMW A05                  | Server      | [f08f5999ac](https://linux-hardware.org/?probe=f08f5999ac) | Apr 13, 2022 |
| Dell          | G5 5505                     | Notebook    | [ce1fc33387](https://linux-hardware.org/?probe=ce1fc33387) | Apr 13, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [dccdc2c9f5](https://linux-hardware.org/?probe=dccdc2c9f5) | Apr 12, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [68dd0c90a1](https://linux-hardware.org/?probe=68dd0c90a1) | Apr 12, 2022 |
| MSI           | GE66 Raider 11UE            | Notebook    | [45472dad72](https://linux-hardware.org/?probe=45472dad72) | Apr 12, 2022 |
| HP            | ProBook 6570b               | Notebook    | [63d922ecdd](https://linux-hardware.org/?probe=63d922ecdd) | Apr 12, 2022 |
| ASUSTek       | ROG Maximus XIII APEX       | Desktop     | [7a26d3fc81](https://linux-hardware.org/?probe=7a26d3fc81) | Apr 12, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [2202a95625](https://linux-hardware.org/?probe=2202a95625) | Apr 12, 2022 |
| HP            | ProBook 6570b               | Notebook    | [87414e70aa](https://linux-hardware.org/?probe=87414e70aa) | Apr 11, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [51c96e48de](https://linux-hardware.org/?probe=51c96e48de) | Apr 10, 2022 |
| Dell          | Precision 7560              | Notebook    | [f8641cc115](https://linux-hardware.org/?probe=f8641cc115) | Apr 10, 2022 |
| Apple         | MacBookAir3,1               | Notebook    | [212412e4d5](https://linux-hardware.org/?probe=212412e4d5) | Apr 09, 2022 |
| ASRock        | Z390 Extreme4               | Desktop     | [1bd70fbd59](https://linux-hardware.org/?probe=1bd70fbd59) | Apr 09, 2022 |
| Gigabyte      | H470 HD3                    | Desktop     | [5ce5c54ecd](https://linux-hardware.org/?probe=5ce5c54ecd) | Apr 09, 2022 |
| ASRock        | Z390 Extreme4               | Desktop     | [ed2dd10e6e](https://linux-hardware.org/?probe=ed2dd10e6e) | Apr 09, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [18fb9eceac](https://linux-hardware.org/?probe=18fb9eceac) | Apr 09, 2022 |
| System76      | Gazelle                     | Notebook    | [9edcac1b2c](https://linux-hardware.org/?probe=9edcac1b2c) | Apr 09, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [b7b2d796d9](https://linux-hardware.org/?probe=b7b2d796d9) | Apr 08, 2022 |
| MSI           | MAG B550 TORPEDO            | Desktop     | [ce26da001a](https://linux-hardware.org/?probe=ce26da001a) | Apr 07, 2022 |
| System76      | Gazelle                     | Notebook    | [e22baecee4](https://linux-hardware.org/?probe=e22baecee4) | Apr 07, 2022 |
| ASUSTek       | P6X58D-E                    | Desktop     | [68be7a767a](https://linux-hardware.org/?probe=68be7a767a) | Apr 07, 2022 |
| MSI           | GE66 Raider 11UE            | Notebook    | [30cd3d5d00](https://linux-hardware.org/?probe=30cd3d5d00) | Apr 06, 2022 |
| ASUSTek       | ROG Maximus XIII APEX       | Desktop     | [8aad15d96c](https://linux-hardware.org/?probe=8aad15d96c) | Apr 06, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [d51c68f84e](https://linux-hardware.org/?probe=d51c68f84e) | Apr 05, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [3f086610fc](https://linux-hardware.org/?probe=3f086610fc) | Apr 05, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [403a6830d9](https://linux-hardware.org/?probe=403a6830d9) | Apr 04, 2022 |
| ASUSTek       | ROG Maximus XIII APEX       | Desktop     | [5bcff46ee9](https://linux-hardware.org/?probe=5bcff46ee9) | Apr 04, 2022 |
| Timi          | A35                         | Notebook    | [90a30461d2](https://linux-hardware.org/?probe=90a30461d2) | Apr 03, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [368a64422d](https://linux-hardware.org/?probe=368a64422d) | Apr 03, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [348ccc5750](https://linux-hardware.org/?probe=348ccc5750) | Apr 01, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [32eabd9ac8](https://linux-hardware.org/?probe=32eabd9ac8) | Apr 01, 2022 |
| ASUSTek       | ROG Strix G733ZX_G733ZX     | Notebook    | [04f5858a30](https://linux-hardware.org/?probe=04f5858a30) | Apr 01, 2022 |
| Razer         | Blade 15 (2022) - RZ09-0... | Notebook    | [b47301d663](https://linux-hardware.org/?probe=b47301d663) | Mar 31, 2022 |
| ASRock        | Z170A-X1                    | Desktop     | [9e1cc71d24](https://linux-hardware.org/?probe=9e1cc71d24) | Mar 31, 2022 |
| MSI           | GE66 Raider 11UE            | Notebook    | [11ca55cd73](https://linux-hardware.org/?probe=11ca55cd73) | Mar 31, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [9ebb4c0fd3](https://linux-hardware.org/?probe=9ebb4c0fd3) | Mar 31, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [5240890472](https://linux-hardware.org/?probe=5240890472) | Mar 29, 2022 |
| MSI           | GE66 Raider 11UE            | Notebook    | [27768b901a](https://linux-hardware.org/?probe=27768b901a) | Mar 28, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [6af3c57a8a](https://linux-hardware.org/?probe=6af3c57a8a) | Mar 24, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [801fa902d0](https://linux-hardware.org/?probe=801fa902d0) | Mar 24, 2022 |
| MSI           | GE66 Raider 11UE            | Notebook    | [69919648c7](https://linux-hardware.org/?probe=69919648c7) | Mar 24, 2022 |
| Gigabyte      | Z590 UD                     | Desktop     | [5cde1a4e83](https://linux-hardware.org/?probe=5cde1a4e83) | Mar 24, 2022 |
| Timi          | Mi Laptop Pro 15            | Notebook    | [33f98f8274](https://linux-hardware.org/?probe=33f98f8274) | Mar 23, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [4b3bd32143](https://linux-hardware.org/?probe=4b3bd32143) | Mar 23, 2022 |
| HP            | Pavilion ZV6100 (EE984EA... | Notebook    | [282dfe7eb0](https://linux-hardware.org/?probe=282dfe7eb0) | Mar 23, 2022 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [6dddf500c7](https://linux-hardware.org/?probe=6dddf500c7) | Mar 22, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [e39c413976](https://linux-hardware.org/?probe=e39c413976) | Mar 21, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [593bf6f937](https://linux-hardware.org/?probe=593bf6f937) | Mar 21, 2022 |
| Unknown       | Unknown                     | Soc         | [dad2f6c4ba](https://linux-hardware.org/?probe=dad2f6c4ba) | Mar 20, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [906f450dd5](https://linux-hardware.org/?probe=906f450dd5) | Mar 20, 2022 |
| BANGHO        | MAX G0101                   | Notebook    | [b40c195d54](https://linux-hardware.org/?probe=b40c195d54) | Mar 20, 2022 |
| Dell          | XPS 12-9Q33                 | Notebook    | [f4829632f8](https://linux-hardware.org/?probe=f4829632f8) | Mar 20, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [6efb7791bb](https://linux-hardware.org/?probe=6efb7791bb) | Mar 19, 2022 |
| ASUSTek       | PRIME X299-DELUXE II        | Desktop     | [a2b06f49d3](https://linux-hardware.org/?probe=a2b06f49d3) | Mar 18, 2022 |
| ASUSTek       | PRIME X299-DELUXE II        | Desktop     | [9e32abccd6](https://linux-hardware.org/?probe=9e32abccd6) | Mar 18, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [3be092b600](https://linux-hardware.org/?probe=3be092b600) | Mar 18, 2022 |
| MSI           | MS-7A34                     | Notebook    | [27f8a2eb1f](https://linux-hardware.org/?probe=27f8a2eb1f) | Mar 18, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [70021af77a](https://linux-hardware.org/?probe=70021af77a) | Mar 15, 2022 |
| MSI           | B560M PRO-VDH WIFI          | Desktop     | [c15007b668](https://linux-hardware.org/?probe=c15007b668) | Mar 15, 2022 |
| Fanless Mi... | PCG02 GLE                   | Stick pc    | [adad5f6ce0](https://linux-hardware.org/?probe=adad5f6ce0) | Mar 15, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [7c09492e3b](https://linux-hardware.org/?probe=7c09492e3b) | Mar 14, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [f7e85dbf71](https://linux-hardware.org/?probe=f7e85dbf71) | Mar 14, 2022 |
| ASUSTek       | PRIME J4005I-C              | Desktop     | [707cb5ce3b](https://linux-hardware.org/?probe=707cb5ce3b) | Mar 14, 2022 |
| Intel         | DH61WW AAG23116-302         | Desktop     | [20682db2fa](https://linux-hardware.org/?probe=20682db2fa) | Mar 14, 2022 |
| Alienware     | 0TYR0X A00                  | Desktop     | [b82ab5d2d7](https://linux-hardware.org/?probe=b82ab5d2d7) | Mar 14, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [9bd0fc9e48](https://linux-hardware.org/?probe=9bd0fc9e48) | Mar 14, 2022 |
| Fanless Mi... | PCG02 GLE                   | Stick pc    | [6b45f989ae](https://linux-hardware.org/?probe=6b45f989ae) | Mar 13, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [624daf4b10](https://linux-hardware.org/?probe=624daf4b10) | Mar 12, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [3f58a0f2a4](https://linux-hardware.org/?probe=3f58a0f2a4) | Mar 11, 2022 |
| Framework     | Laptop                      | Notebook    | [8902c057fb](https://linux-hardware.org/?probe=8902c057fb) | Mar 10, 2022 |
| Dell          | 0J37VM A00                  | Desktop     | [a78d4c99e3](https://linux-hardware.org/?probe=a78d4c99e3) | Mar 09, 2022 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [7eea4038f0](https://linux-hardware.org/?probe=7eea4038f0) | Mar 09, 2022 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [fe3e35f15b](https://linux-hardware.org/?probe=fe3e35f15b) | Mar 09, 2022 |
| Framework     | Laptop                      | Notebook    | [e17db20b1c](https://linux-hardware.org/?probe=e17db20b1c) | Mar 08, 2022 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [b3ba67d085](https://linux-hardware.org/?probe=b3ba67d085) | Mar 08, 2022 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [d6d94816fc](https://linux-hardware.org/?probe=d6d94816fc) | Mar 08, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [f50abf2114](https://linux-hardware.org/?probe=f50abf2114) | Mar 08, 2022 |
| Timi          | RedmiBook Air 13            | Notebook    | [cb1fd6a511](https://linux-hardware.org/?probe=cb1fd6a511) | Mar 08, 2022 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [bc052daf77](https://linux-hardware.org/?probe=bc052daf77) | Mar 07, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [f89153c3e1](https://linux-hardware.org/?probe=f89153c3e1) | Mar 05, 2022 |
| Toshiba       | Satellite L50-C             | Notebook    | [0e6289a2ad](https://linux-hardware.org/?probe=0e6289a2ad) | Mar 04, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [f1b0d6e847](https://linux-hardware.org/?probe=f1b0d6e847) | Mar 03, 2022 |
| ASRock        | A300M-STX                   | Desktop     | [d9c28765e7](https://linux-hardware.org/?probe=d9c28765e7) | Mar 03, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [44656b1bd4](https://linux-hardware.org/?probe=44656b1bd4) | Mar 03, 2022 |
| Intel         | NUC11PABi7 K90104-305       | Mini pc     | [ca53435b36](https://linux-hardware.org/?probe=ca53435b36) | Mar 03, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [5c95114871](https://linux-hardware.org/?probe=5c95114871) | Mar 02, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [6931b9fe82](https://linux-hardware.org/?probe=6931b9fe82) | Mar 02, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [842379fc35](https://linux-hardware.org/?probe=842379fc35) | Mar 01, 2022 |
| Alienware     | 0TYR0X A00                  | Desktop     | [17eda5de26](https://linux-hardware.org/?probe=17eda5de26) | Feb 28, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [ee935ed8be](https://linux-hardware.org/?probe=ee935ed8be) | Feb 28, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [875e06d62c](https://linux-hardware.org/?probe=875e06d62c) | Feb 27, 2022 |
| Intel         | NUC11PABi7 K90104-305       | Mini pc     | [c97a79e04f](https://linux-hardware.org/?probe=c97a79e04f) | Feb 27, 2022 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | Notebook    | [a7fbe4b7c8](https://linux-hardware.org/?probe=a7fbe4b7c8) | Feb 27, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [6d4c3afa7f](https://linux-hardware.org/?probe=6d4c3afa7f) | Feb 27, 2022 |
| Gigabyte      | Z590 UD                     | Desktop     | [a5242ed058](https://linux-hardware.org/?probe=a5242ed058) | Feb 26, 2022 |
| Lenovo        | Yoga Slim 7 14IIL05 82A1    | Notebook    | [0022f4a8cc](https://linux-hardware.org/?probe=0022f4a8cc) | Feb 26, 2022 |
| Gigabyte      | Z590 UD                     | Desktop     | [071dd25266](https://linux-hardware.org/?probe=071dd25266) | Feb 24, 2022 |
| Alienware     | 0TYR0X A00                  | Desktop     | [892e886901](https://linux-hardware.org/?probe=892e886901) | Feb 23, 2022 |
| Alienware     | 0TYR0X A00                  | Desktop     | [71cac3ebdd](https://linux-hardware.org/?probe=71cac3ebdd) | Feb 22, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [cde7566ecb](https://linux-hardware.org/?probe=cde7566ecb) | Feb 22, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [302433b9e3](https://linux-hardware.org/?probe=302433b9e3) | Feb 21, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [6d5688db26](https://linux-hardware.org/?probe=6d5688db26) | Feb 21, 2022 |
| ASUSTek       | UX430UAR                    | Notebook    | [c7cd5ce50d](https://linux-hardware.org/?probe=c7cd5ce50d) | Feb 21, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [160ecaffd8](https://linux-hardware.org/?probe=160ecaffd8) | Feb 21, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [5dea4207b1](https://linux-hardware.org/?probe=5dea4207b1) | Feb 20, 2022 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [1998552d88](https://linux-hardware.org/?probe=1998552d88) | Feb 20, 2022 |
| MSI           | H81I                        | Desktop     | [c556e9c713](https://linux-hardware.org/?probe=c556e9c713) | Feb 20, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [1429fd9ed5](https://linux-hardware.org/?probe=1429fd9ed5) | Feb 20, 2022 |
| Lenovo        | Legion R9000P2021H 82JQ     | Notebook    | [5c3eba73d5](https://linux-hardware.org/?probe=5c3eba73d5) | Feb 20, 2022 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [8b0dc90a9e](https://linux-hardware.org/?probe=8b0dc90a9e) | Feb 19, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [859adc5b97](https://linux-hardware.org/?probe=859adc5b97) | Feb 19, 2022 |
| Lenovo        | Legion Y530-15ICH-1060 8... | Notebook    | [9df089b1ef](https://linux-hardware.org/?probe=9df089b1ef) | Feb 19, 2022 |
| ASUSTek       | ROG Maximus XIII APEX       | Desktop     | [eddf69336b](https://linux-hardware.org/?probe=eddf69336b) | Feb 18, 2022 |
| Gigabyte      | B460 HD3                    | Desktop     | [661166a163](https://linux-hardware.org/?probe=661166a163) | Feb 17, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [6278830433](https://linux-hardware.org/?probe=6278830433) | Feb 17, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [018fa00447](https://linux-hardware.org/?probe=018fa00447) | Feb 17, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [7737b54f68](https://linux-hardware.org/?probe=7737b54f68) | Feb 16, 2022 |
| HP            | ProBook 450 G6              | Notebook    | [e54664c1be](https://linux-hardware.org/?probe=e54664c1be) | Feb 15, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [92456282bc](https://linux-hardware.org/?probe=92456282bc) | Feb 14, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [c1227bf037](https://linux-hardware.org/?probe=c1227bf037) | Feb 14, 2022 |
| YANYU         | H17SL                       | Desktop     | [0a6638d9c9](https://linux-hardware.org/?probe=0a6638d9c9) | Feb 14, 2022 |
| Dell          | Inspiron 5515               | Notebook    | [27dad40db4](https://linux-hardware.org/?probe=27dad40db4) | Feb 13, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [8286f26e6e](https://linux-hardware.org/?probe=8286f26e6e) | Feb 12, 2022 |
| Supermicro    | X10SDV-2C-TP4F              | Server      | [e60ec405af](https://linux-hardware.org/?probe=e60ec405af) | Feb 12, 2022 |
| Dell          | Vostro 5490                 | Notebook    | [a8d3ef29f1](https://linux-hardware.org/?probe=a8d3ef29f1) | Feb 11, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [5836ccecc2](https://linux-hardware.org/?probe=5836ccecc2) | Feb 10, 2022 |
| Supermicro    | X10SDV-2C-TP4F              | Server      | [e761a368c3](https://linux-hardware.org/?probe=e761a368c3) | Feb 10, 2022 |
| MSI           | GS63VR 6RF                  | Notebook    | [c20c87027e](https://linux-hardware.org/?probe=c20c87027e) | Feb 10, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [9f05ddfb03](https://linux-hardware.org/?probe=9f05ddfb03) | Feb 08, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [49cf4eba76](https://linux-hardware.org/?probe=49cf4eba76) | Feb 08, 2022 |
| Lenovo        | ThinkPad X13 Yoga Gen 2 ... | Convertible | [661baafcd7](https://linux-hardware.org/?probe=661baafcd7) | Feb 07, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [68c1afd184](https://linux-hardware.org/?probe=68c1afd184) | Feb 06, 2022 |
| YANYU         | H17SL                       | Desktop     | [cd763ca612](https://linux-hardware.org/?probe=cd763ca612) | Feb 06, 2022 |
| ASUSTek       | 900                         | Notebook    | [88ce413793](https://linux-hardware.org/?probe=88ce413793) | Feb 06, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [8f79e4d763](https://linux-hardware.org/?probe=8f79e4d763) | Feb 06, 2022 |
| Supermicro    | A1SRM-2758F                 | Desktop     | [33b8806332](https://linux-hardware.org/?probe=33b8806332) | Feb 05, 2022 |
| Lenovo        | Legion Y7000 2019 PG0 81... | Notebook    | [f79196e39c](https://linux-hardware.org/?probe=f79196e39c) | Feb 05, 2022 |
| ASUSTek       | ROG Maximus XIII APEX       | Desktop     | [59d4e2a5b2](https://linux-hardware.org/?probe=59d4e2a5b2) | Feb 04, 2022 |
| Gigabyte      | Z490 UD                     | Desktop     | [b571c22d4f](https://linux-hardware.org/?probe=b571c22d4f) | Feb 04, 2022 |
| Neousys Te... | NVS-8208 Rev. A1            | Server      | [4a717f6348](https://linux-hardware.org/?probe=4a717f6348) | Feb 02, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [d424a8e145](https://linux-hardware.org/?probe=d424a8e145) | Feb 01, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [89dbe92caf](https://linux-hardware.org/?probe=89dbe92caf) | Feb 01, 2022 |
| Neousys Te... | NVS-8208 Rev. A1            | Server      | [7f7720253e](https://linux-hardware.org/?probe=7f7720253e) | Feb 01, 2022 |
| Samsung       | RC530/RC730                 | Notebook    | [c4651bdbc6](https://linux-hardware.org/?probe=c4651bdbc6) | Jan 31, 2022 |
| Lenovo        | ThinkPad T480s 20L8S02E0... | Notebook    | [e35fffc0dd](https://linux-hardware.org/?probe=e35fffc0dd) | Jan 30, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [2f36ebcc7e](https://linux-hardware.org/?probe=2f36ebcc7e) | Jan 30, 2022 |
| MSI           | GS63VR 6RF                  | Notebook    | [4873365af6](https://linux-hardware.org/?probe=4873365af6) | Jan 30, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [f49f9dddd2](https://linux-hardware.org/?probe=f49f9dddd2) | Jan 29, 2022 |
| Dell          | Precision 7520              | Notebook    | [4cdcfc0e31](https://linux-hardware.org/?probe=4cdcfc0e31) | Jan 29, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [cd1ab231e7](https://linux-hardware.org/?probe=cd1ab231e7) | Jan 28, 2022 |
| Lenovo        | ThinkPad T480s 20L8S02E0... | Notebook    | [999e47c570](https://linux-hardware.org/?probe=999e47c570) | Jan 28, 2022 |
| ASRock        | AB350M Pro4                 | Desktop     | [6b7cf2d570](https://linux-hardware.org/?probe=6b7cf2d570) | Jan 27, 2022 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [c021622ad4](https://linux-hardware.org/?probe=c021622ad4) | Jan 27, 2022 |
| ASRock        | A88M-G                      | Desktop     | [bb3847af5e](https://linux-hardware.org/?probe=bb3847af5e) | Jan 27, 2022 |
| ASRock        | A88M-G                      | Desktop     | [7f86f91b8f](https://linux-hardware.org/?probe=7f86f91b8f) | Jan 27, 2022 |
| Timi          | RedmiBook 13                | Notebook    | [e20538f56a](https://linux-hardware.org/?probe=e20538f56a) | Jan 26, 2022 |
| Lenovo        | Legion 5P 15IMH05 82AW      | Notebook    | [1abbb329fa](https://linux-hardware.org/?probe=1abbb329fa) | Jan 26, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [656da02110](https://linux-hardware.org/?probe=656da02110) | Jan 24, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [a4f6a4a38e](https://linux-hardware.org/?probe=a4f6a4a38e) | Jan 24, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [9e4f498056](https://linux-hardware.org/?probe=9e4f498056) | Jan 24, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [1721bed3e1](https://linux-hardware.org/?probe=1721bed3e1) | Jan 24, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [db8b77c1ff](https://linux-hardware.org/?probe=db8b77c1ff) | Jan 23, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [1ccb1fd970](https://linux-hardware.org/?probe=1ccb1fd970) | Jan 23, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [7e7edbe447](https://linux-hardware.org/?probe=7e7edbe447) | Jan 23, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [3c430f09c4](https://linux-hardware.org/?probe=3c430f09c4) | Jan 23, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [ab4793dc5e](https://linux-hardware.org/?probe=ab4793dc5e) | Jan 22, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [7a52dda8cc](https://linux-hardware.org/?probe=7a52dda8cc) | Jan 22, 2022 |
| Gigabyte      | Z490 UD                     | Desktop     | [eac4639ad2](https://linux-hardware.org/?probe=eac4639ad2) | Jan 22, 2022 |
| MSI           | GE73 Raider RGB 8RF         | Notebook    | [a5a825a072](https://linux-hardware.org/?probe=a5a825a072) | Jan 22, 2022 |
| Lenovo        | ThinkPad 20FMCT01WW         | Notebook    | [4bd81196a0](https://linux-hardware.org/?probe=4bd81196a0) | Jan 21, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [0799e18f8b](https://linux-hardware.org/?probe=0799e18f8b) | Jan 20, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Gentoo/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Gentoo 2.7     | 555       | 35.83%  |
| Gentoo 2.6     | 412       | 26.6%   |
| Gentoo 2.8     | 306       | 19.75%  |
| Gentoo 2.9     | 158       | 10.2%   |
| Gentoo 2.13    | 67        | 4.33%   |
| Gentoo 2.4.1   | 14        | 0.9%    |
| Gentoo         | 11        | 0.71%   |
| Gentoo 2.3     | 9         | 0.58%   |
| Gentoo 2.2     | 7         | 0.45%   |
| Gentoo 1       | 3         | 0.19%   |
| Gentoo 22.0.1  | 2         | 0.13%   |
| Gentoo Pelikan | 1         | 0.06%   |
| Gentoo 22      | 1         | 0.06%   |
| Gentoo 2022    | 1         | 0.06%   |
| Gentoo 2.1     | 1         | 0.06%   |
| Gentoo 13.0    | 1         | 0.06%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Gentoo | 1375      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.38-gentoo            | 26        | 1.44%   |
| 5.10.27-gentoo           | 25        | 1.39%   |
| 5.10.61-gentoo           | 23        | 1.28%   |
| 5.15.32-gentoo-r1        | 18        | 1%      |
| 6.1.12-gentoo            | 15        | 0.83%   |
| 5.4.80-gentoo-r1         | 15        | 0.83%   |
| 5.4.48-gentoo            | 15        | 0.83%   |
| 5.15.80-gentoo-x86_64    | 15        | 0.83%   |
| 5.15.80-gentoo           | 15        | 0.83%   |
| 5.4.97-gentoo            | 14        | 0.78%   |
| 5.4.28-gentoo            | 14        | 0.78%   |
| 5.10.76-gentoo-r1        | 14        | 0.78%   |
| 5.15.75-gentoo-x86_64    | 13        | 0.72%   |
| 5.10.61-gentoo-x86_64    | 13        | 0.72%   |
| 5.10.27-gentoo-x86_64    | 13        | 0.72%   |
| 5.15.59-gentoo-x86_64    | 12        | 0.67%   |
| 5.15.32-gentoo-r1-x86_64 | 12        | 0.67%   |
| 5.10.52-gentoo           | 12        | 0.67%   |
| 5.7.0-gentoo             | 11        | 0.61%   |
| 5.4.60-gentoo            | 11        | 0.61%   |
| 5.15.88-gentoo           | 11        | 0.61%   |
| 5.4.38-gentoo-x86_64     | 10        | 0.55%   |
| 5.15.75-gentoo           | 9         | 0.5%    |
| 5.15.59-gentoo           | 9         | 0.5%    |
| 5.15.52-gentoo-x86_64    | 9         | 0.5%    |
| 5.15.52-gentoo           | 9         | 0.5%    |
| 5.15.41-gentoo-x86_64    | 9         | 0.5%    |
| 5.10.76-gentoo-r1-x86_64 | 9         | 0.5%    |
| 5.6.15-gentoo            | 8         | 0.44%   |
| 5.4.66-gentoo            | 8         | 0.44%   |
| 5.4.48-gentoo-x86_64     | 8         | 0.44%   |
| 5.15.69-gentoo           | 8         | 0.44%   |
| 5.15.41-gentoo           | 8         | 0.44%   |
| 4.19.86-gentoo           | 8         | 0.44%   |
| 6.1.12-gentoo-x86_64     | 7         | 0.39%   |
| 5.4.97-gentoo-x86_64     | 7         | 0.39%   |
| 5.4.66-gentoo-x86_64     | 7         | 0.39%   |
| 5.17.1-gentoo-r1         | 7         | 0.39%   |
| 5.15.23-gentoo           | 7         | 0.39%   |
| 5.15.11-gentoo-x86_64    | 7         | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.27 | 46        | 2.56%   |
| 5.4.38  | 45        | 2.5%    |
| 5.15.32 | 41        | 2.28%   |
| 5.10.61 | 39        | 2.17%   |
| 5.4.48  | 33        | 1.83%   |
| 5.15.80 | 32        | 1.78%   |
| 5.10.76 | 32        | 1.78%   |
| 6.1.12  | 30        | 1.67%   |
| 5.15.75 | 30        | 1.67%   |
| 5.4.97  | 25        | 1.39%   |
| 5.4.28  | 25        | 1.39%   |
| 5.15.59 | 25        | 1.39%   |
| 5.15.52 | 24        | 1.33%   |
| 5.15.41 | 23        | 1.28%   |
| 5.10.52 | 23        | 1.28%   |
| 5.4.80  | 22        | 1.22%   |
| 5.15.11 | 19        | 1.06%   |
| 5.4.66  | 17        | 0.94%   |
| 5.6.15  | 16        | 0.89%   |
| 5.4.60  | 16        | 0.89%   |
| 5.15.88 | 16        | 0.89%   |
| 5.15.69 | 16        | 0.89%   |
| 5.7.0   | 15        | 0.83%   |
| 5.17.1  | 15        | 0.83%   |
| 5.15.23 | 15        | 0.83%   |
| 5.15.72 | 14        | 0.78%   |
| 5.4.72  | 13        | 0.72%   |
| 4.19.97 | 13        | 0.72%   |
| 6.0.0   | 12        | 0.67%   |
| 5.9.11  | 12        | 0.67%   |
| 5.19.0  | 12        | 0.67%   |
| 5.15.74 | 12        | 0.67%   |
| 5.15.26 | 12        | 0.67%   |
| 5.15.10 | 12        | 0.67%   |
| 6.1.7   | 10        | 0.56%   |
| 5.9.8   | 10        | 0.56%   |
| 5.8.0   | 10        | 0.56%   |
| 4.19.86 | 10        | 0.56%   |
| 5.16.0  | 9         | 0.5%    |
| 5.9.0   | 8         | 0.44%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 326       | 19.52%  |
| 5.4     | 230       | 13.77%  |
| 5.10    | 224       | 13.41%  |
| 6.1     | 89        | 5.33%   |
| 4.19    | 66        | 3.95%   |
| 5.6     | 64        | 3.83%   |
| 5.9     | 58        | 3.47%   |
| 5.8     | 54        | 3.23%   |
| 5.7     | 49        | 2.93%   |
| 5.14    | 49        | 2.93%   |
| 5.16    | 48        | 2.87%   |
| 5.17    | 47        | 2.81%   |
| 6.0     | 45        | 2.69%   |
| 5.18    | 41        | 2.46%   |
| 5.11    | 41        | 2.46%   |
| 5.19    | 36        | 2.16%   |
| 5.13    | 36        | 2.16%   |
| 5.12    | 30        | 1.8%    |
| 6.2     | 25        | 1.5%    |
| 5.5     | 17        | 1.02%   |
| 4.14    | 17        | 1.02%   |
| 5.2     | 12        | 0.72%   |
| 5.1     | 10        | 0.6%    |
| 5.3     | 9         | 0.54%   |
| 5.0     | 9         | 0.54%   |
| 4.9     | 8         | 0.48%   |
| 4.4     | 8         | 0.48%   |
| 4.18    | 7         | 0.42%   |
| 4.6     | 3         | 0.18%   |
| 4.12    | 3         | 0.18%   |
| 4.20    | 2         | 0.12%   |
| 4.10    | 2         | 0.12%   |
| 4.5     | 1         | 0.06%   |
| 4.16    | 1         | 0.06%   |
| 4.13    | 1         | 0.06%   |
| 4.1     | 1         | 0.06%   |
| 3.18    | 1         | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| x86_64   | 1317      | 95.78%  |
| i686     | 28        | 2.04%   |
| aarch64  | 12        | 0.87%   |
| ppc      | 7         | 0.51%   |
| armv7l   | 3         | 0.22%   |
| armv6l   | 3         | 0.22%   |
| armv5tel | 2         | 0.15%   |
| riscv64  | 1         | 0.07%   |
| ppc64le  | 1         | 0.07%   |
| ppc64    | 1         | 0.07%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 635       | 43.05%  |
| KDE5           | 307       | 20.81%  |
| GNOME          | 183       | 12.41%  |
| XFCE           | 128       | 8.68%   |
| KDE            | 58        | 3.93%   |
| MATE           | 37        | 2.51%   |
| dwm            | 24        | 1.63%   |
| LXQt           | 14        | 0.95%   |
| sway           | 13        | 0.88%   |
| X-Cinnamon     | 10        | 0.68%   |
| i3             | 8         | 0.54%   |
| Enlightenment  | 8         | 0.54%   |
| LXDE           | 6         | 0.41%   |
| Cinnamon       | 6         | 0.41%   |
| XSession       | 5         | 0.34%   |
| awesome        | 5         | 0.34%   |
| openbox        | 4         | 0.27%   |
| Hyprland       | 4         | 0.27%   |
| bspwm          | 4         | 0.27%   |
| Trinity        | 3         | 0.2%    |
| Unity          | 2         | 0.14%   |
| GNOME Classic  | 2         | 0.14%   |
| xmonad         | 1         | 0.07%   |
| sussy_bspwm    | 1         | 0.07%   |
| ratpoison      | 1         | 0.07%   |
| qt5ct          | 1         | 0.07%   |
| LeftWM         | 1         | 0.07%   |
| ICEWM          | 1         | 0.07%   |
| i3-with-shmlog | 1         | 0.07%   |
| fvwm           | 1         | 0.07%   |
| fluxbox        | 1         | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 801       | 54.42%  |
| Unknown | 290       | 19.7%   |
| Tty     | 223       | 15.15%  |
| Wayland | 158       | 10.73%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 709       | 49.13%  |
| SDDM    | 365       | 25.29%  |
| LightDM | 161       | 11.16%  |
| GDM     | 126       | 8.73%   |
| XDM     | 26        | 1.8%    |
| SLiM    | 24        | 1.66%   |
| LXDM    | 17        | 1.18%   |
| GREETD  | 7         | 0.49%   |
| TDM     | 6         | 0.42%   |
| KDM     | 1         | 0.07%   |
| GDM3    | 1         | 0.07%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 533       | 36.96%  |
| Unknown    | 217       | 15.05%  |
| C.UTF8     | 129       | 8.95%   |
| de_DE      | 94        | 6.52%   |
| en_GB      | 88        | 6.1%    |
| ru_RU      | 62        | 4.3%    |
| C          | 34        | 2.36%   |
| fr_FR      | 29        | 2.01%   |
| es_ES      | 23        | 1.6%    |
| en_CA      | 22        | 1.53%   |
| it_IT      | 18        | 1.25%   |
| en_AU      | 18        | 1.25%   |
| cs_CZ      | 17        | 1.18%   |
| pl_PL      | 15        | 1.04%   |
| zh_CN      | 10        | 0.69%   |
| pt_BR      | 10        | 0.69%   |
| sv_SE      | 6         | 0.42%   |
| POSIX      | 6         | 0.42%   |
| nl_NL      | 6         | 0.42%   |
| en_US.UTF8 | 6         | 0.42%   |
| el_GR      | 6         | 0.42%   |
| ru_RU.UTF8 | 5         | 0.35%   |
| nl_BE      | 5         | 0.35%   |
| ja_JP      | 5         | 0.35%   |
| fi_FI      | 4         | 0.28%   |
| en_IE      | 4         | 0.28%   |
| de_CH      | 4         | 0.28%   |
| ca_ES      | 4         | 0.28%   |
| zh_TW      | 3         | 0.21%   |
| uk_UA      | 3         | 0.21%   |
| fr_CA      | 3         | 0.21%   |
| es_MX      | 3         | 0.21%   |
| es_AR      | 3         | 0.21%   |
| en_ZA      | 3         | 0.21%   |
| ru_UA      | 2         | 0.14%   |
| ro_RO      | 2         | 0.14%   |
| pt_PT      | 2         | 0.14%   |
| mi_NZ      | 2         | 0.14%   |
| ko_KR      | 2         | 0.14%   |
| es_CL      | 2         | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1000      | 71.33%  |
| BIOS | 402       | 28.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 835       | 59.47%  |
| Btrfs    | 320       | 22.79%  |
| Xfs      | 55        | 3.92%   |
| Zfs      | 51        | 3.63%   |
| F2fs     | 50        | 3.56%   |
| Unknown  | 46        | 3.28%   |
| XXXXXXX  | 19        | 1.35%   |
| Reiserfs | 15        | 1.07%   |
| Overlay  | 3         | 0.21%   |
| Ext3     | 3         | 0.21%   |
| XXX      | 2         | 0.14%   |
| Jfs      | 2         | 0.14%   |
| Xtrfs    | 1         | 0.07%   |
| Ext2     | 1         | 0.07%   |
| Bcachefs | 1         | 0.07%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 1156      | 82.69%  |
| MBR     | 160       | 11.44%  |
| Unknown | 82        | 5.87%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 960       | 66.99%  |
| Yes       | 473       | 33.01%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 942       | 66.86%  |
| Yes       | 467       | 33.14%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 304       | 22.11%  |
| Lenovo                  | 205       | 14.91%  |
| Dell                    | 139       | 10.11%  |
| Hewlett-Packard         | 121       | 8.8%    |
| MSI                     | 119       | 8.65%   |
| Gigabyte Technology     | 90        | 6.55%   |
| ASRock                  | 82        | 5.96%   |
| Acer                    | 44        | 3.2%    |
| Unknown                 | 27        | 1.96%   |
| Intel                   | 26        | 1.89%   |
| Apple                   | 24        | 1.75%   |
| Supermicro              | 19        | 1.38%   |
| Raspberry Pi Foundation | 13        | 0.95%   |
| Timi                    | 11        | 0.8%    |
| Samsung Electronics     | 11        | 0.8%    |
| HUAWEI                  | 11        | 0.8%    |
| Fujitsu                 | 10        | 0.73%   |
| Toshiba                 | 8         | 0.58%   |
| TUXEDO                  | 7         | 0.51%   |
| Razer                   | 5         | 0.36%   |
| IBM                     | 5         | 0.36%   |
| ASRockRack              | 5         | 0.36%   |
| Notebook                | 4         | 0.29%   |
| Google                  | 4         | 0.29%   |
| TYAN Computer           | 3         | 0.22%   |
| Tekram Technology       | 3         | 0.22%   |
| System76                | 3         | 0.22%   |
| Sony                    | 3         | 0.22%   |
| Pegatron                | 3         | 0.22%   |
| Medion                  | 3         | 0.22%   |
| Foxconn                 | 3         | 0.22%   |
| Alienware               | 3         | 0.22%   |
| win element             | 2         | 0.15%   |
| Valve                   | 2         | 0.15%   |
| Star Labs               | 2         | 0.15%   |
| Schenker                | 2         | 0.15%   |
| Purism                  | 2         | 0.15%   |
| Positivo                | 2         | 0.15%   |
| Microsoft               | 2         | 0.15%   |
| Huanan                  | 2         | 0.15%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Unknown                                 | 34        | 2.47%   |
| ASUS All Series                         | 19        | 1.38%   |
| ASUS TUF Gaming X570-PLUS               | 10        | 0.73%   |
| Supermicro Super Server                 | 8         | 0.58%   |
| ASUS PRIME X570-PRO                     | 8         | 0.58%   |
| ASUS PRIME X470-PRO                     | 7         | 0.51%   |
| MSI MS-7C02                             | 6         | 0.44%   |
| MSI MS-7A38                             | 6         | 0.44%   |
| Dell XPS 15 9570                        | 6         | 0.44%   |
| ASUS ROG STRIX X570-E GAMING            | 6         | 0.44%   |
| MSI MS-7C37                             | 5         | 0.36%   |
| MSI MS-7C35                             | 5         | 0.36%   |
| HP Pavilion Notebook                    | 5         | 0.36%   |
| ASUS PRIME X370-PRO                     | 5         | 0.36%   |
| ASRock B450 Pro4                        | 5         | 0.36%   |
| MSI MS-7C91                             | 4         | 0.29%   |
| MSI MS-7B89                             | 4         | 0.29%   |
| MSI MS-7B86                             | 4         | 0.29%   |
| MSI MS-7B79                             | 4         | 0.29%   |
| HP OMEN by Laptop                       | 4         | 0.29%   |
| HP Laptop 14-dk1xxx                     | 4         | 0.29%   |
| Dell XPS 17 9710                        | 4         | 0.29%   |
| Dell XPS 13 9310                        | 4         | 0.29%   |
| ASUS Z170 PRO GAMING                    | 4         | 0.29%   |
| ASUS TUF Gaming B550-PLUS               | 4         | 0.29%   |
| ASUS ROG Strix G513QY_G513QY            | 4         | 0.29%   |
| ASUS ROG STRIX B550-F GAMING            | 4         | 0.29%   |
| ASUS ROG STRIX B450-F GAMING            | 4         | 0.29%   |
| ASUS ROG CROSSHAIR VIII HERO            | 4         | 0.29%   |
| ASUS ROG CROSSHAIR VIII DARK HERO       | 4         | 0.29%   |
| ASUS ROG CROSSHAIR VII HERO             | 4         | 0.29%   |
| ASUS PRIME X570-P                       | 4         | 0.29%   |
| ASUS PRIME B450M-A                      | 4         | 0.29%   |
| ASRock B550M Steel Legend               | 4         | 0.29%   |
| TYAN S7025                              | 3         | 0.22%   |
| Tekram P6B40-A4X-i440BX Rev             | 3         | 0.22%   |
| Supermicro X10SAE                       | 3         | 0.22%   |
| RPi Raspberry Pi Model B Rev 2          | 3         | 0.22%   |
| RPi Raspberry Pi 3 Model B Plus Rev 1.3 | 3         | 0.22%   |
| MSI MS-7C34                             | 3         | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 117       | 8.51%   |
| ASUS ROG          | 74        | 5.38%   |
| ASUS PRIME        | 50        | 3.64%   |
| Dell XPS          | 40        | 2.91%   |
| Dell Latitude     | 40        | 2.91%   |
| ASUS TUF          | 38        | 2.76%   |
| Unknown           | 34        | 2.47%   |
| Acer Aspire       | 26        | 1.89%   |
| Lenovo Legion     | 24        | 1.75%   |
| Lenovo IdeaPad    | 24        | 1.75%   |
| HP Pavilion       | 24        | 1.75%   |
| HP EliteBook      | 19        | 1.38%   |
| ASUS All          | 19        | 1.38%   |
| Dell Inspiron     | 18        | 1.31%   |
| Dell Precision    | 16        | 1.16%   |
| HP Laptop         | 14        | 1.02%   |
| RPi Raspberry     | 13        | 0.95%   |
| Lenovo Yoga       | 13        | 0.95%   |
| HP OMEN           | 11        | 0.8%    |
| Gigabyte X570     | 11        | 0.8%    |
| ASRock X570       | 10        | 0.73%   |
| HP ProBook        | 9         | 0.65%   |
| Dell OptiPlex     | 9         | 0.65%   |
| Supermicro Super  | 8         | 0.58%   |
| Gigabyte B450     | 8         | 0.58%   |
| ASUS ZenBook      | 8         | 0.58%   |
| ASUS VivoBook     | 8         | 0.58%   |
| ASRock X370       | 8         | 0.58%   |
| HP ProLiant       | 7         | 0.51%   |
| Gigabyte B450M    | 7         | 0.51%   |
| Acer Nitro        | 7         | 0.51%   |
| Toshiba Satellite | 6         | 0.44%   |
| Timi RedmiBook    | 6         | 0.44%   |
| MSI MS-7C02       | 6         | 0.44%   |
| MSI MS-7A38       | 6         | 0.44%   |
| HP ZBook          | 6         | 0.44%   |
| HP Compaq         | 6         | 0.44%   |
| ASRock B450       | 6         | 0.44%   |
| Acer Swift        | 6         | 0.44%   |
| Razer Blade       | 5         | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 224       | 16.29%  |
| 2020    | 193       | 14.04%  |
| 2018    | 177       | 12.87%  |
| 2021    | 139       | 10.11%  |
| 2017    | 90        | 6.55%   |
| 2015    | 68        | 4.95%   |
| 2012    | 63        | 4.58%   |
| 2016    | 57        | 4.15%   |
| 2022    | 56        | 4.07%   |
| 2014    | 54        | 3.93%   |
| 2013    | 53        | 3.85%   |
| 2011    | 46        | 3.35%   |
| 2010    | 36        | 2.62%   |
| 2008    | 29        | 2.11%   |
| Unknown | 28        | 2.04%   |
| 2009    | 27        | 1.96%   |
| 2007    | 9         | 0.65%   |
| 2006    | 7         | 0.51%   |
| 2005    | 5         | 0.36%   |
| 2004    | 5         | 0.36%   |
| 2003    | 4         | 0.29%   |
| 2000    | 3         | 0.22%   |
| 2023    | 2         | 0.15%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 649       | 47.2%   |
| Desktop        | 617       | 44.87%  |
| Server         | 37        | 2.69%   |
| Convertible    | 30        | 2.18%   |
| System on chip | 16        | 1.16%   |
| Mini pc        | 14        | 1.02%   |
| All in one     | 7         | 0.51%   |
| Tablet         | 3         | 0.22%   |
| Phone          | 1         | 0.07%   |
| Stick pc       | 1         | 0.07%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1353      | 98.04%  |
| Enabled  | 27        | 1.96%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1365      | 99.27%  |
| Yes  | 10        | 0.73%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 32.01-64.0      | 343       | 24.29%  |
| 16.01-24.0      | 342       | 24.22%  |
| 8.01-16.0       | 214       | 15.16%  |
| 4.01-8.0        | 168       | 11.9%   |
| 64.01-256.0     | 145       | 10.27%  |
| 3.01-4.0        | 77        | 5.45%   |
| 24.01-32.0      | 49        | 3.47%   |
| 1.01-2.0        | 27        | 1.91%   |
| 0.51-1.0        | 19        | 1.35%   |
| 2.01-3.0        | 17        | 1.2%    |
| 0.01-0.5        | 8         | 0.57%   |
| More than 256.0 | 3         | 0.21%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 337       | 20.73%  |
| 4.01-8.0    | 300       | 18.45%  |
| 2.01-3.0    | 271       | 16.67%  |
| 3.01-4.0    | 182       | 11.19%  |
| 8.01-16.0   | 167       | 10.27%  |
| 0.01-0.5    | 160       | 9.84%   |
| 0.51-1.0    | 137       | 8.43%   |
| 16.01-24.0  | 43        | 2.64%   |
| 32.01-64.0  | 12        | 0.74%   |
| 24.01-32.0  | 10        | 0.62%   |
| 64.01-256.0 | 4         | 0.25%   |
| 0           | 3         | 0.18%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 633       | 43.84%  |
| 2      | 377       | 26.11%  |
| 3      | 172       | 11.91%  |
| 4      | 97        | 6.72%   |
| 5      | 68        | 4.71%   |
| 6      | 32        | 2.22%   |
| 7      | 24        | 1.66%   |
| 8      | 13        | 0.9%    |
| 0      | 11        | 0.76%   |
| 9      | 5         | 0.35%   |
| 13     | 3         | 0.21%   |
| 12     | 3         | 0.21%   |
| 26     | 1         | 0.07%   |
| 21     | 1         | 0.07%   |
| 18     | 1         | 0.07%   |
| 17     | 1         | 0.07%   |
| 11     | 1         | 0.07%   |
| 10     | 1         | 0.07%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1097      | 78.47%  |
| Yes       | 301       | 21.53%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1195      | 86.34%  |
| No        | 189       | 13.66%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 939       | 67.9%   |
| No        | 444       | 32.1%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 869       | 62.43%  |
| No        | 523       | 37.57%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 282       | 20.27%  |
| Germany      | 209       | 15.03%  |
| Russia       | 126       | 9.06%   |
| UK           | 67        | 4.82%   |
| France       | 59        | 4.24%   |
| Canada       | 52        | 3.74%   |
| China        | 45        | 3.24%   |
| Spain        | 44        | 3.16%   |
| Poland       | 43        | 3.09%   |
| Czechia      | 34        | 2.44%   |
| Australia    | 34        | 2.44%   |
| Italy        | 30        | 2.16%   |
| Sweden       | 28        | 2.01%   |
| Netherlands  | 28        | 2.01%   |
| Finland      | 25        | 1.8%    |
| Ukraine      | 21        | 1.51%   |
| Brazil       | 18        | 1.29%   |
| Switzerland  | 16        | 1.15%   |
| Greece       | 16        | 1.15%   |
| Belgium      | 14        | 1.01%   |
| Mexico       | 13        | 0.93%   |
| Austria      | 12        | 0.86%   |
| Japan        | 11        | 0.79%   |
| Norway       | 10        | 0.72%   |
| Belarus      | 10        | 0.72%   |
| Turkey       | 9         | 0.65%   |
| Romania      | 9         | 0.65%   |
| India        | 9         | 0.65%   |
| Hong Kong    | 9         | 0.65%   |
| Hungary      | 8         | 0.58%   |
| Taiwan       | 6         | 0.43%   |
| Slovakia     | 6         | 0.43%   |
| Argentina    | 6         | 0.43%   |
| Slovenia     | 5         | 0.36%   |
| Portugal     | 5         | 0.36%   |
| New Zealand  | 5         | 0.36%   |
| Vietnam      | 4         | 0.29%   |
| South Africa | 4         | 0.29%   |
| Lithuania    | 4         | 0.29%   |
| Estonia      | 4         | 0.29%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Berlin            | 50        | 3.31%   |
| Moscow            | 44        | 2.91%   |
| St Petersburg     | 19        | 1.26%   |
| Sydney            | 17        | 1.12%   |
| Athens            | 16        | 1.06%   |
| Warsaw            | 15        | 0.99%   |
| Munich            | 14        | 0.93%   |
| Los Angeles       | 12        | 0.79%   |
| Vancouver         | 11        | 0.73%   |
| Helsinki          | 11        | 0.73%   |
| Amsterdam         | 11        | 0.73%   |
| Kyiv              | 10        | 0.66%   |
| Prague            | 9         | 0.6%    |
| Paris             | 9         | 0.6%    |
| Milan             | 9         | 0.6%    |
| Guangzhou         | 9         | 0.6%    |
| Cieszyn           | 9         | 0.6%    |
| Wuelfrath         | 8         | 0.53%   |
| Vladivostok       | 8         | 0.53%   |
| Seattle           | 8         | 0.53%   |
| Melbourne         | 8         | 0.53%   |
| Frankfurt am Main | 8         | 0.53%   |
| Ponetovice        | 7         | 0.46%   |
| Ottawa            | 7         | 0.46%   |
| Minsk             | 7         | 0.46%   |
| Beijing           | 7         | 0.46%   |
| Woolwich          | 6         | 0.4%    |
| Weatherford       | 6         | 0.4%    |
| Vienna            | 6         | 0.4%    |
| Perth             | 6         | 0.4%    |
| Oulu              | 6         | 0.4%    |
| New York          | 6         | 0.4%    |
| Manitowoc         | 6         | 0.4%    |
| Hamburg           | 6         | 0.4%    |
| Dienheim          | 6         | 0.4%    |
| Zurich            | 5         | 0.33%   |
| Yekaterinburg     | 5         | 0.33%   |
| Toronto           | 5         | 0.33%   |
| Swansea           | 5         | 0.33%   |
| Sao Paulo         | 5         | 0.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 526       | 1048   | 22.55%  |
| WDC                         | 400       | 870    | 17.15%  |
| Seagate                     | 282       | 609    | 12.09%  |
| Kingston                    | 113       | 161    | 4.84%   |
| Toshiba                     | 111       | 179    | 4.76%   |
| SanDisk                     | 110       | 153    | 4.71%   |
| Intel                       | 108       | 173    | 4.63%   |
| Crucial                     | 68        | 114    | 2.91%   |
| SK hynix                    | 65        | 77     | 2.79%   |
| Unknown                     | 61        | 87     | 2.61%   |
| Hitachi                     | 57        | 139    | 2.44%   |
| HGST                        | 55        | 90     | 2.36%   |
| A-DATA Technology           | 36        | 52     | 1.54%   |
| Micron Technology           | 31        | 40     | 1.33%   |
| Phison Electronics          | 20        | 24     | 0.86%   |
| Phison                      | 19        | 29     | 0.81%   |
| KIOXIA                      | 18        | 23     | 0.77%   |
| Corsair                     | 18        | 33     | 0.77%   |
| OCZ                         | 16        | 21     | 0.69%   |
| Apple                       | 9         | 11     | 0.39%   |
| GOODRAM                     | 8         | 35     | 0.34%   |
| China                       | 8         | 18     | 0.34%   |
| Transcend                   | 7         | 12     | 0.3%    |
| Silicon Motion              | 7         | 13     | 0.3%    |
| Plextor                     | 7         | 8      | 0.3%    |
| Patriot                     | 7         | 11     | 0.3%    |
| Fujitsu                     | 7         | 10     | 0.3%    |
| XPG                         | 6         | 12     | 0.26%   |
| SPCC                        | 6         | 6      | 0.26%   |
| Mushkin                     | 6         | 6      | 0.26%   |
| Micron/Crucial Technology   | 6         | 7      | 0.26%   |
| Kingston Technology Company | 6         | 6      | 0.26%   |
| Team                        | 5         | 12     | 0.21%   |
| PNY                         | 5         | 6      | 0.21%   |
| LITEONIT                    | 5         | 6      | 0.21%   |
| LITEON                      | 5         | 8      | 0.21%   |
| IBM                         | 5         | 6      | 0.21%   |
| Apacer                      | 5         | 7      | 0.21%   |
| Realtek Semiconductor       | 4         | 9      | 0.17%   |
| KIOXIA-EXCERIA              | 4         | 8      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 46        | 1.63%   |
| Samsung SSD 850 EVO 250GB                           | 29        | 1.03%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 28        | 0.99%   |
| Samsung SSD 860 EVO 1TB                             | 27        | 0.96%   |
| HGST HTS721010A9E630 1TB                            | 24        | 0.85%   |
| Samsung SSD 860 EVO 500GB                           | 23        | 0.82%   |
| Samsung SSD 850 EVO 500GB                           | 22        | 0.78%   |
| WDC WD30EFRX-68EUZN0 3TB                            | 21        | 0.75%   |
| Kingston SA400S37240G 240GB SSD                     | 20        | 0.71%   |
| Samsung SSD 970 EVO Plus 500GB                      | 19        | 0.67%   |
| Samsung SSD 860 EVO 250GB                           | 19        | 0.67%   |
| Samsung SSD 980 1TB                                 | 16        | 0.57%   |
| Seagate ST1000DM010-2EP102 1TB                      | 15        | 0.53%   |
| Samsung SSD 970 EVO Plus 1TB                        | 15        | 0.53%   |
| Samsung SSD 970 EVO 500GB                           | 15        | 0.53%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 13        | 0.46%   |
| Samsung SSD 970 EVO 250GB                           | 13        | 0.46%   |
| Samsung SSD 970 EVO 1TB                             | 13        | 0.46%   |
| Unknown MMC Card  32GB                              | 12        | 0.43%   |
| Samsung SSD 980 PRO 1TB                             | 12        | 0.43%   |
| Seagate ST500DM002-1BD142 500GB                     | 11        | 0.39%   |
| Seagate ST2000DM008-2FR102 2TB                      | 11        | 0.39%   |
| Seagate ST2000DM001-1ER164 2TB                      | 11        | 0.39%   |
| Samsung SSD 970 PRO 512GB                           | 11        | 0.39%   |
| Samsung SSD 840 EVO 120GB                           | 11        | 0.39%   |
| Intel SSDPEKNW010T8 1TB                             | 11        | 0.39%   |
| WDC WD20EFRX-68EUZN0 2TB                            | 10        | 0.35%   |
| Seagate ST4000DM004-2CV104 4TB                      | 10        | 0.35%   |
| Seagate ST3500418AS 500GB                           | 10        | 0.35%   |
| Samsung SSD 970 PRO 1TB                             | 10        | 0.35%   |
| Samsung SSD 970 EVO Plus 250GB                      | 10        | 0.35%   |
| Samsung SSD 850 EVO 1TB                             | 10        | 0.35%   |
| Samsung SSD 840 EVO 250GB                           | 10        | 0.35%   |
| Samsung MZVLB512HBJQ-000L2 512GB                    | 10        | 0.35%   |
| Kingston SA400S37480G 480GB SSD                     | 10        | 0.35%   |
| WDC WD40EZRZ-00GXCB0 4TB                            | 9         | 0.32%   |
| WDC WD40EFRX-68WT0N0 4TB                            | 9         | 0.32%   |
| Unknown MMC Card  64GB                              | 9         | 0.32%   |
| Unknown MMC Card  128GB                             | 9         | 0.32%   |
| Seagate ST2000DM006-2DM164 2TB                      | 9         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 298       | 689    | 36.56%  |
| Seagate             | 273       | 595    | 33.5%   |
| Toshiba             | 74        | 131    | 9.08%   |
| Hitachi             | 57        | 139    | 6.99%   |
| HGST                | 55        | 90     | 6.75%   |
| Samsung Electronics | 26        | 39     | 3.19%   |
| Fujitsu             | 7         | 10     | 0.86%   |
| IBM                 | 5         | 6      | 0.61%   |
| Unknown             | 3         | 4      | 0.37%   |
| IBM/Hitachi         | 3         | 4      | 0.37%   |
| MDT                 | 2         | 2      | 0.25%   |
| LaCie               | 2         | 12     | 0.25%   |
| Apple               | 2         | 2      | 0.25%   |
| Maxtor              | 1         | 1      | 0.12%   |
| HGST HTS            | 1         | 1      | 0.12%   |
| Hewlett-Packard     | 1         | 2      | 0.12%   |
| FNK TECH            | 1         | 1      | 0.12%   |
| Dyconn H            | 1         | 1      | 0.12%   |
| ASMT                | 1         | 1      | 0.12%   |
| ASMedia             | 1         | 1      | 0.12%   |
| AFAYA               | 1         | 1      | 0.12%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 258       | 457    | 33.95%  |
| Kingston            | 83        | 120    | 10.92%  |
| SanDisk             | 70        | 103    | 9.21%   |
| Crucial             | 60        | 99     | 7.89%   |
| WDC                 | 47        | 66     | 6.18%   |
| Intel               | 37        | 47     | 4.87%   |
| A-DATA Technology   | 22        | 32     | 2.89%   |
| OCZ                 | 15        | 20     | 1.97%   |
| SK hynix            | 13        | 14     | 1.71%   |
| Micron Technology   | 13        | 20     | 1.71%   |
| Corsair             | 11        | 18     | 1.45%   |
| Toshiba             | 10        | 12     | 1.32%   |
| GOODRAM             | 8         | 35     | 1.05%   |
| China               | 8         | 18     | 1.05%   |
| Transcend           | 6         | 11     | 0.79%   |
| Plextor             | 6         | 6      | 0.79%   |
| SPCC                | 5         | 5      | 0.66%   |
| Patriot             | 5         | 9      | 0.66%   |
| Mushkin             | 5         | 5      | 0.66%   |
| LITEONIT            | 5         | 6      | 0.66%   |
| Apple               | 5         | 6      | 0.66%   |
| Team                | 4         | 6      | 0.53%   |
| PNY                 | 4         | 5      | 0.53%   |
| Intenso             | 4         | 5      | 0.53%   |
| Seagate             | 3         | 6      | 0.39%   |
| Apacer              | 3         | 5      | 0.39%   |
| TO Exter            | 2         | 2      | 0.26%   |
| T-FORCE             | 2         | 7      | 0.26%   |
| Smartbuy            | 2         | 2      | 0.26%   |
| Netac               | 2         | 2      | 0.26%   |
| MyDigitalSSD        | 2         | 2      | 0.26%   |
| LITEON              | 2         | 3      | 0.26%   |
| Linux               | 2         | 2      | 0.26%   |
| KingSpec            | 2         | 3      | 0.26%   |
| KingDian            | 2         | 2      | 0.26%   |
| Dogfish             | 2         | 2      | 0.26%   |
| Unknown             | 2         | 3      | 0.26%   |
| Zheino              | 1         | 1      | 0.13%   |
| XrayDisk            | 1         | 1      | 0.13%   |
| Verbatim            | 1         | 1      | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 737       | 1248   | 35.79%  |
| HDD     | 635       | 1732   | 30.84%  |
| SSD     | 627       | 1202   | 30.45%  |
| MMC     | 54        | 77     | 2.62%   |
| Unknown | 6         | 8      | 0.29%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 932       | 2866   | 52.8%   |
| NVMe | 736       | 1247   | 41.7%   |
| MMC  | 54        | 77     | 3.06%   |
| SAS  | 43        | 77     | 2.44%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 635       | 1205   | 44.37%  |
| 0.51-1.0   | 409       | 688    | 28.58%  |
| 1.01-2.0   | 178       | 413    | 12.44%  |
| 3.01-4.0   | 87        | 199    | 6.08%   |
| 4.01-10.0  | 54        | 225    | 3.77%   |
| 2.01-3.0   | 53        | 162    | 3.7%    |
| 10.01-20.0 | 14        | 41     | 0.98%   |
| 20.01-50.0 | 1         | 1      | 0.07%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 286       | 19.29%  |
| 101-250        | 270       | 18.21%  |
| 501-1000       | 245       | 16.52%  |
| 1001-2000      | 181       | 12.2%   |
| More than 3000 | 158       | 10.65%  |
| Unknown        | 86        | 5.8%    |
| 51-100         | 77        | 5.19%   |
| 2001-3000      | 76        | 5.12%   |
| 1-20           | 68        | 4.59%   |
| 21-50          | 36        | 2.43%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 321       | 20.67%  |
| 21-50          | 223       | 14.36%  |
| 101-250        | 223       | 14.36%  |
| 251-500        | 193       | 12.43%  |
| 51-100         | 150       | 9.66%   |
| 501-1000       | 142       | 9.14%   |
| 1001-2000      | 100       | 6.44%   |
| Unknown        | 86        | 5.54%   |
| More than 3000 | 74        | 4.76%   |
| 2001-3000      | 41        | 2.64%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                     | Computers | Drives | Percent |
|-----------------------------------------------------------|-----------|--------|---------|
| Seagate ST3500418AS 500GB                                 | 6         | 7      | 2.21%   |
| HGST HTS721010A9E630 1TB                                  | 6         | 7      | 2.21%   |
| WDC WD40EFRX-68WT0N0 4TB                                  | 4         | 14     | 1.47%   |
| Seagate ST500DM002-1BD142 500GB                           | 4         | 4      | 1.47%   |
| WDC WD30EFRX-68EUZN0 3TB                                  | 3         | 4      | 1.1%    |
| WDC WD30EFRX-68AX9N0 3TB                                  | 3         | 5      | 1.1%    |
| Seagate ST8000AS0002-1NA17Z 8TB                           | 3         | 15     | 1.1%    |
| Seagate ST500DM002-1BC142 500GB                           | 3         | 3      | 1.1%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                        | 3         | 6      | 1.1%    |
| Samsung Electronics SSD 980 1TB                           | 3         | 3      | 1.1%    |
| Samsung Electronics SSD 850 EVO 1TB                       | 3         | 3      | 1.1%    |
| Kingston RBU-SNS8350DES3128GP 128GB SSD                   | 3         | 3      | 1.1%    |
| IBM DJSA-220 12GB                                         | 3         | 3      | 1.1%    |
| WDC WD60EFRX-68MYMN1 6TB                                  | 2         | 5      | 0.74%   |
| WDC WD5000BEVT-22ZAT0 500GB                               | 2         | 2      | 0.74%   |
| WDC WD40EFRX-68N32N0 4TB                                  | 2         | 2      | 0.74%   |
| WDC WD20EZRX-00D8PB0 2TB                                  | 2         | 3      | 0.74%   |
| WDC WD20EFRX-68EUZN0 2TB                                  | 2         | 5      | 0.74%   |
| WDC WD20EARS-00MVWB0 2TB                                  | 2         | 2      | 0.74%   |
| WDC WD2002FAEX-007BA0 2TB                                 | 2         | 2      | 0.74%   |
| WDC WD1600AAJS-75B4A0 160GB                               | 2         | 2      | 0.74%   |
| WDC WD15EARS-00Z5B1 1TB                                   | 2         | 2      | 0.74%   |
| WDC WD10JPVX-75JC3T0 1TB                                  | 2         | 2      | 0.74%   |
| SK hynix HFS256G39TND-N210A 256GB SSD                     | 2         | 2      | 0.74%   |
| Seagate ST4000DM000-1F2168 4TB                            | 2         | 2      | 0.74%   |
| Seagate ST31000340NS 1TB                                  | 2         | 3      | 0.74%   |
| Seagate ST3000DM001-9YN166 3TB                            | 2         | 3      | 0.74%   |
| Seagate ST2000LX001-1RG174 2TB                            | 2         | 2      | 0.74%   |
| Seagate ST2000DX002-2DV164 2TB                            | 2         | 2      | 0.74%   |
| Seagate ST2000DL003-9VT166 2TB                            | 2         | 3      | 0.74%   |
| Seagate ST1000NM0011 1TB                                  | 2         | 6      | 0.74%   |
| SanDisk SSD PLUS 480GB                                    | 2         | 2      | 0.74%   |
| SanDisk SSD PLUS 1000GB                                   | 2         | 2      | 0.74%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD                       | 2         | 2      | 0.74%   |
| Samsung Electronics SSD 870 EVO 500GB                     | 2         | 3      | 0.74%   |
| Samsung Electronics SSD 840 PRO Series 512GB              | 2         | 4      | 0.74%   |
| Samsung Electronics HD103UJ 1TB                           | 2         | 2      | 0.74%   |
| Realtek Semiconductor RTS5763DL NVMe SSD Controller 512GB | 2         | 3      | 0.74%   |
| MDT MD2000KS-00MJB0 200GB                                 | 2         | 2      | 0.74%   |
| Hitachi HDS722020ALA330 2TB                               | 2         | 16     | 0.74%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 60        | 109    | 23.26%  |
| Seagate                     | 58        | 91     | 22.48%  |
| Samsung Electronics         | 30        | 43     | 11.63%  |
| Hitachi                     | 16        | 31     | 6.2%    |
| Toshiba                     | 13        | 15     | 5.04%   |
| HGST                        | 12        | 14     | 4.65%   |
| SanDisk                     | 9         | 11     | 3.49%   |
| SK hynix                    | 6         | 7      | 2.33%   |
| Kingston                    | 6         | 6      | 2.33%   |
| Intel                       | 6         | 7      | 2.33%   |
| Crucial                     | 6         | 6      | 2.33%   |
| IBM                         | 4         | 4      | 1.55%   |
| Fujitsu                     | 4         | 4      | 1.55%   |
| Realtek Semiconductor       | 3         | 7      | 1.16%   |
| OCZ                         | 3         | 3      | 1.16%   |
| Plextor                     | 2         | 2      | 0.78%   |
| MDT                         | 2         | 2      | 0.78%   |
| IBM/Hitachi                 | 2         | 2      | 0.78%   |
| Corsair                     | 2         | 5      | 0.78%   |
| A-DATA Technology           | 2         | 2      | 0.78%   |
| Transcend                   | 1         | 1      | 0.39%   |
| SPCC                        | 1         | 1      | 0.39%   |
| PNY                         | 1         | 1      | 0.39%   |
| Mushkin                     | 1         | 1      | 0.39%   |
| Maxtor                      | 1         | 1      | 0.39%   |
| LITEON                      | 1         | 2      | 0.39%   |
| Kingston Technology Company | 1         | 1      | 0.39%   |
| HGST HTS                    | 1         | 1      | 0.39%   |
| EMTEC                       | 1         | 2      | 0.39%   |
| China                       | 1         | 1      | 0.39%   |
| Apple                       | 1         | 1      | 0.39%   |
| 2.5"                        | 1         | 1      | 0.39%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 59        | 108    | 33.33%  |
| Seagate             | 58        | 91     | 32.77%  |
| Hitachi             | 16        | 31     | 9.04%   |
| Toshiba             | 12        | 14     | 6.78%   |
| HGST                | 12        | 14     | 6.78%   |
| Samsung Electronics | 5         | 6      | 2.82%   |
| IBM                 | 4         | 4      | 2.26%   |
| Fujitsu             | 4         | 4      | 2.26%   |
| MDT                 | 2         | 2      | 1.13%   |
| IBM/Hitachi         | 2         | 2      | 1.13%   |
| Maxtor              | 1         | 1      | 0.56%   |
| HGST HTS            | 1         | 1      | 0.56%   |
| Apple               | 1         | 1      | 0.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 168       | 279    | 67.47%  |
| SSD  | 59        | 74     | 23.69%  |
| NVMe | 22        | 32     | 8.84%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Toshiba THNSN5512GPUK NVMe 512GB                 | 2         | 2      | 28.57%  |
| WDC WD6400BEVT-22A0RT0 640GB                     | 1         | 1      | 14.29%  |
| Seagate ST3500630AS 500GB                        | 1         | 2      | 14.29%  |
| Seagate ST31500341AS 1TB                         | 1         | 1      | 14.29%  |
| Samsung Electronics MZ7LN256HCHP-00000 256GB SSD | 1         | 2      | 14.29%  |
| Hitachi HTS721010G9SA00 100GB                    | 1         | 1      | 14.29%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 2         | 2      | 28.57%  |
| Seagate             | 2         | 3      | 28.57%  |
| WDC                 | 1         | 1      | 14.29%  |
| Samsung Electronics | 1         | 2      | 14.29%  |
| Hitachi             | 1         | 1      | 14.29%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1192      | 3484   | 73.04%  |
| Malfunc  | 237       | 385    | 14.52%  |
| Detected | 196       | 389    | 12.01%  |
| Failed   | 7         | 9      | 0.43%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 727       | 35.71%  |
| AMD                              | 395       | 19.4%   |
| Samsung Electronics              | 336       | 16.5%   |
| SanDisk                          | 115       | 5.65%   |
| ASMedia Technology               | 63        | 3.09%   |
| SK hynix                         | 52        | 2.55%   |
| Phison Electronics               | 51        | 2.5%    |
| Kingston Technology Company      | 37        | 1.82%   |
| Toshiba America Info Systems     | 32        | 1.57%   |
| Marvell Technology Group         | 27        | 1.33%   |
| Nvidia                           | 21        | 1.03%   |
| KIOXIA                           | 20        | 0.98%   |
| ADATA Technology                 | 20        | 0.98%   |
| Micron Technology                | 19        | 0.93%   |
| Micron/Crucial Technology        | 15        | 0.74%   |
| JMicron Technology               | 15        | 0.74%   |
| Silicon Motion                   | 14        | 0.69%   |
| LSI Logic / Symbios Logic        | 12        | 0.59%   |
| Broadcom / LSI                   | 12        | 0.59%   |
| Realtek Semiconductor            | 7         | 0.34%   |
| Seagate Technology               | 6         | 0.29%   |
| Adaptec                          | 6         | 0.29%   |
| Solid State Storage Technology   | 4         | 0.2%    |
| Silicon Image                    | 4         | 0.2%    |
| Silicon Integrated Systems [SiS] | 3         | 0.15%   |
| Lite-On Technology               | 3         | 0.15%   |
| INNOGRIT                         | 3         | 0.15%   |
| Union Memory (Shenzhen)          | 2         | 0.1%    |
| Lenovo                           | 2         | 0.1%    |
| Hewlett-Packard                  | 2         | 0.1%    |
| Apple                            | 2         | 0.1%    |
| 3ware                            | 2         | 0.1%    |
| Yangtze Memory Technologies      | 1         | 0.05%   |
| VIA Technologies                 | 1         | 0.05%   |
| OCZ Technology Group             | 1         | 0.05%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.05%   |
| Lite-On IT Corp. / Plextor       | 1         | 0.05%   |
| Integrated Technology Express    | 1         | 0.05%   |
| Broadcom                         | 1         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 305       | 13.14%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 205       | 8.83%   |
| AMD 400 Series Chipset SATA Controller                                         | 90        | 3.88%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 59        | 2.54%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 57        | 2.46%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 55        | 2.37%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 49        | 2.11%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 43        | 1.85%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 42        | 1.81%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 40        | 1.72%   |
| Samsung NVMe SSD Controller 980                                                | 39        | 1.68%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 37        | 1.59%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 36        | 1.55%   |
| AMD 500 Series Chipset SATA Controller                                         | 35        | 1.51%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 34        | 1.46%   |
| Intel SSD 660P Series                                                          | 33        | 1.42%   |
| Intel Volume Management Device NVMe RAID Controller                            | 30        | 1.29%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 26        | 1.12%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 25        | 1.08%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 24        | 1.03%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 23        | 0.99%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 23        | 0.99%   |
| Intel Comet Lake SATA AHCI Controller                                          | 22        | 0.95%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 22        | 0.95%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 21        | 0.9%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 21        | 0.9%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 19        | 0.82%   |
| AMD X370 Series Chipset SATA Controller                                        | 19        | 0.82%   |
| Phison E12 NVMe Controller                                                     | 18        | 0.78%   |
| Micron NVMe Storage Controller                                                 | 18        | 0.78%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 18        | 0.78%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 18        | 0.78%   |
| Phison E16 PCIe4 NVMe Controller                                               | 17        | 0.73%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 17        | 0.73%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 15        | 0.65%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 15        | 0.65%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 15        | 0.65%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 15        | 0.65%   |
| Intel SATA Controller [RAID mode]                                              | 14        | 0.6%    |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 14        | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 985       | 50.03%  |
| NVMe | 743       | 37.73%  |
| IDE  | 111       | 5.64%   |
| RAID | 102       | 5.18%   |
| SAS  | 21        | 1.07%   |
| SCSI | 7         | 0.36%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 854       | 62.11%  |
| AMD                      | 491       | 35.71%  |
| ARM                      | 17        | 1.24%   |
| Marvell Semiconductor    | 3         | 0.22%   |
| thead,c906               | 1         | 0.07%   |
| PowerNV C1P9S01 REV 1.01 | 1         | 0.07%   |
| PowerMac8,1              | 1         | 0.07%   |
| PowerMac3,6              | 1         | 0.07%   |
| PowerMac10,2             | 1         | 0.07%   |
| PowerBook6,7             | 1         | 0.07%   |
| PowerBook5,6             | 1         | 0.07%   |
| PowerBook5,5             | 1         | 0.07%   |
| PowerBook5,4             | 1         | 0.07%   |
| PowerBook3,4             | 1         | 0.07%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor            | 26        | 1.88%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 24        | 1.73%   |
| AMD Ryzen 5 3600 6-Core Processor             | 20        | 1.44%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 19        | 1.37%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 18        | 1.3%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 17        | 1.23%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 16        | 1.16%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 16        | 1.16%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 16        | 1.16%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 16        | 1.16%   |
| AMD Ryzen 9 3950X 16-Core Processor           | 15        | 1.08%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 14        | 1.01%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 14        | 1.01%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 14        | 1.01%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 14        | 1.01%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 13        | 0.94%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 13        | 0.94%   |
| AMD Ryzen 7 2700 Eight-Core Processor         | 13        | 0.94%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 12        | 0.87%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 12        | 0.87%   |
| ARM Processor                                 | 12        | 0.87%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 12        | 0.87%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 12        | 0.87%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 11        | 0.79%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 11        | 0.79%   |
| AMD Ryzen 7 3800X 8-Core Processor            | 11        | 0.79%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 10        | 0.72%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 10        | 0.72%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 10        | 0.72%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 9         | 0.65%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 9         | 0.65%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 9         | 0.65%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 9         | 0.65%   |
| Intel Core i9-9900K CPU @ 3.60GHz             | 8         | 0.58%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 8         | 0.58%   |
| Intel 12th Gen Core i7-12700H                 | 8         | 0.58%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 8         | 0.58%   |
| AMD FX-8350 Eight-Core Processor              | 8         | 0.58%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 7         | 0.51%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 7         | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i7          | 324       | 23.46%  |
| Intel Core i5          | 193       | 13.98%  |
| AMD Ryzen 7            | 161       | 11.66%  |
| Other                  | 126       | 9.12%   |
| AMD Ryzen 5            | 112       | 8.11%   |
| AMD Ryzen 9            | 83        | 6.01%   |
| Intel Xeon             | 66        | 4.78%   |
| Intel Celeron          | 25        | 1.81%   |
| AMD Ryzen 7 PRO        | 25        | 1.81%   |
| Intel Core i9          | 22        | 1.59%   |
| Intel Atom             | 22        | 1.59%   |
| Intel Core 2 Duo       | 21        | 1.52%   |
| AMD FX                 | 21        | 1.52%   |
| Intel Core i3          | 19        | 1.38%   |
| Intel Pentium          | 18        | 1.3%    |
| AMD Ryzen 3            | 16        | 1.16%   |
| Intel Core 2 Quad      | 10        | 0.72%   |
| Intel Pentium M        | 9         | 0.65%   |
| AMD Ryzen Threadripper | 9         | 0.65%   |
| AMD Phenom II X4       | 9         | 0.65%   |
| Intel Pentium 4        | 8         | 0.58%   |
| AMD Ryzen 5 PRO        | 8         | 0.58%   |
| AMD Phenom II X6       | 6         | 0.43%   |
| AMD A6                 | 6         | 0.43%   |
| AMD A10                | 5         | 0.36%   |
| ARM BCM                | 4         | 0.29%   |
| AMD Sempron            | 4         | 0.29%   |
| AMD Athlon             | 4         | 0.29%   |
| Intel Pentium Silver   | 3         | 0.22%   |
| Intel Pentium III      | 3         | 0.22%   |
| Intel Core m3          | 3         | 0.22%   |
| Intel Core 2           | 3         | 0.22%   |
| AMD EPYC               | 3         | 0.22%   |
| AMD E                  | 3         | 0.22%   |
| AMD Athlon II X3       | 3         | 0.22%   |
| AMD Athlon 64 X2       | 3         | 0.22%   |
| AMD A8                 | 3         | 0.22%   |
| Intel Genuine          | 2         | 0.14%   |
| AMD E1                 | 2         | 0.14%   |
| Intel Xeon Silver      | 1         | 0.07%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 476       | 34.44%  |
| 8       | 251       | 18.16%  |
| 6       | 226       | 16.35%  |
| 2       | 219       | 15.85%  |
| 12      | 62        | 4.49%   |
| 16      | 50        | 3.62%   |
| 1       | 46        | 3.33%   |
| 14      | 13        | 0.94%   |
| Unknown | 11        | 0.8%    |
| 10      | 7         | 0.51%   |
| 3       | 7         | 0.51%   |
| 32      | 4         | 0.29%   |
| 28      | 2         | 0.14%   |
| 24      | 2         | 0.14%   |
| 20      | 2         | 0.14%   |
| 64      | 1         | 0.07%   |
| 44      | 1         | 0.07%   |
| 22      | 1         | 0.07%   |
| 18      | 1         | 0.07%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1339      | 97.24%  |
| 2       | 28        | 2.03%   |
| Unknown | 10        | 0.73%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1079      | 78.08%  |
| 1       | 291       | 21.06%  |
| Unknown | 11        | 0.8%    |
| 4       | 1         | 0.07%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1328      | 96.58%  |
| 32-bit         | 32        | 2.33%   |
| Unknown        | 15        | 1.09%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 210       | 14.68%  |
| 0x906ea    | 69        | 4.82%   |
| 0x08701021 | 57        | 3.98%   |
| 0x506e3    | 54        | 3.77%   |
| 0x306a9    | 45        | 3.14%   |
| 0x306c3    | 44        | 3.07%   |
| 0x806ec    | 41        | 2.87%   |
| 0x0800820d | 39        | 2.73%   |
| 0x906e9    | 37        | 2.59%   |
| 0x806ea    | 36        | 2.52%   |
| 0x0a50000c | 36        | 2.52%   |
| 0x08701013 | 34        | 2.38%   |
| 0x806c1    | 33        | 2.31%   |
| 0x206a7    | 33        | 2.31%   |
| 0x08600106 | 30        | 2.1%    |
| 0x806e9    | 27        | 1.89%   |
| 0x0a201016 | 26        | 1.82%   |
| 0x906ed    | 21        | 1.47%   |
| 0x0a201009 | 20        | 1.4%    |
| 0x08001138 | 20        | 1.4%    |
| 0xa0652    | 18        | 1.26%   |
| 0x08108109 | 18        | 1.26%   |
| 0x1067a    | 17        | 1.19%   |
| 0x906a3    | 16        | 1.12%   |
| 0x806d1    | 16        | 1.12%   |
| 0x40651    | 16        | 1.12%   |
| 0x406e3    | 14        | 0.98%   |
| 0x08600103 | 14        | 0.98%   |
| 0x206c2    | 13        | 0.91%   |
| 0x306f2    | 12        | 0.84%   |
| 0x306d4    | 12        | 0.84%   |
| 0xa0671    | 11        | 0.77%   |
| 0x90672    | 11        | 0.77%   |
| 0x08108102 | 11        | 0.77%   |
| 0xa0655    | 10        | 0.7%    |
| 0x0a601203 | 10        | 0.7%    |
| 0x706e5    | 9         | 0.63%   |
| 0x306e4    | 9         | 0.63%   |
| 0x30678    | 9         | 0.63%   |
| 0x08608103 | 9         | 0.63%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 275       | 19.84%  |
| Zen 2            | 165       | 11.9%   |
| Zen 3            | 105       | 7.58%   |
| Haswell          | 83        | 5.99%   |
| Zen+             | 80        | 5.77%   |
| Unknown          | 77        | 5.56%   |
| Skylake          | 76        | 5.48%   |
| IvyBridge        | 58        | 4.18%   |
| SandyBridge      | 45        | 3.25%   |
| Zen              | 40        | 2.89%   |
| TigerLake        | 38        | 2.74%   |
| CometLake        | 37        | 2.67%   |
| IceLake          | 35        | 2.53%   |
| Alderlake Hybrid | 33        | 2.38%   |
| Broadwell        | 27        | 1.95%   |
| Penryn           | 23        | 1.66%   |
| Westmere         | 22        | 1.59%   |
| Silvermont       | 22        | 1.59%   |
| K10              | 20        | 1.44%   |
| Piledriver       | 19        | 1.37%   |
| P6               | 16        | 1.15%   |
| Core             | 14        | 1.01%   |
| Bonnell          | 13        | 0.94%   |
| Goldmont plus    | 9         | 0.65%   |
| NetBurst         | 8         | 0.58%   |
| Nehalem          | 8         | 0.58%   |
| K8 Hammer        | 7         | 0.51%   |
| Steamroller      | 5         | 0.36%   |
| Bulldozer        | 5         | 0.36%   |
| Bobcat           | 5         | 0.36%   |
| Jaguar           | 4         | 0.29%   |
| Goldmont         | 4         | 0.29%   |
| Excavator        | 3         | 0.22%   |
| Puma             | 2         | 0.14%   |
| K10 Llano        | 2         | 0.14%   |
| Tremont          | 1         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 580       | 35.58%  |
| Nvidia                           | 536       | 32.88%  |
| AMD                              | 471       | 28.9%   |
| ASPEED Technology                | 26        | 1.6%    |
| Matrox Electronics Systems       | 16        | 0.98%   |
| Silicon Integrated Systems [SiS] | 1         | 0.06%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 77        | 4.55%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 57        | 3.37%   |
| AMD Renoir                                                                  | 57        | 3.37%   |
| Intel UHD Graphics 620                                                      | 43        | 2.54%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 36        | 2.13%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 36        | 2.13%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 34        | 2.01%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 34        | 2.01%   |
| Intel HD Graphics 530                                                       | 32        | 1.89%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 30        | 1.77%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 26        | 1.54%   |
| ASPEED Technology ASPEED Graphics Family                                    | 26        | 1.54%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 25        | 1.48%   |
| Intel HD Graphics 620                                                       | 22        | 1.3%    |
| Intel Alder Lake-P Integrated Graphics Controller                           | 19        | 1.12%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 19        | 1.12%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 19        | 1.12%   |
| Intel HD Graphics 630                                                       | 18        | 1.06%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 17        | 1.01%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 17        | 1.01%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 17        | 1.01%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 15        | 0.89%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 15        | 0.89%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 15        | 0.89%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 15        | 0.89%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 14        | 0.83%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 14        | 0.83%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 14        | 0.83%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 14        | 0.83%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 13        | 0.77%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 13        | 0.77%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 12        | 0.71%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 12        | 0.71%   |
| Intel HD Graphics 5500                                                      | 12        | 0.71%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 12        | 0.71%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 11        | 0.65%   |
| Nvidia GP108M [GeForce MX150]                                               | 11        | 0.65%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 11        | 0.65%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 11        | 0.65%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 11        | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x AMD                  | 385       | 27.6%   |
| 1 x Intel                | 346       | 24.8%   |
| 1 x Nvidia               | 302       | 21.65%  |
| Intel + Nvidia           | 192       | 13.76%  |
| AMD + Nvidia             | 36        | 2.58%   |
| 2 x AMD                  | 26        | 1.86%   |
| Other                    | 25        | 1.79%   |
| 1 x ASPEED               | 23        | 1.65%   |
| Intel + AMD              | 22        | 1.58%   |
| 1 x Matrox               | 14        | 1%      |
| 2 x Intel                | 9         | 0.65%   |
| 2 x Nvidia               | 7         | 0.5%    |
| AMD + ASPEED             | 2         | 0.14%   |
| 1 x SiS                  | 1         | 0.07%   |
| Nvidia + Matrox          | 1         | 0.07%   |
| Nvidia + ASPEED          | 1         | 0.07%   |
| Intel + 2 x Nvidia       | 1         | 0.07%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.07%   |
| AMD + Matrox             | 1         | 0.07%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 976       | 69.02%  |
| Proprietary | 332       | 23.48%  |
| Unknown     | 106       | 7.5%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 664       | 46.24%  |
| 7.01-8.0   | 159       | 11.07%  |
| 0.01-0.5   | 145       | 10.1%   |
| 1.01-2.0   | 132       | 9.19%   |
| 3.01-4.0   | 123       | 8.57%   |
| 0.51-1.0   | 71        | 4.94%   |
| 8.01-16.0  | 62        | 4.32%   |
| 5.01-6.0   | 56        | 3.9%    |
| 2.01-3.0   | 16        | 1.11%   |
| 16.01-24.0 | 6         | 0.42%   |
| 4.01-5.0   | 2         | 0.14%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 168       | 10.74%  |
| AU Optronics            | 140       | 8.95%   |
| Dell                    | 130       | 8.31%   |
| BOE                     | 120       | 7.67%   |
| LG Display              | 104       | 6.65%   |
| Chimei Innolux          | 93        | 5.95%   |
| Goldstar                | 76        | 4.86%   |
| Sharp                   | 54        | 3.45%   |
| Hewlett-Packard         | 53        | 3.39%   |
| Ancor Communications    | 52        | 3.32%   |
| AOC                     | 51        | 3.26%   |
| BenQ                    | 49        | 3.13%   |
| Acer                    | 45        | 2.88%   |
| Lenovo                  | 35        | 2.24%   |
| Iiyama                  | 35        | 2.24%   |
| ASUSTek Computer        | 33        | 2.11%   |
| ViewSonic               | 32        | 2.05%   |
| Philips                 | 30        | 1.92%   |
| Apple                   | 28        | 1.79%   |
| Eizo                    | 17        | 1.09%   |
| Chi Mei Optoelectronics | 16        | 1.02%   |
| LG Electronics          | 12        | 0.77%   |
| PANDA                   | 10        | 0.64%   |
| CSO                     | 10        | 0.64%   |
| Unknown                 | 9         | 0.58%   |
| Fujitsu Siemens         | 9         | 0.58%   |
| MSI                     | 8         | 0.51%   |
| Gigabyte Technology     | 7         | 0.45%   |
| Sony                    | 6         | 0.38%   |
| NEC Computers           | 6         | 0.38%   |
| InfoVision              | 6         | 0.38%   |
| Idek Iiyama             | 6         | 0.38%   |
| HannStar                | 6         | 0.38%   |
| Unknown                 | 6         | 0.38%   |
| Sceptre Tech            | 5         | 0.32%   |
| Panasonic               | 4         | 0.26%   |
| Toshiba                 | 3         | 0.19%   |
| TMX                     | 3         | 0.19%   |
| RTK                     | 3         | 0.19%   |
| HVR                     | 3         | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 9         | 0.54%   |
| Iiyama PL2473HD IVM6107 1920x1080 521x293mm 23.5-inch                 | 8         | 0.48%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 8         | 0.48%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 7         | 0.42%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 7         | 0.42%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 7         | 0.42%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 6         | 0.36%   |
| Iiyama PL2409HD IVM560C 1920x1080 521x293mm 23.5-inch                 | 6         | 0.36%   |
| Fujitsu Siemens P24W-6 IPS FUS07EA 1920x1200 518x324mm 24.1-inch      | 6         | 0.36%   |
| Unknown                                                               | 6         | 0.36%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 5         | 0.3%    |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 5         | 0.3%    |
| Dell U2715H DELD066 2560x1440 597x336mm 27.0-inch                     | 5         | 0.3%    |
| Dell P2418D DELD0C1 2560x1440 526x296mm 23.8-inch                     | 5         | 0.3%    |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch      | 5         | 0.3%    |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch        | 5         | 0.3%    |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch               | 4         | 0.24%   |
| Sceptre Tech C305W-2560UN SPT0C0D 2560x1080 690x291mm 29.5-inch       | 4         | 0.24%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 4         | 0.24%   |
| Hewlett-Packard 22es HWP331B 1920x1080 476x268mm 21.5-inch            | 4         | 0.24%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 4         | 0.24%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 4         | 0.24%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch      | 4         | 0.24%   |
| Acer T232HL ACR041F 1920x1080 509x286mm 23.0-inch                     | 4         | 0.24%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 3         | 0.18%   |
| TMX LCD Monitor TMX1560 1920x1080 344x194mm 15.5-inch                 | 3         | 0.18%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 3         | 0.18%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch               | 3         | 0.18%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 3         | 0.18%   |
| Sharp LCD Monitor SHP14D6 3840x2400 366x229mm 17.0-inch               | 3         | 0.18%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch               | 3         | 0.18%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch     | 3         | 0.18%   |
| Samsung Electronics SyncMaster SAM0584 2048x1152 510x290mm 23.1-inch  | 3         | 0.18%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 3         | 0.18%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch  | 3         | 0.18%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 3         | 0.18%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch   | 3         | 0.18%   |
| Samsung Electronics C27HG7x SAM0E16 2560x1440 598x336mm 27.0-inch     | 3         | 0.18%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 3         | 0.18%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 3         | 0.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 701       | 47.05%  |
| 2560x1440 (QHD)    | 138       | 9.26%   |
| 3840x2160 (4K)     | 133       | 8.93%   |
| 1366x768 (WXGA)    | 86        | 5.77%   |
| 1920x1200 (WUXGA)  | 46        | 3.09%   |
| 1680x1050 (WSXGA+) | 39        | 2.62%   |
| 1280x1024 (SXGA)   | 39        | 2.62%   |
| 3440x1440          | 35        | 2.35%   |
| 1600x900 (HD+)     | 30        | 2.01%   |
| Unknown            | 29        | 1.95%   |
| 2560x1600          | 22        | 1.48%   |
| 1440x900 (WXGA+)   | 22        | 1.48%   |
| 2560x1080          | 19        | 1.28%   |
| 3840x2400          | 18        | 1.21%   |
| 3840x1080          | 16        | 1.07%   |
| 1280x800 (WXGA)    | 12        | 0.81%   |
| 1024x600           | 7         | 0.47%   |
| 2880x1800          | 6         | 0.4%    |
| 1600x1200          | 6         | 0.4%    |
| 2160x1440          | 5         | 0.34%   |
| 3840x1200          | 4         | 0.27%   |
| 3200x1800 (QHD+)   | 4         | 0.27%   |
| 2048x1152          | 4         | 0.27%   |
| 1360x768           | 4         | 0.27%   |
| 7680x2160          | 3         | 0.2%    |
| 3456x2160          | 3         | 0.2%    |
| 3200x2000          | 3         | 0.2%    |
| 2288x1287          | 3         | 0.2%    |
| 2256x1504          | 3         | 0.2%    |
| 2160x1200          | 3         | 0.2%    |
| 1920x540           | 3         | 0.2%    |
| 1280x960           | 3         | 0.2%    |
| 1280x854           | 3         | 0.2%    |
| 800x1280           | 2         | 0.13%   |
| 2240x1400          | 2         | 0.13%   |
| 1920x1280          | 2         | 0.13%   |
| 1400x1050          | 2         | 0.13%   |
| 1280x720 (HD)      | 2         | 0.13%   |
| 1024x768 (XGA)     | 2         | 0.13%   |
| 6720x2160          | 1         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 289       | 18.66%  |
| 27      | 202       | 13.04%  |
| 24      | 142       | 9.17%   |
| 23      | 129       | 8.33%   |
| 13      | 124       | 8.01%   |
| 14      | 98        | 6.33%   |
| Unknown | 90        | 5.81%   |
| 17      | 83        | 5.36%   |
| 21      | 79        | 5.1%    |
| 34      | 45        | 2.91%   |
| 19      | 36        | 2.32%   |
| 12      | 31        | 2%      |
| 22      | 26        | 1.68%   |
| 31      | 23        | 1.48%   |
| 16      | 19        | 1.23%   |
| 25      | 14        | 0.9%    |
| 11      | 13        | 0.84%   |
| 20      | 11        | 0.71%   |
| 84      | 10        | 0.65%   |
| 18      | 10        | 0.65%   |
| 32      | 9         | 0.58%   |
| 48      | 7         | 0.45%   |
| 29      | 6         | 0.39%   |
| 10      | 6         | 0.39%   |
| 72      | 5         | 0.32%   |
| 54      | 5         | 0.32%   |
| 40      | 5         | 0.32%   |
| 26      | 5         | 0.32%   |
| 142     | 3         | 0.19%   |
| 49      | 3         | 0.19%   |
| 8       | 3         | 0.19%   |
| 58      | 2         | 0.13%   |
| 47      | 2         | 0.13%   |
| 43      | 2         | 0.13%   |
| 28      | 2         | 0.13%   |
| 75      | 1         | 0.06%   |
| 65      | 1         | 0.06%   |
| 52      | 1         | 0.06%   |
| 50      | 1         | 0.06%   |
| 42      | 1         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 465       | 31.06%  |
| 501-600        | 413       | 27.59%  |
| 401-500        | 142       | 9.49%   |
| 201-300        | 123       | 8.22%   |
| 351-400        | 93        | 6.21%   |
| Unknown        | 90        | 6.01%   |
| 601-700        | 61        | 4.07%   |
| 701-800        | 55        | 3.67%   |
| 1001-1500      | 23        | 1.54%   |
| 1501-2000      | 16        | 1.07%   |
| 801-900        | 6         | 0.4%    |
| More than 2000 | 3         | 0.2%    |
| 101-200        | 3         | 0.2%    |
| 901-1000       | 3         | 0.2%    |
| 1-100          | 1         | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 964       | 70.73%  |
| 16/10   | 182       | 13.35%  |
| Unknown | 75        | 5.5%    |
| 21/9    | 49        | 3.6%    |
| 5/4     | 37        | 2.71%   |
| 3/2     | 21        | 1.54%   |
| 4/3     | 12        | 0.88%   |
| 32/9    | 11        | 0.81%   |
| 1.00    | 4         | 0.29%   |
| 6/5     | 2         | 0.15%   |
| 0.62    | 2         | 0.15%   |
| 3.40    | 1         | 0.07%   |
| 3.20    | 1         | 0.07%   |
| 0.67    | 1         | 0.07%   |
| 0.31    | 1         | 0.07%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 288       | 18.87%  |
| 201-250        | 282       | 18.48%  |
| 301-350        | 206       | 13.5%   |
| 81-90          | 159       | 10.42%  |
| Unknown        | 90        | 5.9%    |
| 351-500        | 80        | 5.24%   |
| 251-300        | 73        | 4.78%   |
| 151-200        | 67        | 4.39%   |
| 71-80          | 62        | 4.06%   |
| 121-130        | 58        | 3.8%    |
| More than 1000 | 31        | 2.03%   |
| 61-70          | 28        | 1.83%   |
| 141-150        | 27        | 1.77%   |
| 111-120        | 20        | 1.31%   |
| 501-1000       | 20        | 1.31%   |
| 51-60          | 15        | 0.98%   |
| 131-140        | 6         | 0.39%   |
| 41-50          | 5         | 0.33%   |
| 91-100         | 5         | 0.33%   |
| 1-40           | 4         | 0.26%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 462       | 31.6%   |
| 121-160       | 421       | 28.8%   |
| 101-120       | 276       | 18.88%  |
| 161-240       | 123       | 8.41%   |
| Unknown       | 90        | 6.16%   |
| More than 240 | 67        | 4.58%   |
| 1-50          | 23        | 1.57%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 973       | 67.85%  |
| 2     | 274       | 19.11%  |
| 0     | 130       | 9.07%   |
| 3     | 49        | 3.42%   |
| 4     | 8         | 0.56%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 862       | 43.12%  |
| Realtek Semiconductor             | 644       | 32.22%  |
| Qualcomm Atheros                  | 136       | 6.8%    |
| Broadcom                          | 84        | 4.2%    |
| MediaTek                          | 30        | 1.5%    |
| Aquantia                          | 21        | 1.05%   |
| Nvidia                            | 17        | 0.85%   |
| ASIX Electronics                  | 17        | 0.85%   |
| Marvell Technology Group          | 16        | 0.8%    |
| Lenovo                            | 13        | 0.65%   |
| Apple                             | 10        | 0.5%    |
| TP-Link                           | 9         | 0.45%   |
| Qualcomm                          | 9         | 0.45%   |
| Dell                              | 9         | 0.45%   |
| Qualcomm Atheros Communications   | 7         | 0.35%   |
| Broadcom Limited                  | 7         | 0.35%   |
| Sierra Wireless                   | 6         | 0.3%    |
| Microsoft                         | 6         | 0.3%    |
| Ralink Technology                 | 5         | 0.25%   |
| Ralink                            | 5         | 0.25%   |
| Fibocom                           | 5         | 0.25%   |
| Ericsson Business Mobile Networks | 5         | 0.25%   |
| Samsung Electronics               | 4         | 0.2%    |
| D-Link System                     | 4         | 0.2%    |
| Xiaomi                            | 3         | 0.15%   |
| Standard Microsystems             | 3         | 0.15%   |
| Microchip Technology              | 3         | 0.15%   |
| Huawei Technologies               | 3         | 0.15%   |
| D-Link                            | 3         | 0.15%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.1%    |
| STMicroelectronics                | 2         | 0.1%    |
| Silicon Integrated Systems [SiS]  | 2         | 0.1%    |
| Sigma Designs                     | 2         | 0.1%    |
| QLogic                            | 2         | 0.1%    |
| NetGear                           | 2         | 0.1%    |
| Netchip Technology                | 2         | 0.1%    |
| Metrologic Instruments            | 2         | 0.1%    |
| ICS Advent                        | 2         | 0.1%    |
| Google                            | 2         | 0.1%    |
| Dresden Elektronik                | 2         | 0.1%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 472       | 19.56%  |
| Intel Wi-Fi 6 AX200                                               | 146       | 6.05%   |
| Intel I211 Gigabit Network Connection                             | 107       | 4.43%   |
| Realtek RTL8125 2.5GbE Controller                                 | 59        | 2.45%   |
| Intel Wireless 8265 / 8275                                        | 59        | 2.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 52        | 2.15%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 45        | 1.86%   |
| Intel Ethernet Controller I225-V                                  | 36        | 1.49%   |
| Intel I210 Gigabit Network Connection                             | 35        | 1.45%   |
| Intel Ethernet Connection (2) I219-V                              | 30        | 1.24%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 29        | 1.2%    |
| Intel Wi-Fi 6 AX201                                               | 28        | 1.16%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 27        | 1.12%   |
| Intel Wireless 7265                                               | 26        | 1.08%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 26        | 1.08%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 25        | 1.04%   |
| Intel Wireless 8260                                               | 25        | 1.04%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 25        | 1.04%   |
| Intel 82574L Gigabit Network Connection                           | 25        | 1.04%   |
| Intel Wireless-AC 9260                                            | 24        | 0.99%   |
| Intel Wireless 7260                                               | 22        | 0.91%   |
| Intel Ethernet Connection (2) I219-LM                             | 22        | 0.91%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 21        | 0.87%   |
| Intel Ethernet Connection (7) I219-V                              | 21        | 0.87%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 20        | 0.83%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 20        | 0.83%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 19        | 0.79%   |
| Intel Ethernet Connection (4) I219-LM                             | 19        | 0.79%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 18        | 0.75%   |
| Intel Wireless 3165                                               | 17        | 0.7%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 16        | 0.66%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 15        | 0.62%   |
| Intel I350 Gigabit Network Connection                             | 15        | 0.62%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 15        | 0.62%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 15        | 0.62%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 13        | 0.54%   |
| Intel Ethernet Connection (2) I218-V                              | 13        | 0.54%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 12        | 0.5%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 12        | 0.5%    |
| Intel Ethernet Connection (4) I219-V                              | 12        | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 614       | 62.21%  |
| Realtek Semiconductor                 | 109       | 11.04%  |
| Qualcomm Atheros                      | 103       | 10.44%  |
| Broadcom                              | 56        | 5.67%   |
| MediaTek                              | 28        | 2.84%   |
| Qualcomm                              | 9         | 0.91%   |
| TP-Link                               | 8         | 0.81%   |
| Qualcomm Atheros Communications       | 7         | 0.71%   |
| Dell                                  | 7         | 0.71%   |
| Sierra Wireless                       | 6         | 0.61%   |
| Microsoft                             | 6         | 0.61%   |
| Ralink Technology                     | 5         | 0.51%   |
| Ralink                                | 5         | 0.51%   |
| Fibocom                               | 5         | 0.51%   |
| Broadcom Limited                      | 4         | 0.41%   |
| D-Link System                         | 3         | 0.3%    |
| D-Link                                | 3         | 0.3%    |
| NetGear                               | 2         | 0.2%    |
| Texas Instruments                     | 1         | 0.1%    |
| Senao                                 | 1         | 0.1%    |
| Quectel Wireless Solutions            | 1         | 0.1%    |
| Edimax Technology                     | 1         | 0.1%    |
| Cisco Aironet Wireless Communications | 1         | 0.1%    |
| BUFFALO                               | 1         | 0.1%    |
| AVM                                   | 1         | 0.1%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 146       | 14.73%  |
| Intel Wireless 8265 / 8275                                              | 59        | 5.95%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 45        | 4.54%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 29        | 2.93%   |
| Intel Wi-Fi 6 AX201                                                     | 28        | 2.83%   |
| Intel Wireless 7265                                                     | 26        | 2.62%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 26        | 2.62%   |
| Intel Wireless 8260                                                     | 25        | 2.52%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 25        | 2.52%   |
| Intel Wireless-AC 9260                                                  | 24        | 2.42%   |
| Intel Wireless 7260                                                     | 22        | 2.22%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 21        | 2.12%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 20        | 2.02%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 20        | 2.02%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 19        | 1.92%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 18        | 1.82%   |
| Intel Wireless 3165                                                     | 17        | 1.72%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 16        | 1.61%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 15        | 1.51%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 15        | 1.51%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 15        | 1.51%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 13        | 1.31%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 12        | 1.21%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 11        | 1.11%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 11        | 1.11%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 11        | 1.11%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 10        | 1.01%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 10        | 1.01%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 9         | 0.91%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 9         | 0.91%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 8         | 0.81%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 8         | 0.81%   |
| Intel Centrino Advanced-N 6235                                          | 8         | 0.81%   |
| Intel Alder Lake-S PCH CNVi WiFi                                        | 8         | 0.81%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 0.71%   |
| Intel Wireless 3160                                                     | 7         | 0.71%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 7         | 0.71%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 7         | 0.71%   |
| Qualcomm Atheros AR9271 802.11n                                         | 6         | 0.61%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 6         | 0.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 608       | 46.45%  |
| Intel                            | 483       | 36.9%   |
| Qualcomm Atheros                 | 46        | 3.51%   |
| Broadcom                         | 38        | 2.9%    |
| Aquantia                         | 21        | 1.6%    |
| Nvidia                           | 17        | 1.3%    |
| ASIX Electronics                 | 17        | 1.3%    |
| Marvell Technology Group         | 16        | 1.22%   |
| Lenovo                           | 13        | 0.99%   |
| Apple                            | 10        | 0.76%   |
| Xiaomi                           | 3         | 0.23%   |
| Standard Microsystems            | 3         | 0.23%   |
| Samsung Electronics              | 3         | 0.23%   |
| Microchip Technology             | 3         | 0.23%   |
| Broadcom Limited                 | 3         | 0.23%   |
| ZTE WCDMA Technologies MSM       | 2         | 0.15%   |
| Silicon Integrated Systems [SiS] | 2         | 0.15%   |
| QLogic                           | 2         | 0.15%   |
| ICS Advent                       | 2         | 0.15%   |
| Google                           | 2         | 0.15%   |
| DisplayLink                      | 2         | 0.15%   |
| 3Com                             | 2         | 0.15%   |
| TP-Link                          | 1         | 0.08%   |
| NetXen Incorporated              | 1         | 0.08%   |
| MediaTek                         | 1         | 0.08%   |
| JMicron Technology               | 1         | 0.08%   |
| Insyde Software                  | 1         | 0.08%   |
| Huawei Technologies              | 1         | 0.08%   |
| Hewlett-Packard                  | 1         | 0.08%   |
| Gemtek                           | 1         | 0.08%   |
| Davicom Semiconductor            | 1         | 0.08%   |
| D-Link System                    | 1         | 0.08%   |
| American Megatrends              | 1         | 0.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 472       | 34.28%  |
| Intel I211 Gigabit Network Connection                             | 107       | 7.77%   |
| Realtek RTL8125 2.5GbE Controller                                 | 59        | 4.28%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 52        | 3.78%   |
| Intel Ethernet Controller I225-V                                  | 36        | 2.61%   |
| Intel I210 Gigabit Network Connection                             | 35        | 2.54%   |
| Intel Ethernet Connection (2) I219-V                              | 30        | 2.18%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 27        | 1.96%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 25        | 1.82%   |
| Intel 82574L Gigabit Network Connection                           | 25        | 1.82%   |
| Intel Ethernet Connection (2) I219-LM                             | 22        | 1.6%    |
| Intel Ethernet Connection (7) I219-V                              | 21        | 1.53%   |
| Intel Ethernet Connection (4) I219-LM                             | 19        | 1.38%   |
| Intel I350 Gigabit Network Connection                             | 15        | 1.09%   |
| Intel Ethernet Connection (2) I218-V                              | 13        | 0.94%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 12        | 0.87%   |
| Intel Ethernet Connection (4) I219-V                              | 12        | 0.87%   |
| Intel Ethernet Connection I217-LM                                 | 11        | 0.8%    |
| Intel Ethernet Connection (7) I219-LM                             | 10        | 0.73%   |
| Intel Ethernet Connection (6) I219-V                              | 10        | 0.73%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 9         | 0.65%   |
| Intel 82579V Gigabit Network Connection                           | 9         | 0.65%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 9         | 0.65%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 8         | 0.58%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 7         | 0.51%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 7         | 0.51%   |
| Nvidia MCP77 Ethernet                                             | 7         | 0.51%   |
| Intel Ethernet Connection I218-LM                                 | 7         | 0.51%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 7         | 0.51%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 6         | 0.44%   |
| Intel Ethernet Connection I219-LM                                 | 6         | 0.44%   |
| Intel Ethernet Connection (5) I219-LM                             | 6         | 0.44%   |
| Apple UniNorth 2 GMAC (Sun GEM)                                   | 6         | 0.44%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 5         | 0.36%   |
| Lenovo USB-C Dock Ethernet                                        | 5         | 0.36%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 0.36%   |
| Intel Ethernet Connection (14) I219-V                             | 5         | 0.36%   |
| Intel Ethernet Connection (10) I219-V                             | 5         | 0.36%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 5         | 0.36%   |
| ASIX AX88179 Gigabit Ethernet                                     | 5         | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1195      | 54.94%  |
| WiFi     | 937       | 43.08%  |
| Modem    | 42        | 1.93%   |
| Unknown  | 1         | 0.05%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 781       | 54.2%   |
| WiFi     | 660       | 45.8%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 695       | 50.07%  |
| 1     | 553       | 39.84%  |
| 3     | 77        | 5.55%   |
| 0     | 26        | 1.87%   |
| 4     | 20        | 1.44%   |
| 6     | 7         | 0.5%    |
| 5     | 6         | 0.43%   |
| 8     | 2         | 0.14%   |
| 12    | 1         | 0.07%   |
| 9     | 1         | 0.07%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1189      | 84.15%  |
| Yes  | 224       | 15.85%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 552       | 62.02%  |
| Realtek Semiconductor           | 67        | 7.53%   |
| Cambridge Silicon Radio         | 55        | 6.18%   |
| Apple                           | 32        | 3.6%    |
| Qualcomm Atheros Communications | 25        | 2.81%   |
| IMC Networks                    | 25        | 2.81%   |
| Broadcom                        | 23        | 2.58%   |
| Foxconn / Hon Hai               | 22        | 2.47%   |
| Lite-On Technology              | 20        | 2.25%   |
| ASUSTek Computer                | 20        | 2.25%   |
| Realtek                         | 8         | 0.9%    |
| Dell                            | 8         | 0.9%    |
| MediaTek                        | 6         | 0.67%   |
| Toshiba                         | 5         | 0.56%   |
| Hewlett-Packard                 | 4         | 0.45%   |
| USI                             | 3         | 0.34%   |
| HTC (High Tech Computer)        | 3         | 0.34%   |
| Belkin Components               | 3         | 0.34%   |
| Foxconn International           | 2         | 0.22%   |
| Ralink Technology               | 1         | 0.11%   |
| Opticis                         | 1         | 0.11%   |
| Edimax Technology               | 1         | 0.11%   |
| Dynex                           | 1         | 0.11%   |
| Chicony Electronics             | 1         | 0.11%   |
| Askey Computer                  | 1         | 0.11%   |
| Actiontec Electronics           | 1         | 0.11%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                   | 150       | 16.84%  |
| Intel AX200 Bluetooth                                                | 147       | 16.5%   |
| Intel AX201 Bluetooth                                                | 86        | 9.65%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 77        | 8.64%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 55        | 6.17%   |
| Realtek Bluetooth Radio                                              | 42        | 4.71%   |
| Intel AX210 Bluetooth                                                | 26        | 2.92%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 25        | 2.81%   |
| Intel Bluetooth Device                                               | 18        | 2.02%   |
| Apple Bluetooth Host Controller                                      | 16        | 1.8%    |
| Realtek  Bluetooth 4.2 Adapter                                       | 15        | 1.68%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 14        | 1.57%   |
| IMC Networks Wireless_Device                                         | 11        | 1.23%   |
| Foxconn / Hon Hai Wireless_Device                                    | 10        | 1.12%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 9         | 1.01%   |
| IMC Networks Bluetooth Radio                                         | 9         | 1.01%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 9         | 1.01%   |
| Realtek Bluetooth Radio                                              | 8         | 0.9%    |
| Foxconn / Hon Hai Bluetooth Device                                   | 8         | 0.9%    |
| Qualcomm Atheros  Bluetooth Device                                   | 7         | 0.79%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 7         | 0.79%   |
| Lite-On Atheros AR3012 Bluetooth                                     | 7         | 0.79%   |
| MediaTek Wireless_Device                                             | 6         | 0.67%   |
| Lite-On Bluetooth Device                                             | 6         | 0.67%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 6         | 0.67%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                              | 5         | 0.56%   |
| Realtek RTL8723B Bluetooth                                           | 5         | 0.56%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 5         | 0.56%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 4         | 0.45%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 4         | 0.45%   |
| IMC Networks Bluetooth Device                                        | 4         | 0.45%   |
| Apple Bluetooth USB Host Controller                                  | 4         | 0.45%   |
| Apple Bluetooth HCI                                                  | 4         | 0.45%   |
| USI Bluetooth Device                                                 | 3         | 0.34%   |
| Qualcomm Atheros Bluetooth USB Host Controller                       | 3         | 0.34%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 3         | 0.34%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                        | 3         | 0.34%   |
| Dell DW375 Bluetooth Module                                          | 3         | 0.34%   |
| Dell BCM20702A0 Bluetooth Module                                     | 3         | 0.34%   |
| Broadcom HP Portable SoftSailing                                     | 3         | 0.34%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 764       | 36.23%  |
| AMD                                  | 544       | 25.79%  |
| Nvidia                               | 417       | 19.77%  |
| C-Media Electronics                  | 50        | 2.37%   |
| Logitech                             | 28        | 1.33%   |
| Creative Labs                        | 19        | 0.9%    |
| SteelSeries ApS                      | 17        | 0.81%   |
| Creative Technology                  | 15        | 0.71%   |
| Realtek Semiconductor                | 14        | 0.66%   |
| Lenovo                               | 14        | 0.66%   |
| ASUSTek Computer                     | 14        | 0.66%   |
| Texas Instruments                    | 13        | 0.62%   |
| Razer USA                            | 9         | 0.43%   |
| Kingston Technology                  | 9         | 0.43%   |
| JMTek                                | 9         | 0.43%   |
| Focusrite-Novation                   | 9         | 0.43%   |
| Plantronics                          | 8         | 0.38%   |
| Blue Microphones                     | 8         | 0.38%   |
| GYROCOM C&C                          | 7         | 0.33%   |
| AudioQuest                           | 7         | 0.33%   |
| Thesycon Systemsoftware & Consulting | 6         | 0.28%   |
| GN Netcom                            | 6         | 0.28%   |
| Corsair                              | 6         | 0.28%   |
| BEHRINGER International              | 6         | 0.28%   |
| Samson Technologies                  | 5         | 0.24%   |
| RODE Microphones                     | 5         | 0.24%   |
| Generalplus Technology               | 5         | 0.24%   |
| Dell                                 | 5         | 0.24%   |
| Sennheiser Communications            | 4         | 0.19%   |
| Trust                                | 3         | 0.14%   |
| Sony                                 | 3         | 0.14%   |
| Solid State Logic                    | 3         | 0.14%   |
| Silicon Integrated Systems [SiS]     | 3         | 0.14%   |
| SAVITECH                             | 3         | 0.14%   |
| No brand                             | 3         | 0.14%   |
| FiiO Electronics Technology          | 3         | 0.14%   |
| DSEA A/S                             | 3         | 0.14%   |
| Audio-Technica                       | 3         | 0.14%   |
| Yamaha                               | 2         | 0.09%   |
| TEAC                                 | 2         | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 164       | 6.46%   |
| AMD Starship/Matisse HD Audio Controller                                   | 149       | 5.87%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 97        | 3.82%   |
| Intel Cannon Lake PCH cAVS                                                 | 90        | 3.54%   |
| Intel Sunrise Point-LP HD Audio                                            | 89        | 3.5%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 80        | 3.15%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 73        | 2.87%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 55        | 2.17%   |
| AMD Navi 10 HDMI Audio                                                     | 46        | 1.81%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 44        | 1.73%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 40        | 1.57%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 39        | 1.54%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 38        | 1.5%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 38        | 1.5%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 36        | 1.42%   |
| Nvidia GP106 High Definition Audio Controller                              | 33        | 1.3%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 32        | 1.26%   |
| Nvidia TU106 High Definition Audio Controller                              | 32        | 1.26%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 32        | 1.26%   |
| Nvidia GP104 High Definition Audio Controller                              | 30        | 1.18%   |
| Nvidia GP107GL High Definition Audio Controller                            | 28        | 1.1%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 27        | 1.06%   |
| Intel Comet Lake PCH-LP cAVS                                               | 27        | 1.06%   |
| Intel Comet Lake PCH cAVS                                                  | 27        | 1.06%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 27        | 1.06%   |
| Nvidia TU104 HD Audio Controller                                           | 25        | 0.98%   |
| Nvidia GA106 High Definition Audio Controller                              | 24        | 0.94%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 24        | 0.94%   |
| Nvidia TU116 High Definition Audio Controller                              | 23        | 0.91%   |
| Nvidia GA104 High Definition Audio Controller                              | 22        | 0.87%   |
| Intel CM238 HD Audio Controller                                            | 22        | 0.87%   |
| Intel 200 Series PCH HD Audio                                              | 22        | 0.87%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 20        | 0.79%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 20        | 0.79%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 20        | 0.79%   |
| Nvidia GA102 High Definition Audio Controller                              | 18        | 0.71%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 18        | 0.71%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 18        | 0.71%   |
| AMD FCH Azalia Controller                                                  | 18        | 0.71%   |
| Nvidia GM206 High Definition Audio Controller                              | 17        | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 295       | 20.29%  |
| Kingston                     | 201       | 13.82%  |
| SK hynix                     | 197       | 13.55%  |
| Corsair                      | 132       | 9.08%   |
| Micron Technology            | 131       | 9.01%   |
| Unknown                      | 119       | 8.18%   |
| G.Skill                      | 113       | 7.77%   |
| Crucial                      | 111       | 7.63%   |
| Ramaxel Technology           | 19        | 1.31%   |
| A-DATA Technology            | 16        | 1.1%    |
| Team                         | 15        | 1.03%   |
| Patriot                      | 12        | 0.83%   |
| Elpida                       | 11        | 0.76%   |
| Transcend                    | 10        | 0.69%   |
| Nanya Technology             | 9         | 0.62%   |
| GOODRAM                      | 8         | 0.55%   |
| Unknown                      | 8         | 0.55%   |
| Unknown (ABCD)               | 4         | 0.28%   |
| AMD                          | 4         | 0.28%   |
| Timetec                      | 3         | 0.21%   |
| Apacer                       | 3         | 0.21%   |
| Toshiba                      | 2         | 0.14%   |
| KLEVV                        | 2         | 0.14%   |
| Avant                        | 2         | 0.14%   |
| Unknown (0x5D00000000000000) | 1         | 0.07%   |
| Thermaltake                  | 1         | 0.07%   |
| Teikon                       | 1         | 0.07%   |
| T-FORCE                      | 1         | 0.07%   |
| Saikano                      | 1         | 0.07%   |
| Qumo                         | 1         | 0.07%   |
| Qimonda                      | 1         | 0.07%   |
| PUSKILL                      | 1         | 0.07%   |
| PNY                          | 1         | 0.07%   |
| Patriot Memory (PDP Systems) | 1         | 0.07%   |
| Patriot Memory               | 1         | 0.07%   |
| Magnum Tech                  | 1         | 0.07%   |
| Kllisre                      | 1         | 0.07%   |
| Kimtigo                      | 1         | 0.07%   |
| Innodisk                     | 1         | 0.07%   |
| HPE                          | 1         | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 14        | 0.91%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s       | 12        | 0.78%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s      | 12        | 0.78%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s       | 11        | 0.71%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s       | 10        | 0.65%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s      | 10        | 0.65%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s       | 10        | 0.65%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s       | 10        | 0.65%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 9         | 0.58%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s       | 9         | 0.58%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s        | 9         | 0.58%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s        | 9         | 0.58%   |
| Unknown RAM Module 1GB SODIMM DDR                           | 8         | 0.52%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s      | 8         | 0.52%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s      | 8         | 0.52%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s      | 8         | 0.52%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s       | 8         | 0.52%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s      | 8         | 0.52%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s       | 8         | 0.52%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s | 8         | 0.52%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s        | 8         | 0.52%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s      | 8         | 0.52%   |
| Unknown                                                     | 8         | 0.52%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s     | 7         | 0.45%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s      | 7         | 0.45%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s       | 7         | 0.45%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s      | 6         | 0.39%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s      | 6         | 0.39%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s       | 6         | 0.39%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s       | 6         | 0.39%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s           | 6         | 0.39%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s         | 6         | 0.39%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s      | 6         | 0.39%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s      | 6         | 0.39%   |
| Unknown RAM Module 1024MB DIMM SDRAM                        | 5         | 0.32%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 5         | 0.32%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s       | 5         | 0.32%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s      | 5         | 0.32%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s       | 5         | 0.32%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s       | 5         | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 806       | 62.34%  |
| DDR3    | 279       | 21.58%  |
| DDR2    | 44        | 3.4%    |
| LPDDR4  | 39        | 3.02%   |
| Unknown | 27        | 2.09%   |
| LPDDR3  | 26        | 2.01%   |
| DDR5    | 26        | 2.01%   |
| SDRAM   | 18        | 1.39%   |
| DDR     | 16        | 1.24%   |
| LPDDR5  | 11        | 0.85%   |
| DRAM    | 1         | 0.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 603       | 46.64%  |
| DIMM         | 603       | 46.64%  |
| Row Of Chips | 78        | 6.03%   |
| Chip         | 6         | 0.46%   |
| Unknown      | 2         | 0.15%   |
| RIMM         | 1         | 0.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 564       | 40.49%  |
| 16384 | 354       | 25.41%  |
| 4096  | 235       | 16.87%  |
| 32768 | 104       | 7.47%   |
| 2048  | 88        | 6.32%   |
| 1024  | 36        | 2.58%   |
| 512   | 7         | 0.5%    |
| 256   | 5         | 0.36%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 254       | 18.16%  |
| 2667    | 217       | 15.51%  |
| 1600    | 171       | 12.22%  |
| 2400    | 98        | 7.01%   |
| 2133    | 81        | 5.79%   |
| 3600    | 75        | 5.36%   |
| 1333    | 64        | 4.57%   |
| 667     | 31        | 2.22%   |
| 3000    | 30        | 2.14%   |
| 800     | 28        | 2%      |
| Unknown | 25        | 1.79%   |
| 3733    | 24        | 1.72%   |
| 3400    | 23        | 1.64%   |
| 4267    | 22        | 1.57%   |
| 4800    | 21        | 1.5%    |
| 1867    | 20        | 1.43%   |
| 2933    | 19        | 1.36%   |
| 3466    | 17        | 1.22%   |
| 3266    | 15        | 1.07%   |
| 6400    | 14        | 1%      |
| 2666    | 14        | 1%      |
| 1334    | 14        | 1%      |
| 3800    | 11        | 0.79%   |
| 8400    | 10        | 0.71%   |
| 1067    | 9         | 0.64%   |
| 1066    | 9         | 0.64%   |
| 3866    | 8         | 0.57%   |
| 1866    | 8         | 0.57%   |
| 2800    | 6         | 0.43%   |
| 400     | 6         | 0.43%   |
| 3333    | 5         | 0.36%   |
| 4000    | 4         | 0.29%   |
| 3666    | 4         | 0.29%   |
| 3534    | 4         | 0.29%   |
| 5200    | 3         | 0.21%   |
| 4266    | 3         | 0.21%   |
| 3100    | 3         | 0.21%   |
| 3066    | 3         | 0.21%   |
| 2048    | 3         | 0.21%   |
| 533     | 3         | 0.21%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 11        | 42.31%  |
| Seiko Epson           | 3         | 11.54%  |
| Samsung Electronics   | 3         | 11.54%  |
| Canon                 | 3         | 11.54%  |
| Brother Industries    | 3         | 11.54%  |
| Xiaomi                | 1         | 3.85%   |
| Lexmark International | 1         | 3.85%   |
| Konica Minolta        | 1         | 3.85%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Canon LiDE 400                        | 2         | 7.69%   |
| Xiaomi MiMouse 2                      | 1         | 3.85%   |
| Seiko Epson WF-3520 Series            | 1         | 3.85%   |
| Seiko Epson WF-2510 Series            | 1         | 3.85%   |
| Seiko Epson AL-M310DN                 | 1         | 3.85%   |
| Samsung ML-191x/ML-252x Laser Printer | 1         | 3.85%   |
| Samsung CLP-325 Color Laser Printer   | 1         | 3.85%   |
| Samsung C460 Series                   | 1         | 3.85%   |
| Lexmark International Lexmark E352dn  | 1         | 3.85%   |
| Konica Minolta magicolor 1680MF scan  | 1         | 3.85%   |
| HP PhotoSmart 130                     | 1         | 3.85%   |
| HP LaserJet P2055 series              | 1         | 3.85%   |
| HP LaserJet M14-M17                   | 1         | 3.85%   |
| HP LaserJet 3200                      | 1         | 3.85%   |
| HP LaserJet 1020                      | 1         | 3.85%   |
| HP LaserJet 1018                      | 1         | 3.85%   |
| HP LaserJet 1010                      | 1         | 3.85%   |
| HP Deskjet D1500 series               | 1         | 3.85%   |
| HP DeskJet 5440                       | 1         | 3.85%   |
| HP DeskJet 3630 series                | 1         | 3.85%   |
| HP Deskjet 2050 J510                  | 1         | 3.85%   |
| Canon CanoScan LiDE 300               | 1         | 3.85%   |
| Brother MFC-L2700DW                   | 1         | 3.85%   |
| Brother MFC-9340CDW                   | 1         | 3.85%   |
| Brother MFC-9130CW                    | 1         | 3.85%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 5         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 2         | 40%     |
| Canon CanoScan LiDE 600F      | 1         | 20%     |
| Canon CanoScan LiDE 220       | 1         | 20%     |
| Canon CanoScan LiDE 110       | 1         | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 151       | 20%     |
| Logitech                               | 96        | 12.72%  |
| IMC Networks                           | 86        | 11.39%  |
| Microdia                               | 70        | 9.27%   |
| Realtek Semiconductor                  | 52        | 6.89%   |
| Sunplus Innovation Technology          | 40        | 5.3%    |
| Acer                                   | 40        | 5.3%    |
| Quanta                                 | 29        | 3.84%   |
| Cheng Uei Precision Industry (Foxlink) | 23        | 3.05%   |
| Lite-On Technology                     | 21        | 2.78%   |
| Apple                                  | 18        | 2.38%   |
| Syntek                                 | 17        | 2.25%   |
| Luxvisions Innotech Limited            | 16        | 2.12%   |
| Samsung Electronics                    | 10        | 1.32%   |
| Bison Electronics                      | 10        | 1.32%   |
| Z-Star Microelectronics                | 8         | 1.06%   |
| Microsoft                              | 5         | 0.66%   |
| MacroSilicon                           | 4         | 0.53%   |
| DigiTech                               | 4         | 0.53%   |
| Suyin                                  | 3         | 0.4%    |
| Generalplus Technology                 | 3         | 0.4%    |
| Creative Technology                    | 3         | 0.4%    |
| AVerMedia Technologies                 | 3         | 0.4%    |
| ARC International                      | 3         | 0.4%    |
| SunplusIT                              | 2         | 0.26%   |
| Silicon Motion                         | 2         | 0.26%   |
| Shenzhen Kingcome Optoelectronic       | 2         | 0.26%   |
| Razer USA                              | 2         | 0.26%   |
| LG Electronics                         | 2         | 0.26%   |
| KYE Systems (Mouse Systems)            | 2         | 0.26%   |
| Genesys Logic                          | 2         | 0.26%   |
| Cubeternet                             | 2         | 0.26%   |
| Alcor Micro                            | 2         | 0.26%   |
| YGTek                                  | 1         | 0.13%   |
| Xiaomi                                 | 1         | 0.13%   |
| webcam                                 | 1         | 0.13%   |
| WaveRider Communications               | 1         | 0.13%   |
| Valve Software                         | 1         | 0.13%   |
| USB3.0 HD Audio Capture                | 1         | 0.13%   |
| Sunplus Technology                     | 1         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 51        | 6.64%   |
| Microdia Integrated_Webcam_HD                        | 38        | 4.95%   |
| IMC Networks Integrated Camera                       | 36        | 4.69%   |
| Logitech HD Pro Webcam C920                          | 25        | 3.26%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 22        | 2.86%   |
| Realtek Integrated_Webcam_HD                         | 20        | 2.6%    |
| Logitech Webcam C270                                 | 17        | 2.21%   |
| Acer Integrated Camera                               | 16        | 2.08%   |
| Chicony HD Webcam                                    | 15        | 1.95%   |
| Syntek Integrated Camera                             | 12        | 1.56%   |
| Sunplus Integrated_Webcam_HD                         | 11        | 1.43%   |
| Chicony HP HD Camera                                 | 11        | 1.43%   |
| Samsung Galaxy A5 (MTP)                              | 10        | 1.3%    |
| Lite-On Integrated Camera                            | 9         | 1.17%   |
| Chicony USB2.0 Camera                                | 9         | 1.17%   |
| Microdia USB 2.0 Camera                              | 8         | 1.04%   |
| Logitech Webcam C310                                 | 7         | 0.91%   |
| Sunplus HD WebCam                                    | 6         | 0.78%   |
| Realtek Integrated Webcam HD                         | 6         | 0.78%   |
| Quanta HP Wide Vision HD Camera                      | 6         | 0.78%   |
| Quanta HD User Facing                                | 6         | 0.78%   |
| Logitech BRIO Ultra HD Webcam                        | 6         | 0.78%   |
| Apple FaceTime HD Camera                             | 6         | 0.78%   |
| Acer SunplusIT Integrated Camera                     | 6         | 0.78%   |
| Logitech C922 Pro Stream Webcam                      | 5         | 0.65%   |
| Chicony Integrated Camera (1280x720@30)              | 5         | 0.65%   |
| Chicony HD User Facing                               | 5         | 0.65%   |
| Bison Integrated Camera                              | 5         | 0.65%   |
| Z-Star Venus USB2.0 Camera                           | 4         | 0.52%   |
| Sunplus HP Wide Vision HD                            | 4         | 0.52%   |
| Quanta HD Webcam                                     | 4         | 0.52%   |
| Microdia Laptop_Integrated_Webcam_HD                 | 4         | 0.52%   |
| Microdia Integrated Webcam                           | 4         | 0.52%   |
| MacroSilicon USB Video                               | 4         | 0.52%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 4         | 0.52%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 4         | 0.52%   |
| Logitech C920 PRO HD Webcam                          | 4         | 0.52%   |
| Lite-On TOSHIBA Web Camera - HD                      | 4         | 0.52%   |
| IMC Networks USB2.0 HD IR UVC WebCam                 | 4         | 0.52%   |
| IMC Networks ov9734_azurewave_camera                 | 4         | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 64        | 44.44%  |
| Validity Sensors           | 34        | 23.61%  |
| Shenzhen Goodix Technology | 23        | 15.97%  |
| Elan Microelectronics      | 8         | 5.56%   |
| STMicroelectronics         | 4         | 2.78%   |
| AuthenTec                  | 4         | 2.78%   |
| LighTuning Technology      | 3         | 2.08%   |
| DigitalPersona             | 2         | 1.39%   |
| Upek                       | 1         | 0.69%   |
| Samsung Electronics        | 1         | 0.69%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 24        | 16.67%  |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 15        | 10.42%  |
| Shenzhen Goodix  Fingerprint Device                        | 10        | 6.94%   |
| Validity Sensors VFS495 Fingerprint Reader                 | 8         | 5.56%   |
| Validity Sensors Synaptics WBDI                            | 8         | 5.56%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 7         | 4.86%   |
| Synaptics WBDI                                             | 7         | 4.86%   |
| Shenzhen Goodix Fingerprint Reader                         | 7         | 4.86%   |
| Shenzhen Goodix FingerPrint                                | 6         | 4.17%   |
| Elan ELAN:Fingerprint                                      | 6         | 4.17%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 4         | 2.78%   |
| STMicroelectronics Fingerprint Reader                      | 4         | 2.78%   |
| Validity Sensors VFS5011 Fingerprint Reader                | 3         | 2.08%   |
| Synaptics UWP WBDI Device                                  | 3         | 2.08%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 2.08%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor          | 2         | 1.39%   |
| Validity Sensors VFS491                                    | 2         | 1.39%   |
| Validity Sensors Fingerprint scanner                       | 2         | 1.39%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint   | 2         | 1.39%   |
| LighTuning EgisTec Touch Fingerprint Sensor                | 2         | 1.39%   |
| Elan ELAN:ARM-M4                                           | 2         | 1.39%   |
| DigitalPersona Fingerprint Reader                          | 2         | 1.39%   |
| AuthenTec AES2501 Fingerprint Sensor                       | 2         | 1.39%   |
| Unknown                                                    | 2         | 1.39%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 1         | 0.69%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 1         | 0.69%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 1         | 0.69%   |
| Synaptics WBDI Device                                      | 1         | 0.69%   |
| Synaptics UWP WBDI                                         | 1         | 0.69%   |
| Synaptics  WBDI                                            | 1         | 0.69%   |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 1         | 0.69%   |
| Samsung Fingerprint Sensor Device - 730B                   | 1         | 0.69%   |
| LighTuning ES603 Swipe Fingerprint Sensor                  | 1         | 0.69%   |
| AuthenTec Fingerprint Sensor                               | 1         | 0.69%   |
| AuthenTec AES2550 Fingerprint Sensor                       | 1         | 0.69%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 36        | 34.95%  |
| Alcor Micro                       | 36        | 34.95%  |
| Yubico.com                        | 4         | 3.88%   |
| Upek                              | 4         | 3.88%   |
| SCM Microsystems                  | 4         | 3.88%   |
| Clay Logic                        | 4         | 3.88%   |
| O2 Micro                          | 3         | 2.91%   |
| Gemalto (was Gemplus)             | 2         | 1.94%   |
| Advanced Card Systems             | 2         | 1.94%   |
| VASCO Data Security International | 1         | 0.97%   |
| Purism, SPC                       | 1         | 0.97%   |
| Microchip Technology              | 1         | 0.97%   |
| Hewlett-Packard                   | 1         | 0.97%   |
| Feitian Technologies              | 1         | 0.97%   |
| Bit4id                            | 1         | 0.97%   |
| Aladdin Knowledge Systems         | 1         | 0.97%   |
| Aktiv                             | 1         | 0.97%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 36        | 34.95%  |
| Broadcom 58200                                                               | 13        | 12.62%  |
| Broadcom 5880                                                                | 12        | 11.65%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 6         | 5.83%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 3.88%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 4         | 3.88%   |
| Clay Logic Nitrokey Pro                                                      | 4         | 3.88%   |
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 3.88%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 1.94%   |
| Yubico.com Yubikey 4/5 CCID                                                  | 2         | 1.94%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 1.94%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 1.94%   |
| VASCO Data Security International DIGIPASS 870                               | 1         | 0.97%   |
| Purism, SPC Librem Key                                                       | 1         | 0.97%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.97%   |
| Microchip Technology SMSC USX101x Reader                                     | 1         | 0.97%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.97%   |
| Feitian Technologies U2F CCID KB                                             | 1         | 0.97%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.97%   |
| Bit4id miniLector-s                                                          | 1         | 0.97%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.97%   |
| Aktiv Rutoken lite                                                           | 1         | 0.97%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.97%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.97%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 657       | 43.17%  |
| 1     | 422       | 27.73%  |
| 2     | 211       | 13.86%  |
| 3     | 115       | 7.56%   |
| 4     | 67        | 4.4%    |
| 5     | 29        | 1.91%   |
| 6     | 15        | 0.99%   |
| 7     | 5         | 0.33%   |
| 8     | 1         | 0.07%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 292       | 18.5%   |
| Graphics card            | 208       | 13.18%  |
| Bluetooth                | 196       | 12.42%  |
| Camera                   | 170       | 10.77%  |
| Fingerprint reader       | 142       | 9%      |
| Net/wireless             | 108       | 6.84%   |
| Chipcard                 | 79        | 5.01%   |
| Sound                    | 71        | 4.5%    |
| Card reader              | 71        | 4.5%    |
| Multimedia controller    | 65        | 4.12%   |
| Network                  | 26        | 1.65%   |
| Firewire controller      | 25        | 1.58%   |
| Unassigned class         | 23        | 1.46%   |
| Net/ethernet             | 23        | 1.46%   |
| Modem                    | 20        | 1.27%   |
| Storage/ide              | 16        | 1.01%   |
| Storage/ata              | 13        | 0.82%   |
| Tv card                  | 7         | 0.44%   |
| Storage/raid             | 7         | 0.44%   |
| Storage                  | 6         | 0.38%   |
| Storage/nvme             | 4         | 0.25%   |
| Dvb card                 | 4         | 0.25%   |
| Wireless                 | 1         | 0.06%   |
| Unclassified device      | 1         | 0.06%   |

