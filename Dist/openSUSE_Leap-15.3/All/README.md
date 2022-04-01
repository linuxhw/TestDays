openSUSE Leap-15.3 - Tested Hardware & Statistics
-------------------------------------------------

A project to collect tested hardware configurations for openSUSE Leap-15.3.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/openSUSE_Leap-15.3/Desktop/README.md) and [notebooks](/Dist/openSUSE_Leap-15.3/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

Total: 155

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | H81M-R                      | Desktop     | [6fffff17df](https://linux-hardware.org/?probe=6fffff17df) | Mar 27, 2022 |
| ASUSTek       | H81M-R                      | Desktop     | [0d4d2c1358](https://linux-hardware.org/?probe=0d4d2c1358) | Mar 27, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [4345817b16](https://linux-hardware.org/?probe=4345817b16) | Mar 23, 2022 |
| Lenovo        | 102F SDK0J40697 WIN 3305... | Desktop     | [adce0625d3](https://linux-hardware.org/?probe=adce0625d3) | Mar 20, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [ef43a1dac3](https://linux-hardware.org/?probe=ef43a1dac3) | Mar 20, 2022 |
| ASUSTek       | ZenBook UX325SA_UM325SA     | Notebook    | [05c0be34be](https://linux-hardware.org/?probe=05c0be34be) | Mar 18, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [53ca03e8ec](https://linux-hardware.org/?probe=53ca03e8ec) | Mar 17, 2022 |
| Dell          | Latitude E7470              | Notebook    | [0d9c88498d](https://linux-hardware.org/?probe=0d9c88498d) | Mar 13, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [455f94f1d3](https://linux-hardware.org/?probe=455f94f1d3) | Mar 04, 2022 |
| Lenovo        | ThinkPad E580 20KS001RGE    | Notebook    | [4ccce94591](https://linux-hardware.org/?probe=4ccce94591) | Mar 03, 2022 |
| HP            | 2129                        | Desktop     | [a6b5f98b78](https://linux-hardware.org/?probe=a6b5f98b78) | Mar 02, 2022 |
| Intel         | DG41WV AAE90316-104         | Desktop     | [b6dc38eb16](https://linux-hardware.org/?probe=b6dc38eb16) | Feb 25, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [362c220f2d](https://linux-hardware.org/?probe=362c220f2d) | Feb 20, 2022 |
| MSI           | CX600                       | Notebook    | [bbd815a6e9](https://linux-hardware.org/?probe=bbd815a6e9) | Feb 17, 2022 |
| LG Electro... | C400-G.BC22P1               | Notebook    | [e202260efb](https://linux-hardware.org/?probe=e202260efb) | Feb 14, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [b3ff58ce92](https://linux-hardware.org/?probe=b3ff58ce92) | Feb 06, 2022 |
| ASRock        | Z68 Extreme4 Gen3           | Desktop     | [29ea90b598](https://linux-hardware.org/?probe=29ea90b598) | Feb 06, 2022 |
| Acer          | Nitro AN515-52              | Notebook    | [51a06ffad3](https://linux-hardware.org/?probe=51a06ffad3) | Feb 05, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [2f03547791](https://linux-hardware.org/?probe=2f03547791) | Feb 05, 2022 |
| Acer          | Aspire VN7-792G             | Notebook    | [20e910e73b](https://linux-hardware.org/?probe=20e910e73b) | Feb 05, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [6423454dd8](https://linux-hardware.org/?probe=6423454dd8) | Jan 28, 2022 |
| ASUSTek       | H97M-E                      | Desktop     | [394132a26d](https://linux-hardware.org/?probe=394132a26d) | Jan 22, 2022 |
| ASUSTek       | H97M-E                      | Desktop     | [83e0c18dcb](https://linux-hardware.org/?probe=83e0c18dcb) | Jan 22, 2022 |
| Notebook      | PCx0Dx                      | Notebook    | [07b8344de7](https://linux-hardware.org/?probe=07b8344de7) | Jan 21, 2022 |
| Notebook      | PCx0Dx                      | Notebook    | [3bdae5c5ac](https://linux-hardware.org/?probe=3bdae5c5ac) | Jan 21, 2022 |
| ASUSTek       | H81M-R                      | Desktop     | [ea01dd4007](https://linux-hardware.org/?probe=ea01dd4007) | Jan 18, 2022 |
| ASUSTek       | H81M-R                      | Desktop     | [f65a651e3c](https://linux-hardware.org/?probe=f65a651e3c) | Jan 18, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [88d5bd947a](https://linux-hardware.org/?probe=88d5bd947a) | Jan 17, 2022 |
| ASUSTek       | H81M-R                      | Desktop     | [d8e311c6cc](https://linux-hardware.org/?probe=d8e311c6cc) | Jan 17, 2022 |
| ASUSTek       | H81M-R                      | Desktop     | [cf10bab7ad](https://linux-hardware.org/?probe=cf10bab7ad) | Jan 17, 2022 |
| Biostar       | H77MU3                      | Desktop     | [da779dbb31](https://linux-hardware.org/?probe=da779dbb31) | Jan 15, 2022 |
| ASUSTek       | H97M-E                      | Desktop     | [abf3b9c5c8](https://linux-hardware.org/?probe=abf3b9c5c8) | Jan 14, 2022 |
| ASUSTek       | H97M-E                      | Desktop     | [54fb155ee1](https://linux-hardware.org/?probe=54fb155ee1) | Jan 14, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [894589da9f](https://linux-hardware.org/?probe=894589da9f) | Jan 11, 2022 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [cda49a0b67](https://linux-hardware.org/?probe=cda49a0b67) | Jan 10, 2022 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [4c9489e27a](https://linux-hardware.org/?probe=4c9489e27a) | Jan 10, 2022 |
| HP            | ProBook x360 11 G5 EE       | Convertible | [2000988c8b](https://linux-hardware.org/?probe=2000988c8b) | Jan 10, 2022 |
| HP            | 2B29                        | Desktop     | [cfb166f99c](https://linux-hardware.org/?probe=cfb166f99c) | Jan 10, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [980348cf8f](https://linux-hardware.org/?probe=980348cf8f) | Jan 09, 2022 |
| ASUSTek       | Z97-K                       | Desktop     | [87ffc81034](https://linux-hardware.org/?probe=87ffc81034) | Jan 08, 2022 |
| Toshiba       | AS 1301                     | Notebook    | [8617f80de9](https://linux-hardware.org/?probe=8617f80de9) | Jan 01, 2022 |
| Dell          | 0RY007                      | Desktop     | [d51d13fdd1](https://linux-hardware.org/?probe=d51d13fdd1) | Dec 31, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [559c6e472e](https://linux-hardware.org/?probe=559c6e472e) | Dec 30, 2021 |
| Dell          | XPS 15 9510                 | Notebook    | [5f594735cc](https://linux-hardware.org/?probe=5f594735cc) | Dec 28, 2021 |
| Lenovo        | ThinkPad L512 44444WG       | Notebook    | [113b39ddbc](https://linux-hardware.org/?probe=113b39ddbc) | Dec 25, 2021 |
| Acer          | Aspire E1-571               | Notebook    | [8b94542162](https://linux-hardware.org/?probe=8b94542162) | Dec 22, 2021 |
| Acer          | Aspire E1-571               | Notebook    | [842eae5b1d](https://linux-hardware.org/?probe=842eae5b1d) | Dec 22, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [6f6aeab7c1](https://linux-hardware.org/?probe=6f6aeab7c1) | Dec 20, 2021 |
| Dell          | Inspiron N4030              | Notebook    | [f5b5166d80](https://linux-hardware.org/?probe=f5b5166d80) | Dec 20, 2021 |
| ASUSTek       | PRIME A320M-E               | Desktop     | [c008e360e7](https://linux-hardware.org/?probe=c008e360e7) | Dec 19, 2021 |
| ASUSTek       | P9X79 PRO                   | Desktop     | [ca4a106ccf](https://linux-hardware.org/?probe=ca4a106ccf) | Dec 18, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [1ff9d84c5f](https://linux-hardware.org/?probe=1ff9d84c5f) | Dec 17, 2021 |
| Acer          | Aspire E1-571               | Notebook    | [27923678bd](https://linux-hardware.org/?probe=27923678bd) | Dec 16, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [a5ddb2410e](https://linux-hardware.org/?probe=a5ddb2410e) | Dec 16, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [e744dbe03d](https://linux-hardware.org/?probe=e744dbe03d) | Dec 15, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [ecc22ad350](https://linux-hardware.org/?probe=ecc22ad350) | Dec 12, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [dab30215a2](https://linux-hardware.org/?probe=dab30215a2) | Dec 05, 2021 |
| ASRock        | Z68 Extreme4 Gen3           | Desktop     | [00a3ad4abc](https://linux-hardware.org/?probe=00a3ad4abc) | Dec 02, 2021 |
| ASRock        | Z68 Extreme4 Gen3           | Desktop     | [e75c56906a](https://linux-hardware.org/?probe=e75c56906a) | Dec 01, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [34898be259](https://linux-hardware.org/?probe=34898be259) | Nov 28, 2021 |
| Lenovo        | ThinkPad T490s 20NYS1XK0... | Notebook    | [aef7318ff6](https://linux-hardware.org/?probe=aef7318ff6) | Nov 27, 2021 |
| Acer          | Aspire E1-772G              | Notebook    | [d49a3f3160](https://linux-hardware.org/?probe=d49a3f3160) | Nov 26, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [a2761e06a4](https://linux-hardware.org/?probe=a2761e06a4) | Nov 24, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [5bfec76970](https://linux-hardware.org/?probe=5bfec76970) | Nov 24, 2021 |
| Lenovo        | G50-45 80E3                 | Notebook    | [43f110e082](https://linux-hardware.org/?probe=43f110e082) | Nov 20, 2021 |
| Dell          | 03015M A09                  | Server      | [c685a0033b](https://linux-hardware.org/?probe=c685a0033b) | Nov 17, 2021 |
| MSI           | H510I PRO WIFI              | Desktop     | [d50547de1f](https://linux-hardware.org/?probe=d50547de1f) | Nov 15, 2021 |
| ASRock        | N68C-GS4 FX                 | Desktop     | [c863f2ca43](https://linux-hardware.org/?probe=c863f2ca43) | Nov 14, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [7d1fd58f75](https://linux-hardware.org/?probe=7d1fd58f75) | Nov 14, 2021 |
| HP            | 844C                        | Desktop     | [2d709598d7](https://linux-hardware.org/?probe=2d709598d7) | Nov 12, 2021 |
| ASUSTek       | M4A78T-E                    | Desktop     | [10991ab539](https://linux-hardware.org/?probe=10991ab539) | Nov 10, 2021 |
| Acer          | Aspire E1-772G              | Notebook    | [ec97cd08d4](https://linux-hardware.org/?probe=ec97cd08d4) | Nov 09, 2021 |
| Acer          | Aspire E1-772G              | Notebook    | [be0c106296](https://linux-hardware.org/?probe=be0c106296) | Nov 09, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | Notebook    | [9a632ea5d1](https://linux-hardware.org/?probe=9a632ea5d1) | Nov 08, 2021 |
| Acer          | Aspire 5820TG               | Notebook    | [d8ae1a4109](https://linux-hardware.org/?probe=d8ae1a4109) | Nov 03, 2021 |
| Acer          | Aspire 5820TG               | Notebook    | [c79617751e](https://linux-hardware.org/?probe=c79617751e) | Nov 03, 2021 |
| Dell          | 0M859N A00                  | Desktop     | [aadca45789](https://linux-hardware.org/?probe=aadca45789) | Nov 01, 2021 |
| Acer          | Aspire E1-772G              | Notebook    | [2ffccc532e](https://linux-hardware.org/?probe=2ffccc532e) | Oct 24, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [b6be115eec](https://linux-hardware.org/?probe=b6be115eec) | Oct 23, 2021 |
| Acer          | Aspire 5560                 | Notebook    | [39fd26f895](https://linux-hardware.org/?probe=39fd26f895) | Oct 22, 2021 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [627c62ae00](https://linux-hardware.org/?probe=627c62ae00) | Oct 21, 2021 |
| Dell          | 0Y2YM6 A00                  | Desktop     | [d9a12dc22c](https://linux-hardware.org/?probe=d9a12dc22c) | Oct 19, 2021 |
| Dell          | 0Y2YM6 A00                  | Desktop     | [34a55551e2](https://linux-hardware.org/?probe=34a55551e2) | Oct 19, 2021 |
| Medion        | E6436 MD61150               | Notebook    | [1edd4700fd](https://linux-hardware.org/?probe=1edd4700fd) | Oct 17, 2021 |
| Medion        | E6436 MD61150               | Notebook    | [2eaa34b93e](https://linux-hardware.org/?probe=2eaa34b93e) | Oct 17, 2021 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [fc4da04b79](https://linux-hardware.org/?probe=fc4da04b79) | Oct 16, 2021 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [ae1811a242](https://linux-hardware.org/?probe=ae1811a242) | Oct 13, 2021 |
| Lenovo        | ThinkPad T490s 20NYS1XK0... | Notebook    | [d3700d8667](https://linux-hardware.org/?probe=d3700d8667) | Oct 13, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U4S... | Notebook    | [3bb6121afa](https://linux-hardware.org/?probe=3bb6121afa) | Oct 13, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [f3c6229102](https://linux-hardware.org/?probe=f3c6229102) | Oct 06, 2021 |
| Lenovo        | 364A SDK0J40700 WIN 3258... | Desktop     | [ce4776505f](https://linux-hardware.org/?probe=ce4776505f) | Oct 03, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [556c37ba9b](https://linux-hardware.org/?probe=556c37ba9b) | Oct 03, 2021 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [ad69186227](https://linux-hardware.org/?probe=ad69186227) | Oct 02, 2021 |
| ASRock        | Z68 Extreme4 Gen3           | Desktop     | [3cec37b610](https://linux-hardware.org/?probe=3cec37b610) | Oct 02, 2021 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [540dca7da7](https://linux-hardware.org/?probe=540dca7da7) | Oct 02, 2021 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | Notebook    | [390b9a8a74](https://linux-hardware.org/?probe=390b9a8a74) | Oct 01, 2021 |
| MSI           | GP63 Leopard 8RD            | Notebook    | [21189bb3e0](https://linux-hardware.org/?probe=21189bb3e0) | Oct 01, 2021 |
| ASUSTek       | M4A78T-E                    | Desktop     | [01ec64f498](https://linux-hardware.org/?probe=01ec64f498) | Sep 24, 2021 |
| Lenovo        | 364A SDK0J40700 WIN 3258... | Desktop     | [58f9ca6247](https://linux-hardware.org/?probe=58f9ca6247) | Sep 22, 2021 |
| Lenovo        | 364A SDK0J40700 WIN 3258... | Desktop     | [db9ccd461b](https://linux-hardware.org/?probe=db9ccd461b) | Sep 22, 2021 |
| Dell          | Precision M6700             | Notebook    | [0d8cf3bf1c](https://linux-hardware.org/?probe=0d8cf3bf1c) | Sep 21, 2021 |
| VS Company    | G31T-M                      | Desktop     | [ed8bb8c0d1](https://linux-hardware.org/?probe=ed8bb8c0d1) | Sep 21, 2021 |
| ASUSTek       | AM1M-A/BR                   | Desktop     | [c586c22b15](https://linux-hardware.org/?probe=c586c22b15) | Sep 20, 2021 |
| Alienware     | 0PGRP5 A02                  | Desktop     | [65615a3aaa](https://linux-hardware.org/?probe=65615a3aaa) | Sep 16, 2021 |
| Alienware     | 0PGRP5 A02                  | Desktop     | [158a015f26](https://linux-hardware.org/?probe=158a015f26) | Sep 15, 2021 |
| MSI           | X370 GAMING PRO             | Desktop     | [629a45e23d](https://linux-hardware.org/?probe=629a45e23d) | Sep 12, 2021 |
| HP            | 8056                        | Desktop     | [3cab8505c4](https://linux-hardware.org/?probe=3cab8505c4) | Sep 06, 2021 |
| Intel         | DG41WV AAE90316-104         | Desktop     | [27c162218f](https://linux-hardware.org/?probe=27c162218f) | Sep 05, 2021 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [be3b65a81d](https://linux-hardware.org/?probe=be3b65a81d) | Aug 29, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [44d0412dd3](https://linux-hardware.org/?probe=44d0412dd3) | Aug 27, 2021 |
| Samsung       | 600B4B/600B5B               | Notebook    | [200275bbd6](https://linux-hardware.org/?probe=200275bbd6) | Aug 27, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [a13b05f65f](https://linux-hardware.org/?probe=a13b05f65f) | Aug 27, 2021 |
| Dell          | Precision M6700             | Notebook    | [191db00b83](https://linux-hardware.org/?probe=191db00b83) | Aug 26, 2021 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [4b5a1af4dd](https://linux-hardware.org/?probe=4b5a1af4dd) | Aug 26, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [73a5085a79](https://linux-hardware.org/?probe=73a5085a79) | Aug 24, 2021 |
| Dell          | Latitude 5480               | Notebook    | [a2110d9601](https://linux-hardware.org/?probe=a2110d9601) | Aug 24, 2021 |
| Dell          | Latitude 5480               | Notebook    | [64e1f3e16c](https://linux-hardware.org/?probe=64e1f3e16c) | Aug 19, 2021 |
| Lenovo        | ThinkPad T61 8895W9U        | Notebook    | [424c5f3e75](https://linux-hardware.org/?probe=424c5f3e75) | Aug 19, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [c68ce33d52](https://linux-hardware.org/?probe=c68ce33d52) | Aug 11, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [9a422a10d3](https://linux-hardware.org/?probe=9a422a10d3) | Aug 11, 2021 |
| Dell          | Inspiron 7460               | Notebook    | [f954aa3826](https://linux-hardware.org/?probe=f954aa3826) | Aug 10, 2021 |
| Samsung       | 600B4B/600B5B               | Notebook    | [0a650b495e](https://linux-hardware.org/?probe=0a650b495e) | Aug 09, 2021 |
| Lenovo        | ThinkPad T460 20FMS75800    | Notebook    | [1a1c3f469d](https://linux-hardware.org/?probe=1a1c3f469d) | Aug 07, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [5953bc46ad](https://linux-hardware.org/?probe=5953bc46ad) | Aug 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [fafaeed466](https://linux-hardware.org/?probe=fafaeed466) | Aug 06, 2021 |
| ASUSTek       | PRIME H310M-A               | Desktop     | [a22aa3c48c](https://linux-hardware.org/?probe=a22aa3c48c) | Aug 01, 2021 |
| MSI           | B85M-E45                    | Desktop     | [0e20d4cea9](https://linux-hardware.org/?probe=0e20d4cea9) | Jul 30, 2021 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [acbcbe74d7](https://linux-hardware.org/?probe=acbcbe74d7) | Jul 22, 2021 |
| HP            | Stream Notebook PC 11       | Notebook    | [a612aa5d15](https://linux-hardware.org/?probe=a612aa5d15) | Jul 20, 2021 |
| HP            | 8433 11                     | Desktop     | [b079ccb608](https://linux-hardware.org/?probe=b079ccb608) | Jul 15, 2021 |
| MSI           | D2415 S26361-D2415-A21      | Desktop     | [b49400f636](https://linux-hardware.org/?probe=b49400f636) | Jul 11, 2021 |
| Lenovo        | ThinkPad T450s 20BWA06J0... | Notebook    | [e4cd39ef75](https://linux-hardware.org/?probe=e4cd39ef75) | Jul 09, 2021 |
| Lenovo        | ThinkPad T450s 20BWA06J0... | Notebook    | [5565f4e4fe](https://linux-hardware.org/?probe=5565f4e4fe) | Jul 09, 2021 |
| Fujitsu       | LIFEBOOK E754               | Notebook    | [e7923c27f1](https://linux-hardware.org/?probe=e7923c27f1) | Jul 08, 2021 |
| MSI           | B350 TOMAHAWK               | Desktop     | [27a6ac997b](https://linux-hardware.org/?probe=27a6ac997b) | Jul 03, 2021 |
| ASRock        | X570M Pro4                  | Desktop     | [a00aea4331](https://linux-hardware.org/?probe=a00aea4331) | Jul 03, 2021 |
| HP            | 0A68h                       | Desktop     | [36cfa6a366](https://linux-hardware.org/?probe=36cfa6a366) | Jun 27, 2021 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [dfc2f82575](https://linux-hardware.org/?probe=dfc2f82575) | Jun 26, 2021 |
| ASUSTek       | G771JW                      | Notebook    | [8e6c4ddee8](https://linux-hardware.org/?probe=8e6c4ddee8) | Jun 24, 2021 |
| ASRock        | X570 Steel Legend           | Desktop     | [b4a11b3e4e](https://linux-hardware.org/?probe=b4a11b3e4e) | Jun 17, 2021 |
| MSI           | MEG X570 GODLIKE            | Desktop     | [11b7f0e8ae](https://linux-hardware.org/?probe=11b7f0e8ae) | Jun 17, 2021 |
| HP            | ZBook 17 G2                 | Notebook    | [3342d4d378](https://linux-hardware.org/?probe=3342d4d378) | Jun 17, 2021 |
| HP            | OMEN by HP Laptop 15-dc1... | Notebook    | [0c01b21401](https://linux-hardware.org/?probe=0c01b21401) | Jun 15, 2021 |
| Sony          | VPCSB15GB                   | Notebook    | [43a9d38ca0](https://linux-hardware.org/?probe=43a9d38ca0) | Jun 03, 2021 |
| HP            | 2AA2                        | Desktop     | [65e7cd2d3e](https://linux-hardware.org/?probe=65e7cd2d3e) | Jun 02, 2021 |
| Sony          | VGN-Z570AN                  | Notebook    | [13d58b8d90](https://linux-hardware.org/?probe=13d58b8d90) | May 21, 2021 |
| Sony          | VGN-Z570AN                  | Notebook    | [e6c7882e05](https://linux-hardware.org/?probe=e6c7882e05) | May 21, 2021 |
| MSI           | GS60 6QE                    | Notebook    | [93c6fd8911](https://linux-hardware.org/?probe=93c6fd8911) | May 18, 2021 |
| MSI           | GS60 6QE                    | Notebook    | [41fe777475](https://linux-hardware.org/?probe=41fe777475) | May 18, 2021 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [184bedf2fd](https://linux-hardware.org/?probe=184bedf2fd) | May 01, 2021 |
| HP            | Pavilion dx6500             | Notebook    | [091cc2c616](https://linux-hardware.org/?probe=091cc2c616) | Apr 13, 2021 |
| HP            | Pavilion dx6500             | Notebook    | [6ad0d5c87f](https://linux-hardware.org/?probe=6ad0d5c87f) | Apr 13, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [97a7246099](https://linux-hardware.org/?probe=97a7246099) | Mar 01, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [b1e186207c](https://linux-hardware.org/?probe=b1e186207c) | Feb 28, 2021 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [fca0fd3336](https://linux-hardware.org/?probe=fca0fd3336) | Jan 03, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Computers | Percent |
|-------------------------------------|-----------|---------|
| 5.3.18-59.37-default                | 18        | 16.51%  |
| 5.3.18-59.27-default                | 13        | 11.93%  |
| 5.3.18-59.19-default                | 13        | 11.93%  |
| 5.3.18-57-default                   | 8         | 7.34%   |
| 5.3.18-59.5-default                 | 6         | 5.5%    |
| 5.3.18-59.24-default                | 6         | 5.5%    |
| 5.3.18-59.16-default                | 6         | 5.5%    |
| 5.3.18-59.10-default                | 5         | 4.59%   |
| 5.3.18-150300.59.54-default         | 5         | 4.59%   |
| 5.3.18-150300.59.49-default         | 5         | 4.59%   |
| 5.3.18-59.34-default                | 4         | 3.67%   |
| 5.3.18-150300.59.43-default         | 3         | 2.75%   |
| 5.3.18-59.19-preempt                | 2         | 1.83%   |
| 5.3.18-59.13-default                | 2         | 1.83%   |
| 5.3.18-lp152.57-default             | 1         | 0.92%   |
| 5.3.18-59.37-preempt                | 1         | 0.92%   |
| 5.3.18-59.34-preempt                | 1         | 0.92%   |
| 5.3.18-59.27-preempt                | 1         | 0.92%   |
| 5.3.18-59.24-preempt                | 1         | 0.92%   |
| 5.3.18-57-preempt                   | 1         | 0.92%   |
| 5.3.18-56-default                   | 1         | 0.92%   |
| 5.3.18-52-default                   | 1         | 0.92%   |
| 5.3.18-46-default                   | 1         | 0.92%   |
| 5.3.18-150300.59.49-preempt         | 1         | 0.92%   |
| 5.16.0-rc2-lp153.2.g696d453-default | 1         | 0.92%   |
| 5.15.11-lp153.3.g730a488-default    | 1         | 0.92%   |
| 4.12.14-197.105-vanilla             | 1         | 0.92%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.3.18  | 98        | 97.03%  |
| 5.16.0  | 1         | 0.99%   |
| 5.15.11 | 1         | 0.99%   |
| 4.12.14 | 1         | 0.99%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.3     | 98        | 97.03%  |
| 5.16    | 1         | 0.99%   |
| 5.15    | 1         | 0.99%   |
| 4.12    | 1         | 0.99%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 101       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| KDE5       | 44        | 41.9%   |
| KDE        | 17        | 16.19%  |
| GNOME      | 16        | 15.24%  |
| Unknown    | 14        | 13.33%  |
| XFCE       | 10        | 9.52%   |
| X-Cinnamon | 3         | 2.86%   |
| MATE       | 1         | 0.95%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 83        | 81.37%  |
| Wayland | 12        | 11.76%  |
| Tty     | 7         | 6.86%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 53        | 51.46%  |
| SDDM    | 22        | 21.36%  |
| LightDM | 22        | 21.36%  |
| XDM     | 5         | 4.85%   |
| GDM     | 1         | 0.97%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 28        | 27.72%  |
| de_DE   | 23        | 22.77%  |
| POSIX   | 11        | 10.89%  |
| pt_BR   | 6         | 5.94%   |
| ru_RU   | 4         | 3.96%   |
| es_ES   | 4         | 3.96%   |
| fr_FR   | 3         | 2.97%   |
| Unknown | 3         | 2.97%   |
| en_GB   | 2         | 1.98%   |
| zh_CN   | 1         | 0.99%   |
| tr_TR   | 1         | 0.99%   |
| sv_SE   | 1         | 0.99%   |
| sk_SK   | 1         | 0.99%   |
| pt_PT   | 1         | 0.99%   |
| pl_PL   | 1         | 0.99%   |
| nl_NL   | 1         | 0.99%   |
| nl_BE   | 1         | 0.99%   |
| it_IT   | 1         | 0.99%   |
| hu_HU   | 1         | 0.99%   |
| hr_HR   | 1         | 0.99%   |
| fi_FI   | 1         | 0.99%   |
| es_MX   | 1         | 0.99%   |
| en_DE   | 1         | 0.99%   |
| en_AU   | 1         | 0.99%   |
| cs_CZ   | 1         | 0.99%   |
| ca_AD   | 1         | 0.99%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 57        | 55.88%  |
| EFI  | 45        | 44.12%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 69        | 67.65%  |
| Ext4    | 28        | 27.45%  |
| Xfs     | 4         | 3.92%   |
| Overlay | 1         | 0.98%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 51        | 49.51%  |
| Unknown | 44        | 42.72%  |
| MBR     | 8         | 7.77%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 90        | 87.38%  |
| Yes       | 13        | 12.62%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 67        | 66.34%  |
| Yes       | 34        | 33.66%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 18        | 17.82%  |
| Lenovo              | 15        | 14.85%  |
| Hewlett-Packard     | 14        | 13.86%  |
| MSI                 | 12        | 11.88%  |
| Dell                | 11        | 10.89%  |
| Acer                | 7         | 6.93%   |
| Gigabyte Technology | 6         | 5.94%   |
| ASRock              | 5         | 4.95%   |
| Sony                | 2         | 1.98%   |
| Fujitsu             | 2         | 1.98%   |
| VS Company          | 1         | 0.99%   |
| TUXEDO              | 1         | 0.99%   |
| Semp Toshiba        | 1         | 0.99%   |
| Samsung Electronics | 1         | 0.99%   |
| Medion              | 1         | 0.99%   |
| Intel               | 1         | 0.99%   |
| HUAWEI              | 1         | 0.99%   |
| Biostar             | 1         | 0.99%   |
| Alienware           | 1         | 0.99%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                         | Computers | Percent |
|----------------------------------------------|-----------|---------|
| ASUS All Series                              | 3         | 2.97%   |
| VS Company G31T-M                            | 1         | 0.99%   |
| TUXEDO Aura 15 Gen1                          | 1         | 0.99%   |
| Sony VPCSB15GB                               | 1         | 0.99%   |
| Sony VGN-Z570AN                              | 1         | 0.99%   |
| Semp Toshiba AS 1301                         | 1         | 0.99%   |
| Samsung 600B4B/600B5B                        | 1         | 0.99%   |
| MSI MS-7D16                                  | 1         | 0.99%   |
| MSI MS-7C34                                  | 1         | 0.99%   |
| MSI MS-7C02                                  | 1         | 0.99%   |
| MSI MS-7B89                                  | 1         | 0.99%   |
| MSI MS-7A38                                  | 1         | 0.99%   |
| MSI MS-7A34                                  | 1         | 0.99%   |
| MSI MS-7A33                                  | 1         | 0.99%   |
| MSI MS-7817                                  | 1         | 0.99%   |
| MSI GS60 6QE                                 | 1         | 0.99%   |
| MSI GP63 Leopard 8RD                         | 1         | 0.99%   |
| MSI ESPRIMO P1510                            | 1         | 0.99%   |
| MSI CX600                                    | 1         | 0.99%   |
| Medion E6436 MD61150                         | 1         | 0.99%   |
| Lenovo V330-15IKB 81AX                       | 1         | 0.99%   |
| Lenovo ThinkStation P500 30A6S4JU00          | 1         | 0.99%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XW00A7TH   | 1         | 0.99%   |
| Lenovo ThinkPad X1 Carbon 4th 20FB002UMC     | 1         | 0.99%   |
| Lenovo ThinkPad T61 8895W9U                  | 1         | 0.99%   |
| Lenovo ThinkPad T490s 20NYS1XK00             | 1         | 0.99%   |
| Lenovo ThinkPad T460 20FMS75800              | 1         | 0.99%   |
| Lenovo ThinkPad T450s 20BWA06J00             | 1         | 0.99%   |
| Lenovo ThinkPad T14 Gen 1 20UES47F00         | 1         | 0.99%   |
| Lenovo ThinkPad L15 Gen 1 20U4S88000         | 1         | 0.99%   |
| Lenovo ThinkPad E580 20KS001RGE              | 1         | 0.99%   |
| Lenovo IdeaPad 330-15IKB 81DC                | 1         | 0.99%   |
| Lenovo IdeaCentre Y710 Cube-15ISH 90FL004WGE | 1         | 0.99%   |
| Lenovo G500 20236                            | 1         | 0.99%   |
| Lenovo G50-45 80E3                           | 1         | 0.99%   |
| Intel DG41WV AAE90316-104                    | 1         | 0.99%   |
| HUAWEI KLVL-WXX9                             | 1         | 0.99%   |
| HP ZBook 17 G2                               | 1         | 0.99%   |
| HP Z840 Workstation                          | 1         | 0.99%   |
| HP xw4400 Workstation                        | 1         | 0.99%   |
| HP Stream Notebook PC 11                     | 1         | 0.99%   |
| HP ProBook x360 11 G5 EE                     | 1         | 0.99%   |
| HP Pavilion Gaming Desktop 790-00xx          | 1         | 0.99%   |
| HP Pavilion Gaming Desktop 690-00xx          | 1         | 0.99%   |
| HP Pavilion dx6500                           | 1         | 0.99%   |
| HP OMEN by HP Laptop 15-dc1xxx               | 1         | 0.99%   |
| HP Laptop 17-ca1xxx                          | 1         | 0.99%   |
| HP Laptop 15s-eq0xxx                         | 1         | 0.99%   |
| HP EliteDesk 800 G2 DM 65W                   | 1         | 0.99%   |
| HP 550-a114                                  | 1         | 0.99%   |
| HP 200-5120br                                | 1         | 0.99%   |
| Gigabyte GA-770TA-UD3                        | 1         | 0.99%   |
| Gigabyte G31M-ES2C                           | 1         | 0.99%   |
| Gigabyte F2A68HM-DS2                         | 1         | 0.99%   |
| Gigabyte B75M-D3H                            | 1         | 0.99%   |
| Gigabyte B550 AORUS PRO AC                   | 1         | 0.99%   |
| Gigabyte B250M-DS3H                          | 1         | 0.99%   |
| Fujitsu LIFEBOOK E754                        | 1         | 0.99%   |
| Fujitsu ESPRIMO P520                         | 1         | 0.99%   |
| Dell XPS 15 9510                             | 1         | 0.99%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 9         | 8.91%   |
| Dell Inspiron         | 5         | 4.95%   |
| Acer Aspire           | 5         | 4.95%   |
| HP Pavilion           | 3         | 2.97%   |
| ASUS All              | 3         | 2.97%   |
| HP Laptop             | 2         | 1.98%   |
| Dell Latitude         | 2         | 1.98%   |
| ASUS TUF              | 2         | 1.98%   |
| ASUS ROG              | 2         | 1.98%   |
| ASUS PRIME            | 2         | 1.98%   |
| Acer Nitro            | 2         | 1.98%   |
| VS Company G31T-M     | 1         | 0.99%   |
| TUXEDO Aura           | 1         | 0.99%   |
| Sony VPCSB15GB        | 1         | 0.99%   |
| Sony VGN-Z570AN       | 1         | 0.99%   |
| Semp Toshiba AS       | 1         | 0.99%   |
| Samsung 600B4B        | 1         | 0.99%   |
| MSI MS-7D16           | 1         | 0.99%   |
| MSI MS-7C34           | 1         | 0.99%   |
| MSI MS-7C02           | 1         | 0.99%   |
| MSI MS-7B89           | 1         | 0.99%   |
| MSI MS-7A38           | 1         | 0.99%   |
| MSI MS-7A34           | 1         | 0.99%   |
| MSI MS-7A33           | 1         | 0.99%   |
| MSI MS-7817           | 1         | 0.99%   |
| MSI GS60              | 1         | 0.99%   |
| MSI GP63              | 1         | 0.99%   |
| MSI ESPRIMO           | 1         | 0.99%   |
| MSI CX600             | 1         | 0.99%   |
| Medion E6436          | 1         | 0.99%   |
| Lenovo V330-15IKB     | 1         | 0.99%   |
| Lenovo ThinkStation   | 1         | 0.99%   |
| Lenovo IdeaPad        | 1         | 0.99%   |
| Lenovo IdeaCentre     | 1         | 0.99%   |
| Lenovo G500           | 1         | 0.99%   |
| Lenovo G50-45         | 1         | 0.99%   |
| Intel DG41WV          | 1         | 0.99%   |
| HUAWEI KLVL-WXX9      | 1         | 0.99%   |
| HP ZBook              | 1         | 0.99%   |
| HP Z840               | 1         | 0.99%   |
| HP xw4400             | 1         | 0.99%   |
| HP Stream             | 1         | 0.99%   |
| HP ProBook            | 1         | 0.99%   |
| HP OMEN               | 1         | 0.99%   |
| HP EliteDesk          | 1         | 0.99%   |
| HP 550-a114           | 1         | 0.99%   |
| HP 200-5120br         | 1         | 0.99%   |
| Gigabyte GA-770TA-UD3 | 1         | 0.99%   |
| Gigabyte G31M-ES2C    | 1         | 0.99%   |
| Gigabyte F2A68HM-DS2  | 1         | 0.99%   |
| Gigabyte B75M-D3H     | 1         | 0.99%   |
| Gigabyte B550         | 1         | 0.99%   |
| Gigabyte B250M-DS3H   | 1         | 0.99%   |
| Fujitsu LIFEBOOK      | 1         | 0.99%   |
| Fujitsu ESPRIMO       | 1         | 0.99%   |
| Dell XPS              | 1         | 0.99%   |
| Dell Vostro           | 1         | 0.99%   |
| Dell Precision        | 1         | 0.99%   |
| Dell PowerEdge        | 1         | 0.99%   |
| Biostar H77MU3        | 1         | 0.99%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 14        | 13.86%  |
| 2018 | 11        | 10.89%  |
| 2014 | 10        | 9.9%    |
| 2012 | 10        | 9.9%    |
| 2021 | 7         | 6.93%   |
| 2020 | 7         | 6.93%   |
| 2017 | 7         | 6.93%   |
| 2015 | 7         | 6.93%   |
| 2016 | 5         | 4.95%   |
| 2010 | 5         | 4.95%   |
| 2013 | 4         | 3.96%   |
| 2011 | 4         | 3.96%   |
| 2009 | 4         | 3.96%   |
| 2007 | 3         | 2.97%   |
| 2008 | 2         | 1.98%   |
| 2006 | 1         | 0.99%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Desktop     | 51        | 50.5%   |
| Notebook    | 48        | 47.52%  |
| Convertible | 1         | 0.99%   |
| Server      | 1         | 0.99%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 90        | 89.11%  |
| Enabled  | 11        | 10.89%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 101       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 28        | 27.72%  |
| 8.01-16.0   | 19        | 18.81%  |
| 4.01-8.0    | 17        | 16.83%  |
| 3.01-4.0    | 15        | 14.85%  |
| 32.01-64.0  | 9         | 8.91%   |
| 64.01-256.0 | 9         | 8.91%   |
| 1.01-2.0    | 2         | 1.98%   |
| 24.01-32.0  | 1         | 0.99%   |
| 2.01-3.0    | 1         | 0.99%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 31        | 29.52%  |
| 2.01-3.0   | 29        | 27.62%  |
| 4.01-8.0   | 23        | 21.9%   |
| 3.01-4.0   | 13        | 12.38%  |
| 8.01-16.0  | 4         | 3.81%   |
| 0.51-1.0   | 4         | 3.81%   |
| 32.01-64.0 | 1         | 0.95%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 42        | 41.58%  |
| 2      | 37        | 36.63%  |
| 3      | 10        | 9.9%    |
| 4      | 6         | 5.94%   |
| 6      | 3         | 2.97%   |
| 9      | 1         | 0.99%   |
| 7      | 1         | 0.99%   |
| 5      | 1         | 0.99%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 52        | 51.49%  |
| Yes       | 49        | 48.51%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 94        | 93.07%  |
| No        | 7         | 6.93%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 79        | 77.45%  |
| No        | 23        | 22.55%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 63        | 61.17%  |
| No        | 40        | 38.83%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Germany     | 25        | 24.51%  |
| USA         | 12        | 11.76%  |
| Brazil      | 11        | 10.78%  |
| Russia      | 5         | 4.9%    |
| France      | 4         | 3.92%   |
| Spain       | 3         | 2.94%   |
| Netherlands | 3         | 2.94%   |
| Mexico      | 3         | 2.94%   |
| India       | 3         | 2.94%   |
| Australia   | 3         | 2.94%   |
| Slovakia    | 2         | 1.96%   |
| Nicaragua   | 2         | 1.96%   |
| Japan       | 2         | 1.96%   |
| Hungary     | 2         | 1.96%   |
| Greece      | 2         | 1.96%   |
| Czechia     | 2         | 1.96%   |
| Belgium     | 2         | 1.96%   |
| Turkey      | 1         | 0.98%   |
| Thailand    | 1         | 0.98%   |
| Sweden      | 1         | 0.98%   |
| Sudan       | 1         | 0.98%   |
| Romania     | 1         | 0.98%   |
| Portugal    | 1         | 0.98%   |
| Poland      | 1         | 0.98%   |
| Peru        | 1         | 0.98%   |
| Luxembourg  | 1         | 0.98%   |
| Italy       | 1         | 0.98%   |
| Finland     | 1         | 0.98%   |
| Croatia     | 1         | 0.98%   |
| China       | 1         | 0.98%   |
| Canada      | 1         | 0.98%   |
| Austria     | 1         | 0.98%   |
| Andorra     | 1         | 0.98%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Computers | Percent |
|-------------------------|-----------|---------|
| Sao Paulo               | 4         | 3.85%   |
| Voerde                  | 2         | 1.92%   |
| Tokyo                   | 2         | 1.92%   |
| Prague                  | 2         | 1.92%   |
| Managua                 | 2         | 1.92%   |
| Kiel                    | 2         | 1.92%   |
| ChapecÃ³              | 2         | 1.92%   |
| Berlin                  | 2         | 1.92%   |
| Zagreb                  | 1         | 0.96%   |
| Vijayawada              | 1         | 0.96%   |
| Vienna                  | 1         | 0.96%   |
| Vaennaesby              | 1         | 0.96%   |
| TrГЄs Lagoas          | 1         | 0.96%   |
| The Hague               | 1         | 0.96%   |
| Texarkana               | 1         | 0.96%   |
| Teresina                | 1         | 0.96%   |
| Tacna                   | 1         | 0.96%   |
| Sydney                  | 1         | 0.96%   |
| Stupava                 | 1         | 0.96%   |
| Stabroek                | 1         | 0.96%   |
| Sehnde                  | 1         | 0.96%   |
| Sartrouville            | 1         | 0.96%   |
| San Luis PotosÃ­ City | 1         | 0.96%   |
| Saint Albans            | 1         | 0.96%   |
| Saalfeld                | 1         | 0.96%   |
| Rockville               | 1         | 0.96%   |
| Rio de Janeiro          | 1         | 0.96%   |
| Recife                  | 1         | 0.96%   |
| Prosper                 | 1         | 0.96%   |
| Pringy                  | 1         | 0.96%   |
| Petrozavodsk            | 1         | 0.96%   |
| Palanpur                | 1         | 0.96%   |
| Oulu                    | 1         | 0.96%   |
| Oregon                  | 1         | 0.96%   |
| Odintsovo               | 1         | 0.96%   |
| Nuremberg               | 1         | 0.96%   |
| Nordenham               | 1         | 0.96%   |
| Munich                  | 1         | 0.96%   |
| Moscow                  | 1         | 0.96%   |
| Monterrey               | 1         | 0.96%   |
| Moelan-sur-Mer          | 1         | 0.96%   |
| Miami                   | 1         | 0.96%   |
| Melbourne               | 1         | 0.96%   |
| McDonough               | 1         | 0.96%   |
| Mansfield               | 1         | 0.96%   |
| Madrid                  | 1         | 0.96%   |
| Luxembourg              | 1         | 0.96%   |
| Lomonosov               | 1         | 0.96%   |
| Leiria                  | 1         | 0.96%   |
| LeÃ³n                 | 1         | 0.96%   |
| Koleczkowo              | 1         | 0.96%   |
| Khartoum                | 1         | 0.96%   |
| Kehl                    | 1         | 0.96%   |
| Kazanâ€™           | 1         | 0.96%   |
| Kathu                   | 1         | 0.96%   |
| Isernhagen              | 1         | 0.96%   |
| Howick                  | 1         | 0.96%   |
| Heraklion               | 1         | 0.96%   |
| Heinsberg               | 1         | 0.96%   |
| Hamelin                 | 1         | 0.96%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 35        | 51     | 19.66%  |
| Samsung Electronics | 31        | 47     | 17.42%  |
| Seagate             | 30        | 48     | 16.85%  |
| Kingston            | 13        | 14     | 7.3%    |
| Toshiba             | 9         | 10     | 5.06%   |
| SanDisk             | 7         | 8      | 3.93%   |
| Hitachi             | 6         | 9      | 3.37%   |
| Crucial             | 6         | 6      | 3.37%   |
| Unknown             | 5         | 5      | 2.81%   |
| SK Hynix            | 4         | 4      | 2.25%   |
| HGST                | 4         | 4      | 2.25%   |
| A-DATA Technology   | 4         | 4      | 2.25%   |
| Micron Technology   | 3         | 4      | 1.69%   |
| Intel               | 3         | 3      | 1.69%   |
| Silicon Motion      | 2         | 2      | 1.12%   |
| Phison              | 2         | 2      | 1.12%   |
| Fujitsu             | 2         | 2      | 1.12%   |
| TO Exter            | 1         | 1      | 0.56%   |
| SSSTC               | 1         | 1      | 0.56%   |
| PLEXTOR             | 1         | 2      | 0.56%   |
| LITEON              | 1         | 1      | 0.56%   |
| Lite-On             | 1         | 1      | 0.56%   |
| JMicron             | 1         | 1      | 0.56%   |
| Intenso             | 1         | 1      | 0.56%   |
| Inateck             | 1         | 1      | 0.56%   |
| HGST HTS            | 1         | 1      | 0.56%   |
| Corsair             | 1         | 1      | 0.56%   |
| China               | 1         | 1      | 0.56%   |
| Apacer              | 1         | 2      | 0.56%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB             | 3         | 1.52%   |
| WDC WDS500G1X0E-00AFY0 500GB          | 2         | 1.02%   |
| WDC WDS480G2G0A-00JH30 480GB SSD      | 2         | 1.02%   |
| WDC WD5000AAKX-07U6AA0 500GB          | 2         | 1.02%   |
| SK Hynix HFS128G39TND-N210A 128GB SSD | 2         | 1.02%   |
| Silicon Motion NVMe SSD Drive 512GB   | 2         | 1.02%   |
| Seagate ST3750528AS 752GB             | 2         | 1.02%   |
| Seagate ST3500418AS 500GB             | 2         | 1.02%   |
| Seagate ST3500413AS 500GB             | 2         | 1.02%   |
| Seagate ST2000DM008-2FR102 2TB        | 2         | 1.02%   |
| Seagate ST2000DM006-2DM164 2TB        | 2         | 1.02%   |
| Seagate ST2000DM001-9YN164 2TB        | 2         | 1.02%   |
| Seagate ST2000DM001-1ER164 2TB        | 2         | 1.02%   |
| Seagate ST1000LM035-1RK172 1TB        | 2         | 1.02%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 2         | 1.02%   |
| Samsung SSD 980 PRO 1TB               | 2         | 1.02%   |
| Samsung SSD 970 EVO 1TB               | 2         | 1.02%   |
| Samsung SSD 870 QVO 1TB               | 2         | 1.02%   |
| Samsung SSD 860 EVO 250GB             | 2         | 1.02%   |
| Samsung SSD 860 EVO 1TB               | 2         | 1.02%   |
| Samsung SSD 850 EVO 500GB             | 2         | 1.02%   |
| Kingston SV300S37A120G 120GB SSD      | 2         | 1.02%   |
| Kingston SA400S37120G 120GB SSD       | 2         | 1.02%   |
| HGST HTS721010A9E630 1TB              | 2         | 1.02%   |
| Fujitsu MHW2120BH 120GB               | 2         | 1.02%   |
| WDC WDS500G2B0A 500GB SSD             | 1         | 0.51%   |
| WDC WDS500G1B0B-00AS40 500GB SSD      | 1         | 0.51%   |
| WDC WDS250G1B0C-00S6U0 250GB          | 1         | 0.51%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD      | 1         | 0.51%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD      | 1         | 0.51%   |
| WDC WDS200T2B0A-00SM50 2TB SSD        | 1         | 0.51%   |
| WDC WDS100T3X0C-00SJG0 1TB            | 1         | 0.51%   |
| WDC WDS100T1X0E-00AFY0 1TB            | 1         | 0.51%   |
| WDC WD800BEVS-60RST0 80GB             | 1         | 0.51%   |
| WDC WD7500AALX-009BA0 752GB           | 1         | 0.51%   |
| WDC WD5000LPVX-00V0TT0 500GB          | 1         | 0.51%   |
| WDC WD5000LPLX-66ZNTT1 500GB          | 1         | 0.51%   |
| WDC WD5000AAVS-00ZTB0 500GB           | 1         | 0.51%   |
| WDC WD5000AAKX-08U6AA0 500GB          | 1         | 0.51%   |
| WDC WD50 00LPCX-00VHAT0 500GB         | 1         | 0.51%   |
| WDC WD40EZAZ-00SF3B0 4TB              | 1         | 0.51%   |
| WDC WD3200BEVT-22ZCT0 320GB           | 1         | 0.51%   |
| WDC WD3200AAKS-00B3A0 320GB           | 1         | 0.51%   |
| WDC WD3200AAJS-56M0A0 320GB           | 1         | 0.51%   |
| WDC WD2500BEVT-60ZCT1 250GB           | 1         | 0.51%   |
| WDC WD2500AAJS-00VTA0 250GB           | 1         | 0.51%   |
| WDC WD20EARX-00PASB0 2TB              | 1         | 0.51%   |
| WDC WD2005FBYZ-01YCBB2 2TB            | 1         | 0.51%   |
| WDC WD10SPZX-60Z10T0 1TB              | 1         | 0.51%   |
| WDC WD10SPZX-24Z10 1TB                | 1         | 0.51%   |
| WDC WD10SPZX-17Z10T0 1TB              | 1         | 0.51%   |
| WDC WD10EZEX-75WN4A0 1TB              | 1         | 0.51%   |
| WDC WD10EZEX-75M2NA0 1TB              | 1         | 0.51%   |
| WDC WD10EZEX-08WN4A0 1TB              | 1         | 0.51%   |
| WDC WD10EZEX-00KUWA0 1TB              | 1         | 0.51%   |
| WDC WD10EZEX-00BN5A0 1TB              | 1         | 0.51%   |
| WDC WD10EAVS-22D7B0 1TB               | 1         | 0.51%   |
| WDC WD10EACS-00D6B1 1TB               | 1         | 0.51%   |
| WDC WD1003FZEX-00K3CA0 1TB            | 1         | 0.51%   |
| WDC WD1001FALS-00E3A0 1TB             | 1         | 0.51%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 30        | 47     | 37.5%   |
| WDC                 | 26        | 38     | 32.5%   |
| Hitachi             | 6         | 9      | 7.5%    |
| Toshiba             | 5         | 6      | 6.25%   |
| Samsung Electronics | 5         | 10     | 6.25%   |
| HGST                | 4         | 4      | 5%      |
| Fujitsu             | 2         | 2      | 2.5%    |
| Unknown             | 1         | 1      | 1.25%   |
| Inateck             | 1         | 1      | 1.25%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 14        | 21     | 22.22%  |
| Kingston            | 12        | 13     | 19.05%  |
| WDC                 | 7         | 7      | 11.11%  |
| SanDisk             | 7         | 8      | 11.11%  |
| A-DATA Technology   | 4         | 4      | 6.35%   |
| Toshiba             | 3         | 3      | 4.76%   |
| Crucial             | 3         | 3      | 4.76%   |
| SK Hynix            | 2         | 2      | 3.17%   |
| Intel               | 2         | 2      | 3.17%   |
| TO Exter            | 1         | 1      | 1.59%   |
| SSSTC               | 1         | 1      | 1.59%   |
| PLEXTOR             | 1         | 2      | 1.59%   |
| Micron Technology   | 1         | 2      | 1.59%   |
| LITEON              | 1         | 1      | 1.59%   |
| JMicron             | 1         | 1      | 1.59%   |
| Intenso             | 1         | 1      | 1.59%   |
| China               | 1         | 1      | 1.59%   |
| Apacer              | 1         | 2      | 1.59%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 63        | 118    | 40.65%  |
| SSD     | 56        | 75     | 36.13%  |
| NVMe    | 31        | 38     | 20%     |
| MMC     | 4         | 4      | 2.58%   |
| Unknown | 1         | 2      | 0.65%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 85        | 187    | 68%     |
| NVMe | 31        | 38     | 24.8%   |
| SAS  | 5         | 8      | 4%      |
| MMC  | 4         | 4      | 3.2%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 58        | 91     | 46.03%  |
| 0.51-1.0   | 46        | 66     | 36.51%  |
| 1.01-2.0   | 17        | 29     | 13.49%  |
| 2.01-3.0   | 2         | 2      | 1.59%   |
| 10.01-20.0 | 2         | 3      | 1.59%   |
| 3.01-4.0   | 1         | 2      | 0.79%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| More than 3000 | 24        | 23.08%  |
| 1001-2000      | 19        | 18.27%  |
| 501-1000       | 18        | 17.31%  |
| 2001-3000      | 16        | 15.38%  |
| 251-500        | 14        | 13.46%  |
| 51-100         | 4         | 3.85%   |
| Unknown        | 4         | 3.85%   |
| 101-250        | 3         | 2.88%   |
| 1-20           | 2         | 1.92%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 21        | 19.27%  |
| 101-250        | 19        | 17.43%  |
| 51-100         | 17        | 15.6%   |
| 1001-2000      | 14        | 12.84%  |
| 501-1000       | 14        | 12.84%  |
| 1-20           | 9         | 8.26%   |
| 21-50          | 5         | 4.59%   |
| 2001-3000      | 4         | 3.67%   |
| Unknown        | 4         | 3.67%   |
| More than 3000 | 2         | 1.83%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-00V0TT0 500GB          | 1         | 1      | 9.09%   |
| WDC WD3200AAJS-56M0A0 320GB           | 1         | 1      | 9.09%   |
| WDC WD2500BEVT-60ZCT1 250GB           | 1         | 1      | 9.09%   |
| SSSTC CVB-8D128-HP 128GB SSD          | 1         | 1      | 9.09%   |
| SK Hynix HFS128G39TND-N210A 128GB SSD | 1         | 1      | 9.09%   |
| Seagate ST3320620AS 320GB             | 1         | 1      | 9.09%   |
| Seagate ST1000LM035-1RK172 1TB        | 1         | 1      | 9.09%   |
| Seagate ST1000DM003-1CH162 1TB        | 1         | 1      | 9.09%   |
| Phison 311CD0512GB                    | 1         | 1      | 9.09%   |
| Kingston SV300S37A120G 120GB SSD      | 1         | 1      | 9.09%   |
| Crucial CT1000P1SSD8 1TB              | 1         | 1      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| WDC      | 3         | 3      | 27.27%  |
| Seagate  | 3         | 3      | 27.27%  |
| SSSTC    | 1         | 1      | 9.09%   |
| SK Hynix | 1         | 1      | 9.09%   |
| Phison   | 1         | 1      | 9.09%   |
| Kingston | 1         | 1      | 9.09%   |
| Crucial  | 1         | 1      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 3      | 50%     |
| Seagate | 3         | 3      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 5         | 6      | 50%     |
| SSD  | 3         | 3      | 30%     |
| NVMe | 2         | 2      | 20%     |

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
| Works    | 53        | 113    | 46.9%   |
| Detected | 50        | 113    | 44.25%  |
| Malfunc  | 10        | 11     | 8.85%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 62        | 45.59%  |
| AMD                              | 27        | 19.85%  |
| Samsung Electronics              | 13        | 9.56%   |
| Sandisk                          | 6         | 4.41%   |
| Phison Electronics               | 3         | 2.21%   |
| Micron/Crucial Technology        | 3         | 2.21%   |
| Marvell Technology Group         | 3         | 2.21%   |
| ASMedia Technology               | 3         | 2.21%   |
| Silicon Motion                   | 2         | 1.47%   |
| Micron Technology                | 2         | 1.47%   |
| Lite-On Technology               | 2         | 1.47%   |
| Broadcom / LSI                   | 2         | 1.47%   |
| Toshiba America Info Systems     | 1         | 0.74%   |
| SK Hynix                         | 1         | 0.74%   |
| Silicon Integrated Systems [SiS] | 1         | 0.74%   |
| Silicon Image                    | 1         | 0.74%   |
| Seagate Technology               | 1         | 0.74%   |
| Nvidia                           | 1         | 0.74%   |
| Kingston Technology Company      | 1         | 0.74%   |
| JMicron Technology               | 1         | 0.74%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 20        | 12.58%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 8         | 5.03%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 7         | 4.4%    |
| AMD 400 Series Chipset SATA Controller                                         | 5         | 3.14%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 2.52%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4         | 2.52%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 4         | 2.52%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                     | 3         | 1.89%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 1.89%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 3         | 1.89%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 1.89%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 1.89%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 3         | 1.89%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 3         | 1.89%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 2         | 1.26%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                     | 2         | 1.26%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 1.26%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 2         | 1.26%   |
| Micron Non-Volatile memory controller                                          | 2         | 1.26%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2         | 1.26%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 1.26%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 2         | 1.26%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 2         | 1.26%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 1.26%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 2         | 1.26%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2         | 1.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 2         | 1.26%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 2         | 1.26%   |
| AMD X370 Series Chipset SATA Controller                                        | 2         | 1.26%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 2         | 1.26%   |
| AMD 300 Series Chipset SATA Controller                                         | 2         | 1.26%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 1         | 0.63%   |
| SK Hynix Gold P31 SSD                                                          | 1         | 0.63%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 1         | 0.63%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 1         | 0.63%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                           | 1         | 0.63%   |
| Seagate FireCuda 520 SSD                                                       | 1         | 0.63%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1         | 0.63%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 0.63%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 1         | 0.63%   |
| Samsung Electronics SATA controller                                            | 1         | 0.63%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 0.63%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1         | 0.63%   |
| Phison E12 NVMe Controller                                                     | 1         | 0.63%   |
| Nvidia MCP61 SATA Controller                                                   | 1         | 0.63%   |
| Nvidia MCP61 IDE                                                               | 1         | 0.63%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 1         | 0.63%   |
| Marvell Group 88SE912x SATA 6Gb/s Controller [IDE mode]                        | 1         | 0.63%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo          | 1         | 0.63%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller                        | 1         | 0.63%   |
| Lite-On SATA controller                                                        | 1         | 0.63%   |
| Lite-On Non-Volatile memory controller                                         | 1         | 0.63%   |
| Kingston Company A2000 NVMe SSD                                                | 1         | 0.63%   |
| JMicron JMB363 SATA/IDE Controller                                             | 1         | 0.63%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 1         | 0.63%   |
| Intel SSD 660P Series                                                          | 1         | 0.63%   |
| Intel SATA Controller [RAID mode]                                              | 1         | 0.63%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 0.63%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 0.63%   |
| Intel C610/X99 series chipset sSATA Controller [RAID mode]                     | 1         | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 76        | 58.02%  |
| NVMe | 30        | 22.9%   |
| IDE  | 15        | 11.45%  |
| RAID | 9         | 6.87%   |
| SAS  | 1         | 0.76%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 68        | 67.33%  |
| AMD    | 33        | 32.67%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz           | 3         | 2.97%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 3         | 2.97%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 2         | 1.98%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 2         | 1.98%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2         | 1.98%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 2         | 1.98%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2         | 1.98%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 2         | 1.98%   |
| Intel Xeon CPU E5-2687W v2 @ 3.40GHz        | 1         | 0.99%   |
| Intel Xeon CPU E5-2667 v3 @ 3.20GHz         | 1         | 0.99%   |
| Intel Xeon CPU E5-2470 v2 @ 2.40GHz         | 1         | 0.99%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz         | 1         | 0.99%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz    | 1         | 0.99%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 0.99%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1         | 0.99%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1         | 0.99%   |
| Intel Pentium CPU G3258 @ 3.20GHz           | 1         | 0.99%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 1         | 0.99%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1         | 0.99%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 0.99%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 0.99%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1         | 0.99%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 1         | 0.99%   |
| Intel Core i7-5600U CPU @ 2.60GHz           | 1         | 0.99%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz          | 1         | 0.99%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1         | 0.99%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz          | 1         | 0.99%   |
| Intel Core i7-3740QM CPU @ 2.70GHz          | 1         | 0.99%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1         | 0.99%   |
| Intel Core i5-8365U CPU @ 1.60GHz           | 1         | 0.99%   |
| Intel Core i5-8300H CPU @ 2.30GHz           | 1         | 0.99%   |
| Intel Core i5-7600K CPU @ 3.80GHz           | 1         | 0.99%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 1         | 0.99%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 1         | 0.99%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 1         | 0.99%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz          | 1         | 0.99%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 1         | 0.99%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1         | 0.99%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 1         | 0.99%   |
| Intel Core i5-4440 CPU @ 3.10GHz            | 1         | 0.99%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 1         | 0.99%   |
| Intel Core i5-4200M CPU @ 2.50GHz           | 1         | 0.99%   |
| Intel Core i5-3317U CPU @ 1.70GHz           | 1         | 0.99%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 1         | 0.99%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 0.99%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 1         | 0.99%   |
| Intel Core i5-2400S CPU @ 2.50GHz           | 1         | 0.99%   |
| Intel Core i5-2320 CPU @ 3.00GHz            | 1         | 0.99%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 1         | 0.99%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 1         | 0.99%   |
| Intel Core i5 CPU M 460 @ 2.53GHz           | 1         | 0.99%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 1         | 0.99%   |
| Intel Core i3-7100U CPU @ 2.40GHz           | 1         | 0.99%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 1         | 0.99%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 1         | 0.99%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 1         | 0.99%   |
| Intel Core 2 Quad CPU Q9300 @ 2.50GHz       | 1         | 0.99%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz        | 1         | 0.99%   |
| Intel Core 2 Duo CPU T5250 @ 1.50GHz        | 1         | 0.99%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 1         | 0.99%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 27        | 26.73%  |
| Intel Core i7           | 16        | 15.84%  |
| AMD Ryzen 7             | 9         | 8.91%   |
| AMD Ryzen 9             | 6         | 5.94%   |
| Intel Core i3           | 5         | 4.95%   |
| Intel Core 2 Duo        | 5         | 4.95%   |
| AMD Ryzen 5             | 5         | 4.95%   |
| Intel Xeon              | 4         | 3.96%   |
| Other                   | 2         | 1.98%   |
| Intel Pentium Dual-Core | 2         | 1.98%   |
| Intel Celeron           | 2         | 1.98%   |
| AMD Phenom II X4        | 2         | 1.98%   |
| AMD FX                  | 2         | 1.98%   |
| AMD A6                  | 2         | 1.98%   |
| Intel Pentium Silver    | 1         | 0.99%   |
| Intel Pentium Dual      | 1         | 0.99%   |
| Intel Pentium           | 1         | 0.99%   |
| Intel Core 2 Quad       | 1         | 0.99%   |
| Intel Core 2            | 1         | 0.99%   |
| AMD Sempron             | 1         | 0.99%   |
| AMD Ryzen 7 PRO         | 1         | 0.99%   |
| AMD Ryzen 3             | 1         | 0.99%   |
| AMD C-50                | 1         | 0.99%   |
| AMD Athlon              | 1         | 0.99%   |
| AMD A8                  | 1         | 0.99%   |
| AMD A10                 | 1         | 0.99%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 37        | 36.63%  |
| 2      | 35        | 34.65%  |
| 8      | 12        | 11.88%  |
| 6      | 8         | 7.92%   |
| 16     | 4         | 3.96%   |
| 12     | 3         | 2.97%   |
| 20     | 1         | 0.99%   |
| 3      | 1         | 0.99%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 99        | 98.02%  |
| 2      | 2         | 1.98%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 65        | 64.36%  |
| 1      | 36        | 35.64%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 101       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 39        | 37.14%  |
| 0x306c3    | 5         | 4.76%   |
| 0x206a7    | 4         | 3.81%   |
| 0x906ea    | 3         | 2.86%   |
| 0x806e9    | 3         | 2.86%   |
| 0x6fd      | 3         | 2.86%   |
| 0x406e3    | 3         | 2.86%   |
| 0x306a9    | 3         | 2.86%   |
| 0x08600106 | 3         | 2.86%   |
| 0x906e9    | 2         | 1.9%    |
| 0x506e3    | 2         | 1.9%    |
| 0x1067a    | 2         | 1.9%    |
| 0x0a201016 | 2         | 1.9%    |
| 0x0a201009 | 2         | 1.9%    |
| 0x08701021 | 2         | 1.9%    |
| 0x08108109 | 2         | 1.9%    |
| 0x08001137 | 2         | 1.9%    |
| 0x07030105 | 2         | 1.9%    |
| 0xa0653    | 1         | 0.95%   |
| 0x806ec    | 1         | 0.95%   |
| 0x806ea    | 1         | 0.95%   |
| 0x806d1    | 1         | 0.95%   |
| 0x806c1    | 1         | 0.95%   |
| 0x706a8    | 1         | 0.95%   |
| 0x706a1    | 1         | 0.95%   |
| 0x306f2    | 1         | 0.95%   |
| 0x306e4    | 1         | 0.95%   |
| 0x306d4    | 1         | 0.95%   |
| 0x30678    | 1         | 0.95%   |
| 0x20655    | 1         | 0.95%   |
| 0x10677    | 1         | 0.95%   |
| 0x10676    | 1         | 0.95%   |
| 0x0a50000c | 1         | 0.95%   |
| 0x0a201204 | 1         | 0.95%   |
| 0x08108102 | 1         | 0.95%   |
| 0x0800820d | 1         | 0.95%   |
| 0x06000852 | 1         | 0.95%   |
| 0x010000db | 1         | 0.95%   |
| 0x010000c8 | 1         | 0.95%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 17        | 16.83%  |
| Haswell       | 11        | 10.89%  |
| IvyBridge     | 8         | 7.92%   |
| Zen 2         | 7         | 6.93%   |
| Skylake       | 7         | 6.93%   |
| Zen+          | 6         | 5.94%   |
| Zen 3         | 6         | 5.94%   |
| SandyBridge   | 5         | 4.95%   |
| Penryn        | 5         | 4.95%   |
| Core          | 5         | 4.95%   |
| Zen           | 4         | 3.96%   |
| Westmere      | 2         | 1.98%   |
| Puma          | 2         | 1.98%   |
| Piledriver    | 2         | 1.98%   |
| K10           | 2         | 1.98%   |
| Goldmont plus | 2         | 1.98%   |
| TigerLake     | 1         | 0.99%   |
| Steamroller   | 1         | 0.99%   |
| Silvermont    | 1         | 0.99%   |
| Nehalem       | 1         | 0.99%   |
| K10 Llano     | 1         | 0.99%   |
| Jaguar        | 1         | 0.99%   |
| Icelake       | 1         | 0.99%   |
| CometLake     | 1         | 0.99%   |
| Broadwell     | 1         | 0.99%   |
| Bobcat        | 1         | 0.99%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Intel       | 52        | 41.94%  |
| Nvidia      | 41        | 33.06%  |
| AMD         | 30        | 24.19%  |
| S3 Graphics | 1         | 0.81%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                       | 4         | 3.15%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 4         | 3.15%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 4         | 3.15%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 4         | 3.15%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4         | 3.15%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 4         | 3.15%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 3         | 2.36%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 3         | 2.36%   |
| Intel HD Graphics 630                                                       | 3         | 2.36%   |
| Intel HD Graphics 530                                                       | 3         | 2.36%   |
| AMD Renoir                                                                  | 3         | 2.36%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2         | 1.57%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 2         | 1.57%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 2         | 1.57%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 1.57%   |
| Intel UHD Graphics 620                                                      | 2         | 1.57%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)         | 2         | 1.57%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)           | 2         | 1.57%   |
| Intel Core Processor Integrated Graphics Controller                         | 2         | 1.57%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2         | 1.57%   |
| AMD Tonga PRO [Radeon R9 285/380]                                           | 2         | 1.57%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                         | 2         | 1.57%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2         | 1.57%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 2         | 1.57%   |
| S3 Graphics 86c764/765 [Trio32/64/64V+]                                     | 1         | 0.79%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 1         | 0.79%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1         | 0.79%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1         | 0.79%   |
| Nvidia GT216 [GeForce GT 220]                                               | 1         | 0.79%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1         | 0.79%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                 | 1         | 0.79%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1         | 0.79%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1         | 0.79%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1         | 0.79%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1         | 0.79%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1         | 0.79%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1         | 0.79%   |
| Nvidia GM204M [GeForce GTX 980M]                                            | 1         | 0.79%   |
| Nvidia GM204M [GeForce GTX 970M]                                            | 1         | 0.79%   |
| Nvidia GM108M [GeForce 940MX]                                               | 1         | 0.79%   |
| Nvidia GM107M [GeForce GTX 960M]                                            | 1         | 0.79%   |
| Nvidia GM107M [GeForce GTX 950M]                                            | 1         | 0.79%   |
| Nvidia GM107GL [Quadro K2200]                                               | 1         | 0.79%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1         | 0.79%   |
| Nvidia GK110GL [Quadro K5200]                                               | 1         | 0.79%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1         | 0.79%   |
| Nvidia GK104GLM [Quadro K3000M]                                             | 1         | 0.79%   |
| Nvidia GF119 [GeForce GT 520]                                               | 1         | 0.79%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]        | 1         | 0.79%   |
| Nvidia GF108 [GeForce GT 630]                                               | 1         | 0.79%   |
| Nvidia GF100GL [Tesla C2050 / C2070]                                        | 1         | 0.79%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                  | 1         | 0.79%   |
| Nvidia GA106 [GeForce RTX 3060]                                             | 1         | 0.79%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 1         | 0.79%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                          | 1         | 0.79%   |
| Nvidia G98M [GeForce 9300M GS]                                              | 1         | 0.79%   |
| Nvidia G84 [GeForce 8600 GT]                                                | 1         | 0.79%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1         | 0.79%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 1         | 0.79%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 1         | 0.79%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 30        | 29.7%   |
| 1 x Nvidia      | 26        | 25.74%  |
| 1 x AMD         | 23        | 22.77%  |
| Intel + Nvidia  | 14        | 13.86%  |
| Intel + AMD     | 6         | 5.94%   |
| 2 x AMD         | 1         | 0.99%   |
| 1 x S3 Graphics | 1         | 0.99%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 76        | 75.25%  |
| Proprietary | 21        | 20.79%  |
| Unknown     | 4         | 3.96%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 63        | 61.17%  |
| 1.01-2.0   | 10        | 9.71%   |
| 0.01-0.5   | 8         | 7.77%   |
| 3.01-4.0   | 6         | 5.83%   |
| 7.01-8.0   | 5         | 4.85%   |
| 5.01-6.0   | 3         | 2.91%   |
| 8.01-16.0  | 3         | 2.91%   |
| 0.51-1.0   | 3         | 2.91%   |
| 16.01-24.0 | 2         | 1.94%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| LG Display           | 14        | 12.17%  |
| Goldstar             | 13        | 11.3%   |
| Samsung Electronics  | 11        | 9.57%   |
| Chimei Innolux       | 11        | 9.57%   |
| Dell                 | 10        | 8.7%    |
| AU Optronics         | 9         | 7.83%   |
| BenQ                 | 5         | 4.35%   |
| Ancor Communications | 5         | 4.35%   |
| Philips              | 4         | 3.48%   |
| Hewlett-Packard      | 4         | 3.48%   |
| Lenovo               | 3         | 2.61%   |
| BOE                  | 3         | 2.61%   |
| Acer                 | 3         | 2.61%   |
| LG Electronics       | 2         | 1.74%   |
| Iiyama               | 2         | 1.74%   |
| ASUSTek Computer     | 2         | 1.74%   |
| AOC                  | 2         | 1.74%   |
| Vizio                | 1         | 0.87%   |
| ViewSonic            | 1         | 0.87%   |
| TCL                  | 1         | 0.87%   |
| Sony                 | 1         | 0.87%   |
| Sharp                | 1         | 0.87%   |
| LG Philips           | 1         | 0.87%   |
| InfoVision           | 1         | 0.87%   |
| Hitachi              | 1         | 0.87%   |
| Fujitsu Siemens      | 1         | 0.87%   |
| Denver               | 1         | 0.87%   |
| CSO                  | 1         | 0.87%   |
| CPT                  | 1         | 0.87%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 1.68%   |
| Hewlett-Packard LV1911 HWP3005 1366x768 410x230mm 18.5-inch           | 2         | 1.68%   |
| Goldstar LG HDR WFHD GSM7714 2560x1080 800x340mm 34.2-inch            | 2         | 1.68%   |
| ASUSTek Computer VG245 AUS24A1 1920x1080 531x299mm 24.0-inch          | 2         | 1.68%   |
| Vizio E60-E3 VIZ1018 3840x2160 1330x748mm 60.1-inch                   | 1         | 0.84%   |
| ViewSonic VX3211-2K VSCF634 2560x1440 698x392mm 31.5-inch             | 1         | 0.84%   |
| TCL LCD TV TCL0030 1920x1080 708x398mm 32.0-inch                      | 1         | 0.84%   |
| Sony Nvidia Defaul t Flat Panel SNY06FA 1600x900 360x200mm 16.2-inch  | 1         | 0.84%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch               | 1         | 0.84%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch     | 1         | 0.84%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 1         | 0.84%   |
| Samsung Electronics SyncMaster SAM0524 1920x1080 480x270mm 21.7-inch  | 1         | 0.84%   |
| Samsung Electronics SyncMaster SAM00A2 1024x768 304x228mm 15.0-inch   | 1         | 0.84%   |
| Samsung Electronics SMS27A850T SAM0887 2560x1440 518x324mm 24.1-inch  | 1         | 0.84%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch  | 1         | 0.84%   |
| Samsung Electronics S34J55x SAM0F72 3440x1440 800x330mm 34.1-inch     | 1         | 0.84%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 800x330mm 34.1-inch     | 1         | 0.84%   |
| Samsung Electronics S23B550 SAM0919 1920x1080 510x287mm 23.0-inch     | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SEC3449 1366x768 309x174mm 14.0-inch  | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 353x198mm 15.9-inch  | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SDC424B 3840x2160 344x194mm 15.5-inch | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 950x540mm 43.0-inch | 1         | 0.84%   |
| Philips PHL 258B6QU PHL08F5 2560x1440 553x311mm 25.0-inch             | 1         | 0.84%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 1         | 0.84%   |
| Philips 150S PHL0812 1024x768 307x230mm 15.1-inch                     | 1         | 0.84%   |
| Philips 150S PHL0805 1024x768 307x230mm 15.1-inch                     | 1         | 0.84%   |
| LG Philips LCD Monitor LPLDB00 1280x800 331x207mm 15.4-inch           | 1         | 0.84%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                     | 1         | 0.84%   |
| LG Electronics LCD Monitor LG TV SSCR 3840x2160                       | 1         | 0.84%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch          | 1         | 0.84%   |
| LG Display LCD Monitor LGD05D8 1920x1080 344x194mm 15.5-inch          | 1         | 0.84%   |
| LG Display LCD Monitor LGD05C0 1920x1080 344x194mm 15.5-inch          | 1         | 0.84%   |
| LG Display LCD Monitor LGD059E 1920x1080 382x215mm 17.3-inch          | 1         | 0.84%   |
| LG Display LCD Monitor LGD053C 1920x1080 309x174mm 14.0-inch          | 1         | 0.84%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch          | 1         | 0.84%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 0.84%   |
| LG Display LCD Monitor LGD04A9 1920x1080 309x174mm 14.0-inch          | 1         | 0.84%   |
| LG Display LCD Monitor LGD0490 1920x1080 309x174mm 14.0-inch          | 1         | 0.84%   |
| LG Display LCD Monitor LGD046C 1920x1080 382x215mm 17.3-inch          | 1         | 0.84%   |
| LG Display LCD Monitor LGD044F 1920x1080 345x194mm 15.6-inch          | 1         | 0.84%   |
| LG Display LCD Monitor LGD02DA 1920x1080 382x215mm 17.3-inch          | 1         | 0.84%   |
| Lenovo LEN T27i-10 LEN61C6 1920x1080 598x336mm 27.0-inch              | 1         | 0.84%   |
| Lenovo LEN P27q-10 LEN61A8 2560x1440 597x336mm 27.0-inch              | 1         | 0.84%   |
| Lenovo LCD Monitor LEN4020 1024x768 286x214mm 14.1-inch               | 1         | 0.84%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch           | 1         | 0.84%   |
| Iiyama PL2592H IVM6135 1920x1080 544x303mm 24.5-inch                  | 1         | 0.84%   |
| Iiyama PL2492H IVM612F 1920x1080 530x300mm 24.0-inch                  | 1         | 0.84%   |
| Hitachi X90W D-sub HIT6008 1440x900 410x257mm 19.1-inch               | 1         | 0.84%   |
| Hewlett-Packard LA1951 HWP285A 1280x1024 380x300mm 19.1-inch          | 1         | 0.84%   |
| Hewlett-Packard 27es HWP3326 1920x1080 598x336mm 27.0-inch            | 1         | 0.84%   |
| Goldstar W2261 GSM56CF 1920x1080 477x268mm 21.5-inch                  | 1         | 0.84%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 1         | 0.84%   |
| Goldstar MP59G GSM5B35 1920x1080 600x340mm 27.2-inch                  | 1         | 0.84%   |
| Goldstar L1718S GSM443C 1280x1024 338x270mm 17.0-inch                 | 1         | 0.84%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 1         | 0.84%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                | 1         | 0.84%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                | 1         | 0.84%   |
| Goldstar E2742 GSM58C9 1920x1080 600x340mm 27.2-inch                  | 1         | 0.84%   |
| Goldstar E2441 GSM581F 1920x1080 530x300mm 24.0-inch                  | 1         | 0.84%   |
| Goldstar BN550Y GSM5BAB 1920x1080 600x340mm 27.2-inch                 | 1         | 0.84%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 49        | 46.23%  |
| 1366x768 (WXGA)    | 15        | 14.15%  |
| 3840x2160 (4K)     | 6         | 5.66%   |
| 2560x1440 (QHD)    | 6         | 5.66%   |
| 1920x1200 (WUXGA)  | 5         | 4.72%   |
| 2560x1080          | 4         | 3.77%   |
| 1024x768 (XGA)     | 4         | 3.77%   |
| 3440x1440          | 3         | 2.83%   |
| 1600x900 (HD+)     | 3         | 2.83%   |
| 1280x1024 (SXGA)   | 3         | 2.83%   |
| 1680x1050 (WSXGA+) | 2         | 1.89%   |
| 1440x900 (WXGA+)   | 2         | 1.89%   |
| 640x480            | 1         | 0.94%   |
| 3840x2400          | 1         | 0.94%   |
| 2160x1440          | 1         | 0.94%   |
| 1280x800 (WXGA)    | 1         | 0.94%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 27        | 24.32%  |
| 27      | 10        | 9.01%   |
| 14      | 10        | 9.01%   |
| 24      | 9         | 8.11%   |
| 21      | 9         | 8.11%   |
| 17      | 9         | 8.11%   |
| 34      | 6         | 5.41%   |
| 23      | 6         | 5.41%   |
| 13      | 4         | 3.6%    |
| 18      | 3         | 2.7%    |
| 11      | 3         | 2.7%    |
| Unknown | 3         | 2.7%    |
| 25      | 2         | 1.8%    |
| 22      | 2         | 1.8%    |
| 19      | 2         | 1.8%    |
| 84      | 1         | 0.9%    |
| 74      | 1         | 0.9%    |
| 32      | 1         | 0.9%    |
| 31      | 1         | 0.9%    |
| 26      | 1         | 0.9%    |
| 20      | 1         | 0.9%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 39        | 35.14%  |
| 501-600     | 25        | 22.52%  |
| 401-500     | 17        | 15.32%  |
| 351-400     | 9         | 8.11%   |
| 701-800     | 7         | 6.31%   |
| 201-300     | 6         | 5.41%   |
| 601-700     | 3         | 2.7%    |
| Unknown     | 3         | 2.7%    |
| 1501-2000   | 2         | 1.8%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 75        | 72.82%  |
| 16/10   | 11        | 10.68%  |
| 21/9    | 6         | 5.83%   |
| 4/3     | 4         | 3.88%   |
| 5/4     | 3         | 2.91%   |
| Unknown | 3         | 2.91%   |
| 3/2     | 1         | 0.97%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 27        | 24.11%  |
| 201-250        | 23        | 20.54%  |
| 81-90          | 12        | 10.71%  |
| 301-350        | 11        | 9.82%   |
| 351-500        | 8         | 7.14%   |
| 121-130        | 7         | 6.25%   |
| 251-300        | 5         | 4.46%   |
| 141-150        | 5         | 4.46%   |
| 151-200        | 4         | 3.57%   |
| 51-60          | 3         | 2.68%   |
| Unknown        | 3         | 2.68%   |
| More than 1000 | 2         | 1.79%   |
| 71-80          | 1         | 0.89%   |
| 91-100         | 1         | 0.89%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 42        | 38.89%  |
| 101-120       | 30        | 27.78%  |
| 121-160       | 29        | 26.85%  |
| Unknown       | 3         | 2.78%   |
| More than 240 | 2         | 1.85%   |
| 161-240       | 2         | 1.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 78        | 77.23%  |
| 2     | 18        | 17.82%  |
| 0     | 4         | 3.96%   |
| 3     | 1         | 0.99%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 61        | 38.61%  |
| Intel                            | 50        | 31.65%  |
| Qualcomm Atheros                 | 16        | 10.13%  |
| Broadcom                         | 8         | 5.06%   |
| Ralink                           | 4         | 2.53%   |
| Broadcom Limited                 | 3         | 1.9%    |
| Samsung Electronics              | 2         | 1.27%   |
| Dell                             | 2         | 1.27%   |
| ASIX Electronics                 | 2         | 1.27%   |
| ZyXEL Communications             | 1         | 0.63%   |
| TP-Link                          | 1         | 0.63%   |
| TOMTOM                           | 1         | 0.63%   |
| Silicon Integrated Systems [SiS] | 1         | 0.63%   |
| Ralink Technology                | 1         | 0.63%   |
| NetXen Incorporated              | 1         | 0.63%   |
| Manta                            | 1         | 0.63%   |
| Lenovo                           | 1         | 0.63%   |
| D-Link System                    | 1         | 0.63%   |
| AVM                              | 1         | 0.63%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 46        | 24.08%  |
| Intel Wi-Fi 6 AX200                                                  | 10        | 5.24%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 5         | 2.62%   |
| Intel I211 Gigabit Network Connection                                | 5         | 2.62%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 4         | 2.09%   |
| Realtek RTL8125 2.5GbE Controller                                    | 4         | 2.09%   |
| Intel Wireless 8260                                                  | 4         | 2.09%   |
| Intel Wireless 7260                                                  | 4         | 2.09%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 3         | 1.57%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller            | 3         | 1.57%   |
| Intel Wireless 8265 / 8275                                           | 3         | 1.57%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 2         | 1.05%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 2         | 1.05%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                             | 2         | 1.05%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                            | 2         | 1.05%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 2         | 1.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 2         | 1.05%   |
| Intel Wireless-AC 9260                                               | 2         | 1.05%   |
| Intel Wireless 3165                                                  | 2         | 1.05%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 2         | 1.05%   |
| Intel Ethernet Connection I219-LM                                    | 2         | 1.05%   |
| Intel Ethernet Connection (2) I218-LM                                | 2         | 1.05%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 2         | 1.05%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 2         | 1.05%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 2         | 1.05%   |
| ASIX AX88179 Gigabit Ethernet                                        | 2         | 1.05%   |
| ZyXEL NWD2205 802.11n Wireless N Adapter [Realtek RTL8192CU]         | 1         | 0.52%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                  | 1         | 0.52%   |
| TOMTOM GO 60                                                         | 1         | 0.52%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter        | 1         | 0.52%   |
| Samsung Kiera                                                        | 1         | 0.52%   |
| Samsung Galaxy series, misc. (tethering mode)                        | 1         | 0.52%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 1         | 0.52%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter             | 1         | 0.52%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                               | 1         | 0.52%   |
| Realtek RTL8191SEvB Wireless LAN Controller                          | 1         | 0.52%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 1         | 0.52%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                      | 1         | 0.52%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                           | 1         | 0.52%   |
| Realtek Killer E3000 2.5GbE Controller                               | 1         | 0.52%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                     | 1         | 0.52%   |
| Realtek 802.11n                                                      | 1         | 0.52%   |
| Ralink RT3072 Wireless Adapter                                       | 1         | 0.52%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                 | 1         | 0.52%   |
| Ralink RT2561/RT61 802.11g PCI                                       | 1         | 0.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 1         | 0.52%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                               | 1         | 0.52%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                            | 1         | 0.52%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 1         | 0.52%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                     | 1         | 0.52%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                           | 1         | 0.52%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                        | 1         | 0.52%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet       | 1         | 0.52%   |
| NetXen Incorporated NX3031 Multifunction 1/10-Gigabit Server Adapter | 1         | 0.52%   |
| Manta MM812                                                          | 1         | 0.52%   |
| Lenovo OneLink+ Giga                                                 | 1         | 0.52%   |
| Intel Wireless 7265                                                  | 1         | 0.52%   |
| Intel WiFi Link 5100                                                 | 1         | 0.52%   |
| Intel Wi-Fi 6 AX201                                                  | 1         | 0.52%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection        | 1         | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 40        | 49.38%  |
| Realtek Semiconductor | 14        | 17.28%  |
| Qualcomm Atheros      | 10        | 12.35%  |
| Broadcom              | 6         | 7.41%   |
| Ralink                | 4         | 4.94%   |
| ZyXEL Communications  | 1         | 1.23%   |
| TP-Link               | 1         | 1.23%   |
| Ralink Technology     | 1         | 1.23%   |
| Dell                  | 1         | 1.23%   |
| D-Link System         | 1         | 1.23%   |
| Broadcom Limited      | 1         | 1.23%   |
| AVM                   | 1         | 1.23%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                        | 10        | 12.35%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 4         | 4.94%   |
| Intel Wireless 8260                                                        | 4         | 4.94%   |
| Intel Wireless 7260                                                        | 4         | 4.94%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                 | 3         | 3.7%    |
| Intel Wireless 8265 / 8275                                                 | 3         | 3.7%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                   | 2         | 2.47%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                            | 2         | 2.47%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                  | 2         | 2.47%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                 | 2         | 2.47%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 2         | 2.47%   |
| Intel Wireless-AC 9260                                                     | 2         | 2.47%   |
| Intel Wireless 3165                                                        | 2         | 2.47%   |
| Intel Tiger Lake PCH CNVi WiFi                                             | 2         | 2.47%   |
| Intel Cannon Lake PCH CNVi WiFi                                            | 2         | 2.47%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                        | 2         | 2.47%   |
| ZyXEL NWD2205 802.11n Wireless N Adapter [Realtek RTL8192CU]               | 1         | 1.23%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                        | 1         | 1.23%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                   | 1         | 1.23%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                   | 1         | 1.23%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                     | 1         | 1.23%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                | 1         | 1.23%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                 | 1         | 1.23%   |
| Realtek 802.11n                                                            | 1         | 1.23%   |
| Ralink RT3072 Wireless Adapter                                             | 1         | 1.23%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                       | 1         | 1.23%   |
| Ralink RT2561/RT61 802.11g PCI                                             | 1         | 1.23%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                 | 1         | 1.23%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                           | 1         | 1.23%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                           | 1         | 1.23%   |
| Intel Wireless 7265                                                        | 1         | 1.23%   |
| Intel WiFi Link 5100                                                       | 1         | 1.23%   |
| Intel Wi-Fi 6 AX201                                                        | 1         | 1.23%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection              | 1         | 1.23%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                      | 1         | 1.23%   |
| Intel Gemini Lake PCH CNVi WiFi                                            | 1         | 1.23%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 1         | 1.23%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                            | 1         | 1.23%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                               | 1         | 1.23%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                              | 1         | 1.23%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                   | 1         | 1.23%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                                       | 1         | 1.23%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 1         | 1.23%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                 | 1         | 1.23%   |
| Broadcom BCM43228 802.11a/b/g/n                                            | 1         | 1.23%   |
| Broadcom BCM43227 802.11b/g/n                                              | 1         | 1.23%   |
| Broadcom BCM43225 802.11b/g/n                                              | 1         | 1.23%   |
| Broadcom BCM43142 802.11b/g/n                                              | 1         | 1.23%   |
| AVM Fritz!WLAN N v2 [Atheros AR9271]                                       | 1         | 1.23%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 57        | 56.44%  |
| Intel                            | 25        | 24.75%  |
| Qualcomm Atheros                 | 8         | 7.92%   |
| Broadcom                         | 3         | 2.97%   |
| Broadcom Limited                 | 2         | 1.98%   |
| ASIX Electronics                 | 2         | 1.98%   |
| Silicon Integrated Systems [SiS] | 1         | 0.99%   |
| Samsung Electronics              | 1         | 0.99%   |
| NetXen Incorporated              | 1         | 0.99%   |
| Lenovo                           | 1         | 0.99%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 46        | 43.4%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 5         | 4.72%   |
| Intel I211 Gigabit Network Connection                                | 5         | 4.72%   |
| Realtek RTL8125 2.5GbE Controller                                    | 4         | 3.77%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller            | 3         | 2.83%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                             | 2         | 1.89%   |
| Intel Ethernet Connection I219-LM                                    | 2         | 1.89%   |
| Intel Ethernet Connection (2) I218-LM                                | 2         | 1.89%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 2         | 1.89%   |
| ASIX AX88179 Gigabit Ethernet                                        | 2         | 1.89%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter        | 1         | 0.94%   |
| Samsung Galaxy series, misc. (tethering mode)                        | 1         | 0.94%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                      | 1         | 0.94%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                           | 1         | 0.94%   |
| Realtek Killer E3000 2.5GbE Controller                               | 1         | 0.94%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                     | 1         | 0.94%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                               | 1         | 0.94%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                            | 1         | 0.94%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                           | 1         | 0.94%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                        | 1         | 0.94%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet       | 1         | 0.94%   |
| NetXen Incorporated NX3031 Multifunction 1/10-Gigabit Server Adapter | 1         | 0.94%   |
| Lenovo OneLink+ Giga                                                 | 1         | 0.94%   |
| Intel I210 Gigabit Network Connection                                | 1         | 0.94%   |
| Intel Ethernet Connection I219-V                                     | 1         | 0.94%   |
| Intel Ethernet Connection I217-V                                     | 1         | 0.94%   |
| Intel Ethernet Connection I217-LM                                    | 1         | 0.94%   |
| Intel Ethernet Connection (6) I219-LM                                | 1         | 0.94%   |
| Intel Ethernet Connection (4) I219-LM                                | 1         | 0.94%   |
| Intel Ethernet Connection (3) I218-LM                                | 1         | 0.94%   |
| Intel Ethernet Connection (2) I219-LM                                | 1         | 0.94%   |
| Intel Ethernet Connection (10) I219-V                                | 1         | 0.94%   |
| Intel 82579V Gigabit Network Connection                              | 1         | 0.94%   |
| Intel 82574L Gigabit Network Connection                              | 1         | 0.94%   |
| Intel 82567LM Gigabit Network Connection                             | 1         | 0.94%   |
| Intel 82566MM Gigabit Network Connection                             | 1         | 0.94%   |
| Intel 82562V-2 10/100 Network Connection                             | 1         | 0.94%   |
| Intel 82541PI Gigabit Ethernet Controller                            | 1         | 0.94%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                     | 1         | 0.94%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                      | 1         | 0.94%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                      | 1         | 0.94%   |
| Broadcom Limited NetLink BCM57785 Gigabit Ethernet PCIe              | 1         | 0.94%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe              | 1         | 0.94%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 94        | 53.11%  |
| WiFi     | 79        | 44.63%  |
| Unknown  | 3         | 1.69%   |
| Modem    | 1         | 0.56%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 81        | 53.29%  |
| WiFi     | 69        | 45.39%  |
| Modem    | 1         | 0.66%   |
| Unknown  | 1         | 0.66%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 64        | 63.37%  |
| 1     | 31        | 30.69%  |
| 3     | 5         | 4.95%   |
| 5     | 1         | 0.99%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 75        | 73.53%  |
| Yes  | 27        | 26.47%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 26        | 40.63%  |
| Realtek Semiconductor           | 8         | 12.5%   |
| Cambridge Silicon Radio         | 8         | 12.5%   |
| Qualcomm Atheros Communications | 6         | 9.38%   |
| Broadcom                        | 3         | 4.69%   |
| Lite-On Technology              | 2         | 3.13%   |
| IMC Networks                    | 2         | 3.13%   |
| Foxconn / Hon Hai               | 2         | 3.13%   |
| Dell                            | 2         | 3.13%   |
| ASUSTek Computer                | 2         | 3.13%   |
| Realtek                         | 1         | 1.56%   |
| Belkin Components               | 1         | 1.56%   |
| Alps Electric                   | 1         | 1.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 9         | 14.06%  |
| Intel AX200 Bluetooth                                                               | 8         | 12.5%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 8         | 12.5%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 4         | 6.25%   |
| Realtek Bluetooth Radio                                                             | 3         | 4.69%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 3         | 4.69%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 3         | 4.69%   |
| Intel AX201 Bluetooth                                                               | 3         | 4.69%   |
| Intel Bluetooth Device                                                              | 2         | 3.13%   |
| IMC Networks Bluetooth Device                                                       | 2         | 3.13%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 1.56%   |
| Realtek Bluetooth Radio                                                             | 1         | 1.56%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 1.56%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 1.56%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 1.56%   |
| Lite-On Bluetooth Device                                                            | 1         | 1.56%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 1.56%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 1.56%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.56%   |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 1         | 1.56%   |
| Dell Broadcom BCM20702A0 Bluetooth                                                  | 1         | 1.56%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 1.56%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 1         | 1.56%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 1         | 1.56%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 1         | 1.56%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                               | 1         | 1.56%   |
| ASUS Bluetooth Adapter                                                              | 1         | 1.56%   |
| ASUS ASUS USB-BT500                                                                 | 1         | 1.56%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 1         | 1.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 64        | 42.38%  |
| AMD                              | 39        | 25.83%  |
| Nvidia                           | 31        | 20.53%  |
| C-Media Electronics              | 3         | 1.99%   |
| Logitech                         | 2         | 1.32%   |
| Lenovo                           | 2         | 1.32%   |
| Creative Labs                    | 2         | 1.32%   |
| Texas Instruments                | 1         | 0.66%   |
| Silicon Integrated Systems [SiS] | 1         | 0.66%   |
| Sennheiser Communications        | 1         | 0.66%   |
| JMTek                            | 1         | 0.66%   |
| GN Netcom                        | 1         | 0.66%   |
| ESS Technology                   | 1         | 0.66%   |
| BEHRINGER International          | 1         | 0.66%   |
| ASUSTek Computer                 | 1         | 0.66%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 9         | 5.17%   |
| AMD Starship/Matisse HD Audio Controller                                   | 9         | 5.17%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7         | 4.02%   |
| AMD Family 17h/19h HD Audio Controller                                     | 7         | 4.02%   |
| Intel Cannon Lake PCH cAVS                                                 | 6         | 3.45%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6         | 3.45%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 6         | 3.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 2.87%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 2.87%   |
| AMD FCH Azalia Controller                                                  | 5         | 2.87%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4         | 2.3%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 2.3%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 4         | 2.3%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 4         | 2.3%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 2.3%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 1.72%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 1.72%   |
| Nvidia GA102 High Definition Audio Controller                              | 3         | 1.72%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 1.72%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3         | 1.72%   |
| AMD Kabini HDMI/DP Audio                                                   | 3         | 1.72%   |
| Nvidia GM206 High Definition Audio Controller                              | 2         | 1.15%   |
| Nvidia GK106 HDMI Audio Controller                                         | 2         | 1.15%   |
| Logitech Headset H390                                                      | 2         | 1.15%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.15%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 2         | 1.15%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 1.15%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 1.15%   |
| AMD Tonga HDMI Audio [Radeon R9 285/380]                                   | 2         | 1.15%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 2         | 1.15%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2         | 1.15%   |
| Texas Instruments PCM2900C Audio CODEC                                     | 1         | 0.57%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 1         | 0.57%   |
| Sennheiser Communications Sennheiser 3D G4ME1                              | 1         | 0.57%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.57%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.57%   |
| Nvidia MCP61 High Definition Audio                                         | 1         | 0.57%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 0.57%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 0.57%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.57%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 0.57%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1         | 0.57%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.57%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 0.57%   |
| Nvidia GK110 High Definition Audio Controller                              | 1         | 0.57%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.57%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 0.57%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.57%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 0.57%   |
| Nvidia GF100 High Definition Audio Controller                              | 1         | 0.57%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 0.57%   |
| Nvidia Audio device                                                        | 1         | 0.57%   |
| Lenovo ThinkPad Thunderbolt 4 Dock USB Audio                               | 1         | 0.57%   |
| Lenovo ThinkPad OneLink Plus Dock Audio                                    | 1         | 0.57%   |
| JMTek audio controller                                                     | 1         | 0.57%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 0.57%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 0.57%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 0.57%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 0.57%   |
| Intel CM238 HD Audio Controller                                            | 1         | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Samsung Electronics    | 15        | 20.27%  |
| SK Hynix               | 11        | 14.86%  |
| Kingston               | 11        | 14.86%  |
| Unknown                | 8         | 10.81%  |
| Corsair                | 6         | 8.11%   |
| Crucial                | 5         | 6.76%   |
| Micron Technology      | 4         | 5.41%   |
| G.Skill                | 4         | 5.41%   |
| Unknown (000004B30000) | 1         | 1.35%   |
| Team                   | 1         | 1.35%   |
| Smart                  | 1         | 1.35%   |
| Ramaxel Technology     | 1         | 1.35%   |
| Patriot                | 1         | 1.35%   |
| GOODRAM                | 1         | 1.35%   |
| GeIL                   | 1         | 1.35%   |
| Elpida                 | 1         | 1.35%   |
| AMD                    | 1         | 1.35%   |
| A-DATA Technology      | 1         | 1.35%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Kingston RAM KHX3600C18D4/32GX 32GB DIMM DDR4 3600MT/s        | 2         | 2.41%   |
| Kingston RAM KHX3200C16D4/16GX 16384MB DIMM DDR4 3600MT/s     | 2         | 2.41%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                     | 1         | 1.2%    |
| Unknown RAM Module 4GB SODIMM DDR2 667MT/s                    | 1         | 1.2%    |
| Unknown RAM Module 4096MB SODIMM DDR3                         | 1         | 1.2%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                    | 1         | 1.2%    |
| Unknown RAM Module 2048MB SODIMM 1067MT/s                     | 1         | 1.2%    |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s                  | 1         | 1.2%    |
| Unknown RAM Module 2048MB DIMM 1333MT/s                       | 1         | 1.2%    |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                    | 1         | 1.2%    |
| Unknown RAM Module 1024MB SODIMM 1067MT/s                     | 1         | 1.2%    |
| Unknown RAM 992124 (997124) 8GB DIMM DDR3 1600MT/s            | 1         | 1.2%    |
| Unknown (000004B30000) RAM Module 32GB DIMM DDR3 1333MT/s     | 1         | 1.2%    |
| Team RAM TEAMGROUP-UD4-2400 8192MB DIMM DDR4 3007MT/s         | 1         | 1.2%    |
| Smart RAM SH564568FH8NWPHSFG 2GB SODIMM DDR3 1333MT/s         | 1         | 1.2%    |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                  | 1         | 1.2%    |
| SK Hynix RAM HYMP125S64CP8-S6 2048MB SODIMM SDRAM             | 1         | 1.2%    |
| SK Hynix RAM HMT425S6AFR6A-PB 2048MB SODIMM DDR3 1600MT/s     | 1         | 1.2%    |
| SK Hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s     | 1         | 1.2%    |
| SK Hynix RAM HMT351R7CFR8C-PB 4GB DIMM DDR3 1600MT/s          | 1         | 1.2%    |
| SK Hynix RAM HMT151R7BFR4C-G7 4GB DIMM DDR3 1066MT/s          | 1         | 1.2%    |
| SK Hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s       | 1         | 1.2%    |
| SK Hynix RAM HMA851S6JJR6N-VK 4096MB SODIMM DDR4 2667MT/s     | 1         | 1.2%    |
| SK Hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s     | 1         | 1.2%    |
| SK Hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s     | 1         | 1.2%    |
| SK Hynix RAM HMA451S6AFR8N-TF 4096MB SODIMM DDR4 2133MT/s     | 1         | 1.2%    |
| SK Hynix RAM HMA41GS6AFR8N-TF 8192MB SODIMM DDR4 2667MT/s     | 1         | 1.2%    |
| SK Hynix RAM H9HCNNNCPMMLXR-NEE 8192MB SODIMM LPDDR4 4266MT/s | 1         | 1.2%    |
| Samsung RAM Module 4096MB SODIMM DDR4 2400MT/s                | 1         | 1.2%    |
| Samsung RAM M471B5673FH0-CH9 2GB DIMM DDR3 4199MT/s           | 1         | 1.2%    |
| Samsung RAM M471B5673EH1-CH9 2GB SODIMM DDR3 1334MT/s         | 1         | 1.2%    |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s         | 1         | 1.2%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s         | 1         | 1.2%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s         | 1         | 1.2%    |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s        | 1         | 1.2%    |
| Samsung RAM M471A2K43DB1-CTD 16384MB SODIMM DDR4 2667MT/s     | 1         | 1.2%    |
| Samsung RAM M471A2G43BB2-CWE 16384MB SODIMM DDR4 3200MT/s     | 1         | 1.2%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s         | 1         | 1.2%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s   | 1         | 1.2%    |
| Samsung RAM M393A2G40DB0-CPB 16384MB DIMM DDR4 2133MT/s       | 1         | 1.2%    |
| Samsung RAM M393A1G40DB0-CPB 8192MB DIMM DDR4 2133MT/s        | 1         | 1.2%    |
| Samsung RAM M378B1G73EB0-YK0 8GB DIMM DDR3 1600MT/s           | 1         | 1.2%    |
| Samsung RAM K4F6E3S4HM-MGCJ 4GB SODIMM LPDDR4 3733MT/s        | 1         | 1.2%    |
| Samsung RAM K4E6E304EE-EGCF 4GB SODIMM LPDDR3 1867MT/s        | 1         | 1.2%    |
| Samsung RAM K4E6E304EE-EGCF 4GB Chip LPDDR3 1867MT/s          | 1         | 1.2%    |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s       | 1         | 1.2%    |
| Patriot RAM PSD48G266681 8GB DIMM DDR4 2934MT/s               | 1         | 1.2%    |
| Micron RAM 8ATF51264HZ-2G1B1 4GB SODIMM DDR4 2667MT/s         | 1         | 1.2%    |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s          | 1         | 1.2%    |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s   | 1         | 1.2%    |
| Micron RAM 16JTF1G64AZ-1G6D1 8GB DIMM DDR3 1600MT/s           | 1         | 1.2%    |
| Kingston RAM MSI26D4S9S8ME-8 8192MB SODIMM DDR4 2667MT/s      | 1         | 1.2%    |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s             | 1         | 1.2%    |
| Kingston RAM KHX1866C10D3/8G 8192MB DIMM DDR3 1867MT/s        | 1         | 1.2%    |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s           | 1         | 1.2%    |
| Kingston RAM ACR16D3LS1KFG/8G 8GB SODIMM DDR3 1600MT/s        | 1         | 1.2%    |
| Kingston RAM 99U5474-016.A00LF 4GB DIMM DDR3 1333MT/s         | 1         | 1.2%    |
| Kingston RAM 99U5471-040.A00LF 8GB DIMM DDR3 1333MT/s         | 1         | 1.2%    |
| Kingston RAM 9905474-012.A00LF 2048MB DIMM DDR3 1333MT/s      | 1         | 1.2%    |
| Kingston RAM 9905471-028.A00LF 4096MB DIMM DDR3 1333MT/s      | 1         | 1.2%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 34        | 52.31%  |
| DDR3    | 19        | 29.23%  |
| LPDDR4  | 4         | 6.15%   |
| DDR2    | 3         | 4.62%   |
| SDRAM   | 2         | 3.08%   |
| Unknown | 2         | 3.08%   |
| LPDDR3  | 1         | 1.54%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 31        | 47.69%  |
| DIMM         | 31        | 47.69%  |
| Row Of Chips | 2         | 3.08%   |
| Chip         | 1         | 1.54%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 27        | 36%     |
| 4096  | 17        | 22.67%  |
| 16384 | 14        | 18.67%  |
| 2048  | 9         | 12%     |
| 32768 | 5         | 6.67%   |
| 1024  | 3         | 4%      |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 12        | 16.44%  |
| 2667    | 11        | 15.07%  |
| 3200    | 8         | 10.96%  |
| 1333    | 6         | 8.22%   |
| 2133    | 5         | 6.85%   |
| 3600    | 4         | 5.48%   |
| 2400    | 3         | 4.11%   |
| 1867    | 3         | 4.11%   |
| 667     | 3         | 4.11%   |
| 4267    | 1         | 1.37%   |
| 4266    | 1         | 1.37%   |
| 4199    | 1         | 1.37%   |
| 3800    | 1         | 1.37%   |
| 3733    | 1         | 1.37%   |
| 3466    | 1         | 1.37%   |
| 3400    | 1         | 1.37%   |
| 3007    | 1         | 1.37%   |
| 3000    | 1         | 1.37%   |
| 2934    | 1         | 1.37%   |
| 2933    | 1         | 1.37%   |
| 2666    | 1         | 1.37%   |
| 2048    | 1         | 1.37%   |
| 1334    | 1         | 1.37%   |
| 1067    | 1         | 1.37%   |
| 1066    | 1         | 1.37%   |
| 800     | 1         | 1.37%   |
| Unknown | 1         | 1.37%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 2         | 25%     |
| Brother Industries  | 2         | 25%     |
| Samsung Electronics | 1         | 12.5%   |
| Prolific Technology | 1         | 12.5%   |
| Kyocera             | 1         | 12.5%   |
| Canon               | 1         | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Samsung SCX-4200 series       | 1         | 12.5%   |
| Prolific PL2305 Parallel Port | 1         | 12.5%   |
| Kyocera FS-1030D printer      | 1         | 12.5%   |
| HP ENVY 4500 series           | 1         | 12.5%   |
| HP DeskJet 6940 series        | 1         | 12.5%   |
| Canon CanoScan LiDE 300       | 1         | 12.5%   |
| Brother Printer               | 1         | 12.5%   |
| Brother HL-L3210CW series     | 1         | 12.5%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Canon       | 3         | 75%     |
| Seiko Epson | 1         | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Seiko Epson GT-X770 [Perfection V500] | 1         | 25%     |
| Canon CanoScan N1240U/LiDE 30         | 1         | 25%     |
| Canon CanoScan LiDE 210               | 1         | 25%     |
| Canon CanoScan LiDE 110               | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 10        | 17.24%  |
| Logitech                               | 8         | 13.79%  |
| Acer                                   | 6         | 10.34%  |
| Realtek Semiconductor                  | 5         | 8.62%   |
| Sunplus Innovation Technology          | 4         | 6.9%    |
| Quanta                                 | 4         | 6.9%    |
| IMC Networks                           | 4         | 6.9%    |
| Cheng Uei Precision Industry (Foxlink) | 4         | 6.9%    |
| Microdia                               | 3         | 5.17%   |
| Lite-On Technology                     | 2         | 3.45%   |
| Z-Star Microelectronics                | 1         | 1.72%   |
| Syntek                                 | 1         | 1.72%   |
| Silicon Motion                         | 1         | 1.72%   |
| Ricoh                                  | 1         | 1.72%   |
| Microsoft                              | 1         | 1.72%   |
| Luxvisions Innotech Limited            | 1         | 1.72%   |
| Creative Technology                    | 1         | 1.72%   |
| ALi                                    | 1         | 1.72%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                | 4         | 6.78%   |
| Logitech Webcam C270                                                     | 3         | 5.08%   |
| Sunplus HD WebCam                                                        | 2         | 3.39%   |
| Realtek Integrated_Webcam_HD                                             | 2         | 3.39%   |
| Microdia Integrated_Webcam_HD                                            | 2         | 3.39%   |
| Logitech HD Pro Webcam C920                                              | 2         | 3.39%   |
| Logitech B525 HD Webcam                                                  | 2         | 3.39%   |
| Acer Integrated Camera                                                   | 2         | 3.39%   |
| Acer BisonCam, NB Pro                                                    | 2         | 3.39%   |
| Z-Star Venus USB2.0 Camera                                               | 1         | 1.69%   |
| Syntek Lenovo EasyCamera                                                 | 1         | 1.69%   |
| Sunplus Integrated_Webcam_HD                                             | 1         | 1.69%   |
| Sunplus 1.3M HD WebCam                                                   | 1         | 1.69%   |
| Silicon Motion WebCam SC-13HDN10939N                                     | 1         | 1.69%   |
| Ricoh Sony Vaio Integrated Webcam                                        | 1         | 1.69%   |
| Realtek USB2.0 HD UVC WebCam                                             | 1         | 1.69%   |
| Realtek USB Camera                                                       | 1         | 1.69%   |
| Realtek Lenovo EasyCamera                                                | 1         | 1.69%   |
| Realtek Integrated Webcam HD                                             | 1         | 1.69%   |
| Quanta HP Wide Vision HD Camera                                          | 1         | 1.69%   |
| Quanta HP TrueVision HD Camera                                           | 1         | 1.69%   |
| Quanta HD Webcam                                                         | 1         | 1.69%   |
| Quanta HD User Facing                                                    | 1         | 1.69%   |
| Microsoft LifeCam VX-700                                                 | 1         | 1.69%   |
| Microdia Laptop_Integrated_Webcam_7645BB9590586C77DC683CD9114697FF.3M    | 1         | 1.69%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                      | 1         | 1.69%   |
| Logitech Webcam C250                                                     | 1         | 1.69%   |
| Lite-On Integrated Camera                                                | 1         | 1.69%   |
| Lite-On HP 5MP Camera                                                    | 1         | 1.69%   |
| IMC Networks USB2.0 VGA UVC WebCam                                       | 1         | 1.69%   |
| IMC Networks USB2.0 UVC HD Webcam                                        | 1         | 1.69%   |
| IMC Networks USB2.0 HD UVC WebCam                                        | 1         | 1.69%   |
| IMC Networks Integrated Camera                                           | 1         | 1.69%   |
| Creative Live! Cam Sync 1080p                                            | 1         | 1.69%   |
| Chicony VGA 24fps UVC Webcam                                             | 1         | 1.69%   |
| Chicony USB2.0 Camera                                                    | 1         | 1.69%   |
| Chicony Integrated Camera (1280x720@30)                                  | 1         | 1.69%   |
| Chicony HP Webcam                                                        | 1         | 1.69%   |
| Chicony HD WebCam                                                        | 1         | 1.69%   |
| Chicony EasyCamera                                                       | 1         | 1.69%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                            | 1         | 1.69%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                      | 1         | 1.69%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 1         | 1.69%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera                         | 1         | 1.69%   |
| ALi Gateway Webcam                                                       | 1         | 1.69%   |
| Acer HD Webcam                                                           | 1         | 1.69%   |
| Acer BisonCam,NB Pro                                                     | 1         | 1.69%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 5         | 41.67%  |
| Validity Sensors           | 4         | 33.33%  |
| Upek                       | 1         | 8.33%   |
| Shenzhen Goodix Technology | 1         | 8.33%   |
| AuthenTec                  | 1         | 8.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor           | 2         | 16.67%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 2         | 16.67%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 8.33%   |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 8.33%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 8.33%   |
| Synaptics  WBDI                                        | 1         | 8.33%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 8.33%   |
| Shenzhen Goodix  Fingerprint Device                    | 1         | 8.33%   |
| AuthenTec AES1660 Fingerprint Sensor                   | 1         | 8.33%   |
| Unknown                                                | 1         | 8.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 2         | 33.33%  |
| Alcor Micro           | 2         | 33.33%  |
| O2 Micro              | 1         | 16.67%  |
| Gemalto (was Gemplus) | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader               | 2         | 33.33%  |
| O2 Micro OZ776 CCID Smartcard Reader              | 1         | 16.67%  |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 1         | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor    | 1         | 16.67%  |
| Broadcom 5880                                     | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 70        | 68.63%  |
| 1     | 27        | 26.47%  |
| 2     | 5         | 4.9%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 12        | 32.43%  |
| Graphics card            | 9         | 24.32%  |
| Chipcard                 | 7         | 18.92%  |
| Net/wireless             | 4         | 10.81%  |
| Unassigned class         | 2         | 5.41%   |
| Communication controller | 1         | 2.7%    |
| Camera                   | 1         | 2.7%    |
| Bluetooth                | 1         | 2.7%    |

