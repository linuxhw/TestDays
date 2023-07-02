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

Total: 177

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 20        | 14.29%  |
| Ubuntu 22.04                 | 10        | 7.14%   |
| Ubuntu 18.04                 | 10        | 7.14%   |
| Ubuntu 21.04                 | 4         | 2.86%   |
| Linux Mint 20.3              | 4         | 2.86%   |
| Ubuntu 20.10                 | 3         | 2.14%   |
| Pop!_OS 22.04                | 3         | 2.14%   |
| Pop!_OS 21.04                | 3         | 2.14%   |
| openSUSE Tumbleweed-XXXXXXXX | 3         | 2.14%   |
| OpenMandriva 4.2             | 3         | 2.14%   |
| Fedora 37                    | 3         | 2.14%   |
| Fedora 32                    | 3         | 2.14%   |
| Xubuntu 20.04                | 2         | 1.43%   |
| Ubuntu 18.10                 | 2         | 1.43%   |
| ROSA R9                      | 2         | 1.43%   |
| Pop!_OS 21.10                | 2         | 1.43%   |
| openSUSE Leap-15.2           | 2         | 1.43%   |
| OpenMandriva 4.90            | 2         | 1.43%   |
| OpenMandriva 23.03           | 2         | 1.43%   |
| LMDE 4                       | 2         | 1.43%   |
| Kubuntu 22.04                | 2         | 1.43%   |
| Debian 10                    | 2         | 1.43%   |
| ArcoLinux Rolling            | 2         | 1.43%   |
| Zorin 16                     | 1         | 0.71%   |
| Xubuntu 18.04                | 1         | 0.71%   |
| Xubuntu 16.04                | 1         | 0.71%   |
| UbuntuDDE 20.04              | 1         | 0.71%   |
| Ubuntu MATE 21.10            | 1         | 0.71%   |
| Ubuntu MATE 20.04            | 1         | 0.71%   |
| Ubuntu 22.10                 | 1         | 0.71%   |
| Ubuntu 19.10                 | 1         | 0.71%   |
| RHEL 8                       | 1         | 0.71%   |
| Pop!_OS 20.10                | 1         | 0.71%   |
| Pop!_OS 20.04                | 1         | 0.71%   |
| Parrot 5.3                   | 1         | 0.71%   |
| Parrot 5.1                   | 1         | 0.71%   |
| openSUSE Leap-15.4           | 1         | 0.71%   |
| openSUSE Leap-15.3           | 1         | 0.71%   |
| openSUSE Leap-15.1           | 1         | 0.71%   |
| OpenMandriva 4.3             | 1         | 0.71%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 49        | 36.84%  |
| Pop!_OS      | 9         | 6.77%   |
| Fedora       | 9         | 6.77%   |
| OpenMandriva | 8         | 6.02%   |
| openSUSE     | 7         | 5.26%   |
| Linux Mint   | 6         | 4.51%   |
| Xubuntu      | 4         | 3.01%   |
| Kubuntu      | 4         | 3.01%   |
| Manjaro      | 3         | 2.26%   |
| Debian       | 3         | 2.26%   |
| Ubuntu MATE  | 2         | 1.5%    |
| ROSA         | 2         | 1.5%    |
| Parrot       | 2         | 1.5%    |
| Lubuntu      | 2         | 1.5%    |
| LMDE         | 2         | 1.5%    |
| KDE neon     | 2         | 1.5%    |
| Kali         | 2         | 1.5%    |
| Endless      | 2         | 1.5%    |
| Elementary   | 2         | 1.5%    |
| ArcoLinux    | 2         | 1.5%    |
| Arch         | 2         | 1.5%    |
| Zorin        | 1         | 0.75%   |
| UbuntuDDE    | 1         | 0.75%   |
| RHEL         | 1         | 0.75%   |
| Mageia       | 1         | 0.75%   |
| Gentoo       | 1         | 0.75%   |
| Garuda Linux | 1         | 0.75%   |
| Clear Linux  | 1         | 0.75%   |
| CentOS       | 1         | 0.75%   |
| BlackPanther | 1         | 0.75%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.8.0-43-generic                | 3         | 2.07%   |
| 5.15.0-52-generic               | 3         | 2.07%   |
| 5.11.0-27-generic               | 3         | 2.07%   |
| 5.10.14-desktop-1omv4002        | 3         | 2.07%   |
| 6.2.6-desktop-1omv2390          | 2         | 1.38%   |
| 6.2.14-200.fc37.x86_64          | 2         | 1.38%   |
| 5.8.0-59-generic                | 2         | 1.38%   |
| 5.4.0-96-generic                | 2         | 1.38%   |
| 5.4.0-90-generic                | 2         | 1.38%   |
| 5.4.0-47-generic                | 2         | 1.38%   |
| 5.4.0-42-generic                | 2         | 1.38%   |
| 5.4.0-122-generic               | 2         | 1.38%   |
| 5.3.0-46-generic                | 2         | 1.38%   |
| 5.19.0-35-generic               | 2         | 1.38%   |
| 5.18.12-desktop-3omv4090        | 2         | 1.38%   |
| 5.16.11-76051611-generic        | 2         | 1.38%   |
| 5.11.0-34-generic               | 2         | 1.38%   |
| 5.11.0-17-generic               | 2         | 1.38%   |
| 5.0.0-23-generic                | 2         | 1.38%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 2         | 1.38%   |
| 4.19.0-17-amd64                 | 2         | 1.38%   |
| 6.3.1-arch2-1                   | 1         | 0.69%   |
| 6.1.8-060108-generic            | 1         | 0.69%   |
| 6.1.22-gentoo-dist              | 1         | 0.69%   |
| 6.1.10-200.fc37.x86_64          | 1         | 0.69%   |
| 6.1.0-1parrot1-amd64            | 1         | 0.69%   |
| 6.0.6-76060006-generic          | 1         | 0.69%   |
| 6.0.0-kali3-amd64               | 1         | 0.69%   |
| 5.9.13-zen1-1-zen               | 1         | 0.69%   |
| 5.9.10-200.fc33.x86_64          | 1         | 0.69%   |
| 5.8.11-050811-generic           | 1         | 0.69%   |
| 5.8.0-63-generic                | 1         | 0.69%   |
| 5.8.0-55-generic                | 1         | 0.69%   |
| 5.8.0-44-generic                | 1         | 0.69%   |
| 5.8.0-31-generic                | 1         | 0.69%   |
| 5.8.0-26-generic                | 1         | 0.69%   |
| 5.8.0-20-generic                | 1         | 0.69%   |
| 5.8.0-14-generic                | 1         | 0.69%   |
| 5.7.6-201.fc32.x86_64           | 1         | 0.69%   |
| 5.7.19-desktop-3.mga7           | 1         | 0.69%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 19        | 13.77%  |
| 5.11.0  | 14        | 10.14%  |
| 5.15.0  | 13        | 9.42%   |
| 5.8.0   | 10        | 7.25%   |
| 5.3.0   | 6         | 4.35%   |
| 5.19.0  | 6         | 4.35%   |
| 4.18.0  | 6         | 4.35%   |
| 5.13.0  | 4         | 2.9%    |
| 4.15.0  | 4         | 2.9%    |
| 5.10.14 | 3         | 2.17%   |
| 5.0.0   | 3         | 2.17%   |
| 6.2.6   | 2         | 1.45%   |
| 6.2.14  | 2         | 1.45%   |
| 5.7.0   | 2         | 1.45%   |
| 5.3.18  | 2         | 1.45%   |
| 5.18.12 | 2         | 1.45%   |
| 5.16.11 | 2         | 1.45%   |
| 5.10.0  | 2         | 1.45%   |
| 4.9.20  | 2         | 1.45%   |
| 4.19.0  | 2         | 1.45%   |
| 6.3.1   | 1         | 0.72%   |
| 6.1.8   | 1         | 0.72%   |
| 6.1.22  | 1         | 0.72%   |
| 6.1.10  | 1         | 0.72%   |
| 6.1.0   | 1         | 0.72%   |
| 6.0.6   | 1         | 0.72%   |
| 6.0.0   | 1         | 0.72%   |
| 5.9.13  | 1         | 0.72%   |
| 5.9.10  | 1         | 0.72%   |
| 5.8.11  | 1         | 0.72%   |
| 5.7.6   | 1         | 0.72%   |
| 5.7.19  | 1         | 0.72%   |
| 5.7.14  | 1         | 0.72%   |
| 5.7.1   | 1         | 0.72%   |
| 5.6.3   | 1         | 0.72%   |
| 5.5.8   | 1         | 0.72%   |
| 5.18.5  | 1         | 0.72%   |
| 5.18.0  | 1         | 0.72%   |
| 5.16.7  | 1         | 0.72%   |
| 5.16.2  | 1         | 0.72%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 19        | 13.77%  |
| 5.15    | 15        | 10.87%  |
| 5.11    | 14        | 10.14%  |
| 5.8     | 11        | 7.97%   |
| 5.3     | 8         | 5.8%    |
| 5.10    | 7         | 5.07%   |
| 4.18    | 7         | 5.07%   |
| 5.7     | 6         | 4.35%   |
| 5.19    | 6         | 4.35%   |
| 5.13    | 5         | 3.62%   |
| 6.2     | 4         | 2.9%    |
| 6.1     | 4         | 2.9%    |
| 5.18    | 4         | 2.9%    |
| 5.16    | 4         | 2.9%    |
| 4.15    | 4         | 2.9%    |
| 5.0     | 3         | 2.17%   |
| 6.0     | 2         | 1.45%   |
| 5.9     | 2         | 1.45%   |
| 5.14    | 2         | 1.45%   |
| 5.12    | 2         | 1.45%   |
| 4.9     | 2         | 1.45%   |
| 4.19    | 2         | 1.45%   |
| 6.3     | 1         | 0.72%   |
| 5.6     | 1         | 0.72%   |
| 5.5     | 1         | 0.72%   |
| 4.4     | 1         | 0.72%   |
| 4.12    | 1         | 0.72%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 127       | 98.45%  |
| i686   | 2         | 1.55%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 60        | 45.11%  |
| KDE5            | 23        | 17.29%  |
| Unknown         | 15        | 11.28%  |
| XFCE            | 8         | 6.02%   |
| X-Cinnamon      | 8         | 6.02%   |
| KDE             | 5         | 3.76%   |
| MATE            | 4         | 3.01%   |
| Pantheon        | 2         | 1.5%    |
| LXQt            | 2         | 1.5%    |
| i3              | 2         | 1.5%    |
| Cinnamon        | 2         | 1.5%    |
| GNOME Flashback | 1         | 0.75%   |
| Deepin          | 1         | 0.75%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 101       | 75.37%  |
| Wayland | 20        | 14.93%  |
| Unknown | 9         | 6.72%   |
| Tty     | 4         | 2.99%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 61        | 45.19%  |
| SDDM    | 22        | 16.3%   |
| GDM     | 19        | 14.07%  |
| LightDM | 17        | 12.59%  |
| GDM3    | 12        | 8.89%   |
| TDM     | 4         | 2.96%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 56        | 42.11%  |
| Unknown | 13        | 9.77%   |
| en_GB   | 11        | 8.27%   |
| fr_FR   | 10        | 7.52%   |
| de_LU   | 9         | 6.77%   |
| de_DE   | 7         | 5.26%   |
| C       | 6         | 4.51%   |
| fr_LU   | 4         | 3.01%   |
| es_ES   | 3         | 2.26%   |
| POSIX   | 2         | 1.5%    |
| nl_NL   | 2         | 1.5%    |
| unm_US  | 1         | 0.75%   |
| pt_PT   | 1         | 0.75%   |
| pt_BR   | 1         | 0.75%   |
| lb_LU   | 1         | 0.75%   |
| it_IT   | 1         | 0.75%   |
| hr_HR   | 1         | 0.75%   |
| fr_CH   | 1         | 0.75%   |
| en_IE   | 1         | 0.75%   |
| en_AU   | 1         | 0.75%   |
| de_CH   | 1         | 0.75%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 70        | 53.44%  |
| BIOS | 61        | 46.56%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 96        | 73.85%  |
| Btrfs   | 14        | 10.77%  |
| Overlay | 9         | 6.92%   |
| Xfs     | 5         | 3.85%   |
| Unknown | 4         | 3.08%   |
| Zfs     | 1         | 0.77%   |
| Tmpfs   | 1         | 0.77%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 61        | 46.92%  |
| GPT     | 59        | 45.38%  |
| MBR     | 10        | 7.69%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 116       | 89.23%  |
| Yes       | 14        | 10.77%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 92        | 70.77%  |
| Yes       | 38        | 29.23%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 19        | 14.73%  |
| Hewlett-Packard     | 18        | 13.95%  |
| Lenovo              | 14        | 10.85%  |
| Dell                | 10        | 7.75%   |
| Gigabyte Technology | 8         | 6.2%    |
| Intel               | 6         | 4.65%   |
| Sony                | 5         | 3.88%   |
| MSI                 | 5         | 3.88%   |
| Apple               | 5         | 3.88%   |
| Acer                | 5         | 3.88%   |
| Medion              | 4         | 3.1%    |
| ASRock              | 4         | 3.1%    |
| Wortmann AG         | 3         | 2.33%   |
| HUAWEI              | 3         | 2.33%   |
| win element         | 2         | 1.55%   |
| Samsung Electronics | 2         | 1.55%   |
| Fujitsu             | 2         | 1.55%   |
| Clevo               | 2         | 1.55%   |
| YJKC                | 1         | 0.78%   |
| TUXEDO              | 1         | 0.78%   |
| Toshiba             | 1         | 0.78%   |
| Timi                | 1         | 0.78%   |
| SLIMBOOK            | 1         | 0.78%   |
| Packard Bell        | 1         | 0.78%   |
| Notebook            | 1         | 0.78%   |
| Microsoft           | 1         | 0.78%   |
| LattePanda          | 1         | 0.78%   |
| JWIPC               | 1         | 0.78%   |
| Foxconn             | 1         | 0.78%   |
| BESSTAR Tech        | 1         | 0.78%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| ASUS All Series                          | 3         | 2.33%   |
| win element MoreFine S500+               | 2         | 1.55%   |
| Dell Precision M3800                     | 2         | 1.55%   |
| YJKC vBook                               | 1         | 0.78%   |
| Wortmann AG TERRA_MOBILE_1749            | 1         | 0.78%   |
| Wortmann AG TERRA_MOBILE_1541H           | 1         | 0.78%   |
| Wortmann AG MS-1727                      | 1         | 0.78%   |
| TUXEDO Pulse 14 Gen1                     | 1         | 0.78%   |
| Toshiba Satellite C55-A-1N0              | 1         | 0.78%   |
| Timi RedmiBook 14 II                     | 1         | 0.78%   |
| Sony VPCP11S1R                           | 1         | 0.78%   |
| Sony VPCEB2E1E                           | 1         | 0.78%   |
| Sony VPCCA4E1E                           | 1         | 0.78%   |
| Sony VGN-NS30E_S                         | 1         | 0.78%   |
| Sony SVF1421E2EW                         | 1         | 0.78%   |
| SLIMBOOK EXECUTIVE-14                    | 1         | 0.78%   |
| Samsung Galaxy TabPro S LTE              | 1         | 0.78%   |
| Samsung 950QDB                           | 1         | 0.78%   |
| Packard Bell EasyNote TJ65               | 1         | 0.78%   |
| Notebook NV4XMB,ME,MZ                    | 1         | 0.78%   |
| MSI MS-7C80                              | 1         | 0.78%   |
| MSI MS-7C08                              | 1         | 0.78%   |
| MSI MS-7816                              | 1         | 0.78%   |
| MSI MS-7578                              | 1         | 0.78%   |
| MSI GF72 8RD                             | 1         | 0.78%   |
| Microsoft Surface Book 2                 | 1         | 0.78%   |
| Medion P961x                             | 1         | 0.78%   |
| Medion P6685 MD61138                     | 1         | 0.78%   |
| Medion MS-7848                           | 1         | 0.78%   |
| Medion E4254 MD62100                     | 1         | 0.78%   |
| Lenovo ThinkStation P920 30BDS2H804      | 1         | 0.78%   |
| Lenovo ThinkPad X1 Carbon 7th 20QDCTO1WW | 1         | 0.78%   |
| Lenovo ThinkPad T590 20N4CTO1WW          | 1         | 0.78%   |
| Lenovo ThinkPad T490 20N3S5DV0S          | 1         | 0.78%   |
| Lenovo ThinkPad T480s 20L7001PFR         | 1         | 0.78%   |
| Lenovo ThinkPad T470s W10DG 20JTS0R800   | 1         | 0.78%   |
| Lenovo ThinkPad T440p 20AWS24B00         | 1         | 0.78%   |
| Lenovo ThinkPad P1 Gen 2 20QTCTO1WW      | 1         | 0.78%   |
| Lenovo ThinkPad L15 Gen 1 20U8S0AH00     | 1         | 0.78%   |
| Lenovo ThinkPad L15 Gen 1 20U7S05B00     | 1         | 0.78%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 10        | 7.75%   |
| Dell Precision        | 6         | 4.65%   |
| HP EliteBook          | 5         | 3.88%   |
| ASUS PRIME            | 4         | 3.1%    |
| Acer Aspire           | 4         | 3.1%    |
| HP ENVY               | 3         | 2.33%   |
| ASUS VivoBook         | 3         | 2.33%   |
| ASUS All              | 3         | 2.33%   |
| Wortmann AG TERRA     | 2         | 1.55%   |
| win element MoreFine  | 2         | 1.55%   |
| HP ProBook            | 2         | 1.55%   |
| HP Compaq             | 2         | 1.55%   |
| Dell XPS              | 2         | 1.55%   |
| ASUS TUF              | 2         | 1.55%   |
| ASUS ROG              | 2         | 1.55%   |
| YJKC vBook            | 1         | 0.78%   |
| Wortmann AG MS-1727   | 1         | 0.78%   |
| TUXEDO Pulse          | 1         | 0.78%   |
| Toshiba Satellite     | 1         | 0.78%   |
| Timi RedmiBook        | 1         | 0.78%   |
| Sony VPCP11S1R        | 1         | 0.78%   |
| Sony VPCEB2E1E        | 1         | 0.78%   |
| Sony VPCCA4E1E        | 1         | 0.78%   |
| Sony VGN-NS30E        | 1         | 0.78%   |
| Sony SVF1421E2EW      | 1         | 0.78%   |
| SLIMBOOK EXECUTIVE-14 | 1         | 0.78%   |
| Samsung Galaxy        | 1         | 0.78%   |
| Samsung 950QDB        | 1         | 0.78%   |
| Packard Bell EasyNote | 1         | 0.78%   |
| Notebook NV4XMB       | 1         | 0.78%   |
| MSI MS-7C80           | 1         | 0.78%   |
| MSI MS-7C08           | 1         | 0.78%   |
| MSI MS-7816           | 1         | 0.78%   |
| MSI MS-7578           | 1         | 0.78%   |
| MSI GF72              | 1         | 0.78%   |
| Microsoft Surface     | 1         | 0.78%   |
| Medion P961x          | 1         | 0.78%   |
| Medion P6685          | 1         | 0.78%   |
| Medion MS-7848        | 1         | 0.78%   |
| Medion E4254          | 1         | 0.78%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 16        | 12.4%   |
| 2018 | 16        | 12.4%   |
| 2020 | 13        | 10.08%  |
| 2021 | 12        | 9.3%    |
| 2017 | 12        | 9.3%    |
| 2013 | 12        | 9.3%    |
| 2014 | 10        | 7.75%   |
| 2010 | 9         | 6.98%   |
| 2016 | 7         | 5.43%   |
| 2011 | 5         | 3.88%   |
| 2015 | 4         | 3.1%    |
| 2022 | 3         | 2.33%   |
| 2012 | 3         | 2.33%   |
| 2009 | 3         | 2.33%   |
| 2007 | 2         | 1.55%   |
| 2023 | 1         | 0.78%   |
| 2008 | 1         | 0.78%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 78        | 60.47%  |
| Desktop     | 40        | 31.01%  |
| Mini pc     | 4         | 3.1%    |
| Convertible | 3         | 2.33%   |
| Tablet      | 2         | 1.55%   |
| All in one  | 1         | 0.78%   |
| Server      | 1         | 0.78%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 118       | 90.77%  |
| Enabled  | 12        | 9.23%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 129       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 37        | 28.24%  |
| 8.01-16.0       | 29        | 22.14%  |
| 4.01-8.0        | 23        | 17.56%  |
| 32.01-64.0      | 16        | 12.21%  |
| 3.01-4.0        | 16        | 12.21%  |
| 64.01-256.0     | 3         | 2.29%   |
| 24.01-32.0      | 2         | 1.53%   |
| 2.01-3.0        | 2         | 1.53%   |
| 1.01-2.0        | 2         | 1.53%   |
| More than 256.0 | 1         | 0.76%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 39        | 28.89%  |
| 1.01-2.0   | 34        | 25.19%  |
| 4.01-8.0   | 26        | 19.26%  |
| 3.01-4.0   | 18        | 13.33%  |
| 8.01-16.0  | 12        | 8.89%   |
| 0.51-1.0   | 3         | 2.22%   |
| 24.01-32.0 | 1         | 0.74%   |
| 16.01-24.0 | 1         | 0.74%   |
| 0.01-0.5   | 1         | 0.74%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 73        | 55.73%  |
| 2      | 33        | 25.19%  |
| 3      | 13        | 9.92%   |
| 4      | 6         | 4.58%   |
| 5      | 3         | 2.29%   |
| 0      | 2         | 1.53%   |
| 7      | 1         | 0.76%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 88        | 68.22%  |
| Yes       | 41        | 31.78%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 107       | 82.95%  |
| No        | 22        | 17.05%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 106       | 81.54%  |
| No        | 24        | 18.46%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 91        | 70.54%  |
| No        | 38        | 29.46%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country    | Computers | Percent |
|------------|-----------|---------|
| Luxembourg | 129       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Luxembourg        | 75        | 54.35%  |
| Strassen          | 9         | 6.52%   |
| Useldange         | 3         | 2.17%   |
| Schifflange       | 3         | 2.17%   |
| Schieren          | 3         | 2.17%   |
| Esch-sur-Alzette  | 3         | 2.17%   |
| Ehnen             | 3         | 2.17%   |
| Differdange       | 3         | 2.17%   |
| Wormeldange       | 2         | 1.45%   |
| Steinfort         | 2         | 1.45%   |
| Sanem             | 2         | 1.45%   |
| Bettange-sur-Mess | 2         | 1.45%   |
| Wiltz             | 1         | 0.72%   |
| Wecker            | 1         | 0.72%   |
| Wasserbillig      | 1         | 0.72%   |
| Vianden           | 1         | 0.72%   |
| Steinsel          | 1         | 0.72%   |
| Soleuvre          | 1         | 0.72%   |
| Roeser            | 1         | 0.72%   |
| Pontpierre        | 1         | 0.72%   |
| Pétange          | 1         | 0.72%   |
| PerlГ©          | 1         | 0.72%   |
| Oberpallen        | 1         | 0.72%   |
| Niederanven       | 1         | 0.72%   |
| Leudelange        | 1         | 0.72%   |
| Kopstal           | 1         | 0.72%   |
| Junglinster       | 1         | 0.72%   |
| Itzig             | 1         | 0.72%   |
| Hunsdorf          | 1         | 0.72%   |
| Hosingen          | 1         | 0.72%   |
| Hesperange        | 1         | 0.72%   |
| Ettelbruck        | 1         | 0.72%   |
| Echternach        | 1         | 0.72%   |
| Dudelange         | 1         | 0.72%   |
| Diekirch          | 1         | 0.72%   |
| Bourscheid        | 1         | 0.72%   |
| Bettembourg       | 1         | 0.72%   |
| Belvaux           | 1         | 0.72%   |
| Beckerich         | 1         | 0.72%   |
| Aspelt            | 1         | 0.72%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 47        | 65     | 24.87%  |
| Seagate                   | 25        | 33     | 13.23%  |
| WDC                       | 22        | 33     | 11.64%  |
| Crucial                   | 13        | 18     | 6.88%   |
| Toshiba                   | 12        | 15     | 6.35%   |
| SanDisk                   | 12        | 16     | 6.35%   |
| Kingston                  | 9         | 12     | 4.76%   |
| SK hynix                  | 5         | 5      | 2.65%   |
| Apple                     | 5         | 6      | 2.65%   |
| Intel                     | 3         | 4      | 1.59%   |
| Hitachi                   | 3         | 4      | 1.59%   |
| Transcend                 | 2         | 2      | 1.06%   |
| Micron Technology         | 2         | 3      | 1.06%   |
| LITEONIT                  | 2         | 2      | 1.06%   |
| LITEON                    | 2         | 2      | 1.06%   |
| Intenso                   | 2         | 3      | 1.06%   |
| HGST                      | 2         | 3      | 1.06%   |
| A-DATA Technology         | 2         | 2      | 1.06%   |
| Unknown                   | 1         | 2      | 0.53%   |
| Union Memory (Shenzhen)   | 1         | 1      | 0.53%   |
| TCSUNBOW                  | 1         | 1      | 0.53%   |
| StarTech                  | 1         | 1      | 0.53%   |
| SABRENT                   | 1         | 1      | 0.53%   |
| Phison                    | 1         | 1      | 0.53%   |
| PHD 3.0                   | 1         | 1      | 0.53%   |
| OCZ                       | 1         | 1      | 0.53%   |
| Micron/Crucial Technology | 1         | 1      | 0.53%   |
| Maxtor                    | 1         | 2      | 0.53%   |
| Lenovo                    | 1         | 1      | 0.53%   |
| LaCie                     | 1         | 1      | 0.53%   |
| KingSpec                  | 1         | 1      | 0.53%   |
| KingDian                  | 1         | 1      | 0.53%   |
| Inateck                   | 1         | 1      | 0.53%   |
| HUAWEI                    | 1         | 1      | 0.53%   |
| Gigabyte Technology       | 1         | 1      | 0.53%   |
| FORESEE                   | 1         | 1      | 0.53%   |
| ASMT                      | 1         | 2      | 0.53%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate Expansion 1TB                               | 4         | 1.87%   |
| Samsung SSD 840 EVO 250GB                           | 3         | 1.4%    |
| Kingston SA400S37240G 240GB SSD                     | 3         | 1.4%    |
| Crucial CT1000P2SSD8 1TB                            | 3         | 1.4%    |
| WDC WD10JPVX-22JC3T0 1TB                            | 2         | 0.93%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 2         | 0.93%   |
| WDC WD10EACS-00D6B1 1TB                             | 2         | 0.93%   |
| Toshiba MQ01ABF050 500GB                            | 2         | 0.93%   |
| Seagate ST1000LM035-1RK172 1TB                      | 2         | 0.93%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB    | 2         | 0.93%   |
| SanDisk SD8SN8U128G1122 128GB SSD                   | 2         | 0.93%   |
| SanDisk NVMe SSD Drive 1TB                          | 2         | 0.93%   |
| Samsung SSD 860 QVO 1TB                             | 2         | 0.93%   |
| Samsung SSD 860 EVO 250GB                           | 2         | 0.93%   |
| Samsung SSD 850 EVO 250GB                           | 2         | 0.93%   |
| Samsung SP2504C 250GB                               | 2         | 0.93%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 2         | 0.93%   |
| Samsung MZVLW256HEHP-000L7 256GB                    | 2         | 0.93%   |
| LITEONIT LMT-256L9M-11 MSATA 256GB SSD              | 2         | 0.93%   |
| Crucial CT240BX500SSD1 240GB                        | 2         | 0.93%   |
| Crucial CT1000MX500SSD1 1TB                         | 2         | 0.93%   |
| WDC WDS500G3X0C-00SJG0 500GB                        | 1         | 0.47%   |
| WDC WDS250G2B0B-00YS70 250GB SSD                    | 1         | 0.47%   |
| WDC WD5000AAVS-00ZTB0 500GB                         | 1         | 0.47%   |
| WDC WD5000AAKS-60Z1A0 500GB                         | 1         | 0.47%   |
| WDC WD40EZRZ-75GXCB0 4TB                            | 1         | 0.47%   |
| WDC WD4000FYYZ-01UL1B2 4TB                          | 1         | 0.47%   |
| WDC WD3200LPCX-00VHAT0 320GB                        | 1         | 0.47%   |
| WDC WD3001FFSX-68JNUN0 3TB                          | 1         | 0.47%   |
| WDC WD3000GLFS-01F8U0 304GB                         | 1         | 0.47%   |
| WDC WD20EFAX-68FB5N0 2TB                            | 1         | 0.47%   |
| WDC WD141KRYZ-01C66B0 14TB                          | 1         | 0.47%   |
| WDC WD10SPZX-17Z10T0 1TB                            | 1         | 0.47%   |
| WDC WD10SPCX-60HWST0 1TB                            | 1         | 0.47%   |
| WDC WD10EZRX-00A8LB0 1TB                            | 1         | 0.47%   |
| WDC WD10EZEX-60ZF5A0 1TB                            | 1         | 0.47%   |
| WDC WD10EARX-00N0YB0 1TB                            | 1         | 0.47%   |
| WDC WD10EARS-00Y5B1 1TB                             | 1         | 0.47%   |
| WDC WD1001FALS-00J7B0 1TB                           | 1         | 0.47%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB                | 1         | 0.47%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 23        | 31     | 37.7%   |
| WDC                 | 16        | 27     | 26.23%  |
| Toshiba             | 8         | 11     | 13.11%  |
| Samsung Electronics | 3         | 3      | 4.92%   |
| Hitachi             | 3         | 4      | 4.92%   |
| HGST                | 2         | 3      | 3.28%   |
| Apple               | 2         | 2      | 3.28%   |
| PHD 3.0             | 1         | 1      | 1.64%   |
| Intenso             | 1         | 1      | 1.64%   |
| Inateck             | 1         | 1      | 1.64%   |
| ASMT                | 1         | 2      | 1.64%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 27        | 36     | 38.57%  |
| SanDisk             | 9         | 11     | 12.86%  |
| Crucial             | 9         | 14     | 12.86%  |
| Kingston            | 5         | 8      | 7.14%   |
| Transcend           | 2         | 2      | 2.86%   |
| Micron Technology   | 2         | 3      | 2.86%   |
| LITEONIT            | 2         | 2      | 2.86%   |
| LITEON              | 2         | 2      | 2.86%   |
| WDC                 | 1         | 1      | 1.43%   |
| TCSUNBOW            | 1         | 1      | 1.43%   |
| SK hynix            | 1         | 1      | 1.43%   |
| OCZ                 | 1         | 1      | 1.43%   |
| Maxtor              | 1         | 2      | 1.43%   |
| Lenovo              | 1         | 1      | 1.43%   |
| KingSpec            | 1         | 1      | 1.43%   |
| KingDian            | 1         | 1      | 1.43%   |
| Intenso             | 1         | 2      | 1.43%   |
| FORESEE             | 1         | 1      | 1.43%   |
| Apple               | 1         | 1      | 1.43%   |
| A-DATA Technology   | 1         | 1      | 1.43%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 58        | 92     | 33.33%  |
| NVMe    | 56        | 65     | 32.18%  |
| HDD     | 54        | 86     | 31.03%  |
| Unknown | 4         | 4      | 2.3%    |
| MMC     | 2         | 3      | 1.15%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 88        | 165    | 55.35%  |
| NVMe | 56        | 64     | 35.22%  |
| SAS  | 13        | 18     | 8.18%   |
| MMC  | 2         | 3      | 1.26%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 64        | 99     | 51.2%   |
| 0.51-1.0   | 42        | 57     | 33.6%   |
| 1.01-2.0   | 8         | 9      | 6.4%    |
| 3.01-4.0   | 6         | 7      | 4.8%    |
| 2.01-3.0   | 2         | 3      | 1.6%    |
| 4.01-10.0  | 2         | 2      | 1.6%    |
| 10.01-20.0 | 1         | 1      | 0.8%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 32        | 24.06%  |
| 101-250        | 32        | 24.06%  |
| 501-1000       | 17        | 12.78%  |
| More than 3000 | 11        | 8.27%   |
| Unknown        | 11        | 8.27%   |
| 1001-2000      | 10        | 7.52%   |
| 2001-3000      | 7         | 5.26%   |
| 51-100         | 6         | 4.51%   |
| 1-20           | 5         | 3.76%   |
| 21-50          | 2         | 1.5%    |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 44        | 32.84%  |
| 21-50          | 19        | 14.18%  |
| 101-250        | 19        | 14.18%  |
| 251-500        | 12        | 8.96%   |
| 51-100         | 11        | 8.21%   |
| Unknown        | 11        | 8.21%   |
| 501-1000       | 8         | 5.97%   |
| 2001-3000      | 4         | 2.99%   |
| 1001-2000      | 4         | 2.99%   |
| More than 3000 | 2         | 1.49%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


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

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Toshiba  | 3         | 3      | 50%     |
| SK hynix | 1         | 1      | 16.67%  |
| Seagate  | 1         | 1      | 16.67%  |
| Crucial  | 1         | 2      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 3         | 3      | 75%     |
| Seagate | 1         | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 68        | 137    | 48.92%  |
| Works    | 65        | 106    | 46.76%  |
| Malfunc  | 6         | 7      | 4.32%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 86        | 51.5%   |
| Samsung Electronics          | 23        | 13.77%  |
| AMD                          | 21        | 12.57%  |
| SanDisk                      | 10        | 5.99%   |
| Micron/Crucial Technology    | 5         | 2.99%   |
| Toshiba America Info Systems | 4         | 2.4%    |
| Kingston Technology Company  | 4         | 2.4%    |
| SK hynix                     | 3         | 1.8%    |
| Marvell Technology Group     | 3         | 1.8%    |
| Phison Electronics           | 2         | 1.2%    |
| Apple                        | 2         | 1.2%    |
| Union Memory (Shenzhen)      | 1         | 0.6%    |
| Seagate Technology           | 1         | 0.6%    |
| ASMedia Technology           | 1         | 0.6%    |
| ADATA Technology             | 1         | 0.6%    |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 18        | 9.84%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 13        | 7.1%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 9         | 4.92%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 9         | 4.92%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 7         | 3.83%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 6         | 3.28%   |
| Intel Volume Management Device NVMe RAID Controller                            | 6         | 3.28%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 6         | 3.28%   |
| Samsung NVMe SSD Controller 980                                                | 4         | 2.19%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 4         | 2.19%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 2.19%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 4         | 2.19%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 2.19%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 2.19%   |
| AMD 400 Series Chipset SATA Controller                                         | 4         | 2.19%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 1.64%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 1.64%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 3         | 1.64%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 1.64%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 3         | 1.64%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 1.09%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 2         | 1.09%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2         | 1.09%   |
| Phison E12 NVMe Controller                                                     | 2         | 1.09%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                      | 2         | 1.09%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 1.09%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 1.09%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 1.09%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 2         | 1.09%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 2         | 1.09%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 1         | 0.55%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 1         | 0.55%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 1         | 0.55%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 1         | 0.55%   |
| Seagate FireCuda 520 SSD                                                       | 1         | 0.55%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1         | 0.55%   |
| Samsung Surface NVMe Controller                                                | 1         | 0.55%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 1         | 0.55%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                     | 1         | 0.55%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 1         | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 93        | 55.36%  |
| NVMe | 57        | 33.93%  |
| RAID | 10        | 5.95%   |
| IDE  | 8         | 4.76%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 102       | 79.07%  |
| AMD    | 27        | 20.93%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 3.1%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 3.1%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 2.33%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 2.33%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 1.55%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 2         | 1.55%   |
| Intel Core i7-4702HQ CPU @ 2.20GHz            | 2         | 1.55%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 2         | 1.55%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 1.55%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 2         | 1.55%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 1.55%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 2         | 1.55%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 2         | 1.55%   |
| AMD Ryzen 5 3600 6-Core Processor             | 2         | 1.55%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 2         | 1.55%   |
| Intel Xeon Gold 6154 CPU @ 3.00GHz            | 1         | 0.78%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.78%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 0.78%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 0.78%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 1         | 0.78%   |
| Intel Pentium CPU P6000 @ 1.87GHz             | 1         | 0.78%   |
| Intel Pentium CPU G4560 @ 3.50GHz             | 1         | 0.78%   |
| Intel Pentium CPU G3250 @ 3.20GHz             | 1         | 0.78%   |
| Intel Pentium CPU 987 @ 1.50GHz               | 1         | 0.78%   |
| Intel Core m5-6Y54 CPU @ 1.10GHz              | 1         | 0.78%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz              | 1         | 0.78%   |
| Intel Core i9-9880H CPU @ 2.30GHz             | 1         | 0.78%   |
| Intel Core i7-9700KF CPU @ 3.60GHz            | 1         | 0.78%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 1         | 0.78%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 1         | 0.78%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 0.78%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 1         | 0.78%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.78%   |
| Intel Core i7-6800K CPU @ 3.40GHz             | 1         | 0.78%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 0.78%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 0.78%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 1         | 0.78%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 1         | 0.78%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 1         | 0.78%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 1         | 0.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 33        | 25.58%  |
| Intel Core i5           | 27        | 20.93%  |
| Other                   | 11        | 8.53%   |
| Intel Core i3           | 9         | 6.98%   |
| AMD Ryzen 5             | 9         | 6.98%   |
| AMD Ryzen 9             | 5         | 3.88%   |
| AMD Ryzen 7             | 5         | 3.88%   |
| Intel Pentium           | 4         | 3.1%    |
| Intel Celeron           | 4         | 3.1%    |
| Intel Pentium Dual-Core | 3         | 2.33%   |
| Intel Core 2 Quad       | 3         | 2.33%   |
| AMD Ryzen 7 PRO         | 2         | 1.55%   |
| AMD Ryzen 5 PRO         | 2         | 1.55%   |
| Intel Xeon Gold         | 1         | 0.78%   |
| Intel Pentium Silver    | 1         | 0.78%   |
| Intel Core m5           | 1         | 0.78%   |
| Intel Core m3           | 1         | 0.78%   |
| Intel Core i9           | 1         | 0.78%   |
| Intel Core 2 Duo        | 1         | 0.78%   |
| Intel Core 2            | 1         | 0.78%   |
| Intel Atom              | 1         | 0.78%   |
| AMD Phenom II X4        | 1         | 0.78%   |
| AMD FX                  | 1         | 0.78%   |
| AMD E2                  | 1         | 0.78%   |
| AMD Athlon II X4        | 1         | 0.78%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 49        | 37.98%  |
| 2       | 40        | 31.01%  |
| 6       | 16        | 12.4%   |
| 8       | 15        | 11.63%  |
| 12      | 3         | 2.33%   |
| 1       | 2         | 1.55%   |
| 36      | 1         | 0.78%   |
| 16      | 1         | 0.78%   |
| 14      | 1         | 0.78%   |
| Unknown | 1         | 0.78%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 128       | 99.22%  |
| 2      | 1         | 0.78%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 100       | 77.52%  |
| 1       | 28        | 21.71%  |
| Unknown | 1         | 0.78%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 128       | 99.22%  |
| 32-bit         | 1         | 0.78%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 29        | 21.64%  |
| 0x306c3    | 13        | 9.7%    |
| 0x806ea    | 5         | 3.73%   |
| 0x40651    | 5         | 3.73%   |
| 0x206a7    | 5         | 3.73%   |
| 0x906e9    | 4         | 2.99%   |
| 0x806c1    | 4         | 2.99%   |
| 0x406e3    | 4         | 2.99%   |
| 0x1067a    | 4         | 2.99%   |
| 0x906ea    | 3         | 2.24%   |
| 0x806eb    | 3         | 2.24%   |
| 0x506e3    | 3         | 2.24%   |
| 0x306d4    | 3         | 2.24%   |
| 0x20655    | 3         | 2.24%   |
| 0xa0655    | 2         | 1.49%   |
| 0x906ed    | 2         | 1.49%   |
| 0x806ec    | 2         | 1.49%   |
| 0x806d1    | 2         | 1.49%   |
| 0x706a1    | 2         | 1.49%   |
| 0x306a9    | 2         | 1.49%   |
| 0x10677    | 2         | 1.49%   |
| 0x0a50000c | 2         | 1.49%   |
| 0x0a20120a | 2         | 1.49%   |
| 0x08701021 | 2         | 1.49%   |
| 0x08701013 | 2         | 1.49%   |
| 0x08600106 | 2         | 1.49%   |
| 0x08600103 | 2         | 1.49%   |
| 0x08108102 | 2         | 1.49%   |
| 0xa0671    | 1         | 0.75%   |
| 0x906c0    | 1         | 0.75%   |
| 0x806e9    | 1         | 0.75%   |
| 0x6fb      | 1         | 0.75%   |
| 0x6f6      | 1         | 0.75%   |
| 0x50654    | 1         | 0.75%   |
| 0x406f1    | 1         | 0.75%   |
| 0x20652    | 1         | 0.75%   |
| 0x106c2    | 1         | 0.75%   |
| 0x0a601203 | 1         | 0.75%   |
| 0x0a50000d | 1         | 0.75%   |
| 0x0a201009 | 1         | 0.75%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 28        | 21.71%  |
| Haswell          | 20        | 15.5%   |
| Zen 2            | 11        | 8.53%   |
| Skylake          | 11        | 8.53%   |
| Zen 3            | 7         | 5.43%   |
| TigerLake        | 6         | 4.65%   |
| Penryn           | 6         | 4.65%   |
| SandyBridge      | 5         | 3.88%   |
| Westmere         | 4         | 3.1%    |
| Broadwell        | 4         | 3.1%    |
| Zen+             | 3         | 2.33%   |
| IvyBridge        | 3         | 2.33%   |
| Icelake          | 3         | 2.33%   |
| CometLake        | 3         | 2.33%   |
| Unknown          | 3         | 2.33%   |
| K10              | 2         | 1.55%   |
| Goldmont plus    | 2         | 1.55%   |
| Core             | 2         | 1.55%   |
| Zen              | 1         | 0.78%   |
| Piledriver       | 1         | 0.78%   |
| Goldmont         | 1         | 0.78%   |
| Excavator        | 1         | 0.78%   |
| Bonnell          | 1         | 0.78%   |
| Alderlake Hybrid | 1         | 0.78%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 82        | 52.23%  |
| Nvidia | 48        | 30.57%  |
| AMD    | 27        | 17.2%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 8         | 5%      |
| Intel UHD Graphics 620                                                      | 7         | 4.38%   |
| AMD Renoir                                                                  | 7         | 4.38%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 6         | 3.75%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 6         | 3.75%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 5         | 3.13%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 5         | 3.13%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 4         | 2.5%    |
| Intel HD Graphics 530                                                       | 4         | 2.5%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4         | 2.5%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 4         | 2.5%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 3         | 1.88%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 3         | 1.88%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 2         | 1.25%   |
| Nvidia GP108M [GeForce MX250]                                               | 2         | 1.25%   |
| Nvidia GP108M [GeForce MX150]                                               | 2         | 1.25%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2         | 1.25%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 2         | 1.25%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2         | 1.25%   |
| Nvidia GK107GLM [Quadro K1100M]                                             | 2         | 1.25%   |
| Nvidia GA107GLM [RTX A1000 Laptop GPU]                                      | 2         | 1.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 1.25%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 2         | 1.25%   |
| Intel Iris Plus Graphics 640                                                | 2         | 1.25%   |
| Intel HD Graphics 5500                                                      | 2         | 1.25%   |
| Intel HD Graphics 515                                                       | 2         | 1.25%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2         | 1.25%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 2         | 1.25%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                               | 1         | 0.63%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                       | 1         | 0.63%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1         | 0.63%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1         | 0.63%   |
| Nvidia GT218 [NVS 300]                                                      | 1         | 0.63%   |
| Nvidia GT218 [GeForce G210]                                                 | 1         | 0.63%   |
| Nvidia GT216M [GeForce GT 330M]                                             | 1         | 0.63%   |
| Nvidia GT215M [GeForce GTS 250M]                                            | 1         | 0.63%   |
| Nvidia GP107GL [Quadro P1000]                                               | 1         | 0.63%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1         | 0.63%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1         | 0.63%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1         | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 53        | 41.09%  |
| Intel + Nvidia | 25        | 19.38%  |
| 1 x Nvidia     | 24        | 18.6%   |
| 1 x AMD        | 21        | 16.28%  |
| 2 x AMD        | 3         | 2.33%   |
| Intel + AMD    | 3         | 2.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 98        | 75.38%  |
| Proprietary | 27        | 20.77%  |
| Unknown     | 5         | 3.85%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 78        | 60%     |
| 3.01-4.0   | 14        | 10.77%  |
| 0.01-0.5   | 12        | 9.23%   |
| 1.01-2.0   | 11        | 8.46%   |
| 0.51-1.0   | 9         | 6.92%   |
| 8.01-16.0  | 4         | 3.08%   |
| 5.01-6.0   | 2         | 1.54%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 22        | 14.97%  |
| Chimei Innolux          | 21        | 14.29%  |
| LG Display              | 15        | 10.2%   |
| AU Optronics            | 10        | 6.8%    |
| Hewlett-Packard         | 8         | 5.44%   |
| Dell                    | 7         | 4.76%   |
| AOC                     | 7         | 4.76%   |
| Sharp                   | 6         | 4.08%   |
| Iiyama                  | 6         | 4.08%   |
| Goldstar                | 6         | 4.08%   |
| BOE                     | 5         | 3.4%    |
| Apple                   | 5         | 3.4%    |
| Philips                 | 4         | 2.72%   |
| BenQ                    | 4         | 2.72%   |
| Medion                  | 3         | 2.04%   |
| Chi Mei Optoelectronics | 3         | 2.04%   |
| Ancor Communications    | 2         | 1.36%   |
| Videoseven              | 1         | 0.68%   |
| Sony                    | 1         | 0.68%   |
| PAR                     | 1         | 0.68%   |
| PANDA                   | 1         | 0.68%   |
| Panasonic               | 1         | 0.68%   |
| MSI                     | 1         | 0.68%   |
| Lenovo                  | 1         | 0.68%   |
| Fujitsu Siemens         | 1         | 0.68%   |
| Eizo                    | 1         | 0.68%   |
| CSO                     | 1         | 0.68%   |
| Belinea                 | 1         | 0.68%   |
| Aosiman                 | 1         | 0.68%   |
| Acer                    | 1         | 0.68%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 2         | 1.34%   |
| Sharp LCD Monitor SHP13F8 3200x1800 346x194mm 15.6-inch               | 2         | 1.34%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch      | 2         | 1.34%   |
| Chimei Innolux LCD Monitor CMN1604 1920x1080 355x199mm 16.0-inch      | 2         | 1.34%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 2         | 1.34%   |
| AOC 2250W AOC2250 1920x1080 477x268mm 21.5-inch                       | 2         | 1.34%   |
| Videoseven L27ADS IGM2700 1920x1080 598x336mm 27.0-inch               | 1         | 0.67%   |
| Sony LCD Monitor SNY05FA 1366x768 310x170mm 13.9-inch                 | 1         | 0.67%   |
| Sharp LCD Monitor SHP1516 3840x2400 336x210mm 15.6-inch               | 1         | 0.67%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch               | 1         | 0.67%   |
| Samsung Electronics U28H75x SAM0DFE 3840x2160 608x345mm 27.5-inch     | 1         | 0.67%   |
| Samsung Electronics T24B350 SAM093E 1920x1080 531x299mm 24.0-inch     | 1         | 0.67%   |
| Samsung Electronics SyncMaster SAM0612 1920x1080 604x342mm 27.3-inch  | 1         | 0.67%   |
| Samsung Electronics SyncMaster SAM04DF 1360x768 410x230mm 18.5-inch   | 1         | 0.67%   |
| Samsung Electronics SMT27A950 SAM080F 1920x1080 598x336mm 27.0-inch   | 1         | 0.67%   |
| Samsung Electronics SM2333T SAM0737 1920x1080 510x290mm 23.1-inch     | 1         | 0.67%   |
| Samsung Electronics S27D390 SAM0B67 1920x1080 598x336mm 27.0-inch     | 1         | 0.67%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 0.67%   |
| Samsung Electronics LCD Monitor U28E590 3840x2160                     | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SEC444E 1600x900 310x174mm 14.0-inch  | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SDC5844 1920x1080 344x194mm 15.5-inch | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch  | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 409x230mm 18.5-inch | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch  | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SDC4159 1920x1080 344x194mm 15.5-inch | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SDC4141 3840x2160 344x194mm 15.5-inch | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SAM0B60 1920x1080 887x500mm 40.1-inch | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 700x390mm 31.5-inch | 1         | 0.67%   |
| Samsung Electronics Color LCD SDCA029 2160x1440 252x168mm 11.9-inch   | 1         | 0.67%   |
| Samsung Electronics C27R500 SAM0F9D 1920x1080 598x336mm 27.0-inch     | 1         | 0.67%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 1         | 0.67%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1         | 0.67%   |
| Philips PHL BDM3270 PHL08E7 2560x1440 708x398mm 32.0-inch             | 1         | 0.67%   |
| Philips PHL 346B1C PHL095C 3440x1440 797x334mm 34.0-inch              | 1         | 0.67%   |
| Philips PHL 275C5 PHLC0E4 1920x1080 598x336mm 27.0-inch               | 1         | 0.67%   |
| Philips PHL 246V5 PHLC0C5 1920x1080 531x299mm 24.0-inch               | 1         | 0.67%   |
| PAR LED1920X1080 PAR9C63 1920x1080 710x400mm 32.1-inch                | 1         | 0.67%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 1         | 0.67%   |
| Panasonic VVX14T092N00 MEI96A2 2256x1504 285x190mm 13.5-inch          | 1         | 0.67%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 69        | 51.11%  |
| 1366x768 (WXGA)    | 15        | 11.11%  |
| 3840x2160 (4K)     | 13        | 9.63%   |
| 2560x1440 (QHD)    | 8         | 5.93%   |
| 1600x900 (HD+)     | 4         | 2.96%   |
| 2880x1800          | 3         | 2.22%   |
| 1920x1200 (WUXGA)  | 3         | 2.22%   |
| 1680x1050 (WSXGA+) | 3         | 2.22%   |
| 3200x1800 (QHD+)   | 2         | 1.48%   |
| 1440x900 (WXGA+)   | 2         | 1.48%   |
| 1360x768           | 2         | 1.48%   |
| 1280x1024 (SXGA)   | 2         | 1.48%   |
| 3840x2400          | 1         | 0.74%   |
| 3840x1080          | 1         | 0.74%   |
| 3440x1440          | 1         | 0.74%   |
| 3072x1920          | 1         | 0.74%   |
| 2560x1600          | 1         | 0.74%   |
| 2520x1680          | 1         | 0.74%   |
| 1280x800 (WXGA)    | 1         | 0.74%   |
| 1024x768 (XGA)     | 1         | 0.74%   |
| Unknown            | 1         | 0.74%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 35        | 23.81%  |
| 27      | 20        | 13.61%  |
| 13      | 14        | 9.52%   |
| 14      | 13        | 8.84%   |
| 17      | 11        | 7.48%   |
| 24      | 10        | 6.8%    |
| 21      | 8         | 5.44%   |
| 23      | 7         | 4.76%   |
| 16      | 5         | 3.4%    |
| Unknown | 5         | 3.4%    |
| 22      | 3         | 2.04%   |
| 72      | 2         | 1.36%   |
| 40      | 2         | 1.36%   |
| 32      | 2         | 1.36%   |
| 18      | 2         | 1.36%   |
| 59      | 1         | 0.68%   |
| 46      | 1         | 0.68%   |
| 34      | 1         | 0.68%   |
| 33      | 1         | 0.68%   |
| 31      | 1         | 0.68%   |
| 25      | 1         | 0.68%   |
| 19      | 1         | 0.68%   |
| 11      | 1         | 0.68%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 58        | 40.28%  |
| 501-600     | 34        | 23.61%  |
| 401-500     | 13        | 9.03%   |
| 351-400     | 13        | 9.03%   |
| 201-300     | 8         | 5.56%   |
| Unknown     | 5         | 3.47%   |
| 701-800     | 4         | 2.78%   |
| 601-700     | 3         | 2.08%   |
| 801-900     | 2         | 1.39%   |
| 1501-2000   | 2         | 1.39%   |
| 1001-1500   | 2         | 1.39%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 103       | 80.47%  |
| 16/10   | 17        | 13.28%  |
| Unknown | 3         | 2.34%   |
| 5/4     | 2         | 1.56%   |
| 4/3     | 1         | 0.78%   |
| 3/2     | 1         | 0.78%   |
| 21/9    | 1         | 0.78%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 35        | 23.81%  |
| 201-250        | 25        | 17.01%  |
| 81-90          | 21        | 14.29%  |
| 301-350        | 20        | 13.61%  |
| 121-130        | 8         | 5.44%   |
| 71-80          | 6         | 4.08%   |
| 351-500        | 5         | 3.4%    |
| Unknown        | 5         | 3.4%    |
| 251-300        | 4         | 2.72%   |
| 111-120        | 4         | 2.72%   |
| More than 1000 | 3         | 2.04%   |
| 141-150        | 3         | 2.04%   |
| 501-1000       | 3         | 2.04%   |
| 131-140        | 2         | 1.36%   |
| 51-60          | 1         | 0.68%   |
| 151-200        | 1         | 0.68%   |
| 91-100         | 1         | 0.68%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 42        | 29.58%  |
| 121-160       | 41        | 28.87%  |
| 101-120       | 31        | 21.83%  |
| 161-240       | 13        | 9.15%   |
| More than 240 | 8         | 5.63%   |
| Unknown       | 5         | 3.52%   |
| 1-50          | 2         | 1.41%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 100       | 76.34%  |
| 2     | 24        | 18.32%  |
| 0     | 5         | 3.82%   |
| 3     | 2         | 1.53%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 89        | 45.64%  |
| Realtek Semiconductor           | 54        | 27.69%  |
| Qualcomm Atheros                | 18        | 9.23%   |
| Broadcom                        | 13        | 6.67%   |
| Marvell Technology Group        | 4         | 2.05%   |
| MediaTek                        | 3         | 1.54%   |
| Sierra Wireless                 | 2         | 1.03%   |
| DisplayLink                     | 2         | 1.03%   |
| TP-Link                         | 1         | 0.51%   |
| Shenzhen Goodix Technology      | 1         | 0.51%   |
| Ralink Technology               | 1         | 0.51%   |
| Qualcomm Atheros Communications | 1         | 0.51%   |
| Lenovo                          | 1         | 0.51%   |
| JMicron Technology              | 1         | 0.51%   |
| Huawei Technologies             | 1         | 0.51%   |
| Broadcom Limited                | 1         | 0.51%   |
| ASIX Electronics                | 1         | 0.51%   |
| Unknown                         | 1         | 0.51%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 38        | 16.31%  |
| Intel Wi-Fi 6 AX200                                                            | 15        | 6.44%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 7         | 3%      |
| Realtek RTL8125 2.5GbE Controller                                              | 6         | 2.58%   |
| Intel I211 Gigabit Network Connection                                          | 6         | 2.58%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 5         | 2.15%   |
| Intel Wireless 8265 / 8275                                                     | 5         | 2.15%   |
| Intel Wireless 8260                                                            | 5         | 2.15%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 5         | 2.15%   |
| Intel Wireless 7260                                                            | 4         | 1.72%   |
| Intel Ethernet Connection (2) I219-V                                           | 4         | 1.72%   |
| Intel Wireless 3160                                                            | 3         | 1.29%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                         | 3         | 1.29%   |
| Intel Ethernet Connection I219-V                                               | 3         | 1.29%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 3         | 1.29%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 3         | 1.29%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 2         | 0.86%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 2         | 0.86%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 2         | 0.86%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 2         | 0.86%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 2         | 0.86%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                  | 2         | 0.86%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.86%   |
| Intel Wireless-AC 9260                                                         | 2         | 0.86%   |
| Intel Wireless 7265                                                            | 2         | 0.86%   |
| Intel Wireless 3165                                                            | 2         | 0.86%   |
| Intel Wi-Fi 6 AX201                                                            | 2         | 0.86%   |
| Intel Tiger Lake PCH CNVi WiFi                                                 | 2         | 0.86%   |
| Intel Ethernet Controller I225-V                                               | 2         | 0.86%   |
| Intel Ethernet Connection I217-V                                               | 2         | 0.86%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 0.86%   |
| Intel Ethernet Connection (6) I219-V                                           | 2         | 0.86%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 0.86%   |
| Intel Ethernet Connection (2) I218-V                                           | 2         | 0.86%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 2         | 0.86%   |
| DisplayLink Dell D3100 Docking Station                                         | 2         | 0.86%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                             | 2         | 0.86%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 2         | 0.86%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                    | 1         | 0.43%   |
| Sierra Wireless EM7455                                                         | 1         | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 67        | 60.36%  |
| Qualcomm Atheros                | 15        | 13.51%  |
| Broadcom                        | 10        | 9.01%   |
| Realtek Semiconductor           | 9         | 8.11%   |
| MediaTek                        | 3         | 2.7%    |
| Sierra Wireless                 | 2         | 1.8%    |
| TP-Link                         | 1         | 0.9%    |
| Ralink Technology               | 1         | 0.9%    |
| Qualcomm Atheros Communications | 1         | 0.9%    |
| Marvell Technology Group        | 1         | 0.9%    |
| Broadcom Limited                | 1         | 0.9%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 15        | 13.39%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 5         | 4.46%   |
| Intel Wireless 8265 / 8275                                     | 5         | 4.46%   |
| Intel Wireless 8260                                            | 5         | 4.46%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 5         | 4.46%   |
| Intel Wireless 7260                                            | 4         | 3.57%   |
| Intel Wireless 3160                                            | 3         | 2.68%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 3         | 2.68%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 2.68%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.79%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2         | 1.79%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 1.79%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 1.79%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 1.79%   |
| Intel Wireless-AC 9260                                         | 2         | 1.79%   |
| Intel Wireless 7265                                            | 2         | 1.79%   |
| Intel Wireless 3165                                            | 2         | 1.79%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 1.79%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 2         | 1.79%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 1.79%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 2         | 1.79%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 1.79%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1         | 0.89%   |
| Sierra Wireless EM7455                                         | 1         | 0.89%   |
| Sierra Wireless EM7305 Modem                                   | 1         | 0.89%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.89%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 0.89%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 0.89%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 0.89%   |
| Realtek 802.11ac NIC                                           | 1         | 0.89%   |
| Ralink RT5370 Wireless Adapter                                 | 1         | 0.89%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 0.89%   |
| Qualcomm Atheros AR9271 802.11n                                | 1         | 0.89%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 0.89%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 0.89%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 1         | 0.89%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 0.89%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 0.89%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter            | 1         | 0.89%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless              | 1         | 0.89%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 52        | 45.61%  |
| Intel                    | 44        | 38.6%   |
| Qualcomm Atheros         | 5         | 4.39%   |
| Broadcom                 | 5         | 4.39%   |
| Marvell Technology Group | 3         | 2.63%   |
| DisplayLink              | 2         | 1.75%   |
| Lenovo                   | 1         | 0.88%   |
| JMicron Technology       | 1         | 0.88%   |
| ASIX Electronics         | 1         | 0.88%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 38        | 32.48%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 7         | 5.98%   |
| Realtek RTL8125 2.5GbE Controller                                              | 6         | 5.13%   |
| Intel I211 Gigabit Network Connection                                          | 6         | 5.13%   |
| Intel Ethernet Connection (2) I219-V                                           | 4         | 3.42%   |
| Intel Ethernet Connection I219-V                                               | 3         | 2.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 3         | 2.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 2         | 1.71%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 1.71%   |
| Intel Ethernet Controller I225-V                                               | 2         | 1.71%   |
| Intel Ethernet Connection I217-V                                               | 2         | 1.71%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 1.71%   |
| Intel Ethernet Connection (6) I219-V                                           | 2         | 1.71%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 1.71%   |
| Intel Ethernet Connection (2) I218-V                                           | 2         | 1.71%   |
| DisplayLink Dell D3100 Docking Station                                         | 2         | 1.71%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.85%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.85%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.85%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.85%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 0.85%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.85%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 0.85%   |
| Lenovo ThinkPad Lan                                                            | 1         | 0.85%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 0.85%   |
| Intel I210 Gigabit Network Connection                                          | 1         | 0.85%   |
| Intel Ethernet controller                                                      | 1         | 0.85%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.85%   |
| Intel Ethernet Connection (7) I219-V                                           | 1         | 0.85%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.85%   |
| Intel Ethernet Connection (6) I219-LM                                          | 1         | 0.85%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1         | 0.85%   |
| Intel Ethernet Connection (3) I219-LM                                          | 1         | 0.85%   |
| Intel Ethernet Connection (3) I218-V                                           | 1         | 0.85%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 0.85%   |
| Intel Ethernet Connection (17) I219-LM                                         | 1         | 0.85%   |
| Intel Ethernet Connection (14) I219-LM                                         | 1         | 0.85%   |
| Intel Ethernet Connection (11) I219-V                                          | 1         | 0.85%   |
| Intel 82577LC Gigabit Network Connection                                       | 1         | 0.85%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 1         | 0.85%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 106       | 49.07%  |
| Ethernet | 106       | 49.07%  |
| Modem    | 2         | 0.93%   |
| Unknown  | 2         | 0.93%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 76        | 55.07%  |
| Ethernet | 62        | 44.93%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 73        | 56.59%  |
| 1     | 50        | 38.76%  |
| 3     | 6         | 4.65%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 102       | 78.46%  |
| Yes  | 28        | 21.54%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 59        | 64.13%  |
| Foxconn / Hon Hai               | 6         | 6.52%   |
| Qualcomm Atheros Communications | 4         | 4.35%   |
| IMC Networks                    | 4         | 4.35%   |
| Cambridge Silicon Radio         | 4         | 4.35%   |
| Apple                           | 3         | 3.26%   |
| Realtek                         | 2         | 2.17%   |
| Lite-On Technology              | 2         | 2.17%   |
| Hewlett-Packard                 | 2         | 2.17%   |
| Toshiba                         | 1         | 1.09%   |
| Realtek Semiconductor           | 1         | 1.09%   |
| Micro Star International        | 1         | 1.09%   |
| Marvell Semiconductor           | 1         | 1.09%   |
| Broadcom                        | 1         | 1.09%   |
| ASUSTek Computer                | 1         | 1.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 20        | 21.74%  |
| Intel AX200 Bluetooth                                                               | 14        | 15.22%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 8         | 8.7%    |
| Intel AX201 Bluetooth                                                               | 7         | 7.61%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 4         | 4.35%   |
| Intel AX210 Bluetooth                                                               | 3         | 3.26%   |
| Realtek Bluetooth Radio                                                             | 2         | 2.17%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 2         | 2.17%   |
| Lite-On Bluetooth Device                                                            | 2         | 2.17%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 2.17%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 2.17%   |
| Intel Bluetooth Device                                                              | 2         | 2.17%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 2.17%   |
| Apple Bluetooth USB Host Controller                                                 | 2         | 2.17%   |
| Toshiba Bluetooth Device                                                            | 1         | 1.09%   |
| Realtek Bluetooth Radio                                                             | 1         | 1.09%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 1.09%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 1.09%   |
| Micro Star International Motorola Bluetooth 2.1+EDR Device                          | 1         | 1.09%   |
| Marvell Bluetooth and Wireless LAN Composite                                        | 1         | 1.09%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 1.09%   |
| IMC Networks Wireless_Device                                                        | 1         | 1.09%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 1.09%   |
| IMC Networks Bluetooth Module                                                       | 1         | 1.09%   |
| IMC Networks Bluetooth Device                                                       | 1         | 1.09%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 1         | 1.09%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.09%   |
| Foxconn / Hon Hai BT                                                                | 1         | 1.09%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 1.09%   |
| Foxconn / Hon Hai BCM43142A0                                                        | 1         | 1.09%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 1.09%   |
| Broadcom Bluetooth 3.0 Device                                                       | 1         | 1.09%   |
| ASUS BCM20702A0                                                                     | 1         | 1.09%   |
| Apple Bluetooth Host Controller                                                     | 1         | 1.09%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 102       | 58.62%  |
| AMD                            | 31        | 17.82%  |
| Nvidia                         | 28        | 16.09%  |
| SteelSeries ApS                | 2         | 1.15%   |
| Logitech                       | 2         | 1.15%   |
| Hewlett-Packard                | 2         | 1.15%   |
| www.hirestech.com 2010 REV 1.4 | 1         | 0.57%   |
| Sony                           | 1         | 0.57%   |
| Realtek Semiconductor          | 1         | 0.57%   |
| Lenovo                         | 1         | 0.57%   |
| C-Media Electronics            | 1         | 0.57%   |
| Bose                           | 1         | 0.57%   |
| Apple                          | 1         | 0.57%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 15        | 7.04%   |
| AMD Family 17h/19h HD Audio Controller                                     | 15        | 7.04%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 13        | 6.1%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 11        | 5.16%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 11        | 5.16%   |
| AMD Starship/Matisse HD Audio Controller                                   | 7         | 3.29%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 6         | 2.82%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 6         | 2.82%   |
| Intel Cannon Lake PCH cAVS                                                 | 6         | 2.82%   |
| Intel 200 Series PCH HD Audio                                              | 6         | 2.82%   |
| Intel Haswell-ULT HD Audio Controller                                      | 5         | 2.35%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 2.35%   |
| Intel 8 Series HD Audio Controller                                         | 5         | 2.35%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4         | 1.88%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 1.88%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 1.88%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 1.88%   |
| Nvidia High Definition Audio Controller                                    | 3         | 1.41%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 1.41%   |
| Intel Comet Lake PCH cAVS                                                  | 3         | 1.41%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 1.41%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 1.41%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 1.41%   |
| Nvidia GP108 High Definition Audio Controller                              | 2         | 0.94%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 0.94%   |
| Nvidia GA106 High Definition Audio Controller                              | 2         | 0.94%   |
| Nvidia Audio device                                                        | 2         | 0.94%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 0.94%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 0.94%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2         | 0.94%   |
| Hewlett-Packard USB Audio                                                  | 2         | 0.94%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 0.94%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 2         | 0.94%   |
| www.hirestech.com 2010 REV 1.4 Music Streamer Pro                          | 1         | 0.47%   |
| SteelSeries ApS SteelSeries Arctis 7                                       | 1         | 0.47%   |
| SteelSeries ApS Arctis Nova 3                                              | 1         | 0.47%   |
| Sony DualShock 4 [CUH-ZCT2x]                                               | 1         | 0.47%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.47%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 0.47%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.47%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 29        | 34.12%  |
| SK hynix                     | 13        | 15.29%  |
| Kingston                     | 7         | 8.24%   |
| Micron Technology            | 6         | 7.06%   |
| Crucial                      | 6         | 7.06%   |
| Corsair                      | 6         | 7.06%   |
| Unknown                      | 4         | 4.71%   |
| G.Skill                      | 4         | 4.71%   |
| A-DATA Technology            | 4         | 4.71%   |
| Qimonda                      | 2         | 2.35%   |
| Wilk                         | 1         | 1.18%   |
| Unknown (0x7F7FB5FFFFFFFFFF) | 1         | 1.18%   |
| Timetec                      | 1         | 1.18%   |
| Dane-Elec                    | 1         | 1.18%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s     | 3         | 3.3%    |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                  | 2         | 2.2%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s         | 2         | 2.2%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s         | 2         | 2.2%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s         | 2         | 2.2%    |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s        | 2         | 2.2%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s         | 2         | 2.2%    |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s       | 2         | 2.2%    |
| Wilk RAM GR3200S464L22S/16G 16GB SODIMM DDR4 3200MT/s         | 1         | 1.1%    |
| Unknown RAM Module 4GB SODIMM DDR3                            | 1         | 1.1%    |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                  | 1         | 1.1%    |
| Unknown RAM Module 2GB SODIMM DDR2                            | 1         | 1.1%    |
| Unknown RAM Module 2048MB SODIMM DDR2                         | 1         | 1.1%    |
| Unknown RAM Module 1024MB SODIMM DDR2                         | 1         | 1.1%    |
| Unknown (0x7F7FB5FFFFFFFFFF) RAM Module 1GB DIMM DDR2 667MT/s | 1         | 1.1%    |
| Timetec RAM SD3-1333 8192MB SODIMM DDR3 1333MT/s              | 1         | 1.1%    |
| SK hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s       | 1         | 1.1%    |
| SK hynix RAM Module 4096MB Row Of Chips LPDDR3 2133MT/s       | 1         | 1.1%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 1         | 1.1%    |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s        | 1         | 1.1%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s        | 1         | 1.1%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s        | 1         | 1.1%    |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s       | 1         | 1.1%    |
| SK hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s       | 1         | 1.1%    |
| SK hynix RAM HMA82GR7CJR8N-VK 16GB DIMM DDR4 2666MT/s         | 1         | 1.1%    |
| SK hynix RAM HMA82GR7AFR8N-VK 16GB DIMM DDR4 2666MT/s         | 1         | 1.1%    |
| SK hynix RAM HMA81GS6MFR8N-UH 8GB SODIMM DDR4 2400MT/s        | 1         | 1.1%    |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s        | 1         | 1.1%    |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                   | 1         | 1.1%    |
| Samsung RAM Module 8GB Row Of Chips LPDDR4 2933MT/s           | 1         | 1.1%    |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                   | 1         | 1.1%    |
| Samsung RAM Module 4GB SODIMM DDR3 1067MT/s                   | 1         | 1.1%    |
| Samsung RAM Module 16384MB SODIMM DDR4 3200MT/s               | 1         | 1.1%    |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s         | 1         | 1.1%    |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s         | 1         | 1.1%    |
| Samsung RAM M471B5173EB0-YK0 4096MB SODIMM DDR3 1600MT/s      | 1         | 1.1%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s         | 1         | 1.1%    |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s         | 1         | 1.1%    |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s        | 1         | 1.1%    |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s        | 1         | 1.1%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 45        | 57.69%  |
| DDR3   | 20        | 25.64%  |
| DDR2   | 5         | 6.41%   |
| LPDDR3 | 4         | 5.13%   |
| DDR5   | 2         | 2.56%   |
| SDRAM  | 1         | 1.28%   |
| LPDDR4 | 1         | 1.28%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 51        | 66.23%  |
| DIMM         | 20        | 25.97%  |
| Row Of Chips | 6         | 7.79%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 36        | 42.86%  |
| 16384 | 20        | 23.81%  |
| 4096  | 15        | 17.86%  |
| 2048  | 8         | 9.52%   |
| 32768 | 3         | 3.57%   |
| 1024  | 2         | 2.38%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 18        | 22.22%  |
| 3200    | 15        | 18.52%  |
| 1600    | 12        | 14.81%  |
| 2400    | 8         | 9.88%   |
| 2133    | 6         | 7.41%   |
| 3600    | 4         | 4.94%   |
| Unknown | 3         | 3.7%    |
| 1333    | 2         | 2.47%   |
| 800     | 2         | 2.47%   |
| 6400    | 1         | 1.23%   |
| 4800    | 1         | 1.23%   |
| 3534    | 1         | 1.23%   |
| 3500    | 1         | 1.23%   |
| 3400    | 1         | 1.23%   |
| 2933    | 1         | 1.23%   |
| 2666    | 1         | 1.23%   |
| 1867    | 1         | 1.23%   |
| 1334    | 1         | 1.23%   |
| 1067    | 1         | 1.23%   |
| 667     | 1         | 1.23%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 3         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                    | Computers | Percent |
|--------------------------|-----------|---------|
| HP OfficeJet 6950        | 1         | 33.33%  |
| HP Officejet 6600        | 1         | 33.33%  |
| HP OfficeJet 5200 series | 1         | 33.33%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 23        | 27.38%  |
| Microdia                               | 11        | 13.1%   |
| IMC Networks                           | 9         | 10.71%  |
| Logitech                               | 6         | 7.14%   |
| Samsung Electronics                    | 4         | 4.76%   |
| Quanta                                 | 4         | 4.76%   |
| Ricoh                                  | 3         | 3.57%   |
| Realtek Semiconductor                  | 3         | 3.57%   |
| Alcor Micro                            | 3         | 3.57%   |
| Sunplus Innovation Technology          | 2         | 2.38%   |
| Luxvisions Innotech Limited            | 2         | 2.38%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.38%   |
| Bison Electronics                      | 2         | 2.38%   |
| Apple                                  | 2         | 2.38%   |
| Acer                                   | 2         | 2.38%   |
| YGTek                                  | 1         | 1.19%   |
| ShineTech                              | 1         | 1.19%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 1.19%   |
| Lite-On Technology                     | 1         | 1.19%   |
| Huawei Technologies                    | 1         | 1.19%   |
| ALi                                    | 1         | 1.19%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                   | 5         | 5.95%   |
| IMC Networks USB2.0 HD UVC WebCam               | 5         | 5.95%   |
| Samsung Galaxy A5 (MTP)                         | 4         | 4.76%   |
| Logitech B525 HD Webcam                         | 3         | 3.57%   |
| IMC Networks Integrated Camera                  | 3         | 3.57%   |
| Chicony Integrated Camera                       | 3         | 3.57%   |
| Realtek Integrated_Webcam_HD                    | 2         | 2.38%   |
| Quanta HD User Facing                           | 2         | 2.38%   |
| Microdia Integrated Webcam                      | 2         | 2.38%   |
| Luxvisions Innotech Limited HP HD Camera        | 2         | 2.38%   |
| Chicony Integrated IR Camera                    | 2         | 2.38%   |
| Chicony Integrated Camera (1280x720@30)         | 2         | 2.38%   |
| Chicony HP Wide Vision HD Camera                | 2         | 2.38%   |
| Chicony HP HD Camera                            | 2         | 2.38%   |
| Alcor Micro USB 2.0 Camera                      | 2         | 2.38%   |
| YGTek Webcam                                    | 1         | 1.19%   |
| Sunplus Laptop Integrated WebCam HD             | 1         | 1.19%   |
| Sunplus HP HD Webcam [Fixed]                    | 1         | 1.19%   |
| ShineTech HD Camera                             | 1         | 1.19%   |
| Shenzhen Kingcome Optoelectronic 720p HD Camera | 1         | 1.19%   |
| Ricoh USB2.0 Camera                             | 1         | 1.19%   |
| Ricoh Sony Visual Communication Camera          | 1         | 1.19%   |
| Ricoh Sony Vaio Integrated Webcam               | 1         | 1.19%   |
| Realtek HP Truevision HD                        | 1         | 1.19%   |
| Quanta HP Wide Vision HD Camera                 | 1         | 1.19%   |
| Quanta HP Webcam                                | 1         | 1.19%   |
| Microdia Webcam Vitade AF                       | 1         | 1.19%   |
| Microdia Webcam                                 | 1         | 1.19%   |
| Microdia REDRAGON Live Camera Audio             | 1         | 1.19%   |
| Microdia Integrated_Webcam_FHD                  | 1         | 1.19%   |
| Logitech Webcam C270                            | 1         | 1.19%   |
| Logitech HD Webcam C910                         | 1         | 1.19%   |
| Logitech HD Pro Webcam C920                     | 1         | 1.19%   |
| Lite-On HP Full-HD Camera                       | 1         | 1.19%   |
| IMC Networks ov9734_azurewave_camera            | 1         | 1.19%   |
| Huawei UVC Camera                               | 1         | 1.19%   |
| Chicony USB2.0 VGA UVC WebCam                   | 1         | 1.19%   |
| Chicony USB2.0 HD UVC WebCam                    | 1         | 1.19%   |
| Chicony USB 2.0 Camera                          | 1         | 1.19%   |
| Chicony TOSHIBA Web Camera - HD                 | 1         | 1.19%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 8         | 38.1%   |
| Validity Sensors           | 5         | 23.81%  |
| Shenzhen Goodix Technology | 4         | 19.05%  |
| Upek                       | 1         | 4.76%   |
| LighTuning Technology      | 1         | 4.76%   |
| Elan Microelectronics      | 1         | 4.76%   |
| AuthenTec                  | 1         | 4.76%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 4         | 19.05%  |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 14.29%  |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 4.76%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 4.76%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 4.76%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 4.76%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 4.76%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 4.76%   |
| Synaptics UWP WBDI                                                         | 1         | 4.76%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 4.76%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 4.76%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 4.76%   |
| Shenzhen Goodix  Fingerprint Device                                        | 1         | 4.76%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 4.76%   |
| Elan ELAN:Fingerprint                                                      | 1         | 4.76%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 4.76%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 5         | 50%     |
| Gemalto (was Gemplus) | 3         | 30%     |
| Broadcom              | 2         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 5         | 50%     |
| Gemalto (was Gemplus) Prox SU USB PC Link Reader                             | 2         | 20%     |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 10%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 10%     |
| Broadcom 58200                                                               | 1         | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 78        | 59.09%  |
| 1     | 37        | 28.03%  |
| 2     | 15        | 11.36%  |
| 3     | 2         | 1.52%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 21        | 30.43%  |
| Graphics card            | 14        | 20.29%  |
| Multimedia controller    | 6         | 8.7%    |
| Chipcard                 | 6         | 8.7%    |
| Net/wireless             | 5         | 7.25%   |
| Network                  | 4         | 5.8%    |
| Communication controller | 3         | 4.35%   |
| Card reader              | 3         | 4.35%   |
| Unassigned class         | 2         | 2.9%    |
| Net/ethernet             | 2         | 2.9%    |
| Sound                    | 1         | 1.45%   |
| Camera                   | 1         | 1.45%   |
| Bluetooth                | 1         | 1.45%   |

