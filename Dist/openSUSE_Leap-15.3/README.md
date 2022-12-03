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

Total: 189

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | ROG STRIX H470-I GAMING     | Desktop     | [8b8ac358e4](https://linux-hardware.org/?probe=8b8ac358e4) | Nov 21, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | Desktop     | [776a9bc0b6](https://linux-hardware.org/?probe=776a9bc0b6) | Nov 09, 2022 |
| Gateway       | NV54 Series                 | Notebook    | [88b57ed4e4](https://linux-hardware.org/?probe=88b57ed4e4) | Oct 09, 2022 |
| ASUSTek       | WS C422 PRO_SE              | Desktop     | [e278a4ab5e](https://linux-hardware.org/?probe=e278a4ab5e) | Sep 21, 2022 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [7532844cd7](https://linux-hardware.org/?probe=7532844cd7) | Sep 11, 2022 |
| ASUSTek       | V161GAR                     | All in one  | [668d4ac33b](https://linux-hardware.org/?probe=668d4ac33b) | Sep 09, 2022 |
| Biostar       | H77MU3                      | Desktop     | [20ba4d44ed](https://linux-hardware.org/?probe=20ba4d44ed) | Sep 05, 2022 |
| ASRock        | B85 Pro4                    | Desktop     | [db3bc987b6](https://linux-hardware.org/?probe=db3bc987b6) | Aug 29, 2022 |
| Lenovo        | ThinkPad T450 20BUS0EW1F    | Notebook    | [88ad38d9f7](https://linux-hardware.org/?probe=88ad38d9f7) | Aug 17, 2022 |
| Lenovo        | ThinkPad T450 20BUS0EW1F    | Notebook    | [73b611ea50](https://linux-hardware.org/?probe=73b611ea50) | Aug 17, 2022 |
| ASUSTek       | M3A78-EM                    | Desktop     | [d9fa82e283](https://linux-hardware.org/?probe=d9fa82e283) | Aug 15, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [56c2008bb6](https://linux-hardware.org/?probe=56c2008bb6) | Jul 25, 2022 |
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
| 5.3.18-59.37-default                | 18        | 12.86%  |
| 5.3.18-59.27-default                | 13        | 9.29%   |
| 5.3.18-59.19-default                | 13        | 9.29%   |
| 5.3.18-57-default                   | 8         | 5.71%   |
| 5.3.18-150300.59.49-default         | 8         | 5.71%   |
| 5.3.18-59.5-default                 | 6         | 4.29%   |
| 5.3.18-59.24-default                | 6         | 4.29%   |
| 5.3.18-59.16-default                | 6         | 4.29%   |
| 5.3.18-150300.59.54-default         | 6         | 4.29%   |
| 5.3.18-59.10-default                | 5         | 3.57%   |
| 5.3.18-150300.59.63-default         | 5         | 3.57%   |
| 5.3.18-59.34-default                | 4         | 2.86%   |
| 5.3.18-150300.59.87-default         | 4         | 2.86%   |
| 5.3.18-150300.59.60-default         | 4         | 2.86%   |
| 5.3.18-150300.59.43-default         | 3         | 2.14%   |
| 5.3.18-59.27-preempt                | 2         | 1.43%   |
| 5.3.18-59.19-preempt                | 2         | 1.43%   |
| 5.3.18-59.13-default                | 2         | 1.43%   |
| 5.3.18-150300.59.93-default         | 2         | 1.43%   |
| 5.3.18-150300.59.90-default         | 2         | 1.43%   |
| 5.3.18-150300.59.68-default         | 2         | 1.43%   |
| 5.3.18-lp152.57-default             | 1         | 0.71%   |
| 5.3.18-59.37-preempt                | 1         | 0.71%   |
| 5.3.18-59.34-preempt                | 1         | 0.71%   |
| 5.3.18-59.24-preempt                | 1         | 0.71%   |
| 5.3.18-57-preempt                   | 1         | 0.71%   |
| 5.3.18-56-default                   | 1         | 0.71%   |
| 5.3.18-52-default                   | 1         | 0.71%   |
| 5.3.18-46-default                   | 1         | 0.71%   |
| 5.3.18-150300.59.98-default         | 1         | 0.71%   |
| 5.3.18-150300.59.76-default         | 1         | 0.71%   |
| 5.3.18-150300.59.71-default         | 1         | 0.71%   |
| 5.3.18-150300.59.63-preempt         | 1         | 0.71%   |
| 5.3.18-150300.59.60-preempt         | 1         | 0.71%   |
| 5.3.18-150300.59.49-preempt         | 1         | 0.71%   |
| 5.17.2-1.gb49cf22-default           | 1         | 0.71%   |
| 5.17.2-1-default                    | 1         | 0.71%   |
| 5.16.0-rc2-lp153.2.g696d453-default | 1         | 0.71%   |
| 5.15.11-lp153.3.g730a488-default    | 1         | 0.71%   |
| 4.12.14-197.105-vanilla             | 1         | 0.71%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.3.18  | 124       | 96.12%  |
| 5.17.2  | 2         | 1.55%   |
| 5.16.0  | 1         | 0.78%   |
| 5.15.11 | 1         | 0.78%   |
| 4.12.14 | 1         | 0.78%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.3     | 124       | 96.12%  |
| 5.17    | 2         | 1.55%   |
| 5.16    | 1         | 0.78%   |
| 5.15    | 1         | 0.78%   |
| 4.12    | 1         | 0.78%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 128       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| KDE5       | 62        | 46.62%  |
| GNOME      | 18        | 13.53%  |
| KDE        | 17        | 12.78%  |
| Unknown    | 16        | 12.03%  |
| XFCE       | 12        | 9.02%   |
| X-Cinnamon | 4         | 3.01%   |
| plasma5    | 1         | 0.75%   |
| MATE       | 1         | 0.75%   |
| LXDE       | 1         | 0.75%   |
| ICEWM      | 1         | 0.75%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 107       | 82.31%  |
| Wayland | 13        | 10%     |
| Tty     | 10        | 7.69%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 65        | 49.24%  |
| SDDM    | 33        | 25%     |
| LightDM | 28        | 21.21%  |
| XDM     | 5         | 3.79%   |
| GDM     | 1         | 0.76%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 36        | 27.69%  |
| de_DE   | 31        | 23.85%  |
| POSIX   | 14        | 10.77%  |
| pt_BR   | 7         | 5.38%   |
| ru_RU   | 5         | 3.85%   |
| es_ES   | 5         | 3.85%   |
| Unknown | 5         | 3.85%   |
| en_GB   | 4         | 3.08%   |
| nl_NL   | 3         | 2.31%   |
| fr_FR   | 3         | 2.31%   |
| it_IT   | 2         | 1.54%   |
| zh_CN   | 1         | 0.77%   |
| tr_TR   | 1         | 0.77%   |
| sv_SE   | 1         | 0.77%   |
| sk_SK   | 1         | 0.77%   |
| pt_PT   | 1         | 0.77%   |
| pl_PL   | 1         | 0.77%   |
| nl_BE   | 1         | 0.77%   |
| hu_HU   | 1         | 0.77%   |
| hr_HR   | 1         | 0.77%   |
| fi_FI   | 1         | 0.77%   |
| es_MX   | 1         | 0.77%   |
| en_DE   | 1         | 0.77%   |
| en_AU   | 1         | 0.77%   |
| cs_CZ   | 1         | 0.77%   |
| ca_AD   | 1         | 0.77%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 76        | 58.91%  |
| EFI  | 53        | 41.09%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 87        | 67.44%  |
| Ext4    | 36        | 27.91%  |
| Xfs     | 5         | 3.88%   |
| Overlay | 1         | 0.78%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 66        | 50.38%  |
| Unknown | 55        | 41.98%  |
| MBR     | 10        | 7.63%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 106       | 81.54%  |
| Yes       | 24        | 18.46%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 90        | 70.31%  |
| Yes       | 38        | 29.69%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 22        | 17.19%  |
| Lenovo              | 19        | 14.84%  |
| Hewlett-Packard     | 17        | 13.28%  |
| MSI                 | 13        | 10.16%  |
| Dell                | 12        | 9.38%   |
| Gigabyte Technology | 11        | 8.59%   |
| ASRock              | 7         | 5.47%   |
| Acer                | 7         | 5.47%   |
| TUXEDO              | 3         | 2.34%   |
| Fujitsu             | 3         | 2.34%   |
| Sony                | 2         | 1.56%   |
| VS Company          | 1         | 0.78%   |
| Shuttle             | 1         | 0.78%   |
| Semp Toshiba        | 1         | 0.78%   |
| Samsung Electronics | 1         | 0.78%   |
| Medion              | 1         | 0.78%   |
| Itautec             | 1         | 0.78%   |
| Intel               | 1         | 0.78%   |
| HUAWEI              | 1         | 0.78%   |
| Gateway             | 1         | 0.78%   |
| Biostar             | 1         | 0.78%   |
| Apple               | 1         | 0.78%   |
| Alienware           | 1         | 0.78%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                         | Computers | Percent |
|----------------------------------------------|-----------|---------|
| ASUS All Series                              | 3         | 2.34%   |
| TUXEDO Pulse 15 Gen1                         | 2         | 1.56%   |
| VS Company G31T-M                            | 1         | 0.78%   |
| TUXEDO Aura 15 Gen1                          | 1         | 0.78%   |
| Sony VPCSB15GB                               | 1         | 0.78%   |
| Sony VGN-Z570AN                              | 1         | 0.78%   |
| Shuttle XS35V4                               | 1         | 0.78%   |
| Semp Toshiba AS 1301                         | 1         | 0.78%   |
| Samsung 600B4B/600B5B                        | 1         | 0.78%   |
| MSI MS-7D16                                  | 1         | 0.78%   |
| MSI MS-7C34                                  | 1         | 0.78%   |
| MSI MS-7C02                                  | 1         | 0.78%   |
| MSI MS-7B89                                  | 1         | 0.78%   |
| MSI MS-7A38                                  | 1         | 0.78%   |
| MSI MS-7A34                                  | 1         | 0.78%   |
| MSI MS-7A33                                  | 1         | 0.78%   |
| MSI MS-7817                                  | 1         | 0.78%   |
| MSI Modern 15 A4M                            | 1         | 0.78%   |
| MSI GS60 6QE                                 | 1         | 0.78%   |
| MSI GP63 Leopard 8RD                         | 1         | 0.78%   |
| MSI ESPRIMO P1510                            | 1         | 0.78%   |
| MSI CX600                                    | 1         | 0.78%   |
| Medion E6436 MD61150                         | 1         | 0.78%   |
| Lenovo Yoga 730-15IKB 81CU                   | 1         | 0.78%   |
| Lenovo V330-15IKB 81AX                       | 1         | 0.78%   |
| Lenovo ThinkStation P520 30BE008VGE          | 1         | 0.78%   |
| Lenovo ThinkStation P500 30A6S4JU00          | 1         | 0.78%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XW00A7TH   | 1         | 0.78%   |
| Lenovo ThinkPad X1 Carbon 4th 20FB002UMC     | 1         | 0.78%   |
| Lenovo ThinkPad T61 8895W9U                  | 1         | 0.78%   |
| Lenovo ThinkPad T490s 20NYS1XK00             | 1         | 0.78%   |
| Lenovo ThinkPad T470 20HES1RB06              | 1         | 0.78%   |
| Lenovo ThinkPad T460 20FMS75800              | 1         | 0.78%   |
| Lenovo ThinkPad T450s 20BWA06J00             | 1         | 0.78%   |
| Lenovo ThinkPad T450 20BUS0EW1F              | 1         | 0.78%   |
| Lenovo ThinkPad T14 Gen 1 20UES47F00         | 1         | 0.78%   |
| Lenovo ThinkPad L15 Gen 1 20U4S88000         | 1         | 0.78%   |
| Lenovo ThinkPad E580 20KS001RGE              | 1         | 0.78%   |
| Lenovo IdeaPad 330-15IKB 81DC                | 1         | 0.78%   |
| Lenovo IdeaCentre Y710 Cube-15ISH 90FL004WGE | 1         | 0.78%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 11        | 8.59%   |
| Dell Inspiron       | 5         | 3.91%   |
| Acer Aspire         | 5         | 3.91%   |
| HP Pavilion         | 3         | 2.34%   |
| ASUS ROG            | 3         | 2.34%   |
| ASUS All            | 3         | 2.34%   |
| TUXEDO Pulse        | 2         | 1.56%   |
| Lenovo ThinkStation | 2         | 1.56%   |
| HP Laptop           | 2         | 1.56%   |
| Gigabyte B550       | 2         | 1.56%   |
| Fujitsu LIFEBOOK    | 2         | 1.56%   |
| Dell Latitude       | 2         | 1.56%   |
| ASUS TUF            | 2         | 1.56%   |
| ASUS PRIME          | 2         | 1.56%   |
| Acer Nitro          | 2         | 1.56%   |
| VS Company G31T-M   | 1         | 0.78%   |
| TUXEDO Aura         | 1         | 0.78%   |
| Sony VPCSB15GB      | 1         | 0.78%   |
| Sony VGN-Z570AN     | 1         | 0.78%   |
| Shuttle XS35V4      | 1         | 0.78%   |
| Semp Toshiba AS     | 1         | 0.78%   |
| Samsung 600B4B      | 1         | 0.78%   |
| MSI MS-7D16         | 1         | 0.78%   |
| MSI MS-7C34         | 1         | 0.78%   |
| MSI MS-7C02         | 1         | 0.78%   |
| MSI MS-7B89         | 1         | 0.78%   |
| MSI MS-7A38         | 1         | 0.78%   |
| MSI MS-7A34         | 1         | 0.78%   |
| MSI MS-7A33         | 1         | 0.78%   |
| MSI MS-7817         | 1         | 0.78%   |
| MSI Modern          | 1         | 0.78%   |
| MSI GS60            | 1         | 0.78%   |
| MSI GP63            | 1         | 0.78%   |
| MSI ESPRIMO         | 1         | 0.78%   |
| MSI CX600           | 1         | 0.78%   |
| Medion E6436        | 1         | 0.78%   |
| Lenovo Yoga         | 1         | 0.78%   |
| Lenovo V330-15IKB   | 1         | 0.78%   |
| Lenovo IdeaPad      | 1         | 0.78%   |
| Lenovo IdeaCentre   | 1         | 0.78%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2018 | 17        | 13.28%  |
| 2020 | 14        | 10.94%  |
| 2019 | 12        | 9.38%   |
| 2012 | 12        | 9.38%   |
| 2014 | 11        | 8.59%   |
| 2021 | 9         | 7.03%   |
| 2017 | 9         | 7.03%   |
| 2015 | 8         | 6.25%   |
| 2011 | 7         | 5.47%   |
| 2010 | 6         | 4.69%   |
| 2016 | 5         | 3.91%   |
| 2013 | 5         | 3.91%   |
| 2009 | 5         | 3.91%   |
| 2008 | 4         | 3.13%   |
| 2007 | 3         | 2.34%   |
| 2006 | 1         | 0.78%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Desktop     | 65        | 50.78%  |
| Notebook    | 57        | 44.53%  |
| Convertible | 3         | 2.34%   |
| All in one  | 2         | 1.56%   |
| Server      | 1         | 0.78%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 116       | 90.63%  |
| Enabled  | 12        | 9.38%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 128       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 36        | 28.13%  |
| 8.01-16.0   | 23        | 17.97%  |
| 4.01-8.0    | 22        | 17.19%  |
| 3.01-4.0    | 19        | 14.84%  |
| 64.01-256.0 | 12        | 9.38%   |
| 32.01-64.0  | 11        | 8.59%   |
| 24.01-32.0  | 2         | 1.56%   |
| 1.01-2.0    | 2         | 1.56%   |
| 2.01-3.0    | 1         | 0.78%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 37        | 28.03%  |
| 2.01-3.0   | 36        | 27.27%  |
| 4.01-8.0   | 31        | 23.48%  |
| 3.01-4.0   | 15        | 11.36%  |
| 0.51-1.0   | 6         | 4.55%   |
| 8.01-16.0  | 4         | 3.03%   |
| 32.01-64.0 | 1         | 0.76%   |
| 24.01-32.0 | 1         | 0.76%   |
| 0.01-0.5   | 1         | 0.76%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 58        | 45.31%  |
| 2      | 43        | 33.59%  |
| 3      | 11        | 8.59%   |
| 4      | 7         | 5.47%   |
| 6      | 4         | 3.13%   |
| 5      | 3         | 2.34%   |
| 9      | 1         | 0.78%   |
| 7      | 1         | 0.78%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 66        | 51.56%  |
| No        | 62        | 48.44%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 118       | 92.19%  |
| No        | 10        | 7.81%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 97        | 75.19%  |
| No        | 32        | 24.81%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 78        | 59.54%  |
| No        | 53        | 40.46%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Germany     | 34        | 26.56%  |
| USA         | 17        | 13.28%  |
| Brazil      | 12        | 9.38%   |
| Russia      | 6         | 4.69%   |
| Netherlands | 4         | 3.13%   |
| France      | 4         | 3.13%   |
| Australia   | 4         | 3.13%   |
| UK          | 3         | 2.34%   |
| Spain       | 3         | 2.34%   |
| Mexico      | 3         | 2.34%   |
| India       | 3         | 2.34%   |
| Slovakia    | 2         | 1.56%   |
| Nicaragua   | 2         | 1.56%   |
| Japan       | 2         | 1.56%   |
| Italy       | 2         | 1.56%   |
| Hungary     | 2         | 1.56%   |
| Greece      | 2         | 1.56%   |
| Czechia     | 2         | 1.56%   |
| Belgium     | 2         | 1.56%   |
| Austria     | 2         | 1.56%   |
| Turkey      | 1         | 0.78%   |
| Thailand    | 1         | 0.78%   |
| Switzerland | 1         | 0.78%   |
| Sweden      | 1         | 0.78%   |
| Sudan       | 1         | 0.78%   |
| Romania     | 1         | 0.78%   |
| Portugal    | 1         | 0.78%   |
| Poland      | 1         | 0.78%   |
| Peru        | 1         | 0.78%   |
| Luxembourg  | 1         | 0.78%   |
| Finland     | 1         | 0.78%   |
| Estonia     | 1         | 0.78%   |
| Croatia     | 1         | 0.78%   |
| China       | 1         | 0.78%   |
| Canada      | 1         | 0.78%   |
| Bulgaria    | 1         | 0.78%   |
| Andorra     | 1         | 0.78%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Sao Paulo             | 4         | 3.05%   |
| Halle                 | 4         | 3.05%   |
| Moscow                | 3         | 2.29%   |
| Wesel                 | 2         | 1.53%   |
| Tokyo                 | 2         | 1.53%   |
| Sydney                | 2         | 1.53%   |
| Stolk                 | 2         | 1.53%   |
| Managua               | 2         | 1.53%   |
| Lehrte                | 2         | 1.53%   |
| Chapecó              | 2         | 1.53%   |
| Berlin                | 2         | 1.53%   |
| Zagreb                | 1         | 0.76%   |
| Weilheim              | 1         | 0.76%   |
| Waltham               | 1         | 0.76%   |
| Vijayawada            | 1         | 0.76%   |
| Vienna                | 1         | 0.76%   |
| Veresegyhaz           | 1         | 0.76%   |
| Vaennaes              | 1         | 0.76%   |
| Udine                 | 1         | 0.76%   |
| Três Lagoas          | 1         | 0.76%   |
| The Hague             | 1         | 0.76%   |
| Teresina              | 1         | 0.76%   |
| Tallinn               | 1         | 0.76%   |
| Tacna                 | 1         | 0.76%   |
| Sterling              | 1         | 0.76%   |
| Stargard              | 1         | 0.76%   |
| Southampton           | 1         | 0.76%   |
| Sofia                 | 1         | 0.76%   |
| San Luis Potosí City | 1         | 0.76%   |
| Samorin               | 1         | 0.76%   |
| Saalfeld              | 1         | 0.76%   |
| Rotterdam             | 1         | 0.76%   |
| Rottenburg            | 1         | 0.76%   |
| Rockville             | 1         | 0.76%   |
| Rio de Janeiro        | 1         | 0.76%   |
| Rio Branco            | 1         | 0.76%   |
| Recife                | 1         | 0.76%   |
| Puyallup              | 1         | 0.76%   |
| Prosper               | 1         | 0.76%   |
| Prague                | 1         | 0.76%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 42        | 61     | 19.27%  |
| Samsung Electronics | 40        | 64     | 18.35%  |
| Seagate             | 38        | 61     | 17.43%  |
| Kingston            | 19        | 22     | 8.72%   |
| Toshiba             | 10        | 11     | 4.59%   |
| SanDisk             | 10        | 11     | 4.59%   |
| Hitachi             | 8         | 11     | 3.67%   |
| Crucial             | 7         | 10     | 3.21%   |
| Unknown             | 5         | 5      | 2.29%   |
| SK hynix            | 5         | 5      | 2.29%   |
| Intel               | 4         | 4      | 1.83%   |
| HGST                | 4         | 5      | 1.83%   |
| A-DATA Technology   | 4         | 4      | 1.83%   |
| Micron Technology   | 3         | 4      | 1.38%   |
| Silicon Motion      | 2         | 2      | 0.92%   |
| Phison              | 2         | 2      | 0.92%   |
| Fujitsu             | 2         | 2      | 0.92%   |
| TO Exter            | 1         | 1      | 0.46%   |
| SSSTC               | 1         | 1      | 0.46%   |
| Plextor             | 1         | 2      | 0.46%   |
| LITEON              | 1         | 1      | 0.46%   |
| Lite-On             | 1         | 1      | 0.46%   |
| JMicron Technology  | 1         | 1      | 0.46%   |
| Intenso             | 1         | 1      | 0.46%   |
| Inateck             | 1         | 1      | 0.46%   |
| HGST HTS            | 1         | 1      | 0.46%   |
| Corsair             | 1         | 1      | 0.46%   |
| China               | 1         | 1      | 0.46%   |
| Apple               | 1         | 1      | 0.46%   |
| Apacer              | 1         | 3      | 0.46%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB    | 3         | 1.22%   |
| Samsung SSD 850 EVO 500GB             | 3         | 1.22%   |
| Samsung SSD 850 EVO 250GB             | 3         | 1.22%   |
| WDC WDS500G1X0E-00AFY0 500GB          | 2         | 0.82%   |
| WDC WDS480G2G0A-00JH30 480GB SSD      | 2         | 0.82%   |
| WDC WD5000AAKX-07U6AA0 500GB          | 2         | 0.82%   |
| WDC WD10EZEX-08WN4A0 1TB              | 2         | 0.82%   |
| WDC WD10EAVS-22D7B0 1TB               | 2         | 0.82%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 2         | 0.82%   |
| Silicon Motion NVMe SSD Drive 512GB   | 2         | 0.82%   |
| Seagate ST3750528AS 752GB             | 2         | 0.82%   |
| Seagate ST3500418AS 500GB             | 2         | 0.82%   |
| Seagate ST3500413AS 500GB             | 2         | 0.82%   |
| Seagate ST2000DM008-2FR102 2TB        | 2         | 0.82%   |
| Seagate ST2000DM006-2DM164 2TB        | 2         | 0.82%   |
| Seagate ST2000DM001-9YN164 2TB        | 2         | 0.82%   |
| Seagate ST2000DM001-1ER164 2TB        | 2         | 0.82%   |
| Seagate ST1000LM035-1RK172 1TB        | 2         | 0.82%   |
| Seagate ST1000DM010-2EP102 1TB        | 2         | 0.82%   |
| Samsung SSD 980 PRO 1TB               | 2         | 0.82%   |
| Samsung SSD 970 EVO 1TB               | 2         | 0.82%   |
| Samsung SSD 870 QVO 1TB               | 2         | 0.82%   |
| Samsung SSD 860 EVO 500GB             | 2         | 0.82%   |
| Samsung SSD 860 EVO 250GB             | 2         | 0.82%   |
| Samsung SSD 860 EVO 1TB               | 2         | 0.82%   |
| Samsung NVMe SSD Drive 1TB            | 2         | 0.82%   |
| Samsung HD105SI 1TB                   | 2         | 0.82%   |
| Samsung HD103SI 1TB                   | 2         | 0.82%   |
| Kingston SV300S37A120G 120GB SSD      | 2         | 0.82%   |
| Kingston SA400S37480G 480GB SSD       | 2         | 0.82%   |
| Kingston SA400S37120G 120GB SSD       | 2         | 0.82%   |
| Kingston NVMe SSD Drive 500GB         | 2         | 0.82%   |
| Hitachi HDS5C3020ALA632 2TB           | 2         | 0.82%   |
| HGST HTS721010A9E630 1TB              | 2         | 0.82%   |
| Fujitsu MHW2120BH 120GB               | 2         | 0.82%   |
| Crucial CT1000MX500SSD1 1TB           | 2         | 0.82%   |
| Crucial CT1000BX500SSD1 1TB           | 2         | 0.82%   |
| WDC WDS500G2B0A 500GB SSD             | 1         | 0.41%   |
| WDC WDS500G1B0B-00AS40 500GB SSD      | 1         | 0.41%   |
| WDC WDS250G1B0C-00S6U0 250GB          | 1         | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 38        | 60     | 38%     |
| WDC                 | 33        | 47     | 33%     |
| Hitachi             | 8         | 11     | 8%      |
| Samsung Electronics | 7         | 14     | 7%      |
| Toshiba             | 6         | 7      | 6%      |
| HGST                | 4         | 5      | 4%      |
| Fujitsu             | 2         | 2      | 2%      |
| Unknown             | 1         | 1      | 1%      |
| Inateck             | 1         | 1      | 1%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 18        | 27     | 24.32%  |
| Kingston            | 14        | 17     | 18.92%  |
| SanDisk             | 10        | 11     | 13.51%  |
| WDC                 | 7         | 8      | 9.46%   |
| Crucial             | 4         | 5      | 5.41%   |
| A-DATA Technology   | 4         | 4      | 5.41%   |
| Toshiba             | 3         | 3      | 4.05%   |
| SK hynix            | 2         | 2      | 2.7%    |
| Intel               | 2         | 2      | 2.7%    |
| TO Exter            | 1         | 1      | 1.35%   |
| SSSTC               | 1         | 1      | 1.35%   |
| Plextor             | 1         | 2      | 1.35%   |
| Micron Technology   | 1         | 2      | 1.35%   |
| LITEON              | 1         | 1      | 1.35%   |
| JMicron Technology  | 1         | 1      | 1.35%   |
| Intenso             | 1         | 1      | 1.35%   |
| China               | 1         | 1      | 1.35%   |
| Apple               | 1         | 1      | 1.35%   |
| Apacer              | 1         | 3      | 1.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 79        | 148    | 41.36%  |
| SSD     | 66        | 93     | 34.55%  |
| NVMe    | 41        | 53     | 21.47%  |
| MMC     | 4         | 4      | 2.09%   |
| Unknown | 1         | 2      | 0.52%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 106       | 234    | 67.52%  |
| NVMe | 41        | 53     | 26.11%  |
| SAS  | 6         | 9      | 3.82%   |
| MMC  | 4         | 4      | 2.55%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 75        | 113    | 47.77%  |
| 0.51-1.0   | 55        | 83     | 35.03%  |
| 1.01-2.0   | 19        | 30     | 12.1%   |
| 3.01-4.0   | 3         | 8      | 1.91%   |
| 2.01-3.0   | 2         | 2      | 1.27%   |
| 10.01-20.0 | 2         | 3      | 1.27%   |
| 4.01-10.0  | 1         | 2      | 0.64%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| More than 3000 | 33        | 25.38%  |
| 1001-2000      | 25        | 19.23%  |
| 501-1000       | 21        | 16.15%  |
| 2001-3000      | 18        | 13.85%  |
| 251-500        | 15        | 11.54%  |
| 101-250        | 5         | 3.85%   |
| Unknown        | 5         | 3.85%   |
| 51-100         | 4         | 3.08%   |
| 1-20           | 3         | 2.31%   |
| 21-50          | 1         | 0.77%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 26        | 19.12%  |
| 251-500        | 23        | 16.91%  |
| 501-1000       | 20        | 14.71%  |
| 51-100         | 18        | 13.24%  |
| 1001-2000      | 15        | 11.03%  |
| 1-20           | 12        | 8.82%   |
| 2001-3000      | 8         | 5.88%   |
| 21-50          | 6         | 4.41%   |
| Unknown        | 5         | 3.68%   |
| More than 3000 | 3         | 2.21%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-00V0TT0 500GB          | 1         | 1      | 7.14%   |
| WDC WD3200AAJS-56M0A0 320GB           | 1         | 1      | 7.14%   |
| WDC WD2500BEVT-60ZCT1 250GB           | 1         | 1      | 7.14%   |
| WDC WD10PURX-64E5EY0 1TB              | 1         | 1      | 7.14%   |
| SSSTC CVB-8D128-HP 128GB              | 1         | 1      | 7.14%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 1         | 1      | 7.14%   |
| Seagate ST9320325AS 320GB             | 1         | 1      | 7.14%   |
| Seagate ST3320620AS 320GB             | 1         | 1      | 7.14%   |
| Seagate ST2000LX001-1RG174 2TB        | 1         | 1      | 7.14%   |
| Seagate ST1000LM035-1RK172 1TB        | 1         | 1      | 7.14%   |
| Seagate ST1000DM003-1CH162 1TB        | 1         | 1      | 7.14%   |
| Phison 311CD0512GB                    | 1         | 1      | 7.14%   |
| Kingston SV300S37A120G 120GB SSD      | 1         | 1      | 7.14%   |
| Crucial CT1000P1SSD8 1TB              | 1         | 1      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 5         | 5      | 35.71%  |
| WDC      | 4         | 4      | 28.57%  |
| SSSTC    | 1         | 1      | 7.14%   |
| SK hynix | 1         | 1      | 7.14%   |
| Phison   | 1         | 1      | 7.14%   |
| Kingston | 1         | 1      | 7.14%   |
| Crucial  | 1         | 1      | 7.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 5      | 55.56%  |
| WDC     | 4         | 4      | 44.44%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 8         | 9      | 61.54%  |
| SSD  | 3         | 3      | 23.08%  |
| NVMe | 2         | 2      | 15.38%  |

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
| Works    | 69        | 145    | 48.25%  |
| Detected | 61        | 141    | 42.66%  |
| Malfunc  | 13        | 14     | 9.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 79        | 45.66%  |
| AMD                              | 36        | 20.81%  |
| Samsung Electronics              | 17        | 9.83%   |
| SanDisk                          | 6         | 3.47%   |
| Kingston Technology Company      | 5         | 2.89%   |
| Micron/Crucial Technology        | 4         | 2.31%   |
| ASMedia Technology               | 4         | 2.31%   |
| Phison Electronics               | 3         | 1.73%   |
| Marvell Technology Group         | 3         | 1.73%   |
| SK hynix                         | 2         | 1.16%   |
| Silicon Motion                   | 2         | 1.16%   |
| Micron Technology                | 2         | 1.16%   |
| Lite-On Technology               | 2         | 1.16%   |
| Broadcom / LSI                   | 2         | 1.16%   |
| Toshiba America Info Systems     | 1         | 0.58%   |
| Silicon Integrated Systems [SiS] | 1         | 0.58%   |
| Silicon Image                    | 1         | 0.58%   |
| Seagate Technology               | 1         | 0.58%   |
| Nvidia                           | 1         | 0.58%   |
| JMicron Technology               | 1         | 0.58%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 25        | 12.38%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 10        | 4.95%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 8         | 3.96%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8         | 3.96%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 6         | 2.97%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5         | 2.48%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5         | 2.48%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4         | 1.98%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 4         | 1.98%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 4         | 1.98%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 3         | 1.49%   |
| Kingston Company Company Non-Volatile memory controller                                 | 3         | 1.49%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3         | 1.49%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3         | 1.49%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 3         | 1.49%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3         | 1.49%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 3         | 1.49%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3         | 1.49%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 3         | 1.49%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3         | 1.49%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 2         | 0.99%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2         | 0.99%   |
| Samsung NVMe SSD Controller 980                                                         | 2         | 0.99%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 2         | 0.99%   |
| Micron Non-Volatile memory controller                                                   | 2         | 0.99%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 2         | 0.99%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 2         | 0.99%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2         | 0.99%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 2         | 0.99%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2         | 0.99%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 2         | 0.99%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 2         | 0.99%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 2         | 0.99%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2         | 0.99%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 0.99%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2         | 0.99%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2         | 0.99%   |
| AMD X370 Series Chipset SATA Controller                                                 | 2         | 0.99%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2         | 0.99%   |
| AMD 300 Series Chipset SATA Controller                                                  | 2         | 0.99%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 99        | 58.24%  |
| NVMe | 40        | 23.53%  |
| IDE  | 21        | 12.35%  |
| RAID | 9         | 5.29%   |
| SAS  | 1         | 0.59%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 86        | 67.19%  |
| AMD    | 42        | 32.81%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz           | 3         | 2.34%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 3         | 2.34%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 3         | 2.34%   |
| AMD Ryzen 7 4800H with Radeon Graphics      | 3         | 2.34%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 2         | 1.56%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 2         | 1.56%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 2         | 1.56%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 2         | 1.56%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 2         | 1.56%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2         | 1.56%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 2         | 1.56%   |
| Intel Xeon W-2145 CPU @ 3.70GHz             | 1         | 0.78%   |
| Intel Xeon W-2135 CPU @ 3.70GHz             | 1         | 0.78%   |
| Intel Xeon CPU E5-2687W v2 @ 3.40GHz        | 1         | 0.78%   |
| Intel Xeon CPU E5-2667 v3 @ 3.20GHz         | 1         | 0.78%   |
| Intel Xeon CPU E5-2470 v2 @ 2.40GHz         | 1         | 0.78%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz         | 1         | 0.78%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz         | 1         | 0.78%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz    | 1         | 0.78%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 0.78%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 0.78%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1         | 0.78%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1         | 0.78%   |
| Intel Pentium CPU G3258 @ 3.20GHz           | 1         | 0.78%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 1         | 0.78%   |
| Intel Core i9-10900T CPU @ 1.90GHz          | 1         | 0.78%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 1         | 0.78%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1         | 0.78%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 0.78%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 0.78%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1         | 0.78%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 1         | 0.78%   |
| Intel Core i7-5600U CPU @ 2.60GHz           | 1         | 0.78%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz          | 1         | 0.78%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1         | 0.78%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz          | 1         | 0.78%   |
| Intel Core i7-3740QM CPU @ 2.70GHz          | 1         | 0.78%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1         | 0.78%   |
| Intel Core i5-8365U CPU @ 1.60GHz           | 1         | 0.78%   |
| Intel Core i5-8300H CPU @ 2.30GHz           | 1         | 0.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 33        | 25.78%  |
| Intel Core i7           | 17        | 13.28%  |
| AMD Ryzen 7             | 13        | 10.16%  |
| Intel Xeon              | 7         | 5.47%   |
| Intel Core i3           | 7         | 5.47%   |
| AMD Ryzen 5             | 7         | 5.47%   |
| AMD Ryzen 9             | 6         | 4.69%   |
| Intel Core 2 Duo        | 5         | 3.91%   |
| Intel Celeron           | 4         | 3.13%   |
| Intel Pentium Dual-Core | 3         | 2.34%   |
| AMD Phenom II X4        | 3         | 2.34%   |
| Other                   | 2         | 1.56%   |
| Intel Core i9           | 2         | 1.56%   |
| Intel Core 2 Quad       | 2         | 1.56%   |
| AMD FX                  | 2         | 1.56%   |
| AMD A6                  | 2         | 1.56%   |
| Intel Pentium Silver    | 1         | 0.78%   |
| Intel Pentium Dual      | 1         | 0.78%   |
| Intel Pentium           | 1         | 0.78%   |
| Intel Core 2            | 1         | 0.78%   |
| AMD Sempron             | 1         | 0.78%   |
| AMD Ryzen 7 PRO         | 1         | 0.78%   |
| AMD Ryzen 3             | 1         | 0.78%   |
| AMD Phenom II X6        | 1         | 0.78%   |
| AMD Phenom II X2        | 1         | 0.78%   |
| AMD C-50                | 1         | 0.78%   |
| AMD Athlon              | 1         | 0.78%   |
| AMD A8                  | 1         | 0.78%   |
| AMD A10                 | 1         | 0.78%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 46        | 35.94%  |
| 2      | 43        | 33.59%  |
| 8      | 17        | 13.28%  |
| 6      | 12        | 9.38%   |
| 16     | 4         | 3.13%   |
| 12     | 3         | 2.34%   |
| 20     | 1         | 0.78%   |
| 10     | 1         | 0.78%   |
| 3      | 1         | 0.78%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 126       | 98.44%  |
| 2      | 2         | 1.56%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 82        | 64.06%  |
| 1      | 46        | 35.94%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 128       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 48        | 36.36%  |
| 0x206a7    | 7         | 5.3%    |
| 0x306c3    | 5         | 3.79%   |
| 0x806e9    | 4         | 3.03%   |
| 0x406e3    | 4         | 3.03%   |
| 0x306a9    | 4         | 3.03%   |
| 0x906ea    | 3         | 2.27%   |
| 0x6fd      | 3         | 2.27%   |
| 0x1067a    | 3         | 2.27%   |
| 0x08701021 | 3         | 2.27%   |
| 0x08600106 | 3         | 2.27%   |
| 0xa0653    | 2         | 1.52%   |
| 0x906e9    | 2         | 1.52%   |
| 0x806ea    | 2         | 1.52%   |
| 0x706a8    | 2         | 1.52%   |
| 0x506e3    | 2         | 1.52%   |
| 0x306d4    | 2         | 1.52%   |
| 0x0a201016 | 2         | 1.52%   |
| 0x0a201009 | 2         | 1.52%   |
| 0x08108109 | 2         | 1.52%   |
| 0x08001137 | 2         | 1.52%   |
| 0x07030105 | 2         | 1.52%   |
| 0x010000c8 | 2         | 1.52%   |
| 0xa0655    | 1         | 0.76%   |
| 0x906ec    | 1         | 0.76%   |
| 0x806ec    | 1         | 0.76%   |
| 0x806d1    | 1         | 0.76%   |
| 0x806c1    | 1         | 0.76%   |
| 0x706a1    | 1         | 0.76%   |
| 0x50654    | 1         | 0.76%   |
| 0x306f2    | 1         | 0.76%   |
| 0x306e4    | 1         | 0.76%   |
| 0x30678    | 1         | 0.76%   |
| 0x20655    | 1         | 0.76%   |
| 0x10677    | 1         | 0.76%   |
| 0x10676    | 1         | 0.76%   |
| 0x0a50000c | 1         | 0.76%   |
| 0x0a201204 | 1         | 0.76%   |
| 0x08108102 | 1         | 0.76%   |
| 0x0810100b | 1         | 0.76%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 20        | 15.63%  |
| Haswell       | 12        | 9.38%   |
| Zen 2         | 11        | 8.59%   |
| Skylake       | 10        | 7.81%   |
| IvyBridge     | 9         | 7.03%   |
| SandyBridge   | 8         | 6.25%   |
| Zen 3         | 7         | 5.47%   |
| Penryn        | 7         | 5.47%   |
| Zen+          | 6         | 4.69%   |
| Zen           | 5         | 3.91%   |
| K10           | 5         | 3.91%   |
| Core          | 5         | 3.91%   |
| Goldmont plus | 3         | 2.34%   |
| CometLake     | 3         | 2.34%   |
| Westmere      | 2         | 1.56%   |
| Silvermont    | 2         | 1.56%   |
| Puma          | 2         | 1.56%   |
| Piledriver    | 2         | 1.56%   |
| Broadwell     | 2         | 1.56%   |
| TigerLake     | 1         | 0.78%   |
| Steamroller   | 1         | 0.78%   |
| Nehalem       | 1         | 0.78%   |
| K10 Llano     | 1         | 0.78%   |
| Jaguar        | 1         | 0.78%   |
| Icelake       | 1         | 0.78%   |
| Bobcat        | 1         | 0.78%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 62        | 40.26%  |
| Nvidia            | 50        | 32.47%  |
| AMD               | 40        | 25.97%  |
| S3 Graphics       | 1         | 0.65%   |
| ASPEED Technology | 1         | 0.65%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6         | 3.82%   |
| AMD Renoir                                                                  | 6         | 3.82%   |
| Intel HD Graphics 620                                                       | 5         | 3.18%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 5         | 3.18%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 4         | 2.55%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 4         | 2.55%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 4         | 2.55%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 4         | 2.55%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 4         | 2.55%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 3         | 1.91%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 3         | 1.91%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3         | 1.91%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 3         | 1.91%   |
| Intel UHD Graphics 620                                                      | 3         | 1.91%   |
| Intel HD Graphics 630                                                       | 3         | 1.91%   |
| Intel HD Graphics 530                                                       | 3         | 1.91%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2         | 1.27%   |
| Nvidia GK208B [GeForce GT 710]                                              | 2         | 1.27%   |
| Nvidia GF108 [GeForce GT 630]                                               | 2         | 1.27%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 2         | 1.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 1.27%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)         | 2         | 1.27%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)           | 2         | 1.27%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 2         | 1.27%   |
| Intel HD Graphics 5500                                                      | 2         | 1.27%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 2         | 1.27%   |
| Intel Core Processor Integrated Graphics Controller                         | 2         | 1.27%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2         | 1.27%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 2         | 1.27%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2         | 1.27%   |
| AMD Tonga PRO [Radeon R9 285/380]                                           | 2         | 1.27%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                         | 2         | 1.27%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2         | 1.27%   |
| S3 Graphics 86c764/765 [Trio32/64/64V+]                                     | 1         | 0.64%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 1         | 0.64%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1         | 0.64%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1         | 0.64%   |
| Nvidia GT216 [GeForce GT 220]                                               | 1         | 0.64%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 1         | 0.64%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                 | 1         | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 39        | 30.47%  |
| 1 x Nvidia      | 32        | 25%     |
| 1 x AMD         | 32        | 25%     |
| Intel + Nvidia  | 15        | 11.72%  |
| Intel + AMD     | 6         | 4.69%   |
| 2 x AMD         | 1         | 0.78%   |
| 1 x S3 Graphics | 1         | 0.78%   |
| Nvidia + ASPEED | 1         | 0.78%   |
| AMD + Nvidia    | 1         | 0.78%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 97        | 75.19%  |
| Proprietary | 27        | 20.93%  |
| Unknown     | 5         | 3.88%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 80        | 60.61%  |
| 1.01-2.0   | 16        | 12.12%  |
| 3.01-4.0   | 8         | 6.06%   |
| 0.01-0.5   | 8         | 6.06%   |
| 7.01-8.0   | 6         | 4.55%   |
| 0.51-1.0   | 5         | 3.79%   |
| 5.01-6.0   | 3         | 2.27%   |
| 8.01-16.0  | 3         | 2.27%   |
| 16.01-24.0 | 2         | 1.52%   |
| 2.01-3.0   | 1         | 0.76%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Goldstar             | 18        | 12.08%  |
| LG Display           | 16        | 10.74%  |
| Samsung Electronics  | 15        | 10.07%  |
| Chimei Innolux       | 13        | 8.72%   |
| Dell                 | 12        | 8.05%   |
| AU Optronics         | 11        | 7.38%   |
| Hewlett-Packard      | 7         | 4.7%    |
| BOE                  | 7         | 4.7%    |
| Ancor Communications | 6         | 4.03%   |
| Philips              | 5         | 3.36%   |
| BenQ                 | 5         | 3.36%   |
| Acer                 | 4         | 2.68%   |
| Lenovo               | 3         | 2.01%   |
| AOC                  | 3         | 2.01%   |
| ViewSonic            | 2         | 1.34%   |
| Medion               | 2         | 1.34%   |
| LG Electronics       | 2         | 1.34%   |
| Iiyama               | 2         | 1.34%   |
| ASUSTek Computer     | 2         | 1.34%   |
| Vizio                | 1         | 0.67%   |
| TCL                  | 1         | 0.67%   |
| Sony                 | 1         | 0.67%   |
| Sharp                | 1         | 0.67%   |
| Sceptre Tech         | 1         | 0.67%   |
| LG Philips           | 1         | 0.67%   |
| InfoVision           | 1         | 0.67%   |
| Hitachi              | 1         | 0.67%   |
| Fujitsu Siemens      | 1         | 0.67%   |
| Denver               | 1         | 0.67%   |
| CSO                  | 1         | 0.67%   |
| CPT                  | 1         | 0.67%   |
| Apple                | 1         | 0.67%   |
| AGO                  | 1         | 0.67%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| ViewSonic VX3211-2K VSCF634 2560x1440 700x390mm 31.5-inch             | 2         | 1.29%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 1.29%   |
| Hewlett-Packard LV1911 HWP3005 1366x768 410x230mm 18.5-inch           | 2         | 1.29%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 2         | 1.29%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 2         | 1.29%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                | 2         | 1.29%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 2         | 1.29%   |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                 | 2         | 1.29%   |
| ASUSTek Computer VG245 AUS24A1 1920x1080 530x300mm 24.0-inch          | 2         | 1.29%   |
| Vizio E43u-D2 VIZ1018 3840x2160 953x543mm 43.2-inch                   | 1         | 0.65%   |
| TCL LCD TV TCL0030 1920x1080 708x398mm 32.0-inch                      | 1         | 0.65%   |
| Sony Nvidia Defaul t Flat Panel SNY06FA 1600x900 360x200mm 16.2-inch  | 1         | 0.65%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch               | 1         | 0.65%   |
| Sceptre Tech Sceptre E19 SPT07A8 1366x768 575x323mm 26.0-inch         | 1         | 0.65%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch     | 1         | 0.65%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch     | 1         | 0.65%   |
| Samsung Electronics T27B300 SAM0933 1920x1080 598x336mm 27.0-inch     | 1         | 0.65%   |
| Samsung Electronics SyncMaster SAM0524 1920x1080 477x268mm 21.5-inch  | 1         | 0.65%   |
| Samsung Electronics SyncMaster SAM00A2 1024x768 304x228mm 15.0-inch   | 1         | 0.65%   |
| Samsung Electronics SMS27A850T SAM0887 2560x1440 518x324mm 24.1-inch  | 1         | 0.65%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch  | 1         | 0.65%   |
| Samsung Electronics S34J55x SAM0F72 3440x1440 797x333mm 34.0-inch     | 1         | 0.65%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch     | 1         | 0.65%   |
| Samsung Electronics S23B550 SAM0919 1920x1080 510x290mm 23.1-inch     | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch  | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC3449 1366x768 309x174mm 14.0-inch  | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 309x174mm 14.0-inch  | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SDC424B 3840x2160 344x194mm 15.5-inch | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SDC324E 1600x900 309x174mm 14.0-inch  | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 950x540mm 43.0-inch | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SAM08FC 1366x768                      | 1         | 0.65%   |
| Philips PHL 258B6QU PHL08F5 2560x1440 553x311mm 25.0-inch             | 1         | 0.65%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 1         | 0.65%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 1         | 0.65%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 1         | 0.65%   |
| Philips 150S PHL0812 1024x768 307x230mm 15.1-inch                     | 1         | 0.65%   |
| Philips 150S PHL0805 1024x768 307x230mm 15.1-inch                     | 1         | 0.65%   |
| Medion MD30999PE MED8928 1440x900 410x256mm 19.0-inch                 | 1         | 0.65%   |
| Medion MD20581 MED369A 1920x1080 597x336mm 27.0-inch                  | 1         | 0.65%   |
| LG Philips LCD Monitor LPLDB00 1280x800 331x207mm 15.4-inch           | 1         | 0.65%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 63        | 46.32%  |
| 1366x768 (WXGA)    | 20        | 14.71%  |
| 3840x2160 (4K)     | 10        | 7.35%   |
| 2560x1440 (QHD)    | 8         | 5.88%   |
| 1600x900 (HD+)     | 6         | 4.41%   |
| 1920x1200 (WUXGA)  | 5         | 3.68%   |
| 2560x1080          | 4         | 2.94%   |
| 1024x768 (XGA)     | 4         | 2.94%   |
| 3440x1440          | 3         | 2.21%   |
| 1680x1050 (WSXGA+) | 3         | 2.21%   |
| 1440x900 (WXGA+)   | 3         | 2.21%   |
| 1280x1024 (SXGA)   | 3         | 2.21%   |
| 640x480            | 1         | 0.74%   |
| 3840x2400          | 1         | 0.74%   |
| 2160x1440          | 1         | 0.74%   |
| 1280x800 (WXGA)    | 1         | 0.74%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 34        | 23.29%  |
| 27      | 16        | 10.96%  |
| 21      | 14        | 9.59%   |
| 24      | 11        | 7.53%   |
| 14      | 11        | 7.53%   |
| 17      | 10        | 6.85%   |
| 23      | 8         | 5.48%   |
| 13      | 7         | 4.79%   |
| 34      | 5         | 3.42%   |
| 31      | 3         | 2.05%   |
| 22      | 3         | 2.05%   |
| 19      | 3         | 2.05%   |
| 18      | 3         | 2.05%   |
| 11      | 3         | 2.05%   |
| Unknown | 3         | 2.05%   |
| 26      | 2         | 1.37%   |
| 25      | 2         | 1.37%   |
| 20      | 2         | 1.37%   |
| 84      | 1         | 0.68%   |
| 74      | 1         | 0.68%   |
| 42      | 1         | 0.68%   |
| 35      | 1         | 0.68%   |
| 32      | 1         | 0.68%   |
| 12      | 1         | 0.68%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 48        | 33.33%  |
| 501-600     | 33        | 22.92%  |
| 401-500     | 25        | 17.36%  |
| 351-400     | 10        | 6.94%   |
| 201-300     | 9         | 6.25%   |
| 701-800     | 6         | 4.17%   |
| 601-700     | 6         | 4.17%   |
| Unknown     | 3         | 2.08%   |
| 1501-2000   | 2         | 1.39%   |
| 801-900     | 1         | 0.69%   |
| 901-1000    | 1         | 0.69%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 99        | 76.15%  |
| 16/10   | 13        | 10%     |
| 21/9    | 6         | 4.62%   |
| 4/3     | 5         | 3.85%   |
| 5/4     | 3         | 2.31%   |
| Unknown | 3         | 2.31%   |
| 3/2     | 1         | 0.77%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 34        | 23.29%  |
| 201-250        | 31        | 21.23%  |
| 301-350        | 17        | 11.64%  |
| 81-90          | 14        | 9.59%   |
| 351-500        | 10        | 6.85%   |
| 121-130        | 8         | 5.48%   |
| 151-200        | 7         | 4.79%   |
| 251-300        | 6         | 4.11%   |
| 141-150        | 5         | 3.42%   |
| 71-80          | 4         | 2.74%   |
| 51-60          | 3         | 2.05%   |
| Unknown        | 3         | 2.05%   |
| More than 1000 | 2         | 1.37%   |
| 501-1000       | 1         | 0.68%   |
| 91-100         | 1         | 0.68%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 53        | 37.59%  |
| 101-120       | 42        | 29.79%  |
| 121-160       | 35        | 24.82%  |
| 161-240       | 4         | 2.84%   |
| More than 240 | 3         | 2.13%   |
| Unknown       | 3         | 2.13%   |
| 1-50          | 1         | 0.71%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 98        | 75.97%  |
| 2     | 23        | 17.83%  |
| 0     | 5         | 3.88%   |
| 3     | 3         | 2.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 76        | 38.58%  |
| Intel                            | 64        | 32.49%  |
| Qualcomm Atheros                 | 19        | 9.64%   |
| Broadcom                         | 10        | 5.08%   |
| Ralink                           | 5         | 2.54%   |
| Broadcom Limited                 | 3         | 1.52%   |
| Samsung Electronics              | 2         | 1.02%   |
| Dell                             | 2         | 1.02%   |
| ASIX Electronics                 | 2         | 1.02%   |
| ZyXEL Communications             | 1         | 0.51%   |
| TP-Link                          | 1         | 0.51%   |
| TOMTOM                           | 1         | 0.51%   |
| Silicon Integrated Systems [SiS] | 1         | 0.51%   |
| Sierra Wireless                  | 1         | 0.51%   |
| Ralink Technology                | 1         | 0.51%   |
| NetXen Incorporated              | 1         | 0.51%   |
| MediaTek                         | 1         | 0.51%   |
| Manta                            | 1         | 0.51%   |
| Lenovo                           | 1         | 0.51%   |
| Edimax Technology                | 1         | 0.51%   |
| DisplayLink                      | 1         | 0.51%   |
| D-Link System                    | 1         | 0.51%   |
| AVM                              | 1         | 0.51%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 55        | 23.31%  |
| Intel Wi-Fi 6 AX200                                               | 12        | 5.08%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 2.97%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 2.12%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 2.12%   |
| Intel I211 Gigabit Network Connection                             | 5         | 2.12%   |
| Intel Wireless 8265 / 8275                                        | 4         | 1.69%   |
| Intel Wireless 8260                                               | 4         | 1.69%   |
| Intel Wireless 7260                                               | 4         | 1.69%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 1.27%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3         | 1.27%   |
| Intel Wireless 3165                                               | 3         | 1.27%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 0.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.85%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 0.85%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 0.85%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 2         | 0.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 0.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 0.85%   |
| Intel Wireless-AC 9260                                            | 2         | 0.85%   |
| Intel Wireless 7265                                               | 2         | 0.85%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 0.85%   |
| Intel I210 Gigabit Network Connection                             | 2         | 0.85%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.85%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.85%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.85%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.85%   |
| Intel Ethernet Connection (2) I218-LM                             | 2         | 0.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 0.85%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 0.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 0.85%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 0.85%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 0.85%   |
| ZyXEL NWD2205 802.11n Wireless N Adapter [Realtek RTL8192CU]      | 1         | 0.42%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 1         | 0.42%   |
| TOMTOM GO 60                                                      | 1         | 0.42%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.42%   |
| Sierra Wireless MC8305 Modem                                      | 1         | 0.42%   |
| Samsung Kiera                                                     | 1         | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 48        | 48%     |
| Realtek Semiconductor | 19        | 19%     |
| Qualcomm Atheros      | 12        | 12%     |
| Broadcom              | 6         | 6%      |
| Ralink                | 5         | 5%      |
| ZyXEL Communications  | 1         | 1%      |
| TP-Link               | 1         | 1%      |
| Sierra Wireless       | 1         | 1%      |
| Ralink Technology     | 1         | 1%      |
| MediaTek              | 1         | 1%      |
| Edimax Technology     | 1         | 1%      |
| Dell                  | 1         | 1%      |
| D-Link System         | 1         | 1%      |
| Broadcom Limited      | 1         | 1%      |
| AVM                   | 1         | 1%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 12        | 12%     |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 5         | 5%      |
| Intel Wireless 8265 / 8275                                     | 4         | 4%      |
| Intel Wireless 8260                                            | 4         | 4%      |
| Intel Wireless 7260                                            | 4         | 4%      |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 3         | 3%      |
| Intel Wireless 3165                                            | 3         | 3%      |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 2         | 2%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 2%      |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 2%      |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2         | 2%      |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 2         | 2%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 2%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 2         | 2%      |
| Intel Wireless-AC 9260                                         | 2         | 2%      |
| Intel Wireless 7265                                            | 2         | 2%      |
| Intel Tiger Lake PCH CNVi WiFi                                 | 2         | 2%      |
| Intel Cannon Lake PCH CNVi WiFi                                | 2         | 2%      |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 2%      |
| ZyXEL NWD2205 802.11n Wireless N Adapter [Realtek RTL8192CU]   | 1         | 1%      |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 1         | 1%      |
| Sierra Wireless MC8305 Modem                                   | 1         | 1%      |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 1         | 1%      |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1         | 1%      |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 1%      |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 1%      |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 1%      |
| Realtek 802.11n                                                | 1         | 1%      |
| Ralink RT3072 Wireless Adapter                                 | 1         | 1%      |
| Ralink RT3062 Wireless 802.11n 2T/2R                           | 1         | 1%      |
| Ralink RT3060 Wireless 802.11n 1T/1R                           | 1         | 1%      |
| Ralink RT2561/RT61 802.11g PCI                                 | 1         | 1%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 1%      |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 1%      |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 1         | 1%      |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 1%      |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 1         | 1%      |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 1         | 1%      |
| Intel WiFi Link 5100                                           | 1         | 1%      |
| Intel Wi-Fi 6 AX201                                            | 1         | 1%      |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 69        | 53.91%  |
| Intel                            | 35        | 27.34%  |
| Qualcomm Atheros                 | 9         | 7.03%   |
| Broadcom                         | 5         | 3.91%   |
| Samsung Electronics              | 2         | 1.56%   |
| Broadcom Limited                 | 2         | 1.56%   |
| ASIX Electronics                 | 2         | 1.56%   |
| Silicon Integrated Systems [SiS] | 1         | 0.78%   |
| NetXen Incorporated              | 1         | 0.78%   |
| Lenovo                           | 1         | 0.78%   |
| DisplayLink                      | 1         | 0.78%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 55        | 41.35%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 7         | 5.26%   |
| Realtek RTL8125 2.5GbE Controller                                    | 5         | 3.76%   |
| Intel I211 Gigabit Network Connection                                | 5         | 3.76%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller            | 3         | 2.26%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                             | 2         | 1.5%    |
| Intel I210 Gigabit Network Connection                                | 2         | 1.5%    |
| Intel Ethernet Connection I219-LM                                    | 2         | 1.5%    |
| Intel Ethernet Connection I217-V                                     | 2         | 1.5%    |
| Intel Ethernet Connection (4) I219-LM                                | 2         | 1.5%    |
| Intel Ethernet Connection (3) I218-LM                                | 2         | 1.5%    |
| Intel Ethernet Connection (2) I218-LM                                | 2         | 1.5%    |
| Intel 82579V Gigabit Network Connection                              | 2         | 1.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 2         | 1.5%    |
| ASIX AX88179 Gigabit Ethernet                                        | 2         | 1.5%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter        | 1         | 0.75%   |
| Samsung Kiera                                                        | 1         | 0.75%   |
| Samsung Galaxy series, misc. (tethering mode)                        | 1         | 0.75%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                      | 1         | 0.75%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                           | 1         | 0.75%   |
| Realtek Killer E3000 2.5GbE Controller                               | 1         | 0.75%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                     | 1         | 0.75%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                               | 1         | 0.75%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                            | 1         | 0.75%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                             | 1         | 0.75%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                           | 1         | 0.75%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                        | 1         | 0.75%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet       | 1         | 0.75%   |
| NetXen Incorporated NX3031 Multifunction 1/10-Gigabit Server Adapter | 1         | 0.75%   |
| Lenovo OneLink+ Giga                                                 | 1         | 0.75%   |
| Intel I350 Gigabit Network Connection                                | 1         | 0.75%   |
| Intel Ethernet Controller I225-V                                     | 1         | 0.75%   |
| Intel Ethernet Connection I219-V                                     | 1         | 0.75%   |
| Intel Ethernet Connection I217-LM                                    | 1         | 0.75%   |
| Intel Ethernet Connection (7) I219-V                                 | 1         | 0.75%   |
| Intel Ethernet Connection (6) I219-LM                                | 1         | 0.75%   |
| Intel Ethernet Connection (2) I219-LM                                | 1         | 0.75%   |
| Intel Ethernet Connection (11) I219-V                                | 1         | 0.75%   |
| Intel Ethernet Connection (10) I219-V                                | 1         | 0.75%   |
| Intel 82574L Gigabit Network Connection                              | 1         | 0.75%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 118       | 54.13%  |
| WiFi     | 97        | 44.5%   |
| Unknown  | 3         | 1.38%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 72        | 52.17%  |
| WiFi     | 65        | 47.1%   |
| Unknown  | 1         | 0.72%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 78        | 60.94%  |
| 1     | 42        | 32.81%  |
| 3     | 6         | 4.69%   |
| 5     | 1         | 0.78%   |
| 4     | 1         | 0.78%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 94        | 72.31%  |
| Yes  | 36        | 27.69%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 32        | 40.51%  |
| Realtek Semiconductor           | 10        | 12.66%  |
| Cambridge Silicon Radio         | 9         | 11.39%  |
| Qualcomm Atheros Communications | 6         | 7.59%   |
| IMC Networks                    | 4         | 5.06%   |
| Foxconn / Hon Hai               | 3         | 3.8%    |
| Broadcom                        | 3         | 3.8%    |
| ASUSTek Computer                | 3         | 3.8%    |
| Lite-On Technology              | 2         | 2.53%   |
| Dell                            | 2         | 2.53%   |
| Realtek                         | 1         | 1.27%   |
| MediaTek                        | 1         | 1.27%   |
| Belkin Components               | 1         | 1.27%   |
| Apple                           | 1         | 1.27%   |
| Alps Electric                   | 1         | 1.27%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 11        | 13.92%  |
| Intel AX200 Bluetooth                                                               | 10        | 12.66%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 9         | 11.39%  |
| Realtek  Bluetooth 4.2 Adapter                                                      | 5         | 6.33%   |
| Realtek Bluetooth Radio                                                             | 4         | 5.06%   |
| Intel AX201 Bluetooth                                                               | 4         | 5.06%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 3         | 3.8%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 3         | 3.8%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 2.53%   |
| IMC Networks Bluetooth Radio                                                        | 2         | 2.53%   |
| IMC Networks Bluetooth Device                                                       | 2         | 2.53%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 1.27%   |
| Realtek Bluetooth Radio                                                             | 1         | 1.27%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 1.27%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 1.27%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 1.27%   |
| MediaTek Wireless_Device                                                            | 1         | 1.27%   |
| Lite-On Bluetooth Device                                                            | 1         | 1.27%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 1.27%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 1.27%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 1.27%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.27%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 1.27%   |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 1         | 1.27%   |
| Dell Broadcom BCM20702A0 Bluetooth                                                  | 1         | 1.27%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 1.27%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 1         | 1.27%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 1         | 1.27%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 1         | 1.27%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                               | 1         | 1.27%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 1         | 1.27%   |
| ASUS Bluetooth Adapter                                                              | 1         | 1.27%   |
| ASUS ASUS USB-BT500                                                                 | 1         | 1.27%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 1         | 1.27%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 1         | 1.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 81        | 42.19%  |
| AMD                              | 51        | 26.56%  |
| Nvidia                           | 39        | 20.31%  |
| C-Media Electronics              | 5         | 2.6%    |
| Creative Labs                    | 3         | 1.56%   |
| Texas Instruments                | 2         | 1.04%   |
| Logitech                         | 2         | 1.04%   |
| Lenovo                           | 2         | 1.04%   |
| Silicon Integrated Systems [SiS] | 1         | 0.52%   |
| Sennheiser Communications        | 1         | 0.52%   |
| JMTek                            | 1         | 0.52%   |
| GN Netcom                        | 1         | 0.52%   |
| ESS Technology                   | 1         | 0.52%   |
| BEHRINGER International          | 1         | 0.52%   |
| ASUSTek Computer                 | 1         | 0.52%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 12        | 5.36%   |
| AMD Starship/Matisse HD Audio Controller                                   | 11        | 4.91%   |
| AMD Family 17h/19h HD Audio Controller                                     | 11        | 4.91%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 9         | 4.02%   |
| Intel Cannon Lake PCH cAVS                                                 | 7         | 3.13%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 7         | 3.13%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 7         | 3.13%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 7         | 3.13%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6         | 2.68%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 6         | 2.68%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5         | 2.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 2.23%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 2.23%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5         | 2.23%   |
| AMD FCH Azalia Controller                                                  | 5         | 2.23%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 5         | 2.23%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 4         | 1.79%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 1.34%   |
| Nvidia GP108 High Definition Audio Controller                              | 3         | 1.34%   |
| Nvidia GK106 HDMI Audio Controller                                         | 3         | 1.34%   |
| Nvidia GA102 High Definition Audio Controller                              | 3         | 1.34%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.34%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 1.34%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 1.34%   |
| Intel 200 Series PCH HD Audio                                              | 3         | 1.34%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3         | 1.34%   |
| AMD Kabini HDMI/DP Audio                                                   | 3         | 1.34%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 0.89%   |
| Nvidia GM206 High Definition Audio Controller                              | 2         | 0.89%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 0.89%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 0.89%   |
| Logitech Headset H390                                                      | 2         | 0.89%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 0.89%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 2         | 0.89%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 0.89%   |
| Intel Audio device                                                         | 2         | 0.89%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 0.89%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 0.89%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                              | 2         | 0.89%   |
| C-Media Electronics CM108 Audio Controller                                 | 2         | 0.89%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Samsung Electronics    | 21        | 22.34%  |
| SK hynix               | 13        | 13.83%  |
| Kingston               | 13        | 13.83%  |
| Unknown                | 10        | 10.64%  |
| Corsair                | 7         | 7.45%   |
| G.Skill                | 6         | 6.38%   |
| Crucial                | 6         | 6.38%   |
| Micron Technology      | 5         | 5.32%   |
| Ramaxel Technology     | 2         | 2.13%   |
| Patriot                | 2         | 2.13%   |
| A-DATA Technology      | 2         | 2.13%   |
| Unknown (000004B30000) | 1         | 1.06%   |
| Team                   | 1         | 1.06%   |
| Smart                  | 1         | 1.06%   |
| Goodram                | 1         | 1.06%   |
| GeIL                   | 1         | 1.06%   |
| Elpida                 | 1         | 1.06%   |
| AMD                    | 1         | 1.06%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s      | 2         | 1.94%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s      | 2         | 1.94%   |
| Kingston RAM KHX3600C18D4/32GX 32GB DIMM DDR4 3600MT/s     | 2         | 1.94%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s     | 2         | 1.94%   |
| G.Skill RAM F4-2400C15-8GNT 8GB DIMM DDR4 2666MT/s         | 2         | 1.94%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                  | 1         | 0.97%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                    | 1         | 0.97%   |
| Unknown RAM Module 4GB SODIMM DDR2 667MT/s                 | 1         | 0.97%   |
| Unknown RAM Module 4096MB SODIMM DDR3                      | 1         | 0.97%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                 | 1         | 0.97%   |
| Unknown RAM Module 2048MB SODIMM 1067MT/s                  | 1         | 0.97%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s               | 1         | 0.97%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                | 1         | 0.97%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                    | 1         | 0.97%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                 | 1         | 0.97%   |
| Unknown RAM Module 1024MB SODIMM 1067MT/s                  | 1         | 0.97%   |
| Unknown RAM 992124 (997124) 8GB DIMM DDR3 1600MT/s         | 1         | 0.97%   |
| Unknown (000004B30000) RAM Module 32GB DIMM DDR3 1333MT/s  | 1         | 0.97%   |
| Team RAM TEAMGROUP-UD4-2400 8GB DIMM DDR4 3007MT/s         | 1         | 0.97%   |
| Smart RAM SH564568FH8NWPHSFG 2GB SODIMM DDR3 1333MT/s      | 1         | 0.97%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s               | 1         | 0.97%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM SDRAM 2048MT/s    | 1         | 0.97%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s     | 1         | 0.97%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s     | 1         | 0.97%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s     | 1         | 0.97%   |
| SK hynix RAM HMT351R7CFR8C-PB 4GB DIMM DDR3 1600MT/s       | 1         | 0.97%   |
| SK hynix RAM HMT151R7BFR4C-G7 4GB DIMM DDR3 1066MT/s       | 1         | 0.97%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s    | 1         | 0.97%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s     | 1         | 0.97%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s     | 1         | 0.97%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16384MB SODIMM DDR4 2667MT/s | 1         | 0.97%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s     | 1         | 0.97%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s     | 1         | 0.97%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s     | 1         | 0.97%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s | 1         | 0.97%   |
| Samsung RAM Module 4096MB SODIMM DDR4 2400MT/s             | 1         | 0.97%   |
| Samsung RAM M471B5673FH0-CH9 2048MB DIMM SDRAM 4199MT/s    | 1         | 0.97%   |
| Samsung RAM M471B5673EH1-CH9 2GB SODIMM DDR3 1334MT/s      | 1         | 0.97%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s      | 1         | 0.97%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s     | 1         | 0.97%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 43        | 52.44%  |
| DDR3    | 24        | 29.27%  |
| DDR2    | 5         | 6.1%    |
| LPDDR4  | 4         | 4.88%   |
| Unknown | 3         | 3.66%   |
| SDRAM   | 2         | 2.44%   |
| LPDDR3  | 1         | 1.22%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 41        | 50%     |
| SODIMM       | 38        | 46.34%  |
| Row Of Chips | 2         | 2.44%   |
| Chip         | 1         | 1.22%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 36        | 38.71%  |
| 4096  | 20        | 21.51%  |
| 16384 | 16        | 17.2%   |
| 2048  | 11        | 11.83%  |
| 32768 | 6         | 6.45%   |
| 1024  | 4         | 4.3%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 17        | 18.48%  |
| 2667    | 16        | 17.39%  |
| 3200    | 10        | 10.87%  |
| 1333    | 9         | 9.78%   |
| 3600    | 5         | 5.43%   |
| 2133    | 5         | 5.43%   |
| 2400    | 3         | 3.26%   |
| 1867    | 3         | 3.26%   |
| 800     | 3         | 3.26%   |
| 667     | 3         | 3.26%   |
| 3800    | 2         | 2.17%   |
| 2666    | 2         | 2.17%   |
| 4267    | 1         | 1.09%   |
| 4266    | 1         | 1.09%   |
| 4199    | 1         | 1.09%   |
| 3866    | 1         | 1.09%   |
| 3733    | 1         | 1.09%   |
| 3466    | 1         | 1.09%   |
| 3400    | 1         | 1.09%   |
| 3007    | 1         | 1.09%   |
| 2934    | 1         | 1.09%   |
| 2048    | 1         | 1.09%   |
| 1334    | 1         | 1.09%   |
| 1067    | 1         | 1.09%   |
| 1066    | 1         | 1.09%   |
| Unknown | 1         | 1.09%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 2         | 22.22%  |
| Canon               | 2         | 22.22%  |
| Brother Industries  | 2         | 22.22%  |
| Samsung Electronics | 1         | 11.11%  |
| Prolific Technology | 1         | 11.11%  |
| Kyocera             | 1         | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Samsung SCX-4200 series       | 1         | 11.11%  |
| Prolific PL2305 Parallel Port | 1         | 11.11%  |
| Kyocera FS-1030D printer      | 1         | 11.11%  |
| HP ENVY 4500 series           | 1         | 11.11%  |
| HP DeskJet 6940 series        | 1         | 11.11%  |
| Canon G3020 series            | 1         | 11.11%  |
| Canon CanoScan LiDE 300       | 1         | 11.11%  |
| Brother Printer               | 1         | 11.11%  |
| Brother HL-L3210CW series     | 1         | 11.11%  |

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
| Chicony Electronics                    | 17        | 22.37%  |
| Logitech                               | 10        | 13.16%  |
| Acer                                   | 7         | 9.21%   |
| IMC Networks                           | 6         | 7.89%   |
| Sunplus Innovation Technology          | 5         | 6.58%   |
| Realtek Semiconductor                  | 5         | 6.58%   |
| Quanta                                 | 4         | 5.26%   |
| Microdia                               | 4         | 5.26%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 5.26%   |
| Lite-On Technology                     | 2         | 2.63%   |
| Z-Star Microelectronics                | 1         | 1.32%   |
| Syntek                                 | 1         | 1.32%   |
| Suyin                                  | 1         | 1.32%   |
| Silicon Motion                         | 1         | 1.32%   |
| Ricoh                                  | 1         | 1.32%   |
| Microsoft                              | 1         | 1.32%   |
| Luxvisions Innotech Limited            | 1         | 1.32%   |
| Hewlett-Packard                        | 1         | 1.32%   |
| Generalplus Technology                 | 1         | 1.32%   |
| Cubeternet                             | 1         | 1.32%   |
| Creative Technology                    | 1         | 1.32%   |
| ALi                                    | 1         | 1.32%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 5         | 6.41%   |
| Logitech Webcam C270                                | 3         | 3.85%   |
| Chicony HD Webcam                                   | 3         | 3.85%   |
| Sunplus HD WebCam                                   | 2         | 2.56%   |
| Realtek Integrated_Webcam_HD                        | 2         | 2.56%   |
| Microdia Integrated_Webcam_HD                       | 2         | 2.56%   |
| Logitech HD Pro Webcam C920                         | 2         | 2.56%   |
| Logitech B525 HD Webcam                             | 2         | 2.56%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 2         | 2.56%   |
| IMC Networks Integrated Camera                      | 2         | 2.56%   |
| Acer HD Webcam                                      | 2         | 2.56%   |
| Acer BisonCam, NB Pro                               | 2         | 2.56%   |
| Z-Star Venus USB2.0 Camera                          | 1         | 1.28%   |
| Syntek Lenovo EasyCamera                            | 1         | 1.28%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 1         | 1.28%   |
| Sunplus Laptop_Integrated_Webcam_HD                 | 1         | 1.28%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 1.28%   |
| Sunplus 1.3M HD WebCam                              | 1         | 1.28%   |
| Silicon Motion WebCam SC-13HDN10939N                | 1         | 1.28%   |
| Ricoh Sony Vaio Integrated Webcam                   | 1         | 1.28%   |
| Realtek USB2.0 HD UVC WebCam                        | 1         | 1.28%   |
| Realtek USB Camera                                  | 1         | 1.28%   |
| Realtek Lenovo EasyCamera                           | 1         | 1.28%   |
| Realtek Integrated Webcam HD                        | 1         | 1.28%   |
| Quanta HP Wide Vision HD Camera                     | 1         | 1.28%   |
| Quanta HP TrueVision HD Camera                      | 1         | 1.28%   |
| Quanta HD Webcam                                    | 1         | 1.28%   |
| Quanta HD User Facing                               | 1         | 1.28%   |
| Microsoft LifeCam VX-700                            | 1         | 1.28%   |
| Microdia Webcam Vitade AF                           | 1         | 1.28%   |
| Microdia Laptop_Integrated_Webcam_0.3M              | 1         | 1.28%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 1.28%   |
| Logitech Webcam C250                                | 1         | 1.28%   |
| Logitech QuickCam Pro 4000                          | 1         | 1.28%   |
| Logitech HD Webcam C615                             | 1         | 1.28%   |
| Lite-On Integrated Camera                           | 1         | 1.28%   |
| Lite-On HP 5MP Camera                               | 1         | 1.28%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 1         | 1.28%   |
| IMC Networks USB2.0 UVC HD Webcam                   | 1         | 1.28%   |
| HP Webcam 3100                                      | 1         | 1.28%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 6         | 40%     |
| Validity Sensors           | 5         | 33.33%  |
| Upek                       | 1         | 6.67%   |
| STMicroelectronics         | 1         | 6.67%   |
| Shenzhen Goodix Technology | 1         | 6.67%   |
| AuthenTec                  | 1         | 6.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor           | 2         | 13.33%  |
| Synaptics  WBDI                                        | 2         | 13.33%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 2         | 13.33%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 6.67%   |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 6.67%   |
| Validity Sensors Synaptics WBDI                        | 1         | 6.67%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 6.67%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 6.67%   |
| STMicroelectronics Fingerprint Reader                  | 1         | 6.67%   |
| Shenzhen Goodix  Fingerprint Device                    | 1         | 6.67%   |
| AuthenTec AES1660 Fingerprint Sensor                   | 1         | 6.67%   |
| Unknown                                                | 1         | 6.67%   |

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
| 0     | 87        | 66.41%  |
| 1     | 35        | 26.72%  |
| 2     | 9         | 6.87%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 15        | 28.85%  |
| Graphics card            | 10        | 19.23%  |
| Chipcard                 | 8         | 15.38%  |
| Net/wireless             | 6         | 11.54%  |
| Sound                    | 3         | 5.77%   |
| Multimedia controller    | 3         | 5.77%   |
| Unassigned class         | 2         | 3.85%   |
| Bluetooth                | 2         | 3.85%   |
| Net/ethernet             | 1         | 1.92%   |
| Communication controller | 1         | 1.92%   |
| Camera                   | 1         | 1.92%   |

