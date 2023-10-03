Rocky Linux - Tested Hardware & Statistics
------------------------------------------

A project to collect tested hardware configurations for Rocky Linux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Rocky_Linux/Desktop/README.md) and [notebooks](/Dist/Rocky_Linux/Notebook/README.md).

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

Total: 213

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Shenzhen M... | HX90G                       | Desktop     | [a6e9f6c7fc](https://linux-hardware.org/?probe=a6e9f6c7fc) | Oct 01, 2023 |
| Dell          | 0D24M8 A01                  | Desktop     | [214eb681ad](https://linux-hardware.org/?probe=214eb681ad) | Oct 01, 2023 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [08fb652352](https://linux-hardware.org/?probe=08fb652352) | Sep 29, 2023 |
| Intel         | NUC12WSBi7 M46422-303       | Mini pc     | [28599e161c](https://linux-hardware.org/?probe=28599e161c) | Sep 15, 2023 |
| Clevo         | P170EM                      | Notebook    | [ee87854652](https://linux-hardware.org/?probe=ee87854652) | Sep 14, 2023 |
| ASUSTek       | F1A55-M LX PLUS             | Desktop     | [a2aebc52bd](https://linux-hardware.org/?probe=a2aebc52bd) | Sep 03, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [ac1293fbf6](https://linux-hardware.org/?probe=ac1293fbf6) | Sep 02, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [1273e75666](https://linux-hardware.org/?probe=1273e75666) | Sep 02, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [88b6546b70](https://linux-hardware.org/?probe=88b6546b70) | Sep 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [9faf6d1836](https://linux-hardware.org/?probe=9faf6d1836) | Aug 30, 2023 |
| Lenovo        | Yoga 720-13IKB 80X6         | Convertible | [e38546c509](https://linux-hardware.org/?probe=e38546c509) | Aug 30, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [40802d54a7](https://linux-hardware.org/?probe=40802d54a7) | Aug 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [62ca959d73](https://linux-hardware.org/?probe=62ca959d73) | Aug 21, 2023 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | Notebook    | [ceb8407c9a](https://linux-hardware.org/?probe=ceb8407c9a) | Aug 21, 2023 |
| Lenovo        | 1048 SDK0J40697 WIN 3305... | Desktop     | [e584e6c368](https://linux-hardware.org/?probe=e584e6c368) | Aug 16, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [fb346f4b46](https://linux-hardware.org/?probe=fb346f4b46) | Aug 15, 2023 |
| ASRock        | X670E Pro RS                | Desktop     | [baa9e459cc](https://linux-hardware.org/?probe=baa9e459cc) | Aug 09, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [32fd45f163](https://linux-hardware.org/?probe=32fd45f163) | Aug 04, 2023 |
| ATOPNUC       | MA90                        | Mini pc     | [47f4b18820](https://linux-hardware.org/?probe=47f4b18820) | Aug 01, 2023 |
| Lenovo        | ThinkPad T430 2347FF9       | Notebook    | [30354c1f38](https://linux-hardware.org/?probe=30354c1f38) | Jul 31, 2023 |
| MSI           | PRO B650-P WIFI             | Desktop     | [92abff2d6e](https://linux-hardware.org/?probe=92abff2d6e) | Jul 31, 2023 |
| MSI           | PRO B650-P WIFI             | Desktop     | [d1c158eebc](https://linux-hardware.org/?probe=d1c158eebc) | Jul 31, 2023 |
| HP            | ZBook 15u G5                | Notebook    | [1b0bb754bc](https://linux-hardware.org/?probe=1b0bb754bc) | Jul 28, 2023 |
| HP            | ZBook 15u G5                | Notebook    | [54684f905d](https://linux-hardware.org/?probe=54684f905d) | Jul 28, 2023 |
| HP            | 0AECh D                     | Desktop     | [58f6dd1695](https://linux-hardware.org/?probe=58f6dd1695) | Jul 14, 2023 |
| Supermicro    | X11DPU                      | Server      | [0b1feb460c](https://linux-hardware.org/?probe=0b1feb460c) | Jul 12, 2023 |
| Supermicro    | X11DPU                      | Server      | [1cbd9c2062](https://linux-hardware.org/?probe=1cbd9c2062) | Jul 12, 2023 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [b4b1f263a8](https://linux-hardware.org/?probe=b4b1f263a8) | Jul 08, 2023 |
| Lenovo        | ThinkPad X270 20HMS79Q00    | Notebook    | [6a9d34223b](https://linux-hardware.org/?probe=6a9d34223b) | Jul 04, 2023 |
| ASUSTek       | G752VM                      | Notebook    | [b518236bd7](https://linux-hardware.org/?probe=b518236bd7) | Jun 21, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [2310257292](https://linux-hardware.org/?probe=2310257292) | Jun 19, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [ee6f9906b5](https://linux-hardware.org/?probe=ee6f9906b5) | Jun 19, 2023 |
| HP            | EliteBook 1040 14 inch G... | Notebook    | [47b86a7e60](https://linux-hardware.org/?probe=47b86a7e60) | Jun 14, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [57b238a5ff](https://linux-hardware.org/?probe=57b238a5ff) | Jun 08, 2023 |
| ASUSTek       | UX430UNR                    | Notebook    | [00ab711e0a](https://linux-hardware.org/?probe=00ab711e0a) | Jun 02, 2023 |
| Lenovo        | 3730 SDK0T76463 WIN 3422... | Desktop     | [da8705e5a7](https://linux-hardware.org/?probe=da8705e5a7) | May 31, 2023 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [530b841978](https://linux-hardware.org/?probe=530b841978) | May 25, 2023 |
| ASRock        | AM1B-ITX                    | Desktop     | [a2e80bffac](https://linux-hardware.org/?probe=a2e80bffac) | May 19, 2023 |
| ASRock        | AM1B-ITX                    | Desktop     | [d0633ac39d](https://linux-hardware.org/?probe=d0633ac39d) | May 19, 2023 |
| HP            | ProBook 645 G1              | Notebook    | [f82952db4b](https://linux-hardware.org/?probe=f82952db4b) | May 14, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [30d9e5ca7d](https://linux-hardware.org/?probe=30d9e5ca7d) | May 11, 2023 |
| Beelink       | BT3 PRO                     | Notebook    | [fb99607da3](https://linux-hardware.org/?probe=fb99607da3) | May 08, 2023 |
| AZW           | MINI S                      | Desktop     | [d7ee12a01b](https://linux-hardware.org/?probe=d7ee12a01b) | May 08, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [5cff94f71e](https://linux-hardware.org/?probe=5cff94f71e) | May 07, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | Notebook    | [43e6345cb8](https://linux-hardware.org/?probe=43e6345cb8) | May 03, 2023 |
| Dell          | 0D735T A00                  | Desktop     | [3070f4e7da](https://linux-hardware.org/?probe=3070f4e7da) | May 02, 2023 |
| Dell          | 06D7TR A00                  | Desktop     | [6fe7179a50](https://linux-hardware.org/?probe=6fe7179a50) | May 01, 2023 |
| Dell          | 0Y2MRG A00                  | Desktop     | [5f765d4d9c](https://linux-hardware.org/?probe=5f765d4d9c) | Apr 29, 2023 |
| Dell          | 0Y2MRG A00                  | Desktop     | [62a4a8b0b5](https://linux-hardware.org/?probe=62a4a8b0b5) | Apr 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | Notebook    | [18306b3af6](https://linux-hardware.org/?probe=18306b3af6) | Apr 23, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [ae500cf4af](https://linux-hardware.org/?probe=ae500cf4af) | Apr 22, 2023 |
| Gigabyte      | C621-WD12-IPMI M18907       | Server      | [030b77c94d](https://linux-hardware.org/?probe=030b77c94d) | Mar 21, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [7c909a0c5a](https://linux-hardware.org/?probe=7c909a0c5a) | Mar 18, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [113406acd8](https://linux-hardware.org/?probe=113406acd8) | Mar 18, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [e967c05c1e](https://linux-hardware.org/?probe=e967c05c1e) | Mar 18, 2023 |
| Dell          | Inspiron 7573               | Convertible | [c89a114562](https://linux-hardware.org/?probe=c89a114562) | Mar 17, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [40f92632ab](https://linux-hardware.org/?probe=40f92632ab) | Mar 16, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [fd875a6058](https://linux-hardware.org/?probe=fd875a6058) | Mar 16, 2023 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [a4c449eef4](https://linux-hardware.org/?probe=a4c449eef4) | Mar 16, 2023 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [5b55ac3757](https://linux-hardware.org/?probe=5b55ac3757) | Mar 15, 2023 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [61af17e1cd](https://linux-hardware.org/?probe=61af17e1cd) | Mar 13, 2023 |
| AZW           | GTR V02                     | Desktop     | [fcd41fbe77](https://linux-hardware.org/?probe=fcd41fbe77) | Mar 10, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [8e02418ca7](https://linux-hardware.org/?probe=8e02418ca7) | Mar 05, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [5510fed545](https://linux-hardware.org/?probe=5510fed545) | Mar 04, 2023 |
| Dell          | 0PM2CW A04                  | Server      | [154f8780de](https://linux-hardware.org/?probe=154f8780de) | Feb 28, 2023 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [b27fb5e204](https://linux-hardware.org/?probe=b27fb5e204) | Feb 26, 2023 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [a2356a66ba](https://linux-hardware.org/?probe=a2356a66ba) | Feb 26, 2023 |
| Sapphire      | PE-AM2RS690V2               | Desktop     | [8aa6cda98e](https://linux-hardware.org/?probe=8aa6cda98e) | Feb 26, 2023 |
| ASUSTek       | ROG Strix G713RW_G713RW     | Notebook    | [5368c6d0a2](https://linux-hardware.org/?probe=5368c6d0a2) | Feb 23, 2023 |
| HP            | ProLiant DL380p Gen8        | Server      | [b82d6321ef](https://linux-hardware.org/?probe=b82d6321ef) | Feb 19, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [feae434e9e](https://linux-hardware.org/?probe=feae434e9e) | Feb 18, 2023 |
| Lenovo        | ThinkPad T480 20L6S8B500    | Notebook    | [b4cbe5bf11](https://linux-hardware.org/?probe=b4cbe5bf11) | Feb 16, 2023 |
| HP            | 1587h                       | Desktop     | [312effb7b7](https://linux-hardware.org/?probe=312effb7b7) | Feb 14, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [9de6fe5d90](https://linux-hardware.org/?probe=9de6fe5d90) | Feb 14, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [68463d6d4b](https://linux-hardware.org/?probe=68463d6d4b) | Feb 13, 2023 |
| Lenovo        | IdeaPad S210 Touch 20257    | Notebook    | [d132553080](https://linux-hardware.org/?probe=d132553080) | Feb 13, 2023 |
| Dell          | Latitude 5420               | Notebook    | [60cc86374d](https://linux-hardware.org/?probe=60cc86374d) | Feb 12, 2023 |
| Dell          | Latitude 5420               | Notebook    | [63a576e744](https://linux-hardware.org/?probe=63a576e744) | Feb 12, 2023 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [7fec987264](https://linux-hardware.org/?probe=7fec987264) | Feb 12, 2023 |
| Dell          | 08HPGT A01                  | Desktop     | [bf2c6ebd43](https://linux-hardware.org/?probe=bf2c6ebd43) | Feb 03, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | Notebook    | [e07858d71e](https://linux-hardware.org/?probe=e07858d71e) | Feb 03, 2023 |
| Positivo      | Mobile                      | Notebook    | [966b4e2454](https://linux-hardware.org/?probe=966b4e2454) | Feb 02, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [bea57d418a](https://linux-hardware.org/?probe=bea57d418a) | Feb 01, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [23b27dab7d](https://linux-hardware.org/?probe=23b27dab7d) | Feb 01, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [989e45d84b](https://linux-hardware.org/?probe=989e45d84b) | Jan 31, 2023 |
| Dell          | Inspiron 15-3573            | Notebook    | [b735bbde51](https://linux-hardware.org/?probe=b735bbde51) | Jan 29, 2023 |
| ASRock        | H610M-HDV/M.2               | Desktop     | [2936bb8fec](https://linux-hardware.org/?probe=2936bb8fec) | Jan 26, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | Notebook    | [06f87714b0](https://linux-hardware.org/?probe=06f87714b0) | Jan 26, 2023 |
| Lenovo        | NOK                         | Desktop     | [507b602676](https://linux-hardware.org/?probe=507b602676) | Jan 25, 2023 |
| Dell          | 0Y2MRG A00                  | Desktop     | [784e2db087](https://linux-hardware.org/?probe=784e2db087) | Jan 25, 2023 |
| HP            | 8952                        | Mini pc     | [e49754f551](https://linux-hardware.org/?probe=e49754f551) | Jan 23, 2023 |
| HP            | 8881                        | Mini pc     | [d9864f2860](https://linux-hardware.org/?probe=d9864f2860) | Jan 23, 2023 |
| HP            | 8952                        | Mini pc     | [c025c38b83](https://linux-hardware.org/?probe=c025c38b83) | Jan 23, 2023 |
| MSI           | H510M PRO-E                 | Desktop     | [c81f6adb11](https://linux-hardware.org/?probe=c81f6adb11) | Jan 20, 2023 |
| Dell          | Precision M6800             | Notebook    | [bcd98b78c4](https://linux-hardware.org/?probe=bcd98b78c4) | Jan 19, 2023 |
| Dell          | Latitude 5420               | Notebook    | [cb511c0f82](https://linux-hardware.org/?probe=cb511c0f82) | Jan 18, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [ff9464407f](https://linux-hardware.org/?probe=ff9464407f) | Jan 15, 2023 |
| Intel         | NUC10i3FNB M38070-307       | Mini pc     | [4ce3e32165](https://linux-hardware.org/?probe=4ce3e32165) | Jan 12, 2023 |
| Intel         | NUC10i3FNB M38070-307       | Mini pc     | [26089f2f9b](https://linux-hardware.org/?probe=26089f2f9b) | Jan 12, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [71d684a605](https://linux-hardware.org/?probe=71d684a605) | Jan 11, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [d6cac381fd](https://linux-hardware.org/?probe=d6cac381fd) | Jan 09, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [e662d0e58a](https://linux-hardware.org/?probe=e662d0e58a) | Jan 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [49d1097b37](https://linux-hardware.org/?probe=49d1097b37) | Jan 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [2fbec34211](https://linux-hardware.org/?probe=2fbec34211) | Jan 07, 2023 |
| Dell          | XPS 17 9720                 | Notebook    | [ae26f02480](https://linux-hardware.org/?probe=ae26f02480) | Jan 03, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [65c34944ec](https://linux-hardware.org/?probe=65c34944ec) | Jan 03, 2023 |
| HP            | EliteBook 2560p             | Notebook    | [89c0ffe36d](https://linux-hardware.org/?probe=89c0ffe36d) | Dec 29, 2022 |
| Dell          | Inspiron 14 5425            | Notebook    | [42f45d59d2](https://linux-hardware.org/?probe=42f45d59d2) | Dec 29, 2022 |
| Dell          | 0VRWRC A00                  | Desktop     | [2135b5161f](https://linux-hardware.org/?probe=2135b5161f) | Dec 28, 2022 |
| HP            | 805D                        | Desktop     | [cf88e571df](https://linux-hardware.org/?probe=cf88e571df) | Dec 28, 2022 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [2a7ce79df8](https://linux-hardware.org/?probe=2a7ce79df8) | Dec 24, 2022 |
| ASUSTek       | X99-WS/IPMI                 | Desktop     | [41f02987e9](https://linux-hardware.org/?probe=41f02987e9) | Dec 16, 2022 |
| HP            | ProBook 640 G3              | Notebook    | [03eba7b664](https://linux-hardware.org/?probe=03eba7b664) | Dec 15, 2022 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | Notebook    | [ede2606ad1](https://linux-hardware.org/?probe=ede2606ad1) | Dec 15, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [b52b8b590b](https://linux-hardware.org/?probe=b52b8b590b) | Nov 30, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [dc35eb3d09](https://linux-hardware.org/?probe=dc35eb3d09) | Nov 30, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [db276a4d2e](https://linux-hardware.org/?probe=db276a4d2e) | Nov 28, 2022 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [86159f4ef3](https://linux-hardware.org/?probe=86159f4ef3) | Nov 20, 2022 |
| Intel         | D33217GKE G69901-202        | Desktop     | [f10d00e42a](https://linux-hardware.org/?probe=f10d00e42a) | Nov 12, 2022 |
| HP            | 8054                        | Desktop     | [08a9a98d04](https://linux-hardware.org/?probe=08a9a98d04) | Nov 10, 2022 |
| HP            | 8054                        | Desktop     | [4ce3ccc26d](https://linux-hardware.org/?probe=4ce3ccc26d) | Nov 09, 2022 |
| MSI           | X299 RAIDER                 | Desktop     | [b7d117fc31](https://linux-hardware.org/?probe=b7d117fc31) | Nov 09, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | Notebook    | [4c47d0ef97](https://linux-hardware.org/?probe=4c47d0ef97) | Nov 05, 2022 |
| HP            | ProLiant DL380 G7           | Server      | [6d994999c9](https://linux-hardware.org/?probe=6d994999c9) | Nov 01, 2022 |
| ASUSTek       | Crosshair V Formula         | Desktop     | [c07ddbeb76](https://linux-hardware.org/?probe=c07ddbeb76) | Oct 31, 2022 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [23be2713d2](https://linux-hardware.org/?probe=23be2713d2) | Oct 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [cda3087aaf](https://linux-hardware.org/?probe=cda3087aaf) | Oct 23, 2022 |
| BESSTAR Te... | HM90                        | Desktop     | [fd411132f6](https://linux-hardware.org/?probe=fd411132f6) | Oct 15, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [71970edbae](https://linux-hardware.org/?probe=71970edbae) | Oct 11, 2022 |
| HP            | Pavilion g6                 | Notebook    | [11d25577b3](https://linux-hardware.org/?probe=11d25577b3) | Oct 08, 2022 |
| ASUSTek       | PRIME H570-PLUS             | Desktop     | [71da92bd30](https://linux-hardware.org/?probe=71da92bd30) | Oct 04, 2022 |
| AZW           | GTR V01                     | Mini pc     | [40c181376b](https://linux-hardware.org/?probe=40c181376b) | Oct 01, 2022 |
| AZW           | GTR V01                     | Mini pc     | [4638cc7f7b](https://linux-hardware.org/?probe=4638cc7f7b) | Oct 01, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [ff511df5c2](https://linux-hardware.org/?probe=ff511df5c2) | Sep 27, 2022 |
| BANGHO        | BES G1529                   | Notebook    | [ce0db88361](https://linux-hardware.org/?probe=ce0db88361) | Sep 20, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [a191bd2a9f](https://linux-hardware.org/?probe=a191bd2a9f) | Sep 18, 2022 |
| Dell          | Latitude 5430               | Notebook    | [617563f7a7](https://linux-hardware.org/?probe=617563f7a7) | Sep 14, 2022 |
| HP            | ZBook 15u G6                | Notebook    | [af658eb920](https://linux-hardware.org/?probe=af658eb920) | Sep 06, 2022 |
| ASUSTek       | P8B WS                      | Desktop     | [bd82f7708c](https://linux-hardware.org/?probe=bd82f7708c) | Sep 02, 2022 |
| Lenovo        | 1046 NO DPK                 | Desktop     | [e21e07827d](https://linux-hardware.org/?probe=e21e07827d) | Aug 26, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [79c81eef28](https://linux-hardware.org/?probe=79c81eef28) | Aug 23, 2022 |
| ASUSTek       | PRIME B460M-A R2.0          | Desktop     | [e29f13e0b6](https://linux-hardware.org/?probe=e29f13e0b6) | Aug 19, 2022 |
| ASUSTek       | PRIME B365-PLUS             | Desktop     | [324410a493](https://linux-hardware.org/?probe=324410a493) | Aug 04, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [713884d2c8](https://linux-hardware.org/?probe=713884d2c8) | Aug 03, 2022 |
| HP            | ZBook 15 G2                 | Notebook    | [34f32c0d0d](https://linux-hardware.org/?probe=34f32c0d0d) | Jul 27, 2022 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [0d503b2789](https://linux-hardware.org/?probe=0d503b2789) | Jul 27, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [ce5ca74472](https://linux-hardware.org/?probe=ce5ca74472) | Jul 17, 2022 |
| Unknown       | Unknown                     | Tablet      | [bf70ad93f5](https://linux-hardware.org/?probe=bf70ad93f5) | Jul 06, 2022 |
| Unknown       | Unknown                     | Tablet      | [6edba7f033](https://linux-hardware.org/?probe=6edba7f033) | Jul 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 34483... | Notebook    | [fa20ff88e1](https://linux-hardware.org/?probe=fa20ff88e1) | Jun 19, 2022 |
| Dell          | Latitude 3420               | Notebook    | [b10330b427](https://linux-hardware.org/?probe=b10330b427) | Jun 15, 2022 |
| Unknown       | X31_ICH7                    | Desktop     | [f8ab18b666](https://linux-hardware.org/?probe=f8ab18b666) | Jun 07, 2022 |
| Dell          | 0GWHMW A01                  | Desktop     | [f427859019](https://linux-hardware.org/?probe=f427859019) | May 30, 2022 |
| Dell          | 072T6D A01                  | Server      | [4b88759a98](https://linux-hardware.org/?probe=4b88759a98) | May 06, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [b586e45245](https://linux-hardware.org/?probe=b586e45245) | Apr 25, 2022 |
| Dell          | 06CV2N A00                  | Desktop     | [f9e949ad9b](https://linux-hardware.org/?probe=f9e949ad9b) | Apr 24, 2022 |
| Gigabyte      | G41MT-USB3                  | Desktop     | [10f3a0eaae](https://linux-hardware.org/?probe=10f3a0eaae) | Apr 21, 2022 |
| Gigabyte      | G41MT-USB3                  | Desktop     | [4618c00b42](https://linux-hardware.org/?probe=4618c00b42) | Apr 17, 2022 |
| NCR           | Pocono BIOS.5.1             | Desktop     | [ca175e1f0c](https://linux-hardware.org/?probe=ca175e1f0c) | Apr 09, 2022 |
| IBM           | 4367 SVT                    | Server      | [3d7400ea9b](https://linux-hardware.org/?probe=3d7400ea9b) | Mar 11, 2022 |
| Dell          | 0NK70N A03                  | Desktop     | [7d4e906833](https://linux-hardware.org/?probe=7d4e906833) | Mar 11, 2022 |
| Supermicro    | X11SSH-CTF                  | Server      | [7a720a4e41](https://linux-hardware.org/?probe=7a720a4e41) | Mar 10, 2022 |
| Dell          | Latitude 5500               | Notebook    | [3d87bc42c6](https://linux-hardware.org/?probe=3d87bc42c6) | Mar 08, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [f78b6db0bd](https://linux-hardware.org/?probe=f78b6db0bd) | Mar 08, 2022 |
| Dell          | Latitude 5500               | Notebook    | [fc0c5280d7](https://linux-hardware.org/?probe=fc0c5280d7) | Mar 08, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [351e05ccc8](https://linux-hardware.org/?probe=351e05ccc8) | Mar 08, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [dc09f11788](https://linux-hardware.org/?probe=dc09f11788) | Mar 08, 2022 |
| Dell          | 0WN7Y6 A01                  | Desktop     | [ef36ccb6ab](https://linux-hardware.org/?probe=ef36ccb6ab) | Feb 22, 2022 |
| Dell          | 0PC5F7 A02                  | Desktop     | [7c6c7dcd5e](https://linux-hardware.org/?probe=7c6c7dcd5e) | Feb 18, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [1d3c449e8a](https://linux-hardware.org/?probe=1d3c449e8a) | Feb 18, 2022 |
| Supermicro    | X11SPW-TF                   | Server      | [a76bb2e30d](https://linux-hardware.org/?probe=a76bb2e30d) | Feb 07, 2022 |
| Dell          | 0XDN97 A02                  | Server      | [02e5c56a80](https://linux-hardware.org/?probe=02e5c56a80) | Feb 03, 2022 |
| Dell          | 0XDN97 A02                  | Server      | [4aa06b4edd](https://linux-hardware.org/?probe=4aa06b4edd) | Feb 03, 2022 |
| Lenovo        | Legion Y7000 2020H 81Y7     | Notebook    | [2ab4cacc1e](https://linux-hardware.org/?probe=2ab4cacc1e) | Jan 26, 2022 |
| Lenovo        | Legion Y7000 2020H 81Y7     | Notebook    | [787aec5f1c](https://linux-hardware.org/?probe=787aec5f1c) | Jan 26, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [1ab47f8ff0](https://linux-hardware.org/?probe=1ab47f8ff0) | Jan 20, 2022 |
| MSI           | Z97A GAMING 6               | Desktop     | [4b935d705c](https://linux-hardware.org/?probe=4b935d705c) | Jan 20, 2022 |
| Dell          | 0X3D66 A07                  | Server      | [d5c4ef93c4](https://linux-hardware.org/?probe=d5c4ef93c4) | Jan 18, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [7225108b91](https://linux-hardware.org/?probe=7225108b91) | Jan 10, 2022 |
| HP            | ZBook 15 G3                 | Notebook    | [89809f906e](https://linux-hardware.org/?probe=89809f906e) | Jan 10, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [90821cb3a5](https://linux-hardware.org/?probe=90821cb3a5) | Jan 03, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [c7f9478d55](https://linux-hardware.org/?probe=c7f9478d55) | Jan 03, 2022 |
| AZW           | Gemini M                    | Desktop     | [25e63b737c](https://linux-hardware.org/?probe=25e63b737c) | Dec 31, 2021 |
| AZW           | Gemini M                    | Desktop     | [05ef59842c](https://linux-hardware.org/?probe=05ef59842c) | Dec 31, 2021 |
| Google        | Tricky                      | Desktop     | [92e2626936](https://linux-hardware.org/?probe=92e2626936) | Nov 30, 2021 |
| Lenovo        | IdeaPad 500S-14ISK 80Q3     | Notebook    | [6ea0cdba08](https://linux-hardware.org/?probe=6ea0cdba08) | Nov 27, 2021 |
| Lenovo        | ThinkPad W540 20BGCTO1WW    | Notebook    | [25055cdc26](https://linux-hardware.org/?probe=25055cdc26) | Nov 23, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [840d920fb2](https://linux-hardware.org/?probe=840d920fb2) | Nov 22, 2021 |
| Gigabyte      | H87-D3H-CF                  | Desktop     | [72fdde33b3](https://linux-hardware.org/?probe=72fdde33b3) | Nov 19, 2021 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [61fe4e654d](https://linux-hardware.org/?probe=61fe4e654d) | Nov 09, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [9d7947a5a8](https://linux-hardware.org/?probe=9d7947a5a8) | Nov 06, 2021 |
| Toshiba       | TECRA W50-A                 | Notebook    | [abee9f36ad](https://linux-hardware.org/?probe=abee9f36ad) | Nov 05, 2021 |
| Dell          | 0N4YC8 A00                  | Desktop     | [1a94195ddb](https://linux-hardware.org/?probe=1a94195ddb) | Oct 15, 2021 |
| Intel         | S2600WFT H48104-850         | Server      | [36c4acac2d](https://linux-hardware.org/?probe=36c4acac2d) | Sep 14, 2021 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [cb9f02b3de](https://linux-hardware.org/?probe=cb9f02b3de) | Sep 07, 2021 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [f80365b98a](https://linux-hardware.org/?probe=f80365b98a) | Sep 07, 2021 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [243dba3b27](https://linux-hardware.org/?probe=243dba3b27) | Sep 02, 2021 |
| Lenovo        | ThinkPad T420 42365H1       | Notebook    | [3430adab89](https://linux-hardware.org/?probe=3430adab89) | Aug 25, 2021 |
| Lenovo        | NOK                         | Desktop     | [274005087d](https://linux-hardware.org/?probe=274005087d) | Aug 23, 2021 |
| Lenovo        | ThinkPad T420 42365H1       | Notebook    | [6a306e2253](https://linux-hardware.org/?probe=6a306e2253) | Aug 16, 2021 |
| Dell          | 0M5DCD A00                  | Desktop     | [91acc7eb93](https://linux-hardware.org/?probe=91acc7eb93) | Aug 15, 2021 |
| Lenovo        | ThinkPad W500 406132G       | Notebook    | [e79080e90d](https://linux-hardware.org/?probe=e79080e90d) | Aug 08, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [860ec3c89d](https://linux-hardware.org/?probe=860ec3c89d) | Aug 08, 2021 |
| Lenovo        | IdeaPad Y410P 20216         | Notebook    | [b2df1c0e6d](https://linux-hardware.org/?probe=b2df1c0e6d) | Aug 08, 2021 |
| Lenovo        | IdeaPad Y410P 20216         | Notebook    | [3fc207c5b9](https://linux-hardware.org/?probe=3fc207c5b9) | Aug 07, 2021 |
| ASUSTek       | PRIME TRX40-PRO S           | Desktop     | [59f7d599dd](https://linux-hardware.org/?probe=59f7d599dd) | Aug 04, 2021 |
| Dell          | 0M5DCD A00                  | Desktop     | [77c3d7076e](https://linux-hardware.org/?probe=77c3d7076e) | Aug 04, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [09738de946](https://linux-hardware.org/?probe=09738de946) | Jul 04, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [741cab87e1](https://linux-hardware.org/?probe=741cab87e1) | Jun 29, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [60fe7f2653](https://linux-hardware.org/?probe=60fe7f2653) | Jun 13, 2021 |
| Toshiba       | Satellite E45-B             | Notebook    | [84683df1f0](https://linux-hardware.org/?probe=84683df1f0) | Jun 12, 2021 |
| HP            | 0B54h D                     | Desktop     | [ee9a2da17c](https://linux-hardware.org/?probe=ee9a2da17c) | May 19, 2021 |
| Acer          | Aspire VN7-591G             | Notebook    | [bc9e6c4910](https://linux-hardware.org/?probe=bc9e6c4910) | May 10, 2021 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| Rocky Linux 9.1 | 42        | 25.15%  |
| Rocky Linux 8.5 | 31        | 18.56%  |
| Rocky Linux 9.2 | 21        | 12.57%  |
| Rocky Linux 9.0 | 19        | 11.38%  |
| Rocky Linux 8.4 | 19        | 11.38%  |
| Rocky Linux 8.7 | 13        | 7.78%   |
| Rocky Linux 8.6 | 11        | 6.59%   |
| Rocky Linux 8.8 | 9         | 5.39%   |
| Rocky Linux 8.3 | 2         | 1.2%    |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Rocky Linux | 165       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                          | Computers | Percent |
|----------------------------------|-----------|---------|
| 5.14.0-162.6.1.el9_1.0.1.x86_64  | 17        | 9.88%   |
| 4.18.0-348.12.2.el8_5.x86_64     | 13        | 7.56%   |
| 5.14.0-284.25.1.el9_2.x86_64     | 8         | 4.65%   |
| 4.18.0-348.7.1.el8_5.x86_64      | 8         | 4.65%   |
| 5.14.0-284.18.1.el9_2.x86_64     | 7         | 4.07%   |
| 5.14.0-162.18.1.el9_1.x86_64     | 7         | 4.07%   |
| 5.14.0-70.26.1.el9_0.x86_64      | 6         | 3.49%   |
| 4.18.0-305.10.2.el8_4.x86_64     | 6         | 3.49%   |
| 5.14.0-70.22.1.el9_0.x86_64      | 5         | 2.91%   |
| 5.14.0-162.23.1.el9_1.x86_64     | 5         | 2.91%   |
| 5.14.0-162.12.1.el9_1.0.2.x86_64 | 5         | 2.91%   |
| 5.14.0-70.30.1.el9_0.x86_64      | 4         | 2.33%   |
| 5.14.0-70.17.1.el9_0.x86_64      | 4         | 2.33%   |
| 5.14.0-284.11.1.el9_2.x86_64     | 4         | 2.33%   |
| 5.14.0-162.6.1.el9_1.x86_64      | 4         | 2.33%   |
| 4.18.0-348.20.1.el8_5.x86_64     | 4         | 2.33%   |
| 4.18.0-477.21.1.el8_8.x86_64     | 3         | 1.74%   |
| 4.18.0-425.3.1.el8.x86_64        | 3         | 1.74%   |
| 4.18.0-425.19.2.el8_7.x86_64     | 3         | 1.74%   |
| 4.18.0-425.13.1.el8_7.x86_64     | 3         | 1.74%   |
| 4.18.0-425.10.1.el8_7.x86_64     | 3         | 1.74%   |
| 4.18.0-372.32.1.el8_6.x86_64     | 3         | 1.74%   |
| 4.18.0-305.25.1.el8_4.x86_64     | 3         | 1.74%   |
| 5.14.0-284.30.1.el9_2.x86_64     | 2         | 1.16%   |
| 5.14.0-162.12.1.el9_1.0.1.x86_64 | 2         | 1.16%   |
| 4.18.0-477.15.1.el8_8.x86_64     | 2         | 1.16%   |
| 4.18.0-477.13.1.el8_8.x86_64     | 2         | 1.16%   |
| 4.18.0-372.9.1.el8.x86_64        | 2         | 1.16%   |
| 4.18.0-372.26.1.el8_6.x86_64     | 2         | 1.16%   |
| 4.18.0-372.19.1.el8_6.x86_64     | 2         | 1.16%   |
| 4.18.0-372.16.1.el8_6.0.1.x86_64 | 2         | 1.16%   |
| 4.18.0-348.2.1.el8_5.x86_64      | 2         | 1.16%   |
| 4.18.0-305.el8.x86_64            | 2         | 1.16%   |
| 4.18.0-305.3.1.el8_4.x86_64      | 2         | 1.16%   |
| 4.18.0-305.19.1.el8_4.x86_64     | 2         | 1.16%   |
| 4.18.0-305.12.1.el8_4.x86_64     | 2         | 1.16%   |
| 4.18.0-240.22.1.el8.x86_64       | 2         | 1.16%   |
| 6.4.12-1.el8.elrepo.x86_64       | 1         | 0.58%   |
| 6.2.12-1.el9.elrepo.x86_64       | 1         | 0.58%   |
| 6.2.10-1.el8.elrepo.x86_64       | 1         | 0.58%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14.0  | 78        | 46.99%  |
| 4.18.0  | 76        | 45.78%  |
| 6.0.10  | 2         | 1.2%    |
| 6.4.12  | 1         | 0.6%    |
| 6.2.12  | 1         | 0.6%    |
| 6.2.10  | 1         | 0.6%    |
| 6.1.8   | 1         | 0.6%    |
| 6.1.6   | 1         | 0.6%    |
| 5.4.157 | 1         | 0.6%    |
| 5.16.15 | 1         | 0.6%    |
| 5.14.1  | 1         | 0.6%    |
| 5.10.89 | 1         | 0.6%    |
| 5.10.52 | 1         | 0.6%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14    | 79        | 47.59%  |
| 4.18    | 76        | 45.78%  |
| 6.2     | 2         | 1.2%    |
| 6.1     | 2         | 1.2%    |
| 6.0     | 2         | 1.2%    |
| 5.10    | 2         | 1.2%    |
| 6.4     | 1         | 0.6%    |
| 5.4     | 1         | 0.6%    |
| 5.16    | 1         | 0.6%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 164       | 99.39%  |
| aarch64 | 1         | 0.61%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 110       | 66.67%  |
| Unknown       | 21        | 12.73%  |
| KDE5          | 13        | 7.88%   |
| MATE          | 9         | 5.45%   |
| GNOME Classic | 5         | 3.03%   |
| XFCE          | 4         | 2.42%   |
| X-Cinnamon    | 3         | 1.82%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 87        | 51.79%  |
| X11     | 60        | 35.71%  |
| Unknown | 10        | 5.95%   |
| Tty     | 8         | 4.76%   |
| Web     | 3         | 1.79%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 74        | 44.85%  |
| GDM     | 72        | 43.64%  |
| SDDM    | 10        | 6.06%   |
| LightDM | 9         | 5.45%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 105       | 63.64%  |
| en_CA   | 7         | 4.24%   |
| ru_RU   | 6         | 3.64%   |
| en_AU   | 5         | 3.03%   |
| C       | 4         | 2.42%   |
| Unknown | 4         | 2.42%   |
| en_ZA   | 3         | 1.82%   |
| en_SG   | 3         | 1.82%   |
| en_IL   | 3         | 1.82%   |
| en_GB   | 3         | 1.82%   |
| de_DE   | 3         | 1.82%   |
| pt_BR   | 2         | 1.21%   |
| es_ES   | 2         | 1.21%   |
| en_IE   | 2         | 1.21%   |
| de_AT   | 2         | 1.21%   |
| zh_TW   | 1         | 0.61%   |
| pl_PL   | 1         | 0.61%   |
| ko_KR   | 1         | 0.61%   |
| ja_JP   | 1         | 0.61%   |
| it_IT   | 1         | 0.61%   |
| hu_HU   | 1         | 0.61%   |
| fr_FR   | 1         | 0.61%   |
| es_CO   | 1         | 0.61%   |
| es_AR   | 1         | 0.61%   |
| en_IN   | 1         | 0.61%   |
| af_ZA   | 1         | 0.61%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 113       | 68.07%  |
| BIOS | 53        | 31.93%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Xfs  | 138       | 83.64%  |
| Ext4 | 26        | 15.76%  |
| Ext3 | 1         | 0.61%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 89        | 53.94%  |
| Unknown | 53        | 32.12%  |
| MBR     | 23        | 13.94%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 134       | 81.21%  |
| Yes       | 31        | 18.79%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 138       | 83.64%  |
| Yes       | 27        | 16.36%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Lenovo                               | 31        | 18.79%  |
| Dell                                 | 31        | 18.79%  |
| Hewlett-Packard                      | 24        | 14.55%  |
| ASUSTek Computer                     | 24        | 14.55%  |
| Gigabyte Technology                  | 9         | 5.45%   |
| MSI                                  | 8         | 4.85%   |
| Intel                                | 4         | 2.42%   |
| AZW                                  | 4         | 2.42%   |
| ASRock                               | 4         | 2.42%   |
| Supermicro                           | 3         | 1.82%   |
| Unknown                              | 3         | 1.82%   |
| Toshiba                              | 2         | 1.21%   |
| Acer                                 | 2         | 1.21%   |
| Techvision                           | 1         | 0.61%   |
| Shenzhen Meigao Electronic Equipment | 1         | 0.61%   |
| Sapphire                             | 1         | 0.61%   |
| Raspberry Pi Foundation              | 1         | 0.61%   |
| Positivo                             | 1         | 0.61%   |
| NCR                                  | 1         | 0.61%   |
| IBM                                  | 1         | 0.61%   |
| HUAWEI                               | 1         | 0.61%   |
| HPE                                  | 1         | 0.61%   |
| Google                               | 1         | 0.61%   |
| Clevo                                | 1         | 0.61%   |
| BESSTAR Tech                         | 1         | 0.61%   |
| Beelink                              | 1         | 0.61%   |
| BANGHO                               | 1         | 0.61%   |
| ATOPNUC                              | 1         | 0.61%   |
| Apple                                | 1         | 0.61%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 3         | 1.82%   |
| Dell PowerEdge R610                        | 2         | 1.21%   |
| Dell OptiPlex 9020                         | 2         | 1.21%   |
| AZW GTR                                    | 2         | 1.21%   |
| Toshiba TECRA W50-A                        | 1         | 0.61%   |
| Toshiba Satellite E45-B                    | 1         | 0.61%   |
| Techvision TVI7309X                        | 1         | 0.61%   |
| Supermicro SYS-6019U-TN4R4T                | 1         | 0.61%   |
| Supermicro SYS-5029P-WTR                   | 1         | 0.61%   |
| Supermicro Super Server                    | 1         | 0.61%   |
| Shenzhen Meigao Electronic Equipment HX90G | 1         | 0.61%   |
| Sapphire PE-AM2RS690V2                     | 1         | 0.61%   |
| RPi Raspberry Pi                           | 1         | 0.61%   |
| Positivo Mobile                            | 1         | 0.61%   |
| NCR xxxx-xxxx-xxxx                         | 1         | 0.61%   |
| MSI MS-7D78                                | 1         | 0.61%   |
| MSI MS-7D46                                | 1         | 0.61%   |
| MSI MS-7D25                                | 1         | 0.61%   |
| MSI MS-7B89                                | 1         | 0.61%   |
| MSI MS-7B78                                | 1         | 0.61%   |
| MSI MS-7A94                                | 1         | 0.61%   |
| MSI MS-7917                                | 1         | 0.61%   |
| MSI H510M PRO-E                            | 1         | 0.61%   |
| Lenovo Yoga 720-13IKB 80X6                 | 1         | 0.61%   |
| Lenovo ThinkStation P620 30E0S0PR00        | 1         | 0.61%   |
| Lenovo ThinkStation P340 30DK000CUS        | 1         | 0.61%   |
| Lenovo ThinkPad X270 20HMS79Q00            | 1         | 0.61%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BTS1V900   | 1         | 0.61%   |
| Lenovo ThinkPad X1 Carbon 344835U          | 1         | 0.61%   |
| Lenovo ThinkPad W540 20BGCTO1WW            | 1         | 0.61%   |
| Lenovo ThinkPad W500 406132G               | 1         | 0.61%   |
| Lenovo ThinkPad T480 20L6S8B500            | 1         | 0.61%   |
| Lenovo ThinkPad T430 2347FF9               | 1         | 0.61%   |
| Lenovo ThinkPad T420 42365H1               | 1         | 0.61%   |
| Lenovo ThinkPad T14s Gen 3 21BR000QUS      | 1         | 0.61%   |
| Lenovo ThinkPad T14s Gen 2a 20XF006XCK     | 1         | 0.61%   |
| Lenovo ThinkPad T14 Gen 3 21AH00HXGE       | 1         | 0.61%   |
| Lenovo ThinkPad P15s Gen 1 20T4CTO1WW      | 1         | 0.61%   |
| Lenovo ThinkPad P1 Gen 4i 20Y3000FHV       | 1         | 0.61%   |
| Lenovo ThinkPad P1 Gen 3 20THCTO1WW        | 1         | 0.61%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Lenovo ThinkPad                            | 16        | 9.7%    |
| ASUS PRIME                                 | 9         | 5.45%   |
| Lenovo IdeaPad                             | 7         | 4.24%   |
| Dell OptiPlex                              | 6         | 3.64%   |
| Dell XPS                                   | 5         | 3.03%   |
| Dell Precision                             | 5         | 3.03%   |
| Dell PowerEdge                             | 5         | 3.03%   |
| HP ZBook                                   | 4         | 2.42%   |
| HP Laptop                                  | 4         | 2.42%   |
| HP EliteBook                               | 4         | 2.42%   |
| Dell Latitude                              | 4         | 2.42%   |
| Dell Vostro                                | 3         | 1.82%   |
| Dell Inspiron                              | 3         | 1.82%   |
| ASUS ASUS                                  | 3         | 1.82%   |
| Unknown                                    | 3         | 1.82%   |
| Lenovo ThinkStation                        | 2         | 1.21%   |
| Lenovo Legion                              | 2         | 1.21%   |
| Lenovo IdeaPadFlex                         | 2         | 1.21%   |
| HP ProLiant                                | 2         | 1.21%   |
| HP ProBook                                 | 2         | 1.21%   |
| HP EliteDesk                               | 2         | 1.21%   |
| AZW GTR                                    | 2         | 1.21%   |
| ASUS ROG                                   | 2         | 1.21%   |
| Acer Aspire                                | 2         | 1.21%   |
| Toshiba TECRA                              | 1         | 0.61%   |
| Toshiba Satellite                          | 1         | 0.61%   |
| Techvision TVI7309X                        | 1         | 0.61%   |
| Supermicro SYS-6019U-TN4R4T                | 1         | 0.61%   |
| Supermicro SYS-5029P-WTR                   | 1         | 0.61%   |
| Supermicro Super                           | 1         | 0.61%   |
| Shenzhen Meigao Electronic Equipment HX90G | 1         | 0.61%   |
| Sapphire PE-AM2RS690V2                     | 1         | 0.61%   |
| RPi Raspberry                              | 1         | 0.61%   |
| Positivo Mobile                            | 1         | 0.61%   |
| NCR xxxx-xxxx-xxxx                         | 1         | 0.61%   |
| MSI MS-7D78                                | 1         | 0.61%   |
| MSI MS-7D46                                | 1         | 0.61%   |
| MSI MS-7D25                                | 1         | 0.61%   |
| MSI MS-7B89                                | 1         | 0.61%   |
| MSI MS-7B78                                | 1         | 0.61%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 23        | 13.94%  |
| 2022    | 21        | 12.73%  |
| 2020    | 19        | 11.52%  |
| 2018    | 17        | 10.3%   |
| 2011    | 13        | 7.88%   |
| 2019    | 12        | 7.27%   |
| 2014    | 10        | 6.06%   |
| 2013    | 10        | 6.06%   |
| 2015    | 9         | 5.45%   |
| 2012    | 9         | 5.45%   |
| 2017    | 7         | 4.24%   |
| 2010    | 5         | 3.03%   |
| 2009    | 3         | 1.82%   |
| 2008    | 3         | 1.82%   |
| 2016    | 2         | 1.21%   |
| 2023    | 1         | 0.61%   |
| Unknown | 1         | 0.61%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 71        | 43.03%  |
| Notebook       | 69        | 41.82%  |
| Server         | 13        | 7.88%   |
| Mini pc        | 6         | 3.64%   |
| Convertible    | 4         | 2.42%   |
| System on chip | 1         | 0.61%   |
| Tablet         | 1         | 0.61%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 143       | 86.67%  |
| Enabled  | 22        | 13.33%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 164       | 99.39%  |
| Yes  | 1         | 0.61%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 42        | 25.3%   |
| 4.01-8.0        | 35        | 21.08%  |
| 32.01-64.0      | 30        | 18.07%  |
| 16.01-24.0      | 19        | 11.45%  |
| 64.01-256.0     | 15        | 9.04%   |
| 3.01-4.0        | 9         | 5.42%   |
| 24.01-32.0      | 6         | 3.61%   |
| More than 256.0 | 4         | 2.41%   |
| 1.01-2.0        | 4         | 2.41%   |
| 2.01-3.0        | 2         | 1.2%    |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 44        | 25.58%  |
| 2.01-3.0   | 41        | 23.84%  |
| 3.01-4.0   | 33        | 19.19%  |
| 1.01-2.0   | 25        | 14.53%  |
| 8.01-16.0  | 11        | 6.4%    |
| 0.51-1.0   | 8         | 4.65%   |
| 16.01-24.0 | 4         | 2.33%   |
| 32.01-64.0 | 2         | 1.16%   |
| 24.01-32.0 | 2         | 1.16%   |
| 0.01-0.5   | 2         | 1.16%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 96        | 57.83%  |
| 2      | 31        | 18.67%  |
| 4      | 13        | 7.83%   |
| 3      | 13        | 7.83%   |
| 6      | 3         | 1.81%   |
| 5      | 3         | 1.81%   |
| 19     | 1         | 0.6%    |
| 18     | 1         | 0.6%    |
| 17     | 1         | 0.6%    |
| 16     | 1         | 0.6%    |
| 14     | 1         | 0.6%    |
| 9      | 1         | 0.6%    |
| 8      | 1         | 0.6%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 121       | 73.33%  |
| Yes       | 44        | 26.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 149       | 89.76%  |
| No        | 17        | 10.24%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 102       | 61.45%  |
| No        | 64        | 38.55%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 90        | 54.22%  |
| No        | 76        | 45.78%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 49        | 29.7%   |
| Canada       | 10        | 6.06%   |
| Germany      | 9         | 5.45%   |
| Russia       | 8         | 4.85%   |
| Australia    | 6         | 3.64%   |
| Italy        | 5         | 3.03%   |
| UK           | 4         | 2.42%   |
| South Africa | 4         | 2.42%   |
| Singapore    | 4         | 2.42%   |
| Poland       | 4         | 2.42%   |
| Netherlands  | 4         | 2.42%   |
| Czechia      | 4         | 2.42%   |
| Spain        | 3         | 1.82%   |
| Mexico       | 3         | 1.82%   |
| Israel       | 3         | 1.82%   |
| India        | 3         | 1.82%   |
| Hungary      | 3         | 1.82%   |
| France       | 3         | 1.82%   |
| Brazil       | 3         | 1.82%   |
| Sweden       | 2         | 1.21%   |
| South Korea  | 2         | 1.21%   |
| Norway       | 2         | 1.21%   |
| Ireland      | 2         | 1.21%   |
| Indonesia    | 2         | 1.21%   |
| Belgium      | 2         | 1.21%   |
| Austria      | 2         | 1.21%   |
| Argentina    | 2         | 1.21%   |
| Uzbekistan   | 1         | 0.61%   |
| UAE          | 1         | 0.61%   |
| Turkey       | 1         | 0.61%   |
| Taiwan       | 1         | 0.61%   |
| Switzerland  | 1         | 0.61%   |
| Slovakia     | 1         | 0.61%   |
| Saudi Arabia | 1         | 0.61%   |
| Portugal     | 1         | 0.61%   |
| Pakistan     | 1         | 0.61%   |
| Malaysia     | 1         | 0.61%   |
| Kazakhstan   | 1         | 0.61%   |
| Japan        | 1         | 0.61%   |
| Finland      | 1         | 0.61%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Singapore     | 4         | 2.41%   |
| Melbourne     | 4         | 2.41%   |
| Toronto       | 3         | 1.81%   |
| Budapest      | 3         | 1.81%   |
| Vienna        | 2         | 1.2%    |
| Prague        | 2         | 1.2%    |
| Philadelphia  | 2         | 1.2%    |
| Oslo          | 2         | 1.2%    |
| Moscow        | 2         | 1.2%    |
| Krakow        | 2         | 1.2%    |
| Haifa         | 2         | 1.2%    |
| Enschede      | 2         | 1.2%    |
| Chicago       | 2         | 1.2%    |
| Centurion     | 2         | 1.2%    |
| Buckley       | 2         | 1.2%    |
| Berlin        | 2         | 1.2%    |
| Adelaide      | 2         | 1.2%    |
| Žilina       | 1         | 0.6%    |
| Yogyakarta    | 1         | 0.6%    |
| Yekaterinburg | 1         | 0.6%    |
| Xi'an         | 1         | 0.6%    |
| Woking        | 1         | 0.6%    |
| Willowbrook   | 1         | 0.6%    |
| Westerville   | 1         | 0.6%    |
| Wells         | 1         | 0.6%    |
| Washington    | 1         | 0.6%    |
| Waltham       | 1         | 0.6%    |
| Wake Forest   | 1         | 0.6%    |
| Voronezh      | 1         | 0.6%    |
| Vancouver     | 1         | 0.6%    |
| Urbana        | 1         | 0.6%    |
| Troisdorf     | 1         | 0.6%    |
| Torrington    | 1         | 0.6%    |
| Tlaxcala City | 1         | 0.6%    |
| Thoothukudi   | 1         | 0.6%    |
| Taoyuan City  | 1         | 0.6%    |
| Syracuse      | 1         | 0.6%    |
| St. John's    | 1         | 0.6%    |
| St Petersburg | 1         | 0.6%    |
| Spokane       | 1         | 0.6%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 46        | 64     | 18.55%  |
| Seagate                     | 35        | 97     | 14.11%  |
| WDC                         | 30        | 57     | 12.1%   |
| Toshiba                     | 14        | 17     | 5.65%   |
| Sandisk                     | 14        | 16     | 5.65%   |
| Intel                       | 11        | 13     | 4.44%   |
| Kingston                    | 10        | 10     | 4.03%   |
| Hitachi                     | 9         | 14     | 3.63%   |
| Crucial                     | 8         | 9      | 3.23%   |
| Unknown                     | 6         | 6      | 2.42%   |
| SK hynix                    | 6         | 8      | 2.42%   |
| Micron Technology           | 4         | 4      | 1.61%   |
| Phison                      | 3         | 4      | 1.21%   |
| HGST                        | 3         | 3      | 1.21%   |
| A-DATA Technology           | 3         | 3      | 1.21%   |
| PNY                         | 2         | 2      | 0.81%   |
| Phison Electronics          | 2         | 17     | 0.81%   |
| MAXIO Technology (Hangzhou) | 2         | 3      | 0.81%   |
| LITEONIT                    | 2         | 2      | 0.81%   |
| Lexar                       | 2         | 2      | 0.81%   |
| KIOXIA                      | 2         | 2      | 0.81%   |
| Gigabyte Technology         | 2         | 2      | 0.81%   |
| Dogfish                     | 2         | 2      | 0.81%   |
| Corsair                     | 2         | 2      | 0.81%   |
| China                       | 2         | 2      | 0.81%   |
| Union Memory (Shenzhen)     | 1         | 1      | 0.4%    |
| UMIS                        | 1         | 1      | 0.4%    |
| Team                        | 1         | 1      | 0.4%    |
| StoreJet                    | 1         | 1      | 0.4%    |
| SATADOM-SL                  | 1         | 1      | 0.4%    |
| SABRENT                     | 1         | 1      | 0.4%    |
| MyDigitalSSD                | 1         | 1      | 0.4%    |
| Micron/Crucial Technology   | 1         | 1      | 0.4%    |
| LITEON                      | 1         | 1      | 0.4%    |
| KIOXIA-EXCERIA              | 1         | 1      | 0.4%    |
| Kingston Technology Company | 1         | 1      | 0.4%    |
| KingFast                    | 1         | 1      | 0.4%    |
| JMicron Technology          | 1         | 1      | 0.4%    |
| INDMEM                      | 1         | 1      | 0.4%    |
| IBM                         | 1         | 1      | 0.4%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST500DM002-1BD142 500GB                     | 4         | 1.41%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 4         | 1.41%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB    | 3         | 1.06%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 3         | 1.06%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 500GB | 3         | 1.06%   |
| WDC WD5000AAKX-75U6AA0 500GB                        | 2         | 0.71%   |
| WDC WD2002FAEX-007BA0 2TB                           | 2         | 0.71%   |
| WDC WD Blue SA510 M.2 2280 1000GB SSD               | 2         | 0.71%   |
| Unknown MMC Card  64GB                              | 2         | 0.71%   |
| Seagate ST9320325AS 320GB                           | 2         | 0.71%   |
| Seagate ST4000DM004-2CV104 4TB                      | 2         | 0.71%   |
| Seagate ST300MP0005 304GB                           | 2         | 0.71%   |
| Seagate ST2000DM008-2FR102 2TB                      | 2         | 0.71%   |
| Seagate ST1000DM010-2EP102 1TB                      | 2         | 0.71%   |
| Samsung SSD 870 EVO 1TB                             | 2         | 0.71%   |
| Samsung SSD 860 EVO 1TB                             | 2         | 0.71%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 512GB  | 2         | 0.71%   |
| Lexar 512GB SSD                                     | 2         | 0.71%   |
| Intel SSD 660P Series 1024GB                        | 2         | 0.71%   |
| Gigabyte GP-GSTFS31240GNTD 240GB                    | 2         | 0.71%   |
| Crucial CT240BX500SSD1 240GB                        | 2         | 0.71%   |
| Crucial CT1000MX500SSD1 1TB                         | 2         | 0.71%   |
| A-DATA SWORDFISH 1TB                                | 2         | 0.71%   |
| WDC WDS500G1R0A-68A4W0 500GB SSD                    | 1         | 0.35%   |
| WDC WDS480G2G0A-00JH30 480GB SSD                    | 1         | 0.35%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD                    | 1         | 0.35%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 1         | 0.35%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 1         | 0.35%   |
| WDC WDS100T1X0E-00AFY0 1TB                          | 1         | 0.35%   |
| WDC WDS100T1R0A-68A4W0 1TB SSD                      | 1         | 0.35%   |
| WDC WDBNCE0010PNC 1TB SSD                           | 1         | 0.35%   |
| WDC WD80EZZX-11CSGA0 8TB                            | 1         | 0.35%   |
| WDC WD80EMAZ-00WJTA0 8TB                            | 1         | 0.35%   |
| WDC WD80EDAZ-11TA3A0 8TB                            | 1         | 0.35%   |
| WDC WD60EFAX-68JH4N1 6TB                            | 1         | 0.35%   |
| WDC WD5003ABYX-18WERA0 500GB                        | 1         | 0.35%   |
| WDC WD5000LPCX-24VHAT0 500GB                        | 1         | 0.35%   |
| WDC WD5000LPCX-24C6HT0 500GB                        | 1         | 0.35%   |
| WDC WD5000BPVT-00A1YT0 500GB                        | 1         | 0.35%   |
| WDC WD5000AUDX-63WNHY0 500GB                        | 1         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 35        | 97     | 41.67%  |
| WDC                 | 22        | 43     | 26.19%  |
| Hitachi             | 9         | 14     | 10.71%  |
| Toshiba             | 7         | 9      | 8.33%   |
| Samsung Electronics | 3         | 4      | 3.57%   |
| Unknown             | 2         | 2      | 2.38%   |
| HGST                | 2         | 2      | 2.38%   |
| StoreJet            | 1         | 1      | 1.19%   |
| SABRENT             | 1         | 1      | 1.19%   |
| IBM                 | 1         | 1      | 1.19%   |
| Fujitsu             | 1         | 1      | 1.19%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 19        | 24     | 23.17%  |
| WDC                 | 8         | 11     | 9.76%   |
| SanDisk             | 8         | 9      | 9.76%   |
| Crucial             | 7         | 8      | 8.54%   |
| Toshiba             | 5         | 5      | 6.1%    |
| Kingston            | 5         | 5      | 6.1%    |
| Intel               | 3         | 4      | 3.66%   |
| SK hynix            | 2         | 2      | 2.44%   |
| PNY                 | 2         | 2      | 2.44%   |
| LITEONIT            | 2         | 2      | 2.44%   |
| Gigabyte Technology | 2         | 2      | 2.44%   |
| Dogfish             | 2         | 2      | 2.44%   |
| China               | 2         | 2      | 2.44%   |
| Team                | 1         | 1      | 1.22%   |
| SATADOM-SL          | 1         | 1      | 1.22%   |
| MyDigitalSSD        | 1         | 1      | 1.22%   |
| LITEON              | 1         | 1      | 1.22%   |
| Lexar               | 1         | 1      | 1.22%   |
| KingFast            | 1         | 1      | 1.22%   |
| INDMEM              | 1         | 1      | 1.22%   |
| GOODRAM             | 1         | 1      | 1.22%   |
| DUEX-120GB          | 1         | 1      | 1.22%   |
| Digma               | 1         | 1      | 1.22%   |
| Corsair             | 1         | 1      | 1.22%   |
| ASMT                | 1         | 1      | 1.22%   |
| Apacer              | 1         | 1      | 1.22%   |
| ADATA SU            | 1         | 1      | 1.22%   |
| A-DATA Technology   | 1         | 1      | 1.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 75        | 111    | 34.72%  |
| SSD     | 70        | 93     | 32.41%  |
| HDD     | 63        | 175    | 29.17%  |
| MMC     | 4         | 4      | 1.85%   |
| Unknown | 4         | 4      | 1.85%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 106       | 253    | 53.27%  |
| NVMe | 75        | 111    | 37.69%  |
| SAS  | 14        | 19     | 7.04%   |
| MMC  | 4         | 4      | 2.01%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 69        | 105    | 47.26%  |
| 0.51-1.0   | 41        | 82     | 28.08%  |
| 1.01-2.0   | 20        | 33     | 13.7%   |
| 3.01-4.0   | 9         | 28     | 6.16%   |
| 4.01-10.0  | 3         | 15     | 2.05%   |
| 2.01-3.0   | 2         | 2      | 1.37%   |
| 10.01-20.0 | 2         | 3      | 1.37%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 47        | 28.14%  |
| 251-500        | 35        | 20.96%  |
| 501-1000       | 27        | 16.17%  |
| 1001-2000      | 20        | 11.98%  |
| More than 3000 | 14        | 8.38%   |
| 2001-3000      | 8         | 4.79%   |
| 51-100         | 8         | 4.79%   |
| Unknown        | 5         | 2.99%   |
| 1-20           | 3         | 1.8%    |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 57        | 33.73%  |
| 21-50          | 37        | 21.89%  |
| 51-100         | 20        | 11.83%  |
| 101-250        | 15        | 8.88%   |
| 501-1000       | 12        | 7.1%    |
| 251-500        | 8         | 4.73%   |
| More than 3000 | 7         | 4.14%   |
| 1001-2000      | 5         | 2.96%   |
| Unknown        | 5         | 2.96%   |
| 2001-3000      | 3         | 1.78%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD5000AAKX-75U6AA0 500GB          | 1         | 1      | 5.56%   |
| WDC WD40EZRZ-00WN9B0 4TB              | 1         | 1      | 5.56%   |
| WDC WD40 EFRX-68N32N0 4TB             | 1         | 1      | 5.56%   |
| WDC WD1001FALS-00J7B1 1TB             | 1         | 2      | 5.56%   |
| WDC WD1001FALS-00J7B0 1TB             | 1         | 4      | 5.56%   |
| Toshiba MK1059GSM 1TB                 | 1         | 1      | 5.56%   |
| Seagate ST9500325AS 500GB             | 1         | 1      | 5.56%   |
| Seagate ST9320325AS 320GB             | 1         | 1      | 5.56%   |
| Seagate ST8000AS0002-1NA17Z 8TB       | 1         | 1      | 5.56%   |
| Seagate ST4000NM0033-9ZM170 4TB       | 1         | 10     | 5.56%   |
| Seagate ST31000528AS 1TB              | 1         | 2      | 5.56%   |
| Seagate ST2000DM008-2FR102 2TB        | 1         | 2      | 5.56%   |
| IBM ST3500641NS 39M4517 39M0181 500GB | 1         | 1      | 5.56%   |
| Hitachi HTS727575A9E364 752GB         | 1         | 1      | 5.56%   |
| Hitachi HDS725050KLA360 500GB         | 1         | 1      | 5.56%   |
| Hitachi HDS721010CLA632 1TB           | 1         | 1      | 5.56%   |
| Crucial CT1050MX300SSD1 1TB           | 1         | 1      | 5.56%   |
| Corsair Neutron SSD 64GB              | 1         | 1      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 17     | 33.33%  |
| WDC     | 5         | 9      | 27.78%  |
| Hitachi | 3         | 3      | 16.67%  |
| Toshiba | 1         | 1      | 5.56%   |
| IBM     | 1         | 1      | 5.56%   |
| Crucial | 1         | 1      | 5.56%   |
| Corsair | 1         | 1      | 5.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 17     | 37.5%   |
| WDC     | 5         | 9      | 31.25%  |
| Hitachi | 3         | 3      | 18.75%  |
| Toshiba | 1         | 1      | 6.25%   |
| IBM     | 1         | 1      | 6.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 14        | 31     | 87.5%   |
| SSD  | 2         | 2      | 12.5%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST9500420AS 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 108       | 255    | 58.06%  |
| Detected | 62        | 98     | 33.33%  |
| Malfunc  | 15        | 33     | 8.06%   |
| Failed   | 1         | 1      | 0.54%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 103       | 45.37%  |
| AMD                          | 34        | 14.98%  |
| Samsung Electronics          | 27        | 11.89%  |
| SanDisk                      | 8         | 3.52%   |
| Phison Electronics           | 6         | 2.64%   |
| LSI Logic / Symbios Logic    | 6         | 2.64%   |
| Kingston Technology Company  | 6         | 2.64%   |
| ASMedia Technology           | 5         | 2.2%    |
| SK hynix                     | 4         | 1.76%   |
| Micron Technology            | 4         | 1.76%   |
| KIOXIA                       | 3         | 1.32%   |
| Broadcom / LSI               | 3         | 1.32%   |
| Toshiba America Info Systems | 2         | 0.88%   |
| Realtek Semiconductor        | 2         | 0.88%   |
| Micron/Crucial Technology    | 2         | 0.88%   |
| MAXIO Technology (Hangzhou)  | 2         | 0.88%   |
| Hewlett-Packard              | 2         | 0.88%   |
| VIA Technologies             | 1         | 0.44%   |
| Union Memory (Shenzhen)      | 1         | 0.44%   |
| Silicon Motion               | 1         | 0.44%   |
| Shenzhen Longsys Electronics | 1         | 0.44%   |
| Marvell Technology Group     | 1         | 0.44%   |
| JMicron Technology           | 1         | 0.44%   |
| ADATA Technology             | 1         | 0.44%   |
| Adaptec                      | 1         | 0.44%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 22        | 8.4%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 11        | 4.2%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 8         | 3.05%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8         | 3.05%   |
| Intel SATA Controller [RAID mode]                                                       | 7         | 2.67%   |
| AMD 400 Series Chipset SATA Controller                                                  | 6         | 2.29%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 5         | 1.91%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 5         | 1.91%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5         | 1.91%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 5         | 1.91%   |
| Samsung NVMe SSD Controller 980                                                         | 4         | 1.53%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4         | 1.53%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4         | 1.53%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 4         | 1.53%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4         | 1.53%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 3         | 1.15%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 3         | 1.15%   |
| Phison PS5013 E13 NVMe Controller                                                       | 3         | 1.15%   |
| Micron 3400 NVMe SSD [Hendrix]                                                          | 3         | 1.15%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 3         | 1.15%   |
| Intel SSD 670p Series [Keystone Harbor]                                                 | 3         | 1.15%   |
| Intel SSD 660P Series                                                                   | 3         | 1.15%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 3         | 1.15%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                           | 3         | 1.15%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                            | 3         | 1.15%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 3         | 1.15%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 3         | 1.15%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3         | 1.15%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3         | 1.15%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3         | 1.15%   |
| AMD 500 Series Chipset SATA Controller                                                  | 3         | 1.15%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 2         | 0.76%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                                       | 2         | 0.76%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 2         | 0.76%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                            | 2         | 0.76%   |
| LSI Logic / Symbios Logic MegaRAID SAS 1078                                             | 2         | 0.76%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                              | 2         | 0.76%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 2         | 0.76%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2         | 0.76%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 2         | 0.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 102       | 44.16%  |
| NVMe | 75        | 32.47%  |
| IDE  | 24        | 10.39%  |
| RAID | 23        | 9.96%   |
| SAS  | 5         | 2.16%   |
| SCSI | 2         | 0.87%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 123       | 74.55%  |
| AMD    | 41        | 24.85%  |
| ARM    | 1         | 0.61%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-2600 CPU @ 3.40GHz            | 4         | 2.42%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 4         | 2.42%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 3         | 1.82%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 3         | 1.82%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 3         | 1.82%   |
| Intel 12th Gen Core i7-1260P                | 3         | 1.82%   |
| Intel Xeon CPU L5530 @ 2.40GHz              | 2         | 1.21%   |
| Intel Xeon CPU E5-2665 0 @ 2.40GHz          | 2         | 1.21%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 2         | 1.21%   |
| Intel Core i7-10610U CPU @ 1.80GHz          | 2         | 1.21%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 1.21%   |
| Intel 12th Gen Core i5-12400F               | 2         | 1.21%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz     | 2         | 1.21%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz      | 2         | 1.21%   |
| AMD Ryzen 9 5900HX with Radeon Graphics     | 2         | 1.21%   |
| AMD FX-8350 Eight-Core Processor            | 2         | 1.21%   |
| Intel Xeon Silver 4216 CPU @ 2.10GHz        | 1         | 0.61%   |
| Intel Xeon Platinum 8124M CPU @ 3.00GHz     | 1         | 0.61%   |
| Intel Xeon Gold 6134 CPU @ 3.20GHz          | 1         | 0.61%   |
| Intel Xeon Gold 6130 CPU @ 2.10GHz          | 1         | 0.61%   |
| Intel Xeon E-2244G CPU @ 3.80GHz            | 1         | 0.61%   |
| Intel Xeon CPU X5680 @ 3.33GHz              | 1         | 0.61%   |
| Intel Xeon CPU X5670 @ 2.93GHz              | 1         | 0.61%   |
| Intel Xeon CPU E5620 @ 2.40GHz              | 1         | 0.61%   |
| Intel Xeon CPU E5-2687W v2 @ 3.40GHz        | 1         | 0.61%   |
| Intel Xeon CPU E5-2680 v4 @ 2.40GHz         | 1         | 0.61%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz         | 1         | 0.61%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz         | 1         | 0.61%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz          | 1         | 0.61%   |
| Intel Xeon CPU E3110 @ 3.00GHz              | 1         | 0.61%   |
| Intel Xeon CPU E3-1245 v5 @ 3.50GHz         | 1         | 0.61%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz         | 1         | 0.61%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 0.61%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1         | 0.61%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 1         | 0.61%   |
| Intel Core i9-7920X CPU @ 2.90GHz           | 1         | 0.61%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 0.61%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 1         | 0.61%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 0.61%   |
| Intel Core i7-6950X CPU @ 3.00GHz           | 1         | 0.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 39        | 23.64%  |
| Other                   | 27        | 16.36%  |
| Intel Core i5           | 22        | 13.33%  |
| Intel Xeon              | 16        | 9.7%    |
| AMD Ryzen 7             | 8         | 4.85%   |
| AMD Ryzen 5             | 7         | 4.24%   |
| Intel Core i3           | 6         | 3.64%   |
| Intel Celeron           | 6         | 3.64%   |
| AMD Ryzen 9             | 6         | 3.64%   |
| AMD FX                  | 3         | 1.82%   |
| Intel Xeon Gold         | 2         | 1.21%   |
| AMD Ryzen Threadripper  | 2         | 1.21%   |
| AMD Ryzen 5 PRO         | 2         | 1.21%   |
| AMD Ryzen 3             | 2         | 1.21%   |
| Intel Xeon Silver       | 1         | 0.61%   |
| Intel Xeon Platinum     | 1         | 0.61%   |
| Intel Pentium Silver    | 1         | 0.61%   |
| Intel Pentium Dual-Core | 1         | 0.61%   |
| Intel Pentium Dual      | 1         | 0.61%   |
| Intel Core i9           | 1         | 0.61%   |
| Intel Core 2 Quad       | 1         | 0.61%   |
| Intel Core 2 Duo        | 1         | 0.61%   |
| Intel Atom              | 1         | 0.61%   |
| AMD Sempron             | 1         | 0.61%   |
| AMD Ryzen Embedded      | 1         | 0.61%   |
| AMD Ryzen 7 PRO         | 1         | 0.61%   |
| AMD Phenom II X6        | 1         | 0.61%   |
| AMD Athlon II X2        | 1         | 0.61%   |
| AMD A8                  | 1         | 0.61%   |
| AMD A4                  | 1         | 0.61%   |
| AMD A10                 | 1         | 0.61%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 63        | 38.18%  |
| 2      | 33        | 20%     |
| 6      | 22        | 13.33%  |
| 8      | 21        | 12.73%  |
| 12     | 8         | 4.85%   |
| 16     | 6         | 3.64%   |
| 10     | 5         | 3.03%   |
| 36     | 1         | 0.61%   |
| 32     | 1         | 0.61%   |
| 28     | 1         | 0.61%   |
| 24     | 1         | 0.61%   |
| 14     | 1         | 0.61%   |
| 3      | 1         | 0.61%   |
| 1      | 1         | 0.61%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 153       | 92.73%  |
| 2      | 12        | 7.27%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 127       | 76.97%  |
| 1      | 38        | 23.03%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 165       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306c3    | 12        | 7.27%   |
| 0x206a7    | 9         | 5.45%   |
| 0x806c1    | 8         | 4.85%   |
| 0x306a9    | 8         | 4.85%   |
| 0x506e3    | 7         | 4.24%   |
| 0x806ec    | 6         | 3.64%   |
| Unknown    | 6         | 3.64%   |
| 0x806ea    | 5         | 3.03%   |
| 0xa0652    | 4         | 2.42%   |
| 0x50654    | 4         | 2.42%   |
| 0x0a50000c | 4         | 2.42%   |
| 0x906a3    | 3         | 1.82%   |
| 0x806e9    | 3         | 1.82%   |
| 0x206c2    | 3         | 1.82%   |
| 0xa0671    | 2         | 1.21%   |
| 0xa0655    | 2         | 1.21%   |
| 0xa0653    | 2         | 1.21%   |
| 0x906ea    | 2         | 1.21%   |
| 0x906c0    | 2         | 1.21%   |
| 0x906a4    | 2         | 1.21%   |
| 0x90675    | 2         | 1.21%   |
| 0x90672    | 2         | 1.21%   |
| 0x706a8    | 2         | 1.21%   |
| 0x406f1    | 2         | 1.21%   |
| 0x40651    | 2         | 1.21%   |
| 0x306e4    | 2         | 1.21%   |
| 0x306d4    | 2         | 1.21%   |
| 0x206d7    | 2         | 1.21%   |
| 0x106a5    | 2         | 1.21%   |
| 0x10676    | 2         | 1.21%   |
| 0x0a601203 | 2         | 1.21%   |
| 0x0a50000d | 2         | 1.21%   |
| 0x08608103 | 2         | 1.21%   |
| 0x08600106 | 2         | 1.21%   |
| 0x08600104 | 2         | 1.21%   |
| 0x0800820d | 2         | 1.21%   |
| 0x06006705 | 2         | 1.21%   |
| 0x06000852 | 2         | 1.21%   |
| 0x906ed    | 1         | 0.61%   |
| 0x806d1    | 1         | 0.61%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 17        | 10.3%   |
| Haswell          | 17        | 10.3%   |
| Skylake          | 13        | 7.88%   |
| SandyBridge      | 12        | 7.27%   |
| Alderlake Hybrid | 12        | 7.27%   |
| IvyBridge        | 10        | 6.06%   |
| Zen 3            | 9         | 5.45%   |
| TigerLake        | 8         | 4.85%   |
| CometLake        | 8         | 4.85%   |
| Unknown          | 8         | 4.85%   |
| Zen 2            | 7         | 4.24%   |
| Piledriver       | 5         | 3.03%   |
| Zen+             | 4         | 2.42%   |
| Westmere         | 4         | 2.42%   |
| Penryn           | 4         | 2.42%   |
| IceLake          | 4         | 2.42%   |
| Broadwell        | 4         | 2.42%   |
| Nehalem          | 3         | 1.82%   |
| K10              | 3         | 1.82%   |
| Goldmont plus    | 3         | 1.82%   |
| Zen              | 2         | 1.21%   |
| Tremont          | 2         | 1.21%   |
| Excavator        | 2         | 1.21%   |
| Silvermont       | 1         | 0.61%   |
| K10 Llano        | 1         | 0.61%   |
| Jaguar           | 1         | 0.61%   |
| Core             | 1         | 0.61%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 88        | 43.14%  |
| Nvidia                     | 63        | 30.88%  |
| AMD                        | 41        | 20.1%   |
| Matrox Electronics Systems | 6         | 2.94%   |
| ASPEED Technology          | 6         | 2.94%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 8         | 3.85%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 7         | 3.37%   |
| ASPEED Technology ASPEED Graphics Family                                    | 6         | 2.88%   |
| Intel UHD Graphics 620                                                      | 5         | 2.4%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 5         | 2.4%    |
| Intel 3rd Gen Core processor Graphics Controller                            | 5         | 2.4%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 5         | 2.4%    |
| Nvidia GK208B [GeForce GT 730]                                              | 4         | 1.92%   |
| Intel HD Graphics 530                                                       | 4         | 1.92%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 4         | 1.92%   |
| Intel Alder Lake-P Integrated Graphics Controller                           | 4         | 1.92%   |
| Nvidia GK106GLM [Quadro K2100M]                                             | 3         | 1.44%   |
| Matrox Electronics Systems MGA G200eW WPCM450                               | 3         | 1.44%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3         | 1.44%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 3         | 1.44%   |
| Intel HD Graphics 620                                                       | 3         | 1.44%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 3         | 1.44%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 3         | 1.44%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                 | 3         | 1.44%   |
| AMD Renoir                                                                  | 3         | 1.44%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                  | 2         | 0.96%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                       | 2         | 0.96%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 2         | 0.96%   |
| Nvidia GP107GL [Quadro P400]                                                | 2         | 0.96%   |
| Nvidia GM108M [GeForce 940M]                                                | 2         | 0.96%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 2         | 0.96%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 2         | 0.96%   |
| Matrox Electronics Systems G200eR2                                          | 2         | 0.96%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 2         | 0.96%   |
| Intel JasperLake [UHD Graphics]                                             | 2         | 0.96%   |
| Intel HD Graphics 5500                                                      | 2         | 0.96%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2         | 0.96%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 2         | 0.96%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                    | 2         | 0.96%   |
| AMD RV620 LE [Radeon HD 3450]                                               | 2         | 0.96%   |
| AMD Rembrandt [Radeon 680M]                                                 | 2         | 0.96%   |
| AMD Raphael                                                                 | 2         | 0.96%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2         | 0.96%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 2         | 0.96%   |
| AMD Lucienne                                                                | 2         | 0.96%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 58        | 35.15%  |
| 1 x Nvidia      | 30        | 18.18%  |
| 1 x AMD         | 27        | 16.36%  |
| Intel + Nvidia  | 25        | 15.15%  |
| 1 x Matrox      | 5         | 3.03%   |
| AMD + Nvidia    | 5         | 3.03%   |
| 2 x AMD         | 4         | 2.42%   |
| Intel + AMD     | 3         | 1.82%   |
| 1 x ASPEED      | 3         | 1.82%   |
| AMD + ASPEED    | 2         | 1.21%   |
| Other           | 1         | 0.61%   |
| Nvidia + Matrox | 1         | 0.61%   |
| Nvidia + ASPEED | 1         | 0.61%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 132       | 80%     |
| Proprietary | 23        | 13.94%  |
| Unknown     | 10        | 6.06%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 83        | 50%     |
| 1.01-2.0   | 23        | 13.86%  |
| 0.01-0.5   | 22        | 13.25%  |
| 3.01-4.0   | 13        | 7.83%   |
| 0.51-1.0   | 10        | 6.02%   |
| 7.01-8.0   | 6         | 3.61%   |
| 5.01-6.0   | 4         | 2.41%   |
| 8.01-16.0  | 2         | 1.2%    |
| 32.01-64.0 | 1         | 0.6%    |
| 2.01-3.0   | 1         | 0.6%    |
| 16.01-24.0 | 1         | 0.6%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 21        | 11.8%   |
| Samsung Electronics     | 18        | 10.11%  |
| LG Display              | 16        | 8.99%   |
| AU Optronics            | 15        | 8.43%   |
| Goldstar                | 13        | 7.3%    |
| Chimei Innolux          | 11        | 6.18%   |
| BOE                     | 11        | 6.18%   |
| Acer                    | 8         | 4.49%   |
| Philips                 | 6         | 3.37%   |
| Hewlett-Packard         | 6         | 3.37%   |
| Sharp                   | 5         | 2.81%   |
| Ancor Communications    | 5         | 2.81%   |
| BenQ                    | 4         | 2.25%   |
| AOC                     | 4         | 2.25%   |
| InfoVision              | 3         | 1.69%   |
| Iiyama                  | 3         | 1.69%   |
| ViewSonic               | 2         | 1.12%   |
| SGT                     | 2         | 1.12%   |
| Sceptre Tech            | 2         | 1.12%   |
| PANDA                   | 2         | 1.12%   |
| Lenovo                  | 2         | 1.12%   |
| ASUSTek Computer        | 2         | 1.12%   |
| Apple                   | 2         | 1.12%   |
| Xiaomi                  | 1         | 0.56%   |
| Vizio                   | 1         | 0.56%   |
| Sony                    | 1         | 0.56%   |
| Panasonic               | 1         | 0.56%   |
| OEM                     | 1         | 0.56%   |
| NEC Computers           | 1         | 0.56%   |
| IBM                     | 1         | 0.56%   |
| HUAWEI                  | 1         | 0.56%   |
| Hitachi                 | 1         | 0.56%   |
| HCL                     | 1         | 0.56%   |
| Gigabyte Technology     | 1         | 0.56%   |
| Eizo                    | 1         | 0.56%   |
| CSO                     | 1         | 0.56%   |
| Chi Mei Optoelectronics | 1         | 0.56%   |
| ADR                     | 1         | 0.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                 | 2         | 1.09%   |
| Goldstar ULTRAWIDE GSM76F6 3440x1440 800x335mm 34.1-inch                | 2         | 1.09%   |
| Dell S3422DWG DELD124 3440x1440 797x334mm 34.0-inch                     | 2         | 1.09%   |
| Dell P2317H DEL40F4 1920x1080 509x286mm 23.0-inch                       | 2         | 1.09%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch          | 2         | 1.09%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch          | 2         | 1.09%   |
| Xiaomi Mi TV XMD00E1 1440x900 708x398mm 32.0-inch                       | 1         | 0.55%   |
| Vizio E320fi-B2 VIZ1005 1920x1080 477x268mm 21.5-inch                   | 1         | 0.55%   |
| ViewSonic VS2210-FHD VSC1939 1920x1080 476x268mm 21.5-inch              | 1         | 0.55%   |
| ViewSonic VA902b VSC211C 1280x1024 376x301mm 19.0-inch                  | 1         | 0.55%   |
| Sony TV *02 SNY045B 1920x1080 1085x610mm 49.0-inch                      | 1         | 0.55%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch                 | 1         | 0.55%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch                 | 1         | 0.55%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                 | 1         | 0.55%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                 | 1         | 0.55%   |
| Sharp LCD Monitor SHP1491 3840x2160 346x194mm 15.6-inch                 | 1         | 0.55%   |
| SGT M156F01 SGT1600 1920x1080 345x194mm 15.6-inch                       | 1         | 0.55%   |
| SGT LC156LF1L_03 SGT1560 1920x1080 345x194mm 15.6-inch                  | 1         | 0.55%   |
| Sceptre Tech X246W-1080p SPT2303 1920x1080 521x293mm 23.5-inch          | 1         | 0.55%   |
| Sceptre Tech X240-CNC SPT0978 1920x1080 880x490mm 39.7-inch             | 1         | 0.55%   |
| Samsung Electronics U32R59x SAM0F96 3840x2160 697x392mm 31.5-inch       | 1         | 0.55%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch       | 1         | 0.55%   |
| Samsung Electronics SyncMaster SAM062E 1280x1024 376x301mm 19.0-inch    | 1         | 0.55%   |
| Samsung Electronics SyncMaster SAM0467 1920x1200 518x324mm 24.1-inch    | 1         | 0.55%   |
| Samsung Electronics SyncMaster SAM0215 1280x1024 338x270mm 17.0-inch    | 1         | 0.55%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch       | 1         | 0.55%   |
| Samsung Electronics LF27T450F SAM7099 1920x1080 597x336mm 27.0-inch     | 1         | 0.55%   |
| Samsung Electronics LF27T35 SAM7080 1920x1080 600x340mm 27.2-inch       | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch    | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch   | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 344x194mm 15.5-inch    | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SDC3752 1920x1080 344x194mm 15.5-inch   | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 950x540mm 43.0-inch   | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SAM0F14 3840x2160 1872x1053mm 84.6-inch | 1         | 0.55%   |
| Samsung Electronics F27G3xTF SAM710D 1920x1080 600x330mm 27.0-inch      | 1         | 0.55%   |
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch      | 1         | 0.55%   |
| Samsung Electronics C49J89x SAM0F21 3840x1080 1196x336mm 48.9-inch      | 1         | 0.55%   |
| Samsung Electronics C27F398 SAM0D44 1920x1080 598x336mm 27.0-inch       | 1         | 0.55%   |
| Philips PHL 499P9 PHL092A 3840x1080 1193x336mm 48.8-inch                | 1         | 0.55%   |
| Philips PHL 275E2F PHLC23A 2560x1440 600x340mm 27.2-inch                | 1         | 0.55%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 72        | 42.35%  |
| 1366x768 (WXGA)    | 14        | 8.24%   |
| 3840x2160 (4K)     | 12        | 7.06%   |
| 2560x1440 (QHD)    | 12        | 7.06%   |
| 1920x1200 (WUXGA)  | 11        | 6.47%   |
| 1280x1024 (SXGA)   | 9         | 5.29%   |
| 1600x900 (HD+)     | 7         | 4.12%   |
| 3440x1440          | 6         | 3.53%   |
| 3840x1080          | 4         | 2.35%   |
| 2560x1080          | 4         | 2.35%   |
| 1680x1050 (WSXGA+) | 4         | 2.35%   |
| 3840x2400          | 3         | 1.76%   |
| 1920x540           | 2         | 1.18%   |
| 1440x900 (WXGA+)   | 2         | 1.18%   |
| 1024x768 (XGA)     | 2         | 1.18%   |
| Unknown            | 2         | 1.18%   |
| 2880x1800          | 1         | 0.59%   |
| 2240x1400          | 1         | 0.59%   |
| 2160x1440          | 1         | 0.59%   |
| 1280x768           | 1         | 0.59%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 36        | 20.34%  |
| 14      | 21        | 11.86%  |
| 27      | 17        | 9.6%    |
| 24      | 17        | 9.6%    |
| 17      | 11        | 6.21%   |
| 34      | 10        | 5.65%   |
| 13      | 9         | 5.08%   |
| 23      | 8         | 4.52%   |
| 31      | 7         | 3.95%   |
| 21      | 7         | 3.95%   |
| 19      | 7         | 3.95%   |
| 20      | 4         | 2.26%   |
| 22      | 3         | 1.69%   |
| 84      | 2         | 1.13%   |
| 65      | 2         | 1.13%   |
| 48      | 2         | 1.13%   |
| 40      | 2         | 1.13%   |
| 18      | 2         | 1.13%   |
| 16      | 2         | 1.13%   |
| Unknown | 2         | 1.13%   |
| 49      | 1         | 0.56%   |
| 39      | 1         | 0.56%   |
| 32      | 1         | 0.56%   |
| 28      | 1         | 0.56%   |
| 25      | 1         | 0.56%   |
| 12      | 1         | 0.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 65        | 36.93%  |
| 501-600     | 40        | 22.73%  |
| 401-500     | 21        | 11.93%  |
| 351-400     | 12        | 6.82%   |
| 701-800     | 11        | 6.25%   |
| 601-700     | 8         | 4.55%   |
| 201-300     | 7         | 3.98%   |
| 1001-1500   | 5         | 2.84%   |
| 801-900     | 3         | 1.7%    |
| 1501-2000   | 2         | 1.14%   |
| Unknown     | 2         | 1.14%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 110       | 70.06%  |
| 16/10   | 20        | 12.74%  |
| 21/9    | 9         | 5.73%   |
| 5/4     | 8         | 5.1%    |
| 32/9    | 3         | 1.91%   |
| 3/2     | 3         | 1.91%   |
| 4/3     | 2         | 1.27%   |
| 6/5     | 1         | 0.64%   |
| Unknown | 1         | 0.64%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 35        | 20%     |
| 201-250        | 28        | 16%     |
| 81-90          | 26        | 14.86%  |
| 351-500        | 18        | 10.29%  |
| 301-350        | 17        | 9.71%   |
| 151-200        | 12        | 6.86%   |
| 121-130        | 7         | 4%      |
| 501-1000       | 7         | 4%      |
| 141-150        | 6         | 3.43%   |
| 251-300        | 5         | 2.86%   |
| More than 1000 | 4         | 2.29%   |
| 71-80          | 3         | 1.71%   |
| 111-120        | 3         | 1.71%   |
| Unknown        | 2         | 1.14%   |
| 61-70          | 1         | 0.57%   |
| 91-100         | 1         | 0.57%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 75        | 43.1%   |
| 121-160       | 47        | 27.01%  |
| 101-120       | 28        | 16.09%  |
| 161-240       | 13        | 7.47%   |
| More than 240 | 7         | 4.02%   |
| 1-50          | 2         | 1.15%   |
| Unknown       | 2         | 1.15%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 106       | 64.24%  |
| 2     | 30        | 18.18%  |
| 0     | 24        | 14.55%  |
| 3     | 4         | 2.42%   |
| 4     | 1         | 0.61%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 106       | 43.09%  |
| Realtek Semiconductor     | 73        | 29.67%  |
| Broadcom                  | 13        | 5.28%   |
| Qualcomm Atheros          | 10        | 4.07%   |
| MediaTek                  | 10        | 4.07%   |
| ASIX Electronics          | 6         | 2.44%   |
| Mellanox Technologies     | 3         | 1.22%   |
| Lenovo                    | 3         | 1.22%   |
| Broadcom Limited          | 3         | 1.22%   |
| Ralink Technology         | 2         | 0.81%   |
| Marvell Technology Group  | 2         | 0.81%   |
| Linksys                   | 2         | 0.81%   |
| TP-Link                   | 1         | 0.41%   |
| Spreadtrum Communications | 1         | 0.41%   |
| Solarflare Communications | 1         | 0.41%   |
| Ralink                    | 1         | 0.41%   |
| Qualcomm                  | 1         | 0.41%   |
| Microsoft                 | 1         | 0.41%   |
| JMicron Technology        | 1         | 0.41%   |
| Dell                      | 1         | 0.41%   |
| D-Link                    | 1         | 0.41%   |
| BUFFALO                   | 1         | 0.41%   |
| ASUSTek Computer          | 1         | 0.41%   |
| Aquantia                  | 1         | 0.41%   |
| American Megatrends       | 1         | 0.41%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                                                                  | Computers | Percent |
|------------------------------------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                                                      | 48        | 16.49%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                                               | 11        | 3.78%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                                                  | 9         | 3.09%   |
| Intel Ethernet Controller I225-V                                                                                       | 8         | 2.75%   |
| Intel Ethernet Connection I217-LM                                                                                      | 7         | 2.41%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                                                       | 7         | 2.41%   |
| Intel Wireless 8265 / 8275                                                                                             | 6         | 2.06%   |
| Intel Wireless 7260                                                                                                    | 6         | 2.06%   |
| Intel Wi-Fi 6 AX201                                                                                                    | 6         | 2.06%   |
| Intel Wi-Fi 6 AX200                                                                                                    | 6         | 2.06%   |
| ASIX AX88179 Gigabit Ethernet                                                                                          | 6         | 2.06%   |
| Realtek RTL8125 2.5GbE Controller                                                                                      | 5         | 1.72%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                                                | 4         | 1.37%   |
| Intel I211 Gigabit Network Connection                                                                                  | 4         | 1.37%   |
| Intel Comet Lake PCH CNVi WiFi                                                                                         | 4         | 1.37%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                                           | 4         | 1.37%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                                             | 3         | 1.03%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                                                          | 3         | 1.03%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                                          | 3         | 1.03%   |
| Intel Wireless 8260                                                                                                    | 3         | 1.03%   |
| Intel Wireless 7265                                                                                                    | 3         | 1.03%   |
| Intel Wireless 3165                                                                                                    | 3         | 1.03%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                                                 | 3         | 1.03%   |
| Intel Ethernet Connection (4) I219-V                                                                                   | 3         | 1.03%   |
| Intel Ethernet Connection (2) I219-LM                                                                                  | 3         | 1.03%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                                                      | 3         | 1.03%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                                                         | 3         | 1.03%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                                                     | 2         | 0.69%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                                               | 2         | 0.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                                               | 2         | 0.69%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                                                  | 2         | 0.69%   |
| Ralink MT7601U Wireless Adapter                                                                                        | 2         | 0.69%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                                             | 2         | 0.69%   |
| Mellanox MT25408A0-FCC-QI ConnectX, Dual Port 40Gb/s InfiniBand / 10GigE Adapter IC with PCIe 2.0 x8 5.0GT/s Interface | 2         | 0.69%   |
| Lenovo ThinkPad TBT 3 Dock                                                                                             | 2         | 0.69%   |
| Intel I350 Gigabit Network Connection                                                                                  | 2         | 0.69%   |
| Intel I210 Gigabit Network Connection                                                                                  | 2         | 0.69%   |
| Intel Ethernet Virtual Function 700 Series                                                                             | 2         | 0.69%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                                                           | 2         | 0.69%   |
| Intel Ethernet Connection I217-V                                                                                       | 2         | 0.69%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 62        | 57.94%  |
| Realtek Semiconductor | 12        | 11.21%  |
| MediaTek              | 10        | 9.35%   |
| Qualcomm Atheros      | 9         | 8.41%   |
| Broadcom              | 3         | 2.8%    |
| Ralink Technology     | 2         | 1.87%   |
| Linksys               | 2         | 1.87%   |
| TP-Link               | 1         | 0.93%   |
| Ralink                | 1         | 0.93%   |
| Microsoft             | 1         | 0.93%   |
| Dell                  | 1         | 0.93%   |
| BUFFALO               | 1         | 0.93%   |
| Broadcom Limited      | 1         | 0.93%   |
| ASUSTek Computer      | 1         | 0.93%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                              | Computers | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake-P PCH CNVi WiFi                                   | 7         | 6.42%   |
| Intel Wireless 8265 / 8275                                         | 6         | 5.5%    |
| Intel Wireless 7260                                                | 6         | 5.5%    |
| Intel Wi-Fi 6 AX201                                                | 6         | 5.5%    |
| Intel Wi-Fi 6 AX200                                                | 6         | 5.5%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                            | 4         | 3.67%   |
| Intel Comet Lake PCH CNVi WiFi                                     | 4         | 3.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                       | 4         | 3.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter         | 3         | 2.75%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter      | 3         | 2.75%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter      | 3         | 2.75%   |
| Intel Wireless 8260                                                | 3         | 2.75%   |
| Intel Wireless 7265                                                | 3         | 2.75%   |
| Intel Wireless 3165                                                | 3         | 2.75%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                             | 3         | 2.75%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                  | 3         | 2.75%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                 | 2         | 1.83%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter           | 2         | 1.83%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter           | 2         | 1.83%   |
| Ralink MT7601U Wireless Adapter                                    | 2         | 1.83%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter         | 2         | 1.83%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                           | 2         | 1.83%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                              | 1         | 0.92%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller [1T1R] | 1         | 0.92%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller        | 1         | 0.92%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter            | 1         | 0.92%   |
| Realtek RTL8723DE Wireless Network Adapter                         | 1         | 0.92%   |
| Realtek RTL8191SEvB Wireless LAN Controller                        | 1         | 0.92%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter              | 1         | 0.92%   |
| Realtek 802.11ac NIC                                               | 1         | 0.92%   |
| Ralink RT3071 Wireless Adapter                                     | 1         | 0.92%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                          | 1         | 0.92%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter         | 1         | 0.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                   | 1         | 0.92%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                   | 1         | 0.92%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                   | 1         | 0.92%   |
| Microsoft Xbox 360 Wireless Adapter                                | 1         | 0.92%   |
| Linksys WUSB6100M 802.11a/b/g/n/ac Wireless Adapter                | 1         | 0.92%   |
| Linksys AE2500 802.11abgn Wireless Adapter [Broadcom BCM43236]     | 1         | 0.92%   |
| Intel Wireless 3160                                                | 1         | 0.92%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 73        | 42.2%   |
| Realtek Semiconductor     | 67        | 38.73%  |
| Broadcom                  | 11        | 6.36%   |
| ASIX Electronics          | 6         | 3.47%   |
| Lenovo                    | 3         | 1.73%   |
| Marvell Technology Group  | 2         | 1.16%   |
| Broadcom Limited          | 2         | 1.16%   |
| Spreadtrum Communications | 1         | 0.58%   |
| Solarflare Communications | 1         | 0.58%   |
| Qualcomm Atheros          | 1         | 0.58%   |
| Qualcomm                  | 1         | 0.58%   |
| Mellanox Technologies     | 1         | 0.58%   |
| JMicron Technology        | 1         | 0.58%   |
| D-Link                    | 1         | 0.58%   |
| Aquantia                  | 1         | 0.58%   |
| American Megatrends       | 1         | 0.58%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 48        | 26.67%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 11        | 6.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 5%      |
| Intel Ethernet Controller I225-V                                  | 8         | 4.44%   |
| Intel Ethernet Connection I217-LM                                 | 7         | 3.89%   |
| ASIX AX88179 Gigabit Ethernet                                     | 6         | 3.33%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 2.78%   |
| Intel I211 Gigabit Network Connection                             | 4         | 2.22%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 1.67%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 1.67%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 3         | 1.67%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 1.11%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 2         | 1.11%   |
| Intel I350 Gigabit Network Connection                             | 2         | 1.11%   |
| Intel I210 Gigabit Network Connection                             | 2         | 1.11%   |
| Intel Ethernet Virtual Function 700 Series                        | 2         | 1.11%   |
| Intel Ethernet Connection X722 for 10GBASE-T                      | 2         | 1.11%   |
| Intel Ethernet Connection I217-V                                  | 2         | 1.11%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 1.11%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.11%   |
| Intel Ethernet Connection (17) I219-V                             | 2         | 1.11%   |
| Intel Ethernet Connection (16) I219-V                             | 2         | 1.11%   |
| Intel Ethernet Connection (16) I219-LM                            | 2         | 1.11%   |
| Intel Ethernet Connection (14) I219-V                             | 2         | 1.11%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 1.11%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 1.11%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express           | 2         | 1.11%   |
| Spreadtrum realme Phone                                           | 1         | 0.56%   |
| Solarflare SFC9020 10G Ethernet Controller                        | 1         | 0.56%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.56%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.56%   |
| Qualcomm Redmi Note 8                                             | 1         | 0.56%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.56%   |
| Mellanox MT27700 Family [ConnectX-4]                              | 1         | 0.56%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 0.56%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 1         | 0.56%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 1         | 0.56%   |
| Lenovo USB-C to LAN                                               | 1         | 0.56%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.56%   |
| Intel Ethernet Controller X710/X557-AT 10GBASE-T                  | 1         | 0.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 148       | 58.73%  |
| WiFi     | 102       | 40.48%  |
| Unknown  | 2         | 0.79%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 110       | 62.15%  |
| WiFi     | 67        | 37.85%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 76        | 46.06%  |
| 1     | 68        | 41.21%  |
| 3     | 8         | 4.85%   |
| 5     | 4         | 2.42%   |
| 4     | 4         | 2.42%   |
| 0     | 2         | 1.21%   |
| 132   | 1         | 0.61%   |
| 66    | 1         | 0.61%   |
| 8     | 1         | 0.61%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 130       | 78.79%  |
| Yes  | 35        | 21.21%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 53        | 58.89%  |
| Realtek Semiconductor           | 6         | 6.67%   |
| MediaTek                        | 6         | 6.67%   |
| Qualcomm Atheros Communications | 5         | 5.56%   |
| Foxconn / Hon Hai               | 4         | 4.44%   |
| Cambridge Silicon Radio         | 4         | 4.44%   |
| Broadcom                        | 4         | 4.44%   |
| IMC Networks                    | 3         | 3.33%   |
| Ralink                          | 1         | 1.11%   |
| Integrated System Solution      | 1         | 1.11%   |
| Hewlett-Packard                 | 1         | 1.11%   |
| Dell                            | 1         | 1.11%   |
| Apple                           | 1         | 1.11%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                    | 21        | 23.33%  |
| Intel AX201 Bluetooth                                 | 14        | 15.56%  |
| MediaTek Wireless_Device                              | 6         | 6.67%   |
| Intel AX200 Bluetooth                                 | 6         | 6.67%   |
| Realtek Bluetooth Radio                               | 5         | 5.56%   |
| Intel Bluetooth Device                                | 5         | 5.56%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 4         | 4.44%   |
| Qualcomm Atheros  Bluetooth Device                    | 3         | 3.33%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 3         | 3.33%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter          | 3         | 3.33%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 2         | 2.22%   |
| Intel AX210 Bluetooth                                 | 2         | 2.22%   |
| Realtek  Bluetooth 4.2 Adapter                        | 1         | 1.11%   |
| Ralink RT3290 Bluetooth                               | 1         | 1.11%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 1         | 1.11%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 1         | 1.11%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1         | 1.11%   |
| IMC Networks Wireless_Device                          | 1         | 1.11%   |
| IMC Networks Bluetooth Radio                          | 1         | 1.11%   |
| IMC Networks Bluetooth Device                         | 1         | 1.11%   |
| HP Broadcom 2070 Bluetooth Combo                      | 1         | 1.11%   |
| Foxconn / Hon Hai MediaTek MT7921 Bluetooth           | 1         | 1.11%   |
| Dell Broadcom BCM20702A0 Bluetooth                    | 1         | 1.11%   |
| Broadcom HP Portable Bumble Bee                       | 1         | 1.11%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 1         | 1.11%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]            | 1         | 1.11%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]    | 1         | 1.11%   |
| Apple Bluetooth Host Controller                       | 1         | 1.11%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 107       | 45.34%  |
| Nvidia                 | 48        | 20.34%  |
| AMD                    | 45        | 19.07%  |
| C-Media Electronics    | 6         | 2.54%   |
| Logitech               | 5         | 2.12%   |
| Texas Instruments      | 2         | 0.85%   |
| Lenovo                 | 2         | 0.85%   |
| GN Netcom              | 2         | 0.85%   |
| Creative Technology    | 2         | 0.85%   |
| Conexant Systems       | 2         | 0.85%   |
| ASUSTek Computer       | 2         | 0.85%   |
| VIA Technologies       | 1         | 0.42%   |
| Tenx Technology        | 1         | 0.42%   |
| Setek Elektronik       | 1         | 0.42%   |
| Saitek                 | 1         | 0.42%   |
| Realtek Semiconductor  | 1         | 0.42%   |
| Plantronics            | 1         | 0.42%   |
| Nektar                 | 1         | 0.42%   |
| KTMicro                | 1         | 0.42%   |
| Huawei Technologies    | 1         | 0.42%   |
| Hewlett-Packard        | 1         | 0.42%   |
| GYROCOM C&C            | 1         | 0.42%   |
| Generalplus Technology | 1         | 0.42%   |
| Creative Labs          | 1         | 0.42%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 19        | 6.86%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 13        | 4.69%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 11        | 3.97%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 10        | 3.61%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 9         | 3.25%   |
| Intel Sunrise Point-LP HD Audio                                            | 9         | 3.25%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 8         | 2.89%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 8         | 2.89%   |
| Intel Comet Lake PCH cAVS                                                  | 6         | 2.17%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 5         | 1.81%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 5         | 1.81%   |
| Nvidia GK107 HDMI Audio Controller                                         | 5         | 1.81%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 1.81%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 1.81%   |
| AMD Starship/Matisse HD Audio Controller                                   | 5         | 1.81%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5         | 1.81%   |
| Nvidia GK106 HDMI Audio Controller                                         | 4         | 1.44%   |
| Nvidia GA104 High Definition Audio Controller                              | 4         | 1.44%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 4         | 1.44%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 1.08%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3         | 1.08%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 1.08%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 1.08%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.08%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 1.08%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 3         | 1.08%   |
| Intel Alder Lake-S HD Audio Controller                                     | 3         | 1.08%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3         | 1.08%   |
| Intel 200 Series PCH HD Audio                                              | 3         | 1.08%   |
| AMD FCH Azalia Controller                                                  | 3         | 1.08%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3         | 1.08%   |
| Texas Instruments PCM2902 Audio Codec                                      | 2         | 0.72%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 0.72%   |
| Nvidia GK104 HDMI Audio Controller                                         | 2         | 0.72%   |
| Nvidia GA106 High Definition Audio Controller                              | 2         | 0.72%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 0.72%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 0.72%   |
| Intel Jasper Lake HD Audio                                                 | 2         | 0.72%   |
| Intel Haswell-ULT HD Audio Controller                                      | 2         | 0.72%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 2         | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 31        | 23.66%  |
| Micron Technology   | 20        | 15.27%  |
| SK hynix            | 17        | 12.98%  |
| Kingston            | 10        | 7.63%   |
| Unknown             | 9         | 6.87%   |
| Crucial             | 9         | 6.87%   |
| G.Skill             | 8         | 6.11%   |
| Corsair             | 8         | 6.11%   |
| A-DATA Technology   | 3         | 2.29%   |
| Unknown             | 2         | 1.53%   |
| Wodposit            | 1         | 0.76%   |
| Unknown (ABCD)      | 1         | 0.76%   |
| Team                | 1         | 0.76%   |
| Smart               | 1         | 0.76%   |
| Ramaxel Technology  | 1         | 0.76%   |
| PNY                 | 1         | 0.76%   |
| Patriot             | 1         | 0.76%   |
| Nanya Technology    | 1         | 0.76%   |
| Magnum Tech         | 1         | 0.76%   |
| Lexar Co Limited    | 1         | 0.76%   |
| Lexar               | 1         | 0.76%   |
| HPE                 | 1         | 0.76%   |
| Hewlett-Packard     | 1         | 0.76%   |
| Gold Key            | 1         | 0.76%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.48%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 2         | 1.48%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.48%   |
| Unknown                                                          | 2         | 1.48%   |
| Wodposit RAM WPBH26D408SWA-8G 8GB SODIMM DDR4 2400MT/s           | 1         | 0.74%   |
| Unknown RAM Module 8GB DIMM DDR4 3000MT/s                        | 1         | 0.74%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 1         | 0.74%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 1         | 0.74%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 1         | 0.74%   |
| Unknown RAM Module 2GB DIMM 667MT/s                              | 1         | 0.74%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 1         | 0.74%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                         | 1         | 0.74%   |
| Unknown RAM Module 1GB DIMM 667MT/s                              | 1         | 0.74%   |
| Unknown RAM Module 16GB DIMM DDR4 2666MT/s                       | 1         | 0.74%   |
| Unknown RAM DDR4 NB 8G 2666 8GB SODIMM DDR4 2667MT/s             | 1         | 0.74%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 1         | 0.74%   |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3733MT/s              | 1         | 0.74%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.74%   |
| SK hynix RAM Module 8GB SODIMM DDR4 3200MT/s                     | 1         | 0.74%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 0.74%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1066MT/s                     | 1         | 0.74%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s                       | 1         | 0.74%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s             | 1         | 0.74%   |
| SK hynix RAM HMT325U7EFR8A-PB 2GB DIMM DDR3 1600MT/s             | 1         | 0.74%   |
| SK hynix RAM HMT31GR7BFR4C-H9 8GB DIMM DDR3 1333MT/s             | 1         | 0.74%   |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s           | 1         | 0.74%   |
| SK hynix RAM HMAB2GS6CMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 0.74%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s          | 1         | 0.74%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 0.74%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.74%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 1         | 0.74%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.74%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s       | 1         | 0.74%   |
| Samsung RAM Module 8GB SODIMM DDR5 4800MT/s                      | 1         | 0.74%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 0.74%   |
| Samsung RAM Module 16GB SODIMM DDR5 4800MT/s                     | 1         | 0.74%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 1         | 0.74%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 0.74%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 0.74%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 0.74%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 65        | 57.52%  |
| DDR3    | 32        | 28.32%  |
| DDR5    | 6         | 5.31%   |
| LPDDR4  | 3         | 2.65%   |
| DDR2    | 3         | 2.65%   |
| LPDDR5  | 2         | 1.77%   |
| LPDDR3  | 1         | 0.88%   |
| Unknown | 1         | 0.88%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 53        | 46.49%  |
| DIMM         | 53        | 46.49%  |
| Row Of Chips | 6         | 5.26%   |
| RIMM         | 1         | 0.88%   |
| Unknown      | 1         | 0.88%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 49        | 40.5%   |
| 16384 | 26        | 21.49%  |
| 4096  | 20        | 16.53%  |
| 32768 | 15        | 12.4%   |
| 1024  | 6         | 4.96%   |
| 2048  | 5         | 4.13%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 28        | 23.14%  |
| 2667  | 19        | 15.7%   |
| 1600  | 15        | 12.4%   |
| 2400  | 11        | 9.09%   |
| 1333  | 8         | 6.61%   |
| 2133  | 6         | 4.96%   |
| 4800  | 5         | 4.13%   |
| 2666  | 4         | 3.31%   |
| 1066  | 3         | 2.48%   |
| 667   | 3         | 2.48%   |
| 3600  | 2         | 1.65%   |
| 3534  | 2         | 1.65%   |
| 6400  | 1         | 0.83%   |
| 5600  | 1         | 0.83%   |
| 5500  | 1         | 0.83%   |
| 4267  | 1         | 0.83%   |
| 4266  | 1         | 0.83%   |
| 3733  | 1         | 0.83%   |
| 3666  | 1         | 0.83%   |
| 3266  | 1         | 0.83%   |
| 3100  | 1         | 0.83%   |
| 3000  | 1         | 0.83%   |
| 2800  | 1         | 0.83%   |
| 2200  | 1         | 0.83%   |
| 2048  | 1         | 0.83%   |
| 1866  | 1         | 0.83%   |
| 1800  | 1         | 0.83%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Seiko Epson        | 2         | 66.67%  |
| Brother Industries | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Seiko Epson XP-4100 Series    | 1         | 33.33%  |
| Seiko Epson Printer           | 1         | 33.33%  |
| Brother HL-2030 Laser Printer | 1         | 33.33%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| HP ScanJet 82x0C  | 1         | 50%     |
| HP OfficeJet 6110 | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 16        | 21.33%  |
| IMC Networks                           | 12        | 16%     |
| Realtek Semiconductor                  | 6         | 8%      |
| Microdia                               | 5         | 6.67%   |
| Syntek                                 | 4         | 5.33%   |
| Sunplus Innovation Technology          | 4         | 5.33%   |
| Luxvisions Innotech Limited            | 4         | 5.33%   |
| Logitech                               | 4         | 5.33%   |
| Bison Electronics                      | 4         | 5.33%   |
| webcamvendor                           | 2         | 2.67%   |
| Quanta                                 | 2         | 2.67%   |
| Generalplus Technology                 | 2         | 2.67%   |
| Suyin                                  | 1         | 1.33%   |
| Sonix Technology                       | 1         | 1.33%   |
| Lite-On Technology                     | 1         | 1.33%   |
| Lenovo                                 | 1         | 1.33%   |
| KYE Systems (Mouse Systems)            | 1         | 1.33%   |
| Intel                                  | 1         | 1.33%   |
| Huawei Technologies                    | 1         | 1.33%   |
| Elgato Systems                         | 1         | 1.33%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.33%   |
| Apple                                  | 1         | 1.33%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 8         | 10.53%  |
| Realtek Integrated_Webcam_HD                        | 4         | 5.26%   |
| Microdia Integrated_Webcam_HD                       | 4         | 5.26%   |
| IMC Networks Integrated Camera                      | 4         | 5.26%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 3         | 3.95%   |
| Chicony HP HD Camera                                | 3         | 3.95%   |
| webcamvendor webcamproduct                          | 2         | 2.63%   |
| Syntek Lenovo EasyCamera                            | 2         | 2.63%   |
| Syntek Integrated Camera                            | 2         | 2.63%   |
| Logitech HD Pro Webcam C920                         | 2         | 2.63%   |
| Generalplus CAMERA - UVC                            | 2         | 2.63%   |
| Chicony HD WebCam                                   | 2         | 2.63%   |
| Bison Integrated RGB Camera                         | 2         | 2.63%   |
| Suyin HP TrueVision HD Integrated Webcam            | 1         | 1.32%   |
| Sunplus NexiGo N930AF FHD Webcam                    | 1         | 1.32%   |
| Sunplus Laptop_Integrated_Webcam_HD                 | 1         | 1.32%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 1.32%   |
| Sunplus Integrated_Webcam_FHD                       | 1         | 1.32%   |
| Sonix USB2.0 HD UVC WebCam                          | 1         | 1.32%   |
| Realtek USB2.0 HD UVC WebCam                        | 1         | 1.32%   |
| Realtek EasyCamera                                  | 1         | 1.32%   |
| Quanta HP Webcam                                    | 1         | 1.32%   |
| Quanta HP 5MP Camera                                | 1         | 1.32%   |
| Microdia Integrated_Webcam_FHD                      | 1         | 1.32%   |
| Luxvisions Innotech Limited Integrated RGB Camera   | 1         | 1.32%   |
| Luxvisions Innotech Limited Integrated Camera       | 1         | 1.32%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 1.32%   |
| Luxvisions Innotech Limited HP HD Camera            | 1         | 1.32%   |
| Logitech Webcam C270                                | 1         | 1.32%   |
| Logitech BRIO                                       | 1         | 1.32%   |
| Lite-On HP HD Webcam                                | 1         | 1.32%   |
| Lenovo UVC Camera                                   | 1         | 1.32%   |
| KYE Systems (Mouse Systems) PC-LM1E Camera          | 1         | 1.32%   |
| Intel RealSense 3D Camera (Front F200)              | 1         | 1.32%   |
| IMC Networks TOSHIBA Web Camera - HD                | 1         | 1.32%   |
| IMC Networks Lenovo EasyCamera                      | 1         | 1.32%   |
| IMC Networks HP TrueVision HD Camera                | 1         | 1.32%   |
| IMC Networks HD Camera                              | 1         | 1.32%   |
| IMC Networks EasyCamera                             | 1         | 1.32%   |
| Huawei HiCamera                                     | 1         | 1.32%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 10        | 35.71%  |
| Validity Sensors           | 7         | 25%     |
| Shenzhen Goodix Technology | 5         | 17.86%  |
| LighTuning Technology      | 3         | 10.71%  |
| Upek                       | 1         | 3.57%   |
| Elan Microelectronics      | 1         | 3.57%   |
| AuthenTec                  | 1         | 3.57%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 10.71%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 2         | 7.14%   |
| Synaptics UWP WBDI Device                                                  | 2         | 7.14%   |
| Shenzhen Goodix  Fingerprint Device                                        | 2         | 7.14%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 7.14%   |
| LighTuning Fingerprint Sensor                                              | 2         | 7.14%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 3.57%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 3.57%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 3.57%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 3.57%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 3.57%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 3.57%   |
| Synaptics WBDI                                                             | 1         | 3.57%   |
| Synaptics  WBDI                                                            | 1         | 3.57%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 3.57%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 3.57%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 3.57%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 3.57%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 3.57%   |
| Elan ELAN:Fingerprint                                                      | 1         | 3.57%   |
| AuthenTec AES2810                                                          | 1         | 3.57%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 3         | 50%     |
| Broadcom    | 2         | 33.33%  |
| O2 Micro    | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 50%     |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 16.67%  |
| Broadcom 58200                                                               | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 90        | 54.55%  |
| 1     | 54        | 32.73%  |
| 2     | 14        | 8.48%   |
| 3     | 3         | 1.82%   |
| 5     | 2         | 1.21%   |
| 4     | 2         | 1.21%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 28        | 28.57%  |
| Graphics card            | 19        | 19.39%  |
| Net/wireless             | 11        | 11.22%  |
| Unassigned class         | 8         | 8.16%   |
| Communication controller | 7         | 7.14%   |
| Net/ethernet             | 4         | 4.08%   |
| Multimedia controller    | 4         | 4.08%   |
| Sound                    | 3         | 3.06%   |
| Firewire controller      | 3         | 3.06%   |
| Chipcard                 | 3         | 3.06%   |
| Network                  | 2         | 2.04%   |
| Storage/raid             | 1         | 1.02%   |
| Storage/ide              | 1         | 1.02%   |
| Storage                  | 1         | 1.02%   |
| Dvb card                 | 1         | 1.02%   |
| Card reader              | 1         | 1.02%   |
| Bluetooth                | 1         | 1.02%   |

