openSUSE Leap-15.3 - Tested Hardware & Statistics
-------------------------------------------------

A project to collect tested hardware configurations for openSUSE Leap-15.3.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/openSUSE_Leap-15.3/Desktop/README.md) and [notebooks](/Dist/openSUSE_Leap-15.3/Notebook/README.md).

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

Total: 177

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [9de0586493](https://linux-hardware.org/?probe=9de0586493) | Jul 01, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [8c7b7c1b45](https://linux-hardware.org/?probe=8c7b7c1b45) | Jul 01, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [3b177fe0af](https://linux-hardware.org/?probe=3b177fe0af) | Jun 17, 2022 |
| HP            | Mini 210-1000               | Notebook    | [65b65f1319](https://linux-hardware.org/?probe=65b65f1319) | Jun 08, 2022 |
| Lenovo        | 1036 SDK0K17763 WIN 1801... | Desktop     | [325cde32e5](https://linux-hardware.org/?probe=325cde32e5) | Jun 06, 2022 |
| Lenovo        | 1036 SDK0K17763 WIN 1801... | Desktop     | [6abee365c1](https://linux-hardware.org/?probe=6abee365c1) | Jun 06, 2022 |
| ASUSTek       | G771JW                      | Notebook    | [b6c03572a0](https://linux-hardware.org/?probe=b6c03572a0) | May 31, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [7fe5175e37](https://linux-hardware.org/?probe=7fe5175e37) | May 30, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [66b453536a](https://linux-hardware.org/?probe=66b453536a) | May 24, 2022 |
| HP            | 2820h                       | Desktop     | [af311c3a41](https://linux-hardware.org/?probe=af311c3a41) | May 18, 2022 |
| HP            | 250 G3                      | Notebook    | [73dbcb9953](https://linux-hardware.org/?probe=73dbcb9953) | May 17, 2022 |
| HP            | 250 G3                      | Notebook    | [a12d6710cf](https://linux-hardware.org/?probe=a12d6710cf) | May 16, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [b31c3ee2d6](https://linux-hardware.org/?probe=b31c3ee2d6) | May 14, 2022 |
| Lenovo        | ThinkPad T470 20HES1RB06    | Notebook    | [0d115ce977](https://linux-hardware.org/?probe=0d115ce977) | May 14, 2022 |
| ASRock        | Z390 Extreme4               | Desktop     | [4142d08db8](https://linux-hardware.org/?probe=4142d08db8) | May 11, 2022 |
| Gigabyte      | B560 HD3                    | Desktop     | [34fd3f60c4](https://linux-hardware.org/?probe=34fd3f60c4) | May 11, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [699a7ea54b](https://linux-hardware.org/?probe=699a7ea54b) | May 04, 2022 |
| ASRock        | Z390 Extreme4               | Desktop     | [344c43c31a](https://linux-hardware.org/?probe=344c43c31a) | May 04, 2022 |
| Fujitsu       | LIFEBOOK S762               | Notebook    | [e168087bf0](https://linux-hardware.org/?probe=e168087bf0) | Apr 28, 2022 |
| Fujitsu       | LIFEBOOK S762               | Notebook    | [c258235d05](https://linux-hardware.org/?probe=c258235d05) | Apr 28, 2022 |
| Lenovo        | Yoga 730-15IKB 81CU         | Convertible | [26727e92e4](https://linux-hardware.org/?probe=26727e92e4) | Apr 22, 2022 |
| HP            | Notebook                    | Notebook    | [65e86d0311](https://linux-hardware.org/?probe=65e86d0311) | Apr 21, 2022 |
| Dell          | System Inspiron N7110       | Notebook    | [aa67c47f23](https://linux-hardware.org/?probe=aa67c47f23) | Apr 13, 2022 |
| ASUSTek       | H81M-R                      | Desktop     | [34fa61f6bd](https://linux-hardware.org/?probe=34fa61f6bd) | Apr 11, 2022 |
| MSI           | Modern 15 A4M               | Notebook    | [a5837a7f35](https://linux-hardware.org/?probe=a5837a7f35) | Apr 11, 2022 |
| MSI           | Modern 15 A4M               | Notebook    | [085aa2eabf](https://linux-hardware.org/?probe=085aa2eabf) | Apr 10, 2022 |
| Lenovo        | 1036 SDK0K17763 WIN 1801... | Desktop     | [eec98977a3](https://linux-hardware.org/?probe=eec98977a3) | Apr 05, 2022 |
| Shuttle       | FS35V4                      | Desktop     | [bfe34cde0c](https://linux-hardware.org/?probe=bfe34cde0c) | Apr 04, 2022 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [0fd3382ba7](https://linux-hardware.org/?probe=0fd3382ba7) | Apr 02, 2022 |
| Itautec       | SM 3330 SM-3330 Padrao 0... | Desktop     | [47e5e82b88](https://linux-hardware.org/?probe=47e5e82b88) | Apr 01, 2022 |
| ASUSTek       | H81M-R                      | Desktop     | [6fffff17df](https://linux-hardware.org/?probe=6fffff17df) | Mar 27, 2022 |
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
| Notebook      | PCx0Dx                      | Notebook    | [07b8344de7](https://linux-hardware.org/?probe=07b8344de7) | Jan 21, 2022 |
| Notebook      | PCx0Dx                      | Notebook    | [3bdae5c5ac](https://linux-hardware.org/?probe=3bdae5c5ac) | Jan 21, 2022 |
| ASUSTek       | H81M-R                      | Desktop     | [ea01dd4007](https://linux-hardware.org/?probe=ea01dd4007) | Jan 18, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [88d5bd947a](https://linux-hardware.org/?probe=88d5bd947a) | Jan 17, 2022 |
| ASUSTek       | H81M-R                      | Desktop     | [cf10bab7ad](https://linux-hardware.org/?probe=cf10bab7ad) | Jan 17, 2022 |
| Biostar       | H77MU3                      | Desktop     | [da779dbb31](https://linux-hardware.org/?probe=da779dbb31) | Jan 15, 2022 |
| ASUSTek       | H97M-E                      | Desktop     | [abf3b9c5c8](https://linux-hardware.org/?probe=abf3b9c5c8) | Jan 14, 2022 |
| ASUSTek       | H97M-E                      | Desktop     | [54fb155ee1](https://linux-hardware.org/?probe=54fb155ee1) | Jan 14, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [894589da9f](https://linux-hardware.org/?probe=894589da9f) | Jan 11, 2022 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [cda49a0b67](https://linux-hardware.org/?probe=cda49a0b67) | Jan 10, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [4c9489e27a](https://linux-hardware.org/?probe=4c9489e27a) | Jan 10, 2022 |
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
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [0c01b21401](https://linux-hardware.org/?probe=0c01b21401) | Jun 15, 2021 |
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

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                             | Computers | Percent |
|-------------------------------------|-----------|---------|
| 5.3.18-59.37-default                | 18        | 13.95%  |
| 5.3.18-59.27-default                | 13        | 10.08%  |
| 5.3.18-59.19-default                | 13        | 10.08%  |
| 5.3.18-57-default                   | 8         | 6.2%    |
| 5.3.18-150300.59.49-default         | 7         | 5.43%   |
| 5.3.18-59.5-default                 | 6         | 4.65%   |
| 5.3.18-59.24-default                | 6         | 4.65%   |
| 5.3.18-59.16-default                | 6         | 4.65%   |
| 5.3.18-150300.59.54-default         | 6         | 4.65%   |
| 5.3.18-59.10-default                | 5         | 3.88%   |
| 5.3.18-150300.59.63-default         | 5         | 3.88%   |
| 5.3.18-59.34-default                | 4         | 3.1%    |
| 5.3.18-150300.59.60-default         | 4         | 3.1%    |
| 5.3.18-150300.59.43-default         | 3         | 2.33%   |
| 5.3.18-59.27-preempt                | 2         | 1.55%   |
| 5.3.18-59.19-preempt                | 2         | 1.55%   |
| 5.3.18-59.13-default                | 2         | 1.55%   |
| 5.3.18-150300.59.68-default         | 2         | 1.55%   |
| 5.3.18-lp152.57-default             | 1         | 0.78%   |
| 5.3.18-59.37-preempt                | 1         | 0.78%   |
| 5.3.18-59.34-preempt                | 1         | 0.78%   |
| 5.3.18-59.24-preempt                | 1         | 0.78%   |
| 5.3.18-57-preempt                   | 1         | 0.78%   |
| 5.3.18-56-default                   | 1         | 0.78%   |
| 5.3.18-52-default                   | 1         | 0.78%   |
| 5.3.18-46-default                   | 1         | 0.78%   |
| 5.3.18-150300.59.71-default         | 1         | 0.78%   |
| 5.3.18-150300.59.63-preempt         | 1         | 0.78%   |
| 5.3.18-150300.59.60-preempt         | 1         | 0.78%   |
| 5.3.18-150300.59.49-preempt         | 1         | 0.78%   |
| 5.17.2-1.gb49cf22-default           | 1         | 0.78%   |
| 5.17.2-1-default                    | 1         | 0.78%   |
| 5.16.0-rc2-lp153.2.g696d453-default | 1         | 0.78%   |
| 5.15.11-lp153.3.g730a488-default    | 1         | 0.78%   |
| 4.12.14-197.105-vanilla             | 1         | 0.78%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.3.18  | 114       | 95.8%   |
| 5.17.2  | 2         | 1.68%   |
| 5.16.0  | 1         | 0.84%   |
| 5.15.11 | 1         | 0.84%   |
| 4.12.14 | 1         | 0.84%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.3     | 114       | 95.8%   |
| 5.17    | 2         | 1.68%   |
| 5.16    | 1         | 0.84%   |
| 5.15    | 1         | 0.84%   |
| 4.12    | 1         | 0.84%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 118       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| KDE5       | 54        | 44.26%  |
| GNOME      | 18        | 14.75%  |
| KDE        | 17        | 13.93%  |
| Unknown    | 14        | 11.48%  |
| XFCE       | 12        | 9.84%   |
| X-Cinnamon | 3         | 2.46%   |
| plasma5    | 1         | 0.82%   |
| MATE       | 1         | 0.82%   |
| LXDE       | 1         | 0.82%   |
| ICEWM      | 1         | 0.82%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 99        | 82.5%   |
| Wayland | 13        | 10.83%  |
| Tty     | 8         | 6.67%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 60        | 49.59%  |
| SDDM    | 29        | 23.97%  |
| LightDM | 26        | 21.49%  |
| XDM     | 5         | 4.13%   |
| GDM     | 1         | 0.83%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 35        | 29.41%  |
| de_DE   | 28        | 23.53%  |
| POSIX   | 12        | 10.08%  |
| pt_BR   | 7         | 5.88%   |
| ru_RU   | 5         | 4.2%    |
| es_ES   | 4         | 3.36%   |
| en_GB   | 4         | 3.36%   |
| fr_FR   | 3         | 2.52%   |
| Unknown | 3         | 2.52%   |
| nl_NL   | 2         | 1.68%   |
| zh_CN   | 1         | 0.84%   |
| tr_TR   | 1         | 0.84%   |
| sv_SE   | 1         | 0.84%   |
| sk_SK   | 1         | 0.84%   |
| pt_PT   | 1         | 0.84%   |
| pl_PL   | 1         | 0.84%   |
| nl_BE   | 1         | 0.84%   |
| it_IT   | 1         | 0.84%   |
| hu_HU   | 1         | 0.84%   |
| hr_HR   | 1         | 0.84%   |
| fi_FI   | 1         | 0.84%   |
| es_MX   | 1         | 0.84%   |
| en_DE   | 1         | 0.84%   |
| en_AU   | 1         | 0.84%   |
| cs_CZ   | 1         | 0.84%   |
| ca_AD   | 1         | 0.84%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 69        | 57.98%  |
| EFI  | 50        | 42.02%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 81        | 68.07%  |
| Ext4    | 32        | 26.89%  |
| Xfs     | 5         | 4.2%    |
| Overlay | 1         | 0.84%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 60        | 49.59%  |
| Unknown | 52        | 42.98%  |
| MBR     | 9         | 7.44%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 99        | 82.5%   |
| Yes       | 21        | 17.5%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 84        | 71.19%  |
| Yes       | 34        | 28.81%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 18        | 15.25%  |
| ASUSTek Computer    | 18        | 15.25%  |
| Hewlett-Packard     | 17        | 14.41%  |
| MSI                 | 13        | 11.02%  |
| Dell                | 12        | 10.17%  |
| Gigabyte Technology | 9         | 7.63%   |
| Acer                | 7         | 5.93%   |
| ASRock              | 6         | 5.08%   |
| Fujitsu             | 3         | 2.54%   |
| TUXEDO              | 2         | 1.69%   |
| Sony                | 2         | 1.69%   |
| VS Company          | 1         | 0.85%   |
| Shuttle             | 1         | 0.85%   |
| Semp Toshiba        | 1         | 0.85%   |
| Samsung Electronics | 1         | 0.85%   |
| Medion              | 1         | 0.85%   |
| Itautec             | 1         | 0.85%   |
| Intel               | 1         | 0.85%   |
| HUAWEI              | 1         | 0.85%   |
| Biostar             | 1         | 0.85%   |
| Apple               | 1         | 0.85%   |
| Alienware           | 1         | 0.85%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                         | Computers | Percent |
|----------------------------------------------|-----------|---------|
| ASUS All Series                              | 3         | 2.54%   |
| VS Company G31T-M                            | 1         | 0.85%   |
| TUXEDO Pulse 15 Gen1                         | 1         | 0.85%   |
| TUXEDO Aura 15 Gen1                          | 1         | 0.85%   |
| Sony VPCSB15GB                               | 1         | 0.85%   |
| Sony VGN-Z570AN                              | 1         | 0.85%   |
| Shuttle XS35V4                               | 1         | 0.85%   |
| Semp Toshiba AS 1301                         | 1         | 0.85%   |
| Samsung 600B4B/600B5B                        | 1         | 0.85%   |
| MSI MS-7D16                                  | 1         | 0.85%   |
| MSI MS-7C34                                  | 1         | 0.85%   |
| MSI MS-7C02                                  | 1         | 0.85%   |
| MSI MS-7B89                                  | 1         | 0.85%   |
| MSI MS-7A38                                  | 1         | 0.85%   |
| MSI MS-7A34                                  | 1         | 0.85%   |
| MSI MS-7A33                                  | 1         | 0.85%   |
| MSI MS-7817                                  | 1         | 0.85%   |
| MSI Modern 15 A4M                            | 1         | 0.85%   |
| MSI GS60 6QE                                 | 1         | 0.85%   |
| MSI GP63 Leopard 8RD                         | 1         | 0.85%   |
| MSI ESPRIMO P1510                            | 1         | 0.85%   |
| MSI CX600                                    | 1         | 0.85%   |
| Medion E6436 MD61150                         | 1         | 0.85%   |
| Lenovo Yoga 730-15IKB 81CU                   | 1         | 0.85%   |
| Lenovo V330-15IKB 81AX                       | 1         | 0.85%   |
| Lenovo ThinkStation P520 30BE008VGE          | 1         | 0.85%   |
| Lenovo ThinkStation P500 30A6S4JU00          | 1         | 0.85%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XW00A7TH   | 1         | 0.85%   |
| Lenovo ThinkPad X1 Carbon 4th 20FB002UMC     | 1         | 0.85%   |
| Lenovo ThinkPad T61 8895W9U                  | 1         | 0.85%   |
| Lenovo ThinkPad T490s 20NYS1XK00             | 1         | 0.85%   |
| Lenovo ThinkPad T470 20HES1RB06              | 1         | 0.85%   |
| Lenovo ThinkPad T460 20FMS75800              | 1         | 0.85%   |
| Lenovo ThinkPad T450s 20BWA06J00             | 1         | 0.85%   |
| Lenovo ThinkPad T14 Gen 1 20UES47F00         | 1         | 0.85%   |
| Lenovo ThinkPad L15 Gen 1 20U4S88000         | 1         | 0.85%   |
| Lenovo ThinkPad E580 20KS001RGE              | 1         | 0.85%   |
| Lenovo IdeaPad 330-15IKB 81DC                | 1         | 0.85%   |
| Lenovo IdeaCentre Y710 Cube-15ISH 90FL004WGE | 1         | 0.85%   |
| Lenovo G500 20236                            | 1         | 0.85%   |
| Lenovo G50-45 80E3                           | 1         | 0.85%   |
| Itautec Infoway SM-3330                      | 1         | 0.85%   |
| Intel DG41WV AAE90316-104                    | 1         | 0.85%   |
| HUAWEI KLVL-WXX9                             | 1         | 0.85%   |
| HP ZBook 17 G2                               | 1         | 0.85%   |
| HP Z840 Workstation                          | 1         | 0.85%   |
| HP xw4400 Workstation                        | 1         | 0.85%   |
| HP Stream Notebook PC 11                     | 1         | 0.85%   |
| HP ProBook x360 11 G5 EE                     | 1         | 0.85%   |
| HP Pavilion Gaming Desktop 790-00xx          | 1         | 0.85%   |
| HP Pavilion Gaming Desktop 690-00xx          | 1         | 0.85%   |
| HP Pavilion dx6500                           | 1         | 0.85%   |
| HP OMEN by Laptop 15-dc1xxx                  | 1         | 0.85%   |
| HP Notebook                                  | 1         | 0.85%   |
| HP Laptop 17-ca1xxx                          | 1         | 0.85%   |
| HP Laptop 15s-eq0xxx                         | 1         | 0.85%   |
| HP ENVY x360 Convertible 13-ag0xxx           | 1         | 0.85%   |
| HP EliteDesk 800 G2 DM 65W                   | 1         | 0.85%   |
| HP Compaq dc5800 Small Form Factor           | 1         | 0.85%   |
| HP 550-a114                                  | 1         | 0.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 10        | 8.47%   |
| Dell Inspiron          | 5         | 4.24%   |
| Acer Aspire            | 5         | 4.24%   |
| HP Pavilion            | 3         | 2.54%   |
| ASUS All               | 3         | 2.54%   |
| Lenovo ThinkStation    | 2         | 1.69%   |
| HP Laptop              | 2         | 1.69%   |
| Gigabyte B550          | 2         | 1.69%   |
| Fujitsu LIFEBOOK       | 2         | 1.69%   |
| Dell Latitude          | 2         | 1.69%   |
| ASUS TUF               | 2         | 1.69%   |
| ASUS ROG               | 2         | 1.69%   |
| ASUS PRIME             | 2         | 1.69%   |
| Acer Nitro             | 2         | 1.69%   |
| VS Company G31T-M      | 1         | 0.85%   |
| TUXEDO Pulse           | 1         | 0.85%   |
| TUXEDO Aura            | 1         | 0.85%   |
| Sony VPCSB15GB         | 1         | 0.85%   |
| Sony VGN-Z570AN        | 1         | 0.85%   |
| Shuttle XS35V4         | 1         | 0.85%   |
| Semp Toshiba AS        | 1         | 0.85%   |
| Samsung 600B4B         | 1         | 0.85%   |
| MSI MS-7D16            | 1         | 0.85%   |
| MSI MS-7C34            | 1         | 0.85%   |
| MSI MS-7C02            | 1         | 0.85%   |
| MSI MS-7B89            | 1         | 0.85%   |
| MSI MS-7A38            | 1         | 0.85%   |
| MSI MS-7A34            | 1         | 0.85%   |
| MSI MS-7A33            | 1         | 0.85%   |
| MSI MS-7817            | 1         | 0.85%   |
| MSI Modern             | 1         | 0.85%   |
| MSI GS60               | 1         | 0.85%   |
| MSI GP63               | 1         | 0.85%   |
| MSI ESPRIMO            | 1         | 0.85%   |
| MSI CX600              | 1         | 0.85%   |
| Medion E6436           | 1         | 0.85%   |
| Lenovo Yoga            | 1         | 0.85%   |
| Lenovo V330-15IKB      | 1         | 0.85%   |
| Lenovo IdeaPad         | 1         | 0.85%   |
| Lenovo IdeaCentre      | 1         | 0.85%   |
| Lenovo G500            | 1         | 0.85%   |
| Lenovo G50-45          | 1         | 0.85%   |
| Itautec Infoway        | 1         | 0.85%   |
| Intel DG41WV           | 1         | 0.85%   |
| HUAWEI KLVL-WXX9       | 1         | 0.85%   |
| HP ZBook               | 1         | 0.85%   |
| HP Z840                | 1         | 0.85%   |
| HP xw4400              | 1         | 0.85%   |
| HP Stream              | 1         | 0.85%   |
| HP ProBook             | 1         | 0.85%   |
| HP OMEN                | 1         | 0.85%   |
| HP Notebook            | 1         | 0.85%   |
| HP ENVY                | 1         | 0.85%   |
| HP EliteDesk           | 1         | 0.85%   |
| HP Compaq              | 1         | 0.85%   |
| HP 550-a114            | 1         | 0.85%   |
| HP 200-5120br          | 1         | 0.85%   |
| Gigabyte GA-880GM-UD2H | 1         | 0.85%   |
| Gigabyte GA-770TA-UD3  | 1         | 0.85%   |
| Gigabyte G31M-ES2C     | 1         | 0.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2018 | 15        | 12.71%  |
| 2019 | 13        | 11.02%  |
| 2020 | 11        | 9.32%   |
| 2014 | 11        | 9.32%   |
| 2012 | 11        | 9.32%   |
| 2017 | 9         | 7.63%   |
| 2021 | 8         | 6.78%   |
| 2015 | 7         | 5.93%   |
| 2011 | 7         | 5.93%   |
| 2010 | 6         | 5.08%   |
| 2016 | 5         | 4.24%   |
| 2013 | 4         | 3.39%   |
| 2009 | 4         | 3.39%   |
| 2008 | 3         | 2.54%   |
| 2007 | 3         | 2.54%   |
| 2006 | 1         | 0.85%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Desktop     | 59        | 50%     |
| Notebook    | 54        | 45.76%  |
| Convertible | 3         | 2.54%   |
| All in one  | 1         | 0.85%   |
| Server      | 1         | 0.85%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 107       | 90.68%  |
| Enabled  | 11        | 9.32%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 118       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 35        | 29.66%  |
| 4.01-8.0    | 21        | 17.8%   |
| 8.01-16.0   | 21        | 17.8%   |
| 3.01-4.0    | 18        | 15.25%  |
| 64.01-256.0 | 10        | 8.47%   |
| 32.01-64.0  | 9         | 7.63%   |
| 1.01-2.0    | 2         | 1.69%   |
| 24.01-32.0  | 1         | 0.85%   |
| 2.01-3.0    | 1         | 0.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 36        | 29.51%  |
| 2.01-3.0   | 33        | 27.05%  |
| 4.01-8.0   | 28        | 22.95%  |
| 3.01-4.0   | 14        | 11.48%  |
| 0.51-1.0   | 5         | 4.1%    |
| 8.01-16.0  | 4         | 3.28%   |
| 32.01-64.0 | 1         | 0.82%   |
| 0.01-0.5   | 1         | 0.82%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 53        | 44.92%  |
| 2      | 40        | 33.9%   |
| 3      | 10        | 8.47%   |
| 4      | 7         | 5.93%   |
| 6      | 3         | 2.54%   |
| 5      | 3         | 2.54%   |
| 9      | 1         | 0.85%   |
| 7      | 1         | 0.85%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 61        | 51.69%  |
| No        | 57        | 48.31%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 108       | 91.53%  |
| No        | 10        | 8.47%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 91        | 76.47%  |
| No        | 28        | 23.53%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 73        | 60.33%  |
| No        | 48        | 39.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Germany     | 29        | 24.58%  |
| USA         | 15        | 12.71%  |
| Brazil      | 12        | 10.17%  |
| Russia      | 6         | 5.08%   |
| Netherlands | 4         | 3.39%   |
| France      | 4         | 3.39%   |
| Australia   | 4         | 3.39%   |
| UK          | 3         | 2.54%   |
| Spain       | 3         | 2.54%   |
| Mexico      | 3         | 2.54%   |
| India       | 3         | 2.54%   |
| Slovakia    | 2         | 1.69%   |
| Nicaragua   | 2         | 1.69%   |
| Japan       | 2         | 1.69%   |
| Hungary     | 2         | 1.69%   |
| Greece      | 2         | 1.69%   |
| Czechia     | 2         | 1.69%   |
| Belgium     | 2         | 1.69%   |
| Turkey      | 1         | 0.85%   |
| Thailand    | 1         | 0.85%   |
| Sweden      | 1         | 0.85%   |
| Sudan       | 1         | 0.85%   |
| Romania     | 1         | 0.85%   |
| Portugal    | 1         | 0.85%   |
| Poland      | 1         | 0.85%   |
| Peru        | 1         | 0.85%   |
| Luxembourg  | 1         | 0.85%   |
| Italy       | 1         | 0.85%   |
| Finland     | 1         | 0.85%   |
| Estonia     | 1         | 0.85%   |
| Croatia     | 1         | 0.85%   |
| China       | 1         | 0.85%   |
| Canada      | 1         | 0.85%   |
| Bulgaria    | 1         | 0.85%   |
| Austria     | 1         | 0.85%   |
| Andorra     | 1         | 0.85%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Sao Paulo             | 4         | 3.31%   |
| Moscow                | 3         | 2.48%   |
| Halle                 | 3         | 2.48%   |
| Wesel                 | 2         | 1.65%   |
| Tokyo                 | 2         | 1.65%   |
| Sydney                | 2         | 1.65%   |
| Stolk                 | 2         | 1.65%   |
| Managua               | 2         | 1.65%   |
| Lehrte                | 2         | 1.65%   |
| Chapecó              | 2         | 1.65%   |
| Berlin                | 2         | 1.65%   |
| Zagreb                | 1         | 0.83%   |
| Weilheim              | 1         | 0.83%   |
| Waltham               | 1         | 0.83%   |
| Vijayawada            | 1         | 0.83%   |
| Vienna                | 1         | 0.83%   |
| Veresegyhaz           | 1         | 0.83%   |
| Vaennaes              | 1         | 0.83%   |
| Três Lagoas          | 1         | 0.83%   |
| The Hague             | 1         | 0.83%   |
| Teresina              | 1         | 0.83%   |
| Tallinn               | 1         | 0.83%   |
| Tacna                 | 1         | 0.83%   |
| Sterling              | 1         | 0.83%   |
| Stargard              | 1         | 0.83%   |
| Southampton           | 1         | 0.83%   |
| Sofia                 | 1         | 0.83%   |
| San Luis Potosí City | 1         | 0.83%   |
| Samorin               | 1         | 0.83%   |
| Saalfeld              | 1         | 0.83%   |
| Rotterdam             | 1         | 0.83%   |
| Rottenburg            | 1         | 0.83%   |
| Rockville             | 1         | 0.83%   |
| Rio de Janeiro        | 1         | 0.83%   |
| Rio Branco            | 1         | 0.83%   |
| Recife                | 1         | 0.83%   |
| Prosper               | 1         | 0.83%   |
| Prague                | 1         | 0.83%   |
| Phuket                | 1         | 0.83%   |
| Petrozavodsk          | 1         | 0.83%   |
| Peine                 | 1         | 0.83%   |
| Paris                 | 1         | 0.83%   |
| Palm Bay              | 1         | 0.83%   |
| Oulu                  | 1         | 0.83%   |
| Nordenham             | 1         | 0.83%   |
| Munich                | 1         | 0.83%   |
| Montreal              | 1         | 0.83%   |
| Monterrey             | 1         | 0.83%   |
| Moelan-sur-Mer        | 1         | 0.83%   |
| Miami                 | 1         | 0.83%   |
| Melbourne             | 1         | 0.83%   |
| McDonough             | 1         | 0.83%   |
| Mansfield             | 1         | 0.83%   |
| Madrid                | 1         | 0.83%   |
| Madison               | 1         | 0.83%   |
| Luxembourg            | 1         | 0.83%   |
| London                | 1         | 0.83%   |
| Lomonosov             | 1         | 0.83%   |
| Lier                  | 1         | 0.83%   |
| León                 | 1         | 0.83%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 39        | 57     | 19.31%  |
| Seagate             | 36        | 59     | 17.82%  |
| Samsung Electronics | 36        | 58     | 17.82%  |
| Kingston            | 16        | 19     | 7.92%   |
| Toshiba             | 10        | 11     | 4.95%   |
| SanDisk             | 9         | 10     | 4.46%   |
| Hitachi             | 7         | 10     | 3.47%   |
| Crucial             | 6         | 6      | 2.97%   |
| Unknown             | 5         | 5      | 2.48%   |
| SK hynix            | 5         | 5      | 2.48%   |
| HGST                | 4         | 5      | 1.98%   |
| A-DATA Technology   | 4         | 4      | 1.98%   |
| Micron Technology   | 3         | 4      | 1.49%   |
| Intel               | 3         | 3      | 1.49%   |
| Silicon Motion      | 2         | 2      | 0.99%   |
| Phison              | 2         | 2      | 0.99%   |
| Fujitsu             | 2         | 2      | 0.99%   |
| TO Exter            | 1         | 1      | 0.5%    |
| SSSTC               | 1         | 1      | 0.5%    |
| Plextor             | 1         | 2      | 0.5%    |
| LITEON              | 1         | 1      | 0.5%    |
| Lite-On             | 1         | 1      | 0.5%    |
| JMicron Technology  | 1         | 1      | 0.5%    |
| Intenso             | 1         | 1      | 0.5%    |
| Inateck             | 1         | 1      | 0.5%    |
| HGST HTS            | 1         | 1      | 0.5%    |
| Corsair             | 1         | 1      | 0.5%    |
| China               | 1         | 1      | 0.5%    |
| Apple               | 1         | 1      | 0.5%    |
| Apacer              | 1         | 3      | 0.5%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB             | 3         | 1.33%   |
| WDC WDS500G1X0E-00AFY0 500GB          | 2         | 0.89%   |
| WDC WDS480G2G0A-00JH30 480GB SSD      | 2         | 0.89%   |
| WDC WD5000AAKX-07U6AA0 500GB          | 2         | 0.89%   |
| WDC WD10EAVS-22D7B0 1TB               | 2         | 0.89%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 2         | 0.89%   |
| Silicon Motion NVMe SSD Drive 512GB   | 2         | 0.89%   |
| Seagate ST3750528AS 752GB             | 2         | 0.89%   |
| Seagate ST3500418AS 500GB             | 2         | 0.89%   |
| Seagate ST3500413AS 500GB             | 2         | 0.89%   |
| Seagate ST2000DM008-2FR102 2TB        | 2         | 0.89%   |
| Seagate ST2000DM006-2DM164 2TB        | 2         | 0.89%   |
| Seagate ST2000DM001-9YN164 2TB        | 2         | 0.89%   |
| Seagate ST2000DM001-1ER164 2TB        | 2         | 0.89%   |
| Seagate ST1000LM035-1RK172 1TB        | 2         | 0.89%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 2         | 0.89%   |
| Seagate ST1000DM010-2EP102 1TB        | 2         | 0.89%   |
| Samsung SSD 980 PRO 1TB               | 2         | 0.89%   |
| Samsung SSD 970 EVO 1TB               | 2         | 0.89%   |
| Samsung SSD 870 QVO 1TB               | 2         | 0.89%   |
| Samsung SSD 860 EVO 250GB             | 2         | 0.89%   |
| Samsung SSD 860 EVO 1TB               | 2         | 0.89%   |
| Samsung SSD 850 EVO 500GB             | 2         | 0.89%   |
| Samsung NVMe SSD Drive 1TB            | 2         | 0.89%   |
| Samsung HD105SI 1TB                   | 2         | 0.89%   |
| Samsung HD103SI 1TB                   | 2         | 0.89%   |
| Kingston SV300S37A120G 120GB SSD      | 2         | 0.89%   |
| Kingston SA400S37120G 120GB SSD       | 2         | 0.89%   |
| Hitachi HDS5C3020ALA632 2TB           | 2         | 0.89%   |
| HGST HTS721010A9E630 1TB              | 2         | 0.89%   |
| Fujitsu MHW2120BH 120GB               | 2         | 0.89%   |
| WDC WDS500G2B0A 500GB SSD             | 1         | 0.44%   |
| WDC WDS500G1B0B-00AS40 500GB SSD      | 1         | 0.44%   |
| WDC WDS250G1B0C-00S6U0 250GB          | 1         | 0.44%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD      | 1         | 0.44%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD      | 1         | 0.44%   |
| WDC WDS200T2B0A-00SM50 2TB SSD        | 1         | 0.44%   |
| WDC WDS100T3X0C-00SJG0 1TB            | 1         | 0.44%   |
| WDC WDS100T1X0E-00AFY0 1TB            | 1         | 0.44%   |
| WDC WD800BEVS-60RST0 80GB             | 1         | 0.44%   |
| WDC WD7500AALX-009BA0 752GB           | 1         | 0.44%   |
| WDC WD5000LPVX-00V0TT0 500GB          | 1         | 0.44%   |
| WDC WD5000LPLX-66ZNTT1 500GB          | 1         | 0.44%   |
| WDC WD5000LPCX-60VHAT0 500GB          | 1         | 0.44%   |
| WDC WD5000AAVS-00ZTB0 500GB           | 1         | 0.44%   |
| WDC WD5000AAKX-08U6AA0 500GB          | 1         | 0.44%   |
| WDC WD50 00LPCX-00VHAT0 500GB         | 1         | 0.44%   |
| WDC WD40EZRZ-00GXCB0 4TB              | 1         | 0.44%   |
| WDC WD40EZAZ-00SF3B0 4TB              | 1         | 0.44%   |
| WDC WD3200BEVT-22ZCT0 320GB           | 1         | 0.44%   |
| WDC WD3200AAKS-00B3A0 320GB           | 1         | 0.44%   |
| WDC WD3200AAJS-56M0A0 320GB           | 1         | 0.44%   |
| WDC WD2500BEVT-60ZCT1 250GB           | 1         | 0.44%   |
| WDC WD2500AAJS-00VTA0 250GB           | 1         | 0.44%   |
| WDC WD20EARX-00PASB0 2TB              | 1         | 0.44%   |
| WDC WD2005FBYZ-01YCBB2 2TB            | 1         | 0.44%   |
| WDC WD15EARS-00MVWB0 1TB              | 1         | 0.44%   |
| WDC WD10SPZX-60Z10T0 1TB              | 1         | 0.44%   |
| WDC WD10SPZX-24Z10 1TB                | 1         | 0.44%   |
| WDC WD10SPZX-17Z10T0 1TB              | 1         | 0.44%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 36        | 58     | 37.89%  |
| WDC                 | 30        | 44     | 31.58%  |
| Samsung Electronics | 7         | 13     | 7.37%   |
| Hitachi             | 7         | 10     | 7.37%   |
| Toshiba             | 6         | 7      | 6.32%   |
| HGST                | 4         | 5      | 4.21%   |
| Fujitsu             | 2         | 2      | 2.11%   |
| Unknown             | 1         | 1      | 1.05%   |
| JMicron Technology  | 1         | 1      | 1.05%   |
| Inateck             | 1         | 1      | 1.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 15        | 23     | 22.73%  |
| Kingston            | 12        | 15     | 18.18%  |
| SanDisk             | 9         | 10     | 13.64%  |
| WDC                 | 7         | 7      | 10.61%  |
| A-DATA Technology   | 4         | 4      | 6.06%   |
| Toshiba             | 3         | 3      | 4.55%   |
| Crucial             | 3         | 3      | 4.55%   |
| SK hynix            | 2         | 2      | 3.03%   |
| Intel               | 2         | 2      | 3.03%   |
| TO Exter            | 1         | 1      | 1.52%   |
| SSSTC               | 1         | 1      | 1.52%   |
| Plextor             | 1         | 2      | 1.52%   |
| Micron Technology   | 1         | 2      | 1.52%   |
| LITEON              | 1         | 1      | 1.52%   |
| Intenso             | 1         | 1      | 1.52%   |
| China               | 1         | 1      | 1.52%   |
| Apple               | 1         | 1      | 1.52%   |
| Apacer              | 1         | 3      | 1.52%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 74        | 142    | 42.05%  |
| SSD     | 59        | 82     | 33.52%  |
| NVMe    | 38        | 48     | 21.59%  |
| MMC     | 4         | 4      | 2.27%   |
| Unknown | 1         | 2      | 0.57%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 98        | 218    | 67.59%  |
| NVMe | 38        | 48     | 26.21%  |
| SAS  | 5         | 8      | 3.45%   |
| MMC  | 4         | 4      | 2.76%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 67        | 104    | 46.53%  |
| 0.51-1.0   | 50        | 75     | 34.72%  |
| 1.01-2.0   | 18        | 29     | 12.5%   |
| 3.01-4.0   | 3         | 8      | 2.08%   |
| 2.01-3.0   | 2         | 2      | 1.39%   |
| 10.01-20.0 | 2         | 3      | 1.39%   |
| 4.01-10.0  | 2         | 3      | 1.39%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| More than 3000 | 32        | 26.67%  |
| 1001-2000      | 24        | 20%     |
| 501-1000       | 20        | 16.67%  |
| 251-500        | 15        | 12.5%   |
| 2001-3000      | 15        | 12.5%   |
| 51-100         | 4         | 3.33%   |
| Unknown        | 4         | 3.33%   |
| 101-250        | 3         | 2.5%    |
| 1-20           | 2         | 1.67%   |
| 21-50          | 1         | 0.83%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 24        | 19.05%  |
| 251-500        | 22        | 17.46%  |
| 501-1000       | 19        | 15.08%  |
| 51-100         | 18        | 14.29%  |
| 1001-2000      | 13        | 10.32%  |
| 1-20           | 10        | 7.94%   |
| 2001-3000      | 7         | 5.56%   |
| 21-50          | 6         | 4.76%   |
| Unknown        | 4         | 3.17%   |
| More than 3000 | 3         | 2.38%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-00V0TT0 500GB          | 1         | 1      | 7.69%   |
| WDC WD3200AAJS-56M0A0 320GB           | 1         | 1      | 7.69%   |
| WDC WD2500BEVT-60ZCT1 250GB           | 1         | 1      | 7.69%   |
| WDC WD10PURX-64E5EY0 1TB              | 1         | 1      | 7.69%   |
| SSSTC CVB-8D128-HP 128GB SSD          | 1         | 1      | 7.69%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 1         | 1      | 7.69%   |
| Seagate ST9320325AS 320GB             | 1         | 1      | 7.69%   |
| Seagate ST3320620AS 320GB             | 1         | 1      | 7.69%   |
| Seagate ST1000LM035-1RK172 1TB        | 1         | 1      | 7.69%   |
| Seagate ST1000DM003-1CH162 1TB        | 1         | 1      | 7.69%   |
| Phison 311CD0512GB                    | 1         | 1      | 7.69%   |
| Kingston SV300S37A120G 120GB SSD      | 1         | 1      | 7.69%   |
| Crucial CT1000P1SSD8 1TB              | 1         | 1      | 7.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| WDC      | 4         | 4      | 30.77%  |
| Seagate  | 4         | 4      | 30.77%  |
| SSSTC    | 1         | 1      | 7.69%   |
| SK hynix | 1         | 1      | 7.69%   |
| Phison   | 1         | 1      | 7.69%   |
| Kingston | 1         | 1      | 7.69%   |
| Crucial  | 1         | 1      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 4         | 4      | 50%     |
| Seagate | 4         | 4      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 7         | 8      | 58.33%  |
| SSD  | 3         | 3      | 25%     |
| NVMe | 2         | 2      | 16.67%  |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 62        | 127    | 46.97%  |
| Detected | 58        | 138    | 43.94%  |
| Malfunc  | 12        | 13     | 9.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 72        | 45%     |
| AMD                              | 33        | 20.63%  |
| Samsung Electronics              | 16        | 10%     |
| SanDisk                          | 6         | 3.75%   |
| Kingston Technology Company      | 4         | 2.5%    |
| ASMedia Technology               | 4         | 2.5%    |
| Phison Electronics               | 3         | 1.88%   |
| Micron/Crucial Technology        | 3         | 1.88%   |
| Marvell Technology Group         | 3         | 1.88%   |
| SK hynix                         | 2         | 1.25%   |
| Silicon Motion                   | 2         | 1.25%   |
| Micron Technology                | 2         | 1.25%   |
| Lite-On Technology               | 2         | 1.25%   |
| Broadcom / LSI                   | 2         | 1.25%   |
| Toshiba America Info Systems     | 1         | 0.63%   |
| Silicon Integrated Systems [SiS] | 1         | 0.63%   |
| Silicon Image                    | 1         | 0.63%   |
| Seagate Technology               | 1         | 0.63%   |
| Nvidia                           | 1         | 0.63%   |
| JMicron Technology               | 1         | 0.63%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 23        | 12.37%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 10        | 5.38%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 7         | 3.76%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 7         | 3.76%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5         | 2.69%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5         | 2.69%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4         | 2.15%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 4         | 2.15%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 4         | 2.15%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4         | 2.15%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 3         | 1.61%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3         | 1.61%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3         | 1.61%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 3         | 1.61%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3         | 1.61%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 3         | 1.61%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 3         | 1.61%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 2         | 1.08%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2         | 1.08%   |
| Samsung NVMe SSD Controller 980                                                         | 2         | 1.08%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 2         | 1.08%   |
| Micron Non-Volatile memory controller                                                   | 2         | 1.08%   |
| Kingston Company Company Non-Volatile memory controller                                 | 2         | 1.08%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 2         | 1.08%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2         | 1.08%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 2         | 1.08%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 2         | 1.08%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 2         | 1.08%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2         | 1.08%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2         | 1.08%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 1.08%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2         | 1.08%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2         | 1.08%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 2         | 1.08%   |
| AMD X370 Series Chipset SATA Controller                                                 | 2         | 1.08%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2         | 1.08%   |
| AMD 300 Series Chipset SATA Controller                                                  | 2         | 1.08%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                    | 1         | 0.54%   |
| SK hynix Gold P31 SSD                                                                   | 1         | 0.54%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 1         | 0.54%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                             | 1         | 0.54%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                    | 1         | 0.54%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                                    | 1         | 0.54%   |
| Seagate FireCuda 520 SSD                                                                | 1         | 0.54%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 1         | 0.54%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 1         | 0.54%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1         | 0.54%   |
| Samsung Electronics SATA controller                                                     | 1         | 0.54%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1         | 0.54%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1         | 0.54%   |
| Phison E12 NVMe Controller                                                              | 1         | 0.54%   |
| Nvidia MCP61 SATA Controller                                                            | 1         | 0.54%   |
| Nvidia MCP61 IDE                                                                        | 1         | 0.54%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 1         | 0.54%   |
| Marvell Group 88SE912x SATA 6Gb/s Controller [IDE mode]                                 | 1         | 0.54%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo                   | 1         | 0.54%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller                                 | 1         | 0.54%   |
| Lite-On SATA controller                                                                 | 1         | 0.54%   |
| Lite-On Non-Volatile memory controller                                                  | 1         | 0.54%   |
| Kingston Company SNVS2000G [NV1 NVMe PCIe SSD 2TB]                                      | 1         | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 90        | 57.69%  |
| NVMe | 37        | 23.72%  |
| IDE  | 19        | 12.18%  |
| RAID | 9         | 5.77%   |
| SAS  | 1         | 0.64%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 79        | 66.95%  |
| AMD    | 39        | 33.05%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz           | 3         | 2.54%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 3         | 2.54%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 3         | 2.54%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 2         | 1.69%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2         | 1.69%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 2         | 1.69%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 2         | 1.69%   |
| AMD Ryzen 7 4800H with Radeon Graphics      | 2         | 1.69%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2         | 1.69%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 2         | 1.69%   |
| Intel Xeon W-2135 CPU @ 3.70GHz             | 1         | 0.85%   |
| Intel Xeon CPU E5-2687W v2 @ 3.40GHz        | 1         | 0.85%   |
| Intel Xeon CPU E5-2667 v3 @ 3.20GHz         | 1         | 0.85%   |
| Intel Xeon CPU E5-2470 v2 @ 2.40GHz         | 1         | 0.85%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz         | 1         | 0.85%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz    | 1         | 0.85%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 0.85%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1         | 0.85%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1         | 0.85%   |
| Intel Pentium CPU G3258 @ 3.20GHz           | 1         | 0.85%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 1         | 0.85%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 1         | 0.85%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1         | 0.85%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 0.85%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 0.85%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1         | 0.85%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 1         | 0.85%   |
| Intel Core i7-5600U CPU @ 2.60GHz           | 1         | 0.85%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz          | 1         | 0.85%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1         | 0.85%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz          | 1         | 0.85%   |
| Intel Core i7-3740QM CPU @ 2.70GHz          | 1         | 0.85%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1         | 0.85%   |
| Intel Core i5-8365U CPU @ 1.60GHz           | 1         | 0.85%   |
| Intel Core i5-8300H CPU @ 2.30GHz           | 1         | 0.85%   |
| Intel Core i5-7600K CPU @ 3.80GHz           | 1         | 0.85%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 1         | 0.85%   |
| Intel Core i5-7300U CPU @ 2.60GHz           | 1         | 0.85%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 1         | 0.85%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 1         | 0.85%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz          | 1         | 0.85%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 1         | 0.85%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 1         | 0.85%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 1         | 0.85%   |
| Intel Core i5-4440 CPU @ 3.10GHz            | 1         | 0.85%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 1         | 0.85%   |
| Intel Core i5-4200M CPU @ 2.50GHz           | 1         | 0.85%   |
| Intel Core i5-3317U CPU @ 1.70GHz           | 1         | 0.85%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 1         | 0.85%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 0.85%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 1         | 0.85%   |
| Intel Core i5-2400S CPU @ 2.50GHz           | 1         | 0.85%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 1         | 0.85%   |
| Intel Core i5-2320 CPU @ 3.00GHz            | 1         | 0.85%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 1         | 0.85%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 1         | 0.85%   |
| Intel Core i5 CPU M 460 @ 2.53GHz           | 1         | 0.85%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 1         | 0.85%   |
| Intel Core i3-7100U CPU @ 2.40GHz           | 1         | 0.85%   |
| Intel Core i3-6100U CPU @ 2.30GHz           | 1         | 0.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 31        | 26.27%  |
| Intel Core i7           | 17        | 14.41%  |
| AMD Ryzen 7             | 11        | 9.32%   |
| Intel Core i3           | 7         | 5.93%   |
| AMD Ryzen 5             | 7         | 5.93%   |
| AMD Ryzen 9             | 6         | 5.08%   |
| Intel Xeon              | 5         | 4.24%   |
| Intel Core 2 Duo        | 5         | 4.24%   |
| Intel Celeron           | 3         | 2.54%   |
| AMD Phenom II X4        | 3         | 2.54%   |
| Other                   | 2         | 1.69%   |
| Intel Pentium Dual-Core | 2         | 1.69%   |
| Intel Core 2 Quad       | 2         | 1.69%   |
| AMD FX                  | 2         | 1.69%   |
| AMD A6                  | 2         | 1.69%   |
| Intel Pentium Silver    | 1         | 0.85%   |
| Intel Pentium Dual      | 1         | 0.85%   |
| Intel Pentium           | 1         | 0.85%   |
| Intel Core i9           | 1         | 0.85%   |
| Intel Core 2            | 1         | 0.85%   |
| AMD Sempron             | 1         | 0.85%   |
| AMD Ryzen 7 PRO         | 1         | 0.85%   |
| AMD Ryzen 3             | 1         | 0.85%   |
| AMD Phenom II X2        | 1         | 0.85%   |
| AMD C-50                | 1         | 0.85%   |
| AMD Athlon              | 1         | 0.85%   |
| AMD A8                  | 1         | 0.85%   |
| AMD A10                 | 1         | 0.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 44        | 37.29%  |
| 2      | 40        | 33.9%   |
| 8      | 14        | 11.86%  |
| 6      | 11        | 9.32%   |
| 16     | 4         | 3.39%   |
| 12     | 3         | 2.54%   |
| 20     | 1         | 0.85%   |
| 3      | 1         | 0.85%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 116       | 98.31%  |
| 2      | 2         | 1.69%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 76        | 64.41%  |
| 1      | 42        | 35.59%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 118       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 45        | 36.89%  |
| 0x206a7    | 7         | 5.74%   |
| 0x306c3    | 5         | 4.1%    |
| 0x806e9    | 4         | 3.28%   |
| 0x406e3    | 4         | 3.28%   |
| 0x906ea    | 3         | 2.46%   |
| 0x6fd      | 3         | 2.46%   |
| 0x306a9    | 3         | 2.46%   |
| 0x1067a    | 3         | 2.46%   |
| 0x08600106 | 3         | 2.46%   |
| 0xa0653    | 2         | 1.64%   |
| 0x906e9    | 2         | 1.64%   |
| 0x806ea    | 2         | 1.64%   |
| 0x506e3    | 2         | 1.64%   |
| 0x0a201016 | 2         | 1.64%   |
| 0x0a201009 | 2         | 1.64%   |
| 0x08701021 | 2         | 1.64%   |
| 0x08108109 | 2         | 1.64%   |
| 0x08001137 | 2         | 1.64%   |
| 0x07030105 | 2         | 1.64%   |
| 0x010000c8 | 2         | 1.64%   |
| 0x906ec    | 1         | 0.82%   |
| 0x806ec    | 1         | 0.82%   |
| 0x806d1    | 1         | 0.82%   |
| 0x806c1    | 1         | 0.82%   |
| 0x706a8    | 1         | 0.82%   |
| 0x706a1    | 1         | 0.82%   |
| 0x306f2    | 1         | 0.82%   |
| 0x306e4    | 1         | 0.82%   |
| 0x306d4    | 1         | 0.82%   |
| 0x30678    | 1         | 0.82%   |
| 0x20655    | 1         | 0.82%   |
| 0x10677    | 1         | 0.82%   |
| 0x10676    | 1         | 0.82%   |
| 0x0a50000c | 1         | 0.82%   |
| 0x0a201204 | 1         | 0.82%   |
| 0x08108102 | 1         | 0.82%   |
| 0x0810100b | 1         | 0.82%   |
| 0x0800820d | 1         | 0.82%   |
| 0x06000852 | 1         | 0.82%   |
| 0x010000db | 1         | 0.82%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 20        | 16.95%  |
| Haswell       | 11        | 9.32%   |
| Zen 2         | 9         | 7.63%   |
| Skylake       | 9         | 7.63%   |
| SandyBridge   | 8         | 6.78%   |
| IvyBridge     | 8         | 6.78%   |
| Zen 3         | 7         | 5.93%   |
| Zen+          | 6         | 5.08%   |
| Penryn        | 6         | 5.08%   |
| Zen           | 5         | 4.24%   |
| Core          | 5         | 4.24%   |
| K10           | 4         | 3.39%   |
| Westmere      | 2         | 1.69%   |
| Silvermont    | 2         | 1.69%   |
| Puma          | 2         | 1.69%   |
| Piledriver    | 2         | 1.69%   |
| Goldmont plus | 2         | 1.69%   |
| CometLake     | 2         | 1.69%   |
| TigerLake     | 1         | 0.85%   |
| Steamroller   | 1         | 0.85%   |
| Nehalem       | 1         | 0.85%   |
| K10 Llano     | 1         | 0.85%   |
| Jaguar        | 1         | 0.85%   |
| Icelake       | 1         | 0.85%   |
| Broadwell     | 1         | 0.85%   |
| Bobcat        | 1         | 0.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Intel       | 58        | 40.56%  |
| Nvidia      | 47        | 32.87%  |
| AMD         | 37        | 25.87%  |
| S3 Graphics | 1         | 0.7%    |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6         | 4.11%   |
| Intel HD Graphics 620                                                       | 5         | 3.42%   |
| AMD Renoir                                                                  | 5         | 3.42%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 4         | 2.74%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 4         | 2.74%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 4         | 2.74%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 4         | 2.74%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 4         | 2.74%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 3         | 2.05%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3         | 2.05%   |
| Intel UHD Graphics 620                                                      | 3         | 2.05%   |
| Intel HD Graphics 630                                                       | 3         | 2.05%   |
| Intel HD Graphics 530                                                       | 3         | 2.05%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 3         | 2.05%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2         | 1.37%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2         | 1.37%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2         | 1.37%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 2         | 1.37%   |
| Nvidia GF108 [GeForce GT 630]                                               | 2         | 1.37%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 2         | 1.37%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 1.37%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)         | 2         | 1.37%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)           | 2         | 1.37%   |
| Intel Core Processor Integrated Graphics Controller                         | 2         | 1.37%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 2         | 1.37%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2         | 1.37%   |
| AMD Tonga PRO [Radeon R9 285/380]                                           | 2         | 1.37%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                         | 2         | 1.37%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2         | 1.37%   |
| S3 Graphics 86c764/765 [Trio32/64/64V+]                                     | 1         | 0.68%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 1         | 0.68%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1         | 0.68%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1         | 0.68%   |
| Nvidia GT216 [GeForce GT 220]                                               | 1         | 0.68%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 1         | 0.68%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                 | 1         | 0.68%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1         | 0.68%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 1         | 0.68%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 1         | 0.68%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1         | 0.68%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1         | 0.68%   |
| Nvidia GM204M [GeForce GTX 980M]                                            | 1         | 0.68%   |
| Nvidia GM204M [GeForce GTX 970M]                                            | 1         | 0.68%   |
| Nvidia GM108M [GeForce 940MX]                                               | 1         | 0.68%   |
| Nvidia GM107M [GeForce GTX 960M]                                            | 1         | 0.68%   |
| Nvidia GM107M [GeForce GTX 950M]                                            | 1         | 0.68%   |
| Nvidia GM107GL [Quadro K2200]                                               | 1         | 0.68%   |
| Nvidia GK110GL [Quadro K5200]                                               | 1         | 0.68%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 1         | 0.68%   |
| Nvidia GK104GLM [Quadro K3000M]                                             | 1         | 0.68%   |
| Nvidia GF119 [GeForce GT 520]                                               | 1         | 0.68%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]        | 1         | 0.68%   |
| Nvidia GF100GL [Tesla C2050 / C2070]                                        | 1         | 0.68%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                  | 1         | 0.68%   |
| Nvidia GA106 [GeForce RTX 3060]                                             | 1         | 0.68%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 1         | 0.68%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                          | 1         | 0.68%   |
| Nvidia G98M [GeForce 9300M GS]                                              | 1         | 0.68%   |
| Nvidia G84 [GeForce 8600 GT]                                                | 1         | 0.68%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 1         | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 35        | 29.66%  |
| 1 x Nvidia      | 30        | 25.42%  |
| 1 x AMD         | 29        | 24.58%  |
| Intel + Nvidia  | 15        | 12.71%  |
| Intel + AMD     | 6         | 5.08%   |
| 2 x AMD         | 1         | 0.85%   |
| 1 x S3 Graphics | 1         | 0.85%   |
| AMD + Nvidia    | 1         | 0.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 90        | 75.63%  |
| Proprietary | 24        | 20.17%  |
| Unknown     | 5         | 4.2%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 74        | 60.66%  |
| 1.01-2.0   | 14        | 11.48%  |
| 3.01-4.0   | 8         | 6.56%   |
| 0.01-0.5   | 8         | 6.56%   |
| 7.01-8.0   | 5         | 4.1%    |
| 0.51-1.0   | 5         | 4.1%    |
| 5.01-6.0   | 3         | 2.46%   |
| 8.01-16.0  | 3         | 2.46%   |
| 16.01-24.0 | 2         | 1.64%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Goldstar             | 17        | 12.59%  |
| LG Display           | 15        | 11.11%  |
| Samsung Electronics  | 13        | 9.63%   |
| Chimei Innolux       | 12        | 8.89%   |
| AU Optronics         | 11        | 8.15%   |
| Dell                 | 10        | 7.41%   |
| Hewlett-Packard      | 6         | 4.44%   |
| BOE                  | 6         | 4.44%   |
| BenQ                 | 5         | 3.7%    |
| Ancor Communications | 5         | 3.7%    |
| Philips              | 4         | 2.96%   |
| Lenovo               | 3         | 2.22%   |
| Acer                 | 3         | 2.22%   |
| ViewSonic            | 2         | 1.48%   |
| LG Electronics       | 2         | 1.48%   |
| Iiyama               | 2         | 1.48%   |
| ASUSTek Computer     | 2         | 1.48%   |
| AOC                  | 2         | 1.48%   |
| Vizio                | 1         | 0.74%   |
| TCL                  | 1         | 0.74%   |
| Sony                 | 1         | 0.74%   |
| Sharp                | 1         | 0.74%   |
| Sceptre Tech         | 1         | 0.74%   |
| Medion               | 1         | 0.74%   |
| LG Philips           | 1         | 0.74%   |
| InfoVision           | 1         | 0.74%   |
| Hitachi              | 1         | 0.74%   |
| Fujitsu Siemens      | 1         | 0.74%   |
| Denver               | 1         | 0.74%   |
| CSO                  | 1         | 0.74%   |
| CPT                  | 1         | 0.74%   |
| Apple                | 1         | 0.74%   |
| AGO                  | 1         | 0.74%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| ViewSonic VX3211-2K VSCF634 2560x1440 698x392mm 31.5-inch             | 2         | 1.43%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 1.43%   |
| Hewlett-Packard LV1911 HWP3005 1366x768 410x230mm 18.5-inch           | 2         | 1.43%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 2         | 1.43%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 2         | 1.43%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                | 2         | 1.43%   |
| ASUSTek Computer VG245 AUS24A1 1920x1080 531x299mm 24.0-inch          | 2         | 1.43%   |
| Vizio E60-E3 VIZ1018 3840x2160 1330x748mm 60.1-inch                   | 1         | 0.71%   |
| TCL LCD TV TCL0030 1920x1080 708x398mm 32.0-inch                      | 1         | 0.71%   |
| Sony Nvidia Defaul t Flat Panel SNY06FA 1600x900 360x200mm 16.2-inch  | 1         | 0.71%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch               | 1         | 0.71%   |
| Sceptre Tech Sceptre E19 SPT07A8 1366x768 575x323mm 26.0-inch         | 1         | 0.71%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch     | 1         | 0.71%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 1         | 0.71%   |
| Samsung Electronics SyncMaster SAM0524 1920x1080 480x270mm 21.7-inch  | 1         | 0.71%   |
| Samsung Electronics SyncMaster SAM00A2 1024x768 304x228mm 15.0-inch   | 1         | 0.71%   |
| Samsung Electronics SMS27A850T SAM0887 2560x1440 518x324mm 24.1-inch  | 1         | 0.71%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch  | 1         | 0.71%   |
| Samsung Electronics S34J55x SAM0F72 3440x1440 797x333mm 34.0-inch     | 1         | 0.71%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch     | 1         | 0.71%   |
| Samsung Electronics S23B550 SAM0919 1920x1080 510x287mm 23.0-inch     | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch  | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SEC3449 1366x768 309x174mm 14.0-inch  | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 353x198mm 15.9-inch  | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SDC424B 3840x2160 344x194mm 15.5-inch | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 950x540mm 43.0-inch | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SAM08FC 1366x768 700x390mm 31.5-inch  | 1         | 0.71%   |
| Philips PHL 258B6QU PHL08F5 2560x1440 553x311mm 25.0-inch             | 1         | 0.71%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 1         | 0.71%   |
| Philips 150S PHL0812 1024x768 307x230mm 15.1-inch                     | 1         | 0.71%   |
| Philips 150S PHL0805 1024x768 307x230mm 15.1-inch                     | 1         | 0.71%   |
| Medion MD30999PE MED8928 1440x900 410x256mm 19.0-inch                 | 1         | 0.71%   |
| LG Philips LCD Monitor LPLDB00 1280x800 331x207mm 15.4-inch           | 1         | 0.71%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                     | 1         | 0.71%   |
| LG Electronics LCD Monitor LG TV SSCR 3840x2160                       | 1         | 0.71%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch          | 1         | 0.71%   |
| LG Display LCD Monitor LGD05D8 1920x1080 344x194mm 15.5-inch          | 1         | 0.71%   |
| LG Display LCD Monitor LGD05C0 1920x1080 344x194mm 15.5-inch          | 1         | 0.71%   |
| LG Display LCD Monitor LGD059E 1920x1080 382x215mm 17.3-inch          | 1         | 0.71%   |
| LG Display LCD Monitor LGD053C 1920x1080 309x174mm 14.0-inch          | 1         | 0.71%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch          | 1         | 0.71%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 0.71%   |
| LG Display LCD Monitor LGD04A9 1920x1080 309x174mm 14.0-inch          | 1         | 0.71%   |
| LG Display LCD Monitor LGD0490 1920x1080 309x174mm 14.0-inch          | 1         | 0.71%   |
| LG Display LCD Monitor LGD046C 1920x1080 382x215mm 17.3-inch          | 1         | 0.71%   |
| LG Display LCD Monitor LGD044F 1920x1080 345x194mm 15.6-inch          | 1         | 0.71%   |
| LG Display LCD Monitor LGD02DA 1920x1080 382x215mm 17.3-inch          | 1         | 0.71%   |
| LG Display LCD Monitor LGD01DA 1366x768 294x166mm 13.3-inch           | 1         | 0.71%   |
| Lenovo LEN T27i-10 LEN61C6 1920x1080 598x336mm 27.0-inch              | 1         | 0.71%   |
| Lenovo LEN P27q-10 LEN61A8 2560x1440 597x336mm 27.0-inch              | 1         | 0.71%   |
| Lenovo LCD Monitor LEN4020 1024x768 286x214mm 14.1-inch               | 1         | 0.71%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch           | 1         | 0.71%   |
| Iiyama PL2592H IVM6135 1920x1080 544x303mm 24.5-inch                  | 1         | 0.71%   |
| Iiyama PL2492H IVM612F 1920x1080 527x296mm 23.8-inch                  | 1         | 0.71%   |
| Hitachi X90W D-sub HIT6008 1440x900 410x257mm 19.1-inch               | 1         | 0.71%   |
| Hewlett-Packard LA1951 HWP285A 1280x1024 380x300mm 19.1-inch          | 1         | 0.71%   |
| Hewlett-Packard 27f HPN354A 1920x1080 598x336mm 27.0-inch             | 1         | 0.71%   |
| Hewlett-Packard 27es HWP3326 1920x1080 598x336mm 27.0-inch            | 1         | 0.71%   |
| Hewlett-Packard 22m HPN3576 1920x1080 476x268mm 21.5-inch             | 1         | 0.71%   |
| Goldstar W2261 GSM56CF 1920x1080 530x300mm 24.0-inch                  | 1         | 0.71%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 58        | 46.4%   |
| 1366x768 (WXGA)    | 18        | 14.4%   |
| 3840x2160 (4K)     | 8         | 6.4%    |
| 2560x1440 (QHD)    | 8         | 6.4%    |
| 1920x1200 (WUXGA)  | 5         | 4%      |
| 1600x900 (HD+)     | 5         | 4%      |
| 2560x1080          | 4         | 3.2%    |
| 1024x768 (XGA)     | 4         | 3.2%    |
| 3440x1440          | 3         | 2.4%    |
| 1440x900 (WXGA+)   | 3         | 2.4%    |
| 1280x1024 (SXGA)   | 3         | 2.4%    |
| 1680x1050 (WSXGA+) | 2         | 1.6%    |
| 640x480            | 1         | 0.8%    |
| 3840x2400          | 1         | 0.8%    |
| 2160x1440          | 1         | 0.8%    |
| 1280x800 (WXGA)    | 1         | 0.8%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 31        | 23.48%  |
| 27      | 13        | 9.85%   |
| 21      | 13        | 9.85%   |
| 17      | 10        | 7.58%   |
| 14      | 10        | 7.58%   |
| 24      | 9         | 6.82%   |
| 13      | 7         | 5.3%    |
| 23      | 6         | 4.55%   |
| 34      | 5         | 3.79%   |
| 31      | 3         | 2.27%   |
| 19      | 3         | 2.27%   |
| 18      | 3         | 2.27%   |
| 11      | 3         | 2.27%   |
| Unknown | 3         | 2.27%   |
| 26      | 2         | 1.52%   |
| 25      | 2         | 1.52%   |
| 22      | 2         | 1.52%   |
| 20      | 2         | 1.52%   |
| 84      | 1         | 0.76%   |
| 74      | 1         | 0.76%   |
| 35      | 1         | 0.76%   |
| 32      | 1         | 0.76%   |
| 12      | 1         | 0.76%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 44        | 33.33%  |
| 501-600     | 29        | 21.97%  |
| 401-500     | 23        | 17.42%  |
| 351-400     | 10        | 7.58%   |
| 201-300     | 9         | 6.82%   |
| 701-800     | 6         | 4.55%   |
| 601-700     | 5         | 3.79%   |
| Unknown     | 3         | 2.27%   |
| 1501-2000   | 2         | 1.52%   |
| 801-900     | 1         | 0.76%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 90        | 75%     |
| 16/10   | 12        | 10%     |
| 21/9    | 6         | 5%      |
| 4/3     | 5         | 4.17%   |
| 5/4     | 3         | 2.5%    |
| Unknown | 3         | 2.5%    |
| 3/2     | 1         | 0.83%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 31        | 23.31%  |
| 201-250        | 26        | 19.55%  |
| 301-350        | 14        | 10.53%  |
| 81-90          | 13        | 9.77%   |
| 351-500        | 10        | 7.52%   |
| 121-130        | 8         | 6.02%   |
| 151-200        | 7         | 5.26%   |
| 251-300        | 6         | 4.51%   |
| 141-150        | 5         | 3.76%   |
| 71-80          | 4         | 3.01%   |
| 51-60          | 3         | 2.26%   |
| Unknown        | 3         | 2.26%   |
| More than 1000 | 2         | 1.5%    |
| 91-100         | 1         | 0.75%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 48        | 37.21%  |
| 101-120       | 38        | 29.46%  |
| 121-160       | 32        | 24.81%  |
| 161-240       | 4         | 3.1%    |
| More than 240 | 3         | 2.33%   |
| Unknown       | 3         | 2.33%   |
| 1-50          | 1         | 0.78%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 91        | 76.47%  |
| 2     | 21        | 17.65%  |
| 0     | 5         | 4.2%    |
| 3     | 2         | 1.68%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 72        | 39.56%  |
| Intel                            | 58        | 31.87%  |
| Qualcomm Atheros                 | 17        | 9.34%   |
| Broadcom                         | 9         | 4.95%   |
| Ralink                           | 5         | 2.75%   |
| Broadcom Limited                 | 3         | 1.65%   |
| Samsung Electronics              | 2         | 1.1%    |
| Dell                             | 2         | 1.1%    |
| ASIX Electronics                 | 2         | 1.1%    |
| ZyXEL Communications             | 1         | 0.55%   |
| TP-Link                          | 1         | 0.55%   |
| TOMTOM                           | 1         | 0.55%   |
| Silicon Integrated Systems [SiS] | 1         | 0.55%   |
| Sierra Wireless                  | 1         | 0.55%   |
| Ralink Technology                | 1         | 0.55%   |
| NetXen Incorporated              | 1         | 0.55%   |
| Manta                            | 1         | 0.55%   |
| Lenovo                           | 1         | 0.55%   |
| Edimax Technology                | 1         | 0.55%   |
| D-Link System                    | 1         | 0.55%   |
| AVM                              | 1         | 0.55%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 51        | 23.39%  |
| Intel Wi-Fi 6 AX200                                               | 11        | 5.05%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 3.21%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 2.29%   |
| Intel I211 Gigabit Network Connection                             | 5         | 2.29%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.83%   |
| Intel Wireless 8265 / 8275                                        | 4         | 1.83%   |
| Intel Wireless 8260                                               | 4         | 1.83%   |
| Intel Wireless 7260                                               | 4         | 1.83%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 1.38%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3         | 1.38%   |
| Intel Wireless 3165                                               | 3         | 1.38%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 0.92%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.92%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.92%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 0.92%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 0.92%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 2         | 0.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 0.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 0.92%   |
| Intel Wireless-AC 9260                                            | 2         | 0.92%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 0.92%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.92%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.92%   |
| Intel Ethernet Connection (2) I218-LM                             | 2         | 0.92%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 0.92%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 0.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 0.92%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 0.92%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 0.92%   |
| ZyXEL NWD2205 802.11n Wireless N Adapter [Realtek RTL8192CU]      | 1         | 0.46%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 1         | 0.46%   |
| TOMTOM GO 60                                                      | 1         | 0.46%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.46%   |
| Sierra Wireless MC8305 Modem                                      | 1         | 0.46%   |
| Samsung Kiera                                                     | 1         | 0.46%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.46%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.46%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1         | 0.46%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 0.46%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1         | 0.46%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.46%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.46%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.46%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1         | 0.46%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.46%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.46%   |
| Ralink RT3072 Wireless Adapter                                    | 1         | 0.46%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                              | 1         | 0.46%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                              | 1         | 0.46%   |
| Ralink RT2561/RT61 802.11g PCI                                    | 1         | 0.46%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 0.46%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.46%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.46%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1         | 0.46%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 1         | 0.46%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 1         | 0.46%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.46%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 0.46%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 45        | 47.87%  |
| Realtek Semiconductor | 18        | 19.15%  |
| Qualcomm Atheros      | 11        | 11.7%   |
| Broadcom              | 6         | 6.38%   |
| Ralink                | 5         | 5.32%   |
| ZyXEL Communications  | 1         | 1.06%   |
| TP-Link               | 1         | 1.06%   |
| Sierra Wireless       | 1         | 1.06%   |
| Ralink Technology     | 1         | 1.06%   |
| Edimax Technology     | 1         | 1.06%   |
| Dell                  | 1         | 1.06%   |
| D-Link System         | 1         | 1.06%   |
| Broadcom Limited      | 1         | 1.06%   |
| AVM                   | 1         | 1.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                        | 11        | 11.7%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 4         | 4.26%   |
| Intel Wireless 8265 / 8275                                                 | 4         | 4.26%   |
| Intel Wireless 8260                                                        | 4         | 4.26%   |
| Intel Wireless 7260                                                        | 4         | 4.26%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                 | 3         | 3.19%   |
| Intel Wireless 3165                                                        | 3         | 3.19%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                   | 2         | 2.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                   | 2         | 2.13%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                            | 2         | 2.13%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                            | 2         | 2.13%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                  | 2         | 2.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                 | 2         | 2.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 2         | 2.13%   |
| Intel Wireless-AC 9260                                                     | 2         | 2.13%   |
| Intel Tiger Lake PCH CNVi WiFi                                             | 2         | 2.13%   |
| Intel Cannon Lake PCH CNVi WiFi                                            | 2         | 2.13%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                        | 2         | 2.13%   |
| ZyXEL NWD2205 802.11n Wireless N Adapter [Realtek RTL8192CU]               | 1         | 1.06%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                        | 1         | 1.06%   |
| Sierra Wireless MC8305 Modem                                               | 1         | 1.06%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                   | 1         | 1.06%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                     | 1         | 1.06%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                | 1         | 1.06%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                      | 1         | 1.06%   |
| Realtek RTL8188EE Wireless Network Adapter                                 | 1         | 1.06%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                 | 1         | 1.06%   |
| Ralink RT3072 Wireless Adapter                                             | 1         | 1.06%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                       | 1         | 1.06%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                       | 1         | 1.06%   |
| Ralink RT2561/RT61 802.11g PCI                                             | 1         | 1.06%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                 | 1         | 1.06%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                           | 1         | 1.06%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                           | 1         | 1.06%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                           | 1         | 1.06%   |
| Intel Wireless 7265                                                        | 1         | 1.06%   |
| Intel WiFi Link 5100                                                       | 1         | 1.06%   |
| Intel Wi-Fi 6 AX201                                                        | 1         | 1.06%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection              | 1         | 1.06%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                      | 1         | 1.06%   |
| Intel Gemini Lake PCH CNVi WiFi                                            | 1         | 1.06%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 1         | 1.06%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                            | 1         | 1.06%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                              | 1         | 1.06%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                               | 1         | 1.06%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                              | 1         | 1.06%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                               | 1         | 1.06%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                   | 1         | 1.06%   |
| Edimax EW-7822ULC 802.11ac Wireless Adapter [Realtek RTL8812AU]            | 1         | 1.06%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                                       | 1         | 1.06%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 1         | 1.06%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                 | 1         | 1.06%   |
| Broadcom BCM43228 802.11a/b/g/n                                            | 1         | 1.06%   |
| Broadcom BCM43227 802.11b/g/n                                              | 1         | 1.06%   |
| Broadcom BCM43225 802.11b/g/n                                              | 1         | 1.06%   |
| Broadcom BCM43142 802.11b/g/n                                              | 1         | 1.06%   |
| AVM Fritz!WLAN N v2 [Atheros AR9271]                                       | 1         | 1.06%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 65        | 56.03%  |
| Intel                            | 30        | 25.86%  |
| Qualcomm Atheros                 | 8         | 6.9%    |
| Broadcom                         | 4         | 3.45%   |
| Samsung Electronics              | 2         | 1.72%   |
| Broadcom Limited                 | 2         | 1.72%   |
| ASIX Electronics                 | 2         | 1.72%   |
| Silicon Integrated Systems [SiS] | 1         | 0.86%   |
| NetXen Incorporated              | 1         | 0.86%   |
| Lenovo                           | 1         | 0.86%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 51        | 42.15%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 7         | 5.79%   |
| Realtek RTL8125 2.5GbE Controller                                    | 5         | 4.13%   |
| Intel I211 Gigabit Network Connection                                | 5         | 4.13%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller            | 3         | 2.48%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                             | 2         | 1.65%   |
| Intel Ethernet Connection I219-LM                                    | 2         | 1.65%   |
| Intel Ethernet Connection (4) I219-LM                                | 2         | 1.65%   |
| Intel Ethernet Connection (2) I218-LM                                | 2         | 1.65%   |
| Intel 82579V Gigabit Network Connection                              | 2         | 1.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 2         | 1.65%   |
| ASIX AX88179 Gigabit Ethernet                                        | 2         | 1.65%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter        | 1         | 0.83%   |
| Samsung Kiera                                                        | 1         | 0.83%   |
| Samsung Galaxy series, misc. (tethering mode)                        | 1         | 0.83%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                      | 1         | 0.83%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                           | 1         | 0.83%   |
| Realtek Killer E3000 2.5GbE Controller                               | 1         | 0.83%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                     | 1         | 0.83%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                               | 1         | 0.83%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                            | 1         | 0.83%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                           | 1         | 0.83%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                        | 1         | 0.83%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet       | 1         | 0.83%   |
| NetXen Incorporated NX3031 Multifunction 1/10-Gigabit Server Adapter | 1         | 0.83%   |
| Lenovo OneLink+ Giga                                                 | 1         | 0.83%   |
| Intel I350 Gigabit Network Connection                                | 1         | 0.83%   |
| Intel I210 Gigabit Network Connection                                | 1         | 0.83%   |
| Intel Ethernet Connection I219-V                                     | 1         | 0.83%   |
| Intel Ethernet Connection I217-V                                     | 1         | 0.83%   |
| Intel Ethernet Connection I217-LM                                    | 1         | 0.83%   |
| Intel Ethernet Connection (7) I219-V                                 | 1         | 0.83%   |
| Intel Ethernet Connection (6) I219-LM                                | 1         | 0.83%   |
| Intel Ethernet Connection (3) I218-LM                                | 1         | 0.83%   |
| Intel Ethernet Connection (2) I219-LM                                | 1         | 0.83%   |
| Intel Ethernet Connection (10) I219-V                                | 1         | 0.83%   |
| Intel 82574L Gigabit Network Connection                              | 1         | 0.83%   |
| Intel 82567LM Gigabit Network Connection                             | 1         | 0.83%   |
| Intel 82566MM Gigabit Network Connection                             | 1         | 0.83%   |
| Intel 82566DM-2 Gigabit Network Connection                           | 1         | 0.83%   |
| Intel 82562V-2 10/100 Network Connection                             | 1         | 0.83%   |
| Intel 82541PI Gigabit Ethernet Controller                            | 1         | 0.83%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                    | 1         | 0.83%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                     | 1         | 0.83%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                      | 1         | 0.83%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                      | 1         | 0.83%   |
| Broadcom Limited NetLink BCM57785 Gigabit Ethernet PCIe              | 1         | 0.83%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe              | 1         | 0.83%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 108       | 53.47%  |
| WiFi     | 91        | 45.05%  |
| Unknown  | 3         | 1.49%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 66        | 51.16%  |
| WiFi     | 62        | 48.06%  |
| Unknown  | 1         | 0.78%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 72        | 61.02%  |
| 1     | 39        | 33.05%  |
| 3     | 5         | 4.24%   |
| 5     | 1         | 0.85%   |
| 4     | 1         | 0.85%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 87        | 72.5%   |
| Yes  | 33        | 27.5%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 29        | 39.19%  |
| Realtek Semiconductor           | 10        | 13.51%  |
| Cambridge Silicon Radio         | 9         | 12.16%  |
| Qualcomm Atheros Communications | 6         | 8.11%   |
| IMC Networks                    | 3         | 4.05%   |
| Foxconn / Hon Hai               | 3         | 4.05%   |
| Broadcom                        | 3         | 4.05%   |
| ASUSTek Computer                | 3         | 4.05%   |
| Lite-On Technology              | 2         | 2.7%    |
| Dell                            | 2         | 2.7%    |
| Realtek                         | 1         | 1.35%   |
| Belkin Components               | 1         | 1.35%   |
| Apple                           | 1         | 1.35%   |
| Alps Electric                   | 1         | 1.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 10        | 13.51%  |
| Intel AX200 Bluetooth                                                               | 9         | 12.16%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 9         | 12.16%  |
| Realtek  Bluetooth 4.2 Adapter                                                      | 5         | 6.76%   |
| Realtek Bluetooth Radio                                                             | 3         | 4.05%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 3         | 4.05%   |
| Intel Bluetooth Device                                                              | 3         | 4.05%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 3         | 4.05%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 2.7%    |
| IMC Networks Bluetooth Device                                                       | 2         | 2.7%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 1.35%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 1.35%   |
| Realtek Bluetooth Radio                                                             | 1         | 1.35%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 1.35%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 1.35%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 1.35%   |
| Lite-On Bluetooth Device                                                            | 1         | 1.35%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 1.35%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 1.35%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 1.35%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 1.35%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.35%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 1.35%   |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 1         | 1.35%   |
| Dell Broadcom BCM20702A0 Bluetooth                                                  | 1         | 1.35%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 1.35%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 1         | 1.35%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 1         | 1.35%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 1         | 1.35%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                               | 1         | 1.35%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 1         | 1.35%   |
| ASUS Bluetooth Adapter                                                              | 1         | 1.35%   |
| ASUS ASUS USB-BT500                                                                 | 1         | 1.35%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 1         | 1.35%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 1         | 1.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 74        | 42.29%  |
| AMD                              | 47        | 26.86%  |
| Nvidia                           | 36        | 20.57%  |
| Creative Labs                    | 3         | 1.71%   |
| C-Media Electronics              | 3         | 1.71%   |
| Logitech                         | 2         | 1.14%   |
| Lenovo                           | 2         | 1.14%   |
| Texas Instruments                | 1         | 0.57%   |
| Silicon Integrated Systems [SiS] | 1         | 0.57%   |
| Sennheiser Communications        | 1         | 0.57%   |
| JMTek                            | 1         | 0.57%   |
| GN Netcom                        | 1         | 0.57%   |
| ESS Technology                   | 1         | 0.57%   |
| BEHRINGER International          | 1         | 0.57%   |
| ASUSTek Computer                 | 1         | 0.57%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 12        | 5.91%   |
| AMD Starship/Matisse HD Audio Controller                                   | 10        | 4.93%   |
| AMD Family 17h/19h HD Audio Controller                                     | 10        | 4.93%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8         | 3.94%   |
| Intel Cannon Lake PCH cAVS                                                 | 7         | 3.45%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6         | 2.96%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6         | 2.96%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 6         | 2.96%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 6         | 2.96%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 6         | 2.96%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5         | 2.46%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 2.46%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 2.46%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5         | 2.46%   |
| AMD FCH Azalia Controller                                                  | 5         | 2.46%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4         | 1.97%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 1.48%   |
| Nvidia GA102 High Definition Audio Controller                              | 3         | 1.48%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 1.48%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3         | 1.48%   |
| AMD Kabini HDMI/DP Audio                                                   | 3         | 1.48%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3         | 1.48%   |
| Nvidia GP108 High Definition Audio Controller                              | 2         | 0.99%   |
| Nvidia GM206 High Definition Audio Controller                              | 2         | 0.99%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 0.99%   |
| Nvidia GK106 HDMI Audio Controller                                         | 2         | 0.99%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 0.99%   |
| Logitech Headset H390                                                      | 2         | 0.99%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 0.99%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 2         | 0.99%   |
| Intel Audio device                                                         | 2         | 0.99%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 0.99%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 0.99%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 0.99%   |
| Intel 200 Series PCH HD Audio                                              | 2         | 0.99%   |
| AMD Tonga HDMI Audio [Radeon R9 285/380]                                   | 2         | 0.99%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 2         | 0.99%   |
| Texas Instruments PCM2900C Audio CODEC                                     | 1         | 0.49%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 1         | 0.49%   |
| Sennheiser Communications Sennheiser 3D G4ME1                              | 1         | 0.49%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.49%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.49%   |
| Nvidia MCP61 High Definition Audio                                         | 1         | 0.49%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 0.49%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.49%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 0.49%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1         | 0.49%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.49%   |
| Nvidia GK110 High Definition Audio Controller                              | 1         | 0.49%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.49%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 0.49%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.49%   |
| Nvidia GF100 High Definition Audio Controller                              | 1         | 0.49%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 0.49%   |
| Nvidia Audio device                                                        | 1         | 0.49%   |
| Lenovo ThinkPad Thunderbolt 4 Dock USB Audio                               | 1         | 0.49%   |
| Lenovo ThinkPad OneLink Plus Dock Audio                                    | 1         | 0.49%   |
| JMTek audio controller                                                     | 1         | 0.49%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 0.49%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 0.49%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Samsung Electronics    | 18        | 21.18%  |
| SK hynix               | 13        | 15.29%  |
| Kingston               | 11        | 12.94%  |
| Unknown                | 9         | 10.59%  |
| Crucial                | 6         | 7.06%   |
| Corsair                | 6         | 7.06%   |
| Micron Technology      | 5         | 5.88%   |
| G.Skill                | 5         | 5.88%   |
| Ramaxel Technology     | 2         | 2.35%   |
| Patriot                | 2         | 2.35%   |
| Unknown (000004B30000) | 1         | 1.18%   |
| Team                   | 1         | 1.18%   |
| Smart                  | 1         | 1.18%   |
| Goodram                | 1         | 1.18%   |
| GeIL                   | 1         | 1.18%   |
| Elpida                 | 1         | 1.18%   |
| AMD                    | 1         | 1.18%   |
| A-DATA Technology      | 1         | 1.18%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s          | 2         | 2.13%   |
| Kingston RAM KHX3600C18D4/32GX 32GB DIMM DDR4 3600MT/s         | 2         | 2.13%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s         | 2         | 2.13%   |
| G.Skill RAM F4-2400C15-8GNT 8192MB DIMM DDR4 2666MT/s          | 2         | 2.13%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 1         | 1.06%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                        | 1         | 1.06%   |
| Unknown RAM Module 4GB SODIMM DDR2 667MT/s                     | 1         | 1.06%   |
| Unknown RAM Module 4096MB SODIMM DDR3                          | 1         | 1.06%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 1         | 1.06%   |
| Unknown RAM Module 2048MB SODIMM 1067MT/s                      | 1         | 1.06%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s                   | 1         | 1.06%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                        | 1         | 1.06%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                     | 1         | 1.06%   |
| Unknown RAM Module 1024MB SODIMM 1067MT/s                      | 1         | 1.06%   |
| Unknown RAM 992124 (997124) 8GB DIMM DDR3 1600MT/s             | 1         | 1.06%   |
| Unknown (000004B30000) RAM Module 32GB DIMM DDR3 1333MT/s      | 1         | 1.06%   |
| Team RAM TEAMGROUP-UD4-2400 8GB DIMM DDR4 3007MT/s             | 1         | 1.06%   |
| Smart RAM SH564568FH8NWPHSFG 2048MB SODIMM DDR3 1333MT/s       | 1         | 1.06%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                   | 1         | 1.06%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM SDRAM 2048MT/s        | 1         | 1.06%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s         | 1         | 1.06%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 1         | 1.06%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s         | 1         | 1.06%   |
| SK hynix RAM HMT351R7CFR8C-PB 4GB DIMM DDR3 1600MT/s           | 1         | 1.06%   |
| SK hynix RAM HMT151R7BFR4C-G7 4GB DIMM DDR3 1066MT/s           | 1         | 1.06%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s        | 1         | 1.06%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s         | 1         | 1.06%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s         | 1         | 1.06%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s        | 1         | 1.06%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 1         | 1.06%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s         | 1         | 1.06%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s         | 1         | 1.06%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s     | 1         | 1.06%   |
| Samsung RAM Module 4096MB SODIMM DDR4 2400MT/s                 | 1         | 1.06%   |
| Samsung RAM M471B5673FH0-CH9 2048MB DIMM SDRAM 4199MT/s        | 1         | 1.06%   |
| Samsung RAM M471B5673EH1-CH9 2GB SODIMM DDR3 1334MT/s          | 1         | 1.06%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s          | 1         | 1.06%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s          | 1         | 1.06%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s         | 1         | 1.06%   |
| Samsung RAM M471A2K43DB1-CTD 16384MB SODIMM DDR4 2667MT/s      | 1         | 1.06%   |
| Samsung RAM M471A2G43BB2-CWE 16GB SODIMM DDR4 3200MT/s         | 1         | 1.06%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s          | 1         | 1.06%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s          | 1         | 1.06%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s    | 1         | 1.06%   |
| Samsung RAM M393A2G40DB0-CPB 16GB DIMM DDR4 2133MT/s           | 1         | 1.06%   |
| Samsung RAM M393A1G40DB0-CPB 8GB DIMM DDR4 2133MT/s            | 1         | 1.06%   |
| Samsung RAM M378B1G73EB0-YK0 8192MB DIMM DDR3 1600MT/s         | 1         | 1.06%   |
| Samsung RAM M3 78T2863EHS-CF7 1024MB DIMM DDR2 800MT/s         | 1         | 1.06%   |
| Samsung RAM K4F6E3S4HM-MGCJ 4096MB SODIMM LPDDR4 3733MT/s      | 1         | 1.06%   |
| Samsung RAM K4E6E304EE-EGCF 4096MB SODIMM LPDDR3 1867MT/s      | 1         | 1.06%   |
| Samsung RAM K4E6E304EE-EGCF 4096MB Chip LPDDR3 1867MT/s        | 1         | 1.06%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s        | 1         | 1.06%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s      | 1         | 1.06%   |
| Patriot RAM PSD48G266681 8GB DIMM DDR4 2934MT/s                | 1         | 1.06%   |
| Patriot RAM PSD22G80026 2048MB DIMM DDR2 800MT/s               | 1         | 1.06%   |
| Micron RAM 8ATF51264HZ-2G1B1 8GB SODIMM DDR4 2667MT/s          | 1         | 1.06%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8192MB SODIMM DDR4 2667MT/s        | 1         | 1.06%   |
| Micron RAM 53E1G32D2NP-046 2048MB Row Of Chips LPDDR4 4267MT/s | 1         | 1.06%   |
| Micron RAM 4ATF51264HZ-2G3E1 4096MB SODIMM DDR4 2667MT/s       | 1         | 1.06%   |
| Micron RAM 16JTF1G64AZ-1G6D1 8GB DIMM DDR3 1600MT/s            | 1         | 1.06%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 39        | 52.7%   |
| DDR3    | 21        | 28.38%  |
| LPDDR4  | 4         | 5.41%   |
| DDR2    | 4         | 5.41%   |
| Unknown | 3         | 4.05%   |
| SDRAM   | 2         | 2.7%    |
| LPDDR3  | 1         | 1.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 36        | 48.65%  |
| DIMM         | 35        | 47.3%   |
| Row Of Chips | 2         | 2.7%    |
| Chip         | 1         | 1.35%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 31        | 36.47%  |
| 4096  | 20        | 23.53%  |
| 16384 | 15        | 17.65%  |
| 2048  | 10        | 11.76%  |
| 32768 | 5         | 5.88%   |
| 1024  | 4         | 4.71%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 15        | 18.29%  |
| 1600    | 13        | 15.85%  |
| 3200    | 9         | 10.98%  |
| 1333    | 8         | 9.76%   |
| 2133    | 5         | 6.1%    |
| 3600    | 4         | 4.88%   |
| 2400    | 3         | 3.66%   |
| 1867    | 3         | 3.66%   |
| 667     | 3         | 3.66%   |
| 3800    | 2         | 2.44%   |
| 2666    | 2         | 2.44%   |
| 800     | 2         | 2.44%   |
| 4267    | 1         | 1.22%   |
| 4266    | 1         | 1.22%   |
| 4199    | 1         | 1.22%   |
| 3733    | 1         | 1.22%   |
| 3466    | 1         | 1.22%   |
| 3007    | 1         | 1.22%   |
| 2934    | 1         | 1.22%   |
| 2933    | 1         | 1.22%   |
| 2048    | 1         | 1.22%   |
| 1334    | 1         | 1.22%   |
| 1067    | 1         | 1.22%   |
| 1066    | 1         | 1.22%   |
| Unknown | 1         | 1.22%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


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

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Samsung SCX-4200 series       | 1         | 12.5%   |
| Prolific PL2305 Parallel Port | 1         | 12.5%   |
| Kyocera FS-1030D printer      | 1         | 12.5%   |
| HP ENVY 4500 series           | 1         | 12.5%   |
| HP DeskJet 6940 series        | 1         | 12.5%   |
| Canon LiDE 300                | 1         | 12.5%   |
| Brother Printer               | 1         | 12.5%   |
| Brother HL-L3210CW series     | 1         | 12.5%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Canon       | 3         | 75%     |
| Seiko Epson | 1         | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 15        | 21.74%  |
| Logitech                               | 9         | 13.04%  |
| Acer                                   | 7         | 10.14%  |
| Sunplus Innovation Technology          | 5         | 7.25%   |
| Realtek Semiconductor                  | 5         | 7.25%   |
| IMC Networks                           | 5         | 7.25%   |
| Quanta                                 | 4         | 5.8%    |
| Cheng Uei Precision Industry (Foxlink) | 4         | 5.8%    |
| Microdia                               | 3         | 4.35%   |
| Lite-On Technology                     | 2         | 2.9%    |
| Z-Star Microelectronics                | 1         | 1.45%   |
| Syntek                                 | 1         | 1.45%   |
| Silicon Motion                         | 1         | 1.45%   |
| Ricoh                                  | 1         | 1.45%   |
| Microsoft                              | 1         | 1.45%   |
| Luxvisions Innotech Limited            | 1         | 1.45%   |
| Hewlett-Packard                        | 1         | 1.45%   |
| Generalplus Technology                 | 1         | 1.45%   |
| Creative Technology                    | 1         | 1.45%   |
| ALi                                    | 1         | 1.45%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                | 4         | 5.63%   |
| Logitech Webcam C270                                                     | 3         | 4.23%   |
| Sunplus HD WebCam                                                        | 2         | 2.82%   |
| Realtek Integrated_Webcam_HD                                             | 2         | 2.82%   |
| Microdia Integrated_Webcam_HD                                            | 2         | 2.82%   |
| Logitech HD Pro Webcam C920                                              | 2         | 2.82%   |
| Logitech B525 HD Webcam                                                  | 2         | 2.82%   |
| IMC Networks Integrated Camera                                           | 2         | 2.82%   |
| Chicony HD Webcam                                                        | 2         | 2.82%   |
| Acer HD Webcam                                                           | 2         | 2.82%   |
| Acer BisonCam, NB Pro                                                    | 2         | 2.82%   |
| Z-Star Venus USB2.0 Camera                                               | 1         | 1.41%   |
| Syntek Lenovo EasyCamera                                                 | 1         | 1.41%   |
| Sunplus Laptop_Integrated_Webcam_HD                                      | 1         | 1.41%   |
| Sunplus Integrated_Webcam_HD                                             | 1         | 1.41%   |
| Sunplus 1.3M HD WebCam                                                   | 1         | 1.41%   |
| Silicon Motion WebCam SC-13HDN10939N                                     | 1         | 1.41%   |
| Ricoh Sony Vaio Integrated Webcam                                        | 1         | 1.41%   |
| Realtek USB2.0 HD UVC WebCam                                             | 1         | 1.41%   |
| Realtek USB Camera                                                       | 1         | 1.41%   |
| Realtek Lenovo EasyCamera                                                | 1         | 1.41%   |
| Realtek Integrated Webcam HD                                             | 1         | 1.41%   |
| Quanta HP Wide Vision HD Camera                                          | 1         | 1.41%   |
| Quanta HP TrueVision HD Camera                                           | 1         | 1.41%   |
| Quanta HD Webcam                                                         | 1         | 1.41%   |
| Quanta HD User Facing                                                    | 1         | 1.41%   |
| Microsoft LifeCam VX-700                                                 | 1         | 1.41%   |
| Microdia Laptop_Integrated_Webcam_7645BB9590586C77DC683CD9114697FF.3M    | 1         | 1.41%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                      | 1         | 1.41%   |
| Logitech Webcam C250                                                     | 1         | 1.41%   |
| Logitech HD Webcam C615                                                  | 1         | 1.41%   |
| Lite-On Integrated Camera                                                | 1         | 1.41%   |
| Lite-On HP 5MP Camera                                                    | 1         | 1.41%   |
| IMC Networks USB2.0 VGA UVC WebCam                                       | 1         | 1.41%   |
| IMC Networks USB2.0 UVC HD Webcam                                        | 1         | 1.41%   |
| IMC Networks USB2.0 HD UVC WebCam                                        | 1         | 1.41%   |
| HP Webcam 3100                                                           | 1         | 1.41%   |
| Generalplus GENERAL WEBCAM                                               | 1         | 1.41%   |
| Creative Live! Cam Sync 1080p                                            | 1         | 1.41%   |
| Chicony VGA 24fps UVC Webcam                                             | 1         | 1.41%   |
| Chicony USB2.0 Camera                                                    | 1         | 1.41%   |
| Chicony ThinkPad T490 Webcam                                             | 1         | 1.41%   |
| Chicony Integrated Camera (1280x720@30)                                  | 1         | 1.41%   |
| Chicony HP Wide Vision HD Camera                                         | 1         | 1.41%   |
| Chicony HP Webcam                                                        | 1         | 1.41%   |
| Chicony HP TrueVision HD                                                 | 1         | 1.41%   |
| Chicony HP IR Camera                                                     | 1         | 1.41%   |
| Chicony FJ Camera                                                        | 1         | 1.41%   |
| Chicony EasyCamera                                                       | 1         | 1.41%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                            | 1         | 1.41%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                      | 1         | 1.41%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 1         | 1.41%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera                         | 1         | 1.41%   |
| ALi Gateway Webcam                                                       | 1         | 1.41%   |
| Acer ThinkPad P50 Integrated Camera                                      | 1         | 1.41%   |
| Acer Integrated Camera                                                   | 1         | 1.41%   |
| Acer BisonCam,NB Pro                                                     | 1         | 1.41%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 6         | 42.86%  |
| Validity Sensors           | 5         | 35.71%  |
| Upek                       | 1         | 7.14%   |
| Shenzhen Goodix Technology | 1         | 7.14%   |
| AuthenTec                  | 1         | 7.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor           | 2         | 14.29%  |
| Synaptics  WBDI                                        | 2         | 14.29%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 2         | 14.29%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 7.14%   |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 7.14%   |
| Validity Sensors Synaptics WBDI                        | 1         | 7.14%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 7.14%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 7.14%   |
| Shenzhen Goodix  Fingerprint Device                    | 1         | 7.14%   |
| AuthenTec AES1660 Fingerprint Sensor                   | 1         | 7.14%   |
| Unknown                                                | 1         | 7.14%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| O2 Micro              | 2         | 28.57%  |
| Broadcom              | 2         | 28.57%  |
| Alcor Micro           | 2         | 28.57%  |
| Gemalto (was Gemplus) | 1         | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader              | 2         | 28.57%  |
| Alcor Micro AU9540 Smartcard Reader               | 2         | 28.57%  |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 1         | 14.29%  |
| Broadcom BCM5880 Secure Applications Processor    | 1         | 14.29%  |
| Broadcom 5880                                     | 1         | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 80        | 66.12%  |
| 1     | 34        | 28.1%   |
| 2     | 7         | 5.79%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 14        | 29.79%  |
| Graphics card            | 10        | 21.28%  |
| Chipcard                 | 8         | 17.02%  |
| Net/wireless             | 5         | 10.64%  |
| Unassigned class         | 2         | 4.26%   |
| Sound                    | 2         | 4.26%   |
| Multimedia controller    | 2         | 4.26%   |
| Bluetooth                | 2         | 4.26%   |
| Communication controller | 1         | 2.13%   |
| Camera                   | 1         | 2.13%   |

