Linux in Luxembourg - Tested Hardware & Statistics
--------------------------------------------------

A project to collect tested hardware configurations for Linux in Luxembourg.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Luxembourg/Desktop/README.md) and [notebooks](/Location/Luxembourg/Notebook/README.md).

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

Total: 247

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Acer          | Aspire V3-372               | Notebook    | [09b938a2da](https://linux-hardware.org/?probe=09b938a2da) | Dec 28, 2024 |
| Dell          | Precision 5570              | Notebook    | [225e1aeb1a](https://linux-hardware.org/?probe=225e1aeb1a) | Dec 20, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [cfc4d7a317](https://linux-hardware.org/?probe=cfc4d7a317) | Dec 13, 2024 |
| Acer          | Aspire F5-572G              | Notebook    | [0968b801ff](https://linux-hardware.org/?probe=0968b801ff) | Nov 25, 2024 |
| ASUSTek       | PRIME H510M-E R2.0          | Desktop     | [98d4a70c46](https://linux-hardware.org/?probe=98d4a70c46) | Nov 20, 2024 |
| MACHINIST     | E5-D8-MAX V1.1              | Desktop     | [f162306658](https://linux-hardware.org/?probe=f162306658) | Nov 05, 2024 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [140fff3e9a](https://linux-hardware.org/?probe=140fff3e9a) | Oct 23, 2024 |
| Lenovo        | ThinkPad E14 Gen 3 20YE0... | Notebook    | [d98d306e9d](https://linux-hardware.org/?probe=d98d306e9d) | Oct 21, 2024 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [9ad57b30b6](https://linux-hardware.org/?probe=9ad57b30b6) | Oct 13, 2024 |
| Gigabyte      | H270N-WIFI-CF               | Desktop     | [b86b3cb42d](https://linux-hardware.org/?probe=b86b3cb42d) | Oct 03, 2024 |
| Lenovo        | ThinkPad E14 Gen 3 20YE0... | Notebook    | [1e671e853b](https://linux-hardware.org/?probe=1e671e853b) | Sep 25, 2024 |
| HP            | Pavilion dv7                | Notebook    | [871aaa0215](https://linux-hardware.org/?probe=871aaa0215) | Sep 11, 2024 |
| HP            | Pavilion dv7                | Notebook    | [af8ba6a16b](https://linux-hardware.org/?probe=af8ba6a16b) | Sep 11, 2024 |
| Dell          | XPS 13 9343                 | Notebook    | [e9a7ac7834](https://linux-hardware.org/?probe=e9a7ac7834) | Aug 21, 2024 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [06e181a534](https://linux-hardware.org/?probe=06e181a534) | Aug 20, 2024 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [848c3baea2](https://linux-hardware.org/?probe=848c3baea2) | Aug 14, 2024 |
| MSI           | B85M-E45                    | Desktop     | [0b7dfbd363](https://linux-hardware.org/?probe=0b7dfbd363) | Jul 29, 2024 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS3... | Notebook    | [23f03d0904](https://linux-hardware.org/?probe=23f03d0904) | Jul 28, 2024 |
| ASRock        | H110M-STX                   | Desktop     | [6ed1b1b9b7](https://linux-hardware.org/?probe=6ed1b1b9b7) | Jul 27, 2024 |
| HP            | 89D8 SMVB                   | Desktop     | [1c42d3aa40](https://linux-hardware.org/?probe=1c42d3aa40) | Jul 23, 2024 |
| MSI           | B85M-E45                    | Desktop     | [a8fab1c7ba](https://linux-hardware.org/?probe=a8fab1c7ba) | Jul 15, 2024 |
| Dell          | XPS 13 7390                 | Notebook    | [abd82d0b67](https://linux-hardware.org/?probe=abd82d0b67) | Jul 11, 2024 |
| Micro Comp... | V3                          | Tablet      | [204e563893](https://linux-hardware.org/?probe=204e563893) | Jul 10, 2024 |
| MSI           | Raider 18 HX A14VGG         | Notebook    | [f052ea706e](https://linux-hardware.org/?probe=f052ea706e) | Jun 26, 2024 |
| HP            | 8928 00100                  | All in one  | [cbe450366d](https://linux-hardware.org/?probe=cbe450366d) | Jun 22, 2024 |
| HP            | 8928 00100                  | All in one  | [49179ddacb](https://linux-hardware.org/?probe=49179ddacb) | Jun 20, 2024 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [692f458014](https://linux-hardware.org/?probe=692f458014) | May 01, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [d8f7a5da03](https://linux-hardware.org/?probe=d8f7a5da03) | Apr 23, 2024 |
| JWIPC         | A320I S1                    | Desktop     | [eea8091ffa](https://linux-hardware.org/?probe=eea8091ffa) | Apr 22, 2024 |
| JWIPC         | A320I S1                    | Desktop     | [c8bb6cd872](https://linux-hardware.org/?probe=c8bb6cd872) | Apr 21, 2024 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [89107c7d88](https://linux-hardware.org/?probe=89107c7d88) | Apr 18, 2024 |
| Dell          | Latitude 5490               | Notebook    | [6083d1ad5b](https://linux-hardware.org/?probe=6083d1ad5b) | Apr 09, 2024 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [63a643c790](https://linux-hardware.org/?probe=63a643c790) | Mar 26, 2024 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [529873e41c](https://linux-hardware.org/?probe=529873e41c) | Mar 26, 2024 |
| ASUSTek       | P6X58D PREMIUM              | Desktop     | [3e42f1f6bb](https://linux-hardware.org/?probe=3e42f1f6bb) | Mar 24, 2024 |
| Lenovo        | IdeaPad Pro 5 16APH8 83A... | Notebook    | [0f6b378c5d](https://linux-hardware.org/?probe=0f6b378c5d) | Mar 22, 2024 |
| Dell          | 0KC9NP A01                  | Desktop     | [ee6bd4e717](https://linux-hardware.org/?probe=ee6bd4e717) | Mar 07, 2024 |
| Unknown       | Unknown                     | Notebook    | [bad7799ac9](https://linux-hardware.org/?probe=bad7799ac9) | Feb 11, 2024 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [aa69326408](https://linux-hardware.org/?probe=aa69326408) | Jan 29, 2024 |
| ASUSTek       | K72JT                       | Notebook    | [51117cd448](https://linux-hardware.org/?probe=51117cd448) | Dec 29, 2023 |
| HP            | 198E                        | Desktop     | [30e0f75eee](https://linux-hardware.org/?probe=30e0f75eee) | Dec 27, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [e1e496f1a9](https://linux-hardware.org/?probe=e1e496f1a9) | Dec 15, 2023 |
| Dell          | Precision M3800             | Notebook    | [9e8d36821a](https://linux-hardware.org/?probe=9e8d36821a) | Dec 14, 2023 |
| ASUSTek       | UN65U                       | Mini pc     | [83a33710cc](https://linux-hardware.org/?probe=83a33710cc) | Dec 13, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [6f35ce12bd](https://linux-hardware.org/?probe=6f35ce12bd) | Dec 07, 2023 |
| Dell          | Precision M3800             | Notebook    | [a01e02361f](https://linux-hardware.org/?probe=a01e02361f) | Nov 26, 2023 |
| Lenovo        | Legion 5 15IAH7H 82RB       | Notebook    | [0b974daf24](https://linux-hardware.org/?probe=0b974daf24) | Nov 24, 2023 |
| Framework     | Laptop                      | Notebook    | [ad3c0b1f5c](https://linux-hardware.org/?probe=ad3c0b1f5c) | Nov 10, 2023 |
| Tactus        | GeoFlex 140                 | Convertible | [a386eceffe](https://linux-hardware.org/?probe=a386eceffe) | Nov 05, 2023 |
| Panasonic     | CF-195DCUBML                | Notebook    | [e9e34a8b3b](https://linux-hardware.org/?probe=e9e34a8b3b) | Oct 29, 2023 |
| SLIMBOOK      | EXECUTIVE-14                | Notebook    | [39250155c4](https://linux-hardware.org/?probe=39250155c4) | Oct 26, 2023 |
| Dell          | 02K9CR A02                  | Desktop     | [47ca1834f0](https://linux-hardware.org/?probe=47ca1834f0) | Oct 15, 2023 |
| Acer          | Swift SFG14-71              | Notebook    | [612557336e](https://linux-hardware.org/?probe=612557336e) | Oct 14, 2023 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [19d2454b52](https://linux-hardware.org/?probe=19d2454b52) | Oct 07, 2023 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [4599ccbd45](https://linux-hardware.org/?probe=4599ccbd45) | Oct 07, 2023 |
| Samsung       | 550XBE/350XBE               | Notebook    | [3185dde146](https://linux-hardware.org/?probe=3185dde146) | Oct 04, 2023 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [2953047bfa](https://linux-hardware.org/?probe=2953047bfa) | Sep 25, 2023 |
| MSI           | GE63 7RD                    | Notebook    | [b0aac4eb91](https://linux-hardware.org/?probe=b0aac4eb91) | Sep 13, 2023 |
| MSI           | PRO Z790-P WIFI             | Desktop     | [5b9aef438f](https://linux-hardware.org/?probe=5b9aef438f) | Aug 12, 2023 |
| MSI           | PRO Z790-P WIFI             | Desktop     | [1f3f8a869b](https://linux-hardware.org/?probe=1f3f8a869b) | Aug 12, 2023 |
| Dell          | Precision 7670              | Notebook    | [09797bd60c](https://linux-hardware.org/?probe=09797bd60c) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [50ee937fb2](https://linux-hardware.org/?probe=50ee937fb2) | Aug 02, 2023 |
| BESSTAR Te... | DMAF5 V1.0                  | Desktop     | [93c8724c91](https://linux-hardware.org/?probe=93c8724c91) | Jul 31, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | Notebook    | [2b50e2b375](https://linux-hardware.org/?probe=2b50e2b375) | Jul 29, 2023 |
| Unknown       | T3 MRD                      | Desktop     | [5539799efa](https://linux-hardware.org/?probe=5539799efa) | Jul 26, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [a179c222ea](https://linux-hardware.org/?probe=a179c222ea) | Jul 23, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [f0dcdf797e](https://linux-hardware.org/?probe=f0dcdf797e) | Jul 23, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [49fc9fb8ce](https://linux-hardware.org/?probe=49fc9fb8ce) | Jul 23, 2023 |
| MACHINIST     | E5-D8-MAX V1.1              | Desktop     | [ea68d9762b](https://linux-hardware.org/?probe=ea68d9762b) | Jul 21, 2023 |
| Win Elemen... | M9                          | Desktop     | [2e5ea821f1](https://linux-hardware.org/?probe=2e5ea821f1) | Jul 01, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [a210e832a8](https://linux-hardware.org/?probe=a210e832a8) | Jun 16, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [eb6365c303](https://linux-hardware.org/?probe=eb6365c303) | Jun 16, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X6... | Notebook    | [e3e61eef7a](https://linux-hardware.org/?probe=e3e61eef7a) | Jun 15, 2023 |
| Lenovo        | 1038 NO DPK                 | Server      | [e91c644324](https://linux-hardware.org/?probe=e91c644324) | Jun 02, 2023 |
| BESSTAR Te... | DMAF5 V1.0                  | Desktop     | [53f395d7fa](https://linux-hardware.org/?probe=53f395d7fa) | May 15, 2023 |
| Dell          | Precision M3800             | Notebook    | [f5f8f44c9e](https://linux-hardware.org/?probe=f5f8f44c9e) | May 10, 2023 |
| ASUSTek       | PRIME Z590-P WIFI           | Desktop     | [5d12a9965b](https://linux-hardware.org/?probe=5d12a9965b) | May 06, 2023 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [f3b5a181df](https://linux-hardware.org/?probe=f3b5a181df) | May 02, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [d3ef8c638e](https://linux-hardware.org/?probe=d3ef8c638e) | Apr 30, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [c8bf9d49d4](https://linux-hardware.org/?probe=c8bf9d49d4) | Apr 15, 2023 |
| SLIMBOOK      | EXECUTIVE-14                | Notebook    | [e66056ac2d](https://linux-hardware.org/?probe=e66056ac2d) | Apr 09, 2023 |
| Dell          | Precision 5570              | Notebook    | [a3d5f928ee](https://linux-hardware.org/?probe=a3d5f928ee) | Mar 31, 2023 |
| Acer          | Aspire A514-54              | Notebook    | [94da64753b](https://linux-hardware.org/?probe=94da64753b) | Mar 30, 2023 |
| ASUSTek       | N751JK                      | Notebook    | [813b5026ad](https://linux-hardware.org/?probe=813b5026ad) | Mar 18, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [b5ef4ae548](https://linux-hardware.org/?probe=b5ef4ae548) | Mar 14, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [e79cdeaf10](https://linux-hardware.org/?probe=e79cdeaf10) | Mar 13, 2023 |
| Packard Be... | EasyNote TJ65               | Notebook    | [18f0877a2e](https://linux-hardware.org/?probe=18f0877a2e) | Mar 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [ac5cf996d9](https://linux-hardware.org/?probe=ac5cf996d9) | Mar 03, 2023 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | Desktop     | [5fe0f2c1fe](https://linux-hardware.org/?probe=5fe0f2c1fe) | Feb 18, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [f91712ea02](https://linux-hardware.org/?probe=f91712ea02) | Feb 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [bc56140257](https://linux-hardware.org/?probe=bc56140257) | Jan 25, 2023 |
| HP            | EliteBook x360 1030 G3      | Convertible | [e5ab68f182](https://linux-hardware.org/?probe=e5ab68f182) | Jan 14, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [6666a9b8ca](https://linux-hardware.org/?probe=6666a9b8ca) | Jan 09, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [71c2b809fb](https://linux-hardware.org/?probe=71c2b809fb) | Jan 09, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [5b645cbd36](https://linux-hardware.org/?probe=5b645cbd36) | Dec 22, 2022 |
| MSI           | B85-G43                     | Desktop     | [a8f28d3f69](https://linux-hardware.org/?probe=a8f28d3f69) | Nov 23, 2022 |
| Dell          | Precision 7670              | Notebook    | [93f14c8b55](https://linux-hardware.org/?probe=93f14c8b55) | Nov 21, 2022 |
| Dell          | Latitude 5520               | Notebook    | [91cab639f0](https://linux-hardware.org/?probe=91cab639f0) | Nov 17, 2022 |
| Intel         | DP35DP AAD81073-207         | Desktop     | [c597415419](https://linux-hardware.org/?probe=c597415419) | Nov 11, 2022 |
| Intel         | NUC6i3SYB H81132-503        | Mini pc     | [91aef8cd0f](https://linux-hardware.org/?probe=91aef8cd0f) | Oct 31, 2022 |
| JWIPC         | A320I S1                    | Desktop     | [44689a88d8](https://linux-hardware.org/?probe=44689a88d8) | Oct 16, 2022 |
| Clevo         | W25xHPx                     | Notebook    | [04196b2306](https://linux-hardware.org/?probe=04196b2306) | Oct 13, 2022 |
| HP            | EliteBook 850 G3            | Notebook    | [2eee433657](https://linux-hardware.org/?probe=2eee433657) | Sep 17, 2022 |
| LattePanda    | 3 Delta CDJQ-BS-7-S70JR1... | Desktop     | [dbfdcae895](https://linux-hardware.org/?probe=dbfdcae895) | Sep 08, 2022 |
| LattePanda    | 3 Delta CDJQ-BS-7-S70JR1... | Desktop     | [4167167e38](https://linux-hardware.org/?probe=4167167e38) | Sep 08, 2022 |
| ASUSTek       | N751JK                      | Notebook    | [ca6cba3420](https://linux-hardware.org/?probe=ca6cba3420) | Jul 28, 2022 |
| Wortmann      | MS-1727                     | Notebook    | [4697b4b4e5](https://linux-hardware.org/?probe=4697b4b4e5) | Jul 27, 2022 |
| Gigabyte      | X99-UD3-CF                  | Desktop     | [75dbdd1681](https://linux-hardware.org/?probe=75dbdd1681) | Jul 26, 2022 |
| Gigabyte      | X99-UD3-CF                  | Desktop     | [7eaa9fa16b](https://linux-hardware.org/?probe=7eaa9fa16b) | Jul 26, 2022 |
| HP            | EliteBook 8560p             | Notebook    | [584fe927af](https://linux-hardware.org/?probe=584fe927af) | Jul 19, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [cc9185a171](https://linux-hardware.org/?probe=cc9185a171) | Jul 17, 2022 |
| HP            | 2820h                       | Desktop     | [7303ad365d](https://linux-hardware.org/?probe=7303ad365d) | Jul 11, 2022 |
| ASUSTek       | TUF Gaming FX505DY_TUF50... | Notebook    | [df304b4da1](https://linux-hardware.org/?probe=df304b4da1) | Jun 17, 2022 |
| win elemen... | MoreFine S500+              | Notebook    | [eafff91c80](https://linux-hardware.org/?probe=eafff91c80) | Jun 03, 2022 |
| TUXEDO        | Pulse 14 Gen1               | Notebook    | [ca9c5a57a8](https://linux-hardware.org/?probe=ca9c5a57a8) | May 06, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [731e3d2588](https://linux-hardware.org/?probe=731e3d2588) | Apr 03, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [ad42ffd24d](https://linux-hardware.org/?probe=ad42ffd24d) | Apr 03, 2022 |
| Sony          | VPCCA4E1E                   | Notebook    | [95fc0956c8](https://linux-hardware.org/?probe=95fc0956c8) | Mar 27, 2022 |
| Intel         | NUC7i5BNB J31144-303        | Mini pc     | [09ac53276d](https://linux-hardware.org/?probe=09ac53276d) | Mar 16, 2022 |
| ASUSTek       | UX430UNR                    | Notebook    | [86dc3583ca](https://linux-hardware.org/?probe=86dc3583ca) | Mar 09, 2022 |
| ASUSTek       | UX430UNR                    | Notebook    | [4c45b3ea17](https://linux-hardware.org/?probe=4c45b3ea17) | Mar 06, 2022 |
| ASUSTek       | UX430UNR                    | Notebook    | [a76e22e410](https://linux-hardware.org/?probe=a76e22e410) | Mar 06, 2022 |
| Intel         | DG41WV AAE90316-104         | Desktop     | [b6dc38eb16](https://linux-hardware.org/?probe=b6dc38eb16) | Feb 25, 2022 |
| ASRock        | H110M-STX                   | Desktop     | [e5876258c7](https://linux-hardware.org/?probe=e5876258c7) | Feb 19, 2022 |
| HP            | 255 G6 Notebook PC          | Notebook    | [30c3320bb3](https://linux-hardware.org/?probe=30c3320bb3) | Feb 12, 2022 |
| HP            | 255 G6 Notebook PC          | Notebook    | [d4f9b2d0e3](https://linux-hardware.org/?probe=d4f9b2d0e3) | Feb 12, 2022 |
| Sony          | VPCEB2E1E                   | Notebook    | [e3df114520](https://linux-hardware.org/?probe=e3df114520) | Feb 11, 2022 |
| HP            | ProBook 450 G6              | Notebook    | [d8a9a9c7d3](https://linux-hardware.org/?probe=d8a9a9c7d3) | Jan 31, 2022 |
| Lenovo        | ThinkPad T490 20N3S5DV0S    | Notebook    | [e619ec0303](https://linux-hardware.org/?probe=e619ec0303) | Jan 31, 2022 |
| ASUSTek       | Z97-A                       | Desktop     | [19d74bd6f0](https://linux-hardware.org/?probe=19d74bd6f0) | Jan 31, 2022 |
| Medion        | P6685 MD61138               | Notebook    | [57dfdfb610](https://linux-hardware.org/?probe=57dfdfb610) | Jan 27, 2022 |
| win elemen... | MoreFine S500+              | Notebook    | [d7767ce266](https://linux-hardware.org/?probe=d7767ce266) | Jan 23, 2022 |
| win elemen... | MoreFine S500+              | Notebook    | [d63a6d7de6](https://linux-hardware.org/?probe=d63a6d7de6) | Jan 23, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [6892ab87e1](https://linux-hardware.org/?probe=6892ab87e1) | Jan 13, 2022 |
| Packard Be... | EasyNote TJ65               | Notebook    | [252c250082](https://linux-hardware.org/?probe=252c250082) | Jan 06, 2022 |
| Fujitsu       | LIFEBOOK E746               | Notebook    | [55ac013e1e](https://linux-hardware.org/?probe=55ac013e1e) | Jan 06, 2022 |
| Fujitsu       | LIFEBOOK E746               | Notebook    | [2f7baecdec](https://linux-hardware.org/?probe=2f7baecdec) | Jan 02, 2022 |
| Fujitsu       | LIFEBOOK E746               | Notebook    | [54248086d3](https://linux-hardware.org/?probe=54248086d3) | Dec 25, 2021 |
| Fujitsu       | LIFEBOOK E746               | Notebook    | [1b53993ffc](https://linux-hardware.org/?probe=1b53993ffc) | Dec 25, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [2845eaa223](https://linux-hardware.org/?probe=2845eaa223) | Nov 27, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [63f386f998](https://linux-hardware.org/?probe=63f386f998) | Nov 23, 2021 |
| Sony          | VGN-NS30E_S                 | Notebook    | [a36535818d](https://linux-hardware.org/?probe=a36535818d) | Nov 20, 2021 |
| Medion        | Cattle24 1M                 | Desktop     | [05747b9a42](https://linux-hardware.org/?probe=05747b9a42) | Nov 10, 2021 |
| Medion        | Cattle24 1M                 | Desktop     | [9763c21680](https://linux-hardware.org/?probe=9763c21680) | Nov 10, 2021 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [b2f196476a](https://linux-hardware.org/?probe=b2f196476a) | Nov 04, 2021 |
| YJKC          | vBook                       | Notebook    | [42ccc640d7](https://linux-hardware.org/?probe=42ccc640d7) | Nov 03, 2021 |
| MSI           | GF72 8RD                    | Notebook    | [4ac8472977](https://linux-hardware.org/?probe=4ac8472977) | Oct 23, 2021 |
| Wortmann      | TERRA_MOBILE_1749           | Notebook    | [8917a2fc6b](https://linux-hardware.org/?probe=8917a2fc6b) | Oct 15, 2021 |
| Dell          | Precision M2800             | Notebook    | [b046a9dfe3](https://linux-hardware.org/?probe=b046a9dfe3) | Oct 08, 2021 |
| ASUSTek       | UX360CA                     | Notebook    | [52039745c7](https://linux-hardware.org/?probe=52039745c7) | Sep 15, 2021 |
| ASUSTek       | UX360CA                     | Notebook    | [413bad53c5](https://linux-hardware.org/?probe=413bad53c5) | Sep 14, 2021 |
| HP            | ProBook 450 G6              | Notebook    | [03689a5674](https://linux-hardware.org/?probe=03689a5674) | Sep 10, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U7S... | Notebook    | [da01ae06a6](https://linux-hardware.org/?probe=da01ae06a6) | Sep 09, 2021 |
| ASUSTek       | UN62                        | Desktop     | [0702f80222](https://linux-hardware.org/?probe=0702f80222) | Sep 09, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [ce97f26d1d](https://linux-hardware.org/?probe=ce97f26d1d) | Sep 09, 2021 |
| Dell          | Precision M3800             | Notebook    | [5dba4d3bce](https://linux-hardware.org/?probe=5dba4d3bce) | Sep 07, 2021 |
| Dell          | Inspiron 16 7610            | Notebook    | [29c29dc50b](https://linux-hardware.org/?probe=29c29dc50b) | Sep 06, 2021 |
| Intel         | DG41WV AAE90316-104         | Desktop     | [27c162218f](https://linux-hardware.org/?probe=27c162218f) | Sep 05, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [d819b1cc24](https://linux-hardware.org/?probe=d819b1cc24) | Sep 04, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [b5388437b9](https://linux-hardware.org/?probe=b5388437b9) | Sep 04, 2021 |
| HP            | 829A                        | Mini pc     | [1f3d092233](https://linux-hardware.org/?probe=1f3d092233) | Aug 30, 2021 |
| Samsung       | 950QDB                      | Convertible | [c0dedecfe1](https://linux-hardware.org/?probe=c0dedecfe1) | Aug 26, 2021 |
| Samsung       | 950QDB                      | Convertible | [21ac7cda75](https://linux-hardware.org/?probe=21ac7cda75) | Aug 26, 2021 |
| HP            | Pavilion Gaming Notebook    | Notebook    | [3b8bef3c61](https://linux-hardware.org/?probe=3b8bef3c61) | Aug 23, 2021 |
| HP            | Pavilion Gaming Notebook    | Notebook    | [c2a3d9da9e](https://linux-hardware.org/?probe=c2a3d9da9e) | Aug 12, 2021 |
| HP            | ProBook 6450b               | Notebook    | [e607e5a89e](https://linux-hardware.org/?probe=e607e5a89e) | Jul 31, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [80a7298343](https://linux-hardware.org/?probe=80a7298343) | Jul 27, 2021 |
| Acer          | Aspire V5-561G              | Notebook    | [caf0285b12](https://linux-hardware.org/?probe=caf0285b12) | Jul 17, 2021 |
| HP            | ProBook 450 G6              | Notebook    | [f13877e5d4](https://linux-hardware.org/?probe=f13877e5d4) | Jul 08, 2021 |
| Sony          | VPCP11S1R                   | Notebook    | [185fd7ceef](https://linux-hardware.org/?probe=185fd7ceef) | Jul 05, 2021 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [c031043704](https://linux-hardware.org/?probe=c031043704) | Jul 01, 2021 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [28c858a3ad](https://linux-hardware.org/?probe=28c858a3ad) | Jul 01, 2021 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [b5b8d7a195](https://linux-hardware.org/?probe=b5b8d7a195) | Jun 13, 2021 |
| Lenovo        | ThinkPad T480s 20L7001PF... | Notebook    | [b54604a23d](https://linux-hardware.org/?probe=b54604a23d) | Jun 10, 2021 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [22e9ce0306](https://linux-hardware.org/?probe=22e9ce0306) | Jun 10, 2021 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [4bc5bdf702](https://linux-hardware.org/?probe=4bc5bdf702) | Jun 10, 2021 |
| Fujitsu       | STYLISTIC Q702              | Notebook    | [6af6b1aa99](https://linux-hardware.org/?probe=6af6b1aa99) | May 17, 2021 |
| Wortmann      | TERRA_MOBILE_1749           | Notebook    | [47e02d3203](https://linux-hardware.org/?probe=47e02d3203) | May 14, 2021 |
| Fujitsu       | STYLISTIC Q702              | Notebook    | [ceb707caf8](https://linux-hardware.org/?probe=ceb707caf8) | May 14, 2021 |
| Intel         | DG965SS AAD41678-308        | Desktop     | [d76e4b9ec3](https://linux-hardware.org/?probe=d76e4b9ec3) | May 04, 2021 |
| HP            | Pavilion Gaming Notebook    | Notebook    | [f514df9912](https://linux-hardware.org/?probe=f514df9912) | May 02, 2021 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [565be765f5](https://linux-hardware.org/?probe=565be765f5) | Apr 29, 2021 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | Notebook    | [359bf83027](https://linux-hardware.org/?probe=359bf83027) | Apr 05, 2021 |
| Toshiba       | Satellite C55-A-1N0         | Notebook    | [7fe4a33a38](https://linux-hardware.org/?probe=7fe4a33a38) | Mar 27, 2021 |
| Intel         | DG41WV AAE90316-104         | Desktop     | [af606a347f](https://linux-hardware.org/?probe=af606a347f) | Mar 15, 2021 |
| Gigabyte      | H81M-DS2                    | Desktop     | [439d425d4b](https://linux-hardware.org/?probe=439d425d4b) | Mar 01, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [467f82a695](https://linux-hardware.org/?probe=467f82a695) | Feb 22, 2021 |
| Apple         | MacBookPro14,1              | Notebook    | [34e4083988](https://linux-hardware.org/?probe=34e4083988) | Feb 20, 2021 |
| Dell          | Vostro 3558                 | Notebook    | [176249071b](https://linux-hardware.org/?probe=176249071b) | Feb 13, 2021 |
| HP            | ENVY 15 x360 PC             | Notebook    | [1760641bd6](https://linux-hardware.org/?probe=1760641bd6) | Feb 13, 2021 |
| Gigabyte      | H81M-DS2                    | Desktop     | [3500ce2480](https://linux-hardware.org/?probe=3500ce2480) | Feb 09, 2021 |
| ASUSTek       | Z87-DELUXE                  | Desktop     | [e160eea25a](https://linux-hardware.org/?probe=e160eea25a) | Dec 28, 2020 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | Notebook    | [cdc7e7e576](https://linux-hardware.org/?probe=cdc7e7e576) | Dec 25, 2020 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [ae14c03ffc](https://linux-hardware.org/?probe=ae14c03ffc) | Dec 19, 2020 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [9ec2d84b9b](https://linux-hardware.org/?probe=9ec2d84b9b) | Dec 10, 2020 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [dfebaa1e1e](https://linux-hardware.org/?probe=dfebaa1e1e) | Dec 06, 2020 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [47f9230c3a](https://linux-hardware.org/?probe=47f9230c3a) | Dec 01, 2020 |
| ASUSTek       | PRIME H470M-PLUS            | Desktop     | [1d77b8496d](https://linux-hardware.org/?probe=1d77b8496d) | Nov 28, 2020 |
| Acer          | Aspire 4741                 | Notebook    | [e65bbc0990](https://linux-hardware.org/?probe=e65bbc0990) | Nov 28, 2020 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | Notebook    | [a6b200eda6](https://linux-hardware.org/?probe=a6b200eda6) | Nov 13, 2020 |
| Dell          | Precision 5540              | Notebook    | [5b3140e7e8](https://linux-hardware.org/?probe=5b3140e7e8) | Oct 29, 2020 |
| Gigabyte      | H81M-DS2                    | Desktop     | [e6be700463](https://linux-hardware.org/?probe=e6be700463) | Oct 28, 2020 |
| Dell          | XPS 15 9560                 | Notebook    | [c2660b6ca0](https://linux-hardware.org/?probe=c2660b6ca0) | Oct 07, 2020 |
| ASUSTek       | Z87-A                       | Desktop     | [bbe1190702](https://linux-hardware.org/?probe=bbe1190702) | Oct 01, 2020 |
| Apple         | MacBookPro15,4              | Notebook    | [2352614158](https://linux-hardware.org/?probe=2352614158) | Sep 25, 2020 |
| Lenovo        | ThinkPad T440p 20AWS24B0... | Notebook    | [8178cca0f9](https://linux-hardware.org/?probe=8178cca0f9) | Sep 16, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [a06e93e3e9](https://linux-hardware.org/?probe=a06e93e3e9) | Sep 04, 2020 |
| HP            | ENVY x360 Convertible 15... | Convertible | [0c09e0b8ba](https://linux-hardware.org/?probe=0c09e0b8ba) | Sep 03, 2020 |
| Timi          | RedmiBook 14 II             | Notebook    | [6cd091184f](https://linux-hardware.org/?probe=6cd091184f) | Aug 21, 2020 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [ffd532c8d8](https://linux-hardware.org/?probe=ffd532c8d8) | Aug 16, 2020 |
| Gigabyte      | Z97X-Gaming 5               | Desktop     | [e1c1c22a7b](https://linux-hardware.org/?probe=e1c1c22a7b) | Aug 11, 2020 |
| Packard Be... | EasyNote TJ65               | Notebook    | [cce3b0b23c](https://linux-hardware.org/?probe=cce3b0b23c) | Aug 07, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [2de50effb2](https://linux-hardware.org/?probe=2de50effb2) | Jul 26, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [c85723b6bf](https://linux-hardware.org/?probe=c85723b6bf) | Jul 23, 2020 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [3f740083f9](https://linux-hardware.org/?probe=3f740083f9) | Jul 19, 2020 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [f1c586d370](https://linux-hardware.org/?probe=f1c586d370) | Jul 19, 2020 |
| Lenovo        | ThinkPad P1 Gen 2 20QTCT... | Notebook    | [0037393fbf](https://linux-hardware.org/?probe=0037393fbf) | Jul 02, 2020 |
| Clevo         | P170EM                      | Notebook    | [41248f6ae8](https://linux-hardware.org/?probe=41248f6ae8) | Jun 13, 2020 |
| Clevo         | P170EM                      | Notebook    | [6f7578fede](https://linux-hardware.org/?probe=6f7578fede) | Jun 13, 2020 |
| Medion        | MS-7848                     | Desktop     | [6c60cef00e](https://linux-hardware.org/?probe=6c60cef00e) | May 06, 2020 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [33665c7f49](https://linux-hardware.org/?probe=33665c7f49) | May 04, 2020 |
| Lenovo        | G50-70 20351                | Notebook    | [fac974e5a6](https://linux-hardware.org/?probe=fac974e5a6) | May 03, 2020 |
| HP            | ENVY Laptop 17-ce1xxx       | Notebook    | [cf98b2c860](https://linux-hardware.org/?probe=cf98b2c860) | Apr 13, 2020 |
| Wortmann      | TERRA_MOBILE_1541H          | Notebook    | [46b44d2d1f](https://linux-hardware.org/?probe=46b44d2d1f) | Apr 12, 2020 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | Notebook    | [91c4d3ed7c](https://linux-hardware.org/?probe=91c4d3ed7c) | Apr 10, 2020 |
| Acer          | Aspire E5-771G              | Notebook    | [c8a1411a14](https://linux-hardware.org/?probe=c8a1411a14) | Mar 28, 2020 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [6e21e82c58](https://linux-hardware.org/?probe=6e21e82c58) | Mar 26, 2020 |
| Dell          | Precision M3800             | Notebook    | [33ee2bd8db](https://linux-hardware.org/?probe=33ee2bd8db) | Mar 22, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [945a4d4691](https://linux-hardware.org/?probe=945a4d4691) | Mar 21, 2020 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [68e88028d6](https://linux-hardware.org/?probe=68e88028d6) | Jan 09, 2020 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [453044841e](https://linux-hardware.org/?probe=453044841e) | Jan 09, 2020 |
| Foxconn       | 2AA9                        | Desktop     | [2b2a941903](https://linux-hardware.org/?probe=2b2a941903) | Jan 07, 2020 |
| Foxconn       | 2AA9                        | Desktop     | [ed7e0428fb](https://linux-hardware.org/?probe=ed7e0428fb) | Jan 07, 2020 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | Desktop     | [c1c91fe558](https://linux-hardware.org/?probe=c1c91fe558) | Nov 18, 2019 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | Desktop     | [9ee20bcfcb](https://linux-hardware.org/?probe=9ee20bcfcb) | Nov 18, 2019 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | Desktop     | [3b96b0c40d](https://linux-hardware.org/?probe=3b96b0c40d) | Nov 17, 2019 |
| HP            | Spectre Laptop 13-af0xx     | Notebook    | [8ee92af301](https://linux-hardware.org/?probe=8ee92af301) | Oct 12, 2019 |
| MSI           | GF72 8RD                    | Notebook    | [b0a808dbdb](https://linux-hardware.org/?probe=b0a808dbdb) | Aug 09, 2019 |
| Gigabyte      | Z270M-D3H-CF                | Desktop     | [3bcd649400](https://linux-hardware.org/?probe=3bcd649400) | Jul 14, 2019 |
| Samsung       | Galaxy TabPro S LTE         | Tablet      | [d7b5599247](https://linux-hardware.org/?probe=d7b5599247) | May 28, 2019 |
| Samsung       | Galaxy TabPro S LTE         | Tablet      | [8a3fcf81ad](https://linux-hardware.org/?probe=8a3fcf81ad) | May 28, 2019 |
| Sony          | SVF1421E2EW                 | Notebook    | [6fd2106f13](https://linux-hardware.org/?probe=6fd2106f13) | Mar 02, 2019 |
| Medion        | E4254 MD62100               | Notebook    | [660722192a](https://linux-hardware.org/?probe=660722192a) | Jan 25, 2019 |
| Microsoft     | Surface Book 2              | Tablet      | [cc42cece8a](https://linux-hardware.org/?probe=cc42cece8a) | Jan 19, 2019 |
| HP            | 3048h                       | Desktop     | [ab8f89fdcc](https://linux-hardware.org/?probe=ab8f89fdcc) | Oct 07, 2018 |
| Intel         | NUC5i3RYB H41000-505        | Mini pc     | [7fcdfdf9e4](https://linux-hardware.org/?probe=7fcdfdf9e4) | Jul 05, 2017 |
| MSI           | NF750-G55                   | Desktop     | [d1b2ddb193](https://linux-hardware.org/?probe=d1b2ddb193) | May 22, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 22        | 11.34%  |
| Ubuntu 22.04                 | 15        | 7.73%   |
| Ubuntu 18.04                 | 10        | 5.15%   |
| Arch Rolling                 | 6         | 3.09%   |
| Ubuntu 21.04                 | 4         | 2.06%   |
| openSUSE Tumbleweed-XXXXXXXX | 4         | 2.06%   |
| OpenMandriva 4.90            | 4         | 2.06%   |
| Linux Mint 20.3              | 4         | 2.06%   |
| Fedora 38                    | 4         | 2.06%   |
| Xubuntu 20.04                | 3         | 1.55%   |
| Ubuntu 20.10                 | 3         | 1.55%   |
| Pop!_OS 22.04                | 3         | 1.55%   |
| Pop!_OS 21.04                | 3         | 1.55%   |
| OpenMandriva 4.2             | 3         | 1.55%   |
| Linux Mint 21.2              | 3         | 1.55%   |
| Fedora 39                    | 3         | 1.55%   |
| Fedora 37                    | 3         | 1.55%   |
| Fedora 32                    | 3         | 1.55%   |
| ArcoLinux Rolling            | 3         | 1.55%   |
| Zorin 16                     | 2         | 1.03%   |
| Ubuntu 24.04                 | 2         | 1.03%   |
| Ubuntu 23.10                 | 2         | 1.03%   |
| Ubuntu 18.10                 | 2         | 1.03%   |
| Pop!_OS 21.10                | 2         | 1.03%   |
| openSUSE Leap-15.2           | 2         | 1.03%   |
| OpenMandriva 24.12           | 2         | 1.03%   |
| OpenMandriva 23.03           | 2         | 1.03%   |
| Lubuntu 22.04                | 2         | 1.03%   |
| LMDE 4                       | 2         | 1.03%   |
| Linux Mint 20.1              | 2         | 1.03%   |
| Kubuntu 22.04                | 2         | 1.03%   |
| Fedora 40                    | 2         | 1.03%   |
| EndeavourOS Rolling          | 2         | 1.03%   |
| Debian 10                    | 2         | 1.03%   |
| Xubuntu 18.04                | 1         | 0.52%   |
| Xubuntu 16.04                | 1         | 0.52%   |
| UbuntuDDE 20.04              | 1         | 0.52%   |
| Ubuntu Studio 20.04          | 1         | 0.52%   |
| Ubuntu MATE 21.10            | 1         | 0.52%   |
| Ubuntu MATE 20.04            | 1         | 0.52%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 60        | 33.15%  |
| Fedora        | 16        | 8.84%   |
| OpenMandriva  | 12        | 6.63%   |
| Linux Mint    | 10        | 5.52%   |
| Pop!_OS       | 9         | 4.97%   |
| openSUSE      | 8         | 4.42%   |
| Arch          | 7         | 3.87%   |
| Kubuntu       | 6         | 3.31%   |
| Xubuntu       | 5         | 2.76%   |
| Manjaro       | 4         | 2.21%   |
| Lubuntu       | 4         | 2.21%   |
| Elementary    | 3         | 1.66%   |
| Debian        | 3         | 1.66%   |
| ArcoLinux     | 3         | 1.66%   |
| Zorin         | 2         | 1.1%    |
| Ubuntu MATE   | 2         | 1.1%    |
| Parrot        | 2         | 1.1%    |
| LMDE          | 2         | 1.1%    |
| KDE neon      | 2         | 1.1%    |
| Kali          | 2         | 1.1%    |
| Gentoo        | 2         | 1.1%    |
| Endless       | 2         | 1.1%    |
| EndeavourOS   | 2         | 1.1%    |
| CachyOS       | 2         | 1.1%    |
| UbuntuDDE     | 1         | 0.55%   |
| Ubuntu Studio | 1         | 0.55%   |
| ROSA          | 1         | 0.55%   |
| RHEL          | 1         | 0.55%   |
| MX            | 1         | 0.55%   |
| Mageia        | 1         | 0.55%   |
| Garuda Linux  | 1         | 0.55%   |
| Clear Linux   | 1         | 0.55%   |
| CentOS        | 1         | 0.55%   |
| BlackPanther  | 1         | 0.55%   |
| Artix         | 1         | 0.55%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Computers | Percent |
|-----------------------------|-----------|---------|
| 5.18.12-desktop-3omv4090    | 4         | 1.97%   |
| 5.8.0-43-generic            | 3         | 1.48%   |
| 5.15.0-52-generic           | 3         | 1.48%   |
| 5.11.0-27-generic           | 3         | 1.48%   |
| 5.10.14-desktop-1omv4002    | 3         | 1.48%   |
| 6.8.0-40-generic            | 2         | 0.99%   |
| 6.5.0-28-generic            | 2         | 0.99%   |
| 6.2.6-desktop-1omv2390      | 2         | 0.99%   |
| 6.2.14-200.fc37.x86_64      | 2         | 0.99%   |
| 6.12.1-desktop-1omv2490     | 2         | 0.99%   |
| 5.8.0-59-generic            | 2         | 0.99%   |
| 5.4.0-96-generic            | 2         | 0.99%   |
| 5.4.0-90-generic            | 2         | 0.99%   |
| 5.4.0-47-generic            | 2         | 0.99%   |
| 5.4.0-42-generic            | 2         | 0.99%   |
| 5.4.0-122-generic           | 2         | 0.99%   |
| 5.3.0-46-generic            | 2         | 0.99%   |
| 5.19.0-35-generic           | 2         | 0.99%   |
| 5.16.11-76051611-generic    | 2         | 0.99%   |
| 5.11.0-34-generic           | 2         | 0.99%   |
| 5.11.0-17-generic           | 2         | 0.99%   |
| 5.0.0-23-generic            | 2         | 0.99%   |
| 4.19.0-17-amd64             | 2         | 0.99%   |
| 6.9.9-arch1-1               | 1         | 0.49%   |
| 6.9.8-arch1-1               | 1         | 0.49%   |
| 6.9.7-200.fc40.x86_64       | 1         | 0.49%   |
| 6.9.5-zen1-1-zen            | 1         | 0.49%   |
| 6.8.6-300.fc40.x86_64       | 1         | 0.49%   |
| 6.8.0-48-generic            | 1         | 0.49%   |
| 6.8.0-45-generic            | 1         | 0.49%   |
| 6.8.0-36-generic            | 1         | 0.49%   |
| 6.8.0-35-generic            | 1         | 0.49%   |
| 6.7.9-200.fc39.x86_64       | 1         | 0.49%   |
| 6.6.7-arch1-1               | 1         | 0.49%   |
| 6.6.6-200.fc39.x86_64       | 1         | 0.49%   |
| 6.6.54-2-MANJARO            | 1         | 0.49%   |
| 6.6.42-1-lts                | 1         | 0.49%   |
| 6.6.4-200.fc39.x86_64       | 1         | 0.49%   |
| 6.6.29-1-lts                | 1         | 0.49%   |
| 6.6.22-gentoo-dist-hardened | 1         | 0.49%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 22        | 11.22%  |
| 5.15.0  | 18        | 9.18%   |
| 5.11.0  | 14        | 7.14%   |
| 5.8.0   | 10        | 5.1%    |
| 6.5.0   | 8         | 4.08%   |
| 5.19.0  | 7         | 3.57%   |
| 6.8.0   | 6         | 3.06%   |
| 5.3.0   | 6         | 3.06%   |
| 4.18.0  | 6         | 3.06%   |
| 5.18.12 | 4         | 2.04%   |
| 5.13.0  | 4         | 2.04%   |
| 4.15.0  | 4         | 2.04%   |
| 5.10.14 | 3         | 1.53%   |
| 5.0.0   | 3         | 1.53%   |
| 6.4.3   | 2         | 1.02%   |
| 6.2.6   | 2         | 1.02%   |
| 6.2.14  | 2         | 1.02%   |
| 6.2.0   | 2         | 1.02%   |
| 6.12.1  | 2         | 1.02%   |
| 5.7.0   | 2         | 1.02%   |
| 5.3.18  | 2         | 1.02%   |
| 5.16.11 | 2         | 1.02%   |
| 5.10.0  | 2         | 1.02%   |
| 4.19.0  | 2         | 1.02%   |
| 6.9.9   | 1         | 0.51%   |
| 6.9.8   | 1         | 0.51%   |
| 6.9.7   | 1         | 0.51%   |
| 6.9.5   | 1         | 0.51%   |
| 6.8.6   | 1         | 0.51%   |
| 6.7.9   | 1         | 0.51%   |
| 6.6.7   | 1         | 0.51%   |
| 6.6.6   | 1         | 0.51%   |
| 6.6.54  | 1         | 0.51%   |
| 6.6.42  | 1         | 0.51%   |
| 6.6.4   | 1         | 0.51%   |
| 6.6.29  | 1         | 0.51%   |
| 6.6.22  | 1         | 0.51%   |
| 6.6.2   | 1         | 0.51%   |
| 6.5.7   | 1         | 0.51%   |
| 6.5.5   | 1         | 0.51%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 22        | 11.28%  |
| 5.15    | 20        | 10.26%  |
| 5.11    | 14        | 7.18%   |
| 6.5     | 11        | 5.64%   |
| 5.8     | 11        | 5.64%   |
| 6.6     | 8         | 4.1%    |
| 5.3     | 8         | 4.1%    |
| 6.8     | 7         | 3.59%   |
| 6.2     | 7         | 3.59%   |
| 5.19    | 7         | 3.59%   |
| 5.10    | 7         | 3.59%   |
| 4.18    | 7         | 3.59%   |
| 5.7     | 6         | 3.08%   |
| 5.18    | 6         | 3.08%   |
| 6.4     | 5         | 2.56%   |
| 5.13    | 5         | 2.56%   |
| 6.9     | 4         | 2.05%   |
| 6.1     | 4         | 2.05%   |
| 5.16    | 4         | 2.05%   |
| 4.15    | 4         | 2.05%   |
| 6.12    | 3         | 1.54%   |
| 5.0     | 3         | 1.54%   |
| 6.3     | 2         | 1.03%   |
| 6.11    | 2         | 1.03%   |
| 6.10    | 2         | 1.03%   |
| 6.0     | 2         | 1.03%   |
| 5.9     | 2         | 1.03%   |
| 5.14    | 2         | 1.03%   |
| 5.12    | 2         | 1.03%   |
| 4.19    | 2         | 1.03%   |
| 6.7     | 1         | 0.51%   |
| 5.6     | 1         | 0.51%   |
| 5.5     | 1         | 0.51%   |
| 4.9     | 1         | 0.51%   |
| 4.4     | 1         | 0.51%   |
| 4.12    | 1         | 0.51%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 173       | 98.86%  |
| i686   | 2         | 1.14%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 77        | 42.54%  |
| KDE5            | 30        | 16.57%  |
| Unknown         | 21        | 11.6%   |
| XFCE            | 13        | 7.18%   |
| X-Cinnamon      | 11        | 6.08%   |
| KDE6            | 5         | 2.76%   |
| KDE             | 5         | 2.76%   |
| MATE            | 4         | 2.21%   |
| Pantheon        | 3         | 1.66%   |
| LXQt            | 3         | 1.66%   |
| Cinnamon        | 3         | 1.66%   |
| i3              | 2         | 1.1%    |
| Deepin          | 2         | 1.1%    |
| LXDE            | 1         | 0.55%   |
| GNOME Flashback | 1         | 0.55%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 122       | 66.67%  |
| Wayland | 45        | 24.59%  |
| Unknown | 11        | 6.01%   |
| Tty     | 5         | 2.73%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 77        | 42.08%  |
| SDDM    | 34        | 18.58%  |
| GDM3    | 23        | 12.57%  |
| GDM     | 23        | 12.57%  |
| LightDM | 21        | 11.48%  |
| TDM     | 4         | 2.19%   |
| XDM     | 1         | 0.55%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 83        | 45.86%  |
| en_GB   | 16        | 8.84%   |
| fr_FR   | 14        | 7.73%   |
| de_LU   | 12        | 6.63%   |
| de_DE   | 12        | 6.63%   |
| Unknown | 12        | 6.63%   |
| C       | 7         | 3.87%   |
| fr_LU   | 6         | 3.31%   |
| es_ES   | 3         | 1.66%   |
| POSIX   | 2         | 1.1%    |
| nl_NL   | 2         | 1.1%    |
| unm_US  | 1         | 0.55%   |
| pt_PT   | 1         | 0.55%   |
| pt_BR   | 1         | 0.55%   |
| lb_LU   | 1         | 0.55%   |
| it_IT   | 1         | 0.55%   |
| hr_HR   | 1         | 0.55%   |
| fr_CH   | 1         | 0.55%   |
| fr_BE   | 1         | 0.55%   |
| en_IE   | 1         | 0.55%   |
| en_AU   | 1         | 0.55%   |
| de_CH   | 1         | 0.55%   |
| C.UTF8  | 1         | 0.55%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 101       | 56.42%  |
| BIOS | 78        | 43.58%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 124       | 68.89%  |
| Btrfs   | 25        | 13.89%  |
| Overlay | 11        | 6.11%   |
| Tmpfs   | 10        | 5.56%   |
| Xfs     | 6         | 3.33%   |
| Unknown | 3         | 1.67%   |
| Zfs     | 1         | 0.56%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 92        | 51.69%  |
| Unknown | 73        | 41.01%  |
| MBR     | 13        | 7.3%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 157       | 88.7%   |
| Yes       | 20        | 11.3%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 129       | 73.3%   |
| Yes       | 47        | 26.7%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| ASUSTek Computer                 | 26        | 14.86%  |
| Hewlett-Packard                  | 24        | 13.71%  |
| Lenovo                           | 20        | 11.43%  |
| Dell                             | 16        | 9.14%   |
| MSI                              | 10        | 5.71%   |
| Gigabyte Technology              | 10        | 5.71%   |
| Acer                             | 8         | 4.57%   |
| Apple                            | 7         | 4%      |
| Intel                            | 6         | 3.43%   |
| Sony                             | 5         | 2.86%   |
| Medion                           | 4         | 2.29%   |
| HUAWEI                           | 4         | 2.29%   |
| ASRock                           | 4         | 2.29%   |
| Wortmann AG                      | 3         | 1.71%   |
| win element                      | 3         | 1.71%   |
| Samsung Electronics              | 2         | 1.14%   |
| Fujitsu                          | 2         | 1.14%   |
| Framework                        | 2         | 1.14%   |
| Clevo                            | 2         | 1.14%   |
| Unknown                          | 2         | 1.14%   |
| YJKC                             | 1         | 0.57%   |
| TUXEDO                           | 1         | 0.57%   |
| Toshiba                          | 1         | 0.57%   |
| Timi                             | 1         | 0.57%   |
| SLIMBOOK                         | 1         | 0.57%   |
| Panasonic                        | 1         | 0.57%   |
| Packard Bell                     | 1         | 0.57%   |
| Notebook                         | 1         | 0.57%   |
| Microsoft                        | 1         | 0.57%   |
| Micro Computer (HK) Tech Limited | 1         | 0.57%   |
| MACHINIST                        | 1         | 0.57%   |
| LattePanda                       | 1         | 0.57%   |
| JWIPC                            | 1         | 0.57%   |
| Foxconn                          | 1         | 0.57%   |
| BESSTAR Tech                     | 1         | 0.57%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| ASUS All Series                | 3         | 1.71%   |
| win element MoreFine S500+     | 2         | 1.14%   |
| Dell Precision M3800           | 2         | 1.14%   |
| Dell Precision 7670            | 2         | 1.14%   |
| Apple MacBookPro8,1            | 2         | 1.14%   |
| Unknown                        | 2         | 1.14%   |
| YJKC vBook                     | 1         | 0.57%   |
| Wortmann AG TERRA_MOBILE_1749  | 1         | 0.57%   |
| Wortmann AG TERRA_MOBILE_1541H | 1         | 0.57%   |
| Wortmann AG MS-1727            | 1         | 0.57%   |
| Win Element M9                 | 1         | 0.57%   |
| TUXEDO Pulse 14 Gen1           | 1         | 0.57%   |
| Toshiba Satellite C55-A-1N0    | 1         | 0.57%   |
| Timi RedmiBook 14 II           | 1         | 0.57%   |
| Sony VPCP11S1R                 | 1         | 0.57%   |
| Sony VPCEB2E1E                 | 1         | 0.57%   |
| Sony VPCCA4E1E                 | 1         | 0.57%   |
| Sony VGN-NS30E_S               | 1         | 0.57%   |
| Sony SVF1421E2EW               | 1         | 0.57%   |
| SLIMBOOK EXECUTIVE-14          | 1         | 0.57%   |
| Samsung Galaxy TabPro S LTE    | 1         | 0.57%   |
| Samsung 950QDB                 | 1         | 0.57%   |
| Panasonic CF-195DCUBML         | 1         | 0.57%   |
| Packard Bell EasyNote TJ65     | 1         | 0.57%   |
| Notebook NV4XMB,ME,MZ          | 1         | 0.57%   |
| MSI Raider 18 HX A14VGG        | 1         | 0.57%   |
| MSI MS-7E06                    | 1         | 0.57%   |
| MSI MS-7D75                    | 1         | 0.57%   |
| MSI MS-7C91                    | 1         | 0.57%   |
| MSI MS-7C80                    | 1         | 0.57%   |
| MSI MS-7C08                    | 1         | 0.57%   |
| MSI MS-7817                    | 1         | 0.57%   |
| MSI MS-7816                    | 1         | 0.57%   |
| MSI GF72 8RD                   | 1         | 0.57%   |
| MSI GE63 7RD                   | 1         | 0.57%   |
| Microsoft Surface Book 2       | 1         | 0.57%   |
| Micro (HK) Tech Limited V3     | 1         | 0.57%   |
| Medion P961x                   | 1         | 0.57%   |
| Medion P6685 MD61138           | 1         | 0.57%   |
| Medion MS-7848                 | 1         | 0.57%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 13        | 7.43%   |
| Dell Precision         | 8         | 4.57%   |
| HP EliteBook           | 6         | 3.43%   |
| Acer Aspire            | 6         | 3.43%   |
| ASUS PRIME             | 5         | 2.86%   |
| HP ENVY                | 4         | 2.29%   |
| Dell XPS               | 4         | 2.29%   |
| ASUS VivoBook          | 3         | 1.71%   |
| ASUS TUF               | 3         | 1.71%   |
| ASUS ROG               | 3         | 1.71%   |
| ASUS All               | 3         | 1.71%   |
| Wortmann AG TERRA      | 2         | 1.14%   |
| win element MoreFine   | 2         | 1.14%   |
| Lenovo IdeaPad         | 2         | 1.14%   |
| HP ZBook               | 2         | 1.14%   |
| HP ProBook             | 2         | 1.14%   |
| HP Pavilion            | 2         | 1.14%   |
| HP Compaq              | 2         | 1.14%   |
| Framework Laptop       | 2         | 1.14%   |
| Apple MacBookPro8      | 2         | 1.14%   |
| Unknown                | 2         | 1.14%   |
| YJKC vBook             | 1         | 0.57%   |
| Wortmann AG MS-1727    | 1         | 0.57%   |
| Win Element M9         | 1         | 0.57%   |
| TUXEDO Pulse           | 1         | 0.57%   |
| Toshiba Satellite      | 1         | 0.57%   |
| Timi RedmiBook         | 1         | 0.57%   |
| Sony VPCP11S1R         | 1         | 0.57%   |
| Sony VPCEB2E1E         | 1         | 0.57%   |
| Sony VPCCA4E1E         | 1         | 0.57%   |
| Sony VGN-NS30E         | 1         | 0.57%   |
| Sony SVF1421E2EW       | 1         | 0.57%   |
| SLIMBOOK EXECUTIVE-14  | 1         | 0.57%   |
| Samsung Galaxy         | 1         | 0.57%   |
| Samsung 950QDB         | 1         | 0.57%   |
| Panasonic CF-195DCUBML | 1         | 0.57%   |
| Packard Bell EasyNote  | 1         | 0.57%   |
| Notebook NV4XMB        | 1         | 0.57%   |
| MSI Raider             | 1         | 0.57%   |
| MSI MS-7E06            | 1         | 0.57%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 20        | 11.43%  |
| 2018 | 19        | 10.86%  |
| 2021 | 18        | 10.29%  |
| 2014 | 16        | 9.14%   |
| 2020 | 15        | 8.57%   |
| 2017 | 13        | 7.43%   |
| 2013 | 13        | 7.43%   |
| 2022 | 9         | 5.14%   |
| 2016 | 8         | 4.57%   |
| 2010 | 8         | 4.57%   |
| 2023 | 7         | 4%      |
| 2011 | 7         | 4%      |
| 2012 | 6         | 3.43%   |
| 2015 | 5         | 2.86%   |
| 2009 | 4         | 2.29%   |
| 2024 | 3         | 1.71%   |
| 2008 | 2         | 1.14%   |
| 2007 | 2         | 1.14%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 103       | 58.86%  |
| Desktop     | 57        | 32.57%  |
| Mini pc     | 5         | 2.86%   |
| Convertible | 4         | 2.29%   |
| Tablet      | 3         | 1.71%   |
| All in one  | 2         | 1.14%   |
| Server      | 1         | 0.57%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 156       | 88.64%  |
| Enabled  | 20        | 11.36%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 175       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 48        | 26.82%  |
| 4.01-8.0        | 34        | 18.99%  |
| 8.01-16.0       | 32        | 17.88%  |
| 32.01-64.0      | 28        | 15.64%  |
| 3.01-4.0        | 19        | 10.61%  |
| 64.01-256.0     | 7         | 3.91%   |
| 24.01-32.0      | 6         | 3.35%   |
| 2.01-3.0        | 2         | 1.12%   |
| 1.01-2.0        | 2         | 1.12%   |
| More than 256.0 | 1         | 0.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 54        | 28.27%  |
| 1.01-2.0   | 43        | 22.51%  |
| 4.01-8.0   | 40        | 20.94%  |
| 3.01-4.0   | 25        | 13.09%  |
| 8.01-16.0  | 19        | 9.95%   |
| 0.51-1.0   | 4         | 2.09%   |
| 24.01-32.0 | 2         | 1.05%   |
| 16.01-24.0 | 2         | 1.05%   |
| 32.01-64.0 | 1         | 0.52%   |
| 0.01-0.5   | 1         | 0.52%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 101       | 56.42%  |
| 2      | 44        | 24.58%  |
| 3      | 16        | 8.94%   |
| 4      | 8         | 4.47%   |
| 7      | 4         | 2.23%   |
| 5      | 3         | 1.68%   |
| 0      | 2         | 1.12%   |
| 6      | 1         | 0.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 119       | 68%     |
| Yes       | 56        | 32%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 147       | 84%     |
| No        | 28        | 16%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 142       | 80.68%  |
| No        | 34        | 19.32%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 122       | 69.71%  |
| No        | 53        | 30.29%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Computers | Percent |
|------------|-----------|---------|
| Luxembourg | 175       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Luxembourg        | 108       | 57.45%  |
| Strassen          | 10        | 5.32%   |
| Schieren          | 8         | 4.26%   |
| Esch-sur-Alzette  | 4         | 2.13%   |
| Useldange         | 3         | 1.6%    |
| Schifflange       | 3         | 1.6%    |
| Ehnen             | 3         | 1.6%    |
| Differdange       | 3         | 1.6%    |
| Wormeldange       | 2         | 1.06%   |
| Steinfort         | 2         | 1.06%   |
| Sanem             | 2         | 1.06%   |
| Dudelange         | 2         | 1.06%   |
| Clervaux          | 2         | 1.06%   |
| Bettange-sur-Mess | 2         | 1.06%   |
| Wiltz             | 1         | 0.53%   |
| Wecker            | 1         | 0.53%   |
| Wasserbillig      | 1         | 0.53%   |
| Vianden           | 1         | 0.53%   |
| Tetange           | 1         | 0.53%   |
| Steinsel          | 1         | 0.53%   |
| Soleuvre          | 1         | 0.53%   |
| Sandweiler        | 1         | 0.53%   |
| Roeser            | 1         | 0.53%   |
| Remich            | 1         | 0.53%   |
| Pontpierre        | 1         | 0.53%   |
| Pétange          | 1         | 0.53%   |
| PerlГ©          | 1         | 0.53%   |
| Oberpallen        | 1         | 0.53%   |
| Niederanven       | 1         | 0.53%   |
| Leudelange        | 1         | 0.53%   |
| Kopstal           | 1         | 0.53%   |
| Junglinster       | 1         | 0.53%   |
| Itzig             | 1         | 0.53%   |
| Hunsdorf          | 1         | 0.53%   |
| Hosingen          | 1         | 0.53%   |
| Hesperange        | 1         | 0.53%   |
| Frisange          | 1         | 0.53%   |
| Ettelbruck        | 1         | 0.53%   |
| Esch-sur-Sûre    | 1         | 0.53%   |
| Echternach        | 1         | 0.53%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 68        | 105    | 25.56%  |
| Seagate                      | 33        | 46     | 12.41%  |
| WDC                          | 29        | 44     | 10.9%   |
| SanDisk                      | 17        | 23     | 6.39%   |
| Crucial                      | 17        | 26     | 6.39%   |
| Toshiba                      | 14        | 17     | 5.26%   |
| Kingston                     | 13        | 18     | 4.89%   |
| SK hynix                     | 9         | 9      | 3.38%   |
| Intel                        | 5         | 6      | 1.88%   |
| Apple                        | 5         | 6      | 1.88%   |
| LITEON                       | 4         | 4      | 1.5%    |
| Hitachi                      | 4         | 6      | 1.5%    |
| HGST                         | 4         | 6      | 1.5%    |
| Transcend                    | 2         | 2      | 0.75%   |
| Shenzhen Longsys Electronics | 2         | 2      | 0.75%   |
| Phison                       | 2         | 2      | 0.75%   |
| Micron Technology            | 2         | 3      | 0.75%   |
| LITEONIT                     | 2         | 2      | 0.75%   |
| Lenovo                       | 2         | 5      | 0.75%   |
| Kingston Technology Company  | 2         | 3      | 0.75%   |
| KingSpec                     | 2         | 3      | 0.75%   |
| Intenso                      | 2         | 3      | 0.75%   |
| A-DATA Technology            | 2         | 2      | 0.75%   |
| Yangtze Memory Technologies  | 1         | 2      | 0.38%   |
| WDC WUH                      | 1         | 1      | 0.38%   |
| Unknown                      | 1         | 2      | 0.38%   |
| Union Memory (Shenzhen)      | 1         | 1      | 0.38%   |
| TCSUNBOW                     | 1         | 1      | 0.38%   |
| Super Talent                 | 1         | 1      | 0.38%   |
| StarTech                     | 1         | 2      | 0.38%   |
| SABRENT                      | 1         | 1      | 0.38%   |
| PNY                          | 1         | 1      | 0.38%   |
| Phison Electronics           | 1         | 1      | 0.38%   |
| PHD 3.0                      | 1         | 1      | 0.38%   |
| OCZ                          | 1         | 1      | 0.38%   |
| NT-128                       | 1         | 1      | 0.38%   |
| Micron/Crucial Technology    | 1         | 1      | 0.38%   |
| Maxtor                       | 1         | 2      | 0.38%   |
| MAXIO Technology (Hangzhou)  | 1         | 4      | 0.38%   |
| LaCie                        | 1         | 1      | 0.38%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 5         | 1.63%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 5         | 1.63%   |
| Seagate Expansion 1TB                                | 4         | 1.3%    |
| Samsung SSD 840 EVO 250GB                            | 4         | 1.3%    |
| WDC WD10JPVX-22JC3T0 1TB                             | 3         | 0.98%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB     | 3         | 0.98%   |
| Samsung SSD 860 EVO 250GB                            | 3         | 0.98%   |
| Samsung SSD 750 EVO 500GB                            | 3         | 0.98%   |
| Kingston SA400S37240G 240GB SSD                      | 3         | 0.98%   |
| Crucial CT240BX500SSD1 240GB                         | 3         | 0.98%   |
| Crucial CT1000P2SSD8 1TB                             | 3         | 0.98%   |
| WDC WD10EZEX-08WN4A0 1TB                             | 2         | 0.65%   |
| WDC WD10EACS-00D6B1 1TB                              | 2         | 0.65%   |
| Toshiba MQ01ABF050 500GB                             | 2         | 0.65%   |
| Seagate ST4000DM004-2CV104 4TB                       | 2         | 0.65%   |
| Seagate ST2000DM008-2FR102 2TB                       | 2         | 0.65%   |
| Seagate ST1000LM035-1RK172 1TB                       | 2         | 0.65%   |
| Seagate ST1000DM003-1ER162 1TB                       | 2         | 0.65%   |
| SanDisk SDSSDH3512G 512GB                            | 2         | 0.65%   |
| SanDisk SD8SN8U128G1122 128GB SSD                    | 2         | 0.65%   |
| SanDisk NVMe SSD Drive 1TB                           | 2         | 0.65%   |
| Samsung SSD 870 EVO 1TB                              | 2         | 0.65%   |
| Samsung SSD 860 QVO 2TB                              | 2         | 0.65%   |
| Samsung SSD 860 QVO 1TB                              | 2         | 0.65%   |
| Samsung SSD 850 EVO 250GB                            | 2         | 0.65%   |
| Samsung SP2504C 250GB                                | 2         | 0.65%   |
| Samsung MZVLW256HEHP-000L7 256GB                     | 2         | 0.65%   |
| LITEONIT LMT-256L9M-11 MSATA 256GB SSD               | 2         | 0.65%   |
| Kingston Company SNV2S1000G 1TB                      | 2         | 0.65%   |
| Kingston SA400S37480G 480GB SSD                      | 2         | 0.65%   |
| Kingston SA400S37120G 120GB SSD                      | 2         | 0.65%   |
| Crucial CT1000MX500SSD1 1TB                          | 2         | 0.65%   |
| Yangtze Memory ZHITAI TiPlus5000 1TB                 | 1         | 0.33%   |
| WDC WUH721818ALE6L4 18TB                             | 1         | 0.33%   |
| WDC WUH 721818ALE6L4 18TB                            | 1         | 0.33%   |
| WDC WDS500G3X0C-00SJG0 500GB                         | 1         | 0.33%   |
| WDC WDS250G2B0B-00YS70 250GB SSD                     | 1         | 0.33%   |
| WDC WDS250G2B0A-00SM50 250GB SSD                     | 1         | 0.33%   |
| WDC WDS200T1X0E-00AFY0 2TB                           | 1         | 0.33%   |
| WDC WDS100T2G0A-00JH30 1TB SSD                       | 1         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 31        | 44     | 40.79%  |
| WDC                 | 20        | 35     | 26.32%  |
| Toshiba             | 8         | 11     | 10.53%  |
| Hitachi             | 4         | 6      | 5.26%   |
| HGST                | 4         | 6      | 5.26%   |
| Samsung Electronics | 3         | 3      | 3.95%   |
| Apple               | 2         | 2      | 2.63%   |
| SABRENT             | 1         | 1      | 1.32%   |
| Intenso             | 1         | 1      | 1.32%   |
| Inateck             | 1         | 1      | 1.32%   |
| ASMT                | 1         | 4      | 1.32%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 38        | 53     | 37.25%  |
| Crucial             | 13        | 22     | 12.75%  |
| SanDisk             | 11        | 14     | 10.78%  |
| Kingston            | 7         | 11     | 6.86%   |
| LITEON              | 4         | 4      | 3.92%   |
| WDC                 | 3         | 3      | 2.94%   |
| Transcend           | 2         | 2      | 1.96%   |
| Toshiba             | 2         | 2      | 1.96%   |
| Micron Technology   | 2         | 3      | 1.96%   |
| LITEONIT            | 2         | 2      | 1.96%   |
| KingSpec            | 2         | 3      | 1.96%   |
| Intel               | 2         | 2      | 1.96%   |
| TCSUNBOW            | 1         | 1      | 0.98%   |
| Super Talent        | 1         | 1      | 0.98%   |
| SK hynix            | 1         | 1      | 0.98%   |
| PNY                 | 1         | 1      | 0.98%   |
| PHD 3.0             | 1         | 1      | 0.98%   |
| OCZ                 | 1         | 1      | 0.98%   |
| NT-128              | 1         | 1      | 0.98%   |
| Maxtor              | 1         | 2      | 0.98%   |
| Lenovo              | 1         | 3      | 0.98%   |
| KingDian            | 1         | 1      | 0.98%   |
| Intenso             | 1         | 2      | 0.98%   |
| FORESEE             | 1         | 1      | 0.98%   |
| Apple               | 1         | 1      | 0.98%   |
| A-DATA Technology   | 1         | 1      | 0.98%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 84        | 113    | 34.71%  |
| SSD     | 84        | 139    | 34.71%  |
| HDD     | 65        | 114    | 26.86%  |
| Unknown | 6         | 7      | 2.48%   |
| MMC     | 3         | 4      | 1.24%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 117       | 231    | 52.7%   |
| NVMe | 84        | 112    | 37.84%  |
| SAS  | 18        | 30     | 8.11%   |
| MMC  | 3         | 4      | 1.35%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 83        | 130    | 49.11%  |
| 0.51-1.0   | 56        | 82     | 33.14%  |
| 1.01-2.0   | 14        | 23     | 8.28%   |
| 3.01-4.0   | 10        | 10     | 5.92%   |
| 10.01-20.0 | 3         | 3      | 1.78%   |
| 2.01-3.0   | 2         | 3      | 1.18%   |
| 4.01-10.0  | 1         | 2      | 0.59%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 42        | 22.46%  |
| 251-500        | 39        | 20.86%  |
| 501-1000       | 26        | 13.9%   |
| 1001-2000      | 21        | 11.23%  |
| More than 3000 | 19        | 10.16%  |
| Unknown        | 12        | 6.42%   |
| 51-100         | 10        | 5.35%   |
| 1-20           | 9         | 4.81%   |
| 2001-3000      | 7         | 3.74%   |
| 21-50          | 2         | 1.07%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 63        | 33.87%  |
| 21-50          | 27        | 14.52%  |
| 101-250        | 23        | 12.37%  |
| 251-500        | 17        | 9.14%   |
| 51-100         | 15        | 8.06%   |
| Unknown        | 12        | 6.45%   |
| 501-1000       | 11        | 5.91%   |
| 1001-2000      | 8         | 4.3%    |
| 2001-3000      | 6         | 3.23%   |
| More than 3000 | 4         | 2.15%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                      | Computers | Drives | Percent |
|--------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABF050 500GB                   | 2         | 2      | 18.18%  |
| Toshiba MK2555GSX 250GB                    | 1         | 1      | 9.09%   |
| SK hynix HFS128G39TND-N210A 128GB SSD      | 1         | 1      | 9.09%   |
| Seagate ST500LM021-1KJ152 500GB            | 1         | 1      | 9.09%   |
| Seagate ST1000LM049-2GH172 1TB             | 1         | 1      | 9.09%   |
| Seagate ST1000DM003-1ER162 1TB             | 1         | 1      | 9.09%   |
| Samsung Electronics SSD 870 EVO 1TB        | 1         | 1      | 9.09%   |
| Samsung Electronics MZVLQ1T0HBLB-00B00 1TB | 1         | 1      | 9.09%   |
| Hitachi HTS543232A7A384 320GB              | 1         | 1      | 9.09%   |
| Crucial CT128MX100SSD1 128GB               | 1         | 2      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 3         | 3      | 27.27%  |
| Seagate             | 3         | 3      | 27.27%  |
| Samsung Electronics | 2         | 2      | 18.18%  |
| SK hynix            | 1         | 1      | 9.09%   |
| Hitachi             | 1         | 1      | 9.09%   |
| Crucial             | 1         | 2      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 3         | 3      | 42.86%  |
| Seagate | 3         | 3      | 42.86%  |
| Hitachi | 1         | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 7         | 7      | 63.64%  |
| SSD  | 3         | 4      | 27.27%  |
| NVMe | 1         | 1      | 9.09%   |

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
| Detected | 94        | 205    | 48.45%  |
| Works    | 90        | 160    | 46.39%  |
| Malfunc  | 10        | 12     | 5.15%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 115       | 49.15%  |
| Samsung Electronics          | 34        | 14.53%  |
| AMD                          | 26        | 11.11%  |
| SanDisk                      | 14        | 5.98%   |
| Kingston Technology Company  | 8         | 3.42%   |
| SK hynix                     | 7         | 2.99%   |
| Micron/Crucial Technology    | 5         | 2.14%   |
| Marvell Technology Group     | 5         | 2.14%   |
| Toshiba America Info Systems | 4         | 1.71%   |
| Phison Electronics           | 4         | 1.71%   |
| Shenzhen Longsys Electronics | 2         | 0.85%   |
| ASMedia Technology           | 2         | 0.85%   |
| Apple                        | 2         | 0.85%   |
| Yangtze Memory Technologies  | 1         | 0.43%   |
| Union Memory (Shenzhen)      | 1         | 0.43%   |
| Seagate Technology           | 1         | 0.43%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.43%   |
| Lenovo                       | 1         | 0.43%   |
| ADATA Technology             | 1         | 0.43%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 19        | 7.45%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 15        | 5.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 13        | 5.1%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 12        | 4.71%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 9         | 3.53%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 8         | 3.14%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 7         | 2.75%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 6         | 2.35%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 6         | 2.35%   |
| Intel Volume Management Device NVMe RAID Controller                            | 6         | 2.35%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 2.35%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 6         | 2.35%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 5         | 1.96%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 5         | 1.96%   |
| AMD 400 Series Chipset SATA Controller                                         | 5         | 1.96%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 4         | 1.57%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 4         | 1.57%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 4         | 1.57%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 4         | 1.57%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 3         | 1.18%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 3         | 1.18%   |
| Phison E12 NVMe Controller                                                     | 3         | 1.18%   |
| Intel SATA Controller [RAID mode]                                              | 3         | 1.18%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 1.18%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 1.18%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 3         | 1.18%   |
| AMD 500 Series Chipset SATA Controller                                         | 3         | 1.18%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 0.78%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 2         | 0.78%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 2         | 0.78%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 2         | 0.78%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                      | 2         | 0.78%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                           | 2         | 0.78%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 2         | 0.78%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 0.78%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 0.78%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 2         | 0.78%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 2         | 0.78%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 0.78%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 2         | 0.78%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 121       | 52.38%  |
| NVMe | 85        | 36.8%   |
| RAID | 16        | 6.93%   |
| IDE  | 9         | 3.9%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 138       | 78.86%  |
| AMD    | 37        | 21.14%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 5         | 2.86%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 2.29%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 1.71%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 1.71%   |
| AMD Ryzen 5 3600 6-Core Processor             | 3         | 1.71%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 1.14%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 2         | 1.14%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 1.14%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 1.14%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 2         | 1.14%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 2         | 1.14%   |
| Intel Core i7-4702HQ CPU @ 2.20GHz            | 2         | 1.14%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.14%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 1.14%   |
| Intel Core i5-7500 CPU @ 3.40GHz              | 2         | 1.14%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 1.14%   |
| Intel Core i5-4590S CPU @ 3.00GHz             | 2         | 1.14%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 2         | 1.14%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 1.14%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 2         | 1.14%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 2         | 1.14%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 1.14%   |
| Intel 12th Gen Core i7-12700H                 | 2         | 1.14%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 2         | 1.14%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 2         | 1.14%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 2         | 1.14%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 2         | 1.14%   |
| Intel Xeon Gold 6154 CPU @ 3.00GHz            | 1         | 0.57%   |
| Intel Xeon CPU X5690 @ 3.47GHz                | 1         | 0.57%   |
| Intel Xeon CPU E5-2698 v3 @ 2.30GHz           | 1         | 0.57%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.57%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 0.57%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 0.57%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 1         | 0.57%   |
| Intel Pentium CPU P6000 @ 1.87GHz             | 1         | 0.57%   |
| Intel Pentium CPU G4560T @ 2.90GHz            | 1         | 0.57%   |
| Intel Pentium CPU G4560 @ 3.50GHz             | 1         | 0.57%   |
| Intel Pentium CPU G3250 @ 3.20GHz             | 1         | 0.57%   |
| Intel Pentium CPU 987 @ 1.50GHz               | 1         | 0.57%   |
| Intel N100                                    | 1         | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 43        | 24.57%  |
| Intel Core i5           | 37        | 21.14%  |
| Other                   | 19        | 10.86%  |
| AMD Ryzen 5             | 14        | 8%      |
| Intel Core i3           | 10        | 5.71%   |
| AMD Ryzen 7             | 10        | 5.71%   |
| Intel Pentium           | 5         | 2.86%   |
| Intel Celeron           | 5         | 2.86%   |
| AMD Ryzen 9             | 5         | 2.86%   |
| Intel Pentium Dual-Core | 3         | 1.71%   |
| Intel Core 2 Quad       | 3         | 1.71%   |
| AMD Ryzen 7 PRO         | 3         | 1.71%   |
| Intel Xeon              | 2         | 1.14%   |
| Intel Core i9           | 2         | 1.14%   |
| Intel Atom              | 2         | 1.14%   |
| AMD Ryzen 5 PRO         | 2         | 1.14%   |
| Intel Xeon Gold         | 1         | 0.57%   |
| Intel Pentium Silver    | 1         | 0.57%   |
| Intel Core m5           | 1         | 0.57%   |
| Intel Core m3           | 1         | 0.57%   |
| Intel Core M            | 1         | 0.57%   |
| Intel Core 2 Duo        | 1         | 0.57%   |
| Intel Core 2            | 1         | 0.57%   |
| AMD Phenom II X4        | 1         | 0.57%   |
| AMD FX                  | 1         | 0.57%   |
| AMD E2                  | 1         | 0.57%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 62        | 35.43%  |
| 2      | 51        | 29.14%  |
| 6      | 25        | 14.29%  |
| 8      | 21        | 12%     |
| 16     | 5         | 2.86%   |
| 12     | 3         | 1.71%   |
| 14     | 2         | 1.14%   |
| 1      | 2         | 1.14%   |
| 36     | 1         | 0.57%   |
| 32     | 1         | 0.57%   |
| 24     | 1         | 0.57%   |
| 10     | 1         | 0.57%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 173       | 98.86%  |
| 2      | 2         | 1.14%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 140       | 80%     |
| 1      | 35        | 20%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 174       | 99.43%  |
| 32-bit         | 1         | 0.57%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 62        | 34.44%  |
| 0x306c3    | 14        | 7.78%   |
| 0x906e9    | 6         | 3.33%   |
| 0x806ea    | 5         | 2.78%   |
| 0x806c1    | 5         | 2.78%   |
| 0x406e3    | 5         | 2.78%   |
| 0x40651    | 5         | 2.78%   |
| 0x206a7    | 5         | 2.78%   |
| 0x20655    | 4         | 2.22%   |
| 0x1067a    | 4         | 2.22%   |
| 0x906ea    | 3         | 1.67%   |
| 0x806eb    | 3         | 1.67%   |
| 0x706a1    | 3         | 1.67%   |
| 0x506e3    | 3         | 1.67%   |
| 0x306d4    | 3         | 1.67%   |
| 0x08701013 | 3         | 1.67%   |
| 0xa0655    | 2         | 1.11%   |
| 0x906ed    | 2         | 1.11%   |
| 0x806ec    | 2         | 1.11%   |
| 0x806d1    | 2         | 1.11%   |
| 0x306a9    | 2         | 1.11%   |
| 0x10677    | 2         | 1.11%   |
| 0x0a50000c | 2         | 1.11%   |
| 0x0a20120a | 2         | 1.11%   |
| 0x08701021 | 2         | 1.11%   |
| 0x08600106 | 2         | 1.11%   |
| 0x08600103 | 2         | 1.11%   |
| 0x08108102 | 2         | 1.11%   |
| 0xb06e0    | 1         | 0.56%   |
| 0xa0671    | 1         | 0.56%   |
| 0xa0653    | 1         | 0.56%   |
| 0x906c0    | 1         | 0.56%   |
| 0x806e9    | 1         | 0.56%   |
| 0x6fb      | 1         | 0.56%   |
| 0x6f6      | 1         | 0.56%   |
| 0x50654    | 1         | 0.56%   |
| 0x406f1    | 1         | 0.56%   |
| 0x406c4    | 1         | 0.56%   |
| 0x20652    | 1         | 0.56%   |
| 0x106c2    | 1         | 0.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 36        | 20.57%  |
| Haswell          | 24        | 13.71%  |
| Zen 2            | 14        | 8%      |
| Skylake          | 13        | 7.43%   |
| Unknown          | 11        | 6.29%   |
| Zen 3            | 10        | 5.71%   |
| TigerLake        | 7         | 4%      |
| SandyBridge      | 7         | 4%      |
| Westmere         | 6         | 3.43%   |
| Penryn           | 6         | 3.43%   |
| IvyBridge        | 6         | 3.43%   |
| Broadwell        | 6         | 3.43%   |
| Alderlake Hybrid | 6         | 3.43%   |
| CometLake        | 5         | 2.86%   |
| Zen+             | 3         | 1.71%   |
| Icelake          | 3         | 1.71%   |
| Goldmont plus    | 3         | 1.71%   |
| Core             | 2         | 1.14%   |
| Zen              | 1         | 0.57%   |
| Silvermont       | 1         | 0.57%   |
| Piledriver       | 1         | 0.57%   |
| K10              | 1         | 0.57%   |
| Goldmont         | 1         | 0.57%   |
| Excavator        | 1         | 0.57%   |
| Bonnell          | 1         | 0.57%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 115       | 53.49%  |
| Nvidia | 61        | 28.37%  |
| AMD    | 39        | 18.14%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                      | 8         | 3.62%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 8         | 3.62%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 7         | 3.17%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                 | 7         | 3.17%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 7         | 3.17%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 6         | 2.71%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 6         | 2.71%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 6         | 2.71%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6         | 2.71%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 5         | 2.26%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 5         | 2.26%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 4         | 1.81%   |
| Intel HD Graphics 530                                                       | 4         | 1.81%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 3         | 1.36%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 3         | 1.36%   |
| Nvidia GA107GLM [RTX A1000 Laptop GPU]                                      | 3         | 1.36%   |
| Intel HD Graphics 630                                                       | 3         | 1.36%   |
| Intel HD Graphics 5500                                                      | 3         | 1.36%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 3         | 1.36%   |
| Intel Alder Lake-HX GT1 [UHD Graphics 770]                                  | 3         | 1.36%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 3         | 1.36%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 2         | 0.9%    |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                       | 2         | 0.9%    |
| Nvidia GP108M [GeForce MX250]                                               | 2         | 0.9%    |
| Nvidia GP108M [GeForce MX150]                                               | 2         | 0.9%    |
| Nvidia GP108 [GeForce GT 1030]                                              | 2         | 0.9%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2         | 0.9%    |
| Nvidia GM204 [GeForce GTX 970]                                              | 2         | 0.9%    |
| Nvidia GK107GLM [Quadro K1100M]                                             | 2         | 0.9%    |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 2         | 0.9%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 2         | 0.9%    |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 2         | 0.9%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 2         | 0.9%    |
| Intel Iris Plus Graphics 640                                                | 2         | 0.9%    |
| Intel HD Graphics 620                                                       | 2         | 0.9%    |
| Intel HD Graphics 515                                                       | 2         | 0.9%    |
| Intel GeminiLake [UHD Graphics 600]                                         | 2         | 0.9%    |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 2         | 0.9%    |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                   | 2         | 0.9%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2         | 0.9%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 77        | 43.5%   |
| Intel + Nvidia | 31        | 17.51%  |
| 1 x AMD        | 31        | 17.51%  |
| 1 x Nvidia     | 28        | 15.82%  |
| 2 x AMD        | 4         | 2.26%   |
| Intel + AMD    | 4         | 2.26%   |
| 2 x Nvidia     | 1         | 0.56%   |
| AMD + Nvidia   | 1         | 0.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 135       | 76.7%   |
| Proprietary | 34        | 19.32%  |
| Unknown     | 7         | 3.98%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 111       | 62.36%  |
| 3.01-4.0   | 19        | 10.67%  |
| 0.01-0.5   | 14        | 7.87%   |
| 1.01-2.0   | 13        | 7.3%    |
| 0.51-1.0   | 10        | 5.62%   |
| 8.01-16.0  | 6         | 3.37%   |
| 5.01-6.0   | 3         | 1.69%   |
| 7.01-8.0   | 2         | 1.12%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 30        | 14.78%  |
| Chimei Innolux          | 22        | 10.84%  |
| LG Display              | 20        | 9.85%   |
| AU Optronics            | 15        | 7.39%   |
| BOE                     | 12        | 5.91%   |
| Hewlett-Packard         | 11        | 5.42%   |
| Dell                    | 10        | 4.93%   |
| Goldstar                | 9         | 4.43%   |
| AOC                     | 9         | 4.43%   |
| Sharp                   | 8         | 3.94%   |
| Iiyama                  | 7         | 3.45%   |
| Apple                   | 7         | 3.45%   |
| BenQ                    | 6         | 2.96%   |
| Philips                 | 5         | 2.46%   |
| Ancor Communications    | 5         | 2.46%   |
| Medion                  | 4         | 1.97%   |
| Eizo                    | 3         | 1.48%   |
| Chi Mei Optoelectronics | 3         | 1.48%   |
| CSO                     | 2         | 0.99%   |
| Acer                    | 2         | 0.99%   |
| ViewSonic               | 1         | 0.49%   |
| Videoseven              | 1         | 0.49%   |
| UGD                     | 1         | 0.49%   |
| Sony                    | 1         | 0.49%   |
| PAR                     | 1         | 0.49%   |
| PANDA                   | 1         | 0.49%   |
| Panasonic               | 1         | 0.49%   |
| MSI                     | 1         | 0.49%   |
| Lenovo                  | 1         | 0.49%   |
| Fujitsu Siemens         | 1         | 0.49%   |
| Belinea                 | 1         | 0.49%   |
| ASUSTek Computer        | 1         | 0.49%   |
| Aosiman                 | 1         | 0.49%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                 | 2         | 0.97%   |
| Sharp LCD Monitor SHP13F8 3200x1800 346x194mm 15.6-inch                 | 2         | 0.97%   |
| Samsung Electronics LCD Monitor SAM0B60 1920x1080 887x500mm 40.1-inch   | 2         | 0.97%   |
| Goldstar ULTRAGEAR GSM5BD3 2560x1440 697x392mm 31.5-inch                | 2         | 0.97%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch        | 2         | 0.97%   |
| Chimei Innolux LCD Monitor CMN1604 1920x1080 355x199mm 16.0-inch        | 2         | 0.97%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch        | 2         | 0.97%   |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch                  | 2         | 0.97%   |
| AOC 2250W AOC2250 1920x1080 477x268mm 21.5-inch                         | 2         | 0.97%   |
| ViewSonic VX2458 series VSC0437 1920x1080 521x293mm 23.5-inch           | 1         | 0.49%   |
| Videoseven L27ADS IGM2700 1920x1080 598x336mm 27.0-inch                 | 1         | 0.49%   |
| UGD Artist13.3pro UGD1302 1920x1080 294x165mm 13.3-inch                 | 1         | 0.49%   |
| Sony LCD Monitor SNY05FA 1366x768 310x170mm 13.9-inch                   | 1         | 0.49%   |
| Sharp LCD Monitor SHP1516 3840x2400 336x210mm 15.6-inch                 | 1         | 0.49%   |
| Sharp LCD Monitor SHP14AE 1920x1080 294x165mm 13.3-inch                 | 1         | 0.49%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch                 | 1         | 0.49%   |
| Sharp LCD Monitor SHP1421 3200x1800 294x165mm 13.3-inch                 | 1         | 0.49%   |
| Samsung Electronics U28H75x SAM0DFE 3840x2160 608x345mm 27.5-inch       | 1         | 0.49%   |
| Samsung Electronics T24B350 SAM093E 1920x1080 531x299mm 24.0-inch       | 1         | 0.49%   |
| Samsung Electronics SyncMaster SAM0612 1920x1080 604x342mm 27.3-inch    | 1         | 0.49%   |
| Samsung Electronics SyncMaster SAM04DF 1360x768 410x230mm 18.5-inch     | 1         | 0.49%   |
| Samsung Electronics SMT27A950 SAM080F 1920x1080 598x336mm 27.0-inch     | 1         | 0.49%   |
| Samsung Electronics SMS27A650 SAM082E 1920x1080 598x336mm 27.0-inch     | 1         | 0.49%   |
| Samsung Electronics SM2333T SAM0737 1920x1080 510x290mm 23.1-inch       | 1         | 0.49%   |
| Samsung Electronics S27D390 SAM0B67 1920x1080 598x336mm 27.0-inch       | 1         | 0.49%   |
| Samsung Electronics S27C750 SAM0A60 1920x1080 598x336mm 27.0-inch       | 1         | 0.49%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 1         | 0.49%   |
| Samsung Electronics Odyssey G70NC SAM7231 3840x2160 941x529mm 42.5-inch | 1         | 0.49%   |
| Samsung Electronics LF27T450F SAM7097 1920x1080 597x336mm 27.0-inch     | 1         | 0.49%   |
| Samsung Electronics LCD Monitor U28E590 3840x2160                       | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SEC444E 1600x900 310x174mm 14.0-inch    | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SDC5844 1920x1080 344x194mm 15.5-inch   | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch    | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch   | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SDC434A 3200x1800 293x165mm 13.2-inch   | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch    | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SDC4181 2880x1800 302x189mm 14.0-inch   | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch   | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SDC4159 1920x1080 344x194mm 15.5-inch   | 1         | 0.49%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 344x194mm 15.5-inch    | 1         | 0.49%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 93        | 50%     |
| 1366x768 (WXGA)    | 16        | 8.6%    |
| 3840x2160 (4K)     | 15        | 8.06%   |
| 2560x1440 (QHD)    | 13        | 6.99%   |
| 1920x1200 (WUXGA)  | 6         | 3.23%   |
| 1600x900 (HD+)     | 5         | 2.69%   |
| 3200x1800 (QHD+)   | 4         | 2.15%   |
| 2880x1800          | 4         | 2.15%   |
| 2560x1600          | 3         | 1.61%   |
| 1680x1050 (WSXGA+) | 3         | 1.61%   |
| 1440x900 (WXGA+)   | 3         | 1.61%   |
| 1280x800 (WXGA)    | 3         | 1.61%   |
| 3840x2400          | 2         | 1.08%   |
| 3840x1080          | 2         | 1.08%   |
| 2256x1504          | 2         | 1.08%   |
| 1360x768           | 2         | 1.08%   |
| 1280x1024 (SXGA)   | 2         | 1.08%   |
| 3440x1440          | 1         | 0.54%   |
| 3072x1920          | 1         | 0.54%   |
| 2560x2160          | 1         | 0.54%   |
| 2520x1680          | 1         | 0.54%   |
| 2160x1440          | 1         | 0.54%   |
| 1600x1200          | 1         | 0.54%   |
| 1024x768 (XGA)     | 1         | 0.54%   |
| Unknown            | 1         | 0.54%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 40        | 19.8%   |
| 27      | 27        | 13.37%  |
| 13      | 23        | 11.39%  |
| 14      | 20        | 9.9%    |
| 24      | 14        | 6.93%   |
| 23      | 14        | 6.93%   |
| 17      | 11        | 5.45%   |
| 21      | 9         | 4.46%   |
| 16      | 8         | 3.96%   |
| 31      | 5         | 2.48%   |
| Unknown | 5         | 2.48%   |
| 22      | 3         | 1.49%   |
| 18      | 3         | 1.49%   |
| 72      | 2         | 0.99%   |
| 47      | 2         | 0.99%   |
| 34      | 2         | 0.99%   |
| 32      | 2         | 0.99%   |
| 19      | 2         | 0.99%   |
| 59      | 1         | 0.5%    |
| 49      | 1         | 0.5%    |
| 46      | 1         | 0.5%    |
| 42      | 1         | 0.5%    |
| 40      | 1         | 0.5%    |
| 33      | 1         | 0.5%    |
| 28      | 1         | 0.5%    |
| 25      | 1         | 0.5%    |
| 20      | 1         | 0.5%    |
| 11      | 1         | 0.5%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 72        | 36.92%  |
| 501-600     | 48        | 24.62%  |
| 201-300     | 18        | 9.23%   |
| 401-500     | 16        | 8.21%   |
| 351-400     | 14        | 7.18%   |
| 601-700     | 8         | 4.1%    |
| 701-800     | 5         | 2.56%   |
| 1001-1500   | 5         | 2.56%   |
| Unknown     | 5         | 2.56%   |
| 1501-2000   | 2         | 1.03%   |
| 801-900     | 1         | 0.51%   |
| 901-1000    | 1         | 0.51%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 136       | 76.84%  |
| 16/10   | 27        | 15.25%  |
| 3/2     | 4         | 2.26%   |
| Unknown | 3         | 1.69%   |
| 5/4     | 2         | 1.13%   |
| 4/3     | 2         | 1.13%   |
| 21/9    | 2         | 1.13%   |
| 32/9    | 1         | 0.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 40        | 19.9%   |
| 201-250        | 35        | 17.41%  |
| 81-90          | 32        | 15.92%  |
| 301-350        | 27        | 13.43%  |
| 71-80          | 11        | 5.47%   |
| 351-500        | 11        | 5.47%   |
| 121-130        | 8         | 3.98%   |
| 111-120        | 7         | 3.48%   |
| 501-1000       | 6         | 2.99%   |
| 251-300        | 5         | 2.49%   |
| Unknown        | 5         | 2.49%   |
| 141-150        | 4         | 1.99%   |
| More than 1000 | 3         | 1.49%   |
| 151-200        | 3         | 1.49%   |
| 131-140        | 2         | 1%      |
| 51-60          | 1         | 0.5%    |
| 91-100         | 1         | 0.5%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 63        | 32.47%  |
| 121-160       | 51        | 26.29%  |
| 101-120       | 37        | 19.07%  |
| 161-240       | 22        | 11.34%  |
| More than 240 | 11        | 5.67%   |
| 1-50          | 5         | 2.58%   |
| Unknown       | 5         | 2.58%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 136       | 76.4%   |
| 2     | 32        | 17.98%  |
| 0     | 7         | 3.93%   |
| 3     | 3         | 1.69%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 112       | 43.58%  |
| Realtek Semiconductor           | 76        | 29.57%  |
| Qualcomm Atheros                | 24        | 9.34%   |
| Broadcom                        | 15        | 5.84%   |
| MediaTek                        | 6         | 2.33%   |
| Marvell Technology Group        | 5         | 1.95%   |
| Sierra Wireless                 | 3         | 1.17%   |
| Broadcom Limited                | 3         | 1.17%   |
| DisplayLink                     | 2         | 0.78%   |
| TP-Link                         | 1         | 0.39%   |
| Shenzhen Goodix Technology      | 1         | 0.39%   |
| Ralink Technology               | 1         | 0.39%   |
| Qualcomm Atheros Communications | 1         | 0.39%   |
| Mellanox Technologies           | 1         | 0.39%   |
| Lenovo                          | 1         | 0.39%   |
| JMicron Technology              | 1         | 0.39%   |
| Huawei Technologies             | 1         | 0.39%   |
| D-Link                          | 1         | 0.39%   |
| ASIX Electronics                | 1         | 0.39%   |
| Unknown                         | 1         | 0.39%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 54        | 17.2%   |
| Intel Wi-Fi 6 AX200                                                            | 18        | 5.73%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 8         | 2.55%   |
| Realtek RTL8125 2.5GbE Controller                                              | 8         | 2.55%   |
| Intel Wireless 8265 / 8275                                                     | 8         | 2.55%   |
| Intel I211 Gigabit Network Connection                                          | 7         | 2.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 5         | 1.59%   |
| Intel Wireless 8260                                                            | 5         | 1.59%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                      | 5         | 1.59%   |
| Intel Ethernet Controller I225-V                                               | 5         | 1.59%   |
| Intel Ethernet Connection (2) I219-V                                           | 5         | 1.59%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 5         | 1.59%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 4         | 1.27%   |
| Intel Wireless 7260                                                            | 4         | 1.27%   |
| Intel Alder Lake-S PCH CNVi WiFi                                               | 4         | 1.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 4         | 1.27%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 3         | 0.96%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 3         | 0.96%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 3         | 0.96%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                  | 3         | 0.96%   |
| Intel Wireless 7265                                                            | 3         | 0.96%   |
| Intel Wireless 3160                                                            | 3         | 0.96%   |
| Intel Ethernet Connection I219-V                                               | 3         | 0.96%   |
| Intel Ethernet Connection I217-LM                                              | 3         | 0.96%   |
| Intel Ethernet Connection (4) I219-V                                           | 3         | 0.96%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 3         | 0.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 3         | 0.96%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 3         | 0.96%   |
| Broadcom BCM4331 802.11a/b/g/n                                                 | 3         | 0.96%   |
| Sierra Wireless EM7305 Modem                                                   | 2         | 0.64%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                       | 2         | 0.64%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 2         | 0.64%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 2         | 0.64%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 2         | 0.64%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                  | 2         | 0.64%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.64%   |
| Intel Wireless 3165                                                            | 2         | 0.64%   |
| Intel Wi-Fi 6 AX201                                                            | 2         | 0.64%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                        | 2         | 0.64%   |
| Intel Tiger Lake PCH CNVi WiFi                                                 | 2         | 0.64%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 87        | 58.39%  |
| Qualcomm Atheros                | 19        | 12.75%  |
| Realtek Semiconductor           | 15        | 10.07%  |
| Broadcom                        | 12        | 8.05%   |
| MediaTek                        | 5         | 3.36%   |
| Sierra Wireless                 | 3         | 2.01%   |
| Broadcom Limited                | 3         | 2.01%   |
| TP-Link                         | 1         | 0.67%   |
| Ralink Technology               | 1         | 0.67%   |
| Qualcomm Atheros Communications | 1         | 0.67%   |
| Marvell Technology Group        | 1         | 0.67%   |
| D-Link                          | 1         | 0.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 18        | 12.08%  |
| Intel Wireless 8265 / 8275                                           | 8         | 5.37%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 5         | 3.36%   |
| Intel Wireless 8260                                                  | 5         | 3.36%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 5         | 3.36%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 5         | 3.36%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 4         | 2.68%   |
| Intel Wireless 7260                                                  | 4         | 2.68%   |
| Intel Alder Lake-S PCH CNVi WiFi                                     | 4         | 2.68%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 3         | 2.01%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 3         | 2.01%   |
| Intel Wireless 7265                                                  | 3         | 2.01%   |
| Intel Wireless 3160                                                  | 3         | 2.01%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 3         | 2.01%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 3         | 2.01%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 3         | 2.01%   |
| Sierra Wireless EM7305 Modem                                         | 2         | 1.34%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 2         | 1.34%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 2         | 1.34%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)       | 2         | 1.34%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 2         | 1.34%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 2         | 1.34%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 2         | 1.34%   |
| Intel Wireless 3165                                                  | 2         | 1.34%   |
| Intel Wi-Fi 6 AX201                                                  | 2         | 1.34%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 2         | 1.34%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 2         | 1.34%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                        | 2         | 1.34%   |
| Intel Centrino Advanced-N 6235                                       | 2         | 1.34%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 2         | 1.34%   |
| Broadcom Limited BCM4352 802.11ac Dual Band Wireless Network Adapter | 2         | 1.34%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter         | 2         | 1.34%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 2         | 1.34%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 1         | 0.67%   |
| Sierra Wireless EM7455                                               | 1         | 0.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 1         | 0.67%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 1         | 0.67%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                      | 1         | 0.67%   |
| Realtek RTL8191SEvB Wireless LAN Controller                          | 1         | 0.67%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 1         | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 72        | 46.15%  |
| Intel                    | 58        | 37.18%  |
| Qualcomm Atheros         | 8         | 5.13%   |
| Broadcom                 | 7         | 4.49%   |
| Marvell Technology Group | 4         | 2.56%   |
| DisplayLink              | 2         | 1.28%   |
| Mellanox Technologies    | 1         | 0.64%   |
| MediaTek                 | 1         | 0.64%   |
| Lenovo                   | 1         | 0.64%   |
| JMicron Technology       | 1         | 0.64%   |
| ASIX Electronics         | 1         | 0.64%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 54        | 33.54%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 8         | 4.97%   |
| Realtek RTL8125 2.5GbE Controller                                              | 8         | 4.97%   |
| Intel I211 Gigabit Network Connection                                          | 7         | 4.35%   |
| Intel Ethernet Controller I225-V                                               | 5         | 3.11%   |
| Intel Ethernet Connection (2) I219-V                                           | 5         | 3.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 4         | 2.48%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 3         | 1.86%   |
| Intel Ethernet Connection I219-V                                               | 3         | 1.86%   |
| Intel Ethernet Connection I217-LM                                              | 3         | 1.86%   |
| Intel Ethernet Connection (4) I219-V                                           | 3         | 1.86%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 3         | 1.86%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 1.24%   |
| Intel Ethernet Connection I217-V                                               | 2         | 1.24%   |
| Intel Ethernet Connection (7) I219-LM                                          | 2         | 1.24%   |
| Intel Ethernet Connection (6) I219-V                                           | 2         | 1.24%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 1.24%   |
| Intel Ethernet Connection (2) I218-V                                           | 2         | 1.24%   |
| Intel Ethernet Connection (17) I219-LM                                         | 2         | 1.24%   |
| DisplayLink Dell D3100 Docking Station                                         | 2         | 1.24%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1         | 0.62%   |
| Realtek Killer E2600 GbE Controller                                            | 1         | 0.62%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.62%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.62%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.62%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.62%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 0.62%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.62%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.62%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.62%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]                          | 1         | 0.62%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                  | 1         | 0.62%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 1         | 0.62%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 0.62%   |
| Lenovo ThinkPad Lan                                                            | 1         | 0.62%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 0.62%   |
| Intel WiMAX Connection 2400m                                                   | 1         | 0.62%   |
| Intel I350 Gigabit Network Connection                                          | 1         | 0.62%   |
| Intel I210 Gigabit Network Connection                                          | 1         | 0.62%   |
| Intel Ethernet controller                                                      | 1         | 0.62%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 145       | 49.66%  |
| WiFi     | 143       | 48.97%  |
| Modem    | 2         | 0.68%   |
| Unknown  | 2         | 0.68%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 101       | 54.89%  |
| Ethernet | 83        | 45.11%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 101       | 57.71%  |
| 1     | 66        | 37.71%  |
| 3     | 7         | 4%      |
| 5     | 1         | 0.57%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 128       | 71.91%  |
| Yes  | 50        | 28.09%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 78        | 62.9%   |
| Foxconn / Hon Hai               | 9         | 7.26%   |
| Qualcomm Atheros Communications | 5         | 4.03%   |
| Apple                           | 5         | 4.03%   |
| Realtek Semiconductor           | 4         | 3.23%   |
| IMC Networks                    | 4         | 3.23%   |
| Cambridge Silicon Radio         | 4         | 3.23%   |
| Realtek                         | 3         | 2.42%   |
| Lite-On Technology              | 3         | 2.42%   |
| MediaTek                        | 2         | 1.61%   |
| Hewlett-Packard                 | 2         | 1.61%   |
| Toshiba                         | 1         | 0.81%   |
| Micro Star International        | 1         | 0.81%   |
| Marvell Semiconductor           | 1         | 0.81%   |
| Broadcom                        | 1         | 0.81%   |
| ASUSTek Computer                | 1         | 0.81%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 24        | 19.35%  |
| Intel AX200 Bluetooth                                                               | 16        | 12.9%   |
| Intel AX201 Bluetooth                                                               | 9         | 7.26%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 8         | 6.45%   |
| Intel AX211 Bluetooth                                                               | 7         | 5.65%   |
| Intel AX210 Bluetooth                                                               | 5         | 4.03%   |
| Realtek Bluetooth Radio                                                             | 4         | 3.23%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 4         | 3.23%   |
| Realtek Bluetooth Radio                                                             | 3         | 2.42%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 3         | 2.42%   |
| Lite-On Bluetooth Device                                                            | 3         | 2.42%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 2.42%   |
| Apple Bluetooth USB Host Controller                                                 | 3         | 2.42%   |
| MediaTek Wireless_Device                                                            | 2         | 1.61%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 1.61%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 2         | 1.61%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 1.61%   |
| Apple Bluetooth Host Controller                                                     | 2         | 1.61%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.81%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.81%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 0.81%   |
| Micro Star International Motorola Bluetooth 2.1+EDR Device                          | 1         | 0.81%   |
| Marvell Bluetooth and Wireless LAN Composite                                        | 1         | 0.81%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.81%   |
| Intel Bluetooth Device                                                              | 1         | 0.81%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.81%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 0.81%   |
| IMC Networks Bluetooth Module                                                       | 1         | 0.81%   |
| IMC Networks Bluetooth Device                                                       | 1         | 0.81%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 1         | 0.81%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 1         | 0.81%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.81%   |
| Foxconn / Hon Hai BT                                                                | 1         | 0.81%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth                                     | 1         | 0.81%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.81%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 1         | 0.81%   |
| Foxconn / Hon Hai BCM43142A0                                                        | 1         | 0.81%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 0.81%   |
| Broadcom Bluetooth 3.0 Device                                                       | 1         | 0.81%   |
| ASUS BCM20702A0                                                                     | 1         | 0.81%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 138       | 56.33%  |
| AMD                                          | 44        | 17.96%  |
| Nvidia                                       | 38        | 15.51%  |
| Logitech                                     | 6         | 2.45%   |
| C-Media Electronics                          | 4         | 1.63%   |
| Hewlett-Packard                              | 3         | 1.22%   |
| SteelSeries ApS                              | 2         | 0.82%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.41%   |
| www.hirestech.com 2012 REV 1.8               | 1         | 0.41%   |
| Sony                                         | 1         | 0.41%   |
| Realtek Semiconductor                        | 1         | 0.41%   |
| Micro Star International                     | 1         | 0.41%   |
| Lenovo                                       | 1         | 0.41%   |
| Kingston Technology                          | 1         | 0.41%   |
| Generalplus Technology                       | 1         | 0.41%   |
| Bose                                         | 1         | 0.41%   |
| Apple                                        | 1         | 0.41%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 22        | 7.33%   |
| Intel Sunrise Point-LP HD Audio                                            | 20        | 6.67%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 16        | 5.33%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 15        | 5%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 13        | 4.33%   |
| AMD Starship/Matisse HD Audio Controller                                   | 10        | 3.33%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 7         | 2.33%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 7         | 2.33%   |
| Intel Cannon Lake PCH cAVS                                                 | 7         | 2.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7         | 2.33%   |
| Intel 200 Series PCH HD Audio                                              | 7         | 2.33%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6         | 2%      |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 1.67%   |
| Intel Haswell-ULT HD Audio Controller                                      | 5         | 1.67%   |
| Intel Broadwell-U Audio Controller                                         | 5         | 1.67%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 1.67%   |
| Intel 8 Series HD Audio Controller                                         | 5         | 1.67%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5         | 1.67%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4         | 1.33%   |
| Nvidia GA107 High Definition Audio Controller                              | 4         | 1.33%   |
| Nvidia GA106 High Definition Audio Controller                              | 4         | 1.33%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 1.33%   |
| Intel Alder Lake-S HD Audio Controller                                     | 4         | 1.33%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 1.33%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 4         | 1.33%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 4         | 1.33%   |
| Nvidia High Definition Audio Controller                                    | 3         | 1%      |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 1%      |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 0.67%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 0.67%   |
| Nvidia GP108 High Definition Audio Controller                              | 2         | 0.67%   |
| Nvidia GM204 High Definition Audio Controller                              | 2         | 0.67%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 0.67%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 0.67%   |
| Logitech Blue Microphones                                                  | 2         | 0.67%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 0.67%   |
| Intel Raptor Lake High Definition Audio Controller                         | 2         | 0.67%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 0.67%   |
| Intel CM238 HD Audio Controller                                            | 2         | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 32        | 27.35%  |
| SK hynix                     | 22        | 18.8%   |
| Micron Technology            | 11        | 9.4%    |
| Kingston                     | 10        | 8.55%   |
| Crucial                      | 9         | 7.69%   |
| Corsair                      | 8         | 6.84%   |
| Unknown                      | 6         | 5.13%   |
| G.Skill                      | 6         | 5.13%   |
| A-DATA Technology            | 5         | 4.27%   |
| Qimonda                      | 2         | 1.71%   |
| Wilk                         | 1         | 0.85%   |
| Unknown (ABCD)               | 1         | 0.85%   |
| Unknown (0x7F7FB5FFFFFFFFFF) | 1         | 0.85%   |
| Timetec                      | 1         | 0.85%   |
| Patriot                      | 1         | 0.85%   |
| Dane-Elec                    | 1         | 0.85%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 2667MT/s              | 3         | 2.42%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                        | 2         | 1.61%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 1.61%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 1.61%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 1.61%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 2         | 1.61%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 2         | 1.61%   |
| Kingston RAM ACR16D3LS1KNG/4G 4GB SODIMM DDR3 1600MT/s              | 2         | 1.61%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s             | 2         | 1.61%   |
| Wilk RAM GR3200S464L22S/16G 16GB SODIMM DDR4 3200MT/s               | 1         | 0.81%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s                         | 1         | 0.81%   |
| Unknown RAM Module 4GB SODIMM LPDDR3 1600MT/s                       | 1         | 0.81%   |
| Unknown RAM Module 4GB SODIMM DDR3                                  | 1         | 0.81%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                        | 1         | 0.81%   |
| Unknown RAM Module 2GB SODIMM DDR2                                  | 1         | 0.81%   |
| Unknown RAM Module 2048MB SODIMM DDR2                               | 1         | 0.81%   |
| Unknown RAM Module 1024MB SODIMM DDR2                               | 1         | 0.81%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s    | 1         | 0.81%   |
| Unknown (0x7F7FB5FFFFFFFFFF) RAM Module 1GB DIMM DDR2 667MT/s       | 1         | 0.81%   |
| Timetec RAM SD3-1333 8GB SODIMM DDR3 1333MT/s                       | 1         | 0.81%   |
| SK hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s             | 1         | 0.81%   |
| SK hynix RAM Module 4GB DIMM DDR3 1066MT/s                          | 1         | 0.81%   |
| SK hynix RAM Module 4096MB Row Of Chips LPDDR3 2133MT/s             | 1         | 0.81%   |
| SK hynix RAM Module 16GB SODIMM DDR5 4800MT/s                       | 1         | 0.81%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 0.81%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s              | 1         | 0.81%   |
| SK hynix RAM HMCG88MEBSA092N 32GB SODIMM DDR5 4800MT/s              | 1         | 0.81%   |
| SK hynix RAM HMCG78AGBSA095N 16GB SODIMM DDR5 5600MT/s              | 1         | 0.81%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 0.81%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s              | 1         | 0.81%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s             | 1         | 0.81%   |
| SK hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 1         | 0.81%   |
| SK hynix RAM HMA82GR7CJR8N-VK 16GB DIMM DDR4 2666MT/s               | 1         | 0.81%   |
| SK hynix RAM HMA82GR7AFR8N-VK 16GB DIMM DDR4 2666MT/s               | 1         | 0.81%   |
| SK hynix RAM HMA81GS6MFR8N-UH 8GB SODIMM DDR4 2400MT/s              | 1         | 0.81%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 0.81%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s              | 1         | 0.81%   |
| SK hynix RAM H9JCNNNFA5MLYR-N6E 8GB Row Of Chips LPDDR5 6400MT/s    | 1         | 0.81%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s    | 1         | 0.81%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 1         | 0.81%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 54        | 50%     |
| DDR3   | 26        | 24.07%  |
| DDR5   | 9         | 8.33%   |
| LPDDR3 | 6         | 5.56%   |
| DDR2   | 5         | 4.63%   |
| SDRAM  | 3         | 2.78%   |
| LPDDR5 | 3         | 2.78%   |
| LPDDR4 | 2         | 1.85%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 66        | 62.26%  |
| DIMM         | 29        | 27.36%  |
| Row Of Chips | 11        | 10.38%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 48        | 42.48%  |
| 16384 | 27        | 23.89%  |
| 4096  | 20        | 17.7%   |
| 32768 | 8         | 7.08%   |
| 2048  | 8         | 7.08%   |
| 1024  | 2         | 1.77%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 21        | 18.75%  |
| 2667    | 21        | 18.75%  |
| 1600    | 16        | 14.29%  |
| 2400    | 9         | 8.04%   |
| 2133    | 8         | 7.14%   |
| 3600    | 6         | 5.36%   |
| 4800    | 5         | 4.46%   |
| 6400    | 3         | 2.68%   |
| 1333    | 3         | 2.68%   |
| Unknown | 3         | 2.68%   |
| 5600    | 2         | 1.79%   |
| 1867    | 2         | 1.79%   |
| 800     | 2         | 1.79%   |
| 7500    | 1         | 0.89%   |
| 6000    | 1         | 0.89%   |
| 3534    | 1         | 0.89%   |
| 3500    | 1         | 0.89%   |
| 3400    | 1         | 0.89%   |
| 2933    | 1         | 0.89%   |
| 2666    | 1         | 0.89%   |
| 1334    | 1         | 0.89%   |
| 1067    | 1         | 0.89%   |
| 1066    | 1         | 0.89%   |
| 667     | 1         | 0.89%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 3         | 75%     |
| STMicroelectronics | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 25%     |
| HP OfficeJet 6950                                         | 1         | 25%     |
| HP Officejet 6600                                         | 1         | 25%     |
| HP OfficeJet 5200 series                                  | 1         | 25%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 28        | 24.35%  |
| Microdia                               | 15        | 13.04%  |
| IMC Networks                           | 12        | 10.43%  |
| Logitech                               | 7         | 6.09%   |
| Bison Electronics                      | 6         | 5.22%   |
| Apple                                  | 6         | 5.22%   |
| Realtek Semiconductor                  | 5         | 4.35%   |
| Samsung Electronics                    | 4         | 3.48%   |
| Quanta                                 | 4         | 3.48%   |
| Sunplus Innovation Technology          | 3         | 2.61%   |
| Ricoh                                  | 3         | 2.61%   |
| Luxvisions Innotech Limited            | 3         | 2.61%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 2.61%   |
| Alcor Micro                            | 3         | 2.61%   |
| Syntek                                 | 2         | 1.74%   |
| YGTek                                  | 1         | 0.87%   |
| Silicon Motion                         | 1         | 0.87%   |
| ShineTech                              | 1         | 0.87%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.87%   |
| Lite-On Technology                     | 1         | 0.87%   |
| kingcome                               | 1         | 0.87%   |
| Huawei Technologies                    | 1         | 0.87%   |
| Cubeternet                             | 1         | 0.87%   |
| ALi                                    | 1         | 0.87%   |
| Acer                                   | 1         | 0.87%   |
| Unknown                                | 1         | 0.87%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                    | 6         | 5.22%   |
| IMC Networks USB2.0 HD UVC WebCam                | 5         | 4.35%   |
| Samsung Galaxy series, misc. (MTP mode)          | 4         | 3.48%   |
| IMC Networks Integrated Camera                   | 4         | 3.48%   |
| Chicony Integrated Camera                        | 4         | 3.48%   |
| Logitech B525 HD Webcam                          | 3         | 2.61%   |
| Chicony HD WebCam                                | 3         | 2.61%   |
| Apple FaceTime HD Camera                         | 3         | 2.61%   |
| Realtek Integrated_Webcam_HD                     | 2         | 1.74%   |
| Quanta HD User Facing                            | 2         | 1.74%   |
| Microdia Integrated_Webcam_FHD                   | 2         | 1.74%   |
| Microdia Integrated Webcam                       | 2         | 1.74%   |
| Luxvisions Innotech Limited HP HD Camera         | 2         | 1.74%   |
| Logitech HD Pro Webcam C920                      | 2         | 1.74%   |
| Chicony Integrated IR Camera                     | 2         | 1.74%   |
| Chicony Integrated Camera (1280x720@30)          | 2         | 1.74%   |
| Chicony HP Wide Vision HD Camera                 | 2         | 1.74%   |
| Chicony HP HD Camera                             | 2         | 1.74%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera | 2         | 1.74%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR               | 2         | 1.74%   |
| YGTek Webcam                                     | 1         | 0.87%   |
| Syntek USB2.0 Camera                             | 1         | 0.87%   |
| Syntek Integrated Camera                         | 1         | 0.87%   |
| Sunplus Laptop Integrated WebCam HD              | 1         | 0.87%   |
| Sunplus Hy-Usb2.0-1*MIC                          | 1         | 0.87%   |
| Sunplus HP HD Webcam [Fixed]                     | 1         | 0.87%   |
| Silicon Motion Web Camera                        | 1         | 0.87%   |
| ShineTech HD Camera                              | 1         | 0.87%   |
| Shenzhen Kingcome Optoelectronic 720p HD Camera  | 1         | 0.87%   |
| Ricoh USB2.0 Camera                              | 1         | 0.87%   |
| Ricoh Sony Visual Communication Camera           | 1         | 0.87%   |
| Ricoh Sony Vaio Integrated Webcam                | 1         | 0.87%   |
| Realtek Laptop Camera                            | 1         | 0.87%   |
| Realtek Integrated Webcam_HD                     | 1         | 0.87%   |
| Realtek HP Truevision HD                         | 1         | 0.87%   |
| Quanta HP Wide Vision HD Camera                  | 1         | 0.87%   |
| Quanta HP Webcam                                 | 1         | 0.87%   |
| Microdia Webcam Vitade AF                        | 1         | 0.87%   |
| Microdia Webcam                                  | 1         | 0.87%   |
| Microdia USB 2.0 Camera                          | 1         | 0.87%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 11        | 40.74%  |
| Validity Sensors           | 7         | 25.93%  |
| Shenzhen Goodix Technology | 5         | 18.52%  |
| Upek                       | 1         | 3.7%    |
| LighTuning Technology      | 1         | 3.7%    |
| Elan Microelectronics      | 1         | 3.7%    |
| AuthenTec                  | 1         | 3.7%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 5         | 18.52%  |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 3         | 11.11%  |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 11.11%  |
| Validity Sensors Synaptics WBDI                                            | 2         | 7.41%   |
| Shenzhen Goodix  Fingerprint Device                                        | 2         | 7.41%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 3.7%    |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 3.7%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 3.7%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 3.7%    |
| Validity Sensors Fingerprint scanner                                       | 1         | 3.7%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 3.7%    |
| Synaptics UWP WBDI                                                         | 1         | 3.7%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 3.7%    |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 3.7%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 3.7%    |
| Elan ELAN:Fingerprint                                                      | 1         | 3.7%    |
| AuthenTec Fingerprint Sensor                                               | 1         | 3.7%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Alcor Micro              | 5         | 38.46%  |
| Broadcom                 | 4         | 30.77%  |
| Gemalto (was Gemplus)    | 3         | 23.08%  |
| Reiner SCT Kartensysteme | 1         | 7.69%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 5         | 38.46%  |
| Gemalto (was Gemplus) Prox SU USB PC Link Reader                             | 2         | 15.38%  |
| Broadcom 58200                                                               | 2         | 15.38%  |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 7.69%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 7.69%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 7.69%   |
| Broadcom 5880                                                                | 1         | 7.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 111       | 62.36%  |
| 1     | 47        | 26.4%   |
| 2     | 17        | 9.55%   |
| 3     | 3         | 1.69%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 27        | 31.76%  |
| Graphics card            | 16        | 18.82%  |
| Net/wireless             | 8         | 9.41%   |
| Chipcard                 | 8         | 9.41%   |
| Multimedia controller    | 7         | 8.24%   |
| Communication controller | 4         | 4.71%   |
| Unassigned class         | 3         | 3.53%   |
| Network                  | 3         | 3.53%   |
| Card reader              | 3         | 3.53%   |
| Net/ethernet             | 2         | 2.35%   |
| Camera                   | 2         | 2.35%   |
| Sound                    | 1         | 1.18%   |
| Bluetooth                | 1         | 1.18%   |

