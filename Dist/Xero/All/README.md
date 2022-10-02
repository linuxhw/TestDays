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

Total: 101

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [9931b35717](https://linux-hardware.org/?probe=9931b35717) | Sep 24, 2022 |
| MSI           | Katana GF66 11UE            | Notebook    | [36b2cba297](https://linux-hardware.org/?probe=36b2cba297) | Sep 05, 2022 |
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

![OS](./images/pie_chart/os_name.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Xero Rolling | 66        | 83.54%  |
| Xero         | 13        | 16.46%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| Xero | 78        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Computers | Percent |
|-------------------------|-----------|---------|
| 5.16.15-arch1-1         | 6         | 6.98%   |
| 5.18.16-arch1-1         | 4         | 4.65%   |
| 5.17.9-arch1-1          | 3         | 3.49%   |
| 5.16.2-arch1-1          | 3         | 3.49%   |
| 5.16.1-arch1-1          | 3         | 3.49%   |
| 5.15.33-1-lts           | 3         | 3.49%   |
| 5.14.14-arch1-1         | 3         | 3.49%   |
| 5.18.3-arch1-1          | 2         | 2.33%   |
| 5.18.11-arch1-1         | 2         | 2.33%   |
| 5.17.5-arch1-1          | 2         | 2.33%   |
| 5.17.1-arch1-1          | 2         | 2.33%   |
| 5.16.8-arch1-1          | 2         | 2.33%   |
| 5.16.16-arch1-1         | 2         | 2.33%   |
| 5.16.13-arch1-1         | 2         | 2.33%   |
| 5.16.12-arch1-1         | 2         | 2.33%   |
| 5.15.10-arch1-1         | 2         | 2.33%   |
| 5.14.8-zen1-1-zen       | 2         | 2.33%   |
| 5.19.3-arch1-1          | 1         | 1.16%   |
| 5.19.2-zen1-1-zen       | 1         | 1.16%   |
| 5.19.10-arch1-1         | 1         | 1.16%   |
| 5.19.1-arch2-1          | 1         | 1.16%   |
| 5.18.9-arch1-1          | 1         | 1.16%   |
| 5.18.6-arch1-1          | 1         | 1.16%   |
| 5.18.0-arch1-1          | 1         | 1.16%   |
| 5.17.7-arch1-1          | 1         | 1.16%   |
| 5.16.16-zen1-1-zen      | 1         | 1.16%   |
| 5.16.14-arch1-1         | 1         | 1.16%   |
| 5.16.10-arch1-1         | 1         | 1.16%   |
| 5.15.8-zen1-1-zen       | 1         | 1.16%   |
| 5.15.6-arch2-1          | 1         | 1.16%   |
| 5.15.4-arch1-1          | 1         | 1.16%   |
| 5.15.35-1-lts           | 1         | 1.16%   |
| 5.15.3-zen1-1-zen       | 1         | 1.16%   |
| 5.15.26-1-lts           | 1         | 1.16%   |
| 5.15.24-1-lts           | 1         | 1.16%   |
| 5.15.13-arch1-1         | 1         | 1.16%   |
| 5.15.13-AMD             | 1         | 1.16%   |
| 5.15.12-zen1-1-zen      | 1         | 1.16%   |
| 5.15.12-arch1-1-surface | 1         | 1.16%   |
| 5.15.12-arch1-1         | 1         | 1.16%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.16.15 | 6         | 6.98%   |
| 5.18.16 | 4         | 4.65%   |
| 5.14.14 | 4         | 4.65%   |
| 5.17.9  | 3         | 3.49%   |
| 5.16.2  | 3         | 3.49%   |
| 5.16.16 | 3         | 3.49%   |
| 5.16.1  | 3         | 3.49%   |
| 5.15.33 | 3         | 3.49%   |
| 5.15.12 | 3         | 3.49%   |
| 5.14.8  | 3         | 3.49%   |
| 5.14.16 | 3         | 3.49%   |
| 5.18.3  | 2         | 2.33%   |
| 5.18.11 | 2         | 2.33%   |
| 5.17.5  | 2         | 2.33%   |
| 5.17.1  | 2         | 2.33%   |
| 5.16.8  | 2         | 2.33%   |
| 5.16.13 | 2         | 2.33%   |
| 5.16.12 | 2         | 2.33%   |
| 5.15.13 | 2         | 2.33%   |
| 5.15.11 | 2         | 2.33%   |
| 5.15.10 | 2         | 2.33%   |
| 5.19.3  | 1         | 1.16%   |
| 5.19.2  | 1         | 1.16%   |
| 5.19.10 | 1         | 1.16%   |
| 5.19.1  | 1         | 1.16%   |
| 5.18.9  | 1         | 1.16%   |
| 5.18.6  | 1         | 1.16%   |
| 5.18.0  | 1         | 1.16%   |
| 5.17.7  | 1         | 1.16%   |
| 5.16.14 | 1         | 1.16%   |
| 5.16.10 | 1         | 1.16%   |
| 5.15.8  | 1         | 1.16%   |
| 5.15.6  | 1         | 1.16%   |
| 5.15.4  | 1         | 1.16%   |
| 5.15.35 | 1         | 1.16%   |
| 5.15.3  | 1         | 1.16%   |
| 5.15.26 | 1         | 1.16%   |
| 5.15.24 | 1         | 1.16%   |
| 5.14.9  | 1         | 1.16%   |
| 5.14.15 | 1         | 1.16%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.16    | 23        | 27.38%  |
| 5.15    | 18        | 21.43%  |
| 5.14    | 13        | 15.48%  |
| 5.18    | 11        | 13.1%   |
| 5.17    | 8         | 9.52%   |
| 5.19    | 4         | 4.76%   |
| 5.10    | 3         | 3.57%   |
| 5.13    | 2         | 2.38%   |
| 5.12    | 1         | 1.19%   |
| 5.11    | 1         | 1.19%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 78        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| KDE5  | 74        | 92.5%   |
| XFCE  | 4         | 5%      |
| GNOME | 2         | 2.5%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 65        | 83.33%  |
| Wayland | 11        | 14.1%   |
| Tty     | 2         | 2.56%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 52        | 63.41%  |
| LightDM | 15        | 18.29%  |
| Unknown | 13        | 15.85%  |
| TDM     | 1         | 1.22%   |
| GDM     | 1         | 1.22%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 44        | 55.7%   |
| en_IN | 6         | 7.59%   |
| en_GB | 5         | 6.33%   |
| C     | 5         | 6.33%   |
| pl_PL | 4         | 5.06%   |
| de_DE | 3         | 3.8%    |
| it_IT | 2         | 2.53%   |
| en_AU | 2         | 2.53%   |
| ru_RU | 1         | 1.27%   |
| fr_FR | 1         | 1.27%   |
| en_IL | 1         | 1.27%   |
| en_DK | 1         | 1.27%   |
| en_CA | 1         | 1.27%   |
| en_AG | 1         | 1.27%   |
| de_AT | 1         | 1.27%   |
| ba_RU | 1         | 1.27%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 54        | 68.35%  |
| BIOS | 25        | 31.65%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 53        | 66.25%  |
| Ext4    | 13        | 16.25%  |
| Xfs     | 8         | 10%     |
| Overlay | 6         | 7.5%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 56        | 70.89%  |
| Unknown | 13        | 16.46%  |
| MBR     | 10        | 12.66%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 61        | 74.39%  |
| Yes       | 21        | 25.61%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 50        | 64.1%   |
| Yes       | 28        | 35.9%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 21        | 26.92%  |
| Lenovo              | 15        | 19.23%  |
| Dell                | 11        | 14.1%   |
| Hewlett-Packard     | 8         | 10.26%  |
| MSI                 | 6         | 7.69%   |
| Acer                | 4         | 5.13%   |
| Gigabyte Technology | 3         | 3.85%   |
| ASRock              | 3         | 3.85%   |
| Pegatron            | 2         | 2.56%   |
| HUAWEI              | 1         | 1.28%   |
| BESSTAR Tech        | 1         | 1.28%   |
| Aquarius            | 1         | 1.28%   |
| Apple               | 1         | 1.28%   |
| Unknown             | 1         | 1.28%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Dell Precision M3800                       | 3         | 3.85%   |
| MSI MS-7971                                | 2         | 2.56%   |
| ASUS TUF Gaming X570-PLUS                  | 2         | 2.56%   |
| Pegatron p6-2026                           | 1         | 1.28%   |
| Pegatron D15K                              | 1         | 1.28%   |
| MSI MS-7B61                                | 1         | 1.28%   |
| MSI Katana GF66 11UE                       | 1         | 1.28%   |
| MSI GP73 Leopard 8RD                       | 1         | 1.28%   |
| MSI GF63 Thin 9SCX                         | 1         | 1.28%   |
| Lenovo Yoga 710-15IKB 80V5                 | 1         | 1.28%   |
| Lenovo Y520-15IKBN 80WK                    | 1         | 1.28%   |
| Lenovo ThinkPad X230 2325HR9               | 1         | 1.28%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XW0055MH | 1         | 1.28%   |
| Lenovo ThinkPad W530 24384CU               | 1         | 1.28%   |
| Lenovo ThinkPad T460 20FMS1XX00            | 1         | 1.28%   |
| Lenovo ThinkPad T430s 2356FG9              | 1         | 1.28%   |
| Lenovo Legion Y740-15IRHg 81UH             | 1         | 1.28%   |
| Lenovo Legion Y540-15IRH-PG0 81SY          | 1         | 1.28%   |
| Lenovo Legion 5 15ARH05H 82B1              | 1         | 1.28%   |
| Lenovo IdeaPad S145-15IIL 81W8             | 1         | 1.28%   |
| Lenovo IdeaPad S145-15AST 81N3             | 1         | 1.28%   |
| Lenovo IdeaPad 5 15ITL05 82FG              | 1         | 1.28%   |
| Lenovo IdeaPad 330-17IKB 81DM              | 1         | 1.28%   |
| Lenovo IdeaPad 3 15IML05 81WR              | 1         | 1.28%   |
| HUAWEI WRT-WX9                             | 1         | 1.28%   |
| HP Z230 SFF Workstation                    | 1         | 1.28%   |
| HP ProOne 400 G1 AiO                       | 1         | 1.28%   |
| HP Pavilion Desktop 590-p0xxx              | 1         | 1.28%   |
| HP Notebook                                | 1         | 1.28%   |
| HP Laptop 15s-eq0xxx                       | 1         | 1.28%   |
| HP Laptop 15-da0xxx                        | 1         | 1.28%   |
| HP ENVY Sleekbook 4                        | 1         | 1.28%   |
| HP Compaq Elite 8300 CMT                   | 1         | 1.28%   |
| Gigabyte Z170X-UD3                         | 1         | 1.28%   |
| Gigabyte X570 AORUS MASTER                 | 1         | 1.28%   |
| Gigabyte B460MDS3HV2                       | 1         | 1.28%   |
| Dell Vostro 3590                           | 1         | 1.28%   |
| Dell Venue 11 Pro 7130 vPro                | 1         | 1.28%   |
| Dell Precision T1500                       | 1         | 1.28%   |
| Dell Latitude E6520                        | 1         | 1.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 5         | 6.41%   |
| Lenovo IdeaPad       | 5         | 6.41%   |
| ASUS TUF             | 5         | 6.41%   |
| Dell Precision       | 4         | 5.13%   |
| ASUS ROG             | 4         | 5.13%   |
| Acer Aspire          | 4         | 5.13%   |
| Lenovo Legion        | 3         | 3.85%   |
| Dell Latitude        | 3         | 3.85%   |
| ASUS VivoBook        | 3         | 3.85%   |
| MSI MS-7971          | 2         | 2.56%   |
| HP Laptop            | 2         | 2.56%   |
| Dell Inspiron        | 2         | 2.56%   |
| ASUS ASUS            | 2         | 2.56%   |
| Pegatron p6-2026     | 1         | 1.28%   |
| Pegatron D15K        | 1         | 1.28%   |
| MSI MS-7B61          | 1         | 1.28%   |
| MSI Katana           | 1         | 1.28%   |
| MSI GP73             | 1         | 1.28%   |
| MSI GF63             | 1         | 1.28%   |
| Lenovo Yoga          | 1         | 1.28%   |
| Lenovo Y520-15IKBN   | 1         | 1.28%   |
| HUAWEI WRT-WX9       | 1         | 1.28%   |
| HP Z230              | 1         | 1.28%   |
| HP ProOne            | 1         | 1.28%   |
| HP Pavilion          | 1         | 1.28%   |
| HP Notebook          | 1         | 1.28%   |
| HP ENVY              | 1         | 1.28%   |
| HP Compaq            | 1         | 1.28%   |
| Gigabyte Z170X-UD3   | 1         | 1.28%   |
| Gigabyte X570        | 1         | 1.28%   |
| Gigabyte B460MDS3HV2 | 1         | 1.28%   |
| Dell Vostro          | 1         | 1.28%   |
| Dell Venue           | 1         | 1.28%   |
| BESSTAR Tech X500    | 1         | 1.28%   |
| ASUS X510UNR         | 1         | 1.28%   |
| ASUS UX303LN         | 1         | 1.28%   |
| ASUS PRIME           | 1         | 1.28%   |
| ASUS P7P55           | 1         | 1.28%   |
| ASUS P5Q             | 1         | 1.28%   |
| ASUS Maximus         | 1         | 1.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 16        | 20.51%  |
| 2020 | 11        | 14.1%   |
| 2018 | 9         | 11.54%  |
| 2017 | 8         | 10.26%  |
| 2021 | 6         | 7.69%   |
| 2012 | 6         | 7.69%   |
| 2013 | 5         | 6.41%   |
| 2015 | 4         | 5.13%   |
| 2014 | 3         | 3.85%   |
| 2016 | 2         | 2.56%   |
| 2011 | 2         | 2.56%   |
| 2010 | 2         | 2.56%   |
| 2009 | 2         | 2.56%   |
| 2022 | 1         | 1.28%   |
| 2008 | 1         | 1.28%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 44        | 56.41%  |
| Desktop     | 31        | 39.74%  |
| Convertible | 2         | 2.56%   |
| Server      | 1         | 1.28%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 78        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 78        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 22        | 28.21%  |
| 16.01-24.0  | 21        | 26.92%  |
| 8.01-16.0   | 16        | 20.51%  |
| 32.01-64.0  | 9         | 11.54%  |
| 3.01-4.0    | 6         | 7.69%   |
| 24.01-32.0  | 3         | 3.85%   |
| 64.01-256.0 | 1         | 1.28%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 29        | 33.72%  |
| 1.01-2.0   | 20        | 23.26%  |
| 4.01-8.0   | 15        | 17.44%  |
| 3.01-4.0   | 11        | 12.79%  |
| 8.01-16.0  | 4         | 4.65%   |
| 16.01-24.0 | 3         | 3.49%   |
| 0.51-1.0   | 2         | 2.33%   |
| 0.01-0.5   | 2         | 2.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 41        | 52.56%  |
| 2      | 20        | 25.64%  |
| 3      | 8         | 10.26%  |
| 4      | 5         | 6.41%   |
| 6      | 2         | 2.56%   |
| 7      | 1         | 1.28%   |
| 5      | 1         | 1.28%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 61        | 78.21%  |
| Yes       | 17        | 21.79%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 64        | 82.05%  |
| No        | 14        | 17.95%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 63        | 80.77%  |
| No        | 15        | 19.23%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 61        | 77.22%  |
| No        | 18        | 22.78%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country               | Computers | Percent |
|-----------------------|-----------|---------|
| USA                   | 19        | 24.36%  |
| India                 | 8         | 10.26%  |
| Poland                | 5         | 6.41%   |
| Germany               | 5         | 6.41%   |
| Italy                 | 3         | 3.85%   |
| Greece                | 3         | 3.85%   |
| France                | 3         | 3.85%   |
| UK                    | 2         | 2.56%   |
| Russia                | 2         | 2.56%   |
| Norway                | 2         | 2.56%   |
| Netherlands           | 2         | 2.56%   |
| Canada                | 2         | 2.56%   |
| Australia             | 2         | 2.56%   |
| Zambia                | 1         | 1.28%   |
| Turkey                | 1         | 1.28%   |
| Togo                  | 1         | 1.28%   |
| Sweden                | 1         | 1.28%   |
| Spain                 | 1         | 1.28%   |
| Portugal              | 1         | 1.28%   |
| Palestinian Territory | 1         | 1.28%   |
| Pakistan              | 1         | 1.28%   |
| Morocco               | 1         | 1.28%   |
| Mongolia              | 1         | 1.28%   |
| Mexico                | 1         | 1.28%   |
| Malaysia              | 1         | 1.28%   |
| Lebanon               | 1         | 1.28%   |
| Israel                | 1         | 1.28%   |
| Hungary               | 1         | 1.28%   |
| Denmark               | 1         | 1.28%   |
| Colombia              | 1         | 1.28%   |
| Brazil                | 1         | 1.28%   |
| Austria               | 1         | 1.28%   |
| Argentina             | 1         | 1.28%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Longmont       | 3         | 3.85%   |
| Madurai        | 2         | 2.56%   |
| Zell am See    | 1         | 1.28%   |
| Wroclaw        | 1         | 1.28%   |
| Wrexham        | 1         | 1.28%   |
| Wells          | 1         | 1.28%   |
| Warsaw         | 1         | 1.28%   |
| Ulan Bator     | 1         | 1.28%   |
| Toronto        | 1         | 1.28%   |
| Tel Aviv       | 1         | 1.28%   |
| Taranto        | 1         | 1.28%   |
| Stuttgart      | 1         | 1.28%   |
| Stavropol      | 1         | 1.28%   |
| Springfield    | 1         | 1.28%   |
| Silkeborg      | 1         | 1.28%   |
| Shadrinsk      | 1         | 1.28%   |
| Salt Lake City | 1         | 1.28%   |
| Ramallah       | 1         | 1.28%   |
| Pune           | 1         | 1.28%   |
| Poznan         | 1         | 1.28%   |
| Portland       | 1         | 1.28%   |
| Pirmasens      | 1         | 1.28%   |
| Phoenix        | 1         | 1.28%   |
| Pavia          | 1         | 1.28%   |
| Passos         | 1         | 1.28%   |
| Paris          | 1         | 1.28%   |
| Oslo           | 1         | 1.28%   |
| Oberursel      | 1         | 1.28%   |
| New Haven      | 1         | 1.28%   |
| Neu-Ulm        | 1         | 1.28%   |
| Mumbai         | 1         | 1.28%   |
| Monterrey      | 1         | 1.28%   |
| Melbourne      | 1         | 1.28%   |
| Lusaka         | 1         | 1.28%   |
| Lucknow        | 1         | 1.28%   |
| Lublin         | 1         | 1.28%   |
| Longview       | 1         | 1.28%   |
| Longvic        | 1         | 1.28%   |
| Lomé          | 1         | 1.28%   |
| Lisbon         | 1         | 1.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 24        | 37     | 18.05%  |
| Samsung Electronics       | 24        | 35     | 18.05%  |
| WDC                       | 21        | 27     | 15.79%  |
| Kingston                  | 9         | 12     | 6.77%   |
| Toshiba                   | 8         | 10     | 6.02%   |
| HGST                      | 6         | 6      | 4.51%   |
| SanDisk                   | 4         | 5      | 3.01%   |
| Intel                     | 4         | 6      | 3.01%   |
| Unknown                   | 3         | 4      | 2.26%   |
| Phison                    | 3         | 3      | 2.26%   |
| Micron Technology         | 3         | 5      | 2.26%   |
| LITEON                    | 2         | 2      | 1.5%    |
| Crucial                   | 2         | 2      | 1.5%    |
| China                     | 2         | 2      | 1.5%    |
| XPG                       | 1         | 1      | 0.75%   |
| Transcend                 | 1         | 1      | 0.75%   |
| SK hynix                  | 1         | 1      | 0.75%   |
| Silicon Motion            | 1         | 1      | 0.75%   |
| Realtek Semiconductor     | 1         | 1      | 0.75%   |
| PNY                       | 1         | 1      | 0.75%   |
| Plextor                   | 1         | 1      | 0.75%   |
| Micron/Crucial Technology | 1         | 1      | 0.75%   |
| LITEONIT                  | 1         | 1      | 0.75%   |
| KIOXIA                    | 1         | 1      | 0.75%   |
| Intenso                   | 1         | 1      | 0.75%   |
| Inateck                   | 1         | 1      | 0.75%   |
| Hitachi                   | 1         | 1      | 0.75%   |
| GOODRAM                   | 1         | 1      | 0.75%   |
| Apple                     | 1         | 1      | 0.75%   |
| Apacer                    | 1         | 1      | 0.75%   |
| A-DATA Technology         | 1         | 1      | 0.75%   |
| 2-Power                   | 1         | 1      | 0.75%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 3         | 1.95%   |
| Seagate One Touch HDD 5TB            | 3         | 1.95%   |
| Kingston SA400S37240G 240GB SSD      | 3         | 1.95%   |
| Toshiba MQ04ABF100 1TB               | 2         | 1.3%    |
| Seagate ST1000LM049-2GH172 1TB       | 2         | 1.3%    |
| Seagate ST1000LM048-2E7172 1TB       | 2         | 1.3%    |
| Seagate ST1000DM010-2EP102 1TB       | 2         | 1.3%    |
| SanDisk NVMe SSD Drive 500GB         | 2         | 1.3%    |
| Samsung SSD 970 EVO 1TB              | 2         | 1.3%    |
| Samsung SSD 860 EVO 250GB            | 2         | 1.3%    |
| Samsung SSD 860 EVO 1TB              | 2         | 1.3%    |
| Samsung SSD 850 EVO 250GB            | 2         | 1.3%    |
| HGST HTS545050A7E680 500GB           | 2         | 1.3%    |
| XPG GAMMIX S50 1TB                   | 1         | 0.65%   |
| WDC WDS512G1X0C-00ENX0 512GB         | 1         | 0.65%   |
| WDC WDS500G3XHC-00SJG0 500GB         | 1         | 0.65%   |
| WDC WDS500G3X0C-00SJG0 500GB         | 1         | 0.65%   |
| WDC WDS500G2B0B-00YS70 500GB SSD     | 1         | 0.65%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 1         | 0.65%   |
| WDC WDS100T1X0E-00AFY0 1TB           | 1         | 0.65%   |
| WDC WDBNCE0010PNC 1TB SSD            | 1         | 0.65%   |
| WDC WD800JD-00MSA1 80GB              | 1         | 0.65%   |
| WDC WD7500BPKT-75PK4T0 752GB         | 1         | 0.65%   |
| WDC WD6400AAKS-22A7B2 640GB          | 1         | 0.65%   |
| WDC WD5000AAVS-00ZTB0 500GB          | 1         | 0.65%   |
| WDC WD5000AAKX-60U6AA0 500GB         | 1         | 0.65%   |
| WDC WD40EZRZ-22GXCB0 4TB             | 1         | 0.65%   |
| WDC WD2500BEVT-60ZCT1 250GB          | 1         | 0.65%   |
| WDC WD20EZRZ-60Z5HB0 2TB             | 1         | 0.65%   |
| WDC WD20EZBX-00AYRA0 2TB             | 1         | 0.65%   |
| WDC WD2003FZEX-00SRLA0 2TB           | 1         | 0.65%   |
| WDC WD10EZEX-60WN4A0 1TB             | 1         | 0.65%   |
| WDC WD10EZEX-22MFCA0 1TB             | 1         | 0.65%   |
| WDC WD10EZEX-00KUWA0 1TB             | 1         | 0.65%   |
| WDC WD1002FAEX-00Z3A0 1TB            | 1         | 0.65%   |
| WDC PC SN720 SDAPNTW-512G-1027 512GB | 1         | 0.65%   |
| WDC PC SN530 SDBPNPZ-256G-1114 256GB | 1         | 0.65%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB | 1         | 0.65%   |
| WDC PC SN520 SDAPMUW-256G-1101 256GB | 1         | 0.65%   |
| Unknown MMC Card  64GB               | 1         | 0.65%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 24        | 36     | 47.06%  |
| WDC                 | 12        | 15     | 23.53%  |
| Toshiba             | 6         | 8      | 11.76%  |
| HGST                | 6         | 6      | 11.76%  |
| Samsung Electronics | 2         | 2      | 3.92%   |
| Hitachi             | 1         | 1      | 1.96%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 15     | 31.58%  |
| Kingston            | 5         | 7      | 13.16%  |
| WDC                 | 3         | 3      | 7.89%   |
| LITEON              | 2         | 2      | 5.26%   |
| Crucial             | 2         | 2      | 5.26%   |
| China               | 2         | 2      | 5.26%   |
| Transcend           | 1         | 1      | 2.63%   |
| SanDisk             | 1         | 1      | 2.63%   |
| PNY                 | 1         | 1      | 2.63%   |
| Plextor             | 1         | 1      | 2.63%   |
| Micron Technology   | 1         | 1      | 2.63%   |
| LITEONIT            | 1         | 1      | 2.63%   |
| Intenso             | 1         | 1      | 2.63%   |
| Intel               | 1         | 1      | 2.63%   |
| GOODRAM             | 1         | 1      | 2.63%   |
| Apple               | 1         | 1      | 2.63%   |
| Apacer              | 1         | 1      | 2.63%   |
| 2-Power             | 1         | 1      | 2.63%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 43        | 68     | 36.44%  |
| NVMe | 39        | 59     | 33.05%  |
| SSD  | 33        | 43     | 27.97%  |
| MMC  | 3         | 4      | 2.54%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 57        | 103    | 53.27%  |
| NVMe | 39        | 58     | 36.45%  |
| SAS  | 8         | 9      | 7.48%   |
| MMC  | 3         | 4      | 2.8%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 36        | 52     | 43.9%   |
| 0.51-1.0   | 30        | 38     | 36.59%  |
| 1.01-2.0   | 8         | 12     | 9.76%   |
| 4.01-10.0  | 6         | 7      | 7.32%   |
| 3.01-4.0   | 1         | 1      | 1.22%   |
| 2.01-3.0   | 1         | 1      | 1.22%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| More than 3000 | 24        | 28.92%  |
| 1001-2000      | 19        | 22.89%  |
| 501-1000       | 11        | 13.25%  |
| 251-500        | 7         | 8.43%   |
| 101-250        | 6         | 7.23%   |
| 1-20           | 4         | 4.82%   |
| 51-100         | 4         | 4.82%   |
| Unknown        | 4         | 4.82%   |
| 21-50          | 2         | 2.41%   |
| 2001-3000      | 2         | 2.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 24        | 28.92%  |
| 51-100         | 16        | 19.28%  |
| 1-20           | 13        | 15.66%  |
| 251-500        | 7         | 8.43%   |
| 501-1000       | 7         | 8.43%   |
| 21-50          | 4         | 4.82%   |
| 2001-3000      | 4         | 4.82%   |
| Unknown        | 4         | 4.82%   |
| More than 3000 | 2         | 2.41%   |
| 1001-2000      | 2         | 2.41%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


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

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


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

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


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

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


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

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 61        | 117    | 64.89%  |
| Detected | 18        | 40     | 19.15%  |
| Malfunc  | 15        | 17     | 15.96%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 60        | 51.72%  |
| AMD                          | 13        | 11.21%  |
| Samsung Electronics          | 12        | 10.34%  |
| SanDisk                      | 10        | 8.62%   |
| Kingston Technology Company  | 4         | 3.45%   |
| Phison Electronics           | 3         | 2.59%   |
| Micron Technology            | 3         | 2.59%   |
| Toshiba America Info Systems | 2         | 1.72%   |
| Realtek Semiconductor        | 2         | 1.72%   |
| SK hynix                     | 1         | 0.86%   |
| Silicon Motion               | 1         | 0.86%   |
| Seagate Technology           | 1         | 0.86%   |
| Micron/Crucial Technology    | 1         | 0.86%   |
| KIOXIA                       | 1         | 0.86%   |
| ASMedia Technology           | 1         | 0.86%   |
| ADATA Technology             | 1         | 0.86%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 12        | 9.52%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 6         | 4.76%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5         | 3.97%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 3.97%   |
| Intel SATA Controller [RAID mode]                                              | 4         | 3.17%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 3.17%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 4         | 3.17%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 3.17%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4         | 3.17%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 3         | 2.38%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 2.38%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 2.38%   |
| Micron Non-Volatile memory controller                                          | 3         | 2.38%   |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 2.38%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 2.38%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 3         | 2.38%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 2.38%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 2         | 1.59%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2         | 1.59%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 1.59%   |
| Phison E12 NVMe Controller                                                     | 2         | 1.59%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 2         | 1.59%   |
| Intel Tiger Lake-LP SATA Controller                                            | 2         | 1.59%   |
| Intel SSD 660P Series                                                          | 2         | 1.59%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 1.59%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 1.59%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 1.59%   |
| AMD 400 Series Chipset SATA Controller                                         | 2         | 1.59%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 0.79%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1         | 0.79%   |
| Seagate FireCuda 510 SSD                                                       | 1         | 0.79%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 1         | 0.79%   |
| SanDisk WD Blue SN570 NVMe SSD                                                 | 1         | 0.79%   |
| SanDisk WD Black NVMe SSD                                                      | 1         | 0.79%   |
| SanDisk PC SN520 NVMe SSD                                                      | 1         | 0.79%   |
| SanDisk Non-Volatile memory controller                                         | 1         | 0.79%   |
| Samsung Apple PCIe SSD                                                         | 1         | 0.79%   |
| Realtek RTS5763DL NVMe SSD Controller                                          | 1         | 0.79%   |
| Realtek Realtek Non-Volatile memory controller                                 | 1         | 0.79%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1         | 0.79%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 63        | 55.26%  |
| NVMe | 39        | 34.21%  |
| RAID | 12        | 10.53%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 63        | 80.77%  |
| AMD    | 15        | 19.23%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-7500U CPU @ 2.70GHz       | 3         | 3.85%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 3         | 3.85%   |
| AMD Ryzen 5 3600X 6-Core Processor      | 3         | 3.85%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 2         | 2.56%   |
| Intel Core i7-4712HQ CPU @ 2.30GHz      | 2         | 2.56%   |
| Intel Core i5-9300H CPU @ 2.40GHz       | 2         | 2.56%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 2         | 2.56%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 2         | 2.56%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 2         | 2.56%   |
| Intel Core i3-8100 CPU @ 3.60GHz        | 2         | 2.56%   |
| AMD Ryzen 7 5800X 8-Core Processor      | 2         | 2.56%   |
| Intel Genuine CPU 0000 @ 2.10GHz        | 1         | 1.28%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 1         | 1.28%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 1         | 1.28%   |
| Intel Core i7-8700K CPU @ 3.70GHz       | 1         | 1.28%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 1         | 1.28%   |
| Intel Core i7-7700K CPU @ 4.20GHz       | 1         | 1.28%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 1         | 1.28%   |
| Intel Core i7-7600U CPU @ 2.80GHz       | 1         | 1.28%   |
| Intel Core i7-6700K CPU @ 4.00GHz       | 1         | 1.28%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz      | 1         | 1.28%   |
| Intel Core i7-4702HQ CPU @ 2.20GHz      | 1         | 1.28%   |
| Intel Core i7-4650U CPU @ 1.70GHz       | 1         | 1.28%   |
| Intel Core i7-3720QM CPU @ 2.60GHz      | 1         | 1.28%   |
| Intel Core i7-2760QM CPU @ 2.40GHz      | 1         | 1.28%   |
| Intel Core i7-10870H CPU @ 2.20GHz      | 1         | 1.28%   |
| Intel Core i7 CPU 870 @ 2.93GHz         | 1         | 1.28%   |
| Intel Core i7 CPU 860 @ 2.80GHz         | 1         | 1.28%   |
| Intel Core i5-9600K CPU @ 3.70GHz       | 1         | 1.28%   |
| Intel Core i5-9400F CPU @ 2.90GHz       | 1         | 1.28%   |
| Intel Core i5-9400 CPU @ 2.90GHz        | 1         | 1.28%   |
| Intel Core i5-6600 CPU @ 3.30GHz        | 1         | 1.28%   |
| Intel Core i5-6500 CPU @ 3.20GHz        | 1         | 1.28%   |
| Intel Core i5-4670 CPU @ 3.40GHz        | 1         | 1.28%   |
| Intel Core i5-4590T CPU @ 2.00GHz       | 1         | 1.28%   |
| Intel Core i5-4300Y CPU @ 1.60GHz       | 1         | 1.28%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 1         | 1.28%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 1         | 1.28%   |
| Intel Core i5-3340M CPU @ 2.70GHz       | 1         | 1.28%   |
| Intel Core i5-3337U CPU @ 1.80GHz       | 1         | 1.28%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model             | Computers | Percent |
|-------------------|-----------|---------|
| Intel Core i5     | 24        | 30.77%  |
| Intel Core i7     | 23        | 29.49%  |
| Other             | 6         | 7.69%   |
| AMD Ryzen 5       | 6         | 7.69%   |
| Intel Core i3     | 5         | 6.41%   |
| AMD Ryzen 7       | 5         | 6.41%   |
| Intel Celeron     | 2         | 2.56%   |
| Intel Genuine     | 1         | 1.28%   |
| Intel Core 2 Quad | 1         | 1.28%   |
| Intel Core 2 Duo  | 1         | 1.28%   |
| AMD Ryzen 9       | 1         | 1.28%   |
| AMD Ryzen 3       | 1         | 1.28%   |
| AMD Athlon        | 1         | 1.28%   |
| AMD A6            | 1         | 1.28%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 36        | 46.15%  |
| 2      | 20        | 25.64%  |
| 6      | 14        | 17.95%  |
| 8      | 7         | 8.97%   |
| 12     | 1         | 1.28%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 78        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 63        | 79.75%  |
| 1      | 16        | 20.25%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 78        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 16        | 20%     |
| 0x906ea    | 6         | 7.5%    |
| 0x806c1    | 5         | 6.25%   |
| 0x306a9    | 5         | 6.25%   |
| 0x806ec    | 4         | 5%      |
| 0x806e9    | 4         | 5%      |
| 0x08701021 | 4         | 5%      |
| 0x506e3    | 3         | 3.75%   |
| 0x306c3    | 3         | 3.75%   |
| 0x0a201016 | 3         | 3.75%   |
| 0x906ed    | 2         | 2.5%    |
| 0x906eb    | 2         | 2.5%    |
| 0x906e9    | 2         | 2.5%    |
| 0x806eb    | 2         | 2.5%    |
| 0x40651    | 2         | 2.5%    |
| 0x1067a    | 2         | 2.5%    |
| 0xa0653    | 1         | 1.25%   |
| 0xa0652    | 1         | 1.25%   |
| 0x806d1    | 1         | 1.25%   |
| 0x706e5    | 1         | 1.25%   |
| 0x706a8    | 1         | 1.25%   |
| 0x406e3    | 1         | 1.25%   |
| 0x206a7    | 1         | 1.25%   |
| 0x20655    | 1         | 1.25%   |
| 0x106e5    | 1         | 1.25%   |
| 0x0a50000b | 1         | 1.25%   |
| 0x08701013 | 1         | 1.25%   |
| 0x08600106 | 1         | 1.25%   |
| 0x08108109 | 1         | 1.25%   |
| 0x0810100b | 1         | 1.25%   |
| 0x06006705 | 1         | 1.25%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 26        | 33.33%  |
| Haswell       | 9         | 11.54%  |
| Zen 2         | 6         | 7.69%   |
| IvyBridge     | 6         | 7.69%   |
| TigerLake     | 5         | 6.41%   |
| Zen 3         | 4         | 5.13%   |
| Skylake       | 4         | 5.13%   |
| Zen+          | 3         | 3.85%   |
| SandyBridge   | 2         | 2.56%   |
| Penryn        | 2         | 2.56%   |
| Nehalem       | 2         | 2.56%   |
| IceLake       | 2         | 2.56%   |
| Goldmont plus | 2         | 2.56%   |
| CometLake     | 2         | 2.56%   |
| Zen           | 1         | 1.28%   |
| Westmere      | 1         | 1.28%   |
| Excavator     | 1         | 1.28%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 49        | 46.23%  |
| Nvidia | 41        | 38.68%  |
| AMD    | 16        | 15.09%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                          | 5         | 4.67%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 4         | 3.74%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 4         | 3.74%   |
| Intel HD Graphics 620                                                     | 4         | 3.74%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 4         | 3.74%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 4         | 3.74%   |
| Nvidia GK107GLM [Quadro K1100M]                                           | 3         | 2.8%    |
| Intel UHD Graphics 620                                                    | 3         | 2.8%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                 | 3         | 2.8%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                   | 3         | 2.8%    |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                    | 2         | 1.87%   |
| Nvidia GP108M [GeForce MX250]                                             | 2         | 1.87%   |
| Nvidia GP108M [GeForce MX150]                                             | 2         | 1.87%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                       | 2         | 1.87%   |
| Nvidia GP104 [GeForce GTX 1080]                                           | 2         | 1.87%   |
| Nvidia GM108M [GeForce 940MX]                                             | 2         | 1.87%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 2         | 1.87%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 2         | 1.87%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 2         | 1.87%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 2         | 1.87%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 0.93%   |
| Nvidia TU117M                                                             | 1         | 0.93%   |
| Nvidia TU117 [GeForce GTX 1650]                                           | 1         | 0.93%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 1         | 0.93%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                     | 1         | 0.93%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                     | 1         | 0.93%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 1         | 0.93%   |
| Nvidia TU106BM [GeForce RTX 2070 Mobile / Max-Q]                          | 1         | 0.93%   |
| Nvidia GP108M [GeForce MX230]                                             | 1         | 0.93%   |
| Nvidia GP108 [GeForce GT 1030]                                            | 1         | 0.93%   |
| Nvidia GP107M [GeForce MX350]                                             | 1         | 0.93%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 0.93%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 1         | 0.93%   |
| Nvidia GP107 [GeForce GTX 1050]                                           | 1         | 0.93%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                        | 1         | 0.93%   |
| Nvidia GM206 [GeForce GTX 960]                                            | 1         | 0.93%   |
| Nvidia GM108M [GeForce 840M]                                              | 1         | 0.93%   |
| Nvidia GM107M [GeForce GTX 860M]                                          | 1         | 0.93%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                         | 1         | 0.93%   |
| Nvidia GK208B [GeForce GT 710]                                            | 1         | 0.93%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Intel + Nvidia | 24        | 30.77%  |
| 1 x Intel      | 20        | 25.64%  |
| 1 x Nvidia     | 16        | 20.51%  |
| 1 x AMD        | 13        | 16.67%  |
| Intel + AMD    | 3         | 3.85%   |
| 2 x Nvidia     | 1         | 1.28%   |
| 2 x Intel      | 1         | 1.28%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 47        | 59.49%  |
| Proprietary | 30        | 37.97%  |
| Unknown     | 2         | 2.53%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 45        | 56.96%  |
| 1.01-2.0   | 14        | 17.72%  |
| 5.01-6.0   | 6         | 7.59%   |
| 7.01-8.0   | 5         | 6.33%   |
| 3.01-4.0   | 3         | 3.8%    |
| 8.01-16.0  | 3         | 3.8%    |
| 0.01-0.5   | 3         | 3.8%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Samsung Electronics  | 15        | 16.48%  |
| AU Optronics         | 12        | 13.19%  |
| BOE                  | 9         | 9.89%   |
| LG Display           | 8         | 8.79%   |
| Chimei Innolux       | 7         | 7.69%   |
| Goldstar             | 5         | 5.49%   |
| Ancor Communications | 5         | 5.49%   |
| Dell                 | 4         | 4.4%    |
| Sharp                | 3         | 3.3%    |
| AOC                  | 3         | 3.3%    |
| Acer                 | 3         | 3.3%    |
| Hewlett-Packard      | 2         | 2.2%    |
| Apple                | 2         | 2.2%    |
| Sceptre Tech         | 1         | 1.1%    |
| PANDA                | 1         | 1.1%    |
| Lenovo               | 1         | 1.1%    |
| Kogan                | 1         | 1.1%    |
| KOC                  | 1         | 1.1%    |
| JRY                  | 1         | 1.1%    |
| Iiyama               | 1         | 1.1%    |
| Idek Iiyama          | 1         | 1.1%    |
| Hitachi              | 1         | 1.1%    |
| Gigabyte Technology  | 1         | 1.1%    |
| CSO                  | 1         | 1.1%    |
| BenQ                 | 1         | 1.1%    |
| ASUSTek Computer     | 1         | 1.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch       | 2         | 2.13%   |
| Samsung Electronics LCD Monitor SAM0F14 3840x2160 950x540mm 43.0-inch   | 2         | 2.13%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch        | 2         | 2.13%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch          | 2         | 2.13%   |
| Sharp LCD Monitor SHP1463 3840x2160 346x194mm 15.6-inch                 | 1         | 1.06%   |
| Sharp LCD Monitor SHP1431 3840x2160 350x190mm 15.7-inch                 | 1         | 1.06%   |
| Sharp LCD Monitor SHP13F8 3200x1800 346x194mm 15.6-inch                 | 1         | 1.06%   |
| Sceptre Tech C27 SPT0ADD 1920x1080 598x336mm 27.0-inch                  | 1         | 1.06%   |
| Samsung Electronics SyncMaster SAM0524 1920x1080 480x270mm 21.7-inch    | 1         | 1.06%   |
| Samsung Electronics SyncMaster SAM02FE 1680x1050 433x271mm 20.1-inch    | 1         | 1.06%   |
| Samsung Electronics SMBX2450L SAM071F 1920x1080 521x293mm 23.5-inch     | 1         | 1.06%   |
| Samsung Electronics SA300/350/360 SAM07D6 1920x1080 531x299mm 24.0-inch | 1         | 1.06%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch   | 1         | 1.06%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch   | 1         | 1.06%   |
| Samsung Electronics LCD Monitor SDC200F 1366x768 344x193mm 15.5-inch    | 1         | 1.06%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 950x540mm 43.0-inch   | 1         | 1.06%   |
| Samsung Electronics LCD Monitor SAM0B60 1920x1080 887x500mm 40.1-inch   | 1         | 1.06%   |
| Samsung Electronics LCD Monitor SAM02EB 1920x540                        | 1         | 1.06%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch     | 1         | 1.06%   |
| PANDA LCD Monitor NCP0063 1920x1080 344x194mm 15.5-inch                 | 1         | 1.06%   |
| LG Display LCD Monitor LGD6E01 1366x768 344x194mm 15.5-inch             | 1         | 1.06%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch            | 1         | 1.06%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch            | 1         | 1.06%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch             | 1         | 1.06%   |
| LG Display LCD Monitor LGD03D7 1366x768 310x174mm 14.0-inch             | 1         | 1.06%   |
| LG Display LCD Monitor LGD03AD 1366x768 309x174mm 14.0-inch             | 1         | 1.06%   |
| LG Display LCD Monitor LGD03A3 1366x768 277x156mm 12.5-inch             | 1         | 1.06%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch             | 1         | 1.06%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                | 1         | 1.06%   |
| Kogan HDMI1 KGN3400 3440x1440 796x334mm 34.0-inch                       | 1         | 1.06%   |
| KOC SXGA85_ANALOG KOC0482 1280x1024 365x292mm 18.4-inch                 | 1         | 1.06%   |
| JRY DP JRY2700 2560x1440 597x336mm 27.0-inch                            | 1         | 1.06%   |
| Iiyama PL2409HD IVM560C 1920x1080 521x293mm 23.5-inch                   | 1         | 1.06%   |
| Idek Iiyama LCD Monitor PL2760Q 2560x1440                               | 1         | 1.06%   |
| Hitachi HISENSE HEC002F 3840x2160 1872x1053mm 84.6-inch                 | 1         | 1.06%   |
| Hewlett-Packard E240c HWP327C 1920x1080 510x290mm 23.1-inch             | 1         | 1.06%   |
| Hewlett-Packard 27w HPN3494 1920x1080 598x336mm 27.0-inch               | 1         | 1.06%   |
| Goldstar ULTRAWIDE GSM76FA 2560x1080 531x298mm 24.0-inch                | 1         | 1.06%   |
| Goldstar LG HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                | 1         | 1.06%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 1         | 1.06%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 45        | 51.72%  |
| 1366x768 (WXGA)    | 9         | 10.34%  |
| 3840x2160 (4K)     | 8         | 9.2%    |
| 2560x1440 (QHD)    | 6         | 6.9%    |
| 3440x1440          | 4         | 4.6%    |
| 2560x1080          | 3         | 3.45%   |
| 1600x900 (HD+)     | 3         | 3.45%   |
| 3840x2400          | 1         | 1.15%   |
| 3840x1080          | 1         | 1.15%   |
| 3200x1800 (QHD+)   | 1         | 1.15%   |
| 2160x1440          | 1         | 1.15%   |
| 1920x540           | 1         | 1.15%   |
| 1920x1200 (WUXGA)  | 1         | 1.15%   |
| 1680x1050 (WSXGA+) | 1         | 1.15%   |
| 1440x900 (WXGA+)   | 1         | 1.15%   |
| 1280x1024 (SXGA)   | 1         | 1.15%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 30        | 32.97%  |
| 27      | 9         | 9.89%   |
| 21      | 7         | 7.69%   |
| 14      | 6         | 6.59%   |
| 34      | 5         | 5.49%   |
| 23      | 5         | 5.49%   |
| 13      | 5         | 5.49%   |
| 84      | 4         | 4.4%    |
| 24      | 4         | 4.4%    |
| 31      | 3         | 3.3%    |
| 17      | 3         | 3.3%    |
| 28      | 2         | 2.2%    |
| 18      | 2         | 2.2%    |
| Unknown | 2         | 2.2%    |
| 54      | 1         | 1.1%    |
| 48      | 1         | 1.1%    |
| 20      | 1         | 1.1%    |
| 12      | 1         | 1.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 38        | 41.76%  |
| 501-600     | 17        | 18.68%  |
| 401-500     | 10        | 10.99%  |
| 701-800     | 5         | 5.49%   |
| 601-700     | 5         | 5.49%   |
| 351-400     | 4         | 4.4%    |
| 201-300     | 4         | 4.4%    |
| 1501-2000   | 4         | 4.4%    |
| 1001-1500   | 2         | 2.2%    |
| Unknown     | 2         | 2.2%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 66        | 81.48%  |
| 21/9    | 7         | 8.64%   |
| 16/10   | 4         | 4.94%   |
| 5/4     | 1         | 1.23%   |
| 32/9    | 1         | 1.23%   |
| 3/2     | 1         | 1.23%   |
| Unknown | 1         | 1.23%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 30        | 33.33%  |
| 201-250        | 15        | 16.67%  |
| 81-90          | 9         | 10%     |
| 301-350        | 9         | 10%     |
| 351-500        | 8         | 8.89%   |
| More than 1000 | 5         | 5.56%   |
| 121-130        | 3         | 3.33%   |
| 71-80          | 2         | 2.22%   |
| 251-300        | 2         | 2.22%   |
| 151-200        | 2         | 2.22%   |
| Unknown        | 2         | 2.22%   |
| 61-70          | 1         | 1.11%   |
| 141-150        | 1         | 1.11%   |
| 501-1000       | 1         | 1.11%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 31        | 36.05%  |
| 51-100        | 23        | 26.74%  |
| 101-120       | 22        | 25.58%  |
| 161-240       | 4         | 4.65%   |
| More than 240 | 3         | 3.49%   |
| Unknown       | 2         | 2.33%   |
| 1-50          | 1         | 1.16%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


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

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 50        | 43.86%  |
| Realtek Semiconductor             | 41        | 35.96%  |
| Qualcomm Atheros                  | 5         | 4.39%   |
| Broadcom Limited                  | 3         | 2.63%   |
| ASIX Electronics                  | 3         | 2.63%   |
| MediaTek                          | 2         | 1.75%   |
| Ericsson Business Mobile Networks | 2         | 1.75%   |
| Broadcom                          | 2         | 1.75%   |
| TP-Link                           | 1         | 0.88%   |
| Samsung Electronics               | 1         | 0.88%   |
| Qualcomm                          | 1         | 0.88%   |
| NetGear                           | 1         | 0.88%   |
| Microsoft                         | 1         | 0.88%   |
| Marvell Technology Group          | 1         | 0.88%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller         | 31        | 22.79%  |
| Intel Wi-Fi 6 AX200                                                       | 6         | 4.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                     | 6         | 4.41%   |
| Intel I211 Gigabit Network Connection                                     | 5         | 3.68%   |
| Intel Cannon Lake PCH CNVi WiFi                                           | 5         | 3.68%   |
| Realtek RTL8125 2.5GbE Controller                                         | 4         | 2.94%   |
| Intel Wireless 7260                                                       | 4         | 2.94%   |
| Intel Wi-Fi 6 AX201                                                       | 4         | 2.94%   |
| Intel Ethernet Connection (2) I219-V                                      | 4         | 2.94%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                              | 4         | 2.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 3         | 2.21%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                  | 3         | 2.21%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                  | 3         | 2.21%   |
| ASIX AX88179 Gigabit Ethernet                                             | 3         | 2.21%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                           | 2         | 1.47%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                | 2         | 1.47%   |
| Intel Wireless-AC 9260                                                    | 2         | 1.47%   |
| Intel Wireless 8265 / 8275                                                | 2         | 1.47%   |
| Intel Ethernet Connection (7) I219-V                                      | 2         | 1.47%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                         | 2         | 1.47%   |
| Ericsson Business Mobile Networks H5321 gw Mobile Broadband Module        | 2         | 1.47%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                | 2         | 1.47%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                       | 1         | 0.74%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)               | 1         | 0.74%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                           | 1         | 0.74%   |
| Realtek RTL8723DE Wireless Network Adapter                                | 1         | 0.74%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                           | 1         | 0.74%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                     | 1         | 0.74%   |
| Realtek 802.11ac NIC                                                      | 1         | 0.74%   |
| Qualcomm Mobile Router                                                    | 1         | 0.74%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                | 1         | 0.74%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                 | 1         | 0.74%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                          | 1         | 0.74%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet            | 1         | 0.74%   |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1         | 0.74%   |
| Microsoft Xbox 360 Wireless Adapter                                       | 1         | 0.74%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                   | 1         | 0.74%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter             | 1         | 0.74%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                      | 1         | 0.74%   |
| Intel Wireless 8260                                                       | 1         | 0.74%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 41        | 64.06%  |
| Realtek Semiconductor | 9         | 14.06%  |
| Qualcomm Atheros      | 4         | 6.25%   |
| Broadcom Limited      | 3         | 4.69%   |
| MediaTek              | 2         | 3.13%   |
| Broadcom              | 2         | 3.13%   |
| TP-Link               | 1         | 1.56%   |
| NetGear               | 1         | 1.56%   |
| Microsoft             | 1         | 1.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                       | 6         | 9.38%   |
| Intel Cannon Lake PCH CNVi WiFi                                           | 5         | 7.81%   |
| Intel Wireless 7260                                                       | 4         | 6.25%   |
| Intel Wi-Fi 6 AX201                                                       | 4         | 6.25%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                              | 4         | 6.25%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                  | 3         | 4.69%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                  | 3         | 4.69%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                           | 2         | 3.13%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                | 2         | 3.13%   |
| Intel Wireless-AC 9260                                                    | 2         | 3.13%   |
| Intel Wireless 8265 / 8275                                                | 2         | 3.13%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                         | 2         | 3.13%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                | 2         | 3.13%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                       | 1         | 1.56%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                           | 1         | 1.56%   |
| Realtek RTL8723DE Wireless Network Adapter                                | 1         | 1.56%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                           | 1         | 1.56%   |
| Realtek 802.11ac NIC                                                      | 1         | 1.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                | 1         | 1.56%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                          | 1         | 1.56%   |
| NetGear Nighthawk A7000 802.11ac Wireless Adapter AC1900 [Realtek 8814AU] | 1         | 1.56%   |
| Microsoft Xbox 360 Wireless Adapter                                       | 1         | 1.56%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                   | 1         | 1.56%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter             | 1         | 1.56%   |
| Intel Wireless 8260                                                       | 1         | 1.56%   |
| Intel Wireless 7265                                                       | 1         | 1.56%   |
| Intel Tiger Lake PCH CNVi WiFi                                            | 1         | 1.56%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                           | 1         | 1.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                          | 1         | 1.56%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                           | 1         | 1.56%   |
| Intel Comet Lake PCH CNVi WiFi                                            | 1         | 1.56%   |
| Intel Centrino Wireless-N 2230                                            | 1         | 1.56%   |
| Intel Centrino Wireless-N 2200                                            | 1         | 1.56%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                | 1         | 1.56%   |
| Broadcom BCM43228 802.11a/b/g/n                                           | 1         | 1.56%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller       | 1         | 1.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 38        | 55.07%  |
| Intel                    | 22        | 31.88%  |
| ASIX Electronics         | 3         | 4.35%   |
| Qualcomm Atheros         | 2         | 2.9%    |
| Samsung Electronics      | 1         | 1.45%   |
| Qualcomm                 | 1         | 1.45%   |
| Marvell Technology Group | 1         | 1.45%   |
| Broadcom                 | 1         | 1.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 31        | 44.29%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 8.57%   |
| Intel I211 Gigabit Network Connection                             | 5         | 7.14%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 5.71%   |
| Intel Ethernet Connection (2) I219-V                              | 4         | 5.71%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 4.29%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 4.29%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 2.86%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 1.43%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 1.43%   |
| Qualcomm Mobile Router                                            | 1         | 1.43%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.43%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 1.43%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 1.43%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.43%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.43%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.43%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.43%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 1.43%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 64        | 49.61%  |
| WiFi     | 63        | 48.84%  |
| Modem    | 2         | 1.55%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 49        | 60.49%  |
| Ethernet | 32        | 39.51%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 38        | 48.72%  |
| 1     | 35        | 44.87%  |
| 3     | 4         | 5.13%   |
| 0     | 1         | 1.28%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 56        | 70.89%  |
| Yes  | 23        | 29.11%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 34        | 55.74%  |
| Broadcom                        | 7         | 11.48%  |
| Realtek Semiconductor           | 5         | 8.2%    |
| Cambridge Silicon Radio         | 4         | 6.56%   |
| IMC Networks                    | 3         | 4.92%   |
| Qualcomm Atheros Communications | 2         | 3.28%   |
| ASUSTek Computer                | 2         | 3.28%   |
| MediaTek                        | 1         | 1.64%   |
| Lite-On Technology              | 1         | 1.64%   |
| Dell                            | 1         | 1.64%   |
| Apple                           | 1         | 1.64%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 12        | 19.67%  |
| Intel Bluetooth wireless interface                  | 7         | 11.48%  |
| Intel AX200 Bluetooth                               | 6         | 9.84%   |
| Intel AX201 Bluetooth                               | 5         | 8.2%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 6.56%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 4.92%   |
| Realtek Bluetooth Radio                             | 2         | 3.28%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 3.28%   |
| IMC Networks Bluetooth Radio                        | 2         | 3.28%   |
| Broadcom BCM20702A0 Bluetooth                       | 2         | 3.28%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 3.28%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 1.64%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 1.64%   |
| MediaTek Wireless_Device                            | 1         | 1.64%   |
| Lite-On Bluetooth Device                            | 1         | 1.64%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.64%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.64%   |
| IMC Networks Wireless_Device                        | 1         | 1.64%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 1.64%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 1.64%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 1.64%   |
| Broadcom BCM2045A0                                  | 1         | 1.64%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 1.64%   |
| ASUS Bluetooth Radio                                | 1         | 1.64%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.64%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 63        | 52.07%  |
| Nvidia                 | 24        | 19.83%  |
| AMD                    | 17        | 14.05%  |
| C-Media Electronics    | 3         | 2.48%   |
| Razer USA              | 2         | 1.65%   |
| Kingston Technology    | 2         | 1.65%   |
| Corsair                | 2         | 1.65%   |
| Tenx Technology        | 1         | 0.83%   |
| Samsung Electronics    | 1         | 0.83%   |
| Realtek Semiconductor  | 1         | 0.83%   |
| Plantronics            | 1         | 0.83%   |
| Logitech               | 1         | 0.83%   |
| Hewlett-Packard        | 1         | 0.83%   |
| Generalplus Technology | 1         | 0.83%   |
| Astro Gaming           | 1         | 0.83%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 8         | 5.67%   |
| Intel Cannon Lake PCH cAVS                                                 | 8         | 5.67%   |
| AMD Starship/Matisse HD Audio Controller                                   | 7         | 4.96%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6         | 4.26%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 6         | 4.26%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 3.55%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 5         | 3.55%   |
| Nvidia TU106 High Definition Audio Controller                              | 4         | 2.84%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 2.84%   |
| Intel 200 Series PCH HD Audio                                              | 4         | 2.84%   |
| AMD Family 17h/19h HD Audio Controller                                     | 4         | 2.84%   |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 2.13%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 2.13%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 2.13%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 2.13%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 2.13%   |
| AMD Navi 10 HDMI Audio                                                     | 3         | 2.13%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 1.42%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 1.42%   |
| Nvidia GP104 High Definition Audio Controller                              | 2         | 1.42%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 1.42%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 1.42%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 1.42%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.42%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 1.42%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 1.42%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2         | 1.42%   |
| Tenx Technology USB AUDIO                                                  | 1         | 0.71%   |
| Samsung Electronics USBC Headset                                           | 1         | 0.71%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.71%   |
| Razer USA RZ04-0318 Gaming Headset [Kraken Ultimate]                       | 1         | 0.71%   |
| Razer USA Razer Kraken X USB                                               | 1         | 0.71%   |
| Plantronics C320-M                                                         | 1         | 0.71%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 0.71%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.71%   |
| Nvidia GP102 HDMI Audio Controller                                         | 1         | 0.71%   |
| Nvidia GM206 High Definition Audio Controller                              | 1         | 0.71%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.71%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 0.71%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 20        | 25%     |
| Samsung Electronics | 18        | 22.5%   |
| Corsair             | 9         | 11.25%  |
| Micron Technology   | 7         | 8.75%   |
| G.Skill             | 6         | 7.5%    |
| Crucial             | 6         | 7.5%    |
| Kingston            | 5         | 6.25%   |
| Unknown             | 4         | 5%      |
| Ramaxel Technology  | 2         | 2.5%    |
| Unifosa             | 1         | 1.25%   |
| Team                | 1         | 1.25%   |
| PNY                 | 1         | 1.25%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 3         | 3.57%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 3.57%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 2.38%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 2.38%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 2         | 2.38%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 2         | 2.38%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                        | 1         | 1.19%   |
| Unknown RAM Module 4GB DIMM DDR4 2133MT/s                        | 1         | 1.19%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                         | 1         | 1.19%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 1         | 1.19%   |
| Unifosa RAM GU512303EP0202 2GB DIMM DDR3 1333MT/s                | 1         | 1.19%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3067MT/s               | 1         | 1.19%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1         | 1.19%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.19%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.19%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.19%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s             | 1         | 1.19%   |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1450MT/s             | 1         | 1.19%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.19%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.19%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 1.19%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 1.19%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 1.19%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 1.19%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 1         | 1.19%   |
| SK hynix RAM HMA81GS6DJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.19%   |
| SK hynix RAM HCNNNFAMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s   | 1         | 1.19%   |
| SK hynix RAM H9CCNNNBJTALAR-NVD 4GB Row Of Chips LPDDR3 2133MT/s | 1         | 1.19%   |
| Samsung RAM Module 8GB DIMM DDR4 2666MT/s                        | 1         | 1.19%   |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s                        | 1         | 1.19%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 1.19%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.19%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.19%   |
| Samsung RAM M471B1G73CB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 1         | 1.19%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 1         | 1.19%   |
| Samsung RAM M471A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s           | 1         | 1.19%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.19%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.19%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.19%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.19%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 44        | 66.67%  |
| DDR3   | 15        | 22.73%  |
| LPDDR4 | 2         | 3.03%   |
| DDR    | 2         | 3.03%   |
| SDRAM  | 1         | 1.52%   |
| LPDDR3 | 1         | 1.52%   |
| DDR2   | 1         | 1.52%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 37        | 55.22%  |
| DIMM         | 24        | 35.82%  |
| Row Of Chips | 6         | 8.96%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 34        | 47.22%  |
| 4096  | 25        | 34.72%  |
| 16384 | 11        | 15.28%  |
| 2048  | 2         | 2.78%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 2667  | 17        | 22.97%  |
| 1600  | 13        | 17.57%  |
| 3200  | 12        | 16.22%  |
| 3600  | 3         | 4.05%   |
| 3266  | 3         | 4.05%   |
| 2933  | 3         | 4.05%   |
| 2400  | 3         | 4.05%   |
| 4267  | 2         | 2.7%    |
| 3400  | 2         | 2.7%    |
| 2133  | 2         | 2.7%    |
| 1333  | 2         | 2.7%    |
| 800   | 2         | 2.7%    |
| 4400  | 1         | 1.35%   |
| 4199  | 1         | 1.35%   |
| 4133  | 1         | 1.35%   |
| 3800  | 1         | 1.35%   |
| 3067  | 1         | 1.35%   |
| 2747  | 1         | 1.35%   |
| 2666  | 1         | 1.35%   |
| 2176  | 1         | 1.35%   |
| 1800  | 1         | 1.35%   |
| 1450  | 1         | 1.35%   |

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

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| IMC Networks                           | 10        | 20%     |
| Realtek Semiconductor                  | 7         | 14%     |
| Chicony Electronics                    | 7         | 14%     |
| Acer                                   | 7         | 14%     |
| Syntek                                 | 3         | 6%      |
| Quanta                                 | 3         | 6%      |
| Microdia                               | 3         | 6%      |
| Sunplus Innovation Technology          | 2         | 4%      |
| Cheng Uei Precision Industry (Foxlink) | 2         | 4%      |
| Suyin                                  | 1         | 2%      |
| Ricoh                                  | 1         | 2%      |
| Logitech                               | 1         | 2%      |
| Lite-On Technology                     | 1         | 2%      |
| Generalplus Technology                 | 1         | 2%      |
| Alpha Imaging Technology               | 1         | 2%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                                         | 4         | 8%      |
| Syntek Integrated Camera                                             | 3         | 6%      |
| IMC Networks USB2.0 HD UVC WebCam                                    | 3         | 6%      |
| Quanta HP TrueVision HD Camera                                       | 2         | 4%      |
| IMC Networks USB2.0 VGA UVC WebCam                                   | 2         | 4%      |
| IMC Networks Integrated Camera                                       | 2         | 4%      |
| Chicony Integrated Camera                                            | 2         | 4%      |
| Chicony EasyCamera                                                   | 2         | 4%      |
| Acer ThinkPad Integrated Camera                                      | 2         | 4%      |
| Acer HD Webcam                                                       | 2         | 4%      |
| Suyin Asus Integrated Webcam                                         | 1         | 2%      |
| Sunplus Laptop_Integrated_Webcam_FHD                                 | 1         | 2%      |
| Sunplus HP Truevision HD                                             | 1         | 2%      |
| Ricoh Integrated Webcam                                              | 1         | 2%      |
| Realtek Integrated Webcam_HD                                         | 1         | 2%      |
| Realtek Integrated Webcam                                            | 1         | 2%      |
| Realtek Built-In Video Camera                                        | 1         | 2%      |
| Quanta HD User Facing                                                | 1         | 2%      |
| Microdia Webcam Vitade AF                                            | 1         | 2%      |
| Microdia Integrated_Webcam_HD                                        | 1         | 2%      |
| Microdia Dell Integrated HD Webcam                                   | 1         | 2%      |
| Logitech Webcam C600                                                 | 1         | 2%      |
| Lite-On Integrated Camera                                            | 1         | 2%      |
| IMC Networks VGA UVC WebCam                                          | 1         | 2%      |
| IMC Networks USB2.0 UVC HD Webcam                                    | 1         | 2%      |
| IMC Networks EasyCamera                                              | 1         | 2%      |
| Generalplus GENERAL WEBCAM                                           | 1         | 2%      |
| Chicony HP Webcam                                                    | 1         | 2%      |
| Chicony HP High Definition 1MP Webcam                                | 1         | 2%      |
| Chicony HD User Facing                                               | 1         | 2%      |
| Cheng Uei Precision Industry (Foxlink) HP High Definition 1MP Webcam | 1         | 2%      |
| Cheng Uei Precision Industry (Foxlink) HD Camera                     | 1         | 2%      |
| Alpha Imaging Integrated_Webcam_8M                                   | 1         | 2%      |
| Acer SunplusIT Integrated Camera                                     | 1         | 2%      |
| Acer Integrated Camera                                               | 1         | 2%      |
| Acer BisonCam, NB Pro                                                | 1         | 2%      |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 2         | 50%     |
| Validity Sensors           | 1         | 25%     |
| Elan Microelectronics      | 1         | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Validity Sensors Synaptics WBDI     | 1         | 25%     |
| Shenzhen Goodix  FingerPrint Device | 1         | 25%     |
| Shenzhen Goodix Fingerprint Reader  | 1         | 25%     |
| Elan ELAN:Fingerprint               | 1         | 25%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Upek     | 2         | 50%     |
| Broadcom | 2         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 2         | 50%     |
| Broadcom BCM5880 Secure Applications Processor             | 2         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 59        | 74.68%  |
| 1     | 17        | 21.52%  |
| 2     | 3         | 3.8%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 6         | 26.09%  |
| Fingerprint reader    | 4         | 17.39%  |
| Chipcard              | 4         | 17.39%  |
| Net/wireless          | 2         | 8.7%    |
| Camera                | 2         | 8.7%    |
| Bluetooth             | 2         | 8.7%    |
| Storage               | 1         | 4.35%   |
| Network               | 1         | 4.35%   |
| Multimedia controller | 1         | 4.35%   |

