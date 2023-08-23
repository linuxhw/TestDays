Linux in Poland - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Poland.

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

Total: 4435

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | GL552VW                     | [6986ca63da](https://linux-hardware.org/?probe=6986ca63da) | Aug 12, 2023 |
| Fujitsu       | FMVA0800C                   | [1dae7b170b](https://linux-hardware.org/?probe=1dae7b170b) | Aug 12, 2023 |
| HP            | Pavilion dv7                | [7e4a63e58c](https://linux-hardware.org/?probe=7e4a63e58c) | Aug 12, 2023 |
| HP            | Pavilion dv7                | [fc48a936d7](https://linux-hardware.org/?probe=fc48a936d7) | Aug 12, 2023 |
| Lenovo        | ThinkPad T430s 2356LPG      | [97dfe9511b](https://linux-hardware.org/?probe=97dfe9511b) | Aug 10, 2023 |
| Google        | Kip                         | [553df8dcdc](https://linux-hardware.org/?probe=553df8dcdc) | Aug 10, 2023 |
| Dell          | Latitude E6540              | [758d587fbb](https://linux-hardware.org/?probe=758d587fbb) | Aug 10, 2023 |
| HP            | ProBook 450 G6              | [c205f19d5e](https://linux-hardware.org/?probe=c205f19d5e) | Aug 09, 2023 |
| HP            | EliteBook 845 G9            | [1ff8d81e4e](https://linux-hardware.org/?probe=1ff8d81e4e) | Aug 09, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [81411c1db8](https://linux-hardware.org/?probe=81411c1db8) | Aug 08, 2023 |
| Acer          | Aspire 5732Z                | [5a0ee0b4c0](https://linux-hardware.org/?probe=5a0ee0b4c0) | Aug 08, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [f6b63d9967](https://linux-hardware.org/?probe=f6b63d9967) | Aug 08, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | [9094c29548](https://linux-hardware.org/?probe=9094c29548) | Aug 07, 2023 |
| HP            | ZBook 15 G3                 | [068b8c5a6f](https://linux-hardware.org/?probe=068b8c5a6f) | Aug 07, 2023 |
| Dell          | Vostro 5471                 | [f4beee823e](https://linux-hardware.org/?probe=f4beee823e) | Aug 07, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [08b395f8d6](https://linux-hardware.org/?probe=08b395f8d6) | Aug 07, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | [270c9a3ea0](https://linux-hardware.org/?probe=270c9a3ea0) | Aug 06, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | [f77c465da0](https://linux-hardware.org/?probe=f77c465da0) | Aug 06, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | [db5a797fc0](https://linux-hardware.org/?probe=db5a797fc0) | Aug 06, 2023 |
| ASUSTek       | ROG Strix G731GU_GL731GU    | [b3c77ee42f](https://linux-hardware.org/?probe=b3c77ee42f) | Aug 05, 2023 |
| Dell          | Latitude 5421               | [d01013b679](https://linux-hardware.org/?probe=d01013b679) | Aug 05, 2023 |
| Dell          | Latitude 5421               | [5dfde4e6ac](https://linux-hardware.org/?probe=5dfde4e6ac) | Aug 05, 2023 |
| Gigabyte      | RC14UD                      | [6ad0758102](https://linux-hardware.org/?probe=6ad0758102) | Aug 04, 2023 |
| Lenovo        | G50-45 80E3                 | [34edcb7dae](https://linux-hardware.org/?probe=34edcb7dae) | Aug 04, 2023 |
| Dell          | Vostro 15 3510              | [bd994e4cc6](https://linux-hardware.org/?probe=bd994e4cc6) | Aug 04, 2023 |
| Dell          | Vostro 15 3510              | [ab2f3b8c7b](https://linux-hardware.org/?probe=ab2f3b8c7b) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [8036065591](https://linux-hardware.org/?probe=8036065591) | Aug 03, 2023 |
| Dell          | Inspiron 13-5368            | [695e2dec6b](https://linux-hardware.org/?probe=695e2dec6b) | Aug 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c2c27c3268](https://linux-hardware.org/?probe=c2c27c3268) | Aug 01, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [762d07665a](https://linux-hardware.org/?probe=762d07665a) | Jul 31, 2023 |
| ASUSTek       | E200HA                      | [6ab93e7940](https://linux-hardware.org/?probe=6ab93e7940) | Jul 30, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [60cfcb00e9](https://linux-hardware.org/?probe=60cfcb00e9) | Jul 30, 2023 |
| Google        | Relm                        | [1c8bd1f9dd](https://linux-hardware.org/?probe=1c8bd1f9dd) | Jul 30, 2023 |
| Lenovo        | ThinkPad A285 20MXS0AE00    | [a6ada51a02](https://linux-hardware.org/?probe=a6ada51a02) | Jul 29, 2023 |
| Dell          | Latitude E7240              | [b794bcdde6](https://linux-hardware.org/?probe=b794bcdde6) | Jul 29, 2023 |
| Dell          | Inspiron 7559               | [fad00d6412](https://linux-hardware.org/?probe=fad00d6412) | Jul 29, 2023 |
| ASUSTek       | X555LJ                      | [690e49362b](https://linux-hardware.org/?probe=690e49362b) | Jul 28, 2023 |
| HP            | Pavilion Gaming Laptop      | [b277fcda26](https://linux-hardware.org/?probe=b277fcda26) | Jul 28, 2023 |
| Toshiba       | Satellite C50D-A-11G        | [b67508b754](https://linux-hardware.org/?probe=b67508b754) | Jul 27, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [e882db39b8](https://linux-hardware.org/?probe=e882db39b8) | Jul 27, 2023 |
| Dell          | Inspiron 3583               | [e235fb3a23](https://linux-hardware.org/?probe=e235fb3a23) | Jul 26, 2023 |
| Dell          | Latitude 9420               | [03c3ca79c4](https://linux-hardware.org/?probe=03c3ca79c4) | Jul 26, 2023 |
| Dell          | XPS 15 9520                 | [24f65961ef](https://linux-hardware.org/?probe=24f65961ef) | Jul 26, 2023 |
| Apple         | MacBookPro9,2               | [af0355313e](https://linux-hardware.org/?probe=af0355313e) | Jul 25, 2023 |
| Lenovo        | ThinkPad L470 20J5S01S00    | [346055ca33](https://linux-hardware.org/?probe=346055ca33) | Jul 25, 2023 |
| Dell          | Latitude 3190               | [b1730d834d](https://linux-hardware.org/?probe=b1730d834d) | Jul 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [412bc51f72](https://linux-hardware.org/?probe=412bc51f72) | Jul 24, 2023 |
| Timi          | TM1701                      | [eb1246586e](https://linux-hardware.org/?probe=eb1246586e) | Jul 24, 2023 |
| ASUSTek       | F7E                         | [2aef1cc2c4](https://linux-hardware.org/?probe=2aef1cc2c4) | Jul 24, 2023 |
| Timi          | TM1701                      | [17fefbecba](https://linux-hardware.org/?probe=17fefbecba) | Jul 24, 2023 |
| Lenovo        | G500s 20245                 | [fbfa8af465](https://linux-hardware.org/?probe=fbfa8af465) | Jul 24, 2023 |
| Acer          | Aspire A715-74G             | [b27862dc34](https://linux-hardware.org/?probe=b27862dc34) | Jul 24, 2023 |
| ASUSTek       | X555LD                      | [732fe69d59](https://linux-hardware.org/?probe=732fe69d59) | Jul 23, 2023 |
| HUAWEI        | HVY-WXX9                    | [44958ef86b](https://linux-hardware.org/?probe=44958ef86b) | Jul 23, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [10e8c0d4ad](https://linux-hardware.org/?probe=10e8c0d4ad) | Jul 23, 2023 |
| Google        | Snappy                      | [a3e6774e43](https://linux-hardware.org/?probe=a3e6774e43) | Jul 23, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [467cc30f89](https://linux-hardware.org/?probe=467cc30f89) | Jul 22, 2023 |
| MSI           | PR601/VR603                 | [b982476d84](https://linux-hardware.org/?probe=b982476d84) | Jul 21, 2023 |
| Razer         | Blade 15 Base Model (Mid... | [d2d53e7406](https://linux-hardware.org/?probe=d2d53e7406) | Jul 21, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [fcdb1fdeed](https://linux-hardware.org/?probe=fcdb1fdeed) | Jul 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [0bd52b9adf](https://linux-hardware.org/?probe=0bd52b9adf) | Jul 20, 2023 |
| Dell          | Latitude 9420               | [750f80b869](https://linux-hardware.org/?probe=750f80b869) | Jul 19, 2023 |
| Dell          | Latitude 9420               | [a4ba4bfde1](https://linux-hardware.org/?probe=a4ba4bfde1) | Jul 19, 2023 |
| Dell          | Latitude E6400              | [7e9ef12f0d](https://linux-hardware.org/?probe=7e9ef12f0d) | Jul 19, 2023 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | [17c6866da9](https://linux-hardware.org/?probe=17c6866da9) | Jul 18, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [35d510901b](https://linux-hardware.org/?probe=35d510901b) | Jul 18, 2023 |
| Teclast       | F6 Pro                      | [d9f3a038e0](https://linux-hardware.org/?probe=d9f3a038e0) | Jul 17, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20STS... | [18f41b2be6](https://linux-hardware.org/?probe=18f41b2be6) | Jul 17, 2023 |
| Lenovo        | ThinkPad X240 20AMS07T00    | [0c460a8007](https://linux-hardware.org/?probe=0c460a8007) | Jul 17, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [111c0b962d](https://linux-hardware.org/?probe=111c0b962d) | Jul 16, 2023 |
| Dell          | Latitude E6440              | [4e40dc49f3](https://linux-hardware.org/?probe=4e40dc49f3) | Jul 16, 2023 |
| HP            | Pavilion HDX9200            | [d893c8a2d1](https://linux-hardware.org/?probe=d893c8a2d1) | Jul 16, 2023 |
| Dell          | Latitude E6330              | [6adb67344f](https://linux-hardware.org/?probe=6adb67344f) | Jul 15, 2023 |
| Lenovo        | ThinkPad T495 20NKS0T101    | [6154504eac](https://linux-hardware.org/?probe=6154504eac) | Jul 15, 2023 |
| ASUSTek       | 1011PX                      | [d91fe40195](https://linux-hardware.org/?probe=d91fe40195) | Jul 15, 2023 |
| MSI           | GE70 2QD                    | [f8ddf3a3a3](https://linux-hardware.org/?probe=f8ddf3a3a3) | Jul 15, 2023 |
| Lenovo        | ThinkPad X240 20AMS07T00    | [8ce6db48b9](https://linux-hardware.org/?probe=8ce6db48b9) | Jul 15, 2023 |
| Lenovo        | ThinkPad T470 20HES0FA03    | [f416cb06c2](https://linux-hardware.org/?probe=f416cb06c2) | Jul 14, 2023 |
| Acer          | Aspire E5-576G              | [0856b48ae7](https://linux-hardware.org/?probe=0856b48ae7) | Jul 13, 2023 |
| Dell          | Latitude E6330              | [58ec0684cd](https://linux-hardware.org/?probe=58ec0684cd) | Jul 13, 2023 |
| Toshiba       | Satellite S75-B             | [ee71e28c8f](https://linux-hardware.org/?probe=ee71e28c8f) | Jul 12, 2023 |
| Lenovo        | ThinkPad T470s 20HGS01A0... | [54e51170a1](https://linux-hardware.org/?probe=54e51170a1) | Jul 11, 2023 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [a78428eb21](https://linux-hardware.org/?probe=a78428eb21) | Jul 11, 2023 |
| Dell          | Inspiron 5748               | [ec95cc29fd](https://linux-hardware.org/?probe=ec95cc29fd) | Jul 11, 2023 |
| Lenovo        | ThinkPad L470 20J5S01S00    | [ef1f607a84](https://linux-hardware.org/?probe=ef1f607a84) | Jul 11, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [97f39991c3](https://linux-hardware.org/?probe=97f39991c3) | Jul 11, 2023 |
| Dell          | Latitude 3190               | [f067ca0dbf](https://linux-hardware.org/?probe=f067ca0dbf) | Jul 11, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [8b9677cc2a](https://linux-hardware.org/?probe=8b9677cc2a) | Jul 10, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [acdd4ea952](https://linux-hardware.org/?probe=acdd4ea952) | Jul 10, 2023 |
| Lenovo        | ThinkPad Edge 0578P6G       | [e79fbdad2d](https://linux-hardware.org/?probe=e79fbdad2d) | Jul 10, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | [d4ca6c4f81](https://linux-hardware.org/?probe=d4ca6c4f81) | Jul 10, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [215d2135b3](https://linux-hardware.org/?probe=215d2135b3) | Jul 09, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [42aaaa0acb](https://linux-hardware.org/?probe=42aaaa0acb) | Jul 09, 2023 |
| HP            | Compaq Presario CQ60        | [60e671ef49](https://linux-hardware.org/?probe=60e671ef49) | Jul 09, 2023 |
| ASUSTek       | X555LJ                      | [2dfec77944](https://linux-hardware.org/?probe=2dfec77944) | Jul 09, 2023 |
| HP            | Laptop 14s-fq0xxx           | [92feea0533](https://linux-hardware.org/?probe=92feea0533) | Jul 08, 2023 |
| HP            | Laptop 14s-fq0xxx           | [2287c62944](https://linux-hardware.org/?probe=2287c62944) | Jul 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [9b8e16f852](https://linux-hardware.org/?probe=9b8e16f852) | Jul 08, 2023 |
| Toshiba       | PORTEGE M700                | [6a67dec7ab](https://linux-hardware.org/?probe=6a67dec7ab) | Jul 08, 2023 |
| Toshiba       | PORTEGE M700                | [b735ddd9a6](https://linux-hardware.org/?probe=b735ddd9a6) | Jul 08, 2023 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | [54ac55c49e](https://linux-hardware.org/?probe=54ac55c49e) | Jul 07, 2023 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | [296474a1b1](https://linux-hardware.org/?probe=296474a1b1) | Jul 07, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | [e4bb31a52c](https://linux-hardware.org/?probe=e4bb31a52c) | Jul 07, 2023 |
| HP            | 255 G7 Notebook PC          | [23a6105e01](https://linux-hardware.org/?probe=23a6105e01) | Jul 06, 2023 |
| Dell          | Latitude 7420               | [44c51e8365](https://linux-hardware.org/?probe=44c51e8365) | Jul 05, 2023 |
| AAEON         | AEC-6637                    | [53f8e37edc](https://linux-hardware.org/?probe=53f8e37edc) | Jul 05, 2023 |
| AAEON         | AEC-6637                    | [a105861e1d](https://linux-hardware.org/?probe=a105861e1d) | Jul 05, 2023 |
| Dell          | Latitude 7420               | [9eae2c6ad4](https://linux-hardware.org/?probe=9eae2c6ad4) | Jul 05, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [3e5dc0c313](https://linux-hardware.org/?probe=3e5dc0c313) | Jul 05, 2023 |
| HP            | 550                         | [f788d05211](https://linux-hardware.org/?probe=f788d05211) | Jul 05, 2023 |
| HP            | 650                         | [a3077996ad](https://linux-hardware.org/?probe=a3077996ad) | Jul 05, 2023 |
| Lenovo        | G500s 20245                 | [1a32b23618](https://linux-hardware.org/?probe=1a32b23618) | Jul 04, 2023 |
| Dell          | Latitude 3190               | [b895b6dced](https://linux-hardware.org/?probe=b895b6dced) | Jul 04, 2023 |
| Lenovo        | Yoga 900-13ISK 80MK         | [75a8750d34](https://linux-hardware.org/?probe=75a8750d34) | Jul 03, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [f567c6c550](https://linux-hardware.org/?probe=f567c6c550) | Jul 03, 2023 |
| Google        | Relm                        | [ef72648bb6](https://linux-hardware.org/?probe=ef72648bb6) | Jul 02, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [3f2c5d0eb2](https://linux-hardware.org/?probe=3f2c5d0eb2) | Jul 01, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [f923d36676](https://linux-hardware.org/?probe=f923d36676) | Jul 01, 2023 |
| Dell          | Inspiron 7720               | [9d8f40247e](https://linux-hardware.org/?probe=9d8f40247e) | Jul 01, 2023 |
| Packard Be... | EasyNote TSX66HR            | [96253a3da8](https://linux-hardware.org/?probe=96253a3da8) | Jul 01, 2023 |
| HP            | EliteBook 820 G2            | [c99236ef84](https://linux-hardware.org/?probe=c99236ef84) | Jun 30, 2023 |
| Lenovo        | ThinkPad T430s 23554L7      | [501b0860c8](https://linux-hardware.org/?probe=501b0860c8) | Jun 30, 2023 |
| Dell          | Latitude E6540              | [a526c901ee](https://linux-hardware.org/?probe=a526c901ee) | Jun 30, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [287d7d6f60](https://linux-hardware.org/?probe=287d7d6f60) | Jun 29, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [723de914e2](https://linux-hardware.org/?probe=723de914e2) | Jun 29, 2023 |
| Acer          | Swift SF314-43              | [363067c171](https://linux-hardware.org/?probe=363067c171) | Jun 29, 2023 |
| Dell          | XPS 15 9570                 | [34df27504f](https://linux-hardware.org/?probe=34df27504f) | Jun 28, 2023 |
| Apple         | MacBookPro7,1               | [5a82f91882](https://linux-hardware.org/?probe=5a82f91882) | Jun 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | [9d6748ef56](https://linux-hardware.org/?probe=9d6748ef56) | Jun 28, 2023 |
| Toshiba       | TECRA R950                  | [cab34ec3dc](https://linux-hardware.org/?probe=cab34ec3dc) | Jun 28, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [ff919014cd](https://linux-hardware.org/?probe=ff919014cd) | Jun 28, 2023 |
| ASUSTek       | K54C                        | [4152d1fcff](https://linux-hardware.org/?probe=4152d1fcff) | Jun 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | [64433a8783](https://linux-hardware.org/?probe=64433a8783) | Jun 27, 2023 |
| Lenovo        | G500s 20245                 | [1aa332e26f](https://linux-hardware.org/?probe=1aa332e26f) | Jun 27, 2023 |
| Valve         | Jupiter                     | [0817dd25ff](https://linux-hardware.org/?probe=0817dd25ff) | Jun 27, 2023 |
| Dell          | Latitude 3190               | [5f68b5235f](https://linux-hardware.org/?probe=5f68b5235f) | Jun 27, 2023 |
| Toshiba       | TECRA R950                  | [f02bb9a43a](https://linux-hardware.org/?probe=f02bb9a43a) | Jun 26, 2023 |
| HP            | 255 G5 Notebook PC          | [cad891675f](https://linux-hardware.org/?probe=cad891675f) | Jun 25, 2023 |
| eMachines     | eME732ZG                    | [4e1d6873ff](https://linux-hardware.org/?probe=4e1d6873ff) | Jun 24, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | [0ec7fedf29](https://linux-hardware.org/?probe=0ec7fedf29) | Jun 24, 2023 |
| Packard Be... | EasyNote TK85               | [314e344780](https://linux-hardware.org/?probe=314e344780) | Jun 24, 2023 |
| Lenovo        | ThinkPad T430 2347BS4       | [a8a9689ea6](https://linux-hardware.org/?probe=a8a9689ea6) | Jun 24, 2023 |
| Lenovo        | ThinkPad L390 20NSS04400    | [feced26491](https://linux-hardware.org/?probe=feced26491) | Jun 23, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [c75670186a](https://linux-hardware.org/?probe=c75670186a) | Jun 23, 2023 |
| Lenovo        | G500s 20245                 | [17db397c48](https://linux-hardware.org/?probe=17db397c48) | Jun 22, 2023 |
| Toshiba       | Satellite Pro C70-B         | [f96a1a3552](https://linux-hardware.org/?probe=f96a1a3552) | Jun 21, 2023 |
| Lenovo        | ThinkPad L470 20J5S01S00    | [5de086be7a](https://linux-hardware.org/?probe=5de086be7a) | Jun 21, 2023 |
| Toshiba       | Satellite Pro C70-B         | [52c4c32098](https://linux-hardware.org/?probe=52c4c32098) | Jun 21, 2023 |
| Notebook      | NV4xPZ                      | [873c70b184](https://linux-hardware.org/?probe=873c70b184) | Jun 21, 2023 |
| Lenovo        | B570 HuronRiver Platform    | [b51dda105a](https://linux-hardware.org/?probe=b51dda105a) | Jun 20, 2023 |
| Toshiba       | Satellite A300              | [f37d67a18d](https://linux-hardware.org/?probe=f37d67a18d) | Jun 19, 2023 |
| Razer         | Blade Stealth 13 (Early ... | [e3843be450](https://linux-hardware.org/?probe=e3843be450) | Jun 18, 2023 |
| HP            | Pavilion dv2                | [3f3b0104a4](https://linux-hardware.org/?probe=3f3b0104a4) | Jun 18, 2023 |
| HP            | Notebook                    | [60eebb0602](https://linux-hardware.org/?probe=60eebb0602) | Jun 18, 2023 |
| Dell          | Latitude 5420               | [f7c9224ef1](https://linux-hardware.org/?probe=f7c9224ef1) | Jun 17, 2023 |
| Dell          | Latitude 5420               | [f553a4e5e7](https://linux-hardware.org/?probe=f553a4e5e7) | Jun 17, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [0d47dc3760](https://linux-hardware.org/?probe=0d47dc3760) | Jun 16, 2023 |
| STONE COMP... | NOTCHA-286                  | [9536ebc16b](https://linux-hardware.org/?probe=9536ebc16b) | Jun 16, 2023 |
| Dell          | Latitude E6400              | [7c59595887](https://linux-hardware.org/?probe=7c59595887) | Jun 16, 2023 |
| STONE COMP... | NOTCHA-286                  | [00a14ade70](https://linux-hardware.org/?probe=00a14ade70) | Jun 16, 2023 |
| Valve         | Jupiter                     | [29869b2464](https://linux-hardware.org/?probe=29869b2464) | Jun 15, 2023 |
| Valve         | Jupiter                     | [bdd96d41a7](https://linux-hardware.org/?probe=bdd96d41a7) | Jun 15, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [a1c36c44b1](https://linux-hardware.org/?probe=a1c36c44b1) | Jun 15, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [8d88084588](https://linux-hardware.org/?probe=8d88084588) | Jun 15, 2023 |
| Lenovo        | ThinkPad T490 20N20032US    | [3df7663e0d](https://linux-hardware.org/?probe=3df7663e0d) | Jun 15, 2023 |
| ASUSTek       | K52N                        | [eb2ec7cb3d](https://linux-hardware.org/?probe=eb2ec7cb3d) | Jun 15, 2023 |
| Lenovo        | G500s 20245                 | [8a04ec65f7](https://linux-hardware.org/?probe=8a04ec65f7) | Jun 15, 2023 |
| Acer          | Nitro AN515-44              | [7670492b40](https://linux-hardware.org/?probe=7670492b40) | Jun 15, 2023 |
| Dell          | Latitude 3190               | [2c8d7ef5b6](https://linux-hardware.org/?probe=2c8d7ef5b6) | Jun 12, 2023 |
| MSI           | GE62 6QC                    | [5581a5c589](https://linux-hardware.org/?probe=5581a5c589) | Jun 12, 2023 |
| Google        | Blorb                       | [0083999b8a](https://linux-hardware.org/?probe=0083999b8a) | Jun 12, 2023 |
| Google        | Blorb                       | [516c0548dc](https://linux-hardware.org/?probe=516c0548dc) | Jun 12, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [b88dfc7e5c](https://linux-hardware.org/?probe=b88dfc7e5c) | Jun 11, 2023 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [67867c022f](https://linux-hardware.org/?probe=67867c022f) | Jun 11, 2023 |
| Dell          | Precision 5520              | [bcbd324c4b](https://linux-hardware.org/?probe=bcbd324c4b) | Jun 11, 2023 |
| Dell          | Precision 5520              | [ab408edcbd](https://linux-hardware.org/?probe=ab408edcbd) | Jun 11, 2023 |
| HP            | Laptop 15-dw1xxx            | [bfde2cf63d](https://linux-hardware.org/?probe=bfde2cf63d) | Jun 10, 2023 |
| HP            | Laptop 15-dw1xxx            | [7c79725474](https://linux-hardware.org/?probe=7c79725474) | Jun 10, 2023 |
| Lenovo        | Y50-70 20378                | [5e060b53c2](https://linux-hardware.org/?probe=5e060b53c2) | Jun 10, 2023 |
| Lenovo        | Y50-70 20378                | [0d548e314b](https://linux-hardware.org/?probe=0d548e314b) | Jun 10, 2023 |
| Dell          | Inspiron 3583               | [2627421665](https://linux-hardware.org/?probe=2627421665) | Jun 09, 2023 |
| HP            | Stream Laptop 14-ds0xxx     | [fb9e2f9fc8](https://linux-hardware.org/?probe=fb9e2f9fc8) | Jun 09, 2023 |
| Panasonic     | CF-53ASCZGFG                | [39e04925ee](https://linux-hardware.org/?probe=39e04925ee) | Jun 08, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [c98ac6e82c](https://linux-hardware.org/?probe=c98ac6e82c) | Jun 08, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [7879db73f8](https://linux-hardware.org/?probe=7879db73f8) | Jun 08, 2023 |
| Fujitsu       | CELSIUS H730                | [a1e397f4a7](https://linux-hardware.org/?probe=a1e397f4a7) | Jun 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [c142d83ce5](https://linux-hardware.org/?probe=c142d83ce5) | Jun 07, 2023 |
| Toshiba       | Satellite L40               | [16c5f74991](https://linux-hardware.org/?probe=16c5f74991) | Jun 06, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [e56988bf8e](https://linux-hardware.org/?probe=e56988bf8e) | Jun 06, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [fc49284b9f](https://linux-hardware.org/?probe=fc49284b9f) | Jun 06, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [83982c1aa9](https://linux-hardware.org/?probe=83982c1aa9) | Jun 05, 2023 |
| HUAWEI        | KLVL-WXX9                   | [38882f47af](https://linux-hardware.org/?probe=38882f47af) | Jun 05, 2023 |
| Dell          | Latitude 3190               | [fa8eba55f0](https://linux-hardware.org/?probe=fa8eba55f0) | Jun 05, 2023 |
| Acer          | Swift SF314-43              | [969354604a](https://linux-hardware.org/?probe=969354604a) | Jun 04, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [514b3788ed](https://linux-hardware.org/?probe=514b3788ed) | Jun 04, 2023 |
| Dell          | Latitude D620               | [0e1b7f4320](https://linux-hardware.org/?probe=0e1b7f4320) | Jun 03, 2023 |
| Acer          | Aspire A114-31              | [7a760e7ad6](https://linux-hardware.org/?probe=7a760e7ad6) | Jun 03, 2023 |
| Lenovo        | ThinkPad L490 20Q5002DMH    | [6d42b7647b](https://linux-hardware.org/?probe=6d42b7647b) | Jun 02, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [fa4bd41f4b](https://linux-hardware.org/?probe=fa4bd41f4b) | Jun 02, 2023 |
| Lenovo        | B50-70 20384                | [5e3a2796a9](https://linux-hardware.org/?probe=5e3a2796a9) | Jun 01, 2023 |
| HP            | EliteBook 820 G2            | [c9409c532d](https://linux-hardware.org/?probe=c9409c532d) | Jun 01, 2023 |
| Toshiba       | Satellite L650              | [63eb6978fa](https://linux-hardware.org/?probe=63eb6978fa) | Jun 01, 2023 |
| Lenovo        | B51-80 80LM                 | [69429cb044](https://linux-hardware.org/?probe=69429cb044) | Jun 01, 2023 |
| HP            | EliteBook 840 G4            | [46ccbd2d62](https://linux-hardware.org/?probe=46ccbd2d62) | May 31, 2023 |
| HP            | EliteBook 840 G4            | [b90cb27f97](https://linux-hardware.org/?probe=b90cb27f97) | May 31, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [7fed965224](https://linux-hardware.org/?probe=7fed965224) | May 30, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [3b186c07a2](https://linux-hardware.org/?probe=3b186c07a2) | May 30, 2023 |
| Dell          | Latitude 3190               | [fe4a8422c8](https://linux-hardware.org/?probe=fe4a8422c8) | May 29, 2023 |
| Dell          | Latitude 7480               | [9eb2396796](https://linux-hardware.org/?probe=9eb2396796) | May 28, 2023 |
| Dell          | Vostro 1015                 | [c51af54d34](https://linux-hardware.org/?probe=c51af54d34) | May 28, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [c2408a1885](https://linux-hardware.org/?probe=c2408a1885) | May 28, 2023 |
| Lenovo        | ThinkPad T470 20HES0FA03    | [c8c8087ee8](https://linux-hardware.org/?probe=c8c8087ee8) | May 27, 2023 |
| ASUSTek       | X555LN                      | [8f16767017](https://linux-hardware.org/?probe=8f16767017) | May 26, 2023 |
| Dell          | Latitude E5440              | [4a5501c365](https://linux-hardware.org/?probe=4a5501c365) | May 26, 2023 |
| Notebook      | NV4xPZ                      | [750cb90d83](https://linux-hardware.org/?probe=750cb90d83) | May 26, 2023 |
| ASUSTek       | GL552VW                     | [0466edde83](https://linux-hardware.org/?probe=0466edde83) | May 25, 2023 |
| ASUSTek       | X551MA                      | [d72352c0dc](https://linux-hardware.org/?probe=d72352c0dc) | May 25, 2023 |
| HP            | EliteBook 840 G3            | [06333c9c97](https://linux-hardware.org/?probe=06333c9c97) | May 24, 2023 |
| Lenovo        | G500s 20245                 | [dd15a8197e](https://linux-hardware.org/?probe=dd15a8197e) | May 24, 2023 |
| Acer          | Aspire E5-571G              | [6531b22151](https://linux-hardware.org/?probe=6531b22151) | May 24, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [ba72bf9d52](https://linux-hardware.org/?probe=ba72bf9d52) | May 24, 2023 |
| Google        | Snappy                      | [8e9ad9e9d3](https://linux-hardware.org/?probe=8e9ad9e9d3) | May 24, 2023 |
| Lenovo        | Unknown                     | [e7148e7a18](https://linux-hardware.org/?probe=e7148e7a18) | May 23, 2023 |
| HP            | 530                         | [70600de142](https://linux-hardware.org/?probe=70600de142) | May 23, 2023 |
| HP            | EliteBook 840 G5            | [74a0ea4304](https://linux-hardware.org/?probe=74a0ea4304) | May 22, 2023 |
| Dell          | Latitude 3190               | [adf9fc9bdb](https://linux-hardware.org/?probe=adf9fc9bdb) | May 22, 2023 |
| ASUSTek       | K84L                        | [5f14f3b293](https://linux-hardware.org/?probe=5f14f3b293) | May 21, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [03b17bc271](https://linux-hardware.org/?probe=03b17bc271) | May 21, 2023 |
| HP            | Unknown                     | [8894bf0f31](https://linux-hardware.org/?probe=8894bf0f31) | May 21, 2023 |
| Valve         | Jupiter                     | [cf5c419d13](https://linux-hardware.org/?probe=cf5c419d13) | May 20, 2023 |
| Lenovo        | G580 20150                  | [87e60904b9](https://linux-hardware.org/?probe=87e60904b9) | May 20, 2023 |
| Lenovo        | G500s 20245                 | [fc125408b5](https://linux-hardware.org/?probe=fc125408b5) | May 20, 2023 |
| Lenovo        | G580 20150                  | [5acf485cbf](https://linux-hardware.org/?probe=5acf485cbf) | May 20, 2023 |
| Apple         | MacBookAir6,2               | [5a0f8e19ee](https://linux-hardware.org/?probe=5a0f8e19ee) | May 19, 2023 |
| Lenovo        | G500s 20245                 | [8c6b9dc52f](https://linux-hardware.org/?probe=8c6b9dc52f) | May 19, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | [26e8deafbf](https://linux-hardware.org/?probe=26e8deafbf) | May 19, 2023 |
| MSI           | GL75 9SE                    | [7fd4d531c9](https://linux-hardware.org/?probe=7fd4d531c9) | May 18, 2023 |
| HP            | EliteBook 820 G2            | [200610da74](https://linux-hardware.org/?probe=200610da74) | May 17, 2023 |
| Google        | Snappy                      | [d13d8adaf4](https://linux-hardware.org/?probe=d13d8adaf4) | May 17, 2023 |
| Google        | Snappy                      | [0c095bb37a](https://linux-hardware.org/?probe=0c095bb37a) | May 17, 2023 |
| Dell          | Latitude 3190               | [1d867407a6](https://linux-hardware.org/?probe=1d867407a6) | May 15, 2023 |
| Lenovo        | IdeaPad S145-15API 81UT     | [3466945196](https://linux-hardware.org/?probe=3466945196) | May 15, 2023 |
| Lenovo        | B590 20206                  | [70b604bc30](https://linux-hardware.org/?probe=70b604bc30) | May 14, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [5f508efff4](https://linux-hardware.org/?probe=5f508efff4) | May 14, 2023 |
| Lenovo        | B50-70 20384                | [1d3db7b456](https://linux-hardware.org/?probe=1d3db7b456) | May 14, 2023 |
| Fujitsu       | CELSIUS H760                | [5e6faf68dd](https://linux-hardware.org/?probe=5e6faf68dd) | May 14, 2023 |
| Lenovo        | B50-70 20384                | [9459f4eae8](https://linux-hardware.org/?probe=9459f4eae8) | May 14, 2023 |
| Fujitsu       | LIFEBOOK S752               | [97e9f91d90](https://linux-hardware.org/?probe=97e9f91d90) | May 14, 2023 |
| ASUSTek       | K53BR                       | [96a60a2970](https://linux-hardware.org/?probe=96a60a2970) | May 14, 2023 |
| Dell          | Latitude E5530 non-vPro     | [aa5dc9770e](https://linux-hardware.org/?probe=aa5dc9770e) | May 13, 2023 |
| Dell          | Latitude E5530 non-vPro     | [51c66f0f57](https://linux-hardware.org/?probe=51c66f0f57) | May 13, 2023 |
| Lenovo        | G50-30 80G0                 | [31d034ce6e](https://linux-hardware.org/?probe=31d034ce6e) | May 13, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [55abeba9a3](https://linux-hardware.org/?probe=55abeba9a3) | May 13, 2023 |
| Fujitsu       | CELSIUS H760                | [7bb1e2b54e](https://linux-hardware.org/?probe=7bb1e2b54e) | May 13, 2023 |
| Toshiba       | Satellite C55-A-1KZ         | [37c165fa30](https://linux-hardware.org/?probe=37c165fa30) | May 13, 2023 |
| Dell          | Precision 3571              | [9a20dccb42](https://linux-hardware.org/?probe=9a20dccb42) | May 13, 2023 |
| GPU Compan... | GWTN156-11                  | [afb2844cb4](https://linux-hardware.org/?probe=afb2844cb4) | May 13, 2023 |
| Samsung       | RF510/RF410/RF710           | [4820c25349](https://linux-hardware.org/?probe=4820c25349) | May 12, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [6950584e4c](https://linux-hardware.org/?probe=6950584e4c) | May 12, 2023 |
| HP            | ProBook 4535s               | [0d2f9561ce](https://linux-hardware.org/?probe=0d2f9561ce) | May 12, 2023 |
| Dell          | Latitude 7390               | [cbd8c5fdbe](https://linux-hardware.org/?probe=cbd8c5fdbe) | May 12, 2023 |
| Dell          | Latitude 7390               | [5677bfdac5](https://linux-hardware.org/?probe=5677bfdac5) | May 12, 2023 |
| Toshiba       | Satellite L40               | [9945f20a3a](https://linux-hardware.org/?probe=9945f20a3a) | May 11, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [4ca3ad7158](https://linux-hardware.org/?probe=4ca3ad7158) | May 11, 2023 |
| Valve         | Jupiter                     | [5bfb32e683](https://linux-hardware.org/?probe=5bfb32e683) | May 11, 2023 |
| HP            | EliteBook 745 G3            | [256ad0c4d8](https://linux-hardware.org/?probe=256ad0c4d8) | May 11, 2023 |
| Lenovo        | ThinkPad L470 20J5S01S00    | [8886b2b825](https://linux-hardware.org/?probe=8886b2b825) | May 10, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [d764690667](https://linux-hardware.org/?probe=d764690667) | May 10, 2023 |
| HP            | Laptop 15s-eq0xxx           | [58000b3a57](https://linux-hardware.org/?probe=58000b3a57) | May 09, 2023 |
| Fujitsu Si... | AMILO Pro Series V3525      | [6272f76b0b](https://linux-hardware.org/?probe=6272f76b0b) | May 09, 2023 |
| HP            | EliteBook 840 14 inch G9... | [a3e5adab46](https://linux-hardware.org/?probe=a3e5adab46) | May 08, 2023 |
| Fujitsu Si... | AMILO Pro Series V3525      | [e3cc11d5e4](https://linux-hardware.org/?probe=e3cc11d5e4) | May 08, 2023 |
| Dell          | Latitude 3190               | [fb4df1325b](https://linux-hardware.org/?probe=fb4df1325b) | May 08, 2023 |
| Valve         | Jupiter                     | [e6397e7f9f](https://linux-hardware.org/?probe=e6397e7f9f) | May 08, 2023 |
| HP            | 15                          | [162a4b16ae](https://linux-hardware.org/?probe=162a4b16ae) | May 08, 2023 |
| Dell          | Latitude 5520               | [4d8ef45cbc](https://linux-hardware.org/?probe=4d8ef45cbc) | May 07, 2023 |
| Acer          | TravelMate 6592             | [d655aad3c5](https://linux-hardware.org/?probe=d655aad3c5) | May 07, 2023 |
| Dell          | Latitude 5290               | [255da608b8](https://linux-hardware.org/?probe=255da608b8) | May 07, 2023 |
| ASUSTek       | Zenbook UM6702RC_RM6702R... | [3cf83f50f0](https://linux-hardware.org/?probe=3cf83f50f0) | May 07, 2023 |
| Toshiba       | Satellite L300D             | [0e2dfb1c74](https://linux-hardware.org/?probe=0e2dfb1c74) | May 06, 2023 |
| ASUSTek       | K75DE                       | [d99045be1c](https://linux-hardware.org/?probe=d99045be1c) | May 05, 2023 |
| Dell          | Inspiron 5770               | [c545869ec5](https://linux-hardware.org/?probe=c545869ec5) | May 05, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [51ae873492](https://linux-hardware.org/?probe=51ae873492) | May 04, 2023 |
| HP            | EliteBook 8540p             | [11b0a5baa1](https://linux-hardware.org/?probe=11b0a5baa1) | May 04, 2023 |
| Google        | Meep                        | [1e5e0e6673](https://linux-hardware.org/?probe=1e5e0e6673) | May 04, 2023 |
| Dell          | Latitude 5490               | [20c5ad2ee2](https://linux-hardware.org/?probe=20c5ad2ee2) | May 03, 2023 |
| Dell          | Latitude E6410              | [8830853258](https://linux-hardware.org/?probe=8830853258) | May 03, 2023 |
| Packard Be... | EasyNote TE69BM             | [fc905a42fb](https://linux-hardware.org/?probe=fc905a42fb) | May 03, 2023 |
| Lenovo        | G500s 20245                 | [560b69d616](https://linux-hardware.org/?probe=560b69d616) | May 03, 2023 |
| Packard Be... | EasyNote LJ65               | [795672236a](https://linux-hardware.org/?probe=795672236a) | May 02, 2023 |
| Packard Be... | EasyNote LJ65               | [77860cab79](https://linux-hardware.org/?probe=77860cab79) | May 02, 2023 |
| Dell          | Vostro 3550                 | [a644bc676e](https://linux-hardware.org/?probe=a644bc676e) | May 01, 2023 |
| HP            | Compaq 6910p                | [a697e756f5](https://linux-hardware.org/?probe=a697e756f5) | May 01, 2023 |
| Dell          | Latitude 3190               | [59c654b2ec](https://linux-hardware.org/?probe=59c654b2ec) | May 01, 2023 |
| Dell          | XPS 15 9500                 | [93fef964a7](https://linux-hardware.org/?probe=93fef964a7) | Apr 30, 2023 |
| Dell          | Latitude XT2                | [3cfd979c60](https://linux-hardware.org/?probe=3cfd979c60) | Apr 30, 2023 |
| Acer          | AO725                       | [03e5f661fb](https://linux-hardware.org/?probe=03e5f661fb) | Apr 30, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [408aa18a63](https://linux-hardware.org/?probe=408aa18a63) | Apr 30, 2023 |
| Lenovo        | IdeaPad L340-17API 81LY     | [44c60dcec2](https://linux-hardware.org/?probe=44c60dcec2) | Apr 30, 2023 |
| Dell          | Inspiron MXC061             | [2d1ab773dd](https://linux-hardware.org/?probe=2d1ab773dd) | Apr 30, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [7c378d88a2](https://linux-hardware.org/?probe=7c378d88a2) | Apr 29, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [f502c40867](https://linux-hardware.org/?probe=f502c40867) | Apr 29, 2023 |
| Acer          | Aspire V5-552G              | [07c58a5169](https://linux-hardware.org/?probe=07c58a5169) | Apr 29, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [a8adc86550](https://linux-hardware.org/?probe=a8adc86550) | Apr 28, 2023 |
| Acer          | Aspire VX5-591G             | [2461a8058f](https://linux-hardware.org/?probe=2461a8058f) | Apr 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | [f1290d4846](https://linux-hardware.org/?probe=f1290d4846) | Apr 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [2474e8e580](https://linux-hardware.org/?probe=2474e8e580) | Apr 27, 2023 |
| HP            | 255 G8 Notebook PC          | [adb8f367ea](https://linux-hardware.org/?probe=adb8f367ea) | Apr 27, 2023 |
| HP            | EliteBook 2560p             | [23b5cbfb33](https://linux-hardware.org/?probe=23b5cbfb33) | Apr 27, 2023 |
| Acer          | Aspire 7250                 | [8e8e082e3d](https://linux-hardware.org/?probe=8e8e082e3d) | Apr 26, 2023 |
| Acer          | Aspire 5737Z                | [121eda50b8](https://linux-hardware.org/?probe=121eda50b8) | Apr 26, 2023 |
| HP            | EliteBook 840 G2            | [a3065a1b59](https://linux-hardware.org/?probe=a3065a1b59) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [d8088982c3](https://linux-hardware.org/?probe=d8088982c3) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [4cffa55fb1](https://linux-hardware.org/?probe=4cffa55fb1) | Apr 26, 2023 |
| HP            | Laptop 15-db1xxx            | [e6380a2186](https://linux-hardware.org/?probe=e6380a2186) | Apr 26, 2023 |
| HP            | Laptop 15                   | [34a2ebf6a1](https://linux-hardware.org/?probe=34a2ebf6a1) | Apr 26, 2023 |
| HP            | Laptop 15-db1xxx            | [872138980a](https://linux-hardware.org/?probe=872138980a) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [2122bd37a5](https://linux-hardware.org/?probe=2122bd37a5) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [af7b14d259](https://linux-hardware.org/?probe=af7b14d259) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [7fbd802154](https://linux-hardware.org/?probe=7fbd802154) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [ffe6065419](https://linux-hardware.org/?probe=ffe6065419) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [94ddc76aae](https://linux-hardware.org/?probe=94ddc76aae) | Apr 26, 2023 |
| Lenovo        | ThinkPad X200 7459KM3       | [cbea785e27](https://linux-hardware.org/?probe=cbea785e27) | Apr 25, 2023 |
| Dell          | Latitude E5470              | [3eb401d939](https://linux-hardware.org/?probe=3eb401d939) | Apr 25, 2023 |
| Dell          | Latitude E5470              | [37fabb89aa](https://linux-hardware.org/?probe=37fabb89aa) | Apr 25, 2023 |
| Lenovo        | G700                        | [75ee4cf99d](https://linux-hardware.org/?probe=75ee4cf99d) | Apr 24, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [9649423c20](https://linux-hardware.org/?probe=9649423c20) | Apr 24, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [af486ae4ae](https://linux-hardware.org/?probe=af486ae4ae) | Apr 24, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [de3ad583ab](https://linux-hardware.org/?probe=de3ad583ab) | Apr 24, 2023 |
| Medion        | X681X                       | [d72837ad07](https://linux-hardware.org/?probe=d72837ad07) | Apr 24, 2023 |
| HP            | EliteBook 650 15.6 inch ... | [78686e5784](https://linux-hardware.org/?probe=78686e5784) | Apr 24, 2023 |
| Dell          | Vostro 5402                 | [b6cb9c9140](https://linux-hardware.org/?probe=b6cb9c9140) | Apr 24, 2023 |
| Dell          | Latitude 3190               | [2c21a51932](https://linux-hardware.org/?probe=2c21a51932) | Apr 24, 2023 |
| Samsung       | R510/P510                   | [4b58936ad7](https://linux-hardware.org/?probe=4b58936ad7) | Apr 23, 2023 |
| Dell          | Inspiron 5559               | [e959cc70fa](https://linux-hardware.org/?probe=e959cc70fa) | Apr 23, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | [18306b3af6](https://linux-hardware.org/?probe=18306b3af6) | Apr 23, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | [bee909cfcd](https://linux-hardware.org/?probe=bee909cfcd) | Apr 23, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | [c101faa12e](https://linux-hardware.org/?probe=c101faa12e) | Apr 23, 2023 |
| Lenovo        | Z51-70 80K6                 | [3d51a6183c](https://linux-hardware.org/?probe=3d51a6183c) | Apr 23, 2023 |
| Dell          | Precision 7550              | [31830a82c6](https://linux-hardware.org/?probe=31830a82c6) | Apr 22, 2023 |
| Dell          | Latitude D620               | [7b0c5ec6f2](https://linux-hardware.org/?probe=7b0c5ec6f2) | Apr 22, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [510237facd](https://linux-hardware.org/?probe=510237facd) | Apr 22, 2023 |
| Gigabyte      | AORUS 15P XD                | [22925aa0c9](https://linux-hardware.org/?probe=22925aa0c9) | Apr 22, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [c1139db413](https://linux-hardware.org/?probe=c1139db413) | Apr 22, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [3056a65306](https://linux-hardware.org/?probe=3056a65306) | Apr 22, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [87d3a8b29f](https://linux-hardware.org/?probe=87d3a8b29f) | Apr 20, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [b7f138b04c](https://linux-hardware.org/?probe=b7f138b04c) | Apr 20, 2023 |
| Dell          | Precision M6600             | [e71bf9e7bb](https://linux-hardware.org/?probe=e71bf9e7bb) | Apr 20, 2023 |
| ASUSTek       | K50IJ                       | [3b07dc847f](https://linux-hardware.org/?probe=3b07dc847f) | Apr 20, 2023 |
| MSI           | Creator Z17 A12UHST         | [1396746fba](https://linux-hardware.org/?probe=1396746fba) | Apr 20, 2023 |
| HP            | 255 G7 Notebook PC          | [b2f977f4a1](https://linux-hardware.org/?probe=b2f977f4a1) | Apr 19, 2023 |
| Acer          | Aspire A715-71G             | [83b48fff59](https://linux-hardware.org/?probe=83b48fff59) | Apr 19, 2023 |
| Dell          | Latitude 7410               | [36e2aea9ea](https://linux-hardware.org/?probe=36e2aea9ea) | Apr 19, 2023 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [09a37b3301](https://linux-hardware.org/?probe=09a37b3301) | Apr 19, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | [1548cc4309](https://linux-hardware.org/?probe=1548cc4309) | Apr 19, 2023 |
| Dell          | Precision M6800             | [b39d3f31df](https://linux-hardware.org/?probe=b39d3f31df) | Apr 18, 2023 |
| Lenovo        | Y50-70 20378                | [af6c719754](https://linux-hardware.org/?probe=af6c719754) | Apr 18, 2023 |
| Gigabyte      | G5 GE                       | [f1baab4be4](https://linux-hardware.org/?probe=f1baab4be4) | Apr 17, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [a0b6c23c0b](https://linux-hardware.org/?probe=a0b6c23c0b) | Apr 17, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [35ec02005f](https://linux-hardware.org/?probe=35ec02005f) | Apr 17, 2023 |
| Acer          | Swift SFA16-41              | [1232f86e3e](https://linux-hardware.org/?probe=1232f86e3e) | Apr 17, 2023 |
| Dell          | Latitude D830               | [3da091adc2](https://linux-hardware.org/?probe=3da091adc2) | Apr 17, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | [7ca92cfada](https://linux-hardware.org/?probe=7ca92cfada) | Apr 17, 2023 |
| Lenovo        | ThinkPad T480s 20L8SF1X0... | [d567c29052](https://linux-hardware.org/?probe=d567c29052) | Apr 17, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [c59c5c0cdf](https://linux-hardware.org/?probe=c59c5c0cdf) | Apr 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [391b43ba8c](https://linux-hardware.org/?probe=391b43ba8c) | Apr 16, 2023 |
| Dell          | Inspiron 5559               | [b74080b280](https://linux-hardware.org/?probe=b74080b280) | Apr 16, 2023 |
| Dell          | Latitude E6330              | [1a75476b96](https://linux-hardware.org/?probe=1a75476b96) | Apr 16, 2023 |
| Acer          | AO722                       | [af4e100c16](https://linux-hardware.org/?probe=af4e100c16) | Apr 15, 2023 |
| Kiano         | Elegance 14.2               | [34062f30df](https://linux-hardware.org/?probe=34062f30df) | Apr 15, 2023 |
| Acer          | Aspire 5336                 | [7613566248](https://linux-hardware.org/?probe=7613566248) | Apr 15, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [9206720811](https://linux-hardware.org/?probe=9206720811) | Apr 14, 2023 |
| Valve         | Jupiter                     | [c1558fbc72](https://linux-hardware.org/?probe=c1558fbc72) | Apr 14, 2023 |
| Lenovo        | Legion 5 15IAH7 82RC        | [9cb53e6d6f](https://linux-hardware.org/?probe=9cb53e6d6f) | Apr 13, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [9341670151](https://linux-hardware.org/?probe=9341670151) | Apr 13, 2023 |
| Lenovo        | ThinkPad X220 4291AY8       | [b2bc70473d](https://linux-hardware.org/?probe=b2bc70473d) | Apr 13, 2023 |
| Fujitsu Si... | AMILO PRO V3515             | [be2d8594c3](https://linux-hardware.org/?probe=be2d8594c3) | Apr 13, 2023 |
| Dell          | Latitude E6230              | [a7cce7ebde](https://linux-hardware.org/?probe=a7cce7ebde) | Apr 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3460C... | [f1999ee14e](https://linux-hardware.org/?probe=f1999ee14e) | Apr 11, 2023 |
| Dell          | Latitude 7390               | [9361f06955](https://linux-hardware.org/?probe=9361f06955) | Apr 11, 2023 |
| Lenovo        | ThinkPad T480 20L5S12H00    | [c550410c5b](https://linux-hardware.org/?probe=c550410c5b) | Apr 11, 2023 |
| HP            | Pavilion dv7                | [000c77d7d5](https://linux-hardware.org/?probe=000c77d7d5) | Apr 10, 2023 |
| HP            | Pavilion dv7                | [08e5108cda](https://linux-hardware.org/?probe=08e5108cda) | Apr 10, 2023 |
| Lenovo        | ThinkPad T450 20BUS0QT04    | [90d7e2bb21](https://linux-hardware.org/?probe=90d7e2bb21) | Apr 09, 2023 |
| Lenovo        | ThinkPad X220 4291LR6       | [ea86227d59](https://linux-hardware.org/?probe=ea86227d59) | Apr 09, 2023 |
| HUAWEI        | HVY-WXX9                    | [6b6b2a8633](https://linux-hardware.org/?probe=6b6b2a8633) | Apr 09, 2023 |
| HUAWEI        | HVY-WXX9                    | [00489240d2](https://linux-hardware.org/?probe=00489240d2) | Apr 09, 2023 |
| Lenovo        | IdeaPad S540-14IWL 81ND     | [869d7607e9](https://linux-hardware.org/?probe=869d7607e9) | Apr 08, 2023 |
| Acer          | Aspire 5336                 | [6e419f3401](https://linux-hardware.org/?probe=6e419f3401) | Apr 08, 2023 |
| Toshiba       | Satellite L750D             | [d510eabb78](https://linux-hardware.org/?probe=d510eabb78) | Apr 08, 2023 |
| Toshiba       | Satellite L750D             | [3c8c0e7455](https://linux-hardware.org/?probe=3c8c0e7455) | Apr 08, 2023 |
| Samsung       | 300E4A/300E5A/300E7A        | [370d1404f2](https://linux-hardware.org/?probe=370d1404f2) | Apr 08, 2023 |
| Lenovo        | G50-70 20351                | [b8dd840f5d](https://linux-hardware.org/?probe=b8dd840f5d) | Apr 08, 2023 |
| Samsung       | 400B4C/400B5C/200B4C/200... | [8026ca606e](https://linux-hardware.org/?probe=8026ca606e) | Apr 07, 2023 |
| Dell          | Inspiron 11-3162            | [accdfd2253](https://linux-hardware.org/?probe=accdfd2253) | Apr 07, 2023 |
| Samsung       | 730U3E/740U3E               | [7d4b6838e2](https://linux-hardware.org/?probe=7d4b6838e2) | Apr 07, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | [413528fa5a](https://linux-hardware.org/?probe=413528fa5a) | Apr 07, 2023 |
| MSI           | GP76 Leopard 10UE           | [c7b870bb22](https://linux-hardware.org/?probe=c7b870bb22) | Apr 07, 2023 |
| Toshiba       | Satellite C855-12N          | [69e30b2fd8](https://linux-hardware.org/?probe=69e30b2fd8) | Apr 07, 2023 |
| HP            | 620                         | [2e14b2c046](https://linux-hardware.org/?probe=2e14b2c046) | Apr 07, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b6f721687e](https://linux-hardware.org/?probe=b6f721687e) | Apr 06, 2023 |
| HP            | ProBook 4740s               | [14fb51de44](https://linux-hardware.org/?probe=14fb51de44) | Apr 06, 2023 |
| eMachines     | E720 V1.09                  | [278ca903ac](https://linux-hardware.org/?probe=278ca903ac) | Apr 06, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [93cb5f66a1](https://linux-hardware.org/?probe=93cb5f66a1) | Apr 06, 2023 |
| Samsung       | 730U3E/740U3E               | [2be8e6430c](https://linux-hardware.org/?probe=2be8e6430c) | Apr 05, 2023 |
| Kruger&Mat... | KM1406                      | [1b536904d4](https://linux-hardware.org/?probe=1b536904d4) | Apr 05, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [f1398d5ada](https://linux-hardware.org/?probe=f1398d5ada) | Apr 05, 2023 |
| Toshiba       | Satellite C50-A             | [8e02a6dbed](https://linux-hardware.org/?probe=8e02a6dbed) | Apr 05, 2023 |
| Lenovo        | G50-80 80E5                 | [b469666726](https://linux-hardware.org/?probe=b469666726) | Apr 05, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [56119c4c93](https://linux-hardware.org/?probe=56119c4c93) | Apr 05, 2023 |
| Google        | Cyan                        | [f02aa2a210](https://linux-hardware.org/?probe=f02aa2a210) | Apr 04, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [0c0196b199](https://linux-hardware.org/?probe=0c0196b199) | Apr 04, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [04afa2e378](https://linux-hardware.org/?probe=04afa2e378) | Apr 04, 2023 |
| Lenovo        | B50-80 80LT                 | [163bfb5525](https://linux-hardware.org/?probe=163bfb5525) | Apr 03, 2023 |
| HP            | Compaq CQ58                 | [f0026163c3](https://linux-hardware.org/?probe=f0026163c3) | Apr 03, 2023 |
| HP            | EliteBook 865 16 inch G9... | [6906a8d309](https://linux-hardware.org/?probe=6906a8d309) | Apr 03, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [71a388a292](https://linux-hardware.org/?probe=71a388a292) | Apr 03, 2023 |
| HP            | Compaq CQ58                 | [7c4676c380](https://linux-hardware.org/?probe=7c4676c380) | Apr 03, 2023 |
| HP            | Stream Notebook             | [27610e0a39](https://linux-hardware.org/?probe=27610e0a39) | Apr 03, 2023 |
| Dell          | Latitude 3190               | [a1fa664431](https://linux-hardware.org/?probe=a1fa664431) | Apr 03, 2023 |
| ASUSTek       | TP300LJ                     | [7da5aab332](https://linux-hardware.org/?probe=7da5aab332) | Apr 02, 2023 |
| Lenovo        | ThinkPad T470 20HES0FA03    | [7274c8222b](https://linux-hardware.org/?probe=7274c8222b) | Apr 02, 2023 |
| HP            | ProBook 455 G1              | [869f36fc4c](https://linux-hardware.org/?probe=869f36fc4c) | Apr 01, 2023 |
| Lenovo        | G560 20042                  | [c5a4783dfb](https://linux-hardware.org/?probe=c5a4783dfb) | Apr 01, 2023 |
| HP            | Compaq Presario CQ60        | [e5a729243d](https://linux-hardware.org/?probe=e5a729243d) | Mar 31, 2023 |
| Samsung       | 950XED                      | [c3b37a213a](https://linux-hardware.org/?probe=c3b37a213a) | Mar 31, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [e2c6f05595](https://linux-hardware.org/?probe=e2c6f05595) | Mar 31, 2023 |
| HUAWEI        | KPL-W0X                     | [6e93ca4159](https://linux-hardware.org/?probe=6e93ca4159) | Mar 31, 2023 |
| Acer          | TravelMate 8172Z            | [10cc090653](https://linux-hardware.org/?probe=10cc090653) | Mar 31, 2023 |
| Dell          | Latitude D620               | [801ede47a2](https://linux-hardware.org/?probe=801ede47a2) | Mar 31, 2023 |
| ASUSTek       | K53SJ                       | [aa9a729217](https://linux-hardware.org/?probe=aa9a729217) | Mar 30, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [6b9737a62f](https://linux-hardware.org/?probe=6b9737a62f) | Mar 30, 2023 |
| HP            | Laptop 15s-fq2xxx           | [f78b6ab8c5](https://linux-hardware.org/?probe=f78b6ab8c5) | Mar 30, 2023 |
| Dell          | Latitude E6530              | [eb7392d1ae](https://linux-hardware.org/?probe=eb7392d1ae) | Mar 29, 2023 |
| Lenovo        | G570 20079                  | [680c7a04ed](https://linux-hardware.org/?probe=680c7a04ed) | Mar 29, 2023 |
| GPD           | G1621-02                    | [2ed8b6c147](https://linux-hardware.org/?probe=2ed8b6c147) | Mar 29, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [fa1a582da6](https://linux-hardware.org/?probe=fa1a582da6) | Mar 29, 2023 |
| HP            | 250 G6 Notebook PC          | [94cdfc44d1](https://linux-hardware.org/?probe=94cdfc44d1) | Mar 28, 2023 |
| Kiano         | Elegance 14.2               | [ea2013b347](https://linux-hardware.org/?probe=ea2013b347) | Mar 28, 2023 |
| Lenovo        | ThinkPad T470p 20J7S0QK0... | [7f5fb11940](https://linux-hardware.org/?probe=7f5fb11940) | Mar 28, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [856b789461](https://linux-hardware.org/?probe=856b789461) | Mar 28, 2023 |
| Dell          | Latitude 7490               | [41d01ead49](https://linux-hardware.org/?probe=41d01ead49) | Mar 28, 2023 |
| Dell          | Inspiron 5735               | [823a6ece98](https://linux-hardware.org/?probe=823a6ece98) | Mar 27, 2023 |
| Lenovo        | ThinkPad X250 20CLS47P00    | [e287203572](https://linux-hardware.org/?probe=e287203572) | Mar 27, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [60012fd503](https://linux-hardware.org/?probe=60012fd503) | Mar 27, 2023 |
| Dell          | XPS 13 7390                 | [aaeb6059a2](https://linux-hardware.org/?probe=aaeb6059a2) | Mar 27, 2023 |
| Dell          | Precision 7670              | [eece926391](https://linux-hardware.org/?probe=eece926391) | Mar 27, 2023 |
| Dell          | Latitude 3190               | [757f1fc2e7](https://linux-hardware.org/?probe=757f1fc2e7) | Mar 27, 2023 |
| Dell          | Precision 7670              | [5b8f0590ec](https://linux-hardware.org/?probe=5b8f0590ec) | Mar 27, 2023 |
| Lenovo        | ThinkPad T520 4243RP3       | [38fa314d2f](https://linux-hardware.org/?probe=38fa314d2f) | Mar 26, 2023 |
| MSI           | Creator Z16 A11UET          | [0133ab37af](https://linux-hardware.org/?probe=0133ab37af) | Mar 26, 2023 |
| Sony          | VGN-BX61VN                  | [76f62cf9c1](https://linux-hardware.org/?probe=76f62cf9c1) | Mar 26, 2023 |
| Lenovo        | G50-80 80E5                 | [250e0a99d1](https://linux-hardware.org/?probe=250e0a99d1) | Mar 26, 2023 |
| Lenovo        | G510 20238                  | [f406bad420](https://linux-hardware.org/?probe=f406bad420) | Mar 26, 2023 |
| Lenovo        | ThinkPad W520 4282PQ7       | [ff42aa158f](https://linux-hardware.org/?probe=ff42aa158f) | Mar 25, 2023 |
| HP            | Notebook                    | [7c4088912e](https://linux-hardware.org/?probe=7c4088912e) | Mar 25, 2023 |
| Lenovo        | ThinkPad T480s 20L7S0YA0... | [f4cb79dbf8](https://linux-hardware.org/?probe=f4cb79dbf8) | Mar 25, 2023 |
| Valve         | Jupiter                     | [6a7628c31d](https://linux-hardware.org/?probe=6a7628c31d) | Mar 25, 2023 |
| HP            | Pavilion dv6                | [29a94d3d9e](https://linux-hardware.org/?probe=29a94d3d9e) | Mar 25, 2023 |
| HP            | Pavilion dv6                | [c3a6c3f669](https://linux-hardware.org/?probe=c3a6c3f669) | Mar 25, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [7f32708bde](https://linux-hardware.org/?probe=7f32708bde) | Mar 24, 2023 |
| HP            | Pavilion Notebook           | [446c510c65](https://linux-hardware.org/?probe=446c510c65) | Mar 24, 2023 |
| Toshiba       | Satellite C855-12N          | [cb9692876c](https://linux-hardware.org/?probe=cb9692876c) | Mar 24, 2023 |
| Toshiba       | Satellite Pro A50-C         | [2fe9003124](https://linux-hardware.org/?probe=2fe9003124) | Mar 24, 2023 |
| Toshiba       | Satellite Pro A50-C         | [95c5c45220](https://linux-hardware.org/?probe=95c5c45220) | Mar 24, 2023 |
| MSI           | Creator Z17 A12UHST         | [47814b01b6](https://linux-hardware.org/?probe=47814b01b6) | Mar 24, 2023 |
| Sony          | SVE1512M6ESI                | [db00c70eb7](https://linux-hardware.org/?probe=db00c70eb7) | Mar 24, 2023 |
| Dell          | Latitude E7450              | [c1e43b6a40](https://linux-hardware.org/?probe=c1e43b6a40) | Mar 23, 2023 |
| Lenovo        | G580                        | [367ed9241a](https://linux-hardware.org/?probe=367ed9241a) | Mar 23, 2023 |
| Lenovo        | G580                        | [6ee526d77a](https://linux-hardware.org/?probe=6ee526d77a) | Mar 22, 2023 |
| Acer          | Aspire VN7-791              | [054efde4e8](https://linux-hardware.org/?probe=054efde4e8) | Mar 22, 2023 |
| Lenovo        | G50-80 80E5                 | [f6ad6626ff](https://linux-hardware.org/?probe=f6ad6626ff) | Mar 22, 2023 |
| HUAWEI        | KPL-W0X                     | [0ae6ab3ff6](https://linux-hardware.org/?probe=0ae6ab3ff6) | Mar 21, 2023 |
| Unknown       | Unknown                     | [31ee1d66d8](https://linux-hardware.org/?probe=31ee1d66d8) | Mar 21, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [57663c8d60](https://linux-hardware.org/?probe=57663c8d60) | Mar 21, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [f5cbd1977f](https://linux-hardware.org/?probe=f5cbd1977f) | Mar 20, 2023 |
| Dell          | Latitude 3190               | [f4bea67dcc](https://linux-hardware.org/?probe=f4bea67dcc) | Mar 20, 2023 |
| HP            | EliteBook 830 G5            | [ba804b8e21](https://linux-hardware.org/?probe=ba804b8e21) | Mar 20, 2023 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [919ccc204b](https://linux-hardware.org/?probe=919ccc204b) | Mar 19, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [c89c2e1369](https://linux-hardware.org/?probe=c89c2e1369) | Mar 18, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [31299394e0](https://linux-hardware.org/?probe=31299394e0) | Mar 18, 2023 |
| Fujitsu       | LIFEBOOK AH530              | [e40cf4f577](https://linux-hardware.org/?probe=e40cf4f577) | Mar 18, 2023 |
| Dell          | Venue 11 Pro 7130 MS        | [2a3bb3e212](https://linux-hardware.org/?probe=2a3bb3e212) | Mar 18, 2023 |
| Dell          | Venue 11 Pro 7130 MS        | [56fab2cb17](https://linux-hardware.org/?probe=56fab2cb17) | Mar 18, 2023 |
| Lenovo        | G570 20079                  | [2d7a146140](https://linux-hardware.org/?probe=2d7a146140) | Mar 18, 2023 |
| ASUSTek       | K52Jc                       | [07dc0a0959](https://linux-hardware.org/?probe=07dc0a0959) | Mar 18, 2023 |
| ASUSTek       | K52Jc                       | [f61ec5ce9f](https://linux-hardware.org/?probe=f61ec5ce9f) | Mar 18, 2023 |
| Dell          | Latitude 5420               | [318da7f6c0](https://linux-hardware.org/?probe=318da7f6c0) | Mar 18, 2023 |
| Toshiba       | QOSMIO X500                 | [2ce878e92e](https://linux-hardware.org/?probe=2ce878e92e) | Mar 17, 2023 |
| Dell          | G5 5590                     | [9686d438e6](https://linux-hardware.org/?probe=9686d438e6) | Mar 17, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [728c9ad9f5](https://linux-hardware.org/?probe=728c9ad9f5) | Mar 17, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | [593bd6b3ac](https://linux-hardware.org/?probe=593bd6b3ac) | Mar 17, 2023 |
| Dell          | Latitude E7440              | [8a6e751b61](https://linux-hardware.org/?probe=8a6e751b61) | Mar 16, 2023 |
| HP            | Laptop 15-bs0xx             | [f53eccbbe9](https://linux-hardware.org/?probe=f53eccbbe9) | Mar 16, 2023 |
| Dell          | Latitude 5511               | [7444a8c723](https://linux-hardware.org/?probe=7444a8c723) | Mar 16, 2023 |
| Dell          | Latitude D620               | [1731735e10](https://linux-hardware.org/?probe=1731735e10) | Mar 16, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [eb0beb38eb](https://linux-hardware.org/?probe=eb0beb38eb) | Mar 16, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [c54f2ca880](https://linux-hardware.org/?probe=c54f2ca880) | Mar 16, 2023 |
| Sony          | VPCEH1S1E                   | [9e8a96156c](https://linux-hardware.org/?probe=9e8a96156c) | Mar 15, 2023 |
| Lenovo        | ThinkPad T440p 20AWS19P0... | [6a2d338526](https://linux-hardware.org/?probe=6a2d338526) | Mar 15, 2023 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | [59d7fa9a34](https://linux-hardware.org/?probe=59d7fa9a34) | Mar 15, 2023 |
| Dell          | Latitude 7390               | [7cc6b3a278](https://linux-hardware.org/?probe=7cc6b3a278) | Mar 15, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | [97fe8661ed](https://linux-hardware.org/?probe=97fe8661ed) | Mar 14, 2023 |
| Kiano         | Elegance 14.2               | [f9ed050c6a](https://linux-hardware.org/?probe=f9ed050c6a) | Mar 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [daa3d3869e](https://linux-hardware.org/?probe=daa3d3869e) | Mar 14, 2023 |
| HP            | ProBook 450 G3              | [d422d0d291](https://linux-hardware.org/?probe=d422d0d291) | Mar 14, 2023 |
| Lenovo        | ThinkPad X301 2776LEG       | [7b0df25d34](https://linux-hardware.org/?probe=7b0df25d34) | Mar 14, 2023 |
| Lenovo        | ThinkPad X301 2776LEG       | [65fe38f62e](https://linux-hardware.org/?probe=65fe38f62e) | Mar 14, 2023 |
| Toshiba       | Satellite L40               | [bfc73429bb](https://linux-hardware.org/?probe=bfc73429bb) | Mar 13, 2023 |
| Samsung       | 300E4A/300E5A/300E7A        | [6c76af84cb](https://linux-hardware.org/?probe=6c76af84cb) | Mar 13, 2023 |
| Acer          | Aspire A315-24P             | [b9cfb4b900](https://linux-hardware.org/?probe=b9cfb4b900) | Mar 13, 2023 |
| Acer          | Aspire A315-24P             | [fba21e619d](https://linux-hardware.org/?probe=fba21e619d) | Mar 13, 2023 |
| HP            | Pavilion dv6                | [f649c78020](https://linux-hardware.org/?probe=f649c78020) | Mar 13, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [bc375a2ddd](https://linux-hardware.org/?probe=bc375a2ddd) | Mar 13, 2023 |
| Dell          | Latitude 3190               | [97cc3ffc79](https://linux-hardware.org/?probe=97cc3ffc79) | Mar 13, 2023 |
| ASUSTek       | X551MA                      | [37b002e8ec](https://linux-hardware.org/?probe=37b002e8ec) | Mar 12, 2023 |
| Lenovo        | ThinkPad X240 20AMS0XP0S    | [a2ee9a2818](https://linux-hardware.org/?probe=a2ee9a2818) | Mar 12, 2023 |
| ASUSTek       | N550JK                      | [bb5d069d90](https://linux-hardware.org/?probe=bb5d069d90) | Mar 12, 2023 |
| Google        | Electro                     | [86cbc9d907](https://linux-hardware.org/?probe=86cbc9d907) | Mar 12, 2023 |
| HP            | 250 G6 Notebook PC          | [d173735b81](https://linux-hardware.org/?probe=d173735b81) | Mar 11, 2023 |
| Dell          | Precision M6600             | [9d5e2f1e01](https://linux-hardware.org/?probe=9d5e2f1e01) | Mar 11, 2023 |
| Acer          | Extensa 5620                | [f95239bf35](https://linux-hardware.org/?probe=f95239bf35) | Mar 11, 2023 |
| Kiano         | Elegance 14.2               | [5714b30108](https://linux-hardware.org/?probe=5714b30108) | Mar 11, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [82b5297ab8](https://linux-hardware.org/?probe=82b5297ab8) | Mar 11, 2023 |
| Lenovo        | ThinkPad T440p 20AWS19P0... | [44867c946f](https://linux-hardware.org/?probe=44867c946f) | Mar 10, 2023 |
| Dell          | Latitude E6530              | [70b72984bc](https://linux-hardware.org/?probe=70b72984bc) | Mar 10, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | [2d99e047c9](https://linux-hardware.org/?probe=2d99e047c9) | Mar 10, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | [99d5f17b22](https://linux-hardware.org/?probe=99d5f17b22) | Mar 09, 2023 |
| HP            | Laptop 15s-eq0xxx           | [7a7e8bc855](https://linux-hardware.org/?probe=7a7e8bc855) | Mar 09, 2023 |
| ASUSTek       | X550CL                      | [9acfcb9b4f](https://linux-hardware.org/?probe=9acfcb9b4f) | Mar 09, 2023 |
| Lenovo        | IdeaPad Y580                | [cc2d7d8a95](https://linux-hardware.org/?probe=cc2d7d8a95) | Mar 09, 2023 |
| Dell          | Latitude E6440              | [b00f44cd46](https://linux-hardware.org/?probe=b00f44cd46) | Mar 09, 2023 |
| Dell          | Latitude E6440              | [3b9229e07a](https://linux-hardware.org/?probe=3b9229e07a) | Mar 09, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [c50daaf3b9](https://linux-hardware.org/?probe=c50daaf3b9) | Mar 09, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [fdc32a6871](https://linux-hardware.org/?probe=fdc32a6871) | Mar 09, 2023 |
| ASUSTek       | X550CL                      | [21f11cf791](https://linux-hardware.org/?probe=21f11cf791) | Mar 09, 2023 |
| HP            | EliteBook 8570w             | [dfd9b7a9b9](https://linux-hardware.org/?probe=dfd9b7a9b9) | Mar 08, 2023 |
| HP            | ENVY 6                      | [4873f7b85f](https://linux-hardware.org/?probe=4873f7b85f) | Mar 08, 2023 |
| Lenovo        | ThinkPad T61 7661BM5        | [daf29f1a82](https://linux-hardware.org/?probe=daf29f1a82) | Mar 08, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [233722f0e1](https://linux-hardware.org/?probe=233722f0e1) | Mar 07, 2023 |
| Dell          | Latitude 7290               | [38f12088b2](https://linux-hardware.org/?probe=38f12088b2) | Mar 07, 2023 |
| HUAWEI        | KPL-W0X                     | [76ebbe553f](https://linux-hardware.org/?probe=76ebbe553f) | Mar 06, 2023 |
| Dell          | Latitude 3190               | [a3a4113ab4](https://linux-hardware.org/?probe=a3a4113ab4) | Mar 06, 2023 |
| Lenovo        | Legion 5 17ACH6 82K0        | [6db57d4d9f](https://linux-hardware.org/?probe=6db57d4d9f) | Mar 05, 2023 |
| ASUSTek       | X551MA                      | [b77e06361b](https://linux-hardware.org/?probe=b77e06361b) | Mar 05, 2023 |
| Lenovo        | ThinkPad T440p 20AWS37F0... | [48677f9f86](https://linux-hardware.org/?probe=48677f9f86) | Mar 05, 2023 |
| IGEL Techn... | H830C                       | [3619b3fcee](https://linux-hardware.org/?probe=3619b3fcee) | Mar 05, 2023 |
| ASUSTek       | N71Vg                       | [4d83fda5ba](https://linux-hardware.org/?probe=4d83fda5ba) | Mar 05, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [8b36c984f8](https://linux-hardware.org/?probe=8b36c984f8) | Mar 05, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [65006682e6](https://linux-hardware.org/?probe=65006682e6) | Mar 05, 2023 |
| HP            | 15                          | [0efd9be7ae](https://linux-hardware.org/?probe=0efd9be7ae) | Mar 04, 2023 |
| HP            | 15                          | [b8a33a3d73](https://linux-hardware.org/?probe=b8a33a3d73) | Mar 04, 2023 |
| Lenovo        | ThinkPad T420 4177R3U       | [525dd38cf1](https://linux-hardware.org/?probe=525dd38cf1) | Mar 04, 2023 |
| Toshiba       | Satellite L40               | [bd108fcfba](https://linux-hardware.org/?probe=bd108fcfba) | Mar 04, 2023 |
| HP            | Notebook                    | [229fbff95c](https://linux-hardware.org/?probe=229fbff95c) | Mar 04, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [afe8ef7318](https://linux-hardware.org/?probe=afe8ef7318) | Mar 04, 2023 |
| HP            | EliteBook 830 G5            | [82acbe37f7](https://linux-hardware.org/?probe=82acbe37f7) | Mar 04, 2023 |
| Dell          | Vostro 3350                 | [1bfad93a1e](https://linux-hardware.org/?probe=1bfad93a1e) | Mar 04, 2023 |
| Dell          | Vostro 3350                 | [f782f8e288](https://linux-hardware.org/?probe=f782f8e288) | Mar 04, 2023 |
| Apple         | MacBookPro8,2               | [0b0c5a6895](https://linux-hardware.org/?probe=0b0c5a6895) | Mar 04, 2023 |
| ASUSTek       | X550CL                      | [c16eae7537](https://linux-hardware.org/?probe=c16eae7537) | Mar 04, 2023 |
| IGEL Techn... | H830C                       | [4625dc0660](https://linux-hardware.org/?probe=4625dc0660) | Mar 04, 2023 |
| Toshiba       | Satellite L40               | [e3f1423c39](https://linux-hardware.org/?probe=e3f1423c39) | Mar 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | [0228fd4ab1](https://linux-hardware.org/?probe=0228fd4ab1) | Mar 04, 2023 |
| Dell          | Latitude 5480               | [4679c9328e](https://linux-hardware.org/?probe=4679c9328e) | Mar 03, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [9186971572](https://linux-hardware.org/?probe=9186971572) | Mar 03, 2023 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | [25f45efbc1](https://linux-hardware.org/?probe=25f45efbc1) | Mar 03, 2023 |
| ASUSTek       | X551MA                      | [608c8a42da](https://linux-hardware.org/?probe=608c8a42da) | Mar 03, 2023 |
| ASUSTek       | X551MA                      | [fa55d9fb5c](https://linux-hardware.org/?probe=fa55d9fb5c) | Mar 03, 2023 |
| Lenovo        | ThinkPad T480s 20L8S2B50... | [8268a3bbf3](https://linux-hardware.org/?probe=8268a3bbf3) | Mar 03, 2023 |
| ASUSTek       | N61Vn                       | [9528e36d7b](https://linux-hardware.org/?probe=9528e36d7b) | Mar 03, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [726752f23a](https://linux-hardware.org/?probe=726752f23a) | Mar 02, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [a5288ab43b](https://linux-hardware.org/?probe=a5288ab43b) | Mar 02, 2023 |
| HP            | ZBook Power G7 Mobile Wo... | [e87ce2454c](https://linux-hardware.org/?probe=e87ce2454c) | Mar 02, 2023 |
| Dell          | Latitude D830               | [83415c82ac](https://linux-hardware.org/?probe=83415c82ac) | Mar 02, 2023 |
| Acer          | Aspire V3-574G              | [e943ab2cde](https://linux-hardware.org/?probe=e943ab2cde) | Mar 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [9b0d952fa9](https://linux-hardware.org/?probe=9b0d952fa9) | Mar 01, 2023 |
| Notebook      | NS50_70MU                   | [18ff6f22a6](https://linux-hardware.org/?probe=18ff6f22a6) | Mar 01, 2023 |
| Dell          | Latitude 5420               | [0596aff5c4](https://linux-hardware.org/?probe=0596aff5c4) | Feb 28, 2023 |
| Lenovo        | Yoga710-14ISK 80TY          | [756e003316](https://linux-hardware.org/?probe=756e003316) | Feb 28, 2023 |
| HP            | ZBook 15u G3                | [9c49a1748b](https://linux-hardware.org/?probe=9c49a1748b) | Feb 28, 2023 |
| Lenovo        | ThinkPad E560 20EV000UUK    | [7060b60651](https://linux-hardware.org/?probe=7060b60651) | Feb 27, 2023 |
| HP            | ProBook 430 G6              | [a184aa7141](https://linux-hardware.org/?probe=a184aa7141) | Feb 27, 2023 |
| Lenovo        | G50-80 80E5                 | [d7bb021829](https://linux-hardware.org/?probe=d7bb021829) | Feb 27, 2023 |
| ASUSTek       | K75VJ                       | [7fc0fff829](https://linux-hardware.org/?probe=7fc0fff829) | Feb 27, 2023 |
| Dell          | Latitude 7390               | [a2167ae72b](https://linux-hardware.org/?probe=a2167ae72b) | Feb 27, 2023 |
| Schenker      | VISION (E22)                | [498444ca02](https://linux-hardware.org/?probe=498444ca02) | Feb 27, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [1ce9430009](https://linux-hardware.org/?probe=1ce9430009) | Feb 27, 2023 |
| HP            | Notebook                    | [a1180ad479](https://linux-hardware.org/?probe=a1180ad479) | Feb 27, 2023 |
| HP            | Notebook                    | [ee2645efa8](https://linux-hardware.org/?probe=ee2645efa8) | Feb 27, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [d57bb59dee](https://linux-hardware.org/?probe=d57bb59dee) | Feb 27, 2023 |
| ASUSTek       | K52F                        | [fa30ea101a](https://linux-hardware.org/?probe=fa30ea101a) | Feb 27, 2023 |
| Dell          | Latitude 3190               | [279b385865](https://linux-hardware.org/?probe=279b385865) | Feb 27, 2023 |
| HP            | Notebook                    | [0d838134b7](https://linux-hardware.org/?probe=0d838134b7) | Feb 27, 2023 |
| Acer          | Aspire ES1-711              | [8e397cc54f](https://linux-hardware.org/?probe=8e397cc54f) | Feb 26, 2023 |
| Gigabyte      | MMLP5AP-00                  | [eb5ca5bb8d](https://linux-hardware.org/?probe=eb5ca5bb8d) | Feb 26, 2023 |
| Valve         | Jupiter                     | [f7289abeb1](https://linux-hardware.org/?probe=f7289abeb1) | Feb 26, 2023 |
| Dell          | Latitude D630               | [cfdc009ff1](https://linux-hardware.org/?probe=cfdc009ff1) | Feb 26, 2023 |
| Acer          | Aspire E5-571G              | [07fe4333eb](https://linux-hardware.org/?probe=07fe4333eb) | Feb 25, 2023 |
| Sony          | VGN-FZ31M                   | [6b830e36f1](https://linux-hardware.org/?probe=6b830e36f1) | Feb 25, 2023 |
| HP            | ZBook 15u G3                | [92879d708d](https://linux-hardware.org/?probe=92879d708d) | Feb 24, 2023 |
| HP            | ZBook 15u G3                | [8a698df80f](https://linux-hardware.org/?probe=8a698df80f) | Feb 24, 2023 |
| HP            | EliteBook 840 G2            | [f1fa3164f9](https://linux-hardware.org/?probe=f1fa3164f9) | Feb 24, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [00591dc764](https://linux-hardware.org/?probe=00591dc764) | Feb 23, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [a85b9d1452](https://linux-hardware.org/?probe=a85b9d1452) | Feb 23, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [e2cdf5625c](https://linux-hardware.org/?probe=e2cdf5625c) | Feb 23, 2023 |
| Dell          | XPS 9320                    | [94e7c2d282](https://linux-hardware.org/?probe=94e7c2d282) | Feb 23, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [bfbb3aab2c](https://linux-hardware.org/?probe=bfbb3aab2c) | Feb 23, 2023 |
| ASUSTek       | 1215B                       | [970d77d150](https://linux-hardware.org/?probe=970d77d150) | Feb 22, 2023 |
| Notebook      | NS50_70MU                   | [a213ec0ba4](https://linux-hardware.org/?probe=a213ec0ba4) | Feb 22, 2023 |
| Apple         | MacBookPro8,1               | [b7071da133](https://linux-hardware.org/?probe=b7071da133) | Feb 22, 2023 |
| Dell          | Latitude 5491               | [fd68ba9595](https://linux-hardware.org/?probe=fd68ba9595) | Feb 21, 2023 |
| Fujitsu       | LIFEBOOK E744               | [bdcee122d3](https://linux-hardware.org/?probe=bdcee122d3) | Feb 21, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [88be67bbc1](https://linux-hardware.org/?probe=88be67bbc1) | Feb 21, 2023 |
| Lenovo        | ThinkPad R61 8933W4S        | [fec1a43d91](https://linux-hardware.org/?probe=fec1a43d91) | Feb 21, 2023 |
| Dell          | System XPS L502X            | [7352f47bb0](https://linux-hardware.org/?probe=7352f47bb0) | Feb 20, 2023 |
| Lenovo        | ThinkPad T410s 2924W3S      | [24081de7f1](https://linux-hardware.org/?probe=24081de7f1) | Feb 20, 2023 |
| HP            | 620                         | [c3dae62545](https://linux-hardware.org/?probe=c3dae62545) | Feb 20, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [e61bce94ea](https://linux-hardware.org/?probe=e61bce94ea) | Feb 20, 2023 |
| Acer          | Aspire A515-44              | [5fc82de1e4](https://linux-hardware.org/?probe=5fc82de1e4) | Feb 20, 2023 |
| Fujitsu       | LIFEBOOK E559               | [5e4c3607c7](https://linux-hardware.org/?probe=5e4c3607c7) | Feb 20, 2023 |
| Dell          | Latitude 3190               | [c05229588b](https://linux-hardware.org/?probe=c05229588b) | Feb 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [0d1a7d0dbe](https://linux-hardware.org/?probe=0d1a7d0dbe) | Feb 20, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | [3ddfaa902f](https://linux-hardware.org/?probe=3ddfaa902f) | Feb 20, 2023 |
| Acer          | Aspire A515-44              | [14e85e829f](https://linux-hardware.org/?probe=14e85e829f) | Feb 20, 2023 |
| Dell          | Latitude E7270              | [4eb17c846c](https://linux-hardware.org/?probe=4eb17c846c) | Feb 20, 2023 |
| Lenovo        | G510 20238                  | [7bc24845b3](https://linux-hardware.org/?probe=7bc24845b3) | Feb 20, 2023 |
| Lenovo        | G510 20238                  | [d6f20de9d5](https://linux-hardware.org/?probe=d6f20de9d5) | Feb 19, 2023 |
| Dell          | Vostro 5502                 | [49252b4695](https://linux-hardware.org/?probe=49252b4695) | Feb 19, 2023 |
| HP            | Unknown                     | [69b276cb01](https://linux-hardware.org/?probe=69b276cb01) | Feb 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [5300c136fd](https://linux-hardware.org/?probe=5300c136fd) | Feb 19, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [5ff3cab69f](https://linux-hardware.org/?probe=5ff3cab69f) | Feb 19, 2023 |
| Apple         | MacBookAir6,1               | [5cade7cfc3](https://linux-hardware.org/?probe=5cade7cfc3) | Feb 19, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [238f636180](https://linux-hardware.org/?probe=238f636180) | Feb 18, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [9b53b2b842](https://linux-hardware.org/?probe=9b53b2b842) | Feb 18, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [cdfcc639d3](https://linux-hardware.org/?probe=cdfcc639d3) | Feb 18, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [cbf0e3814c](https://linux-hardware.org/?probe=cbf0e3814c) | Feb 18, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [a424b3aa47](https://linux-hardware.org/?probe=a424b3aa47) | Feb 18, 2023 |
| Dell          | Latitude 3520               | [8df8f4c6fc](https://linux-hardware.org/?probe=8df8f4c6fc) | Feb 18, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [27958da7cc](https://linux-hardware.org/?probe=27958da7cc) | Feb 18, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [2f3a14eeaa](https://linux-hardware.org/?probe=2f3a14eeaa) | Feb 18, 2023 |
| MSI           | GL65 9SD                    | [a702514760](https://linux-hardware.org/?probe=a702514760) | Feb 17, 2023 |
| Dell          | Inspiron 5570               | [be29883368](https://linux-hardware.org/?probe=be29883368) | Feb 17, 2023 |
| Dell          | Latitude 5491               | [8a3298cdff](https://linux-hardware.org/?probe=8a3298cdff) | Feb 17, 2023 |
| Dell          | Latitude 5511               | [5c3a80271b](https://linux-hardware.org/?probe=5c3a80271b) | Feb 17, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [4a5c7432ae](https://linux-hardware.org/?probe=4a5c7432ae) | Feb 17, 2023 |
| HP            | ZBook Studio G3             | [af86e6cb72](https://linux-hardware.org/?probe=af86e6cb72) | Feb 17, 2023 |
| Lenovo        | ThinkPad T61 7661BM5        | [c829d5ed74](https://linux-hardware.org/?probe=c829d5ed74) | Feb 16, 2023 |
| Apple         | MacBookAir6,1               | [c96e404e3f](https://linux-hardware.org/?probe=c96e404e3f) | Feb 16, 2023 |
| Lenovo        | ThinkPad L13 20R30006PB     | [aad1f06bb9](https://linux-hardware.org/?probe=aad1f06bb9) | Feb 16, 2023 |
| MSI           | Creator Z17 A12UHST         | [a70040c510](https://linux-hardware.org/?probe=a70040c510) | Feb 16, 2023 |
| RTD Embedd... | CMA34CR                     | [dd8527bd65](https://linux-hardware.org/?probe=dd8527bd65) | Feb 16, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [73787e9141](https://linux-hardware.org/?probe=73787e9141) | Feb 16, 2023 |
| Dell          | Latitude 5480               | [ee1b786fd9](https://linux-hardware.org/?probe=ee1b786fd9) | Feb 15, 2023 |
| Lenovo        | Y50-70 20378                | [09301690c5](https://linux-hardware.org/?probe=09301690c5) | Feb 15, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [74a61dff13](https://linux-hardware.org/?probe=74a61dff13) | Feb 15, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [b53cdde5a7](https://linux-hardware.org/?probe=b53cdde5a7) | Feb 15, 2023 |
| HP            | EliteBook 650 15.6 inch ... | [2be1a08ef2](https://linux-hardware.org/?probe=2be1a08ef2) | Feb 15, 2023 |
| GPU Compan... | GWTN141-4                   | [1492f5c475](https://linux-hardware.org/?probe=1492f5c475) | Feb 15, 2023 |
| Dell          | System XPS L502X            | [2ea016be2a](https://linux-hardware.org/?probe=2ea016be2a) | Feb 14, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [65a5587c6d](https://linux-hardware.org/?probe=65a5587c6d) | Feb 14, 2023 |
| Acer          | Aspire A315-35              | [971fa91888](https://linux-hardware.org/?probe=971fa91888) | Feb 14, 2023 |
| Google        | Lillipup                    | [af7451beff](https://linux-hardware.org/?probe=af7451beff) | Feb 14, 2023 |
| Unknown       | Unknown                     | [1f80b65b37](https://linux-hardware.org/?probe=1f80b65b37) | Feb 13, 2023 |
| Unknown       | Unknown                     | [8b28eb095c](https://linux-hardware.org/?probe=8b28eb095c) | Feb 13, 2023 |
| Medion        | Akoya THE TOUCH 10          | [ec6afad108](https://linux-hardware.org/?probe=ec6afad108) | Feb 13, 2023 |
| Timi          | TM1613                      | [ce33c5c02e](https://linux-hardware.org/?probe=ce33c5c02e) | Feb 13, 2023 |
| Lenovo        | IdeaPad S210 Touch 20257    | [d132553080](https://linux-hardware.org/?probe=d132553080) | Feb 13, 2023 |
| Dell          | Latitude 5511               | [161095d97a](https://linux-hardware.org/?probe=161095d97a) | Feb 13, 2023 |
| TrekStor      | Surfbook W2                 | [f43f606f80](https://linux-hardware.org/?probe=f43f606f80) | Feb 13, 2023 |
| Dell          | Latitude 3190               | [f2fd97186c](https://linux-hardware.org/?probe=f2fd97186c) | Feb 13, 2023 |
| Dell          | Latitude E6420              | [6ffa1ea310](https://linux-hardware.org/?probe=6ffa1ea310) | Feb 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [04cfa15383](https://linux-hardware.org/?probe=04cfa15383) | Feb 12, 2023 |
| Lenovo        | ThinkPad T470s 20HGS1LM0... | [8ee6dd00d1](https://linux-hardware.org/?probe=8ee6dd00d1) | Feb 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [40116058d1](https://linux-hardware.org/?probe=40116058d1) | Feb 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [8e00bdf032](https://linux-hardware.org/?probe=8e00bdf032) | Feb 11, 2023 |
| Apple         | MacBookAir5,2               | [4f99163f99](https://linux-hardware.org/?probe=4f99163f99) | Feb 11, 2023 |
| Lenovo        | ThinkPad T430 2347BS4       | [682be07637](https://linux-hardware.org/?probe=682be07637) | Feb 11, 2023 |
| Valve         | Jupiter                     | [081d9e5294](https://linux-hardware.org/?probe=081d9e5294) | Feb 11, 2023 |
| HP            | ProBook 430 G3              | [e995a466a1](https://linux-hardware.org/?probe=e995a466a1) | Feb 10, 2023 |
| Toshiba       | Satellite L750              | [b6239c152e](https://linux-hardware.org/?probe=b6239c152e) | Feb 10, 2023 |
| Acer          | Aspire ES1-111M             | [82eea49fcd](https://linux-hardware.org/?probe=82eea49fcd) | Feb 09, 2023 |
| Acer          | Aspire ES1-111M             | [accbac47d5](https://linux-hardware.org/?probe=accbac47d5) | Feb 09, 2023 |
| Lenovo        | ThinkPad T530 2429MY2       | [9b5ffc7c58](https://linux-hardware.org/?probe=9b5ffc7c58) | Feb 09, 2023 |
| MSI           | Creator Z17 A12UHST         | [8885828bb8](https://linux-hardware.org/?probe=8885828bb8) | Feb 09, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [467c3e9149](https://linux-hardware.org/?probe=467c3e9149) | Feb 09, 2023 |
| Valve         | Jupiter                     | [26cb195bab](https://linux-hardware.org/?probe=26cb195bab) | Feb 08, 2023 |
| Dell          | Latitude 3570               | [dc460632ef](https://linux-hardware.org/?probe=dc460632ef) | Feb 08, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [842956e023](https://linux-hardware.org/?probe=842956e023) | Feb 08, 2023 |
| Dell          | Latitude E6520              | [c9c89084e8](https://linux-hardware.org/?probe=c9c89084e8) | Feb 07, 2023 |
| Dell          | Latitude E4300              | [aaad0477e4](https://linux-hardware.org/?probe=aaad0477e4) | Feb 07, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [307d491fc8](https://linux-hardware.org/?probe=307d491fc8) | Feb 07, 2023 |
| Dell          | Latitude 3520               | [d7569fa081](https://linux-hardware.org/?probe=d7569fa081) | Feb 06, 2023 |
| Valve         | Jupiter                     | [edc8beac1f](https://linux-hardware.org/?probe=edc8beac1f) | Feb 06, 2023 |
| Dell          | Latitude 5511               | [57e8ce4f20](https://linux-hardware.org/?probe=57e8ce4f20) | Feb 06, 2023 |
| Dell          | Latitude 3190               | [eafbc050e8](https://linux-hardware.org/?probe=eafbc050e8) | Feb 06, 2023 |
| HP            | EliteBook 820 G2            | [e8c0f3b7de](https://linux-hardware.org/?probe=e8c0f3b7de) | Feb 05, 2023 |
| HP            | EliteBook 820 G2            | [eb5a23a73b](https://linux-hardware.org/?probe=eb5a23a73b) | Feb 05, 2023 |
| Lenovo        | IdeaPad Y580                | [30d8845f10](https://linux-hardware.org/?probe=30d8845f10) | Feb 05, 2023 |
| Lenovo        | ThinkPad T15 Gen 1 20S6C... | [262dfe3aa9](https://linux-hardware.org/?probe=262dfe3aa9) | Feb 05, 2023 |
| Lenovo        | ThinkBook 14s-IWL 20RM      | [dbef2c679a](https://linux-hardware.org/?probe=dbef2c679a) | Feb 05, 2023 |
| Dell          | Inspiron 5570               | [eb399b4ffa](https://linux-hardware.org/?probe=eb399b4ffa) | Feb 05, 2023 |
| Lenovo        | ThinkBook 14s-IWL 20RM      | [14fb68ece0](https://linux-hardware.org/?probe=14fb68ece0) | Feb 05, 2023 |
| Apple         | MacBookPro8,1               | [d6adca1255](https://linux-hardware.org/?probe=d6adca1255) | Feb 04, 2023 |
| Dell          | Inspiron 5570               | [6e8ab1a5cb](https://linux-hardware.org/?probe=6e8ab1a5cb) | Feb 04, 2023 |
| Apple         | MacBookPro8,3               | [9d397c2187](https://linux-hardware.org/?probe=9d397c2187) | Feb 04, 2023 |
| Apple         | MacBookPro8,3               | [7b676dec23](https://linux-hardware.org/?probe=7b676dec23) | Feb 04, 2023 |
| Acer          | Aspire A515-51G             | [149465f225](https://linux-hardware.org/?probe=149465f225) | Feb 04, 2023 |
| Dell          | Vostro 3550                 | [4f1125bc93](https://linux-hardware.org/?probe=4f1125bc93) | Feb 04, 2023 |
| Lenovo        | G510 20238                  | [a385ff6f36](https://linux-hardware.org/?probe=a385ff6f36) | Feb 04, 2023 |
| Lenovo        | ThinkPad R500 2716W2K       | [a645368e82](https://linux-hardware.org/?probe=a645368e82) | Feb 04, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [c6dae92093](https://linux-hardware.org/?probe=c6dae92093) | Feb 03, 2023 |
| ASUSTek       | 1101HA                      | [28cb433eb0](https://linux-hardware.org/?probe=28cb433eb0) | Feb 03, 2023 |
| Dell          | Latitude 5480               | [da9f98059c](https://linux-hardware.org/?probe=da9f98059c) | Feb 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [9c5cfbc1a1](https://linux-hardware.org/?probe=9c5cfbc1a1) | Feb 03, 2023 |
| HP            | Unknown                     | [4b28efe30c](https://linux-hardware.org/?probe=4b28efe30c) | Feb 03, 2023 |
| Samsung       | 530U3C/530U4C/532U3C        | [4b1dc3d64b](https://linux-hardware.org/?probe=4b1dc3d64b) | Feb 02, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [1c6ed7ede6](https://linux-hardware.org/?probe=1c6ed7ede6) | Feb 02, 2023 |
| Dell          | Vostro 3580                 | [7efc294bac](https://linux-hardware.org/?probe=7efc294bac) | Feb 02, 2023 |
| MSI           | GV62 7RD                    | [c22fffb4e9](https://linux-hardware.org/?probe=c22fffb4e9) | Feb 02, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [ac6a930ffc](https://linux-hardware.org/?probe=ac6a930ffc) | Feb 02, 2023 |
| Dell          | Precision 7540              | [1d0d197808](https://linux-hardware.org/?probe=1d0d197808) | Feb 01, 2023 |
| Dell          | Latitude E7240              | [fe655eca77](https://linux-hardware.org/?probe=fe655eca77) | Jan 31, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [62f941075c](https://linux-hardware.org/?probe=62f941075c) | Jan 31, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [70310e25d1](https://linux-hardware.org/?probe=70310e25d1) | Jan 31, 2023 |
| Dell          | Latitude 5410               | [717012530d](https://linux-hardware.org/?probe=717012530d) | Jan 31, 2023 |
| Unknown       | Unknown                     | [e6c824b966](https://linux-hardware.org/?probe=e6c824b966) | Jan 31, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [aaaa563786](https://linux-hardware.org/?probe=aaaa563786) | Jan 31, 2023 |
| HP            | Compaq 6730s                | [1b083e5b64](https://linux-hardware.org/?probe=1b083e5b64) | Jan 31, 2023 |
| HP            | Compaq 6730s                | [ced2899d20](https://linux-hardware.org/?probe=ced2899d20) | Jan 31, 2023 |
| HP            | ProBook 650 G1              | [fc09442b7c](https://linux-hardware.org/?probe=fc09442b7c) | Jan 30, 2023 |
| HP            | ProBook 650 G1              | [b78602c91d](https://linux-hardware.org/?probe=b78602c91d) | Jan 30, 2023 |
| Dell          | Latitude E5430 non-vPro     | [d1e99e3f04](https://linux-hardware.org/?probe=d1e99e3f04) | Jan 30, 2023 |
| Toshiba       | Satellite P750              | [1cc0f342b5](https://linux-hardware.org/?probe=1cc0f342b5) | Jan 30, 2023 |
| Apple         | MacBookPro5,2               | [4cb11c2a78](https://linux-hardware.org/?probe=4cb11c2a78) | Jan 30, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603ZX... | [7442c84b55](https://linux-hardware.org/?probe=7442c84b55) | Jan 30, 2023 |
| Dell          | Inspiron 5758               | [de58233dca](https://linux-hardware.org/?probe=de58233dca) | Jan 30, 2023 |
| HP            | ZBook 15u G3                | [7f985597d7](https://linux-hardware.org/?probe=7f985597d7) | Jan 30, 2023 |
| HP            | ZBook 15u G3                | [7a35a6d886](https://linux-hardware.org/?probe=7a35a6d886) | Jan 30, 2023 |
| Dell          | Latitude 5480               | [ee87ac218f](https://linux-hardware.org/?probe=ee87ac218f) | Jan 30, 2023 |
| Dell          | Latitude 5480               | [3cbac640e1](https://linux-hardware.org/?probe=3cbac640e1) | Jan 30, 2023 |
| Dell          | Latitude 3190               | [a53530646a](https://linux-hardware.org/?probe=a53530646a) | Jan 30, 2023 |
| Dell          | Latitude E6520              | [81717ed3df](https://linux-hardware.org/?probe=81717ed3df) | Jan 30, 2023 |
| Apple         | MacBookPro11,1              | [e5af375b93](https://linux-hardware.org/?probe=e5af375b93) | Jan 29, 2023 |
| Apple         | MacBookPro11,1              | [41d67fcba8](https://linux-hardware.org/?probe=41d67fcba8) | Jan 29, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [e2fa9aa820](https://linux-hardware.org/?probe=e2fa9aa820) | Jan 29, 2023 |
| ASUSTek       | 1215B                       | [8d26a8d157](https://linux-hardware.org/?probe=8d26a8d157) | Jan 28, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [fb7b1bdaf5](https://linux-hardware.org/?probe=fb7b1bdaf5) | Jan 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [f6d7ba9d48](https://linux-hardware.org/?probe=f6d7ba9d48) | Jan 27, 2023 |
| HP            | EliteBook 640 14 inch G9... | [bbdf827cef](https://linux-hardware.org/?probe=bbdf827cef) | Jan 27, 2023 |
| ASUSTek       | X540SA                      | [93aed28230](https://linux-hardware.org/?probe=93aed28230) | Jan 27, 2023 |
| Kruger&Mat... | KM1406                      | [c944e8058f](https://linux-hardware.org/?probe=c944e8058f) | Jan 27, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [bd7e955a3e](https://linux-hardware.org/?probe=bd7e955a3e) | Jan 27, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [1f74ea5c27](https://linux-hardware.org/?probe=1f74ea5c27) | Jan 27, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | [af3748a4f0](https://linux-hardware.org/?probe=af3748a4f0) | Jan 26, 2023 |
| Acer          | Nitro AN517-55              | [7273b8320c](https://linux-hardware.org/?probe=7273b8320c) | Jan 26, 2023 |
| Lenovo        | ThinkPad T440p 20AWS24B0... | [e4ddea6092](https://linux-hardware.org/?probe=e4ddea6092) | Jan 26, 2023 |
| Acer          | Nitro AN517-55              | [2de4e60fef](https://linux-hardware.org/?probe=2de4e60fef) | Jan 26, 2023 |
| HP            | EliteBook Folio 1040 G1     | [4811286faf](https://linux-hardware.org/?probe=4811286faf) | Jan 26, 2023 |
| Dell          | XPS 9320                    | [a1040b4a3f](https://linux-hardware.org/?probe=a1040b4a3f) | Jan 26, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [26f46d5b40](https://linux-hardware.org/?probe=26f46d5b40) | Jan 25, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [f1e6112f8c](https://linux-hardware.org/?probe=f1e6112f8c) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [baae797a05](https://linux-hardware.org/?probe=baae797a05) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [427a7fa0cb](https://linux-hardware.org/?probe=427a7fa0cb) | Jan 25, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [7fcc3fb992](https://linux-hardware.org/?probe=7fcc3fb992) | Jan 25, 2023 |
| Samsung       | R710                        | [17a3e2ddd9](https://linux-hardware.org/?probe=17a3e2ddd9) | Jan 25, 2023 |
| Dell          | Latitude E6520              | [baf618d1a1](https://linux-hardware.org/?probe=baf618d1a1) | Jan 25, 2023 |
| Dell          | Latitude E6520              | [615879d5e9](https://linux-hardware.org/?probe=615879d5e9) | Jan 24, 2023 |
| Dell          | Latitude 5420               | [cd6dc3695e](https://linux-hardware.org/?probe=cd6dc3695e) | Jan 24, 2023 |
| Lenovo        | ThinkPad T500 2082BPG       | [08a30fd24c](https://linux-hardware.org/?probe=08a30fd24c) | Jan 24, 2023 |
| Dell          | Latitude E5530 non-vPro     | [5ddcb9f78b](https://linux-hardware.org/?probe=5ddcb9f78b) | Jan 23, 2023 |
| Samsung       | 300E4A/300E5A/300E7A        | [c8ec385a88](https://linux-hardware.org/?probe=c8ec385a88) | Jan 23, 2023 |
| Dell          | Latitude 3190               | [7d38c480af](https://linux-hardware.org/?probe=7d38c480af) | Jan 23, 2023 |
| Dell          | Latitude E6500              | [ba7c36fe15](https://linux-hardware.org/?probe=ba7c36fe15) | Jan 23, 2023 |
| Lenovo        | ThinkPad R500 2716W2K       | [ffe1ffc80e](https://linux-hardware.org/?probe=ffe1ffc80e) | Jan 23, 2023 |
| HP            | OMEN by Laptop 17-ck0xxx    | [d3686f2fc3](https://linux-hardware.org/?probe=d3686f2fc3) | Jan 21, 2023 |
| Dell          | Latitude 9420               | [4b847961df](https://linux-hardware.org/?probe=4b847961df) | Jan 21, 2023 |
| Dell          | Latitude 5501               | [72581be7e7](https://linux-hardware.org/?probe=72581be7e7) | Jan 21, 2023 |
| Lenovo        | G560 20042                  | [9c78155cfe](https://linux-hardware.org/?probe=9c78155cfe) | Jan 20, 2023 |
| Lenovo        | G560 20042                  | [61e3ee0517](https://linux-hardware.org/?probe=61e3ee0517) | Jan 20, 2023 |
| HP            | Pavilion dv5                | [94ba65752b](https://linux-hardware.org/?probe=94ba65752b) | Jan 20, 2023 |
| Acer          | Aspire A114-31              | [b341182acd](https://linux-hardware.org/?probe=b341182acd) | Jan 20, 2023 |
| Lenovo        | ThinkPad P51 20HJS1EJ1B     | [2ac4b56c2f](https://linux-hardware.org/?probe=2ac4b56c2f) | Jan 20, 2023 |
| ASUSTek       | ROG Strix G713RM_G713RM     | [844d97dd92](https://linux-hardware.org/?probe=844d97dd92) | Jan 20, 2023 |
| Dell          | Precision M6600             | [4d697ebfd5](https://linux-hardware.org/?probe=4d697ebfd5) | Jan 19, 2023 |
| Dell          | Inspiron 5567               | [a993e95dde](https://linux-hardware.org/?probe=a993e95dde) | Jan 19, 2023 |
| MSI           | Creator Z17 A12UHST         | [1fd7f0acb7](https://linux-hardware.org/?probe=1fd7f0acb7) | Jan 19, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [16f5041f1d](https://linux-hardware.org/?probe=16f5041f1d) | Jan 19, 2023 |
| Lenovo        | Z51-70 80K6                 | [90746298fc](https://linux-hardware.org/?probe=90746298fc) | Jan 19, 2023 |
| Acer          | Aspire A114-31              | [30698dacda](https://linux-hardware.org/?probe=30698dacda) | Jan 19, 2023 |
| Dell          | Latitude 9420               | [3fd325486b](https://linux-hardware.org/?probe=3fd325486b) | Jan 18, 2023 |
| Alienware     | M17xR4                      | [5cce1e5932](https://linux-hardware.org/?probe=5cce1e5932) | Jan 18, 2023 |
| Dell          | Precision 5750              | [592f9624d3](https://linux-hardware.org/?probe=592f9624d3) | Jan 18, 2023 |
| MSI           | GP65 Leopard 10SFK          | [3c09479564](https://linux-hardware.org/?probe=3c09479564) | Jan 18, 2023 |
| Lenovo        | ThinkPad E560 20EV000UUK    | [2ad3913a19](https://linux-hardware.org/?probe=2ad3913a19) | Jan 18, 2023 |
| Lenovo        | ThinkPad E560 20EV000UUK    | [6f463ee96b](https://linux-hardware.org/?probe=6f463ee96b) | Jan 18, 2023 |
| Dell          | Latitude D630               | [0d267a0217](https://linux-hardware.org/?probe=0d267a0217) | Jan 17, 2023 |
| HP            | Pavilion Gaming Notebook    | [03a01ae5f7](https://linux-hardware.org/?probe=03a01ae5f7) | Jan 17, 2023 |
| Lenovo        | ThinkPad E480 20KN0064PB    | [a49c7ed379](https://linux-hardware.org/?probe=a49c7ed379) | Jan 17, 2023 |
| Lenovo        | ThinkPad E480 20KN0064PB    | [9d20f03ffd](https://linux-hardware.org/?probe=9d20f03ffd) | Jan 17, 2023 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [aa6ca0d358](https://linux-hardware.org/?probe=aa6ca0d358) | Jan 17, 2023 |
| ASUSTek       | K53SJ                       | [267ce15a0c](https://linux-hardware.org/?probe=267ce15a0c) | Jan 17, 2023 |
| ASUSTek       | Zenbook UM6702RC_RM6702R... | [21ed6bd75d](https://linux-hardware.org/?probe=21ed6bd75d) | Jan 17, 2023 |
| Dell          | Inspiron 3583               | [79b74ef79b](https://linux-hardware.org/?probe=79b74ef79b) | Jan 16, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [11ca9b863c](https://linux-hardware.org/?probe=11ca9b863c) | Jan 16, 2023 |
| Dell          | Inspiron 11 - 3147          | [af542a44ad](https://linux-hardware.org/?probe=af542a44ad) | Jan 16, 2023 |
| Dell          | Latitude 3190               | [96d1e3a219](https://linux-hardware.org/?probe=96d1e3a219) | Jan 16, 2023 |
| Lenovo        | ThinkPad T460s 20FAS5QW0... | [dd953776aa](https://linux-hardware.org/?probe=dd953776aa) | Jan 16, 2023 |
| Lenovo        | ThinkPad T510 4384FF3       | [b62dac21bd](https://linux-hardware.org/?probe=b62dac21bd) | Jan 15, 2023 |
| Chuwi         | AeroBook Pro                | [13da35b0f7](https://linux-hardware.org/?probe=13da35b0f7) | Jan 15, 2023 |
| ASUSTek       | X510UQR                     | [2fb1d0a04c](https://linux-hardware.org/?probe=2fb1d0a04c) | Jan 14, 2023 |
| Acer          | AO725                       | [739986d5fa](https://linux-hardware.org/?probe=739986d5fa) | Jan 14, 2023 |
| Lenovo        | G585                        | [c7453a5e19](https://linux-hardware.org/?probe=c7453a5e19) | Jan 14, 2023 |
| MSI           | GE70 2QD                    | [5e408d7d3d](https://linux-hardware.org/?probe=5e408d7d3d) | Jan 14, 2023 |
| Dell          | Vostro 3550                 | [3f68ef3681](https://linux-hardware.org/?probe=3f68ef3681) | Jan 13, 2023 |
| HP            | EliteBook 8570w             | [84035db95c](https://linux-hardware.org/?probe=84035db95c) | Jan 13, 2023 |
| Samsung       | SR700                       | [329a7864c0](https://linux-hardware.org/?probe=329a7864c0) | Jan 13, 2023 |
| HP            | Notebook                    | [3fc38fa55e](https://linux-hardware.org/?probe=3fc38fa55e) | Jan 13, 2023 |
| Kiano         | Elegance 13.3               | [2e77ce51b9](https://linux-hardware.org/?probe=2e77ce51b9) | Jan 13, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [05899ebb86](https://linux-hardware.org/?probe=05899ebb86) | Jan 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [4236e82f21](https://linux-hardware.org/?probe=4236e82f21) | Jan 13, 2023 |
| HP            | ProBook 450 G6              | [f675188c46](https://linux-hardware.org/?probe=f675188c46) | Jan 12, 2023 |
| MSI           | GE70 2QD                    | [8dce1e9fdd](https://linux-hardware.org/?probe=8dce1e9fdd) | Jan 12, 2023 |
| Lenovo        | Legion Y740S-15IMH 81YX     | [b61eb04be5](https://linux-hardware.org/?probe=b61eb04be5) | Jan 11, 2023 |
| Sony          | VPCEJ2S1E                   | [f387a3dcf6](https://linux-hardware.org/?probe=f387a3dcf6) | Jan 11, 2023 |
| MSI           | GL75 9SE                    | [e3478b20bd](https://linux-hardware.org/?probe=e3478b20bd) | Jan 11, 2023 |
| ASUSTek       | 1215N                       | [140d48870a](https://linux-hardware.org/?probe=140d48870a) | Jan 11, 2023 |
| ASUSTek       | 1215N                       | [f6588e6319](https://linux-hardware.org/?probe=f6588e6319) | Jan 11, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b828defe64](https://linux-hardware.org/?probe=b828defe64) | Jan 11, 2023 |
| Dell          | Latitude D630               | [64877fdf78](https://linux-hardware.org/?probe=64877fdf78) | Jan 11, 2023 |
| ASUSTek       | X550CC                      | [2aa757ef35](https://linux-hardware.org/?probe=2aa757ef35) | Jan 10, 2023 |
| Samsung       | 550P5C/550P7C               | [33529c6c45](https://linux-hardware.org/?probe=33529c6c45) | Jan 10, 2023 |
| Acer          | Extensa 2540                | [6bddd00c3f](https://linux-hardware.org/?probe=6bddd00c3f) | Jan 10, 2023 |
| Dell          | Latitude E4310              | [1cd2d3300a](https://linux-hardware.org/?probe=1cd2d3300a) | Jan 09, 2023 |
| Dell          | Latitude E5470              | [41c1a02ca6](https://linux-hardware.org/?probe=41c1a02ca6) | Jan 09, 2023 |
| Chuwi         | GemiBook                    | [918dc5f283](https://linux-hardware.org/?probe=918dc5f283) | Jan 09, 2023 |
| Lenovo        | ThinkPad X201 3626D15       | [3d615a1b12](https://linux-hardware.org/?probe=3d615a1b12) | Jan 09, 2023 |
| Dell          | Latitude 3190               | [055e045e52](https://linux-hardware.org/?probe=055e045e52) | Jan 09, 2023 |
| MSI           | GT680R/GX680R/GT683R/GT6... | [0b23cb61e0](https://linux-hardware.org/?probe=0b23cb61e0) | Jan 09, 2023 |
| Samsung       | R780/R778                   | [e26d6dd084](https://linux-hardware.org/?probe=e26d6dd084) | Jan 08, 2023 |
| Acer          | Aspire one 1-131            | [06c3411258](https://linux-hardware.org/?probe=06c3411258) | Jan 08, 2023 |
| Lenovo        | G51-35 80M8                 | [fe19098e1d](https://linux-hardware.org/?probe=fe19098e1d) | Jan 08, 2023 |
| Acer          | Aspire A315-41              | [b4ed141fd3](https://linux-hardware.org/?probe=b4ed141fd3) | Jan 08, 2023 |
| Lenovo        | ThinkPad T460 20FMS0BX0T    | [e05bd2254f](https://linux-hardware.org/?probe=e05bd2254f) | Jan 08, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [de3c61df29](https://linux-hardware.org/?probe=de3c61df29) | Jan 08, 2023 |
| HP            | 655                         | [4c7544d7ad](https://linux-hardware.org/?probe=4c7544d7ad) | Jan 08, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | [1ad8a2f766](https://linux-hardware.org/?probe=1ad8a2f766) | Jan 08, 2023 |
| HP            | ENVY m6                     | [b5089c7b29](https://linux-hardware.org/?probe=b5089c7b29) | Jan 07, 2023 |
| HP            | ProBook 5330m               | [37416931cd](https://linux-hardware.org/?probe=37416931cd) | Jan 07, 2023 |
| Lenovo        | S145-15API 81UT             | [fafc9e3fb7](https://linux-hardware.org/?probe=fafc9e3fb7) | Jan 07, 2023 |
| Apple         | MacBookPro9,2               | [e0e6ab58b6](https://linux-hardware.org/?probe=e0e6ab58b6) | Jan 06, 2023 |
| Dell          | Latitude E6520              | [96679022de](https://linux-hardware.org/?probe=96679022de) | Jan 06, 2023 |
| MSI           | Creator Z17 A12UHST         | [d0299b2518](https://linux-hardware.org/?probe=d0299b2518) | Jan 06, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [c84d3b6b03](https://linux-hardware.org/?probe=c84d3b6b03) | Jan 06, 2023 |
| Lenovo        | Legion 5 17ACH6 82K0        | [9a108faf93](https://linux-hardware.org/?probe=9a108faf93) | Jan 06, 2023 |
| MSI           | GP76 Leopard 10UE           | [117e9ffed7](https://linux-hardware.org/?probe=117e9ffed7) | Jan 06, 2023 |
| MSI           | GP76 Leopard 10UE           | [cacdaaf5c5](https://linux-hardware.org/?probe=cacdaaf5c5) | Jan 05, 2023 |
| Acer          | NG-A715-72G-70F7            | [bbedda14e5](https://linux-hardware.org/?probe=bbedda14e5) | Jan 05, 2023 |
| Acer          | NG-A715-72G-70F7            | [d2c2a681a2](https://linux-hardware.org/?probe=d2c2a681a2) | Jan 05, 2023 |
| Acer          | Aspire A715-74G             | [e0cf0ea368](https://linux-hardware.org/?probe=e0cf0ea368) | Jan 05, 2023 |
| Lenovo        | ThinkPad T460s 20FAS5QW0... | [4853686d6c](https://linux-hardware.org/?probe=4853686d6c) | Jan 05, 2023 |
| ASUSTek       | K55VM                       | [d4d53ed49f](https://linux-hardware.org/?probe=d4d53ed49f) | Jan 04, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [307c51149d](https://linux-hardware.org/?probe=307c51149d) | Jan 03, 2023 |
| Acer          | Nitro AN515-55              | [c5bc3a8eae](https://linux-hardware.org/?probe=c5bc3a8eae) | Jan 03, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [1a3964dd30](https://linux-hardware.org/?probe=1a3964dd30) | Jan 03, 2023 |
| Dell          | XPS 13 7390                 | [b45f76c172](https://linux-hardware.org/?probe=b45f76c172) | Jan 03, 2023 |
| Lenovo        | ThinkPad T460s 20FAS5QW0... | [373efc41b0](https://linux-hardware.org/?probe=373efc41b0) | Jan 03, 2023 |
| Fujitsu       | LIFEBOOK S751               | [5fbed33610](https://linux-hardware.org/?probe=5fbed33610) | Jan 03, 2023 |
| Lenovo        | IdeaPad S540-14IWL 81ND     | [99ba91623a](https://linux-hardware.org/?probe=99ba91623a) | Jan 02, 2023 |
| Acer          | Aspire E1-571               | [eb3f1a0f5f](https://linux-hardware.org/?probe=eb3f1a0f5f) | Jan 02, 2023 |
| Dell          | Latitude 3190               | [19f42109a3](https://linux-hardware.org/?probe=19f42109a3) | Jan 02, 2023 |
| MSI           | PE60 6QE                    | [c331237e28](https://linux-hardware.org/?probe=c331237e28) | Jan 02, 2023 |
| MSI           | PE60 6QE                    | [1ce680cb4d](https://linux-hardware.org/?probe=1ce680cb4d) | Jan 01, 2023 |
| Gigabyte      | RC14UD                      | [24d32a2b05](https://linux-hardware.org/?probe=24d32a2b05) | Jan 01, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | [48c688033a](https://linux-hardware.org/?probe=48c688033a) | Dec 30, 2022 |
| ASUSTek       | K72F                        | [f761bf9bd6](https://linux-hardware.org/?probe=f761bf9bd6) | Dec 30, 2022 |
| Lenovo        | ThinkPad R61 8918DEG        | [82cbc15539](https://linux-hardware.org/?probe=82cbc15539) | Dec 30, 2022 |
| HP            | EliteBook 745 G5            | [d819dbd901](https://linux-hardware.org/?probe=d819dbd901) | Dec 30, 2022 |
| HP            | ProBook 450 G7              | [ca7468f975](https://linux-hardware.org/?probe=ca7468f975) | Dec 29, 2022 |
| Dell          | Latitude E6420              | [9733c425b6](https://linux-hardware.org/?probe=9733c425b6) | Dec 29, 2022 |
| Lenovo        | Y50-70 20378                | [fe7926d39a](https://linux-hardware.org/?probe=fe7926d39a) | Dec 28, 2022 |
| Dell          | Inspiron 3583               | [41c7a16579](https://linux-hardware.org/?probe=41c7a16579) | Dec 28, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [27e072cb3e](https://linux-hardware.org/?probe=27e072cb3e) | Dec 28, 2022 |
| Lenovo        | Y50-70 20378                | [e232c2de6d](https://linux-hardware.org/?probe=e232c2de6d) | Dec 28, 2022 |
| HP            | EliteBook 745 G3            | [1ca2f43148](https://linux-hardware.org/?probe=1ca2f43148) | Dec 27, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [03cca95360](https://linux-hardware.org/?probe=03cca95360) | Dec 27, 2022 |
| HP            | EliteBook 820 G3            | [95555948a2](https://linux-hardware.org/?probe=95555948a2) | Dec 27, 2022 |
| Acer          | Nitro AN515-44              | [58b02cceb0](https://linux-hardware.org/?probe=58b02cceb0) | Dec 27, 2022 |
| Dell          | Latitude 3190               | [f395b56cec](https://linux-hardware.org/?probe=f395b56cec) | Dec 26, 2022 |
| ASUSTek       | X550LD                      | [e0a09344e0](https://linux-hardware.org/?probe=e0a09344e0) | Dec 26, 2022 |
| ASUSTek       | X550LD                      | [d6948e7207](https://linux-hardware.org/?probe=d6948e7207) | Dec 26, 2022 |
| Acer          | Nitro AN515-31              | [249f50d430](https://linux-hardware.org/?probe=249f50d430) | Dec 25, 2022 |
| Lenovo        | ThinkPad T430 23472Y0       | [4a2d13391c](https://linux-hardware.org/?probe=4a2d13391c) | Dec 25, 2022 |
| GPU Compan... | GWTN141-10                  | [38ed4755c3](https://linux-hardware.org/?probe=38ed4755c3) | Dec 24, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [af18889189](https://linux-hardware.org/?probe=af18889189) | Dec 23, 2022 |
| HP            | 255 G7 Notebook PC          | [5bedf1557b](https://linux-hardware.org/?probe=5bedf1557b) | Dec 23, 2022 |
| Fujitsu       | LIFEBOOK S751               | [f3dc3c0121](https://linux-hardware.org/?probe=f3dc3c0121) | Dec 22, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [bf600b6f1c](https://linux-hardware.org/?probe=bf600b6f1c) | Dec 22, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | [06d78a17c1](https://linux-hardware.org/?probe=06d78a17c1) | Dec 21, 2022 |
| Dell          | Precision 3520              | [1763494294](https://linux-hardware.org/?probe=1763494294) | Dec 21, 2022 |
| Sony          | SVE1112M1EB                 | [74e100e63b](https://linux-hardware.org/?probe=74e100e63b) | Dec 21, 2022 |
| ASUSTek       | N55SF                       | [b1d6a6a73d](https://linux-hardware.org/?probe=b1d6a6a73d) | Dec 21, 2022 |
| ASUSTek       | N55SF                       | [bbec56fa90](https://linux-hardware.org/?probe=bbec56fa90) | Dec 21, 2022 |
| Dell          | G15 5510                    | [86d0642973](https://linux-hardware.org/?probe=86d0642973) | Dec 20, 2022 |
| ASUSTek       | TUF Gaming FX505GE          | [094e72dc22](https://linux-hardware.org/?probe=094e72dc22) | Dec 20, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [0d59e38c20](https://linux-hardware.org/?probe=0d59e38c20) | Dec 20, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [37513092d6](https://linux-hardware.org/?probe=37513092d6) | Dec 20, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [03e2c64868](https://linux-hardware.org/?probe=03e2c64868) | Dec 20, 2022 |
| Dell          | Vostro 15 3510              | [f2467d713d](https://linux-hardware.org/?probe=f2467d713d) | Dec 19, 2022 |
| Dell          | Latitude 3190               | [9227c8dbfb](https://linux-hardware.org/?probe=9227c8dbfb) | Dec 19, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [44a96b54b6](https://linux-hardware.org/?probe=44a96b54b6) | Dec 18, 2022 |
| Apple         | MacBookPro14,1              | [8c0c2353ab](https://linux-hardware.org/?probe=8c0c2353ab) | Dec 18, 2022 |
| Valve         | Jupiter                     | [72f897b9d3](https://linux-hardware.org/?probe=72f897b9d3) | Dec 17, 2022 |
| Toshiba       | Satellite L650              | [7ea253aa11](https://linux-hardware.org/?probe=7ea253aa11) | Dec 17, 2022 |
| Apple         | MacBookPro11,1              | [d3517edb25](https://linux-hardware.org/?probe=d3517edb25) | Dec 17, 2022 |
| Dell          | Latitude E6330              | [ca6551bf8e](https://linux-hardware.org/?probe=ca6551bf8e) | Dec 17, 2022 |
| Dell          | Latitude E5570              | [cc58177561](https://linux-hardware.org/?probe=cc58177561) | Dec 17, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | [0d7a54bc21](https://linux-hardware.org/?probe=0d7a54bc21) | Dec 16, 2022 |
| Dell          | Latitude E6410              | [173f8a8dc8](https://linux-hardware.org/?probe=173f8a8dc8) | Dec 16, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | [4f63e7b8d1](https://linux-hardware.org/?probe=4f63e7b8d1) | Dec 15, 2022 |
| Dell          | Latitude 5420               | [5fa4cbba73](https://linux-hardware.org/?probe=5fa4cbba73) | Dec 15, 2022 |
| Lenovo        | ThinkPad T530 24295XU       | [0ebd945403](https://linux-hardware.org/?probe=0ebd945403) | Dec 15, 2022 |
| Gigabyte      | MMLP3AP-00                  | [6b53aab624](https://linux-hardware.org/?probe=6b53aab624) | Dec 14, 2022 |
| Google        | Ultima                      | [867abc2b8f](https://linux-hardware.org/?probe=867abc2b8f) | Dec 14, 2022 |
| ASUSTek       | M3N                         | [4e9f8e4c01](https://linux-hardware.org/?probe=4e9f8e4c01) | Dec 14, 2022 |
| Dell          | Inspiron 3451               | [de7f9d5e33](https://linux-hardware.org/?probe=de7f9d5e33) | Dec 14, 2022 |
| Dell          | XPS L501X                   | [f540185d6c](https://linux-hardware.org/?probe=f540185d6c) | Dec 14, 2022 |
| Dell          | XPS L501X                   | [32e195f4c6](https://linux-hardware.org/?probe=32e195f4c6) | Dec 14, 2022 |
| ASUSTek       | M3N                         | [ff772de294](https://linux-hardware.org/?probe=ff772de294) | Dec 13, 2022 |
| HUAWEI        | HVY-WXX9                    | [37284f659a](https://linux-hardware.org/?probe=37284f659a) | Dec 13, 2022 |
| MSI           | Creator Z17 A12UHST         | [61685b4f1a](https://linux-hardware.org/?probe=61685b4f1a) | Dec 12, 2022 |
| Dell          | Latitude 5411               | [af806502e8](https://linux-hardware.org/?probe=af806502e8) | Dec 12, 2022 |
| Dell          | Latitude 5411               | [334ca886a4](https://linux-hardware.org/?probe=334ca886a4) | Dec 12, 2022 |
| HP            | Pavilion dv7                | [1e10e0306f](https://linux-hardware.org/?probe=1e10e0306f) | Dec 12, 2022 |
| Dell          | Latitude 3190               | [c2c5f3feb3](https://linux-hardware.org/?probe=c2c5f3feb3) | Dec 12, 2022 |
| Apple         | MacBookPro11,1              | [492b382af1](https://linux-hardware.org/?probe=492b382af1) | Dec 11, 2022 |
| HP            | EliteBook 830 G6            | [cea4c76b9d](https://linux-hardware.org/?probe=cea4c76b9d) | Dec 11, 2022 |
| Samsung       | 270E5G/270E5U               | [93075de512](https://linux-hardware.org/?probe=93075de512) | Dec 08, 2022 |
| MSI           | Vector GP76 12UGS           | [d6c55a874f](https://linux-hardware.org/?probe=d6c55a874f) | Dec 08, 2022 |
| Google        | Glimmer                     | [ad4b3f5575](https://linux-hardware.org/?probe=ad4b3f5575) | Dec 08, 2022 |
| Apple         | MacBookPro12,1              | [e15b555b1a](https://linux-hardware.org/?probe=e15b555b1a) | Dec 07, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [3a9774bdac](https://linux-hardware.org/?probe=3a9774bdac) | Dec 07, 2022 |
| Dell          | Latitude 5480               | [0cd7d6e4c0](https://linux-hardware.org/?probe=0cd7d6e4c0) | Dec 07, 2022 |
| Panasonic     | CFMX4-1                     | [c25c16fc1a](https://linux-hardware.org/?probe=c25c16fc1a) | Dec 06, 2022 |
| Dell          | Latitude E7440              | [9a859c9a5d](https://linux-hardware.org/?probe=9a859c9a5d) | Dec 06, 2022 |
| Dell          | Latitude 5310               | [06d96a49a1](https://linux-hardware.org/?probe=06d96a49a1) | Dec 06, 2022 |
| Dell          | Latitude E7440              | [63b84a9439](https://linux-hardware.org/?probe=63b84a9439) | Dec 06, 2022 |
| HP            | EliteBook 8470p             | [e2be1fe149](https://linux-hardware.org/?probe=e2be1fe149) | Dec 06, 2022 |
| Dell          | Latitude 5411               | [62e5941721](https://linux-hardware.org/?probe=62e5941721) | Dec 06, 2022 |
| Dell          | Latitude 5411               | [e0815067bd](https://linux-hardware.org/?probe=e0815067bd) | Dec 06, 2022 |
| Dell          | Latitude 5310               | [f3801600ff](https://linux-hardware.org/?probe=f3801600ff) | Dec 06, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [119ec75a5f](https://linux-hardware.org/?probe=119ec75a5f) | Dec 05, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [36985fd47e](https://linux-hardware.org/?probe=36985fd47e) | Dec 05, 2022 |
| Apple         | MacBookPro11,1              | [5b0565920f](https://linux-hardware.org/?probe=5b0565920f) | Dec 05, 2022 |
| ASUSTek       | X555LJ                      | [a849daba2b](https://linux-hardware.org/?probe=a849daba2b) | Dec 05, 2022 |
| Dell          | Latitude 3190               | [12975376ba](https://linux-hardware.org/?probe=12975376ba) | Dec 05, 2022 |
| MSI           | GF63 Thin 9RCX              | [1bf4364f61](https://linux-hardware.org/?probe=1bf4364f61) | Dec 05, 2022 |
| GMKtec        | NucBox5                     | [cdfbbcc5b2](https://linux-hardware.org/?probe=cdfbbcc5b2) | Dec 04, 2022 |
| Lenovo        | G770 20089                  | [d35d60f972](https://linux-hardware.org/?probe=d35d60f972) | Dec 04, 2022 |
| MSI           | Creator Z17 A12UHST         | [afbbf473b9](https://linux-hardware.org/?probe=afbbf473b9) | Dec 04, 2022 |
| Dell          | Vostro 5471                 | [0bad01b327](https://linux-hardware.org/?probe=0bad01b327) | Dec 04, 2022 |
| HP            | Pavilion dv7                | [90c7688386](https://linux-hardware.org/?probe=90c7688386) | Dec 04, 2022 |
| Google        | Lars                        | [efe9cef4b9](https://linux-hardware.org/?probe=efe9cef4b9) | Dec 04, 2022 |
| Dell          | XPS 15 9570                 | [ec5047129a](https://linux-hardware.org/?probe=ec5047129a) | Dec 03, 2022 |
| HP            | Pavilion dv7                | [c398cf4372](https://linux-hardware.org/?probe=c398cf4372) | Dec 03, 2022 |
| HP            | Pavilion dv7                | [e34ad54f3b](https://linux-hardware.org/?probe=e34ad54f3b) | Dec 03, 2022 |
| Google        | Lars                        | [ad022bfd93](https://linux-hardware.org/?probe=ad022bfd93) | Dec 03, 2022 |
| Dell          | G15 5515                    | [218e5c2825](https://linux-hardware.org/?probe=218e5c2825) | Dec 03, 2022 |
| Dell          | Latitude 5480               | [4eba5810d7](https://linux-hardware.org/?probe=4eba5810d7) | Dec 03, 2022 |
| Dell          | Vostro 5502                 | [86341e8306](https://linux-hardware.org/?probe=86341e8306) | Dec 02, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [4d33c2ab30](https://linux-hardware.org/?probe=4d33c2ab30) | Dec 02, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [929550dc41](https://linux-hardware.org/?probe=929550dc41) | Dec 01, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [615b292682](https://linux-hardware.org/?probe=615b292682) | Dec 01, 2022 |
| HP            | Pavilion dv7                | [aa6cdce8f8](https://linux-hardware.org/?probe=aa6cdce8f8) | Dec 01, 2022 |
| Lenovo        | IdeaPad 310-15IAP 80TT      | [3aa3302b92](https://linux-hardware.org/?probe=3aa3302b92) | Nov 30, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [c3d55f501c](https://linux-hardware.org/?probe=c3d55f501c) | Nov 30, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [f4de100586](https://linux-hardware.org/?probe=f4de100586) | Nov 29, 2022 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [802af80043](https://linux-hardware.org/?probe=802af80043) | Nov 29, 2022 |
| HP            | Pavilion dv7                | [1ba2fdd19b](https://linux-hardware.org/?probe=1ba2fdd19b) | Nov 29, 2022 |
| Dell          | Latitude E6540              | [48c805974c](https://linux-hardware.org/?probe=48c805974c) | Nov 29, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [9c45563fb6](https://linux-hardware.org/?probe=9c45563fb6) | Nov 29, 2022 |
| HP            | Pavilion dv7                | [db7897d2fc](https://linux-hardware.org/?probe=db7897d2fc) | Nov 28, 2022 |
| HP            | ProBook 640 G2              | [56ceffe338](https://linux-hardware.org/?probe=56ceffe338) | Nov 28, 2022 |
| Dell          | Latitude 3190               | [3c4756b965](https://linux-hardware.org/?probe=3c4756b965) | Nov 28, 2022 |
| HUAWEI        | MRC-WX0                     | [98f550465b](https://linux-hardware.org/?probe=98f550465b) | Nov 28, 2022 |
| Valve         | Jupiter                     | [ef85b8ab38](https://linux-hardware.org/?probe=ef85b8ab38) | Nov 28, 2022 |
| Valve         | Jupiter                     | [622315486c](https://linux-hardware.org/?probe=622315486c) | Nov 28, 2022 |
| ASUSTek       | G75VX                       | [87ef485975](https://linux-hardware.org/?probe=87ef485975) | Nov 27, 2022 |
| Acer          | AO722                       | [fb75768c70](https://linux-hardware.org/?probe=fb75768c70) | Nov 26, 2022 |
| HP            | ProBook 6470b               | [c8da54315e](https://linux-hardware.org/?probe=c8da54315e) | Nov 26, 2022 |
| Dell          | Latitude E6220              | [aa8d2d2fc7](https://linux-hardware.org/?probe=aa8d2d2fc7) | Nov 26, 2022 |
| Dell          | Vostro 5471                 | [7a6ec88b73](https://linux-hardware.org/?probe=7a6ec88b73) | Nov 26, 2022 |
| Dell          | Vostro 5471                 | [b9bbfd7551](https://linux-hardware.org/?probe=b9bbfd7551) | Nov 26, 2022 |
| Lenovo        | B51-80 80LM                 | [848b6ab7b3](https://linux-hardware.org/?probe=848b6ab7b3) | Nov 26, 2022 |
| Lenovo        | B51-80 80LM                 | [c34893c661](https://linux-hardware.org/?probe=c34893c661) | Nov 26, 2022 |
| Valve         | Jupiter                     | [7412d8b03b](https://linux-hardware.org/?probe=7412d8b03b) | Nov 26, 2022 |
| Valve         | Jupiter                     | [24d078fe91](https://linux-hardware.org/?probe=24d078fe91) | Nov 26, 2022 |
| Dell          | Latitude E6420              | [c3e8903f19](https://linux-hardware.org/?probe=c3e8903f19) | Nov 25, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [4261949a3e](https://linux-hardware.org/?probe=4261949a3e) | Nov 25, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [8acafcf4ab](https://linux-hardware.org/?probe=8acafcf4ab) | Nov 25, 2022 |
| Dell          | Inspiron 14 Plus 7420       | [a35ca4bbbe](https://linux-hardware.org/?probe=a35ca4bbbe) | Nov 24, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Poland/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 347       | 10.78%  |
| OpenMandriva 4.2             | 187       | 5.81%   |
| Ubuntu 18.04                 | 166       | 5.16%   |
| Ubuntu 22.04                 | 161       | 5%      |
| OpenMandriva 4.3             | 109       | 3.39%   |
| Debian 11                    | 98        | 3.04%   |
| Arch Rolling                 | 64        | 1.99%   |
| OpenMandriva 23.03           | 57        | 1.77%   |
| OpenMandriva 23.01           | 55        | 1.71%   |
| Linux Mint 21.1              | 53        | 1.65%   |
| ROSA R10                     | 50        | 1.55%   |
| Linux Mint 20.3              | 45        | 1.4%    |
| Linux Mint 20.1              | 42        | 1.3%    |
| Arch                         | 42        | 1.3%    |
| KDE neon 20.04               | 40        | 1.24%   |
| Fedora 37                    | 40        | 1.24%   |
| Zorin 16                     | 39        | 1.21%   |
| ROSA R9                      | 39        | 1.21%   |
| Manjaro                      | 38        | 1.18%   |
| ROSA R11.1                   | 36        | 1.12%   |
| Fedora 36                    | 36        | 1.12%   |
| Ubuntu 20.10                 | 33        | 1.03%   |
| Linux Mint 20.2              | 33        | 1.03%   |
| Ubuntu 21.04                 | 32        | 0.99%   |
| Linux Mint 19.3              | 31        | 0.96%   |
| Ubuntu 22.10                 | 30        | 0.93%   |
| ROSA R11                     | 29        | 0.9%    |
| Fedora 38                    | 29        | 0.9%    |
| Pop!_OS 22.04                | 28        | 0.87%   |
| Zorin 15                     | 27        | 0.84%   |
| Ubuntu 19.10                 | 27        | 0.84%   |
| Linux Mint 20                | 27        | 0.84%   |
| Ubuntu 21.10                 | 26        | 0.81%   |
| Linux Mint 21                | 26        | 0.81%   |
| Xubuntu 20.04                | 25        | 0.78%   |
| ROSA R8                      | 25        | 0.78%   |
| Fedora 33                    | 25        | 0.78%   |
| openSUSE Tumbleweed-XXXXXXXX | 24        | 0.75%   |
| Fedora 32                    | 24        | 0.75%   |
| Debian 10                    | 24        | 0.75%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 832       | 27.56%  |
| OpenMandriva  | 417       | 13.81%  |
| Linux Mint    | 260       | 8.61%   |
| Fedora        | 209       | 6.92%   |
| ROSA          | 187       | 6.19%   |
| Debian        | 155       | 5.13%   |
| Manjaro       | 114       | 3.78%   |
| Arch          | 102       | 3.38%   |
| Pop!_OS       | 81        | 2.68%   |
| Zorin         | 69        | 2.29%   |
| KDE neon      | 58        | 1.92%   |
| Kubuntu       | 56        | 1.85%   |
| Xubuntu       | 50        | 1.66%   |
| Kali          | 39        | 1.29%   |
| openSUSE      | 29        | 0.96%   |
| Lubuntu       | 27        | 0.89%   |
| Elementary    | 24        | 0.79%   |
| Endless       | 23        | 0.76%   |
| ArcoLinux     | 23        | 0.76%   |
| SteamOS       | 22        | 0.73%   |
| Gentoo        | 22        | 0.73%   |
| LMDE          | 20        | 0.66%   |
| EndeavourOS   | 19        | 0.63%   |
| Nobara        | 13        | 0.43%   |
| Clear Linux   | 13        | 0.43%   |
| Ubuntu Unity  | 11        | 0.36%   |
| Ubuntu MATE   | 10        | 0.33%   |
| MX            | 10        | 0.33%   |
| Garuda Linux  | 10        | 0.33%   |
| Ubuntu Budgie | 9         | 0.3%    |
| LinuxFX       | 8         | 0.26%   |
| Peppermint    | 7         | 0.23%   |
| BlackPanther  | 7         | 0.23%   |
| CentOS        | 5         | 0.17%   |
| Xero          | 4         | 0.13%   |
| Parrot        | 4         | 0.13%   |
| NixOS         | 4         | 0.13%   |
| Linux Lite    | 4         | 0.13%   |
| EuroLinux     | 4         | 0.13%   |
| Sparky        | 3         | 0.1%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002        | 177       | 5.02%   |
| 5.16.7-desktop-1omv4003         | 106       | 3.01%   |
| 6.2.6-desktop-1omv2390          | 55        | 1.56%   |
| 6.1.1-desktop-1omv2290          | 52        | 1.48%   |
| 5.4.0-42-generic                | 44        | 1.25%   |
| 5.15.0-56-generic               | 42        | 1.19%   |
| 5.15.0-58-generic               | 27        | 0.77%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 26        | 0.74%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 24        | 0.68%   |
| 5.4.0-52-generic                | 22        | 0.62%   |
| 5.4.0-48-generic                | 22        | 0.62%   |
| 5.15.0-43-generic               | 22        | 0.62%   |
| 5.15.0-52-generic               | 21        | 0.6%    |
| 5.4.0-29-generic                | 20        | 0.57%   |
| 5.19.0-35-generic               | 20        | 0.57%   |
| 5.4.0-58-generic                | 19        | 0.54%   |
| 5.4.0-26-generic                | 19        | 0.54%   |
| 5.3.0-46-generic                | 18        | 0.51%   |
| 5.15.0-53-generic               | 18        | 0.51%   |
| 5.4.0-33-generic                | 17        | 0.48%   |
| 5.19.0-32-generic               | 17        | 0.48%   |
| 5.11.0-37-generic               | 17        | 0.48%   |
| 5.0.0-37-generic                | 17        | 0.48%   |
| 5.8.0-43-generic                | 16        | 0.45%   |
| 5.4.0-54-generic                | 16        | 0.45%   |
| 5.15.0-48-generic               | 16        | 0.45%   |
| 4.15.0-desktop-45.1rosa-x86_64  | 16        | 0.45%   |
| 4.1.34-nrj-desktop-2rosa-x86_64 | 16        | 0.45%   |
| 5.4.0-40-generic                | 14        | 0.4%    |
| 5.4.0-37-generic                | 14        | 0.4%    |
| 5.3.0-40-generic                | 14        | 0.4%    |
| 5.4.0-91-generic                | 13        | 0.37%   |
| 5.3.0-42-generic                | 13        | 0.37%   |
| 5.15.0-60-generic               | 13        | 0.37%   |
| 5.13.0-39-generic               | 13        | 0.37%   |
| 5.13.0-27-generic               | 13        | 0.37%   |
| 5.11.0-43-generic               | 13        | 0.37%   |
| 5.11.0-27-generic               | 13        | 0.37%   |
| 5.11.0-25-generic               | 13        | 0.37%   |
| 4.15.0-43-generic               | 13        | 0.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 446       | 13.33%  |
| 5.15.0  | 272       | 8.13%   |
| 5.10.14 | 178       | 5.32%   |
| 4.15.0  | 150       | 4.48%   |
| 5.11.0  | 144       | 4.3%    |
| 5.8.0   | 129       | 3.85%   |
| 5.13.0  | 124       | 3.7%    |
| 5.10.0  | 114       | 3.41%   |
| 5.16.7  | 107       | 3.2%    |
| 5.3.0   | 103       | 3.08%   |
| 5.19.0  | 103       | 3.08%   |
| 6.2.6   | 70        | 2.09%   |
| 5.0.0   | 61        | 1.82%   |
| 4.18.0  | 59        | 1.76%   |
| 6.1.1   | 53        | 1.58%   |
| 4.9.20  | 35        | 1.05%   |
| 4.9.60  | 32        | 0.96%   |
| 4.19.0  | 31        | 0.93%   |
| 6.1.0   | 30        | 0.9%    |
| 5.14.0  | 29        | 0.87%   |
| 4.1.34  | 22        | 0.66%   |
| 6.2.0   | 20        | 0.6%    |
| 6.0.0   | 18        | 0.54%   |
| 5.11.12 | 14        | 0.42%   |
| 4.1.38  | 14        | 0.42%   |
| 5.17.0  | 12        | 0.36%   |
| 6.0.7   | 11        | 0.33%   |
| 5.9.0   | 11        | 0.33%   |
| 5.4.32  | 11        | 0.33%   |
| 5.17.5  | 11        | 0.33%   |
| 6.3.5   | 9         | 0.27%   |
| 6.2.11  | 9         | 0.27%   |
| 5.16.0  | 9         | 0.27%   |
| 5.5.0   | 8         | 0.24%   |
| 5.4.83  | 8         | 0.24%   |
| 4.9.76  | 8         | 0.24%   |
| 6.1.8   | 7         | 0.21%   |
| 6.1.12  | 7         | 0.21%   |
| 6.1.10  | 7         | 0.21%   |
| 6.0.12  | 7         | 0.21%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 505       | 15.41%  |
| 5.10    | 346       | 10.56%  |
| 5.15    | 338       | 10.31%  |
| 5.11    | 182       | 5.55%   |
| 5.16    | 162       | 4.94%   |
| 5.8     | 160       | 4.88%   |
| 4.15    | 150       | 4.58%   |
| 6.1     | 144       | 4.39%   |
| 5.13    | 141       | 4.3%    |
| 6.2     | 140       | 4.27%   |
| 5.19    | 139       | 4.24%   |
| 5.3     | 116       | 3.54%   |
| 4.9     | 101       | 3.08%   |
| 6.0     | 74        | 2.26%   |
| 5.0     | 67        | 2.04%   |
| 5.14    | 62        | 1.89%   |
| 4.18    | 62        | 1.89%   |
| 5.17    | 49        | 1.5%    |
| 5.9     | 42        | 1.28%   |
| 5.6     | 42        | 1.28%   |
| 5.18    | 40        | 1.22%   |
| 4.19    | 37        | 1.13%   |
| 6.3     | 36        | 1.1%    |
| 4.1     | 35        | 1.07%   |
| 5.12    | 25        | 0.76%   |
| 5.5     | 23        | 0.7%    |
| 5.7     | 20        | 0.61%   |
| 4.4     | 8         | 0.24%   |
| 6.4     | 7         | 0.21%   |
| 5.1     | 6         | 0.18%   |
| 5.2     | 4         | 0.12%   |
| 3.10    | 4         | 0.12%   |
| 4.20    | 2         | 0.06%   |
| 4.13    | 2         | 0.06%   |
| 4.10    | 2         | 0.06%   |
| 4.17    | 1         | 0.03%   |
| 4.14    | 1         | 0.03%   |
| 4.12    | 1         | 0.03%   |
| 4.11    | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 2789      | 96.21%  |
| i686    | 109       | 3.76%   |
| aarch64 | 1         | 0.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 1136      | 37.33%  |
| KDE5            | 768       | 25.24%  |
| Unknown         | 260       | 8.54%   |
| XFCE            | 215       | 7.07%   |
| X-Cinnamon      | 183       | 6.01%   |
| KDE4            | 98        | 3.22%   |
| MATE            | 71        | 2.33%   |
| KDE             | 71        | 2.33%   |
| LXQt            | 46        | 1.51%   |
| Cinnamon        | 43        | 1.41%   |
| LXDE            | 36        | 1.18%   |
| Pantheon        | 23        | 0.76%   |
| i3              | 17        | 0.56%   |
| Budgie          | 16        | 0.53%   |
| Unity           | 13        | 0.43%   |
| Deepin          | 9         | 0.3%    |
| GNOME Flashback | 8         | 0.26%   |
| Hyprland        | 4         | 0.13%   |
| awesome         | 4         | 0.13%   |
| sway            | 3         | 0.1%    |
| GNOME Classic   | 3         | 0.1%    |
| Trinity         | 2         | 0.07%   |
| qtile           | 2         | 0.07%   |
| icewm           | 2         | 0.07%   |
| fluxbox         | 2         | 0.07%   |
| DWM             | 2         | 0.07%   |
| stumpwm         | 1         | 0.03%   |
| ratflow         | 1         | 0.03%   |
| qt5ct           | 1         | 0.03%   |
| openbox         | 1         | 0.03%   |
| GNUstep         | 1         | 0.03%   |
| BunsenLabs      | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| X11         | 2336      | 78.15%  |
| Wayland     | 486       | 16.26%  |
| Unknown     | 131       | 4.38%   |
| Tty         | 35        | 1.17%   |
| Unspecified | 1         | 0.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1189      | 39.15%  |
| SDDM    | 721       | 23.74%  |
| GDM     | 366       | 12.05%  |
| GDM3    | 288       | 9.48%   |
| LightDM | 263       | 8.66%   |
| KDM     | 100       | 3.29%   |
| TDM     | 95        | 3.13%   |
| XDM     | 6         | 0.2%    |
| NODM    | 2         | 0.07%   |
| Ly      | 2         | 0.07%   |
| SU      | 1         | 0.03%   |
| SLIMSKI | 1         | 0.03%   |
| SLiM    | 1         | 0.03%   |
| MDM     | 1         | 0.03%   |
| LXDM    | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| pl_PL       | 1592      | 53.14%  |
| en_US       | 824       | 27.5%   |
| Unknown     | 372       | 12.42%  |
| en_GB       | 80        | 2.67%   |
| C           | 54        | 1.8%    |
| ru_RU       | 20        | 0.67%   |
| szl_PL      | 9         | 0.3%    |
| de_DE       | 7         | 0.23%   |
| uk_UA       | 6         | 0.2%    |
| ru_UA       | 4         | 0.13%   |
| en_IE       | 4         | 0.13%   |
| fr_FR       | 3         | 0.1%    |
| nl_NL       | 2         | 0.07%   |
| it_IT       | 2         | 0.07%   |
| hu_HU       | 2         | 0.07%   |
| en_DK       | 2         | 0.07%   |
| C.UTF8      | 2         | 0.07%   |
| sk_SK       | 1         | 0.03%   |
| POSIX       | 1         | 0.03%   |
| es_ES       | 1         | 0.03%   |
| es_AR       | 1         | 0.03%   |
| en_US.utf-8 | 1         | 0.03%   |
| en_IN       | 1         | 0.03%   |
| en_CA       | 1         | 0.03%   |
| en_AU       | 1         | 0.03%   |
| en_AG       | 1         | 0.03%   |
| af_ZA       | 1         | 0.03%   |
| aa_DJ       | 1         | 0.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 1509      | 50.93%  |
| EFI  | 1454      | 49.07%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 2057      | 68.61%  |
| Overlay  | 382       | 12.74%  |
| Btrfs    | 273       | 9.11%   |
| Unknown  | 173       | 5.77%   |
| Xfs      | 43        | 1.43%   |
| Tmpfs    | 27        | 0.9%    |
| Zfs      | 22        | 0.73%   |
| F2fs     | 9         | 0.3%    |
| Rootfs   | 3         | 0.1%    |
| Ext3     | 3         | 0.1%    |
| Ext2     | 3         | 0.1%    |
| XXXXX    | 1         | 0.03%   |
| Jfs      | 1         | 0.03%   |
| Bcachefs | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1329      | 44.51%  |
| GPT     | 1172      | 39.25%  |
| MBR     | 485       | 16.24%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2507      | 84.61%  |
| Yes       | 456       | 15.39%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2005      | 67.94%  |
| Yes       | 946       | 32.06%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 755       | 26.08%  |
| Dell                | 605       | 20.9%   |
| Hewlett-Packard     | 445       | 15.37%  |
| ASUSTek Computer    | 342       | 11.81%  |
| Acer                | 186       | 6.42%   |
| Toshiba             | 82        | 2.83%   |
| Samsung Electronics | 78        | 2.69%   |
| MSI                 | 63        | 2.18%   |
| Sony                | 37        | 1.28%   |
| HUAWEI              | 31        | 1.07%   |
| Apple               | 27        | 0.93%   |
| Fujitsu             | 25        | 0.86%   |
| Fujitsu Siemens     | 22        | 0.76%   |
| Google              | 21        | 0.73%   |
| Valve               | 19        | 0.66%   |
| Packard Bell        | 16        | 0.55%   |
| Notebook            | 15        | 0.52%   |
| eMachines           | 11        | 0.38%   |
| Kiano               | 10        | 0.35%   |
| Timi                | 9         | 0.31%   |
| Medion              | 9         | 0.31%   |
| Gigabyte Technology | 6         | 0.21%   |
| Unknown             | 6         | 0.21%   |
| Kruger&Matz         | 4         | 0.14%   |
| Alienware           | 4         | 0.14%   |
| TUXEDO              | 3         | 0.1%    |
| Teclast             | 3         | 0.1%    |
| Panasonic           | 3         | 0.1%    |
| mPTech              | 3         | 0.1%    |
| GPU Company         | 3         | 0.1%    |
| Clevo               | 3         | 0.1%    |
| Chuwi               | 3         | 0.1%    |
| TrekStor            | 2         | 0.07%   |
| System76            | 2         | 0.07%   |
| Star Labs           | 2         | 0.07%   |
| Schenker            | 2         | 0.07%   |
| Razer               | 2         | 0.07%   |
| MODECOM             | 2         | 0.07%   |
| MAXDATA             | 2         | 0.07%   |
| Maibenben           | 2         | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Dell Inspiron 3451                  | 31        | 1.07%   |
| Unknown                             | 29        | 1%      |
| Valve Jupiter                       | 19        | 0.66%   |
| Dell Latitude E6400                 | 16        | 0.55%   |
| Dell Latitude E6540                 | 15        | 0.52%   |
| Lenovo G50-30 80G0                  | 13        | 0.45%   |
| HP Pavilion dv7                     | 12        | 0.41%   |
| Dell Latitude 5480                  | 12        | 0.41%   |
| Dell Latitude E6430                 | 11        | 0.38%   |
| Dell Latitude D630                  | 11        | 0.38%   |
| Dell Latitude 5490                  | 11        | 0.38%   |
| ASUS X555LJ                         | 11        | 0.38%   |
| Lenovo Legion Y530-15ICH 81FV       | 9         | 0.31%   |
| Lenovo G580 20150                   | 9         | 0.31%   |
| HP 15                               | 9         | 0.31%   |
| Dell Latitude E7440                 | 9         | 0.31%   |
| Dell Latitude E6420                 | 9         | 0.31%   |
| Dell Latitude 5420                  | 9         | 0.31%   |
| Lenovo IdeaPad Y700-15ISK 80NV      | 8         | 0.28%   |
| Lenovo G510 20238                   | 8         | 0.28%   |
| HP Pavilion Gaming Laptop 15-ec1xxx | 8         | 0.28%   |
| HP Pavilion dv6                     | 8         | 0.28%   |
| HP Notebook                         | 8         | 0.28%   |
| Dell Latitude E6330                 | 8         | 0.28%   |
| Toshiba Satellite A300              | 7         | 0.24%   |
| Lenovo Legion Y540-15IRH 81SX       | 7         | 0.24%   |
| Lenovo IdeaPad 100-15IBD 80QQ       | 7         | 0.24%   |
| Lenovo G50-80 80E5                  | 7         | 0.24%   |
| HUAWEI HVY-WXX9                     | 7         | 0.24%   |
| HP Laptop 15-db1xxx                 | 7         | 0.24%   |
| HP EliteBook 6930p                  | 7         | 0.24%   |
| HP 255 G7 Notebook PC               | 7         | 0.24%   |
| HP 250 G6 Notebook PC               | 7         | 0.24%   |
| Dell Latitude E7450                 | 7         | 0.24%   |
| Dell Latitude E6440                 | 7         | 0.24%   |
| Dell Latitude E5470                 | 7         | 0.24%   |
| Dell Latitude E5430 non-vPro        | 7         | 0.24%   |
| Dell Latitude 5511                  | 7         | 0.24%   |
| Samsung 550P5C/550P7C               | 6         | 0.21%   |
| Samsung 350V5C/351V5C/3540VC/3440VC | 6         | 0.21%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 340       | 11.74%  |
| Dell Latitude         | 317       | 10.95%  |
| Lenovo IdeaPad        | 154       | 5.32%   |
| Dell Inspiron         | 152       | 5.25%   |
| Acer Aspire           | 117       | 4.04%   |
| HP EliteBook          | 98        | 3.39%   |
| HP Pavilion           | 97        | 3.35%   |
| Toshiba Satellite     | 66        | 2.28%   |
| HP ProBook            | 65        | 2.25%   |
| Lenovo Legion         | 52        | 1.8%    |
| Dell Precision        | 40        | 1.38%   |
| ASUS VivoBook         | 38        | 1.31%   |
| HP Laptop             | 36        | 1.24%   |
| Dell Vostro           | 34        | 1.17%   |
| Dell XPS              | 32        | 1.11%   |
| Unknown               | 29        | 1%      |
| ASUS ASUS             | 25        | 0.86%   |
| HP Compaq             | 23        | 0.79%   |
| Fujitsu LIFEBOOK      | 21        | 0.73%   |
| ASUS TUF              | 20        | 0.69%   |
| Valve Jupiter         | 19        | 0.66%   |
| HP 250                | 19        | 0.66%   |
| ASUS ROG              | 19        | 0.66%   |
| HP ZBook              | 17        | 0.59%   |
| Packard Bell EasyNote | 16        | 0.55%   |
| Lenovo ThinkBook      | 15        | 0.52%   |
| Acer Extensa          | 15        | 0.52%   |
| Lenovo G50-30         | 13        | 0.45%   |
| Lenovo Yoga           | 12        | 0.41%   |
| Acer TravelMate       | 12        | 0.41%   |
| Acer Swift            | 12        | 0.41%   |
| Acer Nitro            | 12        | 0.41%   |
| Lenovo G580           | 11        | 0.38%   |
| HP OMEN               | 11        | 0.38%   |
| HP 255                | 11        | 0.38%   |
| ASUS X555LJ           | 11        | 0.38%   |
| Fujitsu Siemens AMILO | 10        | 0.35%   |
| ASUS Zenbook          | 10        | 0.35%   |
| Lenovo G50-80         | 9         | 0.31%   |
| HP 15                 | 9         | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 247       | 8.53%   |
| 2012    | 243       | 8.39%   |
| 2013    | 240       | 8.29%   |
| 2020    | 237       | 8.19%   |
| 2011    | 232       | 8.01%   |
| 2018    | 197       | 6.8%    |
| 2014    | 191       | 6.6%    |
| 2015    | 182       | 6.29%   |
| 2008    | 181       | 6.25%   |
| 2021    | 172       | 5.94%   |
| 2017    | 154       | 5.32%   |
| 2010    | 150       | 5.18%   |
| 2016    | 131       | 4.53%   |
| 2007    | 107       | 3.7%    |
| 2009    | 101       | 3.49%   |
| 2022    | 80        | 2.76%   |
| 2006    | 35        | 1.21%   |
| 2023    | 9         | 0.31%   |
| 2005    | 3         | 0.1%    |
| 2004    | 2         | 0.07%   |
| Unknown | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 2895      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 2674      | 91.61%  |
| Enabled  | 245       | 8.39%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2872      | 99.21%  |
| Yes  | 23        | 0.79%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 723       | 24.61%  |
| 4.01-8.0    | 711       | 24.2%   |
| 8.01-16.0   | 488       | 16.61%  |
| 16.01-24.0  | 475       | 16.17%  |
| 32.01-64.0  | 242       | 8.24%   |
| 1.01-2.0    | 126       | 4.29%   |
| 2.01-3.0    | 89        | 3.03%   |
| 24.01-32.0  | 32        | 1.09%   |
| 64.01-256.0 | 30        | 1.02%   |
| 0.51-1.0    | 22        | 0.75%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1192      | 36.71%  |
| 2.01-3.0   | 729       | 22.45%  |
| 4.01-8.0   | 454       | 13.98%  |
| 3.01-4.0   | 405       | 12.47%  |
| 0.51-1.0   | 263       | 8.1%    |
| 8.01-16.0  | 150       | 4.62%   |
| 0.01-0.5   | 30        | 0.92%   |
| 16.01-24.0 | 17        | 0.52%   |
| 24.01-32.0 | 7         | 0.22%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2156      | 72.62%  |
| 2      | 679       | 22.87%  |
| 3      | 80        | 2.69%   |
| 0      | 40        | 1.35%   |
| 4      | 11        | 0.37%   |
| 5      | 3         | 0.1%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1744      | 59.62%  |
| Yes       | 1181      | 40.38%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2507      | 86.21%  |
| No        | 401       | 13.79%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2854      | 98.48%  |
| No        | 44        | 1.52%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2239      | 76%     |
| No        | 707       | 24%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Poland  | 2895      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Warsaw                 | 689       | 21.87%  |
| Krakow                 | 244       | 7.75%   |
| Wroclaw                | 187       | 5.94%   |
| Poznan                 | 179       | 5.68%   |
| Lodz                   | 110       | 3.49%   |
| Gdansk                 | 105       | 3.33%   |
| Katowice               | 82        | 2.6%    |
| Lublin                 | 45        | 1.43%   |
| Gdynia                 | 35        | 1.11%   |
| Szczecin               | 34        | 1.08%   |
| Bialystok              | 26        | 0.83%   |
| Rzeszów               | 24        | 0.76%   |
| Ruda Śląska          | 24        | 0.76%   |
| Torun                  | 23        | 0.73%   |
| Częstochowa           | 23        | 0.73%   |
| Bydgoszcz              | 23        | 0.73%   |
| Gliwice                | 20        | 0.63%   |
| Elblag                 | 19        | 0.6%    |
| Zabrze                 | 17        | 0.54%   |
| Płock                 | 17        | 0.54%   |
| Olsztyn                | 17        | 0.54%   |
| Bytom                  | 16        | 0.51%   |
| Sosnowiec              | 15        | 0.48%   |
| Opole                  | 15        | 0.48%   |
| Kielce                 | 15        | 0.48%   |
| Chorzów               | 14        | 0.44%   |
| Tarnów                | 12        | 0.38%   |
| Siemianowice Śląskie | 11        | 0.35%   |
| Blizniew               | 11        | 0.35%   |
| Rybnik                 | 10        | 0.32%   |
| Pruszków              | 10        | 0.32%   |
| Chorzele               | 10        | 0.32%   |
| Tychy                  | 9         | 0.29%   |
| Skierniewice           | 9         | 0.29%   |
| Bielsko-Biala          | 9         | 0.29%   |
| Zielona Góra          | 8         | 0.25%   |
| Wejherowo              | 8         | 0.25%   |
| Skawina                | 8         | 0.25%   |
| Legnica                | 8         | 0.25%   |
| Kedzierzyn-Kozle       | 8         | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 521       | 690    | 14.36%  |
| Seagate                     | 415       | 515    | 11.44%  |
| WDC                         | 385       | 475    | 10.61%  |
| Toshiba                     | 239       | 296    | 6.59%   |
| GOODRAM                     | 228       | 291    | 6.28%   |
| Unknown                     | 175       | 224    | 4.82%   |
| SanDisk                     | 163       | 203    | 4.49%   |
| Hitachi                     | 140       | 165    | 3.86%   |
| SK hynix                    | 134       | 169    | 3.69%   |
| Kingston                    | 134       | 183    | 3.69%   |
| Intel                       | 132       | 168    | 3.64%   |
| A-DATA Technology           | 129       | 153    | 3.55%   |
| Crucial                     | 122       | 185    | 3.36%   |
| Micron Technology           | 83        | 108    | 2.29%   |
| HGST                        | 74        | 92     | 2.04%   |
| KIOXIA                      | 41        | 46     | 1.13%   |
| Patriot                     | 36        | 44     | 0.99%   |
| SPCC                        | 33        | 39     | 0.91%   |
| PNY                         | 28        | 29     | 0.77%   |
| Plextor                     | 26        | 39     | 0.72%   |
| Fujitsu                     | 24        | 25     | 0.66%   |
| LITEON                      | 20        | 24     | 0.55%   |
| Transcend                   | 18        | 21     | 0.5%    |
| Phison Electronics          | 16        | 16     | 0.44%   |
| Phison                      | 14        | 20     | 0.39%   |
| China                       | 14        | 20     | 0.39%   |
| Silicon Motion              | 13        | 16     | 0.36%   |
| LITEONIT                    | 13        | 15     | 0.36%   |
| KIOXIA-EXCERIA              | 12        | 13     | 0.33%   |
| Apacer                      | 12        | 19     | 0.33%   |
| Apple                       | 11        | 13     | 0.3%    |
| Unknown                     | 10        | 13     | 0.28%   |
| Lenovo                      | 9         | 11     | 0.25%   |
| JMicron Technology          | 9         | 9      | 0.25%   |
| OCZ                         | 8         | 8      | 0.22%   |
| Kingston Technology Company | 8         | 8      | 0.22%   |
| ADATA Technology            | 8         | 11     | 0.22%   |
| HUAWEI                      | 7         | 9      | 0.19%   |
| Gigabyte Technology         | 7         | 8      | 0.19%   |
| Union Memory                | 6         | 9      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST500LT012-1DG142 500GB                     | 57        | 1.52%   |
| Seagate ST1000LM035-1RK172 1TB                      | 47        | 1.25%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 43        | 1.14%   |
| Unknown MMC Card  32GB                              | 29        | 0.77%   |
| GOODRAM SSDPR-CX400-256-G2 256GB                    | 29        | 0.77%   |
| Intel NVMe SSD Drive 512GB                          | 25        | 0.67%   |
| Crucial CT500MX500SSD1 500GB                        | 25        | 0.67%   |
| Toshiba MQ01ABD100 1TB                              | 24        | 0.64%   |
| Seagate ST9500325AS 500GB                           | 24        | 0.64%   |
| GOODRAM SSD 120GB                                   | 23        | 0.61%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 22        | 0.59%   |
| Samsung NVMe SSD Drive 512GB                        | 21        | 0.56%   |
| Kingston SA400S37240G 240GB SSD                     | 21        | 0.56%   |
| Toshiba MQ01ABF050 500GB                            | 20        | 0.53%   |
| HGST HTS721010A9E630 1TB                            | 20        | 0.53%   |
| Crucial CT1000MX500SSD1 1TB                         | 20        | 0.53%   |
| Unknown MMC Card  64GB                              | 19        | 0.51%   |
| Samsung SSD 860 EVO 500GB                           | 19        | 0.51%   |
| Samsung SSD 850 EVO 250GB                           | 19        | 0.51%   |
| Intel SSDPEKNW512G8H 512GB                          | 19        | 0.51%   |
| SanDisk NVMe SSD Drive 512GB                        | 18        | 0.48%   |
| GOODRAM SSD 240GB                                   | 17        | 0.45%   |
| GOODRAM SSDPR-CX400-512 512GB                       | 16        | 0.43%   |
| WDC WD10JPCX-24UE4T0 1TB                            | 15        | 0.4%    |
| Seagate Expansion 1TB                               | 15        | 0.4%    |
| Samsung SSD 980 1TB                                 | 15        | 0.4%    |
| Samsung NVMe SSD Drive 256GB                        | 15        | 0.4%    |
| HGST HTS725050A7E630 500GB                          | 15        | 0.4%    |
| Crucial CT240BX500SSD1 240GB                        | 15        | 0.4%    |
| Patriot Burst 120GB SSD                             | 14        | 0.37%   |
| GOODRAM SSDPR-CX400-512-G2 512GB                    | 14        | 0.37%   |
| GOODRAM SSDPR-CX400-256 256GB                       | 14        | 0.37%   |
| A-DATA SU800 256GB SSD                              | 14        | 0.37%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 13        | 0.35%   |
| Unknown MMC Card  128GB                             | 13        | 0.35%   |
| Samsung SSD 980 500GB                               | 13        | 0.35%   |
| SK hynix NVMe SSD Drive 512GB                       | 12        | 0.32%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 12        | 0.32%   |
| SanDisk SDSSDA240G 240GB                            | 12        | 0.32%   |
| HGST HTS545050A7E680 500GB                          | 12        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 412       | 510    | 36.4%   |
| WDC                 | 259       | 312    | 22.88%  |
| Toshiba             | 161       | 198    | 14.22%  |
| Hitachi             | 140       | 165    | 12.37%  |
| HGST                | 74        | 92     | 6.54%   |
| Samsung Electronics | 33        | 35     | 2.92%   |
| Fujitsu             | 24        | 25     | 2.12%   |
| JMicron Technology  | 8         | 8      | 0.71%   |
| Unknown             | 5         | 5      | 0.44%   |
| ASMT                | 5         | 5      | 0.44%   |
| USB3.0              | 3         | 3      | 0.27%   |
| ASMedia             | 3         | 3      | 0.27%   |
| StoreJet            | 1         | 1      | 0.09%   |
| PHD 3.0             | 1         | 1      | 0.09%   |
| LaCie               | 1         | 2      | 0.09%   |
| IBM/Hitachi         | 1         | 1      | 0.09%   |
| Apple               | 1         | 1      | 0.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 235       | 306    | 17.24%  |
| GOODRAM             | 221       | 284    | 16.21%  |
| Crucial             | 118       | 180    | 8.66%   |
| A-DATA Technology   | 109       | 131    | 8%      |
| Kingston            | 100       | 133    | 7.34%   |
| SanDisk             | 95        | 121    | 6.97%   |
| WDC                 | 57        | 66     | 4.18%   |
| SK hynix            | 39        | 48     | 2.86%   |
| Micron Technology   | 37        | 46     | 2.71%   |
| Intel               | 37        | 42     | 2.71%   |
| Patriot             | 34        | 42     | 2.49%   |
| Toshiba             | 32        | 35     | 2.35%   |
| SPCC                | 31        | 37     | 2.27%   |
| Plextor             | 23        | 36     | 1.69%   |
| PNY                 | 21        | 22     | 1.54%   |
| LITEON              | 20        | 24     | 1.47%   |
| Transcend           | 17        | 20     | 1.25%   |
| China               | 14        | 20     | 1.03%   |
| LITEONIT            | 13        | 15     | 0.95%   |
| KIOXIA-EXCERIA      | 11        | 12     | 0.81%   |
| Apacer              | 10        | 17     | 0.73%   |
| OCZ                 | 8         | 8      | 0.59%   |
| Apple               | 7         | 7      | 0.51%   |
| KingSpec            | 6         | 7      | 0.44%   |
| Gigabyte Technology | 5         | 6      | 0.37%   |
| Biostar             | 3         | 3      | 0.22%   |
| 2-Power             | 3         | 3      | 0.22%   |
| Unknown             | 3         | 3      | 0.22%   |
| Union Memory        | 2         | 3      | 0.15%   |
| Team                | 2         | 2      | 0.15%   |
| Ramaxel Technology  | 2         | 3      | 0.15%   |
| POLION              | 2         | 2      | 0.15%   |
| Phison              | 2         | 2      | 0.15%   |
| Netac               | 2         | 3      | 0.15%   |
| Micron_1            | 2         | 2      | 0.15%   |
| Intenso             | 2         | 2      | 0.15%   |
| HS-SSD-C100         | 2         | 4      | 0.15%   |
| Corsair             | 2         | 2      | 0.15%   |
| BIWIN               | 2         | 2      | 0.15%   |
| BHT                 | 2         | 2      | 0.15%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 1248      | 1735   | 36.57%  |
| HDD     | 1085      | 1367   | 31.79%  |
| NVMe    | 875       | 1209   | 25.64%  |
| MMC     | 168       | 213    | 4.92%   |
| Unknown | 37        | 48     | 1.08%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2070      | 3004   | 64.03%  |
| NVMe | 875       | 1203   | 27.06%  |
| MMC  | 168       | 213    | 5.2%    |
| SAS  | 120       | 152    | 3.71%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1682      | 2291   | 73.16%  |
| 0.51-1.0   | 560       | 740    | 24.36%  |
| 1.01-2.0   | 44        | 55     | 1.91%   |
| 3.01-4.0   | 5         | 5      | 0.22%   |
| 4.01-10.0  | 5         | 5      | 0.22%   |
| 2.01-3.0   | 3         | 6      | 0.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 936       | 30.15%  |
| 251-500        | 683       | 22%     |
| 1-20           | 395       | 12.73%  |
| 501-1000       | 338       | 10.89%  |
| 51-100         | 269       | 8.67%   |
| 21-50          | 145       | 4.67%   |
| 1001-2000      | 144       | 4.64%   |
| Unknown        | 116       | 3.74%   |
| 2001-3000      | 43        | 1.39%   |
| More than 3000 | 35        | 1.13%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1382      | 43.05%  |
| 21-50          | 512       | 15.95%  |
| 101-250        | 424       | 13.21%  |
| 51-100         | 406       | 12.65%  |
| 251-500        | 180       | 5.61%   |
| 501-1000       | 120       | 3.74%   |
| Unknown        | 116       | 3.61%   |
| 1001-2000      | 53        | 1.65%   |
| 2001-3000      | 10        | 0.31%   |
| More than 3000 | 6         | 0.19%   |
| 0              | 1         | 0.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                      | 9         | 9      | 2.75%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 9         | 10     | 2.75%   |
| Seagate ST500LT012-9WS142 500GB                | 8         | 27     | 2.45%   |
| SK hynix PC711 HFS512GDE9X073N 512GB           | 6         | 7      | 1.83%   |
| Seagate ST500LT012-1DG142 500GB                | 6         | 9      | 1.83%   |
| HGST HTS545050A7E680 500GB                     | 5         | 5      | 1.53%   |
| WDC WD5000BEVT-22ZAT0 500GB                    | 4         | 4      | 1.22%   |
| WDC WD10JPVX-22JC3T0 1TB                       | 4         | 4      | 1.22%   |
| Seagate ST1000LM014-1EJ164 1TB                 | 4         | 5      | 1.22%   |
| Hitachi HTS543225L9SA00 250GB                  | 4         | 4      | 1.22%   |
| Hitachi HTS541612J9SA00 120GB                  | 4         | 5      | 1.22%   |
| WDC WD3200BPVT-80ZEST0 320GB                   | 3         | 3      | 0.92%   |
| Toshiba MQ01ABD100 1TB                         | 3         | 4      | 0.92%   |
| Toshiba MK1246GSX 120GB                        | 3         | 3      | 0.92%   |
| Seagate ST980811AS 80GB                        | 3         | 3      | 0.92%   |
| Seagate ST9500420AS 500GB                      | 3         | 3      | 0.92%   |
| Seagate ST9320325AS 320GB                      | 3         | 3      | 0.92%   |
| Seagate ST9250827AS 250GB                      | 3         | 4      | 0.92%   |
| Seagate ST9250410AS 250GB                      | 3         | 3      | 0.92%   |
| Seagate ST320LT020-9YG142 320GB                | 3         | 3      | 0.92%   |
| Hitachi HTS543232A7A384 320GB                  | 3         | 4      | 0.92%   |
| WDC WD7500BPKT-22PK4T0 752GB                   | 2         | 2      | 0.61%   |
| WDC WD1600BEVT-75A23T0 160GB                   | 2         | 2      | 0.61%   |
| WDC WD1600BEVT-22A23T0 160GB                   | 2         | 2      | 0.61%   |
| Toshiba MK5075GSX 500GB                        | 2         | 2      | 0.61%   |
| Toshiba MK3265GSX 320GB                        | 2         | 2      | 0.61%   |
| Toshiba MK1637GSX 160GB                        | 2         | 2      | 0.61%   |
| Seagate ST9250410ASG 250GB                     | 2         | 2      | 0.61%   |
| Seagate ST9250315AS 250GB                      | 2         | 2      | 0.61%   |
| Seagate ST9160821AS 160GB                      | 2         | 3      | 0.61%   |
| Seagate ST9120822AS 120GB                      | 2         | 2      | 0.61%   |
| Seagate ST500LM012 HN-M500MBB 500GB            | 2         | 2      | 0.61%   |
| Seagate ST1000LM035-1RK172 1TB                 | 2         | 2      | 0.61%   |
| Seagate ST1000LM014-SSHD-8GB                   | 2         | 2      | 0.61%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD            | 2         | 2      | 0.61%   |
| Samsung Electronics HM250HI 250GB              | 2         | 2      | 0.61%   |
| Micron Technology 1100_MTFDDAK256TBN 256GB SSD | 2         | 2      | 0.61%   |
| LITEONIT LCT-256M3S 2.5 7mm 256GB SSD          | 2         | 2      | 0.61%   |
| Kingston SV300S37A120G 120GB SSD               | 2         | 2      | 0.61%   |
| Hitachi HTS725050A9A364 500GB                  | 2         | 3      | 0.61%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 85        | 114    | 26.07%  |
| WDC                 | 40        | 41     | 12.27%  |
| Hitachi             | 39        | 44     | 11.96%  |
| Toshiba             | 37        | 47     | 11.35%  |
| Samsung Electronics | 18        | 19     | 5.52%   |
| A-DATA Technology   | 18        | 20     | 5.52%   |
| HGST                | 15        | 16     | 4.6%    |
| SK hynix            | 14        | 15     | 4.29%   |
| SanDisk             | 8         | 9      | 2.45%   |
| Kingston            | 6         | 6      | 1.84%   |
| Intel               | 6         | 6      | 1.84%   |
| Fujitsu             | 6         | 6      | 1.84%   |
| Micron Technology   | 5         | 5      | 1.53%   |
| Crucial             | 5         | 13     | 1.53%   |
| LITEONIT            | 3         | 3      | 0.92%   |
| LITEON              | 3         | 3      | 0.92%   |
| ASMedia             | 3         | 3      | 0.92%   |
| Patriot             | 2         | 4      | 0.61%   |
| OCZ                 | 2         | 2      | 0.61%   |
| China               | 2         | 3      | 0.61%   |
| SPCC                | 1         | 1      | 0.31%   |
| RENICE              | 1         | 1      | 0.31%   |
| Plextor             | 1         | 1      | 0.31%   |
| Platinet            | 1         | 1      | 0.31%   |
| Lexar               | 1         | 1      | 0.31%   |
| Lenovo              | 1         | 1      | 0.31%   |
| KingSpec            | 1         | 1      | 0.31%   |
| Apple               | 1         | 1      | 0.31%   |
| Apacer              | 1         | 1      | 0.31%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 85        | 114    | 36.96%  |
| Hitachi             | 39        | 44     | 16.96%  |
| WDC                 | 38        | 39     | 16.52%  |
| Toshiba             | 34        | 44     | 14.78%  |
| HGST                | 15        | 16     | 6.52%   |
| Samsung Electronics | 10        | 10     | 4.35%   |
| Fujitsu             | 6         | 6      | 2.61%   |
| ASMedia             | 3         | 3      | 1.3%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 225       | 276    | 70.53%  |
| SSD  | 76        | 91     | 23.82%  |
| NVMe | 18        | 21     | 5.64%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD800BEVS-75RST0 80GB       | 1         | 1      | 20%     |
| WDC WD3200BEKT-75PVMT1 320GB    | 1         | 1      | 20%     |
| WDC WD2500BEVS-22UST0 250GB     | 1         | 1      | 20%     |
| Toshiba MK3265GSXN 320GB        | 1         | 1      | 20%     |
| Seagate ST320LT020-9YG142 320GB | 1         | 1      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 3      | 60%     |
| Toshiba | 1         | 1      | 20%     |
| Seagate | 1         | 1      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1438      | 2274   | 46.51%  |
| Works    | 1336      | 1905   | 43.21%  |
| Malfunc  | 313       | 388    | 10.12%  |
| Failed   | 5         | 5      | 0.16%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2188      | 64.98%  |
| AMD                              | 284       | 8.43%   |
| Samsung Electronics              | 269       | 7.99%   |
| SanDisk                          | 132       | 3.92%   |
| SK hynix                         | 95        | 2.82%   |
| Toshiba America Info Systems     | 51        | 1.51%   |
| Phison Electronics               | 46        | 1.37%   |
| Micron Technology                | 46        | 1.37%   |
| KIOXIA                           | 42        | 1.25%   |
| Kingston Technology Company      | 41        | 1.22%   |
| ADATA Technology                 | 29        | 0.86%   |
| Silicon Motion                   | 23        | 0.68%   |
| Nvidia                           | 22        | 0.65%   |
| Union Memory (Shenzhen)          | 14        | 0.42%   |
| Silicon Integrated Systems [SiS] | 11        | 0.33%   |
| Micron/Crucial Technology        | 10        | 0.3%    |
| Lite-On Technology               | 9         | 0.27%   |
| Realtek Semiconductor            | 8         | 0.24%   |
| Lenovo                           | 8         | 0.24%   |
| Solid State Storage Technology   | 7         | 0.21%   |
| VIA Technologies                 | 6         | 0.18%   |
| Shenzhen Longsys Electronics     | 6         | 0.18%   |
| JMicron Technology               | 5         | 0.15%   |
| MAXIO Technology (Hangzhou)      | 4         | 0.12%   |
| Yangtze Memory Technologies      | 2         | 0.06%   |
| Marvell Technology Group         | 2         | 0.06%   |
| Apple                            | 2         | 0.06%   |
| Silicon Image                    | 1         | 0.03%   |
| O2 Micro                         | 1         | 0.03%   |
| Biwin Storage Technology         | 1         | 0.03%   |
| ASMedia Technology               | 1         | 0.03%   |
| Unknown                          | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 241       | 6.51%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 236       | 6.37%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 193       | 5.21%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 169       | 4.57%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 167       | 4.51%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 139       | 3.75%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 122       | 3.3%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 120       | 3.24%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 105       | 2.84%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 101       | 2.73%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 101       | 2.73%   |
| Samsung NVMe SSD Controller 980                                                  | 92        | 2.49%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 91        | 2.46%   |
| Intel Volume Management Device NVMe RAID Controller                              | 82        | 2.22%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 79        | 2.13%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 76        | 2.05%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 76        | 2.05%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 69        | 1.86%   |
| Intel SSD 660P Series                                                            | 63        | 1.7%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 57        | 1.54%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 43        | 1.16%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 40        | 1.08%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 37        | 1%      |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 36        | 0.97%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 32        | 0.86%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 30        | 0.81%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 28        | 0.76%   |
| Intel Tiger Lake-LP SATA Controller                                              | 28        | 0.76%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 28        | 0.76%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 27        | 0.73%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 26        | 0.7%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 26        | 0.7%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 24        | 0.65%   |
| Intel Comet Lake SATA AHCI Controller                                            | 24        | 0.65%   |
| SK hynix BC511 NVMe SSD                                                          | 23        | 0.62%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 23        | 0.62%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 22        | 0.59%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 21        | 0.57%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 20        | 0.54%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 20        | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 2054      | 58.37%  |
| NVMe | 884       | 25.12%  |
| IDE  | 320       | 9.09%   |
| RAID | 261       | 7.42%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 2431      | 83.97%  |
| AMD          | 462       | 15.96%  |
| QUALCOMM     | 1         | 0.03%   |
| CentaurHauls | 1         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron CPU N2840 @ 2.16GHz             | 51        | 1.76%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 46        | 1.59%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 41        | 1.41%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 41        | 1.41%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 41        | 1.41%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 38        | 1.31%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 36        | 1.24%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 35        | 1.21%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 35        | 1.21%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 32        | 1.1%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 31        | 1.07%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 30        | 1.03%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 30        | 1.03%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 29        | 1%      |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 27        | 0.93%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 26        | 0.9%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 26        | 0.9%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 26        | 0.9%    |
| Intel Core i5-8300H CPU @ 2.30GHz             | 24        | 0.83%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 23        | 0.79%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 23        | 0.79%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 22        | 0.76%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 21        | 0.72%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 21        | 0.72%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 20        | 0.69%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 20        | 0.69%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 20        | 0.69%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 20        | 0.69%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 20        | 0.69%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 20        | 0.69%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 19        | 0.66%   |
| AMD Custom APU 0405                           | 19        | 0.66%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 18        | 0.62%   |
| Intel Core i5-3340M CPU @ 2.70GHz             | 18        | 0.62%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 18        | 0.62%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 17        | 0.59%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 17        | 0.59%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 17        | 0.59%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 17        | 0.59%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 17        | 0.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 810       | 27.96%  |
| Intel Core i7                  | 542       | 18.71%  |
| Intel Core i3                  | 231       | 7.97%   |
| Intel Core 2 Duo               | 227       | 7.84%   |
| Other                          | 176       | 6.08%   |
| Intel Celeron                  | 163       | 5.63%   |
| AMD Ryzen 5                    | 141       | 4.87%   |
| AMD Ryzen 7                    | 96        | 3.31%   |
| Intel Pentium                  | 92        | 3.18%   |
| Intel Atom                     | 55        | 1.9%    |
| Intel Pentium Dual-Core        | 40        | 1.38%   |
| AMD A6                         | 27        | 0.93%   |
| Intel Core 2                   | 21        | 0.72%   |
| AMD Ryzen 7 PRO                | 18        | 0.62%   |
| AMD A8                         | 18        | 0.62%   |
| Intel Pentium Dual             | 17        | 0.59%   |
| Intel Genuine                  | 16        | 0.55%   |
| AMD E1                         | 13        | 0.45%   |
| AMD E                          | 13        | 0.45%   |
| AMD A4                         | 13        | 0.45%   |
| AMD A10                        | 12        | 0.41%   |
| Intel Xeon                     | 11        | 0.38%   |
| Intel Celeron M                | 11        | 0.38%   |
| AMD Ryzen 9                    | 10        | 0.35%   |
| Intel Pentium M                | 8         | 0.28%   |
| AMD Ryzen 3                    | 8         | 0.28%   |
| AMD E2                         | 8         | 0.28%   |
| AMD Athlon X2                  | 8         | 0.28%   |
| Intel Core Duo                 | 7         | 0.24%   |
| AMD Turion 64 X2 Mobile        | 7         | 0.24%   |
| AMD Ryzen 5 PRO                | 6         | 0.21%   |
| AMD C-60                       | 6         | 0.21%   |
| Intel Celeron Dual-Core        | 5         | 0.17%   |
| Intel Core i9                  | 4         | 0.14%   |
| AMD Turion X2 Dual-Core Mobile | 4         | 0.14%   |
| AMD Phenom II                  | 4         | 0.14%   |
| AMD Athlon II                  | 4         | 0.14%   |
| Intel Pentium Silver           | 3         | 0.1%    |
| Intel Core m3                  | 3         | 0.1%    |
| Intel Core M                   | 3         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 1598      | 55.12%  |
| 4       | 841       | 29.01%  |
| 6       | 193       | 6.66%   |
| 8       | 137       | 4.73%   |
| 1       | 71        | 2.45%   |
| Unknown | 21        | 0.72%   |
| 14      | 13        | 0.45%   |
| 12      | 13        | 0.45%   |
| 10      | 7         | 0.24%   |
| 3       | 2         | 0.07%   |
| 192     | 1         | 0.03%   |
| 16      | 1         | 0.03%   |
| 5       | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 2892      | 99.9%   |
| Unknown | 2         | 0.07%   |
| 2       | 1         | 0.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 2039      | 70.21%  |
| 1       | 843       | 29.03%  |
| Unknown | 21        | 0.72%   |
| 8       | 1         | 0.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2812      | 96.97%  |
| 32-bit         | 48        | 1.66%   |
| Unknown        | 39        | 1.34%   |
| 64-bit         | 1         | 0.03%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 649       | 21.62%  |
| 0x206a7    | 200       | 6.66%   |
| 0x306a9    | 189       | 6.3%    |
| 0x1067a    | 116       | 3.86%   |
| 0x40651    | 103       | 3.43%   |
| 0x306c3    | 88        | 2.93%   |
| 0x20655    | 87        | 2.9%    |
| 0x906ea    | 85        | 2.83%   |
| 0x806ec    | 85        | 2.83%   |
| 0x306d4    | 82        | 2.73%   |
| 0x806c1    | 81        | 2.7%    |
| 0x30678    | 80        | 2.66%   |
| 0x406e3    | 76        | 2.53%   |
| 0x806ea    | 73        | 2.43%   |
| 0x6fd      | 70        | 2.33%   |
| 0x806e9    | 61        | 2.03%   |
| 0x506e3    | 52        | 1.73%   |
| 0x10676    | 52        | 1.73%   |
| 0x0a50000c | 44        | 1.47%   |
| 0x906e9    | 43        | 1.43%   |
| 0x08600106 | 33        | 1.1%    |
| 0xa0652    | 32        | 1.07%   |
| 0x20652    | 32        | 1.07%   |
| 0x08108102 | 28        | 0.93%   |
| 0x08108109 | 26        | 0.87%   |
| 0x806eb    | 25        | 0.83%   |
| 0x706e5    | 21        | 0.7%    |
| 0x6fb      | 19        | 0.63%   |
| 0x08600104 | 19        | 0.63%   |
| 0x6f6      | 18        | 0.6%    |
| 0x08600103 | 18        | 0.6%    |
| 0x906ed    | 17        | 0.57%   |
| 0x906a3    | 17        | 0.57%   |
| 0x06001119 | 17        | 0.57%   |
| 0x806d1    | 16        | 0.53%   |
| 0x406c4    | 16        | 0.53%   |
| 0x106ca    | 16        | 0.53%   |
| 0x406c3    | 15        | 0.5%    |
| 0x506c9    | 14        | 0.47%   |
| 0x106c2    | 14        | 0.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 491       | 16.95%  |
| Haswell          | 247       | 8.53%   |
| SandyBridge      | 239       | 8.25%   |
| IvyBridge        | 237       | 8.18%   |
| Penryn           | 190       | 6.56%   |
| Skylake          | 160       | 5.52%   |
| Core             | 145       | 5.01%   |
| Westmere         | 138       | 4.76%   |
| Silvermont       | 134       | 4.63%   |
| Broadwell        | 111       | 3.83%   |
| TigerLake        | 99        | 3.42%   |
| Zen 2            | 98        | 3.38%   |
| Unknown          | 69        | 2.38%   |
| Zen+             | 68        | 2.35%   |
| Zen 3            | 61        | 2.11%   |
| CometLake        | 45        | 1.55%   |
| IceLake          | 41        | 1.42%   |
| Bobcat           | 35        | 1.21%   |
| Bonnell          | 34        | 1.17%   |
| P6               | 32        | 1.1%    |
| Alderlake Hybrid | 30        | 1.04%   |
| Piledriver       | 22        | 0.76%   |
| Zen              | 21        | 0.72%   |
| Goldmont plus    | 19        | 0.66%   |
| Goldmont         | 19        | 0.66%   |
| Excavator        | 19        | 0.66%   |
| Puma             | 16        | 0.55%   |
| K8 & K10 hybrid  | 16        | 0.55%   |
| K8 Hammer        | 14        | 0.48%   |
| K10              | 12        | 0.41%   |
| Jaguar           | 12        | 0.41%   |
| K10 Llano        | 11        | 0.38%   |
| Nehalem          | 7         | 0.24%   |
| Steamroller      | 4         | 0.14%   |
| Tremont          | 1         | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2170      | 57.76%  |
| Nvidia                           | 894       | 23.8%   |
| AMD                              | 681       | 18.13%  |
| VIA Technologies                 | 6         | 0.16%   |
| Silicon Integrated Systems [SiS] | 6         | 0.16%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 228       | 5.82%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 220       | 5.61%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 131       | 3.34%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 110       | 2.81%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 107       | 2.73%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 104       | 2.65%   |
| Intel UHD Graphics 620                                                                   | 99        | 2.53%   |
| Intel HD Graphics 5500                                                                   | 99        | 2.53%   |
| Intel Core Processor Integrated Graphics Controller                                      | 93        | 2.37%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 93        | 2.37%   |
| AMD Renoir                                                                               | 92        | 2.35%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 91        | 2.32%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 86        | 2.19%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 77        | 1.96%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 73        | 1.86%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 73        | 1.86%   |
| Intel HD Graphics 620                                                                    | 73        | 1.86%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 69        | 1.76%   |
| Intel HD Graphics 530                                                                    | 57        | 1.45%   |
| Intel HD Graphics 630                                                                    | 53        | 1.35%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 50        | 1.28%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 50        | 1.28%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 47        | 1.2%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 47        | 1.2%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 41        | 1.05%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 40        | 1.02%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 40        | 1.02%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 38        | 0.97%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 35        | 0.89%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 31        | 0.79%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 30        | 0.77%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 28        | 0.71%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 27        | 0.69%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 26        | 0.66%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 26        | 0.66%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 25        | 0.64%   |
| Nvidia TU117M                                                                            | 24        | 0.61%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 24        | 0.61%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 22        | 0.56%   |
| Nvidia GM108M [GeForce 840M]                                                             | 22        | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1382      | 47.52%  |
| Intel + Nvidia           | 619       | 21.29%  |
| 1 x AMD                  | 392       | 13.48%  |
| 1 x Nvidia               | 193       | 6.64%   |
| Intel + AMD              | 159       | 5.47%   |
| AMD + Nvidia             | 81        | 2.79%   |
| 2 x AMD                  | 47        | 1.62%   |
| 2 x Intel                | 15        | 0.52%   |
| Other                    | 6         | 0.21%   |
| 1 x VIA                  | 6         | 0.21%   |
| 1 x SiS                  | 6         | 0.21%   |
| 2 x Nvidia               | 1         | 0.03%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2451      | 83.59%  |
| Proprietary | 404       | 13.78%  |
| Unknown     | 77        | 2.63%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1760      | 59.2%   |
| 1.01-2.0   | 392       | 13.19%  |
| 0.01-0.5   | 383       | 12.88%  |
| 0.51-1.0   | 184       | 6.19%   |
| 3.01-4.0   | 178       | 5.99%   |
| 5.01-6.0   | 48        | 1.61%   |
| 7.01-8.0   | 19        | 0.64%   |
| 2.01-3.0   | 5         | 0.17%   |
| 8.01-16.0  | 4         | 0.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 600       | 18.05%  |
| LG Display              | 520       | 15.64%  |
| Samsung Electronics     | 411       | 12.36%  |
| BOE                     | 385       | 11.58%  |
| Chimei Innolux          | 363       | 10.92%  |
| Dell                    | 125       | 3.76%   |
| Chi Mei Optoelectronics | 109       | 3.28%   |
| Lenovo                  | 100       | 3.01%   |
| Goldstar                | 65        | 1.95%   |
| Iiyama                  | 59        | 1.77%   |
| Sharp                   | 49        | 1.47%   |
| LG Philips              | 45        | 1.35%   |
| PANDA                   | 44        | 1.32%   |
| Philips                 | 33        | 0.99%   |
| BenQ                    | 33        | 0.99%   |
| InfoVision              | 28        | 0.84%   |
| AOC                     | 26        | 0.78%   |
| Acer                    | 25        | 0.75%   |
| Hewlett-Packard         | 24        | 0.72%   |
| Apple                   | 22        | 0.66%   |
| NEC Computers           | 21        | 0.63%   |
| HannStar                | 16        | 0.48%   |
| Ancor Communications    | 16        | 0.48%   |
| CPT                     | 15        | 0.45%   |
| Eizo                    | 14        | 0.42%   |
| CSO                     | 13        | 0.39%   |
| Valve                   | 12        | 0.36%   |
| Toshiba                 | 9         | 0.27%   |
| Mi                      | 9         | 0.27%   |
| LGD                     | 9         | 0.27%   |
| ASUSTek Computer        | 9         | 0.27%   |
| Seiko/Epson             | 8         | 0.24%   |
| MSI                     | 8         | 0.24%   |
| Sony                    | 7         | 0.21%   |
| Panasonic               | 6         | 0.18%   |
| Fujitsu Siemens         | 6         | 0.18%   |
| TMX                     | 5         | 0.15%   |
| InnoLux Display         | 5         | 0.15%   |
| IBM                     | 5         | 0.15%   |
| Vestel Elektronik       | 4         | 0.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 32        | 0.94%   |
| BOE LCD Monitor BOE0629 1366x768 309x173mm 13.9-inch                     | 31        | 0.91%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 28        | 0.82%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 26        | 0.77%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 25        | 0.74%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 25        | 0.74%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 23        | 0.68%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 20        | 0.59%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch                  | 17        | 0.5%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 17        | 0.5%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 17        | 0.5%    |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 16        | 0.47%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 15        | 0.44%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 15        | 0.44%   |
| BOE LCD Monitor BOE06FB 1920x1080 344x194mm 15.5-inch                    | 14        | 0.41%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch             | 13        | 0.38%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 13        | 0.38%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 13        | 0.38%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 13        | 0.38%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 13        | 0.38%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 13        | 0.38%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 12        | 0.35%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 12        | 0.35%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 12        | 0.35%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 12        | 0.35%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 12        | 0.35%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 11        | 0.32%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 11        | 0.32%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 10        | 0.29%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch    | 10        | 0.29%   |
| Samsung Electronics LCD Monitor SDC4852 1920x1080 344x194mm 15.5-inch    | 10        | 0.29%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 10        | 0.29%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 10        | 0.29%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch          | 10        | 0.29%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 10        | 0.29%   |
| BOE LCD Monitor BOE06E2 1920x1080 309x173mm 13.9-inch                    | 10        | 0.29%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch           | 10        | 0.29%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch           | 10        | 0.29%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 10        | 0.29%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 9         | 0.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1268      | 41.14%  |
| 1366x768 (WXGA)    | 828       | 26.87%  |
| 1600x900 (HD+)     | 214       | 6.94%   |
| 1280x800 (WXGA)    | 188       | 6.1%    |
| 3840x2160 (4K)     | 93        | 3.02%   |
| 2560x1440 (QHD)    | 89        | 2.89%   |
| 1920x1200 (WUXGA)  | 75        | 2.43%   |
| 1440x900 (WXGA+)   | 68        | 2.21%   |
| 1680x1050 (WSXGA+) | 51        | 1.65%   |
| 1024x600           | 27        | 0.88%   |
| 3440x1440          | 23        | 0.75%   |
| 2560x1600          | 21        | 0.68%   |
| 1280x1024 (SXGA)   | 21        | 0.68%   |
| 800x1280           | 15        | 0.49%   |
| 2560x1080          | 12        | 0.39%   |
| 3840x2400          | 10        | 0.32%   |
| 2160x1440          | 9         | 0.29%   |
| Unknown            | 9         | 0.29%   |
| 2880x1800          | 8         | 0.26%   |
| 1024x768 (XGA)     | 7         | 0.23%   |
| 3200x1800 (QHD+)   | 5         | 0.16%   |
| 1680x945           | 4         | 0.13%   |
| 3286x1080          | 3         | 0.1%    |
| 1400x1050          | 3         | 0.1%    |
| 1280x768           | 3         | 0.1%    |
| 3840x1600          | 2         | 0.06%   |
| 3840x1080          | 2         | 0.06%   |
| 3456x2160          | 2         | 0.06%   |
| 3200x2000          | 2         | 0.06%   |
| 3000x2000          | 2         | 0.06%   |
| 2288x1287          | 2         | 0.06%   |
| 2256x1504          | 2         | 0.06%   |
| 1600x1200          | 2         | 0.06%   |
| 1280x720 (HD)      | 2         | 0.06%   |
| 6400x1600          | 1         | 0.03%   |
| 5120x1600          | 1         | 0.03%   |
| 3300x2200          | 1         | 0.03%   |
| 2520x1680          | 1         | 0.03%   |
| 2304x1440          | 1         | 0.03%   |
| 2240x1400          | 1         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1423      | 42.63%  |
| 13      | 387       | 11.59%  |
| 14      | 363       | 10.87%  |
| 17      | 251       | 7.52%   |
| 24      | 148       | 4.43%   |
| 23      | 112       | 3.36%   |
| 12      | 106       | 3.18%   |
| 27      | 96        | 2.88%   |
| 21      | 69        | 2.07%   |
| Unknown | 56        | 1.68%   |
| 11      | 47        | 1.41%   |
| 34      | 38        | 1.14%   |
| 16      | 30        | 0.9%    |
| 10      | 29        | 0.87%   |
| 22      | 24        | 0.72%   |
| 19      | 24        | 0.72%   |
| 18      | 22        | 0.66%   |
| 31      | 17        | 0.51%   |
| 7       | 12        | 0.36%   |
| 25      | 11        | 0.33%   |
| 48      | 9         | 0.27%   |
| 20      | 9         | 0.27%   |
| 84      | 8         | 0.24%   |
| 40      | 7         | 0.21%   |
| 72      | 5         | 0.15%   |
| 3       | 5         | 0.15%   |
| 43      | 4         | 0.12%   |
| 32      | 4         | 0.12%   |
| 37      | 3         | 0.09%   |
| 28      | 3         | 0.09%   |
| 26      | 3         | 0.09%   |
| 65      | 2         | 0.06%   |
| 46      | 2         | 0.06%   |
| 142     | 1         | 0.03%   |
| 60      | 1         | 0.03%   |
| 54      | 1         | 0.03%   |
| 52      | 1         | 0.03%   |
| 49      | 1         | 0.03%   |
| 35      | 1         | 0.03%   |
| 33      | 1         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 1983      | 60.29%  |
| 201-300        | 337       | 10.25%  |
| 501-600        | 334       | 10.16%  |
| 351-400        | 312       | 9.49%   |
| 401-500        | 134       | 4.07%   |
| Unknown        | 56        | 1.7%    |
| 701-800        | 43        | 1.31%   |
| 601-700        | 27        | 0.82%   |
| 1001-1500      | 17        | 0.52%   |
| 1-100          | 16        | 0.49%   |
| 1501-2000      | 13        | 0.4%    |
| 801-900        | 11        | 0.33%   |
| 901-1000       | 4         | 0.12%   |
| More than 2000 | 1         | 0.03%   |
| 101-200        | 1         | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 2336      | 80%     |
| 16/10   | 407       | 13.94%  |
| Unknown | 46        | 1.58%   |
| 21/9    | 40        | 1.37%   |
| 3/2     | 33        | 1.13%   |
| 5/4     | 22        | 0.75%   |
| 4/3     | 15        | 0.51%   |
| 0.67    | 12        | 0.41%   |
| 6/5     | 5         | 0.17%   |
| 32/9    | 2         | 0.07%   |
| 1.00    | 1         | 0.03%   |
| 0.62    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1421      | 42.83%  |
| 81-90          | 617       | 18.6%   |
| 201-250        | 271       | 8.17%   |
| 121-130        | 199       | 6%      |
| 71-80          | 125       | 3.77%   |
| 61-70          | 105       | 3.16%   |
| 301-350        | 99        | 2.98%   |
| 251-300        | 71        | 2.14%   |
| 351-500        | 61        | 1.84%   |
| Unknown        | 56        | 1.69%   |
| 51-60          | 47        | 1.42%   |
| 131-140        | 47        | 1.42%   |
| 151-200        | 42        | 1.27%   |
| 41-50          | 29        | 0.87%   |
| 141-150        | 29        | 0.87%   |
| More than 1000 | 27        | 0.81%   |
| 111-120        | 20        | 0.6%    |
| 501-1000       | 18        | 0.54%   |
| 1-40           | 17        | 0.51%   |
| 91-100         | 17        | 0.51%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1343      | 41.23%  |
| 101-120       | 956       | 29.35%  |
| 51-100        | 653       | 20.05%  |
| 161-240       | 155       | 4.76%   |
| More than 240 | 71        | 2.18%   |
| Unknown       | 56        | 1.72%   |
| 1-50          | 23        | 0.71%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 2352      | 78.71%  |
| 2     | 487       | 16.3%   |
| 3     | 69        | 2.31%   |
| 0     | 69        | 2.31%   |
| 4     | 9         | 0.3%    |
| 6     | 1         | 0.03%   |
| 5     | 1         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1676      | 35.21%  |
| Realtek Semiconductor             | 1363      | 28.63%  |
| Qualcomm Atheros                  | 700       | 14.71%  |
| Broadcom                          | 321       | 6.74%   |
| Broadcom Limited                  | 95        | 2%      |
| Dell                              | 80        | 1.68%   |
| Marvell Technology Group          | 66        | 1.39%   |
| Huawei Technologies               | 60        | 1.26%   |
| MediaTek                          | 51        | 1.07%   |
| Ralink                            | 38        | 0.8%    |
| Ericsson Business Mobile Networks | 29        | 0.61%   |
| TP-Link                           | 28        | 0.59%   |
| Hewlett-Packard                   | 24        | 0.5%    |
| Samsung Electronics               | 23        | 0.48%   |
| Sierra Wireless                   | 17        | 0.36%   |
| JMicron Technology                | 17        | 0.36%   |
| Xiaomi                            | 15        | 0.32%   |
| ASIX Electronics                  | 14        | 0.29%   |
| Lenovo                            | 13        | 0.27%   |
| Ralink Technology                 | 12        | 0.25%   |
| Nvidia                            | 12        | 0.25%   |
| Fibocom                           | 10        | 0.21%   |
| DisplayLink                       | 10        | 0.21%   |
| Silicon Integrated Systems [SiS]  | 9         | 0.19%   |
| Qualcomm Atheros Communications   | 9         | 0.19%   |
| Qualcomm                          | 8         | 0.17%   |
| ZTE WCDMA Technologies MSM        | 7         | 0.15%   |
| ASUSTek Computer                  | 6         | 0.13%   |
| VIA Technologies                  | 5         | 0.11%   |
| NetGear                           | 5         | 0.11%   |
| Motorola PCS                      | 5         | 0.11%   |
| Attansic Technology               | 4         | 0.08%   |
| Microsoft                         | 3         | 0.06%   |
| HTC (High Tech Computer)          | 3         | 0.06%   |
| Sigma Designs                     | 2         | 0.04%   |
| Edimax Technology                 | 2         | 0.04%   |
| Uniden                            | 1         | 0.02%   |
| Toshiba                           | 1         | 0.02%   |
| Texas Instruments                 | 1         | 0.02%   |
| Tenda                             | 1         | 0.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 891       | 15.42%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 242       | 4.19%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 162       | 2.8%    |
| Intel Wireless 8265 / 8275                                              | 125       | 2.16%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 124       | 2.15%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 121       | 2.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 116       | 2.01%   |
| Intel Wi-Fi 6 AX200                                                     | 109       | 1.89%   |
| Intel Wireless 7260                                                     | 103       | 1.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 91        | 1.57%   |
| Intel Wireless 8260                                                     | 90        | 1.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 85        | 1.47%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 82        | 1.42%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 79        | 1.37%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 78        | 1.35%   |
| Intel Wi-Fi 6 AX201                                                     | 77        | 1.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 76        | 1.31%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 74        | 1.28%   |
| Intel Wireless 7265                                                     | 73        | 1.26%   |
| Intel Wireless 3160                                                     | 65        | 1.12%   |
| Intel Wireless 3165                                                     | 54        | 0.93%   |
| Intel 82567LM Gigabit Network Connection                                | 53        | 0.92%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 52        | 0.9%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 52        | 0.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 51        | 0.88%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 51        | 0.88%   |
| Broadcom BCM43142 802.11b/g/n                                           | 51        | 0.88%   |
| Intel Centrino Ultimate-N 6300                                          | 49        | 0.85%   |
| Intel Ethernet Connection I218-LM                                       | 46        | 0.8%    |
| Intel WiFi Link 5100                                                    | 45        | 0.78%   |
| Intel Ethernet Connection (4) I219-LM                                   | 45        | 0.78%   |
| Intel 82577LM Gigabit Network Connection                                | 42        | 0.73%   |
| Intel Ethernet Connection I217-LM                                       | 41        | 0.71%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 41        | 0.71%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 41        | 0.71%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 39        | 0.67%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 39        | 0.67%   |
| Huawei E353/E3131                                                       | 37        | 0.64%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 36        | 0.62%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 35        | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1595      | 52.45%  |
| Qualcomm Atheros                  | 584       | 19.2%   |
| Realtek Semiconductor             | 339       | 11.15%  |
| Broadcom                          | 222       | 7.3%    |
| Broadcom Limited                  | 54        | 1.78%   |
| Dell                              | 51        | 1.68%   |
| MediaTek                          | 48        | 1.58%   |
| Ralink                            | 38        | 1.25%   |
| TP-Link                           | 24        | 0.79%   |
| Sierra Wireless                   | 17        | 0.56%   |
| Ralink Technology                 | 12        | 0.39%   |
| Fibocom                           | 10        | 0.33%   |
| Qualcomm Atheros Communications   | 9         | 0.3%    |
| Ericsson Business Mobile Networks | 9         | 0.3%    |
| Qualcomm                          | 6         | 0.2%    |
| Hewlett-Packard                   | 6         | 0.2%    |
| ASUSTek Computer                  | 6         | 0.2%    |
| Microsoft                         | 3         | 0.1%    |
| NetGear                           | 2         | 0.07%   |
| Edimax Technology                 | 2         | 0.07%   |
| Sweex                             | 1         | 0.03%   |
| Sagem                             | 1         | 0.03%   |
| Linksys                           | 1         | 0.03%   |
| Belkin Components                 | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 125       | 4.11%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 124       | 4.07%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 121       | 3.97%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 116       | 3.81%   |
| Intel Wi-Fi 6 AX200                                                     | 109       | 3.58%   |
| Intel Wireless 7260                                                     | 103       | 3.38%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 91        | 2.99%   |
| Intel Wireless 8260                                                     | 90        | 2.96%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 85        | 2.79%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 82        | 2.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 79        | 2.59%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 78        | 2.56%   |
| Intel Wi-Fi 6 AX201                                                     | 77        | 2.53%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 74        | 2.43%   |
| Intel Wireless 7265                                                     | 73        | 2.4%    |
| Intel Wireless 3160                                                     | 65        | 2.13%   |
| Intel Wireless 3165                                                     | 54        | 1.77%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 52        | 1.71%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 52        | 1.71%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 51        | 1.67%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 51        | 1.67%   |
| Broadcom BCM43142 802.11b/g/n                                           | 51        | 1.67%   |
| Intel Centrino Ultimate-N 6300                                          | 49        | 1.61%   |
| Intel WiFi Link 5100                                                    | 45        | 1.48%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 41        | 1.35%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 41        | 1.35%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 39        | 1.28%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 39        | 1.28%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 36        | 1.18%   |
| Intel Centrino Advanced-N 6235                                          | 35        | 1.15%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 33        | 1.08%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 33        | 1.08%   |
| Intel Centrino Advanced-N 6200                                          | 33        | 1.08%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 31        | 1.02%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 30        | 0.99%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 29        | 0.95%   |
| Intel Centrino Wireless-N 2230                                          | 28        | 0.92%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 21        | 0.69%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 21        | 0.69%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 20        | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1232      | 47.2%   |
| Intel                            | 733       | 28.08%  |
| Qualcomm Atheros                 | 207       | 7.93%   |
| Broadcom                         | 137       | 5.25%   |
| Marvell Technology Group         | 66        | 2.53%   |
| Huawei Technologies              | 42        | 1.61%   |
| Broadcom Limited                 | 42        | 1.61%   |
| Samsung Electronics              | 17        | 0.65%   |
| JMicron Technology               | 17        | 0.65%   |
| Xiaomi                           | 14        | 0.54%   |
| ASIX Electronics                 | 14        | 0.54%   |
| Lenovo                           | 13        | 0.5%    |
| Nvidia                           | 12        | 0.46%   |
| DisplayLink                      | 10        | 0.38%   |
| Silicon Integrated Systems [SiS] | 9         | 0.34%   |
| ZTE WCDMA Technologies MSM       | 6         | 0.23%   |
| VIA Technologies                 | 5         | 0.19%   |
| Motorola PCS                     | 5         | 0.19%   |
| TP-Link                          | 4         | 0.15%   |
| Hewlett-Packard                  | 4         | 0.15%   |
| Attansic Technology              | 4         | 0.15%   |
| NetGear                          | 3         | 0.11%   |
| HTC (High Tech Computer)         | 3         | 0.11%   |
| Qualcomm                         | 2         | 0.08%   |
| MediaTek                         | 2         | 0.08%   |
| Tenda                            | 1         | 0.04%   |
| QinHeng Electronics              | 1         | 0.04%   |
| OPPO Electronics                 | 1         | 0.04%   |
| LG Electronics                   | 1         | 0.04%   |
| ICS Advent                       | 1         | 0.04%   |
| HMD Global                       | 1         | 0.04%   |
| Apple                            | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 891       | 33.9%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 242       | 9.21%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 162       | 6.16%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 76        | 2.89%   |
| Intel 82567LM Gigabit Network Connection                          | 53        | 2.02%   |
| Intel Ethernet Connection I218-LM                                 | 46        | 1.75%   |
| Intel Ethernet Connection (4) I219-LM                             | 45        | 1.71%   |
| Intel 82577LM Gigabit Network Connection                          | 42        | 1.6%    |
| Intel Ethernet Connection I217-LM                                 | 41        | 1.56%   |
| Huawei E353/E3131                                                 | 37        | 1.41%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 35        | 1.33%   |
| Intel Ethernet Connection (6) I219-V                              | 31        | 1.18%   |
| Intel Ethernet Connection (3) I218-LM                             | 31        | 1.18%   |
| Intel Ethernet Connection I219-LM                                 | 28        | 1.07%   |
| Intel Ethernet Connection (7) I219-LM                             | 26        | 0.99%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 23        | 0.88%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 22        | 0.84%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 22        | 0.84%   |
| Intel Ethernet Connection (4) I219-V                              | 21        | 0.8%    |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 20        | 0.76%   |
| Intel 82579V Gigabit Network Connection                           | 18        | 0.68%   |
| Intel Ethernet Connection (2) I219-LM                             | 17        | 0.65%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 17        | 0.65%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 16        | 0.61%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 16        | 0.61%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 16        | 0.61%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 15        | 0.57%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 14        | 0.53%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 14        | 0.53%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 14        | 0.53%   |
| Intel Ethernet Connection I219-V                                  | 14        | 0.53%   |
| Intel Ethernet Connection (5) I219-LM                             | 14        | 0.53%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 14        | 0.53%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 13        | 0.49%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 13        | 0.49%   |
| Intel Ethernet Connection (11) I219-LM                            | 13        | 0.49%   |
| Intel 82566MM Gigabit Network Connection                          | 13        | 0.49%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 13        | 0.49%   |
| Intel Ethernet Connection (13) I219-V                             | 12        | 0.46%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 11        | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2854      | 52.24%  |
| Ethernet | 2503      | 45.82%  |
| Modem    | 100       | 1.83%   |
| Unknown  | 6         | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2344      | 77.62%  |
| Ethernet | 676       | 22.38%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2345      | 80.92%  |
| 1     | 509       | 17.56%  |
| 0     | 34        | 1.17%   |
| 3     | 10        | 0.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2706      | 92.51%  |
| Yes  | 219       | 7.49%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1069      | 47.34%  |
| Qualcomm Atheros Communications | 237       | 10.5%   |
| Realtek Semiconductor           | 170       | 7.53%   |
| Broadcom                        | 167       | 7.4%    |
| IMC Networks                    | 120       | 5.31%   |
| Dell                            | 88        | 3.9%    |
| Foxconn / Hon Hai               | 74        | 3.28%   |
| Lite-On Technology              | 70        | 3.1%    |
| Hewlett-Packard                 | 61        | 2.7%    |
| Toshiba                         | 31        | 1.37%   |
| ASUSTek Computer                | 31        | 1.37%   |
| Cambridge Silicon Radio         | 26        | 1.15%   |
| Apple                           | 23        | 1.02%   |
| Ralink                          | 21        | 0.93%   |
| Foxconn International           | 17        | 0.75%   |
| Realtek                         | 12        | 0.53%   |
| Alps Electric                   | 8         | 0.35%   |
| Chicony Electronics             | 6         | 0.27%   |
| Taiyo Yuden                     | 5         | 0.22%   |
| Ralink Technology               | 3         | 0.13%   |
| MediaTek                        | 3         | 0.13%   |
| Integrated System Solution      | 3         | 0.13%   |
| USI                             | 2         | 0.09%   |
| Opticis                         | 2         | 0.09%   |
| Micro Star International        | 2         | 0.09%   |
| Askey Computer                  | 2         | 0.09%   |
| TP-Link                         | 1         | 0.04%   |
| Fujitsu                         | 1         | 0.04%   |
| Edimax Technology               | 1         | 0.04%   |
| Creative Technology             | 1         | 0.04%   |
| AboCom Systems                  | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 500       | 22.13%  |
| Intel AX201 Bluetooth                               | 166       | 7.35%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 142       | 6.29%   |
| Realtek Bluetooth Radio                             | 107       | 4.74%   |
| Qualcomm Atheros  Bluetooth Device                  | 105       | 4.65%   |
| Intel AX200 Bluetooth                               | 103       | 4.56%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 61        | 2.7%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 56        | 2.48%   |
| IMC Networks Bluetooth Radio                        | 53        | 2.35%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 41        | 1.81%   |
| Broadcom BCM2045B (BDC-2.1)                         | 39        | 1.73%   |
| Realtek  Bluetooth 4.2 Adapter                      | 35        | 1.55%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 35        | 1.55%   |
| Intel Wireless-AC 3168 Bluetooth                    | 30        | 1.33%   |
| Dell BCM20702A0 Bluetooth Module                    | 29        | 1.28%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 26        | 1.15%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 25        | 1.11%   |
| HP Broadcom 2070 Bluetooth Combo                    | 25        | 1.11%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 25        | 1.11%   |
| Dell DW375 Bluetooth Module                         | 24        | 1.06%   |
| Ralink RT3290 Bluetooth                             | 21        | 0.93%   |
| IMC Networks Wireless_Device                        | 21        | 0.93%   |
| IMC Networks Bluetooth Device                       | 21        | 0.93%   |
| Lite-On Bluetooth Device                            | 20        | 0.89%   |
| Realtek RTL8723B Bluetooth                          | 19        | 0.84%   |
| Intel Bluetooth Device                              | 19        | 0.84%   |
| Lite-On Atheros AR3012 Bluetooth                    | 17        | 0.75%   |
| Foxconn International BCM43142A0 Bluetooth module   | 17        | 0.75%   |
| Broadcom BCM2070 Bluetooth Device                   | 17        | 0.75%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 15        | 0.66%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 15        | 0.66%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 14        | 0.62%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 14        | 0.62%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 13        | 0.58%   |
| Foxconn / Hon Hai Bluetooth Device                  | 13        | 0.58%   |
| Toshiba Integrated Bluetooth HCI                    | 12        | 0.53%   |
| Realtek 802.11ac WLAN Adapter                       | 12        | 0.53%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 12        | 0.53%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 12        | 0.53%   |
| Dell Wireless 360 Bluetooth                         | 12        | 0.53%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 2382      | 66.99%  |
| AMD                                          | 520       | 14.62%  |
| Nvidia                                       | 445       | 12.51%  |
| C-Media Electronics                          | 23        | 0.65%   |
| Creative Technology                          | 18        | 0.51%   |
| Lenovo                                       | 16        | 0.45%   |
| Realtek Semiconductor                        | 15        | 0.42%   |
| Logitech                                     | 12        | 0.34%   |
| Silicon Integrated Systems [SiS]             | 11        | 0.31%   |
| Plantronics                                  | 11        | 0.31%   |
| GN Netcom                                    | 10        | 0.28%   |
| Hewlett-Packard                              | 7         | 0.2%    |
| VIA Technologies                             | 6         | 0.17%   |
| SteelSeries ApS                              | 6         | 0.17%   |
| Texas Instruments                            | 5         | 0.14%   |
| JMTek                                        | 5         | 0.14%   |
| Generalplus Technology                       | 5         | 0.14%   |
| Dell                                         | 5         | 0.14%   |
| Focusrite-Novation                           | 4         | 0.11%   |
| Sennheiser Communications                    | 3         | 0.08%   |
| Samson Technologies                          | 3         | 0.08%   |
| Kingston Technology                          | 3         | 0.08%   |
| BEHRINGER International                      | 3         | 0.08%   |
| TTGK Technology                              | 2         | 0.06%   |
| Sony                                         | 2         | 0.06%   |
| FUXIN                                        | 2         | 0.06%   |
| DSEA A/S                                     | 2         | 0.06%   |
| AudioQuest                                   | 2         | 0.06%   |
| ASUSTek Computer                             | 2         | 0.06%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.03%   |
| Yamaha                                       | 1         | 0.03%   |
| USB MICROPHONE                               | 1         | 0.03%   |
| Turtle Beach                                 | 1         | 0.03%   |
| THX                                          | 1         | 0.03%   |
| Thesycon Systemsoftware & Consulting         | 1         | 0.03%   |
| Silicon Motion                               | 1         | 0.03%   |
| SAVITECH                                     | 1         | 0.03%   |
| RODE Microphones                             | 1         | 0.03%   |
| Razer USA                                    | 1         | 0.03%   |
| Native Instruments                           | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 280       | 6.57%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 275       | 6.46%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 271       | 6.36%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 194       | 4.56%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 177       | 4.16%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 145       | 3.4%    |
| Intel 8 Series HD Audio Controller                                                                | 137       | 3.22%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 135       | 3.17%   |
| Intel Cannon Lake PCH cAVS                                                                        | 129       | 3.03%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 124       | 2.91%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 113       | 2.65%   |
| Intel Broadwell-U Audio Controller                                                                | 111       | 2.61%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 111       | 2.61%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 110       | 2.58%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 101       | 2.37%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 99        | 2.32%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 84        | 1.97%   |
| AMD FCH Azalia Controller                                                                         | 83        | 1.95%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 78        | 1.83%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 75        | 1.76%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 73        | 1.71%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 69        | 1.62%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 62        | 1.46%   |
| Intel CM238 HD Audio Controller                                                                   | 59        | 1.39%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 51        | 1.2%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 49        | 1.15%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 46        | 1.08%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 43        | 1.01%   |
| Intel Comet Lake PCH cAVS                                                                         | 43        | 1.01%   |
| AMD Kabini HDMI/DP Audio                                                                          | 34        | 0.8%    |
| AMD Wrestler HDMI Audio                                                                           | 33        | 0.77%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 32        | 0.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 30        | 0.7%    |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 30        | 0.7%    |
| Nvidia TU116 High Definition Audio Controller                                                     | 26        | 0.61%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 26        | 0.61%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 26        | 0.61%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 25        | 0.59%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 24        | 0.56%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 22        | 0.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 643       | 28.12%  |
| SK hynix                     | 468       | 20.46%  |
| Micron Technology            | 261       | 11.41%  |
| Kingston                     | 233       | 10.19%  |
| Unknown                      | 164       | 7.17%   |
| GOODRAM                      | 116       | 5.07%   |
| Crucial                      | 92        | 4.02%   |
| Ramaxel Technology           | 61        | 2.67%   |
| A-DATA Technology            | 48        | 2.1%    |
| Nanya Technology             | 41        | 1.79%   |
| Elpida                       | 38        | 1.66%   |
| Patriot                      | 18        | 0.79%   |
| Unknown                      | 13        | 0.57%   |
| Unknown (ABCD)               | 12        | 0.52%   |
| Corsair                      | 11        | 0.48%   |
| Qimonda                      | 10        | 0.44%   |
| Wilk                         | 9         | 0.39%   |
| ASint Technology             | 7         | 0.31%   |
| G.Skill                      | 5         | 0.22%   |
| fef5                         | 4         | 0.17%   |
| 48spaces                     | 4         | 0.17%   |
| Unifosa                      | 3         | 0.13%   |
| Apacer                       | 3         | 0.13%   |
| Transcend                    | 2         | 0.09%   |
| Toshiba                      | 2         | 0.09%   |
| SHARETRONIC                  | 2         | 0.09%   |
| Patriot Memory (PDP Systems) | 2         | 0.09%   |
| Unknown (8A02)               | 1         | 0.04%   |
| Unknown (768A)               | 1         | 0.04%   |
| Team                         | 1         | 0.04%   |
| Swissbit                     | 1         | 0.04%   |
| Smart                        | 1         | 0.04%   |
| Silicon Power                | 1         | 0.04%   |
| PUSKILL                      | 1         | 0.04%   |
| PNY                          | 1         | 0.04%   |
| Goldkey                      | 1         | 0.04%   |
| ff                           | 1         | 0.04%   |
| ChangXin Memory              | 1         | 0.04%   |
| 8CFD000080AD                 | 1         | 0.04%   |
| 4ea5                         | 1         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 37        | 1.51%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s            | 37        | 1.51%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 31        | 1.27%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 28        | 1.14%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 27        | 1.1%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 27        | 1.1%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 26        | 1.06%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 25        | 1.02%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s         | 25        | 1.02%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 24        | 0.98%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 24        | 0.98%   |
| GOODRAM RAM GR2666S464L19/16G 16GB SODIMM DDR4 2667MT/s          | 24        | 0.98%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 23        | 0.94%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 22        | 0.9%    |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM 1600MT/s                 | 21        | 0.86%   |
| GOODRAM RAM GR3200S464L22/16G 16GB SODIMM DDR4 3200MT/s          | 19        | 0.78%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 17        | 0.69%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s            | 16        | 0.65%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 975MT/s             | 15        | 0.61%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s         | 15        | 0.61%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 15        | 0.61%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 15        | 0.61%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 15        | 0.61%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 14        | 0.57%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 14        | 0.57%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 14        | 0.57%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 14        | 0.57%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 14        | 0.57%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s        | 13        | 0.53%   |
| Samsung RAM M471B5673FH0-CF8 2048MB SODIMM DDR3 1067MT/s         | 13        | 0.53%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 13        | 0.53%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 13        | 0.53%   |
| Unknown                                                          | 13        | 0.53%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 12        | 0.49%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 12        | 0.49%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 12        | 0.49%   |
| Kingston RAM KHX2400C14S4/16G 16GB SODIMM DDR4 2667MT/s          | 12        | 0.49%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 11        | 0.45%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 11        | 0.45%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s            | 11        | 0.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 737       | 39.29%  |
| DDR4    | 734       | 39.13%  |
| DDR2    | 165       | 8.8%    |
| SDRAM   | 77        | 4.1%    |
| LPDDR4  | 65        | 3.46%   |
| LPDDR3  | 37        | 1.97%   |
| Unknown | 18        | 0.96%   |
| DDR5    | 16        | 0.85%   |
| LPDDR5  | 11        | 0.59%   |
| DDR     | 11        | 0.59%   |
| DRAM    | 5         | 0.27%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| SODIMM          | 1716      | 93.11%  |
| Row Of Chips    | 96        | 5.21%   |
| Unknown         | 12        | 0.65%   |
| Chip            | 11        | 0.6%    |
| DIMM            | 7         | 0.38%   |
| Proprietary Car | 1         | 0.05%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Notebooks | Percent |
|---------|-----------|---------|
| 8192    | 655       | 31.73%  |
| 4096    | 622       | 30.14%  |
| 2048    | 322       | 15.6%   |
| 16384   | 295       | 14.29%  |
| 1024    | 115       | 5.57%   |
| 32768   | 38        | 1.84%   |
| 512     | 10        | 0.48%   |
| Unknown | 4         | 0.19%   |
| 131072  | 1         | 0.05%   |
| 1536    | 1         | 0.05%   |
| 256     | 1         | 0.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 537       | 26.22%  |
| 2667    | 356       | 17.38%  |
| 3200    | 290       | 14.16%  |
| 1334    | 131       | 6.4%    |
| 2400    | 120       | 5.86%   |
| 2133    | 86        | 4.2%    |
| 667     | 82        | 4%      |
| 1333    | 71        | 3.47%   |
| Unknown | 55        | 2.69%   |
| 4199    | 43        | 2.1%    |
| 1067    | 39        | 1.9%    |
| 800     | 38        | 1.86%   |
| 2048    | 27        | 1.32%   |
| 975     | 26        | 1.27%   |
| 533     | 23        | 1.12%   |
| 4267    | 20        | 0.98%   |
| 4800    | 17        | 0.83%   |
| 3266    | 14        | 0.68%   |
| 1867    | 14        | 0.68%   |
| 8400    | 11        | 0.54%   |
| 6400    | 11        | 0.54%   |
| 1066    | 10        | 0.49%   |
| 4266    | 7         | 0.34%   |
| 3733    | 5         | 0.24%   |
| 400     | 4         | 0.2%    |
| 333     | 4         | 0.2%    |
| 2933    | 2         | 0.1%    |
| 2134    | 1         | 0.05%   |
| 1777    | 1         | 0.05%   |
| 1776    | 1         | 0.05%   |
| 1639    | 1         | 0.05%   |
| 933     | 1         | 0.05%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 10        | 43.48%  |
| Samsung Electronics | 5         | 21.74%  |
| Canon               | 3         | 13.04%  |
| Seiko Epson         | 2         | 8.7%    |
| Zebra               | 1         | 4.35%   |
| Xerox               | 1         | 4.35%   |
| Brother Industries  | 1         | 4.35%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Samsung M2020 Series                    | 2         | 8.7%    |
| HP Deskjet F2280 series                 | 2         | 8.7%    |
| Zebra ZTC GX420t                        | 1         | 4.35%   |
| Xerox Phaser 6000B                      | 1         | 4.35%   |
| Seiko Epson L396 Series                 | 1         | 4.35%   |
| Seiko Epson AL-M310DN                   | 1         | 4.35%   |
| Samsung Xerox Phaser 3117 Laser Printer | 1         | 4.35%   |
| Samsung SCX-6545 Series                 | 1         | 4.35%   |
| Samsung SCX-3400 Series                 | 1         | 4.35%   |
| HP LaserJet P1102                       | 1         | 4.35%   |
| HP LaserJet P1005                       | 1         | 4.35%   |
| HP LaserJet 1020                        | 1         | 4.35%   |
| HP LaserJet 1018                        | 1         | 4.35%   |
| HP Ink Tank Wireless 410 series         | 1         | 4.35%   |
| HP Deskjet Ink Advant K209a-z           | 1         | 4.35%   |
| HP Deskjet D1500 series                 | 1         | 4.35%   |
| HP Deskjet 2540 series                  | 1         | 4.35%   |
| Canon PIXMA MG3000 series               | 1         | 4.35%   |
| Canon MG5600 series                     | 1         | 4.35%   |
| Canon LiDE 400                          | 1         | 4.35%   |
| Brother DCP-1610W                       | 1         | 4.35%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Canon                  | 2         | 50%     |
| Plustek                | 1         | 25%     |
| Microtek International | 1         | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Plustek OpticSlim 1200 Scanner         | 1         | 25%     |
| Microtek International USB1200 Scanner | 1         | 25%     |
| Canon CanoScan N670U/N676U/LiDE 20     | 1         | 25%     |
| Canon CanoScan N1240U/LiDE 30          | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 606       | 24.28%  |
| IMC Networks                           | 260       | 10.42%  |
| Microdia                               | 250       | 10.02%  |
| Realtek Semiconductor                  | 231       | 9.25%   |
| Bison Electronics                      | 146       | 5.85%   |
| Sunplus Innovation Technology          | 137       | 5.49%   |
| Quanta                                 | 123       | 4.93%   |
| Suyin                                  | 116       | 4.65%   |
| Cheng Uei Precision Industry (Foxlink) | 84        | 3.37%   |
| Syntek                                 | 80        | 3.21%   |
| Acer                                   | 62        | 2.48%   |
| Silicon Motion                         | 56        | 2.24%   |
| Lite-On Technology                     | 54        | 2.16%   |
| Ricoh                                  | 30        | 1.2%    |
| Luxvisions Innotech Limited            | 29        | 1.16%   |
| Logitech                               | 28        | 1.12%   |
| Alcor Micro                            | 27        | 1.08%   |
| Lenovo                                 | 26        | 1.04%   |
| Apple                                  | 25        | 1%      |
| Z-Star Microelectronics                | 15        | 0.6%    |
| DigiTech                               | 11        | 0.44%   |
| Sonix Technology                       | 10        | 0.4%    |
| Intel                                  | 10        | 0.4%    |
| Creative Technology                    | 10        | 0.4%    |
| Samsung Electronics                    | 9         | 0.36%   |
| Primax Electronics                     | 9         | 0.36%   |
| ALi                                    | 9         | 0.36%   |
| Microsoft                              | 5         | 0.2%    |
| Importek                               | 5         | 0.2%    |
| Generalplus Technology                 | 5         | 0.2%    |
| Sunplus Technology                     | 3         | 0.12%   |
| Alpha Imaging Technology               | 3         | 0.12%   |
| SunplusIT                              | 2         | 0.08%   |
| OmniVision Technologies                | 2         | 0.08%   |
| MacroSilicon                           | 2         | 0.08%   |
| Foxconn / Hon Hai                      | 2         | 0.08%   |
| Cubeternet                             | 2         | 0.08%   |
| Xiaomi                                 | 1         | 0.04%   |
| WaveRider Communications               | 1         | 0.04%   |
| Trust                                  | 1         | 0.04%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 117       | 4.67%   |
| Microdia Integrated_Webcam_HD            | 87        | 3.48%   |
| Realtek Integrated_Webcam_HD             | 74        | 2.96%   |
| IMC Networks Integrated Camera           | 69        | 2.76%   |
| IMC Networks USB2.0 HD UVC WebCam        | 65        | 2.6%    |
| Sunplus Integrated_Webcam_HD             | 56        | 2.24%   |
| Chicony Lenovo EasyCamera                | 47        | 1.88%   |
| Chicony HD WebCam                        | 43        | 1.72%   |
| Microdia Integrated Webcam               | 42        | 1.68%   |
| Suyin Integrated_Webcam_HD               | 36        | 1.44%   |
| Syntek Lenovo EasyCamera                 | 30        | 1.2%    |
| Syntek Integrated Camera                 | 30        | 1.2%    |
| Realtek Lenovo EasyCamera                | 29        | 1.16%   |
| Bison Lenovo EasyCamera                  | 28        | 1.12%   |
| Quanta HP TrueVision HD Camera           | 27        | 1.08%   |
| Realtek USB Camera                       | 25        | 1%      |
| Chicony HP HD Camera                     | 25        | 1%      |
| Lite-On Integrated Camera                | 23        | 0.92%   |
| Acer Integrated Camera                   | 23        | 0.92%   |
| Bison Integrated Camera                  | 22        | 0.88%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 21        | 0.84%   |
| Chicony USB2.0 HD UVC WebCam             | 21        | 0.84%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 20        | 0.8%    |
| Bison Lenovo Integrated Webcam           | 20        | 0.8%    |
| Realtek Integrated Webcam HD             | 19        | 0.76%   |
| Quanta HD User Facing                    | 19        | 0.76%   |
| Microdia Laptop_Integrated_Webcam_HD     | 19        | 0.76%   |
| Bison SunplusIT Integrated Camera        | 19        | 0.76%   |
| Acer Lenovo EasyCamera                   | 19        | 0.76%   |
| Realtek Integrated Webcam                | 18        | 0.72%   |
| IMC Networks Integrated Webcam           | 17        | 0.68%   |
| Chicony USB 2.0 Camera                   | 17        | 0.68%   |
| Chicony USB2.0 VGA UVC WebCam            | 16        | 0.64%   |
| Chicony Integrated Camera (1280x720@30)  | 16        | 0.64%   |
| Sunplus HD WebCam                        | 15        | 0.6%    |
| Lite-On HP HD Camera                     | 15        | 0.6%    |
| Chicony Lenovo Integrated Camera (0.3MP) | 15        | 0.6%    |
| IMC Networks UVC VGA Webcam              | 13        | 0.52%   |
| Chicony VGA WebCam                       | 13        | 0.52%   |
| Chicony TOSHIBA Web Camera - HD          | 13        | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 191       | 37.23%  |
| Synaptics                          | 113       | 22.03%  |
| Shenzhen Goodix Technology         | 64        | 12.48%  |
| AuthenTec                          | 60        | 11.7%   |
| Upek                               | 37        | 7.21%   |
| Elan Microelectronics              | 19        | 3.7%    |
| LighTuning Technology              | 15        | 2.92%   |
| STMicroelectronics                 | 13        | 2.53%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.19%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 41        | 7.99%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 41        | 7.99%   |
| Shenzhen Goodix  Fingerprint Device                                        | 37        | 7.21%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 35        | 6.82%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 27        | 5.26%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 23        | 4.48%   |
| AuthenTec AES2810                                                          | 23        | 4.48%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 22        | 4.29%   |
| Shenzhen Goodix Fingerprint Reader                                         | 21        | 4.09%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 18        | 3.51%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 14        | 2.73%   |
| Validity Sensors VFS491                                                    | 13        | 2.53%   |
| STMicroelectronics Fingerprint Reader                                      | 13        | 2.53%   |
| Elan ELAN:Fingerprint                                                      | 13        | 2.53%   |
| Synaptics Fingerprint reader [HP G6]                                       | 12        | 2.34%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 11        | 2.14%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 10        | 1.95%   |
| Validity Sensors Fingerprint scanner                                       | 10        | 1.95%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 10        | 1.95%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 9         | 1.75%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 9         | 1.75%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 8         | 1.56%   |
| Validity Sensors Synaptics WBDI                                            | 7         | 1.36%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 1.36%   |
| AuthenTec AES1600                                                          | 7         | 1.36%   |
| Shenzhen Goodix FingerPrint                                                | 6         | 1.17%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 6         | 1.17%   |
| Elan ELAN:ARM-M4                                                           | 6         | 1.17%   |
| Validity Sensors VFS Fingerprint sensor                                    | 5         | 0.97%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 0.97%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 0.78%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 0.78%   |
| Synaptics WBDI                                                             | 4         | 0.78%   |
| Synaptics  WBDI                                                            | 4         | 0.78%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 4         | 0.78%   |
| LighTuning Fingerprint Reader                                              | 4         | 0.78%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 4         | 0.78%   |
| Synaptics WBDI Device                                                      | 3         | 0.58%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.39%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 0.39%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 228       | 57.14%  |
| Alcor Micro               | 78        | 19.55%  |
| O2 Micro                  | 45        | 11.28%  |
| Upek                      | 22        | 5.51%   |
| Lenovo                    | 20        | 5.01%   |
| Gemalto (was Gemplus)     | 4         | 1%      |
| Clay Logic                | 1         | 0.25%   |
| Aladdin Knowledge Systems | 1         | 0.25%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 76        | 19.05%  |
| Broadcom BCM5880 Secure Applications Processor                               | 70        | 17.54%  |
| Broadcom 58200                                                               | 59        | 14.79%  |
| Broadcom 5880                                                                | 57        | 14.29%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 41        | 10.28%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 38        | 9.52%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 22        | 5.51%   |
| Lenovo Integrated Smart Card Reader                                          | 20        | 5.01%   |
| O2 Micro Oz776 SmartCard Reader                                              | 7         | 1.75%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 0.75%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.25%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.25%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.25%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.25%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.25%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.25%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1699      | 57.11%  |
| 1     | 992       | 33.34%  |
| 2     | 243       | 8.17%   |
| 3     | 33        | 1.11%   |
| 4     | 3         | 0.1%    |
| 7     | 2         | 0.07%   |
| 5     | 2         | 0.07%   |
| 6     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 508       | 32.63%  |
| Chipcard                 | 361       | 23.19%  |
| Graphics card            | 333       | 21.39%  |
| Net/wireless             | 96        | 6.17%   |
| Multimedia controller    | 49        | 3.15%   |
| Storage                  | 48        | 3.08%   |
| Bluetooth                | 44        | 2.83%   |
| Camera                   | 32        | 2.06%   |
| Communication controller | 26        | 1.67%   |
| Card reader              | 17        | 1.09%   |
| Sound                    | 11        | 0.71%   |
| Modem                    | 8         | 0.51%   |
| Net/ethernet             | 5         | 0.32%   |
| Firewire controller      | 5         | 0.32%   |
| Flash memory             | 4         | 0.26%   |
| Dvb card                 | 3         | 0.19%   |
| Network                  | 2         | 0.13%   |
| Wireless                 | 1         | 0.06%   |
| Unclassified device      | 1         | 0.06%   |
| Tv card                  | 1         | 0.06%   |
| Storage/raid             | 1         | 0.06%   |
| Storage/ide              | 1         | 0.06%   |

