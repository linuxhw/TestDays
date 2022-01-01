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

| Vendor     | Model                       | Form-Factor | Probe                                                      | Date         |
|------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell       | 0RY007                      | Desktop     | [d51d13fdd1](https://linux-hardware.org/?probe=d51d13fdd1) | Dec 31, 2021 |
| ASUSTek    | ROG CROSSHAIR VIII HERO     | Desktop     | [559c6e472e](https://linux-hardware.org/?probe=559c6e472e) | Dec 30, 2021 |
| Dell       | XPS 15 9510                 | Notebook    | [5f594735cc](https://linux-hardware.org/?probe=5f594735cc) | Dec 28, 2021 |
| Lenovo     | ThinkPad L512 44444WG       | Notebook    | [113b39ddbc](https://linux-hardware.org/?probe=113b39ddbc) | Dec 25, 2021 |
| Acer       | Aspire E1-571               | Notebook    | [8b94542162](https://linux-hardware.org/?probe=8b94542162) | Dec 22, 2021 |
| Acer       | Aspire E1-571               | Notebook    | [842eae5b1d](https://linux-hardware.org/?probe=842eae5b1d) | Dec 22, 2021 |
| ASUSTek    | P8Z77-V LX                  | Desktop     | [6f6aeab7c1](https://linux-hardware.org/?probe=6f6aeab7c1) | Dec 20, 2021 |
| Dell       | Inspiron N4030              | Notebook    | [f5b5166d80](https://linux-hardware.org/?probe=f5b5166d80) | Dec 20, 2021 |
| ASUSTek    | PRIME A320M-E               | Desktop     | [c008e360e7](https://linux-hardware.org/?probe=c008e360e7) | Dec 19, 2021 |
| ASUSTek    | P9X79 PRO                   | Desktop     | [ca4a106ccf](https://linux-hardware.org/?probe=ca4a106ccf) | Dec 18, 2021 |
| ASUSTek    | P8Z77-V LX                  | Desktop     | [1ff9d84c5f](https://linux-hardware.org/?probe=1ff9d84c5f) | Dec 17, 2021 |
| Acer       | Aspire E1-571               | Notebook    | [27923678bd](https://linux-hardware.org/?probe=27923678bd) | Dec 16, 2021 |
| ASUSTek    | P8Z77-V LX                  | Desktop     | [a5ddb2410e](https://linux-hardware.org/?probe=a5ddb2410e) | Dec 16, 2021 |
| ASUSTek    | P8Z77-V LX                  | Desktop     | [e744dbe03d](https://linux-hardware.org/?probe=e744dbe03d) | Dec 15, 2021 |
| Lenovo     | ThinkPad T14 Gen 1 20UES... | Notebook    | [ecc22ad350](https://linux-hardware.org/?probe=ecc22ad350) | Dec 12, 2021 |
| Lenovo     | G500 20236                  | Notebook    | [dab30215a2](https://linux-hardware.org/?probe=dab30215a2) | Dec 05, 2021 |
| ASRock     | Z68 Extreme4 Gen3           | Desktop     | [00a3ad4abc](https://linux-hardware.org/?probe=00a3ad4abc) | Dec 02, 2021 |
| ASRock     | Z68 Extreme4 Gen3           | Desktop     | [e75c56906a](https://linux-hardware.org/?probe=e75c56906a) | Dec 01, 2021 |
| HUAWEI     | KLVL-WXX9                   | Notebook    | [34898be259](https://linux-hardware.org/?probe=34898be259) | Nov 28, 2021 |
| Lenovo     | ThinkPad T490s 20NYS1XK0... | Notebook    | [aef7318ff6](https://linux-hardware.org/?probe=aef7318ff6) | Nov 27, 2021 |
| Acer       | Aspire E1-772G              | Notebook    | [d49a3f3160](https://linux-hardware.org/?probe=d49a3f3160) | Nov 26, 2021 |
| ASUSTek    | CROSSHAIR VI HERO           | Desktop     | [a2761e06a4](https://linux-hardware.org/?probe=a2761e06a4) | Nov 24, 2021 |
| ASUSTek    | CROSSHAIR VI HERO           | Desktop     | [5bfec76970](https://linux-hardware.org/?probe=5bfec76970) | Nov 24, 2021 |
| Lenovo     | G50-45 80E3                 | Notebook    | [43f110e082](https://linux-hardware.org/?probe=43f110e082) | Nov 20, 2021 |
| Dell       | 03015M A09                  | Server      | [c685a0033b](https://linux-hardware.org/?probe=c685a0033b) | Nov 17, 2021 |
| MSI        | H510I PRO WIFI              | Desktop     | [d50547de1f](https://linux-hardware.org/?probe=d50547de1f) | Nov 15, 2021 |
| ASRock     | N68C-GS4 FX                 | Desktop     | [c863f2ca43](https://linux-hardware.org/?probe=c863f2ca43) | Nov 14, 2021 |
| Fujitsu    | D3220-A1 S26361-D3220-A1    | Desktop     | [7d1fd58f75](https://linux-hardware.org/?probe=7d1fd58f75) | Nov 14, 2021 |
| HP         | 844C                        | Desktop     | [2d709598d7](https://linux-hardware.org/?probe=2d709598d7) | Nov 12, 2021 |
| ASUSTek    | M4A78T-E                    | Desktop     | [10991ab539](https://linux-hardware.org/?probe=10991ab539) | Nov 10, 2021 |
| Acer       | Aspire E1-772G              | Notebook    | [ec97cd08d4](https://linux-hardware.org/?probe=ec97cd08d4) | Nov 09, 2021 |
| Acer       | Aspire E1-772G              | Notebook    | [be0c106296](https://linux-hardware.org/?probe=be0c106296) | Nov 09, 2021 |
| Lenovo     | IdeaPad 330-15IKB 81DC      | Notebook    | [9a632ea5d1](https://linux-hardware.org/?probe=9a632ea5d1) | Nov 08, 2021 |
| Acer       | Aspire 5820TG               | Notebook    | [d8ae1a4109](https://linux-hardware.org/?probe=d8ae1a4109) | Nov 03, 2021 |
| Acer       | Aspire 5820TG               | Notebook    | [c79617751e](https://linux-hardware.org/?probe=c79617751e) | Nov 03, 2021 |
| Dell       | 0M859N A00                  | Desktop     | [aadca45789](https://linux-hardware.org/?probe=aadca45789) | Nov 01, 2021 |
| Acer       | Aspire E1-772G              | Notebook    | [2ffccc532e](https://linux-hardware.org/?probe=2ffccc532e) | Oct 24, 2021 |
| Acer       | Nitro AN515-54              | Notebook    | [b6be115eec](https://linux-hardware.org/?probe=b6be115eec) | Oct 23, 2021 |
| Acer       | Aspire 5560                 | Notebook    | [39fd26f895](https://linux-hardware.org/?probe=39fd26f895) | Oct 22, 2021 |
| TUXEDO     | Aura 15 Gen1                | Notebook    | [627c62ae00](https://linux-hardware.org/?probe=627c62ae00) | Oct 21, 2021 |
| Dell       | 0Y2YM6 A00                  | Desktop     | [d9a12dc22c](https://linux-hardware.org/?probe=d9a12dc22c) | Oct 19, 2021 |
| Dell       | 0Y2YM6 A00                  | Desktop     | [34a55551e2](https://linux-hardware.org/?probe=34a55551e2) | Oct 19, 2021 |
| Medion     | E6436 MD61150               | Notebook    | [1edd4700fd](https://linux-hardware.org/?probe=1edd4700fd) | Oct 17, 2021 |
| Medion     | E6436 MD61150               | Notebook    | [2eaa34b93e](https://linux-hardware.org/?probe=2eaa34b93e) | Oct 17, 2021 |
| HP         | Laptop 15s-eq0xxx           | Notebook    | [fc4da04b79](https://linux-hardware.org/?probe=fc4da04b79) | Oct 16, 2021 |
| HP         | Laptop 17-ca1xxx            | Notebook    | [ae1811a242](https://linux-hardware.org/?probe=ae1811a242) | Oct 13, 2021 |
| Lenovo     | ThinkPad T490s 20NYS1XK0... | Notebook    | [d3700d8667](https://linux-hardware.org/?probe=d3700d8667) | Oct 13, 2021 |
| Lenovo     | ThinkPad L15 Gen 1 20U4S... | Notebook    | [3bb6121afa](https://linux-hardware.org/?probe=3bb6121afa) | Oct 13, 2021 |
| Lenovo     | ThinkPad X1 Carbon Gen 9... | Notebook    | [f3c6229102](https://linux-hardware.org/?probe=f3c6229102) | Oct 06, 2021 |
| Lenovo     | 364A SDK0J40700 WIN 3258... | Desktop     | [ce4776505f](https://linux-hardware.org/?probe=ce4776505f) | Oct 03, 2021 |
| MSI        | B450M MORTAR MAX            | Desktop     | [556c37ba9b](https://linux-hardware.org/?probe=556c37ba9b) | Oct 03, 2021 |
| MSI        | B450M PRO-VDH MAX           | Desktop     | [ad69186227](https://linux-hardware.org/?probe=ad69186227) | Oct 02, 2021 |
| ASRock     | Z68 Extreme4 Gen3           | Desktop     | [3cec37b610](https://linux-hardware.org/?probe=3cec37b610) | Oct 02, 2021 |
| MSI        | B450M PRO-VDH MAX           | Desktop     | [540dca7da7](https://linux-hardware.org/?probe=540dca7da7) | Oct 02, 2021 |
| Lenovo     | ThinkPad T550 20CJS1VD01    | Notebook    | [390b9a8a74](https://linux-hardware.org/?probe=390b9a8a74) | Oct 01, 2021 |
| MSI        | GP63 Leopard 8RD            | Notebook    | [21189bb3e0](https://linux-hardware.org/?probe=21189bb3e0) | Oct 01, 2021 |
| ASUSTek    | M4A78T-E                    | Desktop     | [01ec64f498](https://linux-hardware.org/?probe=01ec64f498) | Sep 24, 2021 |
| Lenovo     | 364A SDK0J40700 WIN 3258... | Desktop     | [58f9ca6247](https://linux-hardware.org/?probe=58f9ca6247) | Sep 22, 2021 |
| Lenovo     | 364A SDK0J40700 WIN 3258... | Desktop     | [db9ccd461b](https://linux-hardware.org/?probe=db9ccd461b) | Sep 22, 2021 |
| Dell       | Precision M6700             | Notebook    | [0d8cf3bf1c](https://linux-hardware.org/?probe=0d8cf3bf1c) | Sep 21, 2021 |
| VS Company | G31T-M                      | Desktop     | [ed8bb8c0d1](https://linux-hardware.org/?probe=ed8bb8c0d1) | Sep 21, 2021 |
| ASUSTek    | AM1M-A/BR                   | Desktop     | [c586c22b15](https://linux-hardware.org/?probe=c586c22b15) | Sep 20, 2021 |
| Alienware  | 0PGRP5 A02                  | Desktop     | [65615a3aaa](https://linux-hardware.org/?probe=65615a3aaa) | Sep 16, 2021 |
| Alienware  | 0PGRP5 A02                  | Desktop     | [158a015f26](https://linux-hardware.org/?probe=158a015f26) | Sep 15, 2021 |
| MSI        | X370 GAMING PRO             | Desktop     | [629a45e23d](https://linux-hardware.org/?probe=629a45e23d) | Sep 12, 2021 |
| HP         | 8056                        | Desktop     | [3cab8505c4](https://linux-hardware.org/?probe=3cab8505c4) | Sep 06, 2021 |
| Intel      | DG41WV AAE90316-104         | Desktop     | [27c162218f](https://linux-hardware.org/?probe=27c162218f) | Sep 05, 2021 |
| Gigabyte   | B550 AORUS PRO AC           | Desktop     | [be3b65a81d](https://linux-hardware.org/?probe=be3b65a81d) | Aug 29, 2021 |
| Lenovo     | ThinkPad X1 Carbon 4th 2... | Notebook    | [44d0412dd3](https://linux-hardware.org/?probe=44d0412dd3) | Aug 27, 2021 |
| Samsung    | 600B4B/600B5B               | Notebook    | [200275bbd6](https://linux-hardware.org/?probe=200275bbd6) | Aug 27, 2021 |
| ASRock     | B450M Pro4                  | Desktop     | [a13b05f65f](https://linux-hardware.org/?probe=a13b05f65f) | Aug 27, 2021 |
| Dell       | Precision M6700             | Notebook    | [191db00b83](https://linux-hardware.org/?probe=191db00b83) | Aug 26, 2021 |
| Lenovo     | V330-15IKB 81AX             | Notebook    | [4b5a1af4dd](https://linux-hardware.org/?probe=4b5a1af4dd) | Aug 26, 2021 |
| Lenovo     | G500 20236                  | Notebook    | [73a5085a79](https://linux-hardware.org/?probe=73a5085a79) | Aug 24, 2021 |
| Dell       | Latitude 5480               | Notebook    | [a2110d9601](https://linux-hardware.org/?probe=a2110d9601) | Aug 24, 2021 |
| Dell       | Latitude 5480               | Notebook    | [64e1f3e16c](https://linux-hardware.org/?probe=64e1f3e16c) | Aug 19, 2021 |
| Lenovo     | ThinkPad T61 8895W9U        | Notebook    | [424c5f3e75](https://linux-hardware.org/?probe=424c5f3e75) | Aug 19, 2021 |
| Dell       | Inspiron 3521               | Notebook    | [c68ce33d52](https://linux-hardware.org/?probe=c68ce33d52) | Aug 11, 2021 |
| Dell       | Inspiron 3521               | Notebook    | [9a422a10d3](https://linux-hardware.org/?probe=9a422a10d3) | Aug 11, 2021 |
| Dell       | Inspiron 7460               | Notebook    | [f954aa3826](https://linux-hardware.org/?probe=f954aa3826) | Aug 10, 2021 |
| Samsung    | 600B4B/600B5B               | Notebook    | [0a650b495e](https://linux-hardware.org/?probe=0a650b495e) | Aug 09, 2021 |
| Lenovo     | ThinkPad T460 20FMS75800    | Notebook    | [1a1c3f469d](https://linux-hardware.org/?probe=1a1c3f469d) | Aug 07, 2021 |
| Lenovo     | ThinkPad X1 Carbon 4th 2... | Notebook    | [5953bc46ad](https://linux-hardware.org/?probe=5953bc46ad) | Aug 06, 2021 |
| Lenovo     | ThinkPad X1 Carbon 4th 2... | Notebook    | [fafaeed466](https://linux-hardware.org/?probe=fafaeed466) | Aug 06, 2021 |
| ASUSTek    | PRIME H310M-A               | Desktop     | [a22aa3c48c](https://linux-hardware.org/?probe=a22aa3c48c) | Aug 01, 2021 |
| MSI        | B85M-E45                    | Desktop     | [0e20d4cea9](https://linux-hardware.org/?probe=0e20d4cea9) | Jul 30, 2021 |
| Gigabyte   | B250M-DS3H-CF               | Desktop     | [acbcbe74d7](https://linux-hardware.org/?probe=acbcbe74d7) | Jul 22, 2021 |
| HP         | Stream Notebook PC 11       | Notebook    | [a612aa5d15](https://linux-hardware.org/?probe=a612aa5d15) | Jul 20, 2021 |
| HP         | 8433 11                     | Desktop     | [b079ccb608](https://linux-hardware.org/?probe=b079ccb608) | Jul 15, 2021 |
| MSI        | D2415 S26361-D2415-A21      | Desktop     | [b49400f636](https://linux-hardware.org/?probe=b49400f636) | Jul 11, 2021 |
| Lenovo     | ThinkPad T450s 20BWA06J0... | Notebook    | [e4cd39ef75](https://linux-hardware.org/?probe=e4cd39ef75) | Jul 09, 2021 |
| Lenovo     | ThinkPad T450s 20BWA06J0... | Notebook    | [5565f4e4fe](https://linux-hardware.org/?probe=5565f4e4fe) | Jul 09, 2021 |
| Fujitsu    | LIFEBOOK E754               | Notebook    | [e7923c27f1](https://linux-hardware.org/?probe=e7923c27f1) | Jul 08, 2021 |
| MSI        | B350 TOMAHAWK               | Desktop     | [27a6ac997b](https://linux-hardware.org/?probe=27a6ac997b) | Jul 03, 2021 |
| ASRock     | X570M Pro4                  | Desktop     | [a00aea4331](https://linux-hardware.org/?probe=a00aea4331) | Jul 03, 2021 |
| HP         | 0A68h                       | Desktop     | [36cfa6a366](https://linux-hardware.org/?probe=36cfa6a366) | Jun 27, 2021 |
| ASUSTek    | TUF B450-PRO GAMING         | Desktop     | [dfc2f82575](https://linux-hardware.org/?probe=dfc2f82575) | Jun 26, 2021 |
| ASUSTek    | G771JW                      | Notebook    | [8e6c4ddee8](https://linux-hardware.org/?probe=8e6c4ddee8) | Jun 24, 2021 |
| ASRock     | X570 Steel Legend           | Desktop     | [b4a11b3e4e](https://linux-hardware.org/?probe=b4a11b3e4e) | Jun 17, 2021 |
| MSI        | MEG X570 GODLIKE            | Desktop     | [11b7f0e8ae](https://linux-hardware.org/?probe=11b7f0e8ae) | Jun 17, 2021 |
| HP         | ZBook 17 G2                 | Notebook    | [3342d4d378](https://linux-hardware.org/?probe=3342d4d378) | Jun 17, 2021 |
| HP         | OMEN by HP Laptop 15-dc1... | Notebook    | [0c01b21401](https://linux-hardware.org/?probe=0c01b21401) | Jun 15, 2021 |
| Sony       | VPCSB15GB                   | Notebook    | [43a9d38ca0](https://linux-hardware.org/?probe=43a9d38ca0) | Jun 03, 2021 |
| HP         | 2AA2                        | Desktop     | [65e7cd2d3e](https://linux-hardware.org/?probe=65e7cd2d3e) | Jun 02, 2021 |
| Sony       | VGN-Z570AN                  | Notebook    | [13d58b8d90](https://linux-hardware.org/?probe=13d58b8d90) | May 21, 2021 |
| Sony       | VGN-Z570AN                  | Notebook    | [e6c7882e05](https://linux-hardware.org/?probe=e6c7882e05) | May 21, 2021 |
| MSI        | GS60 6QE                    | Notebook    | [93c6fd8911](https://linux-hardware.org/?probe=93c6fd8911) | May 18, 2021 |
| MSI        | GS60 6QE                    | Notebook    | [41fe777475](https://linux-hardware.org/?probe=41fe777475) | May 18, 2021 |
| ASUSTek    | VivoBook 12_ASUS Laptop ... | Notebook    | [184bedf2fd](https://linux-hardware.org/?probe=184bedf2fd) | May 01, 2021 |
| HP         | Pavilion dx6500             | Notebook    | [091cc2c616](https://linux-hardware.org/?probe=091cc2c616) | Apr 13, 2021 |
| HP         | Pavilion dx6500             | Notebook    | [6ad0d5c87f](https://linux-hardware.org/?probe=6ad0d5c87f) | Apr 13, 2021 |
| Dell       | Inspiron 15 7000 Gaming     | Notebook    | [97a7246099](https://linux-hardware.org/?probe=97a7246099) | Mar 01, 2021 |
| Dell       | Inspiron 15 7000 Gaming     | Notebook    | [b1e186207c](https://linux-hardware.org/?probe=b1e186207c) | Feb 28, 2021 |
| ASUSTek    | P8H61-M LE/USB3             | Desktop     | [fca0fd3336](https://linux-hardware.org/?probe=fca0fd3336) | Jan 03, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                             | Computers | Percent |
|-------------------------------------|-----------|---------|
| 5.3.18-59.27-default                | 13        | 15.66%  |
| 5.3.18-59.19-default                | 13        | 15.66%  |
| 5.3.18-59.37-default                | 8         | 9.64%   |
| 5.3.18-57-default                   | 8         | 9.64%   |
| 5.3.18-59.5-default                 | 6         | 7.23%   |
| 5.3.18-59.24-default                | 6         | 7.23%   |
| 5.3.18-59.16-default                | 6         | 7.23%   |
| 5.3.18-59.10-default                | 5         | 6.02%   |
| 5.3.18-59.34-default                | 4         | 4.82%   |
| 5.3.18-59.19-preempt                | 2         | 2.41%   |
| 5.3.18-59.13-default                | 2         | 2.41%   |
| 5.3.18-lp152.57-default             | 1         | 1.2%    |
| 5.3.18-59.34-preempt                | 1         | 1.2%    |
| 5.3.18-59.27-preempt                | 1         | 1.2%    |
| 5.3.18-59.24-preempt                | 1         | 1.2%    |
| 5.3.18-57-preempt                   | 1         | 1.2%    |
| 5.3.18-56-default                   | 1         | 1.2%    |
| 5.3.18-52-default                   | 1         | 1.2%    |
| 5.3.18-46-default                   | 1         | 1.2%    |
| 5.16.0-rc2-lp153.2.g696d453-default | 1         | 1.2%    |
| 5.15.11-lp153.3.g730a488-default    | 1         | 1.2%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.3.18  | 77        | 97.47%  |
| 5.16.0  | 1         | 1.27%   |
| 5.15.11 | 1         | 1.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.3     | 77        | 97.47%  |
| 5.16    | 1         | 1.27%   |
| 5.15    | 1         | 1.27%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 79        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| KDE5       | 31        | 37.8%   |
| KDE        | 17        | 20.73%  |
| GNOME      | 11        | 13.41%  |
| Unknown    | 11        | 13.41%  |
| XFCE       | 8         | 9.76%   |
| X-Cinnamon | 3         | 3.66%   |
| MATE       | 1         | 1.22%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 64        | 80%     |
| Wayland | 10        | 12.5%   |
| Tty     | 6         | 7.5%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 44        | 55.7%   |
| LightDM | 16        | 20.25%  |
| SDDM    | 14        | 17.72%  |
| XDM     | 4         | 5.06%   |
| GDM     | 1         | 1.27%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 28        | 35.44%  |
| de_DE   | 15        | 18.99%  |
| POSIX   | 8         | 10.13%  |
| pt_BR   | 4         | 5.06%   |
| fr_FR   | 3         | 3.8%    |
| es_ES   | 3         | 3.8%    |
| ru_RU   | 2         | 2.53%   |
| en_GB   | 2         | 2.53%   |
| Unknown | 2         | 2.53%   |
| zh_CN   | 1         | 1.27%   |
| tr_TR   | 1         | 1.27%   |
| sv_SE   | 1         | 1.27%   |
| pt_PT   | 1         | 1.27%   |
| pl_PL   | 1         | 1.27%   |
| nl_BE   | 1         | 1.27%   |
| hu_HU   | 1         | 1.27%   |
| hr_HR   | 1         | 1.27%   |
| es_MX   | 1         | 1.27%   |
| en_AU   | 1         | 1.27%   |
| cs_CZ   | 1         | 1.27%   |
| ca_AD   | 1         | 1.27%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 46        | 58.23%  |
| EFI  | 33        | 41.77%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 55        | 69.62%  |
| Ext4    | 20        | 25.32%  |
| Xfs     | 3         | 3.8%    |
| Overlay | 1         | 1.27%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 38        | 47.5%   |
| Unknown | 38        | 47.5%   |
| MBR     | 4         | 5%      |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 71        | 88.75%  |
| Yes       | 9         | 11.25%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 55        | 69.62%  |
| Yes       | 24        | 30.38%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 13        | 16.46%  |
| ASUSTek Computer    | 12        | 15.19%  |
| Hewlett-Packard     | 11        | 13.92%  |
| MSI                 | 10        | 12.66%  |
| Dell                | 10        | 12.66%  |
| ASRock              | 5         | 6.33%   |
| Acer                | 5         | 6.33%   |
| Sony                | 2         | 2.53%   |
| Gigabyte Technology | 2         | 2.53%   |
| Fujitsu             | 2         | 2.53%   |
| VS Company          | 1         | 1.27%   |
| TUXEDO              | 1         | 1.27%   |
| Samsung Electronics | 1         | 1.27%   |
| Medion              | 1         | 1.27%   |
| Intel               | 1         | 1.27%   |
| HUAWEI              | 1         | 1.27%   |
| Alienware           | 1         | 1.27%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                         | Computers | Percent |
|----------------------------------------------|-----------|---------|
| VS Company G31T-M                            | 1         | 1.27%   |
| TUXEDO Aura 15 Gen1                          | 1         | 1.27%   |
| Sony VPCSB15GB                               | 1         | 1.27%   |
| Sony VGN-Z570AN                              | 1         | 1.27%   |
| Samsung 600B4B/600B5B                        | 1         | 1.27%   |
| MSI MS-7D16                                  | 1         | 1.27%   |
| MSI MS-7C34                                  | 1         | 1.27%   |
| MSI MS-7B89                                  | 1         | 1.27%   |
| MSI MS-7A38                                  | 1         | 1.27%   |
| MSI MS-7A34                                  | 1         | 1.27%   |
| MSI MS-7A33                                  | 1         | 1.27%   |
| MSI MS-7817                                  | 1         | 1.27%   |
| MSI GS60 6QE                                 | 1         | 1.27%   |
| MSI GP63 Leopard 8RD                         | 1         | 1.27%   |
| MSI ESPRIMO P1510                            | 1         | 1.27%   |
| Medion E6436 MD61150                         | 1         | 1.27%   |
| Lenovo V330-15IKB 81AX                       | 1         | 1.27%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XW00A7TH   | 1         | 1.27%   |
| Lenovo ThinkPad X1 Carbon 4th 20FB002UMC     | 1         | 1.27%   |
| Lenovo ThinkPad T61 8895W9U                  | 1         | 1.27%   |
| Lenovo ThinkPad T490s 20NYS1XK00             | 1         | 1.27%   |
| Lenovo ThinkPad T460 20FMS75800              | 1         | 1.27%   |
| Lenovo ThinkPad T450s 20BWA06J00             | 1         | 1.27%   |
| Lenovo ThinkPad T14 Gen 1 20UES47F00         | 1         | 1.27%   |
| Lenovo ThinkPad L15 Gen 1 20U4S88000         | 1         | 1.27%   |
| Lenovo IdeaPad 330-15IKB 81DC                | 1         | 1.27%   |
| Lenovo IdeaCentre Y710 Cube-15ISH 90FL004WGE | 1         | 1.27%   |
| Lenovo G500 20236                            | 1         | 1.27%   |
| Lenovo G50-45 80E3                           | 1         | 1.27%   |
| Intel DG41WV AAE90316-104                    | 1         | 1.27%   |
| HUAWEI KLVL-WXX9                             | 1         | 1.27%   |
| HP ZBook 17 G2                               | 1         | 1.27%   |
| HP xw4400 Workstation                        | 1         | 1.27%   |
| HP Stream Notebook PC 11                     | 1         | 1.27%   |
| HP Pavilion Gaming Desktop 790-00xx          | 1         | 1.27%   |
| HP Pavilion Gaming Desktop 690-00xx          | 1         | 1.27%   |
| HP Pavilion dx6500                           | 1         | 1.27%   |
| HP OMEN by HP Laptop 15-dc1xxx               | 1         | 1.27%   |
| HP Laptop 17-ca1xxx                          | 1         | 1.27%   |
| HP Laptop 15s-eq0xxx                         | 1         | 1.27%   |
| HP EliteDesk 800 G2 DM 65W                   | 1         | 1.27%   |
| HP 200-5120br                                | 1         | 1.27%   |
| Gigabyte B550 AORUS PRO AC                   | 1         | 1.27%   |
| Gigabyte B250M-DS3H                          | 1         | 1.27%   |
| Fujitsu LIFEBOOK E754                        | 1         | 1.27%   |
| Fujitsu ESPRIMO P520                         | 1         | 1.27%   |
| Dell XPS 15 9510                             | 1         | 1.27%   |
| Dell Vostro 3268                             | 1         | 1.27%   |
| Dell Precision M6700                         | 1         | 1.27%   |
| Dell PowerEdge T420                          | 1         | 1.27%   |
| Dell Latitude 5480                           | 1         | 1.27%   |
| Dell Inspiron N4030                          | 1         | 1.27%   |
| Dell Inspiron 7460                           | 1         | 1.27%   |
| Dell Inspiron 530                            | 1         | 1.27%   |
| Dell Inspiron 3521                           | 1         | 1.27%   |
| Dell Inspiron 15 7000 Gaming                 | 1         | 1.27%   |
| ASUS VivoBook 12_ASUS Laptop E203MAS_E203MA  | 1         | 1.27%   |
| ASUS TUF B450-PRO GAMING                     | 1         | 1.27%   |
| ASUS ROG CROSSHAIR VIII HERO                 | 1         | 1.27%   |
| ASUS PRIME H310M-A                           | 1         | 1.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 8         | 10.13%  |
| Dell Inspiron       | 5         | 6.33%   |
| Acer Aspire         | 4         | 5.06%   |
| HP Pavilion         | 3         | 3.8%    |
| HP Laptop           | 2         | 2.53%   |
| ASUS PRIME          | 2         | 2.53%   |
| VS Company G31T-M   | 1         | 1.27%   |
| TUXEDO Aura         | 1         | 1.27%   |
| Sony VPCSB15GB      | 1         | 1.27%   |
| Sony VGN-Z570AN     | 1         | 1.27%   |
| Samsung 600B4B      | 1         | 1.27%   |
| MSI MS-7D16         | 1         | 1.27%   |
| MSI MS-7C34         | 1         | 1.27%   |
| MSI MS-7B89         | 1         | 1.27%   |
| MSI MS-7A38         | 1         | 1.27%   |
| MSI MS-7A34         | 1         | 1.27%   |
| MSI MS-7A33         | 1         | 1.27%   |
| MSI MS-7817         | 1         | 1.27%   |
| MSI GS60            | 1         | 1.27%   |
| MSI GP63            | 1         | 1.27%   |
| MSI ESPRIMO         | 1         | 1.27%   |
| Medion E6436        | 1         | 1.27%   |
| Lenovo V330-15IKB   | 1         | 1.27%   |
| Lenovo IdeaPad      | 1         | 1.27%   |
| Lenovo IdeaCentre   | 1         | 1.27%   |
| Lenovo G500         | 1         | 1.27%   |
| Lenovo G50-45       | 1         | 1.27%   |
| Intel DG41WV        | 1         | 1.27%   |
| HUAWEI KLVL-WXX9    | 1         | 1.27%   |
| HP ZBook            | 1         | 1.27%   |
| HP xw4400           | 1         | 1.27%   |
| HP Stream           | 1         | 1.27%   |
| HP OMEN             | 1         | 1.27%   |
| HP EliteDesk        | 1         | 1.27%   |
| HP 200-5120br       | 1         | 1.27%   |
| Gigabyte B550       | 1         | 1.27%   |
| Gigabyte B250M-DS3H | 1         | 1.27%   |
| Fujitsu LIFEBOOK    | 1         | 1.27%   |
| Fujitsu ESPRIMO     | 1         | 1.27%   |
| Dell XPS            | 1         | 1.27%   |
| Dell Vostro         | 1         | 1.27%   |
| Dell Precision      | 1         | 1.27%   |
| Dell PowerEdge      | 1         | 1.27%   |
| Dell Latitude       | 1         | 1.27%   |
| ASUS VivoBook       | 1         | 1.27%   |
| ASUS TUF            | 1         | 1.27%   |
| ASUS ROG            | 1         | 1.27%   |
| ASUS P9X79          | 1         | 1.27%   |
| ASUS P8Z77-V        | 1         | 1.27%   |
| ASUS P8H61-M        | 1         | 1.27%   |
| ASUS M4A78T-E       | 1         | 1.27%   |
| ASUS G771JW         | 1         | 1.27%   |
| ASUS CROSSHAIR      | 1         | 1.27%   |
| ASUS All            | 1         | 1.27%   |
| ASRock Z68          | 1         | 1.27%   |
| ASRock X570M        | 1         | 1.27%   |
| ASRock X570         | 1         | 1.27%   |
| ASRock N68C-GS4     | 1         | 1.27%   |
| ASRock B450M        | 1         | 1.27%   |
| Alienware X51       | 1         | 1.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 19        | 24.05%  |
| 2020 | 10        | 12.66%  |
| 2018 | 10        | 12.66%  |
| 2019 | 8         | 10.13%  |
| 2010 | 7         | 8.86%   |
| 2016 | 5         | 6.33%   |
| 2014 | 4         | 5.06%   |
| 2011 | 4         | 5.06%   |
| 2013 | 3         | 3.8%    |
| 2017 | 2         | 2.53%   |
| 2015 | 2         | 2.53%   |
| 2009 | 2         | 2.53%   |
| 2007 | 2         | 2.53%   |
| 2012 | 1         | 1.27%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Notebook | 41        | 51.9%   |
| Desktop  | 37        | 46.84%  |
| Server   | 1         | 1.27%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 72        | 91.14%  |
| Enabled  | 7         | 8.86%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 79        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 21        | 26.58%  |
| 8.01-16.0   | 15        | 18.99%  |
| 4.01-8.0    | 13        | 16.46%  |
| 3.01-4.0    | 11        | 13.92%  |
| 64.01-256.0 | 8         | 10.13%  |
| 32.01-64.0  | 7         | 8.86%   |
| 1.01-2.0    | 2         | 2.53%   |
| 24.01-32.0  | 1         | 1.27%   |
| 2.01-3.0    | 1         | 1.27%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 26        | 32.1%   |
| 2.01-3.0  | 21        | 25.93%  |
| 4.01-8.0  | 17        | 20.99%  |
| 3.01-4.0  | 11        | 13.58%  |
| 8.01-16.0 | 3         | 3.7%    |
| 0.51-1.0  | 3         | 3.7%    |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 36        | 45.57%  |
| 2      | 26        | 32.91%  |
| 3      | 9         | 11.39%  |
| 4      | 4         | 5.06%   |
| 6      | 2         | 2.53%   |
| 9      | 1         | 1.27%   |
| 7      | 1         | 1.27%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 42        | 53.16%  |
| Yes       | 37        | 46.84%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 73        | 92.41%  |
| No        | 6         | 7.59%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 65        | 82.28%  |
| No        | 14        | 17.72%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 52        | 65%     |
| No        | 28        | 35%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Germany     | 16        | 20.25%  |
| USA         | 10        | 12.66%  |
| Brazil      | 9         | 11.39%  |
| France      | 4         | 5.06%   |
| Spain       | 3         | 3.8%    |
| Russia      | 3         | 3.8%    |
| Mexico      | 3         | 3.8%    |
| India       | 3         | 3.8%    |
| Australia   | 3         | 3.8%    |
| Nicaragua   | 2         | 2.53%   |
| Japan       | 2         | 2.53%   |
| Hungary     | 2         | 2.53%   |
| Greece      | 2         | 2.53%   |
| Czechia     | 2         | 2.53%   |
| Turkey      | 1         | 1.27%   |
| Thailand    | 1         | 1.27%   |
| Sweden      | 1         | 1.27%   |
| Sudan       | 1         | 1.27%   |
| Slovakia    | 1         | 1.27%   |
| Romania     | 1         | 1.27%   |
| Portugal    | 1         | 1.27%   |
| Poland      | 1         | 1.27%   |
| Netherlands | 1         | 1.27%   |
| Luxembourg  | 1         | 1.27%   |
| Croatia     | 1         | 1.27%   |
| China       | 1         | 1.27%   |
| Canada      | 1         | 1.27%   |
| Belgium     | 1         | 1.27%   |
| Andorra     | 1         | 1.27%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| SÃ£o Paulo            | 3         | 3.75%   |
| Tokyo                 | 2         | 2.5%    |
| Prague                | 2         | 2.5%    |
| Managua               | 2         | 2.5%    |
| Chapec??              | 2         | 2.5%    |
| Zagreb                | 1         | 1.25%   |
| Vijayawada            | 1         | 1.25%   |
| Vaennaesby            | 1         | 1.25%   |
| TrÃªs Lagoas          | 1         | 1.25%   |
| The Hague             | 1         | 1.25%   |
| Sydney                | 1         | 1.25%   |
| Stupava               | 1         | 1.25%   |
| Stabroek              | 1         | 1.25%   |
| Sehnde                | 1         | 1.25%   |
| S??o Paulo            | 1         | 1.25%   |
| Sartrouville          | 1         | 1.25%   |
| San Luis Potos?­ City | 1         | 1.25%   |
| Saint Albans          | 1         | 1.25%   |
| Rockville             | 1         | 1.25%   |
| Recife                | 1         | 1.25%   |
| Pringy                | 1         | 1.25%   |
| Petrozavodsk          | 1         | 1.25%   |
| Palanpur              | 1         | 1.25%   |
| Oregon                | 1         | 1.25%   |
| Nuremberg             | 1         | 1.25%   |
| Nordenham             | 1         | 1.25%   |
| Munich                | 1         | 1.25%   |
| Moscow                | 1         | 1.25%   |
| Monterrey             | 1         | 1.25%   |
| Moelan-sur-Mer        | 1         | 1.25%   |
| Miami                 | 1         | 1.25%   |
| Melbourne             | 1         | 1.25%   |
| McDonough             | 1         | 1.25%   |
| Mansfield             | 1         | 1.25%   |
| Madrid                | 1         | 1.25%   |
| Luxembourg            | 1         | 1.25%   |
| Lomonosov             | 1         | 1.25%   |
| Leiria                | 1         | 1.25%   |
| Le??n                 | 1         | 1.25%   |
| Koleczkowo            | 1         | 1.25%   |
| Khartoum              | 1         | 1.25%   |
| Kehl                  | 1         | 1.25%   |
| Kathu                 | 1         | 1.25%   |
| Isernhagen            | 1         | 1.25%   |
| Howick                | 1         | 1.25%   |
| Heraklion             | 1         | 1.25%   |
| Heinsberg             | 1         | 1.25%   |
| Hamelin               | 1         | 1.25%   |
| Halle                 | 1         | 1.25%   |
| Guangzhou             | 1         | 1.25%   |
| Gevelsberg            | 1         | 1.25%   |
| Gelnhausen            | 1         | 1.25%   |
| G?¶d?¶ll?‘            | 1         | 1.25%   |
| Federal Way           | 1         | 1.25%   |
| Esztergom             | 1         | 1.25%   |
| East Longmeadow       | 1         | 1.25%   |
| Dunkirk               | 1         | 1.25%   |
| Dornhan               | 1         | 1.25%   |
| Dahme                 | 1         | 1.25%   |
| Concarneau            | 1         | 1.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 28        | 38     | 20.29%  |
| Seagate             | 23        | 35     | 16.67%  |
| Samsung Electronics | 21        | 30     | 15.22%  |
| Kingston            | 10        | 10     | 7.25%   |
| SanDisk             | 7         | 8      | 5.07%   |
| Toshiba             | 6         | 7      | 4.35%   |
| Hitachi             | 6         | 8      | 4.35%   |
| HGST                | 4         | 4      | 2.9%    |
| Crucial             | 4         | 4      | 2.9%    |
| A-DATA Technology   | 4         | 4      | 2.9%    |
| Unknown             | 3         | 3      | 2.17%   |
| Intel               | 3         | 3      | 2.17%   |
| SK Hynix            | 2         | 2      | 1.45%   |
| Silicon Motion      | 2         | 2      | 1.45%   |
| Phison              | 2         | 2      | 1.45%   |
| Micron Technology   | 2         | 2      | 1.45%   |
| Fujitsu             | 2         | 2      | 1.45%   |
| TO Exter            | 1         | 1      | 0.72%   |
| PLEXTOR             | 1         | 2      | 0.72%   |
| LITEON              | 1         | 1      | 0.72%   |
| Lite-On             | 1         | 1      | 0.72%   |
| JMicron             | 1         | 1      | 0.72%   |
| Intenso             | 1         | 1      | 0.72%   |
| Inateck             | 1         | 1      | 0.72%   |
| HGST HTS            | 1         | 1      | 0.72%   |
| Corsair             | 1         | 1      | 0.72%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB             | 3         | 2%      |
| Silicon Motion NVMe SSD Drive 512GB   | 2         | 1.33%   |
| Seagate ST3750528AS 752GB             | 2         | 1.33%   |
| Seagate ST2000DM008-2FR102 2TB        | 2         | 1.33%   |
| Seagate ST2000DM006-2DM164 2TB        | 2         | 1.33%   |
| Seagate ST1000LM035-1RK172 1TB        | 2         | 1.33%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 2         | 1.33%   |
| Samsung SSD 860 EVO 250GB             | 2         | 1.33%   |
| Samsung SSD 860 EVO 1TB               | 2         | 1.33%   |
| Samsung SSD 850 EVO 500GB             | 2         | 1.33%   |
| HGST HTS721010A9E630 1TB              | 2         | 1.33%   |
| Fujitsu MHW2120BH 120GB               | 2         | 1.33%   |
| WDC WDS500G1X0E-00AFY0 500GB          | 1         | 0.67%   |
| WDC WDS500G1B0B-00AS40 500GB SSD      | 1         | 0.67%   |
| WDC WDS480G2G0A-00JH30 480GB SSD      | 1         | 0.67%   |
| WDC WDS250G1B0C-00S6U0 250GB          | 1         | 0.67%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD      | 1         | 0.67%   |
| WDC WDS200T2B0A-00SM50 2TB SSD        | 1         | 0.67%   |
| WDC WDS100T3X0C-00SJG0 1TB            | 1         | 0.67%   |
| WDC WDS100T1X0E-00AFY0 1TB            | 1         | 0.67%   |
| WDC WD800BEVS-60RST0 80GB             | 1         | 0.67%   |
| WDC WD7500AALX-009BA0 752GB           | 1         | 0.67%   |
| WDC WD5000LPVX-00V0TT0 500GB          | 1         | 0.67%   |
| WDC WD5000LPLX-66ZNTT1 500GB          | 1         | 0.67%   |
| WDC WD5000AAVS-00ZTB0 500GB           | 1         | 0.67%   |
| WDC WD5000AAKX-07U6AA0 500GB          | 1         | 0.67%   |
| WDC WD50 00LPCX-00VHAT0 500GB         | 1         | 0.67%   |
| WDC WD3200AAKS-00B3A0 320GB           | 1         | 0.67%   |
| WDC WD2500BEVT-60ZCT1 250GB           | 1         | 0.67%   |
| WDC WD2500AAJS-00VTA0 250GB           | 1         | 0.67%   |
| WDC WD20EARX-00PASB0 2TB              | 1         | 0.67%   |
| WDC WD2005FBYZ-01YCBB2 2TB            | 1         | 0.67%   |
| WDC WD10SPZX-60Z10T0 1TB              | 1         | 0.67%   |
| WDC WD10SPZX-24Z10 1TB                | 1         | 0.67%   |
| WDC WD10SPZX-17Z10T0 1TB              | 1         | 0.67%   |
| WDC WD10EZEX-75WN4A0 1TB              | 1         | 0.67%   |
| WDC WD10EZEX-75M2NA0 1TB              | 1         | 0.67%   |
| WDC WD10EZEX-08WN4A0 1TB              | 1         | 0.67%   |
| WDC WD10EZEX-00KUWA0 1TB              | 1         | 0.67%   |
| WDC WD10EZEX-00BN5A0 1TB              | 1         | 0.67%   |
| WDC WD10EAVS-22D7B0 1TB               | 1         | 0.67%   |
| WDC WD10EACS-00D6B1 1TB               | 1         | 0.67%   |
| WDC WD1003FZEX-00K3CA0 1TB            | 1         | 0.67%   |
| WDC WD1001FALS-00E3A0 1TB             | 1         | 0.67%   |
| WDC PC SN730 SDBPNTY-512G-1006 512GB  | 1         | 0.67%   |
| Unknown USD00  256GB                  | 1         | 0.67%   |
| Unknown DA4064  64GB                  | 1         | 0.67%   |
| Unknown 128GB SATA FLASH DRIVE        | 1         | 0.67%   |
| Toshiba TR200 240GB SSD               | 1         | 0.67%   |
| Toshiba TL100 240GB SSD               | 1         | 0.67%   |
| Toshiba THNSNJ256G8NU 256GB SSD       | 1         | 0.67%   |
| Toshiba NVMe SSD Drive 256GB          | 1         | 0.67%   |
| Toshiba MQ01ABD075 752GB              | 1         | 0.67%   |
| Toshiba HDWD130 3TB                   | 1         | 0.67%   |
| TO Exter nal USB 3.0 250GB            | 1         | 0.67%   |
| SK Hynix HFS128G39TND-N210A 128GB SSD | 1         | 0.67%   |
| SK Hynix HBG4e  32GB                  | 1         | 0.67%   |
| Seagate ST9320325AS 320GB             | 1         | 0.67%   |
| Seagate ST500LT012-9WS142 500GB       | 1         | 0.67%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 1         | 0.67%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 23        | 34     | 37.1%   |
| WDC                 | 21        | 29     | 33.87%  |
| Hitachi             | 6         | 8      | 9.68%   |
| HGST                | 4         | 4      | 6.45%   |
| Toshiba             | 2         | 3      | 3.23%   |
| Samsung Electronics | 2         | 5      | 3.23%   |
| Fujitsu             | 2         | 2      | 3.23%   |
| TO Exter            | 1         | 1      | 1.61%   |
| Inateck             | 1         | 1      | 1.61%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 15     | 21.74%  |
| Kingston            | 9         | 9      | 19.57%  |
| SanDisk             | 7         | 8      | 15.22%  |
| WDC                 | 4         | 4      | 8.7%    |
| A-DATA Technology   | 4         | 4      | 8.7%    |
| Toshiba             | 3         | 3      | 6.52%   |
| Intel               | 2         | 2      | 4.35%   |
| Crucial             | 2         | 2      | 4.35%   |
| SK Hynix            | 1         | 1      | 2.17%   |
| PLEXTOR             | 1         | 2      | 2.17%   |
| LITEON              | 1         | 1      | 2.17%   |
| JMicron             | 1         | 1      | 2.17%   |
| Intenso             | 1         | 1      | 2.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 49        | 87     | 40.83%  |
| SSD     | 42        | 53     | 35%     |
| NVMe    | 25        | 29     | 20.83%  |
| MMC     | 3         | 3      | 2.5%    |
| Unknown | 1         | 2      | 0.83%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 67        | 135    | 67.68%  |
| NVMe | 25        | 29     | 25.25%  |
| SAS  | 4         | 7      | 4.04%   |
| MMC  | 3         | 3      | 3.03%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 43        | 65     | 44.79%  |
| 0.51-1.0   | 38        | 50     | 39.58%  |
| 1.01-2.0   | 11        | 20     | 11.46%  |
| 2.01-3.0   | 2         | 2      | 2.08%   |
| 10.01-20.0 | 2         | 3      | 2.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| More than 3000 | 19        | 23.46%  |
| 1001-2000      | 17        | 20.99%  |
| 501-1000       | 14        | 17.28%  |
| 2001-3000      | 12        | 14.81%  |
| 251-500        | 11        | 13.58%  |
| 51-100         | 3         | 3.7%    |
| 1-20           | 2         | 2.47%   |
| Unknown        | 2         | 2.47%   |
| 101-250        | 1         | 1.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 16        | 18.82%  |
| 101-250        | 16        | 18.82%  |
| 51-100         | 16        | 18.82%  |
| 501-1000       | 11        | 12.94%  |
| 1001-2000      | 9         | 10.59%  |
| 1-20           | 7         | 8.24%   |
| 2001-3000      | 4         | 4.71%   |
| 21-50          | 3         | 3.53%   |
| Unknown        | 2         | 2.35%   |
| More than 3000 | 1         | 1.18%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-00V0TT0 500GB     | 1         | 1      | 14.29%  |
| WDC WD2500BEVT-60ZCT1 250GB      | 1         | 1      | 14.29%  |
| Seagate ST3320620AS 320GB        | 1         | 1      | 14.29%  |
| Seagate ST1000LM035-1RK172 1TB   | 1         | 1      | 14.29%  |
| Phison 311CD0512GB               | 1         | 1      | 14.29%  |
| Kingston SV300S37A120G 120GB SSD | 1         | 1      | 14.29%  |
| Crucial CT1000P1SSD8 1TB         | 1         | 1      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| WDC      | 2         | 2      | 28.57%  |
| Seagate  | 2         | 2      | 28.57%  |
| Phison   | 1         | 1      | 14.29%  |
| Kingston | 1         | 1      | 14.29%  |
| Crucial  | 1         | 1      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 2      | 50%     |
| Seagate | 2         | 2      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 4         | 4      | 57.14%  |
| NVMe | 2         | 2      | 28.57%  |
| SSD  | 1         | 1      | 14.29%  |

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
| Detected | 41        | 88     | 48.24%  |
| Works    | 37        | 79     | 43.53%  |
| Malfunc  | 7         | 7      | 8.24%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 50        | 48.08%  |
| AMD                          | 19        | 18.27%  |
| Samsung Electronics          | 9         | 8.65%   |
| Sandisk                      | 5         | 4.81%   |
| Phison Electronics           | 3         | 2.88%   |
| Silicon Motion               | 2         | 1.92%   |
| Micron/Crucial Technology    | 2         | 1.92%   |
| Micron Technology            | 2         | 1.92%   |
| Marvell Technology Group     | 2         | 1.92%   |
| Lite-On Technology           | 2         | 1.92%   |
| ASMedia Technology           | 2         | 1.92%   |
| Toshiba America Info Systems | 1         | 0.96%   |
| Silicon Image                | 1         | 0.96%   |
| Seagate Technology           | 1         | 0.96%   |
| Nvidia                       | 1         | 0.96%   |
| Kingston Technology Company  | 1         | 0.96%   |
| Broadcom / LSI               | 1         | 0.96%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 16        | 13.33%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 6         | 5%      |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 6         | 5%      |
| AMD 400 Series Chipset SATA Controller                                                  | 4         | 3.33%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 3         | 2.5%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 3         | 2.5%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3         | 2.5%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 3         | 2.5%    |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 2         | 1.67%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                              | 2         | 1.67%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2         | 1.67%   |
| Samsung NVMe SSD Controller 980                                                         | 2         | 1.67%   |
| Micron Non-Volatile memory controller                                                   | 2         | 1.67%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2         | 1.67%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 2         | 1.67%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2         | 1.67%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 2         | 1.67%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2         | 1.67%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 2         | 1.67%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 2         | 1.67%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 2         | 1.67%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 2         | 1.67%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 2         | 1.67%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2         | 1.67%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2         | 1.67%   |
| AMD X370 Series Chipset SATA Controller                                                 | 2         | 1.67%   |
| AMD 300 Series Chipset SATA Controller                                                  | 2         | 1.67%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                    | 1         | 0.83%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                                    | 1         | 0.83%   |
| Seagate FireCuda 520 SSD                                                                | 1         | 0.83%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 1         | 0.83%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 1         | 0.83%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1         | 0.83%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1         | 0.83%   |
| Phison E12 NVMe Controller                                                              | 1         | 0.83%   |
| Nvidia MCP61 SATA Controller                                                            | 1         | 0.83%   |
| Nvidia MCP61 IDE                                                                        | 1         | 0.83%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 1         | 0.83%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                         | 1         | 0.83%   |
| Marvell Group 88SE912x SATA 6Gb/s Controller [IDE mode]                                 | 1         | 0.83%   |
| Marvell Group 88SE9128 PCIe SATA 6 Gb/s RAID controller with HyperDuo                   | 1         | 0.83%   |
| Lite-On SATA controller                                                                 | 1         | 0.83%   |
| Lite-On Non-Volatile memory controller                                                  | 1         | 0.83%   |
| Kingston Company A2000 NVMe SSD                                                         | 1         | 0.83%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 1         | 0.83%   |
| Intel SSD 660P Series                                                                   | 1         | 0.83%   |
| Intel SATA Controller [RAID mode]                                                       | 1         | 0.83%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1         | 0.83%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 1         | 0.83%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 1         | 0.83%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 1         | 0.83%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 1         | 0.83%   |
| Intel 82801GR/GDH (ICH7R/ICH7DH) SATA Controller [RAID mode]                            | 1         | 0.83%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1         | 0.83%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1         | 0.83%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1         | 0.83%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 1         | 0.83%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 1         | 0.83%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 1         | 0.83%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 1         | 0.83%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 60        | 59.41%  |
| NVMe | 25        | 24.75%  |
| IDE  | 10        | 9.9%    |
| RAID | 6         | 5.94%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 55        | 69.62%  |
| AMD    | 24        | 30.38%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz           | 3         | 3.8%    |
| Intel Core i7-9750H CPU @ 2.60GHz           | 2         | 2.53%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 2         | 2.53%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 2         | 2.53%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 2         | 2.53%   |
| Intel Xeon CPU E5-2687W v2 @ 3.40GHz        | 1         | 1.27%   |
| Intel Xeon CPU E5-2470 v2 @ 2.40GHz         | 1         | 1.27%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1         | 1.27%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1         | 1.27%   |
| Intel Pentium CPU G3258 @ 3.20GHz           | 1         | 1.27%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 1         | 1.27%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1         | 1.27%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 1.27%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 1.27%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 1.27%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1         | 1.27%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 1         | 1.27%   |
| Intel Core i7-5600U CPU @ 2.60GHz           | 1         | 1.27%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz          | 1         | 1.27%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1         | 1.27%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz          | 1         | 1.27%   |
| Intel Core i7-3740QM CPU @ 2.70GHz          | 1         | 1.27%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 1         | 1.27%   |
| Intel Core i5-8365U CPU @ 1.60GHz           | 1         | 1.27%   |
| Intel Core i5-7600K CPU @ 3.80GHz           | 1         | 1.27%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 1         | 1.27%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 1         | 1.27%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 1         | 1.27%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 1         | 1.27%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 1         | 1.27%   |
| Intel Core i5-4200M CPU @ 2.50GHz           | 1         | 1.27%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1         | 1.27%   |
| Intel Core i5-3317U CPU @ 1.70GHz           | 1         | 1.27%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 1         | 1.27%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 1.27%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 1         | 1.27%   |
| Intel Core i5-2400S CPU @ 2.50GHz           | 1         | 1.27%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 1         | 1.27%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 1         | 1.27%   |
| Intel Core i5 CPU M 460 @ 2.53GHz           | 1         | 1.27%   |
| Intel Core i3-8100 CPU @ 3.60GHz            | 1         | 1.27%   |
| Intel Core i3-7100U CPU @ 2.40GHz           | 1         | 1.27%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 1         | 1.27%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 1         | 1.27%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 1         | 1.27%   |
| Intel Core 2 Quad CPU Q9300 @ 2.50GHz       | 1         | 1.27%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz        | 1         | 1.27%   |
| Intel Core 2 Duo CPU T5250 @ 1.50GHz        | 1         | 1.27%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 1         | 1.27%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 1         | 1.27%   |
| Intel Core 2 CPU 6400 @ 2.13GHz             | 1         | 1.27%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 1         | 1.27%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 1         | 1.27%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz     | 1         | 1.27%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 1         | 1.27%   |
| AMD Sempron 2650 APU with Radeon R3         | 1         | 1.27%   |
| AMD Ryzen 9 3950X 16-Core Processor         | 1         | 1.27%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics  | 1         | 1.27%   |
| AMD Ryzen 7 4800H with Radeon Graphics      | 1         | 1.27%   |
| AMD Ryzen 7 4700U with Radeon Graphics      | 1         | 1.27%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 20        | 25.32%  |
| Intel Core i7           | 15        | 18.99%  |
| AMD Ryzen 7             | 7         | 8.86%   |
| Intel Core i3           | 5         | 6.33%   |
| AMD Ryzen 9             | 5         | 6.33%   |
| Intel Core 2 Duo        | 4         | 5.06%   |
| AMD Ryzen 5             | 4         | 5.06%   |
| Other                   | 2         | 2.53%   |
| Intel Xeon              | 2         | 2.53%   |
| Intel Celeron           | 2         | 2.53%   |
| AMD A6                  | 2         | 2.53%   |
| Intel Pentium Dual-Core | 1         | 1.27%   |
| Intel Pentium Dual      | 1         | 1.27%   |
| Intel Pentium           | 1         | 1.27%   |
| Intel Core 2 Quad       | 1         | 1.27%   |
| Intel Core 2            | 1         | 1.27%   |
| AMD Sempron             | 1         | 1.27%   |
| AMD Ryzen 7 PRO         | 1         | 1.27%   |
| AMD Ryzen 3             | 1         | 1.27%   |
| AMD Phenom II X4        | 1         | 1.27%   |
| AMD FX                  | 1         | 1.27%   |
| AMD Athlon              | 1         | 1.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 30        | 37.97%  |
| 4      | 26        | 32.91%  |
| 8      | 10        | 12.66%  |
| 6      | 7         | 8.86%   |
| 16     | 3         | 3.8%    |
| 12     | 2         | 2.53%   |
| 20     | 1         | 1.27%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 78        | 98.73%  |
| 2      | 1         | 1.27%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 54        | 68.35%  |
| 1      | 25        | 31.65%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 79        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 33        | 40.24%  |
| 0x806e9    | 3         | 3.66%   |
| 0x6fd      | 3         | 3.66%   |
| 0x306c3    | 3         | 3.66%   |
| 0x206a7    | 3         | 3.66%   |
| 0x08600106 | 3         | 3.66%   |
| 0x906ea    | 2         | 2.44%   |
| 0x906e9    | 2         | 2.44%   |
| 0x406e3    | 2         | 2.44%   |
| 0x306a9    | 2         | 2.44%   |
| 0x0a201016 | 2         | 2.44%   |
| 0x0a201009 | 2         | 2.44%   |
| 0x08108109 | 2         | 2.44%   |
| 0x08001137 | 2         | 2.44%   |
| 0xa0653    | 1         | 1.22%   |
| 0x806ec    | 1         | 1.22%   |
| 0x806d1    | 1         | 1.22%   |
| 0x806c1    | 1         | 1.22%   |
| 0x706a1    | 1         | 1.22%   |
| 0x506e3    | 1         | 1.22%   |
| 0x306e4    | 1         | 1.22%   |
| 0x306d4    | 1         | 1.22%   |
| 0x30678    | 1         | 1.22%   |
| 0x20655    | 1         | 1.22%   |
| 0x1067a    | 1         | 1.22%   |
| 0x10677    | 1         | 1.22%   |
| 0x10676    | 1         | 1.22%   |
| 0x08701021 | 1         | 1.22%   |
| 0x08108102 | 1         | 1.22%   |
| 0x0800820d | 1         | 1.22%   |
| 0x07030105 | 1         | 1.22%   |
| 0x010000db | 1         | 1.22%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 15        | 18.99%  |
| IvyBridge     | 7         | 8.86%   |
| Haswell       | 7         | 8.86%   |
| Zen 2         | 6         | 7.59%   |
| Zen+          | 5         | 6.33%   |
| Skylake       | 5         | 6.33%   |
| Zen 3         | 4         | 5.06%   |
| Zen           | 4         | 5.06%   |
| SandyBridge   | 4         | 5.06%   |
| Penryn        | 4         | 5.06%   |
| Core          | 4         | 5.06%   |
| Westmere      | 2         | 2.53%   |
| TigerLake     | 1         | 1.27%   |
| Silvermont    | 1         | 1.27%   |
| Puma          | 1         | 1.27%   |
| Piledriver    | 1         | 1.27%   |
| Nehalem       | 1         | 1.27%   |
| K10 Llano     | 1         | 1.27%   |
| K10           | 1         | 1.27%   |
| Jaguar        | 1         | 1.27%   |
| Icelake       | 1         | 1.27%   |
| Goldmont plus | 1         | 1.27%   |
| CometLake     | 1         | 1.27%   |
| Broadwell     | 1         | 1.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 44        | 44.9%   |
| Nvidia | 30        | 30.61%  |
| AMD    | 24        | 24.49%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                                 | 4         | 4%      |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 4         | 4%      |
| Intel 3rd Gen Core processor Graphics Controller                                      | 4         | 4%      |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 4         | 4%      |
| Intel HD Graphics 630                                                                 | 3         | 3%      |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 3         | 3%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 3         | 3%      |
| AMD Renoir                                                                            | 3         | 3%      |
| Nvidia TU117 [GeForce GTX 1650]                                                       | 2         | 2%      |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 2         | 2%      |
| Nvidia GA102 [GeForce RTX 3090]                                                       | 2         | 2%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller           | 2         | 2%      |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 2         | 2%      |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                   | 2         | 2%      |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                     | 2         | 2%      |
| Intel HD Graphics 530                                                                 | 2         | 2%      |
| Intel Core Processor Integrated Graphics Controller                                   | 2         | 2%      |
| Intel 4 Series Chipset Integrated Graphics Controller                                 | 2         | 2%      |
| AMD Tonga PRO [Radeon R9 285/380]                                                     | 2         | 2%      |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                               | 2         | 2%      |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 1         | 1%      |
| Nvidia TU116 [GeForce GTX 1660]                                                       | 1         | 1%      |
| Nvidia TU106 [GeForce RTX 2070]                                                       | 1         | 1%      |
| Nvidia GT216 [GeForce GT 220]                                                         | 1         | 1%      |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                           | 1         | 1%      |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                    | 1         | 1%      |
| Nvidia GP104 [GeForce GTX 1070]                                                       | 1         | 1%      |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                    | 1         | 1%      |
| Nvidia GM206 [GeForce GTX 960]                                                        | 1         | 1%      |
| Nvidia GM204M [GeForce GTX 980M]                                                      | 1         | 1%      |
| Nvidia GM204M [GeForce GTX 970M]                                                      | 1         | 1%      |
| Nvidia GM108M [GeForce 940MX]                                                         | 1         | 1%      |
| Nvidia GM107M [GeForce GTX 960M]                                                      | 1         | 1%      |
| Nvidia GK208B [GeForce GT 710]                                                        | 1         | 1%      |
| Nvidia GK107 [GeForce GTX 650]                                                        | 1         | 1%      |
| Nvidia GK104GLM [Quadro K3000M]                                                       | 1         | 1%      |
| Nvidia GF119 [GeForce GT 520]                                                         | 1         | 1%      |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 1         | 1%      |
| Nvidia GF100GL [Tesla C2050 / C2070]                                                  | 1         | 1%      |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                            | 1         | 1%      |
| Nvidia GA104 [GeForce RTX 3070]                                                       | 1         | 1%      |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                                    | 1         | 1%      |
| Nvidia G98M [GeForce 9300M GS]                                                        | 1         | 1%      |
| Nvidia G84 [GeForce 8600 GT]                                                          | 1         | 1%      |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 1         | 1%      |
| Intel UHD Graphics 620                                                                | 1         | 1%      |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 1         | 1%      |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 1         | 1%      |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 1         | 1%      |
| Intel HD Graphics 5500                                                                | 1         | 1%      |
| Intel GeminiLake [UHD Graphics 600]                                                   | 1         | 1%      |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 1         | 1%      |
| Intel CometLake-S GT2 [UHD Graphics 630]                                              | 1         | 1%      |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                             | 1         | 1%      |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 1         | 1%      |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 1%      |
| AMD Thames [Radeon HD 7500M/7600M Series]                                             | 1         | 1%      |
| AMD Sun PRO [Radeon HD 8570A/8570M]                                                   | 1         | 1%      |
| AMD Sumo [Radeon HD 6520G]                                                            | 1         | 1%      |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                            | 1         | 1%      |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 26        | 32.91%  |
| 1 x AMD        | 19        | 24.05%  |
| 1 x Nvidia     | 18        | 22.78%  |
| Intel + Nvidia | 11        | 13.92%  |
| Intel + AMD    | 5         | 6.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 63        | 79.75%  |
| Proprietary | 15        | 18.99%  |
| Unknown     | 1         | 1.27%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 52        | 64.2%   |
| 1.01-2.0   | 6         | 7.41%   |
| 0.01-0.5   | 6         | 7.41%   |
| 7.01-8.0   | 4         | 4.94%   |
| 3.01-4.0   | 4         | 4.94%   |
| 0.51-1.0   | 3         | 3.7%    |
| 5.01-6.0   | 2         | 2.47%   |
| 16.01-24.0 | 2         | 2.47%   |
| 8.01-16.0  | 2         | 2.47%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| LG Display           | 12        | 13.04%  |
| Goldstar             | 11        | 11.96%  |
| Chimei Innolux       | 11        | 11.96%  |
| Samsung Electronics  | 8         | 8.7%    |
| AU Optronics         | 8         | 8.7%    |
| Dell                 | 7         | 7.61%   |
| Hewlett-Packard      | 4         | 4.35%   |
| BenQ                 | 4         | 4.35%   |
| Ancor Communications | 4         | 4.35%   |
| Philips              | 3         | 3.26%   |
| Acer                 | 3         | 3.26%   |
| LG Electronics       | 2         | 2.17%   |
| Lenovo               | 2         | 2.17%   |
| AOC                  | 2         | 2.17%   |
| ViewSonic            | 1         | 1.09%   |
| TCL                  | 1         | 1.09%   |
| Sony                 | 1         | 1.09%   |
| Sharp                | 1         | 1.09%   |
| LG Philips           | 1         | 1.09%   |
| InfoVision           | 1         | 1.09%   |
| Iiyama               | 1         | 1.09%   |
| Denver               | 1         | 1.09%   |
| CSO                  | 1         | 1.09%   |
| BOE                  | 1         | 1.09%   |
| ASUSTek Computer     | 1         | 1.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 2.11%   |
| Hewlett-Packard LV1911 HWP3005 1366x768 410x230mm 18.5-inch           | 2         | 2.11%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 2         | 2.11%   |
| ViewSonic VX3211-2K VSCF634 2560x1440 698x392mm 31.5-inch             | 1         | 1.05%   |
| TCL LCD TV TCL0030 1920x1080 708x398mm 32.0-inch                      | 1         | 1.05%   |
| Sony Nvidia Defaul t Flat Panel SNY06FA 1600x900 360x200mm 16.2-inch  | 1         | 1.05%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch               | 1         | 1.05%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch     | 1         | 1.05%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 1         | 1.05%   |
| Samsung Electronics SyncMaster SAM0524 1920x1080 477x268mm 21.5-inch  | 1         | 1.05%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch  | 1         | 1.05%   |
| Samsung Electronics S34J55x SAM0F72 3440x1440 797x333mm 34.0-inch     | 1         | 1.05%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch     | 1         | 1.05%   |
| Samsung Electronics S23B550 SAM0919 1920x1080 510x287mm 23.0-inch     | 1         | 1.05%   |
| Samsung Electronics LCD Monitor SEC3449 1366x768 309x174mm 14.0-inch  | 1         | 1.05%   |
| Samsung Electronics LCD Monitor SDC424B 3840x2160 344x194mm 15.5-inch | 1         | 1.05%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 950x540mm 43.0-inch | 1         | 1.05%   |
| Philips PHL 258B6QU PHL08F5 2560x1440 553x311mm 25.0-inch             | 1         | 1.05%   |
| Philips 150S PHL0812 1024x768 307x230mm 15.1-inch                     | 1         | 1.05%   |
| Philips 150S PHL0805 1024x768 307x230mm 15.1-inch                     | 1         | 1.05%   |
| LG Philips LCD Monitor LPLDB00 1280x800 331x207mm 15.4-inch           | 1         | 1.05%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                     | 1         | 1.05%   |
| LG Electronics LCD Monitor LG TV SSCR 3840x2160                       | 1         | 1.05%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch          | 1         | 1.05%   |
| LG Display LCD Monitor LGD05C0 1920x1080 344x194mm 15.5-inch          | 1         | 1.05%   |
| LG Display LCD Monitor LGD059E 1920x1080 382x215mm 17.3-inch          | 1         | 1.05%   |
| LG Display LCD Monitor LGD053C 1920x1080 309x174mm 14.0-inch          | 1         | 1.05%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch          | 1         | 1.05%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 1.05%   |
| LG Display LCD Monitor LGD04A9 1920x1080 309x174mm 14.0-inch          | 1         | 1.05%   |
| LG Display LCD Monitor LGD046C 1920x1080 380x210mm 17.1-inch          | 1         | 1.05%   |
| LG Display LCD Monitor LGD044F 1920x1080 350x190mm 15.7-inch          | 1         | 1.05%   |
| LG Display LCD Monitor LGD02DA 1920x1080 380x220mm 17.3-inch          | 1         | 1.05%   |
| Lenovo LEN P27q-10 LEN61A8 2560x1440 597x336mm 27.0-inch              | 1         | 1.05%   |
| Lenovo LCD Monitor LEN4020 1024x768 286x214mm 14.1-inch               | 1         | 1.05%   |
| InfoVision LCD Monitor IVO03F4 1920x1200 263x164mm 12.2-inch          | 1         | 1.05%   |
| Iiyama PL2492H IVM612F 1920x1080 530x300mm 24.0-inch                  | 1         | 1.05%   |
| Hewlett-Packard LA1951 HWP285A 1280x1024 380x300mm 19.1-inch          | 1         | 1.05%   |
| Hewlett-Packard 27es HWP3326 1920x1080 598x336mm 27.0-inch            | 1         | 1.05%   |
| Goldstar MP59G GSM5B35 1920x1080 480x270mm 21.7-inch                  | 1         | 1.05%   |
| Goldstar LG ULTRAWIDE GSM59F1 1920x1080 580x240mm 24.7-inch           | 1         | 1.05%   |
| Goldstar LG FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch             | 1         | 1.05%   |
| Goldstar L1718S GSM443C 1280x1024 338x270mm 17.0-inch                 | 1         | 1.05%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 1         | 1.05%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                | 1         | 1.05%   |
| Goldstar E2742 GSM58C9 1920x1080 598x337mm 27.0-inch                  | 1         | 1.05%   |
| Goldstar E2441 GSM581F 1920x1080 531x299mm 24.0-inch                  | 1         | 1.05%   |
| Goldstar 2D FHD LG TV GSM59C6 1920x1080 509x286mm 23.0-inch           | 1         | 1.05%   |
| Denver UWQHD-100-V2 LHC3500 3440x1440 798x342mm 34.2-inch             | 1         | 1.05%   |
| Dell UZ2315H DELF055 1920x1080 509x286mm 23.0-inch                    | 1         | 1.05%   |
| Dell U2711 DELA057 2560x1440 597x336mm 27.0-inch                      | 1         | 1.05%   |
| Dell U2410 DELF017 1920x1200 518x324mm 24.1-inch                      | 1         | 1.05%   |
| Dell S2216H DELD07A 1920x1080 476x268mm 21.5-inch                     | 1         | 1.05%   |
| Dell P2219H DELA114 1920x1080 476x267mm 21.5-inch                     | 1         | 1.05%   |
| Dell E228WFP DELD014 1680x1050 473x296mm 22.0-inch                    | 1         | 1.05%   |
| Dell 1703FP DEL3011 1280x1024 338x270mm 17.0-inch                     | 1         | 1.05%   |
| CSO LCD Monitor CSO1404 1920x1200 302x189mm 14.0-inch                 | 1         | 1.05%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch      | 1         | 1.05%   |
| Chimei Innolux LCD Monitor CMN15F6 1920x1080 344x193mm 15.5-inch      | 1         | 1.05%   |
| Chimei Innolux LCD Monitor CMN15F4 1920x1080 344x193mm 15.5-inch      | 1         | 1.05%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 37        | 44.05%  |
| 1366x768 (WXGA)    | 13        | 15.48%  |
| 3840x2160 (4K)     | 5         | 5.95%   |
| 2560x1440 (QHD)    | 5         | 5.95%   |
| 2560x1080          | 4         | 4.76%   |
| 1920x1200 (WUXGA)  | 3         | 3.57%   |
| 1600x900 (HD+)     | 3         | 3.57%   |
| 1024x768 (XGA)     | 3         | 3.57%   |
| 3440x1440          | 2         | 2.38%   |
| 1680x1050 (WSXGA+) | 2         | 2.38%   |
| 1280x1024 (SXGA)   | 2         | 2.38%   |
| 640x480            | 1         | 1.19%   |
| 3840x2400          | 1         | 1.19%   |
| 2160x1440          | 1         | 1.19%   |
| 1440x900 (WXGA+)   | 1         | 1.19%   |
| 1280x800 (WXGA)    | 1         | 1.19%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 23        | 25.56%  |
| 14      | 9         | 10%     |
| 27      | 8         | 8.89%   |
| 21      | 8         | 8.89%   |
| 17      | 8         | 8.89%   |
| 34      | 5         | 5.56%   |
| 23      | 5         | 5.56%   |
| 24      | 4         | 4.44%   |
| 18      | 3         | 3.33%   |
| 13      | 3         | 3.33%   |
| Unknown | 3         | 3.33%   |
| 22      | 2         | 2.22%   |
| 11      | 2         | 2.22%   |
| 84      | 1         | 1.11%   |
| 32      | 1         | 1.11%   |
| 31      | 1         | 1.11%   |
| 26      | 1         | 1.11%   |
| 25      | 1         | 1.11%   |
| 20      | 1         | 1.11%   |
| 19      | 1         | 1.11%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 35        | 38.89%  |
| 501-600     | 17        | 18.89%  |
| 401-500     | 15        | 16.67%  |
| 701-800     | 6         | 6.67%   |
| 351-400     | 6         | 6.67%   |
| 201-300     | 4         | 4.44%   |
| 601-700     | 3         | 3.33%   |
| Unknown     | 3         | 3.33%   |
| 1501-2000   | 1         | 1.11%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 60        | 74.07%  |
| 16/10   | 7         | 8.64%   |
| 21/9    | 5         | 6.17%   |
| 4/3     | 3         | 3.7%    |
| Unknown | 3         | 3.7%    |
| 5/4     | 2         | 2.47%   |
| 3/2     | 1         | 1.23%   |

Monitor Area
------------

Area in inchÂ²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inchÂ² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 23        | 25.56%  |
| 201-250        | 18        | 20%     |
| 81-90          | 11        | 12.22%  |
| 301-350        | 9         | 10%     |
| 351-500        | 7         | 7.78%   |
| 121-130        | 6         | 6.67%   |
| 141-150        | 5         | 5.56%   |
| 151-200        | 3         | 3.33%   |
| Unknown        | 3         | 3.33%   |
| 51-60          | 2         | 2.22%   |
| More than 1000 | 1         | 1.11%   |
| 251-300        | 1         | 1.11%   |
| 91-100         | 1         | 1.11%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 31        | 35.23%  |
| 101-120       | 27        | 30.68%  |
| 121-160       | 23        | 26.14%  |
| Unknown       | 3         | 3.41%   |
| More than 240 | 2         | 2.27%   |
| 161-240       | 2         | 2.27%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 60        | 75.95%  |
| 2     | 16        | 20.25%  |
| 0     | 2         | 2.53%   |
| 3     | 1         | 1.27%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 44        | 35.48%  |
| Intel                 | 40        | 32.26%  |
| Qualcomm Atheros      | 14        | 11.29%  |
| Broadcom              | 7         | 5.65%   |
| Ralink                | 3         | 2.42%   |
| Broadcom Limited      | 3         | 2.42%   |
| Samsung Electronics   | 2         | 1.61%   |
| ZyXEL Communications  | 1         | 0.81%   |
| TP-Link               | 1         | 0.81%   |
| TOMTOM                | 1         | 0.81%   |
| Ralink Technology     | 1         | 0.81%   |
| NetXen Incorporated   | 1         | 0.81%   |
| Manta                 | 1         | 0.81%   |
| Lenovo                | 1         | 0.81%   |
| Dell                  | 1         | 0.81%   |
| D-Link System         | 1         | 0.81%   |
| AVM                   | 1         | 0.81%   |
| ASIX Electronics      | 1         | 0.81%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 32        | 21.33%  |
| Intel Wi-Fi 6 AX200                                                  | 8         | 5.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 4         | 2.67%   |
| Intel Wireless 7260                                                  | 4         | 2.67%   |
| Intel I211 Gigabit Network Connection                                | 4         | 2.67%   |
| Realtek RTL8125 2.5GbE Controller                                    | 3         | 2%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 3         | 2%      |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller            | 3         | 2%      |
| Intel Wireless 8260                                                  | 3         | 2%      |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 2         | 1.33%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 2         | 1.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                             | 2         | 1.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 2         | 1.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 2         | 1.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 2         | 1.33%   |
| Intel Wireless 8265 / 8275                                           | 2         | 1.33%   |
| Intel Wireless 3165                                                  | 2         | 1.33%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 2         | 1.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 2         | 1.33%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 2         | 1.33%   |
| ZyXEL NWD2205 802.11n Wireless N Adapter [Realtek RTL8192CU]         | 1         | 0.67%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                  | 1         | 0.67%   |
| TOMTOM GO 60                                                         | 1         | 0.67%   |
| Samsung Kiera                                                        | 1         | 0.67%   |
| Samsung Galaxy series, misc. (tethering mode)                        | 1         | 0.67%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 1         | 0.67%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter             | 1         | 0.67%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 1         | 0.67%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                           | 1         | 0.67%   |
| Realtek Killer E3000 2.5GbE Controller                               | 1         | 0.67%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                     | 1         | 0.67%   |
| Ralink RT3072 Wireless Adapter                                       | 1         | 0.67%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                            | 1         | 0.67%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                 | 1         | 0.67%   |
| Ralink RT2561/RT61 802.11g PCI                                       | 1         | 0.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 1         | 0.67%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                               | 1         | 0.67%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                            | 1         | 0.67%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 1         | 0.67%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                           | 1         | 0.67%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                        | 1         | 0.67%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet       | 1         | 0.67%   |
| NetXen Incorporated NX3031 Multifunction 1/10-Gigabit Server Adapter | 1         | 0.67%   |
| Manta MM812                                                          | 1         | 0.67%   |
| Lenovo OneLink+ Giga                                                 | 1         | 0.67%   |
| Intel Wireless-AC 9260                                               | 1         | 0.67%   |
| Intel Wireless 7265                                                  | 1         | 0.67%   |
| Intel WiFi Link 5100                                                 | 1         | 0.67%   |
| Intel Wi-Fi 6 AX201                                                  | 1         | 0.67%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection        | 1         | 0.67%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                | 1         | 0.67%   |
| Intel Gemini Lake PCH CNVi WiFi                                      | 1         | 0.67%   |
| Intel Ethernet Connection I219-V                                     | 1         | 0.67%   |
| Intel Ethernet Connection I219-LM                                    | 1         | 0.67%   |
| Intel Ethernet Connection I217-V                                     | 1         | 0.67%   |
| Intel Ethernet Connection I217-LM                                    | 1         | 0.67%   |
| Intel Ethernet Connection (6) I219-LM                                | 1         | 0.67%   |
| Intel Ethernet Connection (4) I219-LM                                | 1         | 0.67%   |
| Intel Ethernet Connection (3) I218-LM                                | 1         | 0.67%   |
| Intel Ethernet Connection (2) I219-LM                                | 1         | 0.67%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 33        | 50%     |
| Realtek Semiconductor | 11        | 16.67%  |
| Qualcomm Atheros      | 8         | 12.12%  |
| Broadcom              | 5         | 7.58%   |
| Ralink                | 3         | 4.55%   |
| ZyXEL Communications  | 1         | 1.52%   |
| TP-Link               | 1         | 1.52%   |
| Ralink Technology     | 1         | 1.52%   |
| D-Link System         | 1         | 1.52%   |
| Broadcom Limited      | 1         | 1.52%   |
| AVM                   | 1         | 1.52%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                        | 8         | 12.12%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 4         | 6.06%   |
| Intel Wireless 7260                                                        | 4         | 6.06%   |
| Intel Wireless 8260                                                        | 3         | 4.55%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                   | 2         | 3.03%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                            | 2         | 3.03%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                 | 2         | 3.03%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                 | 2         | 3.03%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                           | 2         | 3.03%   |
| Intel Wireless 8265 / 8275                                                 | 2         | 3.03%   |
| Intel Wireless 3165                                                        | 2         | 3.03%   |
| Intel Tiger Lake PCH CNVi WiFi                                             | 2         | 3.03%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                        | 2         | 3.03%   |
| ZyXEL NWD2205 802.11n Wireless N Adapter [Realtek RTL8192CU]               | 1         | 1.52%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                        | 1         | 1.52%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                   | 1         | 1.52%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                   | 1         | 1.52%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                 | 1         | 1.52%   |
| Ralink RT3072 Wireless Adapter                                             | 1         | 1.52%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                  | 1         | 1.52%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                       | 1         | 1.52%   |
| Ralink RT2561/RT61 802.11g PCI                                             | 1         | 1.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                 | 1         | 1.52%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                           | 1         | 1.52%   |
| Intel Wireless-AC 9260                                                     | 1         | 1.52%   |
| Intel Wireless 7265                                                        | 1         | 1.52%   |
| Intel WiFi Link 5100                                                       | 1         | 1.52%   |
| Intel Wi-Fi 6 AX201                                                        | 1         | 1.52%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection              | 1         | 1.52%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                      | 1         | 1.52%   |
| Intel Gemini Lake PCH CNVi WiFi                                            | 1         | 1.52%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 1         | 1.52%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                               | 1         | 1.52%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                              | 1         | 1.52%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                   | 1         | 1.52%   |
| Intel Cannon Lake PCH CNVi WiFi                                            | 1         | 1.52%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 1         | 1.52%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                 | 1         | 1.52%   |
| Broadcom BCM43228 802.11a/b/g/n                                            | 1         | 1.52%   |
| Broadcom BCM43227 802.11b/g/n                                              | 1         | 1.52%   |
| Broadcom BCM43225 802.11b/g/n                                              | 1         | 1.52%   |
| AVM Fritz!WLAN N v2 [Atheros AR9271]                                       | 1         | 1.52%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 40        | 51.95%  |
| Intel                 | 20        | 25.97%  |
| Qualcomm Atheros      | 8         | 10.39%  |
| Broadcom              | 3         | 3.9%    |
| Broadcom Limited      | 2         | 2.6%    |
| Samsung Electronics   | 1         | 1.3%    |
| NetXen Incorporated   | 1         | 1.3%    |
| Lenovo                | 1         | 1.3%    |
| ASIX Electronics      | 1         | 1.3%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 32        | 40%     |
| Intel I211 Gigabit Network Connection                                | 4         | 5%      |
| Realtek RTL8125 2.5GbE Controller                                    | 3         | 3.75%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 3         | 3.75%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller            | 3         | 3.75%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                             | 2         | 2.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 2         | 2.5%    |
| Samsung Galaxy series, misc. (tethering mode)                        | 1         | 1.25%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                           | 1         | 1.25%   |
| Realtek Killer E3000 2.5GbE Controller                               | 1         | 1.25%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                     | 1         | 1.25%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                               | 1         | 1.25%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                            | 1         | 1.25%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                           | 1         | 1.25%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                        | 1         | 1.25%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet       | 1         | 1.25%   |
| NetXen Incorporated NX3031 Multifunction 1/10-Gigabit Server Adapter | 1         | 1.25%   |
| Lenovo OneLink+ Giga                                                 | 1         | 1.25%   |
| Intel Ethernet Connection I219-V                                     | 1         | 1.25%   |
| Intel Ethernet Connection I219-LM                                    | 1         | 1.25%   |
| Intel Ethernet Connection I217-V                                     | 1         | 1.25%   |
| Intel Ethernet Connection I217-LM                                    | 1         | 1.25%   |
| Intel Ethernet Connection (6) I219-LM                                | 1         | 1.25%   |
| Intel Ethernet Connection (4) I219-LM                                | 1         | 1.25%   |
| Intel Ethernet Connection (3) I218-LM                                | 1         | 1.25%   |
| Intel Ethernet Connection (2) I219-LM                                | 1         | 1.25%   |
| Intel Ethernet Connection (10) I219-V                                | 1         | 1.25%   |
| Intel 82579V Gigabit Network Connection                              | 1         | 1.25%   |
| Intel 82574L Gigabit Network Connection                              | 1         | 1.25%   |
| Intel 82567LM Gigabit Network Connection                             | 1         | 1.25%   |
| Intel 82566MM Gigabit Network Connection                             | 1         | 1.25%   |
| Intel 82562V-2 10/100 Network Connection                             | 1         | 1.25%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                     | 1         | 1.25%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                      | 1         | 1.25%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                      | 1         | 1.25%   |
| Broadcom Limited NetLink BCM57785 Gigabit Ethernet PCIe              | 1         | 1.25%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe              | 1         | 1.25%   |
| ASIX AX88179 Gigabit Ethernet                                        | 1         | 1.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 73        | 51.41%  |
| WiFi     | 65        | 45.77%  |
| Unknown  | 3         | 2.11%   |
| Modem    | 1         | 0.7%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 64        | 51.61%  |
| WiFi     | 58        | 46.77%  |
| Modem    | 1         | 0.81%   |
| Unknown  | 1         | 0.81%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 51        | 64.56%  |
| 1     | 23        | 29.11%  |
| 3     | 4         | 5.06%   |
| 5     | 1         | 1.27%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 60        | 75%     |
| Yes  | 20        | 25%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 21        | 40.38%  |
| Realtek Semiconductor           | 8         | 15.38%  |
| Qualcomm Atheros Communications | 6         | 11.54%  |
| Cambridge Silicon Radio         | 4         | 7.69%   |
| Foxconn / Hon Hai               | 2         | 3.85%   |
| Dell                            | 2         | 3.85%   |
| Broadcom                        | 2         | 3.85%   |
| ASUSTek Computer                | 2         | 3.85%   |
| Realtek                         | 1         | 1.92%   |
| Lite-On Technology              | 1         | 1.92%   |
| IMC Networks                    | 1         | 1.92%   |
| Belkin Components               | 1         | 1.92%   |
| Alps Electric                   | 1         | 1.92%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                                                              | 7         | 13.46%  |
| Intel Bluetooth wireless interface                                                  | 6         | 11.54%  |
| Intel AX200 Bluetooth                                                               | 6         | 11.54%  |
| Realtek  Bluetooth 4.2 Adapter                                                      | 4         | 7.69%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 4         | 7.69%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 4         | 7.69%   |
| Realtek Bluetooth Radio                                                             | 3         | 5.77%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 1.92%   |
| Realtek Bluetooth Radio                                                             | 1         | 1.92%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 1.92%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 1.92%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 1.92%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 1.92%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 1.92%   |
| IMC Networks Bluetooth Device                                                       | 1         | 1.92%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.92%   |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 1         | 1.92%   |
| Dell Broadcom BCM20702A0 Bluetooth                                                  | 1         | 1.92%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 1.92%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 1         | 1.92%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 1         | 1.92%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                               | 1         | 1.92%   |
| ASUS Bluetooth Adapter                                                              | 1         | 1.92%   |
| ASUS ASUS USB-BT500                                                                 | 1         | 1.92%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 1         | 1.92%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 53        | 45.3%   |
| AMD                       | 30        | 25.64%  |
| Nvidia                    | 21        | 17.95%  |
| Logitech                  | 2         | 1.71%   |
| Lenovo                    | 2         | 1.71%   |
| Creative Labs             | 2         | 1.71%   |
| C-Media Electronics       | 2         | 1.71%   |
| Texas Instruments         | 1         | 0.85%   |
| Sennheiser Communications | 1         | 0.85%   |
| JMTek                     | 1         | 0.85%   |
| GN Netcom                 | 1         | 0.85%   |
| BEHRINGER International   | 1         | 0.85%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 7         | 5.19%   |
| AMD Starship/Matisse HD Audio Controller                                   | 7         | 5.19%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6         | 4.44%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 6         | 4.44%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 3.7%    |
| Intel Cannon Lake PCH cAVS                                                 | 5         | 3.7%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 3.7%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 5         | 3.7%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 2.96%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 2.96%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 2.96%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 2.22%   |
| Nvidia GA102 High Definition Audio Controller                              | 3         | 2.22%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3         | 2.22%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 2.22%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3         | 2.22%   |
| AMD FCH Azalia Controller                                                  | 3         | 2.22%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 1.48%   |
| Logitech Headset H390                                                      | 2         | 1.48%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 1.48%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 1.48%   |
| AMD Tonga HDMI Audio [Radeon R9 285/380]                                   | 2         | 1.48%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 2         | 1.48%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2         | 1.48%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 1.48%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2         | 1.48%   |
| Texas Instruments PCM2900C Audio CODEC                                     | 1         | 0.74%   |
| Sennheiser Communications Sennheiser 3D G4ME1                              | 1         | 0.74%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.74%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.74%   |
| Nvidia MCP61 High Definition Audio                                         | 1         | 0.74%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 0.74%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 0.74%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1         | 0.74%   |
| Nvidia GM206 High Definition Audio Controller                              | 1         | 0.74%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 0.74%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.74%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 0.74%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.74%   |
| Nvidia GF100 High Definition Audio Controller                              | 1         | 0.74%   |
| Nvidia GA104 High Definition Audio Controller                              | 1         | 0.74%   |
| Lenovo ThinkPad Thunderbolt 4 Dock USB Audio                               | 1         | 0.74%   |
| Lenovo ThinkPad OneLink Plus Dock Audio                                    | 1         | 0.74%   |
| JMTek audio controller                                                     | 1         | 0.74%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 0.74%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 0.74%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 0.74%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 0.74%   |
| Intel CM238 HD Audio Controller                                            | 1         | 0.74%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 0.74%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 1         | 0.74%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 1         | 0.74%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 0.74%   |
| Intel Audio device                                                         | 1         | 0.74%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 0.74%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1         | 0.74%   |
| Intel 200 Series PCH HD Audio                                              | 1         | 0.74%   |
| GN Netcom Jabra UC VOICE 150a MS                                           | 1         | 0.74%   |
| Creative Labs Sound Core3D [Sound Blaster Recon3D / Z-Series]              | 1         | 0.74%   |
| Creative Labs CA0108/CA10300 [Sound Blaster Audigy Series]                 | 1         | 0.74%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Samsung Electronics    | 12        | 22.22%  |
| SK Hynix               | 7         | 12.96%  |
| Kingston               | 7         | 12.96%  |
| Unknown                | 6         | 11.11%  |
| G.Skill                | 4         | 7.41%   |
| Crucial                | 4         | 7.41%   |
| Corsair                | 3         | 5.56%   |
| Micron Technology      | 2         | 3.7%    |
| Unknown (000004B30000) | 1         | 1.85%   |
| Team                   | 1         | 1.85%   |
| Smart                  | 1         | 1.85%   |
| Ramaxel Technology     | 1         | 1.85%   |
| Patriot                | 1         | 1.85%   |
| GOODRAM                | 1         | 1.85%   |
| GeIL                   | 1         | 1.85%   |
| Elpida                 | 1         | 1.85%   |
| A-DATA Technology      | 1         | 1.85%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Kingston RAM KHX3600C18D4/32GX 32GB DIMM DDR4 3600MT/s      | 2         | 3.33%   |
| Unknown RAM Module 4GB SODIMM DDR2 667MT/s                  | 1         | 1.67%   |
| Unknown RAM Module 4096MB SODIMM DDR3                       | 1         | 1.67%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                  | 1         | 1.67%   |
| Unknown RAM Module 2048MB SODIMM 1067MT/s                   | 1         | 1.67%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s                | 1         | 1.67%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                  | 1         | 1.67%   |
| Unknown RAM Module 1024MB SODIMM 1067MT/s                   | 1         | 1.67%   |
| Unknown RAM 992124 (997124) 8GB DIMM DDR3 1600MT/s          | 1         | 1.67%   |
| Unknown (000004B30000) RAM Module 32GB DIMM DDR3 1333MT/s   | 1         | 1.67%   |
| Team RAM TEAMGROUP-UD4-2400 8192MB DIMM DDR4 3007MT/s       | 1         | 1.67%   |
| Smart RAM SH564568FH8NWPHSFG 2GB SODIMM DDR3 1333MT/s       | 1         | 1.67%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                | 1         | 1.67%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s      | 1         | 1.67%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s   | 1         | 1.67%   |
| SK Hynix RAM HMT351R7CFR8C-PB 4GB DIMM DDR3 1600MT/s        | 1         | 1.67%   |
| SK Hynix RAM HMT151R7BFR4C-G7 4GB DIMM DDR3 1066MT/s        | 1         | 1.67%   |
| SK Hynix RAM HMAB2GS6AMR6N-XN 16384MB SODIMM DDR4 3200MT/s  | 1         | 1.67%   |
| SK Hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s      | 1         | 1.67%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s   | 1         | 1.67%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s      | 1         | 1.67%   |
| Samsung RAM M471B5673FH0-CH9 2GB DIMM DDR3 4199MT/s         | 1         | 1.67%   |
| Samsung RAM M471B5673EH1-CH9 2048MB SODIMM DDR3 1334MT/s    | 1         | 1.67%   |
| Samsung RAM M471B5273DH0-CK0 4096MB SODIMM DDR3 1600MT/s    | 1         | 1.67%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s       | 1         | 1.67%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s    | 1         | 1.67%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s      | 1         | 1.67%   |
| Samsung RAM M471A2K43DB1-CTD 16384MB SODIMM DDR4 2667MT/s   | 1         | 1.67%   |
| Samsung RAM M471A2G43BB2-CWE 16384MB SODIMM DDR4 3200MT/s   | 1         | 1.67%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s       | 1         | 1.67%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s | 1         | 1.67%   |
| Samsung RAM K4F6E3S4HM-MGCJ 4GB SODIMM LPDDR4 3733MT/s      | 1         | 1.67%   |
| Samsung RAM K4E6E304EE-EGCF 4GB SODIMM LPDDR3 1867MT/s      | 1         | 1.67%   |
| Samsung RAM K4E6E304EE-EGCF 4GB Chip LPDDR3 1867MT/s        | 1         | 1.67%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s     | 1         | 1.67%   |
| Patriot RAM PSD48G266681 8192MB DIMM DDR4 2934MT/s          | 1         | 1.67%   |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s | 1         | 1.67%   |
| Micron RAM 16JTF1G64AZ-1G6D1 8GB DIMM DDR3 1600MT/s         | 1         | 1.67%   |
| Kingston RAM MSI26D4S9S8ME-8 8192MB SODIMM DDR4 2667MT/s    | 1         | 1.67%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s      | 1         | 1.67%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s           | 1         | 1.67%   |
| Kingston RAM ACR16D3LS1KFG/8G 8GB SODIMM DDR3 1600MT/s      | 1         | 1.67%   |
| Kingston RAM 99U5474-016.A00LF 4096MB DIMM DDR3 1333MT/s    | 1         | 1.67%   |
| Kingston RAM 9905474-012.A00LF 2048MB DIMM DDR3 1333MT/s    | 1         | 1.67%   |
| GOODRAM RAM IR2400S464L15S/8G 8192MB SODIMM DDR4 2133MT/s   | 1         | 1.67%   |
| GeIL RAM CL11-11-11 D3-1600 4096MB DIMM DDR3 1600MT/s       | 1         | 1.67%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s         | 1         | 1.67%   |
| G.Skill RAM F4-3200C15-16GTZKY 16384MB DIMM DDR4 3200MT/s   | 1         | 1.67%   |
| G.Skill RAM F4-2666C19-16GIS 16384MB DIMM DDR4 2667MT/s     | 1         | 1.67%   |
| G.Skill RAM F4-2400C15-8GNT 8GB DIMM DDR4 2400MT/s          | 1         | 1.67%   |
| Elpida RAM EBE11UD8AJWA-6E-E 1024MB DIMM DDR2 667MT/s       | 1         | 1.67%   |
| Crucial RAM CT16G4DFRA266.C16FE 16384MB DIMM DDR4 2667MT/s  | 1         | 1.67%   |
| Crucial RAM CT102464BD160B.M16 8GB DIMM DDR3 1600MT/s       | 1         | 1.67%   |
| Crucial RAM BLS16G4D32AESB.M16FE 16GB DIMM DDR4 3400MT/s    | 1         | 1.67%   |
| Crucial RAM BL32G32C16U4R.M16FB1 32GB DIMM DDR4 3200MT/s    | 1         | 1.67%   |
| Corsair RAM CMT64GX4M4E3200C16 16GB DIMM DDR4 3200MT/s      | 1         | 1.67%   |
| Corsair RAM CMSX8GX4M1A2400C16 8GB SODIMM DDR4 2400MT/s     | 1         | 1.67%   |
| Corsair RAM CMK16GX4M1E3200C16 16384MB DIMM DDR4 3000MT/s   | 1         | 1.67%   |
| A-DATA RAM Module 8192MB SODIMM DDR4 2133MT/s               | 1         | 1.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 26        | 54.17%  |
| DDR3    | 13        | 27.08%  |
| LPDDR4  | 3         | 6.25%   |
| DDR2    | 3         | 6.25%   |
| SDRAM   | 1         | 2.08%   |
| LPDDR3  | 1         | 2.08%   |
| Unknown | 1         | 2.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 24        | 50%     |
| DIMM         | 21        | 43.75%  |
| Row Of Chips | 2         | 4.17%   |
| Chip         | 1         | 2.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 18        | 32.14%  |
| 4096  | 12        | 21.43%  |
| 16384 | 11        | 19.64%  |
| 2048  | 7         | 12.5%   |
| 32768 | 5         | 8.93%   |
| 1024  | 3         | 5.36%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 10        | 18.52%  |
| 3200    | 9         | 16.67%  |
| 2667    | 8         | 14.81%  |
| 3600    | 3         | 5.56%   |
| 1333    | 3         | 5.56%   |
| 667     | 3         | 5.56%   |
| 2400    | 2         | 3.7%    |
| 2133    | 2         | 3.7%    |
| 4267    | 1         | 1.85%   |
| 4199    | 1         | 1.85%   |
| 3733    | 1         | 1.85%   |
| 3400    | 1         | 1.85%   |
| 3007    | 1         | 1.85%   |
| 3000    | 1         | 1.85%   |
| 2934    | 1         | 1.85%   |
| 2933    | 1         | 1.85%   |
| 1867    | 1         | 1.85%   |
| 1334    | 1         | 1.85%   |
| 1067    | 1         | 1.85%   |
| 1066    | 1         | 1.85%   |
| 800     | 1         | 1.85%   |
| Unknown | 1         | 1.85%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 2         | 28.57%  |
| Samsung Electronics | 1         | 14.29%  |
| Prolific Technology | 1         | 14.29%  |
| Kyocera             | 1         | 14.29%  |
| Hewlett-Packard     | 1         | 14.29%  |
| Canon               | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Samsung SCX-4200 series       | 1         | 14.29%  |
| Prolific PL2305 Parallel Port | 1         | 14.29%  |
| Kyocera FS-1030D printer      | 1         | 14.29%  |
| HP ENVY 4500 series           | 1         | 14.29%  |
| Canon CanoScan LiDE 300       | 1         | 14.29%  |
| Brother Printer               | 1         | 14.29%  |
| Brother HL-L3210CW series     | 1         | 14.29%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 1         | 50%     |
| Canon CanoScan LiDE 210       | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 8         | 17.02%  |
| Logitech                               | 6         | 12.77%  |
| Acer                                   | 5         | 10.64%  |
| Sunplus Innovation Technology          | 4         | 8.51%   |
| Realtek Semiconductor                  | 4         | 8.51%   |
| Quanta                                 | 3         | 6.38%   |
| Microdia                               | 3         | 6.38%   |
| IMC Networks                           | 3         | 6.38%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 6.38%   |
| Z-Star Microelectronics                | 1         | 2.13%   |
| Syntek                                 | 1         | 2.13%   |
| Silicon Motion                         | 1         | 2.13%   |
| Ricoh                                  | 1         | 2.13%   |
| Luxvisions Innotech Limited            | 1         | 2.13%   |
| Lite-On Technology                     | 1         | 2.13%   |
| Creative Technology                    | 1         | 2.13%   |
| ALi                                    | 1         | 2.13%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                | 3         | 6.25%   |
| Sunplus HD WebCam                                                        | 2         | 4.17%   |
| Microdia Integrated_Webcam_HD                                            | 2         | 4.17%   |
| Logitech Webcam C270                                                     | 2         | 4.17%   |
| Logitech B525 HD Webcam                                                  | 2         | 4.17%   |
| Z-Star Venus USB2.0 Camera                                               | 1         | 2.08%   |
| Syntek Lenovo EasyCamera                                                 | 1         | 2.08%   |
| Sunplus Integrated_Webcam_HD                                             | 1         | 2.08%   |
| Sunplus 1.3M HD WebCam                                                   | 1         | 2.08%   |
| Silicon Motion WebCam SC-13HDN10939N                                     | 1         | 2.08%   |
| Ricoh Sony Vaio Integrated Webcam                                        | 1         | 2.08%   |
| Realtek USB Camera                                                       | 1         | 2.08%   |
| Realtek Lenovo EasyCamera                                                | 1         | 2.08%   |
| Realtek Laptop_Integrated_Webcam_HD                                      | 1         | 2.08%   |
| Realtek Integrated_Webcam_HD                                             | 1         | 2.08%   |
| Realtek Integrated Webcam HD                                             | 1         | 2.08%   |
| Quanta HP Wide Vision HD Camera                                          | 1         | 2.08%   |
| Quanta HP TrueVision HD Camera                                           | 1         | 2.08%   |
| Quanta HD User Facing                                                    | 1         | 2.08%   |
| Microdia Laptop_Integrated_Webcam_0.3M                                   | 1         | 2.08%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                      | 1         | 2.08%   |
| Logitech Webcam C250                                                     | 1         | 2.08%   |
| Logitech HD Pro Webcam C920                                              | 1         | 2.08%   |
| Lite-On Integrated Camera                                                | 1         | 2.08%   |
| IMC Networks USB2.0 VGA UVC WebCam                                       | 1         | 2.08%   |
| IMC Networks USB2.0 UVC HD Webcam                                        | 1         | 2.08%   |
| IMC Networks Integrated Camera                                           | 1         | 2.08%   |
| Creative Live! Cam Sync 1080p                                            | 1         | 2.08%   |
| Chicony VGA 24fps UVC Webcam                                             | 1         | 2.08%   |
| Chicony USB2.0 Camera                                                    | 1         | 2.08%   |
| Chicony ThinkPad T490 Webcam                                             | 1         | 2.08%   |
| Chicony HP Webcam                                                        | 1         | 2.08%   |
| Chicony EasyCamera                                                       | 1         | 2.08%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                            | 1         | 2.08%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 1         | 2.08%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera                         | 1         | 2.08%   |
| ALi Gateway Webcam                                                       | 1         | 2.08%   |
| Acer ThinkPad P50 Integrated Camera                                      | 1         | 2.08%   |
| Acer Integrated Camera                                                   | 1         | 2.08%   |
| Acer HD Webcam                                                           | 1         | 2.08%   |
| Acer BisonCam,NB Pro                                                     | 1         | 2.08%   |
| Acer BisonCam, NB Pro                                                    | 1         | 2.08%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 36.36%  |
| Synaptics                  | 4         | 36.36%  |
| Upek                       | 1         | 9.09%   |
| Shenzhen Goodix Technology | 1         | 9.09%   |
| AuthenTec                  | 1         | 9.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor           | 2         | 18.18%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 2         | 18.18%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 9.09%   |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 9.09%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 9.09%   |
| Synaptics  WBDI                                        | 1         | 9.09%   |
| Shenzhen Goodix  Fingerprint Device                    | 1         | 9.09%   |
| AuthenTec AES1660 Fingerprint Sensor                   | 1         | 9.09%   |
| Unknown                                                | 1         | 9.09%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 2         | 40%     |
| O2 Micro              | 1         | 20%     |
| Gemalto (was Gemplus) | 1         | 20%     |
| Broadcom              | 1         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader               | 2         | 40%     |
| O2 Micro OZ776 CCID Smartcard Reader              | 1         | 20%     |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 1         | 20%     |
| Broadcom BCM5880 Secure Applications Processor    | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 57        | 71.25%  |
| 1     | 18        | 22.5%   |
| 2     | 5         | 6.25%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 11        | 39.29%  |
| Chipcard                 | 6         | 21.43%  |
| Graphics card            | 5         | 17.86%  |
| Net/wireless             | 3         | 10.71%  |
| Communication controller | 1         | 3.57%   |
| Camera                   | 1         | 3.57%   |
| Bluetooth                | 1         | 3.57%   |

