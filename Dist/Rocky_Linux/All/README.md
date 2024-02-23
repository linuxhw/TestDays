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

Total: 264

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Unknown       | T3 MRD                      | Desktop     | [e3b3bc071f](https://linux-hardware.org/?probe=e3b3bc071f) | Jan 31, 2024 |
| HP            | 8653 A                      | Desktop     | [64cfa9a25f](https://linux-hardware.org/?probe=64cfa9a25f) | Jan 30, 2024 |
| Gigabyte      | MG51-G21-00 01010101        | Server      | [29dc4440ff](https://linux-hardware.org/?probe=29dc4440ff) | Jan 30, 2024 |
| Gigabyte      | MG51-G21-00 01010101        | Server      | [56087b1d70](https://linux-hardware.org/?probe=56087b1d70) | Jan 30, 2024 |
| Machenike     | ARB19                       | Desktop     | [3002916884](https://linux-hardware.org/?probe=3002916884) | Jan 28, 2024 |
| Machenike     | ARB19                       | Desktop     | [4f289b9a02](https://linux-hardware.org/?probe=4f289b9a02) | Jan 28, 2024 |
| Unknown       | Unknown                     | Notebook    | [2d74d756b3](https://linux-hardware.org/?probe=2d74d756b3) | Jan 10, 2024 |
| Unknown       | DS16                        | Notebook    | [1951d37c43](https://linux-hardware.org/?probe=1951d37c43) | Jan 10, 2024 |
| Dell          | 0D735T A00                  | Desktop     | [4f4fe7da0b](https://linux-hardware.org/?probe=4f4fe7da0b) | Jan 06, 2024 |
| Dell          | 0FJM8V A01                  | Server      | [b86b3ead94](https://linux-hardware.org/?probe=b86b3ead94) | Jan 05, 2024 |
| Intel         | X99                         | Desktop     | [ed34568c2b](https://linux-hardware.org/?probe=ed34568c2b) | Jan 05, 2024 |
| Unknown       | Unknown                     | Desktop     | [3faf86bf2b](https://linux-hardware.org/?probe=3faf86bf2b) | Jan 04, 2024 |
| Dell          | Inspiron 3501               | Notebook    | [7c421031f6](https://linux-hardware.org/?probe=7c421031f6) | Jan 04, 2024 |
| Dell          | 0FJM8V A01                  | Server      | [a48bee749e](https://linux-hardware.org/?probe=a48bee749e) | Jan 03, 2024 |
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
| Rocky Linux 9.1 | 44        | 21.15%  |
| Rocky Linux 8.5 | 32        | 15.38%  |
| Rocky Linux 9.2 | 30        | 14.42%  |
| Rocky Linux 9.0 | 19        | 9.13%   |
| Rocky Linux 8.4 | 19        | 9.13%   |
| Rocky Linux 9.3 | 17        | 8.17%   |
| Rocky Linux 8.8 | 16        | 7.69%   |
| Rocky Linux 8.7 | 13        | 6.25%   |
| Rocky Linux 8.6 | 11        | 5.29%   |
| Rocky Linux 8.9 | 5         | 2.4%    |
| Rocky Linux 8.3 | 2         | 0.96%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Rocky Linux | 203       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                          | Computers | Percent |
|----------------------------------|-----------|---------|
| 5.14.0-162.6.1.el9_1.0.1.x86_64  | 18        | 8.41%   |
| 4.18.0-348.12.2.el8_5.x86_64     | 13        | 6.07%   |
| 5.14.0-284.30.1.el9_2.x86_64     | 10        | 4.67%   |
| 5.14.0-362.8.1.el9_3.x86_64      | 9         | 4.21%   |
| 5.14.0-284.25.1.el9_2.x86_64     | 8         | 3.74%   |
| 5.14.0-162.18.1.el9_1.x86_64     | 8         | 3.74%   |
| 4.18.0-477.27.1.el8_8.x86_64     | 8         | 3.74%   |
| 4.18.0-348.7.1.el8_5.x86_64      | 8         | 3.74%   |
| 5.14.0-284.18.1.el9_2.x86_64     | 7         | 3.27%   |
| 5.14.0-70.26.1.el9_0.x86_64      | 6         | 2.8%    |
| 5.14.0-284.11.1.el9_2.x86_64     | 6         | 2.8%    |
| 4.18.0-305.10.2.el8_4.x86_64     | 6         | 2.8%    |
| 5.14.0-70.22.1.el9_0.x86_64      | 5         | 2.34%   |
| 5.14.0-162.23.1.el9_1.x86_64     | 5         | 2.34%   |
| 5.14.0-162.12.1.el9_1.0.2.x86_64 | 5         | 2.34%   |
| 4.18.0-348.20.1.el8_5.x86_64     | 5         | 2.34%   |
| 5.14.0-70.30.1.el9_0.x86_64      | 4         | 1.87%   |
| 5.14.0-70.17.1.el9_0.x86_64      | 4         | 1.87%   |
| 5.14.0-362.13.1.el9_3.x86_64     | 4         | 1.87%   |
| 5.14.0-162.6.1.el9_1.x86_64      | 4         | 1.87%   |
| 4.18.0-477.21.1.el8_8.x86_64     | 3         | 1.4%    |
| 4.18.0-425.3.1.el8.x86_64        | 3         | 1.4%    |
| 4.18.0-425.19.2.el8_7.x86_64     | 3         | 1.4%    |
| 4.18.0-425.13.1.el8_7.x86_64     | 3         | 1.4%    |
| 4.18.0-425.10.1.el8_7.x86_64     | 3         | 1.4%    |
| 4.18.0-372.32.1.el8_6.x86_64     | 3         | 1.4%    |
| 4.18.0-305.25.1.el8_4.x86_64     | 3         | 1.4%    |
| 6.1.64-2.el9.x86_64              | 2         | 0.93%   |
| 5.14.0-162.12.1.el9_1.0.1.x86_64 | 2         | 0.93%   |
| 4.18.0-513.9.1.el8_9.x86_64      | 2         | 0.93%   |
| 4.18.0-513.11.1.el8_9.x86_64     | 2         | 0.93%   |
| 4.18.0-477.15.1.el8_8.x86_64     | 2         | 0.93%   |
| 4.18.0-477.13.1.el8_8.x86_64     | 2         | 0.93%   |
| 4.18.0-372.9.1.el8.x86_64        | 2         | 0.93%   |
| 4.18.0-372.26.1.el8_6.x86_64     | 2         | 0.93%   |
| 4.18.0-372.19.1.el8_6.x86_64     | 2         | 0.93%   |
| 4.18.0-372.16.1.el8_6.0.1.x86_64 | 2         | 0.93%   |
| 4.18.0-348.2.1.el8_5.x86_64      | 2         | 0.93%   |
| 4.18.0-305.el8.x86_64            | 2         | 0.93%   |
| 4.18.0-305.3.1.el8_4.x86_64      | 2         | 0.93%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14.0  | 103       | 50.24%  |
| 4.18.0  | 87        | 42.44%  |
| 6.1.64  | 2         | 0.98%   |
| 6.0.10  | 2         | 0.98%   |
| 6.6.11  | 1         | 0.49%   |
| 6.4.12  | 1         | 0.49%   |
| 6.2.12  | 1         | 0.49%   |
| 6.2.10  | 1         | 0.49%   |
| 6.1.8   | 1         | 0.49%   |
| 6.1.6   | 1         | 0.49%   |
| 5.4.157 | 1         | 0.49%   |
| 5.16.15 | 1         | 0.49%   |
| 5.14.1  | 1         | 0.49%   |
| 5.10.89 | 1         | 0.49%   |
| 5.10.52 | 1         | 0.49%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14    | 104       | 50.73%  |
| 4.18    | 87        | 42.44%  |
| 6.1     | 4         | 1.95%   |
| 6.2     | 2         | 0.98%   |
| 6.0     | 2         | 0.98%   |
| 5.10    | 2         | 0.98%   |
| 6.6     | 1         | 0.49%   |
| 6.4     | 1         | 0.49%   |
| 5.4     | 1         | 0.49%   |
| 5.16    | 1         | 0.49%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 202       | 99.51%  |
| aarch64 | 1         | 0.49%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 137       | 67.16%  |
| Unknown       | 26        | 12.75%  |
| KDE5          | 16        | 7.84%   |
| MATE          | 9         | 4.41%   |
| XFCE          | 7         | 3.43%   |
| GNOME Classic | 5         | 2.45%   |
| X-Cinnamon    | 3         | 1.47%   |
| Cinnamon      | 1         | 0.49%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 107       | 51.44%  |
| X11     | 75        | 36.06%  |
| Unknown | 12        | 5.77%   |
| Tty     | 11        | 5.29%   |
| Web     | 3         | 1.44%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 92        | 45.32%  |
| GDM     | 88        | 43.35%  |
| SDDM    | 12        | 5.91%   |
| LightDM | 11        | 5.42%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 134       | 66.01%  |
| en_CA   | 7         | 3.45%   |
| ru_RU   | 6         | 2.96%   |
| en_AU   | 6         | 2.96%   |
| en_GB   | 4         | 1.97%   |
| C       | 4         | 1.97%   |
| Unknown | 4         | 1.97%   |
| pt_BR   | 3         | 1.48%   |
| es_ES   | 3         | 1.48%   |
| en_ZA   | 3         | 1.48%   |
| en_IL   | 3         | 1.48%   |
| de_DE   | 3         | 1.48%   |
| ko_KR   | 2         | 0.99%   |
| it_IT   | 2         | 0.99%   |
| en_SG   | 2         | 0.99%   |
| en_IE   | 2         | 0.99%   |
| de_AT   | 2         | 0.99%   |
| zh_TW   | 1         | 0.49%   |
| zh_CN   | 1         | 0.49%   |
| pl_PL   | 1         | 0.49%   |
| nl_NL   | 1         | 0.49%   |
| ja_JP   | 1         | 0.49%   |
| hu_HU   | 1         | 0.49%   |
| fr_FR   | 1         | 0.49%   |
| es_CO   | 1         | 0.49%   |
| es_AR   | 1         | 0.49%   |
| en_NZ   | 1         | 0.49%   |
| en_IN   | 1         | 0.49%   |
| ca_ES   | 1         | 0.49%   |
| af_ZA   | 1         | 0.49%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 144       | 70.59%  |
| BIOS | 60        | 29.41%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Xfs  | 171       | 84.24%  |
| Ext4 | 30        | 14.78%  |
| Ext3 | 1         | 0.49%   |
| Ext2 | 1         | 0.49%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 113       | 55.67%  |
| Unknown | 64        | 31.53%  |
| MBR     | 26        | 12.81%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 167       | 82.27%  |
| Yes       | 36        | 17.73%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 168       | 82.76%  |
| Yes       | 35        | 17.24%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 38        | 18.72%  |
| Lenovo                  | 37        | 18.23%  |
| Hewlett-Packard         | 34        | 16.75%  |
| ASUSTek Computer        | 28        | 13.79%  |
| Gigabyte Technology     | 12        | 5.91%   |
| MSI                     | 8         | 3.94%   |
| Unknown                 | 6         | 2.96%   |
| Intel                   | 5         | 2.46%   |
| ASRock                  | 5         | 2.46%   |
| AZW                     | 4         | 1.97%   |
| Supermicro              | 3         | 1.48%   |
| Toshiba                 | 2         | 0.99%   |
| Positivo                | 2         | 0.99%   |
| Acer                    | 2         | 0.99%   |
| Techvision              | 1         | 0.49%   |
| System76                | 1         | 0.49%   |
| Sapphire                | 1         | 0.49%   |
| Raspberry Pi Foundation | 1         | 0.49%   |
| Pegatron                | 1         | 0.49%   |
| NCR                     | 1         | 0.49%   |
| Machenike               | 1         | 0.49%   |
| IBM                     | 1         | 0.49%   |
| HUAWEI                  | 1         | 0.49%   |
| HPE                     | 1         | 0.49%   |
| Google                  | 1         | 0.49%   |
| Clevo                   | 1         | 0.49%   |
| BESSTAR Tech            | 1         | 0.49%   |
| Beelink                 | 1         | 0.49%   |
| BANGHO                  | 1         | 0.49%   |
| ATOPNUC                 | 1         | 0.49%   |
| Apple                   | 1         | 0.49%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 6         | 2.96%   |
| Dell PowerEdge R610                      | 3         | 1.48%   |
| HP Z210 Workstation                      | 2         | 0.99%   |
| HP EliteBook 840 G5                      | 2         | 0.99%   |
| Dell OptiPlex 9020                       | 2         | 0.99%   |
| AZW GTR                                  | 2         | 0.99%   |
| Toshiba TECRA W50-A                      | 1         | 0.49%   |
| Toshiba Satellite E45-B                  | 1         | 0.49%   |
| Techvision TVI7309X                      | 1         | 0.49%   |
| System76 Thelio Mira                     | 1         | 0.49%   |
| Supermicro SYS-6019U-TN4R4T              | 1         | 0.49%   |
| Supermicro SYS-5029P-WTR                 | 1         | 0.49%   |
| Supermicro Super Server                  | 1         | 0.49%   |
| Sapphire PE-AM2RS690V2                   | 1         | 0.49%   |
| RPi Raspberry Pi                         | 1         | 0.49%   |
| Positivo Q464C                           | 1         | 0.49%   |
| Positivo Mobile                          | 1         | 0.49%   |
| Pegatron IPMIP-GS                        | 1         | 0.49%   |
| NCR xxxx-xxxx-xxxx                       | 1         | 0.49%   |
| MSI MS-7D78                              | 1         | 0.49%   |
| MSI MS-7D46                              | 1         | 0.49%   |
| MSI MS-7D25                              | 1         | 0.49%   |
| MSI MS-7B89                              | 1         | 0.49%   |
| MSI MS-7B78                              | 1         | 0.49%   |
| MSI MS-7A94                              | 1         | 0.49%   |
| MSI MS-7917                              | 1         | 0.49%   |
| MSI H510M PRO-E                          | 1         | 0.49%   |
| Machenike DT                             | 1         | 0.49%   |
| Lenovo Yoga 720-13IKB 80X6               | 1         | 0.49%   |
| Lenovo ThinkStation P620 30E0S0PR00      | 1         | 0.49%   |
| Lenovo ThinkStation P340 30DK000CUS      | 1         | 0.49%   |
| Lenovo ThinkPad X270 20HMS79Q00          | 1         | 0.49%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BTS1V900 | 1         | 0.49%   |
| Lenovo ThinkPad X1 Carbon 344835U        | 1         | 0.49%   |
| Lenovo ThinkPad W540 20BGCTO1WW          | 1         | 0.49%   |
| Lenovo ThinkPad W500 406132G             | 1         | 0.49%   |
| Lenovo ThinkPad T480 20L6S8B500          | 1         | 0.49%   |
| Lenovo ThinkPad T430u 86147MG            | 1         | 0.49%   |
| Lenovo ThinkPad T430 2347FF9             | 1         | 0.49%   |
| Lenovo ThinkPad T420 42365H1             | 1         | 0.49%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Lenovo ThinkPad             | 17        | 8.37%   |
| ASUS PRIME                  | 10        | 4.93%   |
| Lenovo IdeaPad              | 8         | 3.94%   |
| Dell PowerEdge              | 8         | 3.94%   |
| HP EliteBook                | 6         | 2.96%   |
| Dell Precision              | 6         | 2.96%   |
| Dell OptiPlex               | 6         | 2.96%   |
| Unknown                     | 6         | 2.96%   |
| Dell XPS                    | 5         | 2.46%   |
| Dell Latitude               | 5         | 2.46%   |
| HP ZBook                    | 4         | 1.97%   |
| HP Laptop                   | 4         | 1.97%   |
| Dell Vostro                 | 4         | 1.97%   |
| Dell Inspiron               | 4         | 1.97%   |
| HP EliteDesk                | 3         | 1.48%   |
| ASUS ROG                    | 3         | 1.48%   |
| ASUS ASUS                   | 3         | 1.48%   |
| Lenovo ThinkStation         | 2         | 0.99%   |
| Lenovo ThinkCentre          | 2         | 0.99%   |
| Lenovo Legion               | 2         | 0.99%   |
| Lenovo IdeaPadFlex          | 2         | 0.99%   |
| HP Z210                     | 2         | 0.99%   |
| HP ProLiant                 | 2         | 0.99%   |
| HP ProBook                  | 2         | 0.99%   |
| HP Pavilion                 | 2         | 0.99%   |
| HP ENVY                     | 2         | 0.99%   |
| AZW GTR                     | 2         | 0.99%   |
| Acer Aspire                 | 2         | 0.99%   |
| Toshiba TECRA               | 1         | 0.49%   |
| Toshiba Satellite           | 1         | 0.49%   |
| Techvision TVI7309X         | 1         | 0.49%   |
| System76 Thelio             | 1         | 0.49%   |
| Supermicro SYS-6019U-TN4R4T | 1         | 0.49%   |
| Supermicro SYS-5029P-WTR    | 1         | 0.49%   |
| Supermicro Super            | 1         | 0.49%   |
| Sapphire PE-AM2RS690V2      | 1         | 0.49%   |
| RPi Raspberry               | 1         | 0.49%   |
| Positivo Q464C              | 1         | 0.49%   |
| Positivo Mobile             | 1         | 0.49%   |
| Pegatron IPMIP-GS           | 1         | 0.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2022    | 29        | 14.29%  |
| 2021    | 25        | 12.32%  |
| 2020    | 25        | 12.32%  |
| 2018    | 22        | 10.84%  |
| 2019    | 15        | 7.39%   |
| 2011    | 14        | 6.9%    |
| 2013    | 12        | 5.91%   |
| 2012    | 11        | 5.42%   |
| 2014    | 10        | 4.93%   |
| 2017    | 9         | 4.43%   |
| 2015    | 9         | 4.43%   |
| 2023    | 6         | 2.96%   |
| 2010    | 6         | 2.96%   |
| 2009    | 4         | 1.97%   |
| 2008    | 3         | 1.48%   |
| 2016    | 2         | 0.99%   |
| Unknown | 1         | 0.49%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 86        | 42.36%  |
| Notebook       | 82        | 40.39%  |
| Server         | 19        | 9.36%   |
| Mini pc        | 8         | 3.94%   |
| Convertible    | 6         | 2.96%   |
| System on chip | 1         | 0.49%   |
| Tablet         | 1         | 0.49%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 176       | 86.7%   |
| Enabled  | 27        | 13.3%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 202       | 99.51%  |
| Yes  | 1         | 0.49%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 49        | 24.02%  |
| 4.01-8.0        | 41        | 20.1%   |
| 32.01-64.0      | 37        | 18.14%  |
| 64.01-256.0     | 22        | 10.78%  |
| 16.01-24.0      | 20        | 9.8%    |
| 3.01-4.0        | 12        | 5.88%   |
| 24.01-32.0      | 9         | 4.41%   |
| More than 256.0 | 7         | 3.43%   |
| 1.01-2.0        | 4         | 1.96%   |
| 2.01-3.0        | 3         | 1.47%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 58        | 27.23%  |
| 2.01-3.0    | 51        | 23.94%  |
| 3.01-4.0    | 39        | 18.31%  |
| 1.01-2.0    | 27        | 12.68%  |
| 8.01-16.0   | 16        | 7.51%   |
| 0.51-1.0    | 11        | 5.16%   |
| 16.01-24.0  | 4         | 1.88%   |
| 32.01-64.0  | 2         | 0.94%   |
| 24.01-32.0  | 2         | 0.94%   |
| 0.01-0.5    | 2         | 0.94%   |
| 64.01-256.0 | 1         | 0.47%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 121       | 58.74%  |
| 2      | 36        | 17.48%  |
| 3      | 19        | 9.22%   |
| 4      | 15        | 7.28%   |
| 6      | 4         | 1.94%   |
| 5      | 4         | 1.94%   |
| 19     | 1         | 0.49%   |
| 18     | 1         | 0.49%   |
| 17     | 1         | 0.49%   |
| 16     | 1         | 0.49%   |
| 14     | 1         | 0.49%   |
| 9      | 1         | 0.49%   |
| 8      | 1         | 0.49%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 150       | 73.89%  |
| Yes       | 53        | 26.11%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 182       | 89.22%  |
| No        | 22        | 10.78%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 128       | 62.44%  |
| No        | 77        | 37.56%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 112       | 54.9%   |
| No        | 92        | 45.1%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 67        | 33%     |
| Germany      | 10        | 4.93%   |
| Canada       | 10        | 4.93%   |
| Russia       | 9         | 4.43%   |
| Italy        | 7         | 3.45%   |
| Australia    | 7         | 3.45%   |
| UK           | 5         | 2.46%   |
| Spain        | 5         | 2.46%   |
| Netherlands  | 5         | 2.46%   |
| South Africa | 4         | 1.97%   |
| Singapore    | 4         | 1.97%   |
| Poland       | 4         | 1.97%   |
| Indonesia    | 4         | 1.97%   |
| Czechia      | 4         | 1.97%   |
| Brazil       | 4         | 1.97%   |
| South Korea  | 3         | 1.48%   |
| Mexico       | 3         | 1.48%   |
| Israel       | 3         | 1.48%   |
| India        | 3         | 1.48%   |
| Hungary      | 3         | 1.48%   |
| France       | 3         | 1.48%   |
| Argentina    | 3         | 1.48%   |
| Sweden       | 2         | 0.99%   |
| Norway       | 2         | 0.99%   |
| Malaysia     | 2         | 0.99%   |
| Ireland      | 2         | 0.99%   |
| China        | 2         | 0.99%   |
| Belgium      | 2         | 0.99%   |
| Austria      | 2         | 0.99%   |
| Uzbekistan   | 1         | 0.49%   |
| UAE          | 1         | 0.49%   |
| Turkey       | 1         | 0.49%   |
| Taiwan       | 1         | 0.49%   |
| Switzerland  | 1         | 0.49%   |
| Slovakia     | 1         | 0.49%   |
| Saudi Arabia | 1         | 0.49%   |
| Portugal     | 1         | 0.49%   |
| Pakistan     | 1         | 0.49%   |
| New Zealand  | 1         | 0.49%   |
| Kenya        | 1         | 0.49%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Melbourne     | 5         | 2.45%   |
| Singapore     | 4         | 1.96%   |
| Toronto       | 3         | 1.47%   |
| Moscow        | 3         | 1.47%   |
| Budapest      | 3         | 1.47%   |
| Berlin        | 3         | 1.47%   |
| Vienna        | 2         | 0.98%   |
| Prague        | 2         | 0.98%   |
| Philadelphia  | 2         | 0.98%   |
| Oslo          | 2         | 0.98%   |
| Krakow        | 2         | 0.98%   |
| Haifa         | 2         | 0.98%   |
| Enschede      | 2         | 0.98%   |
| Chicago       | 2         | 0.98%   |
| Centurion     | 2         | 0.98%   |
| Buckley       | 2         | 0.98%   |
| Bekasi        | 2         | 0.98%   |
| Albuquerque   | 2         | 0.98%   |
| Adelaide      | 2         | 0.98%   |
| Žilina       | 1         | 0.49%   |
| Yogyakarta    | 1         | 0.49%   |
| Yekaterinburg | 1         | 0.49%   |
| Xi'an         | 1         | 0.49%   |
| Woking        | 1         | 0.49%   |
| Willowbrook   | 1         | 0.49%   |
| Westerville   | 1         | 0.49%   |
| Wells         | 1         | 0.49%   |
| Washington    | 1         | 0.49%   |
| Waltham       | 1         | 0.49%   |
| Walnut Creek  | 1         | 0.49%   |
| Wake Forest   | 1         | 0.49%   |
| Voronezh      | 1         | 0.49%   |
| Viggiù       | 1         | 0.49%   |
| Vero Beach    | 1         | 0.49%   |
| Vashon        | 1         | 0.49%   |
| Vancouver     | 1         | 0.49%   |
| Urbana        | 1         | 0.49%   |
| Turin         | 1         | 0.49%   |
| Troisdorf     | 1         | 0.49%   |
| Tower Hamlets | 1         | 0.49%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 55        | 77     | 18.52%  |
| Seagate                     | 38        | 106    | 12.79%  |
| WDC                         | 34        | 62     | 11.45%  |
| SanDisk                     | 17        | 19     | 5.72%   |
| Toshiba                     | 16        | 19     | 5.39%   |
| Intel                       | 13        | 19     | 4.38%   |
| Micron Technology           | 10        | 10     | 3.37%   |
| Kingston                    | 10        | 10     | 3.37%   |
| Unknown                     | 9         | 12     | 3.03%   |
| SK hynix                    | 9         | 11     | 3.03%   |
| Hitachi                     | 9         | 14     | 3.03%   |
| Crucial                     | 9         | 10     | 3.03%   |
| MAXIO Technology (Hangzhou) | 4         | 5      | 1.35%   |
| PNY                         | 3         | 4      | 1.01%   |
| Phison                      | 3         | 4      | 1.01%   |
| Micron/Crucial Technology   | 3         | 4      | 1.01%   |
| HGST                        | 3         | 3      | 1.01%   |
| A-DATA Technology           | 3         | 3      | 1.01%   |
| SABRENT                     | 2         | 2      | 0.67%   |
| LITEONIT                    | 2         | 2      | 0.67%   |
| Lexar                       | 2         | 2      | 0.67%   |
| KIOXIA                      | 2         | 2      | 0.67%   |
| Gigabyte Technology         | 2         | 2      | 0.67%   |
| Dogfish                     | 2         | 2      | 0.67%   |
| Corsair                     | 2         | 2      | 0.67%   |
| China                       | 2         | 2      | 0.67%   |
| Union Memory (Shenzhen)     | 1         | 1      | 0.34%   |
| Union Memory                | 1         | 1      | 0.34%   |
| UMIS                        | 1         | 1      | 0.34%   |
| Teclast                     | 1         | 1      | 0.34%   |
| Team                        | 1         | 1      | 0.34%   |
| StoreJet                    | 1         | 1      | 0.34%   |
| SATADOM-SL                  | 1         | 1      | 0.34%   |
| Realtek Semiconductor       | 1         | 1      | 0.34%   |
| Phison Electronics          | 1         | 16     | 0.34%   |
| Patriot                     | 1         | 1      | 0.34%   |
| MyDigitalSSD                | 1         | 1      | 0.34%   |
| Mobius                      | 1         | 2      | 0.34%   |
| LITEON                      | 1         | 1      | 0.34%   |
| KIOXIA-EXCERIA              | 1         | 1      | 0.34%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 8         | 2.35%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB   | 7         | 2.05%   |
| Seagate ST500DM002-1BD142 500GB                     | 4         | 1.17%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB    | 4         | 1.17%   |
| Unknown MMC Card  64GB                              | 3         | 0.88%   |
| Seagate ST300MP0005 304GB                           | 3         | 0.88%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 3         | 0.88%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                 | 3         | 0.88%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 512GB  | 3         | 0.88%   |
| WDC WD5000AAKX-75U6AA0 500GB                        | 2         | 0.59%   |
| WDC WD2002FAEX-007BA0 2TB                           | 2         | 0.59%   |
| WDC WD Blue SA510 M.2 2280 1000GB                   | 2         | 0.59%   |
| Seagate ST9320325AS 320GB                           | 2         | 0.59%   |
| Seagate ST4000DM004-2CV104 4TB                      | 2         | 0.59%   |
| Seagate ST2000DM008-2FR102 2TB                      | 2         | 0.59%   |
| Seagate ST1000DM010-2EP102 1TB                      | 2         | 0.59%   |
| Seagate One Touch HDD 2TB                           | 2         | 0.59%   |
| Samsung SSD 980 1TB                                 | 2         | 0.59%   |
| Samsung SSD 870 EVO 1TB                             | 2         | 0.59%   |
| Samsung SSD 860 EVO 1TB                             | 2         | 0.59%   |
| SABRENT Disk 500GB                                  | 2         | 0.59%   |
| PNY CS900 240GB SSD                                 | 2         | 0.59%   |
| Lexar 512GB SSD                                     | 2         | 0.59%   |
| Kingston SA400S37120G 120GB SSD                     | 2         | 0.59%   |
| Intel SSD 660P Series 1024GB                        | 2         | 0.59%   |
| Gigabyte GP-GSTFS31240GNTD 240GB                    | 2         | 0.59%   |
| Crucial CT240BX500SSD1 240GB                        | 2         | 0.59%   |
| Crucial CT1000MX500SSD1 1TB                         | 2         | 0.59%   |
| A-DATA SWORDFISH 1TB                                | 2         | 0.59%   |
| WDC WDS500G1R0A-68A4W0 500GB SSD                    | 1         | 0.29%   |
| WDC WDS480G2G0A-00JH30 480GB SSD                    | 1         | 0.29%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD                    | 1         | 0.29%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 1         | 0.29%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 1         | 0.29%   |
| WDC WDS100T1X0E-00AFY0 1TB                          | 1         | 0.29%   |
| WDC WDS100T1R0A-68A4W0 1TB SSD                      | 1         | 0.29%   |
| WDC WDBNCE0010PNC 1TB SSD                           | 1         | 0.29%   |
| WDC WD80EZZX-11CSGA0 8TB                            | 1         | 0.29%   |
| WDC WD80EMAZ-00WJTA0 8TB                            | 1         | 0.29%   |
| WDC WD80EDAZ-11TA3A0 8TB                            | 1         | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 38        | 106    | 41.3%   |
| WDC                 | 25        | 47     | 27.17%  |
| Hitachi             | 9         | 14     | 9.78%   |
| Toshiba             | 8         | 10     | 8.7%    |
| Samsung Electronics | 3         | 5      | 3.26%   |
| Unknown             | 2         | 2      | 2.17%   |
| HGST                | 2         | 2      | 2.17%   |
| StoreJet            | 1         | 1      | 1.09%   |
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
| Samsung Electronics | 20        | 25     | 20.41%  |
| WDC                 | 9         | 12     | 9.18%   |
| SanDisk             | 9         | 10     | 9.18%   |
| Crucial             | 8         | 9      | 8.16%   |
| Kingston            | 6         | 6      | 6.12%   |
| Toshiba             | 5         | 5      | 5.1%    |
| Intel               | 4         | 6      | 4.08%   |
| PNY                 | 3         | 4      | 3.06%   |
| Micron Technology   | 3         | 3      | 3.06%   |
| SK hynix            | 2         | 2      | 2.04%   |
| SABRENT             | 2         | 2      | 2.04%   |
| LITEONIT            | 2         | 2      | 2.04%   |
| Gigabyte Technology | 2         | 2      | 2.04%   |
| Dogfish             | 2         | 2      | 2.04%   |
| China               | 2         | 2      | 2.04%   |
| Teclast             | 1         | 1      | 1.02%   |
| Team                | 1         | 1      | 1.02%   |
| SATADOM-SL          | 1         | 1      | 1.02%   |
| Patriot             | 1         | 1      | 1.02%   |
| MyDigitalSSD        | 1         | 1      | 1.02%   |
| LITEON              | 1         | 1      | 1.02%   |
| Lexar               | 1         | 1      | 1.02%   |
| KingFast            | 1         | 1      | 1.02%   |
| INDMEM              | 1         | 1      | 1.02%   |
| GOODRAM             | 1         | 1      | 1.02%   |
| EAGET               | 1         | 1      | 1.02%   |
| DUEX-120GB          | 1         | 1      | 1.02%   |
| Digma               | 1         | 1      | 1.02%   |
| Corsair             | 1         | 1      | 1.02%   |
| ASMT                | 1         | 1      | 1.02%   |
| Apacer              | 1         | 1      | 1.02%   |
| ADATA SU            | 1         | 1      | 1.02%   |
| A-DATA Technology   | 1         | 1      | 1.02%   |
| Unknown             | 1         | 1      | 1.02%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 97        | 140    | 36.88%  |
| SSD     | 84        | 111    | 31.94%  |
| HDD     | 71        | 192    | 27%     |
| MMC     | 6         | 6      | 2.28%   |
| Unknown | 5         | 8      | 1.9%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 128       | 285    | 51.82%  |
| NVMe | 97        | 140    | 39.27%  |
| SAS  | 16        | 26     | 6.48%   |
| MMC  | 6         | 6      | 2.43%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 79        | 119    | 46.75%  |
| 0.51-1.0   | 47        | 91     | 27.81%  |
| 1.01-2.0   | 23        | 38     | 13.61%  |
| 3.01-4.0   | 11        | 32     | 6.51%   |
| 4.01-10.0  | 4         | 16     | 2.37%   |
| 2.01-3.0   | 2         | 2      | 1.18%   |
| 10.01-20.0 | 2         | 3      | 1.18%   |
| 20.01-50.0 | 1         | 2      | 0.59%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 56        | 27.18%  |
| 251-500        | 42        | 20.39%  |
| 501-1000       | 35        | 16.99%  |
| 1001-2000      | 24        | 11.65%  |
| More than 3000 | 21        | 10.19%  |
| 51-100         | 9         | 4.37%   |
| 2001-3000      | 8         | 3.88%   |
| Unknown        | 5         | 2.43%   |
| 1-20           | 4         | 1.94%   |
| 21-50          | 2         | 0.97%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 73        | 34.76%  |
| 21-50          | 45        | 21.43%  |
| 51-100         | 25        | 11.9%   |
| 101-250        | 20        | 9.52%   |
| 501-1000       | 13        | 6.19%   |
| 251-500        | 12        | 5.71%   |
| More than 3000 | 9         | 4.29%   |
| 1001-2000      | 5         | 2.38%   |
| Unknown        | 5         | 2.38%   |
| 2001-3000      | 3         | 1.43%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD5000AAKX-75U6AA0 500GB          | 1         | 1      | 5%      |
| WDC WD40EZRZ-00WN9B0 4TB              | 1         | 1      | 5%      |
| WDC WD40 EFRX-68N32N0 4TB             | 1         | 1      | 5%      |
| WDC WD1001FALS-00J7B1 1TB             | 1         | 2      | 5%      |
| WDC WD1001FALS-00J7B0 1TB             | 1         | 4      | 5%      |
| Toshiba MK1059GSM 1TB                 | 1         | 1      | 5%      |
| Seagate ST9500325AS 500GB             | 1         | 1      | 5%      |
| Seagate ST9320325AS 320GB             | 1         | 1      | 5%      |
| Seagate ST8000AS0002-1NA17Z 8TB       | 1         | 1      | 5%      |
| Seagate ST4000NM0033-9ZM170 4TB       | 1         | 10     | 5%      |
| Seagate ST31000528AS 1TB              | 1         | 2      | 5%      |
| Seagate ST2000DM008-2FR102 2TB        | 1         | 2      | 5%      |
| Intel SSDSC2KB960G8 960GB             | 1         | 2      | 5%      |
| Intel SSD 600P Series 256GB           | 1         | 2      | 5%      |
| IBM ST3500641NS 39M4517 39M0181 500GB | 1         | 1      | 5%      |
| Hitachi HTS727575A9E364 752GB         | 1         | 1      | 5%      |
| Hitachi HDS725050KLA360 500GB         | 1         | 1      | 5%      |
| Hitachi HDS721010CLA632 1TB           | 1         | 1      | 5%      |
| Crucial CT1050MX300SSD1 1050GB        | 1         | 1      | 5%      |
| Corsair Neutron SSD 64GB              | 1         | 1      | 5%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 17     | 30%     |
| WDC     | 5         | 9      | 25%     |
| Hitachi | 3         | 3      | 15%     |
| Intel   | 2         | 4      | 10%     |
| Toshiba | 1         | 1      | 5%      |
| IBM     | 1         | 1      | 5%      |
| Crucial | 1         | 1      | 5%      |
| Corsair | 1         | 1      | 5%      |

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
| HDD  | 14        | 31     | 77.78%  |
| SSD  | 3         | 4      | 16.67%  |
| NVMe | 1         | 2      | 5.56%   |

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
| Works    | 130       | 290    | 57.27%  |
| Detected | 79        | 129    | 34.8%   |
| Malfunc  | 17        | 37     | 7.49%   |
| Failed   | 1         | 1      | 0.44%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 130       | 45.14%  |
| AMD                          | 40        | 13.89%  |
| Samsung Electronics          | 36        | 12.5%   |
| SanDisk                      | 10        | 3.47%   |
| LSI Logic / Symbios Logic    | 9         | 3.13%   |
| SK hynix                     | 7         | 2.43%   |
| Micron Technology            | 7         | 2.43%   |
| Phison Electronics           | 5         | 1.74%   |
| Kingston Technology Company  | 5         | 1.74%   |
| Broadcom / LSI               | 5         | 1.74%   |
| ASMedia Technology           | 5         | 1.74%   |
| Micron/Crucial Technology    | 4         | 1.39%   |
| MAXIO Technology (Hangzhou)  | 4         | 1.39%   |
| Toshiba America Info Systems | 3         | 1.04%   |
| Realtek Semiconductor        | 3         | 1.04%   |
| KIOXIA                       | 3         | 1.04%   |
| Union Memory (Shenzhen)      | 2         | 0.69%   |
| Marvell Technology Group     | 2         | 0.69%   |
| Hewlett-Packard              | 2         | 0.69%   |
| VIA Technologies             | 1         | 0.35%   |
| Silicon Motion               | 1         | 0.35%   |
| Shenzhen Longsys Electronics | 1         | 0.35%   |
| JMicron Technology           | 1         | 0.35%   |
| ADATA Technology             | 1         | 0.35%   |
| Adaptec                      | 1         | 0.35%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 24        | 7.23%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 15        | 4.52%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 11        | 3.31%   |
| Intel SATA Controller [RAID Mode]                                                       | 10        | 3.01%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 9         | 2.71%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 6         | 1.81%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 6         | 1.81%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 6         | 1.81%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 6         | 1.81%   |
| AMD 400 Series Chipset SATA Controller                                                  | 6         | 1.81%   |
| Micron 3400 NVMe SSD [Hendrix]                                                          | 5         | 1.51%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 5         | 1.51%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                           | 5         | 1.51%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                            | 5         | 1.51%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5         | 1.51%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5         | 1.51%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5         | 1.51%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 4         | 1.2%    |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 4         | 1.2%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 4         | 1.2%    |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 4         | 1.2%    |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 4         | 1.2%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4         | 1.2%    |
| AMD 600 Series Chipset SATA Controller                                                  | 4         | 1.2%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 3         | 0.9%    |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                                | 3         | 0.9%    |
| LSI Logic / Symbios Logic MegaRAID SAS 1078                                             | 3         | 0.9%    |
| Intel Tiger Lake-LP SATA Controller                                                     | 3         | 0.9%    |
| Intel SSD 670p Series [Keystone Harbor]                                                 | 3         | 0.9%    |
| Intel SSD 660P Series                                                                   | 3         | 0.9%    |
| Intel Jasper Lake SATA AHCI Controller                                                  | 3         | 0.9%    |
| Intel Comet Lake SATA AHCI Controller                                                   | 3         | 0.9%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 3         | 0.9%    |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 3         | 0.9%    |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 3         | 0.9%    |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 3         | 0.9%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 3         | 0.9%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3         | 0.9%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3         | 0.9%    |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 3         | 0.9%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 126       | 43.3%   |
| NVMe | 97        | 33.33%  |
| RAID | 31        | 10.65%  |
| IDE  | 29        | 9.97%   |
| SAS  | 6         | 2.06%   |
| SCSI | 2         | 0.69%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 152       | 74.88%  |
| AMD    | 50        | 24.63%  |
| ARM    | 1         | 0.49%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-2600 CPU @ 3.40GHz        | 4         | 1.97%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 4         | 1.97%   |
| Intel Xeon CPU L5530 @ 2.40GHz          | 3         | 1.48%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 3         | 1.48%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 3         | 1.48%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 3         | 1.48%   |
| Intel 12th Gen Core i7-1260P            | 3         | 1.48%   |
| Intel Xeon Gold 6130 CPU @ 2.10GHz      | 2         | 0.99%   |
| Intel Xeon CPU E5-2665 0 @ 2.40GHz      | 2         | 0.99%   |
| Intel Core i7-4770 CPU @ 3.40GHz        | 2         | 0.99%   |
| Intel Core i7-10610U CPU @ 1.80GHz      | 2         | 0.99%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 2         | 0.99%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 2         | 0.99%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 2         | 0.99%   |
| Intel Celeron N5105 @ 2.00GHz           | 2         | 0.99%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 2         | 0.99%   |
| Intel 12th Gen Core i7-12700H           | 2         | 0.99%   |
| Intel 12th Gen Core i5-12400F           | 2         | 0.99%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz | 2         | 0.99%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz  | 2         | 0.99%   |
| AMD FX-8350 Eight-Core Processor        | 2         | 0.99%   |
| Intel Xeon Silver 4216 CPU @ 2.10GHz    | 1         | 0.49%   |
| Intel Xeon Platinum 8124M CPU @ 3.00GHz | 1         | 0.49%   |
| Intel Xeon Gold 6338 CPU @ 2.00GHz      | 1         | 0.49%   |
| Intel Xeon Gold 6242R CPU @ 3.10GHz     | 1         | 0.49%   |
| Intel Xeon Gold 6134 CPU @ 3.20GHz      | 1         | 0.49%   |
| Intel Xeon E-2244G CPU @ 3.80GHz        | 1         | 0.49%   |
| Intel Xeon CPU X7560 @ 2.27GHz          | 1         | 0.49%   |
| Intel Xeon CPU X5680 @ 3.33GHz          | 1         | 0.49%   |
| Intel Xeon CPU X5670 @ 2.93GHz          | 1         | 0.49%   |
| Intel Xeon CPU E5620 @ 2.40GHz          | 1         | 0.49%   |
| Intel Xeon CPU E5-2690 v3 @ 2.60GHz     | 1         | 0.49%   |
| Intel Xeon CPU E5-2687W v2 @ 3.40GHz    | 1         | 0.49%   |
| Intel Xeon CPU E5-2680 v4 @ 2.40GHz     | 1         | 0.49%   |
| Intel Xeon CPU E5-2630 v3 @ 2.40GHz     | 1         | 0.49%   |
| Intel Xeon CPU E5-2620 v2 @ 2.10GHz     | 1         | 0.49%   |
| Intel Xeon CPU E5-2620 0 @ 2.00GHz      | 1         | 0.49%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz      | 1         | 0.49%   |
| Intel Xeon CPU E31230 @ 3.20GHz         | 1         | 0.49%   |
| Intel Xeon CPU E3110 @ 3.00GHz          | 1         | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 43        | 21.18%  |
| Other                   | 31        | 15.27%  |
| Intel Core i5           | 30        | 14.78%  |
| Intel Xeon              | 21        | 10.34%  |
| AMD Ryzen 7             | 10        | 4.93%   |
| Intel Celeron           | 8         | 3.94%   |
| AMD Ryzen 9             | 8         | 3.94%   |
| AMD Ryzen 5             | 8         | 3.94%   |
| Intel Core i3           | 6         | 2.96%   |
| Intel Xeon Gold         | 5         | 2.46%   |
| AMD Ryzen 5 PRO         | 4         | 1.97%   |
| AMD FX                  | 3         | 1.48%   |
| Intel Pentium Dual-Core | 2         | 0.99%   |
| Intel Core i9           | 2         | 0.99%   |
| Intel Atom              | 2         | 0.99%   |
| AMD Ryzen Threadripper  | 2         | 0.99%   |
| AMD Ryzen 3             | 2         | 0.99%   |
| AMD A8                  | 2         | 0.99%   |
| Intel Xeon Silver       | 1         | 0.49%   |
| Intel Xeon Platinum     | 1         | 0.49%   |
| Intel Pentium Silver    | 1         | 0.49%   |
| Intel Pentium Dual      | 1         | 0.49%   |
| Intel Core 2 Quad       | 1         | 0.49%   |
| Intel Core 2 Duo        | 1         | 0.49%   |
| AMD Sempron             | 1         | 0.49%   |
| AMD Ryzen Embedded      | 1         | 0.49%   |
| AMD Ryzen 7 PRO         | 1         | 0.49%   |
| AMD Phenom II X6        | 1         | 0.49%   |
| AMD EPYC                | 1         | 0.49%   |
| AMD Athlon II X2        | 1         | 0.49%   |
| AMD A4                  | 1         | 0.49%   |
| AMD A10                 | 1         | 0.49%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 75        | 36.95%  |
| 2      | 38        | 18.72%  |
| 6      | 27        | 13.3%   |
| 8      | 25        | 12.32%  |
| 12     | 10        | 4.93%   |
| 10     | 8         | 3.94%   |
| 16     | 6         | 2.96%   |
| 32     | 3         | 1.48%   |
| 24     | 3         | 1.48%   |
| 14     | 2         | 0.99%   |
| 64     | 1         | 0.49%   |
| 40     | 1         | 0.49%   |
| 36     | 1         | 0.49%   |
| 28     | 1         | 0.49%   |
| 3      | 1         | 0.49%   |
| 1      | 1         | 0.49%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 185       | 91.13%  |
| 2      | 17        | 8.37%   |
| 4      | 1         | 0.49%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 156       | 76.47%  |
| 1      | 48        | 23.53%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 203       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 23        | 11.22%  |
| 0x306c3    | 12        | 5.85%   |
| 0x206a7    | 10        | 4.88%   |
| 0x806c1    | 8         | 3.9%    |
| 0x306a9    | 8         | 3.9%    |
| 0x806ea    | 7         | 3.41%   |
| 0x506e3    | 7         | 3.41%   |
| 0x806ec    | 6         | 2.93%   |
| 0xa0652    | 5         | 2.44%   |
| 0x50654    | 5         | 2.44%   |
| 0x0a50000c | 5         | 2.44%   |
| 0x906a3    | 4         | 1.95%   |
| 0x906ea    | 3         | 1.46%   |
| 0x906c0    | 3         | 1.46%   |
| 0x806e9    | 3         | 1.46%   |
| 0x706a8    | 3         | 1.46%   |
| 0x206d7    | 3         | 1.46%   |
| 0x206c2    | 3         | 1.46%   |
| 0x0a601203 | 3         | 1.46%   |
| 0x0a404102 | 3         | 1.46%   |
| 0xa0671    | 2         | 0.98%   |
| 0xa0655    | 2         | 0.98%   |
| 0xa0653    | 2         | 0.98%   |
| 0x906a4    | 2         | 0.98%   |
| 0x90675    | 2         | 0.98%   |
| 0x90672    | 2         | 0.98%   |
| 0x406f1    | 2         | 0.98%   |
| 0x40651    | 2         | 0.98%   |
| 0x306e4    | 2         | 0.98%   |
| 0x306d4    | 2         | 0.98%   |
| 0x106a5    | 2         | 0.98%   |
| 0x1067a    | 2         | 0.98%   |
| 0x10676    | 2         | 0.98%   |
| 0x0a50000d | 2         | 0.98%   |
| 0x08608103 | 2         | 0.98%   |
| 0x08600106 | 2         | 0.98%   |
| 0x08600104 | 2         | 0.98%   |
| 0x0800820d | 2         | 0.98%   |
| 0x06006705 | 2         | 0.98%   |
| 0x06001119 | 2         | 0.98%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 23        | 11.33%  |
| Haswell          | 19        | 9.36%   |
| Skylake          | 16        | 7.88%   |
| Alderlake Hybrid | 16        | 7.88%   |
| SandyBridge      | 14        | 6.9%    |
| Unknown          | 12        | 5.91%   |
| IvyBridge        | 11        | 5.42%   |
| Zen 3            | 10        | 4.93%   |
| CometLake        | 10        | 4.93%   |
| Zen 2            | 8         | 3.94%   |
| TigerLake        | 8         | 3.94%   |
| Piledriver       | 6         | 2.96%   |
| Icelake          | 6         | 2.96%   |
| Westmere         | 5         | 2.46%   |
| Penryn           | 5         | 2.46%   |
| Nehalem          | 5         | 2.46%   |
| Zen+             | 4         | 1.97%   |
| Zen              | 4         | 1.97%   |
| Goldmont plus    | 4         | 1.97%   |
| Broadwell        | 4         | 1.97%   |
| Tremont          | 3         | 1.48%   |
| K10              | 3         | 1.48%   |
| Silvermont       | 2         | 0.99%   |
| Excavator        | 2         | 0.99%   |
| K10 Llano        | 1         | 0.49%   |
| Jaguar           | 1         | 0.49%   |
| Core             | 1         | 0.49%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 106       | 42.57%  |
| Nvidia                     | 75        | 30.12%  |
| AMD                        | 51        | 20.48%  |
| Matrox Electronics Systems | 9         | 3.61%   |
| ASPEED Technology          | 8         | 3.21%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 8         | 3.16%   |
| ASPEED Technology ASPEED Graphics Family                                    | 8         | 3.16%   |
| Intel UHD Graphics 620                                                      | 7         | 2.77%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 7         | 2.77%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 6         | 2.37%   |
| Matrox Electronics Systems MGA G200eW WPCM450                               | 5         | 1.98%   |
| Intel HD Graphics 530                                                       | 5         | 1.98%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 5         | 1.98%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                   | 5         | 1.98%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 5         | 1.98%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 5         | 1.98%   |
| Nvidia GK208B [GeForce GT 730]                                              | 4         | 1.58%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 4         | 1.58%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                 | 4         | 1.58%   |
| AMD Rembrandt [Radeon 680M]                                                 | 4         | 1.58%   |
| AMD Raphael                                                                 | 4         | 1.58%   |
| Nvidia GK106GLM [Quadro K2100M]                                             | 3         | 1.19%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 3         | 1.19%   |
| Intel JasperLake [UHD Graphics]                                             | 3         | 1.19%   |
| Intel HD Graphics 620                                                       | 3         | 1.19%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 3         | 1.19%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 3         | 1.19%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 3         | 1.19%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]               | 3         | 1.19%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                  | 2         | 0.79%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                       | 2         | 0.79%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2         | 0.79%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 2         | 0.79%   |
| Nvidia GP107GL [Quadro P400]                                                | 2         | 0.79%   |
| Nvidia GM108M [GeForce 940M]                                                | 2         | 0.79%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 2         | 0.79%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 2         | 0.79%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 2         | 0.79%   |
| Matrox Electronics Systems G200eR2                                          | 2         | 0.79%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 2         | 0.79%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 2         | 0.79%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                      | 2         | 0.79%   |
| Intel HD Graphics 5500                                                      | 2         | 0.79%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 2         | 0.79%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 2         | 0.79%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 74        | 36.45%  |
| 1 x Nvidia      | 36        | 17.73%  |
| 1 x AMD         | 34        | 16.75%  |
| Intel + Nvidia  | 27        | 13.3%   |
| AMD + Nvidia    | 8         | 3.94%   |
| 1 x Matrox      | 7         | 3.45%   |
| 1 x ASPEED      | 4         | 1.97%   |
| 2 x AMD         | 3         | 1.48%   |
| Intel + AMD     | 3         | 1.48%   |
| Nvidia + ASPEED | 2         | 0.99%   |
| AMD + ASPEED    | 2         | 0.99%   |
| Other           | 1         | 0.49%   |
| Nvidia + Matrox | 1         | 0.49%   |
| AMD + Matrox    | 1         | 0.49%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 165       | 80.88%  |
| Proprietary | 29        | 14.22%  |
| Unknown     | 10        | 4.9%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 104       | 50.73%  |
| 1.01-2.0   | 25        | 12.2%   |
| 0.01-0.5   | 24        | 11.71%  |
| 3.01-4.0   | 16        | 7.8%    |
| 0.51-1.0   | 15        | 7.32%   |
| 7.01-8.0   | 5         | 2.44%   |
| 8.01-16.0  | 5         | 2.44%   |
| 5.01-6.0   | 4         | 1.95%   |
| 2.01-3.0   | 3         | 1.46%   |
| 16.01-24.0 | 3         | 1.46%   |
| 32.01-64.0 | 1         | 0.49%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 25        | 11.31%  |
| Samsung Electronics     | 24        | 10.86%  |
| Goldstar                | 18        | 8.14%   |
| AU Optronics            | 18        | 8.14%   |
| LG Display              | 17        | 7.69%   |
| BOE                     | 16        | 7.24%   |
| Chimei Innolux          | 13        | 5.88%   |
| Hewlett-Packard         | 9         | 4.07%   |
| Acer                    | 8         | 3.62%   |
| Philips                 | 7         | 3.17%   |
| Sharp                   | 6         | 2.71%   |
| BenQ                    | 6         | 2.71%   |
| AOC                     | 6         | 2.71%   |
| Ancor Communications    | 5         | 2.26%   |
| Lenovo                  | 3         | 1.36%   |
| InfoVision              | 3         | 1.36%   |
| Iiyama                  | 3         | 1.36%   |
| Eizo                    | 3         | 1.36%   |
| ViewSonic               | 2         | 0.9%    |
| Sony                    | 2         | 0.9%    |
| SGT                     | 2         | 0.9%    |
| Sceptre Tech            | 2         | 0.9%    |
| PANDA                   | 2         | 0.9%    |
| CSO                     | 2         | 0.9%    |
| ASUSTek Computer        | 2         | 0.9%    |
| Apple                   | 2         | 0.9%    |
| Xiaomi                  | 1         | 0.45%   |
| Vizio                   | 1         | 0.45%   |
| Panasonic               | 1         | 0.45%   |
| OEM                     | 1         | 0.45%   |
| NEC Computers           | 1         | 0.45%   |
| LG Electronics          | 1         | 0.45%   |
| IBM                     | 1         | 0.45%   |
| HUAWEI                  | 1         | 0.45%   |
| Hitachi                 | 1         | 0.45%   |
| HCL                     | 1         | 0.45%   |
| Gigabyte Technology     | 1         | 0.45%   |
| EDI                     | 1         | 0.45%   |
| Chi Mei Optoelectronics | 1         | 0.45%   |
| ADR                     | 1         | 0.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 2         | 0.87%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 0.87%   |
| Goldstar ULTRAWIDE GSM76F6 3440x1440 800x335mm 34.1-inch              | 2         | 0.87%   |
| Goldstar LG ULTRAWIDE GSM76FD 2560x1080 800x340mm 34.2-inch           | 2         | 0.87%   |
| Dell S3422DWG DELD124 3440x1440 797x334mm 34.0-inch                   | 2         | 0.87%   |
| Dell P2317H DEL40F4 1920x1080 509x286mm 23.0-inch                     | 2         | 0.87%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch        | 2         | 0.87%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.87%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch        | 2         | 0.87%   |
| AOC 27G2G8 AOC2702 1920x1080 598x336mm 27.0-inch                      | 2         | 0.87%   |
| Xiaomi Mi TV XMD00E1 3840x2160 708x398mm 32.0-inch                    | 1         | 0.43%   |
| Vizio E24-C1 VIZ1005 1920x1080 521x293mm 23.5-inch                    | 1         | 0.43%   |
| ViewSonic VS2210-FHD VSC1939 1920x1080 476x268mm 21.5-inch            | 1         | 0.43%   |
| ViewSonic VA902b VSC211C 1280x1024 376x301mm 19.0-inch                | 1         | 0.43%   |
| Sony TV *02 SNY045B 1920x1080 1085x610mm 49.0-inch                    | 1         | 0.43%   |
| Sony LCD Monitor MS_003C 1366x768 309x173mm 13.9-inch                 | 1         | 0.43%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch               | 1         | 0.43%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 1         | 0.43%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 1         | 0.43%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 1         | 0.43%   |
| Sharp LCD Monitor SHP1491 3840x2160 346x194mm 15.6-inch               | 1         | 0.43%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 1         | 0.43%   |
| SGT L156 SGT1560 1366x768 452x254mm 20.4-inch                         | 1         | 0.43%   |
| SGT F156P1 SGT1600 1920x1080 345x194mm 15.6-inch                      | 1         | 0.43%   |
| Sceptre Tech X246W-1080p SPT2303 1920x1080 521x293mm 23.5-inch        | 1         | 0.43%   |
| Sceptre Tech X240-CNC SPT0978 1920x1080 880x490mm 39.7-inch           | 1         | 0.43%   |
| Samsung Electronics U32R59x SAM0F96 3840x2160 697x392mm 31.5-inch     | 1         | 0.43%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch     | 1         | 0.43%   |
| Samsung Electronics SyncMaster SAM062E 1280x1024 376x301mm 19.0-inch  | 1         | 0.43%   |
| Samsung Electronics SyncMaster SAM0564 1360x768 410x230mm 18.5-inch   | 1         | 0.43%   |
| Samsung Electronics SyncMaster SAM0467 1920x1200 518x324mm 24.1-inch  | 1         | 0.43%   |
| Samsung Electronics SyncMaster SAM0215 1280x1024 338x270mm 17.0-inch  | 1         | 0.43%   |
| Samsung Electronics SMS23A350H SAM07D4 1920x1080 509x286mm 23.0-inch  | 1         | 0.43%   |
| Samsung Electronics S34J55x SAM0F71 3440x1440 800x330mm 34.1-inch     | 1         | 0.43%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch     | 1         | 0.43%   |
| Samsung Electronics LF27T450F SAM7099 1920x1080 597x336mm 27.0-inch   | 1         | 0.43%   |
| Samsung Electronics LF27T35 SAM7080 1920x1080 598x337mm 27.0-inch     | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch  | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SDC416E 2880x1620 344x194mm 15.5-inch | 1         | 0.43%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 89        | 41.98%  |
| 3840x2160 (4K)     | 18        | 8.49%   |
| 1366x768 (WXGA)    | 18        | 8.49%   |
| 2560x1440 (QHD)    | 13        | 6.13%   |
| 1920x1200 (WUXGA)  | 12        | 5.66%   |
| 1280x1024 (SXGA)   | 11        | 5.19%   |
| 3440x1440          | 8         | 3.77%   |
| 1600x900 (HD+)     | 7         | 3.3%    |
| 2560x1080          | 6         | 2.83%   |
| 3840x1080          | 4         | 1.89%   |
| 1680x1050 (WSXGA+) | 4         | 1.89%   |
| 3840x2400          | 3         | 1.42%   |
| 1024x768 (XGA)     | 3         | 1.42%   |
| Unknown            | 3         | 1.42%   |
| 1920x540           | 2         | 0.94%   |
| 1440x900 (WXGA+)   | 2         | 0.94%   |
| 7680x2160          | 1         | 0.47%   |
| 3072x1920          | 1         | 0.47%   |
| 2880x1800          | 1         | 0.47%   |
| 2880x1620          | 1         | 0.47%   |
| 2240x1400          | 1         | 0.47%   |
| 2160x1440          | 1         | 0.47%   |
| 1920x550           | 1         | 0.47%   |
| 1360x768           | 1         | 0.47%   |
| 1280x768           | 1         | 0.47%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 41        | 18.39%  |
| 14      | 28        | 12.56%  |
| 27      | 22        | 9.87%   |
| 24      | 19        | 8.52%   |
| 34      | 13        | 5.83%   |
| 23      | 13        | 5.83%   |
| 17      | 12        | 5.38%   |
| 13      | 12        | 5.38%   |
| 31      | 9         | 4.04%   |
| 19      | 8         | 3.59%   |
| 21      | 7         | 3.14%   |
| Unknown | 7         | 3.14%   |
| 20      | 4         | 1.79%   |
| 18      | 4         | 1.79%   |
| 40      | 3         | 1.35%   |
| 22      | 3         | 1.35%   |
| 16      | 3         | 1.35%   |
| 65      | 2         | 0.9%    |
| 48      | 2         | 0.9%    |
| 32      | 2         | 0.9%    |
| 84      | 1         | 0.45%   |
| 54      | 1         | 0.45%   |
| 49      | 1         | 0.45%   |
| 39      | 1         | 0.45%   |
| 36      | 1         | 0.45%   |
| 35      | 1         | 0.45%   |
| 28      | 1         | 0.45%   |
| 25      | 1         | 0.45%   |
| 12      | 1         | 0.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 81        | 36.65%  |
| 501-600     | 51        | 23.08%  |
| 401-500     | 23        | 10.41%  |
| 701-800     | 16        | 7.24%   |
| 351-400     | 13        | 5.88%   |
| 601-700     | 10        | 4.52%   |
| 201-300     | 8         | 3.62%   |
| Unknown     | 7         | 3.17%   |
| 1001-1500   | 6         | 2.71%   |
| 801-900     | 5         | 2.26%   |
| 1501-2000   | 1         | 0.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 137       | 69.19%  |
| 16/10   | 22        | 11.11%  |
| 21/9    | 13        | 6.57%   |
| 5/4     | 10        | 5.05%   |
| Unknown | 5         | 2.53%   |
| 32/9    | 4         | 2.02%   |
| 4/3     | 3         | 1.52%   |
| 3/2     | 3         | 1.52%   |
| 6/5     | 1         | 0.51%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 41        | 18.55%  |
| 201-250        | 35        | 15.84%  |
| 81-90          | 34        | 15.38%  |
| 351-500        | 25        | 11.31%  |
| 301-350        | 22        | 9.95%   |
| 151-200        | 13        | 5.88%   |
| 141-150        | 9         | 4.07%   |
| 501-1000       | 9         | 4.07%   |
| 121-130        | 7         | 3.17%   |
| Unknown        | 7         | 3.17%   |
| 251-300        | 5         | 2.26%   |
| More than 1000 | 4         | 1.81%   |
| 111-120        | 4         | 1.81%   |
| 71-80          | 3         | 1.36%   |
| 91-100         | 2         | 0.9%    |
| 61-70          | 1         | 0.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 90        | 41.28%  |
| 121-160       | 60        | 27.52%  |
| 101-120       | 34        | 15.6%   |
| 161-240       | 16        | 7.34%   |
| More than 240 | 8         | 3.67%   |
| Unknown       | 7         | 3.21%   |
| 1-50          | 3         | 1.38%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 133       | 65.2%   |
| 2     | 40        | 19.61%  |
| 0     | 26        | 12.75%  |
| 3     | 4         | 1.96%   |
| 4     | 1         | 0.49%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 129       | 41.61%  |
| Realtek Semiconductor     | 94        | 30.32%  |
| Broadcom                  | 17        | 5.48%   |
| MediaTek                  | 13        | 4.19%   |
| Qualcomm Atheros          | 11        | 3.55%   |
| Mellanox Technologies     | 6         | 1.94%   |
| ASIX Electronics          | 6         | 1.94%   |
| Ralink Technology         | 4         | 1.29%   |
| Lenovo                    | 4         | 1.29%   |
| Aquantia                  | 4         | 1.29%   |
| Broadcom Limited          | 3         | 0.97%   |
| Ralink                    | 2         | 0.65%   |
| Marvell Technology Group  | 2         | 0.65%   |
| Linksys                   | 2         | 0.65%   |
| American Megatrends       | 2         | 0.65%   |
| TP-Link                   | 1         | 0.32%   |
| Spreadtrum Communications | 1         | 0.32%   |
| Solarflare Communications | 1         | 0.32%   |
| Qualcomm                  | 1         | 0.32%   |
| Microsoft                 | 1         | 0.32%   |
| JMicron Technology        | 1         | 0.32%   |
| InterBiometrics           | 1         | 0.32%   |
| Dell                      | 1         | 0.32%   |
| D-Link                    | 1         | 0.32%   |
| BUFFALO                   | 1         | 0.32%   |
| ASUSTek Computer          | 1         | 0.32%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                                                  | Computers | Percent |
|------------------------------------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller                                                 | 60        | 16%     |
| Realtek RTL8153 Gigabit Ethernet Adapter                                                                               | 14        | 3.73%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                                                  | 11        | 2.93%   |
| Realtek RTL8125 2.5GbE Controller                                                                                      | 9         | 2.4%    |
| Intel Wireless 8265 / 8275                                                                                             | 8         | 2.13%   |
| Intel Wi-Fi 6 AX200                                                                                                    | 8         | 2.13%   |
| Intel Ethernet Controller I225-V                                                                                       | 8         | 2.13%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                                                       | 8         | 2.13%   |
| Intel Ethernet Connection I217-LM                                                                                      | 7         | 1.87%   |
| Intel Wireless 7260                                                                                                    | 6         | 1.6%    |
| Intel Wi-Fi 6 AX201                                                                                                    | 6         | 1.6%    |
| Intel I211 Gigabit Network Connection                                                                                  | 6         | 1.6%    |
| ASIX AX88179 Gigabit Ethernet                                                                                          | 6         | 1.6%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                                                          | 5         | 1.33%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                                                              | 5         | 1.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                                           | 5         | 1.33%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                                                         | 5         | 1.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                                               | 4         | 1.07%   |
| Intel Wireless 7265                                                                                                    | 4         | 1.07%   |
| Intel Wireless 3165                                                                                                    | 4         | 1.07%   |
| Intel Ethernet Connection (4) I219-LM                                                                                  | 4         | 1.07%   |
| Intel Comet Lake PCH CNVi WiFi                                                                                         | 4         | 1.07%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                                                            | 3         | 0.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                                               | 3         | 0.8%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                                                  | 3         | 0.8%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                                             | 3         | 0.8%    |
| Mellanox MT25408A0-FCC-QI ConnectX, Dual Port 40Gb/s InfiniBand / 10GigE Adapter IC with PCIe 2.0 x8 5.0GT/s Interface | 3         | 0.8%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                                                                | 3         | 0.8%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                                                          | 3         | 0.8%    |
| Intel Wireless 8260                                                                                                    | 3         | 0.8%    |
| Intel I210 Gigabit Network Connection                                                                                  | 3         | 0.8%    |
| Intel Ethernet Controller X550                                                                                         | 3         | 0.8%    |
| Intel Ethernet Connection (4) I219-V                                                                                   | 3         | 0.8%    |
| Intel Ethernet Connection (2) I219-LM                                                                                  | 3         | 0.8%    |
| Intel Ethernet Connection (17) I219-V                                                                                  | 3         | 0.8%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                                                                      | 3         | 0.8%    |
| Intel 82574L Gigabit Network Connection                                                                                | 3         | 0.8%    |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G]                                         | 3         | 0.8%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                                                                     | 2         | 0.53%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                                                      | 2         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 78        | 57.78%  |
| Realtek Semiconductor | 17        | 12.59%  |
| MediaTek              | 13        | 9.63%   |
| Qualcomm Atheros      | 10        | 7.41%   |
| Ralink Technology     | 4         | 2.96%   |
| Broadcom              | 3         | 2.22%   |
| Ralink                | 2         | 1.48%   |
| Linksys               | 2         | 1.48%   |
| TP-Link               | 1         | 0.74%   |
| Microsoft             | 1         | 0.74%   |
| Dell                  | 1         | 0.74%   |
| BUFFALO               | 1         | 0.74%   |
| Broadcom Limited      | 1         | 0.74%   |
| ASUSTek Computer      | 1         | 0.74%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                              | Computers | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                         | 8         | 5.84%   |
| Intel Wi-Fi 6 AX200                                                | 8         | 5.84%   |
| Intel Alder Lake-P PCH CNVi WiFi                                   | 8         | 5.84%   |
| Intel Wireless 7260                                                | 6         | 4.38%   |
| Intel Wi-Fi 6 AX201                                                | 6         | 4.38%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter      | 5         | 3.65%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]          | 5         | 3.65%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                       | 5         | 3.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter           | 4         | 2.92%   |
| Intel Wireless 7265                                                | 4         | 2.92%   |
| Intel Wireless 3165                                                | 4         | 2.92%   |
| Intel Comet Lake PCH CNVi WiFi                                     | 4         | 2.92%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller        | 3         | 2.19%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter           | 3         | 2.19%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter         | 3         | 2.19%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                            | 3         | 2.19%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter      | 3         | 2.19%   |
| Intel Wireless 8260                                                | 3         | 2.19%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                  | 3         | 2.19%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                 | 2         | 1.46%   |
| Ralink MT7601U Wireless Adapter                                    | 2         | 1.46%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                          | 2         | 1.46%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter         | 2         | 1.46%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter         | 2         | 1.46%   |
| Intel Centrino Wireless-N 2230                                     | 2         | 1.46%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                           | 2         | 1.46%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                | 1         | 0.73%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller [1T1R] | 1         | 0.73%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter            | 1         | 0.73%   |
| Realtek RTL8723DE Wireless Network Adapter                         | 1         | 0.73%   |
| Realtek RTL8191SEvB Wireless LAN Controller                        | 1         | 0.73%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter              | 1         | 0.73%   |
| Realtek 802.11ac NIC                                               | 1         | 0.73%   |
| Ralink RT5370 Wireless Adapter                                     | 1         | 0.73%   |
| Ralink RT3071 Wireless Adapter                                     | 1         | 0.73%   |
| Ralink RT2870/RT3070 Wireless Adapter                              | 1         | 0.73%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                   | 1         | 0.73%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                   | 1         | 0.73%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                   | 1         | 0.73%   |
| Microsoft Xbox 360 Wireless Adapter                                | 1         | 0.73%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Realtek Semiconductor     | 86        | 40%     |
| Intel                     | 86        | 40%     |
| Broadcom                  | 15        | 6.98%   |
| ASIX Electronics          | 6         | 2.79%   |
| Lenovo                    | 4         | 1.86%   |
| Aquantia                  | 4         | 1.86%   |
| Mellanox Technologies     | 2         | 0.93%   |
| Marvell Technology Group  | 2         | 0.93%   |
| Broadcom Limited          | 2         | 0.93%   |
| American Megatrends       | 2         | 0.93%   |
| Spreadtrum Communications | 1         | 0.47%   |
| Solarflare Communications | 1         | 0.47%   |
| Qualcomm Atheros          | 1         | 0.47%   |
| Qualcomm                  | 1         | 0.47%   |
| JMicron Technology        | 1         | 0.47%   |
| D-Link                    | 1         | 0.47%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 60        | 25.75%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 14        | 6.01%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 11        | 4.72%   |
| Realtek RTL8125 2.5GbE Controller                                              | 9         | 3.86%   |
| Intel Ethernet Controller I225-V                                               | 8         | 3.43%   |
| Intel Ethernet Connection I217-LM                                              | 7         | 3%      |
| Intel I211 Gigabit Network Connection                                          | 6         | 2.58%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 6         | 2.58%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                 | 5         | 2.15%   |
| Intel Ethernet Connection (4) I219-LM                                          | 4         | 1.72%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 3         | 1.29%   |
| Intel I210 Gigabit Network Connection                                          | 3         | 1.29%   |
| Intel Ethernet Controller X550                                                 | 3         | 1.29%   |
| Intel Ethernet Connection (4) I219-V                                           | 3         | 1.29%   |
| Intel Ethernet Connection (2) I219-LM                                          | 3         | 1.29%   |
| Intel Ethernet Connection (17) I219-V                                          | 3         | 1.29%   |
| Intel 82574L Gigabit Network Connection                                        | 3         | 1.29%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 3         | 1.29%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 2         | 0.86%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 2         | 0.86%   |
| Intel I350 Gigabit Network Connection                                          | 2         | 0.86%   |
| Intel Ethernet Virtual Function 700 Series                                     | 2         | 0.86%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                                  | 2         | 0.86%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                   | 2         | 0.86%   |
| Intel Ethernet Connection I217-V                                               | 2         | 0.86%   |
| Intel Ethernet Connection (6) I219-LM                                          | 2         | 0.86%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2         | 0.86%   |
| Intel Ethernet Connection (16) I219-V                                          | 2         | 0.86%   |
| Intel Ethernet Connection (16) I219-LM                                         | 2         | 0.86%   |
| Intel Ethernet Connection (14) I219-V                                          | 2         | 0.86%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                           | 2         | 0.86%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 2         | 0.86%   |
| Broadcom NetXtreme BCM5722 Gigabit Ethernet PCI Express                        | 2         | 0.86%   |
| American Megatrends Virtual Ethernet.                                          | 2         | 0.86%   |
| Spreadtrum Unisoc Phone                                                        | 1         | 0.43%   |
| Solarflare SFC9020 10G Ethernet Controller                                     | 1         | 0.43%   |
| Realtek USB 10/100/1G/2.5G LAN                                                 | 1         | 0.43%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1         | 0.43%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.43%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1         | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 181       | 57.64%  |
| WiFi     | 128       | 40.76%  |
| Unknown  | 4         | 1.27%   |
| Modem    | 1         | 0.32%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 131       | 60.93%  |
| WiFi     | 83        | 38.6%   |
| Unknown  | 1         | 0.47%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 90        | 44.12%  |
| 1     | 79        | 38.73%  |
| 3     | 15        | 7.35%   |
| 5     | 8         | 3.92%   |
| 4     | 5         | 2.45%   |
| 0     | 3         | 1.47%   |
| 132   | 1         | 0.49%   |
| 66    | 1         | 0.49%   |
| 8     | 1         | 0.49%   |
| 6     | 1         | 0.49%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 157       | 77.34%  |
| Yes  | 46        | 22.66%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 67        | 59.29%  |
| Realtek Semiconductor           | 11        | 9.73%   |
| Qualcomm Atheros Communications | 6         | 5.31%   |
| MediaTek                        | 6         | 5.31%   |
| Foxconn / Hon Hai               | 5         | 4.42%   |
| Broadcom                        | 5         | 4.42%   |
| Cambridge Silicon Radio         | 4         | 3.54%   |
| IMC Networks                    | 3         | 2.65%   |
| Ralink                          | 2         | 1.77%   |
| Integrated System Solution      | 1         | 0.88%   |
| Hewlett-Packard                 | 1         | 0.88%   |
| Dell                            | 1         | 0.88%   |
| Apple                           | 1         | 0.88%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                    | 25        | 22.12%  |
| Intel AX201 Bluetooth                                 | 14        | 12.39%  |
| Realtek Bluetooth Radio                               | 9         | 7.96%   |
| Intel Bluetooth Device                                | 8         | 7.08%   |
| Intel AX200 Bluetooth                                 | 8         | 7.08%   |
| MediaTek Wireless_Device                              | 6         | 5.31%   |
| Qualcomm Atheros  Bluetooth Device                    | 4         | 3.54%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 4         | 3.54%   |
| Intel AX210 Bluetooth                                 | 4         | 3.54%   |
| Foxconn / Hon Hai Wireless_Device                     | 4         | 3.54%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 4         | 3.54%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 3         | 2.65%   |
| Realtek  Bluetooth 4.2 Adapter                        | 2         | 1.77%   |
| Ralink RT3290 Bluetooth                               | 2         | 1.77%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 2         | 1.77%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 1         | 0.88%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 1         | 0.88%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 1         | 0.88%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1         | 0.88%   |
| IMC Networks Wireless_Device                          | 1         | 0.88%   |
| IMC Networks Bluetooth Radio                          | 1         | 0.88%   |
| IMC Networks Bluetooth Device                         | 1         | 0.88%   |
| HP Broadcom 2070 Bluetooth Combo                      | 1         | 0.88%   |
| Foxconn / Hon Hai MediaTek MT7921 Bluetooth           | 1         | 0.88%   |
| Dell Broadcom BCM20702A0 Bluetooth                    | 1         | 0.88%   |
| Broadcom HP Portable Bumble Bee                       | 1         | 0.88%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]            | 1         | 0.88%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]    | 1         | 0.88%   |
| Apple Bluetooth Host Controller                       | 1         | 0.88%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 131       | 45.8%   |
| AMD                    | 57        | 19.93%  |
| Nvidia                 | 56        | 19.58%  |
| Logitech               | 7         | 2.45%   |
| C-Media Electronics    | 5         | 1.75%   |
| Lenovo                 | 3         | 1.05%   |
| ASUSTek Computer       | 3         | 1.05%   |
| Texas Instruments      | 2         | 0.7%    |
| Hewlett-Packard        | 2         | 0.7%    |
| GN Netcom              | 2         | 0.7%    |
| Creative Technology    | 2         | 0.7%    |
| Conexant Systems       | 2         | 0.7%    |
| VIA Technologies       | 1         | 0.35%   |
| Tenx Technology        | 1         | 0.35%   |
| Setek Elektronik       | 1         | 0.35%   |
| Saitek                 | 1         | 0.35%   |
| Realtek Semiconductor  | 1         | 0.35%   |
| Plantronics            | 1         | 0.35%   |
| Nektar                 | 1         | 0.35%   |
| KTMicro                | 1         | 0.35%   |
| JMTek                  | 1         | 0.35%   |
| Huawei Technologies    | 1         | 0.35%   |
| GYROCOM C&C            | 1         | 0.35%   |
| Generalplus Technology | 1         | 0.35%   |
| Creative Labs          | 1         | 0.35%   |
| ASRock                 | 1         | 0.35%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                            | 24        | 7.23%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 14        | 4.22%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 12        | 3.61%   |
| Intel Sunrise Point-LP HD Audio                                                   | 11        | 3.31%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 11        | 3.31%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                           | 10        | 3.01%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 9         | 2.71%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 8         | 2.41%   |
| AMD Rembrandt Radeon High Definition Audio Controller                             | 8         | 2.41%   |
| Intel Comet Lake PCH cAVS                                                         | 7         | 2.11%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 6         | 1.81%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 6         | 1.81%   |
| AMD Starship/Matisse HD Audio Controller                                          | 6         | 1.81%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 5         | 1.51%   |
| Nvidia GK107 HDMI Audio Controller                                                | 5         | 1.51%   |
| Nvidia GA104 High Definition Audio Controller                                     | 5         | 1.51%   |
| Intel 200 Series PCH HD Audio                                                     | 5         | 1.51%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 5         | 1.51%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 5         | 1.51%   |
| Nvidia GK106 HDMI Audio Controller                                                | 4         | 1.2%    |
| Nvidia GA102 High Definition Audio Controller                                     | 4         | 1.2%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 4         | 1.2%    |
| Intel Cannon Point-LP High Definition Audio Controller                            | 4         | 1.2%    |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 4         | 1.2%    |
| AMD FCH Azalia Controller                                                         | 4         | 1.2%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 4         | 1.2%    |
| Nvidia GP107GL High Definition Audio Controller                                   | 3         | 0.9%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 3         | 0.9%    |
| Nvidia GA106 High Definition Audio Controller                                     | 3         | 0.9%    |
| Intel Tiger Lake-H HD Audio Controller                                            | 3         | 0.9%    |
| Intel Jasper Lake HD Audio                                                        | 3         | 0.9%    |
| Intel Comet Lake PCH-LP cAVS                                                      | 3         | 0.9%    |
| Intel Cannon Lake PCH cAVS                                                        | 3         | 0.9%    |
| Intel C610/X99 series chipset HD Audio Controller                                 | 3         | 0.9%    |
| Intel Alder Lake-S HD Audio Controller                                            | 3         | 0.9%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 3         | 0.9%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 3         | 0.9%    |
| AMD Trinity HDMI Audio Controller                                                 | 3         | 0.9%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 3         | 0.9%    |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 3         | 0.9%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 38        | 24.05%  |
| SK hynix            | 26        | 16.46%  |
| Micron Technology   | 23        | 14.56%  |
| Corsair             | 11        | 6.96%   |
| Unknown             | 10        | 6.33%   |
| Kingston            | 10        | 6.33%   |
| Crucial             | 10        | 6.33%   |
| G.Skill             | 8         | 5.06%   |
| Lexar               | 2         | 1.27%   |
| A-DATA Technology   | 2         | 1.27%   |
| Unknown             | 2         | 1.27%   |
| Wodposit            | 1         | 0.63%   |
| Unknown (ABCD)      | 1         | 0.63%   |
| Unknown (0x0080)    | 1         | 0.63%   |
| Team                | 1         | 0.63%   |
| Smart               | 1         | 0.63%   |
| Ramaxel Technology  | 1         | 0.63%   |
| PNY                 | 1         | 0.63%   |
| Patriot             | 1         | 0.63%   |
| Nanya Technology    | 1         | 0.63%   |
| Magnum Tech         | 1         | 0.63%   |
| Lexar Co Limited    | 1         | 0.63%   |
| HPE                 | 1         | 0.63%   |
| Hewlett-Packard     | 1         | 0.63%   |
| Gold Key            | 1         | 0.63%   |
| Elpida              | 1         | 0.63%   |
| CUSO                | 1         | 0.63%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 3         | 1.85%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1066MT/s                        | 2         | 1.23%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s              | 2         | 1.23%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 1.23%   |
| Samsung RAM M393B2873EH1-CF8 1GB DIMM DDR3 1066MT/s                 | 2         | 1.23%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s                | 2         | 1.23%   |
| Unknown                                                             | 2         | 1.23%   |
| Wodposit RAM WPBH26D408SWA-8G 8GB SODIMM DDR4 2667MT/s              | 1         | 0.62%   |
| Unknown RAM Module 8GB DIMM DDR4 3000MT/s                           | 1         | 0.62%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                           | 1         | 0.62%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                           | 1         | 0.62%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                           | 1         | 0.62%   |
| Unknown RAM Module 2GB DIMM 667MT/s                                 | 1         | 0.62%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                      | 1         | 0.62%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                            | 1         | 0.62%   |
| Unknown RAM Module 1GB DIMM 667MT/s                                 | 1         | 0.62%   |
| Unknown RAM Module 16GB DIMM DDR4 3200MT/s                          | 1         | 0.62%   |
| Unknown RAM Module 16GB DIMM DDR4 2666MT/s                          | 1         | 0.62%   |
| Unknown RAM DDR4 NB 8G 2666 8GB SODIMM DDR4 2667MT/s                | 1         | 0.62%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 1         | 0.62%   |
| Unknown (0x0080) RAM Module 16GB SODIMM DDR4 2667MT/s               | 1         | 0.62%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3733MT/s                  | 1         | 0.62%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s               | 1         | 0.62%   |
| SK hynix RAM Module 8GB SODIMM DDR4 3200MT/s                        | 1         | 0.62%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s                        | 1         | 0.62%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                        | 1         | 0.62%   |
| SK hynix RAM Module 4GB Row Of Chips DDR4 2400MT/s                  | 1         | 0.62%   |
| SK hynix RAM Module 32GB SODIMM DDR4 3200MT/s                       | 1         | 0.62%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s                          | 1         | 0.62%   |
| SK hynix RAM HMT351U6EFR8C-PB 4096MB DIMM DDR3 1800MT/s             | 1         | 0.62%   |
| SK hynix RAM HMT325U7EFR8A-PB 2GB DIMM DDR3 1600MT/s                | 1         | 0.62%   |
| SK hynix RAM HMT31GR7BFR4C-H9 8GB DIMM DDR3 1333MT/s                | 1         | 0.62%   |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s              | 1         | 0.62%   |
| SK hynix RAM HMAB2GS6CMR6N-XN 16GB SODIMM DDR4 3200MT/s             | 1         | 0.62%   |
| SK hynix RAM HMAA8GR7CJR4N-XN 64GB DIMM DDR4 3200MT/s               | 1         | 0.62%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s             | 1         | 0.62%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s             | 1         | 0.62%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s              | 1         | 0.62%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 1         | 0.62%   |
| SK hynix RAM HMA82GR7AFR8N-VK 16GB DIMM DDR4 2666MT/s               | 1         | 0.62%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 81        | 58.27%  |
| DDR3    | 37        | 26.62%  |
| DDR5    | 10        | 7.19%   |
| LPDDR5  | 3         | 2.16%   |
| LPDDR4  | 3         | 2.16%   |
| DDR2    | 3         | 2.16%   |
| LPDDR3  | 1         | 0.72%   |
| Unknown | 1         | 0.72%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 67        | 47.86%  |
| SODIMM       | 63        | 45%     |
| Row Of Chips | 8         | 5.71%   |
| RIMM         | 1         | 0.71%   |
| Unknown      | 1         | 0.71%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 53        | 36.05%  |
| 16384 | 38        | 25.85%  |
| 4096  | 24        | 16.33%  |
| 32768 | 19        | 12.93%  |
| 1024  | 7         | 4.76%   |
| 2048  | 5         | 3.4%    |
| 65536 | 1         | 0.68%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 33        | 22%     |
| 2667  | 27        | 18%     |
| 1600  | 17        | 11.33%  |
| 2400  | 13        | 8.67%   |
| 4800  | 8         | 5.33%   |
| 1333  | 8         | 5.33%   |
| 2133  | 7         | 4.67%   |
| 2666  | 6         | 4%      |
| 1066  | 5         | 3.33%   |
| 3600  | 3         | 2%      |
| 667   | 3         | 2%      |
| 6400  | 2         | 1.33%   |
| 3534  | 2         | 1.33%   |
| 1800  | 2         | 1.33%   |
| 5600  | 1         | 0.67%   |
| 5500  | 1         | 0.67%   |
| 4267  | 1         | 0.67%   |
| 4266  | 1         | 0.67%   |
| 3733  | 1         | 0.67%   |
| 3666  | 1         | 0.67%   |
| 3266  | 1         | 0.67%   |
| 3100  | 1         | 0.67%   |
| 3000  | 1         | 0.67%   |
| 2933  | 1         | 0.67%   |
| 2800  | 1         | 0.67%   |
| 2200  | 1         | 0.67%   |
| 2048  | 1         | 0.67%   |
| 1866  | 1         | 0.67%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Seiko Epson        | 2         | 50%     |
| Brother Industries | 2         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Seiko Epson XP-4100 Series    | 1         | 25%     |
| Seiko Epson Printer           | 1         | 25%     |
| Brother MFC-J435W             | 1         | 25%     |
| Brother HL-2030 Laser Printer | 1         | 25%     |

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
| Chicony Electronics                    | 18        | 19.57%  |
| IMC Networks                           | 14        | 15.22%  |
| Realtek Semiconductor                  | 8         | 8.7%    |
| Microdia                               | 8         | 8.7%    |
| Sunplus Innovation Technology          | 5         | 5.43%   |
| Logitech                               | 5         | 5.43%   |
| Syntek                                 | 4         | 4.35%   |
| Luxvisions Innotech Limited            | 4         | 4.35%   |
| Bison Electronics                      | 4         | 4.35%   |
| Quanta                                 | 3         | 3.26%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 3.26%   |
| webcamvendor                           | 2         | 2.17%   |
| Generalplus Technology                 | 2         | 2.17%   |
| USB Camera                             | 1         | 1.09%   |
| Suyin                                  | 1         | 1.09%   |
| Sonix Technology                       | 1         | 1.09%   |
| Silicon Motion                         | 1         | 1.09%   |
| MacroSilicon                           | 1         | 1.09%   |
| Lite-On Technology                     | 1         | 1.09%   |
| Lenovo                                 | 1         | 1.09%   |
| KYE Systems (Mouse Systems)            | 1         | 1.09%   |
| Intel                                  | 1         | 1.09%   |
| Huawei Technologies                    | 1         | 1.09%   |
| Elgato Systems                         | 1         | 1.09%   |
| Apple                                  | 1         | 1.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 10        | 10.75%  |
| Microdia Integrated_Webcam_HD                       | 6         | 6.45%   |
| Realtek Integrated_Webcam_HD                        | 5         | 5.38%   |
| IMC Networks Integrated Camera                      | 5         | 5.38%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 4         | 4.3%    |
| Chicony HP HD Camera                                | 3         | 3.23%   |
| webcamvendor webcamproduct                          | 2         | 2.15%   |
| Syntek Lenovo EasyCamera                            | 2         | 2.15%   |
| Syntek Integrated Camera                            | 2         | 2.15%   |
| Logitech HD Pro Webcam C920                         | 2         | 2.15%   |
| Generalplus GENERAL WEBCAM                          | 2         | 2.15%   |
| Chicony HD WebCam                                   | 2         | 2.15%   |
| Bison Integrated RGB Camera                         | 2         | 2.15%   |
| USB Camera USB Camera                               | 1         | 1.08%   |
| Suyin HP TrueVision HD Integrated Webcam            | 1         | 1.08%   |
| Sunplus Laptop_Integrated_Webcam_HD                 | 1         | 1.08%   |
| Sunplus Integrated_Webcam_FHD                       | 1         | 1.08%   |
| Sunplus Full HD webcam                              | 1         | 1.08%   |
| Sunplus FHD Camera Microphone                       | 1         | 1.08%   |
| Sunplus FHD Camera                                  | 1         | 1.08%   |
| Sonix USB2.0 HD UVC WebCam                          | 1         | 1.08%   |
| Silicon Motion Lenovo EasyCamera                    | 1         | 1.08%   |
| Realtek USB2.0 HD UVC WebCam                        | 1         | 1.08%   |
| Realtek Integrated Webcam_HD                        | 1         | 1.08%   |
| Realtek EasyCamera                                  | 1         | 1.08%   |
| Quanta HP Webcam                                    | 1         | 1.08%   |
| Quanta HP True Vision 5MP Camera                    | 1         | 1.08%   |
| Quanta HP 5MP Camera                                | 1         | 1.08%   |
| Microdia Webcam Vitade AF                           | 1         | 1.08%   |
| Microdia Integrated_Webcam_FHD                      | 1         | 1.08%   |
| MacroSilicon USB3. 0 capture                        | 1         | 1.08%   |
| Luxvisions Innotech Limited Integrated RGB Camera   | 1         | 1.08%   |
| Luxvisions Innotech Limited Integrated Camera       | 1         | 1.08%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 1.08%   |
| Luxvisions Innotech Limited HP HD Camera            | 1         | 1.08%   |
| Logitech Webcam C270                                | 1         | 1.08%   |
| Logitech HD Webcam C615                             | 1         | 1.08%   |
| Logitech BRIO Ultra HD Webcam                       | 1         | 1.08%   |
| Lite-On HP HD Webcam                                | 1         | 1.08%   |
| Lenovo UVC Camera                                   | 1         | 1.08%   |

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
| 0     | 111       | 54.41%  |
| 1     | 67        | 32.84%  |
| 2     | 17        | 8.33%   |
| 3     | 5         | 2.45%   |
| 5     | 2         | 0.98%   |
| 4     | 2         | 0.98%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 30        | 24.79%  |
| Graphics card            | 21        | 17.36%  |
| Unassigned class         | 14        | 11.57%  |
| Net/wireless             | 14        | 11.57%  |
| Communication controller | 10        | 8.26%   |
| Net/ethernet             | 5         | 4.13%   |
| Multimedia controller    | 5         | 4.13%   |
| Network                  | 4         | 3.31%   |
| Firewire controller      | 4         | 3.31%   |
| Sound                    | 3         | 2.48%   |
| Chipcard                 | 3         | 2.48%   |
| Bluetooth                | 2         | 1.65%   |
| Storage/raid             | 1         | 0.83%   |
| Storage/ide              | 1         | 0.83%   |
| Storage                  | 1         | 0.83%   |
| Modem                    | 1         | 0.83%   |
| Dvb card                 | 1         | 0.83%   |
| Card reader              | 1         | 0.83%   |

