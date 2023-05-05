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

Total: 169

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04                 | 20        | 14.93%  |
| Ubuntu 18.04                 | 10        | 7.46%   |
| Ubuntu 22.04                 | 9         | 6.72%   |
| Ubuntu 21.04                 | 4         | 2.99%   |
| Linux Mint 20.3              | 4         | 2.99%   |
| Ubuntu 20.10                 | 3         | 2.24%   |
| Pop!_OS 22.04                | 3         | 2.24%   |
| Pop!_OS 21.04                | 3         | 2.24%   |
| openSUSE Tumbleweed-XXXXXXXX | 3         | 2.24%   |
| OpenMandriva 4.2             | 3         | 2.24%   |
| Fedora 32                    | 3         | 2.24%   |
| Xubuntu 20.04                | 2         | 1.49%   |
| Ubuntu 18.10                 | 2         | 1.49%   |
| ROSA R9                      | 2         | 1.49%   |
| Pop!_OS 21.10                | 2         | 1.49%   |
| openSUSE Leap-15.2           | 2         | 1.49%   |
| OpenMandriva 4.90            | 2         | 1.49%   |
| OpenMandriva 23.03           | 2         | 1.49%   |
| LMDE 4                       | 2         | 1.49%   |
| Kubuntu 22.04                | 2         | 1.49%   |
| Debian 10                    | 2         | 1.49%   |
| Zorin 16                     | 1         | 0.75%   |
| Xubuntu 18.04                | 1         | 0.75%   |
| Xubuntu 16.04                | 1         | 0.75%   |
| UbuntuDDE 20.04              | 1         | 0.75%   |
| Ubuntu MATE 21.10            | 1         | 0.75%   |
| Ubuntu MATE 20.04            | 1         | 0.75%   |
| Ubuntu 22.10                 | 1         | 0.75%   |
| Ubuntu 19.10                 | 1         | 0.75%   |
| RHEL 8                       | 1         | 0.75%   |
| Pop!_OS 20.10                | 1         | 0.75%   |
| Pop!_OS 20.04                | 1         | 0.75%   |
| Parrot 5.1                   | 1         | 0.75%   |
| openSUSE Leap-15.3           | 1         | 0.75%   |
| openSUSE Leap-15.1           | 1         | 0.75%   |
| OpenMandriva 4.3             | 1         | 0.75%   |
| Manjaro 21.2.6               | 1         | 0.75%   |
| Manjaro 21.1.0               | 1         | 0.75%   |
| Manjaro 19.0.2               | 1         | 0.75%   |
| Mageia 7                     | 1         | 0.75%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 48        | 37.8%   |
| Pop!_OS      | 9         | 7.09%   |
| OpenMandriva | 8         | 6.3%    |
| Fedora       | 7         | 5.51%   |
| openSUSE     | 6         | 4.72%   |
| Linux Mint   | 6         | 4.72%   |
| Xubuntu      | 4         | 3.15%   |
| Kubuntu      | 4         | 3.15%   |
| Manjaro      | 3         | 2.36%   |
| Debian       | 3         | 2.36%   |
| Ubuntu MATE  | 2         | 1.57%   |
| ROSA         | 2         | 1.57%   |
| Lubuntu      | 2         | 1.57%   |
| LMDE         | 2         | 1.57%   |
| KDE neon     | 2         | 1.57%   |
| Kali         | 2         | 1.57%   |
| Endless      | 2         | 1.57%   |
| Elementary   | 2         | 1.57%   |
| Arch         | 2         | 1.57%   |
| Zorin        | 1         | 0.79%   |
| UbuntuDDE    | 1         | 0.79%   |
| RHEL         | 1         | 0.79%   |
| Parrot       | 1         | 0.79%   |
| Mageia       | 1         | 0.79%   |
| Gentoo       | 1         | 0.79%   |
| Garuda Linux | 1         | 0.79%   |
| Clear Linux  | 1         | 0.79%   |
| CentOS       | 1         | 0.79%   |
| BlackPanther | 1         | 0.79%   |
| ArcoLinux    | 1         | 0.79%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.8.0-43-generic                | 3         | 2.16%   |
| 5.15.0-52-generic               | 3         | 2.16%   |
| 5.11.0-27-generic               | 3         | 2.16%   |
| 5.10.14-desktop-1omv4002        | 3         | 2.16%   |
| 6.2.6-desktop-1omv2390          | 2         | 1.44%   |
| 5.8.0-59-generic                | 2         | 1.44%   |
| 5.4.0-96-generic                | 2         | 1.44%   |
| 5.4.0-90-generic                | 2         | 1.44%   |
| 5.4.0-47-generic                | 2         | 1.44%   |
| 5.4.0-42-generic                | 2         | 1.44%   |
| 5.4.0-122-generic               | 2         | 1.44%   |
| 5.3.0-46-generic                | 2         | 1.44%   |
| 5.19.0-35-generic               | 2         | 1.44%   |
| 5.18.12-desktop-3omv4090        | 2         | 1.44%   |
| 5.16.11-76051611-generic        | 2         | 1.44%   |
| 5.11.0-34-generic               | 2         | 1.44%   |
| 5.11.0-17-generic               | 2         | 1.44%   |
| 5.0.0-23-generic                | 2         | 1.44%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 2         | 1.44%   |
| 4.19.0-17-amd64                 | 2         | 1.44%   |
| 6.1.8-060108-generic            | 1         | 0.72%   |
| 6.1.22-gentoo-dist              | 1         | 0.72%   |
| 6.1.10-200.fc37.x86_64          | 1         | 0.72%   |
| 6.0.6-76060006-generic          | 1         | 0.72%   |
| 6.0.0-kali3-amd64               | 1         | 0.72%   |
| 5.9.13-zen1-1-zen               | 1         | 0.72%   |
| 5.9.10-200.fc33.x86_64          | 1         | 0.72%   |
| 5.8.11-050811-generic           | 1         | 0.72%   |
| 5.8.0-63-generic                | 1         | 0.72%   |
| 5.8.0-55-generic                | 1         | 0.72%   |
| 5.8.0-44-generic                | 1         | 0.72%   |
| 5.8.0-31-generic                | 1         | 0.72%   |
| 5.8.0-26-generic                | 1         | 0.72%   |
| 5.8.0-20-generic                | 1         | 0.72%   |
| 5.8.0-14-generic                | 1         | 0.72%   |
| 5.7.6-201.fc32.x86_64           | 1         | 0.72%   |
| 5.7.19-desktop-3.mga7           | 1         | 0.72%   |
| 5.7.14-200.fc32.x86_64          | 1         | 0.72%   |
| 5.7.1-1-default                 | 1         | 0.72%   |
| 5.7.0-3-amd64                   | 1         | 0.72%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 19        | 14.39%  |
| 5.11.0  | 14        | 10.61%  |
| 5.15.0  | 13        | 9.85%   |
| 5.8.0   | 10        | 7.58%   |
| 5.3.0   | 6         | 4.55%   |
| 4.18.0  | 6         | 4.55%   |
| 5.19.0  | 5         | 3.79%   |
| 5.13.0  | 4         | 3.03%   |
| 4.15.0  | 4         | 3.03%   |
| 5.10.14 | 3         | 2.27%   |
| 5.0.0   | 3         | 2.27%   |
| 6.2.6   | 2         | 1.52%   |
| 5.7.0   | 2         | 1.52%   |
| 5.3.18  | 2         | 1.52%   |
| 5.18.12 | 2         | 1.52%   |
| 5.16.11 | 2         | 1.52%   |
| 5.10.0  | 2         | 1.52%   |
| 4.9.20  | 2         | 1.52%   |
| 4.19.0  | 2         | 1.52%   |
| 6.1.8   | 1         | 0.76%   |
| 6.1.22  | 1         | 0.76%   |
| 6.1.10  | 1         | 0.76%   |
| 6.0.6   | 1         | 0.76%   |
| 6.0.0   | 1         | 0.76%   |
| 5.9.13  | 1         | 0.76%   |
| 5.9.10  | 1         | 0.76%   |
| 5.8.11  | 1         | 0.76%   |
| 5.7.6   | 1         | 0.76%   |
| 5.7.19  | 1         | 0.76%   |
| 5.7.14  | 1         | 0.76%   |
| 5.7.1   | 1         | 0.76%   |
| 5.6.3   | 1         | 0.76%   |
| 5.5.8   | 1         | 0.76%   |
| 5.18.5  | 1         | 0.76%   |
| 5.18.0  | 1         | 0.76%   |
| 5.16.7  | 1         | 0.76%   |
| 5.16.2  | 1         | 0.76%   |
| 5.15.4  | 1         | 0.76%   |
| 5.15.32 | 1         | 0.76%   |
| 5.14.0  | 1         | 0.76%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 19        | 14.39%  |
| 5.15    | 15        | 11.36%  |
| 5.11    | 14        | 10.61%  |
| 5.8     | 11        | 8.33%   |
| 5.3     | 8         | 6.06%   |
| 5.10    | 7         | 5.3%    |
| 4.18    | 7         | 5.3%    |
| 5.7     | 6         | 4.55%   |
| 5.19    | 5         | 3.79%   |
| 5.13    | 5         | 3.79%   |
| 5.18    | 4         | 3.03%   |
| 5.16    | 4         | 3.03%   |
| 4.15    | 4         | 3.03%   |
| 6.1     | 3         | 2.27%   |
| 5.0     | 3         | 2.27%   |
| 6.2     | 2         | 1.52%   |
| 6.0     | 2         | 1.52%   |
| 5.9     | 2         | 1.52%   |
| 5.12    | 2         | 1.52%   |
| 4.9     | 2         | 1.52%   |
| 4.19    | 2         | 1.52%   |
| 5.6     | 1         | 0.76%   |
| 5.5     | 1         | 0.76%   |
| 5.14    | 1         | 0.76%   |
| 4.4     | 1         | 0.76%   |
| 4.12    | 1         | 0.76%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 122       | 98.39%  |
| i686   | 2         | 1.61%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 58        | 45.31%  |
| KDE5            | 22        | 17.19%  |
| Unknown         | 14        | 10.94%  |
| XFCE            | 8         | 6.25%   |
| X-Cinnamon      | 8         | 6.25%   |
| KDE             | 5         | 3.91%   |
| MATE            | 3         | 2.34%   |
| Pantheon        | 2         | 1.56%   |
| LXQt            | 2         | 1.56%   |
| i3              | 2         | 1.56%   |
| Cinnamon        | 2         | 1.56%   |
| GNOME Flashback | 1         | 0.78%   |
| Deepin          | 1         | 0.78%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 98        | 76.56%  |
| Wayland | 17        | 13.28%  |
| Unknown | 9         | 7.03%   |
| Tty     | 4         | 3.13%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 61        | 46.92%  |
| SDDM    | 20        | 15.38%  |
| GDM     | 18        | 13.85%  |
| LightDM | 16        | 12.31%  |
| GDM3    | 11        | 8.46%   |
| TDM     | 4         | 3.08%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 53        | 41.41%  |
| Unknown | 13        | 10.16%  |
| en_GB   | 11        | 8.59%   |
| fr_FR   | 10        | 7.81%   |
| de_LU   | 9         | 7.03%   |
| de_DE   | 7         | 5.47%   |
| C       | 6         | 4.69%   |
| fr_LU   | 4         | 3.13%   |
| es_ES   | 3         | 2.34%   |
| nl_NL   | 2         | 1.56%   |
| unm_US  | 1         | 0.78%   |
| pt_PT   | 1         | 0.78%   |
| pt_BR   | 1         | 0.78%   |
| POSIX   | 1         | 0.78%   |
| lb_LU   | 1         | 0.78%   |
| it_IT   | 1         | 0.78%   |
| hr_HR   | 1         | 0.78%   |
| fr_CH   | 1         | 0.78%   |
| en_IE   | 1         | 0.78%   |
| de_CH   | 1         | 0.78%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 66        | 52.38%  |
| BIOS | 60        | 47.62%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 94        | 75.2%   |
| Btrfs   | 12        | 9.6%    |
| Overlay | 9         | 7.2%    |
| Xfs     | 5         | 4%      |
| Unknown | 4         | 3.2%    |
| Zfs     | 1         | 0.8%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 61        | 48.8%   |
| GPT     | 54        | 43.2%   |
| MBR     | 10        | 8%      |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 111       | 88.8%   |
| Yes       | 14        | 11.2%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 89        | 71.2%   |
| Yes       | 36        | 28.8%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 19        | 15.32%  |
| Hewlett-Packard     | 17        | 13.71%  |
| Lenovo              | 12        | 9.68%   |
| Dell                | 10        | 8.06%   |
| Gigabyte Technology | 8         | 6.45%   |
| Intel               | 6         | 4.84%   |
| Sony                | 5         | 4.03%   |
| MSI                 | 5         | 4.03%   |
| Apple               | 5         | 4.03%   |
| Acer                | 5         | 4.03%   |
| Medion              | 4         | 3.23%   |
| ASRock              | 4         | 3.23%   |
| Wortmann AG         | 3         | 2.42%   |
| HUAWEI              | 3         | 2.42%   |
| win element         | 2         | 1.61%   |
| Samsung Electronics | 2         | 1.61%   |
| Fujitsu             | 2         | 1.61%   |
| Clevo               | 2         | 1.61%   |
| YJKC                | 1         | 0.81%   |
| TUXEDO              | 1         | 0.81%   |
| Toshiba             | 1         | 0.81%   |
| Timi                | 1         | 0.81%   |
| SLIMBOOK            | 1         | 0.81%   |
| Packard Bell        | 1         | 0.81%   |
| Microsoft           | 1         | 0.81%   |
| LattePanda          | 1         | 0.81%   |
| JWIPC               | 1         | 0.81%   |
| Foxconn             | 1         | 0.81%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| ASUS All Series                          | 3         | 2.42%   |
| win element MoreFine S500+               | 2         | 1.61%   |
| Dell Precision M3800                     | 2         | 1.61%   |
| YJKC vBook                               | 1         | 0.81%   |
| Wortmann AG TERRA_MOBILE_1749            | 1         | 0.81%   |
| Wortmann AG TERRA_MOBILE_1541H           | 1         | 0.81%   |
| Wortmann AG MS-1727                      | 1         | 0.81%   |
| TUXEDO Pulse 14 Gen1                     | 1         | 0.81%   |
| Toshiba Satellite C55-A-1N0              | 1         | 0.81%   |
| Timi RedmiBook 14 II                     | 1         | 0.81%   |
| Sony VPCP11S1R                           | 1         | 0.81%   |
| Sony VPCEB2E1E                           | 1         | 0.81%   |
| Sony VPCCA4E1E                           | 1         | 0.81%   |
| Sony VGN-NS30E_S                         | 1         | 0.81%   |
| Sony SVF1421E2EW                         | 1         | 0.81%   |
| SLIMBOOK EXECUTIVE-14                    | 1         | 0.81%   |
| Samsung Galaxy TabPro S LTE              | 1         | 0.81%   |
| Samsung 950QDB                           | 1         | 0.81%   |
| Packard Bell EasyNote TJ65               | 1         | 0.81%   |
| MSI MS-7C80                              | 1         | 0.81%   |
| MSI MS-7C08                              | 1         | 0.81%   |
| MSI MS-7816                              | 1         | 0.81%   |
| MSI MS-7578                              | 1         | 0.81%   |
| MSI GF72 8RD                             | 1         | 0.81%   |
| Microsoft Surface Book 2                 | 1         | 0.81%   |
| Medion P961x                             | 1         | 0.81%   |
| Medion P6685 MD61138                     | 1         | 0.81%   |
| Medion MS-7848                           | 1         | 0.81%   |
| Medion E4254 MD62100                     | 1         | 0.81%   |
| Lenovo ThinkPad X1 Carbon 7th 20QDCTO1WW | 1         | 0.81%   |
| Lenovo ThinkPad T590 20N4CTO1WW          | 1         | 0.81%   |
| Lenovo ThinkPad T490 20N3S5DV0S          | 1         | 0.81%   |
| Lenovo ThinkPad T480s 20L7001PFR         | 1         | 0.81%   |
| Lenovo ThinkPad T470s W10DG 20JTS0R800   | 1         | 0.81%   |
| Lenovo ThinkPad T440p 20AWS24B00         | 1         | 0.81%   |
| Lenovo ThinkPad P1 Gen 2 20QTCTO1WW      | 1         | 0.81%   |
| Lenovo ThinkPad L15 Gen 1 20U8S0AH00     | 1         | 0.81%   |
| Lenovo ThinkPad L15 Gen 1 20U7S05B00     | 1         | 0.81%   |
| Lenovo ThinkCentre M910s 10MKS02N04      | 1         | 0.81%   |
| Lenovo IdeaPad 330-15ICH 81FK            | 1         | 0.81%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 9         | 7.26%   |
| Dell Precision        | 6         | 4.84%   |
| HP EliteBook          | 5         | 4.03%   |
| ASUS PRIME            | 4         | 3.23%   |
| Acer Aspire           | 4         | 3.23%   |
| HP ENVY               | 3         | 2.42%   |
| ASUS VivoBook         | 3         | 2.42%   |
| ASUS All              | 3         | 2.42%   |
| Wortmann AG TERRA     | 2         | 1.61%   |
| win element MoreFine  | 2         | 1.61%   |
| HP ProBook            | 2         | 1.61%   |
| HP Compaq             | 2         | 1.61%   |
| Dell XPS              | 2         | 1.61%   |
| ASUS TUF              | 2         | 1.61%   |
| ASUS ROG              | 2         | 1.61%   |
| YJKC vBook            | 1         | 0.81%   |
| Wortmann AG MS-1727   | 1         | 0.81%   |
| TUXEDO Pulse          | 1         | 0.81%   |
| Toshiba Satellite     | 1         | 0.81%   |
| Timi RedmiBook        | 1         | 0.81%   |
| Sony VPCP11S1R        | 1         | 0.81%   |
| Sony VPCEB2E1E        | 1         | 0.81%   |
| Sony VPCCA4E1E        | 1         | 0.81%   |
| Sony VGN-NS30E        | 1         | 0.81%   |
| Sony SVF1421E2EW      | 1         | 0.81%   |
| SLIMBOOK EXECUTIVE-14 | 1         | 0.81%   |
| Samsung Galaxy        | 1         | 0.81%   |
| Samsung 950QDB        | 1         | 0.81%   |
| Packard Bell EasyNote | 1         | 0.81%   |
| MSI MS-7C80           | 1         | 0.81%   |
| MSI MS-7C08           | 1         | 0.81%   |
| MSI MS-7816           | 1         | 0.81%   |
| MSI MS-7578           | 1         | 0.81%   |
| MSI GF72              | 1         | 0.81%   |
| Microsoft Surface     | 1         | 0.81%   |
| Medion P961x          | 1         | 0.81%   |
| Medion P6685          | 1         | 0.81%   |
| Medion MS-7848        | 1         | 0.81%   |
| Medion E4254          | 1         | 0.81%   |
| Lenovo ThinkCentre    | 1         | 0.81%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2018 | 16        | 12.9%   |
| 2019 | 15        | 12.1%   |
| 2017 | 13        | 10.48%  |
| 2013 | 12        | 9.68%   |
| 2020 | 11        | 8.87%   |
| 2021 | 10        | 8.06%   |
| 2014 | 10        | 8.06%   |
| 2010 | 9         | 7.26%   |
| 2016 | 6         | 4.84%   |
| 2011 | 5         | 4.03%   |
| 2015 | 4         | 3.23%   |
| 2022 | 3         | 2.42%   |
| 2012 | 3         | 2.42%   |
| 2009 | 3         | 2.42%   |
| 2007 | 2         | 1.61%   |
| 2023 | 1         | 0.81%   |
| 2008 | 1         | 0.81%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 75        | 60.48%  |
| Desktop     | 39        | 31.45%  |
| Mini pc     | 4         | 3.23%   |
| Convertible | 3         | 2.42%   |
| Tablet      | 2         | 1.61%   |
| All in one  | 1         | 0.81%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 114       | 91.94%  |
| Enabled  | 10        | 8.06%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 124       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 37        | 29.37%  |
| 8.01-16.0   | 28        | 22.22%  |
| 4.01-8.0    | 23        | 18.25%  |
| 3.01-4.0    | 16        | 12.7%   |
| 32.01-64.0  | 13        | 10.32%  |
| 64.01-256.0 | 3         | 2.38%   |
| 24.01-32.0  | 2         | 1.59%   |
| 2.01-3.0    | 2         | 1.59%   |
| 1.01-2.0    | 2         | 1.59%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 38        | 29.46%  |
| 1.01-2.0   | 34        | 26.36%  |
| 4.01-8.0   | 24        | 18.6%   |
| 3.01-4.0   | 17        | 13.18%  |
| 8.01-16.0  | 10        | 7.75%   |
| 0.51-1.0   | 3         | 2.33%   |
| 24.01-32.0 | 1         | 0.78%   |
| 16.01-24.0 | 1         | 0.78%   |
| 0.01-0.5   | 1         | 0.78%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 71        | 56.35%  |
| 2      | 32        | 25.4%   |
| 3      | 13        | 10.32%  |
| 4      | 5         | 3.97%   |
| 5      | 2         | 1.59%   |
| 0      | 2         | 1.59%   |
| 7      | 1         | 0.79%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 83        | 66.94%  |
| Yes       | 41        | 33.06%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 102       | 82.26%  |
| No        | 22        | 17.74%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 102       | 81.6%   |
| No        | 23        | 18.4%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 87        | 70.16%  |
| No        | 37        | 29.84%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Computers | Percent |
|------------|-----------|---------|
| Luxembourg | 124       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Luxembourg        | 69        | 52.27%  |
| Strassen          | 9         | 6.82%   |
| Useldange         | 3         | 2.27%   |
| Schifflange       | 3         | 2.27%   |
| Schieren          | 3         | 2.27%   |
| Ehnen             | 3         | 2.27%   |
| Differdange       | 3         | 2.27%   |
| Wormeldange       | 2         | 1.52%   |
| Steinfort         | 2         | 1.52%   |
| Sanem             | 2         | 1.52%   |
| Esch-sur-Alzette  | 2         | 1.52%   |
| Bettange-sur-Mess | 2         | 1.52%   |
| Wiltz             | 1         | 0.76%   |
| Wecker            | 1         | 0.76%   |
| Wasserbillig      | 1         | 0.76%   |
| Vianden           | 1         | 0.76%   |
| Steinsel          | 1         | 0.76%   |
| Soleuvre          | 1         | 0.76%   |
| Roeser            | 1         | 0.76%   |
| Pontpierre        | 1         | 0.76%   |
| Pétange          | 1         | 0.76%   |
| PerlГ©          | 1         | 0.76%   |
| Oberpallen        | 1         | 0.76%   |
| Obercorn          | 1         | 0.76%   |
| Niederanven       | 1         | 0.76%   |
| Leudelange        | 1         | 0.76%   |
| Kopstal           | 1         | 0.76%   |
| Junglinster       | 1         | 0.76%   |
| Itzig             | 1         | 0.76%   |
| Hunsdorf          | 1         | 0.76%   |
| Hosingen          | 1         | 0.76%   |
| Hesperange        | 1         | 0.76%   |
| Ettelbruck        | 1         | 0.76%   |
| Echternach        | 1         | 0.76%   |
| Dudelange         | 1         | 0.76%   |
| Diekirch          | 1         | 0.76%   |
| Bourscheid        | 1         | 0.76%   |
| Bettembourg       | 1         | 0.76%   |
| Belvaux           | 1         | 0.76%   |
| Beckerich         | 1         | 0.76%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 46        | 62     | 25.99%  |
| Seagate                   | 24        | 32     | 13.56%  |
| WDC                       | 20        | 31     | 11.3%   |
| Toshiba                   | 12        | 15     | 6.78%   |
| SanDisk                   | 11        | 15     | 6.21%   |
| Crucial                   | 11        | 16     | 6.21%   |
| Kingston                  | 9         | 12     | 5.08%   |
| Apple                     | 5         | 6      | 2.82%   |
| SK hynix                  | 4         | 4      | 2.26%   |
| Intel                     | 3         | 4      | 1.69%   |
| Hitachi                   | 3         | 4      | 1.69%   |
| Transcend                 | 2         | 2      | 1.13%   |
| LITEONIT                  | 2         | 2      | 1.13%   |
| LITEON                    | 2         | 2      | 1.13%   |
| Intenso                   | 2         | 3      | 1.13%   |
| HGST                      | 2         | 3      | 1.13%   |
| A-DATA Technology         | 2         | 2      | 1.13%   |
| Unknown                   | 1         | 2      | 0.56%   |
| Union Memory (Shenzhen)   | 1         | 1      | 0.56%   |
| TCSUNBOW                  | 1         | 1      | 0.56%   |
| SABRENT                   | 1         | 1      | 0.56%   |
| Phison                    | 1         | 1      | 0.56%   |
| PHD 3.0                   | 1         | 1      | 0.56%   |
| OCZ                       | 1         | 1      | 0.56%   |
| Micron/Crucial Technology | 1         | 1      | 0.56%   |
| Micron Technology         | 1         | 2      | 0.56%   |
| Maxtor                    | 1         | 2      | 0.56%   |
| LaCie                     | 1         | 1      | 0.56%   |
| KingSpec                  | 1         | 1      | 0.56%   |
| KingDian                  | 1         | 1      | 0.56%   |
| Inateck                   | 1         | 1      | 0.56%   |
| HUAWEI                    | 1         | 1      | 0.56%   |
| Gigabyte Technology       | 1         | 1      | 0.56%   |
| FORESEE                   | 1         | 1      | 0.56%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Seagate Expansion 4TB                  | 4         | 1.98%   |
| Samsung SSD 840 EVO 250GB              | 3         | 1.49%   |
| Kingston SA400S37240G 240GB SSD        | 3         | 1.49%   |
| WDC WD10JPVX-22JC3T0 1TB               | 2         | 0.99%   |
| WDC WD10EZEX-08WN4A0 1TB               | 2         | 0.99%   |
| Toshiba MQ01ABF050 500GB               | 2         | 0.99%   |
| Seagate ST1000LM035-1RK172 970GB       | 2         | 0.99%   |
| SanDisk SD8SN8U128G1122 128GB SSD      | 2         | 0.99%   |
| SanDisk NVMe SSD Drive 1TB             | 2         | 0.99%   |
| Samsung SSD 860 QVO 1TB                | 2         | 0.99%   |
| Samsung SSD 860 EVO 250GB              | 2         | 0.99%   |
| Samsung SSD 850 EVO 250GB              | 2         | 0.99%   |
| Samsung SP2504C 250GB                  | 2         | 0.99%   |
| Samsung MZVLW256HEHP-000L7 256GB       | 2         | 0.99%   |
| LITEONIT LMT-256L9M-11 MSATA 256GB SSD | 2         | 0.99%   |
| Crucial CT240BX500SSD1 240GB           | 2         | 0.99%   |
| Crucial CT1000P2SSD8 1TB               | 2         | 0.99%   |
| WDC WDS500G3X0C-00SJG0 500GB           | 1         | 0.5%    |
| WDC WDS250G2B0B-00YS70 250GB SSD       | 1         | 0.5%    |
| WDC WD5000AAVS-00ZTB0 500GB            | 1         | 0.5%    |
| WDC WD5000AAKS-60Z1A0 500GB            | 1         | 0.5%    |
| WDC WD40EZRZ-75GXCB0 4TB               | 1         | 0.5%    |
| WDC WD4000FYYZ-01UL1B2 4TB             | 1         | 0.5%    |
| WDC WD3200LPCX-00VHAT0 320GB           | 1         | 0.5%    |
| WDC WD3001FFSX-68JNUN0 3TB             | 1         | 0.5%    |
| WDC WD3000GLFS-01F8U0 304GB            | 1         | 0.5%    |
| WDC WD20EFAX-68FB5N0 2TB               | 1         | 0.5%    |
| WDC WD141KRYZ-01C66B0 14TB             | 1         | 0.5%    |
| WDC WD10SPZX-17Z10T0 1TB               | 1         | 0.5%    |
| WDC WD10SPCX-60HWST0 1TB               | 1         | 0.5%    |
| WDC WD10EZRX-00A8LB0 1TB               | 1         | 0.5%    |
| WDC WD10EZEX-60ZF5A0 1TB               | 1         | 0.5%    |
| WDC WD10EARX-00N0YB0 1TB               | 1         | 0.5%    |
| WDC WD10EARS-00Y5B1 1TB                | 1         | 0.5%    |
| WDC WD10EACS-00D6B1 1TB                | 1         | 0.5%    |
| WDC WD1001FALS-00J7B0 1TB              | 1         | 0.5%    |
| WDC PC SN730 SDBQNTY-512G-1001 512GB   | 1         | 0.5%    |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB     | 1         | 0.5%    |
| WDC PC SN730 SDBPNTY-512G-1027 512GB   | 1         | 0.5%    |
| Unknown MMC Card  64GB                 | 1         | 0.5%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 22        | 30     | 37.93%  |
| WDC                 | 15        | 26     | 25.86%  |
| Toshiba             | 8         | 11     | 13.79%  |
| Samsung Electronics | 3         | 3      | 5.17%   |
| Hitachi             | 3         | 4      | 5.17%   |
| HGST                | 2         | 3      | 3.45%   |
| Apple               | 2         | 2      | 3.45%   |
| PHD 3.0             | 1         | 1      | 1.72%   |
| Intenso             | 1         | 1      | 1.72%   |
| Inateck             | 1         | 1      | 1.72%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 27        | 35     | 40.3%   |
| SanDisk             | 9         | 11     | 13.43%  |
| Crucial             | 8         | 13     | 11.94%  |
| Kingston            | 5         | 8      | 7.46%   |
| Transcend           | 2         | 2      | 2.99%   |
| LITEONIT            | 2         | 2      | 2.99%   |
| LITEON              | 2         | 2      | 2.99%   |
| WDC                 | 1         | 1      | 1.49%   |
| TCSUNBOW            | 1         | 1      | 1.49%   |
| SK hynix            | 1         | 1      | 1.49%   |
| OCZ                 | 1         | 1      | 1.49%   |
| Micron Technology   | 1         | 2      | 1.49%   |
| Maxtor              | 1         | 2      | 1.49%   |
| KingSpec            | 1         | 1      | 1.49%   |
| KingDian            | 1         | 1      | 1.49%   |
| Intenso             | 1         | 2      | 1.49%   |
| FORESEE             | 1         | 1      | 1.49%   |
| Apple               | 1         | 1      | 1.49%   |
| A-DATA Technology   | 1         | 1      | 1.49%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 56        | 88     | 34.15%  |
| HDD     | 52        | 82     | 31.71%  |
| NVMe    | 51        | 59     | 31.1%   |
| Unknown | 3         | 3      | 1.83%   |
| MMC     | 2         | 3      | 1.22%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 86        | 160    | 57.33%  |
| NVMe | 51        | 58     | 34%     |
| SAS  | 11        | 14     | 7.33%   |
| MMC  | 2         | 3      | 1.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 64        | 98     | 52.89%  |
| 0.51-1.0   | 38        | 51     | 31.4%   |
| 3.01-4.0   | 9         | 9      | 7.44%   |
| 1.01-2.0   | 5         | 6      | 4.13%   |
| 2.01-3.0   | 2         | 3      | 1.65%   |
| 10.01-20.0 | 2         | 2      | 1.65%   |
| 4.01-10.0  | 1         | 1      | 0.83%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 32        | 25.2%   |
| 251-500        | 31        | 24.41%  |
| 501-1000       | 17        | 13.39%  |
| 1001-2000      | 10        | 7.87%   |
| Unknown        | 10        | 7.87%   |
| More than 3000 | 9         | 7.09%   |
| 2001-3000      | 6         | 4.72%   |
| 1-20           | 5         | 3.94%   |
| 51-100         | 5         | 3.94%   |
| 21-50          | 2         | 1.57%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 43        | 33.59%  |
| 21-50          | 19        | 14.84%  |
| 101-250        | 19        | 14.84%  |
| 251-500        | 11        | 8.59%   |
| 51-100         | 11        | 8.59%   |
| Unknown        | 10        | 7.81%   |
| 501-1000       | 8         | 6.25%   |
| 2001-3000      | 3         | 2.34%   |
| More than 3000 | 2         | 1.56%   |
| 1001-2000      | 2         | 1.56%   |

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
| Detected | 65        | 129    | 49.24%  |
| Works    | 61        | 99     | 46.21%  |
| Malfunc  | 6         | 7      | 4.55%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 85        | 53.13%  |
| Samsung Electronics          | 22        | 13.75%  |
| AMD                          | 20        | 12.5%   |
| SanDisk                      | 8         | 5%      |
| Toshiba America Info Systems | 4         | 2.5%    |
| Micron/Crucial Technology    | 4         | 2.5%    |
| Kingston Technology Company  | 4         | 2.5%    |
| Marvell Technology Group     | 3         | 1.88%   |
| SK hynix                     | 2         | 1.25%   |
| Phison Electronics           | 2         | 1.25%   |
| Apple                        | 2         | 1.25%   |
| Union Memory (Shenzhen)      | 1         | 0.63%   |
| Seagate Technology           | 1         | 0.63%   |
| ASMedia Technology           | 1         | 0.63%   |
| ADATA Technology             | 1         | 0.63%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 17        | 9.77%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 13        | 7.47%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 9         | 5.17%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 8         | 4.6%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 6         | 3.45%   |
| Intel Volume Management Device NVMe RAID Controller                            | 6         | 3.45%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 6         | 3.45%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 5         | 2.87%   |
| Samsung NVMe SSD Controller 980                                                | 4         | 2.3%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 2.3%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 4         | 2.3%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 2.3%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 2.3%    |
| AMD 400 Series Chipset SATA Controller                                         | 4         | 2.3%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 1.72%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 3         | 1.72%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 1.72%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 3         | 1.72%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 1.72%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 3         | 1.72%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 1.15%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 2         | 1.15%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2         | 1.15%   |
| Phison E12 NVMe Controller                                                     | 2         | 1.15%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                      | 2         | 1.15%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 1.15%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 1.15%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 1.15%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 2         | 1.15%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 2         | 1.15%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 1         | 0.57%   |
| SK hynix Platinum P41 NVMe Solid State Drive 2TB                               | 1         | 0.57%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 1         | 0.57%   |
| Seagate FireCuda 520 SSD                                                       | 1         | 0.57%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1         | 0.57%   |
| Samsung Surface NVMe Controller                                                | 1         | 0.57%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 1         | 0.57%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                     | 1         | 0.57%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 1         | 0.57%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 1         | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 91        | 56.88%  |
| NVMe | 52        | 32.5%   |
| RAID | 10        | 6.25%   |
| IDE  | 7         | 4.38%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 99        | 79.84%  |
| AMD    | 25        | 20.16%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz           | 4         | 3.23%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 3         | 2.42%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 3         | 2.42%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 3         | 2.42%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 2         | 1.61%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 2         | 1.61%   |
| Intel Core i7-4702HQ CPU @ 2.20GHz          | 2         | 1.61%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 2         | 1.61%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 2         | 1.61%   |
| Intel Core i3-4030U CPU @ 1.90GHz           | 2         | 1.61%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 2         | 1.61%   |
| AMD Ryzen 9 5900HX with Radeon Graphics     | 2         | 1.61%   |
| AMD Ryzen 5 4600H with Radeon Graphics      | 2         | 1.61%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2         | 1.61%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 0.81%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1         | 0.81%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 0.81%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz | 1         | 0.81%   |
| Intel Pentium CPU P6000 @ 1.87GHz           | 1         | 0.81%   |
| Intel Pentium CPU G4560 @ 3.50GHz           | 1         | 0.81%   |
| Intel Pentium CPU G3250 @ 3.20GHz           | 1         | 0.81%   |
| Intel Pentium CPU 987 @ 1.50GHz             | 1         | 0.81%   |
| Intel Core m5-6Y54 CPU @ 1.10GHz            | 1         | 0.81%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz            | 1         | 0.81%   |
| Intel Core i9-9880H CPU @ 2.30GHz           | 1         | 0.81%   |
| Intel Core i7-9700KF CPU @ 3.60GHz          | 1         | 0.81%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1         | 0.81%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 1         | 0.81%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 0.81%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1         | 0.81%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 0.81%   |
| Intel Core i7-6800K CPU @ 3.40GHz           | 1         | 0.81%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 0.81%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 1         | 0.81%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz          | 1         | 0.81%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1         | 0.81%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 1         | 0.81%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1         | 0.81%   |
| Intel Core i7-4712MQ CPU @ 2.30GHz          | 1         | 0.81%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz          | 1         | 0.81%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 33        | 26.61%  |
| Intel Core i5           | 27        | 21.77%  |
| Other                   | 9         | 7.26%   |
| Intel Core i3           | 9         | 7.26%   |
| AMD Ryzen 5             | 8         | 6.45%   |
| AMD Ryzen 9             | 5         | 4.03%   |
| AMD Ryzen 7             | 5         | 4.03%   |
| Intel Pentium           | 4         | 3.23%   |
| Intel Celeron           | 4         | 3.23%   |
| Intel Pentium Dual-Core | 3         | 2.42%   |
| Intel Core 2 Quad       | 3         | 2.42%   |
| AMD Ryzen 7 PRO         | 2         | 1.61%   |
| Intel Pentium Silver    | 1         | 0.81%   |
| Intel Core m5           | 1         | 0.81%   |
| Intel Core m3           | 1         | 0.81%   |
| Intel Core i9           | 1         | 0.81%   |
| Intel Core 2 Duo        | 1         | 0.81%   |
| Intel Core 2            | 1         | 0.81%   |
| Intel Atom              | 1         | 0.81%   |
| AMD Ryzen 5 PRO         | 1         | 0.81%   |
| AMD Phenom II X4        | 1         | 0.81%   |
| AMD FX                  | 1         | 0.81%   |
| AMD E2                  | 1         | 0.81%   |
| AMD Athlon II X4        | 1         | 0.81%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 47        | 37.9%   |
| 2       | 40        | 32.26%  |
| 6       | 15        | 12.1%   |
| 8       | 14        | 11.29%  |
| 12      | 3         | 2.42%   |
| 1       | 2         | 1.61%   |
| 16      | 1         | 0.81%   |
| 14      | 1         | 0.81%   |
| Unknown | 1         | 0.81%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 124       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 95        | 76.61%  |
| 1       | 28        | 22.58%  |
| Unknown | 1         | 0.81%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 123       | 99.19%  |
| 32-bit         | 1         | 0.81%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 28        | 21.88%  |
| 0x306c3    | 13        | 10.16%  |
| 0x806ea    | 5         | 3.91%   |
| 0x40651    | 5         | 3.91%   |
| 0x206a7    | 5         | 3.91%   |
| 0x906e9    | 4         | 3.13%   |
| 0x406e3    | 4         | 3.13%   |
| 0x1067a    | 4         | 3.13%   |
| 0x906ea    | 3         | 2.34%   |
| 0x806eb    | 3         | 2.34%   |
| 0x806c1    | 3         | 2.34%   |
| 0x506e3    | 3         | 2.34%   |
| 0x306d4    | 3         | 2.34%   |
| 0x20655    | 3         | 2.34%   |
| 0xa0655    | 2         | 1.56%   |
| 0x906ed    | 2         | 1.56%   |
| 0x806ec    | 2         | 1.56%   |
| 0x706a1    | 2         | 1.56%   |
| 0x306a9    | 2         | 1.56%   |
| 0x10677    | 2         | 1.56%   |
| 0x0a50000c | 2         | 1.56%   |
| 0x0a20120a | 2         | 1.56%   |
| 0x08701021 | 2         | 1.56%   |
| 0x08701013 | 2         | 1.56%   |
| 0x08600106 | 2         | 1.56%   |
| 0x08600103 | 2         | 1.56%   |
| 0xa0671    | 1         | 0.78%   |
| 0x906c0    | 1         | 0.78%   |
| 0x806e9    | 1         | 0.78%   |
| 0x806d1    | 1         | 0.78%   |
| 0x6fb      | 1         | 0.78%   |
| 0x6f6      | 1         | 0.78%   |
| 0x406f1    | 1         | 0.78%   |
| 0x20652    | 1         | 0.78%   |
| 0x106c2    | 1         | 0.78%   |
| 0x0a601203 | 1         | 0.78%   |
| 0x0a201009 | 1         | 0.78%   |
| 0x08600104 | 1         | 0.78%   |
| 0x08108102 | 1         | 0.78%   |
| 0x0810100b | 1         | 0.78%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 28        | 22.58%  |
| Haswell          | 20        | 16.13%  |
| Zen 2            | 11        | 8.87%   |
| Skylake          | 10        | 8.06%   |
| Zen 3            | 6         | 4.84%   |
| Penryn           | 6         | 4.84%   |
| TigerLake        | 5         | 4.03%   |
| SandyBridge      | 5         | 4.03%   |
| Westmere         | 4         | 3.23%   |
| Broadwell        | 4         | 3.23%   |
| IvyBridge        | 3         | 2.42%   |
| CometLake        | 3         | 2.42%   |
| Unknown          | 3         | 2.42%   |
| Zen+             | 2         | 1.61%   |
| K10              | 2         | 1.61%   |
| Icelake          | 2         | 1.61%   |
| Goldmont plus    | 2         | 1.61%   |
| Core             | 2         | 1.61%   |
| Zen              | 1         | 0.81%   |
| Piledriver       | 1         | 0.81%   |
| Goldmont         | 1         | 0.81%   |
| Excavator        | 1         | 0.81%   |
| Bonnell          | 1         | 0.81%   |
| Alderlake Hybrid | 1         | 0.81%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 80        | 52.98%  |
| Nvidia | 46        | 30.46%  |
| AMD    | 25        | 16.56%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 8         | 5.19%   |
| Intel UHD Graphics 620                                                      | 7         | 4.55%   |
| AMD Renoir                                                                  | 7         | 4.55%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 6         | 3.9%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 5         | 3.25%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 5         | 3.25%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 5         | 3.25%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 4         | 2.6%    |
| Intel HD Graphics 530                                                       | 4         | 2.6%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4         | 2.6%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 3         | 1.95%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 3         | 1.95%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 3         | 1.95%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 2         | 1.3%    |
| Nvidia GP108M [GeForce MX250]                                               | 2         | 1.3%    |
| Nvidia GP108M [GeForce MX150]                                               | 2         | 1.3%    |
| Nvidia GP108 [GeForce GT 1030]                                              | 2         | 1.3%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 2         | 1.3%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2         | 1.3%    |
| Nvidia GK107GLM [Quadro K1100M]                                             | 2         | 1.3%    |
| Nvidia GA107GLM [RTX A1000 Laptop GPU]                                      | 2         | 1.3%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 1.3%    |
| Intel Iris Plus Graphics 640                                                | 2         | 1.3%    |
| Intel HD Graphics 5500                                                      | 2         | 1.3%    |
| Intel HD Graphics 515                                                       | 2         | 1.3%    |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 2         | 1.3%    |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                               | 1         | 0.65%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                       | 1         | 0.65%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1         | 0.65%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1         | 0.65%   |
| Nvidia GT218 [NVS 300]                                                      | 1         | 0.65%   |
| Nvidia GT218 [GeForce G210]                                                 | 1         | 0.65%   |
| Nvidia GT216M [GeForce GT 330M]                                             | 1         | 0.65%   |
| Nvidia GT215M [GeForce GTS 250M]                                            | 1         | 0.65%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1         | 0.65%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1         | 0.65%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 1         | 0.65%   |
| Nvidia GM108M [GeForce 840M]                                                | 1         | 0.65%   |
| Nvidia GM107M [GeForce GTX 950M]                                            | 1         | 0.65%   |
| Nvidia GM107M [GeForce GTX 850M]                                            | 1         | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 52        | 41.94%  |
| Intel + Nvidia | 24        | 19.35%  |
| 1 x Nvidia     | 23        | 18.55%  |
| 1 x AMD        | 19        | 15.32%  |
| 2 x AMD        | 3         | 2.42%   |
| Intel + AMD    | 3         | 2.42%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 94        | 75.2%   |
| Proprietary | 26        | 20.8%   |
| Unknown     | 5         | 4%      |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 77        | 61.6%   |
| 3.01-4.0   | 12        | 9.6%    |
| 1.01-2.0   | 11        | 8.8%    |
| 0.01-0.5   | 11        | 8.8%    |
| 0.51-1.0   | 8         | 6.4%    |
| 8.01-16.0  | 4         | 3.2%    |
| 5.01-6.0   | 2         | 1.6%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 21        | 14.89%  |
| Chimei Innolux          | 18        | 12.77%  |
| LG Display              | 15        | 10.64%  |
| AU Optronics            | 10        | 7.09%   |
| Dell                    | 7         | 4.96%   |
| AOC                     | 7         | 4.96%   |
| Sharp                   | 6         | 4.26%   |
| Iiyama                  | 6         | 4.26%   |
| Hewlett-Packard         | 6         | 4.26%   |
| Goldstar                | 6         | 4.26%   |
| BOE                     | 5         | 3.55%   |
| Apple                   | 5         | 3.55%   |
| Philips                 | 4         | 2.84%   |
| BenQ                    | 4         | 2.84%   |
| Medion                  | 3         | 2.13%   |
| Chi Mei Optoelectronics | 3         | 2.13%   |
| Ancor Communications    | 2         | 1.42%   |
| Videoseven              | 1         | 0.71%   |
| Sony                    | 1         | 0.71%   |
| PAR                     | 1         | 0.71%   |
| PANDA                   | 1         | 0.71%   |
| Panasonic               | 1         | 0.71%   |
| MSI                     | 1         | 0.71%   |
| Lenovo                  | 1         | 0.71%   |
| Fujitsu Siemens         | 1         | 0.71%   |
| Eizo                    | 1         | 0.71%   |
| CSO                     | 1         | 0.71%   |
| Belinea                 | 1         | 0.71%   |
| Aosiman                 | 1         | 0.71%   |
| Acer                    | 1         | 0.71%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 2         | 1.4%    |
| Sharp LCD Monitor SHP13F8 3200x1800 346x194mm 15.6-inch               | 2         | 1.4%    |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 381x214mm 17.2-inch      | 2         | 1.4%    |
| Chimei Innolux LCD Monitor CMN1604 1920x1080 355x199mm 16.0-inch      | 2         | 1.4%    |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 2         | 1.4%    |
| AOC 2250W AOC2250 1920x1080 477x268mm 21.5-inch                       | 2         | 1.4%    |
| Videoseven L27ADS IGM2700 1920x1080 598x336mm 27.0-inch               | 1         | 0.7%    |
| Sony NvidiaDefault SNY05FA 1366x768 290x170mm 13.2-inch               | 1         | 0.7%    |
| Sharp LCD Monitor SHP1516 3840x2400 336x210mm 15.6-inch               | 1         | 0.7%    |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch               | 1         | 0.7%    |
| Samsung Electronics T24B350 SAM093E 1920x1080 531x299mm 24.0-inch     | 1         | 0.7%    |
| Samsung Electronics SyncMaster SAM0612 1920x1080 604x342mm 27.3-inch  | 1         | 0.7%    |
| Samsung Electronics SyncMaster SAM04DF 1360x768 410x230mm 18.5-inch   | 1         | 0.7%    |
| Samsung Electronics SMT27A950 SAM080F 1920x1080 598x336mm 27.0-inch   | 1         | 0.7%    |
| Samsung Electronics SM2333T SAM0737 1920x1080 510x290mm 23.1-inch     | 1         | 0.7%    |
| Samsung Electronics S27D390 SAM0B67 1920x1080 598x336mm 27.0-inch     | 1         | 0.7%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 0.7%    |
| Samsung Electronics LCD Monitor U28E590 3840x2160                     | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SEC444E 1600x900 310x174mm 14.0-inch  | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SDCA029 2560x1440 294x165mm 13.3-inch | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SDC5844 1920x1080 344x194mm 15.5-inch | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch  | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch  | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SDC4159 1920x1080 344x194mm 15.5-inch | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SDC4141 3840x2160 344x194mm 15.5-inch | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SAM0B60 1920x1080 887x500mm 40.1-inch | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 890x500mm 40.2-inch | 1         | 0.7%    |
| Samsung Electronics C27R500 SAM0F9D 1920x1080 598x336mm 27.0-inch     | 1         | 0.7%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 1         | 0.7%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1         | 0.7%    |
| Philips PHL BDM3270 PHL08E7 2560x1440 708x398mm 32.0-inch             | 1         | 0.7%    |
| Philips PHL 346B1C PHL095C 3440x1440 797x334mm 34.0-inch              | 1         | 0.7%    |
| Philips PHL 275C5 PHLC0E4 1920x1080 598x336mm 27.0-inch               | 1         | 0.7%    |
| Philips PHL 246V5 PHLC0C5 1920x1080 531x299mm 24.0-inch               | 1         | 0.7%    |
| PAR LED1920X1080 PAR9C63 1920x1080 710x400mm 32.1-inch                | 1         | 0.7%    |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 1         | 0.7%    |
| Panasonic VVY13F001G10 MEI96A2 1920x1080 344x193mm 15.5-inch          | 1         | 0.7%    |
| MSI MPG27CQ MSI3FA3 2560x1440 600x340mm 27.2-inch                     | 1         | 0.7%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 66        | 50.77%  |
| 1366x768 (WXGA)    | 15        | 11.54%  |
| 3840x2160 (4K)     | 12        | 9.23%   |
| 2560x1440 (QHD)    | 7         | 5.38%   |
| 1600x900 (HD+)     | 4         | 3.08%   |
| 2880x1800          | 3         | 2.31%   |
| 1920x1200 (WUXGA)  | 3         | 2.31%   |
| 1680x1050 (WSXGA+) | 3         | 2.31%   |
| 3200x1800 (QHD+)   | 2         | 1.54%   |
| 1440x900 (WXGA+)   | 2         | 1.54%   |
| 1360x768           | 2         | 1.54%   |
| 1280x1024 (SXGA)   | 2         | 1.54%   |
| 3840x2400          | 1         | 0.77%   |
| 3840x1080          | 1         | 0.77%   |
| 3440x1440          | 1         | 0.77%   |
| 3072x1920          | 1         | 0.77%   |
| 2560x1600          | 1         | 0.77%   |
| 2520x1680          | 1         | 0.77%   |
| 1280x800 (WXGA)    | 1         | 0.77%   |
| 1024x768 (XGA)     | 1         | 0.77%   |
| Unknown            | 1         | 0.77%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 34        | 23.94%  |
| 27      | 18        | 12.68%  |
| 14      | 13        | 9.15%   |
| 13      | 12        | 8.45%   |
| 17      | 11        | 7.75%   |
| 24      | 9         | 6.34%   |
| 23      | 8         | 5.63%   |
| 21      | 8         | 5.63%   |
| 16      | 5         | 3.52%   |
| Unknown | 5         | 3.52%   |
| 22      | 3         | 2.11%   |
| 72      | 2         | 1.41%   |
| 40      | 2         | 1.41%   |
| 32      | 2         | 1.41%   |
| 18      | 2         | 1.41%   |
| 59      | 1         | 0.7%    |
| 46      | 1         | 0.7%    |
| 34      | 1         | 0.7%    |
| 33      | 1         | 0.7%    |
| 31      | 1         | 0.7%    |
| 25      | 1         | 0.7%    |
| 19      | 1         | 0.7%    |
| 11      | 1         | 0.7%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 55        | 39.86%  |
| 501-600     | 32        | 23.19%  |
| 401-500     | 13        | 9.42%   |
| 351-400     | 13        | 9.42%   |
| 201-300     | 8         | 5.8%    |
| Unknown     | 5         | 3.62%   |
| 701-800     | 4         | 2.9%    |
| 801-900     | 2         | 1.45%   |
| 601-700     | 2         | 1.45%   |
| 1501-2000   | 2         | 1.45%   |
| 1001-1500   | 2         | 1.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 98        | 80.33%  |
| 16/10   | 16        | 13.11%  |
| Unknown | 3         | 2.46%   |
| 5/4     | 2         | 1.64%   |
| 4/3     | 1         | 0.82%   |
| 3/2     | 1         | 0.82%   |
| 21/9    | 1         | 0.82%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 34        | 24.11%  |
| 201-250        | 25        | 17.73%  |
| 81-90          | 19        | 13.48%  |
| 301-350        | 18        | 12.77%  |
| 121-130        | 8         | 5.67%   |
| 71-80          | 6         | 4.26%   |
| 351-500        | 5         | 3.55%   |
| Unknown        | 5         | 3.55%   |
| 111-120        | 4         | 2.84%   |
| More than 1000 | 3         | 2.13%   |
| 251-300        | 3         | 2.13%   |
| 141-150        | 3         | 2.13%   |
| 501-1000       | 3         | 2.13%   |
| 131-140        | 2         | 1.42%   |
| 51-60          | 1         | 0.71%   |
| 151-200        | 1         | 0.71%   |
| 91-100         | 1         | 0.71%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 41        | 30.15%  |
| 121-160       | 38        | 27.94%  |
| 101-120       | 30        | 22.06%  |
| 161-240       | 12        | 8.82%   |
| More than 240 | 8         | 5.88%   |
| Unknown       | 5         | 3.68%   |
| 1-50          | 2         | 1.47%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 96        | 76.19%  |
| 2     | 23        | 18.25%  |
| 0     | 5         | 3.97%   |
| 3     | 2         | 1.59%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 86        | 46.24%  |
| Realtek Semiconductor           | 50        | 26.88%  |
| Qualcomm Atheros                | 17        | 9.14%   |
| Broadcom                        | 13        | 6.99%   |
| Marvell Technology Group        | 4         | 2.15%   |
| Sierra Wireless                 | 2         | 1.08%   |
| MediaTek                        | 2         | 1.08%   |
| DisplayLink                     | 2         | 1.08%   |
| TP-Link                         | 1         | 0.54%   |
| Shenzhen Goodix Technology      | 1         | 0.54%   |
| Ralink Technology               | 1         | 0.54%   |
| Qualcomm Atheros Communications | 1         | 0.54%   |
| Lenovo                          | 1         | 0.54%   |
| JMicron Technology              | 1         | 0.54%   |
| Huawei Technologies             | 1         | 0.54%   |
| Broadcom Limited                | 1         | 0.54%   |
| ASIX Electronics                | 1         | 0.54%   |
| Unknown                         | 1         | 0.54%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 35        | 15.84%  |
| Intel Wi-Fi 6 AX200                                                            | 14        | 6.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 6         | 2.71%   |
| Realtek RTL8125 2.5GbE Controller                                              | 6         | 2.71%   |
| Intel I211 Gigabit Network Connection                                          | 6         | 2.71%   |
| Intel Wireless 8265 / 8275                                                     | 5         | 2.26%   |
| Intel Wireless 8260                                                            | 5         | 2.26%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 5         | 2.26%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 4         | 1.81%   |
| Intel Wireless 7260                                                            | 4         | 1.81%   |
| Intel Ethernet Connection (2) I219-V                                           | 4         | 1.81%   |
| Intel Wireless 3160                                                            | 3         | 1.36%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                         | 3         | 1.36%   |
| Intel Ethernet Connection I219-V                                               | 3         | 1.36%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 3         | 1.36%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 3         | 1.36%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 2         | 0.9%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 2         | 0.9%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 2         | 0.9%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 2         | 0.9%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 2         | 0.9%    |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.9%    |
| Intel Wireless-AC 9260                                                         | 2         | 0.9%    |
| Intel Wireless 7265                                                            | 2         | 0.9%    |
| Intel Wireless 3165                                                            | 2         | 0.9%    |
| Intel Wi-Fi 6 AX201                                                            | 2         | 0.9%    |
| Intel Ethernet Controller I225-V                                               | 2         | 0.9%    |
| Intel Ethernet Connection I217-V                                               | 2         | 0.9%    |
| Intel Ethernet Connection I217-LM                                              | 2         | 0.9%    |
| Intel Ethernet Connection (6) I219-V                                           | 2         | 0.9%    |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 0.9%    |
| Intel Ethernet Connection (2) I218-V                                           | 2         | 0.9%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 2         | 0.9%    |
| DisplayLink Dell D3100 Docking Station                                         | 2         | 0.9%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                             | 2         | 0.9%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 2         | 0.9%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                    | 1         | 0.45%   |
| Sierra Wireless EM7455                                                         | 1         | 0.45%   |
| Sierra Wireless EM7305 Modem                                                   | 1         | 0.45%   |
| Shenzhen Goodix Unknow device                                                  | 1         | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 65        | 61.32%  |
| Qualcomm Atheros                | 14        | 13.21%  |
| Broadcom                        | 10        | 9.43%   |
| Realtek Semiconductor           | 8         | 7.55%   |
| Sierra Wireless                 | 2         | 1.89%   |
| MediaTek                        | 2         | 1.89%   |
| TP-Link                         | 1         | 0.94%   |
| Ralink Technology               | 1         | 0.94%   |
| Qualcomm Atheros Communications | 1         | 0.94%   |
| Marvell Technology Group        | 1         | 0.94%   |
| Broadcom Limited                | 1         | 0.94%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 14        | 13.08%  |
| Intel Wireless 8265 / 8275                                     | 5         | 4.67%   |
| Intel Wireless 8260                                            | 5         | 4.67%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 5         | 4.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 4         | 3.74%   |
| Intel Wireless 7260                                            | 4         | 3.74%   |
| Intel Wireless 3160                                            | 3         | 2.8%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 3         | 2.8%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 2.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.87%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2         | 1.87%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 1.87%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 1.87%   |
| Intel Wireless-AC 9260                                         | 2         | 1.87%   |
| Intel Wireless 7265                                            | 2         | 1.87%   |
| Intel Wireless 3165                                            | 2         | 1.87%   |
| Intel Wi-Fi 6 AX201                                            | 2         | 1.87%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 1.87%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 2         | 1.87%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 1.87%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1         | 0.93%   |
| Sierra Wireless EM7455                                         | 1         | 0.93%   |
| Sierra Wireless EM7305 Modem                                   | 1         | 0.93%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.93%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 0.93%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 0.93%   |
| Realtek 802.11ac NIC                                           | 1         | 0.93%   |
| Ralink RT5370 Wireless Adapter                                 | 1         | 0.93%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 0.93%   |
| Qualcomm Atheros AR9271 802.11n                                | 1         | 0.93%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 0.93%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 0.93%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 1         | 0.93%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 0.93%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 0.93%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 1         | 0.93%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter            | 1         | 0.93%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless              | 1         | 0.93%   |
| Intel WiMAX/WiFi Link 5150                                     | 1         | 0.93%   |
| Intel WiMAX Connection 2400m                                   | 1         | 0.93%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 48        | 44.44%  |
| Intel                    | 42        | 38.89%  |
| Qualcomm Atheros         | 5         | 4.63%   |
| Broadcom                 | 5         | 4.63%   |
| Marvell Technology Group | 3         | 2.78%   |
| DisplayLink              | 2         | 1.85%   |
| Lenovo                   | 1         | 0.93%   |
| JMicron Technology       | 1         | 0.93%   |
| ASIX Electronics         | 1         | 0.93%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 35        | 31.82%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 6         | 5.45%   |
| Realtek RTL8125 2.5GbE Controller                                              | 6         | 5.45%   |
| Intel I211 Gigabit Network Connection                                          | 6         | 5.45%   |
| Intel Ethernet Connection (2) I219-V                                           | 4         | 3.64%   |
| Intel Ethernet Connection I219-V                                               | 3         | 2.73%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 3         | 2.73%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 2         | 1.82%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 1.82%   |
| Intel Ethernet Controller I225-V                                               | 2         | 1.82%   |
| Intel Ethernet Connection I217-V                                               | 2         | 1.82%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 1.82%   |
| Intel Ethernet Connection (6) I219-V                                           | 2         | 1.82%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 1.82%   |
| Intel Ethernet Connection (2) I218-V                                           | 2         | 1.82%   |
| DisplayLink Dell D3100 Docking Station                                         | 2         | 1.82%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.91%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.91%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.91%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.91%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 0.91%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.91%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 0.91%   |
| Lenovo ThinkPad Lan                                                            | 1         | 0.91%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 0.91%   |
| Intel Ethernet controller                                                      | 1         | 0.91%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.91%   |
| Intel Ethernet Connection (7) I219-V                                           | 1         | 0.91%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.91%   |
| Intel Ethernet Connection (6) I219-LM                                          | 1         | 0.91%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1         | 0.91%   |
| Intel Ethernet Connection (3) I218-V                                           | 1         | 0.91%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 0.91%   |
| Intel Ethernet Connection (17) I219-LM                                         | 1         | 0.91%   |
| Intel Ethernet Connection (11) I219-V                                          | 1         | 0.91%   |
| Intel 82577LC Gigabit Network Connection                                       | 1         | 0.91%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 1         | 0.91%   |
| Intel 82566DC-2 Gigabit Network Connection                                     | 1         | 0.91%   |
| Intel 82566DC Gigabit Network Connection                                       | 1         | 0.91%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 1         | 0.91%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 102       | 49.28%  |
| Ethernet | 101       | 48.79%  |
| Modem    | 2         | 0.97%   |
| Unknown  | 2         | 0.97%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 72        | 54.55%  |
| Ethernet | 60        | 45.45%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 69        | 55.65%  |
| 1     | 50        | 40.32%  |
| 3     | 5         | 4.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 98        | 78.4%   |
| Yes  | 27        | 21.6%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 57        | 64.77%  |
| Foxconn / Hon Hai               | 5         | 5.68%   |
| IMC Networks                    | 4         | 4.55%   |
| Cambridge Silicon Radio         | 4         | 4.55%   |
| Qualcomm Atheros Communications | 3         | 3.41%   |
| Apple                           | 3         | 3.41%   |
| Realtek                         | 2         | 2.27%   |
| Lite-On Technology              | 2         | 2.27%   |
| Hewlett-Packard                 | 2         | 2.27%   |
| Toshiba                         | 1         | 1.14%   |
| Realtek Semiconductor           | 1         | 1.14%   |
| Micro Star International        | 1         | 1.14%   |
| Marvell Semiconductor           | 1         | 1.14%   |
| Broadcom                        | 1         | 1.14%   |
| ASUSTek Computer                | 1         | 1.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 20        | 22.73%  |
| Intel AX200 Bluetooth                                                               | 13        | 14.77%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 8         | 9.09%   |
| Intel AX201 Bluetooth                                                               | 6         | 6.82%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 4         | 4.55%   |
| Intel AX210 Bluetooth                                                               | 3         | 3.41%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 2         | 2.27%   |
| Lite-On Bluetooth Device                                                            | 2         | 2.27%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 2.27%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 2.27%   |
| Intel Bluetooth Device                                                              | 2         | 2.27%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 2.27%   |
| Apple Bluetooth USB Host Controller                                                 | 2         | 2.27%   |
| Toshiba Bluetooth Device                                                            | 1         | 1.14%   |
| Realtek Bluetooth Radio                                                             | 1         | 1.14%   |
| Realtek Bluetooth Radio                                                             | 1         | 1.14%   |
| Realtek 802.11ac WLAN Adapter                                                       | 1         | 1.14%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 1.14%   |
| Micro Star International Motorola Bluetooth 2.1+EDR Device                          | 1         | 1.14%   |
| Marvell Bluetooth and Wireless LAN Composite                                        | 1         | 1.14%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 1.14%   |
| IMC Networks Wireless_Device                                                        | 1         | 1.14%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 1.14%   |
| IMC Networks Bluetooth Module                                                       | 1         | 1.14%   |
| IMC Networks Bluetooth Device                                                       | 1         | 1.14%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.14%   |
| Foxconn / Hon Hai BT                                                                | 1         | 1.14%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 1.14%   |
| Foxconn / Hon Hai BCM43142A0                                                        | 1         | 1.14%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 1.14%   |
| Broadcom Bluetooth 3.0 Device                                                       | 1         | 1.14%   |
| ASUS BCM20702A0                                                                     | 1         | 1.14%   |
| Apple Bluetooth Host Controller                                                     | 1         | 1.14%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 99        | 59.64%  |
| AMD                            | 29        | 17.47%  |
| Nvidia                         | 26        | 15.66%  |
| SteelSeries ApS                | 2         | 1.2%    |
| Logitech                       | 2         | 1.2%    |
| www.hirestech.com 2010 REV 1.4 | 1         | 0.6%    |
| Sony                           | 1         | 0.6%    |
| Realtek Semiconductor          | 1         | 0.6%    |
| Lenovo                         | 1         | 0.6%    |
| Hewlett-Packard                | 1         | 0.6%    |
| C-Media Electronics            | 1         | 0.6%    |
| Bose                           | 1         | 0.6%    |
| Apple                          | 1         | 0.6%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 15        | 7.39%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 13        | 6.4%    |
| AMD Family 17h/19h HD Audio Controller                                     | 13        | 6.4%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 11        | 5.42%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 10        | 4.93%   |
| AMD Starship/Matisse HD Audio Controller                                   | 7         | 3.45%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 6         | 2.96%   |
| Intel Cannon Lake PCH cAVS                                                 | 6         | 2.96%   |
| Intel 200 Series PCH HD Audio                                              | 6         | 2.96%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 5         | 2.46%   |
| Intel Haswell-ULT HD Audio Controller                                      | 5         | 2.46%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 2.46%   |
| Intel 8 Series HD Audio Controller                                         | 5         | 2.46%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 4         | 1.97%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 1.97%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 1.97%   |
| Nvidia High Definition Audio Controller                                    | 3         | 1.48%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 1.48%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 1.48%   |
| Intel Comet Lake PCH cAVS                                                  | 3         | 1.48%   |
| Intel Broadwell-U Audio Controller                                         | 3         | 1.48%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 1.48%   |
| Nvidia GP108 High Definition Audio Controller                              | 2         | 0.99%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 0.99%   |
| Nvidia GA106 High Definition Audio Controller                              | 2         | 0.99%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 0.99%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 2         | 0.99%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 2         | 0.99%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 0.99%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 2         | 0.99%   |
| www.hirestech.com 2010 REV 1.4 Music Streamer Pro                          | 1         | 0.49%   |
| SteelSeries ApS SteelSeries Arctis 7                                       | 1         | 0.49%   |
| SteelSeries ApS Arctis Nova 3                                              | 1         | 0.49%   |
| Sony DualShock 4 [CUH-ZCT2x]                                               | 1         | 0.49%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.49%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 0.49%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.49%   |
| Nvidia GT216 HDMI Audio Controller                                         | 1         | 0.49%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.49%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 0.49%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 28        | 35%     |
| SK hynix                     | 11        | 13.75%  |
| Micron Technology            | 6         | 7.5%    |
| Kingston                     | 6         | 7.5%    |
| Corsair                      | 6         | 7.5%    |
| Crucial                      | 5         | 6.25%   |
| Unknown                      | 4         | 5%      |
| G.Skill                      | 4         | 5%      |
| A-DATA Technology            | 4         | 5%      |
| Qimonda                      | 2         | 2.5%    |
| Wilk                         | 1         | 1.25%   |
| Unknown (0x7F7FB5FFFFFFFFFF) | 1         | 1.25%   |
| Timetec                      | 1         | 1.25%   |
| Dane-Elec                    | 1         | 1.25%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s        | 3         | 3.53%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s         | 2         | 2.35%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s         | 2         | 2.35%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s         | 2         | 2.35%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s        | 2         | 2.35%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s         | 2         | 2.35%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s       | 2         | 2.35%   |
| Wilk RAM GR3200S464L22S/16G 16GB SODIMM DDR4 3200MT/s         | 1         | 1.18%   |
| Unknown RAM Module 4GB SODIMM DDR3                            | 1         | 1.18%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                  | 1         | 1.18%   |
| Unknown RAM Module 2GB SODIMM DDR2                            | 1         | 1.18%   |
| Unknown RAM Module 2048MB SODIMM DDR2                         | 1         | 1.18%   |
| Unknown RAM Module 1024MB SODIMM DDR2                         | 1         | 1.18%   |
| Unknown (0x7F7FB5FFFFFFFFFF) RAM Module 1GB DIMM DDR2 667MT/s | 1         | 1.18%   |
| Timetec RAM SD3-1333 8192MB SODIMM DDR3 1333MT/s              | 1         | 1.18%   |
| SK hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s       | 1         | 1.18%   |
| SK hynix RAM Module 4096MB Row Of Chips LPDDR3 2133MT/s       | 1         | 1.18%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 1         | 1.18%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s        | 1         | 1.18%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s        | 1         | 1.18%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s       | 1         | 1.18%   |
| SK hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s       | 1         | 1.18%   |
| SK hynix RAM HMA81GS6MFR8N-UH 8GB SODIMM DDR4 2400MT/s        | 1         | 1.18%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s        | 1         | 1.18%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                   | 1         | 1.18%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR4 2933MT/s           | 1         | 1.18%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                   | 1         | 1.18%   |
| Samsung RAM Module 4GB SODIMM DDR3 1067MT/s                   | 1         | 1.18%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                  | 1         | 1.18%   |
| Samsung RAM Module 16384MB SODIMM DDR4 3200MT/s               | 1         | 1.18%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s         | 1         | 1.18%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s         | 1         | 1.18%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s         | 1         | 1.18%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s         | 1         | 1.18%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s         | 1         | 1.18%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s        | 1         | 1.18%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s        | 1         | 1.18%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s         | 1         | 1.18%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s         | 1         | 1.18%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s         | 1         | 1.18%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 40        | 54.79%  |
| DDR3   | 20        | 27.4%   |
| DDR2   | 5         | 6.85%   |
| LPDDR3 | 4         | 5.48%   |
| DDR5   | 2         | 2.74%   |
| SDRAM  | 1         | 1.37%   |
| LPDDR4 | 1         | 1.37%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 47        | 65.28%  |
| DIMM         | 19        | 26.39%  |
| Row Of Chips | 6         | 8.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 35        | 44.3%   |
| 16384 | 17        | 21.52%  |
| 4096  | 15        | 18.99%  |
| 2048  | 8         | 10.13%  |
| 32768 | 2         | 2.53%   |
| 1024  | 2         | 2.53%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 18        | 23.68%  |
| 3200    | 12        | 15.79%  |
| 1600    | 12        | 15.79%  |
| 2400    | 7         | 9.21%   |
| 2133    | 6         | 7.89%   |
| 3600    | 4         | 5.26%   |
| Unknown | 3         | 3.95%   |
| 1333    | 2         | 2.63%   |
| 800     | 2         | 2.63%   |
| 6400    | 1         | 1.32%   |
| 4800    | 1         | 1.32%   |
| 3534    | 1         | 1.32%   |
| 3500    | 1         | 1.32%   |
| 3400    | 1         | 1.32%   |
| 2933    | 1         | 1.32%   |
| 1867    | 1         | 1.32%   |
| 1334    | 1         | 1.32%   |
| 1067    | 1         | 1.32%   |
| 667     | 1         | 1.32%   |

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
| Chicony Electronics                    | 23        | 29.49%  |
| Microdia                               | 10        | 12.82%  |
| IMC Networks                           | 9         | 11.54%  |
| Logitech                               | 5         | 6.41%   |
| Quanta                                 | 4         | 5.13%   |
| Samsung Electronics                    | 3         | 3.85%   |
| Ricoh                                  | 3         | 3.85%   |
| Realtek Semiconductor                  | 3         | 3.85%   |
| Alcor Micro                            | 3         | 3.85%   |
| Sunplus Innovation Technology          | 2         | 2.56%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.56%   |
| Apple                                  | 2         | 2.56%   |
| Acer                                   | 2         | 2.56%   |
| YGTek                                  | 1         | 1.28%   |
| ShineTech                              | 1         | 1.28%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 1.28%   |
| Luxvisions Innotech Limited            | 1         | 1.28%   |
| Lite-On Technology                     | 1         | 1.28%   |
| Huawei Technologies                    | 1         | 1.28%   |
| ALi                                    | 1         | 1.28%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                   | 5         | 6.41%   |
| IMC Networks USB2.0 HD UVC WebCam               | 5         | 6.41%   |
| Samsung Galaxy series, misc. (MTP mode)         | 3         | 3.85%   |
| IMC Networks Integrated Camera                  | 3         | 3.85%   |
| Chicony Integrated Camera                       | 3         | 3.85%   |
| Chicony HD Webcam                               | 3         | 3.85%   |
| Realtek Integrated_Webcam_HD                    | 2         | 2.56%   |
| Quanta HD User Facing                           | 2         | 2.56%   |
| Microdia Integrated Webcam                      | 2         | 2.56%   |
| Logitech B525 HD Webcam                         | 2         | 2.56%   |
| Chicony Integrated Camera (1280x720@30)         | 2         | 2.56%   |
| Chicony HP Wide Vision HD Camera                | 2         | 2.56%   |
| Chicony HP HD Camera                            | 2         | 2.56%   |
| YGTek Webcam                                    | 1         | 1.28%   |
| Sunplus Laptop Integrated WebCam HD             | 1         | 1.28%   |
| Sunplus HP HD Webcam [Fixed]                    | 1         | 1.28%   |
| ShineTech HD Camera                             | 1         | 1.28%   |
| Shenzhen Kingcome Optoelectronic 720p HD Camera | 1         | 1.28%   |
| Ricoh USB2.0 Camera                             | 1         | 1.28%   |
| Ricoh Sony Visual Communication Camera          | 1         | 1.28%   |
| Ricoh Sony Vaio Integrated Webcam               | 1         | 1.28%   |
| Realtek HP Truevision HD                        | 1         | 1.28%   |
| Quanta HP Wide Vision HD Camera                 | 1         | 1.28%   |
| Quanta HP Webcam                                | 1         | 1.28%   |
| Microdia Webcam                                 | 1         | 1.28%   |
| Microdia USB 2.0 Camera                         | 1         | 1.28%   |
| Microdia Integrated_Webcam_FHD                  | 1         | 1.28%   |
| Luxvisions Innotech Limited HP HD Camera        | 1         | 1.28%   |
| Logitech Webcam C270                            | 1         | 1.28%   |
| Logitech HD Webcam C910                         | 1         | 1.28%   |
| Logitech HD Pro Webcam C920                     | 1         | 1.28%   |
| Lite-On HP Full-HD Camera                       | 1         | 1.28%   |
| IMC Networks ov9734_azurewave_camera            | 1         | 1.28%   |
| Huawei HiCamera                                 | 1         | 1.28%   |
| Chicony USB2.0 VGA UVC WebCam                   | 1         | 1.28%   |
| Chicony USB2.0 HD UVC WebCam                    | 1         | 1.28%   |
| Chicony USB 2.0 Camera                          | 1         | 1.28%   |
| Chicony TOSHIBA Web Camera - HD                 | 1         | 1.28%   |
| Chicony ThinkPad T490 Webcam                    | 1         | 1.28%   |
| Chicony Integrated HP HD Webcam                 | 1         | 1.28%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


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

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


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

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 5         | 50%     |
| Gemalto (was Gemplus) | 3         | 30%     |
| Broadcom              | 2         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


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

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 76        | 60.32%  |
| 1     | 35        | 27.78%  |
| 2     | 13        | 10.32%  |
| 3     | 2         | 1.59%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 21        | 32.81%  |
| Graphics card            | 12        | 18.75%  |
| Multimedia controller    | 6         | 9.38%   |
| Chipcard                 | 6         | 9.38%   |
| Network                  | 4         | 6.25%   |
| Net/wireless             | 4         | 6.25%   |
| Communication controller | 3         | 4.69%   |
| Card reader              | 3         | 4.69%   |
| Unassigned class         | 1         | 1.56%   |
| Sound                    | 1         | 1.56%   |
| Net/ethernet             | 1         | 1.56%   |
| Camera                   | 1         | 1.56%   |
| Bluetooth                | 1         | 1.56%   |

