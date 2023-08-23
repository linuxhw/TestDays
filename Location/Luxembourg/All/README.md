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

Total: 189

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04                 | 20        | 13.42%  |
| Ubuntu 22.04                 | 10        | 6.71%   |
| Ubuntu 18.04                 | 10        | 6.71%   |
| Ubuntu 21.04                 | 4         | 2.68%   |
| openSUSE Tumbleweed-XXXXXXXX | 4         | 2.68%   |
| Linux Mint 20.3              | 4         | 2.68%   |
| Ubuntu 20.10                 | 3         | 2.01%   |
| Pop!_OS 22.04                | 3         | 2.01%   |
| Pop!_OS 21.04                | 3         | 2.01%   |
| OpenMandriva 4.2             | 3         | 2.01%   |
| Fedora 37                    | 3         | 2.01%   |
| Fedora 32                    | 3         | 2.01%   |
| Zorin 16                     | 2         | 1.34%   |
| Xubuntu 20.04                | 2         | 1.34%   |
| Ubuntu 18.10                 | 2         | 1.34%   |
| ROSA R9                      | 2         | 1.34%   |
| Pop!_OS 21.10                | 2         | 1.34%   |
| openSUSE Leap-15.2           | 2         | 1.34%   |
| OpenMandriva 4.90            | 2         | 1.34%   |
| OpenMandriva 23.03           | 2         | 1.34%   |
| LMDE 4                       | 2         | 1.34%   |
| Kubuntu 22.04                | 2         | 1.34%   |
| Fedora 38                    | 2         | 1.34%   |
| Debian 10                    | 2         | 1.34%   |
| ArcoLinux Rolling            | 2         | 1.34%   |
| Xubuntu 18.04                | 1         | 0.67%   |
| Xubuntu 16.04                | 1         | 0.67%   |
| UbuntuDDE 20.04              | 1         | 0.67%   |
| Ubuntu Studio 20.04          | 1         | 0.67%   |
| Ubuntu MATE 21.10            | 1         | 0.67%   |
| Ubuntu MATE 20.04            | 1         | 0.67%   |
| Ubuntu 22.10                 | 1         | 0.67%   |
| Ubuntu 19.10                 | 1         | 0.67%   |
| RHEL 8                       | 1         | 0.67%   |
| Pop!_OS 20.10                | 1         | 0.67%   |
| Pop!_OS 20.04                | 1         | 0.67%   |
| Parrot 5.3                   | 1         | 0.67%   |
| Parrot 5.1                   | 1         | 0.67%   |
| openSUSE Leap-15.4           | 1         | 0.67%   |
| openSUSE Leap-15.3           | 1         | 0.67%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 49        | 34.51%  |
| Fedora        | 11        | 7.75%   |
| Pop!_OS       | 9         | 6.34%   |
| openSUSE      | 8         | 5.63%   |
| OpenMandriva  | 8         | 5.63%   |
| Linux Mint    | 7         | 4.93%   |
| Kubuntu       | 5         | 3.52%   |
| Xubuntu       | 4         | 2.82%   |
| Manjaro       | 3         | 2.11%   |
| Lubuntu       | 3         | 2.11%   |
| Debian        | 3         | 2.11%   |
| Zorin         | 2         | 1.41%   |
| Ubuntu MATE   | 2         | 1.41%   |
| ROSA          | 2         | 1.41%   |
| Parrot        | 2         | 1.41%   |
| LMDE          | 2         | 1.41%   |
| KDE neon      | 2         | 1.41%   |
| Kali          | 2         | 1.41%   |
| Endless       | 2         | 1.41%   |
| Elementary    | 2         | 1.41%   |
| ArcoLinux     | 2         | 1.41%   |
| Arch          | 2         | 1.41%   |
| UbuntuDDE     | 1         | 0.7%    |
| Ubuntu Studio | 1         | 0.7%    |
| RHEL          | 1         | 0.7%    |
| Mageia        | 1         | 0.7%    |
| Gentoo        | 1         | 0.7%    |
| Garuda Linux  | 1         | 0.7%    |
| EndeavourOS   | 1         | 0.7%    |
| Clear Linux   | 1         | 0.7%    |
| CentOS        | 1         | 0.7%    |
| BlackPanther  | 1         | 0.7%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.8.0-43-generic                | 3         | 1.94%   |
| 5.15.0-52-generic               | 3         | 1.94%   |
| 5.11.0-27-generic               | 3         | 1.94%   |
| 5.10.14-desktop-1omv4002        | 3         | 1.94%   |
| 6.2.6-desktop-1omv2390          | 2         | 1.29%   |
| 6.2.14-200.fc37.x86_64          | 2         | 1.29%   |
| 5.8.0-59-generic                | 2         | 1.29%   |
| 5.4.0-96-generic                | 2         | 1.29%   |
| 5.4.0-90-generic                | 2         | 1.29%   |
| 5.4.0-47-generic                | 2         | 1.29%   |
| 5.4.0-42-generic                | 2         | 1.29%   |
| 5.4.0-122-generic               | 2         | 1.29%   |
| 5.3.0-46-generic                | 2         | 1.29%   |
| 5.19.0-35-generic               | 2         | 1.29%   |
| 5.18.12-desktop-3omv4090        | 2         | 1.29%   |
| 5.16.11-76051611-generic        | 2         | 1.29%   |
| 5.11.0-34-generic               | 2         | 1.29%   |
| 5.11.0-17-generic               | 2         | 1.29%   |
| 5.0.0-23-generic                | 2         | 1.29%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 2         | 1.29%   |
| 4.19.0-17-amd64                 | 2         | 1.29%   |
| 6.4.7-arch1-1                   | 1         | 0.65%   |
| 6.4.4-zen1-1-zen                | 1         | 0.65%   |
| 6.4.3-1-default                 | 1         | 0.65%   |
| 6.4.3-060403-generic            | 1         | 0.65%   |
| 6.3.12-200.fc38.x86_64          | 1         | 0.65%   |
| 6.3.1-arch2-1                   | 1         | 0.65%   |
| 6.2.9-300.fc38.x86_64           | 1         | 0.65%   |
| 6.2.0-26-generic                | 1         | 0.65%   |
| 6.1.8-060108-generic            | 1         | 0.65%   |
| 6.1.22-gentoo-dist              | 1         | 0.65%   |
| 6.1.10-200.fc37.x86_64          | 1         | 0.65%   |
| 6.1.0-1parrot1-amd64            | 1         | 0.65%   |
| 6.0.6-76060006-generic          | 1         | 0.65%   |
| 6.0.0-kali3-amd64               | 1         | 0.65%   |
| 5.9.13-zen1-1-zen               | 1         | 0.65%   |
| 5.9.10-200.fc33.x86_64          | 1         | 0.65%   |
| 5.8.11-050811-generic           | 1         | 0.65%   |
| 5.8.0-63-generic                | 1         | 0.65%   |
| 5.8.0-55-generic                | 1         | 0.65%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 20        | 13.51%  |
| 5.15.0  | 14        | 9.46%   |
| 5.11.0  | 14        | 9.46%   |
| 5.8.0   | 10        | 6.76%   |
| 5.19.0  | 7         | 4.73%   |
| 5.3.0   | 6         | 4.05%   |
| 4.18.0  | 6         | 4.05%   |
| 5.13.0  | 4         | 2.7%    |
| 4.15.0  | 4         | 2.7%    |
| 5.10.14 | 3         | 2.03%   |
| 5.0.0   | 3         | 2.03%   |
| 6.4.3   | 2         | 1.35%   |
| 6.2.6   | 2         | 1.35%   |
| 6.2.14  | 2         | 1.35%   |
| 5.7.0   | 2         | 1.35%   |
| 5.3.18  | 2         | 1.35%   |
| 5.18.12 | 2         | 1.35%   |
| 5.16.11 | 2         | 1.35%   |
| 5.10.0  | 2         | 1.35%   |
| 4.9.20  | 2         | 1.35%   |
| 4.19.0  | 2         | 1.35%   |
| 6.4.7   | 1         | 0.68%   |
| 6.4.4   | 1         | 0.68%   |
| 6.3.12  | 1         | 0.68%   |
| 6.3.1   | 1         | 0.68%   |
| 6.2.9   | 1         | 0.68%   |
| 6.2.0   | 1         | 0.68%   |
| 6.1.8   | 1         | 0.68%   |
| 6.1.22  | 1         | 0.68%   |
| 6.1.10  | 1         | 0.68%   |
| 6.1.0   | 1         | 0.68%   |
| 6.0.6   | 1         | 0.68%   |
| 6.0.0   | 1         | 0.68%   |
| 5.9.13  | 1         | 0.68%   |
| 5.9.10  | 1         | 0.68%   |
| 5.8.11  | 1         | 0.68%   |
| 5.7.6   | 1         | 0.68%   |
| 5.7.19  | 1         | 0.68%   |
| 5.7.14  | 1         | 0.68%   |
| 5.7.1   | 1         | 0.68%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 20        | 13.51%  |
| 5.15    | 16        | 10.81%  |
| 5.11    | 14        | 9.46%   |
| 5.8     | 11        | 7.43%   |
| 5.3     | 8         | 5.41%   |
| 5.19    | 7         | 4.73%   |
| 5.10    | 7         | 4.73%   |
| 4.18    | 7         | 4.73%   |
| 6.2     | 6         | 4.05%   |
| 5.7     | 6         | 4.05%   |
| 5.13    | 5         | 3.38%   |
| 6.4     | 4         | 2.7%    |
| 6.1     | 4         | 2.7%    |
| 5.18    | 4         | 2.7%    |
| 5.16    | 4         | 2.7%    |
| 4.15    | 4         | 2.7%    |
| 5.0     | 3         | 2.03%   |
| 6.3     | 2         | 1.35%   |
| 6.0     | 2         | 1.35%   |
| 5.9     | 2         | 1.35%   |
| 5.14    | 2         | 1.35%   |
| 5.12    | 2         | 1.35%   |
| 4.9     | 2         | 1.35%   |
| 4.19    | 2         | 1.35%   |
| 5.6     | 1         | 0.68%   |
| 5.5     | 1         | 0.68%   |
| 4.4     | 1         | 0.68%   |
| 4.12    | 1         | 0.68%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 136       | 98.55%  |
| i686   | 2         | 1.45%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 62        | 43.36%  |
| KDE5            | 26        | 18.18%  |
| Unknown         | 15        | 10.49%  |
| XFCE            | 10        | 6.99%   |
| X-Cinnamon      | 9         | 6.29%   |
| KDE             | 5         | 3.5%    |
| MATE            | 4         | 2.8%    |
| LXQt            | 3         | 2.1%    |
| Pantheon        | 2         | 1.4%    |
| i3              | 2         | 1.4%    |
| Deepin          | 2         | 1.4%    |
| Cinnamon        | 2         | 1.4%    |
| GNOME Flashback | 1         | 0.7%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 107       | 74.83%  |
| Wayland | 23        | 16.08%  |
| Unknown | 9         | 6.29%   |
| Tty     | 4         | 2.8%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 66        | 45.83%  |
| SDDM    | 23        | 15.97%  |
| LightDM | 19        | 13.19%  |
| GDM     | 19        | 13.19%  |
| GDM3    | 13        | 9.03%   |
| TDM     | 4         | 2.78%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 60        | 42.25%  |
| en_GB   | 13        | 9.15%   |
| Unknown | 13        | 9.15%   |
| fr_FR   | 12        | 8.45%   |
| de_LU   | 10        | 7.04%   |
| de_DE   | 7         | 4.93%   |
| C       | 6         | 4.23%   |
| fr_LU   | 4         | 2.82%   |
| es_ES   | 3         | 2.11%   |
| POSIX   | 2         | 1.41%   |
| nl_NL   | 2         | 1.41%   |
| unm_US  | 1         | 0.7%    |
| pt_PT   | 1         | 0.7%    |
| pt_BR   | 1         | 0.7%    |
| lb_LU   | 1         | 0.7%    |
| it_IT   | 1         | 0.7%    |
| hr_HR   | 1         | 0.7%    |
| fr_CH   | 1         | 0.7%    |
| en_IE   | 1         | 0.7%    |
| en_AU   | 1         | 0.7%    |
| de_CH   | 1         | 0.7%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 77        | 55%     |
| BIOS | 63        | 45%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 101       | 72.66%  |
| Btrfs   | 18        | 12.95%  |
| Overlay | 9         | 6.47%   |
| Xfs     | 5         | 3.6%    |
| Unknown | 4         | 2.88%   |
| Zfs     | 1         | 0.72%   |
| Tmpfs   | 1         | 0.72%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 66        | 47.48%  |
| GPT     | 63        | 45.32%  |
| MBR     | 10        | 7.19%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 125       | 89.93%  |
| Yes       | 14        | 10.07%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 101       | 72.66%  |
| Yes       | 38        | 27.34%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 21        | 15.22%  |
| Hewlett-Packard     | 19        | 13.77%  |
| Lenovo              | 14        | 10.14%  |
| Dell                | 11        | 7.97%   |
| Gigabyte Technology | 8         | 5.8%    |
| MSI                 | 6         | 4.35%   |
| Intel               | 6         | 4.35%   |
| Sony                | 5         | 3.62%   |
| Apple               | 5         | 3.62%   |
| Acer                | 5         | 3.62%   |
| Medion              | 4         | 2.9%    |
| HUAWEI              | 4         | 2.9%    |
| ASRock              | 4         | 2.9%    |
| Wortmann AG         | 3         | 2.17%   |
| Win Element         | 3         | 2.17%   |
| Samsung Electronics | 2         | 1.45%   |
| Fujitsu             | 2         | 1.45%   |
| Clevo               | 2         | 1.45%   |
| YJKC                | 1         | 0.72%   |
| TUXEDO              | 1         | 0.72%   |
| Toshiba             | 1         | 0.72%   |
| Timi                | 1         | 0.72%   |
| SLIMBOOK            | 1         | 0.72%   |
| Packard Bell        | 1         | 0.72%   |
| Notebook            | 1         | 0.72%   |
| Microsoft           | 1         | 0.72%   |
| MACHINIST           | 1         | 0.72%   |
| LattePanda          | 1         | 0.72%   |
| JWIPC               | 1         | 0.72%   |
| Foxconn             | 1         | 0.72%   |
| BESSTAR Tech        | 1         | 0.72%   |
| Unknown             | 1         | 0.72%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| ASUS All Series                          | 3         | 2.17%   |
| win element MoreFine S500+               | 2         | 1.45%   |
| Dell Precision M3800                     | 2         | 1.45%   |
| Dell Precision 7670                      | 2         | 1.45%   |
| YJKC vBook                               | 1         | 0.72%   |
| Wortmann AG TERRA_MOBILE_1749            | 1         | 0.72%   |
| Wortmann AG TERRA_MOBILE_1541H           | 1         | 0.72%   |
| Wortmann AG MS-1727                      | 1         | 0.72%   |
| Win Element M9                           | 1         | 0.72%   |
| TUXEDO Pulse 14 Gen1                     | 1         | 0.72%   |
| Toshiba Satellite C55-A-1N0              | 1         | 0.72%   |
| Timi RedmiBook 14 II                     | 1         | 0.72%   |
| Sony VPCP11S1R                           | 1         | 0.72%   |
| Sony VPCEB2E1E                           | 1         | 0.72%   |
| Sony VPCCA4E1E                           | 1         | 0.72%   |
| Sony VGN-NS30E_S                         | 1         | 0.72%   |
| Sony SVF1421E2EW                         | 1         | 0.72%   |
| SLIMBOOK EXECUTIVE-14                    | 1         | 0.72%   |
| Samsung Galaxy TabPro S LTE              | 1         | 0.72%   |
| Samsung 950QDB                           | 1         | 0.72%   |
| Packard Bell EasyNote TJ65               | 1         | 0.72%   |
| Notebook NV4XMB,ME,MZ                    | 1         | 0.72%   |
| MSI MS-7E06                              | 1         | 0.72%   |
| MSI MS-7C80                              | 1         | 0.72%   |
| MSI MS-7C08                              | 1         | 0.72%   |
| MSI MS-7816                              | 1         | 0.72%   |
| MSI MS-7578                              | 1         | 0.72%   |
| MSI GF72 8RD                             | 1         | 0.72%   |
| Microsoft Surface Book 2                 | 1         | 0.72%   |
| Medion P961x                             | 1         | 0.72%   |
| Medion P6685 MD61138                     | 1         | 0.72%   |
| Medion MS-7848                           | 1         | 0.72%   |
| Medion E4254 MD62100                     | 1         | 0.72%   |
| MACHINIST E5-D8-MAX V1.1                 | 1         | 0.72%   |
| Lenovo ThinkStation P920 30BDS2H804      | 1         | 0.72%   |
| Lenovo ThinkPad X1 Carbon 7th 20QDCTO1WW | 1         | 0.72%   |
| Lenovo ThinkPad T590 20N4CTO1WW          | 1         | 0.72%   |
| Lenovo ThinkPad T490 20N3S5DV0S          | 1         | 0.72%   |
| Lenovo ThinkPad T480s 20L7001PFR         | 1         | 0.72%   |
| Lenovo ThinkPad T470s W10DG 20JTS0R800   | 1         | 0.72%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 10        | 7.25%   |
| Dell Precision        | 7         | 5.07%   |
| HP EliteBook          | 5         | 3.62%   |
| ASUS PRIME            | 4         | 2.9%    |
| Acer Aspire           | 4         | 2.9%    |
| HP ENVY               | 3         | 2.17%   |
| ASUS VivoBook         | 3         | 2.17%   |
| ASUS TUF              | 3         | 2.17%   |
| ASUS ROG              | 3         | 2.17%   |
| ASUS All              | 3         | 2.17%   |
| Wortmann AG TERRA     | 2         | 1.45%   |
| win element MoreFine  | 2         | 1.45%   |
| HP ZBook              | 2         | 1.45%   |
| HP ProBook            | 2         | 1.45%   |
| HP Compaq             | 2         | 1.45%   |
| Dell XPS              | 2         | 1.45%   |
| YJKC vBook            | 1         | 0.72%   |
| Wortmann AG MS-1727   | 1         | 0.72%   |
| Win Element M9        | 1         | 0.72%   |
| TUXEDO Pulse          | 1         | 0.72%   |
| Toshiba Satellite     | 1         | 0.72%   |
| Timi RedmiBook        | 1         | 0.72%   |
| Sony VPCP11S1R        | 1         | 0.72%   |
| Sony VPCEB2E1E        | 1         | 0.72%   |
| Sony VPCCA4E1E        | 1         | 0.72%   |
| Sony VGN-NS30E        | 1         | 0.72%   |
| Sony SVF1421E2EW      | 1         | 0.72%   |
| SLIMBOOK EXECUTIVE-14 | 1         | 0.72%   |
| Samsung Galaxy        | 1         | 0.72%   |
| Samsung 950QDB        | 1         | 0.72%   |
| Packard Bell EasyNote | 1         | 0.72%   |
| Notebook NV4XMB       | 1         | 0.72%   |
| MSI MS-7E06           | 1         | 0.72%   |
| MSI MS-7C80           | 1         | 0.72%   |
| MSI MS-7C08           | 1         | 0.72%   |
| MSI MS-7816           | 1         | 0.72%   |
| MSI MS-7578           | 1         | 0.72%   |
| MSI GF72              | 1         | 0.72%   |
| Microsoft Surface     | 1         | 0.72%   |
| Medion P961x          | 1         | 0.72%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 18        | 13.04%  |
| 2018 | 16        | 11.59%  |
| 2020 | 14        | 10.14%  |
| 2021 | 13        | 9.42%   |
| 2017 | 12        | 8.7%    |
| 2013 | 12        | 8.7%    |
| 2014 | 10        | 7.25%   |
| 2010 | 9         | 6.52%   |
| 2016 | 7         | 5.07%   |
| 2022 | 5         | 3.62%   |
| 2011 | 5         | 3.62%   |
| 2023 | 4         | 2.9%    |
| 2015 | 4         | 2.9%    |
| 2012 | 3         | 2.17%   |
| 2009 | 3         | 2.17%   |
| 2007 | 2         | 1.45%   |
| 2008 | 1         | 0.72%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 81        | 58.7%   |
| Desktop     | 46        | 33.33%  |
| Mini pc     | 4         | 2.9%    |
| Convertible | 3         | 2.17%   |
| Tablet      | 2         | 1.45%   |
| All in one  | 1         | 0.72%   |
| Server      | 1         | 0.72%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 125       | 89.93%  |
| Enabled  | 14        | 10.07%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 138       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 40        | 28.57%  |
| 8.01-16.0       | 30        | 21.43%  |
| 4.01-8.0        | 23        | 16.43%  |
| 32.01-64.0      | 17        | 12.14%  |
| 3.01-4.0        | 17        | 12.14%  |
| 64.01-256.0     | 6         | 4.29%   |
| 24.01-32.0      | 2         | 1.43%   |
| 2.01-3.0        | 2         | 1.43%   |
| 1.01-2.0        | 2         | 1.43%   |
| More than 256.0 | 1         | 0.71%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 43        | 29.86%  |
| 1.01-2.0   | 34        | 23.61%  |
| 4.01-8.0   | 28        | 19.44%  |
| 3.01-4.0   | 19        | 13.19%  |
| 8.01-16.0  | 13        | 9.03%   |
| 0.51-1.0   | 3         | 2.08%   |
| 24.01-32.0 | 2         | 1.39%   |
| 16.01-24.0 | 1         | 0.69%   |
| 0.01-0.5   | 1         | 0.69%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 77        | 55%     |
| 2      | 34        | 24.29%  |
| 3      | 14        | 10%     |
| 4      | 7         | 5%      |
| 5      | 3         | 2.14%   |
| 7      | 2         | 1.43%   |
| 0      | 2         | 1.43%   |
| 6      | 1         | 0.71%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 96        | 69.57%  |
| Yes       | 42        | 30.43%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 115       | 83.33%  |
| No        | 23        | 16.67%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 113       | 81.29%  |
| No        | 26        | 18.71%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 97        | 70.29%  |
| No        | 41        | 29.71%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Computers | Percent |
|------------|-----------|---------|
| Luxembourg | 138       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Luxembourg        | 81        | 55.1%   |
| Strassen          | 9         | 6.12%   |
| Useldange         | 3         | 2.04%   |
| Schifflange       | 3         | 2.04%   |
| Schieren          | 3         | 2.04%   |
| Esch-sur-Alzette  | 3         | 2.04%   |
| Ehnen             | 3         | 2.04%   |
| Differdange       | 3         | 2.04%   |
| Wormeldange       | 2         | 1.36%   |
| Steinfort         | 2         | 1.36%   |
| Sanem             | 2         | 1.36%   |
| Bettange-sur-Mess | 2         | 1.36%   |
| Wiltz             | 1         | 0.68%   |
| Wecker            | 1         | 0.68%   |
| Wasserbillig      | 1         | 0.68%   |
| Vianden           | 1         | 0.68%   |
| Steinsel          | 1         | 0.68%   |
| Soleuvre          | 1         | 0.68%   |
| Roeser            | 1         | 0.68%   |
| Pontpierre        | 1         | 0.68%   |
| Pétange          | 1         | 0.68%   |
| PerlГ©          | 1         | 0.68%   |
| Oberpallen        | 1         | 0.68%   |
| Niederanven       | 1         | 0.68%   |
| Leudelange        | 1         | 0.68%   |
| Kopstal           | 1         | 0.68%   |
| Junglinster       | 1         | 0.68%   |
| Itzig             | 1         | 0.68%   |
| Hunsdorf          | 1         | 0.68%   |
| Hosingen          | 1         | 0.68%   |
| Hesperange        | 1         | 0.68%   |
| Ettelbruck        | 1         | 0.68%   |
| Echternach        | 1         | 0.68%   |
| Dudelange         | 1         | 0.68%   |
| Diekirch          | 1         | 0.68%   |
| Contern           | 1         | 0.68%   |
| Clervaux          | 1         | 0.68%   |
| Brouch            | 1         | 0.68%   |
| Bourscheid        | 1         | 0.68%   |
| Bettembourg       | 1         | 0.68%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 52        | 71     | 24.88%  |
| Seagate                      | 28        | 37     | 13.4%   |
| WDC                          | 22        | 33     | 10.53%  |
| Crucial                      | 14        | 21     | 6.7%    |
| SanDisk                      | 13        | 18     | 6.22%   |
| Toshiba                      | 12        | 15     | 5.74%   |
| Kingston                     | 10        | 14     | 4.78%   |
| SK hynix                     | 5         | 5      | 2.39%   |
| Apple                        | 5         | 6      | 2.39%   |
| Hitachi                      | 4         | 5      | 1.91%   |
| Intel                        | 3         | 4      | 1.44%   |
| HGST                         | 3         | 4      | 1.44%   |
| Transcend                    | 2         | 2      | 0.96%   |
| Phison                       | 2         | 2      | 0.96%   |
| Micron Technology            | 2         | 3      | 0.96%   |
| LITEONIT                     | 2         | 2      | 0.96%   |
| LITEON                       | 2         | 2      | 0.96%   |
| Intenso                      | 2         | 3      | 0.96%   |
| A-DATA Technology            | 2         | 2      | 0.96%   |
| Unknown                      | 1         | 2      | 0.48%   |
| Union Memory (Shenzhen)      | 1         | 1      | 0.48%   |
| TCSUNBOW                     | 1         | 1      | 0.48%   |
| StarTech                     | 1         | 2      | 0.48%   |
| Shenzhen Longsys Electronics | 1         | 1      | 0.48%   |
| SABRENT                      | 1         | 1      | 0.48%   |
| PNY                          | 1         | 1      | 0.48%   |
| Phison Electronics           | 1         | 1      | 0.48%   |
| PHD 3.0                      | 1         | 1      | 0.48%   |
| OCZ                          | 1         | 1      | 0.48%   |
| Micron/Crucial Technology    | 1         | 1      | 0.48%   |
| Maxtor                       | 1         | 2      | 0.48%   |
| MAXIO Technology (Hangzhou)  | 1         | 2      | 0.48%   |
| Lenovo                       | 1         | 1      | 0.48%   |
| LaCie                        | 1         | 1      | 0.48%   |
| Kingston Technology Company  | 1         | 2      | 0.48%   |
| KingSpec                     | 1         | 1      | 0.48%   |
| KingDian                     | 1         | 1      | 0.48%   |
| JMicron Technology           | 1         | 1      | 0.48%   |
| Inateck                      | 1         | 1      | 0.48%   |
| HUAWEI                       | 1         | 1      | 0.48%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate Expansion 1TB                               | 4         | 1.67%   |
| Samsung SSD 840 EVO 250GB                           | 3         | 1.26%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 3         | 1.26%   |
| Kingston SA400S37240G 240GB SSD                     | 3         | 1.26%   |
| Crucial CT1000P2SSD8 1TB                            | 3         | 1.26%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 2         | 0.84%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 2         | 0.84%   |
| WDC WD10EACS-00D6B1 1TB                             | 2         | 0.84%   |
| Toshiba MQ01ABF050 500GB                            | 2         | 0.84%   |
| Seagate ST4000DM004-2CV104 4TB                      | 2         | 0.84%   |
| Seagate ST2000DM008-2FR102 2TB                      | 2         | 0.84%   |
| Seagate ST1000LM035-1RK172 1TB                      | 2         | 0.84%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB   | 2         | 0.84%   |
| SanDisk SD8SN8U128G1122 128GB SSD                   | 2         | 0.84%   |
| SanDisk NVMe SSD Drive 1TB                          | 2         | 0.84%   |
| Samsung SSD 860 QVO 1TB                             | 2         | 0.84%   |
| Samsung SSD 860 EVO 250GB                           | 2         | 0.84%   |
| Samsung SSD 850 EVO 250GB                           | 2         | 0.84%   |
| Samsung SSD 750 EVO 500GB                           | 2         | 0.84%   |
| Samsung SP2504C 250GB                               | 2         | 0.84%   |
| Samsung MZVLW256HEHP-000L7 256GB                    | 2         | 0.84%   |
| LITEONIT LMT-256L9M-11 MSATA 256GB SSD              | 2         | 0.84%   |
| Kingston SA400S37120G 120GB SSD                     | 2         | 0.84%   |
| Crucial CT240BX500SSD1 240GB                        | 2         | 0.84%   |
| Crucial CT1000MX500SSD1 1TB                         | 2         | 0.84%   |
| WDC WDS500G3X0C-00SJG0 500GB                        | 1         | 0.42%   |
| WDC WDS250G2B0B-00YS70 250GB SSD                    | 1         | 0.42%   |
| WDC WD5000AAVS-00ZTB0 500GB                         | 1         | 0.42%   |
| WDC WD5000AAKS-60Z1A0 500GB                         | 1         | 0.42%   |
| WDC WD40EZRZ-75GXCB0 4TB                            | 1         | 0.42%   |
| WDC WD4000FYYZ-01UL1B2 4TB                          | 1         | 0.42%   |
| WDC WD3200LPCX-00VHAT0 320GB                        | 1         | 0.42%   |
| WDC WD3001FFSX-68JNUN0 3TB                          | 1         | 0.42%   |
| WDC WD3000GLFS-01F8U0 304GB                         | 1         | 0.42%   |
| WDC WD20EFAX-68FB5N0 2TB                            | 1         | 0.42%   |
| WDC WD141KRYZ-01C66B0 14TB                          | 1         | 0.42%   |
| WDC WD10SPZX-17Z10T0 1TB                            | 1         | 0.42%   |
| WDC WD10SPCX-60HWST0 1TB                            | 1         | 0.42%   |
| WDC WD10EZRX-00A8LB0 1TB                            | 1         | 0.42%   |
| WDC WD10EZEX-60ZF5A0 1TB                            | 1         | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 26        | 35     | 39.39%  |
| WDC                 | 16        | 27     | 24.24%  |
| Toshiba             | 8         | 11     | 12.12%  |
| Hitachi             | 4         | 5      | 6.06%   |
| Samsung Electronics | 3         | 3      | 4.55%   |
| HGST                | 3         | 4      | 4.55%   |
| Apple               | 2         | 2      | 3.03%   |
| PHD 3.0             | 1         | 1      | 1.52%   |
| Intenso             | 1         | 1      | 1.52%   |
| Inateck             | 1         | 1      | 1.52%   |
| ASMT                | 1         | 4      | 1.52%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 28        | 37     | 37.33%  |
| SanDisk             | 10        | 12     | 13.33%  |
| Crucial             | 10        | 17     | 13.33%  |
| Kingston            | 6         | 10     | 8%      |
| Transcend           | 2         | 2      | 2.67%   |
| Micron Technology   | 2         | 3      | 2.67%   |
| LITEONIT            | 2         | 2      | 2.67%   |
| LITEON              | 2         | 2      | 2.67%   |
| WDC                 | 1         | 1      | 1.33%   |
| TCSUNBOW            | 1         | 1      | 1.33%   |
| SK hynix            | 1         | 1      | 1.33%   |
| PNY                 | 1         | 1      | 1.33%   |
| OCZ                 | 1         | 1      | 1.33%   |
| Maxtor              | 1         | 2      | 1.33%   |
| Lenovo              | 1         | 1      | 1.33%   |
| KingSpec            | 1         | 1      | 1.33%   |
| KingDian            | 1         | 1      | 1.33%   |
| Intenso             | 1         | 2      | 1.33%   |
| FORESEE             | 1         | 1      | 1.33%   |
| Apple               | 1         | 1      | 1.33%   |
| A-DATA Technology   | 1         | 1      | 1.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 64        | 77     | 33.68%  |
| SSD     | 61        | 100    | 32.11%  |
| HDD     | 57        | 94     | 30%     |
| Unknown | 5         | 6      | 2.63%   |
| MMC     | 3         | 4      | 1.58%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 92        | 179    | 53.18%  |
| NVMe | 64        | 76     | 36.99%  |
| SAS  | 14        | 22     | 8.09%   |
| MMC  | 3         | 4      | 1.73%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 67        | 105    | 50%     |
| 0.51-1.0   | 44        | 60     | 32.84%  |
| 1.01-2.0   | 11        | 13     | 8.21%   |
| 3.01-4.0   | 8         | 11     | 5.97%   |
| 2.01-3.0   | 2         | 3      | 1.49%   |
| 10.01-20.0 | 1         | 1      | 0.75%   |
| 4.01-10.0  | 1         | 1      | 0.75%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 33        | 23.24%  |
| 101-250        | 32        | 22.54%  |
| 501-1000       | 20        | 14.08%  |
| More than 3000 | 15        | 10.56%  |
| Unknown        | 11        | 7.75%   |
| 1001-2000      | 10        | 7.04%   |
| 2001-3000      | 7         | 4.93%   |
| 51-100         | 7         | 4.93%   |
| 1-20           | 5         | 3.52%   |
| 21-50          | 2         | 1.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 45        | 31.47%  |
| 21-50          | 21        | 14.69%  |
| 101-250        | 21        | 14.69%  |
| 251-500        | 12        | 8.39%   |
| 51-100         | 11        | 7.69%   |
| Unknown        | 11        | 7.69%   |
| 501-1000       | 9         | 6.29%   |
| 2001-3000      | 5         | 3.5%    |
| 1001-2000      | 5         | 3.5%    |
| More than 3000 | 3         | 2.1%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABF050 500GB              | 2         | 2      | 33.33%  |
| Toshiba MK2555GSX 250GB               | 1         | 1      | 16.67%  |
| SK hynix HFS128G39TND-N210A 128GB SSD | 1         | 1      | 16.67%  |
| Seagate ST1000LM049-2GH172 1TB        | 1         | 1      | 16.67%  |
| Crucial CT128MX100SSD1 128GB          | 1         | 2      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Toshiba  | 3         | 3      | 50%     |
| SK hynix | 1         | 1      | 16.67%  |
| Seagate  | 1         | 1      | 16.67%  |
| Crucial  | 1         | 2      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 3         | 3      | 75%     |
| Seagate | 1         | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 4         | 4      | 66.67%  |
| SSD  | 2         | 3      | 33.33%  |

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
| Detected | 75        | 154    | 50.34%  |
| Works    | 68        | 120    | 45.64%  |
| Malfunc  | 6         | 7      | 4.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 89        | 49.17%  |
| Samsung Electronics          | 27        | 14.92%  |
| AMD                          | 23        | 12.71%  |
| SanDisk                      | 10        | 5.52%   |
| Micron/Crucial Technology    | 5         | 2.76%   |
| Kingston Technology Company  | 5         | 2.76%   |
| Toshiba America Info Systems | 4         | 2.21%   |
| Phison Electronics           | 4         | 2.21%   |
| SK hynix                     | 3         | 1.66%   |
| Marvell Technology Group     | 3         | 1.66%   |
| Apple                        | 2         | 1.1%    |
| Union Memory (Shenzhen)      | 1         | 0.55%   |
| Shenzhen Longsys Electronics | 1         | 0.55%   |
| Seagate Technology           | 1         | 0.55%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.55%   |
| ASMedia Technology           | 1         | 0.55%   |
| ADATA Technology             | 1         | 0.55%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 19        | 9.64%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 13        | 6.6%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 11        | 5.58%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 9         | 4.57%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 7         | 3.55%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 6         | 3.05%   |
| Intel Volume Management Device NVMe RAID Controller                            | 6         | 3.05%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 6         | 3.05%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 5         | 2.54%   |
| Samsung NVMe SSD Controller 980                                                | 4         | 2.03%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 4         | 2.03%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 2.03%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 4         | 2.03%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 2.03%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 2.03%   |
| AMD 400 Series Chipset SATA Controller                                         | 4         | 2.03%   |
| Phison E12 NVMe Controller                                                     | 3         | 1.52%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 1.52%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 3         | 1.52%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 1.52%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 3         | 1.52%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 1.02%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 2         | 1.02%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2         | 1.02%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                      | 2         | 1.02%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 1.02%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 1.02%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 1.02%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 2         | 1.02%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 2         | 1.02%   |
| AMD 500 Series Chipset SATA Controller                                         | 2         | 1.02%   |
| Union Memory (Shenzhen) AM610 PCIe 3.0 NVMe SSD 128GB                          | 1         | 0.51%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 1         | 0.51%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 1         | 0.51%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 1         | 0.51%   |
| Shenzhen Longsys Non-Volatile memory controller                                | 1         | 0.51%   |
| Seagate FireCuda 520 SSD                                                       | 1         | 0.51%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1         | 0.51%   |
| Samsung NVMe SSD SM0032L                                                       | 1         | 0.51%   |
| Phison PS5013 E13 NVMe Controller                                              | 1         | 0.51%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 98        | 54.14%  |
| NVMe | 65        | 35.91%  |
| RAID | 10        | 5.52%   |
| IDE  | 8         | 4.42%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 108       | 78.26%  |
| AMD    | 30        | 21.74%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 2.9%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 2.9%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 2.17%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 2.17%   |
| AMD Ryzen 5 3600 6-Core Processor             | 3         | 2.17%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 1.45%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 2         | 1.45%   |
| Intel Core i7-4702HQ CPU @ 2.20GHz            | 2         | 1.45%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 2         | 1.45%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 1.45%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 2         | 1.45%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 1.45%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 2         | 1.45%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 2         | 1.45%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 2         | 1.45%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 2         | 1.45%   |
| Intel Xeon Gold 6154 CPU @ 3.00GHz            | 1         | 0.72%   |
| Intel Xeon CPU E5-2698 v3 @ 2.30GHz           | 1         | 0.72%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.72%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 0.72%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 0.72%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 1         | 0.72%   |
| Intel Pentium CPU P6000 @ 1.87GHz             | 1         | 0.72%   |
| Intel Pentium CPU G4560 @ 3.50GHz             | 1         | 0.72%   |
| Intel Pentium CPU G3250 @ 3.20GHz             | 1         | 0.72%   |
| Intel Pentium CPU 987 @ 1.50GHz               | 1         | 0.72%   |
| Intel N100                                    | 1         | 0.72%   |
| Intel Core m5-6Y54 CPU @ 1.10GHz              | 1         | 0.72%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz              | 1         | 0.72%   |
| Intel Core i9-9880H CPU @ 2.30GHz             | 1         | 0.72%   |
| Intel Core i7-9700KF CPU @ 3.60GHz            | 1         | 0.72%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 1         | 0.72%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 1         | 0.72%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 0.72%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 1         | 0.72%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.72%   |
| Intel Core i7-6800K CPU @ 3.40GHz             | 1         | 0.72%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 0.72%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 0.72%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 1         | 0.72%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 33        | 23.91%  |
| Intel Core i5           | 27        | 19.57%  |
| Other                   | 15        | 10.87%  |
| AMD Ryzen 5             | 11        | 7.97%   |
| Intel Core i3           | 9         | 6.52%   |
| AMD Ryzen 7             | 6         | 4.35%   |
| AMD Ryzen 9             | 5         | 3.62%   |
| Intel Pentium           | 4         | 2.9%    |
| Intel Celeron           | 4         | 2.9%    |
| Intel Pentium Dual-Core | 3         | 2.17%   |
| Intel Core 2 Quad       | 3         | 2.17%   |
| Intel Atom              | 2         | 1.45%   |
| AMD Ryzen 7 PRO         | 2         | 1.45%   |
| AMD Ryzen 5 PRO         | 2         | 1.45%   |
| Intel Xeon Gold         | 1         | 0.72%   |
| Intel Xeon              | 1         | 0.72%   |
| Intel Pentium Silver    | 1         | 0.72%   |
| Intel Core m5           | 1         | 0.72%   |
| Intel Core m3           | 1         | 0.72%   |
| Intel Core i9           | 1         | 0.72%   |
| Intel Core 2 Duo        | 1         | 0.72%   |
| Intel Core 2            | 1         | 0.72%   |
| AMD Phenom II X4        | 1         | 0.72%   |
| AMD FX                  | 1         | 0.72%   |
| AMD E2                  | 1         | 0.72%   |
| AMD Athlon II X4        | 1         | 0.72%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 51        | 36.96%  |
| 2       | 40        | 28.99%  |
| 6       | 18        | 13.04%  |
| 8       | 16        | 11.59%  |
| 16      | 4         | 2.9%    |
| 12      | 3         | 2.17%   |
| 1       | 2         | 1.45%   |
| 36      | 1         | 0.72%   |
| 32      | 1         | 0.72%   |
| 14      | 1         | 0.72%   |
| Unknown | 1         | 0.72%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 136       | 98.55%  |
| 2      | 2         | 1.45%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 107       | 77.54%  |
| 1       | 30        | 21.74%  |
| Unknown | 1         | 0.72%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 137       | 99.28%  |
| 32-bit         | 1         | 0.72%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 34        | 23.78%  |
| 0x306c3    | 13        | 9.09%   |
| 0x806ea    | 5         | 3.5%    |
| 0x40651    | 5         | 3.5%    |
| 0x206a7    | 5         | 3.5%    |
| 0x906e9    | 4         | 2.8%    |
| 0x806c1    | 4         | 2.8%    |
| 0x406e3    | 4         | 2.8%    |
| 0x1067a    | 4         | 2.8%    |
| 0x906ea    | 3         | 2.1%    |
| 0x806eb    | 3         | 2.1%    |
| 0x506e3    | 3         | 2.1%    |
| 0x306d4    | 3         | 2.1%    |
| 0x20655    | 3         | 2.1%    |
| 0x08701013 | 3         | 2.1%    |
| 0xa0655    | 2         | 1.4%    |
| 0x906ed    | 2         | 1.4%    |
| 0x806ec    | 2         | 1.4%    |
| 0x806d1    | 2         | 1.4%    |
| 0x706a1    | 2         | 1.4%    |
| 0x306a9    | 2         | 1.4%    |
| 0x10677    | 2         | 1.4%    |
| 0x0a50000c | 2         | 1.4%    |
| 0x0a20120a | 2         | 1.4%    |
| 0x08701021 | 2         | 1.4%    |
| 0x08600106 | 2         | 1.4%    |
| 0x08600103 | 2         | 1.4%    |
| 0x08108102 | 2         | 1.4%    |
| 0xb06e0    | 1         | 0.7%    |
| 0xa0671    | 1         | 0.7%    |
| 0x906c0    | 1         | 0.7%    |
| 0x806e9    | 1         | 0.7%    |
| 0x6fb      | 1         | 0.7%    |
| 0x6f6      | 1         | 0.7%    |
| 0x50654    | 1         | 0.7%    |
| 0x406f1    | 1         | 0.7%    |
| 0x406c4    | 1         | 0.7%    |
| 0x20652    | 1         | 0.7%    |
| 0x106c2    | 1         | 0.7%    |
| 0x0a601203 | 1         | 0.7%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 28        | 20.29%  |
| Haswell          | 21        | 15.22%  |
| Zen 2            | 13        | 9.42%   |
| Skylake          | 11        | 7.97%   |
| Zen 3            | 7         | 5.07%   |
| TigerLake        | 6         | 4.35%   |
| Penryn           | 6         | 4.35%   |
| Unknown          | 6         | 4.35%   |
| SandyBridge      | 5         | 3.62%   |
| Westmere         | 4         | 2.9%    |
| Broadwell        | 4         | 2.9%    |
| Zen+             | 3         | 2.17%   |
| IvyBridge        | 3         | 2.17%   |
| Icelake          | 3         | 2.17%   |
| CometLake        | 3         | 2.17%   |
| Alderlake Hybrid | 3         | 2.17%   |
| K10              | 2         | 1.45%   |
| Goldmont plus    | 2         | 1.45%   |
| Core             | 2         | 1.45%   |
| Zen              | 1         | 0.72%   |
| Silvermont       | 1         | 0.72%   |
| Piledriver       | 1         | 0.72%   |
| Goldmont         | 1         | 0.72%   |
| Excavator        | 1         | 0.72%   |
| Bonnell          | 1         | 0.72%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 87        | 51.79%  |
| Nvidia | 52        | 30.95%  |
| AMD    | 29        | 17.26%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 8         | 4.65%   |
| Intel UHD Graphics 620                                                      | 7         | 4.07%   |
| AMD Renoir                                                                  | 7         | 4.07%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 6         | 3.49%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 6         | 3.49%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 5         | 2.91%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 5         | 2.91%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 4         | 2.33%   |
| Intel HD Graphics 530                                                       | 4         | 2.33%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4         | 2.33%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 4         | 2.33%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 3         | 1.74%   |
| Nvidia GA107GLM [RTX A1000 Laptop GPU]                                      | 3         | 1.74%   |
| Intel Alder Lake-HX GT1 [UHD Graphics 770]                                  | 3         | 1.74%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 3         | 1.74%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 2         | 1.16%   |
| Nvidia GP108M [GeForce MX250]                                               | 2         | 1.16%   |
| Nvidia GP108M [GeForce MX150]                                               | 2         | 1.16%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2         | 1.16%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 2         | 1.16%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2         | 1.16%   |
| Nvidia GK107GLM [Quadro K1100M]                                             | 2         | 1.16%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 2         | 1.16%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 1.16%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 2         | 1.16%   |
| Intel Iris Plus Graphics 640                                                | 2         | 1.16%   |
| Intel HD Graphics 5500                                                      | 2         | 1.16%   |
| Intel HD Graphics 515                                                       | 2         | 1.16%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2         | 1.16%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 2         | 1.16%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                               | 1         | 0.58%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                       | 1         | 0.58%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1         | 0.58%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1         | 0.58%   |
| Nvidia GT218 [NVS 300]                                                      | 1         | 0.58%   |
| Nvidia GT218 [GeForce G210]                                                 | 1         | 0.58%   |
| Nvidia GT216M [GeForce GT 330M]                                             | 1         | 0.58%   |
| Nvidia GT215M [GeForce GTS 250M]                                            | 1         | 0.58%   |
| Nvidia GP107GL [Quadro P1000]                                               | 1         | 0.58%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1         | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 56        | 40.58%  |
| 1 x Nvidia     | 27        | 19.57%  |
| Intel + Nvidia | 26        | 18.84%  |
| 1 x AMD        | 22        | 15.94%  |
| 2 x AMD        | 4         | 2.9%    |
| Intel + AMD    | 3         | 2.17%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 103       | 74.1%   |
| Proprietary | 30        | 21.58%  |
| Unknown     | 6         | 4.32%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 83        | 59.71%  |
| 3.01-4.0   | 15        | 10.79%  |
| 0.01-0.5   | 13        | 9.35%   |
| 1.01-2.0   | 12        | 8.63%   |
| 0.51-1.0   | 9         | 6.47%   |
| 8.01-16.0  | 5         | 3.6%    |
| 5.01-6.0   | 2         | 1.44%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 24        | 15.29%  |
| Chimei Innolux          | 21        | 13.38%  |
| LG Display              | 15        | 9.55%   |
| AU Optronics            | 11        | 7.01%   |
| Hewlett-Packard         | 9         | 5.73%   |
| AOC                     | 8         | 5.1%    |
| Dell                    | 7         | 4.46%   |
| BOE                     | 7         | 4.46%   |
| Sharp                   | 6         | 3.82%   |
| Iiyama                  | 6         | 3.82%   |
| Goldstar                | 6         | 3.82%   |
| Philips                 | 5         | 3.18%   |
| Apple                   | 5         | 3.18%   |
| BenQ                    | 4         | 2.55%   |
| Medion                  | 3         | 1.91%   |
| Chi Mei Optoelectronics | 3         | 1.91%   |
| Ancor Communications    | 3         | 1.91%   |
| Eizo                    | 2         | 1.27%   |
| Videoseven              | 1         | 0.64%   |
| Sony                    | 1         | 0.64%   |
| PAR                     | 1         | 0.64%   |
| PANDA                   | 1         | 0.64%   |
| Panasonic               | 1         | 0.64%   |
| MSI                     | 1         | 0.64%   |
| Lenovo                  | 1         | 0.64%   |
| Fujitsu Siemens         | 1         | 0.64%   |
| CSO                     | 1         | 0.64%   |
| Belinea                 | 1         | 0.64%   |
| Aosiman                 | 1         | 0.64%   |
| Acer                    | 1         | 0.64%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 2         | 1.25%   |
| Sharp LCD Monitor SHP13F8 3200x1800 346x194mm 15.6-inch               | 2         | 1.25%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch      | 2         | 1.25%   |
| Chimei Innolux LCD Monitor CMN1604 1920x1080 355x199mm 16.0-inch      | 2         | 1.25%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 2         | 1.25%   |
| AOC 2250W AOC2250 1920x1080 477x268mm 21.5-inch                       | 2         | 1.25%   |
| Videoseven L27ADS IGM2700 1920x1080 598x336mm 27.0-inch               | 1         | 0.63%   |
| Sony LCD Monitor SNY05FA 1366x768 340x190mm 15.3-inch                 | 1         | 0.63%   |
| Sharp LCD Monitor SHP1516 3840x2400 336x210mm 15.6-inch               | 1         | 0.63%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch               | 1         | 0.63%   |
| Samsung Electronics U28H75x SAM0DFE 3840x2160 608x345mm 27.5-inch     | 1         | 0.63%   |
| Samsung Electronics T24B350 SAM093E 1920x1080 530x300mm 24.0-inch     | 1         | 0.63%   |
| Samsung Electronics SyncMaster SAM0612 1920x1080 604x342mm 27.3-inch  | 1         | 0.63%   |
| Samsung Electronics SyncMaster SAM04DF 1360x768 410x230mm 18.5-inch   | 1         | 0.63%   |
| Samsung Electronics SMT27A950 SAM080F 1920x1080 598x336mm 27.0-inch   | 1         | 0.63%   |
| Samsung Electronics SM2333T SAM0737 1920x1080 510x290mm 23.1-inch     | 1         | 0.63%   |
| Samsung Electronics S27D390 SAM0B67 1920x1080 598x336mm 27.0-inch     | 1         | 0.63%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 0.63%   |
| Samsung Electronics Odyssey G8 SAM7231 3440x1440 809x354mm 34.8-inch  | 1         | 0.63%   |
| Samsung Electronics LCD Monitor U28E590 3840x2160                     | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SEC444E 1600x900 310x174mm 14.0-inch  | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SDC5844 1920x1080 344x194mm 15.5-inch | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch  | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch  | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SDC4159 1920x1080 344x194mm 15.5-inch | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SDC4141 3840x2160 344x194mm 15.5-inch | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SAM0B60 1920x1080 887x500mm 40.1-inch | 1         | 0.63%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 480x270mm 21.7-inch | 1         | 0.63%   |
| Samsung Electronics C49HG9x SAM0E5E 1920x1080 1200x340mm 49.1-inch    | 1         | 0.63%   |
| Samsung Electronics C49HG9x SAM0E5D 1920x1080 1200x340mm 49.1-inch    | 1         | 0.63%   |
| Samsung Electronics C27R50x SAM0F9D 1920x1080 600x340mm 27.2-inch     | 1         | 0.63%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 1         | 0.63%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1         | 0.63%   |
| Philips PHL BDM3270 PHL08E7 2560x1440 708x398mm 32.0-inch             | 1         | 0.63%   |
| Philips PHL 346B1C PHL095C 3440x1440 797x334mm 34.0-inch              | 1         | 0.63%   |
| Philips PHL 275C5 PHLC0E4 1920x1080 598x336mm 27.0-inch               | 1         | 0.63%   |
| Philips PHL 272E1GJ PHLC245 1920x1080 598x336mm 27.0-inch             | 1         | 0.63%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 73        | 50.69%  |
| 1366x768 (WXGA)    | 15        | 10.42%  |
| 3840x2160 (4K)     | 13        | 9.03%   |
| 2560x1440 (QHD)    | 8         | 5.56%   |
| 1920x1200 (WUXGA)  | 5         | 3.47%   |
| 1600x900 (HD+)     | 4         | 2.78%   |
| 2880x1800          | 3         | 2.08%   |
| 1680x1050 (WSXGA+) | 3         | 2.08%   |
| 3840x1080          | 2         | 1.39%   |
| 3440x1440          | 2         | 1.39%   |
| 3200x1800 (QHD+)   | 2         | 1.39%   |
| 1440x900 (WXGA+)   | 2         | 1.39%   |
| 1360x768           | 2         | 1.39%   |
| 1280x1024 (SXGA)   | 2         | 1.39%   |
| 3840x2400          | 1         | 0.69%   |
| 3072x1920          | 1         | 0.69%   |
| 2560x1600          | 1         | 0.69%   |
| 2520x1680          | 1         | 0.69%   |
| 2160x1440          | 1         | 0.69%   |
| 1280x800 (WXGA)    | 1         | 0.69%   |
| 1024x768 (XGA)     | 1         | 0.69%   |
| Unknown            | 1         | 0.69%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 35        | 22.29%  |
| 27      | 20        | 12.74%  |
| 14      | 14        | 8.92%   |
| 13      | 14        | 8.92%   |
| 24      | 11        | 7.01%   |
| 17      | 11        | 7.01%   |
| 23      | 10        | 6.37%   |
| 21      | 8         | 5.1%    |
| 16      | 7         | 4.46%   |
| Unknown | 5         | 3.18%   |
| 22      | 3         | 1.91%   |
| 72      | 2         | 1.27%   |
| 40      | 2         | 1.27%   |
| 34      | 2         | 1.27%   |
| 32      | 2         | 1.27%   |
| 18      | 2         | 1.27%   |
| 59      | 1         | 0.64%   |
| 49      | 1         | 0.64%   |
| 46      | 1         | 0.64%   |
| 33      | 1         | 0.64%   |
| 31      | 1         | 0.64%   |
| 28      | 1         | 0.64%   |
| 25      | 1         | 0.64%   |
| 19      | 1         | 0.64%   |
| 11      | 1         | 0.64%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 60        | 39.22%  |
| 501-600     | 37        | 24.18%  |
| 401-500     | 13        | 8.5%    |
| 351-400     | 13        | 8.5%    |
| 201-300     | 9         | 5.88%   |
| Unknown     | 5         | 3.27%   |
| 701-800     | 4         | 2.61%   |
| 601-700     | 4         | 2.61%   |
| 801-900     | 3         | 1.96%   |
| 1001-1500   | 3         | 1.96%   |
| 1501-2000   | 2         | 1.31%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 107       | 78.1%   |
| 16/10   | 19        | 13.87%  |
| Unknown | 3         | 2.19%   |
| 5/4     | 2         | 1.46%   |
| 3/2     | 2         | 1.46%   |
| 21/9    | 2         | 1.46%   |
| 4/3     | 1         | 0.73%   |
| 32/9    | 1         | 0.73%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 35        | 22.44%  |
| 201-250        | 28        | 17.95%  |
| 81-90          | 22        | 14.1%   |
| 301-350        | 20        | 12.82%  |
| 121-130        | 8         | 5.13%   |
| 351-500        | 7         | 4.49%   |
| 71-80          | 6         | 3.85%   |
| 111-120        | 6         | 3.85%   |
| Unknown        | 5         | 3.21%   |
| 251-300        | 4         | 2.56%   |
| 501-1000       | 4         | 2.56%   |
| More than 1000 | 3         | 1.92%   |
| 141-150        | 3         | 1.92%   |
| 131-140        | 2         | 1.28%   |
| 51-60          | 1         | 0.64%   |
| 151-200        | 1         | 0.64%   |
| 91-100         | 1         | 0.64%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 48        | 31.58%  |
| 121-160       | 43        | 28.29%  |
| 101-120       | 32        | 21.05%  |
| 161-240       | 13        | 8.55%   |
| More than 240 | 8         | 5.26%   |
| Unknown       | 5         | 3.29%   |
| 1-50          | 3         | 1.97%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 105       | 75%     |
| 2     | 27        | 19.29%  |
| 0     | 6         | 4.29%   |
| 3     | 2         | 1.43%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 94        | 46.08%  |
| Realtek Semiconductor           | 58        | 28.43%  |
| Qualcomm Atheros                | 18        | 8.82%   |
| Broadcom                        | 13        | 6.37%   |
| Marvell Technology Group        | 4         | 1.96%   |
| MediaTek                        | 3         | 1.47%   |
| Sierra Wireless                 | 2         | 0.98%   |
| DisplayLink                     | 2         | 0.98%   |
| TP-Link                         | 1         | 0.49%   |
| Shenzhen Goodix Technology      | 1         | 0.49%   |
| Ralink Technology               | 1         | 0.49%   |
| Qualcomm Atheros Communications | 1         | 0.49%   |
| Lenovo                          | 1         | 0.49%   |
| JMicron Technology              | 1         | 0.49%   |
| Huawei Technologies             | 1         | 0.49%   |
| Broadcom Limited                | 1         | 0.49%   |
| ASIX Electronics                | 1         | 0.49%   |
| Unknown                         | 1         | 0.49%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 41        | 16.53%  |
| Intel Wi-Fi 6 AX200                                                            | 16        | 6.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 7         | 2.82%   |
| Realtek RTL8125 2.5GbE Controller                                              | 6         | 2.42%   |
| Intel I211 Gigabit Network Connection                                          | 6         | 2.42%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 5         | 2.02%   |
| Intel Wireless 8265 / 8275                                                     | 5         | 2.02%   |
| Intel Wireless 8260                                                            | 5         | 2.02%   |
| Intel Ethernet Controller I225-V                                               | 5         | 2.02%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 5         | 2.02%   |
| Intel Wireless 7260                                                            | 4         | 1.61%   |
| Intel Ethernet Connection (2) I219-V                                           | 4         | 1.61%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 3         | 1.21%   |
| Intel Wireless 3160                                                            | 3         | 1.21%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                         | 3         | 1.21%   |
| Intel Ethernet Connection I219-V                                               | 3         | 1.21%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 3         | 1.21%   |
| Intel Alder Lake-S PCH CNVi WiFi                                               | 3         | 1.21%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 3         | 1.21%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 2         | 0.81%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 2         | 0.81%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 2         | 0.81%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 2         | 0.81%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                  | 2         | 0.81%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.81%   |
| Intel Wireless-AC 9260                                                         | 2         | 0.81%   |
| Intel Wireless 7265                                                            | 2         | 0.81%   |
| Intel Wireless 3165                                                            | 2         | 0.81%   |
| Intel Wi-Fi 6 AX201                                                            | 2         | 0.81%   |
| Intel Tiger Lake PCH CNVi WiFi                                                 | 2         | 0.81%   |
| Intel Ethernet Connection I217-V                                               | 2         | 0.81%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 0.81%   |
| Intel Ethernet Connection (6) I219-V                                           | 2         | 0.81%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 0.81%   |
| Intel Ethernet Connection (2) I218-V                                           | 2         | 0.81%   |
| Intel Ethernet Connection (17) I219-LM                                         | 2         | 0.81%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 2         | 0.81%   |
| DisplayLink Dell D3100 Docking Station                                         | 2         | 0.81%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                             | 2         | 0.81%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 2         | 0.81%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 72        | 61.02%  |
| Qualcomm Atheros                | 15        | 12.71%  |
| Realtek Semiconductor           | 11        | 9.32%   |
| Broadcom                        | 10        | 8.47%   |
| MediaTek                        | 3         | 2.54%   |
| Sierra Wireless                 | 2         | 1.69%   |
| TP-Link                         | 1         | 0.85%   |
| Ralink Technology               | 1         | 0.85%   |
| Qualcomm Atheros Communications | 1         | 0.85%   |
| Marvell Technology Group        | 1         | 0.85%   |
| Broadcom Limited                | 1         | 0.85%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 16        | 13.45%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 5         | 4.2%    |
| Intel Wireless 8265 / 8275                                     | 5         | 4.2%    |
| Intel Wireless 8260                                            | 5         | 4.2%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 5         | 4.2%    |
| Intel Wireless 7260                                            | 4         | 3.36%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 3         | 2.52%   |
| Intel Wireless 3160                                            | 3         | 2.52%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 3         | 2.52%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 2.52%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 3         | 2.52%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2         | 1.68%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 1.68%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 1.68%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 1.68%   |
| Intel Wireless-AC 9260                                         | 2         | 1.68%   |
| Intel Wireless 7265                                            | 2         | 1.68%   |
| Intel Wireless 3165                                            | 2         | 1.68%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 1.68%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 2         | 1.68%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 1.68%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 2         | 1.68%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 1.68%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1         | 0.84%   |
| Sierra Wireless EM7455                                         | 1         | 0.84%   |
| Sierra Wireless EM7305 Modem                                   | 1         | 0.84%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.84%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1         | 0.84%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 0.84%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 0.84%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 0.84%   |
| Realtek 802.11ac NIC                                           | 1         | 0.84%   |
| Ralink RT5370 Wireless Adapter                                 | 1         | 0.84%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 0.84%   |
| Qualcomm Atheros AR9271 802.11n                                | 1         | 0.84%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 0.84%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 0.84%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 1         | 0.84%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 0.84%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 0.84%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 55        | 45.08%  |
| Intel                    | 49        | 40.16%  |
| Qualcomm Atheros         | 5         | 4.1%    |
| Broadcom                 | 5         | 4.1%    |
| Marvell Technology Group | 3         | 2.46%   |
| DisplayLink              | 2         | 1.64%   |
| Lenovo                   | 1         | 0.82%   |
| JMicron Technology       | 1         | 0.82%   |
| ASIX Electronics         | 1         | 0.82%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 41        | 32.8%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 7         | 5.6%    |
| Realtek RTL8125 2.5GbE Controller                                              | 6         | 4.8%    |
| Intel I211 Gigabit Network Connection                                          | 6         | 4.8%    |
| Intel Ethernet Controller I225-V                                               | 5         | 4%      |
| Intel Ethernet Connection (2) I219-V                                           | 4         | 3.2%    |
| Intel Ethernet Connection I219-V                                               | 3         | 2.4%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 3         | 2.4%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 2         | 1.6%    |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 1.6%    |
| Intel Ethernet Connection I217-V                                               | 2         | 1.6%    |
| Intel Ethernet Connection I217-LM                                              | 2         | 1.6%    |
| Intel Ethernet Connection (6) I219-V                                           | 2         | 1.6%    |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 1.6%    |
| Intel Ethernet Connection (2) I218-V                                           | 2         | 1.6%    |
| Intel Ethernet Connection (17) I219-LM                                         | 2         | 1.6%    |
| DisplayLink Dell D3100 Docking Station                                         | 2         | 1.6%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.8%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.8%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.8%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.8%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 0.8%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.8%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 0.8%    |
| Lenovo ThinkPad Lan                                                            | 1         | 0.8%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 0.8%    |
| Intel I210 Gigabit Network Connection                                          | 1         | 0.8%    |
| Intel Ethernet controller                                                      | 1         | 0.8%    |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.8%    |
| Intel Ethernet Connection (7) I219-V                                           | 1         | 0.8%    |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.8%    |
| Intel Ethernet Connection (6) I219-LM                                          | 1         | 0.8%    |
| Intel Ethernet Connection (5) I219-LM                                          | 1         | 0.8%    |
| Intel Ethernet Connection (3) I219-LM                                          | 1         | 0.8%    |
| Intel Ethernet Connection (3) I218-V                                           | 1         | 0.8%    |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 0.8%    |
| Intel Ethernet Connection (17) I219-V                                          | 1         | 0.8%    |
| Intel Ethernet Connection (14) I219-LM                                         | 1         | 0.8%    |
| Intel Ethernet Connection (11) I219-V                                          | 1         | 0.8%    |
| Intel 82577LC Gigabit Network Connection                                       | 1         | 0.8%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 114       | 49.35%  |
| WiFi     | 113       | 48.92%  |
| Modem    | 2         | 0.87%   |
| Unknown  | 2         | 0.87%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 82        | 55.41%  |
| Ethernet | 66        | 44.59%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 80        | 57.97%  |
| 1     | 52        | 37.68%  |
| 3     | 6         | 4.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 108       | 77.7%   |
| Yes  | 31        | 22.3%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 64        | 65.31%  |
| Foxconn / Hon Hai               | 6         | 6.12%   |
| Qualcomm Atheros Communications | 4         | 4.08%   |
| IMC Networks                    | 4         | 4.08%   |
| Cambridge Silicon Radio         | 4         | 4.08%   |
| Realtek                         | 3         | 3.06%   |
| Apple                           | 3         | 3.06%   |
| Lite-On Technology              | 2         | 2.04%   |
| Hewlett-Packard                 | 2         | 2.04%   |
| Toshiba                         | 1         | 1.02%   |
| Realtek Semiconductor           | 1         | 1.02%   |
| Micro Star International        | 1         | 1.02%   |
| Marvell Semiconductor           | 1         | 1.02%   |
| Broadcom                        | 1         | 1.02%   |
| ASUSTek Computer                | 1         | 1.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 20        | 20.41%  |
| Intel AX200 Bluetooth                                                               | 15        | 15.31%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 8         | 8.16%   |
| Intel AX201 Bluetooth                                                               | 8         | 8.16%   |
| Intel Bluetooth Device                                                              | 5         | 5.1%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 4         | 4.08%   |
| Intel AX210 Bluetooth                                                               | 3         | 3.06%   |
| Realtek 802.11ac WLAN Adapter                                                       | 2         | 2.04%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 2         | 2.04%   |
| Lite-On Bluetooth Device                                                            | 2         | 2.04%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 2.04%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 2.04%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 2.04%   |
| Apple Bluetooth USB Host Controller                                                 | 2         | 2.04%   |
| Toshiba Bluetooth Device                                                            | 1         | 1.02%   |
| Realtek Bluetooth Radio                                                             | 1         | 1.02%   |
| Realtek Bluetooth Radio                                                             | 1         | 1.02%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 1.02%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 1.02%   |
| Micro Star International Motorola Bluetooth 2.1+EDR Device                          | 1         | 1.02%   |
| Marvell Bluetooth and Wireless LAN Composite                                        | 1         | 1.02%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 1.02%   |
| IMC Networks Wireless_Device                                                        | 1         | 1.02%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 1.02%   |
| IMC Networks Bluetooth Module                                                       | 1         | 1.02%   |
| IMC Networks Bluetooth Device                                                       | 1         | 1.02%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 1         | 1.02%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.02%   |
| Foxconn / Hon Hai BT                                                                | 1         | 1.02%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 1.02%   |
| Foxconn / Hon Hai BCM43142A0                                                        | 1         | 1.02%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 1.02%   |
| Broadcom Bluetooth 3.0 Device                                                       | 1         | 1.02%   |
| ASUS BCM20702A0                                                                     | 1         | 1.02%   |
| Apple Bluetooth Host Controller                                                     | 1         | 1.02%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 107       | 56.32%  |
| AMD                                          | 34        | 17.89%  |
| Nvidia                                       | 32        | 16.84%  |
| Logitech                                     | 3         | 1.58%   |
| SteelSeries ApS                              | 2         | 1.05%   |
| Hewlett-Packard                              | 2         | 1.05%   |
| C-Media Electronics                          | 2         | 1.05%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.53%   |
| www.hirestech.com 2012 REV 1.8               | 1         | 0.53%   |
| Sony                                         | 1         | 0.53%   |
| Realtek Semiconductor                        | 1         | 0.53%   |
| Lenovo                                       | 1         | 0.53%   |
| Kingston Technology                          | 1         | 0.53%   |
| Bose                                         | 1         | 0.53%   |
| Apple                                        | 1         | 0.53%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 15        | 6.49%   |
| AMD Family 17h/19h HD Audio Controller                                     | 15        | 6.49%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 13        | 5.63%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 12        | 5.19%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 11        | 4.76%   |
| AMD Starship/Matisse HD Audio Controller                                   | 9         | 3.9%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 6         | 2.6%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 6         | 2.6%    |
| Intel Cannon Lake PCH cAVS                                                 | 6         | 2.6%    |
| Intel 200 Series PCH HD Audio                                              | 6         | 2.6%    |
| Intel Haswell-ULT HD Audio Controller                                      | 5         | 2.16%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 2.16%   |
| Intel 8 Series HD Audio Controller                                         | 5         | 2.16%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4         | 1.73%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 1.73%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 1.73%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 1.73%   |
| Nvidia High Definition Audio Controller                                    | 3         | 1.3%    |
| Nvidia GA106 High Definition Audio Controller                              | 3         | 1.3%    |
| Nvidia Audio device                                                        | 3         | 1.3%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 1.3%    |
| Intel Comet Lake PCH cAVS                                                  | 3         | 1.3%    |
| Intel Broadwell-U Audio Controller                                         | 3         | 1.3%    |
| Intel Alder Lake-S HD Audio Controller                                     | 3         | 1.3%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 1.3%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 1.3%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 3         | 1.3%    |
| Nvidia GP108 High Definition Audio Controller                              | 2         | 0.87%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 0.87%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 0.87%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 0.87%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 0.87%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 2         | 0.87%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2         | 0.87%   |
| Hewlett-Packard USB Audio                                                  | 2         | 0.87%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 0.87%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2         | 0.87%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID             | 1         | 0.43%   |
| www.hirestech.com 2012 REV 1.8 Music Streamer II                           | 1         | 0.43%   |
| SteelSeries ApS SteelSeries Arctis 7                                       | 1         | 0.43%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 29        | 32.58%  |
| SK hynix                     | 15        | 16.85%  |
| Kingston                     | 8         | 8.99%   |
| Micron Technology            | 6         | 6.74%   |
| Crucial                      | 6         | 6.74%   |
| Corsair                      | 6         | 6.74%   |
| Unknown                      | 4         | 4.49%   |
| G.Skill                      | 4         | 4.49%   |
| A-DATA Technology            | 4         | 4.49%   |
| Qimonda                      | 2         | 2.25%   |
| Wilk                         | 1         | 1.12%   |
| Unknown (0x7F7FB5FFFFFFFFFF) | 1         | 1.12%   |
| Timetec                      | 1         | 1.12%   |
| Patriot                      | 1         | 1.12%   |
| Dane-Elec                    | 1         | 1.12%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s     | 3         | 3.16%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                  | 2         | 2.11%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s         | 2         | 2.11%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s         | 2         | 2.11%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s         | 2         | 2.11%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s        | 2         | 2.11%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s         | 2         | 2.11%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s       | 2         | 2.11%   |
| Wilk RAM GR3200S464L22S/16G 16GB SODIMM DDR4 3200MT/s         | 1         | 1.05%   |
| Unknown RAM Module 4GB SODIMM DDR3                            | 1         | 1.05%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                  | 1         | 1.05%   |
| Unknown RAM Module 2GB SODIMM DDR2                            | 1         | 1.05%   |
| Unknown RAM Module 2048MB SODIMM DDR2                         | 1         | 1.05%   |
| Unknown RAM Module 1024MB SODIMM DDR2                         | 1         | 1.05%   |
| Unknown (0x7F7FB5FFFFFFFFFF) RAM Module 1GB DIMM DDR2 667MT/s | 1         | 1.05%   |
| Timetec RAM SD3-1333 8GB SODIMM DDR3 1333MT/s                 | 1         | 1.05%   |
| SK hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s       | 1         | 1.05%   |
| SK hynix RAM Module 4GB DIMM DDR3 1066MT/s                    | 1         | 1.05%   |
| SK hynix RAM Module 4096MB Row Of Chips LPDDR3 2133MT/s       | 1         | 1.05%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 1         | 1.05%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s        | 1         | 1.05%   |
| SK hynix RAM HMCG88MEBSA092N 32GB SODIMM DDR5 4800MT/s        | 1         | 1.05%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s        | 1         | 1.05%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2400MT/s     | 1         | 1.05%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s       | 1         | 1.05%   |
| SK hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s       | 1         | 1.05%   |
| SK hynix RAM HMA82GR7CJR8N-VK 16GB DIMM DDR4 2666MT/s         | 1         | 1.05%   |
| SK hynix RAM HMA82GR7AFR8N-VK 16GB DIMM DDR4 2666MT/s         | 1         | 1.05%   |
| SK hynix RAM HMA81GS6MFR8N-UH 8GB SODIMM DDR4 2400MT/s        | 1         | 1.05%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s        | 1         | 1.05%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                   | 1         | 1.05%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR4 2933MT/s           | 1         | 1.05%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                   | 1         | 1.05%   |
| Samsung RAM Module 4GB SODIMM DDR3 1067MT/s                   | 1         | 1.05%   |
| Samsung RAM Module 16384MB SODIMM DDR4 3200MT/s               | 1         | 1.05%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s         | 1         | 1.05%   |
| Samsung RAM M471B5673FH0-CF8 2048MB SODIMM DDR3 1067MT/s      | 1         | 1.05%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s         | 1         | 1.05%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s         | 1         | 1.05%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s         | 1         | 1.05%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 46        | 56.1%   |
| DDR3   | 21        | 25.61%  |
| DDR2   | 5         | 6.1%    |
| LPDDR3 | 4         | 4.88%   |
| DDR5   | 4         | 4.88%   |
| SDRAM  | 1         | 1.22%   |
| LPDDR4 | 1         | 1.22%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 53        | 65.43%  |
| DIMM         | 22        | 27.16%  |
| Row Of Chips | 6         | 7.41%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 36        | 40.91%  |
| 16384 | 20        | 22.73%  |
| 4096  | 16        | 18.18%  |
| 2048  | 8         | 9.09%   |
| 32768 | 6         | 6.82%   |
| 1024  | 2         | 2.27%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 18        | 21.18%  |
| 3200    | 15        | 17.65%  |
| 1600    | 12        | 14.12%  |
| 2400    | 8         | 9.41%   |
| 2133    | 6         | 7.06%   |
| 3600    | 4         | 4.71%   |
| 4800    | 3         | 3.53%   |
| Unknown | 3         | 3.53%   |
| 1333    | 2         | 2.35%   |
| 800     | 2         | 2.35%   |
| 6400    | 1         | 1.18%   |
| 3534    | 1         | 1.18%   |
| 3500    | 1         | 1.18%   |
| 3400    | 1         | 1.18%   |
| 3266    | 1         | 1.18%   |
| 2933    | 1         | 1.18%   |
| 2666    | 1         | 1.18%   |
| 1867    | 1         | 1.18%   |
| 1334    | 1         | 1.18%   |
| 1067    | 1         | 1.18%   |
| 1066    | 1         | 1.18%   |
| 667     | 1         | 1.18%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 3         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Computers | Percent |
|--------------------------|-----------|---------|
| HP OfficeJet 6950        | 1         | 33.33%  |
| HP Officejet 6600        | 1         | 33.33%  |
| HP OfficeJet 5200 series | 1         | 33.33%  |

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
| Chicony Electronics                    | 23        | 26.44%  |
| Microdia                               | 12        | 13.79%  |
| IMC Networks                           | 9         | 10.34%  |
| Logitech                               | 6         | 6.9%    |
| Samsung Electronics                    | 4         | 4.6%    |
| Quanta                                 | 4         | 4.6%    |
| Ricoh                                  | 3         | 3.45%   |
| Realtek Semiconductor                  | 3         | 3.45%   |
| Luxvisions Innotech Limited            | 3         | 3.45%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 3.45%   |
| Alcor Micro                            | 3         | 3.45%   |
| Sunplus Innovation Technology          | 2         | 2.3%    |
| Bison Electronics                      | 2         | 2.3%    |
| Apple                                  | 2         | 2.3%    |
| Acer                                   | 2         | 2.3%    |
| YGTek                                  | 1         | 1.15%   |
| ShineTech                              | 1         | 1.15%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 1.15%   |
| Lite-On Technology                     | 1         | 1.15%   |
| Huawei Technologies                    | 1         | 1.15%   |
| ALi                                    | 1         | 1.15%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                    | 5         | 5.75%   |
| IMC Networks USB2.0 HD UVC WebCam                | 5         | 5.75%   |
| Samsung Galaxy series, misc. (MTP mode)          | 4         | 4.6%    |
| Logitech B525 HD Webcam                          | 3         | 3.45%   |
| IMC Networks Integrated Camera                   | 3         | 3.45%   |
| Chicony Integrated Camera                        | 3         | 3.45%   |
| Realtek Integrated_Webcam_HD                     | 2         | 2.3%    |
| Quanta HD User Facing                            | 2         | 2.3%    |
| Microdia Integrated_Webcam_FHD                   | 2         | 2.3%    |
| Microdia Integrated Webcam                       | 2         | 2.3%    |
| Luxvisions Innotech Limited HP HD Camera         | 2         | 2.3%    |
| Chicony Integrated IR Camera                     | 2         | 2.3%    |
| Chicony Integrated Camera (1280x720@30)          | 2         | 2.3%    |
| Chicony HP Wide Vision HD Camera                 | 2         | 2.3%    |
| Chicony HP HD Camera                             | 2         | 2.3%    |
| Cheng Uei Precision Industry (Foxlink) HD Camera | 2         | 2.3%    |
| Alcor Micro USB 2.0 Camera                       | 2         | 2.3%    |
| YGTek Webcam                                     | 1         | 1.15%   |
| Sunplus HP HD Webcam [Fixed]                     | 1         | 1.15%   |
| Sunplus HD WebCam                                | 1         | 1.15%   |
| ShineTech HD Camera                              | 1         | 1.15%   |
| Shenzhen Kingcome Optoelectronic 720p HD Camera  | 1         | 1.15%   |
| Ricoh USB2.0 Camera                              | 1         | 1.15%   |
| Ricoh Sony Visual Communication Camera           | 1         | 1.15%   |
| Ricoh Sony Vaio Integrated Webcam                | 1         | 1.15%   |
| Realtek HP Truevision HD                         | 1         | 1.15%   |
| Quanta HP Wide Vision HD Camera                  | 1         | 1.15%   |
| Quanta HP Webcam                                 | 1         | 1.15%   |
| Microdia Webcam Vitade AF                        | 1         | 1.15%   |
| Microdia Webcam                                  | 1         | 1.15%   |
| Microdia USB 2.0 Camera                          | 1         | 1.15%   |
| Luxvisions Innotech Limited HP 5MP Camera        | 1         | 1.15%   |
| Logitech Webcam C270                             | 1         | 1.15%   |
| Logitech HD Webcam C910                          | 1         | 1.15%   |
| Logitech HD Pro Webcam C920                      | 1         | 1.15%   |
| Lite-On HP Full-HD Camera                        | 1         | 1.15%   |
| IMC Networks HD Camera                           | 1         | 1.15%   |
| Huawei HiCamera                                  | 1         | 1.15%   |
| Chicony USB2.0 VGA UVC WebCam                    | 1         | 1.15%   |
| Chicony USB2.0 HD UVC WebCam                     | 1         | 1.15%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 9         | 39.13%  |
| Validity Sensors           | 5         | 21.74%  |
| Shenzhen Goodix Technology | 5         | 21.74%  |
| Upek                       | 1         | 4.35%   |
| LighTuning Technology      | 1         | 4.35%   |
| Elan Microelectronics      | 1         | 4.35%   |
| AuthenTec                  | 1         | 4.35%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 4         | 17.39%  |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 13.04%  |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 2         | 8.7%    |
| Shenzhen Goodix  Fingerprint Device                                        | 2         | 8.7%    |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 4.35%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 4.35%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 4.35%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 4.35%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 4.35%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 4.35%   |
| Synaptics UWP WBDI                                                         | 1         | 4.35%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 4.35%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 4.35%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 4.35%   |
| Elan ELAN:Fingerprint                                                      | 1         | 4.35%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 4.35%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 5         | 45.45%  |
| Gemalto (was Gemplus) | 3         | 27.27%  |
| Broadcom              | 3         | 27.27%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 5         | 45.45%  |
| Gemalto (was Gemplus) Prox SU USB PC Link Reader                             | 2         | 18.18%  |
| Broadcom 58200                                                               | 2         | 18.18%  |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 9.09%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 9.09%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 82        | 58.16%  |
| 1     | 41        | 29.08%  |
| 2     | 15        | 10.64%  |
| 3     | 3         | 2.13%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 23        | 30.67%  |
| Graphics card            | 15        | 20%     |
| Chipcard                 | 7         | 9.33%   |
| Multimedia controller    | 6         | 8%      |
| Net/wireless             | 5         | 6.67%   |
| Network                  | 4         | 5.33%   |
| Communication controller | 4         | 5.33%   |
| Unassigned class         | 3         | 4%      |
| Card reader              | 3         | 4%      |
| Net/ethernet             | 2         | 2.67%   |
| Sound                    | 1         | 1.33%   |
| Camera                   | 1         | 1.33%   |
| Bluetooth                | 1         | 1.33%   |

