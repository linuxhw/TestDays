Xero - Tested Hardware & Statistics
-----------------------------------

A project to collect tested hardware configurations for Xero.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Xero/Desktop/README.md) and [notebooks](/Dist/Xero/Notebook/README.md).

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

Total: 99

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [b28edd3886](https://linux-hardware.org/?probe=b28edd3886) | Aug 26, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [97770c5716](https://linux-hardware.org/?probe=97770c5716) | Aug 26, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [4c95b1bccf](https://linux-hardware.org/?probe=4c95b1bccf) | Aug 22, 2022 |
| Lenovo        | ThinkPad T430s 2356FG9      | Notebook    | [9a10c152af](https://linux-hardware.org/?probe=9a10c152af) | Aug 17, 2022 |
| Aquarius      | NS585                       | Notebook    | [db9cbd5688](https://linux-hardware.org/?probe=db9cbd5688) | Aug 17, 2022 |
| Gigabyte      | B460M DS3H V2               | Desktop     | [2522ff1530](https://linux-hardware.org/?probe=2522ff1530) | Aug 13, 2022 |
| ASUSTek       | P7P55 LX                    | Desktop     | [8211ccc6cc](https://linux-hardware.org/?probe=8211ccc6cc) | Aug 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [b73e5f9cbf](https://linux-hardware.org/?probe=b73e5f9cbf) | Aug 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [f483092edf](https://linux-hardware.org/?probe=f483092edf) | Aug 07, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a0507fae02](https://linux-hardware.org/?probe=a0507fae02) | Jul 31, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [7c46c8f737](https://linux-hardware.org/?probe=7c46c8f737) | Jul 15, 2022 |
| ASUSTek       | G551JM                      | Notebook    | [599c7b9eae](https://linux-hardware.org/?probe=599c7b9eae) | Jul 14, 2022 |
| ASUSTek       | G551JM                      | Notebook    | [9f4536df1c](https://linux-hardware.org/?probe=9f4536df1c) | Jul 14, 2022 |
| ASRock        | AB350 Pro4                  | Desktop     | [7049f819f0](https://linux-hardware.org/?probe=7049f819f0) | Jun 30, 2022 |
| HP            | 3396                        | Desktop     | [00782afa06](https://linux-hardware.org/?probe=00782afa06) | Jun 22, 2022 |
| ASUSTek       | UX303LN                     | Notebook    | [9ce42e1b01](https://linux-hardware.org/?probe=9ce42e1b01) | Jun 12, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [8109a04ffa](https://linux-hardware.org/?probe=8109a04ffa) | Jun 12, 2022 |
| BESSTAR Te... | ATB15                       | Server      | [d6e47a7c18](https://linux-hardware.org/?probe=d6e47a7c18) | Jun 12, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [8a7401e54a](https://linux-hardware.org/?probe=8a7401e54a) | Jun 11, 2022 |
| Acer          | Aspire XC-886 V:2.0         | Desktop     | [2fe8cdaf93](https://linux-hardware.org/?probe=2fe8cdaf93) | May 31, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [ce0e24a314](https://linux-hardware.org/?probe=ce0e24a314) | May 28, 2022 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [53475a6004](https://linux-hardware.org/?probe=53475a6004) | May 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [80d32848bf](https://linux-hardware.org/?probe=80d32848bf) | May 21, 2022 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [3ddad532a9](https://linux-hardware.org/?probe=3ddad532a9) | May 08, 2022 |
| Dell          | Inspiron 7786               | Convertible | [0ef12447d9](https://linux-hardware.org/?probe=0ef12447d9) | May 02, 2022 |
| Dell          | Precision M3800             | Notebook    | [7b63874768](https://linux-hardware.org/?probe=7b63874768) | Apr 25, 2022 |
| Dell          | Precision M3800             | Notebook    | [fbabacd835](https://linux-hardware.org/?probe=fbabacd835) | Apr 24, 2022 |
| Lenovo        | ThinkPad X230 2325HR9       | Notebook    | [a9d9d3fbb2](https://linux-hardware.org/?probe=a9d9d3fbb2) | Apr 21, 2022 |
| MSI           | Z170-A PRO                  | Desktop     | [db5ab86328](https://linux-hardware.org/?probe=db5ab86328) | Apr 11, 2022 |
| Acer          | Aspire A515-54G             | Notebook    | [52b660d8fb](https://linux-hardware.org/?probe=52b660d8fb) | Apr 11, 2022 |
| MSI           | Z170-A PRO                  | Desktop     | [3bd5bb8d08](https://linux-hardware.org/?probe=3bd5bb8d08) | Apr 10, 2022 |
| Dell          | Precision M3800             | Notebook    | [1ef57b39a7](https://linux-hardware.org/?probe=1ef57b39a7) | Apr 10, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [8d251b1b2a](https://linux-hardware.org/?probe=8d251b1b2a) | Apr 03, 2022 |
| Dell          | Precision M3800             | Notebook    | [9fc15d1ae6](https://linux-hardware.org/?probe=9fc15d1ae6) | Mar 31, 2022 |
| HP            | 843B                        | Desktop     | [a88ff7cf5c](https://linux-hardware.org/?probe=a88ff7cf5c) | Mar 27, 2022 |
| Pegatron      | 2AC2                        | Desktop     | [d3c82e973b](https://linux-hardware.org/?probe=d3c82e973b) | Mar 25, 2022 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [745cc1d638](https://linux-hardware.org/?probe=745cc1d638) | Mar 25, 2022 |
| MSI           | GF63 Thin 9SCX              | Notebook    | [4501fa1556](https://linux-hardware.org/?probe=4501fa1556) | Mar 25, 2022 |
| Dell          | Latitude 7480               | Notebook    | [bf00ec6a76](https://linux-hardware.org/?probe=bf00ec6a76) | Mar 23, 2022 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [8eb98db533](https://linux-hardware.org/?probe=8eb98db533) | Mar 22, 2022 |
| HUAWEI        | WRT-WX9                     | Notebook    | [70ec26bed6](https://linux-hardware.org/?probe=70ec26bed6) | Mar 22, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [13cdf54c81](https://linux-hardware.org/?probe=13cdf54c81) | Mar 21, 2022 |
| Dell          | Latitude 7480               | Notebook    | [faddba28a8](https://linux-hardware.org/?probe=faddba28a8) | Mar 19, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [b71110144d](https://linux-hardware.org/?probe=b71110144d) | Mar 19, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [bb9074ccdf](https://linux-hardware.org/?probe=bb9074ccdf) | Mar 18, 2022 |
| Lenovo        | IdeaPad 3 15IML05 81WR      | Notebook    | [918c951cd1](https://linux-hardware.org/?probe=918c951cd1) | Mar 12, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [639e7361ef](https://linux-hardware.org/?probe=639e7361ef) | Mar 12, 2022 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [e251c9f079](https://linux-hardware.org/?probe=e251c9f079) | Mar 11, 2022 |
| MSI           | Z170A PC MATE               | Desktop     | [181e014823](https://linux-hardware.org/?probe=181e014823) | Mar 08, 2022 |
| Gigabyte      | Z170X-UD3-CF                | Desktop     | [3ec7a7f643](https://linux-hardware.org/?probe=3ec7a7f643) | Mar 06, 2022 |
| Dell          | Venue 11 Pro 7130 vPro      | Notebook    | [57b302b119](https://linux-hardware.org/?probe=57b302b119) | Mar 05, 2022 |
| Lenovo        | ThinkPad T460 20FMS1XX00    | Notebook    | [78e82c6674](https://linux-hardware.org/?probe=78e82c6674) | Feb 24, 2022 |
| Dell          | Latitude E6430              | Notebook    | [e1de4e80fe](https://linux-hardware.org/?probe=e1de4e80fe) | Feb 15, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [a3c5f00a2a](https://linux-hardware.org/?probe=a3c5f00a2a) | Feb 10, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [e53fb31614](https://linux-hardware.org/?probe=e53fb31614) | Feb 10, 2022 |
| Lenovo        | Legion Y740-15IRHg 81UH     | Notebook    | [b0cc5e0cbc](https://linux-hardware.org/?probe=b0cc5e0cbc) | Jan 29, 2022 |
| ASUSTek       | P5Q PRO TURBO               | Desktop     | [83ca29c9c8](https://linux-hardware.org/?probe=83ca29c9c8) | Jan 28, 2022 |
| Acer          | Aspire A315-58G             | Notebook    | [cb4f253c1c](https://linux-hardware.org/?probe=cb4f253c1c) | Jan 28, 2022 |
| Dell          | Latitude E6520              | Notebook    | [ee96960cec](https://linux-hardware.org/?probe=ee96960cec) | Jan 25, 2022 |
| Lenovo        | Yoga 710-15IKB 80V5         | Convertible | [3d5fe9fc42](https://linux-hardware.org/?probe=3d5fe9fc42) | Jan 22, 2022 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [0df160c245](https://linux-hardware.org/?probe=0df160c245) | Jan 21, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [230373b3ff](https://linux-hardware.org/?probe=230373b3ff) | Jan 09, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [3df8a1c560](https://linux-hardware.org/?probe=3df8a1c560) | Jan 08, 2022 |
| HP            | 1906                        | Desktop     | [5f8fe7cb20](https://linux-hardware.org/?probe=5f8fe7cb20) | Jan 06, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [793bfa4f40](https://linux-hardware.org/?probe=793bfa4f40) | Jan 04, 2022 |
| HP            | 2179                        | Desktop     | [79bac7ce1b](https://linux-hardware.org/?probe=79bac7ce1b) | Jan 01, 2022 |
| ASUSTek       | TUF B360M-PLUS GAMING/BR    | Desktop     | [512091cd1c](https://linux-hardware.org/?probe=512091cd1c) | Dec 30, 2021 |
| Dell          | Vostro 3590                 | Notebook    | [9e77a2584c](https://linux-hardware.org/?probe=9e77a2584c) | Dec 30, 2021 |
| HP            | 2179                        | Desktop     | [9b6358ce37](https://linux-hardware.org/?probe=9b6358ce37) | Dec 30, 2021 |
| ASUSTek       | ASUS EXPERTBOOK B9400CEA... | Notebook    | [78e3fbdf6a](https://linux-hardware.org/?probe=78e3fbdf6a) | Dec 28, 2021 |
| HP            | Notebook                    | Notebook    | [c14ea64659](https://linux-hardware.org/?probe=c14ea64659) | Dec 23, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [5c2c86f287](https://linux-hardware.org/?probe=5c2c86f287) | Dec 23, 2021 |
| ASUSTek       | X510UNR                     | Notebook    | [0733a05806](https://linux-hardware.org/?probe=0733a05806) | Dec 21, 2021 |
| ASUSTek       | ASUS EXPERTBOOK B9400CEA... | Notebook    | [b4425de4a6](https://linux-hardware.org/?probe=b4425de4a6) | Dec 17, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [6f3bd18b3f](https://linux-hardware.org/?probe=6f3bd18b3f) | Dec 06, 2021 |
| Pegatron      | D15K                        | Notebook    | [eaeaad8d39](https://linux-hardware.org/?probe=eaeaad8d39) | Nov 29, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [728b23aa46](https://linux-hardware.org/?probe=728b23aa46) | Nov 26, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [9e9b6fd944](https://linux-hardware.org/?probe=9e9b6fd944) | Nov 21, 2021 |
| MSI           | GP73 Leopard 8RD            | Notebook    | [5bafb43f78](https://linux-hardware.org/?probe=5bafb43f78) | Nov 21, 2021 |
| Acer          | Aspire A315-58G             | Notebook    | [911895fcf2](https://linux-hardware.org/?probe=911895fcf2) | Nov 19, 2021 |
| Acer          | Aspire A315-58G             | Notebook    | [5748b3cd05](https://linux-hardware.org/?probe=5748b3cd05) | Nov 12, 2021 |
| Lenovo        | ThinkPad W530 24384CU       | Notebook    | [d18d3495e0](https://linux-hardware.org/?probe=d18d3495e0) | Nov 05, 2021 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [4877535f8b](https://linux-hardware.org/?probe=4877535f8b) | Nov 03, 2021 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [8dd5924480](https://linux-hardware.org/?probe=8dd5924480) | Oct 31, 2021 |
| Acer          | Aspire A315-58G             | Notebook    | [905fce5118](https://linux-hardware.org/?probe=905fce5118) | Oct 29, 2021 |
| HP            | ENVY Sleekbook 4            | Notebook    | [ebea056239](https://linux-hardware.org/?probe=ebea056239) | Oct 29, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [2a54689fb3](https://linux-hardware.org/?probe=2a54689fb3) | Oct 24, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [fb95cbb063](https://linux-hardware.org/?probe=fb95cbb063) | Oct 19, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [6cd76dfa2a](https://linux-hardware.org/?probe=6cd76dfa2a) | Oct 13, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [e3a8d1ca32](https://linux-hardware.org/?probe=e3a8d1ca32) | Oct 11, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [c7c4a74bb8](https://linux-hardware.org/?probe=c7c4a74bb8) | Oct 11, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [68865693c7](https://linux-hardware.org/?probe=68865693c7) | Oct 09, 2021 |
| Dell          | 0XC7MM A01                  | Desktop     | [390c5408b2](https://linux-hardware.org/?probe=390c5408b2) | Oct 05, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [e804a59920](https://linux-hardware.org/?probe=e804a59920) | Oct 02, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [a198e8517a](https://linux-hardware.org/?probe=a198e8517a) | Oct 01, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [50fd919991](https://linux-hardware.org/?probe=50fd919991) | Aug 29, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [a3c6fe4037](https://linux-hardware.org/?probe=a3c6fe4037) | Jul 24, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [57d19e2c3a](https://linux-hardware.org/?probe=57d19e2c3a) | May 19, 2021 |
| Acer          | FIH57                       | Desktop     | [9c3e383ea5](https://linux-hardware.org/?probe=9c3e383ea5) | Apr 30, 2021 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Xero Rolling | 64        | 83.12%  |
| Xero         | 13        | 16.88%  |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| Xero | 76        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 5.16.15-arch1-1              | 6         | 7.14%   |
| 5.18.16-arch1-1              | 3         | 3.57%   |
| 5.17.9-arch1-1               | 3         | 3.57%   |
| 5.16.2-arch1-1               | 3         | 3.57%   |
| 5.16.1-arch1-1               | 3         | 3.57%   |
| 5.15.33-1-lts                | 3         | 3.57%   |
| 5.14.14-arch1-1              | 3         | 3.57%   |
| 5.18.3-arch1-1               | 2         | 2.38%   |
| 5.18.11-arch1-1              | 2         | 2.38%   |
| 5.17.5-arch1-1               | 2         | 2.38%   |
| 5.17.1-arch1-1               | 2         | 2.38%   |
| 5.16.8-arch1-1               | 2         | 2.38%   |
| 5.16.16-arch1-1              | 2         | 2.38%   |
| 5.16.13-arch1-1              | 2         | 2.38%   |
| 5.16.12-arch1-1              | 2         | 2.38%   |
| 5.15.10-arch1-1              | 2         | 2.38%   |
| 5.14.8-zen1-1-zen            | 2         | 2.38%   |
| 5.19.3-arch1-1               | 1         | 1.19%   |
| 5.19.2-zen1-1-zen            | 1         | 1.19%   |
| 5.19.1-arch2-1               | 1         | 1.19%   |
| 5.18.9-arch1-1               | 1         | 1.19%   |
| 5.18.6-arch1-1               | 1         | 1.19%   |
| 5.18.0-arch1-1               | 1         | 1.19%   |
| 5.17.7-arch1-1               | 1         | 1.19%   |
| 5.16.16-zen1-1-zen           | 1         | 1.19%   |
| 5.16.14-arch1-1              | 1         | 1.19%   |
| 5.16.10-arch1-1              | 1         | 1.19%   |
| 5.15.8-zen1-1-zen            | 1         | 1.19%   |
| 5.15.6-arch2-1               | 1         | 1.19%   |
| 5.15.4-arch1-1               | 1         | 1.19%   |
| 5.15.35-1-lts                | 1         | 1.19%   |
| 5.15.3-zen1-1-zen            | 1         | 1.19%   |
| 5.15.26-1-lts                | 1         | 1.19%   |
| 5.15.24-1-lts                | 1         | 1.19%   |
| 5.15.13-arch1-1              | 1         | 1.19%   |
| 5.15.13-AMD                  | 1         | 1.19%   |
| 5.15.12-zen1-1-zen           | 1         | 1.19%   |
| 5.15.12-arch1-1-surface      | 1         | 1.19%   |
| 5.15.12-arch1-1              | 1         | 1.19%   |
| 5.15.11-arch2-1-surface      | 1         | 1.19%   |
| 5.15.11-arch2-1              | 1         | 1.19%   |
| 5.14.9-zen2-1-zen            | 1         | 1.19%   |
| 5.14.8-arch1-1               | 1         | 1.19%   |
| 5.14.16-zen1-1-zen           | 1         | 1.19%   |
| 5.14.16-arch1-2-surface      | 1         | 1.19%   |
| 5.14.16-arch1-1              | 1         | 1.19%   |
| 5.14.15-zen1-1-zen           | 1         | 1.19%   |
| 5.14.14-zen1-1-zen           | 1         | 1.19%   |
| 5.14.12-arch1-1              | 1         | 1.19%   |
| 5.14.11-hardened1-1-hardened | 1         | 1.19%   |
| 5.13.4-zen1-1-zen            | 1         | 1.19%   |
| 5.13.13-AMD                  | 1         | 1.19%   |
| 5.12.5-AMD                   | 1         | 1.19%   |
| 5.11.16-zen1-1-zen           | 1         | 1.19%   |
| 5.10.88-1-lts                | 1         | 1.19%   |
| 5.10.80-1-lts                | 1         | 1.19%   |
| 5.10.71-1-lts                | 1         | 1.19%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.16.15 | 6         | 7.14%   |
| 5.14.14 | 4         | 4.76%   |
| 5.18.16 | 3         | 3.57%   |
| 5.17.9  | 3         | 3.57%   |
| 5.16.2  | 3         | 3.57%   |
| 5.16.16 | 3         | 3.57%   |
| 5.16.1  | 3         | 3.57%   |
| 5.15.33 | 3         | 3.57%   |
| 5.15.12 | 3         | 3.57%   |
| 5.14.8  | 3         | 3.57%   |
| 5.14.16 | 3         | 3.57%   |
| 5.18.3  | 2         | 2.38%   |
| 5.18.11 | 2         | 2.38%   |
| 5.17.5  | 2         | 2.38%   |
| 5.17.1  | 2         | 2.38%   |
| 5.16.8  | 2         | 2.38%   |
| 5.16.13 | 2         | 2.38%   |
| 5.16.12 | 2         | 2.38%   |
| 5.15.13 | 2         | 2.38%   |
| 5.15.11 | 2         | 2.38%   |
| 5.15.10 | 2         | 2.38%   |
| 5.19.3  | 1         | 1.19%   |
| 5.19.2  | 1         | 1.19%   |
| 5.19.1  | 1         | 1.19%   |
| 5.18.9  | 1         | 1.19%   |
| 5.18.6  | 1         | 1.19%   |
| 5.18.0  | 1         | 1.19%   |
| 5.17.7  | 1         | 1.19%   |
| 5.16.14 | 1         | 1.19%   |
| 5.16.10 | 1         | 1.19%   |
| 5.15.8  | 1         | 1.19%   |
| 5.15.6  | 1         | 1.19%   |
| 5.15.4  | 1         | 1.19%   |
| 5.15.35 | 1         | 1.19%   |
| 5.15.3  | 1         | 1.19%   |
| 5.15.26 | 1         | 1.19%   |
| 5.15.24 | 1         | 1.19%   |
| 5.14.9  | 1         | 1.19%   |
| 5.14.15 | 1         | 1.19%   |
| 5.14.12 | 1         | 1.19%   |
| 5.14.11 | 1         | 1.19%   |
| 5.13.4  | 1         | 1.19%   |
| 5.13.13 | 1         | 1.19%   |
| 5.12.5  | 1         | 1.19%   |
| 5.11.16 | 1         | 1.19%   |
| 5.10.88 | 1         | 1.19%   |
| 5.10.80 | 1         | 1.19%   |
| 5.10.71 | 1         | 1.19%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.16    | 23        | 28.05%  |
| 5.15    | 18        | 21.95%  |
| 5.14    | 13        | 15.85%  |
| 5.18    | 10        | 12.2%   |
| 5.17    | 8         | 9.76%   |
| 5.19    | 3         | 3.66%   |
| 5.10    | 3         | 3.66%   |
| 5.13    | 2         | 2.44%   |
| 5.12    | 1         | 1.22%   |
| 5.11    | 1         | 1.22%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 76        | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| KDE5  | 72        | 92.31%  |
| XFCE  | 4         | 5.13%   |
| GNOME | 2         | 2.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 64        | 84.21%  |
| Wayland | 10        | 13.16%  |
| Tty     | 2         | 2.63%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 50        | 62.5%   |
| LightDM | 15        | 18.75%  |
| Unknown | 13        | 16.25%  |
| TDM     | 1         | 1.25%   |
| GDM     | 1         | 1.25%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 42        | 54.55%  |
| en_IN | 6         | 7.79%   |
| en_GB | 5         | 6.49%   |
| C     | 5         | 6.49%   |
| pl_PL | 4         | 5.19%   |
| de_DE | 3         | 3.9%    |
| it_IT | 2         | 2.6%    |
| en_AU | 2         | 2.6%    |
| ru_RU | 1         | 1.3%    |
| fr_FR | 1         | 1.3%    |
| en_IL | 1         | 1.3%    |
| en_DK | 1         | 1.3%    |
| en_CA | 1         | 1.3%    |
| en_AG | 1         | 1.3%    |
| de_AT | 1         | 1.3%    |
| ba_RU | 1         | 1.3%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 52        | 67.53%  |
| BIOS | 25        | 32.47%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 52        | 66.67%  |
| Ext4    | 13        | 16.67%  |
| Xfs     | 7         | 8.97%   |
| Overlay | 6         | 7.69%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 54        | 70.13%  |
| Unknown | 13        | 16.88%  |
| MBR     | 10        | 12.99%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 60        | 75%     |
| Yes       | 20        | 25%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 50        | 65.79%  |
| Yes       | 26        | 34.21%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 20        | 26.32%  |
| Lenovo              | 15        | 19.74%  |
| Dell                | 11        | 14.47%  |
| Hewlett-Packard     | 8         | 10.53%  |
| MSI                 | 5         | 6.58%   |
| Acer                | 4         | 5.26%   |
| Gigabyte Technology | 3         | 3.95%   |
| ASRock              | 3         | 3.95%   |
| Pegatron            | 2         | 2.63%   |
| HUAWEI              | 1         | 1.32%   |
| BESSTAR Tech        | 1         | 1.32%   |
| Aquarius            | 1         | 1.32%   |
| Apple               | 1         | 1.32%   |
| Unknown             | 1         | 1.32%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Dell Precision M3800                       | 3         | 3.95%   |
| MSI MS-7971                                | 2         | 2.63%   |
| ASUS TUF Gaming X570-PLUS                  | 2         | 2.63%   |
| Pegatron p6-2026                           | 1         | 1.32%   |
| Pegatron D15K                              | 1         | 1.32%   |
| MSI MS-7B61                                | 1         | 1.32%   |
| MSI GP73 Leopard 8RD                       | 1         | 1.32%   |
| MSI GF63 Thin 9SCX                         | 1         | 1.32%   |
| Lenovo Yoga 710-15IKB 80V5                 | 1         | 1.32%   |
| Lenovo Y520-15IKBN 80WK                    | 1         | 1.32%   |
| Lenovo ThinkPad X230 2325HR9               | 1         | 1.32%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XW0055MH | 1         | 1.32%   |
| Lenovo ThinkPad W530 24384CU               | 1         | 1.32%   |
| Lenovo ThinkPad T460 20FMS1XX00            | 1         | 1.32%   |
| Lenovo ThinkPad T430s 2356FG9              | 1         | 1.32%   |
| Lenovo Legion Y740-15IRHg 81UH             | 1         | 1.32%   |
| Lenovo Legion Y540-15IRH-PG0 81SY          | 1         | 1.32%   |
| Lenovo Legion 5 15ARH05H 82B1              | 1         | 1.32%   |
| Lenovo IdeaPad S145-15IIL 81W8             | 1         | 1.32%   |
| Lenovo IdeaPad S145-15AST 81N3             | 1         | 1.32%   |
| Lenovo IdeaPad 5 15ITL05 82FG              | 1         | 1.32%   |
| Lenovo IdeaPad 330-17IKB 81DM              | 1         | 1.32%   |
| Lenovo IdeaPad 3 15IML05 81WR              | 1         | 1.32%   |
| HUAWEI WRT-WX9                             | 1         | 1.32%   |
| HP Z230 SFF Workstation                    | 1         | 1.32%   |
| HP ProOne 400 G1 AiO                       | 1         | 1.32%   |
| HP Pavilion Desktop 590-p0xxx              | 1         | 1.32%   |
| HP Notebook                                | 1         | 1.32%   |
| HP Laptop 15s-eq0xxx                       | 1         | 1.32%   |
| HP Laptop 15-da0xxx                        | 1         | 1.32%   |
| HP ENVY Sleekbook 4                        | 1         | 1.32%   |
| HP Compaq Elite 8300 CMT                   | 1         | 1.32%   |
| Gigabyte Z170X-UD3                         | 1         | 1.32%   |
| Gigabyte X570 AORUS MASTER                 | 1         | 1.32%   |
| Gigabyte B460MDS3HV2                       | 1         | 1.32%   |
| Dell Vostro 3590                           | 1         | 1.32%   |
| Dell Venue 11 Pro 7130 vPro                | 1         | 1.32%   |
| Dell Precision T1500                       | 1         | 1.32%   |
| Dell Latitude E6520                        | 1         | 1.32%   |
| Dell Latitude E6430                        | 1         | 1.32%   |
| Dell Latitude 7480                         | 1         | 1.32%   |
| Dell Inspiron 7786                         | 1         | 1.32%   |
| Dell Inspiron 1545                         | 1         | 1.32%   |
| BESSTAR Tech X500                          | 1         | 1.32%   |
| ASUS X510UNR                               | 1         | 1.32%   |
| ASUS VivoBook_ASUSLaptop X509FJ_X509FJ     | 1         | 1.32%   |
| ASUS VivoBook_ASUSLaptop X3500PC_K3500PC   | 1         | 1.32%   |
| ASUS VivoBook_ASUS Laptop E410MA_E410MA    | 1         | 1.32%   |
| ASUS UX303LN                               | 1         | 1.32%   |
| ASUS TUF Z390-PLUS GAMING                  | 1         | 1.32%   |
| ASUS TUF Gaming B550M-PLUS                 | 1         | 1.32%   |
| ASUS TUF B360M-PLUS GAMING/BR              | 1         | 1.32%   |
| ASUS ROG STRIX B450-F GAMING               | 1         | 1.32%   |
| ASUS ROG Maximus X HERO                    | 1         | 1.32%   |
| ASUS ROG CROSSHAIR VIII HERO               | 1         | 1.32%   |
| ASUS PRIME A320M-K                         | 1         | 1.32%   |
| ASUS P7P55 LX                              | 1         | 1.32%   |
| ASUS P5Q PRO TURBO                         | 1         | 1.32%   |
| ASUS Maximus IX HERO                       | 1         | 1.32%   |
| ASUS G551JM                                | 1         | 1.32%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 5         | 6.58%   |
| Lenovo IdeaPad       | 5         | 6.58%   |
| ASUS TUF             | 5         | 6.58%   |
| Dell Precision       | 4         | 5.26%   |
| Acer Aspire          | 4         | 5.26%   |
| Lenovo Legion        | 3         | 3.95%   |
| Dell Latitude        | 3         | 3.95%   |
| ASUS VivoBook        | 3         | 3.95%   |
| ASUS ROG             | 3         | 3.95%   |
| MSI MS-7971          | 2         | 2.63%   |
| HP Laptop            | 2         | 2.63%   |
| Dell Inspiron        | 2         | 2.63%   |
| ASUS ASUS            | 2         | 2.63%   |
| Pegatron p6-2026     | 1         | 1.32%   |
| Pegatron D15K        | 1         | 1.32%   |
| MSI MS-7B61          | 1         | 1.32%   |
| MSI GP73             | 1         | 1.32%   |
| MSI GF63             | 1         | 1.32%   |
| Lenovo Yoga          | 1         | 1.32%   |
| Lenovo Y520-15IKBN   | 1         | 1.32%   |
| HUAWEI WRT-WX9       | 1         | 1.32%   |
| HP Z230              | 1         | 1.32%   |
| HP ProOne            | 1         | 1.32%   |
| HP Pavilion          | 1         | 1.32%   |
| HP Notebook          | 1         | 1.32%   |
| HP ENVY              | 1         | 1.32%   |
| HP Compaq            | 1         | 1.32%   |
| Gigabyte Z170X-UD3   | 1         | 1.32%   |
| Gigabyte X570        | 1         | 1.32%   |
| Gigabyte B460MDS3HV2 | 1         | 1.32%   |
| Dell Vostro          | 1         | 1.32%   |
| Dell Venue           | 1         | 1.32%   |
| BESSTAR Tech X500    | 1         | 1.32%   |
| ASUS X510UNR         | 1         | 1.32%   |
| ASUS UX303LN         | 1         | 1.32%   |
| ASUS PRIME           | 1         | 1.32%   |
| ASUS P7P55           | 1         | 1.32%   |
| ASUS P5Q             | 1         | 1.32%   |
| ASUS Maximus         | 1         | 1.32%   |
| ASUS G551JM          | 1         | 1.32%   |
| ASRock X570          | 1         | 1.32%   |
| ASRock B450M         | 1         | 1.32%   |
| ASRock AB350         | 1         | 1.32%   |
| Aquarius NS585       | 1         | 1.32%   |
| Apple MacBookAir6    | 1         | 1.32%   |
| Unknown              | 1         | 1.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 16        | 21.05%  |
| 2020 | 11        | 14.47%  |
| 2018 | 9         | 11.84%  |
| 2017 | 8         | 10.53%  |
| 2012 | 6         | 7.89%   |
| 2021 | 5         | 6.58%   |
| 2013 | 5         | 6.58%   |
| 2015 | 4         | 5.26%   |
| 2014 | 3         | 3.95%   |
| 2016 | 2         | 2.63%   |
| 2011 | 2         | 2.63%   |
| 2010 | 2         | 2.63%   |
| 2009 | 2         | 2.63%   |
| 2008 | 1         | 1.32%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 43        | 56.58%  |
| Desktop     | 30        | 39.47%  |
| Convertible | 2         | 2.63%   |
| Server      | 1         | 1.32%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 76        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 76        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 22        | 28.95%  |
| 16.01-24.0  | 20        | 26.32%  |
| 8.01-16.0   | 16        | 21.05%  |
| 32.01-64.0  | 8         | 10.53%  |
| 3.01-4.0    | 6         | 7.89%   |
| 24.01-32.0  | 3         | 3.95%   |
| 64.01-256.0 | 1         | 1.32%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 29        | 34.52%  |
| 1.01-2.0   | 20        | 23.81%  |
| 4.01-8.0   | 15        | 17.86%  |
| 3.01-4.0   | 10        | 11.9%   |
| 8.01-16.0  | 4         | 4.76%   |
| 16.01-24.0 | 2         | 2.38%   |
| 0.51-1.0   | 2         | 2.38%   |
| 0.01-0.5   | 2         | 2.38%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 40        | 52.63%  |
| 2      | 20        | 26.32%  |
| 3      | 8         | 10.53%  |
| 4      | 4         | 5.26%   |
| 6      | 2         | 2.63%   |
| 7      | 1         | 1.32%   |
| 5      | 1         | 1.32%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 58        | 76.32%  |
| Yes       | 18        | 23.68%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 62        | 81.58%  |
| No        | 14        | 18.42%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 61        | 80.26%  |
| No        | 15        | 19.74%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 59        | 76.62%  |
| No        | 18        | 23.38%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country               | Computers | Percent |
|-----------------------|-----------|---------|
| USA                   | 19        | 25%     |
| India                 | 8         | 10.53%  |
| Poland                | 5         | 6.58%   |
| Germany               | 5         | 6.58%   |
| Italy                 | 3         | 3.95%   |
| Greece                | 3         | 3.95%   |
| France                | 3         | 3.95%   |
| UK                    | 2         | 2.63%   |
| Russia                | 2         | 2.63%   |
| Netherlands           | 2         | 2.63%   |
| Canada                | 2         | 2.63%   |
| Australia             | 2         | 2.63%   |
| Zambia                | 1         | 1.32%   |
| Turkey                | 1         | 1.32%   |
| Togo                  | 1         | 1.32%   |
| Sweden                | 1         | 1.32%   |
| Spain                 | 1         | 1.32%   |
| Portugal              | 1         | 1.32%   |
| Palestinian Territory | 1         | 1.32%   |
| Pakistan              | 1         | 1.32%   |
| Norway                | 1         | 1.32%   |
| Morocco               | 1         | 1.32%   |
| Mongolia              | 1         | 1.32%   |
| Mexico                | 1         | 1.32%   |
| Malaysia              | 1         | 1.32%   |
| Lebanon               | 1         | 1.32%   |
| Israel                | 1         | 1.32%   |
| Hungary               | 1         | 1.32%   |
| Denmark               | 1         | 1.32%   |
| Colombia              | 1         | 1.32%   |
| Brazil                | 1         | 1.32%   |
| Austria               | 1         | 1.32%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Longmont       | 3         | 3.95%   |
| Madurai        | 2         | 2.63%   |
| Zell am See    | 1         | 1.32%   |
| Wroclaw        | 1         | 1.32%   |
| Wrexham        | 1         | 1.32%   |
| Wells          | 1         | 1.32%   |
| Warsaw         | 1         | 1.32%   |
| Ulan Bator     | 1         | 1.32%   |
| Toronto        | 1         | 1.32%   |
| Tel Aviv       | 1         | 1.32%   |
| Taranto        | 1         | 1.32%   |
| Stuttgart      | 1         | 1.32%   |
| Stavropol      | 1         | 1.32%   |
| Springfield    | 1         | 1.32%   |
| Silkeborg      | 1         | 1.32%   |
| Shadrinsk      | 1         | 1.32%   |
| Salt Lake City | 1         | 1.32%   |
| Ramallah       | 1         | 1.32%   |
| Pune           | 1         | 1.32%   |
| Poznan         | 1         | 1.32%   |
| Portland       | 1         | 1.32%   |
| Pirmasens      | 1         | 1.32%   |
| Phoenix        | 1         | 1.32%   |
| Pavia          | 1         | 1.32%   |
| Passos         | 1         | 1.32%   |
| Paris          | 1         | 1.32%   |
| Oslo           | 1         | 1.32%   |
| Oberursel      | 1         | 1.32%   |
| New Haven      | 1         | 1.32%   |
| Neu-Ulm        | 1         | 1.32%   |
| Mumbai         | 1         | 1.32%   |
| Monterrey      | 1         | 1.32%   |
| Melbourne      | 1         | 1.32%   |
| Lusaka         | 1         | 1.32%   |
| Lucknow        | 1         | 1.32%   |
| Lublin         | 1         | 1.32%   |
| Longview       | 1         | 1.32%   |
| Longvic        | 1         | 1.32%   |
| Lomé          | 1         | 1.32%   |
| Lisbon         | 1         | 1.32%   |
| Lamia          | 1         | 1.32%   |
| Kuala Lumpur   | 1         | 1.32%   |
| Kista          | 1         | 1.32%   |
| Istanbul       | 1         | 1.32%   |
| Islamabad      | 1         | 1.32%   |
| Ioannina       | 1         | 1.32%   |
| Gdansk         | 1         | 1.32%   |
| Ernakulam      | 1         | 1.32%   |
| Dunkirk        | 1         | 1.32%   |
| Denver         | 1         | 1.32%   |
| Delft          | 1         | 1.32%   |
| Danville       | 1         | 1.32%   |
| Clearfield     | 1         | 1.32%   |
| Chicago        | 1         | 1.32%   |
| Casablanca     | 1         | 1.32%   |
| Canovelles     | 1         | 1.32%   |
| Candiac        | 1         | 1.32%   |
| Buffalo        | 1         | 1.32%   |
| Budapest       | 1         | 1.32%   |
| Bristol        | 1         | 1.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 24        | 37     | 18.75%  |
| Samsung Electronics       | 23        | 34     | 17.97%  |
| WDC                       | 20        | 26     | 15.63%  |
| Toshiba                   | 8         | 10     | 6.25%   |
| Kingston                  | 8         | 11     | 6.25%   |
| HGST                      | 6         | 6      | 4.69%   |
| SanDisk                   | 4         | 5      | 3.13%   |
| Intel                     | 4         | 6      | 3.13%   |
| Unknown                   | 3         | 4      | 2.34%   |
| Phison                    | 3         | 3      | 2.34%   |
| Micron Technology         | 3         | 5      | 2.34%   |
| LITEON                    | 2         | 2      | 1.56%   |
| Crucial                   | 2         | 2      | 1.56%   |
| China                     | 2         | 2      | 1.56%   |
| XPG                       | 1         | 1      | 0.78%   |
| Transcend                 | 1         | 1      | 0.78%   |
| SK hynix                  | 1         | 1      | 0.78%   |
| PNY                       | 1         | 1      | 0.78%   |
| Plextor                   | 1         | 1      | 0.78%   |
| Micron/Crucial Technology | 1         | 1      | 0.78%   |
| LITEONIT                  | 1         | 1      | 0.78%   |
| KIOXIA                    | 1         | 1      | 0.78%   |
| Intenso                   | 1         | 1      | 0.78%   |
| Inateck                   | 1         | 1      | 0.78%   |
| Hitachi                   | 1         | 1      | 0.78%   |
| GOODRAM                   | 1         | 1      | 0.78%   |
| Apple                     | 1         | 1      | 0.78%   |
| Apacer                    | 1         | 1      | 0.78%   |
| A-DATA Technology         | 1         | 1      | 0.78%   |
| 2-Power                   | 1         | 1      | 0.78%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 3         | 2.01%   |
| Seagate One Touch HDD 5TB            | 3         | 2.01%   |
| Kingston SA400S37240G 240GB SSD      | 3         | 2.01%   |
| Toshiba MQ04ABF100 1TB               | 2         | 1.34%   |
| Seagate ST1000LM049-2GH172 1TB       | 2         | 1.34%   |
| Seagate ST1000LM048-2E7172 1TB       | 2         | 1.34%   |
| Seagate ST1000DM010-2EP102 1TB       | 2         | 1.34%   |
| SanDisk NVMe SSD Drive 500GB         | 2         | 1.34%   |
| Samsung SSD 970 EVO 1TB              | 2         | 1.34%   |
| Samsung SSD 860 EVO 250GB            | 2         | 1.34%   |
| Samsung SSD 860 EVO 1TB              | 2         | 1.34%   |
| Samsung SSD 850 EVO 250GB            | 2         | 1.34%   |
| HGST HTS545050A7E680 500GB           | 2         | 1.34%   |
| XPG GAMMIX S50 1TB                   | 1         | 0.67%   |
| WDC WDS512G1X0C-00ENX0 512GB         | 1         | 0.67%   |
| WDC WDS500G3XHC-00SJG0 500GB         | 1         | 0.67%   |
| WDC WDS500G3X0C-00SJG0 500GB         | 1         | 0.67%   |
| WDC WDS500G2B0B-00YS70 500GB SSD     | 1         | 0.67%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 1         | 0.67%   |
| WDC WDS100T1X0E-00AFY0 1TB           | 1         | 0.67%   |
| WDC WDBNCE0010PNC 1TB SSD            | 1         | 0.67%   |
| WDC WD800JD-00MSA1 80GB              | 1         | 0.67%   |
| WDC WD7500BPKT-75PK4T0 752GB         | 1         | 0.67%   |
| WDC WD6400AAKS-22A7B2 640GB          | 1         | 0.67%   |
| WDC WD5000AAVS-00ZTB0 500GB          | 1         | 0.67%   |
| WDC WD5000AAKX-60U6AA0 500GB         | 1         | 0.67%   |
| WDC WD2500BEVT-60ZCT1 250GB          | 1         | 0.67%   |
| WDC WD20EZRZ-60Z5HB0 2TB             | 1         | 0.67%   |
| WDC WD20EZBX-00AYRA0 2TB             | 1         | 0.67%   |
| WDC WD2003FZEX-00SRLA0 2TB           | 1         | 0.67%   |
| WDC WD10EZEX-60WN4A0 1TB             | 1         | 0.67%   |
| WDC WD10EZEX-22MFCA0 1TB             | 1         | 0.67%   |
| WDC WD10EZEX-00KUWA0 1TB             | 1         | 0.67%   |
| WDC WD1002FAEX-00Z3A0 1TB            | 1         | 0.67%   |
| WDC PC SN720 SDAPNTW-512G-1027 512GB | 1         | 0.67%   |
| WDC PC SN530 SDBPNPZ-256G-1114 256GB | 1         | 0.67%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB | 1         | 0.67%   |
| WDC PC SN520 SDAPMUW-256G-1101 256GB | 1         | 0.67%   |
| Unknown MMC Card  64GB               | 1         | 0.67%   |
| Unknown MMC Card  4GB                | 1         | 0.67%   |
| Unknown MMC Card  128GB              | 1         | 0.67%   |
| Unknown G1J38E  64GB                 | 1         | 0.67%   |
| Transcend TS120GSSD220S 120GB        | 1         | 0.67%   |
| Toshiba MQ01ABF050M 500GB            | 1         | 0.67%   |
| Toshiba MQ01ABD100 1TB               | 1         | 0.67%   |
| Toshiba MK4058GSX 400GB              | 1         | 0.67%   |
| Toshiba KBG40ZNT512G MEMORY 512GB    | 1         | 0.67%   |
| Toshiba KBG30ZMV256G 256GB           | 1         | 0.67%   |
| Toshiba HDWR160 6TB                  | 1         | 0.67%   |
| Toshiba HDWE160 6TB                  | 1         | 0.67%   |
| Toshiba DT01ACA300 3TB               | 1         | 0.67%   |
| SK hynix HFM256GDJTNG-8310A 256GB    | 1         | 0.67%   |
| Seagate ST9500325AS 500GB            | 1         | 0.67%   |
| Seagate ST500LT012-9WS142 500GB      | 1         | 0.67%   |
| Seagate ST500LM000-SSHD-8GB          | 1         | 0.67%   |
| Seagate ST3500418AS 500GB            | 1         | 0.67%   |
| Seagate ST31000524AS 1TB             | 1         | 0.67%   |
| Seagate ST250DM000-1BD141 250GB      | 1         | 0.67%   |
| Seagate ST2000DX001-1CM164 2TB       | 1         | 0.67%   |
| Seagate ST2000DM008-2FR102 2TB       | 1         | 0.67%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 24        | 36     | 48%     |
| WDC                 | 11        | 14     | 22%     |
| Toshiba             | 6         | 8      | 12%     |
| HGST                | 6         | 6      | 12%     |
| Samsung Electronics | 2         | 2      | 4%      |
| Hitachi             | 1         | 1      | 2%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 14     | 29.73%  |
| Kingston            | 5         | 7      | 13.51%  |
| WDC                 | 3         | 3      | 8.11%   |
| LITEON              | 2         | 2      | 5.41%   |
| Crucial             | 2         | 2      | 5.41%   |
| China               | 2         | 2      | 5.41%   |
| Transcend           | 1         | 1      | 2.7%    |
| SanDisk             | 1         | 1      | 2.7%    |
| PNY                 | 1         | 1      | 2.7%    |
| Plextor             | 1         | 1      | 2.7%    |
| Micron Technology   | 1         | 1      | 2.7%    |
| LITEONIT            | 1         | 1      | 2.7%    |
| Intenso             | 1         | 1      | 2.7%    |
| Intel               | 1         | 1      | 2.7%    |
| GOODRAM             | 1         | 1      | 2.7%    |
| Apple               | 1         | 1      | 2.7%    |
| Apacer              | 1         | 1      | 2.7%    |
| 2-Power             | 1         | 1      | 2.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 42        | 67     | 36.84%  |
| NVMe | 37        | 56     | 32.46%  |
| SSD  | 32        | 42     | 28.07%  |
| MMC  | 3         | 4      | 2.63%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 56        | 101    | 53.85%  |
| NVMe | 37        | 55     | 35.58%  |
| SAS  | 8         | 9      | 7.69%   |
| MMC  | 3         | 4      | 2.88%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 36        | 52     | 45.57%  |
| 0.51-1.0   | 29        | 37     | 36.71%  |
| 4.01-10.0  | 7         | 9      | 8.86%   |
| 1.01-2.0   | 6         | 10     | 7.59%   |
| 2.01-3.0   | 1         | 1      | 1.27%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| More than 3000 | 23        | 28.4%   |
| 1001-2000      | 18        | 22.22%  |
| 501-1000       | 11        | 13.58%  |
| 251-500        | 7         | 8.64%   |
| 101-250        | 6         | 7.41%   |
| 1-20           | 4         | 4.94%   |
| 51-100         | 4         | 4.94%   |
| Unknown        | 4         | 4.94%   |
| 21-50          | 2         | 2.47%   |
| 2001-3000      | 2         | 2.47%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 23        | 28.4%   |
| 51-100         | 16        | 19.75%  |
| 1-20           | 13        | 16.05%  |
| 251-500        | 7         | 8.64%   |
| 501-1000       | 7         | 8.64%   |
| 21-50          | 4         | 4.94%   |
| Unknown        | 4         | 4.94%   |
| 2001-3000      | 3         | 3.7%    |
| More than 3000 | 2         | 2.47%   |
| 1001-2000      | 2         | 2.47%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| WDC WD5000AAKX-60U6AA0 500GB     | 1         | 1      | 6.25%   |
| WDC WD1002FAEX-00Z3A0 1TB        | 1         | 2      | 6.25%   |
| Toshiba MQ01ABF050M 500GB        | 1         | 1      | 6.25%   |
| Toshiba MQ01ABD100 1TB           | 1         | 1      | 6.25%   |
| Toshiba MK4058GSX 400GB          | 1         | 1      | 6.25%   |
| Seagate ST9500325AS 500GB        | 1         | 1      | 6.25%   |
| Seagate ST500LM000-SSHD-8GB      | 1         | 1      | 6.25%   |
| Seagate ST31000524AS 1TB         | 1         | 1      | 6.25%   |
| Seagate ST2000DM006-2DM164 2TB   | 1         | 1      | 6.25%   |
| Seagate ST1000LM049-2GH172 1TB   | 1         | 1      | 6.25%   |
| Seagate ST1000LM048-2E7172 1TB   | 1         | 1      | 6.25%   |
| Kingston SUV400S37240G 240GB SSD | 1         | 1      | 6.25%   |
| Hitachi HTS725050A9A364 500GB    | 1         | 1      | 6.25%   |
| HGST HTS725032A7E630 320GB       | 1         | 1      | 6.25%   |
| HGST HTS721010A9E630 1TB         | 1         | 1      | 6.25%   |
| China SATA3 240GB SSD            | 1         | 1      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 6         | 6      | 40%     |
| WDC      | 2         | 3      | 13.33%  |
| Toshiba  | 2         | 3      | 13.33%  |
| HGST     | 2         | 2      | 13.33%  |
| Kingston | 1         | 1      | 6.67%   |
| Hitachi  | 1         | 1      | 6.67%   |
| China    | 1         | 1      | 6.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 6      | 46.15%  |
| WDC     | 2         | 3      | 15.38%  |
| Toshiba | 2         | 3      | 15.38%  |
| HGST    | 2         | 2      | 15.38%  |
| Hitachi | 1         | 1      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 13        | 15     | 86.67%  |
| SSD  | 2         | 2      | 13.33%  |

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
| Works    | 59        | 112    | 64.13%  |
| Detected | 18        | 40     | 19.57%  |
| Malfunc  | 15        | 17     | 16.3%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 59        | 53.15%  |
| Samsung Electronics          | 12        | 10.81%  |
| AMD                          | 12        | 10.81%  |
| SanDisk                      | 10        | 9.01%   |
| Phison Electronics           | 3         | 2.7%    |
| Micron Technology            | 3         | 2.7%    |
| Kingston Technology Company  | 3         | 2.7%    |
| Toshiba America Info Systems | 2         | 1.8%    |
| SK hynix                     | 1         | 0.9%    |
| Seagate Technology           | 1         | 0.9%    |
| Realtek Semiconductor        | 1         | 0.9%    |
| Micron/Crucial Technology    | 1         | 0.9%    |
| KIOXIA                       | 1         | 0.9%    |
| ASMedia Technology           | 1         | 0.9%    |
| ADATA Technology             | 1         | 0.9%    |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 11        | 9.09%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 6         | 4.96%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5         | 4.13%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 4.13%   |
| Intel SATA Controller [RAID mode]                                              | 4         | 3.31%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 3.31%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 4         | 3.31%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 3.31%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4         | 3.31%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 3         | 2.48%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 2.48%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 2.48%   |
| Micron Non-Volatile memory controller                                          | 3         | 2.48%   |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 2.48%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 2.48%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 3         | 2.48%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 2.48%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 2         | 1.65%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2         | 1.65%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 1.65%   |
| Phison E12 NVMe Controller                                                     | 2         | 1.65%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 2         | 1.65%   |
| Intel Tiger Lake-LP SATA Controller                                            | 2         | 1.65%   |
| Intel SSD 660P Series                                                          | 2         | 1.65%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 1.65%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 1.65%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 1.65%   |
| AMD 400 Series Chipset SATA Controller                                         | 2         | 1.65%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 0.83%   |
| Seagate FireCuda 510 SSD                                                       | 1         | 0.83%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 0.83%   |
| SanDisk WD Blue SN570 NVMe SSD                                                 | 1         | 0.83%   |
| SanDisk WD Black NVMe SSD                                                      | 1         | 0.83%   |
| SanDisk PC SN520 NVMe SSD                                                      | 1         | 0.83%   |
| SanDisk Non-Volatile memory controller                                         | 1         | 0.83%   |
| Samsung Apple PCIe SSD                                                         | 1         | 0.83%   |
| Realtek Realtek Non-Volatile memory controller                                 | 1         | 0.83%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1         | 0.83%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 1         | 0.83%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 1         | 0.83%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 1         | 0.83%   |
| Intel Non-Volatile memory controller                                           | 1         | 0.83%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 1         | 0.83%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 0.83%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 0.83%   |
| Intel Comet Lake PCH-LP SATA RAID Premium Controller                           | 1         | 0.83%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 1         | 0.83%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1         | 0.83%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 1         | 0.83%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 1         | 0.83%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 1         | 0.83%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 1         | 0.83%   |
| AMD FCH SATA Controller D                                                      | 1         | 0.83%   |
| AMD 500 Series Chipset SATA Controller                                         | 1         | 0.83%   |
| AMD 300 Series Chipset SATA Controller                                         | 1         | 0.83%   |
| ADATA Non-Volatile memory controller                                           | 1         | 0.83%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 61        | 55.45%  |
| NVMe | 37        | 33.64%  |
| RAID | 12        | 10.91%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 62        | 81.58%  |
| AMD    | 14        | 18.42%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-7500U CPU @ 2.70GHz       | 3         | 3.95%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 3         | 3.95%   |
| AMD Ryzen 5 3600X 6-Core Processor      | 3         | 3.95%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 2         | 2.63%   |
| Intel Core i7-4712HQ CPU @ 2.30GHz      | 2         | 2.63%   |
| Intel Core i5-9300H CPU @ 2.40GHz       | 2         | 2.63%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 2         | 2.63%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 2         | 2.63%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 2         | 2.63%   |
| Intel Core i3-8100 CPU @ 3.60GHz        | 2         | 2.63%   |
| Intel Genuine CPU 0000 @ 2.10GHz        | 1         | 1.32%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 1         | 1.32%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 1         | 1.32%   |
| Intel Core i7-8700K CPU @ 3.70GHz       | 1         | 1.32%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 1         | 1.32%   |
| Intel Core i7-7700K CPU @ 4.20GHz       | 1         | 1.32%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 1         | 1.32%   |
| Intel Core i7-7600U CPU @ 2.80GHz       | 1         | 1.32%   |
| Intel Core i7-6700K CPU @ 4.00GHz       | 1         | 1.32%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz      | 1         | 1.32%   |
| Intel Core i7-4702HQ CPU @ 2.20GHz      | 1         | 1.32%   |
| Intel Core i7-4650U CPU @ 1.70GHz       | 1         | 1.32%   |
| Intel Core i7-3720QM CPU @ 2.60GHz      | 1         | 1.32%   |
| Intel Core i7-2760QM CPU @ 2.40GHz      | 1         | 1.32%   |
| Intel Core i7-10870H CPU @ 2.20GHz      | 1         | 1.32%   |
| Intel Core i7 CPU 870 @ 2.93GHz         | 1         | 1.32%   |
| Intel Core i7 CPU 860 @ 2.80GHz         | 1         | 1.32%   |
| Intel Core i5-9600K CPU @ 3.70GHz       | 1         | 1.32%   |
| Intel Core i5-9400F CPU @ 2.90GHz       | 1         | 1.32%   |
| Intel Core i5-9400 CPU @ 2.90GHz        | 1         | 1.32%   |
| Intel Core i5-6600 CPU @ 3.30GHz        | 1         | 1.32%   |
| Intel Core i5-6500 CPU @ 3.20GHz        | 1         | 1.32%   |
| Intel Core i5-4670 CPU @ 3.40GHz        | 1         | 1.32%   |
| Intel Core i5-4590T CPU @ 2.00GHz       | 1         | 1.32%   |
| Intel Core i5-4300Y CPU @ 1.60GHz       | 1         | 1.32%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 1         | 1.32%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 1         | 1.32%   |
| Intel Core i5-3340M CPU @ 2.70GHz       | 1         | 1.32%   |
| Intel Core i5-3337U CPU @ 1.80GHz       | 1         | 1.32%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 1         | 1.32%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 1         | 1.32%   |
| Intel Core i5-10400F CPU @ 2.90GHz      | 1         | 1.32%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 1         | 1.32%   |
| Intel Core i3-6100U CPU @ 2.30GHz       | 1         | 1.32%   |
| Intel Core i3-2120 CPU @ 3.30GHz        | 1         | 1.32%   |
| Intel Core i3 CPU 540 @ 3.07GHz         | 1         | 1.32%   |
| Intel Core 2 Quad CPU Q9650 @ 3.00GHz   | 1         | 1.32%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz    | 1         | 1.32%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 1         | 1.32%   |
| Intel Celeron J4125 CPU @ 2.00GHz       | 1         | 1.32%   |
| Intel 11th Gen Core i5-11300H @ 3.10GHz | 1         | 1.32%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz | 1         | 1.32%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 1         | 1.32%   |
| AMD Ryzen 7 5800X 8-Core Processor      | 1         | 1.32%   |
| AMD Ryzen 7 5700G with Radeon Graphics  | 1         | 1.32%   |
| AMD Ryzen 7 4800H with Radeon Graphics  | 1         | 1.32%   |
| AMD Ryzen 7 2700 Eight-Core Processor   | 1         | 1.32%   |
| AMD Ryzen 5 5600X 6-Core Processor      | 1         | 1.32%   |
| AMD Ryzen 5 3600 6-Core Processor       | 1         | 1.32%   |
| AMD Ryzen 5 1600 Six-Core Processor     | 1         | 1.32%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Core i5     | 24        | 31.58%  |
| Intel Core i7     | 23        | 30.26%  |
| AMD Ryzen 5       | 6         | 7.89%   |
| Other             | 5         | 6.58%   |
| Intel Core i3     | 5         | 6.58%   |
| AMD Ryzen 7       | 4         | 5.26%   |
| Intel Celeron     | 2         | 2.63%   |
| Intel Genuine     | 1         | 1.32%   |
| Intel Core 2 Quad | 1         | 1.32%   |
| Intel Core 2 Duo  | 1         | 1.32%   |
| AMD Ryzen 9       | 1         | 1.32%   |
| AMD Ryzen 3       | 1         | 1.32%   |
| AMD Athlon        | 1         | 1.32%   |
| AMD A6            | 1         | 1.32%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 36        | 47.37%  |
| 2      | 20        | 26.32%  |
| 6      | 13        | 17.11%  |
| 8      | 6         | 7.89%   |
| 12     | 1         | 1.32%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 76        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 61        | 79.22%  |
| 1      | 16        | 20.78%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 76        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 16        | 20.51%  |
| 0x906ea    | 6         | 7.69%   |
| 0x806c1    | 5         | 6.41%   |
| 0x306a9    | 5         | 6.41%   |
| 0x806ec    | 4         | 5.13%   |
| 0x806e9    | 4         | 5.13%   |
| 0x08701021 | 4         | 5.13%   |
| 0x506e3    | 3         | 3.85%   |
| 0x306c3    | 3         | 3.85%   |
| 0x906ed    | 2         | 2.56%   |
| 0x906eb    | 2         | 2.56%   |
| 0x906e9    | 2         | 2.56%   |
| 0x806eb    | 2         | 2.56%   |
| 0x40651    | 2         | 2.56%   |
| 0x1067a    | 2         | 2.56%   |
| 0x0a201016 | 2         | 2.56%   |
| 0xa0653    | 1         | 1.28%   |
| 0xa0652    | 1         | 1.28%   |
| 0x706e5    | 1         | 1.28%   |
| 0x706a8    | 1         | 1.28%   |
| 0x406e3    | 1         | 1.28%   |
| 0x206a7    | 1         | 1.28%   |
| 0x20655    | 1         | 1.28%   |
| 0x106e5    | 1         | 1.28%   |
| 0x0a50000b | 1         | 1.28%   |
| 0x08701013 | 1         | 1.28%   |
| 0x08600106 | 1         | 1.28%   |
| 0x08108109 | 1         | 1.28%   |
| 0x0810100b | 1         | 1.28%   |
| 0x06006705 | 1         | 1.28%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 26        | 34.21%  |
| Haswell       | 9         | 11.84%  |
| Zen 2         | 6         | 7.89%   |
| IvyBridge     | 6         | 7.89%   |
| TigerLake     | 5         | 6.58%   |
| Skylake       | 4         | 5.26%   |
| Zen+          | 3         | 3.95%   |
| Zen 3         | 3         | 3.95%   |
| SandyBridge   | 2         | 2.63%   |
| Penryn        | 2         | 2.63%   |
| Nehalem       | 2         | 2.63%   |
| Goldmont plus | 2         | 2.63%   |
| CometLake     | 2         | 2.63%   |
| Zen           | 1         | 1.32%   |
| Westmere      | 1         | 1.32%   |
| IceLake       | 1         | 1.32%   |
| Excavator     | 1         | 1.32%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 48        | 46.6%   |
| Nvidia | 40        | 38.83%  |
| AMD    | 15        | 14.56%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                      | 5         | 4.81%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 4         | 3.85%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 4         | 3.85%   |
| Intel HD Graphics 620                                                                 | 4         | 3.85%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 4         | 3.85%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 4         | 3.85%   |
| Nvidia GK107GLM [Quadro K1100M]                                                       | 3         | 2.88%   |
| Intel UHD Graphics 620                                                                | 3         | 2.88%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                             | 3         | 2.88%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                               | 3         | 2.88%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                | 2         | 1.92%   |
| Nvidia GP108M [GeForce MX250]                                                         | 2         | 1.92%   |
| Nvidia GP108M [GeForce MX150]                                                         | 2         | 1.92%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                   | 2         | 1.92%   |
| Nvidia GP104 [GeForce GTX 1080]                                                       | 2         | 1.92%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 2         | 1.92%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 2         | 1.92%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 2         | 1.92%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 2         | 1.92%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 2         | 1.92%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 1         | 0.96%   |
| Nvidia TU117M                                                                         | 1         | 0.96%   |
| Nvidia TU117 [GeForce GTX 1650]                                                       | 1         | 0.96%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 1         | 0.96%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                 | 1         | 0.96%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                                 | 1         | 0.96%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                               | 1         | 0.96%   |
| Nvidia TU106BM [GeForce RTX 2070 Mobile / Max-Q]                                      | 1         | 0.96%   |
| Nvidia GP108M [GeForce MX230]                                                         | 1         | 0.96%   |
| Nvidia GP108 [GeForce GT 1030]                                                        | 1         | 0.96%   |
| Nvidia GP107M [GeForce MX350]                                                         | 1         | 0.96%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 1         | 0.96%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 1         | 0.96%   |
| Nvidia GP107 [GeForce GTX 1050]                                                       | 1         | 0.96%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                    | 1         | 0.96%   |
| Nvidia GM206 [GeForce GTX 960]                                                        | 1         | 0.96%   |
| Nvidia GM108M [GeForce 840M]                                                          | 1         | 0.96%   |
| Nvidia GM107M [GeForce GTX 860M]                                                      | 1         | 0.96%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                     | 1         | 0.96%   |
| Nvidia GK208B [GeForce GT 710]                                                        | 1         | 0.96%   |
| Nvidia GK107GLM [Quadro K1000M]                                                       | 1         | 0.96%   |
| Nvidia GK107 [GeForce GT 740]                                                         | 1         | 0.96%   |
| Nvidia GF119M [NVS 4200M]                                                             | 1         | 0.96%   |
| Nvidia GF108GLM [NVS 5200M]                                                           | 1         | 0.96%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 1         | 0.96%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                                        | 1         | 0.96%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller           | 1         | 0.96%   |
| Intel Tiger Lake UHD Graphics                                                         | 1         | 0.96%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 1         | 0.96%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 1         | 0.96%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 1         | 0.96%   |
| Intel HD Graphics 630                                                                 | 1         | 0.96%   |
| Intel Haswell-ULT High Definition Audio Controller [HD Graphics]                      | 1         | 0.96%   |
| Intel Core Processor Integrated Graphics Controller                                   | 1         | 0.96%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 1         | 0.96%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                    | 1         | 0.96%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 1         | 0.96%   |
| AMD Tonga PRO [Radeon R9 285/380]                                                     | 1         | 0.96%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                              | 1         | 0.96%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                      | 1         | 0.96%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Intel + Nvidia | 23        | 30.26%  |
| 1 x Intel      | 20        | 26.32%  |
| 1 x Nvidia     | 16        | 21.05%  |
| 1 x AMD        | 12        | 15.79%  |
| Intel + AMD    | 3         | 3.95%   |
| 2 x Nvidia     | 1         | 1.32%   |
| 2 x Intel      | 1         | 1.32%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 45        | 58.44%  |
| Proprietary | 30        | 38.96%  |
| Unknown     | 2         | 2.6%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 44        | 57.14%  |
| 1.01-2.0   | 14        | 18.18%  |
| 5.01-6.0   | 6         | 7.79%   |
| 7.01-8.0   | 5         | 6.49%   |
| 3.01-4.0   | 3         | 3.9%    |
| 0.01-0.5   | 3         | 3.9%    |
| 8.01-16.0  | 2         | 2.6%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 14        | 15.91%  |
| AU Optronics         | 11        | 12.5%   |
| BOE                  | 9         | 10.23%  |
| LG Display           | 8         | 9.09%   |
| Chimei Innolux       | 7         | 7.95%   |
| Goldstar             | 5         | 5.68%   |
| Ancor Communications | 5         | 5.68%   |
| Dell                 | 4         | 4.55%   |
| Sharp                | 3         | 3.41%   |
| AOC                  | 3         | 3.41%   |
| Acer                 | 3         | 3.41%   |
| Hewlett-Packard      | 2         | 2.27%   |
| Apple                | 2         | 2.27%   |
| Sceptre Tech         | 1         | 1.14%   |
| PANDA                | 1         | 1.14%   |
| Lenovo               | 1         | 1.14%   |
| Kogan                | 1         | 1.14%   |
| KOC                  | 1         | 1.14%   |
| Iiyama               | 1         | 1.14%   |
| Idek Iiyama          | 1         | 1.14%   |
| Hitachi              | 1         | 1.14%   |
| Gigabyte Technology  | 1         | 1.14%   |
| CSO                  | 1         | 1.14%   |
| BenQ                 | 1         | 1.14%   |
| ASUSTek Computer     | 1         | 1.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SAM0F14 3840x2160 1872x1053mm 84.6-inch | 2         | 2.2%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch        | 2         | 2.2%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch          | 2         | 2.2%    |
| Sharp LCD Monitor SHP1463 3840x2160 346x194mm 15.6-inch                 | 1         | 1.1%    |
| Sharp LCD Monitor SHP1431 3840x2160 350x190mm 15.7-inch                 | 1         | 1.1%    |
| Sharp LCD Monitor SHP13F8 3200x1800 346x194mm 15.6-inch                 | 1         | 1.1%    |
| Sceptre Tech C27 SPT0ADD 1920x1080 598x336mm 27.0-inch                  | 1         | 1.1%    |
| Samsung Electronics SyncMaster SAM0524 1920x1080 480x270mm 21.7-inch    | 1         | 1.1%    |
| Samsung Electronics SyncMaster SAM02FE 1680x1050 433x271mm 20.1-inch    | 1         | 1.1%    |
| Samsung Electronics SMS24A350H SAM07D6 1920x1080 530x300mm 24.0-inch    | 1         | 1.1%    |
| Samsung Electronics SMBX2450L SAM071F 1920x1080 521x293mm 23.5-inch     | 1         | 1.1%    |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch       | 1         | 1.1%    |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch   | 1         | 1.1%    |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch   | 1         | 1.1%    |
| Samsung Electronics LCD Monitor SDC200F 1366x768 344x193mm 15.5-inch    | 1         | 1.1%    |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1872x1053mm 84.6-inch | 1         | 1.1%    |
| Samsung Electronics LCD Monitor SAM0B60 1920x1080 887x500mm 40.1-inch   | 1         | 1.1%    |
| Samsung Electronics LCD Monitor SAM02EB 1920x540                        | 1         | 1.1%    |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch     | 1         | 1.1%    |
| PANDA LCD Monitor NCP0063 1920x1080 344x194mm 15.5-inch                 | 1         | 1.1%    |
| LG Display LCD Monitor LGD6E01 1366x768 344x194mm 15.5-inch             | 1         | 1.1%    |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch            | 1         | 1.1%    |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch            | 1         | 1.1%    |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch             | 1         | 1.1%    |
| LG Display LCD Monitor LGD03D7 1366x768 310x174mm 14.0-inch             | 1         | 1.1%    |
| LG Display LCD Monitor LGD03AD 1366x768 309x174mm 14.0-inch             | 1         | 1.1%    |
| LG Display LCD Monitor LGD03A3 1366x768 277x156mm 12.5-inch             | 1         | 1.1%    |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch             | 1         | 1.1%    |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                | 1         | 1.1%    |
| Kogan HDMI1 KGN3400 3440x1440 796x334mm 34.0-inch                       | 1         | 1.1%    |
| KOC SXGA85_ANALOG KOC0482 1280x1024 365x292mm 18.4-inch                 | 1         | 1.1%    |
| Iiyama PL2409HD IVM560C 1920x1080 521x293mm 23.5-inch                   | 1         | 1.1%    |
| Idek Iiyama LCD Monitor PL2760Q 2560x1440                               | 1         | 1.1%    |
| Hitachi HISENSE HEC002F 3840x2160 1872x1053mm 84.6-inch                 | 1         | 1.1%    |
| Hewlett-Packard E240c HWP327C 1920x1080 510x290mm 23.1-inch             | 1         | 1.1%    |
| Hewlett-Packard 27w HPN3494 1920x1080 598x336mm 27.0-inch               | 1         | 1.1%    |
| Goldstar ULTRAWIDE GSM76FA 2560x1080 531x298mm 24.0-inch                | 1         | 1.1%    |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                   | 1         | 1.1%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 1         | 1.1%    |
| Goldstar 27GL850 GSM5B7F 2560x1440 597x336mm 27.0-inch                  | 1         | 1.1%    |
| Goldstar 27EA63 GSM598B 1920x1080 600x340mm 27.2-inch                   | 1         | 1.1%    |
| Goldstar 22EN43 GSM59D8 1920x1080 480x270mm 21.7-inch                   | 1         | 1.1%    |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch          | 1         | 1.1%    |
| Dell U3219Q DELA124 3840x2160 697x392mm 31.5-inch                       | 1         | 1.1%    |
| Dell U2913WM DEL408A 2560x1080 673x284mm 28.8-inch                      | 1         | 1.1%    |
| Dell SE2219H DELF10F 1920x1080 480x270mm 21.7-inch                      | 1         | 1.1%    |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                       | 1         | 1.1%    |
| CSO LCD Monitor CSO1403 3840x2400 302x189mm 14.0-inch                   | 1         | 1.1%    |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch        | 1         | 1.1%    |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch        | 1         | 1.1%    |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch        | 1         | 1.1%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch        | 1         | 1.1%    |
| Chimei Innolux LCD Monitor CMN1361 1920x1080 293x165mm 13.2-inch        | 1         | 1.1%    |
| BOE LCD Monitor BOE08E7 1920x1080 344x193mm 15.5-inch                   | 1         | 1.1%    |
| BOE LCD Monitor BOE08E2 1920x1080 344x194mm 15.5-inch                   | 1         | 1.1%    |
| BOE LCD Monitor BOE083B 1920x1080 344x193mm 15.5-inch                   | 1         | 1.1%    |
| BOE LCD Monitor BOE0816 1366x768 344x193mm 15.5-inch                    | 1         | 1.1%    |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                   | 1         | 1.1%    |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                   | 1         | 1.1%    |
| BOE LCD Monitor BOE06D1 1366x768 309x173mm 13.9-inch                    | 1         | 1.1%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 44        | 52.38%  |
| 1366x768 (WXGA)    | 9         | 10.71%  |
| 3840x2160 (4K)     | 8         | 9.52%   |
| 2560x1440 (QHD)    | 5         | 5.95%   |
| 3440x1440          | 3         | 3.57%   |
| 2560x1080          | 3         | 3.57%   |
| 1600x900 (HD+)     | 3         | 3.57%   |
| 3840x2400          | 1         | 1.19%   |
| 3840x1080          | 1         | 1.19%   |
| 3200x1800 (QHD+)   | 1         | 1.19%   |
| 2160x1440          | 1         | 1.19%   |
| 1920x540           | 1         | 1.19%   |
| 1920x1200 (WUXGA)  | 1         | 1.19%   |
| 1680x1050 (WSXGA+) | 1         | 1.19%   |
| 1440x900 (WXGA+)   | 1         | 1.19%   |
| 1280x1024 (SXGA)   | 1         | 1.19%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 29        | 32.95%  |
| 27      | 8         | 9.09%   |
| 21      | 7         | 7.95%   |
| 14      | 6         | 6.82%   |
| 23      | 5         | 5.68%   |
| 13      | 5         | 5.68%   |
| 84      | 4         | 4.55%   |
| 34      | 4         | 4.55%   |
| 24      | 4         | 4.55%   |
| 31      | 3         | 3.41%   |
| 17      | 3         | 3.41%   |
| 28      | 2         | 2.27%   |
| 18      | 2         | 2.27%   |
| Unknown | 2         | 2.27%   |
| 54      | 1         | 1.14%   |
| 48      | 1         | 1.14%   |
| 20      | 1         | 1.14%   |
| 12      | 1         | 1.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 37        | 42.05%  |
| 501-600     | 16        | 18.18%  |
| 401-500     | 10        | 11.36%  |
| 601-700     | 5         | 5.68%   |
| 701-800     | 4         | 4.55%   |
| 351-400     | 4         | 4.55%   |
| 201-300     | 4         | 4.55%   |
| 1501-2000   | 4         | 4.55%   |
| 1001-1500   | 2         | 2.27%   |
| Unknown     | 2         | 2.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 64        | 82.05%  |
| 21/9    | 6         | 7.69%   |
| 16/10   | 4         | 5.13%   |
| 5/4     | 1         | 1.28%   |
| 32/9    | 1         | 1.28%   |
| 3/2     | 1         | 1.28%   |
| Unknown | 1         | 1.28%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 29        | 33.33%  |
| 201-250        | 15        | 17.24%  |
| 81-90          | 9         | 10.34%  |
| 301-350        | 8         | 9.2%    |
| 351-500        | 7         | 8.05%   |
| More than 1000 | 5         | 5.75%   |
| 121-130        | 3         | 3.45%   |
| 71-80          | 2         | 2.3%    |
| 251-300        | 2         | 2.3%    |
| 151-200        | 2         | 2.3%    |
| Unknown        | 2         | 2.3%    |
| 61-70          | 1         | 1.15%   |
| 141-150        | 1         | 1.15%   |
| 501-1000       | 1         | 1.15%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 30        | 35.71%  |
| 51-100        | 23        | 27.38%  |
| 101-120       | 21        | 25%     |
| 161-240       | 4         | 4.76%   |
| More than 240 | 3         | 3.57%   |
| Unknown       | 2         | 2.38%   |
| 1-50          | 1         | 1.19%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 59        | 76.62%  |
| 2     | 15        | 19.48%  |
| 0     | 2         | 2.6%    |
| 3     | 1         | 1.3%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 48        | 43.64%  |
| Realtek Semiconductor             | 39        | 35.45%  |
| Qualcomm Atheros                  | 5         | 4.55%   |
| Broadcom Limited                  | 3         | 2.73%   |
| ASIX Electronics                  | 3         | 2.73%   |
| MediaTek                          | 2         | 1.82%   |
| Ericsson Business Mobile Networks | 2         | 1.82%   |
| Broadcom                          | 2         | 1.82%   |
| TP-Link                           | 1         | 0.91%   |
| Samsung Electronics               | 1         | 0.91%   |
| Qualcomm                          | 1         | 0.91%   |
| NetGear                           | 1         | 0.91%   |
| Microsoft                         | 1         | 0.91%   |
| Marvell Technology Group          | 1         | 0.91%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller         | 30        | 22.9%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                     | 6         | 4.58%   |
| Intel Wi-Fi 6 AX200                                                       | 5         | 3.82%   |
| Intel Cannon Lake PCH CNVi WiFi                                           | 5         | 3.82%   |
| Intel Wireless 7260                                                       | 4         | 3.05%   |
| Intel Wi-Fi 6 AX201                                                       | 4         | 3.05%   |
| Intel I211 Gigabit Network Connection                                     | 4         | 3.05%   |
| Intel Ethernet Connection (2) I219-V                                      | 4         | 3.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                              | 4         | 3.05%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 3         | 2.29%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                  | 3         | 2.29%   |
| Realtek RTL8125 2.5GbE Controller                                         | 3         | 2.29%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                  | 3         | 2.29%   |
| ASIX AX88179 Gigabit Ethernet                                             | 3         | 2.29%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                           | 2         | 1.53%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                | 2         | 1.53%   |
| Intel Wireless-AC 9260                                                    | 2         | 1.53%   |
| Intel Wireless 8265 / 8275                                                | 2         | 1.53%   |
| Intel Ethernet Connection (7) I219-V                                      | 2         | 1.53%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                         | 2         | 1.53%   |
| Ericsson Business Mobile Networks H5321 gw Mobile Broadband Module        | 2         | 1.53%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                | 2         | 1.53%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                       | 1         | 0.76%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)               | 1         | 0.76%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                        | 1         | 0.76%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                           | 1         | 0.76%   |
| Realtek RTL8723DE Wireless Network Adapter                                | 1         | 0.76%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                           | 1         | 0.76%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                     | 1         | 0.76%   |
| Qualcomm Nokia X100                                                       | 1         | 0.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                | 1         | 0.76%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                 | 1         | 0.76%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                          | 1         | 0.76%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet            | 1         | 0.76%   |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1         | 0.76%   |
| Microsoft Xbox 360 Wireless Adapter                                       | 1         | 0.76%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                   | 1         | 0.76%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter             | 1         | 0.76%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                      | 1         | 0.76%   |
| Intel Wireless 8260                                                       | 1         | 0.76%   |
| Intel Wireless 7265                                                       | 1         | 0.76%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                           | 1         | 0.76%   |
| Intel Ethernet Connection I219-V                                          | 1         | 0.76%   |
| Intel Ethernet Connection I217-LM                                         | 1         | 0.76%   |
| Intel Ethernet Connection (4) I219-LM                                     | 1         | 0.76%   |
| Intel Ethernet Connection (13) I219-V                                     | 1         | 0.76%   |
| Intel Ethernet Connection (11) I219-V                                     | 1         | 0.76%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                          | 1         | 0.76%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                           | 1         | 0.76%   |
| Intel Comet Lake PCH CNVi WiFi                                            | 1         | 0.76%   |
| Intel Centrino Wireless-N 2230                                            | 1         | 0.76%   |
| Intel Centrino Wireless-N 2200                                            | 1         | 0.76%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                           | 1         | 0.76%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                | 1         | 0.76%   |
| Broadcom BCM43228 802.11a/b/g/n                                           | 1         | 0.76%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller       | 1         | 0.76%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 39        | 62.9%   |
| Realtek Semiconductor | 9         | 14.52%  |
| Qualcomm Atheros      | 4         | 6.45%   |
| Broadcom Limited      | 3         | 4.84%   |
| MediaTek              | 2         | 3.23%   |
| Broadcom              | 2         | 3.23%   |
| TP-Link               | 1         | 1.61%   |
| NetGear               | 1         | 1.61%   |
| Microsoft             | 1         | 1.61%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                       | 5         | 8.06%   |
| Intel Cannon Lake PCH CNVi WiFi                                           | 5         | 8.06%   |
| Intel Wireless 7260                                                       | 4         | 6.45%   |
| Intel Wi-Fi 6 AX201                                                       | 4         | 6.45%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                              | 4         | 6.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 3         | 4.84%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                  | 3         | 4.84%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                           | 2         | 3.23%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                | 2         | 3.23%   |
| Intel Wireless-AC 9260                                                    | 2         | 3.23%   |
| Intel Wireless 8265 / 8275                                                | 2         | 3.23%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                         | 2         | 3.23%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                | 2         | 3.23%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                       | 1         | 1.61%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                        | 1         | 1.61%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                           | 1         | 1.61%   |
| Realtek RTL8723DE Wireless Network Adapter                                | 1         | 1.61%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                           | 1         | 1.61%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                | 1         | 1.61%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                          | 1         | 1.61%   |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1         | 1.61%   |
| Microsoft Xbox 360 Wireless Adapter                                       | 1         | 1.61%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                   | 1         | 1.61%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter             | 1         | 1.61%   |
| Intel Wireless 8260                                                       | 1         | 1.61%   |
| Intel Wireless 7265                                                       | 1         | 1.61%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                           | 1         | 1.61%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                          | 1         | 1.61%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                           | 1         | 1.61%   |
| Intel Comet Lake PCH CNVi WiFi                                            | 1         | 1.61%   |
| Intel Centrino Wireless-N 2230                                            | 1         | 1.61%   |
| Intel Centrino Wireless-N 2200                                            | 1         | 1.61%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                | 1         | 1.61%   |
| Broadcom BCM43228 802.11a/b/g/n                                           | 1         | 1.61%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller       | 1         | 1.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 36        | 54.55%  |
| Intel                    | 21        | 31.82%  |
| ASIX Electronics         | 3         | 4.55%   |
| Qualcomm Atheros         | 2         | 3.03%   |
| Samsung Electronics      | 1         | 1.52%   |
| Qualcomm                 | 1         | 1.52%   |
| Marvell Technology Group | 1         | 1.52%   |
| Broadcom                 | 1         | 1.52%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 30        | 44.78%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 8.96%   |
| Intel I211 Gigabit Network Connection                             | 4         | 5.97%   |
| Intel Ethernet Connection (2) I219-V                              | 4         | 5.97%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 4.48%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 4.48%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 4.48%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 2.99%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 1.49%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 1.49%   |
| Qualcomm Nokia X100                                               | 1         | 1.49%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.49%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 1.49%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 1.49%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.49%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.49%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.49%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.49%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 1.49%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.49%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 62        | 49.6%   |
| WiFi     | 61        | 48.8%   |
| Modem    | 2         | 1.6%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 48        | 60.76%  |
| Ethernet | 31        | 39.24%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 37        | 48.68%  |
| 1     | 35        | 46.05%  |
| 3     | 3         | 3.95%   |
| 0     | 1         | 1.32%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 54        | 70.13%  |
| Yes  | 23        | 29.87%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 32        | 54.24%  |
| Broadcom                        | 7         | 11.86%  |
| Realtek Semiconductor           | 5         | 8.47%   |
| Cambridge Silicon Radio         | 4         | 6.78%   |
| IMC Networks                    | 3         | 5.08%   |
| Qualcomm Atheros Communications | 2         | 3.39%   |
| ASUSTek Computer                | 2         | 3.39%   |
| MediaTek                        | 1         | 1.69%   |
| Lite-On Technology              | 1         | 1.69%   |
| Dell                            | 1         | 1.69%   |
| Apple                           | 1         | 1.69%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 12        | 20.34%  |
| Intel Bluetooth wireless interface                  | 7         | 11.86%  |
| Intel AX200 Bluetooth                               | 5         | 8.47%   |
| Intel AX201 Bluetooth                               | 4         | 6.78%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 6.78%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 5.08%   |
| Realtek Bluetooth Radio                             | 2         | 3.39%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 3.39%   |
| IMC Networks Bluetooth Radio                        | 2         | 3.39%   |
| Broadcom BCM20702A0 Bluetooth                       | 2         | 3.39%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 3.39%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 1.69%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.69%   |
| MediaTek Wireless_Device                            | 1         | 1.69%   |
| Lite-On Bluetooth Device                            | 1         | 1.69%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.69%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.69%   |
| IMC Networks Wireless_Device                        | 1         | 1.69%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 1.69%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 1.69%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 1.69%   |
| Broadcom BCM2045A0                                  | 1         | 1.69%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 1.69%   |
| ASUS Bluetooth Radio                                | 1         | 1.69%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.69%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 62        | 52.99%  |
| Nvidia                 | 23        | 19.66%  |
| AMD                    | 16        | 13.68%  |
| C-Media Electronics    | 3         | 2.56%   |
| Razer USA              | 2         | 1.71%   |
| Kingston Technology    | 2         | 1.71%   |
| Corsair                | 2         | 1.71%   |
| Tenx Technology        | 1         | 0.85%   |
| Samsung Electronics    | 1         | 0.85%   |
| Realtek Semiconductor  | 1         | 0.85%   |
| Plantronics            | 1         | 0.85%   |
| Logitech               | 1         | 0.85%   |
| Hewlett-Packard        | 1         | 0.85%   |
| Generalplus Technology | 1         | 0.85%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 8         | 5.88%   |
| Intel Cannon Lake PCH cAVS                                                 | 8         | 5.88%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6         | 4.41%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 6         | 4.41%   |
| AMD Starship/Matisse HD Audio Controller                                   | 6         | 4.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 3.68%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 5         | 3.68%   |
| Nvidia TU106 High Definition Audio Controller                              | 4         | 2.94%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 2.94%   |
| Intel 200 Series PCH HD Audio                                              | 4         | 2.94%   |
| AMD Family 17h/19h HD Audio Controller                                     | 4         | 2.94%   |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 2.21%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 2.21%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 2.21%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 2.21%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 2.21%   |
| AMD Navi 10 HDMI Audio                                                     | 3         | 2.21%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 1.47%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 1.47%   |
| Nvidia GP104 High Definition Audio Controller                              | 2         | 1.47%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 1.47%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 1.47%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 1.47%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.47%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 1.47%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 1.47%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2         | 1.47%   |
| Tenx Technology USB AUDIO                                                  | 1         | 0.74%   |
| Samsung Electronics USBC Headset                                           | 1         | 0.74%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.74%   |
| Razer USA RZ04-0318 Gaming Headset [Kraken Ultimate]                       | 1         | 0.74%   |
| Razer USA Razer Kraken X USB                                               | 1         | 0.74%   |
| Plantronics C320-M                                                         | 1         | 0.74%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 0.74%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.74%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1         | 0.74%   |
| Nvidia GM206 High Definition Audio Controller                              | 1         | 0.74%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.74%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 0.74%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.74%   |
| Nvidia GF108 High Definition Audio Controller                              | 1         | 0.74%   |
| Nvidia GA102 High Definition Audio Controller                              | 1         | 0.74%   |
| Logitech G633 Gaming Headset                                               | 1         | 0.74%   |
| Kingston Technology HyperX Cloud Flight Wireless                           | 1         | 0.74%   |
| Kingston Technology HyperX 7.1 Audio                                       | 1         | 0.74%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 1         | 0.74%   |
| Intel CM238 HD Audio Controller                                            | 1         | 0.74%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1         | 0.74%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 0.74%   |
| Hewlett-Packard E240C                                                      | 1         | 0.74%   |
| Generalplus Technology USB Audio Device                                    | 1         | 0.74%   |
| Corsair VIRTUOSO SE Wireless Gaming Headset                                | 1         | 0.74%   |
| Corsair HS60 PRO Surround USB Sound Adapter                                | 1         | 0.74%   |
| C-Media Electronics Schiit Modi Uber                                       | 1         | 0.74%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 1         | 0.74%   |
| C-Media Electronics Blue Snowball                                          | 1         | 0.74%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 1         | 0.74%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 1         | 0.74%   |
| AMD Tonga HDMI Audio [Radeon R9 285/380]                                   | 1         | 0.74%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 1         | 0.74%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 20        | 25.64%  |
| Samsung Electronics | 17        | 21.79%  |
| Corsair             | 8         | 10.26%  |
| Micron Technology   | 7         | 8.97%   |
| G.Skill             | 6         | 7.69%   |
| Crucial             | 6         | 7.69%   |
| Kingston            | 5         | 6.41%   |
| Unknown             | 4         | 5.13%   |
| Ramaxel Technology  | 2         | 2.56%   |
| Unifosa             | 1         | 1.28%   |
| Team                | 1         | 1.28%   |
| PNY                 | 1         | 1.28%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 3.66%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s         | 3         | 3.66%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 2         | 2.44%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 2         | 2.44%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                        | 1         | 1.22%   |
| Unknown RAM Module 4GB DIMM DDR4 2133MT/s                        | 1         | 1.22%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                         | 1         | 1.22%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 1         | 1.22%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s                | 1         | 1.22%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3067MT/s               | 1         | 1.22%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3                      | 1         | 1.22%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.22%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.22%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.22%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s             | 1         | 1.22%   |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1450MT/s             | 1         | 1.22%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.22%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.22%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8192MB Row Of Chips DDR4 3200MT/s  | 1         | 1.22%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 1.22%   |
| SK hynix RAM HMA851S6JJR6N-VK 4096MB SODIMM DDR4 2667MT/s        | 1         | 1.22%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 1.22%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 1.22%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 1.22%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 1         | 1.22%   |
| SK hynix RAM HMA81GS6DJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.22%   |
| SK hynix RAM HCNNNFAMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s   | 1         | 1.22%   |
| SK hynix RAM H9CCNNNBJTALAR-NVD 4GB Row Of Chips LPDDR3 2133MT/s | 1         | 1.22%   |
| Samsung RAM Module 8GB DIMM DDR4 2666MT/s                        | 1         | 1.22%   |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s                        | 1         | 1.22%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 1.22%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.22%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.22%   |
| Samsung RAM M471B1G73CB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 1         | 1.22%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 1         | 1.22%   |
| Samsung RAM M471A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s           | 1         | 1.22%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.22%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.22%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.22%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.22%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.22%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.22%   |
| Ramaxel RAM RMT3020EC58E9F1333 4096MB SODIMM DDR3 4199MT/s       | 1         | 1.22%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 1         | 1.22%   |
| PNY RAM 8GBF1X08QFHH36-135-K 8GB DIMM DDR4 2400MT/s              | 1         | 1.22%   |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                       | 1         | 1.22%   |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s      | 1         | 1.22%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s      | 1         | 1.22%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB Row Of Chips DDR4 2667MT/s      | 1         | 1.22%   |
| Micron RAM 4ATF51264HZ-2G3E1 4GB SODIMM DDR4 2667MT/s            | 1         | 1.22%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 1         | 1.22%   |
| Micron RAM 16KTF1G64AZ-1G6E1 8GB DIMM DDR3 1600MT/s              | 1         | 1.22%   |
| Kingston RAM KHYXPX-MID 8GB SODIMM DDR4 2667MT/s                 | 1         | 1.22%   |
| Kingston RAM KHX2133C14/16G 16GB DIMM DDR4 2176MT/s              | 1         | 1.22%   |
| Kingston RAM HP16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s            | 1         | 1.22%   |
| Kingston RAM CBD32D4S2S8MR-8 8GB SODIMM DDR4 3200MT/s            | 1         | 1.22%   |
| Kingston RAM 99U5428-069.A00LF 8192MB SODIMM DDR3 1600MT/s       | 1         | 1.22%   |
| G.Skill RAM F4-3600C17-8GTZR 8GB DIMM DDR4 3600MT/s              | 1         | 1.22%   |
| G.Skill RAM F4-3600C16-8GTZNC 8GB DIMM DDR4 3800MT/s             | 1         | 1.22%   |
| G.Skill RAM F4-3600C16-16GTZRC 16GB DIMM DDR4 4400MT/s           | 1         | 1.22%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 42        | 65.63%  |
| DDR3   | 15        | 23.44%  |
| LPDDR4 | 2         | 3.13%   |
| DDR    | 2         | 3.13%   |
| SDRAM  | 1         | 1.56%   |
| LPDDR3 | 1         | 1.56%   |
| DDR2   | 1         | 1.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 36        | 55.38%  |
| DIMM         | 23        | 35.38%  |
| Row Of Chips | 6         | 9.23%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 34        | 48.57%  |
| 4096  | 25        | 35.71%  |
| 16384 | 9         | 12.86%  |
| 2048  | 2         | 2.86%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 2667  | 17        | 23.61%  |
| 1600  | 13        | 18.06%  |
| 3200  | 11        | 15.28%  |
| 2400  | 4         | 5.56%   |
| 3600  | 3         | 4.17%   |
| 3266  | 3         | 4.17%   |
| 4267  | 2         | 2.78%   |
| 2933  | 2         | 2.78%   |
| 2133  | 2         | 2.78%   |
| 1333  | 2         | 2.78%   |
| 800   | 2         | 2.78%   |
| 4400  | 1         | 1.39%   |
| 4199  | 1         | 1.39%   |
| 4133  | 1         | 1.39%   |
| 3800  | 1         | 1.39%   |
| 3400  | 1         | 1.39%   |
| 3067  | 1         | 1.39%   |
| 2747  | 1         | 1.39%   |
| 2666  | 1         | 1.39%   |
| 2176  | 1         | 1.39%   |
| 1800  | 1         | 1.39%   |
| 1450  | 1         | 1.39%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| IMC Networks                           | 10        | 20.83%  |
| Realtek Semiconductor                  | 7         | 14.58%  |
| Chicony Electronics                    | 7         | 14.58%  |
| Acer                                   | 6         | 12.5%   |
| Syntek                                 | 3         | 6.25%   |
| Quanta                                 | 3         | 6.25%   |
| Sunplus Innovation Technology          | 2         | 4.17%   |
| Microdia                               | 2         | 4.17%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 4.17%   |
| Suyin                                  | 1         | 2.08%   |
| Ricoh                                  | 1         | 2.08%   |
| Logitech                               | 1         | 2.08%   |
| Lite-On Technology                     | 1         | 2.08%   |
| Generalplus Technology                 | 1         | 2.08%   |
| Alpha Imaging Technology               | 1         | 2.08%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                                         | 4         | 8.33%   |
| Syntek Integrated Camera                                             | 3         | 6.25%   |
| IMC Networks USB2.0 HD UVC WebCam                                    | 3         | 6.25%   |
| Quanta HP TrueVision HD Camera                                       | 2         | 4.17%   |
| IMC Networks USB2.0 VGA UVC WebCam                                   | 2         | 4.17%   |
| IMC Networks Integrated Camera                                       | 2         | 4.17%   |
| Chicony Integrated Camera                                            | 2         | 4.17%   |
| Chicony EasyCamera                                                   | 2         | 4.17%   |
| Acer ThinkPad Integrated Camera                                      | 2         | 4.17%   |
| Suyin Asus Integrated Webcam                                         | 1         | 2.08%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                 | 1         | 2.08%   |
| Sunplus HP Truevision HD                                             | 1         | 2.08%   |
| Ricoh Integrated Webcam                                              | 1         | 2.08%   |
| Realtek Integrated Webcam_HD                                         | 1         | 2.08%   |
| Realtek Integrated Webcam                                            | 1         | 2.08%   |
| Realtek Built-In Video Camera                                        | 1         | 2.08%   |
| Quanta HD User Facing                                                | 1         | 2.08%   |
| Microdia Integrated_Webcam_HD                                        | 1         | 2.08%   |
| Microdia Dell Integrated HD Webcam                                   | 1         | 2.08%   |
| Logitech Webcam C600                                                 | 1         | 2.08%   |
| Lite-On Integrated Camera                                            | 1         | 2.08%   |
| IMC Networks VGA UVC WebCam                                          | 1         | 2.08%   |
| IMC Networks USB2.0 UVC HD Webcam                                    | 1         | 2.08%   |
| IMC Networks EasyCamera                                              | 1         | 2.08%   |
| Generalplus GENERAL WEBCAM                                           | 1         | 2.08%   |
| Chicony HP Webcam                                                    | 1         | 2.08%   |
| Chicony HP High Definition 1MP Webcam                                | 1         | 2.08%   |
| Chicony HD User Facing                                               | 1         | 2.08%   |
| Cheng Uei Precision Industry (Foxlink) HP High Definition 1MP Webcam | 1         | 2.08%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera                     | 1         | 2.08%   |
| Alpha Imaging Integrated_Webcam_8M                                   | 1         | 2.08%   |
| Acer SunplusIT Integrated Camera                                     | 1         | 2.08%   |
| Acer Integrated Camera                                               | 1         | 2.08%   |
| Acer HD Webcam                                                       | 1         | 2.08%   |
| Acer BisonCam, NB Pro                                                | 1         | 2.08%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 2         | 50%     |
| Validity Sensors           | 1         | 25%     |
| Elan Microelectronics      | 1         | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI     | 1         | 25%     |
| Shenzhen Goodix  FingerPrint Device | 1         | 25%     |
| Shenzhen Goodix Fingerprint Reader  | 1         | 25%     |
| Elan ELAN:Fingerprint               | 1         | 25%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Upek     | 2         | 50%     |
| Broadcom | 2         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 2         | 50%     |
| Broadcom BCM5880 Secure Applications Processor             | 2         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 58        | 75.32%  |
| 1     | 16        | 20.78%  |
| 2     | 3         | 3.9%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 5         | 22.73%  |
| Fingerprint reader    | 4         | 18.18%  |
| Chipcard              | 4         | 18.18%  |
| Net/wireless          | 2         | 9.09%   |
| Camera                | 2         | 9.09%   |
| Bluetooth             | 2         | 9.09%   |
| Storage               | 1         | 4.55%   |
| Network               | 1         | 4.55%   |
| Multimedia controller | 1         | 4.55%   |

