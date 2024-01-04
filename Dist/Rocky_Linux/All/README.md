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

Total: 250

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | PRIME Z490-P                | Desktop     | [61724f27e7](https://linux-hardware.org/?probe=61724f27e7) | Dec 23, 2023 |
| ASRock        | Z790 Taichi                 | Desktop     | [3bc8305321](https://linux-hardware.org/?probe=3bc8305321) | Dec 22, 2023 |
| Lenovo        | G450 2949                   | Notebook    | [c8c0737175](https://linux-hardware.org/?probe=c8c0737175) | Dec 20, 2023 |
| ASRock        | Z790 Taichi                 | Desktop     | [bffb0cadbe](https://linux-hardware.org/?probe=bffb0cadbe) | Dec 17, 2023 |
| Lenovo        | ThinkPad T430u 86147MG      | Notebook    | [0463c0adc2](https://linux-hardware.org/?probe=0463c0adc2) | Dec 17, 2023 |
| Dell          | Precision 5520              | Notebook    | [b3ea29b5a2](https://linux-hardware.org/?probe=b3ea29b5a2) | Dec 14, 2023 |
| Lenovo        | 3130 SDK0J40697 WIN 3305... | Mini pc     | [e290fd161e](https://linux-hardware.org/?probe=e290fd161e) | Dec 12, 2023 |
| Positivo      | Q464C                       | Notebook    | [47071c986c](https://linux-hardware.org/?probe=47071c986c) | Dec 11, 2023 |
| Gigabyte      | X670 GAMING X AX            | Desktop     | [18d321d9d6](https://linux-hardware.org/?probe=18d321d9d6) | Dec 06, 2023 |
| Dell          | Vostro 3420                 | Notebook    | [95a9c16f88](https://linux-hardware.org/?probe=95a9c16f88) | Nov 28, 2023 |
| HP            | 2AF3                        | Desktop     | [fd3b043741](https://linux-hardware.org/?probe=fd3b043741) | Nov 25, 2023 |
| Dell          | 0XDN97 A02                  | Server      | [0f4391e6bf](https://linux-hardware.org/?probe=0f4391e6bf) | Nov 25, 2023 |
| Pegatron      | IPMIP-GS                    | Desktop     | [fb0f45f5b0](https://linux-hardware.org/?probe=fb0f45f5b0) | Nov 24, 2023 |
| HP            | 158B                        | Desktop     | [bd8928c0a2](https://linux-hardware.org/?probe=bd8928c0a2) | Nov 22, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [3f8f235cae](https://linux-hardware.org/?probe=3f8f235cae) | Nov 19, 2023 |
| System76      | Thelio Mira thelio-mira-... | Desktop     | [a6d3f50714](https://linux-hardware.org/?probe=a6d3f50714) | Nov 18, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [bdbde84396](https://linux-hardware.org/?probe=bdbde84396) | Nov 18, 2023 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | Notebook    | [f36053c77c](https://linux-hardware.org/?probe=f36053c77c) | Nov 13, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [37aa104ebf](https://linux-hardware.org/?probe=37aa104ebf) | Nov 06, 2023 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | Desktop     | [3734293144](https://linux-hardware.org/?probe=3734293144) | Nov 06, 2023 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | Desktop     | [72bedff7a6](https://linux-hardware.org/?probe=72bedff7a6) | Nov 06, 2023 |
| Lenovo        | G450 2949                   | Notebook    | [3f631dfb6e](https://linux-hardware.org/?probe=3f631dfb6e) | Nov 04, 2023 |
| ASUSTek       | Zenbook UP6502ZD_UP6502Z... | Convertible | [849d24e533](https://linux-hardware.org/?probe=849d24e533) | Nov 02, 2023 |
| Dell          | Latitude 7490               | Notebook    | [4859e397e4](https://linux-hardware.org/?probe=4859e397e4) | Nov 02, 2023 |
| HP            | 829A                        | Mini pc     | [d0735e46db](https://linux-hardware.org/?probe=d0735e46db) | Nov 01, 2023 |
| Gigabyte      | MJ11-EC1-OT 01000100        | Server      | [9a7be2dcbd](https://linux-hardware.org/?probe=9a7be2dcbd) | Oct 31, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [650d69cdce](https://linux-hardware.org/?probe=650d69cdce) | Oct 31, 2023 |
| HP            | 1587h                       | Desktop     | [ecafcd1843](https://linux-hardware.org/?probe=ecafcd1843) | Oct 30, 2023 |
| HP            | EliteBook 645 14 inch G1... | Notebook    | [eb5712ae31](https://linux-hardware.org/?probe=eb5712ae31) | Oct 28, 2023 |
| Dell          | 0TY3YW A03                  | Server      | [8cdd7f67f5](https://linux-hardware.org/?probe=8cdd7f67f5) | Oct 27, 2023 |
| HP            | 8653 A                      | Desktop     | [6d84c59a16](https://linux-hardware.org/?probe=6d84c59a16) | Oct 25, 2023 |
| HP            | 81C7 MVB 0C                 | Server      | [dc0db667dc](https://linux-hardware.org/?probe=dc0db667dc) | Oct 23, 2023 |
| Lenovo        | 31900058 STD                | Desktop     | [b6c589b413](https://linux-hardware.org/?probe=b6c589b413) | Oct 19, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [407b6f9273](https://linux-hardware.org/?probe=407b6f9273) | Oct 15, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [0baddc9010](https://linux-hardware.org/?probe=0baddc9010) | Oct 11, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | Notebook    | [a607943a45](https://linux-hardware.org/?probe=a607943a45) | Oct 03, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [6615883de3](https://linux-hardware.org/?probe=6615883de3) | Oct 03, 2023 |
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

![OS](./images/pie_chart/os_name.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| Rocky Linux 9.1 | 44        | 22.22%  |
| Rocky Linux 8.5 | 32        | 16.16%  |
| Rocky Linux 9.2 | 30        | 15.15%  |
| Rocky Linux 9.0 | 19        | 9.6%    |
| Rocky Linux 8.4 | 19        | 9.6%    |
| Rocky Linux 8.8 | 15        | 7.58%   |
| Rocky Linux 8.7 | 13        | 6.57%   |
| Rocky Linux 9.3 | 12        | 6.06%   |
| Rocky Linux 8.6 | 11        | 5.56%   |
| Rocky Linux 8.3 | 2         | 1.01%   |
| Rocky Linux 8.9 | 1         | 0.51%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Rocky Linux | 194       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                          | Computers | Percent |
|----------------------------------|-----------|---------|
| 5.14.0-162.6.1.el9_1.0.1.x86_64  | 18        | 8.82%   |
| 4.18.0-348.12.2.el8_5.x86_64     | 13        | 6.37%   |
| 5.14.0-284.30.1.el9_2.x86_64     | 10        | 4.9%    |
| 5.14.0-362.8.1.el9_3.x86_64      | 9         | 4.41%   |
| 5.14.0-284.25.1.el9_2.x86_64     | 8         | 3.92%   |
| 5.14.0-162.18.1.el9_1.x86_64     | 8         | 3.92%   |
| 4.18.0-348.7.1.el8_5.x86_64      | 8         | 3.92%   |
| 5.14.0-284.18.1.el9_2.x86_64     | 7         | 3.43%   |
| 4.18.0-477.27.1.el8_8.x86_64     | 7         | 3.43%   |
| 5.14.0-70.26.1.el9_0.x86_64      | 6         | 2.94%   |
| 5.14.0-284.11.1.el9_2.x86_64     | 6         | 2.94%   |
| 4.18.0-305.10.2.el8_4.x86_64     | 6         | 2.94%   |
| 5.14.0-70.22.1.el9_0.x86_64      | 5         | 2.45%   |
| 5.14.0-162.23.1.el9_1.x86_64     | 5         | 2.45%   |
| 5.14.0-162.12.1.el9_1.0.2.x86_64 | 5         | 2.45%   |
| 4.18.0-348.20.1.el8_5.x86_64     | 5         | 2.45%   |
| 5.14.0-70.30.1.el9_0.x86_64      | 4         | 1.96%   |
| 5.14.0-70.17.1.el9_0.x86_64      | 4         | 1.96%   |
| 5.14.0-162.6.1.el9_1.x86_64      | 4         | 1.96%   |
| 4.18.0-477.21.1.el8_8.x86_64     | 3         | 1.47%   |
| 4.18.0-425.3.1.el8.x86_64        | 3         | 1.47%   |
| 4.18.0-425.19.2.el8_7.x86_64     | 3         | 1.47%   |
| 4.18.0-425.13.1.el8_7.x86_64     | 3         | 1.47%   |
| 4.18.0-425.10.1.el8_7.x86_64     | 3         | 1.47%   |
| 4.18.0-372.32.1.el8_6.x86_64     | 3         | 1.47%   |
| 4.18.0-305.25.1.el8_4.x86_64     | 3         | 1.47%   |
| 5.14.0-362.13.1.el9_3.x86_64     | 2         | 0.98%   |
| 5.14.0-162.12.1.el9_1.0.1.x86_64 | 2         | 0.98%   |
| 4.18.0-477.15.1.el8_8.x86_64     | 2         | 0.98%   |
| 4.18.0-477.13.1.el8_8.x86_64     | 2         | 0.98%   |
| 4.18.0-372.9.1.el8.x86_64        | 2         | 0.98%   |
| 4.18.0-372.26.1.el8_6.x86_64     | 2         | 0.98%   |
| 4.18.0-372.19.1.el8_6.x86_64     | 2         | 0.98%   |
| 4.18.0-372.16.1.el8_6.0.1.x86_64 | 2         | 0.98%   |
| 4.18.0-348.2.1.el8_5.x86_64      | 2         | 0.98%   |
| 4.18.0-305.el8.x86_64            | 2         | 0.98%   |
| 4.18.0-305.3.1.el8_4.x86_64      | 2         | 0.98%   |
| 4.18.0-305.19.1.el8_4.x86_64     | 2         | 0.98%   |
| 4.18.0-305.12.1.el8_4.x86_64     | 2         | 0.98%   |
| 4.18.0-240.22.1.el8.x86_64       | 2         | 0.98%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14.0  | 101       | 51.53%  |
| 4.18.0  | 83        | 42.35%  |
| 6.0.10  | 2         | 1.02%   |
| 6.4.12  | 1         | 0.51%   |
| 6.2.12  | 1         | 0.51%   |
| 6.2.10  | 1         | 0.51%   |
| 6.1.8   | 1         | 0.51%   |
| 6.1.6   | 1         | 0.51%   |
| 5.4.157 | 1         | 0.51%   |
| 5.16.15 | 1         | 0.51%   |
| 5.14.1  | 1         | 0.51%   |
| 5.10.89 | 1         | 0.51%   |
| 5.10.52 | 1         | 0.51%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14    | 102       | 52.04%  |
| 4.18    | 83        | 42.35%  |
| 6.2     | 2         | 1.02%   |
| 6.1     | 2         | 1.02%   |
| 6.0     | 2         | 1.02%   |
| 5.10    | 2         | 1.02%   |
| 6.4     | 1         | 0.51%   |
| 5.4     | 1         | 0.51%   |
| 5.16    | 1         | 0.51%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 193       | 99.48%  |
| aarch64 | 1         | 0.52%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 133       | 68.56%  |
| Unknown       | 24        | 12.37%  |
| KDE5          | 14        | 7.22%   |
| MATE          | 9         | 4.64%   |
| XFCE          | 5         | 2.58%   |
| GNOME Classic | 5         | 2.58%   |
| X-Cinnamon    | 3         | 1.55%   |
| Cinnamon      | 1         | 0.52%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 102       | 51.52%  |
| X11     | 71        | 35.86%  |
| Unknown | 12        | 6.06%   |
| Tty     | 10        | 5.05%   |
| Web     | 3         | 1.52%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GDM     | 87        | 44.85%  |
| Unknown | 87        | 44.85%  |
| SDDM    | 10        | 5.15%   |
| LightDM | 10        | 5.15%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 126       | 64.95%  |
| en_CA   | 7         | 3.61%   |
| ru_RU   | 6         | 3.09%   |
| en_AU   | 6         | 3.09%   |
| C       | 4         | 2.06%   |
| Unknown | 4         | 2.06%   |
| pt_BR   | 3         | 1.55%   |
| es_ES   | 3         | 1.55%   |
| en_ZA   | 3         | 1.55%   |
| en_IL   | 3         | 1.55%   |
| en_GB   | 3         | 1.55%   |
| de_DE   | 3         | 1.55%   |
| ko_KR   | 2         | 1.03%   |
| it_IT   | 2         | 1.03%   |
| en_SG   | 2         | 1.03%   |
| en_IE   | 2         | 1.03%   |
| de_AT   | 2         | 1.03%   |
| zh_TW   | 1         | 0.52%   |
| zh_CN   | 1         | 0.52%   |
| pl_PL   | 1         | 0.52%   |
| nl_NL   | 1         | 0.52%   |
| ja_JP   | 1         | 0.52%   |
| hu_HU   | 1         | 0.52%   |
| fr_FR   | 1         | 0.52%   |
| es_CO   | 1         | 0.52%   |
| es_AR   | 1         | 0.52%   |
| en_NZ   | 1         | 0.52%   |
| en_IN   | 1         | 0.52%   |
| ca_ES   | 1         | 0.52%   |
| af_ZA   | 1         | 0.52%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 135       | 69.23%  |
| BIOS | 60        | 30.77%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Xfs  | 163       | 84.02%  |
| Ext4 | 30        | 15.46%  |
| Ext3 | 1         | 0.52%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 107       | 55.15%  |
| Unknown | 61        | 31.44%  |
| MBR     | 26        | 13.4%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 159       | 81.96%  |
| Yes       | 35        | 18.04%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 162       | 83.51%  |
| Yes       | 32        | 16.49%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 37        | 19.07%  |
| Dell                    | 36        | 18.56%  |
| Hewlett-Packard         | 33        | 17.01%  |
| ASUSTek Computer        | 28        | 14.43%  |
| Gigabyte Technology     | 11        | 5.67%   |
| MSI                     | 8         | 4.12%   |
| ASRock                  | 5         | 2.58%   |
| Intel                   | 4         | 2.06%   |
| AZW                     | 4         | 2.06%   |
| Supermicro              | 3         | 1.55%   |
| Unknown                 | 3         | 1.55%   |
| Toshiba                 | 2         | 1.03%   |
| Positivo                | 2         | 1.03%   |
| Acer                    | 2         | 1.03%   |
| Techvision              | 1         | 0.52%   |
| System76                | 1         | 0.52%   |
| Sapphire                | 1         | 0.52%   |
| Raspberry Pi Foundation | 1         | 0.52%   |
| Pegatron                | 1         | 0.52%   |
| NCR                     | 1         | 0.52%   |
| IBM                     | 1         | 0.52%   |
| HUAWEI                  | 1         | 0.52%   |
| HPE                     | 1         | 0.52%   |
| Google                  | 1         | 0.52%   |
| Clevo                   | 1         | 0.52%   |
| BESSTAR Tech            | 1         | 0.52%   |
| Beelink                 | 1         | 0.52%   |
| BANGHO                  | 1         | 0.52%   |
| ATOPNUC                 | 1         | 0.52%   |
| Apple                   | 1         | 0.52%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Dell PowerEdge R610                      | 3         | 1.55%   |
| Unknown                                  | 3         | 1.55%   |
| HP Z210 Workstation                      | 2         | 1.03%   |
| HP EliteBook 840 G5                      | 2         | 1.03%   |
| Dell OptiPlex 9020                       | 2         | 1.03%   |
| AZW GTR                                  | 2         | 1.03%   |
| Toshiba TECRA W50-A                      | 1         | 0.52%   |
| Toshiba Satellite E45-B                  | 1         | 0.52%   |
| Techvision TVI7309X                      | 1         | 0.52%   |
| System76 Thelio Mira                     | 1         | 0.52%   |
| Supermicro SYS-6019U-TN4R4T              | 1         | 0.52%   |
| Supermicro SYS-5029P-WTR                 | 1         | 0.52%   |
| Supermicro Super Server                  | 1         | 0.52%   |
| Sapphire PE-AM2RS690V2                   | 1         | 0.52%   |
| RPi Raspberry Pi                         | 1         | 0.52%   |
| Positivo Q464C                           | 1         | 0.52%   |
| Positivo Mobile                          | 1         | 0.52%   |
| Pegatron IPMIP-GS                        | 1         | 0.52%   |
| NCR xxxx-xxxx-xxxx                       | 1         | 0.52%   |
| MSI MS-7D78                              | 1         | 0.52%   |
| MSI MS-7D46                              | 1         | 0.52%   |
| MSI MS-7D25                              | 1         | 0.52%   |
| MSI MS-7B89                              | 1         | 0.52%   |
| MSI MS-7B78                              | 1         | 0.52%   |
| MSI MS-7A94                              | 1         | 0.52%   |
| MSI MS-7917                              | 1         | 0.52%   |
| MSI H510M PRO-E                          | 1         | 0.52%   |
| Lenovo Yoga 720-13IKB 80X6               | 1         | 0.52%   |
| Lenovo ThinkStation P620 30E0S0PR00      | 1         | 0.52%   |
| Lenovo ThinkStation P340 30DK000CUS      | 1         | 0.52%   |
| Lenovo ThinkPad X270 20HMS79Q00          | 1         | 0.52%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BTS1V900 | 1         | 0.52%   |
| Lenovo ThinkPad X1 Carbon 344835U        | 1         | 0.52%   |
| Lenovo ThinkPad W540 20BGCTO1WW          | 1         | 0.52%   |
| Lenovo ThinkPad W500 406132G             | 1         | 0.52%   |
| Lenovo ThinkPad T480 20L6S8B500          | 1         | 0.52%   |
| Lenovo ThinkPad T430u 86147MG            | 1         | 0.52%   |
| Lenovo ThinkPad T430 2347FF9             | 1         | 0.52%   |
| Lenovo ThinkPad T420 42365H1             | 1         | 0.52%   |
| Lenovo ThinkPad T14s Gen 3 21BR000QUS    | 1         | 0.52%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Lenovo ThinkPad             | 17        | 8.76%   |
| ASUS PRIME                  | 10        | 5.15%   |
| Lenovo IdeaPad              | 8         | 4.12%   |
| Dell PowerEdge              | 7         | 3.61%   |
| HP EliteBook                | 6         | 3.09%   |
| Dell Precision              | 6         | 3.09%   |
| Dell OptiPlex               | 6         | 3.09%   |
| Dell XPS                    | 5         | 2.58%   |
| Dell Latitude               | 5         | 2.58%   |
| HP ZBook                    | 4         | 2.06%   |
| HP Laptop                   | 4         | 2.06%   |
| Dell Vostro                 | 4         | 2.06%   |
| HP EliteDesk                | 3         | 1.55%   |
| Dell Inspiron               | 3         | 1.55%   |
| ASUS ROG                    | 3         | 1.55%   |
| ASUS ASUS                   | 3         | 1.55%   |
| Unknown                     | 3         | 1.55%   |
| Lenovo ThinkStation         | 2         | 1.03%   |
| Lenovo ThinkCentre          | 2         | 1.03%   |
| Lenovo Legion               | 2         | 1.03%   |
| Lenovo IdeaPadFlex          | 2         | 1.03%   |
| HP Z210                     | 2         | 1.03%   |
| HP ProLiant                 | 2         | 1.03%   |
| HP ProBook                  | 2         | 1.03%   |
| HP ENVY                     | 2         | 1.03%   |
| AZW GTR                     | 2         | 1.03%   |
| Acer Aspire                 | 2         | 1.03%   |
| Toshiba TECRA               | 1         | 0.52%   |
| Toshiba Satellite           | 1         | 0.52%   |
| Techvision TVI7309X         | 1         | 0.52%   |
| System76 Thelio             | 1         | 0.52%   |
| Supermicro SYS-6019U-TN4R4T | 1         | 0.52%   |
| Supermicro SYS-5029P-WTR    | 1         | 0.52%   |
| Supermicro Super            | 1         | 0.52%   |
| Sapphire PE-AM2RS690V2      | 1         | 0.52%   |
| RPi Raspberry               | 1         | 0.52%   |
| Positivo Q464C              | 1         | 0.52%   |
| Positivo Mobile             | 1         | 0.52%   |
| Pegatron IPMIP-GS           | 1         | 0.52%   |
| NCR xxxx-xxxx-xxxx          | 1         | 0.52%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2022    | 28        | 14.43%  |
| 2021    | 25        | 12.89%  |
| 2020    | 23        | 11.86%  |
| 2018    | 21        | 10.82%  |
| 2011    | 14        | 7.22%   |
| 2019    | 13        | 6.7%    |
| 2013    | 12        | 6.19%   |
| 2012    | 11        | 5.67%   |
| 2014    | 10        | 5.15%   |
| 2017    | 9         | 4.64%   |
| 2015    | 9         | 4.64%   |
| 2010    | 6         | 3.09%   |
| 2009    | 4         | 2.06%   |
| 2023    | 3         | 1.55%   |
| 2008    | 3         | 1.55%   |
| 2016    | 2         | 1.03%   |
| Unknown | 1         | 0.52%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 82        | 42.27%  |
| Notebook       | 79        | 40.72%  |
| Server         | 17        | 8.76%   |
| Mini pc        | 8         | 4.12%   |
| Convertible    | 6         | 3.09%   |
| System on chip | 1         | 0.52%   |
| Tablet         | 1         | 0.52%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 167       | 86.08%  |
| Enabled  | 27        | 13.92%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 193       | 99.48%  |
| Yes  | 1         | 0.52%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 47        | 24.1%   |
| 4.01-8.0        | 40        | 20.51%  |
| 32.01-64.0      | 35        | 17.95%  |
| 64.01-256.0     | 21        | 10.77%  |
| 16.01-24.0      | 20        | 10.26%  |
| 3.01-4.0        | 12        | 6.15%   |
| 24.01-32.0      | 8         | 4.1%    |
| More than 256.0 | 5         | 2.56%   |
| 1.01-2.0        | 4         | 2.05%   |
| 2.01-3.0        | 3         | 1.54%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 56        | 27.45%  |
| 2.01-3.0   | 48        | 23.53%  |
| 3.01-4.0   | 37        | 18.14%  |
| 1.01-2.0   | 27        | 13.24%  |
| 8.01-16.0  | 15        | 7.35%   |
| 0.51-1.0   | 11        | 5.39%   |
| 16.01-24.0 | 4         | 1.96%   |
| 32.01-64.0 | 2         | 0.98%   |
| 24.01-32.0 | 2         | 0.98%   |
| 0.01-0.5   | 2         | 0.98%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 116       | 59.18%  |
| 2      | 34        | 17.35%  |
| 3      | 17        | 8.67%   |
| 4      | 15        | 7.65%   |
| 6      | 4         | 2.04%   |
| 5      | 3         | 1.53%   |
| 19     | 1         | 0.51%   |
| 18     | 1         | 0.51%   |
| 17     | 1         | 0.51%   |
| 16     | 1         | 0.51%   |
| 14     | 1         | 0.51%   |
| 9      | 1         | 0.51%   |
| 8      | 1         | 0.51%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 143       | 73.71%  |
| Yes       | 51        | 26.29%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 174       | 89.23%  |
| No        | 21        | 10.77%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 121       | 62.05%  |
| No        | 74        | 37.95%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 107       | 54.87%  |
| No        | 88        | 45.13%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 63        | 32.47%  |
| Canada       | 10        | 5.15%   |
| Russia       | 9         | 4.64%   |
| Germany      | 9         | 4.64%   |
| Italy        | 7         | 3.61%   |
| Australia    | 7         | 3.61%   |
| UK           | 5         | 2.58%   |
| Spain        | 5         | 2.58%   |
| Netherlands  | 5         | 2.58%   |
| South Africa | 4         | 2.06%   |
| Singapore    | 4         | 2.06%   |
| Poland       | 4         | 2.06%   |
| Czechia      | 4         | 2.06%   |
| Brazil       | 4         | 2.06%   |
| South Korea  | 3         | 1.55%   |
| Mexico       | 3         | 1.55%   |
| Israel       | 3         | 1.55%   |
| India        | 3         | 1.55%   |
| Hungary      | 3         | 1.55%   |
| France       | 3         | 1.55%   |
| Argentina    | 3         | 1.55%   |
| Sweden       | 2         | 1.03%   |
| Norway       | 2         | 1.03%   |
| Ireland      | 2         | 1.03%   |
| Indonesia    | 2         | 1.03%   |
| Belgium      | 2         | 1.03%   |
| Austria      | 2         | 1.03%   |
| Uzbekistan   | 1         | 0.52%   |
| UAE          | 1         | 0.52%   |
| Turkey       | 1         | 0.52%   |
| Taiwan       | 1         | 0.52%   |
| Switzerland  | 1         | 0.52%   |
| Slovakia     | 1         | 0.52%   |
| Saudi Arabia | 1         | 0.52%   |
| Portugal     | 1         | 0.52%   |
| Pakistan     | 1         | 0.52%   |
| New Zealand  | 1         | 0.52%   |
| Malaysia     | 1         | 0.52%   |
| Kenya        | 1         | 0.52%   |
| Kazakhstan   | 1         | 0.52%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Melbourne     | 5         | 2.56%   |
| Singapore     | 4         | 2.05%   |
| Toronto       | 3         | 1.54%   |
| Moscow        | 3         | 1.54%   |
| Budapest      | 3         | 1.54%   |
| Vienna        | 2         | 1.03%   |
| Prague        | 2         | 1.03%   |
| Philadelphia  | 2         | 1.03%   |
| Oslo          | 2         | 1.03%   |
| Krakow        | 2         | 1.03%   |
| Haifa         | 2         | 1.03%   |
| Enschede      | 2         | 1.03%   |
| Chicago       | 2         | 1.03%   |
| Centurion     | 2         | 1.03%   |
| Buckley       | 2         | 1.03%   |
| Berlin        | 2         | 1.03%   |
| Albuquerque   | 2         | 1.03%   |
| Adelaide      | 2         | 1.03%   |
| Žilina       | 1         | 0.51%   |
| Yogyakarta    | 1         | 0.51%   |
| Yekaterinburg | 1         | 0.51%   |
| Xi'an         | 1         | 0.51%   |
| Woking        | 1         | 0.51%   |
| Willowbrook   | 1         | 0.51%   |
| Westerville   | 1         | 0.51%   |
| Wells         | 1         | 0.51%   |
| Washington    | 1         | 0.51%   |
| Waltham       | 1         | 0.51%   |
| Walnut Creek  | 1         | 0.51%   |
| Wake Forest   | 1         | 0.51%   |
| Voronezh      | 1         | 0.51%   |
| Viggiù       | 1         | 0.51%   |
| Vashon        | 1         | 0.51%   |
| Vancouver     | 1         | 0.51%   |
| Urbana        | 1         | 0.51%   |
| Turin         | 1         | 0.51%   |
| Troisdorf     | 1         | 0.51%   |
| Tower Hamlets | 1         | 0.51%   |
| Torrington    | 1         | 0.51%   |
| Tlaxcala City | 1         | 0.51%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 54        | 75     | 18.95%  |
| Seagate                     | 38        | 103    | 13.33%  |
| WDC                         | 32        | 59     | 11.23%  |
| SanDisk                     | 17        | 19     | 5.96%   |
| Toshiba                     | 16        | 19     | 5.61%   |
| Intel                       | 12        | 17     | 4.21%   |
| Micron Technology           | 10        | 10     | 3.51%   |
| Kingston                    | 10        | 10     | 3.51%   |
| Hitachi                     | 9         | 14     | 3.16%   |
| Crucial                     | 9         | 10     | 3.16%   |
| Unknown                     | 8         | 10     | 2.81%   |
| SK hynix                    | 8         | 10     | 2.81%   |
| PNY                         | 3         | 4      | 1.05%   |
| Phison                      | 3         | 4      | 1.05%   |
| Micron/Crucial Technology   | 3         | 4      | 1.05%   |
| MAXIO Technology (Hangzhou) | 3         | 4      | 1.05%   |
| HGST                        | 3         | 3      | 1.05%   |
| A-DATA Technology           | 3         | 3      | 1.05%   |
| LITEONIT                    | 2         | 2      | 0.7%    |
| Lexar                       | 2         | 2      | 0.7%    |
| KIOXIA                      | 2         | 2      | 0.7%    |
| Gigabyte Technology         | 2         | 2      | 0.7%    |
| Dogfish                     | 2         | 2      | 0.7%    |
| Corsair                     | 2         | 2      | 0.7%    |
| China                       | 2         | 2      | 0.7%    |
| Union Memory (Shenzhen)     | 1         | 1      | 0.35%   |
| Union Memory                | 1         | 1      | 0.35%   |
| UMIS                        | 1         | 1      | 0.35%   |
| Team                        | 1         | 1      | 0.35%   |
| StoreJet                    | 1         | 1      | 0.35%   |
| SATADOM-SL                  | 1         | 1      | 0.35%   |
| SABRENT                     | 1         | 1      | 0.35%   |
| Phison Electronics          | 1         | 16     | 0.35%   |
| Patriot                     | 1         | 1      | 0.35%   |
| MyDigitalSSD                | 1         | 1      | 0.35%   |
| Mobius                      | 1         | 2      | 0.35%   |
| LITEON                      | 1         | 1      | 0.35%   |
| KIOXIA-EXCERIA              | 1         | 1      | 0.35%   |
| Kingston Technology Company | 1         | 1      | 0.35%   |
| KingFast                    | 1         | 1      | 0.35%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 8         | 2.46%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 7         | 2.15%   |
| Seagate ST500DM002-1BD142 500GB                     | 4         | 1.23%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 2TB      | 4         | 1.23%   |
| Unknown MMC Card  64GB                              | 3         | 0.92%   |
| Seagate ST300MP0005 304GB                           | 3         | 0.92%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 250GB | 3         | 0.92%   |
| Micron/Crucial P2 NVMe PCIe SSD 4TB                 | 3         | 0.92%   |
| WDC WD5000AAKX-75U6AA0 500GB                        | 2         | 0.62%   |
| WDC WD2002FAEX-007BA0 2TB                           | 2         | 0.62%   |
| WDC WD Blue SA510 M.2 2280 1000GB                   | 2         | 0.62%   |
| Seagate ST9320325AS 320GB                           | 2         | 0.62%   |
| Seagate ST4000DM004-2CV104 4TB                      | 2         | 0.62%   |
| Seagate ST2000DM008-2FR102 2TB                      | 2         | 0.62%   |
| Seagate ST1000DM010-2EP102 1TB                      | 2         | 0.62%   |
| Samsung SSD 980 1TB                                 | 2         | 0.62%   |
| Samsung SSD 870 EVO 1TB                             | 2         | 0.62%   |
| Samsung SSD 860 EVO 1TB                             | 2         | 0.62%   |
| PNY CS900 240GB SSD                                 | 2         | 0.62%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 256GB  | 2         | 0.62%   |
| Lexar 512GB SSD                                     | 2         | 0.62%   |
| Kingston SA400S37120G 120GB SSD                     | 2         | 0.62%   |
| Intel SSD 660P Series 1TB                           | 2         | 0.62%   |
| Gigabyte GP-GSTFS31240GNTD 240GB                    | 2         | 0.62%   |
| Crucial CT240BX500SSD1 240GB                        | 2         | 0.62%   |
| Crucial CT1000MX500SSD1 1TB                         | 2         | 0.62%   |
| A-DATA SWORDFISH 1TB                                | 2         | 0.62%   |
| WDC WDS500G1R0A-68A4W0 500GB SSD                    | 1         | 0.31%   |
| WDC WDS480G2G0A-00JH30 480GB SSD                    | 1         | 0.31%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD                    | 1         | 0.31%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 1         | 0.31%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 1         | 0.31%   |
| WDC WDS100T1X0E-00AFY0 1TB                          | 1         | 0.31%   |
| WDC WDS100T1R0A-68A4W0 1TB SSD                      | 1         | 0.31%   |
| WDC WDBNCE0010PNC 1TB SSD                           | 1         | 0.31%   |
| WDC WD80EZZX-11CSGA0 8TB                            | 1         | 0.31%   |
| WDC WD80EMAZ-00WJTA0 8TB                            | 1         | 0.31%   |
| WDC WD80EDAZ-11TA3A0 8TB                            | 1         | 0.31%   |
| WDC WD60EFAX-68JH4N1 6TB                            | 1         | 0.31%   |
| WDC WD5003ABYX-18WERA0 500GB                        | 1         | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 38        | 103    | 41.3%   |
| WDC                 | 24        | 45     | 26.09%  |
| Hitachi             | 9         | 14     | 9.78%   |
| Toshiba             | 8         | 10     | 8.7%    |
| Samsung Electronics | 3         | 4      | 3.26%   |
| Unknown             | 2         | 2      | 2.17%   |
| HGST                | 2         | 2      | 2.17%   |
| StoreJet            | 1         | 1      | 1.09%   |
| SABRENT             | 1         | 1      | 1.09%   |
| Mobius              | 1         | 2      | 1.09%   |
| IBM                 | 1         | 1      | 1.09%   |
| Fujitsu             | 1         | 1      | 1.09%   |
| DELLBOSS            | 1         | 1      | 1.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 20        | 25     | 21.98%  |
| SanDisk             | 9         | 10     | 9.89%   |
| WDC                 | 8         | 11     | 8.79%   |
| Crucial             | 8         | 9      | 8.79%   |
| Kingston            | 6         | 6      | 6.59%   |
| Toshiba             | 5         | 5      | 5.49%   |
| PNY                 | 3         | 4      | 3.3%    |
| Micron Technology   | 3         | 3      | 3.3%    |
| Intel               | 3         | 4      | 3.3%    |
| SK hynix            | 2         | 2      | 2.2%    |
| LITEONIT            | 2         | 2      | 2.2%    |
| Gigabyte Technology | 2         | 2      | 2.2%    |
| Dogfish             | 2         | 2      | 2.2%    |
| China               | 2         | 2      | 2.2%    |
| Team                | 1         | 1      | 1.1%    |
| SATADOM-SL          | 1         | 1      | 1.1%    |
| Patriot             | 1         | 1      | 1.1%    |
| MyDigitalSSD        | 1         | 1      | 1.1%    |
| LITEON              | 1         | 1      | 1.1%    |
| Lexar               | 1         | 1      | 1.1%    |
| KingFast            | 1         | 1      | 1.1%    |
| INDMEM              | 1         | 1      | 1.1%    |
| GOODRAM             | 1         | 1      | 1.1%    |
| DUEX-120GB          | 1         | 1      | 1.1%    |
| Digma               | 1         | 1      | 1.1%    |
| Corsair             | 1         | 1      | 1.1%    |
| ASMT                | 1         | 1      | 1.1%    |
| Apacer              | 1         | 1      | 1.1%    |
| ADATA SU            | 1         | 1      | 1.1%    |
| A-DATA Technology   | 1         | 1      | 1.1%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 93        | 136    | 36.9%   |
| SSD     | 78        | 103    | 30.95%  |
| HDD     | 71        | 187    | 28.17%  |
| MMC     | 5         | 5      | 1.98%   |
| Unknown | 5         | 7      | 1.98%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 122       | 275    | 51.91%  |
| NVMe | 93        | 136    | 39.57%  |
| SAS  | 15        | 22     | 6.38%   |
| MMC  | 5         | 5      | 2.13%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 75        | 114    | 46.58%  |
| 0.51-1.0   | 45        | 86     | 27.95%  |
| 1.01-2.0   | 21        | 36     | 13.04%  |
| 3.01-4.0   | 11        | 31     | 6.83%   |
| 4.01-10.0  | 4         | 16     | 2.48%   |
| 2.01-3.0   | 2         | 2      | 1.24%   |
| 10.01-20.0 | 2         | 3      | 1.24%   |
| 20.01-50.0 | 1         | 2      | 0.62%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 55        | 28.06%  |
| 251-500        | 41        | 20.92%  |
| 501-1000       | 34        | 17.35%  |
| 1001-2000      | 22        | 11.22%  |
| More than 3000 | 19        | 9.69%   |
| 51-100         | 9         | 4.59%   |
| 2001-3000      | 7         | 3.57%   |
| Unknown        | 5         | 2.55%   |
| 1-20           | 3         | 1.53%   |
| 21-50          | 1         | 0.51%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 70        | 35%     |
| 21-50          | 43        | 21.5%   |
| 51-100         | 25        | 12.5%   |
| 101-250        | 19        | 9.5%    |
| 501-1000       | 12        | 6%      |
| 251-500        | 10        | 5%      |
| More than 3000 | 8         | 4%      |
| 1001-2000      | 5         | 2.5%    |
| Unknown        | 5         | 2.5%    |
| 2001-3000      | 3         | 1.5%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD5000AAKX-75U6AA0 500GB          | 1         | 1      | 5.26%   |
| WDC WD40EZRZ-00WN9B0 4TB              | 1         | 1      | 5.26%   |
| WDC WD40 EFRX-68N32N0 4TB             | 1         | 1      | 5.26%   |
| WDC WD1001FALS-00J7B1 1TB             | 1         | 2      | 5.26%   |
| WDC WD1001FALS-00J7B0 1TB             | 1         | 4      | 5.26%   |
| Toshiba MK1059GSM 1TB                 | 1         | 1      | 5.26%   |
| Seagate ST9500325AS 500GB             | 1         | 1      | 5.26%   |
| Seagate ST9320325AS 320GB             | 1         | 1      | 5.26%   |
| Seagate ST8000AS0002-1NA17Z 8TB       | 1         | 1      | 5.26%   |
| Seagate ST4000NM0033-9ZM170 4TB       | 1         | 10     | 5.26%   |
| Seagate ST31000528AS 1TB              | 1         | 2      | 5.26%   |
| Seagate ST2000DM008-2FR102 2TB        | 1         | 2      | 5.26%   |
| Intel SSD 600P Series 128GB           | 1         | 2      | 5.26%   |
| IBM ST3500641NS 39M4517 39M0181 500GB | 1         | 1      | 5.26%   |
| Hitachi HTS727575A9E364 752GB         | 1         | 1      | 5.26%   |
| Hitachi HDS725050KLA360 500GB         | 1         | 1      | 5.26%   |
| Hitachi HDS721010CLA632 1TB           | 1         | 1      | 5.26%   |
| Crucial CT1050MX300SSD1 1TB           | 1         | 1      | 5.26%   |
| Corsair Neutron SSD 64GB              | 1         | 1      | 5.26%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 17     | 31.58%  |
| WDC     | 5         | 9      | 26.32%  |
| Hitachi | 3         | 3      | 15.79%  |
| Toshiba | 1         | 1      | 5.26%   |
| Intel   | 1         | 2      | 5.26%   |
| IBM     | 1         | 1      | 5.26%   |
| Crucial | 1         | 1      | 5.26%   |
| Corsair | 1         | 1      | 5.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


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

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 14        | 31     | 82.35%  |
| SSD  | 2         | 2      | 11.76%  |
| NVMe | 1         | 2      | 5.88%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST9500420AS 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 125       | 282    | 57.34%  |
| Detected | 76        | 120    | 34.86%  |
| Malfunc  | 16        | 35     | 7.34%   |
| Failed   | 1         | 1      | 0.46%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 122       | 44.53%  |
| AMD                          | 40        | 14.6%   |
| Samsung Electronics          | 35        | 12.77%  |
| SanDisk                      | 10        | 3.65%   |
| Micron Technology            | 7         | 2.55%   |
| LSI Logic / Symbios Logic    | 7         | 2.55%   |
| SK hynix                     | 6         | 2.19%   |
| Phison Electronics           | 5         | 1.82%   |
| Kingston Technology Company  | 5         | 1.82%   |
| Broadcom / LSI               | 5         | 1.82%   |
| ASMedia Technology           | 5         | 1.82%   |
| Micron/Crucial Technology    | 4         | 1.46%   |
| Toshiba America Info Systems | 3         | 1.09%   |
| MAXIO Technology (Hangzhou)  | 3         | 1.09%   |
| KIOXIA                       | 3         | 1.09%   |
| Union Memory (Shenzhen)      | 2         | 0.73%   |
| Realtek Semiconductor        | 2         | 0.73%   |
| Marvell Technology Group     | 2         | 0.73%   |
| Hewlett-Packard              | 2         | 0.73%   |
| VIA Technologies             | 1         | 0.36%   |
| Silicon Motion               | 1         | 0.36%   |
| Shenzhen Longsys Electronics | 1         | 0.36%   |
| JMicron Technology           | 1         | 0.36%   |
| ADATA Technology             | 1         | 0.36%   |
| Adaptec                      | 1         | 0.36%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 28        | 8.83%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 15        | 4.73%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 11        | 3.47%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 9         | 2.84%   |
| Intel SATA Controller [RAID mode]                                                       | 7         | 2.21%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 6         | 1.89%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 6         | 1.89%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 6         | 1.89%   |
| AMD 400 Series Chipset SATA Controller                                                  | 6         | 1.89%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 5         | 1.58%   |
| Micron 3400 NVMe SSD [Hendrix]                                                          | 5         | 1.58%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 5         | 1.58%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5         | 1.58%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5         | 1.58%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 4         | 1.26%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 4         | 1.26%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 4         | 1.26%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                           | 4         | 1.26%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                            | 4         | 1.26%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 4         | 1.26%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 4         | 1.26%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4         | 1.26%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 3         | 0.95%   |
| LSI Logic / Symbios Logic MegaRAID SAS 1078                                             | 3         | 0.95%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 3         | 0.95%   |
| Intel SSD 670p Series [Keystone Harbor]                                                 | 3         | 0.95%   |
| Intel SSD 660P Series                                                                   | 3         | 0.95%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 3         | 0.95%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 3         | 0.95%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 3         | 0.95%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 3         | 0.95%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 3         | 0.95%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 3         | 0.95%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3         | 0.95%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3         | 0.95%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 3         | 0.95%   |
| AMD 500 Series Chipset SATA Controller                                                  | 3         | 0.95%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 2         | 0.63%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                                      | 2         | 0.63%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 2         | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 119       | 42.96%  |
| NVMe | 93        | 33.57%  |
| RAID | 29        | 10.47%  |
| IDE  | 28        | 10.11%  |
| SAS  | 6         | 2.17%   |
| SCSI | 2         | 0.72%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 144       | 74.23%  |
| AMD    | 49        | 25.26%  |
| ARM    | 1         | 0.52%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-2600 CPU @ 3.40GHz            | 4         | 2.06%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 4         | 2.06%   |
| Intel Xeon CPU L5530 @ 2.40GHz              | 3         | 1.55%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 3         | 1.55%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 3         | 1.55%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 3         | 1.55%   |
| Intel 12th Gen Core i7-1260P                | 3         | 1.55%   |
| Intel Xeon Gold 6130 CPU @ 2.10GHz          | 2         | 1.03%   |
| Intel Xeon CPU E5-2665 0 @ 2.40GHz          | 2         | 1.03%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 2         | 1.03%   |
| Intel Core i7-10610U CPU @ 1.80GHz          | 2         | 1.03%   |
| Intel Core i5-8350U CPU @ 1.70GHz           | 2         | 1.03%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 1.03%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 2         | 1.03%   |
| Intel 12th Gen Core i7-12700H               | 2         | 1.03%   |
| Intel 12th Gen Core i5-12400F               | 2         | 1.03%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz     | 2         | 1.03%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz      | 2         | 1.03%   |
| AMD FX-8350 Eight-Core Processor            | 2         | 1.03%   |
| Intel Xeon Silver 4216 CPU @ 2.10GHz        | 1         | 0.52%   |
| Intel Xeon Platinum 8124M CPU @ 3.00GHz     | 1         | 0.52%   |
| Intel Xeon Gold 6338 CPU @ 2.00GHz          | 1         | 0.52%   |
| Intel Xeon Gold 6134 CPU @ 3.20GHz          | 1         | 0.52%   |
| Intel Xeon E-2244G CPU @ 3.80GHz            | 1         | 0.52%   |
| Intel Xeon CPU X5680 @ 3.33GHz              | 1         | 0.52%   |
| Intel Xeon CPU X5670 @ 2.93GHz              | 1         | 0.52%   |
| Intel Xeon CPU E5620 @ 2.40GHz              | 1         | 0.52%   |
| Intel Xeon CPU E5-2687W v2 @ 3.40GHz        | 1         | 0.52%   |
| Intel Xeon CPU E5-2680 v4 @ 2.40GHz         | 1         | 0.52%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz         | 1         | 0.52%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz         | 1         | 0.52%   |
| Intel Xeon CPU E5-2620 0 @ 2.00GHz          | 1         | 0.52%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz          | 1         | 0.52%   |
| Intel Xeon CPU E31230 @ 3.20GHz             | 1         | 0.52%   |
| Intel Xeon CPU E3110 @ 3.00GHz              | 1         | 0.52%   |
| Intel Xeon CPU E3-1245 v5 @ 3.50GHz         | 1         | 0.52%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GHz         | 1         | 0.52%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 0.52%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1         | 0.52%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1         | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 42        | 21.65%  |
| Other                   | 31        | 15.98%  |
| Intel Core i5           | 27        | 13.92%  |
| Intel Xeon              | 19        | 9.79%   |
| AMD Ryzen 7             | 9         | 4.64%   |
| AMD Ryzen 9             | 8         | 4.12%   |
| AMD Ryzen 5             | 8         | 4.12%   |
| Intel Celeron           | 7         | 3.61%   |
| Intel Core i3           | 6         | 3.09%   |
| Intel Xeon Gold         | 4         | 2.06%   |
| AMD Ryzen 5 PRO         | 4         | 2.06%   |
| AMD FX                  | 3         | 1.55%   |
| Intel Pentium Dual-Core | 2         | 1.03%   |
| Intel Core i9           | 2         | 1.03%   |
| Intel Atom              | 2         | 1.03%   |
| AMD Ryzen Threadripper  | 2         | 1.03%   |
| AMD Ryzen 3             | 2         | 1.03%   |
| AMD A8                  | 2         | 1.03%   |
| Intel Xeon Silver       | 1         | 0.52%   |
| Intel Xeon Platinum     | 1         | 0.52%   |
| Intel Pentium Silver    | 1         | 0.52%   |
| Intel Pentium Dual      | 1         | 0.52%   |
| Intel Core 2 Quad       | 1         | 0.52%   |
| Intel Core 2 Duo        | 1         | 0.52%   |
| AMD Sempron             | 1         | 0.52%   |
| AMD Ryzen Embedded      | 1         | 0.52%   |
| AMD Ryzen 7 PRO         | 1         | 0.52%   |
| AMD Phenom II X6        | 1         | 0.52%   |
| AMD EPYC                | 1         | 0.52%   |
| AMD Athlon II X2        | 1         | 0.52%   |
| AMD A4                  | 1         | 0.52%   |
| AMD A10                 | 1         | 0.52%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 72        | 37.11%  |
| 2      | 38        | 19.59%  |
| 6      | 26        | 13.4%   |
| 8      | 23        | 11.86%  |
| 12     | 10        | 5.15%   |
| 10     | 8         | 4.12%   |
| 16     | 6         | 3.09%   |
| 32     | 2         | 1.03%   |
| 24     | 2         | 1.03%   |
| 14     | 2         | 1.03%   |
| 64     | 1         | 0.52%   |
| 36     | 1         | 0.52%   |
| 28     | 1         | 0.52%   |
| 3      | 1         | 0.52%   |
| 1      | 1         | 0.52%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 179       | 92.27%  |
| 2      | 15        | 7.73%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 149       | 76.41%  |
| 1      | 46        | 23.59%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 194       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 16        | 8.21%   |
| 0x306c3    | 12        | 6.15%   |
| 0x206a7    | 10        | 5.13%   |
| 0x806c1    | 8         | 4.1%    |
| 0x306a9    | 8         | 4.1%    |
| 0x806ea    | 7         | 3.59%   |
| 0x506e3    | 7         | 3.59%   |
| 0x806ec    | 6         | 3.08%   |
| 0x50654    | 5         | 2.56%   |
| 0x0a50000c | 5         | 2.56%   |
| 0xa0652    | 4         | 2.05%   |
| 0x906a3    | 4         | 2.05%   |
| 0x906ea    | 3         | 1.54%   |
| 0x806e9    | 3         | 1.54%   |
| 0x706a8    | 3         | 1.54%   |
| 0x206d7    | 3         | 1.54%   |
| 0x206c2    | 3         | 1.54%   |
| 0x0a601203 | 3         | 1.54%   |
| 0xa0671    | 2         | 1.03%   |
| 0xa0655    | 2         | 1.03%   |
| 0xa0653    | 2         | 1.03%   |
| 0x906c0    | 2         | 1.03%   |
| 0x906a4    | 2         | 1.03%   |
| 0x90675    | 2         | 1.03%   |
| 0x90672    | 2         | 1.03%   |
| 0x406f1    | 2         | 1.03%   |
| 0x40651    | 2         | 1.03%   |
| 0x306e4    | 2         | 1.03%   |
| 0x306d4    | 2         | 1.03%   |
| 0x106a5    | 2         | 1.03%   |
| 0x1067a    | 2         | 1.03%   |
| 0x10676    | 2         | 1.03%   |
| 0x0a50000d | 2         | 1.03%   |
| 0x0a404102 | 2         | 1.03%   |
| 0x08608103 | 2         | 1.03%   |
| 0x08600106 | 2         | 1.03%   |
| 0x08600104 | 2         | 1.03%   |
| 0x0800820d | 2         | 1.03%   |
| 0x06006705 | 2         | 1.03%   |
| 0x06001119 | 2         | 1.03%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 21        | 10.82%  |
| Haswell          | 18        | 9.28%   |
| Alderlake Hybrid | 16        | 8.25%   |
| Skylake          | 15        | 7.73%   |
| SandyBridge      | 14        | 7.22%   |
| IvyBridge        | 11        | 5.67%   |
| Unknown          | 11        | 5.67%   |
| Zen 3            | 10        | 5.15%   |
| CometLake        | 9         | 4.64%   |
| Zen 2            | 8         | 4.12%   |
| TigerLake        | 8         | 4.12%   |
| Piledriver       | 6         | 3.09%   |
| Westmere         | 5         | 2.58%   |
| Penryn           | 5         | 2.58%   |
| IceLake          | 5         | 2.58%   |
| Zen+             | 4         | 2.06%   |
| Zen              | 4         | 2.06%   |
| Nehalem          | 4         | 2.06%   |
| Goldmont plus    | 4         | 2.06%   |
| Broadwell        | 4         | 2.06%   |
| K10              | 3         | 1.55%   |
| Tremont          | 2         | 1.03%   |
| Silvermont       | 2         | 1.03%   |
| Excavator        | 2         | 1.03%   |
| K10 Llano        | 1         | 0.52%   |
| Jaguar           | 1         | 0.52%   |
| Core             | 1         | 0.52%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 101       | 42.44%  |
| Nvidia                     | 74        | 31.09%  |
| AMD                        | 48        | 20.17%  |
| Matrox Electronics Systems | 8         | 3.36%   |
| ASPEED Technology          | 7         | 2.94%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 8         | 3.31%   |
| Intel UHD Graphics 620                                                                   | 7         | 2.89%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7         | 2.89%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 7         | 2.89%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 6         | 2.48%   |
| Intel HD Graphics 530                                                                    | 5         | 2.07%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 5         | 2.07%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 2.07%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 5         | 2.07%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 4         | 1.65%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 4         | 1.65%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 4         | 1.65%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 1.65%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 4         | 1.65%   |
| AMD Raphael                                                                              | 4         | 1.65%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 3         | 1.24%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 1.24%   |
| Intel HD Graphics 620                                                                    | 3         | 1.24%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.24%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 1.24%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 3         | 1.24%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 3         | 1.24%   |
| AMD Rembrandt [Radeon 680M]                                                              | 3         | 1.24%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.83%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 2         | 0.83%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 2         | 0.83%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 2         | 0.83%   |
| Nvidia GP107GL [Quadro P400]                                                             | 2         | 0.83%   |
| Nvidia GM108M [GeForce 940M]                                                             | 2         | 0.83%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 2         | 0.83%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                                           | 2         | 0.83%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                                        | 2         | 0.83%   |
| Matrox Electronics Systems G200eR2                                                       | 2         | 0.83%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                                | 2         | 0.83%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 0.83%   |
| Intel JasperLake [UHD Graphics]                                                          | 2         | 0.83%   |
| Intel HD Graphics 5500                                                                   | 2         | 0.83%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 0.83%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 0.83%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 0.83%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 69        | 35.57%  |
| 1 x Nvidia      | 36        | 18.56%  |
| 1 x AMD         | 32        | 16.49%  |
| Intel + Nvidia  | 27        | 13.92%  |
| AMD + Nvidia    | 8         | 4.12%   |
| 1 x Matrox      | 7         | 3.61%   |
| 1 x ASPEED      | 4         | 2.06%   |
| 2 x AMD         | 3         | 1.55%   |
| Intel + AMD     | 3         | 1.55%   |
| AMD + ASPEED    | 2         | 1.03%   |
| Other           | 1         | 0.52%   |
| Nvidia + Matrox | 1         | 0.52%   |
| Nvidia + ASPEED | 1         | 0.52%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 157       | 80.51%  |
| Proprietary | 28        | 14.36%  |
| Unknown     | 10        | 5.13%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 97        | 49.74%  |
| 1.01-2.0   | 24        | 12.31%  |
| 0.01-0.5   | 24        | 12.31%  |
| 3.01-4.0   | 16        | 8.21%   |
| 0.51-1.0   | 14        | 7.18%   |
| 7.01-8.0   | 5         | 2.56%   |
| 8.01-16.0  | 5         | 2.56%   |
| 5.01-6.0   | 4         | 2.05%   |
| 16.01-24.0 | 3         | 1.54%   |
| 2.01-3.0   | 2         | 1.03%   |
| 32.01-64.0 | 1         | 0.51%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 25        | 11.85%  |
| Samsung Electronics     | 23        | 10.9%   |
| Goldstar                | 18        | 8.53%   |
| AU Optronics            | 18        | 8.53%   |
| LG Display              | 17        | 8.06%   |
| BOE                     | 14        | 6.64%   |
| Chimei Innolux          | 11        | 5.21%   |
| Hewlett-Packard         | 8         | 3.79%   |
| Acer                    | 8         | 3.79%   |
| Philips                 | 7         | 3.32%   |
| Sharp                   | 6         | 2.84%   |
| Ancor Communications    | 5         | 2.37%   |
| BenQ                    | 4         | 1.9%    |
| AOC                     | 4         | 1.9%    |
| Lenovo                  | 3         | 1.42%   |
| InfoVision              | 3         | 1.42%   |
| Iiyama                  | 3         | 1.42%   |
| Eizo                    | 3         | 1.42%   |
| ViewSonic               | 2         | 0.95%   |
| Sony                    | 2         | 0.95%   |
| SGT                     | 2         | 0.95%   |
| Sceptre Tech            | 2         | 0.95%   |
| PANDA                   | 2         | 0.95%   |
| CSO                     | 2         | 0.95%   |
| ASUSTek Computer        | 2         | 0.95%   |
| Apple                   | 2         | 0.95%   |
| Xiaomi                  | 1         | 0.47%   |
| Vizio                   | 1         | 0.47%   |
| Panasonic               | 1         | 0.47%   |
| OEM                     | 1         | 0.47%   |
| NEC Computers           | 1         | 0.47%   |
| LG Electronics          | 1         | 0.47%   |
| IBM                     | 1         | 0.47%   |
| HUAWEI                  | 1         | 0.47%   |
| Hitachi                 | 1         | 0.47%   |
| HCL                     | 1         | 0.47%   |
| Gigabyte Technology     | 1         | 0.47%   |
| EDI                     | 1         | 0.47%   |
| Chi Mei Optoelectronics | 1         | 0.47%   |
| ADR                     | 1         | 0.47%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 2         | 0.91%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 0.91%   |
| Goldstar ULTRAWIDE GSM76F6 3440x1440 800x335mm 34.1-inch              | 2         | 0.91%   |
| Goldstar LG ULTRAWIDE GSM76FD 2560x1080 800x340mm 34.2-inch           | 2         | 0.91%   |
| Dell S3422DWG DELD124 3440x1440 797x334mm 34.0-inch                   | 2         | 0.91%   |
| Dell P2317H DEL40F4 1920x1080 509x286mm 23.0-inch                     | 2         | 0.91%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.91%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.91%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch        | 2         | 0.91%   |
| Xiaomi Mi TV XMD00E1 3840x2160 708x398mm 32.0-inch                    | 1         | 0.45%   |
| Vizio E24-C1 VIZ1005 1920x1080 521x293mm 23.5-inch                    | 1         | 0.45%   |
| ViewSonic VS2210-FHD VSC1939 1920x1080 476x268mm 21.5-inch            | 1         | 0.45%   |
| ViewSonic VA902b VSC211C 1280x1024 376x301mm 19.0-inch                | 1         | 0.45%   |
| Sony TV *02 SNY045B 1920x1080 1085x610mm 49.0-inch                    | 1         | 0.45%   |
| Sony LCD Monitor MS_003C 1366x768 309x173mm 13.9-inch                 | 1         | 0.45%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch               | 1         | 0.45%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 1         | 0.45%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 1         | 0.45%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 1         | 0.45%   |
| Sharp LCD Monitor SHP1491 3840x2160 346x194mm 15.6-inch               | 1         | 0.45%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 1         | 0.45%   |
| SGT L156 SGT1560 1366x768 452x254mm 20.4-inch                         | 1         | 0.45%   |
| SGT F156P1 SGT1600 1920x1080 345x194mm 15.6-inch                      | 1         | 0.45%   |
| Sceptre Tech X246W-1080p SPT2303 1920x1080 521x293mm 23.5-inch        | 1         | 0.45%   |
| Sceptre Tech X240-CNC SPT0978 1920x1080 880x490mm 39.7-inch           | 1         | 0.45%   |
| Samsung Electronics U32R59x SAM0F96 3840x2160 700x390mm 31.5-inch     | 1         | 0.45%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch     | 1         | 0.45%   |
| Samsung Electronics SyncMaster SAM062E 1280x1024 376x301mm 19.0-inch  | 1         | 0.45%   |
| Samsung Electronics SyncMaster SAM0564 1360x768 410x230mm 18.5-inch   | 1         | 0.45%   |
| Samsung Electronics SyncMaster SAM0467 1920x1200 518x324mm 24.1-inch  | 1         | 0.45%   |
| Samsung Electronics SyncMaster SAM0215 1280x1024 338x270mm 17.0-inch  | 1         | 0.45%   |
| Samsung Electronics SMS23A350H SAM07D4 1920x1080 509x286mm 23.0-inch  | 1         | 0.45%   |
| Samsung Electronics S34J55x SAM0F71 3440x1440 797x333mm 34.0-inch     | 1         | 0.45%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch     | 1         | 0.45%   |
| Samsung Electronics LF27T450F SAM7099 1920x1080 597x336mm 27.0-inch   | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch  | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SDC416E 2880x1620 344x194mm 15.5-inch | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 344x194mm 15.5-inch  | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SDC3752 1920x1080 344x194mm 15.5-inch | 1         | 0.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 86        | 42.36%  |
| 1366x768 (WXGA)    | 18        | 8.87%   |
| 3840x2160 (4K)     | 14        | 6.9%    |
| 2560x1440 (QHD)    | 13        | 6.4%    |
| 1920x1200 (WUXGA)  | 11        | 5.42%   |
| 1280x1024 (SXGA)   | 11        | 5.42%   |
| 3440x1440          | 8         | 3.94%   |
| 1600x900 (HD+)     | 7         | 3.45%   |
| 2560x1080          | 6         | 2.96%   |
| 3840x1080          | 4         | 1.97%   |
| 1680x1050 (WSXGA+) | 4         | 1.97%   |
| 3840x2400          | 3         | 1.48%   |
| 1024x768 (XGA)     | 3         | 1.48%   |
| Unknown            | 3         | 1.48%   |
| 1920x540           | 2         | 0.99%   |
| 1440x900 (WXGA+)   | 2         | 0.99%   |
| 7680x2160          | 1         | 0.49%   |
| 3072x1920          | 1         | 0.49%   |
| 2880x1800          | 1         | 0.49%   |
| 2880x1620          | 1         | 0.49%   |
| 2240x1400          | 1         | 0.49%   |
| 2160x1440          | 1         | 0.49%   |
| 1360x768           | 1         | 0.49%   |
| 1280x768           | 1         | 0.49%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 39        | 18.31%  |
| 14      | 28        | 13.15%  |
| 27      | 21        | 9.86%   |
| 24      | 19        | 8.92%   |
| 34      | 13        | 6.1%    |
| 23      | 12        | 5.63%   |
| 17      | 12        | 5.63%   |
| 13      | 12        | 5.63%   |
| 31      | 8         | 3.76%   |
| 19      | 8         | 3.76%   |
| 21      | 7         | 3.29%   |
| Unknown | 6         | 2.82%   |
| 20      | 4         | 1.88%   |
| 18      | 4         | 1.88%   |
| 22      | 3         | 1.41%   |
| 65      | 2         | 0.94%   |
| 48      | 2         | 0.94%   |
| 40      | 2         | 0.94%   |
| 16      | 2         | 0.94%   |
| 84      | 1         | 0.47%   |
| 54      | 1         | 0.47%   |
| 49      | 1         | 0.47%   |
| 39      | 1         | 0.47%   |
| 35      | 1         | 0.47%   |
| 32      | 1         | 0.47%   |
| 28      | 1         | 0.47%   |
| 25      | 1         | 0.47%   |
| 12      | 1         | 0.47%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 78        | 36.97%  |
| 501-600     | 49        | 23.22%  |
| 401-500     | 23        | 10.9%   |
| 701-800     | 14        | 6.64%   |
| 351-400     | 13        | 6.16%   |
| 601-700     | 9         | 4.27%   |
| 201-300     | 8         | 3.79%   |
| 1001-1500   | 6         | 2.84%   |
| Unknown     | 6         | 2.84%   |
| 801-900     | 4         | 1.9%    |
| 1501-2000   | 1         | 0.47%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 130       | 68.78%  |
| 16/10   | 21        | 11.11%  |
| 21/9    | 13        | 6.88%   |
| 5/4     | 10        | 5.29%   |
| Unknown | 5         | 2.65%   |
| 4/3     | 3         | 1.59%   |
| 32/9    | 3         | 1.59%   |
| 3/2     | 3         | 1.59%   |
| 6/5     | 1         | 0.53%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 39        | 18.48%  |
| 81-90          | 34        | 16.11%  |
| 201-250        | 34        | 16.11%  |
| 351-500        | 23        | 10.9%   |
| 301-350        | 21        | 9.95%   |
| 151-200        | 13        | 6.16%   |
| 141-150        | 9         | 4.27%   |
| 121-130        | 7         | 3.32%   |
| 501-1000       | 7         | 3.32%   |
| Unknown        | 6         | 2.84%   |
| 251-300        | 5         | 2.37%   |
| More than 1000 | 4         | 1.9%    |
| 71-80          | 3         | 1.42%   |
| 111-120        | 3         | 1.42%   |
| 91-100         | 2         | 0.95%   |
| 61-70          | 1         | 0.47%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 86        | 41.35%  |
| 121-160       | 55        | 26.44%  |
| 101-120       | 34        | 16.35%  |
| 161-240       | 16        | 7.69%   |
| More than 240 | 8         | 3.85%   |
| Unknown       | 6         | 2.88%   |
| 1-50          | 3         | 1.44%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 127       | 65.13%  |
| 2     | 38        | 19.49%  |
| 0     | 25        | 12.82%  |
| 3     | 4         | 2.05%   |
| 4     | 1         | 0.51%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 123       | 41.98%  |
| Realtek Semiconductor     | 88        | 30.03%  |
| Broadcom                  | 16        | 5.46%   |
| MediaTek                  | 12        | 4.1%    |
| Qualcomm Atheros          | 11        | 3.75%   |
| ASIX Electronics          | 6         | 2.05%   |
| Mellanox Technologies     | 5         | 1.71%   |
| Lenovo                    | 4         | 1.37%   |
| Aquantia                  | 4         | 1.37%   |
| Ralink Technology         | 3         | 1.02%   |
| Broadcom Limited          | 3         | 1.02%   |
| Ralink                    | 2         | 0.68%   |
| Marvell Technology Group  | 2         | 0.68%   |
| Linksys                   | 2         | 0.68%   |
| TP-Link                   | 1         | 0.34%   |
| Spreadtrum Communications | 1         | 0.34%   |
| Solarflare Communications | 1         | 0.34%   |
| Qualcomm                  | 1         | 0.34%   |
| Microsoft                 | 1         | 0.34%   |
| JMicron Technology        | 1         | 0.34%   |
| InterBiometrics           | 1         | 0.34%   |
| Dell                      | 1         | 0.34%   |
| D-Link                    | 1         | 0.34%   |
| BUFFALO                   | 1         | 0.34%   |
| ASUSTek Computer          | 1         | 0.34%   |
| American Megatrends       | 1         | 0.34%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                                                  | Computers | Percent |
|------------------------------------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                                                      | 57        | 16.1%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                                               | 14        | 3.95%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                                                  | 11        | 3.11%   |
| Intel Wireless 8265 / 8275                                                                                             | 8         | 2.26%   |
| Intel Wi-Fi 6 AX200                                                                                                    | 8         | 2.26%   |
| Intel Ethernet Controller I225-V                                                                                       | 8         | 2.26%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                                                       | 8         | 2.26%   |
| Realtek RTL8125 2.5GbE Controller                                                                                      | 7         | 1.98%   |
| Intel Ethernet Connection I217-LM                                                                                      | 7         | 1.98%   |
| Intel Wireless 7260                                                                                                    | 6         | 1.69%   |
| Intel Wi-Fi 6 AX201                                                                                                    | 6         | 1.69%   |
| Intel I211 Gigabit Network Connection                                                                                  | 6         | 1.69%   |
| ASIX AX88179 Gigabit Ethernet                                                                                          | 6         | 1.69%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                                                          | 5         | 1.41%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                                                 | 4         | 1.13%   |
| Intel Ethernet Connection (4) I219-LM                                                                                  | 4         | 1.13%   |
| Intel Comet Lake PCH CNVi WiFi                                                                                         | 4         | 1.13%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                                           | 4         | 1.13%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                                                         | 4         | 1.13%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                                                            | 3         | 0.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                                               | 3         | 0.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                                               | 3         | 0.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                                             | 3         | 0.85%   |
| Mellanox MT25408A0-FCC-QI ConnectX, Dual Port 40Gb/s InfiniBand / 10GigE Adapter IC with PCIe 2.0 x8 5.0GT/s Interface | 3         | 0.85%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                                                | 3         | 0.85%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                                          | 3         | 0.85%   |
| Intel Wireless 8260                                                                                                    | 3         | 0.85%   |
| Intel Wireless 7265                                                                                                    | 3         | 0.85%   |
| Intel Wireless 3165                                                                                                    | 3         | 0.85%   |
| Intel I210 Gigabit Network Connection                                                                                  | 3         | 0.85%   |
| Intel Ethernet Connection (4) I219-V                                                                                   | 3         | 0.85%   |
| Intel Ethernet Connection (2) I219-LM                                                                                  | 3         | 0.85%   |
| Intel Ethernet Connection (17) I219-V                                                                                  | 3         | 0.85%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                                                      | 3         | 0.85%   |
| Intel 82574L Gigabit Network Connection                                                                                | 3         | 0.85%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]                                                      | 3         | 0.85%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                                                     | 2         | 0.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                                                  | 2         | 0.56%   |
| Ralink MT7601U Wireless Adapter                                                                                        | 2         | 0.56%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                                              | 2         | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 73        | 57.48%  |
| Realtek Semiconductor | 16        | 12.6%   |
| MediaTek              | 12        | 9.45%   |
| Qualcomm Atheros      | 10        | 7.87%   |
| Ralink Technology     | 3         | 2.36%   |
| Broadcom              | 3         | 2.36%   |
| Ralink                | 2         | 1.57%   |
| Linksys               | 2         | 1.57%   |
| TP-Link               | 1         | 0.79%   |
| Microsoft             | 1         | 0.79%   |
| Dell                  | 1         | 0.79%   |
| BUFFALO               | 1         | 0.79%   |
| Broadcom Limited      | 1         | 0.79%   |
| ASUSTek Computer      | 1         | 0.79%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                              | Computers | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                         | 8         | 6.2%    |
| Intel Wi-Fi 6 AX200                                                | 8         | 6.2%    |
| Intel Alder Lake-P PCH CNVi WiFi                                   | 8         | 6.2%    |
| Intel Wireless 7260                                                | 6         | 4.65%   |
| Intel Wi-Fi 6 AX201                                                | 6         | 4.65%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter      | 5         | 3.88%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                             | 4         | 3.1%    |
| Intel Comet Lake PCH CNVi WiFi                                     | 4         | 3.1%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                       | 4         | 3.1%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller        | 3         | 2.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter           | 3         | 2.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter           | 3         | 2.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter         | 3         | 2.33%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                            | 3         | 2.33%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter      | 3         | 2.33%   |
| Intel Wireless 8260                                                | 3         | 2.33%   |
| Intel Wireless 7265                                                | 3         | 2.33%   |
| Intel Wireless 3165                                                | 3         | 2.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                  | 3         | 2.33%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                 | 2         | 1.55%   |
| Ralink MT7601U Wireless Adapter                                    | 2         | 1.55%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                          | 2         | 1.55%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter         | 2         | 1.55%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter         | 2         | 1.55%   |
| Intel Centrino Wireless-N 2230                                     | 2         | 1.55%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                           | 2         | 1.55%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                              | 1         | 0.78%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller [1T1R] | 1         | 0.78%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter            | 1         | 0.78%   |
| Realtek RTL8723DE Wireless Network Adapter                         | 1         | 0.78%   |
| Realtek RTL8191SEvB Wireless LAN Controller                        | 1         | 0.78%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter              | 1         | 0.78%   |
| Realtek 802.11ac NIC                                               | 1         | 0.78%   |
| Ralink RT5370 Wireless Adapter                                     | 1         | 0.78%   |
| Ralink RT3071 Wireless Adapter                                     | 1         | 0.78%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                   | 1         | 0.78%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                   | 1         | 0.78%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                   | 1         | 0.78%   |
| Microsoft Xbox 360 Wireless Adapter                                | 1         | 0.78%   |
| MediaTek WiFi                                                      | 1         | 0.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 85        | 41.46%  |
| Realtek Semiconductor     | 80        | 39.02%  |
| Broadcom                  | 14        | 6.83%   |
| ASIX Electronics          | 6         | 2.93%   |
| Lenovo                    | 4         | 1.95%   |
| Aquantia                  | 4         | 1.95%   |
| Marvell Technology Group  | 2         | 0.98%   |
| Broadcom Limited          | 2         | 0.98%   |
| Spreadtrum Communications | 1         | 0.49%   |
| Solarflare Communications | 1         | 0.49%   |
| Qualcomm Atheros          | 1         | 0.49%   |
| Qualcomm                  | 1         | 0.49%   |
| Mellanox Technologies     | 1         | 0.49%   |
| JMicron Technology        | 1         | 0.49%   |
| D-Link                    | 1         | 0.49%   |
| American Megatrends       | 1         | 0.49%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 57        | 25.91%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 14        | 6.36%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 5%      |
| Intel Ethernet Controller I225-V                                  | 8         | 3.64%   |
| Realtek RTL8125 2.5GbE Controller                                 | 7         | 3.18%   |
| Intel Ethernet Connection I217-LM                                 | 7         | 3.18%   |
| Intel I211 Gigabit Network Connection                             | 6         | 2.73%   |
| ASIX AX88179 Gigabit Ethernet                                     | 6         | 2.73%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 1.82%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 4         | 1.82%   |
| Intel I210 Gigabit Network Connection                             | 3         | 1.36%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 1.36%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 1.36%   |
| Intel Ethernet Connection (17) I219-V                             | 3         | 1.36%   |
| Intel 82574L Gigabit Network Connection                           | 3         | 1.36%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 3         | 1.36%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2         | 0.91%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 2         | 0.91%   |
| Intel I350 Gigabit Network Connection                             | 2         | 0.91%   |
| Intel Ethernet Virtual Function 700 Series                        | 2         | 0.91%   |
| Intel Ethernet Controller X550                                    | 2         | 0.91%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 2         | 0.91%   |
| Intel Ethernet Connection X722 for 10GBASE-T                      | 2         | 0.91%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.91%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 0.91%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 0.91%   |
| Intel Ethernet Connection (16) I219-V                             | 2         | 0.91%   |
| Intel Ethernet Connection (16) I219-LM                            | 2         | 0.91%   |
| Intel Ethernet Connection (14) I219-V                             | 2         | 0.91%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 0.91%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express           | 2         | 0.91%   |
| Spreadtrum Unisoc Phone                                           | 1         | 0.45%   |
| Solarflare SFC9020 10G Ethernet Controller                        | 1         | 0.45%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1         | 0.45%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.45%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.45%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.45%   |
| Qualcomm FP3                                                      | 1         | 0.45%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.45%   |
| Mellanox MT27700 Family [ConnectX-4]                              | 1         | 0.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 173       | 57.86%  |
| WiFi     | 121       | 40.47%  |
| Unknown  | 4         | 1.34%   |
| Modem    | 1         | 0.33%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 126       | 61.17%  |
| WiFi     | 79        | 38.35%  |
| Unknown  | 1         | 0.49%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 86        | 44.1%   |
| 1     | 78        | 40%     |
| 3     | 13        | 6.67%   |
| 5     | 8         | 4.1%    |
| 4     | 4         | 2.05%   |
| 0     | 3         | 1.54%   |
| 132   | 1         | 0.51%   |
| 66    | 1         | 0.51%   |
| 8     | 1         | 0.51%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 151       | 77.84%  |
| Yes  | 43        | 22.16%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 63        | 58.33%  |
| Realtek Semiconductor           | 10        | 9.26%   |
| Qualcomm Atheros Communications | 6         | 5.56%   |
| MediaTek                        | 6         | 5.56%   |
| Foxconn / Hon Hai               | 5         | 4.63%   |
| Broadcom                        | 5         | 4.63%   |
| Cambridge Silicon Radio         | 4         | 3.7%    |
| IMC Networks                    | 3         | 2.78%   |
| Ralink                          | 2         | 1.85%   |
| Integrated System Solution      | 1         | 0.93%   |
| Hewlett-Packard                 | 1         | 0.93%   |
| Dell                            | 1         | 0.93%   |
| Apple                           | 1         | 0.93%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                    | 23        | 21.3%   |
| Intel Bluetooth Device                                | 22        | 20.37%  |
| Realtek Bluetooth Radio                               | 9         | 8.33%   |
| Intel AX200 Bluetooth                                 | 8         | 7.41%   |
| MediaTek Wireless_Device                              | 6         | 5.56%   |
| Qualcomm Atheros  Bluetooth Device                    | 4         | 3.7%    |
| Intel Centrino Bluetooth Wireless Transceiver         | 4         | 3.7%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 4         | 3.7%    |
| Intel AX210 Bluetooth                                 | 3         | 2.78%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter          | 3         | 2.78%   |
| Ralink RT3290 Bluetooth                               | 2         | 1.85%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 2         | 1.85%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 2         | 1.85%   |
| Realtek  Bluetooth 4.2 Adapter                        | 1         | 0.93%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 1         | 0.93%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 1         | 0.93%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 1         | 0.93%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1         | 0.93%   |
| IMC Networks Wireless_Device                          | 1         | 0.93%   |
| IMC Networks Bluetooth Radio                          | 1         | 0.93%   |
| IMC Networks Bluetooth Device                         | 1         | 0.93%   |
| HP Broadcom 2070 Bluetooth Combo                      | 1         | 0.93%   |
| Foxconn / Hon Hai Wireless_Device                     | 1         | 0.93%   |
| Foxconn / Hon Hai MediaTek MT7921 Bluetooth           | 1         | 0.93%   |
| Dell Broadcom BCM20702A0 Bluetooth                    | 1         | 0.93%   |
| Broadcom HP Portable Bumble Bee                       | 1         | 0.93%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]            | 1         | 0.93%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]    | 1         | 0.93%   |
| Apple Bluetooth Host Controller                       | 1         | 0.93%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 125       | 45.45%  |
| Nvidia                 | 55        | 20%     |
| AMD                    | 54        | 19.64%  |
| Logitech               | 6         | 2.18%   |
| C-Media Electronics    | 5         | 1.82%   |
| Lenovo                 | 3         | 1.09%   |
| ASUSTek Computer       | 3         | 1.09%   |
| Texas Instruments      | 2         | 0.73%   |
| Hewlett-Packard        | 2         | 0.73%   |
| GN Netcom              | 2         | 0.73%   |
| Creative Technology    | 2         | 0.73%   |
| Conexant Systems       | 2         | 0.73%   |
| VIA Technologies       | 1         | 0.36%   |
| Tenx Technology        | 1         | 0.36%   |
| Setek Elektronik       | 1         | 0.36%   |
| Saitek                 | 1         | 0.36%   |
| Realtek Semiconductor  | 1         | 0.36%   |
| Plantronics            | 1         | 0.36%   |
| Nektar                 | 1         | 0.36%   |
| KTMicro                | 1         | 0.36%   |
| JMTek                  | 1         | 0.36%   |
| Huawei Technologies    | 1         | 0.36%   |
| GYROCOM C&C            | 1         | 0.36%   |
| Generalplus Technology | 1         | 0.36%   |
| Creative Labs          | 1         | 0.36%   |
| ASRock                 | 1         | 0.36%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 23        | 7.19%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 14        | 4.38%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 12        | 3.75%   |
| Intel Sunrise Point-LP HD Audio                                            | 11        | 3.44%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 11        | 3.44%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 10        | 3.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 9         | 2.81%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 8         | 2.5%    |
| Intel Comet Lake PCH cAVS                                                  | 7         | 2.19%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 7         | 2.19%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 6         | 1.88%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 6         | 1.88%   |
| AMD Starship/Matisse HD Audio Controller                                   | 6         | 1.88%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 5         | 1.56%   |
| Nvidia GK107 HDMI Audio Controller                                         | 5         | 1.56%   |
| Nvidia GA104 High Definition Audio Controller                              | 5         | 1.56%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 1.56%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5         | 1.56%   |
| Nvidia GK106 HDMI Audio Controller                                         | 4         | 1.25%   |
| Nvidia GA102 High Definition Audio Controller                              | 4         | 1.25%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 1.25%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 4         | 1.25%   |
| Intel 200 Series PCH HD Audio                                              | 4         | 1.25%   |
| AMD FCH Azalia Controller                                                  | 4         | 1.25%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 4         | 1.25%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 0.94%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3         | 0.94%   |
| Nvidia GA106 High Definition Audio Controller                              | 3         | 0.94%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 0.94%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 0.94%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 0.94%   |
| Intel Alder Lake-S HD Audio Controller                                     | 3         | 0.94%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3         | 0.94%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 0.94%   |
| AMD Trinity HDMI Audio Controller                                          | 3         | 0.94%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 0.94%   |
| Texas Instruments PCM2902 Audio Codec                                      | 2         | 0.63%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 0.63%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 0.63%   |
| Nvidia GK104 HDMI Audio Controller                                         | 2         | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 35        | 23.33%  |
| SK hynix            | 26        | 17.33%  |
| Micron Technology   | 22        | 14.67%  |
| Kingston            | 10        | 6.67%   |
| Crucial             | 10        | 6.67%   |
| Corsair             | 10        | 6.67%   |
| Unknown             | 9         | 6%      |
| G.Skill             | 8         | 5.33%   |
| A-DATA Technology   | 2         | 1.33%   |
| Unknown             | 2         | 1.33%   |
| Wodposit            | 1         | 0.67%   |
| Unknown (ABCD)      | 1         | 0.67%   |
| Team                | 1         | 0.67%   |
| Smart               | 1         | 0.67%   |
| Ramaxel Technology  | 1         | 0.67%   |
| PNY                 | 1         | 0.67%   |
| Patriot             | 1         | 0.67%   |
| Nanya Technology    | 1         | 0.67%   |
| Magnum Tech         | 1         | 0.67%   |
| Lexar Co Limited    | 1         | 0.67%   |
| Lexar               | 1         | 0.67%   |
| HPE                 | 1         | 0.67%   |
| Hewlett-Packard     | 1         | 0.67%   |
| Gold Key            | 1         | 0.67%   |
| Elpida              | 1         | 0.67%   |
| CUSO                | 1         | 0.67%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 1.95%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1066MT/s                     | 2         | 1.3%    |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 2         | 1.3%    |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.3%    |
| Samsung RAM M393B2873EH1-CF8 1GB DIMM DDR3 1066MT/s              | 2         | 1.3%    |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 2         | 1.3%    |
| Unknown                                                          | 2         | 1.3%    |
| Wodposit RAM WPBH26D408SWA-8G 8GB SODIMM DDR4 2667MT/s           | 1         | 0.65%   |
| Unknown RAM Module 8GB DIMM DDR4 3000MT/s                        | 1         | 0.65%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 1         | 0.65%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 1         | 0.65%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 1         | 0.65%   |
| Unknown RAM Module 2GB DIMM 667MT/s                              | 1         | 0.65%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 1         | 0.65%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                         | 1         | 0.65%   |
| Unknown RAM Module 1GB DIMM 667MT/s                              | 1         | 0.65%   |
| Unknown RAM Module 16GB DIMM DDR4 2666MT/s                       | 1         | 0.65%   |
| Unknown RAM DDR4 NB 8G 2666 8GB SODIMM DDR4 2667MT/s             | 1         | 0.65%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 0.65%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3733MT/s               | 1         | 0.65%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.65%   |
| SK hynix RAM Module 8GB SODIMM DDR4 3200MT/s                     | 1         | 0.65%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s                     | 1         | 0.65%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 0.65%   |
| SK hynix RAM Module 4GB Row Of Chips DDR4 2400MT/s               | 1         | 0.65%   |
| SK hynix RAM Module 32GB SODIMM DDR4 3200MT/s                    | 1         | 0.65%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s                       | 1         | 0.65%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s             | 1         | 0.65%   |
| SK hynix RAM HMT325U7EFR8A-PB 2GB DIMM DDR3 1600MT/s             | 1         | 0.65%   |
| SK hynix RAM HMT31GR7BFR4C-H9 8GB DIMM DDR3 1333MT/s             | 1         | 0.65%   |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s           | 1         | 0.65%   |
| SK hynix RAM HMAB2GS6CMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 0.65%   |
| SK hynix RAM HMAA8GR7CJR4N-XN 64GB DIMM DDR4 3200MT/s            | 1         | 0.65%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s          | 1         | 0.65%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 0.65%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.65%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 0.65%   |
| SK hynix RAM HMA82GR7AFR8N-VK 16GB DIMM DDR4 2666MT/s            | 1         | 0.65%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.65%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.65%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 75        | 56.82%  |
| DDR3    | 37        | 28.03%  |
| DDR5    | 9         | 6.82%   |
| LPDDR5  | 3         | 2.27%   |
| LPDDR4  | 3         | 2.27%   |
| DDR2    | 3         | 2.27%   |
| LPDDR3  | 1         | 0.76%   |
| Unknown | 1         | 0.76%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 64        | 48.12%  |
| SODIMM       | 59        | 44.36%  |
| Row Of Chips | 8         | 6.02%   |
| RIMM         | 1         | 0.75%   |
| Unknown      | 1         | 0.75%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 53        | 37.86%  |
| 16384 | 32        | 22.86%  |
| 4096  | 24        | 17.14%  |
| 32768 | 18        | 12.86%  |
| 1024  | 7         | 5%      |
| 2048  | 5         | 3.57%   |
| 65536 | 1         | 0.71%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 32        | 22.54%  |
| 2667  | 24        | 16.9%   |
| 1600  | 17        | 11.97%  |
| 2400  | 13        | 9.15%   |
| 1333  | 8         | 5.63%   |
| 4800  | 7         | 4.93%   |
| 2133  | 6         | 4.23%   |
| 2666  | 5         | 3.52%   |
| 1066  | 5         | 3.52%   |
| 3600  | 3         | 2.11%   |
| 667   | 3         | 2.11%   |
| 6400  | 2         | 1.41%   |
| 3534  | 2         | 1.41%   |
| 1800  | 2         | 1.41%   |
| 5600  | 1         | 0.7%    |
| 5500  | 1         | 0.7%    |
| 4267  | 1         | 0.7%    |
| 4266  | 1         | 0.7%    |
| 3733  | 1         | 0.7%    |
| 3666  | 1         | 0.7%    |
| 3266  | 1         | 0.7%    |
| 3100  | 1         | 0.7%    |
| 3000  | 1         | 0.7%    |
| 2800  | 1         | 0.7%    |
| 2200  | 1         | 0.7%    |
| 2048  | 1         | 0.7%    |
| 1866  | 1         | 0.7%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Seiko Epson        | 2         | 66.67%  |
| Brother Industries | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Seiko Epson XP-4100 Series    | 1         | 33.33%  |
| Seiko Epson Printer           | 1         | 33.33%  |
| Brother HL-2030 Laser Printer | 1         | 33.33%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| HP ScanJet 82x0C  | 1         | 50%     |
| HP OfficeJet 6110 | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 18        | 20%     |
| IMC Networks                           | 14        | 15.56%  |
| Realtek Semiconductor                  | 8         | 8.89%   |
| Microdia                               | 6         | 6.67%   |
| Sunplus Innovation Technology          | 5         | 5.56%   |
| Logitech                               | 5         | 5.56%   |
| Syntek                                 | 4         | 4.44%   |
| Luxvisions Innotech Limited            | 4         | 4.44%   |
| Bison Electronics                      | 4         | 4.44%   |
| Quanta                                 | 3         | 3.33%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 3.33%   |
| Generalplus Technology                 | 2         | 2.22%   |
| Creality 3D Technology                 | 2         | 2.22%   |
| Suyin                                  | 1         | 1.11%   |
| Sonix Technology                       | 1         | 1.11%   |
| Silicon Motion                         | 1         | 1.11%   |
| MacroSilicon                           | 1         | 1.11%   |
| Lite-On Technology                     | 1         | 1.11%   |
| Lenovo                                 | 1         | 1.11%   |
| KYE Systems (Mouse Systems)            | 1         | 1.11%   |
| Intel                                  | 1         | 1.11%   |
| icSpring                               | 1         | 1.11%   |
| Huawei Technologies                    | 1         | 1.11%   |
| Elgato Systems                         | 1         | 1.11%   |
| Apple                                  | 1         | 1.11%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 10        | 10.99%  |
| Realtek Integrated_Webcam_HD                        | 5         | 5.49%   |
| Microdia Integrated_Webcam_HD                       | 5         | 5.49%   |
| IMC Networks Integrated Camera                      | 5         | 5.49%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 4         | 4.4%    |
| Chicony HP HD Camera                                | 3         | 3.3%    |
| Syntek Lenovo EasyCamera                            | 2         | 2.2%    |
| Syntek Integrated Camera                            | 2         | 2.2%    |
| Logitech HD Pro Webcam C920                         | 2         | 2.2%    |
| Generalplus GENERAL WEBCAM                          | 2         | 2.2%    |
| Creality 3D CREALITY CAM                            | 2         | 2.2%    |
| Chicony HD WebCam                                   | 2         | 2.2%    |
| Bison Integrated RGB Camera                         | 2         | 2.2%    |
| Suyin HP TrueVision HD Integrated Webcam            | 1         | 1.1%    |
| Sunplus Laptop_Integrated_Webcam_HD                 | 1         | 1.1%    |
| Sunplus Integrated_Webcam_HD                        | 1         | 1.1%    |
| Sunplus Integrated_Webcam_FHD                       | 1         | 1.1%    |
| Sunplus Full HD webcam                              | 1         | 1.1%    |
| Sunplus FHD Camera                                  | 1         | 1.1%    |
| Sonix USB2.0 HD UVC WebCam                          | 1         | 1.1%    |
| Silicon Motion Lenovo EasyCamera                    | 1         | 1.1%    |
| Realtek USB2.0 HD UVC WebCam                        | 1         | 1.1%    |
| Realtek Integrated Webcam_HD                        | 1         | 1.1%    |
| Realtek EasyCamera                                  | 1         | 1.1%    |
| Quanta HP Webcam                                    | 1         | 1.1%    |
| Quanta HP True Vision 5MP Camera                    | 1         | 1.1%    |
| Quanta HP 5MP Camera                                | 1         | 1.1%    |
| Microdia Integrated_Webcam_FHD                      | 1         | 1.1%    |
| MacroSilicon USB3. 0 capture                        | 1         | 1.1%    |
| Luxvisions Innotech Limited Integrated RGB Camera   | 1         | 1.1%    |
| Luxvisions Innotech Limited Integrated Camera       | 1         | 1.1%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 1.1%    |
| Luxvisions Innotech Limited HP HD Camera            | 1         | 1.1%    |
| Logitech Webcam C270                                | 1         | 1.1%    |
| Logitech HD Webcam C615                             | 1         | 1.1%    |
| Logitech BRIO Ultra HD Webcam                       | 1         | 1.1%    |
| Lite-On HP HD Webcam                                | 1         | 1.1%    |
| Lenovo UVC Camera                                   | 1         | 1.1%    |
| KYE Systems (Mouse Systems) Genius Webcam           | 1         | 1.1%    |
| Intel RealSense 3D Camera (Front F200)              | 1         | 1.1%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 10        | 33.33%  |
| Validity Sensors           | 8         | 26.67%  |
| Shenzhen Goodix Technology | 5         | 16.67%  |
| LighTuning Technology      | 3         | 10%     |
| Upek                       | 2         | 6.67%   |
| Elan Microelectronics      | 1         | 3.33%   |
| AuthenTec                  | 1         | 3.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 10%     |
| Validity Sensors VFS495 Fingerprint Reader                                 | 2         | 6.67%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 6.67%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 6.67%   |
| Synaptics UWP WBDI Device                                                  | 2         | 6.67%   |
| Shenzhen Goodix  Fingerprint Device                                        | 2         | 6.67%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 6.67%   |
| LighTuning Fingerprint Sensor                                              | 2         | 6.67%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 3.33%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 3.33%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 3.33%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 3.33%   |
| Synaptics WBDI                                                             | 1         | 3.33%   |
| Synaptics  WBDI                                                            | 1         | 3.33%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 3.33%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 3.33%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 3.33%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 3.33%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 3.33%   |
| Elan ELAN:Fingerprint                                                      | 1         | 3.33%   |
| AuthenTec AES2810                                                          | 1         | 3.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 3         | 42.86%  |
| Alcor Micro | 3         | 42.86%  |
| O2 Micro    | 1         | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 42.86%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 14.29%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 14.29%  |
| Broadcom 5880                                                                | 1         | 14.29%  |
| Broadcom 58200                                                               | 1         | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 106       | 54.36%  |
| 1     | 65        | 33.33%  |
| 2     | 16        | 8.21%   |
| 3     | 4         | 2.05%   |
| 5     | 2         | 1.03%   |
| 4     | 2         | 1.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 30        | 26.09%  |
| Graphics card            | 20        | 17.39%  |
| Net/wireless             | 13        | 11.3%   |
| Unassigned class         | 12        | 10.43%  |
| Communication controller | 9         | 7.83%   |
| Net/ethernet             | 5         | 4.35%   |
| Multimedia controller    | 5         | 4.35%   |
| Firewire controller      | 4         | 3.48%   |
| Sound                    | 3         | 2.61%   |
| Network                  | 3         | 2.61%   |
| Chipcard                 | 3         | 2.61%   |
| Bluetooth                | 2         | 1.74%   |
| Storage/raid             | 1         | 0.87%   |
| Storage/ide              | 1         | 0.87%   |
| Storage                  | 1         | 0.87%   |
| Modem                    | 1         | 0.87%   |
| Dvb card                 | 1         | 0.87%   |
| Card reader              | 1         | 0.87%   |

